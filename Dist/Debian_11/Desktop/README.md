Debian 11 - Tested Hardware & Statistics (Desktops)
---------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

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

Total: 3829

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 1495                        | [50dfd57e41](https://linux-hardware.org/?probe=50dfd57e41) | Jan 03, 2026 |
| Gigabyte      | GB-BSi5-1135G7              | [6ae53887a0](https://linux-hardware.org/?probe=6ae53887a0) | Dec 31, 2025 |
| ASUSTek       | PRIME B365M-A               | [c827dc109a](https://linux-hardware.org/?probe=c827dc109a) | Dec 31, 2025 |
| MSI           | H110M PRO-VH PLUS           | [30fe3e1f95](https://linux-hardware.org/?probe=30fe3e1f95) | Dec 14, 2025 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8a3c1cfa03](https://linux-hardware.org/?probe=8a3c1cfa03) | Dec 09, 2025 |
| MSI           | A88XM-E35 V2                | [f3017661e5](https://linux-hardware.org/?probe=f3017661e5) | Dec 05, 2025 |
| Intel         | Alpha lite                  | [93be5c1af5](https://linux-hardware.org/?probe=93be5c1af5) | Nov 09, 2025 |
| NTT SYSTEM    | Komputer All-in-One NTT ... | [acfa9d530d](https://linux-hardware.org/?probe=acfa9d530d) | Oct 20, 2025 |
| Gigabyte      | GA-790XTA-UD4               | [15db125ea6](https://linux-hardware.org/?probe=15db125ea6) | Oct 15, 2025 |
| Dell          | 0M5DCD A00                  | [76a7edd20f](https://linux-hardware.org/?probe=76a7edd20f) | Oct 09, 2025 |
| HP            | 1790                        | [c6a242ab21](https://linux-hardware.org/?probe=c6a242ab21) | Oct 09, 2025 |
| ASRock        | B450 Pro4                   | [fbf8668490](https://linux-hardware.org/?probe=fbf8668490) | Oct 06, 2025 |
| HP            | 876C SMVB                   | [faa6bb4bdb](https://linux-hardware.org/?probe=faa6bb4bdb) | Sep 10, 2025 |
| HP            | 1790                        | [f4a4ccf236](https://linux-hardware.org/?probe=f4a4ccf236) | Sep 10, 2025 |
| HP            | 1495                        | [1b730db0b1](https://linux-hardware.org/?probe=1b730db0b1) | Sep 07, 2025 |
| ASUSTek       | Z97-PRO                     | [6bf2414c3b](https://linux-hardware.org/?probe=6bf2414c3b) | Sep 07, 2025 |
| ASUSTek       | Z97-PRO                     | [f83b15944f](https://linux-hardware.org/?probe=f83b15944f) | Sep 07, 2025 |
| HP            | 1495                        | [ddeaaec5bc](https://linux-hardware.org/?probe=ddeaaec5bc) | Sep 04, 2025 |
| ASUSTek       | PRIME B360M-C               | [15b41c928c](https://linux-hardware.org/?probe=15b41c928c) | Aug 31, 2025 |
| ASUSTek       | P8H67-M                     | [6db63132a5](https://linux-hardware.org/?probe=6db63132a5) | Aug 30, 2025 |
| HP            | 8712                        | [47663d6487](https://linux-hardware.org/?probe=47663d6487) | Aug 24, 2025 |
| HP            | 1790                        | [9b0bedd9b7](https://linux-hardware.org/?probe=9b0bedd9b7) | Aug 24, 2025 |
| HP            | 1790                        | [e34fdab0a9](https://linux-hardware.org/?probe=e34fdab0a9) | Aug 24, 2025 |
| Gigabyte      | H410M H V2                  | [1bc206cbd3](https://linux-hardware.org/?probe=1bc206cbd3) | Aug 20, 2025 |
| Acer          | Aspire TC-885 V:1.1         | [33e6bdebef](https://linux-hardware.org/?probe=33e6bdebef) | Jul 16, 2025 |
| Dell          | 0P03DX A04                  | [a1d023a277](https://linux-hardware.org/?probe=a1d023a277) | Jul 14, 2025 |
| Dell          | 0P03DX A04                  | [b4fdad092a](https://linux-hardware.org/?probe=b4fdad092a) | Jul 13, 2025 |
| Unknown       | Unknown                     | [ef7a4cd4c1](https://linux-hardware.org/?probe=ef7a4cd4c1) | Jul 10, 2025 |
| ASRock        | X570 PG Velocita            | [521dfe6c86](https://linux-hardware.org/?probe=521dfe6c86) | Jun 24, 2025 |
| ASUSTek       | P8H61-M LX                  | [b4bc28a035](https://linux-hardware.org/?probe=b4bc28a035) | Jun 11, 2025 |
| Dell          | 0J3C2F A00                  | [9f8a3628b3](https://linux-hardware.org/?probe=9f8a3628b3) | Jun 08, 2025 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | [43c8f9da20](https://linux-hardware.org/?probe=43c8f9da20) | May 29, 2025 |
| Intel         | H61                         | [173afcaade](https://linux-hardware.org/?probe=173afcaade) | May 26, 2025 |
| ASRock        | FM2A68M-DG3+                | [0c4fcddebd](https://linux-hardware.org/?probe=0c4fcddebd) | May 13, 2025 |
| ASRock        | FM2A68M-DG3+                | [6a765d2ecc](https://linux-hardware.org/?probe=6a765d2ecc) | May 13, 2025 |
| HP            | 1495                        | [581ae40ba0](https://linux-hardware.org/?probe=581ae40ba0) | May 08, 2025 |
| Gigabyte      | J1800N-D2PH                 | [3f579c4858](https://linux-hardware.org/?probe=3f579c4858) | Apr 28, 2025 |
| ASRock        | FM2A68M-DG3+                | [f5bd4c233b](https://linux-hardware.org/?probe=f5bd4c233b) | Apr 24, 2025 |
| ASRock        | FM2A68M-DG3+                | [2b4950ef6b](https://linux-hardware.org/?probe=2b4950ef6b) | Apr 24, 2025 |
| HP            | 1495                        | [2387fc7971](https://linux-hardware.org/?probe=2387fc7971) | Apr 23, 2025 |
| Intel         | Granite Well FABA           | [e46838f2b2](https://linux-hardware.org/?probe=e46838f2b2) | Apr 18, 2025 |
| ASRock        | B450M Pro4                  | [45728a8f62](https://linux-hardware.org/?probe=45728a8f62) | Apr 18, 2025 |
| Acer          | Predator PO3-600 V:1.1      | [81856c6957](https://linux-hardware.org/?probe=81856c6957) | Apr 07, 2025 |
| Acer          | Predator PO3-600 V:1.1      | [df6f005f45](https://linux-hardware.org/?probe=df6f005f45) | Apr 06, 2025 |
| ASRock        | B250M-HDV                   | [33d5c70b89](https://linux-hardware.org/?probe=33d5c70b89) | Apr 06, 2025 |
| OEM           | Intel H81                   | [46140488e4](https://linux-hardware.org/?probe=46140488e4) | Mar 28, 2025 |
| MSI           | H310M PRO-VDH PLUS          | [d5cf4899f3](https://linux-hardware.org/?probe=d5cf4899f3) | Mar 24, 2025 |
| ASUSTek       | M5A97 R2.0                  | [decd87067a](https://linux-hardware.org/?probe=decd87067a) | Mar 23, 2025 |
| OEM           | Intel H81                   | [61e414370c](https://linux-hardware.org/?probe=61e414370c) | Mar 22, 2025 |
| MSI           | 760GA-P43                   | [1166034212](https://linux-hardware.org/?probe=1166034212) | Mar 21, 2025 |
| MSI           | 760GA-P43                   | [703785faf9](https://linux-hardware.org/?probe=703785faf9) | Mar 21, 2025 |
| Intel         | DH87MC AAG74242-401         | [2b8d965a19](https://linux-hardware.org/?probe=2b8d965a19) | Mar 19, 2025 |
| Gigabyte      | H410M H V3                  | [e0eb7cae1a](https://linux-hardware.org/?probe=e0eb7cae1a) | Mar 19, 2025 |
| HP            | 1495                        | [abcc376227](https://linux-hardware.org/?probe=abcc376227) | Mar 15, 2025 |
| ELSKY         | M219FN-6C                   | [0819c68770](https://linux-hardware.org/?probe=0819c68770) | Mar 12, 2025 |
| ASRock        | X300M-STX                   | [9058ac67fc](https://linux-hardware.org/?probe=9058ac67fc) | Mar 10, 2025 |
| ASUSTek       | B85-PLUS                    | [12dff811e1](https://linux-hardware.org/?probe=12dff811e1) | Mar 10, 2025 |
| Pegatron      | EVANS                       | [d5171b4701](https://linux-hardware.org/?probe=d5171b4701) | Mar 08, 2025 |
| ASRock        | ConRoe1333-D667             | [ccc4dcc6a4](https://linux-hardware.org/?probe=ccc4dcc6a4) | Mar 07, 2025 |
| ASUSTek       | PRIME A320M-K               | [4c0df4a632](https://linux-hardware.org/?probe=4c0df4a632) | Mar 06, 2025 |
| HP            | 3397                        | [587f49298b](https://linux-hardware.org/?probe=587f49298b) | Mar 05, 2025 |
| IceWhale T... | ZMB216-i ZMB                | [4c45b06c90](https://linux-hardware.org/?probe=4c45b06c90) | Mar 01, 2025 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [582931ae92](https://linux-hardware.org/?probe=582931ae92) | Feb 18, 2025 |
| ASRock        | X570 Steel Legend           | [7cde997af7](https://linux-hardware.org/?probe=7cde997af7) | Feb 16, 2025 |
| MSI           | MAG B560 TORPEDO            | [b15e4a5767](https://linux-hardware.org/?probe=b15e4a5767) | Feb 11, 2025 |
| Gigabyte      | H610M S2H V3 DDR4           | [45e02baaa7](https://linux-hardware.org/?probe=45e02baaa7) | Feb 04, 2025 |
| ASRock        | AB350 Gaming-ITX/ac         | [5c17f992f2](https://linux-hardware.org/?probe=5c17f992f2) | Jan 31, 2025 |
| ASRock        | B450M Pro4-F                | [22b68f9601](https://linux-hardware.org/?probe=22b68f9601) | Jan 27, 2025 |
| Huanan        | X99-F8D PLUS V1.3           | [3c0a5cde0c](https://linux-hardware.org/?probe=3c0a5cde0c) | Jan 24, 2025 |
| HP            | 1790                        | [32de7b3c8e](https://linux-hardware.org/?probe=32de7b3c8e) | Jan 20, 2025 |
| MSI           | PRO B660M-P DDR4            | [0000452d93](https://linux-hardware.org/?probe=0000452d93) | Jan 19, 2025 |
| Gigabyte      | 970A-DS3P FX                | [5b98dd4ff7](https://linux-hardware.org/?probe=5b98dd4ff7) | Jan 16, 2025 |
| MSI           | MAG B560 TORPEDO            | [29934f1cac](https://linux-hardware.org/?probe=29934f1cac) | Jan 15, 2025 |
| Unknown       | Unknown                     | [e1bd5d456b](https://linux-hardware.org/?probe=e1bd5d456b) | Jan 12, 2025 |
| ASUSTek       | B85M-G R2.0                 | [ed27c636e3](https://linux-hardware.org/?probe=ed27c636e3) | Jan 07, 2025 |
| Dell          | 09KPNV A00                  | [d2a1de9dc7](https://linux-hardware.org/?probe=d2a1de9dc7) | Jan 04, 2025 |
| ASRock        | J5040-ITX                   | [cfe9a3c37e](https://linux-hardware.org/?probe=cfe9a3c37e) | Dec 28, 2024 |
| Gigabyte      | H370M D3H-CF                | [293052fc3b](https://linux-hardware.org/?probe=293052fc3b) | Dec 24, 2024 |
| ASRock        | J5040-ITX                   | [30c96f3002](https://linux-hardware.org/?probe=30c96f3002) | Dec 19, 2024 |
| ASUSTek       | PRIME B760-PLUS D4          | [379d336bc2](https://linux-hardware.org/?probe=379d336bc2) | Dec 16, 2024 |
| OEM           | B75 Ver:1.41                | [26fc19a77d](https://linux-hardware.org/?probe=26fc19a77d) | Dec 15, 2024 |
| ASUSTek       | PRIME Z590-P                | [2e9144632c](https://linux-hardware.org/?probe=2e9144632c) | Dec 02, 2024 |
| HP            | 339A                        | [c64449a47e](https://linux-hardware.org/?probe=c64449a47e) | Dec 02, 2024 |
| ASRock        | B450M Pro4                  | [c865d51386](https://linux-hardware.org/?probe=c865d51386) | Nov 30, 2024 |
| MSI           | 880GM-E41                   | [d2d4d7473b](https://linux-hardware.org/?probe=d2d4d7473b) | Nov 26, 2024 |
| ASUSTek       | Rampage III GENE            | [89662fc2f1](https://linux-hardware.org/?probe=89662fc2f1) | Nov 23, 2024 |
| ASUSTek       | PRIME Z590-P                | [5b66a14834](https://linux-hardware.org/?probe=5b66a14834) | Nov 20, 2024 |
| Unknown       | Unknown                     | [69c39a72ba](https://linux-hardware.org/?probe=69c39a72ba) | Nov 18, 2024 |
| Acer          | FI946GZG                    | [a7f49035aa](https://linux-hardware.org/?probe=a7f49035aa) | Nov 16, 2024 |
| Acer          | FI946GZG                    | [9d9080e57a](https://linux-hardware.org/?probe=9d9080e57a) | Nov 16, 2024 |
| Dell          | 0KWVT8 A00                  | [cbf908cc03](https://linux-hardware.org/?probe=cbf908cc03) | Nov 13, 2024 |
| Gigabyte      | GA-MA78GM-DS2H              | [5b63d6de06](https://linux-hardware.org/?probe=5b63d6de06) | Nov 12, 2024 |
| HP            | 1495                        | [5778238fb5](https://linux-hardware.org/?probe=5778238fb5) | Nov 09, 2024 |
| ASUSTek       | Z8PE-D12-EMBEDDED           | [a71b3adfe4](https://linux-hardware.org/?probe=a71b3adfe4) | Nov 09, 2024 |
| ASUSTek       | Z8PE-D12-EMBEDDED           | [03ca590abe](https://linux-hardware.org/?probe=03ca590abe) | Nov 09, 2024 |
| Dell          | 01XK1W A00                  | [a66d7f6087](https://linux-hardware.org/?probe=a66d7f6087) | Nov 09, 2024 |
| Intel         | DH77KC AAG39641-400         | [7e99679aa4](https://linux-hardware.org/?probe=7e99679aa4) | Nov 07, 2024 |
| Dell          | 0V8WGR A00                  | [8b995d3611](https://linux-hardware.org/?probe=8b995d3611) | Nov 05, 2024 |
| HP            | 1495                        | [00133664ce](https://linux-hardware.org/?probe=00133664ce) | Nov 02, 2024 |
| ASRock        | B450 Pro4 R2.0              | [9db603450a](https://linux-hardware.org/?probe=9db603450a) | Nov 01, 2024 |
| Gigabyte      | H81M-S2H                    | [b93eb7acfd](https://linux-hardware.org/?probe=b93eb7acfd) | Oct 28, 2024 |
| IBASE Tech... | MB980VF B1                  | [0950d198d6](https://linux-hardware.org/?probe=0950d198d6) | Oct 27, 2024 |
| IBASE Tech... | MB980VF B1                  | [b7bff2d716](https://linux-hardware.org/?probe=b7bff2d716) | Oct 27, 2024 |
| Dell          | 01XK1W A00                  | [5226011358](https://linux-hardware.org/?probe=5226011358) | Oct 27, 2024 |
| Acer          | FI946GZG                    | [5938a70edc](https://linux-hardware.org/?probe=5938a70edc) | Oct 26, 2024 |
| Acer          | FI946GZG                    | [57835df373](https://linux-hardware.org/?probe=57835df373) | Oct 26, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [0642feaea1](https://linux-hardware.org/?probe=0642feaea1) | Oct 22, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [b13668c203](https://linux-hardware.org/?probe=b13668c203) | Oct 22, 2024 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [daf26b85a4](https://linux-hardware.org/?probe=daf26b85a4) | Oct 19, 2024 |
| MSI           | MS-7071                     | [6cf8497c89](https://linux-hardware.org/?probe=6cf8497c89) | Oct 16, 2024 |
| Dell          | 0GXM1W A02                  | [e8c22589e3](https://linux-hardware.org/?probe=e8c22589e3) | Oct 16, 2024 |
| Dell          | 0GXM1W A02                  | [e2cdb3ceef](https://linux-hardware.org/?probe=e2cdb3ceef) | Oct 16, 2024 |
| ASRock        | H610M-HVS                   | [91361cad1e](https://linux-hardware.org/?probe=91361cad1e) | Oct 10, 2024 |
| HP            | ProLiant MicroServer Gen... | [2927ff6f0d](https://linux-hardware.org/?probe=2927ff6f0d) | Oct 09, 2024 |
| Acer          | FI946GZG                    | [92bd6f1fc1](https://linux-hardware.org/?probe=92bd6f1fc1) | Oct 09, 2024 |
| Acer          | FI946GZG                    | [535a355530](https://linux-hardware.org/?probe=535a355530) | Oct 09, 2024 |
| Sapphire      | PI-AM3RS760G2               | [d0eaae2f60](https://linux-hardware.org/?probe=d0eaae2f60) | Oct 09, 2024 |
| ASRock        | B450M Steel Legend          | [1abb05bf25](https://linux-hardware.org/?probe=1abb05bf25) | Oct 03, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | [eca6363c57](https://linux-hardware.org/?probe=eca6363c57) | Oct 02, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | [3b48795f8e](https://linux-hardware.org/?probe=3b48795f8e) | Sep 30, 2024 |
| HP            | 3397                        | [63009f600f](https://linux-hardware.org/?probe=63009f600f) | Sep 30, 2024 |
| Dell          | 0T065F A01                  | [bcbba2bc39](https://linux-hardware.org/?probe=bcbba2bc39) | Sep 21, 2024 |
| Acer          | FI946GZG                    | [38457fe3eb](https://linux-hardware.org/?probe=38457fe3eb) | Sep 20, 2024 |
| Acer          | FI946GZG                    | [7f888553ed](https://linux-hardware.org/?probe=7f888553ed) | Sep 20, 2024 |
| Gigabyte      | B75M-D3V                    | [b96fef78f4](https://linux-hardware.org/?probe=b96fef78f4) | Sep 20, 2024 |
| ASRock        | X570 Phantom Gaming X       | [075f6eaa32](https://linux-hardware.org/?probe=075f6eaa32) | Sep 19, 2024 |
| Lenovo        | SHARKBAY SDK0J40697 WIN     | [6d2a1ac8e1](https://linux-hardware.org/?probe=6d2a1ac8e1) | Sep 18, 2024 |
| Dell          | 01XK1W A00                  | [b1768b27cf](https://linux-hardware.org/?probe=b1768b27cf) | Sep 14, 2024 |
| Dell          | 0NNNCT A01                  | [c3aeffdb84](https://linux-hardware.org/?probe=c3aeffdb84) | Sep 13, 2024 |
| Intel         | CRESCENTBAY                 | [14865f8a73](https://linux-hardware.org/?probe=14865f8a73) | Sep 10, 2024 |
| ASUSTek       | H110M-K                     | [ff593c19ff](https://linux-hardware.org/?probe=ff593c19ff) | Sep 10, 2024 |
| iEi           | SAX9 V1.00                  | [d25454a2fb](https://linux-hardware.org/?probe=d25454a2fb) | Sep 10, 2024 |
| Dell          | 0NNNCT A01                  | [c5d73da3a3](https://linux-hardware.org/?probe=c5d73da3a3) | Sep 09, 2024 |
| ASUSTek       | PRIME H310M-K               | [4a801900e1](https://linux-hardware.org/?probe=4a801900e1) | Sep 09, 2024 |
| ASUSTek       | PRIME H310M-K               | [1c6ee65d7a](https://linux-hardware.org/?probe=1c6ee65d7a) | Sep 09, 2024 |
| ASUSTek       | P8Z68-V LX                  | [9d86f13601](https://linux-hardware.org/?probe=9d86f13601) | Sep 05, 2024 |
| HP            | 18E7                        | [dbea31ed81](https://linux-hardware.org/?probe=dbea31ed81) | Sep 02, 2024 |
| ASRock        | 970M Pro3                   | [5310dbbf32](https://linux-hardware.org/?probe=5310dbbf32) | Sep 01, 2024 |
| MSI           | B85M-G43                    | [374b7d32b3](https://linux-hardware.org/?probe=374b7d32b3) | Sep 01, 2024 |
| Dell          | 01XK1W A00                  | [6e978f31cf](https://linux-hardware.org/?probe=6e978f31cf) | Sep 01, 2024 |
| MSI           | X79A-GD45                   | [2f16c5924f](https://linux-hardware.org/?probe=2f16c5924f) | Aug 29, 2024 |
| ASUSTek       | P5B SE                      | [d545ce5d36](https://linux-hardware.org/?probe=d545ce5d36) | Aug 28, 2024 |
| Phoenix Co... | PSB514 A12                  | [b6636750fd](https://linux-hardware.org/?probe=b6636750fd) | Aug 25, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [b4dc6d4025](https://linux-hardware.org/?probe=b4dc6d4025) | Aug 24, 2024 |
| ASRockRack    | E3C246D4U2-2T               | [c0a760b1bf](https://linux-hardware.org/?probe=c0a760b1bf) | Aug 23, 2024 |
| TYAN Compu... | S5553GM2NR-2T-HE-B          | [81952b8f97](https://linux-hardware.org/?probe=81952b8f97) | Aug 23, 2024 |
| ASUSTek       | M4N78-AM                    | [b8ac55c9e9](https://linux-hardware.org/?probe=b8ac55c9e9) | Aug 22, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [921ec4cff0](https://linux-hardware.org/?probe=921ec4cff0) | Aug 21, 2024 |
| ASRock        | X570 PG Velocita            | [a7fa96eb22](https://linux-hardware.org/?probe=a7fa96eb22) | Aug 21, 2024 |
| ASUSTek       | M4N78-AM                    | [c0fb89099b](https://linux-hardware.org/?probe=c0fb89099b) | Aug 20, 2024 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [48f20ce29b](https://linux-hardware.org/?probe=48f20ce29b) | Aug 19, 2024 |
| Dell          | 01XK1W A00                  | [3d467b94d9](https://linux-hardware.org/?probe=3d467b94d9) | Aug 14, 2024 |
| ASRock        | 970 Extreme3 R2.0           | [5aba1832f5](https://linux-hardware.org/?probe=5aba1832f5) | Aug 11, 2024 |
| AZW           | MINI S 10                   | [62de36544b](https://linux-hardware.org/?probe=62de36544b) | Aug 08, 2024 |
| Dell          | 0GXM1W A00                  | [e80fba5694](https://linux-hardware.org/?probe=e80fba5694) | Aug 05, 2024 |
| ASUSTek       | PRIME Z590-P                | [caf4309fbe](https://linux-hardware.org/?probe=caf4309fbe) | Aug 02, 2024 |
| HP            | 1998                        | [718d1847d7](https://linux-hardware.org/?probe=718d1847d7) | Aug 01, 2024 |
| Gigabyte      | GA-78LMT-USB3               | [f9b69bff33](https://linux-hardware.org/?probe=f9b69bff33) | Jul 31, 2024 |
| Seco          | D62 B.1                     | [fa8221ca8a](https://linux-hardware.org/?probe=fa8221ca8a) | Jul 30, 2024 |
| Dell          | 0XFWHV A00                  | [9845091f7e](https://linux-hardware.org/?probe=9845091f7e) | Jul 28, 2024 |
| Gigabyte      | B85M-DS3H-A                 | [345e2f9291](https://linux-hardware.org/?probe=345e2f9291) | Jul 24, 2024 |
| Gigabyte      | B75M-D3H                    | [6bfee437e7](https://linux-hardware.org/?probe=6bfee437e7) | Jul 23, 2024 |
| Gigabyte      | B550M DS3H                  | [03179392b1](https://linux-hardware.org/?probe=03179392b1) | Jul 22, 2024 |
| Gigabyte      | B365M H                     | [b2bc363dc6](https://linux-hardware.org/?probe=b2bc363dc6) | Jul 22, 2024 |
| Dell          | 051FJ8 A02                  | [757139a0c9](https://linux-hardware.org/?probe=757139a0c9) | Jul 21, 2024 |
| ASUSTek       | VANGUARD B85                | [7453f3f267](https://linux-hardware.org/?probe=7453f3f267) | Jul 19, 2024 |
| IceWhale T... | ZBB001-BK10032 ZMB          | [334a362aba](https://linux-hardware.org/?probe=334a362aba) | Jul 19, 2024 |
| Dell          | 01XK1W A00                  | [52d8794632](https://linux-hardware.org/?probe=52d8794632) | Jul 11, 2024 |
| Dell          | 01XK1W A00                  | [cc46df44b5](https://linux-hardware.org/?probe=cc46df44b5) | Jul 07, 2024 |
| Unknown       | Unknown                     | [e298a5c2b9](https://linux-hardware.org/?probe=e298a5c2b9) | Jul 06, 2024 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [6cadfd61f0](https://linux-hardware.org/?probe=6cadfd61f0) | Jul 05, 2024 |
| HP            | 213D A01                    | [84f1dcac4f](https://linux-hardware.org/?probe=84f1dcac4f) | Jul 02, 2024 |
| Inventec      | D CLASS A02                 | [b12e2708ad](https://linux-hardware.org/?probe=b12e2708ad) | Jun 30, 2024 |
| Unknown       | CN700-8237                  | [696664c26e](https://linux-hardware.org/?probe=696664c26e) | Jun 30, 2024 |
| ASUSTek       | M4N78-AM                    | [dcacfa2dba](https://linux-hardware.org/?probe=dcacfa2dba) | Jun 30, 2024 |
| HP            | ProLiant MicroServer        | [9c05a4ef2d](https://linux-hardware.org/?probe=9c05a4ef2d) | Jun 20, 2024 |
| Dell          | 0F56WK A03                  | [98a85a6db0](https://linux-hardware.org/?probe=98a85a6db0) | Jun 19, 2024 |
| Gigabyte      | B760M H DDR4                | [8d6956f9a6](https://linux-hardware.org/?probe=8d6956f9a6) | Jun 17, 2024 |
| Gigabyte      | B760M H DDR4                | [3e87b834d6](https://linux-hardware.org/?probe=3e87b834d6) | Jun 17, 2024 |
| ASRock        | 970M Pro3                   | [8fbbbe6686](https://linux-hardware.org/?probe=8fbbbe6686) | Jun 05, 2024 |
| ASRock        | 970M Pro3                   | [eeb2f4e975](https://linux-hardware.org/?probe=eeb2f4e975) | Jun 05, 2024 |
| ASRock        | B450 Pro4 R2.0              | [f8ad181953](https://linux-hardware.org/?probe=f8ad181953) | Jun 02, 2024 |
| Acer          | FI946GZG                    | [76cc9c0af8](https://linux-hardware.org/?probe=76cc9c0af8) | Jun 01, 2024 |
| Acer          | FI946GZG                    | [0cfa96d8b2](https://linux-hardware.org/?probe=0cfa96d8b2) | May 19, 2024 |
| Acer          | FI946GZG                    | [6abf4b2ff8](https://linux-hardware.org/?probe=6abf4b2ff8) | May 18, 2024 |
| Acer          | FI946GZG                    | [a4b0b80358](https://linux-hardware.org/?probe=a4b0b80358) | May 18, 2024 |
| Acer          | FI946GZG                    | [988cb72164](https://linux-hardware.org/?probe=988cb72164) | May 18, 2024 |
| Unknown       | CN700-8237                  | [45ae7f3f3d](https://linux-hardware.org/?probe=45ae7f3f3d) | May 17, 2024 |
| ASUSTek       | M4N78-AM                    | [b4082fa5bc](https://linux-hardware.org/?probe=b4082fa5bc) | May 17, 2024 |
| Dell          | 01XK1W A00                  | [29e720dc59](https://linux-hardware.org/?probe=29e720dc59) | May 15, 2024 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [a3d788cabf](https://linux-hardware.org/?probe=a3d788cabf) | May 15, 2024 |
| ASUSTek       | P5PL2                       | [fba00cbc3b](https://linux-hardware.org/?probe=fba00cbc3b) | May 14, 2024 |
| ASUSTek       | P5PL2                       | [299b8ee2c4](https://linux-hardware.org/?probe=299b8ee2c4) | May 14, 2024 |
| Unknown       | 775V88+                     | [73f73bf5c8](https://linux-hardware.org/?probe=73f73bf5c8) | May 11, 2024 |
| MSI           | Z490-A PRO                  | [79ec6e2044](https://linux-hardware.org/?probe=79ec6e2044) | May 09, 2024 |
| ASUSTek       | P8Z77-V LX                  | [b245c99221](https://linux-hardware.org/?probe=b245c99221) | May 07, 2024 |
| ASRock        | B450M Pro4                  | [b1caabc9b5](https://linux-hardware.org/?probe=b1caabc9b5) | May 05, 2024 |
| ASUSTek       | H81M-K                      | [f4dbf33638](https://linux-hardware.org/?probe=f4dbf33638) | May 02, 2024 |
| Acer          | Aspire M5910                | [61b5809dc9](https://linux-hardware.org/?probe=61b5809dc9) | May 01, 2024 |
| MSI           | MAG B550M MORTAR MAX WIF... | [d486386bde](https://linux-hardware.org/?probe=d486386bde) | Apr 26, 2024 |
| Dell          | 01XK1W A00                  | [a5fcd90239](https://linux-hardware.org/?probe=a5fcd90239) | Apr 26, 2024 |
| Colorful T... | C.A68M-E V15                | [b0b7690daa](https://linux-hardware.org/?probe=b0b7690daa) | Apr 20, 2024 |
| Unknown       | i855-W83627HF               | [e1c3562c4a](https://linux-hardware.org/?probe=e1c3562c4a) | Apr 18, 2024 |
| Gigabyte      | X570 UD                     | [5240449916](https://linux-hardware.org/?probe=5240449916) | Apr 18, 2024 |
| ASRock        | B550 Pro4                   | [f906fa4f7c](https://linux-hardware.org/?probe=f906fa4f7c) | Apr 18, 2024 |
| HP            | 805B                        | [d5bf7c2652](https://linux-hardware.org/?probe=d5bf7c2652) | Apr 18, 2024 |
| ASUSTek       | P8H61-M LX R2.0             | [0d46687bb7](https://linux-hardware.org/?probe=0d46687bb7) | Apr 17, 2024 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [ba12ac8498](https://linux-hardware.org/?probe=ba12ac8498) | Apr 17, 2024 |
| AMI           | Cherry Trail CR             | [e60bc95699](https://linux-hardware.org/?probe=e60bc95699) | Apr 16, 2024 |
| ASUSTek       | P8H61-M LX R2.0             | [7cad8d2493](https://linux-hardware.org/?probe=7cad8d2493) | Apr 16, 2024 |
| ASRock        | Z690 PG Riptide             | [b5891958b5](https://linux-hardware.org/?probe=b5891958b5) | Apr 12, 2024 |
| Gigabyte      | Z77X-UD3H                   | [716fbdb5b2](https://linux-hardware.org/?probe=716fbdb5b2) | Apr 12, 2024 |
| HP            | 1998                        | [c0b0ec87ec](https://linux-hardware.org/?probe=c0b0ec87ec) | Apr 10, 2024 |
| Lenovo        | 32E6 NOK                    | [b560c0d5fe](https://linux-hardware.org/?probe=b560c0d5fe) | Apr 09, 2024 |
| Lenovo        | 3740 NOK                    | [355c32d663](https://linux-hardware.org/?probe=355c32d663) | Apr 09, 2024 |
| Dell          | 01XK1W A00                  | [708da72614](https://linux-hardware.org/?probe=708da72614) | Apr 07, 2024 |
| MSI           | MS-B0A21                    | [e74fc30957](https://linux-hardware.org/?probe=e74fc30957) | Apr 05, 2024 |
| ASUSTek       | M5A97 PLUS                  | [b45101bd55](https://linux-hardware.org/?probe=b45101bd55) | Apr 02, 2024 |
| ASUSTek       | H110M-K                     | [8b3c41683d](https://linux-hardware.org/?probe=8b3c41683d) | Mar 30, 2024 |
| Gigabyte      | X570 UD                     | [539238d399](https://linux-hardware.org/?probe=539238d399) | Mar 29, 2024 |
| ASRock        | B550 Pro4                   | [9144eb7fe4](https://linux-hardware.org/?probe=9144eb7fe4) | Mar 29, 2024 |
| Gigabyte      | B550 AORUS PRO V2           | [d84d712a77](https://linux-hardware.org/?probe=d84d712a77) | Mar 29, 2024 |
| Dell          | 01XK1W A00                  | [6940ab6143](https://linux-hardware.org/?probe=6940ab6143) | Mar 24, 2024 |
| Dell          | 048DY8 A01                  | [05267117e8](https://linux-hardware.org/?probe=05267117e8) | Mar 23, 2024 |
| ASUSTek       | PRIME B760M-A D4            | [870960dbb0](https://linux-hardware.org/?probe=870960dbb0) | Mar 21, 2024 |
| Intel         | DB85FL AAG89861-201         | [15f1dac527](https://linux-hardware.org/?probe=15f1dac527) | Mar 21, 2024 |
| MSI           | Z97 GAMING 3                | [ed6f176128](https://linux-hardware.org/?probe=ed6f176128) | Mar 20, 2024 |
| ASUSTek       | PRIME Z590-P                | [73f72d473b](https://linux-hardware.org/?probe=73f72d473b) | Mar 19, 2024 |
| ASUSTek       | PRIME Z590-P                | [b526dd935f](https://linux-hardware.org/?probe=b526dd935f) | Mar 19, 2024 |
| JGINYUE       | X99-D8 Server V1.0          | [aad6effeb0](https://linux-hardware.org/?probe=aad6effeb0) | Mar 18, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | [fecb6cf968](https://linux-hardware.org/?probe=fecb6cf968) | Mar 18, 2024 |
| Fujitsu       | D3513-A1 S26361-D3513-A1    | [e467a62b44](https://linux-hardware.org/?probe=e467a62b44) | Mar 18, 2024 |
| ASUSTek       | AT4NM10T-I                  | [6d006ade6c](https://linux-hardware.org/?probe=6d006ade6c) | Mar 13, 2024 |
| ASUSTek       | AT4NM10T-I                  | [f7ddcc5c64](https://linux-hardware.org/?probe=f7ddcc5c64) | Mar 13, 2024 |
| Intel         | X58 V1608                   | [48e5f0f5a6](https://linux-hardware.org/?probe=48e5f0f5a6) | Mar 13, 2024 |
| Intel         | X58 V1608                   | [84ccc96b6b](https://linux-hardware.org/?probe=84ccc96b6b) | Mar 13, 2024 |
| ASRock        | X570 Phantom Gaming X       | [2a14a96457](https://linux-hardware.org/?probe=2a14a96457) | Mar 12, 2024 |
| Supermicro    | X9DR3-F                     | [f4f1646c44](https://linux-hardware.org/?probe=f4f1646c44) | Mar 10, 2024 |
| ASUSTek       | PRIME H510M-E               | [35d70301d6](https://linux-hardware.org/?probe=35d70301d6) | Mar 04, 2024 |
| MSI           | A320M-A PRO                 | [e69e7cf8f3](https://linux-hardware.org/?probe=e69e7cf8f3) | Mar 02, 2024 |
| MSI           | H310M PRO-M2 PLUS           | [f526190f31](https://linux-hardware.org/?probe=f526190f31) | Mar 01, 2024 |
| Pegatron      | IPM41-D3                    | [5249318369](https://linux-hardware.org/?probe=5249318369) | Feb 29, 2024 |
| ASUSTek       | M2N-E                       | [b3041e34a7](https://linux-hardware.org/?probe=b3041e34a7) | Feb 27, 2024 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [16759c3ced](https://linux-hardware.org/?probe=16759c3ced) | Feb 26, 2024 |
| ASUSTek       | M5A97 R2.0                  | [702dee066a](https://linux-hardware.org/?probe=702dee066a) | Feb 25, 2024 |
| ASRock        | B450 Steel Legend           | [ed5e87fbaf](https://linux-hardware.org/?probe=ed5e87fbaf) | Feb 21, 2024 |
| Dell          | 088DT1 A01                  | [2d163839aa](https://linux-hardware.org/?probe=2d163839aa) | Feb 21, 2024 |
| BESSTAR Te... | HM80                        | [ec826c4feb](https://linux-hardware.org/?probe=ec826c4feb) | Feb 20, 2024 |
| Dell          | 05842Y A00                  | [50fc41ef5c](https://linux-hardware.org/?probe=50fc41ef5c) | Feb 15, 2024 |
| ASUSTek       | M5A97 R2.0                  | [64bdaa6db8](https://linux-hardware.org/?probe=64bdaa6db8) | Feb 15, 2024 |
| Lenovo        | ThinkCentre M91p 4518A4M    | [56739f7004](https://linux-hardware.org/?probe=56739f7004) | Feb 15, 2024 |
| YANYU         | EPIC-C19                    | [9a93a8fd98](https://linux-hardware.org/?probe=9a93a8fd98) | Feb 12, 2024 |
| ASUSTek       | M5A97 R2.0                  | [2ef5e51010](https://linux-hardware.org/?probe=2ef5e51010) | Feb 12, 2024 |
| Intel         | X99 V1.0                    | [225644e904](https://linux-hardware.org/?probe=225644e904) | Feb 09, 2024 |
| MSI           | H110M PRO-VD                | [ba8e24ef8f](https://linux-hardware.org/?probe=ba8e24ef8f) | Feb 08, 2024 |
| ASRock        | G31M-GS                     | [50925f48af](https://linux-hardware.org/?probe=50925f48af) | Feb 06, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | [d8d66e42bc](https://linux-hardware.org/?probe=d8d66e42bc) | Feb 05, 2024 |
| HP            | 3397                        | [fcbc5b3ac6](https://linux-hardware.org/?probe=fcbc5b3ac6) | Jan 29, 2024 |
| ASUSTek       | PRIME B250M-C               | [5c34879ea0](https://linux-hardware.org/?probe=5c34879ea0) | Jan 28, 2024 |
| Lenovo        | 1052 SDK0J40697 WIN 3305... | [b0019abd70](https://linux-hardware.org/?probe=b0019abd70) | Jan 26, 2024 |
| ASRock        | 970M Pro3                   | [f5a09bd7f0](https://linux-hardware.org/?probe=f5a09bd7f0) | Jan 23, 2024 |
| Inventec      | D CLASS A02                 | [25d4886028](https://linux-hardware.org/?probe=25d4886028) | Jan 22, 2024 |
| ASRock        | H61M-HVS                    | [3cfc574d2d](https://linux-hardware.org/?probe=3cfc574d2d) | Jan 22, 2024 |
| MACHINIST     | X99 PR9                     | [2cac18e4ae](https://linux-hardware.org/?probe=2cac18e4ae) | Jan 21, 2024 |
| ASRock        | 970M Pro3                   | [37613f1ec6](https://linux-hardware.org/?probe=37613f1ec6) | Jan 20, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | [5b5d90211c](https://linux-hardware.org/?probe=5b5d90211c) | Jan 18, 2024 |
| ASRock        | J5040-ITX                   | [1d65e65b24](https://linux-hardware.org/?probe=1d65e65b24) | Jan 14, 2024 |
| ASRock        | C2750D4I                    | [c1426b3157](https://linux-hardware.org/?probe=c1426b3157) | Jan 14, 2024 |
| ASUSTek       | Z87-C                       | [acc914cabd](https://linux-hardware.org/?probe=acc914cabd) | Jan 12, 2024 |
| ASUSTek       | PRIME B350M-A               | [7eabdfe5d0](https://linux-hardware.org/?probe=7eabdfe5d0) | Jan 12, 2024 |
| HP            | 0B4Ch D                     | [d04339c0dc](https://linux-hardware.org/?probe=d04339c0dc) | Jan 12, 2024 |
| Dell          | 00V62H A01                  | [6f8302ddde](https://linux-hardware.org/?probe=6f8302ddde) | Jan 08, 2024 |
| MSI           | X79A-GD65                   | [55c0071638](https://linux-hardware.org/?probe=55c0071638) | Jan 06, 2024 |
| Dell          | 00V62H A01                  | [a44b8f65f6](https://linux-hardware.org/?probe=a44b8f65f6) | Jan 06, 2024 |
| Sapphire      | PI-AM3RS760G2               | [78696f8410](https://linux-hardware.org/?probe=78696f8410) | Jan 05, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | [408830a147](https://linux-hardware.org/?probe=408830a147) | Jan 05, 2024 |
| Dell          | 01XK1W A00                  | [90e3c8644a](https://linux-hardware.org/?probe=90e3c8644a) | Jan 05, 2024 |
| Phoenix Co... | PSB514 A12                  | [424bbc0491](https://linux-hardware.org/?probe=424bbc0491) | Jan 03, 2024 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [ee8caab1b7](https://linux-hardware.org/?probe=ee8caab1b7) | Jan 03, 2024 |
| HP            | 1495                        | [48d0ae2bf5](https://linux-hardware.org/?probe=48d0ae2bf5) | Dec 30, 2023 |
| ASUSTek       | CM6870                      | [529b92f758](https://linux-hardware.org/?probe=529b92f758) | Dec 28, 2023 |
| Gigabyte      | P55-UD4P                    | [62b547894e](https://linux-hardware.org/?probe=62b547894e) | Dec 25, 2023 |
| eMachines     | EMCP61M                     | [d464b480dd](https://linux-hardware.org/?probe=d464b480dd) | Dec 23, 2023 |
| HP            | 3396                        | [d0d084ecc8](https://linux-hardware.org/?probe=d0d084ecc8) | Dec 20, 2023 |
| Gigabyte      | Z77X-UD3H                   | [25a077d35e](https://linux-hardware.org/?probe=25a077d35e) | Dec 20, 2023 |
| ASUSTek       | V6-P5G31E                   | [83a8408a7e](https://linux-hardware.org/?probe=83a8408a7e) | Dec 20, 2023 |
| Gigabyte      | H370M DS3H-CF               | [4b6f645ef6](https://linux-hardware.org/?probe=4b6f645ef6) | Dec 20, 2023 |
| ASRock        | 970M Pro3                   | [85233c464d](https://linux-hardware.org/?probe=85233c464d) | Dec 19, 2023 |
| ASRock        | 970M Pro3                   | [acebee7435](https://linux-hardware.org/?probe=acebee7435) | Dec 19, 2023 |
| Gigabyte      | X570S UD                    | [058c14cd39](https://linux-hardware.org/?probe=058c14cd39) | Dec 17, 2023 |
| Dell          | 0M5WNK A02                  | [f47a8fcf1f](https://linux-hardware.org/?probe=f47a8fcf1f) | Dec 15, 2023 |
| Acer          | Aspire 1510 Rev.A           | [452be93d1b](https://linux-hardware.org/?probe=452be93d1b) | Dec 13, 2023 |
| AZW           | MINI S                      | [2512b54e60](https://linux-hardware.org/?probe=2512b54e60) | Dec 09, 2023 |
| Dell          | 0KP561                      | [bd0971e9cc](https://linux-hardware.org/?probe=bd0971e9cc) | Dec 08, 2023 |
| Intel         | H61                         | [fbc4dc7436](https://linux-hardware.org/?probe=fbc4dc7436) | Dec 06, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [a24f117537](https://linux-hardware.org/?probe=a24f117537) | Dec 02, 2023 |
| Dell          | 02YRK5 A02                  | [73c15b7e61](https://linux-hardware.org/?probe=73c15b7e61) | Dec 02, 2023 |
| MSI           | A78M-E45                    | [fd9a5e65e4](https://linux-hardware.org/?probe=fd9a5e65e4) | Nov 30, 2023 |
| ASUSTek       | P5N-MX                      | [c586157333](https://linux-hardware.org/?probe=c586157333) | Nov 30, 2023 |
| Lenovo        | 1048 SDK0J40697 WIN 3305... | [af727ea890](https://linux-hardware.org/?probe=af727ea890) | Nov 29, 2023 |
| HC Technol... | HCAR5000-MI                 | [7ff2232073](https://linux-hardware.org/?probe=7ff2232073) | Nov 29, 2023 |
| MSI           | X299 GAMING PRO CARBON      | [07d105a830](https://linux-hardware.org/?probe=07d105a830) | Nov 28, 2023 |
| Inventec      | DQ Class A02                | [760cc39516](https://linux-hardware.org/?probe=760cc39516) | Nov 27, 2023 |
| AZW           | MINI S                      | [ea6ad73049](https://linux-hardware.org/?probe=ea6ad73049) | Nov 27, 2023 |
| AZW           | MINI S                      | [54b3a350cc](https://linux-hardware.org/?probe=54b3a350cc) | Nov 27, 2023 |
| MSI           | B85M-G43                    | [c8c114c2df](https://linux-hardware.org/?probe=c8c114c2df) | Nov 26, 2023 |
| AZW           | U59                         | [b03056a1ad](https://linux-hardware.org/?probe=b03056a1ad) | Nov 24, 2023 |
| ASRock        | AB350 Pro4                  | [eff446af17](https://linux-hardware.org/?probe=eff446af17) | Nov 22, 2023 |
| ASUSTek       | PRIME X370-PRO              | [26da233e2b](https://linux-hardware.org/?probe=26da233e2b) | Nov 21, 2023 |
| Dell          | 0D6H9T A02                  | [034fe5ff39](https://linux-hardware.org/?probe=034fe5ff39) | Nov 20, 2023 |
| HP            | ProLiant MicroServer Gen... | [885444b8af](https://linux-hardware.org/?probe=885444b8af) | Nov 20, 2023 |
| HP            | 1905                        | [7718b065fd](https://linux-hardware.org/?probe=7718b065fd) | Nov 20, 2023 |
| ASUSTek       | PRIME Z370-P                | [2ffe9e80d4](https://linux-hardware.org/?probe=2ffe9e80d4) | Nov 19, 2023 |
| ASUSTek       | M5A97                       | [e5673cd079](https://linux-hardware.org/?probe=e5673cd079) | Nov 18, 2023 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | [1b1258a703](https://linux-hardware.org/?probe=1b1258a703) | Nov 17, 2023 |
| SIEMENS       | A5E49569366 RS-AF           | [07d3a028ec](https://linux-hardware.org/?probe=07d3a028ec) | Nov 17, 2023 |
| ASRock        | B550 Pro4                   | [1063cc1572](https://linux-hardware.org/?probe=1063cc1572) | Nov 15, 2023 |
| ASRock        | B550 Pro4                   | [8ee2dc1361](https://linux-hardware.org/?probe=8ee2dc1361) | Nov 15, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [6ff4b2ddd5](https://linux-hardware.org/?probe=6ff4b2ddd5) | Nov 15, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [e8e0ef7485](https://linux-hardware.org/?probe=e8e0ef7485) | Nov 15, 2023 |
| Dell          | 02YRK5 A02                  | [c419dad9b3](https://linux-hardware.org/?probe=c419dad9b3) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | [9e2ced6a3b](https://linux-hardware.org/?probe=9e2ced6a3b) | Nov 14, 2023 |
| Dell          | 02YRK5 A02                  | [a6e2f5e7f9](https://linux-hardware.org/?probe=a6e2f5e7f9) | Nov 14, 2023 |
| WanYou        | WanYouChunXiao              | [82c62804fc](https://linux-hardware.org/?probe=82c62804fc) | Nov 13, 2023 |
| ASRock        | J3455-ITX                   | [29b6fb8a4f](https://linux-hardware.org/?probe=29b6fb8a4f) | Nov 11, 2023 |
| Acer          | EG43M                       | [53270970b2](https://linux-hardware.org/?probe=53270970b2) | Nov 09, 2023 |
| HPE           | ProLiant MicroServer Gen... | [7461a3b207](https://linux-hardware.org/?probe=7461a3b207) | Nov 08, 2023 |
| Unknown       | Unknown                     | [5c2d84d61d](https://linux-hardware.org/?probe=5c2d84d61d) | Nov 06, 2023 |
| Unknown       | Unknown                     | [e84ce1e0d3](https://linux-hardware.org/?probe=e84ce1e0d3) | Nov 06, 2023 |
| Dell          | 01XK1W A00                  | [d6cd277a79](https://linux-hardware.org/?probe=d6cd277a79) | Nov 05, 2023 |
| ASRock        | H170M Pro4                  | [b87ccd7768](https://linux-hardware.org/?probe=b87ccd7768) | Nov 03, 2023 |
| ASRock        | Z77 WS                      | [73b9354a1a](https://linux-hardware.org/?probe=73b9354a1a) | Nov 02, 2023 |
| Lenovo        | ThinkCentre M58p 6234A1U    | [b684f82e3c](https://linux-hardware.org/?probe=b684f82e3c) | Nov 01, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [2d90a96dfb](https://linux-hardware.org/?probe=2d90a96dfb) | Oct 31, 2023 |
| Gigabyte      | H170N-WIFI-CF               | [af90b19d11](https://linux-hardware.org/?probe=af90b19d11) | Oct 30, 2023 |
| Shenzhen M... | TH80                        | [22dea9593a](https://linux-hardware.org/?probe=22dea9593a) | Oct 28, 2023 |
| ASUSTek       | H81M-PLUS                   | [f1ee66826b](https://linux-hardware.org/?probe=f1ee66826b) | Oct 24, 2023 |
| ASUSTek       | H81M-PLUS                   | [0f58ce148b](https://linux-hardware.org/?probe=0f58ce148b) | Oct 24, 2023 |
| ASUSTek       | PRIME A320M-K               | [36f77e9a81](https://linux-hardware.org/?probe=36f77e9a81) | Oct 24, 2023 |
| Gigabyte      | 990FXA-UD5                  | [c81764ba28](https://linux-hardware.org/?probe=c81764ba28) | Oct 22, 2023 |
| ASRock        | B550 Pro4                   | [0d55c2a6af](https://linux-hardware.org/?probe=0d55c2a6af) | Oct 20, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [745f21d8bc](https://linux-hardware.org/?probe=745f21d8bc) | Oct 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [67365133d9](https://linux-hardware.org/?probe=67365133d9) | Oct 17, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | [d48d54a951](https://linux-hardware.org/?probe=d48d54a951) | Oct 16, 2023 |
| ASUSTek       | B85M-E                      | [38155dfb23](https://linux-hardware.org/?probe=38155dfb23) | Oct 15, 2023 |
| ASUSTek       | PRIME B550M-A               | [2686ddd07b](https://linux-hardware.org/?probe=2686ddd07b) | Oct 15, 2023 |
| Quantum en... | HackBoard 2                 | [27781c0b8a](https://linux-hardware.org/?probe=27781c0b8a) | Oct 14, 2023 |
| ASRockRack    | X470D4U2-2T                 | [5f59c8dd03](https://linux-hardware.org/?probe=5f59c8dd03) | Oct 14, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [71e899c44a](https://linux-hardware.org/?probe=71e899c44a) | Oct 13, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [89197d184c](https://linux-hardware.org/?probe=89197d184c) | Oct 12, 2023 |
| Dell          | 0T10XW A00                  | [1489eccd85](https://linux-hardware.org/?probe=1489eccd85) | Oct 12, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | [925371c475](https://linux-hardware.org/?probe=925371c475) | Oct 11, 2023 |
| ASRock        | H61M-DGS                    | [b16ee3559a](https://linux-hardware.org/?probe=b16ee3559a) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0cbd266486](https://linux-hardware.org/?probe=0cbd266486) | Oct 11, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [8606120535](https://linux-hardware.org/?probe=8606120535) | Oct 10, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [0198bbbc8c](https://linux-hardware.org/?probe=0198bbbc8c) | Oct 10, 2023 |
| Gigabyte      | G31M-ES2L                   | [7912f11c78](https://linux-hardware.org/?probe=7912f11c78) | Oct 08, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b54dca932a](https://linux-hardware.org/?probe=b54dca932a) | Oct 07, 2023 |
| ASUSTek       | PRIME B365M-A               | [279922964e](https://linux-hardware.org/?probe=279922964e) | Oct 01, 2023 |
| ASRock        | H81M-HG4                    | [7f2a420ea3](https://linux-hardware.org/?probe=7f2a420ea3) | Sep 29, 2023 |
| ASRock        | 970M Pro3                   | [f004fa8e32](https://linux-hardware.org/?probe=f004fa8e32) | Sep 27, 2023 |
| ASRock        | 970M Pro3                   | [3646127006](https://linux-hardware.org/?probe=3646127006) | Sep 27, 2023 |
| Intel         | DP35DP AAD81073-206         | [426e9aff0f](https://linux-hardware.org/?probe=426e9aff0f) | Sep 26, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [273b056209](https://linux-hardware.org/?probe=273b056209) | Sep 25, 2023 |
| MSI           | MS-7318                     | [0e03a1818a](https://linux-hardware.org/?probe=0e03a1818a) | Sep 24, 2023 |
| Acer          | H11H4-AI V:1.0              | [971f03180e](https://linux-hardware.org/?probe=971f03180e) | Sep 24, 2023 |
| HP            | 1905                        | [786257c0e1](https://linux-hardware.org/?probe=786257c0e1) | Sep 23, 2023 |
| ASUSTek       | PRIME B660M-K D4            | [85c3791741](https://linux-hardware.org/?probe=85c3791741) | Sep 21, 2023 |
| MSI           | MS-7318                     | [38f011e50d](https://linux-hardware.org/?probe=38f011e50d) | Sep 21, 2023 |
| NetGear       | ReadyDATA 5200              | [c96e63c738](https://linux-hardware.org/?probe=c96e63c738) | Sep 20, 2023 |
| ASRock        | B550 Pro4                   | [af2217289d](https://linux-hardware.org/?probe=af2217289d) | Sep 19, 2023 |
| Gigabyte      | H55N-USB3                   | [afefe4b055](https://linux-hardware.org/?probe=afefe4b055) | Sep 18, 2023 |
| Supermicro    | X9DR3-F                     | [c2f0532df1](https://linux-hardware.org/?probe=c2f0532df1) | Sep 17, 2023 |
| ASUSTek       | P5G41T-M LX                 | [020deea6d9](https://linux-hardware.org/?probe=020deea6d9) | Sep 15, 2023 |
| Dell          | 01XK1W A00                  | [07e5f3eb14](https://linux-hardware.org/?probe=07e5f3eb14) | Sep 13, 2023 |
| Gigabyte      | P85-D3                      | [f090137faf](https://linux-hardware.org/?probe=f090137faf) | Sep 11, 2023 |
| MSI           | 970A-G46                    | [722b900724](https://linux-hardware.org/?probe=722b900724) | Sep 11, 2023 |
| ASRock        | H81M-HG4                    | [7398d477e4](https://linux-hardware.org/?probe=7398d477e4) | Sep 10, 2023 |
| HP            | 876C SMVB                   | [f122d202cc](https://linux-hardware.org/?probe=f122d202cc) | Sep 10, 2023 |
| ASRock        | J3455-ITX                   | [724826d84b](https://linux-hardware.org/?probe=724826d84b) | Sep 09, 2023 |
| ASUSTek       | PRIME Z370-P                | [9ce78af6e9](https://linux-hardware.org/?probe=9ce78af6e9) | Sep 08, 2023 |
| JGINYUE       | X79M-PLUS V2.2              | [1535be8e5f](https://linux-hardware.org/?probe=1535be8e5f) | Sep 06, 2023 |
| Intel         | DN2800MT AAG23738-803       | [8bdf13908a](https://linux-hardware.org/?probe=8bdf13908a) | Sep 06, 2023 |
| ASRockRack    | B565D4-V1L                  | [ff236ef40e](https://linux-hardware.org/?probe=ff236ef40e) | Sep 06, 2023 |
| Intel         | D33217GKE G76540-205        | [98630bd8bd](https://linux-hardware.org/?probe=98630bd8bd) | Sep 05, 2023 |
| Dell          | 0Y2MRG A00                  | [893bd8a261](https://linux-hardware.org/?probe=893bd8a261) | Sep 04, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | [49e3c842c1](https://linux-hardware.org/?probe=49e3c842c1) | Sep 04, 2023 |
| Unknown       | Unknown                     | [0c53c2df55](https://linux-hardware.org/?probe=0c53c2df55) | Sep 04, 2023 |
| ASRockRack    | X470D4U                     | [d38e269d11](https://linux-hardware.org/?probe=d38e269d11) | Sep 04, 2023 |
| MEGA          | G41T-M7 LGT                 | [8d645686ff](https://linux-hardware.org/?probe=8d645686ff) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7e93b2a981](https://linux-hardware.org/?probe=7e93b2a981) | Sep 02, 2023 |
| HP            | 1495                        | [09b1cf815c](https://linux-hardware.org/?probe=09b1cf815c) | Aug 31, 2023 |
| Dell          | 0T10XW A00                  | [cc093c964f](https://linux-hardware.org/?probe=cc093c964f) | Aug 29, 2023 |
| HP            | 1495                        | [86b148e011](https://linux-hardware.org/?probe=86b148e011) | Aug 26, 2023 |
| HP            | 158A                        | [e154a48901](https://linux-hardware.org/?probe=e154a48901) | Aug 25, 2023 |
| Dell          | 03NVJ6 A01                  | [71102ac92b](https://linux-hardware.org/?probe=71102ac92b) | Aug 24, 2023 |
| Acer          | Aspire XC-780               | [e154995d9e](https://linux-hardware.org/?probe=e154995d9e) | Aug 24, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | [266edae3d0](https://linux-hardware.org/?probe=266edae3d0) | Aug 23, 2023 |
| ASRock        | J4125B-ITX                  | [93853db701](https://linux-hardware.org/?probe=93853db701) | Aug 21, 2023 |
| ASRock        | J4125B-ITX                  | [f9058bcea1](https://linux-hardware.org/?probe=f9058bcea1) | Aug 21, 2023 |
| Medion        | MS-7728                     | [f548540f0c](https://linux-hardware.org/?probe=f548540f0c) | Aug 19, 2023 |
| Dell          | 0CT017                      | [0800c86065](https://linux-hardware.org/?probe=0800c86065) | Aug 14, 2023 |
| Unknown       | CN700-8237                  | [5890f075f7](https://linux-hardware.org/?probe=5890f075f7) | Aug 13, 2023 |
| ECS           | H61H2-CM                    | [7e33e0f06c](https://linux-hardware.org/?probe=7e33e0f06c) | Aug 13, 2023 |
| ECS           | H61H2-CM                    | [2656581f21](https://linux-hardware.org/?probe=2656581f21) | Aug 13, 2023 |
| Gigabyte      | B360HD3PLM-CF               | [650f840aa5](https://linux-hardware.org/?probe=650f840aa5) | Aug 13, 2023 |
| Unknown       | Unknown                     | [a28cd220cd](https://linux-hardware.org/?probe=a28cd220cd) | Aug 12, 2023 |
| Unknown       | Unknown                     | [f62d9a8a9a](https://linux-hardware.org/?probe=f62d9a8a9a) | Aug 12, 2023 |
| ASRock        | J4125B-ITX                  | [fa9ebd523f](https://linux-hardware.org/?probe=fa9ebd523f) | Aug 11, 2023 |
| Lenovo        | 3740 NOK                    | [9964e9a820](https://linux-hardware.org/?probe=9964e9a820) | Aug 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [2be2a9d5f4](https://linux-hardware.org/?probe=2be2a9d5f4) | Aug 09, 2023 |
| HP            | 8433 11                     | [93432b3df2](https://linux-hardware.org/?probe=93432b3df2) | Aug 09, 2023 |
| ASUSTek       | P5LD2-SE                    | [04d19635d5](https://linux-hardware.org/?probe=04d19635d5) | Aug 08, 2023 |
| ASUSTek       | P5LD2-SE                    | [671a686166](https://linux-hardware.org/?probe=671a686166) | Aug 08, 2023 |
| Biostar       | B365MHC                     | [1a7d051f1e](https://linux-hardware.org/?probe=1a7d051f1e) | Aug 06, 2023 |
| Gigabyte      | 990FXA-UD3                  | [4b57f7d6ea](https://linux-hardware.org/?probe=4b57f7d6ea) | Aug 06, 2023 |
| MSI           | B350 TOMAHAWK               | [3aa0e077c0](https://linux-hardware.org/?probe=3aa0e077c0) | Aug 05, 2023 |
| ASRock        | FM2A68M-DG3+                | [d930261042](https://linux-hardware.org/?probe=d930261042) | Aug 04, 2023 |
| Dell          | 0K095G A01                  | [ee2fb87d2f](https://linux-hardware.org/?probe=ee2fb87d2f) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [18f95b58ac](https://linux-hardware.org/?probe=18f95b58ac) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [349de8928b](https://linux-hardware.org/?probe=349de8928b) | Aug 04, 2023 |
| Gigabyte      | H510M H                     | [d74aab937a](https://linux-hardware.org/?probe=d74aab937a) | Aug 02, 2023 |
| ASRock        | X300-ITX                    | [70a181c62b](https://linux-hardware.org/?probe=70a181c62b) | Jul 31, 2023 |
| Intel         | DH55HC AAE70933-502         | [e849da706a](https://linux-hardware.org/?probe=e849da706a) | Jul 31, 2023 |
| Unknown       | Unknown                     | [11d7923fa3](https://linux-hardware.org/?probe=11d7923fa3) | Jul 31, 2023 |
| ASUSTek       | M4N78-AM                    | [a4740d2b14](https://linux-hardware.org/?probe=a4740d2b14) | Jul 31, 2023 |
| Gigabyte      | B550M K                     | [139e314619](https://linux-hardware.org/?probe=139e314619) | Jul 31, 2023 |
| Dell          | 0K240Y A01                  | [80b81f5eff](https://linux-hardware.org/?probe=80b81f5eff) | Jul 30, 2023 |
| ASRockRack    | X470D4U                     | [532a72a722](https://linux-hardware.org/?probe=532a72a722) | Jul 29, 2023 |
| Dell          | 0HD5W2 A01                  | [76394a9fc7](https://linux-hardware.org/?probe=76394a9fc7) | Jul 29, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [4cbba6622f](https://linux-hardware.org/?probe=4cbba6622f) | Jul 28, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [8cf3decf30](https://linux-hardware.org/?probe=8cf3decf30) | Jul 28, 2023 |
| Dell          | 06X1TJ A00                  | [e873051e73](https://linux-hardware.org/?probe=e873051e73) | Jul 27, 2023 |
| ABIT          | NF7-S/NF7,NF7-V,1.0         | [f5184af4e0](https://linux-hardware.org/?probe=f5184af4e0) | Jul 27, 2023 |
| Dell          | 01XK1W A00                  | [9793da4c20](https://linux-hardware.org/?probe=9793da4c20) | Jul 26, 2023 |
| ASRock        | X570 PG Velocita            | [64d86600a4](https://linux-hardware.org/?probe=64d86600a4) | Jul 26, 2023 |
| Phoenix Co... | PSB514 A11                  | [9791c84b0d](https://linux-hardware.org/?probe=9791c84b0d) | Jul 25, 2023 |
| Phoenix Co... | PSB514 A11                  | [8e271c334d](https://linux-hardware.org/?probe=8e271c334d) | Jul 24, 2023 |
| Lenovo        | ThinkCentre M58 7360W1J     | [1e1e565ac4](https://linux-hardware.org/?probe=1e1e565ac4) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | [9297c88bef](https://linux-hardware.org/?probe=9297c88bef) | Jul 23, 2023 |
| Dell          | OptiPlex 755                | [15827e6939](https://linux-hardware.org/?probe=15827e6939) | Jul 23, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [97edd15b78](https://linux-hardware.org/?probe=97edd15b78) | Jul 21, 2023 |
| HP            | ProLiant MicroServer Gen... | [a9214c4672](https://linux-hardware.org/?probe=a9214c4672) | Jul 21, 2023 |
| AAEON         | GENE-CML5 V1.0              | [4120e07431](https://linux-hardware.org/?probe=4120e07431) | Jul 19, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [98cddbfe0e](https://linux-hardware.org/?probe=98cddbfe0e) | Jul 18, 2023 |
| ASUSTek       | Z87-C                       | [5324c1542f](https://linux-hardware.org/?probe=5324c1542f) | Jul 18, 2023 |
| HP            | 805A                        | [d4e6fca09f](https://linux-hardware.org/?probe=d4e6fca09f) | Jul 17, 2023 |
| ASUSTek       | M5A78L/USB3                 | [a8b082a8be](https://linux-hardware.org/?probe=a8b082a8be) | Jul 17, 2023 |
| MSI           | H81M-P33                    | [0d3af45e51](https://linux-hardware.org/?probe=0d3af45e51) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [0c592730d7](https://linux-hardware.org/?probe=0c592730d7) | Jul 16, 2023 |
| Unknown       | Unknown                     | [1073620f0c](https://linux-hardware.org/?probe=1073620f0c) | Jul 16, 2023 |
| GEEKOM        | Mini IT 8                   | [4754a5fc1b](https://linux-hardware.org/?probe=4754a5fc1b) | Jul 16, 2023 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [9161db3013](https://linux-hardware.org/?probe=9161db3013) | Jul 15, 2023 |
| ASUSTek       | Z87-C                       | [33e96d6f34](https://linux-hardware.org/?probe=33e96d6f34) | Jul 15, 2023 |
| Gigabyte      | H81M-HD3                    | [4a6f56c54a](https://linux-hardware.org/?probe=4a6f56c54a) | Jul 15, 2023 |
| Dell          | 06X1TJ A00                  | [8ca31a1cfb](https://linux-hardware.org/?probe=8ca31a1cfb) | Jul 15, 2023 |
| ASRock        | FM2A68M-DG3+                | [19fdd69149](https://linux-hardware.org/?probe=19fdd69149) | Jul 14, 2023 |
| MSI           | H170M PRO-VDH               | [ce0a8a33fb](https://linux-hardware.org/?probe=ce0a8a33fb) | Jul 13, 2023 |
| ASRockRack    | ROMED8QM-2T                 | [a4fe5ea9c9](https://linux-hardware.org/?probe=a4fe5ea9c9) | Jul 13, 2023 |
| Dell          | 0D28YY A00                  | [1976f92f56](https://linux-hardware.org/?probe=1976f92f56) | Jul 12, 2023 |
| ASUSTek       | PRIME B360M-K               | [3a06b254a5](https://linux-hardware.org/?probe=3a06b254a5) | Jul 12, 2023 |
| Unknown       | i855-W83627HF               | [b330e5c4fb](https://linux-hardware.org/?probe=b330e5c4fb) | Jul 12, 2023 |
| Unknown       | i855-W83627HF               | [c0fb949fdc](https://linux-hardware.org/?probe=c0fb949fdc) | Jul 12, 2023 |
| Dell          | 0Y2MRG A00                  | [3866c4a7ff](https://linux-hardware.org/?probe=3866c4a7ff) | Jul 12, 2023 |
| Dell          | 0T10XW A01                  | [58fb207824](https://linux-hardware.org/?probe=58fb207824) | Jul 11, 2023 |
| ASUSTek       | A88XM-A                     | [544563aaae](https://linux-hardware.org/?probe=544563aaae) | Jul 11, 2023 |
| ASUSTek       | PRIME Z590-P                | [8d33346009](https://linux-hardware.org/?probe=8d33346009) | Jul 10, 2023 |
| Dell          | 01XK1W A00                  | [16aac702d5](https://linux-hardware.org/?probe=16aac702d5) | Jul 10, 2023 |
| Dell          | 0M5DCD A00                  | [ae3e8910bf](https://linux-hardware.org/?probe=ae3e8910bf) | Jul 10, 2023 |
| Gigabyte      | B560 HD3                    | [437e2c44d9](https://linux-hardware.org/?probe=437e2c44d9) | Jul 09, 2023 |
| Gigabyte      | X570S AORUS ELITE           | [6381f6da84](https://linux-hardware.org/?probe=6381f6da84) | Jul 09, 2023 |
| Unknown       | Unknown                     | [89a5a4461f](https://linux-hardware.org/?probe=89a5a4461f) | Jul 09, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [003c30f690](https://linux-hardware.org/?probe=003c30f690) | Jul 09, 2023 |
| AZW           | U59                         | [5cf3ddbe4b](https://linux-hardware.org/?probe=5cf3ddbe4b) | Jul 08, 2023 |
| AZW           | U59                         | [ea367423d1](https://linux-hardware.org/?probe=ea367423d1) | Jul 08, 2023 |
| AZW           | MINI S                      | [b13eb96728](https://linux-hardware.org/?probe=b13eb96728) | Jul 08, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [6afd29fd20](https://linux-hardware.org/?probe=6afd29fd20) | Jul 06, 2023 |
| HP            | 895C                        | [8a7f102530](https://linux-hardware.org/?probe=8a7f102530) | Jul 05, 2023 |
| Dell          | 0KYWH7 A00                  | [0c16b66976](https://linux-hardware.org/?probe=0c16b66976) | Jul 04, 2023 |
| Dell          | 0KWVT8 A02                  | [234e7f985d](https://linux-hardware.org/?probe=234e7f985d) | Jul 04, 2023 |
| ASUSTek       | Z87-A                       | [e000de29fe](https://linux-hardware.org/?probe=e000de29fe) | Jul 03, 2023 |
| EPoX Compu... | Intel I945 DDR2 : 5P945-... | [5aa77af58f](https://linux-hardware.org/?probe=5aa77af58f) | Jul 03, 2023 |
| Gigabyte      | B550 UD AC                  | [8e758ec922](https://linux-hardware.org/?probe=8e758ec922) | Jul 03, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | [f17cce1847](https://linux-hardware.org/?probe=f17cce1847) | Jul 02, 2023 |
| Supermicro    | X8ST3                       | [bac142132d](https://linux-hardware.org/?probe=bac142132d) | Jul 01, 2023 |
| ASUSTek       | Z170-A                      | [24adbf0475](https://linux-hardware.org/?probe=24adbf0475) | Jul 01, 2023 |
| NetGear       | ReadyDATA 5200              | [b89ca471ef](https://linux-hardware.org/?probe=b89ca471ef) | Jul 01, 2023 |
| Gigabyte      | B365M D3H-CF                | [f40af0020a](https://linux-hardware.org/?probe=f40af0020a) | Jun 29, 2023 |
| Supermicro    | X8ST3                       | [305a3e3c1a](https://linux-hardware.org/?probe=305a3e3c1a) | Jun 29, 2023 |
| Shuttle       | FS61                        | [a67d2edea8](https://linux-hardware.org/?probe=a67d2edea8) | Jun 28, 2023 |
| AMI           | Cherry Trail CR             | [65fb07ed8d](https://linux-hardware.org/?probe=65fb07ed8d) | Jun 27, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [1143a7eebc](https://linux-hardware.org/?probe=1143a7eebc) | Jun 27, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [baf77629c1](https://linux-hardware.org/?probe=baf77629c1) | Jun 26, 2023 |
| ASRock        | H61M-HVS                    | [a65485d236](https://linux-hardware.org/?probe=a65485d236) | Jun 25, 2023 |
| Dell          | 01XK1W A00                  | [53dbc2e799](https://linux-hardware.org/?probe=53dbc2e799) | Jun 24, 2023 |
| ASRockRack    | X470D4U                     | [2d49269787](https://linux-hardware.org/?probe=2d49269787) | Jun 23, 2023 |
| ASRockRack    | X470D4U2-2T                 | [4a11a4190a](https://linux-hardware.org/?probe=4a11a4190a) | Jun 23, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [1ca06fb3a9](https://linux-hardware.org/?probe=1ca06fb3a9) | Jun 23, 2023 |
| HP            | 3397                        | [8c9be2f4c0](https://linux-hardware.org/?probe=8c9be2f4c0) | Jun 23, 2023 |
| ASRockRack    | X470D4U                     | [d419086209](https://linux-hardware.org/?probe=d419086209) | Jun 22, 2023 |
| HP            | 3397                        | [a47ce0d4dc](https://linux-hardware.org/?probe=a47ce0d4dc) | Jun 22, 2023 |
| ASRockRack    | X470D4U                     | [9e0ba5032b](https://linux-hardware.org/?probe=9e0ba5032b) | Jun 21, 2023 |
| MSI           | H81M-P33                    | [62fb9cda50](https://linux-hardware.org/?probe=62fb9cda50) | Jun 20, 2023 |
| Dell          | 06FW8P A02                  | [f65ec61ffc](https://linux-hardware.org/?probe=f65ec61ffc) | Jun 20, 2023 |
| Dell          | 0PU052                      | [2eb6dceca9](https://linux-hardware.org/?probe=2eb6dceca9) | Jun 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [3eab70981f](https://linux-hardware.org/?probe=3eab70981f) | Jun 19, 2023 |
| AZW           | U59                         | [6f1191e5e2](https://linux-hardware.org/?probe=6f1191e5e2) | Jun 18, 2023 |
| Dell          | 01XK1W A00                  | [f431c0b66f](https://linux-hardware.org/?probe=f431c0b66f) | Jun 18, 2023 |
| MSI           | MAG B550M MORTAR MAX WIF... | [9994571651](https://linux-hardware.org/?probe=9994571651) | Jun 15, 2023 |
| HP            | 1589                        | [6bfe1d5b63](https://linux-hardware.org/?probe=6bfe1d5b63) | Jun 15, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [6e241e56cf](https://linux-hardware.org/?probe=6e241e56cf) | Jun 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [f9ebdca1bd](https://linux-hardware.org/?probe=f9ebdca1bd) | Jun 14, 2023 |
| HP            | 2AED                        | [2550c16272](https://linux-hardware.org/?probe=2550c16272) | Jun 13, 2023 |
| Intel         | JSL MRD                     | [764e533752](https://linux-hardware.org/?probe=764e533752) | Jun 13, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [59a9e7e2e8](https://linux-hardware.org/?probe=59a9e7e2e8) | Jun 11, 2023 |
| Intel         | SHARKBAY                    | [8772d55075](https://linux-hardware.org/?probe=8772d55075) | Jun 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | [4dcc51e897](https://linux-hardware.org/?probe=4dcc51e897) | Jun 10, 2023 |
| ASRock        | B365M Pro4-F                | [e54f1a9447](https://linux-hardware.org/?probe=e54f1a9447) | Jun 10, 2023 |
| ASUSTek       | K30BF_M32BF                 | [65b3c16165](https://linux-hardware.org/?probe=65b3c16165) | Jun 10, 2023 |
| ASUSTek       | P5GC-MX/1333                | [b47fab6285](https://linux-hardware.org/?probe=b47fab6285) | Jun 09, 2023 |
| Gigabyte      | B550M DS3H                  | [ea724e204b](https://linux-hardware.org/?probe=ea724e204b) | Jun 09, 2023 |
| Dell          | 0XCR8D A03                  | [e37bceb6fb](https://linux-hardware.org/?probe=e37bceb6fb) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [bcad738da6](https://linux-hardware.org/?probe=bcad738da6) | Jun 09, 2023 |
| Inventec      | VXC Class A02               | [c2bc26120f](https://linux-hardware.org/?probe=c2bc26120f) | Jun 08, 2023 |
| MSI           | B450M-A PRO MAX             | [230465c003](https://linux-hardware.org/?probe=230465c003) | Jun 08, 2023 |
| ASRock        | B365M Pro4-F                | [7ed0f0346c](https://linux-hardware.org/?probe=7ed0f0346c) | Jun 07, 2023 |
| ASUSTek       | H97M-E                      | [97140e9688](https://linux-hardware.org/?probe=97140e9688) | Jun 07, 2023 |
| Intel         | HURONRIVER                  | [57035a777c](https://linux-hardware.org/?probe=57035a777c) | Jun 07, 2023 |
| Lenovo        | ThinkCentre A58e 0841B4Y    | [fe410cd5db](https://linux-hardware.org/?probe=fe410cd5db) | Jun 07, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [db42ab94ee](https://linux-hardware.org/?probe=db42ab94ee) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d288737b23](https://linux-hardware.org/?probe=d288737b23) | Jun 05, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [3a1c1daa3d](https://linux-hardware.org/?probe=3a1c1daa3d) | Jun 05, 2023 |
| Gigabyte      | H470M DS3H                  | [e7bbac1b14](https://linux-hardware.org/?probe=e7bbac1b14) | Jun 04, 2023 |
| Gigabyte      | B360M HD3                   | [fcb1b60578](https://linux-hardware.org/?probe=fcb1b60578) | Jun 04, 2023 |
| MSI           | H81M-E34                    | [4c5f5c7903](https://linux-hardware.org/?probe=4c5f5c7903) | Jun 04, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | [0bd883cae2](https://linux-hardware.org/?probe=0bd883cae2) | Jun 04, 2023 |
| Dell          | 01XK1W A00                  | [8690705151](https://linux-hardware.org/?probe=8690705151) | Jun 04, 2023 |
| HP            | 843C                        | [e69fbf77e4](https://linux-hardware.org/?probe=e69fbf77e4) | Jun 04, 2023 |
| HP            | 843C                        | [21751c1221](https://linux-hardware.org/?probe=21751c1221) | Jun 04, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [18cb6a946b](https://linux-hardware.org/?probe=18cb6a946b) | Jun 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [8d4d1f7313](https://linux-hardware.org/?probe=8d4d1f7313) | Jun 03, 2023 |
| Gigabyte      | P75-D3                      | [a56c3ceb55](https://linux-hardware.org/?probe=a56c3ceb55) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [d6561ecd7b](https://linux-hardware.org/?probe=d6561ecd7b) | Jun 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | [43901d3db7](https://linux-hardware.org/?probe=43901d3db7) | Jun 02, 2023 |
| ASUSTek       | Z87-C                       | [20242d8299](https://linux-hardware.org/?probe=20242d8299) | Jun 02, 2023 |
| ASUSTek       | P8H61                       | [7e9f999121](https://linux-hardware.org/?probe=7e9f999121) | Jun 02, 2023 |
| Dell          | 01XK1W A00                  | [5846820609](https://linux-hardware.org/?probe=5846820609) | Jun 02, 2023 |
| Intel         | DH61WW AAG23116-204         | [2bfe32ef05](https://linux-hardware.org/?probe=2bfe32ef05) | Jun 02, 2023 |
| ChangWang     | CW56-58                     | [e00e626ea6](https://linux-hardware.org/?probe=e00e626ea6) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | [8557cd4efa](https://linux-hardware.org/?probe=8557cd4efa) | Jun 01, 2023 |
| Gigabyte      | H410M S2H V3                | [78e4d7a22b](https://linux-hardware.org/?probe=78e4d7a22b) | Jun 01, 2023 |
| ASUSTek       | H81M-C                      | [5fc6ec135b](https://linux-hardware.org/?probe=5fc6ec135b) | Jun 01, 2023 |
| ASRock        | J4125-ITX                   | [31e0f624be](https://linux-hardware.org/?probe=31e0f624be) | Jun 01, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX DDR4    | [5f1045564e](https://linux-hardware.org/?probe=5f1045564e) | Jun 01, 2023 |
| Inventec      | D CLASS A02                 | [433df815db](https://linux-hardware.org/?probe=433df815db) | Jun 01, 2023 |
| Intel         | DB75EN AAG39650-302         | [9872e0cb5c](https://linux-hardware.org/?probe=9872e0cb5c) | May 31, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [32a85827df](https://linux-hardware.org/?probe=32a85827df) | May 31, 2023 |
| ASUSTek       | Maximus VIII RANGER         | [354e883340](https://linux-hardware.org/?probe=354e883340) | May 31, 2023 |
| ASRock        | G41M-VS3                    | [166031ba4d](https://linux-hardware.org/?probe=166031ba4d) | May 31, 2023 |
| ASRock        | G41M-VS3                    | [8f55c9aa98](https://linux-hardware.org/?probe=8f55c9aa98) | May 31, 2023 |
| Dell          | 01XK1W A00                  | [8a18b7bada](https://linux-hardware.org/?probe=8a18b7bada) | May 31, 2023 |
| Dell          | 01XK1W A00                  | [611cf59f44](https://linux-hardware.org/?probe=611cf59f44) | May 31, 2023 |
| Intel         | X99                         | [cef654d9c5](https://linux-hardware.org/?probe=cef654d9c5) | May 30, 2023 |
| ASUSTek       | P4S8L                       | [c26269028e](https://linux-hardware.org/?probe=c26269028e) | May 30, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [698e3b5e35](https://linux-hardware.org/?probe=698e3b5e35) | May 30, 2023 |
| Supermicro    | X9DR3-F                     | [afcfc0fdf3](https://linux-hardware.org/?probe=afcfc0fdf3) | May 30, 2023 |
| MSI           | H55M-ED55                   | [a89bdc8ec0](https://linux-hardware.org/?probe=a89bdc8ec0) | May 30, 2023 |
| ASRock        | H310CM-HDV                  | [e6e310a9b4](https://linux-hardware.org/?probe=e6e310a9b4) | May 29, 2023 |
| ASRock        | H310CM-HDV                  | [84e791ec5e](https://linux-hardware.org/?probe=84e791ec5e) | May 29, 2023 |
| Inventec      | VXC Class A02               | [0befe25313](https://linux-hardware.org/?probe=0befe25313) | May 29, 2023 |
| Inventec      | VXC Class A02               | [363827ad8c](https://linux-hardware.org/?probe=363827ad8c) | May 29, 2023 |
| MSI           | Z390-A PRO                  | [c797a10bff](https://linux-hardware.org/?probe=c797a10bff) | May 29, 2023 |
| ASUSTek       | Z10PA-D8 Series             | [02821a3220](https://linux-hardware.org/?probe=02821a3220) | May 29, 2023 |
| Dell          | 040DDP A01                  | [bce6b61241](https://linux-hardware.org/?probe=bce6b61241) | May 29, 2023 |
| Unknown       | Unknown                     | [81e905b8bf](https://linux-hardware.org/?probe=81e905b8bf) | May 29, 2023 |
| MSI           | PRO Z690-A DDR4             | [b0be576b32](https://linux-hardware.org/?probe=b0be576b32) | May 28, 2023 |
| Intel         | X99                         | [70895d913f](https://linux-hardware.org/?probe=70895d913f) | May 28, 2023 |
| Dell          | 01XK1W A00                  | [a81daffe89](https://linux-hardware.org/?probe=a81daffe89) | May 28, 2023 |
| Dell          | 01XK1W A00                  | [ef918dfbfa](https://linux-hardware.org/?probe=ef918dfbfa) | May 28, 2023 |
| AZW           | MINI S                      | [55c17a6700](https://linux-hardware.org/?probe=55c17a6700) | May 27, 2023 |
| MSI           | H55M-ED55                   | [61e1fc3841](https://linux-hardware.org/?probe=61e1fc3841) | May 27, 2023 |
| ASUSTek       | K30BF_M32BF                 | [a262345925](https://linux-hardware.org/?probe=a262345925) | May 27, 2023 |
| HP            | 2B38                        | [528dfa2310](https://linux-hardware.org/?probe=528dfa2310) | May 27, 2023 |
| MSI           | MAG B460M MORTAR            | [ac03083cbd](https://linux-hardware.org/?probe=ac03083cbd) | May 27, 2023 |
| HP            | 895C                        | [f0986c3613](https://linux-hardware.org/?probe=f0986c3613) | May 26, 2023 |
| ASUSTek       | P4S8L                       | [75096a0d55](https://linux-hardware.org/?probe=75096a0d55) | May 25, 2023 |
| ASRock        | H61M-VG4                    | [4a6c3586fa](https://linux-hardware.org/?probe=4a6c3586fa) | May 25, 2023 |
| ASUSTek       | PRIME H270-PRO              | [2a14c05edc](https://linux-hardware.org/?probe=2a14c05edc) | May 25, 2023 |
| Acer          | EG31M R01-A4                | [447645dad3](https://linux-hardware.org/?probe=447645dad3) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2a3382aa0c](https://linux-hardware.org/?probe=2a3382aa0c) | May 25, 2023 |
| Unknown       | SKYBAY                      | [7884ad9bf4](https://linux-hardware.org/?probe=7884ad9bf4) | May 25, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [95321eedeb](https://linux-hardware.org/?probe=95321eedeb) | May 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | [24d62f2da3](https://linux-hardware.org/?probe=24d62f2da3) | May 25, 2023 |
| ASUSTek       | Berkeley                    | [c3e5448952](https://linux-hardware.org/?probe=c3e5448952) | May 24, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [4f91b6897e](https://linux-hardware.org/?probe=4f91b6897e) | May 24, 2023 |
| HP            | 1496                        | [2edc574902](https://linux-hardware.org/?probe=2edc574902) | May 24, 2023 |
| ASUSTek       | PRIME Z370-A II             | [e1681daf09](https://linux-hardware.org/?probe=e1681daf09) | May 24, 2023 |
| ASRock        | B760M Pro RS/D4 WiFi        | [05a334c56f](https://linux-hardware.org/?probe=05a334c56f) | May 24, 2023 |
| ASUSTek       | Z87M-PLUS                   | [f20bf1430d](https://linux-hardware.org/?probe=f20bf1430d) | May 24, 2023 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | [8ae80f0665](https://linux-hardware.org/?probe=8ae80f0665) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | [584c6658c6](https://linux-hardware.org/?probe=584c6658c6) | May 23, 2023 |
| ASUSTek       | PRIME H410M-D               | [e7d7c8f7d8](https://linux-hardware.org/?probe=e7d7c8f7d8) | May 23, 2023 |
| ASRock        | B760M Pro RS/D4 WiFi        | [c5d225afe1](https://linux-hardware.org/?probe=c5d225afe1) | May 23, 2023 |
| ASUSTek       | F2A85-M                     | [9532d524c9](https://linux-hardware.org/?probe=9532d524c9) | May 22, 2023 |
| Unknown       | Unknown                     | [aec9e5a959](https://linux-hardware.org/?probe=aec9e5a959) | May 22, 2023 |
| AZW           | U59                         | [59edf1c8a6](https://linux-hardware.org/?probe=59edf1c8a6) | May 22, 2023 |
| AZW           | U59                         | [b365dbf63a](https://linux-hardware.org/?probe=b365dbf63a) | May 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | [2b2367f9b1](https://linux-hardware.org/?probe=2b2367f9b1) | May 22, 2023 |
| ASUSTek       | K30BF_M32BF                 | [243f08edd7](https://linux-hardware.org/?probe=243f08edd7) | May 22, 2023 |
| Dell          | 0J1C3P A00                  | [5f3d8a94e6](https://linux-hardware.org/?probe=5f3d8a94e6) | May 22, 2023 |
| HP            | 2B38                        | [b45d316c65](https://linux-hardware.org/?probe=b45d316c65) | May 21, 2023 |
| HP            | 2B38                        | [c2ab5ab32a](https://linux-hardware.org/?probe=c2ab5ab32a) | May 21, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [e2d9f2e00f](https://linux-hardware.org/?probe=e2d9f2e00f) | May 21, 2023 |
| MSI           | A320M PRO-VD/S V2           | [f573a9cfae](https://linux-hardware.org/?probe=f573a9cfae) | May 21, 2023 |
| MSI           | Z170A SLI PLUS              | [a28c25cf6a](https://linux-hardware.org/?probe=a28c25cf6a) | May 21, 2023 |
| BESSTAR Te... | HM90                        | [874345ef99](https://linux-hardware.org/?probe=874345ef99) | May 21, 2023 |
| Dell          | 09KPNV A00                  | [118adf4d65](https://linux-hardware.org/?probe=118adf4d65) | May 20, 2023 |
| MSI           | X99S SLI PLUS               | [35b5231ed2](https://linux-hardware.org/?probe=35b5231ed2) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | [d17f4a61d7](https://linux-hardware.org/?probe=d17f4a61d7) | May 20, 2023 |
| ASRock        | Z390 Phantom Gaming SLI     | [0362a8829c](https://linux-hardware.org/?probe=0362a8829c) | May 20, 2023 |
| MSI           | 2AE0                        | [5f47fbb9cb](https://linux-hardware.org/?probe=5f47fbb9cb) | May 19, 2023 |
| MSI           | 2AE0                        | [c14f84a498](https://linux-hardware.org/?probe=c14f84a498) | May 19, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [875d854ec4](https://linux-hardware.org/?probe=875d854ec4) | May 18, 2023 |
| HP            | 8076                        | [fe142eecf2](https://linux-hardware.org/?probe=fe142eecf2) | May 18, 2023 |
| Intel         | DB75EN AAG39650-302         | [2f6a330442](https://linux-hardware.org/?probe=2f6a330442) | May 17, 2023 |
| Gigabyte      | B560 HD3                    | [2a6dcbf826](https://linux-hardware.org/?probe=2a6dcbf826) | May 17, 2023 |
| ASUSTek       | PRIME B365-PLUS             | [d43fc4e5b9](https://linux-hardware.org/?probe=d43fc4e5b9) | May 17, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [863f20642f](https://linux-hardware.org/?probe=863f20642f) | May 17, 2023 |
| ASUSTek       | B150-PLUS                   | [41b19667a8](https://linux-hardware.org/?probe=41b19667a8) | May 17, 2023 |
| MSI           | H510M-A PRO                 | [94ee6e64c4](https://linux-hardware.org/?probe=94ee6e64c4) | May 17, 2023 |
| AMI           | Cherry Trail CR             | [60abe2cf78](https://linux-hardware.org/?probe=60abe2cf78) | May 17, 2023 |
| ASUSTek       | P8Z68-V PRO                 | [84ee42ec2e](https://linux-hardware.org/?probe=84ee42ec2e) | May 17, 2023 |
| Dell          | 0D883F A04                  | [62cee990ff](https://linux-hardware.org/?probe=62cee990ff) | May 17, 2023 |
| Pegatron      | Yangtze                     | [4e3ce38e7b](https://linux-hardware.org/?probe=4e3ce38e7b) | May 17, 2023 |
| ASUSTek       | K30BF_M32BF                 | [6ce8f784b0](https://linux-hardware.org/?probe=6ce8f784b0) | May 17, 2023 |
| Dell          | 07KY25 A00                  | [16e4096f62](https://linux-hardware.org/?probe=16e4096f62) | May 16, 2023 |
| Dell          | 0782GW A00                  | [3699048599](https://linux-hardware.org/?probe=3699048599) | May 16, 2023 |
| Dell          | 0D24M8 A01                  | [4dcf0cf794](https://linux-hardware.org/?probe=4dcf0cf794) | May 16, 2023 |
| Intel         | DB75EN AAG39650-302         | [db27da6896](https://linux-hardware.org/?probe=db27da6896) | May 15, 2023 |
| ASUSTek       | PRIME B550M-K               | [61e6c3f5f1](https://linux-hardware.org/?probe=61e6c3f5f1) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [4ef8752290](https://linux-hardware.org/?probe=4ef8752290) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [b5c9664f50](https://linux-hardware.org/?probe=b5c9664f50) | May 15, 2023 |
| HP            | 339A                        | [4c56331906](https://linux-hardware.org/?probe=4c56331906) | May 14, 2023 |
| Intel         | D510MO AAE76523-404         | [03221e90c1](https://linux-hardware.org/?probe=03221e90c1) | May 14, 2023 |
| Dell          | 01XK1W A00                  | [b15a6ee63f](https://linux-hardware.org/?probe=b15a6ee63f) | May 13, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [921f919bb6](https://linux-hardware.org/?probe=921f919bb6) | May 12, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [b56358c287](https://linux-hardware.org/?probe=b56358c287) | May 12, 2023 |
| HP            | 1632                        | [d3a5a15faa](https://linux-hardware.org/?probe=d3a5a15faa) | May 12, 2023 |
| Dell          | 0K240Y A01                  | [cbc84d049a](https://linux-hardware.org/?probe=cbc84d049a) | May 12, 2023 |
| Dell          | 0HHV7N A00                  | [c458dad4b3](https://linux-hardware.org/?probe=c458dad4b3) | May 12, 2023 |
| Dell          | 0K240Y A02                  | [c51d42778d](https://linux-hardware.org/?probe=c51d42778d) | May 12, 2023 |
| Dell          | 0K240Y A02                  | [e65b0be462](https://linux-hardware.org/?probe=e65b0be462) | May 12, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6c61b581ba](https://linux-hardware.org/?probe=6c61b581ba) | May 12, 2023 |
| Gigabyte      | GA-970A-D3                  | [2302fc6860](https://linux-hardware.org/?probe=2302fc6860) | May 12, 2023 |
| AZW           | Green G3                    | [e11013e93f](https://linux-hardware.org/?probe=e11013e93f) | May 11, 2023 |
| Intel         | DB75EN AAG39650-302         | [e0ebf9fa8a](https://linux-hardware.org/?probe=e0ebf9fa8a) | May 11, 2023 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [4b5279de3c](https://linux-hardware.org/?probe=4b5279de3c) | May 11, 2023 |
| Unknown       | Unknown                     | [661a7cf306](https://linux-hardware.org/?probe=661a7cf306) | May 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | [25b993b097](https://linux-hardware.org/?probe=25b993b097) | May 10, 2023 |
| Dell          | 0C1R19 A01                  | [8a436329aa](https://linux-hardware.org/?probe=8a436329aa) | May 09, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [bcb5863b0a](https://linux-hardware.org/?probe=bcb5863b0a) | May 09, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [99dfb3e933](https://linux-hardware.org/?probe=99dfb3e933) | May 09, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | [e98eff32d6](https://linux-hardware.org/?probe=e98eff32d6) | May 08, 2023 |
| ASRock        | N68-VS3 FX                  | [26e8efdd69](https://linux-hardware.org/?probe=26e8efdd69) | May 08, 2023 |
| HP            | 0AA8h                       | [05689fe634](https://linux-hardware.org/?probe=05689fe634) | May 08, 2023 |
| ASUSTek       | PRIME X570-PRO              | [4a8c2101e8](https://linux-hardware.org/?probe=4a8c2101e8) | May 08, 2023 |
| HP            | 3031h                       | [dc7b257f83](https://linux-hardware.org/?probe=dc7b257f83) | May 08, 2023 |
| MSI           | H61M-E23                    | [22cdfbec52](https://linux-hardware.org/?probe=22cdfbec52) | May 08, 2023 |
| Lenovo        | 0x36C017AA SDK0J40700 WI... | [2a26d32cc3](https://linux-hardware.org/?probe=2a26d32cc3) | May 07, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [0fa7cb39ce](https://linux-hardware.org/?probe=0fa7cb39ce) | May 07, 2023 |
| Unknown       | Unknown                     | [18dcba612c](https://linux-hardware.org/?probe=18dcba612c) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [6ec1762e12](https://linux-hardware.org/?probe=6ec1762e12) | May 07, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [6816b3dddd](https://linux-hardware.org/?probe=6816b3dddd) | May 07, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [e40d8038da](https://linux-hardware.org/?probe=e40d8038da) | May 07, 2023 |
| ASUSTek       | E3 PRO GAMING V5            | [507036954e](https://linux-hardware.org/?probe=507036954e) | May 07, 2023 |
| Dell          | 0N4YC8 A00                  | [e3dc4ed549](https://linux-hardware.org/?probe=e3dc4ed549) | May 06, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [701907636a](https://linux-hardware.org/?probe=701907636a) | May 06, 2023 |
| HP            | 1998                        | [59c2c05cdb](https://linux-hardware.org/?probe=59c2c05cdb) | May 05, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [808f3370fc](https://linux-hardware.org/?probe=808f3370fc) | May 05, 2023 |
| Dell          | 0RN474                      | [b638694274](https://linux-hardware.org/?probe=b638694274) | May 05, 2023 |
| Unknown       | Unknown                     | [e7f4d1fdda](https://linux-hardware.org/?probe=e7f4d1fdda) | May 05, 2023 |
| ASRock        | N68-VS3 FX                  | [417be33443](https://linux-hardware.org/?probe=417be33443) | May 05, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | [4e80f798e2](https://linux-hardware.org/?probe=4e80f798e2) | May 04, 2023 |
| ASRock        | B760 Pro RS/D4              | [78dbd4cfb6](https://linux-hardware.org/?probe=78dbd4cfb6) | May 04, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | [0b303a3773](https://linux-hardware.org/?probe=0b303a3773) | May 03, 2023 |
| Unknown       | Unknown                     | [93a11302fb](https://linux-hardware.org/?probe=93a11302fb) | May 03, 2023 |
| Pegatron      | TRUCKEE                     | [7beeddc27c](https://linux-hardware.org/?probe=7beeddc27c) | May 03, 2023 |
| BESSTAR Te... | DMAF5                       | [b9f947fec3](https://linux-hardware.org/?probe=b9f947fec3) | May 02, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [86b607e7d4](https://linux-hardware.org/?probe=86b607e7d4) | May 02, 2023 |
| MSI           | Z87-G43                     | [8ba78b7b0b](https://linux-hardware.org/?probe=8ba78b7b0b) | May 02, 2023 |
| ASUSTek       | PRIME A520M-E               | [f149f8c9fb](https://linux-hardware.org/?probe=f149f8c9fb) | May 02, 2023 |
| Gigabyte      | H61M-D2H-USB3               | [9098e5d498](https://linux-hardware.org/?probe=9098e5d498) | May 01, 2023 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [ec30321519](https://linux-hardware.org/?probe=ec30321519) | May 01, 2023 |
| Intel         | DN2820FYK H24582-201        | [cfe5e305c8](https://linux-hardware.org/?probe=cfe5e305c8) | May 01, 2023 |
| MSI           | B85-G43 GAMING              | [0d041ed447](https://linux-hardware.org/?probe=0d041ed447) | May 01, 2023 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | [a237c703d9](https://linux-hardware.org/?probe=a237c703d9) | May 01, 2023 |
| HP            | 2B38                        | [bf99202e8b](https://linux-hardware.org/?probe=bf99202e8b) | May 01, 2023 |
| Dell          | 0NC2VH A01                  | [7fb1708706](https://linux-hardware.org/?probe=7fb1708706) | May 01, 2023 |
| HP            | 2B38                        | [6942eb2544](https://linux-hardware.org/?probe=6942eb2544) | May 01, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [ccb46c2a2b](https://linux-hardware.org/?probe=ccb46c2a2b) | Apr 30, 2023 |
| Hardkernel    | ODROID-H3                   | [139d61e128](https://linux-hardware.org/?probe=139d61e128) | Apr 29, 2023 |
| HP            | 3397                        | [8b84766d3d](https://linux-hardware.org/?probe=8b84766d3d) | Apr 29, 2023 |
| Medion        | MS-7708                     | [af2020cd9c](https://linux-hardware.org/?probe=af2020cd9c) | Apr 28, 2023 |
| Medion        | MS-7708                     | [424c4ca2db](https://linux-hardware.org/?probe=424c4ca2db) | Apr 28, 2023 |
| Intel         | H61 V124                    | [1fa0b34b3c](https://linux-hardware.org/?probe=1fa0b34b3c) | Apr 28, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [429d6f994a](https://linux-hardware.org/?probe=429d6f994a) | Apr 28, 2023 |
| ASUSTek       | B150-PRO D3                 | [35fa6f9a33](https://linux-hardware.org/?probe=35fa6f9a33) | Apr 28, 2023 |
| ASRock        | X470 Master SLI             | [cded55a936](https://linux-hardware.org/?probe=cded55a936) | Apr 28, 2023 |
| BESSTAR Te... | HM80                        | [476c573547](https://linux-hardware.org/?probe=476c573547) | Apr 28, 2023 |
| Shenzhen M... | F6BFC                       | [e2f7b853b1](https://linux-hardware.org/?probe=e2f7b853b1) | Apr 27, 2023 |
| Unknown       | Unknown                     | [e9f8ff6596](https://linux-hardware.org/?probe=e9f8ff6596) | Apr 27, 2023 |
| MSI           | MS-B0A21                    | [646d14f7b0](https://linux-hardware.org/?probe=646d14f7b0) | Apr 26, 2023 |
| HP            | 1632                        | [ace6df6aee](https://linux-hardware.org/?probe=ace6df6aee) | Apr 25, 2023 |
| Dell          | 0KYJ8C A00                  | [1e8226d149](https://linux-hardware.org/?probe=1e8226d149) | Apr 25, 2023 |
| ASUSTek       | PRIME Z590-P                | [5d03070db6](https://linux-hardware.org/?probe=5d03070db6) | Apr 24, 2023 |
| HP            | 8056                        | [a7686ee1af](https://linux-hardware.org/?probe=a7686ee1af) | Apr 24, 2023 |
| AZW           | MINI S                      | [d71153ae6e](https://linux-hardware.org/?probe=d71153ae6e) | Apr 24, 2023 |
| Intel         | SE7320EP2 D11950-402        | [ad1a126878](https://linux-hardware.org/?probe=ad1a126878) | Apr 24, 2023 |
| MSI           | Z87-G43                     | [4d908cb615](https://linux-hardware.org/?probe=4d908cb615) | Apr 24, 2023 |
| Dell          | 0N0992 A01                  | [a8e8000610](https://linux-hardware.org/?probe=a8e8000610) | Apr 24, 2023 |
| Biostar       | B350ET2                     | [47289e48eb](https://linux-hardware.org/?probe=47289e48eb) | Apr 23, 2023 |
| ASRock        | B560 Pro4                   | [3a9f7b19fa](https://linux-hardware.org/?probe=3a9f7b19fa) | Apr 23, 2023 |
| MSI           | Z390-A PRO                  | [74cf7ef6e5](https://linux-hardware.org/?probe=74cf7ef6e5) | Apr 23, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | [78c1951456](https://linux-hardware.org/?probe=78c1951456) | Apr 23, 2023 |
| ASRock        | B560 Pro4                   | [965aa93228](https://linux-hardware.org/?probe=965aa93228) | Apr 23, 2023 |
| Unknown       | Unknown                     | [0605faa66d](https://linux-hardware.org/?probe=0605faa66d) | Apr 23, 2023 |
| AZW           | U59                         | [8921a6910d](https://linux-hardware.org/?probe=8921a6910d) | Apr 23, 2023 |
| Shuttle       | DS20U                       | [2e8e79b5ff](https://linux-hardware.org/?probe=2e8e79b5ff) | Apr 23, 2023 |
| HP            | 845A                        | [41a0cad635](https://linux-hardware.org/?probe=41a0cad635) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [ccb49b32a0](https://linux-hardware.org/?probe=ccb49b32a0) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [2651f47f8c](https://linux-hardware.org/?probe=2651f47f8c) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [03a331aa44](https://linux-hardware.org/?probe=03a331aa44) | Apr 22, 2023 |
| ASUSTek       | PRIME B650M-A AX            | [0a90dc180c](https://linux-hardware.org/?probe=0a90dc180c) | Apr 22, 2023 |
| MW            | GMLK-2_5G4L                 | [b5ffb4ee22](https://linux-hardware.org/?probe=b5ffb4ee22) | Apr 22, 2023 |
| Gigabyte      | B550M DS3H                  | [e98b4fdd23](https://linux-hardware.org/?probe=e98b4fdd23) | Apr 21, 2023 |
| ASUSTek       | B85M-G                      | [4392c46287](https://linux-hardware.org/?probe=4392c46287) | Apr 20, 2023 |
| Gigabyte      | Z77-DS3H                    | [cde1ecf1c6](https://linux-hardware.org/?probe=cde1ecf1c6) | Apr 20, 2023 |
| Shuttle       | FS81                        | [051b7f4753](https://linux-hardware.org/?probe=051b7f4753) | Apr 20, 2023 |
| ASRock        | B550 Pro4                   | [2d4578e52a](https://linux-hardware.org/?probe=2d4578e52a) | Apr 20, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [4abfcb4ab3](https://linux-hardware.org/?probe=4abfcb4ab3) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [e93357961f](https://linux-hardware.org/?probe=e93357961f) | Apr 19, 2023 |
| MSI           | MPG Z590 GAMING EDGE WIF... | [97860c01ca](https://linux-hardware.org/?probe=97860c01ca) | Apr 19, 2023 |
| ASRock        | J3455-ITX                   | [895abaa15e](https://linux-hardware.org/?probe=895abaa15e) | Apr 19, 2023 |
| ASRock        | J3455-ITX                   | [f70d811bbd](https://linux-hardware.org/?probe=f70d811bbd) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [fd82dc08dc](https://linux-hardware.org/?probe=fd82dc08dc) | Apr 18, 2023 |
| MSI           | MAG Z390M MORTAR            | [121237b9c1](https://linux-hardware.org/?probe=121237b9c1) | Apr 17, 2023 |
| MSI           | MPG B650I EDGE WIFI         | [11f85df48e](https://linux-hardware.org/?probe=11f85df48e) | Apr 17, 2023 |
| ASRock        | H310M-STX                   | [438e774de5](https://linux-hardware.org/?probe=438e774de5) | Apr 17, 2023 |
| HP            | 0AECh D                     | [f6c67d337e](https://linux-hardware.org/?probe=f6c67d337e) | Apr 17, 2023 |
| ASUSTek       | K30BF_M32BF                 | [6ea01fad49](https://linux-hardware.org/?probe=6ea01fad49) | Apr 17, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7f5feb82ab](https://linux-hardware.org/?probe=7f5feb82ab) | Apr 17, 2023 |
| Gigabyte      | Z690 AORUS ULTRA            | [a4bb147f89](https://linux-hardware.org/?probe=a4bb147f89) | Apr 17, 2023 |
| ASUSTek       | P8H77-M                     | [6364dbb93a](https://linux-hardware.org/?probe=6364dbb93a) | Apr 16, 2023 |
| Dell          | 0HHV7N A00                  | [4443ff9154](https://linux-hardware.org/?probe=4443ff9154) | Apr 16, 2023 |
| HP            | 18E7                        | [6c2c248eec](https://linux-hardware.org/?probe=6c2c248eec) | Apr 16, 2023 |
| ASUSTek       | PRIME X570-P                | [1f02ee3393](https://linux-hardware.org/?probe=1f02ee3393) | Apr 16, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [7d9278e08a](https://linux-hardware.org/?probe=7d9278e08a) | Apr 15, 2023 |
| ASRock        | H61M-DGS                    | [e0b2a066ee](https://linux-hardware.org/?probe=e0b2a066ee) | Apr 15, 2023 |
| Medion        | TJ4125                      | [887d24e023](https://linux-hardware.org/?probe=887d24e023) | Apr 14, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [d7768947bc](https://linux-hardware.org/?probe=d7768947bc) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [f4cbe67033](https://linux-hardware.org/?probe=f4cbe67033) | Apr 14, 2023 |
| ASRock        | H81M-VG4 R2.0               | [cc951809ed](https://linux-hardware.org/?probe=cc951809ed) | Apr 14, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [7730eb04fa](https://linux-hardware.org/?probe=7730eb04fa) | Apr 14, 2023 |
| Gigabyte      | B75M-D3H                    | [6106a2c31f](https://linux-hardware.org/?probe=6106a2c31f) | Apr 13, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [70e0ac9475](https://linux-hardware.org/?probe=70e0ac9475) | Apr 13, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [5be961705c](https://linux-hardware.org/?probe=5be961705c) | Apr 13, 2023 |
| IceWhale T... | ZimaBoard 216 ZMB           | [33a7fad816](https://linux-hardware.org/?probe=33a7fad816) | Apr 13, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [721a60ff30](https://linux-hardware.org/?probe=721a60ff30) | Apr 13, 2023 |
| ASRock        | H410M-HVS R2.0              | [7f388965d7](https://linux-hardware.org/?probe=7f388965d7) | Apr 13, 2023 |
| HP            | 21EF                        | [d2b3751fd1](https://linux-hardware.org/?probe=d2b3751fd1) | Apr 13, 2023 |
| Dell          | 0XD433 A00                  | [e0a30bf441](https://linux-hardware.org/?probe=e0a30bf441) | Apr 12, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [108725a205](https://linux-hardware.org/?probe=108725a205) | Apr 12, 2023 |
| MSI           | Z370 PC PRO                 | [fb3078d5c3](https://linux-hardware.org/?probe=fb3078d5c3) | Apr 12, 2023 |
| Intel         | H61 V124                    | [28b73b97b3](https://linux-hardware.org/?probe=28b73b97b3) | Apr 12, 2023 |
| Dell          | 01XK1W A00                  | [4eb8c9f372](https://linux-hardware.org/?probe=4eb8c9f372) | Apr 12, 2023 |
| MSI           | MS-7060                     | [d78aaad9ec](https://linux-hardware.org/?probe=d78aaad9ec) | Apr 12, 2023 |
| HP            | 1589                        | [c04488f359](https://linux-hardware.org/?probe=c04488f359) | Apr 11, 2023 |
| ASUSTek       | PRIME Z590-P                | [e4299a2ce6](https://linux-hardware.org/?probe=e4299a2ce6) | Apr 11, 2023 |
| HP            | 1589                        | [e52c705c13](https://linux-hardware.org/?probe=e52c705c13) | Apr 11, 2023 |
| ASUSTek       | PRIME Z370-A                | [64759fca72](https://linux-hardware.org/?probe=64759fca72) | Apr 10, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [5b0601fc42](https://linux-hardware.org/?probe=5b0601fc42) | Apr 09, 2023 |
| Medion        | TJ4125                      | [5c5f39a8fd](https://linux-hardware.org/?probe=5c5f39a8fd) | Apr 09, 2023 |
| HP            | 2B29                        | [b909d3c46d](https://linux-hardware.org/?probe=b909d3c46d) | Apr 09, 2023 |
| HP            | 2B29                        | [1fd9cd3d7c](https://linux-hardware.org/?probe=1fd9cd3d7c) | Apr 09, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [3b665833d1](https://linux-hardware.org/?probe=3b665833d1) | Apr 09, 2023 |
| HP            | 83E9                        | [4e62f72ee2](https://linux-hardware.org/?probe=4e62f72ee2) | Apr 08, 2023 |
| HP            | 83E9                        | [36fdd064cc](https://linux-hardware.org/?probe=36fdd064cc) | Apr 08, 2023 |
| AMI           | Intel                       | [48c620d141](https://linux-hardware.org/?probe=48c620d141) | Apr 08, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | [36c87da9d9](https://linux-hardware.org/?probe=36c87da9d9) | Apr 07, 2023 |
| Inventec      | D CLASS A02                 | [3d53baddbf](https://linux-hardware.org/?probe=3d53baddbf) | Apr 07, 2023 |
| Inventec      | VXC Class A02               | [3ff1b18b81](https://linux-hardware.org/?probe=3ff1b18b81) | Apr 07, 2023 |
| Dell          | 01XK1W A00                  | [023a578b76](https://linux-hardware.org/?probe=023a578b76) | Apr 07, 2023 |
| MSI           | MS-7253                     | [1b9074e1ac](https://linux-hardware.org/?probe=1b9074e1ac) | Apr 06, 2023 |
| Foxconn       | 2A8C                        | [f202bac0de](https://linux-hardware.org/?probe=f202bac0de) | Apr 06, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | [6d7db3d917](https://linux-hardware.org/?probe=6d7db3d917) | Apr 06, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [ca1cdc7f46](https://linux-hardware.org/?probe=ca1cdc7f46) | Apr 06, 2023 |
| MSI           | MS-B1831                    | [9ea2ec4f47](https://linux-hardware.org/?probe=9ea2ec4f47) | Apr 06, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [ea7a921618](https://linux-hardware.org/?probe=ea7a921618) | Apr 06, 2023 |
| Gigabyte      | F2A88XN-WIFI                | [125f93468e](https://linux-hardware.org/?probe=125f93468e) | Apr 06, 2023 |
| HP            | 895C                        | [27de3e2244](https://linux-hardware.org/?probe=27de3e2244) | Apr 06, 2023 |
| Huanan        | X99-F8D PLUS V1.1           | [9c6a3de994](https://linux-hardware.org/?probe=9c6a3de994) | Apr 05, 2023 |
| HP            | 895C                        | [3c87e6de19](https://linux-hardware.org/?probe=3c87e6de19) | Apr 05, 2023 |
| ASUSTek       | PRIME A320M-K               | [6dbb59e2fc](https://linux-hardware.org/?probe=6dbb59e2fc) | Apr 05, 2023 |
| ASUSTek       | Z170-K                      | [d9ab0a1946](https://linux-hardware.org/?probe=d9ab0a1946) | Apr 05, 2023 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [2783ec6da9](https://linux-hardware.org/?probe=2783ec6da9) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | [7f6103b394](https://linux-hardware.org/?probe=7f6103b394) | Apr 05, 2023 |
| Shenzhen M... | F7BFD                       | [ac039ed7e6](https://linux-hardware.org/?probe=ac039ed7e6) | Apr 05, 2023 |
| HP            | 1790                        | [55e3d423e0](https://linux-hardware.org/?probe=55e3d423e0) | Apr 05, 2023 |
| Inventec      | D CLASS A02                 | [58cf8c28ff](https://linux-hardware.org/?probe=58cf8c28ff) | Apr 05, 2023 |
| Inventec      | D CLASS A02                 | [7f904181ea](https://linux-hardware.org/?probe=7f904181ea) | Apr 04, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [b5106f816a](https://linux-hardware.org/?probe=b5106f816a) | Apr 04, 2023 |
| Acer          | WG43M                       | [10bf0c0d1a](https://linux-hardware.org/?probe=10bf0c0d1a) | Apr 04, 2023 |
| MSI           | MAG B460 TORPEDO            | [62a628da55](https://linux-hardware.org/?probe=62a628da55) | Apr 04, 2023 |
| Unknown       | Q-790                       | [5f41d7d182](https://linux-hardware.org/?probe=5f41d7d182) | Apr 04, 2023 |
| ASUSTek       | P8Z77-M                     | [ec9901fcd5](https://linux-hardware.org/?probe=ec9901fcd5) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [849adee9bf](https://linux-hardware.org/?probe=849adee9bf) | Apr 03, 2023 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | [6b554016fe](https://linux-hardware.org/?probe=6b554016fe) | Apr 03, 2023 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | [aaa2e273c1](https://linux-hardware.org/?probe=aaa2e273c1) | Apr 03, 2023 |
| Dell          | 07N90W A02                  | [fd992821e0](https://linux-hardware.org/?probe=fd992821e0) | Apr 03, 2023 |
| Unknown       | Unknown                     | [cbcfbb8783](https://linux-hardware.org/?probe=cbcfbb8783) | Apr 03, 2023 |
| BESSTAR Te... | HM90                        | [722013016f](https://linux-hardware.org/?probe=722013016f) | Apr 03, 2023 |
| Shuttle       | FH370                       | [29b2ad6149](https://linux-hardware.org/?probe=29b2ad6149) | Apr 03, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME      | [03fe72ba57](https://linux-hardware.org/?probe=03fe72ba57) | Apr 02, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [6844d471e4](https://linux-hardware.org/?probe=6844d471e4) | Apr 02, 2023 |
| Unknown       | Unknown                     | [077bed9951](https://linux-hardware.org/?probe=077bed9951) | Apr 02, 2023 |
| Google        | Panther                     | [73f3ed3c65](https://linux-hardware.org/?probe=73f3ed3c65) | Apr 02, 2023 |
| MSI           | MS-7318                     | [3d02816b24](https://linux-hardware.org/?probe=3d02816b24) | Apr 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [2a597d7a33](https://linux-hardware.org/?probe=2a597d7a33) | Apr 01, 2023 |
| Dell          | 040DDP A00                  | [0771f1547e](https://linux-hardware.org/?probe=0771f1547e) | Apr 01, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [32c0716bfa](https://linux-hardware.org/?probe=32c0716bfa) | Apr 01, 2023 |
| Medion        | TJ4125                      | [2627cc2d42](https://linux-hardware.org/?probe=2627cc2d42) | Apr 01, 2023 |
| Gigabyte      | A320M-H-CF                  | [a5c21e7892](https://linux-hardware.org/?probe=a5c21e7892) | Apr 01, 2023 |
| Gigabyte      | A320M-H-CF                  | [4b873550ab](https://linux-hardware.org/?probe=4b873550ab) | Apr 01, 2023 |
| ASUSTek       | TS10                        | [054de4f36a](https://linux-hardware.org/?probe=054de4f36a) | Mar 31, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [47f6f4653b](https://linux-hardware.org/?probe=47f6f4653b) | Mar 31, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [624d23335b](https://linux-hardware.org/?probe=624d23335b) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [d6b6c88578](https://linux-hardware.org/?probe=d6b6c88578) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [704145641e](https://linux-hardware.org/?probe=704145641e) | Mar 31, 2023 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [56c886069b](https://linux-hardware.org/?probe=56c886069b) | Mar 31, 2023 |
| Unknown       | iKoolCore R1 iKoolCore R... | [050875ba5f](https://linux-hardware.org/?probe=050875ba5f) | Mar 30, 2023 |
| AZW           | U59                         | [c87edfe3b6](https://linux-hardware.org/?probe=c87edfe3b6) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | [fbcdd4ed13](https://linux-hardware.org/?probe=fbcdd4ed13) | Mar 30, 2023 |
| ASRock        | X670E PG Lightning          | [6078dd3087](https://linux-hardware.org/?probe=6078dd3087) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | [76e79f5f19](https://linux-hardware.org/?probe=76e79f5f19) | Mar 30, 2023 |
| Gigabyte      | H61M-S1                     | [78d1316a55](https://linux-hardware.org/?probe=78d1316a55) | Mar 30, 2023 |
| ASUSTek       | F2A85-M                     | [4d6ae3ef0f](https://linux-hardware.org/?probe=4d6ae3ef0f) | Mar 30, 2023 |
| HP            | 213D A01                    | [d5fb38a71b](https://linux-hardware.org/?probe=d5fb38a71b) | Mar 30, 2023 |
| HP            | 213D A01                    | [79d8e1b64f](https://linux-hardware.org/?probe=79d8e1b64f) | Mar 30, 2023 |
| HP            | 3048h                       | [1a4d86fca8](https://linux-hardware.org/?probe=1a4d86fca8) | Mar 30, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | [4976f6b6b2](https://linux-hardware.org/?probe=4976f6b6b2) | Mar 30, 2023 |
| MSI           | B450 TOMAHAWK               | [9251f2d561](https://linux-hardware.org/?probe=9251f2d561) | Mar 30, 2023 |
| MSI           | B450 TOMAHAWK               | [2d28ba397e](https://linux-hardware.org/?probe=2d28ba397e) | Mar 29, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | [e772d0e916](https://linux-hardware.org/?probe=e772d0e916) | Mar 29, 2023 |
| AZW           | U59                         | [3776cd7fb3](https://linux-hardware.org/?probe=3776cd7fb3) | Mar 29, 2023 |
| AZW           | U59                         | [f7958b8f39](https://linux-hardware.org/?probe=f7958b8f39) | Mar 29, 2023 |
| Medion        | TJ4125                      | [e03693b0f0](https://linux-hardware.org/?probe=e03693b0f0) | Mar 29, 2023 |
| ASRockRack    | X470D4U2-2T                 | [38e3ecfb84](https://linux-hardware.org/?probe=38e3ecfb84) | Mar 29, 2023 |
| Intel         | 945GCT-M                    | [d7e65e945e](https://linux-hardware.org/?probe=d7e65e945e) | Mar 29, 2023 |
| ECS           | G31T-M                      | [d6149cbd0d](https://linux-hardware.org/?probe=d6149cbd0d) | Mar 29, 2023 |
| Dell          | 01XK1W A00                  | [bf9252a1ac](https://linux-hardware.org/?probe=bf9252a1ac) | Mar 29, 2023 |
| HP            | 89B4 A                      | [cb8136a176](https://linux-hardware.org/?probe=cb8136a176) | Mar 28, 2023 |
| Pegatron      | Maureen                     | [0fdcf4a5bc](https://linux-hardware.org/?probe=0fdcf4a5bc) | Mar 28, 2023 |
| Unknown       | Unknown                     | [8f1561c37b](https://linux-hardware.org/?probe=8f1561c37b) | Mar 28, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | [11cb22743c](https://linux-hardware.org/?probe=11cb22743c) | Mar 27, 2023 |
| ASRock        | 770 Extreme3                | [9cd5d1485c](https://linux-hardware.org/?probe=9cd5d1485c) | Mar 27, 2023 |
| HP            | 18E6                        | [a406dc2463](https://linux-hardware.org/?probe=a406dc2463) | Mar 27, 2023 |
| Medion        | TJ4125                      | [571b476915](https://linux-hardware.org/?probe=571b476915) | Mar 27, 2023 |
| ASRock        | FM2A88X+ Killer             | [6180e562dd](https://linux-hardware.org/?probe=6180e562dd) | Mar 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [33608bbcda](https://linux-hardware.org/?probe=33608bbcda) | Mar 27, 2023 |
| Lenovo        | ThinkStation D30 42234T7    | [cfb8c9d396](https://linux-hardware.org/?probe=cfb8c9d396) | Mar 27, 2023 |
| ASRockRack    | D1541D4U-2T8R               | [012c10ae8c](https://linux-hardware.org/?probe=012c10ae8c) | Mar 27, 2023 |
| ASUSTek       | P8Z77-V LE                  | [b6a0d45508](https://linux-hardware.org/?probe=b6a0d45508) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [a4f4013e4e](https://linux-hardware.org/?probe=a4f4013e4e) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [af88fa64c6](https://linux-hardware.org/?probe=af88fa64c6) | Mar 26, 2023 |
| Dell          | 0HY9JP A00                  | [d1c982b241](https://linux-hardware.org/?probe=d1c982b241) | Mar 26, 2023 |
| HP            | 83E2                        | [00f64e69cd](https://linux-hardware.org/?probe=00f64e69cd) | Mar 26, 2023 |
| Medion        | TJ4125                      | [74b96baec4](https://linux-hardware.org/?probe=74b96baec4) | Mar 25, 2023 |
| HP            | 1497                        | [fb8706575a](https://linux-hardware.org/?probe=fb8706575a) | Mar 25, 2023 |
| MSI           | B450M PRO-VDH MAX           | [76338f95ea](https://linux-hardware.org/?probe=76338f95ea) | Mar 25, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [6e459078e7](https://linux-hardware.org/?probe=6e459078e7) | Mar 25, 2023 |
| HP            | 83E2                        | [cd40c6aa18](https://linux-hardware.org/?probe=cd40c6aa18) | Mar 25, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [b9d321c70e](https://linux-hardware.org/?probe=b9d321c70e) | Mar 25, 2023 |
| Dell          | 0PU052                      | [ccea2ad8e8](https://linux-hardware.org/?probe=ccea2ad8e8) | Mar 25, 2023 |
| Gigabyte      | Z690 AORUS PRO              | [9b8ddda3c3](https://linux-hardware.org/?probe=9b8ddda3c3) | Mar 24, 2023 |
| Gigabyte      | B550 AORUS MASTER           | [1f7c1bfa41](https://linux-hardware.org/?probe=1f7c1bfa41) | Mar 24, 2023 |
| AZW           | U59                         | [b4058b773d](https://linux-hardware.org/?probe=b4058b773d) | Mar 24, 2023 |
| ASRockRack    | E3C242D4U2-2T               | [05eb6d08bd](https://linux-hardware.org/?probe=05eb6d08bd) | Mar 23, 2023 |
| Dell          | 0J3C2F A02                  | [cb6e3973c8](https://linux-hardware.org/?probe=cb6e3973c8) | Mar 23, 2023 |
| HP            | 0A68h                       | [527cad6ad0](https://linux-hardware.org/?probe=527cad6ad0) | Mar 23, 2023 |
| Unknown       | Unknown                     | [ef5bf53c45](https://linux-hardware.org/?probe=ef5bf53c45) | Mar 22, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [e2fe65e540](https://linux-hardware.org/?probe=e2fe65e540) | Mar 22, 2023 |
| Dell          | 0HHV7N A00                  | [7b10e71784](https://linux-hardware.org/?probe=7b10e71784) | Mar 22, 2023 |
| Unknown       | Unknown                     | [b96104604a](https://linux-hardware.org/?probe=b96104604a) | Mar 22, 2023 |
| HP            | 3048h                       | [5163f9de22](https://linux-hardware.org/?probe=5163f9de22) | Mar 22, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [57a69bcf57](https://linux-hardware.org/?probe=57a69bcf57) | Mar 21, 2023 |
| Gigabyte      | EX38-DS4                    | [6dd3e18637](https://linux-hardware.org/?probe=6dd3e18637) | Mar 21, 2023 |
| Gigabyte      | Z77X-UD3H                   | [3b06195ff0](https://linux-hardware.org/?probe=3b06195ff0) | Mar 21, 2023 |
| Google        | Teemo                       | [3e60b11752](https://linux-hardware.org/?probe=3e60b11752) | Mar 21, 2023 |
| Supermicro    | X10DRi-T4+                  | [3aa5aebaee](https://linux-hardware.org/?probe=3aa5aebaee) | Mar 20, 2023 |
| HP            | 1825                        | [73a2e18f3a](https://linux-hardware.org/?probe=73a2e18f3a) | Mar 20, 2023 |
| Techvision    | TVI7309X B0                 | [67b681a703](https://linux-hardware.org/?probe=67b681a703) | Mar 20, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [1a21f25ce5](https://linux-hardware.org/?probe=1a21f25ce5) | Mar 20, 2023 |
| ASUSTek       | A88X-PRO                    | [ea415770cb](https://linux-hardware.org/?probe=ea415770cb) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [b5d9053f1c](https://linux-hardware.org/?probe=b5d9053f1c) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [660ae0f7ed](https://linux-hardware.org/?probe=660ae0f7ed) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE            | [d7b27c1822](https://linux-hardware.org/?probe=d7b27c1822) | Mar 19, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [5308592de8](https://linux-hardware.org/?probe=5308592de8) | Mar 19, 2023 |
| Intel         | 945GCT-M                    | [ac83eeefb9](https://linux-hardware.org/?probe=ac83eeefb9) | Mar 19, 2023 |
| ASRock        | Z590M-ITX/ax                | [715b1e5c6b](https://linux-hardware.org/?probe=715b1e5c6b) | Mar 18, 2023 |
| Medion        | TJ4125                      | [6895b929a4](https://linux-hardware.org/?probe=6895b929a4) | Mar 18, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1e96b578fa](https://linux-hardware.org/?probe=1e96b578fa) | Mar 18, 2023 |
| Gigabyte      | Q270M-D3H                   | [b244f2a8fd](https://linux-hardware.org/?probe=b244f2a8fd) | Mar 18, 2023 |
| ASRock        | X570 PG Velocita            | [bc3f2240b9](https://linux-hardware.org/?probe=bc3f2240b9) | Mar 18, 2023 |
| Fujitsu       | D3601-A1 S26361-D3601-A1    | [ec47c2dcb7](https://linux-hardware.org/?probe=ec47c2dcb7) | Mar 18, 2023 |
| Lenovo        | ThinkServer TS440           | [f34d8572e9](https://linux-hardware.org/?probe=f34d8572e9) | Mar 18, 2023 |
| HP            | 198E                        | [23e214216d](https://linux-hardware.org/?probe=23e214216d) | Mar 17, 2023 |
| HP            | 198E                        | [d5d5af66a8](https://linux-hardware.org/?probe=d5d5af66a8) | Mar 17, 2023 |
| Dell          | PowerEdge M620              | [c628cb7f90](https://linux-hardware.org/?probe=c628cb7f90) | Mar 17, 2023 |
| MSI           | MPG Z690 EDGE TI WIFI DD... | [b42850eb13](https://linux-hardware.org/?probe=b42850eb13) | Mar 17, 2023 |
| Gigabyte      | AX370-Gaming 5              | [97d434b3b5](https://linux-hardware.org/?probe=97d434b3b5) | Mar 16, 2023 |
| Gigabyte      | AX370-Gaming 5              | [dd101b4b05](https://linux-hardware.org/?probe=dd101b4b05) | Mar 16, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | [0b9755873a](https://linux-hardware.org/?probe=0b9755873a) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [4e61f760cb](https://linux-hardware.org/?probe=4e61f760cb) | Mar 16, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [b7671cbae5](https://linux-hardware.org/?probe=b7671cbae5) | Mar 16, 2023 |
| Gigabyte      | Q270M-D3H                   | [8841b23ef7](https://linux-hardware.org/?probe=8841b23ef7) | Mar 16, 2023 |
| ASRock        | X570 PG Velocita            | [bd8bc5740e](https://linux-hardware.org/?probe=bd8bc5740e) | Mar 16, 2023 |
| ASRock        | B450M Pro4                  | [108d237ebe](https://linux-hardware.org/?probe=108d237ebe) | Mar 16, 2023 |
| Gigabyte      | Z77X-UD3H                   | [a22bba0e53](https://linux-hardware.org/?probe=a22bba0e53) | Mar 15, 2023 |
| Cincoze       | P1101.01.001                | [9443379d5e](https://linux-hardware.org/?probe=9443379d5e) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | [2d3c739ac5](https://linux-hardware.org/?probe=2d3c739ac5) | Mar 15, 2023 |
| iEi           | SAT3 V1.03                  | [f6f29a0f8a](https://linux-hardware.org/?probe=f6f29a0f8a) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | [ea280402ca](https://linux-hardware.org/?probe=ea280402ca) | Mar 15, 2023 |
| ASUSTek       | B85M-G                      | [513385d981](https://linux-hardware.org/?probe=513385d981) | Mar 15, 2023 |
| Gigabyte      | B450M DS3H V2               | [b952483e9a](https://linux-hardware.org/?probe=b952483e9a) | Mar 15, 2023 |
| HP            | 1495                        | [72769abb34](https://linux-hardware.org/?probe=72769abb34) | Mar 15, 2023 |
| Gigabyte      | H97M-HD3                    | [6831505433](https://linux-hardware.org/?probe=6831505433) | Mar 14, 2023 |
| HP            | ProLiant SL4540 Gen8        | [fb493ce600](https://linux-hardware.org/?probe=fb493ce600) | Mar 14, 2023 |
| Intel         | D945GCPE AAD97209-201       | [7733f89d7d](https://linux-hardware.org/?probe=7733f89d7d) | Mar 14, 2023 |
| Unknown       | Unknown                     | [3c314ab1c2](https://linux-hardware.org/?probe=3c314ab1c2) | Mar 14, 2023 |
| Unknown       | Unknown                     | [eff328db22](https://linux-hardware.org/?probe=eff328db22) | Mar 14, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [9793c62af0](https://linux-hardware.org/?probe=9793c62af0) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [5545b43cf0](https://linux-hardware.org/?probe=5545b43cf0) | Mar 13, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [0211c6712f](https://linux-hardware.org/?probe=0211c6712f) | Mar 13, 2023 |
| Gigabyte      | H61M-DS2                    | [0cee087c15](https://linux-hardware.org/?probe=0cee087c15) | Mar 13, 2023 |
| Gigabyte      | X570 UD                     | [839a069bc4](https://linux-hardware.org/?probe=839a069bc4) | Mar 13, 2023 |
| ASRock        | 970M Pro3                   | [a35e76c9bf](https://linux-hardware.org/?probe=a35e76c9bf) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | [881e48f258](https://linux-hardware.org/?probe=881e48f258) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | [6ddc564b5d](https://linux-hardware.org/?probe=6ddc564b5d) | Mar 12, 2023 |
| HP            | 1825                        | [85011ed37d](https://linux-hardware.org/?probe=85011ed37d) | Mar 12, 2023 |
| Medion        | TJ4125                      | [5b8893bf40](https://linux-hardware.org/?probe=5b8893bf40) | Mar 12, 2023 |
| ASRock        | B450 Pro4                   | [4dd7be5be9](https://linux-hardware.org/?probe=4dd7be5be9) | Mar 12, 2023 |
| Medion        | TJ4125                      | [a93f645a7b](https://linux-hardware.org/?probe=a93f645a7b) | Mar 11, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [c91efb0de0](https://linux-hardware.org/?probe=c91efb0de0) | Mar 11, 2023 |
| MSI           | MS-B1831                    | [a9bfb4f294](https://linux-hardware.org/?probe=a9bfb4f294) | Mar 11, 2023 |
| ASRock        | 970M Pro3                   | [988d270005](https://linux-hardware.org/?probe=988d270005) | Mar 11, 2023 |
| ASRock        | B660M-STX                   | [2d0fdf6553](https://linux-hardware.org/?probe=2d0fdf6553) | Mar 11, 2023 |
| ASRock        | B660M-STX                   | [34a92205b4](https://linux-hardware.org/?probe=34a92205b4) | Mar 11, 2023 |
| MSI           | B560M PRO-VDH WIFI [CEC]    | [eff63861e7](https://linux-hardware.org/?probe=eff63861e7) | Mar 11, 2023 |
| ASRock        | Z790 Taichi Carrara         | [629adaf380](https://linux-hardware.org/?probe=629adaf380) | Mar 11, 2023 |
| Dell          | 01XK1W A00                  | [f8e050789f](https://linux-hardware.org/?probe=f8e050789f) | Mar 11, 2023 |
| ASUSTek       | AT3N7A-I                    | [59de62aac5](https://linux-hardware.org/?probe=59de62aac5) | Mar 11, 2023 |
| Gigabyte      | Z77X-UD3H                   | [823c3530a1](https://linux-hardware.org/?probe=823c3530a1) | Mar 10, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [35ab0f32c5](https://linux-hardware.org/?probe=35ab0f32c5) | Mar 10, 2023 |
| GoWin Solu... | R86S                        | [495614211e](https://linux-hardware.org/?probe=495614211e) | Mar 09, 2023 |
| ASRock        | G31M-VS2                    | [c098fa3ee0](https://linux-hardware.org/?probe=c098fa3ee0) | Mar 09, 2023 |
| AZW           | MINI S                      | [e304668a70](https://linux-hardware.org/?probe=e304668a70) | Mar 09, 2023 |
| ASRock        | 990FX Killer                | [326cdc81b2](https://linux-hardware.org/?probe=326cdc81b2) | Mar 09, 2023 |
| ASUSTek       | P5G41T-M LX                 | [4f55573ba6](https://linux-hardware.org/?probe=4f55573ba6) | Mar 08, 2023 |
| Intel         | JSL MRD                     | [ac75dbf1f6](https://linux-hardware.org/?probe=ac75dbf1f6) | Mar 08, 2023 |
| HP            | 0AACh                       | [2f4ba72670](https://linux-hardware.org/?probe=2f4ba72670) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [69dd85d8cf](https://linux-hardware.org/?probe=69dd85d8cf) | Mar 07, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [ced1079ce2](https://linux-hardware.org/?probe=ced1079ce2) | Mar 07, 2023 |
| ASRock        | B450M-HDV                   | [cca3440ed3](https://linux-hardware.org/?probe=cca3440ed3) | Mar 07, 2023 |
| MSI           | 880GM-E43                   | [f4027fb865](https://linux-hardware.org/?probe=f4027fb865) | Mar 07, 2023 |
| Gigabyte      | B360M DS3H                  | [5a1521197e](https://linux-hardware.org/?probe=5a1521197e) | Mar 07, 2023 |
| Dell          | 0F5C5X A00                  | [5f0ab2a253](https://linux-hardware.org/?probe=5f0ab2a253) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [a0bccf2d2b](https://linux-hardware.org/?probe=a0bccf2d2b) | Mar 06, 2023 |
| HP            | ProLiant MicroServer Gen... | [ae0bbd2f73](https://linux-hardware.org/?probe=ae0bbd2f73) | Mar 06, 2023 |
| ASRock        | B450M Pro4 R2.0             | [31376d711e](https://linux-hardware.org/?probe=31376d711e) | Mar 06, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [2f63b318f6](https://linux-hardware.org/?probe=2f63b318f6) | Mar 06, 2023 |
| Gigabyte      | Z68X-UD3-B3                 | [f2be73745e](https://linux-hardware.org/?probe=f2be73745e) | Mar 06, 2023 |
| AZW           | MINI S                      | [cb0b08973d](https://linux-hardware.org/?probe=cb0b08973d) | Mar 06, 2023 |
| ASRock        | 990FX Extreme4              | [641d1c6a8f](https://linux-hardware.org/?probe=641d1c6a8f) | Mar 05, 2023 |
| Unknown       | i855-W83627HF               | [e60d4877f4](https://linux-hardware.org/?probe=e60d4877f4) | Mar 04, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | [a9c39c2b82](https://linux-hardware.org/?probe=a9c39c2b82) | Mar 04, 2023 |
| MSI           | B250M MORTAR                | [a4e8543fe2](https://linux-hardware.org/?probe=a4e8543fe2) | Mar 03, 2023 |
| ASUSTek       | P5KPL-AM                    | [7471275fc7](https://linux-hardware.org/?probe=7471275fc7) | Mar 03, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [31fc7e49b2](https://linux-hardware.org/?probe=31fc7e49b2) | Mar 03, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [7adf1c211e](https://linux-hardware.org/?probe=7adf1c211e) | Mar 03, 2023 |
| Win elemen... | M600                        | [36ce350e0c](https://linux-hardware.org/?probe=36ce350e0c) | Mar 03, 2023 |
| Dell          | 0D6H9T A02                  | [0027e59622](https://linux-hardware.org/?probe=0027e59622) | Mar 02, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8f61a5507b](https://linux-hardware.org/?probe=8f61a5507b) | Mar 02, 2023 |
| AMI           | Intel                       | [b6d932a0ed](https://linux-hardware.org/?probe=b6d932a0ed) | Mar 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | [0e66878368](https://linux-hardware.org/?probe=0e66878368) | Mar 02, 2023 |
| ASRockRack    | B450D4U-V1L                 | [93e91a76bf](https://linux-hardware.org/?probe=93e91a76bf) | Mar 02, 2023 |
| ASRockRack    | B450D4U-V1L                 | [1774000cc4](https://linux-hardware.org/?probe=1774000cc4) | Mar 02, 2023 |
| HPE           | ProLiant MicroServer Gen... | [11c1bf8316](https://linux-hardware.org/?probe=11c1bf8316) | Mar 02, 2023 |
| ECS           | G31T-M9                     | [88447490cb](https://linux-hardware.org/?probe=88447490cb) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [977be97551](https://linux-hardware.org/?probe=977be97551) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [2191c9e96a](https://linux-hardware.org/?probe=2191c9e96a) | Mar 02, 2023 |
| Supermicro    | X9DR3-F                     | [5b8c79ac33](https://linux-hardware.org/?probe=5b8c79ac33) | Mar 02, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Desktops | Percent |
|------------------------|----------|---------|
| 5.10.0-7-amd64         | 515      | 17.29%  |
| 5.10.0-8-amd64         | 230      | 7.72%   |
| 5.10.0-21-amd64        | 179      | 6.01%   |
| 5.10.0-9-amd64         | 121      | 4.06%   |
| 5.10.0-2-amd64         | 115      | 3.86%   |
| 5.10.0-20-amd64        | 108      | 3.63%   |
| 5.10.0-19-amd64        | 105      | 3.52%   |
| 5.10.0-23-amd64        | 95       | 3.19%   |
| 5.10.0-13-amd64        | 88       | 2.95%   |
| 5.10.0-18-amd64        | 84       | 2.82%   |
| 5.10.0-10-amd64        | 75       | 2.52%   |
| 5.10.0-11-amd64        | 73       | 2.45%   |
| 5.10.0-16-amd64        | 69       | 2.32%   |
| 5.10.0-14-amd64        | 51       | 1.71%   |
| 5.10.0-15-amd64        | 45       | 1.51%   |
| 5.10.0-22-amd64        | 44       | 1.48%   |
| 5.10.0-17-amd64        | 43       | 1.44%   |
| 5.10.0-26-amd64        | 31       | 1.04%   |
| 5.10.0-12-amd64        | 29       | 0.97%   |
| 5.10.0-33-amd64        | 23       | 0.77%   |
| 5.10.0-32-amd64        | 23       | 0.77%   |
| 5.10.0-25-amd64        | 23       | 0.77%   |
| 5.16.0-0.bpo.4-amd64   | 20       | 0.67%   |
| 5.15.102-1-pve         | 20       | 0.67%   |
| 5.15.0-2-amd64         | 20       | 0.67%   |
| 5.10.0-28-amd64        | 20       | 0.67%   |
| 6.0.0-0.deb11.6-amd64  | 19       | 0.64%   |
| 5.13.19-6-pve          | 18       | 0.6%    |
| 5.18.0-0.bpo.1-amd64   | 16       | 0.54%   |
| 5.10.0-27-amd64        | 16       | 0.54%   |
| 6.1.0-0.deb11.7-amd64  | 14       | 0.47%   |
| 5.18.0-0.deb11.4-amd64 | 14       | 0.47%   |
| 5.15.83-1-pve          | 14       | 0.47%   |
| 5.13.19-2-pve          | 14       | 0.47%   |
| 5.10.0-6-amd64         | 14       | 0.47%   |
| 5.15.30-2-pve          | 13       | 0.44%   |
| 5.15.85-1-pve          | 12       | 0.4%    |
| 5.15.74-1-pve          | 12       | 0.4%    |
| 5.15.107-2-pve         | 12       | 0.4%    |
| 5.15.53-1-pve          | 11       | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10.0   | 2192     | 77.87%  |
| 6.1.0    | 58       | 2.06%   |
| 5.13.19  | 44       | 1.56%   |
| 5.18.0   | 43       | 1.53%   |
| 6.0.0    | 39       | 1.39%   |
| 5.15.0   | 35       | 1.24%   |
| 5.16.0   | 31       | 1.1%    |
| 5.19.0   | 21       | 0.75%   |
| 5.15.107 | 20       | 0.71%   |
| 5.15.102 | 20       | 0.71%   |
| 5.14.0   | 18       | 0.64%   |
| 5.11.22  | 17       | 0.6%    |
| 5.15.83  | 14       | 0.5%    |
| 5.15.39  | 13       | 0.46%   |
| 5.15.35  | 13       | 0.46%   |
| 5.15.30  | 13       | 0.46%   |
| 5.15.85  | 12       | 0.43%   |
| 5.15.74  | 12       | 0.43%   |
| 5.15.53  | 11       | 0.39%   |
| 5.17.0   | 10       | 0.36%   |
| 5.15.108 | 8        | 0.28%   |
| 5.15.104 | 8        | 0.28%   |
| 5.19.17  | 6        | 0.21%   |
| 5.15.126 | 6        | 0.21%   |
| 6.2.6    | 5        | 0.18%   |
| 6.1.15   | 5        | 0.18%   |
| 5.15.158 | 5        | 0.18%   |
| 5.15.131 | 5        | 0.18%   |
| 5.15.116 | 5        | 0.18%   |
| 6.2.9    | 4        | 0.14%   |
| 6.2.11   | 4        | 0.14%   |
| 6.0.8    | 4        | 0.14%   |
| 5.15.60  | 4        | 0.14%   |
| 5.13.0   | 4        | 0.14%   |
| 5.16.5   | 3        | 0.11%   |
| 5.15.79  | 3        | 0.11%   |
| 5.15.143 | 3        | 0.11%   |
| 5.10.57  | 3        | 0.11%   |
| 4.19.0   | 3        | 0.11%   |
| 6.1.12   | 2        | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.10     | 2214     | 79.41%  |
| 5.15     | 202      | 7.25%   |
| 6.1      | 68       | 2.44%   |
| 5.13     | 54       | 1.94%   |
| 6.0      | 49       | 1.76%   |
| 5.18     | 47       | 1.69%   |
| 5.16     | 37       | 1.33%   |
| 5.19     | 30       | 1.08%   |
| 5.11     | 20       | 0.72%   |
| 5.14     | 19       | 0.68%   |
| 6.2      | 17       | 0.61%   |
| 5.17     | 12       | 0.43%   |
| 6.3      | 3        | 0.11%   |
| 5.4      | 3        | 0.11%   |
| 4.19     | 3        | 0.11%   |
| 6.9      | 1        | 0.04%   |
| 6.6      | 1        | 0.04%   |
| 6.5      | 1        | 0.04%   |
| 6.12     | 1        | 0.04%   |
| 6.10     | 1        | 0.04%   |
| 5.8      | 1        | 0.04%   |
| 5.5      | 1        | 0.04%   |
| 5.12     | 1        | 0.04%   |
| 5.10.164 | 1        | 0.04%   |
| 5.1      | 1        | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| x86_64  | 2651     | 97.39%  |
| i686    | 65       | 2.39%   |
| riscv64 | 4        | 0.15%   |
| i586    | 1        | 0.04%   |
| armv7l  | 1        | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| Unknown           | 1120     | 40.61%  |
| GNOME             | 527      | 19.11%  |
| XFCE              | 310      | 11.24%  |
| KDE5              | 277      | 10.04%  |
| MATE              | 125      | 4.53%   |
| X-Cinnamon        | 93       | 3.37%   |
| LXDE              | 80       | 2.9%    |
| Cinnamon          | 64       | 2.32%   |
| LXQt              | 38       | 1.38%   |
| i3                | 25       | 0.91%   |
| Openbox           | 18       | 0.65%   |
| KDE               | 16       | 0.58%   |
| trinity           | 13       | 0.47%   |
| GNOME Flashback   | 12       | 0.44%   |
| lightdm-xsession  | 11       | 0.4%    |
| Budgie            | 10       | 0.36%   |
| GNOME Classic     | 5        | 0.18%   |
| sway              | 3        | 0.11%   |
| awesome           | 3        | 0.11%   |
| UKUI              | 1        | 0.04%   |
| icewm             | 1        | 0.04%   |
| GNUstep           | 1        | 0.04%   |
| gnome-xorg        | 1        | 0.04%   |
| Enlightenment     | 1        | 0.04%   |
| e16-session       | 1        | 0.04%   |
| DWM               | 1        | 0.04%   |
| /etc/X11/Xsession | 1        | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 1268     | 46.01%  |
| Unknown     | 711      | 25.8%   |
| Tty         | 504      | 18.29%  |
| Wayland     | 268      | 9.72%   |
| Web         | 3        | 0.11%   |
| Unspecified | 2        | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1423     | 51.9%   |
| LightDM | 537      | 19.58%  |
| GDM     | 396      | 14.44%  |
| SDDM    | 237      | 8.64%   |
| TDM     | 73       | 2.66%   |
| GDM3    | 52       | 1.9%    |
| SLiM    | 9        | 0.33%   |
| XDM     | 6        | 0.22%   |
| NODM    | 5        | 0.18%   |
| LXDM    | 2        | 0.07%   |
| WDM     | 1        | 0.04%   |
| SU      | 1        | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 994      | 36.33%  |
| ru_RU   | 677      | 24.74%  |
| de_DE   | 156      | 5.7%    |
| fr_FR   | 145      | 5.3%    |
| en_GB   | 111      | 4.06%   |
| es_ES   | 81       | 2.96%   |
| pt_BR   | 60       | 2.19%   |
| Unknown | 57       | 2.08%   |
| it_IT   | 53       | 1.94%   |
| C       | 38       | 1.39%   |
| en_CA   | 37       | 1.35%   |
| en_AU   | 35       | 1.28%   |
| pl_PL   | 29       | 1.06%   |
| es_MX   | 16       | 0.58%   |
| es_AR   | 15       | 0.55%   |
| en_IE   | 15       | 0.55%   |
| hu_HU   | 14       | 0.51%   |
| ja_JP   | 13       | 0.48%   |
| es_VE   | 13       | 0.48%   |
| zh_CN   | 12       | 0.44%   |
| en_IN   | 10       | 0.37%   |
| de_AT   | 9        | 0.33%   |
| nl_BE   | 8        | 0.29%   |
| nl_NL   | 7        | 0.26%   |
| en_NZ   | 7        | 0.26%   |
| ca_ES   | 7        | 0.26%   |
| pt_PT   | 6        | 0.22%   |
| de_CH   | 6        | 0.22%   |
| sv_SE   | 5        | 0.18%   |
| en_ZA   | 5        | 0.18%   |
| en_HK   | 5        | 0.18%   |
| uk_UA   | 4        | 0.15%   |
| tr_TR   | 4        | 0.15%   |
| fr_BE   | 4        | 0.15%   |
| es_PE   | 4        | 0.15%   |
| cs_CZ   | 4        | 0.15%   |
| ru_UA   | 3        | 0.11%   |
| hr_HR   | 3        | 0.11%   |
| fr_CH   | 3        | 0.11%   |
| fr_CA   | 3        | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1662     | 60.22%  |
| EFI  | 1098     | 39.78%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 1816     | 66.37%  |
| Overlay | 678      | 24.78%  |
| Btrfs   | 92       | 3.36%   |
| Zfs     | 75       | 2.74%   |
| Xfs     | 39       | 1.43%   |
| Ext3    | 15       | 0.55%   |
| Tmpfs   | 11       | 0.4%    |
| Ext2    | 4        | 0.15%   |
| Unknown | 4        | 0.15%   |
| Rootfs  | 1        | 0.04%   |
| Aufs    | 1        | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 1363     | 49.46%  |
| MBR     | 1036     | 37.59%  |
| Unknown | 357      | 12.95%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2223     | 80.92%  |
| Yes       | 524      | 19.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1617     | 58.91%  |
| Yes       | 1128     | 41.09%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 706      | 25.95%  |
| Gigabyte Technology                  | 439      | 16.13%  |
| MSI                                  | 275      | 10.11%  |
| ASRock                               | 260      | 9.56%   |
| Dell                                 | 196      | 7.2%    |
| Hewlett-Packard                      | 180      | 6.62%   |
| Intel                                | 93       | 3.42%   |
| Lenovo                               | 88       | 3.23%   |
| Unknown                              | 57       | 2.09%   |
| ECS                                  | 49       | 1.8%    |
| Fujitsu                              | 36       | 1.32%   |
| AZW                                  | 31       | 1.14%   |
| ASRockRack                           | 31       | 1.14%   |
| Foxconn                              | 28       | 1.03%   |
| Acer                                 | 22       | 0.81%   |
| Supermicro                           | 19       | 0.7%    |
| Pegatron                             | 15       | 0.55%   |
| Biostar                              | 13       | 0.48%   |
| Inventec                             | 12       | 0.44%   |
| BESSTAR Tech                         | 10       | 0.37%   |
| IceWhale Technology                  | 9        | 0.33%   |
| Huanan                               | 8        | 0.29%   |
| Medion                               | 7        | 0.26%   |
| Shuttle                              | 6        | 0.22%   |
| Google                               | 6        | 0.22%   |
| Apple                                | 5        | 0.18%   |
| Shenzhen Meigao Electronic Equipment | 4        | 0.15%   |
| Positivo                             | 4        | 0.15%   |
| HPE                                  | 4        | 0.15%   |
| Fujitsu Siemens                      | 4        | 0.15%   |
| AMI                                  | 4        | 0.15%   |
| Techvision                           | 3        | 0.11%   |
| Packard Bell                         | 3        | 0.11%   |
| Hardkernel                           | 3        | 0.11%   |
| Aquarius                             | 3        | 0.11%   |
| AAEON                                | 3        | 0.11%   |
| Thecus                               | 2        | 0.07%   |
| Semp Toshiba                         | 2        | 0.07%   |
| Seeed Studio                         | 2        | 0.07%   |
| Phoenix Contact                      | 2        | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 87       | 3.2%    |
| Unknown                      | 58       | 2.13%   |
| ASUS S20 K29                 | 55       | 2.02%   |
| MSI MS-7996                  | 39       | 1.43%   |
| MSI MS-7817                  | 22       | 0.81%   |
| ECS G31T-M9                  | 22       | 0.81%   |
| ASRock H470M-HVS             | 20       | 0.74%   |
| Gigabyte H81M-S2V            | 18       | 0.66%   |
| ASUS PRIME H510M-A           | 17       | 0.62%   |
| Gigabyte H410M S2H           | 16       | 0.59%   |
| ECS H61H2-M13                | 16       | 0.59%   |
| Dell OptiPlex 7010           | 16       | 0.59%   |
| ASUS P8H61-M LX3 R2.0        | 15       | 0.55%   |
| AZW MINI S                   | 13       | 0.48%   |
| AZW U59                      | 12       | 0.44%   |
| ASUS PRIME A320M-K           | 12       | 0.44%   |
| Gigabyte B450M DS3H          | 11       | 0.4%    |
| HP ProLiant MicroServer Gen8 | 10       | 0.37%   |
| ASUS TUF Gaming X570-PLUS    | 10       | 0.37%   |
| ASUS PRIME B450M-A           | 10       | 0.37%   |
| ASUS P8H67-M                 | 10       | 0.37%   |
| ASUS H110M-R                 | 10       | 0.37%   |
| ASRock B450M Pro4            | 10       | 0.37%   |
| HP Z420 Workstation          | 9        | 0.33%   |
| Dell OptiPlex 9020           | 9        | 0.33%   |
| Dell OptiPlex 790            | 9        | 0.33%   |
| HP Compaq Elite 8300 SFF     | 8        | 0.29%   |
| Gigabyte B360M H             | 8        | 0.29%   |
| ASRock H61M-VG4              | 8        | 0.29%   |
| ASRock G31M-VS2              | 8        | 0.29%   |
| MSI MS-7C91                  | 7        | 0.26%   |
| MSI MS-7C56                  | 7        | 0.26%   |
| MSI MS-7C02                  | 7        | 0.26%   |
| Inventec D CLASS             | 7        | 0.26%   |
| Gigabyte P85-D3              | 7        | 0.26%   |
| Gigabyte GA-78LMT-USB3       | 7        | 0.26%   |
| Gigabyte A320M-S2H           | 7        | 0.26%   |
| Fujitsu ESPRIMO P720         | 7        | 0.26%   |
| ASUS P8H61-M LX3 PLUS R2.0   | 7        | 0.26%   |
| ASUS P5G41T-M LE             | 7        | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 152      | 5.59%   |
| Dell OptiPlex          | 105      | 3.86%   |
| ASUS All               | 87       | 3.2%    |
| Unknown                | 58       | 2.13%   |
| ASUS S20               | 55       | 2.02%   |
| Lenovo ThinkCentre     | 53       | 1.95%   |
| HP Compaq              | 50       | 1.84%   |
| ASUS ROG               | 48       | 1.76%   |
| ASUS TUF               | 45       | 1.65%   |
| Dell Precision         | 44       | 1.62%   |
| MSI MS-7996            | 39       | 1.43%   |
| ASUS P8H61-M           | 33       | 1.21%   |
| HP EliteDesk           | 26       | 0.96%   |
| Gigabyte B450M         | 25       | 0.92%   |
| Fujitsu ESPRIMO        | 23       | 0.85%   |
| MSI MS-7817            | 22       | 0.81%   |
| HP ProLiant            | 22       | 0.81%   |
| ECS G31T-M9            | 22       | 0.81%   |
| ASUS PRO               | 22       | 0.81%   |
| Gigabyte H410M         | 21       | 0.77%   |
| ASRock H470M-HVS       | 20       | 0.74%   |
| Gigabyte H81M-S2V      | 18       | 0.66%   |
| ASRock B450M           | 17       | 0.62%   |
| ECS H61H2-M13          | 16       | 0.59%   |
| Lenovo ThinkStation    | 15       | 0.55%   |
| Gigabyte X570          | 15       | 0.55%   |
| ASUS M5A97             | 15       | 0.55%   |
| ASRock B450            | 15       | 0.55%   |
| Gigabyte B550          | 14       | 0.51%   |
| HP ProDesk             | 13       | 0.48%   |
| Dell XPS               | 13       | 0.48%   |
| Dell Inspiron          | 13       | 0.48%   |
| AZW MINI               | 13       | 0.48%   |
| AZW U59                | 12       | 0.44%   |
| ASUS P8H67-M           | 12       | 0.44%   |
| ASUS P5G41T-M          | 12       | 0.44%   |
| Acer Aspire            | 12       | 0.44%   |
| Gigabyte GA-78LMT-USB3 | 11       | 0.4%    |
| Gigabyte B550M         | 10       | 0.37%   |
| Dell Vostro            | 10       | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 280      | 10.29%  |
| 2020    | 271      | 9.96%   |
| 2021    | 238      | 8.75%   |
| 2013    | 232      | 8.53%   |
| 2018    | 230      | 8.45%   |
| 2011    | 167      | 6.14%   |
| 2019    | 162      | 5.95%   |
| 2014    | 150      | 5.51%   |
| 2009    | 132      | 4.85%   |
| 2015    | 128      | 4.7%    |
| 2022    | 127      | 4.67%   |
| 2010    | 124      | 4.56%   |
| 2017    | 120      | 4.41%   |
| 2016    | 107      | 3.93%   |
| 2008    | 90       | 3.31%   |
| 2007    | 64       | 2.35%   |
| 2006    | 27       | 0.99%   |
| 2023    | 26       | 0.96%   |
| 2005    | 19       | 0.7%    |
| 2024    | 7        | 0.26%   |
| 2004    | 6        | 0.22%   |
| 2003    | 6        | 0.22%   |
| 2001    | 3        | 0.11%   |
| Unknown | 3        | 0.11%   |
| 2025    | 1        | 0.04%   |
| 2000    | 1        | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2721     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 2677     | 98.13%  |
| Enabled  | 51       | 1.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2708     | 99.52%  |
| Yes  | 13       | 0.48%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 544      | 19.73%  |
| 4.01-8.0        | 503      | 18.24%  |
| 3.01-4.0        | 423      | 15.34%  |
| 8.01-16.0       | 394      | 14.29%  |
| 32.01-64.0      | 367      | 13.31%  |
| 64.01-256.0     | 247      | 8.96%   |
| 1.01-2.0        | 127      | 4.61%   |
| 24.01-32.0      | 67       | 2.43%   |
| 2.01-3.0        | 48       | 1.74%   |
| 0.51-1.0        | 19       | 0.69%   |
| More than 256.0 | 10       | 0.36%   |
| 0.01-0.5        | 8        | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Desktops | Percent |
|-----------------|----------|---------|
| 0.51-1.0        | 789      | 27.24%  |
| 1.01-2.0        | 582      | 20.1%   |
| 2.01-3.0        | 421      | 14.54%  |
| 4.01-8.0        | 372      | 12.85%  |
| 3.01-4.0        | 278      | 9.6%    |
| 8.01-16.0       | 165      | 5.7%    |
| 0.01-0.5        | 124      | 4.28%   |
| 16.01-24.0      | 66       | 2.28%   |
| 32.01-64.0      | 52       | 1.8%    |
| 24.01-32.0      | 31       | 1.07%   |
| 64.01-256.0     | 15       | 0.52%   |
| More than 256.0 | 1        | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1337     | 47.82%  |
| 2      | 585      | 20.92%  |
| 3      | 332      | 11.87%  |
| 4      | 227      | 8.12%   |
| 5      | 109      | 3.9%    |
| 6      | 71       | 2.54%   |
| 7      | 38       | 1.36%   |
| 8      | 29       | 1.04%   |
| 9      | 15       | 0.54%   |
| 0      | 15       | 0.54%   |
| 10     | 9        | 0.32%   |
| 12     | 6        | 0.21%   |
| 13     | 5        | 0.18%   |
| 11     | 5        | 0.18%   |
| 19     | 2        | 0.07%   |
| 18     | 2        | 0.07%   |
| 16     | 2        | 0.07%   |
| 14     | 2        | 0.07%   |
| 29     | 1        | 0.04%   |
| 28     | 1        | 0.04%   |
| 27     | 1        | 0.04%   |
| 22     | 1        | 0.04%   |
| 21     | 1        | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1832     | 66.93%  |
| Yes       | 905      | 33.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2705     | 99.41%  |
| No        | 16       | 0.59%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1918     | 70.13%  |
| Yes       | 817      | 29.87%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2093     | 76.55%  |
| Yes       | 641      | 23.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| Russia       | 723      | 26.54%  |
| USA          | 407      | 14.94%  |
| Germany      | 259      | 9.51%   |
| France       | 179      | 6.57%   |
| Spain        | 110      | 4.04%   |
| Brazil       | 83       | 3.05%   |
| Italy        | 80       | 2.94%   |
| UK           | 78       | 2.86%   |
| Canada       | 66       | 2.42%   |
| Poland       | 54       | 1.98%   |
| Australia    | 52       | 1.91%   |
| Netherlands  | 43       | 1.58%   |
| Argentina    | 32       | 1.17%   |
| Mexico       | 29       | 1.06%   |
| Austria      | 26       | 0.95%   |
| Switzerland  | 25       | 0.92%   |
| Belgium      | 24       | 0.88%   |
| China        | 23       | 0.84%   |
| Ukraine      | 22       | 0.81%   |
| Hungary      | 22       | 0.81%   |
| Malaysia     | 18       | 0.66%   |
| Czechia      | 18       | 0.66%   |
| Bulgaria     | 18       | 0.66%   |
| Sweden       | 17       | 0.62%   |
| Portugal     | 17       | 0.62%   |
| Japan        | 16       | 0.59%   |
| India        | 16       | 0.59%   |
| Venezuela    | 15       | 0.55%   |
| Norway       | 15       | 0.55%   |
| Finland      | 15       | 0.55%   |
| Romania      | 13       | 0.48%   |
| Hong Kong    | 11       | 0.4%    |
| Taiwan       | 10       | 0.37%   |
| Turkey       | 9        | 0.33%   |
| Ireland      | 9        | 0.33%   |
| Denmark      | 9        | 0.33%   |
| New Zealand  | 8        | 0.29%   |
| Kazakhstan   | 8        | 0.29%   |
| Belarus      | 8        | 0.29%   |
| South Africa | 7        | 0.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Voronezh          | 570      | 20.37%  |
| Moscow            | 43       | 1.54%   |
| St Petersburg     | 27       | 0.96%   |
| Paris             | 20       | 0.71%   |
| Vienna            | 19       | 0.68%   |
| Falkenstein       | 18       | 0.64%   |
| Seville           | 16       | 0.57%   |
| Barcelona         | 16       | 0.57%   |
| Kuala Lumpur      | 15       | 0.54%   |
| Berlin            | 14       | 0.5%    |
| Bangor            | 14       | 0.5%    |
| Sao Paulo         | 13       | 0.46%   |
| Warsaw            | 12       | 0.43%   |
| Melbourne         | 12       | 0.43%   |
| Munich            | 11       | 0.39%   |
| Buenos Aires      | 11       | 0.39%   |
| Sydney            | 10       | 0.36%   |
| Dover-Foxcroft    | 10       | 0.36%   |
| Amsterdam         | 10       | 0.36%   |
| Toronto           | 9        | 0.32%   |
| Sofia             | 9        | 0.32%   |
| Chicago           | 9        | 0.32%   |
| Brisbane          | 9        | 0.32%   |
| Milan             | 8        | 0.29%   |
| Madrid            | 8        | 0.29%   |
| London            | 8        | 0.29%   |
| Zurich            | 7        | 0.25%   |
| Yekaterinburg     | 7        | 0.25%   |
| Valencia          | 7        | 0.25%   |
| Stuttgart         | 7        | 0.25%   |
| Siegsdorf         | 7        | 0.25%   |
| San Jose          | 7        | 0.25%   |
| Nuremberg         | 7        | 0.25%   |
| New York          | 7        | 0.25%   |
| Las Vegas         | 7        | 0.25%   |
| Kyiv              | 7        | 0.25%   |
| Frankfurt am Main | 7        | 0.25%   |
| Cologne           | 7        | 0.25%   |
| Central           | 7        | 0.25%   |
| Stockholm         | 6        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 836      | 1555   | 17.89%  |
| WDC                         | 804      | 1472   | 17.2%   |
| Samsung Electronics         | 655      | 1038   | 14.01%  |
| Kingston                    | 351      | 468    | 7.51%   |
| Toshiba                     | 329      | 603    | 7.04%   |
| Crucial                     | 266      | 342    | 5.69%   |
| SanDisk                     | 157      | 207    | 3.36%   |
| Hitachi                     | 157      | 226    | 3.36%   |
| Intel                       | 86       | 117    | 1.84%   |
| China                       | 82       | 97     | 1.75%   |
| HGST                        | 78       | 136    | 1.67%   |
| A-DATA Technology           | 67       | 88     | 1.43%   |
| PNY                         | 47       | 93     | 1.01%   |
| Unknown                     | 46       | 83     | 0.98%   |
| SPCC                        | 44       | 50     | 0.94%   |
| Corsair                     | 30       | 46     | 0.64%   |
| Transcend                   | 27       | 28     | 0.58%   |
| Phison                      | 27       | 34     | 0.58%   |
| Netac                       | 27       | 86     | 0.58%   |
| Unknown                     | 27       | 29     | 0.58%   |
| Micron Technology           | 26       | 32     | 0.56%   |
| SK hynix                    | 25       | 53     | 0.53%   |
| Intenso                     | 24       | 34     | 0.51%   |
| Hewlett-Packard             | 24       | 41     | 0.51%   |
| Patriot                     | 23       | 30     | 0.49%   |
| Maxtor                      | 23       | 28     | 0.49%   |
| OCZ                         | 21       | 25     | 0.45%   |
| Gigabyte Technology         | 19       | 21     | 0.41%   |
| GOODRAM                     | 16       | 32     | 0.34%   |
| Apacer                      | 13       | 13     | 0.28%   |
| Team                        | 11       | 18     | 0.24%   |
| JMicron Technology          | 11       | 11     | 0.24%   |
| LITEON                      | 9        | 13     | 0.19%   |
| XPG                         | 8        | 9      | 0.17%   |
| Silicon Motion              | 8        | 11     | 0.17%   |
| Micron/Crucial Technology   | 8        | 10     | 0.17%   |
| Kingston Technology Company | 8        | 14     | 0.17%   |
| Plextor                     | 7        | 10     | 0.15%   |
| Mushkin                     | 7        | 9      | 0.15%   |
| KIOXIA                      | 7        | 9      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD  | 91       | 1.65%   |
| Seagate ST500DM002-1BD142 500GB  | 89       | 1.61%   |
| Crucial CT480BX500SSD1 480GB     | 70       | 1.27%   |
| Toshiba DT01ACA050 500GB         | 64       | 1.16%   |
| Seagate ST1000DM010-2EP102 1TB   | 59       | 1.07%   |
| Kingston SV300S37A120G 120GB SSD | 48       | 0.87%   |
| Kingston SA400S37480G 480GB SSD  | 46       | 0.83%   |
| Toshiba DT01ACA100 1TB           | 45       | 0.82%   |
| Samsung SSD 860 EVO 250GB        | 42       | 0.76%   |
| Seagate ST1000DM003-1ER162 1TB   | 37       | 0.67%   |
| Samsung SSD 860 EVO 500GB        | 37       | 0.67%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 36       | 0.65%   |
| Seagate ST2000DM008-2FR102 2TB   | 34       | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB         | 33       | 0.6%    |
| Samsung SSD 970 EVO Plus 1TB     | 33       | 0.6%    |
| Samsung SSD 860 EVO 1TB          | 33       | 0.6%    |
| Hitachi HDS721050CLA362 500GB    | 32       | 0.58%   |
| Crucial CT500MX500SSD1 500GB     | 32       | 0.58%   |
| Toshiba HDWD110 1TB              | 31       | 0.56%   |
| Seagate ST1000DM003-1CH162 1TB   | 31       | 0.56%   |
| Samsung SSD 970 EVO Plus 500GB   | 31       | 0.56%   |
| Crucial CT240BX500SSD1 240GB     | 29       | 0.53%   |
| Samsung SSD 850 EVO 250GB        | 28       | 0.51%   |
| Crucial CT1000MX500SSD1 1TB      | 27       | 0.49%   |
| Unknown                          | 27       | 0.49%   |
| Seagate ST4000DM004-2CV104 4TB   | 26       | 0.47%   |
| Samsung SSD 870 EVO 500GB        | 25       | 0.45%   |
| Samsung SSD 850 EVO 500GB        | 24       | 0.44%   |
| Kingston SA400S37120G 120GB SSD  | 24       | 0.44%   |
| Toshiba DT01ACA200 2TB           | 23       | 0.42%   |
| Samsung SSD 980 PRO 1TB          | 23       | 0.42%   |
| Seagate ST3500418AS 500GB        | 20       | 0.36%   |
| Seagate ST3250318AS 250GB        | 20       | 0.36%   |
| SanDisk NVMe SSD Drive 1TB       | 20       | 0.36%   |
| Samsung SSD 980 1TB              | 20       | 0.36%   |
| Netac SSD 240GB                  | 20       | 0.36%   |
| WDC WD40EFRX-68N32N0 4TB         | 18       | 0.33%   |
| Seagate ST250DM000-1BD141 250GB  | 18       | 0.33%   |
| Seagate ST1000DM003-1SB102 1TB   | 18       | 0.33%   |
| Toshiba DT01ACA300 3TB           | 17       | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 818      | 1499   | 36.78%  |
| WDC                 | 697      | 1296   | 31.34%  |
| Toshiba             | 306      | 559    | 13.76%  |
| Hitachi             | 157      | 226    | 7.06%   |
| Samsung Electronics | 82       | 106    | 3.69%   |
| HGST                | 76       | 133    | 3.42%   |
| Maxtor              | 22       | 27     | 0.99%   |
| Unknown             | 11       | 16     | 0.49%   |
| Hewlett-Packard     | 9        | 20     | 0.4%    |
| JMicron Technology  | 6        | 6      | 0.27%   |
| External            | 4        | 5      | 0.18%   |
| Intenso             | 3        | 3      | 0.13%   |
| Fujitsu             | 3        | 4      | 0.13%   |
| QNAP                | 2        | 3      | 0.09%   |
| IBM/Hitachi         | 2        | 2      | 0.09%   |
| HPE                 | 2        | 6      | 0.09%   |
| ASMT                | 2        | 3      | 0.09%   |
| Apple               | 2        | 2      | 0.09%   |
| WD MediaMax         | 1        | 6      | 0.04%   |
| Synology            | 1        | 1      | 0.04%   |
| StoreJet            | 1        | 1      | 0.04%   |
| SSK                 | 1        | 1      | 0.04%   |
| SD                  | 1        | 1      | 0.04%   |
| RSH-319             | 1        | 1      | 0.04%   |
| pqi                 | 1        | 1      | 0.04%   |
| NAS                 | 1        | 5      | 0.04%   |
| MaxDigital          | 1        | 4      | 0.04%   |
| MARSHAL             | 1        | 1      | 0.04%   |
| Inateck             | 1        | 1      | 0.04%   |
| IBM                 | 1        | 4      | 0.04%   |
| Hajaan              | 1        | 1      | 0.04%   |
| H/W                 | 1        | 3      | 0.04%   |
| China               | 1        | 1      | 0.04%   |
| ASMedia             | 1        | 1      | 0.04%   |
| AMP                 | 1        | 1      | 0.04%   |
| Advantech           | 1        | 1      | 0.04%   |
| 3ware               | 1        | 4      | 0.04%   |
| 128MB               | 1        | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 366      | 542    | 20.77%  |
| Kingston            | 317      | 407    | 17.99%  |
| Crucial             | 238      | 300    | 13.51%  |
| SanDisk             | 103      | 134    | 5.85%   |
| WDC                 | 92       | 102    | 5.22%   |
| China               | 80       | 95     | 4.54%   |
| A-DATA Technology   | 50       | 59     | 2.84%   |
| Intel               | 46       | 61     | 2.61%   |
| SPCC                | 38       | 42     | 2.16%   |
| PNY                 | 35       | 78     | 1.99%   |
| Netac               | 26       | 85     | 1.48%   |
| Transcend           | 25       | 26     | 1.42%   |
| OCZ                 | 21       | 25     | 1.19%   |
| Toshiba             | 20       | 28     | 1.14%   |
| Intenso             | 19       | 27     | 1.08%   |
| Patriot             | 17       | 20     | 0.96%   |
| Micron Technology   | 16       | 18     | 0.91%   |
| GOODRAM             | 13       | 20     | 0.74%   |
| Unknown             | 13       | 14     | 0.74%   |
| Apacer              | 12       | 12     | 0.68%   |
| Gigabyte Technology | 11       | 11     | 0.62%   |
| Hewlett-Packard     | 10       | 14     | 0.57%   |
| Corsair             | 10       | 14     | 0.57%   |
| Team                | 9        | 13     | 0.51%   |
| LITEON              | 8        | 12     | 0.45%   |
| Seagate             | 7        | 8      | 0.4%    |
| Hajaan              | 7        | 8      | 0.4%    |
| SK hynix            | 6        | 7      | 0.34%   |
| NGFF                | 6        | 6      | 0.34%   |
| Mushkin             | 6        | 7      | 0.34%   |
| Xinhaike            | 5        | 8      | 0.28%   |
| SABRENT             | 5        | 5      | 0.28%   |
| Plextor             | 5        | 8      | 0.28%   |
| LITEONIT            | 5        | 9      | 0.28%   |
| Innodisk            | 5        | 5      | 0.28%   |
| Unknown             | 4        | 7      | 0.23%   |
| KingDian            | 4        | 4      | 0.23%   |
| Hoodisk             | 4        | 4      | 0.23%   |
| Foxline             | 4        | 4      | 0.23%   |
| Drevo               | 4        | 4      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1734     | 3956   | 43.84%  |
| SSD     | 1470     | 2357   | 37.17%  |
| NVMe    | 668      | 1053   | 16.89%  |
| Unknown | 55       | 129    | 1.39%   |
| MMC     | 28       | 31     | 0.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 2448     | 6013   | 73.94%  |
| NVMe | 665      | 1047   | 20.08%  |
| SAS  | 170      | 435    | 5.13%   |
| MMC  | 28       | 31     | 0.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1885     | 3015   | 52.39%  |
| 0.51-1.0   | 810      | 1301   | 22.51%  |
| 1.01-2.0   | 383      | 715    | 10.64%  |
| 3.01-4.0   | 205      | 420    | 5.7%    |
| 4.01-10.0  | 158      | 395    | 4.39%   |
| 2.01-3.0   | 106      | 229    | 2.95%   |
| 10.01-20.0 | 51       | 238    | 1.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| Unknown        | 708      | 25.37%  |
| 101-250        | 428      | 15.34%  |
| 501-1000       | 350      | 12.54%  |
| 251-500        | 349      | 12.5%   |
| More than 3000 | 294      | 10.53%  |
| 1001-2000      | 207      | 7.42%   |
| 51-100         | 150      | 5.37%   |
| 1-20           | 108      | 3.87%   |
| 2001-3000      | 106      | 3.8%    |
| 21-50          | 91       | 3.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 750      | 26.42%  |
| Unknown        | 708      | 24.94%  |
| 101-250        | 259      | 9.12%   |
| 21-50          | 223      | 7.85%   |
| 51-100         | 211      | 7.43%   |
| 251-500        | 186      | 6.55%   |
| 501-1000       | 169      | 5.95%   |
| More than 3000 | 135      | 4.76%   |
| 1001-2000      | 126      | 4.44%   |
| 2001-3000      | 64       | 2.25%   |
| 0              | 8        | 0.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB  | 24       | 40     | 3.68%   |
| WDC WD5000AAKX-60U6AA0 500GB     | 20       | 24     | 3.06%   |
| Kingston SV300S37A120G 120GB SSD | 17       | 17     | 2.6%    |
| WDC WD5000AAKX-08U6AA0 500GB     | 8        | 8      | 1.23%   |
| Seagate ST3500418AS 500GB        | 8        | 10     | 1.23%   |
| Hitachi HDS721050CLA362 500GB    | 8        | 8      | 1.23%   |
| Seagate ST3250318AS 250GB        | 7        | 8      | 1.07%   |
| Seagate ST250DM000-1BD141 250GB  | 7        | 7      | 1.07%   |
| Seagate ST1000DM003-9YN162 1TB   | 7        | 8      | 1.07%   |
| Toshiba DT01ACA050 500GB         | 6        | 7      | 0.92%   |
| Seagate ST31000528AS 1TB         | 6        | 7      | 0.92%   |
| Hitachi HDS721050DLE630 500GB    | 6        | 11     | 0.92%   |
| WDC WD20EARX-00PASB0 2TB         | 5        | 5      | 0.77%   |
| WDC WD20EARS-00MVWB0 2TB         | 5        | 5      | 0.77%   |
| WDC WD10EZEX-08WN4A0 1TB         | 5        | 5      | 0.77%   |
| Seagate ST3320613AS 320GB        | 5        | 5      | 0.77%   |
| Seagate ST31500341AS 1TB         | 5        | 7      | 0.77%   |
| WDC WDS120G2G0A-00JH30 120GB SSD | 4        | 4      | 0.61%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 4        | 5      | 0.61%   |
| Seagate ST3500413AS 500GB        | 4        | 5      | 0.61%   |
| Seagate ST2000DL003-9VT166 2TB   | 4        | 4      | 0.61%   |
| Seagate ST1000DM003-1ER162 1TB   | 4        | 5      | 0.61%   |
| Seagate ST1000DM003-1CH162 1TB   | 4        | 4      | 0.61%   |
| WDC WD5000AAKX-001CA0 500GB      | 3        | 3      | 0.46%   |
| WDC WD40EFRX-68N32N0 4TB         | 3        | 6      | 0.46%   |
| WDC WD3200AAJS-08L7A0 320GB      | 3        | 3      | 0.46%   |
| WDC WD3200AAJS-00L7A0 320GB      | 3        | 3      | 0.46%   |
| WDC WD30EFRX-68EUZN0 3TB         | 3        | 3      | 0.46%   |
| WDC WD2500AAJS-00YZCA0 250GB     | 3        | 3      | 0.46%   |
| WDC WD10EARS-00Y5B1 1TB          | 3        | 3      | 0.46%   |
| Toshiba MK2555GSXF 250GB         | 3        | 3      | 0.46%   |
| Toshiba DT01ACA100 1TB           | 3        | 4      | 0.46%   |
| Seagate ST3320620AS 320GB        | 3        | 5      | 0.46%   |
| Seagate ST3320418AS 320GB        | 3        | 5      | 0.46%   |
| Seagate ST3250310AS 250GB        | 3        | 3      | 0.46%   |
| Seagate ST3120827AS 120GB        | 3        | 4      | 0.46%   |
| Seagate ST3120811AS 120GB        | 3        | 3      | 0.46%   |
| Seagate ST2000DM008-2FR102 2TB   | 3        | 4      | 0.46%   |
| Seagate ST2000DM001-1ER164 2TB   | 3        | 3      | 0.46%   |
| Seagate ST2000DM001-1CH164 2TB   | 3        | 4      | 0.46%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 191      | 267    | 30.76%  |
| WDC                 | 183      | 236    | 29.47%  |
| Hitachi             | 45       | 60     | 7.25%   |
| Samsung Electronics | 42       | 49     | 6.76%   |
| Toshiba             | 33       | 41     | 5.31%   |
| Kingston            | 32       | 37     | 5.15%   |
| Intel               | 18       | 22     | 2.9%    |
| A-DATA Technology   | 11       | 14     | 1.77%   |
| Maxtor              | 10       | 13     | 1.61%   |
| Crucial             | 8        | 13     | 1.29%   |
| SanDisk             | 7        | 7      | 1.13%   |
| HGST                | 7        | 7      | 1.13%   |
| China               | 4        | 4      | 0.64%   |
| Transcend           | 3        | 3      | 0.48%   |
| SK hynix            | 3        | 6      | 0.48%   |
| Apacer              | 3        | 3      | 0.48%   |
| SPCC                | 2        | 2      | 0.32%   |
| OCZ                 | 2        | 2      | 0.32%   |
| Micron Technology   | 2        | 2      | 0.32%   |
| Hewlett-Packard     | 2        | 3      | 0.32%   |
| Corsair             | 2        | 2      | 0.32%   |
| Western Digital     | 1        | 2      | 0.16%   |
| ShiJi               | 1        | 1      | 0.16%   |
| PNY                 | 1        | 1      | 0.16%   |
| Patriot             | 1        | 1      | 0.16%   |
| LITEONIT            | 1        | 1      | 0.16%   |
| KingDian            | 1        | 1      | 0.16%   |
| Intenso             | 1        | 1      | 0.16%   |
| IBM                 | 1        | 4      | 0.16%   |
| HANCHU              | 1        | 1      | 0.16%   |
| Fujitsu             | 1        | 2      | 0.16%   |
| EK46XL85C49         | 1        | 1      | 0.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 191      | 267    | 39.22%  |
| WDC                 | 176      | 228    | 36.14%  |
| Hitachi             | 45       | 60     | 9.24%   |
| Toshiba             | 31       | 39     | 6.37%   |
| Samsung Electronics | 23       | 26     | 4.72%   |
| Maxtor              | 10       | 13     | 2.05%   |
| HGST                | 7        | 7      | 1.44%   |
| Hewlett-Packard     | 2        | 3      | 0.41%   |
| IBM                 | 1        | 4      | 0.21%   |
| Fujitsu             | 1        | 2      | 0.21%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 449      | 649    | 77.28%  |
| SSD  | 115      | 134    | 19.79%  |
| NVMe | 17       | 26     | 2.93%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                       | Desktops | Drives | Percent |
|---------------------------------------------|----------|--------|---------|
| WDC WD4001FFSX-68JNUN0 4TB                  | 1        | 1      | 6.25%   |
| Seagate ST500DM005 HD502HJ 500GB            | 1        | 1      | 6.25%   |
| Seagate ST500DM002-1BD142 500GB             | 1        | 2      | 6.25%   |
| Seagate ST3500830AS 500GB                   | 1        | 1      | 6.25%   |
| Seagate ST3500630A 500GB                    | 1        | 1      | 6.25%   |
| Seagate ST2000NM0011 2TB                    | 1        | 1      | 6.25%   |
| Samsung Electronics SSD PM871 2.5 7mm 128GB | 1        | 1      | 6.25%   |
| Samsung Electronics SSD 980 1TB             | 1        | 1      | 6.25%   |
| Samsung Electronics SP0802N 80GB            | 1        | 1      | 6.25%   |
| Samsung Electronics HD253GJ 250GB           | 1        | 1      | 6.25%   |
| Samsung Electronics HD103SJ 1TB             | 1        | 1      | 6.25%   |
| Intel SSDSC2KW256G8 256GB                   | 1        | 1      | 6.25%   |
| Inland SATA SSD 128GB                       | 1        | 1      | 6.25%   |
| HGST HUH728080ALN600 8TB                    | 1        | 1      | 6.25%   |
| HGST HDN724040ALE640 4TB                    | 1        | 1      | 6.25%   |
| Hewlett-Packard SSD S700 500GB              | 1        | 2      | 6.25%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5        | 6      | 31.25%  |
| Samsung Electronics | 5        | 5      | 31.25%  |
| HGST                | 2        | 2      | 12.5%   |
| WDC                 | 1        | 1      | 6.25%   |
| Intel               | 1        | 1      | 6.25%   |
| Inland              | 1        | 1      | 6.25%   |
| Hewlett-Packard     | 1        | 2      | 6.25%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 2082     | 5077   | 64.98%  |
| Malfunc  | 559      | 809    | 17.45%  |
| Detected | 546      | 1621   | 17.04%  |
| Failed   | 16       | 18     | 0.5%    |
| Limited  | 1        | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1920     | 50.43%  |
| AMD                              | 708      | 18.6%   |
| Samsung Electronics              | 274      | 7.2%    |
| ASMedia Technology               | 139      | 3.65%   |
| Sandisk                          | 109      | 2.86%   |
| Phison Electronics               | 83       | 2.18%   |
| Marvell Technology Group         | 77       | 2.02%   |
| JMicron Technology               | 74       | 1.94%   |
| Nvidia                           | 56       | 1.47%   |
| Kingston Technology Company      | 52       | 1.37%   |
| Micron/Crucial Technology        | 40       | 1.05%   |
| LSI Logic / Symbios Logic        | 35       | 0.92%   |
| VIA Technologies                 | 34       | 0.89%   |
| Broadcom / LSI                   | 25       | 0.66%   |
| ADATA Technology                 | 23       | 0.6%    |
| Silicon Motion                   | 22       | 0.58%   |
| SK hynix                         | 18       | 0.47%   |
| Adaptec                          | 13       | 0.34%   |
| Toshiba America Info Systems     | 12       | 0.32%   |
| MAXIO Technology (Hangzhou)      | 12       | 0.32%   |
| Micron Technology                | 11       | 0.29%   |
| Silicon Image                    | 10       | 0.26%   |
| Realtek Semiconductor            | 9        | 0.24%   |
| KIOXIA                           | 8        | 0.21%   |
| Seagate Technology               | 6        | 0.16%   |
| INNOGRIT                         | 5        | 0.13%   |
| Silicon Integrated Systems [SiS] | 4        | 0.11%   |
| Hewlett-Packard                  | 4        | 0.11%   |
| Shenzhen Longsys Electronics     | 3        | 0.08%   |
| Lite-On Technology               | 3        | 0.08%   |
| Integrated Technology Express    | 3        | 0.08%   |
| Biwin Storage Technology         | 3        | 0.08%   |
| Swissbit                         | 2        | 0.05%   |
| 3ware                            | 2        | 0.05%   |
| Solid State Storage Technology   | 1        | 0.03%   |
| Netac Technology                 | 1        | 0.03%   |
| Jiangsu Huacun Elec.             | 1        | 0.03%   |
| Innodisk                         | 1        | 0.03%   |
| Hosin Global Electronics         | 1        | 0.03%   |
| HighPoint Technologies           | 1        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 389      | 8.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 237      | 5.05%   |
| AMD 400 Series Chipset SATA Controller                                                  | 156      | 3.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 155      | 3.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 154      | 3.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 150      | 3.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 143      | 3.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 139      | 2.96%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 114      | 2.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 107      | 2.28%   |
| AMD 500 Series Chipset SATA Controller                                                  | 102      | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 100      | 2.13%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 93       | 1.98%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 84       | 1.79%   |
| Intel SATA Controller [RAID mode]                                                       | 83       | 1.77%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 76       | 1.62%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 73       | 1.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 65       | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 65       | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 65       | 1.39%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 60       | 1.28%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 59       | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 46       | 0.98%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 44       | 0.94%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 42       | 0.9%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 41       | 0.87%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 41       | 0.87%   |
| Phison E12 NVMe Controller                                                              | 40       | 0.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 36       | 0.77%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 33       | 0.7%    |
| AMD 300 Series Chipset SATA Controller                                                  | 32       | 0.68%   |
| Nvidia MCP61 SATA Controller                                                            | 31       | 0.66%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 30       | 0.64%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 30       | 0.64%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 29       | 0.62%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 28       | 0.6%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 26       | 0.55%   |
| Nvidia MCP61 IDE                                                                        | 25       | 0.53%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 25       | 0.53%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 25       | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2207     | 58.7%   |
| NVMe | 666      | 17.71%  |
| IDE  | 632      | 16.81%  |
| RAID | 170      | 4.52%   |
| SAS  | 68       | 1.81%   |
| SCSI | 17       | 0.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 1941     | 71.33%  |
| AMD                   | 770      | 28.3%   |
| CentaurHauls          | 5        | 0.18%   |
| sifive,u74-mc         | 3        | 0.11%   |
| Marvell Semiconductor | 1        | 0.04%   |
| Unknown               | 1        | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-9400 CPU @ 2.90GHz            | 64       | 2.35%   |
| AMD Ryzen 5 3600 6-Core Processor           | 39       | 1.43%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 36       | 1.32%   |
| Intel Pentium CPU G3420 @ 3.20GHz           | 35       | 1.28%   |
| Intel Pentium CPU G4400 @ 3.30GHz           | 32       | 1.17%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 28       | 1.03%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 28       | 1.03%   |
| Intel Core i7-10700 CPU @ 2.90GHz           | 27       | 0.99%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 27       | 0.99%   |
| Intel Core i3-10100 CPU @ 3.60GHz           | 27       | 0.99%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 25       | 0.92%   |
| Intel Celeron N5105 @ 2.00GHz               | 24       | 0.88%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 24       | 0.88%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 23       | 0.84%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 23       | 0.84%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 23       | 0.84%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 22       | 0.81%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 22       | 0.81%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 22       | 0.81%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 21       | 0.77%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 21       | 0.77%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 21       | 0.77%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 21       | 0.77%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 20       | 0.73%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 20       | 0.73%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 20       | 0.73%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 19       | 0.7%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 19       | 0.7%    |
| Intel Core i3-6100 CPU @ 3.70GHz            | 19       | 0.7%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 19       | 0.7%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 18       | 0.66%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 17       | 0.62%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 17       | 0.62%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 17       | 0.62%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 17       | 0.62%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 17       | 0.62%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 16       | 0.59%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 16       | 0.59%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 16       | 0.59%   |
| AMD FX-8350 Eight-Core Processor            | 16       | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 460      | 16.89%  |
| Intel Core i3           | 251      | 9.21%   |
| Intel Core i7           | 245      | 8.99%   |
| Intel Pentium           | 176      | 6.46%   |
| Intel Xeon              | 175      | 6.42%   |
| AMD Ryzen 5             | 168      | 6.17%   |
| Intel Celeron           | 165      | 6.06%   |
| AMD Ryzen 7             | 133      | 4.88%   |
| Other                   | 129      | 4.74%   |
| Intel Core 2 Duo        | 105      | 3.85%   |
| AMD Ryzen 9             | 91       | 3.34%   |
| AMD FX                  | 80       | 2.94%   |
| Intel Pentium Dual-Core | 59       | 2.17%   |
| Intel Core 2 Quad       | 38       | 1.4%    |
| AMD Ryzen 3             | 38       | 1.4%    |
| Intel Atom              | 34       | 1.25%   |
| Intel Core i9           | 26       | 0.95%   |
| AMD Ryzen Threadripper  | 26       | 0.95%   |
| AMD Athlon              | 23       | 0.84%   |
| AMD A10                 | 21       | 0.77%   |
| Intel Pentium Gold      | 20       | 0.73%   |
| AMD Athlon II X2        | 19       | 0.7%    |
| AMD Athlon 64 X2        | 19       | 0.7%    |
| Intel Pentium 4         | 18       | 0.66%   |
| AMD Phenom II X4        | 18       | 0.66%   |
| Intel Core 2            | 14       | 0.51%   |
| AMD GX                  | 14       | 0.51%   |
| Intel Pentium Silver    | 11       | 0.4%    |
| AMD Ryzen 5 PRO         | 11       | 0.4%    |
| AMD Phenom II X6        | 11       | 0.4%    |
| Intel Pentium Dual      | 10       | 0.37%   |
| AMD A8                  | 10       | 0.37%   |
| AMD G                   | 9        | 0.33%   |
| Intel Pentium D         | 8        | 0.29%   |
| AMD A4                  | 8        | 0.29%   |
| AMD Sempron             | 7        | 0.26%   |
| AMD Athlon II X4        | 6        | 0.22%   |
| AMD A6                  | 6        | 0.22%   |
| Intel Genuine           | 5        | 0.18%   |
| AMD Turion II Neo       | 5        | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 919      | 33.7%   |
| 2       | 819      | 30.03%  |
| 6       | 397      | 14.56%  |
| 8       | 255      | 9.35%   |
| 1       | 81       | 2.97%   |
| 16      | 79       | 2.9%    |
| 12      | 77       | 2.82%   |
| 3       | 34       | 1.25%   |
| 10      | 20       | 0.73%   |
| 32      | 13       | 0.48%   |
| 24      | 12       | 0.44%   |
| 14      | 5        | 0.18%   |
| 18      | 4        | 0.15%   |
| Unknown | 4        | 0.15%   |
| 44      | 2        | 0.07%   |
| 36      | 2        | 0.07%   |
| 20      | 2        | 0.07%   |
| 64      | 1        | 0.04%   |
| 28      | 1        | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2669     | 98.05%  |
| 2       | 48       | 1.76%   |
| Unknown | 4        | 0.15%   |
| 0       | 1        | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1416     | 51.93%  |
| 1       | 1307     | 47.93%  |
| Unknown | 4        | 0.15%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2686     | 98.68%  |
| 32-bit         | 30       | 1.1%    |
| Unknown        | 6        | 0.22%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 472      | 16.95%  |
| 0x306c3    | 247      | 8.87%   |
| 0x206a7    | 155      | 5.57%   |
| 0x306a9    | 147      | 5.28%   |
| 0x1067a    | 141      | 5.06%   |
| 0x506e3    | 118      | 4.24%   |
| 0x906ea    | 115      | 4.13%   |
| 0xa0653    | 77       | 2.77%   |
| 0x08701021 | 72       | 2.59%   |
| 0x906e9    | 53       | 1.9%    |
| 0x906c0    | 45       | 1.62%   |
| 0x0a201016 | 42       | 1.51%   |
| 0x08108109 | 41       | 1.47%   |
| 0xa0671    | 40       | 1.44%   |
| 0xa0655    | 40       | 1.44%   |
| 0x0800820d | 37       | 1.33%   |
| 0x90672    | 33       | 1.19%   |
| 0x010000c8 | 26       | 0.93%   |
| 0x906ed    | 24       | 0.86%   |
| 0x6fd      | 24       | 0.86%   |
| 0x306f2    | 23       | 0.83%   |
| 0x906eb    | 21       | 0.75%   |
| 0x0a50000c | 20       | 0.72%   |
| 0x08101016 | 20       | 0.72%   |
| 0x06000822 | 20       | 0.72%   |
| 0x90675    | 19       | 0.68%   |
| 0x6fb      | 19       | 0.68%   |
| 0x0a50000d | 19       | 0.68%   |
| 0x06003106 | 19       | 0.68%   |
| 0x206d7    | 18       | 0.65%   |
| 0x06000852 | 18       | 0.65%   |
| 0x306e4    | 17       | 0.61%   |
| 0x206c2    | 17       | 0.61%   |
| 0x706a8    | 16       | 0.57%   |
| 0x506c9    | 16       | 0.57%   |
| 0x0a201009 | 16       | 0.57%   |
| 0x08600106 | 16       | 0.57%   |
| 0x10676    | 15       | 0.54%   |
| 0x0a20120a | 15       | 0.54%   |
| 0x010000b6 | 15       | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 331      | 12.13%  |
| KabyLake         | 266      | 9.75%   |
| SandyBridge      | 200      | 7.33%   |
| IvyBridge        | 190      | 6.96%   |
| Penryn           | 179      | 6.56%   |
| Zen 3            | 155      | 5.68%   |
| Skylake          | 148      | 5.43%   |
| Zen 2            | 145      | 5.32%   |
| CometLake        | 136      | 4.99%   |
| Unknown          | 111      | 4.07%   |
| Zen+             | 109      | 4%      |
| Piledriver       | 77       | 2.82%   |
| Core             | 74       | 2.71%   |
| K10              | 73       | 2.68%   |
| Zen              | 67       | 2.46%   |
| Tremont          | 53       | 1.94%   |
| Westmere         | 46       | 1.69%   |
| Silvermont       | 38       | 1.39%   |
| NetBurst         | 33       | 1.21%   |
| Nehalem          | 31       | 1.14%   |
| K8 Hammer        | 31       | 1.14%   |
| Goldmont plus    | 28       | 1.03%   |
| Alderlake Hybrid | 28       | 1.03%   |
| Steamroller      | 23       | 0.84%   |
| Goldmont         | 22       | 0.81%   |
| Bulldozer        | 20       | 0.73%   |
| Bonnell          | 20       | 0.73%   |
| Broadwell        | 15       | 0.55%   |
| Icelake          | 13       | 0.48%   |
| Excavator        | 13       | 0.48%   |
| Bobcat           | 13       | 0.48%   |
| Jaguar           | 12       | 0.44%   |
| Puma             | 8        | 0.29%   |
| P6               | 6        | 0.22%   |
| TigerLake        | 5        | 0.18%   |
| K6               | 4        | 0.15%   |
| K10 Llano        | 2        | 0.07%   |
| Gracemont        | 2        | 0.07%   |
| Geode            | 1        | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1242     | 43.15%  |
| Nvidia                           | 896      | 31.13%  |
| AMD                              | 640      | 22.24%  |
| ASPEED Technology                | 61       | 2.12%   |
| Matrox Electronics Systems       | 27       | 0.94%   |
| VIA Technologies                 | 8        | 0.28%   |
| Silicon Integrated Systems [SiS] | 3        | 0.1%    |
| ATI Technologies                 | 1        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 177      | 6.04%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 124      | 4.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 105      | 3.58%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 86       | 2.93%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 82       | 2.8%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 70       | 2.39%   |
| Nvidia GK208B [GeForce GT 710]                                              | 63       | 2.15%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 63       | 2.15%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 63       | 2.15%   |
| ASPEED Technology ASPEED Graphics Family                                    | 61       | 2.08%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                       | 55       | 1.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 51       | 1.74%   |
| Intel JasperLake [UHD Graphics]                                             | 47       | 1.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 46       | 1.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 42       | 1.43%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 40       | 1.36%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 38       | 1.3%    |
| Nvidia GF108 [GeForce GT 730]                                               | 38       | 1.3%    |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                     | 35       | 1.19%   |
| Intel Skylake-S GT1 [HD Graphics 510]                                       | 31       | 1.06%   |
| Intel Alder Lake-S GT1 [UHD Graphics 770]                                   | 30       | 1.02%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 29       | 0.99%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 29       | 0.99%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 27       | 0.92%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 25       | 0.85%   |
| Nvidia GF108 [GeForce GT 630]                                               | 25       | 0.85%   |
| Nvidia GK208B [GeForce GT 730]                                              | 24       | 0.82%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 24       | 0.82%   |
| Nvidia GT218 [GeForce 210]                                                  | 23       | 0.78%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 23       | 0.78%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 23       | 0.78%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 20       | 0.68%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 19       | 0.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 19       | 0.65%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                 | 19       | 0.65%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                     | 18       | 0.61%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 18       | 0.61%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 17       | 0.58%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 16       | 0.55%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 16       | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| 1 x Intel                         | 1126     | 41.02%  |
| 1 x Nvidia                        | 806      | 29.36%  |
| 1 x AMD                           | 576      | 20.98%  |
| 1 x ASPEED                        | 45       | 1.64%   |
| Intel + Nvidia                    | 44       | 1.6%    |
| 1 x Matrox                        | 26       | 0.95%   |
| Other                             | 25       | 0.91%   |
| AMD + Nvidia                      | 24       | 0.87%   |
| 2 x AMD                           | 22       | 0.8%    |
| Nvidia + ASPEED                   | 9        | 0.33%   |
| Intel + AMD                       | 9        | 0.33%   |
| 2 x Nvidia                        | 8        | 0.29%   |
| 1 x VIA                           | 8        | 0.29%   |
| AMD + ASPEED                      | 5        | 0.18%   |
| 1 x SiS                           | 3        | 0.11%   |
| Intel + 2 x Nvidia                | 3        | 0.11%   |
| 3 x AMD                           | 2        | 0.07%   |
| 2 x Nvidia + 1 x ASPEED           | 1        | 0.04%   |
| 2 x Intel                         | 1        | 0.04%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1        | 0.04%   |
| AMD + Matrox                      | 1        | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1476     | 53.71%  |
| Unknown     | 904      | 32.9%   |
| Proprietary | 368      | 13.39%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1827     | 66.2%   |
| 1.01-2.0   | 228      | 8.26%   |
| 0.01-0.5   | 161      | 5.83%   |
| 0.51-1.0   | 147      | 5.33%   |
| 3.01-4.0   | 140      | 5.07%   |
| 7.01-8.0   | 124      | 4.49%   |
| 5.01-6.0   | 62       | 2.25%   |
| 8.01-16.0  | 37       | 1.34%   |
| 2.01-3.0   | 19       | 0.69%   |
| 16.01-24.0 | 8        | 0.29%   |
| 4.01-5.0   | 5        | 0.18%   |
| 32.01-64.0 | 1        | 0.04%   |
| 24.01-32.0 | 1        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 287      | 15.07%  |
| Dell                 | 215      | 11.29%  |
| Goldstar             | 186      | 9.77%   |
| Acer                 | 123      | 6.46%   |
| Hewlett-Packard      | 117      | 6.14%   |
| BenQ                 | 105      | 5.51%   |
| AOC                  | 94       | 4.94%   |
| Philips              | 87       | 4.57%   |
| Ancor Communications | 81       | 4.25%   |
| Unknown              | 47       | 2.47%   |
| ViewSonic            | 43       | 2.26%   |
| Iiyama               | 43       | 2.26%   |
| ASUSTek Computer     | 36       | 1.89%   |
| Eizo                 | 29       | 1.52%   |
| Sony                 | 26       | 1.37%   |
| Lenovo               | 26       | 1.37%   |
| LG Electronics       | 23       | 1.21%   |
| NEC Computers        | 20       | 1.05%   |
| Unknown              | 15       | 0.79%   |
| Vestel Elektronik    | 10       | 0.53%   |
| Medion               | 10       | 0.53%   |
| Fujitsu Siemens      | 10       | 0.53%   |
| Vizio                | 9        | 0.47%   |
| MSI                  | 9        | 0.47%   |
| Sceptre Tech         | 6        | 0.32%   |
| Packard Bell         | 6        | 0.32%   |
| Hitachi              | 6        | 0.32%   |
| HannStar             | 6        | 0.32%   |
| Belinea              | 6        | 0.32%   |
| Toshiba              | 5        | 0.26%   |
| Panasonic            | 5        | 0.26%   |
| Microstep            | 5        | 0.26%   |
| Lenovo Group Limited | 5        | 0.26%   |
| Idek Iiyama          | 5        | 0.26%   |
| HPN                  | 5        | 0.26%   |
| AU Optronics         | 5        | 0.26%   |
| Plain Tree Systems   | 4        | 0.21%   |
| MStar                | 4        | 0.21%   |
| Mi                   | 4        | 0.21%   |
| HUAWEI               | 4        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 34       | 1.69%   |
| Unknown                                                               | 15       | 0.75%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 12       | 0.6%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 11       | 0.55%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch  | 9        | 0.45%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 9        | 0.45%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                | 8        | 0.4%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 7        | 0.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 7        | 0.35%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                     | 7        | 0.35%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 340x270mm 17.1-inch  | 6        | 0.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 6        | 0.3%    |
| Dell E176FP DELA014 1280x1024 338x270mm 17.0-inch                     | 6        | 0.3%    |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                        | 6        | 0.3%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5        | 0.25%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 5        | 0.25%   |
| Hewlett-Packard E201 HWP305F 1600x900 443x249mm 20.0-inch             | 5        | 0.25%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                  | 5        | 0.25%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 5        | 0.25%   |
| Dell U2518D DEL413A 2560x1440 553x311mm 25.0-inch                     | 5        | 0.25%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 5        | 0.25%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 5        | 0.25%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 5        | 0.25%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 5        | 0.25%   |
| Ancor Communications VE228 ACI22FA 1920x1080 477x268mm 21.5-inch      | 5        | 0.25%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 5        | 0.25%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 4        | 0.2%    |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 4        | 0.2%    |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 4        | 0.2%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 4        | 0.2%    |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch               | 4        | 0.2%    |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                      | 4        | 0.2%    |
| Iiyama PL2283H IVM562E 1920x1080 496x292mm 22.7-inch                  | 4        | 0.2%    |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 4        | 0.2%    |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 4        | 0.2%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 4        | 0.2%    |
| Dell 1905FP DEL400D 1280x1024 376x301mm 19.0-inch                     | 4        | 0.2%    |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                     | 4        | 0.2%    |
| BenQ GL2480 BNQ78ED 1920x1080 531x298mm 24.0-inch                     | 4        | 0.2%    |
| BenQ G2220HD BNQ7821 1920x1080 477x268mm 21.5-inch                    | 4        | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 811      | 43.25%  |
| 3840x2160 (4K)     | 180      | 9.6%    |
| 1280x1024 (SXGA)   | 160      | 8.53%   |
| 2560x1440 (QHD)    | 129      | 6.88%   |
| 1680x1050 (WSXGA+) | 88       | 4.69%   |
| Unknown            | 63       | 3.36%   |
| 1366x768 (WXGA)    | 59       | 3.15%   |
| 1920x1200 (WUXGA)  | 50       | 2.67%   |
| 1600x900 (HD+)     | 50       | 2.67%   |
| 1440x900 (WXGA+)   | 46       | 2.45%   |
| 2288x1287          | 36       | 1.92%   |
| 2560x1080          | 26       | 1.39%   |
| 1360x768           | 25       | 1.33%   |
| 3440x1440          | 23       | 1.23%   |
| 1024x768 (XGA)     | 23       | 1.23%   |
| 3840x1080          | 19       | 1.01%   |
| 1600x1200          | 18       | 0.96%   |
| 4480x1440          | 6        | 0.32%   |
| 1920x540           | 6        | 0.32%   |
| 5760x1080          | 4        | 0.21%   |
| 3200x1080          | 4        | 0.21%   |
| 5120x1440          | 3        | 0.16%   |
| 2560x1600          | 3        | 0.16%   |
| 1400x1050          | 3        | 0.16%   |
| 5760x2160          | 2        | 0.11%   |
| 5360x1440          | 2        | 0.11%   |
| 3840x1200          | 2        | 0.11%   |
| 3360x1050          | 2        | 0.11%   |
| 2048x1152          | 2        | 0.11%   |
| 1280x800 (WXGA)    | 2        | 0.11%   |
| 1280x720 (HD)      | 2        | 0.11%   |
| 7680x4320          | 1        | 0.05%   |
| 6400x2160          | 1        | 0.05%   |
| 6160x1440          | 1        | 0.05%   |
| 5120x2160          | 1        | 0.05%   |
| 5120x1080          | 1        | 0.05%   |
| 4480x1600          | 1        | 0.05%   |
| 3840x2560          | 1        | 0.05%   |
| 3840x1600          | 1        | 0.05%   |
| 3600x1080          | 1        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 278      | 14.99%  |
| 27      | 234      | 12.62%  |
| 23      | 216      | 11.65%  |
| 21      | 173      | 9.33%   |
| Unknown | 165      | 8.9%    |
| 19      | 119      | 6.42%   |
| 17      | 80       | 4.31%   |
| 31      | 77       | 4.15%   |
| 18      | 75       | 4.05%   |
| 22      | 66       | 3.56%   |
| 20      | 60       | 3.24%   |
| 15      | 43       | 2.32%   |
| 34      | 38       | 2.05%   |
| 142     | 34       | 1.83%   |
| 84      | 26       | 1.4%    |
| 72      | 21       | 1.13%   |
| 32      | 21       | 1.13%   |
| 54      | 12       | 0.65%   |
| 25      | 12       | 0.65%   |
| 28      | 10       | 0.54%   |
| 40      | 9        | 0.49%   |
| 13      | 9        | 0.49%   |
| 52      | 7        | 0.38%   |
| 26      | 7        | 0.38%   |
| 48      | 5        | 0.27%   |
| 65      | 4        | 0.22%   |
| 43      | 4        | 0.22%   |
| 42      | 4        | 0.22%   |
| 33      | 4        | 0.22%   |
| 29      | 4        | 0.22%   |
| 63      | 3        | 0.16%   |
| 39      | 3        | 0.16%   |
| 35      | 3        | 0.16%   |
| 16      | 3        | 0.16%   |
| 12      | 3        | 0.16%   |
| 75      | 2        | 0.11%   |
| 64      | 2        | 0.11%   |
| 60      | 2        | 0.11%   |
| 49      | 2        | 0.11%   |
| 36      | 2        | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 662      | 36.88%  |
| 401-500        | 411      | 22.9%   |
| Unknown        | 165      | 9.19%   |
| 601-700        | 120      | 6.69%   |
| 301-350        | 118      | 6.57%   |
| 351-400        | 91       | 5.07%   |
| 701-800        | 63       | 3.51%   |
| 1501-2000      | 51       | 2.84%   |
| 1001-1500      | 39       | 2.17%   |
| More than 2000 | 35       | 1.95%   |
| 801-900        | 17       | 0.95%   |
| 201-300        | 13       | 0.72%   |
| 901-1000       | 8        | 0.45%   |
| 101-200        | 2        | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1076     | 61.73%  |
| 16/10   | 202      | 11.59%  |
| 5/4     | 148      | 8.49%   |
| Unknown | 148      | 8.49%   |
| 4/3     | 55       | 3.16%   |
| 21/9    | 46       | 2.64%   |
| 1.00    | 36       | 2.07%   |
| 3/2     | 13       | 0.75%   |
| 6/5     | 10       | 0.57%   |
| 32/9    | 4        | 0.23%   |
| 2.65    | 1        | 0.06%   |
| 2.00    | 1        | 0.06%   |
| 11/10   | 1        | 0.06%   |
| 1.96    | 1        | 0.06%   |
| 0.56    | 1        | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 589      | 32.45%  |
| 301-350        | 239      | 13.17%  |
| 151-200        | 230      | 12.67%  |
| Unknown        | 165      | 9.09%   |
| 351-500        | 152      | 8.37%   |
| 141-150        | 129      | 7.11%   |
| More than 1000 | 120      | 6.61%   |
| 251-300        | 96       | 5.29%   |
| 101-110        | 36       | 1.98%   |
| 501-1000       | 27       | 1.49%   |
| 71-80          | 7        | 0.39%   |
| 111-120        | 6        | 0.33%   |
| 81-90          | 5        | 0.28%   |
| 131-140        | 5        | 0.28%   |
| 121-130        | 5        | 0.28%   |
| 1-40           | 2        | 0.11%   |
| 41-50          | 1        | 0.06%   |
| 91-100         | 1        | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 1079     | 62.01%  |
| 101-120       | 281      | 16.15%  |
| Unknown       | 165      | 9.48%   |
| 1-50          | 96       | 5.52%   |
| 121-160       | 80       | 4.6%    |
| 161-240       | 36       | 2.07%   |
| More than 240 | 3        | 0.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1366     | 49.46%  |
| 0     | 1048     | 37.94%  |
| 2     | 319      | 11.55%  |
| 3     | 27       | 0.98%   |
| 4     | 2        | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 1695     | 46.39%  |
| Intel                            | 1117     | 30.57%  |
| Qualcomm Atheros                 | 194      | 5.31%   |
| Broadcom                         | 94       | 2.57%   |
| Ralink Technology                | 57       | 1.56%   |
| Nvidia                           | 48       | 1.31%   |
| TP-Link                          | 41       | 1.12%   |
| MediaTek                         | 34       | 0.93%   |
| Broadcom Limited                 | 28       | 0.77%   |
| Ralink                           | 25       | 0.68%   |
| Aquantia                         | 20       | 0.55%   |
| Marvell Technology Group         | 19       | 0.52%   |
| Mellanox Technologies            | 17       | 0.47%   |
| D-Link System                    | 16       | 0.44%   |
| Samsung Electronics              | 15       | 0.41%   |
| Qualcomm Atheros Communications  | 15       | 0.41%   |
| ASIX Electronics                 | 15       | 0.41%   |
| American Megatrends              | 13       | 0.36%   |
| VIA Technologies                 | 11       | 0.3%    |
| NetGear                          | 10       | 0.27%   |
| Huawei Technologies              | 10       | 0.27%   |
| D-Link                           | 10       | 0.27%   |
| Xiaomi                           | 9        | 0.25%   |
| Microsoft                        | 9        | 0.25%   |
| Edimax Technology                | 9        | 0.25%   |
| ASUSTek Computer                 | 9        | 0.25%   |
| 3Com                             | 7        | 0.19%   |
| Sigma Designs                    | 6        | 0.16%   |
| Gemtek                           | 5        | 0.14%   |
| Belkin Components                | 5        | 0.14%   |
| ZTE WCDMA Technologies MSM       | 4        | 0.11%   |
| Texas Instruments                | 4        | 0.11%   |
| Dresden Elektronik               | 4        | 0.11%   |
| Silicon Integrated Systems [SiS] | 3        | 0.08%   |
| QLogic                           | 3        | 0.08%   |
| QinHeng Electronics              | 3        | 0.08%   |
| OPPO Electronics                 | 3        | 0.08%   |
| IMC Networks                     | 3        | 0.08%   |
| ICS Advent                       | 3        | 0.08%   |
| Emulex                           | 3        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1355     | 33.12%  |
| Realtek RTL8125 2.5GbE Controller                                      | 135      | 3.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 101      | 2.47%   |
| Intel I211 Gigabit Network Connection                                  | 100      | 2.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 89       | 2.18%   |
| Intel Wi-Fi 6 AX200                                                    | 89       | 2.18%   |
| Intel Ethernet Controller I225-V                                       | 79       | 1.93%   |
| Intel Ethernet Connection (2) I219-V                                   | 65       | 1.59%   |
| Intel Ethernet Connection I217-LM                                      | 62       | 1.52%   |
| Intel I210 Gigabit Network Connection                                  | 59       | 1.44%   |
| Intel 82579V Gigabit Network Connection                                | 39       | 0.95%   |
| Intel 82574L Gigabit Network Connection                                | 39       | 0.95%   |
| Intel Wireless 3165                                                    | 38       | 0.93%   |
| Intel Ethernet Connection (14) I219-V                                  | 37       | 0.9%    |
| Intel Ethernet Connection (7) I219-V                                   | 33       | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 31       | 0.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 30       | 0.73%   |
| Intel Ethernet Connection (2) I219-LM                                  | 30       | 0.73%   |
| Nvidia MCP61 Ethernet                                                  | 29       | 0.71%   |
| Intel Ethernet Connection I217-V                                       | 29       | 0.71%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 28       | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 26       | 0.64%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 24       | 0.59%   |
| Ralink MT7601U Wireless Adapter                                        | 23       | 0.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 23       | 0.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 22       | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 22       | 0.54%   |
| Intel Ethernet Controller X550                                         | 21       | 0.51%   |
| Intel Alder Lake-S PCH CNVi WiFi                                       | 20       | 0.49%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 20       | 0.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 19       | 0.46%   |
| Realtek 802.11ac NIC                                                   | 19       | 0.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 18       | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 18       | 0.44%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 18       | 0.44%   |
| Intel I350 Gigabit Network Connection                                  | 18       | 0.44%   |
| Intel Ethernet Connection (7) I219-LM                                  | 18       | 0.44%   |
| Intel Ethernet Connection (2) I218-V                                   | 18       | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 17       | 0.42%   |
| Intel Wireless 7265                                                    | 17       | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 324      | 36.99%  |
| Realtek Semiconductor           | 185      | 21.12%  |
| Qualcomm Atheros                | 94       | 10.73%  |
| Ralink Technology               | 57       | 6.51%   |
| TP-Link                         | 38       | 4.34%   |
| MediaTek                        | 32       | 3.65%   |
| Ralink                          | 25       | 2.85%   |
| Broadcom                        | 22       | 2.51%   |
| Qualcomm Atheros Communications | 15       | 1.71%   |
| NetGear                         | 10       | 1.14%   |
| D-Link                          | 10       | 1.14%   |
| Edimax Technology               | 9        | 1.03%   |
| ASUSTek Computer                | 9        | 1.03%   |
| Microsoft                       | 8        | 0.91%   |
| D-Link System                   | 7        | 0.8%    |
| Belkin Components               | 5        | 0.57%   |
| Gemtek                          | 4        | 0.46%   |
| Broadcom Limited                | 4        | 0.46%   |
| IMC Networks                    | 3        | 0.34%   |
| AVM                             | 3        | 0.34%   |
| Wilocity                        | 2        | 0.23%   |
| Linksys                         | 2        | 0.23%   |
| Xiaomi                          | 1        | 0.11%   |
| Tenda                           | 1        | 0.11%   |
| Sitecom Europe                  | 1        | 0.11%   |
| Micro Star International        | 1        | 0.11%   |
| Marvell Technology Group        | 1        | 0.11%   |
| Encore Electronics              | 1        | 0.11%   |
| CyberTAN Technology             | 1        | 0.11%   |
| BUFFALO                         | 1        | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 89       | 10.11%  |
| Intel Wireless 3165                                            | 38       | 4.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 31       | 3.52%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 30       | 3.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 28       | 3.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 26       | 2.95%   |
| Ralink MT7601U Wireless Adapter                                | 23       | 2.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 23       | 2.61%   |
| Realtek 802.11ac NIC                                           | 19       | 2.16%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 18       | 2.05%   |
| Intel Wireless 7265                                            | 17       | 1.93%   |
| Intel Wireless 7260                                            | 17       | 1.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16       | 1.82%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 15       | 1.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 15       | 1.7%    |
| Qualcomm Atheros AR9271 802.11n                                | 14       | 1.59%   |
| Ralink RT5370 Wireless Adapter                                 | 13       | 1.48%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 12       | 1.36%   |
| Intel Wireless 8260                                            | 11       | 1.25%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 11       | 1.25%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 10       | 1.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10       | 1.14%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 10       | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 10       | 1.14%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 10       | 1.14%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 10       | 1.14%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 9        | 1.02%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 8        | 0.91%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 8        | 0.91%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 7        | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 7        | 0.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 7        | 0.8%    |
| TP-Link 802.11ac NIC                                           | 6        | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6        | 0.68%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 6        | 0.68%   |
| Ralink RT5372 Wireless Adapter                                 | 6        | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6        | 0.68%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 5        | 0.57%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 5        | 0.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5        | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1623     | 54.26%  |
| Intel                             | 934      | 31.23%  |
| Qualcomm Atheros                  | 108      | 3.61%   |
| Broadcom                          | 76       | 2.54%   |
| Nvidia                            | 47       | 1.57%   |
| Broadcom Limited                  | 24       | 0.8%    |
| Aquantia                          | 20       | 0.67%   |
| Marvell Technology Group          | 19       | 0.64%   |
| Mellanox Technologies             | 16       | 0.53%   |
| Samsung Electronics               | 15       | 0.5%    |
| ASIX Electronics                  | 15       | 0.5%    |
| American Megatrends               | 13       | 0.43%   |
| VIA Technologies                  | 11       | 0.37%   |
| D-Link System                     | 9        | 0.3%    |
| Xiaomi                            | 8        | 0.27%   |
| 3Com                              | 7        | 0.23%   |
| Huawei Technologies               | 6        | 0.2%    |
| TP-Link                           | 3        | 0.1%    |
| Silicon Integrated Systems [SiS]  | 3        | 0.1%    |
| QLogic                            | 3        | 0.1%    |
| OPPO Electronics                  | 3        | 0.1%    |
| ICS Advent                        | 3        | 0.1%    |
| Emulex                            | 3        | 0.1%    |
| DisplayLink                       | 3        | 0.1%    |
| Qualcomm                          | 2        | 0.07%   |
| Motorola PCS                      | 2        | 0.07%   |
| ADMtek                            | 2        | 0.07%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.03%   |
| Tehuti Networks                   | 1        | 0.03%   |
| Sundance Technology Inc / IC Plus | 1        | 0.03%   |
| Standard Microsystems [SMC]       | 1        | 0.03%   |
| Microsoft                         | 1        | 0.03%   |
| Microchip Technology              | 1        | 0.03%   |
| MediaTek                          | 1        | 0.03%   |
| Lenovo                            | 1        | 0.03%   |
| JMicron Technology                | 1        | 0.03%   |
| Google                            | 1        | 0.03%   |
| Gemtek                            | 1        | 0.03%   |
| ATEN International                | 1        | 0.03%   |
| Accton Technology                 | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 1355     | 42.95%  |
| Realtek RTL8125 2.5GbE Controller                                              | 135      | 4.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 101      | 3.2%    |
| Intel I211 Gigabit Network Connection                                          | 100      | 3.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 89       | 2.82%   |
| Intel Ethernet Controller I225-V                                               | 79       | 2.5%    |
| Intel Ethernet Connection (2) I219-V                                           | 65       | 2.06%   |
| Intel Ethernet Connection I217-LM                                              | 62       | 1.97%   |
| Intel I210 Gigabit Network Connection                                          | 59       | 1.87%   |
| Intel 82579V Gigabit Network Connection                                        | 39       | 1.24%   |
| Intel 82574L Gigabit Network Connection                                        | 39       | 1.24%   |
| Intel Ethernet Connection (14) I219-V                                          | 37       | 1.17%   |
| Intel Ethernet Connection (7) I219-V                                           | 33       | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                                          | 30       | 0.95%   |
| Nvidia MCP61 Ethernet                                                          | 29       | 0.92%   |
| Intel Ethernet Connection I217-V                                               | 29       | 0.92%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 24       | 0.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 22       | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 22       | 0.7%    |
| Intel Ethernet Controller X550                                                 | 21       | 0.67%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                           | 20       | 0.63%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 19       | 0.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 18       | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 18       | 0.57%   |
| Intel I350 Gigabit Network Connection                                          | 18       | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                                          | 18       | 0.57%   |
| Intel Ethernet Connection (2) I218-V                                           | 18       | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 17       | 0.54%   |
| Intel Ethernet Controller I226-V                                               | 17       | 0.54%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 16       | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 16       | 0.51%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                               | 14       | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 13       | 0.41%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 13       | 0.41%   |
| American Megatrends Virtual Ethernet.                                          | 13       | 0.41%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 12       | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 11       | 0.35%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 11       | 0.35%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 11       | 0.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 10       | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2705     | 75.62%  |
| WiFi     | 818      | 22.87%  |
| Modem    | 50       | 1.4%    |
| Unknown  | 4        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2381     | 87.92%  |
| WiFi     | 327      | 12.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1771     | 64.78%  |
| 2     | 694      | 25.38%  |
| 3     | 159      | 5.82%   |
| 4     | 41       | 1.5%    |
| 5     | 21       | 0.77%   |
| 6     | 16       | 0.59%   |
| 0     | 12       | 0.44%   |
| 7     | 7        | 0.26%   |
| 8     | 6        | 0.22%   |
| 9     | 3        | 0.11%   |
| 12    | 2        | 0.07%   |
| 17    | 1        | 0.04%   |
| 13    | 1        | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2230     | 81.27%  |
| Yes  | 514      | 18.73%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 305      | 45.86%  |
| Cambridge Silicon Radio         | 146      | 21.95%  |
| Realtek Semiconductor           | 54       | 8.12%   |
| ASUSTek Computer                | 36       | 5.41%   |
| Broadcom                        | 30       | 4.51%   |
| MediaTek                        | 24       | 3.61%   |
| Qualcomm Atheros Communications | 23       | 3.46%   |
| IMC Networks                    | 15       | 2.26%   |
| TP-Link                         | 5        | 0.75%   |
| Foxconn / Hon Hai               | 5        | 0.75%   |
| Apple                           | 4        | 0.6%    |
| Lite-On Technology              | 3        | 0.45%   |
| Realtek                         | 2        | 0.3%    |
| Belkin Components               | 2        | 0.3%    |
| Toshiba                         | 1        | 0.15%   |
| Sitecom Europe                  | 1        | 0.15%   |
| SINO WEALTH                     | 1        | 0.15%   |
| Microsoft                       | 1        | 0.15%   |
| Micro Star International        | 1        | 0.15%   |
| Integrated System Solution      | 1        | 0.15%   |
| Hewlett-Packard                 | 1        | 0.15%   |
| Edimax Technology               | 1        | 0.15%   |
| Dynex                           | 1        | 0.15%   |
| Actions                         | 1        | 0.15%   |
| Unknown                         | 1        | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 146      | 21.92%  |
| Intel Bluetooth wireless interface                        | 85       | 12.76%  |
| Intel AX200 Bluetooth                                     | 84       | 12.61%  |
| Realtek Bluetooth Radio                                   | 44       | 6.61%   |
| Intel Wireless-AC 3168 Bluetooth                          | 30       | 4.5%    |
| Intel AX201 Bluetooth                                     | 28       | 4.2%    |
| Intel AX210 Bluetooth                                     | 25       | 3.75%   |
| MediaTek Wireless_Device                                  | 24       | 3.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 20       | 3%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 16       | 2.4%    |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 16       | 2.4%    |
| Intel Bluetooth Device                                    | 13       | 1.95%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 12       | 1.8%    |
| ASUS ASUS USB-BT500                                       | 9        | 1.35%   |
| Realtek  Bluetooth 4.2 Adapter                            | 8        | 1.2%    |
| IMC Networks Bluetooth Radio                              | 8        | 1.2%    |
| Qualcomm Atheros AR9462 Bluetooth                         | 7        | 1.05%   |
| Qualcomm Atheros  Bluetooth Device                        | 6        | 0.9%    |
| TP-Link TP-T@- UB500 Adapter                              | 5        | 0.75%   |
| Qualcomm Atheros Bluetooth USB Host Controller            | 5        | 0.75%   |
| ASUS Bluetooth Radio                                      | 5        | 0.75%   |
| Intel Centrino Bluetooth Wireless Transceiver             | 4        | 0.6%    |
| IMC Networks Bluetooth Device                             | 4        | 0.6%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE     | 3        | 0.45%   |
| Realtek Bluetooth Radio                                   | 2        | 0.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                    | 2        | 0.3%    |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)           | 2        | 0.3%    |
| Lite-On Bluetooth Device                                  | 2        | 0.3%    |
| IMC Networks Wireless_Device                              | 2        | 0.3%    |
| Foxconn / Hon Hai Wireless_Device                         | 2        | 0.3%    |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter          | 2        | 0.3%    |
| Broadcom BCM43142A0 Bluetooth 4.0                         | 2        | 0.3%    |
| Broadcom BCM2045 Bluetooth                                | 2        | 0.3%    |
| ASUS Bluetooth Device                                     | 2        | 0.3%    |
| ASUS Bluetooth Adapter                                    | 2        | 0.3%    |
| ASUS BCM20702A0                                           | 2        | 0.3%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                      | 2        | 0.3%    |
| Apple Bluetooth Host Controller                           | 2        | 0.3%    |
| Toshiba Atheros AR3012 Bluetooth                          | 1        | 0.15%   |
| Sitecom Europe Sitecom bluetooth2.0 class 1 dongle CN-521 | 1        | 0.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1782     | 44.91%  |
| AMD                                          | 870      | 21.93%  |
| Nvidia                                       | 839      | 21.14%  |
| C-Media Electronics                          | 82       | 2.07%   |
| Logitech                                     | 38       | 0.96%   |
| Creative Labs                                | 36       | 0.91%   |
| ASUSTek Computer                             | 26       | 0.66%   |
| KTMicro                                      | 25       | 0.63%   |
| Generalplus Technology                       | 16       | 0.4%    |
| VIA Technologies                             | 15       | 0.38%   |
| Texas Instruments                            | 15       | 0.38%   |
| Focusrite-Novation                           | 13       | 0.33%   |
| Creative Technology                          | 13       | 0.33%   |
| Micro Star International                     | 11       | 0.28%   |
| Kingston Technology                          | 9        | 0.23%   |
| JMTek                                        | 9        | 0.23%   |
| GN Netcom                                    | 9        | 0.23%   |
| SteelSeries ApS                              | 8        | 0.2%    |
| Plantronics                                  | 7        | 0.18%   |
| Zoran Co. Personal Media Division (Nogatech) | 6        | 0.15%   |
| RODE Microphones                             | 6        | 0.15%   |
| GYROCOM C&C                                  | 6        | 0.15%   |
| Yamaha                                       | 5        | 0.13%   |
| Samson Technologies                          | 5        | 0.13%   |
| Razer USA                                    | 5        | 0.13%   |
| Giga-Byte Technology                         | 5        | 0.13%   |
| Dell                                         | 5        | 0.13%   |
| BEHRINGER International                      | 5        | 0.13%   |
| Silicon Integrated Systems [SiS]             | 4        | 0.1%    |
| Cambridge Silicon Radio                      | 4        | 0.1%    |
| TerraTec Electronic                          | 3        | 0.08%   |
| Tenx Technology                              | 3        | 0.08%   |
| Realtek Semiconductor                        | 3        | 0.08%   |
| M-Audio                                      | 3        | 0.08%   |
| Ensoniq                                      | 3        | 0.08%   |
| DSEA A/S                                     | 3        | 0.08%   |
| Corsair                                      | 3        | 0.08%   |
| Blue Microphones                             | 3        | 0.08%   |
| XMOS                                         | 2        | 0.05%   |
| Valve Software                               | 2        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 256      | 5.57%   |
| AMD Starship/Matisse HD Audio Controller                                   | 213      | 4.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 206      | 4.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 191      | 4.15%   |
| AMD Ryzen HD Audio Controller                                              | 160      | 3.48%   |
| Intel 200 Series PCH HD Audio                                              | 157      | 3.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 146      | 3.17%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 143      | 3.11%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 141      | 3.07%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 115      | 2.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 92       | 2%      |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 89       | 1.94%   |
| Nvidia GF108 High Definition Audio Controller                              | 83       | 1.8%    |
| Nvidia GP107GL High Definition Audio Controller                            | 78       | 1.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 74       | 1.61%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 72       | 1.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 71       | 1.54%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 67       | 1.46%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 63       | 1.37%   |
| AMD FCH Azalia Controller                                                  | 62       | 1.35%   |
| Intel Comet Lake PCH cAVS                                                  | 55       | 1.2%    |
| Intel Alder Lake-S HD Audio Controller                                     | 54       | 1.17%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 47       | 1.02%   |
| Intel Jasper Lake HD Audio                                                 | 46       | 1%      |
| Nvidia GP106 High Definition Audio Controller                              | 45       | 0.98%   |
| Nvidia High Definition Audio Controller                                    | 42       | 0.91%   |
| Intel Smart Sound Technology (SST) Audio Controller                        | 42       | 0.91%   |
| Nvidia TU106 High Definition Audio Controller                              | 38       | 0.83%   |
| Nvidia GP108 High Definition Audio Controller                              | 38       | 0.83%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 37       | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                              | 36       | 0.78%   |
| Nvidia GP104 High Definition Audio Controller                              | 36       | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 36       | 0.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 35       | 0.76%   |
| Intel Comet Lake PCH-V cAVS                                                | 34       | 0.74%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 33       | 0.72%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 33       | 0.72%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 32       | 0.7%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 32       | 0.7%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 31       | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 473      | 17.51%  |
| Unknown                      | 399      | 14.77%  |
| Crucial                      | 319      | 11.81%  |
| Samsung Electronics          | 291      | 10.77%  |
| SK hynix                     | 249      | 9.22%   |
| Corsair                      | 224      | 8.29%   |
| G.Skill                      | 149      | 5.52%   |
| Micron Technology            | 114      | 4.22%   |
| Patriot                      | 70       | 2.59%   |
| A-DATA Technology            | 47       | 1.74%   |
| Unknown                      | 40       | 1.48%   |
| Team                         | 25       | 0.93%   |
| Hikvision                    | 22       | 0.81%   |
| Unknown (ABCD)               | 21       | 0.78%   |
| Ramaxel Technology           | 21       | 0.78%   |
| AMD                          | 18       | 0.67%   |
| Nanya Technology             | 17       | 0.63%   |
| Elpida                       | 16       | 0.59%   |
| Transcend                    | 11       | 0.41%   |
| Timetec                      | 11       | 0.41%   |
| GOODRAM                      | 11       | 0.41%   |
| Smart                        | 9        | 0.33%   |
| GeIL                         | 8        | 0.3%    |
| Apacer                       | 7        | 0.26%   |
| Unknown (0x5846)             | 6        | 0.22%   |
| Hewlett-Packard              | 6        | 0.22%   |
| Avant                        | 6        | 0.22%   |
| Unknown (AB)                 | 5        | 0.19%   |
| Qimonda                      | 5        | 0.19%   |
| Unknown (0x0DD5)             | 4        | 0.15%   |
| PNY                          | 4        | 0.15%   |
| Unknown (0x0B45)             | 3        | 0.11%   |
| Unifosa                      | 3        | 0.11%   |
| Toshiba                      | 3        | 0.11%   |
| Silicon Power                | 3        | 0.11%   |
| Patriot Memory (PDP Systems) | 3        | 0.11%   |
| Kingmax                      | 3        | 0.11%   |
| Kimtigo                      | 3        | 0.11%   |
| Wilk                         | 2        | 0.07%   |
| V-Color                      | 2        | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM SDRAM                              | 46       | 1.55%   |
| Unknown                                                        | 40       | 1.35%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s          | 36       | 1.21%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2667MT/s          | 31       | 1.04%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s         | 29       | 0.98%   |
| Unknown RAM Module 1GB DIMM SDRAM                              | 27       | 0.91%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 3600MT/s           | 24       | 0.81%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 23       | 0.77%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 23       | 0.77%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s | 21       | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 20       | 0.67%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 20       | 0.67%   |
| Hikvision RAM HKED4161DAA1D0MA1 16GB DIMM DDR4 2667MT/s        | 20       | 0.67%   |
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s          | 18       | 0.61%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 17       | 0.57%   |
| Unknown RAM Module 1GB DIMM 800MT/s                            | 16       | 0.54%   |
| Patriot RAM PSD34G160081 4GB DIMM DDR3 1600MT/s                | 16       | 0.54%   |
| Kingston RAM KHX2666C16/8G 8GiB DIMM DDR4 3466MT/s             | 15       | 0.5%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 14       | 0.47%   |
| Patriot RAM PSD32G13332 2GB DIMM DDR3 1333MT/s                 | 14       | 0.47%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 2133MT/s            | 13       | 0.44%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s          | 13       | 0.44%   |
| Unknown RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s           | 12       | 0.4%    |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s            | 12       | 0.4%    |
| Crucial RAM CT8G4DFRA32A.M4FE 8GB DIMM DDR4 3200MT/s           | 12       | 0.4%    |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3600MT/s         | 12       | 0.4%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3600MT/s          | 12       | 0.4%    |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3600MT/s         | 11       | 0.37%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 10       | 0.34%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                           | 10       | 0.34%   |
| Unknown RAM Module 1GB DIMM                                    | 10       | 0.34%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 10       | 0.34%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 10       | 0.34%   |
| Crucial RAM CT8G4DFD8213.C16FAR2 8GB DIMM DDR4 2133MT/s        | 10       | 0.34%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                      | 9        | 0.3%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                      | 9        | 0.3%    |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s          | 9        | 0.3%    |
| Kingston RAM 99U5474-013.A00LF 2GB DIMM DDR3 1600MT/s          | 9        | 0.3%    |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 2667MT/s         | 9        | 0.3%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 8        | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 1090     | 45.4%   |
| DDR3         | 805      | 33.53%  |
| Unknown      | 159      | 6.62%   |
| SDRAM        | 144      | 6%      |
| DDR2         | 106      | 4.41%   |
| LPDDR4       | 33       | 1.37%   |
| DDR5         | 30       | 1.25%   |
| DDR          | 25       | 1.04%   |
| DRAM         | 8        | 0.33%   |
| DDR2 FB-DIMM | 1        | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 2102     | 88.95%  |
| SODIMM       | 234      | 9.9%    |
| Row Of Chips | 12       | 0.51%   |
| RIMM         | 8        | 0.34%   |
| FB-DIMM      | 4        | 0.17%   |
| Unknown      | 2        | 0.08%   |
| Chip         | 1        | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Desktops | Percent |
|---------|----------|---------|
| 8192    | 826      | 31.61%  |
| 4096    | 591      | 22.62%  |
| 16384   | 420      | 16.07%  |
| 2048    | 404      | 15.46%  |
| 32768   | 194      | 7.42%   |
| 1024    | 130      | 4.98%   |
| 512     | 30       | 1.15%   |
| 256     | 7        | 0.27%   |
| 65536   | 4        | 0.15%   |
| 12288   | 2        | 0.08%   |
| 3072    | 1        | 0.04%   |
| 1536    | 1        | 0.04%   |
| 128     | 1        | 0.04%   |
| 16      | 1        | 0.04%   |
| Unknown | 1        | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 457      | 17.42%  |
| 1333    | 287      | 10.94%  |
| 2667    | 249      | 9.49%   |
| 3200    | 228      | 8.69%   |
| 3600    | 178      | 6.79%   |
| 2400    | 160      | 6.1%    |
| 2133    | 136      | 5.18%   |
| 800     | 103      | 3.93%   |
| Unknown | 103      | 3.93%   |
| 1866    | 81       | 3.09%   |
| 667     | 53       | 2.02%   |
| 2666    | 42       | 1.6%    |
| 3733    | 38       | 1.45%   |
| 3000    | 34       | 1.3%    |
| 1800    | 31       | 1.18%   |
| 1066    | 31       | 1.18%   |
| 1867    | 29       | 1.11%   |
| 1067    | 29       | 1.11%   |
| 3400    | 28       | 1.07%   |
| 3800    | 27       | 1.03%   |
| 3466    | 26       | 0.99%   |
| 2933    | 24       | 0.91%   |
| 4000    | 22       | 0.84%   |
| 4800    | 16       | 0.61%   |
| 3933    | 13       | 0.5%    |
| 1334    | 13       | 0.5%    |
| 400     | 13       | 0.5%    |
| 533     | 10       | 0.38%   |
| 3100    | 9        | 0.34%   |
| 2048    | 9        | 0.34%   |
| 3266    | 8        | 0.3%    |
| 1648    | 8        | 0.3%    |
| 4333    | 7        | 0.27%   |
| 1639    | 7        | 0.27%   |
| 3866    | 6        | 0.23%   |
| 3500    | 6        | 0.23%   |
| 2800    | 6        | 0.23%   |
| 2733    | 6        | 0.23%   |
| 6000    | 5        | 0.19%   |
| 5200    | 5        | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 39       | 36.79%  |
| Brother Industries     | 20       | 18.87%  |
| Canon                  | 11       | 10.38%  |
| Samsung Electronics    | 8        | 7.55%   |
| Seiko Epson            | 4        | 3.77%   |
| Xerox                  | 3        | 2.83%   |
| Lexmark International  | 3        | 2.83%   |
| Dymo-CoStar            | 3        | 2.83%   |
| Zebra                  | 2        | 1.89%   |
| Prolific Technology    | 2        | 1.89%   |
| Pantum                 | 2        | 1.89%   |
| STMicroelectronics     | 1        | 0.94%   |
| Ricoh                  | 1        | 0.94%   |
| QinHeng Electronics    | 1        | 0.94%   |
| Printer                | 1        | 0.94%   |
| Kyocera                | 1        | 0.94%   |
| Konica Minolta         | 1        | 0.94%   |
| GODEX INTERNATIONAL    | 1        | 0.94%   |
| Custom Engineering SPA | 1        | 0.94%   |
| Apple                  | 1        | 0.94%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP LaserJet 1200                                          | 5        | 4.72%   |
| Xerox B205                                                | 3        | 2.83%   |
| Samsung ML-1660 Series                                    | 3        | 2.83%   |
| HP LaserJet 1020                                          | 3        | 2.83%   |
| HP HP LaserJet M101-M106                                  | 3        | 2.83%   |
| Prolific PL2305 Parallel Port                             | 2        | 1.89%   |
| HP LaserJet P1005                                         | 2        | 1.89%   |
| HP ENVY 4520 series                                       | 2        | 1.89%   |
| HP DeskJet 2700 series                                    | 2        | 1.89%   |
| Canon MF4410                                              | 2        | 1.89%   |
| Brother MFC-7460DN                                        | 2        | 1.89%   |
| Zebra ZTC ZP 500 (ZPL)                                    | 1        | 0.94%   |
| Zebra ZTC ZD420-203dpi ZPL                                | 1        | 0.94%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.94%   |
| Seiko Epson M105 Series                                   | 1        | 0.94%   |
| Seiko Epson ET-2710 Series                                | 1        | 0.94%   |
| Seiko Epson ET-2700 Series                                | 1        | 0.94%   |
| Seiko Epson EPSON XP-205 207 Series                       | 1        | 0.94%   |
| Samsung SCX-4x26 Series                                   | 1        | 0.94%   |
| Samsung SCX-4650 4x21S Series                             | 1        | 0.94%   |
| Samsung SCX-3200 Series                                   | 1        | 0.94%   |
| Samsung ML-216x Series Laser Printer                      | 1        | 0.94%   |
| Samsung CLP-310 Color Laser Printer                       | 1        | 0.94%   |
| Ricoh SP 211                                              | 1        | 0.94%   |
| QinHeng CH340S                                            | 1        | 0.94%   |
| Printer Printer                                           | 1        | 0.94%   |
| Pantum P2500W series                                      | 1        | 0.94%   |
| Pantum M6500-series                                       | 1        | 0.94%   |
| Lexmark International MS710                               | 1        | 0.94%   |
| Lexmark International Laser Printer                       | 1        | 0.94%   |
| Lexmark International B2338dw                             | 1        | 0.94%   |
| Kyocera ECOSYS M5521cdn                                   | 1        | 0.94%   |
| Konica Minolta bizhub 4402P                               | 1        | 0.94%   |
| HP Officejet J4500 series                                 | 1        | 0.94%   |
| HP Officejet 7110 series                                  | 1        | 0.94%   |
| HP LaserJet Pro M148-M149                                 | 1        | 0.94%   |
| HP LaserJet P2055 series                                  | 1        | 0.94%   |
| HP Laserjet P1505                                         | 1        | 0.94%   |
| HP LaserJet P1006                                         | 1        | 0.94%   |
| HP LaserJet M14-M17                                       | 1        | 0.94%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 14       | 58.33%  |
| Seiko Epson     | 4        | 16.67%  |
| Hewlett-Packard | 3        | 12.5%   |
| AGFA-Gevaert NV | 2        | 8.33%   |
| Mustek Systems  | 1        | 4.17%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                            | 3        | 12.5%   |
| Canon CanoScan LiDE 220                                       | 3        | 12.5%   |
| Canon CanoScan LiDE 210                                       | 2        | 8.33%   |
| Canon CanoScan LiDE 110                                       | 2        | 8.33%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 2        | 8.33%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 1        | 4.17%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1        | 4.17%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]      | 1        | 4.17%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 4.17%   |
| Mustek Systems SNAPSCAN e22                                   | 1        | 4.17%   |
| HP ScanJet Pro 2500 f1                                        | 1        | 4.17%   |
| HP ScanJet 3970c                                              | 1        | 4.17%   |
| HP HP Scanjet 300                                             | 1        | 4.17%   |
| Canon CanoScan LiDE 60                                        | 1        | 4.17%   |
| Canon CanoScan 8800F                                          | 1        | 4.17%   |
| Canon CanoScan 5600F                                          | 1        | 4.17%   |
| Canon CanoScan 4400F                                          | 1        | 4.17%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 146      | 40.78%  |
| Microdia                               | 24       | 6.7%    |
| Generalplus Technology                 | 18       | 5.03%   |
| Sunplus Innovation Technology          | 16       | 4.47%   |
| Microsoft                              | 15       | 4.19%   |
| Creative Technology                    | 12       | 3.35%   |
| Jieli Technology                       | 10       | 2.79%   |
| Apple                                  | 10       | 2.79%   |
| Samsung Electronics                    | 9        | 2.51%   |
| KYE Systems (Mouse Systems)            | 7        | 1.96%   |
| ARC International                      | 6        | 1.68%   |
| Z-Star Microelectronics                | 5        | 1.4%    |
| GEMBIRD                                | 5        | 1.4%    |
| Chicony Electronics                    | 5        | 1.4%    |
| Novatek Microelectronics               | 3        | 0.84%   |
| MacroSilicon                           | 3        | 0.84%   |
| Google                                 | 3        | 0.84%   |
| Genesys Logic                          | 3        | 0.84%   |
| AVerMedia Technologies                 | 3        | 0.84%   |
| Xiongmai                               | 2        | 0.56%   |
| webcam                                 | 2        | 0.56%   |
| Valve Software                         | 2        | 0.56%   |
| SunplusIT                              | 2        | 0.56%   |
| SHENZHEN EMEET TECHNOLOGY              | 2        | 0.56%   |
| Realtek Semiconductor                  | 2        | 0.56%   |
| Razer USA                              | 2        | 0.56%   |
| Nintendo                               | 2        | 0.56%   |
| Cubeternet                             | 2        | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) | 2        | 0.56%   |
| Aveo Technology                        | 2        | 0.56%   |
| Arkmicro Technologies                  | 2        | 0.56%   |
| Xiaomi                                 | 1        | 0.28%   |
| WaveRider Communications               | 1        | 0.28%   |
| ValueHD                                | 1        | 0.28%   |
| USB3.0 HD Audio Capture                | 1        | 0.28%   |
| Unknown                                | 1        | 0.28%   |
| Trust                                  | 1        | 0.28%   |
| Tobii Technology AB                    | 1        | 0.28%   |
| Syntek                                 | 1        | 0.28%   |
| Sunplus IT                             | 1        | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Logitech Webcam C270                                  | 49       | 13.61%  |
| Logitech C922 Pro Stream Webcam                       | 15       | 4.17%   |
| Logitech HD Pro Webcam C920                           | 14       | 3.89%   |
| Generalplus GENERAL WEBCAM                            | 12       | 3.33%   |
| Jieli USB PHY 2.0                                     | 10       | 2.78%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                       | 10       | 2.78%   |
| Samsung Galaxy series, misc. (MTP mode)               | 9        | 2.5%    |
| Microsoft LifeCam HD-3000                             | 8        | 2.22%   |
| Microdia Webcam Vitade AF                             | 8        | 2.22%   |
| Microdia USB 2.0 Camera                               | 7        | 1.94%   |
| Logitech Webcam C310                                  | 7        | 1.94%   |
| Logitech Webcam C170                                  | 7        | 1.94%   |
| Logitech HD Webcam C615                               | 7        | 1.94%   |
| Logitech C920 PRO HD Webcam                           | 6        | 1.67%   |
| Sunplus Integrated Camera                             | 5        | 1.39%   |
| Sunplus Full HD webcam                                | 5        | 1.39%   |
| Logitech HD Webcam C525                               | 5        | 1.39%   |
| Z-Star Venus USB2.0 Camera                            | 4        | 1.11%   |
| ARC International Camera                              | 4        | 1.11%   |
| Novatek HP High Definition 2MP Webcam                 | 3        | 0.83%   |
| Logitech Logitech Webcam C925e                        | 3        | 0.83%   |
| Logitech Logi Webcam C920e                            | 3        | 0.83%   |
| Logitech HD Webcam C910                               | 3        | 0.83%   |
| Logitech BRIO Ultra HD Webcam                         | 3        | 0.83%   |
| KYE Systems (Mouse Systems) USB 2.0 HD1080P PC Camera | 3        | 0.83%   |
| KYE Systems (Mouse Systems) Genius Webcam             | 3        | 0.83%   |
| Generalplus WEB CAM                                   | 3        | 0.83%   |
| Generalplus 808 Camera #9 (web-cam mode)              | 3        | 0.83%   |
| Creative Live! Cam Chat HD [VF0700/VF0790]            | 3        | 0.83%   |
| Xiongmai web camera                                   | 2        | 0.56%   |
| webcam webcam                                         | 2        | 0.56%   |
| Valve Software 3D Camera                              | 2        | 0.56%   |
| SHENZHEN EMEET TECHNOLOGY HD Webcam eMeet C960        | 2        | 0.56%   |
| Razer USA Gaming Webcam [Kiyo]                        | 2        | 0.56%   |
| Nintendo USB Camera                                   | 2        | 0.56%   |
| Microsoft LifeCam HD-5000                             | 2        | 0.56%   |
| Microsoft LifeCam Cinema                              | 2        | 0.56%   |
| Microdia Sonix USB 2.0 Camera                         | 2        | 0.56%   |
| Microdia Camera                                       | 2        | 0.56%   |
| Logitech StreamCam                                    | 2        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Desktops | Percent |
|------------------|----------|---------|
| Validity Sensors | 1        | 50%     |
| Synaptics        | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor | 1        | 50%     |
| Synaptics  WBDI Fingerprint Reader - USB 052 | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| SCM Microsystems         | 3        | 16.67%  |
| Alcor Micro              | 3        | 16.67%  |
| Gemalto (was Gemplus)    | 2        | 11.11%  |
| Yubico.com               | 1        | 5.56%   |
| Reiner SCT Kartensysteme | 1        | 5.56%   |
| Realtek Semiconductor    | 1        | 5.56%   |
| Lenovo                   | 1        | 5.56%   |
| Feitian Technologies     | 1        | 5.56%   |
| CREATOR                  | 1        | 5.56%   |
| Clay Logic               | 1        | 5.56%   |
| Chicony Electronics      | 1        | 5.56%   |
| Cherry                   | 1        | 5.56%   |
| Advanced Card Systems    | 1        | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 2        | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                                        | 2        | 11.11%  |
| Yubico.com Yubikey 4/5 CCID                                                | 1        | 5.56%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                | 1        | 5.56%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 5.56%   |
| Realtek Semiconductor Smart Card Reader Interface                          | 1        | 5.56%   |
| Lenovo Smartcard Keyboard                                                  | 1        | 5.56%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 1        | 5.56%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 5.56%   |
| Feitian Technologies SCR301                                                | 1        | 5.56%   |
| CREATOR CRT-603(CZ1) CCR                                                   | 1        | 5.56%   |
| Clay Logic Nitrokey Pro                                                    | 1        | 5.56%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 1        | 5.56%   |
| Cherry SmartTerminal XX1X                                                  | 1        | 5.56%   |
| Alcor Micro Watchdata W 1981                                               | 1        | 5.56%   |
| Advanced Card Systems ACR39U                                               | 1        | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1614     | 58.63%  |
| 1     | 987      | 35.85%  |
| 2     | 130      | 4.72%   |
| 3     | 17       | 0.62%   |
| 4     | 3        | 0.11%   |
| 7     | 1        | 0.04%   |
| 5     | 1        | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 939      | 75.36%  |
| Net/wireless             | 112      | 8.99%   |
| Communication controller | 51       | 4.09%   |
| Unassigned class         | 42       | 3.37%   |
| Sound                    | 21       | 1.69%   |
| Multimedia controller    | 15       | 1.2%    |
| Bluetooth                | 15       | 1.2%    |
| Camera                   | 10       | 0.8%    |
| Chipcard                 | 8        | 0.64%   |
| Net/ethernet             | 7        | 0.56%   |
| Card reader              | 7        | 0.56%   |
| Storage/raid             | 5        | 0.4%    |
| Tv card                  | 3        | 0.24%   |
| Modem                    | 3        | 0.24%   |
| Network                  | 2        | 0.16%   |
| Fingerprint reader       | 2        | 0.16%   |
| Dvb card                 | 2        | 0.16%   |
| Storage/nvme             | 1        | 0.08%   |
| Storage                  | 1        | 0.08%   |

