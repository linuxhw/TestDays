Linux in Germany - Tested Hardware & Statistics (Desktops)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Germany.

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

Total: 9931

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | P8H67                       | [31a7799a34](https://linux-hardware.org/?probe=31a7799a34) | Dec 01, 2022 |
| ASUSTek       | P7P55D                      | [0a012accfd](https://linux-hardware.org/?probe=0a012accfd) | Dec 01, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [ad24dc05a0](https://linux-hardware.org/?probe=ad24dc05a0) | Dec 01, 2022 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [0e38c9a3be](https://linux-hardware.org/?probe=0e38c9a3be) | Dec 01, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [475ad82d2b](https://linux-hardware.org/?probe=475ad82d2b) | Nov 30, 2022 |
| Medion        | MS-7748                     | [0e92aa55ca](https://linux-hardware.org/?probe=0e92aa55ca) | Nov 30, 2022 |
| Medion        | MS-7800                     | [a5658a6933](https://linux-hardware.org/?probe=a5658a6933) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | [dc5ec6eb84](https://linux-hardware.org/?probe=dc5ec6eb84) | Nov 30, 2022 |
| Dell          | 0M5DCD A00                  | [e9fae02409](https://linux-hardware.org/?probe=e9fae02409) | Nov 30, 2022 |
| ASRock        | 970 Extreme3                | [4951da34da](https://linux-hardware.org/?probe=4951da34da) | Nov 30, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [dd3801095f](https://linux-hardware.org/?probe=dd3801095f) | Nov 30, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [efecce0072](https://linux-hardware.org/?probe=efecce0072) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | [abcc431f9f](https://linux-hardware.org/?probe=abcc431f9f) | Nov 30, 2022 |
| ASUSTek       | PRIME X370-PRO              | [7f89d71e2e](https://linux-hardware.org/?probe=7f89d71e2e) | Nov 30, 2022 |
| ASRock        | N68-S3 UCC                  | [ede29d01f8](https://linux-hardware.org/?probe=ede29d01f8) | Nov 30, 2022 |
| Gigabyte      | 970A-DS3P                   | [22c7db0e68](https://linux-hardware.org/?probe=22c7db0e68) | Nov 30, 2022 |
| Gigabyte      | 970A-DS3P                   | [65493a981c](https://linux-hardware.org/?probe=65493a981c) | Nov 30, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [b38075cef4](https://linux-hardware.org/?probe=b38075cef4) | Nov 29, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [c01a10b89d](https://linux-hardware.org/?probe=c01a10b89d) | Nov 29, 2022 |
| HP            | 18E4                        | [39b839e527](https://linux-hardware.org/?probe=39b839e527) | Nov 29, 2022 |
| ASRock        | N68-S3 UCC                  | [fd6f368580](https://linux-hardware.org/?probe=fd6f368580) | Nov 29, 2022 |
| Dell          | 0M859N A00                  | [95cf7fe257](https://linux-hardware.org/?probe=95cf7fe257) | Nov 29, 2022 |
| ASRock        | 960GM-GS3 FX                | [1474b9ee78](https://linux-hardware.org/?probe=1474b9ee78) | Nov 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [472530d650](https://linux-hardware.org/?probe=472530d650) | Nov 29, 2022 |
| ASUSTek       | Q170T                       | [99abcc63ab](https://linux-hardware.org/?probe=99abcc63ab) | Nov 29, 2022 |
| Medion        | H110H4-EM2                  | [38b9e166f2](https://linux-hardware.org/?probe=38b9e166f2) | Nov 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [a73d36e579](https://linux-hardware.org/?probe=a73d36e579) | Nov 29, 2022 |
| MSI           | X570-A PRO                  | [92ddd925db](https://linux-hardware.org/?probe=92ddd925db) | Nov 28, 2022 |
| ASRock        | Q1900M                      | [0a90a5d3a5](https://linux-hardware.org/?probe=0a90a5d3a5) | Nov 28, 2022 |
| HP            | 18E5                        | [e336f0ac13](https://linux-hardware.org/?probe=e336f0ac13) | Nov 28, 2022 |
| MSI           | Z77A-G43                    | [207d763813](https://linux-hardware.org/?probe=207d763813) | Nov 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e3f55c7b9d](https://linux-hardware.org/?probe=e3f55c7b9d) | Nov 28, 2022 |
| Shuttle       | FS35V4                      | [46923496a3](https://linux-hardware.org/?probe=46923496a3) | Nov 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [54407c7caa](https://linux-hardware.org/?probe=54407c7caa) | Nov 28, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [b0078eda9b](https://linux-hardware.org/?probe=b0078eda9b) | Nov 27, 2022 |
| Acer          | Veriton X4620G V1.0         | [37be4a2bf8](https://linux-hardware.org/?probe=37be4a2bf8) | Nov 27, 2022 |
| Medion        | TJ4125                      | [a1c7ac96d3](https://linux-hardware.org/?probe=a1c7ac96d3) | Nov 27, 2022 |
| MSI           | X570-A PRO                  | [c2c27cf47f](https://linux-hardware.org/?probe=c2c27cf47f) | Nov 27, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a60076a8c2](https://linux-hardware.org/?probe=a60076a8c2) | Nov 27, 2022 |
| ASUSTek       | PRIME B365M-A               | [4f3216dfdc](https://linux-hardware.org/?probe=4f3216dfdc) | Nov 27, 2022 |
| ASUSTek       | PRIME B365M-A               | [498f0a31dc](https://linux-hardware.org/?probe=498f0a31dc) | Nov 27, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [bbf4464c41](https://linux-hardware.org/?probe=bbf4464c41) | Nov 27, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1deadcff69](https://linux-hardware.org/?probe=1deadcff69) | Nov 27, 2022 |
| HP            | 18E4                        | [11c1530767](https://linux-hardware.org/?probe=11c1530767) | Nov 26, 2022 |
| MSI           | 970 GAMING                  | [82a3d83d20](https://linux-hardware.org/?probe=82a3d83d20) | Nov 26, 2022 |
| ASUSTek       | Rampage IV EXTREME          | [e70ff25b31](https://linux-hardware.org/?probe=e70ff25b31) | Nov 26, 2022 |
| ASRock        | H61M-DGS R2.0               | [189b3c0ea0](https://linux-hardware.org/?probe=189b3c0ea0) | Nov 26, 2022 |
| ASUSTek       | PRIME A320M-K               | [be12141830](https://linux-hardware.org/?probe=be12141830) | Nov 26, 2022 |
| ASUSTek       | PRIME A320M-K               | [f34d75bde0](https://linux-hardware.org/?probe=f34d75bde0) | Nov 26, 2022 |
| MSI           | B550-A PRO                  | [8d0b06aa1d](https://linux-hardware.org/?probe=8d0b06aa1d) | Nov 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | [5b531b7b41](https://linux-hardware.org/?probe=5b531b7b41) | Nov 26, 2022 |
| Foxconn       | G41MXP/G41MXP-V             | [f8e0414c84](https://linux-hardware.org/?probe=f8e0414c84) | Nov 26, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [2a7b6d570f](https://linux-hardware.org/?probe=2a7b6d570f) | Nov 26, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [a787a49407](https://linux-hardware.org/?probe=a787a49407) | Nov 25, 2022 |
| ASUSTek       | P8B75-M LX                  | [8522486d64](https://linux-hardware.org/?probe=8522486d64) | Nov 25, 2022 |
| Gigabyte      | Z390 UD                     | [06e25ffa57](https://linux-hardware.org/?probe=06e25ffa57) | Nov 25, 2022 |
| Acer          | Veriton L6620G v1.0         | [33f168992e](https://linux-hardware.org/?probe=33f168992e) | Nov 25, 2022 |
| Gigabyte      | B75M-D3H                    | [d70a6e41ba](https://linux-hardware.org/?probe=d70a6e41ba) | Nov 24, 2022 |
| ASRock        | 960GM-GS3 FX                | [1af92d9936](https://linux-hardware.org/?probe=1af92d9936) | Nov 24, 2022 |
| HP            | 339A                        | [52f957ef60](https://linux-hardware.org/?probe=52f957ef60) | Nov 24, 2022 |
| Dell          | 0MN1TX A01                  | [7f0ba24aad](https://linux-hardware.org/?probe=7f0ba24aad) | Nov 24, 2022 |
| Gigabyte      | Z390 UD                     | [447045be5d](https://linux-hardware.org/?probe=447045be5d) | Nov 24, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [00f8658ee8](https://linux-hardware.org/?probe=00f8658ee8) | Nov 24, 2022 |
| ASRock        | FP6D4-P1                    | [5e52f1b520](https://linux-hardware.org/?probe=5e52f1b520) | Nov 24, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | [51f3e71650](https://linux-hardware.org/?probe=51f3e71650) | Nov 24, 2022 |
| Dell          | 0MN1TX A01                  | [8de6a24029](https://linux-hardware.org/?probe=8de6a24029) | Nov 24, 2022 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | [7265ce493e](https://linux-hardware.org/?probe=7265ce493e) | Nov 23, 2022 |
| Medion        | TJ4125                      | [84084e5cdc](https://linux-hardware.org/?probe=84084e5cdc) | Nov 23, 2022 |
| Medion        | TJ4125                      | [810477dfd9](https://linux-hardware.org/?probe=810477dfd9) | Nov 23, 2022 |
| HP            | 18E4                        | [8dd5fdb580](https://linux-hardware.org/?probe=8dd5fdb580) | Nov 23, 2022 |
| Dell          | 0NDYHG A01                  | [0e693ae457](https://linux-hardware.org/?probe=0e693ae457) | Nov 23, 2022 |
| Gigabyte      | X470 AORUS GAMING 5 WIFI... | [58b3db6784](https://linux-hardware.org/?probe=58b3db6784) | Nov 23, 2022 |
| ASRock        | Q1900B-ITX                  | [7239c46e95](https://linux-hardware.org/?probe=7239c46e95) | Nov 23, 2022 |
| ASUSTek       | PRIME B450M-K               | [2438420107](https://linux-hardware.org/?probe=2438420107) | Nov 22, 2022 |
| ASUSTek       | P8H61-I LX                  | [a537f96848](https://linux-hardware.org/?probe=a537f96848) | Nov 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [76ac354e17](https://linux-hardware.org/?probe=76ac354e17) | Nov 22, 2022 |
| ASUSTek       | Maximus IX HERO             | [587aa317bd](https://linux-hardware.org/?probe=587aa317bd) | Nov 22, 2022 |
| Gigabyte      | 970A-DS3P FX                | [d4d9cadf9f](https://linux-hardware.org/?probe=d4d9cadf9f) | Nov 22, 2022 |
| ASUSTek       | Pro WS C246-ACE             | [1a38780da8](https://linux-hardware.org/?probe=1a38780da8) | Nov 22, 2022 |
| Gigabyte      | A320M-S2H-CF                | [62048f37d6](https://linux-hardware.org/?probe=62048f37d6) | Nov 22, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | [ba7795ec44](https://linux-hardware.org/?probe=ba7795ec44) | Nov 22, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [f2a00a7bb3](https://linux-hardware.org/?probe=f2a00a7bb3) | Nov 21, 2022 |
| HP            | 3647h                       | [8f77a73e9b](https://linux-hardware.org/?probe=8f77a73e9b) | Nov 21, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | [89e6ad23e9](https://linux-hardware.org/?probe=89e6ad23e9) | Nov 21, 2022 |
| Intel         | SKYBAY                      | [7c0566f0ba](https://linux-hardware.org/?probe=7c0566f0ba) | Nov 21, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [f4e5d3bd1c](https://linux-hardware.org/?probe=f4e5d3bd1c) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX H470-I GAMING     | [8b8ac358e4](https://linux-hardware.org/?probe=8b8ac358e4) | Nov 21, 2022 |
| ASRock        | 960GM-VGS3 FX               | [c5ecd06a6f](https://linux-hardware.org/?probe=c5ecd06a6f) | Nov 21, 2022 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | [79403c8f5d](https://linux-hardware.org/?probe=79403c8f5d) | Nov 20, 2022 |
| MSI           | A320M-A PRO MAX             | [486c850cd6](https://linux-hardware.org/?probe=486c850cd6) | Nov 20, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | [41cca3d850](https://linux-hardware.org/?probe=41cca3d850) | Nov 20, 2022 |
| MSI           | X570-A PRO                  | [912f6ac7a3](https://linux-hardware.org/?probe=912f6ac7a3) | Nov 20, 2022 |
| Acer          | Aspire XC-780               | [bfc11805d9](https://linux-hardware.org/?probe=bfc11805d9) | Nov 20, 2022 |
| Acer          | Aspire XC-780               | [a992606b70](https://linux-hardware.org/?probe=a992606b70) | Nov 20, 2022 |
| ASUSTek       | PRIME Z590-A                | [ba2c2a39ed](https://linux-hardware.org/?probe=ba2c2a39ed) | Nov 20, 2022 |
| ASUSTek       | PRIME Z590-A                | [07985535f4](https://linux-hardware.org/?probe=07985535f4) | Nov 20, 2022 |
| Acer          | FX58M                       | [5e7abd5852](https://linux-hardware.org/?probe=5e7abd5852) | Nov 20, 2022 |
| Gigabyte      | B75M-D3H                    | [e5db58baec](https://linux-hardware.org/?probe=e5db58baec) | Nov 19, 2022 |
| Acer          | FX58M                       | [837da7d885](https://linux-hardware.org/?probe=837da7d885) | Nov 19, 2022 |
| ASUSTek       | X99-S                       | [b0bb31d7d9](https://linux-hardware.org/?probe=b0bb31d7d9) | Nov 19, 2022 |
| Gigabyte      | H81M-HD3                    | [d858d2656d](https://linux-hardware.org/?probe=d858d2656d) | Nov 19, 2022 |
| Acer          | Aspire TC-1760              | [a4f03aea9c](https://linux-hardware.org/?probe=a4f03aea9c) | Nov 19, 2022 |
| Intel         | DH55PJ AAE93812-303         | [bebe890c96](https://linux-hardware.org/?probe=bebe890c96) | Nov 19, 2022 |
| Unknown       | QNAP TS-221                 | [b9ff535a3f](https://linux-hardware.org/?probe=b9ff535a3f) | Nov 18, 2022 |
| Lenovo        | ThinkCentre M58 7373AJ5     | [ac213d4e52](https://linux-hardware.org/?probe=ac213d4e52) | Nov 18, 2022 |
| MSI           | X570-A PRO                  | [891ed6f2dc](https://linux-hardware.org/?probe=891ed6f2dc) | Nov 18, 2022 |
| MSI           | A75MA-P35                   | [10016f0246](https://linux-hardware.org/?probe=10016f0246) | Nov 17, 2022 |
| MSI           | H310M PRO-M2 PLUS           | [c5a1b3e5ae](https://linux-hardware.org/?probe=c5a1b3e5ae) | Nov 17, 2022 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [169294b358](https://linux-hardware.org/?probe=169294b358) | Nov 17, 2022 |
| HP            | 8169                        | [6dd9ea2ef0](https://linux-hardware.org/?probe=6dd9ea2ef0) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | [7f7b7354b8](https://linux-hardware.org/?probe=7f7b7354b8) | Nov 17, 2022 |
| MSI           | X79A-GD45                   | [42d08e1136](https://linux-hardware.org/?probe=42d08e1136) | Nov 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | [9f45de6ee3](https://linux-hardware.org/?probe=9f45de6ee3) | Nov 17, 2022 |
| MSI           | A75MA-G55                   | [b678f31b24](https://linux-hardware.org/?probe=b678f31b24) | Nov 16, 2022 |
| Medion        | MS-7728                     | [813d86814d](https://linux-hardware.org/?probe=813d86814d) | Nov 16, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [90662fa2e9](https://linux-hardware.org/?probe=90662fa2e9) | Nov 16, 2022 |
| MSI           | MEG X570 UNIFY              | [750d7eb0d7](https://linux-hardware.org/?probe=750d7eb0d7) | Nov 16, 2022 |
| ASRock        | N68-S3 UCC                  | [3f0f992387](https://linux-hardware.org/?probe=3f0f992387) | Nov 16, 2022 |
| ASRock        | FM2A68M-HD+                 | [e907b4c718](https://linux-hardware.org/?probe=e907b4c718) | Nov 15, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [4da8ff348a](https://linux-hardware.org/?probe=4da8ff348a) | Nov 15, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [ee8a80240d](https://linux-hardware.org/?probe=ee8a80240d) | Nov 15, 2022 |
| ASUSTek       | X79-DELUXE                  | [3005933159](https://linux-hardware.org/?probe=3005933159) | Nov 15, 2022 |
| Gigabyte      | B75M-D3H                    | [e7f0316884](https://linux-hardware.org/?probe=e7f0316884) | Nov 14, 2022 |
| ASUSTek       | PRIME X570-PRO              | [642a889fcc](https://linux-hardware.org/?probe=642a889fcc) | Nov 14, 2022 |
| ASUSTek       | PRIME A520M-A II            | [ff1f659f4e](https://linux-hardware.org/?probe=ff1f659f4e) | Nov 14, 2022 |
| ASUSTek       | PRIME A520M-A II            | [a316ed1e2c](https://linux-hardware.org/?probe=a316ed1e2c) | Nov 14, 2022 |
| ASRock        | 960GM-GS3 FX                | [b47205075c](https://linux-hardware.org/?probe=b47205075c) | Nov 14, 2022 |
| Intel         | H81                         | [738056c2ab](https://linux-hardware.org/?probe=738056c2ab) | Nov 14, 2022 |
| Dell          | 0C27VV A01                  | [5e87654e7a](https://linux-hardware.org/?probe=5e87654e7a) | Nov 14, 2022 |
| MSI           | B450 GAMING PLUS            | [2964de32f4](https://linux-hardware.org/?probe=2964de32f4) | Nov 13, 2022 |
| Gigabyte      | Z390 M-CF                   | [047686dabd](https://linux-hardware.org/?probe=047686dabd) | Nov 13, 2022 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [f18af41d42](https://linux-hardware.org/?probe=f18af41d42) | Nov 13, 2022 |
| Unknown       | Unknown                     | [b89a0c7341](https://linux-hardware.org/?probe=b89a0c7341) | Nov 13, 2022 |
| Dell          | 04YP6J A02                  | [5ca546d877](https://linux-hardware.org/?probe=5ca546d877) | Nov 13, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | [4e3e53f7bb](https://linux-hardware.org/?probe=4e3e53f7bb) | Nov 12, 2022 |
| Gigabyte      | H87-HD3                     | [e5a8d4700d](https://linux-hardware.org/?probe=e5a8d4700d) | Nov 12, 2022 |
| ASRock        | X300M-STX                   | [6b2e935e07](https://linux-hardware.org/?probe=6b2e935e07) | Nov 12, 2022 |
| ASRock        | X300M-STX                   | [b071af765d](https://linux-hardware.org/?probe=b071af765d) | Nov 12, 2022 |
| ASUSTek       | M5A78L-M LX                 | [7998f1d9a3](https://linux-hardware.org/?probe=7998f1d9a3) | Nov 12, 2022 |
| ASUSTek       | PRIME A320M-K               | [f4ed581802](https://linux-hardware.org/?probe=f4ed581802) | Nov 11, 2022 |
| ASUSTek       | PRIME A320M-K               | [e06ab9c0b9](https://linux-hardware.org/?probe=e06ab9c0b9) | Nov 11, 2022 |
| MSI           | H110M ECO                   | [f7a8135cee](https://linux-hardware.org/?probe=f7a8135cee) | Nov 11, 2022 |
| Biostar       | TPower X58                  | [8662697d27](https://linux-hardware.org/?probe=8662697d27) | Nov 11, 2022 |
| ASUSTek       | P5K SE/EPU                  | [d5e58b3718](https://linux-hardware.org/?probe=d5e58b3718) | Nov 11, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [518979e264](https://linux-hardware.org/?probe=518979e264) | Nov 11, 2022 |
| Gigabyte      | MZBSWAP-K4                  | [902fafd6cd](https://linux-hardware.org/?probe=902fafd6cd) | Nov 11, 2022 |
| Gigabyte      | Z270-HD3P-CF                | [578b9c0e61](https://linux-hardware.org/?probe=578b9c0e61) | Nov 11, 2022 |
| Gigabyte      | H81M-D2V                    | [6035f1ee45](https://linux-hardware.org/?probe=6035f1ee45) | Nov 11, 2022 |
| MSI           | X79A-GD45                   | [cb82895374](https://linux-hardware.org/?probe=cb82895374) | Nov 11, 2022 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | [4c84942d2b](https://linux-hardware.org/?probe=4c84942d2b) | Nov 10, 2022 |
| ASUSTek       | PRIME X570-P                | [0e930e7a64](https://linux-hardware.org/?probe=0e930e7a64) | Nov 10, 2022 |
| Gigabyte      | X58A-UD3R                   | [14afa89833](https://linux-hardware.org/?probe=14afa89833) | Nov 10, 2022 |
| Dell          | 00V62H A01                  | [d5f5f32529](https://linux-hardware.org/?probe=d5f5f32529) | Nov 10, 2022 |
| Dell          | 0DR845                      | [c4d2b18dd8](https://linux-hardware.org/?probe=c4d2b18dd8) | Nov 10, 2022 |
| MSI           | D2415 S26361-D2415-A10      | [924e18bdcc](https://linux-hardware.org/?probe=924e18bdcc) | Nov 10, 2022 |
| ASUSTek       | P5Q-E                       | [a37be95e80](https://linux-hardware.org/?probe=a37be95e80) | Nov 10, 2022 |
| ASRock        | FM2A88X-ITX+                | [9347a32d59](https://linux-hardware.org/?probe=9347a32d59) | Nov 10, 2022 |
| Gigabyte      | H55M-UD2H                   | [d32e991d14](https://linux-hardware.org/?probe=d32e991d14) | Nov 10, 2022 |
| Dell          | 0C27VV A01                  | [9e5c4960c3](https://linux-hardware.org/?probe=9e5c4960c3) | Nov 10, 2022 |
| Dell          | 0C27VV A01                  | [a8c3b285d0](https://linux-hardware.org/?probe=a8c3b285d0) | Nov 10, 2022 |
| Gigabyte      | B75M-D3H                    | [b7619dbd72](https://linux-hardware.org/?probe=b7619dbd72) | Nov 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [bf5e7a39a0](https://linux-hardware.org/?probe=bf5e7a39a0) | Nov 09, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [faf531627e](https://linux-hardware.org/?probe=faf531627e) | Nov 09, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [fb87099a0d](https://linux-hardware.org/?probe=fb87099a0d) | Nov 09, 2022 |
| ASUSTek       | PRIME A320M-K               | [fcd0449df8](https://linux-hardware.org/?probe=fcd0449df8) | Nov 09, 2022 |
| MSI           | MEG X570 UNIFY              | [f419558b59](https://linux-hardware.org/?probe=f419558b59) | Nov 09, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [b2d88e2356](https://linux-hardware.org/?probe=b2d88e2356) | Nov 09, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [776a9bc0b6](https://linux-hardware.org/?probe=776a9bc0b6) | Nov 09, 2022 |
| Acer          | Aspire X1930                | [9cdf367d20](https://linux-hardware.org/?probe=9cdf367d20) | Nov 08, 2022 |
| ASRock        | FM2A68M-HD+                 | [a90c14df17](https://linux-hardware.org/?probe=a90c14df17) | Nov 08, 2022 |
| MSI           | Z77A-G43                    | [6dd1e1dc43](https://linux-hardware.org/?probe=6dd1e1dc43) | Nov 07, 2022 |
| Fujitsu       | D2950-A1 S26361-D2950-A1    | [5a88973f7b](https://linux-hardware.org/?probe=5a88973f7b) | Nov 07, 2022 |
| ASRock        | X300M-STX                   | [1fee3f08a9](https://linux-hardware.org/?probe=1fee3f08a9) | Nov 07, 2022 |
| ASRock        | 960GM-GS3 FX                | [ff0d4c2010](https://linux-hardware.org/?probe=ff0d4c2010) | Nov 07, 2022 |
| MSI           | MPG Z590 GAMING CARBON W... | [6987230f73](https://linux-hardware.org/?probe=6987230f73) | Nov 07, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | [640298162b](https://linux-hardware.org/?probe=640298162b) | Nov 07, 2022 |
| ASRock        | Z170 Extreme4               | [f0b56da15d](https://linux-hardware.org/?probe=f0b56da15d) | Nov 07, 2022 |
| Pegatron      | 2AB6                        | [c55efc41db](https://linux-hardware.org/?probe=c55efc41db) | Nov 06, 2022 |
| ASUSTek       | H97M-PLUS                   | [cb778b5593](https://linux-hardware.org/?probe=cb778b5593) | Nov 06, 2022 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | [c46066bcee](https://linux-hardware.org/?probe=c46066bcee) | Nov 06, 2022 |
| T-bao         | MINI PC V1.0                | [f24987d1f0](https://linux-hardware.org/?probe=f24987d1f0) | Nov 06, 2022 |
| T-bao         | MINI PC V1.0                | [dfa8b217aa](https://linux-hardware.org/?probe=dfa8b217aa) | Nov 06, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [99f14194db](https://linux-hardware.org/?probe=99f14194db) | Nov 06, 2022 |
| MSI           | B450M MORTAR MAX            | [b5470f4f19](https://linux-hardware.org/?probe=b5470f4f19) | Nov 06, 2022 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | [c95e4aacac](https://linux-hardware.org/?probe=c95e4aacac) | Nov 06, 2022 |
| ASUSTek       | P5K                         | [6085242cc3](https://linux-hardware.org/?probe=6085242cc3) | Nov 06, 2022 |
| ASUSTek       | P5K                         | [7cddfe4e9a](https://linux-hardware.org/?probe=7cddfe4e9a) | Nov 06, 2022 |
| HP            | 1850                        | [948d3612b1](https://linux-hardware.org/?probe=948d3612b1) | Nov 05, 2022 |
| Gigabyte      | 990FXA-UD7                  | [d4d7721821](https://linux-hardware.org/?probe=d4d7721821) | Nov 05, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [82e39bdaf1](https://linux-hardware.org/?probe=82e39bdaf1) | Nov 05, 2022 |
| Gigabyte      | Z77-DS3H                    | [e97900160b](https://linux-hardware.org/?probe=e97900160b) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | [f60040c1b7](https://linux-hardware.org/?probe=f60040c1b7) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M90p 3282A9G    | [cd87b011a0](https://linux-hardware.org/?probe=cd87b011a0) | Nov 05, 2022 |
| HP            | 3397                        | [9cb876048a](https://linux-hardware.org/?probe=9cb876048a) | Nov 05, 2022 |
| Unknown       | Unknown                     | [2032d5239e](https://linux-hardware.org/?probe=2032d5239e) | Nov 05, 2022 |
| Dell          | 0GX297                      | [fab653cbbe](https://linux-hardware.org/?probe=fab653cbbe) | Nov 04, 2022 |
| HP            | 339A                        | [77ddeeda51](https://linux-hardware.org/?probe=77ddeeda51) | Nov 04, 2022 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | [14dc45e331](https://linux-hardware.org/?probe=14dc45e331) | Nov 04, 2022 |
| HP            | 339A                        | [8ebb8b6522](https://linux-hardware.org/?probe=8ebb8b6522) | Nov 04, 2022 |
| Fujitsu       | D3061-B1 S26361-D3061-B1    | [0e897e5beb](https://linux-hardware.org/?probe=0e897e5beb) | Nov 04, 2022 |
| MSI           | B450-A PRO                  | [8ef3469319](https://linux-hardware.org/?probe=8ef3469319) | Nov 04, 2022 |
| MSI           | H510M PRO                   | [16980e0782](https://linux-hardware.org/?probe=16980e0782) | Nov 04, 2022 |
| Dell          | 00V62H A01                  | [d2ba0a8916](https://linux-hardware.org/?probe=d2ba0a8916) | Nov 04, 2022 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | [9aa8622017](https://linux-hardware.org/?probe=9aa8622017) | Nov 04, 2022 |
| Unknown       | Unknown                     | [8493dcc5e8](https://linux-hardware.org/?probe=8493dcc5e8) | Nov 04, 2022 |
| Dell          | 00V62H A01                  | [57bf24f3da](https://linux-hardware.org/?probe=57bf24f3da) | Nov 04, 2022 |
| HP            | 8056                        | [1a0c34fb50](https://linux-hardware.org/?probe=1a0c34fb50) | Nov 04, 2022 |
| ASUSTek       | P8Z77-V                     | [65c0f5965b](https://linux-hardware.org/?probe=65c0f5965b) | Nov 04, 2022 |
| MSI           | H510M PRO                   | [646aee082a](https://linux-hardware.org/?probe=646aee082a) | Nov 04, 2022 |
| ASRock        | 960GM-GS3 FX                | [f0ba8ee881](https://linux-hardware.org/?probe=f0ba8ee881) | Nov 03, 2022 |
| ASRock        | Q1900M                      | [97544ca916](https://linux-hardware.org/?probe=97544ca916) | Nov 03, 2022 |
| Gigabyte      | B75M-D3H                    | [6d8a634229](https://linux-hardware.org/?probe=6d8a634229) | Nov 03, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [db852ba394](https://linux-hardware.org/?probe=db852ba394) | Nov 03, 2022 |
| Lenovo        | 3716                        | [5a04bbf315](https://linux-hardware.org/?probe=5a04bbf315) | Nov 03, 2022 |
| Gigabyte      | H310M H                     | [7a49c87643](https://linux-hardware.org/?probe=7a49c87643) | Nov 02, 2022 |
| Gigabyte      | H310M H                     | [382965c890](https://linux-hardware.org/?probe=382965c890) | Nov 02, 2022 |
| Medion        | MS-7707                     | [d02f67ee8f](https://linux-hardware.org/?probe=d02f67ee8f) | Nov 02, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [77f847ca29](https://linux-hardware.org/?probe=77f847ca29) | Nov 02, 2022 |
| ASRock        | B450 Pro4                   | [5da1d76cd5](https://linux-hardware.org/?probe=5da1d76cd5) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | [706fb22c95](https://linux-hardware.org/?probe=706fb22c95) | Nov 02, 2022 |
| ASRock        | Q1900B-ITX                  | [6305a98777](https://linux-hardware.org/?probe=6305a98777) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [86bf890d23](https://linux-hardware.org/?probe=86bf890d23) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | [da6ecef3a7](https://linux-hardware.org/?probe=da6ecef3a7) | Nov 02, 2022 |
| HP            | 8054                        | [0f866b3605](https://linux-hardware.org/?probe=0f866b3605) | Nov 02, 2022 |
| ASRock        | N68C-GS UCC                 | [9430ecf81c](https://linux-hardware.org/?probe=9430ecf81c) | Nov 02, 2022 |
| Lenovo        | ThinkCentre A57 970274G     | [809e137f17](https://linux-hardware.org/?probe=809e137f17) | Nov 02, 2022 |
| Pegatron      | 2AD5                        | [0b91ee456b](https://linux-hardware.org/?probe=0b91ee456b) | Nov 02, 2022 |
| ASUSTek       | F2A55-M LK                  | [40cedc7d2c](https://linux-hardware.org/?probe=40cedc7d2c) | Nov 02, 2022 |
| MSI           | H97 GAMING 3                | [1a8c44ca83](https://linux-hardware.org/?probe=1a8c44ca83) | Nov 02, 2022 |
| Pegatron      | 2AD5                        | [5f90d4e478](https://linux-hardware.org/?probe=5f90d4e478) | Nov 02, 2022 |
| ASUSTek       | PRO B460M-C                 | [dcf7112b3d](https://linux-hardware.org/?probe=dcf7112b3d) | Nov 01, 2022 |
| ASUSTek       | PRO B460M-C                 | [a333f47ffa](https://linux-hardware.org/?probe=a333f47ffa) | Nov 01, 2022 |
| HP            | 1905                        | [df0d192970](https://linux-hardware.org/?probe=df0d192970) | Nov 01, 2022 |
| Gigabyte      | P55-UD6                     | [2898ec20b3](https://linux-hardware.org/?probe=2898ec20b3) | Nov 01, 2022 |
| ASUSTek       | M5A78L-M LX V2              | [50bd7a7436](https://linux-hardware.org/?probe=50bd7a7436) | Nov 01, 2022 |
| Dell          | 0C522T A01                  | [efee8139b0](https://linux-hardware.org/?probe=efee8139b0) | Nov 01, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [5fd845ca54](https://linux-hardware.org/?probe=5fd845ca54) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6e577f6de5](https://linux-hardware.org/?probe=6e577f6de5) | Nov 01, 2022 |
| HP            | 339A                        | [68392c18c9](https://linux-hardware.org/?probe=68392c18c9) | Nov 01, 2022 |
| HP            | 1850                        | [b39eac8f74](https://linux-hardware.org/?probe=b39eac8f74) | Oct 31, 2022 |
| Gigabyte      | X99-SLI-CF                  | [d6bc77d638](https://linux-hardware.org/?probe=d6bc77d638) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [966eb5bb18](https://linux-hardware.org/?probe=966eb5bb18) | Oct 31, 2022 |
| Unknown       | Unknown                     | [7cce0a2867](https://linux-hardware.org/?probe=7cce0a2867) | Oct 31, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [860f45c4c1](https://linux-hardware.org/?probe=860f45c4c1) | Oct 31, 2022 |
| HP            | 18E4                        | [89b197e8a9](https://linux-hardware.org/?probe=89b197e8a9) | Oct 31, 2022 |
| ASUSTek       | PRIME B450M-A II            | [c23efa8caa](https://linux-hardware.org/?probe=c23efa8caa) | Oct 31, 2022 |
| Gigabyte      | GA-770TA-UD3                | [4833a609c3](https://linux-hardware.org/?probe=4833a609c3) | Oct 31, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [56ee27b737](https://linux-hardware.org/?probe=56ee27b737) | Oct 31, 2022 |
| ASRock        | Z97 Extreme3                | [c741e4ffe8](https://linux-hardware.org/?probe=c741e4ffe8) | Oct 31, 2022 |
| Gigabyte      | X570 GAMING X               | [d6c135685f](https://linux-hardware.org/?probe=d6c135685f) | Oct 30, 2022 |
| ASUSTek       | A8N32-SLI-Deluxe            | [85389b6454](https://linux-hardware.org/?probe=85389b6454) | Oct 30, 2022 |
| Gigabyte      | Z77M-D3H                    | [83cd207e4e](https://linux-hardware.org/?probe=83cd207e4e) | Oct 30, 2022 |
| ASRock        | B550M Pro4                  | [078fd46e0a](https://linux-hardware.org/?probe=078fd46e0a) | Oct 30, 2022 |
| Shuttle       | FH61R                       | [26f86947ef](https://linux-hardware.org/?probe=26f86947ef) | Oct 30, 2022 |
| ASRock        | 960GM-VGS3 FX               | [ac82c6bda9](https://linux-hardware.org/?probe=ac82c6bda9) | Oct 30, 2022 |
| ASRock        | X570 Pro4                   | [d2407c253b](https://linux-hardware.org/?probe=d2407c253b) | Oct 30, 2022 |
| ASUSTek       | A8N32-SLI-Deluxe            | [55be6f23ce](https://linux-hardware.org/?probe=55be6f23ce) | Oct 30, 2022 |
| Medion        | MS-7707                     | [4f018e8577](https://linux-hardware.org/?probe=4f018e8577) | Oct 30, 2022 |
| MSI           | MS-7358                     | [3ddf4b8fff](https://linux-hardware.org/?probe=3ddf4b8fff) | Oct 30, 2022 |
| ASRock        | 960GM-VGS3 FX               | [5769997d2a](https://linux-hardware.org/?probe=5769997d2a) | Oct 29, 2022 |
| HP            | 0AECh D                     | [ee09a01e9e](https://linux-hardware.org/?probe=ee09a01e9e) | Oct 29, 2022 |
| ASRock        | Z77 Pro4                    | [5ab5790e5f](https://linux-hardware.org/?probe=5ab5790e5f) | Oct 29, 2022 |
| ASRock        | Z77 Pro4                    | [74cc7f147b](https://linux-hardware.org/?probe=74cc7f147b) | Oct 29, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [068d4ec2e6](https://linux-hardware.org/?probe=068d4ec2e6) | Oct 29, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [2c57f9b6a3](https://linux-hardware.org/?probe=2c57f9b6a3) | Oct 29, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [836d9e4de1](https://linux-hardware.org/?probe=836d9e4de1) | Oct 29, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [b7b7481628](https://linux-hardware.org/?probe=b7b7481628) | Oct 29, 2022 |
| Dell          | 0GY6Y8 A03                  | [1c95e9ba40](https://linux-hardware.org/?probe=1c95e9ba40) | Oct 28, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [ce9a718851](https://linux-hardware.org/?probe=ce9a718851) | Oct 28, 2022 |
| ASRock        | Z87 Extreme6                | [a3056065b9](https://linux-hardware.org/?probe=a3056065b9) | Oct 28, 2022 |
| ASRock        | Z87 Extreme6                | [b9e3562398](https://linux-hardware.org/?probe=b9e3562398) | Oct 28, 2022 |
| HP            | 339A                        | [0fdbd7b1d7](https://linux-hardware.org/?probe=0fdbd7b1d7) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VI EXTREME    | [d66f4b6bd9](https://linux-hardware.org/?probe=d66f4b6bd9) | Oct 28, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [81e31b481f](https://linux-hardware.org/?probe=81e31b481f) | Oct 27, 2022 |
| HP            | 894B 10                     | [56afe0f581](https://linux-hardware.org/?probe=56afe0f581) | Oct 27, 2022 |
| Gigabyte      | H370 HD3-CF                 | [275bc51aaf](https://linux-hardware.org/?probe=275bc51aaf) | Oct 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [865ff52614](https://linux-hardware.org/?probe=865ff52614) | Oct 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [4411ceb907](https://linux-hardware.org/?probe=4411ceb907) | Oct 27, 2022 |
| HP            | 2B17                        | [9e5c7e9258](https://linux-hardware.org/?probe=9e5c7e9258) | Oct 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | [4659be383c](https://linux-hardware.org/?probe=4659be383c) | Oct 27, 2022 |
| HP            | 1494                        | [ce43cdfac1](https://linux-hardware.org/?probe=ce43cdfac1) | Oct 26, 2022 |
| HP            | 1494                        | [a23d74a9b3](https://linux-hardware.org/?probe=a23d74a9b3) | Oct 26, 2022 |
| ASUSTek       | Maximus VIII HERO           | [cb657f604d](https://linux-hardware.org/?probe=cb657f604d) | Oct 26, 2022 |
| Fujitsu       | D3498-A2 S26361-D3498-A2    | [d34926f87f](https://linux-hardware.org/?probe=d34926f87f) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [26c34998ae](https://linux-hardware.org/?probe=26c34998ae) | Oct 26, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [8c97ee418a](https://linux-hardware.org/?probe=8c97ee418a) | Oct 26, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [7a0f5285f2](https://linux-hardware.org/?probe=7a0f5285f2) | Oct 26, 2022 |
| ASRock        | B450 Pro4                   | [666aba57b3](https://linux-hardware.org/?probe=666aba57b3) | Oct 26, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [ed68d3c49d](https://linux-hardware.org/?probe=ed68d3c49d) | Oct 26, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [8248930fb7](https://linux-hardware.org/?probe=8248930fb7) | Oct 26, 2022 |
| ASRock        | FM2A78M-HD+                 | [2d0d5ac22b](https://linux-hardware.org/?probe=2d0d5ac22b) | Oct 26, 2022 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | [8e957f305e](https://linux-hardware.org/?probe=8e957f305e) | Oct 26, 2022 |
| Gigabyte      | GA-MA770-UD3                | [ef555f6161](https://linux-hardware.org/?probe=ef555f6161) | Oct 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [46d64e9947](https://linux-hardware.org/?probe=46d64e9947) | Oct 25, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [bb655d6ea7](https://linux-hardware.org/?probe=bb655d6ea7) | Oct 25, 2022 |
| ASUSTek       | P5K-VM                      | [cc1ae5c7f4](https://linux-hardware.org/?probe=cc1ae5c7f4) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [3c65639aad](https://linux-hardware.org/?probe=3c65639aad) | Oct 25, 2022 |
| MSI           | B450M PRO-VDH MAX           | [c1ce4e70e0](https://linux-hardware.org/?probe=c1ce4e70e0) | Oct 25, 2022 |
| ASUSTek       | PRIME B550M-A               | [64e6199c96](https://linux-hardware.org/?probe=64e6199c96) | Oct 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [4ef2a348fc](https://linux-hardware.org/?probe=4ef2a348fc) | Oct 25, 2022 |
| Hardkernel    | ODROID-H2                   | [6398e45c99](https://linux-hardware.org/?probe=6398e45c99) | Oct 24, 2022 |
| Gigabyte      | EP45-DS3L                   | [ee6005f3e7](https://linux-hardware.org/?probe=ee6005f3e7) | Oct 24, 2022 |
| Gigabyte      | EP45-DS3L                   | [b2a8d40905](https://linux-hardware.org/?probe=b2a8d40905) | Oct 24, 2022 |
| HP            | 2B17                        | [4a29395403](https://linux-hardware.org/?probe=4a29395403) | Oct 24, 2022 |
| ASUSTek       | PRIME A320M-K               | [c0b3f0d88e](https://linux-hardware.org/?probe=c0b3f0d88e) | Oct 24, 2022 |
| Gigabyte      | Z77-DS3H                    | [e894ec1b8d](https://linux-hardware.org/?probe=e894ec1b8d) | Oct 24, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [ce3e956a0a](https://linux-hardware.org/?probe=ce3e956a0a) | Oct 24, 2022 |
| ASUSTek       | PB62                        | [ddec39293d](https://linux-hardware.org/?probe=ddec39293d) | Oct 23, 2022 |
| ASUSTek       | P8Z68-V LX                  | [86cff422a6](https://linux-hardware.org/?probe=86cff422a6) | Oct 23, 2022 |
| Medion        | MS-7707                     | [e6d2f4c633](https://linux-hardware.org/?probe=e6d2f4c633) | Oct 23, 2022 |
| ASRock        | FM2A88X-ITX+                | [4865089bf5](https://linux-hardware.org/?probe=4865089bf5) | Oct 23, 2022 |
| MSI           | A320M PRO-M2 V2             | [1691497b7a](https://linux-hardware.org/?probe=1691497b7a) | Oct 23, 2022 |
| Unknown       | 1.0                         | [2a12c33601](https://linux-hardware.org/?probe=2a12c33601) | Oct 23, 2022 |
| MSI           | 760GM-P23                   | [21db3e8ee8](https://linux-hardware.org/?probe=21db3e8ee8) | Oct 23, 2022 |
| HP            | 3647h                       | [b65d5d4bff](https://linux-hardware.org/?probe=b65d5d4bff) | Oct 23, 2022 |
| ASRock        | FM2A68M-HD+                 | [1a49be478c](https://linux-hardware.org/?probe=1a49be478c) | Oct 22, 2022 |
| Gigabyte      | TRX40 DESIGNARE             | [16f90b14dc](https://linux-hardware.org/?probe=16f90b14dc) | Oct 22, 2022 |
| Acer          | Aspire TC-780               | [fd6c66dac7](https://linux-hardware.org/?probe=fd6c66dac7) | Oct 22, 2022 |
| MSI           | B550-A PRO                  | [52d3513a9c](https://linux-hardware.org/?probe=52d3513a9c) | Oct 22, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | [94f3d7aa9d](https://linux-hardware.org/?probe=94f3d7aa9d) | Oct 22, 2022 |
| HP            | 81C3                        | [8c2524a9ba](https://linux-hardware.org/?probe=8c2524a9ba) | Oct 22, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [edf45abefe](https://linux-hardware.org/?probe=edf45abefe) | Oct 21, 2022 |
| MSI           | B550-A PRO                  | [d17faed180](https://linux-hardware.org/?probe=d17faed180) | Oct 21, 2022 |
| Dell          | 0GM819                      | [e2ebe8bae1](https://linux-hardware.org/?probe=e2ebe8bae1) | Oct 21, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [24a7381e8b](https://linux-hardware.org/?probe=24a7381e8b) | Oct 21, 2022 |
| MSI           | A320M-A PRO MAX             | [774861eae7](https://linux-hardware.org/?probe=774861eae7) | Oct 21, 2022 |
| ASRock        | N68-S                       | [3cfa7cd9f8](https://linux-hardware.org/?probe=3cfa7cd9f8) | Oct 21, 2022 |
| MSI           | H81M-E34                    | [b036f0d602](https://linux-hardware.org/?probe=b036f0d602) | Oct 21, 2022 |
| ASUSTek       | Z97-P                       | [f5b8282e1f](https://linux-hardware.org/?probe=f5b8282e1f) | Oct 21, 2022 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | [8a5ccf8170](https://linux-hardware.org/?probe=8a5ccf8170) | Oct 21, 2022 |
| ASUSTek       | H97I-PLUS                   | [b403dcc362](https://linux-hardware.org/?probe=b403dcc362) | Oct 21, 2022 |
| HP            | 2B17                        | [649ee9692f](https://linux-hardware.org/?probe=649ee9692f) | Oct 21, 2022 |
| ASRock        | Q1900-ITX                   | [c9d76cd138](https://linux-hardware.org/?probe=c9d76cd138) | Oct 20, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [7a1b569725](https://linux-hardware.org/?probe=7a1b569725) | Oct 20, 2022 |
| HP            | 1850                        | [786fd367d5](https://linux-hardware.org/?probe=786fd367d5) | Oct 20, 2022 |
| Acer          | Extensa M2610 V:1.0         | [1791236969](https://linux-hardware.org/?probe=1791236969) | Oct 20, 2022 |
| Acer          | Extensa M2610 V:1.0         | [e482e312c8](https://linux-hardware.org/?probe=e482e312c8) | Oct 20, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [01338c4f3c](https://linux-hardware.org/?probe=01338c4f3c) | Oct 19, 2022 |
| ASRock        | B450 Pro4                   | [d7784759fb](https://linux-hardware.org/?probe=d7784759fb) | Oct 19, 2022 |
| MSI           | A320M PRO-M2 V2             | [7524f39579](https://linux-hardware.org/?probe=7524f39579) | Oct 19, 2022 |
| HP            | 3397                        | [b32a50dc29](https://linux-hardware.org/?probe=b32a50dc29) | Oct 19, 2022 |
| HP            | 876C SMVB                   | [384313312d](https://linux-hardware.org/?probe=384313312d) | Oct 19, 2022 |
| MSI           | 970A-G43                    | [cf36036d1d](https://linux-hardware.org/?probe=cf36036d1d) | Oct 18, 2022 |
| HP            | 0A58h                       | [4c8d533bb0](https://linux-hardware.org/?probe=4c8d533bb0) | Oct 18, 2022 |
| HP            | 3397                        | [549104078d](https://linux-hardware.org/?probe=549104078d) | Oct 18, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [e0b5c85988](https://linux-hardware.org/?probe=e0b5c85988) | Oct 18, 2022 |
| Dell          | 09WH54 A00                  | [b16396bd74](https://linux-hardware.org/?probe=b16396bd74) | Oct 18, 2022 |
| ASRock        | X300M-STX                   | [549fe857a6](https://linux-hardware.org/?probe=549fe857a6) | Oct 18, 2022 |
| MSI           | B450M PRO-VDH MAX           | [71ab3d919c](https://linux-hardware.org/?probe=71ab3d919c) | Oct 18, 2022 |
| HP            | 8399                        | [2637ec62e5](https://linux-hardware.org/?probe=2637ec62e5) | Oct 18, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | [1b0e52eddb](https://linux-hardware.org/?probe=1b0e52eddb) | Oct 18, 2022 |
| Fujitsu Si... | D1561 S26361-D1561          | [ac60151848](https://linux-hardware.org/?probe=ac60151848) | Oct 18, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [98024d1066](https://linux-hardware.org/?probe=98024d1066) | Oct 17, 2022 |
| Gigabyte      | MZBSWAP-K4                  | [ef6d1400a3](https://linux-hardware.org/?probe=ef6d1400a3) | Oct 17, 2022 |
| Gigabyte      | M68MT-S2                    | [282e240d2b](https://linux-hardware.org/?probe=282e240d2b) | Oct 17, 2022 |
| Lenovo        | 310B SDK0J40705 WIN 3425... | [ca239da906](https://linux-hardware.org/?probe=ca239da906) | Oct 17, 2022 |
| ASRock        | Z87M Pro4                   | [cf5be4f1e6](https://linux-hardware.org/?probe=cf5be4f1e6) | Oct 17, 2022 |
| ASUSTek       | PRIME A520M-A II            | [cbf3a839e2](https://linux-hardware.org/?probe=cbf3a839e2) | Oct 17, 2022 |
| Acer          | MCP7A                       | [32f914d009](https://linux-hardware.org/?probe=32f914d009) | Oct 17, 2022 |
| MSI           | MEG X570 UNIFY              | [0ec570b33c](https://linux-hardware.org/?probe=0ec570b33c) | Oct 16, 2022 |
| ASRock        | B450M Pro4                  | [d55b50c6c7](https://linux-hardware.org/?probe=d55b50c6c7) | Oct 16, 2022 |
| ASRock        | B450M Pro4                  | [4af4c60051](https://linux-hardware.org/?probe=4af4c60051) | Oct 16, 2022 |
| MSI           | A75MA-G55                   | [79c4c3b21f](https://linux-hardware.org/?probe=79c4c3b21f) | Oct 16, 2022 |
| Dell          | 0W0CHX A00                  | [f305948282](https://linux-hardware.org/?probe=f305948282) | Oct 16, 2022 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | [62cacee577](https://linux-hardware.org/?probe=62cacee577) | Oct 16, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | [c0feb12708](https://linux-hardware.org/?probe=c0feb12708) | Oct 16, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a897ba9d5d](https://linux-hardware.org/?probe=a897ba9d5d) | Oct 16, 2022 |
| MSI           | A320M-A PRO MAX             | [176bc5b449](https://linux-hardware.org/?probe=176bc5b449) | Oct 16, 2022 |
| HP            | 8027                        | [9f3d6e24b5](https://linux-hardware.org/?probe=9f3d6e24b5) | Oct 15, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [b7ebef4e11](https://linux-hardware.org/?probe=b7ebef4e11) | Oct 15, 2022 |
| MSI           | MAG B560 TORPEDO            | [e4522a15ff](https://linux-hardware.org/?probe=e4522a15ff) | Oct 15, 2022 |
| MSI           | A320M-A PRO MAX             | [5f85879cf4](https://linux-hardware.org/?probe=5f85879cf4) | Oct 15, 2022 |
| Gigabyte      | X79S-UP5                    | [62f59af32c](https://linux-hardware.org/?probe=62f59af32c) | Oct 15, 2022 |
| Medion        | MS-7800                     | [8f5e15be42](https://linux-hardware.org/?probe=8f5e15be42) | Oct 15, 2022 |
| Gigabyte      | B75M-D3H                    | [7ead04b896](https://linux-hardware.org/?probe=7ead04b896) | Oct 14, 2022 |
| Gigabyte      | F2A55M-DS2                  | [1feb9942e8](https://linux-hardware.org/?probe=1feb9942e8) | Oct 14, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [9554b1f29a](https://linux-hardware.org/?probe=9554b1f29a) | Oct 14, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [60e6bd1280](https://linux-hardware.org/?probe=60e6bd1280) | Oct 14, 2022 |
| ASUSTek       | PRIME B365M-A               | [e025a87662](https://linux-hardware.org/?probe=e025a87662) | Oct 13, 2022 |
| ASUSTek       | PRIME B365M-A               | [df44c77cfa](https://linux-hardware.org/?probe=df44c77cfa) | Oct 13, 2022 |
| ASUSTek       | P8H67-V                     | [0a4b34dba9](https://linux-hardware.org/?probe=0a4b34dba9) | Oct 13, 2022 |
| ASUSTek       | PRIME A520M-A II            | [736d5cdccc](https://linux-hardware.org/?probe=736d5cdccc) | Oct 13, 2022 |
| MSI           | A320M PRO-M2 V2             | [6c895cb5df](https://linux-hardware.org/?probe=6c895cb5df) | Oct 13, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [4bc8ad9e5f](https://linux-hardware.org/?probe=4bc8ad9e5f) | Oct 12, 2022 |
| BESSTAR Te... | UM350                       | [f58608a000](https://linux-hardware.org/?probe=f58608a000) | Oct 11, 2022 |
| HP            | 0A5Ch                       | [e45ea1b715](https://linux-hardware.org/?probe=e45ea1b715) | Oct 11, 2022 |
| ASUSTek       | P5K-VM                      | [4401db984a](https://linux-hardware.org/?probe=4401db984a) | Oct 11, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [300975f708](https://linux-hardware.org/?probe=300975f708) | Oct 11, 2022 |
| ASUSTek       | PRIME X370-PRO              | [89070a8e96](https://linux-hardware.org/?probe=89070a8e96) | Oct 11, 2022 |
| HP            | 2171                        | [105af7e899](https://linux-hardware.org/?probe=105af7e899) | Oct 11, 2022 |
| ASUSTek       | P8H67-M LE                  | [4f4f9e3cef](https://linux-hardware.org/?probe=4f4f9e3cef) | Oct 11, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [e8a439bb9d](https://linux-hardware.org/?probe=e8a439bb9d) | Oct 11, 2022 |
| MSI           | B550-A PRO                  | [0526dffee9](https://linux-hardware.org/?probe=0526dffee9) | Oct 11, 2022 |
| Gigabyte      | X299X DESIGNARE 10G         | [fd590a067e](https://linux-hardware.org/?probe=fd590a067e) | Oct 10, 2022 |
| MSI           | 970A-G43                    | [c9c2e07ada](https://linux-hardware.org/?probe=c9c2e07ada) | Oct 10, 2022 |
| MSI           | P67A-GD65                   | [009f3853bf](https://linux-hardware.org/?probe=009f3853bf) | Oct 10, 2022 |
| MSI           | 970A-G43                    | [0b6ff268e1](https://linux-hardware.org/?probe=0b6ff268e1) | Oct 10, 2022 |
| Gigabyte      | M68MT-S2                    | [9122f26c80](https://linux-hardware.org/?probe=9122f26c80) | Oct 09, 2022 |
| Fujitsu       | D3003-D1 S26361-D3003-D1    | [afba95481a](https://linux-hardware.org/?probe=afba95481a) | Oct 09, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [37068529a1](https://linux-hardware.org/?probe=37068529a1) | Oct 09, 2022 |
| Fujitsu Si... | D2750-A2 S26361-D2750-A2    | [f8ffca88cc](https://linux-hardware.org/?probe=f8ffca88cc) | Oct 09, 2022 |
| Dell          | 0T568R A00                  | [f217db1e8b](https://linux-hardware.org/?probe=f217db1e8b) | Oct 09, 2022 |
| HP            | 2B4B                        | [b36dc773b0](https://linux-hardware.org/?probe=b36dc773b0) | Oct 09, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [4965ccfef4](https://linux-hardware.org/?probe=4965ccfef4) | Oct 09, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [f80d633c86](https://linux-hardware.org/?probe=f80d633c86) | Oct 09, 2022 |
| Acer          | Aspire XC-105               | [92ba1e0dd4](https://linux-hardware.org/?probe=92ba1e0dd4) | Oct 08, 2022 |
| ASRock        | A75M                        | [b3df324d02](https://linux-hardware.org/?probe=b3df324d02) | Oct 08, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [1335441845](https://linux-hardware.org/?probe=1335441845) | Oct 08, 2022 |
| MSI           | MPG Z590M GAMING EDGE WI... | [b9c9bb7f82](https://linux-hardware.org/?probe=b9c9bb7f82) | Oct 08, 2022 |
| HP            | 0AE8h C                     | [f0b3766b7e](https://linux-hardware.org/?probe=f0b3766b7e) | Oct 08, 2022 |
| HP            | 0AE8h C                     | [4a7d6ce6df](https://linux-hardware.org/?probe=4a7d6ce6df) | Oct 08, 2022 |
| ASRock        | A320M-DGS                   | [b602eb3419](https://linux-hardware.org/?probe=b602eb3419) | Oct 08, 2022 |
| ASRock        | H87 Pro4                    | [d61835444b](https://linux-hardware.org/?probe=d61835444b) | Oct 08, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [937941b02e](https://linux-hardware.org/?probe=937941b02e) | Oct 08, 2022 |
| HP            | 3647h                       | [ddffa21a6e](https://linux-hardware.org/?probe=ddffa21a6e) | Oct 07, 2022 |
| ASUSTek       | P8H67-M LE                  | [9cd069f242](https://linux-hardware.org/?probe=9cd069f242) | Oct 07, 2022 |
| ASUSTek       | PRIME B550M-A               | [c203d7c388](https://linux-hardware.org/?probe=c203d7c388) | Oct 07, 2022 |
| ASUSTek       | Z170-K                      | [69c51c7d03](https://linux-hardware.org/?probe=69c51c7d03) | Oct 07, 2022 |
| ASUSTek       | WS X299 SAGE/10G            | [d0e2d24e97](https://linux-hardware.org/?probe=d0e2d24e97) | Oct 07, 2022 |
| Dell          | 0M9KCM A01                  | [6fa93f6da5](https://linux-hardware.org/?probe=6fa93f6da5) | Oct 07, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [b457bc3cd2](https://linux-hardware.org/?probe=b457bc3cd2) | Oct 07, 2022 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | [aa89234022](https://linux-hardware.org/?probe=aa89234022) | Oct 07, 2022 |
| Gigabyte      | B360HD3PLM-CF               | [fc706adba7](https://linux-hardware.org/?probe=fc706adba7) | Oct 06, 2022 |
| Google        | Panther                     | [4040ad4267](https://linux-hardware.org/?probe=4040ad4267) | Oct 06, 2022 |
| Fujitsu       | D3071-S1 S26361-D3071-S1    | [852194f41b](https://linux-hardware.org/?probe=852194f41b) | Oct 06, 2022 |
| Dell          | 0C27VV A00                  | [0866f99d43](https://linux-hardware.org/?probe=0866f99d43) | Oct 06, 2022 |
| MSI           | 760GM-P23                   | [236a43a0ce](https://linux-hardware.org/?probe=236a43a0ce) | Oct 06, 2022 |
| MSI           | B550-A PRO                  | [de85238b42](https://linux-hardware.org/?probe=de85238b42) | Oct 05, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | [1b399dcbb2](https://linux-hardware.org/?probe=1b399dcbb2) | Oct 05, 2022 |
| MSI           | X470 GAMING PRO MAX         | [2e45442f11](https://linux-hardware.org/?probe=2e45442f11) | Oct 05, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | [d69f58e683](https://linux-hardware.org/?probe=d69f58e683) | Oct 05, 2022 |
| MSI           | A520M-A PRO                 | [ce78c6c4ee](https://linux-hardware.org/?probe=ce78c6c4ee) | Oct 05, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [b151ce6353](https://linux-hardware.org/?probe=b151ce6353) | Oct 04, 2022 |
| MSI           | H81M-E34                    | [ddae6a50ce](https://linux-hardware.org/?probe=ddae6a50ce) | Oct 04, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | [bb43eb5333](https://linux-hardware.org/?probe=bb43eb5333) | Oct 04, 2022 |
| Inventec      | D CLASS A02                 | [851214001a](https://linux-hardware.org/?probe=851214001a) | Oct 04, 2022 |
| ASUSTek       | P6T DELUXE V2               | [1c6fd70d5f](https://linux-hardware.org/?probe=1c6fd70d5f) | Oct 04, 2022 |
| ASRock        | J4005M                      | [0216eb9ea3](https://linux-hardware.org/?probe=0216eb9ea3) | Oct 04, 2022 |
| Gigabyte      | B360M D2V                   | [e0bf78b6b1](https://linux-hardware.org/?probe=e0bf78b6b1) | Oct 04, 2022 |
| Unknown       | Intel X79                   | [3f0526bc2e](https://linux-hardware.org/?probe=3f0526bc2e) | Oct 04, 2022 |
| Biostar       | A960D+V2                    | [9199dbc3dc](https://linux-hardware.org/?probe=9199dbc3dc) | Oct 03, 2022 |
| Gigabyte      | B85M-D2V                    | [4e6047ec5b](https://linux-hardware.org/?probe=4e6047ec5b) | Oct 03, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [08ff84f83f](https://linux-hardware.org/?probe=08ff84f83f) | Oct 03, 2022 |
| ASRock        | 990FX Extreme4              | [3f4ae9ce5e](https://linux-hardware.org/?probe=3f4ae9ce5e) | Oct 03, 2022 |
| Acer          | Predator G3-605             | [19cb18a1b3](https://linux-hardware.org/?probe=19cb18a1b3) | Oct 03, 2022 |
| MSI           | MEG X570 UNIFY              | [758fa4a1d6](https://linux-hardware.org/?probe=758fa4a1d6) | Oct 03, 2022 |
| ASUSTek       | A55BM-K                     | [7cb1df8ece](https://linux-hardware.org/?probe=7cb1df8ece) | Oct 02, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [b1514ab047](https://linux-hardware.org/?probe=b1514ab047) | Oct 02, 2022 |
| MSI           | 970A-G43                    | [c8f6fa5b53](https://linux-hardware.org/?probe=c8f6fa5b53) | Oct 02, 2022 |
| ASUSTek       | M5A97 R2.0                  | [78ff851478](https://linux-hardware.org/?probe=78ff851478) | Oct 02, 2022 |
| Gigabyte      | H87-HD3                     | [bc172de17b](https://linux-hardware.org/?probe=bc172de17b) | Oct 02, 2022 |
| Biostar       | A75MG                       | [ba1785b4b6](https://linux-hardware.org/?probe=ba1785b4b6) | Oct 02, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | [9121550ca1](https://linux-hardware.org/?probe=9121550ca1) | Oct 02, 2022 |
| MSI           | B450M MORTAR MAX            | [6e3b616977](https://linux-hardware.org/?probe=6e3b616977) | Oct 02, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [b1caaffb40](https://linux-hardware.org/?probe=b1caaffb40) | Oct 02, 2022 |
| ASRock        | Z97 Anniversary             | [558ca4b56e](https://linux-hardware.org/?probe=558ca4b56e) | Oct 01, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ff1c77c45a](https://linux-hardware.org/?probe=ff1c77c45a) | Oct 01, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [8a75a2c50b](https://linux-hardware.org/?probe=8a75a2c50b) | Oct 01, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [a7268f8fba](https://linux-hardware.org/?probe=a7268f8fba) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M58 9728AHG     | [a2bc7fc88f](https://linux-hardware.org/?probe=a2bc7fc88f) | Oct 01, 2022 |
| Medion        | MS-7366                     | [c8138f4ffe](https://linux-hardware.org/?probe=c8138f4ffe) | Oct 01, 2022 |
| Medion        | MS-7366                     | [c25c10b259](https://linux-hardware.org/?probe=c25c10b259) | Oct 01, 2022 |
| ASRock        | H87M Pro4                   | [bf8e635afa](https://linux-hardware.org/?probe=bf8e635afa) | Oct 01, 2022 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [982b143d73](https://linux-hardware.org/?probe=982b143d73) | Oct 01, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [151510a184](https://linux-hardware.org/?probe=151510a184) | Oct 01, 2022 |
| MSI           | X370 GAMING PLUS            | [2aa92cb043](https://linux-hardware.org/?probe=2aa92cb043) | Oct 01, 2022 |
| ASUSTek       | M4N72-E                     | [c1c308be2a](https://linux-hardware.org/?probe=c1c308be2a) | Oct 01, 2022 |
| MSI           | A55M-E33                    | [13bd049f55](https://linux-hardware.org/?probe=13bd049f55) | Sep 30, 2022 |
| MSI           | MEG X570 UNIFY              | [4d2e449699](https://linux-hardware.org/?probe=4d2e449699) | Sep 30, 2022 |
| ASUSTek       | M5A78L-M LX3                | [938523ed34](https://linux-hardware.org/?probe=938523ed34) | Sep 30, 2022 |
| ASRock        | H87M Pro4                   | [f8bb8b6de8](https://linux-hardware.org/?probe=f8bb8b6de8) | Sep 30, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [c06e7e3586](https://linux-hardware.org/?probe=c06e7e3586) | Sep 30, 2022 |
| ASUSTek       | PRIME B450M-A               | [cfe1aba7e6](https://linux-hardware.org/?probe=cfe1aba7e6) | Sep 30, 2022 |
| MSI           | Z97 MPOWER                  | [f16a15a5b7](https://linux-hardware.org/?probe=f16a15a5b7) | Sep 30, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | [97e7d2d80f](https://linux-hardware.org/?probe=97e7d2d80f) | Sep 30, 2022 |
| ASUSTek       | EX-A320M-GAMING             | [33d5d34654](https://linux-hardware.org/?probe=33d5d34654) | Sep 30, 2022 |
| Lenovo        | ThinkCentre M58 9728AHG     | [773ae7f01e](https://linux-hardware.org/?probe=773ae7f01e) | Sep 30, 2022 |
| ASRock        | Q1900M                      | [e6804dc6b7](https://linux-hardware.org/?probe=e6804dc6b7) | Sep 29, 2022 |
| HP            | 3398                        | [c2190a0657](https://linux-hardware.org/?probe=c2190a0657) | Sep 29, 2022 |
| ASUSTek       | AM1I-A                      | [201c745d4e](https://linux-hardware.org/?probe=201c745d4e) | Sep 29, 2022 |
| ASRock        | Z97 Pro3                    | [7b34a50df8](https://linux-hardware.org/?probe=7b34a50df8) | Sep 28, 2022 |
| Gigabyte      | H81M-D2W                    | [467845e1c1](https://linux-hardware.org/?probe=467845e1c1) | Sep 28, 2022 |
| Medion        | MS-7707                     | [240ac993dc](https://linux-hardware.org/?probe=240ac993dc) | Sep 28, 2022 |
| MSI           | 2A9Ch                       | [16d3df803b](https://linux-hardware.org/?probe=16d3df803b) | Sep 28, 2022 |
| ASRock        | B450 Pro4                   | [9053250a2c](https://linux-hardware.org/?probe=9053250a2c) | Sep 27, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [1e0110dd5c](https://linux-hardware.org/?probe=1e0110dd5c) | Sep 27, 2022 |
| ASRock        | Z97 Anniversary             | [6132513116](https://linux-hardware.org/?probe=6132513116) | Sep 27, 2022 |
| MSI           | B550-A PRO                  | [2a5a7aeb95](https://linux-hardware.org/?probe=2a5a7aeb95) | Sep 27, 2022 |
| Medion        | MS-7707                     | [a88f6ba4da](https://linux-hardware.org/?probe=a88f6ba4da) | Sep 27, 2022 |
| MSI           | X570-A PRO                  | [a26dee0cd5](https://linux-hardware.org/?probe=a26dee0cd5) | Sep 27, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [63cd838fcc](https://linux-hardware.org/?probe=63cd838fcc) | Sep 27, 2022 |
| Medion        | MS-7728                     | [0b9b2ca570](https://linux-hardware.org/?probe=0b9b2ca570) | Sep 27, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1979013fa2](https://linux-hardware.org/?probe=1979013fa2) | Sep 27, 2022 |
| HP            | 1494                        | [aa2bd7da6c](https://linux-hardware.org/?probe=aa2bd7da6c) | Sep 26, 2022 |
| ASRock        | A75M-HVS                    | [75d51e6237](https://linux-hardware.org/?probe=75d51e6237) | Sep 26, 2022 |
| HP            | 0B40h                       | [d72bb749ff](https://linux-hardware.org/?probe=d72bb749ff) | Sep 26, 2022 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | [508c873693](https://linux-hardware.org/?probe=508c873693) | Sep 26, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | [762ad6e460](https://linux-hardware.org/?probe=762ad6e460) | Sep 26, 2022 |
| ASUSTek       | B150-PLUS                   | [c64181dd6a](https://linux-hardware.org/?probe=c64181dd6a) | Sep 25, 2022 |
| ASRockRack    | X570D4U-2L2T                | [779faa3cfd](https://linux-hardware.org/?probe=779faa3cfd) | Sep 25, 2022 |
| Dell          | 0Y2MRG A00                  | [af1ab104ed](https://linux-hardware.org/?probe=af1ab104ed) | Sep 25, 2022 |
| ASRock        | B450M-HDV                   | [a1639d1654](https://linux-hardware.org/?probe=a1639d1654) | Sep 25, 2022 |
| ASRock        | J3160M                      | [c9cc54f48e](https://linux-hardware.org/?probe=c9cc54f48e) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [208c7988f7](https://linux-hardware.org/?probe=208c7988f7) | Sep 25, 2022 |
| ASRock        | QC5000M-ITX/PH              | [571b95c201](https://linux-hardware.org/?probe=571b95c201) | Sep 25, 2022 |
| ASUSTek       | P8Z77-V DELUXE              | [cd57bfa69c](https://linux-hardware.org/?probe=cd57bfa69c) | Sep 24, 2022 |
| ASUSTek       | P8Z77-V DELUXE              | [bad1de13cc](https://linux-hardware.org/?probe=bad1de13cc) | Sep 24, 2022 |
| Medion        | MS-7616                     | [72af7b904f](https://linux-hardware.org/?probe=72af7b904f) | Sep 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [0daf5c5df5](https://linux-hardware.org/?probe=0daf5c5df5) | Sep 24, 2022 |
| Fujitsu Si... | MS-7504VP-PV                | [fa75c2dfde](https://linux-hardware.org/?probe=fa75c2dfde) | Sep 24, 2022 |
| MSI           | H510M PRO                   | [bb7475d072](https://linux-hardware.org/?probe=bb7475d072) | Sep 24, 2022 |
| ASRock        | X300M-STX                   | [c354f2b293](https://linux-hardware.org/?probe=c354f2b293) | Sep 24, 2022 |
| Lenovo        | NO DPK                      | [7bdaedd0f7](https://linux-hardware.org/?probe=7bdaedd0f7) | Sep 24, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [fd63352b24](https://linux-hardware.org/?probe=fd63352b24) | Sep 24, 2022 |
| MSI           | MS-7358                     | [29d88b0c3b](https://linux-hardware.org/?probe=29d88b0c3b) | Sep 23, 2022 |
| Medion        | B460H6-EM                   | [9ab2a06631](https://linux-hardware.org/?probe=9ab2a06631) | Sep 23, 2022 |
| ASRock        | A320M-DVS R4.0              | [42deee504b](https://linux-hardware.org/?probe=42deee504b) | Sep 23, 2022 |
| ASUSTek       | PRIME B365M-A               | [c4c88d72ae](https://linux-hardware.org/?probe=c4c88d72ae) | Sep 23, 2022 |
| HP            | 0AA8h                       | [9c02e3fc31](https://linux-hardware.org/?probe=9c02e3fc31) | Sep 23, 2022 |
| Fujitsu Si... | MS-7504VP-PV                | [f0916efbf9](https://linux-hardware.org/?probe=f0916efbf9) | Sep 23, 2022 |
| Gigabyte      | B660I AORUS PRO DDR4        | [810c7883d4](https://linux-hardware.org/?probe=810c7883d4) | Sep 23, 2022 |
| HP            | 876C SMVB                   | [c6fbf7c631](https://linux-hardware.org/?probe=c6fbf7c631) | Sep 23, 2022 |
| HP            | 1494                        | [cd3778e7eb](https://linux-hardware.org/?probe=cd3778e7eb) | Sep 22, 2022 |
| HP            | 1494                        | [4a3ad3e89d](https://linux-hardware.org/?probe=4a3ad3e89d) | Sep 22, 2022 |
| MSI           | X470 GAMING PRO             | [a48daa11cd](https://linux-hardware.org/?probe=a48daa11cd) | Sep 22, 2022 |
| ASUSTek       | M5A78L-M LX3                | [75a6fc3a08](https://linux-hardware.org/?probe=75a6fc3a08) | Sep 22, 2022 |
| ASUSTek       | M5A99X EVO                  | [48f4738047](https://linux-hardware.org/?probe=48f4738047) | Sep 22, 2022 |
| ASUSTek       | M5A99X EVO                  | [a484071017](https://linux-hardware.org/?probe=a484071017) | Sep 22, 2022 |
| ASUSTek       | B85M-E                      | [07477a078f](https://linux-hardware.org/?probe=07477a078f) | Sep 22, 2022 |
| HP            | 3647h                       | [7c54133b32](https://linux-hardware.org/?probe=7c54133b32) | Sep 22, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [f6e7ad269e](https://linux-hardware.org/?probe=f6e7ad269e) | Sep 22, 2022 |
| MSI           | 2A9C                        | [0c026ab669](https://linux-hardware.org/?probe=0c026ab669) | Sep 21, 2022 |
| BESSTAR Te... | UM350                       | [62a9723eb7](https://linux-hardware.org/?probe=62a9723eb7) | Sep 21, 2022 |
| ASUSTek       | A8N-SLI                     | [95d20defd7](https://linux-hardware.org/?probe=95d20defd7) | Sep 21, 2022 |
| MSI           | X470 GAMING PRO             | [5c64c61090](https://linux-hardware.org/?probe=5c64c61090) | Sep 21, 2022 |
| ASRock        | A75M-HVS                    | [0f81852612](https://linux-hardware.org/?probe=0f81852612) | Sep 21, 2022 |
| Lenovo        | ThinkCentre M81 5049W16     | [67067bfc09](https://linux-hardware.org/?probe=67067bfc09) | Sep 21, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [ed6f75ec9f](https://linux-hardware.org/?probe=ed6f75ec9f) | Sep 20, 2022 |
| HP            | 1589                        | [da376a40a1](https://linux-hardware.org/?probe=da376a40a1) | Sep 20, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1869422fde](https://linux-hardware.org/?probe=1869422fde) | Sep 20, 2022 |
| ASUSTek       | M5A99X EVO                  | [c59de2d375](https://linux-hardware.org/?probe=c59de2d375) | Sep 20, 2022 |
| MSI           | B450M PRO-VDH MAX           | [06d6be8b85](https://linux-hardware.org/?probe=06d6be8b85) | Sep 20, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [88b0561dbc](https://linux-hardware.org/?probe=88b0561dbc) | Sep 20, 2022 |
| Gigabyte      | EP45T-UD3R                  | [979765d106](https://linux-hardware.org/?probe=979765d106) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [a0a61b5d8c](https://linux-hardware.org/?probe=a0a61b5d8c) | Sep 20, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [bb8e3ae62a](https://linux-hardware.org/?probe=bb8e3ae62a) | Sep 20, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [37673aa4e2](https://linux-hardware.org/?probe=37673aa4e2) | Sep 20, 2022 |
| ASUSTek       | PRIME X470-PRO              | [a6857e4b03](https://linux-hardware.org/?probe=a6857e4b03) | Sep 19, 2022 |
| Dell          | 0GX297                      | [57e334a0c2](https://linux-hardware.org/?probe=57e334a0c2) | Sep 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7a1dbe2204](https://linux-hardware.org/?probe=7a1dbe2204) | Sep 19, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [8c4a94cb33](https://linux-hardware.org/?probe=8c4a94cb33) | Sep 19, 2022 |
| Foxconn       | 2ADA                        | [736a1c0eec](https://linux-hardware.org/?probe=736a1c0eec) | Sep 19, 2022 |
| ASRock        | AB350M-HDV                  | [22b753798c](https://linux-hardware.org/?probe=22b753798c) | Sep 19, 2022 |
| ASRock        | Z97 Anniversary             | [8c308a3e22](https://linux-hardware.org/?probe=8c308a3e22) | Sep 19, 2022 |
| MSI           | Z590-A PRO                  | [42bc6e4e69](https://linux-hardware.org/?probe=42bc6e4e69) | Sep 19, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [a479d9ef5f](https://linux-hardware.org/?probe=a479d9ef5f) | Sep 19, 2022 |
| ASRock        | Z590M-ITX/ax                | [d202b0a504](https://linux-hardware.org/?probe=d202b0a504) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ca1b76cefe](https://linux-hardware.org/?probe=ca1b76cefe) | Sep 19, 2022 |
| Gigabyte      | EP45-UD3                    | [3a6ef7d23b](https://linux-hardware.org/?probe=3a6ef7d23b) | Sep 19, 2022 |
| Lenovo        | ThinkCentre M71e 3157AE2    | [9022058466](https://linux-hardware.org/?probe=9022058466) | Sep 19, 2022 |
| Gigabyte      | Z77-DS3H                    | [5de472d6c0](https://linux-hardware.org/?probe=5de472d6c0) | Sep 18, 2022 |
| ASUSTek       | M5A97 R2.0                  | [a7b0a5d6f3](https://linux-hardware.org/?probe=a7b0a5d6f3) | Sep 18, 2022 |
| ASUSTek       | P7H55-M LX/USB3             | [76eedbf647](https://linux-hardware.org/?probe=76eedbf647) | Sep 18, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [543fad9f1c](https://linux-hardware.org/?probe=543fad9f1c) | Sep 18, 2022 |
| ASUSTek       | P7H55-M LX/USB3             | [95015c9edb](https://linux-hardware.org/?probe=95015c9edb) | Sep 18, 2022 |
| Medion        | MS-7707                     | [df4472374c](https://linux-hardware.org/?probe=df4472374c) | Sep 18, 2022 |
| Medion        | MS-7707                     | [248b893ed4](https://linux-hardware.org/?probe=248b893ed4) | Sep 18, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [21da8441d5](https://linux-hardware.org/?probe=21da8441d5) | Sep 18, 2022 |
| Lenovo        | ThinkStation D20 4158F76    | [d6b369855e](https://linux-hardware.org/?probe=d6b369855e) | Sep 18, 2022 |
| MSI           | MAG Z590 TORPEDO            | [2daced0309](https://linux-hardware.org/?probe=2daced0309) | Sep 17, 2022 |
| Biostar       | H410MH S2                   | [832dd81851](https://linux-hardware.org/?probe=832dd81851) | Sep 17, 2022 |
| ASUSTek       | M5A99X EVO                  | [5653a39e40](https://linux-hardware.org/?probe=5653a39e40) | Sep 17, 2022 |
| HP            | 0AECh D                     | [23adee752f](https://linux-hardware.org/?probe=23adee752f) | Sep 17, 2022 |
| Fujitsu       | D3617-A1 S26361-D3617-A1    | [51d9d832b7](https://linux-hardware.org/?probe=51d9d832b7) | Sep 17, 2022 |
| ASUSTek       | P8P67                       | [a790b35cc1](https://linux-hardware.org/?probe=a790b35cc1) | Sep 17, 2022 |
| Unknown       | Unknown                     | [e61dc9628f](https://linux-hardware.org/?probe=e61dc9628f) | Sep 17, 2022 |
| ASUSTek       | P5K                         | [4a3727841e](https://linux-hardware.org/?probe=4a3727841e) | Sep 17, 2022 |
| ASUSTek       | PRIME A520M-A II            | [0bec316a0b](https://linux-hardware.org/?probe=0bec316a0b) | Sep 17, 2022 |
| ASUSTek       | P8Z77-M                     | [c06544862e](https://linux-hardware.org/?probe=c06544862e) | Sep 16, 2022 |
| ASUSTek       | PRIME B365M-A               | [e191511194](https://linux-hardware.org/?probe=e191511194) | Sep 16, 2022 |
| Gigabyte      | 970A-DS3P                   | [c362a2f06e](https://linux-hardware.org/?probe=c362a2f06e) | Sep 16, 2022 |
| ASUSTek       | KCMA-D8                     | [dc8ecec94f](https://linux-hardware.org/?probe=dc8ecec94f) | Sep 16, 2022 |
| Dell          | 0X8582                      | [3498499960](https://linux-hardware.org/?probe=3498499960) | Sep 16, 2022 |
| Biostar       | A10N-8800E                  | [4a06fb8bfa](https://linux-hardware.org/?probe=4a06fb8bfa) | Sep 16, 2022 |
| HP            | 82F2 A01                    | [f97faeff54](https://linux-hardware.org/?probe=f97faeff54) | Sep 16, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [081d4b1d50](https://linux-hardware.org/?probe=081d4b1d50) | Sep 16, 2022 |
| ASUSTek       | P8Z68-V LX                  | [07dd87b76b](https://linux-hardware.org/?probe=07dd87b76b) | Sep 16, 2022 |
| Lenovo        | ThinkStation D20 4158F76    | [45a3f96ced](https://linux-hardware.org/?probe=45a3f96ced) | Sep 16, 2022 |
| MSI           | B450-A PRO MAX              | [c63f6d45b4](https://linux-hardware.org/?probe=c63f6d45b4) | Sep 16, 2022 |
| ASUSTek       | P5K-VM                      | [b0242689c2](https://linux-hardware.org/?probe=b0242689c2) | Sep 16, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [26699f7431](https://linux-hardware.org/?probe=26699f7431) | Sep 16, 2022 |
| Packard Be... | IMEDIA S3850                | [1fd4536a73](https://linux-hardware.org/?probe=1fd4536a73) | Sep 16, 2022 |
| Fujitsu       | D3028-A1 S26361-D3028-A1    | [b8262094b0](https://linux-hardware.org/?probe=b8262094b0) | Sep 16, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | [dcaf7e8bd0](https://linux-hardware.org/?probe=dcaf7e8bd0) | Sep 15, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [68749016d1](https://linux-hardware.org/?probe=68749016d1) | Sep 15, 2022 |
| Foxconn       | 2ADA                        | [812586d5e3](https://linux-hardware.org/?probe=812586d5e3) | Sep 15, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [875435f3f0](https://linux-hardware.org/?probe=875435f3f0) | Sep 15, 2022 |
| Acer          | FMP55                       | [6721345b03](https://linux-hardware.org/?probe=6721345b03) | Sep 15, 2022 |
| Gigabyte      | EP45T-UD3R                  | [007e9d4205](https://linux-hardware.org/?probe=007e9d4205) | Sep 15, 2022 |
| HP            | 3048h                       | [34d67ab175](https://linux-hardware.org/?probe=34d67ab175) | Sep 15, 2022 |
| HP            | 876C SMVB                   | [adc81b2fd5](https://linux-hardware.org/?probe=adc81b2fd5) | Sep 15, 2022 |
| ASUSTek       | H97I-PLUS                   | [5269bfb990](https://linux-hardware.org/?probe=5269bfb990) | Sep 14, 2022 |
| MSI           | B450-A PRO MAX              | [f1c8ae3891](https://linux-hardware.org/?probe=f1c8ae3891) | Sep 14, 2022 |
| Gigabyte      | P35C-DS3R                   | [eb49db3a8c](https://linux-hardware.org/?probe=eb49db3a8c) | Sep 14, 2022 |
| HP            | 1495                        | [462389df36](https://linux-hardware.org/?probe=462389df36) | Sep 14, 2022 |
| ASUSTek       | Maximus VIII RANGER         | [832824de54](https://linux-hardware.org/?probe=832824de54) | Sep 14, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [e7cb70c141](https://linux-hardware.org/?probe=e7cb70c141) | Sep 14, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [754d0f3a2b](https://linux-hardware.org/?probe=754d0f3a2b) | Sep 14, 2022 |
| Lenovo        | ThinkCentre M71e 3157AE2    | [d88e0026dc](https://linux-hardware.org/?probe=d88e0026dc) | Sep 14, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [175c84f6ea](https://linux-hardware.org/?probe=175c84f6ea) | Sep 13, 2022 |
| Gigabyte      | B365M H                     | [20125b1c13](https://linux-hardware.org/?probe=20125b1c13) | Sep 13, 2022 |
| ASUSTek       | M5A99X EVO                  | [a27df20eda](https://linux-hardware.org/?probe=a27df20eda) | Sep 13, 2022 |
| ASUSTek       | M5A99X EVO                  | [ae9712f9b3](https://linux-hardware.org/?probe=ae9712f9b3) | Sep 13, 2022 |
| ASUSTek       | P7P55 LX                    | [cc28ed218f](https://linux-hardware.org/?probe=cc28ed218f) | Sep 13, 2022 |
| HP            | 876C SMVB                   | [15ec81ce9d](https://linux-hardware.org/?probe=15ec81ce9d) | Sep 13, 2022 |
| HP            | 3647h                       | [c40ded9736](https://linux-hardware.org/?probe=c40ded9736) | Sep 13, 2022 |
| MSI           | Z97 MPOWER                  | [a98aedda05](https://linux-hardware.org/?probe=a98aedda05) | Sep 13, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [00bca0eeff](https://linux-hardware.org/?probe=00bca0eeff) | Sep 12, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [717942ca91](https://linux-hardware.org/?probe=717942ca91) | Sep 12, 2022 |
| Shuttle       | XH310V2                     | [c99efae947](https://linux-hardware.org/?probe=c99efae947) | Sep 12, 2022 |
| ASRock        | B450 Pro4                   | [d750223c3f](https://linux-hardware.org/?probe=d750223c3f) | Sep 12, 2022 |
| Gigabyte      | H81M-D2V                    | [6da1838df1](https://linux-hardware.org/?probe=6da1838df1) | Sep 12, 2022 |
| Gigabyte      | MQLP3AP-00                  | [b7dd480183](https://linux-hardware.org/?probe=b7dd480183) | Sep 12, 2022 |
| Unknown       | Unknown                     | [637418c4f3](https://linux-hardware.org/?probe=637418c4f3) | Sep 12, 2022 |
| ASUSTek       | Pro WS 565-ACE              | [e8da6da2b0](https://linux-hardware.org/?probe=e8da6da2b0) | Sep 12, 2022 |
| ASUSTek       | PRIME X370-PRO              | [2228f0dc13](https://linux-hardware.org/?probe=2228f0dc13) | Sep 12, 2022 |
| HP            | 304Bh                       | [0a7bcbdd9e](https://linux-hardware.org/?probe=0a7bcbdd9e) | Sep 11, 2022 |
| Gigabyte      | 970A-DS3P                   | [581cd5c8f3](https://linux-hardware.org/?probe=581cd5c8f3) | Sep 11, 2022 |
| Gigabyte      | G1.Sniper Z97               | [445e54016b](https://linux-hardware.org/?probe=445e54016b) | Sep 11, 2022 |
| Pegatron      | Benicia                     | [1f8dceb256](https://linux-hardware.org/?probe=1f8dceb256) | Sep 11, 2022 |
| Gigabyte      | Z77-DS3H                    | [7532844cd7](https://linux-hardware.org/?probe=7532844cd7) | Sep 11, 2022 |
| Dell          | 0GY6Y8 A03                  | [675c43f981](https://linux-hardware.org/?probe=675c43f981) | Sep 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1e43753d7a](https://linux-hardware.org/?probe=1e43753d7a) | Sep 10, 2022 |
| ASRock        | G41M-S3                     | [2cdcaebd43](https://linux-hardware.org/?probe=2cdcaebd43) | Sep 10, 2022 |
| ASUSTek       | M5A78L/USB3                 | [49158d0782](https://linux-hardware.org/?probe=49158d0782) | Sep 10, 2022 |
| MSI           | B550-A PRO                  | [f1bdda02e5](https://linux-hardware.org/?probe=f1bdda02e5) | Sep 10, 2022 |
| ASRock        | J3455B-ITX                  | [41d44c11cc](https://linux-hardware.org/?probe=41d44c11cc) | Sep 10, 2022 |
| ASUSTek       | H81M-E                      | [1a9835fb13](https://linux-hardware.org/?probe=1a9835fb13) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [5aa9031e93](https://linux-hardware.org/?probe=5aa9031e93) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [81fcfbb095](https://linux-hardware.org/?probe=81fcfbb095) | Sep 10, 2022 |
| HP            | 3647h                       | [a6a28c7e12](https://linux-hardware.org/?probe=a6a28c7e12) | Sep 10, 2022 |
| Gigabyte      | Z77X-D3H                    | [a81bea8a93](https://linux-hardware.org/?probe=a81bea8a93) | Sep 10, 2022 |
| Gigabyte      | Z77X-D3H                    | [aea58c6ced](https://linux-hardware.org/?probe=aea58c6ced) | Sep 10, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [7c5a6e51dc](https://linux-hardware.org/?probe=7c5a6e51dc) | Sep 09, 2022 |
| ASUSTek       | PRIME B550M-A               | [98fd9b974e](https://linux-hardware.org/?probe=98fd9b974e) | Sep 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [951a99cc8f](https://linux-hardware.org/?probe=951a99cc8f) | Sep 09, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [c6dac06569](https://linux-hardware.org/?probe=c6dac06569) | Sep 09, 2022 |
| ASRock        | B450M Pro4                  | [90b89510ba](https://linux-hardware.org/?probe=90b89510ba) | Sep 09, 2022 |
| Medion        | MS-7707                     | [b8489db42b](https://linux-hardware.org/?probe=b8489db42b) | Sep 08, 2022 |
| ASRock        | Q1900M                      | [aadbe54f8d](https://linux-hardware.org/?probe=aadbe54f8d) | Sep 08, 2022 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | [2c39df8b9f](https://linux-hardware.org/?probe=2c39df8b9f) | Sep 08, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [69216092ab](https://linux-hardware.org/?probe=69216092ab) | Sep 08, 2022 |
| ASRock        | B560 Steel Legend           | [1e26c1ce80](https://linux-hardware.org/?probe=1e26c1ce80) | Sep 08, 2022 |
| ASRock        | Q1900-ITX                   | [738bae7e52](https://linux-hardware.org/?probe=738bae7e52) | Sep 08, 2022 |
| ASUSTek       | PRIME B450M-K II            | [c7a272ed96](https://linux-hardware.org/?probe=c7a272ed96) | Sep 08, 2022 |
| ASRock        | Z390 Phantom Gaming 4S      | [146e7ebf49](https://linux-hardware.org/?probe=146e7ebf49) | Sep 08, 2022 |
| Pegatron      | Benicia                     | [95339a1bdd](https://linux-hardware.org/?probe=95339a1bdd) | Sep 08, 2022 |
| ASUSTek       | P8Z68-V GEN3                | [677554ca4b](https://linux-hardware.org/?probe=677554ca4b) | Sep 08, 2022 |
| HP            | 8460                        | [d74207aa28](https://linux-hardware.org/?probe=d74207aa28) | Sep 08, 2022 |
| ASUSTek       | H97-PRO                     | [fb4bfcf055](https://linux-hardware.org/?probe=fb4bfcf055) | Sep 07, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [a45b18c4bb](https://linux-hardware.org/?probe=a45b18c4bb) | Sep 07, 2022 |
| Medion        | H110H4-EM                   | [1b22e5560d](https://linux-hardware.org/?probe=1b22e5560d) | Sep 07, 2022 |
| ASRock        | Z170 Extreme4               | [70e3d85420](https://linux-hardware.org/?probe=70e3d85420) | Sep 07, 2022 |
| ASRock        | X300M-STX                   | [52f4b6e022](https://linux-hardware.org/?probe=52f4b6e022) | Sep 07, 2022 |
| ASRock        | N68-S3 UCC                  | [31fdd16d2f](https://linux-hardware.org/?probe=31fdd16d2f) | Sep 07, 2022 |
| ASUSTek       | P8H77-V                     | [c92f578a36](https://linux-hardware.org/?probe=c92f578a36) | Sep 07, 2022 |
| Gigabyte      | H310M S2H                   | [9a5564db94](https://linux-hardware.org/?probe=9a5564db94) | Sep 06, 2022 |
| Dell          | 0GY6Y8 A02                  | [10ac4ee2cb](https://linux-hardware.org/?probe=10ac4ee2cb) | Sep 06, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [8a66fbdadd](https://linux-hardware.org/?probe=8a66fbdadd) | Sep 06, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [dd20f0351c](https://linux-hardware.org/?probe=dd20f0351c) | Sep 06, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [3aca46f88b](https://linux-hardware.org/?probe=3aca46f88b) | Sep 06, 2022 |
| ASRock        | N68-S3 UCC                  | [24647846ee](https://linux-hardware.org/?probe=24647846ee) | Sep 06, 2022 |
| MSI           | Z97-G43                     | [eeea153bb2](https://linux-hardware.org/?probe=eeea153bb2) | Sep 06, 2022 |
| Unknown       | Unknown                     | [b88c3e55b5](https://linux-hardware.org/?probe=b88c3e55b5) | Sep 06, 2022 |
| Unknown       | Unknown                     | [cc2c8ef4c8](https://linux-hardware.org/?probe=cc2c8ef4c8) | Sep 06, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [2c5b0be3af](https://linux-hardware.org/?probe=2c5b0be3af) | Sep 06, 2022 |
| MSI           | Z87-G41 PC Mate             | [775e007fc8](https://linux-hardware.org/?probe=775e007fc8) | Sep 05, 2022 |
| ASUSTek       | KGPE-D16                    | [75e6c71399](https://linux-hardware.org/?probe=75e6c71399) | Sep 05, 2022 |
| Gigabyte      | Z690 UD DDR4                | [322fd169c2](https://linux-hardware.org/?probe=322fd169c2) | Sep 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [cbb8ba307c](https://linux-hardware.org/?probe=cbb8ba307c) | Sep 05, 2022 |
| Gigabyte      | Z370M DS3H-CF               | [e590a83122](https://linux-hardware.org/?probe=e590a83122) | Sep 05, 2022 |
| Gigabyte      | Z690 UD DDR4                | [8ff56070e0](https://linux-hardware.org/?probe=8ff56070e0) | Sep 05, 2022 |
| ASUSTek       | PRIME X299-A                | [b580e2e636](https://linux-hardware.org/?probe=b580e2e636) | Sep 05, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [889306ad51](https://linux-hardware.org/?probe=889306ad51) | Sep 04, 2022 |
| AMI           | Cherry Trail CR             | [63136bf463](https://linux-hardware.org/?probe=63136bf463) | Sep 04, 2022 |
| HP            | 8054                        | [878115f808](https://linux-hardware.org/?probe=878115f808) | Sep 04, 2022 |
| ASUSTek       | Z87-A                       | [d57a581b09](https://linux-hardware.org/?probe=d57a581b09) | Sep 04, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [319c882b9f](https://linux-hardware.org/?probe=319c882b9f) | Sep 04, 2022 |
| Gigabyte      | GA-970A-UD3                 | [670953f8b3](https://linux-hardware.org/?probe=670953f8b3) | Sep 04, 2022 |
| MSI           | H510M-A PRO                 | [7bb2d68f03](https://linux-hardware.org/?probe=7bb2d68f03) | Sep 04, 2022 |
| Gigabyte      | B560 AORUS PRO AX           | [fbd2e39516](https://linux-hardware.org/?probe=fbd2e39516) | Sep 04, 2022 |
| MSI           | B450-A PRO MAX              | [2be7ac6aad](https://linux-hardware.org/?probe=2be7ac6aad) | Sep 03, 2022 |
| Gigabyte      | GA-880GA-UD3H               | [14af0852b9](https://linux-hardware.org/?probe=14af0852b9) | Sep 03, 2022 |
| Gigabyte      | GA-970A-UD3                 | [f4c465d47c](https://linux-hardware.org/?probe=f4c465d47c) | Sep 03, 2022 |
| Gigabyte      | GA-880GA-UD3H               | [6c80288d39](https://linux-hardware.org/?probe=6c80288d39) | Sep 03, 2022 |
| ASRock        | Z370M-ITX/ac                | [0151fa47ef](https://linux-hardware.org/?probe=0151fa47ef) | Sep 03, 2022 |
| Gigabyte      | H77-D3H                     | [2d14cae483](https://linux-hardware.org/?probe=2d14cae483) | Sep 03, 2022 |
| Gigabyte      | H77-D3H                     | [b0b601dba0](https://linux-hardware.org/?probe=b0b601dba0) | Sep 03, 2022 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | [793f82cda7](https://linux-hardware.org/?probe=793f82cda7) | Sep 03, 2022 |
| ASRockRack    | X470D4U2/1N1                | [0be6c5963d](https://linux-hardware.org/?probe=0be6c5963d) | Sep 02, 2022 |
| ASUSTek       | P8B WS                      | [bd82f7708c](https://linux-hardware.org/?probe=bd82f7708c) | Sep 02, 2022 |
| HP            | ProLiant MicroServer        | [b7aa18986d](https://linux-hardware.org/?probe=b7aa18986d) | Sep 02, 2022 |
| HP            | ProLiant MicroServer        | [7ab65a419a](https://linux-hardware.org/?probe=7ab65a419a) | Sep 02, 2022 |
| ASRock        | Q1900-ITX                   | [3f3708d874](https://linux-hardware.org/?probe=3f3708d874) | Sep 02, 2022 |
| Gigabyte      | B550M DS3H                  | [acdd27f635](https://linux-hardware.org/?probe=acdd27f635) | Sep 02, 2022 |
| HP            | 8054                        | [1586ce33d1](https://linux-hardware.org/?probe=1586ce33d1) | Sep 02, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0789b27bdb](https://linux-hardware.org/?probe=0789b27bdb) | Sep 02, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | [3772ec2911](https://linux-hardware.org/?probe=3772ec2911) | Sep 02, 2022 |
| ASRockRack    | X470D4U2/1N1                | [2b524b9c24](https://linux-hardware.org/?probe=2b524b9c24) | Sep 01, 2022 |
| Gigabyte      | Z370 HD3-OP-CF              | [55f8dbfb24](https://linux-hardware.org/?probe=55f8dbfb24) | Sep 01, 2022 |
| Gigabyte      | Z370 HD3-OP-CF              | [ead5d021a7](https://linux-hardware.org/?probe=ead5d021a7) | Sep 01, 2022 |
| Gigabyte      | X150M-PRO ECC-CF            | [6db003ed3a](https://linux-hardware.org/?probe=6db003ed3a) | Sep 01, 2022 |
| Gigabyte      | X150M-PRO ECC-CF            | [2f21cd30ff](https://linux-hardware.org/?probe=2f21cd30ff) | Sep 01, 2022 |
| HP            | 81B4                        | [b81985e04e](https://linux-hardware.org/?probe=b81985e04e) | Aug 31, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [1dd7a06125](https://linux-hardware.org/?probe=1dd7a06125) | Aug 31, 2022 |
| ASRock        | Z77 Pro4-M                  | [d7c9a106e7](https://linux-hardware.org/?probe=d7c9a106e7) | Aug 31, 2022 |
| Packard Be... | WMCP78M                     | [93ead8d396](https://linux-hardware.org/?probe=93ead8d396) | Aug 31, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [eb74fdbbbc](https://linux-hardware.org/?probe=eb74fdbbbc) | Aug 30, 2022 |
| Dell          | 0R230R A00                  | [0ea749e83c](https://linux-hardware.org/?probe=0ea749e83c) | Aug 30, 2022 |
| MSI           | X79A-GD45                   | [bb940d6220](https://linux-hardware.org/?probe=bb940d6220) | Aug 30, 2022 |
| Fujitsu       | D3348-B1 S26361-D3348-B1    | [9721d1f81d](https://linux-hardware.org/?probe=9721d1f81d) | Aug 30, 2022 |
| ASUSTek       | M2N-TE                      | [82e7cc26e7](https://linux-hardware.org/?probe=82e7cc26e7) | Aug 30, 2022 |
| ASRock        | B450M Pro4 R2.0             | [d0ca11a18a](https://linux-hardware.org/?probe=d0ca11a18a) | Aug 29, 2022 |
| ASRock        | B450M Pro4 R2.0             | [fb155ef3bd](https://linux-hardware.org/?probe=fb155ef3bd) | Aug 29, 2022 |
| ASRock        | B85 Pro4                    | [db3bc987b6](https://linux-hardware.org/?probe=db3bc987b6) | Aug 29, 2022 |
| HP            | 18E5                        | [c40ab0e3e3](https://linux-hardware.org/?probe=c40ab0e3e3) | Aug 29, 2022 |
| HP            | ProLiant MicroServer Gen... | [b613af8e42](https://linux-hardware.org/?probe=b613af8e42) | Aug 29, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [9fbdc83458](https://linux-hardware.org/?probe=9fbdc83458) | Aug 29, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [7b0113a203](https://linux-hardware.org/?probe=7b0113a203) | Aug 29, 2022 |
| ASRock        | N68-S                       | [9d18792f64](https://linux-hardware.org/?probe=9d18792f64) | Aug 29, 2022 |
| MSI           | B75A-G41                    | [1d0e275f3e](https://linux-hardware.org/?probe=1d0e275f3e) | Aug 28, 2022 |
| ASUSTek       | M2N68-AM SE2                | [0f71a52e11](https://linux-hardware.org/?probe=0f71a52e11) | Aug 28, 2022 |
| Unknown       | 1.0                         | [38ebf9fce3](https://linux-hardware.org/?probe=38ebf9fce3) | Aug 28, 2022 |
| ASUSTek       | P7P55-M                     | [7a73291019](https://linux-hardware.org/?probe=7a73291019) | Aug 28, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [942675a80c](https://linux-hardware.org/?probe=942675a80c) | Aug 28, 2022 |
| MSI           | E350IA-E45                  | [d1d570a455](https://linux-hardware.org/?probe=d1d570a455) | Aug 28, 2022 |
| Gigabyte      | H67A-USB3-B3                | [b04fc1333e](https://linux-hardware.org/?probe=b04fc1333e) | Aug 28, 2022 |
| Lenovo        | SHARKBAY NOK                | [8571fd0486](https://linux-hardware.org/?probe=8571fd0486) | Aug 27, 2022 |
| Gigabyte      | B550 GAMING X V2            | [94e2f7cedc](https://linux-hardware.org/?probe=94e2f7cedc) | Aug 27, 2022 |
| HP            | 3647h                       | [c83122d4d4](https://linux-hardware.org/?probe=c83122d4d4) | Aug 27, 2022 |
| Dell          | 0G3HR7 A00                  | [500cf5a2b4](https://linux-hardware.org/?probe=500cf5a2b4) | Aug 27, 2022 |
| Dell          | 0G3HR7 A00                  | [f9671d44ad](https://linux-hardware.org/?probe=f9671d44ad) | Aug 27, 2022 |
| HP            | 2820h                       | [66e45394e9](https://linux-hardware.org/?probe=66e45394e9) | Aug 27, 2022 |
| ASUSTek       | A68HM-PLUS                  | [f585d57226](https://linux-hardware.org/?probe=f585d57226) | Aug 27, 2022 |
| ASRock        | FM2A68M-HD+                 | [22cc477cd2](https://linux-hardware.org/?probe=22cc477cd2) | Aug 26, 2022 |
| ASUSTek       | IPN73-BA                    | [89f8b175e2](https://linux-hardware.org/?probe=89f8b175e2) | Aug 26, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [dd68273352](https://linux-hardware.org/?probe=dd68273352) | Aug 26, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [d988a14a82](https://linux-hardware.org/?probe=d988a14a82) | Aug 26, 2022 |
| ASUSTek       | M5A78L-M LX                 | [5efc5cdd53](https://linux-hardware.org/?probe=5efc5cdd53) | Aug 25, 2022 |
| Dell          | 0F642F A00                  | [832cf31a6f](https://linux-hardware.org/?probe=832cf31a6f) | Aug 25, 2022 |
| MSI           | MS-7369                     | [3f701de216](https://linux-hardware.org/?probe=3f701de216) | Aug 25, 2022 |
| ASUSTek       | IPN73-BA                    | [da7e1db516](https://linux-hardware.org/?probe=da7e1db516) | Aug 25, 2022 |
| MSI           | A320M PRO-VD/S              | [676e223d96](https://linux-hardware.org/?probe=676e223d96) | Aug 25, 2022 |
| Gigabyte      | Z77X-D3H                    | [294fe7d6c8](https://linux-hardware.org/?probe=294fe7d6c8) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [94446a9884](https://linux-hardware.org/?probe=94446a9884) | Aug 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | [c37bc2a345](https://linux-hardware.org/?probe=c37bc2a345) | Aug 24, 2022 |
| ASRock        | AD2550-ITX                  | [79e491790d](https://linux-hardware.org/?probe=79e491790d) | Aug 24, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [8360395b95](https://linux-hardware.org/?probe=8360395b95) | Aug 24, 2022 |
| Gigabyte      | Z77X-D3H                    | [2952e542e1](https://linux-hardware.org/?probe=2952e542e1) | Aug 24, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [fdce8d9d0d](https://linux-hardware.org/?probe=fdce8d9d0d) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ae4a81a473](https://linux-hardware.org/?probe=ae4a81a473) | Aug 24, 2022 |
| HP            | 1906                        | [b26f30eca5](https://linux-hardware.org/?probe=b26f30eca5) | Aug 24, 2022 |
| IBASE Tech... | MI970VFA                    | [27fc0d8773](https://linux-hardware.org/?probe=27fc0d8773) | Aug 24, 2022 |
| Gigabyte      | H61M-D2H-USB3               | [eae2c82e26](https://linux-hardware.org/?probe=eae2c82e26) | Aug 23, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | [d396a491c2](https://linux-hardware.org/?probe=d396a491c2) | Aug 23, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [6e5a434d0d](https://linux-hardware.org/?probe=6e5a434d0d) | Aug 23, 2022 |
| HP            | 844C                        | [b56856200e](https://linux-hardware.org/?probe=b56856200e) | Aug 23, 2022 |
| ICP / iEi     | B217 V1.0                   | [9b540ece9f](https://linux-hardware.org/?probe=9b540ece9f) | Aug 23, 2022 |
| ASUSTek       | Pro B550M-C                 | [f0691dc9d8](https://linux-hardware.org/?probe=f0691dc9d8) | Aug 23, 2022 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [bb84a4e155](https://linux-hardware.org/?probe=bb84a4e155) | Aug 23, 2022 |
| MSI           | Z87-GD65 GAMING             | [f6f358dde8](https://linux-hardware.org/?probe=f6f358dde8) | Aug 23, 2022 |
| ASRock        | FM2A88M-HD+ R3.0            | [10973eca34](https://linux-hardware.org/?probe=10973eca34) | Aug 22, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [b0af95356c](https://linux-hardware.org/?probe=b0af95356c) | Aug 22, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [bc32a93168](https://linux-hardware.org/?probe=bc32a93168) | Aug 22, 2022 |
| ASUSTek       | A78M-E                      | [594e3ae5f4](https://linux-hardware.org/?probe=594e3ae5f4) | Aug 22, 2022 |
| MSI           | FM2-A55M-P33                | [3ff97d9be5](https://linux-hardware.org/?probe=3ff97d9be5) | Aug 22, 2022 |
| ASUSTek       | Z10PA-U8 Series             | [3e560a4018](https://linux-hardware.org/?probe=3e560a4018) | Aug 22, 2022 |
| ASRock        | X470 Taichi                 | [8f7d642c46](https://linux-hardware.org/?probe=8f7d642c46) | Aug 22, 2022 |
| ASRock        | Z97 Pro3                    | [a9f2cced08](https://linux-hardware.org/?probe=a9f2cced08) | Aug 22, 2022 |
| ASRock        | Z97 Pro3                    | [9590ddbb06](https://linux-hardware.org/?probe=9590ddbb06) | Aug 22, 2022 |
| Gigabyte      | H370 HD3-CF                 | [3f06afc812](https://linux-hardware.org/?probe=3f06afc812) | Aug 21, 2022 |
| MSI           | B550-A PRO                  | [421874f76a](https://linux-hardware.org/?probe=421874f76a) | Aug 21, 2022 |
| MSI           | P55-GD55                    | [89f2c92fa1](https://linux-hardware.org/?probe=89f2c92fa1) | Aug 21, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [c717f7c6d5](https://linux-hardware.org/?probe=c717f7c6d5) | Aug 21, 2022 |
| MSI           | A55M-E33                    | [80d29c4f23](https://linux-hardware.org/?probe=80d29c4f23) | Aug 20, 2022 |
| Packard Be... | WMCP78M                     | [f9cb5cf0a8](https://linux-hardware.org/?probe=f9cb5cf0a8) | Aug 20, 2022 |
| ASUSTek       | PRIME B450M-K II            | [6b101e9381](https://linux-hardware.org/?probe=6b101e9381) | Aug 19, 2022 |
| ASUSTek       | F2A55                       | [fbeb34e877](https://linux-hardware.org/?probe=fbeb34e877) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [4dc3a452d9](https://linux-hardware.org/?probe=4dc3a452d9) | Aug 19, 2022 |
| MSI           | Z77A-G45                    | [ff3c734303](https://linux-hardware.org/?probe=ff3c734303) | Aug 19, 2022 |
| ASUSTek       | M4A88T-M/USB3               | [2494475fe0](https://linux-hardware.org/?probe=2494475fe0) | Aug 19, 2022 |
| ASRock        | B450 Pro4                   | [ed013e82aa](https://linux-hardware.org/?probe=ed013e82aa) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d59342b7a4](https://linux-hardware.org/?probe=d59342b7a4) | Aug 19, 2022 |
| MSI           | MEG X570 UNIFY              | [e32743d60f](https://linux-hardware.org/?probe=e32743d60f) | Aug 19, 2022 |
| Gigabyte      | X299 AORUS MASTER           | [8d76a030ca](https://linux-hardware.org/?probe=8d76a030ca) | Aug 18, 2022 |
| ASUSTek       | H81M-E                      | [2b0b66767d](https://linux-hardware.org/?probe=2b0b66767d) | Aug 18, 2022 |
| BESSTAR Te... | UM350                       | [c7bb6b56fb](https://linux-hardware.org/?probe=c7bb6b56fb) | Aug 18, 2022 |
| Gigabyte      | B450M S2H                   | [a0a7a845e3](https://linux-hardware.org/?probe=a0a7a845e3) | Aug 18, 2022 |
| ASUSTek       | Z97-E                       | [aa95967c03](https://linux-hardware.org/?probe=aa95967c03) | Aug 18, 2022 |
| Lenovo        | SHARKBAY NOK                | [e73d7ae317](https://linux-hardware.org/?probe=e73d7ae317) | Aug 17, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [c4336ae88d](https://linux-hardware.org/?probe=c4336ae88d) | Aug 17, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [8911aeaaaf](https://linux-hardware.org/?probe=8911aeaaaf) | Aug 17, 2022 |
| MSI           | Z87-G41 PC Mate             | [08e79a0a1c](https://linux-hardware.org/?probe=08e79a0a1c) | Aug 16, 2022 |
| MSI           | Z170A GAMING M3             | [e0834224d7](https://linux-hardware.org/?probe=e0834224d7) | Aug 16, 2022 |
| Gigabyte      | H81M-D2V                    | [aa03343ca1](https://linux-hardware.org/?probe=aa03343ca1) | Aug 16, 2022 |
| Gigabyte      | GA-880GMA-UD2H              | [4dae42f9b2](https://linux-hardware.org/?probe=4dae42f9b2) | Aug 16, 2022 |
| MSI           | B450-A PRO MAX              | [8341abd9e2](https://linux-hardware.org/?probe=8341abd9e2) | Aug 16, 2022 |
| ASRock        | B450 Pro4                   | [79f5c08bff](https://linux-hardware.org/?probe=79f5c08bff) | Aug 15, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [d01ce7811a](https://linux-hardware.org/?probe=d01ce7811a) | Aug 15, 2022 |
| MSI           | MAG B560 TORPEDO            | [4a2ce50049](https://linux-hardware.org/?probe=4a2ce50049) | Aug 15, 2022 |
| HP            | 339A                        | [c3e5458c9a](https://linux-hardware.org/?probe=c3e5458c9a) | Aug 15, 2022 |
| ASUSTek       | WS C422 DC                  | [92d816348a](https://linux-hardware.org/?probe=92d816348a) | Aug 15, 2022 |
| Gigabyte      | H81M-D2V                    | [76ab505e7c](https://linux-hardware.org/?probe=76ab505e7c) | Aug 14, 2022 |
| MSI           | X570-A PRO                  | [30146876c6](https://linux-hardware.org/?probe=30146876c6) | Aug 14, 2022 |
| MSI           | Boston                      | [aa89e501bd](https://linux-hardware.org/?probe=aa89e501bd) | Aug 14, 2022 |
| MSI           | H510M PRO                   | [30a01dd713](https://linux-hardware.org/?probe=30a01dd713) | Aug 14, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | [58d97fbc16](https://linux-hardware.org/?probe=58d97fbc16) | Aug 14, 2022 |
| ASRock        | 970 Pro3 R2.0               | [3c5d50938d](https://linux-hardware.org/?probe=3c5d50938d) | Aug 14, 2022 |
| MSI           | A320M PRO-E                 | [2aa966d8af](https://linux-hardware.org/?probe=2aa966d8af) | Aug 14, 2022 |
| Lenovo        | SHARKBAY NOK                | [ee169e47b3](https://linux-hardware.org/?probe=ee169e47b3) | Aug 13, 2022 |
| ASRock        | H67M                        | [c09d83ca79](https://linux-hardware.org/?probe=c09d83ca79) | Aug 13, 2022 |
| HP            | 8906 SMVB                   | [9aeadd926d](https://linux-hardware.org/?probe=9aeadd926d) | Aug 13, 2022 |
| HP            | 8906 SMVB                   | [4f7bbd7462](https://linux-hardware.org/?probe=4f7bbd7462) | Aug 13, 2022 |
| MSI           | Boston                      | [890c944be0](https://linux-hardware.org/?probe=890c944be0) | Aug 12, 2022 |
| MSI           | B450 TOMAHAWK               | [8d95c82a1d](https://linux-hardware.org/?probe=8d95c82a1d) | Aug 12, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [f82761570b](https://linux-hardware.org/?probe=f82761570b) | Aug 12, 2022 |
| MSI           | Z97 GAMING 5                | [e7c81a6ce7](https://linux-hardware.org/?probe=e7c81a6ce7) | Aug 12, 2022 |
| Nvidia        | FN68PT V10                  | [41303a45d7](https://linux-hardware.org/?probe=41303a45d7) | Aug 11, 2022 |
| HP            | 2B4B                        | [6763057a55](https://linux-hardware.org/?probe=6763057a55) | Aug 11, 2022 |
| MSI           | X570-A PRO                  | [63ca983715](https://linux-hardware.org/?probe=63ca983715) | Aug 11, 2022 |
| MSI           | Z87-G45 GAMING              | [5f25d77994](https://linux-hardware.org/?probe=5f25d77994) | Aug 11, 2022 |
| ASUSTek       | PRIME B250-PRO              | [0b8d707dbe](https://linux-hardware.org/?probe=0b8d707dbe) | Aug 11, 2022 |
| MSI           | Z87-G45 GAMING              | [0790b09ae3](https://linux-hardware.org/?probe=0790b09ae3) | Aug 11, 2022 |
| Pegatron      | Benicia                     | [8b8224cb4b](https://linux-hardware.org/?probe=8b8224cb4b) | Aug 11, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [3cfba5bad8](https://linux-hardware.org/?probe=3cfba5bad8) | Aug 11, 2022 |
| Lenovo        | ThinkCentre M81 5049W16     | [5035953069](https://linux-hardware.org/?probe=5035953069) | Aug 10, 2022 |
| Dell          | 042P49 A00                  | [6556e46383](https://linux-hardware.org/?probe=6556e46383) | Aug 10, 2022 |
| Intel         | DH87RL AAG74240-402         | [a83fd820d4](https://linux-hardware.org/?probe=a83fd820d4) | Aug 10, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [2696ad6f3e](https://linux-hardware.org/?probe=2696ad6f3e) | Aug 10, 2022 |
| Unknown       | QNAP TS-221                 | [8d3f7ca9cf](https://linux-hardware.org/?probe=8d3f7ca9cf) | Aug 10, 2022 |
| ASUSTek       | PRIME Z390-A                | [2781a13b80](https://linux-hardware.org/?probe=2781a13b80) | Aug 10, 2022 |
| ASUSTek       | PRIME B450M-K               | [ed054f1da7](https://linux-hardware.org/?probe=ed054f1da7) | Aug 10, 2022 |
| Intel         | DH87RL AAG74240-402         | [8ea693190b](https://linux-hardware.org/?probe=8ea693190b) | Aug 09, 2022 |
| ASUSTek       | PRIME B450M-A               | [d5ddfb6210](https://linux-hardware.org/?probe=d5ddfb6210) | Aug 09, 2022 |
| MSI           | B550-A PRO                  | [b9fb53384c](https://linux-hardware.org/?probe=b9fb53384c) | Aug 09, 2022 |
| ASUSTek       | PRIME X370-PRO              | [73e439f7f9](https://linux-hardware.org/?probe=73e439f7f9) | Aug 09, 2022 |
| MSI           | Z87-G45 GAMING              | [093a936372](https://linux-hardware.org/?probe=093a936372) | Aug 08, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [935f3a82af](https://linux-hardware.org/?probe=935f3a82af) | Aug 08, 2022 |
| MSI           | A320M-A PRO MAX             | [9ee274e581](https://linux-hardware.org/?probe=9ee274e581) | Aug 08, 2022 |
| HP            | 18E7                        | [7dd119f85e](https://linux-hardware.org/?probe=7dd119f85e) | Aug 08, 2022 |
| Lenovo        | MAHOBAY NOK                 | [6018df068b](https://linux-hardware.org/?probe=6018df068b) | Aug 08, 2022 |
| Acer          | FMP55                       | [89d529dd4b](https://linux-hardware.org/?probe=89d529dd4b) | Aug 07, 2022 |
| HP            | 1589                        | [0827fa8662](https://linux-hardware.org/?probe=0827fa8662) | Aug 07, 2022 |
| Foxconn       | 2ACA                        | [2ede4f1763](https://linux-hardware.org/?probe=2ede4f1763) | Aug 07, 2022 |
| HP            | 8768 A                      | [2ee49e3506](https://linux-hardware.org/?probe=2ee49e3506) | Aug 07, 2022 |
| ASUSTek       | P5Q                         | [f45edaf8a6](https://linux-hardware.org/?probe=f45edaf8a6) | Aug 07, 2022 |
| ASUSTek       | P5Q                         | [e07c48b40d](https://linux-hardware.org/?probe=e07c48b40d) | Aug 07, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [67934f8ed6](https://linux-hardware.org/?probe=67934f8ed6) | Aug 07, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [d6d5cc239f](https://linux-hardware.org/?probe=d6d5cc239f) | Aug 07, 2022 |
| ASRock        | B450M-HDV R4.0              | [ec538ff66a](https://linux-hardware.org/?probe=ec538ff66a) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | [fb01882d07](https://linux-hardware.org/?probe=fb01882d07) | Aug 06, 2022 |
| MSI           | FM2-A55M-P33                | [d7a868f0af](https://linux-hardware.org/?probe=d7a868f0af) | Aug 06, 2022 |
| Biostar       | B550MX/E PRO                | [53596a82d1](https://linux-hardware.org/?probe=53596a82d1) | Aug 06, 2022 |
| Gigabyte      | 970A-DS3P                   | [23905636a4](https://linux-hardware.org/?probe=23905636a4) | Aug 06, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [c6d818b28f](https://linux-hardware.org/?probe=c6d818b28f) | Aug 06, 2022 |
| BESSTAR Te... | HM90                        | [36e148426c](https://linux-hardware.org/?probe=36e148426c) | Aug 06, 2022 |
| BESSTAR Te... | HM90                        | [28ec23aa22](https://linux-hardware.org/?probe=28ec23aa22) | Aug 06, 2022 |
| Gigabyte      | B550 GAMING X V2            | [5e1b4032ae](https://linux-hardware.org/?probe=5e1b4032ae) | Aug 05, 2022 |
| ASRock        | A300M-STX                   | [f6b820d15f](https://linux-hardware.org/?probe=f6b820d15f) | Aug 05, 2022 |
| Gigabyte      | B660I AORUS PRO DDR4        | [0a0341c481](https://linux-hardware.org/?probe=0a0341c481) | Aug 05, 2022 |
| Dell          | 0XR1GT A00                  | [2e069ba5c2](https://linux-hardware.org/?probe=2e069ba5c2) | Aug 04, 2022 |
| Gigabyte      | H87-HD3                     | [afc72e5375](https://linux-hardware.org/?probe=afc72e5375) | Aug 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [7a60eede9a](https://linux-hardware.org/?probe=7a60eede9a) | Aug 04, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [56b0b42020](https://linux-hardware.org/?probe=56b0b42020) | Aug 04, 2022 |
| MSI           | X99A TOMAHAWK               | [731716b865](https://linux-hardware.org/?probe=731716b865) | Aug 04, 2022 |
| ASRock        | H77 Pro4-M                  | [71ffad2942](https://linux-hardware.org/?probe=71ffad2942) | Aug 04, 2022 |
| ASUSTek       | PRIME B450M-A               | [fc5ee0d2f9](https://linux-hardware.org/?probe=fc5ee0d2f9) | Aug 04, 2022 |
| Lenovo        | ThinkCentre M58 7373AJ5     | [adcf756453](https://linux-hardware.org/?probe=adcf756453) | Aug 04, 2022 |
| ASUSTek       | PRIME X370-PRO              | [3ff2577782](https://linux-hardware.org/?probe=3ff2577782) | Aug 04, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [d8ac4382e8](https://linux-hardware.org/?probe=d8ac4382e8) | Aug 03, 2022 |
| Lenovo        | 3714 SDK0J40700 WIN 3258... | [e5afdebd04](https://linux-hardware.org/?probe=e5afdebd04) | Aug 03, 2022 |
| Gigabyte      | Z690 UD DDR4                | [3225b48633](https://linux-hardware.org/?probe=3225b48633) | Aug 03, 2022 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | [9c48743761](https://linux-hardware.org/?probe=9c48743761) | Aug 02, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [82291dc9a5](https://linux-hardware.org/?probe=82291dc9a5) | Aug 02, 2022 |
| Dell          | 0GY6Y8 A03                  | [bd49c779fa](https://linux-hardware.org/?probe=bd49c779fa) | Aug 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | [049607c94a](https://linux-hardware.org/?probe=049607c94a) | Aug 02, 2022 |
| Dell          | 0GY6Y8 A03                  | [09ba22e06b](https://linux-hardware.org/?probe=09ba22e06b) | Aug 02, 2022 |
| ASRock        | B450 Pro4                   | [aacc138812](https://linux-hardware.org/?probe=aacc138812) | Aug 02, 2022 |
| ASRock        | X370 Taichi                 | [7d13857a3a](https://linux-hardware.org/?probe=7d13857a3a) | Aug 02, 2022 |
| ASRock        | A300M-STX                   | [a6aba67197](https://linux-hardware.org/?probe=a6aba67197) | Aug 02, 2022 |
| ASRock        | A300M-STX                   | [fae724727b](https://linux-hardware.org/?probe=fae724727b) | Aug 02, 2022 |
| ASRock        | E350M1                      | [87efe56c26](https://linux-hardware.org/?probe=87efe56c26) | Aug 01, 2022 |
| MSI           | X370 KRAIT GAMING           | [fe950a68a3](https://linux-hardware.org/?probe=fe950a68a3) | Aug 01, 2022 |
| ASUSTek       | F2A55-M LK2                 | [97a5e9c390](https://linux-hardware.org/?probe=97a5e9c390) | Aug 01, 2022 |
| ASUSTek       | M2A-VM                      | [4b1dabbf52](https://linux-hardware.org/?probe=4b1dabbf52) | Aug 01, 2022 |
| ASUSTek       | Maximus IX FORMULA          | [2212732244](https://linux-hardware.org/?probe=2212732244) | Aug 01, 2022 |
| Acer          | Veriton M4620G v1.0         | [13304f7d9e](https://linux-hardware.org/?probe=13304f7d9e) | Jul 31, 2022 |
| Dell          | 0T656F A01                  | [02ae993867](https://linux-hardware.org/?probe=02ae993867) | Jul 31, 2022 |
| ASRock        | AB350 Pro4                  | [c300f62638](https://linux-hardware.org/?probe=c300f62638) | Jul 31, 2022 |
| ASRock        | N68-S3 UCC                  | [bcb1d1da28](https://linux-hardware.org/?probe=bcb1d1da28) | Jul 31, 2022 |
| ASUSTek       | P8B75-M LX                  | [653f46c8e3](https://linux-hardware.org/?probe=653f46c8e3) | Jul 31, 2022 |
| MSI           | X399 SLI PLUS               | [515c5375c1](https://linux-hardware.org/?probe=515c5375c1) | Jul 31, 2022 |
| ASUSTek       | PRIME X370-PRO              | [80007c0939](https://linux-hardware.org/?probe=80007c0939) | Jul 31, 2022 |
| MSI           | B85M-P33                    | [6e9af1d1e4](https://linux-hardware.org/?probe=6e9af1d1e4) | Jul 31, 2022 |
| ASUSTek       | PRIME X399-A                | [4fba223020](https://linux-hardware.org/?probe=4fba223020) | Jul 31, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | [cc1944f4a3](https://linux-hardware.org/?probe=cc1944f4a3) | Jul 31, 2022 |
| MSI           | MEG Z690 UNIFY              | [571f500e5e](https://linux-hardware.org/?probe=571f500e5e) | Jul 30, 2022 |
| ASRock        | Z390 Extreme4               | [670d8c5f1e](https://linux-hardware.org/?probe=670d8c5f1e) | Jul 30, 2022 |
| Dell          | 06NWYK A00                  | [1182388bb6](https://linux-hardware.org/?probe=1182388bb6) | Jul 30, 2022 |
| MSI           | MS-7418 100                 | [c17e48cc2b](https://linux-hardware.org/?probe=c17e48cc2b) | Jul 30, 2022 |
| MSI           | MS-7418 100                 | [4644e4eaa8](https://linux-hardware.org/?probe=4644e4eaa8) | Jul 30, 2022 |
| ASUSTek       | P8B75-M                     | [ddf26da899](https://linux-hardware.org/?probe=ddf26da899) | Jul 30, 2022 |
| ASRock        | Z390 Extreme4               | [8130877fa3](https://linux-hardware.org/?probe=8130877fa3) | Jul 30, 2022 |
| MSI           | B450M MORTAR MAX            | [1316e90024](https://linux-hardware.org/?probe=1316e90024) | Jul 30, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [3b1f863612](https://linux-hardware.org/?probe=3b1f863612) | Jul 30, 2022 |
| MSI           | X470 GAMING PRO MAX         | [5651db0a63](https://linux-hardware.org/?probe=5651db0a63) | Jul 30, 2022 |
| Gigabyte      | 970A-DS3                    | [78f00bd2aa](https://linux-hardware.org/?probe=78f00bd2aa) | Jul 30, 2022 |
| ASUSTek       | PRIME Z590-P                | [a90cc43a4b](https://linux-hardware.org/?probe=a90cc43a4b) | Jul 29, 2022 |
| Gigabyte      | GA-890XA-UD3                | [b05155fd03](https://linux-hardware.org/?probe=b05155fd03) | Jul 29, 2022 |
| Gigabyte      | H77-D3H                     | [a1b47c2f81](https://linux-hardware.org/?probe=a1b47c2f81) | Jul 29, 2022 |
| ASRock        | B85 Pro4                    | [98e02ef2cd](https://linux-hardware.org/?probe=98e02ef2cd) | Jul 29, 2022 |
| ASUSTek       | Z87-PRO                     | [715fac7551](https://linux-hardware.org/?probe=715fac7551) | Jul 29, 2022 |
| ASRock        | B85 Pro4                    | [ec68a40236](https://linux-hardware.org/?probe=ec68a40236) | Jul 29, 2022 |
| Biostar       | A880G+                      | [5f10c78e54](https://linux-hardware.org/?probe=5f10c78e54) | Jul 29, 2022 |
| Gigabyte      | H510M S2H                   | [7c42ac18e4](https://linux-hardware.org/?probe=7c42ac18e4) | Jul 29, 2022 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | [d3d824f468](https://linux-hardware.org/?probe=d3d824f468) | Jul 29, 2022 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [902ee3b350](https://linux-hardware.org/?probe=902ee3b350) | Jul 29, 2022 |
| MSI           | B450M MORTAR                | [29a26324b9](https://linux-hardware.org/?probe=29a26324b9) | Jul 29, 2022 |
| ASUSTek       | P8B75-M LX                  | [af972287a0](https://linux-hardware.org/?probe=af972287a0) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-K               | [aa77364c9c](https://linux-hardware.org/?probe=aa77364c9c) | Jul 29, 2022 |
| Gigabyte      | P55M-UD2                    | [1920d703bb](https://linux-hardware.org/?probe=1920d703bb) | Jul 28, 2022 |
| Gigabyte      | B550M AORUS PRO             | [7a5337e18d](https://linux-hardware.org/?probe=7a5337e18d) | Jul 28, 2022 |
| MSI           | B550-A PRO                  | [f597d7cc46](https://linux-hardware.org/?probe=f597d7cc46) | Jul 28, 2022 |
| ASUSTek       | H97-PRO                     | [ca77f59b41](https://linux-hardware.org/?probe=ca77f59b41) | Jul 28, 2022 |
| MSI           | B550-A PRO                  | [2ae0b5a47a](https://linux-hardware.org/?probe=2ae0b5a47a) | Jul 28, 2022 |
| Biostar       | B365MHC                     | [9defcd36e9](https://linux-hardware.org/?probe=9defcd36e9) | Jul 28, 2022 |
| ASUSTek       | H110M-A/M.2                 | [93ad7b0efb](https://linux-hardware.org/?probe=93ad7b0efb) | Jul 28, 2022 |
| ASUSTek       | Z170-A                      | [47f6481e91](https://linux-hardware.org/?probe=47f6481e91) | Jul 28, 2022 |
| ASUSTek       | EB1012G                     | [45c78b3ee4](https://linux-hardware.org/?probe=45c78b3ee4) | Jul 28, 2022 |
| ASRock        | X300M-STX                   | [859f2b1a9c](https://linux-hardware.org/?probe=859f2b1a9c) | Jul 27, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [d0ef6d20cf](https://linux-hardware.org/?probe=d0ef6d20cf) | Jul 27, 2022 |
| Gigabyte      | 970A-UD3P                   | [0d503b2789](https://linux-hardware.org/?probe=0d503b2789) | Jul 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [55318bcefe](https://linux-hardware.org/?probe=55318bcefe) | Jul 27, 2022 |
| MSI           | B250M PRO-VDH               | [eb1ff40d2d](https://linux-hardware.org/?probe=eb1ff40d2d) | Jul 27, 2022 |
| Acer          | EG43M                       | [962c69e9fd](https://linux-hardware.org/?probe=962c69e9fd) | Jul 27, 2022 |
| Dell          | 0200DY A02                  | [40abd530f4](https://linux-hardware.org/?probe=40abd530f4) | Jul 27, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | [85378ff84a](https://linux-hardware.org/?probe=85378ff84a) | Jul 27, 2022 |
| Acer          | IPXHW-RL                    | [d99b7cb71e](https://linux-hardware.org/?probe=d99b7cb71e) | Jul 27, 2022 |
| Medion        | MS-7728                     | [662e3948f2](https://linux-hardware.org/?probe=662e3948f2) | Jul 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [cb4bc3fa42](https://linux-hardware.org/?probe=cb4bc3fa42) | Jul 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | [9f5bf108ac](https://linux-hardware.org/?probe=9f5bf108ac) | Jul 27, 2022 |
| MSI           | B550-A PRO                  | [b924a924e0](https://linux-hardware.org/?probe=b924a924e0) | Jul 27, 2022 |
| Dell          | 06NWYK A00                  | [effad14bc0](https://linux-hardware.org/?probe=effad14bc0) | Jul 26, 2022 |
| Gigabyte      | Z590 AORUS MASTER           | [300ddea4d6](https://linux-hardware.org/?probe=300ddea4d6) | Jul 26, 2022 |
| Gigabyte      | Z370 AORUS Gaming 7         | [6cb2605585](https://linux-hardware.org/?probe=6cb2605585) | Jul 26, 2022 |
| ASUSTek       | P8B75-M                     | [46e85f96ca](https://linux-hardware.org/?probe=46e85f96ca) | Jul 26, 2022 |
| ASRock        | J5005-ITX                   | [36313bb369](https://linux-hardware.org/?probe=36313bb369) | Jul 26, 2022 |
| Gigabyte      | Z590 GAMING X               | [6701685bb5](https://linux-hardware.org/?probe=6701685bb5) | Jul 26, 2022 |
| MSI           | B450M PRO-VDH MAX           | [941092ee95](https://linux-hardware.org/?probe=941092ee95) | Jul 26, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [9d3da43bea](https://linux-hardware.org/?probe=9d3da43bea) | Jul 25, 2022 |
| ASRock        | M3A785GMH/128M              | [87836918b2](https://linux-hardware.org/?probe=87836918b2) | Jul 25, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [3a34e9c018](https://linux-hardware.org/?probe=3a34e9c018) | Jul 25, 2022 |
| Medion        | MS-7797                     | [9ad7252b8a](https://linux-hardware.org/?probe=9ad7252b8a) | Jul 25, 2022 |
| MSI           | H510M PRO                   | [07c98d99d5](https://linux-hardware.org/?probe=07c98d99d5) | Jul 25, 2022 |
| MSI           | H510M PRO                   | [e8693a9212](https://linux-hardware.org/?probe=e8693a9212) | Jul 25, 2022 |
| ASRockRack    | B565D4-V1L                  | [1301ad9bd0](https://linux-hardware.org/?probe=1301ad9bd0) | Jul 25, 2022 |
| ASUSTek       | A78M-E                      | [50b987b79d](https://linux-hardware.org/?probe=50b987b79d) | Jul 25, 2022 |
| ASRock        | H81M-HDS                    | [b3f2310571](https://linux-hardware.org/?probe=b3f2310571) | Jul 24, 2022 |
| Dell          | 03NVJ6 A03                  | [9c0bb64bd9](https://linux-hardware.org/?probe=9c0bb64bd9) | Jul 24, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [221bb14fbd](https://linux-hardware.org/?probe=221bb14fbd) | Jul 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a1aa08113d](https://linux-hardware.org/?probe=a1aa08113d) | Jul 24, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [d0a69fba02](https://linux-hardware.org/?probe=d0a69fba02) | Jul 23, 2022 |
| HP            | 339A                        | [313af629be](https://linux-hardware.org/?probe=313af629be) | Jul 23, 2022 |
| MSI           | 970 GAMING                  | [2814270f24](https://linux-hardware.org/?probe=2814270f24) | Jul 23, 2022 |
| ASUSTek       | PRIME B450M-A               | [b0e3bc86bc](https://linux-hardware.org/?probe=b0e3bc86bc) | Jul 23, 2022 |
| ASUSTek       | PRIME B450M-A               | [8288af270f](https://linux-hardware.org/?probe=8288af270f) | Jul 23, 2022 |
| HP            | 08B4h                       | [8ff662507a](https://linux-hardware.org/?probe=8ff662507a) | Jul 22, 2022 |
| MSI           | Z77A-GD65                   | [f0cf5d1f55](https://linux-hardware.org/?probe=f0cf5d1f55) | Jul 22, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | [a57ab4e2dc](https://linux-hardware.org/?probe=a57ab4e2dc) | Jul 22, 2022 |
| MSI           | Z77A-GD65                   | [edfa6cb848](https://linux-hardware.org/?probe=edfa6cb848) | Jul 22, 2022 |
| Biostar       | A10N-8800E                  | [3f61195f75](https://linux-hardware.org/?probe=3f61195f75) | Jul 22, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [51c2b5bc3b](https://linux-hardware.org/?probe=51c2b5bc3b) | Jul 22, 2022 |
| HP            | 0AECh D                     | [ca7abdaae0](https://linux-hardware.org/?probe=ca7abdaae0) | Jul 22, 2022 |
| Dell          | 0GY6Y8 A03                  | [88d49ee4d4](https://linux-hardware.org/?probe=88d49ee4d4) | Jul 21, 2022 |
| ASUSTek       | P9X79                       | [5ff04691ce](https://linux-hardware.org/?probe=5ff04691ce) | Jul 21, 2022 |
| Dell          | 0GY6Y8 A03                  | [636819dfaf](https://linux-hardware.org/?probe=636819dfaf) | Jul 21, 2022 |
| ASUSTek       | P9X79                       | [1bcee43b6e](https://linux-hardware.org/?probe=1bcee43b6e) | Jul 21, 2022 |
| Unknown       | QNAP TS-221                 | [fb3741faab](https://linux-hardware.org/?probe=fb3741faab) | Jul 21, 2022 |
| Gigabyte      | G41MT-S2PT                  | [b291af1e34](https://linux-hardware.org/?probe=b291af1e34) | Jul 21, 2022 |
| Gigabyte      | 970A-DS3P                   | [379da1a196](https://linux-hardware.org/?probe=379da1a196) | Jul 21, 2022 |
| Gigabyte      | 970A-DS3P                   | [4a2e56ae7b](https://linux-hardware.org/?probe=4a2e56ae7b) | Jul 21, 2022 |
| HP            | 8054                        | [466d7f5591](https://linux-hardware.org/?probe=466d7f5591) | Jul 21, 2022 |
| HP            | 18E9                        | [f15b2671b0](https://linux-hardware.org/?probe=f15b2671b0) | Jul 21, 2022 |
| Pegatron      | Benicia                     | [f197aeb457](https://linux-hardware.org/?probe=f197aeb457) | Jul 21, 2022 |
| ASRock        | B450 Pro4                   | [7037061aed](https://linux-hardware.org/?probe=7037061aed) | Jul 20, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS        | [468283ab86](https://linux-hardware.org/?probe=468283ab86) | Jul 20, 2022 |
| Foxconn       | 2AAF                        | [b97dc9fd47](https://linux-hardware.org/?probe=b97dc9fd47) | Jul 20, 2022 |
| Acer          | EQ45M                       | [53a74d39e4](https://linux-hardware.org/?probe=53a74d39e4) | Jul 20, 2022 |
| Gigabyte      | Z77N-WIFI                   | [a29cfe60ae](https://linux-hardware.org/?probe=a29cfe60ae) | Jul 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [d5ebe1a737](https://linux-hardware.org/?probe=d5ebe1a737) | Jul 20, 2022 |
| ASUSTek       | P8H61/USB3 R2.0             | [1076f6d59a](https://linux-hardware.org/?probe=1076f6d59a) | Jul 19, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Germany/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 1192     | 17.1%   |
| Ubuntu 18.04                 | 539      | 7.73%   |
| OpenMandriva 4.2             | 258      | 3.7%    |
| OpenMandriva 4.3             | 233      | 3.34%   |
| Linux Mint 20.2              | 221      | 3.17%   |
| Linux Mint 20.3              | 202      | 2.9%    |
| Ubuntu 22.04                 | 194      | 2.78%   |
| Debian 11                    | 143      | 2.05%   |
| Ubuntu 21.10                 | 142      | 2.04%   |
| Manjaro                      | 141      | 2.02%   |
| Linux Mint 20.1              | 141      | 2.02%   |
| KDE neon 20.04               | 118      | 1.69%   |
| Arch Rolling                 | 116      | 1.66%   |
| Arch                         | 116      | 1.66%   |
| Linux Mint 19.3              | 113      | 1.62%   |
| Ubuntu 20.10                 | 112      | 1.61%   |
| Linux Mint 20                | 107      | 1.53%   |
| Xubuntu 20.04                | 106      | 1.52%   |
| Ubuntu 21.04                 | 102      | 1.46%   |
| Ubuntu 19.10                 | 93       | 1.33%   |
| Zorin 16                     | 90       | 1.29%   |
| Ubuntu 19.04                 | 83       | 1.19%   |
| openSUSE Tumbleweed-XXXXXXXX | 70       | 1%      |
| Debian 10                    | 70       | 1%      |
| Kubuntu 20.04                | 63       | 0.9%    |
| Pop!_OS 20.10                | 57       | 0.82%   |
| BlackPanther 18.1            | 54       | 0.77%   |
| Linux Mint 21                | 52       | 0.75%   |
| Linux Mint 19.2              | 51       | 0.73%   |
| Pop!_OS 20.04                | 48       | 0.69%   |
| Fedora 33                    | 48       | 0.69%   |
| Pop!_OS 21.04                | 46       | 0.66%   |
| Fedora 32                    | 44       | 0.63%   |
| Gentoo 2.7                   | 43       | 0.62%   |
| Fedora 36                    | 43       | 0.62%   |
| ROSA R11                     | 41       | 0.59%   |
| Ubuntu 18.10                 | 39       | 0.56%   |
| ArcoLinux Rolling            | 39       | 0.56%   |
| Fedora 35                    | 38       | 0.55%   |
| Zorin 15                     | 37       | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 2397     | 36.41%  |
| Linux Mint    | 872      | 13.25%  |
| OpenMandriva  | 538      | 8.17%   |
| Manjaro       | 271      | 4.12%   |
| Debian        | 269      | 4.09%   |
| Fedora        | 237      | 3.6%    |
| Arch          | 221      | 3.36%   |
| Pop!_OS       | 207      | 3.14%   |
| Xubuntu       | 175      | 2.66%   |
| ROSA          | 157      | 2.38%   |
| Zorin         | 136      | 2.07%   |
| openSUSE      | 133      | 2.02%   |
| Kubuntu       | 131      | 1.99%   |
| KDE neon      | 127      | 1.93%   |
| Gentoo        | 93       | 1.41%   |
| BlackPanther  | 56       | 0.85%   |
| Ubuntu Unity  | 51       | 0.77%   |
| ArcoLinux     | 45       | 0.68%   |
| Ubuntu MATE   | 42       | 0.64%   |
| Elementary    | 32       | 0.49%   |
| EndeavourOS   | 31       | 0.47%   |
| Lubuntu       | 28       | 0.43%   |
| Endless       | 28       | 0.43%   |
| LMDE          | 26       | 0.39%   |
| CentOS        | 25       | 0.38%   |
| Ubuntu Budgie | 22       | 0.33%   |
| Kali          | 20       | 0.3%    |
| Clear Linux   | 17       | 0.26%   |
| Garuda Linux  | 16       | 0.24%   |
| QTS           | 15       | 0.23%   |
| MX            | 10       | 0.15%   |
| LinuxFX       | 10       | 0.15%   |
| Ubuntu Studio | 9        | 0.14%   |
| RHEL          | 9        | 0.14%   |
| Solus         | 8        | 0.12%   |
| Reborn OS     | 8        | 0.12%   |
| Peppermint    | 8        | 0.12%   |
| Mageia        | 8        | 0.12%   |
| Artix         | 8        | 0.12%   |
| Parrot        | 7        | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 256      | 3.24%   |
| 5.16.7-desktop-1omv4003  | 232      | 2.94%   |
| 5.4.0-42-generic         | 119      | 1.51%   |
| 5.4.0-58-generic         | 100      | 1.27%   |
| 5.4.0-52-generic         | 77       | 0.98%   |
| 5.4.0-48-generic         | 70       | 0.89%   |
| 5.15.0-48-generic        | 68       | 0.86%   |
| 5.4.0-26-generic         | 64       | 0.81%   |
| 5.4.0-91-generic         | 62       | 0.79%   |
| 5.4.0-40-generic         | 58       | 0.73%   |
| 5.4.0-65-generic         | 53       | 0.67%   |
| 5.15.0-52-generic        | 53       | 0.67%   |
| 5.11.0-27-generic        | 53       | 0.67%   |
| 5.4.0-54-generic         | 51       | 0.65%   |
| 5.13.0-28-generic        | 47       | 0.6%    |
| 5.4.0-37-generic         | 46       | 0.58%   |
| 5.4.0-29-generic         | 46       | 0.58%   |
| 5.3.0-40-generic         | 46       | 0.58%   |
| 5.15.0-46-generic        | 46       | 0.58%   |
| 5.11.0-38-generic        | 45       | 0.57%   |
| 5.11.0-37-generic        | 45       | 0.57%   |
| 5.13.0-30-generic        | 44       | 0.56%   |
| 5.11.0-40-generic        | 44       | 0.56%   |
| 5.13.0-39-generic        | 43       | 0.54%   |
| 4.18.16-desktop-1bP      | 42       | 0.53%   |
| 5.4.0-88-generic         | 40       | 0.51%   |
| 5.4.0-81-generic         | 40       | 0.51%   |
| 5.15.0-47-generic        | 39       | 0.49%   |
| 5.8.0-43-generic         | 38       | 0.48%   |
| 5.8.0-53-generic         | 37       | 0.47%   |
| 5.4.0-80-generic         | 37       | 0.47%   |
| 5.4.0-72-generic         | 37       | 0.47%   |
| 5.4.0-33-generic         | 37       | 0.47%   |
| 5.8.0-44-generic         | 36       | 0.46%   |
| 5.4.0-70-generic         | 36       | 0.46%   |
| 5.11.0-41-generic        | 35       | 0.44%   |
| 5.11.0-25-generic        | 35       | 0.44%   |
| 5.8.0-7630-generic       | 34       | 0.43%   |
| 5.4.0-90-generic         | 34       | 0.43%   |
| 5.4.0-45-generic         | 34       | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 1645     | 22.76%  |
| 4.15.0  | 534      | 7.39%   |
| 5.8.0   | 467      | 6.46%   |
| 5.11.0  | 440      | 6.09%   |
| 5.13.0  | 418      | 5.78%   |
| 5.15.0  | 371      | 5.13%   |
| 5.3.0   | 275      | 3.8%    |
| 5.10.14 | 258      | 3.57%   |
| 5.16.7  | 236      | 3.27%   |
| 5.0.0   | 202      | 2.79%   |
| 4.18.0  | 145      | 2.01%   |
| 5.10.0  | 130      | 1.8%    |
| 4.19.0  | 65       | 0.9%    |
| 4.18.16 | 46       | 0.64%   |
| 5.3.18  | 39       | 0.54%   |
| 4.4.0   | 34       | 0.47%   |
| 5.19.0  | 29       | 0.4%    |
| 4.9.20  | 27       | 0.37%   |
| 4.9.60  | 25       | 0.35%   |
| 5.17.1  | 24       | 0.33%   |
| 5.12.4  | 23       | 0.32%   |
| 5.18.12 | 22       | 0.3%    |
| 5.14.0  | 21       | 0.29%   |
| 5.18.0  | 20       | 0.28%   |
| 5.9.11  | 19       | 0.26%   |
| 5.9.0   | 19       | 0.26%   |
| 5.9.16  | 17       | 0.24%   |
| 5.17.5  | 17       | 0.24%   |
| 4.12.14 | 17       | 0.24%   |
| 3.10.0  | 17       | 0.24%   |
| 5.6.14  | 16       | 0.22%   |
| 5.6.0   | 16       | 0.22%   |
| 5.11.16 | 16       | 0.22%   |
| 5.7.0   | 15       | 0.21%   |
| 5.16.0  | 15       | 0.21%   |
| 5.9.8   | 14       | 0.19%   |
| 5.8.11  | 14       | 0.19%   |
| 5.7.9   | 13       | 0.18%   |
| 5.19.8  | 13       | 0.18%   |
| 5.11.6  | 13       | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 1754     | 24.57%  |
| 5.8     | 568      | 7.96%   |
| 4.15    | 537      | 7.52%   |
| 5.11    | 536      | 7.51%   |
| 5.10    | 518      | 7.25%   |
| 5.15    | 516      | 7.23%   |
| 5.13    | 485      | 6.79%   |
| 5.3     | 335      | 4.69%   |
| 5.16    | 326      | 4.57%   |
| 5.0     | 212      | 2.97%   |
| 4.18    | 196      | 2.75%   |
| 5.9     | 113      | 1.58%   |
| 5.18    | 100      | 1.4%    |
| 4.9     | 99       | 1.39%   |
| 5.19    | 98       | 1.37%   |
| 5.6     | 92       | 1.29%   |
| 5.14    | 85       | 1.19%   |
| 5.17    | 83       | 1.16%   |
| 4.19    | 82       | 1.15%   |
| 5.12    | 71       | 0.99%   |
| 5.7     | 67       | 0.94%   |
| 5.5     | 48       | 0.67%   |
| 6.0     | 42       | 0.59%   |
| 4.4     | 38       | 0.53%   |
| 5.2     | 22       | 0.31%   |
| 4.14    | 17       | 0.24%   |
| 4.12    | 17       | 0.24%   |
| 4.1     | 17       | 0.24%   |
| 3.10    | 17       | 0.24%   |
| 5.1     | 14       | 0.2%    |
| 4.13    | 8        | 0.11%   |
| 4.17    | 7        | 0.1%    |
| 4.20    | 6        | 0.08%   |
| 4.10    | 3        | 0.04%   |
| 4.2     | 2        | 0.03%   |
| 4.16    | 2        | 0.03%   |
| 4.8     | 1        | 0.01%   |
| 4.7     | 1        | 0.01%   |
| 4.6     | 1        | 0.01%   |
| 4.3     | 1        | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| x86_64   | 6198     | 97.59%  |
| i686     | 145      | 2.28%   |
| armv7l   | 3        | 0.05%   |
| ppc      | 2        | 0.03%   |
| armv5tel | 2        | 0.03%   |
| aarch64  | 1        | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Desktops | Percent |
|-------------------|----------|---------|
| GNOME             | 2517     | 37.65%  |
| KDE5              | 1150     | 17.2%   |
| Unknown           | 969      | 14.5%   |
| X-Cinnamon        | 692      | 10.35%  |
| XFCE              | 453      | 6.78%   |
| KDE               | 228      | 3.41%   |
| MATE              | 194      | 2.9%    |
| KDE4              | 94       | 1.41%   |
| Cinnamon          | 74       | 1.11%   |
| Unity             | 51       | 0.76%   |
| i3                | 37       | 0.55%   |
| Budgie            | 35       | 0.52%   |
| Pantheon          | 33       | 0.49%   |
| LXQt              | 33       | 0.49%   |
| LXDE              | 29       | 0.43%   |
| GNOME Classic     | 15       | 0.22%   |
| Deepin            | 14       | 0.21%   |
| GNOME Flashback   | 13       | 0.19%   |
| awesome           | 9        | 0.13%   |
| sway              | 7        | 0.1%    |
| qtile             | 5        | 0.07%   |
| bspwm             | 5        | 0.07%   |
| openbox           | 4        | 0.06%   |
| lightdm-xsession  | 4        | 0.06%   |
| trinity           | 3        | 0.04%   |
| herbstluftwm      | 3        | 0.04%   |
| DWM               | 3        | 0.04%   |
| Yaru:ubuntu:GNOME | 2        | 0.03%   |
| xmonad            | 1        | 0.01%   |
| ubuntustudio      | 1        | 0.01%   |
| pearl:GNOME       | 1        | 0.01%   |
| none+awesome      | 1        | 0.01%   |
| LeftWM            | 1        | 0.01%   |
| i3-with-shmlog    | 1        | 0.01%   |
| hyprland          | 1        | 0.01%   |
| enlightenment     | 1        | 0.01%   |
| chadwm            | 1        | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| X11         | 5312     | 81.21%  |
| Wayland     | 593      | 9.07%   |
| Unknown     | 465      | 7.11%   |
| Tty         | 169      | 2.58%   |
| Web         | 1        | 0.02%   |
| Unspecified | 1        | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3682     | 55.52%  |
| SDDM    | 1008     | 15.2%   |
| GDM3    | 616      | 9.29%   |
| LightDM | 562      | 8.47%   |
| GDM     | 405      | 6.11%   |
| TDM     | 234      | 3.53%   |
| KDM     | 94       | 1.42%   |
| XDM     | 12       | 0.18%   |
| SLiM    | 8        | 0.12%   |
| MDM     | 4        | 0.06%   |
| NODM    | 3        | 0.05%   |
| Ly      | 2        | 0.03%   |
| LXDM    | 2        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| de_DE       | 4278     | 65.6%   |
| en_US       | 979      | 15.01%  |
| Unknown     | 879      | 13.48%  |
| en_GB       | 106      | 1.63%   |
| C           | 102      | 1.56%   |
| en_DE       | 23       | 0.35%   |
| POSIX       | 18       | 0.28%   |
| ru_RU       | 16       | 0.25%   |
| fr_FR       | 12       | 0.18%   |
| pl_PL       | 11       | 0.17%   |
| es_ES       | 9        | 0.14%   |
| it_IT       | 8        | 0.12%   |
| de_AT       | 8        | 0.12%   |
| nl_NL       | 6        | 0.09%   |
| hu_HU       | 6        | 0.09%   |
| en_IE       | 6        | 0.09%   |
| de_CH       | 6        | 0.09%   |
| en_CA       | 5        | 0.08%   |
| C.UTF8      | 5        | 0.08%   |
| ro_RO       | 3        | 0.05%   |
| en_DK       | 3        | 0.05%   |
| el_GR       | 3        | 0.05%   |
| de_BE       | 3        | 0.05%   |
| tr_TR       | 2        | 0.03%   |
| ru_UA       | 2        | 0.03%   |
| pt_PT       | 2        | 0.03%   |
| hr_HR       | 2        | 0.03%   |
| de_IT       | 2        | 0.03%   |
| bs_BA       | 2        | 0.03%   |
| uk_UA       | 1        | 0.02%   |
| en_US-UTF-8 | 1        | 0.02%   |
| en_NZ       | 1        | 0.02%   |
| en_IL       | 1        | 0.02%   |
| en_AU       | 1        | 0.02%   |
| en_AT       | 1        | 0.02%   |
| de_LI       | 1        | 0.02%   |
| de_DE@utf8  | 1        | 0.02%   |
| de_DE.UTF8  | 1        | 0.02%   |
| cs_CZ       | 1        | 0.02%   |
| bg_BG       | 1        | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 4042     | 62.28%  |
| EFI  | 2448     | 37.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type          | Desktops | Percent |
|---------------|----------|---------|
| Ext4          | 4911     | 75.58%  |
| Overlay       | 664      | 10.22%  |
| Btrfs         | 431      | 6.63%   |
| Unknown       | 254      | 3.91%   |
| Xfs           | 96       | 1.48%   |
| Zfs           | 45       | 0.69%   |
| Ext2          | 35       | 0.54%   |
| Ext3          | 34       | 0.52%   |
| F2fs          | 8        | 0.12%   |
| Tmpfs         | 7        | 0.11%   |
| Reiserfs      | 5        | 0.08%   |
| Rootfs        | 2        | 0.03%   |
| XXXXXXX       | 1        | 0.02%   |
| XXXXX         | 1        | 0.02%   |
| XXXX          | 1        | 0.02%   |
| Jfs           | 1        | 0.02%   |
| Fuse.snapfuse | 1        | 0.02%   |
| Aufs          | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 4001     | 61.31%  |
| GPT     | 1707     | 26.16%  |
| MBR     | 818      | 12.53%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 5038     | 77.03%  |
| Yes       | 1502     | 22.97%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 4193     | 64.34%  |
| Yes       | 2324     | 35.66%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 1541     | 24.27%  |
| Gigabyte Technology | 1045     | 16.46%  |
| MSI                 | 940      | 14.8%   |
| ASRock              | 789      | 12.43%  |
| Hewlett-Packard     | 374      | 5.89%   |
| Dell                | 310      | 4.88%   |
| Fujitsu             | 265      | 4.17%   |
| Lenovo              | 190      | 2.99%   |
| Acer                | 151      | 2.38%   |
| Medion              | 141      | 2.22%   |
| Intel               | 69       | 1.09%   |
| Fujitsu Siemens     | 66       | 1.04%   |
| Biostar             | 66       | 1.04%   |
| Unknown             | 57       | 0.9%    |
| Foxconn             | 50       | 0.79%   |
| Pegatron            | 34       | 0.54%   |
| Shuttle             | 30       | 0.47%   |
| Packard Bell        | 28       | 0.44%   |
| BESSTAR Tech        | 16       | 0.25%   |
| Supermicro          | 14       | 0.22%   |
| ASRockRack          | 14       | 0.22%   |
| Apple               | 14       | 0.22%   |
| ECS                 | 13       | 0.2%    |
| AMI                 | 9        | 0.14%   |
| ZOTAC               | 7        | 0.11%   |
| AOpen               | 7        | 0.11%   |
| ABIT                | 7        | 0.11%   |
| EVGA                | 6        | 0.09%   |
| eMachines           | 6        | 0.09%   |
| Wortmann AG         | 5        | 0.08%   |
| IBM                 | 5        | 0.08%   |
| Hardkernel          | 5        | 0.08%   |
| PC Engines          | 4        | 0.06%   |
| Inventec            | 4        | 0.06%   |
| AZW                 | 4        | 0.06%   |
| Tekram Technology   | 3        | 0.05%   |
| Seco                | 3        | 0.05%   |
| AWOW                | 3        | 0.05%   |
| Alienware           | 3        | 0.05%   |
| WinFast             | 2        | 0.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS All Series            | 114      | 1.8%    |
| Unknown                    | 63       | 0.99%   |
| MSI MS-7C37                | 59       | 0.93%   |
| MSI MS-7B86                | 51       | 0.8%    |
| MSI MS-7A38                | 39       | 0.61%   |
| ASUS PRIME A320M-K         | 34       | 0.54%   |
| ASUS PRIME B350-PLUS       | 33       | 0.52%   |
| MSI MS-7B89                | 31       | 0.49%   |
| ASUS M5A78L-M/USB3         | 30       | 0.47%   |
| MSI MS-7C02                | 28       | 0.44%   |
| Dell OptiPlex 7010         | 28       | 0.44%   |
| ASRock B450M Pro4          | 27       | 0.43%   |
| ASUS PRIME X370-PRO        | 26       | 0.41%   |
| MSI MS-7B79                | 25       | 0.39%   |
| Gigabyte X570 AORUS ELITE  | 25       | 0.39%   |
| Gigabyte 970A-DS3P         | 25       | 0.39%   |
| ASUS A68HM-PLUS            | 23       | 0.36%   |
| MSI MS-7693                | 22       | 0.35%   |
| Dell OptiPlex 790          | 22       | 0.35%   |
| MSI MS-7C91                | 21       | 0.33%   |
| MSI MS-7C56                | 21       | 0.33%   |
| Gigabyte GA-78LMT-USB3 6.0 | 21       | 0.33%   |
| ASUS TUF Gaming X570-PLUS  | 20       | 0.31%   |
| ASUS PRIME B450M-A         | 20       | 0.31%   |
| ASRock B450 Pro4           | 20       | 0.31%   |
| ASRock 970 Pro3 R2.0       | 20       | 0.31%   |
| Gigabyte GA-78LMT-S2P      | 19       | 0.3%    |
| ASUS PRIME X470-PRO        | 19       | 0.3%    |
| ASUS M5A97 R2.0            | 19       | 0.3%    |
| ASUS A0000001              | 19       | 0.3%    |
| Gigabyte B450M DS3H        | 18       | 0.28%   |
| Dell OptiPlex 780          | 18       | 0.28%   |
| ASUS TUF Gaming B550-PLUS  | 18       | 0.28%   |
| MSI MS-7C52                | 17       | 0.27%   |
| MSI MS-7A32                | 17       | 0.27%   |
| MSI MS-7816                | 17       | 0.27%   |
| MSI MS-7A34                | 16       | 0.25%   |
| Medion MS-7728             | 16       | 0.25%   |
| MSI MS-7C35                | 15       | 0.24%   |
| Gigabyte TERRA_PC          | 15       | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 279      | 4.39%   |
| Dell OptiPlex           | 200      | 3.15%   |
| Fujitsu ESPRIMO         | 180      | 2.83%   |
| ASUS ROG                | 149      | 2.35%   |
| HP Compaq               | 123      | 1.94%   |
| ASUS All                | 114      | 1.8%    |
| Lenovo ThinkCentre      | 107      | 1.69%   |
| Acer Aspire             | 97       | 1.53%   |
| ASUS TUF                | 85       | 1.34%   |
| ASUS M5A78L-M           | 74       | 1.17%   |
| Unknown                 | 63       | 0.99%   |
| MSI MS-7C37             | 59       | 0.93%   |
| Gigabyte X570           | 59       | 0.93%   |
| MSI MS-7B86             | 51       | 0.8%    |
| Dell Precision          | 47       | 0.74%   |
| Gigabyte GA-78LMT-USB3  | 45       | 0.71%   |
| ASRock 970              | 45       | 0.71%   |
| Gigabyte B450           | 43       | 0.68%   |
| ASUS M5A97              | 43       | 0.68%   |
| HP EliteDesk            | 40       | 0.63%   |
| MSI MS-7A38             | 39       | 0.61%   |
| ASRock B450             | 37       | 0.58%   |
| Fujitsu CELSIUS         | 36       | 0.57%   |
| Gigabyte B550           | 34       | 0.54%   |
| Gigabyte B450M          | 34       | 0.54%   |
| Fujitsu Siemens ESPRIMO | 33       | 0.52%   |
| Lenovo IdeaCentre       | 32       | 0.5%    |
| MSI MS-7B89             | 31       | 0.49%   |
| ASRock B450M            | 29       | 0.46%   |
| MSI MS-7C02             | 28       | 0.44%   |
| HP ProDesk              | 28       | 0.44%   |
| Gigabyte 970A-DS3P      | 28       | 0.44%   |
| Acer Veriton            | 27       | 0.43%   |
| MSI MS-7B79             | 25       | 0.39%   |
| Lenovo ThinkStation     | 25       | 0.39%   |
| ASUS A68HM-PLUS         | 23       | 0.36%   |
| MSI MS-7693             | 22       | 0.35%   |
| ASRock Z77              | 22       | 0.35%   |
| ASRock X470             | 22       | 0.35%   |
| MSI MS-7C91             | 21       | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 664      | 10.46%  |
| 2018    | 655      | 10.31%  |
| 2019    | 546      | 8.6%    |
| 2013    | 539      | 8.49%   |
| 2011    | 515      | 8.11%   |
| 2017    | 450      | 7.09%   |
| 2020    | 431      | 6.79%   |
| 2014    | 419      | 6.6%    |
| 2010    | 406      | 6.39%   |
| 2009    | 351      | 5.53%   |
| 2015    | 283      | 4.46%   |
| 2016    | 258      | 4.06%   |
| 2008    | 257      | 4.05%   |
| 2021    | 186      | 2.93%   |
| 2007    | 178      | 2.8%    |
| 2006    | 90       | 1.42%   |
| 2022    | 40       | 0.63%   |
| 2005    | 39       | 0.61%   |
| 2004    | 15       | 0.24%   |
| Unknown | 12       | 0.19%   |
| 2003    | 9        | 0.14%   |
| 2000    | 4        | 0.06%   |
| 2002    | 2        | 0.03%   |
| 2001    | 1        | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 6350     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 6202     | 97.35%  |
| Enabled  | 169      | 2.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 6342     | 99.87%  |
| Yes  | 8        | 0.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 1688     | 26.03%  |
| 8.01-16.0       | 1306     | 20.14%  |
| 3.01-4.0        | 951      | 14.66%  |
| 32.01-64.0      | 931      | 14.36%  |
| 4.01-8.0        | 893      | 13.77%  |
| 64.01-256.0     | 307      | 4.73%   |
| 24.01-32.0      | 165      | 2.54%   |
| 1.01-2.0        | 144      | 2.22%   |
| 2.01-3.0        | 59       | 0.91%   |
| 0.51-1.0        | 26       | 0.4%    |
| More than 256.0 | 8        | 0.12%   |
| 0.01-0.5        | 5        | 0.08%   |
| Unknown         | 2        | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 2920     | 40.95%  |
| 2.01-3.0    | 1560     | 21.88%  |
| 4.01-8.0    | 901      | 12.63%  |
| 3.01-4.0    | 722      | 10.12%  |
| 0.51-1.0    | 554      | 7.77%   |
| 8.01-16.0   | 271      | 3.8%    |
| 0.01-0.5    | 96       | 1.35%   |
| 16.01-24.0  | 51       | 0.72%   |
| 32.01-64.0  | 25       | 0.35%   |
| 24.01-32.0  | 23       | 0.32%   |
| 64.01-256.0 | 5        | 0.07%   |
| Unknown     | 2        | 0.03%   |
| 0           | 1        | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2293     | 34.4%   |
| 2       | 1937     | 29.06%  |
| 3       | 1127     | 16.91%  |
| 4       | 645      | 9.68%   |
| 5       | 323      | 4.85%   |
| 6       | 132      | 1.98%   |
| 0       | 73       | 1.1%    |
| 7       | 66       | 0.99%   |
| 8       | 30       | 0.45%   |
| 9       | 11       | 0.17%   |
| 10      | 9        | 0.14%   |
| 13      | 4        | 0.06%   |
| 12      | 4        | 0.06%   |
| 17      | 3        | 0.05%   |
| 11      | 3        | 0.05%   |
| Unknown | 3        | 0.05%   |
| 22      | 1        | 0.02%   |
| 20      | 1        | 0.02%   |
| 16      | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3962     | 61.63%  |
| No        | 2467     | 38.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 6305     | 99.29%  |
| No        | 45       | 0.71%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4274     | 66.23%  |
| Yes       | 2179     | 33.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4801     | 74.36%  |
| Yes       | 1655     | 25.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Germany | 6350     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Desktops | Percent |
|-----------------------|----------|---------|
| Berlin                | 524      | 7.64%   |
| Hamburg               | 272      | 3.97%   |
| Munich                | 253      | 3.69%   |
| Frankfurt am Main     | 220      | 3.21%   |
| Cologne               | 132      | 1.93%   |
| Stuttgart             | 123      | 1.79%   |
| Leipzig               | 110      | 1.6%    |
| Essen                 | 76       | 1.11%   |
| Düsseldorf           | 71       | 1.04%   |
| Nuremberg             | 69       | 1.01%   |
| Mannheim              | 67       | 0.98%   |
| Karlsruhe             | 67       | 0.98%   |
| Dresden               | 64       | 0.93%   |
| Falkenstein           | 52       | 0.76%   |
| Dortmund              | 51       | 0.74%   |
| Duisburg              | 50       | 0.73%   |
| Bremen                | 41       | 0.6%    |
| Bonn                  | 37       | 0.54%   |
| Bochum                | 36       | 0.53%   |
| Wuppertal             | 35       | 0.51%   |
| Kiel                  | 32       | 0.47%   |
| Hanover               | 32       | 0.47%   |
| Chemnitz              | 32       | 0.47%   |
| Mainz                 | 31       | 0.45%   |
| Darmstadt             | 31       | 0.45%   |
| Braunschweig          | 30       | 0.44%   |
| Augsburg              | 29       | 0.42%   |
| Wiesbaden             | 28       | 0.41%   |
| Regensburg            | 28       | 0.41%   |
| Krefeld               | 28       | 0.41%   |
| Reutlingen            | 27       | 0.39%   |
| Münster              | 27       | 0.39%   |
| Gelsenkirchen         | 26       | 0.38%   |
| Bielefeld             | 25       | 0.36%   |
| Ludwigshafen am Rhein | 24       | 0.35%   |
| Erfurt                | 24       | 0.35%   |
| Halle                 | 23       | 0.34%   |
| Garbsen               | 23       | 0.34%   |
| Offenbach             | 22       | 0.32%   |
| Bamberg               | 22       | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 2484     | 4444   | 21.04%  |
| WDC                       | 2133     | 3725   | 18.07%  |
| Seagate                   | 1934     | 3192   | 16.38%  |
| SanDisk                   | 828      | 1247   | 7.01%   |
| Crucial                   | 702      | 1047   | 5.95%   |
| Toshiba                   | 646      | 964    | 5.47%   |
| Kingston                  | 418      | 569    | 3.54%   |
| Hitachi                   | 378      | 526    | 3.2%    |
| Intenso                   | 360      | 522    | 3.05%   |
| Unknown                   | 159      | 275    | 1.35%   |
| Intel                     | 157      | 217    | 1.33%   |
| Phison                    | 127      | 172    | 1.08%   |
| A-DATA Technology         | 119      | 158    | 1.01%   |
| OCZ                       | 102      | 128    | 0.86%   |
| HGST                      | 102      | 157    | 0.86%   |
| Maxtor                    | 70       | 108    | 0.59%   |
| Micron Technology         | 67       | 90     | 0.57%   |
| Corsair                   | 55       | 71     | 0.47%   |
| Patriot                   | 54       | 83     | 0.46%   |
| Micron/Crucial Technology | 54       | 82     | 0.46%   |
| Transcend                 | 48       | 58     | 0.41%   |
| China                     | 43       | 52     | 0.36%   |
| SPCC                      | 40       | 58     | 0.34%   |
| Silicon Motion            | 36       | 53     | 0.3%    |
| SK hynix                  | 35       | 41     | 0.3%    |
| ASMT                      | 29       | 39     | 0.25%   |
| Leven                     | 28       | 34     | 0.24%   |
| JMicron Technology        | 28       | 31     | 0.24%   |
| PNY                       | 23       | 31     | 0.19%   |
| WD MediaMax               | 21       | 24     | 0.18%   |
| XPG                       | 20       | 22     | 0.17%   |
| Apacer                    | 19       | 21     | 0.16%   |
| Hewlett-Packard           | 18       | 23     | 0.15%   |
| SABRENT                   | 17       | 18     | 0.14%   |
| LITEON                    | 17       | 19     | 0.14%   |
| Unknown                   | 16       | 23     | 0.14%   |
| Mushkin                   | 15       | 25     | 0.13%   |
| INNOVATION IT             | 15       | 18     | 0.13%   |
| KingDian                  | 14       | 15     | 0.12%   |
| Fujitsu                   | 14       | 15     | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Samsung SSD 850 EVO 250GB       | 223      | 1.59%   |
| Samsung SSD 860 EVO 500GB       | 177      | 1.27%   |
| Samsung SSD 850 EVO 500GB       | 152      | 1.09%   |
| Seagate ST500DM002-1BD142 500GB | 130      | 0.93%   |
| Samsung NVMe SSD Drive 500GB    | 126      | 0.9%    |
| Crucial CT1000MX500SSD1 1TB     | 120      | 0.86%   |
| Toshiba DT01ACA100 1TB          | 119      | 0.85%   |
| Samsung SSD 860 EVO 1TB         | 117      | 0.84%   |
| Crucial CT500MX500SSD1 500GB    | 110      | 0.79%   |
| Samsung NVMe SSD Drive 1TB      | 105      | 0.75%   |
| Toshiba HDWD110 1TB             | 86       | 0.61%   |
| Seagate ST1000DM010-2EP102 1TB  | 85       | 0.61%   |
| Samsung SSD 840 EVO 250GB       | 85       | 0.61%   |
| Samsung SSD 860 EVO 250GB       | 79       | 0.56%   |
| Seagate ST2000DM008-2FR102 2TB  | 78       | 0.56%   |
| WDC WD10EZEX-08WN4A0 1TB        | 73       | 0.52%   |
| Crucial CT240BX500SSD1 240GB    | 71       | 0.51%   |
| WDC WD20EZRZ-00Z5HB0 2TB        | 70       | 0.5%    |
| Seagate ST1000DM003-1CH162 1TB  | 68       | 0.49%   |
| SanDisk SSD PLUS 1000GB         | 65       | 0.46%   |
| Samsung SSD 970 EVO Plus 1TB    | 65       | 0.46%   |
| Toshiba DT01ACA200 2TB          | 64       | 0.46%   |
| SanDisk SSD PLUS 240GB          | 63       | 0.45%   |
| Samsung SSD 840 EVO 120GB       | 62       | 0.44%   |
| SanDisk SSD PLUS 480GB          | 61       | 0.44%   |
| Samsung SSD 970 EVO Plus 500GB  | 61       | 0.44%   |
| Samsung HD103SJ 1TB             | 60       | 0.43%   |
| Seagate ST2000DM001-1ER164 2TB  | 59       | 0.42%   |
| Unknown SD/MMC/MS PRO 8GB       | 55       | 0.39%   |
| Seagate ST4000DM004-2CV104 4TB  | 54       | 0.39%   |
| SanDisk SDSSDA240G 240GB        | 53       | 0.38%   |
| Samsung HD103UJ 1TB             | 53       | 0.38%   |
| WDC WD40EZRZ-00GXCB0 4TB        | 52       | 0.37%   |
| Samsung SSD 860 QVO 1TB         | 52       | 0.37%   |
| Samsung NVMe SSD Drive 250GB    | 52       | 0.37%   |
| Samsung HD501LJ 500GB           | 51       | 0.36%   |
| WDC WD20EARX-00PASB0 2TB        | 50       | 0.36%   |
| WDC WD40EFRX-68N32N0 4TB        | 49       | 0.35%   |
| Seagate ST3500418AS 500GB       | 49       | 0.35%   |
| Seagate ST1000DM003-1ER162 1TB  | 49       | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1948     | 3378   | 33.71%  |
| Seagate             | 1904     | 3142   | 32.95%  |
| Samsung Electronics | 590      | 891    | 10.21%  |
| Toshiba             | 568      | 848    | 9.83%   |
| Hitachi             | 378      | 526    | 6.54%   |
| HGST                | 102      | 157    | 1.77%   |
| Maxtor              | 69       | 104    | 1.19%   |
| Unknown             | 58       | 76     | 1%      |
| Intenso             | 43       | 70     | 0.74%   |
| ASMT                | 26       | 35     | 0.45%   |
| Fujitsu             | 14       | 15     | 0.24%   |
| WD MediaMax         | 12       | 15     | 0.21%   |
| ExcelStor           | 9        | 10     | 0.16%   |
| Dell                | 4        | 8      | 0.07%   |
| USB3.0              | 3        | 3      | 0.05%   |
| Inateck             | 3        | 3      | 0.05%   |
| IBM/Hitachi         | 3        | 3      | 0.05%   |
| IBM                 | 3        | 4      | 0.05%   |
| HGST HTS            | 3        | 3      | 0.05%   |
| Hewlett-Packard     | 3        | 3      | 0.05%   |
| ASMedia             | 3        | 3      | 0.05%   |
| Apple               | 3        | 3      | 0.05%   |
| USB                 | 2        | 2      | 0.03%   |
| MDT                 | 2        | 2      | 0.03%   |
| MARVELL             | 2        | 2      | 0.03%   |
| Magnetic Data       | 2        | 3      | 0.03%   |
| KESU                | 2        | 2      | 0.03%   |
| HPE                 | 2        | 5      | 0.03%   |
| China               | 2        | 2      | 0.03%   |
| TPH00800640GB       | 1        | 1      | 0.02%   |
| TANDBERG            | 1        | 1      | 0.02%   |
| Synology            | 1        | 1      | 0.02%   |
| Quantum             | 1        | 1      | 0.02%   |
| PHD 3.0             | 1        | 2      | 0.02%   |
| Maxone              | 1        | 1      | 0.02%   |
| LIO-ORG             | 1        | 2      | 0.02%   |
| LaCie               | 1        | 1      | 0.02%   |
| JMicron Technology  | 1        | 1      | 0.02%   |
| IB                  | 1        | 2      | 0.02%   |
| Fantom              | 1        | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 1498     | 2348   | 32.36%  |
| SanDisk             | 732      | 1095   | 15.81%  |
| Crucial             | 659      | 975    | 14.24%  |
| Kingston            | 292      | 388    | 6.31%   |
| Intenso             | 266      | 370    | 5.75%   |
| WDC                 | 186      | 244    | 4.02%   |
| A-DATA Technology   | 101      | 136    | 2.18%   |
| OCZ                 | 98       | 120    | 2.12%   |
| Intel               | 93       | 133    | 2.01%   |
| Toshiba             | 65       | 86     | 1.4%    |
| Micron Technology   | 55       | 73     | 1.19%   |
| Patriot             | 50       | 77     | 1.08%   |
| China               | 40       | 49     | 0.86%   |
| Transcend           | 38       | 40     | 0.82%   |
| SPCC                | 33       | 47     | 0.71%   |
| Corsair             | 31       | 43     | 0.67%   |
| Leven               | 27       | 33     | 0.58%   |
| JMicron Technology  | 22       | 24     | 0.48%   |
| PNY                 | 18       | 26     | 0.39%   |
| SK hynix            | 17       | 20     | 0.37%   |
| Apacer              | 17       | 19     | 0.37%   |
| LITEON              | 15       | 17     | 0.32%   |
| INNOVATION IT       | 15       | 18     | 0.32%   |
| Unknown             | 15       | 22     | 0.32%   |
| KingDian            | 14       | 15     | 0.3%    |
| Verbatim            | 12       | 17     | 0.26%   |
| Seagate             | 12       | 15     | 0.26%   |
| Team                | 11       | 15     | 0.24%   |
| Plextor             | 11       | 11     | 0.24%   |
| Netac               | 11       | 12     | 0.24%   |
| Mushkin             | 11       | 21     | 0.24%   |
| Unknown             | 10       | 11     | 0.22%   |
| Hewlett-Packard     | 10       | 12     | 0.22%   |
| LITEONIT            | 9        | 9      | 0.19%   |
| GOODRAM             | 9        | 13     | 0.19%   |
| Emtec               | 9        | 11     | 0.19%   |
| Phison              | 8        | 16     | 0.17%   |
| Drevo               | 8        | 13     | 0.17%   |
| TO Exter            | 6        | 10     | 0.13%   |
| TCSUNBOW            | 6        | 10     | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 4364     | 9338   | 44.43%  |
| SSD     | 3714     | 6734   | 37.81%  |
| NVMe    | 1497     | 2400   | 15.24%  |
| Unknown | 201      | 336    | 2.05%   |
| MMC     | 47       | 60     | 0.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 5824     | 15545  | 73.78%  |
| NVMe | 1489     | 2376   | 18.86%  |
| SAS  | 534      | 887    | 6.76%   |
| MMC  | 47       | 60     | 0.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 4431     | 8191   | 49.42%  |
| 0.51-1.0   | 2480     | 4221   | 27.66%  |
| 1.01-2.0   | 1073     | 1850   | 11.97%  |
| 3.01-4.0   | 392      | 708    | 4.37%   |
| 2.01-3.0   | 322      | 576    | 3.59%   |
| 4.01-10.0  | 215      | 411    | 2.4%    |
| 10.01-20.0 | 48       | 106    | 0.54%   |
| 20.01-50.0 | 4        | 8      | 0.04%   |
| 0          | 1        | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1483     | 21.6%   |
| 251-500        | 1152     | 16.78%  |
| 501-1000       | 1033     | 15.04%  |
| 1001-2000      | 775      | 11.29%  |
| More than 3000 | 675      | 9.83%   |
| 1-20           | 525      | 7.65%   |
| 2001-3000      | 391      | 5.69%   |
| 51-100         | 330      | 4.81%   |
| Unknown        | 323      | 4.7%    |
| 21-50          | 180      | 2.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 2403     | 33.78%  |
| 21-50          | 949      | 13.34%  |
| 101-250        | 804      | 11.3%   |
| 51-100         | 662      | 9.31%   |
| 251-500        | 571      | 8.03%   |
| 501-1000       | 553      | 7.77%   |
| 1001-2000      | 413      | 5.81%   |
| Unknown        | 323      | 4.54%   |
| More than 3000 | 252      | 3.54%   |
| 2001-3000      | 183      | 2.57%   |
| 0              | 1        | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Desktops | Drives | Percent |
|---------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 17       | 19     | 2.56%   |
| Samsung Electronics HD103UJ 1TB       | 12       | 12     | 1.81%   |
| Crucial CT525MX300SSD1 528GB          | 11       | 12     | 1.66%   |
| Samsung Electronics SP2504C 250GB     | 9        | 9      | 1.36%   |
| Samsung Electronics HD501LJ 500GB     | 9        | 12     | 1.36%   |
| WDC WD20EARS-00MVWB0 2TB              | 8        | 10     | 1.2%    |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 7        | 7      | 1.05%   |
| WDC WD20EFRX-68EUZN0 2TB              | 6        | 9      | 0.9%    |
| WDC WD10EARS-00Y5B1 1TB               | 6        | 6      | 0.9%    |
| Seagate ST31000528AS 1TB              | 6        | 7      | 0.9%    |
| Samsung Electronics HD160JJ 160GB     | 6        | 9      | 0.9%    |
| WDC WD20EARX-00PASB0 2TB              | 5        | 5      | 0.75%   |
| Seagate ST3500418AS 500GB             | 5        | 6      | 0.75%   |
| Seagate ST1000DM003-9YN162 1TB        | 5        | 5      | 0.75%   |
| Seagate ST1000DM003-1CH162 1TB        | 5        | 7      | 0.75%   |
| SanDisk SSD PLUS 480GB                | 5        | 5      | 0.75%   |
| Samsung Electronics SSD 840 EVO 120GB | 5        | 6      | 0.75%   |
| Samsung Electronics HD753LJ 752GB     | 5        | 6      | 0.75%   |
| Samsung Electronics HD103SI 1TB       | 5        | 5      | 0.75%   |
| WDC WD5000AAKX-001CA0 500GB           | 4        | 5      | 0.6%    |
| WDC WD5000AADS-00S9B0 500GB           | 4        | 5      | 0.6%    |
| WDC WD40EFRX-68N32N0 4TB              | 4        | 8      | 0.6%    |
| WDC WD20EZRX-00DC0B0 2TB              | 4        | 5      | 0.6%    |
| WDC WD10EARS-22Y5B1 1TB               | 4        | 4      | 0.6%    |
| WDC WD10EADS-00L5B1 1TB               | 4        | 4      | 0.6%    |
| Toshiba DT01ACA100 1TB                | 4        | 4      | 0.6%    |
| Seagate ST9500325AS 500GB             | 4        | 6      | 0.6%    |
| Seagate ST1000DX001-1CM162 1TB        | 4        | 4      | 0.6%    |
| SanDisk SSD PLUS 240GB                | 4        | 4      | 0.6%    |
| SanDisk SSD PLUS 120 GB               | 4        | 4      | 0.6%    |
| Samsung Electronics HD642JJ 640GB     | 4        | 4      | 0.6%    |
| Samsung Electronics HD103SJ 1TB       | 4        | 4      | 0.6%    |
| Kingston SV300S37A120G 120GB SSD      | 4        | 5      | 0.6%    |
| Hitachi HDT721010SLA360 1TB           | 4        | 6      | 0.6%    |
| Hitachi HDS721010CLA332 1TB           | 4        | 5      | 0.6%    |
| WDC WD5003ABYZ-011FA0 500GB           | 3        | 3      | 0.45%   |
| WDC WD30EFRX-68EUZN0 3TB              | 3        | 4      | 0.45%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 3        | 8      | 0.45%   |
| WDC WD2000FYYZ-01UL1B1 2TB            | 3        | 6      | 0.45%   |
| WDC WD10JPVX-22JC3T0 1TB              | 3        | 3      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 173      | 232    | 26.82%  |
| Seagate             | 166      | 203    | 25.74%  |
| Samsung Electronics | 113      | 135    | 17.52%  |
| Hitachi             | 39       | 56     | 6.05%   |
| SanDisk             | 32       | 35     | 4.96%   |
| Crucial             | 21       | 23     | 3.26%   |
| Toshiba             | 19       | 20     | 2.95%   |
| Maxtor              | 10       | 16     | 1.55%   |
| HGST                | 10       | 10     | 1.55%   |
| Intel               | 9        | 9      | 1.4%    |
| Kingston            | 8        | 9      | 1.24%   |
| Intenso             | 7        | 8      | 1.09%   |
| Micron Technology   | 5        | 5      | 0.78%   |
| A-DATA Technology   | 4        | 4      | 0.62%   |
| WD MediaMax         | 3        | 3      | 0.47%   |
| IBM                 | 3        | 3      | 0.47%   |
| SK hynix            | 2        | 2      | 0.31%   |
| OCZ                 | 2        | 4      | 0.31%   |
| MDT                 | 2        | 2      | 0.31%   |
| Fujitsu             | 2        | 3      | 0.31%   |
| XPG                 | 1        | 1      | 0.16%   |
| Unknown             | 1        | 1      | 0.16%   |
| Transcend           | 1        | 1      | 0.16%   |
| TO Exter            | 1        | 1      | 0.16%   |
| SPCC                | 1        | 1      | 0.16%   |
| Plextor             | 1        | 1      | 0.16%   |
| OCZ-VERTEX2         | 1        | 1      | 0.16%   |
| Neo Forza           | 1        | 1      | 0.16%   |
| Mushkin             | 1        | 1      | 0.16%   |
| INNOVATION IT       | 1        | 1      | 0.16%   |
| IBM/Hitachi         | 1        | 1      | 0.16%   |
| IB                  | 1        | 1      | 0.16%   |
| GOODRAM             | 1        | 1      | 0.16%   |
| Corsair             | 1        | 1      | 0.16%   |
| Apple               | 1        | 1      | 0.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 166      | 225    | 32.61%  |
| Seagate             | 166      | 203    | 32.61%  |
| Samsung Electronics | 85       | 100    | 16.7%   |
| Hitachi             | 39       | 56     | 7.66%   |
| Toshiba             | 19       | 20     | 3.73%   |
| Maxtor              | 10       | 16     | 1.96%   |
| HGST                | 10       | 10     | 1.96%   |
| WD MediaMax         | 3        | 3      | 0.59%   |
| IBM                 | 3        | 3      | 0.59%   |
| MDT                 | 2        | 2      | 0.39%   |
| Fujitsu             | 2        | 3      | 0.39%   |
| Unknown             | 1        | 1      | 0.2%    |
| IBM/Hitachi         | 1        | 1      | 0.2%    |
| IB                  | 1        | 1      | 0.2%    |
| Apple               | 1        | 1      | 0.2%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 464      | 645    | 77.33%  |
| SSD  | 120      | 134    | 20%     |
| NVMe | 16       | 18     | 2.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Samsung Electronics HD252HJ 250GB                | 2        | 2      | 14.29%  |
| Samsung Electronics HD103UJ 1TB                  | 2        | 2      | 14.29%  |
| WDC WD30EZRS-00J99B0 3TB                         | 1        | 1      | 7.14%   |
| WDC WD1600YS-23SHB0 160GB                        | 1        | 1      | 7.14%   |
| TPH00800640GB 640GB                              | 1        | 1      | 7.14%   |
| Seagate ST3640323AS 640GB                        | 1        | 1      | 7.14%   |
| Samsung Electronics SSD 850 250GB                | 1        | 1      | 7.14%   |
| Samsung Electronics MZVLB1T0HALR-00000 1TB       | 1        | 2      | 7.14%   |
| Samsung Electronics MZ7LN256HCHP-00000 256GB SSD | 1        | 2      | 7.14%   |
| Maxtor STM3500320AS 500GB                        | 1        | 1      | 7.14%   |
| Intenso SSD SATAIII 128GB                        | 1        | 1      | 7.14%   |
| Hitachi HDP725040GLA360 400GB                    | 1        | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 7        | 9      | 50%     |
| WDC                 | 2        | 2      | 14.29%  |
| TPH00800640GB       | 1        | 1      | 7.14%   |
| Seagate             | 1        | 1      | 7.14%   |
| Maxtor              | 1        | 1      | 7.14%   |
| Intenso             | 1        | 1      | 7.14%   |
| Hitachi             | 1        | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 4168     | 12190  | 59.38%  |
| Works    | 2258     | 5864   | 32.17%  |
| Malfunc  | 578      | 797    | 8.23%   |
| Failed   | 14       | 16     | 0.2%    |
| Limited  | 1        | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 3573     | 39.37%  |
| AMD                              | 2508     | 27.64%  |
| Samsung Electronics              | 832      | 9.17%   |
| ASMedia Technology               | 378      | 4.17%   |
| JMicron Technology               | 266      | 2.93%   |
| Marvell Technology Group         | 250      | 2.75%   |
| Nvidia                           | 225      | 2.48%   |
| SanDisk                          | 181      | 1.99%   |
| Phison Electronics               | 172      | 1.9%    |
| Kingston Technology Company      | 131      | 1.44%   |
| Micron/Crucial Technology        | 110      | 1.21%   |
| VIA Technologies                 | 61       | 0.67%   |
| Silicon Motion                   | 57       | 0.63%   |
| Silicon Image                    | 43       | 0.47%   |
| Adaptec                          | 40       | 0.44%   |
| ADATA Technology                 | 36       | 0.4%    |
| Broadcom / LSI                   | 32       | 0.35%   |
| LSI Logic / Symbios Logic        | 30       | 0.33%   |
| Toshiba America Info Systems     | 20       | 0.22%   |
| SK hynix                         | 18       | 0.2%    |
| Seagate Technology               | 15       | 0.17%   |
| Realtek Semiconductor            | 14       | 0.15%   |
| Micron Technology                | 14       | 0.15%   |
| KIOXIA                           | 9        | 0.1%    |
| 3ware                            | 9        | 0.1%    |
| Integrated Technology Express    | 8        | 0.09%   |
| Silicon Integrated Systems [SiS] | 7        | 0.08%   |
| OCZ Technology Group             | 6        | 0.07%   |
| Lite-On Technology               | 4        | 0.04%   |
| Hewlett-Packard                  | 4        | 0.04%   |
| Shenzhen Longsys Electronics     | 3        | 0.03%   |
| Advanced System Products         | 3        | 0.03%   |
| Promise Technology               | 2        | 0.02%   |
| Lite-On IT Corp. / Plextor       | 2        | 0.02%   |
| HighPoint Technologies           | 2        | 0.02%   |
| Apple                            | 2        | 0.02%   |
| ULi Electronics                  | 1        | 0.01%   |
| Tekram Technology                | 1        | 0.01%   |
| Solid State Storage Technology   | 1        | 0.01%   |
| MAXIO Technology (Hangzhou)      | 1        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1391     | 11.84%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 549      | 4.67%   |
| AMD 400 Series Chipset SATA Controller                                                  | 536      | 4.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 516      | 4.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 423      | 3.6%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 423      | 3.6%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 353      | 3%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 343      | 2.92%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 328      | 2.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 309      | 2.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 289      | 2.46%   |
| AMD 500 Series Chipset SATA Controller                                                  | 254      | 2.16%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 229      | 1.95%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 221      | 1.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 175      | 1.49%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 169      | 1.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 166      | 1.41%   |
| Intel SATA Controller [RAID mode]                                                       | 158      | 1.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 131      | 1.11%   |
| AMD 300 Series Chipset SATA Controller                                                  | 129      | 1.1%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 124      | 1.06%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 113      | 0.96%   |
| AMD FCH SATA Controller D                                                               | 111      | 0.94%   |
| AMD X370 Series Chipset SATA Controller                                                 | 108      | 0.92%   |
| Nvidia MCP61 SATA Controller                                                            | 102      | 0.87%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 95       | 0.81%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 92       | 0.78%   |
| Phison E12 NVMe Controller                                                              | 91       | 0.77%   |
| Nvidia MCP61 IDE                                                                        | 91       | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 86       | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 84       | 0.71%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 83       | 0.71%   |
| Kingston Company A2000 NVMe SSD                                                         | 76       | 0.65%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 70       | 0.6%    |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 63       | 0.54%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 62       | 0.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 61       | 0.52%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 60       | 0.51%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 60       | 0.51%   |
| JMicron JMB368 IDE controller                                                           | 59       | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 5283     | 58.32%  |
| IDE  | 1787     | 19.73%  |
| NVMe | 1525     | 16.83%  |
| RAID | 347      | 3.83%   |
| SAS  | 60       | 0.66%   |
| SCSI | 57       | 0.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 3650     | 57.48%  |
| AMD                   | 2692     | 42.39%  |
| ARM                   | 3        | 0.05%   |
| Marvell Semiconductor | 2        | 0.03%   |
| PowerMac3,6           | 1        | 0.02%   |
| PowerMac10,2          | 1        | 0.02%   |
| Unknown               | 1        | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 163      | 2.55%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 137      | 2.14%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 103      | 1.61%   |
| AMD FX-8350 Eight-Core Processor            | 96       | 1.5%    |
| AMD FX-6300 Six-Core Processor              | 82       | 1.28%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 76       | 1.19%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 72       | 1.13%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 69       | 1.08%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 67       | 1.05%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 65       | 1.02%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 64       | 1%      |
| Intel Core i5-2400 CPU @ 3.10GHz            | 59       | 0.92%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 57       | 0.89%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 57       | 0.89%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 57       | 0.89%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 56       | 0.88%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 54       | 0.85%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 49       | 0.77%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 48       | 0.75%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 47       | 0.74%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 47       | 0.74%   |
| AMD FX-4300 Quad-Core Processor             | 47       | 0.74%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 45       | 0.7%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 45       | 0.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 43       | 0.67%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 43       | 0.67%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 43       | 0.67%   |
| AMD Phenom II X4 955 Processor              | 40       | 0.63%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 39       | 0.61%   |
| AMD Phenom II X4 965 Processor              | 39       | 0.61%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 38       | 0.59%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 37       | 0.58%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 37       | 0.58%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 37       | 0.58%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 37       | 0.58%   |
| AMD Athlon II X2 250 Processor              | 37       | 0.58%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 36       | 0.56%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 36       | 0.56%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 36       | 0.56%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 35       | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 1064     | 16.7%   |
| Intel Core i7           | 798      | 12.53%  |
| AMD Ryzen 5             | 605      | 9.5%    |
| AMD Ryzen 7             | 475      | 7.46%   |
| AMD FX                  | 383      | 6.01%   |
| Intel Core i3           | 334      | 5.24%   |
| Intel Xeon              | 289      | 4.54%   |
| Intel Core 2 Duo        | 208      | 3.26%   |
| Intel Core 2 Quad       | 175      | 2.75%   |
| Intel Celeron           | 172      | 2.7%    |
| AMD Ryzen 9             | 162      | 2.54%   |
| AMD Phenom II X4        | 144      | 2.26%   |
| Intel Pentium           | 130      | 2.04%   |
| Intel Pentium Dual-Core | 109      | 1.71%   |
| AMD Ryzen 3             | 107      | 1.68%   |
| Other                   | 104      | 1.63%   |
| AMD Athlon II X2        | 102      | 1.6%    |
| AMD A8                  | 98       | 1.54%   |
| AMD A10                 | 87       | 1.37%   |
| Intel Core i9           | 60       | 0.94%   |
| AMD Athlon II X4        | 55       | 0.86%   |
| AMD A4                  | 55       | 0.86%   |
| Intel Atom              | 54       | 0.85%   |
| AMD Athlon 64 X2        | 54       | 0.85%   |
| Intel Pentium 4         | 50       | 0.78%   |
| Intel Core 2            | 50       | 0.78%   |
| AMD Phenom II X6        | 37       | 0.58%   |
| AMD Athlon              | 36       | 0.57%   |
| AMD Ryzen 5 PRO         | 34       | 0.53%   |
| AMD Ryzen Threadripper  | 32       | 0.5%    |
| AMD Phenom              | 23       | 0.36%   |
| Intel Pentium Dual      | 21       | 0.33%   |
| Intel Pentium D         | 21       | 0.33%   |
| AMD E                   | 19       | 0.3%    |
| AMD A6                  | 19       | 0.3%    |
| AMD Ryzen 7 PRO         | 17       | 0.27%   |
| AMD Athlon X4           | 17       | 0.27%   |
| AMD Athlon 64           | 17       | 0.27%   |
| AMD Athlon Dual Core    | 15       | 0.24%   |
| Intel Pentium Silver    | 14       | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 2682     | 42.02%  |
| 2       | 1564     | 24.5%   |
| 6       | 870      | 13.63%  |
| 8       | 638      | 10%     |
| 1       | 168      | 2.63%   |
| 12      | 146      | 2.29%   |
| 3       | 137      | 2.15%   |
| 16      | 93       | 1.46%   |
| 10      | 39       | 0.61%   |
| Unknown | 20       | 0.31%   |
| 18      | 6        | 0.09%   |
| 14      | 6        | 0.09%   |
| 32      | 5        | 0.08%   |
| 24      | 4        | 0.06%   |
| 20      | 2        | 0.03%   |
| 5       | 2        | 0.03%   |
| 64      | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 6291     | 99.07%  |
| 2      | 59       | 0.93%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 3563     | 55.91%  |
| 1       | 2789     | 43.76%  |
| Unknown | 20       | 0.31%   |
| 4       | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 6229     | 97.74%  |
| Unknown        | 108      | 1.69%   |
| 32-bit         | 35       | 0.55%   |
| 64-bit         | 1        | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1339     | 20.25%  |
| 0x306c3    | 471      | 7.12%   |
| 0x206a7    | 351      | 5.31%   |
| 0x306a9    | 346      | 5.23%   |
| 0x1067a    | 281      | 4.25%   |
| 0x08701021 | 263      | 3.98%   |
| 0x506e3    | 247      | 3.74%   |
| 0x06000852 | 219      | 3.31%   |
| 0x0800820d | 193      | 2.92%   |
| 0x010000c8 | 182      | 2.75%   |
| 0x906ea    | 149      | 2.25%   |
| 0x06001119 | 122      | 1.85%   |
| 0x08701013 | 121      | 1.83%   |
| 0x906e9    | 119      | 1.8%    |
| 0x6fb      | 91       | 1.38%   |
| 0x08108109 | 79       | 1.19%   |
| 0x106e5    | 72       | 1.09%   |
| 0x08001138 | 72       | 1.09%   |
| 0x0600063e | 60       | 0.91%   |
| 0x0a201009 | 56       | 0.85%   |
| 0x08001137 | 54       | 0.82%   |
| 0x010000db | 54       | 0.82%   |
| 0x0a201016 | 52       | 0.79%   |
| 0x906ed    | 49       | 0.74%   |
| 0x08101016 | 47       | 0.71%   |
| 0xa0655    | 46       | 0.7%    |
| 0x306f2    | 42       | 0.64%   |
| 0x106a5    | 42       | 0.64%   |
| 0x0810100b | 41       | 0.62%   |
| 0x6fd      | 40       | 0.61%   |
| 0xa0671    | 38       | 0.57%   |
| 0x20655    | 38       | 0.57%   |
| 0x06003106 | 37       | 0.56%   |
| 0xa0653    | 34       | 0.51%   |
| 0x6f6      | 34       | 0.51%   |
| 0x20652    | 33       | 0.5%    |
| 0x08600106 | 33       | 0.5%    |
| 0x10676    | 32       | 0.48%   |
| 0x0800820b | 32       | 0.48%   |
| 0x206d7    | 31       | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 634      | 9.95%   |
| Zen 2            | 539      | 8.46%   |
| SandyBridge      | 458      | 7.19%   |
| Piledriver       | 455      | 7.14%   |
| KabyLake         | 450      | 7.06%   |
| IvyBridge        | 427      | 6.7%    |
| K10              | 407      | 6.39%   |
| Zen+             | 395      | 6.2%    |
| Penryn           | 392      | 6.15%   |
| Skylake          | 323      | 5.07%   |
| Zen              | 317      | 4.97%   |
| Zen 3            | 218      | 3.42%   |
| Core             | 213      | 3.34%   |
| Nehalem          | 143      | 2.24%   |
| Westmere         | 115      | 1.8%    |
| K8 Hammer        | 100      | 1.57%   |
| CometLake        | 93       | 1.46%   |
| Silvermont       | 83       | 1.3%    |
| NetBurst         | 82       | 1.29%   |
| Bulldozer        | 75       | 1.18%   |
| Goldmont plus    | 52       | 0.82%   |
| Steamroller      | 51       | 0.8%    |
| Excavator        | 51       | 0.8%    |
| Unknown          | 50       | 0.78%   |
| Bonnell          | 38       | 0.6%    |
| Broadwell        | 31       | 0.49%   |
| Alderlake Hybrid | 30       | 0.47%   |
| K10 Llano        | 26       | 0.41%   |
| Bobcat           | 26       | 0.41%   |
| Jaguar           | 25       | 0.39%   |
| Goldmont         | 22       | 0.35%   |
| Icelake          | 21       | 0.33%   |
| Puma             | 17       | 0.27%   |
| P6               | 5        | 0.08%   |
| K6               | 4        | 0.06%   |
| TigerLake        | 3        | 0.05%   |
| Tremont          | 2        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 2657     | 39.59%  |
| AMD                                          | 2304     | 34.33%  |
| Intel                                        | 1669     | 24.87%  |
| ASPEED Technology                            | 33       | 0.49%   |
| Matrox Electronics Systems                   | 31       | 0.46%   |
| ATI Technologies                             | 5        | 0.07%   |
| S3 Graphics                                  | 4        | 0.06%   |
| VIA Technologies                             | 3        | 0.04%   |
| Silicon Integrated Systems [SiS]             | 3        | 0.04%   |
| XGI Technology (eXtreme Graphics Innovation) | 2        | 0.03%   |
| Dome Imaging Systems                         | 1        | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 315      | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 268      | 3.87%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 205      | 2.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 171      | 2.47%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 141      | 2.04%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 131      | 1.89%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 130      | 1.88%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 129      | 1.86%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 127      | 1.83%   |
| Intel HD Graphics 530                                                                    | 116      | 1.67%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 109      | 1.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 103      | 1.49%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 100      | 1.44%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 89       | 1.29%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 87       | 1.26%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 83       | 1.2%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 81       | 1.17%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 81       | 1.17%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 77       | 1.11%   |
| Nvidia GT218 [GeForce 210]                                                               | 74       | 1.07%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 67       | 0.97%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 67       | 0.97%   |
| Intel HD Graphics 630                                                                    | 66       | 0.95%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 64       | 0.92%   |
| AMD RS780L [Radeon 3000]                                                                 | 64       | 0.92%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 63       | 0.91%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 61       | 0.88%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 52       | 0.75%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 50       | 0.72%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 48       | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 47       | 0.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 47       | 0.68%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 46       | 0.66%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 46       | 0.66%   |
| AMD Renoir                                                                               | 45       | 0.65%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 44       | 0.64%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                                           | 42       | 0.61%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 41       | 0.59%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 40       | 0.58%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 37       | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| 1 x Nvidia                        | 2484     | 38.54%  |
| 1 x AMD                           | 2153     | 33.41%  |
| 1 x Intel                         | 1429     | 22.17%  |
| 2 x AMD                           | 76       | 1.18%   |
| Intel + Nvidia                    | 74       | 1.15%   |
| 2 x Nvidia                        | 53       | 0.82%   |
| AMD + Nvidia                      | 37       | 0.57%   |
| Intel + AMD                       | 35       | 0.54%   |
| 1 x Matrox                        | 28       | 0.43%   |
| 1 x ASPEED                        | 24       | 0.37%   |
| Other                             | 19       | 0.29%   |
| 1 x S3 Graphics                   | 4        | 0.06%   |
| Nvidia + ASPEED                   | 4        | 0.06%   |
| AMD + ASPEED                      | 4        | 0.06%   |
| 1 x VIA                           | 3        | 0.05%   |
| 1 x SiS                           | 3        | 0.05%   |
| Nvidia + Matrox                   | 3        | 0.05%   |
| 2 x Intel                         | 2        | 0.03%   |
| Nvidia + XGI                      | 2        | 0.03%   |
| Intel + AMD + 1 x Nvidia          | 2        | 0.03%   |
| 5 x AMD                           | 1        | 0.02%   |
| 4 x Nvidia                        | 1        | 0.02%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1        | 0.02%   |
| Nvidia + Dome Imaging Systems     | 1        | 0.02%   |
| 1 x Intel + 4 x AMD               | 1        | 0.02%   |
| Intel + 2 x Nvidia                | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 4625     | 71.22%  |
| Proprietary | 1524     | 23.47%  |
| Unknown     | 345      | 5.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2382     | 35.82%  |
| 1.01-2.0   | 1000     | 15.04%  |
| 0.51-1.0   | 826      | 12.42%  |
| 0.01-0.5   | 722      | 10.86%  |
| 7.01-8.0   | 654      | 9.84%   |
| 3.01-4.0   | 606      | 9.11%   |
| 5.01-6.0   | 209      | 3.14%   |
| 8.01-16.0  | 150      | 2.26%   |
| 2.01-3.0   | 83       | 1.25%   |
| 16.01-24.0 | 9        | 0.14%   |
| 4.01-5.0   | 8        | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 1154     | 16.78%  |
| Goldstar             | 675      | 9.82%   |
| Acer                 | 567      | 8.24%   |
| Dell                 | 515      | 7.49%   |
| BenQ                 | 474      | 6.89%   |
| Ancor Communications | 370      | 5.38%   |
| Hewlett-Packard      | 321      | 4.67%   |
| Philips              | 269      | 3.91%   |
| AOC                  | 267      | 3.88%   |
| Fujitsu Siemens      | 220      | 3.2%    |
| Iiyama               | 197      | 2.86%   |
| Eizo                 | 164      | 2.38%   |
| Medion               | 153      | 2.22%   |
| Unknown              | 100      | 1.45%   |
| LG Electronics       | 100      | 1.45%   |
| NEC Computers        | 86       | 1.25%   |
| ASUSTek Computer     | 82       | 1.19%   |
| Lenovo               | 80       | 1.16%   |
| HannStar             | 77       | 1.12%   |
| Sony                 | 69       | 1%      |
| ViewSonic            | 67       | 0.97%   |
| Belinea              | 50       | 0.73%   |
| Vestel Elektronik    | 48       | 0.7%    |
| Panasonic            | 45       | 0.65%   |
| Compal               | 43       | 0.63%   |
| Idek Iiyama          | 39       | 0.57%   |
| Toshiba              | 35       | 0.51%   |
| Grundig              | 34       | 0.49%   |
| MSI                  | 27       | 0.39%   |
| FUS                  | 24       | 0.35%   |
| Hitachi              | 19       | 0.28%   |
| Plain Tree Systems   | 18       | 0.26%   |
| HPN                  | 17       | 0.25%   |
| AUS                  | 17       | 0.25%   |
| HannStar Display     | 16       | 0.23%   |
| DENON                | 14       | 0.2%    |
| CHD                  | 14       | 0.2%    |
| Packard Bell         | 13       | 0.19%   |
| HKC                  | 12       | 0.17%   |
| Unknown              | 12       | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 48       | 0.65%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                     | 42       | 0.57%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 31       | 0.42%   |
| Grundig WXGA GRU4448 1600x1200                                         | 31       | 0.42%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 30       | 0.41%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 29       | 0.39%   |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch       | 29       | 0.39%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch  | 28       | 0.38%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 25       | 0.34%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 24       | 0.32%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                  | 22       | 0.3%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 21       | 0.28%   |
| Acer S242HL ACR0216 1920x1080 531x299mm 24.0-inch                      | 21       | 0.28%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 20       | 0.27%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch       | 20       | 0.27%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 19       | 0.26%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                     | 19       | 0.26%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                      | 19       | 0.26%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 18       | 0.24%   |
| Goldstar W2242 GSM5678 1680x1050 474x296mm 22.0-inch                   | 17       | 0.23%   |
| BenQ GL2450 BNQ78A5 1920x1080 531x298mm 24.0-inch                      | 17       | 0.23%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                   | 16       | 0.22%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                | 16       | 0.22%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch            | 16       | 0.22%   |
| Unknown LCD Monitor SAMSUNG                                            | 15       | 0.2%    |
| Goldstar 32inch FHD GSM76F5 1920x1080 698x392mm 31.5-inch              | 15       | 0.2%    |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                      | 15       | 0.2%    |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                    | 15       | 0.2%    |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                       | 15       | 0.2%    |
| Toshiba TV TSB0108 1360x768 580x320mm 26.1-inch                        | 14       | 0.19%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch   | 14       | 0.19%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 14       | 0.19%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                      | 14       | 0.19%   |
| Samsung Electronics LCD Monitor U28E590 3840x2160                      | 13       | 0.18%   |
| Fujitsu Siemens P19-2 FUS0552 1280x1024 376x301mm 19.0-inch            | 13       | 0.18%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch  | 13       | 0.18%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 12       | 0.16%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                       | 12       | 0.16%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch      | 12       | 0.16%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch               | 12       | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 2937     | 43.64%  |
| 3840x2160 (4K)     | 662      | 9.84%   |
| 1280x1024 (SXGA)   | 597      | 8.87%   |
| 1680x1050 (WSXGA+) | 541      | 8.04%   |
| 2560x1440 (QHD)    | 512      | 7.61%   |
| 1920x1200 (WUXGA)  | 329      | 4.89%   |
| Unknown            | 234      | 3.48%   |
| 3440x1440          | 118      | 1.75%   |
| 3840x1080          | 110      | 1.63%   |
| 1440x900 (WXGA+)   | 110      | 1.63%   |
| 1600x900 (HD+)     | 63       | 0.94%   |
| 2560x1080          | 61       | 0.91%   |
| 1366x768 (WXGA)    | 57       | 0.85%   |
| 1600x1200          | 55       | 0.82%   |
| 1920x540           | 44       | 0.65%   |
| 1360x768           | 40       | 0.59%   |
| 1024x768 (XGA)     | 32       | 0.48%   |
| 3840x1600          | 21       | 0.31%   |
| 4480x1440          | 19       | 0.28%   |
| 3840x1200          | 15       | 0.22%   |
| 2560x1600          | 14       | 0.21%   |
| 5760x2160          | 12       | 0.18%   |
| 3200x1080          | 11       | 0.16%   |
| 1280x720 (HD)      | 11       | 0.16%   |
| 2048x1152          | 10       | 0.15%   |
| 5120x1440          | 8        | 0.12%   |
| 3600x1080          | 8        | 0.12%   |
| 5760x1080          | 7        | 0.1%    |
| 1400x1050          | 7        | 0.1%    |
| 7680x2160          | 6        | 0.09%   |
| 3360x1080          | 4        | 0.06%   |
| 1280x768           | 4        | 0.06%   |
| 6400x2160          | 3        | 0.04%   |
| 3360x1050          | 3        | 0.04%   |
| 2288x1287          | 3        | 0.04%   |
| 7680x1440          | 2        | 0.03%   |
| 5520x1080          | 2        | 0.03%   |
| 5360x1440          | 2        | 0.03%   |
| 5280x1080          | 2        | 0.03%   |
| 5200x1200          | 2        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 1091     | 16.09%  |
| 27      | 1088     | 16.04%  |
| Unknown | 873      | 12.87%  |
| 23      | 792      | 11.68%  |
| 21      | 544      | 8.02%   |
| 19      | 488      | 7.2%    |
| 22      | 423      | 6.24%   |
| 31      | 196      | 2.89%   |
| 17      | 161      | 2.37%   |
| 20      | 141      | 2.08%   |
| 84      | 133      | 1.96%   |
| 34      | 133      | 1.96%   |
| 54      | 75       | 1.11%   |
| 72      | 67       | 0.99%   |
| 25      | 67       | 0.99%   |
| 32      | 62       | 0.91%   |
| 18      | 58       | 0.86%   |
| 40      | 43       | 0.63%   |
| 15      | 42       | 0.62%   |
| 28      | 28       | 0.41%   |
| 65      | 23       | 0.34%   |
| 37      | 22       | 0.32%   |
| 16      | 21       | 0.31%   |
| 33      | 20       | 0.29%   |
| 26      | 20       | 0.29%   |
| 48      | 19       | 0.28%   |
| 52      | 14       | 0.21%   |
| 49      | 14       | 0.21%   |
| 35      | 12       | 0.18%   |
| 50      | 11       | 0.16%   |
| 43      | 11       | 0.16%   |
| 42      | 11       | 0.16%   |
| 39      | 11       | 0.16%   |
| 46      | 10       | 0.15%   |
| 29      | 10       | 0.15%   |
| 55      | 7        | 0.1%    |
| 14      | 6        | 0.09%   |
| 30      | 4        | 0.06%   |
| 13      | 4        | 0.06%   |
| 60      | 3        | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 2712     | 41.25%  |
| 401-500        | 1263     | 19.21%  |
| Unknown        | 873      | 13.28%  |
| 351-400        | 412      | 6.27%   |
| 601-700        | 365      | 5.55%   |
| 301-350        | 221      | 3.36%   |
| 701-800        | 216      | 3.29%   |
| 1501-2000      | 203      | 3.09%   |
| 1001-1500      | 185      | 2.81%   |
| 801-900        | 89       | 1.35%   |
| 901-1000       | 19       | 0.29%   |
| 201-300        | 12       | 0.18%   |
| More than 2000 | 2        | 0.03%   |
| 101-200        | 2        | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 3608     | 56.92%  |
| 16/10   | 971      | 15.32%  |
| Unknown | 786      | 12.4%   |
| 5/4     | 552      | 8.71%   |
| 21/9    | 178      | 2.81%   |
| 4/3     | 121      | 1.91%   |
| 3/2     | 50       | 0.79%   |
| 32/9    | 33       | 0.52%   |
| 6/5     | 31       | 0.49%   |
| 1.00    | 4        | 0.06%   |
| 3.20    | 3        | 0.05%   |
| 1.96    | 1        | 0.02%   |
| 0.56    | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 2217     | 33.3%   |
| 301-350        | 1102     | 16.55%  |
| Unknown        | 873      | 13.11%  |
| 151-200        | 776      | 11.66%  |
| 251-300        | 482      | 7.24%   |
| 351-500        | 457      | 6.86%   |
| More than 1000 | 348      | 5.23%   |
| 141-150        | 193      | 2.9%    |
| 501-1000       | 131      | 1.97%   |
| 101-110        | 41       | 0.62%   |
| 131-140        | 20       | 0.3%    |
| 71-80          | 6        | 0.09%   |
| 111-120        | 4        | 0.06%   |
| 91-100         | 3        | 0.05%   |
| 1-40           | 2        | 0.03%   |
| 81-90          | 1        | 0.02%   |
| 61-70          | 1        | 0.02%   |
| 121-130        | 1        | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 3887     | 61.32%  |
| 101-120       | 994      | 15.68%  |
| Unknown       | 873      | 13.77%  |
| 121-160       | 244      | 3.85%   |
| 1-50          | 213      | 3.36%   |
| 161-240       | 127      | 2%      |
| More than 240 | 1        | 0.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 4896     | 75.44%  |
| 2     | 1038     | 15.99%  |
| 0     | 416      | 6.41%   |
| 3     | 122      | 1.88%   |
| 4     | 16       | 0.25%   |
| 5     | 2        | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 3792     | 44.91%  |
| Intel                           | 2509     | 29.72%  |
| Qualcomm Atheros                | 473      | 5.6%    |
| Broadcom                        | 235      | 2.78%   |
| Nvidia                          | 194      | 2.3%    |
| Ralink Technology               | 142      | 1.68%   |
| TP-Link                         | 118      | 1.4%    |
| Microsoft                       | 87       | 1.03%   |
| AVM                             | 84       | 0.99%   |
| Marvell Technology Group        | 61       | 0.72%   |
| Broadcom Limited                | 59       | 0.7%    |
| IMC Networks                    | 56       | 0.66%   |
| Ralink                          | 53       | 0.63%   |
| D-Link System                   | 51       | 0.6%    |
| Edimax Technology               | 44       | 0.52%   |
| Aquantia                        | 39       | 0.46%   |
| Qualcomm Atheros Communications | 31       | 0.37%   |
| Samsung Electronics             | 30       | 0.36%   |
| ASUSTek Computer                | 28       | 0.33%   |
| VIA Technologies                | 25       | 0.3%    |
| D-Link                          | 24       | 0.28%   |
| MediaTek                        | 23       | 0.27%   |
| NetGear                         | 21       | 0.25%   |
| Belkin Components               | 20       | 0.24%   |
| Sitecom Europe                  | 15       | 0.18%   |
| ASIX Electronics                | 14       | 0.17%   |
| 3Com                            | 14       | 0.17%   |
| Mellanox Technologies           | 13       | 0.15%   |
| Huawei Technologies             | 13       | 0.15%   |
| DisplayLink                     | 12       | 0.14%   |
| Xiaomi                          | 10       | 0.12%   |
| Arduino SA                      | 8        | 0.09%   |
| ZyXEL Communications            | 7        | 0.08%   |
| Dresden Elektronik              | 7        | 0.08%   |
| American Megatrends             | 7        | 0.08%   |
| ZyDAS                           | 5        | 0.06%   |
| Holtek Semiconductor            | 5        | 0.06%   |
| Apple                           | 5        | 0.06%   |
| ADMtek                          | 5        | 0.06%   |
| Texas Instruments               | 4        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3218     | 34.22%  |
| Intel I211 Gigabit Network Connection                             | 433      | 4.6%    |
| Intel Wi-Fi 6 AX200                                               | 256      | 2.72%   |
| Intel Ethernet Connection (2) I219-V                              | 250      | 2.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 245      | 2.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 237      | 2.52%   |
| Intel 82579V Gigabit Network Connection                           | 144      | 1.53%   |
| Intel Ethernet Connection I217-V                                  | 116      | 1.23%   |
| Intel Ethernet Connection I217-LM                                 | 112      | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 101      | 1.07%   |
| Nvidia MCP61 Ethernet                                             | 96       | 1.02%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 93       | 0.99%   |
| Intel Ethernet Controller I225-V                                  | 92       | 0.98%   |
| Intel Ethernet Connection (7) I219-V                              | 91       | 0.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 90       | 0.96%   |
| Intel Ethernet Connection (2) I218-V                              | 77       | 0.82%   |
| Intel I210 Gigabit Network Connection                             | 74       | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                             | 72       | 0.77%   |
| Intel Wireless-AC 9260                                            | 69       | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 65       | 0.69%   |
| Intel 82574L Gigabit Network Connection                           | 63       | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 55       | 0.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 54       | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 48       | 0.51%   |
| Microsoft Xbox 360 Wireless Adapter                               | 47       | 0.5%    |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]              | 45       | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 44       | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 43       | 0.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 41       | 0.44%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 38       | 0.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 38       | 0.4%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 37       | 0.39%   |
| Realtek 802.11ac NIC                                              | 37       | 0.39%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                   | 35       | 0.37%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 35       | 0.37%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 34       | 0.36%   |
| Intel Wireless 8260                                               | 33       | 0.35%   |
| AVM FRITZ!WLAN AC 860                                             | 33       | 0.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 32       | 0.34%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 32       | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 693      | 29.84%  |
| Realtek Semiconductor                 | 545      | 23.47%  |
| Qualcomm Atheros                      | 200      | 8.61%   |
| Ralink Technology                     | 142      | 6.12%   |
| TP-Link                               | 116      | 5%      |
| Microsoft                             | 87       | 3.75%   |
| AVM                                   | 84       | 3.62%   |
| Broadcom                              | 62       | 2.67%   |
| IMC Networks                          | 56       | 2.41%   |
| Ralink                                | 53       | 2.28%   |
| Edimax Technology                     | 44       | 1.89%   |
| D-Link System                         | 39       | 1.68%   |
| Qualcomm Atheros Communications       | 31       | 1.34%   |
| ASUSTek Computer                      | 28       | 1.21%   |
| D-Link                                | 22       | 0.95%   |
| NetGear                               | 21       | 0.9%    |
| MediaTek                              | 21       | 0.9%    |
| Belkin Components                     | 17       | 0.73%   |
| Sitecom Europe                        | 15       | 0.65%   |
| ZyXEL Communications                  | 7        | 0.3%    |
| Broadcom Limited                      | 7        | 0.3%    |
| ZyDAS                                 | 5        | 0.22%   |
| Philips (or NXP)                      | 4        | 0.17%   |
| Marvell Technology Group              | 4        | 0.17%   |
| Linksys                               | 4        | 0.17%   |
| Wacom                                 | 3        | 0.13%   |
| Gemtek                                | 2        | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.09%   |
| Wilocity                              | 1        | 0.04%   |
| Texas Instruments                     | 1        | 0.04%   |
| Sierra Wireless                       | 1        | 0.04%   |
| PLANEX                                | 1        | 0.04%   |
| Intersil                              | 1        | 0.04%   |
| Fujitsu Siemens Computers             | 1        | 0.04%   |
| Fiberline                             | 1        | 0.04%   |
| Accton Technology                     | 1        | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 256      | 10.88%  |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 101      | 4.29%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 90       | 3.82%   |
| Intel Wireless-AC 9260                                               | 69       | 2.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 55       | 2.34%   |
| Microsoft Xbox 360 Wireless Adapter                                  | 47       | 2%      |
| IMC Networks Mediao 802.11n WLAN [Realtek RTL8191SU]                 | 45       | 1.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 41       | 1.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 38       | 1.61%   |
| Realtek 802.11ac NIC                                                 | 37       | 1.57%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                      | 35       | 1.49%   |
| Intel Wireless 8260                                                  | 33       | 1.4%    |
| AVM FRITZ!WLAN AC 860                                                | 33       | 1.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 32       | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 31       | 1.32%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                               | 30       | 1.27%   |
| Intel Wireless 3165                                                  | 30       | 1.27%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]       | 29       | 1.23%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                              | 28       | 1.19%   |
| Microsoft XBOX ACC                                                   | 28       | 1.19%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter             | 27       | 1.15%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                   | 27       | 1.15%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 26       | 1.1%    |
| Intel Wireless 7260                                                  | 26       | 1.1%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 25       | 1.06%   |
| Intel Wireless 7265                                                  | 25       | 1.06%   |
| Ralink RT5572 Wireless Adapter                                       | 24       | 1.02%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                      | 23       | 0.98%   |
| Ralink RT5370 Wireless Adapter                                       | 23       | 0.98%   |
| Intel Wireless 8265 / 8275                                           | 23       | 0.98%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 23       | 0.98%   |
| AVM FRITZ WLAN N v2 [RT5572/rt2870.bin]                              | 23       | 0.98%   |
| Qualcomm Atheros AR9271 802.11n                                      | 22       | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 21       | 0.89%   |
| D-Link System DWA-140 RangeBooster N Adapter(rev.B2) [Ralink RT3072] | 21       | 0.89%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 20       | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 19       | 0.81%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                     | 19       | 0.81%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                     | 18       | 0.76%   |
| Ralink MT7601U Wireless Adapter                                      | 16       | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 3590     | 53.11%  |
| Intel                                  | 2159     | 31.94%  |
| Qualcomm Atheros                       | 290      | 4.29%   |
| Nvidia                                 | 194      | 2.87%   |
| Broadcom                               | 175      | 2.59%   |
| Marvell Technology Group               | 57       | 0.84%   |
| Broadcom Limited                       | 52       | 0.77%   |
| Aquantia                               | 39       | 0.58%   |
| Samsung Electronics                    | 30       | 0.44%   |
| VIA Technologies                       | 25       | 0.37%   |
| ASIX Electronics                       | 14       | 0.21%   |
| 3Com                                   | 14       | 0.21%   |
| DisplayLink                            | 12       | 0.18%   |
| D-Link System                          | 12       | 0.18%   |
| Mellanox Technologies                  | 11       | 0.16%   |
| Xiaomi                                 | 10       | 0.15%   |
| Huawei Technologies                    | 9        | 0.13%   |
| American Megatrends                    | 7        | 0.1%    |
| Apple                                  | 5        | 0.07%   |
| ADMtek                                 | 5        | 0.07%   |
| Netchip Technology                     | 3        | 0.04%   |
| ZTE WCDMA Technologies MSM             | 2        | 0.03%   |
| TP-Link                                | 2        | 0.03%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.03%   |
| Silicon Integrated Systems [SiS]       | 2        | 0.03%   |
| Qualcomm                               | 2        | 0.03%   |
| MediaTek                               | 2        | 0.03%   |
| Lenovo                                 | 2        | 0.03%   |
| JMicron Technology                     | 2        | 0.03%   |
| ICS Advent                             | 2        | 0.03%   |
| HMD Global                             | 2        | 0.03%   |
| Google                                 | 2        | 0.03%   |
| Emulex                                 | 2        | 0.03%   |
| D-Link                                 | 2        | 0.03%   |
| Belkin Components                      | 2        | 0.03%   |
| Trident Microsystems                   | 1        | 0.01%   |
| Total Phase                            | 1        | 0.01%   |
| SysKonnect                             | 1        | 0.01%   |
| Sundance Technology Inc / IC Plus      | 1        | 0.01%   |
| QLogic                                 | 1        | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3218     | 46.1%   |
| Intel I211 Gigabit Network Connection                             | 433      | 6.2%    |
| Intel Ethernet Connection (2) I219-V                              | 250      | 3.58%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 245      | 3.51%   |
| Realtek RTL8125 2.5GbE Controller                                 | 237      | 3.39%   |
| Intel 82579V Gigabit Network Connection                           | 144      | 2.06%   |
| Intel Ethernet Connection I217-V                                  | 116      | 1.66%   |
| Intel Ethernet Connection I217-LM                                 | 112      | 1.6%    |
| Nvidia MCP61 Ethernet                                             | 96       | 1.38%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 93       | 1.33%   |
| Intel Ethernet Controller I225-V                                  | 92       | 1.32%   |
| Intel Ethernet Connection (7) I219-V                              | 91       | 1.3%    |
| Intel Ethernet Connection (2) I218-V                              | 77       | 1.1%    |
| Intel I210 Gigabit Network Connection                             | 74       | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                             | 72       | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 65       | 0.93%   |
| Intel 82574L Gigabit Network Connection                           | 63       | 0.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 54       | 0.77%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 48       | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 44       | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 43       | 0.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 38       | 0.54%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 37       | 0.53%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 35       | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 34       | 0.49%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 32       | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                             | 30       | 0.43%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 29       | 0.42%   |
| Intel 82578DM Gigabit Network Connection                          | 29       | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 26       | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 24       | 0.34%   |
| Broadcom NetLink BCM57781 Gigabit Ethernet PCIe                   | 24       | 0.34%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 23       | 0.33%   |
| Intel 82578DC Gigabit Network Connection                          | 23       | 0.33%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 23       | 0.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 21       | 0.3%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 21       | 0.3%    |
| Nvidia MCP73 Ethernet                                             | 21       | 0.3%    |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 21       | 0.3%    |
| Nvidia MCP77 Ethernet                                             | 20       | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 6305     | 73.79%  |
| WiFi     | 2174     | 25.44%  |
| Modem    | 48       | 0.56%   |
| Unknown  | 18       | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 5443     | 83.38%  |
| WiFi     | 1083     | 16.59%  |
| Unknown  | 2        | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 4577     | 71.71%  |
| 2     | 1503     | 23.55%  |
| 3     | 208      | 3.26%   |
| 4     | 35       | 0.55%   |
| 0     | 33       | 0.52%   |
| 5     | 11       | 0.17%   |
| 6     | 9        | 0.14%   |
| 7     | 3        | 0.05%   |
| 18    | 2        | 0.03%   |
| 12    | 1        | 0.02%   |
| 8     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 4521     | 68.78%  |
| Yes  | 2052     | 31.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 634      | 37.32%  |
| Cambridge Silicon Radio         | 527      | 31.02%  |
| Realtek Semiconductor           | 128      | 7.53%   |
| ASUSTek Computer                | 115      | 6.77%   |
| Broadcom                        | 91       | 5.36%   |
| Qualcomm Atheros Communications | 58       | 3.41%   |
| IMC Networks                    | 23       | 1.35%   |
| Lite-On Technology              | 19       | 1.12%   |
| Integrated System Solution      | 18       | 1.06%   |
| Apple                           | 18       | 1.06%   |
| Belkin Components               | 15       | 0.88%   |
| MediaTek                        | 10       | 0.59%   |
| Edimax Technology               | 7        | 0.41%   |
| Logitech                        | 6        | 0.35%   |
| TP-Link                         | 5        | 0.29%   |
| HTC (High Tech Computer)        | 4        | 0.24%   |
| Qcom                            | 3        | 0.18%   |
| Motorola PCS                    | 2        | 0.12%   |
| Micro Star International        | 2        | 0.12%   |
| Conwise Technology              | 2        | 0.12%   |
| Toshiba                         | 1        | 0.06%   |
| SINO WEALTH                     | 1        | 0.06%   |
| Realtek                         | 1        | 0.06%   |
| National Semiconductor          | 1        | 0.06%   |
| Microsoft                       | 1        | 0.06%   |
| i.Tech Dynamic Limited          | 1        | 0.06%   |
| Hewlett-Packard                 | 1        | 0.06%   |
| Fujitsu Siemens Computers       | 1        | 0.06%   |
| Foxconn / Hon Hai               | 1        | 0.06%   |
| Dell                            | 1        | 0.06%   |
| AVM                             | 1        | 0.06%   |
| Unknown                         | 1        | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 526      | 30.94%  |
| Intel AX200 Bluetooth                                                | 231      | 13.59%  |
| Intel Bluetooth wireless interface                                   | 143      | 8.41%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 97       | 5.71%   |
| Realtek Bluetooth Radio                                              | 87       | 5.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 67       | 3.94%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 60       | 3.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 59       | 3.47%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 36       | 2.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 36       | 2.12%   |
| Intel AX201 Bluetooth                                                | 28       | 1.65%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 27       | 1.59%   |
| Intel AX210 Bluetooth                                                | 22       | 1.29%   |
| ASUS Bluetooth Radio                                                 | 18       | 1.06%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 11       | 0.65%   |
| MediaTek Wireless_Device                                             | 10       | 0.59%   |
| Lite-On Bluetooth Device                                             | 10       | 0.59%   |
| IMC Networks Bluetooth Radio                                         | 10       | 0.59%   |
| ASUS Bluetooth Adapter                                               | 10       | 0.59%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 9        | 0.53%   |
| Integrated System Solution Bluetooth Device                          | 9        | 0.53%   |
| ASUS ASUS USB-BT500                                                  | 9        | 0.53%   |
| Apple Bluetooth USB Host Controller                                  | 9        | 0.53%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 8        | 0.47%   |
| Realtek RTL8821A Bluetooth                                           | 7        | 0.41%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 7        | 0.41%   |
| Logitech BT Mini-Receiver (HCI mode)                                 | 6        | 0.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 6        | 0.35%   |
| ASUS BCM20702A0                                                      | 6        | 0.35%   |
| TP-Link UB500 Adapter                                                | 5        | 0.29%   |
| Qualcomm Atheros  Bluetooth Device                                   | 5        | 0.29%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 5        | 0.29%   |
| Intel Bluetooth Device                                               | 5        | 0.29%   |
| Broadcom BCM2035 Bluetooth dongle                                    | 5        | 0.29%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 5        | 0.29%   |
| Realtek RTL8723B Bluetooth                                           | 4        | 0.24%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 4        | 0.24%   |
| IMC Networks Bluetooth Module                                        | 4        | 0.24%   |
| IMC Networks BCM20702A0                                              | 4        | 0.24%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4        | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Intel                     | 3350     | 31.68%  |
| AMD                       | 3138     | 29.68%  |
| Nvidia                    | 2487     | 23.52%  |
| C-Media Electronics       | 298      | 2.82%   |
| Creative Labs             | 182      | 1.72%   |
| Logitech                  | 124      | 1.17%   |
| Texas Instruments         | 74       | 0.7%    |
| Kingston Technology       | 49       | 0.46%   |
| VIA Technologies          | 48       | 0.45%   |
| Creative Technology       | 48       | 0.45%   |
| Focusrite-Novation        | 46       | 0.44%   |
| JMTek                     | 44       | 0.42%   |
| GN Netcom                 | 44       | 0.42%   |
| Plantronics               | 33       | 0.31%   |
| Sennheiser Communications | 32       | 0.3%    |
| Razer USA                 | 31       | 0.29%   |
| Yamaha                    | 28       | 0.26%   |
| SteelSeries ApS           | 24       | 0.23%   |
| Corsair                   | 24       | 0.23%   |
| ASUSTek Computer          | 24       | 0.23%   |
| Samson Technologies       | 21       | 0.2%    |
| RODE Microphones          | 19       | 0.18%   |
| Generalplus Technology    | 19       | 0.18%   |
| BEHRINGER International   | 19       | 0.18%   |
| TerraTec Electronic       | 14       | 0.13%   |
| GYROCOM C&C               | 12       | 0.11%   |
| Realtek Semiconductor     | 11       | 0.1%    |
| Dell                      | 11       | 0.1%    |
| ROCCAT                    | 10       | 0.09%   |
| M-Audio                   | 10       | 0.09%   |
| Blue Microphones          | 10       | 0.09%   |
| Native Instruments        | 9        | 0.09%   |
| Valve Software            | 8        | 0.08%   |
| USB MICROPHONE            | 8        | 0.08%   |
| Cambridge Silicon Radio   | 8        | 0.08%   |
| AKAI Professional M.I.    | 8        | 0.08%   |
| XMOS                      | 7        | 0.07%   |
| Tenx Technology           | 7        | 0.07%   |
| SAVITECH                  | 7        | 0.07%   |
| Hewlett-Packard           | 7        | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                      | 698      | 5.57%   |
| AMD Starship/Matisse HD Audio Controller                                          | 608      | 4.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 465      | 3.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 422      | 3.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 420      | 3.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 361      | 2.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 316      | 2.52%   |
| AMD Family 17h/19h HD Audio Controller                                            | 314      | 2.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 294      | 2.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 288      | 2.3%    |
| AMD FCH Azalia Controller                                                         | 260      | 2.07%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 237      | 1.89%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 234      | 1.87%   |
| Intel 200 Series PCH HD Audio                                                     | 233      | 1.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 225      | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 190      | 1.52%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 175      | 1.4%    |
| Intel Cannon Lake PCH cAVS                                                        | 172      | 1.37%   |
| Nvidia GP104 High Definition Audio Controller                                     | 164      | 1.31%   |
| Nvidia GP106 High Definition Audio Controller                                     | 163      | 1.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 158      | 1.26%   |
| AMD Navi 10 HDMI Audio                                                            | 150      | 1.2%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 147      | 1.17%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 133      | 1.06%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 128      | 1.02%   |
| Nvidia High Definition Audio Controller                                           | 125      | 1%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 123      | 0.98%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 121      | 0.97%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 113      | 0.9%    |
| Nvidia GM204 High Definition Audio Controller                                     | 112      | 0.89%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 112      | 0.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 111      | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                                     | 108      | 0.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 102      | 0.81%   |
| Nvidia MCP61 High Definition Audio                                                | 98       | 0.78%   |
| Nvidia GF119 HDMI Audio Controller                                                | 92       | 0.73%   |
| Nvidia TU106 High Definition Audio Controller                                     | 91       | 0.73%   |
| AMD Trinity HDMI Audio Controller                                                 | 91       | 0.73%   |
| Nvidia GK104 HDMI Audio Controller                                                | 89       | 0.71%   |
| Nvidia TU104 HD Audio Controller                                                  | 85       | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 503      | 15.14%  |
| G.Skill             | 496      | 14.93%  |
| Kingston            | 426      | 12.82%  |
| Corsair             | 399      | 12.01%  |
| Crucial             | 375      | 11.28%  |
| Samsung Electronics | 366      | 11.01%  |
| SK hynix            | 236      | 7.1%    |
| Micron Technology   | 151      | 4.54%   |
| Nanya Technology    | 55       | 1.66%   |
| A-DATA Technology   | 51       | 1.53%   |
| Team                | 39       | 1.17%   |
| Ramaxel Technology  | 25       | 0.75%   |
| Patriot             | 23       | 0.69%   |
| Unknown             | 23       | 0.69%   |
| Elpida              | 16       | 0.48%   |
| Transcend           | 13       | 0.39%   |
| GeIL                | 12       | 0.36%   |
| Unknown (ABCD)      | 11       | 0.33%   |
| Goodram             | 8        | 0.24%   |
| Unifosa             | 7        | 0.21%   |
| Avant               | 6        | 0.18%   |
| Mushkin             | 4        | 0.12%   |
| CSX                 | 4        | 0.12%   |
| Toshiba             | 3        | 0.09%   |
| Timetec             | 3        | 0.09%   |
| Qimonda             | 3        | 0.09%   |
| Patriot Memory      | 3        | 0.09%   |
| Hewlett-Packard     | 3        | 0.09%   |
| Golden Empire       | 3        | 0.09%   |
| Exceleram           | 3        | 0.09%   |
| Aeneon              | 3        | 0.09%   |
| 48spaces            | 3        | 0.09%   |
| TakeMS              | 2        | 0.06%   |
| Swissbit            | 2        | 0.06%   |
| Silicon Power       | 2        | 0.06%   |
| S                   | 2        | 0.06%   |
| PNY                 | 2        | 0.06%   |
| Lexar               | 2        | 0.06%   |
| INNOVATION PC       | 2        | 0.06%   |
| ATP                 | 2        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s          | 68       | 1.87%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s          | 43       | 1.18%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                      | 39       | 1.07%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 39       | 1.07%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 35       | 0.96%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s           | 34       | 0.94%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                      | 27       | 0.74%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 23       | 0.63%   |
| G.Skill RAM F4-3200C16-16GIS 16GB DIMM DDR4 3600MT/s         | 23       | 0.63%   |
| Unknown                                                      | 23       | 0.63%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s        | 21       | 0.58%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s      | 20       | 0.55%   |
| Samsung RAM M378B5173QH0-CK0 4096MB DIMM DDR3 1600MT/s       | 19       | 0.52%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1600MT/s         | 18       | 0.5%    |
| Corsair RAM CMX8GX3M2A1333C9 4096MB DIMM DDR3 1333MT/s       | 18       | 0.5%    |
| Crucial RAM CT102464BA160B.C16 8192MB DIMM DDR3 1600MT/s     | 16       | 0.44%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s       | 16       | 0.44%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s          | 15       | 0.41%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s        | 15       | 0.41%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                 | 14       | 0.39%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                  | 14       | 0.39%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 14       | 0.39%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s      | 14       | 0.39%   |
| G.Skill RAM F4-3600C16-16GTZNC 16384MB DIMM DDR4 3600MT/s    | 14       | 0.39%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s               | 13       | 0.36%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s        | 13       | 0.36%   |
| G.Skill RAM F4-3000C16-16GISB 16GB DIMM DDR4 3000MT/s        | 13       | 0.36%   |
| Crucial RAM BLS4G3D1609DS1S00. 4GB DIMM DDR3 1600MT/s        | 13       | 0.36%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 12       | 0.33%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                         | 12       | 0.33%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s          | 12       | 0.33%   |
| Samsung RAM M378A1K43CB2-CRC 8GB DIMM DDR4 3500MT/s          | 12       | 0.33%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s          | 12       | 0.33%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s          | 12       | 0.33%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s          | 12       | 0.33%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s        | 12       | 0.33%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                      | 11       | 0.3%    |
| Unknown RAM Module 4096MB DIMM 1600MT/s                      | 11       | 0.3%    |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 11       | 0.3%    |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 11       | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 1415     | 47.25%  |
| DDR3    | 1001     | 33.42%  |
| Unknown | 240      | 8.01%   |
| DDR2    | 156      | 5.21%   |
| SDRAM   | 129      | 4.31%   |
| DDR     | 32       | 1.07%   |
| LPDDR4  | 15       | 0.5%    |
| DRAM    | 5        | 0.17%   |
| DDR5    | 2        | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| DIMM            | 2743     | 93.08%  |
| SODIMM          | 183      | 6.21%   |
| FB-DIMM         | 9        | 0.31%   |
| RIMM            | 8        | 0.27%   |
| Row Of Chips    | 2        | 0.07%   |
| Proprietary Car | 1        | 0.03%   |
| Chip            | 1        | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 1280     | 39.73%  |
| 4096  | 758      | 23.53%  |
| 16384 | 484      | 15.02%  |
| 2048  | 431      | 13.38%  |
| 1024  | 132      | 4.1%    |
| 32768 | 117      | 3.63%   |
| 512   | 18       | 0.56%   |
| 256   | 1        | 0.03%   |
| 16    | 1        | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 626      | 19.16%  |
| 1333    | 429      | 13.13%  |
| 3200    | 369      | 11.29%  |
| 3600    | 220      | 6.73%   |
| 2400    | 209      | 6.4%    |
| 2667    | 176      | 5.39%   |
| 2133    | 173      | 5.29%   |
| 800     | 136      | 4.16%   |
| 667     | 95       | 2.91%   |
| 3000    | 67       | 2.05%   |
| Unknown | 65       | 1.99%   |
| 1866    | 59       | 1.81%   |
| 2666    | 53       | 1.62%   |
| 1867    | 51       | 1.56%   |
| 3866    | 46       | 1.41%   |
| 3400    | 41       | 1.25%   |
| 3733    | 38       | 1.16%   |
| 2933    | 34       | 1.04%   |
| 1800    | 34       | 1.04%   |
| 1066    | 33       | 1.01%   |
| 3466    | 29       | 0.89%   |
| 400     | 28       | 0.86%   |
| 3800    | 27       | 0.83%   |
| 1067    | 19       | 0.58%   |
| 2800    | 18       | 0.55%   |
| 1334    | 17       | 0.52%   |
| 533     | 13       | 0.4%    |
| 3500    | 12       | 0.37%   |
| 2048    | 10       | 0.31%   |
| 3666    | 9        | 0.28%   |
| 2000    | 9        | 0.28%   |
| 3100    | 8        | 0.24%   |
| 2465    | 8        | 0.24%   |
| 333     | 8        | 0.24%   |
| 4000    | 7        | 0.21%   |
| 3066    | 7        | 0.21%   |
| 2200    | 7        | 0.21%   |
| 1639    | 7        | 0.21%   |
| 1648    | 6        | 0.18%   |
| 3334    | 5        | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Hewlett-Packard          | 135      | 29.41%  |
| Brother Industries       | 95       | 20.7%   |
| Canon                    | 77       | 16.78%  |
| Samsung Electronics      | 62       | 13.51%  |
| Seiko Epson              | 28       | 6.1%    |
| Kyocera                  | 12       | 2.61%   |
| Prolific Technology      | 11       | 2.4%    |
| Dymo-CoStar              | 9        | 1.96%   |
| QinHeng Electronics      | 8        | 1.74%   |
| Lexmark International    | 8        | 1.74%   |
| Dell                     | 3        | 0.65%   |
| Xerox                    | 2        | 0.44%   |
| Ricoh                    | 2        | 0.44%   |
| Magic Control Technology | 2        | 0.44%   |
| Seiko Instruments        | 1        | 0.22%   |
| Oki Data                 | 1        | 0.22%   |
| ATEN International       | 1        | 0.22%   |
| Agere Systems (Lucent)   | 1        | 0.22%   |
| Unknown                  | 1        | 0.22%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Prolific PL2305 Parallel Port                          | 11       | 2.38%   |
| Samsung M2020 Series                                   | 10       | 2.16%   |
| Brother HL-2030 Laser Printer                          | 10       | 2.16%   |
| QinHeng CH340S                                         | 8        | 1.73%   |
| Canon iP7200 series                                    | 8        | 1.73%   |
| Samsung C48x Series                                    | 7        | 1.51%   |
| HP ENVY 4520 series                                    | 7        | 1.51%   |
| Canon CanoScan LiDE 300                                | 7        | 1.51%   |
| Samsung M2070 Series                                   | 5        | 1.08%   |
| HP OfficeJet 3830 series                               | 5        | 1.08%   |
| HP DeskJet F4200 series                                | 5        | 1.08%   |
| Canon PIXMA MX920 Series                               | 5        | 1.08%   |
| Canon LiDE 400                                         | 5        | 1.08%   |
| Samsung SCX-472x Series                                | 4        | 0.86%   |
| Samsung ML-1640 Series Laser Printer                   | 4        | 0.86%   |
| HP Officejet Pro 8100                                  | 4        | 0.86%   |
| HP ENVY 4500 series                                    | 4        | 0.86%   |
| HP DeskJet 1110 series                                 | 4        | 0.86%   |
| Brother HL-3142CW series                               | 4        | 0.86%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 3        | 0.65%   |
| Samsung M283x Series                                   | 3        | 0.65%   |
| Samsung C43x Series                                    | 3        | 0.65%   |
| HP OfficeJet Pro 7720 series                           | 3        | 0.65%   |
| HP OfficeJet Pro 69                                    | 3        | 0.65%   |
| HP OfficeJet 5200 series                               | 3        | 0.65%   |
| HP OfficeJet 4650 series                               | 3        | 0.65%   |
| HP Officejet 2620 series                               | 3        | 0.65%   |
| HP Deskjet 3520 series                                 | 3        | 0.65%   |
| HP DeskJet 2620 All-in-One Printer                     | 3        | 0.65%   |
| HP Deskjet 2540 series                                 | 3        | 0.65%   |
| Canon PIXMA MX720 Series                               | 3        | 0.65%   |
| Canon PIXMA MG3600 Series                              | 3        | 0.65%   |
| Canon PIXMA MG2500 Series                              | 3        | 0.65%   |
| Canon Pixma iP4500 Printer                             | 3        | 0.65%   |
| Brother MFC-L2710DW series                             | 3        | 0.65%   |
| Brother MFC-J470DW                                     | 3        | 0.65%   |
| Brother HL-L3210CW series                              | 3        | 0.65%   |
| Brother HL-52x0 series                                 | 3        | 0.65%   |
| Brother HL-2250DN Laser Printer                        | 3        | 0.65%   |
| Brother HL-2140 series                                 | 3        | 0.65%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                 | Desktops | Percent |
|------------------------|----------|---------|
| Canon                  | 130      | 71.43%  |
| Seiko Epson            | 27       | 14.84%  |
| Hewlett-Packard        | 11       | 6.04%   |
| AGFA-Gevaert NV        | 7        | 3.85%   |
| Mustek Systems         | 5        | 2.75%   |
| Nikon                  | 1        | 0.55%   |
| Microtek International | 1        | 0.55%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                                       | 20       | 10.99%  |
| Canon CanoScan LiDE 220                                       | 18       | 9.89%   |
| Canon CanoScan LIDE 25                                        | 14       | 7.69%   |
| Canon CanoScan LiDE 110                                       | 13       | 7.14%   |
| Canon CanoScan N670U/N676U/LiDE 20                            | 12       | 6.59%   |
| Canon CanoScan LiDE 120                                       | 9        | 4.95%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]           | 8        | 4.4%    |
| Canon CanoScan LiDE 100                                       | 7        | 3.85%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                        | 5        | 2.75%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 4        | 2.2%    |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                 | 4        | 2.2%    |
| Canon CanoScan LiDE 90                                        | 4        | 2.2%    |
| Canon CanoScan 9000F Mark II                                  | 4        | 2.2%    |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]      | 3        | 1.65%   |
| HP ScanJet 3970c                                              | 3        | 1.65%   |
| Canon CanoScan N1240U/LiDE 30                                 | 3        | 1.65%   |
| Canon CanoScan LiDE 60                                        | 3        | 1.65%   |
| Canon CanoScan LiDE 200                                       | 3        | 1.65%   |
| Canon CanoScan 8800F                                          | 3        | 1.65%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 3        | 1.65%   |
| Mustek Systems ScanExpress 1200 CU                            | 2        | 1.1%    |
| Canon CanoScan LiDE 700F                                      | 2        | 1.1%    |
| Canon CanoScan LiDE 600F                                      | 2        | 1.1%    |
| Seiko Epson GT-F700 [Perfection V350]                         | 1        | 0.55%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1        | 0.55%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                  | 1        | 0.55%   |
| Seiko Epson GT-9400UF [Perfection 3170]                       | 1        | 0.55%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 0.55%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]   | 1        | 0.55%   |
| Seiko Epson GT-7700U [Perfection 1240U]                       | 1        | 0.55%   |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]                    | 1        | 0.55%   |
| Nikon Coolscan LS 40 ED                                       | 1        | 0.55%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                    | 1        | 0.55%   |
| Mustek Systems ScanExpress A3 USB                             | 1        | 0.55%   |
| Mustek Systems ScanExpress 1200 CU Plus                       | 1        | 0.55%   |
| Microtek International USB1200 Scanner                        | 1        | 0.55%   |
| HP ScanJet Pro 2500 f1                                        | 1        | 0.55%   |
| HP ScanJet G3010                                              | 1        | 0.55%   |
| HP scanjet 8270                                               | 1        | 0.55%   |
| HP ScanJet 5590                                               | 1        | 0.55%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 460      | 40.82%  |
| Microsoft                     | 110      | 9.76%   |
| Microdia                      | 108      | 9.58%   |
| Sunplus Innovation Technology | 42       | 3.73%   |
| Samsung Electronics           | 40       | 3.55%   |
| Creative Technology           | 31       | 2.75%   |
| Generalplus Technology        | 27       | 2.4%    |
| ARC International             | 26       | 2.31%   |
| Realtek Semiconductor         | 24       | 2.13%   |
| Chicony Electronics           | 16       | 1.42%   |
| Apple                         | 15       | 1.33%   |
| Trust                         | 14       | 1.24%   |
| Cubeternet                    | 14       | 1.24%   |
| Z-Star Microelectronics       | 13       | 1.15%   |
| Jieli Technology              | 13       | 1.15%   |
| GEMBIRD                       | 11       | 0.98%   |
| MacroSilicon                  | 10       | 0.89%   |
| Valve Software                | 8        | 0.71%   |
| Sonix Technology              | 8        | 0.71%   |
| IMC Networks                  | 8        | 0.71%   |
| 2M UVC CAMERA                 | 7        | 0.62%   |
| Huawei Technologies           | 6        | 0.53%   |
| Arkmicro Technologies         | 6        | 0.53%   |
| SJ-180517-N                   | 5        | 0.44%   |
| Razer USA                     | 5        | 0.44%   |
| Philips (or NXP)              | 5        | 0.44%   |
| Genesys Logic                 | 5        | 0.44%   |
| Alcor Micro                   | 5        | 0.44%   |
| Sony                          | 4        | 0.35%   |
| KYE Systems (Mouse Systems)   | 4        | 0.35%   |
| Guillemot                     | 4        | 0.35%   |
| Xiaomi                        | 3        | 0.27%   |
| Unknown                       | 3        | 0.27%   |
| SHENZHEN EMEET TECHNOLOGY     | 3        | 0.27%   |
| MediaTek                      | 3        | 0.27%   |
| Linux Foundation              | 3        | 0.27%   |
| Google                        | 3        | 0.27%   |
| Aveo Technology               | 3        | 0.27%   |
| YGTek                         | 2        | 0.18%   |
| WaveRider Communications      | 2        | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 105      | 9.25%   |
| Logitech HD Pro Webcam C920             | 53       | 4.67%   |
| Microsoft LifeCam HD-3000               | 50       | 4.41%   |
| Samsung Galaxy series, misc. (MTP mode) | 39       | 3.44%   |
| Logitech HD Webcam C525                 | 38       | 3.35%   |
| Logitech C922 Pro Stream Webcam         | 29       | 2.56%   |
| Logitech Webcam C310                    | 28       | 2.47%   |
| Microdia USB 2.0 Camera                 | 24       | 2.11%   |
| ARC International Camera                | 24       | 2.11%   |
| Microdia Webcam Vitade AF               | 21       | 1.85%   |
| Microdia Sonix USB 2.0 Camera           | 20       | 1.76%   |
| Microdia Camera                         | 16       | 1.41%   |
| Logitech HD Webcam C510                 | 16       | 1.41%   |
| Sunplus FHD Camera Microphone           | 15       | 1.32%   |
| Logitech Webcam C170                    | 14       | 1.23%   |
| Logitech C920 PRO HD Webcam             | 14       | 1.23%   |
| Jieli USB PHY 2.0                       | 13       | 1.15%   |
| Generalplus GENERAL WEBCAM              | 13       | 1.15%   |
| Apple iPhone 5/5C/5S/6/SE               | 13       | 1.15%   |
| Microsoft LifeCam Cinema                | 12       | 1.06%   |
| Logitech Webcam Pro 9000                | 12       | 1.06%   |
| Logitech Webcam C930e                   | 12       | 1.06%   |
| Logitech HD Webcam C910                 | 12       | 1.06%   |
| Creative Live! Cam Sync HD [VF0770]     | 12       | 1.06%   |
| Microdia Hy-HD-Camera                   | 11       | 0.97%   |
| Logitech StreamCam                      | 11       | 0.97%   |
| Realtek HD webcam                       | 10       | 0.88%   |
| MacroSilicon USB Video                  | 9        | 0.79%   |
| Logitech Webcam C250                    | 9        | 0.79%   |
| Logitech Webcam B500                    | 9        | 0.79%   |
| Logitech QuickCam Pro 9000              | 9        | 0.79%   |
| Logitech QuickCam E 3500                | 9        | 0.79%   |
| Logitech BRIO                           | 9        | 0.79%   |
| Valve Software 3D Camera                | 8        | 0.7%    |
| Sunplus HD 720P webcam                  | 8        | 0.7%    |
| Generalplus 808 Camera                  | 8        | 0.7%    |
| Creative Live! Cam Chat HD [VF0700]     | 8        | 0.7%    |
| Trust USB Camera                        | 7        | 0.62%   |
| Microsoft MicrosoftÂ LifeCam Studio    | 7        | 0.62%   |
| Microsoft LifeCam HD-5000               | 7        | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Elan Microelectronics      | 8        | 44.44%  |
| STMicroelectronics         | 2        | 11.11%  |
| AuthenTec                  | 2        | 11.11%  |
| Validity Sensors           | 1        | 5.56%   |
| Upek                       | 1        | 5.56%   |
| Synaptics                  | 1        | 5.56%   |
| Shenzhen Goodix Technology | 1        | 5.56%   |
| LighTuning Technology      | 1        | 5.56%   |
| DigitalPersona             | 1        | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]            | 8        | 44.44%  |
| STMicroelectronics Fingerprint Reader                  | 2        | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1        | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1        | 5.56%   |
| Synaptics  WBDI Fingerprint Reader - USB 052           | 1        | 5.56%   |
| Shenzhen Goodix  Fingerprint Device                    | 1        | 5.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1        | 5.56%   |
| DigitalPersona Fingerprint Reader                      | 1        | 5.56%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1        | 5.56%   |
| AuthenTec AES1600                                      | 1        | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Reiner SCT Kartensysteme  | 19       | 31.15%  |
| Clay Logic                | 6        | 9.84%   |
| Cherry                    | 6        | 9.84%   |
| Alcor Micro               | 6        | 9.84%   |
| SCM Microsystems          | 4        | 6.56%   |
| OmniKey                   | 4        | 6.56%   |
| Fujitsu Siemens Computers | 4        | 6.56%   |
| Kobil Systems             | 3        | 4.92%   |
| Advanced Card Systems     | 3        | 4.92%   |
| Yubico.com                | 1        | 1.64%   |
| Realtek Semiconductor     | 1        | 1.64%   |
| Lenovo                    | 1        | 1.64%   |
| In Focus Systems          | 1        | 1.64%   |
| Chicony Electronics       | 1        | 1.64%   |
| Aladdin Knowledge Systems | 1        | 1.64%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 7        | 11.48%  |
| Reiner SCT Kartensysteme cyberJack one                                     | 7        | 11.48%  |
| Clay Logic Nitrokey Pro                                                    | 6        | 9.84%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 4        | 6.56%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 4        | 6.56%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 3        | 4.92%   |
| Reiner SCT Kartensysteme tanJack USB                                       | 3        | 4.92%   |
| OmniKey CardMan 3021 / 3121                                                | 3        | 4.92%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                            | 2        | 3.28%   |
| Kobil Systems KOBIL Class 3 Reader                                         | 2        | 3.28%   |
| Alcor Micro Watchdata W 1981                                               | 2        | 3.28%   |
| Advanced Card Systems ACR122U                                              | 2        | 3.28%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                            | 1        | 1.64%   |
| SCM Microsystems SCR331 SmartCard Reader                                   | 1        | 1.64%   |
| Realtek Semiconductor Smart Card Reader Interface                          | 1        | 1.64%   |
| OmniKey CardMan 3121 (HID Technologies)                                    | 1        | 1.64%   |
| Lenovo Smartcard Keyboard                                                  | 1        | 1.64%   |
| Kobil Systems Smart Token                                                  | 1        | 1.64%   |
| In Focus Systems EMV Smartcard Reader                                      | 1        | 1.64%   |
| Fujitsu Siemens Computers Smartcard Reader D323                            | 1        | 1.64%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 1.64%   |
| Fujitsu Siemens Computers Keyboard KB100 SCR eSIG                          | 1        | 1.64%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                  | 1        | 1.64%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                       | 1        | 1.64%   |
| Cherry SmartTerminal XX44                                                  | 1        | 1.64%   |
| Cherry Smart Card Reader USB                                               | 1        | 1.64%   |
| Aladdin Knowledge Systems Token JC                                         | 1        | 1.64%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 1        | 1.64%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 5482     | 84.31%  |
| 1     | 815      | 12.53%  |
| 2     | 150      | 2.31%   |
| 3     | 31       | 0.48%   |
| 5     | 12       | 0.18%   |
| 4     | 9        | 0.14%   |
| 8     | 1        | 0.02%   |
| 7     | 1        | 0.02%   |
| 6     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 412      | 33.47%  |
| Net/wireless             | 246      | 19.98%  |
| Communication controller | 135      | 10.97%  |
| Unassigned class         | 87       | 7.07%   |
| Multimedia controller    | 62       | 5.04%   |
| Sound                    | 61       | 4.96%   |
| Card reader              | 49       | 3.98%   |
| Chipcard                 | 39       | 3.17%   |
| Camera                   | 25       | 2.03%   |
| Bluetooth                | 23       | 1.87%   |
| Fingerprint reader       | 17       | 1.38%   |
| Network                  | 14       | 1.14%   |
| Net/ethernet             | 14       | 1.14%   |
| Storage/ide              | 12       | 0.97%   |
| Storage/raid             | 10       | 0.81%   |
| Modem                    | 5        | 0.41%   |
| Dvb card                 | 5        | 0.41%   |
| Tv card                  | 4        | 0.32%   |
| Firewire controller      | 4        | 0.32%   |
| Storage                  | 3        | 0.24%   |
| Unclassified device      | 2        | 0.16%   |
| Video                    | 1        | 0.08%   |
| Storage/nvme             | 1        | 0.08%   |

