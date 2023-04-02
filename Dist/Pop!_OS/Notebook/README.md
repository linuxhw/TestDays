Pop!_OS - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

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

Total: 6905

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
| Dell          | G3 3590                     | [f61ce9bb82](https://linux-hardware.org/?probe=f61ce9bb82) | Mar 28, 2023 |
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
| Apple         | MacBookPro9,1               | [f85095c103](https://linux-hardware.org/?probe=f85095c103) | Mar 13, 2023 |
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
| HP            | EliteBook 8570w             | [dfd9b7a9b9](https://linux-hardware.org/?probe=dfd9b7a9b9) | Mar 08, 2023 |
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
| TUXEDO        | InfinityBook S 14 Gen6      | [756ac6782b](https://linux-hardware.org/?probe=756ac6782b) | Mar 03, 2023 |
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
| Lenovo        | ThinkPad T460s 20FAS2M30... | [f201c986f0](https://linux-hardware.org/?probe=f201c986f0) | Jan 25, 2023 |
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
| Lenovo        | ThinkPad T460s 20FAS2M30... | [641654df50](https://linux-hardware.org/?probe=641654df50) | Jan 19, 2023 |
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
| Lenovo        | ThinkPad T460s 20FAS2M30... | [1178b43f82](https://linux-hardware.org/?probe=1178b43f82) | Jan 05, 2023 |
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
| Sony          | SVF15213CBB                 | [f8a95f249c](https://linux-hardware.org/?probe=f8a95f249c) | Dec 26, 2022 |
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
| Dell          | Vostro 15 3510              | [f2467d713d](https://linux-hardware.org/?probe=f2467d713d) | Dec 19, 2022 |
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
| Lenovo        | IdeaPad 500-15ISK 80NT      | [30cc472125](https://linux-hardware.org/?probe=30cc472125) | Dec 08, 2022 |
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
| Dell          | Inspiron 7720               | [a75b9a21f9](https://linux-hardware.org/?probe=a75b9a21f9) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [dce6415c9e](https://linux-hardware.org/?probe=dce6415c9e) | Nov 23, 2022 |
| Dell          | Inspiron 7720               | [ae4fc56cb3](https://linux-hardware.org/?probe=ae4fc56cb3) | Nov 23, 2022 |
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
| System76      | Galago Pro                  | [8728b448e9](https://linux-hardware.org/?probe=8728b448e9) | Nov 05, 2022 |
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

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Pop!_OS 22.04 | 1376      | 27.59%  |
| Pop!_OS 20.04 | 1150      | 23.06%  |
| Pop!_OS 21.04 | 959       | 19.23%  |
| Pop!_OS 20.10 | 856       | 17.16%  |
| Pop!_OS 21.10 | 600       | 12.03%  |
| Pop!_OS 19.10 | 30        | 0.6%    |
| Pop!_OS 18.04 | 7         | 0.14%   |
| Pop!_OS 19.04 | 6         | 0.12%   |
| Pop!_OS 18.10 | 4         | 0.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Pop!_OS | 4742      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.11.0-7620-generic      | 442       | 8.3%    |
| 5.8.0-7630-generic       | 381       | 7.16%   |
| 5.4.0-7634-generic       | 346       | 6.5%    |
| 5.19.0-76051900-generic  | 271       | 5.09%   |
| 5.13.0-7614-generic      | 262       | 4.92%   |
| 5.4.0-7642-generic       | 256       | 4.81%   |
| 6.0.12-76060006-generic  | 254       | 4.77%   |
| 5.17.5-76051705-generic  | 247       | 4.64%   |
| 5.8.0-7642-generic       | 242       | 4.55%   |
| 5.11.0-7614-generic      | 227       | 4.26%   |
| 5.13.0-7620-generic      | 218       | 4.09%   |
| 6.0.6-76060006-generic   | 161       | 3.02%   |
| 5.15.15-76051515-generic | 154       | 2.89%   |
| 5.16.11-76051611-generic | 138       | 2.59%   |
| 5.11.0-7612-generic      | 127       | 2.39%   |
| 5.15.5-76051505-generic  | 123       | 2.31%   |
| 5.18.10-76051810-generic | 120       | 2.25%   |
| 5.8.0-7625-generic       | 105       | 1.97%   |
| 5.17.15-76051715-generic | 105       | 1.97%   |
| 5.11.0-7633-generic      | 99        | 1.86%   |
| 5.15.8-76051508-generic  | 98        | 1.84%   |
| 5.16.19-76051619-generic | 95        | 1.78%   |
| 5.16.15-76051615-generic | 92        | 1.73%   |
| 5.4.0-7626-generic       | 84        | 1.58%   |
| 6.2.0-76060200-generic   | 70        | 1.31%   |
| 5.15.11-76051511-generic | 63        | 1.18%   |
| 6.0.2-76060002-generic   | 59        | 1.11%   |
| 5.15.23-76051523-generic | 56        | 1.05%   |
| 6.1.11-76060111-generic  | 53        | 1%      |
| 5.4.0-7625-generic       | 44        | 0.83%   |
| 5.4.0-7629-generic       | 35        | 0.66%   |
| 6.2.6-76060206-generic   | 30        | 0.56%   |
| 6.0.3-76060003-generic   | 23        | 0.43%   |
| 5.19.16-76051916-generic | 21        | 0.39%   |
| 5.3.0-7625-generic       | 10        | 0.19%   |
| 5.3.0-7648-generic       | 6         | 0.11%   |
| 5.11.0-051100-generic    | 6         | 0.11%   |
| 5.3.0-7642-generic       | 4         | 0.08%   |
| 5.3.0-7629-generic       | 4         | 0.08%   |
| 5.3.0-20-generic         | 4         | 0.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 873       | 16.72%  |
| 5.4.0   | 744       | 14.25%  |
| 5.8.0   | 698       | 13.37%  |
| 5.13.0  | 467       | 8.95%   |
| 5.19.0  | 273       | 5.23%   |
| 6.0.12  | 255       | 4.89%   |
| 5.17.5  | 250       | 4.79%   |
| 6.0.6   | 161       | 3.08%   |
| 5.15.15 | 154       | 2.95%   |
| 5.16.11 | 138       | 2.64%   |
| 5.15.5  | 123       | 2.36%   |
| 5.18.10 | 120       | 2.3%    |
| 5.17.15 | 105       | 2.01%   |
| 5.15.8  | 98        | 1.88%   |
| 5.16.19 | 95        | 1.82%   |
| 5.16.15 | 92        | 1.76%   |
| 6.2.0   | 70        | 1.34%   |
| 5.15.11 | 63        | 1.21%   |
| 6.0.2   | 60        | 1.15%   |
| 5.15.23 | 56        | 1.07%   |
| 6.1.11  | 53        | 1.02%   |
| 5.3.0   | 32        | 0.61%   |
| 6.2.6   | 31        | 0.59%   |
| 6.0.3   | 23        | 0.44%   |
| 5.19.16 | 21        | 0.4%    |
| 5.0.0   | 6         | 0.11%   |
| 4.18.0  | 6         | 0.11%   |
| 5.7.0   | 4         | 0.08%   |
| 5.15.0  | 4         | 0.08%   |
| 5.8.6   | 3         | 0.06%   |
| 5.8.11  | 3         | 0.06%   |
| 5.7.1   | 3         | 0.06%   |
| 5.14.0  | 3         | 0.06%   |
| 5.12.14 | 3         | 0.06%   |
| 5.10.0  | 3         | 0.06%   |
| 6.1.9   | 2         | 0.04%   |
| 6.1.0   | 2         | 0.04%   |
| 6.0.9   | 2         | 0.04%   |
| 6.0.0   | 2         | 0.04%   |
| 5.9.12  | 2         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 879       | 17%     |
| 5.4     | 745       | 14.41%  |
| 5.8     | 712       | 13.77%  |
| 5.15    | 494       | 9.56%   |
| 6.0     | 485       | 9.38%   |
| 5.13    | 478       | 9.25%   |
| 5.17    | 355       | 6.87%   |
| 5.16    | 323       | 6.25%   |
| 5.19    | 296       | 5.73%   |
| 5.18    | 124       | 2.4%    |
| 6.2     | 102       | 1.97%   |
| 6.1     | 60        | 1.16%   |
| 5.3     | 32        | 0.62%   |
| 5.10    | 18        | 0.35%   |
| 5.12    | 13        | 0.25%   |
| 5.7     | 11        | 0.21%   |
| 5.14    | 11        | 0.21%   |
| 5.9     | 9         | 0.17%   |
| 5.6     | 7         | 0.14%   |
| 4.18    | 7         | 0.14%   |
| 5.0     | 6         | 0.12%   |
| 4.15    | 2         | 0.04%   |
| 4.9     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 4742      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 4596      | 96.41%  |
| KDE5            | 41        | 0.86%   |
| Unknown         | 37        | 0.78%   |
| KDE             | 25        | 0.52%   |
| X-Cinnamon      | 16        | 0.34%   |
| GNOME Flashback | 10        | 0.21%   |
| XFCE            | 9         | 0.19%   |
| MATE            | 8         | 0.17%   |
| LXQt            | 8         | 0.17%   |
| Cinnamon        | 6         | 0.13%   |
| Unity           | 5         | 0.1%    |
| Budgie          | 4         | 0.08%   |
| Deepin          | 1         | 0.02%   |
| awesome         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 4591      | 96.33%  |
| Wayland | 152       | 3.19%   |
| Unknown | 16        | 0.34%   |
| Tty     | 7         | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3622      | 75.55%  |
| GDM     | 774       | 16.15%  |
| GDM3    | 384       | 8.01%   |
| SDDM    | 8         | 0.17%   |
| TDM     | 5         | 0.1%    |
| LightDM | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2757      | 57.8%   |
| pt_BR   | 352       | 7.38%   |
| en_GB   | 339       | 7.11%   |
| de_DE   | 198       | 4.15%   |
| C       | 119       | 2.49%   |
| it_IT   | 100       | 2.1%    |
| fr_FR   | 96        | 2.01%   |
| en_AU   | 96        | 2.01%   |
| es_ES   | 94        | 1.97%   |
| en_CA   | 84        | 1.76%   |
| ru_RU   | 65        | 1.36%   |
| Unknown | 49        | 1.03%   |
| pt_PT   | 41        | 0.86%   |
| pl_PL   | 40        | 0.84%   |
| sv_SE   | 33        | 0.69%   |
| en_IN   | 28        | 0.59%   |
| nl_NL   | 21        | 0.44%   |
| nb_NO   | 20        | 0.42%   |
| en_ZA   | 18        | 0.38%   |
| es_MX   | 17        | 0.36%   |
| fi_FI   | 16        | 0.34%   |
| tr_TR   | 13        | 0.27%   |
| en_NZ   | 13        | 0.27%   |
| fr_CA   | 11        | 0.23%   |
| es_AR   | 11        | 0.23%   |
| en_IE   | 10        | 0.21%   |
| cs_CZ   | 9         | 0.19%   |
| hu_HU   | 8         | 0.17%   |
| hr_HR   | 8         | 0.17%   |
| en_DK   | 8         | 0.17%   |
| da_DK   | 7         | 0.15%   |
| ro_RO   | 6         | 0.13%   |
| es_CL   | 6         | 0.13%   |
| de_CH   | 6         | 0.13%   |
| sk_SK   | 5         | 0.1%    |
| es_CO   | 5         | 0.1%    |
| zh_CN   | 4         | 0.08%   |
| nl_BE   | 4         | 0.08%   |
| en_IL   | 4         | 0.08%   |
| de_AT   | 4         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 3354      | 69.66%  |
| EFI  | 1461      | 30.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 4542      | 95.46%  |
| Btrfs   | 120       | 2.52%   |
| Overlay | 69        | 1.45%   |
| Xfs     | 19        | 0.4%    |
| Unknown | 7         | 0.15%   |
| Zfs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 3592      | 75.05%  |
| GPT     | 1087      | 22.71%  |
| MBR     | 107       | 2.24%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4640      | 97.58%  |
| Yes       | 115       | 2.42%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4330      | 90.91%  |
| Yes       | 433       | 9.09%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 923       | 19.46%  |
| Dell                   | 839       | 17.69%  |
| Hewlett-Packard        | 645       | 13.6%   |
| ASUSTek Computer       | 545       | 11.49%  |
| Acer                   | 376       | 7.93%   |
| Apple                  | 272       | 5.74%   |
| System76               | 172       | 3.63%   |
| MSI                    | 156       | 3.29%   |
| Toshiba                | 95        | 2%      |
| Samsung Electronics    | 84        | 1.77%   |
| HUAWEI                 | 56        | 1.18%   |
| Sony                   | 47        | 0.99%   |
| Notebook               | 43        | 0.91%   |
| Google                 | 38        | 0.8%    |
| Alienware              | 37        | 0.78%   |
| Fujitsu                | 29        | 0.61%   |
| Positivo               | 26        | 0.55%   |
| Razer                  | 24        | 0.51%   |
| Gigabyte Technology    | 18        | 0.38%   |
| Timi                   | 17        | 0.36%   |
| PC Specialist          | 16        | 0.34%   |
| TUXEDO                 | 14        | 0.3%    |
| LG Electronics         | 13        | 0.27%   |
| Framework              | 12        | 0.25%   |
| Unknown                | 12        | 0.25%   |
| Medion                 | 11        | 0.23%   |
| GPU Company            | 11        | 0.23%   |
| Packard Bell           | 10        | 0.21%   |
| Avell High Performance | 10        | 0.21%   |
| Eluktronics            | 7         | 0.15%   |
| Teclast                | 6         | 0.13%   |
| Panasonic              | 6         | 0.13%   |
| Intel                  | 6         | 0.13%   |
| Gateway                | 6         | 0.13%   |
| Clevo                  | 6         | 0.13%   |
| HONOR                  | 5         | 0.11%   |
| Chuwi                  | 5         | 0.11%   |
| SLIMBOOK               | 4         | 0.08%   |
| Schenker               | 4         | 0.08%   |
| Quanta                 | 4         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| System76 Oryx Pro                         | 42        | 0.89%   |
| System76 Lemur Pro                        | 38        | 0.8%    |
| Dell XPS 15 7590                          | 30        | 0.63%   |
| Apple MacBookPro9,2                       | 25        | 0.53%   |
| Unknown                                   | 24        | 0.51%   |
| System76 Gazelle                          | 23        | 0.49%   |
| System76 Galago Pro                       | 21        | 0.44%   |
| Dell XPS 15 9500                          | 21        | 0.44%   |
| Apple MacBookPro12,1                      | 20        | 0.42%   |
| HP Pavilion Notebook                      | 19        | 0.4%    |
| Apple MacBookPro8,1                       | 19        | 0.4%    |
| HP Notebook                               | 18        | 0.38%   |
| HP Pavilion 15                            | 17        | 0.36%   |
| System76 Darter Pro                       | 16        | 0.34%   |
| Apple MacBookAir7,2                       | 16        | 0.34%   |
| HP Pavilion dv6                           | 15        | 0.32%   |
| Dell XPS 15 9560                          | 14        | 0.3%    |
| Apple MacBookAir6,2                       | 14        | 0.3%    |
| Lenovo IdeaPad S145-15API 81V7            | 13        | 0.27%   |
| Dell XPS 15 9570                          | 13        | 0.27%   |
| Dell Latitude E6420                       | 13        | 0.27%   |
| Apple MacBookPro7,1                       | 13        | 0.27%   |
| Dell XPS 17 9700                          | 11        | 0.23%   |
| Dell XPS 13 9380                          | 11        | 0.23%   |
| Dell Latitude E7240                       | 11        | 0.23%   |
| Apple MacBookPro5,5                       | 11        | 0.23%   |
| Acer Aspire E5-575G                       | 11        | 0.23%   |
| Lenovo ThinkPad X1 Extreme 2nd 20QVCTO1WW | 10        | 0.21%   |
| Lenovo IdeaPad 330-15IKB 81FE             | 10        | 0.21%   |
| HP Pavilion Laptop 15-cw1xxx              | 10        | 0.21%   |
| HP Pavilion g6                            | 10        | 0.21%   |
| Framework Laptop                          | 10        | 0.21%   |
| Dell Inspiron N5110                       | 10        | 0.21%   |
| ASUS TUF Gaming FX505DT_FX505DT           | 10        | 0.21%   |
| Apple MacBook5,1                          | 10        | 0.21%   |
| Samsung 340XAA/350XAA/550XAA              | 9         | 0.19%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY      | 9         | 0.19%   |
| Dell XPS 13 9370                          | 9         | 0.19%   |
| Dell XPS 13 9310                          | 9         | 0.19%   |
| Dell Latitude E7470                       | 9         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 456       | 9.62%   |
| Dell Inspiron      | 271       | 5.71%   |
| Acer Aspire        | 256       | 5.4%    |
| Lenovo IdeaPad     | 254       | 5.36%   |
| Dell Latitude      | 200       | 4.22%   |
| Dell XPS           | 181       | 3.82%   |
| HP Pavilion        | 157       | 3.31%   |
| HP EliteBook       | 102       | 2.15%   |
| HP Laptop          | 91        | 1.92%   |
| ASUS VivoBook      | 86        | 1.81%   |
| Toshiba Satellite  | 83        | 1.75%   |
| ASUS ROG           | 77        | 1.62%   |
| HP ProBook         | 75        | 1.58%   |
| Lenovo Legion      | 69        | 1.46%   |
| Dell Precision     | 59        | 1.24%   |
| Acer Nitro         | 47        | 0.99%   |
| Dell Vostro        | 46        | 0.97%   |
| ASUS ASUS          | 44        | 0.93%   |
| System76 Oryx      | 42        | 0.89%   |
| System76 Lemur     | 41        | 0.86%   |
| Acer Swift         | 35        | 0.74%   |
| HP ENVY            | 33        | 0.7%    |
| Apple MacBookPro11 | 33        | 0.7%    |
| Apple MacBookPro9  | 32        | 0.67%   |
| ASUS ZenBook       | 31        | 0.65%   |
| ASUS TUF           | 30        | 0.63%   |
| HP OMEN            | 27        | 0.57%   |
| Apple MacBookPro8  | 27        | 0.57%   |
| System76 Gazelle   | 25        | 0.53%   |
| System76 Galago    | 24        | 0.51%   |
| Razer Blade        | 24        | 0.51%   |
| HP ZBook           | 24        | 0.51%   |
| Apple MacBookPro5  | 24        | 0.51%   |
| Unknown            | 24        | 0.51%   |
| Lenovo ThinkBook   | 23        | 0.49%   |
| Fujitsu LIFEBOOK   | 22        | 0.46%   |
| Apple MacBookPro12 | 20        | 0.42%   |
| HP Notebook        | 18        | 0.38%   |
| Lenovo Yoga        | 17        | 0.36%   |
| Dell G3            | 17        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 612       | 12.91%  |
| 2020    | 570       | 12.02%  |
| 2021    | 484       | 10.21%  |
| 2018    | 451       | 9.51%   |
| 2012    | 350       | 7.38%   |
| 2013    | 309       | 6.52%   |
| 2017    | 294       | 6.2%    |
| 2015    | 287       | 6.05%   |
| 2011    | 284       | 5.99%   |
| 2016    | 256       | 5.4%    |
| 2014    | 223       | 4.7%    |
| 2010    | 190       | 4.01%   |
| 2022    | 152       | 3.21%   |
| 2009    | 119       | 2.51%   |
| 2008    | 108       | 2.28%   |
| 2007    | 36        | 0.76%   |
| 2006    | 9         | 0.19%   |
| 2023    | 4         | 0.08%   |
| Unknown | 2         | 0.04%   |
| 2005    | 1         | 0.02%   |
| 2004    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4742      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4739      | 99.94%  |
| Enabled  | 3         | 0.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4597      | 96.94%  |
| Yes  | 145       | 3.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1405      | 29.37%  |
| 16.01-24.0  | 1080      | 22.58%  |
| 8.01-16.0   | 876       | 18.31%  |
| 3.01-4.0    | 717       | 14.99%  |
| 32.01-64.0  | 442       | 9.24%   |
| 64.01-256.0 | 94        | 1.97%   |
| 1.01-2.0    | 67        | 1.4%    |
| 24.01-32.0  | 66        | 1.38%   |
| 2.01-3.0    | 36        | 0.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1662      | 32.22%  |
| 1.01-2.0   | 1304      | 25.28%  |
| 4.01-8.0   | 970       | 18.8%   |
| 3.01-4.0   | 953       | 18.47%  |
| 8.01-16.0  | 227       | 4.4%    |
| 16.01-24.0 | 25        | 0.48%   |
| 0.51-1.0   | 10        | 0.19%   |
| 24.01-32.0 | 7         | 0.14%   |
| 0.01-0.5   | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3352      | 69.53%  |
| 2      | 1258      | 26.09%  |
| 3      | 155       | 3.22%   |
| 0      | 24        | 0.5%    |
| 4      | 23        | 0.48%   |
| 5      | 7         | 0.15%   |
| 7      | 1         | 0.02%   |
| 6      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3408      | 71.66%  |
| Yes       | 1348      | 28.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3780      | 79.33%  |
| No        | 985       | 20.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4686      | 98.76%  |
| No        | 59        | 1.24%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4004      | 83.71%  |
| No        | 779       | 16.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 1268      | 26.61%  |
| Brazil       | 491       | 10.3%   |
| Germany      | 287       | 6.02%   |
| UK           | 214       | 4.49%   |
| India        | 205       | 4.3%    |
| Canada       | 166       | 3.48%   |
| Italy        | 156       | 3.27%   |
| France       | 142       | 2.98%   |
| Australia    | 108       | 2.27%   |
| Netherlands  | 97        | 2.04%   |
| Russia       | 86        | 1.8%    |
| Sweden       | 81        | 1.7%    |
| Spain        | 75        | 1.57%   |
| Poland       | 70        | 1.47%   |
| Mexico       | 69        | 1.45%   |
| Portugal     | 68        | 1.43%   |
| Romania      | 54        | 1.13%   |
| Norway       | 52        | 1.09%   |
| Switzerland  | 48        | 1.01%   |
| South Africa | 46        | 0.97%   |
| Turkey       | 42        | 0.88%   |
| Indonesia    | 38        | 0.8%    |
| Greece       | 38        | 0.8%    |
| Finland      | 38        | 0.8%    |
| Philippines  | 37        | 0.78%   |
| Belgium      | 37        | 0.78%   |
| Argentina    | 35        | 0.73%   |
| New Zealand  | 32        | 0.67%   |
| Austria      | 32        | 0.67%   |
| Denmark      | 31        | 0.65%   |
| Chile        | 25        | 0.52%   |
| Czechia      | 23        | 0.48%   |
| Croatia      | 23        | 0.48%   |
| Hungary      | 22        | 0.46%   |
| Ireland      | 21        | 0.44%   |
| Colombia     | 21        | 0.44%   |
| Bulgaria     | 21        | 0.44%   |
| Vietnam      | 20        | 0.42%   |
| Malaysia     | 19        | 0.4%    |
| Japan        | 19        | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 53        | 1.07%   |
| Bengaluru      | 32        | 0.64%   |
| Milan          | 30        | 0.6%    |
| Brisbane       | 27        | 0.54%   |
| Sydney         | 26        | 0.52%   |
| Rio de Janeiro | 24        | 0.48%   |
| London         | 24        | 0.48%   |
| Dallas         | 24        | 0.48%   |
| Paris          | 23        | 0.46%   |
| New York       | 22        | 0.44%   |
| Moscow         | 22        | 0.44%   |
| Vienna         | 21        | 0.42%   |
| Melbourne      | 21        | 0.42%   |
| Bucharest      | 21        | 0.42%   |
| Berlin         | 21        | 0.42%   |
| Athens         | 21        | 0.42%   |
| Rome           | 19        | 0.38%   |
| Istanbul       | 19        | 0.38%   |
| Helsinki       | 19        | 0.38%   |
| Amsterdam      | 19        | 0.38%   |
| Chicago        | 18        | 0.36%   |
| Zagreb         | 17        | 0.34%   |
| Warsaw         | 17        | 0.34%   |
| Madrid         | 17        | 0.34%   |
| Johannesburg   | 17        | 0.34%   |
| Auckland       | 17        | 0.34%   |
| St Petersburg  | 16        | 0.32%   |
| Los Angeles    | 16        | 0.32%   |
| Toronto        | 15        | 0.3%    |
| Sofia          | 15        | 0.3%    |
| Oslo           | 15        | 0.3%    |
| Mexico City    | 15        | 0.3%    |
| Fortaleza      | 15        | 0.3%    |
| Brasília      | 15        | 0.3%    |
| Zurich         | 14        | 0.28%   |
| Stockholm      | 14        | 0.28%   |
| Lisbon         | 14        | 0.28%   |
| Denver         | 14        | 0.28%   |
| Calgary        | 14        | 0.28%   |
| Brooklyn       | 14        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 1112      | 1500   | 18.22%  |
| WDC                            | 650       | 741    | 10.65%  |
| Seagate                        | 600       | 707    | 9.83%   |
| SanDisk                        | 437       | 571    | 7.16%   |
| Toshiba                        | 393       | 462    | 6.44%   |
| Kingston                       | 321       | 381    | 5.26%   |
| SK hynix                       | 292       | 375    | 4.78%   |
| Unknown                        | 283       | 346    | 4.64%   |
| Crucial                        | 217       | 255    | 3.56%   |
| Intel                          | 196       | 245    | 3.21%   |
| HGST                           | 180       | 207    | 2.95%   |
| Micron Technology              | 165       | 184    | 2.7%    |
| Apple                          | 132       | 141    | 2.16%   |
| Hitachi                        | 95        | 104    | 1.56%   |
| A-DATA Technology              | 92        | 111    | 1.51%   |
| Phison                         | 74        | 91     | 1.21%   |
| China                          | 48        | 53     | 0.79%   |
| PNY                            | 47        | 57     | 0.77%   |
| LITEON                         | 43        | 49     | 0.7%    |
| KIOXIA                         | 42        | 51     | 0.69%   |
| Silicon Motion                 | 39        | 47     | 0.64%   |
| Micron/Crucial Technology      | 38        | 51     | 0.62%   |
| Transcend                      | 34        | 39     | 0.56%   |
| LITEONIT                       | 30        | 39     | 0.49%   |
| ADATA Technology               | 21        | 30     | 0.34%   |
| SPCC                           | 18        | 19     | 0.29%   |
| Fujitsu                        | 18        | 19     | 0.29%   |
| Team                           | 17        | 21     | 0.28%   |
| KingSpec                       | 17        | 19     | 0.28%   |
| JMicron Technology             | 17        | 23     | 0.28%   |
| Phison Electronics             | 16        | 18     | 0.26%   |
| Union Memory (Shenzhen)        | 15        | 18     | 0.25%   |
| Patriot                        | 14        | 16     | 0.23%   |
| Solid State Storage Technology | 13        | 16     | 0.21%   |
| OCZ                            | 13        | 13     | 0.21%   |
| Hewlett-Packard                | 13        | 15     | 0.21%   |
| Netac                          | 12        | 13     | 0.2%    |
| Corsair                        | 12        | 14     | 0.2%    |
| Unknown                        | 12        | 13     | 0.2%    |
| Realtek Semiconductor          | 10        | 10     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 103       | 1.61%   |
| Kingston SA400S37240G 240GB SSD                     | 86        | 1.34%   |
| Samsung NVMe SSD Drive 512GB                        | 80        | 1.25%   |
| HGST HTS721010A9E630 1TB                            | 76        | 1.19%   |
| Unknown MMC Card  64GB                              | 68        | 1.06%   |
| Samsung NVMe SSD Drive 1TB                          | 64        | 1%      |
| SK hynix NVMe SSD Drive 512GB                       | 59        | 0.92%   |
| Toshiba MQ01ABD100 1TB                              | 58        | 0.91%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 57        | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 54        | 0.84%   |
| SanDisk NVMe SSD Drive 512GB                        | 53        | 0.83%   |
| Samsung NVMe SSD Drive 500GB                        | 52        | 0.81%   |
| Unknown MMC Card  32GB                              | 49        | 0.77%   |
| Intel NVMe SSD Drive 512GB                          | 47        | 0.73%   |
| Toshiba MQ04ABF100 1TB                              | 46        | 0.72%   |
| WDC WD10SPZX-24Z10 1TB                              | 40        | 0.63%   |
| Samsung NVMe SSD Drive 1024GB                       | 40        | 0.63%   |
| SanDisk NVMe SSD Drive 1TB                          | 37        | 0.58%   |
| Seagate ST9500325AS 500GB                           | 36        | 0.56%   |
| Seagate ST1000LM049-2GH172 1TB                      | 35        | 0.55%   |
| SanDisk NVMe SSD Drive 256GB                        | 35        | 0.55%   |
| Samsung SSD 860 EVO 500GB                           | 35        | 0.55%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 33        | 0.52%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 32        | 0.5%    |
| SK hynix NVMe SSD Drive 1024GB                      | 31        | 0.48%   |
| Seagate ST500LT012-1DG142 500GB                     | 31        | 0.48%   |
| Samsung SSD 850 EVO 250GB                           | 31        | 0.48%   |
| Kingston SA400S37480G 480GB SSD                     | 31        | 0.48%   |
| Crucial CT240BX500SSD1 240GB                        | 31        | 0.48%   |
| Crucial CT500MX500SSD1 500GB                        | 30        | 0.47%   |
| Unknown MMC Card  128GB                             | 29        | 0.45%   |
| SK hynix NVMe SSD Drive 256GB                       | 29        | 0.45%   |
| SanDisk NVMe SSD Drive 500GB                        | 29        | 0.45%   |
| Toshiba NVMe SSD Drive 512GB                        | 28        | 0.44%   |
| HGST HTS541010A9E680 1TB                            | 28        | 0.44%   |
| Kingston SA400S37120G 120GB SSD                     | 27        | 0.42%   |
| Samsung SSD 860 EVO 1TB                             | 26        | 0.41%   |
| Samsung NVMe SSD Drive 2TB                          | 26        | 0.41%   |
| Micron NVMe SSD Drive 512GB                         | 26        | 0.41%   |
| Unknown SD/MMC/MS PRO 64GB                          | 25        | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 574       | 665    | 35.76%  |
| WDC                 | 401       | 440    | 24.98%  |
| Toshiba             | 241       | 272    | 15.02%  |
| HGST                | 180       | 207    | 11.21%  |
| Hitachi             | 95        | 104    | 5.92%   |
| Samsung Electronics | 30        | 31     | 1.87%   |
| Unknown             | 26        | 28     | 1.62%   |
| Fujitsu             | 18        | 19     | 1.12%   |
| Apple               | 16        | 18     | 1%      |
| SABRENT             | 6         | 8      | 0.37%   |
| ASMT                | 6         | 8      | 0.37%   |
| Intenso             | 3         | 4      | 0.19%   |
| PHD 3.0             | 2         | 2      | 0.12%   |
| JMicron Technology  | 2         | 5      | 0.12%   |
| USB3.0              | 1         | 1      | 0.06%   |
| RSH-339             | 1         | 1      | 0.06%   |
| HGST HDN            | 1         | 1      | 0.06%   |
| DAS                 | 1         | 4      | 0.06%   |
| Asm                 | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 449       | 596    | 21.6%   |
| Kingston            | 247       | 279    | 11.88%  |
| SanDisk             | 212       | 261    | 10.2%   |
| Crucial             | 202       | 240    | 9.72%   |
| WDC                 | 132       | 160    | 6.35%   |
| Apple               | 97        | 101    | 4.67%   |
| A-DATA Technology   | 61        | 72     | 2.93%   |
| SK hynix            | 52        | 61     | 2.5%    |
| Micron Technology   | 52        | 55     | 2.5%    |
| Toshiba             | 50        | 60     | 2.41%   |
| China               | 47        | 52     | 2.26%   |
| PNY                 | 46        | 56     | 2.21%   |
| Intel               | 41        | 45     | 1.97%   |
| LITEON              | 40        | 46     | 1.92%   |
| Transcend           | 33        | 38     | 1.59%   |
| LITEONIT            | 30        | 39     | 1.44%   |
| KingSpec            | 17        | 19     | 0.82%   |
| SPCC                | 16        | 17     | 0.77%   |
| Seagate             | 14        | 15     | 0.67%   |
| Patriot             | 14        | 16     | 0.67%   |
| OCZ                 | 13        | 13     | 0.63%   |
| Team                | 11        | 15     | 0.53%   |
| Netac               | 10        | 11     | 0.48%   |
| Hewlett-Packard     | 10        | 12     | 0.48%   |
| Lexar               | 9         | 9      | 0.43%   |
| JMicron Technology  | 9         | 10     | 0.43%   |
| Corsair             | 9         | 10     | 0.43%   |
| KingDian            | 7         | 8      | 0.34%   |
| Dogfish             | 7         | 10     | 0.34%   |
| Intenso             | 6         | 6      | 0.29%   |
| BHT                 | 6         | 6      | 0.29%   |
| Apacer              | 6         | 11     | 0.29%   |
| TO Exter            | 5         | 5      | 0.24%   |
| Plextor             | 5         | 7      | 0.24%   |
| Mushkin             | 5         | 6      | 0.24%   |
| GOODRAM             | 5         | 6      | 0.24%   |
| Maxtor              | 4         | 4      | 0.19%   |
| KIOXIA-EXCERIA      | 4         | 4      | 0.19%   |
| Gigabyte Technology | 4         | 6      | 0.19%   |
| FORESEE             | 4         | 5      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1977      | 2749   | 34.28%  |
| SSD     | 1929      | 2483   | 33.44%  |
| HDD     | 1552      | 1819   | 26.91%  |
| MMC     | 231       | 281    | 4%      |
| Unknown | 79        | 104    | 1.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3038      | 4132   | 55.64%  |
| NVMe | 1973      | 2741   | 36.14%  |
| MMC  | 231       | 281    | 4.23%   |
| SAS  | 218       | 282    | 3.99%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 2194      | 2821   | 63.72%  |
| 0.51-1.0        | 1095      | 1288   | 31.8%   |
| 1.01-2.0        | 135       | 165    | 3.92%   |
| 4.01-10.0       | 10        | 16     | 0.29%   |
| 2.01-3.0        | 4         | 5      | 0.12%   |
| 3.01-4.0        | 3         | 4      | 0.09%   |
| More than 100.0 | 1         | 1      | 0.03%   |
| 10.01-20.0      | 1         | 2      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1644      | 33.65%  |
| 251-500        | 1388      | 28.41%  |
| 501-1000       | 897       | 18.36%  |
| 1001-2000      | 332       | 6.79%   |
| 51-100         | 245       | 5.01%   |
| 21-50          | 117       | 2.39%   |
| 1-20           | 113       | 2.31%   |
| 2001-3000      | 67        | 1.37%   |
| More than 3000 | 54        | 1.11%   |
| Unknown        | 29        | 0.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2016      | 39.33%  |
| 21-50          | 1132      | 22.08%  |
| 51-100         | 668       | 13.03%  |
| 101-250        | 663       | 12.93%  |
| 251-500        | 341       | 6.65%   |
| 501-1000       | 184       | 3.59%   |
| 1001-2000      | 60        | 1.17%   |
| Unknown        | 29        | 0.57%   |
| More than 3000 | 17        | 0.33%   |
| 2001-3000      | 16        | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB               | 5         | 8      | 4.39%   |
| Seagate ST1000LM035-1RK172 1TB           | 4         | 4      | 3.51%   |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 3.51%   |
| Seagate ST500LT012-1DG142 500GB          | 3         | 3      | 2.63%   |
| Seagate ST1000LX015-1U7172 1TB           | 3         | 3      | 2.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 3         | 3      | 2.63%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 5      | 2.63%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 2.63%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 2         | 2      | 1.75%   |
| SK hynix PC711 HFS001TDE9X073N 1TB       | 2         | 2      | 1.75%   |
| Seagate ST9500325AS 500GB                | 2         | 3      | 1.75%   |
| Seagate ST500LT012-9WS142 500GB          | 2         | 2      | 1.75%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 2      | 1.75%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD      | 2         | 2      | 1.75%   |
| Kingston SUV400S37120G 120GB SSD         | 2         | 2      | 1.75%   |
| Crucial CT1000P1SSD8 1TB                 | 2         | 2      | 1.75%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 0.88%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 0.88%   |
| WDC WD5000LPCX-21VHAT0 500GB             | 1         | 1      | 0.88%   |
| WDC WD5000BPVT-22HXZT3 500GB             | 1         | 1      | 0.88%   |
| WDC WD5000BPVT-08HXZT3 500GB             | 1         | 1      | 0.88%   |
| WDC WD3200BEKT-60PVMT0 320GB             | 1         | 1      | 0.88%   |
| WDC WD2500BEVT-22A23T0 250GB             | 1         | 1      | 0.88%   |
| WDC WD1600BJKT-75F4T0 160GB              | 1         | 1      | 0.88%   |
| WDC WD10SPZX-75Z10T1 1TB                 | 1         | 1      | 0.88%   |
| WDC WD10SPZX-24Z10 1TB                   | 1         | 1      | 0.88%   |
| WDC WD10SPZX-22Z10T0 1TB                 | 1         | 1      | 0.88%   |
| WDC WD10SPCX-24HWST1 1TB                 | 1         | 1      | 0.88%   |
| WDC WD10JPVX-75JC3T0 1TB                 | 1         | 1      | 0.88%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 1      | 0.88%   |
| WDC WD10JPVX-60JC3T0 1TB                 | 1         | 1      | 0.88%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB     | 1         | 1      | 0.88%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.88%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 2      | 0.88%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1      | 0.88%   |
| Toshiba MQ02ABD100H 1TB                  | 1         | 1      | 0.88%   |
| Toshiba MQ01ACF050 500GB                 | 1         | 1      | 0.88%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 0.88%   |
| Toshiba MQ01ABD032 320GB                 | 1         | 1      | 0.88%   |
| Toshiba MK7559GSXP 752GB                 | 1         | 1      | 0.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 26     | 21.93%  |
| WDC                 | 18        | 18     | 15.79%  |
| HGST                | 14        | 17     | 12.28%  |
| Toshiba             | 11        | 12     | 9.65%   |
| SK hynix            | 7         | 9      | 6.14%   |
| Samsung Electronics | 6         | 6      | 5.26%   |
| Hitachi             | 6         | 8      | 5.26%   |
| Crucial             | 5         | 5      | 4.39%   |
| A-DATA Technology   | 5         | 5      | 4.39%   |
| Micron Technology   | 4         | 4      | 3.51%   |
| Kingston            | 4         | 4      | 3.51%   |
| Intel               | 3         | 3      | 2.63%   |
| SanDisk             | 2         | 2      | 1.75%   |
| Team                | 1         | 1      | 0.88%   |
| Lexar               | 1         | 1      | 0.88%   |
| Leven               | 1         | 1      | 0.88%   |
| China               | 1         | 1      | 0.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 25        | 26     | 36.23%  |
| WDC     | 16        | 16     | 23.19%  |
| HGST    | 14        | 17     | 20.29%  |
| Toshiba | 8         | 8      | 11.59%  |
| Hitachi | 6         | 8      | 8.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 69        | 75     | 60.53%  |
| SSD  | 29        | 32     | 25.44%  |
| NVMe | 16        | 16     | 14.04%  |

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
| Detected | 3674      | 5733   | 74.01%  |
| Works    | 1175      | 1579   | 23.67%  |
| Malfunc  | 114       | 123    | 2.3%    |
| Failed   | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3185      | 53.67%  |
| Samsung Electronics              | 730       | 12.3%   |
| AMD                              | 595       | 10.03%  |
| SanDisk                          | 334       | 5.63%   |
| SK hynix                         | 239       | 4.03%   |
| Micron Technology                | 113       | 1.9%    |
| Toshiba America Info Systems     | 112       | 1.89%   |
| Phison Electronics               | 93        | 1.57%   |
| Kingston Technology Company      | 82        | 1.38%   |
| Nvidia                           | 76        | 1.28%   |
| ADATA Technology                 | 54        | 0.91%   |
| Micron/Crucial Technology        | 49        | 0.83%   |
| Silicon Motion                   | 47        | 0.79%   |
| KIOXIA                           | 44        | 0.74%   |
| Solid State Storage Technology   | 35        | 0.59%   |
| Union Memory (Shenzhen)          | 30        | 0.51%   |
| Apple                            | 19        | 0.32%   |
| Realtek Semiconductor            | 18        | 0.3%    |
| Marvell Technology Group         | 18        | 0.3%    |
| Seagate Technology               | 12        | 0.2%    |
| Silicon Integrated Systems [SiS] | 8         | 0.13%   |
| Shenzhen Longsys Electronics     | 8         | 0.13%   |
| Lite-On Technology               | 7         | 0.12%   |
| Lenovo                           | 6         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 4         | 0.07%   |
| JMicron Technology               | 4         | 0.07%   |
| ASMedia Technology               | 3         | 0.05%   |
| INNOGRIT                         | 2         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| Silicon Image                    | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| Netac Technology                 | 1         | 0.02%   |
| Enmotus                          | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 564       | 9.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 393       | 6.31%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 380       | 6.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 330       | 5.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 301       | 4.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 262       | 4.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 241       | 3.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 193       | 3.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 148       | 2.38%   |
| Intel Volume Management Device NVMe RAID Controller                            | 142       | 2.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 138       | 2.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 120       | 1.93%   |
| Samsung NVMe SSD Controller 980                                                | 114       | 1.83%   |
| Micron NVMe Storage Controller                                                 | 112       | 1.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 97        | 1.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 95        | 1.53%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 92        | 1.48%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 90        | 1.45%   |
| Intel SSD 660P Series                                                          | 89        | 1.43%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 85        | 1.37%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 85        | 1.37%   |
| Intel Comet Lake SATA AHCI Controller                                          | 79        | 1.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 78        | 1.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 77        | 1.24%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 65        | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 51        | 0.82%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 49        | 0.79%   |
| Phison E12 NVMe Controller                                                     | 49        | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 49        | 0.79%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 49        | 0.79%   |
| Intel Tiger Lake-LP SATA Controller                                            | 48        | 0.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 46        | 0.74%   |
| Nvidia MCP79 AHCI Controller                                                   | 44        | 0.71%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 43        | 0.69%   |
| Samsung Electronics SATA controller                                            | 43        | 0.69%   |
| SK hynix Non-Volatile memory controller                                        | 42        | 0.67%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 40        | 0.64%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 40        | 0.64%   |
| SanDisk Non-Volatile memory controller                                         | 37        | 0.59%   |
| Solid State Storage Non-Volatile memory controller                             | 35        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3360      | 56.39%  |
| NVMe | 1969      | 33.04%  |
| RAID | 471       | 7.9%    |
| IDE  | 159       | 2.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 3858      | 81.36%  |
| AMD    | 884       | 18.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 122       | 2.57%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 94        | 1.98%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 93        | 1.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 87        | 1.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 85        | 1.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 73        | 1.54%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 73        | 1.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 68        | 1.43%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 66        | 1.39%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 65        | 1.37%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 63        | 1.33%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 61        | 1.29%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 57        | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 55        | 1.16%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 53        | 1.12%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 52        | 1.1%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 51        | 1.08%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 47        | 0.99%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 46        | 0.97%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 42        | 0.89%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 42        | 0.89%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 40        | 0.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 38        | 0.8%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 38        | 0.8%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 37        | 0.78%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 36        | 0.76%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 35        | 0.74%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 34        | 0.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 34        | 0.72%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 32        | 0.67%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 32        | 0.67%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 32        | 0.67%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 32        | 0.67%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 31        | 0.65%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 30        | 0.63%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 30        | 0.63%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 30        | 0.63%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 30        | 0.63%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 28        | 0.59%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 27        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1410      | 29.73%  |
| Intel Core i5           | 1205      | 25.41%  |
| Other                   | 391       | 8.25%   |
| Intel Core i3           | 300       | 6.33%   |
| AMD Ryzen 5             | 248       | 5.23%   |
| AMD Ryzen 7             | 247       | 5.21%   |
| Intel Core 2 Duo        | 172       | 3.63%   |
| Intel Celeron           | 155       | 3.27%   |
| Intel Pentium           | 55        | 1.16%   |
| AMD Ryzen 3             | 55        | 1.16%   |
| AMD Ryzen 9             | 54        | 1.14%   |
| Intel Core i9           | 49        | 1.03%   |
| AMD A6                  | 48        | 1.01%   |
| AMD A8                  | 34        | 0.72%   |
| AMD Ryzen 7 PRO         | 32        | 0.67%   |
| Intel Pentium Dual-Core | 31        | 0.65%   |
| AMD A10                 | 29        | 0.61%   |
| AMD A4                  | 24        | 0.51%   |
| Intel Atom              | 19        | 0.4%    |
| Intel Core 2            | 16        | 0.34%   |
| Intel Xeon              | 13        | 0.27%   |
| Intel Pentium Dual      | 13        | 0.27%   |
| Intel Genuine           | 13        | 0.27%   |
| Intel Core m3           | 12        | 0.25%   |
| AMD E1                  | 11        | 0.23%   |
| AMD Ryzen 5 PRO         | 10        | 0.21%   |
| AMD Athlon              | 10        | 0.21%   |
| AMD E                   | 9         | 0.19%   |
| AMD E2                  | 7         | 0.15%   |
| Intel Pentium Silver    | 6         | 0.13%   |
| Intel Core M            | 6         | 0.13%   |
| AMD Turion 64 X2 Mobile | 6         | 0.13%   |
| AMD FX                  | 6         | 0.13%   |
| AMD A12                 | 6         | 0.13%   |
| Intel Celeron Dual-Core | 4         | 0.08%   |
| AMD C-60                | 4         | 0.08%   |
| AMD Athlon X2           | 4         | 0.08%   |
| Intel Core m5           | 3         | 0.06%   |
| AMD Phenom II           | 3         | 0.06%   |
| AMD V120                | 2         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2045      | 43.13%  |
| 4      | 1664      | 35.09%  |
| 6      | 490       | 10.33%  |
| 8      | 431       | 9.09%   |
| 14     | 42        | 0.89%   |
| 12     | 24        | 0.51%   |
| 1      | 23        | 0.49%   |
| 10     | 18        | 0.38%   |
| 16     | 2         | 0.04%   |
| 7      | 1         | 0.02%   |
| 5      | 1         | 0.02%   |
| 3      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4742      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3974      | 83.75%  |
| 1      | 771       | 16.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4735      | 99.85%  |
| Unknown        | 7         | 0.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3065      | 63.07%  |
| 0x906ea    | 151       | 3.11%   |
| 0x806ea    | 107       | 2.2%    |
| 0x306a9    | 101       | 2.08%   |
| 0x806ec    | 98        | 2.02%   |
| 0x806c1    | 93        | 1.91%   |
| 0x206a7    | 91        | 1.87%   |
| 0x406e3    | 85        | 1.75%   |
| 0x40651    | 80        | 1.65%   |
| 0xa0652    | 74        | 1.52%   |
| 0x806e9    | 60        | 1.23%   |
| 0x306c3    | 56        | 1.15%   |
| 0x906e9    | 53        | 1.09%   |
| 0x0a50000c | 48        | 0.99%   |
| 0x08108102 | 44        | 0.91%   |
| 0x306d4    | 40        | 0.82%   |
| 0x806d1    | 37        | 0.76%   |
| 0x1067a    | 35        | 0.72%   |
| 0x806eb    | 34        | 0.7%    |
| 0x506e3    | 34        | 0.7%    |
| 0x08600106 | 32        | 0.66%   |
| 0x906ed    | 28        | 0.58%   |
| 0x08108109 | 28        | 0.58%   |
| 0x906a3    | 24        | 0.49%   |
| 0x08600104 | 23        | 0.47%   |
| 0x20655    | 22        | 0.45%   |
| 0x706e5    | 20        | 0.41%   |
| 0x08608103 | 20        | 0.41%   |
| 0x08600103 | 18        | 0.37%   |
| 0x06006705 | 17        | 0.35%   |
| 0x0810100b | 15        | 0.31%   |
| 0x706a1    | 13        | 0.27%   |
| 0x0a404101 | 12        | 0.25%   |
| 0x40661    | 11        | 0.23%   |
| 0x10676    | 11        | 0.23%   |
| 0x07030105 | 10        | 0.21%   |
| 0xa0660    | 9         | 0.19%   |
| 0x906a4    | 8         | 0.16%   |
| 0x08600102 | 8         | 0.16%   |
| 0x06001119 | 8         | 0.16%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1124      | 23.68%  |
| Haswell          | 420       | 8.85%   |
| SandyBridge      | 339       | 7.14%   |
| IvyBridge        | 334       | 7.04%   |
| Skylake          | 272       | 5.73%   |
| TigerLake        | 222       | 4.68%   |
| Zen+             | 191       | 4.02%   |
| Unknown          | 189       | 3.98%   |
| CometLake        | 187       | 3.94%   |
| Penryn           | 185       | 3.9%    |
| Zen 2            | 178       | 3.75%   |
| Broadwell        | 174       | 3.67%   |
| Zen 3            | 146       | 3.08%   |
| Westmere         | 143       | 3.01%   |
| IceLake          | 89        | 1.88%   |
| Silvermont       | 77        | 1.62%   |
| Core             | 71        | 1.5%    |
| Excavator        | 64        | 1.35%   |
| Goldmont plus    | 53        | 1.12%   |
| Zen              | 49        | 1.03%   |
| Puma             | 41        | 0.86%   |
| Piledriver       | 34        | 0.72%   |
| Alderlake Hybrid | 33        | 0.7%    |
| Bobcat           | 22        | 0.46%   |
| Goldmont         | 20        | 0.42%   |
| Nehalem          | 17        | 0.36%   |
| Jaguar           | 13        | 0.27%   |
| Steamroller      | 12        | 0.25%   |
| K10 Llano        | 12        | 0.25%   |
| K8 Hammer        | 11        | 0.23%   |
| K10              | 9         | 0.19%   |
| K8 & K10 hybrid  | 8         | 0.17%   |
| Bonnell          | 4         | 0.08%   |
| Tremont          | 3         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3501      | 55.23%  |
| Nvidia                           | 1718      | 27.1%   |
| AMD                              | 1113      | 17.56%  |
| Silicon Integrated Systems [SiS] | 6         | 0.09%   |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 321       | 4.95%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 309       | 4.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 307       | 4.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 231       | 3.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 207       | 3.19%   |
| Intel UHD Graphics 620                                                                   | 203       | 3.13%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 191       | 2.94%   |
| AMD Renoir                                                                               | 169       | 2.61%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 166       | 2.56%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 156       | 2.41%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 143       | 2.2%    |
| Intel HD Graphics 620                                                                    | 140       | 2.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 137       | 2.11%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 128       | 1.97%   |
| Intel HD Graphics 5500                                                                   | 122       | 1.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 119       | 1.83%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 115       | 1.77%   |
| Intel HD Graphics 630                                                                    | 114       | 1.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 109       | 1.68%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 82        | 1.26%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 78        | 1.2%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 78        | 1.2%    |
| Intel HD Graphics 530                                                                    | 71        | 1.09%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 69        | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 64        | 0.99%   |
| AMD Lucienne                                                                             | 64        | 0.99%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 62        | 0.96%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 57        | 0.88%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 56        | 0.86%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 56        | 0.86%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 53        | 0.82%   |
| Nvidia GP108M [GeForce MX150]                                                            | 52        | 0.8%    |
| Nvidia TU117M                                                                            | 49        | 0.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 49        | 0.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 49        | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 47        | 0.72%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 45        | 0.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 44        | 0.68%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 39        | 0.6%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 37        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2149      | 45.01%  |
| Intel + Nvidia     | 1179      | 24.69%  |
| 1 x AMD            | 636       | 13.32%  |
| 1 x Nvidia         | 313       | 6.55%   |
| AMD + Nvidia       | 204       | 4.27%   |
| Intel + AMD        | 181       | 3.79%   |
| 2 x AMD            | 93        | 1.95%   |
| 2 x Nvidia         | 9         | 0.19%   |
| 1 x SiS            | 6         | 0.13%   |
| Other              | 2         | 0.04%   |
| Intel + 2 x Nvidia | 2         | 0.04%   |
| 1 x S3 Graphics    | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3289      | 68.74%  |
| Proprietary | 1367      | 28.57%  |
| Unknown     | 129       | 2.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3582      | 74.19%  |
| 1.01-2.0   | 328       | 6.79%   |
| 3.01-4.0   | 310       | 6.42%   |
| 0.01-0.5   | 187       | 3.87%   |
| 5.01-6.0   | 185       | 3.83%   |
| 7.01-8.0   | 101       | 2.09%   |
| 0.51-1.0   | 93        | 1.93%   |
| 2.01-3.0   | 29        | 0.6%    |
| 8.01-16.0  | 13        | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 978       | 17.82%  |
| Chimei Innolux          | 801       | 14.59%  |
| LG Display              | 774       | 14.1%   |
| BOE                     | 701       | 12.77%  |
| Samsung Electronics     | 503       | 9.16%   |
| Apple                   | 227       | 4.14%   |
| Sharp                   | 201       | 3.66%   |
| Goldstar                | 168       | 3.06%   |
| Dell                    | 158       | 2.88%   |
| PANDA                   | 139       | 2.53%   |
| Chi Mei Optoelectronics | 85        | 1.55%   |
| Lenovo                  | 72        | 1.31%   |
| Acer                    | 58        | 1.06%   |
| Hewlett-Packard         | 56        | 1.02%   |
| AOC                     | 55        | 1%      |
| Philips                 | 44        | 0.8%    |
| InfoVision              | 44        | 0.8%    |
| BenQ                    | 42        | 0.77%   |
| ASUSTek Computer        | 31        | 0.56%   |
| Ancor Communications    | 31        | 0.56%   |
| CSO                     | 30        | 0.55%   |
| ViewSonic               | 19        | 0.35%   |
| TMX                     | 14        | 0.26%   |
| Sony                    | 14        | 0.26%   |
| LG Philips              | 14        | 0.26%   |
| Panasonic               | 12        | 0.22%   |
| Vizio                   | 11        | 0.2%    |
| InnoLux Display         | 10        | 0.18%   |
| Sceptre Tech            | 9         | 0.16%   |
| Toshiba                 | 8         | 0.15%   |
| JDI                     | 8         | 0.15%   |
| Iiyama                  | 8         | 0.15%   |
| MSI                     | 6         | 0.11%   |
| Vestel Elektronik       | 5         | 0.09%   |
| LGD                     | 5         | 0.09%   |
| Hitachi                 | 5         | 0.09%   |
| HannStar                | 5         | 0.09%   |
| TCL                     | 4         | 0.07%   |
| Insignia                | 4         | 0.07%   |
| Eizo                    | 4         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 55        | 0.99%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 52        | 0.94%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 47        | 0.85%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 45        | 0.81%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 43        | 0.78%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 39        | 0.7%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 35        | 0.63%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 33        | 0.6%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 30        | 0.54%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 26        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 26        | 0.47%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch     | 25        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 25        | 0.45%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 24        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 24        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 23        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 23        | 0.41%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 22        | 0.4%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 21        | 0.38%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 20        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 19        | 0.34%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 19        | 0.34%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                   | 18        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch          | 18        | 0.32%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 18        | 0.32%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 17        | 0.31%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 16        | 0.29%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                    | 16        | 0.29%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch              | 15        | 0.27%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch          | 15        | 0.27%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch             | 15        | 0.27%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 15        | 0.27%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch             | 15        | 0.27%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 15        | 0.27%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                      | 15        | 0.27%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                   | 14        | 0.25%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                   | 14        | 0.25%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 14        | 0.25%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 14        | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 14        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2424      | 47.15%  |
| 1366x768 (WXGA)    | 1315      | 25.58%  |
| 3840x2160 (4K)     | 265       | 5.15%   |
| 1600x900 (HD+)     | 213       | 4.14%   |
| 2560x1440 (QHD)    | 165       | 3.21%   |
| 1280x800 (WXGA)    | 127       | 2.47%   |
| 1920x1200 (WUXGA)  | 95        | 1.85%   |
| 1440x900 (WXGA+)   | 92        | 1.79%   |
| 2560x1600          | 75        | 1.46%   |
| 2880x1800          | 58        | 1.13%   |
| 2560x1080          | 44        | 0.86%   |
| 3840x2400          | 32        | 0.62%   |
| 3440x1440          | 31        | 0.6%    |
| 1680x1050 (WSXGA+) | 29        | 0.56%   |
| 3200x1800 (QHD+)   | 18        | 0.35%   |
| 2160x1440          | 18        | 0.35%   |
| 1360x768           | 18        | 0.35%   |
| 2256x1504          | 14        | 0.27%   |
| 1280x1024 (SXGA)   | 14        | 0.27%   |
| 1920x540           | 13        | 0.25%   |
| 3000x2000          | 10        | 0.19%   |
| 3840x1080          | 8         | 0.16%   |
| 3456x2160          | 6         | 0.12%   |
| 3200x2000          | 6         | 0.12%   |
| 3072x1920          | 6         | 0.12%   |
| Unknown            | 6         | 0.12%   |
| 3840x1100          | 3         | 0.06%   |
| 2560x1700          | 3         | 0.06%   |
| 2304x1440          | 3         | 0.06%   |
| 800x1280           | 2         | 0.04%   |
| 3840x1600          | 2         | 0.04%   |
| 3840x1200          | 2         | 0.04%   |
| 2288x1287          | 2         | 0.04%   |
| 1920x515           | 2         | 0.04%   |
| 1920x1280          | 2         | 0.04%   |
| 1680x945           | 2         | 0.04%   |
| 1280x720 (HD)      | 2         | 0.04%   |
| 1024x768 (XGA)     | 2         | 0.04%   |
| 1024x600           | 2         | 0.04%   |
| 7680x2160          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2310      | 42.12%  |
| 13      | 857       | 15.63%  |
| 14      | 616       | 11.23%  |
| 17      | 401       | 7.31%   |
| 27      | 184       | 3.36%   |
| 24      | 157       | 2.86%   |
| 23      | 139       | 2.53%   |
| 12      | 118       | 2.15%   |
| 21      | 102       | 1.86%   |
| 31      | 78        | 1.42%   |
| 16      | 71        | 1.29%   |
| 11      | 66        | 1.2%    |
| 34      | 65        | 1.19%   |
| 18      | 47        | 0.86%   |
| Unknown | 42        | 0.77%   |
| 19      | 31        | 0.57%   |
| 84      | 20        | 0.36%   |
| 32      | 20        | 0.36%   |
| 40      | 18        | 0.33%   |
| 20      | 17        | 0.31%   |
| 72      | 15        | 0.27%   |
| 22      | 14        | 0.26%   |
| 54      | 9         | 0.16%   |
| 48      | 9         | 0.16%   |
| 25      | 9         | 0.16%   |
| 52      | 6         | 0.11%   |
| 35      | 5         | 0.09%   |
| 28      | 5         | 0.09%   |
| 26      | 5         | 0.09%   |
| 10      | 5         | 0.09%   |
| 65      | 4         | 0.07%   |
| 49      | 4         | 0.07%   |
| 46      | 4         | 0.07%   |
| 39      | 4         | 0.07%   |
| 33      | 4         | 0.07%   |
| 29      | 4         | 0.07%   |
| 47      | 3         | 0.05%   |
| 37      | 3         | 0.05%   |
| 8       | 2         | 0.04%   |
| 99      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 3356      | 61.65%  |
| 201-300        | 605       | 11.11%  |
| 351-400        | 484       | 8.89%   |
| 501-600        | 439       | 8.06%   |
| 401-500        | 202       | 3.71%   |
| 601-700        | 111       | 2.04%   |
| 701-800        | 90        | 1.65%   |
| 1001-1500      | 43        | 0.79%   |
| Unknown        | 42        | 0.77%   |
| 1501-2000      | 37        | 0.68%   |
| 801-900        | 28        | 0.51%   |
| 901-1000       | 3         | 0.06%   |
| 101-200        | 2         | 0.04%   |
| More than 2000 | 1         | 0.02%   |
| 1-100          | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 4044      | 84.74%  |
| 16/10   | 527       | 11.04%  |
| 21/9    | 77        | 1.61%   |
| 3/2     | 55        | 1.15%   |
| Unknown | 23        | 0.48%   |
| 5/4     | 17        | 0.36%   |
| 32/9    | 9         | 0.19%   |
| 4/3     | 8         | 0.17%   |
| 3.40    | 3         | 0.06%   |
| 3.73    | 2         | 0.04%   |
| 0.62    | 2         | 0.04%   |
| 6/5     | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 0.67    | 1         | 0.02%   |
| 0.63    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2322      | 42.42%  |
| 81-90          | 1186      | 21.67%  |
| 121-130        | 374       | 6.83%   |
| 201-250        | 349       | 6.38%   |
| 71-80          | 284       | 5.19%   |
| 301-350        | 188       | 3.43%   |
| 351-500        | 171       | 3.12%   |
| 61-70          | 111       | 2.03%   |
| 151-200        | 70        | 1.28%   |
| 51-60          | 69        | 1.26%   |
| More than 1000 | 67        | 1.22%   |
| 111-120        | 54        | 0.99%   |
| 251-300        | 52        | 0.95%   |
| 141-150        | 51        | 0.93%   |
| 501-1000       | 44        | 0.8%    |
| Unknown        | 42        | 0.77%   |
| 131-140        | 23        | 0.42%   |
| 91-100         | 9         | 0.16%   |
| 41-50          | 5         | 0.09%   |
| 1-40           | 3         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2354      | 43.89%  |
| 101-120       | 1506      | 28.08%  |
| 51-100        | 743       | 13.85%  |
| 161-240       | 409       | 7.62%   |
| More than 240 | 239       | 4.46%   |
| 1-50          | 71        | 1.32%   |
| Unknown       | 42        | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3755      | 77.42%  |
| 2     | 831       | 17.13%  |
| 0     | 162       | 3.34%   |
| 3     | 96        | 1.98%   |
| 4     | 6         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2582      | 33.72%  |
| Intel                             | 2552      | 33.33%  |
| Qualcomm Atheros                  | 1062      | 13.87%  |
| Broadcom                          | 519       | 6.78%   |
| Broadcom Limited                  | 149       | 1.95%   |
| MediaTek                          | 115       | 1.5%    |
| Marvell Technology Group          | 65        | 0.85%   |
| Nvidia                            | 54        | 0.71%   |
| Ralink                            | 51        | 0.67%   |
| ASIX Electronics                  | 50        | 0.65%   |
| TP-Link                           | 49        | 0.64%   |
| Ralink Technology                 | 38        | 0.5%    |
| Samsung Electronics               | 36        | 0.47%   |
| DisplayLink                       | 30        | 0.39%   |
| Dell                              | 25        | 0.33%   |
| Lenovo                            | 23        | 0.3%    |
| Ericsson Business Mobile Networks | 21        | 0.27%   |
| Qualcomm                          | 20        | 0.26%   |
| Xiaomi                            | 19        | 0.25%   |
| Sierra Wireless                   | 19        | 0.25%   |
| JMicron Technology                | 17        | 0.22%   |
| Google                            | 14        | 0.18%   |
| Hewlett-Packard                   | 13        | 0.17%   |
| OnePlus Technology (Shenzhen)     | 11        | 0.14%   |
| NetGear                           | 11        | 0.14%   |
| ASUSTek Computer                  | 11        | 0.14%   |
| Huawei Technologies               | 10        | 0.13%   |
| D-Link                            | 9         | 0.12%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.1%    |
| Motorola PCS                      | 8         | 0.1%    |
| Apple                             | 6         | 0.08%   |
| OPPO Electronics                  | 5         | 0.07%   |
| Linksys                           | 5         | 0.07%   |
| Microsoft                         | 4         | 0.05%   |
| Qualcomm Atheros Communications   | 3         | 0.04%   |
| Fibocom                           | 3         | 0.04%   |
| Edimax Technology                 | 3         | 0.04%   |
| U-Blox                            | 2         | 0.03%   |
| T & A Mobile Phones               | 2         | 0.03%   |
| Shenzhen Goodix Technology        | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1660      | 18.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 414       | 4.59%   |
| Intel Wi-Fi 6 AX200                                               | 327       | 3.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 232       | 2.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 200       | 2.22%   |
| Intel Wireless 8265 / 8275                                        | 188       | 2.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 172       | 1.91%   |
| Intel Wi-Fi 6 AX201                                               | 167       | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 167       | 1.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 161       | 1.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 155       | 1.72%   |
| Intel Wireless 7260                                               | 153       | 1.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 148       | 1.64%   |
| Intel Wireless 7265                                               | 143       | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 141       | 1.56%   |
| Intel Wireless 8260                                               | 120       | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 113       | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 113       | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 109       | 1.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 103       | 1.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 102       | 1.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 85        | 0.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 84        | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                     | 79        | 0.88%   |
| Intel Wireless 3165                                               | 70        | 0.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 66        | 0.73%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 62        | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 61        | 0.68%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 59        | 0.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 58        | 0.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 57        | 0.63%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 57        | 0.63%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 56        | 0.62%   |
| Intel Wireless 3160                                               | 54        | 0.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 53        | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 52        | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 51        | 0.57%   |
| Intel Wireless-AC 9260                                            | 50        | 0.55%   |
| Intel Centrino Ultimate-N 6300                                    | 47        | 0.52%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 47        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2460      | 49.93%  |
| Qualcomm Atheros                      | 888       | 18.02%  |
| Realtek Semiconductor                 | 657       | 13.33%  |
| Broadcom                              | 443       | 8.99%   |
| Broadcom Limited                      | 118       | 2.39%   |
| MediaTek                              | 111       | 2.25%   |
| Ralink                                | 51        | 1.04%   |
| TP-Link                               | 42        | 0.85%   |
| Ralink Technology                     | 38        | 0.77%   |
| Dell                                  | 22        | 0.45%   |
| Sierra Wireless                       | 19        | 0.39%   |
| Qualcomm                              | 17        | 0.35%   |
| NetGear                               | 10        | 0.2%    |
| D-Link                                | 9         | 0.18%   |
| ASUSTek Computer                      | 9         | 0.18%   |
| Hewlett-Packard                       | 5         | 0.1%    |
| Qualcomm Atheros Communications       | 3         | 0.06%   |
| Microsoft                             | 3         | 0.06%   |
| Fibocom                               | 3         | 0.06%   |
| Edimax Technology                     | 3         | 0.06%   |
| Linksys                               | 2         | 0.04%   |
| D-Link System                         | 2         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.04%   |
| ZyDAS                                 | 1         | 0.02%   |
| Wilocity                              | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Ovislink                              | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Chu Yuen Enterprise                   | 1         | 0.02%   |
| Arduino SA                            | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 327       | 6.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 232       | 4.68%   |
| Intel Wireless 8265 / 8275                                     | 188       | 3.79%   |
| Intel Wi-Fi 6 AX201                                            | 167       | 3.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 167       | 3.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 161       | 3.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 155       | 3.12%   |
| Intel Wireless 7260                                            | 153       | 3.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 148       | 2.98%   |
| Intel Wireless 7265                                            | 143       | 2.88%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 141       | 2.84%   |
| Intel Wireless 8260                                            | 120       | 2.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 113       | 2.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 113       | 2.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 109       | 2.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 103       | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 102       | 2.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 85        | 1.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 84        | 1.69%   |
| Broadcom BCM43142 802.11b/g/n                                  | 79        | 1.59%   |
| Intel Wireless 3165                                            | 70        | 1.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 66        | 1.33%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 62        | 1.25%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 58        | 1.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 57        | 1.15%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 57        | 1.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 56        | 1.13%   |
| Intel Wireless 3160                                            | 54        | 1.09%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 53        | 1.07%   |
| Intel Wireless-AC 9260                                         | 50        | 1.01%   |
| Intel Centrino Ultimate-N 6300                                 | 47        | 0.95%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 47        | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 46        | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 43        | 0.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 42        | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 42        | 0.85%   |
| Intel Centrino Advanced-N 6235                                 | 41        | 0.83%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 38        | 0.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 36        | 0.73%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 32        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2339      | 59.16%  |
| Intel                            | 740       | 18.72%  |
| Qualcomm Atheros                 | 280       | 7.08%   |
| Broadcom                         | 175       | 4.43%   |
| Marvell Technology Group         | 65        | 1.64%   |
| Nvidia                           | 54        | 1.37%   |
| ASIX Electronics                 | 50        | 1.26%   |
| Samsung Electronics              | 35        | 0.89%   |
| Broadcom Limited                 | 35        | 0.89%   |
| DisplayLink                      | 30        | 0.76%   |
| Lenovo                           | 23        | 0.58%   |
| Xiaomi                           | 19        | 0.48%   |
| JMicron Technology               | 17        | 0.43%   |
| Google                           | 14        | 0.35%   |
| OnePlus Technology (Shenzhen)    | 10        | 0.25%   |
| Silicon Integrated Systems [SiS] | 8         | 0.2%    |
| TP-Link                          | 7         | 0.18%   |
| Huawei Technologies              | 7         | 0.18%   |
| Motorola PCS                     | 6         | 0.15%   |
| OPPO Electronics                 | 5         | 0.13%   |
| Apple                            | 5         | 0.13%   |
| Qualcomm                         | 3         | 0.08%   |
| MediaTek                         | 3         | 0.08%   |
| Linksys                          | 3         | 0.08%   |
| T & A Mobile Phones              | 2         | 0.05%   |
| LSI                              | 2         | 0.05%   |
| LG Electronics                   | 2         | 0.05%   |
| ICS Advent                       | 2         | 0.05%   |
| Hewlett-Packard                  | 2         | 0.05%   |
| ASUSTek Computer                 | 2         | 0.05%   |
| Aquantia                         | 2         | 0.05%   |
| Research In Motion               | 1         | 0.03%   |
| NTmore                           | 1         | 0.03%   |
| NetGear                          | 1         | 0.03%   |
| Microsoft                        | 1         | 0.03%   |
| Foxconn / Hon Hai                | 1         | 0.03%   |
| Cypress Semiconductor            | 1         | 0.03%   |
| Attansic Technology              | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1660      | 41.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 414       | 10.35%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 200       | 5%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 172       | 4.3%    |
| Intel Ethernet Connection (4) I219-LM                             | 61        | 1.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 59        | 1.47%   |
| Intel Ethernet Connection I218-LM                                 | 52        | 1.3%    |
| Intel Ethernet Connection I219-LM                                 | 51        | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 46        | 1.15%   |
| Intel Ethernet Connection I217-LM                                 | 45        | 1.12%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 40        | 1%      |
| Nvidia MCP79 Ethernet                                             | 40        | 1%      |
| ASIX AX88179 Gigabit Ethernet                                     | 40        | 1%      |
| Intel Ethernet Connection (3) I218-LM                             | 39        | 0.97%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 36        | 0.9%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 32        | 0.8%    |
| Intel 82577LM Gigabit Network Connection                          | 32        | 0.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 30        | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                             | 27        | 0.67%   |
| Intel Ethernet Connection (4) I219-V                              | 27        | 0.67%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 27        | 0.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26        | 0.65%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 25        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 22        | 0.55%   |
| Intel 82567LM Gigabit Network Connection                          | 21        | 0.52%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 21        | 0.52%   |
| Intel Ethernet Connection (7) I219-V                              | 20        | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 19        | 0.47%   |
| Intel Ethernet Connection (13) I219-V                             | 19        | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 18        | 0.45%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 18        | 0.45%   |
| Intel Ethernet Connection I219-V                                  | 18        | 0.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 0.45%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 18        | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 17        | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 17        | 0.42%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 17        | 0.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 17        | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 16        | 0.4%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 16        | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4688      | 55.09%  |
| Ethernet | 3769      | 44.29%  |
| Modem    | 39        | 0.46%   |
| Unknown  | 13        | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3995      | 79%     |
| Ethernet | 1062      | 21%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3436      | 72.41%  |
| 1     | 1242      | 26.17%  |
| 0     | 35        | 0.74%   |
| 3     | 32        | 0.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3793      | 78.96%  |
| Yes  | 1011      | 21.04%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2069      | 51.3%   |
| Qualcomm Atheros Communications | 395       | 9.79%   |
| Realtek Semiconductor           | 336       | 8.33%   |
| Apple                           | 246       | 6.1%    |
| IMC Networks                    | 211       | 5.23%   |
| Broadcom                        | 188       | 4.66%   |
| Lite-On Technology              | 186       | 4.61%   |
| Foxconn / Hon Hai               | 118       | 2.93%   |
| Dell                            | 62        | 1.54%   |
| Cambridge Silicon Radio         | 40        | 0.99%   |
| Toshiba                         | 30        | 0.74%   |
| Realtek                         | 29        | 0.72%   |
| Hewlett-Packard                 | 28        | 0.69%   |
| Ralink                          | 27        | 0.67%   |
| ASUSTek Computer                | 14        | 0.35%   |
| Foxconn International           | 11        | 0.27%   |
| Ralink Technology               | 8         | 0.2%    |
| Alps Electric                   | 7         | 0.17%   |
| Smart Modular Technologies      | 4         | 0.1%    |
| Askey Computer                  | 4         | 0.1%    |
| USI                             | 3         | 0.07%   |
| Taiyo Yuden                     | 3         | 0.07%   |
| Qcom                            | 3         | 0.07%   |
| Opticis                         | 3         | 0.07%   |
| Fujitsu                         | 2         | 0.05%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| MediaTek                        | 1         | 0.02%   |
| Dynex                           | 1         | 0.02%   |
| Creative Technology             | 1         | 0.02%   |
| Actions                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 711       | 17.62%  |
| Intel AX201 Bluetooth                               | 417       | 10.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 342       | 8.48%   |
| Intel AX200 Bluetooth                               | 322       | 7.98%   |
| Qualcomm Atheros  Bluetooth Device                  | 219       | 5.43%   |
| Realtek Bluetooth Radio                             | 199       | 4.93%   |
| Apple Bluetooth Host Controller                     | 143       | 3.54%   |
| Realtek  Bluetooth 4.2 Adapter                      | 95        | 2.35%   |
| Apple Bluetooth USB Host Controller                 | 73        | 1.81%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 71        | 1.76%   |
| IMC Networks Bluetooth Radio                        | 68        | 1.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 63        | 1.56%   |
| IMC Networks Wireless_Device                        | 54        | 1.34%   |
| Intel AX210 Bluetooth                               | 52        | 1.29%   |
| Foxconn / Hon Hai Bluetooth Device                  | 50        | 1.24%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 48        | 1.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 46        | 1.14%   |
| Intel Bluetooth Device                              | 44        | 1.09%   |
| IMC Networks Bluetooth Device                       | 44        | 1.09%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 42        | 1.04%   |
| Lite-On Bluetooth Device                            | 41        | 1.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 40        | 0.99%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 38        | 0.94%   |
| Intel Wireless-AC 3168 Bluetooth                    | 38        | 0.94%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 36        | 0.89%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 35        | 0.87%   |
| Broadcom BCM2045B (BDC-2.1)                         | 30        | 0.74%   |
| Realtek Bluetooth Radio                             | 29        | 0.72%   |
| Ralink RT3290 Bluetooth                             | 27        | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                   | 26        | 0.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 0.62%   |
| Dell DW375 Bluetooth Module                         | 22        | 0.55%   |
| Lite-On Atheros AR3012 Bluetooth                    | 20        | 0.5%    |
| Lite-On Wireless_Device                             | 19        | 0.47%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 19        | 0.47%   |
| Apple Bluetooth HCI                                 | 19        | 0.47%   |
| HP Broadcom 2070 Bluetooth Combo                    | 17        | 0.42%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 16        | 0.4%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.37%   |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3765      | 60.71%  |
| Nvidia                               | 1075      | 17.33%  |
| AMD                                  | 961       | 15.5%   |
| C-Media Electronics                  | 49        | 0.79%   |
| Logitech                             | 41        | 0.66%   |
| Realtek Semiconductor                | 39        | 0.63%   |
| Lenovo                               | 20        | 0.32%   |
| JMTek                                | 19        | 0.31%   |
| GN Netcom                            | 19        | 0.31%   |
| Kingston Technology                  | 15        | 0.24%   |
| Apple                                | 14        | 0.23%   |
| Texas Instruments                    | 13        | 0.21%   |
| Generalplus Technology               | 12        | 0.19%   |
| Sony                                 | 11        | 0.18%   |
| Razer USA                            | 10        | 0.16%   |
| Hewlett-Packard                      | 10        | 0.16%   |
| Corsair                              | 9         | 0.15%   |
| SteelSeries ApS                      | 8         | 0.13%   |
| Silicon Integrated Systems [SiS]     | 8         | 0.13%   |
| Plantronics                          | 7         | 0.11%   |
| Focusrite-Novation                   | 5         | 0.08%   |
| ASUSTek Computer                     | 5         | 0.08%   |
| Sennheiser Communications            | 4         | 0.06%   |
| FiiO Electronics Technology          | 4         | 0.06%   |
| DSEA A/S                             | 4         | 0.06%   |
| Creative Technology                  | 4         | 0.06%   |
| Tenx Technology                      | 3         | 0.05%   |
| Samson Technologies                  | 3         | 0.05%   |
| No brand                             | 3         | 0.05%   |
| Blue Microphones                     | 3         | 0.05%   |
| Yamaha                               | 2         | 0.03%   |
| XMOS                                 | 2         | 0.03%   |
| Turtle Beach                         | 2         | 0.03%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.03%   |
| TerraTec Electronic                  | 2         | 0.03%   |
| Pioneer DJ                           | 2         | 0.03%   |
| GYROCOM C&C                          | 2         | 0.03%   |
| CMX Systems                          | 2         | 0.03%   |
| AudioQuest                           | 2         | 0.03%   |
| Astro Gaming                         | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 633       | 8.44%   |
| Intel Sunrise Point-LP HD Audio                                            | 546       | 7.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 379       | 5.05%   |
| Intel Cannon Lake PCH cAVS                                                 | 348       | 4.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 292       | 3.89%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 290       | 3.87%   |
| Intel 8 Series HD Audio Controller                                         | 233       | 3.11%   |
| Intel Haswell-ULT HD Audio Controller                                      | 231       | 3.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 222       | 2.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 210       | 2.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 190       | 2.53%   |
| Intel Broadwell-U Audio Controller                                         | 174       | 2.32%   |
| Intel Comet Lake PCH cAVS                                                  | 172       | 2.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 167       | 2.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 160       | 2.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 152       | 2.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 151       | 2.01%   |
| Intel Comet Lake PCH-LP cAVS                                               | 135       | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 131       | 1.75%   |
| Nvidia TU106 High Definition Audio Controller                              | 129       | 1.72%   |
| Intel CM238 HD Audio Controller                                            | 127       | 1.69%   |
| AMD FCH Azalia Controller                                                  | 122       | 1.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 113       | 1.51%   |
| Nvidia GP107GL High Definition Audio Controller                            | 93        | 1.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 89        | 1.19%   |
| Nvidia GA106 High Definition Audio Controller                              | 78        | 1.04%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 76        | 1.01%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 76        | 1.01%   |
| AMD Kabini HDMI/DP Audio                                                   | 73        | 0.97%   |
| Nvidia GA104 High Definition Audio Controller                              | 69        | 0.92%   |
| Nvidia GP106 High Definition Audio Controller                              | 66        | 0.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 64        | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                              | 59        | 0.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 55        | 0.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 53        | 0.71%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 51        | 0.68%   |
| Nvidia Audio device                                                        | 49        | 0.65%   |
| AMD High Definition Audio Controller                                       | 45        | 0.6%    |
| Nvidia MCP79 High Definition Audio                                         | 44        | 0.59%   |
| Nvidia GK107 HDMI Audio Controller                                         | 44        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 457       | 29.68%  |
| SK hynix            | 346       | 22.47%  |
| Micron Technology   | 205       | 13.31%  |
| Kingston            | 124       | 8.05%   |
| Crucial             | 83        | 5.39%   |
| Unknown             | 54        | 3.51%   |
| A-DATA Technology   | 35        | 2.27%   |
| Smart               | 28        | 1.82%   |
| Ramaxel Technology  | 24        | 1.56%   |
| Corsair             | 21        | 1.36%   |
| Goldkey             | 20        | 1.3%    |
| Neo Forza           | 18        | 1.17%   |
| Elpida              | 18        | 1.17%   |
| G.Skill             | 13        | 0.84%   |
| Unknown (ABCD)      | 10        | 0.65%   |
| Smart Brazil        | 10        | 0.65%   |
| Unknown             | 9         | 0.58%   |
| Team                | 7         | 0.45%   |
| Teikon              | 6         | 0.39%   |
| Nanya Technology    | 6         | 0.39%   |
| Apacer              | 5         | 0.32%   |
| PNY                 | 4         | 0.26%   |
| Patriot             | 3         | 0.19%   |
| High Bridge         | 3         | 0.19%   |
| GSkill              | 3         | 0.19%   |
| Avant               | 3         | 0.19%   |
| Transcend           | 2         | 0.13%   |
| Timetec             | 2         | 0.13%   |
| GOODRAM             | 2         | 0.13%   |
| Gold Key            | 2         | 0.13%   |
| CSX                 | 2         | 0.13%   |
| ChangXin Memory     | 2         | 0.13%   |
| Unknown (8A02)      | 1         | 0.06%   |
| Unknown (898F)      | 1         | 0.06%   |
| Unknown (09B6)      | 1         | 0.06%   |
| Unknown (09A4)      | 1         | 0.06%   |
| Silicon Power       | 1         | 0.06%   |
| RZX                 | 1         | 0.06%   |
| PUSKILL             | 1         | 0.06%   |
| Multilaser          | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 37        | 2.29%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 27        | 1.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 24        | 1.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 1.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 18        | 1.12%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 18        | 1.12%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 1.05%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 0.99%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 16        | 0.99%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 15        | 0.93%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 0.93%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 15        | 0.93%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.87%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 13        | 0.81%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.74%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 12        | 0.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.68%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 11        | 0.68%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.68%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 10        | 0.62%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 10        | 0.62%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 10        | 0.62%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 10        | 0.62%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 10        | 0.62%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.56%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 9         | 0.56%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.56%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 9         | 0.56%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s        | 9         | 0.56%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.56%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 9         | 0.56%   |
| Unknown                                                          | 9         | 0.56%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 8         | 0.5%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.5%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.5%    |
| Samsung RAM K4AAG165WA-BCTD 8GB SODIMM DDR4 2667MT/s             | 8         | 0.5%    |
| Neo Forza RAM NMSO432F82-3200E 32GB SODIMM DDR4 3200MT/s         | 8         | 0.5%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 8         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 851       | 66.12%  |
| DDR3    | 255       | 19.81%  |
| LPDDR4  | 68        | 5.28%   |
| LPDDR3  | 60        | 4.66%   |
| DDR5    | 21        | 1.63%   |
| LPDDR5  | 14        | 1.09%   |
| DDR2    | 10        | 0.78%   |
| SDRAM   | 4         | 0.31%   |
| Unknown | 4         | 0.31%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1124      | 85.74%  |
| Row Of Chips | 169       | 12.89%  |
| Chip         | 12        | 0.92%   |
| DIMM         | 4         | 0.31%   |
| Unknown      | 2         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 635       | 45.04%  |
| 4096  | 349       | 24.75%  |
| 16384 | 275       | 19.5%   |
| 2048  | 73        | 5.18%   |
| 32768 | 68        | 4.82%   |
| 1024  | 10        | 0.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 405       | 28.89%  |
| 3200    | 332       | 23.68%  |
| 1600    | 202       | 14.41%  |
| 2400    | 131       | 9.34%   |
| 2133    | 85        | 6.06%   |
| 4267    | 34        | 2.43%   |
| 1334    | 29        | 2.07%   |
| 3266    | 24        | 1.71%   |
| 4800    | 21        | 1.5%    |
| 1867    | 21        | 1.5%    |
| 1333    | 21        | 1.5%    |
| 8400    | 18        | 1.28%   |
| 6400    | 14        | 1%      |
| 4266    | 11        | 0.78%   |
| 1067    | 11        | 0.78%   |
| 800     | 9         | 0.64%   |
| 3733    | 7         | 0.5%    |
| 1866    | 5         | 0.36%   |
| 2933    | 4         | 0.29%   |
| 667     | 4         | 0.29%   |
| Unknown | 3         | 0.21%   |
| 4199    | 2         | 0.14%   |
| 2048    | 2         | 0.14%   |
| 1066    | 2         | 0.14%   |
| 3466    | 1         | 0.07%   |
| 3400    | 1         | 0.07%   |
| 3333    | 1         | 0.07%   |
| 3000    | 1         | 0.07%   |
| 1200    | 1         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 30.77%  |
| Seiko Epson         | 5         | 19.23%  |
| Canon               | 4         | 15.38%  |
| Brother Industries  | 4         | 15.38%  |
| Samsung Electronics | 2         | 7.69%   |
| Xerox               | 1         | 3.85%   |
| MIIIW               | 1         | 3.85%   |
| ICS Advent          | 1         | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung M2020 Series            | 2         | 7.69%   |
| Xerox B215                      | 1         | 3.85%   |
| Seiko Epson WF-3520 Series      | 1         | 3.85%   |
| Seiko Epson L3110 Series        | 1         | 3.85%   |
| Seiko Epson L132 Series         | 1         | 3.85%   |
| Seiko Epson ET-3750 Series      | 1         | 3.85%   |
| Seiko Epson ET-2700 Series      | 1         | 3.85%   |
| MIIIW MW Keyboard Air Mini      | 1         | 3.85%   |
| ICS Advent Parallel Adapter     | 1         | 3.85%   |
| HP OfficeJet 3830 series        | 1         | 3.85%   |
| HP Ink Tank Wireless 410 series | 1         | 3.85%   |
| HP ENVY Photo 7800 series       | 1         | 3.85%   |
| HP ENVY 4520 series             | 1         | 3.85%   |
| HP Deskjet 3050 J610 series     | 1         | 3.85%   |
| HP Deskjet 2540 series          | 1         | 3.85%   |
| HP Deskjet 2050 J510            | 1         | 3.85%   |
| HP Color LaserJet CP2025dn      | 1         | 3.85%   |
| Canon PIXMA MX920 Series        | 1         | 3.85%   |
| Canon GX7000 series             | 1         | 3.85%   |
| Canon G4010 series              | 1         | 3.85%   |
| Canon E400 series               | 1         | 3.85%   |
| Brother HL-L2370DW series       | 1         | 3.85%   |
| Brother HL-L2320D series        | 1         | 3.85%   |
| Brother HL-3170CDW series       | 1         | 3.85%   |
| Brother HL-2270DW Laser Printer | 1         | 3.85%   |

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
| Chicony Electronics                    | 1019      | 24.12%  |
| IMC Networks                           | 457       | 10.82%  |
| Microdia                               | 424       | 10.04%  |
| Acer                                   | 382       | 9.04%   |
| Realtek Semiconductor                  | 351       | 8.31%   |
| Sunplus Innovation Technology          | 235       | 5.56%   |
| Quanta                                 | 215       | 5.09%   |
| Apple                                  | 187       | 4.43%   |
| Cheng Uei Precision Industry (Foxlink) | 149       | 3.53%   |
| Suyin                                  | 123       | 2.91%   |
| Syntek                                 | 103       | 2.44%   |
| Lite-On Technology                     | 85        | 2.01%   |
| Luxvisions Innotech Limited            | 61        | 1.44%   |
| Silicon Motion                         | 59        | 1.4%    |
| Logitech                               | 56        | 1.33%   |
| Bison Electronics                      | 47        | 1.11%   |
| Ricoh                                  | 37        | 0.88%   |
| Alcor Micro                            | 29        | 0.69%   |
| Samsung Electronics                    | 24        | 0.57%   |
| Sonix Technology                       | 18        | 0.43%   |
| SunplusIT                              | 13        | 0.31%   |
| ALi                                    | 13        | 0.31%   |
| Primax Electronics                     | 11        | 0.26%   |
| Z-Star Microelectronics                | 10        | 0.24%   |
| DigiTech                               | 10        | 0.24%   |
| Microsoft                              | 9         | 0.21%   |
| Lenovo                                 | 9         | 0.21%   |
| Importek                               | 9         | 0.21%   |
| Intel                                  | 7         | 0.17%   |
| Generalplus Technology                 | 6         | 0.14%   |
| OmniVision Technologies                | 5         | 0.12%   |
| MacroSilicon                           | 4         | 0.09%   |
| Foxconn / Hon Hai                      | 4         | 0.09%   |
| USB Camera                             | 3         | 0.07%   |
| Unknown                                | 3         | 0.07%   |
| Tobii Technology AB                    | 3         | 0.07%   |
| Razer USA                              | 3         | 0.07%   |
| AVerMedia Technologies                 | 3         | 0.07%   |
| Alpha Imaging Technology               | 3         | 0.07%   |
| Sunplus Technology                     | 2         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 230       | 5.41%   |
| Chicony Integrated Camera                           | 201       | 4.73%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 150       | 3.53%   |
| Realtek Integrated_Webcam_HD                        | 148       | 3.48%   |
| IMC Networks Integrated Camera                      | 127       | 2.99%   |
| Chicony HD Webcam                                   | 126       | 2.97%   |
| Chicony USB2.0 Camera                               | 98        | 2.31%   |
| Acer BisonCam,NB Pro                                | 95        | 2.24%   |
| Sunplus Integrated_Webcam_HD                        | 70        | 1.65%   |
| Syntek Integrated Camera                            | 63        | 1.48%   |
| Apple Built-in iSight                               | 62        | 1.46%   |
| Apple FaceTime HD Camera                            | 60        | 1.41%   |
| Acer Integrated Camera                              | 58        | 1.37%   |
| Quanta HD User Facing                               | 53        | 1.25%   |
| Acer HD Webcam                                      | 53        | 1.25%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 46        | 1.08%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 42        | 0.99%   |
| Acer BisonCam, NB Pro                               | 38        | 0.89%   |
| Microdia Integrated Webcam                          | 34        | 0.8%    |
| Chicony USB 2.0 Camera                              | 34        | 0.8%    |
| Lite-On Integrated Camera                           | 33        | 0.78%   |
| Chicony TOSHIBA Web Camera - HD                     | 33        | 0.78%   |
| Chicony Integrated Camera (1280x720@30)             | 32        | 0.75%   |
| Chicony HD User Facing                              | 32        | 0.75%   |
| Sunplus HD WebCam                                   | 31        | 0.73%   |
| Chicony HP HD Camera                                | 30        | 0.71%   |
| Sunplus ASUS Webcam                                 | 29        | 0.68%   |
| Chicony USB2.0 HD UVC WebCam                        | 29        | 0.68%   |
| Quanta HD Webcam                                    | 28        | 0.66%   |
| Microdia Laptop_Integrated_Webcam_HD                | 28        | 0.66%   |
| Acer SunplusIT Integrated Camera                    | 28        | 0.66%   |
| Realtek Integrated Webcam                           | 26        | 0.61%   |
| Quanta VGA WebCam                                   | 26        | 0.61%   |
| Chicony USB2.0 VGA UVC WebCam                       | 26        | 0.61%   |
| Chicony HP TrueVision HD Camera                     | 25        | 0.59%   |
| Chicony HP Wide Vision HD Camera                    | 24        | 0.56%   |
| Acer Lenovo EasyCamera                              | 24        | 0.56%   |
| Quanta HP TrueVision HD Camera                      | 23        | 0.54%   |
| Bison Integrated Camera                             | 23        | 0.54%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 22        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 251       | 30.65%  |
| Validity Sensors                   | 248       | 30.28%  |
| Shenzhen Goodix Technology         | 149       | 18.19%  |
| Upek                               | 46        | 5.62%   |
| Elan Microelectronics              | 44        | 5.37%   |
| LighTuning Technology              | 37        | 4.52%   |
| AuthenTec                          | 27        | 3.3%    |
| STMicroelectronics                 | 7         | 0.85%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.37%   |
| Focal-systems.Corp                 | 3         | 0.37%   |
| HOLTEK                             | 2         | 0.24%   |
| Samsung Electronics                | 1         | 0.12%   |
| DigitalPersona                     | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 77        | 9.4%    |
| Shenzhen Goodix  Fingerprint Device                                        | 71        | 8.67%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 56        | 6.84%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 47        | 5.74%   |
| Shenzhen Goodix FingerPrint                                                | 47        | 5.74%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 42        | 5.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 34        | 4.15%   |
| Elan ELAN:Fingerprint                                                      | 33        | 4.03%   |
| Shenzhen Goodix Fingerprint Reader                                         | 31        | 3.79%   |
| Synaptics UWP WBDI                                                         | 28        | 3.42%   |
| Validity Sensors Fingerprint scanner                                       | 20        | 2.44%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 20        | 2.44%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 2.2%    |
| Validity Sensors VFS491                                                    | 18        | 2.2%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 18        | 2.2%    |
| Validity Sensors Synaptics WBDI                                            | 18        | 2.2%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 18        | 2.2%    |
| Synaptics WBDI Device                                                      | 18        | 2.2%    |
| Unknown                                                                    | 16        | 1.95%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 15        | 1.83%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 15        | 1.83%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 11        | 1.34%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 1.34%   |
| Elan ELAN:ARM-M4                                                           | 11        | 1.34%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 9         | 1.1%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.1%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 9         | 1.1%    |
| Synaptics  WBDI                                                            | 8         | 0.98%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 0.98%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 0.98%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 0.85%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.85%   |
| AuthenTec AES2810                                                          | 7         | 0.85%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 0.73%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 0.73%   |
| Synaptics UWP WBDI Device                                                  | 5         | 0.61%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.49%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.49%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.37%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 149       | 47.91%  |
| Alcor Micro               | 83        | 26.69%  |
| Upek                      | 29        | 9.32%   |
| O2 Micro                  | 24        | 7.72%   |
| Lenovo                    | 17        | 5.47%   |
| Gemalto (was Gemplus)     | 2         | 0.64%   |
| Aladdin Knowledge Systems | 2         | 0.64%   |
| SCM Microsystems          | 1         | 0.32%   |
| OmniKey                   | 1         | 0.32%   |
| Giesecke & Devrient       | 1         | 0.32%   |
| Clay Logic                | 1         | 0.32%   |
| Advanced Card Systems     | 1         | 0.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 83        | 26.69%  |
| Broadcom BCM5880 Secure Applications Processor                               | 45        | 14.47%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 40        | 12.86%  |
| Broadcom 5880                                                                | 40        | 12.86%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 29        | 9.32%   |
| Broadcom 58200                                                               | 22        | 7.07%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 20        | 6.43%   |
| Lenovo Integrated Smart Card Reader                                          | 17        | 5.47%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.29%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.64%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.64%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.32%   |
| OmniKey CardMan 4321                                                         | 1         | 0.32%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.32%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.32%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.32%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.32%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.32%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2993      | 62.06%  |
| 1     | 1441      | 29.88%  |
| 2     | 335       | 6.95%   |
| 3     | 48        | 1%      |
| 4     | 5         | 0.1%    |
| 5     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 798       | 36.22%  |
| Multimedia controller    | 305       | 13.84%  |
| Chipcard                 | 303       | 13.75%  |
| Graphics card            | 273       | 12.39%  |
| Net/wireless             | 256       | 11.62%  |
| Bluetooth                | 64        | 2.91%   |
| Camera                   | 48        | 2.18%   |
| Storage                  | 37        | 1.68%   |
| Net/ethernet             | 28        | 1.27%   |
| Sound                    | 24        | 1.09%   |
| Card reader              | 18        | 0.82%   |
| Communication controller | 15        | 0.68%   |
| Network                  | 10        | 0.45%   |
| Modem                    | 10        | 0.45%   |
| Storage/ide              | 5         | 0.23%   |
| Storage/nvme             | 3         | 0.14%   |
| Flash memory             | 2         | 0.09%   |
| Firewire controller      | 2         | 0.09%   |
| Unclassified device      | 1         | 0.05%   |
| Dvb card                 | 1         | 0.05%   |

