Linux in Brazil - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

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

Total: 7729

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B450M GAMING                | [7974075b64](https://linux-hardware.org/?probe=7974075b64) | Nov 06, 2023 |
| ASRock        | Z97 Killer                  | [f575f3121e](https://linux-hardware.org/?probe=f575f3121e) | Nov 06, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [99a6c38b5d](https://linux-hardware.org/?probe=99a6c38b5d) | Nov 05, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [c520e5a3b2](https://linux-hardware.org/?probe=c520e5a3b2) | Nov 05, 2023 |
| Dell          | 01XK1W A00                  | [d6cd277a79](https://linux-hardware.org/?probe=d6cd277a79) | Nov 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [f45893cbf7](https://linux-hardware.org/?probe=f45893cbf7) | Nov 05, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [459eb3cd2a](https://linux-hardware.org/?probe=459eb3cd2a) | Nov 04, 2023 |
| Toshiba       | STI 001359                  | [ebf464dbb3](https://linux-hardware.org/?probe=ebf464dbb3) | Nov 04, 2023 |
| ASUSTek       | PRIME X470-PRO              | [c1523fb6a1](https://linux-hardware.org/?probe=c1523fb6a1) | Nov 04, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [baf30122ca](https://linux-hardware.org/?probe=baf30122ca) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [2aa4f1a7f7](https://linux-hardware.org/?probe=2aa4f1a7f7) | Nov 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [a08b1cfa29](https://linux-hardware.org/?probe=a08b1cfa29) | Nov 03, 2023 |
| HP            | 0B54h D                     | [4ec7776a76](https://linux-hardware.org/?probe=4ec7776a76) | Nov 02, 2023 |
| ASRock        | H81M-HG4 R4.0               | [0f5f162498](https://linux-hardware.org/?probe=0f5f162498) | Nov 02, 2023 |
| ASUSTek       | PRIME H510M-D               | [d6749e3f8b](https://linux-hardware.org/?probe=d6749e3f8b) | Nov 01, 2023 |
| Gigabyte      | B75M-HD3                    | [e27c813285](https://linux-hardware.org/?probe=e27c813285) | Oct 31, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [d735ec288c](https://linux-hardware.org/?probe=d735ec288c) | Oct 31, 2023 |
| AMD           | A88K                        | [963e38ef9a](https://linux-hardware.org/?probe=963e38ef9a) | Oct 31, 2023 |
| Gigabyte      | B450M GAMING                | [ac709dc975](https://linux-hardware.org/?probe=ac709dc975) | Oct 31, 2023 |
| ASUSTek       | H81M-C/BR                   | [b92870ed6a](https://linux-hardware.org/?probe=b92870ed6a) | Oct 31, 2023 |
| Intel         | H61                         | [0f282da58e](https://linux-hardware.org/?probe=0f282da58e) | Oct 30, 2023 |
| Intel         | B75                         | [a46db29108](https://linux-hardware.org/?probe=a46db29108) | Oct 29, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [3ea0191175](https://linux-hardware.org/?probe=3ea0191175) | Oct 29, 2023 |
| Intel         | B75                         | [7b6b287377](https://linux-hardware.org/?probe=7b6b287377) | Oct 28, 2023 |
| Intel         | JSL MRD                     | [689d88c57b](https://linux-hardware.org/?probe=689d88c57b) | Oct 28, 2023 |
| Dell          | 076VHM A02                  | [456e31167b](https://linux-hardware.org/?probe=456e31167b) | Oct 28, 2023 |
| Unknown       | Phitronics G31VS-M          | [10bcfab3cb](https://linux-hardware.org/?probe=10bcfab3cb) | Oct 28, 2023 |
| Intel         | H61                         | [1496665abb](https://linux-hardware.org/?probe=1496665abb) | Oct 27, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [5dac9d85f1](https://linux-hardware.org/?probe=5dac9d85f1) | Oct 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [1cb73bada5](https://linux-hardware.org/?probe=1cb73bada5) | Oct 27, 2023 |
| Intel         | H61                         | [fccff5fcb2](https://linux-hardware.org/?probe=fccff5fcb2) | Oct 27, 2023 |
| Gigabyte      | H110M-H-CF                  | [b64c6bb72a](https://linux-hardware.org/?probe=b64c6bb72a) | Oct 26, 2023 |
| Dell          | 0K240Y A04                  | [5bf155abe0](https://linux-hardware.org/?probe=5bf155abe0) | Oct 26, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [138843c6dc](https://linux-hardware.org/?probe=138843c6dc) | Oct 25, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [25c0172035](https://linux-hardware.org/?probe=25c0172035) | Oct 25, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [54a6d9d5d0](https://linux-hardware.org/?probe=54a6d9d5d0) | Oct 24, 2023 |
| Gigabyte      | B450M DS3H V2               | [f99b06d89a](https://linux-hardware.org/?probe=f99b06d89a) | Oct 24, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [61d3768e3f](https://linux-hardware.org/?probe=61d3768e3f) | Oct 24, 2023 |
| Danuri        | B550M-PX                    | [e24df1ad61](https://linux-hardware.org/?probe=e24df1ad61) | Oct 24, 2023 |
| Intel         | H61 V124                    | [034689793f](https://linux-hardware.org/?probe=034689793f) | Oct 24, 2023 |
| Intel         | H61 V124                    | [2405df9db3](https://linux-hardware.org/?probe=2405df9db3) | Oct 23, 2023 |
| AZW           | Gemini M                    | [31ec911dd7](https://linux-hardware.org/?probe=31ec911dd7) | Oct 23, 2023 |
| Gigabyte      | B450 AORUS M                | [e756845de4](https://linux-hardware.org/?probe=e756845de4) | Oct 23, 2023 |
| AZW           | BT3 X                       | [c1e3c10fc4](https://linux-hardware.org/?probe=c1e3c10fc4) | Oct 23, 2023 |
| AZW           | BT3 X                       | [78328e112b](https://linux-hardware.org/?probe=78328e112b) | Oct 23, 2023 |
| Biostar       | B450MH                      | [d082b0cf9d](https://linux-hardware.org/?probe=d082b0cf9d) | Oct 23, 2023 |
| Intel         | B75                         | [96f9a95f89](https://linux-hardware.org/?probe=96f9a95f89) | Oct 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [588ad7e7ef](https://linux-hardware.org/?probe=588ad7e7ef) | Oct 22, 2023 |
| Intel         | H81                         | [f9351663fb](https://linux-hardware.org/?probe=f9351663fb) | Oct 21, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [4f2229b9fa](https://linux-hardware.org/?probe=4f2229b9fa) | Oct 21, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [436e243db6](https://linux-hardware.org/?probe=436e243db6) | Oct 21, 2023 |
| Gigabyte      | H410M H V3                  | [0b9affbbb3](https://linux-hardware.org/?probe=0b9affbbb3) | Oct 21, 2023 |
| Gigabyte      | Z77-DS3H                    | [ca61a8649a](https://linux-hardware.org/?probe=ca61a8649a) | Oct 21, 2023 |
| Gigabyte      | Z77-DS3H                    | [6108985945](https://linux-hardware.org/?probe=6108985945) | Oct 21, 2023 |
| MACHINIST     | X99-MR9D PLUS V1.0          | [aaeff9a386](https://linux-hardware.org/?probe=aaeff9a386) | Oct 20, 2023 |
| Gigabyte      | 990XA-UD3 R5                | [c7d22a23d2](https://linux-hardware.org/?probe=c7d22a23d2) | Oct 20, 2023 |
| Lenovo        | 30D0 NOK                    | [e67eff74dc](https://linux-hardware.org/?probe=e67eff74dc) | Oct 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [6bb9b08c6e](https://linux-hardware.org/?probe=6bb9b08c6e) | Oct 20, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [3fd9b0b53f](https://linux-hardware.org/?probe=3fd9b0b53f) | Oct 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [3b1da376dc](https://linux-hardware.org/?probe=3b1da376dc) | Oct 19, 2023 |
| Gigabyte      | H87-D3H-CF                  | [b1f1e05664](https://linux-hardware.org/?probe=b1f1e05664) | Oct 19, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [d7ddb794ec](https://linux-hardware.org/?probe=d7ddb794ec) | Oct 18, 2023 |
| Gigabyte      | G41MT-S2                    | [50aa4fc1e1](https://linux-hardware.org/?probe=50aa4fc1e1) | Oct 18, 2023 |
| ASRock        | A320M-HD                    | [27d26a4a15](https://linux-hardware.org/?probe=27d26a4a15) | Oct 17, 2023 |
| Pegatron      | IPM41-D3                    | [54150823a1](https://linux-hardware.org/?probe=54150823a1) | Oct 17, 2023 |
| Pegatron      | IPM41-D3                    | [e567a72b4c](https://linux-hardware.org/?probe=e567a72b4c) | Oct 17, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | [da5796de02](https://linux-hardware.org/?probe=da5796de02) | Oct 17, 2023 |
| ASUSTek       | H61M-A/BR                   | [c615f7ee38](https://linux-hardware.org/?probe=c615f7ee38) | Oct 17, 2023 |
| Positivo      | POS-PIG43BC SIM             | [ded7e15a49](https://linux-hardware.org/?probe=ded7e15a49) | Oct 17, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [ac47775d14](https://linux-hardware.org/?probe=ac47775d14) | Oct 17, 2023 |
| Intel         | H61                         | [2bd77947d1](https://linux-hardware.org/?probe=2bd77947d1) | Oct 16, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [fb2bf1baa8](https://linux-hardware.org/?probe=fb2bf1baa8) | Oct 16, 2023 |
| ASRock        | N68-S3 FX                   | [b1a36d42aa](https://linux-hardware.org/?probe=b1a36d42aa) | Oct 16, 2023 |
| Biostar       | A320MH                      | [d797fd8fa3](https://linux-hardware.org/?probe=d797fd8fa3) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | [47788537bf](https://linux-hardware.org/?probe=47788537bf) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | [30723700f1](https://linux-hardware.org/?probe=30723700f1) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | [e4dc0eeb72](https://linux-hardware.org/?probe=e4dc0eeb72) | Oct 15, 2023 |
| ASRock        | A320M-DGS                   | [a9599537b8](https://linux-hardware.org/?probe=a9599537b8) | Oct 15, 2023 |
| Gigabyte      | B450 AORUS M                | [68075a7e8f](https://linux-hardware.org/?probe=68075a7e8f) | Oct 15, 2023 |
| PCWare        | IPMH61R1                    | [145dc39d14](https://linux-hardware.org/?probe=145dc39d14) | Oct 14, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [42e5a09fe2](https://linux-hardware.org/?probe=42e5a09fe2) | Oct 14, 2023 |
| Gigabyte      | B450M GAMING                | [4280b509c6](https://linux-hardware.org/?probe=4280b509c6) | Oct 14, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [0a86fd4e1d](https://linux-hardware.org/?probe=0a86fd4e1d) | Oct 14, 2023 |
| Gigabyte      | G41MT-S2                    | [d45a6f5bf2](https://linux-hardware.org/?probe=d45a6f5bf2) | Oct 14, 2023 |
| Gigabyte      | B450M GAMING                | [06aa8e692c](https://linux-hardware.org/?probe=06aa8e692c) | Oct 14, 2023 |
| Unknown       | MZ-B75-S                    | [6d58c79c33](https://linux-hardware.org/?probe=6d58c79c33) | Oct 13, 2023 |
| MSI           | H110M PRO-VH PLUS           | [7d186ff304](https://linux-hardware.org/?probe=7d186ff304) | Oct 13, 2023 |
| ASRock        | A320M-HD                    | [2b45321310](https://linux-hardware.org/?probe=2b45321310) | Oct 13, 2023 |
| ASRock        | A320M-HD R4.0               | [1b1dd0c7fd](https://linux-hardware.org/?probe=1b1dd0c7fd) | Oct 12, 2023 |
| Gigabyte      | B550M AORUS PRO             | [d7d6c5206f](https://linux-hardware.org/?probe=d7d6c5206f) | Oct 12, 2023 |
| Gigabyte      | 970A-UD3P                   | [34792695eb](https://linux-hardware.org/?probe=34792695eb) | Oct 12, 2023 |
| Gigabyte      | B550M AORUS PRO             | [5e2f8bdc4d](https://linux-hardware.org/?probe=5e2f8bdc4d) | Oct 12, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [b71efdb817](https://linux-hardware.org/?probe=b71efdb817) | Oct 11, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [a6e6952b42](https://linux-hardware.org/?probe=a6e6952b42) | Oct 11, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [89ae9695ef](https://linux-hardware.org/?probe=89ae9695ef) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [5566e985cf](https://linux-hardware.org/?probe=5566e985cf) | Oct 11, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [835f369588](https://linux-hardware.org/?probe=835f369588) | Oct 11, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [9acd34e892](https://linux-hardware.org/?probe=9acd34e892) | Oct 11, 2023 |
| Positivo      | POS-PIH110DV                | [f45f2f425b](https://linux-hardware.org/?probe=f45f2f425b) | Oct 10, 2023 |
| Gigabyte      | B550M AORUS PRO             | [c39ce018d6](https://linux-hardware.org/?probe=c39ce018d6) | Oct 10, 2023 |
| MSI           | A320M-A PRO                 | [4a1888b421](https://linux-hardware.org/?probe=4a1888b421) | Oct 09, 2023 |
| Dell          | 0478VN A00                  | [8881cc216c](https://linux-hardware.org/?probe=8881cc216c) | Oct 09, 2023 |
| Gigabyte      | 945GZM-S2                   | [f9bafdf396](https://linux-hardware.org/?probe=f9bafdf396) | Oct 09, 2023 |
| MACHINIST     | E5-MR9A V1.0                | [4be00bee3e](https://linux-hardware.org/?probe=4be00bee3e) | Oct 09, 2023 |
| ASRock        | A320M-HD R4.0               | [84fc58ce28](https://linux-hardware.org/?probe=84fc58ce28) | Oct 08, 2023 |
| Itautec       | SM 3321 SM-3321 Padrao 0... | [923cec3568](https://linux-hardware.org/?probe=923cec3568) | Oct 08, 2023 |
| Intel         | DG41WV AAE90316-102         | [c666aa6077](https://linux-hardware.org/?probe=c666aa6077) | Oct 08, 2023 |
| Unknown       | Unknown                     | [1eeecb8823](https://linux-hardware.org/?probe=1eeecb8823) | Oct 08, 2023 |
| ASUSTek       | H81M-A/BR                   | [b580accff5](https://linux-hardware.org/?probe=b580accff5) | Oct 08, 2023 |
| MACHINIST     | E5-MR9A V1.0                | [68e7f53229](https://linux-hardware.org/?probe=68e7f53229) | Oct 08, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [687287904f](https://linux-hardware.org/?probe=687287904f) | Oct 08, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [1756f5ba93](https://linux-hardware.org/?probe=1756f5ba93) | Oct 08, 2023 |
| ASRock        | Z77 Extreme4                | [e1cfe6d474](https://linux-hardware.org/?probe=e1cfe6d474) | Oct 08, 2023 |
| ASRock        | A320M-HD                    | [c59dc86e48](https://linux-hardware.org/?probe=c59dc86e48) | Oct 08, 2023 |
| Unknown       | Phitronics G31VS-M          | [7b7ac9e326](https://linux-hardware.org/?probe=7b7ac9e326) | Oct 07, 2023 |
| ASUSTek       | BM1AF_BP1AF_BM6AF           | [bad5263013](https://linux-hardware.org/?probe=bad5263013) | Oct 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [40c01d2bf5](https://linux-hardware.org/?probe=40c01d2bf5) | Oct 07, 2023 |
| Gigabyte      | A520M K V2                  | [839ad0c4b6](https://linux-hardware.org/?probe=839ad0c4b6) | Oct 07, 2023 |
| Gigabyte      | A520M K V2                  | [f3e7c14b62](https://linux-hardware.org/?probe=f3e7c14b62) | Oct 07, 2023 |
| Intel         | H61                         | [1abb1c8f57](https://linux-hardware.org/?probe=1abb1c8f57) | Oct 06, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [45a4c0fbe0](https://linux-hardware.org/?probe=45a4c0fbe0) | Oct 06, 2023 |
| Dell          | 0478VN A00                  | [511df57852](https://linux-hardware.org/?probe=511df57852) | Oct 05, 2023 |
| Biostar       | B450MH                      | [b47659f758](https://linux-hardware.org/?probe=b47659f758) | Oct 05, 2023 |
| Positivo      | POS-EINM70CS POSITIVO       | [fc6322811e](https://linux-hardware.org/?probe=fc6322811e) | Oct 04, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [80010c71e1](https://linux-hardware.org/?probe=80010c71e1) | Oct 04, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a72a2ee89e](https://linux-hardware.org/?probe=a72a2ee89e) | Oct 04, 2023 |
| Gigabyte      | F2A88X-D3H                  | [6ea97d511f](https://linux-hardware.org/?probe=6ea97d511f) | Oct 04, 2023 |
| Lenovo        | NOK                         | [dd6bffed79](https://linux-hardware.org/?probe=dd6bffed79) | Oct 04, 2023 |
| Gigabyte      | B85M-D3H                    | [8356867b4d](https://linux-hardware.org/?probe=8356867b4d) | Oct 04, 2023 |
| Dell          | 0P0MXR A00                  | [06af26dae3](https://linux-hardware.org/?probe=06af26dae3) | Oct 03, 2023 |
| Dell          | 0P0MXR A00                  | [9b4bfad0cc](https://linux-hardware.org/?probe=9b4bfad0cc) | Oct 03, 2023 |
| Unknown       | Phitronics G31VS-M          | [a30a4e0d2e](https://linux-hardware.org/?probe=a30a4e0d2e) | Oct 03, 2023 |
| Intel         | H61                         | [977f3d58ab](https://linux-hardware.org/?probe=977f3d58ab) | Oct 03, 2023 |
| Dell          | 07PR60 A01                  | [020c2fbbf8](https://linux-hardware.org/?probe=020c2fbbf8) | Oct 02, 2023 |
| ASUSTek       | B150M-C/BR                  | [2435f20a18](https://linux-hardware.org/?probe=2435f20a18) | Oct 02, 2023 |
| ASRock        | H370M-ITX/ac                | [cf9e8e26c2](https://linux-hardware.org/?probe=cf9e8e26c2) | Oct 02, 2023 |
| Pegatron      | SM3330 0112                 | [290983ac13](https://linux-hardware.org/?probe=290983ac13) | Oct 01, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [27e61d282f](https://linux-hardware.org/?probe=27e61d282f) | Oct 01, 2023 |
| Toshiba       | STI 009169                  | [0b76bae8f3](https://linux-hardware.org/?probe=0b76bae8f3) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [f3d279f91b](https://linux-hardware.org/?probe=f3d279f91b) | Sep 30, 2023 |
| ASRock        | A320M-DGS                   | [63aafe31f1](https://linux-hardware.org/?probe=63aafe31f1) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [02af70281a](https://linux-hardware.org/?probe=02af70281a) | Sep 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [770e7037d3](https://linux-hardware.org/?probe=770e7037d3) | Sep 30, 2023 |
| Unknown       | Phitronics N68C-M           | [72b5c903d3](https://linux-hardware.org/?probe=72b5c903d3) | Sep 30, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [74bed86ee5](https://linux-hardware.org/?probe=74bed86ee5) | Sep 30, 2023 |
| Intel         | H61                         | [f6a417439c](https://linux-hardware.org/?probe=f6a417439c) | Sep 29, 2023 |
| Intel         | H61                         | [e7dac2f9ed](https://linux-hardware.org/?probe=e7dac2f9ed) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [6177caee37](https://linux-hardware.org/?probe=6177caee37) | Sep 29, 2023 |
| Positivo      | POS-PIH81DI                 | [0e67f3a0f3](https://linux-hardware.org/?probe=0e67f3a0f3) | Sep 29, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [51272b2713](https://linux-hardware.org/?probe=51272b2713) | Sep 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ce3a9f8960](https://linux-hardware.org/?probe=ce3a9f8960) | Sep 28, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [62ba806672](https://linux-hardware.org/?probe=62ba806672) | Sep 28, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [1509f60079](https://linux-hardware.org/?probe=1509f60079) | Sep 28, 2023 |
| Positivo      | POS-RIH470EM 11179450       | [cf8e3e73bb](https://linux-hardware.org/?probe=cf8e3e73bb) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [546df5b57f](https://linux-hardware.org/?probe=546df5b57f) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [503570ad7a](https://linux-hardware.org/?probe=503570ad7a) | Sep 27, 2023 |
| Unknown       | Unknown                     | [cb12d6c853](https://linux-hardware.org/?probe=cb12d6c853) | Sep 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [f47347fb9b](https://linux-hardware.org/?probe=f47347fb9b) | Sep 27, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [811818acb8](https://linux-hardware.org/?probe=811818acb8) | Sep 26, 2023 |
| Huanan        | X99-8M-F V1.2               | [4ddba514a1](https://linux-hardware.org/?probe=4ddba514a1) | Sep 26, 2023 |
| Intel         | H61                         | [ee0266b53c](https://linux-hardware.org/?probe=ee0266b53c) | Sep 25, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [0b586071f1](https://linux-hardware.org/?probe=0b586071f1) | Sep 25, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [fee2fdb49a](https://linux-hardware.org/?probe=fee2fdb49a) | Sep 25, 2023 |
| Gigabyte      | H310M M.2 x.x               | [69cccf347a](https://linux-hardware.org/?probe=69cccf347a) | Sep 25, 2023 |
| OEM           | B75 Ver:1.41                | [01109ec772](https://linux-hardware.org/?probe=01109ec772) | Sep 24, 2023 |
| Lenovo        | ThinkCentre A70z 0401B7P    | [21a635940f](https://linux-hardware.org/?probe=21a635940f) | Sep 24, 2023 |
| PCWare        | APM-A320G                   | [64080404a6](https://linux-hardware.org/?probe=64080404a6) | Sep 24, 2023 |
| Gigabyte      | 945GCM-S2C                  | [9f17460970](https://linux-hardware.org/?probe=9f17460970) | Sep 24, 2023 |
| HOUTER        | OROPC                       | [96625070be](https://linux-hardware.org/?probe=96625070be) | Sep 24, 2023 |
| Positivo      | POS-EIBTPDC                 | [3c2427ba03](https://linux-hardware.org/?probe=3c2427ba03) | Sep 23, 2023 |
| Positivo      | POS-EIBTPDC                 | [586c05976a](https://linux-hardware.org/?probe=586c05976a) | Sep 23, 2023 |
| HOUTER        | OROPC                       | [3f78fb9290](https://linux-hardware.org/?probe=3f78fb9290) | Sep 23, 2023 |
| ASUSTek       | A88XM-A                     | [c2cb8052f9](https://linux-hardware.org/?probe=c2cb8052f9) | Sep 23, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | [fbeac0cab4](https://linux-hardware.org/?probe=fbeac0cab4) | Sep 23, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [47e5429752](https://linux-hardware.org/?probe=47e5429752) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [a35f78cead](https://linux-hardware.org/?probe=a35f78cead) | Sep 21, 2023 |
| Positivo      | POS-AG31AP                  | [2e2072e3ca](https://linux-hardware.org/?probe=2e2072e3ca) | Sep 21, 2023 |
| Megaware      | MW-HDC-M 02/24/2012 - ME... | [d3c9063140](https://linux-hardware.org/?probe=d3c9063140) | Sep 21, 2023 |
| Intel         | B75                         | [37b59e6605](https://linux-hardware.org/?probe=37b59e6605) | Sep 21, 2023 |
| Gigabyte      | B450 AORUS M                | [e2dda8ebb1](https://linux-hardware.org/?probe=e2dda8ebb1) | Sep 21, 2023 |
| Intel         | H55                         | [03693f8574](https://linux-hardware.org/?probe=03693f8574) | Sep 21, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [5e05853c00](https://linux-hardware.org/?probe=5e05853c00) | Sep 20, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [f7629203e7](https://linux-hardware.org/?probe=f7629203e7) | Sep 20, 2023 |
| ASRock        | A320M-HD                    | [01d8f27500](https://linux-hardware.org/?probe=01d8f27500) | Sep 20, 2023 |
| Dell          | 06HR05 A00                  | [a01d6b8630](https://linux-hardware.org/?probe=a01d6b8630) | Sep 20, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [6d9002e7e3](https://linux-hardware.org/?probe=6d9002e7e3) | Sep 19, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [c53d44303e](https://linux-hardware.org/?probe=c53d44303e) | Sep 19, 2023 |
| wpc           | zrd616                      | [f218d73abb](https://linux-hardware.org/?probe=f218d73abb) | Sep 19, 2023 |
| Biostar       | B550GTQ                     | [5478c7bc91](https://linux-hardware.org/?probe=5478c7bc91) | Sep 19, 2023 |
| MSI           | A320M-A PRO                 | [6588973c54](https://linux-hardware.org/?probe=6588973c54) | Sep 19, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [1bd2a17c99](https://linux-hardware.org/?probe=1bd2a17c99) | Sep 19, 2023 |
| Biostar       | H61MLC                      | [154ead8447](https://linux-hardware.org/?probe=154ead8447) | Sep 19, 2023 |
| ASRock        | A320M-HD                    | [00ce48a639](https://linux-hardware.org/?probe=00ce48a639) | Sep 19, 2023 |
| Dell          | 076VHM A02                  | [518361bbc5](https://linux-hardware.org/?probe=518361bbc5) | Sep 18, 2023 |
| Positivo      | POS-EIH610EX 11187943       | [10fbe8fd9b](https://linux-hardware.org/?probe=10fbe8fd9b) | Sep 18, 2023 |
| Kllisre       | X99-B5 V1.1                 | [5597daf348](https://linux-hardware.org/?probe=5597daf348) | Sep 18, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [1875fb96e5](https://linux-hardware.org/?probe=1875fb96e5) | Sep 17, 2023 |
| ASUSTek       | M5A78L/USB3                 | [e1805d26c3](https://linux-hardware.org/?probe=e1805d26c3) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [d4d891ca35](https://linux-hardware.org/?probe=d4d891ca35) | Sep 17, 2023 |
| ASRock        | B450 Pro4                   | [2e8cd612d8](https://linux-hardware.org/?probe=2e8cd612d8) | Sep 17, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [1e71e60505](https://linux-hardware.org/?probe=1e71e60505) | Sep 17, 2023 |
| ASRock        | A320M-HD                    | [8db77afc82](https://linux-hardware.org/?probe=8db77afc82) | Sep 17, 2023 |
| ANGXUN        | X99 V1.0                    | [c6c6277bf3](https://linux-hardware.org/?probe=c6c6277bf3) | Sep 17, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [656da36be3](https://linux-hardware.org/?probe=656da36be3) | Sep 17, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [6f73b0398c](https://linux-hardware.org/?probe=6f73b0398c) | Sep 16, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [7b10a3651b](https://linux-hardware.org/?probe=7b10a3651b) | Sep 16, 2023 |
| Biostar       | X370GTN                     | [1ac44acadd](https://linux-hardware.org/?probe=1ac44acadd) | Sep 16, 2023 |
| Dell          | 0VTJVC A00                  | [8a404c05c2](https://linux-hardware.org/?probe=8a404c05c2) | Sep 15, 2023 |
| MSI           | H310M PRO-VDH               | [100f789658](https://linux-hardware.org/?probe=100f789658) | Sep 15, 2023 |
| Positivo      | POS-RIB360EE 11144907       | [8c1887fa93](https://linux-hardware.org/?probe=8c1887fa93) | Sep 15, 2023 |
| Gigabyte      | A320M-S2H-CF                | [e484eea129](https://linux-hardware.org/?probe=e484eea129) | Sep 14, 2023 |
| Foxconn       | 45GM/45CM/45CM-S            | [135712cd9e](https://linux-hardware.org/?probe=135712cd9e) | Sep 14, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [cbe7fd494b](https://linux-hardware.org/?probe=cbe7fd494b) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [9fde2c205d](https://linux-hardware.org/?probe=9fde2c205d) | Sep 14, 2023 |
| Intel         | H61                         | [5dd60be36a](https://linux-hardware.org/?probe=5dd60be36a) | Sep 14, 2023 |
| Pegatron      | 2AC3                        | [4cee44e8ac](https://linux-hardware.org/?probe=4cee44e8ac) | Sep 13, 2023 |
| HOUTER        | OROPC                       | [711d8f8d80](https://linux-hardware.org/?probe=711d8f8d80) | Sep 13, 2023 |
| Dell          | 01XK1W A00                  | [07e5f3eb14](https://linux-hardware.org/?probe=07e5f3eb14) | Sep 13, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | [3c36dccf79](https://linux-hardware.org/?probe=3c36dccf79) | Sep 12, 2023 |
| Gigabyte      | H110M-H-CF                  | [31cc220aae](https://linux-hardware.org/?probe=31cc220aae) | Sep 12, 2023 |
| Pegatron      | IPMSB-VH1/HDMI/ODM          | [fd4e189b56](https://linux-hardware.org/?probe=fd4e189b56) | Sep 12, 2023 |
| Intel         | H61                         | [513ebd18a2](https://linux-hardware.org/?probe=513ebd18a2) | Sep 12, 2023 |
| Intel         | H61                         | [fec08a2214](https://linux-hardware.org/?probe=fec08a2214) | Sep 12, 2023 |
| PCWare        | IPMH81G1                    | [181367c2db](https://linux-hardware.org/?probe=181367c2db) | Sep 12, 2023 |
| ASUSTek       | P8H77-M                     | [61dc55f063](https://linux-hardware.org/?probe=61dc55f063) | Sep 11, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [c780b34220](https://linux-hardware.org/?probe=c780b34220) | Sep 11, 2023 |
| Gigabyte      | H610M H DDR4                | [e3e2a65f4a](https://linux-hardware.org/?probe=e3e2a65f4a) | Sep 11, 2023 |
| Dell          | 0YXT71 A01                  | [36991ac5a6](https://linux-hardware.org/?probe=36991ac5a6) | Sep 11, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [7f5f0fccd0](https://linux-hardware.org/?probe=7f5f0fccd0) | Sep 11, 2023 |
| Philco        | DTC-A55                     | [30cdd25bb0](https://linux-hardware.org/?probe=30cdd25bb0) | Sep 11, 2023 |
| Login Info... | LOG-H61H2-M2                | [fa6e51b9bf](https://linux-hardware.org/?probe=fa6e51b9bf) | Sep 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [772c3204b4](https://linux-hardware.org/?probe=772c3204b4) | Sep 10, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [6dc842bbb4](https://linux-hardware.org/?probe=6dc842bbb4) | Sep 10, 2023 |
| Daten Tecn... | DA75PRO                     | [343cbab6e9](https://linux-hardware.org/?probe=343cbab6e9) | Sep 10, 2023 |
| Unknown       | Unknown                     | [bc06d42fa2](https://linux-hardware.org/?probe=bc06d42fa2) | Sep 10, 2023 |
| Unknown       | Unknown                     | [2f9aef143e](https://linux-hardware.org/?probe=2f9aef143e) | Sep 10, 2023 |
| Gigabyte      | X570 GAMING X               | [8e988d79b7](https://linux-hardware.org/?probe=8e988d79b7) | Sep 09, 2023 |
| Intel         | H61                         | [f8eaac6637](https://linux-hardware.org/?probe=f8eaac6637) | Sep 09, 2023 |
| ASUSTek       | P8H77-M                     | [0916725ace](https://linux-hardware.org/?probe=0916725ace) | Sep 09, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | [87971ac772](https://linux-hardware.org/?probe=87971ac772) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [8723b09478](https://linux-hardware.org/?probe=8723b09478) | Sep 09, 2023 |
| MSI           | MAG B560M BAZOOKA           | [c3ba2033e2](https://linux-hardware.org/?probe=c3ba2033e2) | Sep 09, 2023 |
| ASUSTek       | P8H61-M LX2 R2.0            | [9d0bacfabd](https://linux-hardware.org/?probe=9d0bacfabd) | Sep 09, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [2b74633199](https://linux-hardware.org/?probe=2b74633199) | Sep 09, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3bb12f9fa5](https://linux-hardware.org/?probe=3bb12f9fa5) | Sep 09, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [0c30921512](https://linux-hardware.org/?probe=0c30921512) | Sep 08, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [6dbe579385](https://linux-hardware.org/?probe=6dbe579385) | Sep 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [edf1e3f8c4](https://linux-hardware.org/?probe=edf1e3f8c4) | Sep 08, 2023 |
| ECS           | BSWI-D2                     | [0bf71b9f12](https://linux-hardware.org/?probe=0bf71b9f12) | Sep 08, 2023 |
| MACHINIST     | X99-RS9 V2.0                | [8fc5475fd3](https://linux-hardware.org/?probe=8fc5475fd3) | Sep 08, 2023 |
| Intel         | H61                         | [929cfae9af](https://linux-hardware.org/?probe=929cfae9af) | Sep 08, 2023 |
| Intel         | HM570                       | [ea25bde02e](https://linux-hardware.org/?probe=ea25bde02e) | Sep 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [2b734c4a23](https://linux-hardware.org/?probe=2b734c4a23) | Sep 07, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [d98f5a5a06](https://linux-hardware.org/?probe=d98f5a5a06) | Sep 07, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [35b6b3a9dd](https://linux-hardware.org/?probe=35b6b3a9dd) | Sep 07, 2023 |
| Gigabyte      | G31M-S2C                    | [a7fb813c79](https://linux-hardware.org/?probe=a7fb813c79) | Sep 07, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [a4624a95da](https://linux-hardware.org/?probe=a4624a95da) | Sep 07, 2023 |
| ASUSTek       | PRIME H510M-E               | [0be77d9ece](https://linux-hardware.org/?probe=0be77d9ece) | Sep 07, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [f8453df937](https://linux-hardware.org/?probe=f8453df937) | Sep 07, 2023 |
| Toshiba       | STI 006998G                 | [d34aadcc92](https://linux-hardware.org/?probe=d34aadcc92) | Sep 07, 2023 |
| ASRock        | Z97 Killer                  | [a1537a06ee](https://linux-hardware.org/?probe=a1537a06ee) | Sep 07, 2023 |
| ASUSTek       | P8H77-M                     | [ebc8d3e851](https://linux-hardware.org/?probe=ebc8d3e851) | Sep 06, 2023 |
| HP            | 3047h                       | [9b6ecf8471](https://linux-hardware.org/?probe=9b6ecf8471) | Sep 06, 2023 |
| HP            | 3047h                       | [51ba95dc5a](https://linux-hardware.org/?probe=51ba95dc5a) | Sep 06, 2023 |
| Biostar       | G31M+                       | [24eb0eb2db](https://linux-hardware.org/?probe=24eb0eb2db) | Sep 06, 2023 |
| HP            | 0B54h D                     | [978ff127e9](https://linux-hardware.org/?probe=978ff127e9) | Sep 05, 2023 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [4a055a6f9c](https://linux-hardware.org/?probe=4a055a6f9c) | Sep 05, 2023 |
| Biostar       | A320MH                      | [1907707516](https://linux-hardware.org/?probe=1907707516) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [a64157168e](https://linux-hardware.org/?probe=a64157168e) | Sep 05, 2023 |
| Biostar       | A320MH                      | [f13f5f9fe9](https://linux-hardware.org/?probe=f13f5f9fe9) | Sep 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [190675e9f1](https://linux-hardware.org/?probe=190675e9f1) | Sep 05, 2023 |
| Intel         | DH55TC AAE70932-206         | [0576ca20ab](https://linux-hardware.org/?probe=0576ca20ab) | Sep 05, 2023 |
| Intel         | DH55TC AAE70932-206         | [710c22af52](https://linux-hardware.org/?probe=710c22af52) | Sep 05, 2023 |
| ASRock        | E35LM1                      | [663d9ac1e1](https://linux-hardware.org/?probe=663d9ac1e1) | Sep 04, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [bcd06888e4](https://linux-hardware.org/?probe=bcd06888e4) | Sep 04, 2023 |
| Gigabyte      | H55M-S2HP                   | [f2ac0f8904](https://linux-hardware.org/?probe=f2ac0f8904) | Sep 04, 2023 |
| ASRock        | A55M-HVS                    | [eaa27d1ba6](https://linux-hardware.org/?probe=eaa27d1ba6) | Sep 04, 2023 |
| ASRock        | N68-S3 FX                   | [2b503dd2b6](https://linux-hardware.org/?probe=2b503dd2b6) | Sep 04, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | [908a64b09a](https://linux-hardware.org/?probe=908a64b09a) | Sep 04, 2023 |
| Dell          | 0CU409                      | [ca461ddc28](https://linux-hardware.org/?probe=ca461ddc28) | Sep 04, 2023 |
| Gigabyte      | A320M-H-CF                  | [8d171f78bf](https://linux-hardware.org/?probe=8d171f78bf) | Sep 04, 2023 |
| MSI           | B450M PRO-VDH PLUS          | [7e0c89dfdb](https://linux-hardware.org/?probe=7e0c89dfdb) | Sep 04, 2023 |
| Gigabyte      | B550M DS3H                  | [b8a2b22a6c](https://linux-hardware.org/?probe=b8a2b22a6c) | Sep 03, 2023 |
| Intel         | H61                         | [209644dbc2](https://linux-hardware.org/?probe=209644dbc2) | Sep 03, 2023 |
| AMD           | A88K                        | [d58c29d4ad](https://linux-hardware.org/?probe=d58c29d4ad) | Sep 03, 2023 |
| Gigabyte      | B450 AORUS M                | [e58d4f8405](https://linux-hardware.org/?probe=e58d4f8405) | Sep 03, 2023 |
| MEGA          | G41T-M7 LGT                 | [8d645686ff](https://linux-hardware.org/?probe=8d645686ff) | Sep 02, 2023 |
| HP            | 3646h                       | [cd226fee15](https://linux-hardware.org/?probe=cd226fee15) | Sep 02, 2023 |
| ASRock        | FM2A55M-VG3+                | [df01a7432c](https://linux-hardware.org/?probe=df01a7432c) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [2a9211117f](https://linux-hardware.org/?probe=2a9211117f) | Sep 02, 2023 |
| Positivo      | POS-EIH610EX 11189814       | [e6a9006a72](https://linux-hardware.org/?probe=e6a9006a72) | Sep 01, 2023 |
| Dell          | 0XT4CY A01                  | [26665d2c19](https://linux-hardware.org/?probe=26665d2c19) | Sep 01, 2023 |
| Positivo      | POS-EIH610EX 11189814       | [e222369e70](https://linux-hardware.org/?probe=e222369e70) | Sep 01, 2023 |
| Intel         | X99H                        | [e020530bc8](https://linux-hardware.org/?probe=e020530bc8) | Sep 01, 2023 |
| Foxconn       | A6VMX 0A                    | [338cdb7d40](https://linux-hardware.org/?probe=338cdb7d40) | Sep 01, 2023 |
| Intel         | H110                        | [05970c6811](https://linux-hardware.org/?probe=05970c6811) | Sep 01, 2023 |
| ASUSTek       | PRIME H410M-D               | [332e78dfba](https://linux-hardware.org/?probe=332e78dfba) | Sep 01, 2023 |
| Foxconn       | G31MXP FAB:1.1              | [4fc2089efc](https://linux-hardware.org/?probe=4fc2089efc) | Sep 01, 2023 |
| ASUSTek       | M4A78LT-M-LE                | [d3d5887ff3](https://linux-hardware.org/?probe=d3d5887ff3) | Sep 01, 2023 |
| ASRock        | A320M-HD                    | [7fd4c8ad9c](https://linux-hardware.org/?probe=7fd4c8ad9c) | Sep 01, 2023 |
| AMD           | A88K                        | [08a455504f](https://linux-hardware.org/?probe=08a455504f) | Sep 01, 2023 |
| ASRock        | B550M-ITX/ac                | [42eb5f3ad4](https://linux-hardware.org/?probe=42eb5f3ad4) | Aug 31, 2023 |
| PCWare        | IPX1800E1                   | [bfe03f751b](https://linux-hardware.org/?probe=bfe03f751b) | Aug 31, 2023 |
| Intel         | H61                         | [d0bd2f4cfa](https://linux-hardware.org/?probe=d0bd2f4cfa) | Aug 31, 2023 |
| Intel         | B75                         | [d8367a0977](https://linux-hardware.org/?probe=d8367a0977) | Aug 31, 2023 |
| MSI           | H61M-P20/W8                 | [c35045d386](https://linux-hardware.org/?probe=c35045d386) | Aug 31, 2023 |
| Red Hat       | RHEL RHEL-9.2.0 PC          | [ee06e81f13](https://linux-hardware.org/?probe=ee06e81f13) | Aug 31, 2023 |
| Intel         | H55                         | [955198ab64](https://linux-hardware.org/?probe=955198ab64) | Aug 31, 2023 |
| Dell          | 0GDG8Y A00                  | [b9c66b93e7](https://linux-hardware.org/?probe=b9c66b93e7) | Aug 31, 2023 |
| MACHINIST     | E5-D8-MAX V1.0              | [339734178a](https://linux-hardware.org/?probe=339734178a) | Aug 31, 2023 |
| Megaware      | MW-NM70HD-MI 06/11/2012 ... | [7b8812491c](https://linux-hardware.org/?probe=7b8812491c) | Aug 31, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [79783b33ff](https://linux-hardware.org/?probe=79783b33ff) | Aug 30, 2023 |
| Positivo      | POS-RIB360EE 11144907       | [ebcd50f639](https://linux-hardware.org/?probe=ebcd50f639) | Aug 30, 2023 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | [fbbbe0087a](https://linux-hardware.org/?probe=fbbbe0087a) | Aug 30, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [9cf292357b](https://linux-hardware.org/?probe=9cf292357b) | Aug 30, 2023 |
| Intel         | DH67CL AAG10212-206         | [e3f4b109ff](https://linux-hardware.org/?probe=e3f4b109ff) | Aug 30, 2023 |
| Foxconn       | Lucknow                     | [eece5a84ae](https://linux-hardware.org/?probe=eece5a84ae) | Aug 30, 2023 |
| Positivo      | POS-RIB360EE 11144907       | [c392d83e8e](https://linux-hardware.org/?probe=c392d83e8e) | Aug 29, 2023 |
| MSI           | H61M-E22/W8                 | [2439d2ed95](https://linux-hardware.org/?probe=2439d2ed95) | Aug 29, 2023 |
| Gigabyte      | G31M-ES2L                   | [7094317c17](https://linux-hardware.org/?probe=7094317c17) | Aug 29, 2023 |
| MSI           | MAG B460M BAZOOKA           | [dcd9ab0f79](https://linux-hardware.org/?probe=dcd9ab0f79) | Aug 29, 2023 |
| Intel         | H81                         | [9b70a28b25](https://linux-hardware.org/?probe=9b70a28b25) | Aug 28, 2023 |
| Intel         | DX79SR AAG57199-200         | [418a709636](https://linux-hardware.org/?probe=418a709636) | Aug 28, 2023 |
| Gigabyte      | H410M H                     | [a4fe691c36](https://linux-hardware.org/?probe=a4fe691c36) | Aug 28, 2023 |
| Gigabyte      | B75M-D3P                    | [73562af96c](https://linux-hardware.org/?probe=73562af96c) | Aug 28, 2023 |
| Positivo      | POS-PQ45AU                  | [aba45a4f14](https://linux-hardware.org/?probe=aba45a4f14) | Aug 27, 2023 |
| MSI           | A68HM-E33 V2                | [bf483bc8d3](https://linux-hardware.org/?probe=bf483bc8d3) | Aug 27, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [c9935dab6b](https://linux-hardware.org/?probe=c9935dab6b) | Aug 27, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | [8ee437beac](https://linux-hardware.org/?probe=8ee437beac) | Aug 27, 2023 |
| ASRock        | A320M-HD                    | [dcb65a221f](https://linux-hardware.org/?probe=dcb65a221f) | Aug 27, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | [2eb35196a6](https://linux-hardware.org/?probe=2eb35196a6) | Aug 26, 2023 |
| HP            | 1998                        | [2c6c07a7d3](https://linux-hardware.org/?probe=2c6c07a7d3) | Aug 26, 2023 |
| Intel         | D33217CK G76541-301         | [24b3b7aac4](https://linux-hardware.org/?probe=24b3b7aac4) | Aug 26, 2023 |
| Positivo      | POS-PIG41BA POSITIVO        | [05dc1d19de](https://linux-hardware.org/?probe=05dc1d19de) | Aug 26, 2023 |
| ASUSTek       | EX-A320M-GAMING             | [6fc7c35bc9](https://linux-hardware.org/?probe=6fc7c35bc9) | Aug 26, 2023 |
| Dell          | 0T656F A01                  | [fe9ddfe6d0](https://linux-hardware.org/?probe=fe9ddfe6d0) | Aug 25, 2023 |
| HP            | 3047h                       | [5c415723ef](https://linux-hardware.org/?probe=5c415723ef) | Aug 24, 2023 |
| Gigabyte      | H61M-S1                     | [09db81cde4](https://linux-hardware.org/?probe=09db81cde4) | Aug 24, 2023 |
| Colorful T... | A320M-K PRO YV14            | [0cf842e282](https://linux-hardware.org/?probe=0cf842e282) | Aug 24, 2023 |
| Gigabyte      | H310M M.2                   | [9b1205f50a](https://linux-hardware.org/?probe=9b1205f50a) | Aug 24, 2023 |
| ASUSTek       | P7H55-M BR                  | [820b86d560](https://linux-hardware.org/?probe=820b86d560) | Aug 24, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | [fd9fa02e66](https://linux-hardware.org/?probe=fd9fa02e66) | Aug 23, 2023 |
| Gigabyte      | A520M DS3H                  | [f8990a10d8](https://linux-hardware.org/?probe=f8990a10d8) | Aug 23, 2023 |
| Gigabyte      | A520M DS3H                  | [a09e28d1d6](https://linux-hardware.org/?probe=a09e28d1d6) | Aug 23, 2023 |
| Positivo      | POS-PIH110DV                | [75f0f78d6c](https://linux-hardware.org/?probe=75f0f78d6c) | Aug 23, 2023 |
| Dell          | 0WY45N A00                  | [523c93534d](https://linux-hardware.org/?probe=523c93534d) | Aug 23, 2023 |
| Gigabyte      | B450 AORUS M                | [38849e44bb](https://linux-hardware.org/?probe=38849e44bb) | Aug 23, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [ac09f27b9d](https://linux-hardware.org/?probe=ac09f27b9d) | Aug 22, 2023 |
| Intel         | H55                         | [8320e0c758](https://linux-hardware.org/?probe=8320e0c758) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [82c63f13d1](https://linux-hardware.org/?probe=82c63f13d1) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [1aee954611](https://linux-hardware.org/?probe=1aee954611) | Aug 22, 2023 |
| Intel         | H81                         | [fe1e95123d](https://linux-hardware.org/?probe=fe1e95123d) | Aug 22, 2023 |
| Gigabyte      | X570 GAMING X               | [6a3c737df2](https://linux-hardware.org/?probe=6a3c737df2) | Aug 22, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | [9762e16c0e](https://linux-hardware.org/?probe=9762e16c0e) | Aug 21, 2023 |
| AMD           | Inagua CRB                  | [9455337239](https://linux-hardware.org/?probe=9455337239) | Aug 21, 2023 |
| Megaware      | MW-G31T-M7                  | [3bed885307](https://linux-hardware.org/?probe=3bed885307) | Aug 20, 2023 |
| Megaware      | MW-G31T-M7                  | [774ca523db](https://linux-hardware.org/?probe=774ca523db) | Aug 19, 2023 |
| Gigabyte      | M68MT-S2P                   | [bbf0f31c1b](https://linux-hardware.org/?probe=bbf0f31c1b) | Aug 19, 2023 |
| HP            | 0266                        | [636546711d](https://linux-hardware.org/?probe=636546711d) | Aug 18, 2023 |
| ECS           | A55F-M4                     | [93a5944754](https://linux-hardware.org/?probe=93a5944754) | Aug 18, 2023 |
| ASUSTek       | PRIME H410M-E               | [ae37d9f640](https://linux-hardware.org/?probe=ae37d9f640) | Aug 18, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [cce6cb2878](https://linux-hardware.org/?probe=cce6cb2878) | Aug 18, 2023 |
| MSI           | X470 GAMING M7 AC           | [92f8391f8f](https://linux-hardware.org/?probe=92f8391f8f) | Aug 18, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [024d9028bb](https://linux-hardware.org/?probe=024d9028bb) | Aug 18, 2023 |
| ASRock        | H61M-HG4                    | [6fbc46fea9](https://linux-hardware.org/?probe=6fbc46fea9) | Aug 17, 2023 |
| QIYIDA        | X79 (INTEL Xeon E5/Corei... | [1aeba3a6ec](https://linux-hardware.org/?probe=1aeba3a6ec) | Aug 17, 2023 |
| QIYIDA        | X79 (INTEL Xeon E5/Corei... | [b44417fa3d](https://linux-hardware.org/?probe=b44417fa3d) | Aug 17, 2023 |
| Gigabyte      | B75M-D3H                    | [93f7041d2f](https://linux-hardware.org/?probe=93f7041d2f) | Aug 17, 2023 |
| ASUSTek       | B150M-C/BR                  | [78e12f014e](https://linux-hardware.org/?probe=78e12f014e) | Aug 17, 2023 |
| Intel         | H55                         | [9d45836b3b](https://linux-hardware.org/?probe=9d45836b3b) | Aug 17, 2023 |
| ASRock        | A320M-HD R4.0               | [f67dd298b1](https://linux-hardware.org/?probe=f67dd298b1) | Aug 16, 2023 |
| Intel         | MAHOBAY                     | [cf9cfddfa5](https://linux-hardware.org/?probe=cf9cfddfa5) | Aug 16, 2023 |
| Intel         | MAHOBAY                     | [6c3b1a6ddd](https://linux-hardware.org/?probe=6c3b1a6ddd) | Aug 16, 2023 |
| PCWare        | IPMH110G                    | [c07caba6a9](https://linux-hardware.org/?probe=c07caba6a9) | Aug 16, 2023 |
| ASRock        | A320M-HDV R4.0              | [f88687d2f0](https://linux-hardware.org/?probe=f88687d2f0) | Aug 15, 2023 |
| Positivo      | POS-RIQ470EN 11190998       | [1eec60309a](https://linux-hardware.org/?probe=1eec60309a) | Aug 15, 2023 |
| HP            | 3047h                       | [b136128b47](https://linux-hardware.org/?probe=b136128b47) | Aug 15, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [11dafc79e8](https://linux-hardware.org/?probe=11dafc79e8) | Aug 15, 2023 |
| Intel         | B75A                        | [c081fb2ca8](https://linux-hardware.org/?probe=c081fb2ca8) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [f6892c6532](https://linux-hardware.org/?probe=f6892c6532) | Aug 15, 2023 |
| HP            | 3047h                       | [4c2aba9453](https://linux-hardware.org/?probe=4c2aba9453) | Aug 14, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [8803256d2e](https://linux-hardware.org/?probe=8803256d2e) | Aug 14, 2023 |
| ASUSTek       | H110M-C/BR                  | [e6da28e1fb](https://linux-hardware.org/?probe=e6da28e1fb) | Aug 14, 2023 |
| Lenovo        | ThinkCentre Edge71 1577K... | [8127e491dc](https://linux-hardware.org/?probe=8127e491dc) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c342e06960](https://linux-hardware.org/?probe=c342e06960) | Aug 14, 2023 |
| Gigabyte      | B450M GAMING                | [495c01f301](https://linux-hardware.org/?probe=495c01f301) | Aug 14, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | [e6fe434dfa](https://linux-hardware.org/?probe=e6fe434dfa) | Aug 13, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [3decac5b92](https://linux-hardware.org/?probe=3decac5b92) | Aug 13, 2023 |
| Intel         | H61                         | [0f81745861](https://linux-hardware.org/?probe=0f81745861) | Aug 13, 2023 |
| Intel         | H61                         | [cbf83ef64b](https://linux-hardware.org/?probe=cbf83ef64b) | Aug 13, 2023 |
| Huanan        | X99-F8 V2.0                 | [60746f5bad](https://linux-hardware.org/?probe=60746f5bad) | Aug 13, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | [d1fddefbb1](https://linux-hardware.org/?probe=d1fddefbb1) | Aug 13, 2023 |
| Intel         | H55                         | [9eb68ebabb](https://linux-hardware.org/?probe=9eb68ebabb) | Aug 13, 2023 |
| Gigabyte      | B85M-D3H                    | [d81314b86d](https://linux-hardware.org/?probe=d81314b86d) | Aug 12, 2023 |
| Intel         | B75A                        | [91f9e56ace](https://linux-hardware.org/?probe=91f9e56ace) | Aug 12, 2023 |
| Intel         | DG31PR AAE58249-301         | [28bc891b6d](https://linux-hardware.org/?probe=28bc891b6d) | Aug 12, 2023 |
| ASUSTek       | J1800I-C/BR                 | [5226916c20](https://linux-hardware.org/?probe=5226916c20) | Aug 12, 2023 |
| ASUSTek       | J1800I-C/BR                 | [f59a93f116](https://linux-hardware.org/?probe=f59a93f116) | Aug 12, 2023 |
| Intel         | DG31PR AAE58249-301         | [3050db3fbf](https://linux-hardware.org/?probe=3050db3fbf) | Aug 12, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | [f8fa12cc07](https://linux-hardware.org/?probe=f8fa12cc07) | Aug 11, 2023 |
| Gigabyte      | A520M DS3H AC               | [c53eeb4caf](https://linux-hardware.org/?probe=c53eeb4caf) | Aug 11, 2023 |
| ASRock        | H310CM-HG4                  | [773b111412](https://linux-hardware.org/?probe=773b111412) | Aug 10, 2023 |
| ASRock        | H310CM-HG4                  | [70c4f2863b](https://linux-hardware.org/?probe=70c4f2863b) | Aug 10, 2023 |
| ASUSTek       | P8Z68-V                     | [cff11cda6f](https://linux-hardware.org/?probe=cff11cda6f) | Aug 10, 2023 |
| Gigabyte      | B85M-D3H                    | [d4a16b0b3e](https://linux-hardware.org/?probe=d4a16b0b3e) | Aug 10, 2023 |
| HP            | 2AF9                        | [b31b796804](https://linux-hardware.org/?probe=b31b796804) | Aug 10, 2023 |
| Dell          | OptiPlex 755                | [279ed1e2d5](https://linux-hardware.org/?probe=279ed1e2d5) | Aug 10, 2023 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | [7acbd56a40](https://linux-hardware.org/?probe=7acbd56a40) | Aug 10, 2023 |
| MSI           | A68HM-E33                   | [be692e44b5](https://linux-hardware.org/?probe=be692e44b5) | Aug 10, 2023 |
| Dell          | 0VXN67 A01                  | [4fbd39d860](https://linux-hardware.org/?probe=4fbd39d860) | Aug 10, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [0c4903c4d2](https://linux-hardware.org/?probe=0c4903c4d2) | Aug 10, 2023 |
| Gigabyte      | G31M-ES2L                   | [1e856f651d](https://linux-hardware.org/?probe=1e856f651d) | Aug 09, 2023 |
| Gigabyte      | B450 AORUS M                | [739bc450b8](https://linux-hardware.org/?probe=739bc450b8) | Aug 09, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [e315608a65](https://linux-hardware.org/?probe=e315608a65) | Aug 09, 2023 |
| Huanan        | X99-TF-Q GAMING V1.2        | [da612198cc](https://linux-hardware.org/?probe=da612198cc) | Aug 09, 2023 |
| SZMZ          | X99M-G2                     | [e22cd6fdac](https://linux-hardware.org/?probe=e22cd6fdac) | Aug 09, 2023 |
| SZMZ          | X99M-G2                     | [2242417727](https://linux-hardware.org/?probe=2242417727) | Aug 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [0b1144add1](https://linux-hardware.org/?probe=0b1144add1) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | [c4ac4952a4](https://linux-hardware.org/?probe=c4ac4952a4) | Aug 09, 2023 |
| Biostar       | X370GT3                     | [6c4e484a34](https://linux-hardware.org/?probe=6c4e484a34) | Aug 09, 2023 |
| Gigabyte      | H410M H V3                  | [62a5817462](https://linux-hardware.org/?probe=62a5817462) | Aug 09, 2023 |
| ASRock        | Z77 Extreme4                | [dace48c9ec](https://linux-hardware.org/?probe=dace48c9ec) | Aug 09, 2023 |
| ASRock        | Z77 Extreme4                | [e4c0e430b2](https://linux-hardware.org/?probe=e4c0e430b2) | Aug 09, 2023 |
| Itautec       | ST 4273 ST-4273 Custom 0... | [2e2f861c7c](https://linux-hardware.org/?probe=2e2f861c7c) | Aug 09, 2023 |
| ASRock        | A320M-HDV R4.0              | [eb99d95702](https://linux-hardware.org/?probe=eb99d95702) | Aug 08, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [88c76f027a](https://linux-hardware.org/?probe=88c76f027a) | Aug 08, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [b477184f03](https://linux-hardware.org/?probe=b477184f03) | Aug 08, 2023 |
| Digiboard     | NM70-I                      | [280ee6d8fe](https://linux-hardware.org/?probe=280ee6d8fe) | Aug 07, 2023 |
| Unknown       | Unknown                     | [e2427beca2](https://linux-hardware.org/?probe=e2427beca2) | Aug 07, 2023 |
| ASUSTek       | P8H61-M LX3                 | [6875c17337](https://linux-hardware.org/?probe=6875c17337) | Aug 06, 2023 |
| Gigabyte      | B450M GAMING                | [570d622bb5](https://linux-hardware.org/?probe=570d622bb5) | Aug 06, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [27792f16e2](https://linux-hardware.org/?probe=27792f16e2) | Aug 06, 2023 |
| MACHINIST     | X99-MR9D PLUS V1.0          | [29f8d73c0e](https://linux-hardware.org/?probe=29f8d73c0e) | Aug 05, 2023 |
| Intel         | B75                         | [9411dd987c](https://linux-hardware.org/?probe=9411dd987c) | Aug 05, 2023 |
| Gigabyte      | H110M-H-CF                  | [17ea53b0c6](https://linux-hardware.org/?probe=17ea53b0c6) | Aug 05, 2023 |
| Intel         | H81                         | [4441a1a1ca](https://linux-hardware.org/?probe=4441a1a1ca) | Aug 05, 2023 |
| ASUSTek       | P8Z77-V LX                  | [92ef92268a](https://linux-hardware.org/?probe=92ef92268a) | Aug 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | [ca1a97268c](https://linux-hardware.org/?probe=ca1a97268c) | Aug 04, 2023 |
| ASRock        | A320M-HDV R4.0              | [de07e937bb](https://linux-hardware.org/?probe=de07e937bb) | Aug 04, 2023 |
| MANCER        | A320M-DA 1006               | [573affec7b](https://linux-hardware.org/?probe=573affec7b) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [a260479012](https://linux-hardware.org/?probe=a260479012) | Aug 04, 2023 |
| ASUSTek       | M5A78L-M LX3                | [0ffd23b534](https://linux-hardware.org/?probe=0ffd23b534) | Aug 04, 2023 |
| OEM           | B75 Ver:1.44                | [6dcf79b752](https://linux-hardware.org/?probe=6dcf79b752) | Aug 03, 2023 |
| Intel         | H61                         | [7b2774c1a1](https://linux-hardware.org/?probe=7b2774c1a1) | Aug 03, 2023 |
| Intel         | H61                         | [8d450f7e6e](https://linux-hardware.org/?probe=8d450f7e6e) | Aug 03, 2023 |
| Win elemen... | M600                        | [b9537c621c](https://linux-hardware.org/?probe=b9537c621c) | Aug 02, 2023 |
| Unknown       | Unknown                     | [3bb1942723](https://linux-hardware.org/?probe=3bb1942723) | Aug 02, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [11d27dea01](https://linux-hardware.org/?probe=11d27dea01) | Aug 02, 2023 |
| Gigabyte      | B450 AORUS M                | [518512fe78](https://linux-hardware.org/?probe=518512fe78) | Aug 02, 2023 |
| Dell          | 0GY6Y8 A02                  | [e1d2deb748](https://linux-hardware.org/?probe=e1d2deb748) | Aug 02, 2023 |
| Dell          | 0FR6WH A01                  | [38feb4d1f7](https://linux-hardware.org/?probe=38feb4d1f7) | Aug 02, 2023 |
| ASRock        | A320M-HDV R4.0              | [2ff30156cf](https://linux-hardware.org/?probe=2ff30156cf) | Aug 02, 2023 |
| Gigabyte      | B450 AORUS M                | [0ced83ffed](https://linux-hardware.org/?probe=0ced83ffed) | Aug 02, 2023 |
| ASRock        | H410M-HDV/M.2               | [71a11bdffd](https://linux-hardware.org/?probe=71a11bdffd) | Aug 02, 2023 |
| ASRock        | B650M PG Riptide            | [bdccf9a3db](https://linux-hardware.org/?probe=bdccf9a3db) | Aug 01, 2023 |
| Lenovo        | 3188 SDK0J40709 WIN 3259... | [59e7f97f2d](https://linux-hardware.org/?probe=59e7f97f2d) | Aug 01, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [668eb36a4a](https://linux-hardware.org/?probe=668eb36a4a) | Aug 01, 2023 |
| ASUSTek       | P8H61-M LX                  | [287740b630](https://linux-hardware.org/?probe=287740b630) | Aug 01, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [2e4793aa6c](https://linux-hardware.org/?probe=2e4793aa6c) | Aug 01, 2023 |
| Gigabyte      | F2A68HM-H                   | [08e1a2a1e1](https://linux-hardware.org/?probe=08e1a2a1e1) | Aug 01, 2023 |
| ASRock        | H110M-HG4                   | [7584e2db20](https://linux-hardware.org/?probe=7584e2db20) | Jul 31, 2023 |
| Intel         | DH55HC AAE70933-502         | [e849da706a](https://linux-hardware.org/?probe=e849da706a) | Jul 31, 2023 |
| Positivo      | POS-PIH110DV                | [faa5c5cda0](https://linux-hardware.org/?probe=faa5c5cda0) | Jul 31, 2023 |
| Unknown       | Phitronics N68C-M           | [0c596c95da](https://linux-hardware.org/?probe=0c596c95da) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [7890c76098](https://linux-hardware.org/?probe=7890c76098) | Jul 31, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [42a2df4c91](https://linux-hardware.org/?probe=42a2df4c91) | Jul 30, 2023 |
| Intel         | DG41WV AAE90316-102         | [fa7d425224](https://linux-hardware.org/?probe=fa7d425224) | Jul 30, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [fe48f2b4d4](https://linux-hardware.org/?probe=fe48f2b4d4) | Jul 30, 2023 |
| MSI           | B85M-E45                    | [dfef6fcff5](https://linux-hardware.org/?probe=dfef6fcff5) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [0ce1be51b9](https://linux-hardware.org/?probe=0ce1be51b9) | Jul 30, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [1bcc28bd33](https://linux-hardware.org/?probe=1bcc28bd33) | Jul 29, 2023 |
| Unknown       | GSUO H61V10C                | [9fd25cd0ba](https://linux-hardware.org/?probe=9fd25cd0ba) | Jul 29, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [96b197dffc](https://linux-hardware.org/?probe=96b197dffc) | Jul 29, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [90c03881ae](https://linux-hardware.org/?probe=90c03881ae) | Jul 29, 2023 |
| Positivo      | POS-EINM70CS POSITIVO       | [bee5e6175b](https://linux-hardware.org/?probe=bee5e6175b) | Jul 29, 2023 |
| MSI           | A520M-A PRO                 | [733695ae93](https://linux-hardware.org/?probe=733695ae93) | Jul 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [bc88e3dbae](https://linux-hardware.org/?probe=bc88e3dbae) | Jul 28, 2023 |
| ASRock        | H110M-HG4                   | [205f3a047f](https://linux-hardware.org/?probe=205f3a047f) | Jul 28, 2023 |
| Digitron      | G31T-M7                     | [7b926165d9](https://linux-hardware.org/?probe=7b926165d9) | Jul 28, 2023 |
| Dell          | 0FR6WH A01                  | [d20434fd50](https://linux-hardware.org/?probe=d20434fd50) | Jul 28, 2023 |
| MSI           | Z270 GAMING PLUS            | [cc489fad92](https://linux-hardware.org/?probe=cc489fad92) | Jul 28, 2023 |
| PCWare        | IPX1800E2                   | [ee17cd82e7](https://linux-hardware.org/?probe=ee17cd82e7) | Jul 27, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | [b9bba11373](https://linux-hardware.org/?probe=b9bba11373) | Jul 27, 2023 |
| ASRock        | A320M-HD                    | [26e141980a](https://linux-hardware.org/?probe=26e141980a) | Jul 27, 2023 |
| Intel         | H55                         | [83f249e836](https://linux-hardware.org/?probe=83f249e836) | Jul 27, 2023 |
| Toshiba       | STI 005492G                 | [6e73cad7e4](https://linux-hardware.org/?probe=6e73cad7e4) | Jul 27, 2023 |
| ASRock        | H61M-HVS                    | [ac730fa4ed](https://linux-hardware.org/?probe=ac730fa4ed) | Jul 26, 2023 |
| ASRock        | H61M-HVS                    | [57d93857f1](https://linux-hardware.org/?probe=57d93857f1) | Jul 26, 2023 |
| ECS           | G41T-M7                     | [eb7ea6e3f6](https://linux-hardware.org/?probe=eb7ea6e3f6) | Jul 26, 2023 |
| Intel         | B75                         | [492fa4fc25](https://linux-hardware.org/?probe=492fa4fc25) | Jul 26, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [55102fad5b](https://linux-hardware.org/?probe=55102fad5b) | Jul 26, 2023 |
| AZW           | SEi                         | [115142c288](https://linux-hardware.org/?probe=115142c288) | Jul 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [959f3b36df](https://linux-hardware.org/?probe=959f3b36df) | Jul 26, 2023 |
| Gigabyte      | G31M-S2L                    | [5af2ea35ee](https://linux-hardware.org/?probe=5af2ea35ee) | Jul 26, 2023 |
| Gigabyte      | X570 GAMING X               | [f67be57cba](https://linux-hardware.org/?probe=f67be57cba) | Jul 26, 2023 |
| Dell          | 01XK1W A00                  | [9793da4c20](https://linux-hardware.org/?probe=9793da4c20) | Jul 26, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | [5ca26c7da9](https://linux-hardware.org/?probe=5ca26c7da9) | Jul 26, 2023 |
| Gigabyte      | B550M DS3H                  | [94a5fdec96](https://linux-hardware.org/?probe=94a5fdec96) | Jul 26, 2023 |
| MSI           | 2A9C                        | [83e6501c96](https://linux-hardware.org/?probe=83e6501c96) | Jul 25, 2023 |
| MAXSUN        | MS-Terminator B660M VER:... | [5cf65783b2](https://linux-hardware.org/?probe=5cf65783b2) | Jul 25, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [cfdb26e14f](https://linux-hardware.org/?probe=cfdb26e14f) | Jul 25, 2023 |
| PCWare        | IPMH61R3 8MB                | [dcbde0a01d](https://linux-hardware.org/?probe=dcbde0a01d) | Jul 24, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [2c4dce1245](https://linux-hardware.org/?probe=2c4dce1245) | Jul 24, 2023 |
| Gigabyte      | B450 AORUS M                | [858d935d25](https://linux-hardware.org/?probe=858d935d25) | Jul 24, 2023 |
| MACHINIST     | X99-MR9D PLUS V1.0          | [d1ef825b01](https://linux-hardware.org/?probe=d1ef825b01) | Jul 24, 2023 |
| Intel         | B75                         | [f6b0d91a50](https://linux-hardware.org/?probe=f6b0d91a50) | Jul 23, 2023 |
| Gigabyte      | H81M-H                      | [50cf88ae28](https://linux-hardware.org/?probe=50cf88ae28) | Jul 23, 2023 |
| ASUSTek       | M5A78L-M LX3                | [8982fa467c](https://linux-hardware.org/?probe=8982fa467c) | Jul 23, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [42d8ff9a34](https://linux-hardware.org/?probe=42d8ff9a34) | Jul 23, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [5e02d0f4e4](https://linux-hardware.org/?probe=5e02d0f4e4) | Jul 22, 2023 |
| ECS           | A780LM-M2                   | [b8b1304632](https://linux-hardware.org/?probe=b8b1304632) | Jul 22, 2023 |
| Itautec       | ST 4271 ST-4271 Padrao 0... | [a12700ebb8](https://linux-hardware.org/?probe=a12700ebb8) | Jul 22, 2023 |
| Biostar       | B350GT3                     | [41d95e4e81](https://linux-hardware.org/?probe=41d95e4e81) | Jul 22, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | [6285ba6300](https://linux-hardware.org/?probe=6285ba6300) | Jul 22, 2023 |
| Intel         | H61                         | [5a977f0aa9](https://linux-hardware.org/?probe=5a977f0aa9) | Jul 21, 2023 |
| Gigabyte      | B450 AORUS M                | [574d6f4393](https://linux-hardware.org/?probe=574d6f4393) | Jul 21, 2023 |
| Kllisre       | X99-B5 V1.1                 | [b132b3f39c](https://linux-hardware.org/?probe=b132b3f39c) | Jul 21, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [55f5c5bd48](https://linux-hardware.org/?probe=55f5c5bd48) | Jul 21, 2023 |
| Intel         | X99H                        | [474e78b162](https://linux-hardware.org/?probe=474e78b162) | Jul 21, 2023 |
| Biostar       | A320MH                      | [5fd84925fd](https://linux-hardware.org/?probe=5fd84925fd) | Jul 20, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [e4cc108748](https://linux-hardware.org/?probe=e4cc108748) | Jul 20, 2023 |
| ASRock        | X99M Extreme4               | [caf88d9f9d](https://linux-hardware.org/?probe=caf88d9f9d) | Jul 20, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [413194ce8c](https://linux-hardware.org/?probe=413194ce8c) | Jul 20, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [08fccc55c8](https://linux-hardware.org/?probe=08fccc55c8) | Jul 20, 2023 |
| Dell          | 02YRK5 A03                  | [a1f7c7f053](https://linux-hardware.org/?probe=a1f7c7f053) | Jul 19, 2023 |
| Intel         | H61                         | [10428f5c68](https://linux-hardware.org/?probe=10428f5c68) | Jul 19, 2023 |
| ASUSTek       | B85M-E/BR                   | [c2ac257f6e](https://linux-hardware.org/?probe=c2ac257f6e) | Jul 18, 2023 |
| Gigabyte      | B450M GAMING                | [d0fff20fb0](https://linux-hardware.org/?probe=d0fff20fb0) | Jul 18, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | [69f0859638](https://linux-hardware.org/?probe=69f0859638) | Jul 18, 2023 |
| ASUSTek       | P8H61-M LE/BR               | [0d9c612141](https://linux-hardware.org/?probe=0d9c612141) | Jul 17, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [25737bce66](https://linux-hardware.org/?probe=25737bce66) | Jul 17, 2023 |
| PCWare        | APM-A520G                   | [aefd780df7](https://linux-hardware.org/?probe=aefd780df7) | Jul 17, 2023 |
| Biostar       | B450MH                      | [22909715b3](https://linux-hardware.org/?probe=22909715b3) | Jul 16, 2023 |
| MSI           | A68HM-E33 V2                | [2d896167d8](https://linux-hardware.org/?probe=2d896167d8) | Jul 16, 2023 |
| Gigabyte      | G41MT-S2P                   | [fd05b31515](https://linux-hardware.org/?probe=fd05b31515) | Jul 16, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [f81eae6d45](https://linux-hardware.org/?probe=f81eae6d45) | Jul 16, 2023 |
| ASRock        | B450M Steel Legend          | [19b39ef686](https://linux-hardware.org/?probe=19b39ef686) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [b7992c5de7](https://linux-hardware.org/?probe=b7992c5de7) | Jul 16, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [f747d5537e](https://linux-hardware.org/?probe=f747d5537e) | Jul 15, 2023 |
| Gigabyte      | Z370M AORUS Gaming-CF       | [64a0d52846](https://linux-hardware.org/?probe=64a0d52846) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | [fc51c8fd14](https://linux-hardware.org/?probe=fc51c8fd14) | Jul 15, 2023 |
| Gigabyte      | Z490M GAMING X              | [1222689443](https://linux-hardware.org/?probe=1222689443) | Jul 15, 2023 |
| MSI           | A320M-A PRO MAX             | [34871aac58](https://linux-hardware.org/?probe=34871aac58) | Jul 15, 2023 |
| ASRock        | G41M-VS3                    | [f472934f38](https://linux-hardware.org/?probe=f472934f38) | Jul 15, 2023 |
| ASUSTek       | A88XM-A                     | [c58d69659f](https://linux-hardware.org/?probe=c58d69659f) | Jul 14, 2023 |
| ASUSTek       | H81M-A/BR                   | [40a2bef1f0](https://linux-hardware.org/?probe=40a2bef1f0) | Jul 14, 2023 |
| ASUSTek       | A88XM-A                     | [e34b3f4c71](https://linux-hardware.org/?probe=e34b3f4c71) | Jul 14, 2023 |
| Dell          | 0T656F A02                  | [9455dc5a07](https://linux-hardware.org/?probe=9455dc5a07) | Jul 14, 2023 |
| MSI           | B450M PRO-M2 MAX            | [dc3059f5b9](https://linux-hardware.org/?probe=dc3059f5b9) | Jul 14, 2023 |
| MSI           | H510M-A PRO                 | [718dc0f09e](https://linux-hardware.org/?probe=718dc0f09e) | Jul 14, 2023 |
| GALAX         | A320M G10g                  | [730e46d4f0](https://linux-hardware.org/?probe=730e46d4f0) | Jul 14, 2023 |
| ASUSTek       | STRIX Z270G GAMING          | [1857fae531](https://linux-hardware.org/?probe=1857fae531) | Jul 13, 2023 |
| Positivo      | POS-EAA75DE                 | [3307527ada](https://linux-hardware.org/?probe=3307527ada) | Jul 13, 2023 |
| Dell          | 04YP6J A03                  | [55d6cad717](https://linux-hardware.org/?probe=55d6cad717) | Jul 13, 2023 |
| Unknown       | EA A520M-E                  | [184201d556](https://linux-hardware.org/?probe=184201d556) | Jul 12, 2023 |
| ASUSTek       | P8H61-M LX2 R2.0            | [38facb34d4](https://linux-hardware.org/?probe=38facb34d4) | Jul 12, 2023 |
| ASUSTek       | M4A78                       | [d9adfecb80](https://linux-hardware.org/?probe=d9adfecb80) | Jul 11, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | [bad8c925e6](https://linux-hardware.org/?probe=bad8c925e6) | Jul 11, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | [f754f1e59b](https://linux-hardware.org/?probe=f754f1e59b) | Jul 11, 2023 |
| OEM           | B75 Ver:1.41                | [68c3f1b61c](https://linux-hardware.org/?probe=68c3f1b61c) | Jul 11, 2023 |
| Pegatron      | IPMH61P1                    | [9aa934f232](https://linux-hardware.org/?probe=9aa934f232) | Jul 11, 2023 |
| HP            | 3047h                       | [1a4c2d4702](https://linux-hardware.org/?probe=1a4c2d4702) | Jul 11, 2023 |
| Gigabyte      | F2A68HM-H                   | [e22f8030d3](https://linux-hardware.org/?probe=e22f8030d3) | Jul 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [0e411803b2](https://linux-hardware.org/?probe=0e411803b2) | Jul 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [8c2add9768](https://linux-hardware.org/?probe=8c2add9768) | Jul 10, 2023 |
| Positivo      | POS-MIH61CF POSITIVO        | [02113d0b75](https://linux-hardware.org/?probe=02113d0b75) | Jul 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [2cc9f44232](https://linux-hardware.org/?probe=2cc9f44232) | Jul 10, 2023 |
| MSI           | MEG Z390 GODLIKE            | [b904121800](https://linux-hardware.org/?probe=b904121800) | Jul 10, 2023 |
| Dell          | 01XK1W A00                  | [16aac702d5](https://linux-hardware.org/?probe=16aac702d5) | Jul 10, 2023 |
| ASRock        | A320M-HD                    | [5477254db4](https://linux-hardware.org/?probe=5477254db4) | Jul 10, 2023 |
| GALAX         | A320M G10g                  | [8ab8387585](https://linux-hardware.org/?probe=8ab8387585) | Jul 10, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [7c3e56e08a](https://linux-hardware.org/?probe=7c3e56e08a) | Jul 10, 2023 |
| MSI           | MEG Z390 GODLIKE            | [9a2170442d](https://linux-hardware.org/?probe=9a2170442d) | Jul 09, 2023 |
| ASRock        | B460M-HDV                   | [7790bc9f7b](https://linux-hardware.org/?probe=7790bc9f7b) | Jul 09, 2023 |
| ASUSTek       | M5A78L-M LX                 | [b4b1f263a8](https://linux-hardware.org/?probe=b4b1f263a8) | Jul 08, 2023 |
| Unknown       | X99-GT                      | [34c4fadab5](https://linux-hardware.org/?probe=34c4fadab5) | Jul 08, 2023 |
| Daten Tecn... | DH110MXV                    | [a2487119a6](https://linux-hardware.org/?probe=a2487119a6) | Jul 08, 2023 |
| GALAX         | A320M G10g                  | [21dab37c75](https://linux-hardware.org/?probe=21dab37c75) | Jul 08, 2023 |
| Unknown       | X99-GT                      | [de745928b7](https://linux-hardware.org/?probe=de745928b7) | Jul 08, 2023 |
| Dell          | 0CU409                      | [196ea8332b](https://linux-hardware.org/?probe=196ea8332b) | Jul 08, 2023 |
| Positivo      | POS-PIG43BC SIM             | [42727a7888](https://linux-hardware.org/?probe=42727a7888) | Jul 08, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | [e07a2eb978](https://linux-hardware.org/?probe=e07a2eb978) | Jul 08, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | [4bcab5adb1](https://linux-hardware.org/?probe=4bcab5adb1) | Jul 08, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [2f16685519](https://linux-hardware.org/?probe=2f16685519) | Jul 08, 2023 |
| Compaq        | Presario CQ-14              | [9ce9813d5a](https://linux-hardware.org/?probe=9ce9813d5a) | Jul 08, 2023 |
| Daten Tecn... | DH110MXV                    | [f9a1d993b2](https://linux-hardware.org/?probe=f9a1d993b2) | Jul 07, 2023 |
| Positivo      | POS-PIQ77CL POSITIVO        | [c9ccceb765](https://linux-hardware.org/?probe=c9ccceb765) | Jul 07, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [901c7b45c2](https://linux-hardware.org/?probe=901c7b45c2) | Jul 07, 2023 |
| MSI           | MEG Z390 GODLIKE            | [5ee0aa7d94](https://linux-hardware.org/?probe=5ee0aa7d94) | Jul 07, 2023 |
| Gigabyte      | A520M K V2                  | [7d81f81cce](https://linux-hardware.org/?probe=7d81f81cce) | Jul 06, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | [88649252eb](https://linux-hardware.org/?probe=88649252eb) | Jul 06, 2023 |
| ASRock        | A320M-HD                    | [7eb9d089cf](https://linux-hardware.org/?probe=7eb9d089cf) | Jul 06, 2023 |
| ASRock        | A320M-HD                    | [2d20ffc659](https://linux-hardware.org/?probe=2d20ffc659) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [25ea01643a](https://linux-hardware.org/?probe=25ea01643a) | Jul 06, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [f156a2bbfa](https://linux-hardware.org/?probe=f156a2bbfa) | Jul 06, 2023 |
| Gigabyte      | G1.Sniper H6                | [7592c0cc37](https://linux-hardware.org/?probe=7592c0cc37) | Jul 05, 2023 |
| Gigabyte      | G1.Sniper H6                | [71505f347f](https://linux-hardware.org/?probe=71505f347f) | Jul 05, 2023 |
| Gigabyte      | B450M DS3H V2               | [919f65a256](https://linux-hardware.org/?probe=919f65a256) | Jul 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [3ec7b573fc](https://linux-hardware.org/?probe=3ec7b573fc) | Jul 05, 2023 |
| Gigabyte      | X570 GAMING X               | [56609b5da2](https://linux-hardware.org/?probe=56609b5da2) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | [eef5ee5c9a](https://linux-hardware.org/?probe=eef5ee5c9a) | Jul 05, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [951a1de3df](https://linux-hardware.org/?probe=951a1de3df) | Jul 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [6b1beb7eeb](https://linux-hardware.org/?probe=6b1beb7eeb) | Jul 05, 2023 |
| Aierben       | NA17                        | [462b502bab](https://linux-hardware.org/?probe=462b502bab) | Jul 05, 2023 |
| Gigabyte      | A320M-H-CF                  | [e2706e4472](https://linux-hardware.org/?probe=e2706e4472) | Jul 05, 2023 |
| Megaware      | MW-H61H2-M2                 | [b86248bd97](https://linux-hardware.org/?probe=b86248bd97) | Jul 05, 2023 |
| Positivo      | POS-EIH61CE SIM             | [48b35c757d](https://linux-hardware.org/?probe=48b35c757d) | Jul 05, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | [941c70d512](https://linux-hardware.org/?probe=941c70d512) | Jul 04, 2023 |
| Intel         | H55                         | [8f8ff68380](https://linux-hardware.org/?probe=8f8ff68380) | Jul 04, 2023 |
| Dell          | 0KWVT8 A02                  | [234e7f985d](https://linux-hardware.org/?probe=234e7f985d) | Jul 04, 2023 |
| Intel         | H61                         | [e841a13522](https://linux-hardware.org/?probe=e841a13522) | Jul 03, 2023 |
| ECS           | H55H-M2                     | [344ce5bb17](https://linux-hardware.org/?probe=344ce5bb17) | Jul 03, 2023 |
| Intel         | H55                         | [1ed1ee7e20](https://linux-hardware.org/?probe=1ed1ee7e20) | Jul 03, 2023 |
| ASUSTek       | A88XM-A                     | [cfaaea2608](https://linux-hardware.org/?probe=cfaaea2608) | Jul 03, 2023 |
| Intel         | H61                         | [f18dd431c3](https://linux-hardware.org/?probe=f18dd431c3) | Jul 03, 2023 |
| Intel         | H55                         | [446ffab057](https://linux-hardware.org/?probe=446ffab057) | Jul 02, 2023 |
| Dell          | 05XGC8 A00                  | [83da477284](https://linux-hardware.org/?probe=83da477284) | Jul 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | [d0ab54293f](https://linux-hardware.org/?probe=d0ab54293f) | Jul 02, 2023 |
| Intel         | H61                         | [5b18122404](https://linux-hardware.org/?probe=5b18122404) | Jul 01, 2023 |
| Intel         | H61                         | [4664a58c9b](https://linux-hardware.org/?probe=4664a58c9b) | Jul 01, 2023 |
| Dell          | 05XGC8 A00                  | [7797ece08f](https://linux-hardware.org/?probe=7797ece08f) | Jul 01, 2023 |
| Daten Tecn... | DH110MXV                    | [83dd07d2a7](https://linux-hardware.org/?probe=83dd07d2a7) | Jul 01, 2023 |
| ASRock        | A320M-HD                    | [1df7c65f40](https://linux-hardware.org/?probe=1df7c65f40) | Jul 01, 2023 |
| ZR            | A320M-F 1005                | [c32d8de777](https://linux-hardware.org/?probe=c32d8de777) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [292b7f6f0f](https://linux-hardware.org/?probe=292b7f6f0f) | Jun 30, 2023 |
| Intel         | X99 V1.x                    | [8e4ce021b1](https://linux-hardware.org/?probe=8e4ce021b1) | Jun 30, 2023 |
| Gigabyte      | H81M-S2PH                   | [69b69e2a09](https://linux-hardware.org/?probe=69b69e2a09) | Jun 30, 2023 |
| MSI           | Z390-A PRO                  | [7c3ce62039](https://linux-hardware.org/?probe=7c3ce62039) | Jun 30, 2023 |
| AZW           | SEi                         | [37527da518](https://linux-hardware.org/?probe=37527da518) | Jun 30, 2023 |
| Gigabyte      | Z77X-D3H                    | [3e1517b7a7](https://linux-hardware.org/?probe=3e1517b7a7) | Jun 30, 2023 |
| Intel         | B75                         | [73d881c953](https://linux-hardware.org/?probe=73d881c953) | Jun 30, 2023 |
| Gigabyte      | Z590 AORUS ULTRA            | [45d5903c62](https://linux-hardware.org/?probe=45d5903c62) | Jun 30, 2023 |
| Intel         | X99 V1.x                    | [1c7ef9ef35](https://linux-hardware.org/?probe=1c7ef9ef35) | Jun 29, 2023 |
| PCWare        | IPMH61R3                    | [e190259144](https://linux-hardware.org/?probe=e190259144) | Jun 29, 2023 |
| Gigabyte      | H81M-S2PH                   | [d0ec676a22](https://linux-hardware.org/?probe=d0ec676a22) | Jun 29, 2023 |
| Dell          | 0GDG8Y A00                  | [f0fdd509f7](https://linux-hardware.org/?probe=f0fdd509f7) | Jun 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | [bb1cb1ef13](https://linux-hardware.org/?probe=bb1cb1ef13) | Jun 29, 2023 |
| HP            | 0B54h D                     | [c13f21ea22](https://linux-hardware.org/?probe=c13f21ea22) | Jun 29, 2023 |
| Dell          | 0T656F A02                  | [bf4264c797](https://linux-hardware.org/?probe=bf4264c797) | Jun 29, 2023 |
| MSI           | MS-7438 100                 | [4d0d23065e](https://linux-hardware.org/?probe=4d0d23065e) | Jun 29, 2023 |
| Intel         | DG41RQ AAE54511-205         | [0e896bc137](https://linux-hardware.org/?probe=0e896bc137) | Jun 29, 2023 |
| ZR            | A320M-F 1005                | [f70bb41b80](https://linux-hardware.org/?probe=f70bb41b80) | Jun 28, 2023 |
| Huanan        | Unknown                     | [397d33202e](https://linux-hardware.org/?probe=397d33202e) | Jun 28, 2023 |
| Lenovo        | NO DPK                      | [2f12ef933e](https://linux-hardware.org/?probe=2f12ef933e) | Jun 28, 2023 |
| ASRock        | B460M-HDV                   | [966b21f9af](https://linux-hardware.org/?probe=966b21f9af) | Jun 28, 2023 |
| ASRock        | H310CM-HG4                  | [8147961b6c](https://linux-hardware.org/?probe=8147961b6c) | Jun 28, 2023 |
| Fill By OE... | Q7700                       | [93c7c01ecb](https://linux-hardware.org/?probe=93c7c01ecb) | Jun 28, 2023 |
| ASUSTek       | M5A97 PLUS                  | [2faeb24e37](https://linux-hardware.org/?probe=2faeb24e37) | Jun 27, 2023 |
| Kennex        | POS-PIG41BA                 | [90addad9e1](https://linux-hardware.org/?probe=90addad9e1) | Jun 27, 2023 |
| ASRock        | H310CM-HG4                  | [16c2222f50](https://linux-hardware.org/?probe=16c2222f50) | Jun 27, 2023 |
| Gigabyte      | H310M M.2 x.x               | [6f9c836bb4](https://linux-hardware.org/?probe=6f9c836bb4) | Jun 27, 2023 |
| Fill By OE... | Q7700                       | [32ac9cb839](https://linux-hardware.org/?probe=32ac9cb839) | Jun 27, 2023 |
| Intel         | DH55TC AAE70932-206         | [9ff872e2a3](https://linux-hardware.org/?probe=9ff872e2a3) | Jun 26, 2023 |
| Positivo      | POS-PIH81DI                 | [42e304c777](https://linux-hardware.org/?probe=42e304c777) | Jun 26, 2023 |
| Positivo      | POS-PIH81DI                 | [77d2d3d01b](https://linux-hardware.org/?probe=77d2d3d01b) | Jun 26, 2023 |
| Lenovo        | 3102 NOK                    | [6277771b08](https://linux-hardware.org/?probe=6277771b08) | Jun 26, 2023 |
| ASRock        | H110M-HG4                   | [6aba51f328](https://linux-hardware.org/?probe=6aba51f328) | Jun 26, 2023 |
| Intel         | H61                         | [8013deae02](https://linux-hardware.org/?probe=8013deae02) | Jun 25, 2023 |
| Intel         | H61                         | [8af1bf1ada](https://linux-hardware.org/?probe=8af1bf1ada) | Jun 25, 2023 |
| Intel         | B75                         | [2456289bbd](https://linux-hardware.org/?probe=2456289bbd) | Jun 25, 2023 |
| Biostar       | G31M+                       | [d8347c5f07](https://linux-hardware.org/?probe=d8347c5f07) | Jun 25, 2023 |
| Intel         | X99H                        | [60f1f4a8ba](https://linux-hardware.org/?probe=60f1f4a8ba) | Jun 25, 2023 |
| HP            | 3397                        | [8d9ed6d13e](https://linux-hardware.org/?probe=8d9ed6d13e) | Jun 25, 2023 |
| Intel         | H55                         | [993c041483](https://linux-hardware.org/?probe=993c041483) | Jun 25, 2023 |
| Intel         | H61                         | [df8b50eae5](https://linux-hardware.org/?probe=df8b50eae5) | Jun 25, 2023 |
| Biostar       | TH55B HD                    | [5fbef8b11a](https://linux-hardware.org/?probe=5fbef8b11a) | Jun 25, 2023 |
| Gigabyte      | G31M-ES2L                   | [be14b80f2c](https://linux-hardware.org/?probe=be14b80f2c) | Jun 24, 2023 |
| Intel         | H61                         | [0f1d3e1299](https://linux-hardware.org/?probe=0f1d3e1299) | Jun 24, 2023 |
| Techvision    | TVI7309X B0                 | [c8fc13e942](https://linux-hardware.org/?probe=c8fc13e942) | Jun 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [74b9f1b367](https://linux-hardware.org/?probe=74b9f1b367) | Jun 24, 2023 |
| Positivo      | POS-AG31AP                  | [bd3b3228c6](https://linux-hardware.org/?probe=bd3b3228c6) | Jun 24, 2023 |
| Gigabyte      | A520M S2H                   | [cc2b3ff1ad](https://linux-hardware.org/?probe=cc2b3ff1ad) | Jun 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [dac65b1c2c](https://linux-hardware.org/?probe=dac65b1c2c) | Jun 24, 2023 |
| MSI           | A320M-A PRO                 | [09b5be9c77](https://linux-hardware.org/?probe=09b5be9c77) | Jun 24, 2023 |
| PERTOSA       | GA-H110TN-M                 | [43b4160c55](https://linux-hardware.org/?probe=43b4160c55) | Jun 24, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [e3d196b0b5](https://linux-hardware.org/?probe=e3d196b0b5) | Jun 24, 2023 |
| Dell          | 01XK1W A00                  | [53dbc2e799](https://linux-hardware.org/?probe=53dbc2e799) | Jun 24, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | [e5b4e8d2d4](https://linux-hardware.org/?probe=e5b4e8d2d4) | Jun 24, 2023 |
| HP            | 1495                        | [eab7d15f02](https://linux-hardware.org/?probe=eab7d15f02) | Jun 23, 2023 |
| Huanan        | X79 V6.11                   | [e94687bb6b](https://linux-hardware.org/?probe=e94687bb6b) | Jun 23, 2023 |
| ASUSTek       | PRIME B350M-A               | [efb0264470](https://linux-hardware.org/?probe=efb0264470) | Jun 23, 2023 |
| Positivo      | POS-AG31AP                  | [1dd704fab9](https://linux-hardware.org/?probe=1dd704fab9) | Jun 22, 2023 |
| ASRock        | A320M-HD                    | [761a478742](https://linux-hardware.org/?probe=761a478742) | Jun 22, 2023 |
| Gigabyte      | M68MT-S2P                   | [dda587b759](https://linux-hardware.org/?probe=dda587b759) | Jun 22, 2023 |
| Gigabyte      | B450 AORUS M                | [7d52f04870](https://linux-hardware.org/?probe=7d52f04870) | Jun 22, 2023 |
| ASRock        | B365 Pro4                   | [46dc8e10a8](https://linux-hardware.org/?probe=46dc8e10a8) | Jun 21, 2023 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [446992e1b5](https://linux-hardware.org/?probe=446992e1b5) | Jun 21, 2023 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | [68ec70d3f8](https://linux-hardware.org/?probe=68ec70d3f8) | Jun 21, 2023 |
| Intel         | H55                         | [545c7e42b3](https://linux-hardware.org/?probe=545c7e42b3) | Jun 21, 2023 |
| HP            | 339A                        | [60b0bff872](https://linux-hardware.org/?probe=60b0bff872) | Jun 21, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [6f0b6969bf](https://linux-hardware.org/?probe=6f0b6969bf) | Jun 20, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [ae2beb307a](https://linux-hardware.org/?probe=ae2beb307a) | Jun 20, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [c2c2365360](https://linux-hardware.org/?probe=c2c2365360) | Jun 20, 2023 |
| Positivo      | POS-ECIG41BSA               | [abaf6ee67e](https://linux-hardware.org/?probe=abaf6ee67e) | Jun 20, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [689b10e4be](https://linux-hardware.org/?probe=689b10e4be) | Jun 19, 2023 |
| Lenovo        | NO DPK                      | [fedcf5f651](https://linux-hardware.org/?probe=fedcf5f651) | Jun 19, 2023 |
| PCWare        | IPMH61R3                    | [256988a55a](https://linux-hardware.org/?probe=256988a55a) | Jun 18, 2023 |
| Standard      | Unknown                     | [4956d7fc21](https://linux-hardware.org/?probe=4956d7fc21) | Jun 18, 2023 |
| Biostar       | A320MH                      | [0c38427f58](https://linux-hardware.org/?probe=0c38427f58) | Jun 18, 2023 |
| ZR            | A320M-F 1005                | [e3c749da2a](https://linux-hardware.org/?probe=e3c749da2a) | Jun 18, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [4bafdb9349](https://linux-hardware.org/?probe=4bafdb9349) | Jun 18, 2023 |
| Dell          | 01XK1W A00                  | [f431c0b66f](https://linux-hardware.org/?probe=f431c0b66f) | Jun 18, 2023 |
| PCWare        | IPX1800E1                   | [59b9fa6ff9](https://linux-hardware.org/?probe=59b9fa6ff9) | Jun 17, 2023 |
| ZR            | A320M-F 1005                | [c190f4fcff](https://linux-hardware.org/?probe=c190f4fcff) | Jun 17, 2023 |
| Intel         | H55                         | [d47f462b1a](https://linux-hardware.org/?probe=d47f462b1a) | Jun 17, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [b4cd8c843f](https://linux-hardware.org/?probe=b4cd8c843f) | Jun 17, 2023 |
| Lenovo        | 32E1 SDK0J40697 WIN 3305... | [c99587d0e0](https://linux-hardware.org/?probe=c99587d0e0) | Jun 16, 2023 |
| ASUSTek       | H61M-A/BR                   | [a587493314](https://linux-hardware.org/?probe=a587493314) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [8124f64b22](https://linux-hardware.org/?probe=8124f64b22) | Jun 16, 2023 |
| Intel         | H61                         | [ac7abe7025](https://linux-hardware.org/?probe=ac7abe7025) | Jun 16, 2023 |
| Intel         | H55                         | [76c89618f1](https://linux-hardware.org/?probe=76c89618f1) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [2a3068b835](https://linux-hardware.org/?probe=2a3068b835) | Jun 16, 2023 |
| Intel         | B85                         | [1e688ea5e1](https://linux-hardware.org/?probe=1e688ea5e1) | Jun 16, 2023 |
| Positivo      | POS-EINM70CS POS            | [a2d50f27d7](https://linux-hardware.org/?probe=a2d50f27d7) | Jun 16, 2023 |
| Pegatron      | IPMIP-GS                    | [fb51893272](https://linux-hardware.org/?probe=fb51893272) | Jun 15, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | [9c446242a8](https://linux-hardware.org/?probe=9c446242a8) | Jun 15, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [ecc8c7d2d0](https://linux-hardware.org/?probe=ecc8c7d2d0) | Jun 15, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [4cad282848](https://linux-hardware.org/?probe=4cad282848) | Jun 15, 2023 |
| Positivo      | POS-PIB150DT                | [cddf7d4ac9](https://linux-hardware.org/?probe=cddf7d4ac9) | Jun 15, 2023 |
| Unknown       | G41T-M7                     | [18a63d3a27](https://linux-hardware.org/?probe=18a63d3a27) | Jun 14, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [64da6bc381](https://linux-hardware.org/?probe=64da6bc381) | Jun 14, 2023 |
| Kllisre       | X99-B5 V1.1                 | [5e22a31b3e](https://linux-hardware.org/?probe=5e22a31b3e) | Jun 14, 2023 |
| Intel         | H61                         | [5d4fb99018](https://linux-hardware.org/?probe=5d4fb99018) | Jun 14, 2023 |
| Biostar       | B350GT3                     | [13b1026096](https://linux-hardware.org/?probe=13b1026096) | Jun 13, 2023 |
| HP            | 2AED                        | [2550c16272](https://linux-hardware.org/?probe=2550c16272) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [74b5d0e60a](https://linux-hardware.org/?probe=74b5d0e60a) | Jun 13, 2023 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [2b0095133a](https://linux-hardware.org/?probe=2b0095133a) | Jun 12, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [613d703a17](https://linux-hardware.org/?probe=613d703a17) | Jun 10, 2023 |
| Intel         | H81                         | [6a51c76e81](https://linux-hardware.org/?probe=6a51c76e81) | Jun 09, 2023 |
| Gigabyte      | 970A-DS3P                   | [1bae25f67b](https://linux-hardware.org/?probe=1bae25f67b) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [bcad738da6](https://linux-hardware.org/?probe=bcad738da6) | Jun 09, 2023 |
| ASUSTek       | P8H61-M LX                  | [28d0a897d3](https://linux-hardware.org/?probe=28d0a897d3) | Jun 09, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [c0fd33b9cc](https://linux-hardware.org/?probe=c0fd33b9cc) | Jun 09, 2023 |
| ASUSTek       | STRIX B250F GAMING          | [76c3e6625b](https://linux-hardware.org/?probe=76c3e6625b) | Jun 09, 2023 |
| Unknown       | GSUO H61V10C                | [0daf816953](https://linux-hardware.org/?probe=0daf816953) | Jun 09, 2023 |
| ASRock        | A320M-HD                    | [9e88454384](https://linux-hardware.org/?probe=9e88454384) | Jun 09, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [a8724dfd68](https://linux-hardware.org/?probe=a8724dfd68) | Jun 08, 2023 |
| Gigabyte      | H610M H DDR4                | [e7cdd7e89b](https://linux-hardware.org/?probe=e7cdd7e89b) | Jun 07, 2023 |
| DIEBOLD       | B85H3-M5                    | [7e56b1fd68](https://linux-hardware.org/?probe=7e56b1fd68) | Jun 07, 2023 |
| ASRock        | B450M Steel Legend          | [5d75bba35e](https://linux-hardware.org/?probe=5d75bba35e) | Jun 06, 2023 |
| ASRock        | H310M-HG4                   | [47b2817d31](https://linux-hardware.org/?probe=47b2817d31) | Jun 06, 2023 |
| Dell          | 0NW6H5 A00                  | [631e6bba84](https://linux-hardware.org/?probe=631e6bba84) | Jun 06, 2023 |
| Intel         | DP55WB AAE64798-204         | [fe09edbecc](https://linux-hardware.org/?probe=fe09edbecc) | Jun 06, 2023 |
| Unknown       | Unknown                     | [e8df83921f](https://linux-hardware.org/?probe=e8df83921f) | Jun 06, 2023 |
| ASUSTek       | M5A88-M                     | [bb29b433c0](https://linux-hardware.org/?probe=bb29b433c0) | Jun 05, 2023 |
| Intel         | DP965LT AAD41694-301        | [f72bcbf0a2](https://linux-hardware.org/?probe=f72bcbf0a2) | Jun 05, 2023 |
| Biostar       | B350GT3                     | [b425f8d45a](https://linux-hardware.org/?probe=b425f8d45a) | Jun 05, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [8cbfe4cdf0](https://linux-hardware.org/?probe=8cbfe4cdf0) | Jun 05, 2023 |
| ASUSTek       | PRIME B350M-A               | [3a0576b177](https://linux-hardware.org/?probe=3a0576b177) | Jun 05, 2023 |
| ASUSTek       | M5A88-M                     | [e750392f99](https://linux-hardware.org/?probe=e750392f99) | Jun 04, 2023 |
| Dell          | 09D7F7 A00                  | [9b80703b01](https://linux-hardware.org/?probe=9b80703b01) | Jun 04, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | [f71eae78c5](https://linux-hardware.org/?probe=f71eae78c5) | Jun 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | [aafda7cf63](https://linux-hardware.org/?probe=aafda7cf63) | Jun 04, 2023 |
| Dell          | 01XK1W A00                  | [8690705151](https://linux-hardware.org/?probe=8690705151) | Jun 04, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | [8b790b76a6](https://linux-hardware.org/?probe=8b790b76a6) | Jun 03, 2023 |
| Biostar       | B450MX-S                    | [ccc6b5c4b5](https://linux-hardware.org/?probe=ccc6b5c4b5) | Jun 03, 2023 |
| Biostar       | B450MX-S                    | [6a01df1d69](https://linux-hardware.org/?probe=6a01df1d69) | Jun 03, 2023 |
| Positivo      | POS-EINM70CS POS            | [80260b495c](https://linux-hardware.org/?probe=80260b495c) | Jun 03, 2023 |
| Positivo      | POS-PIG41BA                 | [f630c0b9cd](https://linux-hardware.org/?probe=f630c0b9cd) | Jun 03, 2023 |
| Intel         | B75                         | [2387f30645](https://linux-hardware.org/?probe=2387f30645) | Jun 03, 2023 |
| Positivo      | POS-RIB360EE 11144907       | [7837922f5b](https://linux-hardware.org/?probe=7837922f5b) | Jun 02, 2023 |
| Dell          | 0GX832 A01                  | [19b718a96c](https://linux-hardware.org/?probe=19b718a96c) | Jun 02, 2023 |
| Unknown       | X99                         | [0ffca5934a](https://linux-hardware.org/?probe=0ffca5934a) | Jun 02, 2023 |
| Gigabyte      | Z590 UD AC                  | [da5b2056e4](https://linux-hardware.org/?probe=da5b2056e4) | Jun 02, 2023 |
| Positivo      | POS-RIB360EE 11144907       | [b4ba7702cb](https://linux-hardware.org/?probe=b4ba7702cb) | Jun 02, 2023 |
| Dell          | 01XK1W A00                  | [5846820609](https://linux-hardware.org/?probe=5846820609) | Jun 02, 2023 |
| ASUSTek       | PRIME X570-P                | [cde4aaef3e](https://linux-hardware.org/?probe=cde4aaef3e) | Jun 01, 2023 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [7ac5ec7c05](https://linux-hardware.org/?probe=7ac5ec7c05) | Jun 01, 2023 |
| AZW           | GTR V02                     | [bd1740c7b2](https://linux-hardware.org/?probe=bd1740c7b2) | May 31, 2023 |
| AZW           | GTR V02                     | [cab90f1838](https://linux-hardware.org/?probe=cab90f1838) | May 31, 2023 |
| Dell          | 01XK1W A00                  | [8a18b7bada](https://linux-hardware.org/?probe=8a18b7bada) | May 31, 2023 |
| Dell          | 01XK1W A00                  | [611cf59f44](https://linux-hardware.org/?probe=611cf59f44) | May 31, 2023 |
| MSI           | B450M MORTAR MAX            | [1d0c56937c](https://linux-hardware.org/?probe=1d0c56937c) | May 31, 2023 |
| ASRock        | H310CM-HG4                  | [9fa8d9d320](https://linux-hardware.org/?probe=9fa8d9d320) | May 30, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | [2334995ee9](https://linux-hardware.org/?probe=2334995ee9) | May 30, 2023 |
| Dell          | 0GXM1W A02                  | [9c252c8688](https://linux-hardware.org/?probe=9c252c8688) | May 30, 2023 |
| Itautec       | ST 4265                     | [8814373cb4](https://linux-hardware.org/?probe=8814373cb4) | May 29, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [e29eb3dfcc](https://linux-hardware.org/?probe=e29eb3dfcc) | May 29, 2023 |
| Itautec       | ST 4265                     | [b89c45a31d](https://linux-hardware.org/?probe=b89c45a31d) | May 29, 2023 |
| Dell          | 0NM64V A01                  | [a109a924f0](https://linux-hardware.org/?probe=a109a924f0) | May 29, 2023 |
| ASRock        | B450M Steel Legend          | [b8436530b0](https://linux-hardware.org/?probe=b8436530b0) | May 28, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [40ba623a3e](https://linux-hardware.org/?probe=40ba623a3e) | May 28, 2023 |
| MSI           | A520M-A PRO                 | [c78b5e28f1](https://linux-hardware.org/?probe=c78b5e28f1) | May 28, 2023 |
| ASRock        | H510M-HVS R2.0              | [c4ee84b38e](https://linux-hardware.org/?probe=c4ee84b38e) | May 28, 2023 |
| Dell          | 01XK1W A00                  | [a81daffe89](https://linux-hardware.org/?probe=a81daffe89) | May 28, 2023 |
| Intel         | X99                         | [6826d78921](https://linux-hardware.org/?probe=6826d78921) | May 28, 2023 |
| Dell          | 01XK1W A00                  | [ef918dfbfa](https://linux-hardware.org/?probe=ef918dfbfa) | May 28, 2023 |
| Intel         | X58M                        | [912addab98](https://linux-hardware.org/?probe=912addab98) | May 27, 2023 |
| Intel         | DH77EB AAG39073-304         | [8310aaaa78](https://linux-hardware.org/?probe=8310aaaa78) | May 27, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [ad8e3ea3ea](https://linux-hardware.org/?probe=ad8e3ea3ea) | May 27, 2023 |
| Wistron       | ProLiant ML110 G6           | [bc1c76bb8f](https://linux-hardware.org/?probe=bc1c76bb8f) | May 27, 2023 |
| Intel         | DH77EB AAG39073-304         | [86545c89c0](https://linux-hardware.org/?probe=86545c89c0) | May 27, 2023 |
| Intel         | B75                         | [8dba7fa195](https://linux-hardware.org/?probe=8dba7fa195) | May 27, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [1cbedc352f](https://linux-hardware.org/?probe=1cbedc352f) | May 26, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [4fedff68f1](https://linux-hardware.org/?probe=4fedff68f1) | May 26, 2023 |
| Gigabyte      | B450 AORUS M                | [40af2d79f9](https://linux-hardware.org/?probe=40af2d79f9) | May 26, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [248bd35ba0](https://linux-hardware.org/?probe=248bd35ba0) | May 26, 2023 |
| ASUSTek       | H110M-C/BR                  | [1c272c65dc](https://linux-hardware.org/?probe=1c272c65dc) | May 26, 2023 |
| ASRock        | A320M-HDV R4.0              | [c897394a34](https://linux-hardware.org/?probe=c897394a34) | May 26, 2023 |
| Toshiba       | STI 005492G                 | [4f161f4ed0](https://linux-hardware.org/?probe=4f161f4ed0) | May 26, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | [a49bd1dd26](https://linux-hardware.org/?probe=a49bd1dd26) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2a3382aa0c](https://linux-hardware.org/?probe=2a3382aa0c) | May 25, 2023 |
| PCWare        | IPMH110G                    | [33b6fce5ff](https://linux-hardware.org/?probe=33b6fce5ff) | May 25, 2023 |
| Biostar       | A68MHE                      | [d1ef52da36](https://linux-hardware.org/?probe=d1ef52da36) | May 25, 2023 |
| ASUSTek       | PRIME B760M-A D4            | [95321eedeb](https://linux-hardware.org/?probe=95321eedeb) | May 25, 2023 |
| Biostar       | A68MHE                      | [e2244a8ed0](https://linux-hardware.org/?probe=e2244a8ed0) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [2c31d88fa2](https://linux-hardware.org/?probe=2c31d88fa2) | May 25, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [efb5aa9bfc](https://linux-hardware.org/?probe=efb5aa9bfc) | May 24, 2023 |
| ASUSTek       | PRIME H510M-E               | [1247209c34](https://linux-hardware.org/?probe=1247209c34) | May 24, 2023 |
| Biostar       | N61PB-M2S                   | [e4669affdb](https://linux-hardware.org/?probe=e4669affdb) | May 24, 2023 |
| AZW           | SEi                         | [bc0c7a512f](https://linux-hardware.org/?probe=bc0c7a512f) | May 24, 2023 |
| ASRock        | A320M-HDV R4.0              | [bce76b90ef](https://linux-hardware.org/?probe=bce76b90ef) | May 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | [44861be08c](https://linux-hardware.org/?probe=44861be08c) | May 24, 2023 |
| AZW           | SEi                         | [825fbaebcd](https://linux-hardware.org/?probe=825fbaebcd) | May 23, 2023 |
| ASUSTek       | B85M-E/BR                   | [ed20b84824](https://linux-hardware.org/?probe=ed20b84824) | May 23, 2023 |
| Intel         | H61                         | [794ecc6c43](https://linux-hardware.org/?probe=794ecc6c43) | May 23, 2023 |
| Gigabyte      | 970A-DS3P FX                | [9063693561](https://linux-hardware.org/?probe=9063693561) | May 23, 2023 |
| Gigabyte      | A320M-S2H-CF SE1            | [61ede8f95d](https://linux-hardware.org/?probe=61ede8f95d) | May 23, 2023 |
| Intel         | DP55WB AAE64798-205         | [91bb4c8e5d](https://linux-hardware.org/?probe=91bb4c8e5d) | May 22, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [2f1b921a18](https://linux-hardware.org/?probe=2f1b921a18) | May 22, 2023 |
| Gigabyte      | A320M-S2H-CF                | [7ff619a028](https://linux-hardware.org/?probe=7ff619a028) | May 21, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [2a95b22ac3](https://linux-hardware.org/?probe=2a95b22ac3) | May 21, 2023 |
| ASRock        | H310CM-HG4                  | [6f698f47d8](https://linux-hardware.org/?probe=6f698f47d8) | May 21, 2023 |
| Unknown       | GSUO H61V10C                | [8e1037e4c1](https://linux-hardware.org/?probe=8e1037e4c1) | May 20, 2023 |
| ASRock        | 970A-G                      | [fd39b2185b](https://linux-hardware.org/?probe=fd39b2185b) | May 20, 2023 |
| Gigabyte      | B660M AORUS PRO DDR4        | [6a3afbb593](https://linux-hardware.org/?probe=6a3afbb593) | May 20, 2023 |
| Dell          | 0VTJVC A00                  | [1acd938f30](https://linux-hardware.org/?probe=1acd938f30) | May 20, 2023 |
| ASRock        | 970A-G                      | [fac3e3c961](https://linux-hardware.org/?probe=fac3e3c961) | May 20, 2023 |
| ASRock        | A320M-HD                    | [1a05e80ee5](https://linux-hardware.org/?probe=1a05e80ee5) | May 20, 2023 |
| MSI           | X99S SLI PLUS               | [35b5231ed2](https://linux-hardware.org/?probe=35b5231ed2) | May 20, 2023 |
| Daten Tecn... | DA320MXV DC                 | [0b7e1e51b9](https://linux-hardware.org/?probe=0b7e1e51b9) | May 20, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [986792e4f0](https://linux-hardware.org/?probe=986792e4f0) | May 19, 2023 |
| ASRock        | Z590M Pro4                  | [d039ed90c5](https://linux-hardware.org/?probe=d039ed90c5) | May 19, 2023 |
| Gigabyte      | H510M H                     | [39725fefa4](https://linux-hardware.org/?probe=39725fefa4) | May 19, 2023 |
| MSI           | H110M PRO-VH PLUS           | [14985fd04f](https://linux-hardware.org/?probe=14985fd04f) | May 18, 2023 |
| Megaware      | MW-H61M-2H v1.3 - 17/07/... | [72303201a3](https://linux-hardware.org/?probe=72303201a3) | May 18, 2023 |
| PCWare        | IPX1800E2                   | [f19d94af88](https://linux-hardware.org/?probe=f19d94af88) | May 18, 2023 |
| PCWare        | IPX1800E2                   | [a75df73ade](https://linux-hardware.org/?probe=a75df73ade) | May 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [be46da6480](https://linux-hardware.org/?probe=be46da6480) | May 18, 2023 |
| ASUSTek       | H81M-A/BR                   | [0982e8a637](https://linux-hardware.org/?probe=0982e8a637) | May 17, 2023 |
| ASUSTek       | P7H55D-M PRO                | [2c423cf3e9](https://linux-hardware.org/?probe=2c423cf3e9) | May 17, 2023 |
| Pegatron      | Yangtze                     | [4e3ce38e7b](https://linux-hardware.org/?probe=4e3ce38e7b) | May 17, 2023 |
| ASUSTek       | P7H55D-M PRO                | [dc1bf86813](https://linux-hardware.org/?probe=dc1bf86813) | May 17, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | [dc2f3b9cdc](https://linux-hardware.org/?probe=dc2f3b9cdc) | May 17, 2023 |
| Intel         | DG41WV AAE90316-101         | [9bef3b952d](https://linux-hardware.org/?probe=9bef3b952d) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [9dd2c4cbee](https://linux-hardware.org/?probe=9dd2c4cbee) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | [dfc49eb820](https://linux-hardware.org/?probe=dfc49eb820) | May 16, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [3f5bade9b8](https://linux-hardware.org/?probe=3f5bade9b8) | May 16, 2023 |
| Intel         | H61                         | [c54c89a4b1](https://linux-hardware.org/?probe=c54c89a4b1) | May 16, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [377fe6aa67](https://linux-hardware.org/?probe=377fe6aa67) | May 16, 2023 |
| Gigabyte      | 970A-DS3P FX                | [b25434cdf3](https://linux-hardware.org/?probe=b25434cdf3) | May 15, 2023 |
| ASUSTek       | Z97M-PLUS/BR                | [dc06cb0aba](https://linux-hardware.org/?probe=dc06cb0aba) | May 15, 2023 |
| Gigabyte      | Z170X-UD5-CF                | [429dc207a6](https://linux-hardware.org/?probe=429dc207a6) | May 15, 2023 |
| Gigabyte      | Z170X-UD5-CF                | [f887e6f037](https://linux-hardware.org/?probe=f887e6f037) | May 15, 2023 |
| Dell          | 024JD7 A00                  | [904e4e2a0d](https://linux-hardware.org/?probe=904e4e2a0d) | May 15, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [58f493d242](https://linux-hardware.org/?probe=58f493d242) | May 15, 2023 |
| Gigabyte      | 970A-DS3P FX                | [7fe35591e7](https://linux-hardware.org/?probe=7fe35591e7) | May 14, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [38b6dd7b3f](https://linux-hardware.org/?probe=38b6dd7b3f) | May 14, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [65374a707a](https://linux-hardware.org/?probe=65374a707a) | May 14, 2023 |
| Gigabyte      | 970A-DS3P FX                | [4e208c9155](https://linux-hardware.org/?probe=4e208c9155) | May 14, 2023 |
| Intel         | X79F1 V2.0                  | [a2446b63b3](https://linux-hardware.org/?probe=a2446b63b3) | May 14, 2023 |
| Intel         | H61 V1.1                    | [f5cbf650c3](https://linux-hardware.org/?probe=f5cbf650c3) | May 14, 2023 |
| Daten Tecn... | DH110MXV                    | [4fd655c0aa](https://linux-hardware.org/?probe=4fd655c0aa) | May 13, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [2c03c64f49](https://linux-hardware.org/?probe=2c03c64f49) | May 13, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | [e5dbe4c6f4](https://linux-hardware.org/?probe=e5dbe4c6f4) | May 13, 2023 |
| Intel         | B75                         | [da0a89cf17](https://linux-hardware.org/?probe=da0a89cf17) | May 13, 2023 |
| Dell          | 01XK1W A00                  | [b15a6ee63f](https://linux-hardware.org/?probe=b15a6ee63f) | May 13, 2023 |
| Toshiba       | STI 007567                  | [579ec5bb2b](https://linux-hardware.org/?probe=579ec5bb2b) | May 13, 2023 |
| Gigabyte      | B450M AORUS ELITE           | [3a0e10e849](https://linux-hardware.org/?probe=3a0e10e849) | May 12, 2023 |
| Huanan        | B75 V10.1 376               | [3293d10187](https://linux-hardware.org/?probe=3293d10187) | May 12, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [7b966568cc](https://linux-hardware.org/?probe=7b966568cc) | May 12, 2023 |
| Biostar       | A320MH                      | [d30baf9379](https://linux-hardware.org/?probe=d30baf9379) | May 12, 2023 |
| MSI           | H61M-P20/W8                 | [b727300be6](https://linux-hardware.org/?probe=b727300be6) | May 11, 2023 |
| Huanan        | B75 V10.1 376               | [3c8b5aefd8](https://linux-hardware.org/?probe=3c8b5aefd8) | May 11, 2023 |
| Gigabyte      | H61M-S1                     | [db910d4ee1](https://linux-hardware.org/?probe=db910d4ee1) | May 11, 2023 |
| Gigabyte      | B75M-D3H                    | [dbf711a2f5](https://linux-hardware.org/?probe=dbf711a2f5) | May 11, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS II    | [3cccf183d9](https://linux-hardware.org/?probe=3cccf183d9) | May 11, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [1b0cd4f3e1](https://linux-hardware.org/?probe=1b0cd4f3e1) | May 11, 2023 |
| Dell          | 076VHM A02                  | [7f1984ec16](https://linux-hardware.org/?probe=7f1984ec16) | May 10, 2023 |
| Dell          | 0GDG8Y A00                  | [e9e13fa531](https://linux-hardware.org/?probe=e9e13fa531) | May 10, 2023 |
| ASRock        | H110M-HG4                   | [7995d3740a](https://linux-hardware.org/?probe=7995d3740a) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [cb4250603d](https://linux-hardware.org/?probe=cb4250603d) | May 10, 2023 |
| ASRock        | H110M-HG4                   | [2864ff8227](https://linux-hardware.org/?probe=2864ff8227) | May 10, 2023 |
| HP            | 0A60h                       | [972820a864](https://linux-hardware.org/?probe=972820a864) | May 10, 2023 |
| ASRock        | N68-S3 FX                   | [0ed94fe810](https://linux-hardware.org/?probe=0ed94fe810) | May 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [6ddb2fa975](https://linux-hardware.org/?probe=6ddb2fa975) | May 10, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [16bdfe6490](https://linux-hardware.org/?probe=16bdfe6490) | May 10, 2023 |
| Dell          | 0D883F A06                  | [18afa7a07b](https://linux-hardware.org/?probe=18afa7a07b) | May 10, 2023 |
| Dell          | 0VXN67 A01                  | [0985b52dee](https://linux-hardware.org/?probe=0985b52dee) | May 09, 2023 |
| Dell          | 0VXN67 A01                  | [b7fd2a3e2f](https://linux-hardware.org/?probe=b7fd2a3e2f) | May 09, 2023 |
| ASRock        | H310CM-HG4                  | [756ed502db](https://linux-hardware.org/?probe=756ed502db) | May 09, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [631317f909](https://linux-hardware.org/?probe=631317f909) | May 08, 2023 |
| Gigabyte      | F2A68HM-H                   | [97986b63ad](https://linux-hardware.org/?probe=97986b63ad) | May 08, 2023 |
| Gigabyte      | G41MT-S2                    | [0458d9f44b](https://linux-hardware.org/?probe=0458d9f44b) | May 08, 2023 |
| Unknown       | Unknown                     | [68e1c1b5a4](https://linux-hardware.org/?probe=68e1c1b5a4) | May 07, 2023 |
| ASUSTek       | M4N68T-M LE                 | [0c3f2af7ad](https://linux-hardware.org/?probe=0c3f2af7ad) | May 07, 2023 |
| Intel         | H61                         | [c359f42a22](https://linux-hardware.org/?probe=c359f42a22) | May 07, 2023 |
| Intel         | D946GZIS AAD66165-301       | [c350f5ed12](https://linux-hardware.org/?probe=c350f5ed12) | May 06, 2023 |
| Lenovo        | NO DPK                      | [15e77c1f0a](https://linux-hardware.org/?probe=15e77c1f0a) | May 06, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [812ae9a763](https://linux-hardware.org/?probe=812ae9a763) | May 06, 2023 |
| Gigabyte      | GA-970A-UD3                 | [05c9e752a5](https://linux-hardware.org/?probe=05c9e752a5) | May 06, 2023 |
| HP            | 1998                        | [59c2c05cdb](https://linux-hardware.org/?probe=59c2c05cdb) | May 05, 2023 |
| Biostar       | G41D3C                      | [15680367e1](https://linux-hardware.org/?probe=15680367e1) | May 05, 2023 |
| ASRock        | A320M-HDV R4.0              | [d27392828f](https://linux-hardware.org/?probe=d27392828f) | May 05, 2023 |
| ASRock        | H81M-HG4 R4.0               | [cc6641b5d9](https://linux-hardware.org/?probe=cc6641b5d9) | May 04, 2023 |
| Unknown       | Unknown                     | [93a11302fb](https://linux-hardware.org/?probe=93a11302fb) | May 03, 2023 |
| MSI           | MEG Z390 GODLIKE            | [89a9759dfb](https://linux-hardware.org/?probe=89a9759dfb) | May 03, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [f4678817a9](https://linux-hardware.org/?probe=f4678817a9) | May 03, 2023 |
| HP            | 83E2                        | [7facfe6465](https://linux-hardware.org/?probe=7facfe6465) | May 02, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [d817c9a53f](https://linux-hardware.org/?probe=d817c9a53f) | May 02, 2023 |
| Gigabyte      | Z170X-Gaming 7              | [a14544f923](https://linux-hardware.org/?probe=a14544f923) | May 02, 2023 |
| Unknown       | Phitronics N68C-M           | [77747ce79b](https://linux-hardware.org/?probe=77747ce79b) | May 02, 2023 |
| ASUSTek       | PRIME A520M-E               | [f149f8c9fb](https://linux-hardware.org/?probe=f149f8c9fb) | May 02, 2023 |
| Apple         | Mac-F4208DC8 PVT            | [16cac427e3](https://linux-hardware.org/?probe=16cac427e3) | May 02, 2023 |
| Apple         | Mac-F4208DC8 PVT            | [45f6915427](https://linux-hardware.org/?probe=45f6915427) | May 02, 2023 |
| ASUSTek       | M5A78L-M LX3 PLUS           | [a41adc3f79](https://linux-hardware.org/?probe=a41adc3f79) | May 02, 2023 |
| Intel         | H61                         | [aa4606c36c](https://linux-hardware.org/?probe=aa4606c36c) | May 02, 2023 |
| Intel         | D946GZIS AAD66165-301       | [e61e22863f](https://linux-hardware.org/?probe=e61e22863f) | May 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | [9ff86ca1f1](https://linux-hardware.org/?probe=9ff86ca1f1) | May 01, 2023 |
| Intel         | H55                         | [04dd5e834e](https://linux-hardware.org/?probe=04dd5e834e) | May 01, 2023 |
| Daten Tecn... | DH110MXV                    | [96402fa64a](https://linux-hardware.org/?probe=96402fa64a) | May 01, 2023 |
| Lenovo        | NO DPK                      | [6997ff96eb](https://linux-hardware.org/?probe=6997ff96eb) | May 01, 2023 |
| MSI           | A520M-A PRO                 | [aa8e8397f6](https://linux-hardware.org/?probe=aa8e8397f6) | May 01, 2023 |
| PCWare        | IPMH410E                    | [9be4314a33](https://linux-hardware.org/?probe=9be4314a33) | May 01, 2023 |
| DIEBOLD       | NM70-I                      | [c01a40d58c](https://linux-hardware.org/?probe=c01a40d58c) | Apr 30, 2023 |
| ASRock        | B550M Steel Legend          | [68d85dd28f](https://linux-hardware.org/?probe=68d85dd28f) | Apr 30, 2023 |
| ASRock        | B550M Steel Legend          | [5166f820a6](https://linux-hardware.org/?probe=5166f820a6) | Apr 30, 2023 |
| ASRock        | 760GM-HD                    | [db79e93331](https://linux-hardware.org/?probe=db79e93331) | Apr 30, 2023 |
| MSI           | MEG Z390 GODLIKE            | [9109b0a7ed](https://linux-hardware.org/?probe=9109b0a7ed) | Apr 30, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | [2e2b57b3ae](https://linux-hardware.org/?probe=2e2b57b3ae) | Apr 30, 2023 |
| ASRock        | B450M Steel Legend          | [fed083feba](https://linux-hardware.org/?probe=fed083feba) | Apr 30, 2023 |
| Intel         | H61                         | [167616bc61](https://linux-hardware.org/?probe=167616bc61) | Apr 30, 2023 |
| Intel         | H81                         | [c70b10516b](https://linux-hardware.org/?probe=c70b10516b) | Apr 30, 2023 |
| ASUSTek       | PRIME H410M-E               | [44a08af32f](https://linux-hardware.org/?probe=44a08af32f) | Apr 29, 2023 |
| ASUSTek       | H81M-C/BR                   | [32942be783](https://linux-hardware.org/?probe=32942be783) | Apr 29, 2023 |
| Gigabyte      | G41MT-S2                    | [ba5c65f4e3](https://linux-hardware.org/?probe=ba5c65f4e3) | Apr 29, 2023 |
| ASUSTek       | P8H61-M LE/BR               | [425f1a3e08](https://linux-hardware.org/?probe=425f1a3e08) | Apr 29, 2023 |
| Gigabyte      | GA-78LMT-S2                 | [16b28befee](https://linux-hardware.org/?probe=16b28befee) | Apr 28, 2023 |
| ASRock        | A320M-HD                    | [43b57e5088](https://linux-hardware.org/?probe=43b57e5088) | Apr 28, 2023 |
| HP            | 158B                        | [ee0297b0ba](https://linux-hardware.org/?probe=ee0297b0ba) | Apr 28, 2023 |
| Intel         | H61 V124                    | [1fa0b34b3c](https://linux-hardware.org/?probe=1fa0b34b3c) | Apr 28, 2023 |
| Lenovo        | NO DPK                      | [d3442220b0](https://linux-hardware.org/?probe=d3442220b0) | Apr 28, 2023 |
| Intel         | H61                         | [b8f0acdf61](https://linux-hardware.org/?probe=b8f0acdf61) | Apr 28, 2023 |
| ASUSTek       | Z97M-PLUS/BR                | [3255acf414](https://linux-hardware.org/?probe=3255acf414) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | [9211d42ee3](https://linux-hardware.org/?probe=9211d42ee3) | Apr 27, 2023 |
| HP            | 3047h                       | [3e6dada8a9](https://linux-hardware.org/?probe=3e6dada8a9) | Apr 26, 2023 |
| Pegatron      | IPM41-D3                    | [faf8704eb3](https://linux-hardware.org/?probe=faf8704eb3) | Apr 26, 2023 |
| MSI           | MAG B550M MORTAR            | [f91ac46cfd](https://linux-hardware.org/?probe=f91ac46cfd) | Apr 26, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [8f417742d1](https://linux-hardware.org/?probe=8f417742d1) | Apr 26, 2023 |
| Biostar       | H610MH                      | [935928c60d](https://linux-hardware.org/?probe=935928c60d) | Apr 26, 2023 |
| Gigabyte      | B550M DS3H                  | [208a0fc365](https://linux-hardware.org/?probe=208a0fc365) | Apr 26, 2023 |
| Intel         | B75                         | [72a3677ac2](https://linux-hardware.org/?probe=72a3677ac2) | Apr 26, 2023 |
| ASUSTek       | PRIME H610M-A D4            | [a7e77375d4](https://linux-hardware.org/?probe=a7e77375d4) | Apr 26, 2023 |
| Intel         | H81                         | [9a14132581](https://linux-hardware.org/?probe=9a14132581) | Apr 26, 2023 |
| ASRock        | AB350M-HDV                  | [44ac797451](https://linux-hardware.org/?probe=44ac797451) | Apr 25, 2023 |
| Biostar       | B450MX-S                    | [5ac7debff3](https://linux-hardware.org/?probe=5ac7debff3) | Apr 25, 2023 |
| Gigabyte      | H87-D3H-CF                  | [b3a3115f0c](https://linux-hardware.org/?probe=b3a3115f0c) | Apr 25, 2023 |
| OEM           | HN B85 Ver:1.4              | [1da5934b27](https://linux-hardware.org/?probe=1da5934b27) | Apr 25, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [342918aa38](https://linux-hardware.org/?probe=342918aa38) | Apr 24, 2023 |
| AMD           | Inagua CRB                  | [085d0aa051](https://linux-hardware.org/?probe=085d0aa051) | Apr 24, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [9bab79728a](https://linux-hardware.org/?probe=9bab79728a) | Apr 24, 2023 |
| Intel         | D946GZIS AAD66165-301       | [9d5ada0fc4](https://linux-hardware.org/?probe=9d5ada0fc4) | Apr 24, 2023 |
| Dell          | 0VTJVC A00                  | [da7d66917d](https://linux-hardware.org/?probe=da7d66917d) | Apr 24, 2023 |
| Gigabyte      | G41MT-S2                    | [de1981f9e6](https://linux-hardware.org/?probe=de1981f9e6) | Apr 24, 2023 |
| Huanan        | X99-8M-F V1.1               | [0621d00b73](https://linux-hardware.org/?probe=0621d00b73) | Apr 24, 2023 |
| Biostar       | B350ET2                     | [47289e48eb](https://linux-hardware.org/?probe=47289e48eb) | Apr 23, 2023 |
| ASUSTek       | AM1M-A/BR                   | [0b29ee62f9](https://linux-hardware.org/?probe=0b29ee62f9) | Apr 23, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [0e85243397](https://linux-hardware.org/?probe=0e85243397) | Apr 23, 2023 |
| HP            | 18E7                        | [c5bc4d9c7f](https://linux-hardware.org/?probe=c5bc4d9c7f) | Apr 23, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | [eebce73217](https://linux-hardware.org/?probe=eebce73217) | Apr 23, 2023 |
| ASUSTek       | H81M-C/BR                   | [46a27a7551](https://linux-hardware.org/?probe=46a27a7551) | Apr 23, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [793e094165](https://linux-hardware.org/?probe=793e094165) | Apr 23, 2023 |
| Pegatron      | IPMH61P1                    | [b71d5b1a48](https://linux-hardware.org/?probe=b71d5b1a48) | Apr 23, 2023 |
| Unknown       | G41                         | [cbe978cc34](https://linux-hardware.org/?probe=cbe978cc34) | Apr 23, 2023 |
| Gigabyte      | VM900M Rev2.0               | [284ada7211](https://linux-hardware.org/?probe=284ada7211) | Apr 23, 2023 |
| PCWare        | IPX1800G2                   | [f63cf0fe51](https://linux-hardware.org/?probe=f63cf0fe51) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [1b475eaa99](https://linux-hardware.org/?probe=1b475eaa99) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [dfb9f87dad](https://linux-hardware.org/?probe=dfb9f87dad) | Apr 22, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [ea8fb664a3](https://linux-hardware.org/?probe=ea8fb664a3) | Apr 22, 2023 |
| ASRock        | H310CM-HG4                  | [6f49f4b883](https://linux-hardware.org/?probe=6f49f4b883) | Apr 21, 2023 |
| ASRock        | H510M-HVS R2.0              | [1de5b776a3](https://linux-hardware.org/?probe=1de5b776a3) | Apr 21, 2023 |
| Dell          | 0GDG8Y A00                  | [a315eaa776](https://linux-hardware.org/?probe=a315eaa776) | Apr 21, 2023 |
| MSI           | 970 GAMING                  | [cb295448b6](https://linux-hardware.org/?probe=cb295448b6) | Apr 21, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [5f1a1c6abd](https://linux-hardware.org/?probe=5f1a1c6abd) | Apr 20, 2023 |
| Gigabyte      | G31M-S2C                    | [0c45fc6929](https://linux-hardware.org/?probe=0c45fc6929) | Apr 20, 2023 |
| ASRock        | FM2A68M-DG3+                | [f8519c5a20](https://linux-hardware.org/?probe=f8519c5a20) | Apr 20, 2023 |
| Intel         | H61S                        | [e29d71587a](https://linux-hardware.org/?probe=e29d71587a) | Apr 20, 2023 |
| ASRock        | FM2A68M-DG3+                | [701110cf4e](https://linux-hardware.org/?probe=701110cf4e) | Apr 19, 2023 |
| ASUSTek       | PRIME B250M-PLUS/BR         | [c0a82bb35a](https://linux-hardware.org/?probe=c0a82bb35a) | Apr 19, 2023 |
| Intel         | X79M-S                      | [0c51f5a0e0](https://linux-hardware.org/?probe=0c51f5a0e0) | Apr 19, 2023 |
| ASUSTek       | PRIME B250M-PLUS/BR         | [8bb9dc2419](https://linux-hardware.org/?probe=8bb9dc2419) | Apr 18, 2023 |
| AMD           | Inagua CRB                  | [8d2ce37fca](https://linux-hardware.org/?probe=8d2ce37fca) | Apr 18, 2023 |
| Dell          | 08NPPY A00                  | [7fcc7d1b34](https://linux-hardware.org/?probe=7fcc7d1b34) | Apr 18, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | [bbbc9206b4](https://linux-hardware.org/?probe=bbbc9206b4) | Apr 17, 2023 |
| Intel         | B75                         | [18dce6805d](https://linux-hardware.org/?probe=18dce6805d) | Apr 15, 2023 |
| AMD           | A88F2EKS                    | [48cef621bd](https://linux-hardware.org/?probe=48cef621bd) | Apr 15, 2023 |
| ASUSTek       | M4A785TD-M EVO              | [dd2d3443a9](https://linux-hardware.org/?probe=dd2d3443a9) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | [e412c388d8](https://linux-hardware.org/?probe=e412c388d8) | Apr 15, 2023 |
| QIYIDA        | X99-H9 V2.0                 | [fcfa1ed488](https://linux-hardware.org/?probe=fcfa1ed488) | Apr 14, 2023 |
| ASRock        | B550M Pro4                  | [ec08193576](https://linux-hardware.org/?probe=ec08193576) | Apr 14, 2023 |
| Gigabyte      | 970A-DS3P                   | [e2f136f068](https://linux-hardware.org/?probe=e2f136f068) | Apr 14, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 578      | 10.35%  |
| Ubuntu 18.04                 | 411      | 7.36%   |
| Ubuntu 22.04                 | 227      | 4.07%   |
| OpenMandriva 4.2             | 173      | 3.1%    |
| OpenMandriva 4.3             | 143      | 2.56%   |
| Linux Mint 20                | 119      | 2.13%   |
| Linux Mint 19.3              | 119      | 2.13%   |
| Pop!_OS 20.04                | 114      | 2.04%   |
| Linux Mint 19.1              | 110      | 1.97%   |
| KDE neon 20.04               | 98       | 1.76%   |
| Zorin 16                     | 96       | 1.72%   |
| Ubuntu 19.04                 | 95       | 1.7%    |
| Pop!_OS 22.04                | 93       | 1.67%   |
| Linux Mint 20.1              | 91       | 1.63%   |
| Manjaro                      | 87       | 1.56%   |
| Linux Mint 20.3              | 81       | 1.45%   |
| Arch Rolling                 | 81       | 1.45%   |
| Debian 11                    | 77       | 1.38%   |
| Fedora 38                    | 72       | 1.29%   |
| Linux Mint 21.1              | 69       | 1.24%   |
| Arch                         | 69       | 1.24%   |
| OpenMandriva 23.03           | 67       | 1.2%    |
| Linux Mint 20.2              | 67       | 1.2%    |
| Pop!_OS 20.10                | 61       | 1.09%   |
| Debian 10                    | 61       | 1.09%   |
| Ubuntu MATE 20.04            | 59       | 1.06%   |
| Ubuntu 19.10                 | 58       | 1.04%   |
| Pop!_OS 21.04                | 57       | 1.02%   |
| Zorin 15                     | 54       | 0.97%   |
| OpenMandriva 23.08           | 53       | 0.95%   |
| OpenMandriva 23.01           | 53       | 0.95%   |
| Linux Mint 19.2              | 49       | 0.88%   |
| Fedora 36                    | 49       | 0.88%   |
| Fedora 37                    | 48       | 0.86%   |
| Linux Mint 21                | 47       | 0.84%   |
| Xubuntu 20.04                | 46       | 0.82%   |
| Fedora 34                    | 43       | 0.77%   |
| ArcoLinux Rolling            | 42       | 0.75%   |
| openSUSE Tumbleweed-XXXXXXXX | 40       | 0.72%   |
| Fedora 32                    | 39       | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 1523     | 28.74%  |
| Linux Mint    | 768      | 14.49%  |
| OpenMandriva  | 505      | 9.53%   |
| Pop!_OS       | 341      | 6.44%   |
| Fedora        | 316      | 5.96%   |
| Debian        | 210      | 3.96%   |
| Manjaro       | 166      | 3.13%   |
| Endless       | 165      | 3.11%   |
| Zorin         | 155      | 2.93%   |
| Arch          | 147      | 2.77%   |
| KDE neon      | 122      | 2.3%    |
| Xubuntu       | 104      | 1.96%   |
| Kubuntu       | 92       | 1.74%   |
| ROSA          | 79       | 1.49%   |
| Ubuntu MATE   | 74       | 1.4%    |
| openSUSE      | 64       | 1.21%   |
| ArcoLinux     | 43       | 0.81%   |
| Lubuntu       | 36       | 0.68%   |
| Ubuntu Unity  | 34       | 0.64%   |
| Elementary    | 32       | 0.6%    |
| LMDE          | 30       | 0.57%   |
| BigLinux      | 22       | 0.42%   |
| Kali          | 18       | 0.34%   |
| LinuxFX       | 16       | 0.3%    |
| Deepin        | 16       | 0.3%    |
| CentOS        | 16       | 0.3%    |
| BlackPanther  | 16       | 0.3%    |
| Ubuntu Budgie | 15       | 0.28%   |
| Gentoo        | 12       | 0.23%   |
| Clear Linux   | 11       | 0.21%   |
| Nobara        | 10       | 0.19%   |
| EndeavourOS   | 9        | 0.17%   |
| Linux Lite    | 7        | 0.13%   |
| Garuda Linux  | 7        | 0.13%   |
| SteamOS       | 6        | 0.11%   |
| Solus         | 6        | 0.11%   |
| Peppermint    | 6        | 0.11%   |
| Parrot        | 6        | 0.11%   |
| MX            | 6        | 0.11%   |
| Xero          | 5        | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.4.0-42-generic         | 229      | 3.78%   |
| 5.10.14-desktop-1omv4002 | 168      | 2.77%   |
| 5.16.7-desktop-1omv4003  | 131      | 2.16%   |
| 4.15.0-46-generic        | 84       | 1.39%   |
| 6.2.6-desktop-1omv2390   | 65       | 1.07%   |
| 5.4.0-48-generic         | 65       | 1.07%   |
| 4.18.0-15-generic        | 49       | 0.81%   |
| 5.4.0-7634-generic       | 48       | 0.79%   |
| 6.1.1-desktop-1omv2290   | 46       | 0.76%   |
| 5.4.0-58-generic         | 46       | 0.76%   |
| 5.4.0-52-generic         | 43       | 0.71%   |
| 5.3.0-40-generic         | 43       | 0.71%   |
| 5.4.0-40-generic         | 41       | 0.68%   |
| 6.4.11-desktop-1omv2390  | 40       | 0.66%   |
| 5.4.0-47-generic         | 40       | 0.66%   |
| 5.11.0-7620-generic      | 37       | 0.61%   |
| 5.3.0-28-generic         | 36       | 0.59%   |
| 5.15.0-56-generic        | 36       | 0.59%   |
| 5.4.0-26-generic         | 35       | 0.58%   |
| 4.15.0-20-generic        | 33       | 0.54%   |
| 5.4.0-70-generic         | 32       | 0.53%   |
| 6.2.6-76060206-generic   | 31       | 0.51%   |
| 5.4.0-72-generic         | 31       | 0.51%   |
| 5.4.0-91-generic         | 30       | 0.5%    |
| 5.0.0-32-generic         | 30       | 0.5%    |
| 5.3.0-46-generic         | 28       | 0.46%   |
| 5.0.0-37-generic         | 28       | 0.46%   |
| 5.8.0-7630-generic       | 27       | 0.45%   |
| 5.4.0-33-generic         | 27       | 0.45%   |
| 4.15.0-54-generic        | 27       | 0.45%   |
| 5.15.0-46-generic        | 26       | 0.43%   |
| 5.15.0-52-generic        | 25       | 0.41%   |
| 5.15.0-78-generic        | 24       | 0.4%    |
| 5.11.0-37-generic        | 24       | 0.4%    |
| 5.8.0-59-generic         | 23       | 0.38%   |
| 5.8.0-14-generic         | 23       | 0.38%   |
| 5.4.0-74-generic         | 23       | 0.38%   |
| 5.4.0-66-generic         | 23       | 0.38%   |
| 5.4.0-54-generic         | 23       | 0.38%   |
| 5.4.0-37-generic         | 23       | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 1137     | 19.88%  |
| 4.15.0  | 423      | 7.4%    |
| 5.15.0  | 399      | 6.98%   |
| 5.8.0   | 258      | 4.51%   |
| 5.11.0  | 252      | 4.41%   |
| 5.3.0   | 244      | 4.27%   |
| 5.0.0   | 234      | 4.09%   |
| 5.13.0  | 174      | 3.04%   |
| 4.18.0  | 174      | 3.04%   |
| 5.10.14 | 168      | 2.94%   |
| 5.19.0  | 144      | 2.52%   |
| 5.16.7  | 131      | 2.29%   |
| 6.2.6   | 100      | 1.75%   |
| 5.10.0  | 97       | 1.7%    |
| 4.19.0  | 74       | 1.29%   |
| 6.2.0   | 71       | 1.24%   |
| 6.4.11  | 49       | 0.86%   |
| 6.1.1   | 49       | 0.86%   |
| 6.1.0   | 33       | 0.58%   |
| 5.7.9   | 21       | 0.37%   |
| 5.17.5  | 21       | 0.37%   |
| 4.4.0   | 20       | 0.35%   |
| 6.4.8   | 18       | 0.31%   |
| 4.9.0   | 18       | 0.31%   |
| 6.2.9   | 17       | 0.3%    |
| 4.9.60  | 15       | 0.26%   |
| 6.5.5   | 14       | 0.24%   |
| 6.0.12  | 14       | 0.24%   |
| 5.18.12 | 14       | 0.24%   |
| 5.16.13 | 14       | 0.24%   |
| 5.13.19 | 14       | 0.24%   |
| 5.7.0   | 13       | 0.23%   |
| 5.14.0  | 13       | 0.23%   |
| 6.0.7   | 12       | 0.21%   |
| 6.0.10  | 12       | 0.21%   |
| 5.17.15 | 12       | 0.21%   |
| 5.15.5  | 12       | 0.21%   |
| 4.18.16 | 12       | 0.21%   |
| 6.4.6   | 11       | 0.19%   |
| 5.16.11 | 11       | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version  | Desktops | Percent |
|----------|----------|---------|
| 5.4      | 1184     | 21%     |
| 5.15     | 489      | 8.67%   |
| 4.15     | 423      | 7.5%    |
| 5.10     | 347      | 6.15%   |
| 5.8      | 300      | 5.32%   |
| 5.11     | 280      | 4.97%   |
| 5.3      | 264      | 4.68%   |
| 5.0      | 248      | 4.4%    |
| 6.2      | 230      | 4.08%   |
| 5.13     | 207      | 3.67%   |
| 5.19     | 195      | 3.46%   |
| 4.18     | 190      | 3.37%   |
| 5.16     | 189      | 3.35%   |
| 6.1      | 169      | 3%      |
| 6.4      | 123      | 2.18%   |
| 4.19     | 90       | 1.6%    |
| 6.0      | 79       | 1.4%    |
| 5.7      | 70       | 1.24%   |
| 5.18     | 58       | 1.03%   |
| 4.9      | 56       | 0.99%   |
| 6.5      | 55       | 0.98%   |
| 5.17     | 53       | 0.94%   |
| 5.6      | 52       | 0.92%   |
| 6.3      | 50       | 0.89%   |
| 5.14     | 50       | 0.89%   |
| 5.12     | 49       | 0.87%   |
| 5.9      | 35       | 0.62%   |
| 4.4      | 20       | 0.35%   |
| 5.5      | 16       | 0.28%   |
| 5.2      | 13       | 0.23%   |
| 5.1      | 11       | 0.2%    |
| 3.10     | 9        | 0.16%   |
| 4.1      | 8        | 0.14%   |
| 4.13     | 6        | 0.11%   |
| 4.20     | 5        | 0.09%   |
| 4.12     | 5        | 0.09%   |
| 4.10     | 5        | 0.09%   |
| 4.8      | 2        | 0.04%   |
| 6.6      | 1        | 0.02%   |
| 5.15.107 | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 4944     | 97.51%  |
| i686   | 126      | 2.49%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| GNOME                    | 2115     | 39.76%  |
| KDE5                     | 889      | 16.71%  |
| Unknown                  | 788      | 14.81%  |
| X-Cinnamon               | 472      | 8.87%   |
| XFCE                     | 382      | 7.18%   |
| MATE                     | 176      | 3.31%   |
| KDE                      | 141      | 2.65%   |
| Cinnamon                 | 91       | 1.71%   |
| LXQt                     | 44       | 0.83%   |
| KDE4                     | 38       | 0.71%   |
| Unity                    | 34       | 0.64%   |
| Pantheon                 | 28       | 0.53%   |
| Budgie                   | 24       | 0.45%   |
| Deepin                   | 20       | 0.38%   |
| LXDE                     | 17       | 0.32%   |
| i3                       | 13       | 0.24%   |
| GNOME Flashback          | 13       | 0.24%   |
| GNOME Classic            | 5        | 0.09%   |
| awesome                  | 5        | 0.09%   |
| sway                     | 4        | 0.08%   |
| Openbox                  | 4        | 0.08%   |
| Enlightenment            | 4        | 0.08%   |
| bspwm                    | 3        | 0.06%   |
| qtile                    | 2        | 0.04%   |
| icewm                    | 2        | 0.04%   |
| Hyprland                 | 2        | 0.04%   |
| DDE                      | 1        | 0.02%   |
| 03WindowMaker            | 1        | 0.02%   |
| /usr/bin/openbox-session | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 4116     | 79.15%  |
| Wayland | 674      | 12.96%  |
| Unknown | 368      | 7.08%   |
| Tty     | 40       | 0.77%   |
| Web     | 2        | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3046     | 58.17%  |
| SDDM    | 771      | 14.72%  |
| GDM     | 462      | 8.82%   |
| GDM3    | 380      | 7.26%   |
| LightDM | 289      | 5.52%   |
| TDM     | 236      | 4.51%   |
| KDM     | 39       | 0.74%   |
| XDM     | 5        | 0.1%    |
| SLiM    | 3        | 0.06%   |
| SLIMSKI | 2        | 0.04%   |
| LXDM    | 2        | 0.04%   |
| MDM     | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| pt_BR       | 3405     | 65.57%  |
| en_US       | 903      | 17.39%  |
| Unknown     | 751      | 14.46%  |
| C           | 73       | 1.41%   |
| pt_PT       | 22       | 0.42%   |
| en_GB       | 17       | 0.33%   |
| es_ES       | 6        | 0.12%   |
| en_CA       | 6        | 0.12%   |
| en_AG       | 2        | 0.04%   |
| C.UTF8      | 2        | 0.04%   |
| pt_BRutf8   | 1        | 0.02%   |
| eo          | 1        | 0.02%   |
| en_US.utf-8 | 1        | 0.02%   |
| en_IN       | 1        | 0.02%   |
| en_IE.UTF8  | 1        | 0.02%   |
| de_DE       | 1        | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 3498     | 67.45%  |
| EFI  | 1688     | 32.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 3767     | 72.04%  |
| Overlay | 517      | 9.89%   |
| Btrfs   | 448      | 8.57%   |
| Unknown | 304      | 5.81%   |
| Tmpfs   | 97       | 1.86%   |
| Xfs     | 46       | 0.88%   |
| Zfs     | 21       | 0.4%    |
| Ext3    | 9        | 0.17%   |
| F2fs    | 8        | 0.15%   |
| Ext2    | 8        | 0.15%   |
| Aufs    | 2        | 0.04%   |
| XXXXXXX | 1        | 0.02%   |
| Jfs     | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 3174     | 60.89%  |
| GPT     | 1278     | 24.52%  |
| MBR     | 761      | 14.6%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 4361     | 83.91%  |
| Yes       | 836      | 16.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 3510     | 67.71%  |
| Yes       | 1674     | 32.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 1296     | 25.58%  |
| Gigabyte Technology | 863      | 17.04%  |
| Intel               | 441      | 8.71%   |
| ASRock              | 439      | 8.67%   |
| Dell                | 291      | 5.74%   |
| MSI                 | 220      | 4.34%   |
| Positivo            | 210      | 4.15%   |
| Unknown             | 165      | 3.26%   |
| Hewlett-Packard     | 158      | 3.12%   |
| PCWare              | 122      | 2.41%   |
| Biostar             | 106      | 2.09%   |
| Lenovo              | 93       | 1.84%   |
| Pegatron            | 73       | 1.44%   |
| ECS                 | 67       | 1.32%   |
| Semp Toshiba        | 49       | 0.97%   |
| Itautec             | 47       | 0.93%   |
| Huanan              | 43       | 0.85%   |
| Megaware            | 32       | 0.63%   |
| Foxconn             | 32       | 0.63%   |
| OEM                 | 24       | 0.47%   |
| MACHINIST           | 20       | 0.39%   |
| AMD                 | 17       | 0.34%   |
| Login Informatica   | 16       | 0.32%   |
| Qbex                | 12       | 0.24%   |
| Digiboard           | 11       | 0.22%   |
| VS Company          | 10       | 0.2%    |
| PCChips             | 10       | 0.2%    |
| Supermicro          | 9        | 0.18%   |
| Philco              | 9        | 0.18%   |
| Digitron            | 9        | 0.18%   |
| Daten Tecnologia    | 9        | 0.18%   |
| Colorful Technology | 7        | 0.14%   |
| AZW                 | 7        | 0.14%   |
| Phitronics          | 6        | 0.12%   |
| INTELBRAS           | 6        | 0.12%   |
| HOUTER              | 6        | 0.12%   |
| CCE                 | 6        | 0.12%   |
| QIYIDA              | 5        | 0.1%    |
| MEGA                | 5        | 0.1%    |
| Kllisre             | 5        | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Unknown                       | 183      | 3.61%   |
| ASUS All Series               | 153      | 3.02%   |
| Intel H61                     | 101      | 1.99%   |
| ASUS PRIME B450M-GAMING/BR    | 65       | 1.28%   |
| ASRock A320M-HD               | 59       | 1.16%   |
| Intel H55                     | 55       | 1.09%   |
| ASUS PRIME A320M-K/BR         | 54       | 1.07%   |
| ASUS M5A78L-M LX/BR           | 53       | 1.05%   |
| Semp Toshiba STI              | 48       | 0.95%   |
| Gigabyte A320M-S2H            | 41       | 0.81%   |
| Gigabyte H61M-S1              | 40       | 0.79%   |
| ASRock B450M Steel Legend     | 37       | 0.73%   |
| ASUS P8H61-M LX3 R2.0         | 36       | 0.71%   |
| Gigabyte B75M-D3H             | 35       | 0.69%   |
| Intel B75                     | 34       | 0.67%   |
| ASUS M5A78L-M PLUS/USB3       | 33       | 0.65%   |
| ASUS TUF Gaming X570-PLUS_BR  | 30       | 0.59%   |
| ASRock N68-S3 FX              | 30       | 0.59%   |
| ASUS H61M-A/BR                | 27       | 0.53%   |
| Gigabyte AB350M-DS3H V2       | 26       | 0.51%   |
| ASUS M5A78L-M/USB3            | 26       | 0.51%   |
| HP Compaq 6005 Pro SFF PC     | 23       | 0.45%   |
| Gigabyte B450M DS3H           | 23       | 0.45%   |
| ASUS P8H61-M LX2 R2.0         | 23       | 0.45%   |
| ASUS P5G41T-M LX2/BR          | 23       | 0.45%   |
| Positivo POS-EIH61CE          | 20       | 0.39%   |
| Intel MAHOBAY                 | 20       | 0.39%   |
| Gigabyte 970A-DS3P            | 20       | 0.39%   |
| Biostar A320MH                | 20       | 0.39%   |
| ASUS TUF Gaming B550M-PLUS    | 20       | 0.39%   |
| Gigabyte G31M-ES2C            | 19       | 0.38%   |
| ASUS TUF B360M-PLUS GAMING/BR | 19       | 0.38%   |
| ASUS M4N68T-M LE              | 19       | 0.38%   |
| Gigabyte GA-78LMT-USB3 6.0    | 18       | 0.36%   |
| Gigabyte B450 AORUS M         | 18       | 0.36%   |
| Gigabyte 945GCM-S2C           | 18       | 0.36%   |
| Dell XPS 8700                 | 18       | 0.36%   |
| Intel H81                     | 17       | 0.34%   |
| ASUS PRIME H310M-E R2.0/BR    | 17       | 0.34%   |
| ASUS P8H61-M LE/BR            | 17       | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS PRIME             | 255      | 5.03%   |
| Unknown                | 183      | 3.61%   |
| Dell OptiPlex          | 171      | 3.38%   |
| ASUS All               | 153      | 3.02%   |
| ASUS TUF               | 132      | 2.61%   |
| ASUS M5A78L-M          | 132      | 2.61%   |
| Intel H61              | 106      | 2.09%   |
| ASUS P8H61-M           | 92       | 1.82%   |
| HP Compaq              | 78       | 1.54%   |
| Lenovo ThinkCentre     | 66       | 1.3%    |
| ASRock A320M-HD        | 62       | 1.22%   |
| ASUS ROG               | 56       | 1.11%   |
| Intel H55              | 55       | 1.09%   |
| Semp Toshiba STI       | 49       | 0.97%   |
| Gigabyte A320M-S2H     | 41       | 0.81%   |
| Itautec Infoway        | 40       | 0.79%   |
| Gigabyte H61M-S1       | 40       | 0.79%   |
| Gigabyte B450M         | 40       | 0.79%   |
| ASRock B450M           | 39       | 0.77%   |
| Intel B75              | 37       | 0.73%   |
| Gigabyte B75M-D3H      | 35       | 0.69%   |
| Gigabyte GA-78LMT-USB3 | 33       | 0.65%   |
| Dell XPS               | 31       | 0.61%   |
| Dell Inspiron          | 31       | 0.61%   |
| ASRock N68-S3          | 31       | 0.61%   |
| HP EliteDesk           | 29       | 0.57%   |
| Gigabyte B450          | 28       | 0.55%   |
| Dell Precision         | 28       | 0.55%   |
| ASUS H61M-A            | 27       | 0.53%   |
| Gigabyte AB350M-DS3H   | 26       | 0.51%   |
| ASUS P5G41T-M          | 26       | 0.51%   |
| Intel X99              | 25       | 0.49%   |
| Dell Vostro            | 25       | 0.49%   |
| Gigabyte 970A-DS3P     | 22       | 0.43%   |
| Biostar A320MH         | 22       | 0.43%   |
| ASUS M5A97             | 21       | 0.41%   |
| Positivo POS-EIH61CE   | 20       | 0.39%   |
| Intel MAHOBAY          | 20       | 0.39%   |
| Gigabyte H110M-H       | 20       | 0.39%   |
| Gigabyte H310M         | 19       | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 566      | 11.17%  |
| 2012    | 509      | 10.05%  |
| 2011    | 496      | 9.79%   |
| 2017    | 433      | 8.55%   |
| 2013    | 372      | 7.34%   |
| 2014    | 363      | 7.17%   |
| 2010    | 343      | 6.77%   |
| 2019    | 335      | 6.61%   |
| 2009    | 312      | 6.16%   |
| 2020    | 247      | 4.88%   |
| 2008    | 246      | 4.86%   |
| 2016    | 221      | 4.36%   |
| 2007    | 197      | 3.89%   |
| 2021    | 134      | 2.65%   |
| 2015    | 107      | 2.11%   |
| 2022    | 78       | 1.54%   |
| 2006    | 62       | 1.22%   |
| 2005    | 17       | 0.34%   |
| 2023    | 15       | 0.3%    |
| Unknown | 7        | 0.14%   |
| 2004    | 5        | 0.1%    |
| 2003    | 1        | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 5066     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 4974     | 97.89%  |
| Enabled  | 107      | 2.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 5066     | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 1199     | 23.07%  |
| 3.01-4.0        | 1163     | 22.38%  |
| 16.01-24.0      | 1052     | 20.24%  |
| 4.01-8.0        | 941      | 18.11%  |
| 32.01-64.0      | 300      | 5.77%   |
| 1.01-2.0        | 264      | 5.08%   |
| 2.01-3.0        | 95       | 1.83%   |
| 24.01-32.0      | 86       | 1.65%   |
| 64.01-256.0     | 72       | 1.39%   |
| 0.51-1.0        | 20       | 0.38%   |
| More than 256.0 | 2        | 0.04%   |
| Unknown         | 2        | 0.04%   |
| 0.01-0.5        | 1        | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 2076     | 36.83%  |
| 2.01-3.0   | 1458     | 25.87%  |
| 4.01-8.0   | 718      | 12.74%  |
| 3.01-4.0   | 671      | 11.91%  |
| 0.51-1.0   | 462      | 8.2%    |
| 8.01-16.0  | 146      | 2.59%   |
| 0.01-0.5   | 72       | 1.28%   |
| 16.01-24.0 | 23       | 0.41%   |
| 24.01-32.0 | 7        | 0.12%   |
| Unknown    | 2        | 0.04%   |
| 32.01-64.0 | 1        | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 2562     | 48.47%  |
| 2       | 1497     | 28.32%  |
| 3       | 672      | 12.71%  |
| 4       | 307      | 5.81%   |
| 5       | 99       | 1.87%   |
| 0       | 63       | 1.19%   |
| 6       | 60       | 1.14%   |
| 7       | 12       | 0.23%   |
| 8       | 8        | 0.15%   |
| 9       | 4        | 0.08%   |
| 14      | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3241     | 63.08%  |
| Yes       | 1897     | 36.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 4982     | 98.32%  |
| No        | 85       | 1.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 3305     | 64.17%  |
| Yes       | 1845     | 35.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4205     | 81.95%  |
| Yes       | 926      | 18.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Brazil  | 5066     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Desktops | Percent |
|----------------------|----------|---------|
| Sao Paulo            | 678      | 12.81%  |
| Rio de Janeiro       | 356      | 6.73%   |
| Brasília            | 150      | 2.83%   |
| Belo Horizonte       | 144      | 2.72%   |
| Curitiba             | 126      | 2.38%   |
| Porto Alegre         | 124      | 2.34%   |
| Fortaleza            | 92       | 1.74%   |
| Campinas             | 75       | 1.42%   |
| Salvador             | 69       | 1.3%    |
| Recife               | 64       | 1.21%   |
| Santo André         | 61       | 1.15%   |
| Goiânia             | 58       | 1.1%    |
| Florianópolis       | 58       | 1.1%    |
| Guarulhos            | 49       | 0.93%   |
| Osasco               | 43       | 0.81%   |
| Niterói             | 43       | 0.81%   |
| Manaus               | 41       | 0.77%   |
| Sorocaba             | 37       | 0.7%    |
| Sao José dos Campos | 36       | 0.68%   |
| Londrina             | 35       | 0.66%   |
| Natal                | 33       | 0.62%   |
| Juiz de Fora         | 33       | 0.62%   |
| Duque de Caxias      | 33       | 0.62%   |
| Belém               | 33       | 0.62%   |
| Serra                | 31       | 0.59%   |
| Palmas               | 30       | 0.57%   |
| Maringá             | 30       | 0.57%   |
| Campo Grande         | 30       | 0.57%   |
| Joinville            | 29       | 0.55%   |
| Blumenau             | 27       | 0.51%   |
| Uberlândia          | 24       | 0.45%   |
| Sao Goncalo          | 24       | 0.45%   |
| Ribeirao Preto       | 24       | 0.45%   |
| Joao Pessoa          | 23       | 0.43%   |
| Teresina             | 22       | 0.42%   |
| Sao Jose             | 22       | 0.42%   |
| Maceió              | 22       | 0.42%   |
| Aracaju              | 21       | 0.4%    |
| Sao Luís            | 20       | 0.38%   |
| Sao Carlos           | 20       | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| Seagate                     | 1999     | 3059   | 23.82%  |
| WDC                         | 1529     | 2124   | 18.22%  |
| Samsung Electronics         | 1073     | 1565   | 12.79%  |
| Kingston                    | 951      | 1333   | 11.33%  |
| Sandisk                     | 358      | 510    | 4.27%   |
| Toshiba                     | 353      | 419    | 4.21%   |
| China                       | 266      | 309    | 3.17%   |
| Hitachi                     | 190      | 232    | 2.26%   |
| Crucial                     | 168      | 210    | 2%      |
| Silicon Motion              | 122      | 161    | 1.45%   |
| Maxtor                      | 122      | 144    | 1.45%   |
| A-DATA Technology           | 111      | 136    | 1.32%   |
| KingSpec                    | 71       | 80     | 0.85%   |
| Realtek Semiconductor       | 66       | 84     | 0.79%   |
| Lexar                       | 63       | 69     | 0.75%   |
| Unknown                     | 52       | 79     | 0.62%   |
| XPG                         | 45       | 56     | 0.54%   |
| Netac                       | 38       | 54     | 0.45%   |
| Intel                       | 37       | 42     | 0.44%   |
| HGST                        | 37       | 43     | 0.44%   |
| Corsair                     | 37       | 49     | 0.44%   |
| Patriot                     | 35       | 52     | 0.42%   |
| Phison                      | 33       | 51     | 0.39%   |
| XrayDisk                    | 32       | 46     | 0.38%   |
| PNY                         | 30       | 32     | 0.36%   |
| MAXIO Technology (Hangzhou) | 30       | 39     | 0.36%   |
| JMicron Technology          | 30       | 32     | 0.36%   |
| Hewlett-Packard             | 30       | 37     | 0.36%   |
| Kingston Technology Company | 27       | 37     | 0.32%   |
| Phison Electronics          | 26       | 37     | 0.31%   |
| Unknown                     | 24       | 29     | 0.29%   |
| Gigabyte Technology         | 22       | 30     | 0.26%   |
| ADATA Technology            | 21       | 30     | 0.25%   |
| LITEON                      | 18       | 20     | 0.21%   |
| KingDian                    | 17       | 20     | 0.2%    |
| WALRAM                      | 15       | 15     | 0.18%   |
| Micron/Crucial Technology   | 15       | 23     | 0.18%   |
| HS-SSD-C100                 | 14       | 14     | 0.17%   |
| SK hynix                    | 13       | 39     | 0.15%   |
| OCZ                         | 13       | 14     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD     | 316      | 3.38%   |
| Seagate ST500DM002-1BD142 500GB     | 267      | 2.86%   |
| Seagate ST1000DM010-2EP102 1TB      | 236      | 2.52%   |
| Kingston SA400S37120G 120GB SSD     | 179      | 1.91%   |
| Kingston SA400S37480G 480GB SSD     | 157      | 1.68%   |
| Samsung HD322HJ 320GB               | 132      | 1.41%   |
| Samsung HD502HJ 500GB               | 112      | 1.2%    |
| Samsung HD161HJ 160GB               | 110      | 1.18%   |
| Samsung HD502HI 500GB               | 105      | 1.12%   |
| Seagate ST1000DM003-1ER162 1TB      | 101      | 1.08%   |
| Seagate ST1000DM003-1CH162 1TB      | 98       | 1.05%   |
| Kingston SV300S37A120G 120GB SSD    | 89       | 0.95%   |
| WDC WD5000AAKX-003CA0 500GB         | 81       | 0.87%   |
| Seagate ST3500312CS 500GB           | 73       | 0.78%   |
| SanDisk SSD PLUS 240GB              | 73       | 0.78%   |
| Seagate ST3500418AS 500GB           | 72       | 0.77%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 71       | 0.76%   |
| WDC WD10EARS-00Y5B1 1TB             | 70       | 0.75%   |
| Crucial CT240BX500SSD1 240GB        | 68       | 0.73%   |
| Seagate Expansion 1TB               | 66       | 0.71%   |
| Seagate ST31000524AS 1TB            | 65       | 0.7%    |
| WDC WD10EZEX-00BN5A0 1TB            | 62       | 0.66%   |
| Seagate ST2000DM006-2DM164 2TB      | 61       | 0.65%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 60       | 0.64%   |
| Toshiba DT01ACA050 500GB            | 59       | 0.63%   |
| WDC WD10EZEX-00WN4A0 1TB            | 58       | 0.62%   |
| Toshiba HDWD110 1TB                 | 58       | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 56       | 0.6%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 52       | 0.56%   |
| Samsung HD103SJ 1TB                 | 51       | 0.55%   |
| Seagate ST3320418AS 320GB           | 50       | 0.53%   |
| Seagate ST2000DM008-2FR102 2TB      | 50       | 0.53%   |
| Samsung HD103SI 1TB                 | 50       | 0.53%   |
| Seagate ST3500413AS 500GB           | 47       | 0.5%    |
| SanDisk SDSSDA120G 120GB            | 47       | 0.5%    |
| WDC WD10EZEX-08WN4A0 1TB            | 45       | 0.48%   |
| Seagate ST31000528AS 1TB            | 44       | 0.47%   |
| SanDisk SSD PLUS 120GB              | 44       | 0.47%   |
| Samsung HD161GJ 160GB               | 44       | 0.47%   |
| SanDisk SDSSDA240G 240GB            | 43       | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1994     | 3041   | 39.71%  |
| WDC                 | 1363     | 1857   | 27.15%  |
| Samsung Electronics | 909      | 1243   | 18.1%   |
| Toshiba             | 338      | 400    | 6.73%   |
| Hitachi             | 190      | 232    | 3.78%   |
| Maxtor              | 116      | 136    | 2.31%   |
| HGST                | 37       | 43     | 0.74%   |
| Hewlett-Packard     | 17       | 21     | 0.34%   |
| Fujitsu             | 13       | 16     | 0.26%   |
| ExcelStor           | 11       | 12     | 0.22%   |
| Unknown             | 10       | 10     | 0.2%    |
| HPE                 | 5        | 5      | 0.1%    |
| USB3.0              | 2        | 2      | 0.04%   |
| JMicron Technology  | 2        | 3      | 0.04%   |
| Initio              | 2        | 2      | 0.04%   |
| External            | 2        | 2      | 0.04%   |
| Apple               | 2        | 2      | 0.04%   |
| SAGE                | 1        | 2      | 0.02%   |
| MDT                 | 1        | 1      | 0.02%   |
| Lenovo              | 1        | 1      | 0.02%   |
| IBM                 | 1        | 3      | 0.02%   |
| HGST HTS            | 1        | 1      | 0.02%   |
| FEASSO              | 1        | 2      | 0.02%   |
| China               | 1        | 2      | 0.02%   |
| Unknown             | 1        | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Kingston            | 901      | 1250   | 34.8%   |
| SanDisk             | 313      | 441    | 12.09%  |
| China               | 264      | 306    | 10.2%   |
| WDC                 | 181      | 239    | 6.99%   |
| Crucial             | 163      | 203    | 6.3%    |
| Samsung Electronics | 118      | 222    | 4.56%   |
| A-DATA Technology   | 86       | 101    | 3.32%   |
| KingSpec            | 69       | 78     | 2.67%   |
| Lexar               | 59       | 65     | 2.28%   |
| Patriot             | 33       | 49     | 1.27%   |
| Corsair             | 29       | 38     | 1.12%   |
| PNY                 | 28       | 30     | 1.08%   |
| Intel               | 28       | 31     | 1.08%   |
| Netac               | 23       | 36     | 0.89%   |
| KingDian            | 17       | 20     | 0.66%   |
| Gigabyte Technology | 16       | 23     | 0.62%   |
| Unknown             | 16       | 17     | 0.62%   |
| XrayDisk            | 14       | 18     | 0.54%   |
| LITEON              | 14       | 16     | 0.54%   |
| OCZ                 | 13       | 14     | 0.5%    |
| Toshiba             | 11       | 14     | 0.42%   |
| Smart               | 9        | 11     | 0.35%   |
| Hewlett-Packard     | 9        | 11     | 0.35%   |
| Team                | 8        | 8      | 0.31%   |
| Seagate             | 8        | 9      | 0.31%   |
| HS-SSD-C100         | 7        | 7      | 0.27%   |
| BHT                 | 7        | 12     | 0.27%   |
| Unknown             | 6        | 6      | 0.23%   |
| Maxtor              | 6        | 8      | 0.23%   |
| KODAK               | 6        | 6      | 0.23%   |
| WALRAM              | 5        | 5      | 0.19%   |
| HUSKY               | 5        | 8      | 0.19%   |
| Apacer              | 5        | 5      | 0.19%   |
| SK hynix            | 4        | 5      | 0.15%   |
| RZX                 | 4        | 10     | 0.15%   |
| Pichau              | 4        | 4      | 0.15%   |
| NN                  | 4        | 6      | 0.15%   |
| KINGBANK            | 4        | 7      | 0.15%   |
| Colorful            | 4        | 5      | 0.15%   |
| Plextor             | 3        | 4      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 3984     | 7040   | 56.98%  |
| SSD     | 2227     | 3460   | 31.85%  |
| NVMe    | 677      | 1030   | 9.68%   |
| Unknown | 98       | 139    | 1.4%    |
| MMC     | 6        | 10     | 0.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 4837     | 10373  | 84.76%  |
| NVMe | 656      | 1001   | 11.49%  |
| SAS  | 208      | 295    | 3.64%   |
| MMC  | 6        | 10     | 0.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Desktops | Drives | Percent |
|-----------------|----------|--------|---------|
| 0.01-0.5        | 3993     | 6894   | 62.4%   |
| 0.51-1.0        | 1788     | 2713   | 27.94%  |
| 1.01-2.0        | 401      | 579    | 6.27%   |
| 2.01-3.0        | 90       | 121    | 1.41%   |
| 3.01-4.0        | 83       | 125    | 1.3%    |
| 4.01-10.0       | 37       | 59     | 0.58%   |
| 10.01-20.0      | 6        | 8      | 0.09%   |
| More than 100.0 | 1        | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 1349     | 24.78%  |
| 251-500        | 1238     | 22.74%  |
| 501-1000       | 774      | 14.22%  |
| 1001-2000      | 562      | 10.33%  |
| 1-20           | 456      | 8.38%   |
| 51-100         | 352      | 6.47%   |
| 2001-3000      | 203      | 3.73%   |
| 21-50          | 197      | 3.62%   |
| More than 3000 | 193      | 3.55%   |
| Unknown        | 119      | 2.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 2094     | 37.54%  |
| 21-50          | 987      | 17.69%  |
| 101-250        | 663      | 11.89%  |
| 51-100         | 597      | 10.7%   |
| 251-500        | 408      | 7.31%   |
| 501-1000       | 392      | 7.03%   |
| 1001-2000      | 193      | 3.46%   |
| Unknown        | 119      | 2.13%   |
| 2001-3000      | 65       | 1.17%   |
| More than 3000 | 60       | 1.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 49       | 53     | 5.29%   |
| Samsung Electronics HD322HJ 320GB   | 28       | 39     | 3.02%   |
| WDC WD5000AAKX-003CA0 500GB         | 26       | 27     | 2.8%    |
| Samsung Electronics HD161HJ 160GB   | 24       | 25     | 2.59%   |
| Samsung Electronics HD502HI 500GB   | 21       | 25     | 2.27%   |
| Samsung Electronics HD502HJ 500GB   | 16       | 17     | 1.73%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 13       | 13     | 1.4%    |
| WDC WD10EARS-00Y5B1 1TB             | 12       | 14     | 1.29%   |
| Seagate ST1000DM010-2EP102 1TB      | 12       | 15     | 1.29%   |
| Maxtor STM3160215AS 160GB           | 11       | 13     | 1.19%   |
| WDC WD3200AAJS-00L7A0 320GB         | 10       | 10     | 1.08%   |
| Samsung Electronics HD250HJ 250GB   | 10       | 11     | 1.08%   |
| Samsung Electronics HD103SI 1TB     | 10       | 13     | 1.08%   |
| Samsung Electronics HD080HJ 80GB    | 10       | 12     | 1.08%   |
| Seagate ST3500418AS 500GB           | 9        | 14     | 0.97%   |
| Seagate ST3320418AS 320GB           | 9        | 13     | 0.97%   |
| Seagate ST31000524AS 1TB            | 9        | 9      | 0.97%   |
| Samsung Electronics HD103SJ 1TB     | 9        | 11     | 0.97%   |
| Seagate ST3500413AS 500GB           | 8        | 9      | 0.86%   |
| Seagate ST2000DM001-1CH164 2TB      | 8        | 10     | 0.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 8        | 11     | 0.86%   |
| Seagate ST1000DM003-1ER162 1TB      | 8        | 10     | 0.86%   |
| Seagate ST1000DM003-1CH162 1TB      | 8        | 11     | 0.86%   |
| Toshiba MQ01ABD050 500GB            | 7        | 7      | 0.76%   |
| Seagate ST3500312CS 500GB           | 7        | 7      | 0.76%   |
| Seagate ST1500DL003-9VT16L 1TB      | 7        | 8      | 0.76%   |
| Seagate ST1000DM003-9YN162 1TB      | 7        | 7      | 0.76%   |
| Samsung Electronics HM321HI 320GB   | 7        | 7      | 0.76%   |
| Maxtor STM3250310AS 250GB           | 7        | 7      | 0.76%   |
| Kingston SV300S37A120G 120GB SSD    | 7        | 7      | 0.76%   |
| WDC WD5000AVCS-632DY1 500GB         | 6        | 7      | 0.65%   |
| WDC WD5000AAKX-083CA1 500GB         | 6        | 6      | 0.65%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 6        | 7      | 0.65%   |
| WDC WD10EZEX-08WN4A0 1TB            | 6        | 6      | 0.65%   |
| WDC WD10EZEX-00BN5A0 1TB            | 6        | 6      | 0.65%   |
| Toshiba DT01ACA050 500GB            | 6        | 6      | 0.65%   |
| Seagate ST31000528AS 1TB            | 6        | 9      | 0.65%   |
| Kingston SA400S37120G 120GB SSD     | 6        | 12     | 0.65%   |
| Seagate ST3250318AS 250GB           | 5        | 5      | 0.54%   |
| Seagate ST3160318AS 160GB           | 5        | 5      | 0.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 271      | 340    | 31.15%  |
| WDC                   | 210      | 247    | 24.14%  |
| Samsung Electronics   | 186      | 230    | 21.38%  |
| Toshiba               | 38       | 40     | 4.37%   |
| Hitachi               | 38       | 39     | 4.37%   |
| Kingston              | 27       | 34     | 3.1%    |
| Maxtor                | 24       | 27     | 2.76%   |
| China                 | 19       | 20     | 2.18%   |
| SanDisk               | 7        | 9      | 0.8%    |
| XPG                   | 6        | 6      | 0.69%   |
| Netac                 | 4        | 5      | 0.46%   |
| A-DATA Technology     | 4        | 4      | 0.46%   |
| Intel                 | 3        | 3      | 0.34%   |
| Crucial               | 3        | 3      | 0.34%   |
| Unknown               | 3        | 3      | 0.34%   |
| OCZ                   | 2        | 2      | 0.23%   |
| JMicron Technology    | 2        | 2      | 0.23%   |
| Hewlett-Packard       | 2        | 2      | 0.23%   |
| ExcelStor             | 2        | 3      | 0.23%   |
| XrayDisk              | 1        | 3      | 0.11%   |
| Team                  | 1        | 1      | 0.11%   |
| Reeinno               | 1        | 1      | 0.11%   |
| Realtek Semiconductor | 1        | 2      | 0.11%   |
| PNY                   | 1        | 1      | 0.11%   |
| Plextor               | 1        | 1      | 0.11%   |
| OCZ-VERTEX3           | 1        | 1      | 0.11%   |
| Mushkin               | 1        | 1      | 0.11%   |
| LITEON                | 1        | 1      | 0.11%   |
| KingSpec              | 1        | 1      | 0.11%   |
| KEEPDATA              | 1        | 1      | 0.11%   |
| Initio                | 1        | 1      | 0.11%   |
| HGST                  | 1        | 1      | 0.11%   |
| Fujitsu               | 1        | 1      | 0.11%   |
| FEASSO                | 1        | 2      | 0.11%   |
| Fanxiang              | 1        | 1      | 0.11%   |
| EXRAM                 | 1        | 1      | 0.11%   |
| EGON                  | 1        | 1      | 0.11%   |
| Corsair               | 1        | 1      | 0.11%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 271      | 340    | 35.42%  |
| WDC                 | 201      | 235    | 26.27%  |
| Samsung Electronics | 185      | 229    | 24.18%  |
| Toshiba             | 38       | 40     | 4.97%   |
| Hitachi             | 38       | 39     | 4.97%   |
| Maxtor              | 24       | 27     | 3.14%   |
| Hewlett-Packard     | 2        | 2      | 0.26%   |
| ExcelStor           | 2        | 3      | 0.26%   |
| Initio              | 1        | 1      | 0.13%   |
| HGST                | 1        | 1      | 0.13%   |
| Fujitsu             | 1        | 1      | 0.13%   |
| FEASSO              | 1        | 2      | 0.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 667      | 920    | 86.4%   |
| SSD  | 90       | 106    | 11.66%  |
| NVMe | 15       | 16     | 1.94%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 4        | 4      | 18.18%  |
| Samsung Electronics HD502HJ 500GB | 3        | 7      | 13.64%  |
| WDC WD5000AAKS-00C8A0 500GB       | 1        | 1      | 4.55%   |
| WDC WD3200BPVT-22JJ5T0 320GB      | 1        | 1      | 4.55%   |
| WDC WD3200BPVT-00JJ5T0 320GB      | 1        | 1      | 4.55%   |
| WDC WD1600BEVT-22ZCT0 160GB       | 1        | 1      | 4.55%   |
| Toshiba DT01ACA100 1TB            | 1        | 1      | 4.55%   |
| Seagate ST3320613AS 320GB         | 1        | 1      | 4.55%   |
| Seagate ST3250318AS 250GB         | 1        | 1      | 4.55%   |
| Seagate ST31000528AS 1TB          | 1        | 1      | 4.55%   |
| Seagate ST31000340NS 1TB          | 1        | 1      | 4.55%   |
| Samsung Electronics HM641JI 640GB | 1        | 1      | 4.55%   |
| Samsung Electronics HM250HI 250GB | 1        | 1      | 4.55%   |
| Samsung Electronics HD322GJ 320GB | 1        | 1      | 4.55%   |
| Samsung Electronics HD103SJ 1TB   | 1        | 1      | 4.55%   |
| Samsung Electronics HD080HJ 80GB  | 1        | 1      | 4.55%   |
| Hitachi HDS721050DLE630 500GB     | 1        | 1      | 4.55%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 8        | 8      | 36.36%  |
| Samsung Electronics | 8        | 12     | 36.36%  |
| WDC                 | 4        | 4      | 18.18%  |
| Toshiba             | 1        | 1      | 4.55%   |
| Hitachi             | 1        | 1      | 4.55%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 3395     | 7818   | 60.52%  |
| Works    | 1460     | 2793   | 26.02%  |
| Malfunc  | 733      | 1042   | 13.07%  |
| Failed   | 22       | 26     | 0.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 3313     | 54.77%  |
| AMD                              | 1453     | 24.02%  |
| Nvidia                           | 225      | 3.72%   |
| Silicon Motion                   | 140      | 2.31%   |
| Realtek Semiconductor            | 89       | 1.47%   |
| Marvell Technology Group         | 87       | 1.44%   |
| Kingston Technology Company      | 87       | 1.44%   |
| JMicron Technology               | 87       | 1.44%   |
| ASMedia Technology               | 81       | 1.34%   |
| SanDisk                          | 78       | 1.29%   |
| Phison Electronics               | 75       | 1.24%   |
| Samsung Electronics              | 72       | 1.19%   |
| ADATA Technology                 | 63       | 1.04%   |
| VIA Technologies                 | 50       | 0.83%   |
| MAXIO Technology (Hangzhou)      | 33       | 0.55%   |
| Micron/Crucial Technology        | 22       | 0.36%   |
| Netac Technology                 | 9        | 0.15%   |
| LSI Logic / Symbios Logic        | 9        | 0.15%   |
| Broadcom / LSI                   | 9        | 0.15%   |
| Solid State Storage Technology   | 8        | 0.13%   |
| SK hynix                         | 8        | 0.13%   |
| Silicon Integrated Systems [SiS] | 8        | 0.13%   |
| Lite-On Technology               | 6        | 0.1%    |
| Silicon Image                    | 5        | 0.08%   |
| Beijing Starblaze Technology     | 5        | 0.08%   |
| Shenzhen Longsys Electronics     | 4        | 0.07%   |
| Seagate Technology               | 4        | 0.07%   |
| OCZ Technology Group             | 4        | 0.07%   |
| INNOGRIT                         | 3        | 0.05%   |
| Adaptec                          | 3        | 0.05%   |
| ULi Electronics                  | 1        | 0.02%   |
| TenaFe                           | 1        | 0.02%   |
| Promise Technology               | 1        | 0.02%   |
| Micron Technology                | 1        | 0.02%   |
| Lenovo                           | 1        | 0.02%   |
| KIOXIA                           | 1        | 0.02%   |
| Hosin Global Electronics         | 1        | 0.02%   |
| Broadcom                         | 1        | 0.02%   |
| Biwin Storage Technology         | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 779      | 9.23%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 611      | 7.24%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 466      | 5.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 450      | 5.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 360      | 4.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 330      | 3.91%   |
| AMD FCH SATA Controller D                                                               | 262      | 3.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 261      | 3.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 261      | 3.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 258      | 3.06%   |
| AMD 400 Series Chipset SATA Controller                                                  | 252      | 2.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 191      | 2.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 187      | 2.21%   |
| Nvidia MCP61 SATA Controller                                                            | 186      | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 186      | 2.2%    |
| Nvidia MCP61 IDE                                                                        | 152      | 1.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 130      | 1.54%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 130      | 1.54%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 121      | 1.43%   |
| AMD 500 Series Chipset SATA Controller                                                  | 110      | 1.3%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 101      | 1.2%    |
| Intel SATA Controller [RAID mode]                                                       | 100      | 1.18%   |
| AMD 300 Series Chipset SATA Controller                                                  | 93       | 1.1%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 92       | 1.09%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 76       | 0.9%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 76       | 0.9%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 64       | 0.76%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 64       | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 61       | 0.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 55       | 0.65%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 54       | 0.64%   |
| Realtek RTS5762 NVMe SSD Controller                                                     | 51       | 0.6%    |
| AMD FCH IDE Controller                                                                  | 50       | 0.59%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 47       | 0.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 44       | 0.52%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 43       | 0.51%   |
| JMicron JMB368 IDE controller                                                           | 42       | 0.5%    |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 40       | 0.47%   |
| Phison E12 NVMe Controller                                                              | 40       | 0.47%   |
| Intel 5 Series/3400 Series Chipset PT IDER Controller                                   | 39       | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 3512     | 56.02%  |
| IDE  | 1920     | 30.63%  |
| NVMe | 662      | 10.56%  |
| RAID | 157      | 2.5%    |
| SCSI | 10       | 0.16%   |
| SAS  | 8        | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Desktops | Percent |
|--------------|----------|---------|
| Intel        | 3389     | 66.9%   |
| AMD          | 1671     | 32.98%  |
| CentaurHauls | 5        | 0.1%    |
| Unknown      | 1        | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD FX-6300 Six-Core Processor              | 102      | 2%      |
| Intel Core i5-3470 CPU @ 3.20GHz            | 94       | 1.84%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 87       | 1.71%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 84       | 1.65%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 72       | 1.41%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 69       | 1.35%   |
| AMD Ryzen 5 3600 6-Core Processor           | 67       | 1.31%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 63       | 1.24%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 61       | 1.2%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 60       | 1.18%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 60       | 1.18%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 60       | 1.18%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 59       | 1.16%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 58       | 1.14%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 57       | 1.12%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 56       | 1.1%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 55       | 1.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 53       | 1.04%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 47       | 0.92%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 44       | 0.86%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 43       | 0.84%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 42       | 0.82%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 41       | 0.8%    |
| Intel Core i5-9400F CPU @ 2.90GHz           | 39       | 0.76%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 39       | 0.76%   |
| AMD FX-8300 Eight-Core Processor            | 36       | 0.71%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 35       | 0.69%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 33       | 0.65%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 33       | 0.65%   |
| Intel Core 2 Duo CPU E7400 @ 2.80GHz        | 33       | 0.65%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 32       | 0.63%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 32       | 0.63%   |
| AMD FX-4300 Quad-Core Processor             | 31       | 0.61%   |
| AMD Athlon II X2 250 Processor              | 31       | 0.61%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 29       | 0.57%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 29       | 0.57%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 29       | 0.57%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 29       | 0.57%   |
| AMD FX-8350 Eight-Core Processor            | 29       | 0.57%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 28       | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 877      | 17.21%  |
| Intel Core i3           | 580      | 11.38%  |
| Intel Core i7           | 459      | 9.01%   |
| AMD Ryzen 5             | 427      | 8.38%   |
| AMD FX                  | 284      | 5.57%   |
| Intel Core 2 Duo        | 259      | 5.08%   |
| Intel Celeron           | 254      | 4.99%   |
| Intel Xeon              | 249      | 4.89%   |
| Intel Pentium Dual-Core | 191      | 3.75%   |
| AMD Ryzen 7             | 182      | 3.57%   |
| Intel Pentium           | 145      | 2.85%   |
| AMD Ryzen 3             | 111      | 2.18%   |
| Intel Core 2 Quad       | 107      | 2.1%    |
| AMD Phenom II X4        | 86       | 1.69%   |
| Intel Pentium Dual      | 77       | 1.51%   |
| AMD Athlon II X2        | 77       | 1.51%   |
| AMD Athlon              | 52       | 1.02%   |
| Other                   | 51       | 1%      |
| AMD Athlon 64 X2        | 46       | 0.9%    |
| AMD A8                  | 46       | 0.9%    |
| AMD Ryzen 9             | 42       | 0.82%   |
| AMD A10                 | 40       | 0.79%   |
| AMD A4                  | 39       | 0.77%   |
| Intel Core 2            | 35       | 0.69%   |
| Intel Atom              | 35       | 0.69%   |
| AMD Phenom II X6        | 33       | 0.65%   |
| AMD Sempron             | 31       | 0.61%   |
| AMD A6                  | 29       | 0.57%   |
| Intel Pentium 4         | 28       | 0.55%   |
| Intel Pentium Gold      | 22       | 0.43%   |
| AMD Phenom II X2        | 21       | 0.41%   |
| Intel Core i9           | 20       | 0.39%   |
| AMD Athlon II X4        | 18       | 0.35%   |
| Intel Genuine           | 14       | 0.27%   |
| AMD Phenom              | 14       | 0.27%   |
| Intel Pentium D         | 13       | 0.26%   |
| AMD Athlon II X3        | 13       | 0.26%   |
| AMD E                   | 10       | 0.2%    |
| AMD Ryzen 5 PRO         | 9        | 0.18%   |
| AMD Ryzen 3 PRO         | 8        | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1887     | 37.05%  |
| 4       | 1814     | 35.62%  |
| 6       | 626      | 12.29%  |
| 8       | 275      | 5.4%    |
| 1       | 201      | 3.95%   |
| 3       | 148      | 2.91%   |
| 12      | 61       | 1.2%    |
| 10      | 28       | 0.55%   |
| 16      | 22       | 0.43%   |
| Unknown | 11       | 0.22%   |
| 14      | 9        | 0.18%   |
| 24      | 5        | 0.1%    |
| 28      | 2        | 0.04%   |
| 18      | 2        | 0.04%   |
| 22      | 1        | 0.02%   |
| 20      | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 5040     | 99.47%  |
| 2       | 25       | 0.49%   |
| 16      | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 2552     | 50.27%  |
| 1       | 2513     | 49.5%   |
| Unknown | 11       | 0.22%   |
| 4       | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 4821     | 94.64%  |
| Unknown        | 229      | 4.5%    |
| 64-bit         | 29       | 0.57%   |
| 32-bit         | 15       | 0.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1242     | 23.56%  |
| 0x306a9    | 414      | 7.85%   |
| 0x206a7    | 400      | 7.59%   |
| 0x1067a    | 392      | 7.44%   |
| 0x306c3    | 321      | 6.09%   |
| 0x06000852 | 159      | 3.02%   |
| 0x906e9    | 131      | 2.48%   |
| 0x906ea    | 123      | 2.33%   |
| 0x010000c8 | 121      | 2.3%    |
| 0x6fd      | 102      | 1.93%   |
| 0x08108109 | 93       | 1.76%   |
| 0x0800820d | 89       | 1.69%   |
| 0x08701021 | 79       | 1.5%    |
| 0x20655    | 78       | 1.48%   |
| 0x306f2    | 59       | 1.12%   |
| 0x08701013 | 54       | 1.02%   |
| 0x6fb      | 52       | 0.99%   |
| 0x506e3    | 52       | 0.99%   |
| 0x20652    | 48       | 0.91%   |
| 0x06001119 | 47       | 0.89%   |
| 0x10676    | 44       | 0.83%   |
| 0x08101016 | 44       | 0.83%   |
| 0x08001138 | 39       | 0.74%   |
| 0xa0653    | 38       | 0.72%   |
| 0x106e5    | 38       | 0.72%   |
| 0x30678    | 35       | 0.66%   |
| 0x010000db | 34       | 0.64%   |
| 0x0600611a | 33       | 0.63%   |
| 0x06003106 | 33       | 0.63%   |
| 0x010000dc | 31       | 0.59%   |
| 0x906eb    | 30       | 0.57%   |
| 0x906ed    | 29       | 0.55%   |
| 0x306e4    | 29       | 0.55%   |
| 0x0a50000d | 28       | 0.53%   |
| 0x0810100b | 28       | 0.53%   |
| 0x0600063e | 27       | 0.51%   |
| 0x10661    | 25       | 0.47%   |
| 0x08001137 | 22       | 0.42%   |
| 0x206d7    | 21       | 0.4%    |
| 0x6f2      | 20       | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| IvyBridge        | 565      | 11.13%  |
| Penryn           | 515      | 10.15%  |
| SandyBridge      | 509      | 10.03%  |
| Haswell          | 486      | 9.57%   |
| KabyLake         | 424      | 8.35%   |
| Piledriver       | 296      | 5.83%   |
| K10              | 294      | 5.79%   |
| Zen+             | 257      | 5.06%   |
| Core             | 249      | 4.91%   |
| Zen              | 214      | 4.22%   |
| Zen 2            | 201      | 3.96%   |
| Westmere         | 166      | 3.27%   |
| Zen 3            | 134      | 2.64%   |
| CometLake        | 93       | 1.83%   |
| Skylake          | 84       | 1.65%   |
| Silvermont       | 78       | 1.54%   |
| K8 Hammer        | 68       | 1.34%   |
| Nehalem          | 62       | 1.22%   |
| NetBurst         | 50       | 0.99%   |
| Bulldozer        | 47       | 0.93%   |
| Excavator        | 46       | 0.91%   |
| Steamroller      | 44       | 0.87%   |
| Unknown          | 39       | 0.77%   |
| Bonnell          | 30       | 0.59%   |
| Bobcat           | 23       | 0.45%   |
| Broadwell        | 22       | 0.43%   |
| Jaguar           | 19       | 0.37%   |
| Alderlake Hybrid | 16       | 0.32%   |
| K10 Llano        | 15       | 0.3%    |
| Icelake          | 12       | 0.24%   |
| Goldmont plus    | 10       | 0.2%    |
| Tremont          | 4        | 0.08%   |
| Goldmont         | 2        | 0.04%   |
| Puma             | 1        | 0.02%   |
| K6               | 1        | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 1916     | 35.93%  |
| Nvidia                           | 1805     | 33.85%  |
| AMD                              | 1555     | 29.16%  |
| VIA Technologies                 | 32       | 0.6%    |
| Matrox Electronics Systems       | 8        | 0.15%   |
| Silicon Integrated Systems [SiS] | 5        | 0.09%   |
| Silicon Motion                   | 4        | 0.08%   |
| ATI Technologies                 | 4        | 0.08%   |
| S3 Graphics                      | 1        | 0.02%   |
| Red Hat                          | 1        | 0.02%   |
| ASPEED Technology                | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 307      | 5.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 268      | 4.92%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 210      | 3.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 189      | 3.47%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 177      | 3.25%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 175      | 3.21%   |
| Nvidia GT218 [GeForce 210]                                                  | 154      | 2.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 114      | 2.09%   |
| Intel Core Processor Integrated Graphics Controller                         | 111      | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 109      | 2%      |
| Intel 82945G/GZ Integrated Graphics Controller                              | 99       | 1.82%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 94       | 1.73%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 92       | 1.69%   |
| AMD RS780L [Radeon 3000]                                                    | 89       | 1.63%   |
| Nvidia GK208B [GeForce GT 710]                                              | 82       | 1.51%   |
| Intel HD Graphics 630                                                       | 76       | 1.4%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 76       | 1.4%    |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                     | 65       | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 65       | 1.19%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 63       | 1.16%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                       | 62       | 1.14%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 61       | 1.12%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 59       | 1.08%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 55       | 1.01%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 54       | 0.99%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 52       | 0.95%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 51       | 0.94%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 50       | 0.92%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 43       | 0.79%   |
| Nvidia GF108 [GeForce GT 730]                                               | 43       | 0.79%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 42       | 0.77%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 40       | 0.73%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 37       | 0.68%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 36       | 0.66%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 36       | 0.66%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 36       | 0.66%   |
| Intel HD Graphics 530                                                       | 36       | 0.66%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 36       | 0.66%   |
| Nvidia GF119 [GeForce GT 610]                                               | 34       | 0.62%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                         | 34       | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| 1 x Intel               | 1755     | 34.15%  |
| 1 x Nvidia              | 1694     | 32.96%  |
| 1 x AMD                 | 1470     | 28.6%   |
| Intel + Nvidia          | 51       | 0.99%   |
| 2 x AMD                 | 43       | 0.84%   |
| 1 x VIA                 | 31       | 0.6%    |
| AMD + Nvidia            | 28       | 0.54%   |
| Intel + AMD             | 22       | 0.43%   |
| 2 x Nvidia              | 18       | 0.35%   |
| 1 x Matrox              | 7        | 0.14%   |
| 1 x SiS                 | 5        | 0.1%    |
| 2 x Intel               | 4        | 0.08%   |
| Intel + Silicon Motion  | 2        | 0.04%   |
| Other                   | 1        | 0.02%   |
| 1 x Silicon Motion      | 1        | 0.02%   |
| 1 x S3 Graphics         | 1        | 0.02%   |
| 1 x Red Hat             | 1        | 0.02%   |
| Nvidia + Silicon Motion | 1        | 0.02%   |
| Intel + 2 x AMD         | 1        | 0.02%   |
| 1 x ASPEED              | 1        | 0.02%   |
| AMD + 2 x Nvidia        | 1        | 0.02%   |
| AMD + Matrox            | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 3952     | 76.72%  |
| Proprietary | 948      | 18.4%   |
| Unknown     | 251      | 4.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2409     | 45.94%  |
| 1.01-2.0   | 765      | 14.59%  |
| 0.51-1.0   | 668      | 12.74%  |
| 0.01-0.5   | 540      | 10.3%   |
| 3.01-4.0   | 432      | 8.24%   |
| 7.01-8.0   | 222      | 4.23%   |
| 5.01-6.0   | 129      | 2.46%   |
| 2.01-3.0   | 48       | 0.92%   |
| 8.01-16.0  | 26       | 0.5%    |
| 16.01-24.0 | 3        | 0.06%   |
| 4.01-5.0   | 2        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 1351     | 26.77%  |
| Samsung Electronics  | 1116     | 22.12%  |
| AOC                  | 761      | 15.08%  |
| Dell                 | 379      | 7.51%   |
| Philips              | 283      | 5.61%   |
| Acer                 | 164      | 3.25%   |
| LG Electronics       | 157      | 3.11%   |
| Hewlett-Packard      | 104      | 2.06%   |
| Unknown              | 59       | 1.17%   |
| Sony                 | 58       | 1.15%   |
| BenQ                 | 58       | 1.15%   |
| Positivo             | 45       | 0.89%   |
| Lenovo               | 45       | 0.89%   |
| ASUSTek Computer     | 26       | 0.52%   |
| Ancor Communications | 23       | 0.46%   |
| Panasonic            | 22       | 0.44%   |
| GDH                  | 20       | 0.4%    |
| Unknown (XXX)        | 18       | 0.36%   |
| VIE                  | 14       | 0.28%   |
| TXD                  | 14       | 0.28%   |
| RTK                  | 13       | 0.26%   |
| NCS                  | 13       | 0.26%   |
| Daewoo               | 12       | 0.24%   |
| HB@                  | 11       | 0.22%   |
| AGO                  | 11       | 0.22%   |
| Toshiba              | 10       | 0.2%    |
| Envision             | 10       | 0.2%    |
| JRY                  | 9        | 0.18%   |
| Unknown              | 9        | 0.18%   |
| STA                  | 8        | 0.16%   |
| PZG                  | 8        | 0.16%   |
| Pixio                | 8        | 0.16%   |
| SKY                  | 7        | 0.14%   |
| MSI                  | 7        | 0.14%   |
| ___                  | 6        | 0.12%   |
| Philco               | 6        | 0.12%   |
| MStar                | 6        | 0.12%   |
| Envision Peripherals | 6        | 0.12%   |
| CVT                  | 6        | 0.12%   |
| STD                  | 5        | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch          | 110      | 2.04%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 69       | 1.28%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 67       | 1.24%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 60       | 1.11%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 48       | 0.89%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch               | 35       | 0.65%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 35       | 0.65%   |
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                    | 35       | 0.65%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch  | 34       | 0.63%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                 | 34       | 0.63%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch    | 32       | 0.59%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                  | 31       | 0.58%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 31       | 0.58%   |
| Goldstar W1752 GSM4490 1440x900 370x232mm 17.2-inch                  | 29       | 0.54%   |
| AOC 1950W AOC1950 1366x768 410x230mm 18.5-inch                       | 28       | 0.52%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch             | 27       | 0.5%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 27       | 0.5%    |
| Goldstar 22MP55 GSM5A26 1920x1080 477x268mm 21.5-inch                | 27       | 0.5%    |
| Samsung Electronics SyncMaster SAM0598 1360x768 410x230mm 18.5-inch  | 26       | 0.48%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                        | 25       | 0.46%   |
| AOC 1619w AOC1619 1366x768 340x190mm 15.3-inch                       | 25       | 0.46%   |
| LG Electronics LCD Monitor LG ULTRAWIDE 2560x1080                    | 24       | 0.45%   |
| Philips PHL 223V5LH PHLC114 1920x1080 477x268mm 21.5-inch            | 23       | 0.43%   |
| Goldstar 25UM58G GSM5B98 2560x1080 673x284mm 28.8-inch               | 23       | 0.43%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch | 22       | 0.41%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch              | 22       | 0.41%   |
| Acer V226HQL ACR032D 1920x1080 477x268mm 21.5-inch                   | 22       | 0.41%   |
| Samsung Electronics SyncMaster SAM01CE 1024x768 300x230mm 14.9-inch  | 21       | 0.39%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                  | 21       | 0.39%   |
| AOC 1621w AOC1621 1366x768 344x194mm 15.5-inch                       | 21       | 0.39%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch    | 20       | 0.37%   |
| Samsung Electronics SMT24A550 SAM07B5 1920x1080 531x299mm 24.0-inch  | 19       | 0.35%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 19       | 0.35%   |
| AOC 912Vwa AOC1912 1440x900 408x255mm 18.9-inch                      | 19       | 0.35%   |
| AOC 712Sa AOC1712 1280x1024 340x270mm 17.1-inch                      | 19       | 0.35%   |
| AOC 2470W1M AOC2470 1920x1080 527x296mm 23.8-inch                    | 19       | 0.35%   |
| Positivo FIT85X NON1801 1360x768 344x194mm 15.5-inch                 | 18       | 0.33%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch               | 18       | 0.33%   |
| Goldstar E1941 GSM4BF0 1366x768 410x230mm 18.5-inch                  | 18       | 0.33%   |
| AOC Q27P2W AOC2702 2560x1440 597x336mm 27.0-inch                     | 18       | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1759     | 34.61%  |
| 1366x768 (WXGA)    | 798      | 15.7%   |
| 1600x900 (HD+)     | 386      | 7.59%   |
| 1440x900 (WXGA+)   | 338      | 6.65%   |
| 1280x1024 (SXGA)   | 324      | 6.37%   |
| 1360x768           | 296      | 5.82%   |
| 2560x1080          | 260      | 5.12%   |
| 3840x2160 (4K)     | 224      | 4.41%   |
| 1680x1050 (WSXGA+) | 163      | 3.21%   |
| 1024x768 (XGA)     | 105      | 2.07%   |
| Unknown            | 101      | 1.99%   |
| 2560x1440 (QHD)    | 77       | 1.51%   |
| 1280x720 (HD)      | 44       | 0.87%   |
| 3840x1080          | 27       | 0.53%   |
| 1920x540           | 25       | 0.49%   |
| 2288x1287          | 19       | 0.37%   |
| 3440x1440          | 18       | 0.35%   |
| 1920x1200 (WUXGA)  | 18       | 0.35%   |
| 1152x864           | 9        | 0.18%   |
| 4480x1080          | 6        | 0.12%   |
| 1600x1200          | 6        | 0.12%   |
| 1280x800 (WXGA)    | 6        | 0.12%   |
| 5760x1080          | 5        | 0.1%    |
| 3360x1080          | 5        | 0.1%    |
| 3200x1080          | 5        | 0.1%    |
| 3286x1080          | 4        | 0.08%   |
| 3520x1080          | 3        | 0.06%   |
| 2732x768           | 3        | 0.06%   |
| 2560x1600          | 3        | 0.06%   |
| 6400x1080          | 2        | 0.04%   |
| 5120x1440          | 2        | 0.04%   |
| 3600x1080          | 2        | 0.04%   |
| 3360x1050          | 2        | 0.04%   |
| 2800x900           | 2        | 0.04%   |
| 2720x768           | 2        | 0.04%   |
| 2720x1024          | 2        | 0.04%   |
| 2646x768           | 2        | 0.04%   |
| 2646x1024          | 2        | 0.04%   |
| 1280x960           | 2        | 0.04%   |
| 640x480            | 1        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 18      | 758      | 14.8%   |
| 21      | 614      | 11.99%  |
| 23      | 567      | 11.07%  |
| Unknown | 486      | 9.49%   |
| 17      | 362      | 7.07%   |
| 15      | 305      | 5.96%   |
| 24      | 291      | 5.68%   |
| 20      | 283      | 5.53%   |
| 19      | 282      | 5.51%   |
| 27      | 235      | 4.59%   |
| 34      | 219      | 4.28%   |
| 22      | 106      | 2.07%   |
| 31      | 103      | 2.01%   |
| 54      | 48       | 0.94%   |
| 72      | 47       | 0.92%   |
| 40      | 44       | 0.86%   |
| 32      | 42       | 0.82%   |
| 28      | 41       | 0.8%    |
| 84      | 38       | 0.74%   |
| 26      | 28       | 0.55%   |
| 16      | 28       | 0.55%   |
| 46      | 26       | 0.51%   |
| 52      | 24       | 0.47%   |
| 14      | 23       | 0.45%   |
| 12      | 20       | 0.39%   |
| 142     | 15       | 0.29%   |
| 13      | 14       | 0.27%   |
| 25      | 11       | 0.21%   |
| 48      | 8        | 0.16%   |
| 37      | 7        | 0.14%   |
| 49      | 5        | 0.1%    |
| 39      | 5        | 0.1%    |
| 65      | 4        | 0.08%   |
| 43      | 4        | 0.08%   |
| 47      | 3        | 0.06%   |
| 41      | 3        | 0.06%   |
| 75      | 2        | 0.04%   |
| 60      | 2        | 0.04%   |
| 55      | 2        | 0.04%   |
| 50      | 2        | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 401-500        | 1921     | 38.52%  |
| 501-600        | 1034     | 20.73%  |
| 301-350        | 582      | 11.67%  |
| Unknown        | 486      | 9.75%   |
| 701-800        | 262      | 5.25%   |
| 351-400        | 184      | 3.69%   |
| 601-700        | 180      | 3.61%   |
| 1001-1500      | 125      | 2.51%   |
| 1501-2000      | 87       | 1.74%   |
| 801-900        | 58       | 1.16%   |
| 201-300        | 45       | 0.9%    |
| More than 2000 | 15       | 0.3%    |
| 901-1000       | 8        | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 3140     | 65.46%  |
| 16/10   | 446      | 9.3%    |
| Unknown | 428      | 8.92%   |
| 5/4     | 319      | 6.65%   |
| 21/9    | 246      | 5.13%   |
| 4/3     | 149      | 3.11%   |
| 3/2     | 42       | 0.88%   |
| 1.00    | 17       | 0.35%   |
| 32/9    | 5        | 0.1%    |
| 2.00    | 2        | 0.04%   |
| 6/5     | 1        | 0.02%   |
| 0.56    | 1        | 0.02%   |
| 0.31    | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1331     | 26.34%  |
| 141-150        | 939      | 18.58%  |
| 151-200        | 773      | 15.3%   |
| Unknown        | 486      | 9.62%   |
| 351-500        | 378      | 7.48%   |
| 101-110        | 283      | 5.6%    |
| 301-350        | 238      | 4.71%   |
| More than 1000 | 193      | 3.82%   |
| 251-300        | 119      | 2.36%   |
| 131-140        | 101      | 2%      |
| 501-1000       | 101      | 2%      |
| 111-120        | 31       | 0.61%   |
| 81-90          | 21       | 0.42%   |
| 71-80          | 20       | 0.4%    |
| 91-100         | 19       | 0.38%   |
| 121-130        | 17       | 0.34%   |
| 51-60          | 2        | 0.04%   |
| 41-50          | 1        | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 3133     | 64.72%  |
| 101-120 | 866      | 17.89%  |
| Unknown | 487      | 10.06%  |
| 1-50    | 257      | 5.31%   |
| 121-160 | 60       | 1.24%   |
| 161-240 | 38       | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 4133     | 80.14%  |
| 2     | 694      | 13.46%  |
| 0     | 284      | 5.51%   |
| 3     | 41       | 0.8%    |
| 4     | 5        | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 3654     | 53.74%  |
| Intel                             | 939      | 13.81%  |
| Qualcomm Atheros                  | 575      | 8.46%   |
| Ralink Technology                 | 359      | 5.28%   |
| Nvidia                            | 192      | 2.82%   |
| Broadcom                          | 157      | 2.31%   |
| TP-Link                           | 135      | 1.99%   |
| Qualcomm Atheros Communications   | 116      | 1.71%   |
| Ralink                            | 96       | 1.41%   |
| Samsung Electronics               | 63       | 0.93%   |
| D-Link                            | 59       | 0.87%   |
| Microsoft                         | 49       | 0.72%   |
| VIA Technologies                  | 48       | 0.71%   |
| Marvell Technology Group          | 43       | 0.63%   |
| MediaTek                          | 34       | 0.5%    |
| Broadcom Limited                  | 34       | 0.5%    |
| Xiaomi                            | 31       | 0.46%   |
| D-Link System                     | 30       | 0.44%   |
| JMicron Technology                | 23       | 0.34%   |
| Motorola PCS                      | 18       | 0.26%   |
| Motorola                          | 14       | 0.21%   |
| ASIX Electronics                  | 12       | 0.18%   |
| Silicon Integrated Systems [SiS]  | 6        | 0.09%   |
| ICS Advent                        | 6        | 0.09%   |
| Huawei Technologies               | 6        | 0.09%   |
| Edimax Technology                 | 6        | 0.09%   |
| Mercucys                          | 5        | 0.07%   |
| DisplayLink                       | 5        | 0.07%   |
| ASUSTek Computer                  | 5        | 0.07%   |
| 3Com                              | 5        | 0.07%   |
| Sundance Technology Inc / IC Plus | 4        | 0.06%   |
| STMicroelectronics                | 4        | 0.06%   |
| QinHeng Electronics               | 4        | 0.06%   |
| Encore Electronics                | 4        | 0.06%   |
| Accton Technology                 | 4        | 0.06%   |
| Qualcomm                          | 3        | 0.04%   |
| Linksys                           | 3        | 0.04%   |
| LG Electronics                    | 3        | 0.04%   |
| Hangzhou Silan Microelectronics   | 3        | 0.04%   |
| Arduino SA                        | 3        | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2841     | 38.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 485      | 6.53%   |
| Ralink MT7601U Wireless Adapter                                   | 204      | 2.75%   |
| Nvidia MCP61 Ethernet                                             | 164      | 2.21%   |
| Qualcomm Atheros AR9271 802.11n                                   | 104      | 1.4%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 102      | 1.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 100      | 1.35%   |
| Intel Ethernet Connection (2) I219-V                              | 94       | 1.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 93       | 1.25%   |
| Intel I211 Gigabit Network Connection                             | 86       | 1.16%   |
| Intel Ethernet Connection (7) I219-V                              | 86       | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 85       | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 81       | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 79       | 1.06%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 78       | 1.05%   |
| Ralink RT5370 Wireless Adapter                                    | 73       | 0.98%   |
| Intel Wi-Fi 6 AX200                                               | 66       | 0.89%   |
| Intel 82579V Gigabit Network Connection                           | 65       | 0.88%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 52       | 0.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 52       | 0.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 50       | 0.67%   |
| Realtek 802.11ac NIC                                              | 50       | 0.67%   |
| Intel Ethernet Connection I217-LM                                 | 45       | 0.61%   |
| Microsoft Xbox 360 Wireless Adapter                               | 42       | 0.57%   |
| Intel 82578DC Gigabit Network Connection                          | 41       | 0.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 40       | 0.54%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 39       | 0.53%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 37       | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 37       | 0.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 36       | 0.48%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 36       | 0.48%   |
| Intel Ethernet Connection (2) I218-V                              | 33       | 0.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 32       | 0.43%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 30       | 0.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 30       | 0.4%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 30       | 0.4%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 29       | 0.39%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 29       | 0.39%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 28       | 0.38%   |
| Intel Ethernet Controller I225-V                                  | 27       | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 529      | 27.02%  |
| Ralink Technology                     | 359      | 18.34%  |
| Qualcomm Atheros                      | 271      | 13.84%  |
| Intel                                 | 219      | 11.18%  |
| TP-Link                               | 131      | 6.69%   |
| Qualcomm Atheros Communications       | 116      | 5.92%   |
| Ralink                                | 96       | 4.9%    |
| D-Link                                | 59       | 3.01%   |
| Microsoft                             | 49       | 2.5%    |
| Broadcom                              | 36       | 1.84%   |
| MediaTek                              | 27       | 1.38%   |
| D-Link System                         | 19       | 0.97%   |
| Broadcom Limited                      | 8        | 0.41%   |
| Marvell Technology Group              | 6        | 0.31%   |
| Edimax Technology                     | 6        | 0.31%   |
| Mercucys                              | 5        | 0.26%   |
| Encore Electronics                    | 4        | 0.2%    |
| Linksys                               | 3        | 0.15%   |
| Xiaomi                                | 2        | 0.1%    |
| Micro Star International              | 2        | 0.1%    |
| IMC Networks                          | 2        | 0.1%    |
| ASUSTek Computer                      | 2        | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2        | 0.1%    |
| Texas Instruments                     | 1        | 0.05%   |
| Samsung Electronics                   | 1        | 0.05%   |
| Philips (or NXP)                      | 1        | 0.05%   |
| NetGear                               | 1        | 0.05%   |
| Accton Technology                     | 1        | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Ralink MT7601U Wireless Adapter                                | 204      | 10.29%  |
| Qualcomm Atheros AR9271 802.11n                                | 104      | 5.24%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 102      | 5.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 85       | 4.29%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 78       | 3.93%   |
| Ralink RT5370 Wireless Adapter                                 | 73       | 3.68%   |
| Intel Wi-Fi 6 AX200                                            | 66       | 3.33%   |
| Realtek 802.11ac NIC                                           | 50       | 2.52%   |
| Microsoft Xbox 360 Wireless Adapter                            | 42       | 2.12%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 40       | 2.02%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 36       | 1.82%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 36       | 1.82%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 32       | 1.61%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 30       | 1.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 30       | 1.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 30       | 1.51%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 29       | 1.46%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 28       | 1.41%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 26       | 1.31%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 25       | 1.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 24       | 1.21%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 22       | 1.11%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 21       | 1.06%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 21       | 1.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 20       | 1.01%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 19       | 0.96%   |
| Intel Wireless-AC 9260                                         | 19       | 0.96%   |
| Intel Wireless 7260                                            | 19       | 0.96%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 18       | 0.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 18       | 0.91%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 18       | 0.91%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 16       | 0.81%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 16       | 0.81%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                      | 14       | 0.71%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 14       | 0.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 14       | 0.71%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 13       | 0.66%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 13       | 0.66%   |
| Intel Wireless 7265                                            | 13       | 0.66%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 12       | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 3497     | 66.22%  |
| Intel                             | 811      | 15.36%  |
| Qualcomm Atheros                  | 328      | 6.21%   |
| Nvidia                            | 192      | 3.64%   |
| Broadcom                          | 122      | 2.31%   |
| Samsung Electronics               | 62       | 1.17%   |
| VIA Technologies                  | 47       | 0.89%   |
| Marvell Technology Group          | 37       | 0.7%    |
| Xiaomi                            | 29       | 0.55%   |
| Broadcom Limited                  | 26       | 0.49%   |
| JMicron Technology                | 23       | 0.44%   |
| Motorola PCS                      | 14       | 0.27%   |
| ASIX Electronics                  | 12       | 0.23%   |
| D-Link System                     | 11       | 0.21%   |
| MediaTek                          | 7        | 0.13%   |
| Silicon Integrated Systems [SiS]  | 6        | 0.11%   |
| ICS Advent                        | 6        | 0.11%   |
| DisplayLink                       | 5        | 0.09%   |
| 3Com                              | 5        | 0.09%   |
| TP-Link                           | 4        | 0.08%   |
| Sundance Technology Inc / IC Plus | 4        | 0.08%   |
| Huawei Technologies               | 4        | 0.08%   |
| Qualcomm                          | 3        | 0.06%   |
| LG Electronics                    | 3        | 0.06%   |
| Hangzhou Silan Microelectronics   | 3        | 0.06%   |
| ASUSTek Computer                  | 3        | 0.06%   |
| Accton Technology                 | 3        | 0.06%   |
| T & A Mobile Phones               | 2        | 0.04%   |
| OPPO Electronics                  | 2        | 0.04%   |
| Aquantia                          | 2        | 0.04%   |
| Apple                             | 2        | 0.04%   |
| ZTE WCDMA Technologies MSM        | 1        | 0.02%   |
| Spreadtrum Communications         | 1        | 0.02%   |
| SK hynix                          | 1        | 0.02%   |
| Netchip Technology                | 1        | 0.02%   |
| IBM                               | 1        | 0.02%   |
| AMD                               | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2841     | 52.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 485      | 8.99%   |
| Nvidia MCP61 Ethernet                                             | 164      | 3.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 100      | 1.85%   |
| Intel Ethernet Connection (2) I219-V                              | 94       | 1.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 93       | 1.72%   |
| Intel I211 Gigabit Network Connection                             | 86       | 1.59%   |
| Intel Ethernet Connection (7) I219-V                              | 86       | 1.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 81       | 1.5%    |
| Realtek RTL8125 2.5GbE Controller                                 | 79       | 1.47%   |
| Intel 82579V Gigabit Network Connection                           | 65       | 1.21%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 52       | 0.96%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 52       | 0.96%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 50       | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 45       | 0.83%   |
| Intel 82578DC Gigabit Network Connection                          | 41       | 0.76%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 39       | 0.72%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 37       | 0.69%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 37       | 0.69%   |
| Intel Ethernet Connection (2) I218-V                              | 33       | 0.61%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 29       | 0.54%   |
| Intel Ethernet Controller I225-V                                  | 27       | 0.5%    |
| Intel 82578DM Gigabit Network Connection                          | 27       | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 25       | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 25       | 0.46%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 22       | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 22       | 0.41%   |
| Intel Ethernet Connection I217-V                                  | 21       | 0.39%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 20       | 0.37%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 17       | 0.32%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 17       | 0.32%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 16       | 0.3%    |
| Intel Ethernet Connection (12) I219-V                             | 16       | 0.3%    |
| Intel 82566DM-2 Gigabit Network Connection                        | 16       | 0.3%    |
| VIA VT6105/VT6106S [Rhine-III]                                    | 14       | 0.26%   |
| Motorola PCS motorola one macro                                   | 14       | 0.26%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 13       | 0.24%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 13       | 0.24%   |
| Intel Ethernet Connection (14) I219-V                             | 13       | 0.24%   |
| Intel 82574L Gigabit Network Connection                           | 13       | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 4982     | 72.47%  |
| WiFi     | 1843     | 26.81%  |
| Modem    | 39       | 0.57%   |
| Unknown  | 11       | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3996     | 76.8%   |
| WiFi     | 1206     | 23.18%  |
| Unknown  | 1        | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 3965     | 77.61%  |
| 2     | 983      | 19.24%  |
| 0     | 81       | 1.59%   |
| 3     | 71       | 1.39%   |
| 4     | 7        | 0.14%   |
| 6     | 1        | 0.02%   |
| 5     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3917     | 75.23%  |
| Yes  | 1290     | 24.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 473      | 50.37%  |
| Intel                           | 198      | 21.09%  |
| Realtek Semiconductor           | 86       | 9.16%   |
| Qualcomm Atheros Communications | 69       | 7.35%   |
| Broadcom                        | 20       | 2.13%   |
| ASUSTek Computer                | 19       | 2.02%   |
| MediaTek                        | 17       | 1.81%   |
| Apple                           | 11       | 1.17%   |
| IMC Networks                    | 9        | 0.96%   |
| Integrated System Solution      | 7        | 0.75%   |
| Actions                         | 6        | 0.64%   |
| ISSC                            | 4        | 0.43%   |
| Foxconn / Hon Hai               | 4        | 0.43%   |
| Conwise Technology              | 3        | 0.32%   |
| Unknown                         | 3        | 0.32%   |
| Micro Star International        | 2        | 0.21%   |
| TP-Link                         | 1        | 0.11%   |
| SINO WEALTH                     | 1        | 0.11%   |
| Realtek                         | 1        | 0.11%   |
| Ralink                          | 1        | 0.11%   |
| Qcom                            | 1        | 0.11%   |
| Motorola PCS                    | 1        | 0.11%   |
| D-Link                          | 1        | 0.11%   |
| AboCom Systems                  | 1        | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 473      | 50.27%  |
| Realtek Bluetooth Radio                               | 83       | 8.82%   |
| Intel AX200 Bluetooth                                 | 59       | 6.27%   |
| Intel Bluetooth wireless interface                    | 55       | 5.84%   |
| Qualcomm Atheros  Bluetooth Device                    | 32       | 3.4%    |
| Intel AX210 Bluetooth                                 | 26       | 2.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 20       | 2.13%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 18       | 1.91%   |
| Intel Wireless-AC 3168 Bluetooth                      | 18       | 1.91%   |
| MediaTek Wireless_Device                              | 17       | 1.81%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 12       | 1.28%   |
| Apple Bluetooth Host Controller                       | 9        | 0.96%   |
| Intel AX201 Bluetooth                                 | 7        | 0.74%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 6        | 0.64%   |
| Actions general adapter                               | 6        | 0.64%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 5        | 0.53%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 5        | 0.53%   |
| ASUS Bluetooth Radio                                  | 5        | 0.53%   |
| ISSC Bluetooth Device                                 | 4        | 0.43%   |
| Integrated System Solution Bluetooth Device           | 4        | 0.43%   |
| IMC Networks Wireless_Device                          | 4        | 0.43%   |
| IMC Networks Bluetooth Radio                          | 4        | 0.43%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 4        | 0.43%   |
| ASUS Bluetooth Adapter                                | 4        | 0.43%   |
| Qualcomm Atheros Bluetooth                            | 3        | 0.32%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 3        | 0.32%   |
| Conwise CW6622                                        | 3        | 0.32%   |
| Broadcom Bluetooth Controller                         | 3        | 0.32%   |
| Broadcom Bluetooth 2.0+eDR dongle                     | 3        | 0.32%   |
| ASUS Qualcomm Bluetooth 4.1                           | 3        | 0.32%   |
| Unknown                                               | 3        | 0.32%   |
| Micro Star International Bluetooth Device             | 2        | 0.21%   |
| Intel Bluetooth Device                                | 2        | 0.21%   |
| Foxconn / Hon Hai Wireless_Device                     | 2        | 0.21%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2        | 0.21%   |
| Broadcom BCM920702 Bluetooth 4.0 Zero Touch Dongle    | 2        | 0.21%   |
| Broadcom BCM2210 Bluetooth                            | 2        | 0.21%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 0.21%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2        | 0.21%   |
| ASUS BCM20702A0                                       | 2        | 0.21%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 3281     | 42.48%  |
| AMD                                             | 1945     | 25.18%  |
| Nvidia                                          | 1615     | 20.91%  |
| C-Media Electronics                             | 201      | 2.6%    |
| Generalplus Technology                          | 91       | 1.18%   |
| VIA Technologies                                | 54       | 0.7%    |
| Logitech                                        | 54       | 0.7%    |
| JMTek                                           | 52       | 0.67%   |
| Creative Labs                                   | 41       | 0.53%   |
| Kingston Technology                             | 37       | 0.48%   |
| Texas Instruments                               | 34       | 0.44%   |
| Corsair                                         | 19       | 0.25%   |
| Microsoft                                       | 17       | 0.22%   |
| Razer USA                                       | 14       | 0.18%   |
| BEHRINGER International                         | 14       | 0.18%   |
| Tenx Technology                                 | 13       | 0.17%   |
| Plantronics                                     | 10       | 0.13%   |
| Licensed by Sony Computer Entertainment America | 10       | 0.13%   |
| Sony                                            | 8        | 0.1%    |
| Goldvish                                        | 8        | 0.1%    |
| GN Netcom                                       | 8        | 0.1%    |
| Silicon Integrated Systems [SiS]                | 7        | 0.09%   |
| Fry's Electronics                               | 7        | 0.09%   |
| Focusrite-Novation                              | 7        | 0.09%   |
| ASUSTek Computer                                | 7        | 0.09%   |
| Samson Technologies                             | 6        | 0.08%   |
| M-Audio                                         | 6        | 0.08%   |
| Jieli Technology                                | 6        | 0.08%   |
| JBL                                             | 6        | 0.08%   |
| FIFINE Microphones                              | 6        | 0.08%   |
| Dell                                            | 6        | 0.08%   |
| Creative Technology                             | 6        | 0.08%   |
| SteelSeries ApS                                 | 5        | 0.06%   |
| Philips (or NXP)                                | 5        | 0.06%   |
| KTMicro                                         | 5        | 0.06%   |
| HECATE G4 TE GAMING HEADSET                     | 5        | 0.06%   |
| Cirrus Logic                                    | 5        | 0.06%   |
| Realtek Semiconductor                           | 4        | 0.05%   |
| Medeli Electronics                              | 4        | 0.05%   |
| Elite Silicon                                   | 4        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 720      | 8%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 612      | 6.8%    |
| AMD SBx00 Azalia (Intel HDA)                                                      | 437      | 4.86%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 385      | 4.28%   |
| AMD Family 17h/19h HD Audio Controller                                            | 336      | 3.73%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 302      | 3.36%   |
| AMD Starship/Matisse HD Audio Controller                                          | 241      | 2.68%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 235      | 2.61%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 233      | 2.59%   |
| Nvidia High Definition Audio Controller                                           | 229      | 2.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 213      | 2.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 193      | 2.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 193      | 2.14%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 185      | 2.06%   |
| Nvidia MCP61 High Definition Audio                                                | 180      | 2%      |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 160      | 1.78%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 156      | 1.73%   |
| Intel 200 Series PCH HD Audio                                                     | 156      | 1.73%   |
| AMD FCH Azalia Controller                                                         | 152      | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                        | 150      | 1.67%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 127      | 1.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 112      | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                                     | 106      | 1.18%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 98       | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                                     | 94       | 1.04%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 94       | 1.04%   |
| Generalplus Technology USB Audio Device                                           | 91       | 1.01%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 80       | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                                     | 74       | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller        | 65       | 0.72%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 64       | 0.71%   |
| Nvidia GF119 HDMI Audio Controller                                                | 58       | 0.64%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 55       | 0.61%   |
| AMD Navi 10 HDMI Audio                                                            | 53       | 0.59%   |
| Nvidia GP104 High Definition Audio Controller                                     | 51       | 0.57%   |
| Nvidia GM206 High Definition Audio Controller                                     | 51       | 0.57%   |
| Nvidia GK107 HDMI Audio Controller                                                | 51       | 0.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 51       | 0.57%   |
| Intel C610/X99 series chipset HD Audio Controller                                 | 50       | 0.56%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 50       | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 696      | 28.1%   |
| Kingston            | 622      | 25.11%  |
| Corsair             | 182      | 7.35%   |
| Smart               | 154      | 6.22%   |
| Crucial             | 106      | 4.28%   |
| A-DATA Technology   | 95       | 3.84%   |
| Samsung Electronics | 74       | 2.99%   |
| SK hynix            | 64       | 2.58%   |
| Team                | 54       | 2.18%   |
| Unknown             | 44       | 1.78%   |
| Micron Technology   | 42       | 1.7%    |
| G.Skill             | 41       | 1.66%   |
| Teikon              | 30       | 1.21%   |
| Multilaser          | 26       | 1.05%   |
| Atermiter           | 18       | 0.73%   |
| Patriot             | 16       | 0.65%   |
| Apacer              | 15       | 0.61%   |
| Avant               | 11       | 0.44%   |
| GeIL                | 10       | 0.4%    |
| Kreton              | 9        | 0.36%   |
| Kllisre             | 9        | 0.36%   |
| HBS                 | 8        | 0.32%   |
| Asgard              | 8        | 0.32%   |
| CSX                 | 7        | 0.28%   |
| RZX                 | 6        | 0.24%   |
| Nanya Technology    | 6        | 0.24%   |
| Unknown (82B5)      | 5        | 0.2%    |
| MemoWise            | 5        | 0.2%    |
| Hewlett-Packard     | 5        | 0.2%    |
| GLOWAY              | 5        | 0.2%    |
| Elpida              | 5        | 0.2%    |
| Qbex                | 4        | 0.16%   |
| PUSKILL             | 4        | 0.16%   |
| Positivo            | 4        | 0.16%   |
| Kingmax             | 4        | 0.16%   |
| Juhor               | 4        | 0.16%   |
| Golden Empire       | 4        | 0.16%   |
| Unknown (ABCD)      | 3        | 0.12%   |
| Transcend           | 3        | 0.12%   |
| Smart Modular       | 3        | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 50       | 1.81%   |
| Unknown                                                  | 44       | 1.59%   |
| Unknown RAM Module 2GB DIMM SDRAM                        | 40       | 1.45%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                | 36       | 1.3%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 33       | 1.2%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s      | 33       | 1.2%    |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 30       | 1.09%   |
| Unknown RAM Module 2048MB DIMM SDRAM                     | 29       | 1.05%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                  | 26       | 0.94%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                 | 21       | 0.76%   |
| Unknown RAM Module 2GB DIMM DDR2                         | 21       | 0.76%   |
| Unknown RAM Module 4GB DIMM SDRAM                        | 20       | 0.72%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s      | 20       | 0.72%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s             | 19       | 0.69%   |
| Unknown RAM Module 2GB DIMM 800MT/s                      | 18       | 0.65%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 17       | 0.62%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s      | 17       | 0.62%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                | 15       | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 15       | 0.54%   |
| Kingston RAM 9905471-006.A00LF 4096MB DIMM DDR3 1333MT/s | 15       | 0.54%   |
| Kingston RAM 99U5474-028.A00LF 4GB DIMM DDR3 1333MT/s    | 14       | 0.51%   |
| Kingston RAM 99U5403-159.A01LF 8GB DIMM DDR3 1600MT/s    | 14       | 0.51%   |
| Unknown RAM Module 4096MB DIMM SDRAM                     | 13       | 0.47%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s      | 13       | 0.47%   |
| Smart RAM SH564568FH8N0QHSCR 2GB DIMM DDR3 1333MT/s      | 13       | 0.47%   |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s            | 13       | 0.47%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1600MT/s      | 13       | 0.47%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s              | 13       | 0.47%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                | 12       | 0.43%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                | 12       | 0.43%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s             | 12       | 0.43%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                   | 12       | 0.43%   |
| Team RAM TEAMGROUP-UD4-3200 8192MB DIMM DDR4 3733MT/s    | 12       | 0.43%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s     | 12       | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 11       | 0.4%    |
| Unknown RAM Module 2048MB DIMM DDR2                      | 11       | 0.4%    |
| Team RAM TEAMGROUP-UD4-2666 8GB DIMM DDR4 3000MT/s       | 11       | 0.4%    |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM 1333MT/s           | 11       | 0.4%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                     | 10       | 0.36%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 10       | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Desktops | Percent |
|--------------|----------|---------|
| DDR3         | 851      | 39.33%  |
| DDR4         | 742      | 34.29%  |
| Unknown      | 218      | 10.07%  |
| DDR2         | 159      | 7.35%   |
| SDRAM        | 141      | 6.52%   |
| DDR          | 35       | 1.62%   |
| DDR5         | 10       | 0.46%   |
| LPDDR4       | 4        | 0.18%   |
| DRAM         | 2        | 0.09%   |
| RAM          | 1        | 0.05%   |
| DDR2 FB-DIMM | 1        | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 2043     | 95.56%  |
| SODIMM       | 88       | 4.12%   |
| RIMM         | 4        | 0.19%   |
| FB-DIMM      | 2        | 0.09%   |
| Row Of Chips | 1        | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 780      | 32.23%  |
| 4096  | 773      | 31.94%  |
| 2048  | 474      | 19.59%  |
| 16384 | 209      | 8.64%   |
| 32768 | 83       | 3.43%   |
| 1024  | 83       | 3.43%   |
| 512   | 12       | 0.5%    |
| 256   | 3        | 0.12%   |
| 15616 | 1        | 0.04%   |
| 1536  | 1        | 0.04%   |
| 16    | 1        | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1333    | 459      | 19.08%  |
| 1600    | 427      | 17.75%  |
| Unknown | 187      | 7.77%   |
| 2400    | 146      | 6.07%   |
| 800     | 109      | 4.53%   |
| 2667    | 106      | 4.41%   |
| 3200    | 103      | 4.28%   |
| 667     | 101      | 4.2%    |
| 3600    | 84       | 3.49%   |
| 3000    | 71       | 2.95%   |
| 2133    | 71       | 2.95%   |
| 3400    | 64       | 2.66%   |
| 1867    | 41       | 1.7%    |
| 3466    | 38       | 1.58%   |
| 1866    | 35       | 1.45%   |
| 2666    | 32       | 1.33%   |
| 2800    | 31       | 1.29%   |
| 1066    | 28       | 1.16%   |
| 2933    | 25       | 1.04%   |
| 1067    | 22       | 0.91%   |
| 400     | 21       | 0.87%   |
| 3733    | 20       | 0.83%   |
| 3800    | 18       | 0.75%   |
| 3151    | 17       | 0.71%   |
| 533     | 17       | 0.71%   |
| 333     | 16       | 0.67%   |
| 1334    | 13       | 0.54%   |
| 3334    | 9        | 0.37%   |
| 1800    | 7        | 0.29%   |
| 3333    | 5        | 0.21%   |
| 41632   | 4        | 0.17%   |
| 5354    | 4        | 0.17%   |
| 3933    | 4        | 0.17%   |
| 2448    | 4        | 0.17%   |
| 6000    | 3        | 0.12%   |
| 4800    | 3        | 0.12%   |
| 3066    | 3        | 0.12%   |
| 2733    | 3        | 0.12%   |
| 2132    | 3        | 0.12%   |
| 49926   | 2        | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 100      | 44.64%  |
| Seiko Epson           | 57       | 25.45%  |
| Samsung Electronics   | 21       | 9.38%   |
| Canon                 | 18       | 8.04%   |
| Brother Industries    | 17       | 7.59%   |
| Lexmark International | 3        | 1.34%   |
| QinHeng Electronics   | 2        | 0.89%   |
| Apple                 | 2        | 0.89%   |
| Ricoh                 | 1        | 0.45%   |
| Prolific Technology   | 1        | 0.45%   |
| Oki Data              | 1        | 0.45%   |
| ARGOX                 | 1        | 0.45%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Seiko Epson ET-2600 Series                   | 9        | 3.95%   |
| Seiko Epson L365 Series                      | 8        | 3.51%   |
| HP DeskJet 2130 series                       | 8        | 3.51%   |
| Seiko Epson ET-2710 Series                   | 7        | 3.07%   |
| HP Ink Tank Wireless 410 series              | 7        | 3.07%   |
| Canon G3010 series                           | 7        | 3.07%   |
| Seiko Epson L355 Series                      | 6        | 2.63%   |
| HP DeskJet 2700 series                       | 6        | 2.63%   |
| Samsung M2070 Series                         | 5        | 2.19%   |
| HP LaserJet P1005                            | 5        | 2.19%   |
| HP DeskJet F4100 Printer series              | 5        | 2.19%   |
| HP Deskjet 3050 J610 series                  | 5        | 2.19%   |
| HP DeskJet 2600 series                       | 5        | 2.19%   |
| HP Deskjet 2540 series                       | 5        | 2.19%   |
| HP Deskjet 2050 J510                         | 5        | 2.19%   |
| Samsung SCX-4200 series                      | 4        | 1.75%   |
| HP Deskjet F4400 series                      | 4        | 1.75%   |
| HP DeskJet 3630 series                       | 4        | 1.75%   |
| Seiko Epson XP-240 Series                    | 3        | 1.32%   |
| Seiko Epson L375 Series                      | 3        | 1.32%   |
| Seiko Epson L360 Series                      | 3        | 1.32%   |
| Seiko Epson L3110 Series                     | 3        | 1.32%   |
| Samsung SCX-3200 Series                      | 3        | 1.32%   |
| Samsung M2020 Series                         | 3        | 1.32%   |
| HP LaserJet Professional P1102w              | 3        | 1.32%   |
| HP LaserJet 1020                             | 3        | 1.32%   |
| HP DeskJet F4200 series                      | 3        | 1.32%   |
| Brother HL-1200 series                       | 3        | 1.32%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 2        | 0.88%   |
| Seiko Epson L210 Series                      | 2        | 0.88%   |
| Seiko Epson L120 Series                      | 2        | 0.88%   |
| Seiko Epson ET-2810 Series                   | 2        | 0.88%   |
| Samsung SCX-3400 Series                      | 2        | 0.88%   |
| QinHeng CH340S                               | 2        | 0.88%   |
| HP PSC-1315/PSC-1317                         | 2        | 0.88%   |
| HP Printing Support                          | 2        | 0.88%   |
| HP LaserJet 1018                             | 2        | 0.88%   |
| HP Deskjet 4620 series                       | 2        | 0.88%   |
| HP DeskJet 1110 series                       | 2        | 0.88%   |
| Canon PIXMA MG3000 series                    | 2        | 0.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Hewlett-Packard | 6        | 37.5%   |
| Canon           | 6        | 37.5%   |
| Seiko Epson     | 2        | 12.5%   |
| Plustek         | 1        | 6.25%   |
| Mustek Systems  | 1        | 6.25%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| HP ScanJet 2400c                                        | 4        | 25%     |
| Canon CanoScan LIDE 25                                  | 4        | 25%     |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1        | 6.25%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1        | 6.25%   |
| Plustek 1200dpi USB Scanner                             | 1        | 6.25%   |
| Mustek Systems ScanExpress 1200 UB                      | 1        | 6.25%   |
| HP ScanJet G4050                                        | 1        | 6.25%   |
| HP ScanJet 3800c                                        | 1        | 6.25%   |
| Canon CanoScan LiDE 210                                 | 1        | 6.25%   |
| Canon CanoScan LiDE 110                                 | 1        | 6.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 238      | 30.16%  |
| Generalplus Technology        | 63       | 7.98%   |
| Microsoft                     | 53       | 6.72%   |
| Microdia                      | 47       | 5.96%   |
| Samsung Electronics           | 44       | 5.58%   |
| Z-Star Microelectronics       | 39       | 4.94%   |
| Aveo Technology               | 28       | 3.55%   |
| GEMBIRD                       | 21       | 2.66%   |
| Cubeternet                    | 18       | 2.28%   |
| Sunplus Innovation Technology | 17       | 2.15%   |
| Jieli Technology              | 17       | 2.15%   |
| Chicony Electronics           | 17       | 2.15%   |
| Pixart Imaging                | 13       | 1.65%   |
| Genesys Logic                 | 10       | 1.27%   |
| Apple                         | 10       | 1.27%   |
| LG Electronics                | 9        | 1.14%   |
| Realtek Semiconductor         | 8        | 1.01%   |
| Arkmicro Technologies         | 8        | 1.01%   |
| Alcor Micro                   | 8        | 1.01%   |
| KYE Systems (Mouse Systems)   | 7        | 0.89%   |
| Hewlett-Packard               | 7        | 0.89%   |
| Bison Electronics             | 7        | 0.89%   |
| SunplusIT                     | 6        | 0.76%   |
| Philips (or NXP)              | 6        | 0.76%   |
| MacroSilicon                  | 6        | 0.76%   |
| Huawei Technologies           | 5        | 0.63%   |
| A4Tech                        | 5        | 0.63%   |
| Sunplus Technology            | 4        | 0.51%   |
| Sonix Technology              | 4        | 0.51%   |
| Lenovo                        | 4        | 0.51%   |
| Asuscom Network               | 4        | 0.51%   |
| Unknown                       | 3        | 0.38%   |
| Silicon Motion                | 3        | 0.38%   |
| IMC Networks                  | 3        | 0.38%   |
| GenesysLogic Technology       | 3        | 0.38%   |
| Creative Technology           | 3        | 0.38%   |
| ARC International             | 3        | 0.38%   |
| ALi                           | 3        | 0.38%   |
| Xiongmai                      | 2        | 0.25%   |
| WCM_USB                       | 2        | 0.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 85       | 10.73%  |
| Logitech HD Pro Webcam C920              | 54       | 6.82%   |
| Samsung Galaxy series, misc. (MTP mode)  | 43       | 5.43%   |
| Generalplus GENERAL WEBCAM               | 42       | 5.3%    |
| Logitech C922 Pro Stream Webcam          | 24       | 3.03%   |
| GEMBIRD USB2.0 PC CAMERA                 | 19       | 2.4%    |
| Jieli USB PHY 2.0                        | 17       | 2.15%   |
| Generalplus 808 Camera #9 (web-cam mode) | 17       | 2.15%   |
| Z-Star Venus USB2.0 Camera               | 16       | 2.02%   |
| Microdia Integrated Camera               | 14       | 1.77%   |
| Logitech BRIO Ultra HD Webcam            | 14       | 1.77%   |
| Aveo USB2.0 Camera                       | 14       | 1.77%   |
| Microdia USB 2.0 Camera                  | 13       | 1.64%   |
| Logitech Webcam C925e                    | 12       | 1.52%   |
| Logitech HD Webcam C525                  | 11       | 1.39%   |
| Logitech C920 PRO HD Webcam              | 11       | 1.39%   |
| Sunplus MTD Camera                       | 10       | 1.26%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro     | 10       | 1.26%   |
| Microsoft LifeCam VX-800                 | 10       | 1.26%   |
| Microsoft LifeCam VX-500 [1357]          | 10       | 1.26%   |
| Z-Star A4 TECH USB2.0 PC Camera E        | 8        | 1.01%   |
| Microsoft LifeCam HD-3000                | 8        | 1.01%   |
| Microsoft LifeCam Cinema                 | 8        | 1.01%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 8        | 1.01%   |
| Microsoft LifeCam VX-2000                | 7        | 0.88%   |
| Microdia Webcam Vitade AF                | 7        | 0.88%   |
| Cubeternet GL-UPC822 UVC WebCam          | 7        | 0.88%   |
| Chicony HP Webcam                        | 7        | 0.88%   |
| Aveo Camera                              | 7        | 0.88%   |
| Philips (or NXP) Webcam SPC530NC         | 6        | 0.76%   |
| Microsoft LifeCam HD-5000                | 6        | 0.76%   |
| Logitech Logi Webcam C920e               | 6        | 0.76%   |
| Bison BisonCam, NB Pro                   | 6        | 0.76%   |
| Microdia Sonix USB 2.0 Camera            | 5        | 0.63%   |
| MacroSilicon USB Video                   | 5        | 0.63%   |
| Huawei UVC Camera                        | 5        | 0.63%   |
| HP Webcam HD 2300                        | 5        | 0.63%   |
| Cubeternet USB2.0 Camera                 | 5        | 0.63%   |
| Chicony HP High Definition 1MP Webcam    | 5        | 0.63%   |
| Aveo UVC camera (Bresser microscope)     | 5        | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| LighTuning Technology | 1        | 33.33%  |
| Futronic Technology   | 1        | 33.33%  |
| Dell                  | 1        | 33.33%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| LighTuning Fingerprint Sensor                  | 1        | 33.33%  |
| Futronic FS81 Fingerprint Scanner Module       | 1        | 33.33%  |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 33.33%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Gemalto (was Gemplus)             | 15       | 38.46%  |
| Giesecke & Devrient               | 5        | 12.82%  |
| Alcor Micro                       | 4        | 10.26%  |
| SCM Microsystems                  | 3        | 7.69%   |
| Chicony Electronics               | 3        | 7.69%   |
| Watchdata                         | 2        | 5.13%   |
| OmniKey                           | 2        | 5.13%   |
| Castles Technology                | 2        | 5.13%   |
| VASCO Data Security International | 1        | 2.56%   |
| Realtek Semiconductor             | 1        | 2.56%   |
| Aladdin Knowledge Systems         | 1        | 2.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader               | 14       | 35.9%   |
| Giesecke & Devrient StarSign CUT S                              | 4        | 10.26%  |
| Alcor Micro AU9540 Smartcard Reader                             | 4        | 10.26%  |
| Chicony Electronics HP Skylab USB Smartcard Keyboard            | 3        | 7.69%   |
| Watchdata USB Key                                               | 2        | 5.13%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader          | 2        | 5.13%   |
| OmniKey CardMan 3021 / 3121                                     | 2        | 5.13%   |
| Castles Technology EZCCID Smart Card Reader                     | 2        | 5.13%   |
| VASCO Data Security International Digipass 905 SmartCard Reader | 1        | 2.56%   |
| SCM Microsystems SCR35xx Smart Card Reader                      | 1        | 2.56%   |
| Realtek Semiconductor Smart Card Reader Interface               | 1        | 2.56%   |
| Giesecke & Devrient StarSign CUT                                | 1        | 2.56%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                | 1        | 2.56%   |
| Aladdin Knowledge Systems Token JC                              | 1        | 2.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 4382     | 84.94%  |
| 1     | 687      | 13.32%  |
| 2     | 63       | 1.22%   |
| 3     | 18       | 0.35%   |
| 4     | 8        | 0.16%   |
| 6     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 331      | 38.9%   |
| Net/wireless             | 217      | 25.5%   |
| Communication controller | 65       | 7.64%   |
| Unassigned class         | 59       | 6.93%   |
| Sound                    | 29       | 3.41%   |
| Multimedia controller    | 29       | 3.41%   |
| Chipcard                 | 26       | 3.06%   |
| Camera                   | 19       | 2.23%   |
| Modem                    | 17       | 2%      |
| Net/ethernet             | 13       | 1.53%   |
| Bluetooth                | 9        | 1.06%   |
| Storage/ide              | 8        | 0.94%   |
| Storage/raid             | 7        | 0.82%   |
| Network                  | 7        | 0.82%   |
| Card reader              | 5        | 0.59%   |
| Storage/nvme             | 2        | 0.24%   |
| Firewire controller      | 2        | 0.24%   |
| Wireless                 | 1        | 0.12%   |
| Video                    | 1        | 0.12%   |
| Unclassified device      | 1        | 0.12%   |
| Storage                  | 1        | 0.12%   |
| Fingerprint reader       | 1        | 0.12%   |
| Dvb card                 | 1        | 0.12%   |

