ROSA - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for ROSA.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ROSA/Desktop/README.md) and [notebooks](/Dist/ROSA/Notebook/README.md).

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

Total: 41229

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MS-N0E1 Ver                 | Notebook    | [9c4dcef9c6](https://linux-hardware.org/?probe=9c4dcef9c6) | Feb 01, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [c790793197](https://linux-hardware.org/?probe=c790793197) | Feb 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [de3138b686](https://linux-hardware.org/?probe=de3138b686) | Feb 01, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [86156a3b50](https://linux-hardware.org/?probe=86156a3b50) | Jan 31, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e53e3c6e8](https://linux-hardware.org/?probe=7e53e3c6e8) | Jan 31, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [204706229b](https://linux-hardware.org/?probe=204706229b) | Jan 31, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [f5379a55ea](https://linux-hardware.org/?probe=f5379a55ea) | Jan 31, 2023 |
| ASUSTek       | H110-PLUS                   | Desktop     | [c20a43e3e5](https://linux-hardware.org/?probe=c20a43e3e5) | Jan 31, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [260d257a0c](https://linux-hardware.org/?probe=260d257a0c) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [4830eacf5e](https://linux-hardware.org/?probe=4830eacf5e) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [0b59b68d55](https://linux-hardware.org/?probe=0b59b68d55) | Jan 30, 2023 |
| MSI           | GL75 Leopard 10SCSR         | Notebook    | [8e30762127](https://linux-hardware.org/?probe=8e30762127) | Jan 30, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [10c275723f](https://linux-hardware.org/?probe=10c275723f) | Jan 30, 2023 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [8f41c8cf5c](https://linux-hardware.org/?probe=8f41c8cf5c) | Jan 30, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [d826805d37](https://linux-hardware.org/?probe=d826805d37) | Jan 30, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [54f6c27c09](https://linux-hardware.org/?probe=54f6c27c09) | Jan 30, 2023 |
| ZoomSmart     | A1002                       | Tablet      | [f8733ffc4d](https://linux-hardware.org/?probe=f8733ffc4d) | Jan 30, 2023 |
| HP            | Pavilion g6                 | Notebook    | [d25ed40cf3](https://linux-hardware.org/?probe=d25ed40cf3) | Jan 30, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [a7232f4811](https://linux-hardware.org/?probe=a7232f4811) | Jan 30, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [7359bcfbfb](https://linux-hardware.org/?probe=7359bcfbfb) | Jan 29, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [c8c73a9f67](https://linux-hardware.org/?probe=c8c73a9f67) | Jan 29, 2023 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [183bb56595](https://linux-hardware.org/?probe=183bb56595) | Jan 29, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [868269808a](https://linux-hardware.org/?probe=868269808a) | Jan 29, 2023 |
| ASRock        | P45DE3                      | Desktop     | [e4c2e737f7](https://linux-hardware.org/?probe=e4c2e737f7) | Jan 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [23d04579d4](https://linux-hardware.org/?probe=23d04579d4) | Jan 29, 2023 |
| ASRock        | Z77M                        | Desktop     | [83a27ed2b5](https://linux-hardware.org/?probe=83a27ed2b5) | Jan 29, 2023 |
| ASRock        | G41M-S3                     | Desktop     | [2196343afa](https://linux-hardware.org/?probe=2196343afa) | Jan 29, 2023 |
| ASUSTek       | P7P55D LE                   | Desktop     | [943a02b7e9](https://linux-hardware.org/?probe=943a02b7e9) | Jan 29, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [c52b5b3357](https://linux-hardware.org/?probe=c52b5b3357) | Jan 29, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [e768563b42](https://linux-hardware.org/?probe=e768563b42) | Jan 29, 2023 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [93e0f40842](https://linux-hardware.org/?probe=93e0f40842) | Jan 29, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [017467452c](https://linux-hardware.org/?probe=017467452c) | Jan 29, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [2fb747792d](https://linux-hardware.org/?probe=2fb747792d) | Jan 29, 2023 |
| ASUSTek       | X550MJ                      | Notebook    | [51fd1f6c24](https://linux-hardware.org/?probe=51fd1f6c24) | Jan 28, 2023 |
| Unknown       | X79                         | Desktop     | [164508bcb4](https://linux-hardware.org/?probe=164508bcb4) | Jan 28, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [8492e549e2](https://linux-hardware.org/?probe=8492e549e2) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B460-G GAMING     | Desktop     | [836e9a9809](https://linux-hardware.org/?probe=836e9a9809) | Jan 28, 2023 |
| Acer          | Aspire TC-705               | Desktop     | [be48644835](https://linux-hardware.org/?probe=be48644835) | Jan 27, 2023 |
| ASUSTek       | M2N-MX                      | Desktop     | [0920c10a0e](https://linux-hardware.org/?probe=0920c10a0e) | Jan 27, 2023 |
| Gigabyte      | B85M-D3H-A                  | Desktop     | [8289da39ca](https://linux-hardware.org/?probe=8289da39ca) | Jan 27, 2023 |
| ASUSTek       | N56DP                       | Notebook    | [a746d3fd78](https://linux-hardware.org/?probe=a746d3fd78) | Jan 27, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [547e171057](https://linux-hardware.org/?probe=547e171057) | Jan 27, 2023 |
| ASUSTek       | N56VJ                       | Notebook    | [6ad6470149](https://linux-hardware.org/?probe=6ad6470149) | Jan 27, 2023 |
| Acer          | Aspire 5532                 | Notebook    | [88e8887c6c](https://linux-hardware.org/?probe=88e8887c6c) | Jan 27, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [7ce2ff0443](https://linux-hardware.org/?probe=7ce2ff0443) | Jan 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [acbaa4516c](https://linux-hardware.org/?probe=acbaa4516c) | Jan 27, 2023 |
| Clevo         | M770SUA                     | Notebook    | [3a19bae169](https://linux-hardware.org/?probe=3a19bae169) | Jan 27, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [ecd1e46811](https://linux-hardware.org/?probe=ecd1e46811) | Jan 27, 2023 |
| Lenovo        | G480 20156                  | Notebook    | [9e09139dbc](https://linux-hardware.org/?probe=9e09139dbc) | Jan 26, 2023 |
| ASUSTek       | 1201N                       | Notebook    | [ddc52a086f](https://linux-hardware.org/?probe=ddc52a086f) | Jan 26, 2023 |
| MSI           | 770-C45                     | Desktop     | [3da3ee46c2](https://linux-hardware.org/?probe=3da3ee46c2) | Jan 26, 2023 |
| Notebook      | P15SM-A/SM1-A               | Notebook    | [7f70263934](https://linux-hardware.org/?probe=7f70263934) | Jan 26, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [02dffce8d7](https://linux-hardware.org/?probe=02dffce8d7) | Jan 26, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [1033fae7e9](https://linux-hardware.org/?probe=1033fae7e9) | Jan 26, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6290f61a46](https://linux-hardware.org/?probe=6290f61a46) | Jan 26, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [e9f4894d6d](https://linux-hardware.org/?probe=e9f4894d6d) | Jan 26, 2023 |
| Acer          | Nitro AN517-51              | Notebook    | [8c568dd8e5](https://linux-hardware.org/?probe=8c568dd8e5) | Jan 26, 2023 |
| ASUSTek       | P7H55-M                     | Desktop     | [34c55ab8ae](https://linux-hardware.org/?probe=34c55ab8ae) | Jan 26, 2023 |
| iRU           | v1.0                        | Desktop     | [5dfa804f74](https://linux-hardware.org/?probe=5dfa804f74) | Jan 26, 2023 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [0b25483160](https://linux-hardware.org/?probe=0b25483160) | Jan 26, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [ee7b9f5fd0](https://linux-hardware.org/?probe=ee7b9f5fd0) | Jan 26, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [883b4a1c39](https://linux-hardware.org/?probe=883b4a1c39) | Jan 26, 2023 |
| MSI           | 770-C45                     | Desktop     | [42ffd24c35](https://linux-hardware.org/?probe=42ffd24c35) | Jan 25, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [ee6e7a2924](https://linux-hardware.org/?probe=ee6e7a2924) | Jan 25, 2023 |
| Lenovo        | V310-15IKB 80T3             | Notebook    | [fe11977488](https://linux-hardware.org/?probe=fe11977488) | Jan 25, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [c2867457c2](https://linux-hardware.org/?probe=c2867457c2) | Jan 25, 2023 |
| MSI           | 770-C45                     | Desktop     | [1991e96ff2](https://linux-hardware.org/?probe=1991e96ff2) | Jan 25, 2023 |
| Lenovo        | V310-15IKB 80T3             | Notebook    | [d56d0b1732](https://linux-hardware.org/?probe=d56d0b1732) | Jan 25, 2023 |
| Acer          | Extensa 2540                | Notebook    | [af5b1ea485](https://linux-hardware.org/?probe=af5b1ea485) | Jan 25, 2023 |
| ASRock        | H310CM-DVS                  | Desktop     | [41b1ad4545](https://linux-hardware.org/?probe=41b1ad4545) | Jan 25, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [8a7a7f6b72](https://linux-hardware.org/?probe=8a7a7f6b72) | Jan 25, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [a9dace6356](https://linux-hardware.org/?probe=a9dace6356) | Jan 24, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [e7afbd79e9](https://linux-hardware.org/?probe=e7afbd79e9) | Jan 24, 2023 |
| ZoomSmart     | A1002                       | Tablet      | [9bfc68ab23](https://linux-hardware.org/?probe=9bfc68ab23) | Jan 24, 2023 |
| HIPER Tech... | HIPER WORKBOOK              | Notebook    | [3b1ce8fc77](https://linux-hardware.org/?probe=3b1ce8fc77) | Jan 24, 2023 |
| Alienware     | 18                          | Notebook    | [982870ed1f](https://linux-hardware.org/?probe=982870ed1f) | Jan 24, 2023 |
| Alienware     | 18                          | Notebook    | [afe83f1946](https://linux-hardware.org/?probe=afe83f1946) | Jan 24, 2023 |
| Gigabyte      | B450M S2H V2                | Desktop     | [e8e7a44a2a](https://linux-hardware.org/?probe=e8e7a44a2a) | Jan 24, 2023 |
| Biostar       | G41-M7                      | Desktop     | [3f66a61637](https://linux-hardware.org/?probe=3f66a61637) | Jan 24, 2023 |
| Pegatron      | IPPPV-D3G                   | Desktop     | [770e25fefd](https://linux-hardware.org/?probe=770e25fefd) | Jan 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [e2d597c046](https://linux-hardware.org/?probe=e2d597c046) | Jan 24, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [416a11089a](https://linux-hardware.org/?probe=416a11089a) | Jan 23, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [0a7ef9990f](https://linux-hardware.org/?probe=0a7ef9990f) | Jan 23, 2023 |
| Acer          | Extensa 5630                | Notebook    | [ae62db30e8](https://linux-hardware.org/?probe=ae62db30e8) | Jan 23, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [257f3b320c](https://linux-hardware.org/?probe=257f3b320c) | Jan 23, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [10fa3eeed2](https://linux-hardware.org/?probe=10fa3eeed2) | Jan 23, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [6d55940af7](https://linux-hardware.org/?probe=6d55940af7) | Jan 23, 2023 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [18fdd7a490](https://linux-hardware.org/?probe=18fdd7a490) | Jan 23, 2023 |
| Gigabyte      | B75M-HD3                    | Desktop     | [77d58eb890](https://linux-hardware.org/?probe=77d58eb890) | Jan 23, 2023 |
| Samsung       | N148P/N208P/N218P/NB28P     | Notebook    | [f665dc3839](https://linux-hardware.org/?probe=f665dc3839) | Jan 23, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [37f26b2f10](https://linux-hardware.org/?probe=37f26b2f10) | Jan 23, 2023 |
| ASUSTek       | Z97-C                       | Desktop     | [3a89f39a8f](https://linux-hardware.org/?probe=3a89f39a8f) | Jan 23, 2023 |
| Samsung       | NC10                        | Notebook    | [6bd13301d9](https://linux-hardware.org/?probe=6bd13301d9) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [b1ced07f7b](https://linux-hardware.org/?probe=b1ced07f7b) | Jan 22, 2023 |
| HP            | ProBook 5330m               | Notebook    | [989327864b](https://linux-hardware.org/?probe=989327864b) | Jan 22, 2023 |
| ASUSTek       | N56VJ                       | Notebook    | [167dae47d7](https://linux-hardware.org/?probe=167dae47d7) | Jan 22, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [0e1605a304](https://linux-hardware.org/?probe=0e1605a304) | Jan 22, 2023 |
| MSI           | CR500                       | Notebook    | [4aaddddd7f](https://linux-hardware.org/?probe=4aaddddd7f) | Jan 22, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [bd85a7e96e](https://linux-hardware.org/?probe=bd85a7e96e) | Jan 22, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [ecfd1795a0](https://linux-hardware.org/?probe=ecfd1795a0) | Jan 22, 2023 |
| ASRock        | B360 Pro4                   | Desktop     | [9cd508a59c](https://linux-hardware.org/?probe=9cd508a59c) | Jan 22, 2023 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [a0b3d87534](https://linux-hardware.org/?probe=a0b3d87534) | Jan 22, 2023 |
| Huanan        | H97-ZD3 V2.0                | Desktop     | [afb82fa3cf](https://linux-hardware.org/?probe=afb82fa3cf) | Jan 22, 2023 |
| Dell          | Vostro 3460                 | Notebook    | [569626e023](https://linux-hardware.org/?probe=569626e023) | Jan 22, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [c861b7e450](https://linux-hardware.org/?probe=c861b7e450) | Jan 22, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [0bf19053f1](https://linux-hardware.org/?probe=0bf19053f1) | Jan 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7d63d494c6](https://linux-hardware.org/?probe=7d63d494c6) | Jan 21, 2023 |
| Samsung       | RV408/RV508                 | Notebook    | [0d5c4881c1](https://linux-hardware.org/?probe=0d5c4881c1) | Jan 21, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [9672c4222a](https://linux-hardware.org/?probe=9672c4222a) | Jan 21, 2023 |
| ASUSTek       | P7H55-M                     | Desktop     | [18efa12cb2](https://linux-hardware.org/?probe=18efa12cb2) | Jan 21, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [df4c3bb4d2](https://linux-hardware.org/?probe=df4c3bb4d2) | Jan 21, 2023 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [3f270588f4](https://linux-hardware.org/?probe=3f270588f4) | Jan 21, 2023 |
| ASRock        | 880GMH/U3S3                 | Desktop     | [f2dff18301](https://linux-hardware.org/?probe=f2dff18301) | Jan 21, 2023 |
| Toshiba       | Satellite P200              | Notebook    | [cdc37dfe5e](https://linux-hardware.org/?probe=cdc37dfe5e) | Jan 20, 2023 |
| Sony          | VGN-FJ3SR_B                 | Notebook    | [4dc8b8d09d](https://linux-hardware.org/?probe=4dc8b8d09d) | Jan 20, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [712d12e3e9](https://linux-hardware.org/?probe=712d12e3e9) | Jan 20, 2023 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [b3df4a1dfa](https://linux-hardware.org/?probe=b3df4a1dfa) | Jan 20, 2023 |
| Lenovo        | B450                        | Notebook    | [96b87672bf](https://linux-hardware.org/?probe=96b87672bf) | Jan 20, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [459b2e28d0](https://linux-hardware.org/?probe=459b2e28d0) | Jan 20, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [4ebd222ef1](https://linux-hardware.org/?probe=4ebd222ef1) | Jan 20, 2023 |
| ECS           | G41T-M7                     | Desktop     | [e6be57e3c3](https://linux-hardware.org/?probe=e6be57e3c3) | Jan 20, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [9abd51692e](https://linux-hardware.org/?probe=9abd51692e) | Jan 20, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [f44f319e21](https://linux-hardware.org/?probe=f44f319e21) | Jan 20, 2023 |
| Huanan        | X99-F8D V2.4                | Desktop     | [26bc61b381](https://linux-hardware.org/?probe=26bc61b381) | Jan 19, 2023 |
| AZW           | U59                         | Desktop     | [6621409d8c](https://linux-hardware.org/?probe=6621409d8c) | Jan 19, 2023 |
| Biostar       | A780LB                      | Desktop     | [ffce251f42](https://linux-hardware.org/?probe=ffce251f42) | Jan 19, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | Desktop     | [348a5d1848](https://linux-hardware.org/?probe=348a5d1848) | Jan 19, 2023 |
| Lenovo        | G70-80 80FF                 | Notebook    | [1ce03f27f3](https://linux-hardware.org/?probe=1ce03f27f3) | Jan 19, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [cfe663eeb9](https://linux-hardware.org/?probe=cfe663eeb9) | Jan 19, 2023 |
| ASUSTek       | P4P800                      | Desktop     | [f37bee349c](https://linux-hardware.org/?probe=f37bee349c) | Jan 18, 2023 |
| Intel         | DG41MJ AAE54659-206         | Desktop     | [98a0ca82de](https://linux-hardware.org/?probe=98a0ca82de) | Jan 18, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [42bf8b9a0d](https://linux-hardware.org/?probe=42bf8b9a0d) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [82eea2cc7b](https://linux-hardware.org/?probe=82eea2cc7b) | Jan 18, 2023 |
| Toshiba       | Satellite Pro C660          | Notebook    | [02a6db2951](https://linux-hardware.org/?probe=02a6db2951) | Jan 18, 2023 |
| Lenovo        | ThinkCentre M57e 6305B2U    | Desktop     | [fbd4306314](https://linux-hardware.org/?probe=fbd4306314) | Jan 18, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [a42e9dbc36](https://linux-hardware.org/?probe=a42e9dbc36) | Jan 18, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [d4147630a1](https://linux-hardware.org/?probe=d4147630a1) | Jan 18, 2023 |
| Toshiba       | Satellite Pro C660          | Notebook    | [a9de8742d5](https://linux-hardware.org/?probe=a9de8742d5) | Jan 17, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [ac58bc440d](https://linux-hardware.org/?probe=ac58bc440d) | Jan 17, 2023 |
| ASRock        | H410M-HVS                   | Desktop     | [2024f1ae76](https://linux-hardware.org/?probe=2024f1ae76) | Jan 17, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b01089cba7](https://linux-hardware.org/?probe=b01089cba7) | Jan 17, 2023 |
| Biostar       | A780LB                      | Desktop     | [fe4d79e9f8](https://linux-hardware.org/?probe=fe4d79e9f8) | Jan 17, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [bffcece8fb](https://linux-hardware.org/?probe=bffcece8fb) | Jan 17, 2023 |
| HP            | Notebook                    | Notebook    | [a998060574](https://linux-hardware.org/?probe=a998060574) | Jan 17, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [bdfe91e3c9](https://linux-hardware.org/?probe=bdfe91e3c9) | Jan 17, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [4507d2f32d](https://linux-hardware.org/?probe=4507d2f32d) | Jan 17, 2023 |
| ASUSTek       | P12R-E Series 60SB0A90-S... | Server      | [f4bf235ea8](https://linux-hardware.org/?probe=f4bf235ea8) | Jan 17, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [e3638a2110](https://linux-hardware.org/?probe=e3638a2110) | Jan 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [df0f33ee66](https://linux-hardware.org/?probe=df0f33ee66) | Jan 16, 2023 |
| Intel         | X99                         | Desktop     | [f966e7aa92](https://linux-hardware.org/?probe=f966e7aa92) | Jan 16, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [37891c1ea9](https://linux-hardware.org/?probe=37891c1ea9) | Jan 16, 2023 |
| Huanan        | H97-ZD3 V2.0                | Desktop     | [aececc6971](https://linux-hardware.org/?probe=aececc6971) | Jan 16, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [363f8daa52](https://linux-hardware.org/?probe=363f8daa52) | Jan 16, 2023 |
| MSI           | 970A-G43                    | Desktop     | [f15370df26](https://linux-hardware.org/?probe=f15370df26) | Jan 16, 2023 |
| ECS           | G41T-M7                     | Desktop     | [51a45a431a](https://linux-hardware.org/?probe=51a45a431a) | Jan 16, 2023 |
| Biostar       | H310MHC2                    | Desktop     | [2ebeb3fa1a](https://linux-hardware.org/?probe=2ebeb3fa1a) | Jan 16, 2023 |
| Unknown       | Unknown                     | Notebook    | [84f591bd6b](https://linux-hardware.org/?probe=84f591bd6b) | Jan 16, 2023 |
| HP            | Notebook                    | Notebook    | [219540f0f7](https://linux-hardware.org/?probe=219540f0f7) | Jan 16, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [c1660ab5a4](https://linux-hardware.org/?probe=c1660ab5a4) | Jan 16, 2023 |
| Biostar       | H310MHC2                    | Desktop     | [939ab29431](https://linux-hardware.org/?probe=939ab29431) | Jan 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2ec1685227](https://linux-hardware.org/?probe=2ec1685227) | Jan 15, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [f51c90cadc](https://linux-hardware.org/?probe=f51c90cadc) | Jan 15, 2023 |
| MSI           | 970A-G43                    | Desktop     | [669512ff6c](https://linux-hardware.org/?probe=669512ff6c) | Jan 15, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [832efe11f1](https://linux-hardware.org/?probe=832efe11f1) | Jan 15, 2023 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [d412197c51](https://linux-hardware.org/?probe=d412197c51) | Jan 15, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [bf4ea0ba42](https://linux-hardware.org/?probe=bf4ea0ba42) | Jan 15, 2023 |
| Kraftway      | ACCORD                      | Notebook    | [63039ae17f](https://linux-hardware.org/?probe=63039ae17f) | Jan 15, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [b5b29198b0](https://linux-hardware.org/?probe=b5b29198b0) | Jan 15, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [fe4b311f78](https://linux-hardware.org/?probe=fe4b311f78) | Jan 15, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [adc92101d7](https://linux-hardware.org/?probe=adc92101d7) | Jan 15, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a65831f165](https://linux-hardware.org/?probe=a65831f165) | Jan 15, 2023 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [af5169b24d](https://linux-hardware.org/?probe=af5169b24d) | Jan 15, 2023 |
| Irbis         | NB264                       | Notebook    | [ed534a1d30](https://linux-hardware.org/?probe=ed534a1d30) | Jan 15, 2023 |
| HP            | 15                          | Notebook    | [6df03629da](https://linux-hardware.org/?probe=6df03629da) | Jan 15, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [282e0e478f](https://linux-hardware.org/?probe=282e0e478f) | Jan 15, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [c59c9570d6](https://linux-hardware.org/?probe=c59c9570d6) | Jan 14, 2023 |
| HP            | 84EE 1100                   | All in one  | [79c81fcfb5](https://linux-hardware.org/?probe=79c81fcfb5) | Jan 14, 2023 |
| MECHREVO      | Jiaolong Series GM5ZG0O     | Notebook    | [17487f7b28](https://linux-hardware.org/?probe=17487f7b28) | Jan 14, 2023 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | Notebook    | [fd3560384c](https://linux-hardware.org/?probe=fd3560384c) | Jan 14, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [6fc2ac2b48](https://linux-hardware.org/?probe=6fc2ac2b48) | Jan 14, 2023 |
| HP            | Mini 110-3700               | Notebook    | [564cb84405](https://linux-hardware.org/?probe=564cb84405) | Jan 14, 2023 |
| MECHREVO      | Jiaolong Series GM5ZG0O     | Notebook    | [a02f812ef3](https://linux-hardware.org/?probe=a02f812ef3) | Jan 14, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [69819d1ce1](https://linux-hardware.org/?probe=69819d1ce1) | Jan 14, 2023 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [64e3a1d972](https://linux-hardware.org/?probe=64e3a1d972) | Jan 14, 2023 |
| Dell          | Inspiron ME051              | Notebook    | [853b489238](https://linux-hardware.org/?probe=853b489238) | Jan 14, 2023 |
| Dell          | Inspiron ME051              | Notebook    | [e806b368b7](https://linux-hardware.org/?probe=e806b368b7) | Jan 14, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [7c5f173e5c](https://linux-hardware.org/?probe=7c5f173e5c) | Jan 13, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [7cde78238f](https://linux-hardware.org/?probe=7cde78238f) | Jan 13, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [ae418043f3](https://linux-hardware.org/?probe=ae418043f3) | Jan 13, 2023 |
| HP            | Notebook                    | Notebook    | [3fc38fa55e](https://linux-hardware.org/?probe=3fc38fa55e) | Jan 13, 2023 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [19be6bae3d](https://linux-hardware.org/?probe=19be6bae3d) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [9ebcc90bcf](https://linux-hardware.org/?probe=9ebcc90bcf) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [71f6d9b711](https://linux-hardware.org/?probe=71f6d9b711) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c551a35ec7](https://linux-hardware.org/?probe=c551a35ec7) | Jan 12, 2023 |
| Acer          | Aspire ES1-331              | Notebook    | [970c4e185f](https://linux-hardware.org/?probe=970c4e185f) | Jan 12, 2023 |
| Acer          | Aspire A315-41G             | Notebook    | [2bfe8a0134](https://linux-hardware.org/?probe=2bfe8a0134) | Jan 12, 2023 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [feee0755d0](https://linux-hardware.org/?probe=feee0755d0) | Jan 12, 2023 |
| ASUSTek       | TP401CA                     | Convertible | [781a6d0157](https://linux-hardware.org/?probe=781a6d0157) | Jan 11, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [5b24178097](https://linux-hardware.org/?probe=5b24178097) | Jan 11, 2023 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [ae85db39c6](https://linux-hardware.org/?probe=ae85db39c6) | Jan 11, 2023 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [5c4331e8b9](https://linux-hardware.org/?probe=5c4331e8b9) | Jan 11, 2023 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [e9a8dfc18e](https://linux-hardware.org/?probe=e9a8dfc18e) | Jan 11, 2023 |
| Clevo         | E512xQ/E4129                | Notebook    | [6c78caccf5](https://linux-hardware.org/?probe=6c78caccf5) | Jan 11, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [9d614553aa](https://linux-hardware.org/?probe=9d614553aa) | Jan 11, 2023 |
| MSI           | GP60 2OD                    | Notebook    | [dbd191a73b](https://linux-hardware.org/?probe=dbd191a73b) | Jan 11, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [8d567b585a](https://linux-hardware.org/?probe=8d567b585a) | Jan 10, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [c4de77365a](https://linux-hardware.org/?probe=c4de77365a) | Jan 10, 2023 |
| Positivo B... | VJFE52F11X-B0611H           | Notebook    | [91caa09e7b](https://linux-hardware.org/?probe=91caa09e7b) | Jan 10, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [87c8f3902d](https://linux-hardware.org/?probe=87c8f3902d) | Jan 10, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [77ecead5ed](https://linux-hardware.org/?probe=77ecead5ed) | Jan 09, 2023 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [d9f3023575](https://linux-hardware.org/?probe=d9f3023575) | Jan 09, 2023 |
| Samsung       | RV420/RV520/RV720           | Notebook    | [c0697ead47](https://linux-hardware.org/?probe=c0697ead47) | Jan 09, 2023 |
| Intel         | DP43BF AAE78171-302         | Desktop     | [ef4b23a73d](https://linux-hardware.org/?probe=ef4b23a73d) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2f03fd41c1](https://linux-hardware.org/?probe=2f03fd41c1) | Jan 09, 2023 |
| ASUSTek       | K54L                        | Notebook    | [88b71478e6](https://linux-hardware.org/?probe=88b71478e6) | Jan 09, 2023 |
| Intel         | DP43BF AAE78171-302         | Desktop     | [2a22078fe1](https://linux-hardware.org/?probe=2a22078fe1) | Jan 09, 2023 |
| ASUSTek       | K61IC                       | Notebook    | [c593968311](https://linux-hardware.org/?probe=c593968311) | Jan 09, 2023 |
| MSI           | GV72 8RD                    | Notebook    | [5fa5d4ef58](https://linux-hardware.org/?probe=5fa5d4ef58) | Jan 09, 2023 |
| Acer          | TravelMate P278-M           | Notebook    | [6b2be0a8cc](https://linux-hardware.org/?probe=6b2be0a8cc) | Jan 09, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [71bd754745](https://linux-hardware.org/?probe=71bd754745) | Jan 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [505cec778a](https://linux-hardware.org/?probe=505cec778a) | Jan 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9924742c7d](https://linux-hardware.org/?probe=9924742c7d) | Jan 08, 2023 |
| ASUSTek       | M3400WUA                    | All in one  | [25ba18f752](https://linux-hardware.org/?probe=25ba18f752) | Jan 08, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [51f731b0f4](https://linux-hardware.org/?probe=51f731b0f4) | Jan 08, 2023 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [5b64e74a17](https://linux-hardware.org/?probe=5b64e74a17) | Jan 08, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [49f4c2fbc8](https://linux-hardware.org/?probe=49f4c2fbc8) | Jan 08, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [e5d4ce1aa7](https://linux-hardware.org/?probe=e5d4ce1aa7) | Jan 08, 2023 |
| Dell          | Latitude 5490               | Notebook    | [8fd07b1457](https://linux-hardware.org/?probe=8fd07b1457) | Jan 08, 2023 |
| ASUSTek       | 1003HAG                     | Notebook    | [0b411dbd38](https://linux-hardware.org/?probe=0b411dbd38) | Jan 08, 2023 |
| Lenovo        | B590 20208                  | Notebook    | [e082e7aece](https://linux-hardware.org/?probe=e082e7aece) | Jan 07, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [93957e7a70](https://linux-hardware.org/?probe=93957e7a70) | Jan 07, 2023 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [b4bf97514d](https://linux-hardware.org/?probe=b4bf97514d) | Jan 07, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [9193043004](https://linux-hardware.org/?probe=9193043004) | Jan 07, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [a6d1d6523b](https://linux-hardware.org/?probe=a6d1d6523b) | Jan 07, 2023 |
| Lenovo        | 0x36C4                      | All in one  | [cb6d0ac822](https://linux-hardware.org/?probe=cb6d0ac822) | Jan 07, 2023 |
| ASUSTek       | 1003HAG                     | Notebook    | [eb8e81a088](https://linux-hardware.org/?probe=eb8e81a088) | Jan 07, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [57ec88a87b](https://linux-hardware.org/?probe=57ec88a87b) | Jan 07, 2023 |
| MB            | A320-SF110                  | Desktop     | [d23ec63d82](https://linux-hardware.org/?probe=d23ec63d82) | Jan 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6893b29920](https://linux-hardware.org/?probe=6893b29920) | Jan 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [7f2254139c](https://linux-hardware.org/?probe=7f2254139c) | Jan 07, 2023 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [a9288e85f6](https://linux-hardware.org/?probe=a9288e85f6) | Jan 06, 2023 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [633f31b57e](https://linux-hardware.org/?probe=633f31b57e) | Jan 06, 2023 |
| Gigabyte      | GA-A75M-DS2                 | Desktop     | [843dbca31d](https://linux-hardware.org/?probe=843dbca31d) | Jan 06, 2023 |
| MB            | A320-SF110                  | Desktop     | [5b690cf226](https://linux-hardware.org/?probe=5b690cf226) | Jan 06, 2023 |
| Huanan        | X99-F8 NALEX, NALEX         | Desktop     | [e59b16e379](https://linux-hardware.org/?probe=e59b16e379) | Jan 06, 2023 |
| ASRock        | A320D4-P1                   | Desktop     | [b6a61f9d2d](https://linux-hardware.org/?probe=b6a61f9d2d) | Jan 06, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [7b61bf12d0](https://linux-hardware.org/?probe=7b61bf12d0) | Jan 06, 2023 |
| ASRock        | D1800M                      | Desktop     | [f70a4786d7](https://linux-hardware.org/?probe=f70a4786d7) | Jan 06, 2023 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [e94f2584b0](https://linux-hardware.org/?probe=e94f2584b0) | Jan 06, 2023 |
| HP            | Compaq 515                  | Notebook    | [6cc60c3d13](https://linux-hardware.org/?probe=6cc60c3d13) | Jan 06, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [1b36fc58ae](https://linux-hardware.org/?probe=1b36fc58ae) | Jan 05, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [bf8c10bdca](https://linux-hardware.org/?probe=bf8c10bdca) | Jan 05, 2023 |
| MSI           | H61M-P20                    | Desktop     | [f48c04fe8f](https://linux-hardware.org/?probe=f48c04fe8f) | Jan 05, 2023 |
| ASRock        | Z77M                        | Desktop     | [fe6f6a7b05](https://linux-hardware.org/?probe=fe6f6a7b05) | Jan 05, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [729add189b](https://linux-hardware.org/?probe=729add189b) | Jan 05, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c2df57a53f](https://linux-hardware.org/?probe=c2df57a53f) | Jan 05, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [5be962cfea](https://linux-hardware.org/?probe=5be962cfea) | Jan 05, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [e1b3de18e9](https://linux-hardware.org/?probe=e1b3de18e9) | Jan 05, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [e3fd4121a2](https://linux-hardware.org/?probe=e3fd4121a2) | Jan 04, 2023 |
| ASUSTek       | A55BM-PLUS                  | Desktop     | [8601b7f2e9](https://linux-hardware.org/?probe=8601b7f2e9) | Jan 04, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [f4631a1285](https://linux-hardware.org/?probe=f4631a1285) | Jan 04, 2023 |
| ASRock        | H510M-HVS                   | Desktop     | [738739788a](https://linux-hardware.org/?probe=738739788a) | Jan 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [5194029152](https://linux-hardware.org/?probe=5194029152) | Jan 04, 2023 |
| ASUSTek       | N551JM                      | Notebook    | [f6de50a76b](https://linux-hardware.org/?probe=f6de50a76b) | Jan 04, 2023 |
| Maibenben     | PC34 V1.0                   | Desktop     | [0ed25644b7](https://linux-hardware.org/?probe=0ed25644b7) | Jan 04, 2023 |
| Gigabyte      | P35-DS3L                    | Desktop     | [c07ba0a973](https://linux-hardware.org/?probe=c07ba0a973) | Jan 04, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [50315135d2](https://linux-hardware.org/?probe=50315135d2) | Jan 04, 2023 |
| ECS           | G41T-M2                     | Desktop     | [8df8f82fb8](https://linux-hardware.org/?probe=8df8f82fb8) | Jan 04, 2023 |
| MSI           | A320M GRENADE               | Desktop     | [5e6f9a181c](https://linux-hardware.org/?probe=5e6f9a181c) | Jan 04, 2023 |
| MSI           | MS-B0A41                    | Desktop     | [f57c26d714](https://linux-hardware.org/?probe=f57c26d714) | Jan 04, 2023 |
| Lenovo        | H420                        | Desktop     | [0765ceb3e8](https://linux-hardware.org/?probe=0765ceb3e8) | Jan 04, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [c3c074f183](https://linux-hardware.org/?probe=c3c074f183) | Jan 03, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [aa99474aec](https://linux-hardware.org/?probe=aa99474aec) | Jan 03, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [89868317cd](https://linux-hardware.org/?probe=89868317cd) | Jan 03, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [f75b0a7e71](https://linux-hardware.org/?probe=f75b0a7e71) | Jan 03, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [b86543e8cf](https://linux-hardware.org/?probe=b86543e8cf) | Jan 03, 2023 |
| ASUSTek       | N551JM                      | Notebook    | [3ba1d0e689](https://linux-hardware.org/?probe=3ba1d0e689) | Jan 03, 2023 |
| Dell          | Precision M6400             | Notebook    | [8f1b979d06](https://linux-hardware.org/?probe=8f1b979d06) | Jan 03, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [b482fc96ea](https://linux-hardware.org/?probe=b482fc96ea) | Jan 03, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [63a14c970b](https://linux-hardware.org/?probe=63a14c970b) | Jan 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8eef31a350](https://linux-hardware.org/?probe=8eef31a350) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [c8618e40a6](https://linux-hardware.org/?probe=c8618e40a6) | Jan 03, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [ee31a67035](https://linux-hardware.org/?probe=ee31a67035) | Jan 03, 2023 |
| ASRock        | N68-GS4 FX                  | Desktop     | [f55d8b7bc9](https://linux-hardware.org/?probe=f55d8b7bc9) | Jan 03, 2023 |
| Gigabyte      | H470M DS3H                  | Desktop     | [07e46fc5f7](https://linux-hardware.org/?probe=07e46fc5f7) | Jan 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4842e4b3e5](https://linux-hardware.org/?probe=4842e4b3e5) | Jan 03, 2023 |
| Jumper        | EZpad                       | Tablet      | [cfa761d534](https://linux-hardware.org/?probe=cfa761d534) | Jan 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a959b07b66](https://linux-hardware.org/?probe=a959b07b66) | Jan 02, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [3a801b9e90](https://linux-hardware.org/?probe=3a801b9e90) | Jan 01, 2023 |
| Huanan        | X99 F8D V2.2                | Desktop     | [c1818201ce](https://linux-hardware.org/?probe=c1818201ce) | Jan 01, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [33bf029e5f](https://linux-hardware.org/?probe=33bf029e5f) | Jan 01, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [75f2e6fae1](https://linux-hardware.org/?probe=75f2e6fae1) | Dec 31, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2161cbc9a0](https://linux-hardware.org/?probe=2161cbc9a0) | Dec 31, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [0d3ed20685](https://linux-hardware.org/?probe=0d3ed20685) | Dec 31, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [896aeb4e20](https://linux-hardware.org/?probe=896aeb4e20) | Dec 31, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [7b10613c1e](https://linux-hardware.org/?probe=7b10613c1e) | Dec 31, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [92920d8ac2](https://linux-hardware.org/?probe=92920d8ac2) | Dec 31, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [e8b804ddd5](https://linux-hardware.org/?probe=e8b804ddd5) | Dec 31, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | Notebook    | [14b589709d](https://linux-hardware.org/?probe=14b589709d) | Dec 31, 2022 |
| Gigabyte      | H55M-USB3                   | Desktop     | [729e1569a8](https://linux-hardware.org/?probe=729e1569a8) | Dec 30, 2022 |
| MSI           | B360M GAMING PLUS           | Desktop     | [9d4f6afc25](https://linux-hardware.org/?probe=9d4f6afc25) | Dec 30, 2022 |
| HP            | Pavilion g6                 | Notebook    | [6f29ccd86e](https://linux-hardware.org/?probe=6f29ccd86e) | Dec 30, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [b0a607e8d8](https://linux-hardware.org/?probe=b0a607e8d8) | Dec 30, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5710b93654](https://linux-hardware.org/?probe=5710b93654) | Dec 30, 2022 |
| AZW           | U59                         | Desktop     | [290e34b89a](https://linux-hardware.org/?probe=290e34b89a) | Dec 30, 2022 |
| ASRock        | N68-GS4 FX                  | Desktop     | [379552e4d2](https://linux-hardware.org/?probe=379552e4d2) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2d63537d23](https://linux-hardware.org/?probe=2d63537d23) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [41da11b027](https://linux-hardware.org/?probe=41da11b027) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [954fdfcd25](https://linux-hardware.org/?probe=954fdfcd25) | Dec 30, 2022 |
| Prestigio     | PSB141C04CGH                | Notebook    | [591f91b689](https://linux-hardware.org/?probe=591f91b689) | Dec 29, 2022 |
| Gigabyte      | B550 GAMING X               | Desktop     | [6e92b3e37b](https://linux-hardware.org/?probe=6e92b3e37b) | Dec 29, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [83acd419e0](https://linux-hardware.org/?probe=83acd419e0) | Dec 29, 2022 |
| ASUSTek       | H97-PRO                     | Desktop     | [b96b861fd7](https://linux-hardware.org/?probe=b96b861fd7) | Dec 29, 2022 |
| ASUSTek       | K40IN                       | Notebook    | [1b4a2d0604](https://linux-hardware.org/?probe=1b4a2d0604) | Dec 29, 2022 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [2cdb821b42](https://linux-hardware.org/?probe=2cdb821b42) | Dec 29, 2022 |
| Gigabyte      | B360M HD3                   | Desktop     | [556bc61c51](https://linux-hardware.org/?probe=556bc61c51) | Dec 29, 2022 |
| Gigabyte      | B360M HD3                   | Desktop     | [f0ab6f0649](https://linux-hardware.org/?probe=f0ab6f0649) | Dec 29, 2022 |
| Aquarius      | NS685U R11                  | Notebook    | [d99ae12a0c](https://linux-hardware.org/?probe=d99ae12a0c) | Dec 29, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [221e9b9fd6](https://linux-hardware.org/?probe=221e9b9fd6) | Dec 28, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [1afc5015f1](https://linux-hardware.org/?probe=1afc5015f1) | Dec 28, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [91c217e497](https://linux-hardware.org/?probe=91c217e497) | Dec 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e36e85614e](https://linux-hardware.org/?probe=e36e85614e) | Dec 28, 2022 |
| ASUSTek       | M4A785-M                    | Desktop     | [7fb63e4360](https://linux-hardware.org/?probe=7fb63e4360) | Dec 27, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [415c0ff63e](https://linux-hardware.org/?probe=415c0ff63e) | Dec 27, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [3b9dbdb180](https://linux-hardware.org/?probe=3b9dbdb180) | Dec 27, 2022 |
| Toshiba       | Satellite U300              | Notebook    | [88861461c8](https://linux-hardware.org/?probe=88861461c8) | Dec 27, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [1aac1f7eca](https://linux-hardware.org/?probe=1aac1f7eca) | Dec 27, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [1707593d6d](https://linux-hardware.org/?probe=1707593d6d) | Dec 27, 2022 |
| HP            | Compaq Presario CQ50        | Notebook    | [802e160a5a](https://linux-hardware.org/?probe=802e160a5a) | Dec 27, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [2b7f53c989](https://linux-hardware.org/?probe=2b7f53c989) | Dec 27, 2022 |
| ASRock        | H510M-HVS                   | Desktop     | [3733446191](https://linux-hardware.org/?probe=3733446191) | Dec 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [155c738d10](https://linux-hardware.org/?probe=155c738d10) | Dec 27, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [542b5ae2f6](https://linux-hardware.org/?probe=542b5ae2f6) | Dec 27, 2022 |
| HP            | Compaq Mini CQ10-100        | Notebook    | [8b34b357bb](https://linux-hardware.org/?probe=8b34b357bb) | Dec 27, 2022 |
| Gigabyte      | i1520N                      | Notebook    | [4f94938d1b](https://linux-hardware.org/?probe=4f94938d1b) | Dec 27, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [17bd139f0c](https://linux-hardware.org/?probe=17bd139f0c) | Dec 26, 2022 |
| Acer          | Aspire Z1-612               | All in one  | [19582f3331](https://linux-hardware.org/?probe=19582f3331) | Dec 26, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [1ba62f0fab](https://linux-hardware.org/?probe=1ba62f0fab) | Dec 26, 2022 |
| Dell          | G5 5590                     | Notebook    | [43fbc3b36d](https://linux-hardware.org/?probe=43fbc3b36d) | Dec 26, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [f9d83535bd](https://linux-hardware.org/?probe=f9d83535bd) | Dec 26, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [735d3cfda2](https://linux-hardware.org/?probe=735d3cfda2) | Dec 26, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [5d26c7c543](https://linux-hardware.org/?probe=5d26c7c543) | Dec 26, 2022 |
| Acer          | Acadia V1.45                | Notebook    | [2d98a8cef2](https://linux-hardware.org/?probe=2d98a8cef2) | Dec 25, 2022 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [5174af9fdd](https://linux-hardware.org/?probe=5174af9fdd) | Dec 25, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [c702bed39d](https://linux-hardware.org/?probe=c702bed39d) | Dec 25, 2022 |
| Unknown       | Unknown                     | Notebook    | [8f4d031a78](https://linux-hardware.org/?probe=8f4d031a78) | Dec 25, 2022 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [85b55a267a](https://linux-hardware.org/?probe=85b55a267a) | Dec 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [8994b9a877](https://linux-hardware.org/?probe=8994b9a877) | Dec 25, 2022 |
| Pegatron      | C15B                        | Notebook    | [f838b3f22c](https://linux-hardware.org/?probe=f838b3f22c) | Dec 25, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [1571f74238](https://linux-hardware.org/?probe=1571f74238) | Dec 25, 2022 |
| HP            | 0AACh                       | Desktop     | [b83da338ee](https://linux-hardware.org/?probe=b83da338ee) | Dec 25, 2022 |
| ASUSTek       | X551CAP                     | Notebook    | [3442037418](https://linux-hardware.org/?probe=3442037418) | Dec 25, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f48ac4aa81](https://linux-hardware.org/?probe=f48ac4aa81) | Dec 25, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [b98be1b1e7](https://linux-hardware.org/?probe=b98be1b1e7) | Dec 25, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [5368526dc0](https://linux-hardware.org/?probe=5368526dc0) | Dec 25, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [fab270a7bf](https://linux-hardware.org/?probe=fab270a7bf) | Dec 25, 2022 |
| ASRock        | B365M-HDV                   | Desktop     | [84ea64b29c](https://linux-hardware.org/?probe=84ea64b29c) | Dec 24, 2022 |
| ASRock        | B365M-HDV                   | Desktop     | [407f76f02f](https://linux-hardware.org/?probe=407f76f02f) | Dec 24, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [bb8b44cf69](https://linux-hardware.org/?probe=bb8b44cf69) | Dec 24, 2022 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [70312467b7](https://linux-hardware.org/?probe=70312467b7) | Dec 24, 2022 |
| Gigabyte      | B660M D2H DDR4              | Desktop     | [c34803fb1e](https://linux-hardware.org/?probe=c34803fb1e) | Dec 24, 2022 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [6f60f1b6da](https://linux-hardware.org/?probe=6f60f1b6da) | Dec 24, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [c107bb3a14](https://linux-hardware.org/?probe=c107bb3a14) | Dec 24, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [cf3882b3f7](https://linux-hardware.org/?probe=cf3882b3f7) | Dec 24, 2022 |
| Gigabyte      | H55M-S2H                    | Desktop     | [7cecfa756a](https://linux-hardware.org/?probe=7cecfa756a) | Dec 24, 2022 |
| HP            | 0AACh                       | Desktop     | [4a7840e1cf](https://linux-hardware.org/?probe=4a7840e1cf) | Dec 24, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [40c2593694](https://linux-hardware.org/?probe=40c2593694) | Dec 24, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [81febc2905](https://linux-hardware.org/?probe=81febc2905) | Dec 23, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [0d45265efc](https://linux-hardware.org/?probe=0d45265efc) | Dec 23, 2022 |
| Unknown       | 865GV-ICH5                  | Desktop     | [fe2ef2ef31](https://linux-hardware.org/?probe=fe2ef2ef31) | Dec 23, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [73dc1109eb](https://linux-hardware.org/?probe=73dc1109eb) | Dec 23, 2022 |
| Intel         | ChiefRiver                  | Notebook    | [a23ea2e43e](https://linux-hardware.org/?probe=a23ea2e43e) | Dec 23, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [b53beddded](https://linux-hardware.org/?probe=b53beddded) | Dec 23, 2022 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [daf1310bfa](https://linux-hardware.org/?probe=daf1310bfa) | Dec 23, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [672c320794](https://linux-hardware.org/?probe=672c320794) | Dec 22, 2022 |
| HP            | G62                         | Notebook    | [00b47da7dc](https://linux-hardware.org/?probe=00b47da7dc) | Dec 22, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [1a8f388366](https://linux-hardware.org/?probe=1a8f388366) | Dec 22, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [8981102ebe](https://linux-hardware.org/?probe=8981102ebe) | Dec 22, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ae98ccd9c2](https://linux-hardware.org/?probe=ae98ccd9c2) | Dec 22, 2022 |
| Unknown       | 865GV-ICH5                  | Desktop     | [f42b7383f4](https://linux-hardware.org/?probe=f42b7383f4) | Dec 22, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [2683bf55bf](https://linux-hardware.org/?probe=2683bf55bf) | Dec 22, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [c485d688ad](https://linux-hardware.org/?probe=c485d688ad) | Dec 22, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [4fc8630d91](https://linux-hardware.org/?probe=4fc8630d91) | Dec 22, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [ad317dc4fd](https://linux-hardware.org/?probe=ad317dc4fd) | Dec 22, 2022 |
| ASUSTek       | P5K PRO                     | Desktop     | [4088ff40e3](https://linux-hardware.org/?probe=4088ff40e3) | Dec 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [10a98289bb](https://linux-hardware.org/?probe=10a98289bb) | Dec 21, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [b7311f5a21](https://linux-hardware.org/?probe=b7311f5a21) | Dec 21, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [c39538e70e](https://linux-hardware.org/?probe=c39538e70e) | Dec 21, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [afac6a5bfa](https://linux-hardware.org/?probe=afac6a5bfa) | Dec 21, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [d6e55e247a](https://linux-hardware.org/?probe=d6e55e247a) | Dec 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [cc485cc076](https://linux-hardware.org/?probe=cc485cc076) | Dec 21, 2022 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [e7383e309b](https://linux-hardware.org/?probe=e7383e309b) | Dec 21, 2022 |
| eMachines     | E525                        | Notebook    | [8368666118](https://linux-hardware.org/?probe=8368666118) | Dec 21, 2022 |
| ASUSTek       | X555SJ                      | Notebook    | [c580c82fe2](https://linux-hardware.org/?probe=c580c82fe2) | Dec 21, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [ba8b12c87e](https://linux-hardware.org/?probe=ba8b12c87e) | Dec 21, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c56023ff15](https://linux-hardware.org/?probe=c56023ff15) | Dec 21, 2022 |
| Pegatron      | A17                         | Notebook    | [f40a055eac](https://linux-hardware.org/?probe=f40a055eac) | Dec 21, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [d27a2a4e0f](https://linux-hardware.org/?probe=d27a2a4e0f) | Dec 20, 2022 |
| Gigabyte      | EP43-S3L                    | Desktop     | [8a24afa21d](https://linux-hardware.org/?probe=8a24afa21d) | Dec 20, 2022 |
| Intel         | X99                         | Desktop     | [ce9b83b781](https://linux-hardware.org/?probe=ce9b83b781) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [e7cfce65f6](https://linux-hardware.org/?probe=e7cfce65f6) | Dec 20, 2022 |
| ASUSTek       | P5QL PRO                    | Desktop     | [44d3238797](https://linux-hardware.org/?probe=44d3238797) | Dec 20, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [a39b8f54af](https://linux-hardware.org/?probe=a39b8f54af) | Dec 20, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [8777d682b0](https://linux-hardware.org/?probe=8777d682b0) | Dec 20, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [7c854ad5e0](https://linux-hardware.org/?probe=7c854ad5e0) | Dec 20, 2022 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [f82010222c](https://linux-hardware.org/?probe=f82010222c) | Dec 20, 2022 |
| ASRock        | Z77M                        | Desktop     | [33c2afa3e0](https://linux-hardware.org/?probe=33c2afa3e0) | Dec 20, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [de20614d06](https://linux-hardware.org/?probe=de20614d06) | Dec 19, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [66e45d9a82](https://linux-hardware.org/?probe=66e45d9a82) | Dec 19, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [90ea21bd4a](https://linux-hardware.org/?probe=90ea21bd4a) | Dec 19, 2022 |
| ASUSTek       | P7P55D EVO                  | Desktop     | [c8f2df83aa](https://linux-hardware.org/?probe=c8f2df83aa) | Dec 19, 2022 |
| ASRock        | P67 Pro3 SE                 | Desktop     | [5a59282fea](https://linux-hardware.org/?probe=5a59282fea) | Dec 19, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [aa5228e9b8](https://linux-hardware.org/?probe=aa5228e9b8) | Dec 19, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [7f8c2370d4](https://linux-hardware.org/?probe=7f8c2370d4) | Dec 19, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [faf7ad4c29](https://linux-hardware.org/?probe=faf7ad4c29) | Dec 19, 2022 |
| MSI           | X460/X460DX                 | Notebook    | [6fff37a8a5](https://linux-hardware.org/?probe=6fff37a8a5) | Dec 18, 2022 |
| MSI           | X460/X460DX                 | Notebook    | [71ca32ac12](https://linux-hardware.org/?probe=71ca32ac12) | Dec 18, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [c793cb6f38](https://linux-hardware.org/?probe=c793cb6f38) | Dec 18, 2022 |
| Acer          | Nitro AN515-56              | Notebook    | [cac9892365](https://linux-hardware.org/?probe=cac9892365) | Dec 18, 2022 |
| Gigabyte      | GA-K8NE                     | Desktop     | [64adeb3e60](https://linux-hardware.org/?probe=64adeb3e60) | Dec 18, 2022 |
| eMachines     | E525                        | Notebook    | [2a0aeb50bf](https://linux-hardware.org/?probe=2a0aeb50bf) | Dec 18, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [626b750c51](https://linux-hardware.org/?probe=626b750c51) | Dec 18, 2022 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [320ef20ffa](https://linux-hardware.org/?probe=320ef20ffa) | Dec 18, 2022 |
| Acer          | AO533                       | Notebook    | [1639951fe5](https://linux-hardware.org/?probe=1639951fe5) | Dec 18, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [7e864dc271](https://linux-hardware.org/?probe=7e864dc271) | Dec 18, 2022 |
| Gigabyte      | P41T-D3P                    | Desktop     | [20f90ee21e](https://linux-hardware.org/?probe=20f90ee21e) | Dec 18, 2022 |
| ASUSTek       | 1201N                       | Notebook    | [214a7002b9](https://linux-hardware.org/?probe=214a7002b9) | Dec 18, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [0dc1961e62](https://linux-hardware.org/?probe=0dc1961e62) | Dec 18, 2022 |
| MSI           | MS-B0A41                    | Desktop     | [3eff37d029](https://linux-hardware.org/?probe=3eff37d029) | Dec 18, 2022 |
| HP            | Pavilion g7                 | Notebook    | [6a1a042504](https://linux-hardware.org/?probe=6a1a042504) | Dec 18, 2022 |
| HP            | Pavilion g7                 | Notebook    | [465a08d81a](https://linux-hardware.org/?probe=465a08d81a) | Dec 18, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [c6cce8ff6d](https://linux-hardware.org/?probe=c6cce8ff6d) | Dec 18, 2022 |
| Gigabyte      | H110N-CF                    | Desktop     | [239dcc2a5c](https://linux-hardware.org/?probe=239dcc2a5c) | Dec 18, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [216bedab36](https://linux-hardware.org/?probe=216bedab36) | Dec 18, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [e889711ed9](https://linux-hardware.org/?probe=e889711ed9) | Dec 17, 2022 |
| Prestigio     | PSB141C04CGH                | Notebook    | [60f02a4cb4](https://linux-hardware.org/?probe=60f02a4cb4) | Dec 17, 2022 |
| ASUSTek       | M2N-XE                      | Desktop     | [5cf5b3eb1b](https://linux-hardware.org/?probe=5cf5b3eb1b) | Dec 17, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [09fc64653e](https://linux-hardware.org/?probe=09fc64653e) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [00cc810cfc](https://linux-hardware.org/?probe=00cc810cfc) | Dec 17, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [74133cd0bd](https://linux-hardware.org/?probe=74133cd0bd) | Dec 17, 2022 |
| ICL           | RAYbook Si1511              | Notebook    | [9994b3ec08](https://linux-hardware.org/?probe=9994b3ec08) | Dec 17, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [c04b0805ad](https://linux-hardware.org/?probe=c04b0805ad) | Dec 17, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [0eb4a7c919](https://linux-hardware.org/?probe=0eb4a7c919) | Dec 17, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [d34f278afd](https://linux-hardware.org/?probe=d34f278afd) | Dec 17, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [f0303dc0a9](https://linux-hardware.org/?probe=f0303dc0a9) | Dec 17, 2022 |
| Acer          | Aspire C22-820              | All in one  | [3e6cfa25b2](https://linux-hardware.org/?probe=3e6cfa25b2) | Dec 17, 2022 |
| Gigabyte      | H81-D3                      | Desktop     | [547126e9e7](https://linux-hardware.org/?probe=547126e9e7) | Dec 17, 2022 |
| Acer          | Aspire ES1-521              | Notebook    | [4f4f04579a](https://linux-hardware.org/?probe=4f4f04579a) | Dec 17, 2022 |
| Maibenben     | MaiBook M                   | Notebook    | [a216b90cac](https://linux-hardware.org/?probe=a216b90cac) | Dec 17, 2022 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [11c0643905](https://linux-hardware.org/?probe=11c0643905) | Dec 16, 2022 |
| Graviton      | DMB-H510-MCA01              | Desktop     | [702f634fc4](https://linux-hardware.org/?probe=702f634fc4) | Dec 16, 2022 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [9d85f624db](https://linux-hardware.org/?probe=9d85f624db) | Dec 16, 2022 |
| Gigabyte      | P75-D3                      | Desktop     | [32b4b4d664](https://linux-hardware.org/?probe=32b4b4d664) | Dec 16, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [116b321e68](https://linux-hardware.org/?probe=116b321e68) | Dec 16, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [a04f7471b9](https://linux-hardware.org/?probe=a04f7471b9) | Dec 16, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [66d31fc2c8](https://linux-hardware.org/?probe=66d31fc2c8) | Dec 16, 2022 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [a959e56dc8](https://linux-hardware.org/?probe=a959e56dc8) | Dec 15, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [0d07341d58](https://linux-hardware.org/?probe=0d07341d58) | Dec 15, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [5f2e420614](https://linux-hardware.org/?probe=5f2e420614) | Dec 15, 2022 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [c25f374572](https://linux-hardware.org/?probe=c25f374572) | Dec 15, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [6367cb9215](https://linux-hardware.org/?probe=6367cb9215) | Dec 15, 2022 |
| ASRock        | A520M Pro4                  | Desktop     | [9a6fcc5f1b](https://linux-hardware.org/?probe=9a6fcc5f1b) | Dec 15, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [766e33e4fb](https://linux-hardware.org/?probe=766e33e4fb) | Dec 15, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [db904895cc](https://linux-hardware.org/?probe=db904895cc) | Dec 15, 2022 |
| Digma         | EVE 11 C421Y ES1067EW       | Notebook    | [458afe13df](https://linux-hardware.org/?probe=458afe13df) | Dec 14, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [902c809015](https://linux-hardware.org/?probe=902c809015) | Dec 14, 2022 |
| ASUSTek       | F2A55-M LE                  | Desktop     | [f4c6e3c225](https://linux-hardware.org/?probe=f4c6e3c225) | Dec 14, 2022 |
| ASUSTek       | F7Z                         | Notebook    | [3c42714822](https://linux-hardware.org/?probe=3c42714822) | Dec 14, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [7040d4353c](https://linux-hardware.org/?probe=7040d4353c) | Dec 14, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [5093772c0f](https://linux-hardware.org/?probe=5093772c0f) | Dec 14, 2022 |
| ASUSTek       | N73SV                       | Notebook    | [7b729a3a7c](https://linux-hardware.org/?probe=7b729a3a7c) | Dec 14, 2022 |
| Intel         | X79v2.72 KD V2.0            | Desktop     | [0e58af2a59](https://linux-hardware.org/?probe=0e58af2a59) | Dec 14, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [1457c2669d](https://linux-hardware.org/?probe=1457c2669d) | Dec 13, 2022 |
| Acer          | Aspire 5720                 | Notebook    | [5940b07034](https://linux-hardware.org/?probe=5940b07034) | Dec 13, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [22431e9b10](https://linux-hardware.org/?probe=22431e9b10) | Dec 13, 2022 |
| ASUSTek       | N73SV                       | Notebook    | [c696bac1dd](https://linux-hardware.org/?probe=c696bac1dd) | Dec 13, 2022 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [0e9eba0773](https://linux-hardware.org/?probe=0e9eba0773) | Dec 13, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [b479704ea5](https://linux-hardware.org/?probe=b479704ea5) | Dec 13, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [d01e578aa0](https://linux-hardware.org/?probe=d01e578aa0) | Dec 13, 2022 |
| Sony          | VPCEJ1L1R                   | Notebook    | [25ab3e0119](https://linux-hardware.org/?probe=25ab3e0119) | Dec 13, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [af674c6b1b](https://linux-hardware.org/?probe=af674c6b1b) | Dec 13, 2022 |
| MSI           | GF65 Thin 10UE              | Notebook    | [ff4ab808c0](https://linux-hardware.org/?probe=ff4ab808c0) | Dec 13, 2022 |
| Clevo         | M7x0K                       | Notebook    | [08ce94ab11](https://linux-hardware.org/?probe=08ce94ab11) | Dec 13, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [dc7d6ae170](https://linux-hardware.org/?probe=dc7d6ae170) | Dec 13, 2022 |
| Intel         | X79v2.72 KD V2.0            | Desktop     | [476f1e7cad](https://linux-hardware.org/?probe=476f1e7cad) | Dec 12, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [8c4853dba7](https://linux-hardware.org/?probe=8c4853dba7) | Dec 12, 2022 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [f09e3c0e19](https://linux-hardware.org/?probe=f09e3c0e19) | Dec 12, 2022 |
| Sony          | SVE1111M1RW                 | Notebook    | [bc29721da9](https://linux-hardware.org/?probe=bc29721da9) | Dec 12, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [5b35ba45a3](https://linux-hardware.org/?probe=5b35ba45a3) | Dec 12, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [8918608744](https://linux-hardware.org/?probe=8918608744) | Dec 12, 2022 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [2e0158ba73](https://linux-hardware.org/?probe=2e0158ba73) | Dec 12, 2022 |
| Gigabyte      | H310M A-CF x.x              | Desktop     | [c6e03bcd07](https://linux-hardware.org/?probe=c6e03bcd07) | Dec 12, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [a096df53ed](https://linux-hardware.org/?probe=a096df53ed) | Dec 12, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [1d93c8b401](https://linux-hardware.org/?probe=1d93c8b401) | Dec 11, 2022 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [4471c4a012](https://linux-hardware.org/?probe=4471c4a012) | Dec 11, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [f803c32eae](https://linux-hardware.org/?probe=f803c32eae) | Dec 11, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [c90a3cb8c2](https://linux-hardware.org/?probe=c90a3cb8c2) | Dec 11, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [e2932e425c](https://linux-hardware.org/?probe=e2932e425c) | Dec 11, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [f24e02511f](https://linux-hardware.org/?probe=f24e02511f) | Dec 11, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [0400a58c53](https://linux-hardware.org/?probe=0400a58c53) | Dec 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f0fa1101ce](https://linux-hardware.org/?probe=f0fa1101ce) | Dec 11, 2022 |
| ECS           | H61H2-M3                    | Desktop     | [dcd96a2b45](https://linux-hardware.org/?probe=dcd96a2b45) | Dec 11, 2022 |
| ECS           | H61H2-M3                    | Desktop     | [9f9fafa75b](https://linux-hardware.org/?probe=9f9fafa75b) | Dec 11, 2022 |
| Samsung       | SQ45/Q70C/P200              | Notebook    | [4a96589cf5](https://linux-hardware.org/?probe=4a96589cf5) | Dec 11, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [f883834ef1](https://linux-hardware.org/?probe=f883834ef1) | Dec 11, 2022 |
| HP            | 8860 A                      | Desktop     | [c039452bd4](https://linux-hardware.org/?probe=c039452bd4) | Dec 11, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [9f72d262ef](https://linux-hardware.org/?probe=9f72d262ef) | Dec 11, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [8bd005fd95](https://linux-hardware.org/?probe=8bd005fd95) | Dec 11, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [aac6da2dfb](https://linux-hardware.org/?probe=aac6da2dfb) | Dec 11, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [4c52e333dd](https://linux-hardware.org/?probe=4c52e333dd) | Dec 10, 2022 |
| ASRock        | H81M-HDS R2.0               | Desktop     | [e3c2a2bc54](https://linux-hardware.org/?probe=e3c2a2bc54) | Dec 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [bb4615bd96](https://linux-hardware.org/?probe=bb4615bd96) | Dec 10, 2022 |
| Intel         | D2500HN AAG81480-500        | Desktop     | [0963fa0173](https://linux-hardware.org/?probe=0963fa0173) | Dec 10, 2022 |
| Supermicro    | X8DT3                       | Server      | [737f9e5af8](https://linux-hardware.org/?probe=737f9e5af8) | Dec 10, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [619a4c2f87](https://linux-hardware.org/?probe=619a4c2f87) | Dec 10, 2022 |
| ASRock        | 760GM-HDV                   | Desktop     | [bbd75ce275](https://linux-hardware.org/?probe=bbd75ce275) | Dec 10, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [4b7783525a](https://linux-hardware.org/?probe=4b7783525a) | Dec 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [941668ad89](https://linux-hardware.org/?probe=941668ad89) | Dec 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [fc07cad186](https://linux-hardware.org/?probe=fc07cad186) | Dec 10, 2022 |
| HP            | 158A                        | Desktop     | [ebcf08f784](https://linux-hardware.org/?probe=ebcf08f784) | Dec 10, 2022 |
| ASRock        | H97 Anniversary             | Desktop     | [3f7aa1b6de](https://linux-hardware.org/?probe=3f7aa1b6de) | Dec 10, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f064a744ba](https://linux-hardware.org/?probe=f064a744ba) | Dec 10, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [c9df3386c5](https://linux-hardware.org/?probe=c9df3386c5) | Dec 10, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [fa13871cf9](https://linux-hardware.org/?probe=fa13871cf9) | Dec 10, 2022 |
| Gigabyte      | H61N-USB3                   | Desktop     | [9a8885a88d](https://linux-hardware.org/?probe=9a8885a88d) | Dec 09, 2022 |
| Lenovo        | 3130 NOK                    | Mini pc     | [02df085bd5](https://linux-hardware.org/?probe=02df085bd5) | Dec 09, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [75f1600dba](https://linux-hardware.org/?probe=75f1600dba) | Dec 09, 2022 |
| MSI           | Modern 15 B12M              | Notebook    | [b5f43a3075](https://linux-hardware.org/?probe=b5f43a3075) | Dec 09, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ed30003f61](https://linux-hardware.org/?probe=ed30003f61) | Dec 09, 2022 |
| Gigabyte      | D425TUD                     | Desktop     | [4d8c330a78](https://linux-hardware.org/?probe=4d8c330a78) | Dec 09, 2022 |
| HP            | 18E7                        | Desktop     | [3ae864582a](https://linux-hardware.org/?probe=3ae864582a) | Dec 09, 2022 |
| Aquarius      | AQB560M                     | Desktop     | [b4bd04a5a0](https://linux-hardware.org/?probe=b4bd04a5a0) | Dec 09, 2022 |
| Aquarius      | AQB560M                     | Desktop     | [56a6a749bb](https://linux-hardware.org/?probe=56a6a749bb) | Dec 09, 2022 |
| Acer          | Aspire C22-820              | All in one  | [1fb0e14b70](https://linux-hardware.org/?probe=1fb0e14b70) | Dec 09, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [05707c88e0](https://linux-hardware.org/?probe=05707c88e0) | Dec 08, 2022 |
| ASUSTek       | UX310UQK                    | Notebook    | [c4a573e93c](https://linux-hardware.org/?probe=c4a573e93c) | Dec 08, 2022 |
| Acer          | Aspire F5-571G              | Notebook    | [dedd56f0fe](https://linux-hardware.org/?probe=dedd56f0fe) | Dec 08, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [969ca94bb7](https://linux-hardware.org/?probe=969ca94bb7) | Dec 08, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [c2ba58af35](https://linux-hardware.org/?probe=c2ba58af35) | Dec 08, 2022 |
| ASUSTek       | K42F                        | Notebook    | [ee90271b2d](https://linux-hardware.org/?probe=ee90271b2d) | Dec 08, 2022 |
| Biostar       | GF8200C M2+                 | Desktop     | [e42ae4deef](https://linux-hardware.org/?probe=e42ae4deef) | Dec 08, 2022 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [4462cb3156](https://linux-hardware.org/?probe=4462cb3156) | Dec 08, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [1b1e1ae174](https://linux-hardware.org/?probe=1b1e1ae174) | Dec 08, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [21c291e1e2](https://linux-hardware.org/?probe=21c291e1e2) | Dec 08, 2022 |
| Huanan        | X99 F8D V2.2                | Desktop     | [d960add854](https://linux-hardware.org/?probe=d960add854) | Dec 08, 2022 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [bedb81f629](https://linux-hardware.org/?probe=bedb81f629) | Dec 08, 2022 |
| Dell          | Inspiron 3721               | Notebook    | [3bfc5892fe](https://linux-hardware.org/?probe=3bfc5892fe) | Dec 08, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c6d0984a2c](https://linux-hardware.org/?probe=c6d0984a2c) | Dec 08, 2022 |
| Aquarius      | AQB560M                     | Desktop     | [3ac41202cf](https://linux-hardware.org/?probe=3ac41202cf) | Dec 08, 2022 |
| ASUSTek       | U24E                        | Notebook    | [e8bdc6be97](https://linux-hardware.org/?probe=e8bdc6be97) | Dec 08, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [0bb6c29bb6](https://linux-hardware.org/?probe=0bb6c29bb6) | Dec 07, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6160229247](https://linux-hardware.org/?probe=6160229247) | Dec 07, 2022 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [eafc4dffd4](https://linux-hardware.org/?probe=eafc4dffd4) | Dec 07, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [ceff27eeef](https://linux-hardware.org/?probe=ceff27eeef) | Dec 07, 2022 |
| Dell          | Inspiron 3137               | Notebook    | [2f74d45567](https://linux-hardware.org/?probe=2f74d45567) | Dec 07, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [fd694a5ddd](https://linux-hardware.org/?probe=fd694a5ddd) | Dec 07, 2022 |
| Pegatron      | C17A                        | Notebook    | [5fc3c61389](https://linux-hardware.org/?probe=5fc3c61389) | Dec 07, 2022 |
| eMachines     | ET1350                      | Desktop     | [2d05a7a068](https://linux-hardware.org/?probe=2d05a7a068) | Dec 07, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [038581b13f](https://linux-hardware.org/?probe=038581b13f) | Dec 07, 2022 |
| ASUSTek       | M2N-XE                      | Desktop     | [663b3c7870](https://linux-hardware.org/?probe=663b3c7870) | Dec 06, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [0613a1c41e](https://linux-hardware.org/?probe=0613a1c41e) | Dec 06, 2022 |
| HP            | Pavilion 15                 | Notebook    | [eb3caff76e](https://linux-hardware.org/?probe=eb3caff76e) | Dec 06, 2022 |
| ASRock        | P67 Pro                     | Desktop     | [74b28c3c76](https://linux-hardware.org/?probe=74b28c3c76) | Dec 06, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [6b5fd6a48c](https://linux-hardware.org/?probe=6b5fd6a48c) | Dec 05, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [afeed5f423](https://linux-hardware.org/?probe=afeed5f423) | Dec 05, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [517e06781a](https://linux-hardware.org/?probe=517e06781a) | Dec 05, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [bd98ec1bcb](https://linux-hardware.org/?probe=bd98ec1bcb) | Dec 05, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [543eb800d7](https://linux-hardware.org/?probe=543eb800d7) | Dec 05, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [c8b886d9bf](https://linux-hardware.org/?probe=c8b886d9bf) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [0301ad14ee](https://linux-hardware.org/?probe=0301ad14ee) | Dec 05, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [26828f578e](https://linux-hardware.org/?probe=26828f578e) | Dec 05, 2022 |
| MSI           | H97 PC Mate                 | Desktop     | [b8081159ab](https://linux-hardware.org/?probe=b8081159ab) | Dec 05, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [44f8fe348a](https://linux-hardware.org/?probe=44f8fe348a) | Dec 05, 2022 |
| Dell          | Vostro 1310                 | Notebook    | [60bdc28f50](https://linux-hardware.org/?probe=60bdc28f50) | Dec 04, 2022 |
| ASUSTek       | F3Sg                        | Notebook    | [f5ae748125](https://linux-hardware.org/?probe=f5ae748125) | Dec 04, 2022 |
| Lenovo        | ThinkPad L420 7854RP1       | Notebook    | [3216e34b2e](https://linux-hardware.org/?probe=3216e34b2e) | Dec 04, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [10dd0b119a](https://linux-hardware.org/?probe=10dd0b119a) | Dec 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [bdf0020add](https://linux-hardware.org/?probe=bdf0020add) | Dec 04, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [f18907cee0](https://linux-hardware.org/?probe=f18907cee0) | Dec 04, 2022 |
| HP            | 2AAC                        | Desktop     | [a6fb7751ed](https://linux-hardware.org/?probe=a6fb7751ed) | Dec 04, 2022 |
| Intel         | DG41CN AAE82429-102         | Desktop     | [8d5cd3253c](https://linux-hardware.org/?probe=8d5cd3253c) | Dec 04, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [d3c99c8d63](https://linux-hardware.org/?probe=d3c99c8d63) | Dec 04, 2022 |
| Intel         | D2500HN AAG34776-404        | Desktop     | [b1ccefe421](https://linux-hardware.org/?probe=b1ccefe421) | Dec 04, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [0218d4ec25](https://linux-hardware.org/?probe=0218d4ec25) | Dec 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [c795306dd2](https://linux-hardware.org/?probe=c795306dd2) | Dec 03, 2022 |
| Gigabyte      | P35-DS3                     | Desktop     | [f4be331a61](https://linux-hardware.org/?probe=f4be331a61) | Dec 03, 2022 |
| Lenovo        | MAHOBAY No DPK              | All in one  | [87db7dbb99](https://linux-hardware.org/?probe=87db7dbb99) | Dec 03, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [ea7168ab4c](https://linux-hardware.org/?probe=ea7168ab4c) | Dec 03, 2022 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [1d881e7756](https://linux-hardware.org/?probe=1d881e7756) | Dec 03, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [c2ee22631f](https://linux-hardware.org/?probe=c2ee22631f) | Dec 03, 2022 |
| ASRock        | K10N78D                     | Desktop     | [7d0d581c7a](https://linux-hardware.org/?probe=7d0d581c7a) | Dec 03, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [91bffab1ae](https://linux-hardware.org/?probe=91bffab1ae) | Dec 03, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [795327c2b7](https://linux-hardware.org/?probe=795327c2b7) | Dec 03, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [f1e82e8a2a](https://linux-hardware.org/?probe=f1e82e8a2a) | Dec 03, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [7bb879efed](https://linux-hardware.org/?probe=7bb879efed) | Dec 03, 2022 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [76ba1ef6f2](https://linux-hardware.org/?probe=76ba1ef6f2) | Dec 03, 2022 |
| MSI           | P67S-C43                    | Desktop     | [9674663124](https://linux-hardware.org/?probe=9674663124) | Dec 03, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [6cb73d5a1c](https://linux-hardware.org/?probe=6cb73d5a1c) | Dec 03, 2022 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [a39dbe7189](https://linux-hardware.org/?probe=a39dbe7189) | Dec 03, 2022 |
| MSI           | GE72 6QC                    | Notebook    | [8411668d4d](https://linux-hardware.org/?probe=8411668d4d) | Dec 02, 2022 |
| Intel         | JSL MRD                     | Desktop     | [1a63097a67](https://linux-hardware.org/?probe=1a63097a67) | Dec 02, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [5c0129ab3f](https://linux-hardware.org/?probe=5c0129ab3f) | Dec 02, 2022 |
| Acer          | Aspire 5951G                | Notebook    | [0b1e900a8c](https://linux-hardware.org/?probe=0b1e900a8c) | Dec 02, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [eaaeeb57fe](https://linux-hardware.org/?probe=eaaeeb57fe) | Dec 02, 2022 |
| HP            | 635                         | Notebook    | [cf79165440](https://linux-hardware.org/?probe=cf79165440) | Dec 02, 2022 |
| Acer          | Aspire V5-572G              | Notebook    | [638e9873a7](https://linux-hardware.org/?probe=638e9873a7) | Dec 02, 2022 |
| Acer          | Aspire V5-572G              | Notebook    | [711acef394](https://linux-hardware.org/?probe=711acef394) | Dec 02, 2022 |
| HP            | 18E7                        | Desktop     | [37c3c7db33](https://linux-hardware.org/?probe=37c3c7db33) | Dec 02, 2022 |
| Samsung       | R410                        | Notebook    | [7c2a18f2cc](https://linux-hardware.org/?probe=7c2a18f2cc) | Dec 01, 2022 |
| 3Q            | TD2500G-P-Q3 A01            | Desktop     | [46626558f6](https://linux-hardware.org/?probe=46626558f6) | Dec 01, 2022 |
| ASUSTek       | AT3IONT-I DELUXE            | Desktop     | [16680c5211](https://linux-hardware.org/?probe=16680c5211) | Dec 01, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [bbb0c707bb](https://linux-hardware.org/?probe=bbb0c707bb) | Dec 01, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [38dfcb79d5](https://linux-hardware.org/?probe=38dfcb79d5) | Dec 01, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [ff5aef2f59](https://linux-hardware.org/?probe=ff5aef2f59) | Dec 01, 2022 |
| MSI           | H81M-E33                    | Desktop     | [aa874580d3](https://linux-hardware.org/?probe=aa874580d3) | Dec 01, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [a8156db955](https://linux-hardware.org/?probe=a8156db955) | Dec 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [5955142015](https://linux-hardware.org/?probe=5955142015) | Dec 01, 2022 |
| HP            | 8184 X4                     | Desktop     | [2b5ea5e34c](https://linux-hardware.org/?probe=2b5ea5e34c) | Dec 01, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [c8dd66d6de](https://linux-hardware.org/?probe=c8dd66d6de) | Dec 01, 2022 |
| Lenovo        | 3190 NOK                    | Mini pc     | [b550b6a30e](https://linux-hardware.org/?probe=b550b6a30e) | Dec 01, 2022 |
| Acer          | Aspire 5336                 | Notebook    | [65be105c02](https://linux-hardware.org/?probe=65be105c02) | Dec 01, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [d82ed03dd9](https://linux-hardware.org/?probe=d82ed03dd9) | Dec 01, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [4ae619c728](https://linux-hardware.org/?probe=4ae619c728) | Dec 01, 2022 |
| Acer          | Aspire 5741G                | Notebook    | [0a336099ba](https://linux-hardware.org/?probe=0a336099ba) | Dec 01, 2022 |
| Lenovo        | B450 1S1680033610187        | Notebook    | [e33670a27b](https://linux-hardware.org/?probe=e33670a27b) | Nov 30, 2022 |
| MSI           | GE72 6QC                    | Notebook    | [ba4847397e](https://linux-hardware.org/?probe=ba4847397e) | Nov 30, 2022 |
| Pegatron      | C15B                        | Notebook    | [defacd8748](https://linux-hardware.org/?probe=defacd8748) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [4e6ae396d9](https://linux-hardware.org/?probe=4e6ae396d9) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [65c3211b0a](https://linux-hardware.org/?probe=65c3211b0a) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2a8dbc14ef](https://linux-hardware.org/?probe=2a8dbc14ef) | Nov 30, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [43815283d9](https://linux-hardware.org/?probe=43815283d9) | Nov 30, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [b245f9da58](https://linux-hardware.org/?probe=b245f9da58) | Nov 30, 2022 |
| Dell          | Inspiron 3558               | Notebook    | [481755baa3](https://linux-hardware.org/?probe=481755baa3) | Nov 30, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [458ea4bd06](https://linux-hardware.org/?probe=458ea4bd06) | Nov 29, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [99c33f6741](https://linux-hardware.org/?probe=99c33f6741) | Nov 29, 2022 |
| HP            | 8437                        | Desktop     | [c5bbfc32f6](https://linux-hardware.org/?probe=c5bbfc32f6) | Nov 29, 2022 |
| Lenovo        | 3162 SDK0J40697 WIN 3305... | Desktop     | [296ceaab80](https://linux-hardware.org/?probe=296ceaab80) | Nov 29, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [c7bff3d908](https://linux-hardware.org/?probe=c7bff3d908) | Nov 29, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [8a99ec717f](https://linux-hardware.org/?probe=8a99ec717f) | Nov 29, 2022 |
| ASUSTek       | Q170T                       | Desktop     | [99abcc63ab](https://linux-hardware.org/?probe=99abcc63ab) | Nov 29, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [5d4811b390](https://linux-hardware.org/?probe=5d4811b390) | Nov 29, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [66fe0c3ddf](https://linux-hardware.org/?probe=66fe0c3ddf) | Nov 29, 2022 |
| ECS           | BSWI-D2                     | Desktop     | [b7e4fbdd31](https://linux-hardware.org/?probe=b7e4fbdd31) | Nov 29, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [6ece9d62e6](https://linux-hardware.org/?probe=6ece9d62e6) | Nov 29, 2022 |
| Lenovo        | G565 20071                  | Notebook    | [659a9a89b9](https://linux-hardware.org/?probe=659a9a89b9) | Nov 28, 2022 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [b2eb1eccbd](https://linux-hardware.org/?probe=b2eb1eccbd) | Nov 28, 2022 |
| Acer          | Aspire ES1-522              | Notebook    | [114c1d0914](https://linux-hardware.org/?probe=114c1d0914) | Nov 28, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [4fbe923ad2](https://linux-hardware.org/?probe=4fbe923ad2) | Nov 28, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [e117f07f42](https://linux-hardware.org/?probe=e117f07f42) | Nov 28, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [245ea45167](https://linux-hardware.org/?probe=245ea45167) | Nov 28, 2022 |
| HP            | 82F1                        | Desktop     | [17ed0cee6a](https://linux-hardware.org/?probe=17ed0cee6a) | Nov 28, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [0c1dece352](https://linux-hardware.org/?probe=0c1dece352) | Nov 28, 2022 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [82b84f846b](https://linux-hardware.org/?probe=82b84f846b) | Nov 27, 2022 |
| Lenovo        | ThinkPad L540 20AVA07BJP    | Notebook    | [cfc9d5c8a2](https://linux-hardware.org/?probe=cfc9d5c8a2) | Nov 27, 2022 |
| Gigabyte      | B550 GAMING X               | Desktop     | [f8979201eb](https://linux-hardware.org/?probe=f8979201eb) | Nov 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [1a24753132](https://linux-hardware.org/?probe=1a24753132) | Nov 27, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [3fda27c7b6](https://linux-hardware.org/?probe=3fda27c7b6) | Nov 27, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e6a6d0affd](https://linux-hardware.org/?probe=e6a6d0affd) | Nov 27, 2022 |
| Quanta        | JW6H                        | Notebook    | [12c85e1c14](https://linux-hardware.org/?probe=12c85e1c14) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2a77cd8415](https://linux-hardware.org/?probe=2a77cd8415) | Nov 27, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [73b4c53383](https://linux-hardware.org/?probe=73b4c53383) | Nov 27, 2022 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [ff31791cfb](https://linux-hardware.org/?probe=ff31791cfb) | Nov 27, 2022 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [e09f910876](https://linux-hardware.org/?probe=e09f910876) | Nov 27, 2022 |
| MACHINIST     | X99-RS9 V3.1                | Desktop     | [86cead0335](https://linux-hardware.org/?probe=86cead0335) | Nov 27, 2022 |
| HP            | Notebook                    | Notebook    | [4ff28b891c](https://linux-hardware.org/?probe=4ff28b891c) | Nov 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c5f8f3f82b](https://linux-hardware.org/?probe=c5f8f3f82b) | Nov 26, 2022 |
| Acer          | Aspire 5733Z                | Notebook    | [7fc415db1f](https://linux-hardware.org/?probe=7fc415db1f) | Nov 26, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [f35782a773](https://linux-hardware.org/?probe=f35782a773) | Nov 26, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f368bfcbe2](https://linux-hardware.org/?probe=f368bfcbe2) | Nov 26, 2022 |
| Sony          | VGN-P31ZRK_G                | Notebook    | [3c0c707fd4](https://linux-hardware.org/?probe=3c0c707fd4) | Nov 26, 2022 |
| Gigabyte      | B560 HD3                    | Desktop     | [f7915b54fb](https://linux-hardware.org/?probe=f7915b54fb) | Nov 26, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [7df334aaa0](https://linux-hardware.org/?probe=7df334aaa0) | Nov 26, 2022 |
| AZW           | SER V01                     | Mini pc     | [fa908550bd](https://linux-hardware.org/?probe=fa908550bd) | Nov 26, 2022 |
| Unknown       | PCWARE APMCP68              | Desktop     | [0cb03d53bb](https://linux-hardware.org/?probe=0cb03d53bb) | Nov 26, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [c17b2fcd65](https://linux-hardware.org/?probe=c17b2fcd65) | Nov 26, 2022 |
| HP            | Notebook                    | Notebook    | [6a8992e3ee](https://linux-hardware.org/?probe=6a8992e3ee) | Nov 26, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [9c2f530d6a](https://linux-hardware.org/?probe=9c2f530d6a) | Nov 25, 2022 |
| MSI           | K9AG Neo2                   | Desktop     | [a57a6f079b](https://linux-hardware.org/?probe=a57a6f079b) | Nov 25, 2022 |
| Insyde        | CherryTrail                 | Notebook    | [f7728857e6](https://linux-hardware.org/?probe=f7728857e6) | Nov 25, 2022 |
| HP            | Pavilion g7                 | Notebook    | [9b84cb2362](https://linux-hardware.org/?probe=9b84cb2362) | Nov 25, 2022 |
| ASRock        | H55M-LE                     | Desktop     | [75b9a8fb03](https://linux-hardware.org/?probe=75b9a8fb03) | Nov 25, 2022 |
| JGINYUE       | B660M-VDH                   | Desktop     | [bd879c87f8](https://linux-hardware.org/?probe=bd879c87f8) | Nov 25, 2022 |
| ASUSTek       | P5K                         | Desktop     | [87e7a3c0d0](https://linux-hardware.org/?probe=87e7a3c0d0) | Nov 25, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [e08bf40900](https://linux-hardware.org/?probe=e08bf40900) | Nov 25, 2022 |
| ASUSTek       | P8H61-MX                    | Desktop     | [d2e3977693](https://linux-hardware.org/?probe=d2e3977693) | Nov 25, 2022 |
| DEPO Compu... | DPC156                      | Notebook    | [9607de1a9c](https://linux-hardware.org/?probe=9607de1a9c) | Nov 25, 2022 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [41fc6614f7](https://linux-hardware.org/?probe=41fc6614f7) | Nov 25, 2022 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [0bb72a6a2a](https://linux-hardware.org/?probe=0bb72a6a2a) | Nov 25, 2022 |
| MSI           | GE72 6QC                    | Notebook    | [07084dd8f9](https://linux-hardware.org/?probe=07084dd8f9) | Nov 24, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [a636cfb9ff](https://linux-hardware.org/?probe=a636cfb9ff) | Nov 24, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [b1551151f5](https://linux-hardware.org/?probe=b1551151f5) | Nov 24, 2022 |
| Aquarius      | NS685U R11                  | Notebook    | [866e6d043c](https://linux-hardware.org/?probe=866e6d043c) | Nov 24, 2022 |
| ASUSTek       | P5P43TD                     | Desktop     | [324669845a](https://linux-hardware.org/?probe=324669845a) | Nov 24, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [a31935f117](https://linux-hardware.org/?probe=a31935f117) | Nov 24, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [8a5a155a45](https://linux-hardware.org/?probe=8a5a155a45) | Nov 24, 2022 |
| Intel         | NUC7i3DNB J57625-508        | Mini pc     | [e65c082f84](https://linux-hardware.org/?probe=e65c082f84) | Nov 24, 2022 |
| eMachines     | Rhine V1.40                 | Other       | [0c40e6da00](https://linux-hardware.org/?probe=0c40e6da00) | Nov 24, 2022 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [4e15e21f75](https://linux-hardware.org/?probe=4e15e21f75) | Nov 24, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [e892605084](https://linux-hardware.org/?probe=e892605084) | Nov 24, 2022 |
| ASUSTek       | P5K Premium                 | Desktop     | [5ff50a49ba](https://linux-hardware.org/?probe=5ff50a49ba) | Nov 23, 2022 |
| HP            | Notebook                    | Notebook    | [f81a524d22](https://linux-hardware.org/?probe=f81a524d22) | Nov 23, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [a17992aaa3](https://linux-hardware.org/?probe=a17992aaa3) | Nov 23, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [4617b6803a](https://linux-hardware.org/?probe=4617b6803a) | Nov 23, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [e83d79d385](https://linux-hardware.org/?probe=e83d79d385) | Nov 23, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [64728372e9](https://linux-hardware.org/?probe=64728372e9) | Nov 23, 2022 |
| HP            | Pavilion dv6                | Notebook    | [e3921e4da9](https://linux-hardware.org/?probe=e3921e4da9) | Nov 23, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [2485671def](https://linux-hardware.org/?probe=2485671def) | Nov 23, 2022 |
| Toshiba       | Satellite U300              | Notebook    | [f24a55abbf](https://linux-hardware.org/?probe=f24a55abbf) | Nov 23, 2022 |
| RuggedPC      | RuggedPadC16V               | Tablet      | [20de4fb74a](https://linux-hardware.org/?probe=20de4fb74a) | Nov 22, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [3a36391d83](https://linux-hardware.org/?probe=3a36391d83) | Nov 22, 2022 |
| MSI           | MS-N051                     | Notebook    | [efb37aedbe](https://linux-hardware.org/?probe=efb37aedbe) | Nov 22, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [c427f12dca](https://linux-hardware.org/?probe=c427f12dca) | Nov 22, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [2438420107](https://linux-hardware.org/?probe=2438420107) | Nov 22, 2022 |
| ASUSTek       | P8H61-I LX                  | Desktop     | [a537f96848](https://linux-hardware.org/?probe=a537f96848) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [ab91a099a5](https://linux-hardware.org/?probe=ab91a099a5) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [149f57ad9c](https://linux-hardware.org/?probe=149f57ad9c) | Nov 22, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [c0a3895ac4](https://linux-hardware.org/?probe=c0a3895ac4) | Nov 22, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [2cd736b247](https://linux-hardware.org/?probe=2cd736b247) | Nov 22, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [49cb3f2e52](https://linux-hardware.org/?probe=49cb3f2e52) | Nov 22, 2022 |
| Biostar       | G41D3+                      | Desktop     | [6ce48937fe](https://linux-hardware.org/?probe=6ce48937fe) | Nov 22, 2022 |
| Notebook      | W65_67SF                    | Notebook    | [91f6aa0bfb](https://linux-hardware.org/?probe=91f6aa0bfb) | Nov 22, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [37808c6686](https://linux-hardware.org/?probe=37808c6686) | Nov 22, 2022 |
| ASRock        | H55M-LE                     | Desktop     | [206082ac3f](https://linux-hardware.org/?probe=206082ac3f) | Nov 22, 2022 |
| Toshiba       | Satellite L45Dt-B           | Notebook    | [9cdcee20dc](https://linux-hardware.org/?probe=9cdcee20dc) | Nov 22, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [2575d2aab2](https://linux-hardware.org/?probe=2575d2aab2) | Nov 22, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [06396e3088](https://linux-hardware.org/?probe=06396e3088) | Nov 21, 2022 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [ed6bb8845a](https://linux-hardware.org/?probe=ed6bb8845a) | Nov 21, 2022 |
| Acer          | Extensa 2519                | Notebook    | [1ab63c7353](https://linux-hardware.org/?probe=1ab63c7353) | Nov 21, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [7d8faca25a](https://linux-hardware.org/?probe=7d8faca25a) | Nov 21, 2022 |
| MSI           | PRO H410M-B                 | Desktop     | [a81c612515](https://linux-hardware.org/?probe=a81c612515) | Nov 21, 2022 |
| MSI           | PRO H410M-B                 | Desktop     | [ebc5b13d4e](https://linux-hardware.org/?probe=ebc5b13d4e) | Nov 21, 2022 |
| Biostar       | G41D3+                      | Desktop     | [d1d42fec13](https://linux-hardware.org/?probe=d1d42fec13) | Nov 21, 2022 |
| HP            | Notebook                    | Notebook    | [c8bac5b72d](https://linux-hardware.org/?probe=c8bac5b72d) | Nov 20, 2022 |
| Acer          | Extensa 2519                | Notebook    | [fc5526a30f](https://linux-hardware.org/?probe=fc5526a30f) | Nov 20, 2022 |
| Acer          | Extensa 2519                | Notebook    | [5ae619eb32](https://linux-hardware.org/?probe=5ae619eb32) | Nov 20, 2022 |
| Acer          | Extensa 2540                | Notebook    | [2cd32708f2](https://linux-hardware.org/?probe=2cd32708f2) | Nov 20, 2022 |
| Intel         | DG45ID AAE27729-310         | Desktop     | [81ecca3cd1](https://linux-hardware.org/?probe=81ecca3cd1) | Nov 20, 2022 |
| ASUSTek       | M4A785T-M                   | Desktop     | [451b8a6b52](https://linux-hardware.org/?probe=451b8a6b52) | Nov 20, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [3f18cccea5](https://linux-hardware.org/?probe=3f18cccea5) | Nov 20, 2022 |
| HP            | Compaq nx9020 (PG641ES#A... | Notebook    | [ba63296d55](https://linux-hardware.org/?probe=ba63296d55) | Nov 20, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [122a37af55](https://linux-hardware.org/?probe=122a37af55) | Nov 20, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [a2eae9195c](https://linux-hardware.org/?probe=a2eae9195c) | Nov 20, 2022 |
| Lenovo        | G560 20042                  | Notebook    | [e2ea91a4ca](https://linux-hardware.org/?probe=e2ea91a4ca) | Nov 20, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [b133dcd886](https://linux-hardware.org/?probe=b133dcd886) | Nov 20, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [5099a55836](https://linux-hardware.org/?probe=5099a55836) | Nov 20, 2022 |
| ASUSTek       | P7H55                       | Desktop     | [aaaefec31e](https://linux-hardware.org/?probe=aaaefec31e) | Nov 20, 2022 |
| Pegatron      | A15                         | Notebook    | [dea0a0c81e](https://linux-hardware.org/?probe=dea0a0c81e) | Nov 20, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [8b000b014f](https://linux-hardware.org/?probe=8b000b014f) | Nov 20, 2022 |
| ASRock        | P43ME                       | Desktop     | [3b90870750](https://linux-hardware.org/?probe=3b90870750) | Nov 20, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [5cf9d6d04e](https://linux-hardware.org/?probe=5cf9d6d04e) | Nov 20, 2022 |
| Samsung       | R528/R728                   | Notebook    | [ea586efd66](https://linux-hardware.org/?probe=ea586efd66) | Nov 19, 2022 |
| Acer          | Aspire Z5101                | All in one  | [66f065adce](https://linux-hardware.org/?probe=66f065adce) | Nov 19, 2022 |
| Huanan        | B75                         | Desktop     | [cfc1803ca1](https://linux-hardware.org/?probe=cfc1803ca1) | Nov 19, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [450ca9f243](https://linux-hardware.org/?probe=450ca9f243) | Nov 19, 2022 |
| iRU           | J231                        | All in one  | [4556fb8986](https://linux-hardware.org/?probe=4556fb8986) | Nov 19, 2022 |
| MSI           | H61M-P21                    | Desktop     | [a91ee7dc9d](https://linux-hardware.org/?probe=a91ee7dc9d) | Nov 19, 2022 |
| iRU           | J231                        | All in one  | [3a1fc1760d](https://linux-hardware.org/?probe=3a1fc1760d) | Nov 19, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [32e06647dd](https://linux-hardware.org/?probe=32e06647dd) | Nov 19, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [7620fe2bdd](https://linux-hardware.org/?probe=7620fe2bdd) | Nov 19, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [19663894ff](https://linux-hardware.org/?probe=19663894ff) | Nov 18, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [99a32a02ce](https://linux-hardware.org/?probe=99a32a02ce) | Nov 18, 2022 |
| Dell          | 0RY007                      | Desktop     | [d11a712f82](https://linux-hardware.org/?probe=d11a712f82) | Nov 18, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [65abbfb38e](https://linux-hardware.org/?probe=65abbfb38e) | Nov 18, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [3e09380a65](https://linux-hardware.org/?probe=3e09380a65) | Nov 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [53f563177d](https://linux-hardware.org/?probe=53f563177d) | Nov 18, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [c695addaa3](https://linux-hardware.org/?probe=c695addaa3) | Nov 18, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [f644eba622](https://linux-hardware.org/?probe=f644eba622) | Nov 18, 2022 |
| Irbis         | TW103                       | Tablet      | [3f6ebcde0a](https://linux-hardware.org/?probe=3f6ebcde0a) | Nov 18, 2022 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [ceafbe876d](https://linux-hardware.org/?probe=ceafbe876d) | Nov 18, 2022 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [f6f8ae996d](https://linux-hardware.org/?probe=f6f8ae996d) | Nov 18, 2022 |
| Haier         | U1520HD                     | Notebook    | [7a9c0df4f1](https://linux-hardware.org/?probe=7a9c0df4f1) | Nov 18, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [99aed6e6d2](https://linux-hardware.org/?probe=99aed6e6d2) | Nov 17, 2022 |
| Intel         | H81                         | Desktop     | [f99a623867](https://linux-hardware.org/?probe=f99a623867) | Nov 17, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [d353571eef](https://linux-hardware.org/?probe=d353571eef) | Nov 17, 2022 |
| Intel         | H81                         | Desktop     | [5bfd56a1f8](https://linux-hardware.org/?probe=5bfd56a1f8) | Nov 17, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [814b71a20c](https://linux-hardware.org/?probe=814b71a20c) | Nov 17, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [f9da339cc7](https://linux-hardware.org/?probe=f9da339cc7) | Nov 17, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [735035876a](https://linux-hardware.org/?probe=735035876a) | Nov 17, 2022 |
| MSI           | H61M-P32/W8                 | Desktop     | [82cba9e87c](https://linux-hardware.org/?probe=82cba9e87c) | Nov 16, 2022 |
| ASUSTek       | X507UA                      | Notebook    | [9a2fe77bac](https://linux-hardware.org/?probe=9a2fe77bac) | Nov 16, 2022 |
| ASUSTek       | B75M-A                      | Desktop     | [087a904af2](https://linux-hardware.org/?probe=087a904af2) | Nov 16, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ccf8236d38](https://linux-hardware.org/?probe=ccf8236d38) | Nov 16, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [39078e426c](https://linux-hardware.org/?probe=39078e426c) | Nov 16, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [74cdb80f42](https://linux-hardware.org/?probe=74cdb80f42) | Nov 16, 2022 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [cf10680f5f](https://linux-hardware.org/?probe=cf10680f5f) | Nov 15, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [e7d93e8540](https://linux-hardware.org/?probe=e7d93e8540) | Nov 15, 2022 |
| Intel         | NUC7i3DNB J57625-508        | Mini pc     | [8e3861630d](https://linux-hardware.org/?probe=8e3861630d) | Nov 15, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [c67fea651e](https://linux-hardware.org/?probe=c67fea651e) | Nov 15, 2022 |
| ASRock        | N68-GS4 FX                  | Desktop     | [c651e62593](https://linux-hardware.org/?probe=c651e62593) | Nov 15, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [31ebbfaf58](https://linux-hardware.org/?probe=31ebbfaf58) | Nov 15, 2022 |
| Toshiba       | Satellite A300D             | Notebook    | [c5dc216e31](https://linux-hardware.org/?probe=c5dc216e31) | Nov 15, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [5802f0db59](https://linux-hardware.org/?probe=5802f0db59) | Nov 15, 2022 |
| Unknown       | Intel X79                   | Desktop     | [61483ea15b](https://linux-hardware.org/?probe=61483ea15b) | Nov 14, 2022 |
| Intel         | NUC7i3DNB J57625-508        | Mini pc     | [fbaa96eef7](https://linux-hardware.org/?probe=fbaa96eef7) | Nov 14, 2022 |
| HP            | ENVY m6                     | Notebook    | [4397c54e20](https://linux-hardware.org/?probe=4397c54e20) | Nov 14, 2022 |
| Lenovo        | 31900059 STD                | All in one  | [cb73069418](https://linux-hardware.org/?probe=cb73069418) | Nov 14, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [191fa275ad](https://linux-hardware.org/?probe=191fa275ad) | Nov 14, 2022 |
| Acer          | Aspire C22-820              | All in one  | [65598ad0b3](https://linux-hardware.org/?probe=65598ad0b3) | Nov 14, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [0f8a90fef7](https://linux-hardware.org/?probe=0f8a90fef7) | Nov 14, 2022 |
| ASUSTek       | K42DY                       | Notebook    | [f7a61f85d9](https://linux-hardware.org/?probe=f7a61f85d9) | Nov 14, 2022 |
| Intel         | H81                         | Desktop     | [738056c2ab](https://linux-hardware.org/?probe=738056c2ab) | Nov 14, 2022 |
| ASUSTek       | UX330CAK                    | Notebook    | [bd7d377985](https://linux-hardware.org/?probe=bd7d377985) | Nov 14, 2022 |
| MSI           | MS-7360                     | Desktop     | [4899c85a97](https://linux-hardware.org/?probe=4899c85a97) | Nov 14, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [34a5f361bd](https://linux-hardware.org/?probe=34a5f361bd) | Nov 14, 2022 |
| ASUSTek       | K53SM                       | Notebook    | [297194e8e4](https://linux-hardware.org/?probe=297194e8e4) | Nov 13, 2022 |
| Toshiba       | Satellite P300              | Notebook    | [02285947b8](https://linux-hardware.org/?probe=02285947b8) | Nov 13, 2022 |
| Pegatron      | 2A94h                       | Desktop     | [5ebd2a4bf4](https://linux-hardware.org/?probe=5ebd2a4bf4) | Nov 13, 2022 |
| Acer          | Aspire E1-531G              | Notebook    | [9f3c8742f7](https://linux-hardware.org/?probe=9f3c8742f7) | Nov 13, 2022 |
| Sony          | SVE1512H1RW                 | Notebook    | [032fdf5260](https://linux-hardware.org/?probe=032fdf5260) | Nov 13, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [e8e7b815c4](https://linux-hardware.org/?probe=e8e7b815c4) | Nov 13, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [af898e0d66](https://linux-hardware.org/?probe=af898e0d66) | Nov 13, 2022 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [aedb84820e](https://linux-hardware.org/?probe=aedb84820e) | Nov 13, 2022 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [0127d7b1cd](https://linux-hardware.org/?probe=0127d7b1cd) | Nov 12, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [10482f151a](https://linux-hardware.org/?probe=10482f151a) | Nov 12, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [6b77cc7062](https://linux-hardware.org/?probe=6b77cc7062) | Nov 12, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [5f20ed2dd2](https://linux-hardware.org/?probe=5f20ed2dd2) | Nov 12, 2022 |
| Foxconn       | H77M/H77M-S                 | Desktop     | [bebf7f53f8](https://linux-hardware.org/?probe=bebf7f53f8) | Nov 12, 2022 |
| HP            | Compaq nc6120 (PY507EA#A... | Notebook    | [a4c594d8db](https://linux-hardware.org/?probe=a4c594d8db) | Nov 12, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c8538a21be](https://linux-hardware.org/?probe=c8538a21be) | Nov 12, 2022 |
| Acer          | Acadia V1.45                | Notebook    | [c6a91498cc](https://linux-hardware.org/?probe=c6a91498cc) | Nov 12, 2022 |
| ASUSTek       | P5K-VM                      | Desktop     | [8d1ad25443](https://linux-hardware.org/?probe=8d1ad25443) | Nov 12, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [7fe6789365](https://linux-hardware.org/?probe=7fe6789365) | Nov 12, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [1243c9795a](https://linux-hardware.org/?probe=1243c9795a) | Nov 12, 2022 |
| ASUSTek       | K53BR                       | Notebook    | [15838034f5](https://linux-hardware.org/?probe=15838034f5) | Nov 12, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [4f40815737](https://linux-hardware.org/?probe=4f40815737) | Nov 12, 2022 |
| MSI           | Z97-G43                     | Desktop     | [f5946a94b0](https://linux-hardware.org/?probe=f5946a94b0) | Nov 12, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a8d2d850a5](https://linux-hardware.org/?probe=a8d2d850a5) | Nov 12, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [4838271135](https://linux-hardware.org/?probe=4838271135) | Nov 11, 2022 |
| Acer          | Acadia V1.19                | Notebook    | [f43450e9d4](https://linux-hardware.org/?probe=f43450e9d4) | Nov 11, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [0d1333128b](https://linux-hardware.org/?probe=0d1333128b) | Nov 11, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [ff49e5ddb5](https://linux-hardware.org/?probe=ff49e5ddb5) | Nov 11, 2022 |
| Sapphire      | IPC-E350M1                  | Desktop     | [58a5544fb4](https://linux-hardware.org/?probe=58a5544fb4) | Nov 11, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [af490e0878](https://linux-hardware.org/?probe=af490e0878) | Nov 11, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [b152665a17](https://linux-hardware.org/?probe=b152665a17) | Nov 11, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [12d6552ded](https://linux-hardware.org/?probe=12d6552ded) | Nov 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [cbd9e440a6](https://linux-hardware.org/?probe=cbd9e440a6) | Nov 11, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [277c219cef](https://linux-hardware.org/?probe=277c219cef) | Nov 11, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [b8b0c9fae3](https://linux-hardware.org/?probe=b8b0c9fae3) | Nov 11, 2022 |
| Biostar       | N68S3+                      | Desktop     | [a37667f835](https://linux-hardware.org/?probe=a37667f835) | Nov 11, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [a37ca89eae](https://linux-hardware.org/?probe=a37ca89eae) | Nov 11, 2022 |
| Samsung       | R519/R719                   | Notebook    | [31260d4616](https://linux-hardware.org/?probe=31260d4616) | Nov 11, 2022 |
| Sony          | VPCEH3J1R                   | Notebook    | [4944a2e287](https://linux-hardware.org/?probe=4944a2e287) | Nov 11, 2022 |
| HP            | Pavilion g6                 | Notebook    | [fc422ba1a4](https://linux-hardware.org/?probe=fc422ba1a4) | Nov 11, 2022 |
| MSI           | B150 GAMING M3              | Desktop     | [13f42af580](https://linux-hardware.org/?probe=13f42af580) | Nov 11, 2022 |
| MSI           | B450M GAMING PLUS           | Desktop     | [dd56553c17](https://linux-hardware.org/?probe=dd56553c17) | Nov 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [f56dc1af6b](https://linux-hardware.org/?probe=f56dc1af6b) | Nov 10, 2022 |
| Unknown       | NF-CK804                    | Desktop     | [6bda1f2345](https://linux-hardware.org/?probe=6bda1f2345) | Nov 10, 2022 |
| ASRock        | H410M-HDV                   | Desktop     | [985b9b55e2](https://linux-hardware.org/?probe=985b9b55e2) | Nov 10, 2022 |
| Acer          | Aspire V5-572G              | Notebook    | [bd537cc78c](https://linux-hardware.org/?probe=bd537cc78c) | Nov 10, 2022 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [0873e8bf70](https://linux-hardware.org/?probe=0873e8bf70) | Nov 10, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [4d6af313f5](https://linux-hardware.org/?probe=4d6af313f5) | Nov 10, 2022 |
| Sony          | VPCS11V9R                   | Notebook    | [a0b4bf7869](https://linux-hardware.org/?probe=a0b4bf7869) | Nov 10, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [b5ce55106f](https://linux-hardware.org/?probe=b5ce55106f) | Nov 10, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [4cf7d8ea41](https://linux-hardware.org/?probe=4cf7d8ea41) | Nov 10, 2022 |
| Intel         | X79                         | Desktop     | [f806dcc4da](https://linux-hardware.org/?probe=f806dcc4da) | Nov 10, 2022 |
| Pegatron      | 2A73h                       | Desktop     | [dc035c362e](https://linux-hardware.org/?probe=dc035c362e) | Nov 10, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [640d78b1e4](https://linux-hardware.org/?probe=640d78b1e4) | Nov 10, 2022 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [d9d004077a](https://linux-hardware.org/?probe=d9d004077a) | Nov 10, 2022 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [2da4055f76](https://linux-hardware.org/?probe=2da4055f76) | Nov 09, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [50b86d41a2](https://linux-hardware.org/?probe=50b86d41a2) | Nov 09, 2022 |
| MSI           | Z370 TOMAHAWK               | Desktop     | [0763a922c8](https://linux-hardware.org/?probe=0763a922c8) | Nov 09, 2022 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [dafce5f727](https://linux-hardware.org/?probe=dafce5f727) | Nov 09, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [bdd79e7a9e](https://linux-hardware.org/?probe=bdd79e7a9e) | Nov 09, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [c92f8d8b22](https://linux-hardware.org/?probe=c92f8d8b22) | Nov 09, 2022 |
| Lenovo        | E31-70 80KX                 | Notebook    | [61343c5ca1](https://linux-hardware.org/?probe=61343c5ca1) | Nov 09, 2022 |
| ASUSTek       | X507UB                      | Notebook    | [2790049313](https://linux-hardware.org/?probe=2790049313) | Nov 09, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [97ed2f1140](https://linux-hardware.org/?probe=97ed2f1140) | Nov 09, 2022 |
| MSI           | GE70 2PL                    | Notebook    | [d09e002aa8](https://linux-hardware.org/?probe=d09e002aa8) | Nov 09, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [46dd8a0416](https://linux-hardware.org/?probe=46dd8a0416) | Nov 08, 2022 |
| ASUSTek       | U24E                        | Notebook    | [a51fe3226f](https://linux-hardware.org/?probe=a51fe3226f) | Nov 08, 2022 |
| MSI           | X370 GAMING PLUS            | Desktop     | [ae91098674](https://linux-hardware.org/?probe=ae91098674) | Nov 08, 2022 |
| MSI           | GE70 2PL                    | Notebook    | [8752dacd05](https://linux-hardware.org/?probe=8752dacd05) | Nov 08, 2022 |
| Acer          | Nitro AN517-52              | Notebook    | [3a2bb9e1e9](https://linux-hardware.org/?probe=3a2bb9e1e9) | Nov 08, 2022 |
| Gigabyte      | GA-A75M-UD2H                | Desktop     | [c8383aa811](https://linux-hardware.org/?probe=c8383aa811) | Nov 08, 2022 |
| Gigabyte      | GA-A75M-UD2H                | Desktop     | [7f6cff35d7](https://linux-hardware.org/?probe=7f6cff35d7) | Nov 08, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [558d46bf81](https://linux-hardware.org/?probe=558d46bf81) | Nov 08, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [b6a1f08748](https://linux-hardware.org/?probe=b6a1f08748) | Nov 08, 2022 |
| HP            | Notebook                    | Notebook    | [0868a7d110](https://linux-hardware.org/?probe=0868a7d110) | Nov 08, 2022 |
| Acer          | IPISB-AG                    | All in one  | [fbca3edeb5](https://linux-hardware.org/?probe=fbca3edeb5) | Nov 08, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [137958160c](https://linux-hardware.org/?probe=137958160c) | Nov 08, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [515cdf3f6c](https://linux-hardware.org/?probe=515cdf3f6c) | Nov 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [37226d7d92](https://linux-hardware.org/?probe=37226d7d92) | Nov 07, 2022 |
| MSI           | X370 GAMING PLUS            | Desktop     | [cda3bef0bc](https://linux-hardware.org/?probe=cda3bef0bc) | Nov 07, 2022 |
| Fujitsu       | D3061-B1 S26361-D3061-B1    | Desktop     | [731ce5b944](https://linux-hardware.org/?probe=731ce5b944) | Nov 07, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [5e972fdb95](https://linux-hardware.org/?probe=5e972fdb95) | Nov 07, 2022 |
| ASRock        | D1800M                      | Desktop     | [4935d67430](https://linux-hardware.org/?probe=4935d67430) | Nov 07, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9992a08641](https://linux-hardware.org/?probe=9992a08641) | Nov 07, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [d5c179046a](https://linux-hardware.org/?probe=d5c179046a) | Nov 07, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [e75f44efd0](https://linux-hardware.org/?probe=e75f44efd0) | Nov 07, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [dd30cc2e63](https://linux-hardware.org/?probe=dd30cc2e63) | Nov 07, 2022 |
| eMachines     | eM350                       | Notebook    | [ac6dda5ddb](https://linux-hardware.org/?probe=ac6dda5ddb) | Nov 07, 2022 |
| Sony          | VPCZ13S9R                   | Notebook    | [9a0f47ed25](https://linux-hardware.org/?probe=9a0f47ed25) | Nov 07, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [c7b8fac7e2](https://linux-hardware.org/?probe=c7b8fac7e2) | Nov 07, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [16b37f0b80](https://linux-hardware.org/?probe=16b37f0b80) | Nov 07, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [614a486442](https://linux-hardware.org/?probe=614a486442) | Nov 07, 2022 |
| ASUSTek       | F2A55-M LK                  | Desktop     | [0c888d2b1f](https://linux-hardware.org/?probe=0c888d2b1f) | Nov 07, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [eae2553adf](https://linux-hardware.org/?probe=eae2553adf) | Nov 06, 2022 |
| MSI           | H81M-P33                    | Desktop     | [00cb3af126](https://linux-hardware.org/?probe=00cb3af126) | Nov 06, 2022 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [0dab96ade2](https://linux-hardware.org/?probe=0dab96ade2) | Nov 06, 2022 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [65ac5d12c7](https://linux-hardware.org/?probe=65ac5d12c7) | Nov 06, 2022 |
| ASRock        | H370M-ITX/ac                | Desktop     | [fe29240874](https://linux-hardware.org/?probe=fe29240874) | Nov 06, 2022 |
| Acer          | EG31M R01-C2                | Desktop     | [1c541d28e0](https://linux-hardware.org/?probe=1c541d28e0) | Nov 06, 2022 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [3ffeb18e56](https://linux-hardware.org/?probe=3ffeb18e56) | Nov 06, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [a60e7d1961](https://linux-hardware.org/?probe=a60e7d1961) | Nov 06, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [db56889368](https://linux-hardware.org/?probe=db56889368) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [05ac02550e](https://linux-hardware.org/?probe=05ac02550e) | Nov 06, 2022 |
| MSI           | B150 GAMING M3              | Desktop     | [38a85b01ad](https://linux-hardware.org/?probe=38a85b01ad) | Nov 06, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [b6a4d355bc](https://linux-hardware.org/?probe=b6a4d355bc) | Nov 06, 2022 |
| Digma         | EVE 10 C301T ES1043EW       | Tablet      | [873aa1a6bb](https://linux-hardware.org/?probe=873aa1a6bb) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [ba495c1631](https://linux-hardware.org/?probe=ba495c1631) | Nov 06, 2022 |
| Samsung       | R510/P510                   | Notebook    | [4921b97206](https://linux-hardware.org/?probe=4921b97206) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [19304dd869](https://linux-hardware.org/?probe=19304dd869) | Nov 06, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [4cadf85e6e](https://linux-hardware.org/?probe=4cadf85e6e) | Nov 06, 2022 |
| Acer          | Aspire A317-52              | Notebook    | [e9ed162010](https://linux-hardware.org/?probe=e9ed162010) | Nov 06, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [ce7c45a3d9](https://linux-hardware.org/?probe=ce7c45a3d9) | Nov 06, 2022 |
| Biostar       | A78LR-M3S                   | Desktop     | [8e8da94ddb](https://linux-hardware.org/?probe=8e8da94ddb) | Nov 06, 2022 |
| Toshiba       | Satellite L550              | Notebook    | [3b95d22100](https://linux-hardware.org/?probe=3b95d22100) | Nov 06, 2022 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [53d09fc292](https://linux-hardware.org/?probe=53d09fc292) | Nov 05, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [a89bc09dca](https://linux-hardware.org/?probe=a89bc09dca) | Nov 05, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [5d6951212b](https://linux-hardware.org/?probe=5d6951212b) | Nov 05, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [92be197f2d](https://linux-hardware.org/?probe=92be197f2d) | Nov 05, 2022 |
| ASUSTek       | PRIME H510M-R               | Desktop     | [922e24a1a0](https://linux-hardware.org/?probe=922e24a1a0) | Nov 05, 2022 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [40ef04163d](https://linux-hardware.org/?probe=40ef04163d) | Nov 05, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [d7512f31a3](https://linux-hardware.org/?probe=d7512f31a3) | Nov 05, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [a8926fce15](https://linux-hardware.org/?probe=a8926fce15) | Nov 05, 2022 |
| ASUSTek       | N76VB                       | Notebook    | [c46794ba60](https://linux-hardware.org/?probe=c46794ba60) | Nov 05, 2022 |
| MSI           | P67A-C43                    | Desktop     | [a5e86512d1](https://linux-hardware.org/?probe=a5e86512d1) | Nov 05, 2022 |
| Fujitsu Si... | AMILO Pro V3205             | Notebook    | [7a03ef6ae1](https://linux-hardware.org/?probe=7a03ef6ae1) | Nov 05, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [698596bd58](https://linux-hardware.org/?probe=698596bd58) | Nov 05, 2022 |
| Gigabyte      | H110M-S2HP-CF               | Desktop     | [94004d5828](https://linux-hardware.org/?probe=94004d5828) | Nov 05, 2022 |
| HP            | Pavilion dv7                | Notebook    | [d17019e1f7](https://linux-hardware.org/?probe=d17019e1f7) | Nov 05, 2022 |
| Gigabyte      | B75-D3V                     | Desktop     | [a562aef0c3](https://linux-hardware.org/?probe=a562aef0c3) | Nov 05, 2022 |
| ASUSTek       | N56VJ                       | Notebook    | [1685737249](https://linux-hardware.org/?probe=1685737249) | Nov 05, 2022 |
| ASUSTek       | M4A77TD PRO                 | Desktop     | [b5fa37b726](https://linux-hardware.org/?probe=b5fa37b726) | Nov 04, 2022 |
| ASUSTek       | F5N                         | Notebook    | [f1efa34bf8](https://linux-hardware.org/?probe=f1efa34bf8) | Nov 04, 2022 |
| ASUSTek       | X75VD                       | Notebook    | [60e91d212e](https://linux-hardware.org/?probe=60e91d212e) | Nov 04, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [6807b6b584](https://linux-hardware.org/?probe=6807b6b584) | Nov 04, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [d0267472d6](https://linux-hardware.org/?probe=d0267472d6) | Nov 04, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [82213a5471](https://linux-hardware.org/?probe=82213a5471) | Nov 04, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [edf9105fc5](https://linux-hardware.org/?probe=edf9105fc5) | Nov 04, 2022 |
| ASUSTek       | F5N                         | Notebook    | [8e3878fe4d](https://linux-hardware.org/?probe=8e3878fe4d) | Nov 04, 2022 |
| ASUSTek       | F5N                         | Notebook    | [f95b9890f6](https://linux-hardware.org/?probe=f95b9890f6) | Nov 04, 2022 |
| HUAWEI        | HKD-WXX                     | Notebook    | [7a8f33b5bf](https://linux-hardware.org/?probe=7a8f33b5bf) | Nov 04, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [ae6073535e](https://linux-hardware.org/?probe=ae6073535e) | Nov 04, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [f67d642096](https://linux-hardware.org/?probe=f67d642096) | Nov 04, 2022 |
| MSI           | B360M PRO-VDH               | Desktop     | [2a801a9792](https://linux-hardware.org/?probe=2a801a9792) | Nov 04, 2022 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [8732711bf0](https://linux-hardware.org/?probe=8732711bf0) | Nov 04, 2022 |
| ASUSTek       | U24E                        | Notebook    | [6303641e69](https://linux-hardware.org/?probe=6303641e69) | Nov 04, 2022 |
| ASRock        | B85M Pro4                   | Desktop     | [55da31d807](https://linux-hardware.org/?probe=55da31d807) | Nov 04, 2022 |
| ASUSTek       | P5K                         | Desktop     | [ebc4a23dcc](https://linux-hardware.org/?probe=ebc4a23dcc) | Nov 04, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [d7c44d9e94](https://linux-hardware.org/?probe=d7c44d9e94) | Nov 04, 2022 |
| MSI           | X370 GAMING PLUS            | Desktop     | [db81c87a42](https://linux-hardware.org/?probe=db81c87a42) | Nov 04, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [16cd4b28ce](https://linux-hardware.org/?probe=16cd4b28ce) | Nov 04, 2022 |
| Huanan        | X99-BD4 V1.3                | Desktop     | [3eccdb8ba1](https://linux-hardware.org/?probe=3eccdb8ba1) | Nov 03, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [ef71fa8dd6](https://linux-hardware.org/?probe=ef71fa8dd6) | Nov 03, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [c560dfaab4](https://linux-hardware.org/?probe=c560dfaab4) | Nov 03, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [d5c39748e3](https://linux-hardware.org/?probe=d5c39748e3) | Nov 03, 2022 |
| MSI           | X370 GAMING PLUS            | Desktop     | [749d91dfd4](https://linux-hardware.org/?probe=749d91dfd4) | Nov 03, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [eb3812d5ce](https://linux-hardware.org/?probe=eb3812d5ce) | Nov 03, 2022 |
| ECS           | MCP61M-M3                   | Desktop     | [fe5e87a9ef](https://linux-hardware.org/?probe=fe5e87a9ef) | Nov 03, 2022 |
| ASUSTek       | 1215B                       | Notebook    | [eeff579fe6](https://linux-hardware.org/?probe=eeff579fe6) | Nov 03, 2022 |
| ASUSTek       | Z97-C                       | Desktop     | [be4968a790](https://linux-hardware.org/?probe=be4968a790) | Nov 03, 2022 |
| ASUSTek       | K501LB                      | Notebook    | [e28cd8cfbf](https://linux-hardware.org/?probe=e28cd8cfbf) | Nov 03, 2022 |
| ASUSTek       | 1215B                       | Notebook    | [3cc2c5ad48](https://linux-hardware.org/?probe=3cc2c5ad48) | Nov 03, 2022 |
| ASRock        | A320D4-P1                   | Desktop     | [8e453f4158](https://linux-hardware.org/?probe=8e453f4158) | Nov 03, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [c54743b7e8](https://linux-hardware.org/?probe=c54743b7e8) | Nov 02, 2022 |
| ASRock        | N68-GS4 FX                  | Desktop     | [da7a70afe1](https://linux-hardware.org/?probe=da7a70afe1) | Nov 02, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [24a3f977bf](https://linux-hardware.org/?probe=24a3f977bf) | Nov 02, 2022 |
| MSI           | MS-7392                     | Desktop     | [d453f89064](https://linux-hardware.org/?probe=d453f89064) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [28d7daff10](https://linux-hardware.org/?probe=28d7daff10) | Nov 02, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [710ab678b2](https://linux-hardware.org/?probe=710ab678b2) | Nov 02, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [519fa92199](https://linux-hardware.org/?probe=519fa92199) | Nov 02, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [d8b066edcd](https://linux-hardware.org/?probe=d8b066edcd) | Nov 02, 2022 |
| ASUSTek       | 1215B                       | Notebook    | [21694405a9](https://linux-hardware.org/?probe=21694405a9) | Nov 02, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [496a16216c](https://linux-hardware.org/?probe=496a16216c) | Nov 02, 2022 |
| Intel         | NUC7i3DNB J57625-508        | Mini pc     | [075f628a80](https://linux-hardware.org/?probe=075f628a80) | Nov 02, 2022 |
| Lenovo        | H420                        | Desktop     | [3e3f04d875](https://linux-hardware.org/?probe=3e3f04d875) | Nov 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [6f89789444](https://linux-hardware.org/?probe=6f89789444) | Nov 02, 2022 |
| Gigabyte      | EP45-DS4                    | Desktop     | [fa96a26c5a](https://linux-hardware.org/?probe=fa96a26c5a) | Nov 02, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [b70c0aa20d](https://linux-hardware.org/?probe=b70c0aa20d) | Nov 01, 2022 |
| Gigabyte      | EP45-DS4                    | Desktop     | [2eb78b1c3d](https://linux-hardware.org/?probe=2eb78b1c3d) | Nov 01, 2022 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [9efd2724b2](https://linux-hardware.org/?probe=9efd2724b2) | Nov 01, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [fe23529093](https://linux-hardware.org/?probe=fe23529093) | Nov 01, 2022 |
| ASRock        | B365M-HDV                   | Desktop     | [29a6bce4c0](https://linux-hardware.org/?probe=29a6bce4c0) | Nov 01, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [76052b7756](https://linux-hardware.org/?probe=76052b7756) | Nov 01, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [a54d6876b6](https://linux-hardware.org/?probe=a54d6876b6) | Nov 01, 2022 |
| MSI           | H61M-P32/W8                 | Desktop     | [14df9c3c14](https://linux-hardware.org/?probe=14df9c3c14) | Nov 01, 2022 |
| ASRock        | N68C-GS FX                  | Desktop     | [f7a9c5f382](https://linux-hardware.org/?probe=f7a9c5f382) | Nov 01, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [406aae2f66](https://linux-hardware.org/?probe=406aae2f66) | Nov 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [da912b99f4](https://linux-hardware.org/?probe=da912b99f4) | Nov 01, 2022 |
| MSI           | H81M-P33                    | Desktop     | [29e4a4ec52](https://linux-hardware.org/?probe=29e4a4ec52) | Oct 31, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [96d61ed3e1](https://linux-hardware.org/?probe=96d61ed3e1) | Oct 31, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [8e480ded02](https://linux-hardware.org/?probe=8e480ded02) | Oct 31, 2022 |
| Gigabyte      | X99-SLI-CF                  | Desktop     | [d6bc77d638](https://linux-hardware.org/?probe=d6bc77d638) | Oct 31, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [eaa9bcaadb](https://linux-hardware.org/?probe=eaa9bcaadb) | Oct 31, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [2fdcf19b6d](https://linux-hardware.org/?probe=2fdcf19b6d) | Oct 31, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [7b016c85d8](https://linux-hardware.org/?probe=7b016c85d8) | Oct 31, 2022 |
| Acer          | Aspire 5733                 | Notebook    | [bcc1836178](https://linux-hardware.org/?probe=bcc1836178) | Oct 31, 2022 |
| Foxconn       | RS690M2MA 0A                | Desktop     | [29605bcad9](https://linux-hardware.org/?probe=29605bcad9) | Oct 31, 2022 |
| ASUSTek       | K43SJ                       | Notebook    | [778e6caf06](https://linux-hardware.org/?probe=778e6caf06) | Oct 31, 2022 |
| Gigabyte      | B660M GAMING X AX           | Desktop     | [d48fe55211](https://linux-hardware.org/?probe=d48fe55211) | Oct 31, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ROSA/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ROSA R10           | 4389      | 14.32%  |
| ROSA R11           | 4115      | 13.43%  |
| ROSA R8            | 3637      | 11.87%  |
| ROSA R6            | 3496      | 11.41%  |
| ROSA R7            | 3301      | 10.77%  |
| ROSA R8.1          | 2852      | 9.31%   |
| ROSA R9            | 2548      | 8.32%   |
| ROSA R11.1         | 2250      | 7.34%   |
| ROSA 12.2          | 1978      | 6.46%   |
| ROSA 12.3          | 617       | 2.01%   |
| ROSA R5            | 571       | 1.86%   |
| ROSA 12.1          | 333       | 1.09%   |
| ROSA 12            | 186       | 0.61%   |
| ROSA R4            | 121       | 0.39%   |
| ROSA R3            | 86        | 0.28%   |
| ROSA R12           | 71        | 0.23%   |
| ROSA 2019.05       | 20        | 0.07%   |
| ROSA R9-R11        | 16        | 0.05%   |
| ROSA R2            | 16        | 0.05%   |
| ROSA 2012.0        | 12        | 0.04%   |
| ROSA Chrome 2.0    | 7         | 0.02%   |
| ROSA R4-R8         | 4         | 0.01%   |
| ROSA DX 1.0        | 4         | 0.01%   |
| ROSA Nickel 2019.0 | 3         | 0.01%   |
| ROSA DX 2.0        | 2         | 0.01%   |
| ROSA 2021.1        | 2         | 0.01%   |
| ROSA 2019.0        | 2         | 0.01%   |
| ROSA SX 1.0        | 1         | 0.003%  |
| ROSA R1            | 1         | 0.003%  |
| ROSA 13.0          | 1         | 0.003%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| ROSA | 25406     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 2053      | 6.21%   |
| 3.14.44-nrj-desktop-2rosa-x86_64    | 1866      | 5.64%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 1827      | 5.52%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 1800      | 5.44%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 1727      | 5.22%   |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 1600      | 4.84%   |
| 4.1.15-nrj-desktop-1rosa-x86_64     | 1381      | 4.17%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 971       | 2.93%   |
| 3.14.44-nrj-desktop-2rosa-i586      | 833       | 2.52%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 782       | 2.36%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 697       | 2.11%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 647       | 1.96%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 580       | 1.75%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 549       | 1.66%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 516       | 1.56%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 502       | 1.52%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 491       | 1.48%   |
| 4.1.16-nrj-desktop-1rosa-x86_64     | 463       | 1.4%    |
| 4.15.0-desktop-68.5rosa-x86_64      | 457       | 1.38%   |
| 4.15.0-desktop-45.1rosa-i586        | 453       | 1.37%   |
| 4.1.15-nrj-desktop-1rosa-i586       | 452       | 1.37%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 446       | 1.35%   |
| 5.4.32-generic-2rosa-x86_64         | 434       | 1.31%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 421       | 1.27%   |
| 5.4.83-generic-2rosa-x86_64         | 388       | 1.17%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 379       | 1.15%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 360       | 1.09%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 340       | 1.03%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 334       | 1.01%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 311       | 0.94%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 278       | 0.84%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 270       | 0.82%   |
| 3.14.53-nrj-desktop-1rosa-x86_64    | 270       | 0.82%   |
| 4.1.22-nrj-desktop-2rosa-x86_64     | 258       | 0.78%   |
| 4.1.33-nrj-desktop-1rosa-x86_64     | 250       | 0.76%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 228       | 0.69%   |
| 3.14.25-nrj-desktop-1rosa           | 219       | 0.66%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 208       | 0.63%   |
| 4.1.13-nrj-desktop-1rosa-x86_64     | 200       | 0.6%    |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 195       | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.15.0   | 4393      | 13.54%  |
| 3.14.44  | 2695      | 8.31%   |
| 4.9.60   | 2594      | 7.99%   |
| 4.9.20   | 2317      | 7.14%   |
| 4.1.25   | 2172      | 6.69%   |
| 4.1.15   | 1832      | 5.65%   |
| 5.10.74  | 1780      | 5.49%   |
| 4.1.34   | 1349      | 4.16%   |
| 4.1.38   | 1110      | 3.42%   |
| 4.9.9    | 1002      | 3.09%   |
| 4.9.124  | 973       | 3%      |
| 4.9.155  | 684       | 2.11%   |
| 4.9.76   | 638       | 1.97%   |
| 4.1.16   | 631       | 1.94%   |
| 5.4.32   | 592       | 1.82%   |
| 4.9.41   | 589       | 1.82%   |
| 5.4.83   | 491       | 1.51%   |
| 4.1.19   | 390       | 1.2%    |
| 3.14.53  | 387       | 1.19%   |
| 5.10.118 | 368       | 1.13%   |
| 4.1.22   | 366       | 1.13%   |
| 4.9.95   | 339       | 1.04%   |
| 4.1.33   | 339       | 1.04%   |
| 4.1.13   | 305       | 0.94%   |
| 4.9.111  | 244       | 0.75%   |
| 5.15.75  | 233       | 0.72%   |
| 3.14.25  | 222       | 0.68%   |
| 3.14.33  | 196       | 0.6%    |
| 5.10.71  | 182       | 0.56%   |
| 4.9.87   | 174       | 0.54%   |
| 5.15.79  | 160       | 0.49%   |
| 3.14.39  | 134       | 0.41%   |
| 4.9.14   | 109       | 0.34%   |
| 5.4.40   | 104       | 0.32%   |
| 5.17.11  | 83        | 0.26%   |
| 4.9.34   | 80        | 0.25%   |
| 4.13.0   | 79        | 0.24%   |
| 5.15.77  | 70        | 0.22%   |
| 3.14.15  | 66        | 0.2%    |
| 5.10.150 | 60        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 8436      | 28.74%  |
| 4.1     | 7556      | 25.74%  |
| 4.15    | 4407      | 15.01%  |
| 3.14    | 3541      | 12.06%  |
| 5.10    | 2308      | 7.86%   |
| 5.4     | 1241      | 4.23%   |
| 5.15    | 550       | 1.87%   |
| 4.4     | 150       | 0.51%   |
| 4.13    | 108       | 0.37%   |
| 3.10    | 101       | 0.34%   |
| 5.17    | 84        | 0.29%   |
| 4.8     | 77        | 0.26%   |
| 5.18    | 74        | 0.25%   |
| 5.0     | 57        | 0.19%   |
| 4.0     | 48        | 0.16%   |
| 4.7     | 47        | 0.16%   |
| 4.6     | 46        | 0.16%   |
| 4.16    | 44        | 0.15%   |
| 4.19    | 41        | 0.14%   |
| 4.18    | 40        | 0.14%   |
| 3.18    | 38        | 0.13%   |
| 4.14    | 32        | 0.11%   |
| 6.0     | 31        | 0.11%   |
| 4.3     | 27        | 0.09%   |
| 5.16    | 26        | 0.09%   |
| 4.2     | 26        | 0.09%   |
| 4.5     | 24        | 0.08%   |
| 4.17    | 21        | 0.07%   |
| 6.1     | 19        | 0.06%   |
| 4.11    | 17        | 0.06%   |
| 5.5     | 15        | 0.05%   |
| 4.12    | 15        | 0.05%   |
| 3.0     | 14        | 0.05%   |
| 5.3     | 12        | 0.04%   |
| 5.2     | 12        | 0.04%   |
| 4.10    | 9         | 0.03%   |
| 3.17    | 9         | 0.03%   |
| 5.9     | 7         | 0.02%   |
| 5.8     | 7         | 0.02%   |
| 5.6     | 6         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 19925     | 76.59%  |
| i686    | 6085      | 23.39%  |
| aarch64 | 3         | 0.01%   |
| e2k     | 1         | 0.004%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE4       | 18076     | 66.08%  |
| KDE5       | 6211      | 22.7%   |
| GNOME      | 1355      | 4.95%   |
| LXQt       | 869       | 3.18%   |
| MATE       | 362       | 1.32%   |
| XFCE       | 222       | 0.81%   |
| LXDE       | 164       | 0.6%    |
| Unknown    | 90        | 0.33%   |
| KDE        | 4         | 0.01%   |
| X-Cinnamon | 1         | 0.004%  |
| Cinnamon   | 1         | 0.004%  |
| Budgie     | 1         | 0.004%  |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 23399     | 90.39%  |
| Wayland | 2473      | 9.55%   |
| Tty     | 14        | 0.05%   |
| Unknown | 2         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| KDM     | 18244     | 67.12%  |
| SDDM    | 6742      | 24.81%  |
| GDM     | 1917      | 7.05%   |
| LightDM | 120       | 0.44%   |
| TDM     | 115       | 0.42%   |
| Unknown | 21        | 0.08%   |
| XDM     | 19        | 0.07%   |
| LXDM    | 1         | 0.004%  |
| LDM     | 1         | 0.004%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 21102     | 80.21%  |
| ru_RU       | 4606      | 17.51%  |
| en_US       | 154       | 0.59%   |
| de_DE       | 73        | 0.28%   |
| pl_PL       | 72        | 0.27%   |
| es_ES       | 44        | 0.17%   |
| pt_BR       | 40        | 0.15%   |
| fr_FR       | 35        | 0.13%   |
| en_GB       | 32        | 0.12%   |
| it_IT       | 29        | 0.11%   |
| ru_UA       | 23        | 0.09%   |
| ro_RO       | 9         | 0.03%   |
| pt_PT       | 9         | 0.03%   |
| C           | 6         | 0.02%   |
| es_PE       | 5         | 0.02%   |
| es_MX       | 5         | 0.02%   |
| es_CO       | 5         | 0.02%   |
| tr_TR       | 4         | 0.02%   |
| fr_BE       | 4         | 0.02%   |
| es_AR       | 4         | 0.02%   |
| cs_CZ       | 4         | 0.02%   |
| sk_SK       | 3         | 0.01%   |
| hu_HU       | 3         | 0.01%   |
| en_IN       | 3         | 0.01%   |
| bg_BG       | 3         | 0.01%   |
| ru_BY       | 2         | 0.01%   |
| nl_NL       | 2         | 0.01%   |
| lv_LV       | 2         | 0.01%   |
| lt_LT       | 2         | 0.01%   |
| es_VE       | 2         | 0.01%   |
| da_DK       | 2         | 0.01%   |
| be_BY       | 2         | 0.01%   |
| tt_RU       | 1         | 0.004%  |
| sv_SE       | 1         | 0.004%  |
| sr_RS@latin | 1         | 0.004%  |
| sr_RS       | 1         | 0.004%  |
| sr_ME       | 1         | 0.004%  |
| ru_KZ       | 1         | 0.004%  |
| ja_JP       | 1         | 0.004%  |
| et_EE       | 1         | 0.004%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 20344     | 78.3%   |
| EFI  | 5638      | 21.7%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Unknown  | 16470     | 61.04%  |
| Ext4     | 10001     | 37.06%  |
| Btrfs    | 358       | 1.33%   |
| Ext3     | 67        | 0.25%   |
| Ext2     | 24        | 0.09%   |
| Xfs      | 21        | 0.08%   |
| Aufs     | 14        | 0.05%   |
| F2fs     | 11        | 0.04%   |
| SAMSUNG  | 6         | 0.02%   |
| Reiserfs | 4         | 0.01%   |
| Overlay  | 2         | 0.01%   |
| Jfs      | 1         | 0.004%  |
| Exfat    | 1         | 0.004%  |
| 2G       | 1         | 0.004%  |
| 20G      | 1         | 0.004%  |
| 12G      | 1         | 0.004%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 16189     | 59.17%  |
| GPT     | 5957      | 21.77%  |
| Unknown | 5215      | 19.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 23455     | 89.59%  |
| Yes       | 2724      | 10.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 21358     | 80.41%  |
| Yes       | 5205      | 19.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 6847      | 26.95%  |
| Gigabyte Technology | 2983      | 11.74%  |
| Lenovo              | 2193      | 8.63%   |
| Hewlett-Packard     | 2080      | 8.19%   |
| Acer                | 2050      | 8.07%   |
| MSI                 | 1576      | 6.2%    |
| ASRock              | 1430      | 5.63%   |
| Dell                | 1072      | 4.22%   |
| Samsung Electronics | 917       | 3.61%   |
| Toshiba             | 473       | 1.86%   |
| Intel               | 421       | 1.66%   |
| Sony                | 321       | 1.26%   |
| ECS                 | 289       | 1.14%   |
| Packard Bell        | 261       | 1.03%   |
| Unknown             | 226       | 0.89%   |
| Biostar             | 203       | 0.8%    |
| Pegatron            | 185       | 0.73%   |
| eMachines           | 178       | 0.7%    |
| Foxconn             | 168       | 0.66%   |
| Fujitsu Siemens     | 110       | 0.43%   |
| Apple               | 109       | 0.43%   |
| Notebook            | 101       | 0.4%    |
| Clevo               | 98        | 0.39%   |
| Fujitsu             | 91        | 0.36%   |
| DNS                 | 49        | 0.19%   |
| Quanta              | 42        | 0.17%   |
| Medion              | 37        | 0.15%   |
| WinFast             | 33        | 0.13%   |
| Huanan              | 32        | 0.13%   |
| EPoX Computer       | 32        | 0.13%   |
| DEXP                | 30        | 0.12%   |
| AMI                 | 28        | 0.11%   |
| Supermicro          | 24        | 0.09%   |
| Prestigio           | 24        | 0.09%   |
| Irbis               | 23        | 0.09%   |
| Digma               | 23        | 0.09%   |
| Aquarius            | 23        | 0.09%   |
| IBM                 | 22        | 0.09%   |
| Nvidia              | 18        | 0.07%   |
| ABIT                | 18        | 0.07%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ASUS All Series              | 358       | 1.41%   |
| Unknown                      | 331       | 1.3%    |
| HP Pavilion g6               | 177       | 0.7%    |
| HP Pavilion dv6              | 108       | 0.43%   |
| ASUS M5A78L-M LX3            | 78        | 0.31%   |
| HP Notebook                  | 76        | 0.3%    |
| MSI MS-7817                  | 75        | 0.3%    |
| ASUS M5A97 R2.0              | 68        | 0.27%   |
| ASRock G31M-S                | 66        | 0.26%   |
| Acer Aspire V3-571G          | 66        | 0.26%   |
| Lenovo G570 20079            | 65        | 0.26%   |
| Gigabyte 970A-DS3P           | 62        | 0.24%   |
| ASRock N68C-S UCC            | 60        | 0.24%   |
| MSI MS-7529                  | 56        | 0.22%   |
| Lenovo B590 20206            | 56        | 0.22%   |
| Gigabyte H61M-S1             | 55        | 0.22%   |
| Gigabyte G31M-ES2L           | 55        | 0.22%   |
| MSI MS-7592                  | 53        | 0.21%   |
| HP Pavilion dv7              | 53        | 0.21%   |
| ASUS P5K                     | 53        | 0.21%   |
| Packard Bell EasyNote TE11HC | 52        | 0.2%    |
| Lenovo G50-30 80G0           | 51        | 0.2%    |
| HP Pavilion g7               | 51        | 0.2%    |
| Lenovo G500 20236            | 48        | 0.19%   |
| ASUS P5B                     | 48        | 0.19%   |
| HP Pavilion 15               | 47        | 0.18%   |
| ASUS P8H61-M LX3 R2.0        | 47        | 0.18%   |
| ASUS P5KPL-AM                | 47        | 0.18%   |
| MSI MS-7309                  | 46        | 0.18%   |
| Dell Inspiron N5110          | 46        | 0.18%   |
| ASUS P8Z77-V LX              | 46        | 0.18%   |
| MSI MS-7788                  | 45        | 0.18%   |
| ASUS P5G41T-M LX2/GB         | 45        | 0.18%   |
| ASUS M5A97 LE R2.0           | 45        | 0.18%   |
| Lenovo G50-45 80E3           | 43        | 0.17%   |
| ASUS P5KPL-AM IN/ROEM/SI     | 43        | 0.17%   |
| Acer Aspire 5750G            | 43        | 0.17%   |
| Acer Aspire 5742G            | 42        | 0.17%   |
| Toshiba Satellite C660       | 41        | 0.16%   |
| ASRock G41M-VS3              | 41        | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 1473      | 5.8%    |
| HP Pavilion           | 636       | 2.5%    |
| Dell Inspiron         | 492       | 1.94%   |
| Lenovo IdeaPad        | 488       | 1.92%   |
| Toshiba Satellite     | 429       | 1.69%   |
| ASUS All              | 358       | 1.41%   |
| Lenovo ThinkPad       | 354       | 1.39%   |
| HP Compaq             | 345       | 1.36%   |
| Unknown               | 331       | 1.3%    |
| Packard Bell EasyNote | 206       | 0.81%   |
| ASUS M5A78L-M         | 205       | 0.81%   |
| Dell Latitude         | 201       | 0.79%   |
| HP ProBook            | 190       | 0.75%   |
| ASUS PRIME            | 186       | 0.73%   |
| ASUS P8H61-M          | 185       | 0.73%   |
| Acer Extensa          | 169       | 0.67%   |
| ASUS P5KPL-AM         | 159       | 0.63%   |
| ASUS M5A97            | 155       | 0.61%   |
| Dell OptiPlex         | 139       | 0.55%   |
| ASUS P5K              | 139       | 0.55%   |
| ASUS P8Z77-V          | 131       | 0.52%   |
| ASUS P5G41T-M         | 118       | 0.46%   |
| HP Laptop             | 113       | 0.44%   |
| ASUS P5Q              | 106       | 0.42%   |
| Dell Vostro           | 102       | 0.4%    |
| Lenovo G580           | 100       | 0.39%   |
| HP EliteBook          | 95        | 0.37%   |
| Lenovo B590           | 94        | 0.37%   |
| Acer TravelMate       | 86        | 0.34%   |
| Lenovo ThinkCentre    | 78        | 0.31%   |
| HP Notebook           | 76        | 0.3%    |
| MSI MS-7817           | 75        | 0.3%    |
| ASUS SABERTOOTH       | 68        | 0.27%   |
| Lenovo G570           | 66        | 0.26%   |
| ASUS VivoBook         | 66        | 0.26%   |
| ASRock G31M-S         | 66        | 0.26%   |
| Gigabyte 970A-DS3P    | 63        | 0.25%   |
| ASRock N68C-S         | 62        | 0.24%   |
| HP ENVY               | 58        | 0.23%   |
| MSI MS-7529           | 56        | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 3669      | 14.44%  |
| 2011    | 3376      | 13.29%  |
| 2010    | 2735      | 10.77%  |
| 2009    | 2372      | 9.34%   |
| 2013    | 2198      | 8.65%   |
| 2008    | 2100      | 8.27%   |
| 2007    | 1901      | 7.48%   |
| 2014    | 1341      | 5.28%   |
| 2006    | 1115      | 4.39%   |
| 2015    | 949       | 3.74%   |
| 2016    | 814       | 3.2%    |
| 2018    | 643       | 2.53%   |
| 2017    | 589       | 2.32%   |
| 2005    | 421       | 1.66%   |
| 2019    | 349       | 1.37%   |
| 2020    | 255       | 1%      |
| 2021    | 226       | 0.89%   |
| 2004    | 148       | 0.58%   |
| 2003    | 80        | 0.31%   |
| 2022    | 58        | 0.23%   |
| Unknown | 46        | 0.18%   |
| 2002    | 15        | 0.06%   |
| 2001    | 5         | 0.02%   |
| 2000    | 1         | 0.004%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 12865     | 50.64%  |
| Notebook       | 12065     | 47.49%  |
| All in one     | 238       | 0.94%   |
| Mini pc        | 116       | 0.46%   |
| Tablet         | 55        | 0.22%   |
| Server         | 36        | 0.14%   |
| Convertible    | 25        | 0.1%    |
| System on chip | 3         | 0.01%   |
| Stick pc       | 2         | 0.01%   |
| Other          | 1         | 0.004%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 25404     | 99.98%  |
| Enabled  | 5         | 0.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 25398     | 99.97%  |
| Yes  | 8         | 0.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 8906      | 33.27%  |
| 8.01-16.0       | 4332      | 16.18%  |
| 4.01-8.0        | 4218      | 15.76%  |
| 1.01-2.0        | 3586      | 13.4%   |
| 2.01-3.0        | 2612      | 9.76%   |
| 16.01-24.0      | 1525      | 5.7%    |
| 0.51-1.0        | 748       | 2.79%   |
| Unknown         | 380       | 1.42%   |
| 32.01-64.0      | 297       | 1.11%   |
| 24.01-32.0      | 89        | 0.33%   |
| 0.01-0.5        | 38        | 0.14%   |
| 64.01-256.0     | 35        | 0.13%   |
| More than 256.0 | 3         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 13574     | 46.21%  |
| 1.01-2.0   | 11423     | 38.89%  |
| 2.01-3.0   | 1962      | 6.68%   |
| 0.01-0.5   | 1150      | 3.92%   |
| 3.01-4.0   | 465       | 1.58%   |
| Unknown    | 447       | 1.52%   |
| 4.01-8.0   | 313       | 1.07%   |
| 8.01-16.0  | 34        | 0.12%   |
| 16.01-24.0 | 5         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 17568     | 65.43%  |
| 2       | 6162      | 22.95%  |
| 3       | 1963      | 7.31%   |
| 4       | 608       | 2.26%   |
| 5       | 224       | 0.83%   |
| 0       | 202       | 0.75%   |
| 6       | 78        | 0.29%   |
| 7       | 18        | 0.07%   |
| 8       | 12        | 0.04%   |
| Unknown | 10        | 0.04%   |
| 9       | 5         | 0.02%   |
| 10      | 1         | 0.004%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 17049     | 65.44%  |
| No        | 9002      | 34.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 24616     | 96.84%  |
| No        | 804       | 3.16%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 15357     | 59.73%  |
| No        | 10353     | 40.27%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 16979     | 65.68%  |
| Yes       | 8872      | 34.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Russia      | 14323     | 53.45%  |
| Unknown     | 8003      | 29.87%  |
| Ukraine     | 1080      | 4.03%   |
| Belarus     | 413       | 1.54%   |
| Germany     | 345       | 1.29%   |
| Poland      | 327       | 1.22%   |
| Kazakhstan  | 237       | 0.88%   |
| USA         | 186       | 0.69%   |
| Italy       | 179       | 0.67%   |
| France      | 171       | 0.64%   |
| Brazil      | 125       | 0.47%   |
| Spain       | 106       | 0.4%    |
| Canada      | 76        | 0.28%   |
| UK          | 75        | 0.28%   |
| Moldova     | 68        | 0.25%   |
| Romania     | 65        | 0.24%   |
| Latvia      | 53        | 0.2%    |
| Bulgaria    | 48        | 0.18%   |
| Mexico      | 43        | 0.16%   |
| Serbia      | 40        | 0.15%   |
| Czechia     | 36        | 0.13%   |
| Austria     | 36        | 0.13%   |
| Israel      | 34        | 0.13%   |
| Turkey      | 32        | 0.12%   |
| Estonia     | 31        | 0.12%   |
| Slovakia    | 30        | 0.11%   |
| Belgium     | 29        | 0.11%   |
| Lithuania   | 28        | 0.1%    |
| Australia   | 28        | 0.1%    |
| Netherlands | 26        | 0.1%    |
| Uzbekistan  | 25        | 0.09%   |
| Switzerland | 25        | 0.09%   |
| Finland     | 25        | 0.09%   |
| Colombia    | 23        | 0.09%   |
| India       | 22        | 0.08%   |
| Greece      | 22        | 0.08%   |
| Argentina   | 22        | 0.08%   |
| Sweden      | 20        | 0.07%   |
| Portugal    | 19        | 0.07%   |
| Hungary     | 18        | 0.07%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 8004      | 28.04%  |
| Moscow           | 2295      | 8.04%   |
| St Petersburg    | 971       | 3.4%    |
| Pecherskoye      | 759       | 2.66%   |
| Novosibirsk      | 505       | 1.77%   |
| Krasnodar        | 440       | 1.54%   |
| Yekaterinburg    | 403       | 1.41%   |
| Samara           | 336       | 1.18%   |
| Nizhniy Novgorod | 334       | 1.17%   |
| Rostov-on-Don    | 288       | 1.01%   |
| Chelyabinsk      | 269       | 0.94%   |
| Perm             | 260       | 0.91%   |
| Voronezh         | 249       | 0.87%   |
| Krasnoyarsk      | 214       | 0.75%   |
| Saratov          | 211       | 0.74%   |
| Omsk             | 169       | 0.59%   |
| Volgograd        | 160       | 0.56%   |
| Kazan’         | 159       | 0.56%   |
| Khabarovsk       | 151       | 0.53%   |
| Minsk            | 149       | 0.52%   |
| Tyumen           | 140       | 0.49%   |
| Barnaul          | 138       | 0.48%   |
| Stavropol        | 136       | 0.48%   |
| Ufa              | 130       | 0.46%   |
| Vladivostok      | 120       | 0.42%   |
| Irkutsk          | 117       | 0.41%   |
| Kyiv             | 115       | 0.4%    |
| Kemerovo         | 115       | 0.4%    |
| Yaroslavl        | 112       | 0.39%   |
| Tula             | 104       | 0.36%   |
| Kaliningrad      | 104       | 0.36%   |
| Novokuznetsk     | 100       | 0.35%   |
| Orenburg         | 97        | 0.34%   |
| Bryansk          | 97        | 0.34%   |
| Simferopol       | 96        | 0.34%   |
| Belgorod         | 93        | 0.33%   |
| Kirov            | 89        | 0.31%   |
| Surgut           | 87        | 0.3%    |
| Astrakhan        | 87        | 0.3%    |
| Ryazan           | 85        | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives  | Percent |
|---------------------|-----------|---------|---------|
| Seagate             | 8889      | 13867   | 25.09%  |
| WDC                 | 8398      | 13316   | 23.7%   |
| Hitachi             | 2939      | 4082    | 8.3%    |
| Toshiba             | 2810      | 3942    | 7.93%   |
| Samsung Electronics | 2775      | 4119    | 7.83%   |
| Kingston            | 1383      | 1900    | 3.9%    |
| HGST                | 889       | 1327    | 2.51%   |
| Unknown             | 806       | 1065    | 2.27%   |
| SanDisk             | 537       | 756     | 1.52%   |
| Maxtor              | 470       | 604     | 1.33%   |
| A-DATA Technology   | 381       | 545     | 1.08%   |
| OCZ                 | 371       | 500     | 1.05%   |
| China               | 362       | 482     | 1.02%   |
| SPCC                | 361       | 516     | 1.02%   |
| Intel               | 317       | 483     | 0.89%   |
| Fujitsu             | 306       | 370     | 0.86%   |
| Crucial             | 295       | 406     | 0.83%   |
| HUAWEI              | 285       | 334     | 0.8%    |
| Plextor             | 261       | 389     | 0.74%   |
| Smartbuy            | 167       | 215     | 0.47%   |
| Transcend           | 150       | 212     | 0.42%   |
| Apacer              | 148       | 207     | 0.42%   |
| Corsair             | 134       | 178     | 0.38%   |
| GOODRAM             | 126       | 166     | 0.36%   |
| SK hynix            | 120       | 165     | 0.34%   |
| KingSpec            | 117       | 160     | 0.33%   |
| Patriot             | 111       | 140     | 0.31%   |
| AMD                 | 111       | 136     | 0.31%   |
| TF CARD             | 72        | 94      | 0.2%    |
| KingDian            | 63        | 94      | 0.18%   |
| Micron Technology   | 59        | 74      | 0.17%   |
| Gigabyte Technology | 56        | 73      | 0.16%   |
| Netac               | 49        | 59      | 0.14%   |
| Apple               | 48        | 61      | 0.14%   |
| ZTE                 | 46        | 53      | 0.13%   |
| Kingmax             | 46        | 95      | 0.13%   |
| Silicon Motion      | 38        | 47      | 0.11%   |
| JMicron Technology  | 36        | 38      | 0.1%    |
| Mass                | 34        | Unknown | 0.1%    |
| LITEONIT            | 33        | 49      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 488       | 1.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 418       | 1.08%   |
| Seagate ST500LT012-1DG142 500GB     | 374       | 0.97%   |
| Seagate ST9500325AS 500GB           | 342       | 0.88%   |
| Seagate ST3500418AS 500GB           | 338       | 0.87%   |
| Toshiba MQ01ABF050 500GB            | 295       | 0.76%   |
| Kingston SV300S37A120G 120GB SSD    | 284       | 0.73%   |
| Toshiba DT01ACA050 500GB            | 281       | 0.73%   |
| Seagate ST1000DM003-1CH162 1TB      | 277       | 0.71%   |
| Toshiba DT01ACA100 1TB              | 235       | 0.61%   |
| Seagate ST9320325AS 320GB           | 232       | 0.6%    |
| HGST HTS545050A7E680 500GB          | 223       | 0.58%   |
| Unknown xD/SD/M.S.                  | 207       | 0.53%   |
| Seagate ST3250410AS 250GB           | 190       | 0.49%   |
| Kingston SA400S37120G 120GB SSD     | 184       | 0.47%   |
| Seagate ST500LT012-9WS142 500GB     | 182       | 0.47%   |
| Hitachi HTS543232A7A384 320GB       | 182       | 0.47%   |
| WDC WD5000AAKX-001CA0 500GB         | 181       | 0.47%   |
| Seagate ST380011A 80GB              | 181       | 0.47%   |
| Seagate ST9250315AS 250GB           | 178       | 0.46%   |
| Seagate ST3160815AS 160GB           | 176       | 0.45%   |
| Seagate ST1000DM010-2EP102 1TB      | 167       | 0.43%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 164       | 0.42%   |
| Seagate ST3250310AS 250GB           | 161       | 0.42%   |
| Seagate ST31000528AS 1TB            | 161       | 0.42%   |
| Seagate ST31000524AS 1TB            | 160       | 0.41%   |
| Toshiba HDWD110 1TB                 | 157       | 0.41%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 157       | 0.41%   |
| Toshiba MQ01ABD100 1TB              | 154       | 0.4%    |
| Seagate ST380815AS 80GB             | 154       | 0.4%    |
| Kingston SA400S37240G 240GB SSD     | 144       | 0.37%   |
| Seagate ST320LT020-9YG142 320GB     | 143       | 0.37%   |
| HGST HTS545050A7E380 500GB          | 142       | 0.37%   |
| Seagate ST1000DM003-1ER162 1TB      | 141       | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB            | 140       | 0.36%   |
| HUAWEI TF CARD Storage 16GB         | 135       | 0.35%   |
| HUAWEI SD Storage 8GB               | 134       | 0.35%   |
| Hitachi HTS547550A9E384 500GB       | 133       | 0.34%   |
| Hitachi HDS721050CLA362 500GB       | 132       | 0.34%   |
| HGST HTS541010A9E680 1TB            | 125       | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8864      | 13810  | 33.93%  |
| WDC                 | 8074      | 12702  | 30.9%   |
| Hitachi             | 2939      | 4082   | 11.25%  |
| Toshiba             | 2681      | 3747   | 10.26%  |
| Samsung Electronics | 1727      | 2465   | 6.61%   |
| HGST                | 889       | 1327   | 3.4%    |
| Maxtor              | 468       | 602    | 1.79%   |
| Fujitsu             | 304       | 367    | 1.16%   |
| IBM/Hitachi         | 31        | 36     | 0.12%   |
| Unknown             | 27        | 37     | 0.1%    |
| Apple               | 27        | 34     | 0.1%    |
| ExcelStor           | 12        | 19     | 0.05%   |
| Hewlett-Packard     | 11        | 15     | 0.04%   |
| ASMT                | 9         | 22     | 0.03%   |
| WD MediaMax         | 8         | 12     | 0.03%   |
| IBM                 | 6         | 9      | 0.02%   |
| Quantum             | 5         | 5      | 0.02%   |
| USB3.0              | 4         | 4      | 0.02%   |
| ASMedia             | 4         | 11     | 0.02%   |
| Magnetic Data       | 3         | 3      | 0.01%   |
| HGST HTS            | 3         | 3      | 0.01%   |
| PHD 3.0             | 2         | 2      | 0.01%   |
| JMicron Technology  | 2         | 2      | 0.01%   |
| Intenso             | 2         | 2      | 0.01%   |
| HPE                 | 2         | 2      | 0.01%   |
| CLOVER              | 2         | 2      | 0.01%   |
| Unknown             | 2         | 2      | 0.01%   |
| ZALMAN              | 1         | 1      | 0.004%  |
| USB 3.0             | 1         | 1      | 0.004%  |
| USB                 | 1         | 1      | 0.004%  |
| TPH01204000GB       | 1         | 1      | 0.004%  |
| TPH00100500GB       | 1         | 1      | 0.004%  |
| Speeding            | 1         | 1      | 0.004%  |
| SILICONMOTION       | 1         | 1      | 0.004%  |
| Silicon             | 1         | 1      | 0.004%  |
| SAGE                | 1         | 1      | 0.004%  |
| SABRENT             | 1         | 1      | 0.004%  |
| OEM                 | 1         | 2      | 0.004%  |
| MSCC                | 1         | 1      | 0.004%  |
| MR2020              | 1         | 1      | 0.004%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 1302      | 1786   | 17.8%   |
| Samsung Electronics | 883       | 1342   | 12.07%  |
| SanDisk             | 469       | 671    | 6.41%   |
| WDC                 | 379       | 496    | 5.18%   |
| OCZ                 | 370       | 499    | 5.06%   |
| China               | 361       | 481    | 4.94%   |
| SPCC                | 356       | 509    | 4.87%   |
| A-DATA Technology   | 338       | 467    | 4.62%   |
| Crucial             | 286       | 390    | 3.91%   |
| Intel               | 262       | 402    | 3.58%   |
| Plextor             | 252       | 373    | 3.44%   |
| Smartbuy            | 161       | 208    | 2.2%    |
| Transcend           | 143       | 199    | 1.95%   |
| Apacer              | 139       | 193    | 1.9%    |
| Corsair             | 133       | 176    | 1.82%   |
| GOODRAM             | 123       | 163    | 1.68%   |
| Toshiba             | 117       | 166    | 1.6%    |
| KingSpec            | 117       | 160    | 1.6%    |
| Patriot             | 106       | 135    | 1.45%   |
| AMD                 | 102       | 123    | 1.39%   |
| KingDian            | 62        | 93     | 0.85%   |
| Kingmax             | 46        | 95     | 0.63%   |
| SK hynix            | 41        | 60     | 0.56%   |
| Gigabyte Technology | 41        | 50     | 0.56%   |
| Netac               | 39        | 47     | 0.53%   |
| Micron Technology   | 37        | 48     | 0.51%   |
| LITEONIT            | 33        | 49     | 0.45%   |
| Team                | 27        | 33     | 0.37%   |
| JMicron Technology  | 27        | 30     | 0.37%   |
| LITEON              | 26        | 37     | 0.36%   |
| XrayDisk            | 23        | 30     | 0.31%   |
| OCZ-VERTEX3         | 22        | 33     | 0.3%    |
| KingFast            | 22        | 30     | 0.3%    |
| PNY                 | 20        | 24     | 0.27%   |
| Apple               | 20        | 26     | 0.27%   |
| Foxline             | 19        | 24     | 0.26%   |
| Unknown             | 19        | 21     | 0.26%   |
| Zheino              | 17        | 21     | 0.23%   |
| Intenso             | 17        | 21     | 0.23%   |
| Londisk             | 14        | 16     | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 21974     | 39345  | 71.75%  |
| SSD     | 6522      | 10207  | 21.3%   |
| NVMe    | 817       | 1183   | 2.67%   |
| Unknown | 693       | 832    | 2.26%   |
| MMC     | 619       | 851    | 2.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 24659     | 49142  | 91.05%  |
| SAS  | 998       | 1254   | 3.68%   |
| NVMe | 808       | 1171   | 2.98%   |
| MMC  | 619       | 851    | 2.29%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 21216     | 36814  | 73.21%  |
| 0.51-1.0        | 6440      | 10571  | 22.22%  |
| 1.01-2.0        | 964       | 1588   | 3.33%   |
| 2.01-3.0        | 196       | 299    | 0.68%   |
| 3.01-4.0        | 114       | 192    | 0.39%   |
| 4.01-10.0       | 44        | 82     | 0.15%   |
| 10.01-20.0      | 4         | 5      | 0.01%   |
| More than 100.0 | 1         | 1      | 0.003%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 7376      | 25.17%  |
| 251-500        | 6466      | 22.06%  |
| 1-20           | 4111      | 14.03%  |
| 51-100         | 3378      | 11.53%  |
| 501-1000       | 3147      | 10.74%  |
| 21-50          | 2560      | 8.73%   |
| 1001-2000      | 1270      | 4.33%   |
| Unknown        | 457       | 1.56%   |
| 2001-3000      | 321       | 1.1%    |
| More than 3000 | 222       | 0.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 18950     | 64.81%  |
| 21-50          | 2771      | 9.48%   |
| 101-250        | 2190      | 7.49%   |
| 51-100         | 1881      | 6.43%   |
| 251-500        | 1492      | 5.1%    |
| 501-1000       | 952       | 3.26%   |
| Unknown        | 457       | 1.56%   |
| 1001-2000      | 383       | 1.31%   |
| 2001-3000      | 87        | 0.3%    |
| More than 3000 | 78        | 0.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB          | 246       | 338    | 1.99%   |
| Seagate ST500DM002-1BD142 500GB    | 194       | 257    | 1.57%   |
| Seagate ST500LT012-9WS142 500GB    | 177       | 223    | 1.43%   |
| Seagate ST3500418AS 500GB          | 168       | 230    | 1.36%   |
| Seagate ST9320325AS 320GB          | 136       | 173    | 1.1%    |
| Seagate ST3250410AS 250GB          | 121       | 155    | 0.98%   |
| Seagate ST9250315AS 250GB          | 120       | 149    | 0.97%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 112       | 131    | 0.9%    |
| Seagate ST3250310AS 250GB          | 106       | 160    | 0.86%   |
| HGST HTS545050A7E680 500GB         | 101       | 134    | 0.82%   |
| Seagate ST500LT012-1DG142 500GB    | 99        | 123    | 0.8%    |
| WDC WD5000AAKX-001CA0 500GB        | 98        | 122    | 0.79%   |
| Seagate ST320LT020-9YG142 320GB    | 87        | 122    | 0.7%    |
| Seagate ST3320613AS 320GB          | 82        | 111    | 0.66%   |
| Seagate ST31000528AS 1TB           | 80        | 107    | 0.65%   |
| Hitachi HTS543232A7A384 320GB      | 79        | 97     | 0.64%   |
| Seagate ST3160815AS 160GB          | 70        | 83     | 0.57%   |
| HGST HTS545050A7E380 500GB         | 70        | 110    | 0.57%   |
| Hitachi HTS545025B9A300 250GB      | 68        | 88     | 0.55%   |
| WDC WD5000AADS-00S9B0 500GB        | 65        | 78     | 0.53%   |
| Seagate ST380011A 80GB             | 65        | 74     | 0.53%   |
| Samsung Electronics HD080HJ 80GB   | 65        | 80     | 0.53%   |
| Seagate ST3160811AS 160GB          | 64        | 90     | 0.52%   |
| Seagate ST31000524AS 1TB           | 60        | 87     | 0.48%   |
| Seagate ST1000DM003-1CH162 1TB     | 58        | 85     | 0.47%   |
| Hitachi HDS721616PLA380 160GB      | 58        | 76     | 0.47%   |
| Seagate ST320LT012-9WS14C 320GB    | 57        | 82     | 0.46%   |
| Hitachi HTS541612J9SA00 119GB      | 57        | 71     | 0.46%   |
| Toshiba MQ01ABD050 500GB           | 56        | 71     | 0.45%   |
| Hitachi HTS547550A9E384 500GB      | 56        | 77     | 0.45%   |
| Samsung Electronics HD160JJ 160GB  | 55        | 85     | 0.44%   |
| Seagate ST1000DM003-9YN162 1TB     | 54        | 65     | 0.44%   |
| Hitachi HDS721050CLA362 500GB      | 54        | 68     | 0.44%   |
| Seagate ST3250318AS 249GB          | 53        | 70     | 0.43%   |
| Hitachi HTS547575A9E384 752GB      | 53        | 76     | 0.43%   |
| Hitachi HTS545050B9A300 500GB      | 53        | 75     | 0.43%   |
| Hitachi HDP725050GLA360 500GB      | 53        | 71     | 0.43%   |
| WDC WD3200AAJS-00L7A0 320GB        | 50        | 59     | 0.4%    |
| Seagate ST9500420AS 500GB          | 50        | 72     | 0.4%    |
| Seagate ST3320620AS 320GB          | 50        | 67     | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4065      | 5692   | 34.39%  |
| WDC                 | 2807      | 3901   | 23.75%  |
| Hitachi             | 1592      | 2131   | 13.47%  |
| Samsung Electronics | 926       | 1250   | 7.83%   |
| Toshiba             | 860       | 1131   | 7.28%   |
| HGST                | 292       | 411    | 2.47%   |
| Maxtor              | 279       | 345    | 2.36%   |
| Kingston            | 172       | 213    | 1.46%   |
| Fujitsu             | 129       | 157    | 1.09%   |
| SanDisk             | 81        | 98     | 0.69%   |
| SPCC                | 68        | 86     | 0.58%   |
| OCZ                 | 66        | 93     | 0.56%   |
| Intel               | 59        | 70     | 0.5%    |
| A-DATA Technology   | 49        | 71     | 0.41%   |
| Corsair             | 41        | 51     | 0.35%   |
| Kingmax             | 31        | 57     | 0.26%   |
| Crucial             | 31        | 48     | 0.26%   |
| IBM/Hitachi         | 27        | 32     | 0.23%   |
| China               | 24        | 32     | 0.2%    |
| KingSpec            | 20        | 29     | 0.17%   |
| Plextor             | 18        | 24     | 0.15%   |
| AMD                 | 13        | 17     | 0.11%   |
| SK hynix            | 12        | 17     | 0.1%    |
| LITEONIT            | 12        | 17     | 0.1%    |
| Transcend           | 9         | 11     | 0.08%   |
| OCZ-VERTEX3         | 8         | 15     | 0.07%   |
| ExcelStor           | 8         | 10     | 0.07%   |
| Apple               | 7         | 8      | 0.06%   |
| Micron Technology   | 6         | 11     | 0.05%   |
| Patriot             | 5         | 5      | 0.04%   |
| Netac               | 5         | 6      | 0.04%   |
| Mushkin             | 5         | 5      | 0.04%   |
| IBM                 | 5         | 7      | 0.04%   |
| Unknown             | 5         | 7      | 0.04%   |
| Smartbuy            | 4         | 4      | 0.03%   |
| Apacer              | 4         | 9      | 0.03%   |
| WD MediaMax         | 3         | 5      | 0.03%   |
| Team                | 3         | 3      | 0.03%   |
| SSSTC               | 3         | 4      | 0.03%   |
| Qumo                | 3         | 5      | 0.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4065      | 5692   | 37.16%  |
| WDC                 | 2774      | 3849   | 25.36%  |
| Hitachi             | 1592      | 2131   | 14.55%  |
| Samsung Electronics | 894       | 1212   | 8.17%   |
| Toshiba             | 855       | 1126   | 7.82%   |
| HGST                | 292       | 411    | 2.67%   |
| Maxtor              | 279       | 345    | 2.55%   |
| Fujitsu             | 129       | 157    | 1.18%   |
| IBM/Hitachi         | 27        | 32     | 0.25%   |
| ExcelStor           | 8         | 10     | 0.07%   |
| IBM                 | 5         | 7      | 0.05%   |
| Apple               | 5         | 6      | 0.05%   |
| WD MediaMax         | 3         | 5      | 0.03%   |
| Hewlett-Packard     | 3         | 4      | 0.03%   |
| Quantum             | 2         | 2      | 0.02%   |
| ASMT                | 2         | 4      | 0.02%   |
| TPH00100500GB       | 1         | 1      | 0.01%   |
| MARSHAL             | 1         | 2      | 0.01%   |
| Magnetic Data       | 1         | 1      | 0.01%   |
| HGST HTS            | 1         | 1      | 0.01%   |
| Unknown             | 1         | 1      | 0.01%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10021     | 14999  | 91.99%  |
| SSD  | 856       | 1147   | 7.86%   |
| NVMe | 17        | 22     | 0.16%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB          | 13        | 14     | 3.23%   |
| Seagate ST31000528AS 1TB           | 12        | 14     | 2.99%   |
| Seagate ST9500325AS 500GB          | 7         | 9      | 1.74%   |
| Seagate ST31000524AS 1TB           | 7         | 8      | 1.74%   |
| Samsung Electronics HM321HI 320GB  | 7         | 9      | 1.74%   |
| HGST HTS545050A7E680 500GB         | 7         | 7      | 1.74%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 6         | 7      | 1.49%   |
| Seagate ST3500412AS 500GB          | 6         | 8      | 1.49%   |
| Hitachi HDS721010DLE630 1TB        | 6         | 8      | 1.49%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 5         | 6      | 1.24%   |
| Seagate ST9320325AS 320GB          | 5         | 6      | 1.24%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 5         | 5      | 1.24%   |
| Samsung Electronics HD502HJ 500GB  | 5         | 5      | 1.24%   |
| HGST HTS545050A7E380 500GB         | 5         | 5      | 1.24%   |
| Toshiba MQ01ABD050 500GB           | 4         | 4      | 1%      |
| Toshiba MK6465GSX 640GB            | 4         | 6      | 1%      |
| Seagate ST9250315AS 250GB          | 4         | 4      | 1%      |
| Seagate ST500LT012-1DG142 500GB    | 4         | 4      | 1%      |
| Seagate ST3500410AS 500GB          | 4         | 5      | 1%      |
| Seagate ST31000333AS 1TB           | 4         | 4      | 1%      |
| Samsung Electronics SP0411N 40GB   | 4         | 5      | 1%      |
| Samsung Electronics HD502IJ 500GB  | 4         | 4      | 1%      |
| Samsung Electronics HD322GJ 320GB  | 4         | 5      | 1%      |
| WDC WD5000AAKS-00V1A0 500GB        | 3         | 4      | 0.75%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 3         | 3      | 0.75%   |
| WDC WD3200AAJS-00L7A0 320GB        | 3         | 4      | 0.75%   |
| WDC WD1600BEVS-22RST0 160GB        | 3         | 4      | 0.75%   |
| WDC WD15EARS-00MVWB0 1TB           | 3         | 6      | 0.75%   |
| Toshiba MK3265GSX 320GB            | 3         | 3      | 0.75%   |
| Seagate ST3750528AS 752GB          | 3         | 3      | 0.75%   |
| Seagate ST32000542AS 2TB           | 3         | 5      | 0.75%   |
| Samsung Electronics HM160HI 160GB  | 3         | 3      | 0.75%   |
| Maxtor 6Y080L0 81GB                | 3         | 3      | 0.75%   |
| Hitachi HTS547575A9E384 752GB      | 3         | 3      | 0.75%   |
| Hitachi HTS547550A9E384 500GB      | 3         | 4      | 0.75%   |
| Hitachi HTS545050A7E380 500GB      | 3         | 3      | 0.75%   |
| Hitachi HDS721050DLE630 500GB      | 3         | 3      | 0.75%   |
| HGST HTS721010A9E630 1TB           | 3         | 4      | 0.75%   |
| WDC WD7501AALS-00J7B0 752GB        | 2         | 2      | 0.5%    |
| WDC WD5000BPVT-00HXZT1 500GB       | 2         | 2      | 0.5%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 122       | 149    | 30.42%  |
| WDC                 | 105       | 123    | 26.18%  |
| Samsung Electronics | 63        | 72     | 15.71%  |
| Toshiba             | 38        | 44     | 9.48%   |
| Hitachi             | 38        | 42     | 9.48%   |
| HGST                | 19        | 21     | 4.74%   |
| Maxtor              | 10        | 10     | 2.49%   |
| Fujitsu             | 2         | 2      | 0.5%    |
| Apple               | 2         | 3      | 0.5%    |
| Hewlett-Packard     | 1         | 1      | 0.25%   |
| Corsair             | 1         | 1      | 0.25%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 17672     | 32740  | 57.31%  |
| Malfunc  | 10661     | 16168  | 34.58%  |
| Detected | 2103      | 3042   | 6.82%   |
| Failed   | 398       | 468    | 1.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 17841     | 63.03%  |
| AMD                              | 5409      | 19.11%  |
| Nvidia                           | 1503      | 5.31%   |
| JMicron Technology               | 1087      | 3.84%   |
| Marvell Technology Group         | 590       | 2.08%   |
| ASMedia Technology               | 361       | 1.28%   |
| VIA Technologies                 | 325       | 1.15%   |
| Samsung Electronics              | 230       | 0.81%   |
| Silicon Integrated Systems [SiS] | 188       | 0.66%   |
| SanDisk                          | 91        | 0.32%   |
| Silicon Motion                   | 89        | 0.31%   |
| Kingston Technology Company      | 89        | 0.31%   |
| SK hynix                         | 57        | 0.2%    |
| Silicon Image                    | 55        | 0.19%   |
| Phison Electronics               | 54        | 0.19%   |
| ADATA Technology                 | 47        | 0.17%   |
| Integrated Technology Express    | 42        | 0.15%   |
| Realtek Semiconductor            | 31        | 0.11%   |
| Micron Technology                | 22        | 0.08%   |
| LSI Logic / Symbios Logic        | 19        | 0.07%   |
| Lite-On Technology               | 18        | 0.06%   |
| KIOXIA                           | 18        | 0.06%   |
| ULi Electronics                  | 16        | 0.06%   |
| Toshiba America Info Systems     | 15        | 0.05%   |
| Union Memory (Shenzhen)          | 14        | 0.05%   |
| Micron/Crucial Technology        | 13        | 0.05%   |
| Adaptec                          | 13        | 0.05%   |
| Solid State Storage Technology   | 9         | 0.03%   |
| Promise Technology               | 7         | 0.02%   |
| OCZ Technology Group             | 7         | 0.02%   |
| Netac Technology                 | 7         | 0.02%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 6         | 0.02%   |
| Hewlett-Packard                  | 5         | 0.02%   |
| Shenzhen Longsys Electronics     | 3         | 0.01%   |
| Broadcom / LSI                   | 3         | 0.01%   |
| ATI Technologies                 | 3         | 0.01%   |
| Transcend                        | 2         | 0.01%   |
| Seagate Technology               | 2         | 0.01%   |
| Artop Electronic                 | 2         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 2051      | 5.38%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 2039      | 5.35%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1756      | 4.61%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1695      | 4.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1638      | 4.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1481      | 3.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1216      | 3.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1174      | 3.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 1055      | 2.77%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 845       | 2.22%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 710       | 1.86%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 704       | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 702       | 1.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 669       | 1.75%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 662       | 1.74%   |
| Nvidia MCP61 SATA Controller                                                            | 661       | 1.73%   |
| Nvidia MCP61 IDE                                                                        | 617       | 1.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 601       | 1.58%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 534       | 1.4%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 531       | 1.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 477       | 1.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 433       | 1.14%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 422       | 1.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 421       | 1.1%    |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 421       | 1.1%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 416       | 1.09%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 397       | 1.04%   |
| JMicron JMB368 IDE controller                                                           | 375       | 0.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 360       | 0.94%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 345       | 0.9%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 328       | 0.86%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 319       | 0.84%   |
| AMD SB600 IDE                                                                           | 316       | 0.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 314       | 0.82%   |
| AMD FCH IDE Controller                                                                  | 310       | 0.81%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 308       | 0.81%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 302       | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 267       | 0.7%    |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 232       | 0.61%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 228       | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 17545     | 58.79%  |
| IDE  | 10819     | 36.25%  |
| NVMe | 814       | 2.73%   |
| RAID | 628       | 2.1%    |
| SCSI | 23        | 0.08%   |
| SAS  | 17        | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 18698     | 73.59%  |
| AMD          | 6694      | 26.35%  |
| CentaurHauls | 12        | 0.05%   |
| ARM          | 3         | 0.01%   |
| MBE8C-PC     | 1         | 0.004%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 239       | 0.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 216       | 0.84%   |
| Intel Pentium 4 CPU 3.00GHz                 | 200       | 0.78%   |
| Intel Atom CPU N450 @ 1.66GHz               | 169       | 0.66%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 161       | 0.63%   |
| Intel Atom CPU N270 @ 1.60GHz               | 155       | 0.61%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 154       | 0.6%    |
| Intel Core i5-2410M CPU @ 2.30GHz           | 151       | 0.59%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 151       | 0.59%   |
| AMD Athlon II X2 250 Processor              | 151       | 0.59%   |
| AMD FX-6300 Six-Core Processor              | 145       | 0.57%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 143       | 0.56%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 143       | 0.56%   |
| AMD E-450 APU with Radeon HD Graphics       | 139       | 0.54%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 133       | 0.52%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 130       | 0.51%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 130       | 0.51%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 128       | 0.5%    |
| Intel Core i3-3110M CPU @ 2.40GHz           | 127       | 0.5%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 127       | 0.5%    |
| Intel Core i3-2310M CPU @ 2.10GHz           | 126       | 0.49%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 125       | 0.49%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 123       | 0.48%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 121       | 0.47%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 116       | 0.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 114       | 0.45%   |
| Intel Atom CPU N455 @ 1.66GHz               | 112       | 0.44%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 110       | 0.43%   |
| AMD FX-8350 Eight-Core Processor            | 105       | 0.41%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 104       | 0.41%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 104       | 0.41%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 103       | 0.4%    |
| Intel Atom CPU N570 @ 1.66GHz               | 100       | 0.39%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 99        | 0.39%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 98        | 0.38%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 97        | 0.38%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 89        | 0.35%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 88        | 0.34%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 85        | 0.33%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+  | 85        | 0.33%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 3608      | 14.12%  |
| Intel Core i3           | 2709      | 10.6%   |
| Intel Core 2 Duo        | 2049      | 8.02%   |
| Intel Celeron           | 1909      | 7.47%   |
| Intel Pentium           | 1739      | 6.8%    |
| Intel Core i7           | 1547      | 6.05%   |
| Intel Atom              | 1191      | 4.66%   |
| Intel Pentium Dual-Core | 851       | 3.33%   |
| AMD FX                  | 736       | 2.88%   |
| AMD Athlon 64 X2        | 717       | 2.81%   |
| AMD Athlon II X2        | 510       | 2%      |
| Intel Core 2 Quad       | 468       | 1.83%   |
| Intel Pentium 4         | 458       | 1.79%   |
| Intel Pentium Dual      | 406       | 1.59%   |
| Intel Core 2            | 404       | 1.58%   |
| Intel Xeon              | 396       | 1.55%   |
| AMD A6                  | 349       | 1.37%   |
| AMD A4                  | 328       | 1.28%   |
| AMD A8                  | 321       | 1.26%   |
| AMD Phenom II X4        | 315       | 1.23%   |
| AMD Ryzen 5             | 299       | 1.17%   |
| AMD A10                 | 280       | 1.1%    |
| AMD E                   | 272       | 1.06%   |
| Intel Genuine           | 227       | 0.89%   |
| AMD Athlon II X4        | 216       | 0.85%   |
| AMD E1                  | 176       | 0.69%   |
| Intel Pentium D         | 171       | 0.67%   |
| AMD Athlon II X3        | 164       | 0.64%   |
| AMD Athlon 64           | 160       | 0.63%   |
| Other                   | 149       | 0.58%   |
| Intel Celeron M         | 137       | 0.54%   |
| AMD Ryzen 3             | 122       | 0.48%   |
| AMD Turion 64 X2 Mobile | 117       | 0.46%   |
| Intel Celeron Dual-Core | 114       | 0.45%   |
| AMD Phenom              | 114       | 0.45%   |
| AMD E2                  | 114       | 0.45%   |
| AMD Sempron             | 111       | 0.43%   |
| AMD Ryzen 7             | 111       | 0.43%   |
| AMD Athlon              | 111       | 0.43%   |
| AMD Athlon X4           | 102       | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 15000     | 57.53%  |
| 4       | 5639      | 21.63%  |
| 1       | 2160      | 8.28%   |
| Unknown | 1870      | 7.17%   |
| 6       | 627       | 2.4%    |
| 3       | 445       | 1.71%   |
| 8       | 262       | 1%      |
| 12      | 32        | 0.12%   |
| 10      | 13        | 0.05%   |
| 16      | 8         | 0.03%   |
| 24      | 6         | 0.02%   |
| 20      | 4         | 0.02%   |
| 192     | 2         | 0.01%   |
| 18      | 2         | 0.01%   |
| 120     | 1         | 0.004%  |
| 28      | 1         | 0.004%  |
| 14      | 1         | 0.004%  |
| 5       | 1         | 0.004%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 25230     | 99%     |
| Unknown | 159       | 0.62%   |
| 2       | 86        | 0.34%   |
| 4       | 7         | 0.03%   |
| 8       | 2         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 14680     | 56.31%  |
| 2       | 9522      | 36.52%  |
| Unknown | 1870      | 7.17%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 23881     | 93.06%  |
| 32-bit         | 977       | 3.81%   |
| Unknown        | 626       | 2.44%   |
| 64-bit         | 179       | 0.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 2909      | 11.18%  |
| 0x306a9    | 2379      | 9.15%   |
| 0x1067a    | 2158      | 8.3%    |
| Unknown    | 1713      | 6.58%   |
| 0x306c3    | 1254      | 4.82%   |
| 0x6fd      | 992       | 3.81%   |
| 0x010000c8 | 920       | 3.54%   |
| 0x20655    | 805       | 3.09%   |
| 0x10676    | 607       | 2.33%   |
| 0x106ca    | 540       | 2.08%   |
| 0x06001119 | 512       | 1.97%   |
| 0x30678    | 454       | 1.75%   |
| 0x40651    | 437       | 1.68%   |
| 0x6fb      | 425       | 1.63%   |
| 0x20652    | 331       | 1.27%   |
| 0x506e3    | 330       | 1.27%   |
| 0x6f6      | 281       | 1.08%   |
| 0x03000027 | 266       | 1.02%   |
| 0x906e9    | 251       | 0.96%   |
| 0x106c2    | 248       | 0.95%   |
| 0x05000119 | 239       | 0.92%   |
| 0x10661    | 227       | 0.87%   |
| 0x30661    | 225       | 0.86%   |
| 0x0600084f | 222       | 0.85%   |
| 0x306d4    | 211       | 0.81%   |
| 0x906ea    | 198       | 0.76%   |
| 0x406c4    | 197       | 0.76%   |
| 0x06000852 | 195       | 0.75%   |
| 0x106e5    | 192       | 0.74%   |
| 0x406e3    | 182       | 0.7%    |
| 0x010000b6 | 181       | 0.7%    |
| 0x07030105 | 167       | 0.64%   |
| 0x6f2      | 164       | 0.63%   |
| 0x406c3    | 163       | 0.63%   |
| 0x010000db | 161       | 0.62%   |
| 0xf41      | 140       | 0.54%   |
| 0xf49      | 133       | 0.51%   |
| 0x06003106 | 133       | 0.51%   |
| 0x6e8      | 132       | 0.51%   |
| 0x806e9    | 123       | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 2979      | 11.64%  |
| Penryn           | 2778      | 10.85%  |
| IvyBridge        | 2437      | 9.52%   |
| Core             | 2287      | 8.93%   |
| K10              | 1850      | 7.23%   |
| Haswell          | 1762      | 6.88%   |
| Westmere         | 1177      | 4.6%    |
| K8 Hammer        | 1129      | 4.41%   |
| Piledriver       | 1108      | 4.33%   |
| Bonnell          | 957       | 3.74%   |
| Silvermont       | 891       | 3.48%   |
| KabyLake         | 816       | 3.19%   |
| NetBurst         | 814       | 3.18%   |
| Skylake          | 541       | 2.11%   |
| Bobcat           | 475       | 1.86%   |
| Unknown          | 417       | 1.63%   |
| P6               | 339       | 1.32%   |
| K10 Llano        | 322       | 1.26%   |
| Nehalem          | 267       | 1.04%   |
| Broadwell        | 228       | 0.89%   |
| Puma             | 215       | 0.84%   |
| Zen              | 211       | 0.82%   |
| Zen+             | 201       | 0.79%   |
| Bulldozer        | 191       | 0.75%   |
| Excavator        | 186       | 0.73%   |
| Jaguar           | 178       | 0.7%    |
| Steamroller      | 152       | 0.59%   |
| K8 & K10 hybrid  | 120       | 0.47%   |
| Zen 2            | 115       | 0.45%   |
| Goldmont plus    | 95        | 0.37%   |
| Goldmont         | 92        | 0.36%   |
| CometLake        | 86        | 0.34%   |
| Zen 3            | 68        | 0.27%   |
| Icelake          | 39        | 0.15%   |
| TigerLake        | 31        | 0.12%   |
| K6               | 26        | 0.1%    |
| Tremont          | 14        | 0.05%   |
| Alderlake Hybrid | 5         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 11024     | 37.64%  |
| Nvidia                           | 10587     | 36.15%  |
| AMD                              | 7519      | 25.67%  |
| Silicon Integrated Systems [SiS] | 61        | 0.21%   |
| VIA Technologies                 | 48        | 0.16%   |
| Matrox Electronics Systems       | 20        | 0.07%   |
| ASPEED Technology                | 16        | 0.05%   |
| ATI Technologies                 | 7         | 0.02%   |
| S3 Graphics                      | 5         | 0.02%   |
| Zhaoxin                          | 1         | 0.003%  |
| Trident Microsystems             | 1         | 0.003%  |
| Huawei Technologies              | 1         | 0.003%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 2046      | 6.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1385      | 4.4%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 582       | 1.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 569       | 1.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 520       | 1.65%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 509       | 1.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 436       | 1.39%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 422       | 1.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 376       | 1.19%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 374       | 1.19%   |
| Nvidia GT218 [GeForce 210]                                                               | 373       | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 367       | 1.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 366       | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 366       | 1.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 320       | 1.02%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 280       | 0.89%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 276       | 0.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 274       | 0.87%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 249       | 0.79%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 244       | 0.78%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 238       | 0.76%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 236       | 0.75%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 228       | 0.72%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 218       | 0.69%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 216       | 0.69%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 215       | 0.68%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 212       | 0.67%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 210       | 0.67%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 207       | 0.66%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 198       | 0.63%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 194       | 0.62%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 192       | 0.61%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 186       | 0.59%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 179       | 0.57%   |
| Intel HD Graphics 5500                                                                   | 172       | 0.55%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 170       | 0.54%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 167       | 0.53%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 167       | 0.53%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 165       | 0.52%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 165       | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| 1 x Nvidia                    | 7891      | 30.59%  |
| 1 x Intel                     | 7553      | 29.28%  |
| 1 x AMD                       | 5750      | 22.29%  |
| Intel + Nvidia                | 2607      | 10.1%   |
| 2 x AMD                       | 1058      | 4.1%    |
| Intel + AMD                   | 672       | 2.6%    |
| 1 x SiS                       | 61        | 0.24%   |
| AMD + Nvidia                  | 60        | 0.23%   |
| 1 x VIA                       | 48        | 0.19%   |
| 2 x Nvidia                    | 33        | 0.13%   |
| 1 x Matrox                    | 17        | 0.07%   |
| Other                         | 15        | 0.06%   |
| 1 x ASPEED                    | 9         | 0.03%   |
| 1 x S3 Graphics               | 4         | 0.02%   |
| AMD + ASPEED                  | 4         | 0.02%   |
| 3 x AMD                       | 3         | 0.01%   |
| Nvidia + Matrox               | 3         | 0.01%   |
| 3 x Nvidia                    | 2         | 0.01%   |
| Nvidia + ASPEED               | 2         | 0.01%   |
| 2 x AMD + 1 x Nvidia          | 1         | 0.004%  |
| 1 x Zhaoxin                   | 1         | 0.004%  |
| 1 x Trident Microsystems      | 1         | 0.004%  |
| Intel + 2 x Nvidia            | 1         | 0.004%  |
| Intel + SiS + 1 x S3 Graphics | 1         | 0.004%  |
| Intel + ASPEED                | 1         | 0.004%  |
| 1 x Huawei Technologies       | 1         | 0.004%  |
| AMD + 2 x Nvidia              | 1         | 0.004%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 21583     | 80.57%  |
| Proprietary | 3655      | 13.64%  |
| Unknown     | 1551      | 5.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 8319      | 30.7%   |
| 0.01-0.5   | 7243      | 26.73%  |
| Unknown    | 5740      | 21.18%  |
| 0.51-1.0   | 3921      | 14.47%  |
| 3.01-4.0   | 1370      | 5.06%   |
| 7.01-8.0   | 195       | 0.72%   |
| 2.01-3.0   | 160       | 0.59%   |
| 5.01-6.0   | 121       | 0.45%   |
| 8.01-16.0  | 29        | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 5538      | 21.92%  |
| AU Optronics            | 2778      | 10.99%  |
| LG Display              | 2220      | 8.79%   |
| Goldstar                | 2201      | 8.71%   |
| Acer                    | 1499      | 5.93%   |
| Chi Mei Optoelectronics | 1173      | 4.64%   |
| BenQ                    | 1065      | 4.21%   |
| Chimei Innolux          | 967       | 3.83%   |
| Philips                 | 876       | 3.47%   |
| BOE                     | 641       | 2.54%   |
| ViewSonic               | 615       | 2.43%   |
| Dell                    | 551       | 2.18%   |
| Ancor Communications    | 528       | 2.09%   |
| AOC                     | 471       | 1.86%   |
| Hewlett-Packard         | 422       | 1.67%   |
| LG Philips              | 418       | 1.65%   |
| Lenovo                  | 391       | 1.55%   |
| HannStar                | 320       | 1.27%   |
| NEC Computers           | 313       | 1.24%   |
| Sony                    | 208       | 0.82%   |
| CPT                     | 181       | 0.72%   |
| Iiyama                  | 140       | 0.55%   |
| InfoVision              | 126       | 0.5%    |
| Apple                   | 107       | 0.42%   |
| Plain Tree Systems      | 79        | 0.31%   |
| Toshiba                 | 76        | 0.3%    |
| Envision Peripherals    | 58        | 0.23%   |
| Fujitsu Siemens         | 55        | 0.22%   |
| Unknown                 | 50        | 0.2%    |
| InnoLux Display         | 50        | 0.2%    |
| Quanta Display          | 48        | 0.19%   |
| Packard Bell            | 48        | 0.19%   |
| Sharp                   | 45        | 0.18%   |
| ___                     | 42        | 0.17%   |
| Panasonic               | 40        | 0.16%   |
| MiTAC                   | 40        | 0.16%   |
| ASUSTek Computer        | 35        | 0.14%   |
| PANDA                   | 31        | 0.12%   |
| Belinea                 | 29        | 0.11%   |
| Hitachi                 | 26        | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 337       | 1.31%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 306       | 1.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 242       | 0.94%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 211       | 0.82%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch      | 154       | 0.6%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 133       | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 128       | 0.5%    |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch                  | 120       | 0.47%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 116       | 0.45%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch      | 113       | 0.44%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 105       | 0.41%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 104       | 0.4%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch      | 103       | 0.4%    |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch      | 96        | 0.37%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch      | 96        | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 95        | 0.37%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 220x130mm 10.1-inch             | 95        | 0.37%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                   | 92        | 0.36%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 89        | 0.35%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch      | 78        | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 75        | 0.29%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 75        | 0.29%   |
| Acer AL1716A ACRAD46 1280x1024 338x270mm 17.0-inch                        | 71        | 0.28%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 69        | 0.27%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 68        | 0.26%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 66        | 0.26%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                       | 66        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 65        | 0.25%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch               | 62        | 0.24%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 62        | 0.24%   |
| AU Optronics LCD Monitor AUO139E 1600x900 380x210mm 17.1-inch             | 60        | 0.23%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                  | 58        | 0.23%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                       | 57        | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 57        | 0.22%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch             | 57        | 0.22%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch      | 56        | 0.22%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                   | 55        | 0.21%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch               | 55        | 0.21%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 55        | 0.21%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch             | 55        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 7063      | 28.23%  |
| 1920x1080 (FHD)    | 6984      | 27.91%  |
| 1280x1024 (SXGA)   | 3239      | 12.94%  |
| 1600x900 (HD+)     | 1562      | 6.24%   |
| 1280x800 (WXGA)    | 1285      | 5.14%   |
| 1440x900 (WXGA+)   | 1121      | 4.48%   |
| 1680x1050 (WSXGA+) | 1100      | 4.4%    |
| 1024x600           | 589       | 2.35%   |
| 1920x1200 (WUXGA)  | 361       | 1.44%   |
| 3840x2160 (4K)     | 302       | 1.21%   |
| 1024x768 (XGA)     | 290       | 1.16%   |
| 1360x768           | 283       | 1.13%   |
| 2560x1440 (QHD)    | 199       | 0.8%    |
| 1600x1200          | 151       | 0.6%    |
| 2560x1080          | 96        | 0.38%   |
| 1920x540           | 64        | 0.26%   |
| 1280x720 (HD)      | 59        | 0.24%   |
| 1400x1050          | 48        | 0.19%   |
| 1152x864           | 38        | 0.15%   |
| 2288x1287          | 24        | 0.1%    |
| 3440x1440          | 23        | 0.09%   |
| 1680x945           | 20        | 0.08%   |
| 2560x1600          | 17        | 0.07%   |
| 2048x1536          | 16        | 0.06%   |
| 2048x1152          | 13        | 0.05%   |
| 1920x1440          | 12        | 0.05%   |
| 1280x960           | 12        | 0.05%   |
| 2160x1440          | 8         | 0.03%   |
| 1280x768           | 8         | 0.03%   |
| 1024x576           | 8         | 0.03%   |
| 2880x1800          | 4         | 0.02%   |
| 4093x4093          | 3         | 0.01%   |
| 3200x1800 (QHD+)   | 3         | 0.01%   |
| 2880x1920          | 3         | 0.01%   |
| 2736x1824          | 3         | 0.01%   |
| Unknown            | 2         | 0.01%   |
| 832x624            | 1         | 0.004%  |
| 640x480            | 1         | 0.004%  |
| 3840x2560          | 1         | 0.004%  |
| 3840x1200          | 1         | 0.004%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 7869      | 31.02%  |
| 17      | 2769      | 10.92%  |
| 19      | 2286      | 9.01%   |
| 21      | 2233      | 8.8%    |
| 23      | 1852      | 7.3%    |
| 24      | 1082      | 4.27%   |
| 18      | 997       | 3.93%   |
| 14      | 856       | 3.37%   |
| 20      | 811       | 3.2%    |
| 13      | 663       | 2.61%   |
| 27      | 653       | 2.57%   |
| 22      | 629       | 2.48%   |
| 10      | 612       | 2.41%   |
| 11      | 317       | 1.25%   |
| 12      | 264       | 1.04%   |
| Unknown | 195       | 0.77%   |
| 31      | 162       | 0.64%   |
| 72      | 126       | 0.5%    |
| 54      | 121       | 0.48%   |
| 40      | 101       | 0.4%    |
| 16      | 98        | 0.39%   |
| 32      | 93        | 0.37%   |
| 34      | 87        | 0.34%   |
| 52      | 58        | 0.23%   |
| 26      | 56        | 0.22%   |
| 25      | 53        | 0.21%   |
| 84      | 50        | 0.2%    |
| 46      | 43        | 0.17%   |
| 8       | 34        | 0.13%   |
| 48      | 30        | 0.12%   |
| 42      | 22        | 0.09%   |
| 43      | 17        | 0.07%   |
| 28      | 14        | 0.06%   |
| 37      | 12        | 0.05%   |
| 55      | 10        | 0.04%   |
| 29      | 10        | 0.04%   |
| 33      | 9         | 0.04%   |
| 65      | 8         | 0.03%   |
| 47      | 7         | 0.03%   |
| 50      | 6         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 10298     | 40.98%  |
| 401-500        | 5382      | 21.42%  |
| 501-600        | 3495      | 13.91%  |
| 351-400        | 3034      | 12.07%  |
| 201-300        | 1620      | 6.45%   |
| 1001-1500      | 297       | 1.18%   |
| 601-700        | 224       | 0.89%   |
| Unknown        | 195       | 0.78%   |
| 701-800        | 192       | 0.76%   |
| 1501-2000      | 181       | 0.72%   |
| 801-900        | 122       | 0.49%   |
| 901-1000       | 43        | 0.17%   |
| 101-200        | 36        | 0.14%   |
| More than 2000 | 9         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 16599     | 67.52%  |
| 16/10   | 3754      | 15.27%  |
| 5/4     | 3043      | 12.38%  |
| 4/3     | 808       | 3.29%   |
| 3/2     | 188       | 0.76%   |
| 21/9    | 94        | 0.38%   |
| 6/5     | 57        | 0.23%   |
| Unknown | 21        | 0.09%   |
| 32/9    | 11        | 0.04%   |
| 1.00    | 5         | 0.02%   |
| 2.21    | 1         | 0.004%  |
| 2.00    | 1         | 0.004%  |
| 1.96    | 1         | 0.004%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 7603      | 30.12%  |
| 201-250        | 4965      | 19.67%  |
| 151-200        | 3763      | 14.91%  |
| 141-150        | 2329      | 9.23%   |
| 81-90          | 1139      | 4.51%   |
| 121-130        | 917       | 3.63%   |
| 301-350        | 696       | 2.76%   |
| 41-50          | 615       | 2.44%   |
| More than 1000 | 434       | 1.72%   |
| 251-300        | 365       | 1.45%   |
| 351-500        | 353       | 1.4%    |
| 131-140        | 335       | 1.33%   |
| 71-80          | 331       | 1.31%   |
| 51-60          | 317       | 1.26%   |
| 111-120        | 244       | 0.97%   |
| 61-70          | 239       | 0.95%   |
| 501-1000       | 228       | 0.9%    |
| Unknown        | 195       | 0.77%   |
| 91-100         | 140       | 0.55%   |
| 1-40           | 36        | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 12186     | 49.36%  |
| 101-120       | 9384      | 38.01%  |
| 121-160       | 2173      | 8.8%    |
| 1-50          | 559       | 2.26%   |
| Unknown       | 195       | 0.79%   |
| 161-240       | 164       | 0.66%   |
| More than 240 | 26        | 0.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 23875     | 92.31%  |
| 2     | 1405      | 5.43%   |
| 0     | 541       | 2.09%   |
| 3     | 43        | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 15543     | 39.88%  |
| Qualcomm Atheros                       | 7872      | 20.2%   |
| Intel                                  | 4460      | 11.44%  |
| Broadcom                               | 2866      | 7.35%   |
| Nvidia                                 | 1238      | 3.18%   |
| Marvell Technology Group               | 1040      | 2.67%   |
| Broadcom Limited                       | 820       | 2.1%    |
| Ralink                                 | 817       | 2.1%    |
| Huawei Technologies                    | 652       | 1.67%   |
| Ralink Technology                      | 585       | 1.5%    |
| VIA Technologies                       | 317       | 0.81%   |
| Qualcomm Atheros Communications        | 239       | 0.61%   |
| D-Link System                          | 207       | 0.53%   |
| D-Link                                 | 190       | 0.49%   |
| JMicron Technology                     | 175       | 0.45%   |
| TP-Link                                | 165       | 0.42%   |
| ASUSTek Computer                       | 164       | 0.42%   |
| Attansic Technology                    | 151       | 0.39%   |
| MediaTek                               | 135       | 0.35%   |
| ZTE WCDMA Technologies MSM             | 134       | 0.34%   |
| Silicon Integrated Systems [SiS]       | 131       | 0.34%   |
| Samsung Electronics                    | 86        | 0.22%   |
| Xiaomi                                 | 74        | 0.19%   |
| Sundance Technology Inc / IC Plus      | 66        | 0.17%   |
| HTC (High Tech Computer)               | 57        | 0.15%   |
| Gemtek                                 | 48        | 0.12%   |
| 3Com                                   | 46        | 0.12%   |
| NetGear                                | 45        | 0.12%   |
| Ericsson Business Mobile Networks      | 39        | 0.1%    |
| Qualcomm                               | 26        | 0.07%   |
| ASIX Electronics                       | 24        | 0.06%   |
| Hewlett-Packard                        | 23        | 0.06%   |
| T & A Mobile Phones                    | 22        | 0.06%   |
| LSI                                    | 22        | 0.06%   |
| IMC Networks                           | 22        | 0.06%   |
| Microsoft                              | 20        | 0.05%   |
| ZyXEL Communications                   | 19        | 0.05%   |
| Sony Ericsson Mobile Communications AB | 19        | 0.05%   |
| Lenovo                                 | 17        | 0.04%   |
| GCT Semiconductor                      | 16        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 11025     | 25.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 2844      | 6.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1985      | 4.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1199      | 2.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 859       | 1.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 858       | 1.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 727       | 1.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 587       | 1.35%   |
| Nvidia MCP61 Ethernet                                                   | 586       | 1.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 581       | 1.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 498       | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 451       | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                           | 384       | 0.89%   |
| Huawei Modem/Networkcard                                                | 361       | 0.83%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 323       | 0.75%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 319       | 0.74%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 316       | 0.73%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 290       | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 286       | 0.66%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 282       | 0.65%   |
| Ralink MT7601U Wireless Adapter                                         | 281       | 0.65%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                           | 275       | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 269       | 0.62%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 265       | 0.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 260       | 0.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 254       | 0.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 252       | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 248       | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 236       | 0.54%   |
| Intel 82579V Gigabit Network Connection                                 | 230       | 0.53%   |
| Intel WiFi Link 5100                                                    | 222       | 0.51%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 210       | 0.48%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 195       | 0.45%   |
| Qualcomm Atheros AR9271 802.11n                                         | 193       | 0.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 189       | 0.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 176       | 0.41%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 172       | 0.4%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 168       | 0.39%   |
| Intel Wireless 7260                                                     | 164       | 0.38%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                 | 162       | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Qualcomm Atheros                  | 5703      | 35.87%  |
| Intel                             | 2978      | 18.73%  |
| Realtek Semiconductor             | 2321      | 14.6%   |
| Broadcom                          | 1959      | 12.32%  |
| Ralink                            | 817       | 5.14%   |
| Ralink Technology                 | 585       | 3.68%   |
| Broadcom Limited                  | 369       | 2.32%   |
| Qualcomm Atheros Communications   | 239       | 1.5%    |
| D-Link                            | 182       | 1.14%   |
| TP-Link                           | 161       | 1.01%   |
| ASUSTek Computer                  | 147       | 0.92%   |
| D-Link System                     | 113       | 0.71%   |
| MediaTek                          | 66        | 0.42%   |
| NetGear                           | 44        | 0.28%   |
| IMC Networks                      | 22        | 0.14%   |
| Microsoft                         | 19        | 0.12%   |
| ZyXEL Communications              | 15        | 0.09%   |
| Edimax Technology                 | 13        | 0.08%   |
| Belkin Components                 | 12        | 0.08%   |
| Mercucys                          | 11        | 0.07%   |
| Linksys                           | 10        | 0.06%   |
| Sierra Wireless                   | 9         | 0.06%   |
| Marvell Technology Group          | 8         | 0.05%   |
| Dell                              | 8         | 0.05%   |
| ZyDAS                             | 7         | 0.04%   |
| Micro Star International          | 6         | 0.04%   |
| Gemtek                            | 6         | 0.04%   |
| Tenda                             | 5         | 0.03%   |
| Sitecom Europe                    | 5         | 0.03%   |
| Sagem                             | 5         | 0.03%   |
| Hewlett-Packard                   | 5         | 0.03%   |
| TRENDnet                          | 4         | 0.03%   |
| Fujitsu Siemens Computers         | 4         | 0.03%   |
| Ericsson Business Mobile Networks | 4         | 0.03%   |
| Accton Technology                 | 4         | 0.03%   |
| Xiaomi                            | 3         | 0.02%   |
| VIA Technologies                  | 3         | 0.02%   |
| Texas Instruments                 | 3         | 0.02%   |
| Qualcomm                          | 3         | 0.02%   |
| BUFFALO                           | 3         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1985      | 12.39%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1199      | 7.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 859       | 5.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 727       | 4.54%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 587       | 3.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 498       | 3.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 451       | 2.82%   |
| Broadcom BCM43142 802.11b/g/n                                           | 384       | 2.4%    |
| Ralink MT7601U Wireless Adapter                                         | 281       | 1.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 269       | 1.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 265       | 1.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 252       | 1.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 248       | 1.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 236       | 1.47%   |
| Intel WiFi Link 5100                                                    | 222       | 1.39%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 210       | 1.31%   |
| Qualcomm Atheros AR9271 802.11n                                         | 193       | 1.2%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 189       | 1.18%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 172       | 1.07%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 168       | 1.05%   |
| Intel Wireless 7260                                                     | 164       | 1.02%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 159       | 0.99%   |
| Intel Centrino Wireless-N 130                                           | 159       | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 141       | 0.88%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 140       | 0.87%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 135       | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 134       | 0.84%   |
| Intel Wireless 7265                                                     | 132       | 0.82%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 132       | 0.82%   |
| Ralink RT5370 Wireless Adapter                                          | 129       | 0.81%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 127       | 0.79%   |
| Intel Centrino Wireless-N 2230                                          | 126       | 0.79%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 112       | 0.7%    |
| Intel Wireless 3165                                                     | 105       | 0.66%   |
| Intel WiMAX/WiFi Link 5150                                              | 101       | 0.63%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 98        | 0.61%   |
| Intel Centrino Wireless-N 100                                           | 93        | 0.58%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 91        | 0.57%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 85        | 0.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 83        | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 14873     | 56.83%  |
| Qualcomm Atheros                       | 3288      | 12.56%  |
| Intel                                  | 2214      | 8.46%   |
| Nvidia                                 | 1237      | 4.73%   |
| Broadcom                               | 1191      | 4.55%   |
| Marvell Technology Group               | 1033      | 3.95%   |
| Broadcom Limited                       | 468       | 1.79%   |
| VIA Technologies                       | 306       | 1.17%   |
| JMicron Technology                     | 175       | 0.67%   |
| Huawei Technologies                    | 151       | 0.58%   |
| Attansic Technology                    | 151       | 0.58%   |
| Silicon Integrated Systems [SiS]       | 128       | 0.49%   |
| ZTE WCDMA Technologies MSM             | 123       | 0.47%   |
| D-Link System                          | 95        | 0.36%   |
| Samsung Electronics                    | 82        | 0.31%   |
| Xiaomi                                 | 71        | 0.27%   |
| Sundance Technology Inc / IC Plus      | 66        | 0.25%   |
| MediaTek                               | 66        | 0.25%   |
| HTC (High Tech Computer)               | 57        | 0.22%   |
| 3Com                                   | 46        | 0.18%   |
| Gemtek                                 | 42        | 0.16%   |
| ASIX Electronics                       | 24        | 0.09%   |
| Qualcomm                               | 23        | 0.09%   |
| T & A Mobile Phones                    | 19        | 0.07%   |
| ASUSTek Computer                       | 18        | 0.07%   |
| Sony Ericsson Mobile Communications AB | 17        | 0.06%   |
| GCT Semiconductor                      | 16        | 0.06%   |
| Vimtron Electronics                    | 15        | 0.06%   |
| Spreadtrum Communications              | 15        | 0.06%   |
| Lenovo                                 | 15        | 0.06%   |
| NTmore                                 | 14        | 0.05%   |
| ICS Advent                             | 9         | 0.03%   |
| ULi Electronics                        | 8         | 0.03%   |
| Davicom Semiconductor                  | 8         | 0.03%   |
| D-Link                                 | 8         | 0.03%   |
| Motorola PCS                           | 7         | 0.03%   |
| ADMtek                                 | 7         | 0.03%   |
| OPPO Electronics                       | 6         | 0.02%   |
| LG Electronics                         | 6         | 0.02%   |
| Android                                | 6         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 11025     | 41.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2844      | 10.73%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 858       | 3.24%   |
| Nvidia MCP61 Ethernet                                             | 586       | 2.21%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 581       | 2.19%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 323       | 1.22%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 319       | 1.2%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 316       | 1.19%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 290       | 1.09%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 286       | 1.08%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 282       | 1.06%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 275       | 1.04%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 260       | 0.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 254       | 0.96%   |
| Intel 82579V Gigabit Network Connection                           | 230       | 0.87%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 195       | 0.74%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 176       | 0.66%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 162       | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 159       | 0.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 158       | 0.6%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 157       | 0.59%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 151       | 0.57%   |
| Intel Ethernet Connection (2) I219-V                              | 150       | 0.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 144       | 0.54%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 142       | 0.54%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 130       | 0.49%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 130       | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 121       | 0.46%   |
| Intel WiMAX Connection 2400m                                      | 120       | 0.45%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 119       | 0.45%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 115       | 0.43%   |
| Nvidia MCP77 Ethernet                                             | 115       | 0.43%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 112       | 0.42%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 112       | 0.42%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 108       | 0.41%   |
| Nvidia CK804 Ethernet Controller                                  | 108       | 0.41%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 108       | 0.41%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                     | 106       | 0.4%    |
| Nvidia MCP51 Ethernet Controller                                  | 104       | 0.39%   |
| Intel I211 Gigabit Network Connection                             | 104       | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 24598     | 60.36%  |
| WiFi     | 15354     | 37.67%  |
| Modem    | 769       | 1.89%   |
| Unknown  | 34        | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 13694     | 52.81%  |
| WiFi     | 12222     | 47.13%  |
| Unknown  | 10        | 0.04%   |
| Modem    | 4         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 13733     | 53.71%  |
| 1     | 11322     | 44.28%  |
| 0     | 329       | 1.29%   |
| 3     | 161       | 0.63%   |
| 4     | 17        | 0.07%   |
| 6     | 2         | 0.01%   |
| 33    | 1         | 0.004%  |
| 16    | 1         | 0.004%  |
| 11    | 1         | 0.004%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 18502     | 69.25%  |
| Unknown | 8003      | 29.95%  |
| Yes     | 212       | 0.79%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 1372      | 15.28%  |
| Intel                           | 1297      | 14.44%  |
| Broadcom                        | 1034      | 11.51%  |
| Realtek Semiconductor           | 831       | 9.25%   |
| Cambridge Silicon Radio         | 738       | 8.22%   |
| IMC Networks                    | 595       | 6.63%   |
| Lite-On Technology              | 579       | 6.45%   |
| Foxconn / Hon Hai               | 572       | 6.37%   |
| ASUSTek Computer                | 406       | 4.52%   |
| Ralink                          | 265       | 2.95%   |
| Hewlett-Packard                 | 227       | 2.53%   |
| Toshiba                         | 226       | 2.52%   |
| Dell                            | 192       | 2.14%   |
| Foxconn International           | 179       | 1.99%   |
| Apple                           | 111       | 1.24%   |
| Alps Electric                   | 74        | 0.82%   |
| Ralink Technology               | 61        | 0.68%   |
| Integrated System Solution      | 57        | 0.63%   |
| MediaTek                        | 24        | 0.27%   |
| Chicony Electronics             | 21        | 0.23%   |
| Micro Star International        | 18        | 0.2%    |
| Taiyo Yuden                     | 15        | 0.17%   |
| Askey Computer                  | 12        | 0.13%   |
| Realtek                         | 10        | 0.11%   |
| USI                             | 9         | 0.1%    |
| Qcom                            | 9         | 0.1%    |
| TP-Link                         | 8         | 0.09%   |
| Roper                           | 8         | 0.09%   |
| Conwise Technology              | 6         | 0.07%   |
| Syntek                          | 4         | 0.04%   |
| Logitech                        | 4         | 0.04%   |
| Samsung Electronics             | 3         | 0.03%   |
| Belkin Components               | 3         | 0.03%   |
| Unknown                         | 2         | 0.02%   |
| Qualcomm Atheros                | 1         | 0.01%   |
| Primax Electronics              | 1         | 0.01%   |
| Opticis                         | 1         | 0.01%   |
| Marvell Semiconductor           | 1         | 0.01%   |
| Fujitsu                         | 1         | 0.01%   |
| D-Link                          | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 738       | 8.21%   |
| Intel Bluetooth wireless interface                                                  | 572       | 6.37%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 527       | 5.86%   |
| Realtek Bluetooth Radio                                                             | 452       | 5.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 343       | 3.82%   |
| Ralink RT3290 Bluetooth                                                             | 265       | 2.95%   |
| Lite-On Bluetooth Device                                                            | 230       | 2.56%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 228       | 2.54%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 207       | 2.3%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 199       | 2.21%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 197       | 2.19%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 195       | 2.17%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 177       | 1.97%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 173       | 1.93%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 162       | 1.8%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 152       | 1.69%   |
| Broadcom BCM2045 Bluetooth                                                          | 147       | 1.64%   |
| Realtek RTL8723B Bluetooth                                                          | 136       | 1.51%   |
| IMC Networks Bluetooth Device                                                       | 128       | 1.42%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 126       | 1.4%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 118       | 1.31%   |
| Qualcomm Atheros Bluetooth                                                          | 101       | 1.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 100       | 1.11%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 98        | 1.09%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 95        | 1.06%   |
| Toshiba Integrated Bluetooth HCI                                                    | 89        | 0.99%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 89        | 0.99%   |
| Broadcom HP Portable Valentine                                                      | 84        | 0.93%   |
| IMC Networks Bluetooth Radio                                                        | 83        | 0.92%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 82        | 0.91%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 80        | 0.89%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 78        | 0.87%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 76        | 0.85%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 72        | 0.8%    |
| IMC Networks Bluetooth module                                                       | 70        | 0.78%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 70        | 0.78%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 67        | 0.75%   |
| Realtek RTL8723A Bluetooth                                                          | 65        | 0.72%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 63        | 0.7%    |
| Intel AX200 Bluetooth                                                               | 54        | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 17629     | 51.61%  |
| AMD                                             | 7634      | 22.35%  |
| Nvidia                                          | 6726      | 19.69%  |
| C-Media Electronics                             | 570       | 1.67%   |
| Creative Labs                                   | 454       | 1.33%   |
| VIA Technologies                                | 213       | 0.62%   |
| Silicon Integrated Systems [SiS]                | 184       | 0.54%   |
| Creative Technology                             | 83        | 0.24%   |
| Logitech                                        | 68        | 0.2%    |
| JMTek                                           | 45        | 0.13%   |
| Texas Instruments                               | 43        | 0.13%   |
| Generalplus Technology                          | 33        | 0.1%    |
| Plantronics                                     | 25        | 0.07%   |
| Ensoniq                                         | 23        | 0.07%   |
| Pixart Imaging                                  | 19        | 0.06%   |
| ASUSTek Computer                                | 19        | 0.06%   |
| Tenx Technology                                 | 18        | 0.05%   |
| ULi Electronics                                 | 16        | 0.05%   |
| Razer USA                                       | 14        | 0.04%   |
| Yamaha                                          | 10        | 0.03%   |
| Shenzhen Rapoo Technology                       | 10        | 0.03%   |
| M-Audio                                         | 10        | 0.03%   |
| Kingston Technology                             | 10        | 0.03%   |
| Aureal Semiconductor                            | 10        | 0.03%   |
| A4Tech                                          | 10        | 0.03%   |
| iCreate Technologies                            | 9         | 0.03%   |
| ESS Technology                                  | 9         | 0.03%   |
| Asahi Kasei Microsystems                        | 9         | 0.03%   |
| Guillemot                                       | 8         | 0.02%   |
| ATI Technologies                                | 8         | 0.02%   |
| Yealink Network Technology                      | 7         | 0.02%   |
| Licensed by Sony Computer Entertainment America | 7         | 0.02%   |
| GYROCOM C&C                                     | 7         | 0.02%   |
| Focusrite-Novation                              | 7         | 0.02%   |
| XMOS                                            | 6         | 0.02%   |
| Sony                                            | 6         | 0.02%   |
| Samson Technologies                             | 6         | 0.02%   |
| Philips (or NXP)                                | 6         | 0.02%   |
| Fortemedia                                      | 6         | 0.02%   |
| EGO SYStems                                     | 6         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3131      | 7.95%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2868      | 7.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2651      | 6.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2611      | 6.63%   |
| AMD FCH Azalia Controller                                                                         | 1584      | 4.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1441      | 3.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1313      | 3.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1104      | 2.8%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 910       | 2.31%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 866       | 2.2%    |
| Nvidia High Definition Audio Controller                                                           | 770       | 1.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 678       | 1.72%   |
| Nvidia MCP61 High Definition Audio                                                                | 641       | 1.63%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 596       | 1.51%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 556       | 1.41%   |
| AMD Kabini HDMI/DP Audio                                                                          | 452       | 1.15%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 448       | 1.14%   |
| Intel 8 Series HD Audio Controller                                                                | 443       | 1.12%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 441       | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 439       | 1.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 439       | 1.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 438       | 1.11%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 407       | 1.03%   |
| AMD Trinity HDMI Audio Controller                                                                 | 398       | 1.01%   |
| AMD Wrestler HDMI Audio                                                                           | 397       | 1.01%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 387       | 0.98%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 363       | 0.92%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 342       | 0.87%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 320       | 0.81%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 311       | 0.79%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 311       | 0.79%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 296       | 0.75%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 295       | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 287       | 0.73%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 278       | 0.71%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 250       | 0.63%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 248       | 0.63%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 243       | 0.62%   |
| Intel 200 Series PCH HD Audio                                                                     | 219       | 0.56%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 217       | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 9193      | 32.59%  |
| Samsung Electronics   | 3942      | 13.97%  |
| Kingston              | 3810      | 13.5%   |
| SK hynix              | 3261      | 11.56%  |
| Micron Technology     | 1139      | 4.04%   |
| Crucial               | 929       | 3.29%   |
| Elpida                | 797       | 2.83%   |
| Nanya Technology      | 728       | 2.58%   |
| Corsair               | 651       | 2.31%   |
| Ramaxel Technology    | 520       | 1.84%   |
| A-DATA Technology     | 495       | 1.75%   |
| AMD                   | 282       | 1%      |
| Patriot               | 269       | 0.95%   |
| ASint Technology      | 179       | 0.63%   |
| GOODRAM               | 156       | 0.55%   |
| Goldkey               | 156       | 0.55%   |
| Transcend             | 138       | 0.49%   |
| 48spaces              | 124       | 0.44%   |
| Silicon Power         | 110       | 0.39%   |
| G.Skill               | 98        | 0.35%   |
| Kingmax               | 95        | 0.34%   |
| SHARETRONIC           | 77        | 0.27%   |
| Qumo                  | 77        | 0.27%   |
| Qimonda               | 77        | 0.27%   |
| Apacer                | 77        | 0.27%   |
| Unifosa               | 70        | 0.25%   |
| Team                  | 68        | 0.24%   |
| GeIL                  | 61        | 0.22%   |
| Unknown (ABCD)        | 51        | 0.18%   |
| Kllisre               | 49        | 0.17%   |
| Foxline               | 48        | 0.17%   |
| Unknown               | 43        | 0.15%   |
| Toshiba               | 31        | 0.11%   |
| KETECH                | 30        | 0.11%   |
| Smart                 | 18        | 0.06%   |
| TakeMS                | 17        | 0.06%   |
| Ramos Technology      | 17        | 0.06%   |
| Kingmax Semiconductor | 17        | 0.06%   |
| Atermiter             | 15        | 0.05%   |
| Hexon                 | 14        | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                                  | 486       | 1.52%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                         | 473       | 1.48%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                                       | 442       | 1.38%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                         | 414       | 1.29%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                                      | 371       | 1.16%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                                      | 350       | 1.09%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                                  | 324       | 1.01%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 313       | 0.98%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                                       | 250       | 0.78%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                                  | 248       | 0.77%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                        | 224       | 0.7%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                                | 221       | 0.69%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                        | 208       | 0.65%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                                  | 206       | 0.64%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                        | 201       | 0.63%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 200       | 0.62%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                        | 193       | 0.6%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 192       | 0.6%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                        | 185       | 0.58%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                        | 177       | 0.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                        | 169       | 0.53%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                                       | 164       | 0.51%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                                       | 162       | 0.51%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                                 | 160       | 0.5%    |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                                | 156       | 0.49%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                                       | 146       | 0.46%   |
| Unknown RAM Module 512MB DIMM SDRAM                                          | 143       | 0.45%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                       | 139       | 0.43%   |
| Unknown RAM Module 1024MB DIMM                                               | 138       | 0.43%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s                        | 132       | 0.41%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                                      | 131       | 0.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                        | 130       | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                                 | 123       | 0.38%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                        | 123       | 0.38%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s                          | 123       | 0.38%   |
| Unknown RAM Module 4096MB SODIMM DDR3                                        | 120       | 0.37%   |
| 48spaces RAM 012345678901234567890123456789012345 1024MB SODIMM DDR2 667MT/s | 116       | 0.36%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                         | 110       | 0.34%   |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s                            | 106       | 0.33%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                                | 102       | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 12189     | 49%     |
| DDR2    | 3903      | 15.69%  |
| Unknown | 3076      | 12.37%  |
| SDRAM   | 2392      | 9.62%   |
| DDR4    | 2225      | 8.94%   |
| DDR     | 730       | 2.93%   |
| DRAM    | 198       | 0.8%    |
| LPDDR4  | 121       | 0.49%   |
| LPDDR3  | 31        | 0.12%   |
| EEPROM  | 3         | 0.01%   |
| DDR5    | 3         | 0.01%   |
| LPDDR5  | 2         | 0.01%   |
| SRAM    | 1         | 0.004%  |
| RAM     | 1         | 0.004%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 12451     | 51.34%  |
| SODIMM       | 11687     | 48.19%  |
| Row Of Chips | 73        | 0.3%    |
| Chip         | 25        | 0.1%    |
| FB-DIMM      | 9         | 0.04%   |
| Unknown      | 7         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 9943      | 34.52%  |
| 2048    | 9618      | 33.39%  |
| 1024    | 4489      | 15.58%  |
| 8192    | 3231      | 11.22%  |
| 512     | 953       | 3.31%   |
| 16384   | 293       | 1.02%   |
| 256     | 198       | 0.69%   |
| 32768   | 53        | 0.18%   |
| Unknown | 10        | 0.03%   |
| 128     | 6         | 0.02%   |
| 32      | 4         | 0.01%   |
| 16      | 3         | 0.01%   |
| 1       | 3         | 0.01%   |
| 1536    | 2         | 0.01%   |
| 32767   | 1         | 0.003%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 6880      | 25.3%   |
| 1333    | 3746      | 13.77%  |
| Unknown | 2553      | 9.39%   |
| 800     | 2316      | 8.52%   |
| 667     | 2219      | 8.16%   |
| 1334    | 2084      | 7.66%   |
| 2400    | 766       | 2.82%   |
| 2667    | 663       | 2.44%   |
| 1067    | 540       | 1.99%   |
| 2133    | 511       | 1.88%   |
| 400     | 509       | 1.87%   |
| 533     | 493       | 1.81%   |
| 4199    | 470       | 1.73%   |
| 1066    | 421       | 1.55%   |
| 3200    | 420       | 1.54%   |
| 1867    | 350       | 1.29%   |
| 333     | 302       | 1.11%   |
| 2048    | 252       | 0.93%   |
| 1866    | 173       | 0.64%   |
| 975     | 124       | 0.46%   |
| 266     | 109       | 0.4%    |
| 3400    | 104       | 0.38%   |
| 1800    | 103       | 0.38%   |
| 3600    | 89        | 0.33%   |
| 2933    | 79        | 0.29%   |
| 3266    | 74        | 0.27%   |
| 1639    | 74        | 0.27%   |
| 2666    | 49        | 0.18%   |
| 66      | 49        | 0.18%   |
| 3466    | 46        | 0.17%   |
| 3000    | 46        | 0.17%   |
| 2000    | 41        | 0.15%   |
| 1648    | 37        | 0.14%   |
| 2134    | 35        | 0.13%   |
| 1400    | 35        | 0.13%   |
| 2800    | 34        | 0.13%   |
| 200     | 32        | 0.12%   |
| 49926   | 25        | 0.09%   |
| 2866    | 24        | 0.09%   |
| 3066    | 19        | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 504       | 30.6%   |
| Canon                           | 380       | 23.07%  |
| Samsung Electronics             | 282       | 17.12%  |
| Seiko Epson                     | 164       | 9.96%   |
| Brother Industries              | 109       | 6.62%   |
| Xerox                           | 48        | 2.91%   |
| Panasonic (Matsushita)          | 38        | 2.31%   |
| Pantum                          | 24        | 1.46%   |
| Kyocera                         | 24        | 1.46%   |
| Ricoh                           | 20        | 1.21%   |
| Prolific Technology             | 13        | 0.79%   |
| QinHeng Electronics             | 8         | 0.49%   |
| Lexmark International           | 8         | 0.49%   |
| TSC Auto ID Technology          | 4         | 0.24%   |
| WinChipHead                     | 3         | 0.18%   |
| STMicroelectronics              | 2         | 0.12%   |
| Sharp                           | 2         | 0.12%   |
| cab Produkttechnik GmbH & Co KG | 2         | 0.12%   |
| Yurex                           | 1         | 0.06%   |
| Xiaomi                          | 1         | 0.06%   |
| Toshiba TEC                     | 1         | 0.06%   |
| Samsung Info. Systems America   | 1         | 0.06%   |
| NXP Semiconductors              | 1         | 0.06%   |
| Konica Minolta                  | 1         | 0.06%   |
| KODAK                           | 1         | 0.06%   |
| Fuji Xerox                      | 1         | 0.06%   |
| Dell                            | 1         | 0.06%   |
| Custom Engineering SPA          | 1         | 0.06%   |
| ATEN International              | 1         | 0.06%   |
| Apple                           | 1         | 0.06%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| HP LaserJet 1020                      | 58        | 3.45%   |
| HP LaserJet P1102                     | 44        | 2.62%   |
| HP LaserJet 1018                      | 44        | 2.62%   |
| Samsung SCX-4200 series               | 43        | 2.56%   |
| Canon LBP2900                         | 38        | 2.26%   |
| Seiko Epson Printer                   | 34        | 2.02%   |
| Panasonic (Matsushita) KX-MB1500RU    | 25        | 1.49%   |
| Seiko Epson USB2.0 Printer (Hi-speed) | 24        | 1.43%   |
| Samsung SCX-3400 Series               | 24        | 1.43%   |
| HP LaserJet 1010                      | 24        | 1.43%   |
| Samsung SCX-3200 Series               | 23        | 1.37%   |
| Canon MF4410                          | 23        | 1.37%   |
| Canon MF3010                          | 23        | 1.37%   |
| HP LaserJet P1005                     | 22        | 1.31%   |
| Seiko Epson L210 Series               | 17        | 1.01%   |
| Samsung ML-1640 Series Laser Printer  | 17        | 1.01%   |
| Canon LBP3010/LBP3018/LBP3050         | 16        | 0.95%   |
| Samsung ML-1210 Printer               | 15        | 0.89%   |
| Canon MF4010 series                   | 15        | 0.89%   |
| HP Deskjet 2050 J510                  | 14        | 0.83%   |
| Canon LBP6000                         | 14        | 0.83%   |
| Canon LaserShot LBP-1120 Printer      | 14        | 0.83%   |
| Samsung M2070 Series                  | 13        | 0.77%   |
| Prolific PL2305 Parallel Port         | 13        | 0.77%   |
| Canon PIXMA MG2500 Series             | 13        | 0.77%   |
| Canon LBP810                          | 13        | 0.77%   |
| Canon iP7200 series                   | 13        | 0.77%   |
| Brother HL-2030 Laser Printer         | 13        | 0.77%   |
| Xerox Phaser 3140 and 3155            | 12        | 0.71%   |
| Samsung ML-2010P Mono Laser Printer   | 12        | 0.71%   |
| HP LaserJet 1200                      | 12        | 0.71%   |
| Canon MG2400 series                   | 12        | 0.71%   |
| Brother HL-1110 series                | 12        | 0.71%   |
| Brother DCP-7057 scanner/printer      | 12        | 0.71%   |
| HP LaserJet 1320                      | 11        | 0.65%   |
| HP LaserJet 1000                      | 11        | 0.65%   |
| HP DeskJet 2130 series                | 11        | 0.65%   |
| Canon LBP6020                         | 11        | 0.65%   |
| Samsung SCX-4100 Scanner              | 10        | 0.59%   |
| Samsung M2020 Series                  | 10        | 0.59%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 172       | 36.21%  |
| Seiko Epson                 | 114       | 24%     |
| Hewlett-Packard             | 82        | 17.26%  |
| Mustek Systems              | 49        | 10.32%  |
| Acer Peripherals (now BenQ) | 19        | 4%      |
| Ultima Electronics          | 18        | 3.79%   |
| KYE Systems (Mouse Systems) | 7         | 1.47%   |
| Fujitsu                     | 4         | 0.84%   |
| Microtek International      | 2         | 0.42%   |
| Avision                     | 2         | 0.42%   |
| AGFA-Gevaert NV             | 2         | 0.42%   |
| Visioneer                   | 1         | 0.21%   |
| Plustek                     | 1         | 0.21%   |
| Papillon Systems            | 1         | 0.21%   |
| Canon Electronics           | 1         | 0.21%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25                                                                | 31        | 6.51%   |
| HP ScanJet 2400c                                                                      | 26        | 5.46%   |
| Canon CanoScan LiDE 110                                                               | 26        | 5.46%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 21        | 4.41%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 18        | 3.78%   |
| Canon CanoScan LiDE 120                                                               | 18        | 3.78%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 17        | 3.57%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 16        | 3.36%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 15        | 3.15%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 14        | 2.94%   |
| Canon CanoScan LiDE 210                                                               | 12        | 2.52%   |
| Canon CanoScan LiDE 60                                                                | 11        | 2.31%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 10        | 2.1%    |
| Canon CanoScan LiDE 100                                                               | 10        | 2.1%    |
| Canon CanoScan LiDE 220                                                               | 9         | 1.89%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 8         | 1.68%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 8         | 1.68%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 7         | 1.47%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 7         | 1.47%   |
| Seiko Epson Perfection 660                                                            | 6         | 1.26%   |
| Mustek Systems SNAPSCAN e22                                                           | 6         | 1.26%   |
| Canon CanoScan                                                                        | 6         | 1.26%   |
| Mustek Systems BearPaw 2448 TA Plus                                                   | 5         | 1.05%   |
| Acer Peripherals (now BenQ) Benq 5560                                                 | 5         | 1.05%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 4         | 0.84%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 4         | 0.84%   |
| HP ScanJet 3800c                                                                      | 4         | 0.84%   |
| HP Scanjet 200                                                                        | 4         | 0.84%   |
| Canon CanoScan LiDE 70                                                                | 4         | 0.84%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 4         | 0.84%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 3         | 0.63%   |
| Mustek Systems BearPaw 2400 TA Plus                                                   | 3         | 0.63%   |
| HP ScanJet G3010                                                                      | 3         | 0.63%   |
| HP ScanJet 3970c                                                                      | 3         | 0.63%   |
| HP ScanJet 3770                                                                       | 3         | 0.63%   |
| HP ScanJet 3500c                                                                      | 3         | 0.63%   |
| HP ScanJet 2200c                                                                      | 3         | 0.63%   |
| HP PSC 1200                                                                           | 3         | 0.63%   |
| Fujitsu ScanSnap SV600                                                                | 3         | 0.63%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 3         | 0.63%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2941      | 21.52%  |
| Logitech                               | 1074      | 7.86%   |
| Acer                                   | 1002      | 7.33%   |
| Suyin                                  | 935       | 6.84%   |
| IMC Networks                           | 863       | 6.32%   |
| Z-Star Microelectronics                | 839       | 6.14%   |
| Microdia                               | 809       | 5.92%   |
| Realtek Semiconductor                  | 730       | 5.34%   |
| Silicon Motion                         | 590       | 4.32%   |
| Sunplus Innovation Technology          | 566       | 4.14%   |
| Alcor Micro                            | 369       | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) | 331       | 2.42%   |
| Syntek                                 | 317       | 2.32%   |
| Quanta                                 | 171       | 1.25%   |
| Microsoft                              | 166       | 1.21%   |
| ALi                                    | 165       | 1.21%   |
| Ricoh                                  | 153       | 1.12%   |
| Apple                                  | 133       | 0.97%   |
| KYE Systems (Mouse Systems)            | 127       | 0.93%   |
| DigiTech                               | 124       | 0.91%   |
| Pixart Imaging                         | 106       | 0.78%   |
| Arkmicro Technologies                  | 103       | 0.75%   |
| Cubeternet                             | 102       | 0.75%   |
| Aveo Technology                        | 98        | 0.72%   |
| GEMBIRD                                | 87        | 0.64%   |
| Samsung Electronics                    | 79        | 0.58%   |
| Lenovo                                 | 67        | 0.49%   |
| Lite-On Technology                     | 63        | 0.46%   |
| Importek                               | 54        | 0.4%    |
| Primax Electronics                     | 46        | 0.34%   |
| Creative Technology                    | 40        | 0.29%   |
| Genesys Logic                          | 32        | 0.23%   |
| OmniVision Technologies                | 26        | 0.19%   |
| Sunplus Technology                     | 23        | 0.17%   |
| Nokia Mobile Phones                    | 21        | 0.15%   |
| Guillemot                              | 21        | 0.15%   |
| Luxvisions Innotech Limited            | 20        | 0.15%   |
| Image Processor                        | 18        | 0.13%   |
| Philips (or NXP)                       | 17        | 0.12%   |
| Hewlett-Packard                        | 16        | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Logitech Webcam C270                     | 361       | 2.64%   |
| Acer Lenovo EasyCamera                   | 357       | 2.61%   |
| Chicony HD Webcam                        | 302       | 2.21%   |
| Z-Star Venus USB2.0 Camera               | 283       | 2.07%   |
| Chicony Lenovo EasyCamera                | 274       | 2%      |
| IMC Networks UVC VGA Webcam              | 203       | 1.48%   |
| Sunplus HD WebCam                        | 197       | 1.44%   |
| Chicony USB 2.0 Camera                   | 193       | 1.41%   |
| Z-Star A4 TECH USB2.0 PC Camera J        | 164       | 1.2%    |
| Acer BisonCam, NB Pro                    | 164       | 1.2%    |
| Chicony USB2.0 HD UVC WebCam             | 158       | 1.15%   |
| Microdia Camera                          | 148       | 1.08%   |
| Realtek USB Camera                       | 137       | 1%      |
| Chicony Integrated Camera                | 125       | 0.91%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 120       | 0.88%   |
| Microdia Sonix USB 2.0 Camera            | 120       | 0.88%   |
| Realtek Lenovo EasyCamera                | 118       | 0.86%   |
| Z-Star Vimicro USB Camera (Altair)       | 115       | 0.84%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 113       | 0.83%   |
| Syntek Lenovo EasyCamera                 | 112       | 0.82%   |
| Silicon Motion WebCam SC-0311139N        | 112       | 0.82%   |
| ALi Gateway Webcam                       | 112       | 0.82%   |
| IMC Networks Integrated Webcam           | 109       | 0.8%    |
| Alcor Micro Asus Integrated Webcam       | 109       | 0.8%    |
| Acer Lenovo Integrated Webcam            | 106       | 0.77%   |
| DigiTech USB 2.0 PC Camera               | 103       | 0.75%   |
| Suyin 1.3M HD WebCam                     | 96        | 0.7%    |
| Chicony USB2.0 VGA UVC WebCam            | 95        | 0.69%   |
| Sunplus Asus Webcam                      | 94        | 0.69%   |
| Arkmicro USB2.0 PC CAMERA                | 93        | 0.68%   |
| Chicony HP Truevision HD                 | 92        | 0.67%   |
| Logitech Webcam C170                     | 89        | 0.65%   |
| Chicony USB2.0 0.3M UVC WebCam           | 86        | 0.63%   |
| Logitech Webcam C310                     | 85        | 0.62%   |
| Logitech Webcam C210                     | 84        | 0.61%   |
| Chicony HP Webcam                        | 82        | 0.6%    |
| IMC Networks USB2.0 VGA UVC WebCam       | 81        | 0.59%   |
| Chicony 1.3M Webcam                      | 81        | 0.59%   |
| IMC Networks USB2.0 UVC HD Webcam        | 79        | 0.58%   |
| Suyin Acer CrystalEye Webcam             | 78        | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 426       | 43.03%  |
| AuthenTec                  | 224       | 22.63%  |
| Upek                       | 156       | 15.76%  |
| STMicroelectronics         | 74        | 7.47%   |
| LighTuning Technology      | 64        | 6.46%   |
| Elan Microelectronics      | 15        | 1.52%   |
| Shenzhen Goodix Technology | 14        | 1.41%   |
| Synaptics                  | 13        | 1.31%   |
| Microsoft                  | 2         | 0.2%    |
| Focal-systems.Corp         | 1         | 0.1%    |
| DigitalPersona             | 1         | 0.1%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 139       | 14.04%  |
| Validity Sensors Fingerprint scanner                                       | 114       | 11.52%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 87        | 8.79%   |
| STMicroelectronics Fingerprint Reader                                      | 74        | 7.47%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 73        | 7.37%   |
| AuthenTec AES1600                                                          | 62        | 6.26%   |
| AuthenTec AES2810                                                          | 55        | 5.56%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 45        | 4.55%   |
| LighTuning Fingerprint Reader                                              | 40        | 4.04%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 39        | 3.94%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 31        | 3.13%   |
| Validity Sensors VFS491                                                    | 26        | 2.63%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 25        | 2.53%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 24        | 2.42%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 19        | 1.92%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 18        | 1.82%   |
| Upek TCS5B Fingerprint sensor                                              | 17        | 1.72%   |
| Shenzhen Goodix  FingerPrint Device                                        | 13        | 1.31%   |
| Elan ELAN:Fingerprint                                                      | 13        | 1.31%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.21%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 0.81%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.71%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 7         | 0.71%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 0.61%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 0.61%   |
| Unknown                                                                    | 5         | 0.51%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 0.4%    |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.3%    |
| Synaptics  WBDI                                                            | 2         | 0.2%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 0.2%    |
| Microsoft Fingerprint Reader                                               | 2         | 0.2%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.1%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.1%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.1%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.1%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 0.1%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.1%    |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.1%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.1%    |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 0.1%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Broadcom                                | 101       | 33.01%  |
| O2 Micro                                | 52        | 16.99%  |
| Alcor Micro                             | 35        | 11.44%  |
| Lenovo                                  | 27        | 8.82%   |
| Upek                                    | 26        | 8.5%    |
| Aladdin Knowledge Systems               | 14        | 4.58%   |
| Advanced Card Systems                   | 11        | 3.59%   |
| OmniKey                                 | 8         | 2.61%   |
| Aktiv                                   | 8         | 2.61%   |
| Realtek Semiconductor                   | 5         | 1.63%   |
| Gemalto (was Gemplus)                   | 5         | 1.63%   |
| Athena Smartcard Solutions              | 4         | 1.31%   |
| Castles Technology                      | 2         | 0.65%   |
| Aladdin R.D.                            | 2         | 0.65%   |
| Reiner SCT Kartensysteme                | 1         | 0.33%   |
| In Focus Systems                        | 1         | 0.33%   |
| Future Technology Devices International | 1         | 0.33%   |
| Cherry                                  | 1         | 0.33%   |
| BIFIT                                   | 1         | 0.33%   |
| Avtor                                   | 1         | 0.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 67        | 21.9%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 36        | 11.76%  |
| Lenovo Integrated Smart Card Reader                                          | 27        | 8.82%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 8.82%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 26        | 8.5%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 25        | 8.17%   |
| O2 Micro Oz776 SmartCard Reader                                              | 16        | 5.23%   |
| Aladdin Knowledge Systems Token JC                                           | 14        | 4.58%   |
| Alcor Micro Watchdata W 1981                                                 | 8         | 2.61%   |
| Broadcom 5880                                                                | 7         | 2.29%   |
| Aktiv Rutoken lite                                                           | 7         | 2.29%   |
| OmniKey CardMan 1021                                                         | 6         | 1.96%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 5         | 1.63%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 4         | 1.31%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 1.31%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.98%   |
| Advanced Card Systems Token USB 64K                                          | 3         | 0.98%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.65%   |
| Castles Technology EZCCID Smart Card Reader                                  | 2         | 0.65%   |
| Broadcom 58200                                                               | 2         | 0.65%   |
| Aladdin R.D. JaCarta                                                         | 2         | 0.65%   |
| Advanced Card Systems ACR3901U                                               | 2         | 0.65%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.33%   |
| OmniKey CardMan 4321                                                         | 1         | 0.33%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.33%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.33%   |
| Future Technology Devices International Parsec Desktop Reader PR-EH08        | 1         | 0.33%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.33%   |
| BIFIT iBank2Key                                                              | 1         | 0.33%   |
| Avtor SecureToken                                                            | 1         | 0.33%   |
| Aktiv KAZTOKEN                                                               | 1         | 0.33%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.33%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 20670     | 78.13%  |
| 1     | 4801      | 18.15%  |
| 2     | 851       | 3.22%   |
| 3     | 106       | 0.4%    |
| 4     | 22        | 0.08%   |
| 5     | 3         | 0.01%   |
| 9     | 1         | 0.004%  |
| 7     | 1         | 0.004%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 3161      | 49.66%  |
| Fingerprint reader       | 988       | 15.52%  |
| Net/wireless             | 518       | 8.14%   |
| Bluetooth                | 353       | 5.55%   |
| Chipcard                 | 290       | 4.56%   |
| Communication controller | 237       | 3.72%   |
| Multimedia controller    | 234       | 3.68%   |
| Camera                   | 138       | 2.17%   |
| Storage                  | 123       | 1.93%   |
| Flash memory             | 96        | 1.51%   |
| Unassigned class         | 61        | 0.96%   |
| Sound                    | 36        | 0.57%   |
| Modem                    | 30        | 0.47%   |
| Dvb card                 | 26        | 0.41%   |
| Card reader              | 26        | 0.41%   |
| Net/ethernet             | 14        | 0.22%   |
| Network                  | 13        | 0.2%    |
| Tv card                  | 6         | 0.09%   |
| Video                    | 5         | 0.08%   |
| Storage/raid             | 4         | 0.06%   |
| Storage/ata              | 4         | 0.06%   |
| Wireless                 | 1         | 0.02%   |
| Storage/ide              | 1         | 0.02%   |

