ROSA - Tested Hardware & Statistics (Desktops)
----------------------------------------------

A project to collect tested hardware configurations for ROSA.

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

Total: 20946

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | H110M-R                     | [c790793197](https://linux-hardware.org/?probe=c790793197) | Feb 01, 2023 |
| Unknown       | Unknown                     | [7e53e3c6e8](https://linux-hardware.org/?probe=7e53e3c6e8) | Jan 31, 2023 |
| Gigabyte      | A320M-H-CF                  | [f5379a55ea](https://linux-hardware.org/?probe=f5379a55ea) | Jan 31, 2023 |
| ASUSTek       | H110-PLUS                   | [c20a43e3e5](https://linux-hardware.org/?probe=c20a43e3e5) | Jan 31, 2023 |
| ASRock        | B650M PG Riptide            | [260d257a0c](https://linux-hardware.org/?probe=260d257a0c) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | [4830eacf5e](https://linux-hardware.org/?probe=4830eacf5e) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | [0b59b68d55](https://linux-hardware.org/?probe=0b59b68d55) | Jan 30, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [10c275723f](https://linux-hardware.org/?probe=10c275723f) | Jan 30, 2023 |
| MSI           | B450M-A PRO MAX             | [a7232f4811](https://linux-hardware.org/?probe=a7232f4811) | Jan 30, 2023 |
| Gigabyte      | B550 GAMING X V2            | [868269808a](https://linux-hardware.org/?probe=868269808a) | Jan 29, 2023 |
| ASRock        | P45DE3                      | [e4c2e737f7](https://linux-hardware.org/?probe=e4c2e737f7) | Jan 29, 2023 |
| ASRock        | Z77M                        | [83a27ed2b5](https://linux-hardware.org/?probe=83a27ed2b5) | Jan 29, 2023 |
| ASRock        | G41M-S3                     | [2196343afa](https://linux-hardware.org/?probe=2196343afa) | Jan 29, 2023 |
| ASUSTek       | P7P55D LE                   | [943a02b7e9](https://linux-hardware.org/?probe=943a02b7e9) | Jan 29, 2023 |
| ASUSTek       | P6T SE                      | [c52b5b3357](https://linux-hardware.org/?probe=c52b5b3357) | Jan 29, 2023 |
| ASRock        | B450 Gaming K4              | [e768563b42](https://linux-hardware.org/?probe=e768563b42) | Jan 29, 2023 |
| MSI           | B450M MORTAR MAX            | [017467452c](https://linux-hardware.org/?probe=017467452c) | Jan 29, 2023 |
| Unknown       | X79                         | [164508bcb4](https://linux-hardware.org/?probe=164508bcb4) | Jan 28, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [8492e549e2](https://linux-hardware.org/?probe=8492e549e2) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B460-G GAMING     | [836e9a9809](https://linux-hardware.org/?probe=836e9a9809) | Jan 28, 2023 |
| Acer          | Aspire TC-705               | [be48644835](https://linux-hardware.org/?probe=be48644835) | Jan 27, 2023 |
| ASUSTek       | M2N-MX                      | [0920c10a0e](https://linux-hardware.org/?probe=0920c10a0e) | Jan 27, 2023 |
| Gigabyte      | B85M-D3H-A                  | [8289da39ca](https://linux-hardware.org/?probe=8289da39ca) | Jan 27, 2023 |
| Gigabyte      | 970A-DS3P                   | [547e171057](https://linux-hardware.org/?probe=547e171057) | Jan 27, 2023 |
| ASRock        | B450 Gaming K4              | [7ce2ff0443](https://linux-hardware.org/?probe=7ce2ff0443) | Jan 27, 2023 |
| MSI           | 770-C45                     | [3da3ee46c2](https://linux-hardware.org/?probe=3da3ee46c2) | Jan 26, 2023 |
| ASUSTek       | P6T SE                      | [1033fae7e9](https://linux-hardware.org/?probe=1033fae7e9) | Jan 26, 2023 |
| ASRock        | B650M PG Riptide            | [e9f4894d6d](https://linux-hardware.org/?probe=e9f4894d6d) | Jan 26, 2023 |
| ASUSTek       | P7H55-M                     | [34c55ab8ae](https://linux-hardware.org/?probe=34c55ab8ae) | Jan 26, 2023 |
| iRU           | v1.0                        | [5dfa804f74](https://linux-hardware.org/?probe=5dfa804f74) | Jan 26, 2023 |
| ASUSTek       | P5E-VM SE                   | [0b25483160](https://linux-hardware.org/?probe=0b25483160) | Jan 26, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [883b4a1c39](https://linux-hardware.org/?probe=883b4a1c39) | Jan 26, 2023 |
| MSI           | 770-C45                     | [42ffd24c35](https://linux-hardware.org/?probe=42ffd24c35) | Jan 25, 2023 |
| MSI           | 770-C45                     | [1991e96ff2](https://linux-hardware.org/?probe=1991e96ff2) | Jan 25, 2023 |
| ASRock        | H310CM-DVS                  | [41b1ad4545](https://linux-hardware.org/?probe=41b1ad4545) | Jan 25, 2023 |
| Gigabyte      | B550 GAMING X V2            | [8a7a7f6b72](https://linux-hardware.org/?probe=8a7a7f6b72) | Jan 25, 2023 |
| Gigabyte      | B450M S2H V2                | [e8e7a44a2a](https://linux-hardware.org/?probe=e8e7a44a2a) | Jan 24, 2023 |
| Biostar       | G41-M7                      | [3f66a61637](https://linux-hardware.org/?probe=3f66a61637) | Jan 24, 2023 |
| Pegatron      | IPPPV-D3G                   | [770e25fefd](https://linux-hardware.org/?probe=770e25fefd) | Jan 24, 2023 |
| ASUSTek       | M5A97 R2.0                  | [e2d597c046](https://linux-hardware.org/?probe=e2d597c046) | Jan 24, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [416a11089a](https://linux-hardware.org/?probe=416a11089a) | Jan 23, 2023 |
| ASRock        | B450 Gaming K4              | [0a7ef9990f](https://linux-hardware.org/?probe=0a7ef9990f) | Jan 23, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [257f3b320c](https://linux-hardware.org/?probe=257f3b320c) | Jan 23, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | [10fa3eeed2](https://linux-hardware.org/?probe=10fa3eeed2) | Jan 23, 2023 |
| ASUSTek       | P5K SE                      | [6d55940af7](https://linux-hardware.org/?probe=6d55940af7) | Jan 23, 2023 |
| Gigabyte      | B75M-HD3                    | [77d58eb890](https://linux-hardware.org/?probe=77d58eb890) | Jan 23, 2023 |
| ASUSTek       | Z97-C                       | [3a89f39a8f](https://linux-hardware.org/?probe=3a89f39a8f) | Jan 23, 2023 |
| Gigabyte      | F2A55M-DS2                  | [0e1605a304](https://linux-hardware.org/?probe=0e1605a304) | Jan 22, 2023 |
| Gigabyte      | H310M H                     | [bd85a7e96e](https://linux-hardware.org/?probe=bd85a7e96e) | Jan 22, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [ecfd1795a0](https://linux-hardware.org/?probe=ecfd1795a0) | Jan 22, 2023 |
| ASRock        | B360 Pro4                   | [9cd508a59c](https://linux-hardware.org/?probe=9cd508a59c) | Jan 22, 2023 |
| ASUSTek       | P5E-VM SE                   | [a0b3d87534](https://linux-hardware.org/?probe=a0b3d87534) | Jan 22, 2023 |
| Huanan        | H97-ZD3 V2.0                | [afb82fa3cf](https://linux-hardware.org/?probe=afb82fa3cf) | Jan 22, 2023 |
| MSI           | H97 GAMING 3                | [c861b7e450](https://linux-hardware.org/?probe=c861b7e450) | Jan 22, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [0bf19053f1](https://linux-hardware.org/?probe=0bf19053f1) | Jan 21, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [9672c4222a](https://linux-hardware.org/?probe=9672c4222a) | Jan 21, 2023 |
| ASUSTek       | P7H55-M                     | [18efa12cb2](https://linux-hardware.org/?probe=18efa12cb2) | Jan 21, 2023 |
| MSI           | B75MA-E33                   | [df4c3bb4d2](https://linux-hardware.org/?probe=df4c3bb4d2) | Jan 21, 2023 |
| ASUSTek       | P7H55-USB3                  | [3f270588f4](https://linux-hardware.org/?probe=3f270588f4) | Jan 21, 2023 |
| ASRock        | 880GMH/U3S3                 | [f2dff18301](https://linux-hardware.org/?probe=f2dff18301) | Jan 21, 2023 |
| MSI           | Z490-A PRO                  | [712d12e3e9](https://linux-hardware.org/?probe=712d12e3e9) | Jan 20, 2023 |
| ASUSTek       | P5E-VM SE                   | [b3df4a1dfa](https://linux-hardware.org/?probe=b3df4a1dfa) | Jan 20, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | [4ebd222ef1](https://linux-hardware.org/?probe=4ebd222ef1) | Jan 20, 2023 |
| ECS           | G41T-M7                     | [e6be57e3c3](https://linux-hardware.org/?probe=e6be57e3c3) | Jan 20, 2023 |
| Gigabyte      | H510M H                     | [f44f319e21](https://linux-hardware.org/?probe=f44f319e21) | Jan 20, 2023 |
| Huanan        | X99-F8D V2.4                | [26bc61b381](https://linux-hardware.org/?probe=26bc61b381) | Jan 19, 2023 |
| AZW           | U59                         | [6621409d8c](https://linux-hardware.org/?probe=6621409d8c) | Jan 19, 2023 |
| Biostar       | A780LB                      | [ffce251f42](https://linux-hardware.org/?probe=ffce251f42) | Jan 19, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | [348a5d1848](https://linux-hardware.org/?probe=348a5d1848) | Jan 19, 2023 |
| ASUSTek       | P4P800                      | [f37bee349c](https://linux-hardware.org/?probe=f37bee349c) | Jan 18, 2023 |
| Intel         | DG41MJ AAE54659-206         | [98a0ca82de](https://linux-hardware.org/?probe=98a0ca82de) | Jan 18, 2023 |
| Lenovo        | ThinkCentre M57e 6305B2U    | [fbd4306314](https://linux-hardware.org/?probe=fbd4306314) | Jan 18, 2023 |
| ASRock        | B75 Pro3-M                  | [a42e9dbc36](https://linux-hardware.org/?probe=a42e9dbc36) | Jan 18, 2023 |
| ASRock        | B75 Pro3-M                  | [d4147630a1](https://linux-hardware.org/?probe=d4147630a1) | Jan 18, 2023 |
| ASUSTek       | Z97-K                       | [ac58bc440d](https://linux-hardware.org/?probe=ac58bc440d) | Jan 17, 2023 |
| ASRock        | H410M-HVS                   | [2024f1ae76](https://linux-hardware.org/?probe=2024f1ae76) | Jan 17, 2023 |
| Gigabyte      | 970A-DS3P                   | [b01089cba7](https://linux-hardware.org/?probe=b01089cba7) | Jan 17, 2023 |
| Biostar       | A780LB                      | [fe4d79e9f8](https://linux-hardware.org/?probe=fe4d79e9f8) | Jan 17, 2023 |
| Gigabyte      | 970A-DS3P                   | [bffcece8fb](https://linux-hardware.org/?probe=bffcece8fb) | Jan 17, 2023 |
| Gigabyte      | B450M H                     | [e3638a2110](https://linux-hardware.org/?probe=e3638a2110) | Jan 17, 2023 |
| Gigabyte      | A320M-S2H-CF                | [df0f33ee66](https://linux-hardware.org/?probe=df0f33ee66) | Jan 16, 2023 |
| Intel         | X99                         | [f966e7aa92](https://linux-hardware.org/?probe=f966e7aa92) | Jan 16, 2023 |
| Huanan        | H97-ZD3 V2.0                | [aececc6971](https://linux-hardware.org/?probe=aececc6971) | Jan 16, 2023 |
| MSI           | 970A-G43                    | [f15370df26](https://linux-hardware.org/?probe=f15370df26) | Jan 16, 2023 |
| ECS           | G41T-M7                     | [51a45a431a](https://linux-hardware.org/?probe=51a45a431a) | Jan 16, 2023 |
| Biostar       | H310MHC2                    | [2ebeb3fa1a](https://linux-hardware.org/?probe=2ebeb3fa1a) | Jan 16, 2023 |
| Gigabyte      | MZBSWMP-00                  | [c1660ab5a4](https://linux-hardware.org/?probe=c1660ab5a4) | Jan 16, 2023 |
| Biostar       | H310MHC2                    | [939ab29431](https://linux-hardware.org/?probe=939ab29431) | Jan 16, 2023 |
| MSI           | 970A-G43                    | [669512ff6c](https://linux-hardware.org/?probe=669512ff6c) | Jan 15, 2023 |
| ASUSTek       | P7H55-USB3                  | [d412197c51](https://linux-hardware.org/?probe=d412197c51) | Jan 15, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [fe4b311f78](https://linux-hardware.org/?probe=fe4b311f78) | Jan 15, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [a65831f165](https://linux-hardware.org/?probe=a65831f165) | Jan 15, 2023 |
| ASUSTek       | P5E-VM SE                   | [af5169b24d](https://linux-hardware.org/?probe=af5169b24d) | Jan 15, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [c59c9570d6](https://linux-hardware.org/?probe=c59c9570d6) | Jan 14, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [69819d1ce1](https://linux-hardware.org/?probe=69819d1ce1) | Jan 14, 2023 |
| ASRock        | N68C-S UCC                  | [7c5f173e5c](https://linux-hardware.org/?probe=7c5f173e5c) | Jan 13, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | [7cde78238f](https://linux-hardware.org/?probe=7cde78238f) | Jan 13, 2023 |
| ASUSTek       | P8H77-V LE                  | [ae418043f3](https://linux-hardware.org/?probe=ae418043f3) | Jan 13, 2023 |
| ASUSTek       | P5E-VM SE                   | [feee0755d0](https://linux-hardware.org/?probe=feee0755d0) | Jan 12, 2023 |
| ASRock        | B450M Pro4                  | [5b24178097](https://linux-hardware.org/?probe=5b24178097) | Jan 11, 2023 |
| ASUSTek       | P7H55-USB3                  | [ae85db39c6](https://linux-hardware.org/?probe=ae85db39c6) | Jan 11, 2023 |
| ASUSTek       | A8N32-SLI-Deluxe            | [e9a8dfc18e](https://linux-hardware.org/?probe=e9a8dfc18e) | Jan 11, 2023 |
| Acer          | Aspire TC-605               | [77ecead5ed](https://linux-hardware.org/?probe=77ecead5ed) | Jan 09, 2023 |
| ASUSTek       | P5E-VM SE                   | [d9f3023575](https://linux-hardware.org/?probe=d9f3023575) | Jan 09, 2023 |
| Intel         | DP43BF AAE78171-302         | [ef4b23a73d](https://linux-hardware.org/?probe=ef4b23a73d) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2f03fd41c1](https://linux-hardware.org/?probe=2f03fd41c1) | Jan 09, 2023 |
| Intel         | DP43BF AAE78171-302         | [2a22078fe1](https://linux-hardware.org/?probe=2a22078fe1) | Jan 09, 2023 |
| ASRock        | Z77 Extreme3                | [51f731b0f4](https://linux-hardware.org/?probe=51f731b0f4) | Jan 08, 2023 |
| ASRock        | 960GM-VGS3 FX               | [5b64e74a17](https://linux-hardware.org/?probe=5b64e74a17) | Jan 08, 2023 |
| ASUSTek       | PRIME A320M-K               | [49f4c2fbc8](https://linux-hardware.org/?probe=49f4c2fbc8) | Jan 08, 2023 |
| ASUSTek       | P5QL PRO                    | [e5d4ce1aa7](https://linux-hardware.org/?probe=e5d4ce1aa7) | Jan 08, 2023 |
| MSI           | B450M MORTAR MAX            | [93957e7a70](https://linux-hardware.org/?probe=93957e7a70) | Jan 07, 2023 |
| Gigabyte      | GA-MA770-UD3                | [b4bf97514d](https://linux-hardware.org/?probe=b4bf97514d) | Jan 07, 2023 |
| ASUSTek       | P8H61-M LX2                 | [9193043004](https://linux-hardware.org/?probe=9193043004) | Jan 07, 2023 |
| ASUSTek       | P8H61-M LX2                 | [a6d1d6523b](https://linux-hardware.org/?probe=a6d1d6523b) | Jan 07, 2023 |
| MB            | A320-SF110                  | [d23ec63d82](https://linux-hardware.org/?probe=d23ec63d82) | Jan 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6893b29920](https://linux-hardware.org/?probe=6893b29920) | Jan 07, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [a9288e85f6](https://linux-hardware.org/?probe=a9288e85f6) | Jan 06, 2023 |
| ASRock        | 960GM-VGS3 FX               | [633f31b57e](https://linux-hardware.org/?probe=633f31b57e) | Jan 06, 2023 |
| Gigabyte      | GA-A75M-DS2                 | [843dbca31d](https://linux-hardware.org/?probe=843dbca31d) | Jan 06, 2023 |
| MB            | A320-SF110                  | [5b690cf226](https://linux-hardware.org/?probe=5b690cf226) | Jan 06, 2023 |
| Huanan        | X99-F8 NALEX, NALEX         | [e59b16e379](https://linux-hardware.org/?probe=e59b16e379) | Jan 06, 2023 |
| ASRock        | A320D4-P1                   | [b6a61f9d2d](https://linux-hardware.org/?probe=b6a61f9d2d) | Jan 06, 2023 |
| Gigabyte      | H61M-S1                     | [7b61bf12d0](https://linux-hardware.org/?probe=7b61bf12d0) | Jan 06, 2023 |
| ASRock        | D1800M                      | [f70a4786d7](https://linux-hardware.org/?probe=f70a4786d7) | Jan 06, 2023 |
| ASUSTek       | P7H55-USB3                  | [e94f2584b0](https://linux-hardware.org/?probe=e94f2584b0) | Jan 06, 2023 |
| MSI           | H61M-P20                    | [f48c04fe8f](https://linux-hardware.org/?probe=f48c04fe8f) | Jan 05, 2023 |
| ASRock        | Z77M                        | [fe6f6a7b05](https://linux-hardware.org/?probe=fe6f6a7b05) | Jan 05, 2023 |
| Gigabyte      | H61M-S1                     | [e1b3de18e9](https://linux-hardware.org/?probe=e1b3de18e9) | Jan 05, 2023 |
| ASUSTek       | A55BM-PLUS                  | [8601b7f2e9](https://linux-hardware.org/?probe=8601b7f2e9) | Jan 04, 2023 |
| ASRock        | H510M-HVS                   | [738739788a](https://linux-hardware.org/?probe=738739788a) | Jan 04, 2023 |
| Unknown       | Unknown                     | [5194029152](https://linux-hardware.org/?probe=5194029152) | Jan 04, 2023 |
| Maibenben     | PC34 V1.0                   | [0ed25644b7](https://linux-hardware.org/?probe=0ed25644b7) | Jan 04, 2023 |
| Gigabyte      | P35-DS3L                    | [c07ba0a973](https://linux-hardware.org/?probe=c07ba0a973) | Jan 04, 2023 |
| ECS           | G41T-M2                     | [8df8f82fb8](https://linux-hardware.org/?probe=8df8f82fb8) | Jan 04, 2023 |
| MSI           | A320M GRENADE               | [5e6f9a181c](https://linux-hardware.org/?probe=5e6f9a181c) | Jan 04, 2023 |
| MSI           | MS-B0A41                    | [f57c26d714](https://linux-hardware.org/?probe=f57c26d714) | Jan 04, 2023 |
| Lenovo        | H420                        | [0765ceb3e8](https://linux-hardware.org/?probe=0765ceb3e8) | Jan 04, 2023 |
| ASUSTek       | PRIME B450M-A               | [89868317cd](https://linux-hardware.org/?probe=89868317cd) | Jan 03, 2023 |
| ASRock        | H510M-HDV R2.0              | [f75b0a7e71](https://linux-hardware.org/?probe=f75b0a7e71) | Jan 03, 2023 |
| Gigabyte      | B550M DS3H                  | [c8618e40a6](https://linux-hardware.org/?probe=c8618e40a6) | Jan 03, 2023 |
| ASRock        | H510M-HDV R2.0              | [ee31a67035](https://linux-hardware.org/?probe=ee31a67035) | Jan 03, 2023 |
| ASRock        | N68-GS4 FX                  | [f55d8b7bc9](https://linux-hardware.org/?probe=f55d8b7bc9) | Jan 03, 2023 |
| Gigabyte      | H470M DS3H                  | [07e46fc5f7](https://linux-hardware.org/?probe=07e46fc5f7) | Jan 03, 2023 |
| ASUSTek       | PRIME B560M-A               | [3a801b9e90](https://linux-hardware.org/?probe=3a801b9e90) | Jan 01, 2023 |
| Huanan        | X99 F8D V2.2                | [c1818201ce](https://linux-hardware.org/?probe=c1818201ce) | Jan 01, 2023 |
| ASUSTek       | P8H67                       | [33bf029e5f](https://linux-hardware.org/?probe=33bf029e5f) | Jan 01, 2023 |
| ASUSTek       | PRIME B550M-A               | [2161cbc9a0](https://linux-hardware.org/?probe=2161cbc9a0) | Dec 31, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [7b10613c1e](https://linux-hardware.org/?probe=7b10613c1e) | Dec 31, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [92920d8ac2](https://linux-hardware.org/?probe=92920d8ac2) | Dec 31, 2022 |
| Gigabyte      | H55M-USB3                   | [729e1569a8](https://linux-hardware.org/?probe=729e1569a8) | Dec 30, 2022 |
| MSI           | B360M GAMING PLUS           | [9d4f6afc25](https://linux-hardware.org/?probe=9d4f6afc25) | Dec 30, 2022 |
| ASUSTek       | P8Z77-V                     | [b0a607e8d8](https://linux-hardware.org/?probe=b0a607e8d8) | Dec 30, 2022 |
| AZW           | U59                         | [290e34b89a](https://linux-hardware.org/?probe=290e34b89a) | Dec 30, 2022 |
| ASRock        | N68-GS4 FX                  | [379552e4d2](https://linux-hardware.org/?probe=379552e4d2) | Dec 30, 2022 |
| Gigabyte      | B550 GAMING X               | [6e92b3e37b](https://linux-hardware.org/?probe=6e92b3e37b) | Dec 29, 2022 |
| ASUSTek       | H97-PRO                     | [b96b861fd7](https://linux-hardware.org/?probe=b96b861fd7) | Dec 29, 2022 |
| ASUSTek       | PRIME A320M-A               | [2cdb821b42](https://linux-hardware.org/?probe=2cdb821b42) | Dec 29, 2022 |
| Gigabyte      | B360M HD3                   | [556bc61c51](https://linux-hardware.org/?probe=556bc61c51) | Dec 29, 2022 |
| Gigabyte      | B360M HD3                   | [f0ab6f0649](https://linux-hardware.org/?probe=f0ab6f0649) | Dec 29, 2022 |
| ASRock        | B450 Gaming K4              | [1afc5015f1](https://linux-hardware.org/?probe=1afc5015f1) | Dec 28, 2022 |
| ASUSTek       | M4A79XTD EVO                | [91c217e497](https://linux-hardware.org/?probe=91c217e497) | Dec 28, 2022 |
| ASUSTek       | M4A785-M                    | [7fb63e4360](https://linux-hardware.org/?probe=7fb63e4360) | Dec 27, 2022 |
| Dell          | 0XHGV1 A01                  | [415c0ff63e](https://linux-hardware.org/?probe=415c0ff63e) | Dec 27, 2022 |
| MSI           | B350 PC MATE                | [3b9dbdb180](https://linux-hardware.org/?probe=3b9dbdb180) | Dec 27, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [1aac1f7eca](https://linux-hardware.org/?probe=1aac1f7eca) | Dec 27, 2022 |
| Gigabyte      | H97-HD3                     | [1707593d6d](https://linux-hardware.org/?probe=1707593d6d) | Dec 27, 2022 |
| ASRock        | H510M-HVS                   | [3733446191](https://linux-hardware.org/?probe=3733446191) | Dec 27, 2022 |
| Gigabyte      | B365M DS3H                  | [f9d83535bd](https://linux-hardware.org/?probe=f9d83535bd) | Dec 26, 2022 |
| Gigabyte      | F2A55M-DS2                  | [735d3cfda2](https://linux-hardware.org/?probe=735d3cfda2) | Dec 26, 2022 |
| Dell          | 0XHGV1 A01                  | [5d26c7c543](https://linux-hardware.org/?probe=5d26c7c543) | Dec 26, 2022 |
| ASUSTek       | P8H61-MX R2.0               | [5174af9fdd](https://linux-hardware.org/?probe=5174af9fdd) | Dec 25, 2022 |
| ASUSTek       | H81M-K                      | [c702bed39d](https://linux-hardware.org/?probe=c702bed39d) | Dec 25, 2022 |
| ASUSTek       | P7H55-M/USB3                | [85b55a267a](https://linux-hardware.org/?probe=85b55a267a) | Dec 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [8994b9a877](https://linux-hardware.org/?probe=8994b9a877) | Dec 25, 2022 |
| HP            | 0AACh                       | [b83da338ee](https://linux-hardware.org/?probe=b83da338ee) | Dec 25, 2022 |
| Gigabyte      | B450M DS3H-CF               | [f48ac4aa81](https://linux-hardware.org/?probe=f48ac4aa81) | Dec 25, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [b98be1b1e7](https://linux-hardware.org/?probe=b98be1b1e7) | Dec 25, 2022 |
| ASRock        | A75M-HVS                    | [5368526dc0](https://linux-hardware.org/?probe=5368526dc0) | Dec 25, 2022 |
| ASRock        | A75M-HVS                    | [fab270a7bf](https://linux-hardware.org/?probe=fab270a7bf) | Dec 25, 2022 |
| ASRock        | B365M-HDV                   | [84ea64b29c](https://linux-hardware.org/?probe=84ea64b29c) | Dec 24, 2022 |
| ASRock        | B365M-HDV                   | [407f76f02f](https://linux-hardware.org/?probe=407f76f02f) | Dec 24, 2022 |
| ASRock        | B450 Gaming K4              | [bb8b44cf69](https://linux-hardware.org/?probe=bb8b44cf69) | Dec 24, 2022 |
| ASRock        | H510M-HDV R2.0              | [70312467b7](https://linux-hardware.org/?probe=70312467b7) | Dec 24, 2022 |
| Gigabyte      | B660M D2H DDR4              | [c34803fb1e](https://linux-hardware.org/?probe=c34803fb1e) | Dec 24, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [6f60f1b6da](https://linux-hardware.org/?probe=6f60f1b6da) | Dec 24, 2022 |
| Dell          | 0Y5DDC A00                  | [c107bb3a14](https://linux-hardware.org/?probe=c107bb3a14) | Dec 24, 2022 |
| ASUSTek       | P8B75-V                     | [cf3882b3f7](https://linux-hardware.org/?probe=cf3882b3f7) | Dec 24, 2022 |
| Gigabyte      | H55M-S2H                    | [7cecfa756a](https://linux-hardware.org/?probe=7cecfa756a) | Dec 24, 2022 |
| HP            | 0AACh                       | [4a7840e1cf](https://linux-hardware.org/?probe=4a7840e1cf) | Dec 24, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [40c2593694](https://linux-hardware.org/?probe=40c2593694) | Dec 24, 2022 |
| Gigabyte      | A320M-H-CF                  | [81febc2905](https://linux-hardware.org/?probe=81febc2905) | Dec 23, 2022 |
| ASUSTek       | H97-PLUS                    | [0d45265efc](https://linux-hardware.org/?probe=0d45265efc) | Dec 23, 2022 |
| Unknown       | 865GV-ICH5                  | [fe2ef2ef31](https://linux-hardware.org/?probe=fe2ef2ef31) | Dec 23, 2022 |
| ASUSTek       | H81M-C                      | [73dc1109eb](https://linux-hardware.org/?probe=73dc1109eb) | Dec 23, 2022 |
| Gigabyte      | H310M A-CF x.x              | [daf1310bfa](https://linux-hardware.org/?probe=daf1310bfa) | Dec 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ae98ccd9c2](https://linux-hardware.org/?probe=ae98ccd9c2) | Dec 22, 2022 |
| Unknown       | 865GV-ICH5                  | [f42b7383f4](https://linux-hardware.org/?probe=f42b7383f4) | Dec 22, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | [2683bf55bf](https://linux-hardware.org/?probe=2683bf55bf) | Dec 22, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [c485d688ad](https://linux-hardware.org/?probe=c485d688ad) | Dec 22, 2022 |
| ASUSTek       | P5K PRO                     | [4088ff40e3](https://linux-hardware.org/?probe=4088ff40e3) | Dec 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | [10a98289bb](https://linux-hardware.org/?probe=10a98289bb) | Dec 21, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [b7311f5a21](https://linux-hardware.org/?probe=b7311f5a21) | Dec 21, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [c39538e70e](https://linux-hardware.org/?probe=c39538e70e) | Dec 21, 2022 |
| ASRock        | ALiveXFire-eSATA2           | [e7383e309b](https://linux-hardware.org/?probe=e7383e309b) | Dec 21, 2022 |
| ASUSTek       | M2N-E                       | [d27a2a4e0f](https://linux-hardware.org/?probe=d27a2a4e0f) | Dec 20, 2022 |
| Gigabyte      | EP43-S3L                    | [8a24afa21d](https://linux-hardware.org/?probe=8a24afa21d) | Dec 20, 2022 |
| Intel         | X99                         | [ce9b83b781](https://linux-hardware.org/?probe=ce9b83b781) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [e7cfce65f6](https://linux-hardware.org/?probe=e7cfce65f6) | Dec 20, 2022 |
| ASUSTek       | P5QL PRO                    | [44d3238797](https://linux-hardware.org/?probe=44d3238797) | Dec 20, 2022 |
| Gigabyte      | H77N-WIFI                   | [a39b8f54af](https://linux-hardware.org/?probe=a39b8f54af) | Dec 20, 2022 |
| ASUSTek       | M4A79XTD EVO                | [7c854ad5e0](https://linux-hardware.org/?probe=7c854ad5e0) | Dec 20, 2022 |
| ASUSTek       | M4A79XTD EVO                | [f82010222c](https://linux-hardware.org/?probe=f82010222c) | Dec 20, 2022 |
| ASRock        | Z77M                        | [33c2afa3e0](https://linux-hardware.org/?probe=33c2afa3e0) | Dec 20, 2022 |
| ASUSTek       | PRIME B450M-K               | [de20614d06](https://linux-hardware.org/?probe=de20614d06) | Dec 19, 2022 |
| Gigabyte      | 970A-DS3P                   | [66e45d9a82](https://linux-hardware.org/?probe=66e45d9a82) | Dec 19, 2022 |
| ASUSTek       | PRIME B450M-K               | [90ea21bd4a](https://linux-hardware.org/?probe=90ea21bd4a) | Dec 19, 2022 |
| ASUSTek       | P7P55D EVO                  | [c8f2df83aa](https://linux-hardware.org/?probe=c8f2df83aa) | Dec 19, 2022 |
| ASRock        | P67 Pro3 SE                 | [5a59282fea](https://linux-hardware.org/?probe=5a59282fea) | Dec 19, 2022 |
| Dell          | 0Y5DDC A00                  | [aa5228e9b8](https://linux-hardware.org/?probe=aa5228e9b8) | Dec 19, 2022 |
| Intel         | MAHOBAY                     | [7f8c2370d4](https://linux-hardware.org/?probe=7f8c2370d4) | Dec 19, 2022 |
| Gigabyte      | GA-K8NE                     | [64adeb3e60](https://linux-hardware.org/?probe=64adeb3e60) | Dec 18, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [626b750c51](https://linux-hardware.org/?probe=626b750c51) | Dec 18, 2022 |
| ASUSTek       | P8H61-MX R2.0               | [320ef20ffa](https://linux-hardware.org/?probe=320ef20ffa) | Dec 18, 2022 |
| ASUSTek       | PRIME X470-PRO              | [7e864dc271](https://linux-hardware.org/?probe=7e864dc271) | Dec 18, 2022 |
| Gigabyte      | P41T-D3P                    | [20f90ee21e](https://linux-hardware.org/?probe=20f90ee21e) | Dec 18, 2022 |
| MSI           | MS-B0A41                    | [3eff37d029](https://linux-hardware.org/?probe=3eff37d029) | Dec 18, 2022 |
| Gigabyte      | H110N-CF                    | [239dcc2a5c](https://linux-hardware.org/?probe=239dcc2a5c) | Dec 18, 2022 |
| ASUSTek       | A88XM-A                     | [e889711ed9](https://linux-hardware.org/?probe=e889711ed9) | Dec 17, 2022 |
| ASUSTek       | M2N-XE                      | [5cf5b3eb1b](https://linux-hardware.org/?probe=5cf5b3eb1b) | Dec 17, 2022 |
| ASRock        | X570 Pro4                   | [09fc64653e](https://linux-hardware.org/?probe=09fc64653e) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [00cc810cfc](https://linux-hardware.org/?probe=00cc810cfc) | Dec 17, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | [74133cd0bd](https://linux-hardware.org/?probe=74133cd0bd) | Dec 17, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [0eb4a7c919](https://linux-hardware.org/?probe=0eb4a7c919) | Dec 17, 2022 |
| Gigabyte      | F2A55M-DS2                  | [d34f278afd](https://linux-hardware.org/?probe=d34f278afd) | Dec 17, 2022 |
| Gigabyte      | 970A-DS3P                   | [f0303dc0a9](https://linux-hardware.org/?probe=f0303dc0a9) | Dec 17, 2022 |
| Gigabyte      | H81-D3                      | [547126e9e7](https://linux-hardware.org/?probe=547126e9e7) | Dec 17, 2022 |
| Gigabyte      | H110M-M2-CF                 | [11c0643905](https://linux-hardware.org/?probe=11c0643905) | Dec 16, 2022 |
| Graviton      | DMB-H510-MCA01              | [702f634fc4](https://linux-hardware.org/?probe=702f634fc4) | Dec 16, 2022 |
| Gigabyte      | P75-D3                      | [32b4b4d664](https://linux-hardware.org/?probe=32b4b4d664) | Dec 16, 2022 |
| Huanan        | X99-QD4 V1.0                | [a959e56dc8](https://linux-hardware.org/?probe=a959e56dc8) | Dec 15, 2022 |
| Intel         | SHARKBAY                    | [0d07341d58](https://linux-hardware.org/?probe=0d07341d58) | Dec 15, 2022 |
| MSI           | K9N6PGM2-V2                 | [c25f374572](https://linux-hardware.org/?probe=c25f374572) | Dec 15, 2022 |
| ASUSTek       | H110M-R                     | [6367cb9215](https://linux-hardware.org/?probe=6367cb9215) | Dec 15, 2022 |
| ASRock        | A520M Pro4                  | [9a6fcc5f1b](https://linux-hardware.org/?probe=9a6fcc5f1b) | Dec 15, 2022 |
| ASUSTek       | PRIME B450M-A               | [766e33e4fb](https://linux-hardware.org/?probe=766e33e4fb) | Dec 15, 2022 |
| ASUSTek       | H110M-R                     | [db904895cc](https://linux-hardware.org/?probe=db904895cc) | Dec 15, 2022 |
| ASUSTek       | F2A55-M LE                  | [f4c6e3c225](https://linux-hardware.org/?probe=f4c6e3c225) | Dec 14, 2022 |
| Gigabyte      | H77N-WIFI                   | [5093772c0f](https://linux-hardware.org/?probe=5093772c0f) | Dec 14, 2022 |
| Intel         | X79v2.72 KD V2.0            | [0e58af2a59](https://linux-hardware.org/?probe=0e58af2a59) | Dec 14, 2022 |
| Gigabyte      | B85M-D3V-A                  | [22431e9b10](https://linux-hardware.org/?probe=22431e9b10) | Dec 13, 2022 |
| Gigabyte      | B85M-D3V-A                  | [0e9eba0773](https://linux-hardware.org/?probe=0e9eba0773) | Dec 13, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [af674c6b1b](https://linux-hardware.org/?probe=af674c6b1b) | Dec 13, 2022 |
| ASUSTek       | PRIME H270-PRO              | [dc7d6ae170](https://linux-hardware.org/?probe=dc7d6ae170) | Dec 13, 2022 |
| Intel         | X79v2.72 KD V2.0            | [476f1e7cad](https://linux-hardware.org/?probe=476f1e7cad) | Dec 12, 2022 |
| MSI           | K9N6PGM2-V2                 | [f09e3c0e19](https://linux-hardware.org/?probe=f09e3c0e19) | Dec 12, 2022 |
| Gigabyte      | B450 GAMING X               | [8918608744](https://linux-hardware.org/?probe=8918608744) | Dec 12, 2022 |
| Gigabyte      | H310M A-CF x.x              | [2e0158ba73](https://linux-hardware.org/?probe=2e0158ba73) | Dec 12, 2022 |
| Gigabyte      | H310M A-CF x.x              | [c6e03bcd07](https://linux-hardware.org/?probe=c6e03bcd07) | Dec 12, 2022 |
| Gigabyte      | M61SME-S2                   | [e2932e425c](https://linux-hardware.org/?probe=e2932e425c) | Dec 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [f0fa1101ce](https://linux-hardware.org/?probe=f0fa1101ce) | Dec 11, 2022 |
| ECS           | H61H2-M3                    | [dcd96a2b45](https://linux-hardware.org/?probe=dcd96a2b45) | Dec 11, 2022 |
| ECS           | H61H2-M3                    | [9f9fafa75b](https://linux-hardware.org/?probe=9f9fafa75b) | Dec 11, 2022 |
| ASUSTek       | Z170-K                      | [f883834ef1](https://linux-hardware.org/?probe=f883834ef1) | Dec 11, 2022 |
| HP            | 8860 A                      | [c039452bd4](https://linux-hardware.org/?probe=c039452bd4) | Dec 11, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | [9f72d262ef](https://linux-hardware.org/?probe=9f72d262ef) | Dec 11, 2022 |
| ASUSTek       | Z170-K                      | [8bd005fd95](https://linux-hardware.org/?probe=8bd005fd95) | Dec 11, 2022 |
| ASUSTek       | PRIME B360M-K               | [aac6da2dfb](https://linux-hardware.org/?probe=aac6da2dfb) | Dec 11, 2022 |
| Gigabyte      | H77-DS3H                    | [4c52e333dd](https://linux-hardware.org/?probe=4c52e333dd) | Dec 10, 2022 |
| ASRock        | H81M-HDS R2.0               | [e3c2a2bc54](https://linux-hardware.org/?probe=e3c2a2bc54) | Dec 10, 2022 |
| Intel         | D2500HN AAG81480-500        | [0963fa0173](https://linux-hardware.org/?probe=0963fa0173) | Dec 10, 2022 |
| ASUSTek       | PRIME B350M-A               | [619a4c2f87](https://linux-hardware.org/?probe=619a4c2f87) | Dec 10, 2022 |
| ASRock        | 760GM-HDV                   | [bbd75ce275](https://linux-hardware.org/?probe=bbd75ce275) | Dec 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [941668ad89](https://linux-hardware.org/?probe=941668ad89) | Dec 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [fc07cad186](https://linux-hardware.org/?probe=fc07cad186) | Dec 10, 2022 |
| HP            | 158A                        | [ebcf08f784](https://linux-hardware.org/?probe=ebcf08f784) | Dec 10, 2022 |
| ASRock        | H97 Anniversary             | [3f7aa1b6de](https://linux-hardware.org/?probe=3f7aa1b6de) | Dec 10, 2022 |
| ASUSTek       | PRIME X570-P                | [f064a744ba](https://linux-hardware.org/?probe=f064a744ba) | Dec 10, 2022 |
| ASUSTek       | Z170-A                      | [c9df3386c5](https://linux-hardware.org/?probe=c9df3386c5) | Dec 10, 2022 |
| Gigabyte      | H61N-USB3                   | [9a8885a88d](https://linux-hardware.org/?probe=9a8885a88d) | Dec 09, 2022 |
| ASUSTek       | M5A97 R2.0                  | [75f1600dba](https://linux-hardware.org/?probe=75f1600dba) | Dec 09, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [ed30003f61](https://linux-hardware.org/?probe=ed30003f61) | Dec 09, 2022 |
| Gigabyte      | D425TUD                     | [4d8c330a78](https://linux-hardware.org/?probe=4d8c330a78) | Dec 09, 2022 |
| HP            | 18E7                        | [3ae864582a](https://linux-hardware.org/?probe=3ae864582a) | Dec 09, 2022 |
| Aquarius      | AQB560M                     | [b4bd04a5a0](https://linux-hardware.org/?probe=b4bd04a5a0) | Dec 09, 2022 |
| Aquarius      | AQB560M                     | [56a6a749bb](https://linux-hardware.org/?probe=56a6a749bb) | Dec 09, 2022 |
| Gigabyte      | G31M-S2L                    | [05707c88e0](https://linux-hardware.org/?probe=05707c88e0) | Dec 08, 2022 |
| Gigabyte      | H81M-S1                     | [c2ba58af35](https://linux-hardware.org/?probe=c2ba58af35) | Dec 08, 2022 |
| Biostar       | GF8200C M2+                 | [e42ae4deef](https://linux-hardware.org/?probe=e42ae4deef) | Dec 08, 2022 |
| Gigabyte      | H61M-S2V-B3                 | [4462cb3156](https://linux-hardware.org/?probe=4462cb3156) | Dec 08, 2022 |
| Gigabyte      | P31-ES3G                    | [21c291e1e2](https://linux-hardware.org/?probe=21c291e1e2) | Dec 08, 2022 |
| Huanan        | X99 F8D V2.2                | [d960add854](https://linux-hardware.org/?probe=d960add854) | Dec 08, 2022 |
| ASUSTek       | P5W DH Deluxe               | [bedb81f629](https://linux-hardware.org/?probe=bedb81f629) | Dec 08, 2022 |
| Aquarius      | AQB560M                     | [3ac41202cf](https://linux-hardware.org/?probe=3ac41202cf) | Dec 08, 2022 |
| ASUSTek       | P8Z77-V LE PLUS             | [eafc4dffd4](https://linux-hardware.org/?probe=eafc4dffd4) | Dec 07, 2022 |
| ASUSTek       | PRIME B460M-K               | [ceff27eeef](https://linux-hardware.org/?probe=ceff27eeef) | Dec 07, 2022 |
| eMachines     | ET1350                      | [2d05a7a068](https://linux-hardware.org/?probe=2d05a7a068) | Dec 07, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [038581b13f](https://linux-hardware.org/?probe=038581b13f) | Dec 07, 2022 |
| ASUSTek       | M2N-XE                      | [663b3c7870](https://linux-hardware.org/?probe=663b3c7870) | Dec 06, 2022 |
| ASRock        | P67 Pro                     | [74b28c3c76](https://linux-hardware.org/?probe=74b28c3c76) | Dec 06, 2022 |
| ASRock        | B450M-HDV                   | [afeed5f423](https://linux-hardware.org/?probe=afeed5f423) | Dec 05, 2022 |
| Gigabyte      | 970A-DS3P                   | [517e06781a](https://linux-hardware.org/?probe=517e06781a) | Dec 05, 2022 |
| Gigabyte      | B450 GAMING X               | [c8b886d9bf](https://linux-hardware.org/?probe=c8b886d9bf) | Dec 05, 2022 |
| ASUSTek       | PRIME A320M-K               | [0301ad14ee](https://linux-hardware.org/?probe=0301ad14ee) | Dec 05, 2022 |
| MSI           | H97 PC Mate                 | [b8081159ab](https://linux-hardware.org/?probe=b8081159ab) | Dec 05, 2022 |
| ASUSTek       | PRIME B450M-A               | [10dd0b119a](https://linux-hardware.org/?probe=10dd0b119a) | Dec 04, 2022 |
| Unknown       | Unknown                     | [bdf0020add](https://linux-hardware.org/?probe=bdf0020add) | Dec 04, 2022 |
| HP            | 2AAC                        | [a6fb7751ed](https://linux-hardware.org/?probe=a6fb7751ed) | Dec 04, 2022 |
| Intel         | DG41CN AAE82429-102         | [8d5cd3253c](https://linux-hardware.org/?probe=8d5cd3253c) | Dec 04, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [d3c99c8d63](https://linux-hardware.org/?probe=d3c99c8d63) | Dec 04, 2022 |
| Intel         | D2500HN AAG34776-404        | [b1ccefe421](https://linux-hardware.org/?probe=b1ccefe421) | Dec 04, 2022 |
| ASUSTek       | H81M-C                      | [0218d4ec25](https://linux-hardware.org/?probe=0218d4ec25) | Dec 03, 2022 |
| Gigabyte      | P35-DS3                     | [f4be331a61](https://linux-hardware.org/?probe=f4be331a61) | Dec 03, 2022 |
| ASUSTek       | H81M-C                      | [ea7168ab4c](https://linux-hardware.org/?probe=ea7168ab4c) | Dec 03, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [1d881e7756](https://linux-hardware.org/?probe=1d881e7756) | Dec 03, 2022 |
| ASRock        | K10N78D                     | [7d0d581c7a](https://linux-hardware.org/?probe=7d0d581c7a) | Dec 03, 2022 |
| Gigabyte      | A320M-H-CF                  | [f1e82e8a2a](https://linux-hardware.org/?probe=f1e82e8a2a) | Dec 03, 2022 |
| Gigabyte      | 970A-UD3P                   | [7bb879efed](https://linux-hardware.org/?probe=7bb879efed) | Dec 03, 2022 |
| Gigabyte      | MZBSWMP-00                  | [76ba1ef6f2](https://linux-hardware.org/?probe=76ba1ef6f2) | Dec 03, 2022 |
| MSI           | P67S-C43                    | [9674663124](https://linux-hardware.org/?probe=9674663124) | Dec 03, 2022 |
| ASUSTek       | Z170M-PLUS                  | [a39dbe7189](https://linux-hardware.org/?probe=a39dbe7189) | Dec 03, 2022 |
| Intel         | JSL MRD                     | [1a63097a67](https://linux-hardware.org/?probe=1a63097a67) | Dec 02, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [5c0129ab3f](https://linux-hardware.org/?probe=5c0129ab3f) | Dec 02, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [eaaeeb57fe](https://linux-hardware.org/?probe=eaaeeb57fe) | Dec 02, 2022 |
| HP            | 18E7                        | [37c3c7db33](https://linux-hardware.org/?probe=37c3c7db33) | Dec 02, 2022 |
| 3Q            | TD2500G-P-Q3 A01            | [46626558f6](https://linux-hardware.org/?probe=46626558f6) | Dec 01, 2022 |
| ASUSTek       | AT3IONT-I DELUXE            | [16680c5211](https://linux-hardware.org/?probe=16680c5211) | Dec 01, 2022 |
| Gigabyte      | B450 GAMING X               | [ff5aef2f59](https://linux-hardware.org/?probe=ff5aef2f59) | Dec 01, 2022 |
| MSI           | H81M-E33                    | [aa874580d3](https://linux-hardware.org/?probe=aa874580d3) | Dec 01, 2022 |
| HP            | 8184 X4                     | [2b5ea5e34c](https://linux-hardware.org/?probe=2b5ea5e34c) | Dec 01, 2022 |
| ASUSTek       | PRIME B460M-K               | [c8dd66d6de](https://linux-hardware.org/?probe=c8dd66d6de) | Dec 01, 2022 |
| ASUSTek       | P8H77-V LE                  | [d82ed03dd9](https://linux-hardware.org/?probe=d82ed03dd9) | Dec 01, 2022 |
| ASUSTek       | SABERTOOTH X58              | [4ae619c728](https://linux-hardware.org/?probe=4ae619c728) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [4e6ae396d9](https://linux-hardware.org/?probe=4e6ae396d9) | Nov 30, 2022 |
| ASUSTek       | H81M-C                      | [458ea4bd06](https://linux-hardware.org/?probe=458ea4bd06) | Nov 29, 2022 |
| ASUSTek       | M5A78L/USB3                 | [99c33f6741](https://linux-hardware.org/?probe=99c33f6741) | Nov 29, 2022 |
| HP            | 8437                        | [c5bbfc32f6](https://linux-hardware.org/?probe=c5bbfc32f6) | Nov 29, 2022 |
| Lenovo        | 3162 SDK0J40697 WIN 3305... | [296ceaab80](https://linux-hardware.org/?probe=296ceaab80) | Nov 29, 2022 |
| ASRock        | N68C-S UCC                  | [c7bff3d908](https://linux-hardware.org/?probe=c7bff3d908) | Nov 29, 2022 |
| ASUSTek       | Q170T                       | [99abcc63ab](https://linux-hardware.org/?probe=99abcc63ab) | Nov 29, 2022 |
| Dell          | 0Y5DDC A00                  | [5d4811b390](https://linux-hardware.org/?probe=5d4811b390) | Nov 29, 2022 |
| Gigabyte      | A320M-H-CF                  | [66fe0c3ddf](https://linux-hardware.org/?probe=66fe0c3ddf) | Nov 29, 2022 |
| ECS           | BSWI-D2                     | [b7e4fbdd31](https://linux-hardware.org/?probe=b7e4fbdd31) | Nov 29, 2022 |
| MSI           | K9N6PGM2-V2                 | [b2eb1eccbd](https://linux-hardware.org/?probe=b2eb1eccbd) | Nov 28, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [245ea45167](https://linux-hardware.org/?probe=245ea45167) | Nov 28, 2022 |
| HP            | 82F1                        | [17ed0cee6a](https://linux-hardware.org/?probe=17ed0cee6a) | Nov 28, 2022 |
| MSI           | K9N6PGM2-V2                 | [82b84f846b](https://linux-hardware.org/?probe=82b84f846b) | Nov 27, 2022 |
| Gigabyte      | B550 GAMING X               | [f8979201eb](https://linux-hardware.org/?probe=f8979201eb) | Nov 27, 2022 |
| Unknown       | Unknown                     | [1a24753132](https://linux-hardware.org/?probe=1a24753132) | Nov 27, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [3fda27c7b6](https://linux-hardware.org/?probe=3fda27c7b6) | Nov 27, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [e6a6d0affd](https://linux-hardware.org/?probe=e6a6d0affd) | Nov 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [2a77cd8415](https://linux-hardware.org/?probe=2a77cd8415) | Nov 27, 2022 |
| ASUSTek       | PRIME B250M-K               | [73b4c53383](https://linux-hardware.org/?probe=73b4c53383) | Nov 27, 2022 |
| ASUSTek       | P7H55-USB3                  | [ff31791cfb](https://linux-hardware.org/?probe=ff31791cfb) | Nov 27, 2022 |
| ASUSTek       | P7H55-USB3                  | [e09f910876](https://linux-hardware.org/?probe=e09f910876) | Nov 27, 2022 |
| MACHINIST     | X99-RS9 V3.1                | [86cead0335](https://linux-hardware.org/?probe=86cead0335) | Nov 27, 2022 |
| ASUSTek       | H110M-R                     | [f35782a773](https://linux-hardware.org/?probe=f35782a773) | Nov 26, 2022 |
| ASUSTek       | PRIME B450M-A               | [f368bfcbe2](https://linux-hardware.org/?probe=f368bfcbe2) | Nov 26, 2022 |
| Gigabyte      | B560 HD3                    | [f7915b54fb](https://linux-hardware.org/?probe=f7915b54fb) | Nov 26, 2022 |
| ASUSTek       | PRIME B460M-K               | [7df334aaa0](https://linux-hardware.org/?probe=7df334aaa0) | Nov 26, 2022 |
| Unknown       | PCWARE APMCP68              | [0cb03d53bb](https://linux-hardware.org/?probe=0cb03d53bb) | Nov 26, 2022 |
| ASUSTek       | P8H77-V LE                  | [c17b2fcd65](https://linux-hardware.org/?probe=c17b2fcd65) | Nov 26, 2022 |
| MSI           | K9AG Neo2                   | [a57a6f079b](https://linux-hardware.org/?probe=a57a6f079b) | Nov 25, 2022 |
| ASRock        | H55M-LE                     | [75b9a8fb03](https://linux-hardware.org/?probe=75b9a8fb03) | Nov 25, 2022 |
| JGINYUE       | B660M-VDH                   | [bd879c87f8](https://linux-hardware.org/?probe=bd879c87f8) | Nov 25, 2022 |
| ASUSTek       | P5K                         | [87e7a3c0d0](https://linux-hardware.org/?probe=87e7a3c0d0) | Nov 25, 2022 |
| ASUSTek       | P8H61-MX                    | [d2e3977693](https://linux-hardware.org/?probe=d2e3977693) | Nov 25, 2022 |
| ASUSTek       | P5P43TD                     | [324669845a](https://linux-hardware.org/?probe=324669845a) | Nov 24, 2022 |
| ASUSTek       | PRIME X370-PRO              | [8a5a155a45](https://linux-hardware.org/?probe=8a5a155a45) | Nov 24, 2022 |
| ASUSTek       | P5KPL-VM                    | [4e15e21f75](https://linux-hardware.org/?probe=4e15e21f75) | Nov 24, 2022 |
| ASUSTek       | H81M-C                      | [e892605084](https://linux-hardware.org/?probe=e892605084) | Nov 24, 2022 |
| ASUSTek       | P5K Premium                 | [5ff50a49ba](https://linux-hardware.org/?probe=5ff50a49ba) | Nov 23, 2022 |
| Gigabyte      | GA-78LMT-S2                 | [a17992aaa3](https://linux-hardware.org/?probe=a17992aaa3) | Nov 23, 2022 |
| Gigabyte      | H77N-WIFI                   | [4617b6803a](https://linux-hardware.org/?probe=4617b6803a) | Nov 23, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [e83d79d385](https://linux-hardware.org/?probe=e83d79d385) | Nov 23, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [64728372e9](https://linux-hardware.org/?probe=64728372e9) | Nov 23, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [3a36391d83](https://linux-hardware.org/?probe=3a36391d83) | Nov 22, 2022 |
| Gigabyte      | B450 GAMING X               | [c427f12dca](https://linux-hardware.org/?probe=c427f12dca) | Nov 22, 2022 |
| ASUSTek       | PRIME B450M-K               | [2438420107](https://linux-hardware.org/?probe=2438420107) | Nov 22, 2022 |
| ASUSTek       | P8H61-I LX                  | [a537f96848](https://linux-hardware.org/?probe=a537f96848) | Nov 22, 2022 |
| Gigabyte      | 970A-UD3P                   | [2cd736b247](https://linux-hardware.org/?probe=2cd736b247) | Nov 22, 2022 |
| ASUSTek       | PRIME B450M-A               | [49cb3f2e52](https://linux-hardware.org/?probe=49cb3f2e52) | Nov 22, 2022 |
| Biostar       | G41D3+                      | [6ce48937fe](https://linux-hardware.org/?probe=6ce48937fe) | Nov 22, 2022 |
| Dell          | 0Y5DDC A00                  | [37808c6686](https://linux-hardware.org/?probe=37808c6686) | Nov 22, 2022 |
| ASRock        | H55M-LE                     | [206082ac3f](https://linux-hardware.org/?probe=206082ac3f) | Nov 22, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | [2575d2aab2](https://linux-hardware.org/?probe=2575d2aab2) | Nov 22, 2022 |
| Gigabyte      | B75M-D3V                    | [06396e3088](https://linux-hardware.org/?probe=06396e3088) | Nov 21, 2022 |
| MSI           | PRO H410M-B                 | [a81c612515](https://linux-hardware.org/?probe=a81c612515) | Nov 21, 2022 |
| MSI           | PRO H410M-B                 | [ebc5b13d4e](https://linux-hardware.org/?probe=ebc5b13d4e) | Nov 21, 2022 |
| Biostar       | G41D3+                      | [d1d42fec13](https://linux-hardware.org/?probe=d1d42fec13) | Nov 21, 2022 |
| Intel         | DG45ID AAE27729-310         | [81ecca3cd1](https://linux-hardware.org/?probe=81ecca3cd1) | Nov 20, 2022 |
| ASUSTek       | M4A785T-M                   | [451b8a6b52](https://linux-hardware.org/?probe=451b8a6b52) | Nov 20, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [122a37af55](https://linux-hardware.org/?probe=122a37af55) | Nov 20, 2022 |
| ASUSTek       | M5A78L-M LX3                | [b133dcd886](https://linux-hardware.org/?probe=b133dcd886) | Nov 20, 2022 |
| ASUSTek       | P7H55                       | [aaaefec31e](https://linux-hardware.org/?probe=aaaefec31e) | Nov 20, 2022 |
| ASRock        | P43ME                       | [3b90870750](https://linux-hardware.org/?probe=3b90870750) | Nov 20, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | [5cf9d6d04e](https://linux-hardware.org/?probe=5cf9d6d04e) | Nov 20, 2022 |
| Huanan        | B75                         | [cfc1803ca1](https://linux-hardware.org/?probe=cfc1803ca1) | Nov 19, 2022 |
| MSI           | H61M-P21                    | [a91ee7dc9d](https://linux-hardware.org/?probe=a91ee7dc9d) | Nov 19, 2022 |
| ASUSTek       | PRIME B460M-K               | [19663894ff](https://linux-hardware.org/?probe=19663894ff) | Nov 18, 2022 |
| ASUSTek       | PRIME B460M-K               | [99a32a02ce](https://linux-hardware.org/?probe=99a32a02ce) | Nov 18, 2022 |
| Dell          | 0RY007                      | [d11a712f82](https://linux-hardware.org/?probe=d11a712f82) | Nov 18, 2022 |
| ASUSTek       | PRIME Z370-P                | [65abbfb38e](https://linux-hardware.org/?probe=65abbfb38e) | Nov 18, 2022 |
| Unknown       | Unknown                     | [53f563177d](https://linux-hardware.org/?probe=53f563177d) | Nov 18, 2022 |
| ASUSTek       | PRIME H510M-K               | [c695addaa3](https://linux-hardware.org/?probe=c695addaa3) | Nov 18, 2022 |
| HP            | 8906 SMVB                   | [f644eba622](https://linux-hardware.org/?probe=f644eba622) | Nov 18, 2022 |
| Gigabyte      | B550 AORUS PRO              | [ceafbe876d](https://linux-hardware.org/?probe=ceafbe876d) | Nov 18, 2022 |
| Gigabyte      | B550 AORUS PRO              | [f6f8ae996d](https://linux-hardware.org/?probe=f6f8ae996d) | Nov 18, 2022 |
| Dell          | 0Y5DDC A00                  | [99aed6e6d2](https://linux-hardware.org/?probe=99aed6e6d2) | Nov 17, 2022 |
| Intel         | H81                         | [f99a623867](https://linux-hardware.org/?probe=f99a623867) | Nov 17, 2022 |
| Gigabyte      | A520M H                     | [d353571eef](https://linux-hardware.org/?probe=d353571eef) | Nov 17, 2022 |
| Intel         | H81                         | [5bfd56a1f8](https://linux-hardware.org/?probe=5bfd56a1f8) | Nov 17, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [814b71a20c](https://linux-hardware.org/?probe=814b71a20c) | Nov 17, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [f9da339cc7](https://linux-hardware.org/?probe=f9da339cc7) | Nov 17, 2022 |
| ASUSTek       | Z170-P                      | [735035876a](https://linux-hardware.org/?probe=735035876a) | Nov 17, 2022 |
| MSI           | H61M-P32/W8                 | [82cba9e87c](https://linux-hardware.org/?probe=82cba9e87c) | Nov 16, 2022 |
| ASUSTek       | B75M-A                      | [087a904af2](https://linux-hardware.org/?probe=087a904af2) | Nov 16, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ccf8236d38](https://linux-hardware.org/?probe=ccf8236d38) | Nov 16, 2022 |
| ASUSTek       | Z87-K                       | [39078e426c](https://linux-hardware.org/?probe=39078e426c) | Nov 16, 2022 |
| Gigabyte      | H110M-S2V-CF                | [74cdb80f42](https://linux-hardware.org/?probe=74cdb80f42) | Nov 16, 2022 |
| ASRock        | N68C-GS FX                  | [e7d93e8540](https://linux-hardware.org/?probe=e7d93e8540) | Nov 15, 2022 |
| ASRock        | N68C-GS FX                  | [c67fea651e](https://linux-hardware.org/?probe=c67fea651e) | Nov 15, 2022 |
| ASRock        | N68-GS4 FX                  | [c651e62593](https://linux-hardware.org/?probe=c651e62593) | Nov 15, 2022 |
| Unknown       | Intel X79                   | [61483ea15b](https://linux-hardware.org/?probe=61483ea15b) | Nov 14, 2022 |
| ASUSTek       | PRIME H510M-K               | [191fa275ad](https://linux-hardware.org/?probe=191fa275ad) | Nov 14, 2022 |
| ASUSTek       | PRIME H510M-K               | [0f8a90fef7](https://linux-hardware.org/?probe=0f8a90fef7) | Nov 14, 2022 |
| Intel         | H81                         | [738056c2ab](https://linux-hardware.org/?probe=738056c2ab) | Nov 14, 2022 |
| MSI           | MS-7360                     | [4899c85a97](https://linux-hardware.org/?probe=4899c85a97) | Nov 14, 2022 |
| Pegatron      | 2A94h                       | [5ebd2a4bf4](https://linux-hardware.org/?probe=5ebd2a4bf4) | Nov 13, 2022 |
| Gigabyte      | H110M-M2-CF                 | [aedb84820e](https://linux-hardware.org/?probe=aedb84820e) | Nov 13, 2022 |
| ASUSTek       | F2A85-V PRO                 | [0127d7b1cd](https://linux-hardware.org/?probe=0127d7b1cd) | Nov 12, 2022 |
| MSI           | A320M-A PRO                 | [6b77cc7062](https://linux-hardware.org/?probe=6b77cc7062) | Nov 12, 2022 |
| Foxconn       | H77M/H77M-S                 | [bebf7f53f8](https://linux-hardware.org/?probe=bebf7f53f8) | Nov 12, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [c8538a21be](https://linux-hardware.org/?probe=c8538a21be) | Nov 12, 2022 |
| ASUSTek       | P5K-VM                      | [8d1ad25443](https://linux-hardware.org/?probe=8d1ad25443) | Nov 12, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [7fe6789365](https://linux-hardware.org/?probe=7fe6789365) | Nov 12, 2022 |
| MSI           | Z97-G43                     | [f5946a94b0](https://linux-hardware.org/?probe=f5946a94b0) | Nov 12, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [a8d2d850a5](https://linux-hardware.org/?probe=a8d2d850a5) | Nov 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [0d1333128b](https://linux-hardware.org/?probe=0d1333128b) | Nov 11, 2022 |
| ASUSTek       | M4A88T-M                    | [ff49e5ddb5](https://linux-hardware.org/?probe=ff49e5ddb5) | Nov 11, 2022 |
| Sapphire      | IPC-E350M1                  | [58a5544fb4](https://linux-hardware.org/?probe=58a5544fb4) | Nov 11, 2022 |
| Gigabyte      | A320M-H-CF                  | [af490e0878](https://linux-hardware.org/?probe=af490e0878) | Nov 11, 2022 |
| ASUSTek       | M4A88T-M                    | [b152665a17](https://linux-hardware.org/?probe=b152665a17) | Nov 11, 2022 |
| ASUSTek       | H81M-PLUS                   | [12d6552ded](https://linux-hardware.org/?probe=12d6552ded) | Nov 11, 2022 |
| ASRock        | B550M-HDV                   | [277c219cef](https://linux-hardware.org/?probe=277c219cef) | Nov 11, 2022 |
| Biostar       | N68S3+                      | [a37667f835](https://linux-hardware.org/?probe=a37667f835) | Nov 11, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [a37ca89eae](https://linux-hardware.org/?probe=a37ca89eae) | Nov 11, 2022 |
| MSI           | B150 GAMING M3              | [13f42af580](https://linux-hardware.org/?probe=13f42af580) | Nov 11, 2022 |
| MSI           | B450M GAMING PLUS           | [dd56553c17](https://linux-hardware.org/?probe=dd56553c17) | Nov 11, 2022 |
| Unknown       | NF-CK804                    | [6bda1f2345](https://linux-hardware.org/?probe=6bda1f2345) | Nov 10, 2022 |
| ASRock        | H410M-HDV                   | [985b9b55e2](https://linux-hardware.org/?probe=985b9b55e2) | Nov 10, 2022 |
| Acer          | H11H4-AI V:1.0              | [0873e8bf70](https://linux-hardware.org/?probe=0873e8bf70) | Nov 10, 2022 |
| ASUSTek       | H110M-K                     | [4d6af313f5](https://linux-hardware.org/?probe=4d6af313f5) | Nov 10, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | [b5ce55106f](https://linux-hardware.org/?probe=b5ce55106f) | Nov 10, 2022 |
| Gigabyte      | A320M-H-CF                  | [4cf7d8ea41](https://linux-hardware.org/?probe=4cf7d8ea41) | Nov 10, 2022 |
| Intel         | X79                         | [f806dcc4da](https://linux-hardware.org/?probe=f806dcc4da) | Nov 10, 2022 |
| Pegatron      | 2A73h                       | [dc035c362e](https://linux-hardware.org/?probe=dc035c362e) | Nov 10, 2022 |
| ASUSTek       | P8Z77-V LK                  | [640d78b1e4](https://linux-hardware.org/?probe=640d78b1e4) | Nov 10, 2022 |
| ASUSTek       | M4N68T-M-LE-V2              | [d9d004077a](https://linux-hardware.org/?probe=d9d004077a) | Nov 10, 2022 |
| Gigabyte      | A520M H                     | [50b86d41a2](https://linux-hardware.org/?probe=50b86d41a2) | Nov 09, 2022 |
| MSI           | Z370 TOMAHAWK               | [0763a922c8](https://linux-hardware.org/?probe=0763a922c8) | Nov 09, 2022 |
| ASUSTek       | P5KPL-SE                    | [dafce5f727](https://linux-hardware.org/?probe=dafce5f727) | Nov 09, 2022 |
| ASRock        | H97 Pro4                    | [bdd79e7a9e](https://linux-hardware.org/?probe=bdd79e7a9e) | Nov 09, 2022 |
| Gigabyte      | 990XA-UD3                   | [c92f8d8b22](https://linux-hardware.org/?probe=c92f8d8b22) | Nov 09, 2022 |
| MSI           | X370 GAMING PLUS            | [ae91098674](https://linux-hardware.org/?probe=ae91098674) | Nov 08, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [c8383aa811](https://linux-hardware.org/?probe=c8383aa811) | Nov 08, 2022 |
| Gigabyte      | GA-A75M-UD2H                | [7f6cff35d7](https://linux-hardware.org/?probe=7f6cff35d7) | Nov 08, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [558d46bf81](https://linux-hardware.org/?probe=558d46bf81) | Nov 08, 2022 |
| Gigabyte      | A320M-H-CF                  | [137958160c](https://linux-hardware.org/?probe=137958160c) | Nov 08, 2022 |
| Unknown       | Unknown                     | [37226d7d92](https://linux-hardware.org/?probe=37226d7d92) | Nov 07, 2022 |
| MSI           | X370 GAMING PLUS            | [cda3bef0bc](https://linux-hardware.org/?probe=cda3bef0bc) | Nov 07, 2022 |
| Fujitsu       | D3061-B1 S26361-D3061-B1    | [731ce5b944](https://linux-hardware.org/?probe=731ce5b944) | Nov 07, 2022 |
| ASRock        | D1800M                      | [4935d67430](https://linux-hardware.org/?probe=4935d67430) | Nov 07, 2022 |
| ASUSTek       | P5KPL-AM EPU                | [dd30cc2e63](https://linux-hardware.org/?probe=dd30cc2e63) | Nov 07, 2022 |
| ASRock        | N68C-GS FX                  | [c7b8fac7e2](https://linux-hardware.org/?probe=c7b8fac7e2) | Nov 07, 2022 |
| Gigabyte      | A320M-H-CF                  | [16b37f0b80](https://linux-hardware.org/?probe=16b37f0b80) | Nov 07, 2022 |
| ASUSTek       | F2A55-M LK                  | [0c888d2b1f](https://linux-hardware.org/?probe=0c888d2b1f) | Nov 07, 2022 |
| MSI           | B450M MORTAR MAX            | [eae2553adf](https://linux-hardware.org/?probe=eae2553adf) | Nov 06, 2022 |
| MSI           | H81M-P33                    | [00cb3af126](https://linux-hardware.org/?probe=00cb3af126) | Nov 06, 2022 |
| ASUSTek       | P8B75-M LE                  | [65ac5d12c7](https://linux-hardware.org/?probe=65ac5d12c7) | Nov 06, 2022 |
| ASRock        | H370M-ITX/ac                | [fe29240874](https://linux-hardware.org/?probe=fe29240874) | Nov 06, 2022 |
| Acer          | EG31M R01-C2                | [1c541d28e0](https://linux-hardware.org/?probe=1c541d28e0) | Nov 06, 2022 |
| ASUSTek       | P8B75-M LE                  | [3ffeb18e56](https://linux-hardware.org/?probe=3ffeb18e56) | Nov 06, 2022 |
| ASUSTek       | PRIME H270-PRO              | [a60e7d1961](https://linux-hardware.org/?probe=a60e7d1961) | Nov 06, 2022 |
| MSI           | B150 GAMING M3              | [38a85b01ad](https://linux-hardware.org/?probe=38a85b01ad) | Nov 06, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [b6a4d355bc](https://linux-hardware.org/?probe=b6a4d355bc) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [ba495c1631](https://linux-hardware.org/?probe=ba495c1631) | Nov 06, 2022 |
| Gigabyte      | F2A55M-DS2                  | [4cadf85e6e](https://linux-hardware.org/?probe=4cadf85e6e) | Nov 06, 2022 |
| ASUSTek       | Z97-C                       | [ce7c45a3d9](https://linux-hardware.org/?probe=ce7c45a3d9) | Nov 06, 2022 |
| Biostar       | A78LR-M3S                   | [8e8da94ddb](https://linux-hardware.org/?probe=8e8da94ddb) | Nov 06, 2022 |
| Gigabyte      | B365M D3H-CF                | [53d09fc292](https://linux-hardware.org/?probe=53d09fc292) | Nov 05, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [5d6951212b](https://linux-hardware.org/?probe=5d6951212b) | Nov 05, 2022 |
| ASUSTek       | PRIME H510M-R               | [922e24a1a0](https://linux-hardware.org/?probe=922e24a1a0) | Nov 05, 2022 |
| Gigabyte      | H110M-M2-CF                 | [40ef04163d](https://linux-hardware.org/?probe=40ef04163d) | Nov 05, 2022 |
| ASUSTek       | M5A78L-M LX                 | [d7512f31a3](https://linux-hardware.org/?probe=d7512f31a3) | Nov 05, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [a8926fce15](https://linux-hardware.org/?probe=a8926fce15) | Nov 05, 2022 |
| MSI           | P67A-C43                    | [a5e86512d1](https://linux-hardware.org/?probe=a5e86512d1) | Nov 05, 2022 |
| Gigabyte      | H110M-S2HP-CF               | [94004d5828](https://linux-hardware.org/?probe=94004d5828) | Nov 05, 2022 |
| Gigabyte      | B75-D3V                     | [a562aef0c3](https://linux-hardware.org/?probe=a562aef0c3) | Nov 05, 2022 |
| ASUSTek       | M4A77TD PRO                 | [b5fa37b726](https://linux-hardware.org/?probe=b5fa37b726) | Nov 04, 2022 |
| ASUSTek       | M5A78L LE                   | [edf9105fc5](https://linux-hardware.org/?probe=edf9105fc5) | Nov 04, 2022 |
| Gigabyte      | Z87-HD3                     | [f67d642096](https://linux-hardware.org/?probe=f67d642096) | Nov 04, 2022 |
| MSI           | B360M PRO-VDH               | [2a801a9792](https://linux-hardware.org/?probe=2a801a9792) | Nov 04, 2022 |
| ASRock        | B85M Pro4                   | [55da31d807](https://linux-hardware.org/?probe=55da31d807) | Nov 04, 2022 |
| ASUSTek       | P5K                         | [ebc4a23dcc](https://linux-hardware.org/?probe=ebc4a23dcc) | Nov 04, 2022 |
| MSI           | X370 GAMING PLUS            | [db81c87a42](https://linux-hardware.org/?probe=db81c87a42) | Nov 04, 2022 |
| Huanan        | X99-BD4 V1.3                | [3eccdb8ba1](https://linux-hardware.org/?probe=3eccdb8ba1) | Nov 03, 2022 |
| Gigabyte      | Z87-HD3                     | [ef71fa8dd6](https://linux-hardware.org/?probe=ef71fa8dd6) | Nov 03, 2022 |
| Gigabyte      | Z490 UD                     | [c560dfaab4](https://linux-hardware.org/?probe=c560dfaab4) | Nov 03, 2022 |
| ASUSTek       | P8H77-V LE                  | [d5c39748e3](https://linux-hardware.org/?probe=d5c39748e3) | Nov 03, 2022 |
| MSI           | X370 GAMING PLUS            | [749d91dfd4](https://linux-hardware.org/?probe=749d91dfd4) | Nov 03, 2022 |
| Gigabyte      | Z490 UD                     | [eb3812d5ce](https://linux-hardware.org/?probe=eb3812d5ce) | Nov 03, 2022 |
| ECS           | MCP61M-M3                   | [fe5e87a9ef](https://linux-hardware.org/?probe=fe5e87a9ef) | Nov 03, 2022 |
| ASUSTek       | Z97-C                       | [be4968a790](https://linux-hardware.org/?probe=be4968a790) | Nov 03, 2022 |
| ASRock        | A320D4-P1                   | [8e453f4158](https://linux-hardware.org/?probe=8e453f4158) | Nov 03, 2022 |
| Gigabyte      | Z390 UD                     | [c54743b7e8](https://linux-hardware.org/?probe=c54743b7e8) | Nov 02, 2022 |
| ASRock        | N68-GS4 FX                  | [da7a70afe1](https://linux-hardware.org/?probe=da7a70afe1) | Nov 02, 2022 |
| Gigabyte      | Z390 UD                     | [24a3f977bf](https://linux-hardware.org/?probe=24a3f977bf) | Nov 02, 2022 |
| MSI           | MS-7392                     | [d453f89064](https://linux-hardware.org/?probe=d453f89064) | Nov 02, 2022 |
| Gigabyte      | H77N-WIFI                   | [d8b066edcd](https://linux-hardware.org/?probe=d8b066edcd) | Nov 02, 2022 |
| Lenovo        | H420                        | [3e3f04d875](https://linux-hardware.org/?probe=3e3f04d875) | Nov 02, 2022 |
| Gigabyte      | EP45-DS4                    | [fa96a26c5a](https://linux-hardware.org/?probe=fa96a26c5a) | Nov 02, 2022 |
| ECS           | H61H2-M2                    | [b70c0aa20d](https://linux-hardware.org/?probe=b70c0aa20d) | Nov 01, 2022 |
| Gigabyte      | EP45-DS4                    | [2eb78b1c3d](https://linux-hardware.org/?probe=2eb78b1c3d) | Nov 01, 2022 |
| ASUSTek       | PRIME H310M-K               | [9efd2724b2](https://linux-hardware.org/?probe=9efd2724b2) | Nov 01, 2022 |
| ASRock        | B365M-HDV                   | [29a6bce4c0](https://linux-hardware.org/?probe=29a6bce4c0) | Nov 01, 2022 |
| ASUSTek       | H81M-C                      | [76052b7756](https://linux-hardware.org/?probe=76052b7756) | Nov 01, 2022 |
| MSI           | H61M-P32/W8                 | [14df9c3c14](https://linux-hardware.org/?probe=14df9c3c14) | Nov 01, 2022 |
| ASRock        | N68C-GS FX                  | [f7a9c5f382](https://linux-hardware.org/?probe=f7a9c5f382) | Nov 01, 2022 |
| MSI           | H81M-P33                    | [29e4a4ec52](https://linux-hardware.org/?probe=29e4a4ec52) | Oct 31, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [96d61ed3e1](https://linux-hardware.org/?probe=96d61ed3e1) | Oct 31, 2022 |
| MSI           | B450-A PRO MAX              | [8e480ded02](https://linux-hardware.org/?probe=8e480ded02) | Oct 31, 2022 |
| Gigabyte      | X99-SLI-CF                  | [d6bc77d638](https://linux-hardware.org/?probe=d6bc77d638) | Oct 31, 2022 |
| ASUSTek       | H81M-C                      | [2fdcf19b6d](https://linux-hardware.org/?probe=2fdcf19b6d) | Oct 31, 2022 |
| Foxconn       | RS690M2MA 0A                | [29605bcad9](https://linux-hardware.org/?probe=29605bcad9) | Oct 31, 2022 |
| Gigabyte      | B660M GAMING X AX           | [d48fe55211](https://linux-hardware.org/?probe=d48fe55211) | Oct 31, 2022 |
| ASRock        | H470M-HDV                   | [a4e522270c](https://linux-hardware.org/?probe=a4e522270c) | Oct 31, 2022 |
| Biostar       | H310MHC2                    | [5ad5ba772f](https://linux-hardware.org/?probe=5ad5ba772f) | Oct 31, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [5e87d391a3](https://linux-hardware.org/?probe=5e87d391a3) | Oct 31, 2022 |
| Intel         | D946GZAB AAD66610-300       | [33c41323a3](https://linux-hardware.org/?probe=33c41323a3) | Oct 31, 2022 |
| ASUSTek       | M5A78L/USB3                 | [b5098e9fe5](https://linux-hardware.org/?probe=b5098e9fe5) | Oct 31, 2022 |
| ASRock        | N68C-GS FX                  | [e24bf2e31f](https://linux-hardware.org/?probe=e24bf2e31f) | Oct 31, 2022 |
| Gigabyte      | H77N-WIFI                   | [d4340d8d66](https://linux-hardware.org/?probe=d4340d8d66) | Oct 31, 2022 |
| ASUSTek       | Leonite2                    | [955ce84cf2](https://linux-hardware.org/?probe=955ce84cf2) | Oct 30, 2022 |
| ASRock        | N68C-GS FX                  | [bf96e5a0a1](https://linux-hardware.org/?probe=bf96e5a0a1) | Oct 30, 2022 |
| ASRock        | H410M-HVS                   | [2d540e06b9](https://linux-hardware.org/?probe=2d540e06b9) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | [6bbea41ce5](https://linux-hardware.org/?probe=6bbea41ce5) | Oct 30, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [b132f4c4e9](https://linux-hardware.org/?probe=b132f4c4e9) | Oct 30, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [7e1df59daa](https://linux-hardware.org/?probe=7e1df59daa) | Oct 30, 2022 |
| Gigabyte      | G41M-Combo                  | [180622c3be](https://linux-hardware.org/?probe=180622c3be) | Oct 30, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | [7f78f3451e](https://linux-hardware.org/?probe=7f78f3451e) | Oct 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | [47b5907eec](https://linux-hardware.org/?probe=47b5907eec) | Oct 29, 2022 |
| ASUSTek       | P5Q SE2                     | [7d576ac245](https://linux-hardware.org/?probe=7d576ac245) | Oct 29, 2022 |
| MSI           | B450M MORTAR MAX            | [d8321f617e](https://linux-hardware.org/?probe=d8321f617e) | Oct 29, 2022 |
| MSI           | B450M MORTAR MAX            | [7f67023fa9](https://linux-hardware.org/?probe=7f67023fa9) | Oct 29, 2022 |
| Gigabyte      | GA-790XTA-UD4               | [a750edc641](https://linux-hardware.org/?probe=a750edc641) | Oct 29, 2022 |
| ASRock        | H410M-HVS                   | [9371d71f6d](https://linux-hardware.org/?probe=9371d71f6d) | Oct 29, 2022 |
| Foxconn       | 2ACA                        | [69544f77d0](https://linux-hardware.org/?probe=69544f77d0) | Oct 29, 2022 |
| Gigabyte      | H110M-M2-CF                 | [34c4f594c4](https://linux-hardware.org/?probe=34c4f594c4) | Oct 29, 2022 |
| Dell          | 0Y5DDC A00                  | [e3421b1908](https://linux-hardware.org/?probe=e3421b1908) | Oct 29, 2022 |
| ASRock        | N68-GS4 FX                  | [04334f2930](https://linux-hardware.org/?probe=04334f2930) | Oct 29, 2022 |
| Gigabyte      | B550 GAMING X V2            | [7b3b808198](https://linux-hardware.org/?probe=7b3b808198) | Oct 29, 2022 |
| Gigabyte      | B550 GAMING X V2            | [5405caf9dc](https://linux-hardware.org/?probe=5405caf9dc) | Oct 28, 2022 |
| MSI           | MAG B560 TOMAHAWK WIFI      | [429fd34d64](https://linux-hardware.org/?probe=429fd34d64) | Oct 28, 2022 |
| ASUSTek       | H81M-C                      | [c96189c44c](https://linux-hardware.org/?probe=c96189c44c) | Oct 28, 2022 |
| Gigabyte      | PH67-UD3-B3                 | [c66fb514ab](https://linux-hardware.org/?probe=c66fb514ab) | Oct 28, 2022 |
| Gigabyte      | A320M-S2H-CF                | [594b16e254](https://linux-hardware.org/?probe=594b16e254) | Oct 28, 2022 |
| Gigabyte      | F2A88X-D3H                  | [dc1e16bba1](https://linux-hardware.org/?probe=dc1e16bba1) | Oct 27, 2022 |
| ASUSTek       | M5A97 PRO                   | [de99c600e5](https://linux-hardware.org/?probe=de99c600e5) | Oct 27, 2022 |
| Gigabyte      | H110M-S2V-CF                | [1d4dfc3e06](https://linux-hardware.org/?probe=1d4dfc3e06) | Oct 27, 2022 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [6de2b1229f](https://linux-hardware.org/?probe=6de2b1229f) | Oct 27, 2022 |
| MSI           | H81M-P33                    | [e4f38c5519](https://linux-hardware.org/?probe=e4f38c5519) | Oct 26, 2022 |
| HP            | 8717                        | [c2fcc7119a](https://linux-hardware.org/?probe=c2fcc7119a) | Oct 26, 2022 |
| ASRock        | 970 Pro3 R2.0               | [c2b4882963](https://linux-hardware.org/?probe=c2b4882963) | Oct 26, 2022 |
| MiTAC         | E220 E220AQ-601             | [1ee0c036f8](https://linux-hardware.org/?probe=1ee0c036f8) | Oct 26, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [926be6d85b](https://linux-hardware.org/?probe=926be6d85b) | Oct 25, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [94a393835b](https://linux-hardware.org/?probe=94a393835b) | Oct 25, 2022 |
| MSI           | B450M-A PRO MAX             | [9f404fe6b4](https://linux-hardware.org/?probe=9f404fe6b4) | Oct 25, 2022 |
| Dell          | 0Y5DDC A00                  | [bc39e0cfd6](https://linux-hardware.org/?probe=bc39e0cfd6) | Oct 25, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [b8b23daad5](https://linux-hardware.org/?probe=b8b23daad5) | Oct 25, 2022 |
| Gigabyte      | H410M H V3                  | [b4c5ed92b7](https://linux-hardware.org/?probe=b4c5ed92b7) | Oct 24, 2022 |
| MSI           | B450M GAMING PLUS           | [e3041ae2eb](https://linux-hardware.org/?probe=e3041ae2eb) | Oct 24, 2022 |
| Gigabyte      | B450 AORUS M                | [08c2a2abf9](https://linux-hardware.org/?probe=08c2a2abf9) | Oct 24, 2022 |
| Gigabyte      | X58A-UD7                    | [8b0cff9259](https://linux-hardware.org/?probe=8b0cff9259) | Oct 24, 2022 |
| ASUSTek       | P8H77-V                     | [fdb1bce84a](https://linux-hardware.org/?probe=fdb1bce84a) | Oct 24, 2022 |
| ECS           | H310CH5-M2                  | [e9d2a5becb](https://linux-hardware.org/?probe=e9d2a5becb) | Oct 24, 2022 |
| Gigabyte      | B450M DS3H V2               | [a159a5720e](https://linux-hardware.org/?probe=a159a5720e) | Oct 23, 2022 |
| ASUSTek       | M4A77T/USB3                 | [2df43ccc5d](https://linux-hardware.org/?probe=2df43ccc5d) | Oct 22, 2022 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | [6105b0d3a9](https://linux-hardware.org/?probe=6105b0d3a9) | Oct 22, 2022 |
| Unknown       | NF-CK804                    | [4df3f7c7e6](https://linux-hardware.org/?probe=4df3f7c7e6) | Oct 22, 2022 |
| MSI           | A320M GRENADE               | [30bcc61268](https://linux-hardware.org/?probe=30bcc61268) | Oct 21, 2022 |
| Gigabyte      | H81M-S1                     | [8168ea4028](https://linux-hardware.org/?probe=8168ea4028) | Oct 21, 2022 |
| Dell          | 0GM819                      | [e2ebe8bae1](https://linux-hardware.org/?probe=e2ebe8bae1) | Oct 21, 2022 |
| ASRock        | N68-S                       | [3cfa7cd9f8](https://linux-hardware.org/?probe=3cfa7cd9f8) | Oct 21, 2022 |
| Gigabyte      | H310M H x.x                 | [a0a8fc6cb0](https://linux-hardware.org/?probe=a0a8fc6cb0) | Oct 21, 2022 |
| MSI           | A320M GRENADE               | [73112f41f7](https://linux-hardware.org/?probe=73112f41f7) | Oct 21, 2022 |
| ASUSTek       | B85-PLUS                    | [a057e410d0](https://linux-hardware.org/?probe=a057e410d0) | Oct 21, 2022 |
| ASUSTek       | B85-PLUS                    | [72c61d8c50](https://linux-hardware.org/?probe=72c61d8c50) | Oct 21, 2022 |
| ASRock        | H81M-HDS R2.0               | [6161a12f13](https://linux-hardware.org/?probe=6161a12f13) | Oct 20, 2022 |
| ASUSTek       | P5Q SE                      | [c223e518c9](https://linux-hardware.org/?probe=c223e518c9) | Oct 20, 2022 |
| ASUSTek       | PRIME B360M-A               | [444b923209](https://linux-hardware.org/?probe=444b923209) | Oct 20, 2022 |
| Gigabyte      | EP41-UD3L                   | [d82763649b](https://linux-hardware.org/?probe=d82763649b) | Oct 20, 2022 |
| Gigabyte      | H77N-WIFI                   | [fffc0ab985](https://linux-hardware.org/?probe=fffc0ab985) | Oct 20, 2022 |
| ASRock        | H81M-HDS R2.0               | [b27f916880](https://linux-hardware.org/?probe=b27f916880) | Oct 19, 2022 |
| Acer          | FMCP7A-ION                  | [e7646c8fe4](https://linux-hardware.org/?probe=e7646c8fe4) | Oct 19, 2022 |
| Gigabyte      | EP41-UD3L                   | [31867fb669](https://linux-hardware.org/?probe=31867fb669) | Oct 19, 2022 |
| ECS           | H61H2-M12                   | [7c4ae7b4ab](https://linux-hardware.org/?probe=7c4ae7b4ab) | Oct 19, 2022 |
| ASUSTek       | Leonite2                    | [717cc412e5](https://linux-hardware.org/?probe=717cc412e5) | Oct 19, 2022 |
| MSI           | PRO H410M-B                 | [549eeb915c](https://linux-hardware.org/?probe=549eeb915c) | Oct 19, 2022 |
| ASUSTek       | H81M-K                      | [a4a1d563b5](https://linux-hardware.org/?probe=a4a1d563b5) | Oct 19, 2022 |
| ASRock        | H61M-GE                     | [6149e0c478](https://linux-hardware.org/?probe=6149e0c478) | Oct 18, 2022 |
| Intel         | X99                         | [4217ddeb6b](https://linux-hardware.org/?probe=4217ddeb6b) | Oct 18, 2022 |
| MSI           | Z490-A PRO                  | [db93de2ab4](https://linux-hardware.org/?probe=db93de2ab4) | Oct 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [3b1ce3ab08](https://linux-hardware.org/?probe=3b1ce3ab08) | Oct 18, 2022 |
| MSI           | B360M GAMING PLUS           | [df2e89c571](https://linux-hardware.org/?probe=df2e89c571) | Oct 18, 2022 |
| Gigabyte      | H77N-WIFI                   | [1e8b0c8279](https://linux-hardware.org/?probe=1e8b0c8279) | Oct 18, 2022 |
| Biostar       | A320MD PRO                  | [0497b12091](https://linux-hardware.org/?probe=0497b12091) | Oct 18, 2022 |
| ASRock        | H310CM-HDV/M.2              | [f2112b8b74](https://linux-hardware.org/?probe=f2112b8b74) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [5335a66143](https://linux-hardware.org/?probe=5335a66143) | Oct 17, 2022 |
| ASRock        | H61M-GE                     | [873932f557](https://linux-hardware.org/?probe=873932f557) | Oct 17, 2022 |
| ASUSTek       | M5A97 R2.0                  | [b85a76dd7f](https://linux-hardware.org/?probe=b85a76dd7f) | Oct 17, 2022 |
| Biostar       | H61MLV                      | [c2fb8ebaac](https://linux-hardware.org/?probe=c2fb8ebaac) | Oct 17, 2022 |
| Dell          | 0HY553                      | [08f05b94e6](https://linux-hardware.org/?probe=08f05b94e6) | Oct 17, 2022 |
| HP            | 81B3                        | [e303e50785](https://linux-hardware.org/?probe=e303e50785) | Oct 16, 2022 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | [62cacee577](https://linux-hardware.org/?probe=62cacee577) | Oct 16, 2022 |
| Gigabyte      | B75M-D2V                    | [20ac585859](https://linux-hardware.org/?probe=20ac585859) | Oct 16, 2022 |
| ASUSTek       | P8H61-M LE                  | [cf76898812](https://linux-hardware.org/?probe=cf76898812) | Oct 16, 2022 |
| ECS           | G41T-M7                     | [3abe70653e](https://linux-hardware.org/?probe=3abe70653e) | Oct 16, 2022 |
| Gigabyte      | GA-770TA-UD3                | [82f436a99c](https://linux-hardware.org/?probe=82f436a99c) | Oct 16, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [59a0225889](https://linux-hardware.org/?probe=59a0225889) | Oct 16, 2022 |
| ASRock        | A55 Pro3                    | [0b3e7a1cd2](https://linux-hardware.org/?probe=0b3e7a1cd2) | Oct 16, 2022 |
| ASUSTek       | PRIME B450M-K               | [288b9fadfe](https://linux-hardware.org/?probe=288b9fadfe) | Oct 15, 2022 |
| Gigabyte      | B250M-D3H-CF                | [c351e0fae6](https://linux-hardware.org/?probe=c351e0fae6) | Oct 15, 2022 |
| ASUSTek       | P7H55-M/USB3                | [8a98e44bee](https://linux-hardware.org/?probe=8a98e44bee) | Oct 15, 2022 |
| ASRock        | B460 Steel Legend           | [ca98840e23](https://linux-hardware.org/?probe=ca98840e23) | Oct 14, 2022 |
| MSI           | B85M-P33                    | [83d476e3d7](https://linux-hardware.org/?probe=83d476e3d7) | Oct 14, 2022 |
| Gigabyte      | H77N-WIFI                   | [d1f08d0589](https://linux-hardware.org/?probe=d1f08d0589) | Oct 14, 2022 |
| ASUSTek       | P8H77-V                     | [9c98c411c5](https://linux-hardware.org/?probe=9c98c411c5) | Oct 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [da04425205](https://linux-hardware.org/?probe=da04425205) | Oct 14, 2022 |
| ASRock        | G41M-VS3                    | [7fa0f82664](https://linux-hardware.org/?probe=7fa0f82664) | Oct 13, 2022 |
| Gigabyte      | H77N-WIFI                   | [6597eea759](https://linux-hardware.org/?probe=6597eea759) | Oct 13, 2022 |
| Founder       | H61H2-AM V1.1               | [4d558904f5](https://linux-hardware.org/?probe=4d558904f5) | Oct 13, 2022 |
| Lenovo        | ThinkCentre M71z 1782RP4    | [bee14a3740](https://linux-hardware.org/?probe=bee14a3740) | Oct 13, 2022 |
| ASUSTek       | P8B75-M                     | [98ea718793](https://linux-hardware.org/?probe=98ea718793) | Oct 12, 2022 |
| ASUSTek       | P8H61-M LX3                 | [be3020e232](https://linux-hardware.org/?probe=be3020e232) | Oct 12, 2022 |
| ASUSTek       | PRIME B560M-A               | [15cc45253b](https://linux-hardware.org/?probe=15cc45253b) | Oct 11, 2022 |
| ASRock        | D1800B-ITX                  | [a44ef4b82f](https://linux-hardware.org/?probe=a44ef4b82f) | Oct 11, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [8ec5da3fb1](https://linux-hardware.org/?probe=8ec5da3fb1) | Oct 10, 2022 |
| ASRock        | D1800B-ITX                  | [7b33424235](https://linux-hardware.org/?probe=7b33424235) | Oct 10, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [899c4a1231](https://linux-hardware.org/?probe=899c4a1231) | Oct 10, 2022 |
| MSI           | MS-7430 0A                  | [ac3040f9c3](https://linux-hardware.org/?probe=ac3040f9c3) | Oct 10, 2022 |
| ASUSTek       | H61M-K                      | [f6d2b67f4a](https://linux-hardware.org/?probe=f6d2b67f4a) | Oct 10, 2022 |
| MSI           | B450M-A PRO MAX             | [cac41cb816](https://linux-hardware.org/?probe=cac41cb816) | Oct 10, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [b4dd4f4043](https://linux-hardware.org/?probe=b4dd4f4043) | Oct 09, 2022 |
| ASUSTek       | M4A78T-E                    | [0d574bf35b](https://linux-hardware.org/?probe=0d574bf35b) | Oct 09, 2022 |
| Gigabyte      | B560M AORUS ELITE           | [81e6a3e257](https://linux-hardware.org/?probe=81e6a3e257) | Oct 09, 2022 |
| ASUSTek       | P5QL PRO                    | [93af7ecaf6](https://linux-hardware.org/?probe=93af7ecaf6) | Oct 09, 2022 |
| Gigabyte      | B550M DS3H                  | [1f344c3f2f](https://linux-hardware.org/?probe=1f344c3f2f) | Oct 09, 2022 |
| Pegatron      | 2A73h                       | [a5b4cd2cda](https://linux-hardware.org/?probe=a5b4cd2cda) | Oct 09, 2022 |
| Huanan        | H97-ZD3 V2.0                | [c6106f322e](https://linux-hardware.org/?probe=c6106f322e) | Oct 09, 2022 |
| ECS           | BSWI-D2                     | [97c824abf6](https://linux-hardware.org/?probe=97c824abf6) | Oct 09, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [0f690e6e12](https://linux-hardware.org/?probe=0f690e6e12) | Oct 08, 2022 |
| ECS           | BSWI-D2                     | [d717be733f](https://linux-hardware.org/?probe=d717be733f) | Oct 08, 2022 |
| Gigabyte      | H81M-H                      | [7f78dda318](https://linux-hardware.org/?probe=7f78dda318) | Oct 07, 2022 |
| Colorful T... | B85M-G PRO V21              | [b41a5ff649](https://linux-hardware.org/?probe=b41a5ff649) | Oct 07, 2022 |
| HP            | 0A60h                       | [8d9a2bf124](https://linux-hardware.org/?probe=8d9a2bf124) | Oct 07, 2022 |
| Gigabyte      | P35-S3                      | [bfd38fc1aa](https://linux-hardware.org/?probe=bfd38fc1aa) | Oct 07, 2022 |
| Gigabyte      | P35-S3                      | [45acd19412](https://linux-hardware.org/?probe=45acd19412) | Oct 07, 2022 |
| eMachines     | ER1401                      | [ee4504d60f](https://linux-hardware.org/?probe=ee4504d60f) | Oct 07, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [ec9fd4936c](https://linux-hardware.org/?probe=ec9fd4936c) | Oct 07, 2022 |
| Kllisre       | X79 V1.2                    | [30966c572c](https://linux-hardware.org/?probe=30966c572c) | Oct 06, 2022 |
| Gigabyte      | H410M S2 V2                 | [ab20fa33ac](https://linux-hardware.org/?probe=ab20fa33ac) | Oct 06, 2022 |
| ASUSTek       | PRIME H510M-R               | [1b770a47f7](https://linux-hardware.org/?probe=1b770a47f7) | Oct 06, 2022 |
| Biostar       | TF570 SLI A2+               | [f7cacc2b3d](https://linux-hardware.org/?probe=f7cacc2b3d) | Oct 06, 2022 |
| Gigabyte      | H110M-S2V-CF                | [a2dd3b08ba](https://linux-hardware.org/?probe=a2dd3b08ba) | Oct 06, 2022 |
| Unknown       | X79                         | [be112e773d](https://linux-hardware.org/?probe=be112e773d) | Oct 06, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [ebe4e45d60](https://linux-hardware.org/?probe=ebe4e45d60) | Oct 05, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [f92b06fc20](https://linux-hardware.org/?probe=f92b06fc20) | Oct 05, 2022 |
| ASUSTek       | P8H77-V                     | [0b3b1d97f8](https://linux-hardware.org/?probe=0b3b1d97f8) | Oct 05, 2022 |
| Gigabyte      | B450M S2H                   | [9d214ef1da](https://linux-hardware.org/?probe=9d214ef1da) | Oct 05, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [7bf87b89f8](https://linux-hardware.org/?probe=7bf87b89f8) | Oct 05, 2022 |
| Gigabyte      | H110M-S2V-CF                | [20673d8f1e](https://linux-hardware.org/?probe=20673d8f1e) | Oct 05, 2022 |
| MSI           | PRO H410M-B                 | [e85d76f196](https://linux-hardware.org/?probe=e85d76f196) | Oct 05, 2022 |
| ASRock        | D1800M                      | [f8f6e6c8f2](https://linux-hardware.org/?probe=f8f6e6c8f2) | Oct 05, 2022 |
| MSI           | B350 TOMAHAWK ARCTIC        | [afcf9c151f](https://linux-hardware.org/?probe=afcf9c151f) | Oct 05, 2022 |
| ASUSTek       | H110M-R                     | [4a6d780641](https://linux-hardware.org/?probe=4a6d780641) | Oct 05, 2022 |
| Gigabyte      | AX370-Gaming K3             | [5ae0d33f23](https://linux-hardware.org/?probe=5ae0d33f23) | Oct 05, 2022 |
| ASUSTek       | Maximus IX CODE             | [da694ad588](https://linux-hardware.org/?probe=da694ad588) | Oct 04, 2022 |
| OEM           | Unknown                     | [ab6e21774c](https://linux-hardware.org/?probe=ab6e21774c) | Oct 04, 2022 |
| ASUSTek       | P6T WS PRO                  | [fb442877c5](https://linux-hardware.org/?probe=fb442877c5) | Oct 04, 2022 |
| Sapphire      | IPC-E350M1                  | [e9a9db8e30](https://linux-hardware.org/?probe=e9a9db8e30) | Oct 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | [c8e379037f](https://linux-hardware.org/?probe=c8e379037f) | Oct 03, 2022 |
| ASUSTek       | H110M-R                     | [ad1e756112](https://linux-hardware.org/?probe=ad1e756112) | Oct 03, 2022 |
| ASUSTek       | A68HM-K                     | [80f73c9aa8](https://linux-hardware.org/?probe=80f73c9aa8) | Oct 03, 2022 |
| ASUSTek       | Leonite2                    | [45ac930d40](https://linux-hardware.org/?probe=45ac930d40) | Oct 03, 2022 |
| Gigabyte      | Z97-HD3                     | [eccf4c45f5](https://linux-hardware.org/?probe=eccf4c45f5) | Oct 03, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [13f60e066f](https://linux-hardware.org/?probe=13f60e066f) | Oct 03, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [e3eb4cd95f](https://linux-hardware.org/?probe=e3eb4cd95f) | Oct 02, 2022 |
| Gigabyte      | P67X-UD3-B3                 | [a63ce26ce2](https://linux-hardware.org/?probe=a63ce26ce2) | Oct 02, 2022 |
| Gigabyte      | EP41-UD3L                   | [30464f2c62](https://linux-hardware.org/?probe=30464f2c62) | Oct 02, 2022 |
| Gigabyte      | B460M DS3H                  | [1f51daf0c8](https://linux-hardware.org/?probe=1f51daf0c8) | Oct 02, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [77a9b37139](https://linux-hardware.org/?probe=77a9b37139) | Oct 02, 2022 |
| Gigabyte      | B450M DS3H-CF               | [00b0117f9a](https://linux-hardware.org/?probe=00b0117f9a) | Oct 02, 2022 |
| MSI           | H61M-P21                    | [f2f4c990bb](https://linux-hardware.org/?probe=f2f4c990bb) | Oct 02, 2022 |
| Gigabyte      | Z97-HD3                     | [0085eb8249](https://linux-hardware.org/?probe=0085eb8249) | Oct 02, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [ade6e8d765](https://linux-hardware.org/?probe=ade6e8d765) | Oct 02, 2022 |
| Huanan        | H97-ZD3 V2.0                | [283a2e4ee5](https://linux-hardware.org/?probe=283a2e4ee5) | Oct 02, 2022 |
| MSI           | B450M-A PRO MAX             | [649f4ec8c6](https://linux-hardware.org/?probe=649f4ec8c6) | Oct 01, 2022 |
| ASUSTek       | H81-PLUS                    | [e251d6b8f7](https://linux-hardware.org/?probe=e251d6b8f7) | Sep 30, 2022 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [8d8e54ed69](https://linux-hardware.org/?probe=8d8e54ed69) | Sep 30, 2022 |
| ASUSTek       | Maximus V GENE              | [7998f02578](https://linux-hardware.org/?probe=7998f02578) | Sep 29, 2022 |
| ASUSTek       | B85M-G                      | [a9983b2858](https://linux-hardware.org/?probe=a9983b2858) | Sep 29, 2022 |
| ASUSTek       | H81M-D                      | [a1580941c3](https://linux-hardware.org/?probe=a1580941c3) | Sep 29, 2022 |
| Biostar       | IH61MF-Q5                   | [7a63314188](https://linux-hardware.org/?probe=7a63314188) | Sep 29, 2022 |
| ASUSTek       | M4A785T-M                   | [03277d55bc](https://linux-hardware.org/?probe=03277d55bc) | Sep 28, 2022 |
| MSI           | G41M-P26                    | [45f0101515](https://linux-hardware.org/?probe=45f0101515) | Sep 28, 2022 |
| Gigabyte      | B560M H                     | [80e3cd655a](https://linux-hardware.org/?probe=80e3cd655a) | Sep 28, 2022 |
| Gigabyte      | B560M H                     | [0192951511](https://linux-hardware.org/?probe=0192951511) | Sep 28, 2022 |
| ASUSTek       | P8H61-MX R2.0               | [3def6cd1c2](https://linux-hardware.org/?probe=3def6cd1c2) | Sep 28, 2022 |
| ASUSTek       | H87-PLUS                    | [ccb24cd91e](https://linux-hardware.org/?probe=ccb24cd91e) | Sep 28, 2022 |
| ASUSTek       | P8H61-M LE                  | [0d9fdddd8a](https://linux-hardware.org/?probe=0d9fdddd8a) | Sep 27, 2022 |
| Gigabyte      | B360M HD3                   | [1107ba42b7](https://linux-hardware.org/?probe=1107ba42b7) | Sep 27, 2022 |
| Dell          | 0Y5DDC A00                  | [a135b97045](https://linux-hardware.org/?probe=a135b97045) | Sep 27, 2022 |
| Unknown       | Unknown                     | [128a8b6e2f](https://linux-hardware.org/?probe=128a8b6e2f) | Sep 27, 2022 |
| Gigabyte      | B450M S2H                   | [b5cc268970](https://linux-hardware.org/?probe=b5cc268970) | Sep 27, 2022 |
| ASUSTek       | Maximus V GENE              | [fc7a783877](https://linux-hardware.org/?probe=fc7a783877) | Sep 26, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [e9bc8b1f10](https://linux-hardware.org/?probe=e9bc8b1f10) | Sep 26, 2022 |
| Huanan        | X99-F8                      | [24c118fb0c](https://linux-hardware.org/?probe=24c118fb0c) | Sep 26, 2022 |
| Huanan        | X99 F8D V2.2                | [7663168534](https://linux-hardware.org/?probe=7663168534) | Sep 26, 2022 |
| ASUSTek       | H81M-K                      | [c449af2ab6](https://linux-hardware.org/?probe=c449af2ab6) | Sep 26, 2022 |
| Unknown       | Unknown                     | [4cff54bad3](https://linux-hardware.org/?probe=4cff54bad3) | Sep 26, 2022 |
| Gigabyte      | H81M-DS2                    | [c8f6c9dd27](https://linux-hardware.org/?probe=c8f6c9dd27) | Sep 26, 2022 |
| Unknown       | Unknown                     | [681b9501bf](https://linux-hardware.org/?probe=681b9501bf) | Sep 26, 2022 |
| MSI           | 870-C45                     | [b110878f50](https://linux-hardware.org/?probe=b110878f50) | Sep 26, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [a9c5aeb1f0](https://linux-hardware.org/?probe=a9c5aeb1f0) | Sep 25, 2022 |
| Gigabyte      | B550M DS3H                  | [4c7d9584fc](https://linux-hardware.org/?probe=4c7d9584fc) | Sep 25, 2022 |
| Gigabyte      | Z590 GAMING X               | [1adef3d977](https://linux-hardware.org/?probe=1adef3d977) | Sep 25, 2022 |
| MSI           | MS-7253                     | [d697f7b879](https://linux-hardware.org/?probe=d697f7b879) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0546e47f90](https://linux-hardware.org/?probe=0546e47f90) | Sep 25, 2022 |
| ASUSTek       | P8Z77-V LE PLUS             | [d58256a0f6](https://linux-hardware.org/?probe=d58256a0f6) | Sep 24, 2022 |
| Huanan        | X99 F8D V2.2                | [6316c089eb](https://linux-hardware.org/?probe=6316c089eb) | Sep 24, 2022 |
| ASRock        | H470M-HDV                   | [dc08f98ca5](https://linux-hardware.org/?probe=dc08f98ca5) | Sep 24, 2022 |
| ASRock        | G41M-VS3                    | [21cfcdcbdd](https://linux-hardware.org/?probe=21cfcdcbdd) | Sep 23, 2022 |
| Gigabyte      | EP45-DS3                    | [7b827acac4](https://linux-hardware.org/?probe=7b827acac4) | Sep 23, 2022 |
| Lenovo        | ThinkCentre M58 8910A8U     | [e9028d165d](https://linux-hardware.org/?probe=e9028d165d) | Sep 22, 2022 |
| Lenovo        | ThinkCentre M58 8910A8U     | [03a3a22c54](https://linux-hardware.org/?probe=03a3a22c54) | Sep 22, 2022 |
| ASUSTek       | H110M-R                     | [0d2eec569a](https://linux-hardware.org/?probe=0d2eec569a) | Sep 22, 2022 |
| Intel         | X99                         | [d751fcb309](https://linux-hardware.org/?probe=d751fcb309) | Sep 22, 2022 |
| Gigabyte      | Z370P D3-CF                 | [5513e351d9](https://linux-hardware.org/?probe=5513e351d9) | Sep 22, 2022 |
| ASUSTek       | ET2230I                     | [074ecf956a](https://linux-hardware.org/?probe=074ecf956a) | Sep 22, 2022 |
| Gigabyte      | H61M-S2PV                   | [65dc86f8d2](https://linux-hardware.org/?probe=65dc86f8d2) | Sep 21, 2022 |
| Gigabyte      | H61M-S2PV                   | [b905e8df57](https://linux-hardware.org/?probe=b905e8df57) | Sep 21, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [c03d31a1c5](https://linux-hardware.org/?probe=c03d31a1c5) | Sep 21, 2022 |
| Gigabyte      | P85-D3                      | [d0b65afb41](https://linux-hardware.org/?probe=d0b65afb41) | Sep 20, 2022 |
| ASRock        | H55M-LE                     | [d361539e5a](https://linux-hardware.org/?probe=d361539e5a) | Sep 20, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [5b22a32f45](https://linux-hardware.org/?probe=5b22a32f45) | Sep 20, 2022 |
| Gigabyte      | P85-D3                      | [97849eb715](https://linux-hardware.org/?probe=97849eb715) | Sep 20, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [8886c62f6c](https://linux-hardware.org/?probe=8886c62f6c) | Sep 20, 2022 |
| ECS           | A55F-M3                     | [4961be8414](https://linux-hardware.org/?probe=4961be8414) | Sep 20, 2022 |
| Colorful T... | C.A68M-K PLUS V16           | [805edc36d5](https://linux-hardware.org/?probe=805edc36d5) | Sep 20, 2022 |
| MSI           | H67MS-E23                   | [5093a2b5b8](https://linux-hardware.org/?probe=5093a2b5b8) | Sep 20, 2022 |
| Biostar       | G41D3C                      | [ad549ccee8](https://linux-hardware.org/?probe=ad549ccee8) | Sep 19, 2022 |
| MSI           | H67MS-E23                   | [2f819d4ed2](https://linux-hardware.org/?probe=2f819d4ed2) | Sep 19, 2022 |
| ASUSTek       | PRIME B250M-A               | [082bdbb3a9](https://linux-hardware.org/?probe=082bdbb3a9) | Sep 18, 2022 |
| ASUSTek       | A68HM-K                     | [eaccfe0b67](https://linux-hardware.org/?probe=eaccfe0b67) | Sep 18, 2022 |
| Huanan        | H97-ZD3 V2.0                | [e54a1ee16e](https://linux-hardware.org/?probe=e54a1ee16e) | Sep 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [3b06edf9e6](https://linux-hardware.org/?probe=3b06edf9e6) | Sep 18, 2022 |
| ASUSTek       | M3A78-VM                    | [1a85e8ddb9](https://linux-hardware.org/?probe=1a85e8ddb9) | Sep 17, 2022 |
| Gigabyte      | A520M H                     | [d75913fe94](https://linux-hardware.org/?probe=d75913fe94) | Sep 17, 2022 |
| Gigabyte      | 945GCMX-S2                  | [fda56f277f](https://linux-hardware.org/?probe=fda56f277f) | Sep 17, 2022 |
| Biostar       | G41D3C                      | [a5db82aa23](https://linux-hardware.org/?probe=a5db82aa23) | Sep 17, 2022 |
| Biostar       | G41D3C                      | [4fa3ad9c51](https://linux-hardware.org/?probe=4fa3ad9c51) | Sep 17, 2022 |
| Gigabyte      | M61PME-S2P                  | [128b564017](https://linux-hardware.org/?probe=128b564017) | Sep 16, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [bf7824cf20](https://linux-hardware.org/?probe=bf7824cf20) | Sep 16, 2022 |
| Gigabyte      | H77N-WIFI                   | [4c524e3336](https://linux-hardware.org/?probe=4c524e3336) | Sep 16, 2022 |
| MACHINIST     | B75 PRO V1.0                | [ef89bf1d8c](https://linux-hardware.org/?probe=ef89bf1d8c) | Sep 16, 2022 |
| ASUSTek       | B75M-A                      | [2680627549](https://linux-hardware.org/?probe=2680627549) | Sep 16, 2022 |
| Gigabyte      | H110M-S2-CF                 | [43a9184afe](https://linux-hardware.org/?probe=43a9184afe) | Sep 16, 2022 |
| ASRock        | P43DE3                      | [c1c1a13db0](https://linux-hardware.org/?probe=c1c1a13db0) | Sep 16, 2022 |
| Gigabyte      | Z490 UD                     | [66c96720a1](https://linux-hardware.org/?probe=66c96720a1) | Sep 16, 2022 |
| Gigabyte      | G41M-Combo                  | [a4b02d9021](https://linux-hardware.org/?probe=a4b02d9021) | Sep 16, 2022 |
| ASRock        | H61M-VS                     | [6aef75c837](https://linux-hardware.org/?probe=6aef75c837) | Sep 15, 2022 |
| Intel         | D33217GKE G76540-204        | [cb5eb5c2c6](https://linux-hardware.org/?probe=cb5eb5c2c6) | Sep 15, 2022 |
| ASUSTek       | P8H61-M LE                  | [d8ecff6375](https://linux-hardware.org/?probe=d8ecff6375) | Sep 15, 2022 |
| ASUSTek       | P8H61-M LX3                 | [b1e2832974](https://linux-hardware.org/?probe=b1e2832974) | Sep 15, 2022 |
| Huanan        | X99-F8D V2.4                | [6f3638ecc6](https://linux-hardware.org/?probe=6f3638ecc6) | Sep 15, 2022 |
| Foxconn       | G41MD                       | [9b301e1ebe](https://linux-hardware.org/?probe=9b301e1ebe) | Sep 15, 2022 |
| Gigabyte      | X79-UD3                     | [e343c2470f](https://linux-hardware.org/?probe=e343c2470f) | Sep 14, 2022 |
| Gigabyte      | Z77M-D3H                    | [d4b7cae48f](https://linux-hardware.org/?probe=d4b7cae48f) | Sep 14, 2022 |
| Huanan        | X99-F8D V2.4                | [c364778ad7](https://linux-hardware.org/?probe=c364778ad7) | Sep 14, 2022 |
| Gigabyte      | MZBSWMP-00                  | [92d4357c28](https://linux-hardware.org/?probe=92d4357c28) | Sep 14, 2022 |
| ASRock        | N68-S3 UCC                  | [5f3b320503](https://linux-hardware.org/?probe=5f3b320503) | Sep 14, 2022 |
| ASUSTek       | Maximus IV Extreme-Z        | [1c7a238f26](https://linux-hardware.org/?probe=1c7a238f26) | Sep 13, 2022 |
| Gigabyte      | A320M-H-CF                  | [591cf6246a](https://linux-hardware.org/?probe=591cf6246a) | Sep 13, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [377d466877](https://linux-hardware.org/?probe=377d466877) | Sep 13, 2022 |
| MSI           | 870-G45                     | [0245395372](https://linux-hardware.org/?probe=0245395372) | Sep 13, 2022 |
| ASUSTek       | B85M-G                      | [74a9860a2e](https://linux-hardware.org/?probe=74a9860a2e) | Sep 13, 2022 |
| ASUSTek       | TUF Gaming B660M-PLUS WI... | [2adaf06b86](https://linux-hardware.org/?probe=2adaf06b86) | Sep 13, 2022 |
| Gigabyte      | Z77M-D3H                    | [5f8b8dc32d](https://linux-hardware.org/?probe=5f8b8dc32d) | Sep 13, 2022 |
| Gigabyte      | H110M-D3H R2-CF             | [87971a36df](https://linux-hardware.org/?probe=87971a36df) | Sep 13, 2022 |
| ASRock        | N68-GS4 FX                  | [85daab087c](https://linux-hardware.org/?probe=85daab087c) | Sep 13, 2022 |
| Huanan        | X99 F8D V2.2                | [ea2b1239e5](https://linux-hardware.org/?probe=ea2b1239e5) | Sep 12, 2022 |
| Gigabyte      | F2A55M-S1                   | [a5ce933202](https://linux-hardware.org/?probe=a5ce933202) | Sep 12, 2022 |
| Huanan        | X99 F8D V2.2                | [a463708cda](https://linux-hardware.org/?probe=a463708cda) | Sep 12, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [1930cd2551](https://linux-hardware.org/?probe=1930cd2551) | Sep 12, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [9062abaf37](https://linux-hardware.org/?probe=9062abaf37) | Sep 12, 2022 |
| ASUSTek       | PRIME H510M-K               | [19b674cc6d](https://linux-hardware.org/?probe=19b674cc6d) | Sep 12, 2022 |
| ASRock        | H110M-DGS R3.0              | [451dab91c7](https://linux-hardware.org/?probe=451dab91c7) | Sep 11, 2022 |
| Biostar       | G41D3C                      | [d7c3e18f9a](https://linux-hardware.org/?probe=d7c3e18f9a) | Sep 11, 2022 |
| Gigabyte      | Z490 UD                     | [d7cbff0646](https://linux-hardware.org/?probe=d7cbff0646) | Sep 11, 2022 |
| Intel         | D2500HN AAG81480-500        | [e78623b2a0](https://linux-hardware.org/?probe=e78623b2a0) | Sep 11, 2022 |
| ASRock        | 880GM-LE                    | [87e17aae81](https://linux-hardware.org/?probe=87e17aae81) | Sep 11, 2022 |
| MSI           | B450M PRO-VDH MAX           | [2944280488](https://linux-hardware.org/?probe=2944280488) | Sep 11, 2022 |
| ASRock        | G41M-VS3                    | [ea9ac42e6d](https://linux-hardware.org/?probe=ea9ac42e6d) | Sep 10, 2022 |
| ASUSTek       | H87-PLUS                    | [76dd595c93](https://linux-hardware.org/?probe=76dd595c93) | Sep 10, 2022 |
| ASRock        | A320M-HDV R4.0              | [cbb786796b](https://linux-hardware.org/?probe=cbb786796b) | Sep 10, 2022 |
| Gigabyte      | A320M-H-CF                  | [9fe50985ad](https://linux-hardware.org/?probe=9fe50985ad) | Sep 10, 2022 |
| ASUSTek       | SABERTOOTH X58              | [ce9d09e18a](https://linux-hardware.org/?probe=ce9d09e18a) | Sep 10, 2022 |
| ASRock        | H510M-HVS                   | [0874eaca4c](https://linux-hardware.org/?probe=0874eaca4c) | Sep 09, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [8f8a2cc0cb](https://linux-hardware.org/?probe=8f8a2cc0cb) | Sep 09, 2022 |
| ASUSTek       | PRIME A320M-K               | [cb47ce6e71](https://linux-hardware.org/?probe=cb47ce6e71) | Sep 09, 2022 |
| HP            | 1494                        | [5f0a73b28f](https://linux-hardware.org/?probe=5f0a73b28f) | Sep 09, 2022 |
| ASRock        | X370 Professional Gaming    | [a4bbe3346b](https://linux-hardware.org/?probe=a4bbe3346b) | Sep 08, 2022 |
| ASRock        | X370 Professional Gaming    | [129011f0c7](https://linux-hardware.org/?probe=129011f0c7) | Sep 08, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [97374173e6](https://linux-hardware.org/?probe=97374173e6) | Sep 08, 2022 |
| MSI           | H61M-P23                    | [457a0bd32f](https://linux-hardware.org/?probe=457a0bd32f) | Sep 08, 2022 |
| ASUSTek       | M5A78L-M LX3                | [82ea2a555b](https://linux-hardware.org/?probe=82ea2a555b) | Sep 08, 2022 |
| HP            | 1497                        | [3cf8f5d97a](https://linux-hardware.org/?probe=3cf8f5d97a) | Sep 07, 2022 |
| Gigabyte      | H55M-S2                     | [4aaaeb3cc4](https://linux-hardware.org/?probe=4aaaeb3cc4) | Sep 07, 2022 |
| Gigabyte      | P43T-ES3G                   | [9b62da0565](https://linux-hardware.org/?probe=9b62da0565) | Sep 07, 2022 |
| ASUSTek       | P8B75-V                     | [6848ab681b](https://linux-hardware.org/?probe=6848ab681b) | Sep 07, 2022 |
| ASUSTek       | P8B75-V                     | [cb3f77526b](https://linux-hardware.org/?probe=cb3f77526b) | Sep 06, 2022 |
| ASRock        | H110M-DVS R2.0              | [a47d0d40bf](https://linux-hardware.org/?probe=a47d0d40bf) | Sep 06, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [b86276ae55](https://linux-hardware.org/?probe=b86276ae55) | Sep 06, 2022 |
| Gigabyte      | 990XA-UD3                   | [307df0d230](https://linux-hardware.org/?probe=307df0d230) | Sep 05, 2022 |
| Gigabyte      | X79-UD3                     | [a3ebfb427d](https://linux-hardware.org/?probe=a3ebfb427d) | Sep 05, 2022 |
| Gigabyte      | MSQ87TN-00                  | [af31e1b75a](https://linux-hardware.org/?probe=af31e1b75a) | Sep 04, 2022 |
| Lenovo        | 3178 NOK                    | [9752c3bf3a](https://linux-hardware.org/?probe=9752c3bf3a) | Sep 04, 2022 |
| JGINYUE       | X99 TITANIUM D4             | [12ac2b2e8b](https://linux-hardware.org/?probe=12ac2b2e8b) | Sep 04, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [b5c65ceb22](https://linux-hardware.org/?probe=b5c65ceb22) | Sep 03, 2022 |
| ASUSTek       | P8Z77-M                     | [fc29a8d6f0](https://linux-hardware.org/?probe=fc29a8d6f0) | Sep 03, 2022 |
| MSI           | B450M BAZOOKA V2            | [6cb8a5dda5](https://linux-hardware.org/?probe=6cb8a5dda5) | Sep 03, 2022 |
| Lenovo        | 3140 NOK                    | [15c11bff97](https://linux-hardware.org/?probe=15c11bff97) | Sep 03, 2022 |
| MACHINIST     | B75 PRO V1.0                | [0f6c8f7249](https://linux-hardware.org/?probe=0f6c8f7249) | Sep 03, 2022 |
| ASRock        | G31M-S                      | [1adc4fd6b0](https://linux-hardware.org/?probe=1adc4fd6b0) | Sep 03, 2022 |
| ASUSTek       | A55BM-E                     | [69de391136](https://linux-hardware.org/?probe=69de391136) | Sep 03, 2022 |
| Gigabyte      | H81M-S1                     | [03a13ca37c](https://linux-hardware.org/?probe=03a13ca37c) | Sep 03, 2022 |
| Gigabyte      | B85-HD3                     | [3fdc9bf72e](https://linux-hardware.org/?probe=3fdc9bf72e) | Sep 03, 2022 |
| Lenovo        | H420                        | [becb9210d9](https://linux-hardware.org/?probe=becb9210d9) | Sep 03, 2022 |
| Pegatron      | 2A73h                       | [42b260ec6b](https://linux-hardware.org/?probe=42b260ec6b) | Sep 03, 2022 |
| ASRock        | A320M-DVS R4.0              | [599f5e06cb](https://linux-hardware.org/?probe=599f5e06cb) | Sep 02, 2022 |
| Gigabyte      | F2A88XN-WIFI                | [6ae1e9ad80](https://linux-hardware.org/?probe=6ae1e9ad80) | Sep 02, 2022 |
| Dell          | 0RY007                      | [29ee3bdaac](https://linux-hardware.org/?probe=29ee3bdaac) | Sep 02, 2022 |
| ASRock        | N68-GS4 FX                  | [f222b860da](https://linux-hardware.org/?probe=f222b860da) | Sep 02, 2022 |
| ASRock        | 990FX Extreme3              | [1e75cefa31](https://linux-hardware.org/?probe=1e75cefa31) | Sep 01, 2022 |
| ASUSTek       | P8Z77-V LE PLUS             | [0f7d76d65c](https://linux-hardware.org/?probe=0f7d76d65c) | Sep 01, 2022 |
| Gigabyte      | P55-US3L                    | [93e1829d36](https://linux-hardware.org/?probe=93e1829d36) | Sep 01, 2022 |
| Gigabyte      | GA-E6010N                   | [8daf2205a5](https://linux-hardware.org/?probe=8daf2205a5) | Sep 01, 2022 |
| ASUSTek       | PRIME B350M-K               | [ae0450c52a](https://linux-hardware.org/?probe=ae0450c52a) | Sep 01, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [c1ba9218de](https://linux-hardware.org/?probe=c1ba9218de) | Sep 01, 2022 |
| Gigabyte      | 970A-DS3P                   | [1bc16dc2be](https://linux-hardware.org/?probe=1bc16dc2be) | Sep 01, 2022 |
| ASRock        | A320M-DVS R4.0              | [c3ca58ba40](https://linux-hardware.org/?probe=c3ca58ba40) | Sep 01, 2022 |
| ASUSTek       | P8H61-MX                    | [52e7588080](https://linux-hardware.org/?probe=52e7588080) | Aug 31, 2022 |
| Intel         | X99                         | [8f4cdd5290](https://linux-hardware.org/?probe=8f4cdd5290) | Aug 31, 2022 |
| Gigabyte      | H55M-UD2H                   | [1a72b89675](https://linux-hardware.org/?probe=1a72b89675) | Aug 31, 2022 |
| Gigabyte      | B75M-D3H                    | [0146e0f5c8](https://linux-hardware.org/?probe=0146e0f5c8) | Aug 31, 2022 |
| ASUSTek       | M2A-VM HDMI                 | [9d9462f5a9](https://linux-hardware.org/?probe=9d9462f5a9) | Aug 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [858b04d480](https://linux-hardware.org/?probe=858b04d480) | Aug 30, 2022 |
| ASRock        | B550M-HDV                   | [61f310f2a2](https://linux-hardware.org/?probe=61f310f2a2) | Aug 30, 2022 |
| Gigabyte      | B550M S2H                   | [73a8574652](https://linux-hardware.org/?probe=73a8574652) | Aug 30, 2022 |
| ASUSTek       | P5G41-M LX                  | [ecf64e8d47](https://linux-hardware.org/?probe=ecf64e8d47) | Aug 30, 2022 |
| ASUSTek       | P5G41-M LX                  | [b7e2198026](https://linux-hardware.org/?probe=b7e2198026) | Aug 30, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [9d3e935355](https://linux-hardware.org/?probe=9d3e935355) | Aug 30, 2022 |
| Unknown       | Unknown                     | [3f51be2653](https://linux-hardware.org/?probe=3f51be2653) | Aug 30, 2022 |
| Intel         | D525MWV AAE93081-401        | [985d906899](https://linux-hardware.org/?probe=985d906899) | Aug 29, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [a37d7cae28](https://linux-hardware.org/?probe=a37d7cae28) | Aug 29, 2022 |
| Gigabyte      | B550M S2H                   | [ac1d1ffdba](https://linux-hardware.org/?probe=ac1d1ffdba) | Aug 29, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [3b245a809d](https://linux-hardware.org/?probe=3b245a809d) | Aug 28, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [dcb225651d](https://linux-hardware.org/?probe=dcb225651d) | Aug 28, 2022 |
| MSI           | B560M-A PRO                 | [a550031b1d](https://linux-hardware.org/?probe=a550031b1d) | Aug 28, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [3ca98fc058](https://linux-hardware.org/?probe=3ca98fc058) | Aug 28, 2022 |
| ASRock        | 990FX Extreme3              | [ec517dabad](https://linux-hardware.org/?probe=ec517dabad) | Aug 28, 2022 |
| ASUSTek       | P7P55D                      | [4476755d78](https://linux-hardware.org/?probe=4476755d78) | Aug 28, 2022 |
| KupiDesheg... | Intel X79 lga 2011          | [92f097526f](https://linux-hardware.org/?probe=92f097526f) | Aug 28, 2022 |
| Dell          | 0RY007                      | [8ff65ac056](https://linux-hardware.org/?probe=8ff65ac056) | Aug 27, 2022 |
| ASUSTek       | PRIME A320M-A               | [517c813c17](https://linux-hardware.org/?probe=517c813c17) | Aug 27, 2022 |
| Gigabyte      | GA-E6010N                   | [5a180519a2](https://linux-hardware.org/?probe=5a180519a2) | Aug 27, 2022 |
| Gigabyte      | H77N-WIFI                   | [458442867e](https://linux-hardware.org/?probe=458442867e) | Aug 27, 2022 |
| ASUSTek       | F1A75-M-PRO R2.0            | [e7e057dd6d](https://linux-hardware.org/?probe=e7e057dd6d) | Aug 27, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [0d6eddc581](https://linux-hardware.org/?probe=0d6eddc581) | Aug 27, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [d745245f37](https://linux-hardware.org/?probe=d745245f37) | Aug 27, 2022 |
| Intel         | X99                         | [4acddafcc3](https://linux-hardware.org/?probe=4acddafcc3) | Aug 26, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | [8ca59c4893](https://linux-hardware.org/?probe=8ca59c4893) | Aug 26, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [bb51a9a03b](https://linux-hardware.org/?probe=bb51a9a03b) | Aug 26, 2022 |
| Gigabyte      | Z170X-Gaming 3              | [d1ca2bc878](https://linux-hardware.org/?probe=d1ca2bc878) | Aug 25, 2022 |
| Dell          | 0RY007                      | [8dece84856](https://linux-hardware.org/?probe=8dece84856) | Aug 25, 2022 |
| Gigabyte      | Z170X-Gaming 3              | [8cb82a76c6](https://linux-hardware.org/?probe=8cb82a76c6) | Aug 25, 2022 |
| ASUSTek       | Z170-A                      | [d3c0ea0334](https://linux-hardware.org/?probe=d3c0ea0334) | Aug 23, 2022 |
| ASUSTek       | Z170-A                      | [257425efde](https://linux-hardware.org/?probe=257425efde) | Aug 23, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | [9f66ff50d5](https://linux-hardware.org/?probe=9f66ff50d5) | Aug 23, 2022 |
| MSI           | Z390-A PRO                  | [f48d5a0a1c](https://linux-hardware.org/?probe=f48d5a0a1c) | Aug 23, 2022 |
| Dell          | 0T1D10 A01                  | [c67ce079c7](https://linux-hardware.org/?probe=c67ce079c7) | Aug 23, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | [ef940d86f4](https://linux-hardware.org/?probe=ef940d86f4) | Aug 23, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [5a6911f8d2](https://linux-hardware.org/?probe=5a6911f8d2) | Aug 23, 2022 |
| Soyo          | SY-Classic B660M            | [7a2731c6bb](https://linux-hardware.org/?probe=7a2731c6bb) | Aug 23, 2022 |
| Soyo          | SY-Classic B660M            | [dcb41473bd](https://linux-hardware.org/?probe=dcb41473bd) | Aug 23, 2022 |
| ASUSTek       | P5QPL-AM                    | [1fdb1ad301](https://linux-hardware.org/?probe=1fdb1ad301) | Aug 23, 2022 |
| ASRock        | N68-GS4 FX                  | [026abd6a11](https://linux-hardware.org/?probe=026abd6a11) | Aug 23, 2022 |
| Gigabyte      | A320M-H-CF                  | [70d138aa2e](https://linux-hardware.org/?probe=70d138aa2e) | Aug 23, 2022 |
| Gigabyte      | F2A88XM-DS2                 | [6c91036286](https://linux-hardware.org/?probe=6c91036286) | Aug 22, 2022 |
| ASUSTek       | P9X79                       | [e279591136](https://linux-hardware.org/?probe=e279591136) | Aug 22, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [37af41aa76](https://linux-hardware.org/?probe=37af41aa76) | Aug 22, 2022 |
| Gigabyte      | 970A-DS3                    | [ae71518dcf](https://linux-hardware.org/?probe=ae71518dcf) | Aug 22, 2022 |
| MSI           | MAG B550M MORTAR            | [441eb14634](https://linux-hardware.org/?probe=441eb14634) | Aug 21, 2022 |
| Huanan        | X99 F8D V2.2                | [d12525038d](https://linux-hardware.org/?probe=d12525038d) | Aug 21, 2022 |
| HP            | 304Bh                       | [1e3d59e493](https://linux-hardware.org/?probe=1e3d59e493) | Aug 21, 2022 |
| Gigabyte      | G41MT-S2P                   | [6d96e92f0d](https://linux-hardware.org/?probe=6d96e92f0d) | Aug 21, 2022 |
| Foxconn       | G31MX Series                | [a68130c719](https://linux-hardware.org/?probe=a68130c719) | Aug 21, 2022 |
| ASUSTek       | PRIME H510M-K               | [d52c203fc9](https://linux-hardware.org/?probe=d52c203fc9) | Aug 21, 2022 |
| ECS           | B75H2-M3                    | [c42410be8b](https://linux-hardware.org/?probe=c42410be8b) | Aug 21, 2022 |
| ASUSTek       | VM45                        | [7d7b99c7f4](https://linux-hardware.org/?probe=7d7b99c7f4) | Aug 21, 2022 |
| ASUSTek       | A88XM-A                     | [f8900d8840](https://linux-hardware.org/?probe=f8900d8840) | Aug 20, 2022 |
| Gigabyte      | H61M-S1                     | [a558a229d2](https://linux-hardware.org/?probe=a558a229d2) | Aug 20, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [8b871bcdc8](https://linux-hardware.org/?probe=8b871bcdc8) | Aug 20, 2022 |
| Gigabyte      | Z170-D3H-CF                 | [8b3ca4e7d1](https://linux-hardware.org/?probe=8b3ca4e7d1) | Aug 19, 2022 |
| MSI           | Z390-A PRO                  | [4bb68951b6](https://linux-hardware.org/?probe=4bb68951b6) | Aug 19, 2022 |
| Dell          | 0TVR1F A01                  | [1b8906bb20](https://linux-hardware.org/?probe=1b8906bb20) | Aug 19, 2022 |
| Gigabyte      | Z590 UD AC                  | [2709dfd2c3](https://linux-hardware.org/?probe=2709dfd2c3) | Aug 19, 2022 |
| Gigabyte      | Q87M-D2H                    | [8c56960243](https://linux-hardware.org/?probe=8c56960243) | Aug 19, 2022 |
| ASUSTek       | PRIME B460M-K               | [f5f3761418](https://linux-hardware.org/?probe=f5f3761418) | Aug 19, 2022 |
| ASUSTek       | M4A77TD PRO                 | [a93d70f67b](https://linux-hardware.org/?probe=a93d70f67b) | Aug 19, 2022 |
| Gigabyte      | H310M H x.x                 | [67f253af6e](https://linux-hardware.org/?probe=67f253af6e) | Aug 18, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [334844dd8c](https://linux-hardware.org/?probe=334844dd8c) | Aug 18, 2022 |
| Gigabyte      | F2A88XM-D3H                 | [3d5404aaff](https://linux-hardware.org/?probe=3d5404aaff) | Aug 18, 2022 |
| ASRock        | 960GM-GS3 FX                | [ea73b0ba84](https://linux-hardware.org/?probe=ea73b0ba84) | Aug 17, 2022 |
| Acer          | Aspire TC-705               | [22d9229d27](https://linux-hardware.org/?probe=22d9229d27) | Aug 17, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [49872997f2](https://linux-hardware.org/?probe=49872997f2) | Aug 17, 2022 |
| ASRock        | FM2A75M-DGS R2.0            | [f6ff5fc2bf](https://linux-hardware.org/?probe=f6ff5fc2bf) | Aug 17, 2022 |
| MSI           | 870-G45                     | [37a9139281](https://linux-hardware.org/?probe=37a9139281) | Aug 16, 2022 |
| Gigabyte      | 990XA-UD3                   | [6c1d243576](https://linux-hardware.org/?probe=6c1d243576) | Aug 16, 2022 |
| MSI           | Z170-A PRO                  | [c4a4ad3997](https://linux-hardware.org/?probe=c4a4ad3997) | Aug 16, 2022 |
| ASRock        | 970 Pro3 R2.0               | [ca6f08767b](https://linux-hardware.org/?probe=ca6f08767b) | Aug 16, 2022 |
| Gigabyte      | 965P-S3                     | [46a181ec76](https://linux-hardware.org/?probe=46a181ec76) | Aug 15, 2022 |
| ASUSTek       | M3A76-CM                    | [710f116ee9](https://linux-hardware.org/?probe=710f116ee9) | Aug 15, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [0b0efd02ad](https://linux-hardware.org/?probe=0b0efd02ad) | Aug 15, 2022 |
| ASUSTek       | Basswood                    | [26e4efad3f](https://linux-hardware.org/?probe=26e4efad3f) | Aug 14, 2022 |
| ASUSTek       | STRIX X99 GAMING            | [b326bf9edc](https://linux-hardware.org/?probe=b326bf9edc) | Aug 14, 2022 |
| ASUSTek       | PRIME B250-PLUS             | [6dab67810d](https://linux-hardware.org/?probe=6dab67810d) | Aug 14, 2022 |
| Gigabyte      | H87-D3H-CF                  | [a37d2f3c90](https://linux-hardware.org/?probe=a37d2f3c90) | Aug 13, 2022 |
| ASRock        | H110M-DGS R3.0              | [5ae618501c](https://linux-hardware.org/?probe=5ae618501c) | Aug 13, 2022 |
| MSI           | B450M GAMING PLUS           | [ac47b6f330](https://linux-hardware.org/?probe=ac47b6f330) | Aug 13, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [c00d2d23cb](https://linux-hardware.org/?probe=c00d2d23cb) | Aug 13, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [f542f6836c](https://linux-hardware.org/?probe=f542f6836c) | Aug 13, 2022 |
| ASRock        | J5040-ITX                   | [acb79396fd](https://linux-hardware.org/?probe=acb79396fd) | Aug 13, 2022 |
| ASRock        | H61M-HVS                    | [12ad08259b](https://linux-hardware.org/?probe=12ad08259b) | Aug 12, 2022 |
| ASUSTek       | P8Z77-V LK                  | [913f2b20a8](https://linux-hardware.org/?probe=913f2b20a8) | Aug 12, 2022 |
| ASUSTek       | H81-PLUS                    | [fd9673005a](https://linux-hardware.org/?probe=fd9673005a) | Aug 10, 2022 |
| Gigabyte      | H55M-USB3                   | [505a83fd9d](https://linux-hardware.org/?probe=505a83fd9d) | Aug 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | [4b083cc768](https://linux-hardware.org/?probe=4b083cc768) | Aug 10, 2022 |
| win elemen... | M1K A00                     | [b8fbdf223f](https://linux-hardware.org/?probe=b8fbdf223f) | Aug 10, 2022 |
| ASUSTek       | H81M-K                      | [79d09da66f](https://linux-hardware.org/?probe=79d09da66f) | Aug 10, 2022 |
| win elemen... | M1K A00                     | [06eeaf2405](https://linux-hardware.org/?probe=06eeaf2405) | Aug 10, 2022 |
| ASUSTek       | M5A78L LE                   | [e4cf778f69](https://linux-hardware.org/?probe=e4cf778f69) | Aug 09, 2022 |
| Dell          | 0Y5DDC A00                  | [d9058af5e6](https://linux-hardware.org/?probe=d9058af5e6) | Aug 09, 2022 |
| MSI           | B250M PRO-VD                | [1cc3a005fc](https://linux-hardware.org/?probe=1cc3a005fc) | Aug 09, 2022 |
| Gigabyte      | H110M-S2V-CF                | [df0b3c4e19](https://linux-hardware.org/?probe=df0b3c4e19) | Aug 08, 2022 |
| Gigabyte      | B450 GAMING X               | [cb35907248](https://linux-hardware.org/?probe=cb35907248) | Aug 08, 2022 |
| Intel         | X99                         | [7004914e87](https://linux-hardware.org/?probe=7004914e87) | Aug 08, 2022 |
| MSI           | B85-G43                     | [d35fcb0c87](https://linux-hardware.org/?probe=d35fcb0c87) | Aug 08, 2022 |
| Pegatron      | IPX41-D3                    | [2b76b11954](https://linux-hardware.org/?probe=2b76b11954) | Aug 08, 2022 |
| Gigabyte      | X58-USB3                    | [c4b360063d](https://linux-hardware.org/?probe=c4b360063d) | Aug 08, 2022 |
| ASUSTek       | B85M-G                      | [82c2bcc60f](https://linux-hardware.org/?probe=82c2bcc60f) | Aug 07, 2022 |
| ASRock        | 960GM-VGS3 FX               | [c5c5963283](https://linux-hardware.org/?probe=c5c5963283) | Aug 07, 2022 |
| ASUSTek       | H110M-R                     | [5c19c69b07](https://linux-hardware.org/?probe=5c19c69b07) | Aug 07, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [02fcf42041](https://linux-hardware.org/?probe=02fcf42041) | Aug 07, 2022 |
| ASUSTek       | PRIME Z370-P                | [6c9131c742](https://linux-hardware.org/?probe=6c9131c742) | Aug 07, 2022 |
| ASUSTek       | Z170-P                      | [8ed3ede567](https://linux-hardware.org/?probe=8ed3ede567) | Aug 06, 2022 |
| ASRock        | N68C-GS UCC                 | [c426402288](https://linux-hardware.org/?probe=c426402288) | Aug 06, 2022 |
| PCWare        | IPX3060E                    | [3fc0886f3b](https://linux-hardware.org/?probe=3fc0886f3b) | Aug 06, 2022 |
| ASRock        | 970 Pro3 R2.0               | [3bdcd4ebd0](https://linux-hardware.org/?probe=3bdcd4ebd0) | Aug 06, 2022 |
| Gigabyte      | H110M-M2-CF                 | [23e85738fb](https://linux-hardware.org/?probe=23e85738fb) | Aug 06, 2022 |
| ASUSTek       | P8Z77-V LX                  | [62ec3bce07](https://linux-hardware.org/?probe=62ec3bce07) | Aug 05, 2022 |
| ASUSTek       | P5GC-MX/1333                | [4de0aa7ccf](https://linux-hardware.org/?probe=4de0aa7ccf) | Aug 05, 2022 |
| Gigabyte      | P35-DS3L                    | [8479ed8742](https://linux-hardware.org/?probe=8479ed8742) | Aug 05, 2022 |
| PCWare        | IPX3060E                    | [d5045f1364](https://linux-hardware.org/?probe=d5045f1364) | Aug 04, 2022 |
| Foxconn       | nT-330i                     | [64504a98ed](https://linux-hardware.org/?probe=64504a98ed) | Aug 04, 2022 |
| ASUSTek       | P8H61-MX R2.0               | [37bbf9a538](https://linux-hardware.org/?probe=37bbf9a538) | Aug 04, 2022 |
| Biostar       | TB85                        | [8d00176a54](https://linux-hardware.org/?probe=8d00176a54) | Aug 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [7f6ef3b14a](https://linux-hardware.org/?probe=7f6ef3b14a) | Aug 03, 2022 |
| Dell          | 0RY007                      | [2ae37df942](https://linux-hardware.org/?probe=2ae37df942) | Aug 03, 2022 |
| Koloe         | X58                         | [19c2318b39](https://linux-hardware.org/?probe=19c2318b39) | Aug 03, 2022 |
| Koloe         | X58                         | [a98013f216](https://linux-hardware.org/?probe=a98013f216) | Aug 03, 2022 |
| Huanan        | X79 PLUS V6.11              | [a4109a7ce6](https://linux-hardware.org/?probe=a4109a7ce6) | Aug 03, 2022 |
| ASUSTek       | A88XM-A                     | [633c971916](https://linux-hardware.org/?probe=633c971916) | Aug 02, 2022 |
| ASUSTek       | P8H61-M LX2                 | [e1918e04fc](https://linux-hardware.org/?probe=e1918e04fc) | Aug 02, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | [afdfe95192](https://linux-hardware.org/?probe=afdfe95192) | Aug 01, 2022 |
| ASRock        | G41M-VS3                    | [db7419f5a9](https://linux-hardware.org/?probe=db7419f5a9) | Aug 01, 2022 |
| Gigabyte      | H110M-S2V-CF                | [c82958696b](https://linux-hardware.org/?probe=c82958696b) | Aug 01, 2022 |
| Gigabyte      | Z370M D3H-CF                | [73f940e59b](https://linux-hardware.org/?probe=73f940e59b) | Jul 31, 2022 |
| ASRock        | B450M Pro4                  | [33185c0a98](https://linux-hardware.org/?probe=33185c0a98) | Jul 31, 2022 |
| ASUSTek       | P8B75-M LE                  | [2433e8dc49](https://linux-hardware.org/?probe=2433e8dc49) | Jul 31, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ROSA/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| ROSA R10           | 2140     | 13.78%  |
| ROSA R11           | 2086     | 13.43%  |
| ROSA R8            | 1892     | 12.18%  |
| ROSA R6            | 1778     | 11.45%  |
| ROSA R7            | 1692     | 10.9%   |
| ROSA R8.1          | 1459     | 9.4%    |
| ROSA R9            | 1277     | 8.22%   |
| ROSA R11.1         | 1152     | 7.42%   |
| ROSA 12.2          | 1022     | 6.58%   |
| ROSA 12.3          | 325      | 2.09%   |
| ROSA R5            | 244      | 1.57%   |
| ROSA 12.1          | 178      | 1.15%   |
| ROSA 12            | 118      | 0.76%   |
| ROSA R4            | 42       | 0.27%   |
| ROSA R12           | 42       | 0.27%   |
| ROSA R3            | 26       | 0.17%   |
| ROSA 2019.05       | 13       | 0.08%   |
| ROSA R9-R11        | 12       | 0.08%   |
| ROSA Chrome 2.0    | 7        | 0.05%   |
| ROSA R2            | 6        | 0.04%   |
| ROSA 2012.0        | 5        | 0.03%   |
| ROSA R4-R8         | 3        | 0.02%   |
| ROSA Nickel 2019.0 | 3        | 0.02%   |
| ROSA DX 1.0        | 2        | 0.01%   |
| ROSA 2021.1        | 2        | 0.01%   |
| ROSA R1            | 1        | 0.01%   |
| ROSA 2019.0        | 1        | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| ROSA | 12865    | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Desktops | Percent |
|-------------------------------------|----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 1048     | 6.24%   |
| 3.14.44-nrj-desktop-2rosa-x86_64    | 950      | 5.66%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 938      | 5.59%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 916      | 5.46%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 902      | 5.37%   |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 862      | 5.13%   |
| 4.1.15-nrj-desktop-1rosa-x86_64     | 745      | 4.44%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 500      | 2.98%   |
| 3.14.44-nrj-desktop-2rosa-i586      | 437      | 2.6%    |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 399      | 2.38%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 351      | 2.09%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 330      | 1.97%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 306      | 1.82%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 289      | 1.72%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 262      | 1.56%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 256      | 1.52%   |
| 4.1.16-nrj-desktop-1rosa-x86_64     | 256      | 1.52%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 239      | 1.42%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 235      | 1.4%    |
| 4.15.0-desktop-68.5rosa-x86_64      | 232      | 1.38%   |
| 4.15.0-desktop-45.1rosa-i586        | 220      | 1.31%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 218      | 1.3%    |
| 4.1.15-nrj-desktop-1rosa-i586       | 218      | 1.3%    |
| 5.4.32-generic-2rosa-x86_64         | 212      | 1.26%   |
| 5.4.83-generic-2rosa-x86_64         | 194      | 1.16%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 194      | 1.16%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 184      | 1.1%    |
| 4.9.9-nrj-desktop-1rosa-i586        | 178      | 1.06%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 178      | 1.06%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 178      | 1.06%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 145      | 0.86%   |
| 4.1.22-nrj-desktop-2rosa-x86_64     | 143      | 0.85%   |
| 3.14.53-nrj-desktop-1rosa-x86_64    | 143      | 0.85%   |
| 4.1.33-nrj-desktop-1rosa-x86_64     | 132      | 0.79%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 126      | 0.75%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 124      | 0.74%   |
| 5.10.71-generic-1rosa2021.1-x86_64  | 116      | 0.69%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 111      | 0.66%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 108      | 0.64%   |
| 4.1.13-nrj-desktop-1rosa-x86_64     | 103      | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 4.15.0   | 2237     | 13.6%   |
| 3.14.44  | 1381     | 8.39%   |
| 4.9.60   | 1297     | 7.88%   |
| 4.9.20   | 1167     | 7.09%   |
| 4.1.25   | 1161     | 7.06%   |
| 4.1.15   | 959      | 5.83%   |
| 5.10.74  | 916      | 5.57%   |
| 4.1.34   | 690      | 4.19%   |
| 4.1.38   | 588      | 3.57%   |
| 4.9.9    | 503      | 3.06%   |
| 4.9.124  | 475      | 2.89%   |
| 4.9.155  | 363      | 2.21%   |
| 4.1.16   | 329      | 2%      |
| 4.9.76   | 321      | 1.95%   |
| 5.4.32   | 286      | 1.74%   |
| 4.9.41   | 283      | 1.72%   |
| 5.4.83   | 238      | 1.45%   |
| 4.1.22   | 196      | 1.19%   |
| 3.14.53  | 195      | 1.19%   |
| 4.1.19   | 192      | 1.17%   |
| 5.10.118 | 187      | 1.14%   |
| 4.1.33   | 177      | 1.08%   |
| 4.9.95   | 162      | 0.98%   |
| 4.1.13   | 148      | 0.9%    |
| 4.9.111  | 135      | 0.82%   |
| 5.15.75  | 118      | 0.72%   |
| 5.10.71  | 116      | 0.71%   |
| 4.9.87   | 96       | 0.58%   |
| 3.14.33  | 91       | 0.55%   |
| 5.15.79  | 88       | 0.53%   |
| 3.14.25  | 87       | 0.53%   |
| 4.9.14   | 54       | 0.33%   |
| 5.4.40   | 53       | 0.32%   |
| 3.14.39  | 52       | 0.32%   |
| 4.9.34   | 45       | 0.27%   |
| 5.17.11  | 43       | 0.26%   |
| 5.15.77  | 37       | 0.22%   |
| 5.10.150 | 33       | 0.2%    |
| 5.15.43  | 32       | 0.19%   |
| 5.15.32  | 28       | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 4.9     | 4222     | 28.42%  |
| 4.1     | 3915     | 26.36%  |
| 4.15    | 2243     | 15.1%   |
| 3.14    | 1766     | 11.89%  |
| 5.10    | 1212     | 8.16%   |
| 5.4     | 607      | 4.09%   |
| 5.15    | 287      | 1.93%   |
| 4.4     | 67       | 0.45%   |
| 5.18    | 51       | 0.34%   |
| 5.17    | 43       | 0.29%   |
| 4.8     | 38       | 0.26%   |
| 3.10    | 32       | 0.22%   |
| 4.7     | 26       | 0.18%   |
| 4.13    | 26       | 0.18%   |
| 5.0     | 25       | 0.17%   |
| 4.19    | 23       | 0.15%   |
| 4.16    | 22       | 0.15%   |
| 4.6     | 20       | 0.13%   |
| 4.18    | 20       | 0.13%   |
| 3.18    | 19       | 0.13%   |
| 6.0     | 18       | 0.12%   |
| 5.16    | 15       | 0.1%    |
| 4.14    | 13       | 0.09%   |
| 5.5     | 12       | 0.08%   |
| 4.3     | 12       | 0.08%   |
| 4.2     | 12       | 0.08%   |
| 4.17    | 12       | 0.08%   |
| 5.3     | 11       | 0.07%   |
| 4.5     | 11       | 0.07%   |
| 4.0     | 10       | 0.07%   |
| 6.1     | 9        | 0.06%   |
| 5.2     | 8        | 0.05%   |
| 4.12    | 6        | 0.04%   |
| 4.11    | 6        | 0.04%   |
| 3.0     | 6        | 0.04%   |
| 5.8     | 5        | 0.03%   |
| 5.9     | 4        | 0.03%   |
| 3.19    | 4        | 0.03%   |
| 5.6     | 3        | 0.02%   |
| 5.19    | 2        | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 10201    | 77.42%  |
| i686   | 2975     | 22.58%  |
| e2k    | 1        | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE4       | 9176     | 66.31%  |
| KDE5       | 3175     | 22.95%  |
| GNOME      | 693      | 5.01%   |
| LXQt       | 375      | 2.71%   |
| MATE       | 178      | 1.29%   |
| XFCE       | 109      | 0.79%   |
| LXDE       | 73       | 0.53%   |
| Unknown    | 54       | 0.39%   |
| KDE        | 2        | 0.01%   |
| X-Cinnamon | 1        | 0.01%   |
| Cinnamon   | 1        | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 11847    | 90.16%  |
| Wayland | 1286     | 9.79%   |
| Tty     | 5        | 0.04%   |
| Unknown | 2        | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| KDM     | 9279     | 67.48%  |
| SDDM    | 3371     | 24.51%  |
| GDM     | 989      | 7.19%   |
| TDM     | 51       | 0.37%   |
| LightDM | 43       | 0.31%   |
| Unknown | 9        | 0.07%   |
| XDM     | 8        | 0.06%   |
| LDM     | 1        | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| Unknown     | 10634    | 79.75%  |
| ru_RU       | 2397     | 17.98%  |
| en_US       | 72       | 0.54%   |
| de_DE       | 39       | 0.29%   |
| pl_PL       | 35       | 0.26%   |
| pt_BR       | 22       | 0.16%   |
| fr_FR       | 22       | 0.16%   |
| es_ES       | 20       | 0.15%   |
| ru_UA       | 16       | 0.12%   |
| it_IT       | 16       | 0.12%   |
| en_GB       | 12       | 0.09%   |
| ro_RO       | 6        | 0.04%   |
| pt_PT       | 6        | 0.04%   |
| es_AR       | 4        | 0.03%   |
| es_CO       | 3        | 0.02%   |
| cs_CZ       | 3        | 0.02%   |
| C           | 3        | 0.02%   |
| sk_SK       | 2        | 0.01%   |
| hu_HU       | 2        | 0.01%   |
| es_MX       | 2        | 0.01%   |
| sr_RS@latin | 1        | 0.01%   |
| sr_ME       | 1        | 0.01%   |
| ru_KZ       | 1        | 0.01%   |
| ru_BY       | 1        | 0.01%   |
| lt_LT       | 1        | 0.01%   |
| ja_JP       | 1        | 0.01%   |
| fr_BE       | 1        | 0.01%   |
| es_VE       | 1        | 0.01%   |
| es_UY       | 1        | 0.01%   |
| es_PE       | 1        | 0.01%   |
| en_IN       | 1        | 0.01%   |
| en_CA       | 1        | 0.01%   |
| el_GR       | 1        | 0.01%   |
| de_CH       | 1        | 0.01%   |
| Default     | 1        | 0.01%   |
| bg_BG       | 1        | 0.01%   |
| be_BY       | 1        | 0.01%   |
| ar_EG       | 1        | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 10839    | 82.23%  |
| EFI  | 2342     | 17.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Unknown  | 8297     | 60.78%  |
| Ext4     | 5090     | 37.29%  |
| Btrfs    | 176      | 1.29%   |
| Ext3     | 39       | 0.29%   |
| Ext2     | 16       | 0.12%   |
| Xfs      | 12       | 0.09%   |
| F2fs     | 7        | 0.05%   |
| SAMSUNG  | 6        | 0.04%   |
| Aufs     | 3        | 0.02%   |
| Reiserfs | 2        | 0.01%   |
| Overlay  | 1        | 0.01%   |
| Exfat    | 1        | 0.01%   |
| 2G       | 1        | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| MBR     | 8503     | 61.32%  |
| GPT     | 2801     | 20.2%   |
| Unknown | 2563     | 18.48%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 11774    | 88.48%  |
| Yes       | 1533     | 11.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 10492    | 77.64%  |
| Yes       | 3021     | 22.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 4635     | 36.03%  |
| Gigabyte Technology | 2968     | 23.07%  |
| ASRock              | 1430     | 11.12%  |
| MSI                 | 1337     | 10.39%  |
| Intel               | 333      | 2.59%   |
| ECS                 | 288      | 2.24%   |
| Hewlett-Packard     | 263      | 2.04%   |
| Dell                | 206      | 1.6%    |
| Biostar             | 203      | 1.58%   |
| Foxconn             | 167      | 1.3%    |
| Unknown             | 163      | 1.27%   |
| Acer                | 153      | 1.19%   |
| Lenovo              | 135      | 1.05%   |
| Pegatron            | 109      | 0.85%   |
| Fujitsu             | 36       | 0.28%   |
| Fujitsu Siemens     | 35       | 0.27%   |
| WinFast             | 33       | 0.26%   |
| Huanan              | 32       | 0.25%   |
| EPoX Computer       | 32       | 0.25%   |
| Nvidia              | 18       | 0.14%   |
| ABIT                | 18       | 0.14%   |
| Packard Bell        | 15       | 0.12%   |
| Medion              | 15       | 0.12%   |
| Supermicro          | 13       | 0.1%    |
| SiS Technology      | 11       | 0.09%   |
| AMD                 | 10       | 0.08%   |
| JW Technology       | 9        | 0.07%   |
| eMachines           | 9        | 0.07%   |
| Shuttle             | 8        | 0.06%   |
| IBM                 | 7        | 0.05%   |
| ZOTAC               | 6        | 0.05%   |
| PCChips             | 6        | 0.05%   |
| Lite-On             | 5        | 0.04%   |
| EVGA                | 5        | 0.04%   |
| Colorful Technology | 5        | 0.04%   |
| AMI                 | 5        | 0.04%   |
| VIA Technologies    | 4        | 0.03%   |
| Positivo            | 4        | 0.03%   |
| OEM                 | 4        | 0.03%   |
| NEC Computers       | 4        | 0.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| ASUS All Series            | 358      | 2.78%   |
| Unknown                    | 177      | 1.38%   |
| ASUS M5A78L-M LX3          | 78       | 0.61%   |
| MSI MS-7817                | 75       | 0.58%   |
| ASUS M5A97 R2.0            | 68       | 0.53%   |
| ASRock G31M-S              | 66       | 0.51%   |
| Gigabyte 970A-DS3P         | 62       | 0.48%   |
| ASRock N68C-S UCC          | 60       | 0.47%   |
| MSI MS-7529                | 56       | 0.44%   |
| Gigabyte H61M-S1           | 55       | 0.43%   |
| Gigabyte G31M-ES2L         | 55       | 0.43%   |
| MSI MS-7592                | 53       | 0.41%   |
| ASUS P5K                   | 53       | 0.41%   |
| ASUS P5B                   | 48       | 0.37%   |
| ASUS P8H61-M LX3 R2.0      | 47       | 0.37%   |
| ASUS P5KPL-AM              | 47       | 0.37%   |
| MSI MS-7309                | 46       | 0.36%   |
| ASUS P8Z77-V LX            | 46       | 0.36%   |
| MSI MS-7788                | 45       | 0.35%   |
| ASUS P5G41T-M LX2/GB       | 45       | 0.35%   |
| ASUS M5A97 LE R2.0         | 45       | 0.35%   |
| ASUS P5KPL-AM IN/ROEM/SI   | 43       | 0.33%   |
| ASRock G41M-VS3            | 41       | 0.32%   |
| MSI MS-7721                | 40       | 0.31%   |
| MSI MS-7693                | 40       | 0.31%   |
| ASUS H110M-R               | 40       | 0.31%   |
| Gigabyte G41M-Combo        | 39       | 0.3%    |
| ASUS SABERTOOTH 990FX R2.0 | 39       | 0.3%    |
| Gigabyte H61M-S2PV         | 37       | 0.29%   |
| ASUS M5A78L-M/USB3         | 37       | 0.29%   |
| MSI MS-7369                | 36       | 0.28%   |
| ASUS P5Q SE2               | 35       | 0.27%   |
| ASUS P5GC-MX/1333          | 35       | 0.27%   |
| ASUS P8H61-M LE            | 32       | 0.25%   |
| ASUS P5G41T-M LX           | 32       | 0.25%   |
| MSI MS-7758                | 31       | 0.24%   |
| MSI MS-7680                | 31       | 0.24%   |
| Gigabyte Z77-DS3H          | 31       | 0.24%   |
| ASUS P5KPL-AM SE           | 31       | 0.24%   |
| ASUS M2N                   | 31       | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUS All            | 358      | 2.78%   |
| ASUS M5A78L-M       | 205      | 1.59%   |
| ASUS PRIME          | 186      | 1.45%   |
| ASUS P8H61-M        | 185      | 1.44%   |
| Unknown             | 177      | 1.38%   |
| ASUS P5KPL-AM       | 159      | 1.24%   |
| ASUS M5A97          | 155      | 1.2%    |
| HP Compaq           | 140      | 1.09%   |
| ASUS P5K            | 139      | 1.08%   |
| Dell OptiPlex       | 137      | 1.06%   |
| ASUS P8Z77-V        | 131      | 1.02%   |
| ASUS P5G41T-M       | 118      | 0.92%   |
| ASUS P5Q            | 106      | 0.82%   |
| Acer Aspire         | 105      | 0.82%   |
| MSI MS-7817         | 75       | 0.58%   |
| Lenovo ThinkCentre  | 68       | 0.53%   |
| ASUS SABERTOOTH     | 68       | 0.53%   |
| ASRock G31M-S       | 66       | 0.51%   |
| Gigabyte 970A-DS3P  | 63       | 0.49%   |
| ASRock N68C-S       | 62       | 0.48%   |
| MSI MS-7529         | 56       | 0.44%   |
| ASUS P5B            | 56       | 0.44%   |
| Gigabyte H61M-S1    | 55       | 0.43%   |
| Gigabyte G31M-ES2L  | 55       | 0.43%   |
| ASUS P5GC-MX        | 55       | 0.43%   |
| MSI MS-7592         | 53       | 0.41%   |
| ASUS P8B75-M        | 47       | 0.37%   |
| ASRock 970          | 47       | 0.37%   |
| MSI MS-7309         | 46       | 0.36%   |
| ASUS P8H61-MX       | 46       | 0.36%   |
| MSI MS-7788         | 45       | 0.35%   |
| ASUS P8H77-V        | 45       | 0.35%   |
| ASUS M2N-MX         | 43       | 0.33%   |
| ASUS M5A78L         | 42       | 0.33%   |
| ASRock G41M-VS3     | 41       | 0.32%   |
| MSI MS-7721         | 40       | 0.31%   |
| MSI MS-7693         | 40       | 0.31%   |
| ASUS P7H55-M        | 40       | 0.31%   |
| ASUS H110M-R        | 40       | 0.31%   |
| Gigabyte G41M-Combo | 39       | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2012    | 1856     | 14.43%  |
| 2009    | 1412     | 10.98%  |
| 2011    | 1311     | 10.19%  |
| 2010    | 1253     | 9.74%   |
| 2008    | 1156     | 8.99%   |
| 2007    | 1138     | 8.85%   |
| 2013    | 1023     | 7.95%   |
| 2006    | 760      | 5.91%   |
| 2014    | 552      | 4.29%   |
| 2016    | 394      | 3.06%   |
| 2018    | 380      | 2.95%   |
| 2015    | 354      | 2.75%   |
| 2005    | 333      | 2.59%   |
| 2017    | 254      | 1.97%   |
| 2019    | 185      | 1.44%   |
| 2004    | 126      | 0.98%   |
| 2020    | 118      | 0.92%   |
| 2021    | 112      | 0.87%   |
| 2003    | 76       | 0.59%   |
| Unknown | 32       | 0.25%   |
| 2022    | 22       | 0.17%   |
| 2002    | 13       | 0.1%    |
| 2001    | 4        | 0.03%   |
| 2000    | 1        | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 12865    | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 12865    | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 12864    | 99.99%  |
| Yes  | 1        | 0.01%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 3.01-4.0    | 4207     | 30.83%  |
| 8.01-16.0   | 2939     | 21.54%  |
| 4.01-8.0    | 1799     | 13.18%  |
| 1.01-2.0    | 1479     | 10.84%  |
| 16.01-24.0  | 1223     | 8.96%   |
| 2.01-3.0    | 1178     | 8.63%   |
| 0.51-1.0    | 289      | 2.12%   |
| 32.01-64.0  | 258      | 1.89%   |
| Unknown     | 153      | 1.12%   |
| 24.01-32.0  | 73       | 0.53%   |
| 64.01-256.0 | 30       | 0.22%   |
| 0.01-0.5    | 18       | 0.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.51-1.0   | 6866     | 46.04%  |
| 1.01-2.0   | 5790     | 38.83%  |
| 2.01-3.0   | 1064     | 7.14%   |
| 0.01-0.5   | 528      | 3.54%   |
| 3.01-4.0   | 261      | 1.75%   |
| 4.01-8.0   | 200      | 1.34%   |
| Unknown    | 178      | 1.19%   |
| 8.01-16.0  | 22       | 0.15%   |
| 16.01-24.0 | 3        | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 7190     | 52.01%  |
| 2       | 3852     | 27.87%  |
| 3       | 1744     | 12.62%  |
| 4       | 596      | 4.31%   |
| 5       | 219      | 1.58%   |
| 0       | 107      | 0.77%   |
| 6       | 78       | 0.56%   |
| 7       | 18       | 0.13%   |
| 8       | 10       | 0.07%   |
| 9       | 5        | 0.04%   |
| Unknown | 4        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 8721     | 65.56%  |
| No        | 4582     | 34.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 12729    | 98.94%  |
| No        | 137      | 1.06%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 10038    | 76.38%  |
| Yes       | 3105     | 23.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 11833    | 90.74%  |
| Yes       | 1208     | 9.26%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| Russia      | 7396     | 54.52%  |
| Unknown     | 4036     | 29.75%  |
| Ukraine     | 540      | 3.98%   |
| Belarus     | 168      | 1.24%   |
| Germany     | 158      | 1.16%   |
| Poland      | 146      | 1.08%   |
| Kazakhstan  | 123      | 0.91%   |
| France      | 92       | 0.68%   |
| Italy       | 91       | 0.67%   |
| USA         | 87       | 0.64%   |
| Brazil      | 72       | 0.53%   |
| Spain       | 47       | 0.35%   |
| Moldova     | 42       | 0.31%   |
| UK          | 39       | 0.29%   |
| Canada      | 38       | 0.28%   |
| Romania     | 31       | 0.23%   |
| Mexico      | 27       | 0.2%    |
| Austria     | 23       | 0.17%   |
| Israel      | 20       | 0.15%   |
| Bulgaria    | 20       | 0.15%   |
| Serbia      | 18       | 0.13%   |
| Latvia      | 18       | 0.13%   |
| Netherlands | 17       | 0.13%   |
| Czechia     | 17       | 0.13%   |
| Estonia     | 16       | 0.12%   |
| Slovakia    | 15       | 0.11%   |
| Australia   | 14       | 0.1%    |
| Lithuania   | 13       | 0.1%    |
| Argentina   | 13       | 0.1%    |
| Sweden      | 12       | 0.09%   |
| Venezuela   | 10       | 0.07%   |
| Switzerland | 10       | 0.07%   |
| Kyrgyzstan  | 10       | 0.07%   |
| Greece      | 10       | 0.07%   |
| Finland     | 10       | 0.07%   |
| Uzbekistan  | 9        | 0.07%   |
| Colombia    | 9        | 0.07%   |
| Belgium     | 9        | 0.07%   |
| Turkey      | 8        | 0.06%   |
| Portugal    | 8        | 0.06%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Unknown          | 4036     | 27.99%  |
| Moscow           | 1079     | 7.48%   |
| St Petersburg    | 436      | 3.02%   |
| Pecherskoye      | 416      | 2.89%   |
| Novosibirsk      | 270      | 1.87%   |
| Krasnodar        | 199      | 1.38%   |
| Yekaterinburg    | 196      | 1.36%   |
| Samara           | 193      | 1.34%   |
| Nizhniy Novgorod | 174      | 1.21%   |
| Rostov-on-Don    | 166      | 1.15%   |
| Chelyabinsk      | 136      | 0.94%   |
| Perm             | 133      | 0.92%   |
| Voronezh         | 122      | 0.85%   |
| Krasnoyarsk      | 114      | 0.79%   |
| Saratov          | 113      | 0.78%   |
| Omsk             | 97       | 0.67%   |
| Volgograd        | 88       | 0.61%   |
| Stavropol        | 79       | 0.55%   |
| Kazan’         | 79       | 0.55%   |
| Barnaul          | 76       | 0.53%   |
| Tyumen           | 73       | 0.51%   |
| Vladivostok      | 71       | 0.49%   |
| Khabarovsk       | 69       | 0.48%   |
| Orenburg         | 64       | 0.44%   |
| Ufa              | 58       | 0.4%    |
| Minsk            | 58       | 0.4%    |
| Bryansk          | 57       | 0.4%    |
| Kemerovo         | 56       | 0.39%   |
| Irkutsk          | 56       | 0.39%   |
| Lipetsk          | 55       | 0.38%   |
| Yaroslavl        | 54       | 0.37%   |
| Tula             | 54       | 0.37%   |
| Novokuznetsk     | 54       | 0.37%   |
| Tomsk            | 50       | 0.35%   |
| Kyiv             | 50       | 0.35%   |
| Belgorod         | 50       | 0.35%   |
| Ulyanovsk        | 48       | 0.33%   |
| Tolyatti         | 47       | 0.33%   |
| Astrakhan        | 47       | 0.33%   |
| Izhevsk          | 46       | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives  | Percent |
|---------------------|----------|---------|---------|
| Seagate             | 5809     | 9671    | 28.65%  |
| WDC                 | 5302     | 9010    | 26.15%  |
| Samsung Electronics | 1867     | 2874    | 9.21%   |
| Hitachi             | 1382     | 1971    | 6.82%   |
| Toshiba             | 1128     | 1687    | 5.56%   |
| Kingston            | 806      | 1160    | 3.98%   |
| Maxtor              | 468      | 602     | 2.31%   |
| OCZ                 | 269      | 358     | 1.33%   |
| SPCC                | 250      | 348     | 1.23%   |
| A-DATA Technology   | 247      | 369     | 1.22%   |
| SanDisk             | 216      | 319     | 1.07%   |
| China               | 211      | 290     | 1.04%   |
| Plextor             | 181      | 284     | 0.89%   |
| Crucial             | 176      | 266     | 0.87%   |
| Intel               | 174      | 303     | 0.86%   |
| HUAWEI              | 150      | 179     | 0.74%   |
| HGST                | 150      | 216     | 0.74%   |
| Apacer              | 100      | 145     | 0.49%   |
| Corsair             | 89       | 115     | 0.44%   |
| Smartbuy            | 88       | 119     | 0.43%   |
| Transcend           | 77       | 107     | 0.38%   |
| GOODRAM             | 77       | 110     | 0.38%   |
| Patriot             | 69       | 88      | 0.34%   |
| AMD                 | 69       | 87      | 0.34%   |
| KingSpec            | 52       | 63      | 0.26%   |
| Fujitsu             | 52       | 60      | 0.26%   |
| Unknown             | 45       | 81      | 0.22%   |
| KingDian            | 37       | 56      | 0.18%   |
| Gigabyte Technology | 37       | 50      | 0.18%   |
| TF CARD             | 34       | 41      | 0.17%   |
| Silicon Motion      | 32       | 39      | 0.16%   |
| Kingmax             | 32       | 65      | 0.16%   |
| ZTE                 | 31       | 35      | 0.15%   |
| Netac               | 27       | 34      | 0.13%   |
| XPG                 | 26       | 31      | 0.13%   |
| XrayDisk            | 19       | 25      | 0.09%   |
| JMicron Technology  | 19       | 22      | 0.09%   |
| IBM/Hitachi         | 19       | 24      | 0.09%   |
| Team                | 18       | 23      | 0.09%   |
| Mass                | 18       | Unknown | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 468      | 2.01%   |
| Seagate ST3500418AS 500GB        | 334      | 1.43%   |
| Toshiba DT01ACA050 500GB         | 278      | 1.19%   |
| Seagate ST1000DM003-1CH162 1TB   | 270      | 1.16%   |
| Toshiba DT01ACA100 1TB           | 234      | 1%      |
| Seagate ST3250410AS 250GB        | 189      | 0.81%   |
| WDC WD5000AAKX-001CA0 500GB      | 180      | 0.77%   |
| Seagate ST380011A 80GB           | 180      | 0.77%   |
| Kingston SV300S37A120G 120GB SSD | 179      | 0.77%   |
| Seagate ST3160815AS 160GB        | 176      | 0.76%   |
| Seagate ST1000DM010-2EP102 1TB   | 166      | 0.71%   |
| Seagate ST3250310AS 250GB        | 161      | 0.69%   |
| Toshiba HDWD110 1TB              | 157      | 0.67%   |
| Seagate ST31000528AS 1TB         | 157      | 0.67%   |
| Seagate ST31000524AS 1TB         | 154      | 0.66%   |
| Seagate ST380815AS 80GB          | 153      | 0.66%   |
| Seagate ST1000DM003-1ER162 1TB   | 139      | 0.6%    |
| WDC WD10EZEX-08WN4A0 1TB         | 137      | 0.59%   |
| Hitachi HDS721050CLA362 500GB    | 131      | 0.56%   |
| Kingston SA400S37120G 120GB SSD  | 117      | 0.5%    |
| Seagate ST3500413AS 500GB        | 115      | 0.49%   |
| WDC WD5000AADS-00S9B0 500GB      | 113      | 0.48%   |
| Seagate ST3320620AS 320GB        | 110      | 0.47%   |
| Seagate ST3320613AS 320GB        | 105      | 0.45%   |
| Samsung HD080HJ 80GB             | 104      | 0.45%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 103      | 0.44%   |
| Seagate ST1000DM003-9YN162 1TB   | 103      | 0.44%   |
| Hitachi HDS721010CLA332 1TB      | 102      | 0.44%   |
| Seagate ST3250318AS 249GB        | 98       | 0.42%   |
| Seagate ST2000DM001-1CH164 2TB   | 97       | 0.42%   |
| WDC WD10EZEX-00BN5A0 1TB         | 96       | 0.41%   |
| Hitachi HDS721616PLA380 160GB    | 96       | 0.41%   |
| Seagate ST3160811AS 160GB        | 95       | 0.41%   |
| Seagate ST340014A 40GB           | 94       | 0.4%    |
| Seagate ST250DM000-1BD141 250GB  | 94       | 0.4%    |
| Seagate ST3320418AS 320GB        | 91       | 0.39%   |
| WDC WD10EARS-00Y5B1 1TB          | 88       | 0.38%   |
| Samsung HD502HJ 500GB            | 85       | 0.36%   |
| Kingston SA400S37240G 240GB SSD  | 81       | 0.35%   |
| HUAWEI SD Storage 8GB            | 81       | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 5798     | 9643   | 37.28%  |
| WDC                 | 5155     | 8645   | 33.15%  |
| Hitachi             | 1382     | 1971   | 8.89%   |
| Samsung Electronics | 1346     | 1979   | 8.66%   |
| Toshiba             | 1089     | 1612   | 7%      |
| Maxtor              | 466      | 600    | 3%      |
| HGST                | 150      | 216    | 0.96%   |
| Fujitsu             | 51       | 59     | 0.33%   |
| IBM/Hitachi         | 19       | 24     | 0.12%   |
| Unknown             | 14       | 20     | 0.09%   |
| ExcelStor           | 12       | 19     | 0.08%   |
| Hewlett-Packard     | 10       | 13     | 0.06%   |
| Apple               | 8        | 8      | 0.05%   |
| WD MediaMax         | 7        | 10     | 0.05%   |
| ASMT                | 6        | 17     | 0.04%   |
| Quantum             | 5        | 5      | 0.03%   |
| IBM                 | 5        | 7      | 0.03%   |
| USB3.0              | 4        | 4      | 0.03%   |
| Magnetic Data       | 3        | 3      | 0.02%   |
| ASMedia             | 2        | 8      | 0.01%   |
| Unknown             | 2        | 2      | 0.01%   |
| USB 3.0             | 1        | 1      | 0.01%   |
| USB                 | 1        | 1      | 0.01%   |
| TPH01204000GB       | 1        | 1      | 0.01%   |
| TPH00100500GB       | 1        | 1      | 0.01%   |
| Speeding            | 1        | 1      | 0.01%   |
| Silicon             | 1        | 1      | 0.01%   |
| SAGE                | 1        | 1      | 0.01%   |
| PHD 3.0             | 1        | 1      | 0.01%   |
| MR2020              | 1        | 1      | 0.01%   |
| Lexar               | 1        | 1      | 0.01%   |
| Intenso             | 1        | 1      | 0.01%   |
| HGST HTS            | 1        | 1      | 0.01%   |
| FC-1307             | 1        | 1      | 0.01%   |
| External            | 1        | 1      | 0.01%   |
| Ext Hard            | 1        | 1      | 0.01%   |
| CLOVER              | 1        | 1      | 0.01%   |
| China               | 1        | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 760      | 1095   | 18.24%  |
| Samsung Electronics | 442      | 723    | 10.61%  |
| OCZ                 | 268      | 357    | 6.43%   |
| SPCC                | 245      | 341    | 5.88%   |
| WDC                 | 236      | 325    | 5.66%   |
| A-DATA Technology   | 214      | 301    | 5.14%   |
| SanDisk             | 211      | 314    | 5.06%   |
| China               | 210      | 289    | 5.04%   |
| Plextor             | 172      | 268    | 4.13%   |
| Crucial             | 170      | 253    | 4.08%   |
| Intel               | 154      | 268    | 3.7%    |
| Apacer              | 96       | 137    | 2.3%    |
| Corsair             | 88       | 113    | 2.11%   |
| Smartbuy            | 85       | 115    | 2.04%   |
| GOODRAM             | 74       | 107    | 1.78%   |
| Transcend           | 71       | 96     | 1.7%    |
| Patriot             | 64       | 83     | 1.54%   |
| AMD                 | 63       | 77     | 1.51%   |
| KingSpec            | 52       | 63     | 1.25%   |
| Toshiba             | 41       | 68     | 0.98%   |
| KingDian            | 37       | 56     | 0.89%   |
| Kingmax             | 32       | 65     | 0.77%   |
| Gigabyte Technology | 30       | 37     | 0.72%   |
| Netac               | 19       | 24     | 0.46%   |
| XrayDisk            | 16       | 22     | 0.38%   |
| Team                | 16       | 20     | 0.38%   |
| OCZ-VERTEX3         | 16       | 25     | 0.38%   |
| JMicron Technology  | 16       | 18     | 0.38%   |
| Foxline             | 15       | 19     | 0.36%   |
| Intenso             | 13       | 17     | 0.31%   |
| KingFast            | 12       | 18     | 0.29%   |
| Unknown             | 12       | 13     | 0.29%   |
| PNY                 | 11       | 12     | 0.26%   |
| Qumo                | 10       | 13     | 0.24%   |
| Micron Technology   | 9        | 10     | 0.22%   |
| Zheino              | 8        | 10     | 0.19%   |
| Palit               | 8        | 11     | 0.19%   |
| OCZ-VERTEX          | 7        | 12     | 0.17%   |
| Londisk             | 7        | 7      | 0.17%   |
| e2e4                | 7        | 11     | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 11797    | 24882  | 73.31%  |
| SSD     | 3581     | 6035   | 22.25%  |
| NVMe    | 438      | 645    | 2.72%   |
| Unknown | 263      | 316    | 1.63%   |
| MMC     | 14       | 19     | 0.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 12693    | 30681  | 93.5%   |
| SAS  | 434      | 558    | 3.2%    |
| NVMe | 434      | 639    | 3.2%    |
| MMC  | 14       | 19     | 0.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 10956    | 21715  | 67.04%  |
| 0.51-1.0        | 4123     | 7123   | 25.23%  |
| 1.01-2.0        | 919      | 1529   | 5.62%   |
| 2.01-3.0        | 191      | 293    | 1.17%   |
| 3.01-4.0        | 109      | 183    | 0.67%   |
| 4.01-10.0       | 39       | 68     | 0.24%   |
| 10.01-20.0      | 4        | 5      | 0.02%   |
| More than 100.0 | 1        | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 3678     | 24.45%  |
| 251-500        | 2781     | 18.49%  |
| 1-20           | 1961     | 13.04%  |
| 51-100         | 1890     | 12.57%  |
| 501-1000       | 1851     | 12.31%  |
| 21-50          | 1221     | 8.12%   |
| 1001-2000      | 995      | 6.62%   |
| 2001-3000      | 284      | 1.89%   |
| More than 3000 | 198      | 1.32%   |
| Unknown        | 181      | 1.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 9233     | 62.04%  |
| 21-50          | 1346     | 9.04%   |
| 101-250        | 1152     | 7.74%   |
| 251-500        | 907      | 6.09%   |
| 51-100         | 890      | 5.98%   |
| 501-1000       | 699      | 4.7%    |
| 1001-2000      | 330      | 2.22%   |
| Unknown        | 181      | 1.22%   |
| 2001-3000      | 77       | 0.52%   |
| More than 3000 | 68       | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 187      | 246    | 2.42%   |
| Seagate ST3500418AS 500GB         | 168      | 230    | 2.17%   |
| Seagate ST3250410AS 250GB         | 120      | 154    | 1.55%   |
| Seagate ST3250310AS 250GB         | 106      | 160    | 1.37%   |
| WDC WD5000AAKX-001CA0 500GB       | 98       | 122    | 1.27%   |
| Seagate ST3320613AS 320GB         | 82       | 111    | 1.06%   |
| Seagate ST31000528AS 1TB          | 78       | 103    | 1.01%   |
| Seagate ST3160815AS 160GB         | 70       | 83     | 0.91%   |
| WDC WD5000AADS-00S9B0 500GB       | 65       | 78     | 0.84%   |
| Seagate ST380011A 80GB            | 65       | 74     | 0.84%   |
| Samsung Electronics HD080HJ 80GB  | 65       | 80     | 0.84%   |
| Seagate ST3160811AS 160GB         | 64       | 90     | 0.83%   |
| Seagate ST31000524AS 1TB          | 58       | 85     | 0.75%   |
| Hitachi HDS721616PLA380 160GB     | 58       | 76     | 0.75%   |
| Seagate ST1000DM003-1CH162 1TB    | 57       | 84     | 0.74%   |
| Samsung Electronics HD160JJ 160GB | 55       | 85     | 0.71%   |
| Seagate ST1000DM003-9YN162 1TB    | 54       | 65     | 0.7%    |
| Seagate ST3250318AS 249GB         | 53       | 70     | 0.69%   |
| Hitachi HDS721050CLA362 500GB     | 53       | 67     | 0.69%   |
| Hitachi HDP725050GLA360 500GB     | 53       | 71     | 0.69%   |
| WDC WD3200AAJS-00L7A0 320GB       | 50       | 59     | 0.65%   |
| Seagate ST3320620AS 320GB         | 50       | 67     | 0.65%   |
| Seagate ST31500341AS 1TB          | 50       | 71     | 0.65%   |
| Hitachi HDS721010CLA332 1TB       | 50       | 62     | 0.65%   |
| WDC WD10EARS-00Y5B1 1TB           | 49       | 81     | 0.63%   |
| Seagate ST380815AS 80GB           | 48       | 61     | 0.62%   |
| Samsung Electronics HD321KJ 320GB | 45       | 54     | 0.58%   |
| Seagate ST3500413AS 500GB         | 44       | 48     | 0.57%   |
| Seagate ST3500320AS 500GB         | 44       | 58     | 0.57%   |
| Samsung Electronics HD161HJ 160GB | 42       | 52     | 0.54%   |
| Seagate ST3320418AS 320GB         | 40       | 50     | 0.52%   |
| Seagate ST250DM000-1BD141 250GB   | 39       | 54     | 0.5%    |
| Maxtor STM3250310AS 250GB         | 39       | 52     | 0.5%    |
| WDC WD5000AAKX-00ERMA0 500GB      | 37       | 52     | 0.48%   |
| WDC WD5000AAKS-00V1A0 500GB       | 37       | 46     | 0.48%   |
| WDC WD5000AAKS-00UU3A0 500GB      | 36       | 42     | 0.47%   |
| Toshiba DT01ACA050 500GB          | 34       | 49     | 0.44%   |
| Samsung Electronics SP2504C 250GB | 33       | 56     | 0.43%   |
| Samsung Electronics SP0802N 80GB  | 33       | 39     | 0.43%   |
| Kingston SV300S37A120G 120GB SSD  | 33       | 38     | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2630     | 3830   | 36.51%  |
| WDC                 | 2080     | 2953   | 28.88%  |
| Samsung Electronics | 740      | 1019   | 10.27%  |
| Hitachi             | 707      | 970    | 9.82%   |
| Maxtor              | 279      | 345    | 3.87%   |
| Toshiba             | 192      | 256    | 2.67%   |
| Kingston            | 108      | 135    | 1.5%    |
| SPCC                | 49       | 66     | 0.68%   |
| OCZ                 | 48       | 65     | 0.67%   |
| Intel               | 38       | 44     | 0.53%   |
| HGST                | 36       | 45     | 0.5%    |
| SanDisk             | 32       | 41     | 0.44%   |
| A-DATA Technology   | 32       | 46     | 0.44%   |
| Corsair             | 29       | 39     | 0.4%    |
| Kingmax             | 25       | 51     | 0.35%   |
| Fujitsu             | 24       | 28     | 0.33%   |
| IBM/Hitachi         | 16       | 21     | 0.22%   |
| Crucial             | 16       | 30     | 0.22%   |
| Plextor             | 10       | 15     | 0.14%   |
| KingSpec            | 9        | 10     | 0.12%   |
| ExcelStor           | 8        | 10     | 0.11%   |
| China               | 8        | 11     | 0.11%   |
| AMD                 | 8        | 10     | 0.11%   |
| OCZ-VERTEX3         | 6        | 12     | 0.08%   |
| IBM                 | 5        | 7      | 0.07%   |
| WD MediaMax         | 3        | 5      | 0.04%   |
| Transcend           | 3        | 3      | 0.04%   |
| Smartbuy            | 3        | 3      | 0.04%   |
| Qumo                | 3        | 5      | 0.04%   |
| Patriot             | 3        | 3      | 0.04%   |
| Netac               | 3        | 3      | 0.04%   |
| LITEONIT            | 3        | 3      | 0.04%   |
| Intenso             | 3        | 4      | 0.04%   |
| Hewlett-Packard     | 3        | 4      | 0.04%   |
| Unknown             | 3        | 4      | 0.04%   |
| XPG                 | 2        | 3      | 0.03%   |
| Silicon Motion      | 2        | 3      | 0.03%   |
| Quantum             | 2        | 2      | 0.03%   |
| Neo                 | 2        | 2      | 0.03%   |
| Mushkin             | 2        | 2      | 0.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2630     | 3830   | 39.28%  |
| WDC                 | 2064     | 2918   | 30.82%  |
| Samsung Electronics | 722      | 996    | 10.78%  |
| Hitachi             | 707      | 970    | 10.56%  |
| Maxtor              | 279      | 345    | 4.17%   |
| Toshiba             | 192      | 256    | 2.87%   |
| HGST                | 36       | 45     | 0.54%   |
| Fujitsu             | 24       | 28     | 0.36%   |
| IBM/Hitachi         | 16       | 21     | 0.24%   |
| ExcelStor           | 8        | 10     | 0.12%   |
| IBM                 | 5        | 7      | 0.07%   |
| WD MediaMax         | 3        | 5      | 0.04%   |
| Hewlett-Packard     | 3        | 4      | 0.04%   |
| Quantum             | 2        | 2      | 0.03%   |
| TPH00100500GB       | 1        | 1      | 0.01%   |
| Magnetic Data       | 1        | 1      | 0.01%   |
| ASMT                | 1        | 2      | 0.01%   |
| Apple               | 1        | 1      | 0.01%   |
| Unknown             | 1        | 1      | 0.01%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 5838     | 9443   | 92.05%  |
| SSD  | 491      | 686    | 7.74%   |
| NVMe | 13       | 18     | 0.2%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB         | 13       | 14     | 5%      |
| Seagate ST31000528AS 1TB          | 12       | 14     | 4.62%   |
| Seagate ST31000524AS 1TB          | 7        | 8      | 2.69%   |
| Seagate ST3500412AS 500GB         | 6        | 8      | 2.31%   |
| Hitachi HDS721010DLE630 1TB       | 6        | 8      | 2.31%   |
| Samsung Electronics HD502HJ 500GB | 5        | 5      | 1.92%   |
| Seagate ST3500410AS 500GB         | 4        | 5      | 1.54%   |
| Seagate ST31000333AS 1TB          | 4        | 4      | 1.54%   |
| Samsung Electronics SP0411N 40GB  | 4        | 5      | 1.54%   |
| Samsung Electronics HD502IJ 500GB | 4        | 4      | 1.54%   |
| Samsung Electronics HD322GJ 320GB | 4        | 5      | 1.54%   |
| HGST HTS545050A7E380 500GB        | 4        | 4      | 1.54%   |
| WDC WD5000AAKS-00V1A0 500GB       | 3        | 4      | 1.15%   |
| WDC WD3200AAJS-00L7A0 320GB       | 3        | 4      | 1.15%   |
| WDC WD15EARS-00MVWB0 1TB          | 3        | 6      | 1.15%   |
| Seagate ST3750528AS 752GB         | 3        | 3      | 1.15%   |
| Seagate ST32000542AS 2TB          | 3        | 5      | 1.15%   |
| Maxtor 6Y080L0 81GB               | 3        | 3      | 1.15%   |
| Hitachi HDS721050DLE630 500GB     | 3        | 3      | 1.15%   |
| WDC WD7501AALS-00J7B0 752GB       | 2        | 2      | 0.77%   |
| WDC WD2500JS-22NCB1 250GB         | 2        | 3      | 0.77%   |
| Toshiba DT01ACA050 500GB          | 2        | 2      | 0.77%   |
| Seagate STM3500418AS 500GB        | 2        | 2      | 0.77%   |
| Seagate ST9320325AS 320GB         | 2        | 3      | 0.77%   |
| Seagate ST9250315AS 250GB         | 2        | 2      | 0.77%   |
| Seagate ST500DM002-1BD142 500GB   | 2        | 2      | 0.77%   |
| Seagate ST3640323AS 640GB         | 2        | 2      | 0.77%   |
| Seagate ST3320613AS 320GB         | 2        | 3      | 0.77%   |
| Seagate ST3250318AS 249GB         | 2        | 6      | 0.77%   |
| Seagate ST3160318AS 160GB         | 2        | 2      | 0.77%   |
| Seagate ST31500341AS 1TB          | 2        | 3      | 0.77%   |
| Samsung Electronics HM321HI 320GB | 2        | 3      | 0.77%   |
| Samsung Electronics HM250HI 250GB | 2        | 2      | 0.77%   |
| Samsung Electronics HD503HI 500GB | 2        | 2      | 0.77%   |
| Samsung Electronics HD252HJ 250GB | 2        | 6      | 0.77%   |
| Samsung Electronics HD251HJ 249GB | 2        | 2      | 0.77%   |
| Samsung Electronics HD204UI 2TB   | 2        | 2      | 0.77%   |
| Samsung Electronics HD105SI 1TB   | 2        | 2      | 0.77%   |
| Hitachi HDT721032SLA380 320GB     | 2        | 2      | 0.77%   |
| Hitachi HDS721025CLA382 250GB     | 2        | 2      | 0.77%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 94       | 114    | 36.29%  |
| WDC                 | 66       | 81     | 25.48%  |
| Samsung Electronics | 46       | 54     | 17.76%  |
| Hitachi             | 24       | 27     | 9.27%   |
| Toshiba             | 10       | 10     | 3.86%   |
| Maxtor              | 9        | 9      | 3.47%   |
| HGST                | 7        | 7      | 2.7%    |
| Hewlett-Packard     | 1        | 1      | 0.39%   |
| Corsair             | 1        | 1      | 0.39%   |
| Apple               | 1        | 1      | 0.39%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 9501     | 20378  | 57.16%  |
| Malfunc  | 6157     | 10147  | 37.04%  |
| Detected | 708      | 1067   | 4.26%   |
| Failed   | 256      | 305    | 1.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 8238     | 52.78%  |
| AMD                              | 3112     | 19.94%  |
| Nvidia                           | 1296     | 8.3%    |
| JMicron Technology               | 1045     | 6.7%    |
| Marvell Technology Group         | 586      | 3.75%   |
| ASMedia Technology               | 358      | 2.29%   |
| VIA Technologies                 | 296      | 1.9%    |
| Samsung Electronics              | 127      | 0.81%   |
| Silicon Motion                   | 75       | 0.48%   |
| Silicon Integrated Systems [SiS] | 71       | 0.45%   |
| Kingston Technology Company      | 54       | 0.35%   |
| Silicon Image                    | 51       | 0.33%   |
| Integrated Technology Express    | 42       | 0.27%   |
| ADATA Technology                 | 38       | 0.24%   |
| Phison Electronics               | 37       | 0.24%   |
| SanDisk                          | 32       | 0.21%   |
| Realtek Semiconductor            | 24       | 0.15%   |
| Lite-On Technology               | 17       | 0.11%   |
| ULi Electronics                  | 15       | 0.1%    |
| LSI Logic / Symbios Logic        | 13       | 0.08%   |
| Micron/Crucial Technology        | 10       | 0.06%   |
| Adaptec                          | 9        | 0.06%   |
| SK hynix                         | 7        | 0.04%   |
| Promise Technology               | 7        | 0.04%   |
| OCZ Technology Group             | 7        | 0.04%   |
| Lite-On IT Corp. / Plextor       | 6        | 0.04%   |
| Netac Technology                 | 5        | 0.03%   |
| MAXIO Technology (Hangzhou)      | 5        | 0.03%   |
| KIOXIA                           | 4        | 0.03%   |
| Toshiba America Info Systems     | 3        | 0.02%   |
| Hewlett-Packard                  | 3        | 0.02%   |
| ATI Technologies                 | 3        | 0.02%   |
| Union Memory (Shenzhen)          | 2        | 0.01%   |
| Seagate Technology               | 2        | 0.01%   |
| Artop Electronic                 | 2        | 0.01%   |
| Transcend                        | 1        | 0.01%   |
| Tekram Technology                | 1        | 0.01%   |
| Shenzhen Longsys Electronics     | 1        | 0.01%   |
| MCST                             | 1        | 0.01%   |
| INNOGRIT                         | 1        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1945     | 8.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1498     | 6.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1455     | 6.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1087     | 4.62%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 853      | 3.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 772      | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 722      | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 699      | 2.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 697      | 2.96%   |
| Nvidia MCP61 SATA Controller                                                            | 661      | 2.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 624      | 2.65%   |
| Nvidia MCP61 IDE                                                                        | 617      | 2.62%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 532      | 2.26%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 523      | 2.22%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 419      | 1.78%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 419      | 1.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 401      | 1.7%    |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 396      | 1.68%   |
| JMicron JMB368 IDE controller                                                           | 373      | 1.59%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 342      | 1.45%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 246      | 1.05%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 243      | 1.03%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 232      | 0.99%   |
| AMD FCH IDE Controller                                                                  | 229      | 0.97%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 228      | 0.97%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 228      | 0.97%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 203      | 0.86%   |
| AMD 400 Series Chipset SATA Controller                                                  | 189      | 0.8%    |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 177      | 0.75%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 173      | 0.74%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 165      | 0.7%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 164      | 0.7%    |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 159      | 0.68%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 159      | 0.68%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 152      | 0.65%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 150      | 0.64%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 145      | 0.62%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 134      | 0.57%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 134      | 0.57%   |
| AMD SB600 IDE                                                                           | 134      | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| IDE  | 8218     | 51.25%  |
| SATA | 6975     | 43.5%   |
| NVMe | 438      | 2.73%   |
| RAID | 371      | 2.31%   |
| SCSI | 21       | 0.13%   |
| SAS  | 12       | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Desktops | Percent |
|----------|----------|---------|
| Intel    | 8501     | 66.07%  |
| AMD      | 4364     | 33.92%  |
| MBE8C-PC | 1        | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 239      | 1.83%   |
| Intel Pentium 4 CPU 3.00GHz                 | 200      | 1.53%   |
| AMD Athlon II X2 250 Processor              | 150      | 1.15%   |
| AMD FX-6300 Six-Core Processor              | 145      | 1.11%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 132      | 1.01%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 128      | 0.98%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 127      | 0.97%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 119      | 0.91%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 116      | 0.89%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 114      | 0.87%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 107      | 0.82%   |
| AMD FX-8350 Eight-Core Processor            | 105      | 0.81%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 104      | 0.8%    |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 103      | 0.79%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 99       | 0.76%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 88       | 0.68%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+  | 85       | 0.65%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 83       | 0.64%   |
| AMD FX-8320 Eight-Core Processor            | 81       | 0.62%   |
| AMD FX-4300 Quad-Core Processor             | 79       | 0.61%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 78       | 0.6%    |
| AMD Athlon II X2 240 Processor              | 78       | 0.6%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 77       | 0.59%   |
| AMD Athlon 64 X2 Dual Core Processor 6000+  | 76       | 0.58%   |
| Intel Core i3 CPU 540 @ 3.07GHz             | 73       | 0.56%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 71       | 0.54%   |
| Intel Pentium Dual CPU E2200 @ 2.20GHz      | 70       | 0.54%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 70       | 0.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 69       | 0.53%   |
| AMD Phenom II X4 955 Processor              | 68       | 0.52%   |
| AMD Athlon 64 X2 Dual Core Processor 5200+  | 68       | 0.52%   |
| AMD Athlon 64 X2 Dual Core Processor 5600+  | 67       | 0.51%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 66       | 0.51%   |
| AMD Athlon 64 X2 Dual Core Processor 3800+  | 66       | 0.51%   |
| AMD Phenom II X4 965 Processor              | 65       | 0.5%    |
| AMD Athlon II X4 640 Processor              | 65       | 0.5%    |
| AMD Athlon II X2 245 Processor              | 64       | 0.49%   |
| AMD Athlon 64 X2 Dual Core Processor 5000+  | 64       | 0.49%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 63       | 0.48%   |
| AMD Athlon 64 X2 Dual Core Processor 4400+  | 63       | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 1545     | 11.89%  |
| Intel Core 2 Duo        | 1058     | 8.15%   |
| Intel Core i3           | 1055     | 8.12%   |
| Intel Celeron           | 821      | 6.32%   |
| AMD FX                  | 733      | 5.64%   |
| AMD Athlon 64 X2        | 679      | 5.23%   |
| Intel Pentium           | 678      | 5.22%   |
| Intel Core i7           | 652      | 5.02%   |
| Intel Pentium Dual-Core | 527      | 4.06%   |
| AMD Athlon II X2        | 507      | 3.9%    |
| Intel Core 2 Quad       | 467      | 3.6%    |
| Intel Pentium 4         | 455      | 3.5%    |
| Intel Xeon              | 366      | 2.82%   |
| AMD Phenom II X4        | 315      | 2.43%   |
| Intel Pentium Dual      | 236      | 1.82%   |
| Intel Core 2            | 232      | 1.79%   |
| AMD Ryzen 5             | 221      | 1.7%    |
| AMD Athlon II X4        | 211      | 1.62%   |
| Intel Pentium D         | 171      | 1.32%   |
| AMD Athlon II X3        | 163      | 1.25%   |
| AMD Athlon 64           | 158      | 1.22%   |
| Intel Atom              | 156      | 1.2%    |
| AMD A4                  | 140      | 1.08%   |
| AMD A8                  | 126      | 0.97%   |
| AMD A10                 | 124      | 0.95%   |
| AMD Phenom              | 114      | 0.88%   |
| AMD Athlon X4           | 102      | 0.79%   |
| AMD Phenom II X6        | 96       | 0.74%   |
| AMD Sempron             | 95       | 0.73%   |
| AMD A6                  | 92       | 0.71%   |
| AMD Ryzen 3             | 89       | 0.69%   |
| AMD Ryzen 7             | 83       | 0.64%   |
| AMD Athlon              | 80       | 0.62%   |
| Other                   | 68       | 0.52%   |
| AMD Phenom II X2        | 59       | 0.45%   |
| Intel Pentium Gold      | 40       | 0.31%   |
| Intel Genuine           | 39       | 0.3%    |
| AMD Phenom II X3        | 24       | 0.18%   |
| AMD E                   | 24       | 0.18%   |
| Intel Celeron D         | 23       | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 6047     | 45.24%  |
| 4       | 3762     | 28.14%  |
| Unknown | 1264     | 9.46%   |
| 1       | 1063     | 7.95%   |
| 6       | 538      | 4.02%   |
| 3       | 406      | 3.04%   |
| 8       | 229      | 1.71%   |
| 12      | 30       | 0.22%   |
| 10      | 12       | 0.09%   |
| 16      | 7        | 0.05%   |
| 24      | 4        | 0.03%   |
| 18      | 2        | 0.01%   |
| 20      | 1        | 0.01%   |
| 14      | 1        | 0.01%   |
| 5       | 1        | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 12777    | 99.01%  |
| Unknown | 69       | 0.53%   |
| 2       | 58       | 0.45%   |
| 4       | 1        | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 8325     | 62.46%  |
| 2       | 3739     | 28.05%  |
| Unknown | 1264     | 9.48%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 12296    | 94.78%  |
| 32-bit         | 324      | 2.5%    |
| Unknown        | 259      | 2%      |
| 64-bit         | 94       | 0.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| 0x1067a    | 1367     | 10.32%  |
| Unknown    | 1167     | 8.81%   |
| 0x206a7    | 1119     | 8.45%   |
| 0x306a9    | 965      | 7.28%   |
| 0x306c3    | 904      | 6.82%   |
| 0x010000c8 | 704      | 5.31%   |
| 0x6fd      | 427      | 3.22%   |
| 0x10676    | 357      | 2.69%   |
| 0x6fb      | 347      | 2.62%   |
| 0x06001119 | 301      | 2.27%   |
| 0x506e3    | 293      | 2.21%   |
| 0x0600084f | 222      | 1.68%   |
| 0x906e9    | 213      | 1.61%   |
| 0x06000852 | 194      | 1.46%   |
| 0x010000db | 161      | 1.22%   |
| 0x106e5    | 144      | 1.09%   |
| 0x20655    | 143      | 1.08%   |
| 0x6f6      | 141      | 1.06%   |
| 0xf41      | 139      | 1.05%   |
| 0xf49      | 133      | 1%      |
| 0x906ea    | 130      | 0.98%   |
| 0x6f2      | 123      | 0.93%   |
| 0x010000b6 | 123      | 0.93%   |
| 0x06003106 | 120      | 0.91%   |
| 0x010000c7 | 117      | 0.88%   |
| 0xf65      | 108      | 0.82%   |
| 0x20652    | 105      | 0.79%   |
| 0x0600063d | 97       | 0.73%   |
| 0x03000027 | 93       | 0.7%    |
| 0x10677    | 92       | 0.69%   |
| 0x06000822 | 88       | 0.66%   |
| 0x0800820d | 82       | 0.62%   |
| 0x106ca    | 79       | 0.6%    |
| 0xf29      | 76       | 0.57%   |
| 0x010000dc | 76       | 0.57%   |
| 0xf43      | 68       | 0.51%   |
| 0x106a5    | 66       | 0.5%    |
| 0x01000086 | 63       | 0.48%   |
| 0x08701021 | 62       | 0.47%   |
| 0x10661    | 61       | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 1741     | 13.38%  |
| K10              | 1514     | 11.64%  |
| Core             | 1222     | 9.39%   |
| SandyBridge      | 1177     | 9.05%   |
| IvyBridge        | 1012     | 7.78%   |
| Haswell          | 965      | 7.42%   |
| K8 Hammer        | 904      | 6.95%   |
| Piledriver       | 841      | 6.46%   |
| NetBurst         | 802      | 6.16%   |
| KabyLake         | 421      | 3.24%   |
| Skylake          | 304      | 2.34%   |
| Westmere         | 275      | 2.11%   |
| Nehalem          | 218      | 1.68%   |
| Unknown          | 212      | 1.63%   |
| Bulldozer        | 191      | 1.47%   |
| Zen              | 186      | 1.43%   |
| Zen+             | 138      | 1.06%   |
| Steamroller      | 137      | 1.05%   |
| Bonnell          | 132      | 1.01%   |
| Silvermont       | 108      | 0.83%   |
| K10 Llano        | 106      | 0.81%   |
| Zen 2            | 85       | 0.65%   |
| CometLake        | 67       | 0.52%   |
| Zen 3            | 42       | 0.32%   |
| Excavator        | 40       | 0.31%   |
| Bobcat           | 34       | 0.26%   |
| Jaguar           | 32       | 0.25%   |
| K6               | 26       | 0.2%    |
| Goldmont plus    | 18       | 0.14%   |
| Goldmont         | 15       | 0.12%   |
| Broadwell        | 13       | 0.1%    |
| Icelake          | 12       | 0.09%   |
| Puma             | 7        | 0.05%   |
| Alderlake Hybrid | 4        | 0.03%   |
| Tremont          | 3        | 0.02%   |
| P6               | 3        | 0.02%   |
| K8 & K10 hybrid  | 2        | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Nvidia                           | 7009     | 51.63%  |
| AMD                              | 3700     | 27.25%  |
| Intel                            | 2816     | 20.74%  |
| VIA Technologies                 | 25       | 0.18%   |
| Silicon Integrated Systems [SiS] | 7        | 0.05%   |
| Matrox Electronics Systems       | 6        | 0.04%   |
| ATI Technologies                 | 6        | 0.04%   |
| S3 Graphics                      | 5        | 0.04%   |
| ASPEED Technology                | 2        | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 429      | 2.99%   |
| Nvidia GT218 [GeForce 210]                                                  | 372      | 2.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 370      | 2.58%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 279      | 1.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 264      | 1.84%   |
| Nvidia G94 [GeForce 9600 GT]                                                | 248      | 1.73%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 243      | 1.69%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 234      | 1.63%   |
| Nvidia GF108 [GeForce GT 630]                                               | 218      | 1.52%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 216      | 1.5%    |
| Nvidia GK208B [GeForce GT 710]                                              | 212      | 1.48%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 207      | 1.44%   |
| Nvidia GF119 [GeForce GT 610]                                               | 197      | 1.37%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 194      | 1.35%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 192      | 1.34%   |
| Nvidia GF108 [GeForce GT 440]                                               | 170      | 1.18%   |
| Nvidia GF108 [GeForce GT 430]                                               | 167      | 1.16%   |
| Nvidia G92 [GeForce GTS 250]                                                | 167      | 1.16%   |
| Nvidia G84 [GeForce 8600 GT]                                                | 160      | 1.11%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 158      | 1.1%    |
| Nvidia GK106 [GeForce GTX 660]                                              | 153      | 1.07%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 141      | 0.98%   |
| Nvidia GK208B [GeForce GT 730]                                              | 134      | 0.93%   |
| Nvidia GT215 [GeForce GT 240]                                               | 133      | 0.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 133      | 0.93%   |
| AMD RS780L [Radeon 3000]                                                    | 131      | 0.91%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 129      | 0.9%    |
| Nvidia GK107 [GeForce GT 640]                                               | 121      | 0.84%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 118      | 0.82%   |
| Nvidia GF106 [GeForce GTS 450]                                              | 115      | 0.8%    |
| AMD Turks XT [Radeon HD 6670/7670]                                          | 109      | 0.76%   |
| Nvidia GK106 [GeForce GTX 650 Ti]                                           | 103      | 0.72%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                           | 103      | 0.72%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 103      | 0.72%   |
| AMD Cape Verde PRO [Radeon HD 7750/8740 / R7 250E]                          | 98       | 0.68%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 96       | 0.67%   |
| Nvidia GT216 [GeForce GT 220]                                               | 92       | 0.64%   |
| Nvidia GF108 [GeForce GT 730]                                               | 92       | 0.64%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 91       | 0.63%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 90       | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| 1 x Nvidia                    | 6832     | 51.68%  |
| 1 x AMD                       | 3241     | 24.52%  |
| 1 x Intel                     | 2467     | 18.66%  |
| 2 x AMD                       | 415      | 3.14%   |
| Intel + Nvidia                | 123      | 0.93%   |
| Intel + AMD                   | 31       | 0.23%   |
| 2 x Nvidia                    | 29       | 0.22%   |
| AMD + Nvidia                  | 29       | 0.22%   |
| 1 x VIA                       | 25       | 0.19%   |
| 1 x SiS                       | 7        | 0.05%   |
| 1 x S3 Graphics               | 4        | 0.03%   |
| 1 x Matrox                    | 4        | 0.03%   |
| 3 x AMD                       | 3        | 0.02%   |
| 3 x Nvidia                    | 2        | 0.02%   |
| Nvidia + Matrox               | 2        | 0.02%   |
| 1 x ASPEED                    | 2        | 0.02%   |
| 2 x AMD + 1 x Nvidia          | 1        | 0.01%   |
| Intel + SiS + 1 x S3 Graphics | 1        | 0.01%   |
| AMD + 2 x Nvidia              | 1        | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 10095    | 72.96%  |
| Proprietary | 2843     | 20.55%  |
| Unknown     | 898      | 6.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 3336     | 23.9%   |
| Unknown    | 3248     | 23.27%  |
| 1.01-2.0   | 3155     | 22.61%  |
| 0.51-1.0   | 3005     | 21.53%  |
| 3.01-4.0   | 746      | 5.34%   |
| 7.01-8.0   | 187      | 1.34%   |
| 2.01-3.0   | 146      | 1.05%   |
| 5.01-6.0   | 106      | 0.76%   |
| 8.01-16.0  | 28       | 0.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 3327     | 26.03%  |
| Goldstar             | 2086     | 16.32%  |
| Acer                 | 1394     | 10.91%  |
| BenQ                 | 999      | 7.82%   |
| Philips              | 827      | 6.47%   |
| ViewSonic            | 580      | 4.54%   |
| Ancor Communications | 491      | 3.84%   |
| Dell                 | 481      | 3.76%   |
| AOC                  | 442      | 3.46%   |
| Hewlett-Packard      | 356      | 2.79%   |
| NEC Computers        | 288      | 2.25%   |
| Sony                 | 132      | 1.03%   |
| Iiyama               | 127      | 0.99%   |
| Plain Tree Systems   | 77       | 0.6%    |
| Lenovo               | 61       | 0.48%   |
| Envision Peripherals | 57       | 0.45%   |
| Fujitsu Siemens      | 50       | 0.39%   |
| Unknown              | 45       | 0.35%   |
| Packard Bell         | 45       | 0.35%   |
| HannStar             | 44       | 0.34%   |
| Toshiba              | 42       | 0.33%   |
| ___                  | 36       | 0.28%   |
| MiTAC                | 35       | 0.27%   |
| ASUSTek Computer     | 34       | 0.27%   |
| Panasonic            | 27       | 0.21%   |
| Belinea              | 27       | 0.21%   |
| Hitachi              | 23       | 0.18%   |
| VIE                  | 22       | 0.17%   |
| Medion               | 21       | 0.16%   |
| KTC                  | 21       | 0.16%   |
| Eizo                 | 20       | 0.16%   |
| MStar                | 17       | 0.13%   |
| JRY                  | 17       | 0.13%   |
| HKC                  | 17       | 0.13%   |
| Haier                | 16       | 0.13%   |
| eMachines            | 15       | 0.12%   |
| BBK                  | 14       | 0.11%   |
| Sharp                | 13       | 0.1%    |
| CVT                  | 12       | 0.09%   |
| RoverScan            | 11       | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 106      | 0.8%    |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 97       | 0.74%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 90       | 0.68%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch  | 74       | 0.56%   |
| Acer AL1716A ACRAD46 1280x1024 338x270mm 17.0-inch                    | 71       | 0.54%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 64       | 0.49%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                   | 53       | 0.4%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 49       | 0.37%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 376x301mm 19.0-inch   | 48       | 0.36%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                  | 44       | 0.33%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 43       | 0.33%   |
| Acer AL1916 ACRAD49 1280x1024 376x301mm 19.0-inch                     | 42       | 0.32%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 40       | 0.3%    |
| Goldstar L1942 GSM4B85 1280x1024 376x301mm 19.0-inch                  | 40       | 0.3%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 39       | 0.3%    |
| Goldstar L1918S GSM4B31 1280x1024 376x301mm 19.0-inch                 | 37       | 0.28%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 890x500mm 40.2-inch | 33       | 0.25%   |
| Goldstar W2242 GSM5677 1680x1050 474x296mm 22.0-inch                  | 32       | 0.24%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 32       | 0.24%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                  | 32       | 0.24%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch   | 31       | 0.24%   |
| Plain Tree Systems LCD Monitor PTS06A5 1280x1024 337x270mm 17.0-inch  | 31       | 0.24%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                   | 31       | 0.24%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                   | 31       | 0.24%   |
| Goldstar L1952S GSM4AE0 1280x1024 376x301mm 19.0-inch                 | 31       | 0.24%   |
| Goldstar L1730S GSM438D 1280x1024 338x270mm 17.0-inch                 | 31       | 0.24%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 30       | 0.23%   |
| Goldstar L1718S GSM443C 1280x1024 338x270mm 17.0-inch                 | 29       | 0.22%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 29       | 0.22%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch  | 27       | 0.21%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 376x301mm 19.0-inch  | 27       | 0.21%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                | 27       | 0.21%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 26       | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 26       | 0.2%    |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch   | 25       | 0.19%   |
| Samsung Electronics SyncMaster SAM0022 1280x1024 312x234mm 15.4-inch  | 25       | 0.19%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 25       | 0.19%   |
| Acer V193W ACR0053 1440x900 408x255mm 18.9-inch                       | 25       | 0.19%   |
| Samsung Electronics SyncMaster SAM010B 1280x1024 340x270mm 17.1-inch  | 24       | 0.18%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                    | 24       | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 5090     | 40.29%  |
| 1280x1024 (SXGA)   | 3075     | 24.34%  |
| 1680x1050 (WSXGA+) | 976      | 7.73%   |
| 1440x900 (WXGA+)   | 820      | 6.49%   |
| 1366x768 (WXGA)    | 616      | 4.88%   |
| 1600x900 (HD+)     | 502      | 3.97%   |
| 1360x768           | 258      | 2.04%   |
| 1920x1200 (WUXGA)  | 236      | 1.87%   |
| 1024x768 (XGA)     | 226      | 1.79%   |
| 3840x2160 (4K)     | 205      | 1.62%   |
| 2560x1440 (QHD)    | 172      | 1.36%   |
| 1600x1200          | 139      | 1.1%    |
| 2560x1080          | 66       | 0.52%   |
| 1920x540           | 52       | 0.41%   |
| 1280x720 (HD)      | 39       | 0.31%   |
| 1152x864           | 35       | 0.28%   |
| 1400x1050          | 29       | 0.23%   |
| 3440x1440          | 20       | 0.16%   |
| 2048x1536          | 14       | 0.11%   |
| 2048x1152          | 12       | 0.09%   |
| 1920x1440          | 12       | 0.09%   |
| 1280x960           | 12       | 0.09%   |
| 2560x1600          | 6        | 0.05%   |
| 2288x1287          | 6        | 0.05%   |
| 1280x768           | 4        | 0.03%   |
| 4093x4093          | 2        | 0.02%   |
| 832x624            | 1        | 0.01%   |
| 640x480            | 1        | 0.01%   |
| 3840x2560          | 1        | 0.01%   |
| 3840x1200          | 1        | 0.01%   |
| 1792x1344          | 1        | 0.01%   |
| 1280x800 (WXGA)    | 1        | 0.01%   |
| 1024x600           | 1        | 0.01%   |
| Unknown            | 1        | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 19      | 2174     | 16.88%  |
| 21      | 2076     | 16.12%  |
| 23      | 1643     | 12.76%  |
| 17      | 1524     | 11.84%  |
| 24      | 976      | 7.58%   |
| 18      | 869      | 6.75%   |
| 20      | 746      | 5.79%   |
| 22      | 597      | 4.64%   |
| 27      | 594      | 4.61%   |
| 15      | 459      | 3.56%   |
| Unknown | 156      | 1.21%   |
| 31      | 137      | 1.06%   |
| 72      | 112      | 0.87%   |
| 54      | 98       | 0.76%   |
| 40      | 87       | 0.68%   |
| 32      | 81       | 0.63%   |
| 34      | 78       | 0.61%   |
| 16      | 63       | 0.49%   |
| 52      | 48       | 0.37%   |
| 25      | 46       | 0.36%   |
| 84      | 40       | 0.31%   |
| 46      | 38       | 0.3%    |
| 48      | 25       | 0.19%   |
| 13      | 24       | 0.19%   |
| 14      | 19       | 0.15%   |
| 12      | 18       | 0.14%   |
| 43      | 17       | 0.13%   |
| 42      | 17       | 0.13%   |
| 26      | 16       | 0.12%   |
| 28      | 14       | 0.11%   |
| 33      | 9        | 0.07%   |
| 65      | 8        | 0.06%   |
| 37      | 8        | 0.06%   |
| 29      | 8        | 0.06%   |
| 55      | 6        | 0.05%   |
| 39      | 6        | 0.05%   |
| 99      | 4        | 0.03%   |
| 60      | 4        | 0.03%   |
| 50      | 4        | 0.03%   |
| 47      | 4        | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 4973     | 39.13%  |
| 501-600        | 3091     | 24.32%  |
| 301-350        | 1982     | 15.59%  |
| 351-400        | 1541     | 12.12%  |
| 1001-1500      | 244      | 1.92%   |
| 601-700        | 194      | 1.53%   |
| 701-800        | 169      | 1.33%   |
| Unknown        | 156      | 1.23%   |
| 1501-2000      | 155      | 1.22%   |
| 801-900        | 104      | 0.82%   |
| 201-300        | 60       | 0.47%   |
| 901-1000       | 35       | 0.28%   |
| More than 2000 | 6        | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 6690     | 53.6%   |
| 5/4     | 2896     | 23.2%   |
| 16/10   | 1892     | 15.16%  |
| 4/3     | 692      | 5.54%   |
| 3/2     | 149      | 1.19%   |
| 21/9    | 86       | 0.69%   |
| 6/5     | 49       | 0.39%   |
| Unknown | 16       | 0.13%   |
| 32/9    | 8        | 0.06%   |
| 1.00    | 3        | 0.02%   |
| 2.00    | 1        | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 4554     | 35.72%  |
| 151-200        | 3517     | 27.59%  |
| 141-150        | 2138     | 16.77%  |
| 301-350        | 601      | 4.71%   |
| More than 1000 | 361      | 2.83%   |
| 251-300        | 322      | 2.53%   |
| 351-500        | 307      | 2.41%   |
| 101-110        | 255      | 2%      |
| 111-120        | 223      | 1.75%   |
| 501-1000       | 190      | 1.49%   |
| Unknown        | 156      | 1.22%   |
| 121-130        | 42       | 0.33%   |
| 131-140        | 35       | 0.27%   |
| 71-80          | 19       | 0.15%   |
| 81-90          | 15       | 0.12%   |
| 91-100         | 11       | 0.09%   |
| 61-70          | 1        | 0.01%   |
| 41-50          | 1        | 0.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 9198     | 74.54%  |
| 101-120       | 2337     | 18.94%  |
| 1-50          | 467      | 3.78%   |
| Unknown       | 156      | 1.26%   |
| 121-160       | 139      | 1.13%   |
| 161-240       | 41       | 0.33%   |
| More than 240 | 1        | 0.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 11984    | 91.36%  |
| 2     | 752      | 5.73%   |
| 0     | 358      | 2.73%   |
| 3     | 24       | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 8647     | 51.3%   |
| Qualcomm Atheros                       | 1877     | 11.14%  |
| Intel                                  | 1464     | 8.69%   |
| Nvidia                                 | 1109     | 6.58%   |
| Ralink Technology                      | 480      | 2.85%   |
| Marvell Technology Group               | 348      | 2.06%   |
| Huawei Technologies                    | 335      | 1.99%   |
| Ralink                                 | 301      | 1.79%   |
| VIA Technologies                       | 300      | 1.78%   |
| Broadcom                               | 207      | 1.23%   |
| Qualcomm Atheros Communications        | 199      | 1.18%   |
| D-Link System                          | 197      | 1.17%   |
| D-Link                                 | 155      | 0.92%   |
| TP-Link                                | 133      | 0.79%   |
| Broadcom Limited                       | 133      | 0.79%   |
| ASUSTek Computer                       | 128      | 0.76%   |
| ZTE WCDMA Technologies MSM             | 81       | 0.48%   |
| Sundance Technology Inc / IC Plus      | 66       | 0.39%   |
| Silicon Integrated Systems [SiS]       | 52       | 0.31%   |
| Xiaomi                                 | 45       | 0.27%   |
| Samsung Electronics                    | 45       | 0.27%   |
| NetGear                                | 44       | 0.26%   |
| MediaTek                               | 44       | 0.26%   |
| 3Com                                   | 44       | 0.26%   |
| HTC (High Tech Computer)               | 36       | 0.21%   |
| IMC Networks                           | 22       | 0.13%   |
| Gemtek                                 | 21       | 0.12%   |
| Microsoft                              | 20       | 0.12%   |
| ZyXEL Communications                   | 19       | 0.11%   |
| LSI                                    | 18       | 0.11%   |
| T & A Mobile Phones                    | 15       | 0.09%   |
| Spreadtrum Communications              | 12       | 0.07%   |
| Sony Ericsson Mobile Communications AB | 11       | 0.07%   |
| Qualcomm                               | 11       | 0.07%   |
| Edimax Technology                      | 10       | 0.06%   |
| Belkin Components                      | 10       | 0.06%   |
| Mercucys                               | 9        | 0.05%   |
| JMicron Technology                     | 9        | 0.05%   |
| GCT Semiconductor                      | 9        | 0.05%   |
| ULi Electronics                        | 8        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 7071     | 39.55%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 648      | 3.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 587      | 3.28%   |
| Nvidia MCP61 Ethernet                                             | 586      | 3.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 251      | 1.4%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 249      | 1.39%   |
| Ralink MT7601U Wireless Adapter                                   | 240      | 1.34%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 204      | 1.14%   |
| Intel 82579V Gigabit Network Connection                           | 200      | 1.12%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 194      | 1.09%   |
| Huawei Modem/Networkcard                                          | 189      | 1.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 187      | 1.05%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 162      | 0.91%   |
| Qualcomm Atheros AR9271 802.11n                                   | 157      | 0.88%   |
| Intel Ethernet Connection (2) I219-V                              | 148      | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 137      | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 136      | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 124      | 0.69%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 121      | 0.68%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 117      | 0.65%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 111      | 0.62%   |
| Ralink RT5370 Wireless Adapter                                    | 108      | 0.6%    |
| Nvidia CK804 Ethernet Controller                                  | 108      | 0.6%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 105      | 0.59%   |
| Intel I211 Gigabit Network Connection                             | 99       | 0.55%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 98       | 0.55%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 93       | 0.52%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 93       | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 92       | 0.51%   |
| Nvidia MCP55 Ethernet                                             | 91       | 0.51%   |
| Nvidia MCP77 Ethernet                                             | 88       | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 87       | 0.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 85       | 0.48%   |
| Nvidia MCP51 Ethernet Controller                                  | 84       | 0.47%   |
| Intel Ethernet Connection I217-V                                  | 82       | 0.46%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 78       | 0.44%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 76       | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 73       | 0.41%   |
| Intel Ethernet Connection (2) I218-V                              | 72       | 0.4%    |
| Ralink RT3060 Wireless 802.11n 1T/1R                              | 68       | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 754      | 22.9%   |
| Qualcomm Atheros                | 554      | 16.83%  |
| Ralink Technology               | 480      | 14.58%  |
| Ralink                          | 301      | 9.14%   |
| Qualcomm Atheros Communications | 199      | 6.04%   |
| Intel                           | 193      | 5.86%   |
| D-Link                          | 153      | 4.65%   |
| TP-Link                         | 132      | 4.01%   |
| ASUSTek Computer                | 118      | 3.58%   |
| D-Link System                   | 103      | 3.13%   |
| Broadcom                        | 85       | 2.58%   |
| NetGear                         | 43       | 1.31%   |
| IMC Networks                    | 22       | 0.67%   |
| Microsoft                       | 19       | 0.58%   |
| Broadcom Limited                | 19       | 0.58%   |
| ZyXEL Communications            | 15       | 0.46%   |
| Edimax Technology               | 10       | 0.3%    |
| Mercucys                        | 9        | 0.27%   |
| Belkin Components               | 9        | 0.27%   |
| MediaTek                        | 8        | 0.24%   |
| Marvell Technology Group        | 6        | 0.18%   |
| Gemtek                          | 6        | 0.18%   |
| ZyDAS                           | 5        | 0.15%   |
| Linksys                         | 5        | 0.15%   |
| TRENDnet                        | 4        | 0.12%   |
| Sitecom Europe                  | 4        | 0.12%   |
| Accton Technology               | 4        | 0.12%   |
| VIA Technologies                | 3        | 0.09%   |
| Texas Instruments               | 3        | 0.09%   |
| Tenda                           | 3        | 0.09%   |
| Sagem                           | 3        | 0.09%   |
| Micro Star International        | 3        | 0.09%   |
| BUFFALO                         | 3        | 0.09%   |
| AboCom Systems                  | 3        | 0.09%   |
| Xiaomi                          | 2        | 0.06%   |
| Z-Com                           | 1        | 0.03%   |
| Wacom                           | 1        | 0.03%   |
| Sierra Wireless                 | 1        | 0.03%   |
| Philips (or NXP)                | 1        | 0.03%   |
| Guillemot                       | 1        | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                | Desktops | Percent |
|--------------------------------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                                      | 240      | 7.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                  | 187      | 5.55%   |
| Qualcomm Atheros AR9271 802.11n                                                      | 157      | 4.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                     | 137      | 4.06%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                               | 117      | 3.47%   |
| Ralink RT5370 Wireless Adapter                                                       | 108      | 3.2%    |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                     | 98       | 2.91%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                 | 68       | 2.02%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                | 64       | 1.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                       | 62       | 1.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                           | 61       | 1.81%   |
| Ralink RT2561/RT61 rev B 802.11g                                                     | 56       | 1.66%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                           | 56       | 1.66%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                              | 52       | 1.54%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                       | 52       | 1.54%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                         | 38       | 1.13%   |
| Realtek RTL8188EE Wireless Network Adapter                                           | 37       | 1.1%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                            | 37       | 1.1%    |
| Ralink RT5360 Wireless 802.11n 1T/1R                                                 | 37       | 1.1%    |
| Realtek RTL8187 Wireless Adapter                                                     | 36       | 1.07%   |
| D-Link 802.11 n WLAN                                                                 | 36       | 1.07%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                     | 30       | 0.89%   |
| Intel Wi-Fi 6 AX200                                                                  | 30       | 0.89%   |
| Realtek 802.11ac NIC                                                                 | 28       | 0.83%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                           | 27       | 0.8%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                            | 27       | 0.8%    |
| ASUS USB-N13 802.11n Network Adapter (rev. B1) [Realtek RTL8192CU]                   | 26       | 0.77%   |
| ASUS N10 Nano 802.11n Network Adapter [Realtek RTL8192CU]                            | 26       | 0.77%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                               | 25       | 0.74%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                            | 25       | 0.74%   |
| Ralink RT2561/RT61 802.11g PCI                                                       | 25       | 0.74%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg]        | 25       | 0.74%   |
| D-Link DWA-140 RangeBooster N Adapter(rev.B3) [Ralink RT5372]                        | 25       | 0.74%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                          | 24       | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                     | 24       | 0.71%   |
| Qualcomm Atheros TP-Link TL-WN821N v3 / TL-WN822N v2 802.11n [Atheros AR7010+AR9287] | 23       | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                     | 21       | 0.62%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                                      | 21       | 0.62%   |
| Intel Wireless 7260                                                                  | 21       | 0.62%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]                 | 21       | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 8374     | 60.45%  |
| Qualcomm Atheros                       | 1384     | 9.99%   |
| Intel                                  | 1351     | 9.75%   |
| Nvidia                                 | 1109     | 8.01%   |
| Marvell Technology Group               | 343      | 2.48%   |
| VIA Technologies                       | 290      | 2.09%   |
| Broadcom                               | 122      | 0.88%   |
| Broadcom Limited                       | 114      | 0.82%   |
| D-Link System                          | 95       | 0.69%   |
| Huawei Technologies                    | 83       | 0.6%    |
| ZTE WCDMA Technologies MSM             | 75       | 0.54%   |
| Sundance Technology Inc / IC Plus      | 66       | 0.48%   |
| Silicon Integrated Systems [SiS]       | 50       | 0.36%   |
| Samsung Electronics                    | 44       | 0.32%   |
| 3Com                                   | 44       | 0.32%   |
| Xiaomi                                 | 43       | 0.31%   |
| HTC (High Tech Computer)               | 36       | 0.26%   |
| MediaTek                               | 35       | 0.25%   |
| T & A Mobile Phones                    | 15       | 0.11%   |
| Gemtek                                 | 15       | 0.11%   |
| Spreadtrum Communications              | 12       | 0.09%   |
| Sony Ericsson Mobile Communications AB | 11       | 0.08%   |
| Qualcomm                               | 11       | 0.08%   |
| ASUSTek Computer                       | 10       | 0.07%   |
| JMicron Technology                     | 9        | 0.06%   |
| GCT Semiconductor                      | 9        | 0.06%   |
| ULi Electronics                        | 8        | 0.06%   |
| Lenovo                                 | 8        | 0.06%   |
| Davicom Semiconductor                  | 7        | 0.05%   |
| ASIX Electronics                       | 7        | 0.05%   |
| ADMtek                                 | 7        | 0.05%   |
| Vimtron Electronics                    | 6        | 0.04%   |
| OPPO Electronics                       | 5        | 0.04%   |
| ZyXEL Communications                   | 4        | 0.03%   |
| ICS Advent                             | 4        | 0.03%   |
| Motorola PCS                           | 3        | 0.02%   |
| LG Electronics                         | 3        | 0.02%   |
| Android                                | 3        | 0.02%   |
| TOMTOM                                 | 2        | 0.01%   |
| SysKonnect                             | 2        | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller          | 7071     | 49.96%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 648      | 4.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 587      | 4.15%   |
| Nvidia MCP61 Ethernet                                                      | 586      | 4.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 251      | 1.77%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                              | 249      | 1.76%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 204      | 1.44%   |
| Intel 82579V Gigabit Network Connection                                    | 200      | 1.41%   |
| VIA VT6105/VT6106S [Rhine-III]                                             | 194      | 1.37%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                    | 162      | 1.14%   |
| Intel Ethernet Connection (2) I219-V                                       | 148      | 1.05%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                   | 136      | 0.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 124      | 0.88%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                 | 121      | 0.86%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                          | 111      | 0.78%   |
| Nvidia CK804 Ethernet Controller                                           | 108      | 0.76%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                            | 105      | 0.74%   |
| Intel I211 Gigabit Network Connection                                      | 99       | 0.7%    |
| VIA VT6102/VT6103 [Rhine-II]                                               | 93       | 0.66%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                 | 93       | 0.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                 | 92       | 0.65%   |
| Nvidia MCP55 Ethernet                                                      | 91       | 0.64%   |
| Nvidia MCP77 Ethernet                                                      | 88       | 0.62%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 87       | 0.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 85       | 0.6%    |
| Nvidia MCP51 Ethernet Controller                                           | 84       | 0.59%   |
| Intel Ethernet Connection I217-V                                           | 82       | 0.58%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 78       | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 76       | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                  | 73       | 0.52%   |
| Intel Ethernet Connection (2) I218-V                                       | 72       | 0.51%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                    | 64       | 0.45%   |
| ZTE WCDMA MSM USB SCSI CD-ROM                                              | 63       | 0.45%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 63       | 0.45%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                            | 58       | 0.41%   |
| Huawei E353/E3131                                                          | 50       | 0.35%   |
| Intel 82574L Gigabit Network Connection                                    | 47       | 0.33%   |
| Realtek RTL8125 2.5GbE Controller                                          | 44       | 0.31%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                  | 42       | 0.3%    |
| Nvidia MCP67 Ethernet                                                      | 40       | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 12720    | 78.67%  |
| WiFi     | 3103     | 19.19%  |
| Modem    | 325      | 2.01%   |
| Unknown  | 20       | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 10701    | 83.45%  |
| WiFi     | 2122     | 16.55%  |
| Unknown  | 1        | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 10449    | 80.44%  |
| 2     | 2263     | 17.42%  |
| 3     | 144      | 1.11%   |
| 0     | 124      | 0.95%   |
| 4     | 7        | 0.05%   |
| 33    | 1        | 0.01%   |
| 6     | 1        | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 9378     | 69.28%  |
| Unknown | 4036     | 29.82%  |
| Yes     | 122      | 0.9%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 579      | 46.66%  |
| Intel                           | 163      | 13.13%  |
| ASUSTek Computer                | 144      | 11.6%   |
| Broadcom                        | 96       | 7.74%   |
| Realtek Semiconductor           | 55       | 4.43%   |
| Qualcomm Atheros Communications | 54       | 4.35%   |
| Integrated System Solution      | 53       | 4.27%   |
| IMC Networks                    | 26       | 2.1%    |
| Lite-On Technology              | 14       | 1.13%   |
| TP-Link                         | 7        | 0.56%   |
| Roper                           | 7        | 0.56%   |
| Ralink                          | 7        | 0.56%   |
| Conwise Technology              | 6        | 0.48%   |
| MediaTek                        | 5        | 0.4%    |
| Apple                           | 5        | 0.4%    |
| Micro Star International        | 4        | 0.32%   |
| Logitech                        | 4        | 0.32%   |
| Foxconn / Hon Hai               | 3        | 0.24%   |
| Belkin Components               | 2        | 0.16%   |
| Unknown                         | 1        | 0.08%   |
| Realtek                         | 1        | 0.08%   |
| Ralink Technology               | 1        | 0.08%   |
| Primax Electronics              | 1        | 0.08%   |
| Hewlett-Packard                 | 1        | 0.08%   |
| Dell                            | 1        | 0.08%   |
| D-Link                          | 1        | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 579      | 46.62%  |
| Intel Bluetooth wireless interface                    | 66       | 5.31%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 49       | 3.95%   |
| Realtek Bluetooth Radio                               | 47       | 3.78%   |
| ASUS Bluetooth Adapter                                | 36       | 2.9%    |
| Qualcomm Atheros AR3011 Bluetooth                     | 34       | 2.74%   |
| Integrated System Solution Bluetooth Device           | 33       | 2.66%   |
| Intel AX200 Bluetooth                                 | 30       | 2.42%   |
| Intel Wireless-AC 3168 Bluetooth                      | 24       | 1.93%   |
| Broadcom BCM2045 Bluetooth                            | 22       | 1.77%   |
| ASUS BCM20702A0                                       | 22       | 1.77%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 20       | 1.61%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 19       | 1.53%   |
| Lite-On Bluetooth Device                              | 13       | 1.05%   |
| Intel AX210 Bluetooth                                 | 12       | 0.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 11       | 0.89%   |
| ASUS Qualcomm Bluetooth 4.1                           | 11       | 0.89%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 10       | 0.81%   |
| ASUS Bluetooth Radio                                  | 10       | 0.81%   |
| IMC Networks Bluetooth Radio                          | 9        | 0.72%   |
| IMC Networks Bluetooth module                         | 8        | 0.64%   |
| Broadcom BCM92045B3 ROM                               | 8        | 0.64%   |
| TP-Link TPuLink UB500 Adapter                         | 7        | 0.56%   |
| Roper Class 1 Bluetooth Dongle                        | 7        | 0.56%   |
| Ralink RT3290 Bluetooth                               | 7        | 0.56%   |
| Broadcom Bluetooth 3.0 Device                         | 7        | 0.56%   |
| ASUS ASUS USB-BT500                                   | 7        | 0.56%   |
| Qualcomm Atheros  Bluetooth Device                    | 6        | 0.48%   |
| Conwise CW6622                                        | 6        | 0.48%   |
| Broadcom Bluetooth 3.0 USB Dongle                     | 6        | 0.48%   |
| Broadcom Bluetooth 2.0+eDR dongle                     | 6        | 0.48%   |
| Realtek  Bluetooth 4.2 Adapter                        | 5        | 0.4%    |
| MediaTek Wireless_Device                              | 5        | 0.4%    |
| Intel Bluetooth Device                                | 5        | 0.4%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 5        | 0.4%    |
| Broadcom BCM2210 Bluetooth                            | 5        | 0.4%    |
| Qualcomm Atheros Bluetooth (AR3011)                   | 4        | 0.32%   |
| Micro Star International Bluetooth Device             | 4        | 0.32%   |
| Logitech BT Mini-Receiver (HCI mode)                  | 4        | 0.32%   |
| IMC Networks BCM20702A0                               | 4        | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 7986     | 39.35%  |
| Nvidia                                          | 5808     | 28.62%  |
| AMD                                             | 4647     | 22.9%   |
| C-Media Electronics                             | 536      | 2.64%   |
| Creative Labs                                   | 449      | 2.21%   |
| VIA Technologies                                | 186      | 0.92%   |
| Silicon Integrated Systems [SiS]                | 67       | 0.33%   |
| Creative Technology                             | 64       | 0.32%   |
| Logitech                                        | 55       | 0.27%   |
| JMTek                                           | 39       | 0.19%   |
| Texas Instruments                               | 37       | 0.18%   |
| Generalplus Technology                          | 23       | 0.11%   |
| Ensoniq                                         | 23       | 0.11%   |
| Plantronics                                     | 21       | 0.1%    |
| Pixart Imaging                                  | 18       | 0.09%   |
| Tenx Technology                                 | 17       | 0.08%   |
| ASUSTek Computer                                | 16       | 0.08%   |
| ULi Electronics                                 | 15       | 0.07%   |
| Razer USA                                       | 14       | 0.07%   |
| Aureal Semiconductor                            | 10       | 0.05%   |
| Shenzhen Rapoo Technology                       | 9        | 0.04%   |
| Kingston Technology                             | 9        | 0.04%   |
| ESS Technology                                  | 9        | 0.04%   |
| Asahi Kasei Microsystems                        | 9        | 0.04%   |
| Yamaha                                          | 8        | 0.04%   |
| ATI Technologies                                | 8        | 0.04%   |
| A4Tech                                          | 8        | 0.04%   |
| Guillemot                                       | 7        | 0.03%   |
| Sony                                            | 6        | 0.03%   |
| Philips (or NXP)                                | 6        | 0.03%   |
| M-Audio                                         | 6        | 0.03%   |
| Licensed by Sony Computer Entertainment America | 6        | 0.03%   |
| Fortemedia                                      | 6        | 0.03%   |
| Yealink Network Technology                      | 5        | 0.02%   |
| iCreate Technologies                            | 5        | 0.02%   |
| Focusrite-Novation                              | 5        | 0.02%   |
| EGO SYStems                                     | 5        | 0.02%   |
| Dell                                            | 5        | 0.02%   |
| Conexant Systems                                | 5        | 0.02%   |
| XMOS                                            | 4        | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 1943     | 8.6%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 1894     | 8.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 1279     | 5.66%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 765      | 3.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 748      | 3.31%   |
| Nvidia GF108 High Definition Audio Controller                                     | 707      | 3.13%   |
| Nvidia MCP61 High Definition Audio                                                | 641      | 2.84%   |
| Nvidia High Definition Audio Controller                                           | 611      | 2.7%    |
| AMD FCH Azalia Controller                                                         | 601      | 2.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 587      | 2.6%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 548      | 2.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 479      | 2.12%   |
| Nvidia GK107 HDMI Audio Controller                                                | 417      | 1.84%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 408      | 1.81%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 398      | 1.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 368      | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 338      | 1.5%    |
| Nvidia GF116 High Definition Audio Controller                                     | 306      | 1.35%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 293      | 1.3%    |
| Nvidia GK106 HDMI Audio Controller                                                | 290      | 1.28%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 289      | 1.28%   |
| Nvidia GF119 HDMI Audio Controller                                                | 280      | 1.24%   |
| Nvidia GK104 HDMI Audio Controller                                                | 234      | 1.04%   |
| Intel 200 Series PCH HD Audio                                                     | 213      | 0.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 198      | 0.88%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 198      | 0.88%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                         | 193      | 0.85%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                     | 192      | 0.85%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 184      | 0.81%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 173      | 0.77%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                              | 165      | 0.73%   |
| Nvidia GF114 HDMI Audio Controller                                                | 156      | 0.69%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 151      | 0.67%   |
| AMD Family 17h/19h HD Audio Controller                                            | 150      | 0.66%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                     | 149      | 0.66%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 146      | 0.65%   |
| Nvidia GP106 High Definition Audio Controller                                     | 143      | 0.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 139      | 0.61%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 138      | 0.61%   |
| Nvidia GF106 High Definition Audio Controller                                     | 128      | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 6861     | 49.49%  |
| Kingston            | 2261     | 16.31%  |
| Samsung Electronics | 793      | 5.72%   |
| Crucial             | 697      | 5.03%   |
| SK hynix            | 597      | 4.31%   |
| Corsair             | 552      | 3.98%   |
| Micron Technology   | 217      | 1.57%   |
| Patriot             | 205      | 1.48%   |
| AMD                 | 197      | 1.42%   |
| Nanya Technology    | 128      | 0.92%   |
| GOODRAM             | 120      | 0.87%   |
| A-DATA Technology   | 94       | 0.68%   |
| G.Skill             | 93       | 0.67%   |
| Silicon Power       | 92       | 0.66%   |
| Transcend           | 86       | 0.62%   |
| Kingmax             | 80       | 0.58%   |
| Elpida              | 77       | 0.56%   |
| Qumo                | 59       | 0.43%   |
| GeIL                | 54       | 0.39%   |
| Team                | 51       | 0.37%   |
| Apacer              | 51       | 0.37%   |
| Goldkey             | 46       | 0.33%   |
| Ramaxel Technology  | 35       | 0.25%   |
| Kllisre             | 33       | 0.24%   |
| Unknown             | 31       | 0.22%   |
| KETECH              | 29       | 0.21%   |
| Unifosa             | 28       | 0.2%    |
| Foxline             | 26       | 0.19%   |
| Qimonda             | 23       | 0.17%   |
| Ramos Technology    | 15       | 0.11%   |
| TakeMS              | 14       | 0.1%    |
| Atermiter           | 13       | 0.09%   |
| Unknown (ABCD)      | 10       | 0.07%   |
| Hexon               | 10       | 0.07%   |
| Exceleram           | 10       | 0.07%   |
| OCZ                 | 9        | 0.06%   |
| TwinMOS             | 7        | 0.05%   |
| PNY                 | 6        | 0.04%   |
| ASint Technology    | 6        | 0.04%   |
| Aeneon              | 6        | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s           | 486      | 2.98%   |
| Unknown RAM Module 2048MB DIMM SDRAM                  | 468      | 2.87%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                | 441      | 2.7%    |
| Unknown RAM Module 1024MB DIMM SDRAM                  | 414      | 2.54%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s               | 371      | 2.27%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s               | 350      | 2.15%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s           | 324      | 1.99%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                | 250      | 1.53%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s           | 248      | 1.52%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s           | 206      | 1.26%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                | 164      | 1.01%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s          | 160      | 0.98%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                | 156      | 0.96%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                | 146      | 0.9%    |
| Unknown RAM Module 512MB DIMM SDRAM                   | 143      | 0.88%   |
| Unknown RAM Module 1024MB DIMM                        | 138      | 0.85%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s               | 131      | 0.8%    |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s   | 123      | 0.75%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s          | 104      | 0.64%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                | 101      | 0.62%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s           | 101      | 0.62%   |
| Unknown RAM Module 1024MB DIMM DDR2                   | 98       | 0.6%    |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s          | 95       | 0.58%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s           | 94       | 0.58%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s               | 87       | 0.53%   |
| Unknown RAM Module 2048MB DIMM                        | 82       | 0.5%    |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s           | 75       | 0.46%   |
| Unknown RAM Module 2048MB DIMM DDR2                   | 75       | 0.46%   |
| Unknown RAM Module 512MB DIMM                         | 73       | 0.45%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s | 73       | 0.45%   |
| Unknown RAM Module 4096MB DIMM SDRAM                  | 69       | 0.42%   |
| Unknown RAM Module 1024MB DIMM 400MT/s                | 67       | 0.41%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3            | 66       | 0.4%    |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s | 62       | 0.38%   |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s            | 60       | 0.37%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s           | 58       | 0.36%   |
| Unknown RAM Module 512MB DIMM DDR2 667MT/s            | 57       | 0.35%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s | 57       | 0.35%   |
| Unknown RAM Module 4096MB DIMM 1066MT/s               | 56       | 0.34%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                | 55       | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 4428     | 34.87%  |
| Unknown | 2873     | 22.62%  |
| DDR2    | 2088     | 16.44%  |
| SDRAM   | 1489     | 11.73%  |
| DDR4    | 1307     | 10.29%  |
| DDR     | 477      | 3.76%   |
| DRAM    | 21       | 0.17%   |
| LPDDR4  | 13       | 0.1%    |
| DDR5    | 3        | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 12229    | 97.88%  |
| SODIMM       | 257      | 2.06%   |
| FB-DIMM      | 7        | 0.06%   |
| Row Of Chips | 1        | 0.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 2048  | 4710     | 31.96%  |
| 4096  | 4178     | 28.35%  |
| 1024  | 2734     | 18.55%  |
| 8192  | 2011     | 13.65%  |
| 512   | 688      | 4.67%   |
| 16384 | 195      | 1.32%   |
| 256   | 165      | 1.12%   |
| 32768 | 42       | 0.29%   |
| 128   | 5        | 0.03%   |
| 32    | 4        | 0.03%   |
| 16    | 3        | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 2470     | 18.06%  |
| 1333    | 2446     | 17.88%  |
| 800     | 1915     | 14%     |
| Unknown | 1497     | 10.94%  |
| 667     | 1118     | 8.17%   |
| 400     | 460      | 3.36%   |
| 2400    | 450      | 3.29%   |
| 2133    | 388      | 2.84%   |
| 1867    | 286      | 2.09%   |
| 1066    | 255      | 1.86%   |
| 533     | 244      | 1.78%   |
| 333     | 219      | 1.6%    |
| 3200    | 184      | 1.35%   |
| 2667    | 179      | 1.31%   |
| 1866    | 156      | 1.14%   |
| 3400    | 104      | 0.76%   |
| 1800    | 103      | 0.75%   |
| 266     | 96       | 0.7%    |
| 1067    | 89       | 0.65%   |
| 3600    | 88       | 0.64%   |
| 2933    | 71       | 0.52%   |
| 1334    | 63       | 0.46%   |
| 66      | 49       | 0.36%   |
| 3466    | 46       | 0.34%   |
| 3000    | 46       | 0.34%   |
| 2666    | 44       | 0.32%   |
| 2000    | 41       | 0.3%    |
| 2048    | 37       | 0.27%   |
| 1648    | 37       | 0.27%   |
| 2134    | 35       | 0.26%   |
| 1639    | 35       | 0.26%   |
| 1400    | 35       | 0.26%   |
| 2800    | 34       | 0.25%   |
| 200     | 28       | 0.2%    |
| 49926   | 25       | 0.18%   |
| 2866    | 24       | 0.18%   |
| 3066    | 19       | 0.14%   |
| 2187    | 14       | 0.1%    |
| 3334    | 12       | 0.09%   |
| 2733    | 12       | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Hewlett-Packard                 | 409      | 30.78%  |
| Canon                           | 309      | 23.25%  |
| Samsung Electronics             | 233      | 17.53%  |
| Seiko Epson                     | 130      | 9.78%   |
| Brother Industries              | 86       | 6.47%   |
| Xerox                           | 38       | 2.86%   |
| Panasonic (Matsushita)          | 25       | 1.88%   |
| Kyocera                         | 22       | 1.66%   |
| Pantum                          | 18       | 1.35%   |
| Ricoh                           | 13       | 0.98%   |
| Prolific Technology             | 10       | 0.75%   |
| Lexmark International           | 8        | 0.6%    |
| QinHeng Electronics             | 6        | 0.45%   |
| TSC Auto ID Technology          | 4        | 0.3%    |
| WinChipHead                     | 3        | 0.23%   |
| STMicroelectronics              | 2        | 0.15%   |
| Sharp                           | 2        | 0.15%   |
| cab Produkttechnik GmbH & Co KG | 2        | 0.15%   |
| Yurex                           | 1        | 0.08%   |
| Toshiba TEC                     | 1        | 0.08%   |
| Samsung Info. Systems America   | 1        | 0.08%   |
| NXP Semiconductors              | 1        | 0.08%   |
| Konica Minolta                  | 1        | 0.08%   |
| KODAK                           | 1        | 0.08%   |
| Fuji Xerox                      | 1        | 0.08%   |
| Custom Engineering SPA          | 1        | 0.08%   |
| ATEN International              | 1        | 0.08%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| HP LaserJet 1020                              | 46       | 3.4%    |
| HP LaserJet 1018                              | 35       | 2.59%   |
| HP LaserJet P1102                             | 34       | 2.52%   |
| Samsung SCX-4200 series                       | 33       | 2.44%   |
| Canon LBP2900                                 | 33       | 2.44%   |
| Seiko Epson Printer                           | 28       | 2.07%   |
| Seiko Epson USB2.0 Printer (Hi-speed)         | 22       | 1.63%   |
| Samsung SCX-3400 Series                       | 19       | 1.41%   |
| HP LaserJet P1005                             | 19       | 1.41%   |
| HP LaserJet 1010                              | 19       | 1.41%   |
| Canon MF4410                                  | 19       | 1.41%   |
| Samsung SCX-3200 Series                       | 18       | 1.33%   |
| Canon MF3010                                  | 18       | 1.33%   |
| Panasonic (Matsushita) KX-MB1500RU            | 17       | 1.26%   |
| Samsung ML-1640 Series Laser Printer          | 15       | 1.11%   |
| Canon MF4010 series                           | 13       | 0.96%   |
| Seiko Epson L210 Series                       | 12       | 0.89%   |
| Canon LBP810                                  | 12       | 0.89%   |
| Canon LBP3010/LBP3018/LBP3050                 | 12       | 0.89%   |
| Xerox Phaser 3140 and 3155                    | 11       | 0.81%   |
| Samsung ML-2010P Mono Laser Printer           | 11       | 0.81%   |
| Samsung ML-1210 Printer                       | 11       | 0.81%   |
| HP Deskjet 2050 J510                          | 11       | 0.81%   |
| Canon LaserShot LBP-1120 Printer              | 11       | 0.81%   |
| Canon iP7200 series                           | 11       | 0.81%   |
| Brother DCP-7057 scanner/printer              | 11       | 0.81%   |
| Prolific PL2305 Parallel Port                 | 10       | 0.74%   |
| HP LaserJet 1320                              | 10       | 0.74%   |
| HP LaserJet 1022                              | 10       | 0.74%   |
| HP LaserJet 1000                              | 10       | 0.74%   |
| HP DeskJet 2130 series                        | 10       | 0.74%   |
| Brother HL-2030 Laser Printer                 | 10       | 0.74%   |
| Samsung SCX-4100 Scanner                      | 9        | 0.67%   |
| Samsung M2070 Series                          | 9        | 0.67%   |
| HP LaserJet 1200                              | 9        | 0.67%   |
| Canon PIXMA MP230                             | 9        | 0.67%   |
| Canon PIXMA MG2500 Series                     | 9        | 0.67%   |
| Canon MG2400 series                           | 9        | 0.67%   |
| Canon LBP6000                                 | 9        | 0.67%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series | 8        | 0.59%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 147      | 37.5%   |
| Seiko Epson                 | 93       | 23.72%  |
| Hewlett-Packard             | 67       | 17.09%  |
| Mustek Systems              | 39       | 9.95%   |
| Acer Peripherals (now BenQ) | 16       | 4.08%   |
| Ultima Electronics          | 15       | 3.83%   |
| KYE Systems (Mouse Systems) | 5        | 1.28%   |
| Fujitsu                     | 3        | 0.77%   |
| Avision                     | 2        | 0.51%   |
| AGFA-Gevaert NV             | 2        | 0.51%   |
| Plustek                     | 1        | 0.26%   |
| Microtek International      | 1        | 0.26%   |
| Canon Electronics           | 1        | 0.26%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Desktops | Percent |
|---------------------------------------------------------------------------------------|----------|---------|
| Canon CanoScan LIDE 25                                                                | 27       | 6.87%   |
| HP ScanJet 2400c                                                                      | 21       | 5.34%   |
| Canon CanoScan LiDE 110                                                               | 21       | 5.34%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 17       | 4.33%   |
| Canon CanoScan LiDE 120                                                               | 16       | 4.07%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 15       | 3.82%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 14       | 3.56%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 13       | 3.31%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 11       | 2.8%    |
| Canon CanoScan LiDE 210                                                               | 11       | 2.8%    |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 10       | 2.54%   |
| Canon CanoScan LiDE 60                                                                | 10       | 2.54%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 8        | 2.04%   |
| Canon CanoScan LiDE 100                                                               | 8        | 2.04%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 7        | 1.78%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 7        | 1.78%   |
| Canon CanoScan LiDE 220                                                               | 7        | 1.78%   |
| Seiko Epson Perfection 660                                                            | 6        | 1.53%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 6        | 1.53%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 5        | 1.27%   |
| Mustek Systems SNAPSCAN e22                                                           | 5        | 1.27%   |
| Mustek Systems BearPaw 2448 TA Plus                                                   | 5        | 1.27%   |
| Canon CanoScan                                                                        | 5        | 1.27%   |
| Acer Peripherals (now BenQ) Benq 5560                                                 | 5        | 1.27%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 4        | 1.02%   |
| HP ScanJet 3800c                                                                      | 4        | 1.02%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 4        | 1.02%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 3        | 0.76%   |
| HP ScanJet 3970c                                                                      | 3        | 0.76%   |
| HP ScanJet 2200c                                                                      | 3        | 0.76%   |
| HP PSC 1200                                                                           | 3        | 0.76%   |
| Fujitsu ScanSnap SV600                                                                | 3        | 0.76%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 3        | 0.76%   |
| Canon CanoScan LiDE 90                                                                | 3        | 0.76%   |
| Canon CanoScan LiDE 70                                                                | 3        | 0.76%   |
| Acer Peripherals (now BenQ) Benq 5000                                                 | 3        | 0.76%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 2        | 0.51%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 2        | 0.51%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 2        | 0.51%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 2        | 0.51%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Logitech                        | 1004     | 32.65%  |
| Z-Star Microelectronics         | 589      | 19.15%  |
| Microdia                        | 261      | 8.49%   |
| Microsoft                       | 158      | 5.14%   |
| KYE Systems (Mouse Systems)     | 120      | 3.9%    |
| Cubeternet                      | 97       | 3.15%   |
| Pixart Imaging                  | 96       | 3.12%   |
| Aveo Technology                 | 96       | 3.12%   |
| Arkmicro Technologies           | 96       | 3.12%   |
| GEMBIRD                         | 77       | 2.5%    |
| Chicony Electronics             | 52       | 1.69%   |
| Realtek Semiconductor           | 44       | 1.43%   |
| Samsung Electronics             | 40       | 1.3%    |
| Creative Technology             | 37       | 1.2%    |
| Alcor Micro                     | 30       | 0.98%   |
| Apple                           | 29       | 0.94%   |
| Guillemot                       | 20       | 0.65%   |
| Genesys Logic                   | 18       | 0.59%   |
| Philips (or NXP)                | 17       | 0.55%   |
| Hewlett-Packard                 | 15       | 0.49%   |
| Silicon Motion                  | 14       | 0.46%   |
| Nokia Mobile Phones             | 13       | 0.42%   |
| Sunplus Innovation Technology   | 12       | 0.39%   |
| SiGma Micro                     | 10       | 0.33%   |
| IMC Networks                    | 10       | 0.33%   |
| Generalplus Technology          | 8        | 0.26%   |
| Trust                           | 7        | 0.23%   |
| A4Tech                          | 7        | 0.23%   |
| Acer                            | 6        | 0.2%    |
| Suyin                           | 5        | 0.16%   |
| lihappe8                        | 5        | 0.16%   |
| Canon                           | 5        | 0.16%   |
| Unknown                         | 4        | 0.13%   |
| Google                          | 4        | 0.13%   |
| Fitipower Integrated Technology | 4        | 0.13%   |
| Sweex                           | 3        | 0.1%    |
| SunplusIT                       | 3        | 0.1%    |
| Sony                            | 3        | 0.1%    |
| Panasonic (Matsushita)          | 3        | 0.1%    |
| Fushicai                        | 3        | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 336      | 10.91%  |
| Z-Star Venus USB2.0 Camera                        | 270      | 8.76%   |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 158      | 5.13%   |
| Microdia Camera                                   | 140      | 4.54%   |
| Z-Star Vimicro USB Camera (Altair)                | 114      | 3.7%    |
| Logitech Webcam C170                              | 87       | 2.82%   |
| Arkmicro USB2.0 PC CAMERA                         | 87       | 2.82%   |
| Logitech Webcam C310                              | 80       | 2.6%    |
| Logitech Webcam C210                              | 80       | 2.6%    |
| Pixart Imaging GE 1.3 MP MiniCam Pro              | 72       | 2.34%   |
| Logitech HD Webcam C525                           | 62       | 2.01%   |
| Cubeternet GL-UPC822 UVC WebCam                   | 52       | 1.69%   |
| Microsoft LifeCam HD-3000                         | 49       | 1.59%   |
| Logitech Webcam C110                              | 48       | 1.56%   |
| Microdia Sonix USB 2.0 Camera                     | 45       | 1.46%   |
| GEMBIRD USB2.0 PC CAMERA                          | 43       | 1.4%    |
| Samsung Galaxy A5 (MTP)                           | 38       | 1.23%   |
| Logitech HD Webcam C510                           | 33       | 1.07%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 33       | 1.07%   |
| Aveo USB2.0 Camera                                | 33       | 1.07%   |
| Aveo Camera                                       | 33       | 1.07%   |
| Microdia USB 2.0 Camera                           | 32       | 1.04%   |
| Logitech HD Pro Webcam C920                       | 30       | 0.97%   |
| Microsoft LifeCam VX-800                          | 28       | 0.91%   |
| Logitech Logitech Webcam C100                     | 28       | 0.91%   |
| Cubeternet USB2.0 Camera                          | 28       | 0.91%   |
| Logitech Logitech Webcam C160                     | 27       | 0.88%   |
| Aveo UVC camera (Bresser microscope)              | 26       | 0.84%   |
| Realtek Full HD webcam                            | 25       | 0.81%   |
| Logitech Webcam C250                              | 22       | 0.71%   |
| Apple iPhone 5/5C/5S/6/SE                         | 22       | 0.71%   |
| Alcor Micro USB 2.0 PC Camera                     | 22       | 0.71%   |
| Microsoft LifeCam VX-2000                         | 20       | 0.65%   |
| Microdia MSI Starcam Racer                        | 19       | 0.62%   |
| Logitech Webcam C120                              | 19       | 0.62%   |
| Logitech HD Webcam C910                           | 19       | 0.62%   |
| Logitech Webcam C200                              | 18       | 0.58%   |
| Logitech HD Webcam C615                           | 18       | 0.58%   |
| Microsoft LifeCam HD-5000                         | 17       | 0.55%   |
| Genesys Logic Camera                              | 15       | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| STMicroelectronics    | 2        | 33.33%  |
| Microsoft             | 2        | 33.33%  |
| LighTuning Technology | 1        | 16.67%  |
| DigitalPersona        | 1        | 16.67%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| STMicroelectronics Fingerprint Reader            | 2        | 33.33%  |
| Microsoft Fingerprint Reader                     | 2        | 33.33%  |
| LighTuning ES603 Swipe Fingerprint Sensor        | 1        | 16.67%  |
| DigitalPersona Fingerprint Scanner, U.are.U 2000 | 1        | 16.67%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Aladdin Knowledge Systems               | 11       | 18.64%  |
| Alcor Micro                             | 10       | 16.95%  |
| Advanced Card Systems                   | 9        | 15.25%  |
| Aktiv                                   | 7        | 11.86%  |
| OmniKey                                 | 5        | 8.47%   |
| Realtek Semiconductor                   | 4        | 6.78%   |
| Athena Smartcard Solutions              | 4        | 6.78%   |
| Castles Technology                      | 2        | 3.39%   |
| Reiner SCT Kartensysteme                | 1        | 1.69%   |
| Gemalto (was Gemplus)                   | 1        | 1.69%   |
| Future Technology Devices International | 1        | 1.69%   |
| Cherry                                  | 1        | 1.69%   |
| BIFIT                                   | 1        | 1.69%   |
| Avtor                                   | 1        | 1.69%   |
| Aladdin R.D.                            | 1        | 1.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Aladdin Knowledge Systems Token JC                                         | 11       | 18.64%  |
| Alcor Micro Watchdata W 1981                                               | 7        | 11.86%  |
| Aktiv Rutoken lite                                                         | 6        | 10.17%  |
| Realtek Semiconductor Smart Card Reader Interface                          | 4        | 6.78%   |
| OmniKey CardMan 1021                                                       | 4        | 6.78%   |
| Athena Smartcard Solutions ASEDrive CCID                                   | 4        | 6.78%   |
| Alcor Micro AU9540 Smartcard Reader                                        | 3        | 5.08%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 3        | 5.08%   |
| Castles Technology EZCCID Smart Card Reader                                | 2        | 3.39%   |
| Advanced Card Systems Token USB 64K                                        | 2        | 3.39%   |
| Advanced Card Systems ACR3901U                                             | 2        | 3.39%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 1        | 1.69%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 1.69%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 1.69%   |
| Future Technology Devices International Parsec Desktop Reader PR-EH08      | 1        | 1.69%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                | 1        | 1.69%   |
| BIFIT iBank2Key                                                            | 1        | 1.69%   |
| Avtor SecureToken                                                          | 1        | 1.69%   |
| Aladdin R.D. JaCarta                                                       | 1        | 1.69%   |
| Aktiv KAZTOKEN                                                             | 1        | 1.69%   |
| Advanced Card Systems ACR39U                                               | 1        | 1.69%   |
| Advanced Card Systems ACR1281 1S Dual Reader                               | 1        | 1.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 11483    | 86.44%  |
| 1     | 1643     | 12.37%  |
| 2     | 139      | 1.05%   |
| 3     | 17       | 0.13%   |
| 9     | 1        | 0.01%   |
| 7     | 1        | 0.01%   |
| 4     | 1        | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 1153     | 60.3%   |
| Net/wireless             | 205      | 10.72%  |
| Communication controller | 158      | 8.26%   |
| Multimedia controller    | 106      | 5.54%   |
| Camera                   | 63       | 3.29%   |
| Chipcard                 | 52       | 2.72%   |
| Unassigned class         | 51       | 2.67%   |
| Modem                    | 28       | 1.46%   |
| Sound                    | 23       | 1.2%    |
| Dvb card                 | 13       | 0.68%   |
| Network                  | 12       | 0.63%   |
| Bluetooth                | 10       | 0.52%   |
| Net/ethernet             | 9        | 0.47%   |
| Tv card                  | 5        | 0.26%   |
| Card reader              | 5        | 0.26%   |
| Storage/raid             | 4        | 0.21%   |
| Storage/ata              | 4        | 0.21%   |
| Storage                  | 4        | 0.21%   |
| Fingerprint reader       | 4        | 0.21%   |
| Video                    | 2        | 0.1%    |
| Storage/ide              | 1        | 0.05%   |

