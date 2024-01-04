Ubuntu 22.04 - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

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

Total: 7227

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | J5005-ITX                   | [5373e7f16c](https://linux-hardware.org/?probe=5373e7f16c) | Jan 02, 2024 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [3a67df5dcf](https://linux-hardware.org/?probe=3a67df5dcf) | Jan 02, 2024 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [b163926938](https://linux-hardware.org/?probe=b163926938) | Jan 02, 2024 |
| ASUSTek       | H81M-C                      | [221ebe85fb](https://linux-hardware.org/?probe=221ebe85fb) | Jan 02, 2024 |
| Dell          | 0XJ8C4 A00                  | [e902f5396d](https://linux-hardware.org/?probe=e902f5396d) | Jan 02, 2024 |
| MSI           | Z77A-G43                    | [b33c14ee42](https://linux-hardware.org/?probe=b33c14ee42) | Jan 02, 2024 |
| MSI           | X79A-GD65                   | [ecb9a57738](https://linux-hardware.org/?probe=ecb9a57738) | Jan 01, 2024 |
| ASRock        | B450M Gaming                | [81242d3eca](https://linux-hardware.org/?probe=81242d3eca) | Jan 01, 2024 |
| ASUSTek       | P8H67-M LE                  | [82877fbf5e](https://linux-hardware.org/?probe=82877fbf5e) | Jan 01, 2024 |
| HP            | 82A2                        | [7cc3d17916](https://linux-hardware.org/?probe=7cc3d17916) | Jan 01, 2024 |
| Gigabyte      | H270N-WIFI-CF               | [d47bc3897f](https://linux-hardware.org/?probe=d47bc3897f) | Jan 01, 2024 |
| Medion        | H110H4-EM                   | [da3367c80e](https://linux-hardware.org/?probe=da3367c80e) | Jan 01, 2024 |
| Dell          | 0D24M8 A01                  | [f363c3e115](https://linux-hardware.org/?probe=f363c3e115) | Jan 01, 2024 |
| Lenovo        | SHARKBAY SDK0E50519 WIN     | [fc9ced99d5](https://linux-hardware.org/?probe=fc9ced99d5) | Jan 01, 2024 |
| Dell          | 09KPNV A01                  | [d6c27424e2](https://linux-hardware.org/?probe=d6c27424e2) | Jan 01, 2024 |
| Centerm       | C92                         | [5ede09f987](https://linux-hardware.org/?probe=5ede09f987) | Jan 01, 2024 |
| Centerm       | C92                         | [0201370bf4](https://linux-hardware.org/?probe=0201370bf4) | Jan 01, 2024 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [6dbc709464](https://linux-hardware.org/?probe=6dbc709464) | Jan 01, 2024 |
| ASRock        | X399 Professional Gaming    | [2d812c76d3](https://linux-hardware.org/?probe=2d812c76d3) | Jan 01, 2024 |
| ASRock        | B450M Pro4                  | [126f6b0c9c](https://linux-hardware.org/?probe=126f6b0c9c) | Dec 31, 2023 |
| ASRock        | B450M Pro4                  | [8625e5d1fa](https://linux-hardware.org/?probe=8625e5d1fa) | Dec 31, 2023 |
| MSI           | B550-A PRO                  | [3b6183bbb5](https://linux-hardware.org/?probe=3b6183bbb5) | Dec 31, 2023 |
| Foxconn       | 2ADA                        | [ae6e6ab09f](https://linux-hardware.org/?probe=ae6e6ab09f) | Dec 31, 2023 |
| HP            | 18E9                        | [298cd92eb1](https://linux-hardware.org/?probe=298cd92eb1) | Dec 31, 2023 |
| ZOTAC         | NM10                        | [c0f4135bd0](https://linux-hardware.org/?probe=c0f4135bd0) | Dec 31, 2023 |
| MACHINIST     | X99-D8-MAX V1.0             | [ef584ae5a8](https://linux-hardware.org/?probe=ef584ae5a8) | Dec 31, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [fda4d32a86](https://linux-hardware.org/?probe=fda4d32a86) | Dec 31, 2023 |
| Dell          | 0C2XKD A01                  | [5e36d4fb43](https://linux-hardware.org/?probe=5e36d4fb43) | Dec 31, 2023 |
| ASUSTek       | P8H67-M PRO                 | [63d62dd94e](https://linux-hardware.org/?probe=63d62dd94e) | Dec 31, 2023 |
| HP            | ProLiant ML110 Gen9         | [0181b68b4a](https://linux-hardware.org/?probe=0181b68b4a) | Dec 31, 2023 |
| ASUSTek       | P8H67-M PRO                 | [6a45d6cf9e](https://linux-hardware.org/?probe=6a45d6cf9e) | Dec 30, 2023 |
| Gigabyte      | A620I AX                    | [7f73790fbf](https://linux-hardware.org/?probe=7f73790fbf) | Dec 30, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [af479728a3](https://linux-hardware.org/?probe=af479728a3) | Dec 30, 2023 |
| ASUSTek       | PRIME X470-PRO              | [495efd257e](https://linux-hardware.org/?probe=495efd257e) | Dec 30, 2023 |
| Unknown       | Unknown                     | [e6e8bd6545](https://linux-hardware.org/?probe=e6e8bd6545) | Dec 30, 2023 |
| MSI           | B350 KRAIT GAMING           | [a4582db0da](https://linux-hardware.org/?probe=a4582db0da) | Dec 30, 2023 |
| DFI           | LP DK 790FXB-M2RS           | [8d0c82bedc](https://linux-hardware.org/?probe=8d0c82bedc) | Dec 30, 2023 |
| HP            | ProLiant ML110 Gen9         | [4cb0683071](https://linux-hardware.org/?probe=4cb0683071) | Dec 30, 2023 |
| Lenovo        | 30BD NOK                    | [033b3c8abd](https://linux-hardware.org/?probe=033b3c8abd) | Dec 30, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e14a6e4044](https://linux-hardware.org/?probe=e14a6e4044) | Dec 30, 2023 |
| Dell          | 0V8WGR A00                  | [88a9972a33](https://linux-hardware.org/?probe=88a9972a33) | Dec 30, 2023 |
| Dell          | 0V8WGR A00                  | [91be04698f](https://linux-hardware.org/?probe=91be04698f) | Dec 30, 2023 |
| Dell          | 09KPNV A01                  | [115ec4e7a9](https://linux-hardware.org/?probe=115ec4e7a9) | Dec 29, 2023 |
| HP            | 304Ah                       | [0a84d8bd4a](https://linux-hardware.org/?probe=0a84d8bd4a) | Dec 29, 2023 |
| Gigabyte      | 990FXA-UD3                  | [9104adc237](https://linux-hardware.org/?probe=9104adc237) | Dec 29, 2023 |
| Shenzhen M... | AHBNB OEM                   | [9883edd543](https://linux-hardware.org/?probe=9883edd543) | Dec 29, 2023 |
| Supermicro    | X10DDW-i                    | [36b4cb3de7](https://linux-hardware.org/?probe=36b4cb3de7) | Dec 29, 2023 |
| Supermicro    | X10DDW-i                    | [7accaaedbb](https://linux-hardware.org/?probe=7accaaedbb) | Dec 29, 2023 |
| Supermicro    | X10DDW-i                    | [5d7ab2ff4b](https://linux-hardware.org/?probe=5d7ab2ff4b) | Dec 29, 2023 |
| Supermicro    | X10DDW-i                    | [be9b9577fd](https://linux-hardware.org/?probe=be9b9577fd) | Dec 29, 2023 |
| Supermicro    | X10DDW-i                    | [4f7ea59b94](https://linux-hardware.org/?probe=4f7ea59b94) | Dec 29, 2023 |
| ASUSTek       | X99-DELUXE                  | [2433b4bc75](https://linux-hardware.org/?probe=2433b4bc75) | Dec 29, 2023 |
| Dell          | 00V62H A01                  | [0032f131d1](https://linux-hardware.org/?probe=0032f131d1) | Dec 29, 2023 |
| MSI           | H110M PRO-VD                | [318343d58b](https://linux-hardware.org/?probe=318343d58b) | Dec 29, 2023 |
| ASUSTek       | PRIME A520M-E               | [3133f699e1](https://linux-hardware.org/?probe=3133f699e1) | Dec 29, 2023 |
| Dell          | 096JG8 A01                  | [915a028a6a](https://linux-hardware.org/?probe=915a028a6a) | Dec 29, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [51ab2c0529](https://linux-hardware.org/?probe=51ab2c0529) | Dec 29, 2023 |
| Inventec      | VXC Class A02               | [0575404de8](https://linux-hardware.org/?probe=0575404de8) | Dec 29, 2023 |
| ASUSTek       | PRIME B365M-A               | [2109440c5e](https://linux-hardware.org/?probe=2109440c5e) | Dec 29, 2023 |
| ASUSTek       | PRIME B365M-A               | [69ed200761](https://linux-hardware.org/?probe=69ed200761) | Dec 29, 2023 |
| MSI           | H110M PRO-VD                | [1c6ef1eeb0](https://linux-hardware.org/?probe=1c6ef1eeb0) | Dec 29, 2023 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | [4f4c0766c2](https://linux-hardware.org/?probe=4f4c0766c2) | Dec 28, 2023 |
| ASRock        | B250M-HDV                   | [c6c27e51ca](https://linux-hardware.org/?probe=c6c27e51ca) | Dec 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | [2d53ff60cb](https://linux-hardware.org/?probe=2d53ff60cb) | Dec 28, 2023 |
| Dell          | 04Y8V0 A02                  | [ba96083a55](https://linux-hardware.org/?probe=ba96083a55) | Dec 28, 2023 |
| HP            | 830C                        | [2f602f34b2](https://linux-hardware.org/?probe=2f602f34b2) | Dec 28, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX         | [0d4c53d42f](https://linux-hardware.org/?probe=0d4c53d42f) | Dec 28, 2023 |
| ASUSTek       | PRIME H510M-A               | [e65000c3c2](https://linux-hardware.org/?probe=e65000c3c2) | Dec 28, 2023 |
| HP            | 830C                        | [2256355ca5](https://linux-hardware.org/?probe=2256355ca5) | Dec 28, 2023 |
| ASRock        | AMCP7A-ION                  | [8358bb2fb8](https://linux-hardware.org/?probe=8358bb2fb8) | Dec 28, 2023 |
| Dell          | 0YXT71 A03                  | [7a857447b4](https://linux-hardware.org/?probe=7a857447b4) | Dec 28, 2023 |
| JHZD          | BQM6                        | [fa041569a6](https://linux-hardware.org/?probe=fa041569a6) | Dec 28, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [8df141917e](https://linux-hardware.org/?probe=8df141917e) | Dec 28, 2023 |
| Acer          | H410H6-M17 P21-A1           | [6c4e2313d7](https://linux-hardware.org/?probe=6c4e2313d7) | Dec 28, 2023 |
| ASUSTek       | M5A97 R2.0                  | [020ea108b0](https://linux-hardware.org/?probe=020ea108b0) | Dec 28, 2023 |
| Gigabyte      | B660 DS3H DDR4              | [3b68c7809f](https://linux-hardware.org/?probe=3b68c7809f) | Dec 27, 2023 |
| HP            | 1589                        | [c52940817e](https://linux-hardware.org/?probe=c52940817e) | Dec 27, 2023 |
| Gigabyte      | Z97M-DS3H                   | [e0b1c57cc6](https://linux-hardware.org/?probe=e0b1c57cc6) | Dec 27, 2023 |
| MSI           | X79A-GD65                   | [298e0aeef7](https://linux-hardware.org/?probe=298e0aeef7) | Dec 27, 2023 |
| MSI           | X79A-GD65                   | [0272fb469a](https://linux-hardware.org/?probe=0272fb469a) | Dec 27, 2023 |
| Dell          | 02VCFF A00                  | [902c7a4466](https://linux-hardware.org/?probe=902c7a4466) | Dec 27, 2023 |
| ASRock        | B650M PG Riptide            | [9a27ea61df](https://linux-hardware.org/?probe=9a27ea61df) | Dec 27, 2023 |
| HP            | 86E9 A                      | [e373d2be5d](https://linux-hardware.org/?probe=e373d2be5d) | Dec 27, 2023 |
| MSI           | B150M MORTAR                | [c179cdb6dc](https://linux-hardware.org/?probe=c179cdb6dc) | Dec 27, 2023 |
| Acer          | H410H6-M17 P21-A1           | [106af034ae](https://linux-hardware.org/?probe=106af034ae) | Dec 27, 2023 |
| Dell          | 0KWVT8 A03                  | [fae868ef79](https://linux-hardware.org/?probe=fae868ef79) | Dec 26, 2023 |
| ASUSTek       | PRIME X570-PRO              | [4e5179b4d1](https://linux-hardware.org/?probe=4e5179b4d1) | Dec 26, 2023 |
| Supermicro    | X8SIL                       | [16a2d27e0a](https://linux-hardware.org/?probe=16a2d27e0a) | Dec 26, 2023 |
| MSI           | MAG B560M BAZOOKA           | [64d1814f82](https://linux-hardware.org/?probe=64d1814f82) | Dec 26, 2023 |
| MSI           | B150M MORTAR                | [23577ab5f1](https://linux-hardware.org/?probe=23577ab5f1) | Dec 26, 2023 |
| Dell          | 042P49 A02                  | [67c9288ec5](https://linux-hardware.org/?probe=67c9288ec5) | Dec 26, 2023 |
| HP            | 86E9 A                      | [c13adc0c5e](https://linux-hardware.org/?probe=c13adc0c5e) | Dec 26, 2023 |
| Dell          | 0D6H9T A00                  | [280147184f](https://linux-hardware.org/?probe=280147184f) | Dec 26, 2023 |
| HP            | 81C5 MVB                    | [15a3980b4a](https://linux-hardware.org/?probe=15a3980b4a) | Dec 25, 2023 |
| MSI           | B85-G43                     | [fd632d7a1f](https://linux-hardware.org/?probe=fd632d7a1f) | Dec 25, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [39eb82bb24](https://linux-hardware.org/?probe=39eb82bb24) | Dec 25, 2023 |
| MSI           | A68HM-P33 V2                | [4f11205fd5](https://linux-hardware.org/?probe=4f11205fd5) | Dec 25, 2023 |
| ASRock        | H61M-VG3                    | [1ef527f93a](https://linux-hardware.org/?probe=1ef527f93a) | Dec 24, 2023 |
| ASRock        | H61DEL                      | [932b2c50eb](https://linux-hardware.org/?probe=932b2c50eb) | Dec 24, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [915a47dab1](https://linux-hardware.org/?probe=915a47dab1) | Dec 24, 2023 |
| ASUSTek       | Z97-K                       | [d330d1d9f9](https://linux-hardware.org/?probe=d330d1d9f9) | Dec 24, 2023 |
| ASUSTek       | Z97-K                       | [d8ae24af2b](https://linux-hardware.org/?probe=d8ae24af2b) | Dec 24, 2023 |
| Acer          | Veriton X2631G V:1.0        | [c9555a34f2](https://linux-hardware.org/?probe=c9555a34f2) | Dec 23, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | [b1c3408d24](https://linux-hardware.org/?probe=b1c3408d24) | Dec 23, 2023 |
| ASRock        | H310CM-HDV/M.2              | [76d95ab75c](https://linux-hardware.org/?probe=76d95ab75c) | Dec 23, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [6f36390142](https://linux-hardware.org/?probe=6f36390142) | Dec 23, 2023 |
| ASRock        | AMCP7A-ION                  | [fb0acc2d50](https://linux-hardware.org/?probe=fb0acc2d50) | Dec 23, 2023 |
| HP            | 1497                        | [9d5244b557](https://linux-hardware.org/?probe=9d5244b557) | Dec 23, 2023 |
| Lenovo        | ThinkCentre M58 7373AJ5     | [201981bc3f](https://linux-hardware.org/?probe=201981bc3f) | Dec 23, 2023 |
| Foxconn       | 2ADA                        | [f30aec24c2](https://linux-hardware.org/?probe=f30aec24c2) | Dec 23, 2023 |
| ASRock        | AMCP7A-ION                  | [7d19dec574](https://linux-hardware.org/?probe=7d19dec574) | Dec 23, 2023 |
| MSI           | PRO Z790-A WIFI             | [9b8ad6a3f1](https://linux-hardware.org/?probe=9b8ad6a3f1) | Dec 23, 2023 |
| eMachines     | EL1360                      | [af31609559](https://linux-hardware.org/?probe=af31609559) | Dec 23, 2023 |
| ASUSTek       | P6T                         | [d90adb3a12](https://linux-hardware.org/?probe=d90adb3a12) | Dec 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | [da051b693c](https://linux-hardware.org/?probe=da051b693c) | Dec 23, 2023 |
| Dell          | 0FDY5C A00                  | [a3fc39604c](https://linux-hardware.org/?probe=a3fc39604c) | Dec 22, 2023 |
| HP            | 8643 SMVB                   | [bbdb2204d8](https://linux-hardware.org/?probe=bbdb2204d8) | Dec 22, 2023 |
| Dell          | 0D6H9T A00                  | [84275b737e](https://linux-hardware.org/?probe=84275b737e) | Dec 22, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [c9bee45423](https://linux-hardware.org/?probe=c9bee45423) | Dec 22, 2023 |
| Intel         | H61                         | [72c7724ef0](https://linux-hardware.org/?probe=72c7724ef0) | Dec 22, 2023 |
| MSI           | X570-A PRO                  | [27a132c185](https://linux-hardware.org/?probe=27a132c185) | Dec 22, 2023 |
| HP            | 8643 SMVB                   | [03ddd69e34](https://linux-hardware.org/?probe=03ddd69e34) | Dec 22, 2023 |
| MSI           | PRO Z790-A WIFI             | [8e38fb94ba](https://linux-hardware.org/?probe=8e38fb94ba) | Dec 22, 2023 |
| Dell          | 0WR7PY A03                  | [9ff527cfd0](https://linux-hardware.org/?probe=9ff527cfd0) | Dec 22, 2023 |
| HP            | 8626                        | [b04d9fcad9](https://linux-hardware.org/?probe=b04d9fcad9) | Dec 22, 2023 |
| Dell          | 0HY9JP A02                  | [6f47019169](https://linux-hardware.org/?probe=6f47019169) | Dec 22, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [8a2d46dced](https://linux-hardware.org/?probe=8a2d46dced) | Dec 22, 2023 |
| LattePanda    | Sigma                       | [09cb864933](https://linux-hardware.org/?probe=09cb864933) | Dec 22, 2023 |
| ASUSTek       | STRIX X99 GAMING            | [2af66f541d](https://linux-hardware.org/?probe=2af66f541d) | Dec 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | [3ff2f289b9](https://linux-hardware.org/?probe=3ff2f289b9) | Dec 22, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [dbc2e93666](https://linux-hardware.org/?probe=dbc2e93666) | Dec 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [628ca02992](https://linux-hardware.org/?probe=628ca02992) | Dec 21, 2023 |
| Gigabyte      | Z87-HD3                     | [49e514e9c4](https://linux-hardware.org/?probe=49e514e9c4) | Dec 21, 2023 |
| Acer          | Aspire XC-1760              | [ac3910a453](https://linux-hardware.org/?probe=ac3910a453) | Dec 21, 2023 |
| Supermicro    | H13DSG-O-CPU                | [1ba9d3bc0c](https://linux-hardware.org/?probe=1ba9d3bc0c) | Dec 21, 2023 |
| Supermicro    | H13DSG-O-CPU                | [066ebdde5b](https://linux-hardware.org/?probe=066ebdde5b) | Dec 21, 2023 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | [191d4913cd](https://linux-hardware.org/?probe=191d4913cd) | Dec 21, 2023 |
| Foxconn       | 2ADA                        | [735572694e](https://linux-hardware.org/?probe=735572694e) | Dec 21, 2023 |
| HP            | 18E7                        | [ad6cf02d18](https://linux-hardware.org/?probe=ad6cf02d18) | Dec 21, 2023 |
| HP            | 18E7                        | [fdb8b2d229](https://linux-hardware.org/?probe=fdb8b2d229) | Dec 21, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [8eca3c15e7](https://linux-hardware.org/?probe=8eca3c15e7) | Dec 21, 2023 |
| ASUSTek       | Z10PG-D16 Series            | [6b3c6c4099](https://linux-hardware.org/?probe=6b3c6c4099) | Dec 21, 2023 |
| MSI           | NF725M-P43                  | [43756d6fad](https://linux-hardware.org/?probe=43756d6fad) | Dec 21, 2023 |
| ASUSTek       | M5A97 R2.0                  | [93a7029d22](https://linux-hardware.org/?probe=93a7029d22) | Dec 21, 2023 |
| Acer          | Veriton X2631G V:1.0        | [7597019eca](https://linux-hardware.org/?probe=7597019eca) | Dec 21, 2023 |
| ASUSTek       | VM40B                       | [8deb79e86e](https://linux-hardware.org/?probe=8deb79e86e) | Dec 20, 2023 |
| Gigabyte      | B560M H                     | [6e7f8b2300](https://linux-hardware.org/?probe=6e7f8b2300) | Dec 20, 2023 |
| Gigabyte      | H81M-DS2                    | [1da522781e](https://linux-hardware.org/?probe=1da522781e) | Dec 20, 2023 |
| Gigabyte      | B550M DS3H                  | [35547b20b3](https://linux-hardware.org/?probe=35547b20b3) | Dec 20, 2023 |
| MSI           | B450-A PRO MAX              | [f46e034f2c](https://linux-hardware.org/?probe=f46e034f2c) | Dec 20, 2023 |
| Dell          | 09KPNV A00                  | [e696fd9ae0](https://linux-hardware.org/?probe=e696fd9ae0) | Dec 20, 2023 |
| Dell          | 0C522T A03                  | [7cd9f2379e](https://linux-hardware.org/?probe=7cd9f2379e) | Dec 20, 2023 |
| ASUSTek       | P8Z77-M PRO                 | [58517da295](https://linux-hardware.org/?probe=58517da295) | Dec 20, 2023 |
| ASRock        | FM2A58M-HD+                 | [09ab03cdcd](https://linux-hardware.org/?probe=09ab03cdcd) | Dec 19, 2023 |
| ANGXUN        | X79-VG2 V1.3                | [532c5b5ddc](https://linux-hardware.org/?probe=532c5b5ddc) | Dec 19, 2023 |
| MSI           | B85-G43                     | [2c855d2376](https://linux-hardware.org/?probe=2c855d2376) | Dec 19, 2023 |
| Dell          | 042P49 A02                  | [11f6da5848](https://linux-hardware.org/?probe=11f6da5848) | Dec 19, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [843515c201](https://linux-hardware.org/?probe=843515c201) | Dec 19, 2023 |
| Dell          | 0C522T A03                  | [35b8611349](https://linux-hardware.org/?probe=35b8611349) | Dec 19, 2023 |
| ASUSTek       | H81-PLUS                    | [359af07cb2](https://linux-hardware.org/?probe=359af07cb2) | Dec 19, 2023 |
| ASUSTek       | H81-PLUS                    | [b4b91802b5](https://linux-hardware.org/?probe=b4b91802b5) | Dec 19, 2023 |
| MSI           | X570-A PRO                  | [3cf8d970f8](https://linux-hardware.org/?probe=3cf8d970f8) | Dec 19, 2023 |
| MSI           | A520M-A PRO                 | [5781ca34c8](https://linux-hardware.org/?probe=5781ca34c8) | Dec 19, 2023 |
| Dell          | 0Y7WYT A00                  | [705321d0b6](https://linux-hardware.org/?probe=705321d0b6) | Dec 19, 2023 |
| HP            | 3647h                       | [0e741d6d7c](https://linux-hardware.org/?probe=0e741d6d7c) | Dec 18, 2023 |
| Supermicro    | X7DWA                       | [2ea00dfda4](https://linux-hardware.org/?probe=2ea00dfda4) | Dec 18, 2023 |
| Supermicro    | X7DWA                       | [6357637f80](https://linux-hardware.org/?probe=6357637f80) | Dec 18, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [f93e198dd4](https://linux-hardware.org/?probe=f93e198dd4) | Dec 18, 2023 |
| Gigabyte      | H410M S2H V3                | [498141a78c](https://linux-hardware.org/?probe=498141a78c) | Dec 18, 2023 |
| HC Technol... | HCAR5000-MI                 | [0cf5577833](https://linux-hardware.org/?probe=0cf5577833) | Dec 18, 2023 |
| Dell          | 06FW8P A02                  | [7b66e504eb](https://linux-hardware.org/?probe=7b66e504eb) | Dec 18, 2023 |
| HC Technol... | HCAR5000-MI                 | [2bee7533b2](https://linux-hardware.org/?probe=2bee7533b2) | Dec 18, 2023 |
| Gigabyte      | B550 GAMING X               | [6ecd3ce2c3](https://linux-hardware.org/?probe=6ecd3ce2c3) | Dec 18, 2023 |
| ASRock        | Z370M-ITX/ac                | [0f7c6a7383](https://linux-hardware.org/?probe=0f7c6a7383) | Dec 17, 2023 |
| ASUSTek       | PRIME B450M-K II            | [8425b10899](https://linux-hardware.org/?probe=8425b10899) | Dec 17, 2023 |
| Dell          | 07N90W A02                  | [0c471e8b44](https://linux-hardware.org/?probe=0c471e8b44) | Dec 17, 2023 |
| ASRock        | Z77 Extreme4                | [ead1dfb3ae](https://linux-hardware.org/?probe=ead1dfb3ae) | Dec 17, 2023 |
| ASRock        | H61M-VG4                    | [a845742a42](https://linux-hardware.org/?probe=a845742a42) | Dec 17, 2023 |
| MSI           | 2A9C                        | [342d099a7f](https://linux-hardware.org/?probe=342d099a7f) | Dec 17, 2023 |
| ASUSTek       | PRIME A320M-K               | [1f0e0f04f8](https://linux-hardware.org/?probe=1f0e0f04f8) | Dec 17, 2023 |
| HP            | 1790                        | [2d8c859110](https://linux-hardware.org/?probe=2d8c859110) | Dec 17, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [8adfc82dc5](https://linux-hardware.org/?probe=8adfc82dc5) | Dec 17, 2023 |
| Dell          | 0KWVT8 A03                  | [d5632292b6](https://linux-hardware.org/?probe=d5632292b6) | Dec 17, 2023 |
| Dell          | 0KWVT8 A03                  | [6745d8d399](https://linux-hardware.org/?probe=6745d8d399) | Dec 17, 2023 |
| Gigabyte      | H77M-D3H                    | [de9dcb40ba](https://linux-hardware.org/?probe=de9dcb40ba) | Dec 17, 2023 |
| Dell          | 0PC5F7 A03                  | [b280c267db](https://linux-hardware.org/?probe=b280c267db) | Dec 17, 2023 |
| Shenzhen M... | TH80                        | [1ad9ee524d](https://linux-hardware.org/?probe=1ad9ee524d) | Dec 16, 2023 |
| Inventec      | DQ Class A02                | [73df6dfb3b](https://linux-hardware.org/?probe=73df6dfb3b) | Dec 16, 2023 |
| Gigabyte      | B85-HD3-A                   | [e3d139cdb3](https://linux-hardware.org/?probe=e3d139cdb3) | Dec 16, 2023 |
| ASUSTek       | PRIME B760-PLUS             | [a7dd86011c](https://linux-hardware.org/?probe=a7dd86011c) | Dec 16, 2023 |
| Intel         | SHARKBAY                    | [efe58ba5df](https://linux-hardware.org/?probe=efe58ba5df) | Dec 16, 2023 |
| Gigabyte      | 970A-DS3P                   | [e6019b847e](https://linux-hardware.org/?probe=e6019b847e) | Dec 16, 2023 |
| HP            | 2B05                        | [81e68a1fb8](https://linux-hardware.org/?probe=81e68a1fb8) | Dec 16, 2023 |
| HP            | 2B05                        | [2063743d90](https://linux-hardware.org/?probe=2063743d90) | Dec 16, 2023 |
| Acer          | EG43M                       | [62c8e8acf8](https://linux-hardware.org/?probe=62c8e8acf8) | Dec 16, 2023 |
| HP            | 1790                        | [9bb2d6fcb4](https://linux-hardware.org/?probe=9bb2d6fcb4) | Dec 16, 2023 |
| ASUSTek       | PRIME A320M-A               | [862ce85408](https://linux-hardware.org/?probe=862ce85408) | Dec 16, 2023 |
| Dell          | 0RT6HT A01                  | [3509be8560](https://linux-hardware.org/?probe=3509be8560) | Dec 16, 2023 |
| ASRock        | X570 Taichi                 | [6458d64d28](https://linux-hardware.org/?probe=6458d64d28) | Dec 16, 2023 |
| Gigabyte      | B85-HD3-A                   | [b60d191f59](https://linux-hardware.org/?probe=b60d191f59) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | [1fae1d3423](https://linux-hardware.org/?probe=1fae1d3423) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | [1a70a13ff4](https://linux-hardware.org/?probe=1a70a13ff4) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | [8be30808ec](https://linux-hardware.org/?probe=8be30808ec) | Dec 15, 2023 |
| Shenzhen M... | AHBNB OEM                   | [1e0ba866f7](https://linux-hardware.org/?probe=1e0ba866f7) | Dec 15, 2023 |
| Google        | Guado                       | [e981ac3399](https://linux-hardware.org/?probe=e981ac3399) | Dec 15, 2023 |
| XDO.AI        | Pantera Pico PC             | [6358b586ac](https://linux-hardware.org/?probe=6358b586ac) | Dec 15, 2023 |
| Gigabyte      | Z790 AORUS MASTER           | [6af7c135e1](https://linux-hardware.org/?probe=6af7c135e1) | Dec 15, 2023 |
| Dell          | 0NW6H5 A00                  | [eb487bbab2](https://linux-hardware.org/?probe=eb487bbab2) | Dec 14, 2023 |
| Unknown       | Unknown                     | [9fb745d9fe](https://linux-hardware.org/?probe=9fb745d9fe) | Dec 14, 2023 |
| Lenovo        | SDK0J40700 WIN              | [48c963a11d](https://linux-hardware.org/?probe=48c963a11d) | Dec 14, 2023 |
| Google        | Guado                       | [50ceaa2515](https://linux-hardware.org/?probe=50ceaa2515) | Dec 14, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [742681b576](https://linux-hardware.org/?probe=742681b576) | Dec 14, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [72cd581273](https://linux-hardware.org/?probe=72cd581273) | Dec 14, 2023 |
| XDO.AI        | Pantera Pico PC             | [fabfe15230](https://linux-hardware.org/?probe=fabfe15230) | Dec 14, 2023 |
| HC Technol... | HCAR5000-MI                 | [d4d42016ea](https://linux-hardware.org/?probe=d4d42016ea) | Dec 14, 2023 |
| Gigabyte      | H410M S2H V3                | [101f8237e0](https://linux-hardware.org/?probe=101f8237e0) | Dec 14, 2023 |
| Dell          | 0TDG4V A01                  | [6da01d5871](https://linux-hardware.org/?probe=6da01d5871) | Dec 14, 2023 |
| ASRock        | B550M Pro4                  | [9d0aff4b01](https://linux-hardware.org/?probe=9d0aff4b01) | Dec 13, 2023 |
| HP            | 83EF                        | [e2a7a03e4c](https://linux-hardware.org/?probe=e2a7a03e4c) | Dec 13, 2023 |
| HP            | 83EF                        | [d5d568c47c](https://linux-hardware.org/?probe=d5d568c47c) | Dec 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [ab0ac93be6](https://linux-hardware.org/?probe=ab0ac93be6) | Dec 13, 2023 |
| HP            | 18E9                        | [ab47a5d40b](https://linux-hardware.org/?probe=ab47a5d40b) | Dec 13, 2023 |
| ASRock        | B550M Pro4                  | [e196db2480](https://linux-hardware.org/?probe=e196db2480) | Dec 13, 2023 |
| Gigabyte      | H410M S2H V3                | [e198c73fa2](https://linux-hardware.org/?probe=e198c73fa2) | Dec 13, 2023 |
| Dell          | 0K240Y A01                  | [227af40d05](https://linux-hardware.org/?probe=227af40d05) | Dec 13, 2023 |
| ASUSTek       | Basswood3G                  | [f686ec5ba9](https://linux-hardware.org/?probe=f686ec5ba9) | Dec 13, 2023 |
| Unknown       | Unknown                     | [fd405f79f2](https://linux-hardware.org/?probe=fd405f79f2) | Dec 13, 2023 |
| ASRock        | 970 Extreme4                | [ce858f7f7c](https://linux-hardware.org/?probe=ce858f7f7c) | Dec 13, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [01f7be08ae](https://linux-hardware.org/?probe=01f7be08ae) | Dec 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [4f1419b521](https://linux-hardware.org/?probe=4f1419b521) | Dec 12, 2023 |
| HP            | 3048h                       | [bb95017425](https://linux-hardware.org/?probe=bb95017425) | Dec 12, 2023 |
| ASUSTek       | PRIME Z790M-PLUS D4         | [eadc049e56](https://linux-hardware.org/?probe=eadc049e56) | Dec 12, 2023 |
| Gigabyte      | H310M H x.x                 | [bcf9fba46f](https://linux-hardware.org/?probe=bcf9fba46f) | Dec 12, 2023 |
| ASRock        | X470 Master SLI             | [2f96568c78](https://linux-hardware.org/?probe=2f96568c78) | Dec 12, 2023 |
| ASRock        | X470 Master SLI             | [68fe94d3be](https://linux-hardware.org/?probe=68fe94d3be) | Dec 12, 2023 |
| Dell          | 0M5DCD A00                  | [98f2d76ef0](https://linux-hardware.org/?probe=98f2d76ef0) | Dec 12, 2023 |
| Gigabyte      | B85M-DS3H-A                 | [c4de324273](https://linux-hardware.org/?probe=c4de324273) | Dec 12, 2023 |
| MSI           | A320M PRO-VD/S              | [c2a6947086](https://linux-hardware.org/?probe=c2a6947086) | Dec 12, 2023 |
| HC Technol... | HCAR5000-MI                 | [d5cb60727d](https://linux-hardware.org/?probe=d5cb60727d) | Dec 12, 2023 |
| MSI           | B450 TOMAHAWK               | [8e66dfbc28](https://linux-hardware.org/?probe=8e66dfbc28) | Dec 12, 2023 |
| HP            | 0AECh D                     | [b1856b493c](https://linux-hardware.org/?probe=b1856b493c) | Dec 12, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | [06f64404ec](https://linux-hardware.org/?probe=06f64404ec) | Dec 12, 2023 |
| Gigabyte      | A520M H                     | [e72a787933](https://linux-hardware.org/?probe=e72a787933) | Dec 12, 2023 |
| ASRock        | B450M-HDV R4.0              | [ee39e0724c](https://linux-hardware.org/?probe=ee39e0724c) | Dec 11, 2023 |
| Gigabyte      | 990FXA-UD3                  | [0d3866e04a](https://linux-hardware.org/?probe=0d3866e04a) | Dec 11, 2023 |
| Dell          | 0Y2YM6 A01                  | [c3fee04c74](https://linux-hardware.org/?probe=c3fee04c74) | Dec 11, 2023 |
| Dell          | 07VWPG A01                  | [a9ad39cd38](https://linux-hardware.org/?probe=a9ad39cd38) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [e3afd2e002](https://linux-hardware.org/?probe=e3afd2e002) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [656bfe20f4](https://linux-hardware.org/?probe=656bfe20f4) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [b1c994920c](https://linux-hardware.org/?probe=b1c994920c) | Dec 11, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [cc7c14dd72](https://linux-hardware.org/?probe=cc7c14dd72) | Dec 11, 2023 |
| MSI           | Z490-A PRO                  | [bd1772e0a0](https://linux-hardware.org/?probe=bd1772e0a0) | Dec 11, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [b7c06bf365](https://linux-hardware.org/?probe=b7c06bf365) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [8badd81a74](https://linux-hardware.org/?probe=8badd81a74) | Dec 11, 2023 |
| ASRock        | B85M Pro4                   | [8a11fe8107](https://linux-hardware.org/?probe=8a11fe8107) | Dec 11, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [448dc8ed72](https://linux-hardware.org/?probe=448dc8ed72) | Dec 11, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [472c013f53](https://linux-hardware.org/?probe=472c013f53) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [8cb24408c9](https://linux-hardware.org/?probe=8cb24408c9) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [df2e9cf858](https://linux-hardware.org/?probe=df2e9cf858) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [c8d223020d](https://linux-hardware.org/?probe=c8d223020d) | Dec 11, 2023 |
| Lenovo        | 3102 SDK0J40705 WIN 3425... | [70364f28ab](https://linux-hardware.org/?probe=70364f28ab) | Dec 11, 2023 |
| Gigabyte      | D-700                       | [18e3ee84cc](https://linux-hardware.org/?probe=18e3ee84cc) | Dec 11, 2023 |
| Intel         | H61                         | [611b51b6c1](https://linux-hardware.org/?probe=611b51b6c1) | Dec 11, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [32d436e221](https://linux-hardware.org/?probe=32d436e221) | Dec 11, 2023 |
| Gigabyte      | EP41-UD3L                   | [9b40e5889d](https://linux-hardware.org/?probe=9b40e5889d) | Dec 10, 2023 |
| Dell          | 0C522T A03                  | [11f857231b](https://linux-hardware.org/?probe=11f857231b) | Dec 10, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [237db70b40](https://linux-hardware.org/?probe=237db70b40) | Dec 10, 2023 |
| ASRock        | A520M-HVS                   | [5d07d03602](https://linux-hardware.org/?probe=5d07d03602) | Dec 10, 2023 |
| Pegatron      | IPMH61P1                    | [0d0474a798](https://linux-hardware.org/?probe=0d0474a798) | Dec 10, 2023 |
| ASUSTek       | PRIME B250M-A               | [1eaf3dd454](https://linux-hardware.org/?probe=1eaf3dd454) | Dec 10, 2023 |
| Dell          | 0TP406                      | [1b81a10a36](https://linux-hardware.org/?probe=1b81a10a36) | Dec 10, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [aa1aa7d695](https://linux-hardware.org/?probe=aa1aa7d695) | Dec 10, 2023 |
| Pegatron      | 2AC3                        | [3831586b47](https://linux-hardware.org/?probe=3831586b47) | Dec 10, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [e87dcf9ee2](https://linux-hardware.org/?probe=e87dcf9ee2) | Dec 10, 2023 |
| ASRock        | H61M-DGS                    | [d49b26fe0c](https://linux-hardware.org/?probe=d49b26fe0c) | Dec 10, 2023 |
| Inventec      | DQ Class A02                | [8e1c466924](https://linux-hardware.org/?probe=8e1c466924) | Dec 09, 2023 |
| ASRock        | H61M-DGS                    | [f8bd255155](https://linux-hardware.org/?probe=f8bd255155) | Dec 09, 2023 |
| Acer          | Veriton X2631G V:1.0        | [1465cf0eac](https://linux-hardware.org/?probe=1465cf0eac) | Dec 09, 2023 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | [af3f6d16ac](https://linux-hardware.org/?probe=af3f6d16ac) | Dec 09, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [5121b6a20c](https://linux-hardware.org/?probe=5121b6a20c) | Dec 09, 2023 |
| MSI           | B150M PRO-VDH               | [e35af0e70a](https://linux-hardware.org/?probe=e35af0e70a) | Dec 09, 2023 |
| ASUSTek       | PRIME A320M-K               | [237110c8c0](https://linux-hardware.org/?probe=237110c8c0) | Dec 09, 2023 |
| Biostar       | A10N-8800E                  | [283ae39c42](https://linux-hardware.org/?probe=283ae39c42) | Dec 09, 2023 |
| Gigabyte      | B550M K                     | [bbf66f105d](https://linux-hardware.org/?probe=bbf66f105d) | Dec 09, 2023 |
| Gigabyte      | B550M K                     | [e44ea6cf67](https://linux-hardware.org/?probe=e44ea6cf67) | Dec 09, 2023 |
| Gigabyte      | Z87-HD3                     | [9f3fb37b64](https://linux-hardware.org/?probe=9f3fb37b64) | Dec 09, 2023 |
| Lenovo        | ThinkCentre M58p 6234AE5    | [4cf3efef96](https://linux-hardware.org/?probe=4cf3efef96) | Dec 09, 2023 |
| Gigabyte      | Z87-HD3                     | [26c99ed573](https://linux-hardware.org/?probe=26c99ed573) | Dec 09, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | [22d34b64f2](https://linux-hardware.org/?probe=22d34b64f2) | Dec 09, 2023 |
| MSI           | B150M PRO-VDH               | [634d1d56b8](https://linux-hardware.org/?probe=634d1d56b8) | Dec 09, 2023 |
| Dell          | 0C522T A03                  | [3c06d9b7a8](https://linux-hardware.org/?probe=3c06d9b7a8) | Dec 09, 2023 |
| Intel         | DH67CL AAG10212-206         | [957289310d](https://linux-hardware.org/?probe=957289310d) | Dec 08, 2023 |
| ASRock        | H510M-ITX/ac                | [4850c05764](https://linux-hardware.org/?probe=4850c05764) | Dec 08, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [69df0251d9](https://linux-hardware.org/?probe=69df0251d9) | Dec 08, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [56eae53402](https://linux-hardware.org/?probe=56eae53402) | Dec 08, 2023 |
| MSI           | B450 TOMAHAWK               | [254b936002](https://linux-hardware.org/?probe=254b936002) | Dec 08, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | [8198e47786](https://linux-hardware.org/?probe=8198e47786) | Dec 08, 2023 |
| Gigabyte      | B85M-HD3                    | [b4da4c1d8a](https://linux-hardware.org/?probe=b4da4c1d8a) | Dec 07, 2023 |
| Biostar       | A10N-8800E                  | [b56d3e163b](https://linux-hardware.org/?probe=b56d3e163b) | Dec 07, 2023 |
| HP            | 8184 X4                     | [bad08bc9a0](https://linux-hardware.org/?probe=bad08bc9a0) | Dec 07, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [16b14ad0a7](https://linux-hardware.org/?probe=16b14ad0a7) | Dec 07, 2023 |
| HP            | 18E9                        | [80f4acdcfd](https://linux-hardware.org/?probe=80f4acdcfd) | Dec 07, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [04dd7cde77](https://linux-hardware.org/?probe=04dd7cde77) | Dec 07, 2023 |
| Dell          | 0NK5PH A00                  | [d96cb11edc](https://linux-hardware.org/?probe=d96cb11edc) | Dec 07, 2023 |
| Pegatron      | IPMH61P1                    | [264229998e](https://linux-hardware.org/?probe=264229998e) | Dec 07, 2023 |
| Gigabyte      | GA-MA770-DS3                | [66917779ad](https://linux-hardware.org/?probe=66917779ad) | Dec 07, 2023 |
| HP            | 09F8h                       | [c988ff1e96](https://linux-hardware.org/?probe=c988ff1e96) | Dec 07, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [5f96473345](https://linux-hardware.org/?probe=5f96473345) | Dec 07, 2023 |
| Dell          | 0GWHMW A00                  | [7843d89bd3](https://linux-hardware.org/?probe=7843d89bd3) | Dec 07, 2023 |
| ASUSTek       | PRIME B650M-A AX II         | [68ae754b57](https://linux-hardware.org/?probe=68ae754b57) | Dec 07, 2023 |
| Gigabyte      | G1.Sniper M3                | [d81e8e0452](https://linux-hardware.org/?probe=d81e8e0452) | Dec 07, 2023 |
| Gigabyte      | G1.Sniper M3                | [ac25bf99a5](https://linux-hardware.org/?probe=ac25bf99a5) | Dec 07, 2023 |
| Dell          | 0DFRFW A01                  | [766521b0e1](https://linux-hardware.org/?probe=766521b0e1) | Dec 06, 2023 |
| HP            | 0AECh D                     | [d58cc2f609](https://linux-hardware.org/?probe=d58cc2f609) | Dec 06, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | [2d3f4ca82c](https://linux-hardware.org/?probe=2d3f4ca82c) | Dec 06, 2023 |
| Gigabyte      | B450M DS3H V2               | [d1337f45be](https://linux-hardware.org/?probe=d1337f45be) | Dec 06, 2023 |
| Gigabyte      | B450M DS3H V2               | [f2a72d7b29](https://linux-hardware.org/?probe=f2a72d7b29) | Dec 06, 2023 |
| ALDO          | C2016-BSWI-D2               | [4dec414c2e](https://linux-hardware.org/?probe=4dec414c2e) | Dec 06, 2023 |
| Dell          | 0RY007                      | [2c93573995](https://linux-hardware.org/?probe=2c93573995) | Dec 06, 2023 |
| Supermicro    | X10DDW-i                    | [30c6080de4](https://linux-hardware.org/?probe=30c6080de4) | Dec 06, 2023 |
| Supermicro    | X10DDW-i                    | [0226f5545c](https://linux-hardware.org/?probe=0226f5545c) | Dec 06, 2023 |
| Supermicro    | X10DDW-i                    | [cf63284103](https://linux-hardware.org/?probe=cf63284103) | Dec 06, 2023 |
| Supermicro    | X10DDW-i                    | [6d0a010766](https://linux-hardware.org/?probe=6d0a010766) | Dec 06, 2023 |
| Supermicro    | X9DRW                       | [485f869e9b](https://linux-hardware.org/?probe=485f869e9b) | Dec 06, 2023 |
| HP            | 82F1                        | [3a292e8aaa](https://linux-hardware.org/?probe=3a292e8aaa) | Dec 06, 2023 |
| Dell          | 0P42M6 A01                  | [2deb37f773](https://linux-hardware.org/?probe=2deb37f773) | Dec 06, 2023 |
| Supermicro    | X10DRL-i                    | [f30d1a0a40](https://linux-hardware.org/?probe=f30d1a0a40) | Dec 06, 2023 |
| Supermicro    | X10DRL-i                    | [7f6c70bab0](https://linux-hardware.org/?probe=7f6c70bab0) | Dec 06, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [c7a3277bfa](https://linux-hardware.org/?probe=c7a3277bfa) | Dec 06, 2023 |
| Gigabyte      | Z370 HD3-CF                 | [1b3a42caac](https://linux-hardware.org/?probe=1b3a42caac) | Dec 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | [9b6cdd96f4](https://linux-hardware.org/?probe=9b6cdd96f4) | Dec 06, 2023 |
| Supermicro    | X9SCL/X9SCMA                | [3176cf1b45](https://linux-hardware.org/?probe=3176cf1b45) | Dec 06, 2023 |
| HP            | 2AF7                        | [4d98ac755f](https://linux-hardware.org/?probe=4d98ac755f) | Dec 06, 2023 |
| Unknown       | G-GLK01                     | [5c5efbafff](https://linux-hardware.org/?probe=5c5efbafff) | Dec 06, 2023 |
| Dell          | 0Y7WYT A00                  | [a59c9d08c1](https://linux-hardware.org/?probe=a59c9d08c1) | Dec 06, 2023 |
| NEC Infron... | MS-9888 10h                 | [8a1a2b9976](https://linux-hardware.org/?probe=8a1a2b9976) | Dec 05, 2023 |
| HC Technol... | HCAR5000-MI                 | [3f2a30851e](https://linux-hardware.org/?probe=3f2a30851e) | Dec 05, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [5e59f15fed](https://linux-hardware.org/?probe=5e59f15fed) | Dec 05, 2023 |
| HP            | 3646h                       | [df62144cda](https://linux-hardware.org/?probe=df62144cda) | Dec 05, 2023 |
| HP            | 339A                        | [53b6aa6808](https://linux-hardware.org/?probe=53b6aa6808) | Dec 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | [6d790b9d8c](https://linux-hardware.org/?probe=6d790b9d8c) | Dec 05, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [fa61806ea8](https://linux-hardware.org/?probe=fa61806ea8) | Dec 05, 2023 |
| Apple         | Mac-F4208DC8 PVT            | [ee36539c94](https://linux-hardware.org/?probe=ee36539c94) | Dec 05, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [599d20e4ef](https://linux-hardware.org/?probe=599d20e4ef) | Dec 04, 2023 |
| MSI           | MPG X670E CARBON WIFI       | [bab7262ca5](https://linux-hardware.org/?probe=bab7262ca5) | Dec 04, 2023 |
| Supermicro    | X10DRG-Q                    | [5844ee0f43](https://linux-hardware.org/?probe=5844ee0f43) | Dec 04, 2023 |
| ASUSTek       | M4A78LT-M                   | [9edd2d878e](https://linux-hardware.org/?probe=9edd2d878e) | Dec 04, 2023 |
| Supermicro    | X10DRG-Q                    | [175bbb55cb](https://linux-hardware.org/?probe=175bbb55cb) | Dec 04, 2023 |
| Foxconn       | 2AB1                        | [93bbf17266](https://linux-hardware.org/?probe=93bbf17266) | Dec 04, 2023 |
| MSI           | Z97 GAMING 7                | [887cbb52f3](https://linux-hardware.org/?probe=887cbb52f3) | Dec 04, 2023 |
| ASUSTek       | PRIME X370-PRO              | [cea029e467](https://linux-hardware.org/?probe=cea029e467) | Dec 04, 2023 |
| ZOTAC         | NM10                        | [a567bbf0a7](https://linux-hardware.org/?probe=a567bbf0a7) | Dec 04, 2023 |
| ASRock        | H97 Performance             | [dc36b5ee77](https://linux-hardware.org/?probe=dc36b5ee77) | Dec 04, 2023 |
| Unknown       | Unknown                     | [18e4bdaa86](https://linux-hardware.org/?probe=18e4bdaa86) | Dec 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6c24e26ef9](https://linux-hardware.org/?probe=6c24e26ef9) | Dec 03, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [6e9e9a487a](https://linux-hardware.org/?probe=6e9e9a487a) | Dec 03, 2023 |
| MSI           | A75MA-G55                   | [02a8179117](https://linux-hardware.org/?probe=02a8179117) | Dec 03, 2023 |
| HP            | 2B46                        | [5bfce44b96](https://linux-hardware.org/?probe=5bfce44b96) | Dec 03, 2023 |
| Google        | Wukong                      | [e665343907](https://linux-hardware.org/?probe=e665343907) | Dec 03, 2023 |
| Gigabyte      | Z77X-UD5H                   | [4cb46d807d](https://linux-hardware.org/?probe=4cb46d807d) | Dec 03, 2023 |
| Gigabyte      | Z77X-UD5H                   | [0c74d4b343](https://linux-hardware.org/?probe=0c74d4b343) | Dec 03, 2023 |
| HP            | ProLiant ML110 Gen9         | [c5f6a282c6](https://linux-hardware.org/?probe=c5f6a282c6) | Dec 03, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [1d3323974f](https://linux-hardware.org/?probe=1d3323974f) | Dec 03, 2023 |
| Shuttle       | DS10U                       | [4e3fa0f845](https://linux-hardware.org/?probe=4e3fa0f845) | Dec 02, 2023 |
| ASUSTek       | P9X79                       | [9cdf3ecc77](https://linux-hardware.org/?probe=9cdf3ecc77) | Dec 02, 2023 |
| ASUSTek       | P8H67-M PRO                 | [5923988290](https://linux-hardware.org/?probe=5923988290) | Dec 02, 2023 |
| ASRock        | AB350 Pro4                  | [61e9871a33](https://linux-hardware.org/?probe=61e9871a33) | Dec 02, 2023 |
| HP            | 3398                        | [26c9b1fa25](https://linux-hardware.org/?probe=26c9b1fa25) | Dec 01, 2023 |
| ASRock        | 970 Extreme4                | [4cbc340e7c](https://linux-hardware.org/?probe=4cbc340e7c) | Dec 01, 2023 |
| Gigabyte      | B150M-DS3H-CF               | [50332d509a](https://linux-hardware.org/?probe=50332d509a) | Dec 01, 2023 |
| Gigabyte      | B550M DS3H AC               | [bc4ff37548](https://linux-hardware.org/?probe=bc4ff37548) | Dec 01, 2023 |
| Dell          | 09KPNV A01                  | [e7cb2d834a](https://linux-hardware.org/?probe=e7cb2d834a) | Dec 01, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [89ec59d64e](https://linux-hardware.org/?probe=89ec59d64e) | Dec 01, 2023 |
| HP            | 2B0B 100                    | [48cb125554](https://linux-hardware.org/?probe=48cb125554) | Dec 01, 2023 |
| ASRock        | B450M-HDV                   | [d59279f095](https://linux-hardware.org/?probe=d59279f095) | Dec 01, 2023 |
| ASUSTek       | M5A78L-M LX3                | [41ae74c0ef](https://linux-hardware.org/?probe=41ae74c0ef) | Dec 01, 2023 |
| ASUSTek       | M5A97 R2.0                  | [dd82ddf299](https://linux-hardware.org/?probe=dd82ddf299) | Dec 01, 2023 |
| Dell          | 0C522T A03                  | [988e96f53c](https://linux-hardware.org/?probe=988e96f53c) | Nov 30, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [96a30d5a91](https://linux-hardware.org/?probe=96a30d5a91) | Nov 30, 2023 |
| Kllisre       | X79 V2.72S                  | [cd66ba8786](https://linux-hardware.org/?probe=cd66ba8786) | Nov 30, 2023 |
| ASUSTek       | CG5275                      | [13c8d80b5d](https://linux-hardware.org/?probe=13c8d80b5d) | Nov 29, 2023 |
| MSI           | B550-A PRO                  | [3bbd848840](https://linux-hardware.org/?probe=3bbd848840) | Nov 29, 2023 |
| Shenzhen M... | F6BFC                       | [1074904ba9](https://linux-hardware.org/?probe=1074904ba9) | Nov 29, 2023 |
| Foxconn       | nT-330i                     | [e20a015b3a](https://linux-hardware.org/?probe=e20a015b3a) | Nov 29, 2023 |
| HP            | 1905                        | [8d1dfc94c1](https://linux-hardware.org/?probe=8d1dfc94c1) | Nov 29, 2023 |
| Gigabyte      | F2A88X-D3H                  | [15c78cff63](https://linux-hardware.org/?probe=15c78cff63) | Nov 29, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [e6c589b9b0](https://linux-hardware.org/?probe=e6c589b9b0) | Nov 29, 2023 |
| ASUSTek       | ROG Maximus XII EXTREME     | [62cb0079ed](https://linux-hardware.org/?probe=62cb0079ed) | Nov 29, 2023 |
| IceWhale T... | ZimaBoard 432 ZMB           | [da395dd09e](https://linux-hardware.org/?probe=da395dd09e) | Nov 28, 2023 |
| Pegatron      | EVANS                       | [0d15cfcfb2](https://linux-hardware.org/?probe=0d15cfcfb2) | Nov 28, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [ee5fe89209](https://linux-hardware.org/?probe=ee5fe89209) | Nov 28, 2023 |
| HP            | 18E5                        | [a078eaa1d4](https://linux-hardware.org/?probe=a078eaa1d4) | Nov 28, 2023 |
| ASRock        | H310CM-HDV/M.2              | [72f7a18db5](https://linux-hardware.org/?probe=72f7a18db5) | Nov 28, 2023 |
| HP            | 8055                        | [a35b553ba1](https://linux-hardware.org/?probe=a35b553ba1) | Nov 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [33388f794b](https://linux-hardware.org/?probe=33388f794b) | Nov 28, 2023 |
| Unknown       | Unknown                     | [34cbcf6478](https://linux-hardware.org/?probe=34cbcf6478) | Nov 28, 2023 |
| Dell          | 06X1TJ A00                  | [4819314a84](https://linux-hardware.org/?probe=4819314a84) | Nov 27, 2023 |
| Intel         | JSL MRD                     | [6c635f4665](https://linux-hardware.org/?probe=6c635f4665) | Nov 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [330921f980](https://linux-hardware.org/?probe=330921f980) | Nov 27, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [85217c44b9](https://linux-hardware.org/?probe=85217c44b9) | Nov 27, 2023 |
| Intel         | HM570                       | [69eb6aa616](https://linux-hardware.org/?probe=69eb6aa616) | Nov 27, 2023 |
| Supermicro    | X10DRL-i                    | [5ef70291dd](https://linux-hardware.org/?probe=5ef70291dd) | Nov 27, 2023 |
| Supermicro    | X10DRU-i+A                  | [1dc89f1473](https://linux-hardware.org/?probe=1dc89f1473) | Nov 27, 2023 |
| Supermicro    | X9DRW                       | [86356d229c](https://linux-hardware.org/?probe=86356d229c) | Nov 27, 2023 |
| Supermicro    | X10DRL-i                    | [258e338541](https://linux-hardware.org/?probe=258e338541) | Nov 27, 2023 |
| Supermicro    | X10DDW-i                    | [dd750184ff](https://linux-hardware.org/?probe=dd750184ff) | Nov 27, 2023 |
| Supermicro    | X10DDW-i                    | [275dfaabe4](https://linux-hardware.org/?probe=275dfaabe4) | Nov 27, 2023 |
| Supermicro    | X10DDW-i                    | [7a9789da62](https://linux-hardware.org/?probe=7a9789da62) | Nov 27, 2023 |
| Supermicro    | X10DDW-i                    | [792780c033](https://linux-hardware.org/?probe=792780c033) | Nov 27, 2023 |
| Supermicro    | X9DRW                       | [c764c8a98e](https://linux-hardware.org/?probe=c764c8a98e) | Nov 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [7d36a1431f](https://linux-hardware.org/?probe=7d36a1431f) | Nov 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | [c594f5ae7a](https://linux-hardware.org/?probe=c594f5ae7a) | Nov 27, 2023 |
| Gigabyte      | Z490 UD                     | [38d2e85b40](https://linux-hardware.org/?probe=38d2e85b40) | Nov 27, 2023 |
| ASUSTek       | P6T SE                      | [caddbf7d43](https://linux-hardware.org/?probe=caddbf7d43) | Nov 27, 2023 |
| Dell          | 0VNM11 A01                  | [63c8ac9339](https://linux-hardware.org/?probe=63c8ac9339) | Nov 27, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | [59d1928371](https://linux-hardware.org/?probe=59d1928371) | Nov 27, 2023 |
| Gigabyte      | Z370N WIFI-CF               | [9704afc74e](https://linux-hardware.org/?probe=9704afc74e) | Nov 27, 2023 |
| ASRock        | A320M-HD                    | [1138c4c71b](https://linux-hardware.org/?probe=1138c4c71b) | Nov 27, 2023 |
| Intel         | HM570                       | [1cb9f8c891](https://linux-hardware.org/?probe=1cb9f8c891) | Nov 27, 2023 |
| Intel         | H61                         | [5146767aa6](https://linux-hardware.org/?probe=5146767aa6) | Nov 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [c090300c01](https://linux-hardware.org/?probe=c090300c01) | Nov 26, 2023 |
| Gigabyte      | GA-970A-UD3                 | [203375fd6b](https://linux-hardware.org/?probe=203375fd6b) | Nov 26, 2023 |
| Intel         | B75                         | [fab278b6c3](https://linux-hardware.org/?probe=fab278b6c3) | Nov 26, 2023 |
| ASUSTek       | PRIME X470-PRO              | [47ec694370](https://linux-hardware.org/?probe=47ec694370) | Nov 26, 2023 |
| Dell          | 0NK5PH A00                  | [ed6b4827c0](https://linux-hardware.org/?probe=ed6b4827c0) | Nov 26, 2023 |
| BCM           | RX67Q                       | [59c8825b99](https://linux-hardware.org/?probe=59c8825b99) | Nov 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [d3e69f25a6](https://linux-hardware.org/?probe=d3e69f25a6) | Nov 26, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [06a2e5b5a8](https://linux-hardware.org/?probe=06a2e5b5a8) | Nov 26, 2023 |
| Dell          | 0K240Y A01                  | [ac50bb87af](https://linux-hardware.org/?probe=ac50bb87af) | Nov 26, 2023 |
| Dell          | 0GYT9V A00                  | [a0fe7b3987](https://linux-hardware.org/?probe=a0fe7b3987) | Nov 26, 2023 |
| AZW           | MINI S 10                   | [32c65d600d](https://linux-hardware.org/?probe=32c65d600d) | Nov 26, 2023 |
| ASUSTek       | M5A97 R2.0                  | [a41a3d9679](https://linux-hardware.org/?probe=a41a3d9679) | Nov 26, 2023 |
| Gigabyte      | GA-970A-UD3                 | [6505e0c278](https://linux-hardware.org/?probe=6505e0c278) | Nov 26, 2023 |
| Gigabyte      | Z170X-Gaming 5              | [555e8e34b6](https://linux-hardware.org/?probe=555e8e34b6) | Nov 26, 2023 |
| Gigabyte      | Z170X-Gaming 5              | [b153aa9661](https://linux-hardware.org/?probe=b153aa9661) | Nov 26, 2023 |
| Foxconn       | H61MXT1/F2/-S/-V            | [0529750c82](https://linux-hardware.org/?probe=0529750c82) | Nov 25, 2023 |
| ASUSTek       | PRIME A320M-K               | [3ff2b07867](https://linux-hardware.org/?probe=3ff2b07867) | Nov 25, 2023 |
| Dell          | 0RT6HT A01                  | [aedd0fa212](https://linux-hardware.org/?probe=aedd0fa212) | Nov 25, 2023 |
| MSI           | Z87-G41 PC Mate             | [cff699d67d](https://linux-hardware.org/?probe=cff699d67d) | Nov 25, 2023 |
| Dell          | 0TDG4V A01                  | [f8200e619a](https://linux-hardware.org/?probe=f8200e619a) | Nov 25, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [e7d72eaf1d](https://linux-hardware.org/?probe=e7d72eaf1d) | Nov 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a727d2b744](https://linux-hardware.org/?probe=a727d2b744) | Nov 25, 2023 |
| ASRock        | AB350 Pro4                  | [0a3b2f3f70](https://linux-hardware.org/?probe=0a3b2f3f70) | Nov 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | [436499a8a7](https://linux-hardware.org/?probe=436499a8a7) | Nov 25, 2023 |
| ASRock        | Z370 Killer SLI/ac          | [c2d9f4aefb](https://linux-hardware.org/?probe=c2d9f4aefb) | Nov 24, 2023 |
| Gigabyte      | Z97M-DS3H                   | [fb9766adc5](https://linux-hardware.org/?probe=fb9766adc5) | Nov 24, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [dcc7dca975](https://linux-hardware.org/?probe=dcc7dca975) | Nov 24, 2023 |
| ASUSTek       | P8Z77-V LX                  | [f4a77c64b0](https://linux-hardware.org/?probe=f4a77c64b0) | Nov 24, 2023 |
| HP            | 2B0B 100                    | [908fb46664](https://linux-hardware.org/?probe=908fb46664) | Nov 24, 2023 |
| HP            | 339A                        | [3168ba2168](https://linux-hardware.org/?probe=3168ba2168) | Nov 24, 2023 |
| Dell          | 0TP406                      | [cc0c592ca4](https://linux-hardware.org/?probe=cc0c592ca4) | Nov 24, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [5417165a43](https://linux-hardware.org/?probe=5417165a43) | Nov 24, 2023 |
| Supermicro    | X10DAI                      | [00b8c3c935](https://linux-hardware.org/?probe=00b8c3c935) | Nov 23, 2023 |
| AZW           | SEi V1.0                    | [d18296a25c](https://linux-hardware.org/?probe=d18296a25c) | Nov 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [b98f204f02](https://linux-hardware.org/?probe=b98f204f02) | Nov 23, 2023 |
| MSI           | Z87-G41 PC Mate             | [ae2a4ee822](https://linux-hardware.org/?probe=ae2a4ee822) | Nov 23, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [d4a222fa3e](https://linux-hardware.org/?probe=d4a222fa3e) | Nov 23, 2023 |
| ASUSTek       | P6T SE                      | [60e24166f1](https://linux-hardware.org/?probe=60e24166f1) | Nov 23, 2023 |
| Gigabyte      | H310M H x.x                 | [b1d5cf3254](https://linux-hardware.org/?probe=b1d5cf3254) | Nov 23, 2023 |
| Gigabyte      | X99-UD4-CF                  | [d71110004d](https://linux-hardware.org/?probe=d71110004d) | Nov 23, 2023 |
| AZW           | Green G4 10                 | [e41477f9c4](https://linux-hardware.org/?probe=e41477f9c4) | Nov 23, 2023 |
| ASUSTek       | Q87T                        | [9f4fa65adc](https://linux-hardware.org/?probe=9f4fa65adc) | Nov 23, 2023 |
| ASUSTek       | Q87T                        | [2b57cf5c8e](https://linux-hardware.org/?probe=2b57cf5c8e) | Nov 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [70c262ab30](https://linux-hardware.org/?probe=70c262ab30) | Nov 23, 2023 |
| Gigabyte      | Z68AP-D3                    | [38521acb5a](https://linux-hardware.org/?probe=38521acb5a) | Nov 23, 2023 |
| ASRock        | Z690M-ITX/ax                | [94ad5ba24d](https://linux-hardware.org/?probe=94ad5ba24d) | Nov 23, 2023 |
| ASRock        | B450M Pro4                  | [e9faa52e9c](https://linux-hardware.org/?probe=e9faa52e9c) | Nov 23, 2023 |
| MSI           | H81M-E33                    | [590f44bb87](https://linux-hardware.org/?probe=590f44bb87) | Nov 22, 2023 |
| ASRock        | J4105-ITX                   | [d5a155c906](https://linux-hardware.org/?probe=d5a155c906) | Nov 22, 2023 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [67293d8013](https://linux-hardware.org/?probe=67293d8013) | Nov 22, 2023 |
| Gigabyte      | 970A-DS3P                   | [5546fbf0d2](https://linux-hardware.org/?probe=5546fbf0d2) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | [60b99664ff](https://linux-hardware.org/?probe=60b99664ff) | Nov 22, 2023 |
| ASRock        | FM2A58M-VG3+                | [df8c7b0bdb](https://linux-hardware.org/?probe=df8c7b0bdb) | Nov 22, 2023 |
| Biostar       | H81MHV3 5.0                 | [3643a6597c](https://linux-hardware.org/?probe=3643a6597c) | Nov 22, 2023 |
| ASRock        | A320M-HDV R4.0              | [794cc91e17](https://linux-hardware.org/?probe=794cc91e17) | Nov 22, 2023 |
| HP            | 1998                        | [260f73efb3](https://linux-hardware.org/?probe=260f73efb3) | Nov 22, 2023 |
| Gigabyte      | GB-BRR3H-4300               | [5850b8f7b8](https://linux-hardware.org/?probe=5850b8f7b8) | Nov 22, 2023 |
| MSI           | PRO Z790-A WIFI             | [4949a4bc03](https://linux-hardware.org/?probe=4949a4bc03) | Nov 22, 2023 |
| MSI           | PRO Z790-A WIFI             | [e5b0fd761f](https://linux-hardware.org/?probe=e5b0fd761f) | Nov 22, 2023 |
| HP            | 1998                        | [cc59ee230b](https://linux-hardware.org/?probe=cc59ee230b) | Nov 22, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [205b0b2438](https://linux-hardware.org/?probe=205b0b2438) | Nov 22, 2023 |
| AZW           | Green G5                    | [ad48753316](https://linux-hardware.org/?probe=ad48753316) | Nov 22, 2023 |
| Supermicro    | X10DRU-i+A                  | [bcefaeb3bc](https://linux-hardware.org/?probe=bcefaeb3bc) | Nov 21, 2023 |
| Foxconn       | 2ABF                        | [c05c0dccd3](https://linux-hardware.org/?probe=c05c0dccd3) | Nov 21, 2023 |
| Foxconn       | 2ABF                        | [043a7040bc](https://linux-hardware.org/?probe=043a7040bc) | Nov 21, 2023 |
| Gigabyte      | B550M DS3H                  | [c1f0bdaf54](https://linux-hardware.org/?probe=c1f0bdaf54) | Nov 21, 2023 |
| Dell          | 062TCH A00                  | [6df960f264](https://linux-hardware.org/?probe=6df960f264) | Nov 21, 2023 |
| ASUSTek       | B150M-ET M2 SERIES          | [a999563329](https://linux-hardware.org/?probe=a999563329) | Nov 21, 2023 |
| ASUSTek       | PRIME A320M-K               | [b29d72095f](https://linux-hardware.org/?probe=b29d72095f) | Nov 20, 2023 |
| HP            | 1905                        | [7f22b93c4b](https://linux-hardware.org/?probe=7f22b93c4b) | Nov 20, 2023 |
| Medion        | H81H3-EM2 H81EM2W08.309     | [5372788890](https://linux-hardware.org/?probe=5372788890) | Nov 20, 2023 |
| Dell          | 062TCH A00                  | [895c93e639](https://linux-hardware.org/?probe=895c93e639) | Nov 20, 2023 |
| Biostar       | Z790 VALKYRIE               | [b052717bb5](https://linux-hardware.org/?probe=b052717bb5) | Nov 20, 2023 |
| ASRock        | H81M-ITX/WiFi               | [e4b1bf4519](https://linux-hardware.org/?probe=e4b1bf4519) | Nov 20, 2023 |
| MSI           | PRO B550M-VC WIFI           | [6d0e282cad](https://linux-hardware.org/?probe=6d0e282cad) | Nov 20, 2023 |
| MSI           | PRO B550M-VC WIFI           | [5df0fefadc](https://linux-hardware.org/?probe=5df0fefadc) | Nov 20, 2023 |
| Gigabyte      | H81M-HD2                    | [a89f5cdc65](https://linux-hardware.org/?probe=a89f5cdc65) | Nov 20, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [d5a1fce5c0](https://linux-hardware.org/?probe=d5a1fce5c0) | Nov 19, 2023 |
| Gigabyte      | GA-790XTA-UD4               | [142c93b927](https://linux-hardware.org/?probe=142c93b927) | Nov 19, 2023 |
| HP            | 0AECh D                     | [208a7b27ab](https://linux-hardware.org/?probe=208a7b27ab) | Nov 19, 2023 |
| ASUSTek       | M4A87TD/USB3                | [1c63aea539](https://linux-hardware.org/?probe=1c63aea539) | Nov 19, 2023 |
| Lenovo        | 30C7 SDK0K13468 WIN 3273... | [27b54b9945](https://linux-hardware.org/?probe=27b54b9945) | Nov 19, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [8f389f95a6](https://linux-hardware.org/?probe=8f389f95a6) | Nov 19, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [8f99d241f8](https://linux-hardware.org/?probe=8f99d241f8) | Nov 19, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [e5d2cc7fcd](https://linux-hardware.org/?probe=e5d2cc7fcd) | Nov 19, 2023 |
| Dell          | 0TDG4V A01                  | [737ddab002](https://linux-hardware.org/?probe=737ddab002) | Nov 19, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | [ab7e55f5b9](https://linux-hardware.org/?probe=ab7e55f5b9) | Nov 19, 2023 |
| HP            | 1905                        | [19cc0187db](https://linux-hardware.org/?probe=19cc0187db) | Nov 19, 2023 |
| ASUSTek       | P7H55                       | [cd5e7b0924](https://linux-hardware.org/?probe=cd5e7b0924) | Nov 18, 2023 |
| Gigabyte      | B360HD3                     | [281c4b4ac5](https://linux-hardware.org/?probe=281c4b4ac5) | Nov 18, 2023 |
| ASUSTek       | A88X-PRO                    | [3fb9313a57](https://linux-hardware.org/?probe=3fb9313a57) | Nov 18, 2023 |
| AZW           | EQ                          | [19fa22ee5a](https://linux-hardware.org/?probe=19fa22ee5a) | Nov 18, 2023 |
| Inventec      | D CLASS A02                 | [ac41b7769d](https://linux-hardware.org/?probe=ac41b7769d) | Nov 18, 2023 |
| ASUSTek       | M2N68 Plus                  | [881ae0051a](https://linux-hardware.org/?probe=881ae0051a) | Nov 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [37139a6fd4](https://linux-hardware.org/?probe=37139a6fd4) | Nov 18, 2023 |
| ASRock        | AB350 Gaming K4             | [281925660d](https://linux-hardware.org/?probe=281925660d) | Nov 18, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [bfbed17470](https://linux-hardware.org/?probe=bfbed17470) | Nov 18, 2023 |
| Dell          | 0VRWRC A00                  | [b43ea86bfc](https://linux-hardware.org/?probe=b43ea86bfc) | Nov 18, 2023 |
| MSI           | B75MA-E33                   | [87132187f5](https://linux-hardware.org/?probe=87132187f5) | Nov 18, 2023 |
| MSI           | B75MA-E33                   | [ed47d2c01d](https://linux-hardware.org/?probe=ed47d2c01d) | Nov 18, 2023 |
| AZW           | EQ                          | [a5a8046409](https://linux-hardware.org/?probe=a5a8046409) | Nov 18, 2023 |
| HP            | 83E1                        | [8c2a7b3183](https://linux-hardware.org/?probe=8c2a7b3183) | Nov 18, 2023 |
| HP            | 83E1                        | [8b8d3394a8](https://linux-hardware.org/?probe=8b8d3394a8) | Nov 18, 2023 |
| ASRock        | B360M IB-R1                 | [fce9bc6ebe](https://linux-hardware.org/?probe=fce9bc6ebe) | Nov 18, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [0ebd3e6dd0](https://linux-hardware.org/?probe=0ebd3e6dd0) | Nov 17, 2023 |
| MSI           | A320M PRO-VD/S              | [2b5bf0b25f](https://linux-hardware.org/?probe=2b5bf0b25f) | Nov 17, 2023 |
| Gigabyte      | H61M-D2-B3                  | [358c0e28e9](https://linux-hardware.org/?probe=358c0e28e9) | Nov 17, 2023 |
| Dell          | 0NV0M7 A01                  | [f5ced375d8](https://linux-hardware.org/?probe=f5ced375d8) | Nov 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [57d850fe75](https://linux-hardware.org/?probe=57d850fe75) | Nov 17, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [6b4903cbb7](https://linux-hardware.org/?probe=6b4903cbb7) | Nov 17, 2023 |
| Medion        | H110H4-EM                   | [e6ca6d6e19](https://linux-hardware.org/?probe=e6ca6d6e19) | Nov 17, 2023 |
| HP            | 83E2                        | [89267eedbb](https://linux-hardware.org/?probe=89267eedbb) | Nov 17, 2023 |
| ASUSTek       | PRIME A320M-K               | [7adb8abf2c](https://linux-hardware.org/?probe=7adb8abf2c) | Nov 17, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [a1a2303573](https://linux-hardware.org/?probe=a1a2303573) | Nov 17, 2023 |
| Huanan        | X99-8M-F V1.3               | [58b38ab609](https://linux-hardware.org/?probe=58b38ab609) | Nov 17, 2023 |
| Huanan        | X99-8M-F V1.3               | [db7291c1da](https://linux-hardware.org/?probe=db7291c1da) | Nov 17, 2023 |
| ASUSTek       | P8H67-M                     | [5a6066ab8c](https://linux-hardware.org/?probe=5a6066ab8c) | Nov 17, 2023 |
| Dell          | 0F428D A00                  | [7111aa0bdb](https://linux-hardware.org/?probe=7111aa0bdb) | Nov 17, 2023 |
| AMI           | Intel                       | [36c0765b5c](https://linux-hardware.org/?probe=36c0765b5c) | Nov 17, 2023 |
| Dell          | 0GXM1W A00                  | [da8f5fa2e5](https://linux-hardware.org/?probe=da8f5fa2e5) | Nov 17, 2023 |
| ASUSTek       | Z170-K                      | [8d6d23926d](https://linux-hardware.org/?probe=8d6d23926d) | Nov 17, 2023 |
| Dell          | 0HHV7N A00                  | [9bb04e6b68](https://linux-hardware.org/?probe=9bb04e6b68) | Nov 17, 2023 |
| ASUSTek       | P8H67-M                     | [663c18d823](https://linux-hardware.org/?probe=663c18d823) | Nov 16, 2023 |
| Gigabyte      | P85-D3                      | [a6742c43a4](https://linux-hardware.org/?probe=a6742c43a4) | Nov 16, 2023 |
| Unknown       | Unknown                     | [f5e4b8400a](https://linux-hardware.org/?probe=f5e4b8400a) | Nov 16, 2023 |
| Supermicro    | X10DRU-i+A                  | [507da23117](https://linux-hardware.org/?probe=507da23117) | Nov 16, 2023 |
| Gigabyte      | H310M H x.x                 | [a95e23a38b](https://linux-hardware.org/?probe=a95e23a38b) | Nov 16, 2023 |
| Lenovo        | NOK                         | [1126fee720](https://linux-hardware.org/?probe=1126fee720) | Nov 16, 2023 |
| Gigabyte      | Z68AP-D3                    | [e1f0981231](https://linux-hardware.org/?probe=e1f0981231) | Nov 16, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [389f2adb17](https://linux-hardware.org/?probe=389f2adb17) | Nov 16, 2023 |
| HP            | 895C                        | [cbc2a3c2ae](https://linux-hardware.org/?probe=cbc2a3c2ae) | Nov 16, 2023 |
| Dell          | 062TCH A00                  | [5e674f81ca](https://linux-hardware.org/?probe=5e674f81ca) | Nov 15, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [fe31319dba](https://linux-hardware.org/?probe=fe31319dba) | Nov 15, 2023 |
| Gigabyte      | B550M K                     | [7415f68bac](https://linux-hardware.org/?probe=7415f68bac) | Nov 15, 2023 |
| MACHINIST     | E5-RS9 V1.11                | [13df1b5b7e](https://linux-hardware.org/?probe=13df1b5b7e) | Nov 15, 2023 |
| HP            | 3031h                       | [41814a3ce4](https://linux-hardware.org/?probe=41814a3ce4) | Nov 15, 2023 |
| ASUSTek       | H81-GAMER                   | [c5a2208642](https://linux-hardware.org/?probe=c5a2208642) | Nov 15, 2023 |
| ASUSTek       | H81-GAMER                   | [8891aedb5d](https://linux-hardware.org/?probe=8891aedb5d) | Nov 15, 2023 |
| Dell          | 0DFRFW A01                  | [dc42526823](https://linux-hardware.org/?probe=dc42526823) | Nov 15, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [27fcb76b4a](https://linux-hardware.org/?probe=27fcb76b4a) | Nov 15, 2023 |
| Dell          | 0D6H9T A02                  | [943ffbe22c](https://linux-hardware.org/?probe=943ffbe22c) | Nov 15, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [193b97cc55](https://linux-hardware.org/?probe=193b97cc55) | Nov 15, 2023 |
| ASUSTek       | M5A97 R2.0                  | [1200e8253b](https://linux-hardware.org/?probe=1200e8253b) | Nov 14, 2023 |
| HP            | 0A64h                       | [db072ebaed](https://linux-hardware.org/?probe=db072ebaed) | Nov 14, 2023 |
| Dell          | 0YNVJG A02                  | [7c23854d23](https://linux-hardware.org/?probe=7c23854d23) | Nov 14, 2023 |
| Dell          | 0PGKWF A02                  | [3025cd2250](https://linux-hardware.org/?probe=3025cd2250) | Nov 14, 2023 |
| Dell          | 0YNVJG A02                  | [a641eb99bf](https://linux-hardware.org/?probe=a641eb99bf) | Nov 14, 2023 |
| Dell          | 05WXFV A03                  | [ecab18e943](https://linux-hardware.org/?probe=ecab18e943) | Nov 14, 2023 |
| Gigabyte      | B85M-HD3                    | [6cd89560fd](https://linux-hardware.org/?probe=6cd89560fd) | Nov 14, 2023 |
| ASUSTek       | Crosshair V Formula         | [81264f0e4e](https://linux-hardware.org/?probe=81264f0e4e) | Nov 14, 2023 |
| Intel         | AlderLake-S ADP-S DDR5 U... | [b3e7f8ab5c](https://linux-hardware.org/?probe=b3e7f8ab5c) | Nov 14, 2023 |
| ASUSTek       | P8B75-M LE                  | [d4baa90ad5](https://linux-hardware.org/?probe=d4baa90ad5) | Nov 14, 2023 |
| ASUSTek       | H110M-A                     | [d2b8ae9725](https://linux-hardware.org/?probe=d2b8ae9725) | Nov 13, 2023 |
| ASUSTek       | P8B75-M LE                  | [5dd5ed8025](https://linux-hardware.org/?probe=5dd5ed8025) | Nov 13, 2023 |
| ASUSTek       | M5A97 R2.0                  | [05e0b7749a](https://linux-hardware.org/?probe=05e0b7749a) | Nov 13, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [6f0d8ee5da](https://linux-hardware.org/?probe=6f0d8ee5da) | Nov 13, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [3c2d452ee0](https://linux-hardware.org/?probe=3c2d452ee0) | Nov 13, 2023 |
| HP            | 2215                        | [452b632947](https://linux-hardware.org/?probe=452b632947) | Nov 13, 2023 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | [15f3bc5d7e](https://linux-hardware.org/?probe=15f3bc5d7e) | Nov 13, 2023 |
| HP            | 0AA0h                       | [6d11e8b4d5](https://linux-hardware.org/?probe=6d11e8b4d5) | Nov 13, 2023 |
| ASUSTek       | H81M-C                      | [b3c22e6ea8](https://linux-hardware.org/?probe=b3c22e6ea8) | Nov 13, 2023 |
| Dell          | 0TDG4V A01                  | [f886eb50fa](https://linux-hardware.org/?probe=f886eb50fa) | Nov 13, 2023 |
| ASUSTek       | M5A97 R2.0                  | [0020161387](https://linux-hardware.org/?probe=0020161387) | Nov 13, 2023 |
| ASUSTek       | PRIME Z390-A                | [597d1856ab](https://linux-hardware.org/?probe=597d1856ab) | Nov 12, 2023 |
| Medion        | MS-7707                     | [a6971454a0](https://linux-hardware.org/?probe=a6971454a0) | Nov 12, 2023 |
| OEM           | B75 Ver:1.41                | [a706806180](https://linux-hardware.org/?probe=a706806180) | Nov 12, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [cd6a15e082](https://linux-hardware.org/?probe=cd6a15e082) | Nov 12, 2023 |
| Acer          | Aspire X3950                | [b5f08e00c9](https://linux-hardware.org/?probe=b5f08e00c9) | Nov 12, 2023 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | [82ac0e505a](https://linux-hardware.org/?probe=82ac0e505a) | Nov 12, 2023 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | [8f08acd434](https://linux-hardware.org/?probe=8f08acd434) | Nov 12, 2023 |
| HP            | 845A                        | [95fbc211ec](https://linux-hardware.org/?probe=95fbc211ec) | Nov 11, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [bedc6fd7f0](https://linux-hardware.org/?probe=bedc6fd7f0) | Nov 11, 2023 |
| HP            | 339A                        | [b72bafad26](https://linux-hardware.org/?probe=b72bafad26) | Nov 11, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [c0932e879f](https://linux-hardware.org/?probe=c0932e879f) | Nov 11, 2023 |
| MSI           | MS-B0A21                    | [c9d19c0810](https://linux-hardware.org/?probe=c9d19c0810) | Nov 11, 2023 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | [e82ee1d840](https://linux-hardware.org/?probe=e82ee1d840) | Nov 11, 2023 |
| ASUSTek       | Z170-A                      | [332413e83b](https://linux-hardware.org/?probe=332413e83b) | Nov 11, 2023 |
| ASUSTek       | PRIME B550M-A AC            | [f709168fa7](https://linux-hardware.org/?probe=f709168fa7) | Nov 11, 2023 |
| HP            | 8054                        | [66fa2fd8c5](https://linux-hardware.org/?probe=66fa2fd8c5) | Nov 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [145330a105](https://linux-hardware.org/?probe=145330a105) | Nov 11, 2023 |
| HP            | 8054                        | [91d4d659b4](https://linux-hardware.org/?probe=91d4d659b4) | Nov 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [cf0d635016](https://linux-hardware.org/?probe=cf0d635016) | Nov 11, 2023 |
| ASUSTek       | P8H67-I DELUXE              | [2e8ed5d14f](https://linux-hardware.org/?probe=2e8ed5d14f) | Nov 11, 2023 |
| HP            | 339A                        | [a89c7d0d5f](https://linux-hardware.org/?probe=a89c7d0d5f) | Nov 10, 2023 |
| HP            | 1998                        | [3843c1d8d9](https://linux-hardware.org/?probe=3843c1d8d9) | Nov 10, 2023 |
| ASUSTek       | H110M-D                     | [6e0b13392e](https://linux-hardware.org/?probe=6e0b13392e) | Nov 10, 2023 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | [947bd85c63](https://linux-hardware.org/?probe=947bd85c63) | Nov 10, 2023 |
| Gigabyte      | H61M-D2-B3                  | [f63e590b7d](https://linux-hardware.org/?probe=f63e590b7d) | Nov 10, 2023 |
| ASUSTek       | P7H55-M                     | [cee33b1be4](https://linux-hardware.org/?probe=cee33b1be4) | Nov 10, 2023 |
| TYAN Compu... | S8030GM2NE 5411T6180004     | [8d9e3d8367](https://linux-hardware.org/?probe=8d9e3d8367) | Nov 10, 2023 |
| Unknown       | Unknown                     | [2a03c8f49d](https://linux-hardware.org/?probe=2a03c8f49d) | Nov 10, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [8db3107f3f](https://linux-hardware.org/?probe=8db3107f3f) | Nov 10, 2023 |
| MouseCompu... | H61MU-S01                   | [f887cc4eb6](https://linux-hardware.org/?probe=f887cc4eb6) | Nov 10, 2023 |
| Gigabyte      | GA-970A-UD3                 | [338ee14ca9](https://linux-hardware.org/?probe=338ee14ca9) | Nov 10, 2023 |
| Gigabyte      | GA-970A-UD3                 | [cb0c56c416](https://linux-hardware.org/?probe=cb0c56c416) | Nov 10, 2023 |
| Pegatron      | 2AD5                        | [d30af2f74e](https://linux-hardware.org/?probe=d30af2f74e) | Nov 09, 2023 |
| ASRock        | N68C-GS FX                  | [fae6b5df26](https://linux-hardware.org/?probe=fae6b5df26) | Nov 09, 2023 |
| Dell          | 08NPPY A00                  | [921976d885](https://linux-hardware.org/?probe=921976d885) | Nov 09, 2023 |
| ASUSTek       | Maximus VI HERO             | [5d5c032d3a](https://linux-hardware.org/?probe=5d5c032d3a) | Nov 09, 2023 |
| Dell          | 0TY565                      | [9bf6328f12](https://linux-hardware.org/?probe=9bf6328f12) | Nov 09, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [c8cbd7f579](https://linux-hardware.org/?probe=c8cbd7f579) | Nov 09, 2023 |
| ASUSTek       | A78M-E                      | [cc1b2dd9fd](https://linux-hardware.org/?probe=cc1b2dd9fd) | Nov 09, 2023 |
| MSI           | X299 RAIDER                 | [3f714787ff](https://linux-hardware.org/?probe=3f714787ff) | Nov 09, 2023 |
| ASUSTek       | Z170-K                      | [8bdabebc5b](https://linux-hardware.org/?probe=8bdabebc5b) | Nov 09, 2023 |
| Dell          | OptiPlex 5050               | [60a7067b29](https://linux-hardware.org/?probe=60a7067b29) | Nov 09, 2023 |
| Lenovo        | ThinkCentre M71e 5033A21    | [61d14476fe](https://linux-hardware.org/?probe=61d14476fe) | Nov 09, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [27571092d5](https://linux-hardware.org/?probe=27571092d5) | Nov 09, 2023 |
| Dell          | 0YJPT1 A00                  | [8c4ff2532c](https://linux-hardware.org/?probe=8c4ff2532c) | Nov 09, 2023 |
| MSI           | 2AE0                        | [9186439c3f](https://linux-hardware.org/?probe=9186439c3f) | Nov 09, 2023 |
| MSI           | 2AE0                        | [0f52bd5340](https://linux-hardware.org/?probe=0f52bd5340) | Nov 09, 2023 |
| ASUSTek       | Pro A520M-C II              | [79bcc584f6](https://linux-hardware.org/?probe=79bcc584f6) | Nov 09, 2023 |
| ASUSTek       | Z87-A                       | [669cb641ab](https://linux-hardware.org/?probe=669cb641ab) | Nov 09, 2023 |
| Gigabyte      | Z690 UD DDR4                | [ed2a5b5b45](https://linux-hardware.org/?probe=ed2a5b5b45) | Nov 09, 2023 |
| Supermicro    | X10DDW-i                    | [0e4c00f6cc](https://linux-hardware.org/?probe=0e4c00f6cc) | Nov 08, 2023 |
| Supermicro    | X10DDW-i                    | [a9857525ee](https://linux-hardware.org/?probe=a9857525ee) | Nov 08, 2023 |
| Supermicro    | X10DDW-i                    | [675f3cc7a6](https://linux-hardware.org/?probe=675f3cc7a6) | Nov 08, 2023 |
| Supermicro    | X10DDW-i                    | [5458cc44c1](https://linux-hardware.org/?probe=5458cc44c1) | Nov 08, 2023 |
| Supermicro    | X10DDW-i                    | [d303acb833](https://linux-hardware.org/?probe=d303acb833) | Nov 08, 2023 |
| Gigabyte      | H61M-D2-B3                  | [ddf4e5c8ba](https://linux-hardware.org/?probe=ddf4e5c8ba) | Nov 08, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [47bd2b5230](https://linux-hardware.org/?probe=47bd2b5230) | Nov 08, 2023 |
| Supermicro    | X10DDW-i                    | [9e7421405d](https://linux-hardware.org/?probe=9e7421405d) | Nov 08, 2023 |
| Supermicro    | X10DDW-i                    | [2dbce05146](https://linux-hardware.org/?probe=2dbce05146) | Nov 08, 2023 |
| Supermicro    | X10DDW-i                    | [72b1e3ca13](https://linux-hardware.org/?probe=72b1e3ca13) | Nov 08, 2023 |
| Supermicro    | X10DDW-i                    | [c0c649585d](https://linux-hardware.org/?probe=c0c649585d) | Nov 08, 2023 |
| Supermicro    | X10DDW-i                    | [9cdae7f88f](https://linux-hardware.org/?probe=9cdae7f88f) | Nov 08, 2023 |
| Dell          | 0C96W1 A03                  | [e33b75f1f2](https://linux-hardware.org/?probe=e33b75f1f2) | Nov 08, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [741dbb7024](https://linux-hardware.org/?probe=741dbb7024) | Nov 08, 2023 |
| Gigabyte      | H310M H x.x                 | [5c1aced8cf](https://linux-hardware.org/?probe=5c1aced8cf) | Nov 08, 2023 |
| Gigabyte      | B85M-D3H                    | [c035e0367f](https://linux-hardware.org/?probe=c035e0367f) | Nov 08, 2023 |
| ASRock        | 970 Extreme3                | [a3c812c28b](https://linux-hardware.org/?probe=a3c812c28b) | Nov 08, 2023 |
| ASRock        | 970 Extreme3                | [1795f98739](https://linux-hardware.org/?probe=1795f98739) | Nov 08, 2023 |
| Gigabyte      | 970A-DS3P                   | [c81bc71fdb](https://linux-hardware.org/?probe=c81bc71fdb) | Nov 08, 2023 |
| MSI           | H81M-E34                    | [f4fc84f8f0](https://linux-hardware.org/?probe=f4fc84f8f0) | Nov 07, 2023 |
| Dell          | 0HHV7N A00                  | [2be7c3b6d6](https://linux-hardware.org/?probe=2be7c3b6d6) | Nov 07, 2023 |
| HP            | 82B4                        | [495ab5bbad](https://linux-hardware.org/?probe=495ab5bbad) | Nov 07, 2023 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | [479317e80f](https://linux-hardware.org/?probe=479317e80f) | Nov 07, 2023 |
| Dell          | 0TY565                      | [1597a5eaf7](https://linux-hardware.org/?probe=1597a5eaf7) | Nov 07, 2023 |
| HP            | 8437                        | [818f52c6f0](https://linux-hardware.org/?probe=818f52c6f0) | Nov 07, 2023 |
| Dell          | 062TCH A00                  | [ac7ca2b01b](https://linux-hardware.org/?probe=ac7ca2b01b) | Nov 07, 2023 |
| Lenovo        | SHARKBAY NOK                | [8ab4453aad](https://linux-hardware.org/?probe=8ab4453aad) | Nov 07, 2023 |
| Dell          | 0JCTF8 A00                  | [1f3f493cb1](https://linux-hardware.org/?probe=1f3f493cb1) | Nov 07, 2023 |
| Supermicro    | X10DRU-i+B                  | [5e4205720d](https://linux-hardware.org/?probe=5e4205720d) | Nov 07, 2023 |
| ASUSTek       | PRIME X470-PRO              | [9a4e137e6c](https://linux-hardware.org/?probe=9a4e137e6c) | Nov 07, 2023 |
| ASRock        | Z77 Pro4                    | [275fbaee75](https://linux-hardware.org/?probe=275fbaee75) | Nov 07, 2023 |
| ASUSTek       | A88X-PRO                    | [174012b81c](https://linux-hardware.org/?probe=174012b81c) | Nov 07, 2023 |
| ASUSTek       | CG8350                      | [af4ec07f3b](https://linux-hardware.org/?probe=af4ec07f3b) | Nov 06, 2023 |
| AZW           | EQ                          | [50c0310d2e](https://linux-hardware.org/?probe=50c0310d2e) | Nov 06, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | [50747bc510](https://linux-hardware.org/?probe=50747bc510) | Nov 06, 2023 |
| HP            | 0A64h                       | [ad021b1397](https://linux-hardware.org/?probe=ad021b1397) | Nov 06, 2023 |
| AZW           | EQ                          | [161d2abf24](https://linux-hardware.org/?probe=161d2abf24) | Nov 06, 2023 |
| BESSTAR Te... | HM90                        | [5ce37cedf9](https://linux-hardware.org/?probe=5ce37cedf9) | Nov 06, 2023 |
| GMKtec        | NucBox K2                   | [a88d491579](https://linux-hardware.org/?probe=a88d491579) | Nov 06, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [cee650aa5a](https://linux-hardware.org/?probe=cee650aa5a) | Nov 06, 2023 |
| Dell          | OptiPlex 5050               | [6c4a08354b](https://linux-hardware.org/?probe=6c4a08354b) | Nov 06, 2023 |
| MSI           | B560M PRO-E                 | [89a24ae9fa](https://linux-hardware.org/?probe=89a24ae9fa) | Nov 06, 2023 |
| ASUSTek       | SABERTOOTH X79              | [c46040087a](https://linux-hardware.org/?probe=c46040087a) | Nov 06, 2023 |
| Shuttle       | XS35V3                      | [0c51d541de](https://linux-hardware.org/?probe=0c51d541de) | Nov 06, 2023 |
| ASUSTek       | P30AD                       | [63322c386f](https://linux-hardware.org/?probe=63322c386f) | Nov 05, 2023 |
| HP            | 2B05                        | [eb343bd373](https://linux-hardware.org/?probe=eb343bd373) | Nov 05, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [25b39b698c](https://linux-hardware.org/?probe=25b39b698c) | Nov 05, 2023 |
| Dell          | 0JCTF8 A00                  | [b3669f73a8](https://linux-hardware.org/?probe=b3669f73a8) | Nov 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [d95f04dd2c](https://linux-hardware.org/?probe=d95f04dd2c) | Nov 05, 2023 |
| HP            | 1495                        | [fe18b89530](https://linux-hardware.org/?probe=fe18b89530) | Nov 05, 2023 |
| ASUSTek       | PRIME X470-PRO              | [692601dd3b](https://linux-hardware.org/?probe=692601dd3b) | Nov 05, 2023 |
| MSI           | MEG Z590 UNIFY              | [1f84fe45f8](https://linux-hardware.org/?probe=1f84fe45f8) | Nov 05, 2023 |
| Dell          | 0WMJ54 A01                  | [5cff6ffdfc](https://linux-hardware.org/?probe=5cff6ffdfc) | Nov 05, 2023 |
| MSI           | NIGHTBLADE Z97              | [3da62b47b3](https://linux-hardware.org/?probe=3da62b47b3) | Nov 05, 2023 |
| Gigabyte      | B450M GAMING-CF             | [247cc16161](https://linux-hardware.org/?probe=247cc16161) | Nov 05, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | [5196f9303d](https://linux-hardware.org/?probe=5196f9303d) | Nov 05, 2023 |
| ASUSTek       | P5Q-PRO                     | [a1500e2e9c](https://linux-hardware.org/?probe=a1500e2e9c) | Nov 05, 2023 |
| Dell          | 062TCH A00                  | [b82fbd03d5](https://linux-hardware.org/?probe=b82fbd03d5) | Nov 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | [2cbd472a6e](https://linux-hardware.org/?probe=2cbd472a6e) | Nov 05, 2023 |
| Medion        | H110H4-EM                   | [9fe03aa296](https://linux-hardware.org/?probe=9fe03aa296) | Nov 04, 2023 |
| ASUSTek       | PRIME X470-PRO              | [c1523fb6a1](https://linux-hardware.org/?probe=c1523fb6a1) | Nov 04, 2023 |
| ASRock        | H470M-STX                   | [5a50d371b8](https://linux-hardware.org/?probe=5a50d371b8) | Nov 04, 2023 |
| Gigabyte      | GA-MA78LMT-S2               | [1636a231b2](https://linux-hardware.org/?probe=1636a231b2) | Nov 04, 2023 |
| HP            | 0A9Ch                       | [95415dec13](https://linux-hardware.org/?probe=95415dec13) | Nov 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [905d699d4d](https://linux-hardware.org/?probe=905d699d4d) | Nov 04, 2023 |
| Dell          | 062TCH A00                  | [b964b2c6be](https://linux-hardware.org/?probe=b964b2c6be) | Nov 04, 2023 |
| ASUSTek       | PRIME H510M-E               | [cd2b005e61](https://linux-hardware.org/?probe=cd2b005e61) | Nov 04, 2023 |
| Dell          | 018D1Y A00                  | [2135015e09](https://linux-hardware.org/?probe=2135015e09) | Nov 04, 2023 |
| Intel         | DG41RQ AAE54511-203         | [dff06d88c5](https://linux-hardware.org/?probe=dff06d88c5) | Nov 03, 2023 |
| Supermicro    | X9DRW                       | [d9bb198389](https://linux-hardware.org/?probe=d9bb198389) | Nov 03, 2023 |
| Supermicro    | X10DRL-i                    | [cada5224ab](https://linux-hardware.org/?probe=cada5224ab) | Nov 03, 2023 |
| Colorful T... | CVN X570M GAMING PRO V14    | [65b9bad459](https://linux-hardware.org/?probe=65b9bad459) | Nov 03, 2023 |
| Intel         | X99                         | [cb3515efba](https://linux-hardware.org/?probe=cb3515efba) | Nov 03, 2023 |
| Dell          | 0TDG4V A01                  | [9d9b09db51](https://linux-hardware.org/?probe=9d9b09db51) | Nov 03, 2023 |
| MSI           | B350 PC MATE                | [9c089ed10c](https://linux-hardware.org/?probe=9c089ed10c) | Nov 03, 2023 |
| Supermicro    | X10DRU-i+B                  | [305ce5bbcc](https://linux-hardware.org/?probe=305ce5bbcc) | Nov 03, 2023 |
| Supermicro    | X10DDW-i                    | [8a0ff875f1](https://linux-hardware.org/?probe=8a0ff875f1) | Nov 03, 2023 |
| Supermicro    | X10DDW-i                    | [3138fbde8e](https://linux-hardware.org/?probe=3138fbde8e) | Nov 03, 2023 |
| Supermicro    | X10DDW-i                    | [f3023a2a6f](https://linux-hardware.org/?probe=f3023a2a6f) | Nov 03, 2023 |
| Supermicro    | X10DDW-i                    | [d9dcb6003e](https://linux-hardware.org/?probe=d9dcb6003e) | Nov 03, 2023 |
| NEC Comput... | MS-7770MH                   | [9d2ab645d4](https://linux-hardware.org/?probe=9d2ab645d4) | Nov 03, 2023 |
| Fujitsu Si... | G31T-M2 V3.02               | [d069c6012d](https://linux-hardware.org/?probe=d069c6012d) | Nov 03, 2023 |
| ASUSTek       | Z97M-PLUS                   | [b0d77e36b1](https://linux-hardware.org/?probe=b0d77e36b1) | Nov 03, 2023 |
| ASRock        | B450M Steel Legend          | [dafce26ef5](https://linux-hardware.org/?probe=dafce26ef5) | Nov 02, 2023 |
| Dell          | 0VHWTR A01                  | [7d589af687](https://linux-hardware.org/?probe=7d589af687) | Nov 02, 2023 |
| Dell          | 0VHWTR A01                  | [b5c8e35523](https://linux-hardware.org/?probe=b5c8e35523) | Nov 02, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [ea92d94742](https://linux-hardware.org/?probe=ea92d94742) | Nov 02, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS        | [99b1ce4372](https://linux-hardware.org/?probe=99b1ce4372) | Nov 02, 2023 |
| Acer          | Nitro N50-600 V:1.1         | [b2c5bb3ed9](https://linux-hardware.org/?probe=b2c5bb3ed9) | Nov 02, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [bf075c47d2](https://linux-hardware.org/?probe=bf075c47d2) | Nov 02, 2023 |
| Intel         | X99                         | [b740510fc0](https://linux-hardware.org/?probe=b740510fc0) | Nov 02, 2023 |
| Supermicro    | X10DRU-i+A                  | [2eee634512](https://linux-hardware.org/?probe=2eee634512) | Nov 02, 2023 |
| Supermicro    | X9DRW                       | [406a1425ae](https://linux-hardware.org/?probe=406a1425ae) | Nov 02, 2023 |
| Supermicro    | X10DRL-i                    | [7d77c86bc5](https://linux-hardware.org/?probe=7d77c86bc5) | Nov 02, 2023 |
| Dell          | 0FXD80 A00                  | [d9b51a3a36](https://linux-hardware.org/?probe=d9b51a3a36) | Nov 02, 2023 |
| AOpen         | D2644 S26361-D2644          | [db682d636c](https://linux-hardware.org/?probe=db682d636c) | Nov 02, 2023 |
| BESSTAR Te... | TH50                        | [fc3a35871e](https://linux-hardware.org/?probe=fc3a35871e) | Nov 02, 2023 |
| MSI           | Z170A GAMING M7             | [9ba4f50201](https://linux-hardware.org/?probe=9ba4f50201) | Nov 02, 2023 |
| ASUSTek       | PRIME A320M-K               | [1b1df273f9](https://linux-hardware.org/?probe=1b1df273f9) | Nov 01, 2023 |
| MSI           | A320M-A PRO MAX             | [f1e35faa1a](https://linux-hardware.org/?probe=f1e35faa1a) | Nov 01, 2023 |
| MSI           | Z170A GAMING M7             | [a613aa5a0f](https://linux-hardware.org/?probe=a613aa5a0f) | Nov 01, 2023 |
| ASRock        | Z690 Taichi                 | [b736058f88](https://linux-hardware.org/?probe=b736058f88) | Nov 01, 2023 |
| HP            | 0A58h                       | [9dd3c3fdfb](https://linux-hardware.org/?probe=9dd3c3fdfb) | Nov 01, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [70365949d8](https://linux-hardware.org/?probe=70365949d8) | Nov 01, 2023 |
| Gigabyte      | Z370N WIFI-CF               | [1ab426a7ed](https://linux-hardware.org/?probe=1ab426a7ed) | Nov 01, 2023 |
| Lenovo        | 3704 SDK0J40700 WIN 3258... | [3987d09af3](https://linux-hardware.org/?probe=3987d09af3) | Nov 01, 2023 |
| ASUSTek       | Z97-AR                      | [39741158bc](https://linux-hardware.org/?probe=39741158bc) | Nov 01, 2023 |
| Gateway       | FX6840                      | [3c391c7868](https://linux-hardware.org/?probe=3c391c7868) | Nov 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [4881df8aec](https://linux-hardware.org/?probe=4881df8aec) | Nov 01, 2023 |
| ASUSTek       | Z170M-PLUS                  | [92b5f4172e](https://linux-hardware.org/?probe=92b5f4172e) | Nov 01, 2023 |
| Gigabyte      | AX370M-Gaming 3-CF          | [3e5415671f](https://linux-hardware.org/?probe=3e5415671f) | Nov 01, 2023 |
| Gigabyte      | A520M K V2                  | [10670f1068](https://linux-hardware.org/?probe=10670f1068) | Nov 01, 2023 |
| Dell          | 09KPNV A01                  | [2477bc3b6a](https://linux-hardware.org/?probe=2477bc3b6a) | Nov 01, 2023 |
| ASUSTek       | PRIME B450M-A               | [8f885b5a65](https://linux-hardware.org/?probe=8f885b5a65) | Nov 01, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [ea285340e0](https://linux-hardware.org/?probe=ea285340e0) | Nov 01, 2023 |
| Gigabyte      | GA-MA770-DS3                | [968cf90d9a](https://linux-hardware.org/?probe=968cf90d9a) | Nov 01, 2023 |
| ASUSTek       | M5A97 R2.0                  | [8c9a8c3bcc](https://linux-hardware.org/?probe=8c9a8c3bcc) | Oct 31, 2023 |
| ASRock        | H310CM-HDV                  | [b24b974555](https://linux-hardware.org/?probe=b24b974555) | Oct 31, 2023 |
| HP            | 0A58h                       | [f7c62b9410](https://linux-hardware.org/?probe=f7c62b9410) | Oct 31, 2023 |
| MSI           | H81M-E34                    | [0babe23a9d](https://linux-hardware.org/?probe=0babe23a9d) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | [5787618dae](https://linux-hardware.org/?probe=5787618dae) | Oct 31, 2023 |
| MSI           | B85-G43 GAMING              | [5d218dd764](https://linux-hardware.org/?probe=5d218dd764) | Oct 31, 2023 |
| Unknown       | Unknown                     | [4e9f4aa1ab](https://linux-hardware.org/?probe=4e9f4aa1ab) | Oct 31, 2023 |
| MSI           | MPG B650 CARBON WIFI        | [fdc23b8b95](https://linux-hardware.org/?probe=fdc23b8b95) | Oct 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VI HERO       | [dd9715f35d](https://linux-hardware.org/?probe=dd9715f35d) | Oct 31, 2023 |
| Dell          | 0P01GV A03                  | [c77bed1e18](https://linux-hardware.org/?probe=c77bed1e18) | Oct 31, 2023 |
| ASUSTek       | PRIME B360M-C               | [874efda598](https://linux-hardware.org/?probe=874efda598) | Oct 31, 2023 |
| ASUSTek       | PRIME B360M-C               | [16da68741a](https://linux-hardware.org/?probe=16da68741a) | Oct 31, 2023 |
| Gigabyte      | GA-970A-UD3                 | [98b1bd5970](https://linux-hardware.org/?probe=98b1bd5970) | Oct 31, 2023 |
| Win elemen... | M600                        | [205389ccc2](https://linux-hardware.org/?probe=205389ccc2) | Oct 31, 2023 |
| Win elemen... | M600                        | [f1a08307c8](https://linux-hardware.org/?probe=f1a08307c8) | Oct 31, 2023 |
| HP            | 1589                        | [2161dc3754](https://linux-hardware.org/?probe=2161dc3754) | Oct 31, 2023 |
| ASUSTek       | PRIME X399-A                | [69f596f456](https://linux-hardware.org/?probe=69f596f456) | Oct 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [daffd3cd06](https://linux-hardware.org/?probe=daffd3cd06) | Oct 30, 2023 |
| AZW           | MINI S 10                   | [9695f9bec4](https://linux-hardware.org/?probe=9695f9bec4) | Oct 30, 2023 |
| Pegatron      | 2AB6                        | [7bcf41bb9f](https://linux-hardware.org/?probe=7bcf41bb9f) | Oct 30, 2023 |
| Gigabyte      | GA-970A-D3                  | [38ae588910](https://linux-hardware.org/?probe=38ae588910) | Oct 30, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | [771ada77a7](https://linux-hardware.org/?probe=771ada77a7) | Oct 30, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [b4f34c54ae](https://linux-hardware.org/?probe=b4f34c54ae) | Oct 30, 2023 |
| ASUSTek       | GA35DX                      | [c1e204e6b1](https://linux-hardware.org/?probe=c1e204e6b1) | Oct 30, 2023 |
| ASUSTek       | STRIX H270F GAMING          | [1c1290e065](https://linux-hardware.org/?probe=1c1290e065) | Oct 30, 2023 |
| MSI           | B85-G43 GAMING              | [fa91d8044f](https://linux-hardware.org/?probe=fa91d8044f) | Oct 30, 2023 |
| HP            | 8436                        | [4fe5c2e03c](https://linux-hardware.org/?probe=4fe5c2e03c) | Oct 30, 2023 |
| Supermicro    | X10DRU-i+B                  | [516d10eb4d](https://linux-hardware.org/?probe=516d10eb4d) | Oct 30, 2023 |
| Supermicro    | X10DRU-i+A                  | [87881094e7](https://linux-hardware.org/?probe=87881094e7) | Oct 30, 2023 |
| Supermicro    | X10DDW-i                    | [175f00718f](https://linux-hardware.org/?probe=175f00718f) | Oct 30, 2023 |
| Supermicro    | X10DDW-i                    | [a3b51e3697](https://linux-hardware.org/?probe=a3b51e3697) | Oct 30, 2023 |
| Dell          | 018D1Y A00                  | [ce361a7112](https://linux-hardware.org/?probe=ce361a7112) | Oct 30, 2023 |
| ASRock        | Z690 Taichi                 | [a9e193be90](https://linux-hardware.org/?probe=a9e193be90) | Oct 30, 2023 |
| ASUSTek       | PRIME X370-PRO              | [394ab5dbff](https://linux-hardware.org/?probe=394ab5dbff) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [102224106e](https://linux-hardware.org/?probe=102224106e) | Oct 30, 2023 |
| AZW           | SEi                         | [aa8ba45b77](https://linux-hardware.org/?probe=aa8ba45b77) | Oct 30, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [186a763d8a](https://linux-hardware.org/?probe=186a763d8a) | Oct 29, 2023 |
| Gigabyte      | GA-770TA-UD3                | [f1a5d466cd](https://linux-hardware.org/?probe=f1a5d466cd) | Oct 29, 2023 |
| Medion        | H110H4-EM                   | [1a2d0e5ed4](https://linux-hardware.org/?probe=1a2d0e5ed4) | Oct 29, 2023 |
| MSI           | X299 TOMAHAWK AC            | [b878ce40e7](https://linux-hardware.org/?probe=b878ce40e7) | Oct 29, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [4e093f6544](https://linux-hardware.org/?probe=4e093f6544) | Oct 29, 2023 |
| Biostar       | G31D-M7                     | [192416033b](https://linux-hardware.org/?probe=192416033b) | Oct 28, 2023 |
| MSI           | B360 GAMING PLUS            | [bb17f05c7f](https://linux-hardware.org/?probe=bb17f05c7f) | Oct 28, 2023 |
| ASUSTek       | P5Q-PRO                     | [2722dd43f2](https://linux-hardware.org/?probe=2722dd43f2) | Oct 28, 2023 |
| MSI           | B450M-A PRO MAX             | [84c2a8040c](https://linux-hardware.org/?probe=84c2a8040c) | Oct 28, 2023 |
| HP            | 1589                        | [fe31fa1d5e](https://linux-hardware.org/?probe=fe31fa1d5e) | Oct 28, 2023 |
| HP            | 1589                        | [5d14d38ded](https://linux-hardware.org/?probe=5d14d38ded) | Oct 28, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [8157e9bd12](https://linux-hardware.org/?probe=8157e9bd12) | Oct 28, 2023 |
| Gateway       | WG43M                       | [8f0cb70746](https://linux-hardware.org/?probe=8f0cb70746) | Oct 28, 2023 |
| Gigabyte      | B75M-D3H                    | [97d8cfe6f0](https://linux-hardware.org/?probe=97d8cfe6f0) | Oct 28, 2023 |
| HP            | 2B05                        | [a32b598fb9](https://linux-hardware.org/?probe=a32b598fb9) | Oct 28, 2023 |
| HP            | 158A                        | [f8fe5be681](https://linux-hardware.org/?probe=f8fe5be681) | Oct 28, 2023 |
| HP            | 2AF3                        | [f7c7d92cea](https://linux-hardware.org/?probe=f7c7d92cea) | Oct 28, 2023 |
| Intel         | H61                         | [1496665abb](https://linux-hardware.org/?probe=1496665abb) | Oct 27, 2023 |
| Lenovo        | SDK0J40700 WIN              | [09f4736f4f](https://linux-hardware.org/?probe=09f4736f4f) | Oct 27, 2023 |
| Supermicro    | X10DDW-i                    | [4ae7cd098c](https://linux-hardware.org/?probe=4ae7cd098c) | Oct 27, 2023 |
| Supermicro    | X10DDW-i                    | [27eeb454c8](https://linux-hardware.org/?probe=27eeb454c8) | Oct 27, 2023 |
| Supermicro    | X10DDW-i                    | [a822fb4575](https://linux-hardware.org/?probe=a822fb4575) | Oct 27, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [05961f3f8d](https://linux-hardware.org/?probe=05961f3f8d) | Oct 27, 2023 |
| Supermicro    | X10DDW-i                    | [7b1a0dde51](https://linux-hardware.org/?probe=7b1a0dde51) | Oct 27, 2023 |
| Dell          | 0JCTF8 A00                  | [3cc39678ff](https://linux-hardware.org/?probe=3cc39678ff) | Oct 27, 2023 |
| Gateway       | FX6840                      | [7acd4709ef](https://linux-hardware.org/?probe=7acd4709ef) | Oct 27, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [8555f763b4](https://linux-hardware.org/?probe=8555f763b4) | Oct 27, 2023 |
| MSI           | 2A9Ch                       | [3e7da65a41](https://linux-hardware.org/?probe=3e7da65a41) | Oct 27, 2023 |
| MSI           | 2A9Ch                       | [6b9e5b921c](https://linux-hardware.org/?probe=6b9e5b921c) | Oct 27, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [2021aa6173](https://linux-hardware.org/?probe=2021aa6173) | Oct 27, 2023 |
| Supermicro    | X10DDW-i                    | [6afb6d264d](https://linux-hardware.org/?probe=6afb6d264d) | Oct 27, 2023 |
| Supermicro    | X10DDW-i                    | [36fadbfb7a](https://linux-hardware.org/?probe=36fadbfb7a) | Oct 27, 2023 |
| HP            | 8433 11                     | [f4b0e9190f](https://linux-hardware.org/?probe=f4b0e9190f) | Oct 27, 2023 |
| HP            | 2AF7                        | [3143f79dcd](https://linux-hardware.org/?probe=3143f79dcd) | Oct 27, 2023 |
| HP            | 0A9Ch                       | [f24350a95c](https://linux-hardware.org/?probe=f24350a95c) | Oct 27, 2023 |
| HP            | 1998                        | [4701148920](https://linux-hardware.org/?probe=4701148920) | Oct 26, 2023 |
| Gigabyte      | 965P-S3                     | [ae3a4e206c](https://linux-hardware.org/?probe=ae3a4e206c) | Oct 26, 2023 |
| ASUSTek       | PRIME Z370-A                | [75fcf950c2](https://linux-hardware.org/?probe=75fcf950c2) | Oct 26, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [bcbce33659](https://linux-hardware.org/?probe=bcbce33659) | Oct 26, 2023 |
| Gigabyte      | H110M-H-CF                  | [b64c6bb72a](https://linux-hardware.org/?probe=b64c6bb72a) | Oct 26, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | [6c7a32d339](https://linux-hardware.org/?probe=6c7a32d339) | Oct 26, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | [f3802ecf63](https://linux-hardware.org/?probe=f3802ecf63) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [f43adee740](https://linux-hardware.org/?probe=f43adee740) | Oct 26, 2023 |
| Gigabyte      | GA-770TA-UD3                | [6944656466](https://linux-hardware.org/?probe=6944656466) | Oct 26, 2023 |
| ASUSTek       | Z170-A                      | [7d69a76c23](https://linux-hardware.org/?probe=7d69a76c23) | Oct 26, 2023 |
| Foxconn       | 2AA9h                       | [dade54701d](https://linux-hardware.org/?probe=dade54701d) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | [534c2c528c](https://linux-hardware.org/?probe=534c2c528c) | Oct 26, 2023 |
| ASUSTek       | Maximus VII HERO            | [87c313ac06](https://linux-hardware.org/?probe=87c313ac06) | Oct 26, 2023 |
| MSI           | MAG Z490 TOMAHAWK           | [1ad6c144a3](https://linux-hardware.org/?probe=1ad6c144a3) | Oct 26, 2023 |
| ASUSTek       | Maximus VII HERO            | [a0e6502d94](https://linux-hardware.org/?probe=a0e6502d94) | Oct 26, 2023 |
| HP            | 158A                        | [86f988197b](https://linux-hardware.org/?probe=86f988197b) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [6709fab81c](https://linux-hardware.org/?probe=6709fab81c) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [c041582324](https://linux-hardware.org/?probe=c041582324) | Oct 26, 2023 |
| HP            | 8265                        | [25dfe4d311](https://linux-hardware.org/?probe=25dfe4d311) | Oct 26, 2023 |
| ASUSTek       | P6X58-E-WS                  | [abb9f306b8](https://linux-hardware.org/?probe=abb9f306b8) | Oct 25, 2023 |
| HP            | 822A                        | [4d1e3ee1f2](https://linux-hardware.org/?probe=4d1e3ee1f2) | Oct 25, 2023 |
| ASRock        | A520M-ITX/ac                | [8a5e0bd9d6](https://linux-hardware.org/?probe=8a5e0bd9d6) | Oct 25, 2023 |
| Acer          | Aspire GX-281               | [63c928a75f](https://linux-hardware.org/?probe=63c928a75f) | Oct 25, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [25c0172035](https://linux-hardware.org/?probe=25c0172035) | Oct 25, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [b38766677c](https://linux-hardware.org/?probe=b38766677c) | Oct 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e090fa6279](https://linux-hardware.org/?probe=e090fa6279) | Oct 25, 2023 |
| Acer          | Veriton S2680G              | [da9a811b04](https://linux-hardware.org/?probe=da9a811b04) | Oct 25, 2023 |
| ASUSTek       | PRIME B450M-A               | [deac292d7d](https://linux-hardware.org/?probe=deac292d7d) | Oct 25, 2023 |
| ASUSTek       | Q87M-E                      | [69e78c6a85](https://linux-hardware.org/?probe=69e78c6a85) | Oct 25, 2023 |
| System76      | Thelio Mira                 | [3bb1924402](https://linux-hardware.org/?probe=3bb1924402) | Oct 25, 2023 |
| MSI           | 2A9C                        | [d87ee22b95](https://linux-hardware.org/?probe=d87ee22b95) | Oct 24, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | [b8ac729343](https://linux-hardware.org/?probe=b8ac729343) | Oct 24, 2023 |
| Dell          | 06FW8P A02                  | [4efc493619](https://linux-hardware.org/?probe=4efc493619) | Oct 24, 2023 |
| ASUSTek       | P8P67 EVO                   | [3baa020480](https://linux-hardware.org/?probe=3baa020480) | Oct 24, 2023 |
| Acer          | Aspire XC-1760              | [8a5c420847](https://linux-hardware.org/?probe=8a5c420847) | Oct 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [54a6d9d5d0](https://linux-hardware.org/?probe=54a6d9d5d0) | Oct 24, 2023 |
| Unknown       | 1.1                         | [c006e77646](https://linux-hardware.org/?probe=c006e77646) | Oct 24, 2023 |
| HP            | 1589                        | [1a61614ad2](https://linux-hardware.org/?probe=1a61614ad2) | Oct 24, 2023 |
| ASUSTek       | PRIME A320M-K               | [d09253d43a](https://linux-hardware.org/?probe=d09253d43a) | Oct 24, 2023 |
| Gigabyte      | B450M DS3H-CF               | [9b0be83ecc](https://linux-hardware.org/?probe=9b0be83ecc) | Oct 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [2d6bcd74d8](https://linux-hardware.org/?probe=2d6bcd74d8) | Oct 24, 2023 |
| Google        | Teemo                       | [ae5140ac26](https://linux-hardware.org/?probe=ae5140ac26) | Oct 24, 2023 |
| Lenovo        | 0B98409 STD                 | [b89f42b23f](https://linux-hardware.org/?probe=b89f42b23f) | Oct 24, 2023 |
| Dell          | 097YXY A00                  | [31dc22d5af](https://linux-hardware.org/?probe=31dc22d5af) | Oct 24, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | [6c35175e9c](https://linux-hardware.org/?probe=6c35175e9c) | Oct 24, 2023 |
| ASRock        | 880GMH/USB3                 | [4d3fcc56ec](https://linux-hardware.org/?probe=4d3fcc56ec) | Oct 24, 2023 |
| Inventec      | D CLASS A02                 | [41bf70ff0b](https://linux-hardware.org/?probe=41bf70ff0b) | Oct 23, 2023 |
| HP            | 83EF                        | [9a8026df67](https://linux-hardware.org/?probe=9a8026df67) | Oct 23, 2023 |
| Acer          | Aspire GX-281               | [0d96eb845d](https://linux-hardware.org/?probe=0d96eb845d) | Oct 23, 2023 |
| ASUSTek       | Z97-A                       | [c715f1ecb0](https://linux-hardware.org/?probe=c715f1ecb0) | Oct 23, 2023 |
| ASUSTek       | H110M-A                     | [a721fea460](https://linux-hardware.org/?probe=a721fea460) | Oct 23, 2023 |
| Gigabyte      | H310M H x.x                 | [d8c12e782e](https://linux-hardware.org/?probe=d8c12e782e) | Oct 23, 2023 |
| Dell          | 0TDG4V A01                  | [932adc1d60](https://linux-hardware.org/?probe=932adc1d60) | Oct 23, 2023 |
| Acer          | WG43M                       | [0580e7ab1b](https://linux-hardware.org/?probe=0580e7ab1b) | Oct 23, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [9ab95fedc6](https://linux-hardware.org/?probe=9ab95fedc6) | Oct 23, 2023 |
| Intel         | DB65AL AAG12530-307         | [09cf560035](https://linux-hardware.org/?probe=09cf560035) | Oct 23, 2023 |
| MSI           | 970 GAMING                  | [dfcfacf8d5](https://linux-hardware.org/?probe=dfcfacf8d5) | Oct 23, 2023 |
| ASRock        | Z490M-ITX/ac                | [98a9374798](https://linux-hardware.org/?probe=98a9374798) | Oct 22, 2023 |
| HP            | 3399                        | [3dca1c2950](https://linux-hardware.org/?probe=3dca1c2950) | Oct 22, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [fb66b6579d](https://linux-hardware.org/?probe=fb66b6579d) | Oct 22, 2023 |
| Fujitsu       | D3601-A1 S26361-D3601-A1    | [dba9cc7689](https://linux-hardware.org/?probe=dba9cc7689) | Oct 22, 2023 |
| Trigkey       | Green G5                    | [a0cb634fc5](https://linux-hardware.org/?probe=a0cb634fc5) | Oct 22, 2023 |
| Packard Be... | FIH57                       | [322f0cceaa](https://linux-hardware.org/?probe=322f0cceaa) | Oct 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | [b6df3ae720](https://linux-hardware.org/?probe=b6df3ae720) | Oct 22, 2023 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | [b3397c9aa2](https://linux-hardware.org/?probe=b3397c9aa2) | Oct 22, 2023 |
| ASUSTek       | P8H67                       | [5e8558b08d](https://linux-hardware.org/?probe=5e8558b08d) | Oct 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [d38a6fb326](https://linux-hardware.org/?probe=d38a6fb326) | Oct 22, 2023 |
| MSI           | MS-7309                     | [b747d8e3a3](https://linux-hardware.org/?probe=b747d8e3a3) | Oct 22, 2023 |
| Dell          | 0YXT71 A00                  | [5f04088965](https://linux-hardware.org/?probe=5f04088965) | Oct 22, 2023 |
| HP            | 18E5                        | [95cc2c3a9c](https://linux-hardware.org/?probe=95cc2c3a9c) | Oct 22, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [ad17620d9f](https://linux-hardware.org/?probe=ad17620d9f) | Oct 21, 2023 |
| ASRock        | H61M-HVS                    | [cd365d2e35](https://linux-hardware.org/?probe=cd365d2e35) | Oct 21, 2023 |
| Lenovo        | ThinkServer TS140           | [b52eba9a1b](https://linux-hardware.org/?probe=b52eba9a1b) | Oct 21, 2023 |
| Gigabyte      | B450M DS3H-CF               | [30d9002099](https://linux-hardware.org/?probe=30d9002099) | Oct 21, 2023 |
| HP            | ML150 G3                    | [eb5a4bfed8](https://linux-hardware.org/?probe=eb5a4bfed8) | Oct 21, 2023 |
| ASUSTek       | Rampage III Extreme         | [36827ef46c](https://linux-hardware.org/?probe=36827ef46c) | Oct 21, 2023 |
| ASUSTek       | P9X79                       | [3df64c6ee4](https://linux-hardware.org/?probe=3df64c6ee4) | Oct 21, 2023 |
| ASRock        | 870 Extreme3 R2.0           | [a625868a25](https://linux-hardware.org/?probe=a625868a25) | Oct 21, 2023 |
| Gigabyte      | Z77M-D3H                    | [0dcc624a0d](https://linux-hardware.org/?probe=0dcc624a0d) | Oct 21, 2023 |
| Packard Be... | FIH57                       | [b16d87199a](https://linux-hardware.org/?probe=b16d87199a) | Oct 21, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [9286fa6477](https://linux-hardware.org/?probe=9286fa6477) | Oct 21, 2023 |
| Intel         | X79G V2.x                   | [49d37b87cf](https://linux-hardware.org/?probe=49d37b87cf) | Oct 21, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [673aa81f04](https://linux-hardware.org/?probe=673aa81f04) | Oct 21, 2023 |
| ASRock        | Z690 Taichi                 | [b249afcf52](https://linux-hardware.org/?probe=b249afcf52) | Oct 21, 2023 |
| ASUSTek       | H110M-A                     | [2ad6656255](https://linux-hardware.org/?probe=2ad6656255) | Oct 21, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [a3af824c75](https://linux-hardware.org/?probe=a3af824c75) | Oct 20, 2023 |
| HP            | 83E9                        | [20501a2966](https://linux-hardware.org/?probe=20501a2966) | Oct 20, 2023 |
| ASUSTek       | H110M-A                     | [4aaa66c7bc](https://linux-hardware.org/?probe=4aaa66c7bc) | Oct 20, 2023 |
| Intel         | D53427RKE G87971-406        | [01b0785dea](https://linux-hardware.org/?probe=01b0785dea) | Oct 20, 2023 |
| ASRock        | Z690 Taichi                 | [a49686cc23](https://linux-hardware.org/?probe=a49686cc23) | Oct 20, 2023 |
| Intel         | D33217CK G76541-300         | [967b9f4bbe](https://linux-hardware.org/?probe=967b9f4bbe) | Oct 20, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [bae930bd47](https://linux-hardware.org/?probe=bae930bd47) | Oct 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | [2ca3451a04](https://linux-hardware.org/?probe=2ca3451a04) | Oct 20, 2023 |
| MSI           | PRO B760M-P DDR4            | [87f50ecd22](https://linux-hardware.org/?probe=87f50ecd22) | Oct 20, 2023 |
| MSI           | PRO B760M-P DDR4            | [23f0d88b97](https://linux-hardware.org/?probe=23f0d88b97) | Oct 20, 2023 |
| ASRock        | B660-ITX                    | [b3a7dac908](https://linux-hardware.org/?probe=b3a7dac908) | Oct 20, 2023 |
| HP            | 0AA0h                       | [4175b0f530](https://linux-hardware.org/?probe=4175b0f530) | Oct 20, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [c123099547](https://linux-hardware.org/?probe=c123099547) | Oct 20, 2023 |
| MSI           | B85M-E45                    | [faedd980e0](https://linux-hardware.org/?probe=faedd980e0) | Oct 20, 2023 |
| ASUSTek       | UN62                        | [a1cb1227bf](https://linux-hardware.org/?probe=a1cb1227bf) | Oct 20, 2023 |
| ASUSTek       | UN62                        | [48e1c6f6e2](https://linux-hardware.org/?probe=48e1c6f6e2) | Oct 20, 2023 |
| HP            | 3397                        | [7622910000](https://linux-hardware.org/?probe=7622910000) | Oct 20, 2023 |
| HP            | 2B4B                        | [d23d9f0e33](https://linux-hardware.org/?probe=d23d9f0e33) | Oct 20, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [82633fd1ef](https://linux-hardware.org/?probe=82633fd1ef) | Oct 19, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [0fa5f53ce0](https://linux-hardware.org/?probe=0fa5f53ce0) | Oct 19, 2023 |
| Supermicro    | X10DDW-i                    | [7f765cc00f](https://linux-hardware.org/?probe=7f765cc00f) | Oct 19, 2023 |
| Supermicro    | X10DDW-i                    | [fbe57c97ea](https://linux-hardware.org/?probe=fbe57c97ea) | Oct 19, 2023 |
| Supermicro    | X10DRL-i                    | [3ff4f4f39b](https://linux-hardware.org/?probe=3ff4f4f39b) | Oct 19, 2023 |
| Supermicro    | X10DDW-i                    | [bc6515ee92](https://linux-hardware.org/?probe=bc6515ee92) | Oct 19, 2023 |
| Supermicro    | X10DDW-i                    | [2d8d01b0df](https://linux-hardware.org/?probe=2d8d01b0df) | Oct 19, 2023 |
| Supermicro    | X10DDW-i                    | [494b45d07d](https://linux-hardware.org/?probe=494b45d07d) | Oct 19, 2023 |
| Supermicro    | X10DRL-i                    | [f25155c26d](https://linux-hardware.org/?probe=f25155c26d) | Oct 19, 2023 |
| Supermicro    | X10DRL-i                    | [78fdf3830c](https://linux-hardware.org/?probe=78fdf3830c) | Oct 19, 2023 |
| Acer          | Aspire TC-330               | [99424bb03e](https://linux-hardware.org/?probe=99424bb03e) | Oct 19, 2023 |
| MSI           | H81M-E34                    | [18c6eb940d](https://linux-hardware.org/?probe=18c6eb940d) | Oct 19, 2023 |
| HP            | 1496                        | [c0c1d4b920](https://linux-hardware.org/?probe=c0c1d4b920) | Oct 19, 2023 |
| HP            | 3397                        | [555ad3c716](https://linux-hardware.org/?probe=555ad3c716) | Oct 19, 2023 |
| Acer          | Aspire TC-330               | [ddabdcc2b7](https://linux-hardware.org/?probe=ddabdcc2b7) | Oct 19, 2023 |
| Foxconn       | 2AB1                        | [ce52d37a5f](https://linux-hardware.org/?probe=ce52d37a5f) | Oct 19, 2023 |
| MSI           | FM2-A75MA-E35               | [868a2c328d](https://linux-hardware.org/?probe=868a2c328d) | Oct 19, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | [0c6accd4fc](https://linux-hardware.org/?probe=0c6accd4fc) | Oct 19, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | [c05a67e739](https://linux-hardware.org/?probe=c05a67e739) | Oct 19, 2023 |
| Dell          | 0T10XW A02                  | [359e8bb86f](https://linux-hardware.org/?probe=359e8bb86f) | Oct 18, 2023 |
| Gigabyte      | M52L-S3P                    | [6c4a10bf6e](https://linux-hardware.org/?probe=6c4a10bf6e) | Oct 18, 2023 |
| Gigabyte      | A320M-S2H-CF                | [3745e48bdc](https://linux-hardware.org/?probe=3745e48bdc) | Oct 18, 2023 |
| Gigabyte      | Z370N WIFI-CF               | [df8d309418](https://linux-hardware.org/?probe=df8d309418) | Oct 18, 2023 |
| Supermicro    | X10DDW-i                    | [b3685de812](https://linux-hardware.org/?probe=b3685de812) | Oct 18, 2023 |
| Supermicro    | X10DDW-i                    | [a84fa735c7](https://linux-hardware.org/?probe=a84fa735c7) | Oct 18, 2023 |
| HP            | 18E7                        | [3beee97f8b](https://linux-hardware.org/?probe=3beee97f8b) | Oct 18, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | [534b565ca1](https://linux-hardware.org/?probe=534b565ca1) | Oct 18, 2023 |
| Supermicro    | X10DRU-i+B                  | [f2e360b8e4](https://linux-hardware.org/?probe=f2e360b8e4) | Oct 18, 2023 |
| Supermicro    | X10DRU-i+A                  | [1245e9bcc8](https://linux-hardware.org/?probe=1245e9bcc8) | Oct 18, 2023 |
| Supermicro    | X9DRW                       | [c57bad94cc](https://linux-hardware.org/?probe=c57bad94cc) | Oct 18, 2023 |
| ASRock        | 970 Pro3 R2.0               | [dbb30ccac0](https://linux-hardware.org/?probe=dbb30ccac0) | Oct 18, 2023 |
| Supermicro    | X10DRU-i+A                  | [8f574baa5b](https://linux-hardware.org/?probe=8f574baa5b) | Oct 18, 2023 |
| HP            | 2B29                        | [70d4194832](https://linux-hardware.org/?probe=70d4194832) | Oct 18, 2023 |
| HP            | 2B29                        | [b4da4bf11d](https://linux-hardware.org/?probe=b4da4bf11d) | Oct 18, 2023 |
| Dell          | 0DR845                      | [4363cfd864](https://linux-hardware.org/?probe=4363cfd864) | Oct 17, 2023 |
| Lenovo        | SHARKBAY NOK                | [15064c45a9](https://linux-hardware.org/?probe=15064c45a9) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [200b756e67](https://linux-hardware.org/?probe=200b756e67) | Oct 17, 2023 |
| ASUSTek       | UN42                        | [53267f9960](https://linux-hardware.org/?probe=53267f9960) | Oct 17, 2023 |
| AMI           | IB70 V202                   | [712b29d6db](https://linux-hardware.org/?probe=712b29d6db) | Oct 17, 2023 |
| Gigabyte      | H310M H x.x                 | [98b06c3d78](https://linux-hardware.org/?probe=98b06c3d78) | Oct 17, 2023 |
| ASUSTek       | P8H67-M PRO                 | [7ebf44d28b](https://linux-hardware.org/?probe=7ebf44d28b) | Oct 17, 2023 |
| Unknown       | Unknown                     | [4e34e33eee](https://linux-hardware.org/?probe=4e34e33eee) | Oct 17, 2023 |
| Unknown       | Unknown                     | [fc0368a716](https://linux-hardware.org/?probe=fc0368a716) | Oct 17, 2023 |
| ASUSTek       | H81M-K                      | [0875e69e22](https://linux-hardware.org/?probe=0875e69e22) | Oct 17, 2023 |
| Intel         | DP35DP AAD81073-208         | [f7059ece0c](https://linux-hardware.org/?probe=f7059ece0c) | Oct 17, 2023 |
| Unknown       | Intel X79                   | [d2553e6cbd](https://linux-hardware.org/?probe=d2553e6cbd) | Oct 17, 2023 |
| HP            | 843B                        | [4f8aa79674](https://linux-hardware.org/?probe=4f8aa79674) | Oct 17, 2023 |
| Gigabyte      | MFLP3CP-00                  | [e2ddb858a9](https://linux-hardware.org/?probe=e2ddb858a9) | Oct 16, 2023 |
| ASRock        | A320M-HDV R3.0              | [95642179a1](https://linux-hardware.org/?probe=95642179a1) | Oct 16, 2023 |
| Dell          | 051FJ8 A00                  | [60bea2da11](https://linux-hardware.org/?probe=60bea2da11) | Oct 16, 2023 |
| Dell          | 0CRH6C A00                  | [861e34ac85](https://linux-hardware.org/?probe=861e34ac85) | Oct 16, 2023 |
| MSI           | 2A9Ch                       | [81c485dfbe](https://linux-hardware.org/?probe=81c485dfbe) | Oct 16, 2023 |
| Unknown       | Unknown                     | [90af9ca939](https://linux-hardware.org/?probe=90af9ca939) | Oct 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | [f12bcba44c](https://linux-hardware.org/?probe=f12bcba44c) | Oct 16, 2023 |
| ASUSTek       | Z170-A                      | [9671bbc29b](https://linux-hardware.org/?probe=9671bbc29b) | Oct 16, 2023 |
| HP            | 0AE4h                       | [a31dd4463f](https://linux-hardware.org/?probe=a31dd4463f) | Oct 16, 2023 |
| HP            | 0AE4h                       | [4ebaa677df](https://linux-hardware.org/?probe=4ebaa677df) | Oct 16, 2023 |
| ASUSTek       | ROG STRIX Z790-A GAMING ... | [e83fde9360](https://linux-hardware.org/?probe=e83fde9360) | Oct 16, 2023 |
| MSI           | B85M-E45                    | [acc8588daa](https://linux-hardware.org/?probe=acc8588daa) | Oct 16, 2023 |
| AZW           | GTR V21                     | [e90b0c01be](https://linux-hardware.org/?probe=e90b0c01be) | Oct 16, 2023 |
| MSI           | 2A9Ch                       | [6b86dab25f](https://linux-hardware.org/?probe=6b86dab25f) | Oct 16, 2023 |
| HP            | 8433 11                     | [24fdb6f03a](https://linux-hardware.org/?probe=24fdb6f03a) | Oct 16, 2023 |
| HP            | ProLiant ML350 Gen9         | [468a686a40](https://linux-hardware.org/?probe=468a686a40) | Oct 15, 2023 |
| Dell          | 0D28YY A01                  | [a69ebf1645](https://linux-hardware.org/?probe=a69ebf1645) | Oct 15, 2023 |
| MSI           | A320M-A PRO MAX             | [3c6ab62b00](https://linux-hardware.org/?probe=3c6ab62b00) | Oct 15, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [c0446b13ce](https://linux-hardware.org/?probe=c0446b13ce) | Oct 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [c84dd6e4ea](https://linux-hardware.org/?probe=c84dd6e4ea) | Oct 15, 2023 |
| Dell          | 0HN7XN A01                  | [6ca94363be](https://linux-hardware.org/?probe=6ca94363be) | Oct 15, 2023 |
| Dell          | 0HN7XN A01                  | [de23701ea4](https://linux-hardware.org/?probe=de23701ea4) | Oct 15, 2023 |
| MSI           | MAG B460M MORTAR WIFI       | [dd3eca03df](https://linux-hardware.org/?probe=dd3eca03df) | Oct 15, 2023 |
| Intel         | X79 V3.0                    | [525be51dcd](https://linux-hardware.org/?probe=525be51dcd) | Oct 15, 2023 |
| ASUSTek       | H81-GAMER                   | [4db3cdfdca](https://linux-hardware.org/?probe=4db3cdfdca) | Oct 15, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [4b5e14f452](https://linux-hardware.org/?probe=4b5e14f452) | Oct 15, 2023 |
| Dell          | 0WR7PY A01                  | [9dbe237209](https://linux-hardware.org/?probe=9dbe237209) | Oct 15, 2023 |
| ASUSTek       | H61M-K                      | [dfee331121](https://linux-hardware.org/?probe=dfee331121) | Oct 15, 2023 |
| ASRock        | B85M                        | [1712e16d1c](https://linux-hardware.org/?probe=1712e16d1c) | Oct 15, 2023 |
| SZMZ          | X99M-G2                     | [1b0f7ae9a7](https://linux-hardware.org/?probe=1b0f7ae9a7) | Oct 15, 2023 |
| MSI           | FM2-A75MA-E35               | [445403f24d](https://linux-hardware.org/?probe=445403f24d) | Oct 15, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_22.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.15.0-56-generic | 291      | 5.3%    |
| 5.15.0-52-generic | 250      | 4.56%   |
| 5.15.0-58-generic | 246      | 4.48%   |
| 5.19.0-35-generic | 212      | 3.86%   |
| 5.15.0-48-generic | 202      | 3.68%   |
| 5.15.0-43-generic | 199      | 3.63%   |
| 5.15.0-47-generic | 196      | 3.57%   |
| 5.19.0-32-generic | 194      | 3.54%   |
| 6.2.0-26-generic  | 190      | 3.46%   |
| 5.19.0-38-generic | 177      | 3.23%   |
| 5.19.0-41-generic | 166      | 3.03%   |
| 6.2.0-36-generic  | 158      | 2.88%   |
| 5.19.0-46-generic | 156      | 2.84%   |
| 5.15.0-53-generic | 151      | 2.75%   |
| 5.15.0-46-generic | 137      | 2.5%    |
| 6.2.0-37-generic  | 130      | 2.37%   |
| 5.15.0-25-generic | 118      | 2.15%   |
| 6.2.0-39-generic  | 106      | 1.93%   |
| 6.2.0-34-generic  | 106      | 1.93%   |
| 5.19.0-43-generic | 106      | 1.93%   |
| 5.15.0-27-generic | 102      | 1.86%   |
| 5.15.0-60-generic | 98       | 1.79%   |
| 5.15.0-41-generic | 93       | 1.7%    |
| 5.15.0-40-generic | 92       | 1.68%   |
| 6.2.0-33-generic  | 90       | 1.64%   |
| 6.2.0-32-generic  | 90       | 1.64%   |
| 6.2.0-35-generic  | 86       | 1.57%   |
| 5.15.0-57-generic | 83       | 1.51%   |
| 5.15.0-50-generic | 80       | 1.46%   |
| 5.19.0-45-generic | 74       | 1.35%   |
| 5.19.0-40-generic | 70       | 1.28%   |
| 5.15.0-67-generic | 63       | 1.15%   |
| 5.15.0-33-generic | 60       | 1.09%   |
| 5.19.0-50-generic | 54       | 0.98%   |
| 5.15.0-30-generic | 53       | 0.97%   |
| 5.15.0-69-generic | 49       | 0.89%   |
| 5.19.0-42-generic | 48       | 0.87%   |
| 5.15.0-39-generic | 46       | 0.84%   |
| 5.15.0-35-generic | 44       | 0.8%    |
| 5.15.0-37-generic | 41       | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 2735     | 55.06%  |
| 5.19.0  | 1153     | 23.21%  |
| 6.2.0   | 934      | 18.8%   |
| 5.17.0  | 19       | 0.38%   |
| 5.13.0  | 15       | 0.3%    |
| 6.1.0   | 9        | 0.18%   |
| 6.5.0   | 6        | 0.12%   |
| 6.0.0   | 6        | 0.12%   |
| 5.18.0  | 5        | 0.1%    |
| 6.0.1   | 3        | 0.06%   |
| 5.19.5  | 3        | 0.06%   |
| 5.18.10 | 3        | 0.06%   |
| 5.17.7  | 3        | 0.06%   |
| 5.10.60 | 3        | 0.06%   |
| 6.4.3   | 2        | 0.04%   |
| 6.4.12  | 2        | 0.04%   |
| 6.4.0   | 2        | 0.04%   |
| 6.2.16  | 2        | 0.04%   |
| 6.2.11  | 2        | 0.04%   |
| 6.1.11  | 2        | 0.04%   |
| 6.0.9   | 2        | 0.04%   |
| 5.8.0   | 2        | 0.04%   |
| 5.19.17 | 2        | 0.04%   |
| 5.17.9  | 2        | 0.04%   |
| 5.17.15 | 2        | 0.04%   |
| 5.15.13 | 2        | 0.04%   |
| 5.14.0  | 2        | 0.04%   |
| 6.7.0   | 1        | 0.02%   |
| 6.6.8   | 1        | 0.02%   |
| 6.6.5   | 1        | 0.02%   |
| 6.6.2   | 1        | 0.02%   |
| 6.5.1   | 1        | 0.02%   |
| 6.4.9   | 1        | 0.02%   |
| 6.4.14  | 1        | 0.02%   |
| 6.4.11  | 1        | 0.02%   |
| 6.3.9   | 1        | 0.02%   |
| 6.3.7   | 1        | 0.02%   |
| 6.3.4   | 1        | 0.02%   |
| 6.3.2   | 1        | 0.02%   |
| 6.3.0   | 1        | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 2738     | 55.15%  |
| 5.19    | 1159     | 23.34%  |
| 6.2     | 944      | 19.01%  |
| 5.17    | 30       | 0.6%    |
| 6.1     | 17       | 0.34%   |
| 5.13    | 15       | 0.3%    |
| 6.0     | 13       | 0.26%   |
| 5.18    | 13       | 0.26%   |
| 6.4     | 9        | 0.18%   |
| 6.5     | 7        | 0.14%   |
| 6.3     | 5        | 0.1%    |
| 6.6     | 3        | 0.06%   |
| 5.10    | 3        | 0.06%   |
| 5.8     | 2        | 0.04%   |
| 5.14    | 2        | 0.04%   |
| 5.11    | 2        | 0.04%   |
| 6.7     | 1        | 0.02%   |
| 5.4     | 1        | 0.02%   |
| 5.16    | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 4724     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 4286     | 90.56%  |
| Unknown         | 285      | 6.02%   |
| GNUstep         | 66       | 1.39%   |
| X-Cinnamon      | 51       | 1.08%   |
| GNOME Flashback | 19       | 0.4%    |
| GNOME Classic   | 10       | 0.21%   |
| i3              | 6        | 0.13%   |
| Enlightenment   | 4        | 0.08%   |
| ubuntu=GNOME    | 1        | 0.02%   |
| ubuntu          | 1        | 0.02%   |
| INPT            | 1        | 0.02%   |
| i3-with-shmlog  | 1        | 0.02%   |
| Cinnamon        | 1        | 0.02%   |
| awesome         | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 2551     | 52.89%  |
| X11     | 1859     | 38.54%  |
| Tty     | 264      | 5.47%   |
| Unknown | 148      | 3.07%   |
| Web     | 1        | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 4098     | 86.36%  |
| Unknown | 460      | 9.69%   |
| LightDM | 145      | 3.06%   |
| SDDM    | 18       | 0.38%   |
| GDM     | 17       | 0.36%   |
| SLiM    | 5        | 0.11%   |
| XDM     | 1        | 0.02%   |
| LXDM    | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 2074     | 43.75%  |
| de_DE   | 457      | 9.64%   |
| fr_FR   | 327      | 6.9%    |
| en_GB   | 231      | 4.87%   |
| pt_BR   | 179      | 3.78%   |
| it_IT   | 154      | 3.25%   |
| en_CA   | 132      | 2.78%   |
| ru_RU   | 109      | 2.3%    |
| es_ES   | 99       | 2.09%   |
| C       | 88       | 1.86%   |
| en_AU   | 85       | 1.79%   |
| en_IN   | 70       | 1.48%   |
| pl_PL   | 65       | 1.37%   |
| Unknown | 52       | 1.1%    |
| nl_NL   | 47       | 0.99%   |
| ja_JP   | 40       | 0.84%   |
| cs_CZ   | 36       | 0.76%   |
| zh_CN   | 33       | 0.7%    |
| es_MX   | 33       | 0.7%    |
| de_AT   | 33       | 0.7%    |
| es_AR   | 30       | 0.63%   |
| sv_SE   | 24       | 0.51%   |
| hu_HU   | 22       | 0.46%   |
| en_ZA   | 21       | 0.44%   |
| fi_FI   | 18       | 0.38%   |
| pt_PT   | 16       | 0.34%   |
| tr_TR   | 15       | 0.32%   |
| en_NZ   | 15       | 0.32%   |
| fr_BE   | 14       | 0.3%    |
| el_GR   | 13       | 0.27%   |
| en_PH   | 12       | 0.25%   |
| de_CH   | 12       | 0.25%   |
| zh_TW   | 11       | 0.23%   |
| ko_KR   | 11       | 0.23%   |
| fr_CA   | 11       | 0.23%   |
| nl_BE   | 10       | 0.21%   |
| es_CO   | 10       | 0.21%   |
| sk_SK   | 9        | 0.19%   |
| en_HK   | 7        | 0.15%   |
| ro_RO   | 6        | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 3306     | 69.15%  |
| EFI  | 1475     | 30.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Ext4          | 3458     | 70.89%  |
| Tmpfs         | 1098     | 22.51%  |
| Overlay       | 152      | 3.12%   |
| Zfs           | 87       | 1.78%   |
| Btrfs         | 42       | 0.86%   |
| Xfs           | 23       | 0.47%   |
| Ext2          | 9        | 0.18%   |
| Unknown       | 4        | 0.08%   |
| Ext3          | 2        | 0.04%   |
| XXXX          | 1        | 0.02%   |
| Jfs           | 1        | 0.02%   |
| Fuse.snapfuse | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 3371     | 69.16%  |
| Unknown | 996      | 20.43%  |
| MBR     | 507      | 10.4%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3948     | 82.3%   |
| Yes       | 849      | 17.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2765     | 57.85%  |
| Yes       | 2015     | 42.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 1157     | 24.49%  |
| Gigabyte Technology                  | 684      | 14.48%  |
| MSI                                  | 527      | 11.16%  |
| Dell                                 | 498      | 10.54%  |
| Hewlett-Packard                      | 379      | 8.02%   |
| ASRock                               | 373      | 7.9%    |
| Lenovo                               | 199      | 4.21%   |
| Intel                                | 138      | 2.92%   |
| Acer                                 | 92       | 1.95%   |
| Fujitsu                              | 75       | 1.59%   |
| Unknown                              | 67       | 1.42%   |
| Supermicro                           | 48       | 1.02%   |
| Pegatron                             | 42       | 0.89%   |
| Foxconn                              | 39       | 0.83%   |
| Medion                               | 36       | 0.76%   |
| Biostar                              | 32       | 0.68%   |
| AZW                                  | 27       | 0.57%   |
| Apple                                | 24       | 0.51%   |
| ECS                                  | 22       | 0.47%   |
| Shuttle                              | 19       | 0.4%    |
| Alienware                            | 18       | 0.38%   |
| Huanan                               | 15       | 0.32%   |
| Gateway                              | 13       | 0.28%   |
| BESSTAR Tech                         | 10       | 0.21%   |
| Positivo                             | 9        | 0.19%   |
| Packard Bell                         | 9        | 0.19%   |
| Shenzhen Meigao Electronic Equipment | 8        | 0.17%   |
| OEM                                  | 6        | 0.13%   |
| Inventec                             | 6        | 0.13%   |
| Google                               | 6        | 0.13%   |
| ASRockRack                           | 6        | 0.13%   |
| AMI                                  | 6        | 0.13%   |
| MACHINIST                            | 5        | 0.11%   |
| eMachines                            | 5        | 0.11%   |
| ZOTAC                                | 4        | 0.08%   |
| Wistron                              | 4        | 0.08%   |
| HC Technology.                       | 4        | 0.08%   |
| Fujitsu Siemens                      | 4        | 0.08%   |
| YANYU                                | 3        | 0.06%   |
| System76                             | 3        | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 113      | 2.39%   |
| Unknown                      | 73       | 1.55%   |
| Dell OptiPlex 7010           | 37       | 0.78%   |
| Dell OptiPlex 9020           | 32       | 0.68%   |
| ASUS PRIME A320M-K           | 28       | 0.59%   |
| ASUS TUF Gaming X570-PLUS    | 23       | 0.49%   |
| MSI MS-7C37                  | 21       | 0.44%   |
| Dell OptiPlex 3020           | 21       | 0.44%   |
| Dell OptiPlex 790            | 20       | 0.42%   |
| MSI MS-7C91                  | 19       | 0.4%    |
| MSI MS-7721                  | 19       | 0.4%    |
| ASUS PRIME Z590-P            | 18       | 0.38%   |
| Dell OptiPlex 3050           | 17       | 0.36%   |
| ASUS ROG STRIX B550-F GAMING | 17       | 0.36%   |
| Intel H61                    | 16       | 0.34%   |
| Dell OptiPlex 7050           | 16       | 0.34%   |
| Dell OptiPlex 990            | 15       | 0.32%   |
| Dell OptiPlex 7040           | 15       | 0.32%   |
| ASUS PRIME X570-PRO          | 15       | 0.32%   |
| ASUS PRIME B550M-A           | 15       | 0.32%   |
| ASRock B450M Pro4            | 15       | 0.32%   |
| MSI MS-7C52                  | 14       | 0.3%    |
| HP Compaq 8200 Elite SFF PC  | 14       | 0.3%    |
| Dell OptiPlex 780            | 14       | 0.3%    |
| MSI MS-7C56                  | 13       | 0.28%   |
| Gigabyte B450M DS3H          | 13       | 0.28%   |
| MSI MS-7817                  | 12       | 0.25%   |
| HP EliteDesk 800 G1 SFF      | 12       | 0.25%   |
| Gigabyte A320M-S2H           | 12       | 0.25%   |
| ASUS M5A78L-M/USB3           | 12       | 0.25%   |
| ASUS H110M-A                 | 12       | 0.25%   |
| Supermicro SYS-6018R-TDW     | 11       | 0.23%   |
| MSI MS-7C02                  | 11       | 0.23%   |
| MSI MS-7B86                  | 11       | 0.23%   |
| HP ProDesk 600 G1 SFF        | 11       | 0.23%   |
| ASUS M5A97 R2.0              | 11       | 0.23%   |
| ASRock A320M-HDV R4.0        | 11       | 0.23%   |
| MSI MS-7B79                  | 10       | 0.21%   |
| MSI MS-7693                  | 10       | 0.21%   |
| HP Compaq Pro 6300 SFF       | 10       | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 318      | 6.73%   |
| ASUS PRIME          | 257      | 5.44%   |
| ASUS ROG            | 159      | 3.37%   |
| Lenovo ThinkCentre  | 116      | 2.46%   |
| HP Compaq           | 115      | 2.43%   |
| ASUS All            | 113      | 2.39%   |
| ASUS TUF            | 112      | 2.37%   |
| Unknown             | 73       | 1.55%   |
| Dell Precision      | 72       | 1.52%   |
| HP EliteDesk        | 60       | 1.27%   |
| Acer Aspire         | 56       | 1.19%   |
| Fujitsu ESPRIMO     | 48       | 1.02%   |
| Dell Inspiron       | 47       | 0.99%   |
| HP ProDesk          | 46       | 0.97%   |
| Gigabyte B450M      | 29       | 0.61%   |
| Lenovo ThinkStation | 28       | 0.59%   |
| ASUS M5A78L-M       | 27       | 0.57%   |
| Gigabyte X570       | 25       | 0.53%   |
| Gigabyte B550M      | 25       | 0.53%   |
| Gigabyte Z390       | 23       | 0.49%   |
| Dell XPS            | 23       | 0.49%   |
| ASUS M5A97          | 23       | 0.49%   |
| ASRock B450M        | 23       | 0.49%   |
| Lenovo IdeaCentre   | 22       | 0.47%   |
| MSI MS-7C37         | 21       | 0.44%   |
| Fujitsu CELSIUS     | 20       | 0.42%   |
| ASUS Pro            | 20       | 0.42%   |
| MSI MS-7C91         | 19       | 0.4%    |
| MSI MS-7721         | 19       | 0.4%    |
| Dell Vostro         | 18       | 0.38%   |
| ASUS P8H61-M        | 18       | 0.38%   |
| Acer Veriton        | 18       | 0.38%   |
| Gigabyte B550       | 17       | 0.36%   |
| Gigabyte B450       | 17       | 0.36%   |
| Intel H61           | 16       | 0.34%   |
| HP Pavilion         | 16       | 0.34%   |
| ASRock X570         | 16       | 0.34%   |
| ASUS CROSSHAIR      | 15       | 0.32%   |
| MSI MS-7C52         | 14       | 0.3%    |
| Gigabyte A320M-S2H  | 14       | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 423      | 8.95%   |
| 2013    | 416      | 8.81%   |
| 2012    | 407      | 8.62%   |
| 2020    | 366      | 7.75%   |
| 2021    | 342      | 7.24%   |
| 2019    | 330      | 6.99%   |
| 2014    | 324      | 6.86%   |
| 2011    | 320      | 6.77%   |
| 2017    | 308      | 6.52%   |
| 2015    | 265      | 5.61%   |
| 2022    | 261      | 5.52%   |
| 2010    | 225      | 4.76%   |
| 2009    | 193      | 4.09%   |
| 2016    | 183      | 3.87%   |
| 2008    | 134      | 2.84%   |
| 2023    | 103      | 2.18%   |
| 2007    | 87       | 1.84%   |
| 2006    | 24       | 0.51%   |
| 2005    | 7        | 0.15%   |
| Unknown | 5        | 0.11%   |
| 2004    | 1        | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 4724     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 4559     | 96.32%  |
| Enabled  | 174      | 3.68%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4715     | 99.81%  |
| Yes  | 9        | 0.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1245     | 26.04%  |
| 32.01-64.0      | 801      | 16.75%  |
| 4.01-8.0        | 792      | 16.57%  |
| 8.01-16.0       | 778      | 16.27%  |
| 3.01-4.0        | 529      | 11.06%  |
| 64.01-256.0     | 370      | 7.74%   |
| 24.01-32.0      | 157      | 3.28%   |
| 1.01-2.0        | 52       | 1.09%   |
| More than 256.0 | 29       | 0.61%   |
| 2.01-3.0        | 25       | 0.52%   |
| 0.51-1.0        | 2        | 0.04%   |
| 0.01-0.5        | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 1554     | 30.47%  |
| 2.01-3.0    | 1520     | 29.8%   |
| 4.01-8.0    | 802      | 15.73%  |
| 3.01-4.0    | 756      | 14.82%  |
| 8.01-16.0   | 266      | 5.22%   |
| 0.51-1.0    | 97       | 1.9%    |
| 16.01-24.0  | 45       | 0.88%   |
| 0.01-0.5    | 22       | 0.43%   |
| 24.01-32.0  | 21       | 0.41%   |
| 32.01-64.0  | 13       | 0.25%   |
| 64.01-256.0 | 4        | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1984     | 40.72%  |
| 2      | 1417     | 29.08%  |
| 3      | 704      | 14.45%  |
| 4      | 347      | 7.12%   |
| 5      | 170      | 3.49%   |
| 6      | 82       | 1.68%   |
| 0      | 57       | 1.17%   |
| 7      | 47       | 0.96%   |
| 8      | 18       | 0.37%   |
| 9      | 17       | 0.35%   |
| 10     | 9        | 0.18%   |
| 11     | 8        | 0.16%   |
| 13     | 3        | 0.06%   |
| 12     | 3        | 0.06%   |
| 25     | 2        | 0.04%   |
| 38     | 1        | 0.02%   |
| 20     | 1        | 0.02%   |
| 17     | 1        | 0.02%   |
| 14     | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2703     | 56.79%  |
| Yes       | 2057     | 43.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4687     | 99.2%   |
| No        | 38       | 0.8%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2603     | 54.66%  |
| Yes       | 2159     | 45.34%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3192     | 66.95%  |
| Yes       | 1576     | 33.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 1044     | 22.04%  |
| Germany      | 536      | 11.32%  |
| France       | 347      | 7.33%   |
| Brazil       | 253      | 5.34%   |
| UK           | 224      | 4.73%   |
| Russia       | 202      | 4.27%   |
| Italy        | 185      | 3.91%   |
| Canada       | 174      | 3.67%   |
| Switzerland  | 146      | 3.08%   |
| Spain        | 120      | 2.53%   |
| Australia    | 95       | 2.01%   |
| Netherlands  | 88       | 1.86%   |
| Poland       | 83       | 1.75%   |
| India        | 78       | 1.65%   |
| Austria      | 61       | 1.29%   |
| Mexico       | 58       | 1.22%   |
| Sweden       | 53       | 1.12%   |
| Japan        | 52       | 1.1%    |
| Argentina    | 49       | 1.03%   |
| Belgium      | 48       | 1.01%   |
| Czechia      | 46       | 0.97%   |
| Finland      | 43       | 0.91%   |
| Turkey       | 38       | 0.8%    |
| Hungary      | 36       | 0.76%   |
| China        | 35       | 0.74%   |
| Greece       | 33       | 0.7%    |
| Romania      | 29       | 0.61%   |
| Slovakia     | 26       | 0.55%   |
| South Africa | 24       | 0.51%   |
| Bulgaria     | 24       | 0.51%   |
| South Korea  | 22       | 0.46%   |
| Portugal     | 22       | 0.46%   |
| Norway       | 18       | 0.38%   |
| Hong Kong    | 18       | 0.38%   |
| Thailand     | 17       | 0.36%   |
| Serbia       | 17       | 0.36%   |
| New Zealand  | 17       | 0.36%   |
| Taiwan       | 16       | 0.34%   |
| Colombia     | 16       | 0.34%   |
| Denmark      | 15       | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Zurich         | 83       | 1.68%   |
| Moscow         | 62       | 1.26%   |
| Berlin         | 47       | 0.95%   |
| Paris          | 37       | 0.75%   |
| Vienna         | 36       | 0.73%   |
| Sydney         | 34       | 0.69%   |
| Sao Paulo      | 27       | 0.55%   |
| Madrid         | 27       | 0.55%   |
| Milan          | 26       | 0.53%   |
| Hamburg        | 25       | 0.51%   |
| St Petersburg  | 24       | 0.49%   |
| Cheboksary     | 24       | 0.49%   |
| Rio de Janeiro | 23       | 0.47%   |
| New York       | 23       | 0.47%   |
| Helsinki       | 21       | 0.43%   |
| Munich         | 20       | 0.41%   |
| Rome           | 19       | 0.38%   |
| Prague         | 19       | 0.38%   |
| Athens         | 19       | 0.38%   |
| Warsaw         | 18       | 0.36%   |
| Toronto        | 18       | 0.36%   |
| Seattle        | 18       | 0.36%   |
| Lucerne        | 18       | 0.36%   |
| Istanbul       | 18       | 0.36%   |
| San Jose       | 17       | 0.34%   |
| Los Angeles    | 17       | 0.34%   |
| Roubaix        | 16       | 0.32%   |
| Melbourne      | 16       | 0.32%   |
| London         | 16       | 0.32%   |
| Budapest       | 15       | 0.3%    |
| Stockholm      | 14       | 0.28%   |
| Singapore      | 14       | 0.28%   |
| Manchester     | 14       | 0.28%   |
| Barcelona      | 14       | 0.28%   |
| Vancouver      | 13       | 0.26%   |
| Dallas         | 13       | 0.26%   |
| Brisbane       | 13       | 0.26%   |
| Amsterdam      | 13       | 0.26%   |
| Sofia          | 12       | 0.24%   |
| Miami          | 12       | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 1497     | 2423   | 18.07%  |
| WDC                         | 1448     | 2399   | 17.48%  |
| Samsung Electronics         | 1253     | 1972   | 15.12%  |
| Kingston                    | 502      | 631    | 6.06%   |
| Sandisk                     | 408      | 575    | 4.92%   |
| Toshiba                     | 406      | 533    | 4.9%    |
| Crucial                     | 367      | 552    | 4.43%   |
| Hitachi                     | 247      | 323    | 2.98%   |
| A-DATA Technology           | 126      | 157    | 1.52%   |
| Intel                       | 124      | 206    | 1.5%    |
| Unknown                     | 105      | 172    | 1.27%   |
| China                       | 105      | 124    | 1.27%   |
| HGST                        | 90       | 152    | 1.09%   |
| Phison Electronics          | 85       | 112    | 1.03%   |
| SK hynix                    | 82       | 105    | 0.99%   |
| Micron/Crucial Technology   | 79       | 105    | 0.95%   |
| Intenso                     | 64       | 84     | 0.77%   |
| PNY                         | 63       | 75     | 0.76%   |
| Silicon Motion              | 62       | 81     | 0.75%   |
| Kingston Technology Company | 61       | 75     | 0.74%   |
| SPCC                        | 52       | 88     | 0.63%   |
| Micron Technology           | 45       | 59     | 0.54%   |
| Phison                      | 43       | 58     | 0.52%   |
| OCZ                         | 39       | 57     | 0.47%   |
| Patriot                     | 34       | 44     | 0.41%   |
| Corsair                     | 33       | 37     | 0.4%    |
| Maxtor                      | 32       | 44     | 0.39%   |
| Lexar                       | 32       | 36     | 0.39%   |
| Gigabyte Technology         | 31       | 40     | 0.37%   |
| Unknown                     | 30       | 33     | 0.36%   |
| Team                        | 29       | 42     | 0.35%   |
| Transcend                   | 28       | 28     | 0.34%   |
| ADATA Technology            | 26       | 34     | 0.31%   |
| Hewlett-Packard             | 25       | 58     | 0.3%    |
| JMicron Technology          | 20       | 21     | 0.24%   |
| ASMT                        | 20       | 33     | 0.24%   |
| KingSpec                    | 19       | 21     | 0.23%   |
| Realtek Semiconductor       | 18       | 21     | 0.22%   |
| Fujitsu                     | 18       | 25     | 0.22%   |
| MAXIO Technology (Hangzhou) | 17       | 21     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 125      | 1.31%   |
| Seagate ST1000DM010-2EP102 1TB                        | 114      | 1.19%   |
| Seagate ST500DM002-1BD142 500GB                       | 113      | 1.18%   |
| Kingston SA400S37240G 240GB SSD                       | 109      | 1.14%   |
| Seagate ST2000DM008-2FR102 2TB                        | 104      | 1.09%   |
| Kingston SA400S37480G 480GB SSD                       | 83       | 0.87%   |
| Samsung SSD 850 EVO 250GB                             | 78       | 0.81%   |
| Samsung SSD 850 EVO 500GB                             | 71       | 0.74%   |
| Samsung SSD 860 EVO 500GB                             | 69       | 0.72%   |
| Toshiba DT01ACA100 1TB                                | 68       | 0.71%   |
| Samsung SSD 980 PRO 1TB                               | 62       | 0.65%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 61       | 0.64%   |
| Seagate ST1000DM003-1CH162 1TB                        | 61       | 0.64%   |
| Seagate ST4000DM004-2CV104 4TB                        | 60       | 0.63%   |
| Crucial CT500MX500SSD1 500GB                          | 54       | 0.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB    | 52       | 0.54%   |
| Crucial CT1000MX500SSD1 1TB                           | 51       | 0.53%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                   | 50       | 0.52%   |
| Toshiba DT01ACA050 500GB                              | 49       | 0.51%   |
| Kingston SA400S37120G 120GB SSD                       | 49       | 0.51%   |
| Seagate ST1000DM003-1ER162 1TB                        | 46       | 0.48%   |
| Crucial CT240BX500SSD1 240GB                          | 44       | 0.46%   |
| Unknown SD/MMC/MS PRO 512GB                           | 41       | 0.43%   |
| Seagate ST1000DM003-1SB102 1TB                        | 41       | 0.43%   |
| SanDisk NVMe SSD Drive 1TB                            | 41       | 0.43%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB | 38       | 0.4%    |
| Samsung SSD 980 1TB                                   | 38       | 0.4%    |
| Toshiba HDWD110 1TB                                   | 37       | 0.39%   |
| Seagate ST2000DM001-1ER164 2TB                        | 35       | 0.37%   |
| Samsung SSD 870 EVO 500GB                             | 35       | 0.37%   |
| Seagate ST2000DM006-2DM164 2TB                        | 33       | 0.34%   |
| Seagate ST2000DM001-1CH164 2TB                        | 33       | 0.34%   |
| Toshiba DT01ACA200 2TB                                | 32       | 0.33%   |
| Crucial CT480BX500SSD1 480GB                          | 32       | 0.33%   |
| Samsung SSD 860 EVO 1TB                               | 31       | 0.32%   |
| Samsung NVMe SSD Drive 1TB                            | 31       | 0.32%   |
| Seagate ST3500418AS 500GB                             | 30       | 0.31%   |
| Seagate ST31000528AS 1TB                              | 30       | 0.31%   |
| Samsung SSD 870 EVO 1TB                               | 30       | 0.31%   |
| Samsung SSD 860 EVO 250GB                             | 30       | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1466     | 2361   | 38.47%  |
| WDC                 | 1284     | 2109   | 33.69%  |
| Toshiba             | 348      | 453    | 9.13%   |
| Hitachi             | 245      | 321    | 6.43%   |
| Samsung Electronics | 190      | 275    | 4.99%   |
| HGST                | 90       | 148    | 2.36%   |
| Unknown             | 47       | 62     | 1.23%   |
| Maxtor              | 30       | 39     | 0.79%   |
| Fujitsu             | 18       | 25     | 0.47%   |
| Intenso             | 17       | 19     | 0.45%   |
| SABRENT             | 15       | 20     | 0.39%   |
| ASMT                | 9        | 11     | 0.24%   |
| Apple               | 8        | 9      | 0.21%   |
| Hewlett-Packard     | 6        | 16     | 0.16%   |
| WD MediaMax         | 5        | 6      | 0.13%   |
| External            | 4        | 4      | 0.1%    |
| ExcelStor           | 4        | 4      | 0.1%    |
| USB3.0              | 3        | 4      | 0.08%   |
| HPE                 | 3        | 5      | 0.08%   |
| USB                 | 2        | 2      | 0.05%   |
| TDAS                | 2        | 11     | 0.05%   |
| LaCie               | 2        | 3      | 0.05%   |
| Inateck             | 2        | 2      | 0.05%   |
| ASMedia             | 2        | 2      | 0.05%   |
| StoreJet            | 1        | 1      | 0.03%   |
| SSK                 | 1        | 1      | 0.03%   |
| RSH-339             | 1        | 1      | 0.03%   |
| QUANTUM             | 1        | 1      | 0.03%   |
| Min Yi U            | 1        | 2      | 0.03%   |
| MARVELL             | 1        | 1      | 0.03%   |
| HGST HTS            | 1        | 1      | 0.03%   |
| DAS                 | 1        | 3      | 0.03%   |
| Unknown             | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 638      | 869    | 22.21%  |
| Kingston            | 421      | 530    | 14.65%  |
| Crucial             | 326      | 492    | 11.35%  |
| SanDisk             | 210      | 295    | 7.31%   |
| WDC                 | 169      | 213    | 5.88%   |
| A-DATA Technology   | 108      | 138    | 3.76%   |
| China               | 104      | 122    | 3.62%   |
| Intel               | 76       | 145    | 2.65%   |
| Toshiba             | 58       | 65     | 2.02%   |
| PNY                 | 58       | 70     | 2.02%   |
| SPCC                | 48       | 83     | 1.67%   |
| OCZ                 | 37       | 43     | 1.29%   |
| Intenso             | 35       | 52     | 1.22%   |
| Patriot             | 33       | 43     | 1.15%   |
| Micron Technology   | 30       | 43     | 1.04%   |
| Team                | 27       | 40     | 0.94%   |
| SK hynix            | 27       | 37     | 0.94%   |
| Transcend           | 26       | 26     | 0.9%    |
| Lexar               | 22       | 25     | 0.77%   |
| Gigabyte Technology | 22       | 31     | 0.77%   |
| Corsair             | 20       | 23     | 0.7%    |
| KingSpec            | 19       | 21     | 0.66%   |
| JMicron Technology  | 17       | 18     | 0.59%   |
| GOODRAM             | 16       | 25     | 0.56%   |
| Hewlett-Packard     | 15       | 15     | 0.52%   |
| Unknown             | 15       | 16     | 0.52%   |
| LITEON              | 14       | 18     | 0.49%   |
| Apacer              | 14       | 14     | 0.49%   |
| ASMT                | 12       | 22     | 0.42%   |
| Fanxiang            | 11       | 15     | 0.38%   |
| Emtec               | 9        | 9      | 0.31%   |
| Dogfish             | 9        | 13     | 0.31%   |
| LITEONIT            | 8        | 9      | 0.28%   |
| FORESEE             | 8        | 8      | 0.28%   |
| Seagate             | 7        | 9      | 0.24%   |
| Netac               | 6        | 8      | 0.21%   |
| Mushkin             | 6        | 6      | 0.21%   |
| Leven               | 6        | 14     | 0.21%   |
| KIOXIA-EXCERIA      | 6        | 14     | 0.21%   |
| Plextor             | 5        | 5      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2972     | 5923   | 42.22%  |
| SSD     | 2426     | 3844   | 34.47%  |
| NVMe    | 1443     | 2230   | 20.5%   |
| Unknown | 172      | 274    | 2.44%   |
| MMC     | 26       | 36     | 0.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 4067     | 9380   | 68.68%  |
| NVMe | 1442     | 2225   | 24.35%  |
| SAS  | 387      | 666    | 6.53%   |
| MMC  | 26       | 36     | 0.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 2767     | 4567   | 46.72%  |
| 0.51-1.0   | 1723     | 2735   | 29.09%  |
| 1.01-2.0   | 753      | 1179   | 12.71%  |
| 3.01-4.0   | 290      | 473    | 4.9%    |
| 4.01-10.0  | 185      | 435    | 3.12%   |
| 2.01-3.0   | 146      | 219    | 2.46%   |
| 10.01-20.0 | 58       | 158    | 0.98%   |
| 0          | 1        | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1175     | 23.83%  |
| 251-500        | 932      | 18.9%   |
| 501-1000       | 899      | 18.24%  |
| 1001-2000      | 566      | 11.48%  |
| More than 3000 | 477      | 9.68%   |
| 2001-3000      | 244      | 4.95%   |
| 51-100         | 234      | 4.75%   |
| 1-20           | 191      | 3.87%   |
| Unknown        | 119      | 2.41%   |
| 21-50          | 93       | 1.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1546     | 30.51%  |
| 21-50          | 922      | 18.2%   |
| 101-250        | 616      | 12.16%  |
| 51-100         | 612      | 12.08%  |
| 251-500        | 407      | 8.03%   |
| 501-1000       | 341      | 6.73%   |
| 1001-2000      | 215      | 4.24%   |
| More than 3000 | 198      | 3.91%   |
| Unknown        | 119      | 2.35%   |
| 2001-3000      | 90       | 1.78%   |
| 0              | 1        | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| WDC WD40EFRX-68WT0N0 4TB              | 8        | 10     | 1.91%   |
| Seagate ST500DM002-1BD142 500GB       | 8        | 8      | 1.91%   |
| Seagate ST1000DM010-2EP102 1TB        | 5        | 5      | 1.2%    |
| WDC WD10EARS-00Y5B1 1TB               | 4        | 5      | 0.96%   |
| Seagate ST3500418AS 500GB             | 4        | 6      | 0.96%   |
| Seagate ST31000528AS 1TB              | 4        | 4      | 0.96%   |
| Seagate ST2000DM008-2FR102 2TB        | 4        | 5      | 0.96%   |
| Seagate ST2000DM001-1CH164 2TB        | 4        | 4      | 0.96%   |
| Seagate ST1000DM003-1CH162 1TB        | 4        | 5      | 0.96%   |
| SanDisk SSD PLUS 480GB                | 4        | 4      | 0.96%   |
| Kingston SA400S37240G 240GB SSD       | 4        | 4      | 0.96%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 3        | 3      | 0.72%   |
| WDC WD5000AAKX-08ERMA0 500GB          | 3        | 3      | 0.72%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 3        | 4      | 0.72%   |
| WDC WD10EZEX-21WN4A0 1TB              | 3        | 3      | 0.72%   |
| WDC WD10EZEX-21M2NA0 1TB              | 3        | 3      | 0.72%   |
| Toshiba DT01ACA050 500GB              | 3        | 3      | 0.72%   |
| Seagate ST500LM021-1KJ152 500GB       | 3        | 5      | 0.72%   |
| Seagate ST3250310AS 250GB             | 3        | 3      | 0.72%   |
| Samsung Electronics SSD 870 EVO 500GB | 3        | 3      | 0.72%   |
| Samsung Electronics SSD 870 EVO 1TB   | 3        | 3      | 0.72%   |
| Kingston SV300S37A120G 120GB SSD      | 3        | 3      | 0.72%   |
| Intel SSDSC2CW120A3 120GB             | 3        | 3      | 0.72%   |
| Intel SSDSC2BB800G7 800GB             | 3        | 9      | 0.72%   |
| A-DATA Technology SX8100NP 512GB      | 3        | 3      | 0.72%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 2        | 2      | 0.48%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 2        | 2      | 0.48%   |
| WDC WD5000AADS-00S9B0 500GB           | 2        | 2      | 0.48%   |
| WDC WD40EZRX-00SPEB0 4TB              | 2        | 2      | 0.48%   |
| WDC WD4003FZEX-00Z4SA0 4TB            | 2        | 4      | 0.48%   |
| WDC WD30EZRX-00MMMB0 3TB              | 2        | 6      | 0.48%   |
| WDC WD2002FAEX-007BA0 2TB             | 2        | 2      | 0.48%   |
| WDC WD10JPVX-22JC3T0 1TB              | 2        | 2      | 0.48%   |
| WDC WD10EZRZ-00HTKB0 1TB              | 2        | 4      | 0.48%   |
| WDC WD10EZEX-60ZF5A0 1TB              | 2        | 2      | 0.48%   |
| WDC WD10EZEX-22MFCA0 1TB              | 2        | 2      | 0.48%   |
| WDC WD10EADS-65L5B1 1TB               | 2        | 2      | 0.48%   |
| WDC WD10EADS-00M2B0 1TB               | 2        | 2      | 0.48%   |
| Toshiba DT01ACA100 1TB                | 2        | 2      | 0.48%   |
| Seagate ST500LM000-SSHD-8GB           | 2        | 3      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 120      | 150    | 29.41%  |
| Seagate             | 107      | 142    | 26.23%  |
| Samsung Electronics | 48       | 53     | 11.76%  |
| Hitachi             | 23       | 27     | 5.64%   |
| Intel               | 17       | 31     | 4.17%   |
| Toshiba             | 15       | 15     | 3.68%   |
| Kingston            | 13       | 13     | 3.19%   |
| Crucial             | 9        | 11     | 2.21%   |
| SanDisk             | 7        | 9      | 1.72%   |
| A-DATA Technology   | 7        | 7      | 1.72%   |
| Maxtor              | 5        | 6      | 1.23%   |
| HGST                | 4        | 5      | 0.98%   |
| China               | 4        | 4      | 0.98%   |
| SK hynix            | 3        | 3      | 0.74%   |
| Micron Technology   | 3        | 9      | 0.74%   |
| LITEONIT            | 3        | 3      | 0.74%   |
| LDLC                | 3        | 4      | 0.74%   |
| Intenso             | 2        | 2      | 0.49%   |
| YS                  | 1        | 1      | 0.25%   |
| XPG                 | 1        | 1      | 0.25%   |
| WD MediaMax         | 1        | 1      | 0.25%   |
| Unknown             | 1        | 1      | 0.25%   |
| Silicon Motion      | 1        | 1      | 0.25%   |
| PNY                 | 1        | 1      | 0.25%   |
| Patriot             | 1        | 1      | 0.25%   |
| OCZ                 | 1        | 1      | 0.25%   |
| Netac               | 1        | 2      | 0.25%   |
| Mushkin             | 1        | 1      | 0.25%   |
| KingSpec            | 1        | 1      | 0.25%   |
| Gigabyte Technology | 1        | 1      | 0.25%   |
| Corsair             | 1        | 1      | 0.25%   |
| ASMedia             | 1        | 1      | 0.25%   |
| Unknown             | 1        | 1      | 0.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 113      | 143    | 39.1%   |
| Seagate             | 107      | 142    | 37.02%  |
| Hitachi             | 23       | 27     | 7.96%   |
| Samsung Electronics | 22       | 24     | 7.61%   |
| Toshiba             | 13       | 13     | 4.5%    |
| Maxtor              | 5        | 6      | 1.73%   |
| HGST                | 4        | 5      | 1.38%   |
| WD MediaMax         | 1        | 1      | 0.35%   |
| Unknown             | 1        | 1      | 0.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 270      | 362    | 69.41%  |
| SSD  | 97       | 124    | 24.94%  |
| NVMe | 22       | 24     | 5.66%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Samsung Electronics SSD 980 500GB     | 2        | 2      | 22.22%  |
| WDC WD800BB-00FJA0 80GB               | 1        | 1      | 11.11%  |
| WDC WD3200AAJS-22VWA0 320GB           | 1        | 1      | 11.11%  |
| Seagate ST3500630AS 500GB             | 1        | 1      | 11.11%  |
| Samsung Electronics SSD 960 EVO 250GB | 1        | 1      | 11.11%  |
| Intel SSDSC2BB480G7 480GB             | 1        | 4      | 11.11%  |
| Intel SSDPEKKW256G7 256GB             | 1        | 1      | 11.11%  |
| Hewlett-Packard EF0450FARMV 450GB     | 1        | 4      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 3        | 3      | 33.33%  |
| WDC                 | 2        | 2      | 22.22%  |
| Intel               | 2        | 5      | 22.22%  |
| Seagate             | 1        | 1      | 11.11%  |
| Hewlett-Packard     | 1        | 4      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 3202     | 8417   | 62.3%   |
| Works    | 1565     | 3365   | 30.45%  |
| Malfunc  | 364      | 510    | 7.08%   |
| Failed   | 9        | 15     | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 3183     | 46.03%  |
| AMD                            | 1394     | 20.16%  |
| Samsung Electronics            | 554      | 8.01%   |
| SanDisk                        | 268      | 3.88%   |
| ASMedia Technology             | 255      | 3.69%   |
| Kingston Technology Company    | 148      | 2.14%   |
| Phison Electronics             | 146      | 2.11%   |
| Marvell Technology Group       | 141      | 2.04%   |
| Micron/Crucial Technology      | 123      | 1.78%   |
| JMicron Technology             | 119      | 1.72%   |
| Nvidia                         | 98       | 1.42%   |
| Silicon Motion                 | 77       | 1.11%   |
| SK hynix                       | 57       | 0.82%   |
| ADATA Technology               | 46       | 0.67%   |
| Broadcom / LSI                 | 30       | 0.43%   |
| Realtek Semiconductor          | 29       | 0.42%   |
| MAXIO Technology (Hangzhou)    | 29       | 0.42%   |
| LSI Logic / Symbios Logic      | 28       | 0.4%    |
| VIA Technologies               | 22       | 0.32%   |
| KIOXIA                         | 21       | 0.3%    |
| Silicon Image                  | 20       | 0.29%   |
| Adaptec                        | 19       | 0.27%   |
| Seagate Technology             | 17       | 0.25%   |
| Micron Technology              | 16       | 0.23%   |
| Shenzhen Longsys Electronics   | 13       | 0.19%   |
| Toshiba America Info Systems   | 12       | 0.17%   |
| INNOGRIT                       | 6        | 0.09%   |
| Hewlett-Packard                | 4        | 0.06%   |
| Apple                          | 4        | 0.06%   |
| Union Memory (Shenzhen)        | 3        | 0.04%   |
| Solidigm                       | 3        | 0.04%   |
| Lite-On Technology             | 3        | 0.04%   |
| Transcend                      | 2        | 0.03%   |
| Solid State Storage Technology | 2        | 0.03%   |
| OCZ Technology Group           | 2        | 0.03%   |
| Netac Technology               | 2        | 0.03%   |
| Integrated Technology Express  | 2        | 0.03%   |
| Chelsio Communications         | 2        | 0.03%   |
| Biwin Storage Technology       | 2        | 0.03%   |
| 3ware                          | 2        | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 768      | 9.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 403      | 4.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 258      | 3.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 253      | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 249      | 2.98%   |
| Intel SATA Controller [RAID mode]                                                       | 245      | 2.93%   |
| AMD 400 Series Chipset SATA Controller                                                  | 236      | 2.83%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 232      | 2.78%   |
| AMD 500 Series Chipset SATA Controller                                                  | 226      | 2.71%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 210      | 2.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 206      | 2.47%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 177      | 2.12%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 167      | 2%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 159      | 1.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 147      | 1.76%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 130      | 1.56%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 128      | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 118      | 1.41%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 105      | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 96       | 1.15%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 95       | 1.14%   |
| AMD FCH SATA Controller D                                                               | 95       | 1.14%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 84       | 1.01%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 82       | 0.98%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 81       | 0.97%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 79       | 0.95%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 75       | 0.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 75       | 0.9%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 68       | 0.81%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 66       | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 59       | 0.71%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 57       | 0.68%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 55       | 0.66%   |
| AMD 300 Series Chipset SATA Controller                                                  | 52       | 0.62%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 51       | 0.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 50       | 0.6%    |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 49       | 0.59%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 49       | 0.59%   |
| Nvidia MCP61 SATA Controller                                                            | 48       | 0.57%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 44       | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3895     | 57.84%  |
| NVMe | 1445     | 21.46%  |
| IDE  | 862      | 12.8%   |
| RAID | 450      | 6.68%   |
| SAS  | 59       | 0.88%   |
| SCSI | 23       | 0.34%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 3242     | 68.63%  |
| AMD    | 1482     | 31.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 72       | 1.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 68       | 1.43%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 58       | 1.22%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 56       | 1.18%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 56       | 1.18%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 55       | 1.16%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 54       | 1.14%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 51       | 1.08%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 47       | 0.99%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 47       | 0.99%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 46       | 0.97%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 46       | 0.97%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 45       | 0.95%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 44       | 0.93%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 43       | 0.91%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 42       | 0.89%   |
| AMD FX-8350 Eight-Core Processor            | 41       | 0.86%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 39       | 0.82%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 38       | 0.8%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 38       | 0.8%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 36       | 0.76%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 35       | 0.74%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 33       | 0.7%    |
| Intel Core i7-9700K CPU @ 3.60GHz           | 31       | 0.65%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 31       | 0.65%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 31       | 0.65%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 29       | 0.61%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 29       | 0.61%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 27       | 0.57%   |
| AMD FX-6300 Six-Core Processor              | 27       | 0.57%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 26       | 0.55%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 26       | 0.55%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 26       | 0.55%   |
| Intel Core i7-9700 CPU @ 3.00GHz            | 25       | 0.53%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 25       | 0.53%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 25       | 0.53%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 24       | 0.51%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 24       | 0.51%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 23       | 0.49%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 23       | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 907      | 19.17%  |
| Intel Core i7           | 703      | 14.86%  |
| Intel Core i3           | 379      | 8.01%   |
| AMD Ryzen 5             | 377      | 7.97%   |
| Intel Xeon              | 334      | 7.06%   |
| Other                   | 312      | 6.59%   |
| AMD Ryzen 7             | 239      | 5.05%   |
| AMD Ryzen 9             | 176      | 3.72%   |
| AMD FX                  | 152      | 3.21%   |
| Intel Celeron           | 144      | 3.04%   |
| Intel Core 2 Duo        | 105      | 2.22%   |
| Intel Pentium           | 99       | 2.09%   |
| Intel Core 2 Quad       | 97       | 2.05%   |
| AMD Ryzen 3             | 71       | 1.5%    |
| AMD A10                 | 54       | 1.14%   |
| Intel Core i9           | 47       | 0.99%   |
| Intel Pentium Dual-Core | 44       | 0.93%   |
| AMD Phenom II X4        | 44       | 0.93%   |
| AMD Ryzen Threadripper  | 37       | 0.78%   |
| AMD Athlon II X2        | 36       | 0.76%   |
| AMD A8                  | 35       | 0.74%   |
| AMD A6                  | 30       | 0.63%   |
| AMD A4                  | 22       | 0.47%   |
| Intel Atom              | 21       | 0.44%   |
| AMD Athlon 64 X2        | 21       | 0.44%   |
| Intel Core 2            | 20       | 0.42%   |
| AMD Athlon II X4        | 20       | 0.42%   |
| AMD Phenom II X6        | 19       | 0.4%    |
| AMD Athlon              | 18       | 0.38%   |
| AMD Phenom II X2        | 14       | 0.3%    |
| AMD Ryzen 5 PRO         | 13       | 0.27%   |
| Intel Pentium Dual      | 12       | 0.25%   |
| Intel Pentium Gold      | 11       | 0.23%   |
| AMD Athlon II X3        | 11       | 0.23%   |
| Intel Pentium 4         | 8        | 0.17%   |
| AMD Sempron             | 8        | 0.17%   |
| AMD Athlon X4           | 8        | 0.17%   |
| AMD GX                  | 7        | 0.15%   |
| AMD Ryzen 3 PRO         | 6        | 0.13%   |
| AMD Phenom              | 6        | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 1908     | 40.3%   |
| 2      | 1000     | 21.12%  |
| 6      | 717      | 15.14%  |
| 8      | 494      | 10.43%  |
| 12     | 194      | 4.1%    |
| 16     | 146      | 3.08%   |
| 1      | 64       | 1.35%   |
| 3      | 62       | 1.31%   |
| 10     | 48       | 1.01%   |
| 24     | 41       | 0.87%   |
| 28     | 13       | 0.27%   |
| 14     | 13       | 0.27%   |
| 32     | 12       | 0.25%   |
| 20     | 8        | 0.17%   |
| 18     | 5        | 0.11%   |
| 64     | 3        | 0.06%   |
| 36     | 3        | 0.06%   |
| 128    | 1        | 0.02%   |
| 44     | 1        | 0.02%   |
| 40     | 1        | 0.02%   |
| 22     | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 4600     | 97.38%  |
| 2      | 124      | 2.62%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 2795     | 59.09%  |
| 1      | 1933     | 40.87%  |
| 6      | 1        | 0.02%   |
| 4      | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 4722     | 99.94%  |
| Unknown        | 3        | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3087     | 63.74%  |
| 0x306c3    | 174      | 3.59%   |
| 0x306a9    | 110      | 2.27%   |
| 0x506e3    | 95       | 1.96%   |
| 0x206a7    | 90       | 1.86%   |
| 0x08701021 | 72       | 1.49%   |
| 0x906ea    | 64       | 1.32%   |
| 0x906e9    | 59       | 1.22%   |
| 0x306f2    | 45       | 0.93%   |
| 0x0a20120a | 45       | 0.93%   |
| 0x90672    | 43       | 0.89%   |
| 0x06000852 | 43       | 0.89%   |
| 0x0800820d | 42       | 0.87%   |
| 0x0a201016 | 38       | 0.78%   |
| 0xa0671    | 36       | 0.74%   |
| 0xa0653    | 35       | 0.72%   |
| 0x1067a    | 33       | 0.68%   |
| 0x0a601203 | 32       | 0.66%   |
| 0x08108109 | 31       | 0.64%   |
| 0x010000c8 | 30       | 0.62%   |
| 0xa0655    | 29       | 0.6%    |
| 0x906ed    | 29       | 0.6%    |
| 0xb0671    | 24       | 0.5%    |
| 0x08701013 | 24       | 0.5%    |
| 0x406f1    | 22       | 0.45%   |
| 0x0a50000d | 20       | 0.41%   |
| 0x0a50000c | 17       | 0.35%   |
| 0x06003106 | 16       | 0.33%   |
| 0x106e5    | 15       | 0.31%   |
| 0x06001119 | 15       | 0.31%   |
| 0x906ec    | 14       | 0.29%   |
| 0x906eb    | 13       | 0.27%   |
| 0x0a201205 | 13       | 0.27%   |
| 0x0a201009 | 13       | 0.27%   |
| 0x08001138 | 13       | 0.27%   |
| 0x20655    | 11       | 0.23%   |
| 0x106a5    | 11       | 0.23%   |
| 0x0810100b | 11       | 0.23%   |
| 0x010000db | 11       | 0.23%   |
| 0x90675    | 10       | 0.21%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 632      | 13.36%  |
| KabyLake         | 440      | 9.3%    |
| IvyBridge        | 369      | 7.8%    |
| SandyBridge      | 333      | 7.04%   |
| Zen 3            | 319      | 6.74%   |
| Skylake          | 299      | 6.32%   |
| Zen 2            | 257      | 5.43%   |
| Unknown          | 231      | 4.88%   |
| Penryn           | 216      | 4.57%   |
| Piledriver       | 189      | 3.99%   |
| Zen+             | 168      | 3.55%   |
| K10              | 167      | 3.53%   |
| CometLake        | 145      | 3.06%   |
| Westmere         | 127      | 2.68%   |
| Zen              | 118      | 2.49%   |
| Core             | 103      | 2.18%   |
| Alderlake Hybrid | 98       | 2.07%   |
| Nehalem          | 82       | 1.73%   |
| Broadwell        | 54       | 1.14%   |
| Icelake          | 50       | 1.06%   |
| Steamroller      | 46       | 0.97%   |
| Silvermont       | 46       | 0.97%   |
| K8 Hammer        | 33       | 0.7%    |
| Excavator        | 32       | 0.68%   |
| Goldmont plus    | 30       | 0.63%   |
| Bulldozer        | 30       | 0.63%   |
| Goldmont         | 18       | 0.38%   |
| Jaguar           | 15       | 0.32%   |
| TigerLake        | 14       | 0.3%    |
| NetBurst         | 13       | 0.27%   |
| K10 Llano        | 13       | 0.27%   |
| Tremont          | 11       | 0.23%   |
| Bonnell          | 11       | 0.23%   |
| Bobcat           | 10       | 0.21%   |
| Puma             | 8        | 0.17%   |
| Gracemont        | 4        | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 2020     | 39.46%  |
| Intel                                        | 1702     | 33.25%  |
| AMD                                          | 1323     | 25.84%  |
| ASPEED Technology                            | 44       | 0.86%   |
| Matrox Electronics Systems                   | 26       | 0.51%   |
| ATI Technologies                             | 2        | 0.04%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.02%   |
| VIA Technologies                             | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 292      | 5.58%   |
| Intel HD Graphics 530                                                       | 166      | 3.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 161      | 3.08%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 143      | 2.73%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 138      | 2.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 136      | 2.6%    |
| Nvidia GK208B [GeForce GT 710]                                              | 101      | 1.93%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 81       | 1.55%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 77       | 1.47%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 76       | 1.45%   |
| Intel HD Graphics 630                                                       | 74       | 1.41%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 70       | 1.34%   |
| Nvidia GT218 [GeForce 210]                                                  | 69       | 1.32%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 62       | 1.19%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 60       | 1.15%   |
| Nvidia GK208B [GeForce GT 730]                                              | 59       | 1.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 56       | 1.07%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 53       | 1.01%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 51       | 0.98%   |
| AMD Raphael                                                                 | 51       | 0.98%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 51       | 0.98%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 49       | 0.94%   |
| Intel AlderLake-S GT1                                                       | 46       | 0.88%   |
| ASPEED Technology ASPEED Graphics Family                                    | 44       | 0.84%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 42       | 0.8%    |
| Nvidia GF119 [GeForce GT 610]                                               | 38       | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 38       | 0.73%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 37       | 0.71%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 37       | 0.71%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 37       | 0.71%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 36       | 0.69%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 36       | 0.69%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 34       | 0.65%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 34       | 0.65%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 34       | 0.65%   |
| Nvidia AD102 [GeForce RTX 4090]                                             | 33       | 0.63%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 32       | 0.61%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 32       | 0.61%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 31       | 0.59%   |
| Intel Core Processor Integrated Graphics Controller                         | 31       | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 1814     | 38.01%  |
| 1 x Intel                | 1441     | 30.2%   |
| 1 x AMD                  | 1167     | 24.46%  |
| Intel + Nvidia           | 88       | 1.84%   |
| AMD + Nvidia             | 71       | 1.49%   |
| 2 x AMD                  | 47       | 0.98%   |
| Intel + AMD              | 32       | 0.67%   |
| 1 x ASPEED               | 32       | 0.67%   |
| 2 x Nvidia               | 27       | 0.57%   |
| 1 x Matrox               | 19       | 0.4%    |
| Nvidia + ASPEED          | 9        | 0.19%   |
| Other                    | 4        | 0.08%   |
| Nvidia + Matrox          | 4        | 0.08%   |
| AMD + Matrox             | 3        | 0.06%   |
| 1 x Intel + 3 x Nvidia   | 2        | 0.04%   |
| Intel + AMD + 1 x Nvidia | 2        | 0.04%   |
| AMD + ASPEED             | 2        | 0.04%   |
| 3 x Nvidia + 1 x ASPEED  | 1        | 0.02%   |
| 3 x AMD                  | 1        | 0.02%   |
| 1 x XGI                  | 1        | 0.02%   |
| 1 x VIA                  | 1        | 0.02%   |
| Intel + 2 x Nvidia       | 1        | 0.02%   |
| Intel + 2 x AMD          | 1        | 0.02%   |
| Intel + AMD + 3 x Nvidia | 1        | 0.02%   |
| AMD + 2 x Nvidia         | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 3287     | 68.51%  |
| Proprietary | 1251     | 26.07%  |
| Unknown     | 260      | 5.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 3484     | 72.57%  |
| 1.01-2.0   | 289      | 6.02%   |
| 7.01-8.0   | 212      | 4.42%   |
| 0.51-1.0   | 212      | 4.42%   |
| 3.01-4.0   | 183      | 3.81%   |
| 0.01-0.5   | 164      | 3.42%   |
| 8.01-16.0  | 115      | 2.4%    |
| 5.01-6.0   | 71       | 1.48%   |
| 16.01-24.0 | 35       | 0.73%   |
| 2.01-3.0   | 29       | 0.6%    |
| 4.01-5.0   | 6        | 0.12%   |
| 32.01-64.0 | 1        | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 793      | 16.64%  |
| Dell                 | 577      | 12.1%   |
| Goldstar             | 456      | 9.57%   |
| Hewlett-Packard      | 338      | 7.09%   |
| Acer                 | 319      | 6.69%   |
| AOC                  | 225      | 4.72%   |
| Philips              | 217      | 4.55%   |
| BenQ                 | 212      | 4.45%   |
| Ancor Communications | 194      | 4.07%   |
| Iiyama               | 116      | 2.43%   |
| Lenovo               | 103      | 2.16%   |
| ViewSonic            | 93       | 1.95%   |
| ASUSTek Computer     | 85       | 1.78%   |
| Sony                 | 65       | 1.36%   |
| Vizio                | 41       | 0.86%   |
| Fujitsu Siemens      | 40       | 0.84%   |
| LG Electronics       | 38       | 0.8%    |
| Panasonic            | 36       | 0.76%   |
| MSI                  | 36       | 0.76%   |
| Eizo                 | 34       | 0.71%   |
| Sceptre Tech         | 33       | 0.69%   |
| Unknown              | 32       | 0.67%   |
| NEC Computers        | 31       | 0.65%   |
| HannStar             | 25       | 0.52%   |
| Unknown              | 22       | 0.46%   |
| Medion               | 20       | 0.42%   |
| Toshiba              | 18       | 0.38%   |
| Gigabyte Technology  | 17       | 0.36%   |
| Apple                | 16       | 0.34%   |
| HKC                  | 15       | 0.31%   |
| Sharp                | 14       | 0.29%   |
| RTK                  | 14       | 0.29%   |
| Vestel Elektronik    | 12       | 0.25%   |
| Unknown (XXX)        | 12       | 0.25%   |
| HUAWEI               | 11       | 0.23%   |
| Hitachi              | 11       | 0.23%   |
| Gericom              | 11       | 0.23%   |
| Mi                   | 10       | 0.21%   |
| Plain Tree Systems   | 9        | 0.19%   |
| MStar                | 9        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 26       | 0.51%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 23       | 0.45%   |
| Unknown                                                                | 22       | 0.43%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 20       | 0.4%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 19       | 0.38%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                      | 19       | 0.38%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 18       | 0.36%   |
| Samsung Electronics LCD Monitor LF24T450F 1920x1080                    | 15       | 0.3%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 15       | 0.3%    |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch             | 15       | 0.3%    |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch           | 15       | 0.3%    |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch  | 13       | 0.26%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                       | 13       | 0.26%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 12       | 0.24%   |
| Sony TV SNY3102 1920x1080 708x398mm 32.0-inch                          | 12       | 0.24%   |
| Philips 197EL PHLC08B 1366x768 410x230mm 18.5-inch                     | 12       | 0.24%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                        | 12       | 0.24%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 12       | 0.24%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                | 11       | 0.22%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                     | 11       | 0.22%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 11       | 0.22%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch      | 10       | 0.2%    |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch               | 10       | 0.2%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 10       | 0.2%    |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                | 10       | 0.2%    |
| Gericom Q26 QMX2426 1920x1080 550x344mm 25.5-inch                      | 10       | 0.2%    |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                      | 10       | 0.2%    |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 480x270mm 21.7-inch  | 10       | 0.2%    |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                    | 9        | 0.18%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                     | 9        | 0.18%   |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                       | 9        | 0.18%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                | 8        | 0.16%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 8        | 0.16%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 8        | 0.16%   |
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                  | 8        | 0.16%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 7        | 0.14%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                 | 7        | 0.14%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 7        | 0.14%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 7        | 0.14%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 7        | 0.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 2203     | 47.27%  |
| 3840x2160 (4K)     | 535      | 11.48%  |
| 2560x1440 (QHD)    | 324      | 6.95%   |
| 1280x1024 (SXGA)   | 254      | 5.45%   |
| 1680x1050 (WSXGA+) | 231      | 4.96%   |
| 1366x768 (WXGA)    | 172      | 3.69%   |
| 1920x1200 (WUXGA)  | 150      | 3.22%   |
| 1440x900 (WXGA+)   | 143      | 3.07%   |
| 1600x900 (HD+)     | 137      | 2.94%   |
| 3440x1440          | 71       | 1.52%   |
| 2560x1080          | 62       | 1.33%   |
| Unknown            | 60       | 1.29%   |
| 1360x768           | 58       | 1.24%   |
| 1920x540           | 42       | 0.9%    |
| 3840x1080          | 34       | 0.73%   |
| 1024x768 (XGA)     | 32       | 0.69%   |
| 1280x720 (HD)      | 24       | 0.52%   |
| 1600x1200          | 19       | 0.41%   |
| 2560x1600          | 14       | 0.3%    |
| 2288x1287          | 13       | 0.28%   |
| 3840x1600          | 12       | 0.26%   |
| 2048x1152          | 7        | 0.15%   |
| 1400x1050          | 6        | 0.13%   |
| 3840x1200          | 5        | 0.11%   |
| 1280x960           | 5        | 0.11%   |
| 4480x1440          | 4        | 0.09%   |
| 5120x1440          | 3        | 0.06%   |
| 3600x1080          | 3        | 0.06%   |
| 3360x1080          | 3        | 0.06%   |
| 3200x1080          | 3        | 0.06%   |
| 5760x1080          | 2        | 0.04%   |
| 1280x768           | 2        | 0.04%   |
| 7680x2160          | 1        | 0.02%   |
| 720x480            | 1        | 0.02%   |
| 6400x2160          | 1        | 0.02%   |
| 5760x2160          | 1        | 0.02%   |
| 5520x1080          | 1        | 0.02%   |
| 5120x1080          | 1        | 0.02%   |
| 4480x1080          | 1        | 0.02%   |
| 4240x1440          | 1        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 694      | 14.55%  |
| 27      | 687      | 14.4%   |
| 23      | 592      | 12.41%  |
| 21      | 518      | 10.86%  |
| Unknown | 322      | 6.75%   |
| 19      | 292      | 6.12%   |
| 31      | 245      | 5.14%   |
| 18      | 160      | 3.35%   |
| 22      | 155      | 3.25%   |
| 20      | 150      | 3.14%   |
| 17      | 128      | 2.68%   |
| 34      | 108      | 2.26%   |
| 84      | 86       | 1.8%    |
| 32      | 66       | 1.38%   |
| 15      | 60       | 1.26%   |
| 72      | 53       | 1.11%   |
| 54      | 51       | 1.07%   |
| 40      | 51       | 1.07%   |
| 25      | 39       | 0.82%   |
| 28      | 24       | 0.5%    |
| 46      | 20       | 0.42%   |
| 26      | 20       | 0.42%   |
| 42      | 19       | 0.4%    |
| 37      | 19       | 0.4%    |
| 52      | 17       | 0.36%   |
| 43      | 16       | 0.34%   |
| 65      | 15       | 0.31%   |
| 29      | 15       | 0.31%   |
| 49      | 13       | 0.27%   |
| 36      | 13       | 0.27%   |
| 48      | 12       | 0.25%   |
| 14      | 9        | 0.19%   |
| 142     | 7        | 0.15%   |
| 12      | 7        | 0.15%   |
| 74      | 6        | 0.13%   |
| 64      | 6        | 0.13%   |
| 35      | 6        | 0.13%   |
| 33      | 6        | 0.13%   |
| 16      | 6        | 0.13%   |
| 69      | 5        | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1837     | 39.67%  |
| 401-500        | 1117     | 24.12%  |
| 601-700        | 363      | 7.84%   |
| Unknown        | 322      | 6.95%   |
| 701-800        | 194      | 4.19%   |
| 301-350        | 181      | 3.91%   |
| 1001-1500      | 159      | 3.43%   |
| 351-400        | 157      | 3.39%   |
| 1501-2000      | 155      | 3.35%   |
| 801-900        | 84       | 1.81%   |
| 901-1000       | 37       | 0.8%    |
| 201-300        | 17       | 0.37%   |
| More than 2000 | 8        | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 3056     | 69.06%  |
| 16/10   | 574      | 12.97%  |
| Unknown | 257      | 5.81%   |
| 5/4     | 252      | 5.69%   |
| 21/9    | 140      | 3.16%   |
| 4/3     | 66       | 1.49%   |
| 32/9    | 29       | 0.66%   |
| 3/2     | 19       | 0.43%   |
| 6/5     | 11       | 0.25%   |
| 1.00    | 10       | 0.23%   |
| 0.56    | 3        | 0.07%   |
| 2.12    | 2        | 0.05%   |
| 2.00    | 2        | 0.05%   |
| 1.96    | 2        | 0.05%   |
| 3.20    | 1        | 0.02%   |
| 0.89    | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1525     | 32.61%  |
| 301-350        | 700      | 14.97%  |
| 151-200        | 599      | 12.81%  |
| 351-500        | 453      | 9.69%   |
| Unknown        | 322      | 6.89%   |
| More than 1000 | 281      | 6.01%   |
| 251-300        | 281      | 6.01%   |
| 141-150        | 249      | 5.33%   |
| 501-1000       | 173      | 3.7%    |
| 101-110        | 53       | 1.13%   |
| 71-80          | 10       | 0.21%   |
| 111-120        | 10       | 0.21%   |
| 131-140        | 9        | 0.19%   |
| 81-90          | 5        | 0.11%   |
| 91-100         | 3        | 0.06%   |
| 121-130        | 2        | 0.04%   |
| 41-50          | 1        | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 2816     | 62.77%  |
| 101-120       | 783      | 17.45%  |
| Unknown       | 322      | 7.18%   |
| 1-50          | 233      | 5.19%   |
| 121-160       | 226      | 5.04%   |
| 161-240       | 105      | 2.34%   |
| More than 240 | 1        | 0.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3539     | 73.41%  |
| 2     | 759      | 15.74%  |
| 0     | 429      | 8.9%    |
| 3     | 81       | 1.68%   |
| 4     | 11       | 0.23%   |
| 6     | 1        | 0.02%   |
| 5     | 1        | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 2793     | 41.73%  |
| Intel                           | 2226     | 33.26%  |
| Qualcomm Atheros                | 333      | 4.98%   |
| Broadcom                        | 198      | 2.96%   |
| TP-Link                         | 136      | 2.03%   |
| Ralink Technology               | 122      | 1.82%   |
| MediaTek                        | 99       | 1.48%   |
| Nvidia                          | 81       | 1.21%   |
| Ralink                          | 69       | 1.03%   |
| Aquantia                        | 49       | 0.73%   |
| NetGear                         | 44       | 0.66%   |
| Broadcom Limited                | 42       | 0.63%   |
| Marvell Technology Group        | 34       | 0.51%   |
| ASIX Electronics                | 33       | 0.49%   |
| Microsoft                       | 32       | 0.48%   |
| Qualcomm Atheros Communications | 31       | 0.46%   |
| Samsung Electronics             | 29       | 0.43%   |
| D-Link System                   | 29       | 0.43%   |
| D-Link                          | 23       | 0.34%   |
| Xiaomi                          | 22       | 0.33%   |
| ASUSTek Computer                | 21       | 0.31%   |
| Edimax Technology               | 17       | 0.25%   |
| Linksys                         | 14       | 0.21%   |
| IMC Networks                    | 13       | 0.19%   |
| DisplayLink                     | 13       | 0.19%   |
| AVM                             | 9        | 0.13%   |
| Qualcomm                        | 8        | 0.12%   |
| Sitecom Europe                  | 7        | 0.1%    |
| Mercucys                        | 7        | 0.1%    |
| Huawei Technologies             | 6        | 0.09%   |
| BUFFALO                         | 6        | 0.09%   |
| Belkin Components               | 6        | 0.09%   |
| ZyDAS                           | 5        | 0.07%   |
| VIA Technologies                | 5        | 0.07%   |
| OPPO Electronics                | 5        | 0.07%   |
| Mellanox Technologies           | 5        | 0.07%   |
| ICS Advent                      | 5        | 0.07%   |
| Google                          | 5        | 0.07%   |
| Arduino SA                      | 5        | 0.07%   |
| ZTE WCDMA Technologies MSM      | 4        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2173     | 28.26%  |
| Realtek RTL8125 2.5GbE Controller                                 | 308      | 4.01%   |
| Intel I211 Gigabit Network Connection                             | 229      | 2.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 219      | 2.85%   |
| Intel Wi-Fi 6 AX200                                               | 194      | 2.52%   |
| Intel Ethernet Controller I225-V                                  | 171      | 2.22%   |
| Intel Ethernet Connection (2) I219-V                              | 162      | 2.11%   |
| Intel Ethernet Connection I217-LM                                 | 161      | 2.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 97       | 1.26%   |
| Intel 82579V Gigabit Network Connection                           | 93       | 1.21%   |
| Intel Ethernet Connection (7) I219-V                              | 91       | 1.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 82       | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 81       | 1.05%   |
| Realtek 802.11ac NIC                                              | 76       | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                             | 76       | 0.99%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 75       | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 66       | 0.86%   |
| Intel Ethernet Connection I217-V                                  | 62       | 0.81%   |
| Intel Ethernet Connection (2) I218-V                              | 59       | 0.77%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 52       | 0.68%   |
| Intel 82574L Gigabit Network Connection                           | 50       | 0.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 49       | 0.64%   |
| Ralink MT7601U Wireless Adapter                                   | 46       | 0.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 45       | 0.59%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 45       | 0.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 43       | 0.56%   |
| Nvidia MCP61 Ethernet                                             | 43       | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 43       | 0.56%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 41       | 0.53%   |
| Intel Wireless 7265                                               | 41       | 0.53%   |
| Intel Wireless 7260                                               | 41       | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 40       | 0.52%   |
| Intel Wireless-AC 9260                                            | 40       | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 39       | 0.51%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 33       | 0.43%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 32       | 0.42%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 31       | 0.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 31       | 0.4%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 30       | 0.39%   |
| Intel I350 Gigabit Network Connection                             | 30       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 798      | 34.46%  |
| Realtek Semiconductor                 | 546      | 23.58%  |
| Qualcomm Atheros                      | 190      | 8.2%    |
| TP-Link                               | 133      | 5.74%   |
| Ralink Technology                     | 122      | 5.27%   |
| MediaTek                              | 92       | 3.97%   |
| Broadcom                              | 75       | 3.24%   |
| Ralink                                | 69       | 2.98%   |
| NetGear                               | 44       | 1.9%    |
| Microsoft                             | 32       | 1.38%   |
| Qualcomm Atheros Communications       | 31       | 1.34%   |
| D-Link                                | 23       | 0.99%   |
| D-Link System                         | 21       | 0.91%   |
| ASUSTek Computer                      | 20       | 0.86%   |
| Broadcom Limited                      | 19       | 0.82%   |
| Edimax Technology                     | 15       | 0.65%   |
| IMC Networks                          | 13       | 0.56%   |
| Linksys                               | 12       | 0.52%   |
| AVM                                   | 9        | 0.39%   |
| Sitecom Europe                        | 7        | 0.3%    |
| Mercucys                              | 7        | 0.3%    |
| BUFFALO                               | 6        | 0.26%   |
| Belkin Components                     | 6        | 0.26%   |
| ZyDAS                                 | 5        | 0.22%   |
| Wilocity                              | 4        | 0.17%   |
| Micro Star International              | 3        | 0.13%   |
| Gemtek                                | 2        | 0.09%   |
| Encore Electronics                    | 2        | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.09%   |
| ZyXEL Communications                  | 1        | 0.04%   |
| TRENDnet                              | 1        | 0.04%   |
| Sierra Wireless                       | 1        | 0.04%   |
| Sagem                                 | 1        | 0.04%   |
| Philips (or NXP)                      | 1        | 0.04%   |
| LSI                                   | 1        | 0.04%   |
| Guillemot                             | 1        | 0.04%   |
| Dell                                  | 1        | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 194      | 8.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 97       | 4.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 81       | 3.44%   |
| Realtek 802.11ac NIC                                          | 76       | 3.23%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 75       | 3.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 66       | 2.81%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 52       | 2.21%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 49       | 2.08%   |
| Ralink MT7601U Wireless Adapter                               | 46       | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 45       | 1.91%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 41       | 1.74%   |
| Intel Wireless 7265                                           | 41       | 1.74%   |
| Intel Wireless 7260                                           | 41       | 1.74%   |
| Intel Wireless-AC 9260                                        | 40       | 1.7%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 33       | 1.4%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 31       | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 31       | 1.32%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 30       | 1.28%   |
| Intel Wireless 3165                                           | 29       | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                | 28       | 1.19%   |
| Intel 700 Series Chipset Family Wi-Fi                         | 27       | 1.15%   |
| Ralink RT5370 Wireless Adapter                                | 26       | 1.11%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter         | 25       | 1.06%   |
| Qualcomm Atheros AR9271 802.11n                               | 25       | 1.06%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 23       | 0.98%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 23       | 0.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 23       | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 23       | 0.98%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 22       | 0.94%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 22       | 0.94%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 22       | 0.94%   |
| Intel Wireless 8260                                           | 21       | 0.89%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter               | 20       | 0.85%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 19       | 0.81%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                        | 19       | 0.81%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 19       | 0.81%   |
| Ralink RT2870/RT3070 Wireless Adapter                         | 17       | 0.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 17       | 0.72%   |
| Microsoft Xbox Wireless Adapter for Windows                   | 17       | 0.72%   |
| Intel Wireless 8265 / 8275                                    | 16       | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 2605     | 51.21%  |
| Intel                                  | 1824     | 35.86%  |
| Qualcomm Atheros                       | 161      | 3.16%   |
| Broadcom                               | 126      | 2.48%   |
| Nvidia                                 | 81       | 1.59%   |
| Aquantia                               | 49       | 0.96%   |
| Marvell Technology Group               | 34       | 0.67%   |
| ASIX Electronics                       | 33       | 0.65%   |
| Broadcom Limited                       | 23       | 0.45%   |
| Xiaomi                                 | 22       | 0.43%   |
| Samsung Electronics                    | 20       | 0.39%   |
| DisplayLink                            | 13       | 0.26%   |
| Qualcomm                               | 8        | 0.16%   |
| D-Link System                          | 8        | 0.16%   |
| MediaTek                               | 6        | 0.12%   |
| VIA Technologies                       | 5        | 0.1%    |
| OPPO Electronics                       | 5        | 0.1%    |
| ICS Advent                             | 5        | 0.1%    |
| Huawei Technologies                    | 5        | 0.1%    |
| Google                                 | 5        | 0.1%    |
| ZTE WCDMA Technologies MSM             | 4        | 0.08%   |
| JMicron Technology                     | 4        | 0.08%   |
| TP-Link                                | 3        | 0.06%   |
| Mellanox Technologies                  | 3        | 0.06%   |
| Chelsio Communications                 | 3        | 0.06%   |
| American Megatrends                    | 3        | 0.06%   |
| Tehuti Networks                        | 2        | 0.04%   |
| Sundance Technology Inc / IC Plus      | 2        | 0.04%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.04%   |
| Linksys                                | 2        | 0.04%   |
| Edimax Technology                      | 2        | 0.04%   |
| Apple                                  | 2        | 0.04%   |
| 3Com                                   | 2        | 0.04%   |
| Vimtron Electronics                    | 1        | 0.02%   |
| Spreadtrum Communications              | 1        | 0.02%   |
| QNAP System                            | 1        | 0.02%   |
| QinHeng Electronics                    | 1        | 0.02%   |
| Prolific Technology                    | 1        | 0.02%   |
| Novatel Wireless                       | 1        | 0.02%   |
| Netchip Technology                     | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2173     | 41.22%  |
| Realtek RTL8125 2.5GbE Controller                                 | 308      | 5.84%   |
| Intel I211 Gigabit Network Connection                             | 229      | 4.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 219      | 4.15%   |
| Intel Ethernet Controller I225-V                                  | 171      | 3.24%   |
| Intel Ethernet Connection (2) I219-V                              | 162      | 3.07%   |
| Intel Ethernet Connection I217-LM                                 | 161      | 3.05%   |
| Intel 82579V Gigabit Network Connection                           | 93       | 1.76%   |
| Intel Ethernet Connection (7) I219-V                              | 91       | 1.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 82       | 1.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 76       | 1.44%   |
| Intel Ethernet Connection I217-V                                  | 62       | 1.18%   |
| Intel Ethernet Connection (2) I218-V                              | 59       | 1.12%   |
| Intel 82574L Gigabit Network Connection                           | 50       | 0.95%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 45       | 0.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 43       | 0.82%   |
| Nvidia MCP61 Ethernet                                             | 43       | 0.82%   |
| Intel I210 Gigabit Network Connection                             | 43       | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 40       | 0.76%   |
| Intel Ethernet Connection (7) I219-LM                             | 39       | 0.74%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 32       | 0.61%   |
| Intel I350 Gigabit Network Connection                             | 30       | 0.57%   |
| Intel Ethernet Connection (5) I219-LM                             | 30       | 0.57%   |
| Intel Ethernet Controller I226-V                                  | 29       | 0.55%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 29       | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 26       | 0.49%   |
| Intel Ethernet Connection (14) I219-V                             | 24       | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 21       | 0.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 21       | 0.4%    |
| Intel Ethernet Connection (17) I219-V                             | 21       | 0.4%    |
| Intel 82578DC Gigabit Network Connection                          | 21       | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 20       | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 19       | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 19       | 0.36%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 19       | 0.36%   |
| Intel Ethernet Controller X550                                    | 19       | 0.36%   |
| Intel Ethernet Connection (2) I218-LM                             | 19       | 0.36%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 19       | 0.36%   |
| Intel 82578DM Gigabit Network Connection                          | 18       | 0.34%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 17       | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4687     | 67.77%  |
| WiFi     | 2164     | 31.29%  |
| Modem    | 57       | 0.82%   |
| Unknown  | 8        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3744     | 75.65%  |
| WiFi     | 1204     | 24.33%  |
| Modem    | 1        | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2902     | 61.12%  |
| 2     | 1531     | 32.25%  |
| 3     | 221      | 4.65%   |
| 4     | 43       | 0.91%   |
| 0     | 28       | 0.59%   |
| 5     | 15       | 0.32%   |
| 7     | 4        | 0.08%   |
| 8     | 2        | 0.04%   |
| 9     | 1        | 0.02%   |
| 6     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3178     | 66.74%  |
| Yes  | 1584     | 33.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 736      | 45.26%  |
| Cambridge Silicon Radio         | 301      | 18.51%  |
| Realtek Semiconductor           | 119      | 7.32%   |
| ASUSTek Computer                | 95       | 5.84%   |
| Broadcom                        | 70       | 4.31%   |
| Qualcomm Atheros Communications | 65       | 4%      |
| MediaTek                        | 52       | 3.2%    |
| IMC Networks                    | 38       | 2.34%   |
| TP-Link                         | 31       | 1.91%   |
| Apple                           | 24       | 1.48%   |
| Lite-On Technology              | 19       | 1.17%   |
| Foxconn / Hon Hai               | 14       | 0.86%   |
| Belkin Components               | 8        | 0.49%   |
| Edimax Technology               | 6        | 0.37%   |
| Realtek                         | 5        | 0.31%   |
| Dell                            | 5        | 0.31%   |
| Micro Star International        | 4        | 0.25%   |
| Logitech                        | 4        | 0.25%   |
| Integrated System Solution      | 4        | 0.25%   |
| Unknown                         | 4        | 0.25%   |
| Dynex                           | 3        | 0.18%   |
| Actions                         | 3        | 0.18%   |
| Toshiba                         | 2        | 0.12%   |
| Ralink                          | 2        | 0.12%   |
| HTC (High Tech Computer)        | 2        | 0.12%   |
| Hewlett-Packard                 | 2        | 0.12%   |
| D-Link System                   | 2        | 0.12%   |
| Conwise Technology              | 2        | 0.12%   |
| TRENDnet                        | 1        | 0.06%   |
| Primax Electronics              | 1        | 0.06%   |
| Mobile Action Technology        | 1        | 0.06%   |
| D-Link                          | 1        | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 301      | 18.49%  |
| Intel AX200 Bluetooth                                 | 167      | 10.26%  |
| Intel Bluetooth wireless interface                    | 144      | 8.85%   |
| Intel Bluetooth Device                                | 142      | 8.72%   |
| Intel AX210 Bluetooth                                 | 95       | 5.84%   |
| Realtek Bluetooth Radio                               | 84       | 5.16%   |
| Intel Wireless-AC 3168 Bluetooth                      | 79       | 4.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 57       | 3.5%    |
| MediaTek Wireless_Device                              | 52       | 3.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 40       | 2.46%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 34       | 2.09%   |
| ASUS Bluetooth Device                                 | 34       | 2.09%   |
| TP-Link UB500 Adapter                                 | 31       | 1.9%    |
| Qualcomm Atheros  Bluetooth Device                    | 25       | 1.54%   |
| IMC Networks Bluetooth Radio                          | 22       | 1.35%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 22       | 1.35%   |
| Realtek  Bluetooth 4.2 Adapter                        | 21       | 1.29%   |
| ASUS Bluetooth Radio                                  | 18       | 1.11%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 17       | 1.04%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 14       | 0.86%   |
| IMC Networks Wireless_Device                          | 11       | 0.68%   |
| Foxconn / Hon Hai Wireless_Device                     | 11       | 0.68%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 10       | 0.61%   |
| Apple Bluetooth USB Host Controller                   | 10       | 0.61%   |
| Lite-On Bluetooth Device                              | 9        | 0.55%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 9        | 0.55%   |
| ASUS Qualcomm Bluetooth 4.1                           | 8        | 0.49%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 8        | 0.49%   |
| Realtek RTL8821A Bluetooth                            | 7        | 0.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 6        | 0.37%   |
| Broadcom BCM2045 Bluetooth                            | 6        | 0.37%   |
| Realtek Bluetooth Radio                               | 5        | 0.31%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 5        | 0.31%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 5        | 0.31%   |
| Edimax Edimax Bluetooth Adapter                       | 5        | 0.31%   |
| Broadcom BCM20702A0                                   | 5        | 0.31%   |
| Apple Bluetooth HCI                                   | 5        | 0.31%   |
| Realtek Bluetooth 5.1 Radio                           | 4        | 0.25%   |
| Micro Star International Bluetooth Device             | 4        | 0.25%   |
| Logitech BT Mini-Receiver (HCI mode)                  | 4        | 0.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 3084     | 39.64%  |
| Nvidia                                       | 1916     | 24.63%  |
| AMD                                          | 1836     | 23.6%   |
| C-Media Electronics                          | 149      | 1.92%   |
| Logitech                                     | 82       | 1.05%   |
| Creative Labs                                | 73       | 0.94%   |
| ASUSTek Computer                             | 60       | 0.77%   |
| GN Netcom                                    | 39       | 0.5%    |
| Micro Star International                     | 37       | 0.48%   |
| Texas Instruments                            | 31       | 0.4%    |
| Kingston Technology                          | 29       | 0.37%   |
| JMTek                                        | 24       | 0.31%   |
| Razer USA                                    | 22       | 0.28%   |
| Corsair                                      | 22       | 0.28%   |
| SteelSeries ApS                              | 21       | 0.27%   |
| Generalplus Technology                       | 20       | 0.26%   |
| Focusrite-Novation                           | 20       | 0.26%   |
| Creative Technology                          | 20       | 0.26%   |
| Plantronics                                  | 15       | 0.19%   |
| Zoran Co. Personal Media Division (Nogatech) | 12       | 0.15%   |
| VIA Technologies                             | 8        | 0.1%    |
| Tenx Technology                              | 8        | 0.1%    |
| Realtek Semiconductor                        | 8        | 0.1%    |
| KTMicro                                      | 8        | 0.1%    |
| Hewlett-Packard                              | 8        | 0.1%    |
| Giga-Byte Technology                         | 8        | 0.1%    |
| Dell                                         | 8        | 0.1%    |
| Blue Microphones                             | 8        | 0.1%    |
| M-Audio                                      | 7        | 0.09%   |
| Astro Gaming                                 | 7        | 0.09%   |
| Apple                                        | 7        | 0.09%   |
| Sony                                         | 6        | 0.08%   |
| DSEA A/S                                     | 6        | 0.08%   |
| BR23                                         | 6        | 0.08%   |
| Sennheiser Communications                    | 5        | 0.06%   |
| Samson Technologies                          | 5        | 0.06%   |
| Yamaha                                       | 4        | 0.05%   |
| Syntek                                       | 4        | 0.05%   |
| Microsoft                                    | 4        | 0.05%   |
| XMOS                                         | 3        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 455      | 5.05%   |
| AMD Starship/Matisse HD Audio Controller                                   | 446      | 4.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 353      | 3.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 323      | 3.59%   |
| AMD Family 17h/19h HD Audio Controller                                     | 283      | 3.14%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 279      | 3.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 270      | 3%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 266      | 2.95%   |
| Intel 200 Series PCH HD Audio                                              | 248      | 2.75%   |
| Intel Cannon Lake PCH cAVS                                                 | 181      | 2.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 174      | 1.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 167      | 1.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 152      | 1.69%   |
| AMD FCH Azalia Controller                                                  | 150      | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 132      | 1.47%   |
| Intel Alder Lake-S HD Audio Controller                                     | 128      | 1.42%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 128      | 1.42%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 127      | 1.41%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 120      | 1.33%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 118      | 1.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 110      | 1.22%   |
| Nvidia GA104 High Definition Audio Controller                              | 105      | 1.17%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 105      | 1.17%   |
| Nvidia High Definition Audio Controller                                    | 104      | 1.16%   |
| Nvidia GA102 High Definition Audio Controller                              | 97       | 1.08%   |
| Nvidia GP104 High Definition Audio Controller                              | 96       | 1.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 94       | 1.04%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 92       | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                              | 90       | 1%      |
| Nvidia GP106 High Definition Audio Controller                              | 88       | 0.98%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 81       | 0.9%    |
| Intel 9 Series Chipset Family HD Audio Controller                          | 81       | 0.9%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 77       | 0.86%   |
| Nvidia GA106 High Definition Audio Controller                              | 73       | 0.81%   |
| Nvidia GK107 HDMI Audio Controller                                         | 71       | 0.79%   |
| Nvidia GF119 HDMI Audio Controller                                         | 70       | 0.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 70       | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                              | 63       | 0.7%    |
| Nvidia TU106 High Definition Audio Controller                              | 62       | 0.69%   |
| Nvidia GP108 High Definition Audio Controller                              | 59       | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| Kingston                     | 448      | 18%     |
| Corsair                      | 356      | 14.3%   |
| Samsung Electronics          | 289      | 11.61%  |
| SK hynix                     | 238      | 9.56%   |
| Crucial                      | 202      | 8.12%   |
| G.Skill                      | 197      | 7.91%   |
| Unknown                      | 190      | 7.63%   |
| Micron Technology            | 143      | 5.75%   |
| A-DATA Technology            | 68       | 2.73%   |
| Team                         | 46       | 1.85%   |
| Unknown                      | 46       | 1.85%   |
| Patriot                      | 26       | 1.04%   |
| Ramaxel Technology           | 23       | 0.92%   |
| Nanya Technology             | 20       | 0.8%    |
| Unknown (ABCD)               | 13       | 0.52%   |
| Transcend                    | 11       | 0.44%   |
| Elpida                       | 11       | 0.44%   |
| Smart                        | 10       | 0.4%    |
| Apacer                       | 8        | 0.32%   |
| AMD                          | 8        | 0.32%   |
| PNY                          | 7        | 0.28%   |
| Hewlett-Packard              | 6        | 0.24%   |
| GOODRAM                      | 6        | 0.24%   |
| ASint Technology             | 6        | 0.24%   |
| Timetec                      | 5        | 0.2%    |
| Silicon Power                | 5        | 0.2%    |
| Avant                        | 5        | 0.2%    |
| Patriot Memory (PDP Systems) | 4        | 0.16%   |
| Lexar                        | 4        | 0.16%   |
| KETECH                       | 4        | 0.16%   |
| Innodisk                     | 4        | 0.16%   |
| GeIL                         | 4        | 0.16%   |
| Atermiter                    | 4        | 0.16%   |
| Asgard                       | 4        | 0.16%   |
| Unknown (0x1636)             | 3        | 0.12%   |
| Unifosa                      | 3        | 0.12%   |
| Neo Forza                    | 3        | 0.12%   |
| KLEVV                        | 3        | 0.12%   |
| Kingmax                      | 3        | 0.12%   |
| Hikvision                    | 3        | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown                                                        | 46       | 1.71%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 25       | 0.93%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 22       | 0.82%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 17       | 0.63%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s           | 17       | 0.63%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                    | 17       | 0.63%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s            | 16       | 0.59%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 16       | 0.59%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 15       | 0.56%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 14       | 0.52%   |
| Team RAM TEAMGROUP-UD4-3200 32GB DIMM DDR4 3800MT/s            | 14       | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 13       | 0.48%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s          | 13       | 0.48%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s         | 13       | 0.48%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 12       | 0.45%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s           | 12       | 0.45%   |
| Kingston RAM 9905734-415.A00G 16GB DIMM DDR4 3200MT/s          | 12       | 0.45%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 11       | 0.41%   |
| Samsung RAM M378A5244CB0-CRC 4GB DIMM DDR4 3066MT/s            | 11       | 0.41%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s           | 11       | 0.41%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 10       | 0.37%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 10       | 0.37%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                           | 9        | 0.33%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s        | 9        | 0.33%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s            | 9        | 0.33%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s          | 9        | 0.33%   |
| Kingston RAM 9905734-016.A00G 16GB DIMM DDR4 3200MT/s          | 9        | 0.33%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s         | 9        | 0.33%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s          | 9        | 0.33%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s           | 8        | 0.3%    |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 8        | 0.3%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 8        | 0.3%    |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s            | 8        | 0.3%    |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s              | 8        | 0.3%    |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 8        | 0.3%    |
| Kingston RAM KF556C40-32 32GB DIMM DDR5 5808MT/s               | 8        | 0.3%    |
| Kingston RAM KF3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s         | 8        | 0.3%    |
| Corsair RAM CMK64GX5M2B5600C40 32GB DIMM DDR5 5600MT/s         | 8        | 0.3%    |
| Corsair RAM CM4X16GC3000C16K4D 16GB DIMM DDR4 3000MT/s         | 8        | 0.3%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 7        | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR4         | 1163     | 52.53%  |
| DDR3         | 692      | 31.26%  |
| DDR5         | 108      | 4.88%   |
| Unknown      | 84       | 3.79%   |
| SDRAM        | 60       | 2.71%   |
| DDR2         | 56       | 2.53%   |
| LPDDR4       | 24       | 1.08%   |
| DDR          | 14       | 0.63%   |
| DRAM         | 7        | 0.32%   |
| LPDDR3       | 4        | 0.18%   |
| LPDDR5       | 1        | 0.05%   |
| DDR2 FB-DIMM | 1        | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 1953     | 89.71%  |
| SODIMM       | 199      | 9.14%   |
| Row Of Chips | 10       | 0.46%   |
| RIMM         | 10       | 0.46%   |
| FB-DIMM      | 4        | 0.18%   |
| Unknown      | 1        | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Desktops | Percent |
|--------|----------|---------|
| 8192   | 841      | 35.65%  |
| 4096   | 523      | 22.17%  |
| 16384  | 516      | 21.87%  |
| 2048   | 216      | 9.16%   |
| 32768  | 215      | 9.11%   |
| 1024   | 37       | 1.57%   |
| 65536  | 5        | 0.21%   |
| 49152  | 3        | 0.13%   |
| 512    | 2        | 0.08%   |
| 131072 | 1        | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 422      | 17.34%  |
| 3200    | 311      | 12.78%  |
| 1333    | 220      | 9.04%   |
| 2400    | 182      | 7.48%   |
| 3600    | 158      | 6.49%   |
| 2667    | 158      | 6.49%   |
| 2133    | 112      | 4.6%    |
| 1867    | 59       | 2.42%   |
| 800     | 52       | 2.14%   |
| 3000    | 50       | 2.05%   |
| 2666    | 46       | 1.89%   |
| 4800    | 42       | 1.73%   |
| 3733    | 38       | 1.56%   |
| 2933    | 37       | 1.52%   |
| 1800    | 34       | 1.4%    |
| 3400    | 33       | 1.36%   |
| 3800    | 32       | 1.31%   |
| 667     | 31       | 1.27%   |
| 3533    | 26       | 1.07%   |
| 1866    | 25       | 1.03%   |
| 1066    | 24       | 0.99%   |
| 5600    | 21       | 0.86%   |
| 3534    | 16       | 0.66%   |
| Unknown | 16       | 0.66%   |
| 3466    | 14       | 0.58%   |
| 3066    | 13       | 0.53%   |
| 1067    | 13       | 0.53%   |
| 6000    | 12       | 0.49%   |
| 3666    | 12       | 0.49%   |
| 3266    | 12       | 0.49%   |
| 5200    | 11       | 0.45%   |
| 2800    | 10       | 0.41%   |
| 2000    | 10       | 0.41%   |
| 3933    | 9        | 0.37%   |
| 3866    | 9        | 0.37%   |
| 3500    | 9        | 0.37%   |
| 1648    | 9        | 0.37%   |
| 1334    | 9        | 0.37%   |
| 400     | 9        | 0.37%   |
| 5808    | 8        | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Hewlett-Packard        | 77       | 34.22%  |
| Brother Industries     | 52       | 23.11%  |
| Canon                  | 27       | 12%     |
| Seiko Epson            | 23       | 10.22%  |
| Samsung Electronics    | 20       | 8.89%   |
| Dymo-CoStar            | 5        | 2.22%   |
| Lexmark International  | 4        | 1.78%   |
| Prolific Technology    | 3        | 1.33%   |
| STMicroelectronics     | 2        | 0.89%   |
| QinHeng Electronics    | 2        | 0.89%   |
| Kyocera                | 2        | 0.89%   |
| Zebra                  | 1        | 0.44%   |
| Xerox                  | 1        | 0.44%   |
| Pantum                 | 1        | 0.44%   |
| Oki Data               | 1        | 0.44%   |
| Fuji Xerox             | 1        | 0.44%   |
| Custom Engineering SPA | 1        | 0.44%   |
| BESTEASY               | 1        | 0.44%   |
| Apple                  | 1        | 0.44%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP DeskJet 2130 series                                    | 5        | 2.18%   |
| Dymo-CoStar LabelWriter 400                               | 4        | 1.75%   |
| Seiko Epson L360 Series                                   | 3        | 1.31%   |
| Seiko Epson L3150 Series                                  | 3        | 1.31%   |
| Seiko Epson ET-2720 Series                                | 3        | 1.31%   |
| Samsung Composite Device                                  | 3        | 1.31%   |
| Prolific PL2305 Parallel Port                             | 3        | 1.31%   |
| HP OfficeJet 3830 series                                  | 3        | 1.31%   |
| HP DeskJet 3700 series                                    | 3        | 1.31%   |
| Canon TS3100 series                                       | 3        | 1.31%   |
| Brother Printer                                           | 3        | 1.31%   |
| Brother MFC-L2700DW                                       | 3        | 1.31%   |
| Brother HL-L2350DW series                                 | 3        | 1.31%   |
| Brother HL-1440 Laser Printer                             | 3        | 1.31%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2        | 0.87%   |
| Seiko Epson XP-2100 Series                                | 2        | 0.87%   |
| Seiko Epson ET-4800 Series                                | 2        | 0.87%   |
| Seiko Epson ET-2810 Series                                | 2        | 0.87%   |
| Samsung ML-216x Series Laser Printer                      | 2        | 0.87%   |
| Samsung M2070 Series                                      | 2        | 0.87%   |
| Samsung C460 Series                                       | 2        | 0.87%   |
| QinHeng CH340S                                            | 2        | 0.87%   |
| HP OfficeJet 5600 (USBHUB)                                | 2        | 0.87%   |
| HP Officejet 4500 G510n-z                                 | 2        | 0.87%   |
| HP LaserJet P1005                                         | 2        | 0.87%   |
| HP LaserJet M203-M206                                     | 2        | 0.87%   |
| HP LaserJet M14-M17                                       | 2        | 0.87%   |
| HP LaserJet 4250                                          | 2        | 0.87%   |
| HP LaserJet 3015                                          | 2        | 0.87%   |
| HP HP OfficeJet Pro 8020 series                           | 2        | 0.87%   |
| HP ENVY 5540 series                                       | 2        | 0.87%   |
| HP ENVY 4520 series                                       | 2        | 0.87%   |
| HP ENVY 4500 series                                       | 2        | 0.87%   |
| HP DeskJet 4100 series                                    | 2        | 0.87%   |
| HP DeskJet 3630 series                                    | 2        | 0.87%   |
| HP Deskjet 3050A                                          | 2        | 0.87%   |
| HP DeskJet 2600 series                                    | 2        | 0.87%   |
| HP Deskjet 2510 series                                    | 2        | 0.87%   |
| HP DeskJet 2300 series                                    | 2        | 0.87%   |
| HP DeskJet 1110 series                                    | 2        | 0.87%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 24       | 58.54%  |
| Seiko Epson                 | 9        | 21.95%  |
| Hewlett-Packard             | 6        | 14.63%  |
| UMAX                        | 1        | 2.44%   |
| Acer Peripherals (now BenQ) | 1        | 2.44%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 120                                  | 6        | 14.63%  |
| Canon CanoScan LiDE 220                                  | 4        | 9.76%   |
| Canon CanoScan LiDE 100                                  | 3        | 7.32%   |
| Seiko Epson GT-F700 [Perfection V350]                    | 2        | 4.88%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 2        | 4.88%   |
| Canon CanoScan LiDE 110                                  | 2        | 4.88%   |
| UMAX Astra 2200/2200SU                                   | 1        | 2.44%   |
| Seiko Epson GT-X770 [Perfection V500]                    | 1        | 2.44%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 2.44%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 1        | 2.44%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]       | 1        | 2.44%   |
| Seiko Epson GT-7700U [Perfection 1240U]                  | 1        | 2.44%   |
| HP Scanjet N6010                                         | 1        | 2.44%   |
| HP ScanJet G4010                                         | 1        | 2.44%   |
| HP Scanjet G2710                                         | 1        | 2.44%   |
| HP ScanJet 4850C/4890C                                   | 1        | 2.44%   |
| HP ScanJet 3970c                                         | 1        | 2.44%   |
| HP ScanJet 3400cse                                       | 1        | 2.44%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 1        | 2.44%   |
| Canon CanoScan N1240U/LiDE 30                            | 1        | 2.44%   |
| Canon CanoScan LiDE 70                                   | 1        | 2.44%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 1        | 2.44%   |
| Canon CanoScan LIDE 25                                   | 1        | 2.44%   |
| Canon CanoScan LiDE 210                                  | 1        | 2.44%   |
| Canon CanoScan LiDE 200                                  | 1        | 2.44%   |
| Canon CanoScan 9000F Mark II                             | 1        | 2.44%   |
| Canon CanoScan 4200F                                     | 1        | 2.44%   |
| Acer Peripherals (now BenQ) Benq 5000                    | 1        | 2.44%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 314      | 36.09%  |
| Microdia                               | 76       | 8.74%   |
| Microsoft                              | 54       | 6.21%   |
| Sunplus Innovation Technology          | 41       | 4.71%   |
| Apple                                  | 32       | 3.68%   |
| Samsung Electronics                    | 30       | 3.45%   |
| Generalplus Technology                 | 27       | 3.1%    |
| ARC International                      | 23       | 2.64%   |
| Chicony Electronics                    | 20       | 2.3%    |
| Z-Star Microelectronics                | 19       | 2.18%   |
| Realtek Semiconductor                  | 19       | 2.18%   |
| Creality 3D Technology                 | 11       | 1.26%   |
| Trust                                  | 10       | 1.15%   |
| Creative Technology                    | 10       | 1.15%   |
| KYE Systems (Mouse Systems)            | 9        | 1.03%   |
| Hewlett-Packard                        | 8        | 0.92%   |
| Cubeternet                             | 8        | 0.92%   |
| MacroSilicon                           | 7        | 0.8%    |
| Razer USA                              | 6        | 0.69%   |
| Jieli Technology                       | 6        | 0.69%   |
| GEMBIRD                                | 6        | 0.69%   |
| WaveRider Communications               | 5        | 0.57%   |
| Sonix Technology                       | 5        | 0.57%   |
| AVerMedia Technologies                 | 5        | 0.57%   |
| Aveo Technology                        | 5        | 0.57%   |
| Philips (or NXP)                       | 4        | 0.46%   |
| Linux Foundation                       | 4        | 0.46%   |
| Genesys Logic                          | 4        | 0.46%   |
| Asuscom Network                        | 4        | 0.46%   |
| YGTek                                  | 3        | 0.34%   |
| OPPO Electronics                       | 3        | 0.34%   |
| IMC Networks                           | 3        | 0.34%   |
| Huawei Technologies                    | 3        | 0.34%   |
| GenesysLogic Technology                | 3        | 0.34%   |
| Cheng Uei Precision Industry (Foxlink) | 3        | 0.34%   |
| Bison Electronics                      | 3        | 0.34%   |
| Arkmicro Technologies                  | 3        | 0.34%   |
| Alcor Micro                            | 3        | 0.34%   |
| YT-221117-J                            | 2        | 0.23%   |
| webcamvendor                           | 2        | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 76       | 8.71%   |
| Logitech HD Pro Webcam C920              | 45       | 5.15%   |
| Logitech C922 Pro Stream Webcam          | 32       | 3.67%   |
| Samsung Galaxy series, misc. (MTP mode)  | 29       | 3.32%   |
| Apple iPhone 5/5C/5S/6/SE                | 29       | 3.32%   |
| ARC International Camera                 | 23       | 2.63%   |
| Microdia Webcam Vitade AF                | 21       | 2.41%   |
| Logitech C920 PRO HD Webcam              | 18       | 2.06%   |
| Microsoft LifeCam HD-3000                | 15       | 1.72%   |
| Microdia USB Camera                      | 15       | 1.72%   |
| Logitech Webcam C170                     | 14       | 1.6%    |
| Logitech HD Webcam C615                  | 14       | 1.6%    |
| Generalplus GENERAL WEBCAM               | 14       | 1.6%    |
| Sunplus Integrated_Webcam_HD             | 13       | 1.49%   |
| Logitech BRIO Ultra HD Webcam            | 12       | 1.37%   |
| Creality 3D CREALITY CAM                 | 11       | 1.26%   |
| Microsoft LifeCam Cinema                 | 10       | 1.15%   |
| Microdia Sonix USB 2.0 Camera            | 10       | 1.15%   |
| Microdia Camera                          | 10       | 1.15%   |
| Logitech Webcam C310                     | 9        | 1.03%   |
| Logitech HD Webcam C525                  | 9        | 1.03%   |
| Microdia USB 2.0 Camera                  | 7        | 0.8%    |
| Microdia Integrated Camera               | 7        | 0.8%    |
| Logitech Webcam C930e                    | 7        | 0.8%    |
| Logitech StreamCam                       | 7        | 0.8%    |
| Logitech HD Webcam C910                  | 7        | 0.8%    |
| Generalplus 808 Camera #9 (web-cam mode) | 7        | 0.8%    |
| Chicony HP High Definition 1MP Webcam    | 7        | 0.8%    |
| Z-Star Venus USB2.0 Camera               | 6        | 0.69%   |
| Sunplus WEBCAM ESSENTIELB W1             | 6        | 0.69%   |
| MacroSilicon USB3. 0 capture             | 6        | 0.69%   |
| Jieli USB PHY 2.0                        | 6        | 0.69%   |
| Generalplus WEB CAM                      | 6        | 0.69%   |
| Sunplus HD 720P webcam                   | 5        | 0.57%   |
| Realtek USB Camera                       | 5        | 0.57%   |
| Realtek Full HD webcam                   | 5        | 0.57%   |
| Logitech Webcam C925e                    | 5        | 0.57%   |
| Logitech QuickCam Pro 9000               | 5        | 0.57%   |
| Logitech QuickCam Communicate MP/S5500   | 5        | 0.57%   |
| Chicony Integrated Camera                | 5        | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Dell                  | 2        | 33.33%  |
| Microsoft             | 1        | 16.67%  |
| LighTuning Technology | 1        | 16.67%  |
| Elan Microelectronics | 1        | 16.67%  |
| DigitalPersona        | 1        | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Dell MS819 Wired Mouse With Fingerprint Reader | 2        | 33.33%  |
| Microsoft Fingerprint Reader                   | 1        | 16.67%  |
| LighTuning Fingerprint Sensor                  | 1        | 16.67%  |
| Elan fingerprint sensor [FeinTech FPS00200]    | 1        | 16.67%  |
| DigitalPersona Fingerprint Reader              | 1        | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Advanced Card Systems     | 9        | 24.32%  |
| Realtek Semiconductor     | 5        | 13.51%  |
| Alcor Micro               | 5        | 13.51%  |
| Gemalto (was Gemplus)     | 4        | 10.81%  |
| SCM Microsystems          | 3        | 8.11%   |
| Chicony Electronics       | 3        | 8.11%   |
| Bit4id                    | 2        | 5.41%   |
| Reiner SCT Kartensysteme  | 1        | 2.7%    |
| Lenovo                    | 1        | 2.7%    |
| Giesecke & Devrient       | 1        | 2.7%    |
| Fujitsu Siemens Computers | 1        | 2.7%    |
| Cherry                    | 1        | 2.7%    |
| Aladdin Knowledge Systems | 1        | 2.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                          | 5        | 13.51%  |
| Advanced Card Systems ACR38 SmartCard Reader                               | 5        | 13.51%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 4        | 10.81%  |
| Alcor Micro AU9540 Smartcard Reader                                        | 4        | 10.81%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 3        | 8.11%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 3        | 8.11%   |
| Advanced Card Systems ACR122U                                              | 2        | 5.41%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 2.7%    |
| Lenovo Smartcard Keyboard                                                  | 1        | 2.7%    |
| Giesecke & Devrient StarSign CUT S                                         | 1        | 2.7%    |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 2.7%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 2.7%    |
| Bit4id miniLector-s                                                        | 1        | 2.7%    |
| Bit4id miniLector EVO                                                      | 1        | 2.7%    |
| Alcor Micro Watchdata W 1981                                               | 1        | 2.7%    |
| Aladdin Knowledge Systems Token JC                                         | 1        | 2.7%    |
| Advanced Card Systems ACR39U                                               | 1        | 2.7%    |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 2.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 3942     | 82.09%  |
| 1     | 690      | 14.37%  |
| 2     | 87       | 1.81%   |
| 4     | 32       | 0.67%   |
| 3     | 31       | 0.65%   |
| 5     | 11       | 0.23%   |
| 6     | 5        | 0.1%    |
| 8     | 2        | 0.04%   |
| 10    | 1        | 0.02%   |
| 7     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 398      | 36.82%  |
| Net/wireless             | 213      | 19.7%   |
| Unassigned class         | 129      | 11.93%  |
| Communication controller | 99       | 9.16%   |
| Sound                    | 65       | 6.01%   |
| Chipcard                 | 25       | 2.31%   |
| Camera                   | 25       | 2.31%   |
| Multimedia controller    | 24       | 2.22%   |
| Bluetooth                | 22       | 2.04%   |
| Storage/raid             | 20       | 1.85%   |
| Net/ethernet             | 18       | 1.67%   |
| Network                  | 12       | 1.11%   |
| Card reader              | 7        | 0.65%   |
| Dvb card                 | 5        | 0.46%   |
| Fingerprint reader       | 4        | 0.37%   |
| Storage/nvme             | 3        | 0.28%   |
| Storage/ata              | 3        | 0.28%   |
| Modem                    | 3        | 0.28%   |
| Tv card                  | 2        | 0.19%   |
| Firewire controller      | 2        | 0.19%   |
| Wireless                 | 1        | 0.09%   |
| Storage/ide              | 1        | 0.09%   |

