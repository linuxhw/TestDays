Pop!_OS 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

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

Total: 4557

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | F5N                         | [b04fac9072](https://linux-hardware.org/?probe=b04fac9072) | Jan 06, 2025 |
| Dell          | Latitude 5320               | [c7f4eada6c](https://linux-hardware.org/?probe=c7f4eada6c) | Jan 06, 2025 |
| Lenovo        | ThinkPad T440s 20ARS46M0... | [17ac336e9c](https://linux-hardware.org/?probe=17ac336e9c) | Jan 05, 2025 |
| Lenovo        | ThinkPad T540p 20BFS0Y00... | [8e40087118](https://linux-hardware.org/?probe=8e40087118) | Jan 05, 2025 |
| Apple         | MacBookPro12,1              | [0699689325](https://linux-hardware.org/?probe=0699689325) | Jan 05, 2025 |
| ASUSTek       | X71Sr                       | [c76c5d5a1c](https://linux-hardware.org/?probe=c76c5d5a1c) | Jan 05, 2025 |
| Apple         | MacBookPro11,1              | [e994e68b69](https://linux-hardware.org/?probe=e994e68b69) | Jan 05, 2025 |
| Apple         | MacBookPro5,5               | [de39de3147](https://linux-hardware.org/?probe=de39de3147) | Jan 05, 2025 |
| Apple         | MacBookPro11,1              | [370a49426e](https://linux-hardware.org/?probe=370a49426e) | Jan 04, 2025 |
| ASUSTek       | X71Sr                       | [c17afe99ee](https://linux-hardware.org/?probe=c17afe99ee) | Jan 03, 2025 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [427c508e21](https://linux-hardware.org/?probe=427c508e21) | Jan 03, 2025 |
| System76      | Oryx Pro                    | [3e45c3caac](https://linux-hardware.org/?probe=3e45c3caac) | Jan 02, 2025 |
| Dell          | Inspiron 3558               | [06fdffd5e6](https://linux-hardware.org/?probe=06fdffd5e6) | Jan 02, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [3bb27ee500](https://linux-hardware.org/?probe=3bb27ee500) | Jan 02, 2025 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [f2f5dbd7b9](https://linux-hardware.org/?probe=f2f5dbd7b9) | Jan 01, 2025 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [497be29097](https://linux-hardware.org/?probe=497be29097) | Jan 01, 2025 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8782970610](https://linux-hardware.org/?probe=8782970610) | Jan 01, 2025 |
| Dell          | Inspiron 7520               | [d24db96b79](https://linux-hardware.org/?probe=d24db96b79) | Jan 01, 2025 |
| Dell          | G15 5520                    | [19d5a43273](https://linux-hardware.org/?probe=19d5a43273) | Jan 01, 2025 |
| Apple         | MacBookPro9,2               | [e6da658e0f](https://linux-hardware.org/?probe=e6da658e0f) | Jan 01, 2025 |
| Acer          | Aspire ES1-572              | [419ddbb177](https://linux-hardware.org/?probe=419ddbb177) | Dec 31, 2024 |
| Acer          | Aspire ES1-572              | [dc58f6466e](https://linux-hardware.org/?probe=dc58f6466e) | Dec 31, 2024 |
| Acer          | Aspire A114-32              | [3af2175d58](https://linux-hardware.org/?probe=3af2175d58) | Dec 31, 2024 |
| Apple         | MacBookAir6,2               | [903e299f16](https://linux-hardware.org/?probe=903e299f16) | Dec 30, 2024 |
| Apple         | MacBookPro9,2               | [a509973046](https://linux-hardware.org/?probe=a509973046) | Dec 30, 2024 |
| Apple         | MacBookPro9,2               | [1e4cb7054c](https://linux-hardware.org/?probe=1e4cb7054c) | Dec 30, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b16417fac3](https://linux-hardware.org/?probe=b16417fac3) | Dec 30, 2024 |
| HP            | EliteBook 840 Aero G8 No... | [af5219d90f](https://linux-hardware.org/?probe=af5219d90f) | Dec 30, 2024 |
| Acer          | Aspire A515-57              | [4bccbc5b01](https://linux-hardware.org/?probe=4bccbc5b01) | Dec 29, 2024 |
| ASUSTek       | TP500LN                     | [beeccb21e7](https://linux-hardware.org/?probe=beeccb21e7) | Dec 29, 2024 |
| ASUSTek       | TP500LN                     | [e71efdddcc](https://linux-hardware.org/?probe=e71efdddcc) | Dec 29, 2024 |
| Lenovo        | Legion Pro 7 16ARX8H 82W... | [702096b561](https://linux-hardware.org/?probe=702096b561) | Dec 29, 2024 |
| Lenovo        | Legion Pro 7 16ARX8H 82W... | [968258cf48](https://linux-hardware.org/?probe=968258cf48) | Dec 29, 2024 |
| HUAWEI        | KLVL-WXX9                   | [eb1589c7c0](https://linux-hardware.org/?probe=eb1589c7c0) | Dec 28, 2024 |
| HP            | EliteBook 8540p             | [3fba3ebc56](https://linux-hardware.org/?probe=3fba3ebc56) | Dec 27, 2024 |
| Acer          | Aspire VX5-591G             | [723f61dbcf](https://linux-hardware.org/?probe=723f61dbcf) | Dec 27, 2024 |
| Acer          | Aspire VX5-591G             | [773ac488ff](https://linux-hardware.org/?probe=773ac488ff) | Dec 27, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [b892b107e9](https://linux-hardware.org/?probe=b892b107e9) | Dec 27, 2024 |
| System76      | Gazelle                     | [cb477659f5](https://linux-hardware.org/?probe=cb477659f5) | Dec 27, 2024 |
| Chuwi         | MiniBook X                  | [2959afdb7e](https://linux-hardware.org/?probe=2959afdb7e) | Dec 27, 2024 |
| Apple         | MacBookPro11,3              | [8c323a18f3](https://linux-hardware.org/?probe=8c323a18f3) | Dec 26, 2024 |
| Apple         | MacBookPro11,3              | [68bd4716f4](https://linux-hardware.org/?probe=68bd4716f4) | Dec 26, 2024 |
| Dell          | G15 5510                    | [e381abffc2](https://linux-hardware.org/?probe=e381abffc2) | Dec 26, 2024 |
| Acer          | Aspire E1-731               | [e633d3e555](https://linux-hardware.org/?probe=e633d3e555) | Dec 26, 2024 |
| System76      | Oryx Pro                    | [336ade52bd](https://linux-hardware.org/?probe=336ade52bd) | Dec 25, 2024 |
| Dell          | Precision 7670              | [7b879477ba](https://linux-hardware.org/?probe=7b879477ba) | Dec 24, 2024 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [5e9a07ac33](https://linux-hardware.org/?probe=5e9a07ac33) | Dec 23, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [a1beeae5b9](https://linux-hardware.org/?probe=a1beeae5b9) | Dec 22, 2024 |
| ASUSTek       | X510UQR                     | [f0c040e507](https://linux-hardware.org/?probe=f0c040e507) | Dec 22, 2024 |
| HUAWEI        | KLVD-WXX9                   | [a5df0d3fd9](https://linux-hardware.org/?probe=a5df0d3fd9) | Dec 22, 2024 |
| Acer          | Aspire E1-731               | [24c0bfe676](https://linux-hardware.org/?probe=24c0bfe676) | Dec 21, 2024 |
| Dell          | Inspiron 3542               | [81c6c26fa4](https://linux-hardware.org/?probe=81c6c26fa4) | Dec 21, 2024 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS0... | [8eaf87896d](https://linux-hardware.org/?probe=8eaf87896d) | Dec 21, 2024 |
| Medion        | S6445 MD61489               | [678fefd644](https://linux-hardware.org/?probe=678fefd644) | Dec 18, 2024 |
| Medion        | S6445 MD61489               | [ddd924a519](https://linux-hardware.org/?probe=ddd924a519) | Dec 18, 2024 |
| HP            | Notebook                    | [c08a1bb97f](https://linux-hardware.org/?probe=c08a1bb97f) | Dec 18, 2024 |
| ASUSTek       | X540LJ                      | [dff11ceadc](https://linux-hardware.org/?probe=dff11ceadc) | Dec 18, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [f332a63f55](https://linux-hardware.org/?probe=f332a63f55) | Dec 18, 2024 |
| Lenovo        | ThinkPad P53 MWS 15.6 (Q... | [a86913fde1](https://linux-hardware.org/?probe=a86913fde1) | Dec 18, 2024 |
| Apple         | MacBookAir3,1               | [29d91557b3](https://linux-hardware.org/?probe=29d91557b3) | Dec 17, 2024 |
| Apple         | MacBookAir3,1               | [62e2c7fe7b](https://linux-hardware.org/?probe=62e2c7fe7b) | Dec 17, 2024 |
| Dell          | System XPS L502X            | [74f4e14d27](https://linux-hardware.org/?probe=74f4e14d27) | Dec 17, 2024 |
| Dell          | System XPS L502X            | [8aa720a976](https://linux-hardware.org/?probe=8aa720a976) | Dec 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [e7ce325050](https://linux-hardware.org/?probe=e7ce325050) | Dec 16, 2024 |
| Dell          | Latitude 7340               | [01bf0e0d2c](https://linux-hardware.org/?probe=01bf0e0d2c) | Dec 16, 2024 |
| Lenovo        | Legion Y7000 81FW           | [b74286b627](https://linux-hardware.org/?probe=b74286b627) | Dec 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [eaa6397d5e](https://linux-hardware.org/?probe=eaa6397d5e) | Dec 16, 2024 |
| System76      | Lemur Pro                   | [96252caa1e](https://linux-hardware.org/?probe=96252caa1e) | Dec 16, 2024 |
| HUAWEI        | KLVL-WXX9                   | [3d5e444772](https://linux-hardware.org/?probe=3d5e444772) | Dec 16, 2024 |
| Apple         | MacBookPro10,1              | [e27d08b364](https://linux-hardware.org/?probe=e27d08b364) | Dec 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ec283efd6e](https://linux-hardware.org/?probe=ec283efd6e) | Dec 15, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [edc19c7235](https://linux-hardware.org/?probe=edc19c7235) | Dec 15, 2024 |
| Apple         | MacBookPro10,1              | [96ffa04014](https://linux-hardware.org/?probe=96ffa04014) | Dec 15, 2024 |
| Lenovo        | LOQ 15IRX9 83DV             | [68a32fe043](https://linux-hardware.org/?probe=68a32fe043) | Dec 15, 2024 |
| Apple         | MacBookPro8,2               | [b3db914035](https://linux-hardware.org/?probe=b3db914035) | Dec 15, 2024 |
| Apple         | MacBookPro8,2               | [ee05cf00fc](https://linux-hardware.org/?probe=ee05cf00fc) | Dec 15, 2024 |
| Dell          | Latitude E6420              | [ed611bf07e](https://linux-hardware.org/?probe=ed611bf07e) | Dec 15, 2024 |
| LG Electro... | 17ZB90R-K.ADC8U1            | [a98308a8ff](https://linux-hardware.org/?probe=a98308a8ff) | Dec 14, 2024 |
| System76      | Galago Pro                  | [263161107b](https://linux-hardware.org/?probe=263161107b) | Dec 14, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [8fd0a47047](https://linux-hardware.org/?probe=8fd0a47047) | Dec 13, 2024 |
| Acer          | Nitro ANV15-41              | [d58a585fc6](https://linux-hardware.org/?probe=d58a585fc6) | Dec 13, 2024 |
| AMI           | Intel                       | [744da97070](https://linux-hardware.org/?probe=744da97070) | Dec 13, 2024 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [adb22b56eb](https://linux-hardware.org/?probe=adb22b56eb) | Dec 12, 2024 |
| System76      | Oryx Pro                    | [c87371b1cb](https://linux-hardware.org/?probe=c87371b1cb) | Dec 12, 2024 |
| Apple         | MacBookPro8,1               | [802c98fd5c](https://linux-hardware.org/?probe=802c98fd5c) | Dec 12, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [5979a585ea](https://linux-hardware.org/?probe=5979a585ea) | Dec 12, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | [0913e12416](https://linux-hardware.org/?probe=0913e12416) | Dec 12, 2024 |
| Dell          | Latitude E7470              | [300b02bb07](https://linux-hardware.org/?probe=300b02bb07) | Dec 12, 2024 |
| Dell          | Latitude 7490               | [f97f9efaf8](https://linux-hardware.org/?probe=f97f9efaf8) | Dec 12, 2024 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [e5be77487d](https://linux-hardware.org/?probe=e5be77487d) | Dec 11, 2024 |
| Dell          | Inspiron 16 5645            | [0437f5d57e](https://linux-hardware.org/?probe=0437f5d57e) | Dec 11, 2024 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [c252814d3e](https://linux-hardware.org/?probe=c252814d3e) | Dec 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [9105942b15](https://linux-hardware.org/?probe=9105942b15) | Dec 10, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [d595bcedb4](https://linux-hardware.org/?probe=d595bcedb4) | Dec 10, 2024 |
| Lenovo        | B5400 20278                 | [e1b20f6c0b](https://linux-hardware.org/?probe=e1b20f6c0b) | Dec 10, 2024 |
| Lenovo        | ThinkPad X270 20HN001HUS    | [ef25178fec](https://linux-hardware.org/?probe=ef25178fec) | Dec 10, 2024 |
| Lenovo        | ThinkPad X270 20HN001HUS    | [954578185e](https://linux-hardware.org/?probe=954578185e) | Dec 10, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [861b5550d3](https://linux-hardware.org/?probe=861b5550d3) | Dec 10, 2024 |
| Dell          | Latitude E6330              | [dfc2aca866](https://linux-hardware.org/?probe=dfc2aca866) | Dec 09, 2024 |
| HP            | ZBook 17 G5                 | [0f14052159](https://linux-hardware.org/?probe=0f14052159) | Dec 09, 2024 |
| Apple         | MacBookPro5,4               | [751741e751](https://linux-hardware.org/?probe=751741e751) | Dec 09, 2024 |
| Apple         | MacBookPro5,4               | [fd85f5ad8f](https://linux-hardware.org/?probe=fd85f5ad8f) | Dec 09, 2024 |
| Apple         | MacBookPro8,1               | [58a0bf4e65](https://linux-hardware.org/?probe=58a0bf4e65) | Dec 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UV... | [e8f69e44e3](https://linux-hardware.org/?probe=e8f69e44e3) | Dec 09, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4fef924a63](https://linux-hardware.org/?probe=4fef924a63) | Dec 09, 2024 |
| Eluktronic... | RP-15                       | [bc1a09c984](https://linux-hardware.org/?probe=bc1a09c984) | Dec 08, 2024 |
| Google        | Samus                       | [362b80bc7d](https://linux-hardware.org/?probe=362b80bc7d) | Dec 08, 2024 |
| HP            | OMEN by Laptop 17-cb1xxx    | [4c1f450872](https://linux-hardware.org/?probe=4c1f450872) | Dec 08, 2024 |
| Dell          | Inspiron N4050              | [7194f36c08](https://linux-hardware.org/?probe=7194f36c08) | Dec 08, 2024 |
| HP            | ProBook 650 G1              | [62f3ba4cc6](https://linux-hardware.org/?probe=62f3ba4cc6) | Dec 07, 2024 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [88d9510fcb](https://linux-hardware.org/?probe=88d9510fcb) | Dec 07, 2024 |
| Dell          | Inspiron 15 5510            | [bd969c198e](https://linux-hardware.org/?probe=bd969c198e) | Dec 07, 2024 |
| Lenovo        | ThinkPad P52 20MAS1WD0S     | [49359bfaf2](https://linux-hardware.org/?probe=49359bfaf2) | Dec 07, 2024 |
| Lenovo        | ThinkPad T420s 417032U      | [4ac33e7516](https://linux-hardware.org/?probe=4ac33e7516) | Dec 07, 2024 |
| Lenovo        | Yoga Pro 7 14AHP9 83E3      | [8ff09eea32](https://linux-hardware.org/?probe=8ff09eea32) | Dec 06, 2024 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [2616e6e6d0](https://linux-hardware.org/?probe=2616e6e6d0) | Dec 06, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [a324fb8617](https://linux-hardware.org/?probe=a324fb8617) | Dec 06, 2024 |
| HP            | Dragonfly Pro ONE           | [6db18a33b7](https://linux-hardware.org/?probe=6db18a33b7) | Dec 06, 2024 |
| Dell          | Latitude 5490               | [04d3dd2626](https://linux-hardware.org/?probe=04d3dd2626) | Dec 05, 2024 |
| Dell          | Inspiron 16 7640 2-in-1     | [3af8e24702](https://linux-hardware.org/?probe=3af8e24702) | Dec 05, 2024 |
| ASUSTek       | N550JV                      | [e0700722fa](https://linux-hardware.org/?probe=e0700722fa) | Dec 04, 2024 |
| Acer          | Aspire A315-44P             | [67fde295de](https://linux-hardware.org/?probe=67fde295de) | Dec 04, 2024 |
| Fujitsu       | CELSIUS H920                | [8b524abe47](https://linux-hardware.org/?probe=8b524abe47) | Dec 03, 2024 |
| Apple         | MacBookPro9,2               | [2749a746c7](https://linux-hardware.org/?probe=2749a746c7) | Dec 03, 2024 |
| Apple         | MacBookPro9,2               | [e36eea22b1](https://linux-hardware.org/?probe=e36eea22b1) | Dec 03, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [8240d92fbc](https://linux-hardware.org/?probe=8240d92fbc) | Dec 02, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e702910c8e](https://linux-hardware.org/?probe=e702910c8e) | Dec 02, 2024 |
| Dell          | XPS 13 9380                 | [265dad936c](https://linux-hardware.org/?probe=265dad936c) | Dec 01, 2024 |
| Framework     | Laptop                      | [dd1492ec61](https://linux-hardware.org/?probe=dd1492ec61) | Dec 01, 2024 |
| Fujitsu       | CELSIUS H920                | [bae9e145b7](https://linux-hardware.org/?probe=bae9e145b7) | Nov 30, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | [296918a3b8](https://linux-hardware.org/?probe=296918a3b8) | Nov 30, 2024 |
| Dell          | Inspiron 3543               | [a87d08ca42](https://linux-hardware.org/?probe=a87d08ca42) | Nov 28, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f8c81ccbdb](https://linux-hardware.org/?probe=f8c81ccbdb) | Nov 28, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [90cef362ad](https://linux-hardware.org/?probe=90cef362ad) | Nov 27, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [b04303ec82](https://linux-hardware.org/?probe=b04303ec82) | Nov 26, 2024 |
| Dell          | Inspiron 3543               | [bcc801145a](https://linux-hardware.org/?probe=bcc801145a) | Nov 25, 2024 |
| Notebook      | NLxxPUx                     | [1f935fe7fc](https://linux-hardware.org/?probe=1f935fe7fc) | Nov 25, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | [ce9660e165](https://linux-hardware.org/?probe=ce9660e165) | Nov 25, 2024 |
| Dell          | Inspiron 5480               | [ce8745ed99](https://linux-hardware.org/?probe=ce8745ed99) | Nov 24, 2024 |
| Lenovo        | ThinkPad T480s 20L8S27M0... | [8cf2b4511a](https://linux-hardware.org/?probe=8cf2b4511a) | Nov 24, 2024 |
| ASUSTek       | GL503VMF                    | [cb79d7ac34](https://linux-hardware.org/?probe=cb79d7ac34) | Nov 24, 2024 |
| MSI           | GF63 8RC                    | [86cd8d621b](https://linux-hardware.org/?probe=86cd8d621b) | Nov 23, 2024 |
| Acer          | Aspire E1-731               | [f8b734fdc4](https://linux-hardware.org/?probe=f8b734fdc4) | Nov 23, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [5730687f62](https://linux-hardware.org/?probe=5730687f62) | Nov 23, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [603ece14b5](https://linux-hardware.org/?probe=603ece14b5) | Nov 23, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [2c25bb8e66](https://linux-hardware.org/?probe=2c25bb8e66) | Nov 23, 2024 |
| Dell          | XPS 15 9570                 | [3da1cde3bf](https://linux-hardware.org/?probe=3da1cde3bf) | Nov 23, 2024 |
| HP            | Dragonfly Pro Laptop PC     | [4512acb105](https://linux-hardware.org/?probe=4512acb105) | Nov 23, 2024 |
| Apple         | MacBookPro11,3              | [9ad6cf1e22](https://linux-hardware.org/?probe=9ad6cf1e22) | Nov 22, 2024 |
| Lenovo        | ThinkPad T490s 20NYS3NT0... | [89cbb90e46](https://linux-hardware.org/?probe=89cbb90e46) | Nov 21, 2024 |
| System76      | Gazelle                     | [b3ba386916](https://linux-hardware.org/?probe=b3ba386916) | Nov 21, 2024 |
| Dell          | Precision 5490              | [32bacf2696](https://linux-hardware.org/?probe=32bacf2696) | Nov 21, 2024 |
| Alienware     | 15 R2                       | [e19cff46a5](https://linux-hardware.org/?probe=e19cff46a5) | Nov 21, 2024 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [13b235f8ac](https://linux-hardware.org/?probe=13b235f8ac) | Nov 21, 2024 |
| Fujitsu       | LIFEBOOK AH532/G21          | [51cbd9f492](https://linux-hardware.org/?probe=51cbd9f492) | Nov 20, 2024 |
| Acer          | Aspire A315-51              | [291ffae1d7](https://linux-hardware.org/?probe=291ffae1d7) | Nov 20, 2024 |
| Lenovo        | ThinkPad T430s 2356CU8      | [88c764ac54](https://linux-hardware.org/?probe=88c764ac54) | Nov 20, 2024 |
| ASUSTek       | ROG Strix G18 G834JZR_G8... | [fbfffc7976](https://linux-hardware.org/?probe=fbfffc7976) | Nov 19, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [e208cd8e71](https://linux-hardware.org/?probe=e208cd8e71) | Nov 19, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [8801ad76a4](https://linux-hardware.org/?probe=8801ad76a4) | Nov 19, 2024 |
| HUAWEI        | NBLB-WAX9N                  | [63467331fb](https://linux-hardware.org/?probe=63467331fb) | Nov 19, 2024 |
| PC Special... | NH5xAx                      | [61b94b9412](https://linux-hardware.org/?probe=61b94b9412) | Nov 18, 2024 |
| Apple         | MacBookPro9,2               | [024e56ebca](https://linux-hardware.org/?probe=024e56ebca) | Nov 17, 2024 |
| Matsushita... | CF-19FDGADCM                | [9fadfe6a9b](https://linux-hardware.org/?probe=9fadfe6a9b) | Nov 17, 2024 |
| Dell          | Inspiron 3558               | [f1630ad0da](https://linux-hardware.org/?probe=f1630ad0da) | Nov 17, 2024 |
| MSI           | GP60 2PE                    | [3d4814126b](https://linux-hardware.org/?probe=3d4814126b) | Nov 16, 2024 |
| ASUSTek       | Strix GL703GS_GL703GS       | [6ea29cc14a](https://linux-hardware.org/?probe=6ea29cc14a) | Nov 16, 2024 |
| Apple         | MacBookPro11,5              | [c2a112f067](https://linux-hardware.org/?probe=c2a112f067) | Nov 16, 2024 |
| Lenovo        | ThinkPad T460 20FN003LGE    | [06d3c3c63f](https://linux-hardware.org/?probe=06d3c3c63f) | Nov 16, 2024 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [5f6a56e720](https://linux-hardware.org/?probe=5f6a56e720) | Nov 16, 2024 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [b7df8d7127](https://linux-hardware.org/?probe=b7df8d7127) | Nov 16, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [48b24cce4c](https://linux-hardware.org/?probe=48b24cce4c) | Nov 16, 2024 |
| Apple         | MacBookPro9,1               | [e839fa544a](https://linux-hardware.org/?probe=e839fa544a) | Nov 15, 2024 |
| Apple         | MacBookPro9,1               | [ff147ff990](https://linux-hardware.org/?probe=ff147ff990) | Nov 15, 2024 |
| Razer         | Blade                       | [0d6640fb39](https://linux-hardware.org/?probe=0d6640fb39) | Nov 15, 2024 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [1ff2d7429c](https://linux-hardware.org/?probe=1ff2d7429c) | Nov 15, 2024 |
| Acer          | Nitro AN515-51              | [b4bf8cdee4](https://linux-hardware.org/?probe=b4bf8cdee4) | Nov 13, 2024 |
| MSI           | Vector 16 HX A13VHG         | [afef5ca6c4](https://linux-hardware.org/?probe=afef5ca6c4) | Nov 13, 2024 |
| Lenovo        | IdeaPad Slim 5 16AHP9 83... | [14d794125a](https://linux-hardware.org/?probe=14d794125a) | Nov 12, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [feb8fd8dbc](https://linux-hardware.org/?probe=feb8fd8dbc) | Nov 12, 2024 |
| MSI           | Modern 14 A10RB             | [e0bf66102b](https://linux-hardware.org/?probe=e0bf66102b) | Nov 12, 2024 |
| Dell          | Precision 3561              | [43f06770e1](https://linux-hardware.org/?probe=43f06770e1) | Nov 11, 2024 |
| Acer          | Aspire 4752                 | [2f02f5ff8b](https://linux-hardware.org/?probe=2f02f5ff8b) | Nov 11, 2024 |
| Infinix       | INBOOK Y1 PLUS              | [53ea4dc826](https://linux-hardware.org/?probe=53ea4dc826) | Nov 11, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [d39f3e11a8](https://linux-hardware.org/?probe=d39f3e11a8) | Nov 11, 2024 |
| Toshiba       | Satellite L655D             | [9a6af30aa7](https://linux-hardware.org/?probe=9a6af30aa7) | Nov 10, 2024 |
| Lenovo        | V330-14IKB 81B0             | [d244f80fd9](https://linux-hardware.org/?probe=d244f80fd9) | Nov 10, 2024 |
| Lenovo        | ThinkPad T490 20N3000KGE    | [8f487ff101](https://linux-hardware.org/?probe=8f487ff101) | Nov 09, 2024 |
| Acer          | Aspire A315-24PT            | [a780b016b5](https://linux-hardware.org/?probe=a780b016b5) | Nov 09, 2024 |
| Toshiba       | Satellite S40Dt-A           | [9df604ab8c](https://linux-hardware.org/?probe=9df604ab8c) | Nov 08, 2024 |
| Gigabyte      | AERO 15XV8                  | [ad28b2f598](https://linux-hardware.org/?probe=ad28b2f598) | Nov 07, 2024 |
| Acer          | Predator PT14-51            | [89ab08c4d5](https://linux-hardware.org/?probe=89ab08c4d5) | Nov 07, 2024 |
| Acer          | SF314-71-50E8               | [026f2ca004](https://linux-hardware.org/?probe=026f2ca004) | Nov 07, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [de1c2a77a8](https://linux-hardware.org/?probe=de1c2a77a8) | Nov 07, 2024 |
| Apple         | MacBookPro8,3               | [86b3f8139b](https://linux-hardware.org/?probe=86b3f8139b) | Nov 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [92d4a2f482](https://linux-hardware.org/?probe=92d4a2f482) | Nov 05, 2024 |
| Lenovo        | V145-15AST 81MT             | [7f51e7a50a](https://linux-hardware.org/?probe=7f51e7a50a) | Nov 05, 2024 |
| Acer          | Nitro AN515-58              | [49b45e8170](https://linux-hardware.org/?probe=49b45e8170) | Nov 04, 2024 |
| Dell          | XPS 13 9370                 | [488431591c](https://linux-hardware.org/?probe=488431591c) | Nov 04, 2024 |
| MSI           | Summit E16FlipEvo A11MT     | [70c39b3a00](https://linux-hardware.org/?probe=70c39b3a00) | Nov 04, 2024 |
| ASUSTek       | Zenbook UX3404VA_Q420VA     | [2dd904a978](https://linux-hardware.org/?probe=2dd904a978) | Nov 03, 2024 |
| System76      | Serval WS                   | [3325ac75c2](https://linux-hardware.org/?probe=3325ac75c2) | Nov 03, 2024 |
| System76      | Pangolin                    | [d1958d8e54](https://linux-hardware.org/?probe=d1958d8e54) | Nov 02, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | [0f0375d12d](https://linux-hardware.org/?probe=0f0375d12d) | Nov 02, 2024 |
| Apple         | MacBookPro10,1              | [1c42e6c25f](https://linux-hardware.org/?probe=1c42e6c25f) | Nov 02, 2024 |
| HP            | Victus by Gaming Laptop ... | [5370c39b49](https://linux-hardware.org/?probe=5370c39b49) | Nov 02, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1502CBA... | [2831ff1766](https://linux-hardware.org/?probe=2831ff1766) | Nov 02, 2024 |
| Dell          | Precision 3590              | [bc82f6333a](https://linux-hardware.org/?probe=bc82f6333a) | Nov 02, 2024 |
| Dell          | Latitude E4300              | [90b6823b82](https://linux-hardware.org/?probe=90b6823b82) | Nov 02, 2024 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [d6283216f3](https://linux-hardware.org/?probe=d6283216f3) | Nov 02, 2024 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [67f2f24139](https://linux-hardware.org/?probe=67f2f24139) | Nov 02, 2024 |
| Google        | Samus                       | [6c26c1cab1](https://linux-hardware.org/?probe=6c26c1cab1) | Nov 01, 2024 |
| Google        | Samus                       | [190f904324](https://linux-hardware.org/?probe=190f904324) | Nov 01, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [06801a2213](https://linux-hardware.org/?probe=06801a2213) | Nov 01, 2024 |
| Dell          | Latitude E4300              | [2c7555b016](https://linux-hardware.org/?probe=2c7555b016) | Oct 31, 2024 |
| Gigabyte      | AERO 15XV8                  | [10526455a3](https://linux-hardware.org/?probe=10526455a3) | Oct 31, 2024 |
| System76      | Darter Pro                  | [47e11617c9](https://linux-hardware.org/?probe=47e11617c9) | Oct 31, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | [8a23e0e1bf](https://linux-hardware.org/?probe=8a23e0e1bf) | Oct 31, 2024 |
| Dell          | Inspiron 16 7640 2-in-1     | [f0a61a6b62](https://linux-hardware.org/?probe=f0a61a6b62) | Oct 31, 2024 |
| Dell          | Inspiron 3543               | [ca851926b9](https://linux-hardware.org/?probe=ca851926b9) | Oct 31, 2024 |
| Dell          | Inspiron 3543               | [3872f48485](https://linux-hardware.org/?probe=3872f48485) | Oct 30, 2024 |
| Gigabyte      | Z590I AORUS ULTRA           | [816bafe83f](https://linux-hardware.org/?probe=816bafe83f) | Oct 30, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | [9589e6f064](https://linux-hardware.org/?probe=9589e6f064) | Oct 30, 2024 |
| Dell          | XPS 15 9510                 | [3e6d95febe](https://linux-hardware.org/?probe=3e6d95febe) | Oct 29, 2024 |
| MSI           | Modern 14 B11MOU            | [1347b3862f](https://linux-hardware.org/?probe=1347b3862f) | Oct 29, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [8c5b5946e9](https://linux-hardware.org/?probe=8c5b5946e9) | Oct 29, 2024 |
| Toshiba       | Satellite C850-B225         | [962858a9aa](https://linux-hardware.org/?probe=962858a9aa) | Oct 29, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [2e04817d43](https://linux-hardware.org/?probe=2e04817d43) | Oct 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [e71f961f6b](https://linux-hardware.org/?probe=e71f961f6b) | Oct 28, 2024 |
| Dell          | Latitude E6430              | [3a0bf739f0](https://linux-hardware.org/?probe=3a0bf739f0) | Oct 28, 2024 |
| Lenovo        | ThinkPad X390 20Q1S6W600    | [8e5f1a7f66](https://linux-hardware.org/?probe=8e5f1a7f66) | Oct 27, 2024 |
| MSI           | Bravo 17 C7VFK              | [a7adfb673d](https://linux-hardware.org/?probe=a7adfb673d) | Oct 27, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [e2335cbea6](https://linux-hardware.org/?probe=e2335cbea6) | Oct 27, 2024 |
| Apple         | MacBookAir7,2               | [6b3fb2ce2d](https://linux-hardware.org/?probe=6b3fb2ce2d) | Oct 26, 2024 |
| System76      | Pangolin                    | [fb57203d8e](https://linux-hardware.org/?probe=fb57203d8e) | Oct 26, 2024 |
| Lenovo        | 3 15ADA05 81W1              | [909b98bfa8](https://linux-hardware.org/?probe=909b98bfa8) | Oct 26, 2024 |
| System76      | Lemur Pro                   | [c9d662ba98](https://linux-hardware.org/?probe=c9d662ba98) | Oct 26, 2024 |
| MSI           | Modern 14 B11MOU            | [e854e6170d](https://linux-hardware.org/?probe=e854e6170d) | Oct 25, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [085e6bccdb](https://linux-hardware.org/?probe=085e6bccdb) | Oct 25, 2024 |
| ASUSTek       | ASUS TUF Gaming A14 FA40... | [100c697e15](https://linux-hardware.org/?probe=100c697e15) | Oct 25, 2024 |
| ASUSTek       | ASUS TUF Gaming A14 FA40... | [e8bafa71e4](https://linux-hardware.org/?probe=e8bafa71e4) | Oct 25, 2024 |
| HP            | Pavilion dv6                | [e0742f5a71](https://linux-hardware.org/?probe=e0742f5a71) | Oct 25, 2024 |
| HP            | Pavilion dv6                | [6038c991fd](https://linux-hardware.org/?probe=6038c991fd) | Oct 25, 2024 |
| Dell          | Latitude E5530 non-vPro     | [81b90346d4](https://linux-hardware.org/?probe=81b90346d4) | Oct 25, 2024 |
| Dell          | Latitude E5530 non-vPro     | [3f56d7a7f5](https://linux-hardware.org/?probe=3f56d7a7f5) | Oct 25, 2024 |
| HP            | Victus by Gaming Laptop ... | [84f4f906f2](https://linux-hardware.org/?probe=84f4f906f2) | Oct 24, 2024 |
| ASUSTek       | GL553VE                     | [ac2e87e2ce](https://linux-hardware.org/?probe=ac2e87e2ce) | Oct 23, 2024 |
| Itautec       | Infoway w7730               | [031ee64761](https://linux-hardware.org/?probe=031ee64761) | Oct 23, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [cb81bdd86a](https://linux-hardware.org/?probe=cb81bdd86a) | Oct 23, 2024 |
| System76      | Pangolin                    | [802316e70a](https://linux-hardware.org/?probe=802316e70a) | Oct 23, 2024 |
| MSI           | GS60 6QE                    | [7e1d315d47](https://linux-hardware.org/?probe=7e1d315d47) | Oct 22, 2024 |
| IT Channel... | NP5x_6x_7x_SNx              | [f92a3a6051](https://linux-hardware.org/?probe=f92a3a6051) | Oct 21, 2024 |
| Positivo      | Schoolmate SF20GM7          | [4b0b1bae90](https://linux-hardware.org/?probe=4b0b1bae90) | Oct 21, 2024 |
| IT Channel... | PCX0DX                      | [c8d8110356](https://linux-hardware.org/?probe=c8d8110356) | Oct 21, 2024 |
| HP            | ProBook 4740s               | [b2dd7236f6](https://linux-hardware.org/?probe=b2dd7236f6) | Oct 20, 2024 |
| Acer          | Aspire 7745G                | [48cc1c84fc](https://linux-hardware.org/?probe=48cc1c84fc) | Oct 20, 2024 |
| HP            | Pavilion dv7                | [77e53f9398](https://linux-hardware.org/?probe=77e53f9398) | Oct 19, 2024 |
| HP            | Pavilion HDX9200            | [1098a89014](https://linux-hardware.org/?probe=1098a89014) | Oct 19, 2024 |
| Dell          | Studio 1555                 | [709087cbff](https://linux-hardware.org/?probe=709087cbff) | Oct 19, 2024 |
| Sony          | VPCEH1M9R                   | [78491a0382](https://linux-hardware.org/?probe=78491a0382) | Oct 18, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [065239fc07](https://linux-hardware.org/?probe=065239fc07) | Oct 18, 2024 |
| Lenovo        | IdeaPad Slim 5 14IRL8 82... | [62c3d2eddd](https://linux-hardware.org/?probe=62c3d2eddd) | Oct 17, 2024 |
| MSI           | Katana 15 B13VFK            | [45d00541c0](https://linux-hardware.org/?probe=45d00541c0) | Oct 17, 2024 |
| HP            | ProBook 650 G2              | [8b6dc142e9](https://linux-hardware.org/?probe=8b6dc142e9) | Oct 17, 2024 |
| Lenovo        | ThinkPad P50 20EQS29A00     | [9cee201a44](https://linux-hardware.org/?probe=9cee201a44) | Oct 17, 2024 |
| Toshiba       | QOSMIO X775                 | [de226c2b19](https://linux-hardware.org/?probe=de226c2b19) | Oct 16, 2024 |
| Dell          | XPS 13 9370                 | [7d89635983](https://linux-hardware.org/?probe=7d89635983) | Oct 16, 2024 |
| Notebook      | W65_W67RB                   | [69df44fe32](https://linux-hardware.org/?probe=69df44fe32) | Oct 16, 2024 |
| Notebook      | W65_W67RB                   | [a787a5ebbb](https://linux-hardware.org/?probe=a787a5ebbb) | Oct 16, 2024 |
| MSI           | Summit E13FlipEvo A12MT     | [9b12651c67](https://linux-hardware.org/?probe=9b12651c67) | Oct 16, 2024 |
| HP            | Pavilion Laptop 15-cd0xx    | [b83fb99eb1](https://linux-hardware.org/?probe=b83fb99eb1) | Oct 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [a3e77b53eb](https://linux-hardware.org/?probe=a3e77b53eb) | Oct 16, 2024 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [56fa2a9b2a](https://linux-hardware.org/?probe=56fa2a9b2a) | Oct 15, 2024 |
| Apple         | MacBookPro8,1               | [18cc7921db](https://linux-hardware.org/?probe=18cc7921db) | Oct 15, 2024 |
| Apple         | MacBookPro8,1               | [e6891ad523](https://linux-hardware.org/?probe=e6891ad523) | Oct 15, 2024 |
| Lenovo        | ThinkPad T490s 20NYS3NT0... | [7dd8855689](https://linux-hardware.org/?probe=7dd8855689) | Oct 15, 2024 |
| Dell          | Latitude E7250              | [ce90b269d6](https://linux-hardware.org/?probe=ce90b269d6) | Oct 14, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | [4b04c405ca](https://linux-hardware.org/?probe=4b04c405ca) | Oct 14, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [00304ae6db](https://linux-hardware.org/?probe=00304ae6db) | Oct 14, 2024 |
| Apple         | MacBookPro8,2               | [f20e6b3dc8](https://linux-hardware.org/?probe=f20e6b3dc8) | Oct 13, 2024 |
| Apple         | MacBookPro8,2               | [ecf92c84fe](https://linux-hardware.org/?probe=ecf92c84fe) | Oct 13, 2024 |
| ASUSTek       | E403NA                      | [9ae450e44c](https://linux-hardware.org/?probe=9ae450e44c) | Oct 13, 2024 |
| Alienware     | m15 R7                      | [5322ba17a8](https://linux-hardware.org/?probe=5322ba17a8) | Oct 13, 2024 |
| System76      | Lemur                       | [61343c26b9](https://linux-hardware.org/?probe=61343c26b9) | Oct 13, 2024 |
| HP            | ZBook 15 G3                 | [396d9b1508](https://linux-hardware.org/?probe=396d9b1508) | Oct 12, 2024 |
| MSI           | Katana 15 B13VFK            | [d5a97499e2](https://linux-hardware.org/?probe=d5a97499e2) | Oct 12, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | [8dc9ff9d77](https://linux-hardware.org/?probe=8dc9ff9d77) | Oct 12, 2024 |
| Dell          | XPS 13 9350                 | [d4ae2f6f73](https://linux-hardware.org/?probe=d4ae2f6f73) | Oct 11, 2024 |
| Acer          | Aspire A515-57              | [4e4e4b33ec](https://linux-hardware.org/?probe=4e4e4b33ec) | Oct 11, 2024 |
| Apple         | MacBookPro8,2               | [b40e0a8447](https://linux-hardware.org/?probe=b40e0a8447) | Oct 11, 2024 |
| HP            | Laptop 14-dk0xxx            | [530feba7a4](https://linux-hardware.org/?probe=530feba7a4) | Oct 11, 2024 |
| Dell          | G3 3579                     | [3f29ebd856](https://linux-hardware.org/?probe=3f29ebd856) | Oct 11, 2024 |
| MSI           | Katana 15 B13VFK            | [2dd48ca806](https://linux-hardware.org/?probe=2dd48ca806) | Oct 10, 2024 |
| MSI           | Modern 14 A10RB             | [148147f2d5](https://linux-hardware.org/?probe=148147f2d5) | Oct 10, 2024 |
| Timi          | Xiaomi Book Pro 14 2022     | [c6cc33d55b](https://linux-hardware.org/?probe=c6cc33d55b) | Oct 10, 2024 |
| HP            | Laptop 14-dk0xxx            | [0658548720](https://linux-hardware.org/?probe=0658548720) | Oct 10, 2024 |
| System76      | Oryx Pro                    | [4a122791a4](https://linux-hardware.org/?probe=4a122791a4) | Oct 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [a3deb73e2b](https://linux-hardware.org/?probe=a3deb73e2b) | Oct 09, 2024 |
| System76      | Lemur Pro                   | [0e513dcca4](https://linux-hardware.org/?probe=0e513dcca4) | Oct 09, 2024 |
| Lenovo        | ThinkPad W530 24382MU       | [afbcd71537](https://linux-hardware.org/?probe=afbcd71537) | Oct 09, 2024 |
| MSI           | Modern 14 A10RB             | [f1b16a12ac](https://linux-hardware.org/?probe=f1b16a12ac) | Oct 09, 2024 |
| Dell          | Precision M4800             | [87e17e0353](https://linux-hardware.org/?probe=87e17e0353) | Oct 09, 2024 |
| Alienware     | m16 R2                      | [5fe417e971](https://linux-hardware.org/?probe=5fe417e971) | Oct 09, 2024 |
| HP            | Victus by Gaming Laptop ... | [ea25986093](https://linux-hardware.org/?probe=ea25986093) | Oct 09, 2024 |
| ASUSTek       | ROG Zephyrus G16 GU603ZI... | [4a70fc8e54](https://linux-hardware.org/?probe=4a70fc8e54) | Oct 08, 2024 |
| HP            | Laptop 15-dy5xxx            | [0e2f27c078](https://linux-hardware.org/?probe=0e2f27c078) | Oct 08, 2024 |
| Dell          | Inspiron 5537               | [ae9d9a4bb9](https://linux-hardware.org/?probe=ae9d9a4bb9) | Oct 07, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [4dc891703c](https://linux-hardware.org/?probe=4dc891703c) | Oct 07, 2024 |
| Apple         | MacBookPro12,1              | [78f8401511](https://linux-hardware.org/?probe=78f8401511) | Oct 07, 2024 |
| Dell          | Latitude 3420               | [6a7a1635f1](https://linux-hardware.org/?probe=6a7a1635f1) | Oct 07, 2024 |
| Apple         | MacBookAir7,2               | [2894d8b661](https://linux-hardware.org/?probe=2894d8b661) | Oct 07, 2024 |
| System76      | Bonobo WS                   | [cb3f9574d5](https://linux-hardware.org/?probe=cb3f9574d5) | Oct 05, 2024 |
| Dell          | Inspiron 5379               | [d4ec7c3588](https://linux-hardware.org/?probe=d4ec7c3588) | Oct 05, 2024 |
| Lenovo        | Legion S7 15ACH6 82K8       | [73a4fb7e13](https://linux-hardware.org/?probe=73a4fb7e13) | Oct 04, 2024 |
| Dell          | Inspiron 3543               | [b675409877](https://linux-hardware.org/?probe=b675409877) | Oct 04, 2024 |
| HP            | Pavilion g6                 | [1a77adf7d3](https://linux-hardware.org/?probe=1a77adf7d3) | Oct 04, 2024 |
| Apple         | MacBookPro12,1              | [db53c1e876](https://linux-hardware.org/?probe=db53c1e876) | Oct 04, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E70... | [28caf4f8a8](https://linux-hardware.org/?probe=28caf4f8a8) | Oct 04, 2024 |
| MSI           | Katana 17 B13VGK            | [554bc53d9e](https://linux-hardware.org/?probe=554bc53d9e) | Oct 03, 2024 |
| HP            | OMEN by Laptop 17-ck0xxx    | [666ea6e8cf](https://linux-hardware.org/?probe=666ea6e8cf) | Oct 03, 2024 |
| MSI           | GP72M 7REX                  | [ed03e0a42a](https://linux-hardware.org/?probe=ed03e0a42a) | Oct 03, 2024 |
| Apple         | MacBookAir7,2               | [7d968335d4](https://linux-hardware.org/?probe=7d968335d4) | Oct 03, 2024 |
| HP            | Compaq Presario CQ41        | [8883290af4](https://linux-hardware.org/?probe=8883290af4) | Oct 03, 2024 |
| Unknown       | Unknown                     | [724da43eb0](https://linux-hardware.org/?probe=724da43eb0) | Oct 03, 2024 |
| HP            | Victus by Gaming Laptop ... | [0b81ce4446](https://linux-hardware.org/?probe=0b81ce4446) | Oct 03, 2024 |
| HP            | Laptop 15s-eq2xxx           | [caae52edaa](https://linux-hardware.org/?probe=caae52edaa) | Oct 02, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6f1403e89a](https://linux-hardware.org/?probe=6f1403e89a) | Oct 02, 2024 |
| Dell          | Inspiron 3521               | [603ca0f8d7](https://linux-hardware.org/?probe=603ca0f8d7) | Oct 02, 2024 |
| Toshiba       | Satellite Pro C50-B         | [73cecf0985](https://linux-hardware.org/?probe=73cecf0985) | Oct 02, 2024 |
| HP            | EliteBook 860 16 inch G1... | [e0b7091ba1](https://linux-hardware.org/?probe=e0b7091ba1) | Oct 01, 2024 |
| Lenovo        | Legion Pro 5 16IRX9 83DF    | [041554f4bd](https://linux-hardware.org/?probe=041554f4bd) | Oct 01, 2024 |
| Dell          | XPS 13 9350                 | [4b43e1f37c](https://linux-hardware.org/?probe=4b43e1f37c) | Oct 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [8f6ef31fc0](https://linux-hardware.org/?probe=8f6ef31fc0) | Oct 01, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [5719cacbe1](https://linux-hardware.org/?probe=5719cacbe1) | Oct 01, 2024 |
| Acer          | Aspire A515-55              | [38c3405231](https://linux-hardware.org/?probe=38c3405231) | Oct 01, 2024 |
| Apple         | MacBookPro12,1              | [7ca3c3aec3](https://linux-hardware.org/?probe=7ca3c3aec3) | Sep 30, 2024 |
| HUAWEI        | BOM-WXX9                    | [2d94aeca06](https://linux-hardware.org/?probe=2d94aeca06) | Sep 30, 2024 |
| Dell          | Latitude E6320              | [e83def8251](https://linux-hardware.org/?probe=e83def8251) | Sep 30, 2024 |
| Dynabook      | TECRA A40-E                 | [78617fd33a](https://linux-hardware.org/?probe=78617fd33a) | Sep 30, 2024 |
| Samsung       | 750XED                      | [4678fb79d7](https://linux-hardware.org/?probe=4678fb79d7) | Sep 30, 2024 |
| HUAWEI        | BOM-WXX9                    | [958be4ca06](https://linux-hardware.org/?probe=958be4ca06) | Sep 30, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a6e4176354](https://linux-hardware.org/?probe=a6e4176354) | Sep 30, 2024 |
| HP            | Laptop 15s-eq2xxx           | [dbc07b818f](https://linux-hardware.org/?probe=dbc07b818f) | Sep 29, 2024 |
| Apple         | MacBookAir7,2               | [f267e0be7a](https://linux-hardware.org/?probe=f267e0be7a) | Sep 29, 2024 |
| Sony          | SVE15126CAB                 | [f60413658c](https://linux-hardware.org/?probe=f60413658c) | Sep 28, 2024 |
| PC Special... | Ionico 15 M                 | [1f586c152d](https://linux-hardware.org/?probe=1f586c152d) | Sep 27, 2024 |
| Lenovo        | ThinkPad W550s 20E2000QU... | [5adcba6b0e](https://linux-hardware.org/?probe=5adcba6b0e) | Sep 27, 2024 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [1af97168e8](https://linux-hardware.org/?probe=1af97168e8) | Sep 27, 2024 |
| Fujitsu       | LIFEBOOK T902               | [7b4b348c98](https://linux-hardware.org/?probe=7b4b348c98) | Sep 27, 2024 |
| ASUSTek       | K95VM                       | [ff438ad161](https://linux-hardware.org/?probe=ff438ad161) | Sep 27, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [35ddc3009c](https://linux-hardware.org/?probe=35ddc3009c) | Sep 27, 2024 |
| Apple         | MacBookPro8,1               | [93e19e497d](https://linux-hardware.org/?probe=93e19e497d) | Sep 27, 2024 |
| ASRock        | N68-GS4 FX R2.0             | [5e82748806](https://linux-hardware.org/?probe=5e82748806) | Sep 26, 2024 |
| Lenovo        | ThinkPad W550s 20E2000QU... | [fe8af671af](https://linux-hardware.org/?probe=fe8af671af) | Sep 26, 2024 |
| PC Special... | P65_67HSHP                  | [2313271b0b](https://linux-hardware.org/?probe=2313271b0b) | Sep 26, 2024 |
| HP            | EliteBook 745 G2            | [6f10a18bc8](https://linux-hardware.org/?probe=6f10a18bc8) | Sep 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0e0ec9b83b](https://linux-hardware.org/?probe=0e0ec9b83b) | Sep 25, 2024 |
| System76      | Lemur Pro                   | [31bd01c8bf](https://linux-hardware.org/?probe=31bd01c8bf) | Sep 25, 2024 |
| Acer          | Swift SFX14-41G             | [ec357b358b](https://linux-hardware.org/?probe=ec357b358b) | Sep 24, 2024 |
| Apple         | MacBookPro11,1              | [05bb9f7907](https://linux-hardware.org/?probe=05bb9f7907) | Sep 24, 2024 |
| GPD           | G1619-04                    | [058bd4c7ff](https://linux-hardware.org/?probe=058bd4c7ff) | Sep 23, 2024 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | [20e79a1fff](https://linux-hardware.org/?probe=20e79a1fff) | Sep 23, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E70... | [df85d46568](https://linux-hardware.org/?probe=df85d46568) | Sep 23, 2024 |
| HP            | EliteBook 840 G2            | [3702cf8035](https://linux-hardware.org/?probe=3702cf8035) | Sep 23, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [e6d5ee9fc0](https://linux-hardware.org/?probe=e6d5ee9fc0) | Sep 23, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [76e2b2a322](https://linux-hardware.org/?probe=76e2b2a322) | Sep 22, 2024 |
| HP            | EliteBook 840 G2            | [78e3642c86](https://linux-hardware.org/?probe=78e3642c86) | Sep 22, 2024 |
| MSI           | Katana GF76 11UE            | [e49bd98e54](https://linux-hardware.org/?probe=e49bd98e54) | Sep 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [28d162298f](https://linux-hardware.org/?probe=28d162298f) | Sep 22, 2024 |
| ASUSTek       | X541UJ                      | [cc2936a90c](https://linux-hardware.org/?probe=cc2936a90c) | Sep 22, 2024 |
| MSI           | Katana GF76 11UE            | [89bb8dc2c6](https://linux-hardware.org/?probe=89bb8dc2c6) | Sep 21, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [fdc7cf356a](https://linux-hardware.org/?probe=fdc7cf356a) | Sep 21, 2024 |
| System76      | Oryx Pro                    | [6610d42db1](https://linux-hardware.org/?probe=6610d42db1) | Sep 20, 2024 |
| Lenovo        | ThinkPad T490 20N2S07G00    | [4a36fced72](https://linux-hardware.org/?probe=4a36fced72) | Sep 20, 2024 |
| HP            | Dragonfly Pro Laptop PC     | [9fb2ecaa2b](https://linux-hardware.org/?probe=9fb2ecaa2b) | Sep 20, 2024 |
| ASUSTek       | G751JM                      | [87122432ea](https://linux-hardware.org/?probe=87122432ea) | Sep 19, 2024 |
| HP            | Elite Dragonfly 13.5 inc... | [dfc03a83e8](https://linux-hardware.org/?probe=dfc03a83e8) | Sep 19, 2024 |
| Dell          | Inspiron 7460               | [15df31e515](https://linux-hardware.org/?probe=15df31e515) | Sep 19, 2024 |
| Toshiba       | Satellite Pro C50-B         | [42a9f50fe0](https://linux-hardware.org/?probe=42a9f50fe0) | Sep 19, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [e6a4fd809a](https://linux-hardware.org/?probe=e6a4fd809a) | Sep 18, 2024 |
| Dell          | XPS 13 9343                 | [da87bf7199](https://linux-hardware.org/?probe=da87bf7199) | Sep 18, 2024 |
| Lenovo        | ThinkPad T490 20N2S07G00    | [b44af6782f](https://linux-hardware.org/?probe=b44af6782f) | Sep 18, 2024 |
| Lenovo        | ThinkPad T470p 20J6003DG... | [bc3c822394](https://linux-hardware.org/?probe=bc3c822394) | Sep 17, 2024 |
| Lenovo        | ThinkPad T470p 20J6003DG... | [8d70e14b2c](https://linux-hardware.org/?probe=8d70e14b2c) | Sep 17, 2024 |
| HP            | Notebook                    | [e7a6a098de](https://linux-hardware.org/?probe=e7a6a098de) | Sep 16, 2024 |
| Lenovo        | ThinkPad T495 20NKS0JH00    | [9c1b1955e0](https://linux-hardware.org/?probe=9c1b1955e0) | Sep 16, 2024 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | [0f1839e516](https://linux-hardware.org/?probe=0f1839e516) | Sep 16, 2024 |
| HP            | Laptop 14-dq2xxx            | [bc22f163ca](https://linux-hardware.org/?probe=bc22f163ca) | Sep 16, 2024 |
| Google        | Bobba                       | [2b41ad3d59](https://linux-hardware.org/?probe=2b41ad3d59) | Sep 16, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K3C... | [8e2cbf4a4c](https://linux-hardware.org/?probe=8e2cbf4a4c) | Sep 15, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K3C... | [ba58290a64](https://linux-hardware.org/?probe=ba58290a64) | Sep 15, 2024 |
| Lenovo        | ThinkBook 16 G5+ APH 21K... | [27a7675f10](https://linux-hardware.org/?probe=27a7675f10) | Sep 15, 2024 |
| Apple         | MacBookPro11,1              | [74c6dede90](https://linux-hardware.org/?probe=74c6dede90) | Sep 15, 2024 |
| Dell          | XPS 15 7590                 | [fc5fb22b68](https://linux-hardware.org/?probe=fc5fb22b68) | Sep 15, 2024 |
| Lenovo        | ThinkPad T490s 20NX0036U... | [67e46acf77](https://linux-hardware.org/?probe=67e46acf77) | Sep 15, 2024 |
| Apple         | MacBookPro11,1              | [bccbd4f8b4](https://linux-hardware.org/?probe=bccbd4f8b4) | Sep 15, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [bc6a4c8d93](https://linux-hardware.org/?probe=bc6a4c8d93) | Sep 14, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c303f60d53](https://linux-hardware.org/?probe=c303f60d53) | Sep 12, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [f7f43b9e05](https://linux-hardware.org/?probe=f7f43b9e05) | Sep 12, 2024 |
| Lenovo        | ThinkPad P1 Gen 6 21FWS1... | [286d8bff4c](https://linux-hardware.org/?probe=286d8bff4c) | Sep 12, 2024 |
| HP            | EliteBook 8470w             | [a4891795bf](https://linux-hardware.org/?probe=a4891795bf) | Sep 12, 2024 |
| HP            | ProBook 440 G6              | [05e673b163](https://linux-hardware.org/?probe=05e673b163) | Sep 12, 2024 |
| Dell          | Inspiron 3543               | [8af7dfeb86](https://linux-hardware.org/?probe=8af7dfeb86) | Sep 12, 2024 |
| Dell          | Latitude 5285               | [c6cfa428e6](https://linux-hardware.org/?probe=c6cfa428e6) | Sep 11, 2024 |
| Lenovo        | Legion S7 15ACH6 82K8       | [67b8e095f4](https://linux-hardware.org/?probe=67b8e095f4) | Sep 11, 2024 |
| Dell          | Latitude 5285               | [c01121651d](https://linux-hardware.org/?probe=c01121651d) | Sep 11, 2024 |
| Dell          | Vostro 2520                 | [39215cb0ac](https://linux-hardware.org/?probe=39215cb0ac) | Sep 11, 2024 |
| ASUSTek       | U36JC                       | [17939b0154](https://linux-hardware.org/?probe=17939b0154) | Sep 11, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [7d69f47d2e](https://linux-hardware.org/?probe=7d69f47d2e) | Sep 11, 2024 |
| Lenovo        | ThinkPad P1 20MDS0LX00      | [19682cb902](https://linux-hardware.org/?probe=19682cb902) | Sep 10, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [d9d1b453e2](https://linux-hardware.org/?probe=d9d1b453e2) | Sep 10, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [35ebae4c04](https://linux-hardware.org/?probe=35ebae4c04) | Sep 10, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [d8b1c359a7](https://linux-hardware.org/?probe=d8b1c359a7) | Sep 10, 2024 |
| HP            | ZBook Firefly 15 inch G8... | [80d75616ad](https://linux-hardware.org/?probe=80d75616ad) | Sep 10, 2024 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [cf75a7672b](https://linux-hardware.org/?probe=cf75a7672b) | Sep 10, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [8a13bf7683](https://linux-hardware.org/?probe=8a13bf7683) | Sep 10, 2024 |
| Dell          | Latitude E7450              | [c44971afd2](https://linux-hardware.org/?probe=c44971afd2) | Sep 10, 2024 |
| Notebook      | NJx0PU                      | [a3df6e5e48](https://linux-hardware.org/?probe=a3df6e5e48) | Sep 09, 2024 |
| Lenovo        | ThinkPad T420 4236PFG       | [7d198fc2a8](https://linux-hardware.org/?probe=7d198fc2a8) | Sep 09, 2024 |
| HP            | Notebook                    | [7392bbfc0f](https://linux-hardware.org/?probe=7392bbfc0f) | Sep 09, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | [7c88f99720](https://linux-hardware.org/?probe=7c88f99720) | Sep 09, 2024 |
| HP            | 242 G1                      | [b3dea9f0da](https://linux-hardware.org/?probe=b3dea9f0da) | Sep 08, 2024 |
| HP            | Victus by Laptop PC         | [9e793a27cc](https://linux-hardware.org/?probe=9e793a27cc) | Sep 08, 2024 |
| MSI           | Summit E13FlipEvo A12MT     | [7cb36d2589](https://linux-hardware.org/?probe=7cb36d2589) | Sep 07, 2024 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [3ccc7931f9](https://linux-hardware.org/?probe=3ccc7931f9) | Sep 07, 2024 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [347ed4b41d](https://linux-hardware.org/?probe=347ed4b41d) | Sep 07, 2024 |
| Apple         | MacBookPro9,2               | [8062c8c6db](https://linux-hardware.org/?probe=8062c8c6db) | Sep 07, 2024 |
| Lenovo        | ThinkPad P53s 20N60024US    | [641f3bbdd3](https://linux-hardware.org/?probe=641f3bbdd3) | Sep 06, 2024 |
| MSI           | Prestige 16 AI Evo B1MG     | [4d8f25ca50](https://linux-hardware.org/?probe=4d8f25ca50) | Sep 04, 2024 |
| Acer          | Aspire 7741                 | [7454e59875](https://linux-hardware.org/?probe=7454e59875) | Sep 04, 2024 |
| HUAWEI        | BOHB-WAX9                   | [865f1eb417](https://linux-hardware.org/?probe=865f1eb417) | Sep 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0f5f95ee18](https://linux-hardware.org/?probe=0f5f95ee18) | Sep 04, 2024 |
| HUAWEI        | BOHB-WAX9                   | [f77ded39c0](https://linux-hardware.org/?probe=f77ded39c0) | Sep 04, 2024 |
| EXTRA Comp... | exone go Premico 1580 X1... | [1703bad8ec](https://linux-hardware.org/?probe=1703bad8ec) | Sep 03, 2024 |
| Dell          | Inspiron 5566               | [84f12b65b5](https://linux-hardware.org/?probe=84f12b65b5) | Sep 03, 2024 |
| Lenovo        | ThinkPad W520 427637U       | [ca76b9cc1f](https://linux-hardware.org/?probe=ca76b9cc1f) | Sep 03, 2024 |
| MSI           | Prestige 16 AI Evo B1MG     | [6218dfd8cc](https://linux-hardware.org/?probe=6218dfd8cc) | Sep 03, 2024 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [e22706262c](https://linux-hardware.org/?probe=e22706262c) | Sep 03, 2024 |
| ASUSTek       | N550LF                      | [62e647ec99](https://linux-hardware.org/?probe=62e647ec99) | Sep 02, 2024 |
| Avell         | A52i                        | [c3a2ce627d](https://linux-hardware.org/?probe=c3a2ce627d) | Sep 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a1e397371d](https://linux-hardware.org/?probe=a1e397371d) | Sep 02, 2024 |
| Dell          | G7 7588                     | [ea9cfd2431](https://linux-hardware.org/?probe=ea9cfd2431) | Sep 02, 2024 |
| Toshiba       | Satellite P200D             | [ee90ede472](https://linux-hardware.org/?probe=ee90ede472) | Sep 02, 2024 |
| ASUSTek       | Q551LNB                     | [1b15832563](https://linux-hardware.org/?probe=1b15832563) | Sep 02, 2024 |
| HP            | ENVY dv7                    | [d097b50f4b](https://linux-hardware.org/?probe=d097b50f4b) | Sep 01, 2024 |
| Dell          | Vostro 5490                 | [93c5d6537d](https://linux-hardware.org/?probe=93c5d6537d) | Sep 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [db303fb0b8](https://linux-hardware.org/?probe=db303fb0b8) | Sep 01, 2024 |
| HP            | ProBook 650 G1              | [1275536428](https://linux-hardware.org/?probe=1275536428) | Aug 30, 2024 |
| HP            | OMEN Laptop 15-en0xxx       | [1e19fc2c83](https://linux-hardware.org/?probe=1e19fc2c83) | Aug 30, 2024 |
| Lenovo        | IdeaPad Y580                | [6173a7b633](https://linux-hardware.org/?probe=6173a7b633) | Aug 29, 2024 |
| Lenovo        | Z710 20250                  | [c3ff73a027](https://linux-hardware.org/?probe=c3ff73a027) | Aug 29, 2024 |
| Dell          | G15 Special Edition 5521    | [c48740cc71](https://linux-hardware.org/?probe=c48740cc71) | Aug 29, 2024 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [a65838a8cd](https://linux-hardware.org/?probe=a65838a8cd) | Aug 29, 2024 |
| HP            | ProBook 6570b               | [6790f5a0e7](https://linux-hardware.org/?probe=6790f5a0e7) | Aug 29, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | [778ec7792e](https://linux-hardware.org/?probe=778ec7792e) | Aug 28, 2024 |
| Google        | Peppy                       | [14671acbf5](https://linux-hardware.org/?probe=14671acbf5) | Aug 28, 2024 |
| Apple         | MacBookPro14,1              | [266e0dc6f8](https://linux-hardware.org/?probe=266e0dc6f8) | Aug 28, 2024 |
| Acer          | Predator PH16-71            | [345d56e949](https://linux-hardware.org/?probe=345d56e949) | Aug 28, 2024 |
| Lenovo        | Y720-15IKB 80VR             | [cb760202a2](https://linux-hardware.org/?probe=cb760202a2) | Aug 28, 2024 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [225d291dce](https://linux-hardware.org/?probe=225d291dce) | Aug 28, 2024 |
| Avell         | A70 ION                     | [afe0116751](https://linux-hardware.org/?probe=afe0116751) | Aug 28, 2024 |
| Avell         | A70 ION                     | [690eb5e9c8](https://linux-hardware.org/?probe=690eb5e9c8) | Aug 27, 2024 |
| Lenovo        | ThinkPad E560 20EV002FCA    | [2fbb53bccc](https://linux-hardware.org/?probe=2fbb53bccc) | Aug 27, 2024 |
| ASUSTek       | G751JM                      | [a445b313f7](https://linux-hardware.org/?probe=a445b313f7) | Aug 27, 2024 |
| ASUSTek       | G751JM                      | [03a0eaa1e2](https://linux-hardware.org/?probe=03a0eaa1e2) | Aug 27, 2024 |
| Lenovo        | Legion Pro 5 16IRX9 83DF    | [4d7cca554c](https://linux-hardware.org/?probe=4d7cca554c) | Aug 27, 2024 |
| Apple         | MacBookPro6,2               | [051889efb2](https://linux-hardware.org/?probe=051889efb2) | Aug 27, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3745bf6bc8](https://linux-hardware.org/?probe=3745bf6bc8) | Aug 27, 2024 |
| Acer          | Nitro AN515-58              | [d87a56b08b](https://linux-hardware.org/?probe=d87a56b08b) | Aug 27, 2024 |
| Acer          | Aspire A315-51              | [ac66939839](https://linux-hardware.org/?probe=ac66939839) | Aug 27, 2024 |
| Lenovo        | ThinkPad T460s 20FAS2CM0... | [d93fcd5f93](https://linux-hardware.org/?probe=d93fcd5f93) | Aug 26, 2024 |
| HUAWEI        | KLVL-WXXW                   | [d27ecef002](https://linux-hardware.org/?probe=d27ecef002) | Aug 26, 2024 |
| MSI           | PRO B760-P WIFI DDR4        | [4c795126c5](https://linux-hardware.org/?probe=4c795126c5) | Aug 26, 2024 |
| Apple         | MacBookPro14,1              | [66f202b859](https://linux-hardware.org/?probe=66f202b859) | Aug 26, 2024 |
| Acer          | Aspire 5755G                | [0482183a93](https://linux-hardware.org/?probe=0482183a93) | Aug 26, 2024 |
| HP            | 250 G8 Notebook PC          | [293d053b9d](https://linux-hardware.org/?probe=293d053b9d) | Aug 26, 2024 |
| HUAWEI        | NBLB-WAX9N                  | [b28769357e](https://linux-hardware.org/?probe=b28769357e) | Aug 26, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f8c21d6744](https://linux-hardware.org/?probe=f8c21d6744) | Aug 26, 2024 |
| Acer          | Nitro AN515-43              | [38dbf54973](https://linux-hardware.org/?probe=38dbf54973) | Aug 26, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [ed97ff0bc3](https://linux-hardware.org/?probe=ed97ff0bc3) | Aug 26, 2024 |
| Apple         | MacBookAir7,2               | [9367a60aa0](https://linux-hardware.org/?probe=9367a60aa0) | Aug 25, 2024 |
| Apple         | MacBookPro14,1              | [43ef764a33](https://linux-hardware.org/?probe=43ef764a33) | Aug 25, 2024 |
| Lenovo        | ThinkPad T430 2347GU8       | [599d1526be](https://linux-hardware.org/?probe=599d1526be) | Aug 25, 2024 |
| HP            | 250 G4                      | [ce0e70beac](https://linux-hardware.org/?probe=ce0e70beac) | Aug 25, 2024 |
| Google        | Swanky                      | [588990c2bb](https://linux-hardware.org/?probe=588990c2bb) | Aug 25, 2024 |
| Acer          | Aspire A315-58              | [8b48db79d9](https://linux-hardware.org/?probe=8b48db79d9) | Aug 25, 2024 |
| Lenovo        | ThinkPad E560 20EV002FCA    | [314ebec0d5](https://linux-hardware.org/?probe=314ebec0d5) | Aug 25, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | [18052b4a90](https://linux-hardware.org/?probe=18052b4a90) | Aug 25, 2024 |
| HP            | Pavilion g4                 | [c9131e779e](https://linux-hardware.org/?probe=c9131e779e) | Aug 24, 2024 |
| Lenovo        | ThinkPad E16 Gen 2 21MA0... | [93731e82be](https://linux-hardware.org/?probe=93731e82be) | Aug 24, 2024 |
| Lenovo        | ThinkPad X280 20KES4XS00    | [fc32fd9284](https://linux-hardware.org/?probe=fc32fd9284) | Aug 24, 2024 |
| ASUSTek       | ROG Zephyrus G16 GU603ZU... | [3226ae443d](https://linux-hardware.org/?probe=3226ae443d) | Aug 24, 2024 |
| Acer          | Aspire5750G                 | [3bfc89a964](https://linux-hardware.org/?probe=3bfc89a964) | Aug 23, 2024 |
| Dell          | Latitude 14 Rugged (5404... | [98393b8796](https://linux-hardware.org/?probe=98393b8796) | Aug 23, 2024 |
| Dell          | Latitude 14 Rugged (5404... | [8457bf32ea](https://linux-hardware.org/?probe=8457bf32ea) | Aug 23, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [b8511c939d](https://linux-hardware.org/?probe=b8511c939d) | Aug 23, 2024 |
| Dell          | Latitude 7410               | [7599e02582](https://linux-hardware.org/?probe=7599e02582) | Aug 23, 2024 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [2eb4a32e24](https://linux-hardware.org/?probe=2eb4a32e24) | Aug 23, 2024 |
| HP            | Pavilion g6                 | [6d362ed565](https://linux-hardware.org/?probe=6d362ed565) | Aug 23, 2024 |
| HP            | EliteBook 8470w             | [41ca7ce107](https://linux-hardware.org/?probe=41ca7ce107) | Aug 22, 2024 |
| Lenovo        | Legion 5 Pro 16IAH7 82S0    | [d8dd107aff](https://linux-hardware.org/?probe=d8dd107aff) | Aug 22, 2024 |
| HP            | EliteBook 8470w             | [42a6e42a14](https://linux-hardware.org/?probe=42a6e42a14) | Aug 22, 2024 |
| Dell          | Latitude 5530               | [1d1d36a896](https://linux-hardware.org/?probe=1d1d36a896) | Aug 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [200dac2a14](https://linux-hardware.org/?probe=200dac2a14) | Aug 21, 2024 |
| HP            | Laptop 15s-eq0xxx           | [0bb57c91c7](https://linux-hardware.org/?probe=0bb57c91c7) | Aug 21, 2024 |
| HP            | Laptop 15-dy2xxx            | [738040b6c7](https://linux-hardware.org/?probe=738040b6c7) | Aug 21, 2024 |
| Lenovo        | ThinkPad W541 20EF000HUS    | [45c924bd76](https://linux-hardware.org/?probe=45c924bd76) | Aug 21, 2024 |
| MSI           | Vector 16 HX A13VHG         | [d63070557d](https://linux-hardware.org/?probe=d63070557d) | Aug 20, 2024 |
| Lenovo        | ThinkPad T440p 20AWS1MK0... | [2fca02ea81](https://linux-hardware.org/?probe=2fca02ea81) | Aug 20, 2024 |
| Acer          | Nitro AN515-55              | [8efd1866d7](https://linux-hardware.org/?probe=8efd1866d7) | Aug 20, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [e06d0034c0](https://linux-hardware.org/?probe=e06d0034c0) | Aug 20, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | [80e61cfbd1](https://linux-hardware.org/?probe=80e61cfbd1) | Aug 20, 2024 |
| HP            | OMEN by Laptop              | [a81b5c0a55](https://linux-hardware.org/?probe=a81b5c0a55) | Aug 19, 2024 |
| HP            | Victus by Laptop 16-e0xx... | [d2a5d429a4](https://linux-hardware.org/?probe=d2a5d429a4) | Aug 19, 2024 |
| HP            | Victus by Laptop 16-e0xx... | [dfe46ace3b](https://linux-hardware.org/?probe=dfe46ace3b) | Aug 19, 2024 |
| HP            | EliteBook 8570p             | [1dff9e4f43](https://linux-hardware.org/?probe=1dff9e4f43) | Aug 19, 2024 |
| Apple         | MacBookPro9,2               | [4b39a4746d](https://linux-hardware.org/?probe=4b39a4746d) | Aug 19, 2024 |
| Acer          | Aspire E5-771G              | [806535f037](https://linux-hardware.org/?probe=806535f037) | Aug 19, 2024 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [f1dce9d246](https://linux-hardware.org/?probe=f1dce9d246) | Aug 18, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [82c27e10b6](https://linux-hardware.org/?probe=82c27e10b6) | Aug 18, 2024 |
| HP            | Dragonfly Pro Laptop PC     | [5ac3ebe458](https://linux-hardware.org/?probe=5ac3ebe458) | Aug 18, 2024 |
| HP            | ZBook 17 G6                 | [e6928ca128](https://linux-hardware.org/?probe=e6928ca128) | Aug 17, 2024 |
| HP            | G62                         | [a81c67e624](https://linux-hardware.org/?probe=a81c67e624) | Aug 17, 2024 |
| HP            | G62                         | [1cd8015652](https://linux-hardware.org/?probe=1cd8015652) | Aug 17, 2024 |
| ASUSTek       | Zephyrus M GM501GS          | [bb4bf7b39c](https://linux-hardware.org/?probe=bb4bf7b39c) | Aug 17, 2024 |
| Acer          | Nitro AN17-41               | [da4f23c3b8](https://linux-hardware.org/?probe=da4f23c3b8) | Aug 16, 2024 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [baa230a51b](https://linux-hardware.org/?probe=baa230a51b) | Aug 16, 2024 |
| Dell          | Vostro 3405                 | [e0edcf5178](https://linux-hardware.org/?probe=e0edcf5178) | Aug 15, 2024 |
| Lenovo        | ThinkPad T460 20FMS5DX00    | [fab5ffbd76](https://linux-hardware.org/?probe=fab5ffbd76) | Aug 15, 2024 |
| Toshiba       | Satellite L50D-A            | [fac7ed2f09](https://linux-hardware.org/?probe=fac7ed2f09) | Aug 15, 2024 |
| Toshiba       | Satellite L50D-A            | [fb54610e9a](https://linux-hardware.org/?probe=fb54610e9a) | Aug 15, 2024 |
| Lenovo        | ThinkPad T495 20NJ000XRT    | [19a31bef91](https://linux-hardware.org/?probe=19a31bef91) | Aug 14, 2024 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | [5e9f9c2509](https://linux-hardware.org/?probe=5e9f9c2509) | Aug 14, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [6d80717dbe](https://linux-hardware.org/?probe=6d80717dbe) | Aug 14, 2024 |
| HP            | ProBook 4740s               | [d515f60fdf](https://linux-hardware.org/?probe=d515f60fdf) | Aug 14, 2024 |
| HP            | ENVY Notebook               | [fa59ee7fd3](https://linux-hardware.org/?probe=fa59ee7fd3) | Aug 14, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [b9d3a6f664](https://linux-hardware.org/?probe=b9d3a6f664) | Aug 14, 2024 |
| System76      | Galago Pro                  | [50dd4a443b](https://linux-hardware.org/?probe=50dd4a443b) | Aug 14, 2024 |
| Alienware     | 17 R4                       | [c88b350309](https://linux-hardware.org/?probe=c88b350309) | Aug 14, 2024 |
| HUAWEI        | RLEF-XX                     | [01008e9053](https://linux-hardware.org/?probe=01008e9053) | Aug 13, 2024 |
| Teclast       | F6                          | [04899994bb](https://linux-hardware.org/?probe=04899994bb) | Aug 13, 2024 |
| Dell          | Latitude E7250              | [d36fafcd47](https://linux-hardware.org/?probe=d36fafcd47) | Aug 13, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a87596a92c](https://linux-hardware.org/?probe=a87596a92c) | Aug 13, 2024 |
| Lenovo        | G50-70 20351                | [b7cfbf4166](https://linux-hardware.org/?probe=b7cfbf4166) | Aug 13, 2024 |
| MSI           | GF63 Thin 9SCX              | [c82fa1eaec](https://linux-hardware.org/?probe=c82fa1eaec) | Aug 13, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [5fa457df46](https://linux-hardware.org/?probe=5fa457df46) | Aug 12, 2024 |
| GPD           | G1619-01                    | [f01b31246d](https://linux-hardware.org/?probe=f01b31246d) | Aug 12, 2024 |
| Lenovo        | ThinkPad T560 20FJS3X800    | [6a14a30f0c](https://linux-hardware.org/?probe=6a14a30f0c) | Aug 11, 2024 |
| Medion        | Unknown                     | [4858654f26](https://linux-hardware.org/?probe=4858654f26) | Aug 10, 2024 |
| HP            | Dragonfly Pro Laptop PC     | [0569bb5626](https://linux-hardware.org/?probe=0569bb5626) | Aug 10, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [4bc5b1dcaa](https://linux-hardware.org/?probe=4bc5b1dcaa) | Aug 10, 2024 |
| Gigabyte      | B560 DS3H AC-Y1             | [1603003755](https://linux-hardware.org/?probe=1603003755) | Aug 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [0d1b4d0ac4](https://linux-hardware.org/?probe=0d1b4d0ac4) | Aug 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [8561a6bc16](https://linux-hardware.org/?probe=8561a6bc16) | Aug 09, 2024 |
| MSI           | GF63 8RD                    | [35cb330aea](https://linux-hardware.org/?probe=35cb330aea) | Aug 08, 2024 |
| ASUSTek       | X555LF                      | [54630e35eb](https://linux-hardware.org/?probe=54630e35eb) | Aug 08, 2024 |
| Lenovo        | IdeaPad U530 Touch 20289    | [a08e92ba45](https://linux-hardware.org/?probe=a08e92ba45) | Aug 08, 2024 |
| ASUSTek       | X555LF                      | [cfb3e05d31](https://linux-hardware.org/?probe=cfb3e05d31) | Aug 08, 2024 |
| Acer          | Nitro ANV15-41              | [edc39e3b63](https://linux-hardware.org/?probe=edc39e3b63) | Aug 08, 2024 |
| HP            | Pavilion Plus Laptop 14-... | [d80eec693d](https://linux-hardware.org/?probe=d80eec693d) | Aug 07, 2024 |
| HP            | Laptop 15s-eq0xxx           | [959b339997](https://linux-hardware.org/?probe=959b339997) | Aug 07, 2024 |
| HP            | Laptop 15s-eq0xxx           | [6a79a09c14](https://linux-hardware.org/?probe=6a79a09c14) | Aug 07, 2024 |
| MSI           | Stealth 16 AI Studio A1V... | [3a5fc2d641](https://linux-hardware.org/?probe=3a5fc2d641) | Aug 07, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [ea0fee7c1b](https://linux-hardware.org/?probe=ea0fee7c1b) | Aug 07, 2024 |
| Dell          | Inspiron 3558               | [6c5260f3ee](https://linux-hardware.org/?probe=6c5260f3ee) | Aug 07, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [dd637d2621](https://linux-hardware.org/?probe=dd637d2621) | Aug 06, 2024 |
| HP            | ProBook 640 G8 Notebook ... | [6c0d4e1016](https://linux-hardware.org/?probe=6c0d4e1016) | Aug 05, 2024 |
| Acer          | Aspire A315-24P             | [86141fc5e8](https://linux-hardware.org/?probe=86141fc5e8) | Aug 05, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [b74b8e3c65](https://linux-hardware.org/?probe=b74b8e3c65) | Aug 04, 2024 |
| Dell          | Latitude 5400               | [a10df67a2c](https://linux-hardware.org/?probe=a10df67a2c) | Aug 04, 2024 |
| ASUSTek       | ASUS Vivobook S 14 M5406... | [ec4802e83f](https://linux-hardware.org/?probe=ec4802e83f) | Aug 03, 2024 |
| ASUSTek       | Zenbook UX3404VA_Q420VA     | [85608395f2](https://linux-hardware.org/?probe=85608395f2) | Aug 03, 2024 |
| Unknown       | Alder Lake N                | [c1fc9502d2](https://linux-hardware.org/?probe=c1fc9502d2) | Aug 03, 2024 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [76a4575a53](https://linux-hardware.org/?probe=76a4575a53) | Aug 03, 2024 |
| Unknown       | Alder Lake N                | [827d3a9aad](https://linux-hardware.org/?probe=827d3a9aad) | Aug 03, 2024 |
| HP            | Laptop 17t-cn200            | [937e050040](https://linux-hardware.org/?probe=937e050040) | Aug 03, 2024 |
| HP            | Laptop 17t-cn200            | [9fe5496875](https://linux-hardware.org/?probe=9fe5496875) | Aug 03, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | [2c21e380ca](https://linux-hardware.org/?probe=2c21e380ca) | Aug 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [0155d5f659](https://linux-hardware.org/?probe=0155d5f659) | Aug 02, 2024 |
| Dell          | Latitude E6440              | [9102489602](https://linux-hardware.org/?probe=9102489602) | Aug 02, 2024 |
| Apple         | MacBookPro10,1              | [f5ab931e82](https://linux-hardware.org/?probe=f5ab931e82) | Aug 02, 2024 |
| HUAWEI        | KLVD-WXX9                   | [ca2053f1f3](https://linux-hardware.org/?probe=ca2053f1f3) | Aug 01, 2024 |
| XIAOMI        | Redmi Book Pro 14 2024      | [5a51521541](https://linux-hardware.org/?probe=5a51521541) | Aug 01, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [15d899f5d6](https://linux-hardware.org/?probe=15d899f5d6) | Aug 01, 2024 |
| Dell          | Vostro 5490                 | [8582fd1c71](https://linux-hardware.org/?probe=8582fd1c71) | Aug 01, 2024 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [e1048b263b](https://linux-hardware.org/?probe=e1048b263b) | Aug 01, 2024 |
| Apple         | MacBookAir4,1               | [f65048efaa](https://linux-hardware.org/?probe=f65048efaa) | Aug 01, 2024 |
| Apple         | MacBookAir4,1               | [c7ffe318c6](https://linux-hardware.org/?probe=c7ffe318c6) | Aug 01, 2024 |
| Acer          | Aspire A515-52G             | [1cc3b703fd](https://linux-hardware.org/?probe=1cc3b703fd) | Jul 31, 2024 |
| Dell          | Latitude 5290               | [2252d3473f](https://linux-hardware.org/?probe=2252d3473f) | Jul 31, 2024 |
| Lenovo        | ThinkPad T440s 20ARS2410... | [a3226495ea](https://linux-hardware.org/?probe=a3226495ea) | Jul 31, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | [5bf5981935](https://linux-hardware.org/?probe=5bf5981935) | Jul 30, 2024 |
| System76      | Oryx Pro                    | [e599b5c5c6](https://linux-hardware.org/?probe=e599b5c5c6) | Jul 30, 2024 |
| Apple         | MacBookPro10,1              | [523817080f](https://linux-hardware.org/?probe=523817080f) | Jul 30, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2f53cf4143](https://linux-hardware.org/?probe=2f53cf4143) | Jul 30, 2024 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [c77623de7c](https://linux-hardware.org/?probe=c77623de7c) | Jul 30, 2024 |
| Notebook      | V54x_6x_TU                  | [3118d3303f](https://linux-hardware.org/?probe=3118d3303f) | Jul 29, 2024 |
| System76      | Darter Pro                  | [73924f0f4c](https://linux-hardware.org/?probe=73924f0f4c) | Jul 29, 2024 |
| Lenovo        | B590 20206                  | [9c18477079](https://linux-hardware.org/?probe=9c18477079) | Jul 28, 2024 |
| Lenovo        | B590 20206                  | [52540f6cac](https://linux-hardware.org/?probe=52540f6cac) | Jul 28, 2024 |
| Acer          | Aspire A315-23              | [75024afb37](https://linux-hardware.org/?probe=75024afb37) | Jul 28, 2024 |
| System76      | Gazelle                     | [fec67421f6](https://linux-hardware.org/?probe=fec67421f6) | Jul 28, 2024 |
| HUAWEI        | BOM-WXX9                    | [b11bd3da5e](https://linux-hardware.org/?probe=b11bd3da5e) | Jul 27, 2024 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [2e002b034a](https://linux-hardware.org/?probe=2e002b034a) | Jul 26, 2024 |
| Notebook      | NL40_50CU                   | [8298c29f96](https://linux-hardware.org/?probe=8298c29f96) | Jul 26, 2024 |
| Dell          | Precision 7710              | [cd66ec6c4f](https://linux-hardware.org/?probe=cd66ec6c4f) | Jul 26, 2024 |
| Apple         | MacBookPro8,1               | [93b0846a8a](https://linux-hardware.org/?probe=93b0846a8a) | Jul 26, 2024 |
| Dell          | Vostro 7570                 | [78d272585d](https://linux-hardware.org/?probe=78d272585d) | Jul 26, 2024 |
| Alienware     | M17xR4                      | [4464fd207d](https://linux-hardware.org/?probe=4464fd207d) | Jul 25, 2024 |
| ASUSTek       | GL702VMK                    | [47b0561d4f](https://linux-hardware.org/?probe=47b0561d4f) | Jul 25, 2024 |
| Dell          | Latitude E7450              | [ba9d36e59d](https://linux-hardware.org/?probe=ba9d36e59d) | Jul 25, 2024 |
| ASUSTek       | N53Jg                       | [0d2baab72b](https://linux-hardware.org/?probe=0d2baab72b) | Jul 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [0ee0fc3367](https://linux-hardware.org/?probe=0ee0fc3367) | Jul 25, 2024 |
| HP            | Compaq Presario CQ60        | [4ce24fa84b](https://linux-hardware.org/?probe=4ce24fa84b) | Jul 25, 2024 |
| HP            | Laptop 15s-eq1xxx           | [8936eea25d](https://linux-hardware.org/?probe=8936eea25d) | Jul 25, 2024 |
| ASUSTek       | GL702VMK                    | [9e3c872bf0](https://linux-hardware.org/?probe=9e3c872bf0) | Jul 24, 2024 |
| HP            | Laptop 14-fq1xxx            | [a1578c19a4](https://linux-hardware.org/?probe=a1578c19a4) | Jul 24, 2024 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [b505ebec8c](https://linux-hardware.org/?probe=b505ebec8c) | Jul 24, 2024 |
| Dell          | G15 5535                    | [cf73f42320](https://linux-hardware.org/?probe=cf73f42320) | Jul 24, 2024 |
| HP            | ProBook 440 14 inch G10 ... | [11a73bf48c](https://linux-hardware.org/?probe=11a73bf48c) | Jul 23, 2024 |
| Lenovo        | YogaPro 14s APH8 82Y8       | [2b41283766](https://linux-hardware.org/?probe=2b41283766) | Jul 23, 2024 |
| HP            | 250 G5 Notebook PC          | [7124648707](https://linux-hardware.org/?probe=7124648707) | Jul 23, 2024 |
| Lenovo        | YogaPro 14s APH8 82Y8       | [3d7bb2e0f5](https://linux-hardware.org/?probe=3d7bb2e0f5) | Jul 23, 2024 |
| ASUSTek       | G75VX                       | [54bea2fd99](https://linux-hardware.org/?probe=54bea2fd99) | Jul 23, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | [19dbbe1ce6](https://linux-hardware.org/?probe=19dbbe1ce6) | Jul 23, 2024 |
| Dell          | Latitude E5470              | [d2229f1d02](https://linux-hardware.org/?probe=d2229f1d02) | Jul 23, 2024 |
| Apple         | MacBookPro11,3              | [bd5f65d8e6](https://linux-hardware.org/?probe=bd5f65d8e6) | Jul 22, 2024 |
| ASUSTek       | K50IN                       | [0bf5e888bb](https://linux-hardware.org/?probe=0bf5e888bb) | Jul 22, 2024 |
| SLIMBOOK      | PROX-AMD5                   | [9ff30b3a99](https://linux-hardware.org/?probe=9ff30b3a99) | Jul 21, 2024 |
| Acer          | Nitro AN515-45              | [19cb8f5e37](https://linux-hardware.org/?probe=19cb8f5e37) | Jul 21, 2024 |
| Dell          | Latitude 14 Rugged (5404... | [212537f148](https://linux-hardware.org/?probe=212537f148) | Jul 21, 2024 |
| HP            | 250 G4                      | [55f1ab783f](https://linux-hardware.org/?probe=55f1ab783f) | Jul 20, 2024 |
| Acer          | Predator PH16-71            | [edc46c2a54](https://linux-hardware.org/?probe=edc46c2a54) | Jul 20, 2024 |
| Dell          | G7 7588                     | [500011a5f7](https://linux-hardware.org/?probe=500011a5f7) | Jul 20, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [a8a25153b0](https://linux-hardware.org/?probe=a8a25153b0) | Jul 19, 2024 |
| HUAWEI        | BOHB-WAX9                   | [342f5b74f4](https://linux-hardware.org/?probe=342f5b74f4) | Jul 19, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [bf416ca62e](https://linux-hardware.org/?probe=bf416ca62e) | Jul 19, 2024 |
| Monster       | TULPAR T7 V20.6             | [3fa804d733](https://linux-hardware.org/?probe=3fa804d733) | Jul 18, 2024 |
| ASUSTek       | N750JK                      | [153b50caa5](https://linux-hardware.org/?probe=153b50caa5) | Jul 18, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [b6d76397c7](https://linux-hardware.org/?probe=b6d76397c7) | Jul 18, 2024 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | [4f76bfd9bc](https://linux-hardware.org/?probe=4f76bfd9bc) | Jul 18, 2024 |
| HP            | Pavilion 15                 | [9a417a6d47](https://linux-hardware.org/?probe=9a417a6d47) | Jul 18, 2024 |
| MSI           | Katana GF76 11UD            | [970f29e1af](https://linux-hardware.org/?probe=970f29e1af) | Jul 18, 2024 |
| Lenovo        | ThinkPad T530 2394EM4       | [0153f0e417](https://linux-hardware.org/?probe=0153f0e417) | Jul 17, 2024 |
| Dell          | Precision M4600             | [ae485ec60d](https://linux-hardware.org/?probe=ae485ec60d) | Jul 17, 2024 |
| ASUSTek       | S550CM                      | [effe093e11](https://linux-hardware.org/?probe=effe093e11) | Jul 17, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [97a6642e86](https://linux-hardware.org/?probe=97a6642e86) | Jul 16, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [d7fcdc7953](https://linux-hardware.org/?probe=d7fcdc7953) | Jul 16, 2024 |
| Dell          | Latitude 5420               | [6bcce50c01](https://linux-hardware.org/?probe=6bcce50c01) | Jul 16, 2024 |
| Dell          | Latitude 7300               | [6df91d1224](https://linux-hardware.org/?probe=6df91d1224) | Jul 16, 2024 |
| Apple         | MacBookAir7,2               | [fb2b18385d](https://linux-hardware.org/?probe=fb2b18385d) | Jul 16, 2024 |
| Apple         | MacBookAir7,2               | [a4156a8d93](https://linux-hardware.org/?probe=a4156a8d93) | Jul 15, 2024 |
| Acer          | Predator PH315-52           | [a914faf95f](https://linux-hardware.org/?probe=a914faf95f) | Jul 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [1af716d016](https://linux-hardware.org/?probe=1af716d016) | Jul 15, 2024 |
| HP            | Compaq Presario CQ40        | [d1e485d3c7](https://linux-hardware.org/?probe=d1e485d3c7) | Jul 15, 2024 |
| Medion        | Unknown                     | [d70e4741b2](https://linux-hardware.org/?probe=d70e4741b2) | Jul 14, 2024 |
| Samsung       | 300E5E/300E4E/300E5V/300... | [ca43efc3a4](https://linux-hardware.org/?probe=ca43efc3a4) | Jul 14, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | [6ed4e23d97](https://linux-hardware.org/?probe=6ed4e23d97) | Jul 14, 2024 |
| Dell          | Latitude 7300               | [d28ba6dc8b](https://linux-hardware.org/?probe=d28ba6dc8b) | Jul 14, 2024 |
| Teclast       | F7 Plus                     | [ceec3db3b3](https://linux-hardware.org/?probe=ceec3db3b3) | Jul 13, 2024 |
| HP            | Pavilion dv7                | [54f99671a4](https://linux-hardware.org/?probe=54f99671a4) | Jul 12, 2024 |
| Apple         | MacBookPro12,1              | [54bbc20d8b](https://linux-hardware.org/?probe=54bbc20d8b) | Jul 12, 2024 |
| Apple         | MacBookPro12,1              | [ae8d2e9d45](https://linux-hardware.org/?probe=ae8d2e9d45) | Jul 12, 2024 |
| Apple         | MacBookPro11,1              | [31b40b4ff0](https://linux-hardware.org/?probe=31b40b4ff0) | Jul 12, 2024 |
| Framework     | Laptop (12th Gen Intel C... | [d2c62dfa17](https://linux-hardware.org/?probe=d2c62dfa17) | Jul 11, 2024 |
| Lenovo        | ThinkPad T440p 20AW000RU... | [5b113db58e](https://linux-hardware.org/?probe=5b113db58e) | Jul 10, 2024 |
| Acidanther... | MacBookPro16,1              | [bf5642784f](https://linux-hardware.org/?probe=bf5642784f) | Jul 10, 2024 |
| Apple         | MacBookAir9,1               | [509b70f889](https://linux-hardware.org/?probe=509b70f889) | Jul 09, 2024 |
| DERE          | V14                         | [4475968bb7](https://linux-hardware.org/?probe=4475968bb7) | Jul 09, 2024 |
| System76      | Gazelle                     | [7738eb7b67](https://linux-hardware.org/?probe=7738eb7b67) | Jul 09, 2024 |
| Fujitsu       | LIFEBOOK AH532/G52          | [f9abf3b9eb](https://linux-hardware.org/?probe=f9abf3b9eb) | Jul 09, 2024 |
| Dell          | Inspiron 5567               | [03d2cff74e](https://linux-hardware.org/?probe=03d2cff74e) | Jul 09, 2024 |
| System76      | Bonobo WS                   | [f29db971cf](https://linux-hardware.org/?probe=f29db971cf) | Jul 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [a0cb1ea15b](https://linux-hardware.org/?probe=a0cb1ea15b) | Jul 08, 2024 |
| Apple         | MacBookPro9,2               | [06199956d3](https://linux-hardware.org/?probe=06199956d3) | Jul 08, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [89528fc843](https://linux-hardware.org/?probe=89528fc843) | Jul 08, 2024 |
| HP            | EliteBook 840 G6            | [ff7b2c54f1](https://linux-hardware.org/?probe=ff7b2c54f1) | Jul 07, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [9999aa95d2](https://linux-hardware.org/?probe=9999aa95d2) | Jul 07, 2024 |
| Dell          | Inspiron 15 5518            | [b2a5e8f87e](https://linux-hardware.org/?probe=b2a5e8f87e) | Jul 07, 2024 |
| HP            | 250 G4                      | [54e9d01e97](https://linux-hardware.org/?probe=54e9d01e97) | Jul 07, 2024 |
| Lenovo        | 3000 G530 4151/200          | [e5dda11a53](https://linux-hardware.org/?probe=e5dda11a53) | Jul 07, 2024 |
| MSI           | Creator M16 HX C14VFG       | [f53a34f3c7](https://linux-hardware.org/?probe=f53a34f3c7) | Jul 07, 2024 |
| Medion        | Unknown                     | [1a6f991fa1](https://linux-hardware.org/?probe=1a6f991fa1) | Jul 06, 2024 |
| Dell          | Inspiron 11-3168            | [dda9042e33](https://linux-hardware.org/?probe=dda9042e33) | Jul 06, 2024 |
| Apple         | MacBookPro11,3              | [1d4a0d0185](https://linux-hardware.org/?probe=1d4a0d0185) | Jul 06, 2024 |
| System76      | Darter Pro                  | [38e13c5e90](https://linux-hardware.org/?probe=38e13c5e90) | Jul 06, 2024 |
| Medion        | P6689 MD60968               | [dbbcaac405](https://linux-hardware.org/?probe=dbbcaac405) | Jul 05, 2024 |
| Alienware     | x17 R2                      | [ffd0134dc6](https://linux-hardware.org/?probe=ffd0134dc6) | Jul 04, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | [10c9d1a180](https://linux-hardware.org/?probe=10c9d1a180) | Jul 04, 2024 |
| HUAWEI        | VLT-WX0                     | [f81bb40cb8](https://linux-hardware.org/?probe=f81bb40cb8) | Jul 03, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | [11d3c82806](https://linux-hardware.org/?probe=11d3c82806) | Jul 02, 2024 |
| Dell          | G7 7588                     | [53fc2778ac](https://linux-hardware.org/?probe=53fc2778ac) | Jul 02, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [43eb169014](https://linux-hardware.org/?probe=43eb169014) | Jul 02, 2024 |
| Lenovo        | ThinkPad L480 20LTS2A30U    | [c89bdf0032](https://linux-hardware.org/?probe=c89bdf0032) | Jul 02, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [8f7463bc2d](https://linux-hardware.org/?probe=8f7463bc2d) | Jul 01, 2024 |
| Dell          | G15 5535                    | [c6e745bd08](https://linux-hardware.org/?probe=c6e745bd08) | Jul 01, 2024 |
| SLIMBOOK      | TITAN                       | [74bc85df70](https://linux-hardware.org/?probe=74bc85df70) | Jul 01, 2024 |
| Dell          | Vostro 3550                 | [1538916e34](https://linux-hardware.org/?probe=1538916e34) | Jun 30, 2024 |
| HP            | Laptop 14s-fq1xxx           | [f706b8cf5a](https://linux-hardware.org/?probe=f706b8cf5a) | Jun 30, 2024 |
| Dell          | Latitude E7240              | [0fa0d32428](https://linux-hardware.org/?probe=0fa0d32428) | Jun 29, 2024 |
| ASUSTek       | ASUS Vivobook Pro 15 N65... | [60ca4af7d3](https://linux-hardware.org/?probe=60ca4af7d3) | Jun 29, 2024 |
| MSI           | GE60 2PE                    | [b7a466ecc5](https://linux-hardware.org/?probe=b7a466ecc5) | Jun 29, 2024 |
| HP            | EliteBook 840 G6            | [55e4321d88](https://linux-hardware.org/?probe=55e4321d88) | Jun 29, 2024 |
| HUAWEI        | BOM-WXX9                    | [aa6b79b180](https://linux-hardware.org/?probe=aa6b79b180) | Jun 29, 2024 |
| System76      | Gazelle                     | [77c78ff63c](https://linux-hardware.org/?probe=77c78ff63c) | Jun 29, 2024 |
| MSI           | GP62M 7RD                   | [f7fc713d82](https://linux-hardware.org/?probe=f7fc713d82) | Jun 28, 2024 |
| MSI           | Creator 15 A10SGS           | [9d64eab3a9](https://linux-hardware.org/?probe=9d64eab3a9) | Jun 28, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | [f37e384bd9](https://linux-hardware.org/?probe=f37e384bd9) | Jun 28, 2024 |
| Gigabyte      | G6 KF                       | [e524f43718](https://linux-hardware.org/?probe=e524f43718) | Jun 28, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | [fb7d22b01d](https://linux-hardware.org/?probe=fb7d22b01d) | Jun 28, 2024 |
| MSI           | GP62M 7RD                   | [7eaf8587d4](https://linux-hardware.org/?probe=7eaf8587d4) | Jun 27, 2024 |
| HP            | OMEN Laptop 15-en1xxx       | [c9f7dbd623](https://linux-hardware.org/?probe=c9f7dbd623) | Jun 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [63282f0687](https://linux-hardware.org/?probe=63282f0687) | Jun 27, 2024 |
| System76      | Serval WS                   | [ac24763016](https://linux-hardware.org/?probe=ac24763016) | Jun 27, 2024 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | [ca8dd46553](https://linux-hardware.org/?probe=ca8dd46553) | Jun 26, 2024 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | [d0136ee04f](https://linux-hardware.org/?probe=d0136ee04f) | Jun 26, 2024 |
| LG Electro... | 17Z90N-R.AAC8U1             | [c2b18d0b6c](https://linux-hardware.org/?probe=c2b18d0b6c) | Jun 26, 2024 |
| HUAWEI        | BOM-WXX9                    | [54cab18b2c](https://linux-hardware.org/?probe=54cab18b2c) | Jun 26, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [08fec730c6](https://linux-hardware.org/?probe=08fec730c6) | Jun 26, 2024 |
| HP            | ZBook 15u G5                | [13113deb85](https://linux-hardware.org/?probe=13113deb85) | Jun 26, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [154f861888](https://linux-hardware.org/?probe=154f861888) | Jun 26, 2024 |
| Dell          | XPS 13 7390                 | [003d750771](https://linux-hardware.org/?probe=003d750771) | Jun 25, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0964e757e8](https://linux-hardware.org/?probe=0964e757e8) | Jun 25, 2024 |
| Acer          | Nitro AN515-44              | [88342fd6d5](https://linux-hardware.org/?probe=88342fd6d5) | Jun 25, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [6269725733](https://linux-hardware.org/?probe=6269725733) | Jun 25, 2024 |
| HP            | EliteBook 8570p             | [6650b4e93d](https://linux-hardware.org/?probe=6650b4e93d) | Jun 24, 2024 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [186d1f827c](https://linux-hardware.org/?probe=186d1f827c) | Jun 24, 2024 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [ab244cc45f](https://linux-hardware.org/?probe=ab244cc45f) | Jun 24, 2024 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [f172d83ec7](https://linux-hardware.org/?probe=f172d83ec7) | Jun 24, 2024 |
| Lenovo        | ThinkPad X230 2325IG8       | [e64978a6d7](https://linux-hardware.org/?probe=e64978a6d7) | Jun 23, 2024 |
| HP            | Victus by Laptop 16-e0xx... | [29d58408c1](https://linux-hardware.org/?probe=29d58408c1) | Jun 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [4ff8cf43c2](https://linux-hardware.org/?probe=4ff8cf43c2) | Jun 22, 2024 |
| Acer          | Predator G3-572             | [4852d6964a](https://linux-hardware.org/?probe=4852d6964a) | Jun 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [11bcad49f7](https://linux-hardware.org/?probe=11bcad49f7) | Jun 22, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [5d284c7c8b](https://linux-hardware.org/?probe=5d284c7c8b) | Jun 22, 2024 |
| HP            | Dragonfly Pro Laptop PC     | [14d0fa062f](https://linux-hardware.org/?probe=14d0fa062f) | Jun 21, 2024 |
| Toshiba       | Satellite E45t-B            | [cc45700d6c](https://linux-hardware.org/?probe=cc45700d6c) | Jun 21, 2024 |
| Apple         | MacBook4,1                  | [e1c1042d53](https://linux-hardware.org/?probe=e1c1042d53) | Jun 20, 2024 |
| HP            | ZBook 17 G6                 | [2095486226](https://linux-hardware.org/?probe=2095486226) | Jun 19, 2024 |
| HP            | OMEN by Laptop              | [d9937127b8](https://linux-hardware.org/?probe=d9937127b8) | Jun 19, 2024 |
| Apple         | MacBook4,1                  | [d604c80259](https://linux-hardware.org/?probe=d604c80259) | Jun 18, 2024 |
| ASUSTek       | GL702VMK                    | [53899b0651](https://linux-hardware.org/?probe=53899b0651) | Jun 18, 2024 |
| Lenovo        | ThinkBook 16 G7 IML 21MS    | [18860f34be](https://linux-hardware.org/?probe=18860f34be) | Jun 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [81eda92b61](https://linux-hardware.org/?probe=81eda92b61) | Jun 17, 2024 |
| Lenovo        | ThinkPad T540p 20BE003AU... | [b350339d8b](https://linux-hardware.org/?probe=b350339d8b) | Jun 17, 2024 |
| Acer          | Aspire A515-54G             | [637324b29c](https://linux-hardware.org/?probe=637324b29c) | Jun 16, 2024 |
| Dell          | Latitude E7240              | [10ea2586d7](https://linux-hardware.org/?probe=10ea2586d7) | Jun 16, 2024 |
| HP            | 15                          | [944d944a3e](https://linux-hardware.org/?probe=944d944a3e) | Jun 16, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [0245272548](https://linux-hardware.org/?probe=0245272548) | Jun 16, 2024 |
| Acer          | Swift SFX14-51G             | [812391b40a](https://linux-hardware.org/?probe=812391b40a) | Jun 16, 2024 |
| Lenovo        | ThinkPad T440s 20ARS0HB0... | [6c013b4999](https://linux-hardware.org/?probe=6c013b4999) | Jun 16, 2024 |
| Apple         | MacBookPro11,2              | [d8be2fc568](https://linux-hardware.org/?probe=d8be2fc568) | Jun 16, 2024 |
| Apple         | MacBookPro11,2              | [5d51b394ff](https://linux-hardware.org/?probe=5d51b394ff) | Jun 16, 2024 |
| HP            | EliteBook 840 G1            | [181b4d6023](https://linux-hardware.org/?probe=181b4d6023) | Jun 16, 2024 |
| HP            | EliteBook 840 G1            | [ffffb8e33b](https://linux-hardware.org/?probe=ffffb8e33b) | Jun 16, 2024 |
| PC Special... | NH5x_7xDPx                  | [c264f3cd40](https://linux-hardware.org/?probe=c264f3cd40) | Jun 16, 2024 |
| HP            | ProBook 450 15.6 inch G9... | [54e7691c73](https://linux-hardware.org/?probe=54e7691c73) | Jun 15, 2024 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [269c4f0a9d](https://linux-hardware.org/?probe=269c4f0a9d) | Jun 13, 2024 |
| LG Electro... | 15Z90N-V.AR52A2             | [36bb248eac](https://linux-hardware.org/?probe=36bb248eac) | Jun 13, 2024 |
| Dell          | Latitude 7480               | [c9ce520244](https://linux-hardware.org/?probe=c9ce520244) | Jun 13, 2024 |
| LG Electro... | 15Z90N-V.AR52A2             | [22fa5f71bb](https://linux-hardware.org/?probe=22fa5f71bb) | Jun 13, 2024 |
| System76      | Lemur Pro                   | [b42a31d837](https://linux-hardware.org/?probe=b42a31d837) | Jun 13, 2024 |
| Lenovo        | Yoga Pro 9 16IMH9 83DN      | [ae087c3229](https://linux-hardware.org/?probe=ae087c3229) | Jun 12, 2024 |
| Dell          | Precision 5520              | [f9af7ebdcc](https://linux-hardware.org/?probe=f9af7ebdcc) | Jun 12, 2024 |
| Dell          | Precision 5520              | [5ffc5b066f](https://linux-hardware.org/?probe=5ffc5b066f) | Jun 12, 2024 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [bf1706da47](https://linux-hardware.org/?probe=bf1706da47) | Jun 11, 2024 |
| Sony          | SVE14A2X1EW                 | [2048f499be](https://linux-hardware.org/?probe=2048f499be) | Jun 11, 2024 |
| Acer          | Predator PH315-54           | [b0bd7d0e16](https://linux-hardware.org/?probe=b0bd7d0e16) | Jun 11, 2024 |
| HP            | Laptop 15q-ds0xxx           | [4636977750](https://linux-hardware.org/?probe=4636977750) | Jun 11, 2024 |
| Dell          | Inspiron 1525               | [4750960106](https://linux-hardware.org/?probe=4750960106) | Jun 11, 2024 |
| Dell          | Precision M6700             | [910ca08946](https://linux-hardware.org/?probe=910ca08946) | Jun 11, 2024 |
| HP            | mt41                        | [8979029b5d](https://linux-hardware.org/?probe=8979029b5d) | Jun 10, 2024 |
| HP            | ProBook 450 G8 Notebook ... | [9687674156](https://linux-hardware.org/?probe=9687674156) | Jun 10, 2024 |
| Lenovo        | ThinkPad T420 418065U       | [9f7eaa959f](https://linux-hardware.org/?probe=9f7eaa959f) | Jun 10, 2024 |
| Apple         | MacBookPro9,2               | [c9eb5827e7](https://linux-hardware.org/?probe=c9eb5827e7) | Jun 10, 2024 |
| Dell          | Precision M6700             | [ff2f8661e9](https://linux-hardware.org/?probe=ff2f8661e9) | Jun 10, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21BV0... | [2ec712b156](https://linux-hardware.org/?probe=2ec712b156) | Jun 09, 2024 |
| HP            | 250 G7 Notebook PC          | [218c416abf](https://linux-hardware.org/?probe=218c416abf) | Jun 09, 2024 |
| Toshiba       | Satellite E45t-B            | [7879555acc](https://linux-hardware.org/?probe=7879555acc) | Jun 09, 2024 |
| Lenovo        | B5400 80B6QB0               | [05953da264](https://linux-hardware.org/?probe=05953da264) | Jun 09, 2024 |
| Dell          | Latitude E6540              | [36e561a31a](https://linux-hardware.org/?probe=36e561a31a) | Jun 08, 2024 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [8462e256b8](https://linux-hardware.org/?probe=8462e256b8) | Jun 08, 2024 |
| HP            | EliteBook 840 G1            | [c197b954a9](https://linux-hardware.org/?probe=c197b954a9) | Jun 07, 2024 |
| MSI           | GX60 3CC                    | [aca5045aba](https://linux-hardware.org/?probe=aca5045aba) | Jun 07, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a787bc6449](https://linux-hardware.org/?probe=a787bc6449) | Jun 07, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7627078958](https://linux-hardware.org/?probe=7627078958) | Jun 07, 2024 |
| Acer          | Aspire A715-42G             | [167f1c0e9c](https://linux-hardware.org/?probe=167f1c0e9c) | Jun 06, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [d9ab37fa2b](https://linux-hardware.org/?probe=d9ab37fa2b) | Jun 06, 2024 |
| Lenovo        | ThinkPad T480 20L6S68T2W    | [9c7b8ae370](https://linux-hardware.org/?probe=9c7b8ae370) | Jun 06, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b71f68fad4](https://linux-hardware.org/?probe=b71f68fad4) | Jun 06, 2024 |
| HUAWEI        | KLVL-WXXW                   | [beca655132](https://linux-hardware.org/?probe=beca655132) | Jun 05, 2024 |
| Dell          | Vostro 3583                 | [f64f416f04](https://linux-hardware.org/?probe=f64f416f04) | Jun 05, 2024 |
| Dell          | Vostro 1510                 | [f92564cf0f](https://linux-hardware.org/?probe=f92564cf0f) | Jun 05, 2024 |
| HP            | Laptop 15-db0xxx            | [dd2101b09a](https://linux-hardware.org/?probe=dd2101b09a) | Jun 05, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [389cba5dac](https://linux-hardware.org/?probe=389cba5dac) | Jun 05, 2024 |
| Apple         | MacBookPro9,2               | [6c88f789c6](https://linux-hardware.org/?probe=6c88f789c6) | Jun 05, 2024 |
| HUAWEI        | KPL-W0X                     | [6809cd5638](https://linux-hardware.org/?probe=6809cd5638) | Jun 04, 2024 |
| MSI           | GX60 3CC                    | [9413730d19](https://linux-hardware.org/?probe=9413730d19) | Jun 04, 2024 |
| ASUSTek       | G750JX                      | [a5580ec212](https://linux-hardware.org/?probe=a5580ec212) | Jun 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [0a84719b87](https://linux-hardware.org/?probe=0a84719b87) | Jun 04, 2024 |
| Dell          | G7 7588                     | [bfe5545e97](https://linux-hardware.org/?probe=bfe5545e97) | Jun 03, 2024 |
| HP            | ENVY NOTEBOOK PC            | [378d0eb91f](https://linux-hardware.org/?probe=378d0eb91f) | Jun 03, 2024 |
| System76      | Pangolin                    | [753cbecca4](https://linux-hardware.org/?probe=753cbecca4) | Jun 03, 2024 |
| LG Electro... | 16Z90R-A.ADC8U1             | [4f91df1047](https://linux-hardware.org/?probe=4f91df1047) | Jun 02, 2024 |
| Apple         | MacBookPro11,1              | [3292a7b915](https://linux-hardware.org/?probe=3292a7b915) | Jun 01, 2024 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [fa1fa5d6ef](https://linux-hardware.org/?probe=fa1fa5d6ef) | Jun 01, 2024 |
| ASUSTek       | TUF Gaming FX505DD          | [9b075c083c](https://linux-hardware.org/?probe=9b075c083c) | May 31, 2024 |
| Apple         | MacBookPro11,1              | [4235731e7a](https://linux-hardware.org/?probe=4235731e7a) | May 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [8ae832a443](https://linux-hardware.org/?probe=8ae832a443) | May 31, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [0fd5ee3376](https://linux-hardware.org/?probe=0fd5ee3376) | May 30, 2024 |
| Acer          | Nitro AN515-53              | [81f35f1ca4](https://linux-hardware.org/?probe=81f35f1ca4) | May 30, 2024 |
| HP            | mt41                        | [634924505d](https://linux-hardware.org/?probe=634924505d) | May 30, 2024 |
| Dell          | Inspiron 7348               | [a513ee6746](https://linux-hardware.org/?probe=a513ee6746) | May 30, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b7a6d5af96](https://linux-hardware.org/?probe=b7a6d5af96) | May 29, 2024 |
| System76      | Galago Pro                  | [8ba7fb6cb9](https://linux-hardware.org/?probe=8ba7fb6cb9) | May 29, 2024 |
| Apple         | MacBookPro9,2               | [3f75dcac27](https://linux-hardware.org/?probe=3f75dcac27) | May 29, 2024 |
| MSI           | Thin GF63 12VE              | [e4303f496e](https://linux-hardware.org/?probe=e4303f496e) | May 29, 2024 |
| System76      | Gazelle                     | [5a9dfce35b](https://linux-hardware.org/?probe=5a9dfce35b) | May 28, 2024 |
| HP            | Laptop 15-bw0xx             | [2204f31974](https://linux-hardware.org/?probe=2204f31974) | May 28, 2024 |
| HP            | Laptop 15-bw0xx             | [ffc4a9774f](https://linux-hardware.org/?probe=ffc4a9774f) | May 28, 2024 |
| Lenovo        | IdeaPad Y530                | [9f15055ea9](https://linux-hardware.org/?probe=9f15055ea9) | May 27, 2024 |
| Acer          | Aspire A515-51G             | [d6150bbab6](https://linux-hardware.org/?probe=d6150bbab6) | May 27, 2024 |
| Acer          | Aspire A715-51G             | [43419cff12](https://linux-hardware.org/?probe=43419cff12) | May 27, 2024 |
| Acer          | Aspire A715-51G             | [3fca192cfc](https://linux-hardware.org/?probe=3fca192cfc) | May 27, 2024 |
| MSI           | GF63 Thin 10SCXR            | [fd86d63cb4](https://linux-hardware.org/?probe=fd86d63cb4) | May 26, 2024 |
| HP            | EliteBook 8440p             | [6fd773583d](https://linux-hardware.org/?probe=6fd773583d) | May 25, 2024 |
| Dell          | Precision M4800             | [17de9adc2b](https://linux-hardware.org/?probe=17de9adc2b) | May 25, 2024 |
| Lenovo        | ThinkPad E490 20N8001BUS    | [26a1242842](https://linux-hardware.org/?probe=26a1242842) | May 24, 2024 |
| HP            | Laptop 15-fd0xxx            | [d316eb38eb](https://linux-hardware.org/?probe=d316eb38eb) | May 24, 2024 |
| MSI           | Cyborg 15 A12VF             | [c2cc910423](https://linux-hardware.org/?probe=c2cc910423) | May 24, 2024 |
| HP            | Dragonfly Pro Laptop PC     | [dd730250f5](https://linux-hardware.org/?probe=dd730250f5) | May 24, 2024 |
| Lenovo        | LOQ 16IRH8 82XW             | [2918fb5b8f](https://linux-hardware.org/?probe=2918fb5b8f) | May 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [78c2a15247](https://linux-hardware.org/?probe=78c2a15247) | May 24, 2024 |
| HUAWEI        | BOHB-WAX9                   | [911fac36a6](https://linux-hardware.org/?probe=911fac36a6) | May 23, 2024 |
| Dell          | Inspiron 1525               | [23100c0c11](https://linux-hardware.org/?probe=23100c0c11) | May 23, 2024 |
| Lenovo        | ThinkPad T420s 41732AU      | [136ea95f4e](https://linux-hardware.org/?probe=136ea95f4e) | May 23, 2024 |
| Lenovo        | ThinkPad T420s 41732AU      | [711d96e5e9](https://linux-hardware.org/?probe=711d96e5e9) | May 23, 2024 |
| Apple         | MacBookPro8,2               | [685d17ccba](https://linux-hardware.org/?probe=685d17ccba) | May 23, 2024 |
| System76      | Gazelle                     | [50af32b27d](https://linux-hardware.org/?probe=50af32b27d) | May 23, 2024 |
| MSI           | GS65 Stealth 9SF            | [f8a0862274](https://linux-hardware.org/?probe=f8a0862274) | May 23, 2024 |
| MSI           | GS65 Stealth 9SF            | [321be6fff1](https://linux-hardware.org/?probe=321be6fff1) | May 23, 2024 |
| Dell          | G15 5520                    | [9a01d7e17e](https://linux-hardware.org/?probe=9a01d7e17e) | May 22, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [1e579e7bc9](https://linux-hardware.org/?probe=1e579e7bc9) | May 22, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [21a9db0e69](https://linux-hardware.org/?probe=21a9db0e69) | May 22, 2024 |
| Lenovo        | ThinkPad X230 2325S3E       | [e07f9a3df9](https://linux-hardware.org/?probe=e07f9a3df9) | May 22, 2024 |
| Positivo      | VJF154                      | [b0d472cf6d](https://linux-hardware.org/?probe=b0d472cf6d) | May 21, 2024 |
| Acer          | Aspire M5-481T              | [fb89268b87](https://linux-hardware.org/?probe=fb89268b87) | May 21, 2024 |
| Dell          | Precision 7720              | [33d11f209f](https://linux-hardware.org/?probe=33d11f209f) | May 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [2d3edc3820](https://linux-hardware.org/?probe=2d3edc3820) | May 20, 2024 |
| Dell          | Latitude E5550              | [4657e1c466](https://linux-hardware.org/?probe=4657e1c466) | May 20, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [3f4de89e2b](https://linux-hardware.org/?probe=3f4de89e2b) | May 19, 2024 |
| Lenovo        | ThinkPad S2 3rd Gen 20L1... | [a4489ca0de](https://linux-hardware.org/?probe=a4489ca0de) | May 19, 2024 |
| Toshiba       | Satellite L50D-A            | [9b860dd740](https://linux-hardware.org/?probe=9b860dd740) | May 19, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [82688ce846](https://linux-hardware.org/?probe=82688ce846) | May 18, 2024 |
| Lenovo        | ThinkPad T460s 20FAS2EW0... | [1473ab54b3](https://linux-hardware.org/?probe=1473ab54b3) | May 18, 2024 |
| Lenovo        | ThinkPad T460s 20FAS2EW0... | [f67b5a2892](https://linux-hardware.org/?probe=f67b5a2892) | May 18, 2024 |
| Acer          | Nitro AN515-58              | [653b100af0](https://linux-hardware.org/?probe=653b100af0) | May 17, 2024 |
| Dell          | XPS 13 7390                 | [a68eeebb7a](https://linux-hardware.org/?probe=a68eeebb7a) | May 17, 2024 |
| Acer          | Predator PH315-52           | [0e1cd73732](https://linux-hardware.org/?probe=0e1cd73732) | May 17, 2024 |
| Dell          | Inspiron 3501               | [292980492d](https://linux-hardware.org/?probe=292980492d) | May 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [2521e5e116](https://linux-hardware.org/?probe=2521e5e116) | May 16, 2024 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [71db51fa59](https://linux-hardware.org/?probe=71db51fa59) | May 15, 2024 |
| HP            | Pavilion Plus Laptop 16-... | [6b2fc8959e](https://linux-hardware.org/?probe=6b2fc8959e) | May 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [7b1593c5ca](https://linux-hardware.org/?probe=7b1593c5ca) | May 15, 2024 |
| Dell          | G15 5520                    | [3897d69dcc](https://linux-hardware.org/?probe=3897d69dcc) | May 14, 2024 |
| Alienware     | m15 R7                      | [9c3fade56c](https://linux-hardware.org/?probe=9c3fade56c) | May 13, 2024 |
| Lenovo        | Legion 5 15IMH05 82AU       | [d6772feb93](https://linux-hardware.org/?probe=d6772feb93) | May 13, 2024 |
| System76      | Oryx Pro                    | [59c2ff7705](https://linux-hardware.org/?probe=59c2ff7705) | May 12, 2024 |
| Casper        | NIRVANA NOTEBOOK            | [c945be80a4](https://linux-hardware.org/?probe=c945be80a4) | May 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [832dafe2b6](https://linux-hardware.org/?probe=832dafe2b6) | May 12, 2024 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | [84350e6996](https://linux-hardware.org/?probe=84350e6996) | May 12, 2024 |
| Dell          | Latitude 7490               | [3c17460acb](https://linux-hardware.org/?probe=3c17460acb) | May 12, 2024 |
| System76      | Gazelle                     | [34b24c6d53](https://linux-hardware.org/?probe=34b24c6d53) | May 11, 2024 |
| System76      | Gazelle                     | [8423d56805](https://linux-hardware.org/?probe=8423d56805) | May 11, 2024 |
| MSI           | Pulse 17 B13VFK             | [3411bfb0da](https://linux-hardware.org/?probe=3411bfb0da) | May 10, 2024 |
| Lenovo        | V720-14 80Y1                | [b7b48be001](https://linux-hardware.org/?probe=b7b48be001) | May 10, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a5031a990b](https://linux-hardware.org/?probe=a5031a990b) | May 10, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [32e0d82f4f](https://linux-hardware.org/?probe=32e0d82f4f) | May 10, 2024 |
| MSI           | GS40 6QE Phantom            | [445dc9e3b3](https://linux-hardware.org/?probe=445dc9e3b3) | May 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [283dc2954f](https://linux-hardware.org/?probe=283dc2954f) | May 10, 2024 |
| Lenovo        | Flex 2-15 20405             | [b5c875cdac](https://linux-hardware.org/?probe=b5c875cdac) | May 10, 2024 |
| MSI           | Pulse 17 B13VFK             | [d7c64d7d11](https://linux-hardware.org/?probe=d7c64d7d11) | May 09, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | [6b95752773](https://linux-hardware.org/?probe=6b95752773) | May 09, 2024 |
| Acer          | Swift SFX14-41G             | [b514ef4494](https://linux-hardware.org/?probe=b514ef4494) | May 09, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | [ad31abdb42](https://linux-hardware.org/?probe=ad31abdb42) | May 09, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | [03e53efb87](https://linux-hardware.org/?probe=03e53efb87) | May 08, 2024 |
| HP            | Laptop 15s-eq2xxx           | [2786d2f8f8](https://linux-hardware.org/?probe=2786d2f8f8) | May 08, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [73ee3d2b74](https://linux-hardware.org/?probe=73ee3d2b74) | May 08, 2024 |
| Lenovo        | ThinkPad T420s 417032U      | [e6839a3d70](https://linux-hardware.org/?probe=e6839a3d70) | May 07, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [9122522638](https://linux-hardware.org/?probe=9122522638) | May 07, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [3064d4fb1f](https://linux-hardware.org/?probe=3064d4fb1f) | May 07, 2024 |
| System76      | Gazelle                     | [fbe88df732](https://linux-hardware.org/?probe=fbe88df732) | May 07, 2024 |
| System76      | Darter Pro                  | [e6da92d97e](https://linux-hardware.org/?probe=e6da92d97e) | May 06, 2024 |
| Dell          | XPS 13 7390                 | [3132f4ff24](https://linux-hardware.org/?probe=3132f4ff24) | May 06, 2024 |
| ASUSTek       | X550CC                      | [db900f1cd1](https://linux-hardware.org/?probe=db900f1cd1) | May 05, 2024 |
| Lenovo        | ThinkPad T420s 41732AU      | [be5eeed803](https://linux-hardware.org/?probe=be5eeed803) | May 05, 2024 |
| ASUSTek       | GL753VD                     | [05c21dbea4](https://linux-hardware.org/?probe=05c21dbea4) | May 05, 2024 |
| Apple         | MacBookAir6,2               | [672e653276](https://linux-hardware.org/?probe=672e653276) | May 05, 2024 |
| System76      | Oryx Pro                    | [6d05743481](https://linux-hardware.org/?probe=6d05743481) | May 05, 2024 |
| Getac         | S410                        | [a05cbbe577](https://linux-hardware.org/?probe=a05cbbe577) | May 04, 2024 |
| Dell          | Inspiron 5520               | [bb83948d6a](https://linux-hardware.org/?probe=bb83948d6a) | May 04, 2024 |
| HP            | Victus by Gaming Laptop ... | [1f42d0fe27](https://linux-hardware.org/?probe=1f42d0fe27) | May 04, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0839696375](https://linux-hardware.org/?probe=0839696375) | May 04, 2024 |
| Dell          | XPS 13 9310                 | [868dd4d0bd](https://linux-hardware.org/?probe=868dd4d0bd) | May 03, 2024 |
| Dell          | XPS 13 9340                 | [4446c73008](https://linux-hardware.org/?probe=4446c73008) | May 03, 2024 |
| Dell          | Latitude E6330              | [02c85088bc](https://linux-hardware.org/?probe=02c85088bc) | May 03, 2024 |
| Alienware     | M14xR1                      | [501de2a1ec](https://linux-hardware.org/?probe=501de2a1ec) | May 02, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c23a3238c0](https://linux-hardware.org/?probe=c23a3238c0) | May 02, 2024 |
| HP            | Pavilion dv7                | [d191e30bf7](https://linux-hardware.org/?probe=d191e30bf7) | May 01, 2024 |
| ASUSTek       | UX430UNR                    | [5712b06d98](https://linux-hardware.org/?probe=5712b06d98) | Apr 30, 2024 |
| ASUSTek       | UX430UNR                    | [a032f50d3f](https://linux-hardware.org/?probe=a032f50d3f) | Apr 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [701927cf4d](https://linux-hardware.org/?probe=701927cf4d) | Apr 30, 2024 |
| Alienware     | M14xR1                      | [dc1461c536](https://linux-hardware.org/?probe=dc1461c536) | Apr 29, 2024 |
| MSI           | Katana 15 B12VGK            | [c8e4cb337e](https://linux-hardware.org/?probe=c8e4cb337e) | Apr 29, 2024 |
| ASUSTek       | X451CA                      | [30d9b5f4ee](https://linux-hardware.org/?probe=30d9b5f4ee) | Apr 28, 2024 |
| Dell          | Inspiron 16 7610            | [2427197c56](https://linux-hardware.org/?probe=2427197c56) | Apr 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [b024eb05d1](https://linux-hardware.org/?probe=b024eb05d1) | Apr 28, 2024 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | [3fbd54c33d](https://linux-hardware.org/?probe=3fbd54c33d) | Apr 27, 2024 |
| Dell          | Precision 5680              | [95bc853549](https://linux-hardware.org/?probe=95bc853549) | Apr 27, 2024 |
| Medion        | Akoya E6227                 | [76bfce53f4](https://linux-hardware.org/?probe=76bfce53f4) | Apr 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [6d6b67129d](https://linux-hardware.org/?probe=6d6b67129d) | Apr 26, 2024 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [ce253ebd01](https://linux-hardware.org/?probe=ce253ebd01) | Apr 26, 2024 |
| HP            | EliteBook 745 G6            | [5354993cb7](https://linux-hardware.org/?probe=5354993cb7) | Apr 25, 2024 |
| HP            | EliteBook 745 G6            | [3b5f41d264](https://linux-hardware.org/?probe=3b5f41d264) | Apr 25, 2024 |
| HP            | ENVY 15                     | [20cb7a828b](https://linux-hardware.org/?probe=20cb7a828b) | Apr 24, 2024 |
| Dell          | Inspiron N4050              | [cbcc357ce6](https://linux-hardware.org/?probe=cbcc357ce6) | Apr 24, 2024 |
| ASRock        | FM2A68M-HD+                 | [74967df09a](https://linux-hardware.org/?probe=74967df09a) | Apr 23, 2024 |
| Apple         | MacBookPro8,2               | [965595373d](https://linux-hardware.org/?probe=965595373d) | Apr 23, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [5453cfa265](https://linux-hardware.org/?probe=5453cfa265) | Apr 23, 2024 |
| Acer          | Aspire A315-59              | [ecc36cef1b](https://linux-hardware.org/?probe=ecc36cef1b) | Apr 23, 2024 |
| MSI           | GE62VR 6RF                  | [68b99dae1a](https://linux-hardware.org/?probe=68b99dae1a) | Apr 23, 2024 |
| Acer          | Aspire A315-59              | [5a88798ad6](https://linux-hardware.org/?probe=5a88798ad6) | Apr 22, 2024 |
| ASUSTek       | ROG Strix SCAR 18 G834JZ... | [28007aea7c](https://linux-hardware.org/?probe=28007aea7c) | Apr 22, 2024 |
| Dell          | XPS 13 9340                 | [5b25704805](https://linux-hardware.org/?probe=5b25704805) | Apr 22, 2024 |
| System76      | Lemur Pro                   | [3b7243efe7](https://linux-hardware.org/?probe=3b7243efe7) | Apr 21, 2024 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [63baa07920](https://linux-hardware.org/?probe=63baa07920) | Apr 21, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ee83ed7c12](https://linux-hardware.org/?probe=ee83ed7c12) | Apr 20, 2024 |
| Apple         | MacBookPro9,2               | [f8fa58a83b](https://linux-hardware.org/?probe=f8fa58a83b) | Apr 19, 2024 |
| Apple         | MacBookPro9,2               | [8dde47a60c](https://linux-hardware.org/?probe=8dde47a60c) | Apr 19, 2024 |
| Google        | Morphius                    | [a8361bc931](https://linux-hardware.org/?probe=a8361bc931) | Apr 19, 2024 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [5bcf08b4b0](https://linux-hardware.org/?probe=5bcf08b4b0) | Apr 19, 2024 |
| HP            | OMEN by Latpop 16-c0100n... | [0ee401b99c](https://linux-hardware.org/?probe=0ee401b99c) | Apr 19, 2024 |
| Toshiba       | Satellite L755D             | [47d623ed44](https://linux-hardware.org/?probe=47d623ed44) | Apr 19, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8f4cd3f89d](https://linux-hardware.org/?probe=8f4cd3f89d) | Apr 19, 2024 |
| Dell          | Precision 5680              | [165f135e49](https://linux-hardware.org/?probe=165f135e49) | Apr 18, 2024 |
| Lenovo        | Slim Pro 9 14IRP8 83BV      | [7b5eee5473](https://linux-hardware.org/?probe=7b5eee5473) | Apr 18, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [bcbc28897f](https://linux-hardware.org/?probe=bcbc28897f) | Apr 17, 2024 |
| Dell          | XPS 15 7590                 | [5b510f5ccd](https://linux-hardware.org/?probe=5b510f5ccd) | Apr 17, 2024 |
| Acer          | Nitro AN515-45              | [224785342d](https://linux-hardware.org/?probe=224785342d) | Apr 17, 2024 |
| ASUSTek       | UX305CA                     | [0793f271ed](https://linux-hardware.org/?probe=0793f271ed) | Apr 17, 2024 |
| HP            | 255 G8 Notebook PC          | [9945f26789](https://linux-hardware.org/?probe=9945f26789) | Apr 17, 2024 |
| Samsung       | 940X3G/930X3G               | [7ae2ace4e3](https://linux-hardware.org/?probe=7ae2ace4e3) | Apr 17, 2024 |
| Samsung       | 940X3G/930X3G               | [ebcb51ed9c](https://linux-hardware.org/?probe=ebcb51ed9c) | Apr 16, 2024 |
| Apple         | MacBookAir4,1               | [fd0c46bab2](https://linux-hardware.org/?probe=fd0c46bab2) | Apr 16, 2024 |
| Dell          | Inspiron 5547               | [088cb90432](https://linux-hardware.org/?probe=088cb90432) | Apr 16, 2024 |
| Acer          | Aspire E1-572G              | [96b786aa6f](https://linux-hardware.org/?probe=96b786aa6f) | Apr 15, 2024 |
| Dell          | Vostro 3400                 | [ddb98658ed](https://linux-hardware.org/?probe=ddb98658ed) | Apr 15, 2024 |
| Acer          | Aspire 5742G                | [91d047cef5](https://linux-hardware.org/?probe=91d047cef5) | Apr 15, 2024 |
| HUAWEI        | BOHB-WAX9                   | [e27137024f](https://linux-hardware.org/?probe=e27137024f) | Apr 15, 2024 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [0e240e7a70](https://linux-hardware.org/?probe=0e240e7a70) | Apr 14, 2024 |
| Acer          | Nitro AN515-51              | [46d9c6bc98](https://linux-hardware.org/?probe=46d9c6bc98) | Apr 14, 2024 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | [b120a1a8eb](https://linux-hardware.org/?probe=b120a1a8eb) | Apr 13, 2024 |
| System76      | Lemur Pro                   | [7c9425e33a](https://linux-hardware.org/?probe=7c9425e33a) | Apr 13, 2024 |
| Dell          | Latitude E5520              | [0f03f7a01f](https://linux-hardware.org/?probe=0f03f7a01f) | Apr 13, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [858512aecf](https://linux-hardware.org/?probe=858512aecf) | Apr 12, 2024 |
| HP            | Victus by Gaming Laptop ... | [7ee4741505](https://linux-hardware.org/?probe=7ee4741505) | Apr 12, 2024 |
| Lenovo        | ThinkPad S5-S540 20B3007... | [696b2e9290](https://linux-hardware.org/?probe=696b2e9290) | Apr 12, 2024 |
| Lenovo        | ThinkPad S5-S540 20B3007... | [7d473643db](https://linux-hardware.org/?probe=7d473643db) | Apr 12, 2024 |
| System76      | Oryx Pro                    | [0204db931b](https://linux-hardware.org/?probe=0204db931b) | Apr 12, 2024 |
| Lenovo        | ThinkPad T470s 20HFCT01W... | [e72d400eb3](https://linux-hardware.org/?probe=e72d400eb3) | Apr 11, 2024 |
| Acer          | Aspire A515-44              | [bcff49116b](https://linux-hardware.org/?probe=bcff49116b) | Apr 11, 2024 |
| Lenovo        | ThinkPad E470 20H10056MZ    | [589fd95069](https://linux-hardware.org/?probe=589fd95069) | Apr 11, 2024 |
| MSI           | Modern 15 A5M               | [df536172a9](https://linux-hardware.org/?probe=df536172a9) | Apr 10, 2024 |
| System76      | Oryx Pro                    | [ea8426e115](https://linux-hardware.org/?probe=ea8426e115) | Apr 10, 2024 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [2b7f101b88](https://linux-hardware.org/?probe=2b7f101b88) | Apr 10, 2024 |
| HP            | EliteBook 8560p             | [e9b9656231](https://linux-hardware.org/?probe=e9b9656231) | Apr 09, 2024 |
| HP            | 250 G4                      | [8f21075772](https://linux-hardware.org/?probe=8f21075772) | Apr 09, 2024 |
| Lenovo        | ThinkPad T470 20HEA0TLUS    | [fac79c8b6b](https://linux-hardware.org/?probe=fac79c8b6b) | Apr 09, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [03de80c7da](https://linux-hardware.org/?probe=03de80c7da) | Apr 08, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [7b9ff3d8a5](https://linux-hardware.org/?probe=7b9ff3d8a5) | Apr 08, 2024 |
| Dell          | Latitude E7240              | [a323cf8e2e](https://linux-hardware.org/?probe=a323cf8e2e) | Apr 08, 2024 |
| Alienware     | m15 R7                      | [5b8340f20c](https://linux-hardware.org/?probe=5b8340f20c) | Apr 08, 2024 |
| Alienware     | m15 R7                      | [2b7f9cd75d](https://linux-hardware.org/?probe=2b7f9cd75d) | Apr 08, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [471a22d2d2](https://linux-hardware.org/?probe=471a22d2d2) | Apr 08, 2024 |
| HP            | 15                          | [6cb916bc6b](https://linux-hardware.org/?probe=6cb916bc6b) | Apr 08, 2024 |
| MSI           | Titan GT77HX 13VI           | [81cf9688bd](https://linux-hardware.org/?probe=81cf9688bd) | Apr 08, 2024 |
| HP            | 15                          | [c3dd3707a8](https://linux-hardware.org/?probe=c3dd3707a8) | Apr 08, 2024 |
| Dell          | Latitude 5401               | [50c9a92ed4](https://linux-hardware.org/?probe=50c9a92ed4) | Apr 07, 2024 |
| Acer          | Swift SF314-71              | [071a57efd2](https://linux-hardware.org/?probe=071a57efd2) | Apr 07, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [25ee9e6b9c](https://linux-hardware.org/?probe=25ee9e6b9c) | Apr 07, 2024 |
| HP            | 255 G8 Notebook PC          | [85dd650b73](https://linux-hardware.org/?probe=85dd650b73) | Apr 07, 2024 |
| Acer          | Nitro AN515-52              | [b36f589241](https://linux-hardware.org/?probe=b36f589241) | Apr 06, 2024 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [75363d665b](https://linux-hardware.org/?probe=75363d665b) | Apr 06, 2024 |
| HP            | OMEN Laptop 15-en1xxx       | [3242172c38](https://linux-hardware.org/?probe=3242172c38) | Apr 06, 2024 |
| HP            | Stream 11 Pro G5            | [60dbf47721](https://linux-hardware.org/?probe=60dbf47721) | Apr 06, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [20ceba9415](https://linux-hardware.org/?probe=20ceba9415) | Apr 06, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [cf5333f4e5](https://linux-hardware.org/?probe=cf5333f4e5) | Apr 06, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [9afed2e851](https://linux-hardware.org/?probe=9afed2e851) | Apr 06, 2024 |
| HP            | EliteBook 8730w             | [342f90f8c1](https://linux-hardware.org/?probe=342f90f8c1) | Apr 05, 2024 |
| HP            | EliteBook 8730w             | [b4c4b71cdb](https://linux-hardware.org/?probe=b4c4b71cdb) | Apr 05, 2024 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | [bf584291d2](https://linux-hardware.org/?probe=bf584291d2) | Apr 04, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 6.9.3-76060903-generic              | 546       | 15.25%  |
| 6.2.6-76060206-generic              | 477       | 13.32%  |
| 5.19.0-76051900-generic             | 276       | 7.71%   |
| 6.0.12-76060006-generic             | 272       | 7.6%    |
| 6.8.0-76060800daily20240311-generic | 256       | 7.15%   |
| 5.17.5-76051705-generic             | 235       | 6.56%   |
| 6.6.10-76060610-generic             | 191       | 5.33%   |
| 6.4.6-76060406-generic              | 188       | 5.25%   |
| 6.0.6-76060006-generic              | 165       | 4.61%   |
| 6.5.6-76060506-generic              | 163       | 4.55%   |
| 6.6.6-76060606-generic              | 128       | 3.57%   |
| 5.18.10-76051810-generic            | 119       | 3.32%   |
| 5.17.15-76051715-generic            | 105       | 2.93%   |
| 6.2.0-76060200-generic              | 79        | 2.21%   |
| 5.16.19-76051619-generic            | 72        | 2.01%   |
| 6.5.4-76060504-generic              | 66        | 1.84%   |
| 6.0.2-76060002-generic              | 58        | 1.62%   |
| 6.1.11-76060111-generic             | 54        | 1.51%   |
| 6.0.3-76060003-generic              | 24        | 0.67%   |
| 5.19.16-76051916-generic            | 21        | 0.59%   |
| 6.5.7-060507-generic                | 3         | 0.08%   |
| 6.7.10-x64v3-xanmod1                | 2         | 0.06%   |
| 6.4.0-060400-generic                | 2         | 0.06%   |
| 6.3.7-060307-generic                | 2         | 0.06%   |
| 6.2.11-060211-generic               | 2         | 0.06%   |
| 6.1.0-1006-oem                      | 2         | 0.06%   |
| 5.17.5-051705-generic               | 2         | 0.06%   |
| 5.16.15-76051615-generic            | 2         | 0.06%   |
| 6.9.1-060901-generic                | 1         | 0.03%   |
| 6.8.9-x64v4-xanmod1                 | 1         | 0.03%   |
| 6.8.0-060800rc1-generic             | 1         | 0.03%   |
| 6.7.5-060705-generic                | 1         | 0.03%   |
| 6.5.8-x64v1-xanmod1                 | 1         | 0.03%   |
| 6.5.5-x64v3-xanmod1                 | 1         | 0.03%   |
| 6.5.12-x64v3-xanmod1                | 1         | 0.03%   |
| 6.5.10-x64v2-xanmod1                | 1         | 0.03%   |
| 6.5.0-rc2                           | 1         | 0.03%   |
| 6.5.0-41-generic                    | 1         | 0.03%   |
| 6.4.5-x64v2-xanmod1                 | 1         | 0.03%   |
| 6.4.3-060403-generic                | 1         | 0.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.9.3   | 546       | 15.26%  |
| 6.2.6   | 478       | 13.36%  |
| 5.19.0  | 279       | 7.8%    |
| 6.0.12  | 272       | 7.6%    |
| 6.8.0   | 257       | 7.18%   |
| 5.17.5  | 238       | 6.65%   |
| 6.6.10  | 191       | 5.34%   |
| 6.4.6   | 188       | 5.25%   |
| 6.0.6   | 165       | 4.61%   |
| 6.5.6   | 163       | 4.56%   |
| 6.6.6   | 128       | 3.58%   |
| 5.18.10 | 119       | 3.33%   |
| 5.17.15 | 105       | 2.93%   |
| 6.2.0   | 79        | 2.21%   |
| 5.16.19 | 72        | 2.01%   |
| 6.5.4   | 66        | 1.84%   |
| 6.0.2   | 59        | 1.65%   |
| 6.1.11  | 54        | 1.51%   |
| 6.0.3   | 24        | 0.67%   |
| 5.19.16 | 21        | 0.59%   |
| 6.5.7   | 3         | 0.08%   |
| 5.15.0  | 3         | 0.08%   |
| 6.7.10  | 2         | 0.06%   |
| 6.5.0   | 2         | 0.06%   |
| 6.4.0   | 2         | 0.06%   |
| 6.3.9   | 2         | 0.06%   |
| 6.3.7   | 2         | 0.06%   |
| 6.2.11  | 2         | 0.06%   |
| 6.11.0  | 2         | 0.06%   |
| 6.10.6  | 2         | 0.06%   |
| 6.1.9   | 2         | 0.06%   |
| 6.1.0   | 2         | 0.06%   |
| 6.0.9   | 2         | 0.06%   |
| 6.0.0   | 2         | 0.06%   |
| 5.17.0  | 2         | 0.06%   |
| 5.16.15 | 2         | 0.06%   |
| 6.9.1   | 1         | 0.03%   |
| 6.8.9   | 1         | 0.03%   |
| 6.7.5   | 1         | 0.03%   |
| 6.5.8   | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 557       | 15.77%  |
| 6.9     | 547       | 15.49%  |
| 6.0     | 505       | 14.3%   |
| 5.17    | 342       | 9.68%   |
| 6.6     | 312       | 8.83%   |
| 5.19    | 302       | 8.55%   |
| 6.8     | 258       | 7.3%    |
| 6.5     | 235       | 6.65%   |
| 6.4     | 192       | 5.44%   |
| 5.18    | 123       | 3.48%   |
| 5.16    | 75        | 2.12%   |
| 6.1     | 61        | 1.73%   |
| 6.3     | 8         | 0.23%   |
| 5.15    | 5         | 0.14%   |
| 6.7     | 3         | 0.08%   |
| 6.10    | 3         | 0.08%   |
| 6.12    | 2         | 0.06%   |
| 6.11    | 2         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3209      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 3124      | 97.02%  |
| KDE5            | 31        | 0.96%   |
| Unknown         | 22        | 0.68%   |
| X-Cinnamon      | 10        | 0.31%   |
| COSMIC          | 10        | 0.31%   |
| Unity           | 5         | 0.16%   |
| GNOME Flashback | 5         | 0.16%   |
| XFCE            | 3         | 0.09%   |
| Cinnamon        | 3         | 0.09%   |
| MATE            | 2         | 0.06%   |
| LXQt            | 2         | 0.06%   |
| awesome         | 2         | 0.06%   |
| i3              | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3038      | 94.03%  |
| Wayland | 172       | 5.32%   |
| Unknown | 17        | 0.53%   |
| Tty     | 4         | 0.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 2247      | 69.2%   |
| GDM3           | 984       | 30.3%   |
| GDM            | 7         | 0.22%   |
| SDDM           | 5         | 0.15%   |
| LightDM        | 2         | 0.06%   |
| COSMIC-GREETER | 2         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1874      | 58%     |
| en_GB   | 200       | 6.19%   |
| pt_BR   | 179       | 5.54%   |
| de_DE   | 139       | 4.3%    |
| C       | 110       | 3.4%    |
| en_AU   | 85        | 2.63%   |
| fr_FR   | 68        | 2.1%    |
| it_IT   | 67        | 2.07%   |
| en_CA   | 54        | 1.67%   |
| es_ES   | 47        | 1.45%   |
| ru_RU   | 39        | 1.21%   |
| pl_PL   | 34        | 1.05%   |
| pt_PT   | 27        | 0.84%   |
| Unknown | 21        | 0.65%   |
| en_IN   | 19        | 0.59%   |
| tr_TR   | 18        | 0.56%   |
| sv_SE   | 18        | 0.56%   |
| nb_NO   | 17        | 0.53%   |
| en_NZ   | 13        | 0.4%    |
| fi_FI   | 12        | 0.37%   |
| es_MX   | 12        | 0.37%   |
| en_IE   | 12        | 0.37%   |
| nl_NL   | 11        | 0.34%   |
| hu_HU   | 10        | 0.31%   |
| es_CL   | 10        | 0.31%   |
| es_AR   | 10        | 0.31%   |
| en_DK   | 10        | 0.31%   |
| cs_CZ   | 10        | 0.31%   |
| en_ZA   | 9         | 0.28%   |
| de_CH   | 9         | 0.28%   |
| da_DK   | 7         | 0.22%   |
| fr_CH   | 6         | 0.19%   |
| fr_CA   | 6         | 0.19%   |
| es_CO   | 6         | 0.19%   |
| de_AT   | 6         | 0.19%   |
| zh_CN   | 4         | 0.12%   |
| fr_BE   | 4         | 0.12%   |
| en_PH   | 4         | 0.12%   |
| zh_TW   | 3         | 0.09%   |
| en_IL   | 3         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 2291      | 70.64%  |
| EFI  | 952       | 29.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 3055      | 94.88%  |
| Btrfs   | 102       | 3.17%   |
| Overlay | 54        | 1.68%   |
| Xfs     | 8         | 0.25%   |
| Zfs     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2224      | 68.54%  |
| GPT     | 958       | 29.52%  |
| MBR     | 63        | 1.94%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3119      | 96.92%  |
| Yes       | 99        | 3.08%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2881      | 89.25%  |
| Yes       | 347       | 10.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 689       | 21.47%  |
| Dell                   | 498       | 15.52%  |
| Hewlett-Packard        | 447       | 13.93%  |
| ASUSTek Computer       | 408       | 12.71%  |
| Acer                   | 232       | 7.23%   |
| Apple                  | 219       | 6.82%   |
| MSI                    | 120       | 3.74%   |
| System76               | 114       | 3.55%   |
| HUAWEI                 | 52        | 1.62%   |
| Toshiba                | 50        | 1.56%   |
| Samsung Electronics    | 44        | 1.37%   |
| Notebook               | 27        | 0.84%   |
| Google                 | 27        | 0.84%   |
| Alienware              | 26        | 0.81%   |
| Fujitsu                | 15        | 0.47%   |
| Sony                   | 14        | 0.44%   |
| Framework              | 14        | 0.44%   |
| Gigabyte Technology    | 13        | 0.41%   |
| Unknown                | 13        | 0.41%   |
| Razer                  | 12        | 0.37%   |
| Positivo               | 10        | 0.31%   |
| PC Specialist          | 10        | 0.31%   |
| GPU Company            | 10        | 0.31%   |
| Timi                   | 9         | 0.28%   |
| HONOR                  | 8         | 0.25%   |
| Medion                 | 7         | 0.22%   |
| LG Electronics         | 7         | 0.22%   |
| GPD                    | 6         | 0.19%   |
| Avell High Performance | 6         | 0.19%   |
| TUXEDO                 | 4         | 0.12%   |
| Schenker               | 4         | 0.12%   |
| Clevo                  | 4         | 0.12%   |
| ASRock                 | 4         | 0.12%   |
| Panasonic              | 3         | 0.09%   |
| Valve                  | 2         | 0.06%   |
| Teclast                | 2         | 0.06%   |
| SLIMBOOK               | 2         | 0.06%   |
| realme                 | 2         | 0.06%   |
| Pegatron               | 2         | 0.06%   |
| Packard Bell           | 2         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| System76 Oryx Pro                   | 28        | 0.87%   |
| System76 Lemur Pro                  | 21        | 0.65%   |
| Apple MacBookPro9,2                 | 21        | 0.65%   |
| Apple MacBookAir7,2                 | 21        | 0.65%   |
| Unknown                             | 21        | 0.65%   |
| System76 Gazelle                    | 18        | 0.56%   |
| Apple MacBookPro8,1                 | 16        | 0.5%    |
| Apple MacBookPro12,1                | 16        | 0.5%    |
| Apple MacBookAir6,2                 | 15        | 0.47%   |
| HP Dev One Notebook PC              | 13        | 0.41%   |
| Apple MacBookPro11,3                | 13        | 0.41%   |
| System76 Pangolin                   | 12        | 0.37%   |
| System76 Darter Pro                 | 12        | 0.37%   |
| Apple MacBookPro11,1                | 12        | 0.37%   |
| System76 Galago Pro                 | 10        | 0.31%   |
| Lenovo Legion 5 15ACH6H 82JU        | 10        | 0.31%   |
| HP Notebook                         | 10        | 0.31%   |
| Dell XPS 15 9570                    | 9         | 0.28%   |
| Dell XPS 15 7590                    | 9         | 0.28%   |
| Apple MacBookPro7,1                 | 9         | 0.28%   |
| Acer Nitro AN515-58                 | 9         | 0.28%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2 | 8         | 0.25%   |
| Lenovo IdeaPad 3 15ALC6 82MF        | 8         | 0.25%   |
| Dell XPS 15 9520                    | 8         | 0.25%   |
| Dell Inspiron 15 7000 Gaming        | 8         | 0.25%   |
| Apple MacBookPro8,2                 | 8         | 0.25%   |
| Lenovo IdeaPad S145-15API 81V7      | 7         | 0.22%   |
| Lenovo IdeaPad Gaming 3 15IAH7 82S9 | 7         | 0.22%   |
| HP Pavilion 15                      | 7         | 0.22%   |
| Dell XPS 13 9370                    | 7         | 0.22%   |
| Dell XPS 13 9310                    | 7         | 0.22%   |
| Dell XPS 13 7390                    | 7         | 0.22%   |
| Apple MacBookPro10,1                | 7         | 0.22%   |
| Lenovo Y50-70 20378                 | 6         | 0.19%   |
| Lenovo IdeaPad 5 Pro 16ARH7 82SN    | 6         | 0.19%   |
| HUAWEI BOHB-WAX9                    | 6         | 0.19%   |
| HP Victus by Laptop 16-e0xxx        | 6         | 0.19%   |
| HP Pavilion g6                      | 6         | 0.19%   |
| HP Pavilion dv7                     | 6         | 0.19%   |
| HP Pavilion dv6                     | 6         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 318       | 9.91%   |
| Lenovo IdeaPad     | 178       | 5.55%   |
| Acer Aspire        | 140       | 4.36%   |
| Dell Latitude      | 137       | 4.27%   |
| Dell Inspiron      | 132       | 4.11%   |
| Dell XPS           | 95        | 2.96%   |
| ASUS VivoBook      | 92        | 2.87%   |
| HP Pavilion        | 83        | 2.59%   |
| Lenovo Legion      | 79        | 2.46%   |
| ASUS ROG           | 78        | 2.43%   |
| HP EliteBook       | 77        | 2.4%    |
| HP Laptop          | 69        | 2.15%   |
| ASUS ASUS          | 60        | 1.87%   |
| Dell Precision     | 57        | 1.78%   |
| HP ProBook         | 50        | 1.56%   |
| Toshiba Satellite  | 42        | 1.31%   |
| Acer Nitro         | 38        | 1.18%   |
| Apple MacBookPro11 | 36        | 1.12%   |
| Dell Vostro        | 32        | 1%      |
| HP ZBook           | 30        | 0.93%   |
| Acer Swift         | 29        | 0.9%    |
| System76 Oryx      | 28        | 0.87%   |
| ASUS Zenbook       | 28        | 0.87%   |
| HP OMEN            | 26        | 0.81%   |
| Apple MacBookPro8  | 25        | 0.78%   |
| Apple MacBookPro9  | 23        | 0.72%   |
| System76 Lemur     | 22        | 0.69%   |
| Lenovo ThinkBook   | 21        | 0.65%   |
| Apple MacBookAir7  | 21        | 0.65%   |
| Unknown            | 21        | 0.65%   |
| Lenovo Yoga        | 20        | 0.62%   |
| System76 Gazelle   | 18        | 0.56%   |
| HP Victus          | 18        | 0.56%   |
| Dell G15           | 16        | 0.5%    |
| Apple MacBookPro12 | 16        | 0.5%    |
| Apple MacBookAir6  | 16        | 0.5%    |
| HP ENVY            | 15        | 0.47%   |
| Framework Laptop   | 14        | 0.44%   |
| Apple MacBookPro5  | 14        | 0.44%   |
| HP Dev             | 13        | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 464       | 14.46%  |
| 2022    | 340       | 10.6%   |
| 2020    | 329       | 10.25%  |
| 2019    | 262       | 8.16%   |
| 2018    | 237       | 7.39%   |
| 2023    | 202       | 6.29%   |
| 2012    | 195       | 6.08%   |
| 2013    | 188       | 5.86%   |
| 2017    | 159       | 4.95%   |
| 2011    | 151       | 4.71%   |
| 2014    | 145       | 4.52%   |
| 2016    | 140       | 4.36%   |
| 2015    | 137       | 4.27%   |
| 2010    | 73        | 2.27%   |
| 2024    | 56        | 1.75%   |
| 2009    | 52        | 1.62%   |
| 2008    | 47        | 1.46%   |
| 2007    | 29        | 0.9%    |
| 2006    | 2         | 0.06%   |
| Unknown | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3209      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3209      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3096      | 96.48%  |
| Yes  | 113       | 3.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 858       | 26.51%  |
| 16.01-24.0  | 791       | 24.44%  |
| 8.01-16.0   | 633       | 19.56%  |
| 32.01-64.0  | 412       | 12.73%  |
| 3.01-4.0    | 337       | 10.41%  |
| 64.01-256.0 | 101       | 3.12%   |
| 24.01-32.0  | 77        | 2.38%   |
| 1.01-2.0    | 15        | 0.46%   |
| 2.01-3.0    | 13        | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 1274      | 36.69%  |
| 2.01-3.0   | 812       | 23.39%  |
| 3.01-4.0   | 745       | 21.46%  |
| 8.01-16.0  | 353       | 10.17%  |
| 1.01-2.0   | 224       | 6.45%   |
| 16.01-24.0 | 51        | 1.47%   |
| 24.01-32.0 | 10        | 0.29%   |
| 0.51-1.0   | 2         | 0.06%   |
| 32.01-64.0 | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2322      | 71.4%   |
| 2      | 801       | 24.63%  |
| 3      | 101       | 3.11%   |
| 0      | 14        | 0.43%   |
| 4      | 12        | 0.37%   |
| 7      | 1         | 0.03%   |
| 5      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2553      | 79.46%  |
| Yes       | 660       | 20.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2440      | 75.64%  |
| No        | 786       | 24.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3131      | 97.54%  |
| No        | 79        | 2.46%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2804      | 86.84%  |
| No        | 425       | 13.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 836       | 25.91%  |
| Brazil       | 255       | 7.9%    |
| Germany      | 207       | 6.42%   |
| UK           | 134       | 4.15%   |
| Canada       | 127       | 3.94%   |
| Italy        | 126       | 3.91%   |
| India        | 126       | 3.91%   |
| Australia    | 108       | 3.35%   |
| France       | 94        | 2.91%   |
| Russia       | 71        | 2.2%    |
| Spain        | 63        | 1.95%   |
| Poland       | 60        | 1.86%   |
| Netherlands  | 60        | 1.86%   |
| Sweden       | 48        | 1.49%   |
| Portugal     | 40        | 1.24%   |
| Norway       | 38        | 1.18%   |
| Mexico       | 38        | 1.18%   |
| Turkey       | 37        | 1.15%   |
| Czechia      | 35        | 1.08%   |
| Indonesia    | 34        | 1.05%   |
| Switzerland  | 30        | 0.93%   |
| Finland      | 29        | 0.9%    |
| Philippines  | 28        | 0.87%   |
| New Zealand  | 26        | 0.81%   |
| Denmark      | 26        | 0.81%   |
| Hungary      | 24        | 0.74%   |
| Romania      | 23        | 0.71%   |
| Austria      | 22        | 0.68%   |
| Argentina    | 22        | 0.68%   |
| Chile        | 21        | 0.65%   |
| Belgium      | 20        | 0.62%   |
| Serbia       | 19        | 0.59%   |
| Greece       | 19        | 0.59%   |
| Bulgaria     | 18        | 0.56%   |
| South Africa | 17        | 0.53%   |
| Ireland      | 17        | 0.53%   |
| Thailand     | 14        | 0.43%   |
| Colombia     | 13        | 0.4%    |
| Vietnam      | 12        | 0.37%   |
| Egypt        | 11        | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Melbourne      | 37        | 1.09%   |
| Sao Paulo      | 29        | 0.86%   |
| Milan          | 24        | 0.71%   |
| Helsinki       | 24        | 0.71%   |
| Warsaw         | 23        | 0.68%   |
| Sydney         | 23        | 0.68%   |
| Brisbane       | 23        | 0.68%   |
| Berlin         | 21        | 0.62%   |
| Bengaluru      | 19        | 0.56%   |
| Istanbul       | 18        | 0.53%   |
| Oslo           | 17        | 0.5%    |
| New York       | 17        | 0.5%    |
| Moscow         | 17        | 0.5%    |
| Chicago        | 17        | 0.5%    |
| Prague         | 15        | 0.44%   |
| Rome           | 14        | 0.41%   |
| Rio de Janeiro | 14        | 0.41%   |
| Paris          | 14        | 0.41%   |
| Madrid         | 14        | 0.41%   |
| Denver         | 14        | 0.41%   |
| Auckland       | 14        | 0.41%   |
| Vienna         | 13        | 0.38%   |
| Delhi          | 13        | 0.38%   |
| Budapest       | 13        | 0.38%   |
| Sofia          | 12        | 0.35%   |
| Lisbon         | 12        | 0.35%   |
| Toronto        | 11        | 0.33%   |
| St Petersburg  | 11        | 0.33%   |
| Seattle        | 11        | 0.33%   |
| Los Angeles    | 11        | 0.33%   |
| Dublin         | 11        | 0.33%   |
| Belgrade       | 11        | 0.33%   |
| Stockholm      | 10        | 0.3%    |
| Mumbai         | 10        | 0.3%    |
| Minneapolis    | 10        | 0.3%    |
| Jakarta        | 10        | 0.3%    |
| Dallas         | 10        | 0.3%    |
| Calgary        | 10        | 0.3%    |
| Bucharest      | 10        | 0.3%    |
| Amsterdam      | 10        | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 794       | 1053   | 19.4%   |
| Sandisk                        | 360       | 462    | 8.8%    |
| WDC                            | 332       | 384    | 8.11%   |
| Seagate                        | 243       | 284    | 5.94%   |
| SK hynix                       | 242       | 281    | 5.91%   |
| Kingston                       | 198       | 245    | 4.84%   |
| Toshiba                        | 197       | 231    | 4.81%   |
| Micron Technology              | 189       | 219    | 4.62%   |
| Intel                          | 148       | 171    | 3.62%   |
| Unknown                        | 143       | 168    | 3.49%   |
| Crucial                        | 129       | 152    | 3.15%   |
| Apple                          | 122       | 141    | 2.98%   |
| KIOXIA                         | 80        | 91     | 1.96%   |
| HGST                           | 79        | 87     | 1.93%   |
| Micron/Crucial Technology      | 52        | 64     | 1.27%   |
| Hitachi                        | 45        | 52     | 1.1%    |
| A-DATA Technology              | 41        | 50     | 1%      |
| Phison                         | 40        | 49     | 0.98%   |
| Kingston Technology Company    | 40        | 41     | 0.98%   |
| Silicon Motion                 | 37        | 43     | 0.9%    |
| China                          | 37        | 43     | 0.9%    |
| Phison Electronics             | 36        | 45     | 0.88%   |
| PNY                            | 29        | 37     | 0.71%   |
| LITEON                         | 21        | 26     | 0.51%   |
| Unknown                        | 21        | 25     | 0.51%   |
| ADATA Technology               | 17        | 18     | 0.42%   |
| Transcend                      | 16        | 19     | 0.39%   |
| SPCC                           | 16        | 17     | 0.39%   |
| ASMT                           | 16        | 16     | 0.39%   |
| Team                           | 15        | 16     | 0.37%   |
| LITEONIT                       | 14        | 26     | 0.34%   |
| KingSpec                       | 14        | 15     | 0.34%   |
| Intenso                        | 13        | 20     | 0.32%   |
| Netac                          | 12        | 12     | 0.29%   |
| Union Memory (Shenzhen)        | 11        | 14     | 0.27%   |
| MAXIO Technology (Hangzhou)    | 11        | 12     | 0.27%   |
| Solid State Storage Technology | 10        | 10     | 0.24%   |
| Patriot                        | 10        | 13     | 0.24%   |
| Lexar                          | 10        | 13     | 0.24%   |
| JMicron Technology             | 10        | 12     | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 106       | 2.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 65        | 1.52%   |
| Kingston SA400S37240G 240GB SSD                       | 45        | 1.06%   |
| Seagate ST1000LM035-1RK172 1TB                        | 40        | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 33        | 0.77%   |
| SanDisk NVMe SSD Drive 1TB                            | 31        | 0.73%   |
| HGST HTS721010A9E630 1TB                              | 31        | 0.73%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                  | 30        | 0.7%    |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 30        | 0.7%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB      | 26        | 0.61%   |
| Intel SSD 660P Series 1024GB                          | 25        | 0.59%   |
| Unknown MMC Card  32GB                                | 24        | 0.56%   |
| Toshiba MQ04ABF100 1TB                                | 24        | 0.56%   |
| Kingston SA400S37480G 480GB SSD                       | 24        | 0.56%   |
| Intel SSDPEKNU512GZ 512GB                             | 24        | 0.56%   |
| Apple SSD SM0128G 121GB                               | 24        | 0.56%   |
| Toshiba MQ01ABD100 1TB                                | 23        | 0.54%   |
| Unknown MMC Card  64GB                                | 22        | 0.52%   |
| Unknown                                               | 21        | 0.49%   |
| Unknown MMC Card  128GB                               | 20        | 0.47%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 19        | 0.45%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 19        | 0.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 19        | 0.45%   |
| SanDisk NVMe SSD Drive 512GB                          | 18        | 0.42%   |
| Crucial CT240BX500SSD1 240GB                          | 18        | 0.42%   |
| Samsung SSD 860 EVO 500GB                             | 17        | 0.4%    |
| Samsung NVMe SSD Drive 512GB                          | 17        | 0.4%    |
| Samsung SSD 850 EVO 500GB                             | 16        | 0.38%   |
| Crucial CT500MX500SSD1 500GB                          | 16        | 0.38%   |
| WDC WD10SPZX-24Z10 1TB                                | 15        | 0.35%   |
| Samsung SSD 980 1TB                                   | 15        | 0.35%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 15        | 0.35%   |
| Intel SSD Pro 7600p/760p/E 6100p Series 512GB         | 15        | 0.35%   |
| Crucial CT1000MX500SSD1 1TB                           | 15        | 0.35%   |
| ASMT USB 3.0 TOSATA 120GB                             | 15        | 0.35%   |
| SK hynix NVMe SSD Drive 512GB                         | 14        | 0.33%   |
| Seagate ST1000LM049-2GH172 1TB                        | 14        | 0.33%   |
| Samsung SSD 870 EVO 500GB                             | 14        | 0.33%   |
| Phison E12 NVMe Controller 480GB                      | 14        | 0.33%   |
| Micron 2210_MTFDHBA512QFD 512GB                       | 14        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 235       | 275    | 33.29%  |
| WDC                 | 175       | 204    | 24.79%  |
| Toshiba             | 116       | 134    | 16.43%  |
| HGST                | 79        | 87     | 11.19%  |
| Hitachi             | 45        | 52     | 6.37%   |
| Samsung Electronics | 11        | 11     | 1.56%   |
| Apple               | 9         | 10     | 1.27%   |
| Unknown             | 8         | 8      | 1.13%   |
| SABRENT             | 5         | 6      | 0.71%   |
| JMicron Technology  | 5         | 6      | 0.71%   |
| Fujitsu             | 5         | 5      | 0.71%   |
| Intenso             | 2         | 7      | 0.28%   |
| External            | 2         | 2      | 0.28%   |
| TO Exter            | 1         | 1      | 0.14%   |
| StoreJet            | 1         | 1      | 0.14%   |
| Min Yi U            | 1         | 1      | 0.14%   |
| MaxDigital          | 1         | 1      | 0.14%   |
| KESU                | 1         | 1      | 0.14%   |
| HGST HDN            | 1         | 1      | 0.14%   |
| ASMT                | 1         | 1      | 0.14%   |
| ASMedia             | 1         | 1      | 0.14%   |
| Asm                 | 1         | 1      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 231       | 289    | 19.68%  |
| Kingston            | 142       | 167    | 12.1%   |
| SanDisk             | 111       | 143    | 9.45%   |
| Crucial             | 110       | 131    | 9.37%   |
| Apple               | 98        | 114    | 8.35%   |
| WDC                 | 70        | 83     | 5.96%   |
| China               | 37        | 43     | 3.15%   |
| Micron Technology   | 28        | 32     | 2.39%   |
| SK hynix            | 27        | 28     | 2.3%    |
| PNY                 | 26        | 33     | 2.21%   |
| Toshiba             | 22        | 22     | 1.87%   |
| Intel               | 20        | 22     | 1.7%    |
| LITEON              | 19        | 24     | 1.62%   |
| A-DATA Technology   | 19        | 23     | 1.62%   |
| Transcend           | 14        | 17     | 1.19%   |
| LITEONIT            | 14        | 26     | 1.19%   |
| KingSpec            | 14        | 15     | 1.19%   |
| SPCC                | 13        | 14     | 1.11%   |
| Netac               | 11        | 11     | 0.94%   |
| Patriot             | 8         | 10     | 0.68%   |
| Intenso             | 8         | 9      | 0.68%   |
| Team                | 6         | 7      | 0.51%   |
| Apacer              | 6         | 10     | 0.51%   |
| Verbatim            | 5         | 6      | 0.43%   |
| Lexar               | 5         | 7      | 0.43%   |
| Hewlett-Packard     | 5         | 5      | 0.43%   |
| KIOXIA-EXCERIA      | 4         | 4      | 0.34%   |
| Unknown             | 4         | 4      | 0.34%   |
| MyDigitalSSD        | 3         | 3      | 0.26%   |
| KingDian            | 3         | 3      | 0.26%   |
| Fanxiang            | 3         | 3      | 0.26%   |
| Dogfish             | 3         | 4      | 0.26%   |
| Corsair             | 3         | 3      | 0.26%   |
| Wibtek              | 2         | 4      | 0.17%   |
| Teclast             | 2         | 3      | 0.17%   |
| Ramaxel Technology  | 2         | 2      | 0.17%   |
| PHD 3.0             | 2         | 2      | 0.17%   |
| OWC                 | 2         | 2      | 0.17%   |
| MidasForce          | 2         | 2      | 0.17%   |
| Inland              | 2         | 2      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1802      | 2488   | 47.82%  |
| SSD     | 1085      | 1405   | 28.8%   |
| HDD     | 680       | 816    | 18.05%  |
| MMC     | 127       | 149    | 3.37%   |
| Unknown | 74        | 91     | 1.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1800      | 2481   | 49.37%  |
| SATA | 1559      | 2119   | 42.76%  |
| SAS  | 160       | 200    | 4.39%   |
| MMC  | 127       | 149    | 3.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1113      | 1420   | 63.1%   |
| 0.51-1.0   | 558       | 680    | 31.63%  |
| 1.01-2.0   | 71        | 91     | 4.02%   |
| 3.01-4.0   | 11        | 13     | 0.62%   |
| 4.01-10.0  | 6         | 12     | 0.34%   |
| 10.01-20.0 | 3         | 3      | 0.17%   |
| 2.01-3.0   | 2         | 2      | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1030      | 31.16%  |
| 251-500        | 983       | 29.73%  |
| 501-1000       | 681       | 20.6%   |
| 1001-2000      | 240       | 7.26%   |
| 51-100         | 112       | 3.39%   |
| 1-20           | 66        | 2%      |
| More than 3000 | 63        | 1.91%   |
| 2001-3000      | 60        | 1.81%   |
| 21-50          | 50        | 1.51%   |
| Unknown        | 21        | 0.64%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1052      | 30.43%  |
| 21-50          | 858       | 24.82%  |
| 101-250        | 539       | 15.59%  |
| 51-100         | 461       | 13.34%  |
| 251-500        | 295       | 8.53%   |
| 501-1000       | 157       | 4.54%   |
| 1001-2000      | 47        | 1.36%   |
| Unknown        | 21        | 0.61%   |
| More than 3000 | 17        | 0.49%   |
| 2001-3000      | 10        | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Notebooks | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS001TDE9X073N 1TB          | 4         | 4      | 5.19%   |
| SK hynix PC711 HFS512GDE9X073N 512GB        | 2         | 2      | 2.6%    |
| Seagate ST500LT012-9WS142 500GB             | 2         | 2      | 2.6%    |
| Seagate ST1000LX015-1U7172 1TB              | 2         | 2      | 2.6%    |
| Seagate ST1000LM035-1RK172 1TB              | 2         | 2      | 2.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB          | 2         | 2      | 2.6%    |
| HGST HTS725050A7E630 500GB                  | 2         | 3      | 2.6%    |
| HGST HTS545050A7E680 500GB                  | 2         | 2      | 2.6%    |
| HGST HTS541010A9E680 1TB                    | 2         | 2      | 2.6%    |
| XPG GAMMIX S41 256GB                        | 1         | 1      | 1.3%    |
| WHALEKOM SSD 512GB                          | 1         | 1      | 1.3%    |
| WDC WDS480G2G0B-00EPW0 480GB SSD            | 1         | 2      | 1.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 1         | 1      | 1.3%    |
| WDC WDS200T2B0B-00YS70 2TB SSD              | 1         | 1      | 1.3%    |
| WDC WDS100T2B0B-00YS70 1TB SSD              | 1         | 1      | 1.3%    |
| WDC WD5000LPVX-75V0TT0 500GB                | 1         | 1      | 1.3%    |
| WDC WD5000LPVX-22V0TT0 500GB                | 1         | 1      | 1.3%    |
| WDC WD3200BEKX-75B7WT0 320GB                | 1         | 1      | 1.3%    |
| WDC WD3200BEKT-60PVMT0 320GB                | 1         | 1      | 1.3%    |
| WDC WD10SPZX-24Z10T0 1TB                    | 1         | 1      | 1.3%    |
| WDC WD10SPZX-22Z10T0 1TB                    | 1         | 1      | 1.3%    |
| WDC WD10SPZX-16Z10T0 1TB                    | 1         | 1      | 1.3%    |
| WDC WD10JPVX-60JC3T1 1TB                    | 1         | 1      | 1.3%    |
| WDC WD10JPVX-60JC3T0 1TB                    | 1         | 1      | 1.3%    |
| WDC WD10JPVX-22JC3T0 1TB                    | 1         | 1      | 1.3%    |
| WDC PC SN520 SDAPMUW-128G-1001 128GB        | 1         | 1      | 1.3%    |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD    | 1         | 1      | 1.3%    |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD    | 1         | 1      | 1.3%    |
| Toshiba MQ04ABF100 1TB                      | 1         | 1      | 1.3%    |
| Toshiba MQ01ACF050 500GB                    | 1         | 1      | 1.3%    |
| Toshiba MQ01ACF032 320GB                    | 1         | 1      | 1.3%    |
| Toshiba MK7559GSXP 752GB                    | 1         | 1      | 1.3%    |
| Toshiba MK3252GSX 320GB                     | 1         | 1      | 1.3%    |
| Team TM8FP4004T 4TB                         | 1         | 1      | 1.3%    |
| SPCC Solid State Disk 128GB                 | 1         | 1      | 1.3%    |
| SK hynix HFS512G39TND-N210A 512GB SSD       | 1         | 1      | 1.3%    |
| SK hynix HFS128G39TND-N210A 128GB SSD       | 1         | 1      | 1.3%    |
| SK hynix BC501 NVMe Solid State Drive 512GB | 1         | 1      | 1.3%    |
| Silicon Motion 1TB PCS PCIe M.2 SSD         | 1         | 1      | 1.3%    |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 1.3%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 16     | 19.48%  |
| Seagate             | 12        | 12     | 15.58%  |
| SK hynix            | 9         | 9      | 11.69%  |
| HGST                | 8         | 9      | 10.39%  |
| Toshiba             | 7         | 7      | 9.09%   |
| Samsung Electronics | 5         | 5      | 6.49%   |
| Kingston            | 2         | 2      | 2.6%    |
| Intel               | 2         | 2      | 2.6%    |
| Crucial             | 2         | 2      | 2.6%    |
| A-DATA Technology   | 2         | 2      | 2.6%    |
| XPG                 | 1         | 1      | 1.3%    |
| WHALEKOM            | 1         | 1      | 1.3%    |
| Team                | 1         | 1      | 1.3%    |
| SPCC                | 1         | 1      | 1.3%    |
| Silicon Motion      | 1         | 1      | 1.3%    |
| SanDisk             | 1         | 1      | 1.3%    |
| Micron Technology   | 1         | 1      | 1.3%    |
| LITEON              | 1         | 1      | 1.3%    |
| Lexar               | 1         | 1      | 1.3%    |
| Leven               | 1         | 1      | 1.3%    |
| Hitachi             | 1         | 3      | 1.3%    |
| Hewlett-Packard     | 1         | 1      | 1.3%    |
| Apacer              | 1         | 1      | 1.3%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 12        | 12     | 33.33%  |
| WDC     | 10        | 10     | 27.78%  |
| HGST    | 8         | 9      | 22.22%  |
| Toshiba | 5         | 5      | 13.89%  |
| Hitachi | 1         | 3      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 39     | 46.75%  |
| SSD  | 21        | 22     | 27.27%  |
| NVMe | 20        | 20     | 25.97%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 50%     |
| Intenso JAJP600M1TB               | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Intenso             | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2353      | 3635   | 69.93%  |
| Works    | 934       | 1231   | 27.76%  |
| Malfunc  | 76        | 81     | 2.26%   |
| Failed   | 2         | 2      | 0.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1848      | 44.07%  |
| Samsung Electronics                     | 631       | 15.05%  |
| AMD                                     | 348       | 8.3%    |
| SanDisk                                 | 326       | 7.77%   |
| SK hynix                                | 215       | 5.13%   |
| Micron Technology                       | 162       | 3.86%   |
| Kingston Technology Company             | 96        | 2.29%   |
| Phison Electronics                      | 83        | 1.98%   |
| KIOXIA                                  | 74        | 1.76%   |
| Toshiba America Info Systems            | 67        | 1.6%    |
| Micron/Crucial Technology               | 65        | 1.55%   |
| Silicon Motion                          | 48        | 1.14%   |
| Nvidia                                  | 43        | 1.03%   |
| ADATA Technology                        | 38        | 0.91%   |
| Solid State Storage Technology          | 26        | 0.62%   |
| Marvell Technology Group                | 18        | 0.43%   |
| MAXIO Technology (Hangzhou)             | 17        | 0.41%   |
| Apple                                   | 14        | 0.33%   |
| Union Memory (Shenzhen)                 | 13        | 0.31%   |
| Solidigm                                | 12        | 0.29%   |
| Shenzhen Longsys Electronics            | 11        | 0.26%   |
| Realtek Semiconductor                   | 11        | 0.26%   |
| INNOGRIT                                | 5         | 0.12%   |
| Yangtze Memory Technologies             | 3         | 0.07%   |
| Shenzhen Unionmemory Information System | 3         | 0.07%   |
| Hosin Global Electronics                | 3         | 0.07%   |
| Transcend                               | 2         | 0.05%   |
| Seagate Technology                      | 2         | 0.05%   |
| Lite-On Technology                      | 2         | 0.05%   |
| Silicon Image                           | 1         | 0.02%   |
| OCZ Technology Group                    | 1         | 0.02%   |
| O2 Micro                                | 1         | 0.02%   |
| Netac Technology                        | 1         | 0.02%   |
| Lenovo                                  | 1         | 0.02%   |
| JMicron Technology                      | 1         | 0.02%   |
| ASMedia Technology                      | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 332       | 7.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 225       | 5.12%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 195       | 4.44%   |
| Intel Volume Management Device NVMe RAID Controller                            | 179       | 4.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 163       | 3.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 150       | 3.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 146       | 3.32%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 145       | 3.3%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 126       | 2.87%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 102       | 2.32%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 93        | 2.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 86        | 1.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 82        | 1.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 81        | 1.84%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 67        | 1.52%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 61        | 1.39%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 57        | 1.3%    |
| Intel Comet Lake SATA AHCI Controller                                          | 55        | 1.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 53        | 1.21%   |
| Intel SSD 660P Series                                                          | 51        | 1.16%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 51        | 1.16%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 50        | 1.14%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 47        | 1.07%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 44        | 1%      |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 43        | 0.98%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 42        | 0.96%   |
| Intel Tiger Lake-LP SATA Controller                                            | 42        | 0.96%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 41        | 0.93%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 40        | 0.91%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 40        | 0.91%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 39        | 0.89%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 39        | 0.89%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 39        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 39        | 0.89%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 35        | 0.8%    |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 31        | 0.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 31        | 0.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 31        | 0.71%   |
| Phison E12 NVMe Controller                                                     | 30        | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 29        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1884      | 45.68%  |
| NVMe | 1795      | 43.53%  |
| RAID | 379       | 9.19%   |
| IDE  | 66        | 1.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2464      | 76.78%  |
| AMD    | 745       | 23.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 62        | 1.93%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 54        | 1.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 52        | 1.62%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 51        | 1.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 51        | 1.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 48        | 1.5%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 47        | 1.46%   |
| Intel 12th Gen Core i7-12700H                 | 46        | 1.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 45        | 1.4%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 43        | 1.34%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 39        | 1.21%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 37        | 1.15%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 37        | 1.15%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 36        | 1.12%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 34        | 1.06%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 33        | 1.03%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 33        | 1.03%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 31        | 0.97%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 30        | 0.93%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 28        | 0.87%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 28        | 0.87%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 28        | 0.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 27        | 0.84%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 25        | 0.78%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 24        | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 23        | 0.72%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 22        | 0.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 22        | 0.69%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 21        | 0.65%   |
| Intel 12th Gen Core i5-1235U                  | 21        | 0.65%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 20        | 0.62%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 19        | 0.59%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 19        | 0.59%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 19        | 0.59%   |
| Intel 12th Gen Core i7-1255U                  | 18        | 0.56%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 18        | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 17        | 0.53%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 17        | 0.53%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 17        | 0.53%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 17        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 764       | 23.81%  |
| Intel Core i5                  | 698       | 21.75%  |
| Other                          | 573       | 17.86%  |
| AMD Ryzen 7                    | 260       | 8.1%    |
| AMD Ryzen 5                    | 205       | 6.39%   |
| Intel Core i3                  | 163       | 5.08%   |
| Intel Celeron                  | 92        | 2.87%   |
| Intel Core 2 Duo               | 76        | 2.37%   |
| AMD Ryzen 9                    | 61        | 1.9%    |
| AMD Ryzen 7 PRO                | 41        | 1.28%   |
| AMD Ryzen 3                    | 26        | 0.81%   |
| Intel Pentium                  | 24        | 0.75%   |
| Intel Core i9                  | 22        | 0.69%   |
| AMD Ryzen 5 PRO                | 22        | 0.69%   |
| AMD A8                         | 20        | 0.62%   |
| AMD A10                        | 20        | 0.62%   |
| AMD A6                         | 19        | 0.59%   |
| Intel Core                     | 18        | 0.56%   |
| Intel Pentium Dual-Core        | 13        | 0.41%   |
| AMD A4                         | 11        | 0.34%   |
| Intel Xeon                     | 10        | 0.31%   |
| AMD Athlon                     | 9         | 0.28%   |
| Intel Pentium Silver           | 8         | 0.25%   |
| AMD E1                         | 5         | 0.16%   |
| AMD E                          | 5         | 0.16%   |
| AMD E2                         | 4         | 0.12%   |
| Intel Core m3                  | 3         | 0.09%   |
| Intel Atom                     | 3         | 0.09%   |
| AMD Ryzen 3 PRO                | 3         | 0.09%   |
| AMD FX                         | 3         | 0.09%   |
| AMD Athlon X2                  | 3         | 0.09%   |
| AMD A12                        | 3         | 0.09%   |
| Intel Genuine                  | 2         | 0.06%   |
| Intel Core m5                  | 2         | 0.06%   |
| Intel Core M                   | 2         | 0.06%   |
| Intel Core 2                   | 2         | 0.06%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.06%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.06%   |
| AMD Phenom II                  | 2         | 0.06%   |
| AMD Athlon II                  | 2         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1061      | 33.06%  |
| 4      | 1037      | 32.32%  |
| 8      | 453       | 14.12%  |
| 6      | 341       | 10.63%  |
| 14     | 114       | 3.55%   |
| 10     | 78        | 2.43%   |
| 12     | 62        | 1.93%   |
| 16     | 30        | 0.93%   |
| 24     | 21        | 0.65%   |
| 1      | 10        | 0.31%   |
| 3      | 2         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3207      | 99.94%  |
| 2      | 2         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2838      | 88.38%  |
| 1      | 373       | 11.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3209      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2744      | 84.43%  |
| 0x0a50000c | 44        | 1.35%   |
| 0x806c1    | 36        | 1.11%   |
| 0x906a3    | 23        | 0.71%   |
| 0x806d1    | 23        | 0.71%   |
| 0x08608103 | 22        | 0.68%   |
| 0xa0652    | 20        | 0.62%   |
| 0x806ea    | 20        | 0.62%   |
| 0x0a404102 | 20        | 0.62%   |
| 0x08600106 | 20        | 0.62%   |
| 0x806ec    | 19        | 0.58%   |
| 0x906ea    | 17        | 0.52%   |
| 0x306a9    | 17        | 0.52%   |
| 0x406e3    | 14        | 0.43%   |
| 0x0a50000d | 14        | 0.43%   |
| 0x0a404101 | 13        | 0.4%    |
| 0x08108109 | 13        | 0.4%    |
| 0x806e9    | 12        | 0.37%   |
| 0x40651    | 11        | 0.34%   |
| 0x08600104 | 11        | 0.34%   |
| 0x906a4    | 9         | 0.28%   |
| 0x206a7    | 9         | 0.28%   |
| 0x306d4    | 8         | 0.25%   |
| 0x1067a    | 8         | 0.25%   |
| 0x906e9    | 7         | 0.22%   |
| 0x706e5    | 7         | 0.22%   |
| 0x506e3    | 7         | 0.22%   |
| 0x306c3    | 7         | 0.22%   |
| 0x0a704103 | 7         | 0.22%   |
| 0x08108102 | 7         | 0.22%   |
| 0x08600103 | 6         | 0.18%   |
| 0x806eb    | 5         | 0.15%   |
| 0x706a8    | 4         | 0.12%   |
| 0x0a601203 | 4         | 0.12%   |
| 0x08608102 | 4         | 0.12%   |
| 0x906c0    | 3         | 0.09%   |
| 0x806c2    | 3         | 0.09%   |
| 0x08a00008 | 3         | 0.09%   |
| 0x0810100b | 3         | 0.09%   |
| 0xa0660    | 2         | 0.06%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 600       | 18.65%  |
| Unknown           | 460       | 14.3%   |
| Haswell           | 242       | 7.52%   |
| TigerLake         | 184       | 5.72%   |
| SandyBridge       | 179       | 5.56%   |
| Zen 3             | 177       | 5.5%    |
| IvyBridge         | 176       | 5.47%   |
| Skylake           | 153       | 4.76%   |
| Alderlake Hybrid  | 136       | 4.23%   |
| Broadwell         | 127       | 3.95%   |
| CometLake         | 110       | 3.42%   |
| Zen 2             | 104       | 3.23%   |
| Zen+              | 97        | 3.02%   |
| Penryn            | 82        | 2.55%   |
| Icelake           | 80        | 2.49%   |
| Westmere          | 55        | 1.71%   |
| Goldmont plus     | 41        | 1.27%   |
| Silvermont        | 32        | 0.99%   |
| Excavator         | 31        | 0.96%   |
| Zen               | 25        | 0.78%   |
| Puma              | 18        | 0.56%   |
| Piledriver        | 17        | 0.53%   |
| Core              | 14        | 0.44%   |
| K10 Llano         | 11        | 0.34%   |
| Goldmont          | 11        | 0.34%   |
| Steamroller       | 8         | 0.25%   |
| Bobcat            | 8         | 0.25%   |
| Meteorlake Hybrid | 6         | 0.19%   |
| Jaguar            | 6         | 0.19%   |
| Nehalem           | 5         | 0.16%   |
| K8 Hammer         | 5         | 0.16%   |
| K10               | 5         | 0.16%   |
| Tremont           | 4         | 0.12%   |
| K8 & K10 hybrid   | 4         | 0.12%   |
| Gracemont         | 4         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2276      | 52.58%  |
| Nvidia | 1200      | 27.72%  |
| AMD    | 853       | 19.7%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 168       | 3.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 163       | 3.69%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 161       | 3.65%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 145       | 3.28%   |
| Intel UHD Graphics 620                                                    | 133       | 3.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 130       | 2.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 119       | 2.7%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 105       | 2.38%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]               | 101       | 2.29%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 97        | 2.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 97        | 2.2%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 90        | 2.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 88        | 1.99%   |
| Intel HD Graphics 5500                                                    | 86        | 1.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 86        | 1.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 84        | 1.9%    |
| AMD Rembrandt [Radeon 680M]                                               | 81        | 1.83%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 79        | 1.79%   |
| AMD Lucienne                                                              | 77        | 1.74%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 76        | 1.72%   |
| Intel HD Graphics 620                                                     | 74        | 1.68%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 73        | 1.65%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 61        | 1.38%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 58        | 1.31%   |
| Intel HD Graphics 630                                                     | 58        | 1.31%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                    | 57        | 1.29%   |
| Intel Core Processor Integrated Graphics Controller                       | 45        | 1.02%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 41        | 0.93%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                           | 40        | 0.91%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 40        | 0.91%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 36        | 0.82%   |
| Intel HD Graphics 530                                                     | 35        | 0.79%   |
| AMD Phoenix1                                                              | 34        | 0.77%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 33        | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 33        | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 31        | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 31        | 0.7%    |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                           | 31        | 0.7%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 29        | 0.66%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                           | 26        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1397      | 43.3%   |
| Intel + Nvidia     | 778       | 24.12%  |
| 1 x AMD            | 472       | 14.63%  |
| AMD + Nvidia       | 229       | 7.1%    |
| 1 x Nvidia         | 183       | 5.67%   |
| Intel + AMD        | 95        | 2.94%   |
| 2 x AMD            | 59        | 1.83%   |
| 2 x Nvidia         | 5         | 0.15%   |
| Other              | 4         | 0.12%   |
| 2 x Intel          | 2         | 0.06%   |
| Intel + 2 x Nvidia | 2         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2207      | 68.1%   |
| Proprietary | 948       | 29.25%  |
| Unknown     | 86        | 2.65%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2802      | 86.48%  |
| 0.01-0.5   | 168       | 5.19%   |
| 1.01-2.0   | 83        | 2.56%   |
| 3.01-4.0   | 61        | 1.88%   |
| 5.01-6.0   | 45        | 1.39%   |
| 7.01-8.0   | 42        | 1.3%    |
| 0.51-1.0   | 27        | 0.83%   |
| 8.01-16.0  | 8         | 0.25%   |
| 2.01-3.0   | 4         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 682       | 17.96%  |
| BOE                     | 599       | 15.77%  |
| Chimei Innolux          | 544       | 14.32%  |
| LG Display              | 460       | 12.11%  |
| Samsung Electronics     | 305       | 8.03%   |
| Apple                   | 189       | 4.98%   |
| Dell                    | 121       | 3.19%   |
| Sharp                   | 113       | 2.98%   |
| Goldstar                | 106       | 2.79%   |
| PANDA                   | 88        | 2.32%   |
| Lenovo                  | 55        | 1.45%   |
| InfoVision              | 47        | 1.24%   |
| Chi Mei Optoelectronics | 44        | 1.16%   |
| Acer                    | 42        | 1.11%   |
| CSO                     | 41        | 1.08%   |
| AOC                     | 35        | 0.92%   |
| Hewlett-Packard         | 32        | 0.84%   |
| Philips                 | 29        | 0.76%   |
| ASUSTek Computer        | 25        | 0.66%   |
| TMX                     | 19        | 0.5%    |
| BenQ                    | 19        | 0.5%    |
| Ancor Communications    | 17        | 0.45%   |
| Iiyama                  | 15        | 0.39%   |
| ViewSonic               | 13        | 0.34%   |
| HKC                     | 11        | 0.29%   |
| MSI                     | 9         | 0.24%   |
| RTK                     | 7         | 0.18%   |
| Sony                    | 6         | 0.16%   |
| Panasonic               | 6         | 0.16%   |
| Gigabyte Technology     | 6         | 0.16%   |
| Vestel Elektronik       | 5         | 0.13%   |
| Toshiba                 | 5         | 0.13%   |
| NEC Computers           | 5         | 0.13%   |
| LG Philips              | 5         | 0.13%   |
| JDI                     | 5         | 0.13%   |
| Vizio                   | 4         | 0.11%   |
| HUAWEI                  | 4         | 0.11%   |
| Hitachi                 | 4         | 0.11%   |
| Eizo                    | 4         | 0.11%   |
| TMA                     | 3         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 48        | 1.25%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 32        | 0.83%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 32        | 0.83%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 31        | 0.81%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 25        | 0.65%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 24        | 0.63%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 21        | 0.55%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 19        | 0.5%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 19        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 17        | 0.44%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 17        | 0.44%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 16        | 0.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 15        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 14        | 0.36%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 14        | 0.36%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 14        | 0.36%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 14        | 0.36%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 13        | 0.34%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch      | 13        | 0.34%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 13        | 0.34%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 13        | 0.34%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 13        | 0.34%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 13        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 12        | 0.31%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 11        | 0.29%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 11        | 0.29%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 11        | 0.29%   |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch                | 11        | 0.29%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                  | 11        | 0.29%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 10        | 0.26%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 10        | 0.26%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 10        | 0.26%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 10        | 0.26%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 10        | 0.26%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 10        | 0.26%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 10        | 0.26%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 9         | 0.23%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 9         | 0.23%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 9         | 0.23%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 9         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1754      | 49.17%  |
| 1366x768 (WXGA)    | 654       | 18.33%  |
| 2560x1440 (QHD)    | 163       | 4.57%   |
| 3840x2160 (4K)     | 161       | 4.51%   |
| 1920x1200 (WUXGA)  | 143       | 4.01%   |
| 2560x1600          | 123       | 3.45%   |
| 1600x900 (HD+)     | 108       | 3.03%   |
| 2880x1800          | 71        | 1.99%   |
| 1280x800 (WXGA)    | 71        | 1.99%   |
| 1440x900 (WXGA+)   | 63        | 1.77%   |
| 3440x1440          | 27        | 0.76%   |
| 2560x1080          | 26        | 0.73%   |
| 3840x2400          | 25        | 0.7%    |
| 2160x1440          | 18        | 0.5%    |
| 3072x1920          | 17        | 0.48%   |
| 1680x1050 (WSXGA+) | 17        | 0.48%   |
| 1280x1024 (SXGA)   | 13        | 0.36%   |
| 2256x1504          | 11        | 0.31%   |
| 3200x2000          | 10        | 0.28%   |
| 3200x1800 (QHD+)   | 10        | 0.28%   |
| 3840x1080          | 9         | 0.25%   |
| 1360x768           | 8         | 0.22%   |
| 3840x1100          | 7         | 0.2%    |
| 3456x2160          | 7         | 0.2%    |
| 1920x1280          | 6         | 0.17%   |
| 2240x1400          | 5         | 0.14%   |
| 3000x2000          | 4         | 0.11%   |
| 2880x1620          | 4         | 0.11%   |
| 2520x1680          | 4         | 0.11%   |
| 1920x540           | 4         | 0.11%   |
| 2304x1440          | 3         | 0.08%   |
| 1280x720 (HD)      | 3         | 0.08%   |
| 800x1280           | 2         | 0.06%   |
| 2560x1700          | 2         | 0.06%   |
| 1600x2560          | 2         | 0.06%   |
| Unknown            | 2         | 0.06%   |
| 4096x2304          | 1         | 0.03%   |
| 3840x1200          | 1         | 0.03%   |
| 3120x2080          | 1         | 0.03%   |
| 2560x2880          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1489      | 39.26%  |
| 13      | 570       | 15.03%  |
| 14      | 484       | 12.76%  |
| 17      | 251       | 6.62%   |
| 16      | 165       | 4.35%   |
| 27      | 155       | 4.09%   |
| 24      | 124       | 3.27%   |
| 23      | 82        | 2.16%   |
| 21      | 70        | 1.85%   |
| 31      | 67        | 1.77%   |
| 12      | 62        | 1.63%   |
| 34      | 47        | 1.24%   |
| 11      | 35        | 0.92%   |
| 18      | 24        | 0.63%   |
| 19      | 19        | 0.5%    |
| 84      | 16        | 0.42%   |
| Unknown | 16        | 0.42%   |
| 32      | 14        | 0.37%   |
| 40      | 13        | 0.34%   |
| 48      | 10        | 0.26%   |
| 22      | 9         | 0.24%   |
| 20      | 8         | 0.21%   |
| 35      | 7         | 0.18%   |
| 72      | 6         | 0.16%   |
| 54      | 6         | 0.16%   |
| 28      | 5         | 0.13%   |
| 49      | 4         | 0.11%   |
| 25      | 4         | 0.11%   |
| 43      | 3         | 0.08%   |
| 29      | 3         | 0.08%   |
| 26      | 3         | 0.08%   |
| 8       | 3         | 0.08%   |
| 74      | 2         | 0.05%   |
| 42      | 2         | 0.05%   |
| 33      | 2         | 0.05%   |
| 86      | 1         | 0.03%   |
| 65      | 1         | 0.03%   |
| 60      | 1         | 0.03%   |
| 57      | 1         | 0.03%   |
| 52      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 2356      | 62.69%  |
| 201-300     | 405       | 10.78%  |
| 501-600     | 328       | 8.73%   |
| 351-400     | 292       | 7.77%   |
| 401-500     | 118       | 3.14%   |
| 601-700     | 96        | 2.55%   |
| 701-800     | 64        | 1.7%    |
| 1001-1500   | 27        | 0.72%   |
| 1501-2000   | 24        | 0.64%   |
| 801-900     | 21        | 0.56%   |
| Unknown     | 16        | 0.43%   |
| 901-1000    | 6         | 0.16%   |
| 101-200     | 3         | 0.08%   |
| 1-100       | 2         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2631      | 78.63%  |
| 16/10   | 560       | 16.74%  |
| 21/9    | 58        | 1.73%   |
| 3/2     | 48        | 1.43%   |
| 5/4     | 15        | 0.45%   |
| 32/9    | 10        | 0.3%    |
| 3.40    | 7         | 0.21%   |
| Unknown | 4         | 0.12%   |
| 4/3     | 2         | 0.06%   |
| 0.63    | 2         | 0.06%   |
| 0.56    | 2         | 0.06%   |
| 6/5     | 1         | 0.03%   |
| 3.73    | 1         | 0.03%   |
| 3.20    | 1         | 0.03%   |
| 1.96    | 1         | 0.03%   |
| 0.89    | 1         | 0.03%   |
| 0.67    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1496      | 39.57%  |
| 81-90          | 833       | 22.03%  |
| 201-250        | 233       | 6.16%   |
| 121-130        | 228       | 6.03%   |
| 71-80          | 197       | 5.21%   |
| 301-350        | 156       | 4.13%   |
| 111-120        | 152       | 4.02%   |
| 351-500        | 140       | 3.7%    |
| 61-70          | 59        | 1.56%   |
| 151-200        | 45        | 1.19%   |
| 51-60          | 42        | 1.11%   |
| More than 1000 | 39        | 1.03%   |
| 251-300        | 36        | 0.95%   |
| 501-1000       | 34        | 0.9%    |
| 141-150        | 30        | 0.79%   |
| 131-140        | 20        | 0.53%   |
| 91-100         | 20        | 0.53%   |
| Unknown        | 16        | 0.42%   |
| 1-40           | 5         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1730      | 46.59%  |
| 101-120       | 837       | 22.54%  |
| 51-100        | 488       | 13.14%  |
| 161-240       | 436       | 11.74%  |
| More than 240 | 169       | 4.55%   |
| 1-50          | 37        | 1%      |
| Unknown       | 16        | 0.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2548      | 77.87%  |
| 2     | 565       | 17.27%  |
| 3     | 81        | 2.48%   |
| 0     | 73        | 2.23%   |
| 4     | 4         | 0.12%   |
| 6     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 1757      | 34.72%  |
| Intel                                 | 1730      | 34.19%  |
| Qualcomm Atheros                      | 507       | 10.02%  |
| Broadcom                              | 305       | 6.03%   |
| MediaTek                              | 226       | 4.47%   |
| Broadcom Limited                      | 107       | 2.11%   |
| ASIX Electronics                      | 49        | 0.97%   |
| Samsung Electronics                   | 28        | 0.55%   |
| Nvidia                                | 26        | 0.51%   |
| TP-Link                               | 25        | 0.49%   |
| Qualcomm                              | 24        | 0.47%   |
| Marvell Technology Group              | 24        | 0.47%   |
| Dell                                  | 24        | 0.47%   |
| Ralink                                | 23        | 0.45%   |
| Xiaomi                                | 19        | 0.38%   |
| Ralink Technology                     | 19        | 0.38%   |
| DisplayLink                           | 19        | 0.38%   |
| Lenovo                                | 17        | 0.34%   |
| Sierra Wireless                       | 14        | 0.28%   |
| Hewlett-Packard                       | 10        | 0.2%    |
| NetGear                               | 9         | 0.18%   |
| JMicron Technology                    | 9         | 0.18%   |
| OPPO Electronics                      | 8         | 0.16%   |
| ASUSTek Computer                      | 8         | 0.16%   |
| Huawei Technologies                   | 7         | 0.14%   |
| Google                                | 6         | 0.12%   |
| Fibocom                               | 6         | 0.12%   |
| Ericsson Business Mobile Networks     | 6         | 0.12%   |
| OnePlus Technology (Shenzhen)         | 5         | 0.1%    |
| Motorola PCS                          | 5         | 0.1%    |
| Qualcomm Atheros Communications       | 4         | 0.08%   |
| Edimax Technology                     | 3         | 0.06%   |
| D-Link                                | 3         | 0.06%   |
| Arduino SA                            | 3         | 0.06%   |
| ZTE WCDMA Technologies MSM            | 2         | 0.04%   |
| Qualcomm Technologies                 | 2         | 0.04%   |
| Microsoft                             | 2         | 0.04%   |
| AVM                                   | 2         | 0.04%   |
| Apple                                 | 2         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1097      | 18.32%  |
| Intel Wi-Fi 6 AX200                                                    | 190       | 3.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 176       | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 168       | 2.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 151       | 2.52%   |
| Intel Wi-Fi 6 AX201                                                    | 141       | 2.36%   |
| Intel Wireless 8265 / 8275                                             | 134       | 2.24%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 120       | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 100       | 1.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 98        | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 97        | 1.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 84        | 1.4%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 83        | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 81        | 1.35%   |
| Intel Wireless 7260                                                    | 80        | 1.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 80        | 1.34%   |
| Intel Wireless 8260                                                    | 79        | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 75        | 1.25%   |
| Intel Wireless 7265                                                    | 74        | 1.24%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 67        | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 65        | 1.09%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 65        | 1.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 65        | 1.09%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 62        | 1.04%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 53        | 0.89%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 53        | 0.89%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 52        | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                                  | 51        | 0.85%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 50        | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 49        | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                      | 48        | 0.8%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 48        | 0.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 47        | 0.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 45        | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                          | 43        | 0.72%   |
| Intel Ethernet Connection I219-LM                                      | 41        | 0.68%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 41        | 0.68%   |
| Broadcom BCM43142 802.11b/g/n                                          | 38        | 0.63%   |
| Realtek Killer E2600 GbE Controller                                    | 36        | 0.6%    |
| Intel Ethernet Connection I217-LM                                      | 34        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1673      | 50.59%  |
| Realtek Semiconductor                 | 485       | 14.67%  |
| Qualcomm Atheros                      | 428       | 12.94%  |
| Broadcom                              | 269       | 8.13%   |
| MediaTek                              | 194       | 5.87%   |
| Broadcom Limited                      | 93        | 2.81%   |
| Ralink                                | 23        | 0.7%    |
| Qualcomm                              | 22        | 0.67%   |
| TP-Link                               | 21        | 0.64%   |
| Dell                                  | 20        | 0.6%    |
| Ralink Technology                     | 19        | 0.57%   |
| Sierra Wireless                       | 14        | 0.42%   |
| NetGear                               | 8         | 0.24%   |
| Fibocom                               | 6         | 0.18%   |
| ASUSTek Computer                      | 6         | 0.18%   |
| Hewlett-Packard                       | 5         | 0.15%   |
| Qualcomm Atheros Communications       | 4         | 0.12%   |
| Edimax Technology                     | 3         | 0.09%   |
| Qualcomm Technologies                 | 2         | 0.06%   |
| Microsoft                             | 2         | 0.06%   |
| D-Link                                | 2         | 0.06%   |
| AVM                                   | 2         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.06%   |
| ZyDAS                                 | 1         | 0.03%   |
| Linksys                               | 1         | 0.03%   |
| Arduino SA                            | 1         | 0.03%   |
| Accton Technology                     | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 190       | 5.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 151       | 4.54%   |
| Intel Wi-Fi 6 AX201                                                  | 141       | 4.24%   |
| Intel Wireless 8265 / 8275                                           | 134       | 4.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 120       | 3.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 100       | 3.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 98        | 2.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 97        | 2.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 84        | 2.53%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 83        | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 81        | 2.44%   |
| Intel Wireless 7260                                                  | 80        | 2.41%   |
| Intel Wireless 8260                                                  | 79        | 2.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 75        | 2.26%   |
| Intel Wireless 7265                                                  | 74        | 2.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 65        | 1.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 65        | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 65        | 1.96%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 62        | 1.87%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 53        | 1.59%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 53        | 1.59%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 50        | 1.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 49        | 1.47%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 47        | 1.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 47        | 1.41%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 45        | 1.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 41        | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                        | 38        | 1.14%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 36        | 1.08%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 34        | 1.02%   |
| Intel Wireless 3165                                                  | 29        | 0.87%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 29        | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 25        | 0.75%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                    | 23        | 0.69%   |
| Intel Centrino Ultimate-N 6300                                       | 23        | 0.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 22        | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 22        | 0.66%   |
| Intel Centrino Advanced-N 6235                                       | 22        | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 21        | 0.63%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 21        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1539      | 59.81%  |
| Intel                                  | 523       | 20.33%  |
| Qualcomm Atheros                       | 128       | 4.97%   |
| Broadcom                               | 110       | 4.28%   |
| ASIX Electronics                       | 49        | 1.9%    |
| MediaTek                               | 31        | 1.2%    |
| Nvidia                                 | 26        | 1.01%   |
| Marvell Technology Group               | 24        | 0.93%   |
| Xiaomi                                 | 19        | 0.74%   |
| DisplayLink                            | 19        | 0.74%   |
| Lenovo                                 | 17        | 0.66%   |
| Samsung Electronics                    | 16        | 0.62%   |
| Broadcom Limited                       | 15        | 0.58%   |
| JMicron Technology                     | 9         | 0.35%   |
| OPPO Electronics                       | 8         | 0.31%   |
| Google                                 | 6         | 0.23%   |
| OnePlus Technology (Shenzhen)          | 5         | 0.19%   |
| Motorola PCS                           | 5         | 0.19%   |
| Huawei Technologies                    | 5         | 0.19%   |
| TP-Link                                | 4         | 0.16%   |
| Hewlett-Packard                        | 3         | 0.12%   |
| Qualcomm                               | 2         | 0.08%   |
| ASUSTek Computer                       | 2         | 0.08%   |
| Apple                                  | 2         | 0.08%   |
| TP-Link Corporation Limited.           | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| NetGear                                | 1         | 0.04%   |
| ICS Advent                             | 1         | 0.04%   |
| D-Link                                 | 1         | 0.04%   |
| Belkin Components                      | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1097      | 41.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 176       | 6.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 168       | 6.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 80        | 3.05%   |
| Intel Ethernet Connection (4) I219-LM                                  | 51        | 1.94%   |
| Realtek RTL8125 2.5GbE Controller                                      | 48        | 1.83%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 48        | 1.83%   |
| ASIX AX88179 Gigabit Ethernet                                          | 43        | 1.64%   |
| Intel Ethernet Connection I219-LM                                      | 41        | 1.56%   |
| Realtek Killer E2600 GbE Controller                                    | 36        | 1.37%   |
| Intel Ethernet Connection I217-LM                                      | 34        | 1.3%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 31        | 1.18%   |
| Intel Ethernet Connection (3) I218-LM                                  | 27        | 1.03%   |
| Intel Ethernet Connection I218-LM                                      | 25        | 0.95%   |
| Intel Ethernet Connection (4) I219-V                                   | 22        | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 21        | 0.8%    |
| Nvidia MCP79 Ethernet                                                  | 21        | 0.8%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 19        | 0.72%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 18        | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 18        | 0.69%   |
| Intel Ethernet Connection (6) I219-LM                                  | 17        | 0.65%   |
| Intel Ethernet Connection (13) I219-V                                  | 17        | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 16        | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 16        | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 16        | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                                  | 15        | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                                  | 15        | 0.57%   |
| Intel Ethernet Connection (16) I219-V                                  | 15        | 0.57%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 15        | 0.57%   |
| Intel Ethernet Connection I219-V                                       | 14        | 0.53%   |
| Intel Ethernet Connection (6) I219-V                                   | 14        | 0.53%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 13        | 0.5%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 13        | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 12        | 0.46%   |
| Intel Ethernet Connection (16) I219-LM                                 | 11        | 0.42%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 11        | 0.42%   |
| Intel 82567LM Gigabit Network Connection                               | 10        | 0.38%   |
| Intel Ethernet Connection (13) I219-LM                                 | 9         | 0.34%   |
| Intel 82577LM Gigabit Network Connection                               | 9         | 0.34%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 9         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3133      | 55.93%  |
| Ethernet | 2429      | 43.36%  |
| Modem    | 35        | 0.62%   |
| Unknown  | 5         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2683      | 78.96%  |
| Ethernet | 714       | 21.01%  |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2173      | 67.72%  |
| 1     | 993       | 30.94%  |
| 0     | 25        | 0.78%   |
| 3     | 18        | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2213      | 67.76%  |
| Yes  | 1053      | 32.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1484      | 52.51%  |
| Realtek Semiconductor           | 285       | 10.08%  |
| Qualcomm Atheros Communications | 207       | 7.32%   |
| Apple                           | 194       | 6.86%   |
| IMC Networks                    | 174       | 6.16%   |
| Foxconn / Hon Hai               | 136       | 4.81%   |
| Lite-On Technology              | 97        | 3.43%   |
| Broadcom                        | 78        | 2.76%   |
| Dell                            | 31        | 1.1%    |
| Realtek                         | 22        | 0.78%   |
| MediaTek                        | 21        | 0.74%   |
| Cambridge Silicon Radio         | 18        | 0.64%   |
| Toshiba                         | 16        | 0.57%   |
| Hewlett-Packard                 | 15        | 0.53%   |
| USI                             | 10        | 0.35%   |
| Ralink                          | 9         | 0.32%   |
| ASUSTek Computer                | 6         | 0.21%   |
| Foxconn International           | 5         | 0.18%   |
| Ralink Technology               | 3         | 0.11%   |
| Opticis                         | 3         | 0.11%   |
| TP-Link                         | 2         | 0.07%   |
| Taiyo Yuden                     | 2         | 0.07%   |
| Smart Modular Technologies      | 2         | 0.07%   |
| Fujitsu                         | 2         | 0.07%   |
| Micro Star International        | 1         | 0.04%   |
| Integrated System Solution      | 1         | 0.04%   |
| Alps Electric                   | 1         | 0.04%   |
| Actions                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 394       | 13.94%  |
| Intel AX201 Bluetooth                               | 369       | 13.05%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 194       | 6.86%   |
| Realtek Bluetooth Radio                             | 189       | 6.69%   |
| Intel AX200 Bluetooth                               | 185       | 6.54%   |
| Intel AX211 Bluetooth                               | 181       | 6.4%    |
| Qualcomm Atheros  Bluetooth Device                  | 111       | 3.93%   |
| Apple Bluetooth Host Controller                     | 111       | 3.93%   |
| IMC Networks Wireless_Device                        | 91        | 3.22%   |
| Apple Bluetooth USB Host Controller                 | 69        | 2.44%   |
| Realtek  Bluetooth 4.2 Adapter                      | 54        | 1.91%   |
| Intel AX210 Bluetooth                               | 50        | 1.77%   |
| Foxconn / Hon Hai Wireless_Device                   | 47        | 1.66%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 36        | 1.27%   |
| IMC Networks Bluetooth Radio                        | 36        | 1.27%   |
| Foxconn / Hon Hai Bluetooth Device                  | 33        | 1.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 27        | 0.96%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 26        | 0.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 25        | 0.88%   |
| Lite-On Wireless_Device                             | 24        | 0.85%   |
| Intel Wireless-AC 3168 Bluetooth                    | 24        | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 23        | 0.81%   |
| Realtek Bluetooth Radio                             | 22        | 0.78%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 22        | 0.78%   |
| IMC Networks Bluetooth Device                       | 22        | 0.78%   |
| MediaTek Wireless_Device                            | 21        | 0.74%   |
| Lite-On Bluetooth Device                            | 20        | 0.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 0.67%   |
| Realtek 802.11ac WLAN Adapter                       | 18        | 0.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 18        | 0.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 17        | 0.6%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 16        | 0.57%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.57%   |
| Lite-On Atheros AR3012 Bluetooth                    | 12        | 0.42%   |
| Dell BCM20702A0 Bluetooth Module                    | 11        | 0.39%   |
| USI Bluetooth Device                                | 10        | 0.35%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 10        | 0.35%   |
| Lite-On Bluetooth Radio                             | 10        | 0.35%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 0.35%   |
| Realtek RTL8723B Bluetooth                          | 9         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2419      | 55.83%  |
| Nvidia                               | 805       | 18.58%  |
| AMD                                  | 791       | 18.26%  |
| C-Media Electronics                  | 31        | 0.72%   |
| Logitech                             | 30        | 0.69%   |
| Lenovo                               | 23        | 0.53%   |
| GN Netcom                            | 19        | 0.44%   |
| Realtek Semiconductor                | 17        | 0.39%   |
| JMTek                                | 14        | 0.32%   |
| Generalplus Technology               | 14        | 0.32%   |
| Kingston Technology                  | 13        | 0.3%    |
| Sony                                 | 12        | 0.28%   |
| Apple                                | 12        | 0.28%   |
| Hewlett-Packard                      | 11        | 0.25%   |
| SteelSeries ApS                      | 9         | 0.21%   |
| Plantronics                          | 9         | 0.21%   |
| Focusrite-Novation                   | 8         | 0.18%   |
| Texas Instruments                    | 7         | 0.16%   |
| Razer USA                            | 7         | 0.16%   |
| Corsair                              | 6         | 0.14%   |
| ASUSTek Computer                     | 6         | 0.14%   |
| FiiO Electronics Technology          | 4         | 0.09%   |
| DSEA A/S                             | 4         | 0.09%   |
| Walmart                              | 3         | 0.07%   |
| Turtle Beach                         | 3         | 0.07%   |
| Nordic Semiconductor ASA             | 3         | 0.07%   |
| TerraTec Electronic                  | 2         | 0.05%   |
| Samsung Electronics                  | 2         | 0.05%   |
| Samson Technologies                  | 2         | 0.05%   |
| Microsoft                            | 2         | 0.05%   |
| iConnectivity                        | 2         | 0.05%   |
| Dell                                 | 2         | 0.05%   |
| Creative Technology                  | 2         | 0.05%   |
| Bose                                 | 2         | 0.05%   |
| Blue Microphones                     | 2         | 0.05%   |
| Arturia                              | 2         | 0.05%   |
| Unknown                              | 2         | 0.05%   |
| Yamaha                               | 1         | 0.02%   |
| THX                                  | 1         | 0.02%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 602       | 11.34%  |
| Intel Sunrise Point-LP HD Audio                                            | 322       | 6.07%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 285       | 5.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 193       | 3.64%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 186       | 3.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 184       | 3.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 162       | 3.05%   |
| Intel Cannon Lake PCH cAVS                                                 | 146       | 2.75%   |
| Intel Broadwell-U Audio Controller                                         | 127       | 2.39%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 126       | 2.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 124       | 2.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 123       | 2.32%   |
| Intel Haswell-ULT HD Audio Controller                                      | 120       | 2.26%   |
| Intel 8 Series HD Audio Controller                                         | 119       | 2.24%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 107       | 2.02%   |
| Intel Comet Lake PCH cAVS                                                  | 100       | 1.88%   |
| Intel Comet Lake PCH-LP cAVS                                               | 94        | 1.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 89        | 1.68%   |
| Nvidia GA107 High Definition Audio Controller                              | 86        | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 86        | 1.62%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 84        | 1.58%   |
| Nvidia GA106 High Definition Audio Controller                              | 81        | 1.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 77        | 1.45%   |
| Nvidia GA104 High Definition Audio Controller                              | 76        | 1.43%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 72        | 1.36%   |
| Intel CM238 HD Audio Controller                                            | 72        | 1.36%   |
| Nvidia AD107 High Definition Audio Controller                              | 65        | 1.22%   |
| Nvidia TU106 High Definition Audio Controller                              | 64        | 1.21%   |
| AMD FCH Azalia Controller                                                  | 64        | 1.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 60        | 1.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 46        | 0.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 41        | 0.77%   |
| Nvidia GP107GL High Definition Audio Controller                            | 39        | 0.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 39        | 0.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 37        | 0.7%    |
| AMD Kabini HDMI/DP Audio                                                   | 37        | 0.7%    |
| Nvidia GP106 High Definition Audio Controller                              | 36        | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                              | 30        | 0.57%   |
| Nvidia GK107 HDMI Audio Controller                                         | 30        | 0.57%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 29        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 362       | 29.12%  |
| SK hynix                                | 288       | 23.17%  |
| Micron Technology                       | 196       | 15.77%  |
| Kingston                                | 76        | 6.11%   |
| Crucial                                 | 73        | 5.87%   |
| Unknown                                 | 31        | 2.49%   |
| Corsair                                 | 27        | 2.17%   |
| Unknown                                 | 27        | 2.17%   |
| A-DATA Technology                       | 20        | 1.61%   |
| Ramaxel Technology                      | 18        | 1.45%   |
| Smart                                   | 14        | 1.13%   |
| Team                                    | 12        | 0.97%   |
| Neo Forza                               | 12        | 0.97%   |
| Goldkey                                 | 11        | 0.88%   |
| G.Skill                                 | 11        | 0.88%   |
| Elpida                                  | 11        | 0.88%   |
| Unknown (ABCD)                          | 5         | 0.4%    |
| PNY                                     | 5         | 0.4%    |
| Nanya Technology                        | 4         | 0.32%   |
| Transcend                               | 3         | 0.24%   |
| Timetec                                 | 3         | 0.24%   |
| Smart Brazil                            | 3         | 0.24%   |
| GSkill                                  | 3         | 0.24%   |
| Teikon                                  | 2         | 0.16%   |
| Gold Key                                | 2         | 0.16%   |
| ChangXin Memory                         | 2         | 0.16%   |
| Avant                                   | 2         | 0.16%   |
| Wilk                                    | 1         | 0.08%   |
| Unknown (8A02)                          | 1         | 0.08%   |
| Unknown (0x0CAB)                        | 1         | 0.08%   |
| Unknown (0x0C26)                        | 1         | 0.08%   |
| Unknown (09B6)                          | 1         | 0.08%   |
| Unknown (09A4)                          | 1         | 0.08%   |
| Silicon Power Computer & Communications | 1         | 0.08%   |
| Silicon Power                           | 1         | 0.08%   |
| SHARETRONIC                             | 1         | 0.08%   |
| Patriot Memory (PDP Systems)            | 1         | 0.08%   |
| OM Nanotech                             | 1         | 0.08%   |
| Kllisre                                 | 1         | 0.08%   |
| HT Micron                               | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 28        | 2.14%   |
| Unknown                                                          | 27        | 2.07%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 1.99%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 1.45%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 1.38%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 1.23%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 1.07%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 14        | 1.07%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 1%      |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 12        | 0.92%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 0.92%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 11        | 0.84%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 11        | 0.84%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 11        | 0.84%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 10        | 0.77%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.69%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.69%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 9         | 0.69%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 8         | 0.61%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.61%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s   | 8         | 0.61%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 8         | 0.61%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 8         | 0.61%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 8         | 0.61%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 8         | 0.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.54%   |
| SK hynix RAM HMCG78AGBSA095N 16GB SODIMM DDR5 5600MT/s           | 7         | 0.54%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.54%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 7         | 0.54%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.54%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s          | 7         | 0.54%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 6         | 0.46%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 6         | 0.46%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.46%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 6         | 0.46%   |
| Samsung RAM M425R1GB4BB0-CQKOD 8GB SODIMM DDR5 4800MT/s          | 6         | 0.46%   |
| Neo Forza RAM NMSO432F82-3200E 32GB SODIMM DDR4 3200MT/s         | 6         | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 6         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 632       | 59.29%  |
| DDR3   | 151       | 14.17%  |
| DDR5   | 108       | 10.13%  |
| LPDDR5 | 74        | 6.94%   |
| LPDDR4 | 56        | 5.25%   |
| LPDDR3 | 36        | 3.38%   |
| SDRAM  | 5         | 0.47%   |
| DDR2   | 4         | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 894       | 82.09%  |
| Row Of Chips | 182       | 16.71%  |
| Chip         | 6         | 0.55%   |
| Unknown      | 6         | 0.55%   |
| DIMM         | 1         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 514       | 44.5%   |
| 16384 | 270       | 23.38%  |
| 4096  | 241       | 20.87%  |
| 32768 | 78        | 6.75%   |
| 2048  | 44        | 3.81%   |
| 1024  | 6         | 0.52%   |
| 49152 | 1         | 0.09%   |
| 3072  | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 369       | 32.57%  |
| 2667    | 213       | 18.8%   |
| 1600    | 110       | 9.71%   |
| 2400    | 74        | 6.53%   |
| 4800    | 73        | 6.44%   |
| 6400    | 53        | 4.68%   |
| 2133    | 49        | 4.32%   |
| 5600    | 36        | 3.18%   |
| 4267    | 29        | 2.56%   |
| 1867    | 15        | 1.32%   |
| 1333    | 14        | 1.24%   |
| 1334    | 13        | 1.15%   |
| 7500    | 12        | 1.06%   |
| 3266    | 12        | 1.06%   |
| 8400    | 9         | 0.79%   |
| 4266    | 9         | 0.79%   |
| 1067    | 9         | 0.79%   |
| 3733    | 4         | 0.35%   |
| 2933    | 4         | 0.35%   |
| 8600    | 3         | 0.26%   |
| 2048    | 3         | 0.26%   |
| 800     | 3         | 0.26%   |
| 8533    | 2         | 0.18%   |
| 7467    | 2         | 0.18%   |
| 5500    | 2         | 0.18%   |
| 5200    | 2         | 0.18%   |
| 4199    | 2         | 0.18%   |
| 3000    | 2         | 0.18%   |
| 1200    | 1         | 0.09%   |
| 1066    | 1         | 0.09%   |
| 667     | 1         | 0.09%   |
| 666     | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 31.25%  |
| Canon               | 4         | 25%     |
| Samsung Electronics | 2         | 12.5%   |
| Xerox               | 1         | 6.25%   |
| Seiko Epson         | 1         | 6.25%   |
| ICS Advent          | 1         | 6.25%   |
| Dymo-CoStar         | 1         | 6.25%   |
| Brother Industries  | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Canon PIXMA MX920 Series        | 2         | 12.5%   |
| Xerox B215                      | 1         | 6.25%   |
| Seiko Epson L382 Series         | 1         | 6.25%   |
| Samsung SCX-4600 Series         | 1         | 6.25%   |
| Samsung M2020 Series            | 1         | 6.25%   |
| ICS Advent Parallel Adapter     | 1         | 6.25%   |
| HP OfficeJet 3830 series        | 1         | 6.25%   |
| HP Ink Tank Wireless 410 series | 1         | 6.25%   |
| HP DeskJet Plus 4100 series     | 1         | 6.25%   |
| HP DeskJet 2130 series          | 1         | 6.25%   |
| HP Color LaserJet CP2025dn      | 1         | 6.25%   |
| Dymo-CoStar LabelWriter 450     | 1         | 6.25%   |
| Canon TR4700 series             | 1         | 6.25%   |
| Canon E400 series               | 1         | 6.25%   |
| Brother HL-L2370DW series       | 1         | 6.25%   |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 617       | 21.28%  |
| IMC Networks                           | 312       | 10.76%  |
| Microdia                               | 261       | 9%      |
| Realtek Semiconductor                  | 212       | 7.31%   |
| Bison Electronics                      | 212       | 7.31%   |
| Quanta                                 | 188       | 6.48%   |
| Sunplus Innovation Technology          | 146       | 5.03%   |
| Apple                                  | 134       | 4.62%   |
| Acer                                   | 109       | 3.76%   |
| Luxvisions Innotech Limited            | 107       | 3.69%   |
| Cheng Uei Precision Industry (Foxlink) | 79        | 2.72%   |
| Syntek                                 | 78        | 2.69%   |
| Lite-On Technology                     | 72        | 2.48%   |
| Sonix Technology                       | 52        | 1.79%   |
| Suyin                                  | 50        | 1.72%   |
| Logitech                               | 41        | 1.41%   |
| Silicon Motion                         | 30        | 1.03%   |
| SunplusIT                              | 20        | 0.69%   |
| Samsung Electronics                    | 20        | 0.69%   |
| Alcor Micro                            | 19        | 0.66%   |
| Shinetech                              | 16        | 0.55%   |
| Ricoh                                  | 9         | 0.31%   |
| Microsoft                              | 9         | 0.31%   |
| Z-Star Microelectronics                | 8         | 0.28%   |
| Primax Electronics                     | 8         | 0.28%   |
| Generalplus Technology                 | 6         | 0.21%   |
| Razer USA                              | 5         | 0.17%   |
| Tobii Technology AB                    | 4         | 0.14%   |
| OmniVision Technologies                | 4         | 0.14%   |
| Lenovo                                 | 4         | 0.14%   |
| kingcome                               | 4         | 0.14%   |
| Importek                               | 4         | 0.14%   |
| icSpring                               | 4         | 0.14%   |
| ALi                                    | 4         | 0.14%   |
| Tripath Technology                     | 3         | 0.1%    |
| HRY                                    | 3         | 0.1%    |
| AVerMedia Technologies                 | 3         | 0.1%    |
| Unknown                                | 3         | 0.1%    |
| Y Media                                | 2         | 0.07%   |
| Sunplus Technology                     | 2         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 162       | 5.55%   |
| Microdia Integrated_Webcam_HD                        | 145       | 4.97%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 113       | 3.87%   |
| IMC Networks Integrated Camera                       | 85        | 2.91%   |
| Realtek Integrated_Webcam_HD                         | 84        | 2.88%   |
| Syntek Integrated Camera                             | 59        | 2.02%   |
| Acer BisonCam,NB Pro                                 | 58        | 1.99%   |
| Chicony HD WebCam                                    | 52        | 1.78%   |
| Bison Integrated Camera                              | 51        | 1.75%   |
| Apple FaceTime HD Camera                             | 49        | 1.68%   |
| Bison HD Webcam                                      | 44        | 1.51%   |
| Quanta HD User Facing                                | 42        | 1.44%   |
| Sunplus Integrated_Webcam_HD                         | 41        | 1.41%   |
| Chicony USB2.0 Camera                                | 36        | 1.23%   |
| Apple Built-in iSight                                | 34        | 1.17%   |
| Sonix USB2.0 HD UVC WebCam                           | 33        | 1.13%   |
| Lite-On Integrated Camera                            | 32        | 1.1%    |
| Chicony HP HD Camera                                 | 32        | 1.1%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                   | 30        | 1.03%   |
| Luxvisions Innotech Limited Integrated Camera        | 27        | 0.93%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 27        | 0.93%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 26        | 0.89%   |
| Acer Integrated Camera                               | 26        | 0.89%   |
| Chicony HD User Facing                               | 25        | 0.86%   |
| Bison SunplusIT Integrated Camera                    | 25        | 0.86%   |
| Quanta HP HD Camera                                  | 23        | 0.79%   |
| Quanta ACER HD User Facing                           | 23        | 0.79%   |
| Quanta HP TrueVision HD Camera                       | 22        | 0.75%   |
| Samsung Galaxy series, misc. (MTP mode)              | 20        | 0.69%   |
| Microdia Integrated Webcam                           | 20        | 0.69%   |
| Chicony HP Truevision HD camera                      | 20        | 0.69%   |
| Chicony Chicony USB2.0 Camera                        | 18        | 0.62%   |
| Chicony USB2.0 VGA UVC WebCam                        | 17        | 0.58%   |
| Chicony USB 2.0 Camera                               | 17        | 0.58%   |
| Chicony HP Wide Vision HD Camera                     | 17        | 0.58%   |
| Realtek USB Camera                                   | 15        | 0.51%   |
| Realtek Integrated Webcam                            | 15        | 0.51%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 15        | 0.51%   |
| Luxvisions Innotech Limited HP HD Camera             | 15        | 0.51%   |
| IMC Networks HD Camera                               | 15        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 210       | 38.25%  |
| Validity Sensors                   | 151       | 27.5%   |
| Shenzhen Goodix Technology         | 86        | 15.66%  |
| Elan Microelectronics              | 30        | 5.46%   |
| Upek                               | 21        | 3.83%   |
| LighTuning Technology              | 21        | 3.83%   |
| AuthenTec                          | 12        | 2.19%   |
| Realtek USB2.0 Finger Print Bridge | 9         | 1.64%   |
| Focal-systems.Corp                 | 5         | 0.91%   |
| HOLTEK                             | 4         | 0.73%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 66        | 12.02%  |
| Shenzhen Goodix  Fingerprint Device                                        | 55        | 10.02%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 35        | 6.38%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 33        | 6.01%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 23        | 4.19%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 21        | 3.83%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 18        | 3.28%   |
| Shenzhen Goodix FingerPrint                                                | 18        | 3.28%   |
| Elan ELAN:ARM-M4                                                           | 15        | 2.73%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 2.37%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 13        | 2.37%   |
| Elan ELAN:Fingerprint                                                      | 13        | 2.37%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 12        | 2.19%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 2.19%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 12        | 2.19%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 11        | 2%      |
| Synaptics WBDI Device                                                      | 11        | 2%      |
| Synaptics Fingerprint reader [HP G6]                                       | 11        | 2%      |
| Validity Sensors VFS491                                                    | 10        | 1.82%   |
| Synaptics TouchPad                                                         | 10        | 1.82%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 1.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.64%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 1.64%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 9         | 1.64%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 8         | 1.46%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 1.46%   |
| Synaptics UWP WBDI Device                                                  | 8         | 1.46%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 1.46%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 8         | 1.46%   |
| Unknown                                                                    | 8         | 1.46%   |
| Synaptics  WBDI                                                            | 7         | 1.28%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 1.09%   |
| Synaptics Prometheus Fingerprint Reader                                    | 6         | 1.09%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 5         | 0.91%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.91%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.73%   |
| HOLTEK FocalTech Fingerprint Device                                        | 4         | 0.73%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 0.55%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.36%   |
| Elan WBF Fingerprint Sensor                                                | 2         | 0.36%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 110       | 54.73%  |
| Alcor Micro           | 60        | 29.85%  |
| O2 Micro              | 12        | 5.97%   |
| Upek                  | 7         | 3.48%   |
| Lenovo                | 7         | 3.48%   |
| Yubico.com            | 1         | 0.5%    |
| SCM Microsystems      | 1         | 0.5%    |
| OmniKey               | 1         | 0.5%    |
| Gemalto (was Gemplus) | 1         | 0.5%    |
| Clay Logic            | 1         | 0.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 60        | 29.85%  |
| Broadcom 58200                                                               | 39        | 19.4%   |
| Broadcom 5880                                                                | 28        | 13.93%  |
| Broadcom BCM5880 Secure Applications Processor                               | 27        | 13.43%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 7.46%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 11        | 5.47%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 3.48%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 3.48%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.5%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.5%    |
| OmniKey CardMan 4321                                                         | 1         | 0.5%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.5%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.5%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.5%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1949      | 59.48%  |
| 1     | 1073      | 32.74%  |
| 2     | 223       | 6.81%   |
| 3     | 27        | 0.82%   |
| 4     | 3         | 0.09%   |
| 6     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 532       | 33.8%   |
| Multimedia controller    | 257       | 16.33%  |
| Graphics card            | 198       | 12.58%  |
| Chipcard                 | 189       | 12.01%  |
| Net/wireless             | 146       | 9.28%   |
| Camera                   | 92        | 5.84%   |
| Bluetooth                | 64        | 4.07%   |
| Sound                    | 19        | 1.21%   |
| Storage                  | 17        | 1.08%   |
| Net/ethernet             | 16        | 1.02%   |
| Network                  | 12        | 0.76%   |
| Modem                    | 10        | 0.64%   |
| Card reader              | 10        | 0.64%   |
| Communication controller | 9         | 0.57%   |
| Storage/ide              | 2         | 0.13%   |
| Storage/nvme             | 1         | 0.06%   |

