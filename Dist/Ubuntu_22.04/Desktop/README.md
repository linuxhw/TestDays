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

Total: 1222

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire TC-605               | [5ff2a41fcd](https://linux-hardware.org/?probe=5ff2a41fcd) | Sep 01, 2022 |
| Dell          | 0R6PCT A01                  | [02af50752e](https://linux-hardware.org/?probe=02af50752e) | Sep 01, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | [f113f959b7](https://linux-hardware.org/?probe=f113f959b7) | Sep 01, 2022 |
| Acer          | Aspire TC-605               | [fdc6b95d8b](https://linux-hardware.org/?probe=fdc6b95d8b) | Sep 01, 2022 |
| Dell          | 042P49 A02                  | [3b1c07d561](https://linux-hardware.org/?probe=3b1c07d561) | Sep 01, 2022 |
| Intel         | D34010WYB H14771-304        | [47d9609ba8](https://linux-hardware.org/?probe=47d9609ba8) | Sep 01, 2022 |
| Intel         | D34010WYB H14771-304        | [fd34481bf8](https://linux-hardware.org/?probe=fd34481bf8) | Sep 01, 2022 |
| Gigabyte      | H81M-WW                     | [2a56f256a3](https://linux-hardware.org/?probe=2a56f256a3) | Sep 01, 2022 |
| Gigabyte      | X150M-PRO ECC-CF            | [6db003ed3a](https://linux-hardware.org/?probe=6db003ed3a) | Sep 01, 2022 |
| Gigabyte      | X150M-PRO ECC-CF            | [2f21cd30ff](https://linux-hardware.org/?probe=2f21cd30ff) | Sep 01, 2022 |
| Lenovo        | 36D5 SDK0J40700 WIN 3258... | [87dfd12899](https://linux-hardware.org/?probe=87dfd12899) | Sep 01, 2022 |
| MSI           | B450M-A PRO MAX             | [6462d2370f](https://linux-hardware.org/?probe=6462d2370f) | Aug 31, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | [12033c4a8b](https://linux-hardware.org/?probe=12033c4a8b) | Aug 31, 2022 |
| HP            | 1906                        | [a23cef9946](https://linux-hardware.org/?probe=a23cef9946) | Aug 31, 2022 |
| HP            | 81B4                        | [b81985e04e](https://linux-hardware.org/?probe=b81985e04e) | Aug 31, 2022 |
| Pegatron      | 2AB6                        | [c4ca3989e0](https://linux-hardware.org/?probe=c4ca3989e0) | Aug 31, 2022 |
| Gigabyte      | P85-D3                      | [71ce0b707c](https://linux-hardware.org/?probe=71ce0b707c) | Aug 31, 2022 |
| ASUSTek       | Z170-K                      | [544582fd23](https://linux-hardware.org/?probe=544582fd23) | Aug 31, 2022 |
| OEM           | Intel H81                   | [4b45e6dc61](https://linux-hardware.org/?probe=4b45e6dc61) | Aug 31, 2022 |
| MSI           | Z390-A PRO                  | [368eff381c](https://linux-hardware.org/?probe=368eff381c) | Aug 31, 2022 |
| ASRock        | Z77 Pro4-M                  | [d7c9a106e7](https://linux-hardware.org/?probe=d7c9a106e7) | Aug 31, 2022 |
| ASRock        | B550M-ITX/ac                | [685e484cbd](https://linux-hardware.org/?probe=685e484cbd) | Aug 31, 2022 |
| ASUSTek       | PRIME X299-DELUXE           | [a76390d5fc](https://linux-hardware.org/?probe=a76390d5fc) | Aug 31, 2022 |
| Foxconn       | 2AAF                        | [a23b1b0822](https://linux-hardware.org/?probe=a23b1b0822) | Aug 30, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [98e0a08e65](https://linux-hardware.org/?probe=98e0a08e65) | Aug 30, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [2fd4ef02b3](https://linux-hardware.org/?probe=2fd4ef02b3) | Aug 30, 2022 |
| ASRockRack    | ROMED8-2T                   | [a034a83f72](https://linux-hardware.org/?probe=a034a83f72) | Aug 30, 2022 |
| Dell          | 0J3C2F A00                  | [276ac60713](https://linux-hardware.org/?probe=276ac60713) | Aug 30, 2022 |
| HP            | 2B38                        | [40428ed239](https://linux-hardware.org/?probe=40428ed239) | Aug 30, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [a01239fd83](https://linux-hardware.org/?probe=a01239fd83) | Aug 29, 2022 |
| Lenovo        | Bantry CRB SDK0J40709 WI... | [4ba4105869](https://linux-hardware.org/?probe=4ba4105869) | Aug 29, 2022 |
| HP            | 304Ah                       | [3f370524f3](https://linux-hardware.org/?probe=3f370524f3) | Aug 29, 2022 |
| HP            | 18E5                        | [c40ab0e3e3](https://linux-hardware.org/?probe=c40ab0e3e3) | Aug 29, 2022 |
| HP            | ProLiant MicroServer Gen... | [b613af8e42](https://linux-hardware.org/?probe=b613af8e42) | Aug 29, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [2d013c60ed](https://linux-hardware.org/?probe=2d013c60ed) | Aug 29, 2022 |
| MSI           | MAG B550 TORPEDO            | [58f0ba95c3](https://linux-hardware.org/?probe=58f0ba95c3) | Aug 29, 2022 |
| ASRock        | A320M-DVS R4.0              | [5140e742a9](https://linux-hardware.org/?probe=5140e742a9) | Aug 29, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [81bc767d5b](https://linux-hardware.org/?probe=81bc767d5b) | Aug 29, 2022 |
| Dell          | 0HY9JP A01                  | [b87b0407d9](https://linux-hardware.org/?probe=b87b0407d9) | Aug 29, 2022 |
| Dell          | 05XGC8 A01                  | [73ac4cc88d](https://linux-hardware.org/?probe=73ac4cc88d) | Aug 29, 2022 |
| Dell          | 0HY9JP A01                  | [fbb579a5d6](https://linux-hardware.org/?probe=fbb579a5d6) | Aug 29, 2022 |
| Dell          | 0HY9JP A00                  | [811e87f60b](https://linux-hardware.org/?probe=811e87f60b) | Aug 28, 2022 |
| Dell          | 0NW6H5 A00                  | [40a706292c](https://linux-hardware.org/?probe=40a706292c) | Aug 28, 2022 |
| ASRock        | B450M Pro4                  | [8f0f345242](https://linux-hardware.org/?probe=8f0f345242) | Aug 28, 2022 |
| MSI           | B450M PRO-M2 MAX            | [5e6e789346](https://linux-hardware.org/?probe=5e6e789346) | Aug 28, 2022 |
| Pegatron      | IPMSB-GS                    | [9edb57e041](https://linux-hardware.org/?probe=9edb57e041) | Aug 28, 2022 |
| ASUSTek       | B85M-E                      | [a0f47aaaa7](https://linux-hardware.org/?probe=a0f47aaaa7) | Aug 28, 2022 |
| Gigabyte      | F2A68HM-S1                  | [420036f4d6](https://linux-hardware.org/?probe=420036f4d6) | Aug 28, 2022 |
| Dell          | 020M3P A00                  | [424ea42e17](https://linux-hardware.org/?probe=424ea42e17) | Aug 28, 2022 |
| Dell          | OptiPlex 3020M              | [84f424cfb7](https://linux-hardware.org/?probe=84f424cfb7) | Aug 28, 2022 |
| Lenovo        | SHARKBAY NOK                | [8571fd0486](https://linux-hardware.org/?probe=8571fd0486) | Aug 27, 2022 |
| HP            | 3647h                       | [c83122d4d4](https://linux-hardware.org/?probe=c83122d4d4) | Aug 27, 2022 |
| Dell          | 0G3HR7 A00                  | [500cf5a2b4](https://linux-hardware.org/?probe=500cf5a2b4) | Aug 27, 2022 |
| Dell          | 0G3HR7 A00                  | [f9671d44ad](https://linux-hardware.org/?probe=f9671d44ad) | Aug 27, 2022 |
| HP            | 18E7                        | [613d55d0e9](https://linux-hardware.org/?probe=613d55d0e9) | Aug 27, 2022 |
| Intel         | DH87RL AAG74240-401         | [814718547c](https://linux-hardware.org/?probe=814718547c) | Aug 27, 2022 |
| MSI           | MPG Z690 FORCE WIFI         | [e476312c10](https://linux-hardware.org/?probe=e476312c10) | Aug 27, 2022 |
| Dell          | 020M3P A00                  | [fea059fea0](https://linux-hardware.org/?probe=fea059fea0) | Aug 27, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [43fdfb3cf8](https://linux-hardware.org/?probe=43fdfb3cf8) | Aug 27, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [a1f434a97c](https://linux-hardware.org/?probe=a1f434a97c) | Aug 27, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [04474401fc](https://linux-hardware.org/?probe=04474401fc) | Aug 26, 2022 |
| ASRock        | B450M-HDV R4.0              | [a180ab604a](https://linux-hardware.org/?probe=a180ab604a) | Aug 26, 2022 |
| Foxconn       | A6VMX 0A                    | [f31fcbf60d](https://linux-hardware.org/?probe=f31fcbf60d) | Aug 26, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | [d0e8962ad5](https://linux-hardware.org/?probe=d0e8962ad5) | Aug 26, 2022 |
| HP            | 8299                        | [37b30a10c2](https://linux-hardware.org/?probe=37b30a10c2) | Aug 26, 2022 |
| Intel         | D2550MUD2 AAG81497-700      | [a181512016](https://linux-hardware.org/?probe=a181512016) | Aug 26, 2022 |
| Biostar       | B660MX-E                    | [4fa9d132c2](https://linux-hardware.org/?probe=4fa9d132c2) | Aug 26, 2022 |
| ASUSTek       | P8Z68-V LE                  | [9839e8eeff](https://linux-hardware.org/?probe=9839e8eeff) | Aug 26, 2022 |
| ASUSTek       | P8H77-V LE                  | [4bd2fabdc7](https://linux-hardware.org/?probe=4bd2fabdc7) | Aug 26, 2022 |
| Intel         | DQ965GF AAD41676-601        | [a163a7fc6d](https://linux-hardware.org/?probe=a163a7fc6d) | Aug 25, 2022 |
| Foxconn       | P35A01                      | [fa220f1ce6](https://linux-hardware.org/?probe=fa220f1ce6) | Aug 25, 2022 |
| Dell          | 0YXT71 A03                  | [176c458f3a](https://linux-hardware.org/?probe=176c458f3a) | Aug 25, 2022 |
| Gigabyte      | X58A-UD3R                   | [3ab6c59d4f](https://linux-hardware.org/?probe=3ab6c59d4f) | Aug 25, 2022 |
| Foxconn       | 2ABF                        | [b19844ee21](https://linux-hardware.org/?probe=b19844ee21) | Aug 25, 2022 |
| Dell          | 0GY6Y8 A03                  | [cb1949a84c](https://linux-hardware.org/?probe=cb1949a84c) | Aug 25, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [a380176da4](https://linux-hardware.org/?probe=a380176da4) | Aug 25, 2022 |
| ECS           | Asterope3                   | [624bd10b6f](https://linux-hardware.org/?probe=624bd10b6f) | Aug 24, 2022 |
| Dell          | 073MMW A03                  | [b41e0fcad5](https://linux-hardware.org/?probe=b41e0fcad5) | Aug 24, 2022 |
| ASUSTek       | PRIME A320M-K               | [a096217ea3](https://linux-hardware.org/?probe=a096217ea3) | Aug 24, 2022 |
| ASUSTek       | H61M-K                      | [26c9be116e](https://linux-hardware.org/?probe=26c9be116e) | Aug 24, 2022 |
| HP            | 1905                        | [6693a2b3c7](https://linux-hardware.org/?probe=6693a2b3c7) | Aug 24, 2022 |
| Dell          | 0F5C5X A00                  | [5e62f9adde](https://linux-hardware.org/?probe=5e62f9adde) | Aug 24, 2022 |
| Dell          | 0200DY A03                  | [9da770b898](https://linux-hardware.org/?probe=9da770b898) | Aug 24, 2022 |
| Gigabyte      | GA-MA770T-UD3               | [4ed5107048](https://linux-hardware.org/?probe=4ed5107048) | Aug 24, 2022 |
| Acer          | Predator G3620              | [b79ed7b47b](https://linux-hardware.org/?probe=b79ed7b47b) | Aug 23, 2022 |
| ASUSTek       | M5A97 R2.0                  | [fdc1bb0c75](https://linux-hardware.org/?probe=fdc1bb0c75) | Aug 23, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [6e5a434d0d](https://linux-hardware.org/?probe=6e5a434d0d) | Aug 23, 2022 |
| Dell          | 0WR7PY A03                  | [1dd7e73006](https://linux-hardware.org/?probe=1dd7e73006) | Aug 23, 2022 |
| Dell          | 0WR7PY A03                  | [071889c1b4](https://linux-hardware.org/?probe=071889c1b4) | Aug 23, 2022 |
| MSI           | B450-A PRO MAX              | [47257deb9b](https://linux-hardware.org/?probe=47257deb9b) | Aug 23, 2022 |
| ASRock        | G41M-VS3                    | [97772a7cb6](https://linux-hardware.org/?probe=97772a7cb6) | Aug 23, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [fca17b512f](https://linux-hardware.org/?probe=fca17b512f) | Aug 23, 2022 |
| Pegatron      | E60                         | [c1aba90f51](https://linux-hardware.org/?probe=c1aba90f51) | Aug 23, 2022 |
| Gigabyte      | 970A-DS3P                   | [79bc344d85](https://linux-hardware.org/?probe=79bc344d85) | Aug 23, 2022 |
| ASUSTek       | P5Q-PRO                     | [622dac7a01](https://linux-hardware.org/?probe=622dac7a01) | Aug 22, 2022 |
| ASUSTek       | PRIME H410M-E               | [5270930555](https://linux-hardware.org/?probe=5270930555) | Aug 22, 2022 |
| ASRock        | A320M-HDV R4.0              | [3cca56dc74](https://linux-hardware.org/?probe=3cca56dc74) | Aug 22, 2022 |
| Dell          | 0J3C2F A00                  | [0ff24f8d0a](https://linux-hardware.org/?probe=0ff24f8d0a) | Aug 22, 2022 |
| Intel         | H61                         | [f2a42b45ca](https://linux-hardware.org/?probe=f2a42b45ca) | Aug 22, 2022 |
| ASUSTek       | A78M-E                      | [594e3ae5f4](https://linux-hardware.org/?probe=594e3ae5f4) | Aug 22, 2022 |
| MSI           | 2A9C                        | [4f15bcded6](https://linux-hardware.org/?probe=4f15bcded6) | Aug 22, 2022 |
| ASUSTek       | P5B SE                      | [f8291aad0a](https://linux-hardware.org/?probe=f8291aad0a) | Aug 22, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [a332f284ab](https://linux-hardware.org/?probe=a332f284ab) | Aug 22, 2022 |
| Dell          | 0427JK A00                  | [8f6a2c8d0b](https://linux-hardware.org/?probe=8f6a2c8d0b) | Aug 22, 2022 |
| Dell          | 0PC5F7 A01                  | [141b155ee9](https://linux-hardware.org/?probe=141b155ee9) | Aug 22, 2022 |
| Dell          | 0T1D10 A01                  | [8c4bf9344a](https://linux-hardware.org/?probe=8c4bf9344a) | Aug 21, 2022 |
| Shuttle       | FS81                        | [4c3be1b1a6](https://linux-hardware.org/?probe=4c3be1b1a6) | Aug 21, 2022 |
| HP            | 3047h                       | [4b36895c4f](https://linux-hardware.org/?probe=4b36895c4f) | Aug 21, 2022 |
| Unknown       | X79A                        | [5c545069e2](https://linux-hardware.org/?probe=5c545069e2) | Aug 21, 2022 |
| ASUSTek       | B150M-A                     | [0dac247b92](https://linux-hardware.org/?probe=0dac247b92) | Aug 21, 2022 |
| Biostar       | G31-M7 TE                   | [aaacebef4a](https://linux-hardware.org/?probe=aaacebef4a) | Aug 21, 2022 |
| OEM           | G41 775 ICH7 8712           | [71bfa72a22](https://linux-hardware.org/?probe=71bfa72a22) | Aug 21, 2022 |
| Dell          | 09M8Y8 A02                  | [0fbe4d3ee0](https://linux-hardware.org/?probe=0fbe4d3ee0) | Aug 21, 2022 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | [8047eeecb4](https://linux-hardware.org/?probe=8047eeecb4) | Aug 20, 2022 |
| ASRock        | H310CM-DVS                  | [17f6682bf3](https://linux-hardware.org/?probe=17f6682bf3) | Aug 20, 2022 |
| MSI           | A55M-E33                    | [80d29c4f23](https://linux-hardware.org/?probe=80d29c4f23) | Aug 20, 2022 |
| ASUSTek       | Maximus III GENE            | [9cbc8d9f88](https://linux-hardware.org/?probe=9cbc8d9f88) | Aug 20, 2022 |
| Supermicro    | X10DRT-PT                   | [748c44c44c](https://linux-hardware.org/?probe=748c44c44c) | Aug 20, 2022 |
| ASUSTek       | A88X-PRO                    | [f3eacd2075](https://linux-hardware.org/?probe=f3eacd2075) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1f85d6a1b9](https://linux-hardware.org/?probe=1f85d6a1b9) | Aug 20, 2022 |
| MSI           | Boston                      | [4a10f122a2](https://linux-hardware.org/?probe=4a10f122a2) | Aug 19, 2022 |
| Dell          | 0RY206                      | [faf3aaf7b6](https://linux-hardware.org/?probe=faf3aaf7b6) | Aug 19, 2022 |
| HP            | 8184 X4                     | [2dcf653d17](https://linux-hardware.org/?probe=2dcf653d17) | Aug 19, 2022 |
| HP            | 8184 X4                     | [080aadafd7](https://linux-hardware.org/?probe=080aadafd7) | Aug 19, 2022 |
| ASUSTek       | F2A55                       | [fbeb34e877](https://linux-hardware.org/?probe=fbeb34e877) | Aug 19, 2022 |
| Dell          | 0WR7PY A03                  | [81f6e6a93d](https://linux-hardware.org/?probe=81f6e6a93d) | Aug 19, 2022 |
| HP            | 1497                        | [580e1a6efe](https://linux-hardware.org/?probe=580e1a6efe) | Aug 19, 2022 |
| MSI           | Z77A-G45                    | [ff3c734303](https://linux-hardware.org/?probe=ff3c734303) | Aug 19, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | [d39161dc13](https://linux-hardware.org/?probe=d39161dc13) | Aug 19, 2022 |
| ASUSTek       | A88XM-E                     | [04d716a25d](https://linux-hardware.org/?probe=04d716a25d) | Aug 19, 2022 |
| Gigabyte      | B450 GAMING X               | [699e2fb2ee](https://linux-hardware.org/?probe=699e2fb2ee) | Aug 19, 2022 |
| LattePanda    | Delta CDJQ-BI-7-S70GR200... | [78e2d2b06a](https://linux-hardware.org/?probe=78e2d2b06a) | Aug 19, 2022 |
| LattePanda    | Delta CDJQ-BI-7-S70GR200... | [8720690695](https://linux-hardware.org/?probe=8720690695) | Aug 19, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [ccea67d380](https://linux-hardware.org/?probe=ccea67d380) | Aug 19, 2022 |
| ASUSTek       | X99-A/USB                   | [4bfbe43f55](https://linux-hardware.org/?probe=4bfbe43f55) | Aug 19, 2022 |
| ASUSTek       | X99-A/USB                   | [b723cf0362](https://linux-hardware.org/?probe=b723cf0362) | Aug 19, 2022 |
| Intel         | X79M-S                      | [b6746f7b8d](https://linux-hardware.org/?probe=b6746f7b8d) | Aug 18, 2022 |
| Acer          | Veriton X2631G V:1.0        | [de98920808](https://linux-hardware.org/?probe=de98920808) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6d2502dc07](https://linux-hardware.org/?probe=6d2502dc07) | Aug 18, 2022 |
| Intel         | D54250WYK H13922-302        | [ba78bd360c](https://linux-hardware.org/?probe=ba78bd360c) | Aug 18, 2022 |
| Gigabyte      | Z370 HD3P-CF                | [410c71e7ef](https://linux-hardware.org/?probe=410c71e7ef) | Aug 18, 2022 |
| MSI           | 760GM-P23                   | [42245b8fc8](https://linux-hardware.org/?probe=42245b8fc8) | Aug 18, 2022 |
| ASUSTek       | Z97-E                       | [aa95967c03](https://linux-hardware.org/?probe=aa95967c03) | Aug 18, 2022 |
| MSI           | MPG Z690 FORCE WIFI         | [df94820d80](https://linux-hardware.org/?probe=df94820d80) | Aug 18, 2022 |
| ASUSTek       | ProArt B660-CREATOR D4      | [f9f180ac3a](https://linux-hardware.org/?probe=f9f180ac3a) | Aug 18, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | [bd7c6f361d](https://linux-hardware.org/?probe=bd7c6f361d) | Aug 18, 2022 |
| Intel         | Unknown                     | [23f3bdae8a](https://linux-hardware.org/?probe=23f3bdae8a) | Aug 18, 2022 |
| Dell          | 0FDY5C A00                  | [4cd1658b87](https://linux-hardware.org/?probe=4cd1658b87) | Aug 17, 2022 |
| ASUSTek       | P7H55-M                     | [7596762e80](https://linux-hardware.org/?probe=7596762e80) | Aug 17, 2022 |
| Foxconn       | 2ABF                        | [eaea01215e](https://linux-hardware.org/?probe=eaea01215e) | Aug 17, 2022 |
| Dell          | 00V62H A01                  | [34b4c61308](https://linux-hardware.org/?probe=34b4c61308) | Aug 17, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [8911aeaaaf](https://linux-hardware.org/?probe=8911aeaaaf) | Aug 17, 2022 |
| Dell          | 0RY206                      | [5dd1ce5c96](https://linux-hardware.org/?probe=5dd1ce5c96) | Aug 17, 2022 |
| Gigabyte      | Z590 UD AC                  | [5ee622e6da](https://linux-hardware.org/?probe=5ee622e6da) | Aug 17, 2022 |
| MSI           | MPG Z390M GAMING EDGE AC    | [d81b4dec2a](https://linux-hardware.org/?probe=d81b4dec2a) | Aug 17, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [1ab8003e04](https://linux-hardware.org/?probe=1ab8003e04) | Aug 17, 2022 |
| Acer          | Aspire TC-885 V:1.1         | [2a3c6446e5](https://linux-hardware.org/?probe=2a3c6446e5) | Aug 17, 2022 |
| Acer          | Veriton X2631G V:1.0        | [a7af0ea5e7](https://linux-hardware.org/?probe=a7af0ea5e7) | Aug 17, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | [56ba58f5d0](https://linux-hardware.org/?probe=56ba58f5d0) | Aug 16, 2022 |
| Dell          | 0U880P A00                  | [926c7c752c](https://linux-hardware.org/?probe=926c7c752c) | Aug 16, 2022 |
| Dell          | 0U880P A00                  | [bce1a6b1fd](https://linux-hardware.org/?probe=bce1a6b1fd) | Aug 16, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [ed6155d213](https://linux-hardware.org/?probe=ed6155d213) | Aug 16, 2022 |
| ASUSTek       | P7H55-M                     | [bbcdb246aa](https://linux-hardware.org/?probe=bbcdb246aa) | Aug 16, 2022 |
| HP            | 1497                        | [c0b6759020](https://linux-hardware.org/?probe=c0b6759020) | Aug 16, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | [171a797c22](https://linux-hardware.org/?probe=171a797c22) | Aug 16, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | [f882fcbe3a](https://linux-hardware.org/?probe=f882fcbe3a) | Aug 16, 2022 |
| Intel         | B75                         | [8eb918ea53](https://linux-hardware.org/?probe=8eb918ea53) | Aug 16, 2022 |
| ASUSTek       | PRIME B450-PLUS             | [d01ce7811a](https://linux-hardware.org/?probe=d01ce7811a) | Aug 15, 2022 |
| Gigabyte      | B75M-D3V                    | [cdea2e0afd](https://linux-hardware.org/?probe=cdea2e0afd) | Aug 15, 2022 |
| Gigabyte      | B75M-D3V                    | [87f8cc8553](https://linux-hardware.org/?probe=87f8cc8553) | Aug 15, 2022 |
| ASRock        | H55M                        | [8d0bd0d2d2](https://linux-hardware.org/?probe=8d0bd0d2d2) | Aug 15, 2022 |
| MSI           | MAG B560 TORPEDO            | [4a2ce50049](https://linux-hardware.org/?probe=4a2ce50049) | Aug 15, 2022 |
| ASUSTek       | Z87-PLUS                    | [63d41691ef](https://linux-hardware.org/?probe=63d41691ef) | Aug 15, 2022 |
| HP            | 1495                        | [34b69b08b1](https://linux-hardware.org/?probe=34b69b08b1) | Aug 15, 2022 |
| MSI           | A320M-A PRO MAX             | [bf211d4e64](https://linux-hardware.org/?probe=bf211d4e64) | Aug 15, 2022 |
| HP            | 1495                        | [1ace6c9868](https://linux-hardware.org/?probe=1ace6c9868) | Aug 15, 2022 |
| HP            | 1495                        | [af820eee7e](https://linux-hardware.org/?probe=af820eee7e) | Aug 15, 2022 |
| HP            | 1495                        | [6db4307c50](https://linux-hardware.org/?probe=6db4307c50) | Aug 15, 2022 |
| HP            | 1495                        | [c122ce06ab](https://linux-hardware.org/?probe=c122ce06ab) | Aug 15, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [3d2bd6d842](https://linux-hardware.org/?probe=3d2bd6d842) | Aug 15, 2022 |
| HP            | 0B4Ch D                     | [98ea1068a3](https://linux-hardware.org/?probe=98ea1068a3) | Aug 15, 2022 |
| ASUSTek       | P7H55-M                     | [5106d4eda8](https://linux-hardware.org/?probe=5106d4eda8) | Aug 15, 2022 |
| Lenovo        | 3098 0B98401 WIN            | [769802c689](https://linux-hardware.org/?probe=769802c689) | Aug 15, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [e322338b55](https://linux-hardware.org/?probe=e322338b55) | Aug 15, 2022 |
| MACHINIST     | X99-K9 V2.0                 | [9193936bdf](https://linux-hardware.org/?probe=9193936bdf) | Aug 15, 2022 |
| ASUSTek       | M3A79-T DELUXE              | [6d42c46a57](https://linux-hardware.org/?probe=6d42c46a57) | Aug 15, 2022 |
| ASUSTek       | TUF H370-PRO GAMING         | [5cd8255ceb](https://linux-hardware.org/?probe=5cd8255ceb) | Aug 15, 2022 |
| HP            | 2AFB                        | [7d4ca16239](https://linux-hardware.org/?probe=7d4ca16239) | Aug 15, 2022 |
| Dell          | 0RY206                      | [b6288fd6c7](https://linux-hardware.org/?probe=b6288fd6c7) | Aug 14, 2022 |
| Dell          | 0J3C2F A00                  | [3574cfa833](https://linux-hardware.org/?probe=3574cfa833) | Aug 14, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | [3bdf8d4582](https://linux-hardware.org/?probe=3bdf8d4582) | Aug 14, 2022 |
| MSI           | Z170A PC MATE               | [97f14bc24c](https://linux-hardware.org/?probe=97f14bc24c) | Aug 14, 2022 |
| Acer          | Aspire XC-605               | [125a8c791a](https://linux-hardware.org/?probe=125a8c791a) | Aug 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [bd26ce6aa4](https://linux-hardware.org/?probe=bd26ce6aa4) | Aug 14, 2022 |
| ASUSTek       | H61M-A/BR                   | [4443a6c129](https://linux-hardware.org/?probe=4443a6c129) | Aug 14, 2022 |
| ASUSTek       | H61M-A/BR                   | [082a5297bd](https://linux-hardware.org/?probe=082a5297bd) | Aug 14, 2022 |
| Pegatron      | 2A94                        | [81b0cdd377](https://linux-hardware.org/?probe=81b0cdd377) | Aug 14, 2022 |
| ASRock        | B450M Pro4                  | [ac9e2d3187](https://linux-hardware.org/?probe=ac9e2d3187) | Aug 14, 2022 |
| HP            | 1493                        | [e5d0f16bbc](https://linux-hardware.org/?probe=e5d0f16bbc) | Aug 14, 2022 |
| Gigabyte      | Z77M-D3H                    | [15633ed7b1](https://linux-hardware.org/?probe=15633ed7b1) | Aug 14, 2022 |
| ASUSTek       | B85M-G                      | [c92d457cd6](https://linux-hardware.org/?probe=c92d457cd6) | Aug 13, 2022 |
| Dell          | 0KP561                      | [38f01be008](https://linux-hardware.org/?probe=38f01be008) | Aug 13, 2022 |
| Dell          | 0KP561                      | [293f6f95bb](https://linux-hardware.org/?probe=293f6f95bb) | Aug 13, 2022 |
| MSI           | MAG B660M MORTAR WIFI       | [4e1b75908c](https://linux-hardware.org/?probe=4e1b75908c) | Aug 13, 2022 |
| MSI           | MPG Z690 FORCE WIFI         | [73af2996db](https://linux-hardware.org/?probe=73af2996db) | Aug 13, 2022 |
| MSI           | MPG Z690 FORCE WIFI         | [144b7c2cf1](https://linux-hardware.org/?probe=144b7c2cf1) | Aug 13, 2022 |
| Dell          | 04YP6J A01                  | [c402ff86c1](https://linux-hardware.org/?probe=c402ff86c1) | Aug 13, 2022 |
| ASUSTek       | PRIME A320M-K               | [44f3f1991f](https://linux-hardware.org/?probe=44f3f1991f) | Aug 13, 2022 |
| Dell          | 0DFRFW A01                  | [9e59d35488](https://linux-hardware.org/?probe=9e59d35488) | Aug 12, 2022 |
| Dell          | 0KWVT8 A02                  | [248a425322](https://linux-hardware.org/?probe=248a425322) | Aug 12, 2022 |
| Dell          | 0DFRFW A01                  | [4a9c41e3fd](https://linux-hardware.org/?probe=4a9c41e3fd) | Aug 12, 2022 |
| ASRock        | B450M Pro4                  | [57c63e8fb9](https://linux-hardware.org/?probe=57c63e8fb9) | Aug 12, 2022 |
| HP            | 304Ah                       | [bc1242ecf9](https://linux-hardware.org/?probe=bc1242ecf9) | Aug 12, 2022 |
| HP            | 304Ah                       | [82db2a1b27](https://linux-hardware.org/?probe=82db2a1b27) | Aug 12, 2022 |
| Dell          | 07PR60 A02                  | [7ed59c8c10](https://linux-hardware.org/?probe=7ed59c8c10) | Aug 12, 2022 |
| BESSTAR Te... | TH50                        | [03159c112c](https://linux-hardware.org/?probe=03159c112c) | Aug 12, 2022 |
| ASUSTek       | A88X-PRO                    | [b7d681fafd](https://linux-hardware.org/?probe=b7d681fafd) | Aug 12, 2022 |
| ASUSTek       | PRIME A320M-K               | [1f75df3828](https://linux-hardware.org/?probe=1f75df3828) | Aug 12, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [98cc4a3075](https://linux-hardware.org/?probe=98cc4a3075) | Aug 12, 2022 |
| Lenovo        | ThinkCentre A58 76117MG     | [d55fd9912c](https://linux-hardware.org/?probe=d55fd9912c) | Aug 12, 2022 |
| Gigabyte      | Z270-Gaming K3              | [792065e2eb](https://linux-hardware.org/?probe=792065e2eb) | Aug 12, 2022 |
| Gigabyte      | Z270-Gaming K3              | [9f4802971d](https://linux-hardware.org/?probe=9f4802971d) | Aug 12, 2022 |
| Pegatron      | IPMSB-GS                    | [7d2cd4cc35](https://linux-hardware.org/?probe=7d2cd4cc35) | Aug 11, 2022 |
| Pegatron      | IPMSB-GS                    | [7e2bf60517](https://linux-hardware.org/?probe=7e2bf60517) | Aug 11, 2022 |
| Dell          | 04YP6J A01                  | [43257ffabd](https://linux-hardware.org/?probe=43257ffabd) | Aug 11, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | [e5e5d0d3a3](https://linux-hardware.org/?probe=e5e5d0d3a3) | Aug 11, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | [93ecf84dcf](https://linux-hardware.org/?probe=93ecf84dcf) | Aug 11, 2022 |
| Foxconn       | 45GM/45CM/45CM-S            | [a6b418356a](https://linux-hardware.org/?probe=a6b418356a) | Aug 11, 2022 |
| Pegatron      | Benicia                     | [8b8224cb4b](https://linux-hardware.org/?probe=8b8224cb4b) | Aug 11, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | [3cfba5bad8](https://linux-hardware.org/?probe=3cfba5bad8) | Aug 11, 2022 |
| ASUSTek       | M5A78L-M LX/BR              | [c66de39c4c](https://linux-hardware.org/?probe=c66de39c4c) | Aug 11, 2022 |
| ASUSTek       | H170M-PLUS/BR               | [d081204e0a](https://linux-hardware.org/?probe=d081204e0a) | Aug 10, 2022 |
| ASRock        | G41M-VS3                    | [4185ab0f97](https://linux-hardware.org/?probe=4185ab0f97) | Aug 10, 2022 |
| Unknown       | Unknown                     | [dc354e0b4f](https://linux-hardware.org/?probe=dc354e0b4f) | Aug 10, 2022 |
| Lenovo        | SHARKBAY NOK                | [9a77cf2f22](https://linux-hardware.org/?probe=9a77cf2f22) | Aug 10, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [2696ad6f3e](https://linux-hardware.org/?probe=2696ad6f3e) | Aug 10, 2022 |
| ASUSTek       | PRIME B450M-K               | [ed054f1da7](https://linux-hardware.org/?probe=ed054f1da7) | Aug 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e54e09e3cf](https://linux-hardware.org/?probe=e54e09e3cf) | Aug 09, 2022 |
| ASUSTek       | PRIME B450M-A               | [d5ddfb6210](https://linux-hardware.org/?probe=d5ddfb6210) | Aug 09, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5a84fd5a16](https://linux-hardware.org/?probe=5a84fd5a16) | Aug 09, 2022 |
| Dell          | 088DT1 A01                  | [eab28163ce](https://linux-hardware.org/?probe=eab28163ce) | Aug 09, 2022 |
| SHARKBAY      | Unknown                     | [a35fff735f](https://linux-hardware.org/?probe=a35fff735f) | Aug 09, 2022 |
| Gigabyte      | X58A-UD3R                   | [a2a0eab4fb](https://linux-hardware.org/?probe=a2a0eab4fb) | Aug 09, 2022 |
| Gigabyte      | X58A-UD3R                   | [fa0d5bccf4](https://linux-hardware.org/?probe=fa0d5bccf4) | Aug 09, 2022 |
| ASUSTek       | A88XM-E                     | [f496954b96](https://linux-hardware.org/?probe=f496954b96) | Aug 08, 2022 |
| ASRock        | H55M-LE                     | [841c63de14](https://linux-hardware.org/?probe=841c63de14) | Aug 08, 2022 |
| ASRock        | N68-VGS3 FX                 | [18d8a04343](https://linux-hardware.org/?probe=18d8a04343) | Aug 08, 2022 |
| ASUSTek       | A88XM-E                     | [84dcf54ab8](https://linux-hardware.org/?probe=84dcf54ab8) | Aug 08, 2022 |
| MSI           | A320M-A PRO MAX             | [9ee274e581](https://linux-hardware.org/?probe=9ee274e581) | Aug 08, 2022 |
| Lenovo        | MAHOBAY NOK                 | [6018df068b](https://linux-hardware.org/?probe=6018df068b) | Aug 08, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [7b8b4b5616](https://linux-hardware.org/?probe=7b8b4b5616) | Aug 08, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [2d41c9a29f](https://linux-hardware.org/?probe=2d41c9a29f) | Aug 08, 2022 |
| Foxconn       | 2ACA                        | [2ede4f1763](https://linux-hardware.org/?probe=2ede4f1763) | Aug 07, 2022 |
| Alienware     | 0PGRP5 A01                  | [305bf6182f](https://linux-hardware.org/?probe=305bf6182f) | Aug 07, 2022 |
| Gigabyte      | A320M-S2H-CF                | [5ddb15f201](https://linux-hardware.org/?probe=5ddb15f201) | Aug 07, 2022 |
| ASUSTek       | Rampage V EXTREME           | [d04d31476f](https://linux-hardware.org/?probe=d04d31476f) | Aug 07, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [3b8f0ef40a](https://linux-hardware.org/?probe=3b8f0ef40a) | Aug 07, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [61e317887a](https://linux-hardware.org/?probe=61e317887a) | Aug 07, 2022 |
| MSI           | 2A9C                        | [e279622ca6](https://linux-hardware.org/?probe=e279622ca6) | Aug 06, 2022 |
| ASUSTek       | Rampage V EXTREME           | [000a2985cc](https://linux-hardware.org/?probe=000a2985cc) | Aug 06, 2022 |
| Dell          | 0VHWTR A02                  | [61b30cfde0](https://linux-hardware.org/?probe=61b30cfde0) | Aug 06, 2022 |
| Gigabyte      | F2A55M-S1                   | [cf3ed2131f](https://linux-hardware.org/?probe=cf3ed2131f) | Aug 06, 2022 |
| ASUSTek       | B85M-G                      | [616c57c367](https://linux-hardware.org/?probe=616c57c367) | Aug 06, 2022 |
| ASUSTek       | M4A88T-V EVO/USB3           | [cb4144185f](https://linux-hardware.org/?probe=cb4144185f) | Aug 05, 2022 |
| ASUSTek       | M4A88T-V EVO/USB3           | [157246e96d](https://linux-hardware.org/?probe=157246e96d) | Aug 05, 2022 |
| Fujitsu Si... | MS-7504VP-PV                | [03f6cbc20a](https://linux-hardware.org/?probe=03f6cbc20a) | Aug 05, 2022 |
| Gigabyte      | B550 GAMING X V2            | [5e1b4032ae](https://linux-hardware.org/?probe=5e1b4032ae) | Aug 05, 2022 |
| Pegatron      | 2AED                        | [8edd69e862](https://linux-hardware.org/?probe=8edd69e862) | Aug 05, 2022 |
| MSI           | 2A9C                        | [d125bcbfe9](https://linux-hardware.org/?probe=d125bcbfe9) | Aug 05, 2022 |
| Foxconn       | ALOE X3                     | [abcfa46aae](https://linux-hardware.org/?probe=abcfa46aae) | Aug 05, 2022 |
| Gigabyte      | H61M-D2-B3                  | [e477bf9f83](https://linux-hardware.org/?probe=e477bf9f83) | Aug 05, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [e0129903ae](https://linux-hardware.org/?probe=e0129903ae) | Aug 04, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | [eb168cff15](https://linux-hardware.org/?probe=eb168cff15) | Aug 04, 2022 |
| HP            | 3398                        | [447e644ae1](https://linux-hardware.org/?probe=447e644ae1) | Aug 04, 2022 |
| HP            | 3398                        | [07655b848a](https://linux-hardware.org/?probe=07655b848a) | Aug 04, 2022 |
| HP            | 82A2                        | [1db2ba3636](https://linux-hardware.org/?probe=1db2ba3636) | Aug 04, 2022 |
| HP            | 8054                        | [888466c84e](https://linux-hardware.org/?probe=888466c84e) | Aug 04, 2022 |
| Dell          | 0HGFJM A00                  | [b1011ae242](https://linux-hardware.org/?probe=b1011ae242) | Aug 04, 2022 |
| ASUSTek       | PRIME B450M-A               | [fc5ee0d2f9](https://linux-hardware.org/?probe=fc5ee0d2f9) | Aug 04, 2022 |
| Lenovo        | SDK0E50510 WIN              | [e43f32d47e](https://linux-hardware.org/?probe=e43f32d47e) | Aug 04, 2022 |
| Foxconn       | 45GM/45CM/45CM-S            | [3d64e8f950](https://linux-hardware.org/?probe=3d64e8f950) | Aug 04, 2022 |
| MSI           | H110M PRO-VH                | [8bdd8d91db](https://linux-hardware.org/?probe=8bdd8d91db) | Aug 04, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [26a2956fd0](https://linux-hardware.org/?probe=26a2956fd0) | Aug 04, 2022 |
| Lenovo        | 3714 SDK0J40700 WIN 3258... | [e5afdebd04](https://linux-hardware.org/?probe=e5afdebd04) | Aug 03, 2022 |
| Gigabyte      | Z77P-D3                     | [216f67b619](https://linux-hardware.org/?probe=216f67b619) | Aug 03, 2022 |
| Supermicro    | X7DCL                       | [4b841e9401](https://linux-hardware.org/?probe=4b841e9401) | Aug 03, 2022 |
| Dell          | 0KW626                      | [629c1c7800](https://linux-hardware.org/?probe=629c1c7800) | Aug 03, 2022 |
| ASUSTek       | M5A97                       | [e5b05f8e39](https://linux-hardware.org/?probe=e5b05f8e39) | Aug 02, 2022 |
| Acer          | Veriton X2631G V:1.0        | [182bfa1039](https://linux-hardware.org/?probe=182bfa1039) | Aug 02, 2022 |
| HP            | 3047h                       | [a8301b8155](https://linux-hardware.org/?probe=a8301b8155) | Aug 02, 2022 |
| Lenovo        | 314F SDK0Q40112 WIN 3305... | [e906976bea](https://linux-hardware.org/?probe=e906976bea) | Aug 02, 2022 |
| Dell          | 0GY6Y8 A03                  | [bd49c779fa](https://linux-hardware.org/?probe=bd49c779fa) | Aug 02, 2022 |
| Acer          | Predator PO3-620            | [ff0507688f](https://linux-hardware.org/?probe=ff0507688f) | Aug 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | [049607c94a](https://linux-hardware.org/?probe=049607c94a) | Aug 02, 2022 |
| Dell          | 0GY6Y8 A03                  | [09ba22e06b](https://linux-hardware.org/?probe=09ba22e06b) | Aug 02, 2022 |
| Acer          | FIH57                       | [eec3e58c8c](https://linux-hardware.org/?probe=eec3e58c8c) | Aug 02, 2022 |
| Acer          | Veriton X2631G V:1.0        | [e63e46c5a4](https://linux-hardware.org/?probe=e63e46c5a4) | Aug 02, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [42cb82f584](https://linux-hardware.org/?probe=42cb82f584) | Aug 01, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | [8e83e6141d](https://linux-hardware.org/?probe=8e83e6141d) | Aug 01, 2022 |
| Alienware     | 04VWF2 A02                  | [a877f0aa97](https://linux-hardware.org/?probe=a877f0aa97) | Aug 01, 2022 |
| Dell          | 0P096C A01                  | [11bc1115f2](https://linux-hardware.org/?probe=11bc1115f2) | Aug 01, 2022 |
| HP            | 3646h                       | [7988eaa5e3](https://linux-hardware.org/?probe=7988eaa5e3) | Aug 01, 2022 |
| MSI           | MEG X570 UNIFY              | [9be9a3e83b](https://linux-hardware.org/?probe=9be9a3e83b) | Aug 01, 2022 |
| QIYIDA        | X99-H9 V2.0                 | [e1fa8ab12b](https://linux-hardware.org/?probe=e1fa8ab12b) | Aug 01, 2022 |
| ASUSTek       | M2A-VM                      | [4b1dabbf52](https://linux-hardware.org/?probe=4b1dabbf52) | Aug 01, 2022 |
| PCWare        | IPMH61R1                    | [0843909534](https://linux-hardware.org/?probe=0843909534) | Aug 01, 2022 |
| Apple         | Mac-F221BEC8                | [13cbc87486](https://linux-hardware.org/?probe=13cbc87486) | Jul 31, 2022 |
| Gigabyte      | H81M-DS2V                   | [0645ed0b9e](https://linux-hardware.org/?probe=0645ed0b9e) | Jul 31, 2022 |
| Gigabyte      | H81M-DS2V                   | [f5e17ecf3d](https://linux-hardware.org/?probe=f5e17ecf3d) | Jul 31, 2022 |
| PCWare        | IPMH61R1                    | [7da7204a12](https://linux-hardware.org/?probe=7da7204a12) | Jul 31, 2022 |
| HP            | 2AF7                        | [da51487005](https://linux-hardware.org/?probe=da51487005) | Jul 31, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [22b4bcc010](https://linux-hardware.org/?probe=22b4bcc010) | Jul 31, 2022 |
| HP            | 3646h                       | [443cfc9c15](https://linux-hardware.org/?probe=443cfc9c15) | Jul 31, 2022 |
| Gigabyte      | F2A68HM-H                   | [047d3c88ad](https://linux-hardware.org/?probe=047d3c88ad) | Jul 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [16f64b6f1a](https://linux-hardware.org/?probe=16f64b6f1a) | Jul 30, 2022 |
| ASUSTek       | M4N68T-M-LE-V2              | [7cc8e19d03](https://linux-hardware.org/?probe=7cc8e19d03) | Jul 30, 2022 |
| Acer          | FIH57                       | [a6b9d91f36](https://linux-hardware.org/?probe=a6b9d91f36) | Jul 30, 2022 |
| ASRock        | Z390 Extreme4               | [670d8c5f1e](https://linux-hardware.org/?probe=670d8c5f1e) | Jul 30, 2022 |
| Gigabyte      | H81M-HD3                    | [0f83741c2e](https://linux-hardware.org/?probe=0f83741c2e) | Jul 30, 2022 |
| ASRock        | Z390 Extreme4               | [8130877fa3](https://linux-hardware.org/?probe=8130877fa3) | Jul 30, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [f6ecfb2a51](https://linux-hardware.org/?probe=f6ecfb2a51) | Jul 30, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [7ceff6f032](https://linux-hardware.org/?probe=7ceff6f032) | Jul 30, 2022 |
| Alienware     | 0PGRP5 A01                  | [7c0915ec41](https://linux-hardware.org/?probe=7c0915ec41) | Jul 30, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [82d0a7ace6](https://linux-hardware.org/?probe=82d0a7ace6) | Jul 29, 2022 |
| ASRock        | Z97 Pro4                    | [0db03812df](https://linux-hardware.org/?probe=0db03812df) | Jul 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | [3c18081f88](https://linux-hardware.org/?probe=3c18081f88) | Jul 29, 2022 |
| HP            | 1497                        | [1f72cc333a](https://linux-hardware.org/?probe=1f72cc333a) | Jul 29, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [51893f2237](https://linux-hardware.org/?probe=51893f2237) | Jul 29, 2022 |
| Intel         | H61                         | [7bb7deaca9](https://linux-hardware.org/?probe=7bb7deaca9) | Jul 29, 2022 |
| Gigabyte      | Z170XP-SLI-CF               | [5a12531bf9](https://linux-hardware.org/?probe=5a12531bf9) | Jul 29, 2022 |
| ASUSTek       | P5G41T-M LX2/BR             | [e84f999c94](https://linux-hardware.org/?probe=e84f999c94) | Jul 29, 2022 |
| Dell          | 0UW457 A03                  | [b09d9907b9](https://linux-hardware.org/?probe=b09d9907b9) | Jul 29, 2022 |
| HP            | 3647h                       | [321f75b5a1](https://linux-hardware.org/?probe=321f75b5a1) | Jul 29, 2022 |
| ASUSTek       | PRIME B450M-K               | [aa77364c9c](https://linux-hardware.org/?probe=aa77364c9c) | Jul 29, 2022 |
| ASRock        | H77M-ITX                    | [ca0d4b7108](https://linux-hardware.org/?probe=ca0d4b7108) | Jul 28, 2022 |
| ASUSTek       | Pro B560M-C                 | [c4a4fed104](https://linux-hardware.org/?probe=c4a4fed104) | Jul 28, 2022 |
| MSI           | MEG X570 ACE                | [c2741e6f43](https://linux-hardware.org/?probe=c2741e6f43) | Jul 28, 2022 |
| ASUSTek       | Pro B560M-C                 | [61c0b1285b](https://linux-hardware.org/?probe=61c0b1285b) | Jul 28, 2022 |
| MSI           | B250M PRO-VDH               | [737604edb6](https://linux-hardware.org/?probe=737604edb6) | Jul 28, 2022 |
| ASUSTek       | Z97-C                       | [e292699b1c](https://linux-hardware.org/?probe=e292699b1c) | Jul 28, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [db241f583d](https://linux-hardware.org/?probe=db241f583d) | Jul 28, 2022 |
| Gigabyte      | B85-HD3                     | [ca37936b6f](https://linux-hardware.org/?probe=ca37936b6f) | Jul 28, 2022 |
| Gigabyte      | GA-970A-UD3                 | [62b86d61af](https://linux-hardware.org/?probe=62b86d61af) | Jul 28, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [df54f79195](https://linux-hardware.org/?probe=df54f79195) | Jul 28, 2022 |
| ASUSTek       | P8H67-M LE                  | [08af503a5a](https://linux-hardware.org/?probe=08af503a5a) | Jul 28, 2022 |
| ASUSTek       | VC65                        | [b43ad009f1](https://linux-hardware.org/?probe=b43ad009f1) | Jul 28, 2022 |
| Foxconn       | ALOE X3                     | [dd3dd847b8](https://linux-hardware.org/?probe=dd3dd847b8) | Jul 28, 2022 |
| ASUSTek       | Pro B560M-C                 | [d8b47ea062](https://linux-hardware.org/?probe=d8b47ea062) | Jul 27, 2022 |
| PCWare        | IPMH61R1                    | [18610dd9f0](https://linux-hardware.org/?probe=18610dd9f0) | Jul 27, 2022 |
| Apple         | Mac-F221BEC8                | [98461afcdb](https://linux-hardware.org/?probe=98461afcdb) | Jul 27, 2022 |
| Apple         | Mac-F221BEC8                | [703ce95e74](https://linux-hardware.org/?probe=703ce95e74) | Jul 27, 2022 |
| HP            | 8054                        | [3b76696319](https://linux-hardware.org/?probe=3b76696319) | Jul 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [55318bcefe](https://linux-hardware.org/?probe=55318bcefe) | Jul 27, 2022 |
| Acer          | Aspire XC-830               | [3f67091cd9](https://linux-hardware.org/?probe=3f67091cd9) | Jul 27, 2022 |
| MSI           | X79A-GD45 Plus              | [5496428dac](https://linux-hardware.org/?probe=5496428dac) | Jul 27, 2022 |
| Acer          | Aspire XC-830               | [21032de7c0](https://linux-hardware.org/?probe=21032de7c0) | Jul 27, 2022 |
| MSI           | 2A9C                        | [de5a8c7ecd](https://linux-hardware.org/?probe=de5a8c7ecd) | Jul 27, 2022 |
| Gigabyte      | H410M S2 V3                 | [29d5401a6b](https://linux-hardware.org/?probe=29d5401a6b) | Jul 27, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [0648778462](https://linux-hardware.org/?probe=0648778462) | Jul 26, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [1e2e0882a8](https://linux-hardware.org/?probe=1e2e0882a8) | Jul 26, 2022 |
| Huanan        | X99-F8                      | [3ba1885fb4](https://linux-hardware.org/?probe=3ba1885fb4) | Jul 26, 2022 |
| Gigabyte      | Z370N WIFI-CF               | [eb3c3fceb3](https://linux-hardware.org/?probe=eb3c3fceb3) | Jul 26, 2022 |
| ASRock        | H77M-ITX                    | [78a53c9be0](https://linux-hardware.org/?probe=78a53c9be0) | Jul 26, 2022 |
| Acer          | FIH57                       | [f351802c52](https://linux-hardware.org/?probe=f351802c52) | Jul 26, 2022 |
| ASRock        | H77M-ITX                    | [8c749dd7e6](https://linux-hardware.org/?probe=8c749dd7e6) | Jul 26, 2022 |
| HP            | 870C                        | [b88964a379](https://linux-hardware.org/?probe=b88964a379) | Jul 26, 2022 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | [b61b6b5fa5](https://linux-hardware.org/?probe=b61b6b5fa5) | Jul 26, 2022 |
| HP            | 339A                        | [39d7b3c457](https://linux-hardware.org/?probe=39d7b3c457) | Jul 26, 2022 |
| Medion        | MS-7800                     | [cb2ef643bb](https://linux-hardware.org/?probe=cb2ef643bb) | Jul 26, 2022 |
| Acer          | FIH57                       | [df3c42e452](https://linux-hardware.org/?probe=df3c42e452) | Jul 25, 2022 |
| HP            | 18E9                        | [8514b39779](https://linux-hardware.org/?probe=8514b39779) | Jul 25, 2022 |
| Medion        | MS-7797                     | [9ad7252b8a](https://linux-hardware.org/?probe=9ad7252b8a) | Jul 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [fe6b7362b8](https://linux-hardware.org/?probe=fe6b7362b8) | Jul 25, 2022 |
| ASUSTek       | Maximus VII HERO            | [b44ef13187](https://linux-hardware.org/?probe=b44ef13187) | Jul 24, 2022 |
| HP            | 3646h                       | [65d1da3eba](https://linux-hardware.org/?probe=65d1da3eba) | Jul 24, 2022 |
| Medion        | MS-7800                     | [320071c9a0](https://linux-hardware.org/?probe=320071c9a0) | Jul 24, 2022 |
| Dell          | 0KV3RP A00                  | [be029b4d99](https://linux-hardware.org/?probe=be029b4d99) | Jul 24, 2022 |
| ASRock        | H81M-HDS                    | [b3f2310571](https://linux-hardware.org/?probe=b3f2310571) | Jul 24, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [903908877a](https://linux-hardware.org/?probe=903908877a) | Jul 24, 2022 |
| Dell          | 042P49 A02                  | [85391d674c](https://linux-hardware.org/?probe=85391d674c) | Jul 24, 2022 |
| XDO.AI        | Pantera Pico PC             | [e29f39ad9e](https://linux-hardware.org/?probe=e29f39ad9e) | Jul 23, 2022 |
| Dell          | 08WKV3 A00                  | [894cbd512c](https://linux-hardware.org/?probe=894cbd512c) | Jul 23, 2022 |
| ASUSTek       | P5QPL-AM                    | [79113b8782](https://linux-hardware.org/?probe=79113b8782) | Jul 23, 2022 |
| AZW           | SEi                         | [e2d04ac048](https://linux-hardware.org/?probe=e2d04ac048) | Jul 23, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [4b3a55fc55](https://linux-hardware.org/?probe=4b3a55fc55) | Jul 23, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | [7d3501365a](https://linux-hardware.org/?probe=7d3501365a) | Jul 23, 2022 |
| ASUSTek       | PRIME B450M-A               | [b0e3bc86bc](https://linux-hardware.org/?probe=b0e3bc86bc) | Jul 23, 2022 |
| ASUSTek       | PRIME B450M-A               | [8288af270f](https://linux-hardware.org/?probe=8288af270f) | Jul 23, 2022 |
| HP            | 2B2B                        | [14cefcf857](https://linux-hardware.org/?probe=14cefcf857) | Jul 22, 2022 |
| Gigabyte      | Z690I A ULTRA PLUS D4       | [453b2cce27](https://linux-hardware.org/?probe=453b2cce27) | Jul 22, 2022 |
| Gigabyte      | GA-78LMT-USB3 R2            | [a57ab4e2dc](https://linux-hardware.org/?probe=a57ab4e2dc) | Jul 22, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [f383b92a53](https://linux-hardware.org/?probe=f383b92a53) | Jul 22, 2022 |
| MSI           | A78M-E45 V2                 | [c5007c5729](https://linux-hardware.org/?probe=c5007c5729) | Jul 22, 2022 |
| ASUSTek       | P7H55-M LX                  | [3e14a0baf3](https://linux-hardware.org/?probe=3e14a0baf3) | Jul 22, 2022 |
| Shuttle       | FH67H                       | [fe77bc1ab0](https://linux-hardware.org/?probe=fe77bc1ab0) | Jul 22, 2022 |
| Gigabyte      | Z97-D3H-CF                  | [07be23439c](https://linux-hardware.org/?probe=07be23439c) | Jul 21, 2022 |
| Pegatron      | Benicia                     | [f197aeb457](https://linux-hardware.org/?probe=f197aeb457) | Jul 21, 2022 |
| Unknown       | T3 MRD                      | [afbe55b100](https://linux-hardware.org/?probe=afbe55b100) | Jul 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [7e6502be7c](https://linux-hardware.org/?probe=7e6502be7c) | Jul 20, 2022 |
| ASUSTek       | A88X-PRO                    | [a9fb1104e7](https://linux-hardware.org/?probe=a9fb1104e7) | Jul 20, 2022 |
| ASRock        | B450 Pro4                   | [7037061aed](https://linux-hardware.org/?probe=7037061aed) | Jul 20, 2022 |
| Acer          | EQ45M                       | [53a74d39e4](https://linux-hardware.org/?probe=53a74d39e4) | Jul 20, 2022 |
| ASUSTek       | A88X-PRO                    | [400c3cee0d](https://linux-hardware.org/?probe=400c3cee0d) | Jul 20, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [d88edfec1f](https://linux-hardware.org/?probe=d88edfec1f) | Jul 20, 2022 |
| Huanan        | X99-TF V2.0                 | [4217957e12](https://linux-hardware.org/?probe=4217957e12) | Jul 19, 2022 |
| Medion        | MS-7797                     | [68faff0dba](https://linux-hardware.org/?probe=68faff0dba) | Jul 19, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [2c81e24a1a](https://linux-hardware.org/?probe=2c81e24a1a) | Jul 19, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [290d973b31](https://linux-hardware.org/?probe=290d973b31) | Jul 19, 2022 |
| MSI           | Z77A-G43                    | [56afef1d13](https://linux-hardware.org/?probe=56afef1d13) | Jul 19, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | [f32b12f921](https://linux-hardware.org/?probe=f32b12f921) | Jul 19, 2022 |
| Dell          | 0CRH6C A02                  | [e324e6a67b](https://linux-hardware.org/?probe=e324e6a67b) | Jul 18, 2022 |
| ASUSTek       | M4A88T-M                    | [57ed9f00c7](https://linux-hardware.org/?probe=57ed9f00c7) | Jul 18, 2022 |
| ASUSTek       | M4A88T-M                    | [f99189e2d0](https://linux-hardware.org/?probe=f99189e2d0) | Jul 18, 2022 |
| PCPartner     | MILANO-P Rev.00             | [1b6d72c5ac](https://linux-hardware.org/?probe=1b6d72c5ac) | Jul 18, 2022 |
| Gigabyte      | A320M-H-CF                  | [5bdae5b8f7](https://linux-hardware.org/?probe=5bdae5b8f7) | Jul 18, 2022 |
| Intel         | X79M-S                      | [225309497e](https://linux-hardware.org/?probe=225309497e) | Jul 18, 2022 |
| Intel         | X79M-S                      | [d788e4c74d](https://linux-hardware.org/?probe=d788e4c74d) | Jul 18, 2022 |
| ASUSTek       | WS X299 SAGE                | [acb31e0818](https://linux-hardware.org/?probe=acb31e0818) | Jul 18, 2022 |
| Gigabyte      | Z97X-Gaming 3               | [ec770759cd](https://linux-hardware.org/?probe=ec770759cd) | Jul 17, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [325fbd84e9](https://linux-hardware.org/?probe=325fbd84e9) | Jul 17, 2022 |
| ASRock        | H310CM-HDV                  | [5cad17641f](https://linux-hardware.org/?probe=5cad17641f) | Jul 17, 2022 |
| ASUSTek       | Z170-K                      | [094ba7059b](https://linux-hardware.org/?probe=094ba7059b) | Jul 16, 2022 |
| Gigabyte      | P55-USB3                    | [a974b4bb92](https://linux-hardware.org/?probe=a974b4bb92) | Jul 16, 2022 |
| MSI           | MPG Z690 FORCE WIFI         | [88f3a17986](https://linux-hardware.org/?probe=88f3a17986) | Jul 16, 2022 |
| ASUSTek       | PRIME H610M-E D4            | [66fe37549d](https://linux-hardware.org/?probe=66fe37549d) | Jul 16, 2022 |
| ASRock        | H61M-GS                     | [a653521268](https://linux-hardware.org/?probe=a653521268) | Jul 16, 2022 |
| ASRock        | H61M-GS                     | [1d2de44667](https://linux-hardware.org/?probe=1d2de44667) | Jul 16, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [710cf5ff0e](https://linux-hardware.org/?probe=710cf5ff0e) | Jul 16, 2022 |
| ASUSTek       | P8H61-M LX2                 | [4b2f1f5d39](https://linux-hardware.org/?probe=4b2f1f5d39) | Jul 16, 2022 |
| Acer          | FIH57                       | [ea25a3cc88](https://linux-hardware.org/?probe=ea25a3cc88) | Jul 15, 2022 |
| Supermicro    | X10DRH-CT                   | [bcf5e02acd](https://linux-hardware.org/?probe=bcf5e02acd) | Jul 15, 2022 |
| ASUSTek       | H81M-E                      | [a227b89fef](https://linux-hardware.org/?probe=a227b89fef) | Jul 15, 2022 |
| Lenovo        | 7033EW4                     | [e471fc8ecd](https://linux-hardware.org/?probe=e471fc8ecd) | Jul 15, 2022 |
| Intel         | D54250WYK H13922-304        | [2ea167ab24](https://linux-hardware.org/?probe=2ea167ab24) | Jul 15, 2022 |
| Dell          | 042P49 A02                  | [bb5748e226](https://linux-hardware.org/?probe=bb5748e226) | Jul 15, 2022 |
| ASUSTek       | SABERTOOTH Z77              | [48c1d4e141](https://linux-hardware.org/?probe=48c1d4e141) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M58p 6234F73    | [c5695a430f](https://linux-hardware.org/?probe=c5695a430f) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M58p 6234F73    | [0a0ad06ece](https://linux-hardware.org/?probe=0a0ad06ece) | Jul 15, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [14a754a395](https://linux-hardware.org/?probe=14a754a395) | Jul 14, 2022 |
| ASRock        | A55M-VS                     | [844ac53526](https://linux-hardware.org/?probe=844ac53526) | Jul 14, 2022 |
| ASRock        | A55M-VS                     | [3b8f491017](https://linux-hardware.org/?probe=3b8f491017) | Jul 14, 2022 |
| ASUSTek       | H81M-E                      | [e1ef49be7d](https://linux-hardware.org/?probe=e1ef49be7d) | Jul 14, 2022 |
| Gigabyte      | 990FXA-UD5                  | [7797840c50](https://linux-hardware.org/?probe=7797840c50) | Jul 14, 2022 |
| ASRockRack    | ROMED8-2T                   | [e56577e7d4](https://linux-hardware.org/?probe=e56577e7d4) | Jul 14, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | [a4f5723ada](https://linux-hardware.org/?probe=a4f5723ada) | Jul 14, 2022 |
| ASRockRack    | ROMED8-2T                   | [d0bfc3e9d3](https://linux-hardware.org/?probe=d0bfc3e9d3) | Jul 14, 2022 |
| Dell          | 0W2F8G A01                  | [77f2181e08](https://linux-hardware.org/?probe=77f2181e08) | Jul 13, 2022 |
| ASUSTek       | X99-A                       | [6db5d85e5c](https://linux-hardware.org/?probe=6db5d85e5c) | Jul 13, 2022 |
| MSI           | B450 TOMAHAWK               | [6cf3eeb7fc](https://linux-hardware.org/?probe=6cf3eeb7fc) | Jul 13, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [37890b5158](https://linux-hardware.org/?probe=37890b5158) | Jul 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | [0e195b05bf](https://linux-hardware.org/?probe=0e195b05bf) | Jul 13, 2022 |
| MSI           | A320M PRO-VH PLUS           | [e007a2fbc2](https://linux-hardware.org/?probe=e007a2fbc2) | Jul 13, 2022 |
| HP            | 2B17                        | [c9481d00f3](https://linux-hardware.org/?probe=c9481d00f3) | Jul 13, 2022 |
| Intel         | D34010WYK H14771-304        | [3fe93a38f6](https://linux-hardware.org/?probe=3fe93a38f6) | Jul 13, 2022 |
| Dell          | 07KY25 A00                  | [14e0ab8eb2](https://linux-hardware.org/?probe=14e0ab8eb2) | Jul 13, 2022 |
| Acer          | EQ45M                       | [22911b2564](https://linux-hardware.org/?probe=22911b2564) | Jul 12, 2022 |
| Gigabyte      | A520M S2H                   | [52aab7f65b](https://linux-hardware.org/?probe=52aab7f65b) | Jul 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [43e78c262a](https://linux-hardware.org/?probe=43e78c262a) | Jul 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [063f846aad](https://linux-hardware.org/?probe=063f846aad) | Jul 12, 2022 |
| HP            | 2B2B                        | [3254e734a5](https://linux-hardware.org/?probe=3254e734a5) | Jul 12, 2022 |
| Intel         | D34010WYK H14771-304        | [26c70348e9](https://linux-hardware.org/?probe=26c70348e9) | Jul 12, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [37ee80d118](https://linux-hardware.org/?probe=37ee80d118) | Jul 11, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [80de38308d](https://linux-hardware.org/?probe=80de38308d) | Jul 11, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1a80abdbf2](https://linux-hardware.org/?probe=1a80abdbf2) | Jul 11, 2022 |
| ASUSTek       | P5LD2                       | [933399f6f5](https://linux-hardware.org/?probe=933399f6f5) | Jul 11, 2022 |
| MSI           | H81M-P33                    | [05099f85ea](https://linux-hardware.org/?probe=05099f85ea) | Jul 11, 2022 |
| Acer          | Aspire M3920                | [9b12bf66ac](https://linux-hardware.org/?probe=9b12bf66ac) | Jul 11, 2022 |
| YANYU         | EPIC-C19                    | [5bda78db57](https://linux-hardware.org/?probe=5bda78db57) | Jul 11, 2022 |
| HP            | 0B4Ch D                     | [f49fb95b26](https://linux-hardware.org/?probe=f49fb95b26) | Jul 10, 2022 |
| Acer          | FIH57                       | [b052eec1d0](https://linux-hardware.org/?probe=b052eec1d0) | Jul 10, 2022 |
| Dell          | 09M8Y8 A02                  | [b4f3b56350](https://linux-hardware.org/?probe=b4f3b56350) | Jul 10, 2022 |
| Acer          | Nitro N50-610               | [48c007b4e2](https://linux-hardware.org/?probe=48c007b4e2) | Jul 10, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [978d27ca8b](https://linux-hardware.org/?probe=978d27ca8b) | Jul 10, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [3209c50980](https://linux-hardware.org/?probe=3209c50980) | Jul 10, 2022 |
| Medion        | H81H3-EM2                   | [fbe5cf60f0](https://linux-hardware.org/?probe=fbe5cf60f0) | Jul 10, 2022 |
| Gigabyte      | PH67A-D3-B3                 | [5ccd729440](https://linux-hardware.org/?probe=5ccd729440) | Jul 10, 2022 |
| Apple         | Mac-F221BEC8                | [2efb274f31](https://linux-hardware.org/?probe=2efb274f31) | Jul 10, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [cbe2ceab3e](https://linux-hardware.org/?probe=cbe2ceab3e) | Jul 10, 2022 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [f5d291204f](https://linux-hardware.org/?probe=f5d291204f) | Jul 10, 2022 |
| MSI           | MPG Z690 FORCE WIFI         | [d1eaa06cd9](https://linux-hardware.org/?probe=d1eaa06cd9) | Jul 09, 2022 |
| ABIT          | IP35-E                      | [797026a126](https://linux-hardware.org/?probe=797026a126) | Jul 09, 2022 |
| ABIT          | IP35-E                      | [e217f62c10](https://linux-hardware.org/?probe=e217f62c10) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [e5316b7d72](https://linux-hardware.org/?probe=e5316b7d72) | Jul 09, 2022 |
| Unknown       | Unknown                     | [e7dfa60f77](https://linux-hardware.org/?probe=e7dfa60f77) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [3df269fec9](https://linux-hardware.org/?probe=3df269fec9) | Jul 09, 2022 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [8ac6704c06](https://linux-hardware.org/?probe=8ac6704c06) | Jul 09, 2022 |
| Gigabyte      | Z690 UD DDR4                | [bcec55fd41](https://linux-hardware.org/?probe=bcec55fd41) | Jul 09, 2022 |
| Pegatron      | 2AC3                        | [e1d3204cf2](https://linux-hardware.org/?probe=e1d3204cf2) | Jul 09, 2022 |
| Gigabyte      | 970A-DS3P                   | [75f0ca97b8](https://linux-hardware.org/?probe=75f0ca97b8) | Jul 08, 2022 |
| ASRock        | A320M-HDV R4.0              | [4f7f102599](https://linux-hardware.org/?probe=4f7f102599) | Jul 08, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [d66a60be9a](https://linux-hardware.org/?probe=d66a60be9a) | Jul 08, 2022 |
| ECS           | H110M4-C23                  | [4a4af6d2e9](https://linux-hardware.org/?probe=4a4af6d2e9) | Jul 08, 2022 |
| MSI           | H510M PRO-E                 | [560e81bb64](https://linux-hardware.org/?probe=560e81bb64) | Jul 08, 2022 |
| MSI           | H510M PRO-E                 | [4f57a8d7f4](https://linux-hardware.org/?probe=4f57a8d7f4) | Jul 08, 2022 |
| HP            | 212B                        | [f5972124a5](https://linux-hardware.org/?probe=f5972124a5) | Jul 08, 2022 |
| HP            | 212B                        | [c6b1d18aec](https://linux-hardware.org/?probe=c6b1d18aec) | Jul 08, 2022 |
| MSI           | 2A9C                        | [40457980de](https://linux-hardware.org/?probe=40457980de) | Jul 08, 2022 |
| ASRock        | G41M-VS3                    | [fe19bb609e](https://linux-hardware.org/?probe=fe19bb609e) | Jul 08, 2022 |
| ASRock        | G41M-VS3                    | [8dc2d34c99](https://linux-hardware.org/?probe=8dc2d34c99) | Jul 08, 2022 |
| MSI           | Z590-A PRO                  | [45155c9045](https://linux-hardware.org/?probe=45155c9045) | Jul 07, 2022 |
| MSI           | Z590-A PRO                  | [2685bc5f4f](https://linux-hardware.org/?probe=2685bc5f4f) | Jul 07, 2022 |
| ASUSTek       | PRIME Z590-P                | [53fbdec1df](https://linux-hardware.org/?probe=53fbdec1df) | Jul 07, 2022 |
| ASUSTek       | Pro H510M-C                 | [f991c1fba8](https://linux-hardware.org/?probe=f991c1fba8) | Jul 07, 2022 |
| ASUSTek       | Pro H510M-C                 | [a5f338ae1a](https://linux-hardware.org/?probe=a5f338ae1a) | Jul 07, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | [758112a61d](https://linux-hardware.org/?probe=758112a61d) | Jul 07, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [50dc2b8c60](https://linux-hardware.org/?probe=50dc2b8c60) | Jul 07, 2022 |
| MSI           | X470 GAMING PRO             | [b94f3f8031](https://linux-hardware.org/?probe=b94f3f8031) | Jul 07, 2022 |
| HP            | 18E7                        | [68781cd22f](https://linux-hardware.org/?probe=68781cd22f) | Jul 07, 2022 |
| Dell          | 0FKVT5 A01                  | [8f61264039](https://linux-hardware.org/?probe=8f61264039) | Jul 07, 2022 |
| Dell          | 0FKVT5 A01                  | [de88b169a1](https://linux-hardware.org/?probe=de88b169a1) | Jul 07, 2022 |
| Intel         | DG35EC AAE29266-205         | [5b90bd12c7](https://linux-hardware.org/?probe=5b90bd12c7) | Jul 07, 2022 |
| Intel         | DG35EC AAE29266-205         | [9c2136e4eb](https://linux-hardware.org/?probe=9c2136e4eb) | Jul 07, 2022 |
| ASUSTek       | PRIME B450M-A               | [a3548b2397](https://linux-hardware.org/?probe=a3548b2397) | Jul 06, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | [21f58df6b0](https://linux-hardware.org/?probe=21f58df6b0) | Jul 06, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [ebaa969297](https://linux-hardware.org/?probe=ebaa969297) | Jul 06, 2022 |
| HP            | 870C                        | [17993cf668](https://linux-hardware.org/?probe=17993cf668) | Jul 06, 2022 |
| ASUSTek       | P5GC-MX                     | [a3ec66a255](https://linux-hardware.org/?probe=a3ec66a255) | Jul 05, 2022 |
| Acer          | FIH57                       | [75895f96b9](https://linux-hardware.org/?probe=75895f96b9) | Jul 05, 2022 |
| Gigabyte      | H110M-S2H-CF                | [e400d050db](https://linux-hardware.org/?probe=e400d050db) | Jul 05, 2022 |
| HP            | 3646h                       | [36c53efdac](https://linux-hardware.org/?probe=36c53efdac) | Jul 05, 2022 |
| HP            | 3646h                       | [675a46eda3](https://linux-hardware.org/?probe=675a46eda3) | Jul 05, 2022 |
| HP            | 3648h                       | [4d9ef6de51](https://linux-hardware.org/?probe=4d9ef6de51) | Jul 05, 2022 |
| MSI           | Z170-A PRO                  | [24a76119e1](https://linux-hardware.org/?probe=24a76119e1) | Jul 04, 2022 |
| Dell          | 07KY25 A01                  | [35ac60e264](https://linux-hardware.org/?probe=35ac60e264) | Jul 04, 2022 |
| Shuttle       | FS61                        | [43d79d98be](https://linux-hardware.org/?probe=43d79d98be) | Jul 04, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [5c8477b1a3](https://linux-hardware.org/?probe=5c8477b1a3) | Jul 04, 2022 |
| ASUSTek       | ROG ZENITH II EXTREME AL... | [6f75b1c1e4](https://linux-hardware.org/?probe=6f75b1c1e4) | Jul 04, 2022 |
| MSI           | 970A SLI Krait Edition      | [3199c023cb](https://linux-hardware.org/?probe=3199c023cb) | Jul 04, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | [c76805b11f](https://linux-hardware.org/?probe=c76805b11f) | Jul 04, 2022 |
| HP            | 18E7                        | [39c3a381f4](https://linux-hardware.org/?probe=39c3a381f4) | Jul 04, 2022 |
| Lenovo        | SHARKBAY NOK                | [15088a414c](https://linux-hardware.org/?probe=15088a414c) | Jul 03, 2022 |
| ASUSTek       | M5A99X EVO                  | [f0c71f2614](https://linux-hardware.org/?probe=f0c71f2614) | Jul 03, 2022 |
| MSI           | B450M BAZOOKA V2            | [bded0a2071](https://linux-hardware.org/?probe=bded0a2071) | Jul 03, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | [2a709f4166](https://linux-hardware.org/?probe=2a709f4166) | Jul 03, 2022 |
| Acer          | Aspire TC-280               | [7322461b76](https://linux-hardware.org/?probe=7322461b76) | Jul 03, 2022 |
| HP            | 8643 SMVB                   | [66de926a3d](https://linux-hardware.org/?probe=66de926a3d) | Jul 03, 2022 |
| ASUSTek       | B85M-G R2.0                 | [ab0751d062](https://linux-hardware.org/?probe=ab0751d062) | Jul 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [6fa5768750](https://linux-hardware.org/?probe=6fa5768750) | Jul 02, 2022 |
| Medion        | MS-7797                     | [0fa607f9a5](https://linux-hardware.org/?probe=0fa607f9a5) | Jul 02, 2022 |
| Dell          | 0D28YY A03                  | [de2bbc9ab0](https://linux-hardware.org/?probe=de2bbc9ab0) | Jul 02, 2022 |
| MSI           | Z170A GAMING M7             | [a0d37a0b9f](https://linux-hardware.org/?probe=a0d37a0b9f) | Jul 02, 2022 |
| Gigabyte      | H81M-S                      | [4a6acd9191](https://linux-hardware.org/?probe=4a6acd9191) | Jul 02, 2022 |
| Apple         | Mac-F221BEC8                | [564950d244](https://linux-hardware.org/?probe=564950d244) | Jul 02, 2022 |
| Acer          | Aspire TC-280               | [0e497c1c13](https://linux-hardware.org/?probe=0e497c1c13) | Jul 02, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [dbeb1565c1](https://linux-hardware.org/?probe=dbeb1565c1) | Jul 02, 2022 |
| Foxconn       | ALOE X3                     | [754758d432](https://linux-hardware.org/?probe=754758d432) | Jul 02, 2022 |
| ASRock        | N68-VS3 UCC                 | [dd43bf961c](https://linux-hardware.org/?probe=dd43bf961c) | Jul 02, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [060a34b3a1](https://linux-hardware.org/?probe=060a34b3a1) | Jul 01, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [630bb92cd8](https://linux-hardware.org/?probe=630bb92cd8) | Jul 01, 2022 |
| MSI           | Z390 GAM PRO CARB AC        | [a55ab11db7](https://linux-hardware.org/?probe=a55ab11db7) | Jul 01, 2022 |
| Dell          | 042P49 A02                  | [110e5da723](https://linux-hardware.org/?probe=110e5da723) | Jul 01, 2022 |
| Intel         | DX58SO AAE29331-703         | [3b22974574](https://linux-hardware.org/?probe=3b22974574) | Jul 01, 2022 |
| Medion        | MS-7797                     | [01ff2f8272](https://linux-hardware.org/?probe=01ff2f8272) | Jul 01, 2022 |
| ASUSTek       | M5A78L LE                   | [19dbe00e60](https://linux-hardware.org/?probe=19dbe00e60) | Jul 01, 2022 |
| HP            | 805D                        | [3610332b9c](https://linux-hardware.org/?probe=3610332b9c) | Jul 01, 2022 |
| Dell          | 042P49 A02                  | [169b7b8c30](https://linux-hardware.org/?probe=169b7b8c30) | Jul 01, 2022 |
| Gigabyte      | H81M-S2PH                   | [cc62a478ac](https://linux-hardware.org/?probe=cc62a478ac) | Jul 01, 2022 |
| Gigabyte      | Z97X-Gaming 3               | [9b8bb163d3](https://linux-hardware.org/?probe=9b8bb163d3) | Jul 01, 2022 |
| ECS           | A780GM-A                    | [2cea4325e9](https://linux-hardware.org/?probe=2cea4325e9) | Jul 01, 2022 |
| Unknown       | Unknown                     | [1de34d9bf9](https://linux-hardware.org/?probe=1de34d9bf9) | Jun 30, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [349dc94a13](https://linux-hardware.org/?probe=349dc94a13) | Jun 29, 2022 |
| MSI           | MEG Z490 UNIFY              | [2c7a50869d](https://linux-hardware.org/?probe=2c7a50869d) | Jun 29, 2022 |
| Dell          | 0M5DCD A00                  | [7ff0a3f172](https://linux-hardware.org/?probe=7ff0a3f172) | Jun 29, 2022 |
| Dell          | 0M5DCD A00                  | [483d6a9299](https://linux-hardware.org/?probe=483d6a9299) | Jun 29, 2022 |
| Lenovo        | MAHOBAY NOK                 | [20a14662e8](https://linux-hardware.org/?probe=20a14662e8) | Jun 29, 2022 |
| MSI           | MPG Z390I GAMING EDGE AC    | [389293962a](https://linux-hardware.org/?probe=389293962a) | Jun 29, 2022 |
| ASUSTek       | B85M-E                      | [2423d184c0](https://linux-hardware.org/?probe=2423d184c0) | Jun 29, 2022 |
| ASUSTek       | P5LD2                       | [4fdebc2b9c](https://linux-hardware.org/?probe=4fdebc2b9c) | Jun 29, 2022 |
| ASRock        | B550M-ITX/ac                | [01614433d5](https://linux-hardware.org/?probe=01614433d5) | Jun 29, 2022 |
| ASUSTek       | P5LD2                       | [c7f67d9347](https://linux-hardware.org/?probe=c7f67d9347) | Jun 29, 2022 |
| ASUSTek       | PRO H410M-C                 | [9f705aea75](https://linux-hardware.org/?probe=9f705aea75) | Jun 29, 2022 |
| Dell          | 0D24M8 A00                  | [1588270a58](https://linux-hardware.org/?probe=1588270a58) | Jun 29, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [d59692d648](https://linux-hardware.org/?probe=d59692d648) | Jun 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [5873a7a8dd](https://linux-hardware.org/?probe=5873a7a8dd) | Jun 29, 2022 |
| MSI           | H110M GAMING                | [e33051cbd0](https://linux-hardware.org/?probe=e33051cbd0) | Jun 28, 2022 |
| Dell          | 0TP406                      | [4f0f2b2e05](https://linux-hardware.org/?probe=4f0f2b2e05) | Jun 28, 2022 |
| Acer          | H81-M1                      | [9ddfb2ec8d](https://linux-hardware.org/?probe=9ddfb2ec8d) | Jun 28, 2022 |
| HP            | 0B4Ch D                     | [6e28eeb447](https://linux-hardware.org/?probe=6e28eeb447) | Jun 27, 2022 |
| Dell          | 0RF703                      | [7b1a5ddcb6](https://linux-hardware.org/?probe=7b1a5ddcb6) | Jun 27, 2022 |
| ASRock        | 970 Pro3 R2.0               | [ba2f829e73](https://linux-hardware.org/?probe=ba2f829e73) | Jun 27, 2022 |
| Dell          | 051FJ8 A02                  | [5b997790f1](https://linux-hardware.org/?probe=5b997790f1) | Jun 27, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | [3d575e19b6](https://linux-hardware.org/?probe=3d575e19b6) | Jun 27, 2022 |
| MSI           | B450M-A PRO MAX             | [666f9678a5](https://linux-hardware.org/?probe=666f9678a5) | Jun 27, 2022 |
| ASUSTek       | P8B75-M LE                  | [48cbc869da](https://linux-hardware.org/?probe=48cbc869da) | Jun 27, 2022 |
| ASUSTek       | P8B75-M LE                  | [ea31080862](https://linux-hardware.org/?probe=ea31080862) | Jun 27, 2022 |
| MSI           | Z590-A PRO                  | [1adcde94c5](https://linux-hardware.org/?probe=1adcde94c5) | Jun 26, 2022 |
| MSI           | Z590-A PRO                  | [18d6fda695](https://linux-hardware.org/?probe=18d6fda695) | Jun 26, 2022 |
| MSI           | H55M-E33                    | [035cfe1a5b](https://linux-hardware.org/?probe=035cfe1a5b) | Jun 26, 2022 |
| MSI           | B450M PRO-M2                | [516abfbea1](https://linux-hardware.org/?probe=516abfbea1) | Jun 26, 2022 |
| MSI           | B450M-A PRO MAX             | [aa9757e958](https://linux-hardware.org/?probe=aa9757e958) | Jun 26, 2022 |
| ASUSTek       | P8Z68-V LX                  | [5935ab812a](https://linux-hardware.org/?probe=5935ab812a) | Jun 26, 2022 |
| MSI           | PRO Z690-A                  | [34a2f4f726](https://linux-hardware.org/?probe=34a2f4f726) | Jun 26, 2022 |
| ASUSTek       | P8H61-I                     | [15b8beca14](https://linux-hardware.org/?probe=15b8beca14) | Jun 26, 2022 |
| Dell          | 0HD5W2 A01                  | [9f87421952](https://linux-hardware.org/?probe=9f87421952) | Jun 26, 2022 |
| Dell          | 0VD92X A00                  | [5082bf92e9](https://linux-hardware.org/?probe=5082bf92e9) | Jun 26, 2022 |
| MSI           | A78M-E45 V2                 | [e4cd6586b4](https://linux-hardware.org/?probe=e4cd6586b4) | Jun 26, 2022 |
| Gigabyte      | X570 GAMING X               | [b66ac35391](https://linux-hardware.org/?probe=b66ac35391) | Jun 26, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [f440505698](https://linux-hardware.org/?probe=f440505698) | Jun 25, 2022 |
| MSI           | H81M-P33                    | [9ba6c64800](https://linux-hardware.org/?probe=9ba6c64800) | Jun 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [8f2b511688](https://linux-hardware.org/?probe=8f2b511688) | Jun 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [ace55b44d7](https://linux-hardware.org/?probe=ace55b44d7) | Jun 25, 2022 |
| Lenovo        | 3714 SDK0J40700 WIN 3258... | [1be22bc8af](https://linux-hardware.org/?probe=1be22bc8af) | Jun 24, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | [57660d8f0f](https://linux-hardware.org/?probe=57660d8f0f) | Jun 24, 2022 |
| ASUSTek       | PRIME X570-P                | [fc1716de1f](https://linux-hardware.org/?probe=fc1716de1f) | Jun 24, 2022 |
| ASUSTek       | PRIME X570-P                | [785ec99ee8](https://linux-hardware.org/?probe=785ec99ee8) | Jun 24, 2022 |
| Gigabyte      | A520M S2H                   | [094c3f1e98](https://linux-hardware.org/?probe=094c3f1e98) | Jun 24, 2022 |
| Dell          | 0KW626                      | [ceb37aeba1](https://linux-hardware.org/?probe=ceb37aeba1) | Jun 24, 2022 |
| Intel         | X79G V2.x                   | [67b2e27895](https://linux-hardware.org/?probe=67b2e27895) | Jun 24, 2022 |
| ASUSTek       | X99-DELUXE                  | [34e3aad338](https://linux-hardware.org/?probe=34e3aad338) | Jun 24, 2022 |
| HP            | 2AF7                        | [86ecfeb9e2](https://linux-hardware.org/?probe=86ecfeb9e2) | Jun 24, 2022 |
| Dell          | 018D1Y A00                  | [8344a8b783](https://linux-hardware.org/?probe=8344a8b783) | Jun 24, 2022 |
| Foxconn       | 2AB1                        | [389a1d6185](https://linux-hardware.org/?probe=389a1d6185) | Jun 23, 2022 |
| Dell          | 0MGK50 A02                  | [eca7a31c46](https://linux-hardware.org/?probe=eca7a31c46) | Jun 23, 2022 |
| Dell          | 0MGK50 A02                  | [134bf128f7](https://linux-hardware.org/?probe=134bf128f7) | Jun 23, 2022 |
| ASRock        | Z590M-ITX/ax                | [263e8a50af](https://linux-hardware.org/?probe=263e8a50af) | Jun 23, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [95d5b870bb](https://linux-hardware.org/?probe=95d5b870bb) | Jun 23, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [3cfb6f7ee5](https://linux-hardware.org/?probe=3cfb6f7ee5) | Jun 23, 2022 |
| Lenovo        | MAHOBAY                     | [8f7a233327](https://linux-hardware.org/?probe=8f7a233327) | Jun 22, 2022 |
| Dell          | 0W2F8G A01                  | [447653d4f2](https://linux-hardware.org/?probe=447653d4f2) | Jun 22, 2022 |
| Dell          | 0W2F8G A01                  | [4610c38358](https://linux-hardware.org/?probe=4610c38358) | Jun 22, 2022 |
| ASUSTek       | P6T WS PRO                  | [9899337065](https://linux-hardware.org/?probe=9899337065) | Jun 22, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | [e4116b95a2](https://linux-hardware.org/?probe=e4116b95a2) | Jun 22, 2022 |
| Dell          | 042P49 A01                  | [836efa773c](https://linux-hardware.org/?probe=836efa773c) | Jun 22, 2022 |
| Dell          | 042P49 A01                  | [380b66353e](https://linux-hardware.org/?probe=380b66353e) | Jun 21, 2022 |
| MSI           | A320M-A PRO                 | [1f3b17165b](https://linux-hardware.org/?probe=1f3b17165b) | Jun 21, 2022 |
| ASRock        | H81M-VG4                    | [f9f9db00a7](https://linux-hardware.org/?probe=f9f9db00a7) | Jun 21, 2022 |
| Acer          | Aspire X1700                | [6a67f8cba0](https://linux-hardware.org/?probe=6a67f8cba0) | Jun 21, 2022 |
| HP            | 0AA0h                       | [ccc94e1725](https://linux-hardware.org/?probe=ccc94e1725) | Jun 21, 2022 |
| Gigabyte      | M68MT-S2                    | [c52b07844d](https://linux-hardware.org/?probe=c52b07844d) | Jun 21, 2022 |
| Gigabyte      | M68MT-S2                    | [31f786c1ff](https://linux-hardware.org/?probe=31f786c1ff) | Jun 21, 2022 |
| MSI           | B250I GAMING PRO AC         | [280d4af2d2](https://linux-hardware.org/?probe=280d4af2d2) | Jun 21, 2022 |
| MSI           | B250I GAMING PRO AC         | [c90adf6d43](https://linux-hardware.org/?probe=c90adf6d43) | Jun 21, 2022 |
| Gigabyte      | B660M GAMING DDR4           | [80ecbe8684](https://linux-hardware.org/?probe=80ecbe8684) | Jun 21, 2022 |
| Gigabyte      | B450M DS3H WIFI V2-CF       | [37f7936cd9](https://linux-hardware.org/?probe=37f7936cd9) | Jun 21, 2022 |
| Dell          | 0VD92X A00                  | [d0edbadf25](https://linux-hardware.org/?probe=d0edbadf25) | Jun 21, 2022 |
| ASUSTek       | Q87M-E                      | [9f37139898](https://linux-hardware.org/?probe=9f37139898) | Jun 21, 2022 |
| Dell          | 0TP406                      | [3798b45f67](https://linux-hardware.org/?probe=3798b45f67) | Jun 20, 2022 |
| MSI           | A78M-E45 V2                 | [97b9d51036](https://linux-hardware.org/?probe=97b9d51036) | Jun 20, 2022 |
| MSI           | Creator X299                | [279caedd2f](https://linux-hardware.org/?probe=279caedd2f) | Jun 20, 2022 |
| MSI           | A320M-A PRO                 | [8cecec73c6](https://linux-hardware.org/?probe=8cecec73c6) | Jun 19, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [2a4d1c8a0b](https://linux-hardware.org/?probe=2a4d1c8a0b) | Jun 19, 2022 |
| Gigabyte      | 965P-S3                     | [0beb9ce480](https://linux-hardware.org/?probe=0beb9ce480) | Jun 19, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [4c91d4b394](https://linux-hardware.org/?probe=4c91d4b394) | Jun 19, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [571829be67](https://linux-hardware.org/?probe=571829be67) | Jun 19, 2022 |
| ASUSTek       | X99-A/USB                   | [d9808cc5aa](https://linux-hardware.org/?probe=d9808cc5aa) | Jun 19, 2022 |
| Dell          | 09M8Y8 A02                  | [a029173d31](https://linux-hardware.org/?probe=a029173d31) | Jun 18, 2022 |
| Acer          | Aspire X3950                | [7a70838628](https://linux-hardware.org/?probe=7a70838628) | Jun 18, 2022 |
| Dell          | 0XHGV1 A00                  | [aeb1a92366](https://linux-hardware.org/?probe=aeb1a92366) | Jun 18, 2022 |
| MSI           | A320M-A PRO MAX             | [50149d3df0](https://linux-hardware.org/?probe=50149d3df0) | Jun 18, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [3e7ce078c6](https://linux-hardware.org/?probe=3e7ce078c6) | Jun 18, 2022 |
| Gigabyte      | H61M-DS2                    | [866ee7a33b](https://linux-hardware.org/?probe=866ee7a33b) | Jun 18, 2022 |
| Gigabyte      | F2A68HM-H                   | [3adcbf0255](https://linux-hardware.org/?probe=3adcbf0255) | Jun 18, 2022 |
| ASRock        | G41M-GS                     | [9167934132](https://linux-hardware.org/?probe=9167934132) | Jun 18, 2022 |
| ASUSTek       | H110M-CS/BR                 | [35cfc3daf7](https://linux-hardware.org/?probe=35cfc3daf7) | Jun 18, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | [63e3deaaf4](https://linux-hardware.org/?probe=63e3deaaf4) | Jun 17, 2022 |
| Gigabyte      | M68MT-S2                    | [570c3b2345](https://linux-hardware.org/?probe=570c3b2345) | Jun 17, 2022 |
| ASUSTek       | H110M-CS/BR                 | [47e88dae48](https://linux-hardware.org/?probe=47e88dae48) | Jun 17, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | [f5d7a0bba4](https://linux-hardware.org/?probe=f5d7a0bba4) | Jun 17, 2022 |
| HP            | 1998                        | [86d621451f](https://linux-hardware.org/?probe=86d621451f) | Jun 17, 2022 |
| ASUSTek       | P8H67-M LE                  | [d52a1b8eea](https://linux-hardware.org/?probe=d52a1b8eea) | Jun 17, 2022 |
| HP            | 8184 X4                     | [e2f24b580b](https://linux-hardware.org/?probe=e2f24b580b) | Jun 17, 2022 |
| Dell          | 0KRC95 A00                  | [c47403b875](https://linux-hardware.org/?probe=c47403b875) | Jun 17, 2022 |
| HP            | 8184 X4                     | [668438d39e](https://linux-hardware.org/?probe=668438d39e) | Jun 17, 2022 |
| MSI           | B450-A PRO MAX              | [24ecffb555](https://linux-hardware.org/?probe=24ecffb555) | Jun 16, 2022 |
| Lenovo        | 3148 SDK0J40709 WIN 3259... | [475e980cb3](https://linux-hardware.org/?probe=475e980cb3) | Jun 16, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [63ba339f77](https://linux-hardware.org/?probe=63ba339f77) | Jun 16, 2022 |
| MSI           | B450M PRO-M2 MAX            | [f005c585bd](https://linux-hardware.org/?probe=f005c585bd) | Jun 16, 2022 |
| Gigabyte      | B560M DS3H AC               | [f0b95571fd](https://linux-hardware.org/?probe=f0b95571fd) | Jun 16, 2022 |
| ITI LIMITE... | SMAASH XU3i                 | [549a55efdf](https://linux-hardware.org/?probe=549a55efdf) | Jun 16, 2022 |
| ITI LIMITE... | SMAASH XU3i                 | [693d81e1a3](https://linux-hardware.org/?probe=693d81e1a3) | Jun 16, 2022 |
| HP            | 3031h                       | [00080c0264](https://linux-hardware.org/?probe=00080c0264) | Jun 16, 2022 |
| ASUSTek       | PRIME X570-P                | [4dc736e2b5](https://linux-hardware.org/?probe=4dc736e2b5) | Jun 16, 2022 |
| Lenovo        | 102F SDK0E50510 WIN 2625... | [35c05116d1](https://linux-hardware.org/?probe=35c05116d1) | Jun 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [e8f85ab771](https://linux-hardware.org/?probe=e8f85ab771) | Jun 16, 2022 |
| MSI           | A78M-E45 V2                 | [86394fa5df](https://linux-hardware.org/?probe=86394fa5df) | Jun 16, 2022 |
| MSI           | MPG B550I GAMING EDGE MA... | [69b95cc638](https://linux-hardware.org/?probe=69b95cc638) | Jun 16, 2022 |
| Nvidia        | MCP73                       | [4af86ef214](https://linux-hardware.org/?probe=4af86ef214) | Jun 15, 2022 |
| Nvidia        | MCP73                       | [bc4b2de5bc](https://linux-hardware.org/?probe=bc4b2de5bc) | Jun 15, 2022 |
| Gigabyte      | M68MT-S2                    | [ded75509fb](https://linux-hardware.org/?probe=ded75509fb) | Jun 15, 2022 |
| Lenovo        | 3148 SDK0J40709 WIN 3259... | [8d5ba3c58c](https://linux-hardware.org/?probe=8d5ba3c58c) | Jun 15, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [8bf8ec8bd0](https://linux-hardware.org/?probe=8bf8ec8bd0) | Jun 15, 2022 |
| Acer          | Aspire X1400                | [a90701fd86](https://linux-hardware.org/?probe=a90701fd86) | Jun 15, 2022 |
| MSI           | B550M PRO-VDH               | [9916ed24a9](https://linux-hardware.org/?probe=9916ed24a9) | Jun 15, 2022 |
| ASUSTek       | PRIME A320M-K               | [c8dfb12509](https://linux-hardware.org/?probe=c8dfb12509) | Jun 14, 2022 |
| Medion        | B460H6-EM                   | [b2d8ad91a9](https://linux-hardware.org/?probe=b2d8ad91a9) | Jun 14, 2022 |
| Dell          | 0VD92X A00                  | [4f3e4e102f](https://linux-hardware.org/?probe=4f3e4e102f) | Jun 14, 2022 |
| Dell          | 0VD92X A00                  | [550ed4b1c0](https://linux-hardware.org/?probe=550ed4b1c0) | Jun 14, 2022 |
| Dell          | 0VD92X A00                  | [e6e0165682](https://linux-hardware.org/?probe=e6e0165682) | Jun 14, 2022 |
| ASUSTek       | F2A55-M                     | [845c94e939](https://linux-hardware.org/?probe=845c94e939) | Jun 14, 2022 |
| MSI           | A78M-E45 V2                 | [a2d26ab800](https://linux-hardware.org/?probe=a2d26ab800) | Jun 14, 2022 |
| ASUSTek       | P9X79 PRO                   | [6643e636b5](https://linux-hardware.org/?probe=6643e636b5) | Jun 14, 2022 |
| MSI           | H81M-E33                    | [d6180859a8](https://linux-hardware.org/?probe=d6180859a8) | Jun 14, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [aeb975478b](https://linux-hardware.org/?probe=aeb975478b) | Jun 14, 2022 |
| ASUSTek       | F2A55-M                     | [3cf5e25cca](https://linux-hardware.org/?probe=3cf5e25cca) | Jun 14, 2022 |
| Intel         | DH67BL AAG10189-211         | [15cb74d079](https://linux-hardware.org/?probe=15cb74d079) | Jun 13, 2022 |
| ASUSTek       | PRIME H310M-E               | [f0e0fc8360](https://linux-hardware.org/?probe=f0e0fc8360) | Jun 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [36bf4dc378](https://linux-hardware.org/?probe=36bf4dc378) | Jun 13, 2022 |
| ASRock        | B75M-DGS R2.0               | [457047ad06](https://linux-hardware.org/?probe=457047ad06) | Jun 13, 2022 |
| Acer          | Veriton X2631G V:1.0        | [8f7cca461c](https://linux-hardware.org/?probe=8f7cca461c) | Jun 13, 2022 |
| ASUSTek       | F2A55-M                     | [e6a15fe5a4](https://linux-hardware.org/?probe=e6a15fe5a4) | Jun 13, 2022 |
| ASUSTek       | PRO H410M-C                 | [055ed7de1b](https://linux-hardware.org/?probe=055ed7de1b) | Jun 13, 2022 |
| ASUSTek       | P5KPL/1600                  | [0c6a9f5dff](https://linux-hardware.org/?probe=0c6a9f5dff) | Jun 13, 2022 |
| ASUSTek       | P5KPL/1600                  | [aeec9e715d](https://linux-hardware.org/?probe=aeec9e715d) | Jun 13, 2022 |
| ASRock        | B460M Pro4                  | [603eff18a0](https://linux-hardware.org/?probe=603eff18a0) | Jun 12, 2022 |
| Intel         | DH61CR AAG14064-207         | [a840bbb5a3](https://linux-hardware.org/?probe=a840bbb5a3) | Jun 12, 2022 |
| Dell          | 0XHGV1 A00                  | [6eec9d17a5](https://linux-hardware.org/?probe=6eec9d17a5) | Jun 12, 2022 |
| Gigabyte      | 970A-DS3P                   | [d22ca1b39a](https://linux-hardware.org/?probe=d22ca1b39a) | Jun 12, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [38bf9d2a7b](https://linux-hardware.org/?probe=38bf9d2a7b) | Jun 12, 2022 |
| ASUSTek       | F2A55-M                     | [8f99758eb8](https://linux-hardware.org/?probe=8f99758eb8) | Jun 12, 2022 |
| Intel         | DB75EN AAG39650-400         | [5fa7614020](https://linux-hardware.org/?probe=5fa7614020) | Jun 12, 2022 |
| HP            | 3396                        | [4c0f1563a7](https://linux-hardware.org/?probe=4c0f1563a7) | Jun 12, 2022 |
| MSI           | A68HM-E33 V2                | [b473ea12dc](https://linux-hardware.org/?probe=b473ea12dc) | Jun 12, 2022 |
| Gigabyte      | 970A-DS3P                   | [a3ca1ea153](https://linux-hardware.org/?probe=a3ca1ea153) | Jun 12, 2022 |
| Unknown       | X99-GT                      | [6a36412f6d](https://linux-hardware.org/?probe=6a36412f6d) | Jun 12, 2022 |
| ASUSTek       | H170M-PLUS                  | [416fd6d121](https://linux-hardware.org/?probe=416fd6d121) | Jun 11, 2022 |
| Biostar       | B450MX-S                    | [be9e9c5a99](https://linux-hardware.org/?probe=be9e9c5a99) | Jun 11, 2022 |
| Gigabyte      | B450M DS3H-CF               | [d07617dd7a](https://linux-hardware.org/?probe=d07617dd7a) | Jun 11, 2022 |
| Pegatron      | 2AC3                        | [a93743e1a0](https://linux-hardware.org/?probe=a93743e1a0) | Jun 11, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [a3dcf1b0d6](https://linux-hardware.org/?probe=a3dcf1b0d6) | Jun 11, 2022 |
| Acer          | Veriton X2631G V:1.0        | [943f097be0](https://linux-hardware.org/?probe=943f097be0) | Jun 11, 2022 |
| Unknown       | G41                         | [04e03cb3d5](https://linux-hardware.org/?probe=04e03cb3d5) | Jun 10, 2022 |
| Lenovo        | ThinkServer TS140           | [23515284b5](https://linux-hardware.org/?probe=23515284b5) | Jun 10, 2022 |
| ASUSTek       | P5B-Deluxe                  | [eb7ee3a693](https://linux-hardware.org/?probe=eb7ee3a693) | Jun 10, 2022 |
| ASUSTek       | M5A99X EVO                  | [e54c226fed](https://linux-hardware.org/?probe=e54c226fed) | Jun 10, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [f00af11f1c](https://linux-hardware.org/?probe=f00af11f1c) | Jun 10, 2022 |
| ASUSTek       | PRIME X570-P                | [1e73a95e9e](https://linux-hardware.org/?probe=1e73a95e9e) | Jun 10, 2022 |
| ASUSTek       | P5Q                         | [df07364c28](https://linux-hardware.org/?probe=df07364c28) | Jun 10, 2022 |
| Dell          | 0XHGV1 A00                  | [0de2a3f1a0](https://linux-hardware.org/?probe=0de2a3f1a0) | Jun 10, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [238e30f096](https://linux-hardware.org/?probe=238e30f096) | Jun 10, 2022 |
| Foxconn       | 2AB7                        | [339721d187](https://linux-hardware.org/?probe=339721d187) | Jun 10, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [9deff6136b](https://linux-hardware.org/?probe=9deff6136b) | Jun 10, 2022 |
| Gigabyte      | H61M-DS2                    | [e202a8662f](https://linux-hardware.org/?probe=e202a8662f) | Jun 10, 2022 |
| Gigabyte      | GA-990FXA-UD5               | [b33d07af6c](https://linux-hardware.org/?probe=b33d07af6c) | Jun 09, 2022 |
| Dell          | 0XCR8D A03                  | [7b5fb1809b](https://linux-hardware.org/?probe=7b5fb1809b) | Jun 09, 2022 |
| Dell          | 06JWJY A01                  | [d4675eb5c0](https://linux-hardware.org/?probe=d4675eb5c0) | Jun 09, 2022 |
| Dell          | 0XCR8D A03                  | [08cc695028](https://linux-hardware.org/?probe=08cc695028) | Jun 09, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [bda08758b5](https://linux-hardware.org/?probe=bda08758b5) | Jun 09, 2022 |
| MSI           | A55M-E33                    | [388ba5e3dd](https://linux-hardware.org/?probe=388ba5e3dd) | Jun 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [6d195af721](https://linux-hardware.org/?probe=6d195af721) | Jun 09, 2022 |
| Gigabyte      | 970A-UD3P                   | [7e45eef7ba](https://linux-hardware.org/?probe=7e45eef7ba) | Jun 09, 2022 |
| MSI           | MAG B550M MORTAR            | [40c1095611](https://linux-hardware.org/?probe=40c1095611) | Jun 08, 2022 |
| ASUSTek       | PRIME B350M-A               | [d5f5af27dc](https://linux-hardware.org/?probe=d5f5af27dc) | Jun 08, 2022 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | [36d73de92c](https://linux-hardware.org/?probe=36d73de92c) | Jun 08, 2022 |
| Gigabyte      | F2A55M-HD2                  | [19e1ff0736](https://linux-hardware.org/?probe=19e1ff0736) | Jun 08, 2022 |
| HP            | 1998                        | [362416dfc1](https://linux-hardware.org/?probe=362416dfc1) | Jun 08, 2022 |
| Acer          | Veriton X2631G V:1.0        | [0c5963ea95](https://linux-hardware.org/?probe=0c5963ea95) | Jun 07, 2022 |
| HP            | 8433 11                     | [fa4c4f5c0e](https://linux-hardware.org/?probe=fa4c4f5c0e) | Jun 07, 2022 |
| MSI           | B550-A PRO                  | [13c7b714dc](https://linux-hardware.org/?probe=13c7b714dc) | Jun 07, 2022 |
| Gigabyte      | F2A68HM-S1                  | [017e41e32c](https://linux-hardware.org/?probe=017e41e32c) | Jun 07, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [c443fc775b](https://linux-hardware.org/?probe=c443fc775b) | Jun 07, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [9ab2042d74](https://linux-hardware.org/?probe=9ab2042d74) | Jun 07, 2022 |
| ASRock        | H55M                        | [058eceb951](https://linux-hardware.org/?probe=058eceb951) | Jun 07, 2022 |
| ASUSTek       | PRO H410M-C                 | [fa1a1d1431](https://linux-hardware.org/?probe=fa1a1d1431) | Jun 07, 2022 |
| Gigabyte      | B85M-D2V                    | [fabaa25753](https://linux-hardware.org/?probe=fabaa25753) | Jun 07, 2022 |
| MSI           | H510I PRO WIFI              | [7cb5b3fd8a](https://linux-hardware.org/?probe=7cb5b3fd8a) | Jun 06, 2022 |
| Shuttle       | FS61                        | [4f4bd19a2d](https://linux-hardware.org/?probe=4f4bd19a2d) | Jun 06, 2022 |
| ASUSTek       | PRIME B365M-K               | [0cf459f0db](https://linux-hardware.org/?probe=0cf459f0db) | Jun 06, 2022 |
| Intel         | H61                         | [8178c4da07](https://linux-hardware.org/?probe=8178c4da07) | Jun 06, 2022 |
| MSI           | A68HM-E33                   | [0c4686ca42](https://linux-hardware.org/?probe=0c4686ca42) | Jun 06, 2022 |
| Dell          | 0C2XKD A01                  | [e82c37f339](https://linux-hardware.org/?probe=e82c37f339) | Jun 06, 2022 |
| ASUSTek       | Q87M-E                      | [3c8c0d1998](https://linux-hardware.org/?probe=3c8c0d1998) | Jun 06, 2022 |
| MSI           | A320M-A PRO                 | [488a6e3259](https://linux-hardware.org/?probe=488a6e3259) | Jun 05, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | [0dd5791ff8](https://linux-hardware.org/?probe=0dd5791ff8) | Jun 05, 2022 |
| Dell          | 0200DY A01                  | [00f49d760b](https://linux-hardware.org/?probe=00f49d760b) | Jun 05, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | [1b7a237b9b](https://linux-hardware.org/?probe=1b7a237b9b) | Jun 05, 2022 |
| Dell          | 0HHV7N A00                  | [45bdcd9b5c](https://linux-hardware.org/?probe=45bdcd9b5c) | Jun 05, 2022 |
| Dell          | 0C3YXR A00                  | [5c72365ea3](https://linux-hardware.org/?probe=5c72365ea3) | Jun 05, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX         | [4760e98a1c](https://linux-hardware.org/?probe=4760e98a1c) | Jun 05, 2022 |
| Dell          | 0K3CM7 A00                  | [d90f0bb618](https://linux-hardware.org/?probe=d90f0bb618) | Jun 05, 2022 |
| MSI           | B460M-A PRO                 | [c858bede94](https://linux-hardware.org/?probe=c858bede94) | Jun 05, 2022 |
| Gigabyte      | GA-990FXA-UD3               | [e636b14f58](https://linux-hardware.org/?probe=e636b14f58) | Jun 05, 2022 |
| ASUSTek       | M5A97 R2.0                  | [07468743a9](https://linux-hardware.org/?probe=07468743a9) | Jun 04, 2022 |
| MSI           | B85M-E45                    | [4446978a6f](https://linux-hardware.org/?probe=4446978a6f) | Jun 04, 2022 |
| MSI           | H510I PRO WIFI              | [39d9bd396f](https://linux-hardware.org/?probe=39d9bd396f) | Jun 04, 2022 |
| Shuttle       | DS10U                       | [f2d2634abd](https://linux-hardware.org/?probe=f2d2634abd) | Jun 04, 2022 |
| ASRock        | 870 Extreme3                | [e93db26e8c](https://linux-hardware.org/?probe=e93db26e8c) | Jun 04, 2022 |
| Gigabyte      | Z590 VISION G               | [c91b17ed23](https://linux-hardware.org/?probe=c91b17ed23) | Jun 04, 2022 |
| Biostar       | G41U3G                      | [40d72e8d4a](https://linux-hardware.org/?probe=40d72e8d4a) | Jun 04, 2022 |
| ASUSTek       | PRIME A320M-K               | [5d311a66dc](https://linux-hardware.org/?probe=5d311a66dc) | Jun 04, 2022 |
| Biostar       | G41U3G                      | [d3eb0d0a63](https://linux-hardware.org/?probe=d3eb0d0a63) | Jun 03, 2022 |
| Supermicro    | X10SBA-LA                   | [4b46c69e08](https://linux-hardware.org/?probe=4b46c69e08) | Jun 03, 2022 |
| MSI           | MPG Z390I GAMING EDGE AC    | [a31e1dac27](https://linux-hardware.org/?probe=a31e1dac27) | Jun 03, 2022 |
| ASUSTek       | P8B75-M LE                  | [72008ba457](https://linux-hardware.org/?probe=72008ba457) | Jun 03, 2022 |
| MSI           | A68HM-P33                   | [9dbbf2c6ec](https://linux-hardware.org/?probe=9dbbf2c6ec) | Jun 03, 2022 |
| MSI           | B75MA-E33                   | [cba34d6021](https://linux-hardware.org/?probe=cba34d6021) | Jun 03, 2022 |
| MSI           | A68HM-P33                   | [0590463974](https://linux-hardware.org/?probe=0590463974) | Jun 03, 2022 |
| MSI           | A68HM-P33 V2                | [ff55b171ff](https://linux-hardware.org/?probe=ff55b171ff) | Jun 03, 2022 |
| ASUSTek       | B85M-G                      | [68e585cb49](https://linux-hardware.org/?probe=68e585cb49) | Jun 03, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [eccf357f9f](https://linux-hardware.org/?probe=eccf357f9f) | Jun 03, 2022 |
| Gigabyte      | Z590 VISION G               | [a2a510d9dd](https://linux-hardware.org/?probe=a2a510d9dd) | Jun 03, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [051dd28c75](https://linux-hardware.org/?probe=051dd28c75) | Jun 03, 2022 |
| Gigabyte      | H81M-S1                     | [3210714de1](https://linux-hardware.org/?probe=3210714de1) | Jun 03, 2022 |
| Gigabyte      | H81M-S1                     | [9b01043ab8](https://linux-hardware.org/?probe=9b01043ab8) | Jun 03, 2022 |
| ASRock        | 760GM-HDV                   | [b72f6362e5](https://linux-hardware.org/?probe=b72f6362e5) | Jun 02, 2022 |
| MSI           | B450M-A PRO MAX             | [86be2de304](https://linux-hardware.org/?probe=86be2de304) | Jun 02, 2022 |
| ASUSTek       | B85M-G                      | [c0273d93b6](https://linux-hardware.org/?probe=c0273d93b6) | Jun 02, 2022 |
| MSI           | B450M-A PRO MAX             | [979e6b0d13](https://linux-hardware.org/?probe=979e6b0d13) | Jun 02, 2022 |
| ASUSTek       | H110M-K                     | [e85b6e752d](https://linux-hardware.org/?probe=e85b6e752d) | Jun 02, 2022 |
| ASUSTek       | H81M-K                      | [3fc80d0ef1](https://linux-hardware.org/?probe=3fc80d0ef1) | Jun 02, 2022 |
| MSI           | A68HM-P33                   | [a47c89c432](https://linux-hardware.org/?probe=a47c89c432) | Jun 02, 2022 |
| MSI           | A68HM-P33                   | [6cb525598b](https://linux-hardware.org/?probe=6cb525598b) | Jun 02, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [238f6ecead](https://linux-hardware.org/?probe=238f6ecead) | Jun 02, 2022 |
| ASUSTek       | TUF Z270 MARK 2             | [c8c6c6ca29](https://linux-hardware.org/?probe=c8c6c6ca29) | Jun 02, 2022 |
| ASUSTek       | PRIME A320M-K               | [2a7bfa492d](https://linux-hardware.org/?probe=2a7bfa492d) | Jun 02, 2022 |
| Gigabyte      | Z690 UD DDR4                | [17a0805ec2](https://linux-hardware.org/?probe=17a0805ec2) | Jun 02, 2022 |
| ASUSTek       | PRIME Z690-P WIFI           | [bfd781966f](https://linux-hardware.org/?probe=bfd781966f) | Jun 02, 2022 |
| ASRock        | 760GM-HDV                   | [e116b2ed29](https://linux-hardware.org/?probe=e116b2ed29) | Jun 01, 2022 |
| MSI           | MPG Z390I GAMING EDGE AC    | [db32f9ad3e](https://linux-hardware.org/?probe=db32f9ad3e) | Jun 01, 2022 |
| MSI           | Z77A-G41                    | [8a43bd2e75](https://linux-hardware.org/?probe=8a43bd2e75) | Jun 01, 2022 |
| Gigabyte      | F2A55M-HD2                  | [cb731e1ef2](https://linux-hardware.org/?probe=cb731e1ef2) | Jun 01, 2022 |
| MSI           | A68HM-E33                   | [c784c88156](https://linux-hardware.org/?probe=c784c88156) | Jun 01, 2022 |
| MSI           | A68HM-P33                   | [cf1188fed4](https://linux-hardware.org/?probe=cf1188fed4) | Jun 01, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | [915fbaa0ea](https://linux-hardware.org/?probe=915fbaa0ea) | Jun 01, 2022 |
| ASUSTek       | Z170-P                      | [4684599a3a](https://linux-hardware.org/?probe=4684599a3a) | Jun 01, 2022 |
| ASRock        | H81M-DG4                    | [45dbfa155f](https://linux-hardware.org/?probe=45dbfa155f) | Jun 01, 2022 |
| ASUSTek       | STRIX B250H GAMING          | [9f28088790](https://linux-hardware.org/?probe=9f28088790) | Jun 01, 2022 |
| Alienware     | 0XJKKD A00                  | [ae3a750f2e](https://linux-hardware.org/?probe=ae3a750f2e) | Jun 01, 2022 |
| Intel         | DP67BG AAG10491-305         | [714722d24b](https://linux-hardware.org/?probe=714722d24b) | Jun 01, 2022 |
| MSI           | B250M BAZOOKA               | [45d3300158](https://linux-hardware.org/?probe=45d3300158) | Jun 01, 2022 |
| Dell          | 0NK5PH A00                  | [960e8817bf](https://linux-hardware.org/?probe=960e8817bf) | Jun 01, 2022 |
| Unknown       | SKYBAY                      | [88ef811c4d](https://linux-hardware.org/?probe=88ef811c4d) | May 31, 2022 |
| Pegatron      | 2AED                        | [67df0b1c08](https://linux-hardware.org/?probe=67df0b1c08) | May 31, 2022 |
| Dell          | 07WP95 A02                  | [65ae31976a](https://linux-hardware.org/?probe=65ae31976a) | May 31, 2022 |
| Dell          | 0200DY A01                  | [0d7be8de90](https://linux-hardware.org/?probe=0d7be8de90) | May 31, 2022 |
| MSI           | B450-A PRO MAX              | [72484e859d](https://linux-hardware.org/?probe=72484e859d) | May 31, 2022 |
| Dell          | 0200DY A01                  | [c3c585ba02](https://linux-hardware.org/?probe=c3c585ba02) | May 31, 2022 |
| Unknown       | Unknown                     | [c2d6d647d8](https://linux-hardware.org/?probe=c2d6d647d8) | May 31, 2022 |
| MSI           | B450-A PRO MAX              | [9f7d224ed7](https://linux-hardware.org/?probe=9f7d224ed7) | May 31, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [ab6fb60b96](https://linux-hardware.org/?probe=ab6fb60b96) | May 31, 2022 |
| ASUSTek       | H81M-A                      | [d24672a3cd](https://linux-hardware.org/?probe=d24672a3cd) | May 31, 2022 |
| Intel         | DP67BG AAG10491-305         | [966ab11802](https://linux-hardware.org/?probe=966ab11802) | May 31, 2022 |
| Gigabyte      | Q35M-S2                     | [7ef3498226](https://linux-hardware.org/?probe=7ef3498226) | May 30, 2022 |
| ASRock        | 870 Extreme3                | [7e2000d3a1](https://linux-hardware.org/?probe=7e2000d3a1) | May 30, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [b0e96de917](https://linux-hardware.org/?probe=b0e96de917) | May 30, 2022 |
| ASUSTek       | PRO H410M-C                 | [c40635b66e](https://linux-hardware.org/?probe=c40635b66e) | May 30, 2022 |
| Unknown       | Unknown                     | [59d0634230](https://linux-hardware.org/?probe=59d0634230) | May 30, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [b4f73129a2](https://linux-hardware.org/?probe=b4f73129a2) | May 30, 2022 |
| ASUSTek       | M5A78L LE                   | [44e2ec7714](https://linux-hardware.org/?probe=44e2ec7714) | May 30, 2022 |
| ASUSTek       | X99-E-10G WS                | [83e525ca4e](https://linux-hardware.org/?probe=83e525ca4e) | May 30, 2022 |
| ECS           | MCP61M-M3                   | [b785b68657](https://linux-hardware.org/?probe=b785b68657) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [0b83e8fa79](https://linux-hardware.org/?probe=0b83e8fa79) | May 29, 2022 |
| Intel         | DQ35JO AAD82085-803         | [40429e6d9a](https://linux-hardware.org/?probe=40429e6d9a) | May 29, 2022 |
| Biostar       | G41U3G                      | [1c6caef665](https://linux-hardware.org/?probe=1c6caef665) | May 29, 2022 |
| MSI           | H510I PRO WIFI              | [b4b8c3db64](https://linux-hardware.org/?probe=b4b8c3db64) | May 29, 2022 |
| ASUSTek       | PRO H410M-C                 | [bcca466c5e](https://linux-hardware.org/?probe=bcca466c5e) | May 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [c11ae8de66](https://linux-hardware.org/?probe=c11ae8de66) | May 29, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [c1dd2cf1be](https://linux-hardware.org/?probe=c1dd2cf1be) | May 29, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | [0df520da7e](https://linux-hardware.org/?probe=0df520da7e) | May 29, 2022 |
| ASUSTek       | PRO H410M-C                 | [b83d80f5d2](https://linux-hardware.org/?probe=b83d80f5d2) | May 29, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [7fd1e065eb](https://linux-hardware.org/?probe=7fd1e065eb) | May 29, 2022 |
| Shuttle       | FS81                        | [756f86d9fc](https://linux-hardware.org/?probe=756f86d9fc) | May 28, 2022 |
| Acer          | Veriton X2631G V:1.0        | [3c144d36f0](https://linux-hardware.org/?probe=3c144d36f0) | May 28, 2022 |
| Pegatron      | 2ACF                        | [bd97a6b3dd](https://linux-hardware.org/?probe=bd97a6b3dd) | May 28, 2022 |
| ASUSTek       | H110M-K                     | [9ff7306bbd](https://linux-hardware.org/?probe=9ff7306bbd) | May 28, 2022 |
| Gigabyte      | B150M-D3H-CF                | [e5fdf1083f](https://linux-hardware.org/?probe=e5fdf1083f) | May 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c0399b42b7](https://linux-hardware.org/?probe=c0399b42b7) | May 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | [1094233e96](https://linux-hardware.org/?probe=1094233e96) | May 28, 2022 |
| Dell          | 0C2XKD A01                  | [2aaa53dd85](https://linux-hardware.org/?probe=2aaa53dd85) | May 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | [5458522367](https://linux-hardware.org/?probe=5458522367) | May 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [ce112fb9d2](https://linux-hardware.org/?probe=ce112fb9d2) | May 28, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [bd7aea9bfd](https://linux-hardware.org/?probe=bd7aea9bfd) | May 28, 2022 |
| Acer          | Veriton X2631G V:1.0        | [26e26a3995](https://linux-hardware.org/?probe=26e26a3995) | May 28, 2022 |
| MSI           | B450 TOMAHAWK               | [2651c1881a](https://linux-hardware.org/?probe=2651c1881a) | May 27, 2022 |
| Dell          | 0GXM1W A02                  | [8e0891e3c7](https://linux-hardware.org/?probe=8e0891e3c7) | May 27, 2022 |
| Dell          | 09KPNV A01                  | [b98a471ead](https://linux-hardware.org/?probe=b98a471ead) | May 27, 2022 |
| Dell          | 09KPNV A01                  | [44162ea497](https://linux-hardware.org/?probe=44162ea497) | May 27, 2022 |
| ASUSTek       | P5G41T-M LX                 | [5dbf3199e0](https://linux-hardware.org/?probe=5dbf3199e0) | May 27, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [f5beaba229](https://linux-hardware.org/?probe=f5beaba229) | May 27, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [2624ebd3a1](https://linux-hardware.org/?probe=2624ebd3a1) | May 27, 2022 |
| ASUSTek       | B150-PLUS                   | [bdcda1dabc](https://linux-hardware.org/?probe=bdcda1dabc) | May 27, 2022 |
| Gigabyte      | Z590 VISION G               | [586d86827b](https://linux-hardware.org/?probe=586d86827b) | May 27, 2022 |
| Dell          | 0YJPT1 A00                  | [b122151e55](https://linux-hardware.org/?probe=b122151e55) | May 27, 2022 |
| Gigabyte      | Z77X-UD3H                   | [0cf6ee749e](https://linux-hardware.org/?probe=0cf6ee749e) | May 27, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [f10aecd449](https://linux-hardware.org/?probe=f10aecd449) | May 27, 2022 |
| ASUSTek       | STRIKER II FORMULA          | [df37e5c694](https://linux-hardware.org/?probe=df37e5c694) | May 27, 2022 |
| Dell          | 0MY171 A01                  | [9500786a21](https://linux-hardware.org/?probe=9500786a21) | May 26, 2022 |
| ASUSTek       | PRIME X570-P                | [3774c9e6e6](https://linux-hardware.org/?probe=3774c9e6e6) | May 26, 2022 |
| MSI           | A320M-A PRO MAX             | [f1ccdbbba4](https://linux-hardware.org/?probe=f1ccdbbba4) | May 26, 2022 |
| ASUSTek       | PRIME X570-P                | [f52de609a0](https://linux-hardware.org/?probe=f52de609a0) | May 26, 2022 |
| ASUSTek       | PRO H410M-C                 | [e38c676047](https://linux-hardware.org/?probe=e38c676047) | May 26, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | [9f18dbe621](https://linux-hardware.org/?probe=9f18dbe621) | May 26, 2022 |
| ASRock        | Z270 Gaming K6              | [fbf8e08024](https://linux-hardware.org/?probe=fbf8e08024) | May 25, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | [9d9a7dc189](https://linux-hardware.org/?probe=9d9a7dc189) | May 25, 2022 |
| ASRock        | AB350M Pro4                 | [dd39f18241](https://linux-hardware.org/?probe=dd39f18241) | May 25, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [200070a992](https://linux-hardware.org/?probe=200070a992) | May 25, 2022 |
| Gigabyte      | G31M-S2C                    | [5251ce0950](https://linux-hardware.org/?probe=5251ce0950) | May 25, 2022 |
| Gigabyte      | Z77X-UD3H                   | [0d439f9812](https://linux-hardware.org/?probe=0d439f9812) | May 25, 2022 |
| Dell          | 0DT029 A00                  | [17b19530f5](https://linux-hardware.org/?probe=17b19530f5) | May 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a649429f59](https://linux-hardware.org/?probe=a649429f59) | May 25, 2022 |
| Dell          | 096JG8 A01                  | [51aaf4adcd](https://linux-hardware.org/?probe=51aaf4adcd) | May 24, 2022 |
| Dell          | 0WG864                      | [5bda6fbb3a](https://linux-hardware.org/?probe=5bda6fbb3a) | May 24, 2022 |
| Gigabyte      | P55-UD3L                    | [256b5355c3](https://linux-hardware.org/?probe=256b5355c3) | May 24, 2022 |
| Dell          | 0HY9JP A01                  | [4107e267d7](https://linux-hardware.org/?probe=4107e267d7) | May 24, 2022 |
| Gigabyte      | Z590 VISION G               | [1158b31567](https://linux-hardware.org/?probe=1158b31567) | May 24, 2022 |
| MSI           | H97M-G43                    | [4c1e9752b6](https://linux-hardware.org/?probe=4c1e9752b6) | May 23, 2022 |
| ASUSTek       | PRIME B660M-A AC D4         | [286688e46b](https://linux-hardware.org/?probe=286688e46b) | May 23, 2022 |
| ASRock        | 970 Pro3 R2.0               | [afeae78ecd](https://linux-hardware.org/?probe=afeae78ecd) | May 23, 2022 |
| Shuttle       | FS110                       | [d1147263be](https://linux-hardware.org/?probe=d1147263be) | May 23, 2022 |
| Intel         | H55                         | [8dd80b1c9d](https://linux-hardware.org/?probe=8dd80b1c9d) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | [be78ab6334](https://linux-hardware.org/?probe=be78ab6334) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | [c21c66647d](https://linux-hardware.org/?probe=c21c66647d) | May 23, 2022 |
| ASUSTek       | PRO H410M-C                 | [a700df310a](https://linux-hardware.org/?probe=a700df310a) | May 23, 2022 |
| Intel         | H55                         | [c383403505](https://linux-hardware.org/?probe=c383403505) | May 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | [f5ff0b74e4](https://linux-hardware.org/?probe=f5ff0b74e4) | May 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | [9678842f4f](https://linux-hardware.org/?probe=9678842f4f) | May 23, 2022 |
| Gigabyte      | Z390 UD                     | [d49bf6427c](https://linux-hardware.org/?probe=d49bf6427c) | May 23, 2022 |
| MSI           | 2AE0                        | [ea14a764bb](https://linux-hardware.org/?probe=ea14a764bb) | May 22, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | [ee04d8165a](https://linux-hardware.org/?probe=ee04d8165a) | May 22, 2022 |
| Gigabyte      | Z690 UD DDR4                | [85ec601970](https://linux-hardware.org/?probe=85ec601970) | May 22, 2022 |
| ASRock        | 760GM-HDV                   | [a7c99d7f14](https://linux-hardware.org/?probe=a7c99d7f14) | May 22, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [70c677bafe](https://linux-hardware.org/?probe=70c677bafe) | May 22, 2022 |
| ASRock        | 760GM-HDV                   | [a37dd040cc](https://linux-hardware.org/?probe=a37dd040cc) | May 22, 2022 |
| Gigabyte      | Z690 UD DDR4                | [1ceb70430f](https://linux-hardware.org/?probe=1ceb70430f) | May 22, 2022 |
| MSI           | Z97 GAMING 3                | [495bcbd710](https://linux-hardware.org/?probe=495bcbd710) | May 22, 2022 |
| Shuttle       | FS110                       | [4845946b59](https://linux-hardware.org/?probe=4845946b59) | May 22, 2022 |
| HP            | 18E4                        | [e8bc371de1](https://linux-hardware.org/?probe=e8bc371de1) | May 22, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [5f03a4b52d](https://linux-hardware.org/?probe=5f03a4b52d) | May 21, 2022 |
| Gigabyte      | G41MT-D3                    | [aac14b5554](https://linux-hardware.org/?probe=aac14b5554) | May 21, 2022 |
| ASRock        | AB350M-HDV R3.0             | [01fcce62c6](https://linux-hardware.org/?probe=01fcce62c6) | May 21, 2022 |
| Gigabyte      | G41MT-D3                    | [6763ad45ce](https://linux-hardware.org/?probe=6763ad45ce) | May 21, 2022 |
| ASUSTek       | Crosshair IV Formula        | [d6c9df82c6](https://linux-hardware.org/?probe=d6c9df82c6) | May 21, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [cedcf3fa98](https://linux-hardware.org/?probe=cedcf3fa98) | May 21, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | [72560a6e0c](https://linux-hardware.org/?probe=72560a6e0c) | May 21, 2022 |
| HP            | 18E4                        | [e567895819](https://linux-hardware.org/?probe=e567895819) | May 21, 2022 |
| ASUSTek       | P7H55-M LX                  | [72a96fc8a3](https://linux-hardware.org/?probe=72a96fc8a3) | May 20, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [73c9c54bb6](https://linux-hardware.org/?probe=73c9c54bb6) | May 20, 2022 |
| Medion        | H81H3-EM2                   | [ba616a92bf](https://linux-hardware.org/?probe=ba616a92bf) | May 20, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | [7dcdef576a](https://linux-hardware.org/?probe=7dcdef576a) | May 20, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [162c85f06d](https://linux-hardware.org/?probe=162c85f06d) | May 20, 2022 |
| Gigabyte      | Z590 VISION G               | [6e7143bfd4](https://linux-hardware.org/?probe=6e7143bfd4) | May 20, 2022 |
| Gigabyte      | Z77X-UP7                    | [8b4b27f72d](https://linux-hardware.org/?probe=8b4b27f72d) | May 20, 2022 |
| Dell          | 09M8Y8 A01                  | [f4894739f4](https://linux-hardware.org/?probe=f4894739f4) | May 20, 2022 |
| HP            | 8767 A                      | [a1b50431fa](https://linux-hardware.org/?probe=a1b50431fa) | May 19, 2022 |
| MSI           | MPG B550I GAMING EDGE MA... | [407d3e4f43](https://linux-hardware.org/?probe=407d3e4f43) | May 19, 2022 |
| Intel         | ChiefRiver                  | [8e4aca2b1f](https://linux-hardware.org/?probe=8e4aca2b1f) | May 19, 2022 |
| Intel         | ChiefRiver                  | [4d38806404](https://linux-hardware.org/?probe=4d38806404) | May 19, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [6a9166ca20](https://linux-hardware.org/?probe=6a9166ca20) | May 19, 2022 |
| Dell          | 0HY9JP A01                  | [d845952849](https://linux-hardware.org/?probe=d845952849) | May 19, 2022 |
| Gigabyte      | AX370M-DS3H-CF              | [39fb6cd4e3](https://linux-hardware.org/?probe=39fb6cd4e3) | May 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | [b2eceeef6d](https://linux-hardware.org/?probe=b2eceeef6d) | May 19, 2022 |
| ASUSTek       | PRIME B360M-D               | [6a00f5f597](https://linux-hardware.org/?probe=6a00f5f597) | May 18, 2022 |
| ECS           | GF7050VT-M5                 | [485f780320](https://linux-hardware.org/?probe=485f780320) | May 18, 2022 |
| ASUSTek       | M5A88-V EVO                 | [ab5a307891](https://linux-hardware.org/?probe=ab5a307891) | May 18, 2022 |
| ASUSTek       | PRIME B450M-K               | [54f3323bd2](https://linux-hardware.org/?probe=54f3323bd2) | May 18, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [eaea352b1a](https://linux-hardware.org/?probe=eaea352b1a) | May 18, 2022 |
| Foxconn       | 2ADA                        | [60579b7d68](https://linux-hardware.org/?probe=60579b7d68) | May 18, 2022 |
| Gigabyte      | Z370 AORUS ULTRA GAMING-... | [ea23b1fec2](https://linux-hardware.org/?probe=ea23b1fec2) | May 18, 2022 |
| MSI           | A320M-A PRO MAX             | [13bacdb7b6](https://linux-hardware.org/?probe=13bacdb7b6) | May 18, 2022 |
| ASRock        | FM2A68M-DG3+                | [a1b9d7e608](https://linux-hardware.org/?probe=a1b9d7e608) | May 18, 2022 |
| ASUSTek       | PRIME B450M-K               | [1dba88e243](https://linux-hardware.org/?probe=1dba88e243) | May 18, 2022 |
| ASUSTek       | F2A85-M PRO                 | [99e949c3e8](https://linux-hardware.org/?probe=99e949c3e8) | May 18, 2022 |
| Dell          | 0HN7XN A00                  | [6fba9a10da](https://linux-hardware.org/?probe=6fba9a10da) | May 18, 2022 |
| ASUSTek       | P8H61 PRO                   | [87a148ac90](https://linux-hardware.org/?probe=87a148ac90) | May 18, 2022 |
| ASUSTek       | PRIME A320M-K               | [cb6038cd9b](https://linux-hardware.org/?probe=cb6038cd9b) | May 18, 2022 |
| ASUSTek       | A8N32-SLI-Deluxe            | [78a9ab4d15](https://linux-hardware.org/?probe=78a9ab4d15) | May 17, 2022 |
| ASRock        | 970M Pro3                   | [f08826b5b4](https://linux-hardware.org/?probe=f08826b5b4) | May 17, 2022 |
| HP            | 22F8                        | [70f6561c5c](https://linux-hardware.org/?probe=70f6561c5c) | May 16, 2022 |
| ASUSTek       | PRO H410M-C                 | [1b0cb5afca](https://linux-hardware.org/?probe=1b0cb5afca) | May 16, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [3bf7390ce3](https://linux-hardware.org/?probe=3bf7390ce3) | May 16, 2022 |
| ASUSTek       | M3N78 PRO                   | [246f442b9b](https://linux-hardware.org/?probe=246f442b9b) | May 15, 2022 |
| Gigabyte      | Z690 UD DDR4                | [e2ed8b47c2](https://linux-hardware.org/?probe=e2ed8b47c2) | May 15, 2022 |
| ASRock        | 970 Pro3 R2.0               | [5ad0b4a6c6](https://linux-hardware.org/?probe=5ad0b4a6c6) | May 15, 2022 |
| Acer          | H57M01                      | [9116ecebcb](https://linux-hardware.org/?probe=9116ecebcb) | May 15, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [d4e303b92c](https://linux-hardware.org/?probe=d4e303b92c) | May 15, 2022 |
| Gigabyte      | H110M-S2-CF                 | [a2fa413622](https://linux-hardware.org/?probe=a2fa413622) | May 15, 2022 |
| ASUSTek       | M3N78 PRO                   | [af5eec886b](https://linux-hardware.org/?probe=af5eec886b) | May 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [021f95ce24](https://linux-hardware.org/?probe=021f95ce24) | May 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9ce2f8b28b](https://linux-hardware.org/?probe=9ce2f8b28b) | May 15, 2022 |
| Gigabyte      | PH67A-D3-B3                 | [e819cbe6f7](https://linux-hardware.org/?probe=e819cbe6f7) | May 15, 2022 |
| ASRock        | 970M Pro3                   | [5f67a595f4](https://linux-hardware.org/?probe=5f67a595f4) | May 15, 2022 |
| ASUSTek       | Z170I PRO GAMING            | [a58685906f](https://linux-hardware.org/?probe=a58685906f) | May 15, 2022 |
| MSI           | PRO Z690-A DDR4             | [5ce4d54b58](https://linux-hardware.org/?probe=5ce4d54b58) | May 14, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [d7f98d5384](https://linux-hardware.org/?probe=d7f98d5384) | May 14, 2022 |
| Gigabyte      | X570S AORUS MASTER          | [b061586ff0](https://linux-hardware.org/?probe=b061586ff0) | May 14, 2022 |
| Gigabyte      | PH67A-D3-B3                 | [a292b16ff7](https://linux-hardware.org/?probe=a292b16ff7) | May 14, 2022 |
| ASUSTek       | Z97-P                       | [3fc95850aa](https://linux-hardware.org/?probe=3fc95850aa) | May 14, 2022 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | [975e7a6b47](https://linux-hardware.org/?probe=975e7a6b47) | May 14, 2022 |
| Acer          | H57M01                      | [42100344af](https://linux-hardware.org/?probe=42100344af) | May 14, 2022 |
| Intel         | X99 V1.0                    | [554b088978](https://linux-hardware.org/?probe=554b088978) | May 14, 2022 |
| Acer          | Veriton M670G               | [a583d3a342](https://linux-hardware.org/?probe=a583d3a342) | May 13, 2022 |
| Gigabyte      | X58A-UD3R                   | [0e9a009c11](https://linux-hardware.org/?probe=0e9a009c11) | May 13, 2022 |
| MSI           | B550M PRO-VDH               | [fd15b34806](https://linux-hardware.org/?probe=fd15b34806) | May 13, 2022 |
| Shuttle       | DS10U                       | [2f2acb55e9](https://linux-hardware.org/?probe=2f2acb55e9) | May 13, 2022 |
| Intel         | DH67BL AAG10189-210         | [2340d530cd](https://linux-hardware.org/?probe=2340d530cd) | May 13, 2022 |
| Gigabyte      | X58A-UD3R                   | [ed659a9633](https://linux-hardware.org/?probe=ed659a9633) | May 13, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [3fe223176c](https://linux-hardware.org/?probe=3fe223176c) | May 13, 2022 |
| Acer          | Aspire X3400                | [9dd76b4599](https://linux-hardware.org/?probe=9dd76b4599) | May 13, 2022 |
| Acer          | Aspire X3400                | [b590b149fc](https://linux-hardware.org/?probe=b590b149fc) | May 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a2e10758ca](https://linux-hardware.org/?probe=a2e10758ca) | May 13, 2022 |
| Dell          | 0773VG A02                  | [0743f4573d](https://linux-hardware.org/?probe=0743f4573d) | May 12, 2022 |
| Dell          | 0HY9JP A01                  | [0026740e3f](https://linux-hardware.org/?probe=0026740e3f) | May 12, 2022 |
| Shuttle       | FH87                        | [42cb5c0ef7](https://linux-hardware.org/?probe=42cb5c0ef7) | May 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [91404c39c7](https://linux-hardware.org/?probe=91404c39c7) | May 12, 2022 |
| ASUSTek       | P8H61                       | [d2b843c446](https://linux-hardware.org/?probe=d2b843c446) | May 12, 2022 |
| HP            | 0AECh D                     | [68adfe0740](https://linux-hardware.org/?probe=68adfe0740) | May 12, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [578328d0b5](https://linux-hardware.org/?probe=578328d0b5) | May 12, 2022 |
| Unknown       | Unknown                     | [7931f8191f](https://linux-hardware.org/?probe=7931f8191f) | May 11, 2022 |
| Unknown       | Unknown                     | [271a8ba23e](https://linux-hardware.org/?probe=271a8ba23e) | May 11, 2022 |
| MSI           | Z97S SLI Krait Edition      | [861cbb7b6e](https://linux-hardware.org/?probe=861cbb7b6e) | May 11, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [14f5c24c81](https://linux-hardware.org/?probe=14f5c24c81) | May 11, 2022 |
| Dell          | 0WMJ54 A00                  | [393406b0e8](https://linux-hardware.org/?probe=393406b0e8) | May 11, 2022 |
| Gigabyte      | Z590 VISION G               | [0e12a4aa26](https://linux-hardware.org/?probe=0e12a4aa26) | May 11, 2022 |
| Intel         | B75                         | [d2a9132d48](https://linux-hardware.org/?probe=d2a9132d48) | May 11, 2022 |
| ASUSTek       | H61M-K                      | [64f2ed4df2](https://linux-hardware.org/?probe=64f2ed4df2) | May 11, 2022 |
| ASRock        | B550 Steel Legend           | [a940d31b37](https://linux-hardware.org/?probe=a940d31b37) | May 10, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [74862d462d](https://linux-hardware.org/?probe=74862d462d) | May 10, 2022 |
| Gigabyte      | H97N                        | [21f1bf0f0c](https://linux-hardware.org/?probe=21f1bf0f0c) | May 10, 2022 |
| ASRock        | J4105B-ITX                  | [6e507d9a68](https://linux-hardware.org/?probe=6e507d9a68) | May 09, 2022 |
| ECS           | A68M-C4DL                   | [b8c60cf7a0](https://linux-hardware.org/?probe=b8c60cf7a0) | May 09, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [05b7c2c72c](https://linux-hardware.org/?probe=05b7c2c72c) | May 09, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [a9e6ecf483](https://linux-hardware.org/?probe=a9e6ecf483) | May 09, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | [7987b700d5](https://linux-hardware.org/?probe=7987b700d5) | May 09, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [b57ce8e7e1](https://linux-hardware.org/?probe=b57ce8e7e1) | May 09, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [b3cac7c464](https://linux-hardware.org/?probe=b3cac7c464) | May 09, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [38e20673c2](https://linux-hardware.org/?probe=38e20673c2) | May 09, 2022 |
| ASRock        | J4105B-ITX                  | [c4eea9f630](https://linux-hardware.org/?probe=c4eea9f630) | May 09, 2022 |
| Intel         | H61                         | [3f5d8ae941](https://linux-hardware.org/?probe=3f5d8ae941) | May 09, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [89f0b017b1](https://linux-hardware.org/?probe=89f0b017b1) | May 09, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [bd7335e1cd](https://linux-hardware.org/?probe=bd7335e1cd) | May 09, 2022 |
| ASUSTek       | Pro WS C621-64L SAGE-10G... | [4ebf4d9cc8](https://linux-hardware.org/?probe=4ebf4d9cc8) | May 09, 2022 |
| Gigabyte      | Z97X-Gaming 5               | [77145b587d](https://linux-hardware.org/?probe=77145b587d) | May 09, 2022 |
| Gigabyte      | Z97X-Gaming 5               | [e3f65dec10](https://linux-hardware.org/?probe=e3f65dec10) | May 09, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [422c9f9cae](https://linux-hardware.org/?probe=422c9f9cae) | May 09, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | [344bc071a2](https://linux-hardware.org/?probe=344bc071a2) | May 09, 2022 |
| HP            | 1998                        | [bb8d501109](https://linux-hardware.org/?probe=bb8d501109) | May 09, 2022 |
| ASUSTek       | P5Q SE/R                    | [c99b0a0683](https://linux-hardware.org/?probe=c99b0a0683) | May 08, 2022 |
| Acer          | Revo RL80                   | [c48857049a](https://linux-hardware.org/?probe=c48857049a) | May 08, 2022 |
| Pegatron      | Eureka3                     | [e383533179](https://linux-hardware.org/?probe=e383533179) | May 08, 2022 |
| Gigabyte      | Z170X-GamingG1              | [28fc5f92bc](https://linux-hardware.org/?probe=28fc5f92bc) | May 08, 2022 |
| HP            | 870C                        | [adb470192a](https://linux-hardware.org/?probe=adb470192a) | May 08, 2022 |
| ASUSTek       | Z170-A                      | [abccbed349](https://linux-hardware.org/?probe=abccbed349) | May 08, 2022 |
| ASUSTek       | P8H77-V LE                  | [acf562b58b](https://linux-hardware.org/?probe=acf562b58b) | May 08, 2022 |
| ASUSTek       | P8H77-V LE                  | [1a3e2da376](https://linux-hardware.org/?probe=1a3e2da376) | May 08, 2022 |
| ASUSTek       | Z170-A                      | [97e2613936](https://linux-hardware.org/?probe=97e2613936) | May 08, 2022 |
| ASUSTek       | PRIME B360M-A               | [c589ad9143](https://linux-hardware.org/?probe=c589ad9143) | May 07, 2022 |
| ASUSTek       | P8B75-M                     | [6371d77b5d](https://linux-hardware.org/?probe=6371d77b5d) | May 07, 2022 |
| Pegatron      | 2AC3                        | [d2932b8b78](https://linux-hardware.org/?probe=d2932b8b78) | May 07, 2022 |
| Dell          | 0WMJ54 A01                  | [58b3a1b83d](https://linux-hardware.org/?probe=58b3a1b83d) | May 07, 2022 |
| Dell          | 00V62H A00                  | [5c5f2f2b5c](https://linux-hardware.org/?probe=5c5f2f2b5c) | May 07, 2022 |
| Medion        | B460H6-EM                   | [e2abcd94ce](https://linux-hardware.org/?probe=e2abcd94ce) | May 06, 2022 |
| Lenovo        | 0B98401 WIN                 | [b080a2bae5](https://linux-hardware.org/?probe=b080a2bae5) | May 06, 2022 |
| HP            | 1495                        | [4b63b733be](https://linux-hardware.org/?probe=4b63b733be) | May 06, 2022 |
| Lenovo        | NO DPK                      | [24340ea9a8](https://linux-hardware.org/?probe=24340ea9a8) | May 06, 2022 |
| Google        | Panther                     | [4b7366ed94](https://linux-hardware.org/?probe=4b7366ed94) | May 06, 2022 |
| ASRock        | B85M DASH/OL R2.0           | [61c86467ba](https://linux-hardware.org/?probe=61c86467ba) | May 06, 2022 |
| MSI           | B550M PRO-VDH               | [40f4bf344a](https://linux-hardware.org/?probe=40f4bf344a) | May 05, 2022 |
| Supermicro    | X8ST3                       | [3cab505f0a](https://linux-hardware.org/?probe=3cab505f0a) | May 05, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [7b488333bb](https://linux-hardware.org/?probe=7b488333bb) | May 05, 2022 |
| ASUSTek       | Z97-K                       | [f03b0f28ef](https://linux-hardware.org/?probe=f03b0f28ef) | May 05, 2022 |
| MSI           | 770-C45                     | [0e9179888b](https://linux-hardware.org/?probe=0e9179888b) | May 05, 2022 |
| Lenovo        | NO DPK                      | [dc8d8b070e](https://linux-hardware.org/?probe=dc8d8b070e) | May 05, 2022 |
| MSI           | Z390-A PRO                  | [145317db95](https://linux-hardware.org/?probe=145317db95) | May 05, 2022 |
| MSI           | H55M-E23                    | [d42084b294](https://linux-hardware.org/?probe=d42084b294) | May 04, 2022 |
| ASUSTek       | Maximus VI HERO             | [540a55671c](https://linux-hardware.org/?probe=540a55671c) | May 04, 2022 |
| Gigabyte      | X99-UD4-CF                  | [d5cd65ba5b](https://linux-hardware.org/?probe=d5cd65ba5b) | May 04, 2022 |
| Lenovo        | 0B98401 WIN                 | [180a5d086f](https://linux-hardware.org/?probe=180a5d086f) | May 04, 2022 |
| Lenovo        | 0B98401 WIN                 | [f47683cd76](https://linux-hardware.org/?probe=f47683cd76) | May 04, 2022 |
| ASUSTek       | PRIME B360-PLUS             | [4ce66ff579](https://linux-hardware.org/?probe=4ce66ff579) | May 04, 2022 |
| Gigabyte      | H110M-S2-CF                 | [156de9d4de](https://linux-hardware.org/?probe=156de9d4de) | May 04, 2022 |
| ASUSTek       | Z97M-PLUS                   | [c2ab1a3ec2](https://linux-hardware.org/?probe=c2ab1a3ec2) | May 04, 2022 |
| Gigabyte      | B75M-HD3                    | [7dc76bf420](https://linux-hardware.org/?probe=7dc76bf420) | May 04, 2022 |
| ASUSTek       | B150M PRO GAMING            | [a31ab08668](https://linux-hardware.org/?probe=a31ab08668) | May 04, 2022 |
| Dell          | 0Y56T3 A00                  | [3bdd958639](https://linux-hardware.org/?probe=3bdd958639) | May 04, 2022 |
| Dell          | 0P301D A02                  | [ab9edfbc39](https://linux-hardware.org/?probe=ab9edfbc39) | May 03, 2022 |
| Acer          | FX58M                       | [0a6673afb9](https://linux-hardware.org/?probe=0a6673afb9) | May 03, 2022 |
| Gigabyte      | H110-D3A-CF                 | [74e69f5610](https://linux-hardware.org/?probe=74e69f5610) | May 03, 2022 |
| Shuttle       | FG41 V20                    | [fd07bdf7b5](https://linux-hardware.org/?probe=fd07bdf7b5) | May 02, 2022 |
| Dell          | 0M017G A00                  | [93884340db](https://linux-hardware.org/?probe=93884340db) | May 02, 2022 |
| Alienware     | 07JNH0 A02                  | [d39a57aed6](https://linux-hardware.org/?probe=d39a57aed6) | May 02, 2022 |
| ASUSTek       | PRIME B450M-A               | [bbbfaa9157](https://linux-hardware.org/?probe=bbbfaa9157) | May 02, 2022 |
| Dell          | 09M8Y8 A01                  | [301694185a](https://linux-hardware.org/?probe=301694185a) | May 02, 2022 |
| Dell          | 0HHV7N A00                  | [7636489d8e](https://linux-hardware.org/?probe=7636489d8e) | May 01, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [965ebad5cb](https://linux-hardware.org/?probe=965ebad5cb) | May 01, 2022 |
| MSI           | A320M-A PRO MAX             | [c396021a33](https://linux-hardware.org/?probe=c396021a33) | May 01, 2022 |
| Gigabyte      | B365M DS3H                  | [cc016ce0c5](https://linux-hardware.org/?probe=cc016ce0c5) | May 01, 2022 |
| ASUSTek       | H61M-K                      | [fbbae98a18](https://linux-hardware.org/?probe=fbbae98a18) | May 01, 2022 |
| Gigabyte      | Z77X-UD3H                   | [f30bbca593](https://linux-hardware.org/?probe=f30bbca593) | May 01, 2022 |
| ASUSTek       | P5B                         | [39c9900546](https://linux-hardware.org/?probe=39c9900546) | May 01, 2022 |
| Positivo      | POS-ECIG41BSA               | [b622f7f43f](https://linux-hardware.org/?probe=b622f7f43f) | Apr 30, 2022 |
| Medion        | MS-7616                     | [f3572ea9a5](https://linux-hardware.org/?probe=f3572ea9a5) | Apr 30, 2022 |
| Gigabyte      | H61M-DS2 x.x                | [463e99eb8c](https://linux-hardware.org/?probe=463e99eb8c) | Apr 30, 2022 |
| MSI           | X570-A PRO                  | [ff568c874c](https://linux-hardware.org/?probe=ff568c874c) | Apr 30, 2022 |
| Gigabyte      | B365M DS3H                  | [f140b54261](https://linux-hardware.org/?probe=f140b54261) | Apr 30, 2022 |
| Gigabyte      | B550M DS3H                  | [f62d8963d7](https://linux-hardware.org/?probe=f62d8963d7) | Apr 30, 2022 |
| ASRock        | B75M-ITX                    | [dbc851e0d3](https://linux-hardware.org/?probe=dbc851e0d3) | Apr 30, 2022 |
| HP            | 3396                        | [468c2975ee](https://linux-hardware.org/?probe=468c2975ee) | Apr 30, 2022 |
| Huanan        | X99-BD4 V/OPCZAO            | [2f215a330a](https://linux-hardware.org/?probe=2f215a330a) | Apr 30, 2022 |
| MSI           | B550-A PRO                  | [0b23621ed1](https://linux-hardware.org/?probe=0b23621ed1) | Apr 30, 2022 |
| MSI           | A88XM-E45 V2                | [a50ad068b1](https://linux-hardware.org/?probe=a50ad068b1) | Apr 30, 2022 |
| Gigabyte      | B550M DS3H                  | [7797c23169](https://linux-hardware.org/?probe=7797c23169) | Apr 30, 2022 |
| MSI           | A320M PRO-E                 | [655905bb3b](https://linux-hardware.org/?probe=655905bb3b) | Apr 29, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [fe522bdf2e](https://linux-hardware.org/?probe=fe522bdf2e) | Apr 29, 2022 |
| ASUSTek       | M5A97 LE R2.0               | [686f4acac4](https://linux-hardware.org/?probe=686f4acac4) | Apr 29, 2022 |
| ASUSTek       | Rampage IV EXTREME          | [111d072676](https://linux-hardware.org/?probe=111d072676) | Apr 29, 2022 |
| Dell          | 07WP95 A02                  | [8dd4d42608](https://linux-hardware.org/?probe=8dd4d42608) | Apr 29, 2022 |
| Huanan        | X99-BD4 V/OPCZAO            | [a5743a1922](https://linux-hardware.org/?probe=a5743a1922) | Apr 29, 2022 |
| Pepper Job... | GLK-UC2X                    | [28495f32bd](https://linux-hardware.org/?probe=28495f32bd) | Apr 29, 2022 |
| Alienware     | 07W25T A00                  | [b989838f70](https://linux-hardware.org/?probe=b989838f70) | Apr 29, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | [27df4d83ea](https://linux-hardware.org/?probe=27df4d83ea) | Apr 29, 2022 |
| ASUSTek       | PRIME B360M-A               | [519ed87066](https://linux-hardware.org/?probe=519ed87066) | Apr 29, 2022 |
| ASUSTek       | PRIME B360M-A               | [c46a1d595b](https://linux-hardware.org/?probe=c46a1d595b) | Apr 29, 2022 |
| MSI           | A78M-E35                    | [8f9bf75a08](https://linux-hardware.org/?probe=8f9bf75a08) | Apr 29, 2022 |
| ASUSTek       | Z87-WS                      | [1c67952875](https://linux-hardware.org/?probe=1c67952875) | Apr 29, 2022 |
| MSI           | X470 GAMING PLUS MAX        | [d291472a69](https://linux-hardware.org/?probe=d291472a69) | Apr 28, 2022 |
| ASRock        | H61M-VG4                    | [92f92ef4ee](https://linux-hardware.org/?probe=92f92ef4ee) | Apr 28, 2022 |
| ASRock        | B450M Pro4                  | [773f69d63b](https://linux-hardware.org/?probe=773f69d63b) | Apr 28, 2022 |
| ASUSTek       | M5A78L LE                   | [96739891ab](https://linux-hardware.org/?probe=96739891ab) | Apr 28, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [919872f97b](https://linux-hardware.org/?probe=919872f97b) | Apr 28, 2022 |
| ASRock        | B450M Pro4                  | [2943b21899](https://linux-hardware.org/?probe=2943b21899) | Apr 28, 2022 |
| MSI           | B450M PRO-VDH PLUS          | [c4f91167bb](https://linux-hardware.org/?probe=c4f91167bb) | Apr 27, 2022 |
| MSI           | B550M PRO-VDH WIFI          | [b923126955](https://linux-hardware.org/?probe=b923126955) | Apr 27, 2022 |
| ASUSTek       | H110M-A/M.2                 | [4c6852d631](https://linux-hardware.org/?probe=4c6852d631) | Apr 27, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [f06ce3d416](https://linux-hardware.org/?probe=f06ce3d416) | Apr 27, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [a3f49d1a04](https://linux-hardware.org/?probe=a3f49d1a04) | Apr 27, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [b47f678ce9](https://linux-hardware.org/?probe=b47f678ce9) | Apr 27, 2022 |
| ASRock        | H61M-VG4                    | [fff58f97e8](https://linux-hardware.org/?probe=fff58f97e8) | Apr 27, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [3c53a0e59d](https://linux-hardware.org/?probe=3c53a0e59d) | Apr 27, 2022 |
| Gigabyte      | H61M-S2PV                   | [f09766a481](https://linux-hardware.org/?probe=f09766a481) | Apr 27, 2022 |
| HP            | 22F8                        | [eb4d49a17b](https://linux-hardware.org/?probe=eb4d49a17b) | Apr 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [56da721176](https://linux-hardware.org/?probe=56da721176) | Apr 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [1619af58d4](https://linux-hardware.org/?probe=1619af58d4) | Apr 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [3c6aace75c](https://linux-hardware.org/?probe=3c6aace75c) | Apr 27, 2022 |
| MSI           | 880GMA-E35                  | [6ff68166f7](https://linux-hardware.org/?probe=6ff68166f7) | Apr 26, 2022 |
| Dell          | 0WR7PY A03                  | [4ac0a4dff1](https://linux-hardware.org/?probe=4ac0a4dff1) | Apr 26, 2022 |
| Dell          | 0VNM11 A00                  | [6aae7c23ad](https://linux-hardware.org/?probe=6aae7c23ad) | Apr 26, 2022 |
| MSI           | A320M-A PRO MAX             | [e06fd46729](https://linux-hardware.org/?probe=e06fd46729) | Apr 26, 2022 |
| Biostar       | J3160NH                     | [8ffd3a1aa4](https://linux-hardware.org/?probe=8ffd3a1aa4) | Apr 26, 2022 |
| MSI           | Z68A-GD80                   | [fedca9082a](https://linux-hardware.org/?probe=fedca9082a) | Apr 25, 2022 |
| ASUSTek       | H81M-V3                     | [4d87f6f113](https://linux-hardware.org/?probe=4d87f6f113) | Apr 25, 2022 |
| Gigabyte      | P55M-UD2                    | [5f9ffc8d46](https://linux-hardware.org/?probe=5f9ffc8d46) | Apr 24, 2022 |
| Dell          | 0GXM1W A02                  | [6564561a75](https://linux-hardware.org/?probe=6564561a75) | Apr 24, 2022 |
| ASRock        | Z170 Gaming K4              | [96b772b4e6](https://linux-hardware.org/?probe=96b772b4e6) | Apr 24, 2022 |
| Acer          | FX58M                       | [3074ddb372](https://linux-hardware.org/?probe=3074ddb372) | Apr 24, 2022 |
| Dell          | 0GXM1W A02                  | [af6b49b2a5](https://linux-hardware.org/?probe=af6b49b2a5) | Apr 24, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | [e0e448efcb](https://linux-hardware.org/?probe=e0e448efcb) | Apr 24, 2022 |
| ASUSTek       | F2A85-M PRO                 | [e0298dd8f0](https://linux-hardware.org/?probe=e0298dd8f0) | Apr 24, 2022 |
| HP            | 21EF                        | [9e37979ea3](https://linux-hardware.org/?probe=9e37979ea3) | Apr 23, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | [929f99800a](https://linux-hardware.org/?probe=929f99800a) | Apr 23, 2022 |
| Dell          | 00V62H A00                  | [2da43c32a4](https://linux-hardware.org/?probe=2da43c32a4) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | [3b01c4a4a5](https://linux-hardware.org/?probe=3b01c4a4a5) | Apr 23, 2022 |
| MSI           | MS-1T11                     | [9c16a631ef](https://linux-hardware.org/?probe=9c16a631ef) | Apr 23, 2022 |
| MSI           | MS-1T11                     | [e263cd80f5](https://linux-hardware.org/?probe=e263cd80f5) | Apr 23, 2022 |
| HP            | 22F8                        | [67dc13d1ad](https://linux-hardware.org/?probe=67dc13d1ad) | Apr 23, 2022 |
| ASUSTek       | PRIME B560-PLUS             | [8e31efa5fa](https://linux-hardware.org/?probe=8e31efa5fa) | Apr 23, 2022 |
| Dell          | 088DT1 A01                  | [9e72ff0940](https://linux-hardware.org/?probe=9e72ff0940) | Apr 22, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | [d35c4838f2](https://linux-hardware.org/?probe=d35c4838f2) | Apr 22, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | [61e0546ed7](https://linux-hardware.org/?probe=61e0546ed7) | Apr 22, 2022 |
| ASRock        | Z370 Pro4-IB                | [c0c51e4d53](https://linux-hardware.org/?probe=c0c51e4d53) | Apr 22, 2022 |
| Dell          | 0HD5W2 A00                  | [ddfd89e9dc](https://linux-hardware.org/?probe=ddfd89e9dc) | Apr 22, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | [a76e953825](https://linux-hardware.org/?probe=a76e953825) | Apr 22, 2022 |
| MSI           | MAG B460 TOMAHAWK           | [8ef18c7ea4](https://linux-hardware.org/?probe=8ef18c7ea4) | Apr 21, 2022 |
| HP            | 8054                        | [f9ec7b0896](https://linux-hardware.org/?probe=f9ec7b0896) | Apr 21, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | [b84eab559e](https://linux-hardware.org/?probe=b84eab559e) | Apr 21, 2022 |
| Gigabyte      | B450M GAMING                | [bf31ebdabe](https://linux-hardware.org/?probe=bf31ebdabe) | Apr 21, 2022 |
| MSI           | Z97 GAMING 5                | [a6bd59cad3](https://linux-hardware.org/?probe=a6bd59cad3) | Apr 20, 2022 |
| ASRock        | X470 Taichi Ultimate        | [d10be6941f](https://linux-hardware.org/?probe=d10be6941f) | Apr 20, 2022 |
| ASRock        | X470 Taichi Ultimate        | [a92dda8ded](https://linux-hardware.org/?probe=a92dda8ded) | Apr 20, 2022 |
| MSI           | Z97 GAMING 5                | [350979cb0a](https://linux-hardware.org/?probe=350979cb0a) | Apr 19, 2022 |
| Gigabyte      | H310M S2H x.x               | [a0325fabb2](https://linux-hardware.org/?probe=a0325fabb2) | Apr 17, 2022 |
| Gigabyte      | H310M S2H x.x               | [d775ab24fe](https://linux-hardware.org/?probe=d775ab24fe) | Apr 17, 2022 |
| MSI           | 970 GAMING                  | [1ed579d3d1](https://linux-hardware.org/?probe=1ed579d3d1) | Apr 16, 2022 |
| MSI           | 970 GAMING                  | [dae8a4db62](https://linux-hardware.org/?probe=dae8a4db62) | Apr 16, 2022 |
| Unknown       | Unknown                     | [3e2989ae49](https://linux-hardware.org/?probe=3e2989ae49) | Apr 15, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [cf9feaf8ec](https://linux-hardware.org/?probe=cf9feaf8ec) | Apr 15, 2022 |
| Gigabyte      | B75M-D3P                    | [cfb6502298](https://linux-hardware.org/?probe=cfb6502298) | Apr 14, 2022 |
| MSI           | MEG X570 UNIFY              | [bacc580e7a](https://linux-hardware.org/?probe=bacc580e7a) | Apr 13, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [e4ea2782f9](https://linux-hardware.org/?probe=e4ea2782f9) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | [f394924315](https://linux-hardware.org/?probe=f394924315) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | [9edb3bbc43](https://linux-hardware.org/?probe=9edb3bbc43) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [1009093226](https://linux-hardware.org/?probe=1009093226) | Apr 10, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [62c84ef4b4](https://linux-hardware.org/?probe=62c84ef4b4) | Apr 09, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | [07bde861ad](https://linux-hardware.org/?probe=07bde861ad) | Apr 09, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [8a07adc0f8](https://linux-hardware.org/?probe=8a07adc0f8) | Apr 09, 2022 |
| Unknown       | HX90                        | [913b92a244](https://linux-hardware.org/?probe=913b92a244) | Apr 08, 2022 |
| HP            | 1495                        | [36ea4763de](https://linux-hardware.org/?probe=36ea4763de) | Apr 08, 2022 |
| Maxtang       | FP30 V1.0                   | [2062d8578e](https://linux-hardware.org/?probe=2062d8578e) | Apr 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [fa9314716d](https://linux-hardware.org/?probe=fa9314716d) | Apr 07, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d2f9498bd2](https://linux-hardware.org/?probe=d2f9498bd2) | Apr 05, 2022 |
| Acer          | Aspire XC-603               | [ef344607ad](https://linux-hardware.org/?probe=ef344607ad) | Apr 04, 2022 |
| Packard Be... | IMEDIA S2110A               | [b8bf871708](https://linux-hardware.org/?probe=b8bf871708) | Apr 04, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | [7da8a936ea](https://linux-hardware.org/?probe=7da8a936ea) | Apr 04, 2022 |
| Gigabyte      | Z690 UD AX                  | [a052a5e936](https://linux-hardware.org/?probe=a052a5e936) | Apr 03, 2022 |
| Unknown       | Unknown                     | [ec51dcaf0a](https://linux-hardware.org/?probe=ec51dcaf0a) | Apr 03, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | [a9f2820894](https://linux-hardware.org/?probe=a9f2820894) | Apr 02, 2022 |
| Dell          | 07PR60 A00                  | [40f34fbc8f](https://linux-hardware.org/?probe=40f34fbc8f) | Apr 01, 2022 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | [f0fdc95810](https://linux-hardware.org/?probe=f0fdc95810) | Apr 01, 2022 |
| HP            | ProLiant ML110 G7           | [9e1e2b2ae7](https://linux-hardware.org/?probe=9e1e2b2ae7) | Apr 01, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [ce2e9f743d](https://linux-hardware.org/?probe=ce2e9f743d) | Mar 31, 2022 |
| Dell          | 0YNVJG A01                  | [4ccce61117](https://linux-hardware.org/?probe=4ccce61117) | Mar 30, 2022 |
| MSI           | B450M PRO-M2 MAX            | [f21ef43d0f](https://linux-hardware.org/?probe=f21ef43d0f) | Mar 30, 2022 |
| Le Cube 1     | Unknown                     | [a881cc0397](https://linux-hardware.org/?probe=a881cc0397) | Mar 26, 2022 |
| HP            | 1589                        | [8c1f30bb6f](https://linux-hardware.org/?probe=8c1f30bb6f) | Mar 23, 2022 |
| ASRock        | 970 Extreme3 R2.0           | [f417e6a6ef](https://linux-hardware.org/?probe=f417e6a6ef) | Mar 11, 2022 |
| Unknown       | T3 MRD                      | [256dc440ec](https://linux-hardware.org/?probe=256dc440ec) | Mar 09, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [1fb25ad2c3](https://linux-hardware.org/?probe=1fb25ad2c3) | Mar 05, 2022 |
| ASUSTek       | M4A87TD/USB3                | [aa80ded615](https://linux-hardware.org/?probe=aa80ded615) | Mar 04, 2022 |
| ASUSTek       | M4A87TD/USB3                | [3e997c5618](https://linux-hardware.org/?probe=3e997c5618) | Mar 03, 2022 |
| Unknown       | T3 MRD                      | [35ab38818d](https://linux-hardware.org/?probe=35ab38818d) | Feb 28, 2022 |
| Unknown       | T3 MRD                      | [01dd9cefa7](https://linux-hardware.org/?probe=01dd9cefa7) | Feb 28, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [18d37562a8](https://linux-hardware.org/?probe=18d37562a8) | Feb 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d8af57f59a](https://linux-hardware.org/?probe=d8af57f59a) | Feb 26, 2022 |
| Gigabyte      | H61M-DS2 DVI                | [90c43679f7](https://linux-hardware.org/?probe=90c43679f7) | Feb 23, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | [fa5ed1f68b](https://linux-hardware.org/?probe=fa5ed1f68b) | Feb 13, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | [e329340668](https://linux-hardware.org/?probe=e329340668) | Feb 11, 2022 |
| Dell          | 0YXT71 A03                  | [19227aa57d](https://linux-hardware.org/?probe=19227aa57d) | Feb 11, 2022 |
| HP            | 212B                        | [fab24340a5](https://linux-hardware.org/?probe=fab24340a5) | Feb 10, 2022 |
| ASRockRack    | X470D4U2/1N1                | [735bc0f806](https://linux-hardware.org/?probe=735bc0f806) | Feb 04, 2022 |
| ASUSTek       | P5P41T/USB3                 | [f45dc3454a](https://linux-hardware.org/?probe=f45dc3454a) | Jan 25, 2022 |
| ASUSTek       | P5P41T/USB3                 | [105593cece](https://linux-hardware.org/?probe=105593cece) | Jan 23, 2022 |
| Gigabyte      | GB-BSi7-1165G7              | [ab94ff1199](https://linux-hardware.org/?probe=ab94ff1199) | Jan 20, 2022 |
| MSI           | Z490-A PRO                  | [b2655bbd43](https://linux-hardware.org/?probe=b2655bbd43) | Jan 15, 2022 |
| MSI           | C236A WORKSTATION           | [97795d3ebc](https://linux-hardware.org/?probe=97795d3ebc) | Jan 07, 2022 |
| Intel         | H61                         | [e2b49aa759](https://linux-hardware.org/?probe=e2b49aa759) | Dec 30, 2021 |
| Lenovo        | 3141 NOK                    | [cc90d7c889](https://linux-hardware.org/?probe=cc90d7c889) | Dec 13, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [0db33a5b23](https://linux-hardware.org/?probe=0db33a5b23) | Dec 10, 2021 |
| Huanan        | X99 F8D V2.2                | [dcd5217827](https://linux-hardware.org/?probe=dcd5217827) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | [16854f2502](https://linux-hardware.org/?probe=16854f2502) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | [e6f3417028](https://linux-hardware.org/?probe=e6f3417028) | Nov 27, 2021 |
| Gigabyte      | EP31-DS3L                   | [c0134f6231](https://linux-hardware.org/?probe=c0134f6231) | Nov 11, 2021 |
| Gigabyte      | EP31-DS3L                   | [4d659bf7e4](https://linux-hardware.org/?probe=4d659bf7e4) | Nov 11, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [36e64b8256](https://linux-hardware.org/?probe=36e64b8256) | Nov 10, 2021 |
| MSI           | MS-7235                     | [bbfa7fb897](https://linux-hardware.org/?probe=bbfa7fb897) | Oct 24, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Desktops | Percent |
|-----------------------------|----------|---------|
| 5.15.0-46-generic           | 121      | 13.07%  |
| 5.15.0-27-generic           | 102      | 11.02%  |
| 5.15.0-41-generic           | 90       | 9.72%   |
| 5.15.0-40-generic           | 89       | 9.61%   |
| 5.15.0-25-generic           | 88       | 9.5%    |
| 5.15.0-43-generic           | 74       | 7.99%   |
| 5.15.0-33-generic           | 61       | 6.59%   |
| 5.15.0-30-generic           | 52       | 5.62%   |
| 5.15.0-39-generic           | 45       | 4.86%   |
| 5.15.0-35-generic           | 44       | 4.75%   |
| 5.15.0-37-generic           | 43       | 4.64%   |
| 5.15.0-47-generic           | 23       | 2.48%   |
| 5.15.0-23-generic           | 12       | 1.3%    |
| 5.15.0-18-generic           | 9        | 0.97%   |
| 5.15.0-32-generic           | 7        | 0.76%   |
| 5.13.0-19-generic           | 7        | 0.76%   |
| 5.15.0-28-generic           | 4        | 0.43%   |
| 5.15.0-45-generic           | 3        | 0.32%   |
| 5.15.0-22-generic           | 3        | 0.32%   |
| 5.18.0-051800-generic       | 2        | 0.22%   |
| 5.17.0-1013-oem             | 2        | 0.22%   |
| 5.17.0-051700-generic       | 2        | 0.22%   |
| 5.15.13-051513-generic      | 2        | 0.22%   |
| 5.15.0-48-generic           | 2        | 0.22%   |
| 5.8.0-53-generic            | 1        | 0.11%   |
| 5.19.3-051903-generic       | 1        | 0.11%   |
| 5.19.0-051900-generic       | 1        | 0.11%   |
| 5.18.8-051808-generic       | 1        | 0.11%   |
| 5.18.3-051803-generic       | 1        | 0.11%   |
| 5.18.13-051813-generic      | 1        | 0.11%   |
| 5.18.10-051810-generic      | 1        | 0.11%   |
| 5.18.1-tkg-pds              | 1        | 0.11%   |
| 5.18.0-14.2-liquorix-amd64  | 1        | 0.11%   |
| 5.17.9-xanmod1-x64v2        | 1        | 0.11%   |
| 5.17.9-051709-generic       | 1        | 0.11%   |
| 5.17.7-051707-generic       | 1        | 0.11%   |
| 5.17.6-051706-generic       | 1        | 0.11%   |
| 5.17.5-051705-generic       | 1        | 0.11%   |
| 5.17.4-051704-generic       | 1        | 0.11%   |
| 5.17.2-051702-generic       | 1        | 0.11%   |
| 5.17.15-051715-generic      | 1        | 0.11%   |
| 5.17.14-void31-nomac-znver3 | 1        | 0.11%   |
| 5.17.1-051701-generic       | 1        | 0.11%   |
| 5.17.0-void25-nomac-znver3  | 1        | 0.11%   |
| 5.17.0-tkg-cacule           | 1        | 0.11%   |
| 5.17.0-4.1-liquorix-amd64   | 1        | 0.11%   |
| 5.17.0-1014-oem             | 1        | 0.11%   |
| 5.17.0-1006-oem             | 1        | 0.11%   |
| 5.17.0-1003-oem             | 1        | 0.11%   |
| 5.16.0-051600-generic       | 1        | 0.11%   |
| 5.15.0-47-lowlatency        | 1        | 0.11%   |
| 5.15.0-40-lowlatency        | 1        | 0.11%   |
| 5.15.0-37-lowlatency        | 1        | 0.11%   |
| 5.15.0-30-lowlatency        | 1        | 0.11%   |
| 5.15.0-27-lowlatency        | 1        | 0.11%   |
| 5.15.0-17-generic           | 1        | 0.11%   |
| 5.15.0-10037-tuxedo         | 1        | 0.11%   |
| 5.15.0-051500rc7-generic    | 1        | 0.11%   |
| 5.13.0-48-generic           | 1        | 0.11%   |
| 5.13.0-40-generic           | 1        | 0.11%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15.0  | 831      | 94.75%  |
| 5.13.0  | 12       | 1.37%   |
| 5.17.0  | 10       | 1.14%   |
| 5.18.0  | 3        | 0.34%   |
| 5.17.9  | 2        | 0.23%   |
| 5.15.13 | 2        | 0.23%   |
| 5.8.0   | 1        | 0.11%   |
| 5.19.3  | 1        | 0.11%   |
| 5.19.0  | 1        | 0.11%   |
| 5.18.8  | 1        | 0.11%   |
| 5.18.3  | 1        | 0.11%   |
| 5.18.13 | 1        | 0.11%   |
| 5.18.10 | 1        | 0.11%   |
| 5.18.1  | 1        | 0.11%   |
| 5.17.7  | 1        | 0.11%   |
| 5.17.6  | 1        | 0.11%   |
| 5.17.5  | 1        | 0.11%   |
| 5.17.4  | 1        | 0.11%   |
| 5.17.2  | 1        | 0.11%   |
| 5.17.15 | 1        | 0.11%   |
| 5.17.14 | 1        | 0.11%   |
| 5.17.1  | 1        | 0.11%   |
| 5.16.0  | 1        | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.15    | 833      | 95.09%  |
| 5.17    | 19       | 2.17%   |
| 5.13    | 12       | 1.37%   |
| 5.18    | 8        | 0.91%   |
| 5.19    | 2        | 0.23%   |
| 5.8     | 1        | 0.11%   |
| 5.16    | 1        | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 873      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 809      | 92.67%  |
| Unknown         | 41       | 4.7%    |
| X-Cinnamon      | 12       | 1.37%   |
| Unity           | 5        | 0.57%   |
| GNOME Classic   | 4        | 0.46%   |
| i3              | 1        | 0.11%   |
| GNOME Flashback | 1        | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Wayland | 468      | 53.12%  |
| X11     | 371      | 42.11%  |
| Tty     | 27       | 3.06%   |
| Unknown | 15       | 1.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| GDM3    | 774      | 88.46%  |
| Unknown | 75       | 8.57%   |
| LightDM | 15       | 1.71%   |
| GDM     | 6        | 0.69%   |
| SDDM    | 3        | 0.34%   |
| SLiM    | 2        | 0.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 357      | 40.89%  |
| de_DE   | 81       | 9.28%   |
| fr_FR   | 56       | 6.41%   |
| en_GB   | 56       | 6.41%   |
| pt_BR   | 34       | 3.89%   |
| ru_RU   | 30       | 3.44%   |
| en_CA   | 26       | 2.98%   |
| es_ES   | 25       | 2.86%   |
| it_IT   | 22       | 2.52%   |
| en_AU   | 19       | 2.18%   |
| cs_CZ   | 14       | 1.6%    |
| pl_PL   | 12       | 1.37%   |
| en_IN   | 12       | 1.37%   |
| ja_JP   | 10       | 1.15%   |
| es_AR   | 8        | 0.92%   |
| sv_SE   | 7        | 0.8%    |
| pt_PT   | 7        | 0.8%    |
| C       | 7        | 0.8%    |
| nl_NL   | 6        | 0.69%   |
| es_MX   | 6        | 0.69%   |
| en_ZA   | 6        | 0.69%   |
| zh_CN   | 5        | 0.57%   |
| en_PH   | 5        | 0.57%   |
| de_CH   | 5        | 0.57%   |
| de_AT   | 5        | 0.57%   |
| tr_TR   | 4        | 0.46%   |
| fi_FI   | 4        | 0.46%   |
| en_NZ   | 4        | 0.46%   |
| el_GR   | 4        | 0.46%   |
| zh_TW   | 3        | 0.34%   |
| sk_SK   | 3        | 0.34%   |
| nl_BE   | 3        | 0.34%   |
| fr_BE   | 3        | 0.34%   |
| es_CL   | 3        | 0.34%   |
| ko_KR   | 2        | 0.23%   |
| hu_HU   | 2        | 0.23%   |
| fr_CA   | 2        | 0.23%   |
| es_PE   | 2        | 0.23%   |
| Unknown | 2        | 0.23%   |
| th_TH   | 1        | 0.11%   |
| ro_RO   | 1        | 0.11%   |
| nb_NO   | 1        | 0.11%   |
| es_VE   | 1        | 0.11%   |
| es_NI   | 1        | 0.11%   |
| es_EC   | 1        | 0.11%   |
| es_CU   | 1        | 0.11%   |
| es_CR   | 1        | 0.11%   |
| en_ZW   | 1        | 0.11%   |
| en_SG   | 1        | 0.11%   |
| de_BE   | 1        | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 635      | 72.32%  |
| EFI  | 243      | 27.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 791      | 90.5%   |
| Overlay | 29       | 3.32%   |
| Zfs     | 27       | 3.09%   |
| Btrfs   | 17       | 1.95%   |
| Xfs     | 7        | 0.8%    |
| Ext2    | 2        | 0.23%   |
| Unknown | 1        | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 605      | 69.06%  |
| GPT     | 249      | 28.42%  |
| MBR     | 22       | 2.51%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 709      | 80.57%  |
| Yes       | 171      | 19.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 500      | 56.82%  |
| Yes       | 380      | 43.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 211      | 24.17%  |
| Gigabyte Technology | 133      | 15.23%  |
| MSI                 | 127      | 14.55%  |
| Dell                | 92       | 10.54%  |
| Hewlett-Packard     | 62       | 7.1%    |
| ASRock              | 54       | 6.19%   |
| Lenovo              | 33       | 3.78%   |
| Intel               | 29       | 3.32%   |
| Acer                | 23       | 2.63%   |
| Unknown             | 13       | 1.49%   |
| Foxconn             | 11       | 1.26%   |
| Pegatron            | 10       | 1.15%   |
| Shuttle             | 9        | 1.03%   |
| Medion              | 6        | 0.69%   |
| Fujitsu             | 6        | 0.69%   |
| ECS                 | 6        | 0.69%   |
| Alienware           | 6        | 0.69%   |
| Supermicro          | 5        | 0.57%   |
| Biostar             | 5        | 0.57%   |
| Apple               | 5        | 0.57%   |
| Huanan              | 4        | 0.46%   |
| OEM                 | 2        | 0.23%   |
| ASRockRack          | 2        | 0.23%   |
| YANYU               | 1        | 0.11%   |
| XDO.AI              | 1        | 0.11%   |
| SHARKBAY            | 1        | 0.11%   |
| QIYIDA              | 1        | 0.11%   |
| Positivo            | 1        | 0.11%   |
| Pepper Jobs         | 1        | 0.11%   |
| PCWare              | 1        | 0.11%   |
| PCPartner           | 1        | 0.11%   |
| Packard Bell        | 1        | 0.11%   |
| Nvidia              | 1        | 0.11%   |
| Maxtang             | 1        | 0.11%   |
| MACHINIST           | 1        | 0.11%   |
| Le Cube 1           | 1        | 0.11%   |
| LattePanda          | 1        | 0.11%   |
| ITI LIMITED         | 1        | 0.11%   |
| Google              | 1        | 0.11%   |
| Fujitsu Siemens     | 1        | 0.11%   |
| BESSTAR Tech        | 1        | 0.11%   |
| ABIT                | 1        | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Desktops | Percent |
|------------------------------------------|----------|---------|
| ASUS All Series                          | 25       | 2.86%   |
| Unknown                                  | 16       | 1.83%   |
| MSI MS-7721                              | 12       | 1.37%   |
| Dell OptiPlex 7010                       | 9        | 1.03%   |
| MSI MS-7C52                              | 7        | 0.8%    |
| ASUS PRIME A320M-K                       | 7        | 0.8%    |
| Dell OptiPlex 790                        | 6        | 0.69%   |
| Intel H61                                | 5        | 0.57%   |
| Dell OptiPlex 9020                       | 5        | 0.57%   |
| ASUS TUF Gaming X570-PLUS                | 5        | 0.57%   |
| MSI MS-7C91                              | 4        | 0.46%   |
| MSI MS-7C02                              | 4        | 0.46%   |
| MSI MS-7B84                              | 4        | 0.46%   |
| Dell OptiPlex 3020                       | 4        | 0.46%   |
| Dell OptiPlex 3010                       | 4        | 0.46%   |
| ASUS ROG STRIX B550-F GAMING             | 4        | 0.46%   |
| ASUS Pro WS WRX80E-SAGE SE WIFI          | 4        | 0.46%   |
| Apple MacPro5,1                          | 4        | 0.46%   |
| MSI MS-7D54                              | 3        | 0.34%   |
| MSI MS-7D42                              | 3        | 0.34%   |
| MSI MS-7C92                              | 3        | 0.34%   |
| MSI MS-7C37                              | 3        | 0.34%   |
| MSI MS-7C35                              | 3        | 0.34%   |
| MSI MS-7B79                              | 3        | 0.34%   |
| MSI MS-7A38                              | 3        | 0.34%   |
| MSI MS-7817                              | 3        | 0.34%   |
| HP Z400 Workstation                      | 3        | 0.34%   |
| HP ProDesk 600 G1 SFF                    | 3        | 0.34%   |
| HP EliteDesk 800 G2 SFF                  | 3        | 0.34%   |
| HP EliteDesk 800 G1 SFF                  | 3        | 0.34%   |
| HP Compaq 8200 Elite SFF PC              | 3        | 0.34%   |
| Dell XPS 8940                            | 3        | 0.34%   |
| Dell OptiPlex 780                        | 3        | 0.34%   |
| Dell OptiPlex 7050                       | 3        | 0.34%   |
| Dell OptiPlex 7040                       | 3        | 0.34%   |
| ASUS ROG STRIX X570-E GAMING             | 3        | 0.34%   |
| ASUS PRIME B450M-A                       | 3        | 0.34%   |
| ASUS CROSSHAIR V FORMULA-Z               | 3        | 0.34%   |
| ASRock G41M-VS3                          | 3        | 0.34%   |
| ASRock B450M Pro4                        | 3        | 0.34%   |
| Shuttle DS81D                            | 2        | 0.23%   |
| Shuttle DS10U                            | 2        | 0.23%   |
| MSI MS-7D25                              | 2        | 0.23%   |
| MSI MS-7D16                              | 2        | 0.23%   |
| MSI MS-7D09                              | 2        | 0.23%   |
| MSI MS-7C95                              | 2        | 0.23%   |
| MSI MS-7C51                              | 2        | 0.23%   |
| MSI MS-7B17                              | 2        | 0.23%   |
| MSI MS-7A70                              | 2        | 0.23%   |
| MSI MS-7971                              | 2        | 0.23%   |
| MSI MS-7758                              | 2        | 0.23%   |
| MSI MS-7693                              | 2        | 0.23%   |
| MSI MS-7641                              | 2        | 0.23%   |
| MSI MS-7636                              | 2        | 0.23%   |
| Intel X79M-S                             | 2        | 0.23%   |
| Intel B75                                | 2        | 0.23%   |
| HP Z440 Workstation                      | 2        | 0.23%   |
| HP EliteDesk 800 G6 Small Form Factor PC | 2        | 0.23%   |
| HP Compaq Elite 8300 CMT                 | 2        | 0.23%   |
| HP Compaq 8100 Elite SFF PC              | 2        | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Dell OptiPlex        | 55       | 6.3%    |
| ASUS PRIME           | 34       | 3.89%   |
| ASUS ROG             | 25       | 2.86%   |
| ASUS All             | 25       | 2.86%   |
| HP Compaq            | 20       | 2.29%   |
| Lenovo ThinkCentre   | 19       | 2.18%   |
| ASUS TUF             | 17       | 1.95%   |
| Unknown              | 16       | 1.83%   |
| Acer Aspire          | 15       | 1.72%   |
| MSI MS-7721          | 12       | 1.37%   |
| Dell Precision       | 12       | 1.37%   |
| HP EliteDesk         | 11       | 1.26%   |
| Dell Inspiron        | 10       | 1.15%   |
| Gigabyte X570        | 8        | 0.92%   |
| ASUS Pro             | 8        | 0.92%   |
| MSI MS-7C52          | 7        | 0.8%    |
| ASUS CROSSHAIR       | 7        | 0.8%    |
| HP ProDesk           | 6        | 0.69%   |
| Dell XPS             | 6        | 0.69%   |
| Intel H61            | 5        | 0.57%   |
| Gigabyte Z390        | 5        | 0.57%   |
| ASUS M5A97           | 5        | 0.57%   |
| MSI MS-7C91          | 4        | 0.46%   |
| MSI MS-7C02          | 4        | 0.46%   |
| MSI MS-7B84          | 4        | 0.46%   |
| Lenovo ThinkStation  | 4        | 0.46%   |
| Lenovo IdeaCentre    | 4        | 0.46%   |
| Gigabyte Z690        | 4        | 0.46%   |
| ASUS P8H61-M         | 4        | 0.46%   |
| Apple MacPro5        | 4        | 0.46%   |
| Acer Veriton         | 4        | 0.46%   |
| MSI MS-7D54          | 3        | 0.34%   |
| MSI MS-7D42          | 3        | 0.34%   |
| MSI MS-7C92          | 3        | 0.34%   |
| MSI MS-7C37          | 3        | 0.34%   |
| MSI MS-7C35          | 3        | 0.34%   |
| MSI MS-7B79          | 3        | 0.34%   |
| MSI MS-7A38          | 3        | 0.34%   |
| MSI MS-7817          | 3        | 0.34%   |
| HP Z400              | 3        | 0.34%   |
| Gigabyte Z97X-Gaming | 3        | 0.34%   |
| Gigabyte Z370        | 3        | 0.34%   |
| Gigabyte X570S       | 3        | 0.34%   |
| Gigabyte H61M-DS2    | 3        | 0.34%   |
| Gigabyte B550        | 3        | 0.34%   |
| Gigabyte B450M       | 3        | 0.34%   |
| Gigabyte B450        | 3        | 0.34%   |
| Fujitsu ESPRIMO      | 3        | 0.34%   |
| Dell Vostro          | 3        | 0.34%   |
| Dell Studio          | 3        | 0.34%   |
| ASUS P8B75-M         | 3        | 0.34%   |
| ASUS P7H55-M         | 3        | 0.34%   |
| ASUS M5A99X          | 3        | 0.34%   |
| ASUS M5A78L-M        | 3        | 0.34%   |
| ASRock G41M-VS3      | 3        | 0.34%   |
| ASRock B450M         | 3        | 0.34%   |
| ASRock 970           | 3        | 0.34%   |
| Shuttle DS81D        | 2        | 0.23%   |
| Shuttle DS10U        | 2        | 0.23%   |
| MSI MS-7D25          | 2        | 0.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2021    | 81       | 9.28%   |
| 2013    | 81       | 9.28%   |
| 2012    | 78       | 8.93%   |
| 2018    | 74       | 8.48%   |
| 2019    | 69       | 7.9%    |
| 2014    | 67       | 7.67%   |
| 2020    | 65       | 7.45%   |
| 2011    | 59       | 6.76%   |
| 2010    | 57       | 6.53%   |
| 2015    | 51       | 5.84%   |
| 2017    | 50       | 5.73%   |
| 2009    | 34       | 3.89%   |
| 2016    | 31       | 3.55%   |
| 2008    | 28       | 3.21%   |
| 2022    | 23       | 2.63%   |
| 2007    | 17       | 1.95%   |
| 2006    | 5        | 0.57%   |
| 2005    | 2        | 0.23%   |
| Unknown | 1        | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 873      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 846      | 96.69%  |
| Enabled  | 29       | 3.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 872      | 99.89%  |
| Yes  | 1        | 0.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 247      | 28.13%  |
| 4.01-8.0        | 148      | 16.86%  |
| 8.01-16.0       | 147      | 16.74%  |
| 32.01-64.0      | 140      | 15.95%  |
| 3.01-4.0        | 105      | 11.96%  |
| 64.01-256.0     | 52       | 5.92%   |
| 24.01-32.0      | 22       | 2.51%   |
| 1.01-2.0        | 7        | 0.8%    |
| More than 256.0 | 5        | 0.57%   |
| 2.01-3.0        | 5        | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 321      | 35.35%  |
| 2.01-3.0   | 265      | 29.19%  |
| 3.01-4.0   | 131      | 14.43%  |
| 4.01-8.0   | 123      | 13.55%  |
| 8.01-16.0  | 38       | 4.19%   |
| 0.51-1.0   | 15       | 1.65%   |
| 16.01-24.0 | 6        | 0.66%   |
| 0.01-0.5   | 4        | 0.44%   |
| 24.01-32.0 | 3        | 0.33%   |
| 32.01-64.0 | 2        | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 331      | 37.36%  |
| 2      | 252      | 28.44%  |
| 3      | 139      | 15.69%  |
| 4      | 67       | 7.56%   |
| 5      | 39       | 4.4%    |
| 6      | 20       | 2.26%   |
| 0      | 13       | 1.47%   |
| 8      | 8        | 0.9%    |
| 7      | 8        | 0.9%    |
| 9      | 3        | 0.34%   |
| 11     | 2        | 0.23%   |
| 20     | 1        | 0.11%   |
| 13     | 1        | 0.11%   |
| 12     | 1        | 0.11%   |
| 10     | 1        | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 494      | 56.39%  |
| Yes       | 382      | 43.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 866      | 99.08%  |
| No        | 8        | 0.92%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 463      | 52.85%  |
| Yes       | 413      | 47.15%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 579      | 65.95%  |
| Yes       | 299      | 34.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Desktops | Percent |
|---------------------|----------|---------|
| USA                 | 175      | 20.05%  |
| Germany             | 90       | 10.31%  |
| France              | 58       | 6.64%   |
| Russia              | 53       | 6.07%   |
| UK                  | 51       | 5.84%   |
| Brazil              | 50       | 5.73%   |
| Canada              | 32       | 3.67%   |
| Spain               | 26       | 2.98%   |
| Italy               | 26       | 2.98%   |
| Australia           | 21       | 2.41%   |
| Poland              | 17       | 1.95%   |
| Argentina           | 16       | 1.83%   |
| Czechia             | 15       | 1.72%   |
| Switzerland         | 14       | 1.6%    |
| Finland             | 14       | 1.6%    |
| Netherlands         | 13       | 1.49%   |
| Japan               | 13       | 1.49%   |
| India               | 12       | 1.37%   |
| Austria             | 12       | 1.37%   |
| Sweden              | 11       | 1.26%   |
| Belgium             | 11       | 1.26%   |
| Turkey              | 8        | 0.92%   |
| South Africa        | 8        | 0.92%   |
| Mexico              | 8        | 0.92%   |
| Portugal            | 7        | 0.8%    |
| Bulgaria            | 7        | 0.8%    |
| Hungary             | 6        | 0.69%   |
| Romania             | 5        | 0.57%   |
| Norway              | 5        | 0.57%   |
| New Zealand         | 5        | 0.57%   |
| Greece              | 5        | 0.57%   |
| Thailand            | 4        | 0.46%   |
| Taiwan              | 4        | 0.46%   |
| South Korea         | 4        | 0.46%   |
| Saudi Arabia        | 4        | 0.46%   |
| Philippines         | 4        | 0.46%   |
| Peru                | 4        | 0.46%   |
| China               | 4        | 0.46%   |
| Slovakia            | 3        | 0.34%   |
| Hong Kong           | 3        | 0.34%   |
| Chile               | 3        | 0.34%   |
| Algeria             | 3        | 0.34%   |
| Slovenia            | 2        | 0.23%   |
| Serbia              | 2        | 0.23%   |
| Réunion            | 2        | 0.23%   |
| Pakistan            | 2        | 0.23%   |
| Nicaragua           | 2        | 0.23%   |
| Morocco             | 2        | 0.23%   |
| Malaysia            | 2        | 0.23%   |
| Denmark             | 2        | 0.23%   |
| Colombia            | 2        | 0.23%   |
| Venezuela           | 1        | 0.11%   |
| Ukraine             | 1        | 0.11%   |
| UAE                 | 1        | 0.11%   |
| Trinidad and Tobago | 1        | 0.11%   |
| Singapore           | 1        | 0.11%   |
| Myanmar             | 1        | 0.11%   |
| Lithuania           | 1        | 0.11%   |
| Latvia              | 1        | 0.11%   |
| Ivory Coast         | 1        | 0.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Desktops | Percent |
|---------------|----------|---------|
| Cheboksary    | 23       | 2.6%    |
| Berlin        | 10       | 1.13%   |
| Sydney        | 9        | 1.02%   |
| Sao Paulo     | 9        | 1.02%   |
| Helsinki      | 9        | 1.02%   |
| Prague        | 7        | 0.79%   |
| Moscow        | 7        | 0.79%   |
| Dallas        | 7        | 0.79%   |
| Paris         | 6        | 0.68%   |
| Madrid        | 6        | 0.68%   |
| Jacksonville  | 6        | 0.68%   |
| Istanbul      | 6        | 0.68%   |
| Zurich        | 5        | 0.57%   |
| Vienna        | 5        | 0.57%   |
| Manchester    | 5        | 0.57%   |
| Debica        | 5        | 0.57%   |
| Brisbane      | 5        | 0.57%   |
| St Petersburg | 4        | 0.45%   |
| San Jose      | 4        | 0.45%   |
| Portland      | 4        | 0.45%   |
| Munich        | 4        | 0.45%   |
| London        | 4        | 0.45%   |
| Hamburg       | 4        | 0.45%   |
| Guarulhos     | 4        | 0.45%   |
| Athens        | 4        | 0.45%   |
| Sofia         | 3        | 0.34%   |
| Santiago      | 3        | 0.34%   |
| Santa Clara   | 3        | 0.34%   |
| Rome          | 3        | 0.34%   |
| Ottawa        | 3        | 0.34%   |
| Osaka         | 3        | 0.34%   |
| Novosibirsk   | 3        | 0.34%   |
| Lima          | 3        | 0.34%   |
| Houston       | 3        | 0.34%   |
| Buenos Aires  | 3        | 0.34%   |
| Budapest      | 3        | 0.34%   |
| Bucharest     | 3        | 0.34%   |
| Barcelona     | 3        | 0.34%   |
| Auckland      | 3        | 0.34%   |
| Atlanta       | 3        | 0.34%   |
| Amsterdam     | 3        | 0.34%   |
| Ypsilanti     | 2        | 0.23%   |
| Wroclaw       | 2        | 0.23%   |
| Wiesbaden     | 2        | 0.23%   |
| Warsaw        | 2        | 0.23%   |
| Volta Redonda | 2        | 0.23%   |
| Vancouver     | 2        | 0.23%   |
| Toronto       | 2        | 0.23%   |
| Tampere       | 2        | 0.23%   |
| Taipei        | 2        | 0.23%   |
| Stuttgart     | 2        | 0.23%   |
| Sheffield     | 2        | 0.23%   |
| Seoul         | 2        | 0.23%   |
| Seattle       | 2        | 0.23%   |
| San Antonio   | 2        | 0.23%   |
| Saint Paul    | 2        | 0.23%   |
| Saarlouis     | 2        | 0.23%   |
| Roubaix       | 2        | 0.23%   |
| Rosario       | 2        | 0.23%   |
| Rochester     | 2        | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 300      | 449    | 19.13%  |
| WDC                       | 290      | 501    | 18.49%  |
| Samsung Electronics       | 225      | 335    | 14.35%  |
| Toshiba                   | 103      | 137    | 6.57%   |
| Kingston                  | 100      | 123    | 6.38%   |
| Crucial                   | 72       | 89     | 4.59%   |
| SanDisk                   | 68       | 94     | 4.34%   |
| Hitachi                   | 49       | 54     | 3.13%   |
| A-DATA Technology         | 22       | 24     | 1.4%    |
| SK hynix                  | 20       | 23     | 1.28%   |
| Phison                    | 20       | 30     | 1.28%   |
| HGST                      | 17       | 25     | 1.08%   |
| Intel                     | 16       | 17     | 1.02%   |
| China                     | 16       | 19     | 1.02%   |
| Unknown                   | 15       | 26     | 0.96%   |
| Intenso                   | 14       | 17     | 0.89%   |
| OCZ                       | 13       | 25     | 0.83%   |
| PNY                       | 12       | 16     | 0.77%   |
| Silicon Motion            | 10       | 11     | 0.64%   |
| SPCC                      | 9        | 10     | 0.57%   |
| Micron Technology         | 9        | 11     | 0.57%   |
| Corsair                   | 9        | 9      | 0.57%   |
| Maxtor                    | 7        | 8      | 0.45%   |
| Gigabyte Technology       | 7        | 8      | 0.45%   |
| Unknown                   | 7        | 8      | 0.45%   |
| Transcend                 | 6        | 6      | 0.38%   |
| Micron/Crucial Technology | 6        | 10     | 0.38%   |
| Lexar                     | 6        | 6      | 0.38%   |
| XPG                       | 5        | 6      | 0.32%   |
| Team                      | 5        | 10     | 0.32%   |
| Realtek Semiconductor     | 5        | 5      | 0.32%   |
| Netac                     | 5        | 5      | 0.32%   |
| JMicron Technology        | 5        | 5      | 0.32%   |
| KIOXIA                    | 4        | 6      | 0.26%   |
| Dogfish                   | 4        | 5      | 0.26%   |
| WALRAM                    | 3        | 3      | 0.19%   |
| KingFast                  | 3        | 3      | 0.19%   |
| Emtec                     | 3        | 3      | 0.19%   |
| USB3.0                    | 2        | 2      | 0.13%   |
| SABRENT                   | 2        | 3      | 0.13%   |
| Plextor                   | 2        | 2      | 0.13%   |
| Patriot                   | 2        | 2      | 0.13%   |
| Mushkin                   | 2        | 2      | 0.13%   |
| LITEONIT                  | 2        | 2      | 0.13%   |
| Leven                     | 2        | 2      | 0.13%   |
| KIOXIA-EXCERIA            | 2        | 2      | 0.13%   |
| KingSpec                  | 2        | 2      | 0.13%   |
| KingDian                  | 2        | 2      | 0.13%   |
| HPE                       | 2        | 2      | 0.13%   |
| HGST HTS                  | 2        | 2      | 0.13%   |
| GOODRAM                   | 2        | 3      | 0.13%   |
| FORESEE                   | 2        | 2      | 0.13%   |
| ASMT                      | 2        | 3      | 0.13%   |
| Apple                     | 2        | 2      | 0.13%   |
| Apacer                    | 2        | 2      | 0.13%   |
| Zheino                    | 1        | 1      | 0.06%   |
| XrayDisk                  | 1        | 1      | 0.06%   |
| WDC WDBN                  | 1        | 1      | 0.06%   |
| WD MediaMax               | 1        | 1      | 0.06%   |
| ViperTeq                  | 1        | 1      | 0.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB    | 24       | 1.28%   |
| Toshiba VT180 240GB SSD            | 23       | 1.22%   |
| Seagate ST1000DM010-2EP102 1TB     | 22       | 1.17%   |
| Toshiba DT01ACA050 500GB           | 21       | 1.12%   |
| Seagate ST2000DM008-2FR102 2TB     | 21       | 1.12%   |
| Kingston SA400S37240G 240GB SSD    | 20       | 1.06%   |
| Samsung SSD 850 EVO 500GB          | 19       | 1.01%   |
| SanDisk NVMe SSD Drive 1TB         | 18       | 0.96%   |
| Samsung NVMe SSD Drive 1TB         | 18       | 0.96%   |
| Samsung SSD 850 EVO 250GB          | 17       | 0.9%    |
| Samsung SSD 860 EVO 500GB          | 15       | 0.8%    |
| Seagate ST1000DM003-1CH162 1TB     | 13       | 0.69%   |
| Crucial CT500MX500SSD1 500GB       | 13       | 0.69%   |
| Toshiba HDWD110 1TB                | 12       | 0.64%   |
| Seagate ST1000DM003-1ER162 1TB     | 12       | 0.64%   |
| Samsung SSD 980 PRO 1TB            | 12       | 0.64%   |
| Toshiba DT01ACA100 1TB             | 11       | 0.59%   |
| Crucial CT1000MX500SSD1 1TB        | 11       | 0.59%   |
| WDC WD10EZEX-08WN4A0 1TB           | 10       | 0.53%   |
| SanDisk NVMe SSD Drive 500GB       | 10       | 0.53%   |
| Samsung SSD 970 EVO Plus 500GB     | 10       | 0.53%   |
| Kingston SA400S37480G 480GB SSD    | 10       | 0.53%   |
| Kingston SA400S37120G 120GB SSD    | 10       | 0.53%   |
| Seagate ST4000DM004-2CV104 4TB     | 9        | 0.48%   |
| Seagate ST2000DM001-1ER164 2TB     | 9        | 0.48%   |
| Samsung NVMe SSD Drive 500GB       | 9        | 0.48%   |
| Toshiba DT01ACA200 2TB             | 8        | 0.43%   |
| Seagate ST31000528AS 1TB           | 8        | 0.43%   |
| Samsung SSD 860 EVO 1TB            | 8        | 0.43%   |
| Toshiba MQ01ABD100 1TB             | 7        | 0.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 7        | 0.37%   |
| Seagate ST1000DM003-1SB102 1TB     | 7        | 0.37%   |
| Seagate Expansion Desk 4TB         | 7        | 0.37%   |
| Samsung SSD 980 1TB                | 7        | 0.37%   |
| Crucial CT240BX500SSD1 240GB       | 7        | 0.37%   |
| Unknown                            | 7        | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 6        | 0.32%   |
| WDC WD10EZEX-00BN5A0 1TB           | 6        | 0.32%   |
| Unknown SD/MMC/MS PRO 128GB        | 6        | 0.32%   |
| Seagate ST3500418AS 500GB          | 6        | 0.32%   |
| Seagate ST2000DM006-2DM164 2TB     | 6        | 0.32%   |
| Seagate ST2000DM001-1CH164 2TB     | 6        | 0.32%   |
| Seagate Expansion 500GB            | 6        | 0.32%   |
| Samsung SSD 970 EVO Plus 1TB       | 6        | 0.32%   |
| Samsung SSD 870 QVO 1TB            | 6        | 0.32%   |
| Samsung SSD 860 EVO 250GB          | 6        | 0.32%   |
| Kingston SV300S37A240G 240GB SSD   | 6        | 0.32%   |
| Crucial CT480BX500SSD1 480GB       | 6        | 0.32%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 5        | 0.27%   |
| WDC WD20EARX-00PASB0 2TB           | 5        | 0.27%   |
| WDC WD1003FZEX-00MK2A0 1TB         | 5        | 0.27%   |
| Seagate ST4000VN008-2DR166 4TB     | 5        | 0.27%   |
| Seagate ST31000524AS 1TB           | 5        | 0.27%   |
| Seagate ST2000DM001-9YN164 2TB     | 5        | 0.27%   |
| Seagate ST1000LM049-2GH172 1TB     | 5        | 0.27%   |
| Seagate ST1000DM003-9YN162 1TB     | 5        | 0.27%   |
| SanDisk SDSSDA240G 240GB           | 5        | 0.27%   |
| Samsung SSD 970 EVO 500GB          | 5        | 0.27%   |
| Samsung SSD 850 EVO 1TB            | 5        | 0.27%   |
| Samsung SSD 750 EVO 250GB          | 5        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 292      | 438    | 38.47%  |
| WDC                 | 250      | 434    | 32.94%  |
| Toshiba             | 83       | 101    | 10.94%  |
| Hitachi             | 49       | 54     | 6.46%   |
| Samsung Electronics | 38       | 51     | 5.01%   |
| HGST                | 17       | 25     | 2.24%   |
| Unknown             | 8        | 11     | 1.05%   |
| Maxtor              | 6        | 7      | 0.79%   |
| Intenso             | 5        | 6      | 0.66%   |
| SABRENT             | 2        | 3      | 0.26%   |
| ASMT                | 2        | 3      | 0.26%   |
| WD MediaMax         | 1        | 1      | 0.13%   |
| USB3.0              | 1        | 1      | 0.13%   |
| HPE                 | 1        | 1      | 0.13%   |
| Fujitsu             | 1        | 1      | 0.13%   |
| ExcelStor           | 1        | 1      | 0.13%   |
| DAS                 | 1        | 3      | 0.13%   |
| Apple               | 1        | 1      | 0.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 125      | 156    | 21.97%  |
| Kingston            | 85       | 103    | 14.94%  |
| Crucial             | 69       | 85     | 12.13%  |
| SanDisk             | 39       | 56     | 6.85%   |
| WDC                 | 35       | 42     | 6.15%   |
| Toshiba             | 32       | 34     | 5.62%   |
| China               | 16       | 19     | 2.81%   |
| A-DATA Technology   | 16       | 18     | 2.81%   |
| OCZ                 | 11       | 11     | 1.93%   |
| PNY                 | 10       | 14     | 1.76%   |
| SPCC                | 9        | 10     | 1.58%   |
| Intel               | 9        | 9      | 1.58%   |
| Intenso             | 7        | 8      | 1.23%   |
| Transcend           | 6        | 6      | 1.05%   |
| SK hynix            | 6        | 6      | 1.05%   |
| Lexar               | 6        | 6      | 1.05%   |
| Team                | 5        | 10     | 0.88%   |
| Micron Technology   | 5        | 7      | 0.88%   |
| Gigabyte Technology | 5        | 6      | 0.88%   |
| Corsair             | 5        | 5      | 0.88%   |
| Netac               | 4        | 4      | 0.7%    |
| JMicron Technology  | 4        | 4      | 0.7%    |
| Dogfish             | 4        | 5      | 0.7%    |
| Unknown             | 4        | 5      | 0.7%    |
| Emtec               | 3        | 3      | 0.53%   |
| Seagate             | 2        | 2      | 0.35%   |
| Plextor             | 2        | 2      | 0.35%   |
| Phison              | 2        | 2      | 0.35%   |
| Patriot             | 2        | 2      | 0.35%   |
| Mushkin             | 2        | 2      | 0.35%   |
| LITEONIT            | 2        | 2      | 0.35%   |
| Leven               | 2        | 2      | 0.35%   |
| KIOXIA-EXCERIA      | 2        | 2      | 0.35%   |
| KingSpec            | 2        | 2      | 0.35%   |
| KingDian            | 2        | 2      | 0.35%   |
| GOODRAM             | 2        | 3      | 0.35%   |
| FORESEE             | 2        | 2      | 0.35%   |
| Apacer              | 2        | 2      | 0.35%   |
| XrayDisk            | 1        | 1      | 0.18%   |
| WDC WDBN            | 1        | 1      | 0.18%   |
| WALRAM              | 1        | 1      | 0.18%   |
| ViperTeq            | 1        | 1      | 0.18%   |
| USB3.0              | 1        | 1      | 0.18%   |
| UMAX                | 1        | 1      | 0.18%   |
| TCSUNBOW-X5         | 1        | 1      | 0.18%   |
| StoreJet            | 1        | 1      | 0.18%   |
| Smartbuy            | 1        | 1      | 0.18%   |
| S3+                 | 1        | 1      | 0.18%   |
| RZX                 | 1        | 1      | 0.18%   |
| PNY USB             | 1        | 1      | 0.18%   |
| OWC                 | 1        | 1      | 0.18%   |
| MidasForce          | 1        | 1      | 0.18%   |
| Maxtor              | 1        | 1      | 0.18%   |
| Londisk             | 1        | 2      | 0.18%   |
| LDLC                | 1        | 1      | 0.18%   |
| KLEVV               | 1        | 2      | 0.18%   |
| KingFast            | 1        | 1      | 0.18%   |
| Hewlett-Packard     | 1        | 1      | 0.18%   |
| BAITITON            | 1        | 1      | 0.18%   |
| Apple               | 1        | 1      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 583      | 1142   | 43.93%  |
| SSD     | 467      | 684    | 35.19%  |
| NVMe    | 234      | 351    | 17.63%  |
| Unknown | 39       | 48     | 2.94%   |
| MMC     | 4        | 7      | 0.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 777      | 1767   | 71.28%  |
| NVMe | 234      | 351    | 21.47%  |
| SAS  | 75       | 107    | 6.88%   |
| MMC  | 4        | 7      | 0.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 565      | 866    | 48.83%  |
| 0.51-1.0   | 325      | 480    | 28.09%  |
| 1.01-2.0   | 142      | 231    | 12.27%  |
| 3.01-4.0   | 51       | 74     | 4.41%   |
| 4.01-10.0  | 37       | 103    | 3.2%    |
| 2.01-3.0   | 26       | 33     | 2.25%   |
| 10.01-20.0 | 11       | 39     | 0.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 214      | 24.02%  |
| 251-500        | 176      | 19.75%  |
| 501-1000       | 174      | 19.53%  |
| 1001-2000      | 94       | 10.55%  |
| More than 3000 | 92       | 10.33%  |
| 1-20           | 45       | 5.05%   |
| 2001-3000      | 44       | 4.94%   |
| 51-100         | 35       | 3.93%   |
| 21-50          | 12       | 1.35%   |
| Unknown        | 5        | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 339      | 37.5%   |
| 21-50          | 146      | 16.15%  |
| 101-250        | 109      | 12.06%  |
| 51-100         | 86       | 9.51%   |
| 251-500        | 72       | 7.96%   |
| 501-1000       | 48       | 5.31%   |
| More than 3000 | 39       | 4.31%   |
| 1001-2000      | 38       | 4.2%    |
| 2001-3000      | 21       | 2.32%   |
| Unknown        | 5        | 0.55%   |
| 0              | 1        | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD5000AAKX-08ERMA0 500GB                     | 2        | 2      | 2.7%    |
| WDC WD40EFRX-68WT0N0 4TB                         | 2        | 3      | 2.7%    |
| WDC WD10EZEX-22MFCA0 1TB                         | 2        | 2      | 2.7%    |
| Seagate ST500DM002-1BD142 500GB                  | 2        | 2      | 2.7%    |
| Seagate ST1000DM003-1CH162 1TB                   | 2        | 2      | 2.7%    |
| Hitachi HDS721010CLA332 1TB                      | 2        | 2      | 2.7%    |
| WDC WD75 00BPVT-16HXZ 752GB                      | 1        | 1      | 1.35%   |
| WDC WD6400BEVT-60A0RT0 640GB                     | 1        | 1      | 1.35%   |
| WDC WD6002FZWX-00GBGB0 6TB                       | 1        | 1      | 1.35%   |
| WDC WD5000AAKS-65V0A0 500GB                      | 1        | 1      | 1.35%   |
| WDC WD40PURZ-85TTDY0 4TB                         | 1        | 1      | 1.35%   |
| WDC WD4003FZEX-00Z4SA0 4TB                       | 1        | 2      | 1.35%   |
| WDC WD20EARX-008FB0 2TB                          | 1        | 2      | 1.35%   |
| WDC WD10PURX-64D85Y0 1TB                         | 1        | 1      | 1.35%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1        | 1      | 1.35%   |
| WDC WD10EFRX-68FYTN0 1TB                         | 1        | 1      | 1.35%   |
| WDC WD10EARX-00N0YB0 1TB                         | 1        | 1      | 1.35%   |
| WDC WD10EARS-00Y5B1 1TB                          | 1        | 1      | 1.35%   |
| WDC WD1003FBYX-01Y7B1 1TB                        | 1        | 1      | 1.35%   |
| Toshiba MQ01ABD100 1TB                           | 1        | 1      | 1.35%   |
| Toshiba MK6465GSX 640GB                          | 1        | 1      | 1.35%   |
| Toshiba DT01ACA100 1TB                           | 1        | 1      | 1.35%   |
| Seagate ST500LT012-9WS142 500GB                  | 1        | 1      | 1.35%   |
| Seagate ST4000VX007-2DT166 4TB                   | 1        | 1      | 1.35%   |
| Seagate ST3750640NS 752GB                        | 1        | 2      | 1.35%   |
| Seagate ST3250823AS 250GB                        | 1        | 1      | 1.35%   |
| Seagate ST3250410AS 250GB                        | 1        | 1      | 1.35%   |
| Seagate ST3160815AS 160GB                        | 1        | 1      | 1.35%   |
| Seagate ST3160811AS 160GB                        | 1        | 1      | 1.35%   |
| Seagate ST31500341AS 1TB                         | 1        | 1      | 1.35%   |
| Seagate ST31000528AS 1TB                         | 1        | 1      | 1.35%   |
| Seagate ST2000DX002-2DV164 2TB                   | 1        | 1      | 1.35%   |
| Seagate ST1000DX001-1CM162 1TB                   | 1        | 1      | 1.35%   |
| Seagate ST1000DM010-2EP102 1TB                   | 1        | 1      | 1.35%   |
| Seagate ST1000DM003-9YN162 1TB                   | 1        | 1      | 1.35%   |
| SanDisk SSD PLUS 480GB                           | 1        | 1      | 1.35%   |
| SanDisk SD9SB8W-128G-1006 128GB SSD              | 1        | 1      | 1.35%   |
| Samsung Electronics SSD PM800 Series 2.5 256GB   | 1        | 1      | 1.35%   |
| Samsung Electronics SSD 980 PRO 2TB              | 1        | 2      | 1.35%   |
| Samsung Electronics SSD 980 PRO 1TB              | 1        | 1      | 1.35%   |
| Samsung Electronics SSD 870 EVO 1TB              | 1        | 1      | 1.35%   |
| Samsung Electronics SP1614C 160GB                | 1        | 1      | 1.35%   |
| Samsung Electronics MZ7TE128HMGR-000H1 128GB SSD | 1        | 1      | 1.35%   |
| Samsung Electronics HD642JJ 640GB                | 1        | 1      | 1.35%   |
| Samsung Electronics HD322GJ 320GB                | 1        | 1      | 1.35%   |
| Samsung Electronics HD321KJ 320GB                | 1        | 1      | 1.35%   |
| Samsung Electronics HD103SI 1TB                  | 1        | 1      | 1.35%   |
| PNY CS3030 500GB SSD                             | 1        | 1      | 1.35%   |
| OCZ VERTEX4 256GB SSD                            | 1        | 1      | 1.35%   |
| Maxtor STM3160211AS 160GB                        | 1        | 1      | 1.35%   |
| Maxtor 7Y250M0 250GB                             | 1        | 1      | 1.35%   |
| LITEONIT LCT-128M3S 128GB SSD                    | 1        | 1      | 1.35%   |
| LITEONIT LCS-128M6S 128GB SSD                    | 1        | 1      | 1.35%   |
| Kingston SV300S37A60G 64GB SSD                   | 1        | 1      | 1.35%   |
| Kingston SV300S37A120G 120GB SSD                 | 1        | 1      | 1.35%   |
| Kingston SH103S3240G 240GB SSD                   | 1        | 1      | 1.35%   |
| Kingston SA400S37240G 240GB SSD                  | 1        | 1      | 1.35%   |
| Intenso SSD 120GB                                | 1        | 1      | 1.35%   |
| Intel SSDSC2BW240H6 240GB                        | 1        | 1      | 1.35%   |
| Hitachi HUA722010CLA330 1TB                      | 1        | 1      | 1.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 18       | 22     | 24.66%  |
| Seagate             | 17       | 18     | 23.29%  |
| Samsung Electronics | 10       | 11     | 13.7%   |
| Hitachi             | 8        | 8      | 10.96%  |
| Kingston            | 4        | 4      | 5.48%   |
| Toshiba             | 3        | 3      | 4.11%   |
| SanDisk             | 2        | 2      | 2.74%   |
| Maxtor              | 2        | 2      | 2.74%   |
| LITEONIT            | 2        | 2      | 2.74%   |
| PNY                 | 1        | 1      | 1.37%   |
| OCZ                 | 1        | 1      | 1.37%   |
| Intenso             | 1        | 1      | 1.37%   |
| Intel               | 1        | 1      | 1.37%   |
| HGST                | 1        | 2      | 1.37%   |
| Crucial             | 1        | 1      | 1.37%   |
| A-DATA Technology   | 1        | 1      | 1.37%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 18       | 22     | 33.33%  |
| Seagate             | 17       | 18     | 31.48%  |
| Hitachi             | 8        | 8      | 14.81%  |
| Samsung Electronics | 5        | 5      | 9.26%   |
| Toshiba             | 3        | 3      | 5.56%   |
| Maxtor              | 2        | 2      | 3.7%    |
| HGST                | 1        | 2      | 1.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 50       | 60     | 72.46%  |
| SSD  | 15       | 15     | 21.74%  |
| NVMe | 4        | 5      | 5.8%    |

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
| Detected | 607      | 1555   | 64.57%  |
| Works    | 270      | 597    | 28.72%  |
| Malfunc  | 63       | 80     | 6.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 587      | 46.88%  |
| AMD                           | 262      | 20.93%  |
| Samsung Electronics           | 93       | 7.43%   |
| SanDisk                       | 53       | 4.23%   |
| ASMedia Technology            | 45       | 3.59%   |
| Marvell Technology Group      | 30       | 2.4%    |
| Phison Electronics            | 24       | 1.92%   |
| JMicron Technology            | 24       | 1.92%   |
| Nvidia                        | 20       | 1.6%    |
| SK hynix                      | 16       | 1.28%   |
| Kingston Technology Company   | 16       | 1.28%   |
| Silicon Motion                | 11       | 0.88%   |
| Micron/Crucial Technology     | 9        | 0.72%   |
| LSI Logic / Symbios Logic     | 9        | 0.72%   |
| Realtek Semiconductor         | 8        | 0.64%   |
| Silicon Image                 | 6        | 0.48%   |
| ADATA Technology              | 6        | 0.48%   |
| VIA Technologies              | 5        | 0.4%    |
| KIOXIA                        | 5        | 0.4%    |
| Seagate Technology            | 4        | 0.32%   |
| Micron Technology             | 4        | 0.32%   |
| OCZ Technology Group          | 2        | 0.16%   |
| Union Memory (Shenzhen)       | 1        | 0.08%   |
| Toshiba America Info Systems  | 1        | 0.08%   |
| Shenzhen Longsys Electronics  | 1        | 0.08%   |
| MAXIO Technology (Hangzhou)   | 1        | 0.08%   |
| Lite-On IT Corp. / Plextor    | 1        | 0.08%   |
| Integrated Technology Express | 1        | 0.08%   |
| HighPoint Technologies        | 1        | 0.08%   |
| Chelsio Communications        | 1        | 0.08%   |
| Broadcom / LSI                | 1        | 0.08%   |
| Biwin Storage Technology      | 1        | 0.08%   |
| Areca Technology              | 1        | 0.08%   |
| Adaptec                       | 1        | 0.08%   |
| 3ware                         | 1        | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 149      | 9.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 85       | 5.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 52       | 3.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 49       | 3.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 49       | 3.2%    |
| AMD 400 Series Chipset SATA Controller                                                  | 48       | 3.13%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 42       | 2.74%   |
| Intel SATA Controller [RAID mode]                                                       | 39       | 2.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 39       | 2.55%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 38       | 2.48%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 33       | 2.15%   |
| AMD 500 Series Chipset SATA Controller                                                  | 28       | 1.83%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 27       | 1.76%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 25       | 1.63%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 24       | 1.57%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 23       | 1.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 21       | 1.37%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 21       | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 21       | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 21       | 1.37%   |
| AMD FCH SATA Controller D                                                               | 21       | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 20       | 1.31%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 18       | 1.17%   |
| Samsung NVMe SSD Controller 980                                                         | 16       | 1.04%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 16       | 1.04%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 16       | 1.04%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 15       | 0.98%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 14       | 0.91%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 13       | 0.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 12       | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 12       | 0.78%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 12       | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 11       | 0.72%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 11       | 0.72%   |
| SanDisk Non-Volatile memory controller                                                  | 10       | 0.65%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 10       | 0.65%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 10       | 0.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 10       | 0.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 10       | 0.65%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 10       | 0.65%   |
| AMD 300 Series Chipset SATA Controller                                                  | 10       | 0.65%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 9        | 0.59%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 9        | 0.59%   |
| Phison E12 NVMe Controller                                                              | 9        | 0.59%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                            | 9        | 0.59%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 9        | 0.59%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 9        | 0.59%   |
| SK hynix Gold P31 SSD                                                                   | 8        | 0.52%   |
| Nvidia MCP61 SATA Controller                                                            | 8        | 0.52%   |
| JMicron JMB368 IDE controller                                                           | 8        | 0.52%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 8        | 0.52%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 8        | 0.52%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 8        | 0.52%   |
| AMD FCH IDE Controller                                                                  | 8        | 0.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7        | 0.46%   |
| Nvidia MCP61 IDE                                                                        | 7        | 0.46%   |
| Kingston Company Company Non-Volatile memory controller                                 | 7        | 0.46%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 7        | 0.46%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 7        | 0.46%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 7        | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 712      | 58.89%  |
| NVMe | 235      | 19.44%  |
| IDE  | 176      | 14.56%  |
| RAID | 73       | 6.04%   |
| SAS  | 8        | 0.66%   |
| SCSI | 5        | 0.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 599      | 68.61%  |
| AMD    | 274      | 31.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor               | 18       | 2.06%   |
| Intel Core i7-2600 CPU @ 3.40GHz                | 14       | 1.6%    |
| Intel Core i5-4460 CPU @ 3.20GHz                | 14       | 1.6%    |
| Intel Core i5-3470 CPU @ 3.20GHz                | 13       | 1.49%   |
| AMD Ryzen 5 5600X 6-Core Processor              | 13       | 1.49%   |
| Intel Core i7-4770 CPU @ 3.40GHz                | 11       | 1.26%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 11       | 1.26%   |
| AMD FX-8350 Eight-Core Processor                | 10       | 1.15%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 9        | 1.03%   |
| Intel Core i7-4790 CPU @ 3.60GHz                | 9        | 1.03%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz            | 9        | 1.03%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 9        | 1.03%   |
| Intel Core i7-4790K CPU @ 4.00GHz               | 8        | 0.92%   |
| Intel Core i5-4590 CPU @ 3.30GHz                | 8        | 0.92%   |
| Intel Core i3 CPU 540 @ 3.07GHz                 | 8        | 0.92%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz            | 8        | 0.92%   |
| AMD Ryzen 9 5900X 12-Core Processor             | 8        | 0.92%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 7        | 0.8%    |
| Intel Core i7-3770 CPU @ 3.40GHz                | 7        | 0.8%    |
| Intel Core i5-2400 CPU @ 3.10GHz                | 7        | 0.8%    |
| Intel Core i3-3220 CPU @ 3.30GHz                | 7        | 0.8%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics     | 7        | 0.8%    |
| Intel Core i9-9900K CPU @ 3.60GHz               | 6        | 0.69%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 6        | 0.69%   |
| Intel Core i5-4570 CPU @ 3.20GHz                | 6        | 0.69%   |
| Intel Core i3-6100 CPU @ 3.70GHz                | 6        | 0.69%   |
| Intel Core i3-4150 CPU @ 3.50GHz                | 6        | 0.69%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 6        | 0.69%   |
| Intel Core i3-2120 CPU @ 3.30GHz                | 6        | 0.69%   |
| Intel 12th Gen Core i9-12900K                   | 6        | 0.69%   |
| AMD Ryzen 9 5950X 16-Core Processor             | 6        | 0.69%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 6        | 0.69%   |
| AMD A10-7700K Radeon R7, 10 Compute Cores 4C+6G | 6        | 0.69%   |
| Intel Core i7-5820K CPU @ 3.30GHz               | 5        | 0.57%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 5        | 0.57%   |
| Intel Core i5-6600K CPU @ 3.50GHz               | 5        | 0.57%   |
| Intel Core i5-3570 CPU @ 3.40GHz                | 5        | 0.57%   |
| Intel Core i3-10100 CPU @ 3.60GHz               | 5        | 0.57%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz           | 5        | 0.57%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 5        | 0.57%   |
| AMD Ryzen 7 5700G with Radeon Graphics          | 5        | 0.57%   |
| AMD Ryzen 7 1700 Eight-Core Processor           | 5        | 0.57%   |
| AMD Ryzen 5 5600G with Radeon Graphics          | 5        | 0.57%   |
| AMD Phenom II X4 965 Processor                  | 5        | 0.57%   |
| AMD Phenom II X4 955 Processor                  | 5        | 0.57%   |
| AMD FX-4300 Quad-Core Processor                 | 5        | 0.57%   |
| Intel Pentium CPU G3220 @ 3.00GHz               | 4        | 0.46%   |
| Intel Core i7-9700K CPU @ 3.60GHz               | 4        | 0.46%   |
| Intel Core i7-8700K CPU @ 3.70GHz               | 4        | 0.46%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 4        | 0.46%   |
| Intel Core i7-10700 CPU @ 2.90GHz               | 4        | 0.46%   |
| Intel Core i5-9400F CPU @ 2.90GHz               | 4        | 0.46%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 4        | 0.46%   |
| Intel Core i5-3570K CPU @ 3.40GHz               | 4        | 0.46%   |
| Intel Core i5-2500 CPU @ 3.30GHz                | 4        | 0.46%   |
| Intel Core i3-4160 CPU @ 3.60GHz                | 4        | 0.46%   |
| Intel Core i3-3240 CPU @ 3.40GHz                | 4        | 0.46%   |
| Intel Core i3-2100 CPU @ 3.10GHz                | 4        | 0.46%   |
| Intel Core i3 CPU 550 @ 3.20GHz                 | 4        | 0.46%   |
| Intel Core 2 Quad CPU Q8200 @ 2.33GHz           | 4        | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 159      | 18.21%  |
| Intel Core i7           | 125      | 14.32%  |
| Intel Core i3           | 88       | 10.08%  |
| AMD Ryzen 5             | 64       | 7.33%   |
| Intel Xeon              | 53       | 6.07%   |
| Other                   | 44       | 5.04%   |
| AMD Ryzen 7             | 41       | 4.7%    |
| AMD FX                  | 34       | 3.89%   |
| Intel Core 2 Duo        | 29       | 3.32%   |
| Intel Celeron           | 25       | 2.86%   |
| AMD Ryzen 9             | 23       | 2.63%   |
| Intel Pentium           | 20       | 2.29%   |
| Intel Core 2 Quad       | 20       | 2.29%   |
| AMD A10                 | 15       | 1.72%   |
| AMD Ryzen 3             | 14       | 1.6%    |
| AMD Phenom II X4        | 14       | 1.6%    |
| Intel Core i9           | 12       | 1.37%   |
| AMD A8                  | 10       | 1.15%   |
| Intel Pentium Dual-Core | 8        | 0.92%   |
| AMD A4                  | 8        | 0.92%   |
| AMD Phenom II X6        | 6        | 0.69%   |
| AMD Ryzen Threadripper  | 5        | 0.57%   |
| AMD Athlon II X2        | 5        | 0.57%   |
| Intel Core 2            | 4        | 0.46%   |
| AMD Ryzen 5 PRO         | 4        | 0.46%   |
| AMD A6                  | 4        | 0.46%   |
| Intel Pentium Dual      | 3        | 0.34%   |
| Intel Pentium 4         | 3        | 0.34%   |
| Intel Atom              | 3        | 0.34%   |
| AMD Athlon II X4        | 3        | 0.34%   |
| AMD Athlon 64 X2        | 3        | 0.34%   |
| AMD Athlon              | 3        | 0.34%   |
| AMD Ryzen 7 PRO         | 2        | 0.23%   |
| AMD Phenom II X2        | 2        | 0.23%   |
| AMD Phenom              | 2        | 0.23%   |
| AMD Athlon II X3        | 2        | 0.23%   |
| AMD Athlon 64           | 2        | 0.23%   |
| Intel Pentium Gold      | 1        | 0.11%   |
| Intel Genuine           | 1        | 0.11%   |
| Intel Core 2 Extreme    | 1        | 0.11%   |
| Intel Celeron D         | 1        | 0.11%   |
| AMD Ryzen Embedded      | 1        | 0.11%   |
| AMD Ryzen 3 PRO         | 1        | 0.11%   |
| AMD GX                  | 1        | 0.11%   |
| AMD EPYC                | 1        | 0.11%   |
| AMD E1                  | 1        | 0.11%   |
| AMD E                   | 1        | 0.11%   |
| AMD Athlon X4           | 1        | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 355      | 40.66%  |
| 2      | 215      | 24.63%  |
| 6      | 126      | 14.43%  |
| 8      | 87       | 9.97%   |
| 12     | 28       | 3.21%   |
| 16     | 20       | 2.29%   |
| 1      | 17       | 1.95%   |
| 10     | 9        | 1.03%   |
| 3      | 9        | 1.03%   |
| 32     | 2        | 0.23%   |
| 28     | 2        | 0.23%   |
| 64     | 1        | 0.11%   |
| 24     | 1        | 0.11%   |
| 14     | 1        | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 857      | 98.17%  |
| 2      | 16       | 1.83%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 522      | 59.79%  |
| 1      | 351      | 40.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 872      | 99.89%  |
| Unknown        | 1        | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 560      | 62.92%  |
| 0x306c3    | 37       | 4.16%   |
| 0x206a7    | 22       | 2.47%   |
| 0x306a9    | 21       | 2.36%   |
| 0x08701021 | 17       | 1.91%   |
| 0x906e9    | 16       | 1.8%    |
| 0x506e3    | 16       | 1.8%    |
| 0x1067a    | 11       | 1.24%   |
| 0x0a201016 | 11       | 1.24%   |
| 0x06003106 | 11       | 1.24%   |
| 0xa0653    | 10       | 1.12%   |
| 0x906ea    | 10       | 1.12%   |
| 0x06000852 | 9        | 1.01%   |
| 0x90672    | 8        | 0.9%    |
| 0x306f2    | 8        | 0.9%    |
| 0x010000c8 | 7        | 0.79%   |
| 0x06001119 | 6        | 0.67%   |
| 0xa0671    | 5        | 0.56%   |
| 0xa0655    | 5        | 0.56%   |
| 0x106a5    | 5        | 0.56%   |
| 0x0a50000c | 5        | 0.56%   |
| 0x08108109 | 5        | 0.56%   |
| 0x0800820d | 5        | 0.56%   |
| 0x906ec    | 4        | 0.45%   |
| 0x08701013 | 4        | 0.45%   |
| 0x706a8    | 3        | 0.34%   |
| 0x0a201204 | 3        | 0.34%   |
| 0x0a201009 | 3        | 0.34%   |
| 0x0830104d | 3        | 0.34%   |
| 0x0810100b | 3        | 0.34%   |
| 0x00000000 | 3        | 0.34%   |
| 0x906ed    | 2        | 0.22%   |
| 0x906eb    | 2        | 0.22%   |
| 0x90675    | 2        | 0.22%   |
| 0x806ec    | 2        | 0.22%   |
| 0x706a1    | 2        | 0.22%   |
| 0x50654    | 2        | 0.22%   |
| 0x20655    | 2        | 0.22%   |
| 0x10676    | 2        | 0.22%   |
| 0x0a20120a | 2        | 0.22%   |
| 0x08101016 | 2        | 0.22%   |
| 0x08001138 | 2        | 0.22%   |
| 0x08001126 | 2        | 0.22%   |
| 0x010000db | 2        | 0.22%   |
| 0x906c0    | 1        | 0.11%   |
| 0x806e9    | 1        | 0.11%   |
| 0x806c2    | 1        | 0.11%   |
| 0x806c1    | 1        | 0.11%   |
| 0x6fd      | 1        | 0.11%   |
| 0x6f6      | 1        | 0.11%   |
| 0x406f1    | 1        | 0.11%   |
| 0x406e3    | 1        | 0.11%   |
| 0x306e4    | 1        | 0.11%   |
| 0x30679    | 1        | 0.11%   |
| 0x30661    | 1        | 0.11%   |
| 0x206d7    | 1        | 0.11%   |
| 0x206c2    | 1        | 0.11%   |
| 0x20652    | 1        | 0.11%   |
| 0x106e5    | 1        | 0.11%   |
| 0x10677    | 1        | 0.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 129      | 14.78%  |
| IvyBridge        | 75       | 8.59%   |
| KabyLake         | 64       | 7.33%   |
| SandyBridge      | 61       | 6.99%   |
| Zen 2            | 56       | 6.41%   |
| Penryn           | 54       | 6.19%   |
| Skylake          | 52       | 5.96%   |
| Zen 3            | 47       | 5.38%   |
| Piledriver       | 44       | 5.04%   |
| K10              | 34       | 3.89%   |
| Zen+             | 30       | 3.44%   |
| Westmere         | 30       | 3.44%   |
| CometLake        | 28       | 3.21%   |
| Unknown          | 27       | 3.09%   |
| Zen              | 25       | 2.86%   |
| Core             | 20       | 2.29%   |
| Steamroller      | 16       | 1.83%   |
| Nehalem          | 15       | 1.72%   |
| Alderlake Hybrid | 9        | 1.03%   |
| Goldmont plus    | 8        | 0.92%   |
| Broadwell        | 7        | 0.8%    |
| Silvermont       | 6        | 0.69%   |
| Icelake          | 6        | 0.69%   |
| Excavator        | 6        | 0.69%   |
| K8 Hammer        | 5        | 0.57%   |
| Bulldozer        | 5        | 0.57%   |
| NetBurst         | 4        | 0.46%   |
| TigerLake        | 3        | 0.34%   |
| K10 Llano        | 2        | 0.23%   |
| Bobcat           | 2        | 0.23%   |
| Tremont          | 1        | 0.11%   |
| Puma             | 1        | 0.11%   |
| Bonnell          | 1        | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 370      | 39.91%  |
| Intel                                        | 293      | 31.61%  |
| AMD                                          | 254      | 27.4%   |
| ASPEED Technology                            | 6        | 0.65%   |
| Matrox Electronics Systems                   | 3        | 0.32%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 60       | 6.39%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 28       | 2.98%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 27       | 2.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 27       | 2.88%   |
| Intel HD Graphics 530                                                       | 25       | 2.66%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 22       | 2.34%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 16       | 1.7%    |
| Nvidia GK208B [GeForce GT 730]                                              | 16       | 1.7%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 16       | 1.7%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 15       | 1.6%    |
| AMD Kaveri [Radeon R7 Graphics]                                             | 14       | 1.49%   |
| Nvidia GK208B [GeForce GT 710]                                              | 13       | 1.38%   |
| Intel AlderLake-S GT1                                                       | 13       | 1.38%   |
| Intel HD Graphics 630                                                       | 12       | 1.28%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 11       | 1.17%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 11       | 1.17%   |
| Nvidia GT218 [GeForce 210]                                                  | 10       | 1.06%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 1.06%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 10       | 1.06%   |
| AMD Cezanne                                                                 | 10       | 1.06%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 9        | 0.96%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 9        | 0.96%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 9        | 0.96%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 9        | 0.96%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 8        | 0.85%   |
| Nvidia G96C [GeForce 9500 GT]                                               | 8        | 0.85%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 8        | 0.85%   |
| Intel Core Processor Integrated Graphics Controller                         | 8        | 0.85%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 8        | 0.85%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 8        | 0.85%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 8        | 0.85%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 7        | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 7        | 0.75%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 7        | 0.75%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 6        | 0.64%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 6        | 0.64%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 6        | 0.64%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 6        | 0.64%   |
| Nvidia GF119 [GeForce GT 610]                                               | 6        | 0.64%   |
| Nvidia GF108 [GeForce GT 730]                                               | 6        | 0.64%   |
| Nvidia GA102 [GeForce RTX 3080 Ti]                                          | 6        | 0.64%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 6        | 0.64%   |
| ASPEED Technology ASPEED Graphics Family                                    | 6        | 0.64%   |
| AMD Trinity 2 [Radeon HD 7480D]                                             | 6        | 0.64%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 6        | 0.64%   |
| AMD Caicos XT [Radeon HD 7470/8470 / R5 235/310 OEM]                        | 6        | 0.64%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 5        | 0.53%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 5        | 0.53%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                           | 5        | 0.53%   |
| Intel RocketLake-S GT1 [UHD Graphics 750]                                   | 5        | 0.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 5        | 0.53%   |
| AMD RS780L [Radeon 3000]                                                    | 5        | 0.53%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 5        | 0.53%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 4        | 0.43%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 4        | 0.43%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 4        | 0.43%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 4        | 0.43%   |
| AMD RV730 PRO [Radeon HD 4650]                                              | 4        | 0.43%   |
| AMD RS880 [Radeon HD 4200]                                                  | 4        | 0.43%   |
| AMD Renoir                                                                  | 4        | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 338      | 38.5%   |
| 1 x Intel                | 251      | 28.59%  |
| 1 x AMD                  | 235      | 26.77%  |
| Intel + Nvidia           | 16       | 1.82%   |
| AMD + Nvidia             | 9        | 1.03%   |
| 2 x AMD                  | 6        | 0.68%   |
| 2 x Nvidia               | 5        | 0.57%   |
| Intel + AMD              | 5        | 0.57%   |
| 1 x ASPEED               | 4        | 0.46%   |
| Other                    | 2        | 0.23%   |
| Nvidia + ASPEED          | 2        | 0.23%   |
| 1 x Matrox               | 2        | 0.23%   |
| 1 x XGI                  | 1        | 0.11%   |
| Nvidia + Matrox          | 1        | 0.11%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 597      | 68.23%  |
| Proprietary | 227      | 25.94%  |
| Unknown     | 51       | 5.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 646      | 73.24%  |
| 1.01-2.0   | 51       | 5.78%   |
| 0.51-1.0   | 49       | 5.56%   |
| 7.01-8.0   | 40       | 4.54%   |
| 3.01-4.0   | 37       | 4.2%    |
| 0.01-0.5   | 22       | 2.49%   |
| 5.01-6.0   | 15       | 1.7%    |
| 8.01-16.0  | 13       | 1.47%   |
| 4.01-5.0   | 4        | 0.45%   |
| 2.01-3.0   | 4        | 0.45%   |
| 16.01-24.0 | 1        | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 145      | 16.08%  |
| Dell                 | 103      | 11.42%  |
| Goldstar             | 93       | 10.31%  |
| BenQ                 | 52       | 5.76%   |
| Hewlett-Packard      | 50       | 5.54%   |
| Acer                 | 49       | 5.43%   |
| Philips              | 45       | 4.99%   |
| Ancor Communications | 43       | 4.77%   |
| AOC                  | 35       | 3.88%   |
| Lenovo               | 25       | 2.77%   |
| ViewSonic            | 23       | 2.55%   |
| ASUSTek Computer     | 21       | 2.33%   |
| LG Electronics       | 13       | 1.44%   |
| Iiyama               | 13       | 1.44%   |
| Unknown              | 12       | 1.33%   |
| Sony                 | 12       | 1.33%   |
| Fujitsu Siemens      | 9        | 1%      |
| Sceptre Tech         | 8        | 0.89%   |
| Panasonic            | 7        | 0.78%   |
| NEC Computers        | 6        | 0.67%   |
| Vizio                | 5        | 0.55%   |
| Vestel Elektronik    | 5        | 0.55%   |
| Onkyo                | 5        | 0.55%   |
| Gigabyte Technology  | 5        | 0.55%   |
| Eizo                 | 5        | 0.55%   |
| Unknown              | 5        | 0.55%   |
| Toshiba              | 4        | 0.44%   |
| Sharp                | 4        | 0.44%   |
| RTK                  | 4        | 0.44%   |
| MStar                | 4        | 0.44%   |
| Unknown (XXX)        | 3        | 0.33%   |
| MSI                  | 3        | 0.33%   |
| Medion               | 3        | 0.33%   |
| HKC                  | 3        | 0.33%   |
| Apple                | 3        | 0.33%   |
| ___                  | 2        | 0.22%   |
| Xiaomi               | 2        | 0.22%   |
| STA                  | 2        | 0.22%   |
| SKY                  | 2        | 0.22%   |
| Seiki                | 2        | 0.22%   |
| KTC                  | 2        | 0.22%   |
| Idek Iiyama          | 2        | 0.22%   |
| HUAWEI               | 2        | 0.22%   |
| Hitachi              | 2        | 0.22%   |
| HannStar             | 2        | 0.22%   |
| CTV                  | 2        | 0.22%   |
| Compal               | 2        | 0.22%   |
| AU Optronics         | 2        | 0.22%   |
| Zoran                | 1        | 0.11%   |
| YUK                  | 1        | 0.11%   |
| YCT                  | 1        | 0.11%   |
| Westinghouse         | 1        | 0.11%   |
| Wacom                | 1        | 0.11%   |
| Viotek               | 1        | 0.11%   |
| Unknown (AAA)        | 1        | 0.11%   |
| TCT                  | 1        | 0.11%   |
| Targa Visionary      | 1        | 0.11%   |
| Sunplus              | 1        | 0.11%   |
| SPU                  | 1        | 0.11%   |
| Skyworth             | 1        | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                       | 17       | 1.79%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                     | 8        | 0.84%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch       | 7        | 0.74%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 5        | 0.53%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                 | 5        | 0.53%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 5        | 0.53%   |
| Unknown                                                                 | 5        | 0.53%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 4        | 0.42%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 4        | 0.42%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch       | 4        | 0.42%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                 | 4        | 0.42%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 4        | 0.42%   |
| Goldstar LCD Monitor GSM5AB8 1920x1080 480x270mm 21.7-inch              | 4        | 0.42%   |
| BenQ GL2760 BNQ78D5 1920x1080 598x336mm 27.0-inch                       | 4        | 0.42%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch   | 4        | 0.42%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch   | 3        | 0.32%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch      | 3        | 0.32%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 3        | 0.32%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                      | 3        | 0.32%   |
| MStar Demo MST0030 1920x540 708x398mm 32.0-inch                         | 3        | 0.32%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                | 3        | 0.32%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch               | 3        | 0.32%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                  | 3        | 0.32%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                  | 3        | 0.32%   |
| Dell U2410 DELF016 1920x1200 518x324mm 24.1-inch                        | 3        | 0.32%   |
| AOC Q27G1WG4 AOC2701 2560x1440 597x336mm 27.0-inch                      | 3        | 0.32%   |
| AOC G2790G4 AOC2790 1920x1080 598x336mm 27.0-inch                       | 3        | 0.32%   |
| AOC G2490W1G4 AOC2490 1920x1080 527x296mm 23.8-inch                     | 3        | 0.32%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch        | 3        | 0.32%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch        | 3        | 0.32%   |
| ViewSonic VA2246 SERIES VSC6F2E 1920x1080 477x268mm 21.5-inch           | 2        | 0.21%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch           | 2        | 0.21%   |
| STA SEMP LEDTV STA0030 1920x1080 708x398mm 32.0-inch                    | 2        | 0.21%   |
| SKY SKYWORTH SKY0001 1920x1080 885x498mm 40.0-inch                      | 2        | 0.21%   |
| Sceptre Tech Sceptre F27 SPT0ABF 1920x1080 409x230mm 18.5-inch          | 2        | 0.21%   |
| Sceptre Tech Sceptre C27 SPT0AD7 1920x1080 598x336mm 27.0-inch          | 2        | 0.21%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 2        | 0.21%   |
| Samsung Electronics SyncMaster SAM0473 2048x1152 510x287mm 23.0-inch    | 2        | 0.21%   |
| Samsung Electronics SyncMaster SAM044C 1680x1050 474x296mm 22.0-inch    | 2        | 0.21%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch       | 2        | 0.21%   |
| Samsung Electronics LS28AG700N SAM7177 3840x2160 632x360mm 28.6-inch    | 2        | 0.21%   |
| Samsung Electronics LCD Monitor SyncMaster 1280x1024                    | 2        | 0.21%   |
| Samsung Electronics LCD Monitor SAM7032 1920x1080 1210x680mm 54.6-inch  | 2        | 0.21%   |
| Samsung Electronics LCD Monitor SAM0FB9 3840x2160 1872x1053mm 84.6-inch | 2        | 0.21%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch | 2        | 0.21%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch    | 2        | 0.21%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 1020x570mm 46.0-inch  | 2        | 0.21%   |
| Samsung Electronics LCD Monitor SAM07BA 1920x1080 480x270mm 21.7-inch   | 2        | 0.21%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 2        | 0.21%   |
| Onkyo TX-NR747 ONK0F71 1920x1200 550x309mm 24.8-inch                    | 2        | 0.21%   |
| HKC 24N1 HKC2413 1920x1080 527x296mm 23.8-inch                          | 2        | 0.21%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch                 | 2        | 0.21%   |
| Goldstar TV GSM75A2 1360x768 700x392mm 31.6-inch                        | 2        | 0.21%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 2        | 0.21%   |
| Goldstar HDR 4K GSM774F 3840x2160 697x392mm 31.5-inch                   | 2        | 0.21%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                   | 2        | 0.21%   |
| Goldstar E2251 GSM586D 1920x1080 480x270mm 21.7-inch                    | 2        | 0.21%   |
| Gigabyte Technology AORUS FV43U GBT4300 3840x2160 697x392mm 31.5-inch   | 2        | 0.21%   |
| Dell U2415 DELA0B9 1920x1200 518x324mm 24.1-inch                        | 2        | 0.21%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                     | 2        | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 422      | 48.23%  |
| 3840x2160 (4K)     | 107      | 12.23%  |
| 2560x1440 (QHD)    | 67       | 7.66%   |
| 1280x1024 (SXGA)   | 46       | 5.26%   |
| 1680x1050 (WSXGA+) | 39       | 4.46%   |
| 1366x768 (WXGA)    | 28       | 3.2%    |
| 1920x1200 (WUXGA)  | 25       | 2.86%   |
| 1600x900 (HD+)     | 21       | 2.4%    |
| 1440x900 (WXGA+)   | 21       | 2.4%    |
| 3440x1440          | 13       | 1.49%   |
| 2560x1080          | 12       | 1.37%   |
| 1360x768           | 12       | 1.37%   |
| 1920x540           | 9        | 1.03%   |
| Unknown            | 9        | 1.03%   |
| 3840x1080          | 6        | 0.69%   |
| 1280x720 (HD)      | 5        | 0.57%   |
| 2288x1287          | 4        | 0.46%   |
| 2048x1152          | 4        | 0.46%   |
| 1024x768 (XGA)     | 4        | 0.46%   |
| 2560x1600          | 2        | 0.23%   |
| 1600x1200          | 2        | 0.23%   |
| 1400x1050          | 2        | 0.23%   |
| 720x480            | 1        | 0.11%   |
| 5760x2160          | 1        | 0.11%   |
| 4480x1440          | 1        | 0.11%   |
| 4480x1080          | 1        | 0.11%   |
| 4080x2058          | 1        | 0.11%   |
| 3840x2560          | 1        | 0.11%   |
| 3840x1600          | 1        | 0.11%   |
| 3360x1080          | 1        | 0.11%   |
| 2464x900           | 1        | 0.11%   |
| 2048x1536          | 1        | 0.11%   |
| 1920x800           | 1        | 0.11%   |
| 1920x2160          | 1        | 0.11%   |
| 1280x960           | 1        | 0.11%   |
| 1280x800 (WXGA)    | 1        | 0.11%   |
| 1280x768           | 1        | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 130      | 14.43%  |
| 23      | 128      | 14.21%  |
| 24      | 120      | 13.32%  |
| 21      | 95       | 10.54%  |
| Unknown | 55       | 6.1%    |
| 19      | 46       | 5.11%   |
| 31      | 42       | 4.66%   |
| 22      | 32       | 3.55%   |
| 17      | 27       | 3%      |
| 18      | 24       | 2.66%   |
| 20      | 21       | 2.33%   |
| 34      | 20       | 2.22%   |
| 32      | 20       | 2.22%   |
| 84      | 17       | 1.89%   |
| 72      | 11       | 1.22%   |
| 54      | 11       | 1.22%   |
| 15      | 11       | 1.22%   |
| 40      | 9        | 1%      |
| 43      | 7        | 0.78%   |
| 25      | 7        | 0.78%   |
| 52      | 6        | 0.67%   |
| 28      | 6        | 0.67%   |
| 65      | 5        | 0.55%   |
| 46      | 5        | 0.55%   |
| 142     | 4        | 0.44%   |
| 48      | 4        | 0.44%   |
| 42      | 4        | 0.44%   |
| 37      | 4        | 0.44%   |
| 26      | 4        | 0.44%   |
| 55      | 3        | 0.33%   |
| 29      | 3        | 0.33%   |
| 13      | 3        | 0.33%   |
| 57      | 2        | 0.22%   |
| 14      | 2        | 0.22%   |
| 12      | 2        | 0.22%   |
| 100     | 1        | 0.11%   |
| 74      | 1        | 0.11%   |
| 64      | 1        | 0.11%   |
| 63      | 1        | 0.11%   |
| 61      | 1        | 0.11%   |
| 50      | 1        | 0.11%   |
| 49      | 1        | 0.11%   |
| 36      | 1        | 0.11%   |
| 33      | 1        | 0.11%   |
| 30      | 1        | 0.11%   |
| 16      | 1        | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 350      | 40%     |
| 401-500        | 192      | 21.94%  |
| 601-700        | 68       | 7.77%   |
| Unknown        | 55       | 6.29%   |
| 701-800        | 41       | 4.69%   |
| 1001-1500      | 41       | 4.69%   |
| 301-350        | 38       | 4.34%   |
| 1501-2000      | 29       | 3.31%   |
| 351-400        | 27       | 3.09%   |
| 801-900        | 13       | 1.49%   |
| 901-1000       | 11       | 1.26%   |
| More than 2000 | 5        | 0.57%   |
| 201-300        | 5        | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 593      | 71.62%  |
| 16/10   | 93       | 11.23%  |
| 5/4     | 46       | 5.56%   |
| Unknown | 45       | 5.43%   |
| 21/9    | 24       | 2.9%    |
| 4/3     | 11       | 1.33%   |
| 32/9    | 6        | 0.72%   |
| 3/2     | 4        | 0.48%   |
| 1.00    | 4        | 0.48%   |
| 6/5     | 2        | 0.24%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 299      | 33.9%   |
| 301-350        | 135      | 15.31%  |
| 151-200        | 96       | 10.88%  |
| 351-500        | 87       | 9.86%   |
| More than 1000 | 66       | 7.48%   |
| Unknown        | 55       | 6.24%   |
| 251-300        | 44       | 4.99%   |
| 141-150        | 43       | 4.88%   |
| 501-1000       | 35       | 3.97%   |
| 101-110        | 8        | 0.91%   |
| 71-80          | 4        | 0.45%   |
| 131-140        | 4        | 0.45%   |
| 81-90          | 3        | 0.34%   |
| 121-130        | 1        | 0.11%   |
| 111-120        | 1        | 0.11%   |
| 91-100         | 1        | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 514      | 60.19%  |
| 101-120       | 152      | 17.8%   |
| 1-50          | 61       | 7.14%   |
| Unknown       | 55       | 6.44%   |
| 121-160       | 49       | 5.74%   |
| 161-240       | 22       | 2.58%   |
| More than 240 | 1        | 0.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 657      | 74.49%  |
| 2     | 149      | 16.89%  |
| 0     | 62       | 7.03%   |
| 3     | 12       | 1.36%   |
| 4     | 2        | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 553      | 44.42%  |
| Intel                                  | 387      | 31.08%  |
| Qualcomm Atheros                       | 64       | 5.14%   |
| Broadcom                               | 39       | 3.13%   |
| Ralink Technology                      | 23       | 1.85%   |
| Ralink                                 | 20       | 1.61%   |
| Nvidia                                 | 18       | 1.45%   |
| TP-Link                                | 17       | 1.37%   |
| Microsoft                              | 12       | 0.96%   |
| Marvell Technology Group               | 11       | 0.88%   |
| Broadcom Limited                       | 11       | 0.88%   |
| MediaTek                               | 8        | 0.64%   |
| ASUSTek Computer                       | 8        | 0.64%   |
| Xiaomi                                 | 6        | 0.48%   |
| Aquantia                               | 6        | 0.48%   |
| Samsung Electronics                    | 5        | 0.4%    |
| NetGear                                | 5        | 0.4%    |
| D-Link System                          | 4        | 0.32%   |
| Mellanox Technologies                  | 3        | 0.24%   |
| D-Link                                 | 3        | 0.24%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.16%   |
| Qualcomm Atheros Communications        | 2        | 0.16%   |
| Linksys                                | 2        | 0.16%   |
| IMC Networks                           | 2        | 0.16%   |
| Huawei Technologies                    | 2        | 0.16%   |
| Encore Electronics                     | 2        | 0.16%   |
| ASIX Electronics                       | 2        | 0.16%   |
| Wilocity                               | 1        | 0.08%   |
| VIA Technologies                       | 1        | 0.08%   |
| Systec                                 | 1        | 0.08%   |
| Sundance Technology Inc / IC Plus      | 1        | 0.08%   |
| Sitecom Europe                         | 1        | 0.08%   |
| Sigma Designs                          | 1        | 0.08%   |
| Sagem                                  | 1        | 0.08%   |
| Qualcomm                               | 1        | 0.08%   |
| Pulse-Eight                            | 1        | 0.08%   |
| Provo Craft & Novelty                  | 1        | 0.08%   |
| Philips (or NXP)                       | 1        | 0.08%   |
| Motorola PCS                           | 1        | 0.08%   |
| Microchip Technology                   | 1        | 0.08%   |
| Micro Star International               | 1        | 0.08%   |
| LG Electronics                         | 1        | 0.08%   |
| JMicron Technology                     | 1        | 0.08%   |
| ICS Advent                             | 1        | 0.08%   |
| Exar                                   | 1        | 0.08%   |
| Edimax Technology                      | 1        | 0.08%   |
| Dresden Elektronik                     | 1        | 0.08%   |
| DisplayLink                            | 1        | 0.08%   |
| Cypress Semiconductor                  | 1        | 0.08%   |
| Chelsio Communications                 | 1        | 0.08%   |
| Belkin Components                      | 1        | 0.08%   |
| AVM                                    | 1        | 0.08%   |
| Apple                                  | 1        | 0.08%   |
| American Megatrends                    | 1        | 0.08%   |
| Unknown                                | 1        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 426      | 29.85%  |
| Realtek RTL8125 2.5GbE Controller                                 | 54       | 3.78%   |
| Intel Wi-Fi 6 AX200                                               | 47       | 3.29%   |
| Intel I211 Gigabit Network Connection                             | 40       | 2.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 38       | 2.66%   |
| Intel Ethernet Connection (2) I219-V                              | 31       | 2.17%   |
| Intel Ethernet Controller I225-V                                  | 26       | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 25       | 1.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22       | 1.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 22       | 1.54%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 21       | 1.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 17       | 1.19%   |
| Intel Ethernet Connection (7) I219-V                              | 14       | 0.98%   |
| Intel 82579V Gigabit Network Connection                           | 14       | 0.98%   |
| Intel Ethernet Connection I217-V                                  | 13       | 0.91%   |
| Realtek 802.11ac NIC                                              | 12       | 0.84%   |
| Intel Ethernet Connection (2) I218-V                              | 12       | 0.84%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 12       | 0.84%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 12       | 0.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11       | 0.77%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 11       | 0.77%   |
| Intel 82574L Gigabit Network Connection                           | 11       | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 10       | 0.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 10       | 0.7%    |
| Ralink MT7601U Wireless Adapter                                   | 9        | 0.63%   |
| Microsoft XBOX ACC                                                | 9        | 0.63%   |
| Nvidia MCP61 Ethernet                                             | 8        | 0.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8        | 0.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 7        | 0.49%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 7        | 0.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7        | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 0.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 7        | 0.49%   |
| Intel I210 Gigabit Network Connection                             | 7        | 0.49%   |
| Intel Ethernet Controller X550                                    | 7        | 0.49%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7        | 0.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6        | 0.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6        | 0.42%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 6        | 0.42%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 6        | 0.42%   |
| Intel Wireless-AC 9260                                            | 6        | 0.42%   |
| Intel Wireless 7260                                               | 6        | 0.42%   |
| Intel Ethernet Connection (14) I219-V                             | 6        | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5        | 0.35%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 5        | 0.35%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 5        | 0.35%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 5        | 0.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 0.35%   |
| Intel Ethernet Connection (5) I219-LM                             | 5        | 0.35%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5        | 0.35%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 4        | 0.28%   |
| TP-Link 802.11ac WLAN Adapter                                     | 4        | 0.28%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 4        | 0.28%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4        | 0.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4        | 0.28%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4        | 0.28%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 4        | 0.28%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.28%   |
| Intel Wireless 8265 / 8275                                        | 4        | 0.28%   |
| Intel Wireless 8260                                               | 4        | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 150      | 33.78%  |
| Realtek Semiconductor           | 110      | 24.77%  |
| Qualcomm Atheros                | 38       | 8.56%   |
| Ralink Technology               | 23       | 5.18%   |
| Broadcom                        | 22       | 4.95%   |
| Ralink                          | 20       | 4.5%    |
| TP-Link                         | 17       | 3.83%   |
| Microsoft                       | 12       | 2.7%    |
| MediaTek                        | 8        | 1.8%    |
| Broadcom Limited                | 8        | 1.8%    |
| ASUSTek Computer                | 8        | 1.8%    |
| NetGear                         | 5        | 1.13%   |
| D-Link System                   | 4        | 0.9%    |
| D-Link                          | 3        | 0.68%   |
| Qualcomm Atheros Communications | 2        | 0.45%   |
| Linksys                         | 2        | 0.45%   |
| IMC Networks                    | 2        | 0.45%   |
| Encore Electronics              | 2        | 0.45%   |
| Wilocity                        | 1        | 0.23%   |
| Sitecom Europe                  | 1        | 0.23%   |
| Sagem                           | 1        | 0.23%   |
| Philips (or NXP)                | 1        | 0.23%   |
| Micro Star International        | 1        | 0.23%   |
| Edimax Technology               | 1        | 0.23%   |
| Belkin Components               | 1        | 0.23%   |
| AVM                             | 1        | 0.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 47       | 10.49%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 22       | 4.91%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 21       | 4.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 17       | 3.79%   |
| Realtek 802.11ac NIC                                           | 12       | 2.68%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 12       | 2.68%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 11       | 2.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 10       | 2.23%   |
| Ralink MT7601U Wireless Adapter                                | 9        | 2.01%   |
| Microsoft XBOX ACC                                             | 9        | 2.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 8        | 1.79%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 7        | 1.56%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 7        | 1.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7        | 1.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 7        | 1.56%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 7        | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6        | 1.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6        | 1.34%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 6        | 1.34%   |
| Intel Wireless-AC 9260                                         | 6        | 1.34%   |
| Intel Wireless 7260                                            | 6        | 1.34%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 5        | 1.12%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 5        | 1.12%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 4        | 0.89%   |
| TP-Link 802.11ac WLAN Adapter                                  | 4        | 0.89%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 4        | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4        | 0.89%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 4        | 0.89%   |
| Intel Wireless 8265 / 8275                                     | 4        | 0.89%   |
| Intel Wireless 8260                                            | 4        | 0.89%   |
| Intel Wireless 7265                                            | 4        | 0.89%   |
| Intel Wireless 3165                                            | 4        | 0.89%   |
| ASUS 802.11ac NIC                                              | 4        | 0.89%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 3        | 0.67%   |
| TP-Link TL-WN722N v2                                           | 3        | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3        | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3        | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3        | 0.67%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 3        | 0.67%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 3        | 0.67%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 3        | 0.67%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 3        | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3        | 0.67%   |
| Ralink RT5370 Wireless Adapter                                 | 3        | 0.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3        | 0.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3        | 0.67%   |
| Intel Centrino Advanced-N 6235                                 | 3        | 0.67%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                         | 3        | 0.67%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3        | 0.67%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 2        | 0.45%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 2        | 0.45%   |
| Ralink RT2870 Wireless Adapter                                 | 2        | 0.45%   |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter              | 2        | 0.45%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                           | 2        | 0.45%   |
| Ralink RT3092 Wireless 802.11n 2T/2R PCIe                      | 2        | 0.45%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2        | 0.45%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 2        | 0.45%   |
| Qualcomm Atheros AR9271 802.11n                                | 2        | 0.45%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2        | 0.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2        | 0.45%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Realtek Semiconductor                  | 519      | 55.45%  |
| Intel                                  | 305      | 32.59%  |
| Qualcomm Atheros                       | 28       | 2.99%   |
| Nvidia                                 | 18       | 1.92%   |
| Broadcom                               | 17       | 1.82%   |
| Marvell Technology Group               | 11       | 1.18%   |
| Xiaomi                                 | 6        | 0.64%   |
| Aquantia                               | 6        | 0.64%   |
| Samsung Electronics                    | 5        | 0.53%   |
| Broadcom Limited                       | 3        | 0.32%   |
| Sony Ericsson Mobile Communications AB | 2        | 0.21%   |
| Mellanox Technologies                  | 2        | 0.21%   |
| Huawei Technologies                    | 2        | 0.21%   |
| ASIX Electronics                       | 2        | 0.21%   |
| VIA Technologies                       | 1        | 0.11%   |
| Sundance Technology Inc / IC Plus      | 1        | 0.11%   |
| Qualcomm                               | 1        | 0.11%   |
| LG Electronics                         | 1        | 0.11%   |
| JMicron Technology                     | 1        | 0.11%   |
| ICS Advent                             | 1        | 0.11%   |
| DisplayLink                            | 1        | 0.11%   |
| Chelsio Communications                 | 1        | 0.11%   |
| Apple                                  | 1        | 0.11%   |
| American Megatrends                    | 1        | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 426      | 44.01%  |
| Realtek RTL8125 2.5GbE Controller                                 | 54       | 5.58%   |
| Intel I211 Gigabit Network Connection                             | 40       | 4.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 38       | 3.93%   |
| Intel Ethernet Connection (2) I219-V                              | 31       | 3.2%    |
| Intel Ethernet Controller I225-V                                  | 26       | 2.69%   |
| Intel Ethernet Connection I217-LM                                 | 25       | 2.58%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22       | 2.27%   |
| Intel Ethernet Connection (7) I219-V                              | 14       | 1.45%   |
| Intel 82579V Gigabit Network Connection                           | 14       | 1.45%   |
| Intel Ethernet Connection I217-V                                  | 13       | 1.34%   |
| Intel Ethernet Connection (2) I218-V                              | 12       | 1.24%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 12       | 1.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11       | 1.14%   |
| Intel 82574L Gigabit Network Connection                           | 11       | 1.14%   |
| Intel Ethernet Connection (2) I219-LM                             | 10       | 1.03%   |
| Nvidia MCP61 Ethernet                                             | 8        | 0.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 0.72%   |
| Intel I210 Gigabit Network Connection                             | 7        | 0.72%   |
| Intel Ethernet Controller X550                                    | 7        | 0.72%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 6        | 0.62%   |
| Intel Ethernet Connection (14) I219-V                             | 6        | 0.62%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5        | 0.52%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 5        | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5        | 0.52%   |
| Intel Ethernet Connection (5) I219-LM                             | 5        | 0.52%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5        | 0.52%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4        | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4        | 0.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4        | 0.41%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 4        | 0.41%   |
| Intel Ethernet Connection I218-V                                  | 4        | 0.41%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4        | 0.41%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 4        | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.31%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.31%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3        | 0.31%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3        | 0.31%   |
| Nvidia MCP77 Ethernet                                             | 3        | 0.31%   |
| Nvidia MCP73 Ethernet                                             | 3        | 0.31%   |
| Intel Ethernet Connection (2) I218-LM                             | 3        | 0.31%   |
| Intel Ethernet Connection (17) I219-V                             | 3        | 0.31%   |
| Intel 82583V Gigabit Network Connection                           | 3        | 0.31%   |
| Sony Ericsson Mobile AB G3311                                     | 2        | 0.21%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2        | 0.21%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 2        | 0.21%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2        | 0.21%   |
| Nvidia MCP79 Ethernet                                             | 2        | 0.21%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2        | 0.21%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 2        | 0.21%   |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.21%   |
| Intel Ethernet Connection (6) I219-LM                             | 2        | 0.21%   |
| Intel Ethernet Connection (14) I219-LM                            | 2        | 0.21%   |
| Intel Ethernet Connection (13) I219-V                             | 2        | 0.21%   |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.21%   |
| Intel Ethernet Connection (11) I219-LM                            | 2        | 0.21%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.21%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.21%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2        | 0.21%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2        | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 865      | 67.16%  |
| WiFi     | 413      | 32.07%  |
| Modem    | 7        | 0.54%   |
| Unknown  | 3        | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 683      | 75.97%  |
| WiFi     | 216      | 24.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 533      | 60.98%  |
| 2     | 279      | 31.92%  |
| 3     | 49       | 5.61%   |
| 4     | 6        | 0.69%   |
| 0     | 6        | 0.69%   |
| 8     | 1        | 0.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 591      | 67.47%  |
| Yes  | 285      | 32.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 131      | 42.95%  |
| Cambridge Silicon Radio         | 61       | 20%     |
| Realtek Semiconductor           | 20       | 6.56%   |
| Broadcom                        | 19       | 6.23%   |
| ASUSTek Computer                | 17       | 5.57%   |
| Qualcomm Atheros Communications | 15       | 4.92%   |
| IMC Networks                    | 7        | 2.3%    |
| MediaTek                        | 6        | 1.97%   |
| Apple                           | 6        | 1.97%   |
| Lite-On Technology              | 5        | 1.64%   |
| Logitech                        | 3        | 0.98%   |
| Dell                            | 3        | 0.98%   |
| Belkin Components               | 3        | 0.98%   |
| TP-Link                         | 2        | 0.66%   |
| Edimax Technology               | 2        | 0.66%   |
| TRENDnet                        | 1        | 0.33%   |
| Mobile Action Technology        | 1        | 0.33%   |
| Micro Star International        | 1        | 0.33%   |
| Integrated System Solution      | 1        | 0.33%   |
| Unknown                         | 1        | 0.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 61       | 20%     |
| Intel AX200 Bluetooth                                 | 38       | 12.46%  |
| Intel Bluetooth wireless interface                    | 21       | 6.89%   |
| Intel AX201 Bluetooth                                 | 20       | 6.56%   |
| Intel AX210 Bluetooth                                 | 19       | 6.23%   |
| Realtek Bluetooth Radio                               | 16       | 5.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 12       | 3.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 11       | 3.61%   |
| Intel Wireless-AC 3168 Bluetooth                      | 9        | 2.95%   |
| Qualcomm Atheros  Bluetooth Device                    | 7        | 2.3%    |
| MediaTek Wireless_Device                              | 6        | 1.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 5        | 1.64%   |
| IMC Networks Bluetooth Radio                          | 5        | 1.64%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 5        | 1.64%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 4        | 1.31%   |
| Intel Bluetooth Device                                | 4        | 1.31%   |
| ASUS ASUS USB-BT500                                   | 4        | 1.31%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 4        | 1.31%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 3        | 0.98%   |
| Logitech BT Mini-Receiver (HCI mode)                  | 3        | 0.98%   |
| Lite-On Bluetooth Device                              | 3        | 0.98%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 3        | 0.98%   |
| ASUS Bluetooth Radio                                  | 3        | 0.98%   |
| TP-Link UB500 Adapter                                 | 2        | 0.66%   |
| Realtek  Bluetooth 4.2 Adapter                        | 2        | 0.66%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 2        | 0.66%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 2        | 0.66%   |
| Edimax Bluetooth Adapter                              | 2        | 0.66%   |
| Dell Broadcom BCM20702A0 Bluetooth                    | 2        | 0.66%   |
| Broadcom HP Bluethunder                               | 2        | 0.66%   |
| Apple Bluetooth USB Host Controller                   | 2        | 0.66%   |
| TRENDnet TBW-108UB USB Adapter                        | 1        | 0.33%   |
| Realtek RTL8821A Bluetooth                            | 1        | 0.33%   |
| Realtek RTL8723B Bluetooth                            | 1        | 0.33%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1        | 0.33%   |
| Mobile Action MA-700 Bluetooth Adapter                | 1        | 0.33%   |
| Micro Star International Bluetooth Device             | 1        | 0.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 1        | 0.33%   |
| Lite-On Atheros AR3012 Bluetooth                      | 1        | 0.33%   |
| Integrated System Solution Bluetooth Device           | 1        | 0.33%   |
| IMC Networks Wireless_Device                          | 1        | 0.33%   |
| IMC Networks Bluetooth Device                         | 1        | 0.33%   |
| Dell BCM20702A0 Bluetooth Module                      | 1        | 0.33%   |
| Broadcom HP Bluetooth Module                          | 1        | 0.33%   |
| Broadcom Bluetooth 2.0+eDR dongle                     | 1        | 0.33%   |
| Broadcom BCM43142A0 Bluetooth Device                  | 1        | 0.33%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1        | 0.33%   |
| Broadcom BCM2035 Bluetooth dongle                     | 1        | 0.33%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 0.33%   |
| Belkin Components F8T012 Bluetooth Adapter            | 1        | 0.33%   |
| Belkin Components F8T001v2 Bluetooth                  | 1        | 0.33%   |
| ASUS Qualcomm Bluetooth 4.1                           | 1        | 0.33%   |
| ASUS Bluetooth Device                                 | 1        | 0.33%   |
| Unknown                                               | 1        | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 573      | 40.47%  |
| AMD                                          | 358      | 25.28%  |
| Nvidia                                       | 336      | 23.73%  |
| C-Media Electronics                          | 29       | 2.05%   |
| Creative Labs                                | 14       | 0.99%   |
| Logitech                                     | 12       | 0.85%   |
| SteelSeries ApS                              | 6        | 0.42%   |
| Texas Instruments                            | 5        | 0.35%   |
| Micro Star International                     | 5        | 0.35%   |
| GN Netcom                                    | 5        | 0.35%   |
| ASUSTek Computer                             | 5        | 0.35%   |
| Zoran Co. Personal Media Division (Nogatech) | 4        | 0.28%   |
| Kingston Technology                          | 4        | 0.28%   |
| Generalplus Technology                       | 4        | 0.28%   |
| Creative Technology                          | 4        | 0.28%   |
| Corsair                                      | 4        | 0.28%   |
| Razer USA                                    | 3        | 0.21%   |
| JMTek                                        | 3        | 0.21%   |
| Astro Gaming                                 | 3        | 0.21%   |
| Syntek                                       | 2        | 0.14%   |
| Medeli Electronics                           | 2        | 0.14%   |
| Giga-Byte Technology                         | 2        | 0.14%   |
| Focusrite-Novation                           | 2        | 0.14%   |
| Elite Silicon                                | 2        | 0.14%   |
| XMOS                                         | 1        | 0.07%   |
| Xilinx                                       | 1        | 0.07%   |
| Turtle Beach                                 | 1        | 0.07%   |
| Sennheiser Communications                    | 1        | 0.07%   |
| RODE Microphones                             | 1        | 0.07%   |
| PreSonus Audio Electronics                   | 1        | 0.07%   |
| Plantronics                                  | 1        | 0.07%   |
| Orbbec 3D Technology International           | 1        | 0.07%   |
| Native Instruments                           | 1        | 0.07%   |
| Nam Tai E&E Products                         | 1        | 0.07%   |
| Microsoft                                    | 1        | 0.07%   |
| M-Audio                                      | 1        | 0.07%   |
| KORG                                         | 1        | 0.07%   |
| Huawei Technologies                          | 1        | 0.07%   |
| Fry's Electronics                            | 1        | 0.07%   |
| Ensoniq                                      | 1        | 0.07%   |
| Elgato Systems                               | 1        | 0.07%   |
| DigiTech                                     | 1        | 0.07%   |
| Dell                                         | 1        | 0.07%   |
| Cooler Master                                | 1        | 0.07%   |
| Cirrus Logic                                 | 1        | 0.07%   |
| Bose                                         | 1        | 0.07%   |
| Blue Microphones                             | 1        | 0.07%   |
| AVer Information                             | 1        | 0.07%   |
| Audient                                      | 1        | 0.07%   |
| Arturia                                      | 1        | 0.07%   |
| Apple                                        | 1        | 0.07%   |
| AOKEO                                        | 1        | 0.07%   |
| Unknown                                      | 1        | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 94       | 5.73%   |
| AMD Starship/Matisse HD Audio Controller                                          | 87       | 5.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 72       | 4.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 69       | 4.21%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 59       | 3.6%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 51       | 3.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 50       | 3.05%   |
| Intel 200 Series PCH HD Audio                                                     | 35       | 2.13%   |
| AMD FCH Azalia Controller                                                         | 35       | 2.13%   |
| AMD Family 17h/19h HD Audio Controller                                            | 35       | 2.13%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 33       | 2.01%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 29       | 1.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 28       | 1.71%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 28       | 1.71%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 25       | 1.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 24       | 1.46%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 24       | 1.46%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 22       | 1.34%   |
| Intel Cannon Lake PCH cAVS                                                        | 22       | 1.34%   |
| Intel Alder Lake-S HD Audio Controller                                            | 22       | 1.34%   |
| Nvidia GP104 High Definition Audio Controller                                     | 21       | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                                     | 18       | 1.1%    |
| Intel C610/X99 series chipset HD Audio Controller                                 | 18       | 1.1%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 18       | 1.1%    |
| Nvidia GA102 High Definition Audio Controller                                     | 17       | 1.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 17       | 1.04%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 16       | 0.98%   |
| AMD Navi 10 HDMI Audio                                                            | 16       | 0.98%   |
| AMD Kaveri HDMI/DP Audio Controller                                               | 16       | 0.98%   |
| Nvidia TU116 High Definition Audio Controller                                     | 15       | 0.91%   |
| Nvidia High Definition Audio Controller                                           | 15       | 0.91%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 15       | 0.91%   |
| Intel Tiger Lake-H HD Audio Controller                                            | 14       | 0.85%   |
| Intel Audio device                                                                | 14       | 0.85%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 14       | 0.85%   |
| Nvidia GP106 High Definition Audio Controller                                     | 13       | 0.79%   |
| Nvidia GA104 High Definition Audio Controller                                     | 13       | 0.79%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 13       | 0.79%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 13       | 0.79%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 13       | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                                | 12       | 0.73%   |
| Nvidia TU104 HD Audio Controller                                                  | 11       | 0.67%   |
| Nvidia GP108 High Definition Audio Controller                                     | 11       | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 11       | 0.67%   |
| Nvidia GK104 HDMI Audio Controller                                                | 11       | 0.67%   |
| Nvidia GF119 HDMI Audio Controller                                                | 11       | 0.67%   |
| Nvidia GA106 High Definition Audio Controller                                     | 11       | 0.67%   |
| Nvidia TU106 High Definition Audio Controller                                     | 10       | 0.61%   |
| Nvidia GM206 High Definition Audio Controller                                     | 10       | 0.61%   |
| Nvidia GM204 High Definition Audio Controller                                     | 10       | 0.61%   |
| Intel Comet Lake PCH-V cAVS                                                       | 10       | 0.61%   |
| Intel C600/X79 series chipset High Definition Audio Controller                    | 10       | 0.61%   |
| Nvidia GK106 HDMI Audio Controller                                                | 9        | 0.55%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                    | 9        | 0.55%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                  | 9        | 0.55%   |
| Nvidia MCP61 High Definition Audio                                                | 8        | 0.49%   |
| Intel Comet Lake PCH cAVS                                                         | 8        | 0.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                      | 8        | 0.49%   |
| AMD Trinity HDMI Audio Controller                                                 | 8        | 0.49%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                    | 8        | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 77       | 17.74%  |
| Corsair             | 69       | 15.9%   |
| Samsung Electronics | 45       | 10.37%  |
| Unknown             | 43       | 9.91%   |
| SK hynix            | 42       | 9.68%   |
| G.Skill             | 31       | 7.14%   |
| Crucial             | 30       | 6.91%   |
| Micron Technology   | 29       | 6.68%   |
| A-DATA Technology   | 10       | 2.3%    |
| Team                | 8        | 1.84%   |
| Patriot             | 6        | 1.38%   |
| Unknown             | 6        | 1.38%   |
| Ramaxel Technology  | 5        | 1.15%   |
| KETECH              | 4        | 0.92%   |
| PNY                 | 3        | 0.69%   |
| GOODRAM             | 3        | 0.69%   |
| Unknown (ABCD)      | 2        | 0.46%   |
| Transcend           | 2        | 0.46%   |
| Nanya Technology    | 2        | 0.46%   |
| Kingmax             | 2        | 0.46%   |
| Hewlett-Packard     | 2        | 0.46%   |
| GeIL                | 2        | 0.46%   |
| ZION                | 1        | 0.23%   |
| V-Color             | 1        | 0.23%   |
| Unifosa             | 1        | 0.23%   |
| Timetec             | 1        | 0.23%   |
| Qumo                | 1        | 0.23%   |
| Kllisre             | 1        | 0.23%   |
| Exceleram           | 1        | 0.23%   |
| Essencore Limited   | 1        | 0.23%   |
| Elpida              | 1        | 0.23%   |
| Avant               | 1        | 0.23%   |
| Apacer              | 1        | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Desktops | Percent |
|--------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s        | 9        | 1.94%   |
| Unknown                                                      | 6        | 1.29%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 5        | 1.08%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                         | 5        | 1.08%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s          | 5        | 1.08%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3200MT/s       | 5        | 1.08%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 4        | 0.86%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s         | 4        | 0.86%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s            | 4        | 0.86%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s         | 4        | 0.86%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3000MT/s        | 4        | 0.86%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                         | 3        | 0.65%   |
| Samsung RAM M378B5273CH0-CK0 4096MB DIMM DDR3 2000MT/s       | 3        | 0.65%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s          | 3        | 0.65%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s          | 3        | 0.65%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s        | 3        | 0.65%   |
| KETECH RAM Module 8GB DIMM DDR3 1600MT/s                     | 3        | 0.65%   |
| Crucial RAM CT102464BD160B.M16 8GB DIMM DDR3 1600MT/s        | 3        | 0.65%   |
| Corsair RAM CMZ8GX3M2A1600C9 4096MB DIMM DDR3 1600MT/s       | 3        | 0.65%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3600MT/s       | 3        | 0.65%   |
| Corsair RAM CMK16GX4M2A2133C13 8GB DIMM DDR4 3000MT/s        | 3        | 0.65%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 2        | 0.43%   |
| Unknown RAM Module 2GB DIMM 400MT/s                          | 2        | 0.43%   |
| Unknown RAM 1600 CL9 Series 8192MB DIMM DDR3 1066MT/s        | 2        | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 1GB DIMM DDR3 2400MT/s | 2        | 0.43%   |
| Team RAM TEAMGROUP-UD3-1600 8GB DIMM DDR3 1600MT/s           | 2        | 0.43%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s                   | 2        | 0.43%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s         | 2        | 0.43%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s         | 2        | 0.43%   |
| SK hynix RAM DMT451E6AFR8C-PB 4GB DIMM DDR3 1600MT/s         | 2        | 0.43%   |
| Samsung RAM Module 8GB DIMM DDR4 2400MT/s                    | 2        | 0.43%   |
| Samsung RAM Module 2GB DIMM DDR3 1333MT/s                    | 2        | 0.43%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s        | 2        | 0.43%   |
| Samsung RAM M391A2K43BB1-CTD 16384MB DIMM DDR4 3600MT/s      | 2        | 0.43%   |
| Samsung RAM M378B5673EH1-CH9 2GB DIMM DDR3 1333MT/s          | 2        | 0.43%   |
| Ramaxel RAM RMR1870EC58E9F1333 4GB DIMM DDR3 1333MT/s        | 2        | 0.43%   |
| Micron RAM 8JTF51264AZ-1G6E1 4096MB DIMM DDR3 1600MT/s       | 2        | 0.43%   |
| Micron RAM 8JTF25664AZ-1G6M1 2GB DIMM DDR3 1600MT/s          | 2        | 0.43%   |
| Micron RAM 8ATF2G64AZ-3G2E1 16GB DIMM DDR4 3200MT/s          | 2        | 0.43%   |
| Micron RAM 36ASF2G72PZ-2G1A2 16GB DIMM DDR4 2133MT/s         | 2        | 0.43%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s       | 2        | 0.43%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s            | 2        | 0.43%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s          | 2        | 0.43%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s          | 2        | 0.43%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s          | 2        | 0.43%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s        | 2        | 0.43%   |
| Kingston RAM K531R8-HYA 4GB DIMM DDR3 1600MT/s               | 2        | 0.43%   |
| Kingston RAM 99U5471-052.A00LF 8GB DIMM DDR3 1333MT/s        | 2        | 0.43%   |
| Kingston RAM 99U5471-031.A00LF 8GB DIMM DDR3 1333MT/s        | 2        | 0.43%   |
| KETECH RAM Module 2GB DIMM DDR3 1600MT/s                     | 2        | 0.43%   |
| Goodram RAM GR1333D364L9/4G 4GB DIMM DDR3 1600MT/s           | 2        | 0.43%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2400MT/s        | 2        | 0.43%   |
| Crucial RAM BL8G24C16U4B.8FB 8GB DIMM DDR4 2400MT/s          | 2        | 0.43%   |
| Corsair RAM CMY8GX3M2A1866C9 4GB DIMM DDR3 1867MT/s          | 2        | 0.43%   |
| Corsair RAM CMX8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s          | 2        | 0.43%   |
| Corsair RAM CMV4GX3M1A1333C9 4096MB DIMM DDR3 1600MT/s       | 2        | 0.43%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s       | 2        | 0.43%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s        | 2        | 0.43%   |
| ZION RAM ZION4GBDDR3PC1600 4GB DIMM DDR3 1400MT/s            | 1        | 0.22%   |
| V-Color RAM TD48G26S819K-VC 8GB DIMM DDR4 2667MT/s           | 1        | 0.22%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 189      | 50.4%   |
| DDR3    | 128      | 34.13%  |
| Unknown | 22       | 5.87%   |
| SDRAM   | 15       | 4%      |
| DDR2    | 12       | 3.2%    |
| LPDDR4  | 5        | 1.33%   |
| DRAM    | 2        | 0.53%   |
| DDR     | 2        | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 338      | 92.6%   |
| SODIMM       | 23       | 6.3%    |
| Row Of Chips | 2        | 0.55%   |
| RIMM         | 1        | 0.27%   |
| FB-DIMM      | 1        | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Desktops | Percent |
|--------|----------|---------|
| 8192   | 149      | 36.88%  |
| 4096   | 108      | 26.73%  |
| 16384  | 77       | 19.06%  |
| 2048   | 38       | 9.41%   |
| 32768  | 22       | 5.45%   |
| 1024   | 7        | 1.73%   |
| 65536  | 2        | 0.5%    |
| 131072 | 1        | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 80       | 19.23%  |
| 3200    | 50       | 12.02%  |
| 1333    | 46       | 11.06%  |
| 3600    | 43       | 10.34%  |
| 2400    | 29       | 6.97%   |
| 2667    | 24       | 5.77%   |
| 2133    | 20       | 4.81%   |
| 1867    | 11       | 2.64%   |
| 3466    | 10       | 2.4%    |
| 3000    | 9        | 2.16%   |
| 800     | 9        | 2.16%   |
| 2666    | 8        | 1.92%   |
| 2933    | 7        | 1.68%   |
| 1800    | 7        | 1.68%   |
| 667     | 7        | 1.68%   |
| 1066    | 5        | 1.2%    |
| Unknown | 5        | 1.2%    |
| 3400    | 4        | 0.96%   |
| 1067    | 4        | 0.96%   |
| 4800    | 3        | 0.72%   |
| 4000    | 3        | 0.72%   |
| 2800    | 3        | 0.72%   |
| 2000    | 3        | 0.72%   |
| 5600    | 2        | 0.48%   |
| 3733    | 2        | 0.48%   |
| 3467    | 2        | 0.48%   |
| 2733    | 2        | 0.48%   |
| 1866    | 2        | 0.48%   |
| 1400    | 2        | 0.48%   |
| 400     | 2        | 0.48%   |
| 4600    | 1        | 0.24%   |
| 4333    | 1        | 0.24%   |
| 4040    | 1        | 0.24%   |
| 3666    | 1        | 0.24%   |
| 3266    | 1        | 0.24%   |
| 3066    | 1        | 0.24%   |
| 2934    | 1        | 0.24%   |
| 2200    | 1        | 0.24%   |
| 2048    | 1        | 0.24%   |
| 1334    | 1        | 0.24%   |
| 533     | 1        | 0.24%   |
| 333     | 1        | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 14       | 37.84%  |
| Samsung Electronics   | 7        | 18.92%  |
| Brother Industries    | 7        | 18.92%  |
| Canon                 | 5        | 13.51%  |
| Seiko Epson           | 2        | 5.41%   |
| Prolific Technology   | 1        | 2.7%    |
| Lexmark International | 1        | 2.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung Composite Device             | 3        | 7.89%   |
| HP DeskJet 1110 series               | 2        | 5.26%   |
| Seiko Epson L220 Series              | 1        | 2.63%   |
| Seiko Epson ET-2720 Series           | 1        | 2.63%   |
| Samsung SCX-4600 Series              | 1        | 2.63%   |
| Samsung ML-216x Series Laser Printer | 1        | 2.63%   |
| Samsung M267x 287x Series            | 1        | 2.63%   |
| Samsung M2070 Series                 | 1        | 2.63%   |
| Prolific PL2305 Parallel Port        | 1        | 2.63%   |
| Lexmark International B2442dw        | 1        | 2.63%   |
| HP Smart Tank 7000 series            | 1        | 2.63%   |
| HP Officejet Pro 8630                | 1        | 2.63%   |
| HP OfficeJet 8700                    | 1        | 2.63%   |
| HP OfficeJet 5600 (USBHUB)           | 1        | 2.63%   |
| HP OfficeJet 5500 series             | 1        | 2.63%   |
| HP Officejet 4500 G510n-z            | 1        | 2.63%   |
| HP OfficeJet 3830 series             | 1        | 2.63%   |
| HP LaserJet Professional P1102w      | 1        | 2.63%   |
| HP LaserJet P1005                    | 1        | 2.63%   |
| HP LaserJet 1320                     | 1        | 2.63%   |
| HP ENVY 4500 series                  | 1        | 2.63%   |
| HP DeskJet 2130 series               | 1        | 2.63%   |
| Canon TS3100 series                  | 1        | 2.63%   |
| Canon PIXMA iP3000x Printer          | 1        | 2.63%   |
| Canon MF632C/634C                    | 1        | 2.63%   |
| Canon MF4410                         | 1        | 2.63%   |
| Canon MF4320-4350                    | 1        | 2.63%   |
| Canon iR2004/2204 UFRII LT           | 1        | 2.63%   |
| Brother MFC-L2700DW                  | 1        | 2.63%   |
| Brother HL-5340 series               | 1        | 2.63%   |
| Brother HL-52x0 series               | 1        | 2.63%   |
| Brother HL-2240 series               | 1        | 2.63%   |
| Brother HL-2030 Laser Printer        | 1        | 2.63%   |
| Brother HL-1440 Laser Printer        | 1        | 2.63%   |
| Brother HL-1200 series               | 1        | 2.63%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Desktops | Percent |
|-------------|----------|---------|
| Canon       | 5        | 71.43%  |
| Seiko Epson | 2        | 28.57%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                              | Desktops | Percent |
|----------------------------------------------------|----------|---------|
| Seiko Epson GT-X770 [Perfection V500]              | 1        | 14.29%  |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO] | 1        | 14.29%  |
| Canon CanoScan LIDE 25                             | 1        | 14.29%  |
| Canon CanoScan LiDE 220                            | 1        | 14.29%  |
| Canon CanoScan LiDE 200                            | 1        | 14.29%  |
| Canon CanoScan LiDE 110                            | 1        | 14.29%  |
| Canon CanoScan LiDE 100                            | 1        | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 62       | 37.35%  |
| Microdia                               | 11       | 6.63%   |
| Sunplus Innovation Technology          | 10       | 6.02%   |
| Microsoft                              | 10       | 6.02%   |
| Apple                                  | 7        | 4.22%   |
| Generalplus Technology                 | 6        | 3.61%   |
| Z-Star Microelectronics                | 5        | 3.01%   |
| Razer USA                              | 4        | 2.41%   |
| Chicony Electronics                    | 4        | 2.41%   |
| ARC International                      | 4        | 2.41%   |
| Samsung Electronics                    | 3        | 1.81%   |
| Realtek Semiconductor                  | 3        | 1.81%   |
| Creative Technology                    | 3        | 1.81%   |
| webcam                                 | 2        | 1.2%    |
| Trust                                  | 2        | 1.2%    |
| Pixart Imaging                         | 2        | 1.2%    |
| MacroSilicon                           | 2        | 1.2%    |
| KYE Systems (Mouse Systems)            | 2        | 1.2%    |
| Hewlett-Packard                        | 2        | 1.2%    |
| Alcor Micro                            | 2        | 1.2%    |
| YGTek                                  | 1        | 0.6%    |
| WaveRider Communications               | 1        | 0.6%    |
| Tobii Technology AB                    | 1        | 0.6%    |
| Sony                                   | 1        | 0.6%    |
| Sonix Technology                       | 1        | 0.6%    |
| Panasonic (Matsushita)                 | 1        | 0.6%    |
| Magic Control Technology               | 1        | 0.6%    |
| Jieli Technology                       | 1        | 0.6%    |
| Huawei Technologies                    | 1        | 0.6%    |
| HD USB Camera                          | 1        | 0.6%    |
| Guillemot                              | 1        | 0.6%    |
| Google                                 | 1        | 0.6%    |
| Genesys Logic                          | 1        | 0.6%    |
| GEMBIRD                                | 1        | 0.6%    |
| eMeet                                  | 1        | 0.6%    |
| Dynex                                  | 1        | 0.6%    |
| Cubeternet                             | 1        | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) | 1        | 0.6%    |
| AVer Information                       | 1        | 0.6%    |
| Arkmicro Technologies                  | 1        | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                         | 16       | 9.64%   |
| Logitech Webcam C270                                | 11       | 6.63%   |
| Logitech C922 Pro Stream Webcam                     | 9        | 5.42%   |
| Generalplus GENERAL WEBCAM                          | 6        | 3.61%   |
| Apple iPhone 5/5C/5S/6/SE                           | 6        | 3.61%   |
| Sunplus Depstech webcam MIC                         | 5        | 3.01%   |
| Microdia Webcam Vitade AF                           | 4        | 2.41%   |
| Logitech HD Webcam C615                             | 4        | 2.41%   |
| Logitech C920 PRO HD Webcam                         | 4        | 2.41%   |
| ARC International Camera                            | 4        | 2.41%   |
| Samsung Galaxy series, misc. (MTP mode)             | 3        | 1.81%   |
| Razer USA Gaming Webcam [Kiyo]                      | 3        | 1.81%   |
| Microsoft LifeCam HD-3000                           | 3        | 1.81%   |
| Microdia USB 2.0 Camera                             | 3        | 1.81%   |
| Logitech HD Webcam C525                             | 3        | 1.81%   |
| Z-Star Venus USB2.0 Camera                          | 2        | 1.2%    |
| webcam webcam                                       | 2        | 1.2%    |
| Sunplus Full HD webcam                              | 2        | 1.2%    |
| Pixart Imaging GE 1.3 MP MiniCam Pro                | 2        | 1.2%    |
| Microsoft LifeCam VX-500 [1357]                     | 2        | 1.2%    |
| Microsoft LifeCam Cinema                            | 2        | 1.2%    |
| Microdia Integrated Camera                          | 2        | 1.2%    |
| MacroSilicon USB Video                              | 2        | 1.2%    |
| Logitech Webcam C170                                | 2        | 1.2%    |
| KYE Systems (Mouse Systems) FaceCam 1000X           | 2        | 1.2%    |
| Chicony HP High Definition 1MP Webcam               | 2        | 1.2%    |
| Alcor Micro USB 2.0 PC Camera                       | 2        | 1.2%    |
| Z-Star Lenovo USB 2.0 UVC Camera                    | 1        | 0.6%    |
| Z-Star Integrated Camera                            | 1        | 0.6%    |
| Z-Star A4 TECH USB2.0 PC Camera E                   | 1        | 0.6%    |
| YGTek Webcam                                        | 1        | 0.6%    |
| WaveRider USB 2.0 Camera                            | 1        | 0.6%    |
| Trust USB Camera                                    | 1        | 0.6%    |
| Trust Full HD Webcam                                | 1        | 0.6%    |
| Tobii AB EyeChip                                    | 1        | 0.6%    |
| Sunplus Webcam                                      | 1        | 0.6%    |
| Sunplus USB2.0 Camera                               | 1        | 0.6%    |
| Sunplus Canyon CNS-CWC5 Webcam                      | 1        | 0.6%    |
| Sony CEVCECM                                        | 1        | 0.6%    |
| Sonix HDF Webcam USB                                | 1        | 0.6%    |
| Realtek NexiGo N660P FHD Webcam                     | 1        | 0.6%    |
| Realtek Integrated_Webcam_FHD                       | 1        | 0.6%    |
| Realtek FULL HD 1080P Webcam                        | 1        | 0.6%    |
| Razer USA Razer Ripsaw HD - Game Capture Card       | 1        | 0.6%    |
| Panasonic (Matsushita) NV-GS11/230/250 (DV mode)    | 1        | 0.6%    |
| Microsoft Xbox NUI Camera                           | 1        | 0.6%    |
| Microsoft MicrosoftÂ LifeCam HD-6000 for Notebooks | 1        | 0.6%    |
| Microsoft LifeCam Studio                            | 1        | 0.6%    |
| Microdia Sonix USB 2.0 Camera                       | 1        | 0.6%    |
| Microdia Camera                                     | 1        | 0.6%    |
| Magic Control j5 WebCam JVCU100                     | 1        | 0.6%    |
| Logitech Webcam C930e                               | 1        | 0.6%    |
| Logitech Webcam C925e                               | 1        | 0.6%    |
| Logitech Webcam C600                                | 1        | 0.6%    |
| Logitech Webcam C210                                | 1        | 0.6%    |
| Logitech StreamCam                                  | 1        | 0.6%    |
| Logitech QuickCam Pro 9000                          | 1        | 0.6%    |
| Logitech QuickCam Express                           | 1        | 0.6%    |
| Logitech QuickCam E 3500                            | 1        | 0.6%    |
| Logitech Logi 4K Stream Edition                     | 1        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Elan Microelectronics | 1        | 50%     |
| Dell                  | 1        | 50%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Elan fingerprint sensor [FeinTech FPS00200]    | 1        | 50%     |
| Dell MS819 Wired Mouse With Fingerprint Reader | 1        | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 1        | 50%     |
| Gemalto (was Gemplus) | 1        | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1        | 50%     |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader | 1        | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 718      | 81.5%   |
| 1     | 141      | 16%     |
| 2     | 12       | 1.36%   |
| 3     | 8        | 0.91%   |
| 5     | 1        | 0.11%   |
| 4     | 1        | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 73       | 39.67%  |
| Net/wireless             | 44       | 23.91%  |
| Unassigned class         | 21       | 11.41%  |
| Sound                    | 12       | 6.52%   |
| Communication controller | 11       | 5.98%   |
| Bluetooth                | 6        | 3.26%   |
| Storage/raid             | 3        | 1.63%   |
| Multimedia controller    | 3        | 1.63%   |
| Net/ethernet             | 2        | 1.09%   |
| Chipcard                 | 2        | 1.09%   |
| Card reader              | 2        | 1.09%   |
| Camera                   | 2        | 1.09%   |
| Network                  | 1        | 0.54%   |
| Fingerprint reader       | 1        | 0.54%   |
| Dvb card                 | 1        | 0.54%   |

