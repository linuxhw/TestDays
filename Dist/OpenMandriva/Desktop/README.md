OpenMandriva - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva.

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

Total: 6744

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASRock        | G41M-VS3                    | [d592b19e9b](https://linux-hardware.org/?probe=d592b19e9b) | Jun 10, 2023 |
| HP            | 339A                        | [348ce53f71](https://linux-hardware.org/?probe=348ce53f71) | Jun 10, 2023 |
| Gigabyte      | GA-880GM-D2H                | [2e46385299](https://linux-hardware.org/?probe=2e46385299) | Jun 10, 2023 |
| Gigabyte      | B560M H                     | [fadb7a6aa8](https://linux-hardware.org/?probe=fadb7a6aa8) | Jun 10, 2023 |
| Dell          | 0D883F A06                  | [f0d5120461](https://linux-hardware.org/?probe=f0d5120461) | Jun 10, 2023 |
| Wistron       | ProLiant ML110 G5           | [eea1c44d94](https://linux-hardware.org/?probe=eea1c44d94) | Jun 10, 2023 |
| GuoGuang      | IC2M1028V-J                 | [d7c1b01b69](https://linux-hardware.org/?probe=d7c1b01b69) | Jun 10, 2023 |
| Acer          | Predator G3600              | [02a0cf3a71](https://linux-hardware.org/?probe=02a0cf3a71) | Jun 10, 2023 |
| MSI           | 970A-G46                    | [e4471b7a38](https://linux-hardware.org/?probe=e4471b7a38) | Jun 09, 2023 |
| ASUSTek       | P8H61-M LX2                 | [3fb94f0c4b](https://linux-hardware.org/?probe=3fb94f0c4b) | Jun 09, 2023 |
| MSI           | A520M-A PRO                 | [8a9223ce9f](https://linux-hardware.org/?probe=8a9223ce9f) | Jun 09, 2023 |
| HP            | 09E0h                       | [b6bb01441c](https://linux-hardware.org/?probe=b6bb01441c) | Jun 09, 2023 |
| ASRock        | Z690M-ITX/ax                | [f0bad84fca](https://linux-hardware.org/?probe=f0bad84fca) | Jun 08, 2023 |
| Gigabyte      | X570 UD                     | [98a10d2fd9](https://linux-hardware.org/?probe=98a10d2fd9) | Jun 08, 2023 |
| MSI           | X470 GAMING PLUS            | [eea4cea0e0](https://linux-hardware.org/?probe=eea4cea0e0) | Jun 08, 2023 |
| Biostar       | H610MH                      | [2cd4e157d4](https://linux-hardware.org/?probe=2cd4e157d4) | Jun 08, 2023 |
| GuoGuang      | IC2M1028V-J                 | [04527d6ad9](https://linux-hardware.org/?probe=04527d6ad9) | Jun 08, 2023 |
| AMI           | Cherry Trail CR             | [5816e6a1cf](https://linux-hardware.org/?probe=5816e6a1cf) | Jun 07, 2023 |
| HP            | 1905                        | [0617f4e698](https://linux-hardware.org/?probe=0617f4e698) | Jun 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | [369f5d3044](https://linux-hardware.org/?probe=369f5d3044) | Jun 07, 2023 |
| HP            | 8169                        | [45543e5040](https://linux-hardware.org/?probe=45543e5040) | Jun 07, 2023 |
| Kraftway      | KWH510                      | [3a5ccb373b](https://linux-hardware.org/?probe=3a5ccb373b) | Jun 07, 2023 |
| HP            | 2B34                        | [d0b5c9767f](https://linux-hardware.org/?probe=d0b5c9767f) | Jun 07, 2023 |
| ASRock        | Z790 Taichi Carrara         | [bdea2092aa](https://linux-hardware.org/?probe=bdea2092aa) | Jun 06, 2023 |
| HP            | 822A                        | [8cf8694f03](https://linux-hardware.org/?probe=8cf8694f03) | Jun 06, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [624a84a2fc](https://linux-hardware.org/?probe=624a84a2fc) | Jun 06, 2023 |
| Intel         | E5 V1.0                     | [077c08c2dc](https://linux-hardware.org/?probe=077c08c2dc) | Jun 06, 2023 |
| Acer          | EQ45LM                      | [73f7a3078f](https://linux-hardware.org/?probe=73f7a3078f) | Jun 06, 2023 |
| Acer          | WMCP78M                     | [a7a466de8a](https://linux-hardware.org/?probe=a7a466de8a) | Jun 06, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [1bd1a651bb](https://linux-hardware.org/?probe=1bd1a651bb) | Jun 05, 2023 |
| HP            | 8265                        | [7afc259b97](https://linux-hardware.org/?probe=7afc259b97) | Jun 05, 2023 |
| MSI           | H110M ECO                   | [4215fc5993](https://linux-hardware.org/?probe=4215fc5993) | Jun 05, 2023 |
| Gigabyte      | B550M DS3H                  | [4895fe7746](https://linux-hardware.org/?probe=4895fe7746) | Jun 05, 2023 |
| ASUSTek       | PRIME Z590-P                | [933aa24820](https://linux-hardware.org/?probe=933aa24820) | Jun 05, 2023 |
| AMD           | A88                         | [a7f64b7e4b](https://linux-hardware.org/?probe=a7f64b7e4b) | Jun 05, 2023 |
| ASRock        | 960GM-GS3 FX                | [72702690e5](https://linux-hardware.org/?probe=72702690e5) | Jun 05, 2023 |
| Intel         | DE3815TYKH H26998-402       | [d2f97c16e9](https://linux-hardware.org/?probe=d2f97c16e9) | Jun 05, 2023 |
| ASRock        | B150M Pro4                  | [0b59eacbd3](https://linux-hardware.org/?probe=0b59eacbd3) | Jun 05, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [d275c3c00b](https://linux-hardware.org/?probe=d275c3c00b) | Jun 05, 2023 |
| HP            | 1850                        | [bddc14be8b](https://linux-hardware.org/?probe=bddc14be8b) | Jun 05, 2023 |
| HP            | 8643 SMVB                   | [697cc43136](https://linux-hardware.org/?probe=697cc43136) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [3af6e03b1c](https://linux-hardware.org/?probe=3af6e03b1c) | Jun 04, 2023 |
| HP            | 1495                        | [0cbf6bee1f](https://linux-hardware.org/?probe=0cbf6bee1f) | Jun 04, 2023 |
| Acer          | Veriton X4630G V:1.0        | [5106e40f32](https://linux-hardware.org/?probe=5106e40f32) | Jun 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [70e5950511](https://linux-hardware.org/?probe=70e5950511) | Jun 04, 2023 |
| MSI           | Boston                      | [95b4d5183d](https://linux-hardware.org/?probe=95b4d5183d) | Jun 04, 2023 |
| Foxconn       | G41MD                       | [f988a585c9](https://linux-hardware.org/?probe=f988a585c9) | Jun 04, 2023 |
| ASUSTek       | Pro B550M-C                 | [094889a0e2](https://linux-hardware.org/?probe=094889a0e2) | Jun 03, 2023 |
| ECS           | G31T-M                      | [55d38b75c7](https://linux-hardware.org/?probe=55d38b75c7) | Jun 03, 2023 |
| ASUSTek       | PRIME A520M-A               | [7dac003c12](https://linux-hardware.org/?probe=7dac003c12) | Jun 03, 2023 |
| MSI           | H110M PRO-VH PLUS           | [79e14478a3](https://linux-hardware.org/?probe=79e14478a3) | Jun 03, 2023 |
| Positivo      | POS-PIG41BA                 | [f630c0b9cd](https://linux-hardware.org/?probe=f630c0b9cd) | Jun 03, 2023 |
| Dell          | 0GX832 A01                  | [19b718a96c](https://linux-hardware.org/?probe=19b718a96c) | Jun 02, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [70a097a219](https://linux-hardware.org/?probe=70a097a219) | Jun 02, 2023 |
| ASUSTek       | PRIME B550-PLUS             | [f22933cdb1](https://linux-hardware.org/?probe=f22933cdb1) | Jun 01, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [75c4e47bea](https://linux-hardware.org/?probe=75c4e47bea) | Jun 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [e242ec473b](https://linux-hardware.org/?probe=e242ec473b) | Jun 01, 2023 |
| Fujitsu Si... | D2740-A2 S26361-D2740-A2    | [165491db1f](https://linux-hardware.org/?probe=165491db1f) | Jun 01, 2023 |
| OEM           | Intel H81                   | [b62ec659fa](https://linux-hardware.org/?probe=b62ec659fa) | Jun 01, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | [d94ba8fb27](https://linux-hardware.org/?probe=d94ba8fb27) | Jun 01, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [417320253a](https://linux-hardware.org/?probe=417320253a) | May 31, 2023 |
| Foxconn       | 2ABF                        | [ca4691fd95](https://linux-hardware.org/?probe=ca4691fd95) | May 31, 2023 |
| ASUSTek       | P5G41T-M LX3                | [483bf9a882](https://linux-hardware.org/?probe=483bf9a882) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [eda1870d76](https://linux-hardware.org/?probe=eda1870d76) | May 31, 2023 |
| TPV-INVENT... | 2AC6 A01                    | [1ac394c97c](https://linux-hardware.org/?probe=1ac394c97c) | May 30, 2023 |
| ASRock        | H310CM-HG4                  | [9fa8d9d320](https://linux-hardware.org/?probe=9fa8d9d320) | May 30, 2023 |
| ASUSTek       | P5KPL-AM                    | [48359795cc](https://linux-hardware.org/?probe=48359795cc) | May 30, 2023 |
| HP            | 82F2 A01                    | [fb729f1358](https://linux-hardware.org/?probe=fb729f1358) | May 29, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [a46f523ea2](https://linux-hardware.org/?probe=a46f523ea2) | May 29, 2023 |
| MSI           | P67A-GD65                   | [fe5e3bcd7b](https://linux-hardware.org/?probe=fe5e3bcd7b) | May 29, 2023 |
| Gigabyte      | Z690 UD                     | [feab206ef4](https://linux-hardware.org/?probe=feab206ef4) | May 29, 2023 |
| ASRock        | X670E Taichi Carrara        | [7b001db11a](https://linux-hardware.org/?probe=7b001db11a) | May 29, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [528f7440b7](https://linux-hardware.org/?probe=528f7440b7) | May 29, 2023 |
| Gigabyte      | H61M-DS2 x.x                | [e58b7bfc92](https://linux-hardware.org/?probe=e58b7bfc92) | May 29, 2023 |
| ASUSTek       | H81M-C                      | [ece00aac41](https://linux-hardware.org/?probe=ece00aac41) | May 29, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | [1c87272ed8](https://linux-hardware.org/?probe=1c87272ed8) | May 29, 2023 |
| ASRock        | G41M-VS3                    | [4d002c31be](https://linux-hardware.org/?probe=4d002c31be) | May 28, 2023 |
| ASRock        | B450M Steel Legend          | [b8436530b0](https://linux-hardware.org/?probe=b8436530b0) | May 28, 2023 |
| Gateway       | DT55                        | [22d84550c6](https://linux-hardware.org/?probe=22d84550c6) | May 28, 2023 |
| Gigabyte      | GA-MA78LMT-S2               | [bf3b702d7a](https://linux-hardware.org/?probe=bf3b702d7a) | May 28, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [ad8e3ea3ea](https://linux-hardware.org/?probe=ad8e3ea3ea) | May 27, 2023 |
| ASRock        | A320M-HDV R4.0              | [3e43db6ab5](https://linux-hardware.org/?probe=3e43db6ab5) | May 27, 2023 |
| ASUSTek       | F2A85-V PRO                 | [f2181d0270](https://linux-hardware.org/?probe=f2181d0270) | May 27, 2023 |
| Dell          | 0TP412                      | [112fa3015f](https://linux-hardware.org/?probe=112fa3015f) | May 27, 2023 |
| Wistron       | ProLiant ML110 G6           | [bc1c76bb8f](https://linux-hardware.org/?probe=bc1c76bb8f) | May 27, 2023 |
| MSI           | B560M PRO-VDH               | [b0435ce0dc](https://linux-hardware.org/?probe=b0435ce0dc) | May 27, 2023 |
| Intel         | B75                         | [8dba7fa195](https://linux-hardware.org/?probe=8dba7fa195) | May 27, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [3900a03a2c](https://linux-hardware.org/?probe=3900a03a2c) | May 27, 2023 |
| MSI           | B450 TOMAHAWK               | [3e9709dc25](https://linux-hardware.org/?probe=3e9709dc25) | May 27, 2023 |
| Pegatron      | 2A94h                       | [b17003f11e](https://linux-hardware.org/?probe=b17003f11e) | May 27, 2023 |
| MSI           | B250M BAZOOKA               | [2bfe50d945](https://linux-hardware.org/?probe=2bfe50d945) | May 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [5977804b94](https://linux-hardware.org/?probe=5977804b94) | May 26, 2023 |
| Gigabyte      | B450M DS3H V2               | [c4af5a7969](https://linux-hardware.org/?probe=c4af5a7969) | May 26, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [5d54a10d85](https://linux-hardware.org/?probe=5d54a10d85) | May 26, 2023 |
| ASRock        | A320M-HDV R4.0              | [c897394a34](https://linux-hardware.org/?probe=c897394a34) | May 26, 2023 |
| Fujitsu Si... | D2464-A1 S26361-D2464-A1    | [313c8a3663](https://linux-hardware.org/?probe=313c8a3663) | May 26, 2023 |
| Acer          | EQ45LM                      | [a49c4c8438](https://linux-hardware.org/?probe=a49c4c8438) | May 26, 2023 |
| Acer          | Aspire M3910                | [f4dedc13f9](https://linux-hardware.org/?probe=f4dedc13f9) | May 25, 2023 |
| MSI           | Z590 PLUS                   | [1f531f4e58](https://linux-hardware.org/?probe=1f531f4e58) | May 25, 2023 |
| MSI           | A520M-A PRO                 | [6f1a19d503](https://linux-hardware.org/?probe=6f1a19d503) | May 25, 2023 |
| ASRock        | B550M-HDV                   | [5311e723a0](https://linux-hardware.org/?probe=5311e723a0) | May 25, 2023 |
| ASUSTek       | P8B75-V                     | [cbcfc55949](https://linux-hardware.org/?probe=cbcfc55949) | May 25, 2023 |
| Dell          | 0XJ8C4 A00                  | [b6b7396e06](https://linux-hardware.org/?probe=b6b7396e06) | May 25, 2023 |
| ASUSTek       | PRIME H510M-E               | [1247209c34](https://linux-hardware.org/?probe=1247209c34) | May 24, 2023 |
| Lenovo        | 318E SDK0L22692 WIN 3792... | [5fb6f16a6d](https://linux-hardware.org/?probe=5fb6f16a6d) | May 24, 2023 |
| Gigabyte      | B365M DS3H                  | [149a19eeeb](https://linux-hardware.org/?probe=149a19eeeb) | May 24, 2023 |
| Gigabyte      | 8I945GZME-RH                | [3b4c63eddb](https://linux-hardware.org/?probe=3b4c63eddb) | May 24, 2023 |
| Intel         | H61                         | [794ecc6c43](https://linux-hardware.org/?probe=794ecc6c43) | May 23, 2023 |
| HP            | 81B3                        | [6b35d06402](https://linux-hardware.org/?probe=6b35d06402) | May 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | [c13217076b](https://linux-hardware.org/?probe=c13217076b) | May 23, 2023 |
| BESSTAR Te... | UM350                       | [e177bb8db5](https://linux-hardware.org/?probe=e177bb8db5) | May 23, 2023 |
| ASUSTek       | H81M-K                      | [f65eac842b](https://linux-hardware.org/?probe=f65eac842b) | May 23, 2023 |
| Unknown       | Unknown                     | [9cbda228a9](https://linux-hardware.org/?probe=9cbda228a9) | May 23, 2023 |
| Foxconn       | G41MD                       | [a3a8a67867](https://linux-hardware.org/?probe=a3a8a67867) | May 23, 2023 |
| BESSTAR Te... | HM90                        | [bc2b7d421d](https://linux-hardware.org/?probe=bc2b7d421d) | May 22, 2023 |
| HP            | 2AF3                        | [e70a1c12fb](https://linux-hardware.org/?probe=e70a1c12fb) | May 22, 2023 |
| ASRock        | H310M-STX                   | [c5d385dd80](https://linux-hardware.org/?probe=c5d385dd80) | May 22, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | [2f1b921a18](https://linux-hardware.org/?probe=2f1b921a18) | May 22, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [63a27f785d](https://linux-hardware.org/?probe=63a27f785d) | May 22, 2023 |
| HP            | 1632                        | [ed47689eec](https://linux-hardware.org/?probe=ed47689eec) | May 22, 2023 |
| Dell          | 0PC5F7 A03                  | [0ef682fa85](https://linux-hardware.org/?probe=0ef682fa85) | May 21, 2023 |
| ASUSTek       | P7P55-M                     | [1c5c9709dd](https://linux-hardware.org/?probe=1c5c9709dd) | May 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | [7ff619a028](https://linux-hardware.org/?probe=7ff619a028) | May 21, 2023 |
| ASRock        | Q1900M                      | [0290a65c70](https://linux-hardware.org/?probe=0290a65c70) | May 21, 2023 |
| ASUSTek       | P8H77-M LE                  | [e9b749f2ba](https://linux-hardware.org/?probe=e9b749f2ba) | May 21, 2023 |
| ASRock        | Z68 Pro3-M                  | [0deaff38f5](https://linux-hardware.org/?probe=0deaff38f5) | May 21, 2023 |
| Unknown       | Unknown                     | [c3af6442c9](https://linux-hardware.org/?probe=c3af6442c9) | May 21, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [b68e5e0285](https://linux-hardware.org/?probe=b68e5e0285) | May 20, 2023 |
| ASUSTek       | P8Z77-V                     | [b38a68e146](https://linux-hardware.org/?probe=b38a68e146) | May 20, 2023 |
| Foxconn       | G41MD                       | [1a649b0512](https://linux-hardware.org/?probe=1a649b0512) | May 20, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | [f4ed05479f](https://linux-hardware.org/?probe=f4ed05479f) | May 19, 2023 |
| Gigabyte      | F2A88X-D3H                  | [76bae0c7fb](https://linux-hardware.org/?probe=76bae0c7fb) | May 19, 2023 |
| ASRock        | Z590M Pro4                  | [d039ed90c5](https://linux-hardware.org/?probe=d039ed90c5) | May 19, 2023 |
| Gigabyte      | H510M H                     | [39725fefa4](https://linux-hardware.org/?probe=39725fefa4) | May 19, 2023 |
| HP            | 0A54h                       | [76953e42f8](https://linux-hardware.org/?probe=76953e42f8) | May 18, 2023 |
| ASUSTek       | P5KPL-SE                    | [2914e5278a](https://linux-hardware.org/?probe=2914e5278a) | May 18, 2023 |
| ASUSTek       | PRIME Z790-P                | [99d6173179](https://linux-hardware.org/?probe=99d6173179) | May 18, 2023 |
| Dell          | 0GDG8Y A00                  | [bc0a4ba851](https://linux-hardware.org/?probe=bc0a4ba851) | May 18, 2023 |
| Gigabyte      | GA-970A-D3                  | [b30dee1244](https://linux-hardware.org/?probe=b30dee1244) | May 18, 2023 |
| ASRock        | N68-GS4/USB3 FX             | [80fa152a82](https://linux-hardware.org/?probe=80fa152a82) | May 17, 2023 |
| Fujitsu       | D3420-U1 S26361-D3420-U1    | [958b2ab1f9](https://linux-hardware.org/?probe=958b2ab1f9) | May 17, 2023 |
| Gigabyte      | B450M H                     | [4bd367b4c7](https://linux-hardware.org/?probe=4bd367b4c7) | May 17, 2023 |
| HP            | 18E5                        | [5e25e2156a](https://linux-hardware.org/?probe=5e25e2156a) | May 16, 2023 |
| Maxtang       | FP650 V1.0                  | [8f1eba846a](https://linux-hardware.org/?probe=8f1eba846a) | May 16, 2023 |
| Foxconn       | P35A01                      | [d3f10a59ba](https://linux-hardware.org/?probe=d3f10a59ba) | May 16, 2023 |
| ASUSTek       | H110I-PLUS                  | [652d9e0fa9](https://linux-hardware.org/?probe=652d9e0fa9) | May 15, 2023 |
| Gigabyte      | B360M DS3H                  | [eee39f2f10](https://linux-hardware.org/?probe=eee39f2f10) | May 15, 2023 |
| ASUSTek       | M5A88-V EVO                 | [02da78340f](https://linux-hardware.org/?probe=02da78340f) | May 15, 2023 |
| Gigabyte      | H410M H V2                  | [1effa68567](https://linux-hardware.org/?probe=1effa68567) | May 15, 2023 |
| HP            | 8436                        | [ae94b377fd](https://linux-hardware.org/?probe=ae94b377fd) | May 15, 2023 |
| BESSTAR Te... | UM350                       | [fafdf532fb](https://linux-hardware.org/?probe=fafdf532fb) | May 15, 2023 |
| Dell          | 0KRC95 A02                  | [7380a83f05](https://linux-hardware.org/?probe=7380a83f05) | May 14, 2023 |
| ASUSTek       | M2A-MX                      | [43c0de16a2](https://linux-hardware.org/?probe=43c0de16a2) | May 14, 2023 |
| Lenovo        | ThinkCentre M58 7627AD5     | [e0b4de3daf](https://linux-hardware.org/?probe=e0b4de3daf) | May 14, 2023 |
| Inventec      | D CLASS A02                 | [309a617781](https://linux-hardware.org/?probe=309a617781) | May 13, 2023 |
| ASRock        | G41M-GS3                    | [8859685e86](https://linux-hardware.org/?probe=8859685e86) | May 13, 2023 |
| Dell          | 09KPNV A01                  | [cbd408a1a6](https://linux-hardware.org/?probe=cbd408a1a6) | May 13, 2023 |
| Gigabyte      | B360M DS3H                  | [82dbe1cdf7](https://linux-hardware.org/?probe=82dbe1cdf7) | May 13, 2023 |
| Dell          | 0NDYHG A01                  | [8fdc05a6ad](https://linux-hardware.org/?probe=8fdc05a6ad) | May 13, 2023 |
| Intel         | H61                         | [685bd5d439](https://linux-hardware.org/?probe=685bd5d439) | May 12, 2023 |
| Lenovo        | SDK0E50510 WIN 262507960... | [2892c822d5](https://linux-hardware.org/?probe=2892c822d5) | May 12, 2023 |
| Dell          | 0W0CHX A00                  | [60defd2bfe](https://linux-hardware.org/?probe=60defd2bfe) | May 12, 2023 |
| ASUSTek       | P5B-VM SE                   | [bd1c748eed](https://linux-hardware.org/?probe=bd1c748eed) | May 12, 2023 |
| HP            | 0A58h                       | [b48452bdd9](https://linux-hardware.org/?probe=b48452bdd9) | May 12, 2023 |
| Acer          | RS880M05                    | [5952c105f6](https://linux-hardware.org/?probe=5952c105f6) | May 12, 2023 |
| Dell          | 04YP6J A02                  | [aec2bbbb46](https://linux-hardware.org/?probe=aec2bbbb46) | May 11, 2023 |
| Gigabyte      | H61M-S1                     | [db910d4ee1](https://linux-hardware.org/?probe=db910d4ee1) | May 11, 2023 |
| MSI           | MEG X570 GODLIKE            | [989d8eef43](https://linux-hardware.org/?probe=989d8eef43) | May 11, 2023 |
| MSI           | H110M PRO-VH PLUS           | [040f5917ec](https://linux-hardware.org/?probe=040f5917ec) | May 10, 2023 |
| ASUSTek       | PRIME A320M-E               | [8376015b15](https://linux-hardware.org/?probe=8376015b15) | May 10, 2023 |
| MSI           | B350M PRO-VDH               | [76dbae3614](https://linux-hardware.org/?probe=76dbae3614) | May 10, 2023 |
| Intel         | X58M                        | [666b002908](https://linux-hardware.org/?probe=666b002908) | May 10, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [68afb54270](https://linux-hardware.org/?probe=68afb54270) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [8f7bcc525d](https://linux-hardware.org/?probe=8f7bcc525d) | May 10, 2023 |
| ASUSTek       | P8H77-V                     | [f86702afcf](https://linux-hardware.org/?probe=f86702afcf) | May 10, 2023 |
| ASUSTek       | M4A78L-M                    | [1a843c3a7f](https://linux-hardware.org/?probe=1a843c3a7f) | May 10, 2023 |
| HP            | 304Ah                       | [7c6a6b156f](https://linux-hardware.org/?probe=7c6a6b156f) | May 09, 2023 |
| Acer          | EG43M                       | [01704e814c](https://linux-hardware.org/?probe=01704e814c) | May 09, 2023 |
| ASUSTek       | M32CD4-K                    | [0bca52bcc5](https://linux-hardware.org/?probe=0bca52bcc5) | May 09, 2023 |
| ASUSTek       | P5KPL-VM                    | [f173eb5463](https://linux-hardware.org/?probe=f173eb5463) | May 09, 2023 |
| ASRock        | B450M Steel Legend          | [53d91dca3c](https://linux-hardware.org/?probe=53d91dca3c) | May 08, 2023 |
| Dell          | 0XCR8D A02                  | [5bc5ccdcad](https://linux-hardware.org/?probe=5bc5ccdcad) | May 08, 2023 |
| Gigabyte      | 970A-DS3P                   | [acf61a6132](https://linux-hardware.org/?probe=acf61a6132) | May 08, 2023 |
| Dell          | 0T656F A01                  | [94294c8cf0](https://linux-hardware.org/?probe=94294c8cf0) | May 08, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | [e7b77f5cf0](https://linux-hardware.org/?probe=e7b77f5cf0) | May 08, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | [22bd54d6d1](https://linux-hardware.org/?probe=22bd54d6d1) | May 08, 2023 |
| ASUSTek       | P5QLD PRO                   | [c2a0653c52](https://linux-hardware.org/?probe=c2a0653c52) | May 08, 2023 |
| Gigabyte      | X570S AORUS PRO AX          | [47388f4553](https://linux-hardware.org/?probe=47388f4553) | May 08, 2023 |
| Pegatron      | NARRA5                      | [46a87a6448](https://linux-hardware.org/?probe=46a87a6448) | May 07, 2023 |
| Dell          | 0R230R A00                  | [16611a8ed6](https://linux-hardware.org/?probe=16611a8ed6) | May 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | [893f259653](https://linux-hardware.org/?probe=893f259653) | May 07, 2023 |
| MSI           | H110M PRO-VH                | [d63bc9aeca](https://linux-hardware.org/?probe=d63bc9aeca) | May 07, 2023 |
| ASUSTek       | P8H67                       | [eeb083abcd](https://linux-hardware.org/?probe=eeb083abcd) | May 07, 2023 |
| Unknown       | Unknown                     | [68e1c1b5a4](https://linux-hardware.org/?probe=68e1c1b5a4) | May 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [99fbd772e8](https://linux-hardware.org/?probe=99fbd772e8) | May 07, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [895855ed9a](https://linux-hardware.org/?probe=895855ed9a) | May 07, 2023 |
| Gigabyte      | H470M K                     | [655bbe4068](https://linux-hardware.org/?probe=655bbe4068) | May 07, 2023 |
| Gigabyte      | Z97-D3H-CF                  | [f86e67c005](https://linux-hardware.org/?probe=f86e67c005) | May 07, 2023 |
| Shuttle       | FZ77                        | [e4a71bcb2d](https://linux-hardware.org/?probe=e4a71bcb2d) | May 07, 2023 |
| Gigabyte      | G41M-Combo                  | [077ced1a40](https://linux-hardware.org/?probe=077ced1a40) | May 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [f3ea9b926d](https://linux-hardware.org/?probe=f3ea9b926d) | May 06, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [4278efc4ca](https://linux-hardware.org/?probe=4278efc4ca) | May 06, 2023 |
| Alienware     | 0R3FWM A00                  | [c6dbe0270a](https://linux-hardware.org/?probe=c6dbe0270a) | May 06, 2023 |
| Dell          | 0M5DCD A00                  | [70862b2870](https://linux-hardware.org/?probe=70862b2870) | May 06, 2023 |
| Intel         | WADE-8076-ST-WMS            | [ae71682181](https://linux-hardware.org/?probe=ae71682181) | May 06, 2023 |
| ASUSTek       | P5G41T-M LE                 | [d5456946bb](https://linux-hardware.org/?probe=d5456946bb) | May 06, 2023 |
| ASRock        | G41C-GS                     | [03076cae9a](https://linux-hardware.org/?probe=03076cae9a) | May 06, 2023 |
| ASRock        | Q270 Pro BTC+               | [4fc3d2c86f](https://linux-hardware.org/?probe=4fc3d2c86f) | May 05, 2023 |
| MSI           | A75A-G55                    | [6ecb91213c](https://linux-hardware.org/?probe=6ecb91213c) | May 05, 2023 |
| Intel         | B75                         | [f70469a019](https://linux-hardware.org/?probe=f70469a019) | May 05, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [09bd22441b](https://linux-hardware.org/?probe=09bd22441b) | May 05, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | [c9a5bee99d](https://linux-hardware.org/?probe=c9a5bee99d) | May 05, 2023 |
| Foxconn       | H61MXV/H67MXV               | [ffb03b8bd4](https://linux-hardware.org/?probe=ffb03b8bd4) | May 05, 2023 |
| Gigabyte      | X570S AORUS ELITE           | [6f2b69becc](https://linux-hardware.org/?probe=6f2b69becc) | May 05, 2023 |
| Gigabyte      | AX370-Gaming K7             | [ca84298b9d](https://linux-hardware.org/?probe=ca84298b9d) | May 05, 2023 |
| Dell          | 0PU052                      | [03c6b8486e](https://linux-hardware.org/?probe=03c6b8486e) | May 05, 2023 |
| MSI           | 760GM-P34                   | [cb75fca473](https://linux-hardware.org/?probe=cb75fca473) | May 04, 2023 |
| ASRock        | Z590 Steel Legend           | [d36cec198b](https://linux-hardware.org/?probe=d36cec198b) | May 04, 2023 |
| Gigabyte      | H410M H                     | [6116c0df52](https://linux-hardware.org/?probe=6116c0df52) | May 04, 2023 |
| Gigabyte      | P55M-UD2                    | [a07a7cf773](https://linux-hardware.org/?probe=a07a7cf773) | May 04, 2023 |
| Gigabyte      | H81M-H                      | [92c9651e22](https://linux-hardware.org/?probe=92c9651e22) | May 04, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [2dabac74e0](https://linux-hardware.org/?probe=2dabac74e0) | May 03, 2023 |
| ASUSTek       | Maximus V GENE              | [1f49086889](https://linux-hardware.org/?probe=1f49086889) | May 03, 2023 |
| Acer          | H57M01                      | [affe73e1a5](https://linux-hardware.org/?probe=affe73e1a5) | May 03, 2023 |
| MSI           | MS-7025                     | [a15dc17cfc](https://linux-hardware.org/?probe=a15dc17cfc) | May 02, 2023 |
| Unknown       | 1.0                         | [5f99ebeed7](https://linux-hardware.org/?probe=5f99ebeed7) | May 02, 2023 |
| Lenovo        | SHARKBAY NO DPK             | [01bd34ece8](https://linux-hardware.org/?probe=01bd34ece8) | May 01, 2023 |
| HP            | 3031h                       | [84140549cd](https://linux-hardware.org/?probe=84140549cd) | May 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [00dc63bf78](https://linux-hardware.org/?probe=00dc63bf78) | May 01, 2023 |
| MAXSUN        | MS-A86FX FS M.3             | [3ce20d3b05](https://linux-hardware.org/?probe=3ce20d3b05) | May 01, 2023 |
| Lenovo        | ThinkCentre M71e 5033A1U    | [2e39bbf0cf](https://linux-hardware.org/?probe=2e39bbf0cf) | May 01, 2023 |
| HP            | 3033h                       | [31a4e00c60](https://linux-hardware.org/?probe=31a4e00c60) | May 01, 2023 |
| HP            | 3648h                       | [38ab69c4e2](https://linux-hardware.org/?probe=38ab69c4e2) | May 01, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | [2fd44c38fd](https://linux-hardware.org/?probe=2fd44c38fd) | May 01, 2023 |
| Gigabyte      | Z77M-D3H                    | [6da1ddcef5](https://linux-hardware.org/?probe=6da1ddcef5) | May 01, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [41e9bb9584](https://linux-hardware.org/?probe=41e9bb9584) | May 01, 2023 |
| HP            | 822A                        | [b373ff6def](https://linux-hardware.org/?probe=b373ff6def) | May 01, 2023 |
| Dell          | 06D7TR A00                  | [e7905065dd](https://linux-hardware.org/?probe=e7905065dd) | Apr 30, 2023 |
| MSI           | B450M PRO-M2                | [b650f0a26e](https://linux-hardware.org/?probe=b650f0a26e) | Apr 30, 2023 |
| DIEBOLD       | NM70-I                      | [c01a40d58c](https://linux-hardware.org/?probe=c01a40d58c) | Apr 30, 2023 |
| HP            | ProLiant ML310e Gen8 v2     | [501d26e477](https://linux-hardware.org/?probe=501d26e477) | Apr 30, 2023 |
| ASRock        | 760GM-HD                    | [db79e93331](https://linux-hardware.org/?probe=db79e93331) | Apr 30, 2023 |
| Gigabyte      | Z77M-D3H                    | [a3d2b3dcd3](https://linux-hardware.org/?probe=a3d2b3dcd3) | Apr 30, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [ac7894081f](https://linux-hardware.org/?probe=ac7894081f) | Apr 30, 2023 |
| Medion        | D3F3-EM                     | [6b9e38ad6c](https://linux-hardware.org/?probe=6b9e38ad6c) | Apr 30, 2023 |
| MSI           | A68HM GRENADE               | [938aa1cb46](https://linux-hardware.org/?probe=938aa1cb46) | Apr 30, 2023 |
| Gigabyte      | H77-DS3H                    | [6750e5f83d](https://linux-hardware.org/?probe=6750e5f83d) | Apr 30, 2023 |
| Acer          | E661GXM                     | [d5433b46bd](https://linux-hardware.org/?probe=d5433b46bd) | Apr 30, 2023 |
| Acer          | Aspire X3950                | [406366d5c1](https://linux-hardware.org/?probe=406366d5c1) | Apr 30, 2023 |
| T-bao         | MINI PC V1.0                | [8e77950434](https://linux-hardware.org/?probe=8e77950434) | Apr 30, 2023 |
| Intel         | H61                         | [167616bc61](https://linux-hardware.org/?probe=167616bc61) | Apr 30, 2023 |
| Dell          | 0GXM1W A02                  | [7dcb847a6c](https://linux-hardware.org/?probe=7dcb847a6c) | Apr 30, 2023 |
| Dell          | 0773VG A02                  | [a684ad4938](https://linux-hardware.org/?probe=a684ad4938) | Apr 29, 2023 |
| ASUSTek       | H81M-C/BR                   | [32942be783](https://linux-hardware.org/?probe=32942be783) | Apr 29, 2023 |
| ASRock        | 890FX Deluxe4               | [327a1a2b37](https://linux-hardware.org/?probe=327a1a2b37) | Apr 29, 2023 |
| ASUSTek       | Z97-P                       | [8ea78b28f1](https://linux-hardware.org/?probe=8ea78b28f1) | Apr 29, 2023 |
| Foxconn       | 2AB7                        | [01e7b05d2a](https://linux-hardware.org/?probe=01e7b05d2a) | Apr 29, 2023 |
| ASRock        | A320M-DVS R4.0              | [7e7da68aa3](https://linux-hardware.org/?probe=7e7da68aa3) | Apr 28, 2023 |
| AZW           | MINI S 10                   | [12ba32f977](https://linux-hardware.org/?probe=12ba32f977) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [92be2563a8](https://linux-hardware.org/?probe=92be2563a8) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [2beb48be05](https://linux-hardware.org/?probe=2beb48be05) | Apr 27, 2023 |
| MSI           | H81M-P33                    | [2099cafe74](https://linux-hardware.org/?probe=2099cafe74) | Apr 27, 2023 |
| ASUSTek       | P5GC-VM/SI                  | [abf277ec59](https://linux-hardware.org/?probe=abf277ec59) | Apr 27, 2023 |
| ASRock        | H510M-HDV R2.0              | [91930613cb](https://linux-hardware.org/?probe=91930613cb) | Apr 27, 2023 |
| MSI           | A78M-E35 V2                 | [5eb0f9d104](https://linux-hardware.org/?probe=5eb0f9d104) | Apr 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [6601cb2397](https://linux-hardware.org/?probe=6601cb2397) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [54dea0607f](https://linux-hardware.org/?probe=54dea0607f) | Apr 26, 2023 |
| ASUSTek       | AM1M-A                      | [ab3c4ea199](https://linux-hardware.org/?probe=ab3c4ea199) | Apr 26, 2023 |
| ASUSTek       | PRIME B250M-C               | [aca5bf366f](https://linux-hardware.org/?probe=aca5bf366f) | Apr 26, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | [238598d9ab](https://linux-hardware.org/?probe=238598d9ab) | Apr 26, 2023 |
| Biostar       | H610MH                      | [935928c60d](https://linux-hardware.org/?probe=935928c60d) | Apr 26, 2023 |
| Acer          | Aspire TC-605               | [b9dcc7f752](https://linux-hardware.org/?probe=b9dcc7f752) | Apr 26, 2023 |
| Gigabyte      | B75M-D3H                    | [4f1e4da37e](https://linux-hardware.org/?probe=4f1e4da37e) | Apr 26, 2023 |
| Intel         | H81                         | [9a14132581](https://linux-hardware.org/?probe=9a14132581) | Apr 26, 2023 |
| HP            | 83E2                        | [f10d975821](https://linux-hardware.org/?probe=f10d975821) | Apr 26, 2023 |
| ASUSTek       | PRIME H270-PLUS             | [8a0cd0bb6e](https://linux-hardware.org/?probe=8a0cd0bb6e) | Apr 26, 2023 |
| HP            | 3029h                       | [35be4d25c4](https://linux-hardware.org/?probe=35be4d25c4) | Apr 25, 2023 |
| ASUSTek       | P8P67 LE                    | [e46f340908](https://linux-hardware.org/?probe=e46f340908) | Apr 25, 2023 |
| ASRock        | AB350M-HDV                  | [44ac797451](https://linux-hardware.org/?probe=44ac797451) | Apr 25, 2023 |
| MSI           | B250M PRO-VH                | [f132c966f5](https://linux-hardware.org/?probe=f132c966f5) | Apr 25, 2023 |
| ASUSTek       | A68HM-K                     | [ae90303c3a](https://linux-hardware.org/?probe=ae90303c3a) | Apr 25, 2023 |
| ASUSTek       | J1800I-C                    | [0a58f3fa51](https://linux-hardware.org/?probe=0a58f3fa51) | Apr 25, 2023 |
| Lenovo        | ThinkCentre A70z 0401G6G    | [b1b8bf3df6](https://linux-hardware.org/?probe=b1b8bf3df6) | Apr 25, 2023 |
| Dell          | 0773VG A01                  | [40cf2f15c2](https://linux-hardware.org/?probe=40cf2f15c2) | Apr 25, 2023 |
| HP            | 18E9                        | [b9bb679cca](https://linux-hardware.org/?probe=b9bb679cca) | Apr 25, 2023 |
| ASUSTek       | PRIME A520M-K               | [a437a858a4](https://linux-hardware.org/?probe=a437a858a4) | Apr 25, 2023 |
| Lenovo        | SHARKBAY NOK                | [c5adfbd376](https://linux-hardware.org/?probe=c5adfbd376) | Apr 25, 2023 |
| Gigabyte      | 945GCM-S2L                  | [405bcbb43c](https://linux-hardware.org/?probe=405bcbb43c) | Apr 25, 2023 |
| ASRock        | H81M-VG4 R2.0               | [09c7ae9819](https://linux-hardware.org/?probe=09c7ae9819) | Apr 25, 2023 |
| Gigabyte      | Z77M-D3H                    | [915147a191](https://linux-hardware.org/?probe=915147a191) | Apr 25, 2023 |
| Gigabyte      | Z77M-D3H                    | [92a968e58d](https://linux-hardware.org/?probe=92a968e58d) | Apr 25, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [d9ad034d8c](https://linux-hardware.org/?probe=d9ad034d8c) | Apr 24, 2023 |
| ASUSTek       | P7P55D-E                    | [0e79aaac72](https://linux-hardware.org/?probe=0e79aaac72) | Apr 24, 2023 |
| ASRock        | H97M Anniversary            | [fdcfb2bde7](https://linux-hardware.org/?probe=fdcfb2bde7) | Apr 24, 2023 |
| ASUSTek       | PRIME Z590-P                | [ebe492b020](https://linux-hardware.org/?probe=ebe492b020) | Apr 24, 2023 |
| ASRock        | X570 Taichi                 | [0842334fa2](https://linux-hardware.org/?probe=0842334fa2) | Apr 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [6531aafbfe](https://linux-hardware.org/?probe=6531aafbfe) | Apr 24, 2023 |
| Gigabyte      | GA-970A-UD3                 | [6f3f14d26d](https://linux-hardware.org/?probe=6f3f14d26d) | Apr 23, 2023 |
| ASUSTek       | Z170-K                      | [538ebf1f96](https://linux-hardware.org/?probe=538ebf1f96) | Apr 23, 2023 |
| HP            | 0AA8h                       | [b927834a03](https://linux-hardware.org/?probe=b927834a03) | Apr 23, 2023 |
| Gigabyte      | B550 GAMING X V2            | [22594512d1](https://linux-hardware.org/?probe=22594512d1) | Apr 23, 2023 |
| Shenzhen M... | F6CQW                       | [c2be3dd62b](https://linux-hardware.org/?probe=c2be3dd62b) | Apr 23, 2023 |
| Gigabyte      | H61M-S2PH                   | [ec36f4ada2](https://linux-hardware.org/?probe=ec36f4ada2) | Apr 23, 2023 |
| MSI           | B450 GAMING PLUS MAX        | [cc80f06375](https://linux-hardware.org/?probe=cc80f06375) | Apr 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [3fa24b1a91](https://linux-hardware.org/?probe=3fa24b1a91) | Apr 23, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [93790f1835](https://linux-hardware.org/?probe=93790f1835) | Apr 23, 2023 |
| Gigabyte      | 990FXA-UD3                  | [bf1dbf49a8](https://linux-hardware.org/?probe=bf1dbf49a8) | Apr 22, 2023 |
| Gigabyte      | EP45-UD3                    | [5d45f63468](https://linux-hardware.org/?probe=5d45f63468) | Apr 22, 2023 |
| ASUSTek       | P8H77-I                     | [e2276c080b](https://linux-hardware.org/?probe=e2276c080b) | Apr 22, 2023 |
| Biostar       | A75MG                       | [50cb5c256e](https://linux-hardware.org/?probe=50cb5c256e) | Apr 22, 2023 |
| Gigabyte      | B550M S2H                   | [485f002152](https://linux-hardware.org/?probe=485f002152) | Apr 22, 2023 |
| Fujitsu       | FJNB037                     | [00e5e30f9b](https://linux-hardware.org/?probe=00e5e30f9b) | Apr 22, 2023 |
| Dell          | 0K240Y A02                  | [2d1b73d846](https://linux-hardware.org/?probe=2d1b73d846) | Apr 22, 2023 |
| ECS           | APLD-MINI                   | [8f3546722b](https://linux-hardware.org/?probe=8f3546722b) | Apr 22, 2023 |
| ASUSTek       | PRIME H510M-K               | [820acdb913](https://linux-hardware.org/?probe=820acdb913) | Apr 22, 2023 |
| MSI           | B360M BAZOOKA               | [46516c6f3a](https://linux-hardware.org/?probe=46516c6f3a) | Apr 22, 2023 |
| Fujitsu Si... | D2156-A1 S26361-D2156-A1    | [617f821f9a](https://linux-hardware.org/?probe=617f821f9a) | Apr 22, 2023 |
| Intel         | DG41RQ AAE54511-203         | [6a17fe6ead](https://linux-hardware.org/?probe=6a17fe6ead) | Apr 21, 2023 |
| ASRock        | H310CM-HG4                  | [6f49f4b883](https://linux-hardware.org/?probe=6f49f4b883) | Apr 21, 2023 |
| Intel         | DB65AL AAG12530-310         | [c625f3747a](https://linux-hardware.org/?probe=c625f3747a) | Apr 21, 2023 |
| Gigabyte      | B75M-HD3                    | [cde822d71c](https://linux-hardware.org/?probe=cde822d71c) | Apr 21, 2023 |
| HP            | 18E5                        | [0437b3deb1](https://linux-hardware.org/?probe=0437b3deb1) | Apr 21, 2023 |
| ASUSTek       | F2A85-V                     | [422eb87f07](https://linux-hardware.org/?probe=422eb87f07) | Apr 21, 2023 |
| Dell          | 0GDG8Y A00                  | [a315eaa776](https://linux-hardware.org/?probe=a315eaa776) | Apr 21, 2023 |
| Dell          | 040DDP A01                  | [6720e15331](https://linux-hardware.org/?probe=6720e15331) | Apr 21, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [fd91075868](https://linux-hardware.org/?probe=fd91075868) | Apr 21, 2023 |
| MouseCompu... | Z87-S01                     | [8caff0d2f2](https://linux-hardware.org/?probe=8caff0d2f2) | Apr 21, 2023 |
| ASRock        | P43DE                       | [8f2c0ecc69](https://linux-hardware.org/?probe=8f2c0ecc69) | Apr 21, 2023 |
| ASRock        | Z270 Taichi                 | [faf3402431](https://linux-hardware.org/?probe=faf3402431) | Apr 21, 2023 |
| Intel         | DG965RY AAD41691-301        | [0a153df418](https://linux-hardware.org/?probe=0a153df418) | Apr 20, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [5f1a1c6abd](https://linux-hardware.org/?probe=5f1a1c6abd) | Apr 20, 2023 |
| MSI           | B550-A PRO                  | [f2fc6a5da5](https://linux-hardware.org/?probe=f2fc6a5da5) | Apr 20, 2023 |
| Intel         | DG43GT AAE62768-301         | [643ed4ce33](https://linux-hardware.org/?probe=643ed4ce33) | Apr 20, 2023 |
| Gigabyte      | H61M-DS2                    | [8c43353ee9](https://linux-hardware.org/?probe=8c43353ee9) | Apr 20, 2023 |
| Acer          | Aspire XC-710 V:1.1         | [a09ea158cc](https://linux-hardware.org/?probe=a09ea158cc) | Apr 20, 2023 |
| HP            | 0B4Ch D                     | [69c613b55f](https://linux-hardware.org/?probe=69c613b55f) | Apr 20, 2023 |
| ASUSTek       | P5K SE                      | [eeff4cd84c](https://linux-hardware.org/?probe=eeff4cd84c) | Apr 20, 2023 |
| Gigabyte      | H81N                        | [5729c6c6a9](https://linux-hardware.org/?probe=5729c6c6a9) | Apr 20, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [561b87c8b4](https://linux-hardware.org/?probe=561b87c8b4) | Apr 20, 2023 |
| Gigabyte      | G31M-S2C                    | [0c45fc6929](https://linux-hardware.org/?probe=0c45fc6929) | Apr 20, 2023 |
| Intel         | H61S                        | [e29d71587a](https://linux-hardware.org/?probe=e29d71587a) | Apr 20, 2023 |
| HP            | 18E4                        | [1bd96a017f](https://linux-hardware.org/?probe=1bd96a017f) | Apr 19, 2023 |
| ASRock        | B560M-HDV                   | [b835e48fad](https://linux-hardware.org/?probe=b835e48fad) | Apr 19, 2023 |
| Dell          | 0NDYHG A01                  | [9c7e865b56](https://linux-hardware.org/?probe=9c7e865b56) | Apr 19, 2023 |
| Foxconn       | 2ABF                        | [53d3a8d066](https://linux-hardware.org/?probe=53d3a8d066) | Apr 19, 2023 |
| ECS           | BSW-MINI                    | [5d3161092f](https://linux-hardware.org/?probe=5d3161092f) | Apr 19, 2023 |
| ASRock        | B550M Pro4                  | [5fa6c74be4](https://linux-hardware.org/?probe=5fa6c74be4) | Apr 19, 2023 |
| MSI           | 0B58h                       | [6473456480](https://linux-hardware.org/?probe=6473456480) | Apr 19, 2023 |
| ECS           | H61H2-CM                    | [4396b0b045](https://linux-hardware.org/?probe=4396b0b045) | Apr 19, 2023 |
| HP            | 8309                        | [d82a6a4488](https://linux-hardware.org/?probe=d82a6a4488) | Apr 19, 2023 |
| MSI           | MS-7235                     | [efaeac524b](https://linux-hardware.org/?probe=efaeac524b) | Apr 18, 2023 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | [10693010af](https://linux-hardware.org/?probe=10693010af) | Apr 18, 2023 |
| Biostar       | A960D+V2                    | [34c47b4141](https://linux-hardware.org/?probe=34c47b4141) | Apr 18, 2023 |
| MSI           | B450 TOMAHAWK               | [fb3d31599f](https://linux-hardware.org/?probe=fb3d31599f) | Apr 18, 2023 |
| Dell          | 0KRC95 A00                  | [99ea2c7790](https://linux-hardware.org/?probe=99ea2c7790) | Apr 18, 2023 |
| NEC Comput... | MS-7451VM                   | [dc094ceba3](https://linux-hardware.org/?probe=dc094ceba3) | Apr 18, 2023 |
| ASRock        | B450M Pro4                  | [4c6abc2653](https://linux-hardware.org/?probe=4c6abc2653) | Apr 18, 2023 |
| ASUSTek       | P5QC                        | [7d47aa511b](https://linux-hardware.org/?probe=7d47aa511b) | Apr 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [dc707578c9](https://linux-hardware.org/?probe=dc707578c9) | Apr 18, 2023 |
| ASUSTek       | P8H67-M PRO                 | [9eb59318e2](https://linux-hardware.org/?probe=9eb59318e2) | Apr 18, 2023 |
| Acer          | FQ965M MP                   | [9be9793747](https://linux-hardware.org/?probe=9be9793747) | Apr 18, 2023 |
| HP            | 18E9                        | [8c36235f13](https://linux-hardware.org/?probe=8c36235f13) | Apr 18, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | [8b585cf135](https://linux-hardware.org/?probe=8b585cf135) | Apr 18, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [8944559c50](https://linux-hardware.org/?probe=8944559c50) | Apr 17, 2023 |
| Gigabyte      | G31M-ES2L                   | [0244194778](https://linux-hardware.org/?probe=0244194778) | Apr 17, 2023 |
| HP            | 1850                        | [fa2fa68792](https://linux-hardware.org/?probe=fa2fa68792) | Apr 17, 2023 |
| HP            | 8062                        | [a2558d47e8](https://linux-hardware.org/?probe=a2558d47e8) | Apr 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4174faae23](https://linux-hardware.org/?probe=4174faae23) | Apr 17, 2023 |
| ASRock        | H61M-DGS R2.0               | [695446a864](https://linux-hardware.org/?probe=695446a864) | Apr 17, 2023 |
| ASRock        | X99 Extreme4                | [e375be2ea6](https://linux-hardware.org/?probe=e375be2ea6) | Apr 17, 2023 |
| Medion        | MS-7728                     | [1da2d605db](https://linux-hardware.org/?probe=1da2d605db) | Apr 16, 2023 |
| Acer          | Aspire X3950                | [5a9abbd85f](https://linux-hardware.org/?probe=5a9abbd85f) | Apr 16, 2023 |
| eMachines     | E945GCU                     | [4e6aa4be24](https://linux-hardware.org/?probe=4e6aa4be24) | Apr 16, 2023 |
| ASUSTek       | X99-A/USB                   | [d686a4d03c](https://linux-hardware.org/?probe=d686a4d03c) | Apr 16, 2023 |
| MSI           | H310M PRO-VDH               | [01452c33d1](https://linux-hardware.org/?probe=01452c33d1) | Apr 16, 2023 |
| Gigabyte      | H61M-D2H-USB3               | [0134b33f82](https://linux-hardware.org/?probe=0134b33f82) | Apr 16, 2023 |
| ASRock        | N68-GS4 FX                  | [19a6cddfe0](https://linux-hardware.org/?probe=19a6cddfe0) | Apr 16, 2023 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | [4d3cbcc4d9](https://linux-hardware.org/?probe=4d3cbcc4d9) | Apr 16, 2023 |
| Dell          | 0RF705                      | [32dbb3206b](https://linux-hardware.org/?probe=32dbb3206b) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | [a2596e8d06](https://linux-hardware.org/?probe=a2596e8d06) | Apr 16, 2023 |
| ASRock        | B650M PG Riptide            | [71643d03ec](https://linux-hardware.org/?probe=71643d03ec) | Apr 16, 2023 |
| ASUSTek       | PRIME H410M-E               | [fedecfd9ff](https://linux-hardware.org/?probe=fedecfd9ff) | Apr 16, 2023 |
| Foxconn       | ALOE                        | [702f958604](https://linux-hardware.org/?probe=702f958604) | Apr 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [980c6d63d6](https://linux-hardware.org/?probe=980c6d63d6) | Apr 16, 2023 |
| Lenovo        | SHARKBAY SDK0J40700 WIN ... | [00b59d56cd](https://linux-hardware.org/?probe=00b59d56cd) | Apr 16, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | [fad0ef7fef](https://linux-hardware.org/?probe=fad0ef7fef) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [0853728b34](https://linux-hardware.org/?probe=0853728b34) | Apr 16, 2023 |
| MSI           | B150A GAMING PRO            | [26432a7622](https://linux-hardware.org/?probe=26432a7622) | Apr 16, 2023 |
| ASUSTek       | PRIME X570-P                | [337102cd4c](https://linux-hardware.org/?probe=337102cd4c) | Apr 15, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | [7ac461b735](https://linux-hardware.org/?probe=7ac461b735) | Apr 15, 2023 |
| Gigabyte      | F2A85XN-WIFI                | [80a8d69a06](https://linux-hardware.org/?probe=80a8d69a06) | Apr 15, 2023 |
| Foxconn       | 2A8C                        | [8a75d034c7](https://linux-hardware.org/?probe=8a75d034c7) | Apr 15, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [e17175b9ac](https://linux-hardware.org/?probe=e17175b9ac) | Apr 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [83d43e489d](https://linux-hardware.org/?probe=83d43e489d) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | [e412c388d8](https://linux-hardware.org/?probe=e412c388d8) | Apr 15, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | [82abb09c06](https://linux-hardware.org/?probe=82abb09c06) | Apr 15, 2023 |
| Gigabyte      | GA-870A-UD3                 | [a359e8f3ea](https://linux-hardware.org/?probe=a359e8f3ea) | Apr 15, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [8a5b5b102c](https://linux-hardware.org/?probe=8a5b5b102c) | Apr 14, 2023 |
| Gigabyte      | GA-990XA-UD3                | [d5669e92ed](https://linux-hardware.org/?probe=d5669e92ed) | Apr 14, 2023 |
| Gigabyte      | P55-UD3R                    | [5e8538987d](https://linux-hardware.org/?probe=5e8538987d) | Apr 14, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [3741318176](https://linux-hardware.org/?probe=3741318176) | Apr 14, 2023 |
| HP            | 1791                        | [c87bf6d0e1](https://linux-hardware.org/?probe=c87bf6d0e1) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [1bf207dfca](https://linux-hardware.org/?probe=1bf207dfca) | Apr 13, 2023 |
| Dell          | 0GXM1W A00                  | [f96d907026](https://linux-hardware.org/?probe=f96d907026) | Apr 13, 2023 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | [490a059818](https://linux-hardware.org/?probe=490a059818) | Apr 13, 2023 |
| HP            | 1589                        | [b1ca06250e](https://linux-hardware.org/?probe=b1ca06250e) | Apr 13, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [d79266b94f](https://linux-hardware.org/?probe=d79266b94f) | Apr 13, 2023 |
| HP            | 3397                        | [0e4d29ffcd](https://linux-hardware.org/?probe=0e4d29ffcd) | Apr 13, 2023 |
| Gigabyte      | Z77M-D3H                    | [ffdcd55e2e](https://linux-hardware.org/?probe=ffdcd55e2e) | Apr 13, 2023 |
| Gigabyte      | H61M-HD2                    | [ea4bae8ef7](https://linux-hardware.org/?probe=ea4bae8ef7) | Apr 13, 2023 |
| MSI           | MS-7360                     | [48bee654fc](https://linux-hardware.org/?probe=48bee654fc) | Apr 13, 2023 |
| HP            | 1998                        | [8f0fef0b77](https://linux-hardware.org/?probe=8f0fef0b77) | Apr 12, 2023 |
| HP            | 805D                        | [f12230e709](https://linux-hardware.org/?probe=f12230e709) | Apr 12, 2023 |
| ASRock        | Z97M Pro4                   | [d98390c8a7](https://linux-hardware.org/?probe=d98390c8a7) | Apr 12, 2023 |
| Dell          | 02K9CR A01                  | [45c419b8d6](https://linux-hardware.org/?probe=45c419b8d6) | Apr 12, 2023 |
| Gigabyte      | A320M-H-CF                  | [6ac890debf](https://linux-hardware.org/?probe=6ac890debf) | Apr 12, 2023 |
| ASRock        | M3N78D FX                   | [618073d9e9](https://linux-hardware.org/?probe=618073d9e9) | Apr 12, 2023 |
| Gigabyte      | H310M S2H x.x               | [203aeef6a1](https://linux-hardware.org/?probe=203aeef6a1) | Apr 12, 2023 |
| Unknown       | SKYBAY                      | [9cd0292459](https://linux-hardware.org/?probe=9cd0292459) | Apr 12, 2023 |
| Gigabyte      | B450M DS3H V2               | [63c52bc5db](https://linux-hardware.org/?probe=63c52bc5db) | Apr 12, 2023 |
| ABIT          | NF-M2S                      | [30e3a2e8c4](https://linux-hardware.org/?probe=30e3a2e8c4) | Apr 11, 2023 |
| ASUSTek       | P5LD2-X/1333                | [e0e655f63c](https://linux-hardware.org/?probe=e0e655f63c) | Apr 11, 2023 |
| Unknown       | Unknown                     | [c67c78ba10](https://linux-hardware.org/?probe=c67c78ba10) | Apr 11, 2023 |
| MSI           | 970A GAMING PRO CARBON      | [b6cae4ec58](https://linux-hardware.org/?probe=b6cae4ec58) | Apr 11, 2023 |
| Acer          | Aspire TC-780               | [ce8b386e5b](https://linux-hardware.org/?probe=ce8b386e5b) | Apr 11, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [ad8009e647](https://linux-hardware.org/?probe=ad8009e647) | Apr 11, 2023 |
| Lenovo        | Dory CRB                    | [cab4258e1b](https://linux-hardware.org/?probe=cab4258e1b) | Apr 11, 2023 |
| Dell          | 0WR7PY A02                  | [2cec768fe1](https://linux-hardware.org/?probe=2cec768fe1) | Apr 11, 2023 |
| HP            | 805B                        | [591658775d](https://linux-hardware.org/?probe=591658775d) | Apr 11, 2023 |
| MSI           | B450M MORTAR MAX            | [e2cffb810b](https://linux-hardware.org/?probe=e2cffb810b) | Apr 10, 2023 |
| Biostar       | H61MHV                      | [13b4632c72](https://linux-hardware.org/?probe=13b4632c72) | Apr 10, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [35f953cfe0](https://linux-hardware.org/?probe=35f953cfe0) | Apr 10, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [979e7ab8f3](https://linux-hardware.org/?probe=979e7ab8f3) | Apr 10, 2023 |
| ASRock        | B550M-ITX/ac                | [e043c1c94c](https://linux-hardware.org/?probe=e043c1c94c) | Apr 10, 2023 |
| Gigabyte      | H61M-D2-B3                  | [bf18b5af69](https://linux-hardware.org/?probe=bf18b5af69) | Apr 10, 2023 |
| HP            | 3032h                       | [824604840a](https://linux-hardware.org/?probe=824604840a) | Apr 10, 2023 |
| Lanix         | ChiefRiver                  | [ef23ac88e4](https://linux-hardware.org/?probe=ef23ac88e4) | Apr 10, 2023 |
| Biostar       | H81MHV3L                    | [8638a242be](https://linux-hardware.org/?probe=8638a242be) | Apr 10, 2023 |
| Biostar       | A320MH                      | [a2aef00c0c](https://linux-hardware.org/?probe=a2aef00c0c) | Apr 09, 2023 |
| ASRock        | X570 Pro4                   | [feb08fab62](https://linux-hardware.org/?probe=feb08fab62) | Apr 09, 2023 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | [54fabc7712](https://linux-hardware.org/?probe=54fabc7712) | Apr 09, 2023 |
| MACHINIST     | X99-k9 V1.0                 | [650acc25ef](https://linux-hardware.org/?probe=650acc25ef) | Apr 09, 2023 |
| ASRock        | Q1900M                      | [6ff7177033](https://linux-hardware.org/?probe=6ff7177033) | Apr 09, 2023 |
| Pegatron      | 2A73h                       | [5de48bf7df](https://linux-hardware.org/?probe=5de48bf7df) | Apr 09, 2023 |
| ECS           | H61H2-M17                   | [a2860baaee](https://linux-hardware.org/?probe=a2860baaee) | Apr 09, 2023 |
| HP            | 1998                        | [3974cfbb0c](https://linux-hardware.org/?probe=3974cfbb0c) | Apr 09, 2023 |
| Dell          | 0TTDMJ A00                  | [2b039ea053](https://linux-hardware.org/?probe=2b039ea053) | Apr 09, 2023 |
| ASUSTek       | AM1M-A                      | [120f5780bd](https://linux-hardware.org/?probe=120f5780bd) | Apr 09, 2023 |
| ASUSTek       | B85M-E                      | [fe9976de62](https://linux-hardware.org/?probe=fe9976de62) | Apr 09, 2023 |
| Gigabyte      | H370 HD3-CF                 | [b2c9afc61f](https://linux-hardware.org/?probe=b2c9afc61f) | Apr 09, 2023 |
| MSI           | B350M MORTAR                | [03960a3def](https://linux-hardware.org/?probe=03960a3def) | Apr 09, 2023 |
| Lenovo        | ThinkCentre M90p 5536W67    | [f67448dd99](https://linux-hardware.org/?probe=f67448dd99) | Apr 09, 2023 |
| Unknown       | Unknown                     | [2765290b8c](https://linux-hardware.org/?probe=2765290b8c) | Apr 09, 2023 |
| Dell          | 0Y2MRG A01                  | [d512dee0ba](https://linux-hardware.org/?probe=d512dee0ba) | Apr 09, 2023 |
| ASUSTek       | P5K                         | [00a17a60bf](https://linux-hardware.org/?probe=00a17a60bf) | Apr 09, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [4644a0ea43](https://linux-hardware.org/?probe=4644a0ea43) | Apr 09, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [0f364f6e82](https://linux-hardware.org/?probe=0f364f6e82) | Apr 09, 2023 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | [436d55c73e](https://linux-hardware.org/?probe=436d55c73e) | Apr 09, 2023 |
| ASRock        | X300-ITX                    | [dbdef76cc2](https://linux-hardware.org/?probe=dbdef76cc2) | Apr 09, 2023 |
| SYWZ          | S210H Series                | [5989537064](https://linux-hardware.org/?probe=5989537064) | Apr 09, 2023 |
| AZW           | U59                         | [404036be4e](https://linux-hardware.org/?probe=404036be4e) | Apr 09, 2023 |
| ASRock        | B150 Combo                  | [c4acc08020](https://linux-hardware.org/?probe=c4acc08020) | Apr 09, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | [e579aabfdb](https://linux-hardware.org/?probe=e579aabfdb) | Apr 09, 2023 |
| MSI           | A68HM-E33 V2                | [05fc2725cf](https://linux-hardware.org/?probe=05fc2725cf) | Apr 09, 2023 |
| Dell          | 0PU052                      | [8f8c7f3a02](https://linux-hardware.org/?probe=8f8c7f3a02) | Apr 09, 2023 |
| Intel         | DH67BL AAG10189-207         | [1f13dff346](https://linux-hardware.org/?probe=1f13dff346) | Apr 08, 2023 |
| MSI           | B350 PC MATE                | [5c6c535e4d](https://linux-hardware.org/?probe=5c6c535e4d) | Apr 08, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | [3fe1220d26](https://linux-hardware.org/?probe=3fe1220d26) | Apr 08, 2023 |
| HP            | 1459                        | [201dc05036](https://linux-hardware.org/?probe=201dc05036) | Apr 08, 2023 |
| ASRock        | 4X4-R1000                   | [56af110ee1](https://linux-hardware.org/?probe=56af110ee1) | Apr 08, 2023 |
| ASUSTek       | P8Z77-V PRO                 | [e1d6888ead](https://linux-hardware.org/?probe=e1d6888ead) | Apr 08, 2023 |
| Gigabyte      | GA-73PVM-S2                 | [2149d942b3](https://linux-hardware.org/?probe=2149d942b3) | Apr 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [e657bedde3](https://linux-hardware.org/?probe=e657bedde3) | Apr 08, 2023 |
| ASUSTek       | A88XM-A                     | [52728f9e37](https://linux-hardware.org/?probe=52728f9e37) | Apr 08, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [4b4e5dfe24](https://linux-hardware.org/?probe=4b4e5dfe24) | Apr 08, 2023 |
| ASUSTek       | P5K                         | [ea3489709c](https://linux-hardware.org/?probe=ea3489709c) | Apr 08, 2023 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | [9cd5518f53](https://linux-hardware.org/?probe=9cd5518f53) | Apr 08, 2023 |
| Gigabyte      | B450M S2H                   | [f08d8d6bbd](https://linux-hardware.org/?probe=f08d8d6bbd) | Apr 08, 2023 |
| ASUSTek       | P8P67                       | [a62766f42e](https://linux-hardware.org/?probe=a62766f42e) | Apr 08, 2023 |
| MSI           | B550M-A PRO                 | [e3fcf877c0](https://linux-hardware.org/?probe=e3fcf877c0) | Apr 08, 2023 |
| Acer          | Aspire X3990                | [4d4816d6f8](https://linux-hardware.org/?probe=4d4816d6f8) | Apr 08, 2023 |
| ASRock        | 960GC-GS FX                 | [90cb74d9f0](https://linux-hardware.org/?probe=90cb74d9f0) | Apr 08, 2023 |
| ASRock        | 970 Pro3 R2.0               | [375bb1794b](https://linux-hardware.org/?probe=375bb1794b) | Apr 08, 2023 |
| ASUSTek       | A68HM-K                     | [55d971a67f](https://linux-hardware.org/?probe=55d971a67f) | Apr 08, 2023 |
| Lenovo        | No DPK                      | [7028629b85](https://linux-hardware.org/?probe=7028629b85) | Apr 08, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [c2132caa73](https://linux-hardware.org/?probe=c2132caa73) | Apr 08, 2023 |
| Biostar       | A520MH                      | [9cf296886b](https://linux-hardware.org/?probe=9cf296886b) | Apr 07, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | [fa161c8db8](https://linux-hardware.org/?probe=fa161c8db8) | Apr 07, 2023 |
| ASRock        | B360M/OEM                   | [d1feabb956](https://linux-hardware.org/?probe=d1feabb956) | Apr 07, 2023 |
| ASUSTek       | H110M-R                     | [d4e3e5d85c](https://linux-hardware.org/?probe=d4e3e5d85c) | Apr 07, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [2d355e87d7](https://linux-hardware.org/?probe=2d355e87d7) | Apr 07, 2023 |
| Dell          | 0KRC95 A01                  | [9300a95302](https://linux-hardware.org/?probe=9300a95302) | Apr 07, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [bd1dc31213](https://linux-hardware.org/?probe=bd1dc31213) | Apr 07, 2023 |
| ASRock        | H97M Pro4                   | [904fc9e194](https://linux-hardware.org/?probe=904fc9e194) | Apr 07, 2023 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [c76171c0a7](https://linux-hardware.org/?probe=c76171c0a7) | Apr 07, 2023 |
| ASRock        | 970A-G                      | [819194bd46](https://linux-hardware.org/?probe=819194bd46) | Apr 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [0f3e23c7ce](https://linux-hardware.org/?probe=0f3e23c7ce) | Apr 07, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | [10c9b38ed6](https://linux-hardware.org/?probe=10c9b38ed6) | Apr 07, 2023 |
| Gigabyte      | B75M-D3H                    | [bf0c0bb982](https://linux-hardware.org/?probe=bf0c0bb982) | Apr 07, 2023 |
| Gigabyte      | H61M-S2PV                   | [8c4f851451](https://linux-hardware.org/?probe=8c4f851451) | Apr 07, 2023 |
| HP            | 82A2                        | [68d2b054d7](https://linux-hardware.org/?probe=68d2b054d7) | Apr 07, 2023 |
| Gigabyte      | Z77M-D3H                    | [d76bd92923](https://linux-hardware.org/?probe=d76bd92923) | Apr 07, 2023 |
| ASUSTek       | M4N98TD EVO                 | [8a2a2cf1ce](https://linux-hardware.org/?probe=8a2a2cf1ce) | Apr 07, 2023 |
| Alienware     | 0TYR0X A01                  | [35c94d7cd4](https://linux-hardware.org/?probe=35c94d7cd4) | Apr 07, 2023 |
| ASRock        | Z370 Taichi                 | [49aced4300](https://linux-hardware.org/?probe=49aced4300) | Apr 07, 2023 |
| MSI           | KA790GX                     | [c3dfb7614d](https://linux-hardware.org/?probe=c3dfb7614d) | Apr 07, 2023 |
| HP            | 1998                        | [50421ddca5](https://linux-hardware.org/?probe=50421ddca5) | Apr 07, 2023 |
| Biostar       | G41D3                       | [969695eafd](https://linux-hardware.org/?probe=969695eafd) | Apr 06, 2023 |
| Dell          | 0DFRFW A01                  | [773a0244a1](https://linux-hardware.org/?probe=773a0244a1) | Apr 06, 2023 |
| ASUSTek       | P8H61-M LX                  | [df6a8a3453](https://linux-hardware.org/?probe=df6a8a3453) | Apr 06, 2023 |
| Dell          | 04GJJT A00                  | [5c7df0085d](https://linux-hardware.org/?probe=5c7df0085d) | Apr 06, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [4a0aa9f6d0](https://linux-hardware.org/?probe=4a0aa9f6d0) | Apr 06, 2023 |
| MSI           | J1800I                      | [983e4f18d4](https://linux-hardware.org/?probe=983e4f18d4) | Apr 06, 2023 |
| ASRock        | A320M-DVS R4.0              | [c6e30ff3cc](https://linux-hardware.org/?probe=c6e30ff3cc) | Apr 06, 2023 |
| Dell          | 0HD5W2 A01                  | [294131b150](https://linux-hardware.org/?probe=294131b150) | Apr 06, 2023 |
| ASRock        | H61M-DGS                    | [e2dd28ca36](https://linux-hardware.org/?probe=e2dd28ca36) | Apr 06, 2023 |
| Biostar       | G31D-M7                     | [9d1a5129bd](https://linux-hardware.org/?probe=9d1a5129bd) | Apr 06, 2023 |
| Gigabyte      | A320M-S2H-CF                | [e04829aef9](https://linux-hardware.org/?probe=e04829aef9) | Apr 06, 2023 |
| Gigabyte      | F2A55M-DS2                  | [fea5792a8b](https://linux-hardware.org/?probe=fea5792a8b) | Apr 06, 2023 |
| MSI           | A88XM-E35 V2                | [bf4c16404e](https://linux-hardware.org/?probe=bf4c16404e) | Apr 06, 2023 |
| ASUSTek       | PRIME B450M-A               | [122c9d0ae2](https://linux-hardware.org/?probe=122c9d0ae2) | Apr 06, 2023 |
| ASUSTek       | H170-PRO                    | [8756f8891c](https://linux-hardware.org/?probe=8756f8891c) | Apr 06, 2023 |
| ASUSTek       | A68HM-E                     | [0c9ae9bcd7](https://linux-hardware.org/?probe=0c9ae9bcd7) | Apr 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [9e99b4150b](https://linux-hardware.org/?probe=9e99b4150b) | Apr 06, 2023 |
| eMachines     | EL1352                      | [ccd83551e0](https://linux-hardware.org/?probe=ccd83551e0) | Apr 06, 2023 |
| ASUSTek       | P5B                         | [a2a4936e2c](https://linux-hardware.org/?probe=a2a4936e2c) | Apr 06, 2023 |
| Gigabyte      | Z690 UD DDR4                | [7644d4a8fa](https://linux-hardware.org/?probe=7644d4a8fa) | Apr 06, 2023 |
| Dell          | 0HHV7N A00                  | [73cc9e48a0](https://linux-hardware.org/?probe=73cc9e48a0) | Apr 06, 2023 |
| ASUSTek       | PRIME A320M-K               | [8b92d25f91](https://linux-hardware.org/?probe=8b92d25f91) | Apr 06, 2023 |
| Dell          | 0F5C5X A00                  | [0e0a176bf8](https://linux-hardware.org/?probe=0e0a176bf8) | Apr 06, 2023 |
| HP            | 830C                        | [ab6399decd](https://linux-hardware.org/?probe=ab6399decd) | Apr 06, 2023 |
| Dell          | 0GXM1W A02                  | [3fae5e4d5c](https://linux-hardware.org/?probe=3fae5e4d5c) | Apr 05, 2023 |
| Gigabyte      | B560 DS3H AC-Y1             | [0893f3016e](https://linux-hardware.org/?probe=0893f3016e) | Apr 05, 2023 |
| Gigabyte      | X570 GAMING X               | [83132b245e](https://linux-hardware.org/?probe=83132b245e) | Apr 05, 2023 |
| Dell          | 0HN7XN A01                  | [43469cea83](https://linux-hardware.org/?probe=43469cea83) | Apr 05, 2023 |
| MSI           | A320M-A PRO MAX             | [8c33d7498d](https://linux-hardware.org/?probe=8c33d7498d) | Apr 05, 2023 |
| HP            | 3397                        | [2c3fa64234](https://linux-hardware.org/?probe=2c3fa64234) | Apr 05, 2023 |
| Gigabyte      | H97-HD3                     | [caf5563d44](https://linux-hardware.org/?probe=caf5563d44) | Apr 05, 2023 |
| Acer          | Aspire XC-330               | [a0e2b31c08](https://linux-hardware.org/?probe=a0e2b31c08) | Apr 05, 2023 |
| Acer          | EG31M R01-C3                | [a548c9e661](https://linux-hardware.org/?probe=a548c9e661) | Apr 05, 2023 |
| ASRock        | A320M-DVS R4.0              | [6da0293a4b](https://linux-hardware.org/?probe=6da0293a4b) | Apr 05, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [0e7d453676](https://linux-hardware.org/?probe=0e7d453676) | Apr 05, 2023 |
| ASUSTek       | P5KPL-CM                    | [78c525b19b](https://linux-hardware.org/?probe=78c525b19b) | Apr 05, 2023 |
| Gigabyte      | F2A75M-HD2                  | [04694eb1f9](https://linux-hardware.org/?probe=04694eb1f9) | Apr 05, 2023 |
| MSI           | B150 PC MATE                | [da2d2d3d5c](https://linux-hardware.org/?probe=da2d2d3d5c) | Apr 05, 2023 |
| ASRock        | B450 Steel Legend           | [62bdbae29c](https://linux-hardware.org/?probe=62bdbae29c) | Apr 05, 2023 |
| HP            | 2AA2                        | [28c42fc95f](https://linux-hardware.org/?probe=28c42fc95f) | Apr 05, 2023 |
| ASRock        | B75 Pro3-M                  | [81b76a458e](https://linux-hardware.org/?probe=81b76a458e) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [5881a47fd0](https://linux-hardware.org/?probe=5881a47fd0) | Apr 05, 2023 |
| Gigabyte      | GA-A75M-UD2H                | [7f4b812a58](https://linux-hardware.org/?probe=7f4b812a58) | Apr 05, 2023 |
| MSI           | Z97 GAMING 5                | [41a5c82c1e](https://linux-hardware.org/?probe=41a5c82c1e) | Apr 05, 2023 |
| Gigabyte      | B660M DS3H DDR4             | [59d486f5bd](https://linux-hardware.org/?probe=59d486f5bd) | Apr 05, 2023 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | [4505cd8ddc](https://linux-hardware.org/?probe=4505cd8ddc) | Apr 05, 2023 |
| ASUSTek       | PRIME B360M-K               | [caa685db91](https://linux-hardware.org/?probe=caa685db91) | Apr 05, 2023 |
| ASUSTek       | PRIME Z370M-PLUS II         | [9fc5c6f8a7](https://linux-hardware.org/?probe=9fc5c6f8a7) | Apr 05, 2023 |
| Dell          | 0V8WGR A02                  | [3b8d266671](https://linux-hardware.org/?probe=3b8d266671) | Apr 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [540d1f11a6](https://linux-hardware.org/?probe=540d1f11a6) | Apr 05, 2023 |
| HP            | 18E5                        | [71c68a2c6a](https://linux-hardware.org/?probe=71c68a2c6a) | Apr 05, 2023 |
| ASRock        | H61MV-ITX                   | [c721707e0a](https://linux-hardware.org/?probe=c721707e0a) | Apr 05, 2023 |
| MSI           | MS-7529                     | [2c6cdf6397](https://linux-hardware.org/?probe=2c6cdf6397) | Apr 04, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | [d8dc8a37b1](https://linux-hardware.org/?probe=d8dc8a37b1) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f43197a66f](https://linux-hardware.org/?probe=f43197a66f) | Apr 04, 2023 |
| ASUSTek       | A68HM-PLUS                  | [4246e4df2b](https://linux-hardware.org/?probe=4246e4df2b) | Apr 04, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [9885a8adee](https://linux-hardware.org/?probe=9885a8adee) | Apr 04, 2023 |
| MSI           | Z390-A PRO                  | [60583d2cb0](https://linux-hardware.org/?probe=60583d2cb0) | Apr 04, 2023 |
| Acer          | Aspire M1470                | [d0120a6452](https://linux-hardware.org/?probe=d0120a6452) | Apr 04, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [1eae1b3796](https://linux-hardware.org/?probe=1eae1b3796) | Apr 04, 2023 |
| ASUSTek       | PRIME A320M-C R2.0          | [70b2a73996](https://linux-hardware.org/?probe=70b2a73996) | Apr 04, 2023 |
| Dell          | 040DDP A00                  | [af03c6afe4](https://linux-hardware.org/?probe=af03c6afe4) | Apr 04, 2023 |
| MSI           | B450-A PRO MAX              | [31d10a7e98](https://linux-hardware.org/?probe=31d10a7e98) | Apr 04, 2023 |
| Lenovo        | 3140 NOK                    | [207d400267](https://linux-hardware.org/?probe=207d400267) | Apr 04, 2023 |
| Fujitsu       | D3236-S1 S26361-D3236-S1    | [89962b2435](https://linux-hardware.org/?probe=89962b2435) | Apr 04, 2023 |
| ASUSTek       | A55BM-E                     | [3e174ff8a3](https://linux-hardware.org/?probe=3e174ff8a3) | Apr 04, 2023 |
| ECS           | Iris8                       | [f86927f9ff](https://linux-hardware.org/?probe=f86927f9ff) | Apr 04, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [e13bc4c0b8](https://linux-hardware.org/?probe=e13bc4c0b8) | Apr 04, 2023 |
| Intel         | B75                         | [8d116f68cf](https://linux-hardware.org/?probe=8d116f68cf) | Apr 04, 2023 |
| Dell          | 00F82W A00                  | [a78ce73463](https://linux-hardware.org/?probe=a78ce73463) | Apr 04, 2023 |
| Dell          | 0D6H9T A01                  | [dd49afbf3f](https://linux-hardware.org/?probe=dd49afbf3f) | Apr 04, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [8db8b523f3](https://linux-hardware.org/?probe=8db8b523f3) | Apr 04, 2023 |
| ASUSTek       | PRIME Q270M-C               | [a3d5910e8e](https://linux-hardware.org/?probe=a3d5910e8e) | Apr 04, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [f637374c21](https://linux-hardware.org/?probe=f637374c21) | Apr 03, 2023 |
| ASRock        | 990FX Extreme3              | [013cd9b246](https://linux-hardware.org/?probe=013cd9b246) | Apr 03, 2023 |
| Intel         | DZ87KLT75K AAG74721-304     | [4f97ce0a4b](https://linux-hardware.org/?probe=4f97ce0a4b) | Apr 03, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | [de861c6d3f](https://linux-hardware.org/?probe=de861c6d3f) | Apr 03, 2023 |
| ASRock        | FM2A68M-DG3+                | [47c6d88922](https://linux-hardware.org/?probe=47c6d88922) | Apr 03, 2023 |
| MSI           | H81M-E33                    | [34b04c305a](https://linux-hardware.org/?probe=34b04c305a) | Apr 03, 2023 |
| ASRock        | A55M-HVS                    | [426d150c30](https://linux-hardware.org/?probe=426d150c30) | Apr 03, 2023 |
| MSI           | 760GM-P23                   | [7c446415d8](https://linux-hardware.org/?probe=7c446415d8) | Apr 03, 2023 |
| Foxconn       | H67MP-S/-V/H67MP            | [08612f7258](https://linux-hardware.org/?probe=08612f7258) | Apr 03, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [65668a06ad](https://linux-hardware.org/?probe=65668a06ad) | Apr 03, 2023 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [2cbd354a8f](https://linux-hardware.org/?probe=2cbd354a8f) | Apr 03, 2023 |
| Pegatron      | JESSE                       | [60c37e2dda](https://linux-hardware.org/?probe=60c37e2dda) | Apr 03, 2023 |
| Dell          | 09KPNV A00                  | [2296872799](https://linux-hardware.org/?probe=2296872799) | Apr 03, 2023 |
| Gigabyte      | B360M H                     | [cc5feeb3eb](https://linux-hardware.org/?probe=cc5feeb3eb) | Apr 03, 2023 |
| ASUSTek       | H61M-K                      | [f4b76d1e01](https://linux-hardware.org/?probe=f4b76d1e01) | Apr 03, 2023 |
| Gigabyte      | H61M-S2P                    | [6d808d8c4d](https://linux-hardware.org/?probe=6d808d8c4d) | Apr 03, 2023 |
| MSI           | B450M MORTAR MAX            | [53ace0533c](https://linux-hardware.org/?probe=53ace0533c) | Apr 03, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [8566b9511a](https://linux-hardware.org/?probe=8566b9511a) | Apr 02, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [07089aebf5](https://linux-hardware.org/?probe=07089aebf5) | Apr 02, 2023 |
| Lenovo        | ThinkCentre M91p 4518RH1    | [ead0ecfb3a](https://linux-hardware.org/?probe=ead0ecfb3a) | Apr 02, 2023 |
| MSI           | A88XM-E35                   | [fb40e13d92](https://linux-hardware.org/?probe=fb40e13d92) | Apr 02, 2023 |
| HP            | 2215                        | [9e43555613](https://linux-hardware.org/?probe=9e43555613) | Apr 02, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | [f9d9946012](https://linux-hardware.org/?probe=f9d9946012) | Apr 02, 2023 |
| ASRock        | Q1900M                      | [dfae44d3f6](https://linux-hardware.org/?probe=dfae44d3f6) | Apr 02, 2023 |
| ASUSTek       | Z97-K                       | [d56ea84c5f](https://linux-hardware.org/?probe=d56ea84c5f) | Apr 02, 2023 |
| Gigabyte      | GA-880GM-UD2H               | [f46913bb86](https://linux-hardware.org/?probe=f46913bb86) | Apr 02, 2023 |
| MSI           | H510M-A PRO                 | [f580fda8f1](https://linux-hardware.org/?probe=f580fda8f1) | Apr 02, 2023 |
| MSI           | FM2-A75IA-E53               | [f8092c0da9](https://linux-hardware.org/?probe=f8092c0da9) | Apr 02, 2023 |
| ASRock        | H81M-VG4 R2.0               | [f811a203a0](https://linux-hardware.org/?probe=f811a203a0) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [3a8d512ae4](https://linux-hardware.org/?probe=3a8d512ae4) | Apr 02, 2023 |
| MSI           | MPG Z590 GAMING CARBON W... | [d0006b7678](https://linux-hardware.org/?probe=d0006b7678) | Apr 02, 2023 |
| HP            | 2AF3                        | [fe33aa7257](https://linux-hardware.org/?probe=fe33aa7257) | Apr 02, 2023 |
| MSI           | A320M-A PRO MAX             | [54fbd647bc](https://linux-hardware.org/?probe=54fbd647bc) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [024be9ff96](https://linux-hardware.org/?probe=024be9ff96) | Apr 02, 2023 |
| Gigabyte      | H410M S2 V3                 | [b908036588](https://linux-hardware.org/?probe=b908036588) | Apr 02, 2023 |
| HP            | 3397                        | [04943f0d5f](https://linux-hardware.org/?probe=04943f0d5f) | Apr 02, 2023 |
| ASUSTek       | B150M-K D3                  | [08df6b50be](https://linux-hardware.org/?probe=08df6b50be) | Apr 02, 2023 |
| Dell          | 096JG8 A01                  | [d016e78eab](https://linux-hardware.org/?probe=d016e78eab) | Apr 02, 2023 |
| Acer          | Veriton X2632G V:1.0        | [f5eafafc96](https://linux-hardware.org/?probe=f5eafafc96) | Apr 02, 2023 |
| Dell          | 0GDG8Y A02                  | [83110b2400](https://linux-hardware.org/?probe=83110b2400) | Apr 02, 2023 |
| ULTRATOP      | C2017-LIVA-ZE               | [96d0c389b8](https://linux-hardware.org/?probe=96d0c389b8) | Apr 02, 2023 |
| Acer          | EQ45LM                      | [5bafe47784](https://linux-hardware.org/?probe=5bafe47784) | Apr 02, 2023 |
| Intel         | B75                         | [caad7f240a](https://linux-hardware.org/?probe=caad7f240a) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | [7ccbfd0fd3](https://linux-hardware.org/?probe=7ccbfd0fd3) | Apr 02, 2023 |
| Dell          | 02YYK5 A01                  | [ecfba44652](https://linux-hardware.org/?probe=ecfba44652) | Apr 02, 2023 |
| Unknown       | Unknown                     | [089fc02d40](https://linux-hardware.org/?probe=089fc02d40) | Apr 01, 2023 |
| Nvidia        | MCP7A 2                     | [26ab83ffcb](https://linux-hardware.org/?probe=26ab83ffcb) | Apr 01, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [d645276b0a](https://linux-hardware.org/?probe=d645276b0a) | Apr 01, 2023 |
| Acer          | RS880M05                    | [bddd902030](https://linux-hardware.org/?probe=bddd902030) | Apr 01, 2023 |
| ASUSTek       | M5A97 LE R2.0               | [4f9739adf7](https://linux-hardware.org/?probe=4f9739adf7) | Apr 01, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | [b7848305ec](https://linux-hardware.org/?probe=b7848305ec) | Apr 01, 2023 |
| Gigabyte      | H410M DS2V                  | [67b081e859](https://linux-hardware.org/?probe=67b081e859) | Apr 01, 2023 |
| Gigabyte      | Z68X-UD4-B3                 | [79bcb88c5b](https://linux-hardware.org/?probe=79bcb88c5b) | Apr 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [5919c1d671](https://linux-hardware.org/?probe=5919c1d671) | Apr 01, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | [217bb72a30](https://linux-hardware.org/?probe=217bb72a30) | Apr 01, 2023 |
| Biostar       | H61MLV                      | [db9714357e](https://linux-hardware.org/?probe=db9714357e) | Apr 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [b272d7b271](https://linux-hardware.org/?probe=b272d7b271) | Apr 01, 2023 |
| ASUSTek       | PRIME Z490-P                | [bbbfbb2dfc](https://linux-hardware.org/?probe=bbbfbb2dfc) | Apr 01, 2023 |
| Intel         | DB75EN AAG39650-303         | [50d4a766a6](https://linux-hardware.org/?probe=50d4a766a6) | Apr 01, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [3f218796ae](https://linux-hardware.org/?probe=3f218796ae) | Apr 01, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [5ef1391fb2](https://linux-hardware.org/?probe=5ef1391fb2) | Apr 01, 2023 |
| Lenovo        | 317E SDK0K17763 WIN 1801... | [a4cad34ac9](https://linux-hardware.org/?probe=a4cad34ac9) | Apr 01, 2023 |
| ASUSTek       | PRIME X470-PRO              | [96fcc41161](https://linux-hardware.org/?probe=96fcc41161) | Apr 01, 2023 |
| ASRock        | B450 Pro4 R2.0              | [046d59655e](https://linux-hardware.org/?probe=046d59655e) | Apr 01, 2023 |
| ASUSTek       | B250 MINING EXPERT          | [da86fa8f75](https://linux-hardware.org/?probe=da86fa8f75) | Apr 01, 2023 |
| MSI           | MEG X670E ACE               | [2b9356529f](https://linux-hardware.org/?probe=2b9356529f) | Apr 01, 2023 |
| Lenovo        | SHARKBAY NOK                | [091d2eda88](https://linux-hardware.org/?probe=091d2eda88) | Apr 01, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | [664da8ff45](https://linux-hardware.org/?probe=664da8ff45) | Apr 01, 2023 |
| Gigabyte      | MZGLKDP-00                  | [c9427f4873](https://linux-hardware.org/?probe=c9427f4873) | Apr 01, 2023 |
| Gigabyte      | F2A78M-DS2                  | [0528b2df2b](https://linux-hardware.org/?probe=0528b2df2b) | Apr 01, 2023 |
| ASUSTek       | PRIME B350M-A               | [f8afb163dc](https://linux-hardware.org/?probe=f8afb163dc) | Apr 01, 2023 |
| ASRock        | B460M Pro4                  | [1f3b96d1a0](https://linux-hardware.org/?probe=1f3b96d1a0) | Apr 01, 2023 |
| Acer          | Aspire XC-780               | [206239c162](https://linux-hardware.org/?probe=206239c162) | Apr 01, 2023 |
| MSI           | H97M-G43                    | [b93caf26e4](https://linux-hardware.org/?probe=b93caf26e4) | Apr 01, 2023 |
| Fujitsu       | D3432-A1 S26361-D3432-A1    | [86241cd6ad](https://linux-hardware.org/?probe=86241cd6ad) | Apr 01, 2023 |
| HP            | 304Ah                       | [14d92e85a2](https://linux-hardware.org/?probe=14d92e85a2) | Apr 01, 2023 |
| HP            | 84FD                        | [79367d5f7d](https://linux-hardware.org/?probe=79367d5f7d) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS M                | [c1a0385d07](https://linux-hardware.org/?probe=c1a0385d07) | Apr 01, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [ad3ead1116](https://linux-hardware.org/?probe=ad3ead1116) | Apr 01, 2023 |
| ASUSTek       | PRIME A320M-K               | [16f87cd333](https://linux-hardware.org/?probe=16f87cd333) | Apr 01, 2023 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | [f54ccba86f](https://linux-hardware.org/?probe=f54ccba86f) | Apr 01, 2023 |
| ASUSTek       | P8Z77-V PREMIUM             | [d774a892d1](https://linux-hardware.org/?probe=d774a892d1) | Apr 01, 2023 |
| Dell          | 0TTDMJ A00                  | [5d6606235d](https://linux-hardware.org/?probe=5d6606235d) | Apr 01, 2023 |
| Dell          | 0M5DCD A00                  | [91cc314380](https://linux-hardware.org/?probe=91cc314380) | Apr 01, 2023 |
| Gigabyte      | F2A88XM-HD3                 | [39bc576f7f](https://linux-hardware.org/?probe=39bc576f7f) | Apr 01, 2023 |
| HP            | 8053                        | [6c887800bb](https://linux-hardware.org/?probe=6c887800bb) | Apr 01, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [369bd03522](https://linux-hardware.org/?probe=369bd03522) | Apr 01, 2023 |
| Pegatron      | 2AC2                        | [ca0b0464d7](https://linux-hardware.org/?probe=ca0b0464d7) | Apr 01, 2023 |
| Dell          | 04YP6J A02                  | [0223f7bb3e](https://linux-hardware.org/?probe=0223f7bb3e) | Mar 31, 2023 |
| ECS           | GeForce 8000 series         | [32e951a2ca](https://linux-hardware.org/?probe=32e951a2ca) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [9e09a54915](https://linux-hardware.org/?probe=9e09a54915) | Mar 31, 2023 |
| HP            | 2AFA                        | [d177838277](https://linux-hardware.org/?probe=d177838277) | Mar 31, 2023 |
| ASRock        | Z87 Extreme6                | [675d214cbe](https://linux-hardware.org/?probe=675d214cbe) | Mar 31, 2023 |
| Dell          | 0JP3NX A00                  | [016632c560](https://linux-hardware.org/?probe=016632c560) | Mar 31, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [1ac381c18f](https://linux-hardware.org/?probe=1ac381c18f) | Mar 31, 2023 |
| MSI           | H81M-P33                    | [e2442d5cac](https://linux-hardware.org/?probe=e2442d5cac) | Mar 31, 2023 |
| Gigabyte      | Z77-DS3H                    | [79e2cfa0f1](https://linux-hardware.org/?probe=79e2cfa0f1) | Mar 31, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | [32c138c982](https://linux-hardware.org/?probe=32c138c982) | Mar 31, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [a025953f4c](https://linux-hardware.org/?probe=a025953f4c) | Mar 31, 2023 |
| Dell          | 0WMJ54 A00                  | [d11328af2a](https://linux-hardware.org/?probe=d11328af2a) | Mar 31, 2023 |
| MSI           | B550-A PRO                  | [ab4f36e0fa](https://linux-hardware.org/?probe=ab4f36e0fa) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [c27e3be5ba](https://linux-hardware.org/?probe=c27e3be5ba) | Mar 31, 2023 |
| Wistron       | ProLiant ML110 G5           | [925759c41c](https://linux-hardware.org/?probe=925759c41c) | Mar 31, 2023 |
| Dell          | 0HMX8D A01                  | [36b8532260](https://linux-hardware.org/?probe=36b8532260) | Mar 31, 2023 |
| MSI           | Z270-A PRO                  | [a5d218b9a6](https://linux-hardware.org/?probe=a5d218b9a6) | Mar 31, 2023 |
| Gigabyte      | Z68XP-UD3                   | [029afd6a5c](https://linux-hardware.org/?probe=029afd6a5c) | Mar 31, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | [fc9a42e387](https://linux-hardware.org/?probe=fc9a42e387) | Mar 31, 2023 |
| ASUSTek       | TUF Z270 MARK 2             | [6bd60aa5f0](https://linux-hardware.org/?probe=6bd60aa5f0) | Mar 31, 2023 |
| ASUSTek       | P8Z77-V                     | [498726ce78](https://linux-hardware.org/?probe=498726ce78) | Mar 31, 2023 |
| Dell          | 042P49 A02                  | [46dc3b9655](https://linux-hardware.org/?probe=46dc3b9655) | Mar 31, 2023 |
| Medion        | MS-7728                     | [cf66e81623](https://linux-hardware.org/?probe=cf66e81623) | Mar 31, 2023 |
| ASUSTek       | H110M-R                     | [bd1a48e47d](https://linux-hardware.org/?probe=bd1a48e47d) | Mar 31, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [7a0f5608b2](https://linux-hardware.org/?probe=7a0f5608b2) | Mar 31, 2023 |
| ASRock        | Z97 Anniversary             | [c23aeb60ba](https://linux-hardware.org/?probe=c23aeb60ba) | Mar 31, 2023 |
| HP            | 3397                        | [5a25984320](https://linux-hardware.org/?probe=5a25984320) | Mar 31, 2023 |
| Gigabyte      | B85M-HD3                    | [3d24b75a10](https://linux-hardware.org/?probe=3d24b75a10) | Mar 31, 2023 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [e84598d67c](https://linux-hardware.org/?probe=e84598d67c) | Mar 31, 2023 |
| Dell          | 00V62H A01                  | [05d42527df](https://linux-hardware.org/?probe=05d42527df) | Mar 31, 2023 |
| HP            | 1998                        | [c47c52dfc6](https://linux-hardware.org/?probe=c47c52dfc6) | Mar 31, 2023 |
| ASRock        | H61M                        | [29327171c4](https://linux-hardware.org/?probe=29327171c4) | Mar 31, 2023 |
| HP            | 8767 A                      | [186bad76b7](https://linux-hardware.org/?probe=186bad76b7) | Mar 31, 2023 |
| Gigabyte      | H310M A-CF                  | [c26786d423](https://linux-hardware.org/?probe=c26786d423) | Mar 31, 2023 |
| ASUSTek       | H97-PLUS                    | [5f163f6a24](https://linux-hardware.org/?probe=5f163f6a24) | Mar 31, 2023 |
| ASUSTek       | UN65U                       | [70d0f8f069](https://linux-hardware.org/?probe=70d0f8f069) | Mar 31, 2023 |
| Gigabyte      | EP43-DS3L                   | [b7594db73b](https://linux-hardware.org/?probe=b7594db73b) | Mar 31, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | [1fa3e0934f](https://linux-hardware.org/?probe=1fa3e0934f) | Mar 31, 2023 |
| ASUSTek       | PRIME J4005I-C              | [193d27ceac](https://linux-hardware.org/?probe=193d27ceac) | Mar 31, 2023 |
| MSI           | H110M PRO-VH PLUS           | [0992e2d8d8](https://linux-hardware.org/?probe=0992e2d8d8) | Mar 31, 2023 |
| OEM_MB        | NARRA3                      | [75050a4d2e](https://linux-hardware.org/?probe=75050a4d2e) | Mar 31, 2023 |
| ASUSTek       | M5A78L-M LX3                | [6ff0a3cb3f](https://linux-hardware.org/?probe=6ff0a3cb3f) | Mar 31, 2023 |
| Foxconn       | 2ABF                        | [8daf4bf0a5](https://linux-hardware.org/?probe=8daf4bf0a5) | Mar 30, 2023 |
| ASRock        | H310CM-HDV                  | [a9a41a38ed](https://linux-hardware.org/?probe=a9a41a38ed) | Mar 30, 2023 |
| ASUSTek       | PRIME A320M-K               | [3670f0a6ed](https://linux-hardware.org/?probe=3670f0a6ed) | Mar 30, 2023 |
| HP            | 843F                        | [862f573134](https://linux-hardware.org/?probe=862f573134) | Mar 30, 2023 |
| ASRock        | 970 Extreme3                | [906f9d6d04](https://linux-hardware.org/?probe=906f9d6d04) | Mar 30, 2023 |
| Gigabyte      | P41T-D3P                    | [c8cadc8a94](https://linux-hardware.org/?probe=c8cadc8a94) | Mar 30, 2023 |
| DFI           | LP UT X58                   | [cd706d90d3](https://linux-hardware.org/?probe=cd706d90d3) | Mar 30, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [d72978731a](https://linux-hardware.org/?probe=d72978731a) | Mar 30, 2023 |
| MSI           | Z370-A PRO                  | [9aba047596](https://linux-hardware.org/?probe=9aba047596) | Mar 30, 2023 |
| Gigabyte      | A520 AORUS ELITE            | [f7f74305ba](https://linux-hardware.org/?probe=f7f74305ba) | Mar 30, 2023 |
| Intel         | B75A                        | [b7b1423f34](https://linux-hardware.org/?probe=b7b1423f34) | Mar 30, 2023 |
| Biostar       | B550MX/E PRO                | [cffcb0a2a6](https://linux-hardware.org/?probe=cffcb0a2a6) | Mar 30, 2023 |
| Gigabyte      | H410M S2H V2                | [cf13162657](https://linux-hardware.org/?probe=cf13162657) | Mar 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ad1392d8c0](https://linux-hardware.org/?probe=ad1392d8c0) | Mar 30, 2023 |
| HP            | 82B4                        | [9712d04ab5](https://linux-hardware.org/?probe=9712d04ab5) | Mar 30, 2023 |
| Dell          | 0T7D40 A01                  | [dc44647f41](https://linux-hardware.org/?probe=dc44647f41) | Mar 30, 2023 |
| ASUSTek       | B85M-E                      | [7c7f9d0e36](https://linux-hardware.org/?probe=7c7f9d0e36) | Mar 30, 2023 |
| Packard Be... | FIH57                       | [f1336c6cc4](https://linux-hardware.org/?probe=f1336c6cc4) | Mar 30, 2023 |
| Pegatron      | 2ADC                        | [1326ad508e](https://linux-hardware.org/?probe=1326ad508e) | Mar 30, 2023 |
| Packard Be... | MCP73PV                     | [2082d90602](https://linux-hardware.org/?probe=2082d90602) | Mar 30, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [4ccaa78b43](https://linux-hardware.org/?probe=4ccaa78b43) | Mar 30, 2023 |
| MSI           | B450M BAZOOKA V2            | [7888e091f7](https://linux-hardware.org/?probe=7888e091f7) | Mar 30, 2023 |
| Gigabyte      | GA-880GA-UD3H               | [393fc00a5d](https://linux-hardware.org/?probe=393fc00a5d) | Mar 30, 2023 |
| Medion        | B250H4-EM                   | [f569d44749](https://linux-hardware.org/?probe=f569d44749) | Mar 30, 2023 |
| ASUSTek       | P8H77-V                     | [1869e23c56](https://linux-hardware.org/?probe=1869e23c56) | Mar 30, 2023 |
| MSI           | H97 PC Mate                 | [37c098e51a](https://linux-hardware.org/?probe=37c098e51a) | Mar 30, 2023 |
| Gigabyte      | Z390 UD                     | [558d551d9a](https://linux-hardware.org/?probe=558d551d9a) | Mar 30, 2023 |
| ASRock        | B85M Pro4                   | [d237bcc0a2](https://linux-hardware.org/?probe=d237bcc0a2) | Mar 30, 2023 |
| Gigabyte      | B75M-D3V                    | [d3ae118e3b](https://linux-hardware.org/?probe=d3ae118e3b) | Mar 30, 2023 |
| Shuttle       | FH270                       | [83c990d212](https://linux-hardware.org/?probe=83c990d212) | Mar 30, 2023 |
| MSI           | H81M-P33                    | [4606b5b93d](https://linux-hardware.org/?probe=4606b5b93d) | Mar 29, 2023 |
| Dell          | 042P49 A01                  | [9a4f4be1ab](https://linux-hardware.org/?probe=9a4f4be1ab) | Mar 29, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [fb2605e6fa](https://linux-hardware.org/?probe=fb2605e6fa) | Mar 29, 2023 |
| Dell          | 0TP412                      | [f9f3e5cc04](https://linux-hardware.org/?probe=f9f3e5cc04) | Mar 29, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [599577c3b4](https://linux-hardware.org/?probe=599577c3b4) | Mar 29, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [3b7fe31c07](https://linux-hardware.org/?probe=3b7fe31c07) | Mar 29, 2023 |
| EPoX Compu... | nForce3 DDR: 8KDA7I Seri... | [38e3c2378c](https://linux-hardware.org/?probe=38e3c2378c) | Mar 29, 2023 |
| Dell          | 0T2HR0 A02                  | [bf959f65d2](https://linux-hardware.org/?probe=bf959f65d2) | Mar 29, 2023 |
| Gigabyte      | B550M DS3H                  | [612dd1dba2](https://linux-hardware.org/?probe=612dd1dba2) | Mar 29, 2023 |
| Lenovo        | 30D2 NOK                    | [e4d898e37d](https://linux-hardware.org/?probe=e4d898e37d) | Mar 29, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [634c2e1e74](https://linux-hardware.org/?probe=634c2e1e74) | Mar 29, 2023 |
| ASRock        | B450 Pro4                   | [c77fc70f0c](https://linux-hardware.org/?probe=c77fc70f0c) | Mar 29, 2023 |
| Acer          | Predator G3-605             | [8a1a55a1da](https://linux-hardware.org/?probe=8a1a55a1da) | Mar 29, 2023 |
| HP            | 0A60h                       | [6ad65f4f2b](https://linux-hardware.org/?probe=6ad65f4f2b) | Mar 28, 2023 |
| WinFast       | 6100M2MA FAB1.0             | [bed481b8ce](https://linux-hardware.org/?probe=bed481b8ce) | Mar 28, 2023 |
| HP            | 3047h                       | [c4f4f0c51d](https://linux-hardware.org/?probe=c4f4f0c51d) | Mar 28, 2023 |
| ASRock        | J5040-ITX                   | [799a14a5d5](https://linux-hardware.org/?probe=799a14a5d5) | Mar 28, 2023 |
| MSI           | B450-A PRO MAX              | [f3ebf80a3d](https://linux-hardware.org/?probe=f3ebf80a3d) | Mar 28, 2023 |
| Gigabyte      | H310M S2 x.x                | [21504643b4](https://linux-hardware.org/?probe=21504643b4) | Mar 28, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [4807db08a9](https://linux-hardware.org/?probe=4807db08a9) | Mar 28, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [ad5969356b](https://linux-hardware.org/?probe=ad5969356b) | Mar 28, 2023 |
| Gigabyte      | GA-780T-D3L                 | [4f523c6409](https://linux-hardware.org/?probe=4f523c6409) | Mar 28, 2023 |
| Lenovo        | 3178 SDK0J40700 WIN 3258... | [1c14b29af5](https://linux-hardware.org/?probe=1c14b29af5) | Mar 28, 2023 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | [16db0eb166](https://linux-hardware.org/?probe=16db0eb166) | Mar 28, 2023 |
| ASUSTek       | P5G41T-M LX                 | [3f2f66842c](https://linux-hardware.org/?probe=3f2f66842c) | Mar 28, 2023 |
| Gigabyte      | H61M-S2P-R3                 | [428dc61d58](https://linux-hardware.org/?probe=428dc61d58) | Mar 28, 2023 |
| Dell          | 0R5KF8 A03                  | [decf0f5193](https://linux-hardware.org/?probe=decf0f5193) | Mar 28, 2023 |
| Gigabyte      | H55M-USB3                   | [140b984b9f](https://linux-hardware.org/?probe=140b984b9f) | Mar 28, 2023 |
| Lenovo        | NO DPK                      | [220c640743](https://linux-hardware.org/?probe=220c640743) | Mar 28, 2023 |
| MSI           | H87-G41 PC Mate             | [0d1345af82](https://linux-hardware.org/?probe=0d1345af82) | Mar 28, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [8e7d5a0eb8](https://linux-hardware.org/?probe=8e7d5a0eb8) | Mar 28, 2023 |
| Lenovo        | ThinkStation S30 0568E8G    | [ea3855cca5](https://linux-hardware.org/?probe=ea3855cca5) | Mar 28, 2023 |
| Lenovo        | SHARKBAY 31900058 STD       | [5064a5267e](https://linux-hardware.org/?probe=5064a5267e) | Mar 28, 2023 |
| ASRock        | X470 Taichi                 | [79d0ee9715](https://linux-hardware.org/?probe=79d0ee9715) | Mar 28, 2023 |
| ASUSTek       | PRIME X570-P                | [8234cd55a8](https://linux-hardware.org/?probe=8234cd55a8) | Mar 28, 2023 |
| Intel         | H61                         | [56437a0e05](https://linux-hardware.org/?probe=56437a0e05) | Mar 28, 2023 |
| Gigabyte      | H61M-S1                     | [9af85c78cb](https://linux-hardware.org/?probe=9af85c78cb) | Mar 28, 2023 |
| Gigabyte      | A320M-H-CF                  | [6b4122e888](https://linux-hardware.org/?probe=6b4122e888) | Mar 28, 2023 |
| Lenovo        | 0x36A017AA SDK0J40709 WI... | [562426633d](https://linux-hardware.org/?probe=562426633d) | Mar 28, 2023 |
| ASUSTek       | Z170-P                      | [03e9908048](https://linux-hardware.org/?probe=03e9908048) | Mar 28, 2023 |
| Dell          | 0G261D A00                  | [f63f67f28f](https://linux-hardware.org/?probe=f63f67f28f) | Mar 28, 2023 |
| Acer          | Predator G3-605             | [8caea0f833](https://linux-hardware.org/?probe=8caea0f833) | Mar 27, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [face5f2ef3](https://linux-hardware.org/?probe=face5f2ef3) | Mar 27, 2023 |
| ASRock        | Z77 Extreme6                | [365cc196f2](https://linux-hardware.org/?probe=365cc196f2) | Mar 27, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | [91a63afb10](https://linux-hardware.org/?probe=91a63afb10) | Mar 27, 2023 |
| Gigabyte      | B450M S2H                   | [0901eb1e27](https://linux-hardware.org/?probe=0901eb1e27) | Mar 27, 2023 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | [8d039976c9](https://linux-hardware.org/?probe=8d039976c9) | Mar 27, 2023 |
| Pegatron      | 2AD5                        | [502ff745d4](https://linux-hardware.org/?probe=502ff745d4) | Mar 27, 2023 |
| ASUSTek       | PRIME Z590-P                | [ab55adbf68](https://linux-hardware.org/?probe=ab55adbf68) | Mar 27, 2023 |
| Gigabyte      | H81M-H                      | [709242697d](https://linux-hardware.org/?probe=709242697d) | Mar 27, 2023 |
| HP            | 1998                        | [82adc9926e](https://linux-hardware.org/?probe=82adc9926e) | Mar 27, 2023 |
| Dell          | 0G919G A00                  | [139207e1a7](https://linux-hardware.org/?probe=139207e1a7) | Mar 27, 2023 |
| Lenovo        | 102F NO DPK                 | [85a4bbf301](https://linux-hardware.org/?probe=85a4bbf301) | Mar 27, 2023 |
| ASUSTek       | P7H55                       | [40158bca43](https://linux-hardware.org/?probe=40158bca43) | Mar 27, 2023 |
| Gigabyte      | H310M H                     | [16ba0fa199](https://linux-hardware.org/?probe=16ba0fa199) | Mar 27, 2023 |
| Lenovo        | ThinkCentre M71e 3157AE2    | [a71ced0077](https://linux-hardware.org/?probe=a71ced0077) | Mar 27, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [bcd49e85cb](https://linux-hardware.org/?probe=bcd49e85cb) | Mar 27, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | [fa7272f576](https://linux-hardware.org/?probe=fa7272f576) | Mar 27, 2023 |
| ASRock        | A320M-HDV                   | [9685e81600](https://linux-hardware.org/?probe=9685e81600) | Mar 27, 2023 |
| Gigabyte      | H87M-D3H                    | [b277bc971f](https://linux-hardware.org/?probe=b277bc971f) | Mar 27, 2023 |
| Acer          | Veriton M4630G V:1.0        | [7fba52ef43](https://linux-hardware.org/?probe=7fba52ef43) | Mar 27, 2023 |
| ASUSTek       | P8Z77-V LK                  | [6b088adaf9](https://linux-hardware.org/?probe=6b088adaf9) | Mar 27, 2023 |
| Lenovo        | 36EB SDK0R32862 WIN 3258... | [943075edf7](https://linux-hardware.org/?probe=943075edf7) | Mar 27, 2023 |
| ASRock        | B450M Pro4                  | [a6bb6f959c](https://linux-hardware.org/?probe=a6bb6f959c) | Mar 27, 2023 |
| Unknown       | Unknown                     | [ecf55ab179](https://linux-hardware.org/?probe=ecf55ab179) | Mar 27, 2023 |
| Gigabyte      | G31M-ES2C                   | [fcd077e70a](https://linux-hardware.org/?probe=fcd077e70a) | Mar 27, 2023 |
| HP            | 844C                        | [8270d682a8](https://linux-hardware.org/?probe=8270d682a8) | Mar 27, 2023 |
| Unknown       | 1.0                         | [e09cc1385b](https://linux-hardware.org/?probe=e09cc1385b) | Mar 27, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [8af0f96567](https://linux-hardware.org/?probe=8af0f96567) | Mar 27, 2023 |
| ASUSTek       | P8H61-MX R2.0               | [9064f6704d](https://linux-hardware.org/?probe=9064f6704d) | Mar 27, 2023 |
| ASUSTek       | Z97-K R2.0                  | [b1e1f4d711](https://linux-hardware.org/?probe=b1e1f4d711) | Mar 27, 2023 |
| MSI           | H410M PRO-C                 | [95cb5acf9e](https://linux-hardware.org/?probe=95cb5acf9e) | Mar 27, 2023 |
| Dell          | 01TJ2K A03                  | [f390eb34f6](https://linux-hardware.org/?probe=f390eb34f6) | Mar 27, 2023 |
| ASUSTek       | PRIME B450M-A               | [2077f4f3ab](https://linux-hardware.org/?probe=2077f4f3ab) | Mar 27, 2023 |
| HP            | 1998                        | [2d5e0737e5](https://linux-hardware.org/?probe=2d5e0737e5) | Mar 27, 2023 |
| ASUSTek       | M4A78-HTPC                  | [be398d5786](https://linux-hardware.org/?probe=be398d5786) | Mar 27, 2023 |
| HP            | 8704                        | [ab934a36cb](https://linux-hardware.org/?probe=ab934a36cb) | Mar 26, 2023 |
| Gigabyte      | B85M-HD3                    | [36c8e41310](https://linux-hardware.org/?probe=36c8e41310) | Mar 26, 2023 |
| Fujitsu Si... | MS-7504VP-PV                | [83448b2d9b](https://linux-hardware.org/?probe=83448b2d9b) | Mar 26, 2023 |
| ASUSTek       | PRIME A320M-K               | [8d0ef2d912](https://linux-hardware.org/?probe=8d0ef2d912) | Mar 26, 2023 |
| ASRock        | X300-ITX                    | [34402bbf9b](https://linux-hardware.org/?probe=34402bbf9b) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [8decb2b6c4](https://linux-hardware.org/?probe=8decb2b6c4) | Mar 26, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [bf08e5eecd](https://linux-hardware.org/?probe=bf08e5eecd) | Mar 26, 2023 |
| Medion        | P2A4-EM                     | [45e86dd60d](https://linux-hardware.org/?probe=45e86dd60d) | Mar 26, 2023 |
| ASUSTek       | P8H67                       | [3b9e638ecb](https://linux-hardware.org/?probe=3b9e638ecb) | Mar 26, 2023 |
| PCWare        | IPMH61R3                    | [2fbd1f3f64](https://linux-hardware.org/?probe=2fbd1f3f64) | Mar 26, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [b527095c8c](https://linux-hardware.org/?probe=b527095c8c) | Mar 26, 2023 |
| Chuwi         | RZBOX                       | [14ef8add03](https://linux-hardware.org/?probe=14ef8add03) | Mar 26, 2023 |
| ASUSTek       | PRIME H510M-K               | [54e2f18738](https://linux-hardware.org/?probe=54e2f18738) | Mar 26, 2023 |
| ASUSTek       | PRIME A520M-K               | [f01520e14a](https://linux-hardware.org/?probe=f01520e14a) | Mar 26, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | [0730a39a3a](https://linux-hardware.org/?probe=0730a39a3a) | Mar 26, 2023 |
| Lenovo        | ThinkCentre M58p 6137A2U    | [cc740804d7](https://linux-hardware.org/?probe=cc740804d7) | Mar 25, 2023 |
| ASUSTek       | P8H77-M                     | [6fc56d2339](https://linux-hardware.org/?probe=6fc56d2339) | Mar 25, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [e6219e18b1](https://linux-hardware.org/?probe=e6219e18b1) | Mar 25, 2023 |
| HP            | 8433 11                     | [1f76e1dc62](https://linux-hardware.org/?probe=1f76e1dc62) | Mar 25, 2023 |
| MSI           | A520M PRO                   | [c27ea21be5](https://linux-hardware.org/?probe=c27ea21be5) | Mar 25, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [3ce94dae13](https://linux-hardware.org/?probe=3ce94dae13) | Mar 25, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [76d02ffbf0](https://linux-hardware.org/?probe=76d02ffbf0) | Mar 25, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [227aba28f2](https://linux-hardware.org/?probe=227aba28f2) | Mar 25, 2023 |
| Dell          | 0654JC A01                  | [3771b8bf2e](https://linux-hardware.org/?probe=3771b8bf2e) | Mar 25, 2023 |
| Gigabyte      | F2A78M-HD2                  | [c7bf2c9968](https://linux-hardware.org/?probe=c7bf2c9968) | Mar 25, 2023 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | [ca8bcc6073](https://linux-hardware.org/?probe=ca8bcc6073) | Mar 25, 2023 |
| Gigabyte      | H310N                       | [33a905038c](https://linux-hardware.org/?probe=33a905038c) | Mar 24, 2023 |
| HP            | 212A                        | [df28b0fdb0](https://linux-hardware.org/?probe=df28b0fdb0) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [5c811e496f](https://linux-hardware.org/?probe=5c811e496f) | Mar 24, 2023 |
| Gigabyte      | M52S-S3P                    | [c9ac6eb940](https://linux-hardware.org/?probe=c9ac6eb940) | Mar 24, 2023 |
| Gigabyte      | H410M S2                    | [08b36ebc25](https://linux-hardware.org/?probe=08b36ebc25) | Mar 24, 2023 |
| Lenovo        | SDK0E50519 WIN              | [2fb6bb5874](https://linux-hardware.org/?probe=2fb6bb5874) | Mar 24, 2023 |
| Dell          | 0NK5PH A00                  | [f76bc64ee4](https://linux-hardware.org/?probe=f76bc64ee4) | Mar 24, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [b03324de35](https://linux-hardware.org/?probe=b03324de35) | Mar 24, 2023 |
| ASUSTek       | M4N98TD EVO                 | [9cb4b84924](https://linux-hardware.org/?probe=9cb4b84924) | Mar 24, 2023 |
| Intel         | HURONRIVER                  | [5bac43b2f0](https://linux-hardware.org/?probe=5bac43b2f0) | Mar 24, 2023 |
| ASUSTek       | GRYPHON Z87                 | [befbe47acc](https://linux-hardware.org/?probe=befbe47acc) | Mar 23, 2023 |
| HP            | 1497                        | [2238b69c99](https://linux-hardware.org/?probe=2238b69c99) | Mar 23, 2023 |
| Dell          | 0NDYHG A01                  | [93bc601af0](https://linux-hardware.org/?probe=93bc601af0) | Mar 23, 2023 |
| Biostar       | G41D3+                      | [ebb9a17568](https://linux-hardware.org/?probe=ebb9a17568) | Mar 23, 2023 |
| Gigabyte      | H61M-DS2                    | [fba2a4dffc](https://linux-hardware.org/?probe=fba2a4dffc) | Mar 23, 2023 |
| MSI           | MS-7255                     | [7322068101](https://linux-hardware.org/?probe=7322068101) | Mar 23, 2023 |
| Digiboard     | NM70-TI                     | [d654b9738a](https://linux-hardware.org/?probe=d654b9738a) | Mar 23, 2023 |
| ASRock        | H61M-HVGS                   | [5e9cf8fb44](https://linux-hardware.org/?probe=5e9cf8fb44) | Mar 22, 2023 |
| HP            | 339A                        | [a09a5bd5a9](https://linux-hardware.org/?probe=a09a5bd5a9) | Mar 22, 2023 |
| HP            | 802F                        | [89dadeeea6](https://linux-hardware.org/?probe=89dadeeea6) | Mar 22, 2023 |
| BESSTAR Te... | UM700                       | [32116dbba8](https://linux-hardware.org/?probe=32116dbba8) | Mar 21, 2023 |
| MSI           | B450M PRO-M2 MAX            | [bdfe7a3498](https://linux-hardware.org/?probe=bdfe7a3498) | Mar 21, 2023 |
| Dell          | 0NK70N A03                  | [7c5f606c7d](https://linux-hardware.org/?probe=7c5f606c7d) | Mar 21, 2023 |
| Gigabyte      | B75N                        | [8a16ffed3b](https://linux-hardware.org/?probe=8a16ffed3b) | Mar 21, 2023 |
| Dell          | 0C2KJT A00                  | [54bdc4bbd0](https://linux-hardware.org/?probe=54bdc4bbd0) | Mar 21, 2023 |
| Dell          | 0D441T A03                  | [926d18b722](https://linux-hardware.org/?probe=926d18b722) | Mar 20, 2023 |
| Gigabyte      | A520I AC                    | [a9e094374a](https://linux-hardware.org/?probe=a9e094374a) | Mar 20, 2023 |
| Gigabyte      | GA-990FX-GAMING             | [7f1e3cf271](https://linux-hardware.org/?probe=7f1e3cf271) | Mar 20, 2023 |
| Dell          | 0F6X5P A00                  | [258c8aa62c](https://linux-hardware.org/?probe=258c8aa62c) | Mar 20, 2023 |
| Acer          | Veriton M4610G              | [fed7efcecb](https://linux-hardware.org/?probe=fed7efcecb) | Mar 20, 2023 |
| Gigabyte      | Z68A-D3H-B3                 | [6c420d8fba](https://linux-hardware.org/?probe=6c420d8fba) | Mar 20, 2023 |
| Gigabyte      | P43-ES3G                    | [60a7dc4c2e](https://linux-hardware.org/?probe=60a7dc4c2e) | Mar 20, 2023 |
| Unknown       | Unknown                     | [dfcc73f24d](https://linux-hardware.org/?probe=dfcc73f24d) | Mar 20, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [db3e17d5f1](https://linux-hardware.org/?probe=db3e17d5f1) | Mar 20, 2023 |
| ASUSTek       | PRIME B350M-A               | [9ee81ffe32](https://linux-hardware.org/?probe=9ee81ffe32) | Mar 20, 2023 |
| ASUSTek       | PRIME H510M-E               | [8c46e42391](https://linux-hardware.org/?probe=8c46e42391) | Mar 20, 2023 |
| ASRock        | 970A-G                      | [52b0aa69ba](https://linux-hardware.org/?probe=52b0aa69ba) | Mar 20, 2023 |
| HP            | 18E7                        | [9e4b5010d8](https://linux-hardware.org/?probe=9e4b5010d8) | Mar 20, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [32d80303b6](https://linux-hardware.org/?probe=32d80303b6) | Mar 20, 2023 |
| HP            | 3646h                       | [812e12695b](https://linux-hardware.org/?probe=812e12695b) | Mar 19, 2023 |
| ASRock        | G31M-GS                     | [abef6c6862](https://linux-hardware.org/?probe=abef6c6862) | Mar 19, 2023 |
| ASUSTek       | M51BC                       | [65db0797b0](https://linux-hardware.org/?probe=65db0797b0) | Mar 19, 2023 |
| Gigabyte      | A520M H                     | [a3cee7c278](https://linux-hardware.org/?probe=a3cee7c278) | Mar 19, 2023 |
| Gigabyte      | 990FXA-UD5                  | [0daa99f732](https://linux-hardware.org/?probe=0daa99f732) | Mar 19, 2023 |
| ASUSTek       | P8H61-M LX PLUS             | [cdf57a039e](https://linux-hardware.org/?probe=cdf57a039e) | Mar 19, 2023 |
| HP            | 3397                        | [3f0b2c8e5b](https://linux-hardware.org/?probe=3f0b2c8e5b) | Mar 19, 2023 |
| Dell          | 0MM599                      | [df3a1bd31b](https://linux-hardware.org/?probe=df3a1bd31b) | Mar 18, 2023 |
| Intel         | H55                         | [2b6fdbe93c](https://linux-hardware.org/?probe=2b6fdbe93c) | Mar 18, 2023 |
| Gigabyte      | 970A-DS3P                   | [727e5c46b7](https://linux-hardware.org/?probe=727e5c46b7) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [d8004fdcde](https://linux-hardware.org/?probe=d8004fdcde) | Mar 18, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [2a1291ac22](https://linux-hardware.org/?probe=2a1291ac22) | Mar 18, 2023 |
| Dell          | 07N90W A02                  | [267dad60ba](https://linux-hardware.org/?probe=267dad60ba) | Mar 18, 2023 |
| MSI           | H55M-P31                    | [e95e62df99](https://linux-hardware.org/?probe=e95e62df99) | Mar 18, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [b346ffbe8e](https://linux-hardware.org/?probe=b346ffbe8e) | Mar 18, 2023 |
| MSI           | MS-7360                     | [6c8cb5d98f](https://linux-hardware.org/?probe=6c8cb5d98f) | Mar 18, 2023 |
| HP            | 1589                        | [5c483a16fc](https://linux-hardware.org/?probe=5c483a16fc) | Mar 18, 2023 |
| Unknown       | Unknown                     | [d91eb1923c](https://linux-hardware.org/?probe=d91eb1923c) | Mar 17, 2023 |
| Medion        | H81H3-EM2 H81EM2W08.217     | [1e1a430355](https://linux-hardware.org/?probe=1e1a430355) | Mar 17, 2023 |
| Gigabyte      | G41MT-D3                    | [9a4ac88209](https://linux-hardware.org/?probe=9a4ac88209) | Mar 17, 2023 |
| Dell          | 0HN7XN A01                  | [4ce2092fe2](https://linux-hardware.org/?probe=4ce2092fe2) | Mar 17, 2023 |
| Gigabyte      | G41MT-S2P                   | [abb09d2f8e](https://linux-hardware.org/?probe=abb09d2f8e) | Mar 17, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | [452349c032](https://linux-hardware.org/?probe=452349c032) | Mar 17, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | [0125449b9f](https://linux-hardware.org/?probe=0125449b9f) | Mar 17, 2023 |
| Dell          | 0T1D10 A01                  | [c640b09a8b](https://linux-hardware.org/?probe=c640b09a8b) | Mar 17, 2023 |
| Lenovo        | ThinkCentre A58 7522M4J     | [ba0a303be5](https://linux-hardware.org/?probe=ba0a303be5) | Mar 17, 2023 |
| ASUSTek       | P7H55-M PRO                 | [0c7a43b36b](https://linux-hardware.org/?probe=0c7a43b36b) | Mar 17, 2023 |
| Acer          | Batman A01                  | [0d7671ef18](https://linux-hardware.org/?probe=0d7671ef18) | Mar 17, 2023 |
| Fujitsu       | D3012-A1 S26361-D3012-A1    | [14c33dda50](https://linux-hardware.org/?probe=14c33dda50) | Mar 16, 2023 |
| ASUSTek       | P5W DH Deluxe               | [761d6accb1](https://linux-hardware.org/?probe=761d6accb1) | Mar 16, 2023 |
| Pegatron      | 2AB5                        | [7ab2e7b0ab](https://linux-hardware.org/?probe=7ab2e7b0ab) | Mar 16, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [293b961af2](https://linux-hardware.org/?probe=293b961af2) | Mar 16, 2023 |
| ASUSTek       | CG5290                      | [e0ab58dbfe](https://linux-hardware.org/?probe=e0ab58dbfe) | Mar 16, 2023 |
| ASUSTek       | P5QPL-AM                    | [e89d2059c0](https://linux-hardware.org/?probe=e89d2059c0) | Mar 16, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [c7a98e4c15](https://linux-hardware.org/?probe=c7a98e4c15) | Mar 16, 2023 |
| OEM           | B85 JHS359                  | [1d5d7e95fc](https://linux-hardware.org/?probe=1d5d7e95fc) | Mar 16, 2023 |
| HP            | 8299                        | [59417ae66d](https://linux-hardware.org/?probe=59417ae66d) | Mar 16, 2023 |
| Acer          | FIH57                       | [ee8c95f841](https://linux-hardware.org/?probe=ee8c95f841) | Mar 16, 2023 |
| Biostar       | A10N-8800E                  | [1f081ed675](https://linux-hardware.org/?probe=1f081ed675) | Mar 16, 2023 |
| HP            | 0B40h                       | [b26ab9fc5d](https://linux-hardware.org/?probe=b26ab9fc5d) | Mar 16, 2023 |
| Intel         | Unknown                     | [b4b73aafa0](https://linux-hardware.org/?probe=b4b73aafa0) | Mar 15, 2023 |
| ASUSTek       | P9X79-E WS                  | [e16021b874](https://linux-hardware.org/?probe=e16021b874) | Mar 15, 2023 |
| Pegatron      | 2ACF                        | [7e97ed3ca3](https://linux-hardware.org/?probe=7e97ed3ca3) | Mar 15, 2023 |
| ASUSTek       | VC62B                       | [9bf2d226a8](https://linux-hardware.org/?probe=9bf2d226a8) | Mar 15, 2023 |
| Gigabyte      | B550 VISION D-P             | [4707dc8ed6](https://linux-hardware.org/?probe=4707dc8ed6) | Mar 15, 2023 |
| PCWare        | IPX4105G Pro                | [f685771047](https://linux-hardware.org/?probe=f685771047) | Mar 15, 2023 |
| Dell          | 0773VG A00                  | [320dab99e7](https://linux-hardware.org/?probe=320dab99e7) | Mar 15, 2023 |
| ASUSTek       | M5A88-M                     | [4b1712febb](https://linux-hardware.org/?probe=4b1712febb) | Mar 15, 2023 |
| MSI           | H61M-P20                    | [8129a4f5a4](https://linux-hardware.org/?probe=8129a4f5a4) | Mar 15, 2023 |
| MSI           | FM2-A55M-E33                | [d6106fe9e3](https://linux-hardware.org/?probe=d6106fe9e3) | Mar 14, 2023 |
| ASRock        | A320M-HDV R4.0              | [723cb09007](https://linux-hardware.org/?probe=723cb09007) | Mar 14, 2023 |
| Packard Be... | IMEDIA S3840                | [b54abceafe](https://linux-hardware.org/?probe=b54abceafe) | Mar 14, 2023 |
| ASUSTek       | P5KR                        | [613bbd6934](https://linux-hardware.org/?probe=613bbd6934) | Mar 14, 2023 |
| ASRock        | G31M-S                      | [7672cc15a2](https://linux-hardware.org/?probe=7672cc15a2) | Mar 13, 2023 |
| ASUSTek       | B75M-A                      | [8ca3a8801d](https://linux-hardware.org/?probe=8ca3a8801d) | Mar 13, 2023 |
| ASUSTek       | PRIME X370-PRO              | [05da6b812c](https://linux-hardware.org/?probe=05da6b812c) | Mar 13, 2023 |
| Pegatron      | 2AB6                        | [8feb2e38c0](https://linux-hardware.org/?probe=8feb2e38c0) | Mar 13, 2023 |
| ASUSTek       | PRIME H410M-A               | [1f67ba4519](https://linux-hardware.org/?probe=1f67ba4519) | Mar 13, 2023 |
| HP            | 8767 A                      | [1e76ecbaa7](https://linux-hardware.org/?probe=1e76ecbaa7) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H-A                  | [4265744c52](https://linux-hardware.org/?probe=4265744c52) | Mar 12, 2023 |
| Dell          | 00V62H A01                  | [a45ebd1b85](https://linux-hardware.org/?probe=a45ebd1b85) | Mar 12, 2023 |
| HP            | 1998                        | [68d7c4350d](https://linux-hardware.org/?probe=68d7c4350d) | Mar 12, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [964377c32c](https://linux-hardware.org/?probe=964377c32c) | Mar 12, 2023 |
| Pegatron      | 2AC2                        | [a6084e8904](https://linux-hardware.org/?probe=a6084e8904) | Mar 11, 2023 |
| ASUSTek       | A88X-PLUS                   | [3624df5386](https://linux-hardware.org/?probe=3624df5386) | Mar 11, 2023 |
| ASUSTek       | PRIME Z270-P                | [8f2b6b3bc1](https://linux-hardware.org/?probe=8f2b6b3bc1) | Mar 11, 2023 |
| Gigabyte      | H81M-H                      | [fd3c999c22](https://linux-hardware.org/?probe=fd3c999c22) | Mar 11, 2023 |
| Gigabyte      | P55-UD3R                    | [e720741a00](https://linux-hardware.org/?probe=e720741a00) | Mar 11, 2023 |
| HP            | 8433 11                     | [51a4dbf83e](https://linux-hardware.org/?probe=51a4dbf83e) | Mar 11, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | [c5950249eb](https://linux-hardware.org/?probe=c5950249eb) | Mar 11, 2023 |
| Gigabyte      | 970A-UD3P                   | [2da8e75f5c](https://linux-hardware.org/?probe=2da8e75f5c) | Mar 11, 2023 |
| ASUSTek       | P7P55D DELUXE               | [d2b402f3c0](https://linux-hardware.org/?probe=d2b402f3c0) | Mar 11, 2023 |
| MSI           | Z170-A PRO                  | [a83243223a](https://linux-hardware.org/?probe=a83243223a) | Mar 10, 2023 |
| MSI           | A68HM-E33 V2                | [7cad3dc309](https://linux-hardware.org/?probe=7cad3dc309) | Mar 10, 2023 |
| MSI           | G31TM-P21                   | [262750077e](https://linux-hardware.org/?probe=262750077e) | Mar 10, 2023 |
| HP            | 0AA0h                       | [f86f0bc187](https://linux-hardware.org/?probe=f86f0bc187) | Mar 10, 2023 |
| Dell          | 0G2DM9 A02                  | [e6d8fa1563](https://linux-hardware.org/?probe=e6d8fa1563) | Mar 10, 2023 |
| Acer          | Veriton X4640G V:1.1        | [dd3e15feee](https://linux-hardware.org/?probe=dd3e15feee) | Mar 10, 2023 |
| HP            | 1850                        | [1b56ff36d2](https://linux-hardware.org/?probe=1b56ff36d2) | Mar 10, 2023 |
| Gigabyte      | B450M DS3H-CF               | [bf4c797c87](https://linux-hardware.org/?probe=bf4c797c87) | Mar 10, 2023 |
| Inventec      | D CLASS A02                 | [b9e49da1f7](https://linux-hardware.org/?probe=b9e49da1f7) | Mar 10, 2023 |
| MSI           | 970A-G46                    | [322eb2bdf0](https://linux-hardware.org/?probe=322eb2bdf0) | Mar 09, 2023 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [fcb5d30135](https://linux-hardware.org/?probe=fcb5d30135) | Mar 09, 2023 |
| ASRock        | H61M-ITX                    | [ab7e81c6ca](https://linux-hardware.org/?probe=ab7e81c6ca) | Mar 09, 2023 |
| ASRock        | A320M-DVS R4.0              | [8e02302d63](https://linux-hardware.org/?probe=8e02302d63) | Mar 09, 2023 |
| Gigabyte      | GA-M55PLUS-S3G              | [dfd0b3e3de](https://linux-hardware.org/?probe=dfd0b3e3de) | Mar 08, 2023 |
| ASUSTek       | P5W DH Deluxe               | [df3b5da4ce](https://linux-hardware.org/?probe=df3b5da4ce) | Mar 08, 2023 |
| Lenovo        | MAHOBAY                     | [c756678fad](https://linux-hardware.org/?probe=c756678fad) | Mar 08, 2023 |
| ASUSTek       | B85M-G                      | [70f4bed81b](https://linux-hardware.org/?probe=70f4bed81b) | Mar 08, 2023 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | [b1a69ac03b](https://linux-hardware.org/?probe=b1a69ac03b) | Mar 08, 2023 |
| ECS           | MCP61PM-GM                  | [ac561937e3](https://linux-hardware.org/?probe=ac561937e3) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [971feb34e4](https://linux-hardware.org/?probe=971feb34e4) | Mar 07, 2023 |
| Dell          | 0T1D10 A01                  | [ef67915ff3](https://linux-hardware.org/?probe=ef67915ff3) | Mar 07, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [c5809ffd96](https://linux-hardware.org/?probe=c5809ffd96) | Mar 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | [c6f9f5a58d](https://linux-hardware.org/?probe=c6f9f5a58d) | Mar 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | [349f7731c8](https://linux-hardware.org/?probe=349f7731c8) | Mar 06, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | [0c133c161b](https://linux-hardware.org/?probe=0c133c161b) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [98f8bd8557](https://linux-hardware.org/?probe=98f8bd8557) | Mar 06, 2023 |
| ASUSTek       | PRIME A320M-K               | [38cb86265f](https://linux-hardware.org/?probe=38cb86265f) | Mar 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | [0cda9f83b1](https://linux-hardware.org/?probe=0cda9f83b1) | Mar 06, 2023 |
| Gigabyte      | P35-DS3L                    | [31aeecfcb9](https://linux-hardware.org/?probe=31aeecfcb9) | Mar 06, 2023 |
| ASUSTek       | PRIME X370-PRO              | [9b72e94139](https://linux-hardware.org/?probe=9b72e94139) | Mar 06, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | [2891c31951](https://linux-hardware.org/?probe=2891c31951) | Mar 06, 2023 |
| MSI           | H110M PRO-VH PLUS           | [e4e66a8215](https://linux-hardware.org/?probe=e4e66a8215) | Mar 06, 2023 |
| Dell          | 06D7TR A00                  | [375809fb93](https://linux-hardware.org/?probe=375809fb93) | Mar 06, 2023 |
| Dell          | 0VRWRC A00                  | [4810cd01e3](https://linux-hardware.org/?probe=4810cd01e3) | Mar 06, 2023 |
| HP            | 212A                        | [faacd553af](https://linux-hardware.org/?probe=faacd553af) | Mar 06, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | [c89683aeed](https://linux-hardware.org/?probe=c89683aeed) | Mar 06, 2023 |
| Gigabyte      | B450M GAMING                | [168b8db115](https://linux-hardware.org/?probe=168b8db115) | Mar 06, 2023 |
| Gigabyte      | B450M S2H V2                | [a2242be67c](https://linux-hardware.org/?probe=a2242be67c) | Mar 05, 2023 |
| Gigabyte      | H370 HD3-CF                 | [30365cbef7](https://linux-hardware.org/?probe=30365cbef7) | Mar 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [91fc2d53f8](https://linux-hardware.org/?probe=91fc2d53f8) | Mar 05, 2023 |
| MSI           | MS-6702E                    | [e17662e6c0](https://linux-hardware.org/?probe=e17662e6c0) | Mar 05, 2023 |
| HP            | 18E5                        | [969462a8a0](https://linux-hardware.org/?probe=969462a8a0) | Mar 05, 2023 |
| Lenovo        | ThinkCentre XXXX 739527G    | [c3e39b21f9](https://linux-hardware.org/?probe=c3e39b21f9) | Mar 05, 2023 |
| ASRock        | A300M-STX                   | [d920a52e51](https://linux-hardware.org/?probe=d920a52e51) | Mar 05, 2023 |
| Gigabyte      | MZBAYAP-00                  | [b090a8b795](https://linux-hardware.org/?probe=b090a8b795) | Mar 05, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [92b81bb3a1](https://linux-hardware.org/?probe=92b81bb3a1) | Mar 05, 2023 |
| ASUSTek       | H110M-A/M.2                 | [3c4bf3c1bd](https://linux-hardware.org/?probe=3c4bf3c1bd) | Mar 05, 2023 |
| ASUSTek       | H81M-E                      | [fc1a09013d](https://linux-hardware.org/?probe=fc1a09013d) | Mar 05, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| OpenMandriva 4.2    | 2268     | 34.67%  |
| OpenMandriva 4.3    | 2058     | 31.46%  |
| OpenMandriva 23.01  | 891      | 13.62%  |
| OpenMandriva 23.03  | 661      | 10.11%  |
| OpenMandriva 4.50   | 408      | 6.24%   |
| OpenMandriva 4.90   | 158      | 2.42%   |
| OpenMandriva 22.12  | 43       | 0.66%   |
| OpenMandriva 23.90  | 21       | 0.32%   |
| OpenMandriva 23.06  | 11       | 0.17%   |
| OpenMandriva 4.1    | 10       | 0.15%   |
| OpenMandriva 22.11  | 5        | 0.08%   |
| OpenMandriva 2014.0 | 3        | 0.05%   |
| OpenMandriva 4.0    | 2        | 0.03%   |
| OpenMandriva 4.0.1  | 1        | 0.02%   |
| OpenMandriva 22.90  | 1        | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| OpenMandriva | 6206     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Desktops | Percent |
|--------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002       | 2200     | 33.31%  |
| 5.16.7-desktop-1omv4003        | 1936     | 29.31%  |
| 6.1.1-desktop-1omv2290         | 805      | 12.19%  |
| 6.2.6-desktop-1omv2390         | 627      | 9.49%   |
| 5.12.4-desktop-1omv4050        | 206      | 3.12%   |
| 5.18.12-desktop-3omv4090       | 147      | 2.23%   |
| 5.16.13-desktop-1omv4003       | 142      | 2.15%   |
| 5.11.12-desktop-1omv4002       | 90       | 1.36%   |
| 5.19.5-desktop-1omv4090        | 80       | 1.21%   |
| 6.1.4-desktop-1omv2301         | 73       | 1.11%   |
| 5.19.12-desktop-2omv4090       | 54       | 0.82%   |
| 6.0.10-desktop-2omv22090       | 42       | 0.64%   |
| 5.14.7-desktop-1omv4050        | 22       | 0.33%   |
| 6.2.2-desktop-1omv2390         | 19       | 0.29%   |
| 6.2.1-desktop-1omv2390         | 11       | 0.17%   |
| 6.3.5-desktop-3omv2390         | 10       | 0.15%   |
| 5.19.11-desktop-2omv4090       | 10       | 0.15%   |
| 5.12.7-desktop-1omv4003        | 10       | 0.15%   |
| 5.5.12-desktop-1omv4001        | 9        | 0.14%   |
| 5.14.14-desktop-1omv4050       | 8        | 0.12%   |
| 6.1.2-desktop-1omv2301         | 7        | 0.11%   |
| 6.2.0-desktop-0.rc2.1omv2301   | 5        | 0.08%   |
| 6.1.11-desktop-1omv2390        | 5        | 0.08%   |
| 5.11.0-desktop-clang-1omv4002  | 5        | 0.08%   |
| 5.10.13-desktop-1omv4002       | 5        | 0.08%   |
| 5.17.1-desktop-2omv4050        | 4        | 0.06%   |
| 5.16.3-desktop-2omv4050        | 4        | 0.06%   |
| 6.2.8-desktop-1omv2390         | 3        | 0.05%   |
| 5.19.0-desktop-1omv4090        | 3        | 0.05%   |
| 6.3.0-desktop-1omv2390         | 2        | 0.03%   |
| 6.1.9-desktop-1omv2390         | 2        | 0.03%   |
| 6.1.4-desktop-gcc-1omv2301     | 2        | 0.03%   |
| 5.18.9-desktop-gcc-1omv4090    | 2        | 0.03%   |
| 5.18.13-desktop-1omv4090       | 2        | 0.03%   |
| 5.17.7-desktop-1omv4090        | 2        | 0.03%   |
| 5.16.5-desktop-2omv4003        | 2        | 0.03%   |
| 5.13.2-desktop-clang-1omv4050  | 2        | 0.03%   |
| 5.12.7-desktop-clang-1omv4003  | 2        | 0.03%   |
| 5.11.11-desktop-clang-1omv4050 | 2        | 0.03%   |
| 4.1.12-nrj-server-1omv         | 2        | 0.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10.14 | 2200     | 33.31%  |
| 5.16.7  | 1937     | 29.33%  |
| 6.1.1   | 805      | 12.19%  |
| 6.2.6   | 627      | 9.49%   |
| 5.12.4  | 206      | 3.12%   |
| 5.18.12 | 147      | 2.23%   |
| 5.16.13 | 143      | 2.17%   |
| 5.11.12 | 90       | 1.36%   |
| 5.19.5  | 80       | 1.21%   |
| 6.1.4   | 75       | 1.14%   |
| 5.19.12 | 55       | 0.83%   |
| 6.0.10  | 42       | 0.64%   |
| 5.14.7  | 22       | 0.33%   |
| 6.2.2   | 19       | 0.29%   |
| 5.12.7  | 12       | 0.18%   |
| 6.2.1   | 11       | 0.17%   |
| 5.19.11 | 11       | 0.17%   |
| 6.3.5   | 10       | 0.15%   |
| 5.5.12  | 9        | 0.14%   |
| 5.14.14 | 8        | 0.12%   |
| 6.1.2   | 7        | 0.11%   |
| 6.2.0   | 6        | 0.09%   |
| 6.1.11  | 5        | 0.08%   |
| 5.11.0  | 5        | 0.08%   |
| 5.10.13 | 5        | 0.08%   |
| 5.17.1  | 4        | 0.06%   |
| 5.16.3  | 4        | 0.06%   |
| 6.3.0   | 3        | 0.05%   |
| 6.2.8   | 3        | 0.05%   |
| 6.0.9   | 3        | 0.05%   |
| 6.0.0   | 3        | 0.05%   |
| 5.19.0  | 3        | 0.05%   |
| 5.16.5  | 3        | 0.05%   |
| 5.13.2  | 3        | 0.05%   |
| 6.1.9   | 2        | 0.03%   |
| 5.18.9  | 2        | 0.03%   |
| 5.18.13 | 2        | 0.03%   |
| 5.17.7  | 2        | 0.03%   |
| 5.11.11 | 2        | 0.03%   |
| 4.1.12  | 2        | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.10    | 2209     | 33.61%  |
| 5.16    | 2058     | 31.31%  |
| 6.1     | 896      | 13.63%  |
| 6.2     | 667      | 10.15%  |
| 5.12    | 222      | 3.38%   |
| 5.18    | 152      | 2.31%   |
| 5.19    | 151      | 2.3%    |
| 5.11    | 97       | 1.48%   |
| 6.0     | 50       | 0.76%   |
| 5.14    | 31       | 0.47%   |
| 6.3     | 14       | 0.21%   |
| 5.5     | 10       | 0.15%   |
| 5.17    | 6        | 0.09%   |
| 5.13    | 3        | 0.05%   |
| 4.1     | 3        | 0.05%   |
| 5.1     | 2        | 0.03%   |
| 5.8     | 1        | 0.02%   |
| 5.3     | 1        | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 6206     | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Desktops | Percent |
|----------|----------|---------|
| KDE5     | 5976     | 95.72%  |
| GNOME    | 189      | 3.03%   |
| LXQt     | 53       | 0.85%   |
| Unknown  | 11       | 0.18%   |
| Budgie   | 6        | 0.1%    |
| Cinnamon | 4        | 0.06%   |
| XFCE     | 2        | 0.03%   |
| KDE4     | 1        | 0.02%   |
| KDE      | 1        | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 5996     | 96.23%  |
| Wayland | 233      | 3.74%   |
| Unknown | 2        | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 6030     | 96.81%  |
| GDM     | 189      | 3.03%   |
| Unknown | 5        | 0.08%   |
| LightDM | 4        | 0.06%   |
| KDM     | 1        | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 3385     | 53.32%  |
| de_DE   | 500      | 7.88%   |
| ru_RU   | 455      | 7.17%   |
| fr_FR   | 349      | 5.5%    |
| pt_BR   | 262      | 4.13%   |
| pl_PL   | 195      | 3.07%   |
| it_IT   | 169      | 2.66%   |
| es_ES   | 138      | 2.17%   |
| en_GB   | 132      | 2.08%   |
| cs_CZ   | 68       | 1.07%   |
| es_MX   | 56       | 0.88%   |
| es_AR   | 56       | 0.88%   |
| hu_HU   | 55       | 0.87%   |
| de_AT   | 53       | 0.83%   |
| en_CA   | 44       | 0.69%   |
| en_AU   | 39       | 0.61%   |
| nl_NL   | 31       | 0.49%   |
| fr_CA   | 30       | 0.47%   |
| en_IN   | 25       | 0.39%   |
| de_CH   | 25       | 0.39%   |
| tr_TR   | 18       | 0.28%   |
| ru_UA   | 18       | 0.28%   |
| es_VE   | 18       | 0.28%   |
| es_CO   | 18       | 0.28%   |
| pt_PT   | 15       | 0.24%   |
| fr_BE   | 15       | 0.24%   |
| da_DK   | 15       | 0.24%   |
| es_CL   | 14       | 0.22%   |
| Unknown | 13       | 0.2%    |
| en_HK   | 10       | 0.16%   |
| ro_RO   | 9        | 0.14%   |
| es_PE   | 8        | 0.13%   |
| en_IL   | 8        | 0.13%   |
| nl_BE   | 7        | 0.11%   |
| es_UY   | 7        | 0.11%   |
| en_ZA   | 7        | 0.11%   |
| uk_UA   | 6        | 0.09%   |
| ja_JP   | 6        | 0.09%   |
| nb_NO   | 5        | 0.08%   |
| es_SV   | 5        | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 3533     | 56.5%   |
| EFI  | 2720     | 43.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Overlay  | 4910     | 75.98%  |
| Ext4     | 1430     | 22.13%  |
| Btrfs    | 71       | 1.1%    |
| Xfs      | 22       | 0.34%   |
| F2fs     | 9        | 0.14%   |
| Ext3     | 7        | 0.11%   |
| Jfs      | 5        | 0.08%   |
| Unknown  | 4        | 0.06%   |
| Reiserfs | 2        | 0.03%   |
| Tmpfs    | 1        | 0.02%   |
| Ext2     | 1        | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 3896     | 62.05%  |
| MBR     | 2355     | 37.51%  |
| Unknown | 28       | 0.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3892     | 61.64%  |
| No        | 2422     | 38.36%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3394     | 54.1%   |
| No        | 2879     | 45.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 1504     | 24.23%  |
| Gigabyte Technology | 1109     | 17.87%  |
| MSI                 | 677      | 10.91%  |
| ASRock              | 581      | 9.36%   |
| Hewlett-Packard     | 517      | 8.33%   |
| Dell                | 493      | 7.94%   |
| Lenovo              | 242      | 3.9%    |
| Intel               | 172      | 2.77%   |
| Acer                | 150      | 2.42%   |
| Fujitsu             | 84       | 1.35%   |
| Foxconn             | 78       | 1.26%   |
| Pegatron            | 75       | 1.21%   |
| Biostar             | 75       | 1.21%   |
| ECS                 | 51       | 0.82%   |
| Unknown             | 47       | 0.76%   |
| Medion              | 46       | 0.74%   |
| Positivo            | 20       | 0.32%   |
| Fujitsu Siemens     | 19       | 0.31%   |
| BESSTAR Tech        | 18       | 0.29%   |
| AZW                 | 15       | 0.24%   |
| Shuttle             | 13       | 0.21%   |
| PCWare              | 12       | 0.19%   |
| Packard Bell        | 12       | 0.19%   |
| Alienware           | 10       | 0.16%   |
| Supermicro          | 9        | 0.15%   |
| MACHINIST           | 9        | 0.15%   |
| Gateway             | 9        | 0.15%   |
| OEM                 | 8        | 0.13%   |
| Inventec            | 7        | 0.11%   |
| Huanan              | 6        | 0.1%    |
| eMachines           | 6        | 0.1%    |
| Apple               | 6        | 0.1%    |
| Semp Toshiba        | 5        | 0.08%   |
| Itautec             | 5        | 0.08%   |
| Wistron             | 4        | 0.06%   |
| Philco              | 4        | 0.06%   |
| MouseComputer       | 4        | 0.06%   |
| AMD                 | 4        | 0.06%   |
| ABIT                | 4        | 0.06%   |
| Login Informatica   | 3        | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 130      | 2.09%   |
| Unknown                      | 52       | 0.84%   |
| Dell OptiPlex 7010           | 45       | 0.73%   |
| Dell OptiPlex 780            | 37       | 0.6%    |
| ASUS PRIME A320M-K           | 31       | 0.5%    |
| Gigabyte H410M H V3          | 27       | 0.44%   |
| Dell OptiPlex 9020           | 26       | 0.42%   |
| Intel H61                    | 25       | 0.4%    |
| HP EliteDesk 800 G1 SFF      | 24       | 0.39%   |
| Gigabyte 970A-DS3P           | 24       | 0.39%   |
| Dell OptiPlex 3020           | 22       | 0.35%   |
| MSI MS-7817                  | 21       | 0.34%   |
| MSI MS-7721                  | 21       | 0.34%   |
| HP Compaq Pro 6300 SFF       | 21       | 0.34%   |
| ASUS TUF Gaming X570-PLUS    | 21       | 0.34%   |
| MSI MS-7C37                  | 20       | 0.32%   |
| Gigabyte B450M DS3H          | 20       | 0.32%   |
| ASUS SABERTOOTH Z77          | 20       | 0.32%   |
| ASUS PRIME B450M-A           | 20       | 0.32%   |
| MSI MS-7C02                  | 19       | 0.31%   |
| Gigabyte A320M-S2H           | 19       | 0.31%   |
| Dell OptiPlex 790            | 19       | 0.31%   |
| ASUS M5A78L-M/USB3           | 18       | 0.29%   |
| HP Compaq 8200 Elite SFF PC  | 16       | 0.26%   |
| Dell OptiPlex 380            | 16       | 0.26%   |
| ASUS M5A97 R2.0              | 16       | 0.26%   |
| MSI MS-7C91                  | 15       | 0.24%   |
| MSI MS-7B86                  | 15       | 0.24%   |
| ASUS TUF Gaming B550-PLUS    | 15       | 0.24%   |
| ASUS PRIME B450M-A II        | 15       | 0.24%   |
| MSI MS-7C56                  | 14       | 0.23%   |
| MSI MS-7A38                  | 14       | 0.23%   |
| MSI MS-7693                  | 14       | 0.23%   |
| Gigabyte GA-78LMT-USB3 6.0   | 14       | 0.23%   |
| Gigabyte G31M-ES2L           | 14       | 0.23%   |
| Gigabyte B75M-D3H            | 14       | 0.23%   |
| Dell OptiPlex 390            | 14       | 0.23%   |
| ASUS ROG STRIX B550-F GAMING | 14       | 0.23%   |
| ASRock B450M Pro4            | 14       | 0.23%   |
| MSI MS-7C52                  | 13       | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| Dell OptiPlex          | 335      | 5.4%    |
| ASUS PRIME             | 286      | 4.61%   |
| HP Compaq              | 187      | 3.01%   |
| Lenovo ThinkCentre     | 150      | 2.42%   |
| ASUS All               | 130      | 2.09%   |
| ASUS ROG               | 109      | 1.76%   |
| Acer Aspire            | 99       | 1.6%    |
| ASUS TUF               | 97       | 1.56%   |
| HP EliteDesk           | 84       | 1.35%   |
| Fujitsu ESPRIMO        | 72       | 1.16%   |
| ASUS M5A78L-M          | 63       | 1.02%   |
| HP ProDesk             | 62       | 1%      |
| Unknown                | 52       | 0.84%   |
| Dell Precision         | 49       | 0.79%   |
| Gigabyte B450M         | 47       | 0.76%   |
| ASUS P8H61-M           | 43       | 0.69%   |
| Dell Inspiron          | 42       | 0.68%   |
| Lenovo IdeaCentre      | 38       | 0.61%   |
| Gigabyte H410M         | 38       | 0.61%   |
| Dell Vostro            | 38       | 0.61%   |
| ASUS SABERTOOTH        | 38       | 0.61%   |
| Acer Veriton           | 38       | 0.61%   |
| HP Pavilion            | 37       | 0.6%    |
| Gigabyte B450          | 36       | 0.58%   |
| Gigabyte X570          | 34       | 0.55%   |
| ASUS M5A97             | 34       | 0.55%   |
| Gigabyte GA-78LMT-USB3 | 30       | 0.48%   |
| ASUS P8Z77-V           | 30       | 0.48%   |
| ASRock B450M           | 30       | 0.48%   |
| Intel H61              | 27       | 0.44%   |
| Gigabyte 970A-DS3P     | 24       | 0.39%   |
| Gigabyte A320M-S2H     | 23       | 0.37%   |
| ASUS P5K               | 23       | 0.37%   |
| MSI MS-7817            | 21       | 0.34%   |
| MSI MS-7721            | 21       | 0.34%   |
| MSI MS-7C37            | 20       | 0.32%   |
| Gigabyte B550          | 20       | 0.32%   |
| ASUS P5G41T-M          | 20       | 0.32%   |
| MSI MS-7C02            | 19       | 0.31%   |
| Gigabyte Z390          | 19       | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2012 | 677      | 10.91%  |
| 2013 | 577      | 9.3%    |
| 2018 | 549      | 8.85%   |
| 2011 | 484      | 7.8%    |
| 2014 | 422      | 6.8%    |
| 2010 | 401      | 6.46%   |
| 2020 | 397      | 6.4%    |
| 2009 | 381      | 6.14%   |
| 2019 | 371      | 5.98%   |
| 2017 | 342      | 5.51%   |
| 2021 | 317      | 5.11%   |
| 2008 | 298      | 4.8%    |
| 2015 | 284      | 4.58%   |
| 2016 | 258      | 4.16%   |
| 2007 | 196      | 3.16%   |
| 2006 | 131      | 2.11%   |
| 2022 | 86       | 1.39%   |
| 2005 | 22       | 0.35%   |
| 2023 | 8        | 0.13%   |
| 2004 | 5        | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 6206     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 6206     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 6205     | 99.98%  |
| Yes  | 1        | 0.02%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 1419     | 22.65%  |
| 16.01-24.0      | 1329     | 21.21%  |
| 4.01-8.0        | 1225     | 19.55%  |
| 3.01-4.0        | 1199     | 19.14%  |
| 32.01-64.0      | 578      | 9.22%   |
| 1.01-2.0        | 194      | 3.1%    |
| 24.01-32.0      | 122      | 1.95%   |
| 64.01-256.0     | 120      | 1.92%   |
| 2.01-3.0        | 63       | 1.01%   |
| 0.51-1.0        | 12       | 0.19%   |
| More than 256.0 | 5        | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 4426     | 69.04%  |
| 0.51-1.0   | 930      | 14.51%  |
| 2.01-3.0   | 731      | 11.4%   |
| 0.01-0.5   | 167      | 2.6%    |
| 3.01-4.0   | 101      | 1.58%   |
| 4.01-8.0   | 39       | 0.61%   |
| 8.01-16.0  | 14       | 0.22%   |
| 16.01-24.0 | 2        | 0.03%   |
| 32.01-64.0 | 1        | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 2703     | 42.69%  |
| 2      | 1705     | 26.93%  |
| 3      | 895      | 14.14%  |
| 4      | 504      | 7.96%   |
| 5      | 216      | 3.41%   |
| 0      | 128      | 2.02%   |
| 6      | 88       | 1.39%   |
| 7      | 40       | 0.63%   |
| 8      | 31       | 0.49%   |
| 9      | 8        | 0.13%   |
| 12     | 3        | 0.05%   |
| 15     | 2        | 0.03%   |
| 13     | 2        | 0.03%   |
| 11     | 2        | 0.03%   |
| 10     | 2        | 0.03%   |
| 18     | 1        | 0.02%   |
| 17     | 1        | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3662     | 58.67%  |
| No        | 2580     | 41.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 6142     | 98.97%  |
| No        | 64       | 1.03%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4048     | 64.82%  |
| Yes       | 2197     | 35.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 4798     | 76.85%  |
| Yes       | 1445     | 23.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Desktops | Percent |
|-------------|----------|---------|
| USA         | 787      | 12.67%  |
| Germany     | 710      | 11.43%  |
| Russia      | 571      | 9.19%   |
| France      | 444      | 7.15%   |
| Brazil      | 410      | 6.6%    |
| Poland      | 301      | 4.84%   |
| Italy       | 278      | 4.47%   |
| Canada      | 199      | 3.2%    |
| UK          | 198      | 3.19%   |
| Spain       | 193      | 3.11%   |
| Australia   | 117      | 1.88%   |
| Mexico      | 91       | 1.46%   |
| Hungary     | 88       | 1.42%   |
| Czechia     | 84       | 1.35%   |
| Netherlands | 79       | 1.27%   |
| Japan       | 79       | 1.27%   |
| India       | 79       | 1.27%   |
| Ukraine     | 77       | 1.24%   |
| Argentina   | 74       | 1.19%   |
| Austria     | 72       | 1.16%   |
| Finland     | 70       | 1.13%   |
| Switzerland | 52       | 0.84%   |
| Romania     | 52       | 0.84%   |
| Sweden      | 48       | 0.77%   |
| Serbia      | 45       | 0.72%   |
| Belgium     | 45       | 0.72%   |
| Greece      | 43       | 0.69%   |
| Portugal    | 42       | 0.68%   |
| Slovakia    | 39       | 0.63%   |
| Indonesia   | 38       | 0.61%   |
| Turkey      | 34       | 0.55%   |
| Israel      | 32       | 0.52%   |
| Bulgaria    | 31       | 0.5%    |
| Venezuela   | 30       | 0.48%   |
| Egypt       | 28       | 0.45%   |
| China       | 27       | 0.43%   |
| Malaysia    | 26       | 0.42%   |
| Denmark     | 26       | 0.42%   |
| Norway      | 25       | 0.4%    |
| Taiwan      | 24       | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Moscow           | 109      | 1.7%    |
| Sao Paulo        | 49       | 0.76%   |
| Berlin           | 48       | 0.75%   |
| Warsaw           | 44       | 0.69%   |
| St Petersburg    | 39       | 0.61%   |
| Rio de Janeiro   | 37       | 0.58%   |
| Vienna           | 35       | 0.55%   |
| Paris            | 35       | 0.55%   |
| Milan            | 35       | 0.55%   |
| Mexico City      | 29       | 0.45%   |
| Rome             | 28       | 0.44%   |
| Helsinki         | 27       | 0.42%   |
| Sydney           | 24       | 0.37%   |
| Melbourne        | 24       | 0.37%   |
| Nizhniy Novgorod | 23       | 0.36%   |
| Madrid           | 23       | 0.36%   |
| Hamburg          | 22       | 0.34%   |
| Gonikoppal       | 22       | 0.34%   |
| Budapest         | 22       | 0.34%   |
| Munich           | 20       | 0.31%   |
| Montreal         | 20       | 0.31%   |
| Yekaterinburg    | 19       | 0.3%    |
| Strzyzow         | 18       | 0.28%   |
| Brisbane         | 18       | 0.28%   |
| Athens           | 18       | 0.28%   |
| Prague           | 17       | 0.27%   |
| Novosibirsk      | 17       | 0.27%   |
| Cairo            | 17       | 0.27%   |
| Belgrade         | 17       | 0.27%   |
| Porto Alegre     | 16       | 0.25%   |
| Buenos Aires     | 16       | 0.25%   |
| Nuremberg        | 15       | 0.23%   |
| Barcelona        | 15       | 0.23%   |
| San José        | 14       | 0.22%   |
| Marseille        | 14       | 0.22%   |
| Stuttgart        | 13       | 0.2%    |
| Poznan           | 13       | 0.2%    |
| New Taipei       | 13       | 0.2%    |
| Kuala Lumpur     | 13       | 0.2%    |
| Krakow           | 13       | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2219     | 3066   | 20.51%  |
| Seagate             | 2081     | 2755   | 19.24%  |
| Samsung Electronics | 1309     | 1835   | 12.1%   |
| Kingston            | 694      | 832    | 6.42%   |
| Toshiba             | 614      | 724    | 5.68%   |
| Crucial             | 530      | 659    | 4.9%    |
| Hitachi             | 401      | 454    | 3.71%   |
| SanDisk             | 387      | 467    | 3.58%   |
| A-DATA Technology   | 253      | 288    | 2.34%   |
| China               | 150      | 172    | 1.39%   |
| Unknown             | 133      | 170    | 1.23%   |
| Intel               | 109      | 122    | 1.01%   |
| Maxtor              | 106      | 121    | 0.98%   |
| PNY                 | 100      | 118    | 0.92%   |
| SPCC                | 98       | 117    | 0.91%   |
| Patriot             | 87       | 95     | 0.8%    |
| Intenso             | 77       | 89     | 0.71%   |
| GOODRAM             | 77       | 91     | 0.71%   |
| HGST                | 74       | 99     | 0.68%   |
| Apacer              | 65       | 73     | 0.6%    |
| Phison              | 55       | 73     | 0.51%   |
| OCZ                 | 54       | 58     | 0.5%    |
| Corsair             | 53       | 57     | 0.49%   |
| Transcend           | 51       | 54     | 0.47%   |
| Gigabyte Technology | 44       | 52     | 0.41%   |
| Team                | 41       | 43     | 0.38%   |
| JMicron Technology  | 40       | 43     | 0.37%   |
| SK hynix            | 37       | 40     | 0.34%   |
| Netac               | 37       | 40     | 0.34%   |
| Micron Technology   | 37       | 40     | 0.34%   |
| Hewlett-Packard     | 37       | 42     | 0.34%   |
| Unknown             | 36       | 38     | 0.33%   |
| Silicon Motion      | 32       | 34     | 0.3%    |
| XPG                 | 28       | 39     | 0.26%   |
| ASMT                | 27       | 29     | 0.25%   |
| KIOXIA-EXCERIA      | 23       | 23     | 0.21%   |
| KingSpec            | 23       | 23     | 0.21%   |
| Lexar               | 20       | 20     | 0.18%   |
| Plextor             | 19       | 22     | 0.18%   |
| Fujitsu             | 19       | 19     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST500DM002-1BD142 500GB  | 204      | 1.64%   |
| Kingston SA400S37240G 240GB SSD  | 161      | 1.29%   |
| Seagate ST1000DM010-2EP102 1TB   | 160      | 1.29%   |
| Toshiba DT01ACA100 1TB           | 124      | 1%      |
| Seagate ST2000DM008-2FR102 2TB   | 109      | 0.88%   |
| WDC WD10EZEX-08WN4A0 1TB         | 95       | 0.76%   |
| Toshiba DT01ACA050 500GB         | 89       | 0.71%   |
| Kingston SA400S37480G 480GB SSD  | 83       | 0.67%   |
| Seagate ST3500418AS 500GB        | 82       | 0.66%   |
| Samsung SSD 860 EVO 500GB        | 81       | 0.65%   |
| Kingston SV300S37A120G 120GB SSD | 78       | 0.63%   |
| Kingston SA400S37120G 120GB SSD  | 77       | 0.62%   |
| Crucial CT500MX500SSD1 500GB     | 76       | 0.61%   |
| Seagate ST1000DM003-1ER162 1TB   | 74       | 0.59%   |
| Unknown SD/MMC/MS PRO 64GB       | 68       | 0.55%   |
| Samsung SSD 860 EVO 250GB        | 68       | 0.55%   |
| Crucial CT240BX500SSD1 240GB     | 67       | 0.54%   |
| Samsung SSD 850 EVO 250GB        | 63       | 0.51%   |
| Crucial CT1000MX500SSD1 1TB      | 62       | 0.5%    |
| Toshiba HDWD110 1TB              | 60       | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 56       | 0.45%   |
| WDC WD10EZEX-00BN5A0 1TB         | 54       | 0.43%   |
| Toshiba DT01ACA200 2TB           | 54       | 0.43%   |
| Seagate ST3500413AS 500GB        | 53       | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB   | 52       | 0.42%   |
| Samsung SSD 970 EVO Plus 500GB   | 51       | 0.41%   |
| Samsung SSD 850 EVO 500GB        | 51       | 0.41%   |
| Seagate ST2000DM001-1ER164 2TB   | 50       | 0.4%    |
| Seagate ST1000DM003-1SB102 1TB   | 50       | 0.4%    |
| Crucial CT480BX500SSD1 480GB     | 50       | 0.4%    |
| WDC WD20EZRZ-00Z5HB0 2TB         | 42       | 0.34%   |
| Samsung SSD 860 EVO 1TB          | 42       | 0.34%   |
| Seagate ST2000DM001-1CH164 2TB   | 41       | 0.33%   |
| Seagate ST31000528AS 1TB         | 39       | 0.31%   |
| Samsung HD502HJ 500GB            | 39       | 0.31%   |
| Samsung SSD 970 EVO Plus 1TB     | 38       | 0.31%   |
| Seagate ST2000DM006-2DM164 2TB   | 37       | 0.3%    |
| Samsung HD103SJ 1TB              | 37       | 0.3%    |
| Seagate Expansion 1TB            | 36       | 0.29%   |
| Unknown                          | 36       | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 2055     | 2709   | 35.75%  |
| WDC                 | 1930     | 2569   | 33.57%  |
| Toshiba             | 559      | 660    | 9.72%   |
| Samsung Electronics | 422      | 489    | 7.34%   |
| Hitachi             | 401      | 454    | 6.98%   |
| Maxtor              | 104      | 119    | 1.81%   |
| HGST                | 74       | 99     | 1.29%   |
| Unknown             | 72       | 76     | 1.25%   |
| Fujitsu             | 18       | 18     | 0.31%   |
| Hewlett-Packard     | 12       | 12     | 0.21%   |
| WD MediaMax         | 8        | 12     | 0.14%   |
| Intenso             | 8        | 8      | 0.14%   |
| External            | 8        | 8      | 0.14%   |
| USB3.0              | 7        | 7      | 0.12%   |
| Apple               | 7        | 7      | 0.12%   |
| QUANTUM             | 5        | 5      | 0.09%   |
| IBM/Hitachi         | 5        | 6      | 0.09%   |
| HPE                 | 5        | 5      | 0.09%   |
| ExcelStor           | 5        | 5      | 0.09%   |
| ASMT                | 4        | 5      | 0.07%   |
| ASMedia             | 4        | 4      | 0.07%   |
| Unknown             | 3        | 3      | 0.05%   |
| USB                 | 2        | 3      | 0.03%   |
| StoreJet            | 2        | 2      | 0.03%   |
| SSK                 | 2        | 2      | 0.03%   |
| RSH-319             | 2        | 2      | 0.03%   |
| MDT                 | 2        | 2      | 0.03%   |
| Magnetic Data       | 2        | 2      | 0.03%   |
| JMicron Technology  | 2        | 2      | 0.03%   |
| Inateck             | 2        | 2      | 0.03%   |
| HGST HTS            | 2        | 2      | 0.03%   |
| China               | 2        | 3      | 0.03%   |
| USB 3.0             | 1        | 2      | 0.02%   |
| TPH00800640GB       | 1        | 1      | 0.02%   |
| Super Talent        | 1        | 1      | 0.02%   |
| SAGE                | 1        | 1      | 0.02%   |
| SABRENT             | 1        | 2      | 0.02%   |
| RSH-339             | 1        | 1      | 0.02%   |
| Promise             | 1        | 1      | 0.02%   |
| MARVELL             | 1        | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 657      | 875    | 16.41%  |
| Kingston            | 587      | 695    | 14.66%  |
| Crucial             | 439      | 540    | 10.97%  |
| SanDisk             | 342      | 408    | 8.54%   |
| WDC                 | 276      | 321    | 6.89%   |
| A-DATA Technology   | 214      | 239    | 5.35%   |
| China               | 148      | 169    | 3.7%    |
| PNY                 | 91       | 107    | 2.27%   |
| SPCC                | 77       | 91     | 1.92%   |
| Patriot             | 76       | 84     | 1.9%    |
| GOODRAM             | 74       | 85     | 1.85%   |
| Intenso             | 67       | 77     | 1.67%   |
| Intel               | 59       | 63     | 1.47%   |
| Apacer              | 58       | 63     | 1.45%   |
| OCZ                 | 54       | 58     | 1.35%   |
| Toshiba             | 49       | 51     | 1.22%   |
| Transcend           | 43       | 45     | 1.07%   |
| Team                | 35       | 36     | 0.87%   |
| Micron Technology   | 31       | 34     | 0.77%   |
| Unknown             | 30       | 32     | 0.75%   |
| Netac               | 29       | 32     | 0.72%   |
| Gigabyte Technology | 26       | 28     | 0.65%   |
| Corsair             | 26       | 28     | 0.65%   |
| JMicron Technology  | 24       | 26     | 0.6%    |
| ASMT                | 23       | 24     | 0.57%   |
| KingSpec            | 22       | 22     | 0.55%   |
| KIOXIA-EXCERIA      | 16       | 16     | 0.4%    |
| Hewlett-Packard     | 16       | 18     | 0.4%    |
| XrayDisk            | 15       | 15     | 0.37%   |
| Unknown             | 15       | 16     | 0.37%   |
| LITEON              | 15       | 15     | 0.37%   |
| SK hynix            | 14       | 15     | 0.35%   |
| SABRENT             | 14       | 16     | 0.35%   |
| Plextor             | 13       | 15     | 0.32%   |
| Lexar               | 13       | 13     | 0.32%   |
| KingFast            | 13       | 15     | 0.32%   |
| Seagate             | 11       | 13     | 0.27%   |
| Leven               | 11       | 11     | 0.27%   |
| TO Exter            | 10       | 10     | 0.25%   |
| KingDian            | 10       | 11     | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 4454     | 7319   | 50.55%  |
| SSD     | 3132     | 4706   | 35.55%  |
| NVMe    | 1107     | 1536   | 12.56%  |
| Unknown | 97       | 133    | 1.1%    |
| MMC     | 21       | 23     | 0.24%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 5807     | 11544  | 78.3%   |
| NVMe | 1104     | 1522   | 14.89%  |
| SAS  | 484      | 628    | 6.53%   |
| MMC  | 21       | 23     | 0.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 4599     | 7202   | 56.42%  |
| 0.51-1.0   | 2247     | 3121   | 27.56%  |
| 1.01-2.0   | 767      | 979    | 9.41%   |
| 2.01-3.0   | 187      | 241    | 2.29%   |
| 3.01-4.0   | 182      | 249    | 2.23%   |
| 4.01-10.0  | 121      | 176    | 1.48%   |
| 10.01-20.0 | 49       | 57     | 0.6%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 2958     | 45.51%  |
| Unknown        | 957      | 14.72%  |
| 101-250        | 866      | 13.32%  |
| 251-500        | 580      | 8.92%   |
| 501-1000       | 346      | 5.32%   |
| 51-100         | 274      | 4.22%   |
| 21-50          | 252      | 3.88%   |
| 1001-2000      | 153      | 2.35%   |
| More than 3000 | 60       | 0.92%   |
| 2001-3000      | 54       | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 4701     | 73.49%  |
| Unknown        | 957      | 14.96%  |
| 21-50          | 169      | 2.64%   |
| 101-250        | 160      | 2.5%    |
| 51-100         | 124      | 1.94%   |
| 251-500        | 115      | 1.8%    |
| 501-1000       | 98       | 1.53%   |
| 1001-2000      | 41       | 0.64%   |
| More than 3000 | 16       | 0.25%   |
| 2001-3000      | 16       | 0.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 87       | 94     | 3.73%   |
| Seagate ST3500418AS 500GB         | 39       | 43     | 1.67%   |
| WDC WD5000AAKX-001CA0 500GB       | 20       | 23     | 0.86%   |
| Seagate ST31000524AS 1TB          | 20       | 20     | 0.86%   |
| Toshiba DT01ACA100 1TB            | 19       | 21     | 0.82%   |
| Seagate ST31000528AS 1TB          | 19       | 20     | 0.82%   |
| Kingston SV300S37A120G 120GB SSD  | 19       | 20     | 0.82%   |
| WDC WD5000AAKX-75U6AA0 500GB      | 18       | 18     | 0.77%   |
| Seagate ST9500325AS 500GB         | 18       | 19     | 0.77%   |
| Seagate ST1000DM010-2EP102 1TB    | 18       | 19     | 0.77%   |
| Toshiba DT01ACA050 500GB          | 17       | 19     | 0.73%   |
| Seagate ST3500413AS 500GB         | 17       | 18     | 0.73%   |
| Samsung Electronics HD322HJ 320GB | 16       | 18     | 0.69%   |
| Seagate ST3320418AS 320GB         | 15       | 16     | 0.64%   |
| Seagate ST2000DM001-1CH164 2TB    | 15       | 15     | 0.64%   |
| Seagate ST1000DM003-9YN162 1TB    | 15       | 16     | 0.64%   |
| Samsung Electronics HD502HJ 500GB | 14       | 14     | 0.6%    |
| Samsung Electronics HD161HJ 160GB | 14       | 14     | 0.6%    |
| Hitachi HDS721050CLA362 500GB     | 14       | 17     | 0.6%    |
| Samsung Electronics HD103SJ 1TB   | 13       | 14     | 0.56%   |
| Hitachi HDS721010CLA332 1TB       | 13       | 13     | 0.56%   |
| Seagate ST250DM000-1BD141 250GB   | 12       | 12     | 0.52%   |
| Samsung Electronics HD103SI 1TB   | 12       | 12     | 0.52%   |
| WDC WD5000AADS-00S9B0 500GB       | 11       | 11     | 0.47%   |
| Seagate ST3250318AS 250GB         | 11       | 11     | 0.47%   |
| Seagate ST1000DM003-1CH162 1TB    | 11       | 13     | 0.47%   |
| Samsung Electronics HD103UJ 1TB   | 11       | 13     | 0.47%   |
| Maxtor STM3250310AS 250GB         | 11       | 11     | 0.47%   |
| WDC WD3200AAJS-00L7A0 320GB       | 10       | 10     | 0.43%   |
| WDC WD20EARS-00MVWB0 2TB          | 10       | 12     | 0.43%   |
| WDC WD10EARS-00Y5B1 1TB           | 10       | 13     | 0.43%   |
| Seagate ST3250310AS 250GB         | 10       | 12     | 0.43%   |
| Seagate ST2000DL003-9VT166 2TB    | 10       | 11     | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD  | 9        | 11     | 0.39%   |
| WDC WD5000AAKX-003CA0 500GB       | 9        | 9      | 0.39%   |
| WDC WD20EZRZ-00Z5HB0 2TB          | 9        | 10     | 0.39%   |
| Seagate ST500LM021-1KJ152 500GB   | 9        | 9      | 0.39%   |
| Seagate ST3320613AS 320GB         | 9        | 10     | 0.39%   |
| Seagate ST3250820AS 250GB         | 9        | 10     | 0.39%   |
| Seagate ST31500341AS 1TB          | 9        | 9      | 0.39%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 679      | 772    | 30.67%  |
| WDC                 | 651      | 761    | 29.4%   |
| Samsung Electronics | 230      | 257    | 10.39%  |
| Hitachi             | 175      | 194    | 7.9%    |
| Toshiba             | 85       | 90     | 3.84%   |
| Maxtor              | 68       | 72     | 3.07%   |
| Kingston            | 67       | 71     | 3.03%   |
| SanDisk             | 33       | 36     | 1.49%   |
| HGST                | 22       | 28     | 0.99%   |
| Crucial             | 22       | 24     | 0.99%   |
| A-DATA Technology   | 19       | 21     | 0.86%   |
| Intel               | 16       | 16     | 0.72%   |
| China               | 14       | 14     | 0.63%   |
| Hewlett-Packard     | 8        | 8      | 0.36%   |
| OCZ                 | 7        | 7      | 0.32%   |
| GOODRAM             | 7        | 7      | 0.32%   |
| Fujitsu             | 7        | 7      | 0.32%   |
| ASMT                | 7        | 7      | 0.32%   |
| SPCC                | 6        | 6      | 0.27%   |
| Unknown             | 6        | 6      | 0.27%   |
| Netac               | 5        | 5      | 0.23%   |
| Corsair             | 5        | 5      | 0.23%   |
| Patriot             | 4        | 4      | 0.18%   |
| Micron Technology   | 4        | 5      | 0.18%   |
| WD MediaMax         | 3        | 3      | 0.14%   |
| SK hynix            | 3        | 3      | 0.14%   |
| KingSpec            | 3        | 3      | 0.14%   |
| Intenso             | 3        | 3      | 0.14%   |
| IBM/Hitachi         | 3        | 4      | 0.14%   |
| XPG                 | 2        | 2      | 0.09%   |
| USB3.0              | 2        | 2      | 0.09%   |
| Team                | 2        | 2      | 0.09%   |
| QUANTUM             | 2        | 2      | 0.09%   |
| LITEON              | 2        | 2      | 0.09%   |
| Initio              | 2        | 2      | 0.09%   |
| HPE                 | 2        | 2      | 0.09%   |
| Apacer              | 2        | 3      | 0.09%   |
| XSTAR               | 1        | 1      | 0.05%   |
| XrayDisk            | 1        | 1      | 0.05%   |
| WDC WDS2            | 1        | 1      | 0.05%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 679      | 772    | 35.96%  |
| WDC                 | 626      | 729    | 33.16%  |
| Samsung Electronics | 200      | 224    | 10.59%  |
| Hitachi             | 175      | 194    | 9.27%   |
| Toshiba             | 84       | 89     | 4.45%   |
| Maxtor              | 68       | 72     | 3.6%    |
| HGST                | 22       | 28     | 1.17%   |
| Fujitsu             | 7        | 7      | 0.37%   |
| Hewlett-Packard     | 6        | 6      | 0.32%   |
| WD MediaMax         | 3        | 3      | 0.16%   |
| IBM/Hitachi         | 3        | 4      | 0.16%   |
| USB3.0              | 2        | 2      | 0.11%   |
| Quantum             | 2        | 2      | 0.11%   |
| HPE                 | 2        | 2      | 0.11%   |
| SAGE                | 1        | 1      | 0.05%   |
| RSH-339             | 1        | 1      | 0.05%   |
| RSH-319             | 1        | 1      | 0.05%   |
| IB                  | 1        | 1      | 0.05%   |
| ExcelStor           | 1        | 1      | 0.05%   |
| China               | 1        | 1      | 0.05%   |
| ASMT                | 1        | 1      | 0.05%   |
| ASMedia             | 1        | 1      | 0.05%   |
| Unknown             | 1        | 1      | 0.05%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 1669     | 2143   | 83.74%  |
| SSD     | 297      | 322    | 14.9%   |
| NVMe    | 26       | 27     | 1.3%    |
| Unknown | 1        | 1      | 0.05%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB                        | 3        | 4      | 5.08%   |
| Seagate ST3250318AS 250GB                        | 3        | 3      | 5.08%   |
| Samsung Electronics HD103SJ 1TB                  | 3        | 3      | 5.08%   |
| Apple HDD HTS541010A9E662 1TB                    | 3        | 3      | 5.08%   |
| WDC WD800JD-00LSA0 80GB                          | 2        | 3      | 3.39%   |
| WDC WD20EZRX-00D8PB0 2TB                         | 2        | 2      | 3.39%   |
| Seagate ST500DM002-1BD142 500GB                  | 2        | 2      | 3.39%   |
| Samsung Electronics HD502HJ 500GB                | 2        | 2      | 3.39%   |
| Samsung Electronics HD103UJ 1TB                  | 2        | 3      | 3.39%   |
| WDC WD800JD-75MSA3 80GB                          | 1        | 1      | 1.69%   |
| WDC WD7501AALS-00J7B0 752GB                      | 1        | 1      | 1.69%   |
| WDC WD7500BPVT-22HXZT3 752GB                     | 1        | 1      | 1.69%   |
| WDC WD5000AAKS-00C8A0 500GB                      | 1        | 1      | 1.69%   |
| WDC WD3200AAJS-60Z0A0 320GB                      | 1        | 1      | 1.69%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1        | 1      | 1.69%   |
| WDC WD1600YS-23SHB0 160GB                        | 1        | 1      | 1.69%   |
| WDC WD10JPVT-75A1YT0 1TB                         | 1        | 1      | 1.69%   |
| WDC WD10EALX-759BA1 1TB                          | 1        | 1      | 1.69%   |
| TPH00800640GB 640GB                              | 1        | 1      | 1.69%   |
| Toshiba MQ01ABD050 500GB                         | 1        | 1      | 1.69%   |
| Toshiba MK3256GSY 320GB                          | 1        | 1      | 1.69%   |
| Toshiba DT01ACA100 1TB                           | 1        | 1      | 1.69%   |
| Seagate STM3250318AS 250GB                       | 1        | 1      | 1.69%   |
| Seagate STM31000528AS 1TB                        | 1        | 1      | 1.69%   |
| Seagate ST980811AS 80GB                          | 1        | 1      | 1.69%   |
| Seagate ST9320423AS 320GB                        | 1        | 1      | 1.69%   |
| Seagate ST3750640NS 752GB                        | 1        | 1      | 1.69%   |
| Seagate ST3320418AS 320GB                        | 1        | 1      | 1.69%   |
| Seagate ST3250820AS 250GB                        | 1        | 1      | 1.69%   |
| Seagate ST3160215A 160GB                         | 1        | 1      | 1.69%   |
| Seagate ST31000528AS 1TB                         | 1        | 1      | 1.69%   |
| Samsung Electronics SSD 980 500GB                | 1        | 1      | 1.69%   |
| Samsung Electronics SSD 980 1TB                  | 1        | 1      | 1.69%   |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1        | 1      | 1.69%   |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1        | 1      | 1.69%   |
| Samsung Electronics HM160HI 160GB                | 1        | 1      | 1.69%   |
| Samsung Electronics HD753LJ 752GB                | 1        | 1      | 1.69%   |
| Samsung Electronics HD501LJ 500GB                | 1        | 1      | 1.69%   |
| Samsung Electronics HD252HJ 250GB                | 1        | 1      | 1.69%   |
| Maxtor STM3500320AS 500GB                        | 1        | 1      | 1.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 17       | 18     | 28.81%  |
| Samsung Electronics | 15       | 16     | 25.42%  |
| WDC                 | 13       | 14     | 22.03%  |
| Hitachi             | 4        | 4      | 6.78%   |
| Toshiba             | 3        | 3      | 5.08%   |
| Apple               | 3        | 3      | 5.08%   |
| TPH00800640GB       | 1        | 1      | 1.69%   |
| Maxtor              | 1        | 1      | 1.69%   |
| Kingston            | 1        | 1      | 1.69%   |
| GOODRAM             | 1        | 1      | 1.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 5022     | 10251  | 65.47%  |
| Malfunc  | 1927     | 2493   | 25.12%  |
| Detected | 665      | 911    | 8.67%   |
| Failed   | 57       | 62     | 0.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 3963     | 48.53%  |
| AMD                              | 2002     | 24.52%  |
| Samsung Electronics              | 364      | 4.46%   |
| ASMedia Technology               | 240      | 2.94%   |
| JMicron Technology               | 222      | 2.72%   |
| Nvidia                           | 212      | 2.6%    |
| SanDisk                          | 190      | 2.33%   |
| Marvell Technology Group         | 185      | 2.27%   |
| Phison Electronics               | 154      | 1.89%   |
| Kingston Technology Company      | 127      | 1.56%   |
| Micron/Crucial Technology        | 97       | 1.19%   |
| Silicon Motion                   | 93       | 1.14%   |
| VIA Technologies                 | 61       | 0.75%   |
| ADATA Technology                 | 43       | 0.53%   |
| Realtek Semiconductor            | 27       | 0.33%   |
| SK hynix                         | 20       | 0.24%   |
| Seagate Technology               | 16       | 0.2%    |
| MAXIO Technology (Hangzhou)      | 16       | 0.2%    |
| Toshiba America Info Systems     | 15       | 0.18%   |
| Silicon Image                    | 14       | 0.17%   |
| Micron Technology                | 14       | 0.17%   |
| KIOXIA                           | 11       | 0.13%   |
| LSI Logic / Symbios Logic        | 10       | 0.12%   |
| Integrated Technology Express    | 10       | 0.12%   |
| Broadcom / LSI                   | 10       | 0.12%   |
| Shenzhen Longsys Electronics     | 8        | 0.1%    |
| Lite-On Technology               | 8        | 0.1%    |
| Promise Technology               | 5        | 0.06%   |
| Adaptec                          | 5        | 0.06%   |
| Lite-On IT Corp. / Plextor       | 4        | 0.05%   |
| Silicon Integrated Systems [SiS] | 3        | 0.04%   |
| Hewlett-Packard                  | 3        | 0.04%   |
| Biwin Storage Technology         | 3        | 0.04%   |
| Union Memory (Shenzhen)          | 2        | 0.02%   |
| Netac Technology                 | 2        | 0.02%   |
| INNOGRIT                         | 2        | 0.02%   |
| 3ware                            | 2        | 0.02%   |
| Yangtze Memory Technologies      | 1        | 0.01%   |
| Solid State Storage Technology   | 1        | 0.01%   |
| OCZ Technology Group             | 1        | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1057     | 9.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 530      | 4.99%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 378      | 3.56%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 376      | 3.54%   |
| AMD 400 Series Chipset SATA Controller                                                  | 373      | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 349      | 3.29%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 310      | 2.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 289      | 2.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 281      | 2.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 266      | 2.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 255      | 2.4%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 223      | 2.1%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 217      | 2.04%   |
| AMD 500 Series Chipset SATA Controller                                                  | 206      | 1.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 204      | 1.92%   |
| Intel SATA Controller [RAID mode]                                                       | 185      | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 185      | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 183      | 1.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 175      | 1.65%   |
| AMD FCH SATA Controller D                                                               | 141      | 1.33%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 132      | 1.24%   |
| Nvidia MCP61 SATA Controller                                                            | 120      | 1.13%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 118      | 1.11%   |
| Nvidia MCP61 IDE                                                                        | 109      | 1.03%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 103      | 0.97%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 99       | 0.93%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 96       | 0.9%    |
| AMD 300 Series Chipset SATA Controller                                                  | 95       | 0.9%    |
| AMD FCH IDE Controller                                                                  | 89       | 0.84%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 77       | 0.73%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 76       | 0.72%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 73       | 0.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 72       | 0.68%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 71       | 0.67%   |
| Phison E12 NVMe Controller                                                              | 70       | 0.66%   |
| Samsung NVMe SSD Controller 980                                                         | 67       | 0.63%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 67       | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 64       | 0.6%    |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 64       | 0.6%    |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 64       | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 4762     | 58.61%  |
| IDE  | 1939     | 23.86%  |
| NVMe | 1097     | 13.5%   |
| RAID | 291      | 3.58%   |
| SAS  | 22       | 0.27%   |
| SCSI | 14       | 0.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 4016     | 64.71%  |
| AMD    | 2190     | 35.29%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 102      | 1.64%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 89       | 1.43%   |
| AMD Ryzen 5 3600 6-Core Processor           | 83       | 1.33%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 73       | 1.17%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 70       | 1.12%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 66       | 1.06%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 66       | 1.06%   |
| AMD FX-8350 Eight-Core Processor            | 64       | 1.03%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 59       | 0.95%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 59       | 0.95%   |
| Intel Core i5-10400 CPU @ 2.90GHz           | 59       | 0.95%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 59       | 0.95%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 57       | 0.92%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 56       | 0.9%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 54       | 0.87%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 53       | 0.85%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 52       | 0.84%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 51       | 0.82%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 46       | 0.74%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 46       | 0.74%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 45       | 0.72%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 44       | 0.71%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 44       | 0.71%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 42       | 0.67%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 42       | 0.67%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 41       | 0.66%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 41       | 0.66%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 37       | 0.59%   |
| AMD FX-6300 Six-Core Processor              | 37       | 0.59%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 36       | 0.58%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 36       | 0.58%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 35       | 0.56%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 35       | 0.56%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 34       | 0.55%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 34       | 0.55%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 33       | 0.53%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 32       | 0.51%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 31       | 0.5%    |
| Intel Core i5-9400F CPU @ 2.90GHz           | 31       | 0.5%    |
| Intel Core i7-6700 CPU @ 3.40GHz            | 30       | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 1143     | 18.38%  |
| Intel Core i3           | 628      | 10.1%   |
| Intel Core i7           | 591      | 9.5%    |
| AMD Ryzen 5             | 475      | 7.64%   |
| Intel Core 2 Duo        | 305      | 4.9%    |
| AMD FX                  | 259      | 4.16%   |
| AMD Ryzen 7             | 248      | 3.99%   |
| Intel Pentium           | 234      | 3.76%   |
| Intel Celeron           | 226      | 3.63%   |
| Intel Core 2 Quad       | 184      | 2.96%   |
| Intel Xeon              | 177      | 2.85%   |
| Intel Pentium Dual-Core | 143      | 2.3%    |
| AMD Ryzen 3             | 124      | 1.99%   |
| Other                   | 123      | 1.98%   |
| AMD A8                  | 111      | 1.78%   |
| AMD Athlon II X2        | 99       | 1.59%   |
| AMD Ryzen 9             | 94       | 1.51%   |
| AMD Phenom II X4        | 90       | 1.45%   |
| AMD A10                 | 77       | 1.24%   |
| AMD Athlon 64 X2        | 75       | 1.21%   |
| Intel Core 2            | 67       | 1.08%   |
| AMD A4                  | 67       | 1.08%   |
| AMD Athlon              | 60       | 0.96%   |
| AMD A6                  | 53       | 0.85%   |
| Intel Pentium Dual      | 49       | 0.79%   |
| AMD Athlon II X4        | 41       | 0.66%   |
| AMD Phenom II X6        | 37       | 0.59%   |
| AMD Phenom              | 33       | 0.53%   |
| Intel Atom              | 31       | 0.5%    |
| Intel Pentium 4         | 30       | 0.48%   |
| Intel Core i9           | 30       | 0.48%   |
| Intel Pentium Gold      | 28       | 0.45%   |
| Intel Pentium D         | 28       | 0.45%   |
| AMD Athlon II X3        | 26       | 0.42%   |
| AMD Sempron             | 22       | 0.35%   |
| AMD Athlon X4           | 22       | 0.35%   |
| AMD Ryzen 5 PRO         | 21       | 0.34%   |
| AMD Athlon 64           | 19       | 0.31%   |
| AMD Phenom II X2        | 17       | 0.27%   |
| AMD Ryzen Threadripper  | 13       | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 2404     | 38.63%  |
| 2       | 2193     | 35.24%  |
| 6       | 775      | 12.45%  |
| 8       | 376      | 6.04%   |
| 1       | 195      | 3.13%   |
| 3       | 105      | 1.69%   |
| 12      | 85       | 1.37%   |
| 16      | 46       | 0.74%   |
| 10      | 22       | 0.35%   |
| 14      | 7        | 0.11%   |
| 24      | 6        | 0.1%    |
| 28      | 3        | 0.05%   |
| 32      | 2        | 0.03%   |
| 20      | 2        | 0.03%   |
| 44      | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 6174     | 99.48%  |
| 2      | 32       | 0.52%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 3107     | 49.98%  |
| 2       | 3092     | 49.74%  |
| 4       | 9        | 0.14%   |
| 8       | 4        | 0.06%   |
| 12      | 2        | 0.03%   |
| 6       | 1        | 0.02%   |
| Unknown | 1        | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 6204     | 99.95%  |
| Unknown        | 3        | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 649      | 10.24%  |
| 0x306c3    | 602      | 9.5%    |
| 0x306a9    | 463      | 7.31%   |
| 0x1067a    | 433      | 6.83%   |
| 0x206a7    | 402      | 6.34%   |
| 0x08701021 | 222      | 3.5%    |
| 0x506e3    | 196      | 3.09%   |
| 0x906ea    | 158      | 2.49%   |
| 0x906e9    | 144      | 2.27%   |
| 0x06001119 | 134      | 2.11%   |
| 0x0800820d | 122      | 1.93%   |
| 0x010000c8 | 122      | 1.93%   |
| 0x08108109 | 95       | 1.5%    |
| 0x08101016 | 92       | 1.45%   |
| 0x06000822 | 89       | 1.4%    |
| 0xa0653    | 87       | 1.37%   |
| 0x6fb      | 81       | 1.28%   |
| 0x6fd      | 76       | 1.2%    |
| 0xa0655    | 73       | 1.15%   |
| 0x06003106 | 71       | 1.12%   |
| 0x10676    | 62       | 0.98%   |
| 0x08001138 | 61       | 0.96%   |
| 0x106e5    | 60       | 0.95%   |
| 0x010000b6 | 53       | 0.84%   |
| 0x0a201016 | 52       | 0.82%   |
| 0x906eb    | 51       | 0.8%    |
| 0x20655    | 51       | 0.8%    |
| 0x0a50000d | 51       | 0.8%    |
| 0x0a50000c | 49       | 0.77%   |
| 0xa0671    | 43       | 0.68%   |
| 0x0600081c | 42       | 0.66%   |
| 0x906ed    | 39       | 0.62%   |
| 0x08600106 | 38       | 0.6%    |
| 0x0600611a | 38       | 0.6%    |
| 0x106a5    | 36       | 0.57%   |
| 0x6f6      | 35       | 0.55%   |
| 0x010000bf | 35       | 0.55%   |
| 0x10677    | 33       | 0.52%   |
| 0x08701013 | 33       | 0.52%   |
| 0x6f2      | 31       | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 711      | 11.45%  |
| Penryn           | 567      | 9.13%   |
| IvyBridge        | 533      | 8.58%   |
| KabyLake         | 494      | 7.95%   |
| SandyBridge      | 466      | 7.5%    |
| K10              | 366      | 5.89%   |
| Piledriver       | 357      | 5.75%   |
| Zen 2            | 313      | 5.04%   |
| Zen+             | 262      | 4.22%   |
| Core             | 252      | 4.06%   |
| Skylake          | 240      | 3.86%   |
| Zen              | 232      | 3.74%   |
| Zen 3            | 226      | 3.64%   |
| CometLake        | 182      | 2.93%   |
| K8 Hammer        | 115      | 1.85%   |
| Nehalem          | 107      | 1.72%   |
| Westmere         | 105      | 1.69%   |
| Steamroller      | 86       | 1.38%   |
| Silvermont       | 71       | 1.14%   |
| NetBurst         | 65       | 1.05%   |
| Excavator        | 58       | 0.93%   |
| Bulldozer        | 54       | 0.87%   |
| Alderlake Hybrid | 50       | 0.81%   |
| Icelake          | 46       | 0.74%   |
| K10 Llano        | 41       | 0.66%   |
| Goldmont plus    | 37       | 0.6%    |
| Jaguar           | 33       | 0.53%   |
| Bonnell          | 26       | 0.42%   |
| Puma             | 24       | 0.39%   |
| Broadwell        | 21       | 0.34%   |
| Bobcat           | 21       | 0.34%   |
| Goldmont         | 20       | 0.32%   |
| Unknown          | 15       | 0.24%   |
| Tremont          | 13       | 0.21%   |
| TigerLake        | 2        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 2293     | 35.62%  |
| Intel                      | 2157     | 33.51%  |
| AMD                        | 1963     | 30.5%   |
| Matrox Electronics Systems | 12       | 0.19%   |
| VIA Technologies           | 6        | 0.09%   |
| ATI Technologies           | 3        | 0.05%   |
| S3 Graphics                | 1        | 0.02%   |
| Conexant Systems           | 1        | 0.02%   |
| ASPEED Technology          | 1        | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 354      | 5.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 261      | 3.98%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 235      | 3.59%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 222      | 3.39%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 188      | 2.87%   |
| Nvidia GK208B [GeForce GT 710]                                              | 170      | 2.59%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 131      | 2%      |
| Nvidia GT218 [GeForce 210]                                                  | 130      | 1.98%   |
| Intel HD Graphics 530                                                       | 124      | 1.89%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 121      | 1.85%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 105      | 1.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 105      | 1.6%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 99       | 1.51%   |
| Nvidia GK208B [GeForce GT 730]                                              | 98       | 1.5%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 97       | 1.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 93       | 1.42%   |
| Intel HD Graphics 630                                                       | 83       | 1.27%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 76       | 1.16%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 74       | 1.13%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 66       | 1.01%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 59       | 0.9%    |
| Nvidia GF119 [GeForce GT 610]                                               | 59       | 0.9%    |
| AMD RS780L [Radeon 3000]                                                    | 58       | 0.89%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 55       | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 55       | 0.84%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 55       | 0.84%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 55       | 0.84%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 54       | 0.82%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 53       | 0.81%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 46       | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 46       | 0.7%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 46       | 0.7%    |
| Nvidia GF108 [GeForce GT 630]                                               | 45       | 0.69%   |
| Intel Core Processor Integrated Graphics Controller                         | 44       | 0.67%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 41       | 0.63%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 41       | 0.63%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 38       | 0.58%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 37       | 0.56%   |
| AMD Renoir                                                                  | 37       | 0.56%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 35       | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 2181     | 34.9%   |
| 1 x Intel                | 1941     | 31.06%  |
| 1 x AMD                  | 1831     | 29.3%   |
| 2 x AMD                  | 76       | 1.22%   |
| Intel + Nvidia           | 74       | 1.18%   |
| 2 x Intel                | 48       | 0.77%   |
| Intel + AMD              | 33       | 0.53%   |
| AMD + Nvidia             | 26       | 0.42%   |
| 2 x Nvidia               | 14       | 0.22%   |
| 1 x Matrox               | 11       | 0.18%   |
| 1 x VIA                  | 6        | 0.1%    |
| Intel + 2 x Nvidia       | 2        | 0.03%   |
| 3 x AMD                  | 1        | 0.02%   |
| 1 x S3 Graphics          | 1        | 0.02%   |
| Nvidia + Matrox          | 1        | 0.02%   |
| Nvidia + ASPEED          | 1        | 0.02%   |
| Intel + Conexant Systems | 1        | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 5975     | 95.92%  |
| Unknown     | 206      | 3.31%   |
| Proprietary | 48       | 0.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 2146     | 34.28%  |
| 1.01-2.0   | 1100     | 17.57%  |
| 0.51-1.0   | 981      | 15.67%  |
| 0.01-0.5   | 837      | 13.37%  |
| 3.01-4.0   | 470      | 7.51%   |
| 7.01-8.0   | 396      | 6.33%   |
| 5.01-6.0   | 180      | 2.88%   |
| 8.01-16.0  | 76       | 1.21%   |
| 2.01-3.0   | 61       | 0.97%   |
| 16.01-24.0 | 10       | 0.16%   |
| 4.01-5.0   | 3        | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 1083     | 17.68%  |
| Goldstar             | 729      | 11.9%   |
| Dell                 | 534      | 8.72%   |
| Hewlett-Packard      | 527      | 8.6%    |
| Acer                 | 477      | 7.79%   |
| Philips              | 370      | 6.04%   |
| AOC                  | 352      | 5.75%   |
| BenQ                 | 285      | 4.65%   |
| Ancor Communications | 241      | 3.93%   |
| ViewSonic            | 158      | 2.58%   |
| Iiyama               | 131      | 2.14%   |
| ASUSTek Computer     | 99       | 1.62%   |
| Lenovo               | 73       | 1.19%   |
| Sony                 | 64       | 1.04%   |
| Fujitsu Siemens      | 62       | 1.01%   |
| Eizo                 | 54       | 0.88%   |
| NEC Computers        | 52       | 0.85%   |
| HannStar             | 41       | 0.67%   |
| Medion               | 31       | 0.51%   |
| Sceptre Tech         | 28       | 0.46%   |
| Unknown              | 27       | 0.44%   |
| Panasonic            | 27       | 0.44%   |
| Toshiba              | 24       | 0.39%   |
| Vizio                | 22       | 0.36%   |
| Vestel Elektronik    | 22       | 0.36%   |
| MSI                  | 20       | 0.33%   |
| Sharp                | 18       | 0.29%   |
| Hitachi              | 16       | 0.26%   |
| Belinea              | 16       | 0.26%   |
| MStar                | 14       | 0.23%   |
| Packard Bell         | 13       | 0.21%   |
| Gigabyte Technology  | 13       | 0.21%   |
| Unknown (XXX)        | 12       | 0.2%    |
| ___                  | 11       | 0.18%   |
| Insignia             | 11       | 0.18%   |
| IOD                  | 10       | 0.16%   |
| HKC                  | 10       | 0.16%   |
| Gateway              | 10       | 0.16%   |
| Unknown              | 10       | 0.16%   |
| RTK                  | 9        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 43       | 0.69%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 30       | 0.48%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 28       | 0.45%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 23       | 0.37%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                       | 23       | 0.37%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch  | 22       | 0.35%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                      | 22       | 0.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 21       | 0.34%   |
| AOC 27P2DG5 AOC2702 1920x1080 598x336mm 27.0-inch                     | 21       | 0.34%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 19       | 0.3%    |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 17       | 0.27%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 17       | 0.27%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 17       | 0.27%   |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch            | 16       | 0.26%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 15       | 0.24%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 14       | 0.22%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                 | 14       | 0.22%   |
| Panasonic TV MEIA296 3840x2160 708x398mm 32.0-inch                    | 14       | 0.22%   |
| Goldstar W2243 GSM56FE 1920x1080 477x269mm 21.6-inch                  | 13       | 0.21%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                   | 13       | 0.21%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 13       | 0.21%   |
| AOC 2460G5 AOC2460 1920x1080 531x299mm 24.0-inch                      | 13       | 0.21%   |
| Samsung Electronics U28E590 SAM0C4D 1680x1050 610x350mm 27.7-inch     | 12       | 0.19%   |
| MStar TV MST0030 1920x1080 708x398mm 32.0-inch                        | 12       | 0.19%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch            | 12       | 0.19%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 12       | 0.19%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 12       | 0.19%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                     | 12       | 0.19%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                     | 11       | 0.18%   |
| AOC 936W AOC1936 1366x768 410x230mm 18.5-inch                         | 11       | 0.18%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 10       | 0.16%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 10       | 0.16%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch     | 10       | 0.16%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 10       | 0.16%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 10       | 0.16%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 10       | 0.16%   |
| Ancor Communications VS278 ACI27A1 1920x1080 598x336mm 27.0-inch      | 10       | 0.16%   |
| Unknown                                                               | 10       | 0.16%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch  | 9        | 0.14%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 9        | 0.14%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 2983     | 49.54%  |
| 1280x1024 (SXGA)   | 543      | 9.02%   |
| 3840x2160 (4K)     | 446      | 7.41%   |
| 1680x1050 (WSXGA+) | 406      | 6.74%   |
| 1366x768 (WXGA)    | 316      | 5.25%   |
| 2560x1440 (QHD)    | 300      | 4.98%   |
| 1440x900 (WXGA+)   | 270      | 4.48%   |
| 1600x900 (HD+)     | 202      | 3.35%   |
| 1920x1200 (WUXGA)  | 155      | 2.57%   |
| 1360x768           | 117      | 1.94%   |
| 3440x1440          | 61       | 1.01%   |
| 2560x1080          | 50       | 0.83%   |
| 1920x540           | 32       | 0.53%   |
| 1024x768 (XGA)     | 30       | 0.5%    |
| 1600x1200          | 22       | 0.37%   |
| 1280x720 (HD)      | 15       | 0.25%   |
| 1280x960           | 12       | 0.2%    |
| 2560x1600          | 10       | 0.17%   |
| 2288x1287          | 10       | 0.17%   |
| 2048x1152          | 7        | 0.12%   |
| Unknown            | 7        | 0.12%   |
| 3840x1080          | 6        | 0.1%    |
| 1280x768           | 5        | 0.08%   |
| 3840x1600          | 3        | 0.05%   |
| 1152x864           | 2        | 0.03%   |
| 8320x1440          | 1        | 0.02%   |
| 6000x1440          | 1        | 0.02%   |
| 5760x2160          | 1        | 0.02%   |
| 5120x1440          | 1        | 0.02%   |
| 4480x2023          | 1        | 0.02%   |
| 3840x1200          | 1        | 0.02%   |
| 3200x1080          | 1        | 0.02%   |
| 2048x1536          | 1        | 0.02%   |
| 1536x2048          | 1        | 0.02%   |
| 1400x1050          | 1        | 0.02%   |
| 1024x600           | 1        | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 908      | 14.79%  |
| 21      | 852      | 13.88%  |
| 27      | 742      | 12.09%  |
| 24      | 729      | 11.88%  |
| 19      | 535      | 8.72%   |
| 18      | 357      | 5.82%   |
| 22      | 302      | 4.92%   |
| 17      | 287      | 4.68%   |
| 31      | 245      | 3.99%   |
| 20      | 227      | 3.7%    |
| Unknown | 114      | 1.86%   |
| 34      | 102      | 1.66%   |
| 84      | 91       | 1.48%   |
| 15      | 91       | 1.48%   |
| 32      | 66       | 1.08%   |
| 40      | 55       | 0.9%    |
| 72      | 52       | 0.85%   |
| 54      | 45       | 0.73%   |
| 25      | 39       | 0.64%   |
| 26      | 30       | 0.49%   |
| 52      | 25       | 0.41%   |
| 28      | 21       | 0.34%   |
| 65      | 17       | 0.28%   |
| 48      | 15       | 0.24%   |
| 39      | 15       | 0.24%   |
| 37      | 14       | 0.23%   |
| 35      | 13       | 0.21%   |
| 33      | 13       | 0.21%   |
| 29      | 13       | 0.21%   |
| 46      | 12       | 0.2%    |
| 42      | 11       | 0.18%   |
| 142     | 8        | 0.13%   |
| 36      | 8        | 0.13%   |
| 12      | 8        | 0.13%   |
| 60      | 7        | 0.11%   |
| 47      | 7        | 0.11%   |
| 43      | 7        | 0.11%   |
| 16      | 7        | 0.11%   |
| 74      | 6        | 0.1%    |
| 55      | 6        | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 2244     | 37.34%  |
| 401-500        | 1989     | 33.1%   |
| 301-350        | 363      | 6.04%   |
| 601-700        | 359      | 5.97%   |
| 351-400        | 307      | 5.11%   |
| 701-800        | 190      | 3.16%   |
| 1501-2000      | 152      | 2.53%   |
| 1001-1500      | 152      | 2.53%   |
| Unknown        | 114      | 1.9%    |
| 801-900        | 98       | 1.63%   |
| 901-1000       | 21       | 0.35%   |
| 201-300        | 12       | 0.2%    |
| More than 2000 | 8        | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 4174     | 70.64%  |
| 16/10   | 861      | 14.57%  |
| 5/4     | 532      | 9%      |
| 21/9    | 115      | 1.95%   |
| 4/3     | 96       | 1.62%   |
| 3/2     | 48       | 0.81%   |
| Unknown | 44       | 0.74%   |
| 6/5     | 13       | 0.22%   |
| 32/9    | 10       | 0.17%   |
| 1.00    | 8        | 0.14%   |
| 2.12    | 2        | 0.03%   |
| 3.20    | 1        | 0.02%   |
| 2.01    | 1        | 0.02%   |
| 2.00    | 1        | 0.02%   |
| 1.96    | 1        | 0.02%   |
| 0.75    | 1        | 0.02%   |
| 0.56    | 1        | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 2283     | 37.67%  |
| 151-200        | 1050     | 17.32%  |
| 301-350        | 763      | 12.59%  |
| 141-150        | 558      | 9.21%   |
| 351-500        | 447      | 7.38%   |
| More than 1000 | 286      | 4.72%   |
| 251-300        | 284      | 4.69%   |
| 501-1000       | 150      | 2.47%   |
| Unknown        | 114      | 1.88%   |
| 101-110        | 68       | 1.12%   |
| 111-120        | 22       | 0.36%   |
| 131-140        | 16       | 0.26%   |
| 71-80          | 8        | 0.13%   |
| 91-100         | 5        | 0.08%   |
| 121-130        | 3        | 0.05%   |
| 81-90          | 2        | 0.03%   |
| 51-60          | 1        | 0.02%   |
| 41-50          | 1        | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 4192     | 70.77%  |
| 101-120 | 1132     | 19.11%  |
| 1-50    | 256      | 4.32%   |
| 121-160 | 160      | 2.7%    |
| Unknown | 114      | 1.92%   |
| 161-240 | 69       | 1.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 5647     | 90.61%  |
| 2     | 443      | 7.11%   |
| 0     | 98       | 1.57%   |
| 3     | 37       | 0.59%   |
| 4     | 5        | 0.08%   |
| 7     | 1        | 0.02%   |
| 5     | 1        | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 4018     | 49.11%  |
| Intel                                 | 2037     | 24.9%   |
| Qualcomm Atheros                      | 605      | 7.4%    |
| Ralink Technology                     | 214      | 2.62%   |
| Broadcom                              | 196      | 2.4%    |
| Nvidia                                | 179      | 2.19%   |
| Ralink                                | 110      | 1.34%   |
| TP-Link                               | 92       | 1.12%   |
| Qualcomm Atheros Communications       | 68       | 0.83%   |
| Marvell Technology Group              | 63       | 0.77%   |
| Broadcom Limited                      | 58       | 0.71%   |
| MediaTek                              | 43       | 0.53%   |
| D-Link System                         | 36       | 0.44%   |
| D-Link                                | 33       | 0.4%    |
| Huawei Technologies                   | 30       | 0.37%   |
| ASUSTek Computer                      | 30       | 0.37%   |
| VIA Technologies                      | 27       | 0.33%   |
| NetGear                               | 26       | 0.32%   |
| Belkin Components                     | 23       | 0.28%   |
| Samsung Electronics                   | 20       | 0.24%   |
| Microsoft                             | 20       | 0.24%   |
| Aquantia                              | 20       | 0.24%   |
| ASIX Electronics                      | 15       | 0.18%   |
| ZTE WCDMA Technologies MSM            | 14       | 0.17%   |
| Motorola PCS                          | 14       | 0.17%   |
| IMC Networks                          | 14       | 0.17%   |
| Edimax Technology                     | 14       | 0.17%   |
| 3Com                                  | 13       | 0.16%   |
| Xiaomi                                | 11       | 0.13%   |
| AVM                                   | 11       | 0.13%   |
| Linksys                               | 10       | 0.12%   |
| OPPO Electronics                      | 7        | 0.09%   |
| Mercucys                              | 5        | 0.06%   |
| JMicron Technology                    | 5        | 0.06%   |
| DisplayLink                           | 5        | 0.06%   |
| ZyDAS                                 | 4        | 0.05%   |
| Wilocity                              | 4        | 0.05%   |
| T & A Mobile Phones                   | 4        | 0.05%   |
| Qualcomm                              | 4        | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4        | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3375     | 37.43%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 239      | 2.65%   |
| Intel I211 Gigabit Network Connection                             | 197      | 2.18%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 188      | 2.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 179      | 1.98%   |
| Intel Ethernet Connection I217-LM                                 | 176      | 1.95%   |
| Intel Wi-Fi 6 AX200                                               | 168      | 1.86%   |
| Intel Ethernet Connection (2) I219-V                              | 160      | 1.77%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 118      | 1.31%   |
| Intel 82579V Gigabit Network Connection                           | 116      | 1.29%   |
| Nvidia MCP61 Ethernet                                             | 105      | 1.16%   |
| Ralink MT7601U Wireless Adapter                                   | 100      | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 90       | 1%      |
| Intel Ethernet Controller I225-V                                  | 88       | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 84       | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 83       | 0.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 81       | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 71       | 0.79%   |
| Intel Ethernet Connection I217-V                                  | 57       | 0.63%   |
| Qualcomm Atheros AR9271 802.11n                                   | 56       | 0.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 55       | 0.61%   |
| Intel Wireless-AC 9260                                            | 53       | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 51       | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 47       | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 43       | 0.48%   |
| Intel Ethernet Connection (2) I218-V                              | 43       | 0.48%   |
| Intel Wireless 7265                                               | 42       | 0.47%   |
| Intel Wireless 3165                                               | 41       | 0.45%   |
| Intel 82574L Gigabit Network Connection                           | 41       | 0.45%   |
| Ralink RT5370 Wireless Adapter                                    | 40       | 0.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 39       | 0.43%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 38       | 0.42%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 37       | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 37       | 0.41%   |
| Intel Wireless 7260                                               | 37       | 0.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 35       | 0.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 35       | 0.39%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 35       | 0.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 35       | 0.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 35       | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 620      | 27.07%  |
| Realtek Semiconductor                 | 582      | 25.41%  |
| Qualcomm Atheros                      | 290      | 12.66%  |
| Ralink Technology                     | 214      | 9.34%   |
| Ralink                                | 110      | 4.8%    |
| TP-Link                               | 84       | 3.67%   |
| Qualcomm Atheros Communications       | 68       | 2.97%   |
| Broadcom                              | 48       | 2.1%    |
| D-Link                                | 33       | 1.44%   |
| MediaTek                              | 32       | 1.4%    |
| ASUSTek Computer                      | 30       | 1.31%   |
| NetGear                               | 24       | 1.05%   |
| Belkin Components                     | 23       | 1%      |
| Microsoft                             | 20       | 0.87%   |
| D-Link System                         | 15       | 0.66%   |
| IMC Networks                          | 14       | 0.61%   |
| Edimax Technology                     | 14       | 0.61%   |
| AVM                                   | 11       | 0.48%   |
| Linksys                               | 10       | 0.44%   |
| Broadcom Limited                      | 6        | 0.26%   |
| Mercucys                              | 5        | 0.22%   |
| ZyDAS                                 | 4        | 0.17%   |
| Wilocity                              | 4        | 0.17%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4        | 0.17%   |
| ZyXEL Communications                  | 2        | 0.09%   |
| Wacom                                 | 2        | 0.09%   |
| Sweex                                 | 2        | 0.09%   |
| PLANEX                                | 2        | 0.09%   |
| Philips (or NXP)                      | 2        | 0.09%   |
| Guillemot                             | 2        | 0.09%   |
| Chu Yuen Enterprise                   | 2        | 0.09%   |
| BUFFALO                               | 2        | 0.09%   |
| VIA Technologies                      | 1        | 0.04%   |
| TRENDnet                              | 1        | 0.04%   |
| Sitecom Europe                        | 1        | 0.04%   |
| Senao                                 | 1        | 0.04%   |
| Realtek                               | 1        | 0.04%   |
| Micro Star International              | 1        | 0.04%   |
| Logitec                               | 1        | 0.04%   |
| LG Electronics                        | 1        | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 168      | 7.28%   |
| Ralink MT7601U Wireless Adapter                                | 100      | 4.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 90       | 3.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 84       | 3.64%   |
| Qualcomm Atheros AR9271 802.11n                                | 56       | 2.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 55       | 2.38%   |
| Intel Wireless-AC 9260                                         | 53       | 2.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 51       | 2.21%   |
| Intel Wireless 7265                                            | 42       | 1.82%   |
| Intel Wireless 3165                                            | 41       | 1.78%   |
| Ralink RT5370 Wireless Adapter                                 | 40       | 1.73%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 39       | 1.69%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 38       | 1.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 37       | 1.6%    |
| Intel Wireless 7260                                            | 37       | 1.6%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 35       | 1.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 35       | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 35       | 1.52%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 33       | 1.43%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 30       | 1.3%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 30       | 1.3%    |
| Realtek 802.11ac NIC                                           | 30       | 1.3%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 28       | 1.21%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 27       | 1.17%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 26       | 1.13%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 26       | 1.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 24       | 1.04%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 23       | 1%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 23       | 1%      |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 21       | 0.91%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 21       | 0.91%   |
| Intel Wireless 8260                                            | 21       | 0.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 20       | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 20       | 0.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 18       | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 17       | 0.74%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 17       | 0.74%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 15       | 0.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 15       | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 15       | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 3830     | 58.72%  |
| Intel                             | 1660     | 25.45%  |
| Qualcomm Atheros                  | 338      | 5.18%   |
| Nvidia                            | 179      | 2.74%   |
| Broadcom                          | 149      | 2.28%   |
| Marvell Technology Group          | 63       | 0.97%   |
| Broadcom Limited                  | 52       | 0.8%    |
| Huawei Technologies               | 28       | 0.43%   |
| VIA Technologies                  | 24       | 0.37%   |
| D-Link System                     | 21       | 0.32%   |
| Aquantia                          | 20       | 0.31%   |
| Samsung Electronics               | 18       | 0.28%   |
| ASIX Electronics                  | 15       | 0.23%   |
| ZTE WCDMA Technologies MSM        | 13       | 0.2%    |
| 3Com                              | 13       | 0.2%    |
| Xiaomi                            | 11       | 0.17%   |
| MediaTek                          | 11       | 0.17%   |
| TP-Link                           | 10       | 0.15%   |
| Motorola PCS                      | 8        | 0.12%   |
| OPPO Electronics                  | 7        | 0.11%   |
| JMicron Technology                | 5        | 0.08%   |
| DisplayLink                       | 5        | 0.08%   |
| T & A Mobile Phones               | 4        | 0.06%   |
| Qualcomm                          | 4        | 0.06%   |
| Silicon Integrated Systems [SiS]  | 3        | 0.05%   |
| Mellanox Technologies             | 3        | 0.05%   |
| HTC (High Tech Computer)          | 3        | 0.05%   |
| Sundance Technology Inc / IC Plus | 2        | 0.03%   |
| Spreadtrum Communications         | 2        | 0.03%   |
| OnePlus Technology (Shenzhen)     | 2        | 0.03%   |
| NetGear                           | 2        | 0.03%   |
| LG Electronics                    | 2        | 0.03%   |
| ICS Advent                        | 2        | 0.03%   |
| HMD Global                        | 2        | 0.03%   |
| vivo                              | 1        | 0.02%   |
| SysKonnect                        | 1        | 0.02%   |
| Netchip Technology                | 1        | 0.02%   |
| Lenovo                            | 1        | 0.02%   |
| IBM                               | 1        | 0.02%   |
| Foxconn / Hon Hai                 | 1        | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3375     | 50.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 239      | 3.58%   |
| Intel I211 Gigabit Network Connection                             | 197      | 2.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 188      | 2.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 179      | 2.68%   |
| Intel Ethernet Connection I217-LM                                 | 176      | 2.64%   |
| Intel Ethernet Connection (2) I219-V                              | 160      | 2.4%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 118      | 1.77%   |
| Intel 82579V Gigabit Network Connection                           | 116      | 1.74%   |
| Nvidia MCP61 Ethernet                                             | 105      | 1.57%   |
| Intel Ethernet Controller I225-V                                  | 88       | 1.32%   |
| Intel Ethernet Connection (7) I219-V                              | 83       | 1.24%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 81       | 1.21%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 71       | 1.06%   |
| Intel Ethernet Connection I217-V                                  | 57       | 0.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 47       | 0.7%    |
| Intel Ethernet Connection (2) I219-LM                             | 43       | 0.64%   |
| Intel Ethernet Connection (2) I218-V                              | 43       | 0.64%   |
| Intel 82574L Gigabit Network Connection                           | 41       | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 37       | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 35       | 0.52%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 35       | 0.52%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 32       | 0.48%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 31       | 0.46%   |
| Intel 82578DM Gigabit Network Connection                          | 28       | 0.42%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 28       | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 27       | 0.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26       | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 26       | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 25       | 0.37%   |
| Intel 82578DC Gigabit Network Connection                          | 24       | 0.36%   |
| Intel Ethernet Connection (14) I219-V                             | 23       | 0.34%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 23       | 0.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 21       | 0.31%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 21       | 0.31%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 18       | 0.27%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 16       | 0.24%   |
| Nvidia MCP77 Ethernet                                             | 16       | 0.24%   |
| Intel Ethernet Connection (2) I218-LM                             | 16       | 0.24%   |
| Intel Ethernet Connection (11) I219-V                             | 16       | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 6143     | 73.38%  |
| WiFi     | 2197     | 26.24%  |
| Modem    | 19       | 0.23%   |
| Unknown  | 13       | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 5189     | 84.51%  |
| WiFi     | 951      | 15.49%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 4436     | 71.27%  |
| 2     | 1583     | 25.43%  |
| 3     | 138      | 2.22%   |
| 0     | 47       | 0.76%   |
| 4     | 16       | 0.26%   |
| 5     | 2        | 0.03%   |
| 7     | 1        | 0.02%   |
| 6     | 1        | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Desktops | Percent |
|---------|----------|---------|
| No      | 4573     | 72.91%  |
| Yes     | 1698     | 27.07%  |
| Unknown | 1        | 0.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 563      | 38.43%  |
| Cambridge Silicon Radio         | 412      | 28.12%  |
| Realtek Semiconductor           | 127      | 8.67%   |
| ASUSTek Computer                | 91       | 6.21%   |
| Broadcom                        | 69       | 4.71%   |
| Qualcomm Atheros Communications | 52       | 3.55%   |
| IMC Networks                    | 41       | 2.8%    |
| MediaTek                        | 20       | 1.37%   |
| Lite-On Technology              | 12       | 0.82%   |
| Integrated System Solution      | 11       | 0.75%   |
| TP-Link                         | 10       | 0.68%   |
| Belkin Components               | 9        | 0.61%   |
| Apple                           | 9        | 0.61%   |
| Dynex                           | 6        | 0.41%   |
| Primax Electronics              | 5        | 0.34%   |
| Ralink                          | 4        | 0.27%   |
| Realtek                         | 3        | 0.2%    |
| Foxconn / Hon Hai               | 3        | 0.2%    |
| Micro Star International        | 2        | 0.14%   |
| ISSC                            | 2        | 0.14%   |
| Hewlett-Packard                 | 2        | 0.14%   |
| Edimax Technology               | 2        | 0.14%   |
| Dell                            | 2        | 0.14%   |
| Accel Semiconductor             | 2        | 0.14%   |
| Unknown                         | 2        | 0.14%   |
| Unknown                         | 1        | 0.07%   |
| SINO WEALTH                     | 1        | 0.07%   |
| Qcom                            | 1        | 0.07%   |
| i.Tech Dynamic Limited          | 1        | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 412      | 28.07%  |
| Intel Bluetooth wireless interface                       | 156      | 10.63%  |
| Intel AX200 Bluetooth                                    | 156      | 10.63%  |
| Intel Wireless-AC 3168 Bluetooth                         | 80       | 5.45%   |
| Realtek Bluetooth Radio                                  | 78       | 5.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 45       | 3.07%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 41       | 2.79%   |
| Intel AX201 Bluetooth                                    | 37       | 2.52%   |
| Realtek  Bluetooth 4.2 Adapter                           | 36       | 2.45%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 36       | 2.45%   |
| Intel AX210 Bluetooth                                    | 34       | 2.32%   |
| IMC Networks Bluetooth Radio                             | 29       | 1.98%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 26       | 1.77%   |
| Qualcomm Atheros  Bluetooth Device                       | 25       | 1.7%    |
| MediaTek Wireless_Device                                 | 20       | 1.36%   |
| ASUS ASUS USB-BT500                                      | 18       | 1.23%   |
| ASUS Bluetooth Radio                                     | 14       | 0.95%   |
| TP-Link UB500 Adapter                                    | 10       | 0.68%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 10       | 0.68%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 9        | 0.61%   |
| Lite-On Bluetooth Device                                 | 8        | 0.54%   |
| Integrated System Solution Bluetooth Device              | 8        | 0.54%   |
| ASUS Qualcomm Bluetooth 4.1                              | 8        | 0.54%   |
| ASUS Bluetooth Adapter                                   | 8        | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 7        | 0.48%   |
| Belkin Components Bluetooth Mini Dongle                  | 7        | 0.48%   |
| ASUS Bluetooth Device                                    | 7        | 0.48%   |
| Realtek RTL8821A Bluetooth                               | 6        | 0.41%   |
| Intel Bluetooth Device                                   | 6        | 0.41%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 6        | 0.41%   |
| Broadcom BCM2045 Bluetooth                               | 6        | 0.41%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter            | 5        | 0.34%   |
| IMC Networks Wireless_Device                             | 5        | 0.34%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 5        | 0.34%   |
| ASUS BCM20702A0                                          | 5        | 0.34%   |
| Ralink RT3290 Bluetooth                                  | 4        | 0.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 4        | 0.27%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 4        | 0.27%   |
| IMC Networks Bluetooth Device                            | 4        | 0.27%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                  | 3        | 0.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| Intel                                | 3863     | 40.5%   |
| AMD                                  | 2557     | 26.81%  |
| Nvidia                               | 2134     | 22.37%  |
| C-Media Electronics                  | 225      | 2.36%   |
| Creative Labs                        | 171      | 1.79%   |
| Logitech                             | 65       | 0.68%   |
| Texas Instruments                    | 45       | 0.47%   |
| JMTek                                | 33       | 0.35%   |
| Generalplus Technology               | 31       | 0.32%   |
| Creative Technology                  | 29       | 0.3%    |
| VIA Technologies                     | 27       | 0.28%   |
| ASUSTek Computer                     | 24       | 0.25%   |
| Tenx Technology                      | 16       | 0.17%   |
| Razer USA                            | 16       | 0.17%   |
| Kingston Technology                  | 12       | 0.13%   |
| GN Netcom                            | 12       | 0.13%   |
| Focusrite-Novation                   | 10       | 0.1%    |
| SteelSeries ApS                      | 9        | 0.09%   |
| KTMicro                              | 9        | 0.09%   |
| XMOS                                 | 8        | 0.08%   |
| Plantronics                          | 8        | 0.08%   |
| Giga-Byte Technology                 | 8        | 0.08%   |
| PreSonus Audio Electronics           | 7        | 0.07%   |
| Micro Star International             | 7        | 0.07%   |
| Dell                                 | 7        | 0.07%   |
| Yamaha                               | 6        | 0.06%   |
| Samson Technologies                  | 6        | 0.06%   |
| Corsair                              | 6        | 0.06%   |
| Blue Microphones                     | 6        | 0.06%   |
| Thesycon Systemsoftware & Consulting | 5        | 0.05%   |
| Sony                                 | 5        | 0.05%   |
| SAVITECH                             | 5        | 0.05%   |
| M-Audio                              | 5        | 0.05%   |
| Hewlett-Packard                      | 5        | 0.05%   |
| GYROCOM C&C                          | 5        | 0.05%   |
| Ensoniq                              | 5        | 0.05%   |
| BEHRINGER International              | 5        | 0.05%   |
| Trust                                | 4        | 0.04%   |
| ROCCAT                               | 4        | 0.04%   |
| Guangzhou FiiO Electronics           | 4        | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 552      | 4.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 546      | 4.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 532      | 4.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 405      | 3.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 400      | 3.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 380      | 3.37%   |
| AMD Family 17h/19h HD Audio Controller                                            | 374      | 3.32%   |
| AMD Starship/Matisse HD Audio Controller                                          | 366      | 3.24%   |
| AMD FCH Azalia Controller                                                         | 340      | 3.01%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 290      | 2.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 272      | 2.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 259      | 2.3%    |
| Intel 200 Series PCH HD Audio                                                     | 237      | 2.1%    |
| Nvidia High Definition Audio Controller                                           | 202      | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 197      | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 195      | 1.73%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 189      | 1.68%   |
| Intel Cannon Lake PCH cAVS                                                        | 186      | 1.65%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 164      | 1.45%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 161      | 1.43%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 150      | 1.33%   |
| Nvidia GF108 High Definition Audio Controller                                     | 146      | 1.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 145      | 1.29%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                               | 131      | 1.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 121      | 1.07%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                      | 117      | 1.04%   |
| Nvidia MCP61 High Definition Audio                                                | 116      | 1.03%   |
| Nvidia GF119 HDMI Audio Controller                                                | 112      | 0.99%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 106      | 0.94%   |
| Nvidia GP108 High Definition Audio Controller                                     | 105      | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                                     | 104      | 0.92%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 100      | 0.89%   |
| Nvidia GP106 High Definition Audio Controller                                     | 99       | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                                | 92       | 0.82%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 86       | 0.76%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 86       | 0.76%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 85       | 0.75%   |
| AMD Trinity HDMI Audio Controller                                                 | 81       | 0.72%   |
| AMD Navi 10 HDMI Audio                                                            | 78       | 0.69%   |
| AMD Kabini HDMI/DP Audio                                                          | 76       | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 1396     | 19.16%  |
| Kingston            | 1318     | 18.09%  |
| Samsung Electronics | 754      | 10.35%  |
| Corsair             | 590      | 8.1%    |
| SK hynix            | 578      | 7.93%   |
| Crucial             | 525      | 7.21%   |
| G.Skill             | 437      | 6%      |
| Micron Technology   | 376      | 5.16%   |
| A-DATA Technology   | 159      | 2.18%   |
| Nanya Technology    | 108      | 1.48%   |
| Team                | 90       | 1.24%   |
| Patriot             | 90       | 1.24%   |
| Unknown             | 85       | 1.17%   |
| Ramaxel Technology  | 70       | 0.96%   |
| GOODRAM             | 64       | 0.88%   |
| Elpida              | 60       | 0.82%   |
| Transcend           | 37       | 0.51%   |
| Smart               | 33       | 0.45%   |
| Apacer              | 33       | 0.45%   |
| AMD                 | 33       | 0.45%   |
| Kingmax             | 24       | 0.33%   |
| GeIL                | 22       | 0.3%    |
| Unifosa             | 20       | 0.27%   |
| Silicon Power       | 20       | 0.27%   |
| Unknown (ABCD)      | 19       | 0.26%   |
| Qimonda             | 14       | 0.19%   |
| PNY                 | 12       | 0.16%   |
| Multilaser          | 12       | 0.16%   |
| Avant               | 12       | 0.16%   |
| Toshiba             | 8        | 0.11%   |
| Teikon              | 8        | 0.11%   |
| CSX                 | 7        | 0.1%    |
| Atermiter           | 7        | 0.1%    |
| Timetec             | 6        | 0.08%   |
| OCZ                 | 6        | 0.08%   |
| Kreton              | 6        | 0.08%   |
| Kllisre             | 6        | 0.08%   |
| KLEVV               | 6        | 0.08%   |
| Goldkey             | 6        | 0.08%   |
| Foxline             | 6        | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Unknown RAM Module 2GB DIMM 800MT/s                    | 99       | 1.22%   |
| Unknown RAM Module 2GB DIMM SDRAM                      | 96       | 1.19%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 94       | 1.16%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 90       | 1.11%   |
| Unknown                                                | 85       | 1.05%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 68       | 0.84%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 62       | 0.77%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 57       | 0.7%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 50       | 0.62%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s    | 48       | 0.59%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s               | 47       | 0.58%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                   | 46       | 0.57%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 46       | 0.57%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 46       | 0.57%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s   | 44       | 0.54%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s         | 43       | 0.53%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s              | 41       | 0.51%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 41       | 0.51%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s               | 39       | 0.48%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 36       | 0.44%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s   | 35       | 0.43%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s    | 33       | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s              | 32       | 0.4%    |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 32       | 0.4%    |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 32       | 0.4%    |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s               | 30       | 0.37%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 30       | 0.37%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s      | 30       | 0.37%   |
| Unknown RAM Module 1GB DIMM 800MT/s                    | 29       | 0.36%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s    | 29       | 0.36%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s  | 29       | 0.36%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                   | 28       | 0.35%   |
| Unknown RAM Module 4GB DIMM SDRAM                      | 28       | 0.35%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s    | 28       | 0.35%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s              | 27       | 0.33%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s              | 27       | 0.33%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s    | 27       | 0.33%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s    | 27       | 0.33%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s | 27       | 0.33%   |
| Unknown RAM Module 1GB DIMM 667MT/s                    | 26       | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 2541     | 40.33%  |
| DDR4    | 2137     | 33.92%  |
| Unknown | 575      | 9.13%   |
| DDR2    | 482      | 7.65%   |
| SDRAM   | 428      | 6.79%   |
| DDR     | 93       | 1.48%   |
| LPDDR4  | 22       | 0.35%   |
| DDR5    | 18       | 0.29%   |
| DRAM    | 3        | 0.05%   |
| LPDDR3  | 2        | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 5767     | 93.93%  |
| SODIMM       | 355      | 5.78%   |
| RIMM         | 10       | 0.16%   |
| FB-DIMM      | 7        | 0.11%   |
| Row Of Chips | 1        | 0.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 2241     | 32.09%  |
| 4096  | 2139     | 30.63%  |
| 2048  | 1432     | 20.51%  |
| 16384 | 551      | 7.89%   |
| 1024  | 437      | 6.26%   |
| 32768 | 117      | 1.68%   |
| 512   | 61       | 0.87%   |
| 256   | 2        | 0.03%   |
| 3072  | 1        | 0.01%   |
| 64    | 1        | 0.01%   |
| 32    | 1        | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 1513     | 21.41%  |
| 1333    | 1085     | 15.36%  |
| 800     | 412      | 5.83%   |
| 2400    | 386      | 5.46%   |
| 3200    | 365      | 5.17%   |
| 2667    | 335      | 4.74%   |
| 3600    | 317      | 4.49%   |
| 2133    | 288      | 4.08%   |
| 667     | 281      | 3.98%   |
| Unknown | 233      | 3.3%    |
| 1867    | 158      | 2.24%   |
| 1866    | 127      | 1.8%    |
| 2666    | 109      | 1.54%   |
| 3400    | 97       | 1.37%   |
| 1066    | 97       | 1.37%   |
| 1800    | 93       | 1.32%   |
| 3000    | 86       | 1.22%   |
| 2933    | 82       | 1.16%   |
| 400     | 81       | 1.15%   |
| 1067    | 69       | 0.98%   |
| 533     | 58       | 0.82%   |
| 3800    | 40       | 0.57%   |
| 3733    | 40       | 0.57%   |
| 3866    | 39       | 0.55%   |
| 1334    | 39       | 0.55%   |
| 2800    | 38       | 0.54%   |
| 3533    | 35       | 0.5%    |
| 3266    | 35       | 0.5%    |
| 2048    | 34       | 0.48%   |
| 3466    | 32       | 0.45%   |
| 3666    | 28       | 0.4%    |
| 2000    | 26       | 0.37%   |
| 1648    | 23       | 0.33%   |
| 49926   | 22       | 0.31%   |
| 333     | 22       | 0.31%   |
| 3066    | 19       | 0.27%   |
| 2200    | 19       | 0.27%   |
| 1639    | 18       | 0.25%   |
| 3333    | 16       | 0.23%   |
| 2733    | 16       | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 151      | 39.02%  |
| Brother Industries    | 83       | 21.45%  |
| Canon                 | 52       | 13.44%  |
| Seiko Epson           | 35       | 9.04%   |
| Samsung Electronics   | 34       | 8.79%   |
| Lexmark International | 8        | 2.07%   |
| QinHeng Electronics   | 5        | 1.29%   |
| Prolific Technology   | 5        | 1.29%   |
| Kyocera               | 3        | 0.78%   |
| Dymo-CoStar           | 3        | 0.78%   |
| Xerox                 | 2        | 0.52%   |
| Ricoh                 | 2        | 0.52%   |
| Zebra                 | 1        | 0.26%   |
| Oki Data              | 1        | 0.26%   |
| NXP Semiconductors    | 1        | 0.26%   |
| Citizen               | 1        | 0.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| HP DeskJet 2600 series               | 7        | 1.78%   |
| HP ENVY 4520 series                  | 6        | 1.53%   |
| HP DeskJet 2700 series               | 6        | 1.53%   |
| Brother HL-L2390DW                   | 6        | 1.53%   |
| Samsung M2070 Series                 | 5        | 1.27%   |
| Samsung M2020 Series                 | 5        | 1.27%   |
| QinHeng CH340S                       | 5        | 1.27%   |
| Prolific PL2305 Parallel Port        | 5        | 1.27%   |
| HP DeskJet 3630 series               | 5        | 1.27%   |
| HP DeskJet 2130 series               | 5        | 1.27%   |
| Samsung ML-1640 Series Laser Printer | 4        | 1.02%   |
| HP LaserJet P1006                    | 4        | 1.02%   |
| HP LaserJet P1005                    | 4        | 1.02%   |
| HP LaserJet 1018                     | 4        | 1.02%   |
| HP Ink Tank Wireless 410 series      | 4        | 1.02%   |
| Canon PIXMA MX920 Series             | 4        | 1.02%   |
| Brother Printer                      | 4        | 1.02%   |
| Seiko Epson L365 Series              | 3        | 0.76%   |
| Seiko Epson L120 Series              | 3        | 0.76%   |
| Seiko Epson ET-2710 Series           | 3        | 0.76%   |
| HP LaserJet Pro M148f-M149f          | 3        | 0.76%   |
| HP LaserJet 1020                     | 3        | 0.76%   |
| HP LaserJet 1010                     | 3        | 0.76%   |
| HP Deskjet 1050 J410                 | 3        | 0.76%   |
| Canon TS5100 series                  | 3        | 0.76%   |
| Canon PIXMA MG3600 Series            | 3        | 0.76%   |
| Canon LiDE 300                       | 3        | 0.76%   |
| Brother MFC-L2710DW series           | 3        | 0.76%   |
| Brother MFC-J470DW                   | 3        | 0.76%   |
| Brother HL-L2360D series             | 3        | 0.76%   |
| Brother HL-3140CW series             | 3        | 0.76%   |
| Brother DCP-T310                     | 3        | 0.76%   |
| Seiko Epson XP-243 245 247 Series    | 2        | 0.51%   |
| Seiko Epson WF-2510 Series           | 2        | 0.51%   |
| Seiko Epson L6160 Series             | 2        | 0.51%   |
| Seiko Epson ET-4760 Series           | 2        | 0.51%   |
| Samsung SCX-3400 Series              | 2        | 0.51%   |
| Samsung ML-2010P Mono Laser Printer  | 2        | 0.51%   |
| Samsung M267x 287x Series            | 2        | 0.51%   |
| Samsung CLP-310 Color Laser Printer  | 2        | 0.51%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Canon                       | 44       | 55.7%   |
| Hewlett-Packard             | 11       | 13.92%  |
| Seiko Epson                 | 9        | 11.39%  |
| Mustek Systems              | 7        | 8.86%   |
| AGFA-Gevaert NV             | 3        | 3.8%    |
| KYE Systems (Mouse Systems) | 2        | 2.53%   |
| Plustek                     | 1        | 1.27%   |
| Fujitsu                     | 1        | 1.27%   |
| Acer Peripherals (now BenQ) | 1        | 1.27%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 210                                  | 7        | 8.86%   |
| Canon CanoScan LiDE 110                                  | 6        | 7.59%   |
| Canon CanoScan LiDE 100                                  | 6        | 7.59%   |
| Canon CanoScan LiDE 120                                  | 4        | 5.06%   |
| Mustek Systems ScanExpress 1200 UB                       | 3        | 3.8%    |
| Canon CanoScan LIDE 25                                   | 3        | 3.8%    |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 2        | 2.53%   |
| HP ScanJet 4500C/5550C                                   | 2        | 2.53%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2        | 2.53%   |
| Canon CanoScan N1240U/LiDE 30                            | 2        | 2.53%   |
| Canon CanoScan LiDE 70                                   | 2        | 2.53%   |
| Canon CanoScan LiDE 60                                   | 2        | 2.53%   |
| Canon CanoScan LiDE 220                                  | 2        | 2.53%   |
| Canon CanoScan LiDE 200                                  | 2        | 2.53%   |
| AGFA-Gevaert NV SnapScan e20                             | 2        | 2.53%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]              | 1        | 1.27%   |
| Seiko Epson GT-X770 [Perfection V500]                    | 1        | 1.27%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]  | 1        | 1.27%   |
| Seiko Epson GT-F700 [Perfection V350]                    | 1        | 1.27%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]        | 1        | 1.27%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1        | 1.27%   |
| Seiko Epson GT-7400U [Perfection 1270]                   | 1        | 1.27%   |
| Plustek 600DPI USB Scanner                               | 1        | 1.27%   |
| Mustek Systems SNAPSCAN e22                              | 1        | 1.27%   |
| Mustek Systems ScanExpress 1200 CU                       | 1        | 1.27%   |
| Mustek Systems BearPaw 2448 CU Pro                       | 1        | 1.27%   |
| Mustek Systems BearPaw 1200 CU Plus                      | 1        | 1.27%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1        | 1.27%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE      | 1        | 1.27%   |
| HP ScanJet G4010                                         | 1        | 1.27%   |
| HP ScanJet 4570c                                         | 1        | 1.27%   |
| HP ScanJet 4370                                          | 1        | 1.27%   |
| HP ScanJet 3800c                                         | 1        | 1.27%   |
| HP ScanJet 3670                                          | 1        | 1.27%   |
| HP ScanJet 2400c                                         | 1        | 1.27%   |
| HP ScanJet 2300c                                         | 1        | 1.27%   |
| HP ScanJet 2200c                                         | 1        | 1.27%   |
| HP PSC 1200                                              | 1        | 1.27%   |
| Fujitsu ScanSnap SV600                                   | 1        | 1.27%   |
| Canon CanoScan N650U/N656U                               | 1        | 1.27%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Logitech                               | 314      | 36.77%  |
| Microdia                               | 73       | 8.55%   |
| Microsoft                              | 57       | 6.67%   |
| Chicony Electronics                    | 30       | 3.51%   |
| Z-Star Microelectronics                | 29       | 3.4%    |
| Realtek Semiconductor                  | 20       | 2.34%   |
| Generalplus Technology                 | 20       | 2.34%   |
| Sunplus Innovation Technology          | 19       | 2.22%   |
| GEMBIRD                                | 19       | 2.22%   |
| Aveo Technology                        | 17       | 1.99%   |
| Samsung Electronics                    | 16       | 1.87%   |
| KYE Systems (Mouse Systems)            | 16       | 1.87%   |
| Creative Technology                    | 16       | 1.87%   |
| ARC International                      | 14       | 1.64%   |
| Cubeternet                             | 13       | 1.52%   |
| Apple                                  | 12       | 1.41%   |
| Jieli Technology                       | 11       | 1.29%   |
| Hewlett-Packard                        | 11       | 1.29%   |
| Huawei Technologies                    | 9        | 1.05%   |
| Trust                                  | 8        | 0.94%   |
| Alcor Micro                            | 7        | 0.82%   |
| Unknown                                | 6        | 0.7%    |
| Genesys Logic                          | 6        | 0.7%    |
| Arkmicro Technologies                  | 6        | 0.7%    |
| A4Tech                                 | 6        | 0.7%    |
| webcam                                 | 5        | 0.59%   |
| WaveRider Communications               | 5        | 0.59%   |
| Pixart Imaging                         | 5        | 0.59%   |
| MacroSilicon                           | 5        | 0.59%   |
| AVerMedia Technologies                 | 5        | 0.59%   |
| Sonix Technology                       | 4        | 0.47%   |
| Razer USA                              | 4        | 0.47%   |
| IMC Networks                           | 4        | 0.47%   |
| WCM_USB                                | 3        | 0.35%   |
| Silicon Motion                         | 3        | 0.35%   |
| LG Electronics                         | 3        | 0.35%   |
| Guillemot                              | 3        | 0.35%   |
| Cheng Uei Precision Industry (Foxlink) | 3        | 0.35%   |
| USB3.0 HD Audio Capture                | 2        | 0.23%   |
| Tobii Technology AB                    | 2        | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 78       | 9.11%   |
| Logitech HD Pro Webcam C920                       | 42       | 4.91%   |
| Logitech Webcam C310                              | 31       | 3.62%   |
| Logitech HD Webcam C525                           | 27       | 3.15%   |
| Microsoft LifeCam HD-3000                         | 21       | 2.45%   |
| Logitech Webcam C170                              | 19       | 2.22%   |
| Generalplus GENERAL WEBCAM                        | 17       | 1.99%   |
| Samsung Galaxy series, misc. (MTP mode)           | 16       | 1.87%   |
| Microdia Camera                                   | 16       | 1.87%   |
| Microdia Webcam Vitade AF                         | 14       | 1.64%   |
| ARC International Camera                          | 14       | 1.64%   |
| Aveo USB2.0 Camera                                | 13       | 1.52%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 12       | 1.4%    |
| Microdia CameraA                                  | 11       | 1.29%   |
| Logitech QuickCam Pro 9000                        | 11       | 1.29%   |
| Logitech HD Webcam C615                           | 11       | 1.29%   |
| Jieli USB PHY 2.0                                 | 11       | 1.29%   |
| Microdia Sonix USB 2.0 Camera                     | 10       | 1.17%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 10       | 1.17%   |
| Logitech C922 Pro Stream Webcam                   | 9        | 1.05%   |
| Huawei UVC Camera                                 | 9        | 1.05%   |
| GEMBIRD USB2.0 PC CAMERA                          | 9        | 1.05%   |
| Z-Star A4 TECH USB2.0 PC Camera E                 | 8        | 0.93%   |
| Microdia Integrated Camera                        | 8        | 0.93%   |
| Logitech HD Webcam C910                           | 8        | 0.93%   |
| Cubeternet USB2.0 Camera                          | 8        | 0.93%   |
| Microsoft LifeCam Cinema                          | 7        | 0.82%   |
| Microdia USB 2.0 Camera                           | 7        | 0.82%   |
| Z-Star Venus USB2.0 Camera                        | 6        | 0.7%    |
| Z-Star A4 TECH USB2.0 PC Camera J                 | 6        | 0.7%    |
| Microsoft LifeCam HD-5000                         | 6        | 0.7%    |
| Logitech Webcam C930e                             | 6        | 0.7%    |
| Logitech Webcam C250                              | 6        | 0.7%    |
| Logitech HD Webcam C510                           | 6        | 0.7%    |
| Creative Live! Cam Sync HD [VF0770]               | 6        | 0.7%    |
| Chicony HP High Definition 1MP Webcam             | 6        | 0.7%    |
| Alcor Micro USB 2.0 PC Camera                     | 6        | 0.7%    |
| webcam webcam                                     | 5        | 0.58%   |
| WaveRider USB 2.0 Camera                          | 5        | 0.58%   |
| Unknown HD camera                                 | 5        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| AuthenTec             | 3        | 37.5%   |
| Upek                  | 2        | 25%     |
| Validity Sensors      | 1        | 12.5%   |
| LighTuning Technology | 1        | 12.5%   |
| DigitalPersona        | 1        | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2        | 25%     |
| AuthenTec AES1600                                      | 2        | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor           | 1        | 12.5%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1        | 12.5%   |
| DigitalPersona Fingerprint Reader                      | 1        | 12.5%   |
| AuthenTec Fingerprint Sensor                           | 1        | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Alcor Micro                       | 6        | 19.35%  |
| SCM Microsystems                  | 5        | 16.13%  |
| Gemalto (was Gemplus)             | 4        | 12.9%   |
| Realtek Semiconductor             | 3        | 9.68%   |
| BIT4ID                            | 3        | 9.68%   |
| Reiner SCT Kartensysteme          | 2        | 6.45%   |
| OmniKey                           | 2        | 6.45%   |
| Advanced Card Systems             | 2        | 6.45%   |
| VASCO Data Security International | 1        | 3.23%   |
| Fujitsu Siemens Computers         | 1        | 3.23%   |
| Cherry                            | 1        | 3.23%   |
| Castles Technology                | 1        | 3.23%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                        | 4        | 12.9%   |
| Realtek Semiconductor Smart Card Reader Interface                          | 3        | 9.68%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                          | 3        | 9.68%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader | 2        | 6.45%   |
| BIT4ID miniLector EVO                                                      | 2        | 6.45%   |
| Alcor Micro Watchdata W 1981                                               | 2        | 6.45%   |
| Advanced Card Systems ACR38 SmartCard Reader                               | 2        | 6.45%   |
| VASCO Data Security International Digipass 905 SmartCard Reader            | 1        | 3.23%   |
| SCM Microsystems uTrust 3700 F CL Reader                                   | 1        | 3.23%   |
| SCM Microsystems SCR335 SmartCard Reader                                   | 1        | 3.23%   |
| SCM Microsystems SCR333 SmartCard Reader                                   | 1        | 3.23%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                     | 1        | 3.23%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                            | 1        | 3.23%   |
| OmniKey CardMan 3021 / 3121                                                | 1        | 3.23%   |
| OmniKey CardMan 1021                                                       | 1        | 3.23%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                           | 1        | 3.23%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                              | 1        | 3.23%   |
| Cherry Smart Terminal XX44                                                 | 1        | 3.23%   |
| Castles Technology EZCCID Smart Card Reader                                | 1        | 3.23%   |
| BIT4ID miniLector AIR NFC v3                                               | 1        | 3.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 5655     | 90.74%  |
| 1     | 536      | 8.6%    |
| 2     | 34       | 0.55%   |
| 3     | 4        | 0.06%   |
| 7     | 1        | 0.02%   |
| 6     | 1        | 0.02%   |
| 4     | 1        | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 275      | 44.64%  |
| Net/wireless             | 133      | 21.59%  |
| Unassigned class         | 45       | 7.31%   |
| Communication controller | 35       | 5.68%   |
| Multimedia controller    | 33       | 5.36%   |
| Chipcard                 | 29       | 4.71%   |
| Camera                   | 16       | 2.6%    |
| Bluetooth                | 13       | 2.11%   |
| Fingerprint reader       | 8        | 1.3%    |
| Network                  | 6        | 0.97%   |
| Card reader              | 5        | 0.81%   |
| Sound                    | 4        | 0.65%   |
| Wireless                 | 3        | 0.49%   |
| Net/ethernet             | 3        | 0.49%   |
| Modem                    | 3        | 0.49%   |
| Storage/raid             | 2        | 0.32%   |
| Storage/ata              | 2        | 0.32%   |
| Unclassified device      | 1        | 0.16%   |

