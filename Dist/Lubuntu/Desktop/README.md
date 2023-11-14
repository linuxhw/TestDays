Lubuntu - Tested Hardware & Statistics (Desktops)
-------------------------------------------------

A project to collect tested hardware configurations for Lubuntu.

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

Total: 636

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| PCChips       | P49G                        | [6b1de00356](https://linux-hardware.org/?probe=6b1de00356) | Nov 02, 2023 |
| ZOTAC         | NM10                        | [5a951d80a6](https://linux-hardware.org/?probe=5a951d80a6) | Oct 31, 2023 |
| Dell          | 0WR7PY A02                  | [d63ccd5259](https://linux-hardware.org/?probe=d63ccd5259) | Oct 30, 2023 |
| ASUSTek       | P7P55-M                     | [3fa8a23f12](https://linux-hardware.org/?probe=3fa8a23f12) | Oct 29, 2023 |
| Intel         | H61                         | [fccff5fcb2](https://linux-hardware.org/?probe=fccff5fcb2) | Oct 27, 2023 |
| Acer          | Veriton N4660G              | [712511f568](https://linux-hardware.org/?probe=712511f568) | Oct 27, 2023 |
| Gigabyte      | B75M-D3H                    | [5a23f97862](https://linux-hardware.org/?probe=5a23f97862) | Oct 23, 2023 |
| ZOTAC         | NM10                        | [2e0ab67bec](https://linux-hardware.org/?probe=2e0ab67bec) | Oct 21, 2023 |
| HP            | 8265                        | [f1bdedb075](https://linux-hardware.org/?probe=f1bdedb075) | Oct 20, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [8ff07b1c79](https://linux-hardware.org/?probe=8ff07b1c79) | Oct 19, 2023 |
| MSI           | B550-A PRO                  | [c60b3dbfa2](https://linux-hardware.org/?probe=c60b3dbfa2) | Oct 17, 2023 |
| ASRock        | Q1900B-ITX                  | [f8ad7736e2](https://linux-hardware.org/?probe=f8ad7736e2) | Oct 07, 2023 |
| ASUSTek       | PRIME B450M-A               | [bf8761b854](https://linux-hardware.org/?probe=bf8761b854) | Oct 06, 2023 |
| Dell          | 0JP3NX A01                  | [d14bc5c139](https://linux-hardware.org/?probe=d14bc5c139) | Sep 27, 2023 |
| Intel         | H61                         | [ee0266b53c](https://linux-hardware.org/?probe=ee0266b53c) | Sep 25, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | [7b1aae3e2b](https://linux-hardware.org/?probe=7b1aae3e2b) | Sep 20, 2023 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | [47d423039b](https://linux-hardware.org/?probe=47d423039b) | Sep 19, 2023 |
| Intel         | D945GCZ AAD32112-503        | [806f698174](https://linux-hardware.org/?probe=806f698174) | Sep 14, 2023 |
| ASRock        | X570 Steel Legend           | [04666fa9b7](https://linux-hardware.org/?probe=04666fa9b7) | Sep 11, 2023 |
| ASUSTek       | M4A87TD/USB3                | [6aea4eb6c4](https://linux-hardware.org/?probe=6aea4eb6c4) | Sep 09, 2023 |
| Dell          | 0T10XW A00                  | [89f4028960](https://linux-hardware.org/?probe=89f4028960) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [23f0f9321c](https://linux-hardware.org/?probe=23f0f9321c) | Sep 05, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [69fec63660](https://linux-hardware.org/?probe=69fec63660) | Sep 04, 2023 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | [ea00f871b9](https://linux-hardware.org/?probe=ea00f871b9) | Sep 04, 2023 |
| Acer          | Predator G3610              | [04153b05c7](https://linux-hardware.org/?probe=04153b05c7) | Aug 22, 2023 |
| Gigabyte      | B560 HD3                    | [3dfc4104a4](https://linux-hardware.org/?probe=3dfc4104a4) | Aug 18, 2023 |
| Inventec      | DQ Class A02                | [92a3afc475](https://linux-hardware.org/?probe=92a3afc475) | Aug 17, 2023 |
| Gigabyte      | H510M H                     | [374096baa6](https://linux-hardware.org/?probe=374096baa6) | Aug 15, 2023 |
| ASUSTek       | BM6875_BM6675_BP6375        | [0a2cdad4c1](https://linux-hardware.org/?probe=0a2cdad4c1) | Aug 15, 2023 |
| Apple         | Mac-F223BEC8                | [74a3be9a4a](https://linux-hardware.org/?probe=74a3be9a4a) | Aug 14, 2023 |
| Gigabyte      | H61M-D2H-USB3               | [0028486d9d](https://linux-hardware.org/?probe=0028486d9d) | Aug 10, 2023 |
| Shuttle       | XS35V3                      | [ced8776e4d](https://linux-hardware.org/?probe=ced8776e4d) | Aug 09, 2023 |
| ASUSTek       | P5QD TURBO                  | [ffbbe60721](https://linux-hardware.org/?probe=ffbbe60721) | Aug 05, 2023 |
| Shuttle       | XS35V3                      | [52c5dda710](https://linux-hardware.org/?probe=52c5dda710) | Jul 31, 2023 |
| AAEON         | MF-001 V1.0                 | [1a2d3f1778](https://linux-hardware.org/?probe=1a2d3f1778) | Jul 30, 2023 |
| Unknown       | Unknown                     | [80a34d344b](https://linux-hardware.org/?probe=80a34d344b) | Jul 28, 2023 |
| Unknown       | SCHNEIDER                   | [6ab609f07e](https://linux-hardware.org/?probe=6ab609f07e) | Jul 27, 2023 |
| Unknown       | T3 MRD                      | [5539799efa](https://linux-hardware.org/?probe=5539799efa) | Jul 26, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | [5ca26c7da9](https://linux-hardware.org/?probe=5ca26c7da9) | Jul 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4fe4e8b639](https://linux-hardware.org/?probe=4fe4e8b639) | Jul 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [742d3b24c8](https://linux-hardware.org/?probe=742d3b24c8) | Jul 24, 2023 |
| HP            | 2187 A01                    | [efd197811b](https://linux-hardware.org/?probe=efd197811b) | Jul 22, 2023 |
| HP            | 3646h                       | [01f2207fe0](https://linux-hardware.org/?probe=01f2207fe0) | Jul 22, 2023 |
| ASRock        | 970M Pro3                   | [07809870aa](https://linux-hardware.org/?probe=07809870aa) | Jul 19, 2023 |
| MSI           | A68HM-E33 V2                | [2d896167d8](https://linux-hardware.org/?probe=2d896167d8) | Jul 16, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | [493d7a5ab7](https://linux-hardware.org/?probe=493d7a5ab7) | Jul 12, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [b6b1cf5b68](https://linux-hardware.org/?probe=b6b1cf5b68) | Jul 02, 2023 |
| Dell          | 0T656F A02                  | [e9b879f3ff](https://linux-hardware.org/?probe=e9b879f3ff) | Jul 02, 2023 |
| ASUSTek       | M4A87TD/USB3                | [fa54c60ae0](https://linux-hardware.org/?probe=fa54c60ae0) | Jun 26, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [f0268ac6a8](https://linux-hardware.org/?probe=f0268ac6a8) | Jun 26, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [004f9be7a7](https://linux-hardware.org/?probe=004f9be7a7) | Jun 21, 2023 |
| ASRock        | J4125-ITX                   | [b4c617c995](https://linux-hardware.org/?probe=b4c617c995) | Jun 19, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [f52a0ddf99](https://linux-hardware.org/?probe=f52a0ddf99) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [7b9388df1b](https://linux-hardware.org/?probe=7b9388df1b) | Jun 16, 2023 |
| Pegatron      | 2A73h                       | [a96d9ae076](https://linux-hardware.org/?probe=a96d9ae076) | Jun 15, 2023 |
| HP            | 21B4 A01                    | [16b576ebea](https://linux-hardware.org/?probe=16b576ebea) | Jun 15, 2023 |
| HP            | 3646h                       | [046f5d1a5b](https://linux-hardware.org/?probe=046f5d1a5b) | Jun 09, 2023 |
| HP            | 3646h                       | [02353b5e9f](https://linux-hardware.org/?probe=02353b5e9f) | Jun 06, 2023 |
| HP            | 3397                        | [046df77f81](https://linux-hardware.org/?probe=046df77f81) | Jun 02, 2023 |
| Unknown       | Unknown                     | [a1a76abc51](https://linux-hardware.org/?probe=a1a76abc51) | May 24, 2023 |
| Foxconn       | G41MXE-V                    | [ffc74ae329](https://linux-hardware.org/?probe=ffc74ae329) | May 21, 2023 |
| ASUSTek       | A88XM-A                     | [eea6382d39](https://linux-hardware.org/?probe=eea6382d39) | May 19, 2023 |
| ZOTAC         | NM10                        | [0be7755cf9](https://linux-hardware.org/?probe=0be7755cf9) | May 19, 2023 |
| PCWare        | IPX1800E2                   | [f19d94af88](https://linux-hardware.org/?probe=f19d94af88) | May 18, 2023 |
| PCWare        | IPX1800E2                   | [a75df73ade](https://linux-hardware.org/?probe=a75df73ade) | May 18, 2023 |
| Acer          | EQ45M                       | [57fa86c8dc](https://linux-hardware.org/?probe=57fa86c8dc) | May 11, 2023 |
| ASUSTek       | M4A87TD/USB3                | [5438ddaf64](https://linux-hardware.org/?probe=5438ddaf64) | May 08, 2023 |
| Unknown       | Phitronics N68C-M           | [77747ce79b](https://linux-hardware.org/?probe=77747ce79b) | May 02, 2023 |
| Intel         | DG41RQ AAE54511-203         | [4eb2bc6e88](https://linux-hardware.org/?probe=4eb2bc6e88) | May 01, 2023 |
| NEC Comput... | ECS-945G                    | [5f6daf506f](https://linux-hardware.org/?probe=5f6daf506f) | May 01, 2023 |
| ASUSTek       | F1A55-M LK R2.0             | [234e0d0738](https://linux-hardware.org/?probe=234e0d0738) | Apr 23, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [f79af9bad0](https://linux-hardware.org/?probe=f79af9bad0) | Apr 20, 2023 |
| MSI           | H310M PRO-VD                | [498c52e62e](https://linux-hardware.org/?probe=498c52e62e) | Apr 10, 2023 |
| ASRock        | G31M-S                      | [70f35c82f1](https://linux-hardware.org/?probe=70f35c82f1) | Apr 03, 2023 |
| MSI           | B550-A PRO                  | [f243351def](https://linux-hardware.org/?probe=f243351def) | Mar 31, 2023 |
| ASRock        | G31M-S                      | [4ad324790c](https://linux-hardware.org/?probe=4ad324790c) | Mar 28, 2023 |
| ASRock        | G31M-S                      | [225f122e05](https://linux-hardware.org/?probe=225f122e05) | Mar 28, 2023 |
| YANYU         | ITX-S192                    | [0d2fb6a8d7](https://linux-hardware.org/?probe=0d2fb6a8d7) | Mar 27, 2023 |
| Pegatron      | Acacia                      | [4ce0966b14](https://linux-hardware.org/?probe=4ce0966b14) | Mar 26, 2023 |
| Pegatron      | Acacia                      | [4faa2a52d3](https://linux-hardware.org/?probe=4faa2a52d3) | Mar 26, 2023 |
| ASRock        | N68-GS4/USB3 FX             | [b846b11174](https://linux-hardware.org/?probe=b846b11174) | Mar 25, 2023 |
| ASRock        | H110M-HDV                   | [cfe369e6b8](https://linux-hardware.org/?probe=cfe369e6b8) | Mar 24, 2023 |
| ASRock        | H110M-HDV                   | [5228141efd](https://linux-hardware.org/?probe=5228141efd) | Mar 16, 2023 |
| Gigabyte      | MJPLNBB-00                  | [e8c31757e0](https://linux-hardware.org/?probe=e8c31757e0) | Mar 12, 2023 |
| Positivo      | P5VD2-MX                    | [50b7084313](https://linux-hardware.org/?probe=50b7084313) | Mar 12, 2023 |
| ASRock        | G41M-VS3                    | [309d95f00f](https://linux-hardware.org/?probe=309d95f00f) | Mar 11, 2023 |
| BANGHO        | LITE E34                    | [39f7b525e2](https://linux-hardware.org/?probe=39f7b525e2) | Mar 10, 2023 |
| Gigabyte      | B360M DS3H                  | [3710f0f407](https://linux-hardware.org/?probe=3710f0f407) | Mar 07, 2023 |
| Pegatron      | 2AD5                        | [3356f97e00](https://linux-hardware.org/?probe=3356f97e00) | Mar 06, 2023 |
| ASUSTek       | A7N8X-E                     | [d0847fb118](https://linux-hardware.org/?probe=d0847fb118) | Mar 06, 2023 |
| Pegatron      | 2AD5                        | [86b939ac1a](https://linux-hardware.org/?probe=86b939ac1a) | Mar 03, 2023 |
| ASRock        | Z87 Extreme4                | [d085a259d5](https://linux-hardware.org/?probe=d085a259d5) | Mar 03, 2023 |
| Intel         | X79 V2.72A                  | [ae4efdfbc5](https://linux-hardware.org/?probe=ae4efdfbc5) | Mar 02, 2023 |
| Pegatron      | 2AD5                        | [0f487c3a2a](https://linux-hardware.org/?probe=0f487c3a2a) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | [4c68f5ea84](https://linux-hardware.org/?probe=4c68f5ea84) | Feb 25, 2023 |
| Gigabyte      | B450M S2H                   | [4b440b2084](https://linux-hardware.org/?probe=4b440b2084) | Feb 22, 2023 |
| Pegatron      | 2A73h                       | [835743de83](https://linux-hardware.org/?probe=835743de83) | Feb 21, 2023 |
| Gigabyte      | A320M-H-CF                  | [11739ccfa1](https://linux-hardware.org/?probe=11739ccfa1) | Feb 20, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [1c2d1949fd](https://linux-hardware.org/?probe=1c2d1949fd) | Feb 19, 2023 |
| Gigabyte      | F2A88XM-D3HP                | [edfa765236](https://linux-hardware.org/?probe=edfa765236) | Feb 19, 2023 |
| Gigabyte      | B450M S2H                   | [2420c1fb57](https://linux-hardware.org/?probe=2420c1fb57) | Feb 18, 2023 |
| MSI           | MS-7267                     | [0b89f039c1](https://linux-hardware.org/?probe=0b89f039c1) | Feb 17, 2023 |
| Gigabyte      | B450M S2H                   | [72b29b5f80](https://linux-hardware.org/?probe=72b29b5f80) | Feb 16, 2023 |
| ECS           | G41T-M7                     | [3308b85e2f](https://linux-hardware.org/?probe=3308b85e2f) | Feb 15, 2023 |
| ASUSTek       | M5A78L-M LX3                | [c7374801ac](https://linux-hardware.org/?probe=c7374801ac) | Feb 13, 2023 |
| MSI           | 970A-G46                    | [6012e644eb](https://linux-hardware.org/?probe=6012e644eb) | Feb 13, 2023 |
| HP            | 89D8 SMVB                   | [49d1ea8b3e](https://linux-hardware.org/?probe=49d1ea8b3e) | Feb 11, 2023 |
| Dell          | 0FPP7F A00                  | [0a67b25026](https://linux-hardware.org/?probe=0a67b25026) | Feb 11, 2023 |
| Gigabyte      | H61MA-D2V                   | [380eb0d0e1](https://linux-hardware.org/?probe=380eb0d0e1) | Feb 08, 2023 |
| MSI           | B550-A PRO                  | [55e2abbd96](https://linux-hardware.org/?probe=55e2abbd96) | Feb 04, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [4f6655087b](https://linux-hardware.org/?probe=4f6655087b) | Feb 03, 2023 |
| MSI           | MS-7032                     | [7b481f4c8c](https://linux-hardware.org/?probe=7b481f4c8c) | Jan 25, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [1099a3c6c9](https://linux-hardware.org/?probe=1099a3c6c9) | Jan 24, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [4944e0cddd](https://linux-hardware.org/?probe=4944e0cddd) | Jan 24, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | [27ea4205e5](https://linux-hardware.org/?probe=27ea4205e5) | Jan 22, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | [11964c6701](https://linux-hardware.org/?probe=11964c6701) | Jan 16, 2023 |
| NEC Comput... | ECS-945G                    | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| MSI           | K9A2VM                      | [98ce1d06ad](https://linux-hardware.org/?probe=98ce1d06ad) | Jan 14, 2023 |
| ASRock        | ION3D-HT                    | [48707e3794](https://linux-hardware.org/?probe=48707e3794) | Jan 12, 2023 |
| ASRock        | H110M-HDV                   | [deff7fc898](https://linux-hardware.org/?probe=deff7fc898) | Jan 07, 2023 |
| MSI           | A320M-A PRO                 | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| ASUSTek       | M5A97 PRO                   | [7921dc0197](https://linux-hardware.org/?probe=7921dc0197) | Jan 05, 2023 |
| Dell          | Dimension 4500S             | [5b907b07e4](https://linux-hardware.org/?probe=5b907b07e4) | Jan 05, 2023 |
| Positivo      | POS-AG31AP                  | [a0ef7524c6](https://linux-hardware.org/?probe=a0ef7524c6) | Jan 02, 2023 |
| Positivo      | POS-AG31AP                  | [4cc8fbf002](https://linux-hardware.org/?probe=4cc8fbf002) | Jan 02, 2023 |
| HP            | 21B4 A01                    | [cdc9730e81](https://linux-hardware.org/?probe=cdc9730e81) | Dec 31, 2022 |
| ASRock        | 970DE3/U3S3                 | [1505706e04](https://linux-hardware.org/?probe=1505706e04) | Dec 25, 2022 |
| ASRock        | 970DE3/U3S3                 | [1c996d8122](https://linux-hardware.org/?probe=1c996d8122) | Dec 25, 2022 |
| ZOTAC         | NM10                        | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [5c437c961e](https://linux-hardware.org/?probe=5c437c961e) | Dec 13, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASUSTek       | PRIME A320M-F               | [abe82b0f58](https://linux-hardware.org/?probe=abe82b0f58) | Dec 04, 2022 |
| ASUSTek       | ET1610PT                    | [d8b1840336](https://linux-hardware.org/?probe=d8b1840336) | Dec 03, 2022 |
| ASUSTek       | M4A87TD/USB3                | [e38a783ce1](https://linux-hardware.org/?probe=e38a783ce1) | Nov 28, 2022 |
| Lenovo        | 0B98401 PRO                 | [63487a2957](https://linux-hardware.org/?probe=63487a2957) | Nov 28, 2022 |
| Lenovo        | 0B98401 PRO                 | [0b632b7ae8](https://linux-hardware.org/?probe=0b632b7ae8) | Nov 27, 2022 |
| MSI           | B550M PRO-VDH               | [ba7b5c7748](https://linux-hardware.org/?probe=ba7b5c7748) | Nov 26, 2022 |
| Foxconn       | G41MXP/G41MXP-V             | [f8e0414c84](https://linux-hardware.org/?probe=f8e0414c84) | Nov 26, 2022 |
| Intel         | BTC-T37                     | [f52a08ae38](https://linux-hardware.org/?probe=f52a08ae38) | Nov 25, 2022 |
| MSI           | A520M-A PRO                 | [8db2bc8883](https://linux-hardware.org/?probe=8db2bc8883) | Nov 25, 2022 |
| Unknown       | Unknown                     | [029cddbcd6](https://linux-hardware.org/?probe=029cddbcd6) | Nov 23, 2022 |
| ASUSTek       | IP4BL-ME-Oli                | [242fd5b355](https://linux-hardware.org/?probe=242fd5b355) | Nov 21, 2022 |
| HP            | 3048h                       | [33ced86304](https://linux-hardware.org/?probe=33ced86304) | Nov 19, 2022 |
| HP            | 3048h                       | [e5fdb1f67a](https://linux-hardware.org/?probe=e5fdb1f67a) | Nov 19, 2022 |
| ASUSTek       | M2NPV-VM                    | [db28f53298](https://linux-hardware.org/?probe=db28f53298) | Nov 12, 2022 |
| ASUSTek       | EB1501P                     | [0664261b3a](https://linux-hardware.org/?probe=0664261b3a) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | [ad47bcfb8b](https://linux-hardware.org/?probe=ad47bcfb8b) | Nov 11, 2022 |
| AMI           | Cherry Trail CR             | [f731a55cc1](https://linux-hardware.org/?probe=f731a55cc1) | Nov 05, 2022 |
| ASRock        | FM2A88X Extreme4+           | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| Intel         | D33217GKE G76540-203        | [eb15ca5b98](https://linux-hardware.org/?probe=eb15ca5b98) | Nov 03, 2022 |
| Intel         | D33217GKE G76540-203        | [20824af437](https://linux-hardware.org/?probe=20824af437) | Nov 03, 2022 |
| Lenovo        | NOK                         | [8c9f8ff505](https://linux-hardware.org/?probe=8c9f8ff505) | Nov 03, 2022 |
| Intel         | D33217GKE G76540-203        | [95238cc6e8](https://linux-hardware.org/?probe=95238cc6e8) | Oct 30, 2022 |
| Intel         | D33217GKE G76540-203        | [2501d67199](https://linux-hardware.org/?probe=2501d67199) | Oct 28, 2022 |
| Lenovo        | ThinkCentre M81 5048E2G     | [35840b3b8c](https://linux-hardware.org/?probe=35840b3b8c) | Oct 23, 2022 |
| ASRock        | H110M-HDV                   | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| Gigabyte      | F2A58M-HD2                  | [944509d58b](https://linux-hardware.org/?probe=944509d58b) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | [191540e7bc](https://linux-hardware.org/?probe=191540e7bc) | Oct 12, 2022 |
| Acer          | EM61SM/EM61PM               | [fb2dd76511](https://linux-hardware.org/?probe=fb2dd76511) | Oct 10, 2022 |
| AOpen         | D1007 0BBA                  | [b3597a7cbc](https://linux-hardware.org/?probe=b3597a7cbc) | Oct 10, 2022 |
| Fujitsu       | D3003-D1 S26361-D3003-D1    | [afba95481a](https://linux-hardware.org/?probe=afba95481a) | Oct 09, 2022 |
| HP            | 0B4Ch D                     | [1b409fc1f6](https://linux-hardware.org/?probe=1b409fc1f6) | Oct 01, 2022 |
| HP            | 0B4Ch D                     | [ccc7fe3103](https://linux-hardware.org/?probe=ccc7fe3103) | Oct 01, 2022 |
| ASUSTek       | P8P67                       | [1ad22cf7a8](https://linux-hardware.org/?probe=1ad22cf7a8) | Sep 28, 2022 |
| Dell          | 0PU052                      | [2890a8407e](https://linux-hardware.org/?probe=2890a8407e) | Sep 28, 2022 |
| Dell          | 0R849J A00                  | [cf2069932e](https://linux-hardware.org/?probe=cf2069932e) | Sep 26, 2022 |
| ASUSTek       | Maximus V FORMULA           | [cf8128637b](https://linux-hardware.org/?probe=cf8128637b) | Sep 24, 2022 |
| ASUSTek       | Maximus V FORMULA           | [e63b24acc3](https://linux-hardware.org/?probe=e63b24acc3) | Sep 24, 2022 |
| Intel         | DH67CL AAG10212-210         | [3468d8c911](https://linux-hardware.org/?probe=3468d8c911) | Sep 24, 2022 |
| Dell          | 0PU052                      | [6ca93366df](https://linux-hardware.org/?probe=6ca93366df) | Sep 23, 2022 |
| Dell          | 09M8Y8 A01                  | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| MSI           | B450-A PRO MAX              | [89fad64303](https://linux-hardware.org/?probe=89fad64303) | Sep 20, 2022 |
| Gigabyte      | G31M-S2C                    | [f7f3a2e7c8](https://linux-hardware.org/?probe=f7f3a2e7c8) | Sep 17, 2022 |
| AMI           | Cherry Trail CR             | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| Dell          | 0J584C A00                  | [de442f1c61](https://linux-hardware.org/?probe=de442f1c61) | Sep 01, 2022 |
| Gigabyte      | G31M-S2C                    | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| ASRock        | A520M-HVS                   | [842ad7d4d2](https://linux-hardware.org/?probe=842ad7d4d2) | Aug 22, 2022 |
| MSI           | Z590-A PRO                  | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| ASUSTek       | H110M-CS                    | [df6dff3fa3](https://linux-hardware.org/?probe=df6dff3fa3) | Aug 19, 2022 |
| MSI           | Z170A GAMING M3             | [e0834224d7](https://linux-hardware.org/?probe=e0834224d7) | Aug 16, 2022 |
| ASUSTek       | M5A97 R2.0                  | [c2acc2d803](https://linux-hardware.org/?probe=c2acc2d803) | Aug 10, 2022 |
| ASRock        | G41M-VS3                    | [16a2e0ab5d](https://linux-hardware.org/?probe=16a2e0ab5d) | Aug 09, 2022 |
| ASUSTek       | H110M-CS                    | [98c601bb55](https://linux-hardware.org/?probe=98c601bb55) | Aug 08, 2022 |
| ASUSTek       | H110M-CS                    | [01e4feaac6](https://linux-hardware.org/?probe=01e4feaac6) | Aug 07, 2022 |
| HP            | 8768 A                      | [2ee49e3506](https://linux-hardware.org/?probe=2ee49e3506) | Aug 07, 2022 |
| Lenovo        | BRASWELL SDK0J40697 WIN ... | [f601e2f557](https://linux-hardware.org/?probe=f601e2f557) | Aug 05, 2022 |
| ASRock        | G41M-VS3                    | [16c2b30680](https://linux-hardware.org/?probe=16c2b30680) | Aug 04, 2022 |
| Acer          | EG31M R01-A3                | [c5b4092eb4](https://linux-hardware.org/?probe=c5b4092eb4) | Aug 04, 2022 |
| MSI           | X399 SLI PLUS               | [515c5375c1](https://linux-hardware.org/?probe=515c5375c1) | Jul 31, 2022 |
| Dell          | 0WR7PY A03                  | [0cabe39a74](https://linux-hardware.org/?probe=0cabe39a74) | Jul 27, 2022 |
| MSI           | AMETHYST-M                  | [d5fb610246](https://linux-hardware.org/?probe=d5fb610246) | Jul 26, 2022 |
| Dell          | 0X8582                      | [b52bb428f4](https://linux-hardware.org/?probe=b52bb428f4) | Jul 26, 2022 |
| ASRock        | M3A785GMH/128M              | [87836918b2](https://linux-hardware.org/?probe=87836918b2) | Jul 25, 2022 |
| AMI           | Cherry Trail CR             | [6463c26211](https://linux-hardware.org/?probe=6463c26211) | Jul 25, 2022 |
| ASUSTek       | M5A78L LE                   | [4ade852983](https://linux-hardware.org/?probe=4ade852983) | Jul 23, 2022 |
| Dell          | 0X8582                      | [ab2bf3496e](https://linux-hardware.org/?probe=ab2bf3496e) | Jul 20, 2022 |
| MSI           | H510I PRO WIFI              | [cb9ba02bb3](https://linux-hardware.org/?probe=cb9ba02bb3) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Dell          | 0X8582                      | [5b8458f200](https://linux-hardware.org/?probe=5b8458f200) | Jul 19, 2022 |
| MSI           | X570-A PRO                  | [84b1994696](https://linux-hardware.org/?probe=84b1994696) | Jul 16, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | [21b83125d8](https://linux-hardware.org/?probe=21b83125d8) | Jul 14, 2022 |
| Foxconn       | 2ACA                        | [92681ef1e5](https://linux-hardware.org/?probe=92681ef1e5) | Jul 07, 2022 |
| HP            | 1495                        | [32ea18bc68](https://linux-hardware.org/?probe=32ea18bc68) | Jul 06, 2022 |
| MSI           | A88XM-E35                   | [8767210da3](https://linux-hardware.org/?probe=8767210da3) | Jul 04, 2022 |
| HP            | 1495                        | [6300d25ff0](https://linux-hardware.org/?probe=6300d25ff0) | Jul 04, 2022 |
| Intel         | DQ57TM AAE70931-403         | [92c11e77c4](https://linux-hardware.org/?probe=92c11e77c4) | Jul 03, 2022 |
| MSI           | 760GM-P23                   | [ff0f44e63c](https://linux-hardware.org/?probe=ff0f44e63c) | Jun 26, 2022 |
| Dell          | 0VRWRC A00                  | [fe159bf237](https://linux-hardware.org/?probe=fe159bf237) | Jun 26, 2022 |
| Intel         | DQ57TM AAE70931-403         | [357e062693](https://linux-hardware.org/?probe=357e062693) | Jun 25, 2022 |
| ASUSTek       | M4N78-AM                    | [f98db3efe8](https://linux-hardware.org/?probe=f98db3efe8) | Jun 22, 2022 |
| Gigabyte      | GA-MA69G-S3H                | [2dba47edb2](https://linux-hardware.org/?probe=2dba47edb2) | Jun 18, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [474c946289](https://linux-hardware.org/?probe=474c946289) | Jun 17, 2022 |
| ASUSTek       | M4N78-AM                    | [d7dddc4270](https://linux-hardware.org/?probe=d7dddc4270) | Jun 16, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | [14ed78a258](https://linux-hardware.org/?probe=14ed78a258) | Jun 11, 2022 |
| ASUSTek       | PRIME X370-A                | [bd1889b281](https://linux-hardware.org/?probe=bd1889b281) | Jun 06, 2022 |
| HP            | 3397                        | [2f3fb08195](https://linux-hardware.org/?probe=2f3fb08195) | Jun 03, 2022 |
| Unknown       | Unknown                     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| ASRock        | FM2A85X Extreme6            | [365ff27343](https://linux-hardware.org/?probe=365ff27343) | May 27, 2022 |
| ASRock        | FM2A85X Extreme6            | [00d4dc8661](https://linux-hardware.org/?probe=00d4dc8661) | May 24, 2022 |
| Unknown       | Unknown                     | [aa6db2ed41](https://linux-hardware.org/?probe=aa6db2ed41) | May 23, 2022 |
| Unknown       | HX90                        | [22dac34b7b](https://linux-hardware.org/?probe=22dac34b7b) | May 21, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | [942f142f46](https://linux-hardware.org/?probe=942f142f46) | May 20, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [9254de4361](https://linux-hardware.org/?probe=9254de4361) | May 18, 2022 |
| Lenovo        | NOK                         | [e7a84a12e6](https://linux-hardware.org/?probe=e7a84a12e6) | May 16, 2022 |
| Unknown       | Unknown                     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Dell          | 0CRH6C A00                  | [fe2648c1f7](https://linux-hardware.org/?probe=fe2648c1f7) | May 14, 2022 |
| Pegatron      | VIOLET6                     | [dbbdea4231](https://linux-hardware.org/?probe=dbbdea4231) | May 12, 2022 |
| ASUSTek       | Rampage III GENE            | [798c1f07f6](https://linux-hardware.org/?probe=798c1f07f6) | May 10, 2022 |
| Gigabyte      | G31M-ES2L                   | [bf9f724f45](https://linux-hardware.org/?probe=bf9f724f45) | May 04, 2022 |
| Gigabyte      | G31M-ES2L                   | [05585fedf4](https://linux-hardware.org/?probe=05585fedf4) | May 04, 2022 |
| Acer          | Aspire XC100A               | [dbad5c417d](https://linux-hardware.org/?probe=dbad5c417d) | May 04, 2022 |
| Intel         | DQ57TM AAE70931-403         | [dd1df3c77d](https://linux-hardware.org/?probe=dd1df3c77d) | May 02, 2022 |
| Dell          | 02YYK5 A01                  | [19dd091f8b](https://linux-hardware.org/?probe=19dd091f8b) | May 01, 2022 |
| Dell          | 08NPPY A00                  | [6c4d2173a5](https://linux-hardware.org/?probe=6c4d2173a5) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [a547974d27](https://linux-hardware.org/?probe=a547974d27) | Apr 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [7be2e51c84](https://linux-hardware.org/?probe=7be2e51c84) | Apr 27, 2022 |
| Dell          | 018D1Y A00                  | [705fbe0501](https://linux-hardware.org/?probe=705fbe0501) | Apr 23, 2022 |
| ZOTAC         | NM10                        | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| Gigabyte      | H97-D3H-CF                  | [e9ad69846b](https://linux-hardware.org/?probe=e9ad69846b) | Apr 14, 2022 |
| ASUSTek       | PRIME A320M-F               | [1e81b06f04](https://linux-hardware.org/?probe=1e81b06f04) | Apr 14, 2022 |
| ASRock        | G31M-S                      | [e02bbd85b4](https://linux-hardware.org/?probe=e02bbd85b4) | Apr 10, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [a09ecdae05](https://linux-hardware.org/?probe=a09ecdae05) | Apr 07, 2022 |
| Unknown       | Unknown                     | [4de543bc53](https://linux-hardware.org/?probe=4de543bc53) | Apr 03, 2022 |
| Gigabyte      | Q77M-D2H                    | [ecbd26a0e1](https://linux-hardware.org/?probe=ecbd26a0e1) | Apr 02, 2022 |
| MSI           | 990FXA-GD65                 | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| Unknown       | Unknown                     | [926a8980fc](https://linux-hardware.org/?probe=926a8980fc) | Mar 30, 2022 |
| Lenovo        | ThinkCentre M55p 8811VQV    | [dc2a995551](https://linux-hardware.org/?probe=dc2a995551) | Mar 27, 2022 |
| ASUSTek       | M4N68T-M LE                 | [8d26cd120c](https://linux-hardware.org/?probe=8d26cd120c) | Mar 15, 2022 |
| ASUSTek       | M4N68T-M LE                 | [2ba5a37abd](https://linux-hardware.org/?probe=2ba5a37abd) | Mar 15, 2022 |
| ASRock        | Q1900M                      | [ce28f1e721](https://linux-hardware.org/?probe=ce28f1e721) | Mar 09, 2022 |
| MSI           | MAG B460M MORTAR            | [0e1398474c](https://linux-hardware.org/?probe=0e1398474c) | Mar 09, 2022 |
| ASUSTek       | M2N-SLI                     | [675f15b6db](https://linux-hardware.org/?probe=675f15b6db) | Mar 07, 2022 |
| Intel         | DH87RL AAG74240-403         | [9c8ac31778](https://linux-hardware.org/?probe=9c8ac31778) | Mar 07, 2022 |
| HP            | 3647h                       | [11858412ec](https://linux-hardware.org/?probe=11858412ec) | Mar 06, 2022 |
| Dell          | 0HN7XN A00                  | [ac36138ae4](https://linux-hardware.org/?probe=ac36138ae4) | Mar 04, 2022 |
| ASRock        | H110M-HDV                   | [96416af97f](https://linux-hardware.org/?probe=96416af97f) | Mar 03, 2022 |
| Dell          | 0HN7XN A00                  | [1da1f4ab04](https://linux-hardware.org/?probe=1da1f4ab04) | Mar 03, 2022 |
| HP            | 339A                        | [820ebf5859](https://linux-hardware.org/?probe=820ebf5859) | Feb 26, 2022 |
| HP            | 2AF7                        | [116084cb0a](https://linux-hardware.org/?probe=116084cb0a) | Feb 20, 2022 |
| Dell          | 0DR845                      | [73ab1563bc](https://linux-hardware.org/?probe=73ab1563bc) | Feb 18, 2022 |
| ASUSTek       | PRIME B350M-E               | [70f555009e](https://linux-hardware.org/?probe=70f555009e) | Feb 18, 2022 |
| Pegatron      | Narra6                      | [712b5069b6](https://linux-hardware.org/?probe=712b5069b6) | Feb 17, 2022 |
| Biostar       | H81MHV3 5.0                 | [c70891d986](https://linux-hardware.org/?probe=c70891d986) | Feb 14, 2022 |
| ASRock        | A320M-HDV R4.0              | [27e20ff1d8](https://linux-hardware.org/?probe=27e20ff1d8) | Feb 14, 2022 |
| Gigabyte      | GA-MA69G-S3H                | [7e455c0441](https://linux-hardware.org/?probe=7e455c0441) | Feb 13, 2022 |
| Gigabyte      | G41M-Combo                  | [a72979e0f8](https://linux-hardware.org/?probe=a72979e0f8) | Feb 11, 2022 |
| Intel         | D945GCLF2 AAE46416-103      | [b3977cd496](https://linux-hardware.org/?probe=b3977cd496) | Feb 10, 2022 |
| ASUSTek       | Puffer                      | [a14c8ed9ad](https://linux-hardware.org/?probe=a14c8ed9ad) | Feb 06, 2022 |
| Unknown       | 865G-M8                     | [ecc67cf3bc](https://linux-hardware.org/?probe=ecc67cf3bc) | Feb 06, 2022 |
| Gigabyte      | B450M S2H                   | [1a0186c0a7](https://linux-hardware.org/?probe=1a0186c0a7) | Feb 04, 2022 |
| HP            | 0A80h                       | [ad7e41ed45](https://linux-hardware.org/?probe=ad7e41ed45) | Feb 04, 2022 |
| AAEON         | MF-001 V1.0                 | [01244429c8](https://linux-hardware.org/?probe=01244429c8) | Feb 03, 2022 |
| Acer          | Aspire TC-105               | [638079e113](https://linux-hardware.org/?probe=638079e113) | Feb 03, 2022 |
| Dell          | 0TW904 A01                  | [f80a01d518](https://linux-hardware.org/?probe=f80a01d518) | Jan 30, 2022 |
| Dell          | 0NKW6Y A02                  | [f01b040659](https://linux-hardware.org/?probe=f01b040659) | Jan 30, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | [9b0853e1e9](https://linux-hardware.org/?probe=9b0853e1e9) | Jan 29, 2022 |
| HP            | 3048h                       | [829e0c8a9c](https://linux-hardware.org/?probe=829e0c8a9c) | Jan 25, 2022 |
| HP            | 3048h                       | [5fa883113f](https://linux-hardware.org/?probe=5fa883113f) | Jan 24, 2022 |
| Pegatron      | EVE                         | [06d22ac6e2](https://linux-hardware.org/?probe=06d22ac6e2) | Jan 21, 2022 |
| Pegatron      | EVE                         | [5640f6122a](https://linux-hardware.org/?probe=5640f6122a) | Jan 21, 2022 |
| Unknown       | K8Upgrade-1689              | [d2e29b9e82](https://linux-hardware.org/?probe=d2e29b9e82) | Jan 15, 2022 |
| Dell          | 07N90W A01                  | [c8db7d01bd](https://linux-hardware.org/?probe=c8db7d01bd) | Jan 15, 2022 |
| ASRock        | B450M Pro4 R2.0             | [79e8f681f1](https://linux-hardware.org/?probe=79e8f681f1) | Jan 13, 2022 |
| Acer          | WG43M                       | [af76e9bcfe](https://linux-hardware.org/?probe=af76e9bcfe) | Jan 12, 2022 |
| Acer          | WG43M                       | [5784b66aee](https://linux-hardware.org/?probe=5784b66aee) | Jan 12, 2022 |
| Unknown       | Unknown                     | [a80be6a29f](https://linux-hardware.org/?probe=a80be6a29f) | Jan 12, 2022 |
| Dell          | 02YYK5 A01                  | [e41c34594e](https://linux-hardware.org/?probe=e41c34594e) | Jan 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | [4c24369bb7](https://linux-hardware.org/?probe=4c24369bb7) | Jan 11, 2022 |
| ASUSTek       | P8P67 DELUXE                | [9bd6fe4b7c](https://linux-hardware.org/?probe=9bd6fe4b7c) | Jan 08, 2022 |
| Dell          | 032W55 A03                  | [e68d1bd4aa](https://linux-hardware.org/?probe=e68d1bd4aa) | Jan 04, 2022 |
| Pegatron      | 2AD5                        | [efc0a3875a](https://linux-hardware.org/?probe=efc0a3875a) | Dec 29, 2021 |
| Biostar       | A68N-2100                   | [81f4a18209](https://linux-hardware.org/?probe=81f4a18209) | Dec 26, 2021 |
| ASUSTek       | A8N5X                       | [4786d6b56c](https://linux-hardware.org/?probe=4786d6b56c) | Dec 24, 2021 |
| HP            | 090Ch                       | [bf92e3c728](https://linux-hardware.org/?probe=bf92e3c728) | Dec 22, 2021 |
| AMI           | Cherry Trail Tablet         | [c5c7ca1d56](https://linux-hardware.org/?probe=c5c7ca1d56) | Dec 20, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [c52d7dc596](https://linux-hardware.org/?probe=c52d7dc596) | Dec 17, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [a58123c368](https://linux-hardware.org/?probe=a58123c368) | Dec 17, 2021 |
| Dell          | 0J3C2F A02                  | [a1cc2ad6fd](https://linux-hardware.org/?probe=a1cc2ad6fd) | Dec 08, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ddafe324b7](https://linux-hardware.org/?probe=ddafe324b7) | Dec 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | [e9b454a745](https://linux-hardware.org/?probe=e9b454a745) | Dec 04, 2021 |
| MSI           | Boston                      | [0b79772dfa](https://linux-hardware.org/?probe=0b79772dfa) | Dec 04, 2021 |
| HP            | 1497                        | [f848ad29cd](https://linux-hardware.org/?probe=f848ad29cd) | Dec 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | [b096d0494e](https://linux-hardware.org/?probe=b096d0494e) | Dec 02, 2021 |
| Gigabyte      | P35-DS3L                    | [2e5a8410bc](https://linux-hardware.org/?probe=2e5a8410bc) | Dec 01, 2021 |
| ASUSTek       | CM1435                      | [febd571863](https://linux-hardware.org/?probe=febd571863) | Nov 28, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [c4345f14ad](https://linux-hardware.org/?probe=c4345f14ad) | Nov 27, 2021 |
| Gigabyte      | G31M-S2C                    | [0598f63a64](https://linux-hardware.org/?probe=0598f63a64) | Nov 25, 2021 |
| Gigabyte      | G31M-S2C                    | [4528ddf31d](https://linux-hardware.org/?probe=4528ddf31d) | Nov 25, 2021 |
| Gigabyte      | A520I AC                    | [ae985a32ad](https://linux-hardware.org/?probe=ae985a32ad) | Nov 23, 2021 |
| Acer          | Aspire XC600 v1.0           | [2f1bc07165](https://linux-hardware.org/?probe=2f1bc07165) | Nov 17, 2021 |
| Dell          | 0T568R A00                  | [bee032ad7d](https://linux-hardware.org/?probe=bee032ad7d) | Nov 14, 2021 |
| Acer          | Aspire X1700                | [c5f8009554](https://linux-hardware.org/?probe=c5f8009554) | Nov 11, 2021 |
| ASUSTek       | Z170-A                      | [614e3100c1](https://linux-hardware.org/?probe=614e3100c1) | Nov 11, 2021 |
| Acer          | Aspire X1700                | [57213f86cb](https://linux-hardware.org/?probe=57213f86cb) | Nov 05, 2021 |
| MSI           | MAG Z490 TOMAHAWK           | [5cea4f8e91](https://linux-hardware.org/?probe=5cea4f8e91) | Nov 04, 2021 |
| Foxconn       | 2AA9h                       | [92ec7d0070](https://linux-hardware.org/?probe=92ec7d0070) | Nov 03, 2021 |
| Medion        | MS-7728                     | [564ffdab3d](https://linux-hardware.org/?probe=564ffdab3d) | Nov 02, 2021 |
| ASUSTek       | PRIME H410M-E               | [7b62ad7c35](https://linux-hardware.org/?probe=7b62ad7c35) | Oct 27, 2021 |
| MSI           | MS-7309                     | [72f1e0a452](https://linux-hardware.org/?probe=72f1e0a452) | Oct 25, 2021 |
| ASUSTek       | H170M-PLUS                  | [15969208ae](https://linux-hardware.org/?probe=15969208ae) | Oct 18, 2021 |
| Unknown       | X99-D8                      | [e335225bdb](https://linux-hardware.org/?probe=e335225bdb) | Oct 17, 2021 |
| AAEON         | MF-001 V1.0                 | [3f6dfebdf6](https://linux-hardware.org/?probe=3f6dfebdf6) | Oct 12, 2021 |
| Acer          | Aspire X1700                | [0fe52aff1e](https://linux-hardware.org/?probe=0fe52aff1e) | Oct 07, 2021 |
| Acer          | Aspire X1700                | [0a715fa1e0](https://linux-hardware.org/?probe=0a715fa1e0) | Oct 07, 2021 |
| MSI           | B350 TOMAHAWK PLUS          | [acbc75f1b8](https://linux-hardware.org/?probe=acbc75f1b8) | Oct 06, 2021 |
| Unknown       | X79M2-Q                     | [c864ea2ab2](https://linux-hardware.org/?probe=c864ea2ab2) | Oct 05, 2021 |
| Gigabyte      | P35-DS3L                    | [2f7c2f51f8](https://linux-hardware.org/?probe=2f7c2f51f8) | Oct 01, 2021 |
| Pegatron      | Acacia                      | [645d85506e](https://linux-hardware.org/?probe=645d85506e) | Sep 28, 2021 |
| ZOTAC         | NM10                        | [94313faa27](https://linux-hardware.org/?probe=94313faa27) | Sep 27, 2021 |
| Foxconn       | Priv                        | [78997c0b10](https://linux-hardware.org/?probe=78997c0b10) | Sep 24, 2021 |
| Acer          | H57M01                      | [6e58f49020](https://linux-hardware.org/?probe=6e58f49020) | Sep 24, 2021 |
| Gigabyte      | H61M-DS2H                   | [16783c2955](https://linux-hardware.org/?probe=16783c2955) | Sep 21, 2021 |
| ASUSTek       | P8C WS                      | [e1dce50aa6](https://linux-hardware.org/?probe=e1dce50aa6) | Sep 18, 2021 |
| ASRock        | Z590M-ITX/ax                | [2496caf8c3](https://linux-hardware.org/?probe=2496caf8c3) | Sep 17, 2021 |
| Foxconn       | 2AAF                        | [be2ce05253](https://linux-hardware.org/?probe=be2ce05253) | Sep 17, 2021 |
| ASRock        | Z590M-ITX/ax                | [8027337fff](https://linux-hardware.org/?probe=8027337fff) | Sep 16, 2021 |
| ASUSTek       | P6T SE                      | [b50449f73f](https://linux-hardware.org/?probe=b50449f73f) | Sep 14, 2021 |
| Dell          | 0M5DCD A00                  | [f4c9642d6f](https://linux-hardware.org/?probe=f4c9642d6f) | Sep 10, 2021 |
| MSI           | AMETHYST-M                  | [eea8d03e34](https://linux-hardware.org/?probe=eea8d03e34) | Sep 05, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [0fa53c65bb](https://linux-hardware.org/?probe=0fa53c65bb) | Aug 24, 2021 |
| ASRock        | FM2A68M-DG3+                | [157d6655d0](https://linux-hardware.org/?probe=157d6655d0) | Aug 23, 2021 |
| ZOTAC         | NM10                        | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| MSI           | 760GM-E51                   | [1edbc1f4d8](https://linux-hardware.org/?probe=1edbc1f4d8) | Aug 19, 2021 |
| HP            | 8299                        | [48455294be](https://linux-hardware.org/?probe=48455294be) | Jul 28, 2021 |
| Huanan        | X99-TF V2.0                 | [f6911a81e8](https://linux-hardware.org/?probe=f6911a81e8) | Jul 26, 2021 |
| Intel         | DG965SS AAD41678-307        | [d3f38dbf63](https://linux-hardware.org/?probe=d3f38dbf63) | Jul 24, 2021 |
| HP            | 1495                        | [3f39c0e882](https://linux-hardware.org/?probe=3f39c0e882) | Jul 23, 2021 |
| HP            | 0A1Ch E                     | [6d6f2ce899](https://linux-hardware.org/?probe=6d6f2ce899) | Jul 21, 2021 |
| Gigabyte      | B450M H                     | [cb2babd945](https://linux-hardware.org/?probe=cb2babd945) | Jul 20, 2021 |
| ASUSTek       | V-P8H67E                    | [e0ff38374e](https://linux-hardware.org/?probe=e0ff38374e) | Jul 13, 2021 |
| Gigabyte      | Z77X-UD3H                   | [572b814c9a](https://linux-hardware.org/?probe=572b814c9a) | Jul 11, 2021 |
| HP            | 3397                        | [b9b07bdc0a](https://linux-hardware.org/?probe=b9b07bdc0a) | Jul 09, 2021 |
| Positivo      | POS-MI945AA                 | [2a1eda1972](https://linux-hardware.org/?probe=2a1eda1972) | Jul 07, 2021 |
| ASUSTek       | P8H61-M LE                  | [456048c8ee](https://linux-hardware.org/?probe=456048c8ee) | Jul 06, 2021 |
| Hardkernel    | ODROID-H2                   | [37fdca8e63](https://linux-hardware.org/?probe=37fdca8e63) | Jul 06, 2021 |
| ASUSTek       | P5K                         | [11fed8f8ae](https://linux-hardware.org/?probe=11fed8f8ae) | Jul 03, 2021 |
| Biostar       | A68N-2100                   | [bffed391bc](https://linux-hardware.org/?probe=bffed391bc) | Jul 02, 2021 |
| Dell          | 0TW904 A01                  | [b98c7e4685](https://linux-hardware.org/?probe=b98c7e4685) | Jun 29, 2021 |
| Intel         | DG41WV AAE90316-102         | [c04c0fcc65](https://linux-hardware.org/?probe=c04c0fcc65) | Jun 25, 2021 |
| Gigabyte      | B550M AORUS PRO             | [5d8e8c301f](https://linux-hardware.org/?probe=5d8e8c301f) | Jun 24, 2021 |
| IBM           | 8183V6D                     | [d5c4e8c76b](https://linux-hardware.org/?probe=d5c4e8c76b) | Jun 18, 2021 |
| Dell          | 0TW904 A01                  | [51b0adff27](https://linux-hardware.org/?probe=51b0adff27) | Jun 17, 2021 |
| ASUSTek       | PRIME H410M-E               | [0eb8caf654](https://linux-hardware.org/?probe=0eb8caf654) | Jun 08, 2021 |
| Fujitsu Si... | D2584-A1 S26361-D2584-A1    | [ec208f5ad8](https://linux-hardware.org/?probe=ec208f5ad8) | Jun 06, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [f4ce6e2f6a](https://linux-hardware.org/?probe=f4ce6e2f6a) | Jun 02, 2021 |
| MSI           | B350M GAMING PRO            | [52c67d407d](https://linux-hardware.org/?probe=52c67d407d) | May 31, 2021 |
| ASUSTek       | K8N                         | [2bfbb90a8e](https://linux-hardware.org/?probe=2bfbb90a8e) | May 24, 2021 |
| HP            | 1905                        | [fd0f9e5ab1](https://linux-hardware.org/?probe=fd0f9e5ab1) | May 23, 2021 |
| HP            | 09C4h                       | [a94946d561](https://linux-hardware.org/?probe=a94946d561) | May 23, 2021 |
| HP            | 21B4 A01                    | [b2a7cbbc72](https://linux-hardware.org/?probe=b2a7cbbc72) | May 23, 2021 |
| Dell          | 0HY175 A03                  | [d1b6626b26](https://linux-hardware.org/?probe=d1b6626b26) | May 20, 2021 |
| HP            | 1905                        | [28fb3ce7e8](https://linux-hardware.org/?probe=28fb3ce7e8) | May 20, 2021 |
| ASUSTek       | V-P8H67E                    | [e8f0220bba](https://linux-hardware.org/?probe=e8f0220bba) | May 19, 2021 |
| ASUSTek       | K8N                         | [1d266884ca](https://linux-hardware.org/?probe=1d266884ca) | May 19, 2021 |
| ASRock        | N68-VS3 UCC                 | [85eaf93d23](https://linux-hardware.org/?probe=85eaf93d23) | May 18, 2021 |
| Dell          | 0D441T A03                  | [c23a919651](https://linux-hardware.org/?probe=c23a919651) | May 18, 2021 |
| MSI           | H61M-E33                    | [23d2285e8a](https://linux-hardware.org/?probe=23d2285e8a) | May 13, 2021 |
| ASRock        | N68-VS3 UCC                 | [b4015edbbe](https://linux-hardware.org/?probe=b4015edbbe) | May 12, 2021 |
| ASUSTek       | K8N                         | [e692a4b6aa](https://linux-hardware.org/?probe=e692a4b6aa) | May 11, 2021 |
| Unknown       | Unknown                     | [c42f475a67](https://linux-hardware.org/?probe=c42f475a67) | May 08, 2021 |
| ASUSTek       | H110I-PLUS                  | [0f9c2db369](https://linux-hardware.org/?probe=0f9c2db369) | May 07, 2021 |
| Dell          | 09M8Y8 A01                  | [8c9dd0e965](https://linux-hardware.org/?probe=8c9dd0e965) | May 06, 2021 |
| ASUSTek       | H110I-PLUS                  | [579414cef4](https://linux-hardware.org/?probe=579414cef4) | May 04, 2021 |
| IBM           | 8183V6D                     | [0df40278d1](https://linux-hardware.org/?probe=0df40278d1) | May 02, 2021 |
| ASUSTek       | P5GC-MX/1333                | [9088160499](https://linux-hardware.org/?probe=9088160499) | Apr 30, 2021 |
| ASUSTek       | P5GC-MX/1333                | [7feaa72545](https://linux-hardware.org/?probe=7feaa72545) | Apr 30, 2021 |
| AAEON         | MF-001 V1.0                 | [ef051b442a](https://linux-hardware.org/?probe=ef051b442a) | Apr 28, 2021 |
| Packard Be... | IMEDIA S1350                | [781d544a3e](https://linux-hardware.org/?probe=781d544a3e) | Apr 27, 2021 |
| ASRock        | FM2A88M Extreme4+           | [25f6cfe2bb](https://linux-hardware.org/?probe=25f6cfe2bb) | Apr 26, 2021 |
| Intel         | SHARKBAY                    | [cf6ec831df](https://linux-hardware.org/?probe=cf6ec831df) | Apr 25, 2021 |
| ASUSTek       | P5Q DELUXE                  | [145106a409](https://linux-hardware.org/?probe=145106a409) | Apr 25, 2021 |
| Intel         | DX58SO AAE29331-404         | [e4f384c278](https://linux-hardware.org/?probe=e4f384c278) | Apr 24, 2021 |
| Intel         | D525MW AAE93082-401         | [aea7beb5c3](https://linux-hardware.org/?probe=aea7beb5c3) | Apr 12, 2021 |
| ASUSTek       | P7P55 LX                    | [219757d806](https://linux-hardware.org/?probe=219757d806) | Apr 11, 2021 |
| ASRock        | N68-VS3 UCC                 | [72861aa353](https://linux-hardware.org/?probe=72861aa353) | Apr 09, 2021 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [2c58a29c2a](https://linux-hardware.org/?probe=2c58a29c2a) | Apr 02, 2021 |
| Gigabyte      | X570 GAMING X               | [d36d3e1e58](https://linux-hardware.org/?probe=d36d3e1e58) | Apr 01, 2021 |
| MSI           | Boston                      | [e0cfb03088](https://linux-hardware.org/?probe=e0cfb03088) | Mar 30, 2021 |
| HP            | 1589                        | [8b3a28644e](https://linux-hardware.org/?probe=8b3a28644e) | Mar 28, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | [25fd34ad8f](https://linux-hardware.org/?probe=25fd34ad8f) | Mar 27, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | [354da6602b](https://linux-hardware.org/?probe=354da6602b) | Mar 27, 2021 |
| HP            | 8054                        | [b3bc9388b0](https://linux-hardware.org/?probe=b3bc9388b0) | Mar 27, 2021 |
| HP            | 1589                        | [7b3c9bf186](https://linux-hardware.org/?probe=7b3c9bf186) | Mar 27, 2021 |
| ASUSTek       | Z97-K                       | [383cee85b7](https://linux-hardware.org/?probe=383cee85b7) | Mar 25, 2021 |
| ASUSTek       | M5A97 R2.0                  | [83716bfba8](https://linux-hardware.org/?probe=83716bfba8) | Mar 24, 2021 |
| HP            | 21D0                        | [ebf910609e](https://linux-hardware.org/?probe=ebf910609e) | Mar 23, 2021 |
| Dell          | 09M8Y8 A01                  | [e1adceeeeb](https://linux-hardware.org/?probe=e1adceeeeb) | Mar 20, 2021 |
| ASRock        | N68C-S UCC                  | [8ae162d330](https://linux-hardware.org/?probe=8ae162d330) | Mar 16, 2021 |
| Lenovo        | SDK0E50510 WIN              | [a6b06d9421](https://linux-hardware.org/?probe=a6b06d9421) | Mar 16, 2021 |
| ASRock        | N68C-S UCC                  | [e099627755](https://linux-hardware.org/?probe=e099627755) | Mar 15, 2021 |
| ASRock        | N68C-S UCC                  | [2abee1f31e](https://linux-hardware.org/?probe=2abee1f31e) | Mar 14, 2021 |
| ASRock        | 775Dual-VSTA                | [6f870bccf3](https://linux-hardware.org/?probe=6f870bccf3) | Mar 13, 2021 |
| MSI           | Boston                      | [e9513c3b7a](https://linux-hardware.org/?probe=e9513c3b7a) | Mar 03, 2021 |
| Gigabyte      | H81M-DS2                    | [439d425d4b](https://linux-hardware.org/?probe=439d425d4b) | Mar 01, 2021 |
| Dell          | 09M8Y8 A01                  | [3ed340b3ba](https://linux-hardware.org/?probe=3ed340b3ba) | Feb 28, 2021 |
| Dell          | 0RY007                      | [6172822ebb](https://linux-hardware.org/?probe=6172822ebb) | Feb 27, 2021 |
| Intel         | D945GCLF2 AAE46416-103      | [47d5daa739](https://linux-hardware.org/?probe=47d5daa739) | Feb 25, 2021 |
| ASRock        | 775VM800                    | [5b04151216](https://linux-hardware.org/?probe=5b04151216) | Feb 15, 2021 |
| ASRock        | 775VM800                    | [d292f6ac7b](https://linux-hardware.org/?probe=d292f6ac7b) | Feb 12, 2021 |
| Intel         | ChiefRiver                  | [25476cfcb9](https://linux-hardware.org/?probe=25476cfcb9) | Feb 10, 2021 |
| Gigabyte      | H81M-DS2                    | [9c1652cf08](https://linux-hardware.org/?probe=9c1652cf08) | Feb 10, 2021 |
| Intel         | D945GTP AAC97834-305        | [fa876f7290](https://linux-hardware.org/?probe=fa876f7290) | Feb 10, 2021 |
| ASUSTek       | M2A-MX                      | [1541b0dbe1](https://linux-hardware.org/?probe=1541b0dbe1) | Feb 09, 2021 |
| ASUSTek       | M2A-MX                      | [391d63e436](https://linux-hardware.org/?probe=391d63e436) | Feb 09, 2021 |
| ASUSTek       | M3A78-EMH HDMI              | [7c78d0efc3](https://linux-hardware.org/?probe=7c78d0efc3) | Feb 09, 2021 |
| ASUSTek       | M3A78-EMH HDMI              | [beddd7c01d](https://linux-hardware.org/?probe=beddd7c01d) | Feb 09, 2021 |
| ASUSTek       | P5G41T-M LE                 | [f08dd9c298](https://linux-hardware.org/?probe=f08dd9c298) | Feb 08, 2021 |
| Intel         | D945GCLF2 AAE46416-103      | [a8af34d0ee](https://linux-hardware.org/?probe=a8af34d0ee) | Feb 08, 2021 |
| ASUSTek       | P5G41T-M LE                 | [32061cad93](https://linux-hardware.org/?probe=32061cad93) | Feb 08, 2021 |
| HP            | 3048h                       | [59c1560e00](https://linux-hardware.org/?probe=59c1560e00) | Jan 30, 2021 |
| Dell          | 0TP406                      | [8d298a20d5](https://linux-hardware.org/?probe=8d298a20d5) | Jan 28, 2021 |
| Lenovo        | ThinkCentre XXXX 9632AU8    | [cdc139f77e](https://linux-hardware.org/?probe=cdc139f77e) | Jan 24, 2021 |
| MSI           | MS-7270                     | [9e5fa11934](https://linux-hardware.org/?probe=9e5fa11934) | Jan 24, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [fdc50253da](https://linux-hardware.org/?probe=fdc50253da) | Jan 21, 2021 |
| Dell          | 0D28YY A00                  | [3761191ef4](https://linux-hardware.org/?probe=3761191ef4) | Jan 21, 2021 |
| Dell          | 0D28YY A00                  | [5446971c89](https://linux-hardware.org/?probe=5446971c89) | Jan 20, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [71a9d08996](https://linux-hardware.org/?probe=71a9d08996) | Jan 14, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [55f1890303](https://linux-hardware.org/?probe=55f1890303) | Jan 11, 2021 |
| Pegatron      | NARRA3                      | [ebb1428c72](https://linux-hardware.org/?probe=ebb1428c72) | Jan 11, 2021 |
| ASUSTek       | P8Z68-V LX                  | [3ff4a460a2](https://linux-hardware.org/?probe=3ff4a460a2) | Jan 10, 2021 |
| Gigabyte      | Z77N-WIFI                   | [653ea393e6](https://linux-hardware.org/?probe=653ea393e6) | Jan 06, 2021 |
| MSI           | AMETHYST-M                  | [ee8e20c6fb](https://linux-hardware.org/?probe=ee8e20c6fb) | Jan 06, 2021 |
| AMI           | Cherry Trail CR             | [4fe52138ff](https://linux-hardware.org/?probe=4fe52138ff) | Jan 04, 2021 |
| AMI           | Cherry Trail CR             | [d86f56eaf3](https://linux-hardware.org/?probe=d86f56eaf3) | Jan 04, 2021 |
| MSI           | MS-7250                     | [72950b548d](https://linux-hardware.org/?probe=72950b548d) | Jan 04, 2021 |
| ASUSTek       | ROG Maximus X HERO          | [48edae2fa9](https://linux-hardware.org/?probe=48edae2fa9) | Jan 04, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | [73f8eb43d6](https://linux-hardware.org/?probe=73f8eb43d6) | Jan 01, 2021 |
| Gigabyte      | H81M-HD3                    | [5df1b1d371](https://linux-hardware.org/?probe=5df1b1d371) | Dec 30, 2020 |
| ASRock        | FM2A88X Pro3+               | [a57902b2df](https://linux-hardware.org/?probe=a57902b2df) | Dec 23, 2020 |
| Lenovo        | ThinkCentre M58p 6136A66    | [166a0c26e2](https://linux-hardware.org/?probe=166a0c26e2) | Dec 23, 2020 |
| Dell          | 0WG864                      | [f5cb8c4f4a](https://linux-hardware.org/?probe=f5cb8c4f4a) | Dec 23, 2020 |
| Gigabyte      | B550M AORUS PRO             | [cdc016f9d1](https://linux-hardware.org/?probe=cdc016f9d1) | Dec 18, 2020 |
| HP            | 3031h                       | [b1c4657359](https://linux-hardware.org/?probe=b1c4657359) | Dec 16, 2020 |
| Gigabyte      | GA-78LMT-S2P                | [43ba858067](https://linux-hardware.org/?probe=43ba858067) | Dec 16, 2020 |
| Dell          | 0WG864                      | [de92f1f8e4](https://linux-hardware.org/?probe=de92f1f8e4) | Dec 11, 2020 |
| Gigabyte      | H77M-D3H                    | [170d95c5c3](https://linux-hardware.org/?probe=170d95c5c3) | Dec 05, 2020 |
| Gigabyte      | H77M-D3H                    | [d00d18cbda](https://linux-hardware.org/?probe=d00d18cbda) | Dec 05, 2020 |
| ASRock        | FM2A85X Extreme6            | [225f795531](https://linux-hardware.org/?probe=225f795531) | Dec 01, 2020 |
| eMachines     | EMCP61M                     | [19e0a468d5](https://linux-hardware.org/?probe=19e0a468d5) | Dec 01, 2020 |
| eMachines     | EMCP61M                     | [c76fe73c42](https://linux-hardware.org/?probe=c76fe73c42) | Dec 01, 2020 |
| Gigabyte      | 965P-DS3                    | [ce0a64067a](https://linux-hardware.org/?probe=ce0a64067a) | Nov 29, 2020 |
| Gigabyte      | 965P-DS3                    | [d7ac62fba3](https://linux-hardware.org/?probe=d7ac62fba3) | Nov 29, 2020 |
| Lenovo        | 367D 31900058 STD           | [40b28c6d37](https://linux-hardware.org/?probe=40b28c6d37) | Nov 29, 2020 |
| Biostar       | G31-M7 TE                   | [174de8e1d6](https://linux-hardware.org/?probe=174de8e1d6) | Nov 29, 2020 |
| Biostar       | G31-M7 TE                   | [7b85d35e4d](https://linux-hardware.org/?probe=7b85d35e4d) | Nov 29, 2020 |
| MSI           | P55-GD80                    | [409cb71474](https://linux-hardware.org/?probe=409cb71474) | Nov 27, 2020 |
| MSI           | B450 GAMING PLUS MAX        | [761ecd0a1c](https://linux-hardware.org/?probe=761ecd0a1c) | Nov 25, 2020 |
| ASRock        | 4Core1600-GLAN              | [5eae42eb75](https://linux-hardware.org/?probe=5eae42eb75) | Nov 25, 2020 |
| HP            | 2820h                       | [fc14726596](https://linux-hardware.org/?probe=fc14726596) | Nov 23, 2020 |
| Gigabyte      | GA-MA78GM-S2H               | [63776843ec](https://linux-hardware.org/?probe=63776843ec) | Nov 21, 2020 |
| Pegatron      | Narra6                      | [7878c50c46](https://linux-hardware.org/?probe=7878c50c46) | Nov 20, 2020 |
| MSI           | MS-7250                     | [8f408a7fec](https://linux-hardware.org/?probe=8f408a7fec) | Nov 17, 2020 |
| HP            | 09F8h                       | [60fbac3096](https://linux-hardware.org/?probe=60fbac3096) | Nov 16, 2020 |
| Foxconn       | 2AA9                        | [dbe623f2ad](https://linux-hardware.org/?probe=dbe623f2ad) | Nov 14, 2020 |
| ECS           | Iris8                       | [1614d7d736](https://linux-hardware.org/?probe=1614d7d736) | Nov 14, 2020 |
| IBM           | 8183V6D                     | [7784e64311](https://linux-hardware.org/?probe=7784e64311) | Nov 14, 2020 |
| ECS           | Iris8                       | [c2d76cebd4](https://linux-hardware.org/?probe=c2d76cebd4) | Nov 14, 2020 |
| MSI           | G41M-P28                    | [21e89d9e69](https://linux-hardware.org/?probe=21e89d9e69) | Nov 11, 2020 |
| Gigabyte      | B450M S2H                   | [b2054d891d](https://linux-hardware.org/?probe=b2054d891d) | Nov 10, 2020 |
| ASRock        | 4Core1600-GLAN              | [3bc862c3f6](https://linux-hardware.org/?probe=3bc862c3f6) | Nov 03, 2020 |
| IBM           | 8183V6D                     | [440a6a1057](https://linux-hardware.org/?probe=440a6a1057) | Nov 02, 2020 |
| Gigabyte      | B250M-D3H-CF                | [547d1a4d87](https://linux-hardware.org/?probe=547d1a4d87) | Nov 01, 2020 |
| HP            | 0AA8h                       | [f619ee9af9](https://linux-hardware.org/?probe=f619ee9af9) | Oct 31, 2020 |
| Intel         | STK1AW32SC H91596-300       | [64ad81c366](https://linux-hardware.org/?probe=64ad81c366) | Oct 31, 2020 |
| Dell          | 0J3C2F A02                  | [a0c7490384](https://linux-hardware.org/?probe=a0c7490384) | Oct 23, 2020 |
| ASRock        | G41M-GS3                    | [55872633b0](https://linux-hardware.org/?probe=55872633b0) | Oct 21, 2020 |
| HP            | 2187 A01                    | [ed8c0e270a](https://linux-hardware.org/?probe=ed8c0e270a) | Oct 21, 2020 |
| HP            | 2187 A01                    | [873e321107](https://linux-hardware.org/?probe=873e321107) | Oct 20, 2020 |
| ASUSTek       | P5S800-VM                   | [abb4e0e0c2](https://linux-hardware.org/?probe=abb4e0e0c2) | Oct 17, 2020 |
| ASUSTek       | PRIME H310M-K               | [706aa7bb74](https://linux-hardware.org/?probe=706aa7bb74) | Oct 13, 2020 |
| ASUSTek       | PRIME H310M-K               | [132e2b687c](https://linux-hardware.org/?probe=132e2b687c) | Oct 13, 2020 |
| Dell          | 0KRC95 A01                  | [a6576290b5](https://linux-hardware.org/?probe=a6576290b5) | Oct 10, 2020 |
| MSI           | H97M-E35                    | [583794cac0](https://linux-hardware.org/?probe=583794cac0) | Oct 10, 2020 |
| MSI           | H110M ECO                   | [21fea178f7](https://linux-hardware.org/?probe=21fea178f7) | Oct 06, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [bcac6bcfaf](https://linux-hardware.org/?probe=bcac6bcfaf) | Oct 03, 2020 |
| Biostar       | N61PC-M2S                   | [f41fe9205d](https://linux-hardware.org/?probe=f41fe9205d) | Sep 30, 2020 |
| Gigabyte      | Z370P D3-CF                 | [a112988e2e](https://linux-hardware.org/?probe=a112988e2e) | Sep 28, 2020 |
| Intel         | D945GCLF2 AAE46416-103      | [426bdc3586](https://linux-hardware.org/?probe=426bdc3586) | Sep 24, 2020 |
| Gateway       | SX2185                      | [7404f09683](https://linux-hardware.org/?probe=7404f09683) | Sep 22, 2020 |
| MSI           | B450M MORTAR MAX            | [e7728895a3](https://linux-hardware.org/?probe=e7728895a3) | Sep 20, 2020 |
| Dell          | 0J3C2F A02                  | [c1cbfad587](https://linux-hardware.org/?probe=c1cbfad587) | Sep 20, 2020 |
| ASRock        | A320M-DGS                   | [0ee0a67ae6](https://linux-hardware.org/?probe=0ee0a67ae6) | Sep 13, 2020 |
| HP            | 0A50h                       | [ace0e3fed5](https://linux-hardware.org/?probe=ace0e3fed5) | Sep 13, 2020 |
| HP            | 0A50h                       | [f70b1ce07f](https://linux-hardware.org/?probe=f70b1ce07f) | Sep 12, 2020 |
| Intel         | DG31PR AAD97573-302         | [0362c81208](https://linux-hardware.org/?probe=0362c81208) | Sep 11, 2020 |
| ASUSTek       | V-P8H67E                    | [a86b68e7e2](https://linux-hardware.org/?probe=a86b68e7e2) | Sep 05, 2020 |
| Dell          | 0CU409                      | [d226085fe5](https://linux-hardware.org/?probe=d226085fe5) | Aug 26, 2020 |
| ASRock        | A320M-HD                    | [8e8b3d8d21](https://linux-hardware.org/?probe=8e8b3d8d21) | Aug 23, 2020 |
| Biostar       | A68N-2100                   | [27b74a4963](https://linux-hardware.org/?probe=27b74a4963) | Aug 16, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [a43507c564](https://linux-hardware.org/?probe=a43507c564) | Aug 12, 2020 |
| PCChips       | A13G                        | [d3bc7edc49](https://linux-hardware.org/?probe=d3bc7edc49) | Aug 09, 2020 |
| Lenovo        | ThinkCentre M58p 7220W21    | [aa37671480](https://linux-hardware.org/?probe=aa37671480) | Aug 05, 2020 |
| Philco        | 14F                         | [8fce6fc79b](https://linux-hardware.org/?probe=8fce6fc79b) | Jul 31, 2020 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [10a2f3c16b](https://linux-hardware.org/?probe=10a2f3c16b) | Jul 30, 2020 |
| Lenovo        | SDK0E50515 STD              | [def93851d7](https://linux-hardware.org/?probe=def93851d7) | Jul 27, 2020 |
| ASUSTek       | E45M1-M PRO                 | [b4e6ad4325](https://linux-hardware.org/?probe=b4e6ad4325) | Jul 25, 2020 |
| Positivo      | POS-EIH61CE POSITIVO        | [aea6ae732a](https://linux-hardware.org/?probe=aea6ae732a) | Jul 25, 2020 |
| ASUSTek       | P7P55 LX                    | [b907d5353a](https://linux-hardware.org/?probe=b907d5353a) | Jul 25, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [fd15d7f633](https://linux-hardware.org/?probe=fd15d7f633) | Jul 24, 2020 |
| ASUSTek       | M5A97 EVO R2.0              | [e79c3ae616](https://linux-hardware.org/?probe=e79c3ae616) | Jul 24, 2020 |
| Intel         | H55                         | [f9399791b8](https://linux-hardware.org/?probe=f9399791b8) | Jul 24, 2020 |
| ASUSTek       | E45M1-M PRO                 | [cf22d23381](https://linux-hardware.org/?probe=cf22d23381) | Jul 22, 2020 |
| HP            | 085Ch                       | [c22eb5394a](https://linux-hardware.org/?probe=c22eb5394a) | Jul 22, 2020 |
| HP            | 085Ch                       | [a6b75813e8](https://linux-hardware.org/?probe=a6b75813e8) | Jul 20, 2020 |
| IBM           | eServer x3105 -[434722J]... | [25f7acc0f7](https://linux-hardware.org/?probe=25f7acc0f7) | Jul 20, 2020 |
| MSI           | B450M MORTAR MAX            | [09f9209cda](https://linux-hardware.org/?probe=09f9209cda) | Jul 18, 2020 |
| Gigabyte      | H61M-S1                     | [03b6eef668](https://linux-hardware.org/?probe=03b6eef668) | Jul 16, 2020 |
| Gigabyte      | H61M-S1                     | [61727004f5](https://linux-hardware.org/?probe=61727004f5) | Jul 16, 2020 |
| ASRock        | 775Dual-VSTA                | [b97000d1d8](https://linux-hardware.org/?probe=b97000d1d8) | Jul 16, 2020 |
| ASRock        | 775Dual-VSTA                | [94cba10ae4](https://linux-hardware.org/?probe=94cba10ae4) | Jul 15, 2020 |
| ASUSTek       | P5S800-VM                   | [214ec41334](https://linux-hardware.org/?probe=214ec41334) | Jul 14, 2020 |
| Biostar       | A68N-2100                   | [07e923d97c](https://linux-hardware.org/?probe=07e923d97c) | Jul 04, 2020 |
| HP            | 3396                        | [820e05ee01](https://linux-hardware.org/?probe=820e05ee01) | Jul 03, 2020 |
| ASUSTek       | P5LD2EB2-DHS                | [66d4b86237](https://linux-hardware.org/?probe=66d4b86237) | Jul 01, 2020 |
| MSI           | X570-A PRO                  | [8d3308bf38](https://linux-hardware.org/?probe=8d3308bf38) | Jun 23, 2020 |
| ASUSTek       | M2R-FVM                     | [e6ee210f6d](https://linux-hardware.org/?probe=e6ee210f6d) | Jun 23, 2020 |
| HP            | 304Ah                       | [196b570551](https://linux-hardware.org/?probe=196b570551) | Jun 23, 2020 |
| HP            | 304Ah                       | [bfe838c10f](https://linux-hardware.org/?probe=bfe838c10f) | Jun 23, 2020 |
| Dell          | 0Y2MRG A00                  | [c64fcf2a5d](https://linux-hardware.org/?probe=c64fcf2a5d) | Jun 21, 2020 |
| Dell          | 0Y2MRG A00                  | [21bd837ffa](https://linux-hardware.org/?probe=21bd837ffa) | Jun 20, 2020 |
| Intel         | DG31PR AAE58249-306         | [ee1eb9d6fb](https://linux-hardware.org/?probe=ee1eb9d6fb) | Jun 18, 2020 |
| ASUSTek       | M2R-FVM                     | [33713a0404](https://linux-hardware.org/?probe=33713a0404) | Jun 18, 2020 |
| HP            | 09E0h                       | [4979e74209](https://linux-hardware.org/?probe=4979e74209) | Jun 18, 2020 |
| MSI           | 0A48                        | [e9c8fd5217](https://linux-hardware.org/?probe=e9c8fd5217) | Jun 17, 2020 |
| HP            | 09E0h                       | [3fbd5af0ab](https://linux-hardware.org/?probe=3fbd5af0ab) | Jun 16, 2020 |
| Intel         | DG31PR AAE58249-306         | [9e786bc6e0](https://linux-hardware.org/?probe=9e786bc6e0) | Jun 12, 2020 |
| ASUSTek       | ET1612I                     | [7232340ccc](https://linux-hardware.org/?probe=7232340ccc) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | [4400ee29ed](https://linux-hardware.org/?probe=4400ee29ed) | Jun 08, 2020 |
| Gigabyte      | F2A88XM-HD3                 | [d730ecdbd6](https://linux-hardware.org/?probe=d730ecdbd6) | Jun 08, 2020 |
| Qbex          | HDC-M                       | [5d547380f0](https://linux-hardware.org/?probe=5d547380f0) | Jun 01, 2020 |
| ASUSTek       | ET1612I                     | [ee417d15f0](https://linux-hardware.org/?probe=ee417d15f0) | May 31, 2020 |
| Biostar       | GF7025-M2                   | [66b5de774d](https://linux-hardware.org/?probe=66b5de774d) | May 26, 2020 |
| ASUSTek       | A8N-SLI                     | [5ccefc89ce](https://linux-hardware.org/?probe=5ccefc89ce) | May 23, 2020 |
| ASUSTek       | A8N-SLI                     | [2c0867a9ec](https://linux-hardware.org/?probe=2c0867a9ec) | May 23, 2020 |
| ASUSTek       | P8H67-M LX                  | [0ba192cc01](https://linux-hardware.org/?probe=0ba192cc01) | May 22, 2020 |
| Gigabyte      | GA-870A-UD3                 | [4da7cc2128](https://linux-hardware.org/?probe=4da7cc2128) | May 21, 2020 |
| HP            | 21B4 A01                    | [a787f75e19](https://linux-hardware.org/?probe=a787f75e19) | May 19, 2020 |
| Gigabyte      | 8I865G775-G                 | [f7d448edb4](https://linux-hardware.org/?probe=f7d448edb4) | May 18, 2020 |
| Unknown       | P4M800Pro-8237              | [71f901a69f](https://linux-hardware.org/?probe=71f901a69f) | May 18, 2020 |
| Unknown       | P4M800Pro-8237              | [bce5724752](https://linux-hardware.org/?probe=bce5724752) | May 18, 2020 |
| Unknown       | P4M800Pro-8237              | [21d6bc116d](https://linux-hardware.org/?probe=21d6bc116d) | May 15, 2020 |
| VIA Techno... | P4X266-8233                 | [0bf3b29d80](https://linux-hardware.org/?probe=0bf3b29d80) | May 14, 2020 |
| VIA Techno... | P4X266-8233                 | [597e6a2b14](https://linux-hardware.org/?probe=597e6a2b14) | May 14, 2020 |
| ASUSTek       | Berkeley                    | [ebb35e1770](https://linux-hardware.org/?probe=ebb35e1770) | May 14, 2020 |
| ASUSTek       | Berkeley                    | [038ada5ee3](https://linux-hardware.org/?probe=038ada5ee3) | May 14, 2020 |
| Gigabyte      | K8M800-8237                 | [8e2c1f0e62](https://linux-hardware.org/?probe=8e2c1f0e62) | May 13, 2020 |
| ASUSTek       | P5N-E SLI                   | [7af6f2c4d4](https://linux-hardware.org/?probe=7af6f2c4d4) | May 11, 2020 |
| ASUSTek       | P5S800-VM                   | [a4020f35b9](https://linux-hardware.org/?probe=a4020f35b9) | May 10, 2020 |
| ASUSTek       | P5B-Deluxe                  | [a8c07c11cb](https://linux-hardware.org/?probe=a8c07c11cb) | May 09, 2020 |
| ASUSTek       | P5B-Deluxe                  | [dd51c6c85e](https://linux-hardware.org/?probe=dd51c6c85e) | May 09, 2020 |
| Acer          | Aspire XC-703G              | [87c5ee1001](https://linux-hardware.org/?probe=87c5ee1001) | May 07, 2020 |
| HP            | 090Ch                       | [c471684991](https://linux-hardware.org/?probe=c471684991) | May 04, 2020 |
| HP            | 090Ch                       | [6f88fbc1ad](https://linux-hardware.org/?probe=6f88fbc1ad) | May 04, 2020 |
| Gigabyte      | GA-K8NF-9                   | [70a90ff062](https://linux-hardware.org/?probe=70a90ff062) | May 04, 2020 |
| ASUSTek       | P5G41C-M LX                 | [180e7f281b](https://linux-hardware.org/?probe=180e7f281b) | May 03, 2020 |
| VIA Techno... | P4X266-8233                 | [069ba04b1c](https://linux-hardware.org/?probe=069ba04b1c) | May 02, 2020 |
| Intel         | DN2800MT AAG23738-801       | [eba41acd95](https://linux-hardware.org/?probe=eba41acd95) | Apr 29, 2020 |
| ASUSTek       | VM40B                       | [acf2922656](https://linux-hardware.org/?probe=acf2922656) | Apr 26, 2020 |
| ASUSTek       | VM40B                       | [2fc777ae6a](https://linux-hardware.org/?probe=2fc777ae6a) | Apr 26, 2020 |
| MSI           | Boston                      | [e7cf465e34](https://linux-hardware.org/?probe=e7cf465e34) | Apr 22, 2020 |
| Acer          | Aspire X1800                | [beb70c1fc5](https://linux-hardware.org/?probe=beb70c1fc5) | Apr 19, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [c263eac3e9](https://linux-hardware.org/?probe=c263eac3e9) | Apr 13, 2020 |
| Acer          | MCP73VE NVIDIA MCP73        | [75fff2a0a6](https://linux-hardware.org/?probe=75fff2a0a6) | Apr 13, 2020 |
| eMachines     | EL1360G                     | [53d061d3b2](https://linux-hardware.org/?probe=53d061d3b2) | Apr 11, 2020 |
| Dell          | 0MM599                      | [19e2d2af44](https://linux-hardware.org/?probe=19e2d2af44) | Apr 11, 2020 |
| Intel         | DN2820FYK H24582-204        | [77cf46ddde](https://linux-hardware.org/?probe=77cf46ddde) | Apr 06, 2020 |
| Gigabyte      | nForce                      | [46e8276491](https://linux-hardware.org/?probe=46e8276491) | Apr 03, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [7759201b72](https://linux-hardware.org/?probe=7759201b72) | Apr 03, 2020 |
| Intel         | D945GCLF2 AAE46416-103      | [8e8dbf13fb](https://linux-hardware.org/?probe=8e8dbf13fb) | Mar 30, 2020 |
| Dell          | 0WG864                      | [092ae3a8ca](https://linux-hardware.org/?probe=092ae3a8ca) | Mar 27, 2020 |
| Gigabyte      | 945GCM-S2L                  | [548577276f](https://linux-hardware.org/?probe=548577276f) | Mar 27, 2020 |
| ASUSTek       | A8V-MQ                      | [54a0034c0a](https://linux-hardware.org/?probe=54a0034c0a) | Mar 24, 2020 |
| ASRock        | FM2A85X Extreme6            | [e4588ca61a](https://linux-hardware.org/?probe=e4588ca61a) | Mar 21, 2020 |
| Dell          | 0T287N A03                  | [02ebc6d299](https://linux-hardware.org/?probe=02ebc6d299) | Mar 16, 2020 |
| ASRock        | ConRoe865GV                 | [e849d8b11f](https://linux-hardware.org/?probe=e849d8b11f) | Mar 15, 2020 |
| ASRock        | B450M Pro4                  | [d7eb29abd9](https://linux-hardware.org/?probe=d7eb29abd9) | Mar 13, 2020 |
| ASRock        | ConRoe865GV                 | [2f52f8c106](https://linux-hardware.org/?probe=2f52f8c106) | Mar 12, 2020 |
| ASUSTek       | M2A-VM HDMI                 | [3746f6db56](https://linux-hardware.org/?probe=3746f6db56) | Mar 12, 2020 |
| Gigabyte      | P67A-D3-B3                  | [c00f70d6a6](https://linux-hardware.org/?probe=c00f70d6a6) | Mar 10, 2020 |
| ASUSTek       | H81M-E                      | [709a2484bc](https://linux-hardware.org/?probe=709a2484bc) | Mar 09, 2020 |
| ASRock        | B450M Pro4                  | [168bd28370](https://linux-hardware.org/?probe=168bd28370) | Feb 27, 2020 |
| ASUSTek       | CUSL2-M                     | [a20a268bb5](https://linux-hardware.org/?probe=a20a268bb5) | Feb 23, 2020 |
| Dell          | 08HPGT A01                  | [64e6dd4ba1](https://linux-hardware.org/?probe=64e6dd4ba1) | Feb 20, 2020 |
| HP            | 0A64h                       | [23d32db8b9](https://linux-hardware.org/?probe=23d32db8b9) | Feb 10, 2020 |
| HP            | 0A64h                       | [eed7c64698](https://linux-hardware.org/?probe=eed7c64698) | Feb 06, 2020 |
| ASRock        | N73V-S                      | [80b08d6e38](https://linux-hardware.org/?probe=80b08d6e38) | Jan 27, 2020 |
| ASRock        | N73V-S                      | [1f67c1102b](https://linux-hardware.org/?probe=1f67c1102b) | Jan 26, 2020 |
| Gigabyte      | GA-K8NF-9                   | [2b8833407a](https://linux-hardware.org/?probe=2b8833407a) | Jan 25, 2020 |
| MSI           | MS-7369                     | [5c6d33ae36](https://linux-hardware.org/?probe=5c6d33ae36) | Jan 25, 2020 |
| ASUSTek       | P5G41C-M LX                 | [cc1a05b68f](https://linux-hardware.org/?probe=cc1a05b68f) | Jan 24, 2020 |
| Dell          | 0GY6Y8 A03                  | [88961c610a](https://linux-hardware.org/?probe=88961c610a) | Jan 23, 2020 |
| ASUSTek       | P5QD TURBO                  | [d96168ded2](https://linux-hardware.org/?probe=d96168ded2) | Jan 12, 2020 |
| Intel         | D945GCLF2 AAE46416-103      | [947354716f](https://linux-hardware.org/?probe=947354716f) | Jan 07, 2020 |
| HP            | 0AA8h                       | [77b5333591](https://linux-hardware.org/?probe=77b5333591) | Jan 04, 2020 |
| ASUSTek       | V-P8H67E                    | [274eea3275](https://linux-hardware.org/?probe=274eea3275) | Dec 20, 2019 |
| ASUSTek       | V-P8H67E                    | [030c06dbf0](https://linux-hardware.org/?probe=030c06dbf0) | Dec 15, 2019 |
| ASUSTek       | V-P8H67E                    | [893a9b3000](https://linux-hardware.org/?probe=893a9b3000) | Dec 14, 2019 |
| AAEON         | MF-001 V1.0                 | [08480474f8](https://linux-hardware.org/?probe=08480474f8) | Dec 08, 2019 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [36a930502d](https://linux-hardware.org/?probe=36a930502d) | Nov 30, 2019 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [3bf663653b](https://linux-hardware.org/?probe=3bf663653b) | Nov 23, 2019 |
| ASRock        | H55M                        | [a199be0d97](https://linux-hardware.org/?probe=a199be0d97) | Nov 12, 2019 |
| ASRock        | H55M                        | [7202462c60](https://linux-hardware.org/?probe=7202462c60) | Nov 12, 2019 |
| Acer          | Aspire XC-703               | [5e3493c08f](https://linux-hardware.org/?probe=5e3493c08f) | Nov 11, 2019 |
| Acer          | Aspire XC-703               | [d31b932863](https://linux-hardware.org/?probe=d31b932863) | Nov 11, 2019 |
| Acer          | Aspire XC-703               | [0a5f0a6adc](https://linux-hardware.org/?probe=0a5f0a6adc) | Nov 11, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | [59fbd049bb](https://linux-hardware.org/?probe=59fbd049bb) | Aug 25, 2019 |
| Intel         | D945GCLF2 AAE46416-103      | [0b0497458b](https://linux-hardware.org/?probe=0b0497458b) | Aug 22, 2019 |
| ASUSTek       | Z97-A                       | [d85c2d26cb](https://linux-hardware.org/?probe=d85c2d26cb) | Jul 26, 2019 |
| ASRock        | AD525PV3                    | [682bc26535](https://linux-hardware.org/?probe=682bc26535) | Jul 03, 2019 |
| ASUSTek       | P5VD2-VM                    | [b99ee7c099](https://linux-hardware.org/?probe=b99ee7c099) | Apr 02, 2019 |
| ASUSTek       | M2N4-SLI                    | [84abf7384b](https://linux-hardware.org/?probe=84abf7384b) | Mar 24, 2019 |
| Unknown       | Unknown                     | [52b4b037a1](https://linux-hardware.org/?probe=52b4b037a1) | Feb 01, 2019 |
| Unknown       | Unknown                     | [f9908c15ca](https://linux-hardware.org/?probe=f9908c15ca) | Feb 01, 2019 |
| ASRock        | B75M-DGS R2.0               | [b54d9c9c47](https://linux-hardware.org/?probe=b54d9c9c47) | Dec 19, 2018 |
| PCWare        | IPX1800G2                   | [1721a635e2](https://linux-hardware.org/?probe=1721a635e2) | Nov 25, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Lubuntu/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Lubuntu 20.04    | 155      | 34.22%  |
| Lubuntu 22.04    | 100      | 22.08%  |
| Lubuntu 18.04    | 75       | 16.56%  |
| Lubuntu 21.10    | 29       | 6.4%    |
| Lubuntu 19.10    | 17       | 3.75%   |
| Lubuntu 16.04    | 16       | 3.53%   |
| Lubuntu 20.10    | 15       | 3.31%   |
| Lubuntu 21.04    | 13       | 2.87%   |
| Lubuntu 23.04    | 12       | 2.65%   |
| Lubuntu 22.10    | 10       | 2.21%   |
| Lubuntu 18.10    | 4        | 0.88%   |
| Lubuntu 19.04    | 2        | 0.44%   |
| Lubuntu 16.10    | 2        | 0.44%   |
| Lubuntu 23.10    | 1        | 0.22%   |
| Lubuntu 18.04.05 | 1        | 0.22%   |
| Lubuntu 17.04    | 1        | 0.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Lubuntu | 442      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 5.4.0-42-generic   | 11       | 2.23%   |
| 5.15.0-43-generic  | 11       | 2.23%   |
| 5.4.0-52-generic   | 8        | 1.62%   |
| 5.8.0-50-generic   | 7        | 1.42%   |
| 5.15.0-60-generic  | 7        | 1.42%   |
| 5.13.0-19-generic  | 7        | 1.42%   |
| 5.11.0-27-generic  | 7        | 1.42%   |
| 4.15.0-142-generic | 6        | 1.22%   |
| 5.4.0-54-generic   | 5        | 1.01%   |
| 5.19.0-50-generic  | 5        | 1.01%   |
| 5.19.0-32-generic  | 5        | 1.01%   |
| 5.15.0-41-generic  | 5        | 1.01%   |
| 5.13.0-40-generic  | 5        | 1.01%   |
| 5.13.0-28-generic  | 5        | 1.01%   |
| 5.8.0-59-generic   | 4        | 0.81%   |
| 5.4.0-91-generic   | 4        | 0.81%   |
| 5.4.0-77-generic   | 4        | 0.81%   |
| 5.4.0-67-generic   | 4        | 0.81%   |
| 5.4.0-48-generic   | 4        | 0.81%   |
| 5.4.0-47-generic   | 4        | 0.81%   |
| 5.4.0-40-generic   | 4        | 0.81%   |
| 5.4.0-29-generic   | 4        | 0.81%   |
| 5.4.0-122-generic  | 4        | 0.81%   |
| 5.15.0-75-generic  | 4        | 0.81%   |
| 5.15.0-56-generic  | 4        | 0.81%   |
| 5.15.0-53-generic  | 4        | 0.81%   |
| 5.15.0-52-generic  | 4        | 0.81%   |
| 5.15.0-48-generic  | 4        | 0.81%   |
| 5.15.0-47-generic  | 4        | 0.81%   |
| 5.15.0-25-generic  | 4        | 0.81%   |
| 4.15.0-74-generic  | 4        | 0.81%   |
| 4.15.0-106-generic | 4        | 0.81%   |
| 6.2.0-35-generic   | 3        | 0.61%   |
| 6.2.0-26-generic   | 3        | 0.61%   |
| 6.2.0-25-generic   | 3        | 0.61%   |
| 5.8.0-63-generic   | 3        | 0.61%   |
| 5.8.0-53-generic   | 3        | 0.61%   |
| 5.8.0-49-generic   | 3        | 0.61%   |
| 5.8.0-41-generic   | 3        | 0.61%   |
| 5.4.0-96-generic   | 3        | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 105      | 22.83%  |
| 5.15.0  | 86       | 18.7%   |
| 4.15.0  | 61       | 13.26%  |
| 5.13.0  | 41       | 8.91%   |
| 5.8.0   | 37       | 8.04%   |
| 5.11.0  | 31       | 6.74%   |
| 5.19.0  | 26       | 5.65%   |
| 5.3.0   | 20       | 4.35%   |
| 6.2.0   | 16       | 3.48%   |
| 5.0.0   | 5        | 1.09%   |
| 4.4.0   | 4        | 0.87%   |
| 4.18.0  | 4        | 0.87%   |
| 6.1.0   | 2        | 0.43%   |
| 4.8.0   | 2        | 0.43%   |
| 6.5.8   | 1        | 0.22%   |
| 6.5.0   | 1        | 0.22%   |
| 6.3.3   | 1        | 0.22%   |
| 6.2.8   | 1        | 0.22%   |
| 6.2.6   | 1        | 0.22%   |
| 6.1.46  | 1        | 0.22%   |
| 6.1.3   | 1        | 0.22%   |
| 6.0.9   | 1        | 0.22%   |
| 6.0.8   | 1        | 0.22%   |
| 6.0.14  | 1        | 0.22%   |
| 5.6.15  | 1        | 0.22%   |
| 5.6.0   | 1        | 0.22%   |
| 5.4.30  | 1        | 0.22%   |
| 5.3.18  | 1        | 0.22%   |
| 5.16.5  | 1        | 0.22%   |
| 5.15.5  | 1        | 0.22%   |
| 5.14.0  | 1        | 0.22%   |
| 5.12.1  | 1        | 0.22%   |
| 4.15.18 | 1        | 0.22%   |
| 4.10.0  | 1        | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 106      | 23.04%  |
| 5.15    | 87       | 18.91%  |
| 4.15    | 62       | 13.48%  |
| 5.13    | 41       | 8.91%   |
| 5.8     | 37       | 8.04%   |
| 5.11    | 31       | 6.74%   |
| 5.19    | 26       | 5.65%   |
| 5.3     | 21       | 4.57%   |
| 6.2     | 18       | 3.91%   |
| 5.0     | 5        | 1.09%   |
| 6.1     | 4        | 0.87%   |
| 4.4     | 4        | 0.87%   |
| 4.18    | 4        | 0.87%   |
| 6.0     | 3        | 0.65%   |
| 6.5     | 2        | 0.43%   |
| 5.6     | 2        | 0.43%   |
| 4.8     | 2        | 0.43%   |
| 6.3     | 1        | 0.22%   |
| 5.16    | 1        | 0.22%   |
| 5.14    | 1        | 0.22%   |
| 5.12    | 1        | 0.22%   |
| 4.10    | 1        | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 402      | 90.95%  |
| i686   | 39       | 8.82%   |
| ppc64  | 1        | 0.23%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| LXQt            | 331      | 74.38%  |
| LXDE            | 88       | 19.78%  |
| GNOME           | 10       | 2.25%   |
| Unknown         | 7        | 1.57%   |
| XFCE            | 2        | 0.45%   |
| Openbox         | 2        | 0.45%   |
| X-Cinnamon      | 1        | 0.22%   |
| Lubuntu         | 1        | 0.22%   |
| KDE5            | 1        | 0.22%   |
| i3              | 1        | 0.22%   |
| GNOME Flashback | 1        | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 427      | 95.53%  |
| Tty         | 14       | 3.13%   |
| Wayland     | 3        | 0.67%   |
| Unknown     | 2        | 0.45%   |
| Unspecified | 1        | 0.22%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 225      | 50.11%  |
| Unknown | 132      | 29.4%   |
| LightDM | 48       | 10.69%  |
| TDM     | 24       | 5.35%   |
| GDM     | 12       | 2.67%   |
| GDM3    | 3        | 0.67%   |
| XDM     | 2        | 0.45%   |
| LXDM    | 2        | 0.45%   |
| SLiM    | 1        | 0.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 116      | 26.07%  |
| fr_FR   | 52       | 11.69%  |
| de_DE   | 35       | 7.87%   |
| pt_BR   | 29       | 6.52%   |
| it_IT   | 27       | 6.07%   |
| en_GB   | 23       | 5.17%   |
| C       | 20       | 4.49%   |
| ru_RU   | 15       | 3.37%   |
| Unknown | 13       | 2.92%   |
| es_ES   | 11       | 2.47%   |
| en_CA   | 11       | 2.47%   |
| es_AR   | 9        | 2.02%   |
| en_AU   | 8        | 1.8%    |
| pl_PL   | 5        | 1.12%   |
| hu_HU   | 5        | 1.12%   |
| fi_FI   | 5        | 1.12%   |
| cs_CZ   | 5        | 1.12%   |
| nl_NL   | 4        | 0.9%    |
| ja_JP   | 4        | 0.9%    |
| es_MX   | 4        | 0.9%    |
| tr_TR   | 3        | 0.67%   |
| es_PE   | 3        | 0.67%   |
| en_IN   | 3        | 0.67%   |
| el_GR   | 3        | 0.67%   |
| zh_TW   | 2        | 0.45%   |
| sv_SE   | 2        | 0.45%   |
| pt_PT   | 2        | 0.45%   |
| fr_CA   | 2        | 0.45%   |
| es_UY   | 2        | 0.45%   |
| es_CR   | 2        | 0.45%   |
| es_CO   | 2        | 0.45%   |
| en_ZA   | 2        | 0.45%   |
| de_CH   | 2        | 0.45%   |
| bg_BG   | 2        | 0.45%   |
| ru_UA   | 1        | 0.22%   |
| nl_BE   | 1        | 0.22%   |
| lt_LT   | 1        | 0.22%   |
| hr_HR   | 1        | 0.22%   |
| es_GT   | 1        | 0.22%   |
| es_EC   | 1        | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 322      | 72.69%  |
| EFI  | 121      | 27.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 399      | 89.86%  |
| Overlay | 21       | 4.73%   |
| Tmpfs   | 9        | 2.03%   |
| Btrfs   | 5        | 1.13%   |
| Xfs     | 4        | 0.9%    |
| Unknown | 2        | 0.45%   |
| Zfs     | 1        | 0.23%   |
| XXX4    | 1        | 0.23%   |
| F2fs    | 1        | 0.23%   |
| Ext3    | 1        | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 186      | 41.7%   |
| GPT     | 133      | 29.82%  |
| MBR     | 127      | 28.48%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 369      | 82.74%  |
| Yes       | 77       | 17.26%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 298      | 67.12%  |
| Yes       | 146      | 32.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 84       | 19%     |
| Gigabyte Technology | 50       | 11.31%  |
| MSI                 | 43       | 9.73%   |
| Hewlett-Packard     | 41       | 9.28%   |
| ASRock              | 41       | 9.28%   |
| Dell                | 39       | 8.82%   |
| Intel               | 24       | 5.43%   |
| Lenovo              | 17       | 3.85%   |
| Acer                | 15       | 3.39%   |
| Unknown             | 15       | 3.39%   |
| Pegatron            | 11       | 2.49%   |
| Foxconn             | 9        | 2.04%   |
| Biostar             | 5        | 1.13%   |
| AMI                 | 5        | 1.13%   |
| AAEON               | 5        | 1.13%   |
| Positivo            | 4        | 0.9%    |
| Fujitsu             | 3        | 0.68%   |
| PCWare              | 2        | 0.45%   |
| PCChips             | 2        | 0.45%   |
| IBM                 | 2        | 0.45%   |
| Fujitsu Siemens     | 2        | 0.45%   |
| eMachines           | 2        | 0.45%   |
| ECS                 | 2        | 0.45%   |
| Apple               | 2        | 0.45%   |
| ZOTAC               | 1        | 0.23%   |
| YANYU               | 1        | 0.23%   |
| VIA Technologies    | 1        | 0.23%   |
| Shuttle             | 1        | 0.23%   |
| Seeed Studio        | 1        | 0.23%   |
| Qbex                | 1        | 0.23%   |
| Philco              | 1        | 0.23%   |
| Packard Bell        | 1        | 0.23%   |
| NEC Computers       | 1        | 0.23%   |
| Medion              | 1        | 0.23%   |
| Inventec            | 1        | 0.23%   |
| IceWhale Technology | 1        | 0.23%   |
| Huanan              | 1        | 0.23%   |
| Hardkernel          | 1        | 0.23%   |
| Gateway             | 1        | 0.23%   |
| BANGHO              | 1        | 0.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| Unknown                              | 15       | 3.39%   |
| AAEON MF-001                         | 5        | 1.13%   |
| MSI MS-7C37                          | 4        | 0.9%    |
| HP t620 Quad Core TC                 | 4        | 0.9%    |
| Dell OptiPlex 7010                   | 4        | 0.9%    |
| Dell OptiPlex 790                    | 3        | 0.68%   |
| ASUS V-P8H67E                        | 3        | 0.68%   |
| ASUS All Series                      | 3        | 0.68%   |
| ASRock FM2A85X Extreme6              | 3        | 0.68%   |
| Pegatron NC689AA-ABA s3700y          | 2        | 0.45%   |
| Pegatron Compaq dx2400 Microtower PC | 2        | 0.45%   |
| MSI MS-7C56                          | 2        | 0.45%   |
| MSI MS-7B89                          | 2        | 0.45%   |
| MSI MS-7B86                          | 2        | 0.45%   |
| MSI MS-7721                          | 2        | 0.45%   |
| HP t620 Dual Core TC                 | 2        | 0.45%   |
| HP Compaq dc7800 Small Form Factor   | 2        | 0.45%   |
| HP Compaq 6000 Pro SFF PC            | 2        | 0.45%   |
| Gigabyte H81M-DS2                    | 2        | 0.45%   |
| Gigabyte G31M-ES2C                   | 2        | 0.45%   |
| Dell OptiPlex 755                    | 2        | 0.45%   |
| Dell OptiPlex 3050                   | 2        | 0.45%   |
| Dell DM061                           | 2        | 0.45%   |
| Dell Dimension 9100                  | 2        | 0.45%   |
| ASUS TUF Gaming X570-PLUS            | 2        | 0.45%   |
| ASUS PRIME H410M-E                   | 2        | 0.45%   |
| ASUS P5QD TURBO                      | 2        | 0.45%   |
| ASUS M5A97 R2.0                      | 2        | 0.45%   |
| ASRock N68-VS3 UCC                   | 2        | 0.45%   |
| ASRock G41M-VS3                      | 2        | 0.45%   |
| ASRock G31M-S                        | 2        | 0.45%   |
| ASRock 775Dual-VSTA                  | 2        | 0.45%   |
| AMI Z83-V                            | 2        | 0.45%   |
| ZOTAC NM10                           | 1        | 0.23%   |
| YANYU ITX-S192                       | 1        | 0.23%   |
| VIA P4X266-8233                      | 1        | 0.23%   |
| Shuttle XS35V3                       | 1        | 0.23%   |
| Seeed Studio ODYSSEY-X86J4125        | 1        | 0.23%   |
| Qbex HDC-M                           | 1        | 0.23%   |
| Positivo POS-MI945AA                 | 1        | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| HP Compaq            | 20       | 4.52%   |
| Dell OptiPlex        | 20       | 4.52%   |
| Unknown              | 15       | 3.39%   |
| Lenovo ThinkCentre   | 13       | 2.94%   |
| Acer Aspire          | 11       | 2.49%   |
| ASUS PRIME           | 7        | 1.58%   |
| HP t620              | 6        | 1.36%   |
| AAEON MF-001         | 5        | 1.13%   |
| MSI MS-7C37          | 4        | 0.9%    |
| Dell Vostro          | 4        | 0.9%    |
| Dell Dimension       | 4        | 0.9%    |
| ASUS ROG             | 4        | 0.9%    |
| ASUS M5A97           | 4        | 0.9%    |
| Dell Precision       | 3        | 0.68%   |
| Dell Inspiron        | 3        | 0.68%   |
| ASUS V-P8H67E        | 3        | 0.68%   |
| ASUS TUF             | 3        | 0.68%   |
| ASUS All             | 3        | 0.68%   |
| ASRock FM2A85X       | 3        | 0.68%   |
| Pegatron NC689AA-ABA | 2        | 0.45%   |
| Pegatron Compaq      | 2        | 0.45%   |
| MSI MS-7C56          | 2        | 0.45%   |
| MSI MS-7B89          | 2        | 0.45%   |
| MSI MS-7B86          | 2        | 0.45%   |
| MSI MS-7721          | 2        | 0.45%   |
| Intel X79            | 2        | 0.45%   |
| Intel DG31PR         | 2        | 0.45%   |
| HP EliteDesk         | 2        | 0.45%   |
| HP dc5000            | 2        | 0.45%   |
| Gigabyte H81M-DS2    | 2        | 0.45%   |
| Gigabyte G31M-ES2C   | 2        | 0.45%   |
| Gigabyte B450M       | 2        | 0.45%   |
| Dell Studio          | 2        | 0.45%   |
| Dell DM061           | 2        | 0.45%   |
| ASUS P8P67           | 2        | 0.45%   |
| ASUS P5QD            | 2        | 0.45%   |
| ASUS P5G41T-M        | 2        | 0.45%   |
| ASRock N68-VS3       | 2        | 0.45%   |
| ASRock G41M-VS3      | 2        | 0.45%   |
| ASRock G31M-S        | 2        | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 37       | 8.37%   |
| 2011    | 37       | 8.37%   |
| 2008    | 37       | 8.37%   |
| 2009    | 36       | 8.14%   |
| 2010    | 33       | 7.47%   |
| 2007    | 33       | 7.47%   |
| 2013    | 30       | 6.79%   |
| 2017    | 25       | 5.66%   |
| 2014    | 25       | 5.66%   |
| 2020    | 24       | 5.43%   |
| 2006    | 24       | 5.43%   |
| 2019    | 18       | 4.07%   |
| 2015    | 17       | 3.85%   |
| 2018    | 15       | 3.39%   |
| 2021    | 14       | 3.17%   |
| 2005    | 13       | 2.94%   |
| 2016    | 7        | 1.58%   |
| 2022    | 5        | 1.13%   |
| 2004    | 5        | 1.13%   |
| 2001    | 2        | 0.45%   |
| Unknown | 2        | 0.45%   |
| 2003    | 1        | 0.23%   |
| 2002    | 1        | 0.23%   |
| 2000    | 1        | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 442      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 432      | 97.74%  |
| Enabled  | 10       | 2.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 442      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 110      | 24.34%  |
| 4.01-8.0        | 78       | 17.26%  |
| 8.01-16.0       | 64       | 14.16%  |
| 1.01-2.0        | 62       | 13.72%  |
| 16.01-24.0      | 56       | 12.39%  |
| 32.01-64.0      | 31       | 6.86%   |
| 2.01-3.0        | 17       | 3.76%   |
| 0.51-1.0        | 14       | 3.1%    |
| 64.01-256.0     | 8        | 1.77%   |
| 24.01-32.0      | 6        | 1.33%   |
| 0.01-0.5        | 5        | 1.11%   |
| More than 256.0 | 1        | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 201      | 42.58%  |
| 0.51-1.0   | 105      | 22.25%  |
| 2.01-3.0   | 77       | 16.31%  |
| 4.01-8.0   | 40       | 8.47%   |
| 0.01-0.5   | 23       | 4.87%   |
| 3.01-4.0   | 16       | 3.39%   |
| 8.01-16.0  | 8        | 1.69%   |
| 32.01-64.0 | 1        | 0.21%   |
| 16.01-24.0 | 1        | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 238      | 53.48%  |
| 2      | 121      | 27.19%  |
| 3      | 31       | 6.97%   |
| 4      | 25       | 5.62%   |
| 5      | 13       | 2.92%   |
| 0      | 5        | 1.12%   |
| 6      | 4        | 0.9%    |
| 8      | 2        | 0.45%   |
| 7      | 2        | 0.45%   |
| 17     | 1        | 0.22%   |
| 14     | 1        | 0.22%   |
| 12     | 1        | 0.22%   |
| 10     | 1        | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 228      | 51.12%  |
| Yes       | 218      | 48.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 435      | 98.42%  |
| No        | 7        | 1.58%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 269      | 60.45%  |
| Yes       | 176      | 39.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 367      | 82.29%  |
| Yes       | 79       | 17.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 69       | 15.54%  |
| France       | 52       | 11.71%  |
| Germany      | 39       | 8.78%   |
| Brazil       | 36       | 8.11%   |
| Italy        | 30       | 6.76%   |
| Russia       | 19       | 4.28%   |
| Canada       | 15       | 3.38%   |
| UK           | 14       | 3.15%   |
| Spain        | 14       | 3.15%   |
| Argentina    | 10       | 2.25%   |
| Poland       | 9        | 2.03%   |
| Netherlands  | 9        | 2.03%   |
| Finland      | 9        | 2.03%   |
| Hungary      | 8        | 1.8%    |
| Australia    | 8        | 1.8%    |
| Switzerland  | 7        | 1.58%   |
| Czechia      | 6        | 1.35%   |
| India        | 5        | 1.13%   |
| Turkey       | 4        | 0.9%    |
| Mexico       | 4        | 0.9%    |
| Japan        | 4        | 0.9%    |
| Greece       | 4        | 0.9%    |
| Bulgaria     | 4        | 0.9%    |
| Belgium      | 4        | 0.9%    |
| Sweden       | 3        | 0.68%   |
| South Africa | 3        | 0.68%   |
| Peru         | 3        | 0.68%   |
| Malaysia     | 3        | 0.68%   |
| Indonesia    | 3        | 0.68%   |
| Colombia     | 3        | 0.68%   |
| Uruguay      | 2        | 0.45%   |
| Taiwan       | 2        | 0.45%   |
| Slovakia     | 2        | 0.45%   |
| Romania      | 2        | 0.45%   |
| Puerto Rico  | 2        | 0.45%   |
| New Zealand  | 2        | 0.45%   |
| Luxembourg   | 2        | 0.45%   |
| Ireland      | 2        | 0.45%   |
| Iran         | 2        | 0.45%   |
| Costa Rica   | 2        | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Sao Paulo         | 5        | 1.09%   |
| Rome              | 5        | 1.09%   |
| Milan             | 5        | 1.09%   |
| Melbourne         | 5        | 1.09%   |
| Lyon              | 5        | 1.09%   |
| Paris             | 4        | 0.87%   |
| Oshawa            | 4        | 0.87%   |
| Zurich            | 3        | 0.65%   |
| Wellington        | 3        | 0.65%   |
| Voronezh          | 3        | 0.65%   |
| Tampere           | 3        | 0.65%   |
| Rio de Janeiro    | 3        | 0.65%   |
| Prague            | 3        | 0.65%   |
| Nederland         | 3        | 0.65%   |
| Kuala Lumpur      | 3        | 0.65%   |
| Warsaw            | 2        | 0.43%   |
| Valencia          | 2        | 0.43%   |
| Toulouse          | 2        | 0.43%   |
| Toronto           | 2        | 0.43%   |
| St Petersburg     | 2        | 0.43%   |
| Raahe             | 2        | 0.43%   |
| Pécs             | 2        | 0.43%   |
| Novo Gama         | 2        | 0.43%   |
| Nitra             | 2        | 0.43%   |
| New York          | 2        | 0.43%   |
| Moscow            | 2        | 0.43%   |
| Mobile            | 2        | 0.43%   |
| Mason             | 2        | 0.43%   |
| Marseille         | 2        | 0.43%   |
| Madrid            | 2        | 0.43%   |
| Luxembourg        | 2        | 0.43%   |
| Largo             | 2        | 0.43%   |
| Karlstad          | 2        | 0.43%   |
| Istanbul          | 2        | 0.43%   |
| Heredia           | 2        | 0.43%   |
| Helsinki          | 2        | 0.43%   |
| Hamburg           | 2        | 0.43%   |
| Frankfurt am Main | 2        | 0.43%   |
| Figeac            | 2        | 0.43%   |
| Denver            | 2        | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 155      | 215    | 22.66%  |
| WDC                         | 139      | 206    | 20.32%  |
| Samsung Electronics         | 79       | 126    | 11.55%  |
| Hitachi                     | 40       | 51     | 5.85%   |
| Kingston                    | 37       | 45     | 5.41%   |
| Toshiba                     | 27       | 29     | 3.95%   |
| SanDisk                     | 22       | 23     | 3.22%   |
| Crucial                     | 22       | 36     | 3.22%   |
| Maxtor                      | 19       | 21     | 2.78%   |
| Unknown                     | 17       | 20     | 2.49%   |
| A-DATA Technology           | 10       | 12     | 1.46%   |
| HGST                        | 8        | 10     | 1.17%   |
| China                       | 7        | 7      | 1.02%   |
| Intel                       | 6        | 6      | 0.88%   |
| Team                        | 4        | 4      | 0.58%   |
| PNY                         | 4        | 4      | 0.58%   |
| Micron Technology           | 4        | 4      | 0.58%   |
| Intenso                     | 4        | 4      | 0.58%   |
| Corsair                     | 4        | 4      | 0.58%   |
| TO Exter                    | 3        | 3      | 0.44%   |
| SPCC                        | 3        | 5      | 0.44%   |
| Lexar                       | 3        | 3      | 0.44%   |
| Hewlett-Packard             | 3        | 8      | 0.44%   |
| GOODRAM                     | 3        | 3      | 0.44%   |
| Transcend                   | 2        | 3      | 0.29%   |
| Silicon Motion              | 2        | 3      | 0.29%   |
| Plextor                     | 2        | 4      | 0.29%   |
| Patriot                     | 2        | 2      | 0.29%   |
| OCZ                         | 2        | 2      | 0.29%   |
| Londisk                     | 2        | 2      | 0.29%   |
| LITEONIT                    | 2        | 2      | 0.29%   |
| LDLC                        | 2        | 2      | 0.29%   |
| Kingston Technology Company | 2        | 2      | 0.29%   |
| JMicron Technology          | 2        | 2      | 0.29%   |
| Fujitsu                     | 2        | 2      | 0.29%   |
| External                    | 2        | 2      | 0.29%   |
| Apple                       | 2        | 2      | 0.29%   |
| Apacer                      | 2        | 2      | 0.29%   |
| Unknown                     | 2        | 2      | 0.29%   |
| WD MediaMax                 | 1        | 1      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 13       | 1.68%   |
| Kingston SA400S37240G 240GB SSD     | 10       | 1.29%   |
| Seagate ST1000DM010-2EP102 1TB      | 7        | 0.9%    |
| Seagate ST3500418AS 500GB           | 6        | 0.77%   |
| Seagate ST2000DM008-2FR102 2TB      | 6        | 0.77%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 5        | 0.65%   |
| Seagate ST3250310AS 250GB           | 5        | 0.65%   |
| Samsung SSD 850 EVO 500GB           | 5        | 0.65%   |
| Samsung HD103SJ 1TB                 | 5        | 0.65%   |
| Kingston SA400S37120G 120GB SSD     | 5        | 0.65%   |
| Crucial CT1000BX500SSD1 1TB         | 5        | 0.65%   |
| Unknown M52516  16GB                | 4        | 0.52%   |
| Seagate ST3500312CS 500GB           | 4        | 0.52%   |
| Seagate ST31000528AS 1TB            | 4        | 0.52%   |
| Seagate ST2000DM001-1CH164 2TB      | 4        | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4        | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB      | 4        | 0.52%   |
| Samsung SSD 850 EVO 250GB           | 4        | 0.52%   |
| Samsung HD502IJ 500GB               | 4        | 0.52%   |
| Samsung HD161HJ 160GB               | 4        | 0.52%   |
| Kingston SA400S37480G 480GB SSD     | 4        | 0.52%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 3        | 0.39%   |
| WDC WD40EFRX-68WT0N0 4TB            | 3        | 0.39%   |
| WDC WD20EFRX-68EUZN0 2TB            | 3        | 0.39%   |
| WDC WD10EZEX-60WN4A0 1TB            | 3        | 0.39%   |
| Toshiba DT01ACA050 500GB            | 3        | 0.39%   |
| TO Exter nal USB 3.0 2TB            | 3        | 0.39%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3        | 0.39%   |
| Seagate ST4000DM004-2CV104 4TB      | 3        | 0.39%   |
| Seagate ST380013AS 80GB             | 3        | 0.39%   |
| Seagate ST3360320AS 360GB           | 3        | 0.39%   |
| Seagate ST3250410AS 250GB           | 3        | 0.39%   |
| Seagate ST3160318AS 160GB           | 3        | 0.39%   |
| Seagate ST2000DM001-1ER164 2TB      | 3        | 0.39%   |
| Seagate ST1000DM003-9YN162 1TB      | 3        | 0.39%   |
| Seagate ST1000DM003-1ER162 1TB      | 3        | 0.39%   |
| Seagate Expansion 1TB               | 3        | 0.39%   |
| SanDisk SDSSDP128G 128GB            | 3        | 0.39%   |
| Samsung SSD 980 PRO 2TB             | 3        | 0.39%   |
| Samsung SSD 970 EVO Plus 500GB      | 3        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 154      | 213    | 36.84%  |
| WDC                 | 127      | 184    | 30.38%  |
| Hitachi             | 40       | 51     | 9.57%   |
| Samsung Electronics | 36       | 47     | 8.61%   |
| Toshiba             | 23       | 25     | 5.5%    |
| Maxtor              | 18       | 20     | 4.31%   |
| HGST                | 8        | 10     | 1.91%   |
| Unknown             | 2        | 2      | 0.48%   |
| Hewlett-Packard     | 2        | 2      | 0.48%   |
| Fujitsu             | 2        | 2      | 0.48%   |
| External            | 2        | 2      | 0.48%   |
| WD MediaMax         | 1        | 1      | 0.24%   |
| RSH-319             | 1        | 1      | 0.24%   |
| Apricorn            | 1        | 1      | 0.24%   |
| Apple               | 1        | 1      | 0.24%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 34       | 51     | 16.27%  |
| Kingston            | 33       | 41     | 15.79%  |
| SanDisk             | 18       | 19     | 8.61%   |
| Crucial             | 17       | 31     | 8.13%   |
| WDC                 | 15       | 18     | 7.18%   |
| A-DATA Technology   | 8        | 10     | 3.83%   |
| China               | 7        | 7      | 3.35%   |
| Intel               | 5        | 5      | 2.39%   |
| Toshiba             | 4        | 4      | 1.91%   |
| Team                | 4        | 4      | 1.91%   |
| PNY                 | 4        | 4      | 1.91%   |
| Micron Technology   | 4        | 4      | 1.91%   |
| Intenso             | 4        | 4      | 1.91%   |
| Corsair             | 4        | 4      | 1.91%   |
| TO Exter            | 3        | 3      | 1.44%   |
| Lexar               | 3        | 3      | 1.44%   |
| GOODRAM             | 3        | 3      | 1.44%   |
| Transcend           | 2        | 3      | 0.96%   |
| Plextor             | 2        | 4      | 0.96%   |
| Patriot             | 2        | 2      | 0.96%   |
| OCZ                 | 2        | 2      | 0.96%   |
| Londisk             | 2        | 2      | 0.96%   |
| LITEONIT            | 2        | 2      | 0.96%   |
| Apacer              | 2        | 2      | 0.96%   |
| Verbatim            | 1        | 1      | 0.48%   |
| Unknown             | 1        | 1      | 0.48%   |
| TSA                 | 1        | 1      | 0.48%   |
| SPCC                | 1        | 1      | 0.48%   |
| Smartbuy            | 1        | 1      | 0.48%   |
| PNY USB             | 1        | 1      | 0.48%   |
| ORTIAL              | 1        | 1      | 0.48%   |
| Mushkin             | 1        | 1      | 0.48%   |
| Maxtor              | 1        | 1      | 0.48%   |
| Leven               | 1        | 2      | 0.48%   |
| LDLC                | 1        | 1      | 0.48%   |
| Kston               | 1        | 4      | 0.48%   |
| KLEVV               | 1        | 1      | 0.48%   |
| KINGBANK            | 1        | 2      | 0.48%   |
| KimMiDi             | 1        | 1      | 0.48%   |
| HS-SSD-E100         | 1        | 1      | 0.48%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 318      | 562    | 56.08%  |
| SSD     | 188      | 267    | 33.16%  |
| NVMe    | 38       | 63     | 6.7%    |
| MMC     | 17       | 19     | 3%      |
| Unknown | 6        | 10     | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 412      | 809    | 84.6%   |
| NVMe | 37       | 62     | 7.6%    |
| SAS  | 21       | 31     | 4.31%   |
| MMC  | 17       | 19     | 3.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 347      | 530    | 64.86%  |
| 0.51-1.0   | 106      | 165    | 19.81%  |
| 1.01-2.0   | 45       | 70     | 8.41%   |
| 3.01-4.0   | 17       | 37     | 3.18%   |
| 2.01-3.0   | 12       | 15     | 2.24%   |
| 4.01-10.0  | 8        | 12     | 1.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 133      | 29.49%  |
| 251-500        | 89       | 19.73%  |
| 501-1000       | 47       | 10.42%  |
| 1001-2000      | 38       | 8.43%   |
| 51-100         | 36       | 7.98%   |
| More than 3000 | 32       | 7.1%    |
| 21-50          | 28       | 6.21%   |
| 1-20           | 25       | 5.54%   |
| 2001-3000      | 20       | 4.43%   |
| Unknown        | 3        | 0.67%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 198      | 42.58%  |
| 21-50          | 80       | 17.2%   |
| 101-250        | 53       | 11.4%   |
| 51-100         | 34       | 7.31%   |
| 251-500        | 27       | 5.81%   |
| 501-1000       | 26       | 5.59%   |
| 1001-2000      | 21       | 4.52%   |
| More than 3000 | 16       | 3.44%   |
| 2001-3000      | 7        | 1.51%   |
| Unknown        | 3        | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Desktops | Drives | Percent |
|------------------------------------|----------|--------|---------|
| Seagate ST1000DM003-9YN162 1TB     | 3        | 3      | 3.8%    |
| WDC WD40EFRX-68WT0N0 4TB           | 2        | 3      | 2.53%   |
| Seagate ST500DM002-1BD142 500GB    | 2        | 2      | 2.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2        | 3      | 2.53%   |
| Samsung Electronics HD502IJ 500GB  | 2        | 2      | 2.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1        | 1      | 1.27%   |
| WDC WD60EFRX-68L0BN1 6TB           | 1        | 2      | 1.27%   |
| WDC WD5000AAKX-003CA0 500GB        | 1        | 1      | 1.27%   |
| WDC WD400EB-00CPF0 40GB            | 1        | 1      | 1.27%   |
| WDC WD400BB-75CAA0 40GB            | 1        | 1      | 1.27%   |
| WDC WD3200AACS-00M6B0 320GB        | 1        | 1      | 1.27%   |
| WDC WD2500HHTZ-04N21V0 250GB       | 1        | 1      | 1.27%   |
| WDC WD2500AAJS-75M0A0 249GB        | 1        | 1      | 1.27%   |
| WDC WD20EFRX-68EUZN0 2TB           | 1        | 1      | 1.27%   |
| WDC WD2003FYYS-02W0B0 2TB          | 1        | 1      | 1.27%   |
| WDC WD1600AAJS-60B4A0 160GB        | 1        | 2      | 1.27%   |
| WDC WD10SPZX-08Z10 1TB             | 1        | 1      | 1.27%   |
| WDC WD10EZEX-60WN4A1 1TB           | 1        | 1      | 1.27%   |
| WDC WD10EZEX-60WN4A0 1TB           | 1        | 1      | 1.27%   |
| WDC WD10EADS-65M2B0 1TB            | 1        | 1      | 1.27%   |
| WDC WD10EACS-00D6B1 1TB            | 1        | 1      | 1.27%   |
| WDC WD1003FBYX-01Y7B0 1TB          | 1        | 2      | 1.27%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 1        | 1      | 1.27%   |
| Toshiba MK6465GSX 640GB            | 1        | 1      | 1.27%   |
| Toshiba HDWE140 4TB                | 1        | 1      | 1.27%   |
| Toshiba DT01ACA050 500GB           | 1        | 1      | 1.27%   |
| Seagate ST9500420AS 500GB          | 1        | 1      | 1.27%   |
| Seagate ST9500325AS 500GB          | 1        | 1      | 1.27%   |
| Seagate ST9250315AS 250GB          | 1        | 1      | 1.27%   |
| Seagate ST9160310AS 160GB          | 1        | 1      | 1.27%   |
| Seagate ST4000DM004-2CV104 4TB     | 1        | 1      | 1.27%   |
| Seagate ST380815AS 80GB            | 1        | 1      | 1.27%   |
| Seagate ST380011A 80GB             | 1        | 1      | 1.27%   |
| Seagate ST360012A 64GB             | 1        | 1      | 1.27%   |
| Seagate ST3500413AS 500GB          | 1        | 1      | 1.27%   |
| Seagate ST3360320AS 360GB          | 1        | 1      | 1.27%   |
| Seagate ST3250310AS 250GB          | 1        | 1      | 1.27%   |
| Seagate ST3200822AS 200GB          | 1        | 1      | 1.27%   |
| Seagate ST3160812AS 160GB          | 1        | 1      | 1.27%   |
| Seagate ST3160318AS 160GB          | 1        | 1      | 1.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 24       | 27     | 32.43%  |
| WDC                 | 18       | 24     | 24.32%  |
| Hitachi             | 7        | 8      | 9.46%   |
| Samsung Electronics | 5        | 5      | 6.76%   |
| Maxtor              | 5        | 5      | 6.76%   |
| Kingston            | 4        | 4      | 5.41%   |
| Toshiba             | 3        | 3      | 4.05%   |
| SanDisk             | 1        | 1      | 1.35%   |
| Mushkin             | 1        | 1      | 1.35%   |
| LDLC                | 1        | 1      | 1.35%   |
| Intel               | 1        | 1      | 1.35%   |
| Fujitsu             | 1        | 1      | 1.35%   |
| Apple               | 1        | 1      | 1.35%   |
| Apacer              | 1        | 1      | 1.35%   |
| A-DATA Technology   | 1        | 1      | 1.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 24       | 27     | 38.71%  |
| WDC                 | 17       | 23     | 27.42%  |
| Hitachi             | 7        | 8      | 11.29%  |
| Maxtor              | 5        | 5      | 8.06%   |
| Samsung Electronics | 4        | 4      | 6.45%   |
| Toshiba             | 3        | 3      | 4.84%   |
| Fujitsu             | 1        | 1      | 1.61%   |
| Apple               | 1        | 1      | 1.61%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 55       | 72     | 82.09%  |
| SSD  | 12       | 12     | 17.91%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Toshiba HDWD110 1TB               | 1        | 1      | 14.29%  |
| Seagate ST3500418AS 500GB         | 1        | 1      | 14.29%  |
| Samsung Electronics SSD 980 1TB   | 1        | 1      | 14.29%  |
| Samsung Electronics SSD 850 250GB | 1        | 1      | 14.29%  |
| Samsung Electronics HD080HJ 80GB  | 1        | 1      | 14.29%  |
| Intel SSDSA1M160G2HP 160GB        | 1        | 1      | 14.29%  |
| HGST HTS725025A7 250GB            | 1        | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 3      | 42.86%  |
| Toshiba             | 1        | 1      | 14.29%  |
| Seagate             | 1        | 1      | 14.29%  |
| Intel               | 1        | 1      | 14.29%  |
| HGST                | 1        | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 233      | 462    | 47.17%  |
| Works    | 190      | 368    | 38.46%  |
| Malfunc  | 64       | 84     | 12.96%  |
| Failed   | 7        | 7      | 1.42%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 264      | 49.91%  |
| AMD                              | 108      | 20.42%  |
| Nvidia                           | 43       | 8.13%   |
| JMicron Technology               | 18       | 3.4%    |
| ASMedia Technology               | 16       | 3.02%   |
| Samsung Electronics              | 15       | 2.84%   |
| Marvell Technology Group         | 13       | 2.46%   |
| VIA Technologies                 | 11       | 2.08%   |
| SanDisk                          | 6        | 1.13%   |
| Kingston Technology Company      | 6        | 1.13%   |
| Silicon Motion                   | 5        | 0.95%   |
| Micron/Crucial Technology        | 5        | 0.95%   |
| Silicon Image                    | 3        | 0.57%   |
| LSI Logic / Symbios Logic        | 3        | 0.57%   |
| ULi Electronics                  | 2        | 0.38%   |
| ADATA Technology                 | 2        | 0.38%   |
| SK hynix                         | 1        | 0.19%   |
| Silicon Integrated Systems [SiS] | 1        | 0.19%   |
| Shenzhen Longsys Electronics     | 1        | 0.19%   |
| Seagate Technology               | 1        | 0.19%   |
| Phison Electronics               | 1        | 0.19%   |
| Micron Technology                | 1        | 0.19%   |
| Broadcom                         | 1        | 0.19%   |
| Apple                            | 1        | 0.19%   |
| Adaptec                          | 1        | 0.19%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 58       | 7.84%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 46       | 6.22%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 32       | 4.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 22       | 2.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 20       | 2.7%    |
| Nvidia MCP61 SATA Controller                                                            | 19       | 2.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 17       | 2.3%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 17       | 2.3%    |
| Nvidia MCP61 IDE                                                                        | 16       | 2.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 16       | 2.16%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 14       | 1.89%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 13       | 1.76%   |
| AMD 400 Series Chipset SATA Controller                                                  | 13       | 1.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 12       | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12       | 1.62%   |
| Intel SATA Controller [RAID mode]                                                       | 11       | 1.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11       | 1.49%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 10       | 1.35%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 10       | 1.35%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 10       | 1.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 9        | 1.22%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 9        | 1.22%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 8        | 1.08%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 8        | 1.08%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 8        | 1.08%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8        | 1.08%   |
| Nvidia CK804 Serial ATA Controller                                                      | 7        | 0.95%   |
| Nvidia CK804 IDE                                                                        | 7        | 0.95%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 7        | 0.95%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 7        | 0.95%   |
| AMD FCH SATA Controller D                                                               | 7        | 0.95%   |
| AMD FCH IDE Controller                                                                  | 7        | 0.95%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 6        | 0.81%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 6        | 0.81%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5        | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 5        | 0.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5        | 0.68%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 5        | 0.68%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 5        | 0.68%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 5        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 257      | 47.95%  |
| IDE  | 213      | 39.74%  |
| NVMe | 37       | 6.9%    |
| RAID | 24       | 4.48%   |
| SCSI | 3        | 0.56%   |
| SAS  | 2        | 0.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Intel       | 291      | 65.84%  |
| AMD         | 150      | 33.94%  |
| PowerMac7,2 | 1        | 0.23%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 9        | 2.04%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 8        | 1.81%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 7        | 1.58%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 6        | 1.36%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 6        | 1.36%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 5        | 1.13%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 5        | 1.13%   |
| Intel Pentium 4 CPU 3.00GHz                 | 5        | 1.13%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 5        | 1.13%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 5        | 1.13%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 5        | 1.13%   |
| AMD GX-415GA SOC with Radeon HD Graphics    | 5        | 1.13%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 4        | 0.9%    |
| Intel Pentium D CPU 2.80GHz                 | 4        | 0.9%    |
| Intel Pentium 4 CPU 2.80GHz                 | 4        | 0.9%    |
| Intel Core i5-4570 CPU @ 3.20GHz            | 4        | 0.9%    |
| Intel Core i3-2120 CPU @ 3.30GHz            | 4        | 0.9%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 4        | 0.9%    |
| Intel Atom CPU D525 @ 1.80GHz               | 4        | 0.9%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 4        | 0.9%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4        | 0.9%    |
| AMD Athlon II X2 250 Processor              | 4        | 0.9%    |
| AMD Athlon 64 Processor 3000+               | 4        | 0.9%    |
| Intel Pentium Dual-Core CPU E5800 @ 3.20GHz | 3        | 0.68%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 3        | 0.68%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 3        | 0.68%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 3        | 0.68%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 3        | 0.68%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 3        | 0.68%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 3        | 0.68%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3        | 0.68%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3        | 0.68%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3        | 0.68%   |
| Intel Core 2 Duo CPU E7300 @ 2.66GHz        | 3        | 0.68%   |
| Intel Core 2 Duo CPU E7200 @ 2.53GHz        | 3        | 0.68%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 3        | 0.68%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 3        | 0.68%   |
| Intel Core 2 CPU 6300 @ 1.86GHz             | 3        | 0.68%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 3        | 0.68%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 3        | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 54       | 12.22%  |
| Intel Celeron           | 32       | 7.24%   |
| Intel Core 2 Duo        | 30       | 6.79%   |
| Intel Core i3           | 28       | 6.33%   |
| Intel Core i7           | 27       | 6.11%   |
| Intel Atom              | 23       | 5.2%    |
| AMD Athlon 64 X2        | 20       | 4.52%   |
| AMD Ryzen 5             | 18       | 4.07%   |
| Intel Pentium Dual-Core | 16       | 3.62%   |
| AMD Ryzen 7             | 15       | 3.39%   |
| Intel Xeon              | 14       | 3.17%   |
| Intel Pentium 4         | 14       | 3.17%   |
| Intel Core 2 Quad       | 14       | 3.17%   |
| Intel Pentium Dual      | 12       | 2.71%   |
| AMD FX                  | 12       | 2.71%   |
| AMD Athlon II X2        | 11       | 2.49%   |
| AMD A10                 | 9        | 2.04%   |
| Intel Core 2            | 8        | 1.81%   |
| AMD Athlon 64           | 8        | 1.81%   |
| AMD GX                  | 7        | 1.58%   |
| Intel Pentium D         | 6        | 1.36%   |
| Intel Pentium           | 6        | 1.36%   |
| AMD Phenom II X4        | 5        | 1.13%   |
| AMD A8                  | 5        | 1.13%   |
| Other                   | 4        | 0.9%    |
| AMD Ryzen 3             | 4        | 0.9%    |
| AMD Ryzen 9             | 3        | 0.68%   |
| AMD E1                  | 3        | 0.68%   |
| AMD E                   | 3        | 0.68%   |
| Intel Core i9           | 2        | 0.45%   |
| AMD Sempron             | 2        | 0.45%   |
| AMD Ryzen Threadripper  | 2        | 0.45%   |
| AMD Phenom II X6        | 2        | 0.45%   |
| AMD Athlon X4           | 2        | 0.45%   |
| AMD Athlon II X4        | 2        | 0.45%   |
| AMD Athlon II X3        | 2        | 0.45%   |
| AMD A4                  | 2        | 0.45%   |
| Intel Pentium III       | 1        | 0.23%   |
| Intel Pentium Gold      | 1        | 0.23%   |
| Intel Genuine           | 1        | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 193      | 43.67%  |
| 4      | 141      | 31.9%   |
| 1      | 43       | 9.73%   |
| 6      | 29       | 6.56%   |
| 8      | 21       | 4.75%   |
| 3      | 7        | 1.58%   |
| 12     | 3        | 0.68%   |
| 16     | 2        | 0.45%   |
| 10     | 2        | 0.45%   |
| 64     | 1        | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 437      | 98.87%  |
| 2      | 5        | 1.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 281      | 63.57%  |
| 2      | 160      | 36.2%   |
| 8      | 1        | 0.23%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 430      | 97.29%  |
| 32-bit         | 10       | 2.26%   |
| Unknown        | 2        | 0.45%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 133      | 29.69%  |
| 0x1067a    | 29       | 6.47%   |
| 0x206a7    | 25       | 5.58%   |
| 0x306c3    | 17       | 3.79%   |
| 0x306a9    | 16       | 3.57%   |
| 0x6fd      | 11       | 2.46%   |
| 0x6fb      | 10       | 2.23%   |
| 0x406c4    | 10       | 2.23%   |
| 0x06001119 | 9        | 2.01%   |
| 0x06000852 | 8        | 1.79%   |
| 0x0700010f | 7        | 1.56%   |
| 0x010000c8 | 7        | 1.56%   |
| 0x106ca    | 6        | 1.34%   |
| 0x10676    | 6        | 1.34%   |
| 0x08701021 | 6        | 1.34%   |
| 0x906ea    | 5        | 1.12%   |
| 0x6f2      | 5        | 1.12%   |
| 0x30678    | 5        | 1.12%   |
| 0x20655    | 5        | 1.12%   |
| 0x010000db | 5        | 1.12%   |
| 0xf41      | 4        | 0.89%   |
| 0xa0653    | 4        | 0.89%   |
| 0x906e9    | 4        | 0.89%   |
| 0x506e3    | 4        | 0.89%   |
| 0x0a50000c | 4        | 0.89%   |
| 0x0800820d | 4        | 0.89%   |
| 0x06003106 | 4        | 0.89%   |
| 0x010000c7 | 4        | 0.89%   |
| 0xf65      | 3        | 0.67%   |
| 0xf49      | 3        | 0.67%   |
| 0x6f6      | 3        | 0.67%   |
| 0x30679    | 3        | 0.67%   |
| 0x206d7    | 3        | 0.67%   |
| 0x0a50000d | 3        | 0.67%   |
| 0x0a201009 | 3        | 0.67%   |
| 0x08701013 | 3        | 0.67%   |
| 0x05000119 | 3        | 0.67%   |
| 0xf64      | 2        | 0.45%   |
| 0xf43      | 2        | 0.45%   |
| 0xf29      | 2        | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Penryn        | 48       | 10.86%  |
| Core          | 37       | 8.37%   |
| SandyBridge   | 34       | 7.69%   |
| K8 Hammer     | 32       | 7.24%   |
| IvyBridge     | 30       | 6.79%   |
| Haswell       | 28       | 6.33%   |
| K10           | 27       | 6.11%   |
| NetBurst      | 24       | 5.43%   |
| Silvermont    | 21       | 4.75%   |
| Piledriver    | 20       | 4.52%   |
| Zen 3         | 15       | 3.39%   |
| Zen+          | 12       | 2.71%   |
| Zen 2         | 12       | 2.71%   |
| KabyLake      | 12       | 2.71%   |
| Bonnell       | 11       | 2.49%   |
| CometLake     | 10       | 2.26%   |
| Westmere      | 9        | 2.04%   |
| Jaguar        | 9        | 2.04%   |
| Skylake       | 8        | 1.81%   |
| Nehalem       | 7        | 1.58%   |
| Bobcat        | 7        | 1.58%   |
| Steamroller   | 5        | 1.13%   |
| Goldmont plus | 5        | 1.13%   |
| Zen           | 3        | 0.68%   |
| Goldmont      | 3        | 0.68%   |
| Excavator     | 3        | 0.68%   |
| Unknown       | 3        | 0.68%   |
| K10 Llano     | 2        | 0.45%   |
| Tremont       | 1        | 0.23%   |
| P6            | 1        | 0.23%   |
| K6            | 1        | 0.23%   |
| Icelake       | 1        | 0.23%   |
| Bulldozer     | 1        | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 161      | 34.85%  |
| Nvidia                           | 152      | 32.9%   |
| AMD                              | 144      | 31.17%  |
| VIA Technologies                 | 3        | 0.65%   |
| Silicon Integrated Systems [SiS] | 1        | 0.22%   |
| Matrox Electronics Systems       | 1        | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19       | 3.93%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 18       | 3.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 13       | 2.69%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 12       | 2.48%   |
| Nvidia GT218 [GeForce 210]                                                               | 11       | 2.27%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 11       | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 10       | 2.07%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10       | 2.07%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 9        | 1.86%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 8        | 1.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 8        | 1.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8        | 1.65%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 7        | 1.45%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 6        | 1.24%   |
| Intel HD Graphics 530                                                                    | 6        | 1.24%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 6        | 1.24%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6        | 1.24%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 5        | 1.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5        | 1.03%   |
| Intel 82865G Integrated Graphics Controller                                              | 5        | 1.03%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 5        | 1.03%   |
| AMD Kabini [Radeon HD 8330E]                                                             | 5        | 1.03%   |
| AMD Juniper XT [Radeon HD 5770]                                                          | 5        | 1.03%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 5        | 1.03%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 4        | 0.83%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 4        | 0.83%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4        | 0.83%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 4        | 0.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4        | 0.83%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4        | 0.83%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 4        | 0.83%   |
| AMD RS780L [Radeon 3000]                                                                 | 4        | 0.83%   |
| AMD Richland [Radeon HD 8670D]                                                           | 4        | 0.83%   |
| Nvidia GT218 [ION]                                                                       | 3        | 0.62%   |
| Nvidia GK107 [GeForce GT 640]                                                            | 3        | 0.62%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 3        | 0.62%   |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                                  | 3        | 0.62%   |
| Intel HD Graphics 500                                                                    | 3        | 0.62%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 3        | 0.62%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| 1 x Intel          | 150      | 33.71%  |
| 1 x Nvidia         | 141      | 31.69%  |
| 1 x AMD            | 121      | 27.19%  |
| 2 x AMD            | 16       | 3.6%    |
| AMD + Nvidia       | 5        | 1.12%   |
| 1 x VIA            | 3        | 0.67%   |
| 2 x Nvidia         | 2        | 0.45%   |
| 2 x Intel          | 1        | 0.22%   |
| 1 x SiS            | 1        | 0.22%   |
| 1 x Matrox         | 1        | 0.22%   |
| Intel + 2 x Nvidia | 1        | 0.22%   |
| Intel + 2 x AMD    | 1        | 0.22%   |
| Intel + Nvidia     | 1        | 0.22%   |
| Intel + AMD        | 1        | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 358      | 80.27%  |
| Proprietary | 62       | 13.9%   |
| Unknown     | 26       | 5.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 200      | 44.74%  |
| 0.01-0.5   | 109      | 24.38%  |
| 0.51-1.0   | 51       | 11.41%  |
| 1.01-2.0   | 42       | 9.4%    |
| 3.01-4.0   | 19       | 4.25%   |
| 7.01-8.0   | 13       | 2.91%   |
| 8.01-16.0  | 7        | 1.57%   |
| 5.01-6.0   | 3        | 0.67%   |
| 2.01-3.0   | 3        | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 72       | 17.65%  |
| Dell                 | 48       | 11.76%  |
| Goldstar             | 29       | 7.11%   |
| Acer                 | 27       | 6.62%   |
| Hewlett-Packard      | 24       | 5.88%   |
| Philips              | 23       | 5.64%   |
| AOC                  | 18       | 4.41%   |
| BenQ                 | 17       | 4.17%   |
| Ancor Communications | 14       | 3.43%   |
| Iiyama               | 12       | 2.94%   |
| Lenovo               | 8        | 1.96%   |
| Vizio                | 7        | 1.72%   |
| Unknown              | 7        | 1.72%   |
| Sony                 | 5        | 1.23%   |
| NEC Computers        | 5        | 1.23%   |
| LG Electronics       | 5        | 1.23%   |
| HannStar             | 4        | 0.98%   |
| Eizo                 | 4        | 0.98%   |
| Positivo             | 3        | 0.74%   |
| MSI                  | 3        | 0.74%   |
| Fujitsu Siemens      | 3        | 0.74%   |
| Belinea              | 3        | 0.74%   |
| ___                  | 2        | 0.49%   |
| ViewSonic            | 2        | 0.49%   |
| Unknown (ADA)        | 2        | 0.49%   |
| Toshiba              | 2        | 0.49%   |
| Sceptre Tech         | 2        | 0.49%   |
| Plain Tree Systems   | 2        | 0.49%   |
| LG Display           | 2        | 0.49%   |
| IOD                  | 2        | 0.49%   |
| FL_                  | 2        | 0.49%   |
| Elo Touch            | 2        | 0.49%   |
| Daewoo               | 2        | 0.49%   |
| Compaq Computer      | 2        | 0.49%   |
| Apple                | 2        | 0.49%   |
| Xiaomi               | 1        | 0.25%   |
| Westinghouse         | 1        | 0.25%   |
| Videoseven           | 1        | 0.25%   |
| VHT                  | 1        | 0.25%   |
| Vestel               | 1        | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 3        | 0.72%   |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 3        | 0.72%   |
| ___ LCDTV16 ___0101 1920x1080                                         | 2        | 0.48%   |
| Vizio VOJ320F1A VIZ0050 1920x1080 700x390mm 31.5-inch                 | 2        | 0.48%   |
| Vizio E280i-A1 VIZ1002 1360x768 607x345mm 27.5-inch                   | 2        | 0.48%   |
| Unknown (ADA) LCD Monitor ADA0004 1280x800 150x100mm 7.1-inch         | 2        | 0.48%   |
| Samsung Electronics SyncMaster SAM027C 1680x1050 433x271mm 20.1-inch  | 2        | 0.48%   |
| Samsung Electronics SyncMaster SAM022F 1280x1024 312x234mm 15.4-inch  | 2        | 0.48%   |
| Samsung Electronics SyncMaster SAM0119 1280x1024 352x264mm 17.3-inch  | 2        | 0.48%   |
| Samsung Electronics SMB2230N SAM0635 1920x1080 477x268mm 21.5-inch    | 2        | 0.48%   |
| Samsung Electronics S24D300 SAM0B40 1920x1080 521x293mm 23.5-inch     | 2        | 0.48%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 443x249mm 20.0-inch      | 2        | 0.48%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 2        | 0.48%   |
| Samsung Electronics C24F390 SAM0D2D 1920x1080 521x293mm 23.5-inch     | 2        | 0.48%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch               | 2        | 0.48%   |
| Lenovo LEN L24q-30 LEN65FB 2560x1440 527x296mm 23.8-inch              | 2        | 0.48%   |
| Iiyama PL2730H IVM663A 1920x1080 598x336mm 27.0-inch                  | 2        | 0.48%   |
| Iiyama PL2283H IVM562E 1920x1080 480x270mm 21.7-inch                  | 2        | 0.48%   |
| Hewlett-Packard LA2205 HWP2847 1680x1050 470x300mm 22.0-inch          | 2        | 0.48%   |
| Hewlett-Packard 2009 HWP2827 1600x900 440x250mm 19.9-inch             | 2        | 0.48%   |
| Goldstar M228WA GSM563C 1680x1050 434x270mm 20.1-inch                 | 2        | 0.48%   |
| FL_ HDMI4K FL_2801 2560x1600 480x270mm 21.7-inch                      | 2        | 0.48%   |
| Elo Touch elotouch.com ELO1925 1280x1024 376x301mm 19.0-inch          | 2        | 0.48%   |
| Dell U2711 DELA057 2560x1440 597x336mm 27.0-inch                      | 2        | 0.48%   |
| Dell ST2410 DELA05D 1920x1080 531x299mm 24.0-inch                     | 2        | 0.48%   |
| Dell P190S DEL405A 1280x1024 376x301mm 19.0-inch                      | 2        | 0.48%   |
| Dell AW2518HF DELA102 1920x1080 544x303mm 24.5-inch                   | 2        | 0.48%   |
| Dell 1707FP DEL4012 1280x1024 338x270mm 17.0-inch                     | 2        | 0.48%   |
| BenQ GW2450H BNQ78C1 1920x1080 531x298mm 24.0-inch                    | 2        | 0.48%   |
| AOC G2460 AOC2460 1920x1080 531x299mm 24.0-inch                       | 2        | 0.48%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 2        | 0.48%   |
| AOC 2236 AOC2236 1920x1080 477x268mm 21.5-inch                        | 2        | 0.48%   |
| AOC 1621w AOC1621 1366x768 344x194mm 15.5-inch                        | 2        | 0.48%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 410x260mm 19.1-inch | 2        | 0.48%   |
| Acer AL1716 ACR06B4 1280x1024 338x271mm 17.1-inch                     | 2        | 0.48%   |
| ___ LCD TV ___9000 1360x768                                           | 1        | 0.24%   |
| Xiaomi Mi TV XMD00E1 1440x900 708x398mm 32.0-inch                     | 1        | 0.24%   |
| Westinghouse LCM-22w2 WDE2202 1680x1050 473x296mm 22.0-inch           | 1        | 0.24%   |
| Vizio VO42LFHDTV10A VIZ0043 1920x1080 930x520mm 41.9-inch             | 1        | 0.24%   |
| Vizio E421VO VIZ0090 1920x1080 930x530mm 42.1-inch                    | 1        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 147      | 35.77%  |
| 1280x1024 (SXGA)   | 64       | 15.57%  |
| 1680x1050 (WSXGA+) | 35       | 8.52%   |
| 1366x768 (WXGA)    | 32       | 7.79%   |
| 1440x900 (WXGA+)   | 21       | 5.11%   |
| 2560x1440 (QHD)    | 18       | 4.38%   |
| 1600x900 (HD+)     | 18       | 4.38%   |
| 3840x2160 (4K)     | 14       | 3.41%   |
| 1024x768 (XGA)     | 14       | 3.41%   |
| 1360x768           | 8        | 1.95%   |
| 1920x1200 (WUXGA)  | 7        | 1.7%    |
| Unknown            | 4        | 0.97%   |
| 3440x1440          | 3        | 0.73%   |
| 2288x1287          | 3        | 0.73%   |
| 1280x800 (WXGA)    | 3        | 0.73%   |
| 3600x1200          | 2        | 0.49%   |
| 2560x1600          | 2        | 0.49%   |
| 2560x1080          | 2        | 0.49%   |
| 2048x1536          | 2        | 0.49%   |
| 1600x1200          | 2        | 0.49%   |
| 1280x768           | 2        | 0.49%   |
| 1280x720 (HD)      | 2        | 0.49%   |
| 800x600            | 1        | 0.24%   |
| 5760x2160          | 1        | 0.24%   |
| 3200x1080          | 1        | 0.24%   |
| 2160x1200          | 1        | 0.24%   |
| 1920x540           | 1        | 0.24%   |
| 1152x864           | 1        | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 46       | 11.41%  |
| 19      | 41       | 10.17%  |
| 23      | 37       | 9.18%   |
| 17      | 36       | 8.93%   |
| Unknown | 33       | 8.19%   |
| 21      | 32       | 7.94%   |
| 18      | 28       | 6.95%   |
| 27      | 27       | 6.7%    |
| 20      | 26       | 6.45%   |
| 22      | 22       | 5.46%   |
| 15      | 21       | 5.21%   |
| 31      | 6        | 1.49%   |
| 72      | 5        | 1.24%   |
| 34      | 4        | 0.99%   |
| 14      | 4        | 0.99%   |
| 84      | 3        | 0.74%   |
| 47      | 3        | 0.74%   |
| 40      | 3        | 0.74%   |
| 65      | 2        | 0.5%    |
| 39      | 2        | 0.5%    |
| 38      | 2        | 0.5%    |
| 32      | 2        | 0.5%    |
| 29      | 2        | 0.5%    |
| 13      | 2        | 0.5%    |
| 7       | 2        | 0.5%    |
| 142     | 1        | 0.25%   |
| 60      | 1        | 0.25%   |
| 52      | 1        | 0.25%   |
| 49      | 1        | 0.25%   |
| 48      | 1        | 0.25%   |
| 43      | 1        | 0.25%   |
| 42      | 1        | 0.25%   |
| 41      | 1        | 0.25%   |
| 26      | 1        | 0.25%   |
| 11      | 1        | 0.25%   |
| 8       | 1        | 0.25%   |
| 5       | 1        | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 116      | 29.07%  |
| 501-600        | 109      | 27.32%  |
| 301-350        | 54       | 13.53%  |
| 351-400        | 35       | 8.77%   |
| Unknown        | 33       | 8.27%   |
| 601-700        | 10       | 2.51%   |
| 1001-1500      | 9        | 2.26%   |
| 1501-2000      | 8        | 2.01%   |
| 801-900        | 7        | 1.75%   |
| 701-800        | 6        | 1.5%    |
| 201-300        | 4        | 1%      |
| 101-200        | 4        | 1%      |
| 901-1000       | 3        | 0.75%   |
| More than 2000 | 1        | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 214      | 54.59%  |
| 5/4     | 60       | 15.31%  |
| 16/10   | 59       | 15.05%  |
| Unknown | 27       | 6.89%   |
| 4/3     | 23       | 5.87%   |
| 21/9    | 4        | 1.02%   |
| 6/5     | 2        | 0.51%   |
| 3/2     | 2        | 0.51%   |
| 1.00    | 1        | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 113      | 28.39%  |
| 151-200        | 84       | 21.11%  |
| 141-150        | 52       | 13.07%  |
| Unknown        | 33       | 8.29%   |
| 301-350        | 29       | 7.29%   |
| 101-110        | 20       | 5.03%   |
| More than 1000 | 15       | 3.77%   |
| 501-1000       | 14       | 3.52%   |
| 351-500        | 12       | 3.02%   |
| 251-300        | 11       | 2.76%   |
| 81-90          | 4        | 1.01%   |
| 1-40           | 4        | 1.01%   |
| 131-140        | 2        | 0.5%    |
| 111-120        | 2        | 0.5%    |
| 51-60          | 1        | 0.25%   |
| 121-130        | 1        | 0.25%   |
| 91-100         | 1        | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 268      | 68.37%  |
| 101-120       | 56       | 14.29%  |
| Unknown       | 33       | 8.42%   |
| 1-50          | 19       | 4.85%   |
| 121-160       | 11       | 2.81%   |
| 161-240       | 4        | 1.02%   |
| More than 240 | 1        | 0.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 387      | 86.58%  |
| 2     | 33       | 7.38%   |
| 0     | 23       | 5.15%   |
| 3     | 3        | 0.67%   |
| 4     | 1        | 0.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 267      | 41.72%  |
| Intel                           | 125      | 19.53%  |
| Qualcomm Atheros                | 43       | 6.72%   |
| Nvidia                          | 38       | 5.94%   |
| Ralink Technology               | 34       | 5.31%   |
| Broadcom                        | 18       | 2.81%   |
| TP-Link                         | 11       | 1.72%   |
| Samsung Electronics             | 9        | 1.41%   |
| Broadcom Limited                | 9        | 1.41%   |
| VIA Technologies                | 8        | 1.25%   |
| Ralink                          | 8        | 1.25%   |
| Marvell Technology Group        | 8        | 1.25%   |
| NetGear                         | 6        | 0.94%   |
| Qualcomm Atheros Communications | 5        | 0.78%   |
| Huawei Technologies             | 4        | 0.63%   |
| D-Link System                   | 4        | 0.63%   |
| Belkin Components               | 4        | 0.63%   |
| MediaTek                        | 3        | 0.47%   |
| D-Link                          | 3        | 0.47%   |
| Xiaomi                          | 2        | 0.31%   |
| ULi Electronics                 | 2        | 0.31%   |
| JMicron Technology              | 2        | 0.31%   |
| ICS Advent                      | 2        | 0.31%   |
| ASUSTek Computer                | 2        | 0.31%   |
| ASIX Electronics                | 2        | 0.31%   |
| 3Com                            | 2        | 0.31%   |
| ZyXEL Communications            | 1        | 0.16%   |
| ZTE WCDMA Technologies MSM      | 1        | 0.16%   |
| U-Blox                          | 1        | 0.16%   |
| Trident Microsystems            | 1        | 0.16%   |
| Texas Instruments               | 1        | 0.16%   |
| T & A Mobile Phones             | 1        | 0.16%   |
| Sitecom Europe                  | 1        | 0.16%   |
| Seeed Technology                | 1        | 0.16%   |
| Motorola PCS                    | 1        | 0.16%   |
| LSI                             | 1        | 0.16%   |
| Logitec                         | 1        | 0.16%   |
| Intersil                        | 1        | 0.16%   |
| IMC Networks                    | 1        | 0.16%   |
| GERTEC Telecomunicacoes         | 1        | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 204      | 29.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22       | 3.22%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 18       | 2.64%   |
| Nvidia MCP61 Ethernet                                             | 17       | 2.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15       | 2.2%    |
| Ralink MT7601U Wireless Adapter                                   | 13       | 1.9%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 9        | 1.32%   |
| Ralink RT5370 Wireless Adapter                                    | 8        | 1.17%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7        | 1.02%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 6        | 0.88%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 6        | 0.88%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6        | 0.88%   |
| Nvidia CK804 Ethernet Controller                                  | 6        | 0.88%   |
| Intel I211 Gigabit Network Connection                             | 6        | 0.88%   |
| Intel Ethernet Controller I225-V                                  | 6        | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 0.88%   |
| Intel 82579V Gigabit Network Connection                           | 6        | 0.88%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 6        | 0.88%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 5        | 0.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 0.73%   |
| Ralink RT5572 Wireless Adapter                                    | 5        | 0.73%   |
| Qualcomm Atheros AR9271 802.11n                                   | 5        | 0.73%   |
| Nvidia MCP73 Ethernet                                             | 5        | 0.73%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 5        | 0.73%   |
| Intel Ethernet Connection I217-V                                  | 5        | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4        | 0.59%   |
| Realtek RTL8187 Wireless Adapter                                  | 4        | 0.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 0.59%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 4        | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4        | 0.59%   |
| Intel Wireless 7260                                               | 4        | 0.59%   |
| Intel Wireless 3165                                               | 4        | 0.59%   |
| Intel NM10/ICH7 Family LAN Controller                             | 4        | 0.59%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 0.59%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 0.59%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 3        | 0.44%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 3        | 0.44%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 3        | 0.44%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 41       | 22.04%  |
| Ralink Technology               | 34       | 18.28%  |
| Intel                           | 30       | 16.13%  |
| Qualcomm Atheros                | 22       | 11.83%  |
| TP-Link                         | 10       | 5.38%   |
| Ralink                          | 8        | 4.3%    |
| Broadcom                        | 8        | 4.3%    |
| Qualcomm Atheros Communications | 5        | 2.69%   |
| NetGear                         | 5        | 2.69%   |
| Belkin Components               | 4        | 2.15%   |
| MediaTek                        | 3        | 1.61%   |
| Broadcom Limited                | 3        | 1.61%   |
| D-Link System                   | 2        | 1.08%   |
| D-Link                          | 2        | 1.08%   |
| ASUSTek Computer                | 2        | 1.08%   |
| ZyXEL Communications            | 1        | 0.54%   |
| Sitecom Europe                  | 1        | 0.54%   |
| Samsung Electronics             | 1        | 0.54%   |
| Marvell Technology Group        | 1        | 0.54%   |
| Logitec                         | 1        | 0.54%   |
| IMC Networks                    | 1        | 0.54%   |
| Edimax Technology               | 1        | 0.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                         | 13       | 6.99%   |
| Ralink RT5370 Wireless Adapter                                          | 8        | 4.3%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 6        | 3.23%   |
| Ralink RT5572 Wireless Adapter                                          | 5        | 2.69%   |
| Qualcomm Atheros AR9271 802.11n                                         | 5        | 2.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 4        | 2.15%   |
| Realtek RTL8187 Wireless Adapter                                        | 4        | 2.15%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 4        | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4        | 2.15%   |
| Intel Wireless 7260                                                     | 4        | 2.15%   |
| Intel Wireless 3165                                                     | 4        | 2.15%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 3        | 1.61%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 3        | 1.61%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 3        | 1.61%   |
| Realtek 802.11ac NIC                                                    | 3        | 1.61%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 3        | 1.61%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter              | 3        | 1.61%   |
| Intel Wireless-AC 9260                                                  | 3        | 1.61%   |
| Intel Wireless 7265                                                     | 3        | 1.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3        | 1.61%   |
| Intel Wi-Fi 6 AX200                                                     | 3        | 1.61%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3        | 1.61%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 2        | 1.08%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 2        | 1.08%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2        | 1.08%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 2        | 1.08%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                 | 2        | 1.08%   |
| Ralink RT2501/RT2573 Wireless Adapter                                   | 2        | 1.08%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 2        | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2        | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2        | 1.08%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 2        | 1.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2        | 1.08%   |
| NetGear A6210                                                           | 2        | 1.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2        | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2        | 1.08%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller     | 2        | 1.08%   |
| Belkin Components F7D1101 v1 Basic Wireless Adapter [Realtek RTL8188SU] | 2        | 1.08%   |
| ZyXEL ZyAIR G-202 802.11bg                                              | 1        | 0.54%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1        | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Realtek Semiconductor      | 248      | 51.56%  |
| Intel                      | 102      | 21.21%  |
| Nvidia                     | 38       | 7.9%    |
| Qualcomm Atheros           | 24       | 4.99%   |
| Broadcom                   | 11       | 2.29%   |
| VIA Technologies           | 8        | 1.66%   |
| Samsung Electronics        | 8        | 1.66%   |
| Marvell Technology Group   | 7        | 1.46%   |
| Broadcom Limited           | 6        | 1.25%   |
| Huawei Technologies        | 4        | 0.83%   |
| Xiaomi                     | 2        | 0.42%   |
| ULi Electronics            | 2        | 0.42%   |
| JMicron Technology         | 2        | 0.42%   |
| ICS Advent                 | 2        | 0.42%   |
| D-Link System              | 2        | 0.42%   |
| ASIX Electronics           | 2        | 0.42%   |
| 3Com                       | 2        | 0.42%   |
| ZTE WCDMA Technologies MSM | 1        | 0.21%   |
| Trident Microsystems       | 1        | 0.21%   |
| TP-Link                    | 1        | 0.21%   |
| T & A Mobile Phones        | 1        | 0.21%   |
| NetGear                    | 1        | 0.21%   |
| Motorola PCS               | 1        | 0.21%   |
| D-Link                     | 1        | 0.21%   |
| Aquantia                   | 1        | 0.21%   |
| Apple                      | 1        | 0.21%   |
| ADMtek                     | 1        | 0.21%   |
| Accton Technology          | 1        | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 204      | 41.55%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22       | 4.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 18       | 3.67%   |
| Nvidia MCP61 Ethernet                                             | 17       | 3.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15       | 3.05%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 9        | 1.83%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7        | 1.43%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 6        | 1.22%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6        | 1.22%   |
| Nvidia CK804 Ethernet Controller                                  | 6        | 1.22%   |
| Intel I211 Gigabit Network Connection                             | 6        | 1.22%   |
| Intel Ethernet Controller I225-V                                  | 6        | 1.22%   |
| Intel Ethernet Connection I217-LM                                 | 6        | 1.22%   |
| Intel 82579V Gigabit Network Connection                           | 6        | 1.22%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 6        | 1.22%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 5        | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5        | 1.02%   |
| Nvidia MCP73 Ethernet                                             | 5        | 1.02%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 5        | 1.02%   |
| Intel Ethernet Connection I217-V                                  | 5        | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4        | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4        | 0.81%   |
| Intel NM10/ICH7 Family LAN Controller                             | 4        | 0.81%   |
| Intel Ethernet Connection (2) I219-V                              | 4        | 0.81%   |
| Intel 82574L Gigabit Network Connection                           | 4        | 0.81%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 3        | 0.61%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 3        | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3        | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3        | 0.61%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3        | 0.61%   |
| Huawei ALP-AL00                                                   | 3        | 0.61%   |
| Broadcom Limited NetXtreme BCM5782 Gigabit Ethernet               | 3        | 0.61%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 2        | 0.41%   |
| ULi ULi 1689,1573 integrated ethernet.                            | 2        | 0.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.41%   |
| Nvidia MCP77 Ethernet                                             | 2        | 0.41%   |
| Nvidia MCP55 Ethernet                                             | 2        | 0.41%   |
| Nvidia MCP51 Ethernet Controller                                  | 2        | 0.41%   |
| Nvidia CK8S Ethernet Controller                                   | 2        | 0.41%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 435      | 70.5%   |
| WiFi     | 176      | 28.53%  |
| Modem    | 5        | 0.81%   |
| Unknown  | 1        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 344      | 75.27%  |
| WiFi     | 113      | 24.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 322      | 72.85%  |
| 2     | 102      | 23.08%  |
| 3     | 11       | 2.49%   |
| 0     | 5        | 1.13%   |
| 6     | 1        | 0.23%   |
| 4     | 1        | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 353      | 79.68%  |
| Yes  | 90       | 20.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 26       | 32.1%   |
| Cambridge Silicon Radio         | 22       | 27.16%  |
| Broadcom                        | 6        | 7.41%   |
| Realtek Semiconductor           | 4        | 4.94%   |
| Qualcomm Atheros Communications | 4        | 4.94%   |
| ASUSTek Computer                | 3        | 3.7%    |
| TP-Link                         | 2        | 2.47%   |
| MediaTek                        | 2        | 2.47%   |
| Logitech                        | 2        | 2.47%   |
| Foxconn / Hon Hai               | 2        | 2.47%   |
| Ralink                          | 1        | 1.23%   |
| Lite-On Technology              | 1        | 1.23%   |
| Integrated System Solution      | 1        | 1.23%   |
| HTC (High Tech Computer)        | 1        | 1.23%   |
| Hewlett-Packard                 | 1        | 1.23%   |
| Fujitsu                         | 1        | 1.23%   |
| Dynex                           | 1        | 1.23%   |
| Apple                           | 1        | 1.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 22       | 27.16%  |
| Intel Bluetooth wireless interface                                   | 10       | 12.35%  |
| Realtek Bluetooth Radio                                              | 3        | 3.7%    |
| Qualcomm Atheros AR3011 Bluetooth                                    | 3        | 3.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3        | 3.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 3        | 3.7%    |
| Intel AX210 Bluetooth                                                | 3        | 3.7%    |
| Intel AX200 Bluetooth                                                | 3        | 3.7%    |
| TP-Link UB500 Adapter                                                | 2        | 2.47%   |
| MediaTek Wireless_Device                                             | 2        | 2.47%   |
| Logitech BT Mini-Receiver (HCI mode)                                 | 2        | 2.47%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 2        | 2.47%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2        | 2.47%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 1.23%   |
| Ralink RT3290 Bluetooth                                              | 1        | 1.23%   |
| Qualcomm Atheros  Bluetooth Device                                   | 1        | 1.23%   |
| Lite-On Bluetooth Device                                             | 1        | 1.23%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1        | 1.23%   |
| Intel AX201 Bluetooth                                                | 1        | 1.23%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 1        | 1.23%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 1.23%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 1        | 1.23%   |
| Fujitsu Bluetooth Device                                             | 1        | 1.23%   |
| Foxconn / Hon Hai Wireless_Device                                    | 1        | 1.23%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 1        | 1.23%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 1.23%   |
| Broadcom HP Portable Bumble Bee                                      | 1        | 1.23%   |
| Broadcom Bluetooth Device                                            | 1        | 1.23%   |
| Broadcom BCM20702A0                                                  | 1        | 1.23%   |
| Broadcom BCM2045 Bluetooth                                           | 1        | 1.23%   |
| ASUS Bluetooth Radio                                                 | 1        | 1.23%   |
| ASUS BCM20702A0                                                      | 1        | 1.23%   |
| ASUS ASUS USB-BT500                                                  | 1        | 1.23%   |
| Apple Bluetooth HCI                                                  | 1        | 1.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 250      | 40.39%  |
| AMD                                          | 155      | 25.04%  |
| Nvidia                                       | 135      | 21.81%  |
| C-Media Electronics                          | 16       | 2.58%   |
| VIA Technologies                             | 11       | 1.78%   |
| Creative Labs                                | 10       | 1.62%   |
| Texas Instruments                            | 4        | 0.65%   |
| ASUSTek Computer                             | 4        | 0.65%   |
| XMOS                                         | 3        | 0.48%   |
| Logitech                                     | 3        | 0.48%   |
| Creative Technology                          | 3        | 0.48%   |
| ULi Electronics                              | 2        | 0.32%   |
| Razer USA                                    | 2        | 0.32%   |
| GN Netcom                                    | 2        | 0.32%   |
| Generalplus Technology                       | 2        | 0.32%   |
| Focusrite-Novation                           | 2        | 0.32%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.16%   |
| Sony                                         | 1        | 0.16%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.16%   |
| Setek Elektronik                             | 1        | 0.16%   |
| Plantronics                                  | 1        | 0.16%   |
| Nordic Semiconductor ASA                     | 1        | 0.16%   |
| Micro Star International                     | 1        | 0.16%   |
| KORG                                         | 1        | 0.16%   |
| JMTek                                        | 1        | 0.16%   |
| Guillemot                                    | 1        | 0.16%   |
| ESI                                          | 1        | 0.16%   |
| Ensoniq                                      | 1        | 0.16%   |
| Elgato Systems                               | 1        | 0.16%   |
| Cirrus Logic                                 | 1        | 0.16%   |
| Asahi Kasei Microsystems                     | 1        | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 49       | 6.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 35       | 4.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 32       | 4.49%   |
| AMD FCH Azalia Controller                                                         | 25       | 3.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 24       | 3.37%   |
| Nvidia High Definition Audio Controller                                           | 21       | 2.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 20       | 2.81%   |
| Nvidia MCP61 High Definition Audio                                                | 19       | 2.67%   |
| AMD Starship/Matisse HD Audio Controller                                          | 16       | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 15       | 2.11%   |
| AMD Family 17h/19h HD Audio Controller                                            | 15       | 2.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 14       | 1.97%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 13       | 1.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 12       | 1.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 12       | 1.69%   |
| AMD Kabini HDMI/DP Audio                                                          | 12       | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 11       | 1.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 10       | 1.4%    |
| AMD Renoir Radeon High Definition Audio Controller                                | 10       | 1.4%    |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 10       | 1.4%    |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 9        | 1.26%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 9        | 1.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 9        | 1.26%   |
| Nvidia GF108 High Definition Audio Controller                                     | 8        | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 8        | 1.12%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 7        | 0.98%   |
| Nvidia GK107 HDMI Audio Controller                                                | 7        | 0.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 7        | 0.98%   |
| AMD Trinity HDMI Audio Controller                                                 | 7        | 0.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 6        | 0.84%   |
| Intel Cannon Lake PCH cAVS                                                        | 6        | 0.84%   |
| AMD Wrestler HDMI Audio                                                           | 6        | 0.84%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 6        | 0.84%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 6        | 0.84%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 6        | 0.84%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                         | 5        | 0.7%    |
| Nvidia MCP73 High Definition Audio                                                | 5        | 0.7%    |
| Nvidia CK804 AC'97 Audio Controller                                               | 5        | 0.7%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 5        | 0.7%    |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                              | 5        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Unknown                      | 74       | 24.1%   |
| Samsung Electronics          | 42       | 13.68%  |
| Kingston                     | 38       | 12.38%  |
| SK hynix                     | 31       | 10.1%   |
| G.Skill                      | 20       | 6.51%   |
| Corsair                      | 19       | 6.19%   |
| Micron Technology            | 15       | 4.89%   |
| Crucial                      | 14       | 4.56%   |
| Nanya Technology             | 8        | 2.61%   |
| Unknown (ABCD)               | 5        | 1.63%   |
| Elpida                       | 5        | 1.63%   |
| A-DATA Technology            | 5        | 1.63%   |
| Unknown                      | 5        | 1.63%   |
| Patriot                      | 4        | 1.3%    |
| Transcend                    | 2        | 0.65%   |
| Timetec                      | 2        | 0.65%   |
| Unknown (AB)                 | 1        | 0.33%   |
| Unknown (0x4000000000000000) | 1        | 0.33%   |
| Unknown (07FB)               | 1        | 0.33%   |
| Unifosa                      | 1        | 0.33%   |
| Teikon                       | 1        | 0.33%   |
| Team                         | 1        | 0.33%   |
| Smart                        | 1        | 0.33%   |
| Silicon Power                | 1        | 0.33%   |
| Ramaxel Technology           | 1        | 0.33%   |
| Qimonda                      | 1        | 0.33%   |
| Princeton                    | 1        | 0.33%   |
| PNY                          | 1        | 0.33%   |
| Infineon                     | 1        | 0.33%   |
| GOODRAM                      | 1        | 0.33%   |
| Golden Empire                | 1        | 0.33%   |
| e2e4                         | 1        | 0.33%   |
| ASint Technology             | 1        | 0.33%   |
| 48spaces                     | 1        | 0.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 5        | 1.49%   |
| Unknown                                                        | 5        | 1.49%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                       | 4        | 1.19%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s                  | 4        | 1.19%   |
| Unknown RAM Module 2GB DIMM SDRAM                              | 3        | 0.89%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 3        | 0.89%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                         | 3        | 0.89%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 3        | 0.89%   |
| Nanya RAM NT2GT64U8HD0BY-AD 2048MB DIMM DDR2 2048MT/s          | 3        | 0.89%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s            | 3        | 0.89%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 2        | 0.6%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 2        | 0.6%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 2        | 0.6%    |
| Unknown RAM Module 1GB DIMM SDRAM                              | 2        | 0.6%    |
| Unknown RAM Module 1024MB DIMM DDR 400MT/s                     | 2        | 0.6%    |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                     | 2        | 0.6%    |
| SK hynix RAM Module 2048MB DIMM DDR3 1066MT/s                  | 2        | 0.6%    |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 49926MT/s          | 2        | 0.6%    |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s           | 2        | 0.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 2        | 0.6%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2        | 0.6%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2        | 0.6%    |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s            | 2        | 0.6%    |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR3 2133MT/s         | 2        | 0.6%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 2        | 0.6%    |
| Samsung RAM M3 78T6553EZS-CE6 512MB DIMM DDR2 667MT/s          | 2        | 0.6%    |
| Micron RAM 16JTF51264AZ-1G4M1 4GB DIMM DDR3 1333MT/s           | 2        | 0.6%    |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s                   | 2        | 0.6%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 2        | 0.6%    |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s          | 2        | 0.6%    |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s            | 2        | 0.6%    |
| G.Skill RAM F4-2666C19-16GIS 16GB DIMM DDR4 2667MT/s           | 2        | 0.6%    |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s            | 2        | 0.6%    |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s          | 2        | 0.6%    |
| Unknown RAM Module 8GB DIMM 1600MT/s                           | 1        | 0.3%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 0.3%    |
| Unknown RAM Module 8192MB DIMM DDR3 1866MT/s                   | 1        | 0.3%    |
| Unknown RAM Module 8192MB DIMM 667MT/s                         | 1        | 0.3%    |
| Unknown RAM Module 8192MB DIMM 1600MT/s                        | 1        | 0.3%    |
| Unknown RAM Module 512MB DIMM SDRAM 266MT/s                    | 1        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 96       | 35.29%  |
| DDR4    | 63       | 23.16%  |
| DDR2    | 41       | 15.07%  |
| SDRAM   | 27       | 9.93%   |
| Unknown | 26       | 9.56%   |
| DDR     | 11       | 4.04%   |
| LPDDR4  | 5        | 1.84%   |
| DRAM    | 2        | 0.74%   |
| DDR5    | 1        | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 234      | 88.64%  |
| SODIMM | 30       | 11.36%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 86       | 29.05%  |
| 4096  | 68       | 22.97%  |
| 8192  | 64       | 21.62%  |
| 1024  | 31       | 10.47%  |
| 16384 | 27       | 9.12%   |
| 512   | 9        | 3.04%   |
| 32768 | 5        | 1.69%   |
| 256   | 4        | 1.35%   |
| 65536 | 1        | 0.34%   |
| 128   | 1        | 0.34%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 58       | 19.86%  |
| 1333    | 32       | 10.96%  |
| 800     | 26       | 8.9%    |
| Unknown | 17       | 5.82%   |
| 3200    | 15       | 5.14%   |
| 667     | 15       | 5.14%   |
| 2400    | 12       | 4.11%   |
| 2133    | 12       | 4.11%   |
| 2667    | 11       | 3.77%   |
| 1066    | 10       | 3.42%   |
| 400     | 9        | 3.08%   |
| 1866    | 8        | 2.74%   |
| 533     | 7        | 2.4%    |
| 3600    | 6        | 2.05%   |
| 1867    | 6        | 2.05%   |
| 2048    | 5        | 1.71%   |
| 333     | 5        | 1.71%   |
| 3400    | 4        | 1.37%   |
| 1067    | 4        | 1.37%   |
| 49926   | 3        | 1.03%   |
| 3866    | 3        | 1.03%   |
| 266     | 3        | 1.03%   |
| 3933    | 2        | 0.68%   |
| 3066    | 2        | 0.68%   |
| 3000    | 2        | 0.68%   |
| 2800    | 2        | 0.68%   |
| 2733    | 2        | 0.68%   |
| 2666    | 2        | 0.68%   |
| 41632   | 1        | 0.34%   |
| 4800    | 1        | 0.34%   |
| 3666    | 1        | 0.34%   |
| 3534    | 1        | 0.34%   |
| 3151    | 1        | 0.34%   |
| 2933    | 1        | 0.34%   |
| 1800    | 1        | 0.34%   |
| 1639    | 1        | 0.34%   |
| 1334    | 1        | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 5        | 31.25%  |
| Samsung Electronics   | 4        | 25%     |
| Canon                 | 2        | 12.5%   |
| Brother Industries    | 2        | 12.5%   |
| Seiko Epson           | 1        | 6.25%   |
| Lexmark International | 1        | 6.25%   |
| Dymo-CoStar           | 1        | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Seiko Epson TM-T20X                     | 1        | 6.25%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1        | 6.25%   |
| Samsung SCX-4200 series                 | 1        | 6.25%   |
| Samsung SCX-3400 Series                 | 1        | 6.25%   |
| Samsung M2020 Series                    | 1        | 6.25%   |
| Lexmark International Z33 Printer       | 1        | 6.25%   |
| HP PSC 1500 series                      | 1        | 6.25%   |
| HP OfficeJet 4650 series                | 1        | 6.25%   |
| HP LaserJet P2015 series                | 1        | 6.25%   |
| HP DeskJet D2460                        | 1        | 6.25%   |
| HP DeskJet 3630 series                  | 1        | 6.25%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo  | 1        | 6.25%   |
| Canon PIXMA MP250                       | 1        | 6.25%   |
| Canon LiDE 300                          | 1        | 6.25%   |
| Brother Printer                         | 1        | 6.25%   |
| Brother DCP-7055W                       | 1        | 6.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 3        | 60%     |
| Canon           | 2        | 40%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| HP scanjet 8270         | 1        | 20%     |
| HP ScanJet 2400c        | 1        | 20%     |
| HP HP4470C              | 1        | 20%     |
| Canon CanoScan LiDE 220 | 1        | 20%     |
| Canon CanoScan LiDE 200 | 1        | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 13       | 27.08%  |
| Microsoft                     | 4        | 8.33%   |
| Generalplus Technology        | 4        | 8.33%   |
| Samsung Electronics           | 2        | 4.17%   |
| KYE Systems (Mouse Systems)   | 2        | 4.17%   |
| Genesys Logic                 | 2        | 4.17%   |
| GEMBIRD                       | 2        | 4.17%   |
| Chicony Electronics           | 2        | 4.17%   |
| ARC International             | 2        | 4.17%   |
| Apple                         | 2        | 4.17%   |
| Z-Star Microelectronics       | 1        | 2.08%   |
| WaveRider Communications      | 1        | 2.08%   |
| SunplusIT                     | 1        | 2.08%   |
| Sunplus Innovation Technology | 1        | 2.08%   |
| Pixart Imaging                | 1        | 2.08%   |
| Microdia                      | 1        | 2.08%   |
| LG Electronics                | 1        | 2.08%   |
| IMC Networks                  | 1        | 2.08%   |
| Huawei Technologies           | 1        | 2.08%   |
| Guillemot                     | 1        | 2.08%   |
| GEO Semi                      | 1        | 2.08%   |
| Bison Electronics             | 1        | 2.08%   |
| AVerMedia Technologies        | 1        | 2.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 4        | 8.33%   |
| Microsoft LifeCam HD-3000                             | 3        | 6.25%   |
| Generalplus GENERAL WEBCAM                            | 3        | 6.25%   |
| Samsung Galaxy series, misc. (MTP mode)               | 2        | 4.17%   |
| Logitech HD Webcam C615                               | 2        | 4.17%   |
| Logitech HD Webcam C525                               | 2        | 4.17%   |
| Genesys Logic Camera                                  | 2        | 4.17%   |
| ARC International Camera                              | 2        | 4.17%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                       | 2        | 4.17%   |
| Z-Star Sirius USB2.0 Camera                           | 1        | 2.08%   |
| WaveRider USB Live camera                             | 1        | 2.08%   |
| SunplusIT USB 2.0 Camera                              | 1        | 2.08%   |
| Sunplus Full HD webcam                                | 1        | 2.08%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                  | 1        | 2.08%   |
| Microsoft LifeCam VX-800                              | 1        | 2.08%   |
| Microdia Webcam Vitade AF                             | 1        | 2.08%   |
| Logitech Webcam C300                                  | 1        | 2.08%   |
| Logitech Webcam C170                                  | 1        | 2.08%   |
| Logitech Webcam B500                                  | 1        | 2.08%   |
| Logitech QuickCam Zoom                                | 1        | 2.08%   |
| Logitech HD Pro Webcam C920                           | 1        | 2.08%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1        | 2.08%   |
| KYE Systems (Mouse Systems) Genius eFace 1325R        | 1        | 2.08%   |
| KYE Systems (Mouse Systems) FaceCam 1000X             | 1        | 2.08%   |
| IMC Networks USB2.0 UVC VGA WebCam                    | 1        | 2.08%   |
| Huawei UVC Camera                                     | 1        | 2.08%   |
| Guillemot Hercules HD Sunset                          | 1        | 2.08%   |
| GEO Semi Condor                                       | 1        | 2.08%   |
| Generalplus 808 Camera #9 (web-cam mode)              | 1        | 2.08%   |
| GEMBIRD USB2.0 PC CAMERA                              | 1        | 2.08%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]     | 1        | 2.08%   |
| Chicony CNF7042                                       | 1        | 2.08%   |
| Chicony ASUS USB2.0 Webcam                            | 1        | 2.08%   |
| Bison Integrated Camera                               | 1        | 2.08%   |
| AVerMedia Live Streamer CAM 313                       | 1        | 2.08%   |

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
| Cherry      | 2        | 50%     |
| OmniKey     | 1        | 25%     |
| Alcor Micro | 1        | 25%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Cherry SmartCard Reader Keyboard KC 1000 SC | 2        | 50%     |
| OmniKey CardMan 3021 / 3121                 | 1        | 25%     |
| Alcor Micro AU9540 Smartcard Reader         | 1        | 25%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 368      | 82.33%  |
| 1     | 65       | 14.54%  |
| 2     | 12       | 2.68%   |
| 4     | 1        | 0.22%   |
| 3     | 1        | 0.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 37       | 40.66%  |
| Net/wireless             | 15       | 16.48%  |
| Communication controller | 11       | 12.09%  |
| Sound                    | 6        | 6.59%   |
| Multimedia controller    | 5        | 5.49%   |
| Unassigned class         | 4        | 4.4%    |
| Net/ethernet             | 4        | 4.4%    |
| Dvb card                 | 2        | 2.2%    |
| Chipcard                 | 2        | 2.2%    |
| Bluetooth                | 2        | 2.2%    |
| Storage/raid             | 1        | 1.1%    |
| Modem                    | 1        | 1.1%    |
| Camera                   | 1        | 1.1%    |

