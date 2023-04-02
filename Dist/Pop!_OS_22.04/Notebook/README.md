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

Total: 1941

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad U310                | [6add75e18c](https://linux-hardware.org/?probe=6add75e18c) | Apr 01, 2023 |
| Toshiba       | Satellite L45-B             | [6d4878cdbf](https://linux-hardware.org/?probe=6d4878cdbf) | Apr 01, 2023 |
| HP            | 240 G6 Notebook PC          | [44e093df31](https://linux-hardware.org/?probe=44e093df31) | Apr 01, 2023 |
| System76      | Lemur Pro                   | [5d57a3397e](https://linux-hardware.org/?probe=5d57a3397e) | Mar 31, 2023 |
| ASUSTek       | X751LD                      | [2ef82331de](https://linux-hardware.org/?probe=2ef82331de) | Mar 31, 2023 |
| Acer          | Aspire A515-56              | [bf846cebb9](https://linux-hardware.org/?probe=bf846cebb9) | Mar 30, 2023 |
| Acer          | Nitro AN515-58              | [27befad01f](https://linux-hardware.org/?probe=27befad01f) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | [21515b7373](https://linux-hardware.org/?probe=21515b7373) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | [080e22fdb2](https://linux-hardware.org/?probe=080e22fdb2) | Mar 30, 2023 |
| Toshiba       | IS 1413G                    | [13f35137bd](https://linux-hardware.org/?probe=13f35137bd) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [7ee1845d96](https://linux-hardware.org/?probe=7ee1845d96) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | [bb80f561a2](https://linux-hardware.org/?probe=bb80f561a2) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [854490056d](https://linux-hardware.org/?probe=854490056d) | Mar 29, 2023 |
| HP            | ZBook 15 G5                 | [059358e49b](https://linux-hardware.org/?probe=059358e49b) | Mar 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [af48722867](https://linux-hardware.org/?probe=af48722867) | Mar 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0667374075](https://linux-hardware.org/?probe=0667374075) | Mar 28, 2023 |
| Acer          | Nitro AN515-45              | [0aabfe954d](https://linux-hardware.org/?probe=0aabfe954d) | Mar 28, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [7939320fa4](https://linux-hardware.org/?probe=7939320fa4) | Mar 28, 2023 |
| Positivo      | Mobile                      | [60fd382fbf](https://linux-hardware.org/?probe=60fd382fbf) | Mar 28, 2023 |
| Positivo      | Mobile                      | [b08c430903](https://linux-hardware.org/?probe=b08c430903) | Mar 28, 2023 |
| Razer         | Blade                       | [ffa791eb4a](https://linux-hardware.org/?probe=ffa791eb4a) | Mar 28, 2023 |
| ASUSTek       | X751LD                      | [61382d0bd8](https://linux-hardware.org/?probe=61382d0bd8) | Mar 28, 2023 |
| Dell          | Inspiron 15-3567            | [d2b4780094](https://linux-hardware.org/?probe=d2b4780094) | Mar 28, 2023 |
| Toshiba       | IS 1413G                    | [635309aff4](https://linux-hardware.org/?probe=635309aff4) | Mar 28, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T400     | [5b4466c085](https://linux-hardware.org/?probe=5b4466c085) | Mar 28, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [8ddee342c9](https://linux-hardware.org/?probe=8ddee342c9) | Mar 28, 2023 |
| Dell          | XPS 15 9570                 | [5be538736f](https://linux-hardware.org/?probe=5be538736f) | Mar 27, 2023 |
| Toshiba       | Satellite C55-C             | [d7ec0eb4b1](https://linux-hardware.org/?probe=d7ec0eb4b1) | Mar 27, 2023 |
| Apple         | MacBook5,1                  | [a5c200217f](https://linux-hardware.org/?probe=a5c200217f) | Mar 26, 2023 |
| MSI           | GL63 8RC                    | [935b78c3da](https://linux-hardware.org/?probe=935b78c3da) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [537fc6af0e](https://linux-hardware.org/?probe=537fc6af0e) | Mar 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [55c29cec29](https://linux-hardware.org/?probe=55c29cec29) | Mar 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [905078c7b9](https://linux-hardware.org/?probe=905078c7b9) | Mar 26, 2023 |
| Dell          | Latitude E7240              | [3d91b46fda](https://linux-hardware.org/?probe=3d91b46fda) | Mar 26, 2023 |
| Dell          | XPS 13 9370                 | [3f3967267f](https://linux-hardware.org/?probe=3f3967267f) | Mar 26, 2023 |
| Lenovo        | Y50-70 20378                | [61897b32de](https://linux-hardware.org/?probe=61897b32de) | Mar 25, 2023 |
| HP            | Spectre Laptop 13-af0xx     | [6fdc683220](https://linux-hardware.org/?probe=6fdc683220) | Mar 25, 2023 |
| MSI           | Katana GF66 12UG            | [9e03ac14c0](https://linux-hardware.org/?probe=9e03ac14c0) | Mar 25, 2023 |
| Apple         | MacBookPro11,3              | [21c3ce9508](https://linux-hardware.org/?probe=21c3ce9508) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ac415822b8](https://linux-hardware.org/?probe=ac415822b8) | Mar 24, 2023 |
| HP            | Laptop 15-db0xxx            | [ad0e5c0483](https://linux-hardware.org/?probe=ad0e5c0483) | Mar 24, 2023 |
| Dell          | Latitude 5420               | [e6afbbee47](https://linux-hardware.org/?probe=e6afbbee47) | Mar 24, 2023 |
| HP            | EliteBook 8460p             | [f78f58795c](https://linux-hardware.org/?probe=f78f58795c) | Mar 24, 2023 |
| Alienware     | 17 R4                       | [3c456dc309](https://linux-hardware.org/?probe=3c456dc309) | Mar 24, 2023 |
| GPU Compan... | GWTN141-10                  | [9007c1d23f](https://linux-hardware.org/?probe=9007c1d23f) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [f8f47e3220](https://linux-hardware.org/?probe=f8f47e3220) | Mar 23, 2023 |
| Dell          | Precision 7710              | [25a4797475](https://linux-hardware.org/?probe=25a4797475) | Mar 23, 2023 |
| Toshiba       | IS 1413G                    | [3a75d7fb8d](https://linux-hardware.org/?probe=3a75d7fb8d) | Mar 23, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [aba9609828](https://linux-hardware.org/?probe=aba9609828) | Mar 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [f6580b20d3](https://linux-hardware.org/?probe=f6580b20d3) | Mar 22, 2023 |
| Apple         | MacBook5,1                  | [bc6e3fa274](https://linux-hardware.org/?probe=bc6e3fa274) | Mar 22, 2023 |
| Apple         | MacBookAir7,2               | [627590f38c](https://linux-hardware.org/?probe=627590f38c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | [a49ece0e6c](https://linux-hardware.org/?probe=a49ece0e6c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | [315f2256c6](https://linux-hardware.org/?probe=315f2256c6) | Mar 22, 2023 |
| Apple         | MacBookPro8,1               | [b616377b13](https://linux-hardware.org/?probe=b616377b13) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | [aff8d829e0](https://linux-hardware.org/?probe=aff8d829e0) | Mar 22, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [99fe9f96c6](https://linux-hardware.org/?probe=99fe9f96c6) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | [af60ed4cde](https://linux-hardware.org/?probe=af60ed4cde) | Mar 22, 2023 |
| Apple         | MacBookAir7,2               | [3b3376e72c](https://linux-hardware.org/?probe=3b3376e72c) | Mar 21, 2023 |
| HUAWEI        | KPL-W0X                     | [afc1ff125b](https://linux-hardware.org/?probe=afc1ff125b) | Mar 21, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [3c100c55be](https://linux-hardware.org/?probe=3c100c55be) | Mar 21, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | [039724e2c2](https://linux-hardware.org/?probe=039724e2c2) | Mar 21, 2023 |
| Dell          | G15 5511                    | [6d71997e08](https://linux-hardware.org/?probe=6d71997e08) | Mar 21, 2023 |
| Dell          | XPS L421X                   | [fd54af9534](https://linux-hardware.org/?probe=fd54af9534) | Mar 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [afe8ca841c](https://linux-hardware.org/?probe=afe8ca841c) | Mar 21, 2023 |
| Acer          | Aspire 5349                 | [c0f5810e5c](https://linux-hardware.org/?probe=c0f5810e5c) | Mar 21, 2023 |
| MSI           | Prestige 14Evo A11M         | [cac8d6b991](https://linux-hardware.org/?probe=cac8d6b991) | Mar 21, 2023 |
| HP            | Dev One Notebook PC         | [d6ff521952](https://linux-hardware.org/?probe=d6ff521952) | Mar 21, 2023 |
| Acer          | Nitro AN517-55              | [d6393f5710](https://linux-hardware.org/?probe=d6393f5710) | Mar 21, 2023 |
| HP            | Dev One Notebook PC         | [404c84b0ea](https://linux-hardware.org/?probe=404c84b0ea) | Mar 21, 2023 |
| Acer          | Nitro AN517-55              | [edf722e245](https://linux-hardware.org/?probe=edf722e245) | Mar 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | [2ff2eab844](https://linux-hardware.org/?probe=2ff2eab844) | Mar 21, 2023 |
| ASUSTek       | G74Sx                       | [d2b90b7d2f](https://linux-hardware.org/?probe=d2b90b7d2f) | Mar 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [2ef051fd19](https://linux-hardware.org/?probe=2ef051fd19) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [48de9eb9e3](https://linux-hardware.org/?probe=48de9eb9e3) | Mar 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [afcac034a9](https://linux-hardware.org/?probe=afcac034a9) | Mar 20, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [d08f174747](https://linux-hardware.org/?probe=d08f174747) | Mar 20, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [c9b4e3cf00](https://linux-hardware.org/?probe=c9b4e3cf00) | Mar 20, 2023 |
| Dell          | Latitude 5590               | [49922a3223](https://linux-hardware.org/?probe=49922a3223) | Mar 19, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [55dc5e3ef4](https://linux-hardware.org/?probe=55dc5e3ef4) | Mar 19, 2023 |
| MSI           | PS42 8M                     | [aad18852f4](https://linux-hardware.org/?probe=aad18852f4) | Mar 19, 2023 |
| ASUSTek       | G74Sx                       | [f7f92408dc](https://linux-hardware.org/?probe=f7f92408dc) | Mar 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6b6ceb1a1a](https://linux-hardware.org/?probe=6b6ceb1a1a) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e3410282c5](https://linux-hardware.org/?probe=e3410282c5) | Mar 19, 2023 |
| ASUSTek       | S551LB                      | [7d4485326f](https://linux-hardware.org/?probe=7d4485326f) | Mar 18, 2023 |
| GPU Compan... | GWTN141-10                  | [ff8db61ccf](https://linux-hardware.org/?probe=ff8db61ccf) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | [4eab8887fa](https://linux-hardware.org/?probe=4eab8887fa) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | [b3bf824f3a](https://linux-hardware.org/?probe=b3bf824f3a) | Mar 18, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [dd296a8801](https://linux-hardware.org/?probe=dd296a8801) | Mar 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S11N00    | [60d80937ea](https://linux-hardware.org/?probe=60d80937ea) | Mar 18, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [91ae5652cc](https://linux-hardware.org/?probe=91ae5652cc) | Mar 18, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [274f959cfc](https://linux-hardware.org/?probe=274f959cfc) | Mar 17, 2023 |
| Dell          | Latitude E7240              | [cbcae7df75](https://linux-hardware.org/?probe=cbcae7df75) | Mar 17, 2023 |
| Positivo      | N1250                       | [e5ee22876a](https://linux-hardware.org/?probe=e5ee22876a) | Mar 17, 2023 |
| HP            | ProBook 4530s               | [f0abd32fe4](https://linux-hardware.org/?probe=f0abd32fe4) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | [a7a6cc1ab5](https://linux-hardware.org/?probe=a7a6cc1ab5) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | [204994be7f](https://linux-hardware.org/?probe=204994be7f) | Mar 17, 2023 |
| TUXEDO        | Pulse 14 Gen1               | [525b267c31](https://linux-hardware.org/?probe=525b267c31) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [a1adc8641d](https://linux-hardware.org/?probe=a1adc8641d) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [a0eea87e02](https://linux-hardware.org/?probe=a0eea87e02) | Mar 17, 2023 |
| Unknown       | Unknown                     | [3eb0bf05b4](https://linux-hardware.org/?probe=3eb0bf05b4) | Mar 17, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0RP0... | [f901058202](https://linux-hardware.org/?probe=f901058202) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d6f5cd9505](https://linux-hardware.org/?probe=d6f5cd9505) | Mar 16, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | [5f48c46d68](https://linux-hardware.org/?probe=5f48c46d68) | Mar 16, 2023 |
| HP            | Laptop 15s-eq1xxx           | [59a304e790](https://linux-hardware.org/?probe=59a304e790) | Mar 15, 2023 |
| Acer          | Aspire A715-42G             | [8bdae79f7a](https://linux-hardware.org/?probe=8bdae79f7a) | Mar 15, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [6a2d338526](https://linux-hardware.org/?probe=6a2d338526) | Mar 15, 2023 |
| Razer         | Blade Stealth 13 (Early ... | [eb1d71edb4](https://linux-hardware.org/?probe=eb1d71edb4) | Mar 15, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | [af254fca4d](https://linux-hardware.org/?probe=af254fca4d) | Mar 15, 2023 |
| SAGER         | X8100                       | [90aaefeb9e](https://linux-hardware.org/?probe=90aaefeb9e) | Mar 15, 2023 |
| System76      | Pangolin                    | [4f39796131](https://linux-hardware.org/?probe=4f39796131) | Mar 15, 2023 |
| Dell          | Latitude E7240              | [d4ed345a47](https://linux-hardware.org/?probe=d4ed345a47) | Mar 14, 2023 |
| Lenovo        | ThinkPad T450s 20BWS14G0... | [1161c07721](https://linux-hardware.org/?probe=1161c07721) | Mar 14, 2023 |
| Sony          | VPCZ12V9R                   | [28be5f7f2b](https://linux-hardware.org/?probe=28be5f7f2b) | Mar 14, 2023 |
| Dell          | Latitude E7240              | [4a7d442938](https://linux-hardware.org/?probe=4a7d442938) | Mar 14, 2023 |
| HP            | EliteBook 8560w             | [44d9ce8acb](https://linux-hardware.org/?probe=44d9ce8acb) | Mar 14, 2023 |
| HP            | EliteBook 8560w             | [986fe8c418](https://linux-hardware.org/?probe=986fe8c418) | Mar 14, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [ae9f2da5a4](https://linux-hardware.org/?probe=ae9f2da5a4) | Mar 14, 2023 |
| HP            | EliteBook 840 G6            | [874706952d](https://linux-hardware.org/?probe=874706952d) | Mar 14, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [de22b8a7e6](https://linux-hardware.org/?probe=de22b8a7e6) | Mar 14, 2023 |
| Dell          | Inspiron 7348               | [7459d24035](https://linux-hardware.org/?probe=7459d24035) | Mar 13, 2023 |
| Toshiba       | IS 1413G                    | [b93a4bdcbb](https://linux-hardware.org/?probe=b93a4bdcbb) | Mar 13, 2023 |
| Acer          | Aspire 4530                 | [84f4733a96](https://linux-hardware.org/?probe=84f4733a96) | Mar 13, 2023 |
| Acer          | Nitro AN515-58              | [7f2ecd927d](https://linux-hardware.org/?probe=7f2ecd927d) | Mar 13, 2023 |
| Apple         | MacBookPro15,1              | [663f73a08e](https://linux-hardware.org/?probe=663f73a08e) | Mar 13, 2023 |
| Apple         | MacBookPro15,1              | [5d1a30091e](https://linux-hardware.org/?probe=5d1a30091e) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [a826b1cd32](https://linux-hardware.org/?probe=a826b1cd32) | Mar 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | [87ef2f6efb](https://linux-hardware.org/?probe=87ef2f6efb) | Mar 12, 2023 |
| HUAWEI        | NBM-WXX9                    | [27b710cd68](https://linux-hardware.org/?probe=27b710cd68) | Mar 12, 2023 |
| Google        | Kefka                       | [4a54e34e44](https://linux-hardware.org/?probe=4a54e34e44) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [7090114437](https://linux-hardware.org/?probe=7090114437) | Mar 12, 2023 |
| Dell          | Inspiron 5452               | [2c8ca0e296](https://linux-hardware.org/?probe=2c8ca0e296) | Mar 12, 2023 |
| Positivo B... | VJFE41F11X-XXXXXX           | [99f410d801](https://linux-hardware.org/?probe=99f410d801) | Mar 11, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [e101a1c94c](https://linux-hardware.org/?probe=e101a1c94c) | Mar 11, 2023 |
| HONOR         | NMH-WCX9                    | [d8cf10f11d](https://linux-hardware.org/?probe=d8cf10f11d) | Mar 11, 2023 |
| HP            | ZBook 17                    | [a775bc33c5](https://linux-hardware.org/?probe=a775bc33c5) | Mar 11, 2023 |
| Maibenben     | P748                        | [a44d1bb8e4](https://linux-hardware.org/?probe=a44d1bb8e4) | Mar 11, 2023 |
| Toshiba       | IS 1413G                    | [39cc207ce7](https://linux-hardware.org/?probe=39cc207ce7) | Mar 11, 2023 |
| Lenovo        | ThinkPad L440 20ASS0ET00    | [2ac6dfff4f](https://linux-hardware.org/?probe=2ac6dfff4f) | Mar 11, 2023 |
| GPD           | G1619-04                    | [302ff30130](https://linux-hardware.org/?probe=302ff30130) | Mar 11, 2023 |
| GPD           | G1619-04                    | [d8f5b9eec9](https://linux-hardware.org/?probe=d8f5b9eec9) | Mar 11, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [96f4bd0a52](https://linux-hardware.org/?probe=96f4bd0a52) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [969ab4279f](https://linux-hardware.org/?probe=969ab4279f) | Mar 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [c44f0eab3e](https://linux-hardware.org/?probe=c44f0eab3e) | Mar 10, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [44867c946f](https://linux-hardware.org/?probe=44867c946f) | Mar 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [50dd87563b](https://linux-hardware.org/?probe=50dd87563b) | Mar 10, 2023 |
| Samsung       | R430/R480/R440              | [cdb2525b51](https://linux-hardware.org/?probe=cdb2525b51) | Mar 10, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [410a5a70f3](https://linux-hardware.org/?probe=410a5a70f3) | Mar 10, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [eac4ae85a4](https://linux-hardware.org/?probe=eac4ae85a4) | Mar 10, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [baffc24bef](https://linux-hardware.org/?probe=baffc24bef) | Mar 10, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [187761b57d](https://linux-hardware.org/?probe=187761b57d) | Mar 09, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4e1196658a](https://linux-hardware.org/?probe=4e1196658a) | Mar 09, 2023 |
| HP            | ENVY Notebook               | [8a063efa19](https://linux-hardware.org/?probe=8a063efa19) | Mar 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [a8d1bd3e81](https://linux-hardware.org/?probe=a8d1bd3e81) | Mar 09, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [7805fe229d](https://linux-hardware.org/?probe=7805fe229d) | Mar 08, 2023 |
| Razer         | Blade 15 Advanced Model ... | [46fa9eab7d](https://linux-hardware.org/?probe=46fa9eab7d) | Mar 08, 2023 |
| Google        | Bobba                       | [01d8f57c7e](https://linux-hardware.org/?probe=01d8f57c7e) | Mar 08, 2023 |
| Lenovo        | IdeaPad U310                | [f666446ecb](https://linux-hardware.org/?probe=f666446ecb) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3ff5ff8f2d](https://linux-hardware.org/?probe=3ff5ff8f2d) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [3b02985778](https://linux-hardware.org/?probe=3b02985778) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [e6e0d7226d](https://linux-hardware.org/?probe=e6e0d7226d) | Mar 07, 2023 |
| HP            | Dev One Notebook PC         | [4a698cb3eb](https://linux-hardware.org/?probe=4a698cb3eb) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8a6c736217](https://linux-hardware.org/?probe=8a6c736217) | Mar 07, 2023 |
| Toshiba       | IS 1413G                    | [12954ccbdb](https://linux-hardware.org/?probe=12954ccbdb) | Mar 07, 2023 |
| Google        | Lillipup                    | [b924f92de8](https://linux-hardware.org/?probe=b924f92de8) | Mar 07, 2023 |
| HP            | Dev One Notebook PC         | [5a03b7e11e](https://linux-hardware.org/?probe=5a03b7e11e) | Mar 07, 2023 |
| Apple         | MacBookPro8,1               | [bef545e821](https://linux-hardware.org/?probe=bef545e821) | Mar 07, 2023 |
| Dell          | Inspiron 16 7610            | [625691c490](https://linux-hardware.org/?probe=625691c490) | Mar 06, 2023 |
| Dell          | Inspiron 16 7610            | [66b4f88fb7](https://linux-hardware.org/?probe=66b4f88fb7) | Mar 06, 2023 |
| HP            | 3115m                       | [87abd0ac9d](https://linux-hardware.org/?probe=87abd0ac9d) | Mar 06, 2023 |
| Dell          | G7 7588                     | [a50e6bef64](https://linux-hardware.org/?probe=a50e6bef64) | Mar 06, 2023 |
| HUAWEI        | KPL-W0X                     | [76ebbe553f](https://linux-hardware.org/?probe=76ebbe553f) | Mar 06, 2023 |
| Apple         | MacBookAir7,2               | [ae4d8e9128](https://linux-hardware.org/?probe=ae4d8e9128) | Mar 06, 2023 |
| MSI           | Vector GP76 12UHSO          | [e82fbd8c0a](https://linux-hardware.org/?probe=e82fbd8c0a) | Mar 06, 2023 |
| Acer          | Swift SFX14-41G             | [baff849073](https://linux-hardware.org/?probe=baff849073) | Mar 05, 2023 |
| HP            | ProBook 450 G1              | [a6c8ba1040](https://linux-hardware.org/?probe=a6c8ba1040) | Mar 05, 2023 |
| Apple         | MacBookAir7,2               | [fef18d1795](https://linux-hardware.org/?probe=fef18d1795) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [779113ef3c](https://linux-hardware.org/?probe=779113ef3c) | Mar 05, 2023 |
| HP            | Pavilion 15                 | [0c4050d1ef](https://linux-hardware.org/?probe=0c4050d1ef) | Mar 05, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [ff4621a345](https://linux-hardware.org/?probe=ff4621a345) | Mar 05, 2023 |
| Dell          | Latitude 5420               | [ea5ac72a44](https://linux-hardware.org/?probe=ea5ac72a44) | Mar 05, 2023 |
| Toshiba       | IS 1413G                    | [a655c49d8b](https://linux-hardware.org/?probe=a655c49d8b) | Mar 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [b73251069c](https://linux-hardware.org/?probe=b73251069c) | Mar 05, 2023 |
| HP            | ProBook 450 G1              | [ca5a019457](https://linux-hardware.org/?probe=ca5a019457) | Mar 04, 2023 |
| Apple         | MacBookPro9,2               | [ba908d3339](https://linux-hardware.org/?probe=ba908d3339) | Mar 04, 2023 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [26ca476e1a](https://linux-hardware.org/?probe=26ca476e1a) | Mar 04, 2023 |
| Dell          | System XPS L321X            | [24d0d12eca](https://linux-hardware.org/?probe=24d0d12eca) | Mar 04, 2023 |
| Lenovo        | ThinkPad X270 20HN001RUS    | [ccda7b2155](https://linux-hardware.org/?probe=ccda7b2155) | Mar 04, 2023 |
| Gigabyte      | AORUS 17 XE4                | [6f6750ee73](https://linux-hardware.org/?probe=6f6750ee73) | Mar 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [db92a5f137](https://linux-hardware.org/?probe=db92a5f137) | Mar 03, 2023 |
| HP            | EliteBook 8440p             | [9ce5a599cd](https://linux-hardware.org/?probe=9ce5a599cd) | Mar 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | [e73235d592](https://linux-hardware.org/?probe=e73235d592) | Mar 03, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [2c6ad91981](https://linux-hardware.org/?probe=2c6ad91981) | Mar 02, 2023 |
| Acer          | Swift SF314-54              | [62defb89e3](https://linux-hardware.org/?probe=62defb89e3) | Mar 02, 2023 |
| System76      | Lemur Pro                   | [e7ed83aaf7](https://linux-hardware.org/?probe=e7ed83aaf7) | Mar 01, 2023 |
| HP            | 15                          | [97985ac192](https://linux-hardware.org/?probe=97985ac192) | Mar 01, 2023 |
| HP            | EliteBook 830 G5            | [9abfe7631c](https://linux-hardware.org/?probe=9abfe7631c) | Mar 01, 2023 |
| ASUSTek       | X751LD                      | [46eecb2678](https://linux-hardware.org/?probe=46eecb2678) | Mar 01, 2023 |
| Dell          | Precision 3571              | [40348190de](https://linux-hardware.org/?probe=40348190de) | Mar 01, 2023 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [571d426262](https://linux-hardware.org/?probe=571d426262) | Mar 01, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [78ee2e145b](https://linux-hardware.org/?probe=78ee2e145b) | Mar 01, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [bd4fd4080d](https://linux-hardware.org/?probe=bd4fd4080d) | Mar 01, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [90d8927f0a](https://linux-hardware.org/?probe=90d8927f0a) | Mar 01, 2023 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [5aad25779a](https://linux-hardware.org/?probe=5aad25779a) | Feb 28, 2023 |
| Acer          | Aspire A515-57              | [6c511739eb](https://linux-hardware.org/?probe=6c511739eb) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HN001RUS    | [ff84200b75](https://linux-hardware.org/?probe=ff84200b75) | Feb 28, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [88745e1f03](https://linux-hardware.org/?probe=88745e1f03) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [357c1abb1d](https://linux-hardware.org/?probe=357c1abb1d) | Feb 27, 2023 |
| Razer         | Blade 15 Base Model (Ear... | [425567e8f3](https://linux-hardware.org/?probe=425567e8f3) | Feb 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | [bd62e34a09](https://linux-hardware.org/?probe=bd62e34a09) | Feb 27, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | [82a40f1881](https://linux-hardware.org/?probe=82a40f1881) | Feb 27, 2023 |
| Acer          | Aspire A515-56              | [97e3001416](https://linux-hardware.org/?probe=97e3001416) | Feb 26, 2023 |
| Dell          | XPS 13 7390                 | [2a8830034a](https://linux-hardware.org/?probe=2a8830034a) | Feb 26, 2023 |
| Acer          | Nitro AN515-58              | [1c93095718](https://linux-hardware.org/?probe=1c93095718) | Feb 26, 2023 |
| Sony          | VPCZ12V9R                   | [3014067c24](https://linux-hardware.org/?probe=3014067c24) | Feb 26, 2023 |
| GPU Compan... | GWTN141-10                  | [1550bec17e](https://linux-hardware.org/?probe=1550bec17e) | Feb 25, 2023 |
| GPU Compan... | GWTN141-10                  | [aa535b0731](https://linux-hardware.org/?probe=aa535b0731) | Feb 25, 2023 |
| Dell          | G7 7588                     | [82f1398a69](https://linux-hardware.org/?probe=82f1398a69) | Feb 25, 2023 |
| Alienware     | 15 R3                       | [72543030d5](https://linux-hardware.org/?probe=72543030d5) | Feb 25, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | [42b9d60137](https://linux-hardware.org/?probe=42b9d60137) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b5f840e593](https://linux-hardware.org/?probe=b5f840e593) | Feb 25, 2023 |
| System76      | Galago Pro                  | [3e4391562b](https://linux-hardware.org/?probe=3e4391562b) | Feb 25, 2023 |
| Packard Be... | EasyNote TS11HR             | [0a63352761](https://linux-hardware.org/?probe=0a63352761) | Feb 25, 2023 |
| Dell          | XPS 15 9500                 | [96e6c2c201](https://linux-hardware.org/?probe=96e6c2c201) | Feb 25, 2023 |
| Dell          | Latitude 3310               | [d989647d9d](https://linux-hardware.org/?probe=d989647d9d) | Feb 25, 2023 |
| Acer          | Aspire A515-56              | [517a6211c9](https://linux-hardware.org/?probe=517a6211c9) | Feb 24, 2023 |
| HP            | ProBook 450 G1              | [f7c4b009f1](https://linux-hardware.org/?probe=f7c4b009f1) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [297c37ec04](https://linux-hardware.org/?probe=297c37ec04) | Feb 24, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [2f561a23c3](https://linux-hardware.org/?probe=2f561a23c3) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [041c57ebe6](https://linux-hardware.org/?probe=041c57ebe6) | Feb 24, 2023 |
| Apple         | MacBookPro9,2               | [c591acd5d6](https://linux-hardware.org/?probe=c591acd5d6) | Feb 24, 2023 |
| Dell          | Inspiron 5423               | [7cf47f3118](https://linux-hardware.org/?probe=7cf47f3118) | Feb 23, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [00591dc764](https://linux-hardware.org/?probe=00591dc764) | Feb 23, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | [bb0d8e868d](https://linux-hardware.org/?probe=bb0d8e868d) | Feb 23, 2023 |
| Toshiba       | Satellite C855-1T5          | [8a96579c89](https://linux-hardware.org/?probe=8a96579c89) | Feb 23, 2023 |
| System76      | Gazelle                     | [609f452af9](https://linux-hardware.org/?probe=609f452af9) | Feb 23, 2023 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | [33a4731a5e](https://linux-hardware.org/?probe=33a4731a5e) | Feb 23, 2023 |
| Dell          | Latitude E7240              | [7f8278ff44](https://linux-hardware.org/?probe=7f8278ff44) | Feb 23, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [34016a67d9](https://linux-hardware.org/?probe=34016a67d9) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [312937f0d0](https://linux-hardware.org/?probe=312937f0d0) | Feb 22, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | [6ab727e8c0](https://linux-hardware.org/?probe=6ab727e8c0) | Feb 22, 2023 |
| Apple         | MacBookPro11,4              | [c4eab564b3](https://linux-hardware.org/?probe=c4eab564b3) | Feb 22, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [af2d2bd596](https://linux-hardware.org/?probe=af2d2bd596) | Feb 21, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [41b4e0957f](https://linux-hardware.org/?probe=41b4e0957f) | Feb 21, 2023 |
| HP            | EliteBook Folio 1040 G2     | [265018acd3](https://linux-hardware.org/?probe=265018acd3) | Feb 21, 2023 |
| Apple         | MacBookPro16,1              | [a5cff07fd8](https://linux-hardware.org/?probe=a5cff07fd8) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [022527aa4c](https://linux-hardware.org/?probe=022527aa4c) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [3b1afb00a2](https://linux-hardware.org/?probe=3b1afb00a2) | Feb 21, 2023 |
| Dell          | G15 5525                    | [63bd2ac7b9](https://linux-hardware.org/?probe=63bd2ac7b9) | Feb 21, 2023 |
| Acer          | Swift SF114-34              | [e9f5a9d293](https://linux-hardware.org/?probe=e9f5a9d293) | Feb 21, 2023 |
| Dell          | Precision M4800             | [b8e31b63ce](https://linux-hardware.org/?probe=b8e31b63ce) | Feb 20, 2023 |
| HP            | Laptop 14s-fq0xxx           | [0bc03f3b39](https://linux-hardware.org/?probe=0bc03f3b39) | Feb 20, 2023 |
| HP            | ProBook 450 G1              | [b5e8826f8c](https://linux-hardware.org/?probe=b5e8826f8c) | Feb 20, 2023 |
| Dell          | XPS 15 7590                 | [297b06716d](https://linux-hardware.org/?probe=297b06716d) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [d4fdbbf1ba](https://linux-hardware.org/?probe=d4fdbbf1ba) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [a11d164d69](https://linux-hardware.org/?probe=a11d164d69) | Feb 19, 2023 |
| Apple         | MacBook4,1                  | [2011c2060b](https://linux-hardware.org/?probe=2011c2060b) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [cc0e711862](https://linux-hardware.org/?probe=cc0e711862) | Feb 18, 2023 |
| HP            | 240 G6 Notebook PC          | [fc39dde214](https://linux-hardware.org/?probe=fc39dde214) | Feb 18, 2023 |
| Dell          | Latitude E7240              | [461873da2d](https://linux-hardware.org/?probe=461873da2d) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [5cc4ff8271](https://linux-hardware.org/?probe=5cc4ff8271) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [75f9e575b3](https://linux-hardware.org/?probe=75f9e575b3) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [f120e182a1](https://linux-hardware.org/?probe=f120e182a1) | Feb 17, 2023 |
| HUAWEI        | BOD-WXX9                    | [a56a788adf](https://linux-hardware.org/?probe=a56a788adf) | Feb 17, 2023 |
| HP            | EliteBook 830 G5            | [7ef47e7131](https://linux-hardware.org/?probe=7ef47e7131) | Feb 17, 2023 |
| HONOR         | NBR-WAX9                    | [b16ea0055d](https://linux-hardware.org/?probe=b16ea0055d) | Feb 17, 2023 |
| Dell          | Latitude E4200              | [18868db8a1](https://linux-hardware.org/?probe=18868db8a1) | Feb 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [91c566ccc9](https://linux-hardware.org/?probe=91c566ccc9) | Feb 16, 2023 |
| Apple         | MacBookPro9,2               | [e67f600749](https://linux-hardware.org/?probe=e67f600749) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | [2b0904349a](https://linux-hardware.org/?probe=2b0904349a) | Feb 16, 2023 |
| Lenovo        | G50-80 80E5                 | [64c385ee36](https://linux-hardware.org/?probe=64c385ee36) | Feb 16, 2023 |
| OriginPC      | Voyager a1600               | [9608c5afd5](https://linux-hardware.org/?probe=9608c5afd5) | Feb 16, 2023 |
| Google        | Blorb                       | [286353731c](https://linux-hardware.org/?probe=286353731c) | Feb 16, 2023 |
| Lenovo        | ThinkPad T530 2392AQU       | [1b89c43b58](https://linux-hardware.org/?probe=1b89c43b58) | Feb 16, 2023 |
| HP            | EliteBook 850 G2            | [ed0641ce38](https://linux-hardware.org/?probe=ed0641ce38) | Feb 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [74a61dff13](https://linux-hardware.org/?probe=74a61dff13) | Feb 15, 2023 |
| Apple         | MacBookPro12,1              | [bdb6e585b0](https://linux-hardware.org/?probe=bdb6e585b0) | Feb 15, 2023 |
| Lenovo        | ThinkPad T450s 20BWS14G0... | [5c4a26ada0](https://linux-hardware.org/?probe=5c4a26ada0) | Feb 14, 2023 |
| Dell          | Precision M3800             | [98b54858cb](https://linux-hardware.org/?probe=98b54858cb) | Feb 14, 2023 |
| Dell          | Inspiron 15 3511            | [1028ef9686](https://linux-hardware.org/?probe=1028ef9686) | Feb 14, 2023 |
| MSI           | Prestige 14Evo A11M         | [abeebd4312](https://linux-hardware.org/?probe=abeebd4312) | Feb 13, 2023 |
| Sony          | VPCEG27FM                   | [748a67669f](https://linux-hardware.org/?probe=748a67669f) | Feb 13, 2023 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | [a6af7624cd](https://linux-hardware.org/?probe=a6af7624cd) | Feb 13, 2023 |
| Samsung       | 730U3E/740U3E               | [91ac69dfa1](https://linux-hardware.org/?probe=91ac69dfa1) | Feb 13, 2023 |
| Lenovo        | ThinkPad T410 2522G76       | [b15d4051cd](https://linux-hardware.org/?probe=b15d4051cd) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [d38212ee96](https://linux-hardware.org/?probe=d38212ee96) | Feb 13, 2023 |
| Apple         | MacBookPro11,2              | [2314b98760](https://linux-hardware.org/?probe=2314b98760) | Feb 12, 2023 |
| Apple         | MacBookPro12,1              | [139b92595a](https://linux-hardware.org/?probe=139b92595a) | Feb 12, 2023 |
| Haier         | GG1500A                     | [4c4598157f](https://linux-hardware.org/?probe=4c4598157f) | Feb 12, 2023 |
| Dell          | Latitude XT2                | [9b98bf4722](https://linux-hardware.org/?probe=9b98bf4722) | Feb 12, 2023 |
| Dell          | Precision M4700             | [1a44cb5ef9](https://linux-hardware.org/?probe=1a44cb5ef9) | Feb 11, 2023 |
| Apple         | MacBookPro11,1              | [fb407bfc13](https://linux-hardware.org/?probe=fb407bfc13) | Feb 11, 2023 |
| Lenovo        | ThinkPad T470s 20HFCT01W... | [322a9d340e](https://linux-hardware.org/?probe=322a9d340e) | Feb 11, 2023 |
| Acer          | Aspire 5742G                | [1315dbeb6c](https://linux-hardware.org/?probe=1315dbeb6c) | Feb 11, 2023 |
| Lenovo        | G50-45 80E3                 | [ab07f075d8](https://linux-hardware.org/?probe=ab07f075d8) | Feb 11, 2023 |
| Apple         | MacBook8,1                  | [2f1c5b90a8](https://linux-hardware.org/?probe=2f1c5b90a8) | Feb 11, 2023 |
| Lenovo        | G50-45 80E3                 | [24cb179c5a](https://linux-hardware.org/?probe=24cb179c5a) | Feb 11, 2023 |
| MSI           | GF63 Thin 9RCX              | [9cbcfdd748](https://linux-hardware.org/?probe=9cbcfdd748) | Feb 10, 2023 |
| Dell          | Latitude 5290 2-in-1        | [cb03f9e72e](https://linux-hardware.org/?probe=cb03f9e72e) | Feb 10, 2023 |
| Dell          | G15 5520                    | [121b06f3cc](https://linux-hardware.org/?probe=121b06f3cc) | Feb 10, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [d0cc5f80fc](https://linux-hardware.org/?probe=d0cc5f80fc) | Feb 09, 2023 |
| HP            | EliteBook 840 G5            | [39dbdb0fa9](https://linux-hardware.org/?probe=39dbdb0fa9) | Feb 09, 2023 |
| Lenovo        | ThinkPad T450 20BUA0PNUK    | [8837c33007](https://linux-hardware.org/?probe=8837c33007) | Feb 09, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [74dd2176ff](https://linux-hardware.org/?probe=74dd2176ff) | Feb 09, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [93afe9ddeb](https://linux-hardware.org/?probe=93afe9ddeb) | Feb 09, 2023 |
| Dell          | Inspiron 3576               | [a025641dfc](https://linux-hardware.org/?probe=a025641dfc) | Feb 09, 2023 |
| Acer          | Aspire A315-59              | [edc6b0a3af](https://linux-hardware.org/?probe=edc6b0a3af) | Feb 09, 2023 |
| Dell          | XPS 13 9360                 | [db7e89340f](https://linux-hardware.org/?probe=db7e89340f) | Feb 09, 2023 |
| System76      | Lemur Pro                   | [94cf78a9d9](https://linux-hardware.org/?probe=94cf78a9d9) | Feb 08, 2023 |
| Dell          | G15 5520                    | [7f4d36cea1](https://linux-hardware.org/?probe=7f4d36cea1) | Feb 08, 2023 |
| HP            | EliteBook 830 G5            | [5554154df2](https://linux-hardware.org/?probe=5554154df2) | Feb 07, 2023 |
| Dell          | System XPS L702X            | [cdbc3578d0](https://linux-hardware.org/?probe=cdbc3578d0) | Feb 07, 2023 |
| Alienware     | m15 R7                      | [254ab40fcf](https://linux-hardware.org/?probe=254ab40fcf) | Feb 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [f6c24b1ea8](https://linux-hardware.org/?probe=f6c24b1ea8) | Feb 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [50af8c9fe6](https://linux-hardware.org/?probe=50af8c9fe6) | Feb 06, 2023 |
| ASUSTek       | UX430UNR                    | [96d7a1938a](https://linux-hardware.org/?probe=96d7a1938a) | Feb 06, 2023 |
| Acer          | Swift SF114-34              | [28aad1fae5](https://linux-hardware.org/?probe=28aad1fae5) | Feb 06, 2023 |
| ASUSTek       | X751LD                      | [12d5592082](https://linux-hardware.org/?probe=12d5592082) | Feb 06, 2023 |
| Notebook      | NJ50_70CU                   | [c0c9951f8d](https://linux-hardware.org/?probe=c0c9951f8d) | Feb 05, 2023 |
| Dell          | Latitude 7380               | [7b9d4ef8b4](https://linux-hardware.org/?probe=7b9d4ef8b4) | Feb 05, 2023 |
| Acer          | Swift SF114-34              | [ea8a0e0617](https://linux-hardware.org/?probe=ea8a0e0617) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | [5c2bd1284d](https://linux-hardware.org/?probe=5c2bd1284d) | Feb 05, 2023 |
| Alienware     | 17 R5                       | [7f5f8bdb1f](https://linux-hardware.org/?probe=7f5f8bdb1f) | Feb 05, 2023 |
| Fujitsu       | LIFEBOOK T902               | [9c92a1772d](https://linux-hardware.org/?probe=9c92a1772d) | Feb 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d95f28d447](https://linux-hardware.org/?probe=d95f28d447) | Feb 05, 2023 |
| Apple         | MacBookPro5,4               | [a705eb3101](https://linux-hardware.org/?probe=a705eb3101) | Feb 05, 2023 |
| Apple         | MacBookPro5,4               | [7a80b2d6d7](https://linux-hardware.org/?probe=7a80b2d6d7) | Feb 05, 2023 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [e5e8537cef](https://linux-hardware.org/?probe=e5e8537cef) | Feb 05, 2023 |
| HP            | Laptop 15-bw0xx             | [0cb9ba3cf9](https://linux-hardware.org/?probe=0cb9ba3cf9) | Feb 05, 2023 |
| ASUSTek       | X751LD                      | [13948b75ae](https://linux-hardware.org/?probe=13948b75ae) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | [b5ac9ebd7c](https://linux-hardware.org/?probe=b5ac9ebd7c) | Feb 05, 2023 |
| HP            | Notebook                    | [0ad701667d](https://linux-hardware.org/?probe=0ad701667d) | Feb 05, 2023 |
| HP            | Notebook                    | [37f601798c](https://linux-hardware.org/?probe=37f601798c) | Feb 05, 2023 |
| Dell          | G15 5515                    | [7418ca82c1](https://linux-hardware.org/?probe=7418ca82c1) | Feb 04, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [fd2b67e6ab](https://linux-hardware.org/?probe=fd2b67e6ab) | Feb 04, 2023 |
| Dell          | Latitude 3520               | [ce594f431c](https://linux-hardware.org/?probe=ce594f431c) | Feb 04, 2023 |
| Acer          | Aspire A515-51G             | [149465f225](https://linux-hardware.org/?probe=149465f225) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [448d3800ac](https://linux-hardware.org/?probe=448d3800ac) | Feb 04, 2023 |
| Toshiba       | Satellite C855-233          | [8fc7835588](https://linux-hardware.org/?probe=8fc7835588) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN0017US     | [43c5ab14ec](https://linux-hardware.org/?probe=43c5ab14ec) | Feb 03, 2023 |
| Dell          | Latitude E7240              | [da54499919](https://linux-hardware.org/?probe=da54499919) | Feb 03, 2023 |
| Haier         | GG1500A                     | [b54ce000d3](https://linux-hardware.org/?probe=b54ce000d3) | Feb 03, 2023 |
| Star Labs     | StarBook                    | [98ad1bcab4](https://linux-hardware.org/?probe=98ad1bcab4) | Feb 03, 2023 |
| Star Labs     | StarBook                    | [5fe174bdd1](https://linux-hardware.org/?probe=5fe174bdd1) | Feb 03, 2023 |
| Acer          | Aspire A315-59              | [704c6e370c](https://linux-hardware.org/?probe=704c6e370c) | Feb 03, 2023 |
| Timi          | RedmiBook Pro 15S           | [8a1c423c67](https://linux-hardware.org/?probe=8a1c423c67) | Feb 03, 2023 |
| Apple         | MacBookPro8,1               | [c441c159c1](https://linux-hardware.org/?probe=c441c159c1) | Feb 03, 2023 |
| HP            | Laptop 15-db1xxx            | [8944f22b68](https://linux-hardware.org/?probe=8944f22b68) | Feb 02, 2023 |
| Acer          | Swift SF114-32              | [96b48bebd2](https://linux-hardware.org/?probe=96b48bebd2) | Feb 02, 2023 |
| Dell          | Inspiron 3584               | [4bfcbe7c13](https://linux-hardware.org/?probe=4bfcbe7c13) | Feb 02, 2023 |
| Dell          | Precision 3571              | [8ee8f6f768](https://linux-hardware.org/?probe=8ee8f6f768) | Feb 02, 2023 |
| Dell          | Precision 3571              | [9453f26568](https://linux-hardware.org/?probe=9453f26568) | Feb 02, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [8db619716a](https://linux-hardware.org/?probe=8db619716a) | Feb 02, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [7019bd88e0](https://linux-hardware.org/?probe=7019bd88e0) | Feb 01, 2023 |
| HP            | Pavilion 15                 | [946fec8f7d](https://linux-hardware.org/?probe=946fec8f7d) | Feb 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [6294616fc6](https://linux-hardware.org/?probe=6294616fc6) | Feb 01, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [6ed194a014](https://linux-hardware.org/?probe=6ed194a014) | Feb 01, 2023 |
| Timi          | Mi NoteBook Ultra           | [d897ec0114](https://linux-hardware.org/?probe=d897ec0114) | Feb 01, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [c4869ecf2c](https://linux-hardware.org/?probe=c4869ecf2c) | Feb 01, 2023 |
| Acer          | Predator PH517-61           | [b16ddc31d8](https://linux-hardware.org/?probe=b16ddc31d8) | Feb 01, 2023 |
| Dell          | Latitude E7240              | [fe655eca77](https://linux-hardware.org/?probe=fe655eca77) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [3803fd2405](https://linux-hardware.org/?probe=3803fd2405) | Jan 31, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [db8bdbd72b](https://linux-hardware.org/?probe=db8bdbd72b) | Jan 31, 2023 |
| Dell          | Inspiron 7400               | [a6b124fd34](https://linux-hardware.org/?probe=a6b124fd34) | Jan 31, 2023 |
| Apple         | MacBookPro12,1              | [228ab40738](https://linux-hardware.org/?probe=228ab40738) | Jan 31, 2023 |
| HP            | Notebook                    | [82d58b21c4](https://linux-hardware.org/?probe=82d58b21c4) | Jan 31, 2023 |
| HP            | ZBook Studio G3             | [506988f4ba](https://linux-hardware.org/?probe=506988f4ba) | Jan 31, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | [7636aeaacc](https://linux-hardware.org/?probe=7636aeaacc) | Jan 31, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [230b38f8e6](https://linux-hardware.org/?probe=230b38f8e6) | Jan 31, 2023 |
| Acer          | Swift SF114-32              | [82d317899e](https://linux-hardware.org/?probe=82d317899e) | Jan 31, 2023 |
| Dell          | XPS 15 9500                 | [6a0af9dbcb](https://linux-hardware.org/?probe=6a0af9dbcb) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [2474b4641c](https://linux-hardware.org/?probe=2474b4641c) | Jan 30, 2023 |
| GPU Compan... | GWTN141-10                  | [f012d6d71c](https://linux-hardware.org/?probe=f012d6d71c) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | [d4aec33c44](https://linux-hardware.org/?probe=d4aec33c44) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | [58e7588538](https://linux-hardware.org/?probe=58e7588538) | Jan 30, 2023 |
| Acer          | Swift SF114-32              | [1228d6d0f7](https://linux-hardware.org/?probe=1228d6d0f7) | Jan 30, 2023 |
| Dell          | G15 5511                    | [36214ba4de](https://linux-hardware.org/?probe=36214ba4de) | Jan 30, 2023 |
| Dell          | Latitude E7240              | [a1f713f6e3](https://linux-hardware.org/?probe=a1f713f6e3) | Jan 30, 2023 |
| Avell High... | B11 MOB                     | [dd9d29ddc7](https://linux-hardware.org/?probe=dd9d29ddc7) | Jan 30, 2023 |
| Acer          | Aspire A515-45              | [42405a6a0c](https://linux-hardware.org/?probe=42405a6a0c) | Jan 30, 2023 |
| HP            | Pavilion dv6                | [0966ae419c](https://linux-hardware.org/?probe=0966ae419c) | Jan 30, 2023 |
| ASUSTek       | X555LD                      | [b70d834fe5](https://linux-hardware.org/?probe=b70d834fe5) | Jan 29, 2023 |
| Dell          | G15 5515                    | [1be125c3cd](https://linux-hardware.org/?probe=1be125c3cd) | Jan 29, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [ff3381fe1a](https://linux-hardware.org/?probe=ff3381fe1a) | Jan 28, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [c6770f3828](https://linux-hardware.org/?probe=c6770f3828) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [ec9bed5b5d](https://linux-hardware.org/?probe=ec9bed5b5d) | Jan 28, 2023 |
| ASUSTek       | ET2321I                     | [dbb162975e](https://linux-hardware.org/?probe=dbb162975e) | Jan 28, 2023 |
| MSI           | Vector GP76 12UHSO          | [549b690251](https://linux-hardware.org/?probe=549b690251) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [e225ce26a1](https://linux-hardware.org/?probe=e225ce26a1) | Jan 28, 2023 |
| MSI           | Vector GP76 12UHSO          | [cbbd1d3e3e](https://linux-hardware.org/?probe=cbbd1d3e3e) | Jan 28, 2023 |
| Dell          | XPS 13 9305                 | [684b829dbb](https://linux-hardware.org/?probe=684b829dbb) | Jan 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ce2955973a](https://linux-hardware.org/?probe=ce2955973a) | Jan 27, 2023 |
| System76      | Lemur Pro                   | [40c5731c48](https://linux-hardware.org/?probe=40c5731c48) | Jan 27, 2023 |
| Clevo         | W150HNM/W170HN              | [63709a14ca](https://linux-hardware.org/?probe=63709a14ca) | Jan 27, 2023 |
| Dell          | Latitude E7240              | [d88cdedff3](https://linux-hardware.org/?probe=d88cdedff3) | Jan 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [df04ffbd50](https://linux-hardware.org/?probe=df04ffbd50) | Jan 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [b2ffc58bb1](https://linux-hardware.org/?probe=b2ffc58bb1) | Jan 26, 2023 |
| Dell          | G3 3590                     | [8a7e4e4db0](https://linux-hardware.org/?probe=8a7e4e4db0) | Jan 26, 2023 |
| System76      | Lemur Pro                   | [097cd4c9f8](https://linux-hardware.org/?probe=097cd4c9f8) | Jan 26, 2023 |
| Gigabyte      | A5 K1                       | [e0771eb5f6](https://linux-hardware.org/?probe=e0771eb5f6) | Jan 25, 2023 |
| HP            | ProBook 6550b               | [c7983e417c](https://linux-hardware.org/?probe=c7983e417c) | Jan 25, 2023 |
| Timi          | RedmiBook Pro 15S           | [4629dc82aa](https://linux-hardware.org/?probe=4629dc82aa) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [bc56140257](https://linux-hardware.org/?probe=bc56140257) | Jan 25, 2023 |
| Gigabyte      | A5 K1                       | [d5e00555ca](https://linux-hardware.org/?probe=d5e00555ca) | Jan 25, 2023 |
| Dell          | Inspiron 13-7353            | [5ebcba8c52](https://linux-hardware.org/?probe=5ebcba8c52) | Jan 25, 2023 |
| Dell          | Latitude E7240              | [2d488752b6](https://linux-hardware.org/?probe=2d488752b6) | Jan 25, 2023 |
| Dell          | System Inspiron N7110       | [935a295b28](https://linux-hardware.org/?probe=935a295b28) | Jan 25, 2023 |
| ASUSTek       | N551JW                      | [9694a30eff](https://linux-hardware.org/?probe=9694a30eff) | Jan 25, 2023 |
| Dell          | Latitude E7240              | [9d44efa2f9](https://linux-hardware.org/?probe=9d44efa2f9) | Jan 24, 2023 |
| Acer          | Swift SFA16-41              | [1c05334105](https://linux-hardware.org/?probe=1c05334105) | Jan 24, 2023 |
| LG Electro... | 17Z90Q-K.AAC7U1             | [73a0023203](https://linux-hardware.org/?probe=73a0023203) | Jan 24, 2023 |
| Google        | Link                        | [5c44e38153](https://linux-hardware.org/?probe=5c44e38153) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [f6e09cc9fb](https://linux-hardware.org/?probe=f6e09cc9fb) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [306e6ae925](https://linux-hardware.org/?probe=306e6ae925) | Jan 23, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [821e7b4330](https://linux-hardware.org/?probe=821e7b4330) | Jan 22, 2023 |
| Purism        | Librem 15 v3                | [fcb1d44df6](https://linux-hardware.org/?probe=fcb1d44df6) | Jan 22, 2023 |
| Dell          | Latitude E5470              | [1a2810f035](https://linux-hardware.org/?probe=1a2810f035) | Jan 22, 2023 |
| HP            | Notebook                    | [57bf6826ef](https://linux-hardware.org/?probe=57bf6826ef) | Jan 22, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | [0729d0a10f](https://linux-hardware.org/?probe=0729d0a10f) | Jan 22, 2023 |
| Dell          | XPS 13 9350                 | [223ab1f016](https://linux-hardware.org/?probe=223ab1f016) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9b3b21f5b7](https://linux-hardware.org/?probe=9b3b21f5b7) | Jan 21, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [22d9f43ef5](https://linux-hardware.org/?probe=22d9f43ef5) | Jan 21, 2023 |
| Razer x La... | TensorBook (late 2021)      | [9062d4274f](https://linux-hardware.org/?probe=9062d4274f) | Jan 21, 2023 |
| Dell          | Latitude 5300               | [e8c4218110](https://linux-hardware.org/?probe=e8c4218110) | Jan 21, 2023 |
| Lenovo        | ThinkPad T530 23943J8       | [1da6722b35](https://linux-hardware.org/?probe=1da6722b35) | Jan 21, 2023 |
| Dell          | Inspiron 5505               | [9a17165647](https://linux-hardware.org/?probe=9a17165647) | Jan 20, 2023 |
| Dell          | Inspiron 5505               | [e1003a85c9](https://linux-hardware.org/?probe=e1003a85c9) | Jan 20, 2023 |
| ASUSTek       | X442URR                     | [6104ee1f65](https://linux-hardware.org/?probe=6104ee1f65) | Jan 20, 2023 |
| Dell          | Latitude E7240              | [a4e01b187f](https://linux-hardware.org/?probe=a4e01b187f) | Jan 20, 2023 |
| HP            | Laptop 15-bw0xx             | [0bf7ea6726](https://linux-hardware.org/?probe=0bf7ea6726) | Jan 20, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [c1169d55de](https://linux-hardware.org/?probe=c1169d55de) | Jan 19, 2023 |
| Dell          | Latitude E7240              | [475187029d](https://linux-hardware.org/?probe=475187029d) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [edc36777f0](https://linux-hardware.org/?probe=edc36777f0) | Jan 19, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [b318baed4f](https://linux-hardware.org/?probe=b318baed4f) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [eddf4927eb](https://linux-hardware.org/?probe=eddf4927eb) | Jan 19, 2023 |
| Razer         | Blade                       | [b3f154ac11](https://linux-hardware.org/?probe=b3f154ac11) | Jan 19, 2023 |
| Dell          | G5 5590                     | [01888c3049](https://linux-hardware.org/?probe=01888c3049) | Jan 19, 2023 |
| Dell          | Latitude E6540              | [440b0eec1c](https://linux-hardware.org/?probe=440b0eec1c) | Jan 18, 2023 |
| MSI           | Alpha 15 A3DDK              | [832ee11e43](https://linux-hardware.org/?probe=832ee11e43) | Jan 18, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [81d4385a14](https://linux-hardware.org/?probe=81d4385a14) | Jan 18, 2023 |
| Lenovo        | ThinkPad T560 20FH001QUS    | [933f67b6b5](https://linux-hardware.org/?probe=933f67b6b5) | Jan 18, 2023 |
| Dell          | Precision 7670              | [5c70243651](https://linux-hardware.org/?probe=5c70243651) | Jan 18, 2023 |
| Lenovo        | ThinkPad T560 20FH001QUS    | [48a56bd8c2](https://linux-hardware.org/?probe=48a56bd8c2) | Jan 18, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [ac28c1fba4](https://linux-hardware.org/?probe=ac28c1fba4) | Jan 18, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [45e2d0fb2d](https://linux-hardware.org/?probe=45e2d0fb2d) | Jan 18, 2023 |
| Dell          | Latitude E5440              | [eb945eac4e](https://linux-hardware.org/?probe=eb945eac4e) | Jan 18, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [8bf0f8c8fe](https://linux-hardware.org/?probe=8bf0f8c8fe) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [18d3c84771](https://linux-hardware.org/?probe=18d3c84771) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [bd0bc47120](https://linux-hardware.org/?probe=bd0bc47120) | Jan 17, 2023 |
| Framework     | Laptop                      | [e94774a411](https://linux-hardware.org/?probe=e94774a411) | Jan 17, 2023 |
| Acer          | Aspire 5625G                | [244d8473fc](https://linux-hardware.org/?probe=244d8473fc) | Jan 16, 2023 |
| Dell          | Latitude E7240              | [dc47f005d6](https://linux-hardware.org/?probe=dc47f005d6) | Jan 16, 2023 |
| Lenovo        | IdeaPad Y570 0862           | [8c43e56714](https://linux-hardware.org/?probe=8c43e56714) | Jan 16, 2023 |
| Chuwi         | GemiBook Pro                | [b51cc41cb3](https://linux-hardware.org/?probe=b51cc41cb3) | Jan 16, 2023 |
| System76      | Lemur Pro                   | [fde9d32359](https://linux-hardware.org/?probe=fde9d32359) | Jan 16, 2023 |
| Apple         | MacBook8,1                  | [64b089dfb7](https://linux-hardware.org/?probe=64b089dfb7) | Jan 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [db57593b81](https://linux-hardware.org/?probe=db57593b81) | Jan 14, 2023 |
| MSI           | Bravo 15 B5DD               | [ffb8653d34](https://linux-hardware.org/?probe=ffb8653d34) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [76f54ae84c](https://linux-hardware.org/?probe=76f54ae84c) | Jan 14, 2023 |
| Dell          | Precision 3571              | [c71e32c6ea](https://linux-hardware.org/?probe=c71e32c6ea) | Jan 14, 2023 |
| Acer          | Predator PT315-52           | [149941b52c](https://linux-hardware.org/?probe=149941b52c) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [9eed89d744](https://linux-hardware.org/?probe=9eed89d744) | Jan 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [d10834c7df](https://linux-hardware.org/?probe=d10834c7df) | Jan 14, 2023 |
| System76      | Oryx Pro                    | [da1374fa1c](https://linux-hardware.org/?probe=da1374fa1c) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [ed7ff7569c](https://linux-hardware.org/?probe=ed7ff7569c) | Jan 14, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [2860788f11](https://linux-hardware.org/?probe=2860788f11) | Jan 14, 2023 |
| HONOR         | NMH-WCX9                    | [10a9c33aed](https://linux-hardware.org/?probe=10a9c33aed) | Jan 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [362d8c4594](https://linux-hardware.org/?probe=362d8c4594) | Jan 13, 2023 |
| Dell          | Latitude 5300               | [148745c883](https://linux-hardware.org/?probe=148745c883) | Jan 13, 2023 |
| HP            | EliteBook 8570w             | [84035db95c](https://linux-hardware.org/?probe=84035db95c) | Jan 13, 2023 |
| Lenovo        | ThinkPad T500 2081CTO       | [96a079dbf8](https://linux-hardware.org/?probe=96a079dbf8) | Jan 13, 2023 |
| Lenovo        | ThinkPad T500 2081CTO       | [53b39e47e9](https://linux-hardware.org/?probe=53b39e47e9) | Jan 13, 2023 |
| Lenovo        | ThinkPad T460 20FMS2BM00    | [afefa18c04](https://linux-hardware.org/?probe=afefa18c04) | Jan 12, 2023 |
| HP            | Dev One Notebook PC         | [f7304c0af2](https://linux-hardware.org/?probe=f7304c0af2) | Jan 12, 2023 |
| Samsung       | 270E5J/2570EJ               | [22f9a03d68](https://linux-hardware.org/?probe=22f9a03d68) | Jan 12, 2023 |
| HP            | EliteBook 840 G5            | [a62af2c5a8](https://linux-hardware.org/?probe=a62af2c5a8) | Jan 11, 2023 |
| Dell          | Latitude E7240              | [93d832d08f](https://linux-hardware.org/?probe=93d832d08f) | Jan 11, 2023 |
| Lenovo        | IdeaPad Y570 20091          | [3538dd1b8a](https://linux-hardware.org/?probe=3538dd1b8a) | Jan 11, 2023 |
| Acer          | TravelMate P245-M           | [1722e41c8d](https://linux-hardware.org/?probe=1722e41c8d) | Jan 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [0f1f6b2662](https://linux-hardware.org/?probe=0f1f6b2662) | Jan 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a2363c6939](https://linux-hardware.org/?probe=a2363c6939) | Jan 11, 2023 |
| Acer          | Swift SF314-56              | [456445a93c](https://linux-hardware.org/?probe=456445a93c) | Jan 10, 2023 |
| Dell          | Latitude E7240              | [83a785903b](https://linux-hardware.org/?probe=83a785903b) | Jan 10, 2023 |
| HP            | EliteBook 840 G5            | [0eb6418a53](https://linux-hardware.org/?probe=0eb6418a53) | Jan 10, 2023 |
| HP            | OMEN by Laptop              | [a365222a35](https://linux-hardware.org/?probe=a365222a35) | Jan 09, 2023 |
| Razer x La... | TensorBook (late 2021)      | [d798473e75](https://linux-hardware.org/?probe=d798473e75) | Jan 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [e384aea51e](https://linux-hardware.org/?probe=e384aea51e) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [1829eed17a](https://linux-hardware.org/?probe=1829eed17a) | Jan 09, 2023 |
| Dell          | Latitude E7240              | [c191d76ac2](https://linux-hardware.org/?probe=c191d76ac2) | Jan 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [07cc23f1cd](https://linux-hardware.org/?probe=07cc23f1cd) | Jan 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d784655474](https://linux-hardware.org/?probe=d784655474) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | [7e17526b20](https://linux-hardware.org/?probe=7e17526b20) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | [698649c9ae](https://linux-hardware.org/?probe=698649c9ae) | Jan 08, 2023 |
| Dell          | Latitude E7240              | [c7cf2afdd9](https://linux-hardware.org/?probe=c7cf2afdd9) | Jan 07, 2023 |
| HP            | ENVY dv6                    | [2a01900cb1](https://linux-hardware.org/?probe=2a01900cb1) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [f191d63ace](https://linux-hardware.org/?probe=f191d63ace) | Jan 07, 2023 |
| Dell          | Latitude E7240              | [7018e90a09](https://linux-hardware.org/?probe=7018e90a09) | Jan 07, 2023 |
| System76      | Bonobo WS                   | [afb9abd3c6](https://linux-hardware.org/?probe=afb9abd3c6) | Jan 07, 2023 |
| Dell          | Latitude E7240              | [d4dc080444](https://linux-hardware.org/?probe=d4dc080444) | Jan 07, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [ab9f1d1812](https://linux-hardware.org/?probe=ab9f1d1812) | Jan 07, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [bf425a41f8](https://linux-hardware.org/?probe=bf425a41f8) | Jan 07, 2023 |
| Lenovo        | G580 20157                  | [63bc1e725c](https://linux-hardware.org/?probe=63bc1e725c) | Jan 07, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [43f6676d9d](https://linux-hardware.org/?probe=43f6676d9d) | Jan 06, 2023 |
| Dell          | Latitude 7520               | [f4f253a52b](https://linux-hardware.org/?probe=f4f253a52b) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [67f40c78ec](https://linux-hardware.org/?probe=67f40c78ec) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [58f2e834d8](https://linux-hardware.org/?probe=58f2e834d8) | Jan 06, 2023 |
| Dell          | Precision M4700             | [414d8c4701](https://linux-hardware.org/?probe=414d8c4701) | Jan 06, 2023 |
| Dell          | Latitude E7240              | [b00208bba7](https://linux-hardware.org/?probe=b00208bba7) | Jan 06, 2023 |
| Dell          | Latitude E7240              | [6eae9dc932](https://linux-hardware.org/?probe=6eae9dc932) | Jan 05, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [7acb37a2f5](https://linux-hardware.org/?probe=7acb37a2f5) | Jan 05, 2023 |
| HP            | ZBook Power 15.6 inch G8... | [28eb8d09fa](https://linux-hardware.org/?probe=28eb8d09fa) | Jan 05, 2023 |
| Acer          | Aspire 7745G                | [4f54cd1f61](https://linux-hardware.org/?probe=4f54cd1f61) | Jan 05, 2023 |
| Acer          | Aspire 7745G                | [0393900e99](https://linux-hardware.org/?probe=0393900e99) | Jan 05, 2023 |
| System76      | Gazelle                     | [b603d1ecc7](https://linux-hardware.org/?probe=b603d1ecc7) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | [8f42c7bc8c](https://linux-hardware.org/?probe=8f42c7bc8c) | Jan 04, 2023 |
| Datto         | Unknown                     | [e8c9c2e91f](https://linux-hardware.org/?probe=e8c9c2e91f) | Jan 04, 2023 |
| Dell          | XPS 13 9300                 | [7b1ce41c16](https://linux-hardware.org/?probe=7b1ce41c16) | Jan 03, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [f6d1d35842](https://linux-hardware.org/?probe=f6d1d35842) | Jan 02, 2023 |
| Panasonic     | FZ55-1                      | [b09d64c936](https://linux-hardware.org/?probe=b09d64c936) | Jan 02, 2023 |
| Fujitsu       | FMVNS6C3                    | [49d8591166](https://linux-hardware.org/?probe=49d8591166) | Jan 02, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [1490ccc480](https://linux-hardware.org/?probe=1490ccc480) | Jan 02, 2023 |
| Dell          | Latitude E7240              | [ccf48432e0](https://linux-hardware.org/?probe=ccf48432e0) | Jan 02, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [5e52308407](https://linux-hardware.org/?probe=5e52308407) | Jan 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [d841c27fe1](https://linux-hardware.org/?probe=d841c27fe1) | Jan 02, 2023 |
| ASUSTek       | UX310UQK                    | [79baf6f82a](https://linux-hardware.org/?probe=79baf6f82a) | Jan 01, 2023 |
| Dell          | Latitude E7270              | [09f72d101d](https://linux-hardware.org/?probe=09f72d101d) | Jan 01, 2023 |
| Dell          | XPS 9320                    | [28342f1b5c](https://linux-hardware.org/?probe=28342f1b5c) | Jan 01, 2023 |
| HP            | ZBook 15 G3                 | [a53517f382](https://linux-hardware.org/?probe=a53517f382) | Jan 01, 2023 |
| Dell          | XPS 9320                    | [4ef3eb6975](https://linux-hardware.org/?probe=4ef3eb6975) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [9f2441851f](https://linux-hardware.org/?probe=9f2441851f) | Dec 31, 2022 |
| HP            | EliteBook 8740w (WH274UT... | [e42d4e66a0](https://linux-hardware.org/?probe=e42d4e66a0) | Dec 31, 2022 |
| MSI           | GE60 2OC\2OE                | [c307379c36](https://linux-hardware.org/?probe=c307379c36) | Dec 30, 2022 |
| Dell          | G3 3500                     | [6be65a4ee5](https://linux-hardware.org/?probe=6be65a4ee5) | Dec 30, 2022 |
| Lenovo        | Z50-70 20354                | [29984f68c6](https://linux-hardware.org/?probe=29984f68c6) | Dec 30, 2022 |
| Apple         | MacBookPro7,1               | [db4379ed1e](https://linux-hardware.org/?probe=db4379ed1e) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3f1ca6740d](https://linux-hardware.org/?probe=3f1ca6740d) | Dec 30, 2022 |
| Dell          | Latitude E7240              | [5f83c8f4ad](https://linux-hardware.org/?probe=5f83c8f4ad) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [d048930c78](https://linux-hardware.org/?probe=d048930c78) | Dec 30, 2022 |
| Dell          | G5 5590                     | [dada63bf04](https://linux-hardware.org/?probe=dada63bf04) | Dec 30, 2022 |
| HP            | Pavilion 15                 | [956866bbdd](https://linux-hardware.org/?probe=956866bbdd) | Dec 29, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [aa2aad674b](https://linux-hardware.org/?probe=aa2aad674b) | Dec 29, 2022 |
| Lenovo        | ThinkPad W510 4389W14       | [c83a9ac8a9](https://linux-hardware.org/?probe=c83a9ac8a9) | Dec 29, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [467a749806](https://linux-hardware.org/?probe=467a749806) | Dec 29, 2022 |
| System76      | Lemur Pro                   | [0a61e4fe8d](https://linux-hardware.org/?probe=0a61e4fe8d) | Dec 29, 2022 |
| HP            | ENVY dv7                    | [97e029af78](https://linux-hardware.org/?probe=97e029af78) | Dec 29, 2022 |
| Apple         | MacBookPro14,1              | [2bd4899c8a](https://linux-hardware.org/?probe=2bd4899c8a) | Dec 29, 2022 |
| Apple         | MacBookPro14,1              | [919cfc2c9c](https://linux-hardware.org/?probe=919cfc2c9c) | Dec 29, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [f2ea0a18c8](https://linux-hardware.org/?probe=f2ea0a18c8) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [2e62e57e1c](https://linux-hardware.org/?probe=2e62e57e1c) | Dec 28, 2022 |
| ASUSTek       | P453UA                      | [0bf89f0f8f](https://linux-hardware.org/?probe=0bf89f0f8f) | Dec 28, 2022 |
| Lenovo        | Y50-70 20378                | [fe7926d39a](https://linux-hardware.org/?probe=fe7926d39a) | Dec 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c844147ffd](https://linux-hardware.org/?probe=c844147ffd) | Dec 28, 2022 |
| Alienware     | M11x R2                     | [a0da72bec0](https://linux-hardware.org/?probe=a0da72bec0) | Dec 28, 2022 |
| Dell          | Inspiron 5505               | [ba2d75cfa7](https://linux-hardware.org/?probe=ba2d75cfa7) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [9cc79e51c0](https://linux-hardware.org/?probe=9cc79e51c0) | Dec 28, 2022 |
| HUAWEI        | HVY-WXX9                    | [069f0917d6](https://linux-hardware.org/?probe=069f0917d6) | Dec 28, 2022 |
| Apple         | MacBookPro8,2               | [e4255e8ed7](https://linux-hardware.org/?probe=e4255e8ed7) | Dec 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6a2f859c67](https://linux-hardware.org/?probe=6a2f859c67) | Dec 27, 2022 |
| Acer          | Aspire A515-57              | [470c8d54ba](https://linux-hardware.org/?probe=470c8d54ba) | Dec 27, 2022 |
| Apple         | MacBookPro8,2               | [c62b37d15c](https://linux-hardware.org/?probe=c62b37d15c) | Dec 27, 2022 |
| Acer          | Aspire A515-57              | [c0a659dbb1](https://linux-hardware.org/?probe=c0a659dbb1) | Dec 27, 2022 |
| Dell          | XPS 15 9500                 | [d1d8257c05](https://linux-hardware.org/?probe=d1d8257c05) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [2195143f19](https://linux-hardware.org/?probe=2195143f19) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [73e9da47ae](https://linux-hardware.org/?probe=73e9da47ae) | Dec 27, 2022 |
| HP            | Pavilion dv6                | [d759125511](https://linux-hardware.org/?probe=d759125511) | Dec 26, 2022 |
| Acer          | Swift SF314-511             | [b8ad48c33c](https://linux-hardware.org/?probe=b8ad48c33c) | Dec 26, 2022 |
| Apple         | MacBookPro14,1              | [eb6c6ee49e](https://linux-hardware.org/?probe=eb6c6ee49e) | Dec 26, 2022 |
| ASUSTek       | N550JV                      | [748284a21e](https://linux-hardware.org/?probe=748284a21e) | Dec 26, 2022 |
| Dell          | XPS 13 9360                 | [bddcc1503f](https://linux-hardware.org/?probe=bddcc1503f) | Dec 26, 2022 |
| Acer          | Aspire A114-32              | [593969da1f](https://linux-hardware.org/?probe=593969da1f) | Dec 26, 2022 |
| Avell High... | C62 MOB                     | [658f34e70d](https://linux-hardware.org/?probe=658f34e70d) | Dec 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [46687a6be3](https://linux-hardware.org/?probe=46687a6be3) | Dec 26, 2022 |
| Sony          | VGN-FW21E                   | [e5eb6c865f](https://linux-hardware.org/?probe=e5eb6c865f) | Dec 25, 2022 |
| GPD           | G1621-02                    | [10a7e912f8](https://linux-hardware.org/?probe=10a7e912f8) | Dec 25, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [576fb3852f](https://linux-hardware.org/?probe=576fb3852f) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9ea4a13b0f](https://linux-hardware.org/?probe=9ea4a13b0f) | Dec 25, 2022 |
| HP            | 255 G8 Notebook PC          | [3f72d88324](https://linux-hardware.org/?probe=3f72d88324) | Dec 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [de111c3be5](https://linux-hardware.org/?probe=de111c3be5) | Dec 24, 2022 |
| HP            | EliteBook 865 16 inch G9... | [857cb922f9](https://linux-hardware.org/?probe=857cb922f9) | Dec 24, 2022 |
| Dell          | Latitude E7470              | [8e6bdc1809](https://linux-hardware.org/?probe=8e6bdc1809) | Dec 24, 2022 |
| System76      | Pangolin                    | [2ee273cbcf](https://linux-hardware.org/?probe=2ee273cbcf) | Dec 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [214b2a3235](https://linux-hardware.org/?probe=214b2a3235) | Dec 23, 2022 |
| HP            | Laptop 14s-dk0xxx           | [53aa474cf5](https://linux-hardware.org/?probe=53aa474cf5) | Dec 23, 2022 |
| Timi          | TM1703                      | [5e25655f36](https://linux-hardware.org/?probe=5e25655f36) | Dec 23, 2022 |
| Toshiba       | Satellite Pro C50-A-1MX     | [78487975ce](https://linux-hardware.org/?probe=78487975ce) | Dec 23, 2022 |
| Dell          | Latitude E7240              | [918223cece](https://linux-hardware.org/?probe=918223cece) | Dec 23, 2022 |
| Medion        | X6816                       | [bafbf1ea90](https://linux-hardware.org/?probe=bafbf1ea90) | Dec 23, 2022 |
| Medion        | X6816                       | [ac9627e5d4](https://linux-hardware.org/?probe=ac9627e5d4) | Dec 23, 2022 |
| Dell          | Latitude E7240              | [7bd2309063](https://linux-hardware.org/?probe=7bd2309063) | Dec 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d7b8ef01e2](https://linux-hardware.org/?probe=d7b8ef01e2) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [db7dc4fa25](https://linux-hardware.org/?probe=db7dc4fa25) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [e8ac233c29](https://linux-hardware.org/?probe=e8ac233c29) | Dec 22, 2022 |
| ASUSTek       | K53SJ                       | [341becfd8a](https://linux-hardware.org/?probe=341becfd8a) | Dec 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [ad4be7f0fa](https://linux-hardware.org/?probe=ad4be7f0fa) | Dec 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a70ba97a7a](https://linux-hardware.org/?probe=a70ba97a7a) | Dec 22, 2022 |
| ASUSTek       | K53SJ                       | [e60df2d8ba](https://linux-hardware.org/?probe=e60df2d8ba) | Dec 22, 2022 |
| Acer          | Swift SF314-512             | [505ab3f60a](https://linux-hardware.org/?probe=505ab3f60a) | Dec 22, 2022 |
| Dell          | Latitude E7240              | [d81efafde1](https://linux-hardware.org/?probe=d81efafde1) | Dec 22, 2022 |
| System76      | Lemur Pro                   | [ed549bfe74](https://linux-hardware.org/?probe=ed549bfe74) | Dec 21, 2022 |
| System76      | Lemur Pro                   | [30be17e71c](https://linux-hardware.org/?probe=30be17e71c) | Dec 21, 2022 |
| Dell          | Precision 3520              | [1763494294](https://linux-hardware.org/?probe=1763494294) | Dec 21, 2022 |
| ASUSTek       | Strix 15 GL503GE            | [0377cc3170](https://linux-hardware.org/?probe=0377cc3170) | Dec 21, 2022 |
| Dell          | Latitude E7240              | [545294a23a](https://linux-hardware.org/?probe=545294a23a) | Dec 21, 2022 |
| Apple         | MacBookPro12,1              | [debd2eb829](https://linux-hardware.org/?probe=debd2eb829) | Dec 21, 2022 |
| Dell          | Inspiron 5515               | [b0df20f3d1](https://linux-hardware.org/?probe=b0df20f3d1) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7d5914dcb2](https://linux-hardware.org/?probe=7d5914dcb2) | Dec 21, 2022 |
| Dell          | Latitude E7240              | [a368a7be00](https://linux-hardware.org/?probe=a368a7be00) | Dec 21, 2022 |
| ASUSTek       | VivoBook S14 X411UF         | [894f0ab5df](https://linux-hardware.org/?probe=894f0ab5df) | Dec 21, 2022 |
| ASUSTek       | N53SM                       | [9c9b1d3f5b](https://linux-hardware.org/?probe=9c9b1d3f5b) | Dec 21, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | [d5a877b2c6](https://linux-hardware.org/?probe=d5a877b2c6) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | [b7999f8a61](https://linux-hardware.org/?probe=b7999f8a61) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | [04b9163920](https://linux-hardware.org/?probe=04b9163920) | Dec 19, 2022 |
| Lenovo        | IdeaPad Z410 20292          | [e46710b0cf](https://linux-hardware.org/?probe=e46710b0cf) | Dec 19, 2022 |
| Dell          | Inspiron 7572               | [418178c3ca](https://linux-hardware.org/?probe=418178c3ca) | Dec 19, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1QX0... | [76771fa0aa](https://linux-hardware.org/?probe=76771fa0aa) | Dec 19, 2022 |
| Chuwi         | GemiBook Pro                | [b34ce3474d](https://linux-hardware.org/?probe=b34ce3474d) | Dec 19, 2022 |
| System76      | Gazelle                     | [da46fb926a](https://linux-hardware.org/?probe=da46fb926a) | Dec 19, 2022 |
| Dell          | Inspiron 15-3567            | [f58039213b](https://linux-hardware.org/?probe=f58039213b) | Dec 18, 2022 |
| GPU Compan... | GWNR71517                   | [e680612eb4](https://linux-hardware.org/?probe=e680612eb4) | Dec 18, 2022 |
| Lenovo        | ThinkPad Edge E430 62718... | [92fede3d5a](https://linux-hardware.org/?probe=92fede3d5a) | Dec 18, 2022 |
| Avell High... | B.ON                        | [9661ece374](https://linux-hardware.org/?probe=9661ece374) | Dec 17, 2022 |
| Dell          | XPS 15 9510                 | [1641d91910](https://linux-hardware.org/?probe=1641d91910) | Dec 17, 2022 |
| Dell          | Inspiron 5458               | [8ed4687f2f](https://linux-hardware.org/?probe=8ed4687f2f) | Dec 16, 2022 |
| System76      | Gazelle                     | [b5ef8cec53](https://linux-hardware.org/?probe=b5ef8cec53) | Dec 16, 2022 |
| Acer          | Aspire V5-571G              | [575a61802b](https://linux-hardware.org/?probe=575a61802b) | Dec 16, 2022 |
| Dell          | Latitude 3310               | [4066d1434e](https://linux-hardware.org/?probe=4066d1434e) | Dec 16, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [544e464dab](https://linux-hardware.org/?probe=544e464dab) | Dec 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [18d67ba2ab](https://linux-hardware.org/?probe=18d67ba2ab) | Dec 15, 2022 |
| ALLDOCUBE     | i1405C                      | [10d8101488](https://linux-hardware.org/?probe=10d8101488) | Dec 15, 2022 |
| Fujitsu       | FMVNS6C3                    | [d7a6961431](https://linux-hardware.org/?probe=d7a6961431) | Dec 15, 2022 |
| Apple         | MacBookPro10,1              | [a22dd35e04](https://linux-hardware.org/?probe=a22dd35e04) | Dec 14, 2022 |
| Apple         | MacBookPro11,3              | [d0c2bf600a](https://linux-hardware.org/?probe=d0c2bf600a) | Dec 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [d623f983cd](https://linux-hardware.org/?probe=d623f983cd) | Dec 13, 2022 |
| Lenovo        | G505 20240                  | [e6777c2fbc](https://linux-hardware.org/?probe=e6777c2fbc) | Dec 13, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [b08795ce45](https://linux-hardware.org/?probe=b08795ce45) | Dec 13, 2022 |
| Lenovo        | ThinkPad T530 23943J8       | [e5d69d9f81](https://linux-hardware.org/?probe=e5d69d9f81) | Dec 13, 2022 |
| Apple         | MacBookPro9,2               | [2981da7231](https://linux-hardware.org/?probe=2981da7231) | Dec 12, 2022 |
| MSI           | Summit E16Flip A12UCT       | [1db3976bb5](https://linux-hardware.org/?probe=1db3976bb5) | Dec 12, 2022 |
| Toshiba       | Satellite C55-C             | [777b365c04](https://linux-hardware.org/?probe=777b365c04) | Dec 12, 2022 |
| System76      | Gazelle                     | [8498636db6](https://linux-hardware.org/?probe=8498636db6) | Dec 12, 2022 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [d438f3f50a](https://linux-hardware.org/?probe=d438f3f50a) | Dec 12, 2022 |
| Apple         | MacBookPro13,3              | [10b29f88c5](https://linux-hardware.org/?probe=10b29f88c5) | Dec 12, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [75a9a0c076](https://linux-hardware.org/?probe=75a9a0c076) | Dec 12, 2022 |
| ASUSTek       | K56CB                       | [94b056f1f4](https://linux-hardware.org/?probe=94b056f1f4) | Dec 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E4C... | [7ffd00681b](https://linux-hardware.org/?probe=7ffd00681b) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6de2a0ad33](https://linux-hardware.org/?probe=6de2a0ad33) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [4b0492b053](https://linux-hardware.org/?probe=4b0492b053) | Dec 11, 2022 |
| Dell          | Latitude E7240              | [d6dddd9632](https://linux-hardware.org/?probe=d6dddd9632) | Dec 11, 2022 |
| Acer          | Aspire A515-44G             | [b85a211b25](https://linux-hardware.org/?probe=b85a211b25) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [ca7d835a38](https://linux-hardware.org/?probe=ca7d835a38) | Dec 11, 2022 |
| System76      | Gazelle                     | [8b0297b19e](https://linux-hardware.org/?probe=8b0297b19e) | Dec 11, 2022 |
| Lenovo        | G470 20078                  | [65264ef208](https://linux-hardware.org/?probe=65264ef208) | Dec 11, 2022 |
| Fujitsu       | FMVNS6C3                    | [2cdacbc923](https://linux-hardware.org/?probe=2cdacbc923) | Dec 11, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [15695e4deb](https://linux-hardware.org/?probe=15695e4deb) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1a7d599cd5](https://linux-hardware.org/?probe=1a7d599cd5) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [040652df3d](https://linux-hardware.org/?probe=040652df3d) | Dec 10, 2022 |
| Lenovo        | G470 20078                  | [ea75ebf831](https://linux-hardware.org/?probe=ea75ebf831) | Dec 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [2dc32e31b3](https://linux-hardware.org/?probe=2dc32e31b3) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [e8fe4392be](https://linux-hardware.org/?probe=e8fe4392be) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [cf32d7158c](https://linux-hardware.org/?probe=cf32d7158c) | Dec 09, 2022 |
| GPU Compan... | GWNR71517                   | [ef20df1d4f](https://linux-hardware.org/?probe=ef20df1d4f) | Dec 09, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [8ce314db56](https://linux-hardware.org/?probe=8ce314db56) | Dec 08, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [858f06f0e5](https://linux-hardware.org/?probe=858f06f0e5) | Dec 08, 2022 |
| Acer          | TravelMate P214-41-G2       | [cb52e49fa2](https://linux-hardware.org/?probe=cb52e49fa2) | Dec 08, 2022 |
| Dell          | G15 5515                    | [861bd0cabf](https://linux-hardware.org/?probe=861bd0cabf) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [ca25d43c56](https://linux-hardware.org/?probe=ca25d43c56) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [104e0e02d1](https://linux-hardware.org/?probe=104e0e02d1) | Dec 08, 2022 |
| LG Electro... | 16Z90P-K.AA78A1             | [1646f1763d](https://linux-hardware.org/?probe=1646f1763d) | Dec 08, 2022 |
| Avell High... | A62 LIV                     | [a4f96694c4](https://linux-hardware.org/?probe=a4f96694c4) | Dec 07, 2022 |
| Acer          | Aspire A515-45              | [7eebb7f601](https://linux-hardware.org/?probe=7eebb7f601) | Dec 07, 2022 |
| Dell          | Latitude E7240              | [632cda6ecd](https://linux-hardware.org/?probe=632cda6ecd) | Dec 07, 2022 |
| HP            | ENVY 17                     | [a19d90a89f](https://linux-hardware.org/?probe=a19d90a89f) | Dec 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b5f311cc8f](https://linux-hardware.org/?probe=b5f311cc8f) | Dec 07, 2022 |
| Dell          | Inspiron 1750               | [e369c14198](https://linux-hardware.org/?probe=e369c14198) | Dec 07, 2022 |
| Lenovo        | IdeaPad Y560                | [64abd8c6fe](https://linux-hardware.org/?probe=64abd8c6fe) | Dec 06, 2022 |
| Fujitsu       | FMVNS6C3                    | [5b60c9dfd0](https://linux-hardware.org/?probe=5b60c9dfd0) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [05f4b7d7cf](https://linux-hardware.org/?probe=05f4b7d7cf) | Dec 06, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [86cd634760](https://linux-hardware.org/?probe=86cd634760) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [6f0ceb7a46](https://linux-hardware.org/?probe=6f0ceb7a46) | Dec 05, 2022 |
| Dell          | G5 5505                     | [f19a76c344](https://linux-hardware.org/?probe=f19a76c344) | Dec 05, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [1798adf382](https://linux-hardware.org/?probe=1798adf382) | Dec 05, 2022 |
| ASUSTek       | UL50VT                      | [ff4edb7010](https://linux-hardware.org/?probe=ff4edb7010) | Dec 05, 2022 |
| HP            | ProBook 6450b               | [f602f6c0bc](https://linux-hardware.org/?probe=f602f6c0bc) | Dec 05, 2022 |
| HP            | ProBook 6450b               | [de39c86a4c](https://linux-hardware.org/?probe=de39c86a4c) | Dec 05, 2022 |
| System76      | Gazelle                     | [deb2c9b6c9](https://linux-hardware.org/?probe=deb2c9b6c9) | Dec 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [7687bdc111](https://linux-hardware.org/?probe=7687bdc111) | Dec 04, 2022 |
| Acer          | Nitro AN515-54              | [33f26cca4f](https://linux-hardware.org/?probe=33f26cca4f) | Dec 04, 2022 |
| HP            | Notebook                    | [610cea9ebc](https://linux-hardware.org/?probe=610cea9ebc) | Dec 04, 2022 |
| Dell          | Latitude E7240              | [6f34110d45](https://linux-hardware.org/?probe=6f34110d45) | Dec 04, 2022 |
| Unknown       | Unknown                     | [54c6593c53](https://linux-hardware.org/?probe=54c6593c53) | Dec 03, 2022 |
| Unknown       | Unknown                     | [7668b4d9a2](https://linux-hardware.org/?probe=7668b4d9a2) | Dec 03, 2022 |
| HP            | EliteBook 820 G3            | [6913ec89c8](https://linux-hardware.org/?probe=6913ec89c8) | Dec 03, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [4f36906529](https://linux-hardware.org/?probe=4f36906529) | Dec 02, 2022 |
| HP            | ProBook 450 G7 HP NOTEBO... | [2fe5c76c3c](https://linux-hardware.org/?probe=2fe5c76c3c) | Dec 02, 2022 |
| HP            | Notebook                    | [4184c8fa06](https://linux-hardware.org/?probe=4184c8fa06) | Dec 02, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [9c5bc7ca10](https://linux-hardware.org/?probe=9c5bc7ca10) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [0ade3eaab1](https://linux-hardware.org/?probe=0ade3eaab1) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [a3746e8985](https://linux-hardware.org/?probe=a3746e8985) | Dec 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [562e1f4b92](https://linux-hardware.org/?probe=562e1f4b92) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c8ef49d294](https://linux-hardware.org/?probe=c8ef49d294) | Dec 01, 2022 |
| HP            | Pavilion dv7                | [aa6cdce8f8](https://linux-hardware.org/?probe=aa6cdce8f8) | Dec 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [62ae8cb7dc](https://linux-hardware.org/?probe=62ae8cb7dc) | Dec 01, 2022 |
| Dell          | Inspiron 13-5378            | [9d25b2f6e0](https://linux-hardware.org/?probe=9d25b2f6e0) | Dec 01, 2022 |
| Dell          | XPS 13 9310                 | [aadf1c39a0](https://linux-hardware.org/?probe=aadf1c39a0) | Dec 01, 2022 |
| Google        | Cyan                        | [4aa7125981](https://linux-hardware.org/?probe=4aa7125981) | Nov 30, 2022 |
| HP            | ZBook 14 G2                 | [b2bba919b2](https://linux-hardware.org/?probe=b2bba919b2) | Nov 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [66b6e49eb5](https://linux-hardware.org/?probe=66b6e49eb5) | Nov 30, 2022 |
| Acer          | Nitro AN515-43              | [b315e85bda](https://linux-hardware.org/?probe=b315e85bda) | Nov 30, 2022 |
| MSI           | Modern 14 B5M               | [8277ece293](https://linux-hardware.org/?probe=8277ece293) | Nov 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [53ee9a8fb9](https://linux-hardware.org/?probe=53ee9a8fb9) | Nov 30, 2022 |
| HP            | Laptop 14-dq1xxx            | [b12534f13d](https://linux-hardware.org/?probe=b12534f13d) | Nov 30, 2022 |
| Dell          | Latitude E7240              | [8b0b984870](https://linux-hardware.org/?probe=8b0b984870) | Nov 29, 2022 |
| HP            | ProBook 450 G8              | [eec30c7857](https://linux-hardware.org/?probe=eec30c7857) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | [e9932df850](https://linux-hardware.org/?probe=e9932df850) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | [179ff76e75](https://linux-hardware.org/?probe=179ff76e75) | Nov 29, 2022 |
| HP            | Pavilion dv7                | [1ba2fdd19b](https://linux-hardware.org/?probe=1ba2fdd19b) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | [bb417133ee](https://linux-hardware.org/?probe=bb417133ee) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | [ddb2f42bcc](https://linux-hardware.org/?probe=ddb2f42bcc) | Nov 29, 2022 |
| Dell          | Latitude 5411               | [122facad78](https://linux-hardware.org/?probe=122facad78) | Nov 28, 2022 |
| HP            | Pavilion dv7                | [db7897d2fc](https://linux-hardware.org/?probe=db7897d2fc) | Nov 28, 2022 |
| Apple         | MacBookPro10,1              | [c0c2f77cdb](https://linux-hardware.org/?probe=c0c2f77cdb) | Nov 28, 2022 |
| Lenovo        | IdeaPad Y560                | [4918810cd1](https://linux-hardware.org/?probe=4918810cd1) | Nov 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [16705fe86c](https://linux-hardware.org/?probe=16705fe86c) | Nov 28, 2022 |
| Dell          | Inspiron 15 5510            | [5ec5306c0f](https://linux-hardware.org/?probe=5ec5306c0f) | Nov 28, 2022 |
| Clevo         | W55xEU                      | [5ed799ba64](https://linux-hardware.org/?probe=5ed799ba64) | Nov 28, 2022 |
| MSI           | GP72 7RDX                   | [648eb6d88a](https://linux-hardware.org/?probe=648eb6d88a) | Nov 28, 2022 |
| Acer          | Aspire A515-57              | [984e01118e](https://linux-hardware.org/?probe=984e01118e) | Nov 28, 2022 |
| HP            | Laptop 14-fq1xxx            | [7837242848](https://linux-hardware.org/?probe=7837242848) | Nov 27, 2022 |
| Toshiba       | Satellite L775D             | [bf6fc6fd49](https://linux-hardware.org/?probe=bf6fc6fd49) | Nov 27, 2022 |
| Dell          | Latitude E6230              | [f3536b80de](https://linux-hardware.org/?probe=f3536b80de) | Nov 27, 2022 |
| Dell          | Latitude E6230              | [dbaae2beb7](https://linux-hardware.org/?probe=dbaae2beb7) | Nov 27, 2022 |
| Apple         | MacBookPro6,2               | [409c3edc19](https://linux-hardware.org/?probe=409c3edc19) | Nov 27, 2022 |
| Alienware     | 17                          | [08ebf1e9a2](https://linux-hardware.org/?probe=08ebf1e9a2) | Nov 27, 2022 |
| HP            | Laptop 14-fq1xxx            | [49dc64dc76](https://linux-hardware.org/?probe=49dc64dc76) | Nov 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [935c9528be](https://linux-hardware.org/?probe=935c9528be) | Nov 26, 2022 |
| Dell          | Inspiron 3521               | [015854e59a](https://linux-hardware.org/?probe=015854e59a) | Nov 26, 2022 |
| HP            | ZBook 15                    | [2ff5969ae6](https://linux-hardware.org/?probe=2ff5969ae6) | Nov 26, 2022 |
| HP            | ZBook 15                    | [55e4fb5ba0](https://linux-hardware.org/?probe=55e4fb5ba0) | Nov 26, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [e784cdc15d](https://linux-hardware.org/?probe=e784cdc15d) | Nov 26, 2022 |
| Gigabyte      | AORUS 5 SE                  | [d9e1ceb3c1](https://linux-hardware.org/?probe=d9e1ceb3c1) | Nov 26, 2022 |
| HUAWEI        | MRGF-XX                     | [f60090b407](https://linux-hardware.org/?probe=f60090b407) | Nov 26, 2022 |
| Apple         | MacBookPro7,1               | [8268fc2c12](https://linux-hardware.org/?probe=8268fc2c12) | Nov 26, 2022 |
| HP            | ProBook 450 G5              | [9a8373739a](https://linux-hardware.org/?probe=9a8373739a) | Nov 26, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [32ab0a36a4](https://linux-hardware.org/?probe=32ab0a36a4) | Nov 25, 2022 |
| Acer          | Aspire A315-54              | [b7269b7617](https://linux-hardware.org/?probe=b7269b7617) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [770e9d413e](https://linux-hardware.org/?probe=770e9d413e) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f0bebe7a20](https://linux-hardware.org/?probe=f0bebe7a20) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [dce6415c9e](https://linux-hardware.org/?probe=dce6415c9e) | Nov 23, 2022 |
| Lenovo        | IdeaPad Y560                | [154702cbc6](https://linux-hardware.org/?probe=154702cbc6) | Nov 23, 2022 |
| Dell          | XPS 15 7590                 | [2355853fda](https://linux-hardware.org/?probe=2355853fda) | Nov 23, 2022 |
| HP            | G62                         | [754a471519](https://linux-hardware.org/?probe=754a471519) | Nov 23, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | [f06e160e11](https://linux-hardware.org/?probe=f06e160e11) | Nov 23, 2022 |
| Dell          | Latitude E7470              | [03725ebee3](https://linux-hardware.org/?probe=03725ebee3) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | [4692ce22fb](https://linux-hardware.org/?probe=4692ce22fb) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | [cb82f6d418](https://linux-hardware.org/?probe=cb82f6d418) | Nov 22, 2022 |
| Dell          | Latitude E6540              | [9a3ff03cbb](https://linux-hardware.org/?probe=9a3ff03cbb) | Nov 22, 2022 |
| Gigabyte      | AORUS 5 SE                  | [c88614e7f3](https://linux-hardware.org/?probe=c88614e7f3) | Nov 22, 2022 |
| MSI           | Katana GF76 11UG            | [e29dda268c](https://linux-hardware.org/?probe=e29dda268c) | Nov 21, 2022 |
| MSI           | Katana GF76 11UG            | [9627a23b1f](https://linux-hardware.org/?probe=9627a23b1f) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | [b0b972f8ef](https://linux-hardware.org/?probe=b0b972f8ef) | Nov 21, 2022 |
| Dell          | Precision 7670              | [93f14c8b55](https://linux-hardware.org/?probe=93f14c8b55) | Nov 21, 2022 |
| Alienware     | 17                          | [16b37ce649](https://linux-hardware.org/?probe=16b37ce649) | Nov 21, 2022 |
| Acer          | Swift SF314-42              | [5ec428f8b3](https://linux-hardware.org/?probe=5ec428f8b3) | Nov 21, 2022 |
| Unknown       | Unknown                     | [5a06cde126](https://linux-hardware.org/?probe=5a06cde126) | Nov 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [6355251bd6](https://linux-hardware.org/?probe=6355251bd6) | Nov 20, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [18f301f8c5](https://linux-hardware.org/?probe=18f301f8c5) | Nov 20, 2022 |
| Dell          | Vostro 3458                 | [9f05e54f99](https://linux-hardware.org/?probe=9f05e54f99) | Nov 20, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [cba7abe277](https://linux-hardware.org/?probe=cba7abe277) | Nov 20, 2022 |
| Lenovo        | ThinkPad E490 20N8000RUK    | [6eb57e34de](https://linux-hardware.org/?probe=6eb57e34de) | Nov 20, 2022 |
| Apple         | MacBookPro11,2              | [03447c1967](https://linux-hardware.org/?probe=03447c1967) | Nov 20, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [d4bb2f3867](https://linux-hardware.org/?probe=d4bb2f3867) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [37145c9282](https://linux-hardware.org/?probe=37145c9282) | Nov 19, 2022 |
| HP            | ProBook 6450b               | [10c8ec5d4c](https://linux-hardware.org/?probe=10c8ec5d4c) | Nov 19, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [41ffb4e75f](https://linux-hardware.org/?probe=41ffb4e75f) | Nov 19, 2022 |
| Dell          | XPS 13 9360                 | [250885e79f](https://linux-hardware.org/?probe=250885e79f) | Nov 19, 2022 |
| Valve         | Jupiter                     | [afdcde154a](https://linux-hardware.org/?probe=afdcde154a) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | [ceac47decc](https://linux-hardware.org/?probe=ceac47decc) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | [5abeec1752](https://linux-hardware.org/?probe=5abeec1752) | Nov 18, 2022 |
| Dell          | Precision M4400             | [715efc61ae](https://linux-hardware.org/?probe=715efc61ae) | Nov 18, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [95b46d1513](https://linux-hardware.org/?probe=95b46d1513) | Nov 18, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | [8f4df3bbda](https://linux-hardware.org/?probe=8f4df3bbda) | Nov 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [dee1a4e29e](https://linux-hardware.org/?probe=dee1a4e29e) | Nov 17, 2022 |
| Lenovo        | ThinkPad T550 20CJS18S00    | [ba94994594](https://linux-hardware.org/?probe=ba94994594) | Nov 17, 2022 |
| Dell          | G15 5515                    | [bb76ce58ad](https://linux-hardware.org/?probe=bb76ce58ad) | Nov 17, 2022 |
| Toshiba       | Satellite L500              | [5579ea8656](https://linux-hardware.org/?probe=5579ea8656) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [5c49c7037b](https://linux-hardware.org/?probe=5c49c7037b) | Nov 16, 2022 |
| Razer x La... | TensorBook (late 2021)      | [b7fff356a7](https://linux-hardware.org/?probe=b7fff356a7) | Nov 16, 2022 |
| HP            | ZBook 14 G2                 | [8ce9402aad](https://linux-hardware.org/?probe=8ce9402aad) | Nov 16, 2022 |
| Acer          | Aspire V3-575G              | [9044e30d53](https://linux-hardware.org/?probe=9044e30d53) | Nov 16, 2022 |
| Acer          | Aspire A114-32              | [5a76aee400](https://linux-hardware.org/?probe=5a76aee400) | Nov 16, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [1f2e05b205](https://linux-hardware.org/?probe=1f2e05b205) | Nov 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [809e86d562](https://linux-hardware.org/?probe=809e86d562) | Nov 15, 2022 |
| Acer          | Swift SF314-43              | [bc5218c5da](https://linux-hardware.org/?probe=bc5218c5da) | Nov 15, 2022 |
| OEGStone      | NOTCHA-322                  | [a5f28e095e](https://linux-hardware.org/?probe=a5f28e095e) | Nov 15, 2022 |
| System76      | Oryx Pro                    | [3ea0d459e1](https://linux-hardware.org/?probe=3ea0d459e1) | Nov 15, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [426dec8739](https://linux-hardware.org/?probe=426dec8739) | Nov 15, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [f55f35c2fe](https://linux-hardware.org/?probe=f55f35c2fe) | Nov 15, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [31cf057099](https://linux-hardware.org/?probe=31cf057099) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [0d39dde901](https://linux-hardware.org/?probe=0d39dde901) | Nov 14, 2022 |
| Dell          | Inspiron 7560               | [45474958e5](https://linux-hardware.org/?probe=45474958e5) | Nov 14, 2022 |
| Dell          | Inspiron 15 3511            | [43214de971](https://linux-hardware.org/?probe=43214de971) | Nov 13, 2022 |
| Timi          | TM1613                      | [d038ff5636](https://linux-hardware.org/?probe=d038ff5636) | Nov 13, 2022 |
| MSI           | GL73 9SC                    | [25b89592e0](https://linux-hardware.org/?probe=25b89592e0) | Nov 13, 2022 |
| GPU Compan... | GWTN141-10                  | [1e4f22395f](https://linux-hardware.org/?probe=1e4f22395f) | Nov 13, 2022 |
| GPU Compan... | GWTN141-10                  | [7325cce71f](https://linux-hardware.org/?probe=7325cce71f) | Nov 13, 2022 |
| MSI           | GL73 9SC                    | [86b0a359fa](https://linux-hardware.org/?probe=86b0a359fa) | Nov 13, 2022 |
| Apple         | MacBookPro10,1              | [d433817b4f](https://linux-hardware.org/?probe=d433817b4f) | Nov 13, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [3e75f5aa87](https://linux-hardware.org/?probe=3e75f5aa87) | Nov 12, 2022 |
| Dell          | Latitude E7270              | [629a581a22](https://linux-hardware.org/?probe=629a581a22) | Nov 12, 2022 |
| Apple         | MacBookAir6,2               | [c6b54c443e](https://linux-hardware.org/?probe=c6b54c443e) | Nov 12, 2022 |
| Google        | Shyvana                     | [2df69a0782](https://linux-hardware.org/?probe=2df69a0782) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | [aec286073d](https://linux-hardware.org/?probe=aec286073d) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | [3884507df6](https://linux-hardware.org/?probe=3884507df6) | Nov 11, 2022 |
| Dell          | Precision M4700             | [4fc304d429](https://linux-hardware.org/?probe=4fc304d429) | Nov 11, 2022 |
| HP            | EliteBook 840 G1            | [4ed347e186](https://linux-hardware.org/?probe=4ed347e186) | Nov 11, 2022 |
| System76      | Lemur Pro                   | [7df985e36a](https://linux-hardware.org/?probe=7df985e36a) | Nov 10, 2022 |
| Acer          | Aspire A114-32              | [a06fb78621](https://linux-hardware.org/?probe=a06fb78621) | Nov 10, 2022 |
| HP            | EliteBook 840 G5            | [e281a0277b](https://linux-hardware.org/?probe=e281a0277b) | Nov 10, 2022 |
| HP            | EliteBook 840 G3            | [6d00ba40be](https://linux-hardware.org/?probe=6d00ba40be) | Nov 10, 2022 |
| MSI           | MS-1688                     | [d8c76d2264](https://linux-hardware.org/?probe=d8c76d2264) | Nov 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [234729e8b5](https://linux-hardware.org/?probe=234729e8b5) | Nov 08, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [9979d8a6b6](https://linux-hardware.org/?probe=9979d8a6b6) | Nov 08, 2022 |
| Apple         | MacBookAir7,2               | [c4afe62f3b](https://linux-hardware.org/?probe=c4afe62f3b) | Nov 08, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [1918990398](https://linux-hardware.org/?probe=1918990398) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [44e88f2879](https://linux-hardware.org/?probe=44e88f2879) | Nov 07, 2022 |
| HP            | ENVY NOTEBOOK PC            | [ba3abf3883](https://linux-hardware.org/?probe=ba3abf3883) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [61756efe8c](https://linux-hardware.org/?probe=61756efe8c) | Nov 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [ca4bb217ab](https://linux-hardware.org/?probe=ca4bb217ab) | Nov 07, 2022 |
| Dell          | Latitude E7240              | [2db569e056](https://linux-hardware.org/?probe=2db569e056) | Nov 06, 2022 |
| Dell          | Inspiron 1525               | [f28061e4da](https://linux-hardware.org/?probe=f28061e4da) | Nov 06, 2022 |
| Dell          | G7 7700                     | [ba3a89822a](https://linux-hardware.org/?probe=ba3a89822a) | Nov 06, 2022 |
| Wortmann      | TERRA_MOBILE_1542           | [2a2464e0a3](https://linux-hardware.org/?probe=2a2464e0a3) | Nov 06, 2022 |
| Wortmann      | TERRA_MOBILE_1542           | [eded2f5469](https://linux-hardware.org/?probe=eded2f5469) | Nov 06, 2022 |
| Acer          | Swift SF314-42              | [c4c5bd2515](https://linux-hardware.org/?probe=c4c5bd2515) | Nov 06, 2022 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | [1f4a1244b3](https://linux-hardware.org/?probe=1f4a1244b3) | Nov 06, 2022 |
| HP            | 15 Notebook PC              | [ba76e04444](https://linux-hardware.org/?probe=ba76e04444) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [1cc6297ab8](https://linux-hardware.org/?probe=1cc6297ab8) | Nov 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [82048cfa4a](https://linux-hardware.org/?probe=82048cfa4a) | Nov 06, 2022 |
| Acer          | Aspire 5520                 | [6e6b76588b](https://linux-hardware.org/?probe=6e6b76588b) | Nov 06, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [d10e0ce942](https://linux-hardware.org/?probe=d10e0ce942) | Nov 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [a26a719002](https://linux-hardware.org/?probe=a26a719002) | Nov 05, 2022 |
| HP            | ENVY NOTEBOOK PC            | [b0600fe299](https://linux-hardware.org/?probe=b0600fe299) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [2eb5db395b](https://linux-hardware.org/?probe=2eb5db395b) | Nov 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f078009dc8](https://linux-hardware.org/?probe=f078009dc8) | Nov 05, 2022 |
| MSI           | Modern 14 B11SB             | [61543eb00f](https://linux-hardware.org/?probe=61543eb00f) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5881bdde3a](https://linux-hardware.org/?probe=5881bdde3a) | Nov 04, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [58989ea140](https://linux-hardware.org/?probe=58989ea140) | Nov 04, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [578d48ac0c](https://linux-hardware.org/?probe=578d48ac0c) | Nov 04, 2022 |
| Toshiba       | Satellite L350              | [17157970ee](https://linux-hardware.org/?probe=17157970ee) | Nov 04, 2022 |
| Toshiba       | Satellite L350              | [7479ad8a79](https://linux-hardware.org/?probe=7479ad8a79) | Nov 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [0622b6fa8f](https://linux-hardware.org/?probe=0622b6fa8f) | Nov 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [bec7082d7a](https://linux-hardware.org/?probe=bec7082d7a) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [de163caae3](https://linux-hardware.org/?probe=de163caae3) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | [fa19e49b0a](https://linux-hardware.org/?probe=fa19e49b0a) | Nov 04, 2022 |
| Dell          | Inspiron 3442               | [9fec26118c](https://linux-hardware.org/?probe=9fec26118c) | Nov 04, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [d63435720c](https://linux-hardware.org/?probe=d63435720c) | Nov 04, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [c868e47483](https://linux-hardware.org/?probe=c868e47483) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f391e8dce8](https://linux-hardware.org/?probe=f391e8dce8) | Nov 03, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [a43927efff](https://linux-hardware.org/?probe=a43927efff) | Nov 03, 2022 |
| Dell          | Precision 14 5470           | [dab29b7f5b](https://linux-hardware.org/?probe=dab29b7f5b) | Nov 03, 2022 |
| Acer          | Aspire A114-32              | [2394d00673](https://linux-hardware.org/?probe=2394d00673) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [39e7abb29a](https://linux-hardware.org/?probe=39e7abb29a) | Nov 03, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [d9de10d93e](https://linux-hardware.org/?probe=d9de10d93e) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | [036ff9e51f](https://linux-hardware.org/?probe=036ff9e51f) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | [d5d1583252](https://linux-hardware.org/?probe=d5d1583252) | Nov 02, 2022 |
| Apple         | MacBookPro9,2               | [0f40b36846](https://linux-hardware.org/?probe=0f40b36846) | Nov 02, 2022 |
| PC Special... | Elimina Iv 15               | [f462ba9c43](https://linux-hardware.org/?probe=f462ba9c43) | Nov 02, 2022 |
| Fujitsu       | LIFEBOOK A532               | [d4af3b0745](https://linux-hardware.org/?probe=d4af3b0745) | Nov 01, 2022 |
| Intel Clie... | CMCN1CC                     | [719731b244](https://linux-hardware.org/?probe=719731b244) | Nov 01, 2022 |
| Dell          | Latitude E7240              | [effafc033d](https://linux-hardware.org/?probe=effafc033d) | Nov 01, 2022 |
| Apple         | MacBookPro12,1              | [e08326bc94](https://linux-hardware.org/?probe=e08326bc94) | Nov 01, 2022 |
| Dell          | G5 5587                     | [a4e32e9eb8](https://linux-hardware.org/?probe=a4e32e9eb8) | Nov 01, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | [da8fec7ac4](https://linux-hardware.org/?probe=da8fec7ac4) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6db184e152](https://linux-hardware.org/?probe=6db184e152) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [60cfb7dcc6](https://linux-hardware.org/?probe=60cfb7dcc6) | Nov 01, 2022 |
| Dell          | Latitude E7240              | [d8ae1a7195](https://linux-hardware.org/?probe=d8ae1a7195) | Nov 01, 2022 |
| Dell          | XPS 13 9310                 | [d284b1709a](https://linux-hardware.org/?probe=d284b1709a) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [325516bbce](https://linux-hardware.org/?probe=325516bbce) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [740d19ba42](https://linux-hardware.org/?probe=740d19ba42) | Oct 31, 2022 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | [c6a13e1ab3](https://linux-hardware.org/?probe=c6a13e1ab3) | Oct 31, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [b4fedd7c20](https://linux-hardware.org/?probe=b4fedd7c20) | Oct 31, 2022 |
| Dell          | Precision M6700             | [e5952f6f57](https://linux-hardware.org/?probe=e5952f6f57) | Oct 31, 2022 |
| HP            | ENVY NOTEBOOK PC            | [f2893aaedf](https://linux-hardware.org/?probe=f2893aaedf) | Oct 31, 2022 |
| Apple         | MacBookPro11,3              | [64d1c159aa](https://linux-hardware.org/?probe=64d1c159aa) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | [4591ea2ad6](https://linux-hardware.org/?probe=4591ea2ad6) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | [5dd8b365d6](https://linux-hardware.org/?probe=5dd8b365d6) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [424aaaf5bd](https://linux-hardware.org/?probe=424aaaf5bd) | Oct 30, 2022 |
| Toshiba       | Satellite C855-1T5          | [c07f6a167a](https://linux-hardware.org/?probe=c07f6a167a) | Oct 30, 2022 |
| GPU Compan... | GWTN141-10                  | [189fca8ab3](https://linux-hardware.org/?probe=189fca8ab3) | Oct 30, 2022 |
| Tactus        | GeoBook 140                 | [71f32a229a](https://linux-hardware.org/?probe=71f32a229a) | Oct 30, 2022 |
| HP            | Pavilion dv7                | [6ff9a469f7](https://linux-hardware.org/?probe=6ff9a469f7) | Oct 30, 2022 |
| Apple         | MacBookPro3,1               | [27a5553057](https://linux-hardware.org/?probe=27a5553057) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | [8f48ae7586](https://linux-hardware.org/?probe=8f48ae7586) | Oct 29, 2022 |
| MSI           | GE60 0NC\0ND                | [79bd38da8f](https://linux-hardware.org/?probe=79bd38da8f) | Oct 29, 2022 |
| Samsung       | 800G5M/800G5W               | [d688233d28](https://linux-hardware.org/?probe=d688233d28) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | [8f1f41f3b0](https://linux-hardware.org/?probe=8f1f41f3b0) | Oct 29, 2022 |
| Acer          | Aspire E5-571G              | [cc0f34a2fa](https://linux-hardware.org/?probe=cc0f34a2fa) | Oct 29, 2022 |
| MSI           | Prestige 15 A12UC           | [3d4c4364f1](https://linux-hardware.org/?probe=3d4c4364f1) | Oct 28, 2022 |
| Notebook      | NV4xPZ                      | [86e7370778](https://linux-hardware.org/?probe=86e7370778) | Oct 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [9dcb685f5e](https://linux-hardware.org/?probe=9dcb685f5e) | Oct 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [df9ef8c115](https://linux-hardware.org/?probe=df9ef8c115) | Oct 28, 2022 |
| Apple         | MacBookPro5,3               | [4fa08c7d6f](https://linux-hardware.org/?probe=4fa08c7d6f) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3e6896ee0a](https://linux-hardware.org/?probe=3e6896ee0a) | Oct 28, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [2fdc53f0f3](https://linux-hardware.org/?probe=2fdc53f0f3) | Oct 28, 2022 |
| Acer          | Aspire E5-575G              | [04d54cb9c8](https://linux-hardware.org/?probe=04d54cb9c8) | Oct 28, 2022 |
| Dell          | Precision 5530              | [bb4d35f452](https://linux-hardware.org/?probe=bb4d35f452) | Oct 28, 2022 |
| Dell          | XPS 15 9520                 | [d04e962e56](https://linux-hardware.org/?probe=d04e962e56) | Oct 28, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0957761dea](https://linux-hardware.org/?probe=0957761dea) | Oct 28, 2022 |
| Lenovo        | Legion Y540-15IRH 81RJ      | [a90eba59e8](https://linux-hardware.org/?probe=a90eba59e8) | Oct 28, 2022 |
| HP            | Laptop 15-db0xxx            | [b82aebb005](https://linux-hardware.org/?probe=b82aebb005) | Oct 28, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [f27c4e1041](https://linux-hardware.org/?probe=f27c4e1041) | Oct 27, 2022 |
| System76      | Oryx Pro                    | [ff42b6e74a](https://linux-hardware.org/?probe=ff42b6e74a) | Oct 27, 2022 |
| Novatech      | NLx0MU                      | [41c5d984a0](https://linux-hardware.org/?probe=41c5d984a0) | Oct 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [e7db99be75](https://linux-hardware.org/?probe=e7db99be75) | Oct 27, 2022 |
| Apple         | MacBookAir6,2               | [cca0d420fe](https://linux-hardware.org/?probe=cca0d420fe) | Oct 27, 2022 |
| HP            | Laptop 15-dy2xxx            | [304a013939](https://linux-hardware.org/?probe=304a013939) | Oct 27, 2022 |
| MSI           | GF63 Thin 11UD              | [9f7121381b](https://linux-hardware.org/?probe=9f7121381b) | Oct 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ada4cec1b7](https://linux-hardware.org/?probe=ada4cec1b7) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [022cfe6707](https://linux-hardware.org/?probe=022cfe6707) | Oct 26, 2022 |
| Acer          | Aspire A515-52              | [81371581d1](https://linux-hardware.org/?probe=81371581d1) | Oct 26, 2022 |
| Gigabyte      | AERO 15 Classic-SA          | [7977a48aca](https://linux-hardware.org/?probe=7977a48aca) | Oct 26, 2022 |
| Dell          | XPS 15 9520                 | [1ede815931](https://linux-hardware.org/?probe=1ede815931) | Oct 26, 2022 |
| Acer          | Nitro AN515-58              | [9deeea3723](https://linux-hardware.org/?probe=9deeea3723) | Oct 26, 2022 |
| MSI           | GF63 Thin 11UD              | [2b6b8d3854](https://linux-hardware.org/?probe=2b6b8d3854) | Oct 26, 2022 |
| Apple         | MacBookAir7,2               | [892c5e2cda](https://linux-hardware.org/?probe=892c5e2cda) | Oct 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [b98bd6b361](https://linux-hardware.org/?probe=b98bd6b361) | Oct 26, 2022 |
| Lenovo        | ThinkPad X260 20F600A4MD    | [50cce404c7](https://linux-hardware.org/?probe=50cce404c7) | Oct 25, 2022 |
| Avell High... | A62 LIV                     | [673f411692](https://linux-hardware.org/?probe=673f411692) | Oct 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [3375318388](https://linux-hardware.org/?probe=3375318388) | Oct 25, 2022 |
| Dell          | XPS 15 7590                 | [7f9028d036](https://linux-hardware.org/?probe=7f9028d036) | Oct 25, 2022 |
| Toshiba       | Satellite Pro S500          | [a26efdcfb5](https://linux-hardware.org/?probe=a26efdcfb5) | Oct 25, 2022 |
| HP            | ZBook 15                    | [b2d2352668](https://linux-hardware.org/?probe=b2d2352668) | Oct 25, 2022 |
| HP            | EliteBook 820 G2            | [b31fec75e1](https://linux-hardware.org/?probe=b31fec75e1) | Oct 25, 2022 |
| Dell          | G15 5511                    | [0f47c64bab](https://linux-hardware.org/?probe=0f47c64bab) | Oct 25, 2022 |
| Acer          | Nitro AN515-58              | [d03f6896eb](https://linux-hardware.org/?probe=d03f6896eb) | Oct 25, 2022 |
| Dell          | Latitude E7240              | [6966cfc71f](https://linux-hardware.org/?probe=6966cfc71f) | Oct 25, 2022 |
| MSI           | Prestige 14Evo A11M         | [7c4edd1a6d](https://linux-hardware.org/?probe=7c4edd1a6d) | Oct 24, 2022 |
| Dell          | XPS 15 9570                 | [d76c41ef1b](https://linux-hardware.org/?probe=d76c41ef1b) | Oct 24, 2022 |
| Dell          | Inspiron 16 7610            | [47a3e2b5f6](https://linux-hardware.org/?probe=47a3e2b5f6) | Oct 24, 2022 |
| HP            | Laptop 15s-fq0xxx           | [2510215a0b](https://linux-hardware.org/?probe=2510215a0b) | Oct 24, 2022 |
| Apple         | MacBookAir6,2               | [c271de3628](https://linux-hardware.org/?probe=c271de3628) | Oct 24, 2022 |
| System76      | Gazelle                     | [77686d0854](https://linux-hardware.org/?probe=77686d0854) | Oct 24, 2022 |
| HP            | Laptop 15s-gy0xxx           | [d1219c1387](https://linux-hardware.org/?probe=d1219c1387) | Oct 23, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [c70d6b90b6](https://linux-hardware.org/?probe=c70d6b90b6) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [bd25fa1073](https://linux-hardware.org/?probe=bd25fa1073) | Oct 23, 2022 |
| Apple         | MacBookAir6,2               | [edd13bcc76](https://linux-hardware.org/?probe=edd13bcc76) | Oct 23, 2022 |
| Apple         | MacBookPro10,1              | [9380dfc8b7](https://linux-hardware.org/?probe=9380dfc8b7) | Oct 23, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [4884be1a24](https://linux-hardware.org/?probe=4884be1a24) | Oct 22, 2022 |
| Dell          | Inspiron 3576               | [426ddc8fdb](https://linux-hardware.org/?probe=426ddc8fdb) | Oct 22, 2022 |
| Lenovo        | G50-30 80G0                 | [32a9b1de4f](https://linux-hardware.org/?probe=32a9b1de4f) | Oct 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [079a05485d](https://linux-hardware.org/?probe=079a05485d) | Oct 22, 2022 |
| System76      | Oryx Pro                    | [7de5d55c99](https://linux-hardware.org/?probe=7de5d55c99) | Oct 22, 2022 |
| Intel         | Montevina CRB               | [11cb344c52](https://linux-hardware.org/?probe=11cb344c52) | Oct 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1227d6561e](https://linux-hardware.org/?probe=1227d6561e) | Oct 22, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [ed692d6080](https://linux-hardware.org/?probe=ed692d6080) | Oct 21, 2022 |
| Razer x La... | TensorBook (late 2021)      | [27cae45787](https://linux-hardware.org/?probe=27cae45787) | Oct 20, 2022 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [504036a2f6](https://linux-hardware.org/?probe=504036a2f6) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ddee1b5408](https://linux-hardware.org/?probe=ddee1b5408) | Oct 20, 2022 |
| System76      | Lemur Pro                   | [df61411c9d](https://linux-hardware.org/?probe=df61411c9d) | Oct 20, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c14937070e](https://linux-hardware.org/?probe=c14937070e) | Oct 19, 2022 |
| Dell          | Inspiron 3583               | [a8170f7786](https://linux-hardware.org/?probe=a8170f7786) | Oct 19, 2022 |
| MSI           | GF63 Thin 11UD              | [ca39605260](https://linux-hardware.org/?probe=ca39605260) | Oct 18, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [08327d561d](https://linux-hardware.org/?probe=08327d561d) | Oct 18, 2022 |
| Apple         | MacBookPro5,4               | [2a51555c53](https://linux-hardware.org/?probe=2a51555c53) | Oct 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [ed64a103f1](https://linux-hardware.org/?probe=ed64a103f1) | Oct 18, 2022 |
| HP            | Laptop 15-dy0xxx            | [2d1482e433](https://linux-hardware.org/?probe=2d1482e433) | Oct 18, 2022 |
| System76      | Lemur Pro                   | [53226822f5](https://linux-hardware.org/?probe=53226822f5) | Oct 18, 2022 |
| MSI           | GF63 Thin 11UD              | [d522208941](https://linux-hardware.org/?probe=d522208941) | Oct 17, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [40771441a2](https://linux-hardware.org/?probe=40771441a2) | Oct 17, 2022 |
| Lenovo        | Legion Y740-17IRH 81UG      | [67aec6ad33](https://linux-hardware.org/?probe=67aec6ad33) | Oct 17, 2022 |
| MSI           | GP72VR 7RF                  | [86a4902866](https://linux-hardware.org/?probe=86a4902866) | Oct 17, 2022 |
| Dell          | Latitude E6430s             | [ca202dddd6](https://linux-hardware.org/?probe=ca202dddd6) | Oct 17, 2022 |
| Acer          | Aspire E5-553G              | [bab2e8dad2](https://linux-hardware.org/?probe=bab2e8dad2) | Oct 17, 2022 |
| HP            | G62                         | [839b09744e](https://linux-hardware.org/?probe=839b09744e) | Oct 17, 2022 |
| Dell          | Vostro 15-3568              | [b7ea5640c2](https://linux-hardware.org/?probe=b7ea5640c2) | Oct 17, 2022 |
| HP            | ENVY 17                     | [ab25d54223](https://linux-hardware.org/?probe=ab25d54223) | Oct 16, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [502f19e8b3](https://linux-hardware.org/?probe=502f19e8b3) | Oct 16, 2022 |
| HP            | Pavilion g6                 | [2729d4b101](https://linux-hardware.org/?probe=2729d4b101) | Oct 14, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [2ba7e8c424](https://linux-hardware.org/?probe=2ba7e8c424) | Oct 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [128cccafa6](https://linux-hardware.org/?probe=128cccafa6) | Oct 14, 2022 |
| HP            | Pavilion g6                 | [4fbce46637](https://linux-hardware.org/?probe=4fbce46637) | Oct 14, 2022 |
| System76      | Galago Pro                  | [ec92c5a918](https://linux-hardware.org/?probe=ec92c5a918) | Oct 14, 2022 |
| KELYX ARGE... | KL9120                      | [a14b57c22c](https://linux-hardware.org/?probe=a14b57c22c) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [e2db064195](https://linux-hardware.org/?probe=e2db064195) | Oct 13, 2022 |
| Google        | Kefka                       | [4775b995dd](https://linux-hardware.org/?probe=4775b995dd) | Oct 13, 2022 |
| System76      | Lemur Pro                   | [ec569ddc8f](https://linux-hardware.org/?probe=ec569ddc8f) | Oct 13, 2022 |
| MSI           | Katana GF76 11UD            | [3c11d61a58](https://linux-hardware.org/?probe=3c11d61a58) | Oct 13, 2022 |
| MSI           | Katana GF76 11UD            | [236e24530f](https://linux-hardware.org/?probe=236e24530f) | Oct 12, 2022 |
| Dell          | Precision M6700             | [4c867e9075](https://linux-hardware.org/?probe=4c867e9075) | Oct 12, 2022 |
| Acer          | Aspire 5740                 | [273721cef2](https://linux-hardware.org/?probe=273721cef2) | Oct 12, 2022 |
| Razer         | Blade                       | [c7386df23f](https://linux-hardware.org/?probe=c7386df23f) | Oct 12, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [2d102e0f1e](https://linux-hardware.org/?probe=2d102e0f1e) | Oct 12, 2022 |
| HP            | Pavilion 15                 | [8b93ec27f4](https://linux-hardware.org/?probe=8b93ec27f4) | Oct 12, 2022 |
| GPU Compan... | GWTN141-10                  | [1feb5d7501](https://linux-hardware.org/?probe=1feb5d7501) | Oct 12, 2022 |
| Alienware     | 15 R3                       | [bfdbf12cbb](https://linux-hardware.org/?probe=bfdbf12cbb) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | [93ca81946a](https://linux-hardware.org/?probe=93ca81946a) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | [921c4a26d1](https://linux-hardware.org/?probe=921c4a26d1) | Oct 11, 2022 |
| KELYX ARGE... | KL9120                      | [477851891a](https://linux-hardware.org/?probe=477851891a) | Oct 11, 2022 |
| MSI           | MS-7A34                     | [9850074c97](https://linux-hardware.org/?probe=9850074c97) | Oct 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [f4a46537c2](https://linux-hardware.org/?probe=f4a46537c2) | Oct 10, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                              | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| 5.19.0-76051900-generic              | 271       | 18.05%  |
| 6.0.12-76060006-generic              | 254       | 16.92%  |
| 5.17.5-76051705-generic              | 227       | 15.12%  |
| 6.0.6-76060006-generic               | 161       | 10.73%  |
| 5.18.10-76051810-generic             | 117       | 7.79%   |
| 5.17.15-76051715-generic             | 104       | 6.93%   |
| 6.2.0-76060200-generic               | 70        | 4.66%   |
| 5.16.19-76051619-generic             | 70        | 4.66%   |
| 6.0.2-76060002-generic               | 59        | 3.93%   |
| 6.1.11-76060111-generic              | 53        | 3.53%   |
| 6.2.6-76060206-generic               | 30        | 2%      |
| 6.0.3-76060003-generic               | 23        | 1.53%   |
| 5.19.16-76051916-generic             | 21        | 1.4%    |
| 6.1.0-1006-oem                       | 2         | 0.13%   |
| 5.17.5-051705-generic                | 2         | 0.13%   |
| 5.16.15-76051615-generic             | 2         | 0.13%   |
| 6.2.6-060206-generic                 | 1         | 0.07%   |
| 6.2.1-060201-generic                 | 1         | 0.07%   |
| 6.1.9-x64v1-xanmod1                  | 1         | 0.07%   |
| 6.1.9-060109-generic                 | 1         | 0.07%   |
| 6.1.8-060108-generic                 | 1         | 0.07%   |
| 6.1.7-060107-generic                 | 1         | 0.07%   |
| 6.1.18-x64v2-xanmod1                 | 1         | 0.07%   |
| 6.1.14-x64v2-xanmod1                 | 1         | 0.07%   |
| 6.1.0-2.1-liquorix-amd64             | 1         | 0.07%   |
| 6.0.9-x64v1-xanmod1                  | 1         | 0.07%   |
| 6.0.9-060009-generic                 | 1         | 0.07%   |
| 6.0.2-x64v2-xanmod1                  | 1         | 0.07%   |
| 6.0.0-060000rc1daily20220820-generic | 1         | 0.07%   |
| 6.0.0-060000-generic                 | 1         | 0.07%   |
| 5.19.4-xanmod1                       | 1         | 0.07%   |
| 5.19.3-051903-generic                | 1         | 0.07%   |
| 5.19.14-xanmod1                      | 1         | 0.07%   |
| 5.19.12-xanmod1                      | 1         | 0.07%   |
| 5.19.0-rc1+                          | 1         | 0.07%   |
| 5.19.0-051900-generic                | 1         | 0.07%   |
| 5.18.6-xanmod1                       | 1         | 0.07%   |
| 5.18.4-xanmod1                       | 1         | 0.07%   |
| 5.18.16-xanmod1                      | 1         | 0.07%   |
| 5.18.0-051800rc1-generic             | 1         | 0.07%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19.0  | 273       | 18.2%   |
| 6.0.12  | 254       | 16.93%  |
| 5.17.5  | 230       | 15.33%  |
| 6.0.6   | 161       | 10.73%  |
| 5.18.10 | 117       | 7.8%    |
| 5.17.15 | 104       | 6.93%   |
| 6.2.0   | 70        | 4.67%   |
| 5.16.19 | 70        | 4.67%   |
| 6.0.2   | 60        | 4%      |
| 6.1.11  | 53        | 3.53%   |
| 6.2.6   | 31        | 2.07%   |
| 6.0.3   | 23        | 1.53%   |
| 5.19.16 | 21        | 1.4%    |
| 6.1.9   | 2         | 0.13%   |
| 6.1.0   | 2         | 0.13%   |
| 6.0.9   | 2         | 0.13%   |
| 6.0.0   | 2         | 0.13%   |
| 5.17.0  | 2         | 0.13%   |
| 5.16.15 | 2         | 0.13%   |
| 5.15.0  | 2         | 0.13%   |
| 6.2.1   | 1         | 0.07%   |
| 6.1.8   | 1         | 0.07%   |
| 6.1.7   | 1         | 0.07%   |
| 6.1.18  | 1         | 0.07%   |
| 6.1.14  | 1         | 0.07%   |
| 5.19.4  | 1         | 0.07%   |
| 5.19.3  | 1         | 0.07%   |
| 5.19.14 | 1         | 0.07%   |
| 5.19.12 | 1         | 0.07%   |
| 5.18.6  | 1         | 0.07%   |
| 5.18.4  | 1         | 0.07%   |
| 5.18.16 | 1         | 0.07%   |
| 5.18.0  | 1         | 0.07%   |
| 5.17.7  | 1         | 0.07%   |
| 5.17.6  | 1         | 0.07%   |
| 5.17.2  | 1         | 0.07%   |
| 5.16.11 | 1         | 0.07%   |
| 5.15.87 | 1         | 0.07%   |
| 5.15.65 | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0     | 484       | 32.86%  |
| 5.17    | 333       | 22.61%  |
| 5.19    | 296       | 20.1%   |
| 5.18    | 121       | 8.21%   |
| 6.2     | 102       | 6.92%   |
| 5.16    | 73        | 4.96%   |
| 6.1     | 60        | 4.07%   |
| 5.15    | 4         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1376      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 1348      | 97.82%  |
| KDE5            | 13        | 0.94%   |
| Unknown         | 8         | 0.58%   |
| X-Cinnamon      | 3         | 0.22%   |
| Unity           | 2         | 0.15%   |
| GNOME Flashback | 2         | 0.15%   |
| XFCE            | 1         | 0.07%   |
| LXQt            | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1315      | 95.01%  |
| Wayland | 60        | 4.34%   |
| Unknown | 7         | 0.51%   |
| Tty     | 2         | 0.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1003      | 72.31%  |
| GDM3    | 378       | 27.25%  |
| GDM     | 4         | 0.29%   |
| SDDM    | 2         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 843       | 61.04%  |
| en_GB   | 89        | 6.44%   |
| pt_BR   | 79        | 5.72%   |
| de_DE   | 52        | 3.77%   |
| it_IT   | 38        | 2.75%   |
| C       | 32        | 2.32%   |
| en_AU   | 28        | 2.03%   |
| fr_FR   | 23        | 1.67%   |
| es_ES   | 19        | 1.38%   |
| ru_RU   | 16        | 1.16%   |
| en_CA   | 16        | 1.16%   |
| nb_NO   | 12        | 0.87%   |
| sv_SE   | 10        | 0.72%   |
| pl_PL   | 10        | 0.72%   |
| en_IE   | 9         | 0.65%   |
| en_NZ   | 8         | 0.58%   |
| pt_PT   | 7         | 0.51%   |
| Unknown | 7         | 0.51%   |
| nl_NL   | 6         | 0.43%   |
| fi_FI   | 6         | 0.43%   |
| es_MX   | 6         | 0.43%   |
| en_IN   | 6         | 0.43%   |
| fr_CA   | 5         | 0.36%   |
| es_AR   | 5         | 0.36%   |
| de_CH   | 5         | 0.36%   |
| tr_TR   | 4         | 0.29%   |
| es_CO   | 4         | 0.29%   |
| en_ZA   | 4         | 0.29%   |
| es_CL   | 3         | 0.22%   |
| cs_CZ   | 3         | 0.22%   |
| fr_CH   | 2         | 0.14%   |
| fr_BE   | 2         | 0.14%   |
| en_SG   | 2         | 0.14%   |
| en_DK   | 2         | 0.14%   |
| de_AT   | 2         | 0.14%   |
| da_DK   | 2         | 0.14%   |
| sr_RS   | 1         | 0.07%   |
| ro_RO   | 1         | 0.07%   |
| lv_LV   | 1         | 0.07%   |
| ja_JP   | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1020      | 73.65%  |
| EFI  | 365       | 26.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1301      | 94.21%  |
| Btrfs   | 54        | 3.91%   |
| Overlay | 20        | 1.45%   |
| Xfs     | 5         | 0.36%   |
| Zfs     | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 995       | 71.74%  |
| GPT     | 367       | 26.46%  |
| MBR     | 25        | 1.8%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1342      | 97.32%  |
| Yes       | 37        | 2.68%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1253      | 90.73%  |
| Yes       | 128       | 9.27%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 279       | 20.28%  |
| Dell                   | 229       | 16.64%  |
| Hewlett-Packard        | 181       | 13.15%  |
| ASUSTek Computer       | 171       | 12.43%  |
| Acer                   | 101       | 7.34%   |
| Apple                  | 96        | 6.98%   |
| MSI                    | 48        | 3.49%   |
| System76               | 43        | 3.13%   |
| Toshiba                | 27        | 1.96%   |
| Samsung Electronics    | 22        | 1.6%    |
| HUAWEI                 | 19        | 1.38%   |
| Google                 | 13        | 0.94%   |
| Fujitsu                | 10        | 0.73%   |
| Alienware              | 10        | 0.73%   |
| Razer                  | 8         | 0.58%   |
| GPU Company            | 8         | 0.58%   |
| Gigabyte Technology    | 8         | 0.58%   |
| Sony                   | 7         | 0.51%   |
| Notebook               | 7         | 0.51%   |
| Timi                   | 6         | 0.44%   |
| Framework              | 6         | 0.44%   |
| HONOR                  | 5         | 0.36%   |
| Avell High Performance | 5         | 0.36%   |
| TUXEDO                 | 4         | 0.29%   |
| Positivo               | 4         | 0.29%   |
| Unknown                | 4         | 0.29%   |
| PC Specialist          | 3         | 0.22%   |
| LG Electronics         | 3         | 0.22%   |
| GPD                    | 3         | 0.22%   |
| Clevo                  | 3         | 0.22%   |
| Valve                  | 2         | 0.15%   |
| Panasonic              | 2         | 0.15%   |
| OriginPC               | 2         | 0.15%   |
| Medion                 | 2         | 0.15%   |
| Wortmann AG            | 1         | 0.07%   |
| VANT                   | 1         | 0.07%   |
| Tactus                 | 1         | 0.07%   |
| Star Labs              | 1         | 0.07%   |
| Semp Toshiba           | 1         | 0.07%   |
| Schenker               | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| System76 Oryx Pro                   | 13        | 0.94%   |
| System76 Lemur Pro                  | 12        | 0.87%   |
| Apple MacBookPro12,1                | 9         | 0.65%   |
| Apple MacBookAir7,2                 | 9         | 0.65%   |
| Apple MacBookPro9,2                 | 8         | 0.58%   |
| Unknown                             | 8         | 0.58%   |
| System76 Gazelle                    | 7         | 0.51%   |
| HP Dev One Notebook PC              | 7         | 0.51%   |
| Apple MacBookAir6,2                 | 7         | 0.51%   |
| Lenovo IdeaPad S145-15API 81V7      | 6         | 0.44%   |
| Dell XPS 15 9520                    | 6         | 0.44%   |
| Lenovo Legion 5 15ACH6H 82JU        | 5         | 0.36%   |
| HP Pavilion 15                      | 5         | 0.36%   |
| Dell XPS 13 9360                    | 5         | 0.36%   |
| Dell Latitude E7240                 | 5         | 0.36%   |
| Apple MacBookPro7,1                 | 5         | 0.36%   |
| Apple MacBookPro11,3                | 5         | 0.36%   |
| Acer Aspire A515-45                 | 5         | 0.36%   |
| System76 Galago Pro                 | 4         | 0.29%   |
| Lenovo IdeaPad 5 Pro 16ARH7 82SN    | 4         | 0.29%   |
| Lenovo IdeaPad 3 15ALC6 82MF        | 4         | 0.29%   |
| HP Notebook                         | 4         | 0.29%   |
| Framework Laptop                    | 4         | 0.29%   |
| Dell XPS 15 9570                    | 4         | 0.29%   |
| Dell XPS 13 9310                    | 4         | 0.29%   |
| Dell XPS 13 9305                    | 4         | 0.29%   |
| Dell Latitude E7270                 | 4         | 0.29%   |
| Dell Latitude E6540                 | 4         | 0.29%   |
| Apple MacBookPro8,1                 | 4         | 0.29%   |
| Apple MacBook5,1                    | 4         | 0.29%   |
| Acer Nitro AN515-58                 | 4         | 0.29%   |
| System76 Darter Pro                 | 3         | 0.22%   |
| Razer Blade                         | 3         | 0.22%   |
| MSI Prestige 15 A10SC               | 3         | 0.22%   |
| Lenovo Legion Y530-15ICH 81FV       | 3         | 0.22%   |
| Lenovo Legion 5 Pro 16ARH7H 82RG    | 3         | 0.22%   |
| Lenovo IdeaPad 330-15IKB 81FE       | 3         | 0.22%   |
| HONOR NMH-WCX9                      | 3         | 0.22%   |
| HP Pavilion Notebook                | 3         | 0.22%   |
| HP Pavilion Gaming Laptop 15-dk0xxx | 3         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 126       | 9.16%   |
| Lenovo IdeaPad     | 73        | 5.31%   |
| Acer Aspire        | 63        | 4.58%   |
| Dell Inspiron      | 61        | 4.43%   |
| Dell Latitude      | 55        | 4%      |
| Dell XPS           | 49        | 3.56%   |
| HP Pavilion        | 36        | 2.62%   |
| Lenovo Legion      | 33        | 2.4%    |
| HP EliteBook       | 32        | 2.33%   |
| ASUS VivoBook      | 32        | 2.33%   |
| ASUS ROG           | 30        | 2.18%   |
| HP Laptop          | 28        | 2.03%   |
| Dell Precision     | 25        | 1.82%   |
| Toshiba Satellite  | 24        | 1.74%   |
| HP ProBook         | 23        | 1.67%   |
| ASUS ASUS          | 21        | 1.53%   |
| Acer Swift         | 16        | 1.16%   |
| ASUS Zenbook       | 15        | 1.09%   |
| HP ZBook           | 14        | 1.02%   |
| Acer Nitro         | 14        | 1.02%   |
| System76 Oryx      | 13        | 0.94%   |
| Dell Vostro        | 13        | 0.94%   |
| Apple MacBookPro11 | 13        | 0.94%   |
| System76 Lemur     | 12        | 0.87%   |
| Lenovo ThinkBook   | 10        | 0.73%   |
| HP ENVY            | 10        | 0.73%   |
| HP OMEN            | 9         | 0.65%   |
| Apple MacBookPro9  | 9         | 0.65%   |
| Apple MacBookPro12 | 9         | 0.65%   |
| Apple MacBookAir7  | 9         | 0.65%   |
| Razer Blade        | 8         | 0.58%   |
| Fujitsu LIFEBOOK   | 8         | 0.58%   |
| Dell G15           | 8         | 0.58%   |
| Unknown            | 8         | 0.58%   |
| System76 Gazelle   | 7         | 0.51%   |
| HP Dev             | 7         | 0.51%   |
| Apple MacBookPro5  | 7         | 0.51%   |
| Apple MacBookAir6  | 7         | 0.51%   |
| MSI Prestige       | 6         | 0.44%   |
| Framework Laptop   | 6         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 244       | 17.73%  |
| 2020 | 162       | 11.77%  |
| 2022 | 147       | 10.68%  |
| 2019 | 124       | 9.01%   |
| 2018 | 108       | 7.85%   |
| 2013 | 84        | 6.1%    |
| 2016 | 78        | 5.67%   |
| 2012 | 77        | 5.6%    |
| 2015 | 76        | 5.52%   |
| 2017 | 63        | 4.58%   |
| 2011 | 59        | 4.29%   |
| 2014 | 53        | 3.85%   |
| 2010 | 42        | 3.05%   |
| 2009 | 36        | 2.62%   |
| 2008 | 14        | 1.02%   |
| 2007 | 5         | 0.36%   |
| 2023 | 4         | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1376      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1376      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1330      | 96.66%  |
| Yes  | 46        | 3.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 396       | 28.57%  |
| 16.01-24.0  | 345       | 24.89%  |
| 8.01-16.0   | 258       | 18.61%  |
| 3.01-4.0    | 162       | 11.69%  |
| 32.01-64.0  | 153       | 11.04%  |
| 64.01-256.0 | 33        | 2.38%   |
| 24.01-32.0  | 29        | 2.09%   |
| 2.01-3.0    | 6         | 0.43%   |
| 1.01-2.0    | 4         | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 477       | 32.47%  |
| 4.01-8.0   | 394       | 26.82%  |
| 3.01-4.0   | 327       | 22.26%  |
| 1.01-2.0   | 156       | 10.62%  |
| 8.01-16.0  | 101       | 6.88%   |
| 16.01-24.0 | 12        | 0.82%   |
| 24.01-32.0 | 2         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1001      | 72.38%  |
| 2      | 331       | 23.93%  |
| 3      | 41        | 2.96%   |
| 4      | 4         | 0.29%   |
| 0      | 4         | 0.29%   |
| 7      | 1         | 0.07%   |
| 5      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1077      | 78.16%  |
| Yes       | 301       | 21.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1032      | 74.73%  |
| No        | 349       | 25.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1362      | 98.98%  |
| No        | 14        | 1.02%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1179      | 85.31%  |
| No        | 203       | 14.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 371       | 26.83%  |
| Brazil       | 119       | 8.6%    |
| Germany      | 84        | 6.07%   |
| Italy        | 64        | 4.63%   |
| UK           | 61        | 4.41%   |
| India        | 57        | 4.12%   |
| Canada       | 47        | 3.4%    |
| France       | 38        | 2.75%   |
| Australia    | 35        | 2.53%   |
| Russia       | 29        | 2.1%    |
| Norway       | 25        | 1.81%   |
| Netherlands  | 23        | 1.66%   |
| Spain        | 22        | 1.59%   |
| Sweden       | 21        | 1.52%   |
| Mexico       | 19        | 1.37%   |
| Portugal     | 17        | 1.23%   |
| Poland       | 17        | 1.23%   |
| Turkey       | 15        | 1.08%   |
| Switzerland  | 14        | 1.01%   |
| New Zealand  | 14        | 1.01%   |
| Greece       | 13        | 0.94%   |
| Romania      | 12        | 0.87%   |
| Philippines  | 12        | 0.87%   |
| Indonesia    | 12        | 0.87%   |
| Finland      | 12        | 0.87%   |
| Argentina    | 12        | 0.87%   |
| Thailand     | 11        | 0.8%    |
| Belgium      | 11        | 0.8%    |
| Chile        | 9         | 0.65%   |
| Bulgaria     | 9         | 0.65%   |
| Ireland      | 8         | 0.58%   |
| Hungary      | 8         | 0.58%   |
| Czechia      | 8         | 0.58%   |
| Colombia     | 8         | 0.58%   |
| Austria      | 8         | 0.58%   |
| South Africa | 7         | 0.51%   |
| Serbia       | 7         | 0.51%   |
| Denmark      | 7         | 0.51%   |
| Vietnam      | 6         | 0.43%   |
| Egypt        | 6         | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Milan          | 12        | 0.84%   |
| Istanbul       | 11        | 0.77%   |
| Brisbane       | 11        | 0.77%   |
| Oslo           | 10        | 0.7%    |
| Berlin         | 10        | 0.7%    |
| Bengaluru      | 10        | 0.7%    |
| Sao Paulo      | 9         | 0.63%   |
| Melbourne      | 9         | 0.63%   |
| Rome           | 8         | 0.56%   |
| Munich         | 8         | 0.56%   |
| Moscow         | 8         | 0.56%   |
| London         | 8         | 0.56%   |
| Helsinki       | 8         | 0.56%   |
| Chicago        | 8         | 0.56%   |
| St Petersburg  | 7         | 0.49%   |
| Rio de Janeiro | 7         | 0.49%   |
| Denver         | 7         | 0.49%   |
| Auckland       | 7         | 0.49%   |
| Sydney         | 6         | 0.42%   |
| Sofia          | 6         | 0.42%   |
| Seattle        | 6         | 0.42%   |
| New York       | 6         | 0.42%   |
| Mumbai         | 6         | 0.42%   |
| Minneapolis    | 6         | 0.42%   |
| Lisbon         | 6         | 0.42%   |
| Calgary        | 6         | 0.42%   |
| Zurich         | 5         | 0.35%   |
| Warsaw         | 5         | 0.35%   |
| Singapore      | 5         | 0.35%   |
| San Jose       | 5         | 0.35%   |
| Paris          | 5         | 0.35%   |
| Edmonton       | 5         | 0.35%   |
| Dallas         | 5         | 0.35%   |
| Budapest       | 5         | 0.35%   |
| Bucharest      | 5         | 0.35%   |
| Belgrade       | 5         | 0.35%   |
| Athens         | 5         | 0.35%   |
| Washington     | 4         | 0.28%   |
| Vienna         | 4         | 0.28%   |
| Toronto        | 4         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 340       | 433    | 19.45%  |
| WDC                            | 156       | 173    | 8.92%   |
| SanDisk                        | 141       | 178    | 8.07%   |
| Seagate                        | 123       | 141    | 7.04%   |
| SK hynix                       | 104       | 118    | 5.95%   |
| Toshiba                        | 96        | 109    | 5.49%   |
| Kingston                       | 82        | 94     | 4.69%   |
| Micron Technology              | 69        | 77     | 3.95%   |
| Crucial                        | 62        | 68     | 3.55%   |
| Unknown                        | 61        | 73     | 3.49%   |
| Intel                          | 57        | 68     | 3.26%   |
| Apple                          | 52        | 56     | 2.97%   |
| HGST                           | 43        | 46     | 2.46%   |
| KIOXIA                         | 23        | 25     | 1.32%   |
| Phison                         | 22        | 24     | 1.26%   |
| A-DATA Technology              | 22        | 26     | 1.26%   |
| PNY                            | 18        | 24     | 1.03%   |
| Hitachi                        | 18        | 21     | 1.03%   |
| Micron/Crucial Technology      | 17        | 21     | 0.97%   |
| China                          | 15        | 16     | 0.86%   |
| Phison Electronics             | 14        | 16     | 0.8%    |
| Silicon Motion                 | 12        | 13     | 0.69%   |
| LITEON                         | 10        | 11     | 0.57%   |
| KingSpec                       | 10        | 11     | 0.57%   |
| LITEONIT                       | 9         | 12     | 0.51%   |
| Kingston Technology Company    | 9         | 9      | 0.51%   |
| Unknown                        | 9         | 10     | 0.51%   |
| Union Memory (Shenzhen)        | 8         | 10     | 0.46%   |
| Netac                          | 8         | 8      | 0.46%   |
| Intenso                        | 8         | 9      | 0.46%   |
| Transcend                      | 5         | 6      | 0.29%   |
| SPCC                           | 5         | 5      | 0.29%   |
| Solid State Storage Technology | 5         | 5      | 0.29%   |
| Solid State Storage            | 5         | 5      | 0.29%   |
| ADATA Technology               | 5         | 5      | 0.29%   |
| Team                           | 4         | 4      | 0.23%   |
| Patriot                        | 4         | 5      | 0.23%   |
| W800S                          | 3         | 6      | 0.17%   |
| SSSTC                          | 3         | 3      | 0.17%   |
| MyDigitalSSD                   | 3         | 3      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 32        | 1.75%   |
| Kingston SA400S37240G 240GB SSD                     | 25        | 1.37%   |
| Seagate ST1000LM035-1RK172 1TB                      | 23        | 1.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 18        | 0.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 18        | 0.98%   |
| Samsung NVMe SSD Drive 512GB                        | 17        | 0.93%   |
| HGST HTS721010A9E630 1TB                            | 16        | 0.87%   |
| Crucial CT240BX500SSD1 240GB                        | 15        | 0.82%   |
| SK hynix NVMe SSD Drive 512GB                       | 14        | 0.76%   |
| SanDisk NVMe SSD Drive 1TB                          | 13        | 0.71%   |
| Toshiba MQ04ABF100 1TB                              | 12        | 0.66%   |
| Toshiba MQ01ABD100 1TB                              | 12        | 0.66%   |
| Unknown MMC Card  64GB                              | 11        | 0.6%    |
| Apple SSD SM0128G 121GB                             | 11        | 0.6%    |
| WDC WD10SPZX-24Z10 1TB                              | 10        | 0.55%   |
| Seagate ST1000LM049-2GH172 1TB                      | 10        | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 10        | 0.55%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                | 10        | 0.55%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1TB      | 10        | 0.55%   |
| SanDisk NVMe SSD Drive 512GB                        | 10        | 0.55%   |
| Samsung NVMe SSD Drive 1TB                          | 10        | 0.55%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 10        | 0.55%   |
| Kingston SA400S37480G 480GB SSD                     | 10        | 0.55%   |
| Unknown MMC Card  32GB                              | 9         | 0.49%   |
| SK hynix NVMe SSD Drive 1024GB                      | 9         | 0.49%   |
| SanDisk NVMe SSD Drive 256GB                        | 9         | 0.49%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 9         | 0.49%   |
| Samsung NVMe SSD Drive 500GB                        | 9         | 0.49%   |
| Intel SSD 660P Series 512GB                         | 9         | 0.49%   |
| Unknown                                             | 9         | 0.49%   |
| Unknown MMC Card  128GB                             | 8         | 0.44%   |
| Samsung SSD 860 EVO 500GB                           | 8         | 0.44%   |
| Samsung SSD 850 EVO 500GB                           | 8         | 0.44%   |
| Samsung NVMe SSD Drive 2TB                          | 8         | 0.44%   |
| Samsung NVMe SSD Drive 1024GB                       | 8         | 0.44%   |
| Micron NVMe SSD Drive 512GB                         | 8         | 0.44%   |
| Intel SSDPEKNW010T8 1TB                             | 8         | 0.44%   |
| Crucial CT1000MX500SSD1 1TB                         | 8         | 0.44%   |
| Unknown SD/MMC/MS PRO 64GB                          | 7         | 0.38%   |
| Samsung SSD 970 EVO Plus 1TB                        | 7         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 119       | 137    | 34%     |
| WDC                 | 90        | 100    | 25.71%  |
| Toshiba             | 55        | 62     | 15.71%  |
| HGST                | 43        | 46     | 12.29%  |
| Hitachi             | 18        | 21     | 5.14%   |
| Unknown             | 7         | 7      | 2%      |
| Samsung Electronics | 5         | 5      | 1.43%   |
| Fujitsu             | 3         | 3      | 0.86%   |
| Apple               | 3         | 4      | 0.86%   |
| Intenso             | 2         | 3      | 0.57%   |
| USB3.0              | 1         | 1      | 0.29%   |
| SABRENT             | 1         | 2      | 0.29%   |
| PHD 3.0             | 1         | 1      | 0.29%   |
| HGST HDN            | 1         | 1      | 0.29%   |
| Asm                 | 1         | 1      | 0.29%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 106       | 138    | 20.15%  |
| Kingston            | 60        | 65     | 11.41%  |
| Crucial             | 56        | 62     | 10.65%  |
| SanDisk             | 53        | 66     | 10.08%  |
| Apple               | 40        | 42     | 7.6%    |
| WDC                 | 27        | 31     | 5.13%   |
| PNY                 | 17        | 23     | 3.23%   |
| China               | 15        | 16     | 2.85%   |
| Toshiba             | 12        | 12     | 2.28%   |
| SK hynix            | 12        | 13     | 2.28%   |
| Micron Technology   | 10        | 10     | 1.9%    |
| KingSpec            | 10        | 11     | 1.9%    |
| LITEONIT            | 9         | 12     | 1.71%   |
| LITEON              | 9         | 10     | 1.71%   |
| A-DATA Technology   | 9         | 11     | 1.71%   |
| Intel               | 8         | 9      | 1.52%   |
| Netac               | 6         | 6      | 1.14%   |
| Transcend           | 5         | 6      | 0.95%   |
| Intenso             | 5         | 5      | 0.95%   |
| Patriot             | 4         | 5      | 0.76%   |
| SPCC                | 3         | 3      | 0.57%   |
| MyDigitalSSD        | 3         | 3      | 0.57%   |
| KingDian            | 2         | 2      | 0.38%   |
| JMicron Technology  | 2         | 2      | 0.38%   |
| Hewlett-Packard     | 2         | 2      | 0.38%   |
| Dogfish             | 2         | 2      | 0.38%   |
| Apacer              | 2         | 6      | 0.38%   |
| Unknown             | 2         | 2      | 0.38%   |
| W800S               | 1         | 1      | 0.19%   |
| TwinMOS             | 1         | 1      | 0.19%   |
| TrekStor            | 1         | 1      | 0.19%   |
| Teutons             | 1         | 1      | 0.19%   |
| Teclast             | 1         | 1      | 0.19%   |
| TEAM TM8            | 1         | 1      | 0.19%   |
| SATAFIRM            | 1         | 1      | 0.19%   |
| Ramaxel Technology  | 1         | 1      | 0.19%   |
| Radeon              | 1         | 1      | 0.19%   |
| PUSKILL             | 1         | 1      | 0.19%   |
| PNY USB             | 1         | 1      | 0.19%   |
| Phison              | 1         | 1      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 721       | 943    | 44.34%  |
| SSD     | 488       | 611    | 30.01%  |
| HDD     | 337       | 394    | 20.73%  |
| MMC     | 55        | 63     | 3.38%   |
| Unknown | 25        | 35     | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 728       | 959    | 46.37%  |
| NVMe | 719       | 939    | 45.8%   |
| SAS  | 68        | 85     | 4.33%   |
| MMC  | 55        | 63     | 3.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 511       | 655    | 62.93%  |
| 0.51-1.0   | 258       | 292    | 31.77%  |
| 1.01-2.0   | 34        | 43     | 4.19%   |
| 4.01-10.0  | 5         | 10     | 0.62%   |
| 3.01-4.0   | 2         | 2      | 0.25%   |
| 2.01-3.0   | 2         | 3      | 0.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 442       | 31.62%  |
| 251-500        | 418       | 29.9%   |
| 501-1000       | 296       | 21.17%  |
| 1001-2000      | 97        | 6.94%   |
| 51-100         | 47        | 3.36%   |
| 1-20           | 29        | 2.07%   |
| 21-50          | 22        | 1.57%   |
| 2001-3000      | 21        | 1.5%    |
| More than 3000 | 19        | 1.36%   |
| Unknown        | 7         | 0.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 459       | 31.63%  |
| 21-50          | 356       | 24.53%  |
| 101-250        | 218       | 15.02%  |
| 51-100         | 205       | 14.13%  |
| 251-500        | 125       | 8.61%   |
| 501-1000       | 59        | 4.07%   |
| 1001-2000      | 11        | 0.76%   |
| Unknown        | 7         | 0.48%   |
| More than 3000 | 6         | 0.41%   |
| 2001-3000      | 5         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS001TDE9X073N 1TB                  | 2         | 2      | 6.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 2      | 6.25%   |
| HGST HTS725050A7E630 500GB                          | 2         | 3      | 6.25%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 1      | 3.13%   |
| WDC WD3200BEKT-60PVMT0 320GB                        | 1         | 1      | 3.13%   |
| WDC WD10SPZX-22Z10T0 1TB                            | 1         | 1      | 3.13%   |
| WDC WD10JPVX-60JC3T1 1TB                            | 1         | 1      | 3.13%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 3.13%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB                | 1         | 1      | 3.13%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD            | 1         | 1      | 3.13%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 1         | 1      | 3.13%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1      | 3.13%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 3.13%   |
| Team TM8FP4004T 4TB                                 | 1         | 1      | 3.13%   |
| SK hynix HFS512G39TND-N210A 512GB SSD               | 1         | 1      | 3.13%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 1         | 1      | 3.13%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 3.13%   |
| Seagate ST500LM030-2E717D 500GB                     | 1         | 1      | 3.13%   |
| Seagate ST1000LX015-1U7172 1TB                      | 1         | 1      | 3.13%   |
| Samsung Electronics SSD 870 EVO 500GB               | 1         | 1      | 3.13%   |
| Samsung Electronics SSD 850 EVO 500GB               | 1         | 1      | 3.13%   |
| Micron Technology MTFDDAK256MAY-1AH1ZABHA 256GB SSD | 1         | 1      | 3.13%   |
| Lexar 1TB SSD                                       | 1         | 1      | 3.13%   |
| Leven JAJS600M256C 256GB                            | 1         | 1      | 3.13%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 3      | 3.13%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 3.13%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 3.13%   |
| HGST HTS541075A9E680 752GB                          | 1         | 1      | 3.13%   |
| A-DATA Technology IM2P33F3 NVMe 512GB               | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 18.75%  |
| Seagate             | 5         | 5      | 15.63%  |
| HGST                | 5         | 6      | 15.63%  |
| Toshiba             | 4         | 4      | 12.5%   |
| SK hynix            | 4         | 4      | 12.5%   |
| Samsung Electronics | 2         | 2      | 6.25%   |
| Team                | 1         | 1      | 3.13%   |
| Micron Technology   | 1         | 1      | 3.13%   |
| Lexar               | 1         | 1      | 3.13%   |
| Leven               | 1         | 1      | 3.13%   |
| Hitachi             | 1         | 3      | 3.13%   |
| A-DATA Technology   | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 29.41%  |
| HGST    | 5         | 6      | 29.41%  |
| WDC     | 4         | 4      | 23.53%  |
| Toshiba | 2         | 2      | 11.76%  |
| Hitachi | 1         | 3      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 20     | 53.13%  |
| SSD  | 8         | 8      | 25%     |
| NVMe | 7         | 7      | 21.88%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1038      | 1517   | 71.34%  |
| Works    | 384       | 493    | 26.39%  |
| Malfunc  | 32        | 35     | 2.2%    |
| Failed   | 1         | 1      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 815       | 45.63%  |
| Samsung Electronics            | 261       | 14.61%  |
| AMD                            | 178       | 9.97%   |
| SanDisk                        | 122       | 6.83%   |
| SK hynix                       | 92        | 5.15%   |
| Micron Technology              | 58        | 3.25%   |
| Phison Electronics             | 39        | 2.18%   |
| Toshiba America Info Systems   | 31        | 1.74%   |
| Kingston Technology Company    | 30        | 1.68%   |
| Nvidia                         | 24        | 1.34%   |
| Micron/Crucial Technology      | 22        | 1.23%   |
| KIOXIA                         | 22        | 1.23%   |
| ADATA Technology               | 18        | 1.01%   |
| Silicon Motion                 | 15        | 0.84%   |
| Solid State Storage Technology | 13        | 0.73%   |
| Union Memory (Shenzhen)        | 10        | 0.56%   |
| Apple                          | 9         | 0.5%    |
| Marvell Technology Group       | 8         | 0.45%   |
| Shenzhen Longsys Electronics   | 5         | 0.28%   |
| Realtek Semiconductor          | 4         | 0.22%   |
| Seagate Technology             | 2         | 0.11%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.11%   |
| INNOGRIT                       | 2         | 0.11%   |
| Yangtze Memory Technologies    | 1         | 0.06%   |
| O2 Micro                       | 1         | 0.06%   |
| Netac Technology               | 1         | 0.06%   |
| Lite-On Technology             | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 171       | 9.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 100       | 5.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 91        | 4.84%   |
| Intel Volume Management Device NVMe RAID Controller                            | 81        | 4.31%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 71        | 3.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 70        | 3.72%   |
| Micron NVMe Storage Controller                                                 | 57        | 3.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 57        | 3.03%   |
| Samsung NVMe SSD Controller 980                                                | 53        | 2.82%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 51        | 2.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 51        | 2.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 48        | 2.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 43        | 2.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 37        | 1.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 37        | 1.97%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 33        | 1.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 31        | 1.65%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 26        | 1.38%   |
| Intel SSD 660P Series                                                          | 25        | 1.33%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 25        | 1.33%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 23        | 1.22%   |
| Intel Tiger Lake-LP SATA Controller                                            | 23        | 1.22%   |
| SanDisk Non-Volatile memory controller                                         | 22        | 1.17%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 21        | 1.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 21        | 1.12%   |
| Samsung Electronics SATA controller                                            | 20        | 1.06%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 20        | 1.06%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 20        | 1.06%   |
| Phison E12 NVMe Controller                                                     | 18        | 0.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 18        | 0.96%   |
| Intel Comet Lake SATA AHCI Controller                                          | 17        | 0.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 17        | 0.9%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 14        | 0.74%   |
| Nvidia MCP79 AHCI Controller                                                   | 14        | 0.74%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 14        | 0.74%   |
| Kingston Company Company Non-Volatile memory controller                        | 14        | 0.74%   |
| Solid State Storage Non-Volatile memory controller                             | 13        | 0.69%   |
| SK hynix Non-Volatile memory controller                                        | 13        | 0.69%   |
| Phison PS5013 E13 NVMe Controller                                              | 13        | 0.69%   |
| Intel Non-Volatile memory controller                                           | 13        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 873       | 49.02%  |
| NVMe | 714       | 40.09%  |
| RAID | 159       | 8.93%   |
| IDE  | 35        | 1.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1059      | 76.96%  |
| AMD    | 317       | 23.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 34        | 2.47%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 31        | 2.25%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 30        | 2.18%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 24        | 1.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 24        | 1.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 23        | 1.67%   |
| Intel 12th Gen Core i7-12700H                 | 23        | 1.67%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 22        | 1.6%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 22        | 1.6%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 19        | 1.38%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 19        | 1.38%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 18        | 1.31%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 1.23%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 17        | 1.23%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 17        | 1.23%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 1.16%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 1.02%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 0.94%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 13        | 0.94%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 0.87%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 12        | 0.87%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 12        | 0.87%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 12        | 0.87%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 0.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 11        | 0.8%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 11        | 0.8%    |
| AMD Ryzen 7 6800H with Radeon Graphics        | 11        | 0.8%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 10        | 0.73%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 10        | 0.73%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 10        | 0.73%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 9         | 0.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 0.65%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 0.65%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 9         | 0.65%   |
| Intel 12th Gen Core i7-1260P                  | 9         | 0.65%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 9         | 0.65%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 8         | 0.58%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 8         | 0.58%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 8         | 0.58%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 8         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 346       | 25.15%  |
| Intel Core i5           | 300       | 21.8%   |
| Other                   | 221       | 16.06%  |
| AMD Ryzen 7             | 108       | 7.85%   |
| AMD Ryzen 5             | 91        | 6.61%   |
| Intel Core i3           | 73        | 5.31%   |
| Intel Core 2 Duo        | 44        | 3.2%    |
| Intel Celeron           | 43        | 3.13%   |
| AMD Ryzen 9             | 21        | 1.53%   |
| AMD Ryzen 7 PRO         | 18        | 1.31%   |
| AMD Ryzen 3             | 13        | 0.94%   |
| Intel Pentium           | 12        | 0.87%   |
| AMD A8                  | 11        | 0.8%    |
| AMD A10                 | 11        | 0.8%    |
| AMD A6                  | 9         | 0.65%   |
| Intel Core i9           | 7         | 0.51%   |
| AMD Ryzen 5 PRO         | 7         | 0.51%   |
| Intel Pentium Dual-Core | 5         | 0.36%   |
| Intel Xeon              | 4         | 0.29%   |
| AMD A4                  | 4         | 0.29%   |
| Intel Pentium Silver    | 3         | 0.22%   |
| Intel Genuine           | 2         | 0.15%   |
| Intel Core M            | 2         | 0.15%   |
| AMD Ryzen 3 PRO         | 2         | 0.15%   |
| AMD Phenom II           | 2         | 0.15%   |
| AMD E1                  | 2         | 0.15%   |
| AMD E                   | 2         | 0.15%   |
| AMD Athlon X2           | 2         | 0.15%   |
| AMD Athlon              | 2         | 0.15%   |
| Intel Pentium Gold      | 1         | 0.07%   |
| Intel Core m3           | 1         | 0.07%   |
| Intel Core 2 Quad       | 1         | 0.07%   |
| Intel Core 2            | 1         | 0.07%   |
| Intel Atom              | 1         | 0.07%   |
| AMD Turion II           | 1         | 0.07%   |
| AMD Turion 64 X2 Mobile | 1         | 0.07%   |
| AMD E2                  | 1         | 0.07%   |
| AMD A12                 | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 485       | 35.25%  |
| 4      | 470       | 34.16%  |
| 8      | 187       | 13.59%  |
| 6      | 154       | 11.19%  |
| 14     | 39        | 2.83%   |
| 12     | 20        | 1.45%   |
| 10     | 15        | 1.09%   |
| 1      | 4         | 0.29%   |
| 16     | 1         | 0.07%   |
| 3      | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1376      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1197      | 86.93%  |
| 1      | 180       | 13.07%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1376      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 999       | 71.61%  |
| 0x806c1    | 35        | 2.51%   |
| 0x0a50000c | 30        | 2.15%   |
| 0x806d1    | 23        | 1.65%   |
| 0x906a3    | 22        | 1.58%   |
| 0xa0652    | 19        | 1.36%   |
| 0x806ec    | 19        | 1.36%   |
| 0x806ea    | 19        | 1.36%   |
| 0x906ea    | 16        | 1.15%   |
| 0x306a9    | 16        | 1.15%   |
| 0x08608103 | 13        | 0.93%   |
| 0x406e3    | 12        | 0.86%   |
| 0x0a404101 | 12        | 0.86%   |
| 0x40651    | 11        | 0.79%   |
| 0x08600106 | 11        | 0.79%   |
| 0x806e9    | 10        | 0.72%   |
| 0x906a4    | 8         | 0.57%   |
| 0x306d4    | 8         | 0.57%   |
| 0x1067a    | 8         | 0.57%   |
| 0x08600104 | 8         | 0.57%   |
| 0x08108109 | 8         | 0.57%   |
| 0x906e9    | 7         | 0.5%    |
| 0x706e5    | 7         | 0.5%    |
| 0x506e3    | 7         | 0.5%    |
| 0x306c3    | 7         | 0.5%    |
| 0x206a7    | 7         | 0.5%    |
| 0x0a404102 | 6         | 0.43%   |
| 0x806eb    | 5         | 0.36%   |
| 0x706a8    | 4         | 0.29%   |
| 0x0a50000d | 4         | 0.29%   |
| 0x08600103 | 4         | 0.29%   |
| 0x906c0    | 3         | 0.22%   |
| 0x806c2    | 3         | 0.22%   |
| 0x08608102 | 3         | 0.22%   |
| 0x08108102 | 3         | 0.22%   |
| 0xa0660    | 2         | 0.14%   |
| 0x906ed    | 2         | 0.14%   |
| 0x0810100b | 2         | 0.14%   |
| 0x07030106 | 2         | 0.14%   |
| 0x07030105 | 2         | 0.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 258       | 18.71%  |
| Unknown          | 140       | 10.15%  |
| Haswell          | 111       | 8.05%   |
| TigerLake        | 98        | 7.11%   |
| Zen 3            | 83        | 6.02%   |
| IvyBridge        | 75        | 5.44%   |
| SandyBridge      | 74        | 5.37%   |
| Skylake          | 63        | 4.57%   |
| Broadwell        | 60        | 4.35%   |
| CometLake        | 53        | 3.84%   |
| Zen 2            | 51        | 3.7%    |
| Zen+             | 49        | 3.55%   |
| Penryn           | 47        | 3.41%   |
| IceLake          | 41        | 2.97%   |
| Westmere         | 33        | 2.39%   |
| Alderlake Hybrid | 31        | 2.25%   |
| Goldmont plus    | 20        | 1.45%   |
| Silvermont       | 17        | 1.23%   |
| Excavator        | 14        | 1.02%   |
| Puma             | 13        | 0.94%   |
| Zen              | 11        | 0.8%    |
| Piledriver       | 9         | 0.65%   |
| K10 Llano        | 5         | 0.36%   |
| Core             | 5         | 0.36%   |
| Tremont          | 3         | 0.22%   |
| Nehalem          | 3         | 0.22%   |
| K10              | 3         | 0.22%   |
| Steamroller      | 2         | 0.15%   |
| K8 Hammer        | 2         | 0.15%   |
| Bobcat           | 2         | 0.15%   |
| K8 & K10 hybrid  | 1         | 0.07%   |
| Jaguar           | 1         | 0.07%   |
| Goldmont         | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 970       | 52.83%  |
| Nvidia | 498       | 27.12%  |
| AMD    | 368       | 20.04%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 90        | 4.8%    |
| Intel 3rd Gen Core processor Graphics Controller                                      | 70        | 3.74%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 68        | 3.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 67        | 3.58%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 59        | 3.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 58        | 3.09%   |
| Intel UHD Graphics 620                                                                | 56        | 2.99%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 56        | 2.99%   |
| AMD Renoir                                                                            | 51        | 2.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 48        | 2.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 43        | 2.29%   |
| AMD Lucienne                                                                          | 41        | 2.19%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 40        | 2.13%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 40        | 2.13%   |
| Intel HD Graphics 5500                                                                | 40        | 2.13%   |
| Intel HD Graphics 620                                                                 | 38        | 2.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 37        | 1.97%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 35        | 1.87%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 33        | 1.76%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 31        | 1.65%   |
| AMD Rembrandt [Radeon 680M]                                                           | 28        | 1.49%   |
| Intel Core Processor Integrated Graphics Controller                                   | 27        | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 26        | 1.39%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 24        | 1.28%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 22        | 1.17%   |
| Intel HD Graphics 630                                                                 | 22        | 1.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 19        | 1.01%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 18        | 0.96%   |
| Intel HD Graphics 530                                                                 | 18        | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 17        | 0.91%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 17        | 0.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 17        | 0.91%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 16        | 0.85%   |
| Nvidia TU117M                                                                         | 14        | 0.75%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 14        | 0.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 13        | 0.69%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 13        | 0.69%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 12        | 0.64%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 11        | 0.59%   |
| Nvidia C79 [GeForce 9400M]                                                            | 11        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 607       | 43.92%  |
| Intel + Nvidia     | 320       | 23.15%  |
| 1 x AMD            | 208       | 15.05%  |
| AMD + Nvidia       | 92        | 6.66%   |
| 1 x Nvidia         | 80        | 5.79%   |
| Intel + AMD        | 41        | 2.97%   |
| 2 x AMD            | 27        | 1.95%   |
| 2 x Nvidia         | 3         | 0.22%   |
| Other              | 2         | 0.14%   |
| Intel + 2 x Nvidia | 2         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 972       | 70.23%  |
| Proprietary | 391       | 28.25%  |
| Unknown     | 21        | 1.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1201      | 86.22%  |
| 0.01-0.5   | 60        | 4.31%   |
| 1.01-2.0   | 33        | 2.37%   |
| 3.01-4.0   | 31        | 2.23%   |
| 5.01-6.0   | 26        | 1.87%   |
| 7.01-8.0   | 21        | 1.51%   |
| 0.51-1.0   | 13        | 0.93%   |
| 8.01-16.0  | 5         | 0.36%   |
| 2.01-3.0   | 3         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 301       | 18.59%  |
| BOE                     | 236       | 14.58%  |
| Chimei Innolux          | 232       | 14.33%  |
| LG Display              | 204       | 12.6%   |
| Samsung Electronics     | 126       | 7.78%   |
| Apple                   | 78        | 4.82%   |
| Dell                    | 52        | 3.21%   |
| Goldstar                | 50        | 3.09%   |
| Sharp                   | 49        | 3.03%   |
| PANDA                   | 45        | 2.78%   |
| Lenovo                  | 23        | 1.42%   |
| InfoVision              | 19        | 1.17%   |
| Acer                    | 19        | 1.17%   |
| CSO                     | 18        | 1.11%   |
| Hewlett-Packard         | 16        | 0.99%   |
| Chi Mei Optoelectronics | 14        | 0.86%   |
| ASUSTek Computer        | 14        | 0.86%   |
| Philips                 | 12        | 0.74%   |
| AOC                     | 11        | 0.68%   |
| BenQ                    | 8         | 0.49%   |
| Ancor Communications    | 8         | 0.49%   |
| TMX                     | 7         | 0.43%   |
| ViewSonic               | 5         | 0.31%   |
| Sony                    | 4         | 0.25%   |
| Panasonic               | 4         | 0.25%   |
| MSI                     | 4         | 0.25%   |
| Vizio                   | 3         | 0.19%   |
| TCL                     | 3         | 0.19%   |
| JDI                     | 3         | 0.19%   |
| Iiyama                  | 3         | 0.19%   |
| Hitachi                 | 3         | 0.19%   |
| Vestel Elektronik       | 2         | 0.12%   |
| Unknown                 | 2         | 0.12%   |
| Toshiba                 | 2         | 0.12%   |
| Sceptre Tech            | 2         | 0.12%   |
| NEC Computers           | 2         | 0.12%   |
| HKC                     | 2         | 0.12%   |
| Denver                  | 2         | 0.12%   |
| DENON                   | 2         | 0.12%   |
| ___                     | 1         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch | 17        | 1.04%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch   | 15        | 0.92%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch          | 14        | 0.86%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch | 14        | 0.86%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch | 13        | 0.79%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch | 10        | 0.61%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch  | 10        | 0.61%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch   | 10        | 0.61%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch    | 10        | 0.61%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch     | 9         | 0.55%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch     | 8         | 0.49%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch | 8         | 0.49%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch             | 8         | 0.49%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch     | 7         | 0.43%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch            | 7         | 0.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch      | 6         | 0.37%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch      | 6         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch | 6         | 0.37%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch            | 6         | 0.37%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch            | 6         | 0.37%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch   | 6         | 0.37%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch   | 6         | 0.37%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch   | 6         | 0.37%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch    | 6         | 0.37%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch   | 6         | 0.37%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch             | 6         | 0.37%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch          | 5         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch  | 5         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch  | 5         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch  | 5         | 0.31%   |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch            | 5         | 0.31%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch   | 5         | 0.31%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x194mm 15.5-inch   | 5         | 0.31%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch    | 5         | 0.31%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch   | 5         | 0.31%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch    | 5         | 0.31%   |
| TMX LCD Monitor TMX1560 1920x1080 344x194mm 15.5-inch            | 4         | 0.24%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch          | 4         | 0.24%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch          | 4         | 0.24%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch          | 4         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 738       | 48.52%  |
| 1366x768 (WXGA)    | 321       | 21.1%   |
| 3840x2160 (4K)     | 72        | 4.73%   |
| 2560x1440 (QHD)    | 62        | 4.08%   |
| 1600x900 (HD+)     | 52        | 3.42%   |
| 1920x1200 (WUXGA)  | 43        | 2.83%   |
| 2560x1600          | 42        | 2.76%   |
| 1440x900 (WXGA+)   | 29        | 1.91%   |
| 1280x800 (WXGA)    | 29        | 1.91%   |
| 2880x1800          | 28        | 1.84%   |
| 3440x1440          | 14        | 0.92%   |
| 3840x2400          | 10        | 0.66%   |
| 2560x1080          | 10        | 0.66%   |
| 1280x1024 (SXGA)   | 7         | 0.46%   |
| 2256x1504          | 6         | 0.39%   |
| 2160x1440          | 6         | 0.39%   |
| 3200x1800 (QHD+)   | 5         | 0.33%   |
| 1360x768           | 5         | 0.33%   |
| 3456x2160          | 4         | 0.26%   |
| 3200x2000          | 4         | 0.26%   |
| 3072x1920          | 4         | 0.26%   |
| 1680x1050 (WSXGA+) | 4         | 0.26%   |
| 1920x540           | 3         | 0.2%    |
| 800x1280           | 2         | 0.13%   |
| 3840x1100          | 2         | 0.13%   |
| 3840x1080          | 2         | 0.13%   |
| 3000x2000          | 2         | 0.13%   |
| 2304x1440          | 2         | 0.13%   |
| 1920x1280          | 2         | 0.13%   |
| 1280x720 (HD)      | 2         | 0.13%   |
| 3840x1200          | 1         | 0.07%   |
| 3120x2080          | 1         | 0.07%   |
| 2560x1700          | 1         | 0.07%   |
| 1920x515           | 1         | 0.07%   |
| 1600x2560          | 1         | 0.07%   |
| 1600x1200          | 1         | 0.07%   |
| 1400x1050          | 1         | 0.07%   |
| 1280x1080          | 1         | 0.07%   |
| Unknown            | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 646       | 39.9%   |
| 13      | 281       | 17.36%  |
| 14      | 185       | 11.43%  |
| 17      | 104       | 6.42%   |
| 27      | 60        | 3.71%   |
| 24      | 52        | 3.21%   |
| 23      | 43        | 2.66%   |
| 16      | 39        | 2.41%   |
| 12      | 34        | 2.1%    |
| 21      | 27        | 1.67%   |
| 34      | 21        | 1.3%    |
| 31      | 20        | 1.24%   |
| 11      | 16        | 0.99%   |
| 19      | 12        | 0.74%   |
| Unknown | 10        | 0.62%   |
| 32      | 9         | 0.56%   |
| 84      | 8         | 0.49%   |
| 18      | 7         | 0.43%   |
| 40      | 6         | 0.37%   |
| 72      | 5         | 0.31%   |
| 35      | 4         | 0.25%   |
| 22      | 4         | 0.25%   |
| 20      | 4         | 0.25%   |
| 48      | 3         | 0.19%   |
| 54      | 2         | 0.12%   |
| 49      | 2         | 0.12%   |
| 29      | 2         | 0.12%   |
| 28      | 2         | 0.12%   |
| 25      | 2         | 0.12%   |
| 74      | 1         | 0.06%   |
| 60      | 1         | 0.06%   |
| 57      | 1         | 0.06%   |
| 47      | 1         | 0.06%   |
| 43      | 1         | 0.06%   |
| 37      | 1         | 0.06%   |
| 33      | 1         | 0.06%   |
| 8       | 1         | 0.06%   |
| 7       | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 993       | 61.95%  |
| 201-300     | 194       | 12.1%   |
| 501-600     | 138       | 8.61%   |
| 351-400     | 119       | 7.42%   |
| 401-500     | 48        | 2.99%   |
| 601-700     | 33        | 2.06%   |
| 701-800     | 31        | 1.93%   |
| 1501-2000   | 14        | 0.87%   |
| 801-900     | 11        | 0.69%   |
| 1001-1500   | 10        | 0.62%   |
| Unknown     | 10        | 0.62%   |
| 101-200     | 1         | 0.06%   |
| 1-100       | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1147      | 80.95%  |
| 16/10   | 200       | 14.11%  |
| 21/9    | 26        | 1.83%   |
| 3/2     | 20        | 1.41%   |
| 5/4     | 8         | 0.56%   |
| 32/9    | 3         | 0.21%   |
| Unknown | 3         | 0.21%   |
| 4/3     | 2         | 0.14%   |
| 3.40    | 2         | 0.14%   |
| 3.73    | 1         | 0.07%   |
| 3.20    | 1         | 0.07%   |
| 0.67    | 1         | 0.07%   |
| 0.63    | 1         | 0.07%   |
| 0.62    | 1         | 0.07%   |
| 0.56    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 647       | 40.04%  |
| 81-90          | 364       | 22.52%  |
| 201-250        | 104       | 6.44%   |
| 71-80          | 97        | 6%      |
| 121-130        | 95        | 5.88%   |
| 301-350        | 60        | 3.71%   |
| 351-500        | 56        | 3.47%   |
| 111-120        | 36        | 2.23%   |
| 61-70          | 32        | 1.98%   |
| 151-200        | 23        | 1.42%   |
| More than 1000 | 21        | 1.3%    |
| 51-60          | 18        | 1.11%   |
| 251-300        | 17        | 1.05%   |
| 501-1000       | 11        | 0.68%   |
| 141-150        | 10        | 0.62%   |
| Unknown        | 10        | 0.62%   |
| 131-140        | 7         | 0.43%   |
| 91-100         | 6         | 0.37%   |
| 1-40           | 2         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 721       | 45.52%  |
| 101-120       | 389       | 24.56%  |
| 51-100        | 207       | 13.07%  |
| 161-240       | 166       | 10.48%  |
| More than 240 | 73        | 4.61%   |
| 1-50          | 18        | 1.14%   |
| Unknown       | 10        | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1080      | 77.42%  |
| 2     | 242       | 17.35%  |
| 3     | 37        | 2.65%   |
| 0     | 34        | 2.44%   |
| 4     | 2         | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 742       | 34.43%  |
| Intel                                 | 735       | 34.11%  |
| Qualcomm Atheros                      | 254       | 11.79%  |
| Broadcom                              | 125       | 5.8%    |
| MediaTek                              | 67        | 3.11%   |
| Broadcom Limited                      | 53        | 2.46%   |
| ASIX Electronics                      | 21        | 0.97%   |
| Nvidia                                | 15        | 0.7%    |
| TP-Link                               | 14        | 0.65%   |
| Marvell Technology Group              | 14        | 0.65%   |
| Samsung Electronics                   | 13        | 0.6%    |
| DisplayLink                           | 12        | 0.56%   |
| Dell                                  | 9         | 0.42%   |
| Ralink                                | 8         | 0.37%   |
| Qualcomm                              | 8         | 0.37%   |
| Xiaomi                                | 7         | 0.32%   |
| Lenovo                                | 6         | 0.28%   |
| Ralink Technology                     | 5         | 0.23%   |
| JMicron Technology                    | 5         | 0.23%   |
| Sierra Wireless                       | 4         | 0.19%   |
| OnePlus Technology (Shenzhen)         | 4         | 0.19%   |
| NetGear                               | 4         | 0.19%   |
| Hewlett-Packard                       | 4         | 0.19%   |
| Ericsson Business Mobile Networks     | 3         | 0.14%   |
| OPPO Electronics                      | 2         | 0.09%   |
| Motorola PCS                          | 2         | 0.09%   |
| Huawei Technologies                   | 2         | 0.09%   |
| Google                                | 2         | 0.09%   |
| D-Link                                | 2         | 0.09%   |
| ASUSTek Computer                      | 2         | 0.09%   |
| Apple                                 | 2         | 0.09%   |
| ZyDAS                                 | 1         | 0.05%   |
| U-Blox                                | 1         | 0.05%   |
| Shenzhen Goodix Technology            | 1         | 0.05%   |
| Qualcomm Atheros Communications       | 1         | 0.05%   |
| Linksys                               | 1         | 0.05%   |
| Fibocom                               | 1         | 0.05%   |
| Arduino SA                            | 1         | 0.05%   |
| Accton Technology                     | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 464       | 18.2%   |
| Intel Wi-Fi 6 AX200                                               | 95        | 3.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 82        | 3.22%   |
| Intel Wi-Fi 6 AX201                                               | 73        | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 70        | 2.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 63        | 2.47%   |
| Intel Wireless 8265 / 8275                                        | 57        | 2.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 47        | 1.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 45        | 1.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 44        | 1.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 43        | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 42        | 1.65%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 41        | 1.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 39        | 1.53%   |
| Intel Wireless 7265                                               | 38        | 1.49%   |
| Intel Wireless 8260                                               | 35        | 1.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 35        | 1.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 32        | 1.25%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 32        | 1.25%   |
| Intel Wireless 7260                                               | 31        | 1.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 29        | 1.14%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 26        | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 24        | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 23        | 0.9%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 23        | 0.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 21        | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 21        | 0.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 21        | 0.82%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 20        | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 19        | 0.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 0.71%   |
| Broadcom BCM43142 802.11b/g/n                                     | 18        | 0.71%   |
| ASIX AX88179 Gigabit Ethernet                                     | 18        | 0.71%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 17        | 0.67%   |
| Intel Wireless-AC 9260                                            | 16        | 0.63%   |
| Intel Ethernet Connection I217-LM                                 | 16        | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 15        | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                             | 15        | 0.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 15        | 0.59%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 14        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 712       | 49.76%  |
| Qualcomm Atheros                      | 220       | 15.37%  |
| Realtek Semiconductor                 | 218       | 15.23%  |
| Broadcom                              | 109       | 7.62%   |
| MediaTek                              | 66        | 4.61%   |
| Broadcom Limited                      | 45        | 3.14%   |
| TP-Link                               | 11        | 0.77%   |
| Dell                                  | 9         | 0.63%   |
| Ralink                                | 8         | 0.56%   |
| Qualcomm                              | 8         | 0.56%   |
| Ralink Technology                     | 5         | 0.35%   |
| Sierra Wireless                       | 4         | 0.28%   |
| NetGear                               | 4         | 0.28%   |
| Hewlett-Packard                       | 2         | 0.14%   |
| D-Link                                | 2         | 0.14%   |
| ZyDAS                                 | 1         | 0.07%   |
| Qualcomm Atheros Communications       | 1         | 0.07%   |
| Linksys                               | 1         | 0.07%   |
| Fibocom                               | 1         | 0.07%   |
| ASUSTek Computer                      | 1         | 0.07%   |
| Arduino SA                            | 1         | 0.07%   |
| Accton Technology                     | 1         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 95        | 6.59%   |
| Intel Wi-Fi 6 AX201                                            | 73        | 5.07%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 63        | 4.37%   |
| Intel Wireless 8265 / 8275                                     | 57        | 3.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 47        | 3.26%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 45        | 3.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 44        | 3.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 43        | 2.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 42        | 2.91%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 41        | 2.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 39        | 2.71%   |
| Intel Wireless 7265                                            | 38        | 2.64%   |
| Intel Wireless 8260                                            | 35        | 2.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 32        | 2.22%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 32        | 2.22%   |
| Intel Wireless 7260                                            | 31        | 2.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 29        | 2.01%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 26        | 1.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 24        | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 23        | 1.6%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 23        | 1.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 21        | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 21        | 1.46%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 20        | 1.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 18        | 1.25%   |
| Broadcom BCM43142 802.11b/g/n                                  | 18        | 1.25%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 17        | 1.18%   |
| Intel Wireless-AC 9260                                         | 16        | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 15        | 1.04%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 14        | 0.97%   |
| Intel Centrino Advanced-N 6235                                 | 14        | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 11        | 0.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 11        | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 11        | 0.76%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 11        | 0.76%   |
| Intel Centrino Ultimate-N 6300                                 | 10        | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 9         | 0.62%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 9         | 0.62%   |
| MediaTek Wi-Fi 6E MT7922 160MHz Wireless Network Adapter       | 9         | 0.62%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 9         | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 647       | 59.8%   |
| Intel                         | 214       | 19.78%  |
| Qualcomm Atheros              | 59        | 5.45%   |
| Broadcom                      | 43        | 3.97%   |
| ASIX Electronics              | 21        | 1.94%   |
| Nvidia                        | 15        | 1.39%   |
| Marvell Technology Group      | 14        | 1.29%   |
| Samsung Electronics           | 13        | 1.2%    |
| DisplayLink                   | 12        | 1.11%   |
| Broadcom Limited              | 8         | 0.74%   |
| Xiaomi                        | 7         | 0.65%   |
| Lenovo                        | 6         | 0.55%   |
| JMicron Technology            | 5         | 0.46%   |
| OnePlus Technology (Shenzhen) | 4         | 0.37%   |
| TP-Link                       | 3         | 0.28%   |
| OPPO Electronics              | 2         | 0.18%   |
| Motorola PCS                  | 2         | 0.18%   |
| Google                        | 2         | 0.18%   |
| Apple                         | 2         | 0.18%   |
| Huawei Technologies           | 1         | 0.09%   |
| Hewlett-Packard               | 1         | 0.09%   |
| ASUSTek Computer              | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 464       | 42.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 82        | 7.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 70        | 6.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 35        | 3.18%   |
| Intel Ethernet Connection (4) I219-LM                             | 21        | 1.91%   |
| Realtek RTL8125 2.5GbE Controller                                 | 19        | 1.73%   |
| ASIX AX88179 Gigabit Ethernet                                     | 18        | 1.64%   |
| Intel Ethernet Connection I217-LM                                 | 16        | 1.46%   |
| Intel Ethernet Connection (3) I218-LM                             | 15        | 1.36%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 15        | 1.36%   |
| Nvidia MCP79 Ethernet                                             | 13        | 1.18%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 1.18%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 12        | 1.09%   |
| Intel Ethernet Connection I218-LM                                 | 10        | 0.91%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9         | 0.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 9         | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9         | 0.82%   |
| Intel Ethernet Connection (13) I219-V                             | 9         | 0.82%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8         | 0.73%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 8         | 0.73%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 7         | 0.64%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 7         | 0.64%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 0.64%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.64%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.55%   |
| Intel Ethernet Connection (6) I219-LM                             | 6         | 0.55%   |
| Intel Ethernet Connection (16) I219-V                             | 6         | 0.55%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 0.55%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 6         | 0.55%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 5         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.45%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 5         | 0.45%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.45%   |
| Intel Ethernet Connection I219-V                                  | 5         | 0.45%   |
| Intel Ethernet Connection (16) I219-LM                            | 5         | 0.45%   |
| Intel 82577LC Gigabit Network Connection                          | 5         | 0.45%   |
| DisplayLink Dell Universal Dock D6000                             | 5         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1362      | 56.8%   |
| Ethernet | 1026      | 42.79%  |
| Modem    | 7         | 0.29%   |
| Unknown  | 3         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1164      | 80.11%  |
| Ethernet | 289       | 19.89%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 921       | 66.93%  |
| 1     | 433       | 31.47%  |
| 0     | 13        | 0.94%   |
| 3     | 9         | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 971       | 69.91%  |
| Yes  | 418       | 30.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 628       | 53.04%  |
| Realtek Semiconductor           | 112       | 9.46%   |
| Qualcomm Atheros Communications | 104       | 8.78%   |
| Apple                           | 83        | 7.01%   |
| IMC Networks                    | 70        | 5.91%   |
| Foxconn / Hon Hai               | 47        | 3.97%   |
| Lite-On Technology              | 42        | 3.55%   |
| Broadcom                        | 33        | 2.79%   |
| Toshiba                         | 10        | 0.84%   |
| Dell                            | 10        | 0.84%   |
| Realtek                         | 9         | 0.76%   |
| Cambridge Silicon Radio         | 8         | 0.68%   |
| Hewlett-Packard                 | 7         | 0.59%   |
| Opticis                         | 3         | 0.25%   |
| Foxconn International           | 3         | 0.25%   |
| Taiyo Yuden                     | 2         | 0.17%   |
| Smart Modular Technologies      | 2         | 0.17%   |
| Ralink Technology               | 2         | 0.17%   |
| Ralink                          | 2         | 0.17%   |
| Fujitsu                         | 2         | 0.17%   |
| USI                             | 1         | 0.08%   |
| Micro Star International        | 1         | 0.08%   |
| MediaTek                        | 1         | 0.08%   |
| ASUSTek Computer                | 1         | 0.08%   |
| Actions                         | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 170       | 14.35%  |
| Intel AX201 Bluetooth                               | 164       | 13.84%  |
| Intel AX200 Bluetooth                               | 93        | 7.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 83        | 7%      |
| Realtek Bluetooth Radio                             | 79        | 6.67%   |
| Qualcomm Atheros  Bluetooth Device                  | 58        | 4.89%   |
| Apple Bluetooth Host Controller                     | 48        | 4.05%   |
| Intel Bluetooth Device                              | 42        | 3.54%   |
| Apple Bluetooth USB Host Controller                 | 29        | 2.45%   |
| IMC Networks Wireless_Device                        | 28        | 2.36%   |
| Realtek  Bluetooth 4.2 Adapter                      | 25        | 2.11%   |
| Intel AX210 Bluetooth                               | 25        | 2.11%   |
| Foxconn / Hon Hai Wireless_Device                   | 20        | 1.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 17        | 1.43%   |
| Foxconn / Hon Hai Bluetooth Device                  | 16        | 1.35%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 15        | 1.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 15        | 1.27%   |
| IMC Networks Bluetooth Radio                        | 15        | 1.27%   |
| IMC Networks Bluetooth Device                       | 14        | 1.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 13        | 1.1%    |
| Lite-On Wireless_Device                             | 12        | 1.01%   |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 0.93%   |
| Realtek Bluetooth Radio                             | 9         | 0.76%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 9         | 0.76%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 0.68%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 0.68%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 7         | 0.59%   |
| Lite-On Bluetooth Device                            | 7         | 0.59%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.51%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 0.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.42%   |
| Lite-On Bluetooth Radio                             | 5         | 0.42%   |
| IMC Networks Bluetooth USB Host Controller          | 5         | 0.42%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.42%   |
| Broadcom BCM20702A0                                 | 5         | 0.42%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 0.42%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 0.42%   |
| Toshiba BCM43142A0                                  | 4         | 0.34%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.34%   |
| Broadcom BCM43142A0 Bluetooth Device                | 4         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1034      | 56.81%  |
| AMD                                  | 337       | 18.52%  |
| Nvidia                               | 316       | 17.36%  |
| Logitech                             | 13        | 0.71%   |
| C-Media Electronics                  | 13        | 0.71%   |
| GN Netcom                            | 9         | 0.49%   |
| Sony                                 | 8         | 0.44%   |
| Realtek Semiconductor                | 8         | 0.44%   |
| Generalplus Technology               | 8         | 0.44%   |
| Kingston Technology                  | 7         | 0.38%   |
| Hewlett-Packard                      | 7         | 0.38%   |
| Lenovo                               | 6         | 0.33%   |
| Apple                                | 6         | 0.33%   |
| Texas Instruments                    | 4         | 0.22%   |
| SteelSeries ApS                      | 4         | 0.22%   |
| JMTek                                | 4         | 0.22%   |
| ASUSTek Computer                     | 4         | 0.22%   |
| Razer USA                            | 3         | 0.16%   |
| Focusrite-Novation                   | 3         | 0.16%   |
| Turtle Beach                         | 2         | 0.11%   |
| Sennheiser Communications            | 2         | 0.11%   |
| Plantronics                          | 2         | 0.11%   |
| FiiO Electronics Technology          | 2         | 0.11%   |
| DSEA A/S                             | 2         | 0.11%   |
| Corsair                              | 2         | 0.11%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.05%   |
| TerraTec Electronic                  | 1         | 0.05%   |
| Samson Technologies                  | 1         | 0.05%   |
| Reloop                               | 1         | 0.05%   |
| Pioneer DJ                           | 1         | 0.05%   |
| No brand                             | 1         | 0.05%   |
| Midiplus                             | 1         | 0.05%   |
| iConnectivity                        | 1         | 0.05%   |
| CMX Systems                          | 1         | 0.05%   |
| Blue Microphones                     | 1         | 0.05%   |
| Best Buy                             | 1         | 0.05%   |
| Audio-Technica                       | 1         | 0.05%   |
| Astro Gaming                         | 1         | 0.05%   |
| Antlion Audio                        | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 251       | 11.17%  |
| Intel Sunrise Point-LP HD Audio                                            | 140       | 6.23%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 140       | 6.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 98        | 4.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 85        | 3.78%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 73        | 3.25%   |
| Intel Cannon Lake PCH cAVS                                                 | 66        | 2.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 64        | 2.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 60        | 2.67%   |
| Intel Broadwell-U Audio Controller                                         | 60        | 2.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 57        | 2.54%   |
| Intel 8 Series HD Audio Controller                                         | 56        | 2.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 54        | 2.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 51        | 2.27%   |
| Intel Comet Lake PCH cAVS                                                  | 48        | 2.14%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 42        | 1.87%   |
| Nvidia GA106 High Definition Audio Controller                              | 40        | 1.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 39        | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 36        | 1.6%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 36        | 1.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 36        | 1.6%    |
| Nvidia Audio device                                                        | 35        | 1.56%   |
| Nvidia GA104 High Definition Audio Controller                              | 34        | 1.51%   |
| Intel Comet Lake PCH-LP cAVS                                               | 31        | 1.38%   |
| AMD FCH Azalia Controller                                                  | 30        | 1.34%   |
| Nvidia TU106 High Definition Audio Controller                              | 28        | 1.25%   |
| Intel CM238 HD Audio Controller                                            | 28        | 1.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 23        | 1.02%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 22        | 0.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 21        | 0.93%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 20        | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 19        | 0.85%   |
| AMD Kabini HDMI/DP Audio                                                   | 19        | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 17        | 0.76%   |
| Nvidia GP107GL High Definition Audio Controller                            | 16        | 0.71%   |
| Nvidia MCP79 High Definition Audio                                         | 15        | 0.67%   |
| Nvidia GP106 High Definition Audio Controller                              | 15        | 0.67%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 14        | 0.62%   |
| Nvidia GK107 HDMI Audio Controller                                         | 12        | 0.53%   |
| Nvidia GP104 High Definition Audio Controller                              | 11        | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 160       | 32%     |
| SK hynix            | 113       | 22.6%   |
| Micron Technology   | 74        | 14.8%   |
| Kingston            | 27        | 5.4%    |
| Crucial             | 26        | 5.2%    |
| Unknown             | 14        | 2.8%    |
| A-DATA Technology   | 9         | 1.8%    |
| Unknown             | 8         | 1.6%    |
| Smart               | 7         | 1.4%    |
| Neo Forza           | 7         | 1.4%    |
| Goldkey             | 6         | 1.2%    |
| Team                | 5         | 1%      |
| Ramaxel Technology  | 4         | 0.8%    |
| PNY                 | 4         | 0.8%    |
| G.Skill             | 4         | 0.8%    |
| Unknown (ABCD)      | 3         | 0.6%    |
| Nanya Technology    | 3         | 0.6%    |
| GSkill              | 3         | 0.6%    |
| Elpida              | 3         | 0.6%    |
| Corsair             | 3         | 0.6%    |
| Transcend           | 2         | 0.4%    |
| Smart Brazil        | 2         | 0.4%    |
| Gold Key            | 2         | 0.4%    |
| Avant               | 2         | 0.4%    |
| Unknown (8A02)      | 1         | 0.2%    |
| Unknown (09B6)      | 1         | 0.2%    |
| Unknown (09A4)      | 1         | 0.2%    |
| Timetec             | 1         | 0.2%    |
| Teikon              | 1         | 0.2%    |
| Kllisre             | 1         | 0.2%    |
| CSX                 | 1         | 0.2%    |
| ChangXin Memory     | 1         | 0.2%    |
| Apacer              | 1         | 0.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 2.49%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 2.1%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.91%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 1.53%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 1.53%   |
| Unknown                                                          | 8         | 1.53%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 7         | 1.34%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 6         | 1.15%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 6         | 1.15%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 6         | 1.15%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.96%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 0.96%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.96%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.96%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.76%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 0.76%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.76%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.76%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 0.76%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 4         | 0.76%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s        | 4         | 0.76%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.76%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.76%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 4         | 0.76%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.76%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 3         | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.57%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 3         | 0.57%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 3         | 0.57%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 3         | 0.57%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.57%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 3         | 0.57%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.57%   |
| Samsung RAM Module 4GB SODIMM DDR3 1867MT/s                      | 3         | 0.57%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 3         | 0.57%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.57%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 270       | 63.38%  |
| DDR3   | 71        | 16.67%  |
| LPDDR4 | 30        | 7.04%   |
| DDR5   | 19        | 4.46%   |
| LPDDR3 | 16        | 3.76%   |
| LPDDR5 | 14        | 3.29%   |
| SDRAM  | 3         | 0.7%    |
| DDR2   | 3         | 0.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 359       | 82.15%  |
| Row Of Chips | 73        | 16.7%   |
| Chip         | 3         | 0.69%   |
| DIMM         | 1         | 0.23%   |
| Unknown      | 1         | 0.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 211       | 45.87%  |
| 4096  | 106       | 23.04%  |
| 16384 | 86        | 18.7%   |
| 32768 | 27        | 5.87%   |
| 2048  | 26        | 5.65%   |
| 1024  | 4         | 0.87%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 160       | 34.93%  |
| 2667  | 89        | 19.43%  |
| 1600  | 48        | 10.48%  |
| 2400  | 29        | 6.33%   |
| 2133  | 23        | 5.02%   |
| 4800  | 19        | 4.15%   |
| 4267  | 18        | 3.93%   |
| 6400  | 14        | 3.06%   |
| 1867  | 9         | 1.97%   |
| 8400  | 7         | 1.53%   |
| 1334  | 7         | 1.53%   |
| 1333  | 7         | 1.53%   |
| 1067  | 6         | 1.31%   |
| 3266  | 5         | 1.09%   |
| 4266  | 4         | 0.87%   |
| 3733  | 3         | 0.66%   |
| 800   | 3         | 0.66%   |
| 2933  | 2         | 0.44%   |
| 2048  | 2         | 0.44%   |
| 4199  | 1         | 0.22%   |
| 1200  | 1         | 0.22%   |
| 1066  | 1         | 0.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 33.33%  |
| Canon               | 2         | 22.22%  |
| Xerox               | 1         | 11.11%  |
| Samsung Electronics | 1         | 11.11%  |
| ICS Advent          | 1         | 11.11%  |
| Brother Industries  | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Xerox B215                      | 1         | 11.11%  |
| Samsung M2020 Series            | 1         | 11.11%  |
| ICS Advent Parallel Adapter     | 1         | 11.11%  |
| HP OfficeJet 3830 series        | 1         | 11.11%  |
| HP Ink Tank Wireless 410 series | 1         | 11.11%  |
| HP Color LaserJet CP2025dn      | 1         | 11.11%  |
| Canon PIXMA MX920 Series        | 1         | 11.11%  |
| Canon E400 series               | 1         | 11.11%  |
| Brother HL-L2370DW series       | 1         | 11.11%  |

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
| Chicony Electronics                    | 281       | 22.57%  |
| IMC Networks                           | 130       | 10.44%  |
| Acer                                   | 130       | 10.44%  |
| Microdia                               | 124       | 9.96%   |
| Realtek Semiconductor                  | 100       | 8.03%   |
| Quanta                                 | 81        | 6.51%   |
| Sunplus Innovation Technology          | 61        | 4.9%    |
| Apple                                  | 59        | 4.74%   |
| Cheng Uei Precision Industry (Foxlink) | 36        | 2.89%   |
| Luxvisions Innotech Limited            | 31        | 2.49%   |
| Syntek                                 | 29        | 2.33%   |
| Lite-On Technology                     | 26        | 2.09%   |
| Suyin                                  | 24        | 1.93%   |
| Logitech                               | 17        | 1.37%   |
| Sonix Technology                       | 14        | 1.12%   |
| Bison Electronics                      | 13        | 1.04%   |
| Silicon Motion                         | 12        | 0.96%   |
| SunplusIT                              | 11        | 0.88%   |
| Samsung Electronics                    | 9         | 0.72%   |
| Z-Star Microelectronics                | 7         | 0.56%   |
| Alcor Micro                            | 5         | 0.4%    |
| Ricoh                                  | 4         | 0.32%   |
| Primax Electronics                     | 4         | 0.32%   |
| Microsoft                              | 4         | 0.32%   |
| Generalplus Technology                 | 4         | 0.32%   |
| Razer USA                              | 3         | 0.24%   |
| Tobii Technology AB                    | 2         | 0.16%   |
| Lenovo                                 | 2         | 0.16%   |
| HRY                                    | 2         | 0.16%   |
| ALi                                    | 2         | 0.16%   |
| Y Media                                | 1         | 0.08%   |
| USB Camera                             | 1         | 0.08%   |
| Trust                                  | 1         | 0.08%   |
| Tripath Technology                     | 1         | 0.08%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.08%   |
| Pixart Imaging                         | 1         | 0.08%   |
| Oculus VR                              | 1         | 0.08%   |
| MacroSilicon                           | 1         | 0.08%   |
| LG Electronics                         | 1         | 0.08%   |
| KYE Systems (Mouse Systems)            | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 69        | 5.51%   |
| Microdia Integrated_Webcam_HD                       | 65        | 5.19%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 50        | 3.99%   |
| Realtek Integrated_Webcam_HD                        | 43        | 3.43%   |
| IMC Networks Integrated Camera                      | 32        | 2.55%   |
| Acer BisonCam,NB Pro                                | 27        | 2.15%   |
| Chicony HD Webcam                                   | 25        | 2%      |
| Syntek Integrated Camera                            | 23        | 1.84%   |
| Chicony USB2.0 Camera                               | 23        | 1.84%   |
| Acer Integrated Camera                              | 23        | 1.84%   |
| Acer HD Webcam                                      | 22        | 1.76%   |
| Quanta HD User Facing                               | 21        | 1.68%   |
| Sunplus Integrated_Webcam_HD                        | 19        | 1.52%   |
| Apple Built-in iSight                               | 19        | 1.52%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 16        | 1.28%   |
| Apple FaceTime HD Camera                            | 16        | 1.28%   |
| Chicony HD User Facing                              | 14        | 1.12%   |
| Quanta HP HD Camera                                 | 13        | 1.04%   |
| Microdia Integrated Webcam                          | 13        | 1.04%   |
| Chicony HP HD Camera                                | 13        | 1.04%   |
| Sonix USB2.0 HD UVC WebCam                          | 11        | 0.88%   |
| Luxvisions Innotech Limited HP HD Camera            | 11        | 0.88%   |
| Chicony USB2.0 VGA UVC WebCam                       | 11        | 0.88%   |
| Realtek Integrated Webcam                           | 10        | 0.8%    |
| Lite-On Integrated Camera                           | 10        | 0.8%    |
| Chicony Integrated Camera (1280x720@30)             | 10        | 0.8%    |
| Chicony HP TrueVision HD Camera                     | 10        | 0.8%    |
| Acer SunplusIT Integrated Camera                    | 10        | 0.8%    |
| Samsung Galaxy A5 (MTP)                             | 9         | 0.72%   |
| Chicony TOSHIBA Web Camera - HD                     | 9         | 0.72%   |
| Acer Lenovo EasyCamera                              | 9         | 0.72%   |
| Quanta HP TrueVision HD Camera                      | 8         | 0.64%   |
| Quanta ACER HD User Facing                          | 8         | 0.64%   |
| Microdia USB 2.0 Camera                             | 8         | 0.64%   |
| Microdia Integrated Webcam HD                       | 8         | 0.64%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 8         | 0.64%   |
| Chicony USB 2.0 Camera                              | 8         | 0.64%   |
| Realtek USB2.0 HD UVC WebCam                        | 7         | 0.56%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 7         | 0.56%   |
| Chicony HP Wide Vision HD Camera                    | 7         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 83        | 35.02%  |
| Validity Sensors                   | 64        | 27%     |
| Shenzhen Goodix Technology         | 45        | 18.99%  |
| LighTuning Technology              | 11        | 4.64%   |
| Elan Microelectronics              | 11        | 4.64%   |
| Upek                               | 9         | 3.8%    |
| AuthenTec                          | 6         | 2.53%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 1.27%   |
| Focal-systems.Corp                 | 3         | 1.27%   |
| HOLTEK                             | 2         | 0.84%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 25        | 10.55%  |
| Shenzhen Goodix  Fingerprint Device                                        | 25        | 10.55%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 6.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 13        | 5.49%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 4.64%   |
| Shenzhen Goodix FingerPrint                                                | 11        | 4.64%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 3.8%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 8         | 3.38%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 3.38%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 2.95%   |
| Elan ELAN:ARM-M4                                                           | 7         | 2.95%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 2.53%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 2.53%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.11%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 2.11%   |
| Synaptics WBDI Device                                                      | 5         | 2.11%   |
| Synaptics UWP WBDI Device                                                  | 5         | 2.11%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 2.11%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 1.69%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.69%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.69%   |
| Synaptics UWP WBDI                                                         | 4         | 1.69%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.69%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.69%   |
| Unknown                                                                    | 4         | 1.69%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.27%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.27%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 1.27%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.27%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 1.27%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 0.84%   |
| Validity Sensors VFS491                                                    | 2         | 0.84%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.84%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.84%   |
| HOLTEK FocalTech Fingerprint Device                                        | 2         | 0.84%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.84%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.84%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.42%   |
| Synaptics  WBDI                                                            | 1         | 0.42%   |
| AuthenTec AES2810                                                          | 1         | 0.42%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 46        | 52.87%  |
| Alcor Micro           | 24        | 27.59%  |
| O2 Micro              | 6         | 6.9%    |
| Upek                  | 4         | 4.6%    |
| Lenovo                | 4         | 4.6%    |
| OmniKey               | 1         | 1.15%   |
| Gemalto (was Gemplus) | 1         | 1.15%   |
| Clay Logic            | 1         | 1.15%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 24        | 27.59%  |
| Broadcom 5880                                                                | 13        | 14.94%  |
| Broadcom 58200                                                               | 13        | 14.94%  |
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 12.64%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 10.34%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 5.75%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 4.6%    |
| Lenovo Integrated Smart Card Reader                                          | 4         | 4.6%    |
| OmniKey CardMan 4321                                                         | 1         | 1.15%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.15%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.15%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.15%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 833       | 59.8%   |
| 1     | 443       | 31.8%   |
| 2     | 99        | 7.11%   |
| 3     | 17        | 1.22%   |
| 4     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 227       | 33.68%  |
| Multimedia controller    | 120       | 17.8%   |
| Chipcard                 | 82        | 12.17%  |
| Graphics card            | 76        | 11.28%  |
| Net/wireless             | 67        | 9.94%   |
| Bluetooth                | 29        | 4.3%    |
| Camera                   | 26        | 3.86%   |
| Sound                    | 9         | 1.34%   |
| Net/ethernet             | 7         | 1.04%   |
| Storage                  | 6         | 0.89%   |
| Network                  | 6         | 0.89%   |
| Card reader              | 6         | 0.89%   |
| Modem                    | 5         | 0.74%   |
| Communication controller | 5         | 0.74%   |
| Storage/ide              | 2         | 0.3%    |
| Storage/nvme             | 1         | 0.15%   |

