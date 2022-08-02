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

Total: 220

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Ubuntu 20.04      | 13       | 9.29%   |
| Ubuntu 18.04      | 10       | 7.14%   |
| Pop!_OS 20.04     | 9        | 6.43%   |
| BlackPanther 18.1 | 7        | 5%      |
| Zorin 15          | 5        | 3.57%   |
| KDE neon 20.04    | 5        | 3.57%   |
| Endless 3.7.7     | 5        | 3.57%   |
| Ubuntu 22.04      | 4        | 2.86%   |
| Pop!_OS 21.04     | 4        | 2.86%   |
| Pop!_OS 20.10     | 4        | 2.86%   |
| Endless 3.7.6     | 4        | 2.86%   |
| OpenMandriva 4.3  | 3        | 2.14%   |
| OpenMandriva 4.2  | 3        | 2.14%   |
| Linux Mint 20.2   | 3        | 2.14%   |
| Linux Mint 20.1   | 3        | 2.14%   |
| Fedora 32         | 3        | 2.14%   |
| BlackPanther 16.2 | 3        | 2.14%   |
| Ubuntu 21.10      | 2        | 1.43%   |
| Manjaro           | 2        | 1.43%   |
| Linux Mint 19.3   | 2        | 1.43%   |
| Kali 2021.4       | 2        | 1.43%   |
| Fedora 33         | 2        | 1.43%   |
| Endless 3.9.4     | 2        | 1.43%   |
| Endless 3.3.20    | 2        | 1.43%   |
| Debian 10         | 2        | 1.43%   |
| Xubuntu 20.04     | 1        | 0.71%   |
| Xubuntu 19.10     | 1        | 0.71%   |
| Ubuntu MATE 18.04 | 1        | 0.71%   |
| Ubuntu 19.10      | 1        | 0.71%   |
| Solus 4.3         | 1        | 0.71%   |
| ROSA R11          | 1        | 0.71%   |
| ROSA R10          | 1        | 0.71%   |
| Reborn OS         | 1        | 0.71%   |
| Pop!_OS 22.04     | 1        | 0.71%   |
| Peppermint 10     | 1        | 0.71%   |
| MX 20             | 1        | 0.71%   |
| Manjaro 21.3.1    | 1        | 0.71%   |
| Manjaro 21.2.4    | 1        | 0.71%   |
| Manjaro 21.2.3    | 1        | 0.71%   |
| Manjaro 21.1.5    | 1        | 0.71%   |
| Manjaro 21.0.3    | 1        | 0.71%   |
| LMDE 4            | 1        | 0.71%   |
| Linux Mint 20.3   | 1        | 0.71%   |
| Linux Mint 20     | 1        | 0.71%   |
| Linux Mint 19.1   | 1        | 0.71%   |
| Kubuntu 18.04     | 1        | 0.71%   |
| Kali 2022.1       | 1        | 0.71%   |
| Kali 2021.2       | 1        | 0.71%   |
| Hash Linux        | 1        | 0.71%   |
| Gentoo 2.7        | 1        | 0.71%   |
| Garuda Linux      | 1        | 0.71%   |
| Fedora 36         | 1        | 0.71%   |
| Fedora 35         | 1        | 0.71%   |
| Fedora 34         | 1        | 0.71%   |
| Endless 3.9.1     | 1        | 0.71%   |
| Endless 3.6.0     | 1        | 0.71%   |
| Elementary 5.1.7  | 1        | 0.71%   |
| Elementary 5.0    | 1        | 0.71%   |
| Debian 9          | 1        | 0.71%   |
| BunsenLabs 10.5   | 1        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Ubuntu       | 29       | 21.8%   |
| Pop!_OS      | 18       | 13.53%  |
| Endless      | 14       | 10.53%  |
| Linux Mint   | 10       | 7.52%   |
| Fedora       | 8        | 6.02%   |
| BlackPanther | 8        | 6.02%   |
| OpenMandriva | 6        | 4.51%   |
| Manjaro      | 6        | 4.51%   |
| Zorin        | 5        | 3.76%   |
| KDE neon     | 5        | 3.76%   |
| Kali         | 3        | 2.26%   |
| Debian       | 3        | 2.26%   |
| Xubuntu      | 2        | 1.5%    |
| ROSA         | 2        | 1.5%    |
| Elementary   | 2        | 1.5%    |
| Ubuntu MATE  | 1        | 0.75%   |
| Solus        | 1        | 0.75%   |
| Reborn OS    | 1        | 0.75%   |
| Peppermint   | 1        | 0.75%   |
| MX           | 1        | 0.75%   |
| LMDE         | 1        | 0.75%   |
| Kubuntu      | 1        | 0.75%   |
| Hash Linux   | 1        | 0.75%   |
| Gentoo       | 1        | 0.75%   |
| Garuda Linux | 1        | 0.75%   |
| BunsenLabs   | 1        | 0.75%   |
| Arch         | 1        | 0.75%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Desktops | Percent |
|----------------------------|----------|---------|
| 4.18.16-desktop-1bP        | 7        | 4.64%   |
| 5.8.0-7630-generic         | 6        | 3.97%   |
| 5.3.0-28-generic           | 6        | 3.97%   |
| 5.3.0-23-generic           | 4        | 2.65%   |
| 5.4.0-7634-generic         | 3        | 1.99%   |
| 5.4.0-58-generic           | 3        | 1.99%   |
| 5.16.7-desktop-1omv4003    | 3        | 1.99%   |
| 5.10.14-desktop-1omv4002   | 3        | 1.99%   |
| 4.9.20-desktop-pae-1bP     | 3        | 1.99%   |
| 5.8.0-36-generic           | 2        | 1.32%   |
| 5.8.0-14-generic           | 2        | 1.32%   |
| 5.4.0-80-generic           | 2        | 1.32%   |
| 5.4.0-73-generic           | 2        | 1.32%   |
| 5.4.0-65-generic           | 2        | 1.32%   |
| 5.3.0-46-generic           | 2        | 1.32%   |
| 5.15.0-41-generic          | 2        | 1.32%   |
| 5.15.0-27-generic          | 2        | 1.32%   |
| 5.13.0-7620-generic        | 2        | 1.32%   |
| 5.13.0-35-generic          | 2        | 1.32%   |
| 5.13.0-30-generic          | 2        | 1.32%   |
| 4.18.0-18-generic          | 2        | 1.32%   |
| 4.13.0-32-generic          | 2        | 1.32%   |
| 5.9.14-100.fc32.x86_64     | 1        | 0.66%   |
| 5.9.11-zen2-1-zen          | 1        | 0.66%   |
| 5.8.8-200.fc32.x86_64      | 1        | 0.66%   |
| 5.8.4-200.fc32.x86_64      | 1        | 0.66%   |
| 5.8.18-300.fc33.x86_64     | 1        | 0.66%   |
| 5.8.0-7642-generic         | 1        | 0.66%   |
| 5.8.0-7625-generic         | 1        | 0.66%   |
| 5.8.0-55-generic           | 1        | 0.66%   |
| 5.8.0-41-generic           | 1        | 0.66%   |
| 5.8.0-40-generic           | 1        | 0.66%   |
| 5.7.11-200.fc32.x86_64     | 1        | 0.66%   |
| 5.4.70                     | 1        | 0.66%   |
| 5.4.0-99-generic           | 1        | 0.66%   |
| 5.4.0-81-generic           | 1        | 0.66%   |
| 5.4.0-7642-generic         | 1        | 0.66%   |
| 5.4.0-74-generic           | 1        | 0.66%   |
| 5.4.0-67-generic           | 1        | 0.66%   |
| 5.4.0-66-generic           | 1        | 0.66%   |
| 5.4.0-64-generic           | 1        | 0.66%   |
| 5.4.0-52-generic           | 1        | 0.66%   |
| 5.4.0-51-generic           | 1        | 0.66%   |
| 5.4.0-48-generic           | 1        | 0.66%   |
| 5.4.0-42-generic           | 1        | 0.66%   |
| 5.4.0-26-generic           | 1        | 0.66%   |
| 5.4.0-122-generic          | 1        | 0.66%   |
| 5.4.0-113-generic          | 1        | 0.66%   |
| 5.3.0-62-generic           | 1        | 0.66%   |
| 5.3.0-53-generic           | 1        | 0.66%   |
| 5.3.0-51-generic           | 1        | 0.66%   |
| 5.3.0-42-lowlatency        | 1        | 0.66%   |
| 5.3.0-1007-oracle          | 1        | 0.66%   |
| 5.18.13-200.fc36.x86_64    | 1        | 0.66%   |
| 5.17.5-76051705-generic    | 1        | 0.66%   |
| 5.17.5-200.fc35.x86_64     | 1        | 0.66%   |
| 5.16.0-kali1-amd64         | 1        | 0.66%   |
| 5.16.0-18.1-liquorix-amd64 | 1        | 0.66%   |
| 5.15.5-custom              | 1        | 0.66%   |
| 5.15.49-1-MANJARO          | 1        | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 23       | 16.08%  |
| 5.8.0   | 15       | 10.49%  |
| 5.3.0   | 15       | 10.49%  |
| 5.13.0  | 10       | 6.99%   |
| 4.15.0  | 8        | 5.59%   |
| 4.18.16 | 7        | 4.9%    |
| 5.15.0  | 6        | 4.2%    |
| 5.11.0  | 5        | 3.5%    |
| 5.16.7  | 3        | 2.1%    |
| 5.10.14 | 3        | 2.1%    |
| 5.0.0   | 3        | 2.1%    |
| 4.9.20  | 3        | 2.1%    |
| 4.19.0  | 3        | 2.1%    |
| 4.18.0  | 3        | 2.1%    |
| 5.17.5  | 2        | 1.4%    |
| 5.16.0  | 2        | 1.4%    |
| 5.10.0  | 2        | 1.4%    |
| 4.13.0  | 2        | 1.4%    |
| 5.9.14  | 1        | 0.7%    |
| 5.9.11  | 1        | 0.7%    |
| 5.8.8   | 1        | 0.7%    |
| 5.8.4   | 1        | 0.7%    |
| 5.8.18  | 1        | 0.7%    |
| 5.7.11  | 1        | 0.7%    |
| 5.4.70  | 1        | 0.7%    |
| 5.18.13 | 1        | 0.7%    |
| 5.15.5  | 1        | 0.7%    |
| 5.15.49 | 1        | 0.7%    |
| 5.15.41 | 1        | 0.7%    |
| 5.15.32 | 1        | 0.7%    |
| 5.15.26 | 1        | 0.7%    |
| 5.15.21 | 1        | 0.7%    |
| 5.14.14 | 1        | 0.7%    |
| 5.13.12 | 1        | 0.7%    |
| 5.11.16 | 1        | 0.7%    |
| 5.10.8  | 1        | 0.7%    |
| 5.10.70 | 1        | 0.7%    |
| 5.10.49 | 1        | 0.7%    |
| 5.10.42 | 1        | 0.7%    |
| 5.10.4  | 1        | 0.7%    |
| 5.10.36 | 1        | 0.7%    |
| 5.10.3  | 1        | 0.7%    |
| 5.10.10 | 1        | 0.7%    |
| 5.1.15  | 1        | 0.7%    |
| 4.9.60  | 1        | 0.7%    |
| 4.9.182 | 1        | 0.7%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 24       | 17.02%  |
| 5.8     | 18       | 12.77%  |
| 5.3     | 15       | 10.64%  |
| 5.10    | 12       | 8.51%   |
| 5.15    | 11       | 7.8%    |
| 5.13    | 11       | 7.8%    |
| 4.18    | 10       | 7.09%   |
| 4.15    | 8        | 5.67%   |
| 5.11    | 6        | 4.26%   |
| 5.16    | 5        | 3.55%   |
| 4.9     | 5        | 3.55%   |
| 5.0     | 3        | 2.13%   |
| 4.19    | 3        | 2.13%   |
| 5.9     | 2        | 1.42%   |
| 5.17    | 2        | 1.42%   |
| 4.13    | 2        | 1.42%   |
| 5.7     | 1        | 0.71%   |
| 5.18    | 1        | 0.71%   |
| 5.14    | 1        | 0.71%   |
| 5.1     | 1        | 0.71%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 125      | 95.42%  |
| i686   | 5        | 3.82%   |
| armv7l | 1        | 0.76%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 61       | 45.52%  |
| KDE5            | 28       | 20.9%   |
| XFCE            | 11       | 8.21%   |
| Unknown         | 10       | 7.46%   |
| X-Cinnamon      | 7        | 5.22%   |
| Unity           | 3        | 2.24%   |
| MATE            | 3        | 2.24%   |
| KDE             | 3        | 2.24%   |
| LXQt            | 2        | 1.49%   |
| Pantheon        | 1        | 0.75%   |
| openbox         | 1        | 0.75%   |
| LXDE            | 1        | 0.75%   |
| GNOME Flashback | 1        | 0.75%   |
| Budgie          | 1        | 0.75%   |
| awesome         | 1        | 0.75%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 115      | 87.79%  |
| Wayland | 6        | 4.58%   |
| Tty     | 5        | 3.82%   |
| Unknown | 5        | 3.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 82       | 61.19%  |
| SDDM    | 25       | 18.66%  |
| LightDM | 10       | 7.46%   |
| GDM3    | 9        | 6.72%   |
| GDM     | 6        | 4.48%   |
| TDM     | 2        | 1.49%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_PH   | 62       | 46.97%  |
| en_US   | 48       | 36.36%  |
| Unknown | 18       | 13.64%  |
| C       | 3        | 2.27%   |
| de_DE   | 1        | 0.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 81       | 61.36%  |
| EFI  | 51       | 38.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 107      | 79.26%  |
| Overlay | 12       | 8.89%   |
| Btrfs   | 11       | 8.15%   |
| Unknown | 4        | 2.96%   |
| Xfs     | 1        | 0.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 86       | 63.7%   |
| GPT     | 31       | 22.96%  |
| MBR     | 18       | 13.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 110      | 80.29%  |
| Yes       | 27       | 19.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 99       | 72.26%  |
| Yes       | 38       | 27.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 30       | 23.26%  |
| MSI                 | 27       | 20.93%  |
| ASUSTek Computer    | 24       | 18.6%   |
| ASRock              | 9        | 6.98%   |
| Hewlett-Packard     | 6        | 4.65%   |
| Dell                | 6        | 4.65%   |
| Foxconn             | 5        | 3.88%   |
| ECS                 | 4        | 3.1%    |
| Biostar             | 4        | 3.1%    |
| EMAXX TECHNOLOGY    | 3        | 2.33%   |
| Pegatron            | 2        | 1.55%   |
| YANYU               | 1        | 0.78%   |
| TriGem Computer     | 1        | 0.78%   |
| QTQD                | 1        | 0.78%   |
| NEC Computers       | 1        | 0.78%   |
| Lenovo              | 1        | 0.78%   |
| JOOYON              | 1        | 0.78%   |
| AMD                 | 1        | 0.78%   |
| Acer                | 1        | 0.78%   |
| Unknown             | 1        | 0.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| MSI MS-7721                         | 4        | 3.1%    |
| MSI MS-7309                         | 4        | 3.1%    |
| ASUS All Series                     | 4        | 3.1%    |
| Gigabyte F2A68HM-S1                 | 3        | 2.33%   |
| Foxconn G31MX Series                | 3        | 2.33%   |
| ASUS P8H61-M LX3 PLUS R2.0          | 3        | 2.33%   |
| ASRock B450M Steel Legend           | 3        | 2.33%   |
| Pegatron IPMSB-H61                  | 2        | 1.55%   |
| Gigabyte Z590 AORUS ULTRA           | 2        | 1.55%   |
| Gigabyte A320M-S2H V2               | 2        | 1.55%   |
| Foxconn 500B Microtower             | 2        | 1.55%   |
| ASUS PRIME B250M-K                  | 2        | 1.55%   |
| ASUS EX-H310M-V3 R2.0               | 2        | 1.55%   |
| Unknown                             | 2        | 1.55%   |
| YANYU EPIC-C19                      | 1        | 0.78%   |
| TriGem DreamSys                     | 1        | 0.78%   |
| NEC Computers PC-MK36LBZCHEAM       | 1        | 0.78%   |
| MSI MS-7D43                         | 1        | 0.78%   |
| MSI MS-7D23                         | 1        | 0.78%   |
| MSI MS-7D22                         | 1        | 0.78%   |
| MSI MS-7D18                         | 1        | 0.78%   |
| MSI MS-7C94                         | 1        | 0.78%   |
| MSI MS-7C52                         | 1        | 0.78%   |
| MSI MS-7C02                         | 1        | 0.78%   |
| MSI MS-7B89                         | 1        | 0.78%   |
| MSI MS-7A57                         | 1        | 0.78%   |
| MSI MS-7A38                         | 1        | 0.78%   |
| MSI MS-7A36                         | 1        | 0.78%   |
| MSI MS-7978                         | 1        | 0.78%   |
| MSI MS-7918                         | 1        | 0.78%   |
| MSI MS-7914                         | 1        | 0.78%   |
| MSI MS-7817                         | 1        | 0.78%   |
| MSI AY702AA-A2K p6390d              | 1        | 0.78%   |
| MSI A55PV.AR3510D                   | 1        | 0.78%   |
| MSI *NP                             | 1        | 0.78%   |
| MSI *MF                             | 1        | 0.78%   |
| Lenovo IdeaCentre Q190 10115        | 1        | 0.78%   |
| JOOYON IPM41-D3                     | 1        | 0.78%   |
| HP Z640 Workstation                 | 1        | 0.78%   |
| HP ProDesk 600 G2 SFF               | 1        | 0.78%   |
| HP ProDesk 400 G3 MT                | 1        | 0.78%   |
| HP Compaq dc7900 Small Form Factor  | 1        | 0.78%   |
| HP Compaq dc7700 Ultra-slim Desktop | 1        | 0.78%   |
| HP 200-010                          | 1        | 0.78%   |
| Gigabyte Z97N-WIFI                  | 1        | 0.78%   |
| Gigabyte Z77X-UD5H                  | 1        | 0.78%   |
| Gigabyte Z370M D3H                  | 1        | 0.78%   |
| Gigabyte X570 AORUS PRO WIFI        | 1        | 0.78%   |
| Gigabyte X299 UD4 Pro               | 1        | 0.78%   |
| Gigabyte MZGLKCP-00                 | 1        | 0.78%   |
| Gigabyte H97M-D3H                   | 1        | 0.78%   |
| Gigabyte H81M-DS2                   | 1        | 0.78%   |
| Gigabyte H81M-D2V                   | 1        | 0.78%   |
| Gigabyte H61M-DS2                   | 1        | 0.78%   |
| Gigabyte H410M H V3                 | 1        | 0.78%   |
| Gigabyte H310M DS2                  | 1        | 0.78%   |
| Gigabyte GA-MA78GM-US2H             | 1        | 0.78%   |
| Gigabyte GA-78LMT-S2 R2             | 1        | 0.78%   |
| Gigabyte G41M-Combo                 | 1        | 0.78%   |
| Gigabyte F2A78M-HD2                 | 1        | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Dell OptiPlex                 | 6        | 4.65%   |
| ASUS P8H61-M                  | 5        | 3.88%   |
| MSI MS-7721                   | 4        | 3.1%    |
| MSI MS-7309                   | 4        | 3.1%    |
| ASUS PRIME                    | 4        | 3.1%    |
| ASUS All                      | 4        | 3.1%    |
| Gigabyte F2A68HM-S1           | 3        | 2.33%   |
| Gigabyte A320M-S2H            | 3        | 2.33%   |
| Foxconn G31MX                 | 3        | 2.33%   |
| ASRock B450M                  | 3        | 2.33%   |
| Pegatron IPMSB-H61            | 2        | 1.55%   |
| HP ProDesk                    | 2        | 1.55%   |
| HP Compaq                     | 2        | 1.55%   |
| Gigabyte Z590                 | 2        | 1.55%   |
| Gigabyte B450                 | 2        | 1.55%   |
| Foxconn 500B                  | 2        | 1.55%   |
| ASUS EX-H310M-V3              | 2        | 1.55%   |
| Unknown                       | 2        | 1.55%   |
| YANYU EPIC-C19                | 1        | 0.78%   |
| TriGem DreamSys               | 1        | 0.78%   |
| NEC Computers PC-MK36LBZCHEAM | 1        | 0.78%   |
| MSI MS-7D43                   | 1        | 0.78%   |
| MSI MS-7D23                   | 1        | 0.78%   |
| MSI MS-7D22                   | 1        | 0.78%   |
| MSI MS-7D18                   | 1        | 0.78%   |
| MSI MS-7C94                   | 1        | 0.78%   |
| MSI MS-7C52                   | 1        | 0.78%   |
| MSI MS-7C02                   | 1        | 0.78%   |
| MSI MS-7B89                   | 1        | 0.78%   |
| MSI MS-7A57                   | 1        | 0.78%   |
| MSI MS-7A38                   | 1        | 0.78%   |
| MSI MS-7A36                   | 1        | 0.78%   |
| MSI MS-7978                   | 1        | 0.78%   |
| MSI MS-7918                   | 1        | 0.78%   |
| MSI MS-7914                   | 1        | 0.78%   |
| MSI MS-7817                   | 1        | 0.78%   |
| MSI AY702AA-A2K               | 1        | 0.78%   |
| MSI A55PV.AR3510D             | 1        | 0.78%   |
| MSI *NP                       | 1        | 0.78%   |
| MSI *MF                       | 1        | 0.78%   |
| Lenovo IdeaCentre             | 1        | 0.78%   |
| JOOYON IPM41-D3               | 1        | 0.78%   |
| HP Z640                       | 1        | 0.78%   |
| HP 200-010                    | 1        | 0.78%   |
| Gigabyte Z97N-WIFI            | 1        | 0.78%   |
| Gigabyte Z77X-UD5H            | 1        | 0.78%   |
| Gigabyte Z370M                | 1        | 0.78%   |
| Gigabyte X570                 | 1        | 0.78%   |
| Gigabyte X299                 | 1        | 0.78%   |
| Gigabyte MZGLKCP-00           | 1        | 0.78%   |
| Gigabyte H97M-D3H             | 1        | 0.78%   |
| Gigabyte H81M-DS2             | 1        | 0.78%   |
| Gigabyte H81M-D2V             | 1        | 0.78%   |
| Gigabyte H61M-DS2             | 1        | 0.78%   |
| Gigabyte H410M                | 1        | 0.78%   |
| Gigabyte H310M                | 1        | 0.78%   |
| Gigabyte GA-MA78GM-US2H       | 1        | 0.78%   |
| Gigabyte GA-78LMT-S2          | 1        | 0.78%   |
| Gigabyte G41M-Combo           | 1        | 0.78%   |
| Gigabyte F2A78M-HD2           | 1        | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2014    | 17       | 13.18%  |
| 2015    | 12       | 9.3%    |
| 2010    | 12       | 9.3%    |
| 2017    | 11       | 8.53%   |
| 2013    | 11       | 8.53%   |
| 2018    | 10       | 7.75%   |
| 2012    | 10       | 7.75%   |
| 2019    | 8        | 6.2%    |
| 2021    | 7        | 5.43%   |
| 2020    | 7        | 5.43%   |
| 2009    | 7        | 5.43%   |
| 2007    | 7        | 5.43%   |
| 2011    | 4        | 3.1%    |
| 2016    | 3        | 2.33%   |
| 2008    | 2        | 1.55%   |
| Unknown | 1        | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 129      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 125      | 96.9%   |
| Enabled  | 4        | 3.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 129      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 34       | 25.19%  |
| 3.01-4.0    | 30       | 22.22%  |
| 16.01-24.0  | 23       | 17.04%  |
| 4.01-8.0    | 20       | 14.81%  |
| 32.01-64.0  | 9        | 6.67%   |
| 1.01-2.0    | 7        | 5.19%   |
| 2.01-3.0    | 5        | 3.7%    |
| 64.01-256.0 | 5        | 3.7%    |
| 24.01-32.0  | 2        | 1.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Desktops | Percent |
|-----------|----------|---------|
| 1.01-2.0  | 51       | 35.42%  |
| 2.01-3.0  | 32       | 22.22%  |
| 4.01-8.0  | 21       | 14.58%  |
| 0.51-1.0  | 16       | 11.11%  |
| 3.01-4.0  | 11       | 7.64%   |
| 0.01-0.5  | 7        | 4.86%   |
| 8.01-16.0 | 6        | 4.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 66       | 47.83%  |
| 2      | 44       | 31.88%  |
| 4      | 11       | 7.97%   |
| 3      | 9        | 6.52%   |
| 5      | 5        | 3.62%   |
| 0      | 2        | 1.45%   |
| 13     | 1        | 0.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 102      | 75%     |
| Yes       | 34       | 25%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 129      | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 80       | 60.61%  |
| Yes       | 52       | 39.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 103      | 79.84%  |
| Yes       | 26       | 20.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Philippines | 129      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Quezon City       | 32       | 22.07%  |
| Davao City        | 10       | 6.9%    |
| Cagayan de Oro    | 10       | 6.9%    |
| Iligan City       | 6        | 4.14%   |
| Bacolod City      | 6        | 4.14%   |
| Angeles City      | 6        | 4.14%   |
| San Miguel        | 5        | 3.45%   |
| Santa Rosa        | 4        | 2.76%   |
| Cebu City         | 4        | 2.76%   |
| Bacoor            | 4        | 2.76%   |
| Zamboanga City    | 3        | 2.07%   |
| Mandaluyong City  | 3        | 2.07%   |
| Manajao           | 3        | 2.07%   |
| Lipa City         | 3        | 2.07%   |
| Pasig             | 2        | 1.38%   |
| Paranaque City    | 2        | 1.38%   |
| Manila            | 2        | 1.38%   |
| Mandaue City      | 2        | 1.38%   |
| Makati City       | 2        | 1.38%   |
| Magugpo Poblacion | 2        | 1.38%   |
| Imus              | 2        | 1.38%   |
| Caloocan City     | 2        | 1.38%   |
| Antipolo City     | 2        | 1.38%   |
| Abaga             | 2        | 1.38%   |
| Tuguegarao City   | 1        | 0.69%   |
| Taytay            | 1        | 0.69%   |
| Tarlac City       | 1        | 0.69%   |
| Taguig            | 1        | 0.69%   |
| Sibulan           | 1        | 0.69%   |
| San Fernando City | 1        | 0.69%   |
| San Carlos        | 1        | 0.69%   |
| Nagcarlan         | 1        | 0.69%   |
| Marikina City     | 1        | 0.69%   |
| Malolos           | 1        | 0.69%   |
| Lucena City       | 1        | 0.69%   |
| Lapu-Lapu City    | 1        | 0.69%   |
| Lahug             | 1        | 0.69%   |
| Iloilo City       | 1        | 0.69%   |
| Ilagan            | 1        | 0.69%   |
| General Santos    | 1        | 0.69%   |
| Dumaguete         | 1        | 0.69%   |
| Dasmarinas        | 1        | 0.69%   |
| Daet              | 1        | 0.69%   |
| Cauayan           | 1        | 0.69%   |
| Carmona           | 1        | 0.69%   |
| Cainta            | 1        | 0.69%   |
| Cabanatuan City   | 1        | 0.69%   |
| Bubog             | 1        | 0.69%   |
| Alicia            | 1        | 0.69%   |
| Abuno             | 1        | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 53       | 80     | 25.12%  |
| WDC                   | 41       | 58     | 19.43%  |
| Toshiba               | 17       | 22     | 8.06%   |
| Hitachi               | 14       | 27     | 6.64%   |
| Samsung Electronics   | 13       | 21     | 6.16%   |
| Kingston              | 13       | 19     | 6.16%   |
| SanDisk               | 7        | 8      | 3.32%   |
| Lexar                 | 5        | 6      | 2.37%   |
| Gigabyte Technology   | 5        | 6      | 2.37%   |
| Team                  | 4        | 5      | 1.9%    |
| Unknown               | 3        | 4      | 1.42%   |
| Transcend             | 3        | 3      | 1.42%   |
| HGST                  | 3        | 3      | 1.42%   |
| Crucial               | 3        | 5      | 1.42%   |
| A-DATA Technology     | 3        | 3      | 1.42%   |
| XPG                   | 2        | 2      | 0.95%   |
| WALRAM                | 2        | 2      | 0.95%   |
| SK hynix              | 2        | 8      | 0.95%   |
| Intel                 | 2        | 3      | 0.95%   |
| Fujitsu               | 2        | 2      | 0.95%   |
| ZOTAC                 | 1        | 1      | 0.47%   |
| XrayDisk              | 1        | 1      | 0.47%   |
| Voyager               | 1        | 1      | 0.47%   |
| T-FORCE               | 1        | 1      | 0.47%   |
| Realtek Semiconductor | 1        | 1      | 0.47%   |
| PNY                   | 1        | 1      | 0.47%   |
| Phison                | 1        | 1      | 0.47%   |
| Kingmax               | 1        | 1      | 0.47%   |
| Kimtigo               | 1        | 2      | 0.47%   |
| Indilinx              | 1        | 1      | 0.47%   |
| HS-SSD-E100           | 1        | 1      | 0.47%   |
| Hikvision             | 1        | 2      | 0.47%   |
| GLOWAY                | 1        | 1      | 0.47%   |
| FORESEE               | 1        | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST1000DM010-2EP102 1TB   | 10       | 4.12%   |
| Seagate ST500DM002-1BD142 500GB  | 9        | 3.7%    |
| Toshiba DT01ACA050 500GB         | 7        | 2.88%   |
| Seagate ST4000DM004-2CV104 4TB   | 5        | 2.06%   |
| Hitachi HDS721050CLA362 500GB    | 5        | 2.06%   |
| WDC WD10EZEX-08WN4A0 1TB         | 4        | 1.65%   |
| Samsung SSD 860 EVO 250GB        | 4        | 1.65%   |
| Kingston SA400S37120G 120GB SSD  | 4        | 1.65%   |
| Hitachi HDS721616PLA380 160GB    | 4        | 1.65%   |
| WDC WD5000AZLX-60K2TA0 500GB     | 3        | 1.23%   |
| WDC WD10EZEX-22MFCA0 1TB         | 3        | 1.23%   |
| Toshiba MQ01ABD100 1TB           | 3        | 1.23%   |
| Toshiba DT01ACA100 1TB           | 3        | 1.23%   |
| Seagate ST500DM002-1ER14C 500GB  | 3        | 1.23%   |
| Seagate ST3160812AS 160GB        | 3        | 1.23%   |
| Samsung SSD 860 EVO 500GB        | 3        | 1.23%   |
| Lexar 128GB SSD                  | 3        | 1.23%   |
| Hitachi HTS543232A7A384 320GB    | 3        | 1.23%   |
| WDC WD5003ABYZ-011FA0 500GB      | 2        | 0.82%   |
| WDC WD20EARX-00ZUDB0 2TB         | 2        | 0.82%   |
| WDC WD10EZEX-08M2NA0 1TB         | 2        | 0.82%   |
| WDC WD10EZEX-00BN5A0 1TB         | 2        | 0.82%   |
| Transcend TS128GSSD370S 128GB    | 2        | 0.82%   |
| Toshiba THNSNJ128G8NU 128GB SSD  | 2        | 0.82%   |
| Team T253X2256G 256GB SSD        | 2        | 0.82%   |
| Seagate ST3500312CS 500GB        | 2        | 0.82%   |
| Seagate ST31000524AS 1TB         | 2        | 0.82%   |
| Seagate ST2000DM008-2FR102 2TB   | 2        | 0.82%   |
| Seagate ST1000DM003-9YN162 1TB   | 2        | 0.82%   |
| Seagate ST1000DM003-1CH162 1TB   | 2        | 0.82%   |
| SanDisk SDSSDA240G 240GB         | 2        | 0.82%   |
| Samsung SSD 970 EVO Plus 500GB   | 2        | 0.82%   |
| Kingston SV300S37A120G 120GB SSD | 2        | 0.82%   |
| Kingston SA400S37240G 240GB SSD  | 2        | 0.82%   |
| Hitachi HDT725025VLA380 250GB    | 2        | 0.82%   |
| Hitachi HDT722525DLA380 250GB    | 2        | 0.82%   |
| HGST HTS725050A7E630 500GB       | 2        | 0.82%   |
| Gigabyte GP-GSTFS31120GNTD 120GB | 2        | 0.82%   |
| Gigabyte GP-AG41TB               | 2        | 0.82%   |
| Fujitsu MHW2080BH 80GB           | 2        | 0.82%   |
| Crucial CT500P2SSD8 500GB        | 2        | 0.82%   |
| A-DATA SU800 256GB SSD           | 2        | 0.82%   |
| ZOTAC ZTSSD-S11-120G-P 120GB     | 1        | 0.41%   |
| XrayDisk 128GB                   | 1        | 0.41%   |
| XPG NVMe SSD Drive 2TB           | 1        | 0.41%   |
| XPG NVMe SSD Drive 1024GB        | 1        | 0.41%   |
| WDC WDS500G2B0A 500GB SSD        | 1        | 0.41%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD | 1        | 0.41%   |
| WDC WDS250G2B0A-00SM50 250GB SSD | 1        | 0.41%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 1        | 0.41%   |
| WDC WD800JD-00MSA1 80GB          | 1        | 0.41%   |
| WDC WD6400AAKS-00A7B2 640GB      | 1        | 0.41%   |
| WDC WD5000LPVX-08V0TT5 500GB     | 1        | 0.41%   |
| WDC WD5000AVDS-63U7B1 500GB      | 1        | 0.41%   |
| WDC WD5000AAVS-57ZTB0 500GB      | 1        | 0.41%   |
| WDC WD5000AAVS-00ZTB0 500GB      | 1        | 0.41%   |
| WDC WD5000AAKX-603CA0 500GB      | 1        | 0.41%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1        | 0.41%   |
| WDC WD40EFRX-68WT0N0 4TB         | 1        | 0.41%   |
| WDC WD40EFRX-68N32N0 4TB         | 1        | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 53       | 79     | 40.46%  |
| WDC                 | 40       | 52     | 30.53%  |
| Toshiba             | 17       | 20     | 12.98%  |
| Hitachi             | 14       | 27     | 10.69%  |
| HGST                | 3        | 3      | 2.29%   |
| Fujitsu             | 2        | 2      | 1.53%   |
| Unknown             | 1        | 1      | 0.76%   |
| Samsung Electronics | 1        | 2      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 12       | 17     | 18.18%  |
| Samsung Electronics | 10       | 16     | 15.15%  |
| SanDisk             | 7        | 8      | 10.61%  |
| WDC                 | 4        | 6      | 6.06%   |
| Team                | 4        | 5      | 6.06%   |
| Lexar               | 4        | 5      | 6.06%   |
| Transcend           | 3        | 3      | 4.55%   |
| A-DATA Technology   | 3        | 3      | 4.55%   |
| Toshiba             | 2        | 2      | 3.03%   |
| SK hynix            | 2        | 8      | 3.03%   |
| Intel               | 2        | 3      | 3.03%   |
| Gigabyte Technology | 2        | 2      | 3.03%   |
| ZOTAC               | 1        | 1      | 1.52%   |
| WALRAM              | 1        | 1      | 1.52%   |
| Unknown             | 1        | 2      | 1.52%   |
| PNY                 | 1        | 1      | 1.52%   |
| Kingmax             | 1        | 1      | 1.52%   |
| Kimtigo             | 1        | 2      | 1.52%   |
| HS-SSD-E100         | 1        | 1      | 1.52%   |
| Hikvision           | 1        | 2      | 1.52%   |
| GLOWAY              | 1        | 1      | 1.52%   |
| FORESEE             | 1        | 1      | 1.52%   |
| Crucial             | 1        | 2      | 1.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 104      | 186    | 58.1%   |
| SSD     | 54       | 93     | 30.17%  |
| NVMe    | 15       | 18     | 8.38%   |
| Unknown | 5        | 5      | 2.79%   |
| MMC     | 1        | 1      | 0.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 122      | 276    | 85.31%  |
| NVMe | 15       | 18     | 10.49%  |
| SAS  | 5        | 8      | 3.5%    |
| MMC  | 1        | 1      | 0.7%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 103      | 186    | 64.38%  |
| 0.51-1.0   | 38       | 70     | 23.75%  |
| 1.01-2.0   | 10       | 12     | 6.25%   |
| 3.01-4.0   | 9        | 11     | 5.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 42       | 29.58%  |
| 251-500        | 35       | 24.65%  |
| 501-1000       | 12       | 8.45%   |
| 51-100         | 10       | 7.04%   |
| More than 3000 | 9        | 6.34%   |
| 1001-2000      | 9        | 6.34%   |
| 1-20           | 8        | 5.63%   |
| 2001-3000      | 6        | 4.23%   |
| Unknown        | 6        | 4.23%   |
| 21-50          | 5        | 3.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 52       | 36.36%  |
| 21-50          | 26       | 18.18%  |
| 101-250        | 19       | 13.29%  |
| 51-100         | 17       | 11.89%  |
| 501-1000       | 7        | 4.9%    |
| 251-500        | 6        | 4.2%    |
| Unknown        | 6        | 4.2%    |
| 2001-3000      | 5        | 3.5%    |
| 1001-2000      | 3        | 2.1%    |
| More than 3000 | 2        | 1.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| Hitachi HDS721050CLA362 500GB   | 5        | 10     | 23.81%  |
| Hitachi HTS543232A7A384 320GB   | 3        | 5      | 14.29%  |
| WDC WD5003ABYZ-011FA0 500GB     | 1        | 1      | 4.76%   |
| WDC WD5000AAKX-603CA0 500GB     | 1        | 1      | 4.76%   |
| WDC WD3200AAJS-08L7A0 320GB     | 1        | 1      | 4.76%   |
| Unknown S050 Hard drive 500GB   | 1        | 1      | 4.76%   |
| Toshiba MQ01ABD100 1TB          | 1        | 1      | 4.76%   |
| Toshiba DT01ACA100 1TB          | 1        | 1      | 4.76%   |
| Toshiba DT01ACA050 500GB        | 1        | 1      | 4.76%   |
| Seagate ST500DM002-1BD142 500GB | 1        | 2      | 4.76%   |
| Seagate ST380815AS 80GB         | 1        | 1      | 4.76%   |
| Seagate ST3500514NS 500GB       | 1        | 1      | 4.76%   |
| Seagate ST3500418AS 500GB       | 1        | 1      | 4.76%   |
| Hitachi HDS721050CLA660 500GB   | 1        | 1      | 4.76%   |
| HGST HTS541010A9E680 1TB        | 1        | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 6        | 16     | 35.29%  |
| Seagate | 4        | 5      | 23.53%  |
| WDC     | 3        | 3      | 17.65%  |
| Toshiba | 2        | 3      | 11.76%  |
| Unknown | 1        | 1      | 5.88%   |
| HGST    | 1        | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Hitachi | 6        | 16     | 35.29%  |
| Seagate | 4        | 5      | 23.53%  |
| WDC     | 3        | 3      | 17.65%  |
| Toshiba | 2        | 3      | 11.76%  |
| Unknown | 1        | 1      | 5.88%   |
| HGST    | 1        | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 29     | 100%    |

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
| Detected | 84       | 196    | 61.76%  |
| Works    | 38       | 78     | 27.94%  |
| Malfunc  | 14       | 29     | 10.29%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 77       | 52.74%  |
| AMD                         | 43       | 29.45%  |
| Nvidia                      | 7        | 4.79%   |
| Phison Electronics          | 5        | 3.42%   |
| Samsung Electronics         | 3        | 2.05%   |
| Micron/Crucial Technology   | 2        | 1.37%   |
| Marvell Technology Group    | 2        | 1.37%   |
| ADATA Technology            | 2        | 1.37%   |
| Silicon Motion              | 1        | 0.68%   |
| Realtek Semiconductor       | 1        | 0.68%   |
| Kingston Technology Company | 1        | 0.68%   |
| Broadcom / LSI              | 1        | 0.68%   |
| ASMedia Technology          | 1        | 0.68%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 24       | 11.82%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13       | 6.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 13       | 6.4%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 12       | 5.91%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9        | 4.43%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9        | 4.43%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 8        | 3.94%   |
| Nvidia MCP61 SATA Controller                                                            | 7        | 3.45%   |
| Nvidia MCP61 IDE                                                                        | 7        | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 3.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 3.45%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 2.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5        | 2.46%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5        | 2.46%   |
| AMD FCH SATA Controller D                                                               | 5        | 2.46%   |
| AMD FCH IDE Controller                                                                  | 5        | 2.46%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4        | 1.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4        | 1.97%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3        | 1.48%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 1.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 2        | 0.99%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2        | 0.99%   |
| Intel SATA Controller [RAID mode]                                                       | 2        | 0.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 2        | 0.99%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2        | 0.99%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2        | 0.99%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 1        | 0.49%   |
| Samsung NVMe SSD Controller 980                                                         | 1        | 0.49%   |
| Realtek Realtek Non-Volatile memory controller                                          | 1        | 0.49%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1        | 0.49%   |
| Phison Electronics Non-Volatile memory controller                                       | 1        | 0.49%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 1        | 0.49%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 1        | 0.49%   |
| Kingston Company A2000 NVMe SSD                                                         | 1        | 0.49%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 1        | 0.49%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1        | 0.49%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 1        | 0.49%   |
| Intel C610/X99 series chipset sSATA Controller [RAID mode]                              | 1        | 0.49%   |
| Intel C600/X79 series chipset SATA RAID Controller                                      | 1        | 0.49%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 1        | 0.49%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 1        | 0.49%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1        | 0.49%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 1        | 0.49%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 1        | 0.49%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 1        | 0.49%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1        | 0.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 1        | 0.49%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 1        | 0.49%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 1        | 0.49%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 1        | 0.49%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 1        | 0.49%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 1        | 0.49%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 1        | 0.49%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                                     | 1        | 0.49%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 1        | 0.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1        | 0.49%   |
| AMD RS690 PCI to PCI Bridge (PCI Express Port 2)                                        | 1        | 0.49%   |
| AMD FCH RAID Controller                                                                 | 1        | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 93       | 60%     |
| IDE  | 42       | 27.1%   |
| NVMe | 15       | 9.68%   |
| RAID | 4        | 2.58%   |
| SAS  | 1        | 0.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 78       | 60.47%  |
| AMD    | 50       | 38.76%  |
| ARM    | 1        | 0.78%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 5        | 3.88%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4        | 3.1%    |
| AMD Ryzen 5 2600 Six-Core Processor           | 4        | 3.1%    |
| AMD Sempron Processor LE-1100                 | 3        | 2.33%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3        | 2.33%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 3        | 2.33%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 3        | 2.33%   |
| AMD A6-6400K APU with Radeon HD Graphics      | 3        | 2.33%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2        | 1.55%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 2        | 1.55%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2        | 1.55%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 2        | 1.55%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 2        | 1.55%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2        | 1.55%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 2        | 1.55%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 2        | 1.55%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2        | 1.55%   |
| Intel Core i3-4170 CPU @ 3.70GHz              | 2        | 1.55%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2        | 1.55%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 2        | 1.55%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz         | 2        | 1.55%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2        | 1.55%   |
| Intel 11th Gen Core i9-11900K @ 3.50GHz       | 2        | 1.55%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2        | 1.55%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 2        | 1.55%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2        | 1.55%   |
| AMD A10-5800K APU with Radeon HD Graphics     | 2        | 1.55%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz           | 1        | 0.78%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz        | 1        | 0.78%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1        | 0.78%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 1        | 0.78%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 1        | 0.78%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 1        | 0.78%   |
| Intel Pentium CPU G2020 @ 2.90GHz             | 1        | 0.78%   |
| Intel Core i9-10850K CPU @ 3.60GHz            | 1        | 0.78%   |
| Intel Core i7-7800X CPU @ 3.50GHz             | 1        | 0.78%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 1        | 0.78%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 1        | 0.78%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 1        | 0.78%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 1        | 0.78%   |
| Intel Core i5-8500 CPU @ 3.00GHz              | 1        | 0.78%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 1        | 0.78%   |
| Intel Core i5-7600K CPU @ 3.80GHz             | 1        | 0.78%   |
| Intel Core i5-6500T CPU @ 2.50GHz             | 1        | 0.78%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 1        | 0.78%   |
| Intel Core i5-4690K CPU @ 3.50GHz             | 1        | 0.78%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 1        | 0.78%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 1        | 0.78%   |
| Intel Core i5 CPU 760 @ 2.80GHz               | 1        | 0.78%   |
| Intel Core i5 CPU 750 @ 2.67GHz               | 1        | 0.78%   |
| Intel Core i3-9100F CPU @ 3.60GHz             | 1        | 0.78%   |
| Intel Core i3-4160T CPU @ 3.10GHz             | 1        | 0.78%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 1        | 0.78%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 1        | 0.78%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 1        | 0.78%   |
| Intel Core i3-3210 CPU @ 3.20GHz              | 1        | 0.78%   |
| Intel Core i3-10105F CPU @ 3.70GHz            | 1        | 0.78%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 1        | 0.78%   |
| Intel Core 2 Duo CPU E8300 @ 2.83GHz          | 1        | 0.78%   |
| Intel Core 2 Duo CPU E6850 @ 3.00GHz          | 1        | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 21       | 16.28%  |
| Intel Core i7           | 14       | 10.85%  |
| Intel Core i3           | 13       | 10.08%  |
| AMD Ryzen 5             | 12       | 9.3%    |
| Intel Core 2 Duo        | 9        | 6.98%   |
| AMD A6                  | 7        | 5.43%   |
| Other                   | 6        | 4.65%   |
| Intel Pentium Dual-Core | 4        | 3.1%    |
| Intel Celeron           | 4        | 3.1%    |
| AMD Ryzen 7             | 4        | 3.1%    |
| AMD Ryzen 3             | 4        | 3.1%    |
| AMD A8                  | 4        | 3.1%    |
| Intel Core 2 Quad       | 3        | 2.33%   |
| AMD Sempron             | 3        | 2.33%   |
| AMD FX                  | 3        | 2.33%   |
| AMD A10                 | 3        | 2.33%   |
| Intel Pentium Gold      | 2        | 1.55%   |
| Intel Pentium           | 2        | 1.55%   |
| AMD Phenom II X4        | 2        | 1.55%   |
| AMD Athlon II X2        | 2        | 1.55%   |
| AMD A4                  | 2        | 1.55%   |
| Intel Xeon              | 1        | 0.78%   |
| Intel Core i9           | 1        | 0.78%   |
| AMD Phenom II X2        | 1        | 0.78%   |
| AMD Athlon 64 X2        | 1        | 0.78%   |
| AMD Athlon              | 1        | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 48       | 37.21%  |
| 2      | 46       | 35.66%  |
| 6      | 15       | 11.63%  |
| 1      | 11       | 8.53%   |
| 8      | 6        | 4.65%   |
| 16     | 1        | 0.78%   |
| 10     | 1        | 0.78%   |
| 3      | 1        | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 128      | 99.22%  |
| 2      | 1        | 0.78%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 71       | 55.04%  |
| 1      | 58       | 44.96%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 127      | 97.69%  |
| Unknown        | 3        | 2.31%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 33       | 25.38%  |
| 0x306c3    | 12       | 9.23%   |
| 0x1067a    | 12       | 9.23%   |
| 0x06001119 | 6        | 4.62%   |
| 0x906e9    | 5        | 3.85%   |
| 0x506e3    | 5        | 3.85%   |
| 0x306a9    | 5        | 3.85%   |
| 0x08701021 | 5        | 3.85%   |
| 0x0800820d | 5        | 3.85%   |
| 0x906ea    | 4        | 3.08%   |
| 0x206a7    | 4        | 3.08%   |
| 0x06003106 | 4        | 3.08%   |
| 0xa0671    | 3        | 2.31%   |
| 0x6fb      | 2        | 1.54%   |
| 0x10676    | 2        | 1.54%   |
| 0x0810100b | 2        | 1.54%   |
| 0x010000c8 | 2        | 1.54%   |
| 0xa0655    | 1        | 0.77%   |
| 0xa0653    | 1        | 0.77%   |
| 0x90675    | 1        | 0.77%   |
| 0x706a1    | 1        | 0.77%   |
| 0x50654    | 1        | 0.77%   |
| 0x406f1    | 1        | 0.77%   |
| 0x40651    | 1        | 0.77%   |
| 0x30679    | 1        | 0.77%   |
| 0x106e5    | 1        | 0.77%   |
| 0x08600106 | 1        | 0.77%   |
| 0x08108109 | 1        | 0.77%   |
| 0x08101016 | 1        | 0.77%   |
| 0x08101007 | 1        | 0.77%   |
| 0x0700010f | 1        | 0.77%   |
| 0x0600611a | 1        | 0.77%   |
| 0x06000852 | 1        | 0.77%   |
| 0x03000027 | 1        | 0.77%   |
| 0x010000db | 1        | 0.77%   |
| 0x010000c7 | 1        | 0.77%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 18       | 13.95%  |
| Penryn           | 14       | 10.85%  |
| Piledriver       | 12       | 9.3%    |
| KabyLake         | 10       | 7.75%   |
| Zen+             | 9        | 6.98%   |
| IvyBridge        | 9        | 6.98%   |
| Skylake          | 7        | 5.43%   |
| Zen 2            | 6        | 4.65%   |
| Zen              | 5        | 3.88%   |
| Steamroller      | 5        | 3.88%   |
| SandyBridge      | 5        | 3.88%   |
| K10              | 5        | 3.88%   |
| K8 Hammer        | 4        | 3.1%    |
| CometLake        | 4        | 3.1%    |
| Nehalem          | 2        | 1.55%   |
| Icelake          | 2        | 1.55%   |
| Excavator        | 2        | 1.55%   |
| Core             | 2        | 1.55%   |
| Unknown          | 2        | 1.55%   |
| Silvermont       | 1        | 0.78%   |
| K10 Llano        | 1        | 0.78%   |
| Jaguar           | 1        | 0.78%   |
| Goldmont plus    | 1        | 0.78%   |
| Broadwell        | 1        | 0.78%   |
| Alderlake Hybrid | 1        | 0.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Nvidia | 53       | 37.59%  |
| AMD    | 45       | 31.91%  |
| Intel  | 43       | 30.5%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 4 Series Chipset Integrated Graphics Controller                       | 7        | 4.79%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 6        | 4.11%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                      | 6        | 4.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 6        | 4.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6        | 4.11%   |
| Nvidia GF108 [GeForce GT 730]                                               | 5        | 3.42%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 2.74%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 2.74%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 4        | 2.74%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 4        | 2.74%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 4        | 2.74%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 2.05%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3        | 2.05%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 3        | 2.05%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3        | 2.05%   |
| Intel HD Graphics 630                                                       | 3        | 2.05%   |
| Intel HD Graphics 530                                                       | 3        | 2.05%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 3        | 2.05%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3        | 2.05%   |
| AMD Richland [Radeon HD 8470D]                                              | 3        | 2.05%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 2.05%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 3        | 2.05%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 1.37%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2        | 1.37%   |
| Nvidia GK208B [GeForce GT 730]                                              | 2        | 1.37%   |
| Nvidia GF108 [GeForce GT 630]                                               | 2        | 1.37%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 2        | 1.37%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 2        | 1.37%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 2        | 1.37%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 2        | 1.37%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 2        | 1.37%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 1        | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 1        | 0.68%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 1        | 0.68%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1        | 0.68%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 1        | 0.68%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 1        | 0.68%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1        | 0.68%   |
| Nvidia GK208 [GeForce GT 630 Rev. 2]                                        | 1        | 0.68%   |
| Nvidia GF119 [GeForce GT 610]                                               | 1        | 0.68%   |
| Nvidia GF114 [GeForce GTX 560]                                              | 1        | 0.68%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 1        | 0.68%   |
| Intel VGA compatible controller                                             | 1        | 0.68%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 1        | 0.68%   |
| Intel HD Graphics 510                                                       | 1        | 0.68%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 1        | 0.68%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1        | 0.68%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1        | 0.68%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 1        | 0.68%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                   | 1        | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1        | 0.68%   |
| AMD Trinity [Radeon HD 7660D]                                               | 1        | 0.68%   |
| AMD Trinity 2 [Radeon HD 7540D]                                             | 1        | 0.68%   |
| AMD Tonga PRO [Radeon R9 285/380]                                           | 1        | 0.68%   |
| AMD SuperSumo [Radeon HD 6410D]                                             | 1        | 0.68%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 1        | 0.68%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                           | 1        | 0.68%   |
| AMD RS780 [Radeon HD 3200]                                                  | 1        | 0.68%   |
| AMD Renoir                                                                  | 1        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 47       | 34.81%  |
| 1 x AMD        | 44       | 32.59%  |
| 1 x Intel      | 37       | 27.41%  |
| Intel + Nvidia | 3        | 2.22%   |
| 2 x Nvidia     | 2        | 1.48%   |
| Other          | 1        | 0.74%   |
| 2 x AMD        | 1        | 0.74%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 96       | 73.28%  |
| Proprietary | 28       | 21.37%  |
| Unknown     | 7        | 5.34%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 59       | 43.7%   |
| 1.01-2.0   | 20       | 14.81%  |
| 0.51-1.0   | 16       | 11.85%  |
| 0.01-0.5   | 13       | 9.63%   |
| 3.01-4.0   | 12       | 8.89%   |
| 7.01-8.0   | 5        | 3.7%    |
| 5.01-6.0   | 5        | 3.7%    |
| 8.01-16.0  | 3        | 2.22%   |
| 2.01-3.0   | 2        | 1.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 20       | 15.38%  |
| Dell                 | 19       | 14.62%  |
| AOC                  | 14       | 10.77%  |
| Acer                 | 14       | 10.77%  |
| Hewlett-Packard      | 7        | 5.38%   |
| Ancor Communications | 7        | 5.38%   |
| Goldstar             | 6        | 4.62%   |
| ASUSTek Computer     | 5        | 3.85%   |
| ViewSonic            | 4        | 3.08%   |
| Sony                 | 3        | 2.31%   |
| Lenovo               | 3        | 2.31%   |
| BenQ                 | 3        | 2.31%   |
| VIE                  | 2        | 1.54%   |
| Philips              | 2        | 1.54%   |
| Mi                   | 2        | 1.54%   |
| IPS                  | 2        | 1.54%   |
| eMachines            | 2        | 1.54%   |
| Eizo                 | 2        | 1.54%   |
| Unknown              | 1        | 0.77%   |
| SMC                  | 1        | 0.77%   |
| SGT                  | 1        | 0.77%   |
| NVISION              | 1        | 0.77%   |
| NVI                  | 1        | 0.77%   |
| NEX                  | 1        | 0.77%   |
| MStar                | 1        | 0.77%   |
| MSI                  | 1        | 0.77%   |
| HON                  | 1        | 0.77%   |
| ELSA International   | 1        | 0.77%   |
| CTV                  | 1        | 0.77%   |
| AUS                  | 1        | 0.77%   |
| Unknown              | 1        | 0.77%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 4        | 2.9%    |
| Dell SE177FP DELF001 1280x1024 338x270mm 17.0-inch                    | 4        | 2.9%    |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 4        | 2.9%    |
| Lenovo LT1952p Wide LEN0990 1440x900 408x255mm 18.9-inch              | 3        | 2.17%   |
| Dell P170S DEL4058 1280x1024 338x270mm 17.0-inch                      | 3        | 2.17%   |
| AOC 2060W3 AOC2060 1920x1080 435x239mm 19.5-inch                      | 3        | 2.17%   |
| Ancor Communications ASUS VC239 ACI23C4 1920x1080 509x286mm 23.0-inch | 3        | 2.17%   |
| VIE A/G1956 VIE1850 1366x768 414x257mm 19.2-inch                      | 2        | 1.45%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2        | 1.45%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2        | 1.45%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 2        | 1.45%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 2        | 1.45%   |
| Dell E198FP DELA028 1280x1024 376x301mm 19.0-inch                     | 2        | 1.45%   |
| ASUSTek Computer VG27AQL1A AUS2705 2560x1440 600x340mm 27.2-inch      | 2        | 1.45%   |
| Acer R230H ACR046E 1920x1080 509x286mm 23.0-inch                      | 2        | 1.45%   |
| Acer EB192Q ACR0517 1366x768 410x230mm 18.5-inch                      | 2        | 1.45%   |
| ViewSonic XG2705 VSC0E39 1920x1080 598x336mm 27.0-inch                | 1        | 0.72%   |
| ViewSonic VX2450 SERIES VSCE226 1920x1080 525x297mm 23.7-inch         | 1        | 0.72%   |
| ViewSonic VA1917 SERIES VSCAD30 1366x768 410x230mm 18.5-inch          | 1        | 0.72%   |
| ViewSonic VA1601W-LED VSC1A25 1366x768 344x193mm 15.5-inch            | 1        | 0.72%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 1        | 0.72%   |
| Sony TV SNYAB03 1920x1080                                             | 1        | 0.72%   |
| Sony TV SNYA301 1920x1080                                             | 1        | 0.72%   |
| Sony TV SNY2A01 1360x768                                              | 1        | 0.72%   |
| SMC LCD Monitor SMC0001 1920x540 720x420mm 32.8-inch                  | 1        | 0.72%   |
| SGT Monitor SGT2360 1920x1080 521x299mm 23.6-inch                     | 1        | 0.72%   |
| Samsung Electronics SyncMaster SAM0841 1920x1080 885x498mm 40.0-inch  | 1        | 0.72%   |
| Samsung Electronics SyncMaster SAM0381 1280x1024 338x270mm 17.0-inch  | 1        | 0.72%   |
| Samsung Electronics SyncMaster SAM01A9 1280x1024 338x270mm 17.0-inch  | 1        | 0.72%   |
| Samsung Electronics SMB2230 SAM063F 1920x1080 477x268mm 21.5-inch     | 1        | 0.72%   |
| Samsung Electronics SMB1740R SAM0692 1280x1024 338x270mm 17.0-inch    | 1        | 0.72%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 1        | 0.72%   |
| Samsung Electronics S19B300 SAM08A6 1366x768 410x230mm 18.5-inch      | 1        | 0.72%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                     | 1        | 0.72%   |
| Samsung Electronics LCD Monitor SMB1930N 1366x768                     | 1        | 0.72%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 1        | 0.72%   |
| Samsung Electronics LCD Monitor SAM0B7C 1920x1080 480x270mm 21.7-inch | 1        | 0.72%   |
| Samsung Electronics LCD Monitor S23C350 1920x1080                     | 1        | 0.72%   |
| Samsung Electronics LCD Monitor CF791 3440x1440                       | 1        | 0.72%   |
| Philips PHL 271V8 PHLC213 1920x1080 598x336mm 27.0-inch               | 1        | 0.72%   |
| Philips PHL 242M8 PHLC253 1920x1080 527x296mm 23.8-inch               | 1        | 0.72%   |
| Philips PHL 227E7 PHLC100 1920x1080 476x268mm 21.5-inch               | 1        | 0.72%   |
| NVISION IP240 NVI2400 1920x1080 409x330mm 20.7-inch                   | 1        | 0.72%   |
| NVI IP24V1 NVI2400 1920x1080 520x320mm 24.0-inch                      | 1        | 0.72%   |
| NEX 96VD NEX963D 1366x768 410x230mm 18.5-inch                         | 1        | 0.72%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 1        | 0.72%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch               | 1        | 0.72%   |
| IPS N200HD IPS0200 1600x900 450x240mm 20.1-inch                       | 1        | 0.72%   |
| IPS IP220 IPS2200 1920x1080 409x330mm 20.7-inch                       | 1        | 0.72%   |
| HON HDMI HON3200 1920x1080 699x393mm 31.6-inch                        | 1        | 0.72%   |
| Hewlett-Packard V214b HPN3563 1920x1080 458x258mm 20.7-inch           | 1        | 0.72%   |
| Hewlett-Packard P19b G4 HPN36A0 1366x768 410x230mm 18.5-inch          | 1        | 0.72%   |
| Hewlett-Packard L1710 HWP26EB 1280x1024 340x270mm 17.1-inch           | 1        | 0.72%   |
| Hewlett-Packard E273 HPN3471 1920x1080 598x336mm 27.0-inch            | 1        | 0.72%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch            | 1        | 0.72%   |
| Hewlett-Packard E223 HPN345C 1920x1080 476x268mm 21.5-inch            | 1        | 0.72%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch             | 1        | 0.72%   |
| Goldstar LG QHD GSM772A 2560x1440 700x390mm 31.5-inch                 | 1        | 0.72%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 1        | 0.72%   |
| Goldstar E2750 GSM57DC 1920x1080 510x290mm 23.1-inch                  | 1        | 0.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Desktops | Percent |
|-------------------|----------|---------|
| 1920x1080 (FHD)   | 53       | 42.06%  |
| 1366x768 (WXGA)   | 26       | 20.63%  |
| 1280x1024 (SXGA)  | 14       | 11.11%  |
| 1600x900 (HD+)    | 12       | 9.52%   |
| 3840x2160 (4K)    | 6        | 4.76%   |
| 1440x900 (WXGA+)  | 4        | 3.17%   |
| 2560x1440 (QHD)   | 3        | 2.38%   |
| 3440x1440         | 2        | 1.59%   |
| 1920x1200 (WUXGA) | 2        | 1.59%   |
| 3200x1080         | 1        | 0.79%   |
| 1920x540          | 1        | 0.79%   |
| 1360x768          | 1        | 0.79%   |
| Unknown           | 1        | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 22       | 16.67%  |
| 23      | 16       | 12.12%  |
| 17      | 12       | 9.09%   |
| Unknown | 12       | 9.09%   |
| 24      | 11       | 8.33%   |
| 21      | 11       | 8.33%   |
| 20      | 11       | 8.33%   |
| 19      | 11       | 8.33%   |
| 27      | 9        | 6.82%   |
| 72      | 3        | 2.27%   |
| 32      | 3        | 2.27%   |
| 31      | 3        | 2.27%   |
| 15      | 3        | 2.27%   |
| 40      | 2        | 1.52%   |
| 52      | 1        | 0.76%   |
| 34      | 1        | 0.76%   |
| 22      | 1        | 0.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 49       | 38.89%  |
| 501-600     | 34       | 26.98%  |
| 301-350     | 15       | 11.9%   |
| Unknown     | 12       | 9.52%   |
| 701-800     | 4        | 3.17%   |
| 601-700     | 3        | 2.38%   |
| 351-400     | 3        | 2.38%   |
| 1501-2000   | 3        | 2.38%   |
| 801-900     | 2        | 1.59%   |
| 1001-1500   | 1        | 0.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 85       | 68.55%  |
| 5/4     | 14       | 11.29%  |
| Unknown | 12       | 9.68%   |
| 16/10   | 11       | 8.87%   |
| 6/5     | 1        | 0.81%   |
| 21/9    | 1        | 0.81%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 141-150        | 32       | 25.2%   |
| 201-250        | 29       | 22.83%  |
| 151-200        | 26       | 20.47%  |
| Unknown        | 12       | 9.45%   |
| 301-350        | 9        | 7.09%   |
| 351-500        | 7        | 5.51%   |
| More than 1000 | 4        | 3.15%   |
| 251-300        | 3        | 2.36%   |
| 101-110        | 2        | 1.57%   |
| 501-1000       | 2        | 1.57%   |
| 91-100         | 1        | 0.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 85       | 69.67%  |
| 101-120 | 19       | 15.57%  |
| Unknown | 12       | 9.84%   |
| 1-50    | 5        | 4.1%    |
| 161-240 | 1        | 0.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 106      | 80.92%  |
| 2     | 15       | 11.45%  |
| 0     | 10       | 7.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 96       | 53.33%  |
| Intel                                 | 25       | 13.89%  |
| Ralink Technology                     | 13       | 7.22%   |
| Qualcomm Atheros                      | 12       | 6.67%   |
| TP-Link                               | 6        | 3.33%   |
| Nvidia                                | 5        | 2.78%   |
| Samsung Electronics                   | 3        | 1.67%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 1.67%   |
| Xiaomi                                | 2        | 1.11%   |
| OPPO Electronics                      | 2        | 1.11%   |
| Huawei Technologies                   | 2        | 1.11%   |
| D-Link                                | 2        | 1.11%   |
| Broadcom                              | 2        | 1.11%   |
| Sundance Technology Inc / IC Plus     | 1        | 0.56%   |
| Realtek                               | 1        | 0.56%   |
| Qualcomm Atheros Communications       | 1        | 0.56%   |
| Qualcomm                              | 1        | 0.56%   |
| JMicron Technology                    | 1        | 0.56%   |
| ICS Advent                            | 1        | 0.56%   |
| D-Link System                         | 1        | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                                  | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                                      | 90       | 44.12%  |
| Ralink MT7601U Wireless Adapter                                                                        | 7        | 3.43%   |
| Nvidia MCP61 Ethernet                                                                                  | 5        | 2.45%   |
| Intel Wi-Fi 6 AX200                                                                                    | 4        | 1.96%   |
| Realtek RTL8125 2.5GbE Controller                                                                      | 3        | 1.47%   |
| Realtek 802.11ac NIC                                                                                   | 3        | 1.47%   |
| Intel I211 Gigabit Network Connection                                                                  | 3        | 1.47%   |
| Intel Ethernet Controller I225-V                                                                       | 3        | 1.47%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v1 Dual-Band Wireless-N Network Adapter [Ralink RT2870] | 3        | 1.47%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                            | 2        | 0.98%   |
| Samsung E2530 Phone (Samsung Kies mode)                                                                | 2        | 0.98%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                     | 2        | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                                    | 2        | 0.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                                  | 2        | 0.98%   |
| Ralink RT5370 Wireless Adapter                                                                         | 2        | 0.98%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                                  | 2        | 0.98%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                                      | 2        | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                       | 2        | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                                          | 2        | 0.98%   |
| OPPO SDM720G-IDP _SN:B922E265                                                                          | 2        | 0.98%   |
| Intel Ethernet Connection I217-V                                                                       | 2        | 0.98%   |
| Intel Ethernet Connection (2) I219-V                                                                   | 2        | 0.98%   |
| Intel 82579V Gigabit Network Connection                                                                | 2        | 0.98%   |
| Huawei LYA-L09                                                                                         | 2        | 0.98%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                                         | 1        | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                                                   | 1        | 0.49%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                           | 1        | 0.49%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                                    | 1        | 0.49%   |
| TP-Link 802.11ac WLAN Adapter                                                                          | 1        | 0.49%   |
| TP-Link 802.11ac NIC                                                                                   | 1        | 0.49%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY                             | 1        | 0.49%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                                                       | 1        | 0.49%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                               | 1        | 0.49%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                             | 1        | 0.49%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                                 | 1        | 0.49%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                                  | 1        | 0.49%   |
| Realtek RTL8188EE Wireless Network Adapter                                                             | 1        | 0.49%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                                | 1        | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                                                  | 1        | 0.49%   |
| Realtek 802.11n WLAN Adapter                                                                           | 1        | 0.49%   |
| Realtek 802.11n NIC                                                                                    | 1        | 0.49%   |
| Ralink RT3072 Wireless Adapter                                                                         | 1        | 0.49%   |
| Qualcomm BENGAL-QRD _SN:C5464635                                                                       | 1        | 0.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                             | 1        | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                                              | 1        | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                                              | 1        | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                                              | 1        | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                                              | 1        | 0.49%   |
| Qualcomm Atheros AR9271 802.11n                                                                        | 1        | 0.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                         | 1        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                                               | 1        | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                                             | 1        | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                                         | 1        | 0.49%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                                                    | 1        | 0.49%   |
| Intel Wireless-AC 9260                                                                                 | 1        | 0.49%   |
| Intel Wireless 7260                                                                                    | 1        | 0.49%   |
| Intel Wireless 3165                                                                                    | 1        | 0.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                         | 1        | 0.49%   |
| Intel I210 Gigabit Network Connection                                                                  | 1        | 0.49%   |
| Intel Ethernet Connection I217-LM                                                                      | 1        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 14       | 24.56%  |
| Ralink Technology                     | 13       | 22.81%  |
| Intel                                 | 11       | 19.3%   |
| TP-Link                               | 6        | 10.53%  |
| Qualcomm Atheros                      | 4        | 7.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3        | 5.26%   |
| D-Link                                | 2        | 3.51%   |
| Samsung Electronics                   | 1        | 1.75%   |
| Realtek                               | 1        | 1.75%   |
| Qualcomm Atheros Communications       | 1        | 1.75%   |
| Broadcom                              | 1        | 1.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                                  | Desktops | Percent |
|--------------------------------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                                        | 7        | 12.07%  |
| Intel Wi-Fi 6 AX200                                                                                    | 4        | 6.9%    |
| Realtek 802.11ac NIC                                                                                   | 3        | 5.17%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB600N v1 Dual-Band Wireless-N Network Adapter [Ralink RT2870] | 3        | 5.17%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                            | 2        | 3.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                                     | 2        | 3.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                                    | 2        | 3.45%   |
| Ralink RT5370 Wireless Adapter                                                                         | 2        | 3.45%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                                  | 2        | 3.45%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                                                      | 2        | 3.45%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                       | 2        | 3.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                           | 1        | 1.72%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                                    | 1        | 1.72%   |
| TP-Link 802.11ac WLAN Adapter                                                                          | 1        | 1.72%   |
| TP-Link 802.11ac NIC                                                                                   | 1        | 1.72%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter                                                       | 1        | 1.72%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                               | 1        | 1.72%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                             | 1        | 1.72%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                                 | 1        | 1.72%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                                  | 1        | 1.72%   |
| Realtek RTL8188EE Wireless Network Adapter                                                             | 1        | 1.72%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                                | 1        | 1.72%   |
| Realtek 802.11n WLAN Adapter                                                                           | 1        | 1.72%   |
| Realtek 802.11n NIC                                                                                    | 1        | 1.72%   |
| Ralink RT3072 Wireless Adapter                                                                         | 1        | 1.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                             | 1        | 1.72%   |
| Qualcomm Atheros AR9271 802.11n                                                                        | 1        | 1.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                         | 1        | 1.72%   |
| Intel Wireless-AC 9260                                                                                 | 1        | 1.72%   |
| Intel Wireless 7260                                                                                    | 1        | 1.72%   |
| Intel Wireless 3165                                                                                    | 1        | 1.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                                                         | 1        | 1.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                       | 1        | 1.72%   |
| Intel Comet Lake PCH CNVi WiFi                                                                         | 1        | 1.72%   |
| Intel Alder Lake-S PCH CNVi WiFi                                                                       | 1        | 1.72%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU]                                   | 1        | 1.72%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                                                         | 1        | 1.72%   |
| Broadcom BCM43142 802.11b/g/n                                                                          | 1        | 1.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 96       | 67.61%  |
| Intel                             | 20       | 14.08%  |
| Qualcomm Atheros                  | 9        | 6.34%   |
| Nvidia                            | 5        | 3.52%   |
| Xiaomi                            | 2        | 1.41%   |
| OPPO Electronics                  | 2        | 1.41%   |
| Huawei Technologies               | 2        | 1.41%   |
| Sundance Technology Inc / IC Plus | 1        | 0.7%    |
| Qualcomm                          | 1        | 0.7%    |
| JMicron Technology                | 1        | 0.7%    |
| ICS Advent                        | 1        | 0.7%    |
| D-Link System                     | 1        | 0.7%    |
| Broadcom                          | 1        | 0.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 90       | 62.5%   |
| Nvidia MCP61 Ethernet                                                      | 5        | 3.47%   |
| Realtek RTL8125 2.5GbE Controller                                          | 3        | 2.08%   |
| Intel I211 Gigabit Network Connection                                      | 3        | 2.08%   |
| Intel Ethernet Controller I225-V                                           | 3        | 2.08%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 2        | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 2        | 1.39%   |
| OPPO SDM720G-IDP _SN:B922E265                                              | 2        | 1.39%   |
| Intel Ethernet Connection I217-V                                           | 2        | 1.39%   |
| Intel Ethernet Connection (2) I219-V                                       | 2        | 1.39%   |
| Intel 82579V Gigabit Network Connection                                    | 2        | 1.39%   |
| Huawei LYA-L09                                                             | 2        | 1.39%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 1        | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                       | 1        | 0.69%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 1        | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 1        | 0.69%   |
| Qualcomm BENGAL-QRD _SN:C5464635                                           | 1        | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 1        | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                  | 1        | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 1        | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 1        | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 1        | 0.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 1        | 0.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 1        | 0.69%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                        | 1        | 0.69%   |
| Intel I210 Gigabit Network Connection                                      | 1        | 0.69%   |
| Intel Ethernet Connection I217-LM                                          | 1        | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                                      | 1        | 0.69%   |
| Intel Ethernet Connection (2) I218-V                                       | 1        | 0.69%   |
| Intel Ethernet Connection (2) I218-LM                                      | 1        | 0.69%   |
| Intel Ethernet Connection (10) I219-V                                      | 1        | 0.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 1        | 0.69%   |
| Intel 82574L Gigabit Network Connection                                    | 1        | 0.69%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 1        | 0.69%   |
| Intel 82566DM Gigabit Network Connection                                   | 1        | 0.69%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                    | 1        | 0.69%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                            | 1        | 0.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                            | 1        | 0.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 129      | 70.49%  |
| WiFi     | 52       | 28.42%  |
| Modem    | 2        | 1.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 105      | 77.21%  |
| WiFi     | 31       | 22.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 105      | 80.77%  |
| 2     | 20       | 15.38%  |
| 3     | 5        | 3.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 123      | 93.18%  |
| Yes  | 9        | 6.82%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 10       | 38.46%  |
| Cambridge Silicon Radio    | 8        | 30.77%  |
| Broadcom                   | 4        | 15.38%  |
| Realtek Semiconductor      | 1        | 3.85%   |
| Lite-On Technology         | 1        | 3.85%   |
| Integrated System Solution | 1        | 3.85%   |
| IMC Networks               | 1        | 3.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 8        | 30.77%  |
| Intel AX201 Bluetooth                                 | 3        | 11.54%  |
| Intel AX200 Bluetooth                                 | 3        | 11.54%  |
| Intel Bluetooth wireless interface                    | 2        | 7.69%   |
| Broadcom BCM2035 Bluetooth                            | 2        | 7.69%   |
| Realtek Bluetooth Radio                               | 1        | 3.85%   |
| Lite-On Bluetooth Device                              | 1        | 3.85%   |
| Intel Wireless-AC 3168 Bluetooth                      | 1        | 3.85%   |
| Intel Bluetooth Device                                | 1        | 3.85%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1        | 3.85%   |
| IMC Networks Bluetooth Device                         | 1        | 3.85%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1        | 3.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1        | 3.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 76       | 37.62%  |
| AMD                         | 55       | 27.23%  |
| Nvidia                      | 50       | 24.75%  |
| C-Media Electronics         | 3        | 1.49%   |
| SteelSeries ApS             | 2        | 0.99%   |
| Logitech                    | 2        | 0.99%   |
| GN Netcom                   | 2        | 0.99%   |
| Generalplus Technology      | 2        | 0.99%   |
| DCMT Technology             | 2        | 0.99%   |
| XMOS                        | 1        | 0.5%    |
| Kingston Technology         | 1        | 0.5%    |
| Giga-Byte Technology        | 1        | 0.5%    |
| FiiO Electronics Technology | 1        | 0.5%    |
| FIFINE 683 Microphone       | 1        | 0.5%    |
| Elgato Systems              | 1        | 0.5%    |
| Corsair                     | 1        | 0.5%    |
| Cooler Master               | 1        | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD FCH Azalia Controller                                                         | 17       | 6.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 13       | 5.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 13       | 5.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 10       | 4.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 10       | 4.05%   |
| Intel 200 Series PCH HD Audio                                                     | 10       | 4.05%   |
| AMD Family 17h/19h HD Audio Controller                                            | 8        | 3.24%   |
| Nvidia MCP61 High Definition Audio                                                | 7        | 2.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 7        | 2.83%   |
| Nvidia GF108 High Definition Audio Controller                                     | 7        | 2.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 7        | 2.83%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 6        | 2.43%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 6        | 2.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 5        | 2.02%   |
| AMD Starship/Matisse HD Audio Controller                                          | 5        | 2.02%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 5        | 2.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 5        | 2.02%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 5        | 2.02%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 5        | 2.02%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 5        | 2.02%   |
| Nvidia GP104 High Definition Audio Controller                                     | 4        | 1.62%   |
| Nvidia GA102 High Definition Audio Controller                                     | 4        | 1.62%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 4        | 1.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 4        | 1.62%   |
| AMD Trinity HDMI Audio Controller                                                 | 4        | 1.62%   |
| Nvidia TU116 High Definition Audio Controller                                     | 3        | 1.21%   |
| Nvidia GP106 High Definition Audio Controller                                     | 3        | 1.21%   |
| Intel Audio device                                                                | 3        | 1.21%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 3        | 1.21%   |
| Nvidia GM204 High Definition Audio Controller                                     | 2        | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 2        | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 2        | 0.81%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 2        | 0.81%   |
| Generalplus Technology USB Audio Device                                           | 2        | 0.81%   |
| DCMT Technology USB Condenser Microphone                                          | 2        | 0.81%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 2        | 0.81%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 2        | 0.81%   |
| XMOS X1S USB DAC                                                                  | 1        | 0.4%    |
| SteelSeries ApS SteelSeries Arctis 7                                              | 1        | 0.4%    |
| SteelSeries ApS SteelSeries Arctis 5                                              | 1        | 0.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 1        | 0.4%    |
| Nvidia High Definition Audio Controller                                           | 1        | 0.4%    |
| Nvidia GP108 High Definition Audio Controller                                     | 1        | 0.4%    |
| Nvidia GM206 High Definition Audio Controller                                     | 1        | 0.4%    |
| Nvidia GM200 High Definition Audio                                                | 1        | 0.4%    |
| Nvidia GF119 HDMI Audio Controller                                                | 1        | 0.4%    |
| Nvidia GF114 HDMI Audio Controller                                                | 1        | 0.4%    |
| Nvidia GF106 High Definition Audio Controller                                     | 1        | 0.4%    |
| Logitech USB Headset H540                                                         | 1        | 0.4%    |
| Logitech G633 Gaming Headset                                                      | 1        | 0.4%    |
| Kingston Technology HyperX 7.1 Audio                                              | 1        | 0.4%    |
| Intel Haswell-ULT HD Audio Controller                                             | 1        | 0.4%    |
| Intel Comet Lake PCH cAVS                                                         | 1        | 0.4%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 1        | 0.4%    |
| Intel Cannon Lake PCH cAVS                                                        | 1        | 0.4%    |
| Intel C610/X99 series chipset HD Audio Controller                                 | 1        | 0.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 1        | 0.4%    |
| Intel Alder Lake-S HD Audio Controller                                            | 1        | 0.4%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 1        | 0.4%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 1        | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 15       | 25.42%  |
| Unknown             | 9        | 15.25%  |
| Team                | 6        | 10.17%  |
| G.Skill             | 5        | 8.47%   |
| SK hynix            | 4        | 6.78%   |
| Samsung Electronics | 4        | 6.78%   |
| Patriot             | 2        | 3.39%   |
| Kingmax             | 2        | 3.39%   |
| Corsair             | 2        | 3.39%   |
| Unknown             | 2        | 3.39%   |
| Uroad               | 1        | 1.69%   |
| Transcend           | 1        | 1.69%   |
| Silicon Power       | 1        | 1.69%   |
| PNY                 | 1        | 1.69%   |
| Nanya Technology    | 1        | 1.69%   |
| Mitsubishi          | 1        | 1.69%   |
| Crucial             | 1        | 1.69%   |
| Carry               | 1        | 1.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s          | 3        | 4.84%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s          | 2        | 3.23%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s              | 2        | 3.23%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s         | 2        | 3.23%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s          | 2        | 3.23%   |
| Corsair RAM CMT128GX4M4C3200C16 32GB DIMM DDR4 3200MT/s      | 2        | 3.23%   |
| Unknown                                                      | 2        | 3.23%   |
| Uroad RAM WJD8G4M16P12800 8192MB DIMM DDR3 1600MT/s          | 1        | 1.61%   |
| Unknown RAM Module 8192MB DIMM                               | 1        | 1.61%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 1        | 1.61%   |
| Unknown RAM Module 4GB DIMM DDR4 2133MT/s                    | 1        | 1.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 1        | 1.61%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                         | 1        | 1.61%   |
| Unknown RAM Module 4096MB DIMM DDR2                          | 1        | 1.61%   |
| Unknown RAM Module 1GB DIMM DDR2                             | 1        | 1.61%   |
| Unknown RAM Module 16384MB DIMM DDR4 2666MT/s                | 1        | 1.61%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                  | 1        | 1.61%   |
| Unknown RAM Module 1024MB DIMM DDR2                          | 1        | 1.61%   |
| Unknown RAM KZ24UE5116HAR8 8192MB DIMM DDR4 2400MT/s         | 1        | 1.61%   |
| Transcend RAM TS2GLH64V4B 16384MB DIMM DDR4 2400MT/s         | 1        | 1.61%   |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s           | 1        | 1.61%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s           | 1        | 1.61%   |
| Team RAM TEAMGROUP-UD4-2400 8GB DIMM DDR4 2400MT/s           | 1        | 1.61%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s           | 1        | 1.61%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2133MT/s                | 1        | 1.61%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 1        | 1.61%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s         | 1        | 1.61%   |
| SK hynix RAM HMA81GR7MFR8N-UH 8GB DIMM DDR4 2400MT/s         | 1        | 1.61%   |
| SK hynix RAM HMA81GR7AFR8N-UH 8GB DIMM DDR4 2400MT/s         | 1        | 1.61%   |
| Silicon Power RAM SP008GBLFU266B02 8192MB DIMM DDR4 2400MT/s | 1        | 1.61%   |
| Samsung RAM Module 4096MB DIMM DDR4 2133MT/s                 | 1        | 1.61%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 1        | 1.61%   |
| Samsung RAM M378A1K43CB2-CRC 8192MB DIMM DDR4 3500MT/s       | 1        | 1.61%   |
| Samsung RAM M3 78T2863QZS-CF7 1GB DIMM DDR2 800MT/s          | 1        | 1.61%   |
| PNY RAM 16GF2X08QFHH36-135-K 16GB DIMM DDR4 3200MT/s         | 1        | 1.61%   |
| Nanya RAM NT4GC64B8HG0NF-CG 4GB DIMM 1333MT/s                | 1        | 1.61%   |
| Mitsubishi RAM Module 8GB DIMM DDR3 1600MT/s                 | 1        | 1.61%   |
| Kingston RAM Module 4096MB DIMM DDR3 1600MT/s                | 1        | 1.61%   |
| Kingston RAM Module 16384MB DIMM DDR4 2666MT/s               | 1        | 1.61%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s       | 1        | 1.61%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s          | 1        | 1.61%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s            | 1        | 1.61%   |
| Kingston RAM KHX1866C10D3/4G 4GB DIMM DDR3 1867MT/s          | 1        | 1.61%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s        | 1        | 1.61%   |
| Kingston RAM KF2666C16D4/8G 8192MB DIMM DDR4 2667MT/s        | 1        | 1.61%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s        | 1        | 1.61%   |
| Kingston RAM 99U5403-036.A00LF 4GB DIMM DDR3 1600MT/s        | 1        | 1.61%   |
| Kingmax RAM GLAF62F-DA--------- 4GB DIMM DDR4 2400MT/s       | 1        | 1.61%   |
| Kingmax RAM FLGF65F-D8KJB 4096MB DIMM DDR3 1600MT/s          | 1        | 1.61%   |
| G.Skill RAM F4-3600C16-16GTZNC 16384MB DIMM DDR4 3600MT/s    | 1        | 1.61%   |
| G.Skill RAM F4-2400C15-8GVR 8GB DIMM DDR4 3200MT/s           | 1        | 1.61%   |
| G.Skill RAM F4-2400C15-16GVR 16GB DIMM DDR4 2400MT/s         | 1        | 1.61%   |
| Crucial RAM CT8G4DFS8266.C8FD1 8GB DIMM DDR4 2667MT/s        | 1        | 1.61%   |
| Carry RAM U3A4G93-16GBHN2B00 4096MB DIMM DDR3 1600MT/s       | 1        | 1.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 29       | 55.77%  |
| DDR3    | 17       | 32.69%  |
| DDR2    | 3        | 5.77%   |
| Unknown | 2        | 3.85%   |
| SDRAM   | 1        | 1.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 52       | 98.11%  |
| SODIMM | 1        | 1.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 23       | 41.07%  |
| 4096  | 15       | 26.79%  |
| 16384 | 10       | 17.86%  |
| 32768 | 5        | 8.93%   |
| 1024  | 3        | 5.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 11       | 20.37%  |
| 3200    | 8        | 14.81%  |
| 2133    | 7        | 12.96%  |
| 2400    | 6        | 11.11%  |
| 3600    | 5        | 9.26%   |
| 2667    | 3        | 5.56%   |
| Unknown | 3        | 5.56%   |
| 3466    | 2        | 3.7%    |
| 1800    | 2        | 3.7%    |
| 1333    | 2        | 3.7%    |
| 3733    | 1        | 1.85%   |
| 3500    | 1        | 1.85%   |
| 2666    | 1        | 1.85%   |
| 800     | 1        | 1.85%   |
| 667     | 1        | 1.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Canon              | 2        | 50%     |
| Seiko Epson        | 1        | 25%     |
| Brother Industries | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Desktops | Percent |
|---------------------------|----------|---------|
| Seiko Epson L120 Series   | 1        | 25%     |
| Canon PIXMA MG2500 Series | 1        | 25%     |
| Canon G2010 series        | 1        | 25%     |
| Brother DCP-T700W         | 1        | 25%     |

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
| Z-Star Microelectronics     | 4        | 12.12%  |
| Microdia                    | 4        | 12.12%  |
| Logitech                    | 4        | 12.12%  |
| Jieli Technology            | 4        | 12.12%  |
| Realtek Semiconductor       | 3        | 9.09%   |
| Pixart Imaging              | 3        | 9.09%   |
| Samsung Electronics         | 2        | 6.06%   |
| Cubeternet                  | 2        | 6.06%   |
| A4Tech                      | 2        | 6.06%   |
| Razer USA                   | 1        | 3.03%   |
| KYE Systems (Mouse Systems) | 1        | 3.03%   |
| Generalplus Technology      | 1        | 3.03%   |
| Apple                       | 1        | 3.03%   |
| Alcor Micro                 | 1        | 3.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| Jieli USB PHY 2.0                                | 4        | 12.12%  |
| Z-Star Venus USB2.0 Camera                       | 3        | 9.09%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro             | 3        | 9.09%   |
| Microdia Integrated Camera                       | 2        | 6.06%   |
| Logitech HD Webcam C910                          | 2        | 6.06%   |
| A4Tech FHD 1080P PC Camera                       | 2        | 6.06%   |
| Z-Star A4 TECH USB2.0 PC Camera J                | 1        | 3.03%   |
| Samsung USB2.0 UVC HQ WebCam                     | 1        | 3.03%   |
| Samsung Galaxy A5 (MTP)                          | 1        | 3.03%   |
| Realtek Laptop_Integrated_Webcam_FHD             | 1        | 3.03%   |
| Realtek Front Camera                             | 1        | 3.03%   |
| Realtek BRI-S90AF                                | 1        | 3.03%   |
| Razer USA Gaming Webcam [Kiyo]                   | 1        | 3.03%   |
| Microdia Sonix USB 2.0 Camera                    | 1        | 3.03%   |
| Microdia rapoo camera                            | 1        | 3.03%   |
| Logitech Webcam C270                             | 1        | 3.03%   |
| Logitech HD Webcam B910                          | 1        | 3.03%   |
| KYE Systems (Mouse Systems) AUKEY PC-LM1E Camera | 1        | 3.03%   |
| Generalplus 808 Camera                           | 1        | 3.03%   |
| Cubeternet USB2.0 Camera                         | 1        | 3.03%   |
| Cubeternet GL-UPC822 UVC WebCam                  | 1        | 3.03%   |
| Apple iPhone 5/5C/5S/6/SE                        | 1        | 3.03%   |
| Alcor Micro USB 2.0 PC cam                       | 1        | 3.03%   |

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
| 0     | 111      | 84.73%  |
| 1     | 17       | 12.98%  |
| 2     | 3        | 2.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 8        | 36.36%  |
| Graphics card            | 8        | 36.36%  |
| Unassigned class         | 1        | 4.55%   |
| Storage/raid             | 1        | 4.55%   |
| Network                  | 1        | 4.55%   |
| Net/ethernet             | 1        | 4.55%   |
| Communication controller | 1        | 4.55%   |
| Chipcard                 | 1        | 4.55%   |

