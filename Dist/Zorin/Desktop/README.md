Zorin - Tested Hardware & Statistics (Desktops)
-----------------------------------------------

A project to collect tested hardware configurations for Zorin.

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

Total: 3236

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0D28YY A01                  | [f67d5d22eb](https://linux-hardware.org/?probe=f67d5d22eb) | Jan 02, 2024 |
| ASUSTek       | M4A87TD/USB3                | [8c2ae70cdd](https://linux-hardware.org/?probe=8c2ae70cdd) | Jan 02, 2024 |
| Gigabyte      | Z590 UD AC                  | [0db9ec67ac](https://linux-hardware.org/?probe=0db9ec67ac) | Jan 02, 2024 |
| Unknown       | Unknown                     | [b101d94fff](https://linux-hardware.org/?probe=b101d94fff) | Jan 01, 2024 |
| Gigabyte      | X79-UP4                     | [4c7ec5ec88](https://linux-hardware.org/?probe=4c7ec5ec88) | Jan 01, 2024 |
| ASUSTek       | PRIME A320M-K               | [685d971973](https://linux-hardware.org/?probe=685d971973) | Jan 01, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [d2112b91c1](https://linux-hardware.org/?probe=d2112b91c1) | Jan 01, 2024 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [252e78398a](https://linux-hardware.org/?probe=252e78398a) | Jan 01, 2024 |
| HP            | 1850                        | [b635f6412c](https://linux-hardware.org/?probe=b635f6412c) | Jan 01, 2024 |
| ASUSTek       | P5G41T-M LX                 | [ab74a1228a](https://linux-hardware.org/?probe=ab74a1228a) | Jan 01, 2024 |
| ASUSTek       | PRIME J4005I-C/BR           | [12a957b14b](https://linux-hardware.org/?probe=12a957b14b) | Jan 01, 2024 |
| ASUSTek       | PRIME J4005I-C/BR           | [7f4bbc6a71](https://linux-hardware.org/?probe=7f4bbc6a71) | Dec 31, 2023 |
| ASUSTek       | PRIME J4005I-C/BR           | [5b8817b3de](https://linux-hardware.org/?probe=5b8817b3de) | Dec 31, 2023 |
| ASUSTek       | CM6870                      | [bdc19328ef](https://linux-hardware.org/?probe=bdc19328ef) | Dec 31, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [daee98e116](https://linux-hardware.org/?probe=daee98e116) | Dec 31, 2023 |
| Dell          | 0RW199                      | [62dc9ffa33](https://linux-hardware.org/?probe=62dc9ffa33) | Dec 31, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [e330d0191e](https://linux-hardware.org/?probe=e330d0191e) | Dec 31, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [5d368c5304](https://linux-hardware.org/?probe=5d368c5304) | Dec 31, 2023 |
| ASUSTek       | PRIME X399-A                | [ac506b01e6](https://linux-hardware.org/?probe=ac506b01e6) | Dec 30, 2023 |
| HP            | 82F1                        | [9fc9cb3de0](https://linux-hardware.org/?probe=9fc9cb3de0) | Dec 30, 2023 |
| Gigabyte      | AX370-Gaming K5-CF          | [ba1b2a738a](https://linux-hardware.org/?probe=ba1b2a738a) | Dec 30, 2023 |
| Dell          | 0VRWRC A00                  | [c58ff5350b](https://linux-hardware.org/?probe=c58ff5350b) | Dec 30, 2023 |
| ASUSTek       | TUF Gaming B760M-PLUS WI... | [843542e7eb](https://linux-hardware.org/?probe=843542e7eb) | Dec 30, 2023 |
| Dell          | 0M5DCD A00                  | [a85c9d93c8](https://linux-hardware.org/?probe=a85c9d93c8) | Dec 30, 2023 |
| Pegatron      | 2A9A                        | [92def1bf4a](https://linux-hardware.org/?probe=92def1bf4a) | Dec 30, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7dca6779be](https://linux-hardware.org/?probe=7dca6779be) | Dec 29, 2023 |
| Gigabyte      | P55A-UD4                    | [c1694a8923](https://linux-hardware.org/?probe=c1694a8923) | Dec 29, 2023 |
| Gigabyte      | H81M-S2H                    | [a3a0b274d0](https://linux-hardware.org/?probe=a3a0b274d0) | Dec 29, 2023 |
| ASRock        | B550M-C                     | [ba3fa09385](https://linux-hardware.org/?probe=ba3fa09385) | Dec 29, 2023 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [7a34810f0e](https://linux-hardware.org/?probe=7a34810f0e) | Dec 29, 2023 |
| Gigabyte      | P55A-UD4                    | [580efd7b07](https://linux-hardware.org/?probe=580efd7b07) | Dec 29, 2023 |
| ASUSTek       | M4A87TD/USB3                | [62939d6430](https://linux-hardware.org/?probe=62939d6430) | Dec 29, 2023 |
| ASUSTek       | PRIME X399-A                | [4d46811257](https://linux-hardware.org/?probe=4d46811257) | Dec 29, 2023 |
| Gigabyte      | H61M-D2H-USB3               | [018e344b4d](https://linux-hardware.org/?probe=018e344b4d) | Dec 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ee1b832527](https://linux-hardware.org/?probe=ee1b832527) | Dec 28, 2023 |
| Dell          | 033FF6 A00                  | [f54cfd23ee](https://linux-hardware.org/?probe=f54cfd23ee) | Dec 28, 2023 |
| HP            | 8055                        | [0829ea2c26](https://linux-hardware.org/?probe=0829ea2c26) | Dec 28, 2023 |
| Dell          | 0GDG8Y A00                  | [59c76d34e1](https://linux-hardware.org/?probe=59c76d34e1) | Dec 27, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [a6041ee7fc](https://linux-hardware.org/?probe=a6041ee7fc) | Dec 27, 2023 |
| ASUSTek       | M4A79T Deluxe               | [167d330ef0](https://linux-hardware.org/?probe=167d330ef0) | Dec 27, 2023 |
| Gigabyte      | H61M-D2H-USB3               | [64a4b468b6](https://linux-hardware.org/?probe=64a4b468b6) | Dec 27, 2023 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | [d476db4ac3](https://linux-hardware.org/?probe=d476db4ac3) | Dec 27, 2023 |
| ASUSTek       | PRIME B450M-K II            | [45f0a0ac2d](https://linux-hardware.org/?probe=45f0a0ac2d) | Dec 27, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [bc9feace53](https://linux-hardware.org/?probe=bc9feace53) | Dec 27, 2023 |
| ASUSTek       | PRIME B450M-K II            | [a74968ee9c](https://linux-hardware.org/?probe=a74968ee9c) | Dec 27, 2023 |
| Dell          | 0M5DCD A00                  | [3444d7393c](https://linux-hardware.org/?probe=3444d7393c) | Dec 26, 2023 |
| Pegatron      | 2A9A                        | [e67022179a](https://linux-hardware.org/?probe=e67022179a) | Dec 26, 2023 |
| ASUSTek       | M4A87TD/USB3                | [ac88b7e1f2](https://linux-hardware.org/?probe=ac88b7e1f2) | Dec 26, 2023 |
| Intel         | X99-P4 V1.0                 | [69e399de83](https://linux-hardware.org/?probe=69e399de83) | Dec 25, 2023 |
| Dell          | 0GDG8Y A00                  | [52a5621ef8](https://linux-hardware.org/?probe=52a5621ef8) | Dec 25, 2023 |
| Dell          | 084J0R A00                  | [856558c97d](https://linux-hardware.org/?probe=856558c97d) | Dec 25, 2023 |
| Intel         | DH77EB AAG39073-304         | [0cee3977a0](https://linux-hardware.org/?probe=0cee3977a0) | Dec 25, 2023 |
| Dell          | 0MN1TX A04                  | [ba94c75ba0](https://linux-hardware.org/?probe=ba94c75ba0) | Dec 25, 2023 |
| HP            | 2AF7                        | [2fc4d5dd6b](https://linux-hardware.org/?probe=2fc4d5dd6b) | Dec 24, 2023 |
| Lenovo        | 3098 0B98417 PRO            | [770682ab90](https://linux-hardware.org/?probe=770682ab90) | Dec 24, 2023 |
| HP            | 2AF7                        | [baa5012432](https://linux-hardware.org/?probe=baa5012432) | Dec 24, 2023 |
| HP            | 0B4Ch D                     | [2f8f606e9f](https://linux-hardware.org/?probe=2f8f606e9f) | Dec 24, 2023 |
| HP            | 8299                        | [b579f81db7](https://linux-hardware.org/?probe=b579f81db7) | Dec 24, 2023 |
| ASRock        | 990FX Professional          | [34c4b1fbd4](https://linux-hardware.org/?probe=34c4b1fbd4) | Dec 24, 2023 |
| HP            | 8299                        | [9d48e9f8cb](https://linux-hardware.org/?probe=9d48e9f8cb) | Dec 24, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [6c327c054f](https://linux-hardware.org/?probe=6c327c054f) | Dec 24, 2023 |
| HP            | 0B4Ch D                     | [6ee70cb266](https://linux-hardware.org/?probe=6ee70cb266) | Dec 24, 2023 |
| ASUSTek       | M2V                         | [67c7bc43ed](https://linux-hardware.org/?probe=67c7bc43ed) | Dec 23, 2023 |
| ASUSTek       | M2V                         | [1d6970f290](https://linux-hardware.org/?probe=1d6970f290) | Dec 23, 2023 |
| HP            | 1998                        | [8eb25518c4](https://linux-hardware.org/?probe=8eb25518c4) | Dec 23, 2023 |
| ASUSTek       | M5A99FX PRO R2.0            | [1622d9b25b](https://linux-hardware.org/?probe=1622d9b25b) | Dec 23, 2023 |
| Gigabyte      | B650 GAMING X AX            | [9c0210d1ed](https://linux-hardware.org/?probe=9c0210d1ed) | Dec 22, 2023 |
| Gigabyte      | B450 AORUS M                | [084e48827c](https://linux-hardware.org/?probe=084e48827c) | Dec 21, 2023 |
| Intel         | DH77EB AAG39073-304         | [83183dbb01](https://linux-hardware.org/?probe=83183dbb01) | Dec 21, 2023 |
| Dell          | 0JP3NX A01                  | [706947928d](https://linux-hardware.org/?probe=706947928d) | Dec 21, 2023 |
| Gigabyte      | Z170X-UD5-CF                | [67662437e4](https://linux-hardware.org/?probe=67662437e4) | Dec 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6311def15e](https://linux-hardware.org/?probe=6311def15e) | Dec 21, 2023 |
| Unknown       | Unknown                     | [ded73c0619](https://linux-hardware.org/?probe=ded73c0619) | Dec 21, 2023 |
| ASUSTek       | M4A785TD-V EVO              | [8b094a74c9](https://linux-hardware.org/?probe=8b094a74c9) | Dec 21, 2023 |
| ASUSTek       | M5A99X EVO                  | [c0c637bbba](https://linux-hardware.org/?probe=c0c637bbba) | Dec 21, 2023 |
| Dell          | 0FM586                      | [eadcdb629b](https://linux-hardware.org/?probe=eadcdb629b) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [af51ef8978](https://linux-hardware.org/?probe=af51ef8978) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [7cda066ff6](https://linux-hardware.org/?probe=7cda066ff6) | Dec 20, 2023 |
| HP            | 1998                        | [bc41363911](https://linux-hardware.org/?probe=bc41363911) | Dec 20, 2023 |
| HP            | 8653 A                      | [0fd89faa0c](https://linux-hardware.org/?probe=0fd89faa0c) | Dec 18, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | [a411802ac6](https://linux-hardware.org/?probe=a411802ac6) | Dec 17, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [ad9eaf3ae6](https://linux-hardware.org/?probe=ad9eaf3ae6) | Dec 16, 2023 |
| Dell          | 02YYK5 A01                  | [0558258245](https://linux-hardware.org/?probe=0558258245) | Dec 16, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | [faf62fd1be](https://linux-hardware.org/?probe=faf62fd1be) | Dec 16, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [64bf6abdc6](https://linux-hardware.org/?probe=64bf6abdc6) | Dec 16, 2023 |
| Dell          | 0FM586                      | [c895a8d51f](https://linux-hardware.org/?probe=c895a8d51f) | Dec 15, 2023 |
| HP            | 09CCh                       | [e966e2bb97](https://linux-hardware.org/?probe=e966e2bb97) | Dec 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [646c709529](https://linux-hardware.org/?probe=646c709529) | Dec 15, 2023 |
| Gigabyte      | H410M H V3                  | [048f7ace00](https://linux-hardware.org/?probe=048f7ace00) | Dec 14, 2023 |
| Dell          | 0GDG8Y A00                  | [85f532c1c5](https://linux-hardware.org/?probe=85f532c1c5) | Dec 13, 2023 |
| Positivo      | POS-PIQ57BQ POSITIVO        | [1a2fe7c9ef](https://linux-hardware.org/?probe=1a2fe7c9ef) | Dec 13, 2023 |
| Dell          | 0HHV7N A00                  | [be9d84c772](https://linux-hardware.org/?probe=be9d84c772) | Dec 13, 2023 |
| Dell          | 0HHV7N A00                  | [eb16cdaf5c](https://linux-hardware.org/?probe=eb16cdaf5c) | Dec 13, 2023 |
| ASUSTek       | Maximus VII HERO            | [f779186ae7](https://linux-hardware.org/?probe=f779186ae7) | Dec 11, 2023 |
| HP            | 8643 SMVB                   | [d0ff744f50](https://linux-hardware.org/?probe=d0ff744f50) | Dec 10, 2023 |
| HP            | 09CCh                       | [3ef7653874](https://linux-hardware.org/?probe=3ef7653874) | Dec 10, 2023 |
| HP            | 8643 SMVB                   | [e7dbed1e89](https://linux-hardware.org/?probe=e7dbed1e89) | Dec 10, 2023 |
| Dell          | 0FM586                      | [2bf8665376](https://linux-hardware.org/?probe=2bf8665376) | Dec 10, 2023 |
| MSI           | 2AE0                        | [29c5d75dcf](https://linux-hardware.org/?probe=29c5d75dcf) | Dec 10, 2023 |
| MSI           | 2AE0                        | [63543021ec](https://linux-hardware.org/?probe=63543021ec) | Dec 10, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [5522722e53](https://linux-hardware.org/?probe=5522722e53) | Dec 10, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [52e1cb6958](https://linux-hardware.org/?probe=52e1cb6958) | Dec 10, 2023 |
| ASUSTek       | PRIME A320M-K               | [bc892e5d3b](https://linux-hardware.org/?probe=bc892e5d3b) | Dec 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [955f530c70](https://linux-hardware.org/?probe=955f530c70) | Dec 08, 2023 |
| MSI           | MS-7309                     | [bfc6167f25](https://linux-hardware.org/?probe=bfc6167f25) | Dec 06, 2023 |
| MSI           | MS-7309                     | [556b1ebd9a](https://linux-hardware.org/?probe=556b1ebd9a) | Dec 06, 2023 |
| Gigabyte      | 970A-DS3P                   | [396f3e6e9e](https://linux-hardware.org/?probe=396f3e6e9e) | Dec 06, 2023 |
| Gateway       | SX2851                      | [2ec497373d](https://linux-hardware.org/?probe=2ec497373d) | Dec 05, 2023 |
| ASUSTek       | P8Z68-V GEN3                | [3792e939db](https://linux-hardware.org/?probe=3792e939db) | Dec 05, 2023 |
| ASRock        | B550M PG Riptide            | [6132709ecd](https://linux-hardware.org/?probe=6132709ecd) | Dec 05, 2023 |
| Lenovo        | SHARKBAY NOK                | [549c56d2f8](https://linux-hardware.org/?probe=549c56d2f8) | Dec 04, 2023 |
| Lenovo        | SHARKBAY NOK                | [9714fadd61](https://linux-hardware.org/?probe=9714fadd61) | Dec 04, 2023 |
| ASUSTek       | PRIME B450M-A               | [23937a8b80](https://linux-hardware.org/?probe=23937a8b80) | Dec 04, 2023 |
| Gigabyte      | B365M DS3H                  | [0d13c9a0b6](https://linux-hardware.org/?probe=0d13c9a0b6) | Dec 04, 2023 |
| Unknown       | Unknown                     | [4800fa6c99](https://linux-hardware.org/?probe=4800fa6c99) | Dec 04, 2023 |
| Dell          | 042P49 A00                  | [6bc5e84b91](https://linux-hardware.org/?probe=6bc5e84b91) | Dec 04, 2023 |
| Dell          | 042P49 A00                  | [813edffc94](https://linux-hardware.org/?probe=813edffc94) | Dec 04, 2023 |
| HP            | 3031h                       | [06a9e0c346](https://linux-hardware.org/?probe=06a9e0c346) | Dec 04, 2023 |
| MSI           | 870A-G54                    | [46f9552be9](https://linux-hardware.org/?probe=46f9552be9) | Dec 03, 2023 |
| Unknown       | Unknown                     | [dca543f661](https://linux-hardware.org/?probe=dca543f661) | Dec 03, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [7a932c5570](https://linux-hardware.org/?probe=7a932c5570) | Dec 02, 2023 |
| ASRock        | B550 Phantom Gaming 4       | [9b46bc6583](https://linux-hardware.org/?probe=9b46bc6583) | Dec 02, 2023 |
| MSI           | MPG Z590M GAMING EDGE WI... | [a8495b2209](https://linux-hardware.org/?probe=a8495b2209) | Dec 01, 2023 |
| Acer          | Extensa M2610 V:1.0         | [e4c1bd6f51](https://linux-hardware.org/?probe=e4c1bd6f51) | Nov 30, 2023 |
| Gigabyte      | GA-870A-UD3                 | [062cd64553](https://linux-hardware.org/?probe=062cd64553) | Nov 29, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | [7d6885561f](https://linux-hardware.org/?probe=7d6885561f) | Nov 28, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | [e106315577](https://linux-hardware.org/?probe=e106315577) | Nov 28, 2023 |
| Acer          | Aspire TC-280               | [bfd90230bc](https://linux-hardware.org/?probe=bfd90230bc) | Nov 27, 2023 |
| Acer          | Aspire TC-280               | [4b2fec8699](https://linux-hardware.org/?probe=4b2fec8699) | Nov 27, 2023 |
| AZW           | Green G3                    | [c08be7a4cf](https://linux-hardware.org/?probe=c08be7a4cf) | Nov 26, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | [e4062fc1e4](https://linux-hardware.org/?probe=e4062fc1e4) | Nov 25, 2023 |
| HP            | 82F1                        | [09c7b87413](https://linux-hardware.org/?probe=09c7b87413) | Nov 24, 2023 |
| HP            | 82F1                        | [9ed00910d4](https://linux-hardware.org/?probe=9ed00910d4) | Nov 24, 2023 |
| Gigabyte      | GA-MA74GMT-S2               | [440e7b6c7c](https://linux-hardware.org/?probe=440e7b6c7c) | Nov 23, 2023 |
| ASUSTek       | Maximus VIII RANGER         | [c5a84018e9](https://linux-hardware.org/?probe=c5a84018e9) | Nov 23, 2023 |
| HP            | 3029h                       | [2dd2ec759b](https://linux-hardware.org/?probe=2dd2ec759b) | Nov 23, 2023 |
| HOUTER        | IPMIP-GS                    | [1daae127f8](https://linux-hardware.org/?probe=1daae127f8) | Nov 23, 2023 |
| ASUSTek       | P5G41T-M LX                 | [fca11dfd70](https://linux-hardware.org/?probe=fca11dfd70) | Nov 23, 2023 |
| MSI           | Z390-A PRO                  | [1f07a66db1](https://linux-hardware.org/?probe=1f07a66db1) | Nov 22, 2023 |
| AZW           | MINI S 10                   | [47bd270ae8](https://linux-hardware.org/?probe=47bd270ae8) | Nov 21, 2023 |
| Gigabyte      | H77N-WIFI                   | [6e0d000498](https://linux-hardware.org/?probe=6e0d000498) | Nov 20, 2023 |
| Gigabyte      | GA-MA78G-DS3H               | [8047aac511](https://linux-hardware.org/?probe=8047aac511) | Nov 20, 2023 |
| MSI           | Z97-G55 SLI                 | [9137a70965](https://linux-hardware.org/?probe=9137a70965) | Nov 20, 2023 |
| AZW           | MINI S 10                   | [a1358be402](https://linux-hardware.org/?probe=a1358be402) | Nov 20, 2023 |
| Intel         | H61                         | [bdab1dc80a](https://linux-hardware.org/?probe=bdab1dc80a) | Nov 19, 2023 |
| Intel         | H61                         | [4b5806ba4c](https://linux-hardware.org/?probe=4b5806ba4c) | Nov 19, 2023 |
| Acer          | Extensa M2610 V:1.0         | [7b70ac1965](https://linux-hardware.org/?probe=7b70ac1965) | Nov 19, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | [cb10d99771](https://linux-hardware.org/?probe=cb10d99771) | Nov 18, 2023 |
| Lenovo        | ThinkCentre M90p 5536Y1K    | [6bdc4cb524](https://linux-hardware.org/?probe=6bdc4cb524) | Nov 18, 2023 |
| Lenovo        | SHARKBAY NOK                | [d087235304](https://linux-hardware.org/?probe=d087235304) | Nov 17, 2023 |
| ECS           | H61H2-M2                    | [df572cd989](https://linux-hardware.org/?probe=df572cd989) | Nov 15, 2023 |
| JHZD          | BQM5                        | [cab813ae6e](https://linux-hardware.org/?probe=cab813ae6e) | Nov 14, 2023 |
| Gigabyte      | Z390 UD                     | [f961fee784](https://linux-hardware.org/?probe=f961fee784) | Nov 14, 2023 |
| Dell          | 0RW199                      | [e3b364ccd6](https://linux-hardware.org/?probe=e3b364ccd6) | Nov 13, 2023 |
| Intel         | H61                         | [cbefae3544](https://linux-hardware.org/?probe=cbefae3544) | Nov 13, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [8bcc86ef17](https://linux-hardware.org/?probe=8bcc86ef17) | Nov 12, 2023 |
| HP            | ProLiant ML350e Gen8 v2     | [f5de128dd1](https://linux-hardware.org/?probe=f5de128dd1) | Nov 12, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [d46548a5e6](https://linux-hardware.org/?probe=d46548a5e6) | Nov 12, 2023 |
| Dell          | 0HN7XN A01                  | [cd4230cf5b](https://linux-hardware.org/?probe=cd4230cf5b) | Nov 12, 2023 |
| Intel         | H61                         | [c65f2e03f6](https://linux-hardware.org/?probe=c65f2e03f6) | Nov 11, 2023 |
| Gigabyte      | H510M H                     | [08c8ac6e4d](https://linux-hardware.org/?probe=08c8ac6e4d) | Nov 09, 2023 |
| Gigabyte      | H510M H                     | [c0e0567705](https://linux-hardware.org/?probe=c0e0567705) | Nov 09, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [97e4b3093b](https://linux-hardware.org/?probe=97e4b3093b) | Nov 09, 2023 |
| Dell          | 0RW199                      | [11e414d343](https://linux-hardware.org/?probe=11e414d343) | Nov 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [b48cc5df9c](https://linux-hardware.org/?probe=b48cc5df9c) | Nov 08, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [abb549b943](https://linux-hardware.org/?probe=abb549b943) | Nov 07, 2023 |
| Dell          | 0KWVT8 A03                  | [864f50cabf](https://linux-hardware.org/?probe=864f50cabf) | Nov 07, 2023 |
| ASUSTek       | NODUSM3                     | [ad49ac2316](https://linux-hardware.org/?probe=ad49ac2316) | Nov 07, 2023 |
| Samsung       | DT1234567890 SEC_SW_REVI... | [4ef314d383](https://linux-hardware.org/?probe=4ef314d383) | Nov 06, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | [6c8bb1840e](https://linux-hardware.org/?probe=6c8bb1840e) | Nov 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [38b95c0462](https://linux-hardware.org/?probe=38b95c0462) | Nov 05, 2023 |
| HP            | 1497                        | [734abf0595](https://linux-hardware.org/?probe=734abf0595) | Nov 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [9d8a12d929](https://linux-hardware.org/?probe=9d8a12d929) | Nov 05, 2023 |
| Gigabyte      | M5NM1AI-GB                  | [99e2275a93](https://linux-hardware.org/?probe=99e2275a93) | Nov 05, 2023 |
| Unknown       | Unknown                     | [dbd2e07499](https://linux-hardware.org/?probe=dbd2e07499) | Nov 05, 2023 |
| Unknown       | Unknown                     | [e98e6bb977](https://linux-hardware.org/?probe=e98e6bb977) | Nov 05, 2023 |
| Toshiba       | STI 001359                  | [ebf464dbb3](https://linux-hardware.org/?probe=ebf464dbb3) | Nov 04, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [239e99c725](https://linux-hardware.org/?probe=239e99c725) | Nov 03, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [c5e282cbad](https://linux-hardware.org/?probe=c5e282cbad) | Nov 02, 2023 |
| Dell          | 0XCR8D A01                  | [bc8414b164](https://linux-hardware.org/?probe=bc8414b164) | Nov 01, 2023 |
| Gigabyte      | H510M H                     | [6db0212093](https://linux-hardware.org/?probe=6db0212093) | Nov 01, 2023 |
| Lenovo        | MAHOBAY                     | [319e545ba5](https://linux-hardware.org/?probe=319e545ba5) | Oct 31, 2023 |
| MSI           | A320M PRO-M2 V2             | [3b667e2123](https://linux-hardware.org/?probe=3b667e2123) | Oct 31, 2023 |
| Pegatron      | EVANS                       | [3ea2a80843](https://linux-hardware.org/?probe=3ea2a80843) | Oct 31, 2023 |
| Pegatron      | EVANS                       | [52c3eeea68](https://linux-hardware.org/?probe=52c3eeea68) | Oct 31, 2023 |
| HP            | 21F5 0A                     | [097ce56daf](https://linux-hardware.org/?probe=097ce56daf) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [c447277c0b](https://linux-hardware.org/?probe=c447277c0b) | Oct 30, 2023 |
| HP            | 1998                        | [2182b05a45](https://linux-hardware.org/?probe=2182b05a45) | Oct 29, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [28f261fb9a](https://linux-hardware.org/?probe=28f261fb9a) | Oct 29, 2023 |
| MSI           | Z370M MORTAR                | [0af3708cd3](https://linux-hardware.org/?probe=0af3708cd3) | Oct 29, 2023 |
| HP            | 18E4                        | [b192ce4f35](https://linux-hardware.org/?probe=b192ce4f35) | Oct 28, 2023 |
| Dell          | 06X1TJ A00                  | [c2bc73c67b](https://linux-hardware.org/?probe=c2bc73c67b) | Oct 28, 2023 |
| ASUSTek       | P8B75-M                     | [b9830b7f02](https://linux-hardware.org/?probe=b9830b7f02) | Oct 28, 2023 |
| MSI           | Boston                      | [66f7505c8b](https://linux-hardware.org/?probe=66f7505c8b) | Oct 27, 2023 |
| HP            | 2215                        | [01fd79c4fe](https://linux-hardware.org/?probe=01fd79c4fe) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | [463b5f73b5](https://linux-hardware.org/?probe=463b5f73b5) | Oct 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [67021475e9](https://linux-hardware.org/?probe=67021475e9) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | [ec0dcdaa76](https://linux-hardware.org/?probe=ec0dcdaa76) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | [4f4d354524](https://linux-hardware.org/?probe=4f4d354524) | Oct 26, 2023 |
| Intel         | H61                         | [cb396f193e](https://linux-hardware.org/?probe=cb396f193e) | Oct 26, 2023 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [ca4ce5575c](https://linux-hardware.org/?probe=ca4ce5575c) | Oct 26, 2023 |
| LORD ELECT... | Guso G4x + ICH7 Series M... | [c6f81cf996](https://linux-hardware.org/?probe=c6f81cf996) | Oct 25, 2023 |
| ASUSTek       | P8Z77-V LX                  | [6f9c14dc54](https://linux-hardware.org/?probe=6f9c14dc54) | Oct 24, 2023 |
| Gigabyte      | B450 AORUS M                | [706967e8e6](https://linux-hardware.org/?probe=706967e8e6) | Oct 24, 2023 |
| Gigabyte      | B85M-D3V Plus               | [845b1f10ef](https://linux-hardware.org/?probe=845b1f10ef) | Oct 24, 2023 |
| Dell          | 0RCPW3 A03                  | [a461b9f3e7](https://linux-hardware.org/?probe=a461b9f3e7) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | [905555c7d5](https://linux-hardware.org/?probe=905555c7d5) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | [5f6d67d67e](https://linux-hardware.org/?probe=5f6d67d67e) | Oct 23, 2023 |
| ASRock        | AB350 Pro4                  | [961b658ac5](https://linux-hardware.org/?probe=961b658ac5) | Oct 23, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [6f89b3f8ad](https://linux-hardware.org/?probe=6f89b3f8ad) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | [ff9e1d6c16](https://linux-hardware.org/?probe=ff9e1d6c16) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | [9999b4b89a](https://linux-hardware.org/?probe=9999b4b89a) | Oct 22, 2023 |
| ASUSTek       | SABERTOOTH P67              | [5536078e9f](https://linux-hardware.org/?probe=5536078e9f) | Oct 21, 2023 |
| ASRock        | B450 Pro4                   | [d8b8f7bafe](https://linux-hardware.org/?probe=d8b8f7bafe) | Oct 20, 2023 |
| Lenovo        | SHARKBAY NOK                | [cb8d8311e7](https://linux-hardware.org/?probe=cb8d8311e7) | Oct 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [af96c09a64](https://linux-hardware.org/?probe=af96c09a64) | Oct 19, 2023 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [77079711d3](https://linux-hardware.org/?probe=77079711d3) | Oct 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7fed113f9b](https://linux-hardware.org/?probe=7fed113f9b) | Oct 19, 2023 |
| EPSON DIRE... | AT992E                      | [bdc9d825d8](https://linux-hardware.org/?probe=bdc9d825d8) | Oct 18, 2023 |
| EPSON DIRE... | AT992E                      | [ec5284109e](https://linux-hardware.org/?probe=ec5284109e) | Oct 18, 2023 |
| Unknown       | Unknown                     | [03cf657f5a](https://linux-hardware.org/?probe=03cf657f5a) | Oct 17, 2023 |
| ASUSTek       | P5Q PRO TURBO               | [16a117accb](https://linux-hardware.org/?probe=16a117accb) | Oct 15, 2023 |
| ASUSTek       | H61M-K                      | [d43a466e59](https://linux-hardware.org/?probe=d43a466e59) | Oct 14, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [f4e7334b7e](https://linux-hardware.org/?probe=f4e7334b7e) | Oct 14, 2023 |
| ASUSTek       | P7H55-M LX                  | [17d1931208](https://linux-hardware.org/?probe=17d1931208) | Oct 13, 2023 |
| MSI           | B85M-E45                    | [6ad9d3ff3c](https://linux-hardware.org/?probe=6ad9d3ff3c) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | [ffd832c09d](https://linux-hardware.org/?probe=ffd832c09d) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | [c70591ee60](https://linux-hardware.org/?probe=c70591ee60) | Oct 12, 2023 |
| Dell          | 0NDYHG A01                  | [02414ff1af](https://linux-hardware.org/?probe=02414ff1af) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | [cc50dc0894](https://linux-hardware.org/?probe=cc50dc0894) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | [754748eac6](https://linux-hardware.org/?probe=754748eac6) | Oct 11, 2023 |
| Dell          | 0XHGV1 A00                  | [adda7a23c2](https://linux-hardware.org/?probe=adda7a23c2) | Oct 11, 2023 |
| AMI           | Intel                       | [1615dc16ba](https://linux-hardware.org/?probe=1615dc16ba) | Oct 10, 2023 |
| Lenovo        | Tiger Hill                  | [cdd9f65bf5](https://linux-hardware.org/?probe=cdd9f65bf5) | Oct 10, 2023 |
| Gigabyte      | H55M-USB3                   | [c4ae24b408](https://linux-hardware.org/?probe=c4ae24b408) | Oct 10, 2023 |
| Toshiba       | Mobile Intel 4 Series/IC... | [d97f4b5e6f](https://linux-hardware.org/?probe=d97f4b5e6f) | Oct 09, 2023 |
| Unknown       | Unknown                     | [1eeecb8823](https://linux-hardware.org/?probe=1eeecb8823) | Oct 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [067260a51f](https://linux-hardware.org/?probe=067260a51f) | Oct 08, 2023 |
| Shuttle       | FS110                       | [cd7c40ed57](https://linux-hardware.org/?probe=cd7c40ed57) | Oct 08, 2023 |
| MSI           | G41M-P33 Combo              | [b82e5d0718](https://linux-hardware.org/?probe=b82e5d0718) | Oct 07, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [f347154767](https://linux-hardware.org/?probe=f347154767) | Oct 07, 2023 |
| Pegatron      | EVANS                       | [f798f24c90](https://linux-hardware.org/?probe=f798f24c90) | Oct 07, 2023 |
| MSI           | G41M-P33 Combo              | [299eee42c7](https://linux-hardware.org/?probe=299eee42c7) | Oct 07, 2023 |
| Intel         | X99                         | [9bc14ff597](https://linux-hardware.org/?probe=9bc14ff597) | Oct 06, 2023 |
| Gigabyte      | H510M H                     | [9be367f445](https://linux-hardware.org/?probe=9be367f445) | Oct 06, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [ff815f228b](https://linux-hardware.org/?probe=ff815f228b) | Oct 05, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [a6668a2378](https://linux-hardware.org/?probe=a6668a2378) | Oct 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [de22cbed3e](https://linux-hardware.org/?probe=de22cbed3e) | Oct 04, 2023 |
| Dell          | 0RW199                      | [f829184aa0](https://linux-hardware.org/?probe=f829184aa0) | Oct 04, 2023 |
| Lenovo        | Tiger Hill                  | [4a3ef3e12f](https://linux-hardware.org/?probe=4a3ef3e12f) | Oct 03, 2023 |
| Pegatron      | EVANS                       | [3f2a4fe53e](https://linux-hardware.org/?probe=3f2a4fe53e) | Oct 03, 2023 |
| Gigabyte      | Z270-HD3-CF                 | [c23994e74a](https://linux-hardware.org/?probe=c23994e74a) | Oct 02, 2023 |
| MSI           | B85M-E45                    | [12fa4b4da3](https://linux-hardware.org/?probe=12fa4b4da3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | [2c6f35e1d3](https://linux-hardware.org/?probe=2c6f35e1d3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | [ded620f59b](https://linux-hardware.org/?probe=ded620f59b) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [5698c85faa](https://linux-hardware.org/?probe=5698c85faa) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [056bfb8474](https://linux-hardware.org/?probe=056bfb8474) | Oct 01, 2023 |
| Intel         | X79M-S                      | [dfa1322112](https://linux-hardware.org/?probe=dfa1322112) | Oct 01, 2023 |
| MSI           | B75MA-E33                   | [8d558a64e8](https://linux-hardware.org/?probe=8d558a64e8) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [e0cdb74f25](https://linux-hardware.org/?probe=e0cdb74f25) | Oct 01, 2023 |
| Acer          | Predator G3610              | [cddfa514ba](https://linux-hardware.org/?probe=cddfa514ba) | Sep 30, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [c93af00811](https://linux-hardware.org/?probe=c93af00811) | Sep 30, 2023 |
| MP            | MS-7848                     | [63d5662351](https://linux-hardware.org/?probe=63d5662351) | Sep 30, 2023 |
| ASUSTek       | P8Z77-V LX                  | [186991da49](https://linux-hardware.org/?probe=186991da49) | Sep 29, 2023 |
| Gigabyte      | 970A-DS3P                   | [145f7eccd3](https://linux-hardware.org/?probe=145f7eccd3) | Sep 29, 2023 |
| ASUSTek       | P8Z77-V LX                  | [a318f83948](https://linux-hardware.org/?probe=a318f83948) | Sep 29, 2023 |
| MSI           | A320M-A PRO MAX             | [4aa521a31f](https://linux-hardware.org/?probe=4aa521a31f) | Sep 29, 2023 |
| HP            | 2B35                        | [2f63f14724](https://linux-hardware.org/?probe=2f63f14724) | Sep 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ce3a9f8960](https://linux-hardware.org/?probe=ce3a9f8960) | Sep 28, 2023 |
| MSI           | A320M-A PRO MAX             | [f6c6bfc3fe](https://linux-hardware.org/?probe=f6c6bfc3fe) | Sep 27, 2023 |
| Intel         | X79G V2.x                   | [3d001a09ab](https://linux-hardware.org/?probe=3d001a09ab) | Sep 27, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [811818acb8](https://linux-hardware.org/?probe=811818acb8) | Sep 26, 2023 |
| Dell          | 0NW6H5 A00                  | [e7e87a1269](https://linux-hardware.org/?probe=e7e87a1269) | Sep 26, 2023 |
| Dell          | 0Y5DDC A00                  | [29feb62e32](https://linux-hardware.org/?probe=29feb62e32) | Sep 25, 2023 |
| Dell          | 0D28YY A01                  | [7c901ae7fd](https://linux-hardware.org/?probe=7c901ae7fd) | Sep 25, 2023 |
| Dell          | 0HN7XN A01                  | [fd3ce44501](https://linux-hardware.org/?probe=fd3ce44501) | Sep 23, 2023 |
| Unknown       | Unknown                     | [e2c17f3a64](https://linux-hardware.org/?probe=e2c17f3a64) | Sep 23, 2023 |
| Intel         | DB85FL AAG89861-201         | [58b289a69d](https://linux-hardware.org/?probe=58b289a69d) | Sep 23, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [e513362f71](https://linux-hardware.org/?probe=e513362f71) | Sep 22, 2023 |
| ASUSTek       | PRIME B460M-A               | [7ecfb9c56f](https://linux-hardware.org/?probe=7ecfb9c56f) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [47e5429752](https://linux-hardware.org/?probe=47e5429752) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [a35f78cead](https://linux-hardware.org/?probe=a35f78cead) | Sep 21, 2023 |
| AZW           | MINI S 10                   | [e393d95960](https://linux-hardware.org/?probe=e393d95960) | Sep 21, 2023 |
| Gigabyte      | GA-870A-UD3                 | [e57a830f9c](https://linux-hardware.org/?probe=e57a830f9c) | Sep 21, 2023 |
| Dell          | 0F3KHR A00                  | [dd7f2cf2b2](https://linux-hardware.org/?probe=dd7f2cf2b2) | Sep 20, 2023 |
| Lenovo        | H320 10044                  | [bf4ffce3e9](https://linux-hardware.org/?probe=bf4ffce3e9) | Sep 20, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [776633dd59](https://linux-hardware.org/?probe=776633dd59) | Sep 20, 2023 |
| Dell          | 0F3KHR A00                  | [fcdaf47870](https://linux-hardware.org/?probe=fcdaf47870) | Sep 20, 2023 |
| Unknown       | Unknown                     | [e4dc880c6f](https://linux-hardware.org/?probe=e4dc880c6f) | Sep 20, 2023 |
| Dell          | 0RW199                      | [2857c6ada1](https://linux-hardware.org/?probe=2857c6ada1) | Sep 20, 2023 |
| Gigabyte      | Z790 UD AC                  | [83af285806](https://linux-hardware.org/?probe=83af285806) | Sep 20, 2023 |
| Biostar       | H61MLC                      | [154ead8447](https://linux-hardware.org/?probe=154ead8447) | Sep 19, 2023 |
| ASRock        | AB350 Pro4                  | [f45c7732e3](https://linux-hardware.org/?probe=f45c7732e3) | Sep 19, 2023 |
| AZW           | GTR V21                     | [5066e153f8](https://linux-hardware.org/?probe=5066e153f8) | Sep 19, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | [202375fbb7](https://linux-hardware.org/?probe=202375fbb7) | Sep 18, 2023 |
| HP            | 3047h                       | [a955e9b6c6](https://linux-hardware.org/?probe=a955e9b6c6) | Sep 17, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [9e7069cdc3](https://linux-hardware.org/?probe=9e7069cdc3) | Sep 17, 2023 |
| Dell          | 0C27VV A02                  | [08ed0347db](https://linux-hardware.org/?probe=08ed0347db) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [d4d891ca35](https://linux-hardware.org/?probe=d4d891ca35) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | [b42ad40603](https://linux-hardware.org/?probe=b42ad40603) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | [3a230dc10f](https://linux-hardware.org/?probe=3a230dc10f) | Sep 16, 2023 |
| Acer          | Aspire XC-330               | [8913a6c47f](https://linux-hardware.org/?probe=8913a6c47f) | Sep 16, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [2fa5c8bb34](https://linux-hardware.org/?probe=2fa5c8bb34) | Sep 16, 2023 |
| MSI           | B550-A PRO                  | [83cb90361c](https://linux-hardware.org/?probe=83cb90361c) | Sep 14, 2023 |
| MSI           | Z170A-G45 GAMING            | [40aee3739e](https://linux-hardware.org/?probe=40aee3739e) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | [9bbec30b2f](https://linux-hardware.org/?probe=9bbec30b2f) | Sep 13, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [3cba209625](https://linux-hardware.org/?probe=3cba209625) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [4dcd4e8234](https://linux-hardware.org/?probe=4dcd4e8234) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | [cbfa4c2641](https://linux-hardware.org/?probe=cbfa4c2641) | Sep 13, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [b94c2a0420](https://linux-hardware.org/?probe=b94c2a0420) | Sep 13, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | [e4f73d159c](https://linux-hardware.org/?probe=e4f73d159c) | Sep 12, 2023 |
| Gigabyte      | B85M-HD3                    | [8ddbf6665f](https://linux-hardware.org/?probe=8ddbf6665f) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [9fc04871b0](https://linux-hardware.org/?probe=9fc04871b0) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [a80cffbabe](https://linux-hardware.org/?probe=a80cffbabe) | Sep 11, 2023 |
| Dell          | 0HY9JP A02                  | [5907e59551](https://linux-hardware.org/?probe=5907e59551) | Sep 11, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | [c57a3a012d](https://linux-hardware.org/?probe=c57a3a012d) | Sep 11, 2023 |
| ASUSTek       | PRIME H370-A                | [c757d0e2c3](https://linux-hardware.org/?probe=c757d0e2c3) | Sep 11, 2023 |
| ASUSTek       | CG8270                      | [a8db1b43ce](https://linux-hardware.org/?probe=a8db1b43ce) | Sep 09, 2023 |
| ASUSTek       | CG8270                      | [26b9818094](https://linux-hardware.org/?probe=26b9818094) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | [6f66e35ec3](https://linux-hardware.org/?probe=6f66e35ec3) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | [9306917366](https://linux-hardware.org/?probe=9306917366) | Sep 09, 2023 |
| HP            | 8299                        | [df4048bcc4](https://linux-hardware.org/?probe=df4048bcc4) | Sep 08, 2023 |
| ASUSTek       | P5KPL-VM                    | [97d9faccab](https://linux-hardware.org/?probe=97d9faccab) | Sep 07, 2023 |
| ASUSTek       | P5KPL-VM                    | [3112302ff6](https://linux-hardware.org/?probe=3112302ff6) | Sep 07, 2023 |
| Acer          | Aspire X1470                | [d136074365](https://linux-hardware.org/?probe=d136074365) | Sep 07, 2023 |
| Acer          | Aspire X1470                | [a965ab170a](https://linux-hardware.org/?probe=a965ab170a) | Sep 07, 2023 |
| ASUSTek       | SABERTOOTH P67              | [002bdcd34d](https://linux-hardware.org/?probe=002bdcd34d) | Sep 07, 2023 |
| Pegatron      | 2AD5                        | [fe02bb3d71](https://linux-hardware.org/?probe=fe02bb3d71) | Sep 07, 2023 |
| Dell          | 02YYK5 A01                  | [6bb77310bf](https://linux-hardware.org/?probe=6bb77310bf) | Sep 06, 2023 |
| Pegatron      | IPXSB-H61                   | [415ba1cfc1](https://linux-hardware.org/?probe=415ba1cfc1) | Sep 06, 2023 |
| Dell          | 0F3KHR A00                  | [53bfbec77e](https://linux-hardware.org/?probe=53bfbec77e) | Sep 06, 2023 |
| Gigabyte      | 970A-DS3P                   | [3227a8a6bc](https://linux-hardware.org/?probe=3227a8a6bc) | Sep 06, 2023 |
| Alienware     | 0446JC A01                  | [d0c3088707](https://linux-hardware.org/?probe=d0c3088707) | Sep 06, 2023 |
| HP            | 0B54h D                     | [6fc93ef4ee](https://linux-hardware.org/?probe=6fc93ef4ee) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [f8ec276ea3](https://linux-hardware.org/?probe=f8ec276ea3) | Sep 05, 2023 |
| Gigabyte      | 970A-DS3P                   | [788841792b](https://linux-hardware.org/?probe=788841792b) | Sep 04, 2023 |
| Inventec      | Z CLASS A02                 | [7f0254a775](https://linux-hardware.org/?probe=7f0254a775) | Sep 04, 2023 |
| Pegatron      | IPXSB-H61                   | [78a354984d](https://linux-hardware.org/?probe=78a354984d) | Sep 04, 2023 |
| Dell          | 0D28YY A01                  | [ae79e6a689](https://linux-hardware.org/?probe=ae79e6a689) | Sep 04, 2023 |
| Gigabyte      | Z97X-UD5H                   | [2c9b64c445](https://linux-hardware.org/?probe=2c9b64c445) | Sep 03, 2023 |
| Intel         | DB85FL AAG89861-201         | [9845368fc2](https://linux-hardware.org/?probe=9845368fc2) | Sep 03, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [eee58fd067](https://linux-hardware.org/?probe=eee58fd067) | Sep 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6215db2c5a](https://linux-hardware.org/?probe=6215db2c5a) | Sep 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | [53b682d960](https://linux-hardware.org/?probe=53b682d960) | Sep 02, 2023 |
| Intel         | X79M-S                      | [a6952c68e4](https://linux-hardware.org/?probe=a6952c68e4) | Sep 01, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [be8b002a45](https://linux-hardware.org/?probe=be8b002a45) | Aug 31, 2023 |
| Intel         | DB85FL AAG89861-201         | [035f2909a1](https://linux-hardware.org/?probe=035f2909a1) | Aug 30, 2023 |
| Lenovo        | SDK0E50510 WIN              | [d963970016](https://linux-hardware.org/?probe=d963970016) | Aug 30, 2023 |
| HP            | 8054                        | [f73271d96e](https://linux-hardware.org/?probe=f73271d96e) | Aug 30, 2023 |
| Gigabyte      | Z97X-UD5H                   | [3fb03adafb](https://linux-hardware.org/?probe=3fb03adafb) | Aug 29, 2023 |
| Dell          | 0GY6Y8 A02                  | [fffbca3973](https://linux-hardware.org/?probe=fffbca3973) | Aug 28, 2023 |
| Intel         | H61                         | [9e5ed4db62](https://linux-hardware.org/?probe=9e5ed4db62) | Aug 28, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [929efec703](https://linux-hardware.org/?probe=929efec703) | Aug 27, 2023 |
| eMachines     | EL1352                      | [5f9258beb2](https://linux-hardware.org/?probe=5f9258beb2) | Aug 27, 2023 |
| GuoGuang      | IC2M1028N                   | [ffcd5b9fa5](https://linux-hardware.org/?probe=ffcd5b9fa5) | Aug 25, 2023 |
| Pegatron      | BOWIE                       | [270cd028cf](https://linux-hardware.org/?probe=270cd028cf) | Aug 25, 2023 |
| MSI           | Z87 MPOWER MAX              | [42d3a714ac](https://linux-hardware.org/?probe=42d3a714ac) | Aug 24, 2023 |
| AZW           | MINI S                      | [7712e558c5](https://linux-hardware.org/?probe=7712e558c5) | Aug 24, 2023 |
| AZW           | MINI S                      | [6296a4f71d](https://linux-hardware.org/?probe=6296a4f71d) | Aug 24, 2023 |
| HP            | 8299                        | [aa27bed4f1](https://linux-hardware.org/?probe=aa27bed4f1) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [82c63f13d1](https://linux-hardware.org/?probe=82c63f13d1) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [1aee954611](https://linux-hardware.org/?probe=1aee954611) | Aug 22, 2023 |
| Unknown       | Unknown                     | [9b52370ec1](https://linux-hardware.org/?probe=9b52370ec1) | Aug 22, 2023 |
| Unknown       | Unknown                     | [51e91dd03e](https://linux-hardware.org/?probe=51e91dd03e) | Aug 22, 2023 |
| Dell          | 0GY6Y8 A02                  | [409855b61b](https://linux-hardware.org/?probe=409855b61b) | Aug 21, 2023 |
| Dell          | 08NPPY A00                  | [7a206bdd57](https://linux-hardware.org/?probe=7a206bdd57) | Aug 21, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | [2ac06099d8](https://linux-hardware.org/?probe=2ac06099d8) | Aug 19, 2023 |
| ASUSTek       | H97-PRO GAMER               | [f97c8a25c5](https://linux-hardware.org/?probe=f97c8a25c5) | Aug 19, 2023 |
| ASUSTek       | P5L-MX                      | [f06dbc1b8c](https://linux-hardware.org/?probe=f06dbc1b8c) | Aug 19, 2023 |
| HP            | 3047h                       | [91d9eaa1de](https://linux-hardware.org/?probe=91d9eaa1de) | Aug 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [d109b04177](https://linux-hardware.org/?probe=d109b04177) | Aug 19, 2023 |
| HP            | 3047h                       | [a4aa888c24](https://linux-hardware.org/?probe=a4aa888c24) | Aug 18, 2023 |
| HP            | 3032h                       | [34a300f540](https://linux-hardware.org/?probe=34a300f540) | Aug 17, 2023 |
| Intel         | X79M-S                      | [d79895d82c](https://linux-hardware.org/?probe=d79895d82c) | Aug 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | [7c1a42d442](https://linux-hardware.org/?probe=7c1a42d442) | Aug 17, 2023 |
| ASUSTek       | B150M-C/BR                  | [78e12f014e](https://linux-hardware.org/?probe=78e12f014e) | Aug 17, 2023 |
| Dell          | 0M6C7G A00                  | [50731e7c54](https://linux-hardware.org/?probe=50731e7c54) | Aug 16, 2023 |
| ASRock        | 970 Pro3 R2.0               | [50b5957370](https://linux-hardware.org/?probe=50b5957370) | Aug 16, 2023 |
| HP            | 09CCh                       | [947fb1edcb](https://linux-hardware.org/?probe=947fb1edcb) | Aug 15, 2023 |
| Gigabyte      | H61M-DS2V                   | [a1dccbbd3f](https://linux-hardware.org/?probe=a1dccbbd3f) | Aug 15, 2023 |
| Biostar       | H410MH                      | [abe98ae584](https://linux-hardware.org/?probe=abe98ae584) | Aug 15, 2023 |
| Gigabyte      | H110M-H-CF                  | [bb4bf558dd](https://linux-hardware.org/?probe=bb4bf558dd) | Aug 15, 2023 |
| Dell          | 02YRK5 A02                  | [e79cdd0ba3](https://linux-hardware.org/?probe=e79cdd0ba3) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f09f15784f](https://linux-hardware.org/?probe=f09f15784f) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | [dea6e2f8b8](https://linux-hardware.org/?probe=dea6e2f8b8) | Aug 13, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | [7e47b7128b](https://linux-hardware.org/?probe=7e47b7128b) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | [1034423357](https://linux-hardware.org/?probe=1034423357) | Aug 13, 2023 |
| Biostar       | A770 A2+                    | [ff8bec8b75](https://linux-hardware.org/?probe=ff8bec8b75) | Aug 12, 2023 |
| MSI           | 2AE0                        | [b8a2a0eb5c](https://linux-hardware.org/?probe=b8a2a0eb5c) | Aug 12, 2023 |
| HP            | 09CCh                       | [15bfdf7213](https://linux-hardware.org/?probe=15bfdf7213) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | [d35bac0620](https://linux-hardware.org/?probe=d35bac0620) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | [fb7d0009fd](https://linux-hardware.org/?probe=fb7d0009fd) | Aug 12, 2023 |
| HP            | 3032h                       | [1727f042cd](https://linux-hardware.org/?probe=1727f042cd) | Aug 11, 2023 |
| Intel         | DZ68BC AAG30742-401         | [9bf37df045](https://linux-hardware.org/?probe=9bf37df045) | Aug 10, 2023 |
| Dell          | 0WMJ54 A01                  | [6e9ca3c833](https://linux-hardware.org/?probe=6e9ca3c833) | Aug 09, 2023 |
| HP            | 3032h                       | [03a8cc31ea](https://linux-hardware.org/?probe=03a8cc31ea) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | [6047747c8f](https://linux-hardware.org/?probe=6047747c8f) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | [8a11b56d79](https://linux-hardware.org/?probe=8a11b56d79) | Aug 09, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [2e30c62b25](https://linux-hardware.org/?probe=2e30c62b25) | Aug 08, 2023 |
| Intel         | X79M-S                      | [8250cad3d6](https://linux-hardware.org/?probe=8250cad3d6) | Aug 08, 2023 |
| Gigabyte      | B450 AORUS M                | [965220ce86](https://linux-hardware.org/?probe=965220ce86) | Aug 07, 2023 |
| Pegatron      | IPMMB-MQ1                   | [70c450c395](https://linux-hardware.org/?probe=70c450c395) | Aug 06, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | [6b22ae1f36](https://linux-hardware.org/?probe=6b22ae1f36) | Aug 06, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [1af709c14e](https://linux-hardware.org/?probe=1af709c14e) | Aug 05, 2023 |
| Gigabyte      | Z97X-UD5H                   | [3bc330734d](https://linux-hardware.org/?probe=3bc330734d) | Aug 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [3b5e9f52a2](https://linux-hardware.org/?probe=3b5e9f52a2) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [5d998a099e](https://linux-hardware.org/?probe=5d998a099e) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | [e57d71e056](https://linux-hardware.org/?probe=e57d71e056) | Aug 05, 2023 |
| Unknown       | Unknown                     | [8ee9cccace](https://linux-hardware.org/?probe=8ee9cccace) | Aug 05, 2023 |
| ASRock        | N68-VS3 UCC                 | [3793d876eb](https://linux-hardware.org/?probe=3793d876eb) | Aug 04, 2023 |
| Gigabyte      | B550M DS3H AC               | [f27f9b2a7f](https://linux-hardware.org/?probe=f27f9b2a7f) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | [8193f810ab](https://linux-hardware.org/?probe=8193f810ab) | Aug 03, 2023 |
| ASUSTek       | PRIME B450M-K II            | [35cf0fd859](https://linux-hardware.org/?probe=35cf0fd859) | Aug 03, 2023 |
| Intel         | X79M-S                      | [5a4d94f325](https://linux-hardware.org/?probe=5a4d94f325) | Aug 02, 2023 |
| HP            | 89B5 A                      | [cb6f36f32c](https://linux-hardware.org/?probe=cb6f36f32c) | Aug 02, 2023 |
| Pegatron      | BOWIE                       | [cfce53f1a3](https://linux-hardware.org/?probe=cfce53f1a3) | Aug 02, 2023 |
| Unknown       | Unknown                     | [731a8b0e31](https://linux-hardware.org/?probe=731a8b0e31) | Aug 02, 2023 |
| ASUSTek       | P8H61-M LX                  | [287740b630](https://linux-hardware.org/?probe=287740b630) | Aug 01, 2023 |
| HP            | 1496                        | [24863488f0](https://linux-hardware.org/?probe=24863488f0) | Aug 01, 2023 |
| Dell          | 0HJ054                      | [85ceb83c22](https://linux-hardware.org/?probe=85ceb83c22) | Jul 31, 2023 |
| ASUSTek       | M4N68T-M LE                 | [90dce7a9cf](https://linux-hardware.org/?probe=90dce7a9cf) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [0ce1be51b9](https://linux-hardware.org/?probe=0ce1be51b9) | Jul 30, 2023 |
| Gigabyte      | M68MT-S2                    | [b1125cd76c](https://linux-hardware.org/?probe=b1125cd76c) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | [1771e4ca4b](https://linux-hardware.org/?probe=1771e4ca4b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | [e668b29cf4](https://linux-hardware.org/?probe=e668b29cf4) | Jul 29, 2023 |
| ASUSTek       | P7H55-M LX                  | [bc92202f16](https://linux-hardware.org/?probe=bc92202f16) | Jul 29, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | [8c930cc5e4](https://linux-hardware.org/?probe=8c930cc5e4) | Jul 29, 2023 |
| MSI           | B75MA-E33                   | [310207e0fd](https://linux-hardware.org/?probe=310207e0fd) | Jul 29, 2023 |
| Pegatron      | BOWIE                       | [4d413cb864](https://linux-hardware.org/?probe=4d413cb864) | Jul 28, 2023 |
| HP            | 3397                        | [e61ccd6dbf](https://linux-hardware.org/?probe=e61ccd6dbf) | Jul 27, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [e7fdf45ff0](https://linux-hardware.org/?probe=e7fdf45ff0) | Jul 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [2f12124bed](https://linux-hardware.org/?probe=2f12124bed) | Jul 27, 2023 |
| MP            | MS-7848                     | [3dd9f22548](https://linux-hardware.org/?probe=3dd9f22548) | Jul 26, 2023 |
| Acer          | Elena                       | [78eff851f2](https://linux-hardware.org/?probe=78eff851f2) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | [1b062f3c31](https://linux-hardware.org/?probe=1b062f3c31) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | [bca4424b5d](https://linux-hardware.org/?probe=bca4424b5d) | Jul 26, 2023 |
| ASUSTek       | B250 MINING EXPERT          | [0236b3ce26](https://linux-hardware.org/?probe=0236b3ce26) | Jul 26, 2023 |
| Dell          | 088DT1 A01                  | [1355a4f2f4](https://linux-hardware.org/?probe=1355a4f2f4) | Jul 25, 2023 |
| HP            | 8350                        | [f17382c501](https://linux-hardware.org/?probe=f17382c501) | Jul 23, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [13bb65f561](https://linux-hardware.org/?probe=13bb65f561) | Jul 23, 2023 |
| Dell          | 0MN1TX A04                  | [4ff31f4185](https://linux-hardware.org/?probe=4ff31f4185) | Jul 22, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [b8cf03e7b7](https://linux-hardware.org/?probe=b8cf03e7b7) | Jul 22, 2023 |
| ASUSTek       | F1A55-M LX                  | [87b85c2e28](https://linux-hardware.org/?probe=87b85c2e28) | Jul 22, 2023 |
| ASRock        | B85M                        | [c4f0b0b1fa](https://linux-hardware.org/?probe=c4f0b0b1fa) | Jul 22, 2023 |
| HP            | 3048h                       | [1be902df43](https://linux-hardware.org/?probe=1be902df43) | Jul 21, 2023 |
| HP            | 3047h                       | [07de35877b](https://linux-hardware.org/?probe=07de35877b) | Jul 21, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [9afd0f1d0f](https://linux-hardware.org/?probe=9afd0f1d0f) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [35c4e6ad97](https://linux-hardware.org/?probe=35c4e6ad97) | Jul 20, 2023 |
| HP            | 8767 A                      | [d5275f1025](https://linux-hardware.org/?probe=d5275f1025) | Jul 20, 2023 |
| Dell          | 0F5C5X A00                  | [3832c8f626](https://linux-hardware.org/?probe=3832c8f626) | Jul 20, 2023 |
| Dell          | 0C27VV A02                  | [da1c963814](https://linux-hardware.org/?probe=da1c963814) | Jul 19, 2023 |
| Dell          | 0C27VV A02                  | [02008985ce](https://linux-hardware.org/?probe=02008985ce) | Jul 19, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | [57b17e7ae1](https://linux-hardware.org/?probe=57b17e7ae1) | Jul 15, 2023 |
| Gigabyte      | Z370M AORUS Gaming-CF       | [64a0d52846](https://linux-hardware.org/?probe=64a0d52846) | Jul 15, 2023 |
| Gigabyte      | B450 AORUS M                | [2f5c2842c2](https://linux-hardware.org/?probe=2f5c2842c2) | Jul 14, 2023 |
| Dell          | 0FDY5C A00                  | [35399aae18](https://linux-hardware.org/?probe=35399aae18) | Jul 14, 2023 |
| Dell          | 0D441T A03                  | [622890c12a](https://linux-hardware.org/?probe=622890c12a) | Jul 14, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [b690698c10](https://linux-hardware.org/?probe=b690698c10) | Jul 12, 2023 |
| HP            | 8299                        | [763cebf303](https://linux-hardware.org/?probe=763cebf303) | Jul 12, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7c6ad4407b](https://linux-hardware.org/?probe=7c6ad4407b) | Jul 11, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [c81c5855d4](https://linux-hardware.org/?probe=c81c5855d4) | Jul 11, 2023 |
| Acer          | EG31M R01-B1                | [dbc5e1d5db](https://linux-hardware.org/?probe=dbc5e1d5db) | Jul 11, 2023 |
| Acer          | EG31M R01-B1                | [12f533494b](https://linux-hardware.org/?probe=12f533494b) | Jul 11, 2023 |
| ASRock        | A320M-HDV R4.0              | [ab81f36697](https://linux-hardware.org/?probe=ab81f36697) | Jul 11, 2023 |
| Dell          | 09WH54 A00                  | [b118891f3d](https://linux-hardware.org/?probe=b118891f3d) | Jul 10, 2023 |
| ASRock        | B460M Pro4                  | [c972293107](https://linux-hardware.org/?probe=c972293107) | Jul 10, 2023 |
| ASUSTek       | GRYPHON Z87                 | [2ed1092e31](https://linux-hardware.org/?probe=2ed1092e31) | Jul 10, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [213c80bbee](https://linux-hardware.org/?probe=213c80bbee) | Jul 09, 2023 |
| ASUSTek       | PRIME B350M-A               | [be65f2aa45](https://linux-hardware.org/?probe=be65f2aa45) | Jul 08, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [2d342d7a37](https://linux-hardware.org/?probe=2d342d7a37) | Jul 07, 2023 |
| Dell          | 0HN7XN A01                  | [24a4044173](https://linux-hardware.org/?probe=24a4044173) | Jul 06, 2023 |
| Gigabyte      | B75M-D3H                    | [8a9c93e501](https://linux-hardware.org/?probe=8a9c93e501) | Jul 06, 2023 |
| ASRock        | FP6D4-P1                    | [42b5bdcdd7](https://linux-hardware.org/?probe=42b5bdcdd7) | Jul 05, 2023 |
| Positivo      | POS-EIH61CE SIM             | [48b35c757d](https://linux-hardware.org/?probe=48b35c757d) | Jul 05, 2023 |
| Intel         | H55                         | [8f8ff68380](https://linux-hardware.org/?probe=8f8ff68380) | Jul 04, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [9bca67bb40](https://linux-hardware.org/?probe=9bca67bb40) | Jul 04, 2023 |
| HP            | 21F5 0A                     | [bc7304ba1c](https://linux-hardware.org/?probe=bc7304ba1c) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | [452fe27c46](https://linux-hardware.org/?probe=452fe27c46) | Jul 04, 2023 |
| MSI           | 760GM-P23                   | [168d5b0b7b](https://linux-hardware.org/?probe=168d5b0b7b) | Jul 04, 2023 |
| Foxconn       | G41S/G41S-K                 | [21adb87fbd](https://linux-hardware.org/?probe=21adb87fbd) | Jul 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [7672f159bf](https://linux-hardware.org/?probe=7672f159bf) | Jul 03, 2023 |
| Dell          | 0GY6Y8 A02                  | [729dbec695](https://linux-hardware.org/?probe=729dbec695) | Jul 02, 2023 |
| MSI           | MS-B9181                    | [fef890b931](https://linux-hardware.org/?probe=fef890b931) | Jul 02, 2023 |
| MSI           | MS-B9181                    | [47b3ce0c58](https://linux-hardware.org/?probe=47b3ce0c58) | Jul 02, 2023 |
| MSI           | PRO Z690-A WIFI             | [2bc4b36c94](https://linux-hardware.org/?probe=2bc4b36c94) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | [c787bf91c3](https://linux-hardware.org/?probe=c787bf91c3) | Jul 02, 2023 |
| Win Elemen... | M9                          | [2e5ea821f1](https://linux-hardware.org/?probe=2e5ea821f1) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | [a4e29f77e5](https://linux-hardware.org/?probe=a4e29f77e5) | Jul 01, 2023 |
| MSI           | H61M-P31                    | [9012219f61](https://linux-hardware.org/?probe=9012219f61) | Jun 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | [bb1cb1ef13](https://linux-hardware.org/?probe=bb1cb1ef13) | Jun 29, 2023 |
| Gigabyte      | P31-DS3L                    | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | [0a35c3c750](https://linux-hardware.org/?probe=0a35c3c750) | Jun 27, 2023 |
| HP            | 8906 SMVB                   | [18ab778722](https://linux-hardware.org/?probe=18ab778722) | Jun 26, 2023 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [85eeeb037b](https://linux-hardware.org/?probe=85eeeb037b) | Jun 26, 2023 |
| Gigabyte      | G31M-ES2L                   | [be14b80f2c](https://linux-hardware.org/?probe=be14b80f2c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | [bd3b3228c6](https://linux-hardware.org/?probe=bd3b3228c6) | Jun 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [dac65b1c2c](https://linux-hardware.org/?probe=dac65b1c2c) | Jun 24, 2023 |
| Dell          | 00V62H A01                  | [23134d6c71](https://linux-hardware.org/?probe=23134d6c71) | Jun 24, 2023 |
| ASUSTek       | P5B                         | [a62968d622](https://linux-hardware.org/?probe=a62968d622) | Jun 24, 2023 |
| ASUSTek       | F2A85-V PRO                 | [011552703c](https://linux-hardware.org/?probe=011552703c) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | [1dd704fab9](https://linux-hardware.org/?probe=1dd704fab9) | Jun 22, 2023 |
| Dell          | 0G9322                      | [a742a26282](https://linux-hardware.org/?probe=a742a26282) | Jun 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [1e11366a3e](https://linux-hardware.org/?probe=1e11366a3e) | Jun 21, 2023 |
| Intel         | D34010WYK H14771-304        | [0d3af8114b](https://linux-hardware.org/?probe=0d3af8114b) | Jun 20, 2023 |
| AZW           | GTR V02                     | [f9bee18426](https://linux-hardware.org/?probe=f9bee18426) | Jun 19, 2023 |
| ASUSTek       | P5LD2                       | [7038963b77](https://linux-hardware.org/?probe=7038963b77) | Jun 18, 2023 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [707e7d9862](https://linux-hardware.org/?probe=707e7d9862) | Jun 17, 2023 |
| Pegatron      | BOWIE                       | [a2bbc6abd3](https://linux-hardware.org/?probe=a2bbc6abd3) | Jun 17, 2023 |
| ASRock        | B85M                        | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Dell          | 0KC9NP A01                  | [b00d413241](https://linux-hardware.org/?probe=b00d413241) | Jun 14, 2023 |
| Dell          | 0KC9NP A01                  | [1d487a1ed5](https://linux-hardware.org/?probe=1d487a1ed5) | Jun 14, 2023 |
| Dell          | 0WR7PY A02                  | [eab79964fb](https://linux-hardware.org/?probe=eab79964fb) | Jun 14, 2023 |
| Vorke         | V1 Plus                     | [a63988d437](https://linux-hardware.org/?probe=a63988d437) | Jun 14, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [c1992a1680](https://linux-hardware.org/?probe=c1992a1680) | Jun 13, 2023 |
| Pegatron      | BOWIE                       | [2794a5aa86](https://linux-hardware.org/?probe=2794a5aa86) | Jun 12, 2023 |
| ASUSTek       | P5B                         | [6308a1c633](https://linux-hardware.org/?probe=6308a1c633) | Jun 12, 2023 |
| Toshiba       | Mobile Intel 4 Series/IC... | [45696e1d1b](https://linux-hardware.org/?probe=45696e1d1b) | Jun 12, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [373e36422d](https://linux-hardware.org/?probe=373e36422d) | Jun 12, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | [9ea7188339](https://linux-hardware.org/?probe=9ea7188339) | Jun 11, 2023 |
| HP            | 8350                        | [8a40ff28c8](https://linux-hardware.org/?probe=8a40ff28c8) | Jun 11, 2023 |
| ASUSTek       | P5B                         | [794635cbea](https://linux-hardware.org/?probe=794635cbea) | Jun 10, 2023 |
| MP            | MS-7848                     | [cd63c98850](https://linux-hardware.org/?probe=cd63c98850) | Jun 10, 2023 |
| Nvidia        | MCP79                       | [8203509a77](https://linux-hardware.org/?probe=8203509a77) | Jun 09, 2023 |
| ASRock        | H81M-HDS                    | [e1ff6f4e2f](https://linux-hardware.org/?probe=e1ff6f4e2f) | Jun 08, 2023 |
| ASUSTek       | P5B                         | [32baec6c0f](https://linux-hardware.org/?probe=32baec6c0f) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | [74cf1d0b63](https://linux-hardware.org/?probe=74cf1d0b63) | Jun 08, 2023 |
| Shenzhen M... | F7BFD                       | [88cbeea389](https://linux-hardware.org/?probe=88cbeea389) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [20d28155d8](https://linux-hardware.org/?probe=20d28155d8) | Jun 08, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [517cbd7f48](https://linux-hardware.org/?probe=517cbd7f48) | Jun 08, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [2ad7aefc45](https://linux-hardware.org/?probe=2ad7aefc45) | Jun 07, 2023 |
| HP            | 8350                        | [113be26d4c](https://linux-hardware.org/?probe=113be26d4c) | Jun 07, 2023 |
| Dell          | 0G9322                      | [e81a7f788a](https://linux-hardware.org/?probe=e81a7f788a) | Jun 07, 2023 |
| Nvidia        | MCP79                       | [bf109ed28f](https://linux-hardware.org/?probe=bf109ed28f) | Jun 06, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [79f63dcf8e](https://linux-hardware.org/?probe=79f63dcf8e) | Jun 06, 2023 |
| ASUSTek       | CM1730,CM1830               | [2cc76d0cd9](https://linux-hardware.org/?probe=2cc76d0cd9) | Jun 05, 2023 |
| ASUSTek       | CM1730,CM1830               | [7dc46d923e](https://linux-hardware.org/?probe=7dc46d923e) | Jun 05, 2023 |
| ASUSTek       | P5Q                         | [85c6e06d3b](https://linux-hardware.org/?probe=85c6e06d3b) | Jun 05, 2023 |
| Dell          | 00010C A00                  | [fb12198605](https://linux-hardware.org/?probe=fb12198605) | Jun 05, 2023 |
| Dell          | 00010C A00                  | [d94442285c](https://linux-hardware.org/?probe=d94442285c) | Jun 05, 2023 |
| ASUSTek       | B75M-A                      | [55139a968d](https://linux-hardware.org/?probe=55139a968d) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | [413aba0d3f](https://linux-hardware.org/?probe=413aba0d3f) | Jun 04, 2023 |
| Dell          | 0G9322                      | [a1c5ec8909](https://linux-hardware.org/?probe=a1c5ec8909) | Jun 03, 2023 |
| Dell          | 0NW6H5 A00                  | [01387c3030](https://linux-hardware.org/?probe=01387c3030) | Jun 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [20260fb3b3](https://linux-hardware.org/?probe=20260fb3b3) | Jun 03, 2023 |
| HP            | 339A                        | [bb4619f4eb](https://linux-hardware.org/?probe=bb4619f4eb) | Jun 02, 2023 |
| Gateway       | SX2851                      | [262ddffda9](https://linux-hardware.org/?probe=262ddffda9) | Jun 02, 2023 |
| MSI           | H81M-E34                    | [26362cac22](https://linux-hardware.org/?probe=26362cac22) | Jun 02, 2023 |
| MSI           | H81M-E34                    | [9f04387a7c](https://linux-hardware.org/?probe=9f04387a7c) | Jun 01, 2023 |
| ASRock        | ALiveDual-eSATA2            | [0f490d3b39](https://linux-hardware.org/?probe=0f490d3b39) | Jun 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [abc4bba144](https://linux-hardware.org/?probe=abc4bba144) | Jun 01, 2023 |
| MSI           | 890FXA-GD70                 | [bcc4cd9597](https://linux-hardware.org/?probe=bcc4cd9597) | Jun 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | [923c9a18ff](https://linux-hardware.org/?probe=923c9a18ff) | Jun 01, 2023 |
| MSI           | B450 TOMAHAWK               | [0ddd2982db](https://linux-hardware.org/?probe=0ddd2982db) | May 31, 2023 |
| MSI           | B450 TOMAHAWK               | [93d1ee7e2d](https://linux-hardware.org/?probe=93d1ee7e2d) | May 31, 2023 |
| Acer          | Predator G3-605             | [f33c170be3](https://linux-hardware.org/?probe=f33c170be3) | May 27, 2023 |
| ASUSTek       | M2V-MX SE                   | [be58596103](https://linux-hardware.org/?probe=be58596103) | May 27, 2023 |
| ASUSTek       | M2V-MX SE                   | [0eedc4211a](https://linux-hardware.org/?probe=0eedc4211a) | May 27, 2023 |
| Dell          | 0G9322                      | [4d1450ba3a](https://linux-hardware.org/?probe=4d1450ba3a) | May 27, 2023 |
| Dell          | 0G9322                      | [d742ccb0c4](https://linux-hardware.org/?probe=d742ccb0c4) | May 27, 2023 |
| HP            | 21D0                        | [7f83859a91](https://linux-hardware.org/?probe=7f83859a91) | May 27, 2023 |
| MSI           | H97 GUARD-PRO               | [3737e6c832](https://linux-hardware.org/?probe=3737e6c832) | May 27, 2023 |
| HP            | 18E5                        | [23e2edb1fe](https://linux-hardware.org/?probe=23e2edb1fe) | May 26, 2023 |
| Dell          | 0K095G A02                  | [f11b8418c9](https://linux-hardware.org/?probe=f11b8418c9) | May 26, 2023 |
| HP            | 21D0                        | [8e52c2613c](https://linux-hardware.org/?probe=8e52c2613c) | May 26, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [61dc4c5620](https://linux-hardware.org/?probe=61dc4c5620) | May 25, 2023 |
| ECS           | H510H6-M2                   | [eba710b3de](https://linux-hardware.org/?probe=eba710b3de) | May 24, 2023 |
| Vorke         | V1 Plus                     | [81c0b82d6c](https://linux-hardware.org/?probe=81c0b82d6c) | May 24, 2023 |
| ECS           | H510H6-M2                   | [b36784601b](https://linux-hardware.org/?probe=b36784601b) | May 24, 2023 |
| HP            | 8906 SMVB                   | [ca3ed99a5c](https://linux-hardware.org/?probe=ca3ed99a5c) | May 24, 2023 |
| Pegatron      | 2AC2A                       | [f9e504a430](https://linux-hardware.org/?probe=f9e504a430) | May 24, 2023 |
| HP            | 21EF                        | [f1d5c9381c](https://linux-hardware.org/?probe=f1d5c9381c) | May 23, 2023 |
| MSI           | H81M-E34                    | [4247f30888](https://linux-hardware.org/?probe=4247f30888) | May 23, 2023 |
| Unknown       | Unknown                     | [977cf42905](https://linux-hardware.org/?probe=977cf42905) | May 23, 2023 |
| HP            | 21EF                        | [3249975d27](https://linux-hardware.org/?probe=3249975d27) | May 22, 2023 |
| ASRock        | H77M                        | [7f173e0b75](https://linux-hardware.org/?probe=7f173e0b75) | May 22, 2023 |
| HP            | 18E5                        | [d1bc34770d](https://linux-hardware.org/?probe=d1bc34770d) | May 22, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [b6465d2950](https://linux-hardware.org/?probe=b6465d2950) | May 21, 2023 |
| Dell          | 02N3WF A01                  | [8d0096c040](https://linux-hardware.org/?probe=8d0096c040) | May 21, 2023 |
| Dell          | 0M5DCD A00                  | [4087cdd6cb](https://linux-hardware.org/?probe=4087cdd6cb) | May 20, 2023 |
| Dell          | 0M5DCD A00                  | [8db744994d](https://linux-hardware.org/?probe=8db744994d) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [0bcd2c7244](https://linux-hardware.org/?probe=0bcd2c7244) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [c1594f6dab](https://linux-hardware.org/?probe=c1594f6dab) | May 20, 2023 |
| Gigabyte      | X570 GAMING X               | [8a6ad6c590](https://linux-hardware.org/?probe=8a6ad6c590) | May 19, 2023 |
| Dell          | 0GDG8Y A00                  | [514fe06c9e](https://linux-hardware.org/?probe=514fe06c9e) | May 19, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [31568d83f7](https://linux-hardware.org/?probe=31568d83f7) | May 18, 2023 |
| Gigabyte      | H81M-DS2                    | [754dc9d1fc](https://linux-hardware.org/?probe=754dc9d1fc) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | [ee37475637](https://linux-hardware.org/?probe=ee37475637) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | [68406e2c40](https://linux-hardware.org/?probe=68406e2c40) | May 18, 2023 |
| Acer          | Revo 70                     | [6cbc11e75b](https://linux-hardware.org/?probe=6cbc11e75b) | May 17, 2023 |
| HP            | 2B02                        | [a6bf09d51c](https://linux-hardware.org/?probe=a6bf09d51c) | May 17, 2023 |
| Pegatron      | Benicia                     | [e6ee1c66f6](https://linux-hardware.org/?probe=e6ee1c66f6) | May 17, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [d3c3cc9f96](https://linux-hardware.org/?probe=d3c3cc9f96) | May 15, 2023 |
| Intel         | Tiger Hill                  | [fdbe67045c](https://linux-hardware.org/?probe=fdbe67045c) | May 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [dd8c6c3811](https://linux-hardware.org/?probe=dd8c6c3811) | May 15, 2023 |
| HP            | 18E5                        | [7d5ceb9f5d](https://linux-hardware.org/?probe=7d5ceb9f5d) | May 15, 2023 |
| Gigabyte      | GA-970A-UD3                 | [24c81ddf59](https://linux-hardware.org/?probe=24c81ddf59) | May 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [38b6dd7b3f](https://linux-hardware.org/?probe=38b6dd7b3f) | May 14, 2023 |
| ASUSTek       | K8N-DRE                     | [395dc0cfb3](https://linux-hardware.org/?probe=395dc0cfb3) | May 13, 2023 |
| ASUSTek       | K8N-DRE                     | [f55a0c735f](https://linux-hardware.org/?probe=f55a0c735f) | May 13, 2023 |
| Vorke         | V1 Plus                     | [19f095fc02](https://linux-hardware.org/?probe=19f095fc02) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e844f3a6fe](https://linux-hardware.org/?probe=e844f3a6fe) | May 13, 2023 |
| Acer          | Predator G3-605             | [2d1485d58b](https://linux-hardware.org/?probe=2d1485d58b) | May 13, 2023 |
| Gigabyte      | A520M DS3H                  | [e053d0d304](https://linux-hardware.org/?probe=e053d0d304) | May 13, 2023 |
| Acer          | Predator G3-605             | [d3fc5ad399](https://linux-hardware.org/?probe=d3fc5ad399) | May 13, 2023 |
| Gigabyte      | GA-970A-UD3                 | [080f1c13d8](https://linux-hardware.org/?probe=080f1c13d8) | May 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [e2c57c80fc](https://linux-hardware.org/?probe=e2c57c80fc) | May 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d041d35517](https://linux-hardware.org/?probe=d041d35517) | May 12, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d3ab5dcb5d](https://linux-hardware.org/?probe=d3ab5dcb5d) | May 12, 2023 |
| Gigabyte      | H110M-H-CF                  | [89b8dfaad7](https://linux-hardware.org/?probe=89b8dfaad7) | May 12, 2023 |
| Gigabyte      | Z77-DS3H                    | [c86f346e1d](https://linux-hardware.org/?probe=c86f346e1d) | May 12, 2023 |
| 16280-BM-3... | BADWARE-335861024712484 ... | [8f3baa5ed5](https://linux-hardware.org/?probe=8f3baa5ed5) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [719d80a236](https://linux-hardware.org/?probe=719d80a236) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [b25b524237](https://linux-hardware.org/?probe=b25b524237) | May 10, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [22778449cc](https://linux-hardware.org/?probe=22778449cc) | May 10, 2023 |
| ASUSTek       | A55BM-E                     | [4b1cb4d8cf](https://linux-hardware.org/?probe=4b1cb4d8cf) | May 10, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [ffd84ff48e](https://linux-hardware.org/?probe=ffd84ff48e) | May 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [abf6d2bf1d](https://linux-hardware.org/?probe=abf6d2bf1d) | May 09, 2023 |
| ASRock        | H61M-DGS                    | [0b1518261e](https://linux-hardware.org/?probe=0b1518261e) | May 09, 2023 |
| ASUSTek       | H81I-PLUS                   | [93d7a459be](https://linux-hardware.org/?probe=93d7a459be) | May 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d45b33c736](https://linux-hardware.org/?probe=d45b33c736) | May 09, 2023 |
| ASRock        | H61M-DGS                    | [96cfd64792](https://linux-hardware.org/?probe=96cfd64792) | May 07, 2023 |
| HP            | 339A                        | [8b646a0fa1](https://linux-hardware.org/?probe=8b646a0fa1) | May 07, 2023 |
| HP            | 339A                        | [e23aaae239](https://linux-hardware.org/?probe=e23aaae239) | May 07, 2023 |
| Intel         | D946GZIS AAD66165-301       | [c350f5ed12](https://linux-hardware.org/?probe=c350f5ed12) | May 06, 2023 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | [288e495c16](https://linux-hardware.org/?probe=288e495c16) | May 06, 2023 |
| ASRockRack    | D1521D4I2                   | [136a9303c0](https://linux-hardware.org/?probe=136a9303c0) | May 06, 2023 |
| MSI           | MAG B550M BAZOOKA           | [7b0b45831c](https://linux-hardware.org/?probe=7b0b45831c) | May 06, 2023 |
| MSI           | X570-A PRO                  | [46894747b1](https://linux-hardware.org/?probe=46894747b1) | May 05, 2023 |
| MSI           | X570-A PRO                  | [2723e21a6e](https://linux-hardware.org/?probe=2723e21a6e) | May 05, 2023 |
| Gigabyte      | M68MT-S2                    | [d571b75547](https://linux-hardware.org/?probe=d571b75547) | May 05, 2023 |
| ASRock        | B550M-HDV                   | [408cbd96c0](https://linux-hardware.org/?probe=408cbd96c0) | May 04, 2023 |
| Unknown       | Unknown                     | [5b46ed614a](https://linux-hardware.org/?probe=5b46ed614a) | May 04, 2023 |
| ASUSTek       | P5N73-CM                    | [e64a3c2da5](https://linux-hardware.org/?probe=e64a3c2da5) | May 04, 2023 |
| Gigabyte      | Z590 VISION G               | [d37eb8bf49](https://linux-hardware.org/?probe=d37eb8bf49) | May 04, 2023 |
| ASRock        | H81M-HDS                    | [60e11bdf11](https://linux-hardware.org/?probe=60e11bdf11) | May 04, 2023 |
| Gigabyte      | MFLP5IP-00                  | [c9c14a6da2](https://linux-hardware.org/?probe=c9c14a6da2) | May 03, 2023 |
| Gigabyte      | P55A-UD3                    | [c338210639](https://linux-hardware.org/?probe=c338210639) | May 03, 2023 |
| Dell          | 09WH54 A00                  | [0afa4006cd](https://linux-hardware.org/?probe=0afa4006cd) | May 03, 2023 |
| ASUSTek       | PRIME X370-PRO              | [d3757c615f](https://linux-hardware.org/?probe=d3757c615f) | May 02, 2023 |
| Intel         | D946GZIS AAD66165-301       | [e61e22863f](https://linux-hardware.org/?probe=e61e22863f) | May 02, 2023 |
| ASRock        | G41M-GS                     | [0824a9c571](https://linux-hardware.org/?probe=0824a9c571) | May 01, 2023 |
| Intel         | H55                         | [04dd5e834e](https://linux-hardware.org/?probe=04dd5e834e) | May 01, 2023 |
| ASRock        | H61M-DGS                    | [f395109c45](https://linux-hardware.org/?probe=f395109c45) | May 01, 2023 |
| Dell          | 02YYK5 A01                  | [1a00a1321e](https://linux-hardware.org/?probe=1a00a1321e) | Apr 30, 2023 |
| MSI           | IONA                        | [966ec83038](https://linux-hardware.org/?probe=966ec83038) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | [946a95c594](https://linux-hardware.org/?probe=946a95c594) | Apr 30, 2023 |
| Foxconn       | G41S/G41S-K                 | [58cebf39d1](https://linux-hardware.org/?probe=58cebf39d1) | Apr 30, 2023 |
| Unknown       | Unknown                     | [4b0542737c](https://linux-hardware.org/?probe=4b0542737c) | Apr 29, 2023 |
| Dell          | 08NPPY A00                  | [25bc3aa225](https://linux-hardware.org/?probe=25bc3aa225) | Apr 29, 2023 |
| Unknown       | Unknown                     | [c4941a5c16](https://linux-hardware.org/?probe=c4941a5c16) | Apr 27, 2023 |
| Pegatron      | IPM41-D3                    | [faf8704eb3](https://linux-hardware.org/?probe=faf8704eb3) | Apr 26, 2023 |
| Intel         | D34010WYK H14771-304        | [4fbbe6e603](https://linux-hardware.org/?probe=4fbbe6e603) | Apr 26, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [07e9099105](https://linux-hardware.org/?probe=07e9099105) | Apr 26, 2023 |
| HP            | 1632                        | [0355cb4e69](https://linux-hardware.org/?probe=0355cb4e69) | Apr 25, 2023 |
| ASUSTek       | M5A97 R2.0                  | [4231d023e9](https://linux-hardware.org/?probe=4231d023e9) | Apr 25, 2023 |
| eMachines     | MCP61PM-GM                  | [ff00693839](https://linux-hardware.org/?probe=ff00693839) | Apr 25, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [9bab79728a](https://linux-hardware.org/?probe=9bab79728a) | Apr 24, 2023 |
| ASUSTek       | P5Q                         | [57e3cfa7dc](https://linux-hardware.org/?probe=57e3cfa7dc) | Apr 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [9d5ada0fc4](https://linux-hardware.org/?probe=9d5ada0fc4) | Apr 24, 2023 |
| ASRock        | H61M-DGS                    | [154380c27c](https://linux-hardware.org/?probe=154380c27c) | Apr 24, 2023 |
| Gigabyte      | B650M DS3H                  | [3d07651a47](https://linux-hardware.org/?probe=3d07651a47) | Apr 24, 2023 |
| Dell          | 03NVJ6 A01                  | [8db1376917](https://linux-hardware.org/?probe=8db1376917) | Apr 23, 2023 |
| Pegatron      | 2AB5                        | [5f771d8ee5](https://linux-hardware.org/?probe=5f771d8ee5) | Apr 23, 2023 |
| Unknown       | G41                         | [cbe978cc34](https://linux-hardware.org/?probe=cbe978cc34) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [25ee911879](https://linux-hardware.org/?probe=25ee911879) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [468824c4d9](https://linux-hardware.org/?probe=468824c4d9) | Apr 23, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | [a68d32d442](https://linux-hardware.org/?probe=a68d32d442) | Apr 23, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [0cd5599131](https://linux-hardware.org/?probe=0cd5599131) | Apr 22, 2023 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | [3c3719b07f](https://linux-hardware.org/?probe=3c3719b07f) | Apr 22, 2023 |
| Dell          | 0F373D A00                  | [206de0188d](https://linux-hardware.org/?probe=206de0188d) | Apr 22, 2023 |
| Dell          | 03NVJ6 A01                  | [e60b9070a6](https://linux-hardware.org/?probe=e60b9070a6) | Apr 22, 2023 |
| ASUSTek       | M5A78L LE                   | [b19724085f](https://linux-hardware.org/?probe=b19724085f) | Apr 21, 2023 |
| Gigabyte      | B650M DS3H                  | [de196a2cfa](https://linux-hardware.org/?probe=de196a2cfa) | Apr 21, 2023 |
| ASUSTek       | H110M-R                     | [d428839f7c](https://linux-hardware.org/?probe=d428839f7c) | Apr 20, 2023 |
| HP            | 2ADE                        | [1a3d108a58](https://linux-hardware.org/?probe=1a3d108a58) | Apr 20, 2023 |
| HP            | 8054                        | [0f2c12c877](https://linux-hardware.org/?probe=0f2c12c877) | Apr 20, 2023 |
| Lenovo        | SHARKBAY 31900058 STD or... | [1331c6ef06](https://linux-hardware.org/?probe=1331c6ef06) | Apr 19, 2023 |
| HP            | 8906 SMVB                   | [65eb0fa6be](https://linux-hardware.org/?probe=65eb0fa6be) | Apr 19, 2023 |
| Dell          | 0WMJ54 A01                  | [2a7fe6d74b](https://linux-hardware.org/?probe=2a7fe6d74b) | Apr 18, 2023 |
| Dell          | 0WMJ54 A01                  | [be92b53515](https://linux-hardware.org/?probe=be92b53515) | Apr 18, 2023 |
| ASL           | BayTrail JHS773             | [3a5977ad04](https://linux-hardware.org/?probe=3a5977ad04) | Apr 18, 2023 |
| Dell          | 0T656F A02                  | [0d291f14a1](https://linux-hardware.org/?probe=0d291f14a1) | Apr 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | [119560d8db](https://linux-hardware.org/?probe=119560d8db) | Apr 17, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [307e22b0d6](https://linux-hardware.org/?probe=307e22b0d6) | Apr 17, 2023 |
| MSI           | MEG X570 UNIFY              | [b2311e7cac](https://linux-hardware.org/?probe=b2311e7cac) | Apr 17, 2023 |
| ASUSTek       | PRIME Z370-A                | [b9d869fe6b](https://linux-hardware.org/?probe=b9d869fe6b) | Apr 16, 2023 |
| ASRock        | H61M-DGS                    | [506ba2605a](https://linux-hardware.org/?probe=506ba2605a) | Apr 15, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [c7568482a9](https://linux-hardware.org/?probe=c7568482a9) | Apr 15, 2023 |
| Intel         | H61                         | [81c7094e68](https://linux-hardware.org/?probe=81c7094e68) | Apr 15, 2023 |
| MSI           | B75MA-E33                   | [d50de3a52c](https://linux-hardware.org/?probe=d50de3a52c) | Apr 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [fcfa1ed488](https://linux-hardware.org/?probe=fcfa1ed488) | Apr 14, 2023 |
| Biostar       | TZ75B                       | [c6720e2db2](https://linux-hardware.org/?probe=c6720e2db2) | Apr 14, 2023 |
| Foxconn       | G31MVP FAB:1.0              | [41eac5ca2f](https://linux-hardware.org/?probe=41eac5ca2f) | Apr 14, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [e9c2f8d5ba](https://linux-hardware.org/?probe=e9c2f8d5ba) | Apr 14, 2023 |
| Intel         | H61                         | [8aeeb449f8](https://linux-hardware.org/?probe=8aeeb449f8) | Apr 14, 2023 |
| ASRock        | B550 Steel Legend           | [9da868694f](https://linux-hardware.org/?probe=9da868694f) | Apr 14, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [4267100894](https://linux-hardware.org/?probe=4267100894) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [5e9f89e556](https://linux-hardware.org/?probe=5e9f89e556) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | [d72e78c1b0](https://linux-hardware.org/?probe=d72e78c1b0) | Apr 13, 2023 |
| Gigabyte      | M68MT-S2                    | [ac4059b403](https://linux-hardware.org/?probe=ac4059b403) | Apr 13, 2023 |
| MSI           | B450M PRO-M2 MAX            | [6f7e9a6bb2](https://linux-hardware.org/?probe=6f7e9a6bb2) | Apr 13, 2023 |
| ASUSTek       | B85M-G                      | [27bfaf568a](https://linux-hardware.org/?probe=27bfaf568a) | Apr 12, 2023 |
| Gigabyte      | EX58-EXTREME                | [82a946e356](https://linux-hardware.org/?probe=82a946e356) | Apr 12, 2023 |
| ASUSTek       | P8H67-M PRO                 | [1627e0654a](https://linux-hardware.org/?probe=1627e0654a) | Apr 11, 2023 |
| ASUSTek       | P8H67-M PRO                 | [57aa7d103d](https://linux-hardware.org/?probe=57aa7d103d) | Apr 11, 2023 |
| ASUSTek       | P5K                         | [36bc294c5b](https://linux-hardware.org/?probe=36bc294c5b) | Apr 11, 2023 |
| MSI           | B75MA-E33                   | [27e5e2df0d](https://linux-hardware.org/?probe=27e5e2df0d) | Apr 06, 2023 |
| Dell          | 0GY6Y8 A01                  | [ecba971f16](https://linux-hardware.org/?probe=ecba971f16) | Apr 06, 2023 |
| ASUSTek       | H87-PRO                     | [085dc66a77](https://linux-hardware.org/?probe=085dc66a77) | Apr 05, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [68d14e873f](https://linux-hardware.org/?probe=68d14e873f) | Apr 05, 2023 |
| eMachines     | MCP61PM-GM                  | [dc35ec4564](https://linux-hardware.org/?probe=dc35ec4564) | Apr 04, 2023 |
| Gigabyte      | H410M S2 V3                 | [fdff0f112e](https://linux-hardware.org/?probe=fdff0f112e) | Apr 04, 2023 |
| Medion        | MS-7707                     | [c490d9dc74](https://linux-hardware.org/?probe=c490d9dc74) | Apr 04, 2023 |
| eMachines     | MCP61PM-GM                  | [59f9325843](https://linux-hardware.org/?probe=59f9325843) | Apr 03, 2023 |
| ASRock        | H61M-DGS                    | [e05fcde338](https://linux-hardware.org/?probe=e05fcde338) | Apr 03, 2023 |
| Acer          | Veriton X4610G              | [49b3c45306](https://linux-hardware.org/?probe=49b3c45306) | Apr 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [ea4626fdcc](https://linux-hardware.org/?probe=ea4626fdcc) | Apr 02, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [118effffda](https://linux-hardware.org/?probe=118effffda) | Apr 02, 2023 |
| Dell          | 0D883F A04                  | [5bdaaa0d23](https://linux-hardware.org/?probe=5bdaaa0d23) | Apr 02, 2023 |
| HOUTER        | IPMIP-GS                    | [4ef0c7aaaa](https://linux-hardware.org/?probe=4ef0c7aaaa) | Apr 02, 2023 |
| Pegatron      | 2ACF                        | [c015b7fd50](https://linux-hardware.org/?probe=c015b7fd50) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [1fb4c6ac6a](https://linux-hardware.org/?probe=1fb4c6ac6a) | Apr 01, 2023 |
| Acer          | Predator G3-605             | [eb21663788](https://linux-hardware.org/?probe=eb21663788) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [80bb5bbf28](https://linux-hardware.org/?probe=80bb5bbf28) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [1fa4ec7b05](https://linux-hardware.org/?probe=1fa4ec7b05) | Apr 01, 2023 |
| Medion        | H61H2-LM3                   | [2e79b95cb4](https://linux-hardware.org/?probe=2e79b95cb4) | Apr 01, 2023 |
| Dell          | 0K240Y A02                  | [ca6aacf14e](https://linux-hardware.org/?probe=ca6aacf14e) | Mar 31, 2023 |
| Dell          | 09M8Y8 A01                  | [2c13e40cd2](https://linux-hardware.org/?probe=2c13e40cd2) | Mar 30, 2023 |
| ASUSTek       | Benicia                     | [7332efabad](https://linux-hardware.org/?probe=7332efabad) | Mar 30, 2023 |
| HOUTER        | ORO-PC                      | [9547c4bdac](https://linux-hardware.org/?probe=9547c4bdac) | Mar 29, 2023 |
| Gigabyte      | H310M H x.x                 | [a927671ce2](https://linux-hardware.org/?probe=a927671ce2) | Mar 29, 2023 |
| MSI           | B560M-A PRO                 | [62bfea11fe](https://linux-hardware.org/?probe=62bfea11fe) | Mar 28, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [c97dbb0917](https://linux-hardware.org/?probe=c97dbb0917) | Mar 28, 2023 |
| Dell          | 06X1TJ A01                  | [7e99e3d73e](https://linux-hardware.org/?probe=7e99e3d73e) | Mar 28, 2023 |
| ASRock        | Z68 Pro3-M                  | [60f0809fbf](https://linux-hardware.org/?probe=60f0809fbf) | Mar 28, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [dcbcf69a04](https://linux-hardware.org/?probe=dcbcf69a04) | Mar 27, 2023 |
| Dell          | 0J8H4R A00                  | [63d85fd315](https://linux-hardware.org/?probe=63d85fd315) | Mar 27, 2023 |
| Lenovo        | 11061GG ThinkServer TS13... | [174e514c30](https://linux-hardware.org/?probe=174e514c30) | Mar 26, 2023 |
| Packard Be... | MCP73PV                     | [87d1fd7511](https://linux-hardware.org/?probe=87d1fd7511) | Mar 26, 2023 |
| Dell          | 0GU083 A00                  | [e577b0129c](https://linux-hardware.org/?probe=e577b0129c) | Mar 26, 2023 |
| ASRock        | H61M-DGS                    | [76fc7291a6](https://linux-hardware.org/?probe=76fc7291a6) | Mar 26, 2023 |
| AZW           | MINI S                      | [f3381963ae](https://linux-hardware.org/?probe=f3381963ae) | Mar 25, 2023 |
| ASRock        | AB350 Gaming K4             | [ecc09c1362](https://linux-hardware.org/?probe=ecc09c1362) | Mar 25, 2023 |
| Dell          | 0D28YY A01                  | [38b08369e7](https://linux-hardware.org/?probe=38b08369e7) | Mar 25, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [ce9cdcc598](https://linux-hardware.org/?probe=ce9cdcc598) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | [e859e77bc7](https://linux-hardware.org/?probe=e859e77bc7) | Mar 24, 2023 |
| Dell          | 0HD5W2 A01                  | [ce7e17cb45](https://linux-hardware.org/?probe=ce7e17cb45) | Mar 24, 2023 |
| ASRock        | X570 Steel Legend           | [05d4059f59](https://linux-hardware.org/?probe=05d4059f59) | Mar 24, 2023 |
| MSI           | B450M PRO-VDH MAX           | [c83000783a](https://linux-hardware.org/?probe=c83000783a) | Mar 23, 2023 |
| ASRock        | B550M-ITX/ac                | [e8ad290196](https://linux-hardware.org/?probe=e8ad290196) | Mar 23, 2023 |
| Intel         | G41                         | [c9fccfc8c1](https://linux-hardware.org/?probe=c9fccfc8c1) | Mar 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [d0b0015eb2](https://linux-hardware.org/?probe=d0b0015eb2) | Mar 22, 2023 |
| ASUSTek       | PRIME X370-PRO              | [9409e4e133](https://linux-hardware.org/?probe=9409e4e133) | Mar 20, 2023 |
| Acer          | Revo RL80                   | [23ee51b834](https://linux-hardware.org/?probe=23ee51b834) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | [93ae4afbbc](https://linux-hardware.org/?probe=93ae4afbbc) | Mar 20, 2023 |
| MSI           | B75MA-E33                   | [cddf0b016f](https://linux-hardware.org/?probe=cddf0b016f) | Mar 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | [75996f8bcf](https://linux-hardware.org/?probe=75996f8bcf) | Mar 19, 2023 |
| HP            | 158A                        | [61467de4d5](https://linux-hardware.org/?probe=61467de4d5) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | [2b86166550](https://linux-hardware.org/?probe=2b86166550) | Mar 19, 2023 |
| ASUSTek       | PRIME A320M-K               | [f0f20a06ef](https://linux-hardware.org/?probe=f0f20a06ef) | Mar 19, 2023 |
| HP            | 2B01                        | [1a096f9b36](https://linux-hardware.org/?probe=1a096f9b36) | Mar 19, 2023 |
| MSI           | B75MA-E33                   | [314245636a](https://linux-hardware.org/?probe=314245636a) | Mar 18, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | [5f4a932bcd](https://linux-hardware.org/?probe=5f4a932bcd) | Mar 18, 2023 |
| HP            | 83E1                        | [2a1ade4f84](https://linux-hardware.org/?probe=2a1ade4f84) | Mar 17, 2023 |
| Dell          | 0D28YY A01                  | [76b31023a4](https://linux-hardware.org/?probe=76b31023a4) | Mar 17, 2023 |
| HP            | 158A                        | [4a023a55d8](https://linux-hardware.org/?probe=4a023a55d8) | Mar 16, 2023 |
| Lenovo        | SHARKBAY NOK                | [3388dd991a](https://linux-hardware.org/?probe=3388dd991a) | Mar 15, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | [eb761f4a30](https://linux-hardware.org/?probe=eb761f4a30) | Mar 14, 2023 |
| Gigabyte      | H110M-H-CF                  | [cc372ccf7d](https://linux-hardware.org/?probe=cc372ccf7d) | Mar 14, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [0f440670f2](https://linux-hardware.org/?probe=0f440670f2) | Mar 14, 2023 |
| Gigabyte      | H55M-S2H                    | [55d6288663](https://linux-hardware.org/?probe=55d6288663) | Mar 14, 2023 |
| HP            | 83E1                        | [d286798430](https://linux-hardware.org/?probe=d286798430) | Mar 13, 2023 |
| Soncview      | G41D3C                      | [877ff67a70](https://linux-hardware.org/?probe=877ff67a70) | Mar 13, 2023 |
| Gigabyte      | H97M-D3H                    | [178af6e35b](https://linux-hardware.org/?probe=178af6e35b) | Mar 12, 2023 |
| HP            | 18E7                        | [2042edf904](https://linux-hardware.org/?probe=2042edf904) | Mar 12, 2023 |
| HP            | 09CCh                       | [e122b11e42](https://linux-hardware.org/?probe=e122b11e42) | Mar 12, 2023 |
| Dell          | 0GM819                      | [1db4004d05](https://linux-hardware.org/?probe=1db4004d05) | Mar 12, 2023 |
| Medion        | MS-7707                     | [a0621e0cd1](https://linux-hardware.org/?probe=a0621e0cd1) | Mar 12, 2023 |
| Gigabyte      | EX58-EXTREME                | [f45a0d4c01](https://linux-hardware.org/?probe=f45a0d4c01) | Mar 12, 2023 |
| Medion        | MS-7707                     | [4c9432026b](https://linux-hardware.org/?probe=4c9432026b) | Mar 12, 2023 |
| Gigabyte      | H110M-H-CF                  | [91da2169aa](https://linux-hardware.org/?probe=91da2169aa) | Mar 12, 2023 |
| Gigabyte      | X670E AORUS XTREME          | [83cb566647](https://linux-hardware.org/?probe=83cb566647) | Mar 12, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [bd0c265909](https://linux-hardware.org/?probe=bd0c265909) | Mar 11, 2023 |
| Intel         | H61                         | [5650f6d211](https://linux-hardware.org/?probe=5650f6d211) | Mar 11, 2023 |
| Acer          | WG43M                       | [5858448536](https://linux-hardware.org/?probe=5858448536) | Mar 11, 2023 |
| Acer          | WG43M                       | [3d562885d0](https://linux-hardware.org/?probe=3d562885d0) | Mar 11, 2023 |
| HP            | 09CCh                       | [9421be2c59](https://linux-hardware.org/?probe=9421be2c59) | Mar 11, 2023 |
| Dell          | 0T10XW A00                  | [a47baaadde](https://linux-hardware.org/?probe=a47baaadde) | Mar 11, 2023 |
| ASUSTek       | H110M-R                     | [434a8e0e37](https://linux-hardware.org/?probe=434a8e0e37) | Mar 10, 2023 |
| Pegatron      | 2ACB                        | [1599d2a2ef](https://linux-hardware.org/?probe=1599d2a2ef) | Mar 09, 2023 |
| Unknown       | HX90                        | [21530c00a4](https://linux-hardware.org/?probe=21530c00a4) | Mar 09, 2023 |
| Gigabyte      | Z370 HD3P-CF                | [8115c702cb](https://linux-hardware.org/?probe=8115c702cb) | Mar 09, 2023 |
| MSI           | B450 GAMING PLUS            | [5fd5c7db62](https://linux-hardware.org/?probe=5fd5c7db62) | Mar 09, 2023 |
| Dell          | 0T10XW A00                  | [fd255666fc](https://linux-hardware.org/?probe=fd255666fc) | Mar 08, 2023 |
| Gigabyte      | B450 GAMING X               | [6f7b473b62](https://linux-hardware.org/?probe=6f7b473b62) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [5f93500136](https://linux-hardware.org/?probe=5f93500136) | Mar 08, 2023 |
| ASRock        | B450M Pro4-F                | [fdba382132](https://linux-hardware.org/?probe=fdba382132) | Mar 08, 2023 |
| Gigabyte      | A320M-S2H-CF                | [00ddbf4ad1](https://linux-hardware.org/?probe=00ddbf4ad1) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | [10c9c37ebc](https://linux-hardware.org/?probe=10c9c37ebc) | Mar 07, 2023 |
| ASUSTek       | P5GC-MX                     | [c7ccf3de7b](https://linux-hardware.org/?probe=c7ccf3de7b) | Mar 07, 2023 |
| ASUSTek       | H97M-PLUS                   | [aa987a6626](https://linux-hardware.org/?probe=aa987a6626) | Mar 07, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [83c569f727](https://linux-hardware.org/?probe=83c569f727) | Mar 06, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [ca3531a813](https://linux-hardware.org/?probe=ca3531a813) | Mar 06, 2023 |
| Dell          | 0JC474                      | [90db9efd8d](https://linux-hardware.org/?probe=90db9efd8d) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [7c9b56f288](https://linux-hardware.org/?probe=7c9b56f288) | Mar 05, 2023 |
| Gigabyte      | B450M DS3H V2               | [d1a55c59a3](https://linux-hardware.org/?probe=d1a55c59a3) | Mar 05, 2023 |
| Apple         | Mac-F221BEC8                | [f3c06b377f](https://linux-hardware.org/?probe=f3c06b377f) | Mar 04, 2023 |
| ASUSTek       | H81M-K                      | [05507dab01](https://linux-hardware.org/?probe=05507dab01) | Mar 04, 2023 |
| ASUSTek       | PRIME H410M-R               | [240adbe154](https://linux-hardware.org/?probe=240adbe154) | Mar 04, 2023 |
| Gigabyte      | B460M AORUS PRO             | [829848b662](https://linux-hardware.org/?probe=829848b662) | Mar 04, 2023 |
| ASRock        | Wolfdale1333-D667           | [7dd4939e64](https://linux-hardware.org/?probe=7dd4939e64) | Mar 03, 2023 |
| Unknown       | Rev.00                      | [89ff2d84f4](https://linux-hardware.org/?probe=89ff2d84f4) | Mar 03, 2023 |
| ASUSTek       | P7H55-M LX                  | [80e66c5eac](https://linux-hardware.org/?probe=80e66c5eac) | Mar 03, 2023 |
| ASUSTek       | P5QPL-AM                    | [52b68672fc](https://linux-hardware.org/?probe=52b68672fc) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [1e039a31d1](https://linux-hardware.org/?probe=1e039a31d1) | Mar 03, 2023 |
| HP            | 805D                        | [4638c85566](https://linux-hardware.org/?probe=4638c85566) | Mar 01, 2023 |
| ASUSTek       | SABERTOOTH P67              | [fa7df5da3b](https://linux-hardware.org/?probe=fa7df5da3b) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [ca7d449be6](https://linux-hardware.org/?probe=ca7d449be6) | Feb 28, 2023 |
| Lenovo        | SKYBAY SDK0J40697 WIN 33... | [75e0fb99ed](https://linux-hardware.org/?probe=75e0fb99ed) | Feb 28, 2023 |
| Google        | Buddy                       | [ac3d9aaed0](https://linux-hardware.org/?probe=ac3d9aaed0) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | [7f907fadb7](https://linux-hardware.org/?probe=7f907fadb7) | Feb 27, 2023 |
| Dell          | 0WMJ54 A01                  | [766991da5e](https://linux-hardware.org/?probe=766991da5e) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | [6c62bbbf3b](https://linux-hardware.org/?probe=6c62bbbf3b) | Feb 27, 2023 |
| Dell          | 0Y2MRG A00                  | [2479c3c245](https://linux-hardware.org/?probe=2479c3c245) | Feb 27, 2023 |
| HP            | 1998                        | [90794415e9](https://linux-hardware.org/?probe=90794415e9) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [a21ea9613b](https://linux-hardware.org/?probe=a21ea9613b) | Feb 26, 2023 |
| MSI           | B75MA-E33                   | [57a009cdd4](https://linux-hardware.org/?probe=57a009cdd4) | Feb 25, 2023 |
| MSI           | B75MA-E33                   | [fc1a3d88ae](https://linux-hardware.org/?probe=fc1a3d88ae) | Feb 25, 2023 |
| MSI           | H81M-P33                    | [1bc1cedec6](https://linux-hardware.org/?probe=1bc1cedec6) | Feb 25, 2023 |
| ASUSTek       | PRIME B560M-A               | [7357439273](https://linux-hardware.org/?probe=7357439273) | Feb 25, 2023 |
| HP            | 2AF7                        | [a8eba0b0c4](https://linux-hardware.org/?probe=a8eba0b0c4) | Feb 25, 2023 |
| HP            | 2AF7                        | [3bf3afd1d5](https://linux-hardware.org/?probe=3bf3afd1d5) | Feb 25, 2023 |
| HP            | 2129                        | [5118eb06d4](https://linux-hardware.org/?probe=5118eb06d4) | Feb 24, 2023 |
| Dell          | 0HN7XN A01                  | [f283ae7cb2](https://linux-hardware.org/?probe=f283ae7cb2) | Feb 23, 2023 |
| ASUSTek       | P7H55-M/USB3                | [472721d72c](https://linux-hardware.org/?probe=472721d72c) | Feb 22, 2023 |
| HP            | 2129                        | [5a6b1e7169](https://linux-hardware.org/?probe=5a6b1e7169) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [e861797e74](https://linux-hardware.org/?probe=e861797e74) | Feb 21, 2023 |
| ASUSTek       | F2A55-M                     | [c9d150f24c](https://linux-hardware.org/?probe=c9d150f24c) | Feb 21, 2023 |
| ASUSTek       | SABERTOOTH Z87              | [40e2157901](https://linux-hardware.org/?probe=40e2157901) | Feb 21, 2023 |
| HP            | 1850                        | [f184ff6250](https://linux-hardware.org/?probe=f184ff6250) | Feb 21, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [e062475561](https://linux-hardware.org/?probe=e062475561) | Feb 20, 2023 |
| eMachines     | MCP61PM-GM                  | [aeafa2dbee](https://linux-hardware.org/?probe=aeafa2dbee) | Feb 19, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | [5d6240bcc6](https://linux-hardware.org/?probe=5d6240bcc6) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [09aad96389](https://linux-hardware.org/?probe=09aad96389) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | [be0f73193d](https://linux-hardware.org/?probe=be0f73193d) | Feb 19, 2023 |
| Gigabyte      | H97M-D3H                    | [c784a261d4](https://linux-hardware.org/?probe=c784a261d4) | Feb 19, 2023 |
| Gigabyte      | H81M-S2H                    | [d6f4d9d8df](https://linux-hardware.org/?probe=d6f4d9d8df) | Feb 19, 2023 |
| HOUTER        | ORO-PC                      | [af7ffdc7a9](https://linux-hardware.org/?probe=af7ffdc7a9) | Feb 18, 2023 |
| ASUSTek       | P5KC                        | [b2a9f21210](https://linux-hardware.org/?probe=b2a9f21210) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [6cc82a744e](https://linux-hardware.org/?probe=6cc82a744e) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [96c9f07207](https://linux-hardware.org/?probe=96c9f07207) | Feb 18, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [2734c1a2ae](https://linux-hardware.org/?probe=2734c1a2ae) | Feb 18, 2023 |
| MSI           | H270 PC MATE                | [6581748d54](https://linux-hardware.org/?probe=6581748d54) | Feb 17, 2023 |
| MSI           | 760GM-P23                   | [529e0929d2](https://linux-hardware.org/?probe=529e0929d2) | Feb 17, 2023 |
| Gigabyte      | 990FXA-UD3                  | [97e017594b](https://linux-hardware.org/?probe=97e017594b) | Feb 16, 2023 |
| Gigabyte      | 990FXA-UD3                  | [51b7c93a69](https://linux-hardware.org/?probe=51b7c93a69) | Feb 16, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [4275665066](https://linux-hardware.org/?probe=4275665066) | Feb 16, 2023 |
| MSI           | Z370M MORTAR                | [5ac9c9a924](https://linux-hardware.org/?probe=5ac9c9a924) | Feb 15, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [995da369f0](https://linux-hardware.org/?probe=995da369f0) | Feb 14, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | [b6b09f6455](https://linux-hardware.org/?probe=b6b09f6455) | Feb 14, 2023 |
| Gigabyte      | 945GZM-S2                   | [e271dc0c66](https://linux-hardware.org/?probe=e271dc0c66) | Feb 14, 2023 |
| Gigabyte      | B450M DS3H V2               | [92fc220243](https://linux-hardware.org/?probe=92fc220243) | Feb 14, 2023 |
| Google        | Teemo                       | [53bf6d19ca](https://linux-hardware.org/?probe=53bf6d19ca) | Feb 14, 2023 |
| MSI           | MS-B9181                    | [a155bc9fc3](https://linux-hardware.org/?probe=a155bc9fc3) | Feb 13, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [1e3c885566](https://linux-hardware.org/?probe=1e3c885566) | Feb 13, 2023 |
| Dell          | 0Y7WYT A00                  | [e289b5bb8d](https://linux-hardware.org/?probe=e289b5bb8d) | Feb 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | [5efd07985b](https://linux-hardware.org/?probe=5efd07985b) | Feb 13, 2023 |
| Alienware     | 0N43JM A00                  | [ef1d9239ab](https://linux-hardware.org/?probe=ef1d9239ab) | Feb 12, 2023 |
| Lenovo        | ThinkServer TS140           | [59eeaafe59](https://linux-hardware.org/?probe=59eeaafe59) | Feb 12, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [45f78c29cb](https://linux-hardware.org/?probe=45f78c29cb) | Feb 12, 2023 |
| Gigabyte      | B560 HD3                    | [498c449a46](https://linux-hardware.org/?probe=498c449a46) | Feb 12, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [43e0c40499](https://linux-hardware.org/?probe=43e0c40499) | Feb 11, 2023 |
| Unknown       | Unknown                     | [ce78e6cdb9](https://linux-hardware.org/?probe=ce78e6cdb9) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | [a789235fe3](https://linux-hardware.org/?probe=a789235fe3) | Feb 11, 2023 |
| HP            | 8054                        | [55c5642509](https://linux-hardware.org/?probe=55c5642509) | Feb 11, 2023 |
| Gigabyte      | H81M-S2H                    | [f3919f8d69](https://linux-hardware.org/?probe=f3919f8d69) | Feb 11, 2023 |
| IBM           | 819046G                     | [a43370bbbd](https://linux-hardware.org/?probe=a43370bbbd) | Feb 11, 2023 |
| Unknown       | Unknown                     | [f5e5e27e8e](https://linux-hardware.org/?probe=f5e5e27e8e) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [7a6b34f58c](https://linux-hardware.org/?probe=7a6b34f58c) | Feb 11, 2023 |
| HP            | 8643 SMVB                   | [5e8a88b237](https://linux-hardware.org/?probe=5e8a88b237) | Feb 11, 2023 |
| ASUSTek       | P5K                         | [9f8790812d](https://linux-hardware.org/?probe=9f8790812d) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [6d9d60d4b8](https://linux-hardware.org/?probe=6d9d60d4b8) | Feb 10, 2023 |
| Unknown       | Unknown                     | [cb0a834e1a](https://linux-hardware.org/?probe=cb0a834e1a) | Feb 10, 2023 |
| MSI           | GF615M-P31                  | [36dcd2e516](https://linux-hardware.org/?probe=36dcd2e516) | Feb 10, 2023 |
| Gigabyte      | X570 GAMING X               | [458744c54d](https://linux-hardware.org/?probe=458744c54d) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | [628151aedd](https://linux-hardware.org/?probe=628151aedd) | Feb 09, 2023 |
| Gigabyte      | X570 GAMING X               | [dd9b71e8d2](https://linux-hardware.org/?probe=dd9b71e8d2) | Feb 09, 2023 |
| Gigabyte      | B660 DS3H AX DDR4           | [73ae27760d](https://linux-hardware.org/?probe=73ae27760d) | Feb 09, 2023 |
| ASUSTek       | PRIME B550M-A               | [dd76c764a1](https://linux-hardware.org/?probe=dd76c764a1) | Feb 08, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [37aec8a881](https://linux-hardware.org/?probe=37aec8a881) | Feb 08, 2023 |
| Gigabyte      | GA-MA74GM-S2H               | [e7ee51ecdd](https://linux-hardware.org/?probe=e7ee51ecdd) | Feb 08, 2023 |
| ASUSTek       | SABERTOOTH P67              | [1fdf18a3ed](https://linux-hardware.org/?probe=1fdf18a3ed) | Feb 08, 2023 |
| Foxconn       | NT-A2400&NT-A3500 FAB       | [000ed6c589](https://linux-hardware.org/?probe=000ed6c589) | Feb 07, 2023 |
| Intel         | CRESCENTBAY                 | [1830edf54c](https://linux-hardware.org/?probe=1830edf54c) | Feb 07, 2023 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | [96f24866e0](https://linux-hardware.org/?probe=96f24866e0) | Feb 06, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [05b252ac05](https://linux-hardware.org/?probe=05b252ac05) | Feb 05, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | [0de7e3b318](https://linux-hardware.org/?probe=0de7e3b318) | Feb 05, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | [e61bc21eaf](https://linux-hardware.org/?probe=e61bc21eaf) | Feb 05, 2023 |
| HP            | 2B47                        | [3db96ac186](https://linux-hardware.org/?probe=3db96ac186) | Feb 04, 2023 |
| Dell          | 0HN7XN A01                  | [0399613500](https://linux-hardware.org/?probe=0399613500) | Feb 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e5a1cf7284](https://linux-hardware.org/?probe=e5a1cf7284) | Feb 03, 2023 |
| MSI           | B85M-E45                    | [13453f924e](https://linux-hardware.org/?probe=13453f924e) | Feb 03, 2023 |
| Intel         | X58                         | [55a6a5bd82](https://linux-hardware.org/?probe=55a6a5bd82) | Feb 03, 2023 |
| Unknown       | G41 Series                  | [69d4cb64a2](https://linux-hardware.org/?probe=69d4cb64a2) | Feb 03, 2023 |
| HP            | 1825                        | [fd942fd3ba](https://linux-hardware.org/?probe=fd942fd3ba) | Feb 02, 2023 |
| HP            | 09F8h                       | [19339c9512](https://linux-hardware.org/?probe=19339c9512) | Feb 02, 2023 |
| Dell          | 0D28YY A01                  | [51b04e5d58](https://linux-hardware.org/?probe=51b04e5d58) | Feb 01, 2023 |
| ASRock        | H87 Pro4                    | [8a53501060](https://linux-hardware.org/?probe=8a53501060) | Jan 31, 2023 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | [2c021665e1](https://linux-hardware.org/?probe=2c021665e1) | Jan 31, 2023 |
| MSI           | H81M-P33                    | [63402c414d](https://linux-hardware.org/?probe=63402c414d) | Jan 30, 2023 |
| HP            | 1791                        | [0cb5402c68](https://linux-hardware.org/?probe=0cb5402c68) | Jan 29, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [bc4b6513bb](https://linux-hardware.org/?probe=bc4b6513bb) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | [0da956ecde](https://linux-hardware.org/?probe=0da956ecde) | Jan 28, 2023 |
| MSI           | 760GM-P23                   | [e00bd18cc2](https://linux-hardware.org/?probe=e00bd18cc2) | Jan 28, 2023 |
| HP            | 843F                        | [5e9a5d2afd](https://linux-hardware.org/?probe=5e9a5d2afd) | Jan 28, 2023 |
| MSI           | PRO H610M-G DDR4            | [ad4f37d5a4](https://linux-hardware.org/?probe=ad4f37d5a4) | Jan 28, 2023 |
| HP            | 2B47                        | [cce5f9ec07](https://linux-hardware.org/?probe=cce5f9ec07) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e7b74c9ad4](https://linux-hardware.org/?probe=e7b74c9ad4) | Jan 27, 2023 |
| ASRock        | H61M-DGS                    | [825e70e660](https://linux-hardware.org/?probe=825e70e660) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| ASRock        | H87 Pro4                    | [c1427c9b7b](https://linux-hardware.org/?probe=c1427c9b7b) | Jan 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [951bfcd626](https://linux-hardware.org/?probe=951bfcd626) | Jan 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [c216d513a0](https://linux-hardware.org/?probe=c216d513a0) | Jan 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [06b972165b](https://linux-hardware.org/?probe=06b972165b) | Jan 25, 2023 |
| ASRock        | H61M-DGS                    | [5672937ec6](https://linux-hardware.org/?probe=5672937ec6) | Jan 25, 2023 |
| HP            | 2ADE                        | [b927cb3f98](https://linux-hardware.org/?probe=b927cb3f98) | Jan 24, 2023 |
| Acer          | RS880M05                    | [c7e3fe60e1](https://linux-hardware.org/?probe=c7e3fe60e1) | Jan 23, 2023 |
| ASRock        | H61M                        | [f5b1db73f7](https://linux-hardware.org/?probe=f5b1db73f7) | Jan 22, 2023 |
| ASUSTek       | P5Q                         | [9e3b6b7075](https://linux-hardware.org/?probe=9e3b6b7075) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [90ad82dcac](https://linux-hardware.org/?probe=90ad82dcac) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [9579ec96bc](https://linux-hardware.org/?probe=9579ec96bc) | Jan 21, 2023 |
| HP            | 89B5 A                      | [1b6e288840](https://linux-hardware.org/?probe=1b6e288840) | Jan 21, 2023 |
| HP            | 843F                        | [07f6efa703](https://linux-hardware.org/?probe=07f6efa703) | Jan 20, 2023 |
| ASUSTek       | M4A3000E                    | [650236c7cc](https://linux-hardware.org/?probe=650236c7cc) | Jan 19, 2023 |
| ASRock        | B450 Pro4                   | [8131194ea1](https://linux-hardware.org/?probe=8131194ea1) | Jan 19, 2023 |
| ASUSTek       | P7P55D-E                    | [6bc203c6fd](https://linux-hardware.org/?probe=6bc203c6fd) | Jan 19, 2023 |
| HP            | 843F                        | [83ca70ac2d](https://linux-hardware.org/?probe=83ca70ac2d) | Jan 19, 2023 |
| Dell          | 0D28YY A01                  | [82b540a137](https://linux-hardware.org/?probe=82b540a137) | Jan 19, 2023 |
| ASUSTek       | M4A3000E                    | [4f8a71f0c5](https://linux-hardware.org/?probe=4f8a71f0c5) | Jan 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [dfac4d4f79](https://linux-hardware.org/?probe=dfac4d4f79) | Jan 17, 2023 |
| HP            | 3397                        | [a58c9ac196](https://linux-hardware.org/?probe=a58c9ac196) | Jan 17, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [69b469a6fb](https://linux-hardware.org/?probe=69b469a6fb) | Jan 16, 2023 |
| Gigabyte      | EX58-EXTREME                | [bb62149054](https://linux-hardware.org/?probe=bb62149054) | Jan 16, 2023 |
| Medion        | MS-7707                     | [9665ceabf1](https://linux-hardware.org/?probe=9665ceabf1) | Jan 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [3677d8f4e7](https://linux-hardware.org/?probe=3677d8f4e7) | Jan 15, 2023 |
| Gigabyte      | M68MT-S2                    | [a728c46633](https://linux-hardware.org/?probe=a728c46633) | Jan 15, 2023 |
| Unknown       | Unknown                     | [a69d4b7b4f](https://linux-hardware.org/?probe=a69d4b7b4f) | Jan 15, 2023 |
| Alienware     | 2                           | [97c74c0c7b](https://linux-hardware.org/?probe=97c74c0c7b) | Jan 15, 2023 |
| Dell          | 0F0TGN A00                  | [38a44bb08b](https://linux-hardware.org/?probe=38a44bb08b) | Jan 14, 2023 |
| HP            | 18E7                        | [3acf05bf4e](https://linux-hardware.org/?probe=3acf05bf4e) | Jan 14, 2023 |
| Unknown       | Unknown                     | [9cb802849a](https://linux-hardware.org/?probe=9cb802849a) | Jan 14, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | [e00028a10c](https://linux-hardware.org/?probe=e00028a10c) | Jan 14, 2023 |
| HC            | HCAR357-MI V1.0             | [b5f80f8eac](https://linux-hardware.org/?probe=b5f80f8eac) | Jan 14, 2023 |
| HP            | 0B4Ch D                     | [c5edc9fbc7](https://linux-hardware.org/?probe=c5edc9fbc7) | Jan 14, 2023 |
| Dell          | 0F0TGN A00                  | [dc548d070e](https://linux-hardware.org/?probe=dc548d070e) | Jan 13, 2023 |
| HP            | 3397                        | [baae324548](https://linux-hardware.org/?probe=baae324548) | Jan 13, 2023 |
| Acer          | FRS690L                     | [5b27fe10aa](https://linux-hardware.org/?probe=5b27fe10aa) | Jan 13, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [07cedbf55a](https://linux-hardware.org/?probe=07cedbf55a) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | [1706cf55cf](https://linux-hardware.org/?probe=1706cf55cf) | Jan 12, 2023 |
| ASUSTek       | H87-PRO                     | [4ac36f25a9](https://linux-hardware.org/?probe=4ac36f25a9) | Jan 11, 2023 |
| HP            | 843B                        | [ac14cee88f](https://linux-hardware.org/?probe=ac14cee88f) | Jan 10, 2023 |
| HP            | 843B                        | [e45a20a47f](https://linux-hardware.org/?probe=e45a20a47f) | Jan 10, 2023 |
| ASUSTek       | M4A88T-M                    | [4c3d063774](https://linux-hardware.org/?probe=4c3d063774) | Jan 09, 2023 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [abc1a27105](https://linux-hardware.org/?probe=abc1a27105) | Jan 08, 2023 |
| HP            | 2129                        | [4d6113e60d](https://linux-hardware.org/?probe=4d6113e60d) | Jan 08, 2023 |
| ASRock        | X670E PG Lightning          | [2b3261504f](https://linux-hardware.org/?probe=2b3261504f) | Jan 08, 2023 |
| MAXSUN        | MS-TZZ A320M.2-VH           | [f3e00dc862](https://linux-hardware.org/?probe=f3e00dc862) | Jan 07, 2023 |
| Standard      | X50-V2                      | [69b7593670](https://linux-hardware.org/?probe=69b7593670) | Jan 07, 2023 |
| HP            | 2B47                        | [8ad8cb5e8f](https://linux-hardware.org/?probe=8ad8cb5e8f) | Jan 06, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | [2df76bde47](https://linux-hardware.org/?probe=2df76bde47) | Jan 06, 2023 |
| Dell          | 0HN7XN A01                  | [e597f176c2](https://linux-hardware.org/?probe=e597f176c2) | Jan 03, 2023 |
| Dell          | 018D1Y A00                  | [9ba9bcee90](https://linux-hardware.org/?probe=9ba9bcee90) | Jan 03, 2023 |
| Foxconn       | H67S/H61SP                  | [c7684d1f93](https://linux-hardware.org/?probe=c7684d1f93) | Jan 03, 2023 |
| HP            | 8350                        | [3ab0d55a41](https://linux-hardware.org/?probe=3ab0d55a41) | Jan 02, 2023 |
| ASUSTek       | D300TA                      | [f522fa7b4d](https://linux-hardware.org/?probe=f522fa7b4d) | Jan 02, 2023 |
| ASUSTek       | H87-PRO                     | [f95906c714](https://linux-hardware.org/?probe=f95906c714) | Jan 01, 2023 |
| Dell          | 0T10XW A00                  | [21638e1dfe](https://linux-hardware.org/?probe=21638e1dfe) | Dec 31, 2022 |
| Gigabyte      | G31M-S2C                    | [39f08657f8](https://linux-hardware.org/?probe=39f08657f8) | Dec 31, 2022 |
| Gigabyte      | B550 AORUS PRO              | [c8da48f03c](https://linux-hardware.org/?probe=c8da48f03c) | Dec 30, 2022 |
| HOUTER        | IPMIP-GS                    | [6fddf7d035](https://linux-hardware.org/?probe=6fddf7d035) | Dec 30, 2022 |
| Biostar       | TA970                       | [6a55825894](https://linux-hardware.org/?probe=6a55825894) | Dec 30, 2022 |
| Gigabyte      | 970A-DS3P                   | [c841093094](https://linux-hardware.org/?probe=c841093094) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | [59f6170d5b](https://linux-hardware.org/?probe=59f6170d5b) | Dec 29, 2022 |
| MSI           | Z490-A PRO                  | [e4e5afd812](https://linux-hardware.org/?probe=e4e5afd812) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | [0d8d6061d7](https://linux-hardware.org/?probe=0d8d6061d7) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | [4bda137e99](https://linux-hardware.org/?probe=4bda137e99) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | [7ce6d4b3e3](https://linux-hardware.org/?probe=7ce6d4b3e3) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | [f828f74e07](https://linux-hardware.org/?probe=f828f74e07) | Dec 29, 2022 |
| PCWare        | IPMH61R1                    | [a221946f02](https://linux-hardware.org/?probe=a221946f02) | Dec 29, 2022 |
| Dell          | 03KWTV A02                  | [82612358ac](https://linux-hardware.org/?probe=82612358ac) | Dec 28, 2022 |
| HP            | 2AF7                        | [9663a281c1](https://linux-hardware.org/?probe=9663a281c1) | Dec 28, 2022 |
| Acer          | Aspire XC-780               | [0d90d1884c](https://linux-hardware.org/?probe=0d90d1884c) | Dec 27, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [5ce1ea886f](https://linux-hardware.org/?probe=5ce1ea886f) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [f56ea263a2](https://linux-hardware.org/?probe=f56ea263a2) | Dec 26, 2022 |
| HP            | 2AF7                        | [287696b4fc](https://linux-hardware.org/?probe=287696b4fc) | Dec 25, 2022 |
| Gigabyte      | GA-770T-USB3                | [08d1b04754](https://linux-hardware.org/?probe=08d1b04754) | Dec 25, 2022 |
| ASRock        | 970 Extreme4                | [2655b3c6b6](https://linux-hardware.org/?probe=2655b3c6b6) | Dec 24, 2022 |
| Intel         | H61                         | [8d5eb236e1](https://linux-hardware.org/?probe=8d5eb236e1) | Dec 24, 2022 |
| HP            | 2AF7                        | [7b79dd8352](https://linux-hardware.org/?probe=7b79dd8352) | Dec 23, 2022 |
| HP            | 2AF7                        | [5ef9ce3357](https://linux-hardware.org/?probe=5ef9ce3357) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | [08a8cc75ac](https://linux-hardware.org/?probe=08a8cc75ac) | Dec 23, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| Zorin 16 | 1401     | 67.85%  |
| Zorin 15 | 553      | 26.78%  |
| Zorin 12 | 76       | 3.68%   |
| Zorin 17 | 35       | 1.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| Zorin | 2059     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Desktops | Percent |
|-------------------|----------|---------|
| 5.15.0-56-generic | 73       | 3.04%   |
| 5.11.0-38-generic | 62       | 2.58%   |
| 5.15.0-67-generic | 58       | 2.42%   |
| 5.15.0-69-generic | 56       | 2.33%   |
| 5.15.0-46-generic | 56       | 2.33%   |
| 5.11.0-27-generic | 56       | 2.33%   |
| 5.11.0-40-generic | 50       | 2.08%   |
| 5.15.0-52-generic | 49       | 2.04%   |
| 5.13.0-39-generic | 49       | 2.04%   |
| 5.15.0-78-generic | 46       | 1.92%   |
| 5.15.0-58-generic | 46       | 1.92%   |
| 5.15.0-60-generic | 45       | 1.88%   |
| 5.15.0-71-generic | 41       | 1.71%   |
| 5.15.0-48-generic | 41       | 1.71%   |
| 5.11.0-41-generic | 41       | 1.71%   |
| 5.3.0-40-generic  | 40       | 1.67%   |
| 5.13.0-30-generic | 40       | 1.67%   |
| 5.13.0-40-generic | 38       | 1.58%   |
| 5.15.0-76-generic | 37       | 1.54%   |
| 5.11.0-43-generic | 36       | 1.5%    |
| 5.15.0-41-generic | 35       | 1.46%   |
| 5.11.0-37-generic | 35       | 1.46%   |
| 5.15.0-84-generic | 34       | 1.42%   |
| 6.2.0-39-generic  | 33       | 1.38%   |
| 5.15.0-91-generic | 32       | 1.33%   |
| 5.4.0-42-generic  | 31       | 1.29%   |
| 5.13.0-28-generic | 31       | 1.29%   |
| 5.11.0-34-generic | 31       | 1.29%   |
| 5.15.0-88-generic | 29       | 1.21%   |
| 5.15.0-53-generic | 29       | 1.21%   |
| 5.13.0-35-generic | 28       | 1.17%   |
| 5.15.0-73-generic | 27       | 1.13%   |
| 5.0.0-37-generic  | 27       | 1.13%   |
| 5.13.0-27-generic | 26       | 1.08%   |
| 5.13.0-41-generic | 25       | 1.04%   |
| 5.15.0-89-generic | 24       | 1%      |
| 5.15.0-83-generic | 24       | 1%      |
| 5.13.0-52-generic | 24       | 1%      |
| 5.15.0-72-generic | 23       | 0.96%   |
| 5.13.0-44-generic | 21       | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 789      | 36.83%  |
| 5.11.0  | 334      | 15.59%  |
| 5.4.0   | 326      | 15.22%  |
| 5.13.0  | 293      | 13.68%  |
| 5.3.0   | 158      | 7.38%   |
| 4.15.0  | 75       | 3.5%    |
| 5.0.0   | 58       | 2.71%   |
| 6.2.0   | 35       | 1.63%   |
| 4.18.0  | 27       | 1.26%   |
| 5.8.0   | 26       | 1.21%   |
| 6.5.7   | 1        | 0.05%   |
| 6.3.2   | 1        | 0.05%   |
| 6.3.0   | 1        | 0.05%   |
| 6.2.7   | 1        | 0.05%   |
| 6.2.16  | 1        | 0.05%   |
| 6.1.8   | 1        | 0.05%   |
| 6.1.7   | 1        | 0.05%   |
| 6.0.8   | 1        | 0.05%   |
| 5.8.5   | 1        | 0.05%   |
| 5.7.17  | 1        | 0.05%   |
| 5.7.1   | 1        | 0.05%   |
| 5.7.0   | 1        | 0.05%   |
| 5.19.6  | 1        | 0.05%   |
| 5.19.2  | 1        | 0.05%   |
| 5.19.12 | 1        | 0.05%   |
| 5.17.9  | 1        | 0.05%   |
| 5.17.5  | 1        | 0.05%   |
| 5.17.1  | 1        | 0.05%   |
| 5.15.13 | 1        | 0.05%   |
| 5.14.0  | 1        | 0.05%   |
| 4.4.0   | 1        | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 790      | 36.9%   |
| 5.11    | 334      | 15.6%   |
| 5.4     | 326      | 15.23%  |
| 5.13    | 293      | 13.69%  |
| 5.3     | 158      | 7.38%   |
| 4.15    | 75       | 3.5%    |
| 5.0     | 58       | 2.71%   |
| 6.2     | 37       | 1.73%   |
| 5.8     | 27       | 1.26%   |
| 4.18    | 27       | 1.26%   |
| 5.7     | 3        | 0.14%   |
| 5.19    | 3        | 0.14%   |
| 5.17    | 3        | 0.14%   |
| 6.3     | 2        | 0.09%   |
| 6.5     | 1        | 0.05%   |
| 6.1     | 1        | 0.05%   |
| 6.0     | 1        | 0.05%   |
| 5.14    | 1        | 0.05%   |
| 4.4     | 1        | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 1947     | 94.56%  |
| i686   | 112      | 5.44%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| GNOME      | 1591     | 76.12%  |
| XFCE       | 371      | 17.75%  |
| Unknown    | 119      | 5.69%   |
| KDE5       | 3        | 0.14%   |
| MATE       | 2        | 0.1%    |
| Cinnamon   | 2        | 0.1%    |
| X-Cinnamon | 1        | 0.05%   |
| KDE        | 1        | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 1962     | 94.65%  |
| Unknown | 68       | 3.28%   |
| Wayland | 42       | 2.03%   |
| Tty     | 1        | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1752     | 83.71%  |
| GDM3    | 141      | 6.74%   |
| GDM     | 111      | 5.3%    |
| LightDM | 84       | 4.01%   |
| TDM     | 4        | 0.19%   |
| SDDM    | 1        | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| en_US       | 770      | 37.16%  |
| de_DE       | 183      | 8.83%   |
| pt_BR       | 147      | 7.09%   |
| en_GB       | 132      | 6.37%   |
| Unknown     | 96       | 4.63%   |
| fr_FR       | 64       | 3.09%   |
| en_CA       | 61       | 2.94%   |
| it_IT       | 60       | 2.9%    |
| en_IN       | 45       | 2.17%   |
| es_ES       | 43       | 2.08%   |
| pl_PL       | 39       | 1.88%   |
| nl_NL       | 39       | 1.88%   |
| en_AU       | 38       | 1.83%   |
| es_AR       | 31       | 1.5%    |
| ru_RU       | 27       | 1.3%    |
| es_MX       | 22       | 1.06%   |
| hu_HU       | 21       | 1.01%   |
| en_ZA       | 21       | 1.01%   |
| cs_CZ       | 14       | 0.68%   |
| sv_SE       | 12       | 0.58%   |
| pt_PT       | 12       | 0.58%   |
| fr_CA       | 11       | 0.53%   |
| nl_BE       | 9        | 0.43%   |
| es_CL       | 9        | 0.43%   |
| tr_TR       | 8        | 0.39%   |
| nb_NO       | 8        | 0.39%   |
| es_CO       | 8        | 0.39%   |
| C           | 8        | 0.39%   |
| ja_JP       | 7        | 0.34%   |
| fi_FI       | 7        | 0.34%   |
| en_NZ       | 7        | 0.34%   |
| el_GR       | 7        | 0.34%   |
| es_VE       | 6        | 0.29%   |
| en_PH       | 6        | 0.29%   |
| de_CH       | 6        | 0.29%   |
| da_DK       | 6        | 0.29%   |
| sk_SK       | 5        | 0.24%   |
| bg_BG       | 5        | 0.24%   |
| sr_RS@latin | 4        | 0.19%   |
| sr_RS       | 4        | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 1265     | 60.88%  |
| EFI  | 813      | 39.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 1915     | 92.29%  |
| Tmpfs    | 41       | 1.98%   |
| Overlay  | 37       | 1.78%   |
| Zfs      | 31       | 1.49%   |
| Btrfs    | 19       | 0.92%   |
| Ext2     | 11       | 0.53%   |
| Unknown  | 10       | 0.48%   |
| Xfs      | 5        | 0.24%   |
| Ext3     | 5        | 0.24%   |
| Reiserfs | 1        | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1864     | 89.66%  |
| GPT     | 136      | 6.54%   |
| MBR     | 79       | 3.8%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1933     | 93.34%  |
| Yes       | 138      | 6.66%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 1673     | 80.43%  |
| Yes       | 407      | 19.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 464      | 22.54%  |
| Gigabyte Technology | 314      | 15.25%  |
| Dell                | 222      | 10.78%  |
| MSI                 | 187      | 9.08%   |
| Hewlett-Packard     | 187      | 9.08%   |
| ASRock              | 149      | 7.24%   |
| Lenovo              | 94       | 4.57%   |
| Intel               | 64       | 3.11%   |
| Unknown             | 41       | 1.99%   |
| Pegatron            | 40       | 1.94%   |
| Acer                | 39       | 1.89%   |
| Biostar             | 27       | 1.31%   |
| Fujitsu             | 25       | 1.21%   |
| Foxconn             | 25       | 1.21%   |
| ECS                 | 19       | 0.92%   |
| Positivo            | 9        | 0.44%   |
| Medion              | 8        | 0.39%   |
| AZW                 | 8        | 0.39%   |
| Alienware           | 8        | 0.39%   |
| Shuttle             | 7        | 0.34%   |
| Apple               | 7        | 0.34%   |
| Gateway             | 5        | 0.24%   |
| eMachines           | 5        | 0.24%   |
| Packard Bell        | 4        | 0.19%   |
| OEM                 | 4        | 0.19%   |
| IBM                 | 4        | 0.19%   |
| Google              | 4        | 0.19%   |
| BESSTAR Tech        | 4        | 0.19%   |
| Semp Toshiba        | 3        | 0.15%   |
| Samsung Electronics | 3        | 0.15%   |
| Huanan              | 3        | 0.15%   |
| ABIT                | 3        | 0.15%   |
| ZOTAC               | 2        | 0.1%    |
| WinFast             | 2        | 0.1%    |
| SiS Technology      | 2        | 0.1%    |
| QIYIDA              | 2        | 0.1%    |
| PCWare              | 2        | 0.1%    |
| MAXSUN              | 2        | 0.1%    |
| MACHINIST           | 2        | 0.1%    |
| LORD ELECTRONICS    | 2        | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Desktops | Percent |
|----------------------------------|----------|---------|
| Unknown                          | 45       | 2.19%   |
| ASUS All Series                  | 42       | 2.04%   |
| Dell OptiPlex 7010               | 16       | 0.78%   |
| Dell OptiPlex 780                | 11       | 0.53%   |
| MSI MS-7817                      | 10       | 0.49%   |
| Gigabyte A320M-S2H               | 10       | 0.49%   |
| Dell OptiPlex 790                | 10       | 0.49%   |
| Dell OptiPlex 380                | 10       | 0.49%   |
| ASUS TUF Gaming X570-PLUS        | 9        | 0.44%   |
| ASUS M5A97 R2.0                  | 9        | 0.44%   |
| ASUS M5A78L-M/USB3               | 9        | 0.44%   |
| MSI MS-7C02                      | 8        | 0.39%   |
| Intel H61                        | 8        | 0.39%   |
| Gigabyte B450 AORUS M            | 8        | 0.39%   |
| Gigabyte 970A-DS3P               | 8        | 0.39%   |
| Dell OptiPlex 755                | 8        | 0.39%   |
| Gigabyte GA-78LMT-USB3 6.0       | 7        | 0.34%   |
| Dell OptiPlex 990                | 7        | 0.34%   |
| Dell OptiPlex 9020               | 7        | 0.34%   |
| Dell OptiPlex 3010               | 7        | 0.34%   |
| HP ProDesk 600 G1 SFF            | 6        | 0.29%   |
| HP EliteDesk 800 G1 SFF          | 6        | 0.29%   |
| Dell Precision WorkStation T3500 | 6        | 0.29%   |
| Dell OptiPlex 7040               | 6        | 0.29%   |
| Dell OptiPlex 7020               | 6        | 0.29%   |
| MSI MS-7C37                      | 5        | 0.24%   |
| HP Compaq Pro 6300 SFF           | 5        | 0.24%   |
| HP Compaq Elite 8300 SFF         | 5        | 0.24%   |
| Gigabyte GA-78LMT-USB3           | 5        | 0.24%   |
| Gigabyte B450M DS3H              | 5        | 0.24%   |
| Dell OptiPlex 390                | 5        | 0.24%   |
| Dell OptiPlex 3050               | 5        | 0.24%   |
| Dell OptiPlex 3020               | 5        | 0.24%   |
| Dell Inspiron 3847               | 5        | 0.24%   |
| ASUS P8Z77-V LX                  | 5        | 0.24%   |
| ASRock N68C-S UCC                | 5        | 0.24%   |
| ASRock B450 Pro4                 | 5        | 0.24%   |
| MSI MS-7C91                      | 4        | 0.19%   |
| MSI MS-7C75                      | 4        | 0.19%   |
| MSI MS-7B89                      | 4        | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 137      | 6.65%   |
| HP Compaq              | 67       | 3.25%   |
| Lenovo ThinkCentre     | 61       | 2.96%   |
| ASUS PRIME             | 58       | 2.82%   |
| ASUS ROG               | 45       | 2.19%   |
| Unknown                | 45       | 2.19%   |
| ASUS TUF               | 44       | 2.14%   |
| ASUS All               | 42       | 2.04%   |
| HP EliteDesk           | 27       | 1.31%   |
| Dell Precision         | 27       | 1.31%   |
| Fujitsu ESPRIMO        | 20       | 0.97%   |
| Dell Inspiron          | 20       | 0.97%   |
| Acer Aspire            | 18       | 0.87%   |
| Gigabyte B450          | 16       | 0.78%   |
| HP ProDesk             | 15       | 0.73%   |
| ASUS M5A97             | 15       | 0.73%   |
| ASUS M5A78L-M          | 14       | 0.68%   |
| Gigabyte GA-78LMT-USB3 | 13       | 0.63%   |
| Lenovo IdeaCentre      | 11       | 0.53%   |
| HP Pavilion            | 11       | 0.53%   |
| Gigabyte A320M-S2H     | 11       | 0.53%   |
| Dell Vostro            | 11       | 0.53%   |
| MSI MS-7817            | 10       | 0.49%   |
| Gigabyte X570          | 10       | 0.49%   |
| Gigabyte B450M         | 10       | 0.49%   |
| Acer Veriton           | 10       | 0.49%   |
| Dell XPS               | 9        | 0.44%   |
| ASUS P8H61-M           | 9        | 0.44%   |
| ASRock B450            | 9        | 0.44%   |
| MSI MS-7C02            | 8        | 0.39%   |
| Intel H61              | 8        | 0.39%   |
| Gigabyte 970A-DS3P     | 8        | 0.39%   |
| ASUS P5G41T-M          | 8        | 0.39%   |
| ASRock B450M           | 8        | 0.39%   |
| ASRock X570            | 7        | 0.34%   |
| ASUS P8Z77-V           | 6        | 0.29%   |
| ASRock N68C-S          | 6        | 0.29%   |
| ASRock 970             | 6        | 0.29%   |
| MSI MS-7C37            | 5        | 0.24%   |
| Gigabyte B550M         | 5        | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2013    | 181      | 8.79%   |
| 2012    | 178      | 8.64%   |
| 2011    | 177      | 8.6%    |
| 2018    | 159      | 7.72%   |
| 2010    | 151      | 7.33%   |
| 2014    | 150      | 7.29%   |
| 2009    | 137      | 6.65%   |
| 2008    | 117      | 5.68%   |
| 2020    | 110      | 5.34%   |
| 2017    | 109      | 5.29%   |
| 2019    | 107      | 5.2%    |
| 2021    | 89       | 4.32%   |
| 2007    | 84       | 4.08%   |
| 2016    | 71       | 3.45%   |
| 2015    | 69       | 3.35%   |
| 2022    | 50       | 2.43%   |
| 2006    | 49       | 2.38%   |
| 2005    | 29       | 1.41%   |
| 2023    | 19       | 0.92%   |
| 2004    | 10       | 0.49%   |
| 2003    | 6        | 0.29%   |
| Unknown | 6        | 0.29%   |
| 2002    | 1        | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 2059     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 1961     | 94.92%  |
| Enabled  | 105      | 5.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2055     | 99.81%  |
| Yes  | 4        | 0.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 442      | 21.1%   |
| 8.01-16.0       | 410      | 19.57%  |
| 3.01-4.0        | 371      | 17.71%  |
| 4.01-8.0        | 341      | 16.28%  |
| 32.01-64.0      | 232      | 11.07%  |
| 1.01-2.0        | 111      | 5.3%    |
| 64.01-256.0     | 67       | 3.2%    |
| 2.01-3.0        | 52       | 2.48%   |
| 24.01-32.0      | 43       | 2.05%   |
| 0.51-1.0        | 25       | 1.19%   |
| More than 256.0 | 1        | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 877      | 38.91%  |
| 2.01-3.0   | 610      | 27.06%  |
| 3.01-4.0   | 286      | 12.69%  |
| 4.01-8.0   | 260      | 11.54%  |
| 0.51-1.0   | 138      | 6.12%   |
| 8.01-16.0  | 54       | 2.4%    |
| 0.01-0.5   | 16       | 0.71%   |
| 16.01-24.0 | 9        | 0.4%    |
| 32.01-64.0 | 2        | 0.09%   |
| 24.01-32.0 | 2        | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 1015     | 47.76%  |
| 2      | 588      | 27.67%  |
| 3      | 251      | 11.81%  |
| 4      | 133      | 6.26%   |
| 5      | 65       | 3.06%   |
| 6      | 36       | 1.69%   |
| 7      | 13       | 0.61%   |
| 8      | 10       | 0.47%   |
| 0      | 9        | 0.42%   |
| 11     | 2        | 0.09%   |
| 51     | 1        | 0.05%   |
| 10     | 1        | 0.05%   |
| 9      | 1        | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1109     | 53.42%  |
| No        | 967      | 46.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 2035     | 98.83%  |
| No        | 24       | 1.17%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1048     | 50.36%  |
| Yes       | 1033     | 49.64%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 1454     | 69.94%  |
| Yes       | 625      | 30.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 517      | 25.04%  |
| Germany      | 205      | 9.93%   |
| Brazil       | 163      | 7.89%   |
| UK           | 134      | 6.49%   |
| Canada       | 82       | 3.97%   |
| Italy        | 72       | 3.49%   |
| Netherlands  | 64       | 3.1%    |
| France       | 61       | 2.95%   |
| India        | 49       | 2.37%   |
| Spain        | 47       | 2.28%   |
| Poland       | 44       | 2.13%   |
| Australia    | 41       | 1.99%   |
| Argentina    | 37       | 1.79%   |
| Mexico       | 27       | 1.31%   |
| Hungary      | 25       | 1.21%   |
| South Africa | 23       | 1.11%   |
| Russia       | 21       | 1.02%   |
| Greece       | 21       | 1.02%   |
| Sweden       | 19       | 0.92%   |
| Denmark      | 19       | 0.92%   |
| Czechia      | 19       | 0.92%   |
| Belgium      | 19       | 0.92%   |
| Indonesia    | 18       | 0.87%   |
| Portugal     | 17       | 0.82%   |
| Switzerland  | 16       | 0.77%   |
| Norway       | 16       | 0.77%   |
| Serbia       | 15       | 0.73%   |
| Chile        | 15       | 0.73%   |
| Colombia     | 13       | 0.63%   |
| Turkey       | 11       | 0.53%   |
| Bulgaria     | 11       | 0.53%   |
| Romania      | 10       | 0.48%   |
| Malaysia     | 10       | 0.48%   |
| Japan        | 10       | 0.48%   |
| Finland      | 10       | 0.48%   |
| Egypt        | 10       | 0.48%   |
| Venezuela    | 9        | 0.44%   |
| Slovakia     | 9        | 0.44%   |
| Philippines  | 9        | 0.44%   |
| Ukraine      | 8        | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Desktops | Percent |
|----------------|----------|---------|
| Rio de Janeiro | 18       | 0.83%   |
| Berlin         | 18       | 0.83%   |
| Sao Paulo      | 16       | 0.74%   |
| Athens         | 15       | 0.69%   |
| Munich         | 12       | 0.56%   |
| Cape Town      | 12       | 0.56%   |
| Milan          | 10       | 0.46%   |
| Houston        | 10       | 0.46%   |
| Toronto        | 9        | 0.42%   |
| Rome           | 9        | 0.42%   |
| Perth          | 9        | 0.42%   |
| Denver         | 9        | 0.42%   |
| Copenhagen     | 9        | 0.42%   |
| Phoenix        | 8        | 0.37%   |
| Buenos Aires   | 8        | 0.37%   |
| Bogotá        | 8        | 0.37%   |
| Belgrade       | 8        | 0.37%   |
| Adelaide       | 8        | 0.37%   |
| Zurich         | 7        | 0.32%   |
| Sydney         | 7        | 0.32%   |
| Santiago       | 7        | 0.32%   |
| Montreal       | 7        | 0.32%   |
| London         | 7        | 0.32%   |
| Calgary        | 7        | 0.32%   |
| Budapest       | 7        | 0.32%   |
| Bengaluru      | 7        | 0.32%   |
| Atlanta        | 7        | 0.32%   |
| Warsaw         | 6        | 0.28%   |
| Vienna         | 6        | 0.28%   |
| The Hague      | 6        | 0.28%   |
| San Jose       | 6        | 0.28%   |
| Portland       | 6        | 0.28%   |
| Melbourne      | 6        | 0.28%   |
| Las Vegas      | 6        | 0.28%   |
| Johannesburg   | 6        | 0.28%   |
| Hamburg        | 6        | 0.28%   |
| Dortmund       | 6        | 0.28%   |
| Dayton         | 6        | 0.28%   |
| Dallas         | 6        | 0.28%   |
| Brasília      | 6        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 698      | 1058   | 19.94%  |
| WDC                         | 635      | 915    | 18.14%  |
| Samsung Electronics         | 444      | 692    | 12.68%  |
| Kingston                    | 213      | 301    | 6.08%   |
| SanDisk                     | 173      | 237    | 4.94%   |
| Toshiba                     | 172      | 258    | 4.91%   |
| Hitachi                     | 163      | 200    | 4.66%   |
| Crucial                     | 122      | 147    | 3.48%   |
| China                       | 56       | 64     | 1.6%    |
| Maxtor                      | 47       | 66     | 1.34%   |
| A-DATA Technology           | 42       | 52     | 1.2%    |
| Unknown                     | 37       | 63     | 1.06%   |
| Intel                       | 37       | 45     | 1.06%   |
| PNY                         | 32       | 43     | 0.91%   |
| Phison                      | 32       | 41     | 0.91%   |
| Silicon Motion              | 30       | 41     | 0.86%   |
| Intenso                     | 25       | 31     | 0.71%   |
| HGST                        | 24       | 35     | 0.69%   |
| Micron/Crucial Technology   | 23       | 26     | 0.66%   |
| SK hynix                    | 22       | 28     | 0.63%   |
| SPCC                        | 20       | 28     | 0.57%   |
| Patriot                     | 19       | 31     | 0.54%   |
| OCZ                         | 18       | 21     | 0.51%   |
| Micron Technology           | 18       | 19     | 0.51%   |
| GOODRAM                     | 14       | 17     | 0.4%    |
| Lexar                       | 13       | 15     | 0.37%   |
| JMicron Technology          | 13       | 18     | 0.37%   |
| Phison Electronics          | 12       | 15     | 0.34%   |
| Hewlett-Packard             | 12       | 16     | 0.34%   |
| Unknown                     | 12       | 13     | 0.34%   |
| KingSpec                    | 11       | 14     | 0.31%   |
| Gigabyte Technology         | 11       | 19     | 0.31%   |
| Corsair                     | 11       | 18     | 0.31%   |
| Apple                       | 11       | 12     | 0.31%   |
| Realtek Semiconductor       | 10       | 10     | 0.29%   |
| MAXIO Technology (Hangzhou) | 10       | 10     | 0.29%   |
| Apacer                      | 10       | 13     | 0.29%   |
| Transcend                   | 9        | 10     | 0.26%   |
| Netac                       | 9        | 13     | 0.26%   |
| Kingston Technology Company | 9        | 12     | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB                     | 64       | 1.61%   |
| Kingston SA400S37240G 240GB SSD                     | 59       | 1.48%   |
| Seagate ST1000DM010-2EP102 1TB                      | 43       | 1.08%   |
| Samsung SSD 860 EVO 500GB                           | 32       | 0.8%    |
| Kingston SA400S37120G 120GB SSD                     | 32       | 0.8%    |
| Seagate ST3500418AS 500GB                           | 31       | 0.78%   |
| Crucial CT240BX500SSD1 240GB                        | 29       | 0.73%   |
| Seagate ST1000DM003-1CH162 1TB                      | 28       | 0.7%    |
| Samsung SSD 850 EVO 250GB                           | 27       | 0.68%   |
| Toshiba DT01ACA100 1TB                              | 26       | 0.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 26       | 0.65%   |
| Kingston SA400S37480G 480GB SSD                     | 26       | 0.65%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 25       | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB                      | 24       | 0.6%    |
| Toshiba HDWD110 1TB                                 | 22       | 0.55%   |
| Kingston SV300S37A120G 120GB SSD                    | 22       | 0.55%   |
| Samsung NVMe SSD Drive 1TB                          | 21       | 0.53%   |
| Seagate ST2000DM001-1ER164 2TB                      | 20       | 0.5%    |
| Samsung NVMe SSD Drive 500GB                        | 20       | 0.5%    |
| Seagate ST31000528AS 1TB                            | 18       | 0.45%   |
| Samsung SSD 850 EVO 500GB                           | 18       | 0.45%   |
| Seagate ST2000DM008-2FR102 2TB                      | 17       | 0.43%   |
| Crucial CT500MX500SSD1 500GB                        | 17       | 0.43%   |
| Unknown SD/MMC/MS PRO 512GB                         | 16       | 0.4%    |
| Seagate ST3500413AS 500GB                           | 16       | 0.4%    |
| Toshiba DT01ACA050 500GB                            | 15       | 0.38%   |
| Seagate ST4000DM004-2CV104 4TB                      | 15       | 0.38%   |
| SanDisk NVMe SSD Drive 500GB                        | 15       | 0.38%   |
| Seagate ST3500312CS 500GB                           | 14       | 0.35%   |
| Seagate ST1000DM003-1SB102 1TB                      | 14       | 0.35%   |
| Samsung SSD 840 EVO 250GB                           | 14       | 0.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 14       | 0.35%   |
| Crucial CT1000MX500SSD1 1TB                         | 14       | 0.35%   |
| Toshiba DT01ACA200 2TB                              | 13       | 0.33%   |
| SanDisk NVMe SSD Drive 1TB                          | 13       | 0.33%   |
| Seagate ST3250310AS 250GB                           | 12       | 0.3%    |
| Seagate ST31000524AS 1TB                            | 12       | 0.3%    |
| Seagate ST2000DM001-1CH164 2TB                      | 12       | 0.3%    |
| SanDisk SSD PLUS 240GB                              | 12       | 0.3%    |
| Samsung SSD 870 EVO 1TB                             | 12       | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 687      | 1033   | 37.34%  |
| WDC                 | 589      | 833    | 32.01%  |
| Hitachi             | 163      | 200    | 8.86%   |
| Toshiba             | 152      | 235    | 8.26%   |
| Samsung Electronics | 125      | 167    | 6.79%   |
| Maxtor              | 46       | 65     | 2.5%    |
| HGST                | 24       | 35     | 1.3%    |
| Unknown             | 17       | 23     | 0.92%   |
| SABRENT             | 7        | 8      | 0.38%   |
| Apple               | 7        | 8      | 0.38%   |
| USB3.0              | 4        | 5      | 0.22%   |
| Hewlett-Packard     | 4        | 7      | 0.22%   |
| XrayDisk            | 2        | 2      | 0.11%   |
| QUANTUM             | 2        | 2      | 0.11%   |
| External            | 2        | 2      | 0.11%   |
| WD MediaMax         | 1        | 1      | 0.05%   |
| TO Exter            | 1        | 1      | 0.05%   |
| TDAS                | 1        | 3      | 0.05%   |
| Intenso             | 1        | 2      | 0.05%   |
| HGST HTS            | 1        | 1      | 0.05%   |
| Fujitsu             | 1        | 1      | 0.05%   |
| ExcelStor           | 1        | 1      | 0.05%   |
| ASMT109x            | 1        | 2      | 0.05%   |
| ACASIS              | 1        | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 227      | 333    | 19.03%  |
| Kingston            | 186      | 249    | 15.59%  |
| Crucial             | 117      | 142    | 9.81%   |
| SanDisk             | 111      | 146    | 9.3%    |
| WDC                 | 57       | 72     | 4.78%   |
| China               | 55       | 63     | 4.61%   |
| A-DATA Technology   | 40       | 50     | 3.35%   |
| PNY                 | 32       | 43     | 2.68%   |
| Intel               | 26       | 31     | 2.18%   |
| Intenso             | 20       | 24     | 1.68%   |
| SPCC                | 19       | 27     | 1.59%   |
| Patriot             | 18       | 30     | 1.51%   |
| OCZ                 | 17       | 20     | 1.42%   |
| Toshiba             | 13       | 15     | 1.09%   |
| Micron Technology   | 13       | 14     | 1.09%   |
| Lexar               | 13       | 15     | 1.09%   |
| GOODRAM             | 13       | 16     | 1.09%   |
| KingSpec            | 10       | 13     | 0.84%   |
| JMicron Technology  | 10       | 14     | 0.84%   |
| Apacer              | 10       | 13     | 0.84%   |
| Transcend           | 9        | 10     | 0.75%   |
| SK hynix            | 9        | 9      | 0.75%   |
| Netac               | 9        | 12     | 0.75%   |
| Gigabyte Technology | 9        | 16     | 0.75%   |
| Hewlett-Packard     | 8        | 9      | 0.67%   |
| Corsair             | 8        | 14     | 0.67%   |
| Team                | 7        | 9      | 0.59%   |
| Leven               | 7        | 8      | 0.59%   |
| Verbatim            | 5        | 6      | 0.42%   |
| LITEON              | 5        | 6      | 0.42%   |
| Unknown             | 5        | 6      | 0.42%   |
| Super Talent        | 4        | 5      | 0.34%   |
| Seagate             | 4        | 7      | 0.34%   |
| Drevo               | 4        | 6      | 0.34%   |
| Plextor             | 3        | 4      | 0.25%   |
| Pioneer             | 3        | 3      | 0.25%   |
| Mushkin             | 3        | 3      | 0.25%   |
| LITEONIT            | 3        | 3      | 0.25%   |
| KIOXIA-EXCERIA      | 3        | 7      | 0.25%   |
| Fanxiang            | 3        | 3      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1433     | 2638   | 48.89%  |
| SSD     | 1001     | 1569   | 34.15%  |
| NVMe    | 408      | 618    | 13.92%  |
| Unknown | 81       | 106    | 2.76%   |
| MMC     | 8        | 9      | 0.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 1919     | 4110   | 77.6%   |
| NVMe | 407      | 616    | 16.46%  |
| SAS  | 139      | 205    | 5.62%   |
| MMC  | 8        | 9      | 0.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 1470     | 2430   | 56.56%  |
| 0.51-1.0   | 679      | 1057   | 26.13%  |
| 1.01-2.0   | 268      | 387    | 10.31%  |
| 3.01-4.0   | 74       | 160    | 2.85%   |
| 4.01-10.0  | 53       | 77     | 2.04%   |
| 2.01-3.0   | 45       | 65     | 1.73%   |
| 10.01-20.0 | 9        | 29     | 0.35%   |
| 20.01-50.0 | 1        | 2      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 646      | 29.95%  |
| 251-500        | 484      | 22.44%  |
| 501-1000       | 316      | 14.65%  |
| 1001-2000      | 194      | 8.99%   |
| 51-100         | 155      | 7.19%   |
| More than 3000 | 135      | 6.26%   |
| 21-50          | 81       | 3.76%   |
| 2001-3000      | 68       | 3.15%   |
| 1-20           | 58       | 2.69%   |
| Unknown        | 20       | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 883      | 39.26%  |
| 21-50          | 507      | 22.54%  |
| 51-100         | 257      | 11.43%  |
| 101-250        | 202      | 8.98%   |
| 251-500        | 139      | 6.18%   |
| 501-1000       | 101      | 4.49%   |
| 1001-2000      | 62       | 2.76%   |
| More than 3000 | 59       | 2.62%   |
| Unknown        | 20       | 0.89%   |
| 2001-3000      | 19       | 0.84%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Desktops | Drives | Percent |
|------------------------------------------|----------|--------|---------|
| WDC WD30EFRX-68EUZN0 3TB                 | 2        | 2      | 3.7%    |
| Seagate ST500DM002-1BD142 500GB          | 2        | 2      | 3.7%    |
| Seagate ST2000LM007-1R8174 2TB           | 2        | 2      | 3.7%    |
| HGST HTS541010A9E680 1TB                 | 2        | 2      | 3.7%    |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1        | 1      | 1.85%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1        | 1      | 1.85%   |
| WDC WD5000AAKS-00V1A0 500GB              | 1        | 1      | 1.85%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1        | 1      | 1.85%   |
| WDC WD2500AAJS-00B4A0 250GB              | 1        | 1      | 1.85%   |
| WDC WD20EZRX-22D8PB0 2TB                 | 1        | 1      | 1.85%   |
| WDC WD20EZRX-00D8PB0 2TB                 | 1        | 1      | 1.85%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1        | 2      | 1.85%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1        | 1      | 1.85%   |
| WDC WD Green 2.5 1000GB                  | 1        | 1      | 1.85%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1        | 1      | 1.85%   |
| Toshiba MQ01ABD100 1TB                   | 1        | 1      | 1.85%   |
| Toshiba MK8046GSX 80GB                   | 1        | 1      | 1.85%   |
| Toshiba MK3265GSX 320GB                  | 1        | 1      | 1.85%   |
| Toshiba MG03ACA200 2TB                   | 1        | 1      | 1.85%   |
| Toshiba DT01ACA100 1TB                   | 1        | 1      | 1.85%   |
| Silicon Motion Inland NVMe SSD 256GB     | 1        | 1      | 1.85%   |
| Seagate ST9500420AS 500GB                | 1        | 1      | 1.85%   |
| Seagate ST8000DM004-2CX188 8TB           | 1        | 1      | 1.85%   |
| Seagate ST4000DM004-2CV104 4TB           | 1        | 1      | 1.85%   |
| Seagate ST3500514NS 500GB                | 1        | 1      | 1.85%   |
| Seagate ST3500413AS 500GB                | 1        | 1      | 1.85%   |
| Seagate ST3500312CS 500GB                | 1        | 1      | 1.85%   |
| Seagate ST3360320AS 360GB                | 1        | 1      | 1.85%   |
| Seagate ST3320620AS 320GB                | 1        | 1      | 1.85%   |
| Seagate ST3250318AS 250GB                | 1        | 1      | 1.85%   |
| Seagate ST320LT012-1DG14C 320GB          | 1        | 1      | 1.85%   |
| Seagate ST320LT009-9WC142 320GB          | 1        | 1      | 1.85%   |
| Seagate ST3160310CS 160GB                | 1        | 1      | 1.85%   |
| Seagate ST2000LM003 HN-M201RAD 2TB       | 1        | 1      | 1.85%   |
| Seagate ST2000DX002-2DV164 2TB           | 1        | 1      | 1.85%   |
| Seagate ST2000DM008-2FR102 2TB           | 1        | 1      | 1.85%   |
| Seagate ST2000DM001-9YN164 2TB           | 1        | 1      | 1.85%   |
| Seagate ST2000DL003-9VT166 2TB           | 1        | 1      | 1.85%   |
| Seagate ST1000DM003-1ER162 1TB           | 1        | 1      | 1.85%   |
| Samsung Electronics HD154UI 1TB          | 1        | 1      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 21       | 22     | 39.62%  |
| WDC                 | 12       | 13     | 22.64%  |
| Toshiba             | 6        | 6      | 11.32%  |
| HGST                | 3        | 3      | 5.66%   |
| Kingston            | 2        | 2      | 3.77%   |
| A-DATA Technology   | 2        | 2      | 3.77%   |
| Silicon Motion      | 1        | 1      | 1.89%   |
| Samsung Electronics | 1        | 1      | 1.89%   |
| OCZ                 | 1        | 1      | 1.89%   |
| Maxtor              | 1        | 1      | 1.89%   |
| Intel               | 1        | 1      | 1.89%   |
| Hitachi             | 1        | 1      | 1.89%   |
| China               | 1        | 1      | 1.89%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 21       | 22     | 50%     |
| WDC                 | 10       | 11     | 23.81%  |
| Toshiba             | 5        | 5      | 11.9%   |
| HGST                | 3        | 3      | 7.14%   |
| Samsung Electronics | 1        | 1      | 2.38%   |
| Maxtor              | 1        | 1      | 2.38%   |
| Hitachi             | 1        | 1      | 2.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 38       | 44     | 77.55%  |
| SSD  | 9        | 9      | 18.37%  |
| NVMe | 2        | 2      | 4.08%   |

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
| Detected | 1931     | 4538   | 91.04%  |
| Works    | 142      | 347    | 6.69%   |
| Malfunc  | 48       | 55     | 2.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1327     | 48.64%  |
| AMD                              | 603      | 22.1%   |
| Samsung Electronics              | 134      | 4.91%   |
| Nvidia                           | 93       | 3.41%   |
| ASMedia Technology               | 76       | 2.79%   |
| SanDisk                          | 74       | 2.71%   |
| JMicron Technology               | 68       | 2.49%   |
| Marvell Technology Group         | 49       | 1.8%    |
| Phison Electronics               | 48       | 1.76%   |
| Kingston Technology Company      | 43       | 1.58%   |
| Silicon Motion                   | 32       | 1.17%   |
| VIA Technologies                 | 28       | 1.03%   |
| Micron/Crucial Technology        | 28       | 1.03%   |
| ADATA Technology                 | 13       | 0.48%   |
| SK hynix                         | 12       | 0.44%   |
| Silicon Image                    | 12       | 0.44%   |
| MAXIO Technology (Hangzhou)      | 11       | 0.4%    |
| Realtek Semiconductor            | 10       | 0.37%   |
| Seagate Technology               | 9        | 0.33%   |
| KIOXIA                           | 8        | 0.29%   |
| Toshiba America Info Systems     | 6        | 0.22%   |
| Silicon Integrated Systems [SiS] | 6        | 0.22%   |
| Broadcom / LSI                   | 6        | 0.22%   |
| Micron Technology                | 5        | 0.18%   |
| Shenzhen Longsys Electronics     | 3        | 0.11%   |
| Integrated Technology Express    | 3        | 0.11%   |
| INNOGRIT                         | 3        | 0.11%   |
| OCZ Technology Group             | 2        | 0.07%   |
| HighPoint Technologies           | 2        | 0.07%   |
| Apple                            | 2        | 0.07%   |
| Union Memory (Shenzhen)          | 1        | 0.04%   |
| TenaFe                           | 1        | 0.04%   |
| Solid State Storage Technology   | 1        | 0.04%   |
| Promise Technology               | 1        | 0.04%   |
| Nextorage                        | 1        | 0.04%   |
| Netac Technology                 | 1        | 0.04%   |
| LSI Logic / Symbios Logic        | 1        | 0.04%   |
| Lite-On Technology               | 1        | 0.04%   |
| Lite-On IT Corp. / Plextor       | 1        | 0.04%   |
| Hewlett-Packard                  | 1        | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 311      | 8.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 180      | 5.03%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 166      | 4.64%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 133      | 3.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 123      | 3.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 122      | 3.41%   |
| AMD 400 Series Chipset SATA Controller                                                  | 103      | 2.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 95       | 2.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 87       | 2.43%   |
| Intel SATA Controller [RAID mode]                                                       | 85       | 2.37%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 81       | 2.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 72       | 2.01%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 68       | 1.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 63       | 1.76%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 54       | 1.51%   |
| Nvidia MCP61 SATA Controller                                                            | 52       | 1.45%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 51       | 1.42%   |
| AMD 500 Series Chipset SATA Controller                                                  | 51       | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 50       | 1.4%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 42       | 1.17%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 37       | 1.03%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 37       | 1.03%   |
| Nvidia MCP61 IDE                                                                        | 36       | 1.01%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 33       | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 32       | 0.89%   |
| AMD FCH SATA Controller D                                                               | 31       | 0.87%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 28       | 0.78%   |
| Phison E12 NVMe Controller                                                              | 27       | 0.75%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 27       | 0.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 27       | 0.75%   |
| AMD 300 Series Chipset SATA Controller                                                  | 27       | 0.75%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 26       | 0.73%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 25       | 0.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 25       | 0.7%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 24       | 0.67%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 23       | 0.64%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 22       | 0.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 21       | 0.59%   |
| JMicron JMB368 IDE controller                                                           | 21       | 0.59%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 21       | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 1489     | 53.6%   |
| IDE  | 715      | 25.74%  |
| NVMe | 406      | 14.61%  |
| RAID | 153      | 5.51%   |
| SAS  | 9        | 0.32%   |
| SCSI | 6        | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 1369     | 66.49%  |
| AMD    | 690      | 33.51%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i5-2400 CPU @ 3.10GHz            | 38       | 1.84%   |
| AMD Ryzen 5 3600 6-Core Processor           | 33       | 1.6%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 28       | 1.35%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 26       | 1.26%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 26       | 1.26%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 19       | 0.92%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 19       | 0.92%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 19       | 0.92%   |
| Intel Pentium 4 CPU 3.00GHz                 | 18       | 0.87%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 17       | 0.82%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 17       | 0.82%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 17       | 0.82%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 16       | 0.77%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 16       | 0.77%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 16       | 0.77%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 16       | 0.77%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 16       | 0.77%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 16       | 0.77%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 16       | 0.77%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 15       | 0.73%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 15       | 0.73%   |
| AMD FX-6300 Six-Core Processor              | 15       | 0.73%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 14       | 0.68%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 14       | 0.68%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 14       | 0.68%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 14       | 0.68%   |
| AMD FX-8350 Eight-Core Processor            | 14       | 0.68%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 13       | 0.63%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 13       | 0.63%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 13       | 0.63%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 12       | 0.58%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 12       | 0.58%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 12       | 0.58%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz      | 11       | 0.53%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 11       | 0.53%   |
| Intel Core i5-4570T CPU @ 2.90GHz           | 11       | 0.53%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 11       | 0.53%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 10       | 0.48%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 10       | 0.48%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 10       | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 365      | 17.68%  |
| Intel Core i7           | 210      | 10.17%  |
| Intel Core i3           | 161      | 7.8%    |
| AMD Ryzen 5             | 135      | 6.54%   |
| Intel Xeon              | 99       | 4.8%    |
| Intel Core 2 Duo        | 93       | 4.51%   |
| AMD FX                  | 82       | 3.97%   |
| AMD Ryzen 7             | 78       | 3.78%   |
| Intel Celeron           | 66       | 3.2%    |
| Intel Core 2 Quad       | 65       | 3.15%   |
| Intel Pentium Dual-Core | 58       | 2.81%   |
| Other                   | 56       | 2.71%   |
| Intel Pentium Dual      | 47       | 2.28%   |
| Intel Pentium           | 47       | 2.28%   |
| AMD Ryzen 9             | 47       | 2.28%   |
| AMD Athlon II X2        | 43       | 2.08%   |
| Intel Pentium 4         | 39       | 1.89%   |
| AMD Athlon 64 X2        | 35       | 1.7%    |
| AMD Ryzen 3             | 32       | 1.55%   |
| AMD Phenom II X4        | 30       | 1.45%   |
| AMD A8                  | 27       | 1.31%   |
| AMD A10                 | 20       | 0.97%   |
| Intel Core 2            | 19       | 0.92%   |
| AMD A6                  | 19       | 0.92%   |
| AMD A4                  | 17       | 0.82%   |
| AMD Athlon              | 16       | 0.78%   |
| Intel Core i9           | 15       | 0.73%   |
| AMD Sempron             | 14       | 0.68%   |
| AMD Phenom II X6        | 13       | 0.63%   |
| Intel Atom              | 12       | 0.58%   |
| AMD Athlon II X4        | 12       | 0.58%   |
| Intel Pentium D         | 10       | 0.48%   |
| AMD Athlon II X3        | 9        | 0.44%   |
| AMD Phenom              | 7        | 0.34%   |
| AMD Athlon 64           | 7        | 0.34%   |
| Intel Pentium Gold      | 6        | 0.29%   |
| AMD Ryzen Threadripper  | 4        | 0.19%   |
| AMD Phenom II X2        | 4        | 0.19%   |
| AMD E1                  | 4        | 0.19%   |
| AMD E                   | 4        | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 796      | 38.51%  |
| 2      | 676      | 32.7%   |
| 6      | 221      | 10.69%  |
| 8      | 144      | 6.97%   |
| 1      | 107      | 5.18%   |
| 3      | 37       | 1.79%   |
| 12     | 36       | 1.74%   |
| 16     | 26       | 1.26%   |
| 10     | 15       | 0.73%   |
| 14     | 3        | 0.15%   |
| 28     | 2        | 0.1%    |
| 24     | 2        | 0.1%    |
| 20     | 1        | 0.05%   |
| 18     | 1        | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 2043     | 99.22%  |
| 2      | 16       | 0.78%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 1067     | 51.8%   |
| 2      | 993      | 48.2%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 2030     | 98.59%  |
| 32-bit         | 28       | 1.36%   |
| Unknown        | 1        | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 229      | 10.93%  |
| 0x306c3    | 210      | 10.02%  |
| 0x1067a    | 154      | 7.35%   |
| 0x206a7    | 147      | 7.01%   |
| 0x306a9    | 127      | 6.06%   |
| 0x506e3    | 72       | 3.44%   |
| 0x06000852 | 57       | 2.72%   |
| 0x6fd      | 56       | 2.67%   |
| 0x08701021 | 54       | 2.58%   |
| 0x010000c8 | 49       | 2.34%   |
| 0x906ea    | 35       | 1.67%   |
| 0x906e9    | 35       | 1.67%   |
| 0x0800820d | 35       | 1.67%   |
| 0x6fb      | 32       | 1.53%   |
| 0x06001119 | 32       | 1.53%   |
| 0xa0655    | 27       | 1.29%   |
| 0xa0653    | 24       | 1.15%   |
| 0x20655    | 22       | 1.05%   |
| 0x0600063e | 21       | 1%      |
| 0x010000db | 21       | 1%      |
| 0x10676    | 20       | 0.95%   |
| 0x08108109 | 20       | 0.95%   |
| 0x0a201016 | 19       | 0.91%   |
| 0xa0671    | 18       | 0.86%   |
| 0x106e5    | 18       | 0.86%   |
| 0x906ed    | 17       | 0.81%   |
| 0x06003106 | 17       | 0.81%   |
| 0x08001138 | 16       | 0.76%   |
| 0x20652    | 15       | 0.72%   |
| 0x106a5    | 15       | 0.72%   |
| 0x010000dc | 15       | 0.72%   |
| 0x906eb    | 14       | 0.67%   |
| 0x08701013 | 14       | 0.67%   |
| 0x6f6      | 13       | 0.62%   |
| 0x306f2    | 12       | 0.57%   |
| 0x206d7    | 12       | 0.57%   |
| 0x0a50000d | 12       | 0.57%   |
| 0x03000027 | 12       | 0.57%   |
| 0xf43      | 11       | 0.52%   |
| 0x306e4    | 11       | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 244      | 11.83%  |
| Penryn           | 186      | 9.02%   |
| SandyBridge      | 167      | 8.1%    |
| IvyBridge        | 145      | 7.03%   |
| K10              | 124      | 6.01%   |
| Core             | 121      | 5.87%   |
| KabyLake         | 119      | 5.77%   |
| Piledriver       | 95       | 4.6%    |
| Zen 2            | 90       | 4.36%   |
| Skylake          | 79       | 3.83%   |
| Zen 3            | 73       | 3.54%   |
| Zen+             | 66       | 3.2%    |
| K8 Hammer        | 61       | 2.96%   |
| Zen              | 60       | 2.91%   |
| NetBurst         | 57       | 2.76%   |
| CometLake        | 54       | 2.62%   |
| Westmere         | 50       | 2.42%   |
| Unknown          | 43       | 2.08%   |
| Nehalem          | 40       | 1.94%   |
| Bulldozer        | 23       | 1.11%   |
| Silvermont       | 21       | 1.02%   |
| Steamroller      | 18       | 0.87%   |
| Excavator        | 18       | 0.87%   |
| IceLake          | 16       | 0.78%   |
| Alderlake Hybrid | 15       | 0.73%   |
| K10 Llano        | 12       | 0.58%   |
| Jaguar           | 11       | 0.53%   |
| Bonnell          | 10       | 0.48%   |
| Goldmont plus    | 9        | 0.44%   |
| Bobcat           | 9        | 0.44%   |
| Puma             | 8        | 0.39%   |
| Broadwell        | 8        | 0.39%   |
| Tremont          | 4        | 0.19%   |
| K6               | 3        | 0.15%   |
| Goldmont         | 2        | 0.1%    |
| TigerLake        | 1        | 0.05%   |
| P6               | 1        | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 800      | 36.53%  |
| Intel                            | 706      | 32.24%  |
| AMD                              | 668      | 30.5%   |
| VIA Technologies                 | 8        | 0.37%   |
| Silicon Integrated Systems [SiS] | 2        | 0.09%   |
| Matrox Electronics Systems       | 2        | 0.09%   |
| Trident Microsystems             | 1        | 0.05%   |
| Silicon Motion                   | 1        | 0.05%   |
| ATI Technologies                 | 1        | 0.05%   |
| ASPEED Technology                | 1        | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 118      | 5.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 84       | 3.74%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 73       | 3.25%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 68       | 3.02%   |
| Nvidia GK208B [GeForce GT 710]                                              | 60       | 2.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 55       | 2.45%   |
| Intel HD Graphics 530                                                       | 38       | 1.69%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 37       | 1.65%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 37       | 1.65%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 35       | 1.56%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 30       | 1.33%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 28       | 1.25%   |
| Nvidia GK208B [GeForce GT 730]                                              | 28       | 1.25%   |
| Intel Core Processor Integrated Graphics Controller                         | 28       | 1.25%   |
| Nvidia GT218 [GeForce 210]                                                  | 26       | 1.16%   |
| Intel HD Graphics 630                                                       | 24       | 1.07%   |
| AMD RS780L [Radeon 3000]                                                    | 24       | 1.07%   |
| Nvidia GF119 [GeForce GT 610]                                               | 22       | 0.98%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 22       | 0.98%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 22       | 0.98%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 21       | 0.93%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 19       | 0.85%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 18       | 0.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 18       | 0.8%    |
| Intel 82945G/GZ Integrated Graphics Controller                              | 17       | 0.76%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 17       | 0.76%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 16       | 0.71%   |
| Nvidia GF108 [GeForce GT 730]                                               | 16       | 0.71%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 15       | 0.67%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 15       | 0.67%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 15       | 0.67%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 14       | 0.62%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 14       | 0.62%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 14       | 0.62%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 13       | 0.58%   |
| AMD Raphael                                                                 | 13       | 0.58%   |
| Nvidia GF108 [GeForce GT 630]                                               | 12       | 0.53%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 12       | 0.53%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 12       | 0.53%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 12       | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 745      | 35.83%  |
| 1 x Intel                | 624      | 30.01%  |
| 1 x AMD                  | 599      | 28.81%  |
| 2 x AMD                  | 37       | 1.78%   |
| Intel + Nvidia           | 23       | 1.11%   |
| Intel + AMD              | 16       | 0.77%   |
| AMD + Nvidia             | 15       | 0.72%   |
| 1 x VIA                  | 8        | 0.38%   |
| 2 x Nvidia               | 4        | 0.19%   |
| 1 x SiS                  | 2        | 0.1%    |
| 1 x Matrox               | 2        | 0.1%    |
| 2 x AMD + 1 x Nvidia     | 1        | 0.05%   |
| 1 x Trident Microsystems | 1        | 0.05%   |
| Nvidia + Silicon Motion  | 1        | 0.05%   |
| 1 x ASPEED               | 1        | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 1458     | 69.86%  |
| Proprietary | 473      | 22.66%  |
| Unknown     | 156      | 7.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 901      | 42.68%  |
| 0.01-0.5   | 293      | 13.88%  |
| 1.01-2.0   | 269      | 12.74%  |
| 0.51-1.0   | 263      | 12.46%  |
| 3.01-4.0   | 141      | 6.68%   |
| 7.01-8.0   | 130      | 6.16%   |
| 8.01-16.0  | 44       | 2.08%   |
| 5.01-6.0   | 43       | 2.04%   |
| 2.01-3.0   | 22       | 1.04%   |
| 16.01-24.0 | 4        | 0.19%   |
| 4.01-5.0   | 1        | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 315      | 15.81%  |
| Dell                 | 197      | 9.89%   |
| Goldstar             | 191      | 9.59%   |
| Hewlett-Packard      | 163      | 8.18%   |
| Acer                 | 138      | 6.93%   |
| AOC                  | 108      | 5.42%   |
| Philips              | 91       | 4.57%   |
| Ancor Communications | 79       | 3.97%   |
| BenQ                 | 71       | 3.56%   |
| LG Electronics       | 45       | 2.26%   |
| ViewSonic            | 43       | 2.16%   |
| Unknown              | 36       | 1.81%   |
| Lenovo               | 29       | 1.46%   |
| Sony                 | 26       | 1.31%   |
| Unknown              | 23       | 1.15%   |
| Iiyama               | 19       | 0.95%   |
| NEC Computers        | 17       | 0.85%   |
| Fujitsu Siemens      | 17       | 0.85%   |
| ASUSTek Computer     | 17       | 0.85%   |
| Vizio                | 16       | 0.8%    |
| Sceptre Tech         | 16       | 0.8%    |
| Toshiba              | 13       | 0.65%   |
| Eizo                 | 13       | 0.65%   |
| MSI                  | 11       | 0.55%   |
| HPN                  | 10       | 0.5%    |
| Idek Iiyama          | 9        | 0.45%   |
| HannStar             | 8        | 0.4%    |
| Gateway              | 8        | 0.4%    |
| FUS                  | 8        | 0.4%    |
| Envision             | 7        | 0.35%   |
| AUS                  | 7        | 0.35%   |
| Sharp                | 6        | 0.3%    |
| Panasonic            | 6        | 0.3%    |
| Microstep            | 6        | 0.3%    |
| Medion               | 6        | 0.3%    |
| Vestel               | 5        | 0.25%   |
| Pixio                | 5        | 0.25%   |
| MStar                | 5        | 0.25%   |
| KTC                  | 5        | 0.25%   |
| Insignia             | 5        | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Unknown                                                               | 23       | 1.09%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 9        | 0.43%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 9        | 0.43%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 8        | 0.38%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                      | 7        | 0.33%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 6        | 0.28%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 6        | 0.28%   |
| Philips LCD Monitor FTV 1920x1080                                     | 6        | 0.28%   |
| Hewlett-Packard 2009 HWP2827 1600x900 442x249mm 20.0-inch             | 6        | 0.28%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                 | 5        | 0.24%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch      | 5        | 0.24%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 5        | 0.24%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 4        | 0.19%   |
| Unknown (XXX) Beyond TV XXX2851 1920x1080 1209x680mm 54.6-inch        | 4        | 0.19%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch | 4        | 0.19%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 4        | 0.19%   |
| Philips PHL 242M8 PHLC253 1920x1080 527x296mm 23.8-inch               | 4        | 0.19%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 4        | 0.19%   |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                      | 4        | 0.19%   |
| Hewlett-Packard 24f HPN3546 1920x1080 527x296mm 23.8-inch             | 4        | 0.19%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 4        | 0.19%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                   | 4        | 0.19%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 4        | 0.19%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch             | 4        | 0.19%   |
| Dell SE198WFP DELF003 1440x900 408x255mm 18.9-inch                    | 4        | 0.19%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 4        | 0.19%   |
| BenQ GL2450H BNQ78A7 1920x1080 530x300mm 24.0-inch                    | 4        | 0.19%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 4        | 0.19%   |
| Vizio M220VA VIZ0070 1920x1080 476x268mm 21.5-inch                    | 3        | 0.14%   |
| Vestel LCD Monitor 48UHD_LCD_TV 3840x2160                             | 3        | 0.14%   |
| Unknown LCD Monitor SAMSUNG                                           | 3        | 0.14%   |
| Toshiba TV TSB0206 1920x1080 890x500mm 40.2-inch                      | 3        | 0.14%   |
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch              | 3        | 0.14%   |
| Samsung Electronics U28D590 SAM0B81 3840x2160 608x345mm 27.5-inch     | 3        | 0.14%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 470x300mm 22.0-inch  | 3        | 0.14%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 3        | 0.14%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                  | 3        | 0.14%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                  | 3        | 0.14%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch | 3        | 0.14%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 3        | 0.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 809      | 41.07%  |
| 1280x1024 (SXGA)   | 155      | 7.87%   |
| 3840x2160 (4K)     | 141      | 7.16%   |
| 1680x1050 (WSXGA+) | 119      | 6.04%   |
| 1366x768 (WXGA)    | 102      | 5.18%   |
| 1600x900 (HD+)     | 92       | 4.67%   |
| 1440x900 (WXGA+)   | 85       | 4.31%   |
| 2560x1440 (QHD)    | 77       | 3.91%   |
| Unknown            | 76       | 3.86%   |
| 1360x768           | 55       | 2.79%   |
| 1920x1200 (WUXGA)  | 41       | 2.08%   |
| 3440x1440          | 37       | 1.88%   |
| 3840x1080          | 36       | 1.83%   |
| 2560x1080          | 22       | 1.12%   |
| 1920x540           | 17       | 0.86%   |
| 1024x768 (XGA)     | 17       | 0.86%   |
| 1600x1200          | 9        | 0.46%   |
| 5760x1080          | 6        | 0.3%    |
| 1280x720 (HD)      | 6        | 0.3%    |
| 4480x1440          | 4        | 0.2%    |
| 3840x1600          | 4        | 0.2%    |
| 5760x2160          | 3        | 0.15%   |
| 3600x1080          | 3        | 0.15%   |
| 2560x1600          | 3        | 0.15%   |
| 1152x864           | 3        | 0.15%   |
| 6400x1440          | 2        | 0.1%    |
| 5440x1080          | 2        | 0.1%    |
| 5120x1440          | 2        | 0.1%    |
| 4480x1080          | 2        | 0.1%    |
| 3360x1080          | 2        | 0.1%    |
| 3200x1200          | 2        | 0.1%    |
| 3200x1080          | 2        | 0.1%    |
| 3120x1050          | 2        | 0.1%    |
| 2944x1080          | 2        | 0.1%    |
| 2720x1024          | 2        | 0.1%    |
| 2048x1152          | 2        | 0.1%    |
| 1280x960           | 2        | 0.1%    |
| 7680x2160          | 1        | 0.05%   |
| 7680x1080          | 1        | 0.05%   |
| 6880x1440          | 1        | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 373      | 19.06%  |
| 23      | 174      | 8.89%   |
| 24      | 173      | 8.84%   |
| 21      | 172      | 8.79%   |
| 27      | 169      | 8.64%   |
| 19      | 148      | 7.56%   |
| 20      | 107      | 5.47%   |
| 18      | 104      | 5.31%   |
| 31      | 78       | 3.99%   |
| 22      | 77       | 3.93%   |
| 17      | 74       | 3.78%   |
| 34      | 42       | 2.15%   |
| 15      | 36       | 1.84%   |
| 40      | 30       | 1.53%   |
| 72      | 21       | 1.07%   |
| 84      | 19       | 0.97%   |
| 54      | 19       | 0.97%   |
| 32      | 17       | 0.87%   |
| 26      | 15       | 0.77%   |
| 65      | 9        | 0.46%   |
| 52      | 8        | 0.41%   |
| 48      | 7        | 0.36%   |
| 36      | 7        | 0.36%   |
| 25      | 7        | 0.36%   |
| 49      | 6        | 0.31%   |
| 42      | 6        | 0.31%   |
| 28      | 6        | 0.31%   |
| 46      | 5        | 0.26%   |
| 33      | 4        | 0.2%    |
| 74      | 3        | 0.15%   |
| 39      | 3        | 0.15%   |
| 37      | 3        | 0.15%   |
| 35      | 3        | 0.15%   |
| 29      | 3        | 0.15%   |
| 60      | 2        | 0.1%    |
| 58      | 2        | 0.1%    |
| 57      | 2        | 0.1%    |
| 55      | 2        | 0.1%    |
| 47      | 2        | 0.1%    |
| 41      | 2        | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 520      | 27.33%  |
| 501-600        | 480      | 25.22%  |
| Unknown        | 373      | 19.6%   |
| 301-350        | 109      | 5.73%   |
| 601-700        | 106      | 5.57%   |
| 351-400        | 81       | 4.26%   |
| 701-800        | 70       | 3.68%   |
| 1001-1500      | 65       | 3.42%   |
| 1501-2000      | 46       | 2.42%   |
| 801-900        | 39       | 2.05%   |
| 901-1000       | 10       | 0.53%   |
| 201-300        | 3        | 0.16%   |
| More than 2000 | 1        | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 1012     | 55.12%  |
| Unknown | 340      | 18.52%  |
| 16/10   | 233      | 12.69%  |
| 5/4     | 138      | 7.52%   |
| 21/9    | 51       | 2.78%   |
| 4/3     | 34       | 1.85%   |
| 32/9    | 14       | 0.76%   |
| 6/5     | 7        | 0.38%   |
| 3/2     | 5        | 0.27%   |
| 2.00    | 1        | 0.05%   |
| 1.00    | 1        | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 477      | 24.77%  |
| Unknown        | 373      | 19.37%  |
| 151-200        | 323      | 16.77%  |
| 301-350        | 172      | 8.93%   |
| 351-500        | 149      | 7.74%   |
| 141-150        | 148      | 7.68%   |
| More than 1000 | 94       | 4.88%   |
| 251-300        | 73       | 3.79%   |
| 501-1000       | 69       | 3.58%   |
| 101-110        | 28       | 1.45%   |
| 111-120        | 7        | 0.36%   |
| 131-140        | 6        | 0.31%   |
| 91-100         | 3        | 0.16%   |
| 81-90          | 2        | 0.1%    |
| 71-80          | 1        | 0.05%   |
| 121-130        | 1        | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 1066     | 57.72%  |
| Unknown | 373      | 20.19%  |
| 101-120 | 256      | 13.86%  |
| 1-50    | 97       | 5.25%   |
| 121-160 | 38       | 2.06%   |
| 161-240 | 17       | 0.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1681     | 80.01%  |
| 2     | 235      | 11.19%  |
| 0     | 155      | 7.38%   |
| 3     | 26       | 1.24%   |
| 4     | 4        | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 1265     | 41.31%  |
| Intel                                 | 762      | 24.89%  |
| Qualcomm Atheros                      | 191      | 6.24%   |
| Ralink Technology                     | 116      | 3.79%   |
| Broadcom                              | 114      | 3.72%   |
| Nvidia                                | 79       | 2.58%   |
| TP-Link                               | 69       | 2.25%   |
| Ralink                                | 46       | 1.5%    |
| Broadcom Limited                      | 37       | 1.21%   |
| MediaTek                              | 36       | 1.18%   |
| Marvell Technology Group              | 27       | 0.88%   |
| NetGear                               | 25       | 0.82%   |
| D-Link                                | 25       | 0.82%   |
| Samsung Electronics                   | 23       | 0.75%   |
| D-Link System                         | 22       | 0.72%   |
| VIA Technologies                      | 21       | 0.69%   |
| Xiaomi                                | 17       | 0.56%   |
| Qualcomm Atheros Communications       | 14       | 0.46%   |
| Microsoft                             | 14       | 0.46%   |
| Huawei Technologies                   | 13       | 0.42%   |
| ASIX Electronics                      | 11       | 0.36%   |
| Edimax Technology                     | 10       | 0.33%   |
| ASUSTek Computer                      | 10       | 0.33%   |
| Aquantia                              | 9        | 0.29%   |
| Belkin Components                     | 8        | 0.26%   |
| OPPO Electronics                      | 6        | 0.2%    |
| Linksys                               | 6        | 0.2%    |
| Silicon Integrated Systems [SiS]      | 5        | 0.16%   |
| DisplayLink                           | 5        | 0.16%   |
| Qualcomm                              | 4        | 0.13%   |
| Motorola PCS                          | 4        | 0.13%   |
| Gemtek                                | 4        | 0.13%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4        | 0.13%   |
| Sundance Technology Inc / IC Plus     | 3        | 0.1%    |
| Sitecom Europe                        | 3        | 0.1%    |
| Motorola                              | 3        | 0.1%    |
| JMicron Technology                    | 3        | 0.1%    |
| Apple                                 | 3        | 0.1%    |
| ZyDAS                                 | 2        | 0.07%   |
| ZTE WCDMA Technologies MSM            | 2        | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 935      | 27.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 103      | 3%      |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 90       | 2.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 81       | 2.36%   |
| Intel I211 Gigabit Network Connection                             | 73       | 2.13%   |
| Intel Ethernet Connection I217-LM                                 | 69       | 2.01%   |
| Intel Wi-Fi 6 AX200                                               | 66       | 1.92%   |
| Ralink MT7601U Wireless Adapter                                   | 51       | 1.48%   |
| Intel Ethernet Connection (2) I219-V                              | 50       | 1.46%   |
| Nvidia MCP61 Ethernet                                             | 49       | 1.43%   |
| Realtek 802.11ac NIC                                              | 41       | 1.19%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 40       | 1.16%   |
| Intel Ethernet Controller I225-V                                  | 39       | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 33       | 0.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 32       | 0.93%   |
| Intel Ethernet Connection I217-V                                  | 30       | 0.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 28       | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 28       | 0.82%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 26       | 0.76%   |
| Intel 82579V Gigabit Network Connection                           | 24       | 0.7%    |
| Intel Ethernet Connection (2) I218-V                              | 22       | 0.64%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 21       | 0.61%   |
| Intel Wireless-AC 9260                                            | 21       | 0.61%   |
| Intel Wireless 7265                                               | 21       | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 20       | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                             | 20       | 0.58%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 19       | 0.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 19       | 0.55%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 19       | 0.55%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 18       | 0.52%   |
| Ralink RT5370 Wireless Adapter                                    | 18       | 0.52%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter      | 18       | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 17       | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16       | 0.47%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 15       | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 15       | 0.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 15       | 0.44%   |
| Intel Wireless 7260                                               | 15       | 0.44%   |
| Intel 82574L Gigabit Network Connection                           | 15       | 0.44%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 14       | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 305      | 26.66%  |
| Intel                                 | 270      | 23.6%   |
| Ralink Technology                     | 116      | 10.14%  |
| Qualcomm Atheros                      | 96       | 8.39%   |
| TP-Link                               | 66       | 5.77%   |
| Ralink                                | 46       | 4.02%   |
| Broadcom                              | 46       | 4.02%   |
| MediaTek                              | 28       | 2.45%   |
| NetGear                               | 25       | 2.19%   |
| D-Link                                | 25       | 2.19%   |
| D-Link System                         | 18       | 1.57%   |
| Qualcomm Atheros Communications       | 14       | 1.22%   |
| Microsoft                             | 14       | 1.22%   |
| Broadcom Limited                      | 11       | 0.96%   |
| Edimax Technology                     | 9        | 0.79%   |
| Belkin Components                     | 8        | 0.7%    |
| ASUSTek Computer                      | 8        | 0.7%    |
| Linksys                               | 6        | 0.52%   |
| Marvell Technology Group              | 4        | 0.35%   |
| Gemtek                                | 4        | 0.35%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4        | 0.35%   |
| Sitecom Europe                        | 3        | 0.26%   |
| ZyDAS                                 | 2        | 0.17%   |
| TRENDnet                              | 2        | 0.17%   |
| Senao                                 | 2        | 0.17%   |
| Philips (or NXP)                      | 2        | 0.17%   |
| Micro Star International              | 2        | 0.17%   |
| AVM                                   | 2        | 0.17%   |
| ZyXEL Communications                  | 1        | 0.09%   |
| Xiaomi                                | 1        | 0.09%   |
| Panasonic (Matsushita)                | 1        | 0.09%   |
| Ovislink                              | 1        | 0.09%   |
| IMC Networks                          | 1        | 0.09%   |
| ADMtek                                | 1        | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 66       | 5.7%    |
| Ralink MT7601U Wireless Adapter                                | 51       | 4.4%    |
| Realtek 802.11ac NIC                                           | 41       | 3.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 40       | 3.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 33       | 2.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 32       | 2.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 28       | 2.42%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 21       | 1.81%   |
| Intel Wireless-AC 9260                                         | 21       | 1.81%   |
| Intel Wireless 7265                                            | 21       | 1.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 20       | 1.73%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 19       | 1.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 19       | 1.64%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 18       | 1.55%   |
| Ralink RT5370 Wireless Adapter                                 | 18       | 1.55%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 18       | 1.55%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 15       | 1.3%    |
| Intel Wireless 7260                                            | 15       | 1.3%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 14       | 1.21%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 13       | 1.12%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 12       | 1.04%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 11       | 0.95%   |
| Qualcomm Atheros AR9271 802.11n                                | 11       | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11       | 0.95%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 11       | 0.95%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 11       | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 11       | 0.95%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 10       | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 10       | 0.86%   |
| Intel Wireless 8260                                            | 10       | 0.86%   |
| Intel Wireless 3165                                            | 10       | 0.86%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 9        | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 9        | 0.78%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 9        | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9        | 0.78%   |
| Microsoft Xbox 360 Wireless Adapter                            | 8        | 0.69%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 8        | 0.69%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 7        | 0.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7        | 0.6%    |
| Ralink RT2501/RT2573 Wireless Adapter                          | 7        | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1149     | 52.35%  |
| Intel                             | 607      | 27.65%  |
| Qualcomm Atheros                  | 100      | 4.56%   |
| Nvidia                            | 79       | 3.6%    |
| Broadcom                          | 69       | 3.14%   |
| Broadcom Limited                  | 27       | 1.23%   |
| Marvell Technology Group          | 23       | 1.05%   |
| VIA Technologies                  | 21       | 0.96%   |
| Xiaomi                            | 16       | 0.73%   |
| Samsung Electronics               | 15       | 0.68%   |
| Huawei Technologies               | 12       | 0.55%   |
| ASIX Electronics                  | 11       | 0.5%    |
| Aquantia                          | 9        | 0.41%   |
| MediaTek                          | 8        | 0.36%   |
| OPPO Electronics                  | 6        | 0.27%   |
| Silicon Integrated Systems [SiS]  | 5        | 0.23%   |
| DisplayLink                       | 5        | 0.23%   |
| Qualcomm                          | 4        | 0.18%   |
| D-Link System                     | 4        | 0.18%   |
| TP-Link                           | 3        | 0.14%   |
| Sundance Technology Inc / IC Plus | 3        | 0.14%   |
| JMicron Technology                | 3        | 0.14%   |
| Apple                             | 3        | 0.14%   |
| Motorola PCS                      | 2        | 0.09%   |
| ASUSTek Computer                  | 2        | 0.09%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.05%   |
| Research In Motion                | 1        | 0.05%   |
| ICS Advent                        | 1        | 0.05%   |
| HMD Global                        | 1        | 0.05%   |
| Google                            | 1        | 0.05%   |
| GCT Semiconductor                 | 1        | 0.05%   |
| Edimax Technology                 | 1        | 0.05%   |
| Accton Technology                 | 1        | 0.05%   |
| 3Com                              | 1        | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 935      | 41.76%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 103      | 4.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 90       | 4.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 81       | 3.62%   |
| Intel I211 Gigabit Network Connection                             | 73       | 3.26%   |
| Intel Ethernet Connection I217-LM                                 | 69       | 3.08%   |
| Intel Ethernet Connection (2) I219-V                              | 50       | 2.23%   |
| Nvidia MCP61 Ethernet                                             | 49       | 2.19%   |
| Intel Ethernet Controller I225-V                                  | 39       | 1.74%   |
| Intel Ethernet Connection I217-V                                  | 30       | 1.34%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 28       | 1.25%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 26       | 1.16%   |
| Intel 82579V Gigabit Network Connection                           | 24       | 1.07%   |
| Intel Ethernet Connection (2) I218-V                              | 22       | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                             | 20       | 0.89%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 19       | 0.85%   |
| Intel Ethernet Connection (7) I219-V                              | 17       | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16       | 0.71%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 15       | 0.67%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 15       | 0.67%   |
| Intel 82574L Gigabit Network Connection                           | 15       | 0.67%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 13       | 0.58%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 13       | 0.58%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 12       | 0.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 12       | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 11       | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11       | 0.49%   |
| Nvidia MCP73 Ethernet                                             | 11       | 0.49%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 11       | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10       | 0.45%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 10       | 0.45%   |
| Intel 82578DM Gigabit Network Connection                          | 10       | 0.45%   |
| Intel 82578DC Gigabit Network Connection                          | 10       | 0.45%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 9        | 0.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8        | 0.36%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8        | 0.36%   |
| Intel Ethernet Connection (12) I219-V                             | 8        | 0.36%   |
| Huawei MAR-LX1M                                                   | 8        | 0.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7        | 0.31%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7        | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2035     | 65.54%  |
| WiFi     | 1034     | 33.3%   |
| Modem    | 30       | 0.97%   |
| Unknown  | 6        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 1517     | 70.59%  |
| WiFi     | 627      | 29.18%  |
| Modem    | 3        | 0.14%   |
| Unknown  | 2        | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 1383     | 66.65%  |
| 2     | 606      | 29.2%   |
| 3     | 64       | 3.08%   |
| 0     | 16       | 0.77%   |
| 5     | 3        | 0.14%   |
| 4     | 2        | 0.1%    |
| 7     | 1        | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 1539     | 73.67%  |
| Yes  | 550      | 26.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 227      | 35.69%  |
| Cambridge Silicon Radio         | 138      | 21.7%   |
| Realtek Semiconductor           | 76       | 11.95%  |
| Broadcom                        | 42       | 6.6%    |
| ASUSTek Computer                | 27       | 4.25%   |
| Qualcomm Atheros Communications | 23       | 3.62%   |
| IMC Networks                    | 19       | 2.99%   |
| MediaTek                        | 13       | 2.04%   |
| Apple                           | 11       | 1.73%   |
| TP-Link                         | 9        | 1.42%   |
| Dynex                           | 7        | 1.1%    |
| Integrated System Solution      | 5        | 0.79%   |
| Belkin Components               | 5        | 0.79%   |
| Micro Star International        | 4        | 0.63%   |
| Foxconn / Hon Hai               | 4        | 0.63%   |
| Actions                         | 4        | 0.63%   |
| Realtek                         | 3        | 0.47%   |
| Lite-On Technology              | 3        | 0.47%   |
| Unknown                         | 3        | 0.47%   |
| Logitech                        | 2        | 0.31%   |
| Dell                            | 2        | 0.31%   |
| Sitecom Europe                  | 1        | 0.16%   |
| Ralink                          | 1        | 0.16%   |
| National Semiconductor          | 1        | 0.16%   |
| Mobile Action Technology        | 1        | 0.16%   |
| Marvell Semiconductor           | 1        | 0.16%   |
| Hewlett-Packard                 | 1        | 0.16%   |
| Fujitsu                         | 1        | 0.16%   |
| Edimax Technology               | 1        | 0.16%   |
| D-Link System                   | 1        | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 138      | 21.7%   |
| Realtek Bluetooth Radio                                  | 59       | 9.28%   |
| Intel Bluetooth wireless interface                       | 53       | 8.33%   |
| Intel AX200 Bluetooth                                    | 52       | 8.18%   |
| Intel AX210 Bluetooth                                    | 28       | 4.4%    |
| Intel Wireless-AC 3168 Bluetooth                         | 27       | 4.25%   |
| Intel Bluetooth Device                                   | 24       | 3.77%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 22       | 3.46%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 16       | 2.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 14       | 2.2%    |
| MediaTek Wireless_Device                                 | 13       | 2.04%   |
| IMC Networks Bluetooth Radio                             | 13       | 2.04%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 12       | 1.89%   |
| TP-Link UB500 Adapter                                    | 9        | 1.42%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 7        | 1.1%    |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 7        | 1.1%    |
| Realtek  Bluetooth 4.2 Adapter                           | 6        | 0.94%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 6        | 0.94%   |
| ASUS Bluetooth Radio                                     | 6        | 0.94%   |
| Apple Bluetooth USB Host Controller                      | 6        | 0.94%   |
| Realtek RTL8821A Bluetooth                               | 5        | 0.79%   |
| Realtek Bluetooth 5.1 Radio                              | 5        | 0.79%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 5        | 0.79%   |
| ASUS Bluetooth Device                                    | 5        | 0.79%   |
| Qualcomm Atheros  Bluetooth Device                       | 4        | 0.63%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter    | 4        | 0.63%   |
| Actions general adapter                                  | 4        | 0.63%   |
| Realtek Bluetooth Radio                                  | 3        | 0.47%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 3        | 0.47%   |
| Micro Star International Bluetooth Device                | 3        | 0.47%   |
| Lite-On Bluetooth Device                                 | 3        | 0.47%   |
| Integrated System Solution Bluetooth Device              | 3        | 0.47%   |
| IMC Networks Wireless_Device                             | 3        | 0.47%   |
| Foxconn / Hon Hai Wireless_Device                        | 3        | 0.47%   |
| Broadcom HP Portable Bumble Bee                          | 3        | 0.47%   |
| Broadcom Bluetooth 2.0+eDR dongle                        | 3        | 0.47%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter         | 3        | 0.47%   |
| Broadcom BCM43142A0 Bluetooth 4.0                        | 3        | 0.47%   |
| ASUS Qualcomm Bluetooth 4.1                              | 3        | 0.47%   |
| Unknown                                                  | 3        | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 1312     | 39.75%  |
| AMD                                          | 837      | 25.36%  |
| Nvidia                                       | 735      | 22.27%  |
| C-Media Electronics                          | 83       | 2.51%   |
| Creative Labs                                | 41       | 1.24%   |
| VIA Technologies                             | 25       | 0.76%   |
| Logitech                                     | 24       | 0.73%   |
| JMTek                                        | 18       | 0.55%   |
| Generalplus Technology                       | 16       | 0.48%   |
| ASUSTek Computer                             | 16       | 0.48%   |
| Kingston Technology                          | 15       | 0.45%   |
| Texas Instruments                            | 10       | 0.3%    |
| Razer USA                                    | 9        | 0.27%   |
| Plantronics                                  | 9        | 0.27%   |
| GN Netcom                                    | 9        | 0.27%   |
| Creative Technology                          | 8        | 0.24%   |
| Micro Star International                     | 7        | 0.21%   |
| Tenx Technology                              | 6        | 0.18%   |
| Silicon Integrated Systems [SiS]             | 6        | 0.18%   |
| Realtek Semiconductor                        | 5        | 0.15%   |
| Zoran Co. Personal Media Division (Nogatech) | 4        | 0.12%   |
| KTMicro                                      | 4        | 0.12%   |
| Focusrite-Novation                           | 4        | 0.12%   |
| BR23                                         | 4        | 0.12%   |
| Thesycon Systemsoftware & Consulting         | 3        | 0.09%   |
| SteelSeries ApS                              | 3        | 0.09%   |
| RODE Microphones                             | 3        | 0.09%   |
| Corsair                                      | 3        | 0.09%   |
| Astro Gaming                                 | 3        | 0.09%   |
| Asahi Kasei Microsystems                     | 3        | 0.09%   |
| Yamaha                                       | 2        | 0.06%   |
| Turtle Beach                                 | 2        | 0.06%   |
| Sennheiser Communications                    | 2        | 0.06%   |
| Samsung Electronics                          | 2        | 0.06%   |
| Microsoft                                    | 2        | 0.06%   |
| Micronas                                     | 2        | 0.06%   |
| Ensoniq                                      | 2        | 0.06%   |
| DigiTech                                     | 2        | 0.06%   |
| DCMT Technology                              | 2        | 0.06%   |
| Cambridge Audio                              | 2        | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 191      | 4.97%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 188      | 4.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 184      | 4.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 172      | 4.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 135      | 3.52%   |
| AMD Starship/Matisse HD Audio Controller                                          | 130      | 3.39%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 104      | 2.71%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 95       | 2.47%   |
| AMD Family 17h/19h HD Audio Controller                                            | 92       | 2.4%    |
| AMD FCH Azalia Controller                                                         | 86       | 2.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 77       | 2.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 76       | 1.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 75       | 1.95%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 60       | 1.56%   |
| Intel 200 Series PCH HD Audio                                                     | 59       | 1.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 58       | 1.51%   |
| Nvidia MCP61 High Definition Audio                                                | 51       | 1.33%   |
| Intel Cannon Lake PCH cAVS                                                        | 51       | 1.33%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 50       | 1.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 48       | 1.25%   |
| Nvidia High Definition Audio Controller                                           | 44       | 1.15%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 43       | 1.12%   |
| Nvidia GF108 High Definition Audio Controller                                     | 43       | 1.12%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 41       | 1.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 40       | 1.04%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 38       | 0.99%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 37       | 0.96%   |
| Nvidia TU116 High Definition Audio Controller                                     | 36       | 0.94%   |
| Nvidia GF119 HDMI Audio Controller                                                | 36       | 0.94%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 33       | 0.86%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 33       | 0.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 30       | 0.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 29       | 0.76%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 28       | 0.73%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 27       | 0.7%    |
| AMD Navi 10 HDMI Audio                                                            | 27       | 0.7%    |
| Nvidia GP106 High Definition Audio Controller                                     | 25       | 0.65%   |
| Nvidia GP104 High Definition Audio Controller                                     | 25       | 0.65%   |
| AMD Kabini HDMI/DP Audio                                                          | 25       | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                                | 24       | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 69       | 20.72%  |
| Kingston            | 44       | 13.21%  |
| Samsung Electronics | 36       | 10.81%  |
| Corsair             | 33       | 9.91%   |
| SK hynix            | 27       | 8.11%   |
| G.Skill             | 27       | 8.11%   |
| Crucial             | 25       | 7.51%   |
| Micron Technology   | 16       | 4.8%    |
| Team                | 12       | 3.6%    |
| Elpida              | 6        | 1.8%    |
| Unknown             | 5        | 1.5%    |
| Ramaxel Technology  | 3        | 0.9%    |
| Patriot             | 3        | 0.9%    |
| Nanya Technology    | 3        | 0.9%    |
| A-DATA Technology   | 3        | 0.9%    |
| Wilk                | 2        | 0.6%    |
| Unifosa             | 2        | 0.6%    |
| Qimonda             | 2        | 0.6%    |
| Avant               | 2        | 0.6%    |
| Transcend           | 1        | 0.3%    |
| Timetec             | 1        | 0.3%    |
| SUPER KINGSTEK      | 1        | 0.3%    |
| Ramos Technology    | 1        | 0.3%    |
| PNY                 | 1        | 0.3%    |
| Patriot Memory      | 1        | 0.3%    |
| Goldkey             | 1        | 0.3%    |
| Golden Empire       | 1        | 0.3%    |
| F7852C80            | 1        | 0.3%    |
| CSX                 | 1        | 0.3%    |
| ASint Technology    | 1        | 0.3%    |
| Apacer              | 1        | 0.3%    |
| AMD                 | 1        | 0.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s           | 7        | 1.94%   |
| Unknown                                                | 5        | 1.39%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 4        | 1.11%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 4        | 1.11%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 3        | 0.83%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3733MT/s     | 3        | 0.83%   |
| Team RAM TEAMGROUP-UD4-2666 8192MB DIMM DDR4 3000MT/s  | 3        | 0.83%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s   | 3        | 0.83%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 3        | 0.83%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s   | 3        | 0.83%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 3        | 0.83%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s  | 3        | 0.83%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s           | 2        | 0.55%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 2        | 0.55%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s           | 2        | 0.55%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                 | 2        | 0.55%   |
| Unknown RAM Module 4096MB DIMM                         | 2        | 0.55%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 2        | 0.55%   |
| Unknown RAM Module 2GB DIMM 667MT/s                    | 2        | 0.55%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 2        | 0.55%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 2        | 0.55%   |
| Unknown RAM Module 1GB DIMM DDR2                       | 2        | 0.55%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 2        | 0.55%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s            | 2        | 0.55%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                 | 2        | 0.55%   |
| Unknown RAM Module 1024MB DIMM                         | 2        | 0.55%   |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 2933MT/s     | 2        | 0.55%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s     | 2        | 0.55%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 2        | 0.55%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 2        | 0.55%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 2        | 0.55%   |
| Samsung RAM M378B5273DH0-CH9 4096MB DIMM DDR2 2133MT/s | 2        | 0.55%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s    | 2        | 0.55%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s    | 2        | 0.55%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 2        | 0.55%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 2        | 0.55%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s    | 2        | 0.55%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s  | 2        | 0.55%   |
| Kingston RAM KCM633-ELC 1024MB DIMM DDR2 2048MT/s      | 2        | 0.55%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s  | 2        | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 108      | 36.61%  |
| DDR3    | 104      | 35.25%  |
| Unknown | 31       | 10.51%  |
| DDR2    | 21       | 7.12%   |
| SDRAM   | 19       | 6.44%   |
| DDR5    | 6        | 2.03%   |
| DDR     | 4        | 1.36%   |
| LPDDR4  | 2        | 0.68%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 270      | 94.08%  |
| SODIMM       | 14       | 4.88%   |
| Row Of Chips | 2        | 0.7%    |
| FB-DIMM      | 1        | 0.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 110      | 34.06%  |
| 4096  | 85       | 26.32%  |
| 2048  | 50       | 15.48%  |
| 16384 | 31       | 9.6%    |
| 1024  | 27       | 8.36%   |
| 32768 | 18       | 5.57%   |
| 512   | 2        | 0.62%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 55       | 17.19%  |
| 1333    | 45       | 14.06%  |
| 3200    | 26       | 8.13%   |
| 3600    | 21       | 6.56%   |
| 800     | 17       | 5.31%   |
| Unknown | 15       | 4.69%   |
| 2667    | 10       | 3.13%   |
| 2133    | 10       | 3.13%   |
| 2400    | 9        | 2.81%   |
| 667     | 9        | 2.81%   |
| 3733    | 8        | 2.5%    |
| 1866    | 8        | 2.5%    |
| 3000    | 7        | 2.19%   |
| 1800    | 7        | 2.19%   |
| 4800    | 5        | 1.56%   |
| 2933    | 4        | 1.25%   |
| 2666    | 4        | 1.25%   |
| 1867    | 4        | 1.25%   |
| 1066    | 4        | 1.25%   |
| 400     | 4        | 1.25%   |
| 333     | 4        | 1.25%   |
| 3866    | 3        | 0.94%   |
| 3800    | 3        | 0.94%   |
| 2800    | 3        | 0.94%   |
| 3666    | 2        | 0.63%   |
| 3500    | 2        | 0.63%   |
| 3466    | 2        | 0.63%   |
| 3400    | 2        | 0.63%   |
| 2048    | 2        | 0.63%   |
| 49926   | 1        | 0.31%   |
| 7000    | 1        | 0.31%   |
| 6000    | 1        | 0.31%   |
| 5354    | 1        | 0.31%   |
| 5200    | 1        | 0.31%   |
| 4400    | 1        | 0.31%   |
| 4266    | 1        | 0.31%   |
| 4000    | 1        | 0.31%   |
| 3933    | 1        | 0.31%   |
| 3534    | 1        | 0.31%   |
| 3533    | 1        | 0.31%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 35       | 28.23%  |
| Canon                 | 28       | 22.58%  |
| Brother Industries    | 22       | 17.74%  |
| Seiko Epson           | 15       | 12.1%   |
| Samsung Electronics   | 13       | 10.48%  |
| Lexmark International | 3        | 2.42%   |
| Ricoh                 | 2        | 1.61%   |
| Toshiba TEC           | 1        | 0.81%   |
| STMicroelectronics    | 1        | 0.81%   |
| QinHeng Electronics   | 1        | 0.81%   |
| Pantum                | 1        | 0.81%   |
| Konica Minolta        | 1        | 0.81%   |
| GG IMAGE              | 1        | 0.81%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| HP ENVY 4520 series                                       | 3        | 2.42%   |
| Canon TS3100 series                                       | 3        | 2.42%   |
| Canon PIXMA MG2500 Series                                 | 3        | 2.42%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 2        | 1.61%   |
| Seiko Epson L3110 Series                                  | 2        | 1.61%   |
| Samsung ML-216x Series Laser Printer                      | 2        | 1.61%   |
| Samsung M2070 Series                                      | 2        | 1.61%   |
| Samsung C460 Series                                       | 2        | 1.61%   |
| HP OfficeJet 6950                                         | 2        | 1.61%   |
| HP LaserJet Professional P1102w                           | 2        | 1.61%   |
| HP ENVY 5000 series                                       | 2        | 1.61%   |
| HP DeskJet 2700 series                                    | 2        | 1.61%   |
| HP DeskJet 2130 series                                    | 2        | 1.61%   |
| Canon PIXMA MG3600 Series                                 | 2        | 1.61%   |
| Canon MF4010 series                                       | 2        | 1.61%   |
| Canon LiDE 400                                            | 2        | 1.61%   |
| Brother HL-L2350DW series                                 | 2        | 1.61%   |
| Brother HL-52x0 series                                    | 2        | 1.61%   |
| Brother HL-2130 series                                    | 2        | 1.61%   |
| Toshiba TEC e-STD120 USB                                  | 1        | 0.81%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.81%   |
| Seiko Epson XP-7100 Series                                | 1        | 0.81%   |
| Seiko Epson XP-225 Series                                 | 1        | 0.81%   |
| Seiko Epson XP-200 Series                                 | 1        | 0.81%   |
| Seiko Epson L805 Series                                   | 1        | 0.81%   |
| Seiko Epson L6270 Series                                  | 1        | 0.81%   |
| Seiko Epson L365 Series                                   | 1        | 0.81%   |
| Seiko Epson L360 Series                                   | 1        | 0.81%   |
| Seiko Epson L355 Series                                   | 1        | 0.81%   |
| Seiko Epson L3150 Series                                  | 1        | 0.81%   |
| Seiko Epson L120 Series                                   | 1        | 0.81%   |
| Seiko Epson ET-2820 Series                                | 1        | 0.81%   |
| Samsung SCX-483x 5x3x Series                              | 1        | 0.81%   |
| Samsung SCX-4623 Series                                   | 1        | 0.81%   |
| Samsung SCX-4200 series                                   | 1        | 0.81%   |
| Samsung SCX-3400 Series                                   | 1        | 0.81%   |
| Samsung ML-2950 Series                                    | 1        | 0.81%   |
| Samsung ML-2010P Mono Laser Printer                       | 1        | 0.81%   |
| Samsung CLX-3300 Series                                   | 1        | 0.81%   |
| Ricoh SP C250SF                                           | 1        | 0.81%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 14       | 77.78%  |
| Hewlett-Packard | 3        | 16.67%  |
| Seiko Epson     | 1        | 5.56%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20     | 3        | 15.79%  |
| Canon CanoScan LiDE 90                 | 2        | 10.53%  |
| Canon CanoScan LiDE 220                | 2        | 10.53%  |
| Canon CanoScan LiDE 100                | 2        | 10.53%  |
| Seiko Epson Scanner                    | 1        | 5.26%   |
| HP ScanJet 2400c                       | 1        | 5.26%   |
| HP Scanjet 200                         | 1        | 5.26%   |
| HP PSC 1200                            | 1        | 5.26%   |
| Canon CanoScan LiDE 60                 | 1        | 5.26%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1        | 5.26%   |
| Canon CanoScan LIDE 25                 | 1        | 5.26%   |
| Canon CanoScan LiDE 110                | 1        | 5.26%   |
| Canon CanoScan D660U                   | 1        | 5.26%   |
| Canon CanoScan 8800F                   | 1        | 5.26%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 80       | 26.58%  |
| Microdia                      | 28       | 9.3%    |
| Microsoft                     | 24       | 7.97%   |
| Apple                         | 16       | 5.32%   |
| Sunplus Innovation Technology | 14       | 4.65%   |
| Chicony Electronics           | 12       | 3.99%   |
| Samsung Electronics           | 11       | 3.65%   |
| Generalplus Technology        | 10       | 3.32%   |
| Z-Star Microelectronics       | 7        | 2.33%   |
| ARC International             | 7        | 2.33%   |
| Jieli Technology              | 6        | 1.99%   |
| Cubeternet                    | 6        | 1.99%   |
| GEMBIRD                       | 5        | 1.66%   |
| Realtek Semiconductor         | 4        | 1.33%   |
| Razer USA                     | 4        | 1.33%   |
| IMC Networks                  | 4        | 1.33%   |
| Creative Technology           | 4        | 1.33%   |
| Tobii Technology AB           | 3        | 1%      |
| Creality 3D Technology        | 3        | 1%      |
| Aveo Technology               | 3        | 1%      |
| Arkmicro Technologies         | 3        | 1%      |
| A4Tech                        | 3        | 1%      |
| Xiongmai                      | 2        | 0.66%   |
| WaveRider Communications      | 2        | 0.66%   |
| Trust                         | 2        | 0.66%   |
| Suyin                         | 2        | 0.66%   |
| Sonix Technology              | 2        | 0.66%   |
| Pixart Imaging                | 2        | 0.66%   |
| MacroSilicon                  | 2        | 0.66%   |
| lihappe8                      | 2        | 0.66%   |
| KYE Systems (Mouse Systems)   | 2        | 0.66%   |
| Guillemot                     | 2        | 0.66%   |
| Genesys Logic                 | 2        | 0.66%   |
| AVerMedia Technologies        | 2        | 0.66%   |
| Alcor Micro                   | 2        | 0.66%   |
| Xiaomi                        | 1        | 0.33%   |
| Unknown                       | 1        | 0.33%   |
| Teslong Camera                | 1        | 0.33%   |
| Sweex                         | 1        | 0.33%   |
| Sunplus Technology            | 1        | 0.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 22       | 7.26%   |
| Logitech HD Pro Webcam C920              | 14       | 4.62%   |
| Apple iPhone 5/5C/5S/6/SE                | 14       | 4.62%   |
| Microsoft LifeCam HD-3000                | 12       | 3.96%   |
| Samsung Galaxy series, misc. (MTP mode)  | 11       | 3.63%   |
| Microdia Webcam Vitade AF                | 7        | 2.31%   |
| ARC International Camera                 | 7        | 2.31%   |
| Sunplus Integrated_Webcam_HD             | 6        | 1.98%   |
| Microdia USB 2.0 Camera                  | 6        | 1.98%   |
| Jieli USB PHY 2.0                        | 6        | 1.98%   |
| Chicony HP High Definition 1MP Webcam    | 6        | 1.98%   |
| Logitech HD Webcam C615                  | 5        | 1.65%   |
| Logitech C920 PRO HD Webcam              | 5        | 1.65%   |
| Sunplus HD 720P webcam                   | 4        | 1.32%   |
| Razer USA Gaming Webcam [Kiyo]           | 4        | 1.32%   |
| Microdia USB Camera                      | 4        | 1.32%   |
| Logitech Webcam C925e                    | 4        | 1.32%   |
| Generalplus GENERAL WEBCAM               | 4        | 1.32%   |
| Generalplus 808 Camera #9 (web-cam mode) | 4        | 1.32%   |
| Z-Star Integrated Camera                 | 3        | 0.99%   |
| Tobii AB EyeChip                         | 3        | 0.99%   |
| Microsoft LifeCam VX-500 [1357]          | 3        | 0.99%   |
| Microdia Integrated Camera               | 3        | 0.99%   |
| Logitech Webcam C310                     | 3        | 0.99%   |
| Logitech HD Webcam C910                  | 3        | 0.99%   |
| Logitech C922 Pro Stream Webcam          | 3        | 0.99%   |
| Cubeternet GL-UPC822 UVC WebCam          | 3        | 0.99%   |
| Creality 3D CREALITY CAM                 | 3        | 0.99%   |
| Chicony CNF8050 Webcam                   | 3        | 0.99%   |
| Z-Star Venus USB2.0 Camera               | 2        | 0.66%   |
| Xiongmai web camera                      | 2        | 0.66%   |
| WaveRider USB Live camera                | 2        | 0.66%   |
| Suyin HD WebCam                          | 2        | 0.66%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro     | 2        | 0.66%   |
| Microsoft MicrosoftÂ LifeCam Cinema     | 2        | 0.66%   |
| Microsoft LifeCam VX-2000                | 2        | 0.66%   |
| Microsoft LifeCam HD-5000                | 2        | 0.66%   |
| Microdia USB Live camera                 | 2        | 0.66%   |
| Microdia Camera                          | 2        | 0.66%   |
| Logitech Webcam C250                     | 2        | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 3        | 75%     |
| AuthenTec             | 1        | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                     | Desktops | Percent |
|-------------------------------------------|----------|---------|
| LighTuning Fingerprint Sensor             | 2        | 50%     |
| LighTuning ES603 Swipe Fingerprint Sensor | 1        | 25%     |
| AuthenTec AES2501 Fingerprint Sensor      | 1        | 25%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 2        | 15.38%  |
| Alcor Micro                       | 2        | 15.38%  |
| Advanced Card Systems             | 2        | 15.38%  |
| VASCO Data Security International | 1        | 7.69%   |
| SCM Microsystems                  | 1        | 7.69%   |
| Reiner SCT Kartensysteme          | 1        | 7.69%   |
| Kobil Systems                     | 1        | 7.69%   |
| Jing-Mold Enterprise              | 1        | 7.69%   |
| Fujitsu Siemens Computers         | 1        | 7.69%   |
| Chicony Electronics               | 1        | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                 | 2        | 15.38%  |
| Alcor Micro AU9540 Smartcard Reader                               | 2        | 15.38%  |
| VASCO Data Security International Digipass 905 SmartCard Reader   | 1        | 7.69%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader            | 1        | 7.69%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                   | 1        | 7.69%   |
| Kobil Systems KOBIL Class 3 Reader                                | 1        | 7.69%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard | 1        | 7.69%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                     | 1        | 7.69%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard              | 1        | 7.69%   |
| Advanced Card Systems ACR39U                                      | 1        | 7.69%   |
| Advanced Card Systems ACR1281 1S Dual Reader                      | 1        | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 1653     | 78.71%  |
| 1     | 386      | 18.38%  |
| 2     | 51       | 2.43%   |
| 3     | 8        | 0.38%   |
| 4     | 2        | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 210      | 42.6%   |
| Net/wireless             | 165      | 33.47%  |
| Communication controller | 31       | 6.29%   |
| Multimedia controller    | 20       | 4.06%   |
| Unassigned class         | 15       | 3.04%   |
| Modem                    | 9        | 1.83%   |
| Chipcard                 | 9        | 1.83%   |
| Storage/raid             | 7        | 1.42%   |
| Sound                    | 5        | 1.01%   |
| Bluetooth                | 5        | 1.01%   |
| Fingerprint reader       | 4        | 0.81%   |
| Net/ethernet             | 3        | 0.61%   |
| Storage/ide              | 2        | 0.41%   |
| Network                  | 2        | 0.41%   |
| Camera                   | 2        | 0.41%   |
| Storage/nvme             | 1        | 0.2%    |
| Storage                  | 1        | 0.2%    |
| Dvb card                 | 1        | 0.2%    |
| Card reader              | 1        | 0.2%    |

