Pop!_OS - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS/Desktop/README.md) and [notebooks](/Dist/Pop!_OS/Notebook/README.md).

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

Total: 12794

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 7275               | Tablet      | [c118ca04bc](https://linux-hardware.org/?probe=c118ca04bc) | Apr 01, 2023 |
| Lenovo        | IdeaPad U310                | Notebook    | [6add75e18c](https://linux-hardware.org/?probe=6add75e18c) | Apr 01, 2023 |
| Lenovo        | 4030                        | Desktop     | [7a23fd4fb4](https://linux-hardware.org/?probe=7a23fd4fb4) | Apr 01, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [6d4878cdbf](https://linux-hardware.org/?probe=6d4878cdbf) | Apr 01, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [f7c90851ac](https://linux-hardware.org/?probe=f7c90851ac) | Apr 01, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [44e093df31](https://linux-hardware.org/?probe=44e093df31) | Apr 01, 2023 |
| System76      | Lemur Pro                   | Notebook    | [5d57a3397e](https://linux-hardware.org/?probe=5d57a3397e) | Mar 31, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [fc44ad8c07](https://linux-hardware.org/?probe=fc44ad8c07) | Mar 31, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [6f4a645737](https://linux-hardware.org/?probe=6f4a645737) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [61e2653466](https://linux-hardware.org/?probe=61e2653466) | Mar 31, 2023 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [11b3a7cdb1](https://linux-hardware.org/?probe=11b3a7cdb1) | Mar 31, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [2ef82331de](https://linux-hardware.org/?probe=2ef82331de) | Mar 31, 2023 |
| Supermicro    | X10SLV                      | Server      | [b61612a8a8](https://linux-hardware.org/?probe=b61612a8a8) | Mar 31, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [c346cf16d3](https://linux-hardware.org/?probe=c346cf16d3) | Mar 30, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [bf846cebb9](https://linux-hardware.org/?probe=bf846cebb9) | Mar 30, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [27befad01f](https://linux-hardware.org/?probe=27befad01f) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [21515b7373](https://linux-hardware.org/?probe=21515b7373) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [080e22fdb2](https://linux-hardware.org/?probe=080e22fdb2) | Mar 30, 2023 |
| HP            | 0AA4h                       | Desktop     | [97457bb10c](https://linux-hardware.org/?probe=97457bb10c) | Mar 30, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [af4901f141](https://linux-hardware.org/?probe=af4901f141) | Mar 30, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [cec51b833f](https://linux-hardware.org/?probe=cec51b833f) | Mar 30, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [13f35137bd](https://linux-hardware.org/?probe=13f35137bd) | Mar 30, 2023 |
| Foxconn       | 2AB1 DVT                    | Desktop     | [a9e8e4d4b0](https://linux-hardware.org/?probe=a9e8e4d4b0) | Mar 30, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [81dda92e58](https://linux-hardware.org/?probe=81dda92e58) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [7ee1845d96](https://linux-hardware.org/?probe=7ee1845d96) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [bb80f561a2](https://linux-hardware.org/?probe=bb80f561a2) | Mar 30, 2023 |
| HP            | 8433 11                     | Desktop     | [55f7473ba8](https://linux-hardware.org/?probe=55f7473ba8) | Mar 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [854490056d](https://linux-hardware.org/?probe=854490056d) | Mar 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [059358e49b](https://linux-hardware.org/?probe=059358e49b) | Mar 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [78046d9b99](https://linux-hardware.org/?probe=78046d9b99) | Mar 29, 2023 |
| HP            | 0AA4h                       | Desktop     | [801f843749](https://linux-hardware.org/?probe=801f843749) | Mar 29, 2023 |
| Win elemen... | M600                        | Desktop     | [7cf2343b6f](https://linux-hardware.org/?probe=7cf2343b6f) | Mar 29, 2023 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [c994f20b64](https://linux-hardware.org/?probe=c994f20b64) | Mar 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [af48722867](https://linux-hardware.org/?probe=af48722867) | Mar 28, 2023 |
| Dell          | G3 3590                     | Notebook    | [f61ce9bb82](https://linux-hardware.org/?probe=f61ce9bb82) | Mar 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0667374075](https://linux-hardware.org/?probe=0667374075) | Mar 28, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [0aabfe954d](https://linux-hardware.org/?probe=0aabfe954d) | Mar 28, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [7939320fa4](https://linux-hardware.org/?probe=7939320fa4) | Mar 28, 2023 |
| Positivo      | Mobile                      | Notebook    | [60fd382fbf](https://linux-hardware.org/?probe=60fd382fbf) | Mar 28, 2023 |
| Positivo      | Mobile                      | Notebook    | [b08c430903](https://linux-hardware.org/?probe=b08c430903) | Mar 28, 2023 |
| HP            | 09F0h                       | Desktop     | [540ec71101](https://linux-hardware.org/?probe=540ec71101) | Mar 28, 2023 |
| Razer         | Blade                       | Notebook    | [ffa791eb4a](https://linux-hardware.org/?probe=ffa791eb4a) | Mar 28, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [61382d0bd8](https://linux-hardware.org/?probe=61382d0bd8) | Mar 28, 2023 |
| ASRock        | H510M-HVS                   | Desktop     | [97744fad07](https://linux-hardware.org/?probe=97744fad07) | Mar 28, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [d2b4780094](https://linux-hardware.org/?probe=d2b4780094) | Mar 28, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [635309aff4](https://linux-hardware.org/?probe=635309aff4) | Mar 28, 2023 |
| ASRock        | B650M PG Riptide WiFi       | Desktop     | [f17c95f91b](https://linux-hardware.org/?probe=f17c95f91b) | Mar 28, 2023 |
| ASRock        | B650M PG Riptide WiFi       | Desktop     | [1b67e2c4fd](https://linux-hardware.org/?probe=1b67e2c4fd) | Mar 28, 2023 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [cde470cb39](https://linux-hardware.org/?probe=cde470cb39) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c4bba42d7b](https://linux-hardware.org/?probe=c4bba42d7b) | Mar 28, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T400     | Notebook    | [5b4466c085](https://linux-hardware.org/?probe=5b4466c085) | Mar 28, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [8ddee342c9](https://linux-hardware.org/?probe=8ddee342c9) | Mar 28, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [adee3bbdde](https://linux-hardware.org/?probe=adee3bbdde) | Mar 28, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [f6236c5962](https://linux-hardware.org/?probe=f6236c5962) | Mar 27, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [5be538736f](https://linux-hardware.org/?probe=5be538736f) | Mar 27, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [d7ec0eb4b1](https://linux-hardware.org/?probe=d7ec0eb4b1) | Mar 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [878fa94b87](https://linux-hardware.org/?probe=878fa94b87) | Mar 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [a5c200217f](https://linux-hardware.org/?probe=a5c200217f) | Mar 26, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [8ffc3ea292](https://linux-hardware.org/?probe=8ffc3ea292) | Mar 26, 2023 |
| MSI           | Z490 PLUS                   | Desktop     | [06032b5e04](https://linux-hardware.org/?probe=06032b5e04) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | Desktop     | [479aff4877](https://linux-hardware.org/?probe=479aff4877) | Mar 26, 2023 |
| MSI           | GL63 8RC                    | Notebook    | [935b78c3da](https://linux-hardware.org/?probe=935b78c3da) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | Desktop     | [67ddc813cf](https://linux-hardware.org/?probe=67ddc813cf) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [537fc6af0e](https://linux-hardware.org/?probe=537fc6af0e) | Mar 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [55c29cec29](https://linux-hardware.org/?probe=55c29cec29) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [fc01cd79a4](https://linux-hardware.org/?probe=fc01cd79a4) | Mar 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c08caf1dee](https://linux-hardware.org/?probe=c08caf1dee) | Mar 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [905078c7b9](https://linux-hardware.org/?probe=905078c7b9) | Mar 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [f6f4996c63](https://linux-hardware.org/?probe=f6f4996c63) | Mar 26, 2023 |
| Dell          | Latitude E7240              | Notebook    | [3d91b46fda](https://linux-hardware.org/?probe=3d91b46fda) | Mar 26, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [3f3967267f](https://linux-hardware.org/?probe=3f3967267f) | Mar 26, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [61897b32de](https://linux-hardware.org/?probe=61897b32de) | Mar 25, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0f7d28bd43](https://linux-hardware.org/?probe=0f7d28bd43) | Mar 25, 2023 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [6fdc683220](https://linux-hardware.org/?probe=6fdc683220) | Mar 25, 2023 |
| MSI           | Katana GF66 12UG            | Notebook    | [9e03ac14c0](https://linux-hardware.org/?probe=9e03ac14c0) | Mar 25, 2023 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [6c64b62e05](https://linux-hardware.org/?probe=6c64b62e05) | Mar 25, 2023 |
| Intel         | NUC10i3FNB K61362-305       | Mini pc     | [26c0bb67b6](https://linux-hardware.org/?probe=26c0bb67b6) | Mar 25, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [811be842de](https://linux-hardware.org/?probe=811be842de) | Mar 25, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [21c3ce9508](https://linux-hardware.org/?probe=21c3ce9508) | Mar 24, 2023 |
| Dell          | 0PC5F7 A01                  | Desktop     | [61550296b7](https://linux-hardware.org/?probe=61550296b7) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ac415822b8](https://linux-hardware.org/?probe=ac415822b8) | Mar 24, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ad0e5c0483](https://linux-hardware.org/?probe=ad0e5c0483) | Mar 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [e6afbbee47](https://linux-hardware.org/?probe=e6afbbee47) | Mar 24, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [f78f58795c](https://linux-hardware.org/?probe=f78f58795c) | Mar 24, 2023 |
| HP            | 212B                        | Desktop     | [266912cedd](https://linux-hardware.org/?probe=266912cedd) | Mar 24, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f5cbf68e6d](https://linux-hardware.org/?probe=f5cbf68e6d) | Mar 24, 2023 |
| Alienware     | 17 R4                       | Notebook    | [3c456dc309](https://linux-hardware.org/?probe=3c456dc309) | Mar 24, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [9007c1d23f](https://linux-hardware.org/?probe=9007c1d23f) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Notebook    | [f8f47e3220](https://linux-hardware.org/?probe=f8f47e3220) | Mar 23, 2023 |
| Dell          | Precision 7710              | Notebook    | [25a4797475](https://linux-hardware.org/?probe=25a4797475) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [09fec047e4](https://linux-hardware.org/?probe=09fec047e4) | Mar 23, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [3a75d7fb8d](https://linux-hardware.org/?probe=3a75d7fb8d) | Mar 23, 2023 |
| MSI           | MPG Z590 GAMING FORCE       | Desktop     | [7a3319972e](https://linux-hardware.org/?probe=7a3319972e) | Mar 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [c06eaca849](https://linux-hardware.org/?probe=c06eaca849) | Mar 23, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [aba9609828](https://linux-hardware.org/?probe=aba9609828) | Mar 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [f6580b20d3](https://linux-hardware.org/?probe=f6580b20d3) | Mar 22, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [dab7a6edbc](https://linux-hardware.org/?probe=dab7a6edbc) | Mar 22, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [bc6e3fa274](https://linux-hardware.org/?probe=bc6e3fa274) | Mar 22, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d458338d97](https://linux-hardware.org/?probe=d458338d97) | Mar 22, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [627590f38c](https://linux-hardware.org/?probe=627590f38c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | Notebook    | [a49ece0e6c](https://linux-hardware.org/?probe=a49ece0e6c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | Notebook    | [315f2256c6](https://linux-hardware.org/?probe=315f2256c6) | Mar 22, 2023 |
| Dell          | 0RK936                      | Desktop     | [af3e7f60cb](https://linux-hardware.org/?probe=af3e7f60cb) | Mar 22, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b616377b13](https://linux-hardware.org/?probe=b616377b13) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [aff8d829e0](https://linux-hardware.org/?probe=aff8d829e0) | Mar 22, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [99fe9f96c6](https://linux-hardware.org/?probe=99fe9f96c6) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [af60ed4cde](https://linux-hardware.org/?probe=af60ed4cde) | Mar 22, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [3b3376e72c](https://linux-hardware.org/?probe=3b3376e72c) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [b4c65fead7](https://linux-hardware.org/?probe=b4c65fead7) | Mar 21, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [afc1ff125b](https://linux-hardware.org/?probe=afc1ff125b) | Mar 21, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [3c100c55be](https://linux-hardware.org/?probe=3c100c55be) | Mar 21, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [039724e2c2](https://linux-hardware.org/?probe=039724e2c2) | Mar 21, 2023 |
| Dell          | G15 5511                    | Notebook    | [6d71997e08](https://linux-hardware.org/?probe=6d71997e08) | Mar 21, 2023 |
| Dell          | XPS L421X                   | Notebook    | [fd54af9534](https://linux-hardware.org/?probe=fd54af9534) | Mar 21, 2023 |
| Dell          | 0RK936                      | Desktop     | [6c2680e4e9](https://linux-hardware.org/?probe=6c2680e4e9) | Mar 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [afe8ca841c](https://linux-hardware.org/?probe=afe8ca841c) | Mar 21, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [c0f5810e5c](https://linux-hardware.org/?probe=c0f5810e5c) | Mar 21, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [cac8d6b991](https://linux-hardware.org/?probe=cac8d6b991) | Mar 21, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [d6ff521952](https://linux-hardware.org/?probe=d6ff521952) | Mar 21, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [16253cadcf](https://linux-hardware.org/?probe=16253cadcf) | Mar 21, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [d6393f5710](https://linux-hardware.org/?probe=d6393f5710) | Mar 21, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [404c84b0ea](https://linux-hardware.org/?probe=404c84b0ea) | Mar 21, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [d4e033725b](https://linux-hardware.org/?probe=d4e033725b) | Mar 21, 2023 |
| Supermicro    | X9SAE                       | Desktop     | [01195f072e](https://linux-hardware.org/?probe=01195f072e) | Mar 21, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [edf722e245](https://linux-hardware.org/?probe=edf722e245) | Mar 21, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [5ea7504472](https://linux-hardware.org/?probe=5ea7504472) | Mar 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | Notebook    | [2ff2eab844](https://linux-hardware.org/?probe=2ff2eab844) | Mar 21, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [d2b90b7d2f](https://linux-hardware.org/?probe=d2b90b7d2f) | Mar 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [2ef051fd19](https://linux-hardware.org/?probe=2ef051fd19) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [48de9eb9e3](https://linux-hardware.org/?probe=48de9eb9e3) | Mar 20, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [b133c68356](https://linux-hardware.org/?probe=b133c68356) | Mar 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [afcac034a9](https://linux-hardware.org/?probe=afcac034a9) | Mar 20, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [d08f174747](https://linux-hardware.org/?probe=d08f174747) | Mar 20, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Notebook    | [c9b4e3cf00](https://linux-hardware.org/?probe=c9b4e3cf00) | Mar 20, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [3fe3c818f7](https://linux-hardware.org/?probe=3fe3c818f7) | Mar 20, 2023 |
| Dell          | Latitude 5590               | Notebook    | [49922a3223](https://linux-hardware.org/?probe=49922a3223) | Mar 19, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [55dc5e3ef4](https://linux-hardware.org/?probe=55dc5e3ef4) | Mar 19, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [22290c7abf](https://linux-hardware.org/?probe=22290c7abf) | Mar 19, 2023 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [6681949ccc](https://linux-hardware.org/?probe=6681949ccc) | Mar 19, 2023 |
| MSI           | PS42 8M                     | Notebook    | [aad18852f4](https://linux-hardware.org/?probe=aad18852f4) | Mar 19, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [d0079fa594](https://linux-hardware.org/?probe=d0079fa594) | Mar 19, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [f7f92408dc](https://linux-hardware.org/?probe=f7f92408dc) | Mar 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6b6ceb1a1a](https://linux-hardware.org/?probe=6b6ceb1a1a) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e3410282c5](https://linux-hardware.org/?probe=e3410282c5) | Mar 19, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c462ccc41a](https://linux-hardware.org/?probe=c462ccc41a) | Mar 19, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [0139691951](https://linux-hardware.org/?probe=0139691951) | Mar 19, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [22e0286a24](https://linux-hardware.org/?probe=22e0286a24) | Mar 19, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [0018c1237d](https://linux-hardware.org/?probe=0018c1237d) | Mar 19, 2023 |
| Dell          | 0WMJ54 A00                  | Desktop     | [bcb1a34cf2](https://linux-hardware.org/?probe=bcb1a34cf2) | Mar 19, 2023 |
| ASUSTek       | S551LB                      | Notebook    | [7d4485326f](https://linux-hardware.org/?probe=7d4485326f) | Mar 18, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [ff8db61ccf](https://linux-hardware.org/?probe=ff8db61ccf) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [4eab8887fa](https://linux-hardware.org/?probe=4eab8887fa) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [b3bf824f3a](https://linux-hardware.org/?probe=b3bf824f3a) | Mar 18, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Notebook    | [dd296a8801](https://linux-hardware.org/?probe=dd296a8801) | Mar 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S11N00    | Notebook    | [60d80937ea](https://linux-hardware.org/?probe=60d80937ea) | Mar 18, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [dc411c9ce3](https://linux-hardware.org/?probe=dc411c9ce3) | Mar 18, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [91ae5652cc](https://linux-hardware.org/?probe=91ae5652cc) | Mar 18, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [274f959cfc](https://linux-hardware.org/?probe=274f959cfc) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [c4bebd7028](https://linux-hardware.org/?probe=c4bebd7028) | Mar 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [2389fcea33](https://linux-hardware.org/?probe=2389fcea33) | Mar 17, 2023 |
| Dell          | Latitude E7240              | Notebook    | [cbcae7df75](https://linux-hardware.org/?probe=cbcae7df75) | Mar 17, 2023 |
| Intel         | X99 V1.x                    | Desktop     | [9b471dcdcf](https://linux-hardware.org/?probe=9b471dcdcf) | Mar 17, 2023 |
| Positivo      | N1250                       | Notebook    | [e5ee22876a](https://linux-hardware.org/?probe=e5ee22876a) | Mar 17, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [557a99333f](https://linux-hardware.org/?probe=557a99333f) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [27356d58d5](https://linux-hardware.org/?probe=27356d58d5) | Mar 17, 2023 |
| HP            | 843F                        | Desktop     | [e444e0d76a](https://linux-hardware.org/?probe=e444e0d76a) | Mar 17, 2023 |
| HP            | ProBook 4530s               | Notebook    | [f0abd32fe4](https://linux-hardware.org/?probe=f0abd32fe4) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | Notebook    | [a7a6cc1ab5](https://linux-hardware.org/?probe=a7a6cc1ab5) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | Notebook    | [204994be7f](https://linux-hardware.org/?probe=204994be7f) | Mar 17, 2023 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [525b267c31](https://linux-hardware.org/?probe=525b267c31) | Mar 17, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [b20fcd6878](https://linux-hardware.org/?probe=b20fcd6878) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [a1adc8641d](https://linux-hardware.org/?probe=a1adc8641d) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [a0eea87e02](https://linux-hardware.org/?probe=a0eea87e02) | Mar 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [3eb0bf05b4](https://linux-hardware.org/?probe=3eb0bf05b4) | Mar 17, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0RP0... | Notebook    | [f901058202](https://linux-hardware.org/?probe=f901058202) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d6f5cd9505](https://linux-hardware.org/?probe=d6f5cd9505) | Mar 16, 2023 |
| Dell          | 02GDWG A00                  | Desktop     | [c81ac4434e](https://linux-hardware.org/?probe=c81ac4434e) | Mar 16, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | Notebook    | [5f48c46d68](https://linux-hardware.org/?probe=5f48c46d68) | Mar 16, 2023 |
| Microsoft     | Surface Book                | Tablet      | [d5cd9be69a](https://linux-hardware.org/?probe=d5cd9be69a) | Mar 16, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [67d6333f85](https://linux-hardware.org/?probe=67d6333f85) | Mar 15, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [59a304e790](https://linux-hardware.org/?probe=59a304e790) | Mar 15, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [8bdae79f7a](https://linux-hardware.org/?probe=8bdae79f7a) | Mar 15, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | Notebook    | [6a2d338526](https://linux-hardware.org/?probe=6a2d338526) | Mar 15, 2023 |
| ASUSTek       | Z87-K                       | Desktop     | [fe2d844bfb](https://linux-hardware.org/?probe=fe2d844bfb) | Mar 15, 2023 |
| Razer         | Blade Stealth 13 (Early ... | Notebook    | [eb1d71edb4](https://linux-hardware.org/?probe=eb1d71edb4) | Mar 15, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | Notebook    | [af254fca4d](https://linux-hardware.org/?probe=af254fca4d) | Mar 15, 2023 |
| SAGER         | X8100                       | Notebook    | [90aaefeb9e](https://linux-hardware.org/?probe=90aaefeb9e) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [88c4c221af](https://linux-hardware.org/?probe=88c4c221af) | Mar 15, 2023 |
| Huanan        | X99-AD3 GAMING V2.0         | Desktop     | [0586633e29](https://linux-hardware.org/?probe=0586633e29) | Mar 15, 2023 |
| ASUSTek       | PRIME Z790-P WIFI D4        | Desktop     | [e8bbe7a962](https://linux-hardware.org/?probe=e8bbe7a962) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [0c74f7b048](https://linux-hardware.org/?probe=0c74f7b048) | Mar 15, 2023 |
| System76      | Pangolin                    | Notebook    | [4f39796131](https://linux-hardware.org/?probe=4f39796131) | Mar 15, 2023 |
| Dell          | Latitude E7240              | Notebook    | [d4ed345a47](https://linux-hardware.org/?probe=d4ed345a47) | Mar 14, 2023 |
| ASRock        | B550 Extreme4               | Desktop     | [9a139b5bad](https://linux-hardware.org/?probe=9a139b5bad) | Mar 14, 2023 |
| Lenovo        | ThinkPad T450s 20BWS14G0... | Notebook    | [1161c07721](https://linux-hardware.org/?probe=1161c07721) | Mar 14, 2023 |
| Sony          | VPCZ12V9R                   | Notebook    | [28be5f7f2b](https://linux-hardware.org/?probe=28be5f7f2b) | Mar 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [4a7d442938](https://linux-hardware.org/?probe=4a7d442938) | Mar 14, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [44d9ce8acb](https://linux-hardware.org/?probe=44d9ce8acb) | Mar 14, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [986fe8c418](https://linux-hardware.org/?probe=986fe8c418) | Mar 14, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [95248fc9a0](https://linux-hardware.org/?probe=95248fc9a0) | Mar 14, 2023 |
| Dell          | 0RK936                      | Desktop     | [59cbc1f071](https://linux-hardware.org/?probe=59cbc1f071) | Mar 14, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | Notebook    | [ae9f2da5a4](https://linux-hardware.org/?probe=ae9f2da5a4) | Mar 14, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [874706952d](https://linux-hardware.org/?probe=874706952d) | Mar 14, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [de22b8a7e6](https://linux-hardware.org/?probe=de22b8a7e6) | Mar 14, 2023 |
| Dell          | Inspiron 7348               | Notebook    | [7459d24035](https://linux-hardware.org/?probe=7459d24035) | Mar 13, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [f85095c103](https://linux-hardware.org/?probe=f85095c103) | Mar 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f5215489c7](https://linux-hardware.org/?probe=f5215489c7) | Mar 13, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [b03c056ee1](https://linux-hardware.org/?probe=b03c056ee1) | Mar 13, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [b93a4bdcbb](https://linux-hardware.org/?probe=b93a4bdcbb) | Mar 13, 2023 |
| Acer          | Aspire 4530                 | Notebook    | [84f4733a96](https://linux-hardware.org/?probe=84f4733a96) | Mar 13, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [7f2ecd927d](https://linux-hardware.org/?probe=7f2ecd927d) | Mar 13, 2023 |
| Gateway       | WG43M                       | Desktop     | [c1ab165971](https://linux-hardware.org/?probe=c1ab165971) | Mar 13, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [663f73a08e](https://linux-hardware.org/?probe=663f73a08e) | Mar 13, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [5d1a30091e](https://linux-hardware.org/?probe=5d1a30091e) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [a826b1cd32](https://linux-hardware.org/?probe=a826b1cd32) | Mar 13, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [0e2618e3ea](https://linux-hardware.org/?probe=0e2618e3ea) | Mar 12, 2023 |
| Dell          | 0DFRFW A01                  | Desktop     | [1b8b00dbc5](https://linux-hardware.org/?probe=1b8b00dbc5) | Mar 12, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | Notebook    | [87ef2f6efb](https://linux-hardware.org/?probe=87ef2f6efb) | Mar 12, 2023 |
| HP            | ProLiant DL380 G7           | Server      | [9911027e53](https://linux-hardware.org/?probe=9911027e53) | Mar 12, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [27b710cd68](https://linux-hardware.org/?probe=27b710cd68) | Mar 12, 2023 |
| Google        | Kefka                       | Notebook    | [4a54e34e44](https://linux-hardware.org/?probe=4a54e34e44) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [7090114437](https://linux-hardware.org/?probe=7090114437) | Mar 12, 2023 |
| Dell          | Inspiron 5452               | Notebook    | [2c8ca0e296](https://linux-hardware.org/?probe=2c8ca0e296) | Mar 12, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [47ea9647d3](https://linux-hardware.org/?probe=47ea9647d3) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [75fc2c0a15](https://linux-hardware.org/?probe=75fc2c0a15) | Mar 12, 2023 |
| Positivo B... | VJFE41F11X-XXXXXX           | Notebook    | [99f410d801](https://linux-hardware.org/?probe=99f410d801) | Mar 11, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [e101a1c94c](https://linux-hardware.org/?probe=e101a1c94c) | Mar 11, 2023 |
| Acer          | Aspire X1935                | Desktop     | [6846ecd490](https://linux-hardware.org/?probe=6846ecd490) | Mar 11, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [d8cf10f11d](https://linux-hardware.org/?probe=d8cf10f11d) | Mar 11, 2023 |
| HP            | ZBook 17                    | Notebook    | [a775bc33c5](https://linux-hardware.org/?probe=a775bc33c5) | Mar 11, 2023 |
| Maibenben     | P748                        | Notebook    | [a44d1bb8e4](https://linux-hardware.org/?probe=a44d1bb8e4) | Mar 11, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [39cc207ce7](https://linux-hardware.org/?probe=39cc207ce7) | Mar 11, 2023 |
| Lenovo        | ThinkPad L440 20ASS0ET00    | Notebook    | [2ac6dfff4f](https://linux-hardware.org/?probe=2ac6dfff4f) | Mar 11, 2023 |
| GPD           | G1619-04                    | Notebook    | [302ff30130](https://linux-hardware.org/?probe=302ff30130) | Mar 11, 2023 |
| GPD           | G1619-04                    | Notebook    | [d8f5b9eec9](https://linux-hardware.org/?probe=d8f5b9eec9) | Mar 11, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [8736fd04a8](https://linux-hardware.org/?probe=8736fd04a8) | Mar 11, 2023 |
| Dell          | 0KC9NP A00                  | Desktop     | [873a2bf50c](https://linux-hardware.org/?probe=873a2bf50c) | Mar 11, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [9535f3676b](https://linux-hardware.org/?probe=9535f3676b) | Mar 10, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [fca941c098](https://linux-hardware.org/?probe=fca941c098) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Notebook    | [96f4bd0a52](https://linux-hardware.org/?probe=96f4bd0a52) | Mar 10, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [ccba86bda3](https://linux-hardware.org/?probe=ccba86bda3) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Notebook    | [969ab4279f](https://linux-hardware.org/?probe=969ab4279f) | Mar 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [c44f0eab3e](https://linux-hardware.org/?probe=c44f0eab3e) | Mar 10, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | Notebook    | [44867c946f](https://linux-hardware.org/?probe=44867c946f) | Mar 10, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [dbdadff4f2](https://linux-hardware.org/?probe=dbdadff4f2) | Mar 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [50dd87563b](https://linux-hardware.org/?probe=50dd87563b) | Mar 10, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [e183f14e7e](https://linux-hardware.org/?probe=e183f14e7e) | Mar 10, 2023 |
| Samsung       | R430/R480/R440              | Notebook    | [cdb2525b51](https://linux-hardware.org/?probe=cdb2525b51) | Mar 10, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [410a5a70f3](https://linux-hardware.org/?probe=410a5a70f3) | Mar 10, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [eac4ae85a4](https://linux-hardware.org/?probe=eac4ae85a4) | Mar 10, 2023 |
| Positivo      | POS-PIQ77CL                 | Desktop     | [789838055a](https://linux-hardware.org/?probe=789838055a) | Mar 10, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [baffc24bef](https://linux-hardware.org/?probe=baffc24bef) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [214efb1e94](https://linux-hardware.org/?probe=214efb1e94) | Mar 09, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [187761b57d](https://linux-hardware.org/?probe=187761b57d) | Mar 09, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [4e1196658a](https://linux-hardware.org/?probe=4e1196658a) | Mar 09, 2023 |
| HP            | ENVY Notebook               | Notebook    | [8a063efa19](https://linux-hardware.org/?probe=8a063efa19) | Mar 09, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [670e89da85](https://linux-hardware.org/?probe=670e89da85) | Mar 09, 2023 |
| Gigabyte      | H110M-DS2V DDR3-CF          | Desktop     | [d101f34459](https://linux-hardware.org/?probe=d101f34459) | Mar 09, 2023 |
| HP            | ProLiant DL360p Gen8        | Server      | [b483cfbad7](https://linux-hardware.org/?probe=b483cfbad7) | Mar 09, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [a8d1bd3e81](https://linux-hardware.org/?probe=a8d1bd3e81) | Mar 09, 2023 |
| MSI           | X58 PLATINUM SLI            | Desktop     | [c8875fb17f](https://linux-hardware.org/?probe=c8875fb17f) | Mar 08, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [7805fe229d](https://linux-hardware.org/?probe=7805fe229d) | Mar 08, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [dfd9b7a9b9](https://linux-hardware.org/?probe=dfd9b7a9b9) | Mar 08, 2023 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [46fa9eab7d](https://linux-hardware.org/?probe=46fa9eab7d) | Mar 08, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [b99222314c](https://linux-hardware.org/?probe=b99222314c) | Mar 08, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [4f64764c75](https://linux-hardware.org/?probe=4f64764c75) | Mar 08, 2023 |
| Dell          | 051FJ8 A02                  | Desktop     | [4c15877e95](https://linux-hardware.org/?probe=4c15877e95) | Mar 08, 2023 |
| Google        | Bobba                       | Notebook    | [01d8f57c7e](https://linux-hardware.org/?probe=01d8f57c7e) | Mar 08, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [6ddf3ecd86](https://linux-hardware.org/?probe=6ddf3ecd86) | Mar 08, 2023 |
| ASRock        | 890GX Extreme3              | Desktop     | [4d59bfb158](https://linux-hardware.org/?probe=4d59bfb158) | Mar 08, 2023 |
| Lenovo        | IdeaPad U310                | Notebook    | [f666446ecb](https://linux-hardware.org/?probe=f666446ecb) | Mar 07, 2023 |
| HP            | 83E9                        | Desktop     | [9a756f9158](https://linux-hardware.org/?probe=9a756f9158) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3ff5ff8f2d](https://linux-hardware.org/?probe=3ff5ff8f2d) | Mar 07, 2023 |
| ASRock        | G41M-GS3                    | Desktop     | [9e11e1f2af](https://linux-hardware.org/?probe=9e11e1f2af) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [3b02985778](https://linux-hardware.org/?probe=3b02985778) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [e6e0d7226d](https://linux-hardware.org/?probe=e6e0d7226d) | Mar 07, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [8c709c4723](https://linux-hardware.org/?probe=8c709c4723) | Mar 07, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [4a698cb3eb](https://linux-hardware.org/?probe=4a698cb3eb) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [8a6c736217](https://linux-hardware.org/?probe=8a6c736217) | Mar 07, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [12954ccbdb](https://linux-hardware.org/?probe=12954ccbdb) | Mar 07, 2023 |
| Google        | Lillipup                    | Notebook    | [b924f92de8](https://linux-hardware.org/?probe=b924f92de8) | Mar 07, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [5a03b7e11e](https://linux-hardware.org/?probe=5a03b7e11e) | Mar 07, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [bef545e821](https://linux-hardware.org/?probe=bef545e821) | Mar 07, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [bfc1bf412e](https://linux-hardware.org/?probe=bfc1bf412e) | Mar 06, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [625691c490](https://linux-hardware.org/?probe=625691c490) | Mar 06, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [66b4f88fb7](https://linux-hardware.org/?probe=66b4f88fb7) | Mar 06, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [5656c3015d](https://linux-hardware.org/?probe=5656c3015d) | Mar 06, 2023 |
| HP            | 3115m                       | Notebook    | [87abd0ac9d](https://linux-hardware.org/?probe=87abd0ac9d) | Mar 06, 2023 |
| Dell          | G7 7588                     | Notebook    | [a50e6bef64](https://linux-hardware.org/?probe=a50e6bef64) | Mar 06, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [76ebbe553f](https://linux-hardware.org/?probe=76ebbe553f) | Mar 06, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [ae4d8e9128](https://linux-hardware.org/?probe=ae4d8e9128) | Mar 06, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [e82fbd8c0a](https://linux-hardware.org/?probe=e82fbd8c0a) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [da3b20e7c1](https://linux-hardware.org/?probe=da3b20e7c1) | Mar 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [baff849073](https://linux-hardware.org/?probe=baff849073) | Mar 05, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [a6c8ba1040](https://linux-hardware.org/?probe=a6c8ba1040) | Mar 05, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [eb3f7a337f](https://linux-hardware.org/?probe=eb3f7a337f) | Mar 05, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [fef18d1795](https://linux-hardware.org/?probe=fef18d1795) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [779113ef3c](https://linux-hardware.org/?probe=779113ef3c) | Mar 05, 2023 |
| HP            | Pavilion 15                 | Notebook    | [0c4050d1ef](https://linux-hardware.org/?probe=0c4050d1ef) | Mar 05, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [ff4621a345](https://linux-hardware.org/?probe=ff4621a345) | Mar 05, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [b75483941a](https://linux-hardware.org/?probe=b75483941a) | Mar 05, 2023 |
| Dell          | Latitude 5420               | Notebook    | [ea5ac72a44](https://linux-hardware.org/?probe=ea5ac72a44) | Mar 05, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [a655c49d8b](https://linux-hardware.org/?probe=a655c49d8b) | Mar 05, 2023 |
| HP            | 339A                        | Desktop     | [a2af229dad](https://linux-hardware.org/?probe=a2af229dad) | Mar 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [b73251069c](https://linux-hardware.org/?probe=b73251069c) | Mar 05, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [efd2d0c074](https://linux-hardware.org/?probe=efd2d0c074) | Mar 05, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [ca5a019457](https://linux-hardware.org/?probe=ca5a019457) | Mar 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [ba908d3339](https://linux-hardware.org/?probe=ba908d3339) | Mar 04, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [c3d6a142c0](https://linux-hardware.org/?probe=c3d6a142c0) | Mar 04, 2023 |
| Lenovo        | ThinkPad E490 20N8005JMH    | Notebook    | [26ca476e1a](https://linux-hardware.org/?probe=26ca476e1a) | Mar 04, 2023 |
| Dell          | System XPS L321X            | Notebook    | [24d0d12eca](https://linux-hardware.org/?probe=24d0d12eca) | Mar 04, 2023 |
| Lenovo        | ThinkPad X270 20HN001RUS    | Notebook    | [ccda7b2155](https://linux-hardware.org/?probe=ccda7b2155) | Mar 04, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [87cdc5bd5a](https://linux-hardware.org/?probe=87cdc5bd5a) | Mar 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ca004eceae](https://linux-hardware.org/?probe=ca004eceae) | Mar 03, 2023 |
| Acer          | Aspire M3970                | Desktop     | [2708d5fa99](https://linux-hardware.org/?probe=2708d5fa99) | Mar 03, 2023 |
| Gigabyte      | AORUS 17 XE4                | Notebook    | [6f6750ee73](https://linux-hardware.org/?probe=6f6750ee73) | Mar 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [db92a5f137](https://linux-hardware.org/?probe=db92a5f137) | Mar 03, 2023 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [1a24f06457](https://linux-hardware.org/?probe=1a24f06457) | Mar 03, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [9ce5a599cd](https://linux-hardware.org/?probe=9ce5a599cd) | Mar 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [141faab02f](https://linux-hardware.org/?probe=141faab02f) | Mar 03, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [c2d6b5218e](https://linux-hardware.org/?probe=c2d6b5218e) | Mar 03, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [840dab3a7c](https://linux-hardware.org/?probe=840dab3a7c) | Mar 03, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [6ea9159a52](https://linux-hardware.org/?probe=6ea9159a52) | Mar 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [8ce5103cac](https://linux-hardware.org/?probe=8ce5103cac) | Mar 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | Notebook    | [e73235d592](https://linux-hardware.org/?probe=e73235d592) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [62c37af17b](https://linux-hardware.org/?probe=62c37af17b) | Mar 03, 2023 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [756ac6782b](https://linux-hardware.org/?probe=756ac6782b) | Mar 03, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [a23a00a71e](https://linux-hardware.org/?probe=a23a00a71e) | Mar 02, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [2c6ad91981](https://linux-hardware.org/?probe=2c6ad91981) | Mar 02, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f942bae731](https://linux-hardware.org/?probe=f942bae731) | Mar 02, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [7deb9825c2](https://linux-hardware.org/?probe=7deb9825c2) | Mar 02, 2023 |
| ASRockRack    | X570D4U                     | Desktop     | [9c4b25d5dc](https://linux-hardware.org/?probe=9c4b25d5dc) | Mar 02, 2023 |
| Acer          | Swift SF314-54              | Notebook    | [62defb89e3](https://linux-hardware.org/?probe=62defb89e3) | Mar 02, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [4207bf1ee6](https://linux-hardware.org/?probe=4207bf1ee6) | Mar 02, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [ed4f0e394a](https://linux-hardware.org/?probe=ed4f0e394a) | Mar 02, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [5b94fc8fa8](https://linux-hardware.org/?probe=5b94fc8fa8) | Mar 02, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [85456379c1](https://linux-hardware.org/?probe=85456379c1) | Mar 02, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [a79b4ff73c](https://linux-hardware.org/?probe=a79b4ff73c) | Mar 02, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [6126e81a28](https://linux-hardware.org/?probe=6126e81a28) | Mar 01, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b6930e4615](https://linux-hardware.org/?probe=b6930e4615) | Mar 01, 2023 |
| System76      | Lemur Pro                   | Notebook    | [e7ed83aaf7](https://linux-hardware.org/?probe=e7ed83aaf7) | Mar 01, 2023 |
| HP            | 15                          | Notebook    | [97985ac192](https://linux-hardware.org/?probe=97985ac192) | Mar 01, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [2b007293f7](https://linux-hardware.org/?probe=2b007293f7) | Mar 01, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [9abfe7631c](https://linux-hardware.org/?probe=9abfe7631c) | Mar 01, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [46eecb2678](https://linux-hardware.org/?probe=46eecb2678) | Mar 01, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [bd415a086a](https://linux-hardware.org/?probe=bd415a086a) | Mar 01, 2023 |
| Dell          | Precision 3571              | Notebook    | [40348190de](https://linux-hardware.org/?probe=40348190de) | Mar 01, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [dcaa80ec62](https://linux-hardware.org/?probe=dcaa80ec62) | Mar 01, 2023 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | Notebook    | [571d426262](https://linux-hardware.org/?probe=571d426262) | Mar 01, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [78ee2e145b](https://linux-hardware.org/?probe=78ee2e145b) | Mar 01, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [bd4fd4080d](https://linux-hardware.org/?probe=bd4fd4080d) | Mar 01, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [90d8927f0a](https://linux-hardware.org/?probe=90d8927f0a) | Mar 01, 2023 |
| Gigabyte      | Z77X-UP4 TH                 | Desktop     | [b80cb49656](https://linux-hardware.org/?probe=b80cb49656) | Mar 01, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [0e0b3360ba](https://linux-hardware.org/?probe=0e0b3360ba) | Feb 28, 2023 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | Notebook    | [5aad25779a](https://linux-hardware.org/?probe=5aad25779a) | Feb 28, 2023 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [7f53a53eba](https://linux-hardware.org/?probe=7f53a53eba) | Feb 28, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [6c511739eb](https://linux-hardware.org/?probe=6c511739eb) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HN001RUS    | Notebook    | [ff84200b75](https://linux-hardware.org/?probe=ff84200b75) | Feb 28, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [88745e1f03](https://linux-hardware.org/?probe=88745e1f03) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [357c1abb1d](https://linux-hardware.org/?probe=357c1abb1d) | Feb 27, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [13edc00539](https://linux-hardware.org/?probe=13edc00539) | Feb 27, 2023 |
| AZW           | SER                         | Mini pc     | [f5b64e8716](https://linux-hardware.org/?probe=f5b64e8716) | Feb 27, 2023 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [425567e8f3](https://linux-hardware.org/?probe=425567e8f3) | Feb 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | Notebook    | [bd62e34a09](https://linux-hardware.org/?probe=bd62e34a09) | Feb 27, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | Notebook    | [82a40f1881](https://linux-hardware.org/?probe=82a40f1881) | Feb 27, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [97e3001416](https://linux-hardware.org/?probe=97e3001416) | Feb 26, 2023 |
| Dell          | 03KWTV A02                  | Desktop     | [8b6eae9fd5](https://linux-hardware.org/?probe=8b6eae9fd5) | Feb 26, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [a3b8430bad](https://linux-hardware.org/?probe=a3b8430bad) | Feb 26, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [fe1c90a3aa](https://linux-hardware.org/?probe=fe1c90a3aa) | Feb 26, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [f081452f55](https://linux-hardware.org/?probe=f081452f55) | Feb 26, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [2a8830034a](https://linux-hardware.org/?probe=2a8830034a) | Feb 26, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [1c93095718](https://linux-hardware.org/?probe=1c93095718) | Feb 26, 2023 |
| Sony          | VPCZ12V9R                   | Notebook    | [3014067c24](https://linux-hardware.org/?probe=3014067c24) | Feb 26, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [f991f0e9df](https://linux-hardware.org/?probe=f991f0e9df) | Feb 26, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [87647b8c76](https://linux-hardware.org/?probe=87647b8c76) | Feb 26, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [42fe607d11](https://linux-hardware.org/?probe=42fe607d11) | Feb 25, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [1550bec17e](https://linux-hardware.org/?probe=1550bec17e) | Feb 25, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [aa535b0731](https://linux-hardware.org/?probe=aa535b0731) | Feb 25, 2023 |
| Dell          | G7 7588                     | Notebook    | [82f1398a69](https://linux-hardware.org/?probe=82f1398a69) | Feb 25, 2023 |
| Alienware     | 15 R3                       | Notebook    | [72543030d5](https://linux-hardware.org/?probe=72543030d5) | Feb 25, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | Notebook    | [42b9d60137](https://linux-hardware.org/?probe=42b9d60137) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b5f840e593](https://linux-hardware.org/?probe=b5f840e593) | Feb 25, 2023 |
| System76      | Galago Pro                  | Notebook    | [3e4391562b](https://linux-hardware.org/?probe=3e4391562b) | Feb 25, 2023 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [0a63352761](https://linux-hardware.org/?probe=0a63352761) | Feb 25, 2023 |
| MSI           | PRO Z790-P WIFI DDR4        | Desktop     | [59b7e1da6d](https://linux-hardware.org/?probe=59b7e1da6d) | Feb 25, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [96e6c2c201](https://linux-hardware.org/?probe=96e6c2c201) | Feb 25, 2023 |
| Dell          | Latitude 3310               | Notebook    | [d989647d9d](https://linux-hardware.org/?probe=d989647d9d) | Feb 25, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [517a6211c9](https://linux-hardware.org/?probe=517a6211c9) | Feb 24, 2023 |
| ZOTAC         | MEK1                        | Desktop     | [a61a52d794](https://linux-hardware.org/?probe=a61a52d794) | Feb 24, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [f7c4b009f1](https://linux-hardware.org/?probe=f7c4b009f1) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [297c37ec04](https://linux-hardware.org/?probe=297c37ec04) | Feb 24, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [2f561a23c3](https://linux-hardware.org/?probe=2f561a23c3) | Feb 24, 2023 |
| HP            | 8433 11                     | Desktop     | [881b062090](https://linux-hardware.org/?probe=881b062090) | Feb 24, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [59d0e692ef](https://linux-hardware.org/?probe=59d0e692ef) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [041c57ebe6](https://linux-hardware.org/?probe=041c57ebe6) | Feb 24, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f2a29f6d2e](https://linux-hardware.org/?probe=f2a29f6d2e) | Feb 24, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2913081292](https://linux-hardware.org/?probe=2913081292) | Feb 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c591acd5d6](https://linux-hardware.org/?probe=c591acd5d6) | Feb 24, 2023 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [10ffde0986](https://linux-hardware.org/?probe=10ffde0986) | Feb 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [27a3c3c4c1](https://linux-hardware.org/?probe=27a3c3c4c1) | Feb 24, 2023 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [7ad94e1be6](https://linux-hardware.org/?probe=7ad94e1be6) | Feb 24, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [7cf47f3118](https://linux-hardware.org/?probe=7cf47f3118) | Feb 23, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [00591dc764](https://linux-hardware.org/?probe=00591dc764) | Feb 23, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | Notebook    | [bb0d8e868d](https://linux-hardware.org/?probe=bb0d8e868d) | Feb 23, 2023 |
| Toshiba       | Satellite C855-1T5          | Notebook    | [8a96579c89](https://linux-hardware.org/?probe=8a96579c89) | Feb 23, 2023 |
| System76      | Gazelle                     | Notebook    | [609f452af9](https://linux-hardware.org/?probe=609f452af9) | Feb 23, 2023 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | Notebook    | [33a4731a5e](https://linux-hardware.org/?probe=33a4731a5e) | Feb 23, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [8d8af65e26](https://linux-hardware.org/?probe=8d8af65e26) | Feb 23, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [f8f5ea8885](https://linux-hardware.org/?probe=f8f5ea8885) | Feb 23, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [205f7c6f50](https://linux-hardware.org/?probe=205f7c6f50) | Feb 23, 2023 |
| Dell          | Latitude E7240              | Notebook    | [7f8278ff44](https://linux-hardware.org/?probe=7f8278ff44) | Feb 23, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [34016a67d9](https://linux-hardware.org/?probe=34016a67d9) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [312937f0d0](https://linux-hardware.org/?probe=312937f0d0) | Feb 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [d032f0a547](https://linux-hardware.org/?probe=d032f0a547) | Feb 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ec6ab709e5](https://linux-hardware.org/?probe=ec6ab709e5) | Feb 22, 2023 |
| Lenovo        | 102F SBB0J05441 WIN 3305... | Desktop     | [ea890b85f3](https://linux-hardware.org/?probe=ea890b85f3) | Feb 22, 2023 |
| Gigabyte      | H81M-HD3                    | Desktop     | [d19e079879](https://linux-hardware.org/?probe=d19e079879) | Feb 22, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | Notebook    | [6ab727e8c0](https://linux-hardware.org/?probe=6ab727e8c0) | Feb 22, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [c4eab564b3](https://linux-hardware.org/?probe=c4eab564b3) | Feb 22, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [af2d2bd596](https://linux-hardware.org/?probe=af2d2bd596) | Feb 21, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [41b4e0957f](https://linux-hardware.org/?probe=41b4e0957f) | Feb 21, 2023 |
| ASRock        | B550 Extreme4               | Desktop     | [db2686086b](https://linux-hardware.org/?probe=db2686086b) | Feb 21, 2023 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [265018acd3](https://linux-hardware.org/?probe=265018acd3) | Feb 21, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [a5cff07fd8](https://linux-hardware.org/?probe=a5cff07fd8) | Feb 21, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [8c97a04c10](https://linux-hardware.org/?probe=8c97a04c10) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [022527aa4c](https://linux-hardware.org/?probe=022527aa4c) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [3b1afb00a2](https://linux-hardware.org/?probe=3b1afb00a2) | Feb 21, 2023 |
| Dell          | G15 5525                    | Notebook    | [63bd2ac7b9](https://linux-hardware.org/?probe=63bd2ac7b9) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [7dd9134373](https://linux-hardware.org/?probe=7dd9134373) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [fafea002be](https://linux-hardware.org/?probe=fafea002be) | Feb 21, 2023 |
| ASUSTek       | B75M-A                      | Desktop     | [c0c41ca089](https://linux-hardware.org/?probe=c0c41ca089) | Feb 21, 2023 |
| Alienware     | 0NWN7M A00                  | Desktop     | [eef5c2f68f](https://linux-hardware.org/?probe=eef5c2f68f) | Feb 21, 2023 |
| ASUSTek       | B75M-A                      | Desktop     | [2ea45a0d80](https://linux-hardware.org/?probe=2ea45a0d80) | Feb 21, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [e9f5a9d293](https://linux-hardware.org/?probe=e9f5a9d293) | Feb 21, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [5fd759f0ba](https://linux-hardware.org/?probe=5fd759f0ba) | Feb 21, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [edbf6ce468](https://linux-hardware.org/?probe=edbf6ce468) | Feb 20, 2023 |
| Dell          | Precision M4800             | Notebook    | [b8e31b63ce](https://linux-hardware.org/?probe=b8e31b63ce) | Feb 20, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [1862dee971](https://linux-hardware.org/?probe=1862dee971) | Feb 20, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [cc8628ae2c](https://linux-hardware.org/?probe=cc8628ae2c) | Feb 20, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0bc03f3b39](https://linux-hardware.org/?probe=0bc03f3b39) | Feb 20, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [b335ec1cc3](https://linux-hardware.org/?probe=b335ec1cc3) | Feb 20, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [b5e8826f8c](https://linux-hardware.org/?probe=b5e8826f8c) | Feb 20, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [1d62ae4e43](https://linux-hardware.org/?probe=1d62ae4e43) | Feb 20, 2023 |
| Intel         | NUC8i7HNB J68197-502        | Mini pc     | [2f702c3f2f](https://linux-hardware.org/?probe=2f702c3f2f) | Feb 19, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [297b06716d](https://linux-hardware.org/?probe=297b06716d) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [d4fdbbf1ba](https://linux-hardware.org/?probe=d4fdbbf1ba) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [a11d164d69](https://linux-hardware.org/?probe=a11d164d69) | Feb 19, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [2011c2060b](https://linux-hardware.org/?probe=2011c2060b) | Feb 19, 2023 |
| ASRock        | H87 Performance             | Desktop     | [a28df01cad](https://linux-hardware.org/?probe=a28df01cad) | Feb 19, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [9805ab5764](https://linux-hardware.org/?probe=9805ab5764) | Feb 19, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [8df8fe9ae8](https://linux-hardware.org/?probe=8df8fe9ae8) | Feb 19, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [813066eda5](https://linux-hardware.org/?probe=813066eda5) | Feb 19, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [b99541f6ad](https://linux-hardware.org/?probe=b99541f6ad) | Feb 19, 2023 |
| Dell          | 0NNNCT A01                  | Desktop     | [a301dac224](https://linux-hardware.org/?probe=a301dac224) | Feb 18, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [e87ff10942](https://linux-hardware.org/?probe=e87ff10942) | Feb 18, 2023 |
| HP            | 8437                        | Desktop     | [f8f0f71bf5](https://linux-hardware.org/?probe=f8f0f71bf5) | Feb 18, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [cc0e711862](https://linux-hardware.org/?probe=cc0e711862) | Feb 18, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [fc39dde214](https://linux-hardware.org/?probe=fc39dde214) | Feb 18, 2023 |
| Dell          | Latitude E7240              | Notebook    | [461873da2d](https://linux-hardware.org/?probe=461873da2d) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [5cc4ff8271](https://linux-hardware.org/?probe=5cc4ff8271) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [75f9e575b3](https://linux-hardware.org/?probe=75f9e575b3) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [f120e182a1](https://linux-hardware.org/?probe=f120e182a1) | Feb 17, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a56a788adf](https://linux-hardware.org/?probe=a56a788adf) | Feb 17, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [7ef47e7131](https://linux-hardware.org/?probe=7ef47e7131) | Feb 17, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [b16ea0055d](https://linux-hardware.org/?probe=b16ea0055d) | Feb 17, 2023 |
| Dell          | Latitude E4200              | Notebook    | [18868db8a1](https://linux-hardware.org/?probe=18868db8a1) | Feb 17, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [4101f152f5](https://linux-hardware.org/?probe=4101f152f5) | Feb 17, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [755006e226](https://linux-hardware.org/?probe=755006e226) | Feb 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [91c566ccc9](https://linux-hardware.org/?probe=91c566ccc9) | Feb 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e67f600749](https://linux-hardware.org/?probe=e67f600749) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | Notebook    | [2b0904349a](https://linux-hardware.org/?probe=2b0904349a) | Feb 16, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [64c385ee36](https://linux-hardware.org/?probe=64c385ee36) | Feb 16, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3206e7be82](https://linux-hardware.org/?probe=3206e7be82) | Feb 16, 2023 |
| OriginPC      | Voyager a1600               | Notebook    | [9608c5afd5](https://linux-hardware.org/?probe=9608c5afd5) | Feb 16, 2023 |
| Google        | Blorb                       | Notebook    | [286353731c](https://linux-hardware.org/?probe=286353731c) | Feb 16, 2023 |
| Lenovo        | 3136 SDK0K17763 WIN 1801... | Mini pc     | [01d39bc0ca](https://linux-hardware.org/?probe=01d39bc0ca) | Feb 16, 2023 |
| Lenovo        | ThinkPad T530 2392AQU       | Notebook    | [1b89c43b58](https://linux-hardware.org/?probe=1b89c43b58) | Feb 16, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [684445aeab](https://linux-hardware.org/?probe=684445aeab) | Feb 16, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [5a6d751e4b](https://linux-hardware.org/?probe=5a6d751e4b) | Feb 15, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [c82882e708](https://linux-hardware.org/?probe=c82882e708) | Feb 15, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [ed0641ce38](https://linux-hardware.org/?probe=ed0641ce38) | Feb 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [74a61dff13](https://linux-hardware.org/?probe=74a61dff13) | Feb 15, 2023 |
| Intel         | X99 V1.x                    | Desktop     | [31da77bea8](https://linux-hardware.org/?probe=31da77bea8) | Feb 15, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [c803a7f9e8](https://linux-hardware.org/?probe=c803a7f9e8) | Feb 15, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [3a660768c0](https://linux-hardware.org/?probe=3a660768c0) | Feb 15, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bdb6e585b0](https://linux-hardware.org/?probe=bdb6e585b0) | Feb 15, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [011e8929fa](https://linux-hardware.org/?probe=011e8929fa) | Feb 15, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [9dfc369401](https://linux-hardware.org/?probe=9dfc369401) | Feb 15, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [1161e39e43](https://linux-hardware.org/?probe=1161e39e43) | Feb 15, 2023 |
| Lenovo        | ThinkPad T450s 20BWS14G0... | Notebook    | [5c4a26ada0](https://linux-hardware.org/?probe=5c4a26ada0) | Feb 14, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [c008b1943f](https://linux-hardware.org/?probe=c008b1943f) | Feb 14, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [2ca590a85e](https://linux-hardware.org/?probe=2ca590a85e) | Feb 14, 2023 |
| Dell          | Precision M3800             | Notebook    | [98b54858cb](https://linux-hardware.org/?probe=98b54858cb) | Feb 14, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [1028ef9686](https://linux-hardware.org/?probe=1028ef9686) | Feb 14, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [27c2ee6ee0](https://linux-hardware.org/?probe=27c2ee6ee0) | Feb 14, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [826959e69e](https://linux-hardware.org/?probe=826959e69e) | Feb 13, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [abeebd4312](https://linux-hardware.org/?probe=abeebd4312) | Feb 13, 2023 |
| Sony          | VPCEG27FM                   | Notebook    | [748a67669f](https://linux-hardware.org/?probe=748a67669f) | Feb 13, 2023 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | Notebook    | [a6af7624cd](https://linux-hardware.org/?probe=a6af7624cd) | Feb 13, 2023 |
| Samsung       | 730U3E/740U3E               | Notebook    | [91ac69dfa1](https://linux-hardware.org/?probe=91ac69dfa1) | Feb 13, 2023 |
| Lenovo        | ThinkPad T410 2522G76       | Notebook    | [b15d4051cd](https://linux-hardware.org/?probe=b15d4051cd) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [d38212ee96](https://linux-hardware.org/?probe=d38212ee96) | Feb 13, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [2314b98760](https://linux-hardware.org/?probe=2314b98760) | Feb 12, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [139b92595a](https://linux-hardware.org/?probe=139b92595a) | Feb 12, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [d94084bbee](https://linux-hardware.org/?probe=d94084bbee) | Feb 12, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [2a6f501cb1](https://linux-hardware.org/?probe=2a6f501cb1) | Feb 12, 2023 |
| Haier         | GG1500A                     | Notebook    | [4c4598157f](https://linux-hardware.org/?probe=4c4598157f) | Feb 12, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [89ba42b53e](https://linux-hardware.org/?probe=89ba42b53e) | Feb 12, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [687ecdce15](https://linux-hardware.org/?probe=687ecdce15) | Feb 12, 2023 |
| Dell          | Latitude XT2                | Notebook    | [9b98bf4722](https://linux-hardware.org/?probe=9b98bf4722) | Feb 12, 2023 |
| Dell          | Precision M4700             | Notebook    | [1a44cb5ef9](https://linux-hardware.org/?probe=1a44cb5ef9) | Feb 11, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [fb407bfc13](https://linux-hardware.org/?probe=fb407bfc13) | Feb 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [2c1562b21f](https://linux-hardware.org/?probe=2c1562b21f) | Feb 11, 2023 |
| Lenovo        | ThinkPad T470s 20HFCT01W... | Notebook    | [322a9d340e](https://linux-hardware.org/?probe=322a9d340e) | Feb 11, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [1315dbeb6c](https://linux-hardware.org/?probe=1315dbeb6c) | Feb 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [2d776f8810](https://linux-hardware.org/?probe=2d776f8810) | Feb 11, 2023 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [b82ab8816d](https://linux-hardware.org/?probe=b82ab8816d) | Feb 11, 2023 |
| HP            | 18E4                        | Desktop     | [55972b87dd](https://linux-hardware.org/?probe=55972b87dd) | Feb 11, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [ab07f075d8](https://linux-hardware.org/?probe=ab07f075d8) | Feb 11, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [2f1c5b90a8](https://linux-hardware.org/?probe=2f1c5b90a8) | Feb 11, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [24cb179c5a](https://linux-hardware.org/?probe=24cb179c5a) | Feb 11, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [0b14ee6551](https://linux-hardware.org/?probe=0b14ee6551) | Feb 11, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502FBA... | Convertible | [dd34aed5d9](https://linux-hardware.org/?probe=dd34aed5d9) | Feb 11, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [c17ac89917](https://linux-hardware.org/?probe=c17ac89917) | Feb 11, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [181c0e03e2](https://linux-hardware.org/?probe=181c0e03e2) | Feb 10, 2023 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [9cbcfdd748](https://linux-hardware.org/?probe=9cbcfdd748) | Feb 10, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [cb03f9e72e](https://linux-hardware.org/?probe=cb03f9e72e) | Feb 10, 2023 |
| Dell          | 0Y7WYT A00                  | Desktop     | [e4369afe1e](https://linux-hardware.org/?probe=e4369afe1e) | Feb 10, 2023 |
| ASUSTek       | A55BM-PLUS                  | Desktop     | [7c9763c23f](https://linux-hardware.org/?probe=7c9763c23f) | Feb 10, 2023 |
| Dell          | G15 5520                    | Notebook    | [121b06f3cc](https://linux-hardware.org/?probe=121b06f3cc) | Feb 10, 2023 |
| Samsung       | DeskTop System              | Desktop     | [2437c4afda](https://linux-hardware.org/?probe=2437c4afda) | Feb 10, 2023 |
| Dell          | 0CR1TT A00                  | All in one  | [be588e52b7](https://linux-hardware.org/?probe=be588e52b7) | Feb 09, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [d0cc5f80fc](https://linux-hardware.org/?probe=d0cc5f80fc) | Feb 09, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [39dbdb0fa9](https://linux-hardware.org/?probe=39dbdb0fa9) | Feb 09, 2023 |
| Lenovo        | ThinkPad T450 20BUA0PNUK    | Notebook    | [8837c33007](https://linux-hardware.org/?probe=8837c33007) | Feb 09, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [390c8dd03a](https://linux-hardware.org/?probe=390c8dd03a) | Feb 09, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | Notebook    | [74dd2176ff](https://linux-hardware.org/?probe=74dd2176ff) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [17bf959fd0](https://linux-hardware.org/?probe=17bf959fd0) | Feb 09, 2023 |
| Acer          | Aspire M3970                | Desktop     | [718cc13462](https://linux-hardware.org/?probe=718cc13462) | Feb 09, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [93afe9ddeb](https://linux-hardware.org/?probe=93afe9ddeb) | Feb 09, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [a025641dfc](https://linux-hardware.org/?probe=a025641dfc) | Feb 09, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [edc6b0a3af](https://linux-hardware.org/?probe=edc6b0a3af) | Feb 09, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [db7e89340f](https://linux-hardware.org/?probe=db7e89340f) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [16af8175a4](https://linux-hardware.org/?probe=16af8175a4) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX463FA_UX463FA     | Convertible | [e43aebc69d](https://linux-hardware.org/?probe=e43aebc69d) | Feb 08, 2023 |
| System76      | Lemur Pro                   | Notebook    | [94cf78a9d9](https://linux-hardware.org/?probe=94cf78a9d9) | Feb 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [43b52ad56f](https://linux-hardware.org/?probe=43b52ad56f) | Feb 08, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [1c07b901bb](https://linux-hardware.org/?probe=1c07b901bb) | Feb 08, 2023 |
| HP            | 2129                        | Desktop     | [80920d0d75](https://linux-hardware.org/?probe=80920d0d75) | Feb 08, 2023 |
| Dell          | G15 5520                    | Notebook    | [7f4d36cea1](https://linux-hardware.org/?probe=7f4d36cea1) | Feb 08, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [d8dcaddb54](https://linux-hardware.org/?probe=d8dcaddb54) | Feb 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [275ce1a7fc](https://linux-hardware.org/?probe=275ce1a7fc) | Feb 08, 2023 |
| ASRock        | B660 Pro-C/ax               | Desktop     | [31e10f0e68](https://linux-hardware.org/?probe=31e10f0e68) | Feb 07, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [5554154df2](https://linux-hardware.org/?probe=5554154df2) | Feb 07, 2023 |
| Dell          | System XPS L702X            | Notebook    | [cdbc3578d0](https://linux-hardware.org/?probe=cdbc3578d0) | Feb 07, 2023 |
| Alienware     | m15 R7                      | Notebook    | [254ab40fcf](https://linux-hardware.org/?probe=254ab40fcf) | Feb 07, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [8588a36683](https://linux-hardware.org/?probe=8588a36683) | Feb 07, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [81ece9483e](https://linux-hardware.org/?probe=81ece9483e) | Feb 07, 2023 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [fe95bfe3d3](https://linux-hardware.org/?probe=fe95bfe3d3) | Feb 07, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [e67a1c86b7](https://linux-hardware.org/?probe=e67a1c86b7) | Feb 07, 2023 |
| Gigabyte      | Z170X-UD5-CF                | Desktop     | [03a392d41f](https://linux-hardware.org/?probe=03a392d41f) | Feb 07, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aef988ae85](https://linux-hardware.org/?probe=aef988ae85) | Feb 07, 2023 |
| Dell          | 02GDWG A00                  | Desktop     | [c0660c15fb](https://linux-hardware.org/?probe=c0660c15fb) | Feb 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [f6c24b1ea8](https://linux-hardware.org/?probe=f6c24b1ea8) | Feb 07, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [209a38d937](https://linux-hardware.org/?probe=209a38d937) | Feb 07, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI      | Desktop     | [25fbfe1d66](https://linux-hardware.org/?probe=25fbfe1d66) | Feb 07, 2023 |
| System76      | Thelio thelio-r2            | Desktop     | [4cdf7d2895](https://linux-hardware.org/?probe=4cdf7d2895) | Feb 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [50af8c9fe6](https://linux-hardware.org/?probe=50af8c9fe6) | Feb 06, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [96d7a1938a](https://linux-hardware.org/?probe=96d7a1938a) | Feb 06, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [42dba6bdb3](https://linux-hardware.org/?probe=42dba6bdb3) | Feb 06, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [a9bfc9669d](https://linux-hardware.org/?probe=a9bfc9669d) | Feb 06, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [28aad1fae5](https://linux-hardware.org/?probe=28aad1fae5) | Feb 06, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [12d5592082](https://linux-hardware.org/?probe=12d5592082) | Feb 06, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [c0c9951f8d](https://linux-hardware.org/?probe=c0c9951f8d) | Feb 05, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [2e5b18f7c5](https://linux-hardware.org/?probe=2e5b18f7c5) | Feb 05, 2023 |
| Dell          | Latitude 7380               | Notebook    | [7b9d4ef8b4](https://linux-hardware.org/?probe=7b9d4ef8b4) | Feb 05, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [ea8a0e0617](https://linux-hardware.org/?probe=ea8a0e0617) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | Notebook    | [5c2bd1284d](https://linux-hardware.org/?probe=5c2bd1284d) | Feb 05, 2023 |
| Alienware     | 17 R5                       | Notebook    | [7f5f8bdb1f](https://linux-hardware.org/?probe=7f5f8bdb1f) | Feb 05, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [6f09d6cd6c](https://linux-hardware.org/?probe=6f09d6cd6c) | Feb 05, 2023 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [9c92a1772d](https://linux-hardware.org/?probe=9c92a1772d) | Feb 05, 2023 |
| HP            | 8054                        | Desktop     | [c709653825](https://linux-hardware.org/?probe=c709653825) | Feb 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d95f28d447](https://linux-hardware.org/?probe=d95f28d447) | Feb 05, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [a705eb3101](https://linux-hardware.org/?probe=a705eb3101) | Feb 05, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [7a80b2d6d7](https://linux-hardware.org/?probe=7a80b2d6d7) | Feb 05, 2023 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | Notebook    | [e5e8537cef](https://linux-hardware.org/?probe=e5e8537cef) | Feb 05, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [0cb9ba3cf9](https://linux-hardware.org/?probe=0cb9ba3cf9) | Feb 05, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [13948b75ae](https://linux-hardware.org/?probe=13948b75ae) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | Notebook    | [b5ac9ebd7c](https://linux-hardware.org/?probe=b5ac9ebd7c) | Feb 05, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [403785d1ec](https://linux-hardware.org/?probe=403785d1ec) | Feb 05, 2023 |
| HP            | Notebook                    | Notebook    | [0ad701667d](https://linux-hardware.org/?probe=0ad701667d) | Feb 05, 2023 |
| HP            | Notebook                    | Notebook    | [37f601798c](https://linux-hardware.org/?probe=37f601798c) | Feb 05, 2023 |
| Dell          | G15 5515                    | Notebook    | [7418ca82c1](https://linux-hardware.org/?probe=7418ca82c1) | Feb 04, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [fd2b67e6ab](https://linux-hardware.org/?probe=fd2b67e6ab) | Feb 04, 2023 |
| Dell          | Latitude 3520               | Notebook    | [ce594f431c](https://linux-hardware.org/?probe=ce594f431c) | Feb 04, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [db5c0dd7b2](https://linux-hardware.org/?probe=db5c0dd7b2) | Feb 04, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [85ce5298e5](https://linux-hardware.org/?probe=85ce5298e5) | Feb 04, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [149465f225](https://linux-hardware.org/?probe=149465f225) | Feb 04, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [c66fb39891](https://linux-hardware.org/?probe=c66fb39891) | Feb 04, 2023 |
| Gigabyte      | Z170X-UD5-CF                | Desktop     | [cd9d867630](https://linux-hardware.org/?probe=cd9d867630) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [448d3800ac](https://linux-hardware.org/?probe=448d3800ac) | Feb 04, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0f24e9c32c](https://linux-hardware.org/?probe=0f24e9c32c) | Feb 04, 2023 |
| Toshiba       | Satellite C855-233          | Notebook    | [8fc7835588](https://linux-hardware.org/?probe=8fc7835588) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN0017US     | Notebook    | [43c5ab14ec](https://linux-hardware.org/?probe=43c5ab14ec) | Feb 03, 2023 |
| Dell          | Latitude E7240              | Notebook    | [da54499919](https://linux-hardware.org/?probe=da54499919) | Feb 03, 2023 |
| Haier         | GG1500A                     | Notebook    | [b54ce000d3](https://linux-hardware.org/?probe=b54ce000d3) | Feb 03, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [084eee2317](https://linux-hardware.org/?probe=084eee2317) | Feb 03, 2023 |
| Star Labs     | StarBook                    | Notebook    | [98ad1bcab4](https://linux-hardware.org/?probe=98ad1bcab4) | Feb 03, 2023 |
| Star Labs     | StarBook                    | Notebook    | [5fe174bdd1](https://linux-hardware.org/?probe=5fe174bdd1) | Feb 03, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [704c6e370c](https://linux-hardware.org/?probe=704c6e370c) | Feb 03, 2023 |
| AZW           | SER                         | Mini pc     | [198a217d13](https://linux-hardware.org/?probe=198a217d13) | Feb 03, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [8a1c423c67](https://linux-hardware.org/?probe=8a1c423c67) | Feb 03, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c441c159c1](https://linux-hardware.org/?probe=c441c159c1) | Feb 03, 2023 |
| HP            | 834F                        | Desktop     | [9a4a1839d3](https://linux-hardware.org/?probe=9a4a1839d3) | Feb 02, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [8944f22b68](https://linux-hardware.org/?probe=8944f22b68) | Feb 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0b0eaa5c48](https://linux-hardware.org/?probe=0b0eaa5c48) | Feb 02, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [96b48bebd2](https://linux-hardware.org/?probe=96b48bebd2) | Feb 02, 2023 |
| Dell          | Inspiron 3584               | Notebook    | [4bfcbe7c13](https://linux-hardware.org/?probe=4bfcbe7c13) | Feb 02, 2023 |
| HP            | 872E                        | Mini pc     | [c73d160043](https://linux-hardware.org/?probe=c73d160043) | Feb 02, 2023 |
| Dell          | Precision 3571              | Notebook    | [8ee8f6f768](https://linux-hardware.org/?probe=8ee8f6f768) | Feb 02, 2023 |
| Dell          | Precision 3571              | Notebook    | [9453f26568](https://linux-hardware.org/?probe=9453f26568) | Feb 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2fe2d2d279](https://linux-hardware.org/?probe=2fe2d2d279) | Feb 02, 2023 |
| Dell          | Latitude 7320 Detachable    | Tablet      | [7560429d05](https://linux-hardware.org/?probe=7560429d05) | Feb 02, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [6d4ee8a3c6](https://linux-hardware.org/?probe=6d4ee8a3c6) | Feb 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ffabf45521](https://linux-hardware.org/?probe=ffabf45521) | Feb 02, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [0811d3d2f0](https://linux-hardware.org/?probe=0811d3d2f0) | Feb 02, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a899b18189](https://linux-hardware.org/?probe=a899b18189) | Feb 02, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [8db619716a](https://linux-hardware.org/?probe=8db619716a) | Feb 02, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [7019bd88e0](https://linux-hardware.org/?probe=7019bd88e0) | Feb 01, 2023 |
| HP            | Pavilion 15                 | Notebook    | [946fec8f7d](https://linux-hardware.org/?probe=946fec8f7d) | Feb 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [6294616fc6](https://linux-hardware.org/?probe=6294616fc6) | Feb 01, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [b13dd2d455](https://linux-hardware.org/?probe=b13dd2d455) | Feb 01, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [6ed194a014](https://linux-hardware.org/?probe=6ed194a014) | Feb 01, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [d897ec0114](https://linux-hardware.org/?probe=d897ec0114) | Feb 01, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [c4869ecf2c](https://linux-hardware.org/?probe=c4869ecf2c) | Feb 01, 2023 |
| Acer          | Predator PH517-61           | Notebook    | [b16ddc31d8](https://linux-hardware.org/?probe=b16ddc31d8) | Feb 01, 2023 |
| Dell          | Latitude E7240              | Notebook    | [fe655eca77](https://linux-hardware.org/?probe=fe655eca77) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [3803fd2405](https://linux-hardware.org/?probe=3803fd2405) | Jan 31, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [db8bdbd72b](https://linux-hardware.org/?probe=db8bdbd72b) | Jan 31, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [a6b124fd34](https://linux-hardware.org/?probe=a6b124fd34) | Jan 31, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [228ab40738](https://linux-hardware.org/?probe=228ab40738) | Jan 31, 2023 |
| HP            | Notebook                    | Notebook    | [82d58b21c4](https://linux-hardware.org/?probe=82d58b21c4) | Jan 31, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [506988f4ba](https://linux-hardware.org/?probe=506988f4ba) | Jan 31, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [7636aeaacc](https://linux-hardware.org/?probe=7636aeaacc) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [84278c514e](https://linux-hardware.org/?probe=84278c514e) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [e91278bf3b](https://linux-hardware.org/?probe=e91278bf3b) | Jan 31, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [230b38f8e6](https://linux-hardware.org/?probe=230b38f8e6) | Jan 31, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [82d317899e](https://linux-hardware.org/?probe=82d317899e) | Jan 31, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [6a0af9dbcb](https://linux-hardware.org/?probe=6a0af9dbcb) | Jan 31, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [33ae030343](https://linux-hardware.org/?probe=33ae030343) | Jan 31, 2023 |
| Intel         | NUC6i5SYB H81131-504        | Mini pc     | [d079e3930d](https://linux-hardware.org/?probe=d079e3930d) | Jan 31, 2023 |
| MSI           | PRO Z690-P DDR4             | Desktop     | [a434328de5](https://linux-hardware.org/?probe=a434328de5) | Jan 30, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [2474b4641c](https://linux-hardware.org/?probe=2474b4641c) | Jan 30, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [f012d6d71c](https://linux-hardware.org/?probe=f012d6d71c) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | Notebook    | [d4aec33c44](https://linux-hardware.org/?probe=d4aec33c44) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | Notebook    | [58e7588538](https://linux-hardware.org/?probe=58e7588538) | Jan 30, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [1228d6d0f7](https://linux-hardware.org/?probe=1228d6d0f7) | Jan 30, 2023 |
| Dell          | G15 5511                    | Notebook    | [36214ba4de](https://linux-hardware.org/?probe=36214ba4de) | Jan 30, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [a96d93846a](https://linux-hardware.org/?probe=a96d93846a) | Jan 30, 2023 |
| Dell          | Latitude E7240              | Notebook    | [a1f713f6e3](https://linux-hardware.org/?probe=a1f713f6e3) | Jan 30, 2023 |
| Avell High... | B11 MOB                     | Notebook    | [dd9d29ddc7](https://linux-hardware.org/?probe=dd9d29ddc7) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [3d555e69f7](https://linux-hardware.org/?probe=3d555e69f7) | Jan 30, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [42405a6a0c](https://linux-hardware.org/?probe=42405a6a0c) | Jan 30, 2023 |
| HP            | Pavilion dv6                | Notebook    | [0966ae419c](https://linux-hardware.org/?probe=0966ae419c) | Jan 30, 2023 |
| Intel         | H61                         | Desktop     | [87a72c61f2](https://linux-hardware.org/?probe=87a72c61f2) | Jan 29, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [b70d834fe5](https://linux-hardware.org/?probe=b70d834fe5) | Jan 29, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [b07e189d3c](https://linux-hardware.org/?probe=b07e189d3c) | Jan 29, 2023 |
| Dell          | G15 5515                    | Notebook    | [1be125c3cd](https://linux-hardware.org/?probe=1be125c3cd) | Jan 29, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6b71ec1a01](https://linux-hardware.org/?probe=6b71ec1a01) | Jan 28, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [a9367f87d4](https://linux-hardware.org/?probe=a9367f87d4) | Jan 28, 2023 |
| ASUSTek       | GA35DX                      | Desktop     | [697b0d8654](https://linux-hardware.org/?probe=697b0d8654) | Jan 28, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [ff3381fe1a](https://linux-hardware.org/?probe=ff3381fe1a) | Jan 28, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [c74b6b90f0](https://linux-hardware.org/?probe=c74b6b90f0) | Jan 28, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [c6770f3828](https://linux-hardware.org/?probe=c6770f3828) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [ec9bed5b5d](https://linux-hardware.org/?probe=ec9bed5b5d) | Jan 28, 2023 |
| ASUSTek       | ET2321I                     | Notebook    | [dbb162975e](https://linux-hardware.org/?probe=dbb162975e) | Jan 28, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [549b690251](https://linux-hardware.org/?probe=549b690251) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [e225ce26a1](https://linux-hardware.org/?probe=e225ce26a1) | Jan 28, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [cbbd1d3e3e](https://linux-hardware.org/?probe=cbbd1d3e3e) | Jan 28, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [684b829dbb](https://linux-hardware.org/?probe=684b829dbb) | Jan 28, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [995da6b474](https://linux-hardware.org/?probe=995da6b474) | Jan 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ce2955973a](https://linux-hardware.org/?probe=ce2955973a) | Jan 27, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [55d50f6d18](https://linux-hardware.org/?probe=55d50f6d18) | Jan 27, 2023 |
| System76      | Lemur Pro                   | Notebook    | [40c5731c48](https://linux-hardware.org/?probe=40c5731c48) | Jan 27, 2023 |
| HP            | 1495                        | Desktop     | [8c1f7b5fbd](https://linux-hardware.org/?probe=8c1f7b5fbd) | Jan 27, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [c2a36422b4](https://linux-hardware.org/?probe=c2a36422b4) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [df315d8050](https://linux-hardware.org/?probe=df315d8050) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [14a0252d88](https://linux-hardware.org/?probe=14a0252d88) | Jan 27, 2023 |
| Clevo         | W150HNM/W170HN              | Notebook    | [63709a14ca](https://linux-hardware.org/?probe=63709a14ca) | Jan 27, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [0b70a364b7](https://linux-hardware.org/?probe=0b70a364b7) | Jan 27, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [a42ba7ef9e](https://linux-hardware.org/?probe=a42ba7ef9e) | Jan 26, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [1f8bd6b38e](https://linux-hardware.org/?probe=1f8bd6b38e) | Jan 26, 2023 |
| Dell          | Latitude E7240              | Notebook    | [d88cdedff3](https://linux-hardware.org/?probe=d88cdedff3) | Jan 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [df04ffbd50](https://linux-hardware.org/?probe=df04ffbd50) | Jan 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [b2ffc58bb1](https://linux-hardware.org/?probe=b2ffc58bb1) | Jan 26, 2023 |
| Dell          | G3 3590                     | Notebook    | [8a7e4e4db0](https://linux-hardware.org/?probe=8a7e4e4db0) | Jan 26, 2023 |
| System76      | Lemur Pro                   | Notebook    | [097cd4c9f8](https://linux-hardware.org/?probe=097cd4c9f8) | Jan 26, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2fe7cc7865](https://linux-hardware.org/?probe=2fe7cc7865) | Jan 25, 2023 |
| Gigabyte      | A5 K1                       | Notebook    | [e0771eb5f6](https://linux-hardware.org/?probe=e0771eb5f6) | Jan 25, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [e32b0f2c79](https://linux-hardware.org/?probe=e32b0f2c79) | Jan 25, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c7c957ccb3](https://linux-hardware.org/?probe=c7c957ccb3) | Jan 25, 2023 |
| HP            | ProBook 6550b               | Notebook    | [c7983e417c](https://linux-hardware.org/?probe=c7983e417c) | Jan 25, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [4629dc82aa](https://linux-hardware.org/?probe=4629dc82aa) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [bc56140257](https://linux-hardware.org/?probe=bc56140257) | Jan 25, 2023 |
| Gigabyte      | A5 K1                       | Notebook    | [d5e00555ca](https://linux-hardware.org/?probe=d5e00555ca) | Jan 25, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2M30... | Notebook    | [f201c986f0](https://linux-hardware.org/?probe=f201c986f0) | Jan 25, 2023 |
| Dell          | Inspiron 13-7353            | Notebook    | [5ebcba8c52](https://linux-hardware.org/?probe=5ebcba8c52) | Jan 25, 2023 |
| Dell          | Latitude E7240              | Notebook    | [2d488752b6](https://linux-hardware.org/?probe=2d488752b6) | Jan 25, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [935a295b28](https://linux-hardware.org/?probe=935a295b28) | Jan 25, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [9694a30eff](https://linux-hardware.org/?probe=9694a30eff) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [10f149abb7](https://linux-hardware.org/?probe=10f149abb7) | Jan 24, 2023 |
| MeLE          | Rev GMLR1                   | Mini pc     | [1f294d6a67](https://linux-hardware.org/?probe=1f294d6a67) | Jan 24, 2023 |
| Dell          | 02P9X9 A00                  | Server      | [be7339e967](https://linux-hardware.org/?probe=be7339e967) | Jan 24, 2023 |
| Acer          | Aspire M3970                | Desktop     | [c822a510e5](https://linux-hardware.org/?probe=c822a510e5) | Jan 24, 2023 |
| Dell          | Latitude E7240              | Notebook    | [9d44efa2f9](https://linux-hardware.org/?probe=9d44efa2f9) | Jan 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3221475cc8](https://linux-hardware.org/?probe=3221475cc8) | Jan 24, 2023 |
| Acer          | Swift SFA16-41              | Notebook    | [1c05334105](https://linux-hardware.org/?probe=1c05334105) | Jan 24, 2023 |
| LG Electro... | 17Z90Q-K.AAC7U1             | Notebook    | [73a0023203](https://linux-hardware.org/?probe=73a0023203) | Jan 24, 2023 |
| Google        | Link                        | Notebook    | [5c44e38153](https://linux-hardware.org/?probe=5c44e38153) | Jan 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [4f5be0720a](https://linux-hardware.org/?probe=4f5be0720a) | Jan 23, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [c87ce45f84](https://linux-hardware.org/?probe=c87ce45f84) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [f6e09cc9fb](https://linux-hardware.org/?probe=f6e09cc9fb) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [306e6ae925](https://linux-hardware.org/?probe=306e6ae925) | Jan 23, 2023 |
| ASUSTek       | Rampage II GENE             | Desktop     | [112b5304d9](https://linux-hardware.org/?probe=112b5304d9) | Jan 23, 2023 |
| MACHINIST     | X79 Z9-D7 V2.0              | Desktop     | [9d5d06d342](https://linux-hardware.org/?probe=9d5d06d342) | Jan 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [75acbba6b1](https://linux-hardware.org/?probe=75acbba6b1) | Jan 23, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [82b094a66b](https://linux-hardware.org/?probe=82b094a66b) | Jan 23, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bfb889f5d5](https://linux-hardware.org/?probe=bfb889f5d5) | Jan 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6597dd71bc](https://linux-hardware.org/?probe=6597dd71bc) | Jan 23, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [8f19cbfb31](https://linux-hardware.org/?probe=8f19cbfb31) | Jan 22, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [821e7b4330](https://linux-hardware.org/?probe=821e7b4330) | Jan 22, 2023 |
| Purism        | Librem 15 v3                | Notebook    | [fcb1d44df6](https://linux-hardware.org/?probe=fcb1d44df6) | Jan 22, 2023 |
| MSI           | H81M-E34                    | Desktop     | [c11041ba13](https://linux-hardware.org/?probe=c11041ba13) | Jan 22, 2023 |
| ASUSTek       | H61M-E                      | Desktop     | [eec3fddef5](https://linux-hardware.org/?probe=eec3fddef5) | Jan 22, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [758ea69493](https://linux-hardware.org/?probe=758ea69493) | Jan 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4f65820da4](https://linux-hardware.org/?probe=4f65820da4) | Jan 22, 2023 |
| Dell          | Latitude E5470              | Notebook    | [1a2810f035](https://linux-hardware.org/?probe=1a2810f035) | Jan 22, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [d1b63bbd2d](https://linux-hardware.org/?probe=d1b63bbd2d) | Jan 22, 2023 |
| HP            | Notebook                    | Notebook    | [57bf6826ef](https://linux-hardware.org/?probe=57bf6826ef) | Jan 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [01e83b7640](https://linux-hardware.org/?probe=01e83b7640) | Jan 22, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [0729d0a10f](https://linux-hardware.org/?probe=0729d0a10f) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [ebab459512](https://linux-hardware.org/?probe=ebab459512) | Jan 22, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [223ab1f016](https://linux-hardware.org/?probe=223ab1f016) | Jan 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [70b4ca8de7](https://linux-hardware.org/?probe=70b4ca8de7) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [9b3b21f5b7](https://linux-hardware.org/?probe=9b3b21f5b7) | Jan 21, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [22d9f43ef5](https://linux-hardware.org/?probe=22d9f43ef5) | Jan 21, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [1a27b660c2](https://linux-hardware.org/?probe=1a27b660c2) | Jan 21, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [6dd531590e](https://linux-hardware.org/?probe=6dd531590e) | Jan 21, 2023 |
| Razer x La... | TensorBook (late 2021)      | Notebook    | [9062d4274f](https://linux-hardware.org/?probe=9062d4274f) | Jan 21, 2023 |
| Dell          | Latitude 5300               | Notebook    | [e8c4218110](https://linux-hardware.org/?probe=e8c4218110) | Jan 21, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [bd601f83d3](https://linux-hardware.org/?probe=bd601f83d3) | Jan 21, 2023 |
| ASRock        | X99 Professional Gaming ... | Desktop     | [d203633f83](https://linux-hardware.org/?probe=d203633f83) | Jan 21, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [ce0ba337df](https://linux-hardware.org/?probe=ce0ba337df) | Jan 21, 2023 |
| ASRock        | X99 Professional Gaming ... | Desktop     | [e47d5b2419](https://linux-hardware.org/?probe=e47d5b2419) | Jan 21, 2023 |
| Lenovo        | ThinkPad T530 23943J8       | Notebook    | [1da6722b35](https://linux-hardware.org/?probe=1da6722b35) | Jan 21, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [011553878f](https://linux-hardware.org/?probe=011553878f) | Jan 21, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [b7b8f92df1](https://linux-hardware.org/?probe=b7b8f92df1) | Jan 21, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [9a17165647](https://linux-hardware.org/?probe=9a17165647) | Jan 20, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [e1003a85c9](https://linux-hardware.org/?probe=e1003a85c9) | Jan 20, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2ad3ad8258](https://linux-hardware.org/?probe=2ad3ad8258) | Jan 20, 2023 |
| ASUSTek       | X442URR                     | Notebook    | [6104ee1f65](https://linux-hardware.org/?probe=6104ee1f65) | Jan 20, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [a10fc5f5a9](https://linux-hardware.org/?probe=a10fc5f5a9) | Jan 20, 2023 |
| Dell          | Latitude E7240              | Notebook    | [a4e01b187f](https://linux-hardware.org/?probe=a4e01b187f) | Jan 20, 2023 |
| ASRock        | X99 Professional Gaming ... | Desktop     | [266b8bc492](https://linux-hardware.org/?probe=266b8bc492) | Jan 20, 2023 |
| Alienware     | 0N43JM A00                  | Desktop     | [06a6ec74c0](https://linux-hardware.org/?probe=06a6ec74c0) | Jan 20, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [0bf7ea6726](https://linux-hardware.org/?probe=0bf7ea6726) | Jan 20, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [c1169d55de](https://linux-hardware.org/?probe=c1169d55de) | Jan 19, 2023 |
| Lenovo        | 3767 WIN SDK0T76461 3422... | All in one  | [f9f38488a8](https://linux-hardware.org/?probe=f9f38488a8) | Jan 19, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2M30... | Notebook    | [641654df50](https://linux-hardware.org/?probe=641654df50) | Jan 19, 2023 |
| Dell          | Latitude E7240              | Notebook    | [475187029d](https://linux-hardware.org/?probe=475187029d) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [edc36777f0](https://linux-hardware.org/?probe=edc36777f0) | Jan 19, 2023 |
| ASRock        | X99 Professional Gaming ... | Desktop     | [0fbcb3df67](https://linux-hardware.org/?probe=0fbcb3df67) | Jan 19, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [cbad1c4df4](https://linux-hardware.org/?probe=cbad1c4df4) | Jan 19, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [b318baed4f](https://linux-hardware.org/?probe=b318baed4f) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [eddf4927eb](https://linux-hardware.org/?probe=eddf4927eb) | Jan 19, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [3ff2eaf5ed](https://linux-hardware.org/?probe=3ff2eaf5ed) | Jan 19, 2023 |
| Dell          | Inspiron 5491 2n1           | Convertible | [061608feaa](https://linux-hardware.org/?probe=061608feaa) | Jan 19, 2023 |
| Razer         | Blade                       | Notebook    | [b3f154ac11](https://linux-hardware.org/?probe=b3f154ac11) | Jan 19, 2023 |
| Dell          | G5 5590                     | Notebook    | [01888c3049](https://linux-hardware.org/?probe=01888c3049) | Jan 19, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [d13ca33fcf](https://linux-hardware.org/?probe=d13ca33fcf) | Jan 18, 2023 |
| Dell          | Latitude E6540              | Notebook    | [440b0eec1c](https://linux-hardware.org/?probe=440b0eec1c) | Jan 18, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [832ee11e43](https://linux-hardware.org/?probe=832ee11e43) | Jan 18, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [81d4385a14](https://linux-hardware.org/?probe=81d4385a14) | Jan 18, 2023 |
| Lenovo        | ThinkPad T560 20FH001QUS    | Notebook    | [933f67b6b5](https://linux-hardware.org/?probe=933f67b6b5) | Jan 18, 2023 |
| Dell          | Precision 7670              | Notebook    | [5c70243651](https://linux-hardware.org/?probe=5c70243651) | Jan 18, 2023 |
| Intel         | NUC12EDBi9 M27907-302       | Mini pc     | [b43c8a95b7](https://linux-hardware.org/?probe=b43c8a95b7) | Jan 18, 2023 |
| Lenovo        | ThinkPad T560 20FH001QUS    | Notebook    | [48a56bd8c2](https://linux-hardware.org/?probe=48a56bd8c2) | Jan 18, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [ac28c1fba4](https://linux-hardware.org/?probe=ac28c1fba4) | Jan 18, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [45e2d0fb2d](https://linux-hardware.org/?probe=45e2d0fb2d) | Jan 18, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [b5b4cde08e](https://linux-hardware.org/?probe=b5b4cde08e) | Jan 18, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [3ee772766c](https://linux-hardware.org/?probe=3ee772766c) | Jan 18, 2023 |
| Dell          | Latitude E5440              | Notebook    | [eb945eac4e](https://linux-hardware.org/?probe=eb945eac4e) | Jan 18, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [ebc45fdfd5](https://linux-hardware.org/?probe=ebc45fdfd5) | Jan 18, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [0eae2f92fa](https://linux-hardware.org/?probe=0eae2f92fa) | Jan 17, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [f908807ed9](https://linux-hardware.org/?probe=f908807ed9) | Jan 17, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [8bf0f8c8fe](https://linux-hardware.org/?probe=8bf0f8c8fe) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [18d3c84771](https://linux-hardware.org/?probe=18d3c84771) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [bd0bc47120](https://linux-hardware.org/?probe=bd0bc47120) | Jan 17, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [24d62d6974](https://linux-hardware.org/?probe=24d62d6974) | Jan 17, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [564482477e](https://linux-hardware.org/?probe=564482477e) | Jan 17, 2023 |
| Framework     | Laptop                      | Notebook    | [e94774a411](https://linux-hardware.org/?probe=e94774a411) | Jan 17, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6e8f360d6e](https://linux-hardware.org/?probe=6e8f360d6e) | Jan 17, 2023 |
| ASRock        | H87 Performance             | Desktop     | [a71c911bcf](https://linux-hardware.org/?probe=a71c911bcf) | Jan 17, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [22fca13d2b](https://linux-hardware.org/?probe=22fca13d2b) | Jan 17, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [2ba8d32a71](https://linux-hardware.org/?probe=2ba8d32a71) | Jan 17, 2023 |
| Gateway       | WG43M                       | Desktop     | [af3a009366](https://linux-hardware.org/?probe=af3a009366) | Jan 17, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [48cc2e0e69](https://linux-hardware.org/?probe=48cc2e0e69) | Jan 17, 2023 |
| Gateway       | WG43M                       | Desktop     | [b0aa3af22f](https://linux-hardware.org/?probe=b0aa3af22f) | Jan 17, 2023 |
| ASRock        | H87 Performance             | Desktop     | [9e2cd66ef5](https://linux-hardware.org/?probe=9e2cd66ef5) | Jan 16, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [2e65fc8357](https://linux-hardware.org/?probe=2e65fc8357) | Jan 16, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [ba736834cd](https://linux-hardware.org/?probe=ba736834cd) | Jan 16, 2023 |
| HC            | HCAR357-MI V1.0             | Desktop     | [ef934af180](https://linux-hardware.org/?probe=ef934af180) | Jan 16, 2023 |
| Acer          | Aspire 5625G                | Notebook    | [244d8473fc](https://linux-hardware.org/?probe=244d8473fc) | Jan 16, 2023 |
| Dell          | Latitude E7240              | Notebook    | [dc47f005d6](https://linux-hardware.org/?probe=dc47f005d6) | Jan 16, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [7eabefdc79](https://linux-hardware.org/?probe=7eabefdc79) | Jan 16, 2023 |
| Lenovo        | IdeaPad Y570 0862           | Notebook    | [8c43e56714](https://linux-hardware.org/?probe=8c43e56714) | Jan 16, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b51cc41cb3](https://linux-hardware.org/?probe=b51cc41cb3) | Jan 16, 2023 |
| System76      | Lemur Pro                   | Notebook    | [fde9d32359](https://linux-hardware.org/?probe=fde9d32359) | Jan 16, 2023 |
| ASRock        | B550 Extreme4               | Desktop     | [01f850d2fb](https://linux-hardware.org/?probe=01f850d2fb) | Jan 15, 2023 |
| Dell          | 0PXWHK A00                  | Desktop     | [82f04ecd77](https://linux-hardware.org/?probe=82f04ecd77) | Jan 15, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [64b089dfb7](https://linux-hardware.org/?probe=64b089dfb7) | Jan 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [db57593b81](https://linux-hardware.org/?probe=db57593b81) | Jan 14, 2023 |
| Dell          | 0PXWHK A00                  | Desktop     | [25db796fd6](https://linux-hardware.org/?probe=25db796fd6) | Jan 14, 2023 |
| MAXSUN        | MS-TZZ B460M                | Desktop     | [14758fc3e7](https://linux-hardware.org/?probe=14758fc3e7) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [f5499bf32a](https://linux-hardware.org/?probe=f5499bf32a) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [d3896698c8](https://linux-hardware.org/?probe=d3896698c8) | Jan 14, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [ffb8653d34](https://linux-hardware.org/?probe=ffb8653d34) | Jan 14, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [a92296f2e7](https://linux-hardware.org/?probe=a92296f2e7) | Jan 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [76f54ae84c](https://linux-hardware.org/?probe=76f54ae84c) | Jan 14, 2023 |
| Dell          | Precision 3571              | Notebook    | [c71e32c6ea](https://linux-hardware.org/?probe=c71e32c6ea) | Jan 14, 2023 |
| Acer          | Predator PT315-52           | Notebook    | [149941b52c](https://linux-hardware.org/?probe=149941b52c) | Jan 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [9eed89d744](https://linux-hardware.org/?probe=9eed89d744) | Jan 14, 2023 |
| Acer          | Aspire XC-603G              | Desktop     | [21e24944ad](https://linux-hardware.org/?probe=21e24944ad) | Jan 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d10834c7df](https://linux-hardware.org/?probe=d10834c7df) | Jan 14, 2023 |
| System76      | Oryx Pro                    | Notebook    | [da1374fa1c](https://linux-hardware.org/?probe=da1374fa1c) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | Desktop     | [4ce5e1fd02](https://linux-hardware.org/?probe=4ce5e1fd02) | Jan 14, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4c3d300ccc](https://linux-hardware.org/?probe=4c3d300ccc) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | Desktop     | [09560460b9](https://linux-hardware.org/?probe=09560460b9) | Jan 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [ed7ff7569c](https://linux-hardware.org/?probe=ed7ff7569c) | Jan 14, 2023 |
| ASUSTek       | P9X79-E WS                  | Desktop     | [e868d6909e](https://linux-hardware.org/?probe=e868d6909e) | Jan 14, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [2860788f11](https://linux-hardware.org/?probe=2860788f11) | Jan 14, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [c01da2fcf9](https://linux-hardware.org/?probe=c01da2fcf9) | Jan 14, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [d4a8ff871f](https://linux-hardware.org/?probe=d4a8ff871f) | Jan 14, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [10a9c33aed](https://linux-hardware.org/?probe=10a9c33aed) | Jan 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [362d8c4594](https://linux-hardware.org/?probe=362d8c4594) | Jan 13, 2023 |
| Dell          | Latitude 5300               | Notebook    | [148745c883](https://linux-hardware.org/?probe=148745c883) | Jan 13, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [84035db95c](https://linux-hardware.org/?probe=84035db95c) | Jan 13, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [1921b19009](https://linux-hardware.org/?probe=1921b19009) | Jan 13, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1ad37ae4cc](https://linux-hardware.org/?probe=1ad37ae4cc) | Jan 13, 2023 |
| Lenovo        | ThinkPad T500 2081CTO       | Notebook    | [96a079dbf8](https://linux-hardware.org/?probe=96a079dbf8) | Jan 13, 2023 |
| Lenovo        | ThinkPad T500 2081CTO       | Notebook    | [53b39e47e9](https://linux-hardware.org/?probe=53b39e47e9) | Jan 13, 2023 |
| HP            | 8299                        | Desktop     | [e4e0920f71](https://linux-hardware.org/?probe=e4e0920f71) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMS2BM00    | Notebook    | [afefa18c04](https://linux-hardware.org/?probe=afefa18c04) | Jan 12, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [f7304c0af2](https://linux-hardware.org/?probe=f7304c0af2) | Jan 12, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [22f9a03d68](https://linux-hardware.org/?probe=22f9a03d68) | Jan 12, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [a62af2c5a8](https://linux-hardware.org/?probe=a62af2c5a8) | Jan 11, 2023 |
| Dell          | Latitude E7240              | Notebook    | [93d832d08f](https://linux-hardware.org/?probe=93d832d08f) | Jan 11, 2023 |
| ASUSTek       | H61M-E                      | Desktop     | [38691cf2cc](https://linux-hardware.org/?probe=38691cf2cc) | Jan 11, 2023 |
| Lenovo        | IdeaPad Y570 20091          | Notebook    | [3538dd1b8a](https://linux-hardware.org/?probe=3538dd1b8a) | Jan 11, 2023 |
| Acer          | TravelMate P245-M           | Notebook    | [1722e41c8d](https://linux-hardware.org/?probe=1722e41c8d) | Jan 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [0f1f6b2662](https://linux-hardware.org/?probe=0f1f6b2662) | Jan 11, 2023 |
| Lenovo        | ThinkCentre M71e 3157W8B    | Desktop     | [70078ceabd](https://linux-hardware.org/?probe=70078ceabd) | Jan 11, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [aa36c50a9f](https://linux-hardware.org/?probe=aa36c50a9f) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [ae12526ceb](https://linux-hardware.org/?probe=ae12526ceb) | Jan 11, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [6694d6e805](https://linux-hardware.org/?probe=6694d6e805) | Jan 11, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [8d12a9a7ea](https://linux-hardware.org/?probe=8d12a9a7ea) | Jan 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a2363c6939](https://linux-hardware.org/?probe=a2363c6939) | Jan 11, 2023 |
| Acer          | Swift SF314-56              | Notebook    | [456445a93c](https://linux-hardware.org/?probe=456445a93c) | Jan 10, 2023 |
| Dell          | Latitude E7240              | Notebook    | [83a785903b](https://linux-hardware.org/?probe=83a785903b) | Jan 10, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | Mini pc     | [06eee6367f](https://linux-hardware.org/?probe=06eee6367f) | Jan 10, 2023 |
| ASUSTek       | P9X79-E WS                  | Desktop     | [f3b4e5135f](https://linux-hardware.org/?probe=f3b4e5135f) | Jan 10, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [547fc87531](https://linux-hardware.org/?probe=547fc87531) | Jan 10, 2023 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [f03ae5d905](https://linux-hardware.org/?probe=f03ae5d905) | Jan 10, 2023 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [9645ad91cc](https://linux-hardware.org/?probe=9645ad91cc) | Jan 10, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [0eb6418a53](https://linux-hardware.org/?probe=0eb6418a53) | Jan 10, 2023 |
| HP            | 8433 11                     | Desktop     | [5e26cba33b](https://linux-hardware.org/?probe=5e26cba33b) | Jan 10, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E30013... | Tablet      | [4bcaff2f2b](https://linux-hardware.org/?probe=4bcaff2f2b) | Jan 09, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [a365222a35](https://linux-hardware.org/?probe=a365222a35) | Jan 09, 2023 |
| Razer x La... | TensorBook (late 2021)      | Notebook    | [d798473e75](https://linux-hardware.org/?probe=d798473e75) | Jan 09, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [a9ee630b0b](https://linux-hardware.org/?probe=a9ee630b0b) | Jan 09, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [b39213e4d0](https://linux-hardware.org/?probe=b39213e4d0) | Jan 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aef797585c](https://linux-hardware.org/?probe=aef797585c) | Jan 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [e384aea51e](https://linux-hardware.org/?probe=e384aea51e) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [3982bc570e](https://linux-hardware.org/?probe=3982bc570e) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [1829eed17a](https://linux-hardware.org/?probe=1829eed17a) | Jan 09, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [e64cca399f](https://linux-hardware.org/?probe=e64cca399f) | Jan 09, 2023 |
| MSI           | B350M BAZOOKA               | Desktop     | [e7d2bcfcfb](https://linux-hardware.org/?probe=e7d2bcfcfb) | Jan 09, 2023 |
| Dell          | Latitude E7240              | Notebook    | [c191d76ac2](https://linux-hardware.org/?probe=c191d76ac2) | Jan 09, 2023 |
| ASRock        | X370 Gaming K4              | Desktop     | [0ed2f96ba8](https://linux-hardware.org/?probe=0ed2f96ba8) | Jan 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [36ed66f057](https://linux-hardware.org/?probe=36ed66f057) | Jan 08, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [1b055dc79d](https://linux-hardware.org/?probe=1b055dc79d) | Jan 08, 2023 |
| Wortmann      | NA92                        | All in one  | [7e4e12aab4](https://linux-hardware.org/?probe=7e4e12aab4) | Jan 08, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [22b35f0197](https://linux-hardware.org/?probe=22b35f0197) | Jan 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [07cc23f1cd](https://linux-hardware.org/?probe=07cc23f1cd) | Jan 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d784655474](https://linux-hardware.org/?probe=d784655474) | Jan 08, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [0b85968e35](https://linux-hardware.org/?probe=0b85968e35) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | Notebook    | [7e17526b20](https://linux-hardware.org/?probe=7e17526b20) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | Notebook    | [698649c9ae](https://linux-hardware.org/?probe=698649c9ae) | Jan 08, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [15f31fc9a5](https://linux-hardware.org/?probe=15f31fc9a5) | Jan 07, 2023 |
| Dell          | Latitude E7240              | Notebook    | [c7cf2afdd9](https://linux-hardware.org/?probe=c7cf2afdd9) | Jan 07, 2023 |
| HP            | ENVY dv6                    | Notebook    | [2a01900cb1](https://linux-hardware.org/?probe=2a01900cb1) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [f191d63ace](https://linux-hardware.org/?probe=f191d63ace) | Jan 07, 2023 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [4673ec60ea](https://linux-hardware.org/?probe=4673ec60ea) | Jan 07, 2023 |
| HP            | 2B4B                        | Desktop     | [57273c7b72](https://linux-hardware.org/?probe=57273c7b72) | Jan 07, 2023 |
| Dell          | Latitude E7240              | Notebook    | [7018e90a09](https://linux-hardware.org/?probe=7018e90a09) | Jan 07, 2023 |
| Dell          | 04GJJT A00                  | Desktop     | [85142569a6](https://linux-hardware.org/?probe=85142569a6) | Jan 07, 2023 |
| HUAWEI        | DRC-WXX                     | Tablet      | [b598f4182c](https://linux-hardware.org/?probe=b598f4182c) | Jan 07, 2023 |
| System76      | Bonobo WS                   | Notebook    | [afb9abd3c6](https://linux-hardware.org/?probe=afb9abd3c6) | Jan 07, 2023 |
| Dell          | Latitude E7240              | Notebook    | [d4dc080444](https://linux-hardware.org/?probe=d4dc080444) | Jan 07, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [ab9f1d1812](https://linux-hardware.org/?probe=ab9f1d1812) | Jan 07, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [bf425a41f8](https://linux-hardware.org/?probe=bf425a41f8) | Jan 07, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [63bc1e725c](https://linux-hardware.org/?probe=63bc1e725c) | Jan 07, 2023 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [89eccb038f](https://linux-hardware.org/?probe=89eccb038f) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [43f6676d9d](https://linux-hardware.org/?probe=43f6676d9d) | Jan 06, 2023 |
| Dell          | Latitude 7520               | Notebook    | [f4f253a52b](https://linux-hardware.org/?probe=f4f253a52b) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [67f40c78ec](https://linux-hardware.org/?probe=67f40c78ec) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [58f2e834d8](https://linux-hardware.org/?probe=58f2e834d8) | Jan 06, 2023 |
| Dell          | Precision M4700             | Notebook    | [414d8c4701](https://linux-hardware.org/?probe=414d8c4701) | Jan 06, 2023 |
| Dell          | Latitude E7240              | Notebook    | [b00208bba7](https://linux-hardware.org/?probe=b00208bba7) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f2024a8808](https://linux-hardware.org/?probe=f2024a8808) | Jan 06, 2023 |
| Acer          | Aspire M3970                | Desktop     | [2ef35b6d4b](https://linux-hardware.org/?probe=2ef35b6d4b) | Jan 05, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [0abf746107](https://linux-hardware.org/?probe=0abf746107) | Jan 05, 2023 |
| Dell          | Latitude E7240              | Notebook    | [6eae9dc932](https://linux-hardware.org/?probe=6eae9dc932) | Jan 05, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [1396e4d561](https://linux-hardware.org/?probe=1396e4d561) | Jan 05, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [7acb37a2f5](https://linux-hardware.org/?probe=7acb37a2f5) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2M30... | Notebook    | [1178b43f82](https://linux-hardware.org/?probe=1178b43f82) | Jan 05, 2023 |
| Intel         | HM570                       | Desktop     | [8728d2372a](https://linux-hardware.org/?probe=8728d2372a) | Jan 05, 2023 |
| AZW           | GTR V02                     | Desktop     | [2cf7a814cb](https://linux-hardware.org/?probe=2cf7a814cb) | Jan 05, 2023 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [28eb8d09fa](https://linux-hardware.org/?probe=28eb8d09fa) | Jan 05, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [4f54cd1f61](https://linux-hardware.org/?probe=4f54cd1f61) | Jan 05, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [0393900e99](https://linux-hardware.org/?probe=0393900e99) | Jan 05, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [04ca884448](https://linux-hardware.org/?probe=04ca884448) | Jan 05, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [98fafd877d](https://linux-hardware.org/?probe=98fafd877d) | Jan 04, 2023 |
| HP            | 3047h                       | Desktop     | [2c75b0b4ee](https://linux-hardware.org/?probe=2c75b0b4ee) | Jan 04, 2023 |
| System76      | Gazelle                     | Notebook    | [b603d1ecc7](https://linux-hardware.org/?probe=b603d1ecc7) | Jan 04, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [81269f2363](https://linux-hardware.org/?probe=81269f2363) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [8f42c7bc8c](https://linux-hardware.org/?probe=8f42c7bc8c) | Jan 04, 2023 |
| Datto         | Unknown                     | Notebook    | [e8c9c2e91f](https://linux-hardware.org/?probe=e8c9c2e91f) | Jan 04, 2023 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [afb6056f1d](https://linux-hardware.org/?probe=afb6056f1d) | Jan 04, 2023 |
| ASRock        | 760GM-HDV                   | Desktop     | [f994e91031](https://linux-hardware.org/?probe=f994e91031) | Jan 04, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d50cf83414](https://linux-hardware.org/?probe=d50cf83414) | Jan 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6da268e22f](https://linux-hardware.org/?probe=6da268e22f) | Jan 03, 2023 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [78367dd37f](https://linux-hardware.org/?probe=78367dd37f) | Jan 03, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [bd01380cb3](https://linux-hardware.org/?probe=bd01380cb3) | Jan 03, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [7b1ce41c16](https://linux-hardware.org/?probe=7b1ce41c16) | Jan 03, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [741f0d79a1](https://linux-hardware.org/?probe=741f0d79a1) | Jan 03, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [f6d1d35842](https://linux-hardware.org/?probe=f6d1d35842) | Jan 02, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [71ebcdc5ff](https://linux-hardware.org/?probe=71ebcdc5ff) | Jan 02, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [e8ad216a59](https://linux-hardware.org/?probe=e8ad216a59) | Jan 02, 2023 |
| HP            | Pro x360 435 13.3 inch G... | Convertible | [097761efca](https://linux-hardware.org/?probe=097761efca) | Jan 02, 2023 |
| Panasonic     | FZ55-1                      | Notebook    | [b09d64c936](https://linux-hardware.org/?probe=b09d64c936) | Jan 02, 2023 |
| ASUSTek       | P6T                         | Desktop     | [e648b2523e](https://linux-hardware.org/?probe=e648b2523e) | Jan 02, 2023 |
| Acer          | Aspire XC-603G              | Desktop     | [b2e25a20de](https://linux-hardware.org/?probe=b2e25a20de) | Jan 02, 2023 |
| Fujitsu       | FMVNS6C3                    | Notebook    | [49d8591166](https://linux-hardware.org/?probe=49d8591166) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0e4b6aa6c2](https://linux-hardware.org/?probe=0e4b6aa6c2) | Jan 02, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [1490ccc480](https://linux-hardware.org/?probe=1490ccc480) | Jan 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e26cc7285f](https://linux-hardware.org/?probe=e26cc7285f) | Jan 02, 2023 |
| Win elemen... | M600                        | Desktop     | [5d4320db68](https://linux-hardware.org/?probe=5d4320db68) | Jan 02, 2023 |
| Dell          | Latitude E7240              | Notebook    | [ccf48432e0](https://linux-hardware.org/?probe=ccf48432e0) | Jan 02, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [9be0f7265e](https://linux-hardware.org/?probe=9be0f7265e) | Jan 02, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [5e52308407](https://linux-hardware.org/?probe=5e52308407) | Jan 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [d841c27fe1](https://linux-hardware.org/?probe=d841c27fe1) | Jan 02, 2023 |
| ASUSTek       | UX310UQK                    | Notebook    | [79baf6f82a](https://linux-hardware.org/?probe=79baf6f82a) | Jan 01, 2023 |
| MSI           | PRO B550-VC                 | Desktop     | [f5574e6e00](https://linux-hardware.org/?probe=f5574e6e00) | Jan 01, 2023 |
| Dell          | Latitude E7270              | Notebook    | [09f72d101d](https://linux-hardware.org/?probe=09f72d101d) | Jan 01, 2023 |
| Dell          | XPS 9320                    | Notebook    | [28342f1b5c](https://linux-hardware.org/?probe=28342f1b5c) | Jan 01, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [a53517f382](https://linux-hardware.org/?probe=a53517f382) | Jan 01, 2023 |
| Dell          | XPS 9320                    | Notebook    | [4ef3eb6975](https://linux-hardware.org/?probe=4ef3eb6975) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [28f9b91b32](https://linux-hardware.org/?probe=28f9b91b32) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6b98637c82](https://linux-hardware.org/?probe=6b98637c82) | Jan 01, 2023 |
| Acer          | Aspire XC-603G              | Desktop     | [660548d31c](https://linux-hardware.org/?probe=660548d31c) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [34528f04fe](https://linux-hardware.org/?probe=34528f04fe) | Jan 01, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a51048ad0a](https://linux-hardware.org/?probe=a51048ad0a) | Jan 01, 2023 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [e5f5073bcd](https://linux-hardware.org/?probe=e5f5073bcd) | Dec 31, 2022 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [a470da90e8](https://linux-hardware.org/?probe=a470da90e8) | Dec 31, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [9f2441851f](https://linux-hardware.org/?probe=9f2441851f) | Dec 31, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [5b204eade4](https://linux-hardware.org/?probe=5b204eade4) | Dec 31, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [ad32666c8c](https://linux-hardware.org/?probe=ad32666c8c) | Dec 31, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [6f61aac097](https://linux-hardware.org/?probe=6f61aac097) | Dec 31, 2022 |
| HP            | EliteBook 8740w (WH274UT... | Notebook    | [e42d4e66a0](https://linux-hardware.org/?probe=e42d4e66a0) | Dec 31, 2022 |
| MSI           | GE60 2OC\2OE                | Notebook    | [c307379c36](https://linux-hardware.org/?probe=c307379c36) | Dec 30, 2022 |
| Dell          | G3 3500                     | Notebook    | [6be65a4ee5](https://linux-hardware.org/?probe=6be65a4ee5) | Dec 30, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [29984f68c6](https://linux-hardware.org/?probe=29984f68c6) | Dec 30, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [17fc3a4abc](https://linux-hardware.org/?probe=17fc3a4abc) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [76e9829e66](https://linux-hardware.org/?probe=76e9829e66) | Dec 30, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [db4379ed1e](https://linux-hardware.org/?probe=db4379ed1e) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [3f1ca6740d](https://linux-hardware.org/?probe=3f1ca6740d) | Dec 30, 2022 |
| Dell          | Latitude E7240              | Notebook    | [5f83c8f4ad](https://linux-hardware.org/?probe=5f83c8f4ad) | Dec 30, 2022 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [85bfa942e6](https://linux-hardware.org/?probe=85bfa942e6) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [d048930c78](https://linux-hardware.org/?probe=d048930c78) | Dec 30, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [4b3cfd1d9c](https://linux-hardware.org/?probe=4b3cfd1d9c) | Dec 30, 2022 |
| Dell          | G5 5590                     | Notebook    | [dada63bf04](https://linux-hardware.org/?probe=dada63bf04) | Dec 30, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [17f72460f6](https://linux-hardware.org/?probe=17f72460f6) | Dec 29, 2022 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [2373b5141b](https://linux-hardware.org/?probe=2373b5141b) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [956866bbdd](https://linux-hardware.org/?probe=956866bbdd) | Dec 29, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [aa2aad674b](https://linux-hardware.org/?probe=aa2aad674b) | Dec 29, 2022 |
| Lenovo        | ThinkPad W510 4389W14       | Notebook    | [c83a9ac8a9](https://linux-hardware.org/?probe=c83a9ac8a9) | Dec 29, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [467a749806](https://linux-hardware.org/?probe=467a749806) | Dec 29, 2022 |
| Acer          | Aspire XC-603G              | Desktop     | [08dc8ac6b7](https://linux-hardware.org/?probe=08dc8ac6b7) | Dec 29, 2022 |
| System76      | Lemur Pro                   | Notebook    | [0a61e4fe8d](https://linux-hardware.org/?probe=0a61e4fe8d) | Dec 29, 2022 |
| HP            | ENVY dv7                    | Notebook    | [97e029af78](https://linux-hardware.org/?probe=97e029af78) | Dec 29, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pop!_OS 22.04 | 2392      | 26.13%  |
| Pop!_OS 20.04 | 2123      | 23.19%  |
| Pop!_OS 21.04 | 1801      | 19.67%  |
| Pop!_OS 20.10 | 1651      | 18.04%  |
| Pop!_OS 21.10 | 1112      | 12.15%  |
| Pop!_OS 19.10 | 47        | 0.51%   |
| Pop!_OS 19.04 | 12        | 0.13%   |
| Pop!_OS 18.04 | 11        | 0.12%   |
| Pop!_OS 18.10 | 5         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Pop!_OS | 8651      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.11.0-7620-generic      | 837       | 8.52%   |
| 5.8.0-7630-generic       | 741       | 7.55%   |
| 5.4.0-7634-generic       | 666       | 6.78%   |
| 5.13.0-7614-generic      | 496       | 5.05%   |
| 5.8.0-7642-generic       | 482       | 4.91%   |
| 5.4.0-7642-generic       | 465       | 4.74%   |
| 6.0.12-76060006-generic  | 461       | 4.69%   |
| 5.17.5-76051705-generic  | 454       | 4.62%   |
| 5.19.0-76051900-generic  | 443       | 4.51%   |
| 5.11.0-7614-generic      | 438       | 4.46%   |
| 5.13.0-7620-generic      | 413       | 4.21%   |
| 6.0.6-76060006-generic   | 297       | 3.02%   |
| 5.15.15-76051515-generic | 280       | 2.85%   |
| 5.16.11-76051611-generic | 262       | 2.67%   |
| 5.15.5-76051505-generic  | 236       | 2.4%    |
| 5.11.0-7612-generic      | 226       | 2.3%    |
| 5.18.10-76051810-generic | 212       | 2.16%   |
| 5.8.0-7625-generic       | 196       | 2%      |
| 5.17.15-76051715-generic | 189       | 1.92%   |
| 5.11.0-7633-generic      | 180       | 1.83%   |
| 5.16.19-76051619-generic | 178       | 1.81%   |
| 5.15.8-76051508-generic  | 171       | 1.74%   |
| 5.16.15-76051615-generic | 151       | 1.54%   |
| 5.4.0-7626-generic       | 144       | 1.47%   |
| 5.15.11-76051511-generic | 115       | 1.17%   |
| 6.2.0-76060200-generic   | 110       | 1.12%   |
| 5.15.23-76051523-generic | 91        | 0.93%   |
| 6.1.11-76060111-generic  | 89        | 0.91%   |
| 6.0.2-76060002-generic   | 87        | 0.89%   |
| 5.4.0-7625-generic       | 74        | 0.75%   |
| 5.4.0-7629-generic       | 62        | 0.63%   |
| 6.2.6-76060206-generic   | 58        | 0.59%   |
| 5.19.16-76051916-generic | 43        | 0.44%   |
| 6.0.3-76060003-generic   | 39        | 0.4%    |
| 5.3.0-7625-generic       | 16        | 0.16%   |
| 5.3.0-7629-generic       | 10        | 0.1%    |
| 5.3.0-7648-generic       | 9         | 0.09%   |
| 5.11.0-051100-generic    | 9         | 0.09%   |
| 5.4.0-7624-generic       | 6         | 0.06%   |
| 5.13.0-1011-raspi        | 6         | 0.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 1625      | 16.91%  |
| 5.4.0   | 1370      | 14.25%  |
| 5.8.0   | 1359      | 14.14%  |
| 5.13.0  | 911       | 9.48%   |
| 6.0.12  | 463       | 4.82%   |
| 5.17.5  | 457       | 4.75%   |
| 5.19.0  | 446       | 4.64%   |
| 6.0.6   | 298       | 3.1%    |
| 5.15.15 | 281       | 2.92%   |
| 5.16.11 | 262       | 2.73%   |
| 5.15.5  | 236       | 2.46%   |
| 5.18.10 | 212       | 2.21%   |
| 5.17.15 | 189       | 1.97%   |
| 5.16.19 | 178       | 1.85%   |
| 5.15.8  | 171       | 1.78%   |
| 5.16.15 | 151       | 1.57%   |
| 5.15.11 | 115       | 1.2%    |
| 6.2.0   | 110       | 1.14%   |
| 5.15.23 | 91        | 0.95%   |
| 6.1.11  | 90        | 0.94%   |
| 6.0.2   | 90        | 0.94%   |
| 6.2.6   | 59        | 0.61%   |
| 5.3.0   | 51        | 0.53%   |
| 5.19.16 | 43        | 0.45%   |
| 6.0.3   | 39        | 0.41%   |
| 5.0.0   | 12        | 0.12%   |
| 5.15.0  | 11        | 0.11%   |
| 5.8.5   | 8         | 0.08%   |
| 5.7.0   | 8         | 0.08%   |
| 5.8.12  | 7         | 0.07%   |
| 4.18.0  | 7         | 0.07%   |
| 6.1.0   | 6         | 0.06%   |
| 5.13.12 | 6         | 0.06%   |
| 5.10.0  | 6         | 0.06%   |
| 5.8.6   | 5         | 0.05%   |
| 5.6.16  | 5         | 0.05%   |
| 5.7.8   | 4         | 0.04%   |
| 5.7.1   | 4         | 0.04%   |
| 5.14.0  | 4         | 0.04%   |
| 5.12.14 | 4         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 1634      | 17.17%  |
| 5.8     | 1396      | 14.67%  |
| 5.4     | 1374      | 14.44%  |
| 5.13    | 930       | 9.77%   |
| 5.15    | 901       | 9.47%   |
| 6.0     | 870       | 9.14%   |
| 5.17    | 646       | 6.79%   |
| 5.16    | 580       | 6.1%    |
| 5.19    | 491       | 5.16%   |
| 5.18    | 219       | 2.3%    |
| 6.2     | 172       | 1.81%   |
| 6.1     | 107       | 1.12%   |
| 5.3     | 51        | 0.54%   |
| 5.10    | 28        | 0.29%   |
| 5.7     | 27        | 0.28%   |
| 5.12    | 18        | 0.19%   |
| 5.14    | 16        | 0.17%   |
| 5.9     | 15        | 0.16%   |
| 5.6     | 15        | 0.16%   |
| 5.0     | 12        | 0.13%   |
| 4.18    | 8         | 0.08%   |
| 4.15    | 3         | 0.03%   |
| 5.1     | 1         | 0.01%   |
| 4.9     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 8634      | 99.8%   |
| aarch64 | 17        | 0.2%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 8383      | 96.33%  |
| KDE5            | 74        | 0.85%   |
| KDE             | 59        | 0.68%   |
| Unknown         | 56        | 0.64%   |
| X-Cinnamon      | 37        | 0.43%   |
| MATE            | 19        | 0.22%   |
| XFCE            | 16        | 0.18%   |
| GNOME Flashback | 15        | 0.17%   |
| Cinnamon        | 13        | 0.15%   |
| LXQt            | 11        | 0.13%   |
| Unity           | 6         | 0.07%   |
| Budgie          | 6         | 0.07%   |
| i3              | 3         | 0.03%   |
| pop             | 1         | 0.01%   |
| Pantheon        | 1         | 0.01%   |
| Deepin          | 1         | 0.01%   |
| awesome         | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 8420      | 96.8%   |
| Wayland | 239       | 2.75%   |
| Unknown | 26        | 0.3%    |
| Tty     | 13        | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 6933      | 79.36%  |
| GDM     | 1200      | 13.74%  |
| GDM3    | 577       | 6.6%    |
| SDDM    | 15        | 0.17%   |
| TDM     | 8         | 0.09%   |
| LightDM | 3         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 4990      | 57.26%  |
| en_GB   | 651       | 7.47%   |
| pt_BR   | 617       | 7.08%   |
| de_DE   | 408       | 4.68%   |
| C       | 266       | 3.05%   |
| en_AU   | 219       | 2.51%   |
| en_CA   | 192       | 2.2%    |
| fr_FR   | 171       | 1.96%   |
| it_IT   | 154       | 1.77%   |
| es_ES   | 138       | 1.58%   |
| ru_RU   | 110       | 1.26%   |
| pl_PL   | 77        | 0.88%   |
| Unknown | 73        | 0.84%   |
| sv_SE   | 58        | 0.67%   |
| pt_PT   | 55        | 0.63%   |
| nl_NL   | 54        | 0.62%   |
| en_IN   | 34        | 0.39%   |
| fi_FI   | 32        | 0.37%   |
| nb_NO   | 27        | 0.31%   |
| en_ZA   | 24        | 0.28%   |
| es_MX   | 22        | 0.25%   |
| fr_CA   | 21        | 0.24%   |
| es_AR   | 21        | 0.24%   |
| en_NZ   | 20        | 0.23%   |
| en_DK   | 18        | 0.21%   |
| tr_TR   | 17        | 0.2%    |
| es_CL   | 15        | 0.17%   |
| da_DK   | 14        | 0.16%   |
| cs_CZ   | 14        | 0.16%   |
| hu_HU   | 13        | 0.15%   |
| en_IE   | 13        | 0.15%   |
| sk_SK   | 12        | 0.14%   |
| nl_BE   | 12        | 0.14%   |
| hr_HR   | 12        | 0.14%   |
| ja_JP   | 11        | 0.13%   |
| zh_TW   | 10        | 0.11%   |
| de_CH   | 10        | 0.11%   |
| de_AT   | 10        | 0.11%   |
| ro_RO   | 9         | 0.1%    |
| zh_CN   | 7         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 6465      | 73.72%  |
| EFI  | 2305      | 26.28%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 8293      | 95.53%  |
| Btrfs   | 198       | 2.28%   |
| Overlay | 142       | 1.64%   |
| Xfs     | 28        | 0.32%   |
| Unknown | 13        | 0.15%   |
| Zfs     | 6         | 0.07%   |
| Ext2    | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 6888      | 78.99%  |
| GPT     | 1647      | 18.89%  |
| MBR     | 185       | 2.12%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 8445      | 97.25%  |
| Yes       | 239       | 2.75%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7920      | 91.11%  |
| Yes       | 773       | 8.89%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1505      | 17.4%   |
| Dell                    | 1154      | 13.34%  |
| Lenovo                  | 1148      | 13.27%  |
| Hewlett-Packard         | 920       | 10.63%  |
| Gigabyte Technology     | 667       | 7.71%   |
| MSI                     | 647       | 7.48%   |
| Acer                    | 415       | 4.8%    |
| Apple                   | 363       | 4.2%    |
| ASRock                  | 340       | 3.93%   |
| System76                | 203       | 2.35%   |
| Intel                   | 122       | 1.41%   |
| Toshiba                 | 95        | 1.1%    |
| Samsung Electronics     | 90        | 1.04%   |
| HUAWEI                  | 58        | 0.67%   |
| Alienware               | 55        | 0.64%   |
| Sony                    | 48        | 0.55%   |
| Microsoft               | 44        | 0.51%   |
| Notebook                | 43        | 0.5%    |
| Fujitsu                 | 43        | 0.5%    |
| Google                  | 40        | 0.46%   |
| Positivo                | 37        | 0.43%   |
| Unknown                 | 33        | 0.38%   |
| Pegatron                | 27        | 0.31%   |
| Razer                   | 24        | 0.28%   |
| Medion                  | 21        | 0.24%   |
| Supermicro              | 19        | 0.22%   |
| Timi                    | 17        | 0.2%    |
| Raspberry Pi Foundation | 17        | 0.2%    |
| Foxconn                 | 17        | 0.2%    |
| Biostar                 | 17        | 0.2%    |
| PC Specialist           | 16        | 0.18%   |
| LG Electronics          | 15        | 0.17%   |
| ECS                     | 15        | 0.17%   |
| TUXEDO                  | 14        | 0.16%   |
| Gateway                 | 13        | 0.15%   |
| Packard Bell            | 12        | 0.14%   |
| Framework               | 12        | 0.14%   |
| Huanan                  | 11        | 0.13%   |
| GPU Company             | 11        | 0.13%   |
| Avell High Performance  | 10        | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| ASUS All Series                | 84        | 0.97%   |
| Unknown                        | 46        | 0.53%   |
| System76 Oryx Pro              | 42        | 0.49%   |
| ASUS TUF Gaming X570-PLUS      | 41        | 0.47%   |
| System76 Lemur Pro             | 38        | 0.44%   |
| Gigabyte B450M DS3H            | 34        | 0.39%   |
| MSI MS-7C02                    | 30        | 0.35%   |
| Dell XPS 15 7590               | 30        | 0.35%   |
| ASUS ROG STRIX B450-F GAMING   | 28        | 0.32%   |
| MSI MS-7C37                    | 26        | 0.3%    |
| MSI MS-7B86                    | 26        | 0.3%    |
| Apple MacBookPro9,2            | 25        | 0.29%   |
| ASUS ROG STRIX B550-F GAMING   | 24        | 0.28%   |
| System76 Gazelle               | 23        | 0.27%   |
| Dell OptiPlex 9020             | 23        | 0.27%   |
| ASUS PRIME B450M-A             | 22        | 0.25%   |
| System76 Galago Pro            | 21        | 0.24%   |
| Gigabyte X570 AORUS ELITE      | 21        | 0.24%   |
| Dell XPS 15 9500               | 21        | 0.24%   |
| System76 Thelio                | 20        | 0.23%   |
| Apple MacBookPro12,1           | 20        | 0.23%   |
| HP Pavilion Notebook           | 19        | 0.22%   |
| Apple MacBookPro8,1            | 19        | 0.22%   |
| HP Notebook                    | 18        | 0.21%   |
| HP Pavilion 15                 | 17        | 0.2%    |
| System76 Darter Pro            | 16        | 0.18%   |
| Gigabyte A320M-S2H             | 16        | 0.18%   |
| ASRock B450M Pro4              | 16        | 0.18%   |
| Apple MacBookAir7,2            | 16        | 0.18%   |
| MSI MS-7C91                    | 15        | 0.17%   |
| HP Pavilion dv6                | 15        | 0.17%   |
| Dell OptiPlex 7010             | 15        | 0.17%   |
| ASRock B450M Steel Legend      | 15        | 0.17%   |
| Dell XPS 15 9560               | 14        | 0.16%   |
| Apple MacBookAir6,2            | 14        | 0.16%   |
| RPi Raspberry Pi               | 13        | 0.15%   |
| Lenovo IdeaPad S145-15API 81V7 | 13        | 0.15%   |
| Gigabyte X570 AORUS MASTER     | 13        | 0.15%   |
| Gigabyte B450 I AORUS PRO WIFI | 13        | 0.15%   |
| Gigabyte B450 AORUS PRO WIFI   | 13        | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 481       | 5.56%   |
| Dell Inspiron      | 326       | 3.77%   |
| ASUS ROG           | 293       | 3.39%   |
| Acer Aspire        | 279       | 3.23%   |
| Lenovo IdeaPad     | 267       | 3.09%   |
| Dell Latitude      | 213       | 2.46%   |
| Dell XPS           | 207       | 2.39%   |
| HP Pavilion        | 177       | 2.05%   |
| ASUS PRIME         | 177       | 2.05%   |
| ASUS TUF           | 148       | 1.71%   |
| Dell OptiPlex      | 143       | 1.65%   |
| HP EliteBook       | 107       | 1.24%   |
| Dell Precision     | 104       | 1.2%    |
| HP Laptop          | 91        | 1.05%   |
| ASUS VivoBook      | 90        | 1.04%   |
| ASUS All           | 84        | 0.97%   |
| Toshiba Satellite  | 83        | 0.96%   |
| HP ProBook         | 76        | 0.88%   |
| HP ENVY            | 76        | 0.88%   |
| Lenovo Legion      | 74        | 0.86%   |
| Gigabyte X570      | 72        | 0.83%   |
| HP Compaq          | 71        | 0.82%   |
| Lenovo Yoga        | 62        | 0.72%   |
| Dell Vostro        | 58        | 0.67%   |
| Lenovo ThinkCentre | 54        | 0.62%   |
| Gigabyte B450      | 51        | 0.59%   |
| Acer Nitro         | 50        | 0.58%   |
| Gigabyte B450M     | 48        | 0.55%   |
| Unknown            | 46        | 0.53%   |
| ASUS ASUS          | 45        | 0.52%   |
| Microsoft Surface  | 44        | 0.51%   |
| System76 Oryx      | 42        | 0.49%   |
| System76 Lemur     | 41        | 0.47%   |
| ASUS ZenBook       | 38        | 0.44%   |
| ASRock B450M       | 37        | 0.43%   |
| HP OMEN            | 36        | 0.42%   |
| Acer Swift         | 35        | 0.4%    |
| ASRock X570        | 33        | 0.38%   |
| Apple MacBookPro11 | 33        | 0.38%   |
| Apple MacBookPro9  | 32        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1114      | 12.88%  |
| 2020    | 1047      | 12.1%   |
| 2018    | 1035      | 11.96%  |
| 2021    | 713       | 8.24%   |
| 2012    | 636       | 7.35%   |
| 2017    | 596       | 6.89%   |
| 2013    | 542       | 6.27%   |
| 2011    | 501       | 5.79%   |
| 2015    | 467       | 5.4%    |
| 2014    | 435       | 5.03%   |
| 2016    | 432       | 4.99%   |
| 2010    | 329       | 3.8%    |
| 2009    | 244       | 2.82%   |
| 2022    | 238       | 2.75%   |
| 2008    | 181       | 2.09%   |
| 2007    | 94        | 1.09%   |
| 2006    | 21        | 0.24%   |
| Unknown | 18        | 0.21%   |
| 2023    | 5         | 0.06%   |
| 2005    | 2         | 0.02%   |
| 2004    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 4742      | 54.81%  |
| Desktop        | 3305      | 38.2%   |
| Convertible    | 239       | 2.76%   |
| Mini pc        | 111       | 1.28%   |
| All in one     | 105       | 1.21%   |
| Tablet         | 102       | 1.18%   |
| Server         | 28        | 0.32%   |
| System on chip | 18        | 0.21%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 8646      | 99.93%  |
| Enabled  | 6         | 0.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 8504      | 98.3%   |
| Yes  | 147       | 1.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 2294      | 26.17%  |
| 4.01-8.0        | 1899      | 21.66%  |
| 8.01-16.0       | 1627      | 18.56%  |
| 32.01-64.0      | 1199      | 13.68%  |
| 3.01-4.0        | 1071      | 12.22%  |
| 64.01-256.0     | 326       | 3.72%   |
| 24.01-32.0      | 178       | 2.03%   |
| 1.01-2.0        | 113       | 1.29%   |
| 2.01-3.0        | 48        | 0.55%   |
| More than 256.0 | 10        | 0.11%   |
| 0.51-1.0        | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 2885      | 30.49%  |
| 1.01-2.0    | 2369      | 25.03%  |
| 4.01-8.0    | 1905      | 20.13%  |
| 3.01-4.0    | 1746      | 18.45%  |
| 8.01-16.0   | 439       | 4.64%   |
| 16.01-24.0  | 61        | 0.64%   |
| 24.01-32.0  | 21        | 0.22%   |
| 0.51-1.0    | 19        | 0.2%    |
| 32.01-64.0  | 13        | 0.14%   |
| 64.01-256.0 | 4         | 0.04%   |
| 0.01-0.5    | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 4920      | 55.61%  |
| 2      | 2409      | 27.23%  |
| 3      | 776       | 8.77%   |
| 4      | 395       | 4.46%   |
| 5      | 166       | 1.88%   |
| 6      | 69        | 0.78%   |
| 0      | 50        | 0.57%   |
| 7      | 28        | 0.32%   |
| 8      | 10        | 0.11%   |
| 11     | 8         | 0.09%   |
| 9      | 7         | 0.08%   |
| 10     | 3         | 0.03%   |
| 23     | 1         | 0.01%   |
| 20     | 1         | 0.01%   |
| 19     | 1         | 0.01%   |
| 14     | 1         | 0.01%   |
| 13     | 1         | 0.01%   |
| 12     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 6159      | 70.84%  |
| Yes       | 2535      | 29.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7362      | 84.79%  |
| No        | 1321      | 15.21%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6999      | 80.5%   |
| No        | 1695      | 19.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5835      | 66.78%  |
| No        | 2902      | 33.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 2635      | 30.31%  |
| Brazil       | 825       | 9.49%   |
| Germany      | 576       | 6.63%   |
| UK           | 438       | 5.04%   |
| Canada       | 379       | 4.36%   |
| Australia    | 255       | 2.93%   |
| India        | 252       | 2.9%    |
| Italy        | 248       | 2.85%   |
| France       | 221       | 2.54%   |
| Netherlands  | 191       | 2.2%    |
| Sweden       | 147       | 1.69%   |
| Russia       | 142       | 1.63%   |
| Poland       | 133       | 1.53%   |
| Spain        | 115       | 1.32%   |
| Portugal     | 98        | 1.13%   |
| Mexico       | 95        | 1.09%   |
| Switzerland  | 88        | 1.01%   |
| South Africa | 86        | 0.99%   |
| Romania      | 84        | 0.97%   |
| Norway       | 84        | 0.97%   |
| Finland      | 82        | 0.94%   |
| Austria      | 66        | 0.76%   |
| Belgium      | 64        | 0.74%   |
| Greece       | 63        | 0.72%   |
| Philippines  | 61        | 0.7%    |
| New Zealand  | 61        | 0.7%    |
| Argentina    | 60        | 0.69%   |
| Denmark      | 55        | 0.63%   |
| Turkey       | 52        | 0.6%    |
| Indonesia    | 50        | 0.58%   |
| Chile        | 44        | 0.51%   |
| Czechia      | 41        | 0.47%   |
| Japan        | 39        | 0.45%   |
| Ireland      | 39        | 0.45%   |
| Hungary      | 38        | 0.44%   |
| Bulgaria     | 37        | 0.43%   |
| Malaysia     | 33        | 0.38%   |
| Croatia      | 33        | 0.38%   |
| Ukraine      | 31        | 0.36%   |
| Slovakia     | 28        | 0.32%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 96        | 1.06%   |
| Sydney         | 65        | 0.72%   |
| Melbourne      | 52        | 0.57%   |
| Berlin         | 51        | 0.56%   |
| Rio de Janeiro | 48        | 0.53%   |
| Brisbane       | 48        | 0.53%   |
| Milan          | 46        | 0.51%   |
| Vienna         | 41        | 0.45%   |
| Helsinki       | 41        | 0.45%   |
| London         | 40        | 0.44%   |
| Moscow         | 38        | 0.42%   |
| Dallas         | 38        | 0.42%   |
| Bengaluru      | 36        | 0.4%    |
| Warsaw         | 34        | 0.38%   |
| Chicago        | 34        | 0.38%   |
| New York       | 33        | 0.36%   |
| Paris          | 32        | 0.35%   |
| Athens         | 32        | 0.35%   |
| Amsterdam      | 32        | 0.35%   |
| Rome           | 31        | 0.34%   |
| Denver         | 30        | 0.33%   |
| Bucharest      | 30        | 0.33%   |
| Auckland       | 30        | 0.33%   |
| Toronto        | 29        | 0.32%   |
| Zurich         | 28        | 0.31%   |
| Miami          | 28        | 0.31%   |
| Seattle        | 27        | 0.3%    |
| Johannesburg   | 27        | 0.3%    |
| Sofia          | 26        | 0.29%   |
| Montreal       | 26        | 0.29%   |
| Los Angeles    | 26        | 0.29%   |
| Istanbul       | 26        | 0.29%   |
| Edmonton       | 26        | 0.29%   |
| Calgary        | 26        | 0.29%   |
| Brasília      | 26        | 0.29%   |
| Madrid         | 25        | 0.28%   |
| Lisbon         | 25        | 0.28%   |
| Phoenix        | 23        | 0.25%   |
| Dublin         | 23        | 0.25%   |
| Zagreb         | 22        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 2408      | 3654   | 18.1%   |
| WDC                       | 1789      | 2477   | 13.45%  |
| Seagate                   | 1778      | 2545   | 13.36%  |
| SanDisk                   | 889       | 1171   | 6.68%   |
| Kingston                  | 736       | 927    | 5.53%   |
| Toshiba                   | 703       | 859    | 5.28%   |
| Crucial                   | 534       | 701    | 4.01%   |
| Unknown                   | 428       | 549    | 3.22%   |
| SK hynix                  | 379       | 487    | 2.85%   |
| Intel                     | 371       | 500    | 2.79%   |
| Hitachi                   | 266       | 333    | 2%      |
| Phison                    | 229       | 320    | 1.72%   |
| HGST                      | 228       | 272    | 1.71%   |
| Micron Technology         | 209       | 249    | 1.57%   |
| A-DATA Technology         | 198       | 247    | 1.49%   |
| Apple                     | 170       | 198    | 1.28%   |
| PNY                       | 128       | 163    | 0.96%   |
| China                     | 119       | 158    | 0.89%   |
| Silicon Motion            | 118       | 158    | 0.89%   |
| Micron/Crucial Technology | 117       | 154    | 0.88%   |
| KIOXIA                    | 64        | 77     | 0.48%   |
| LITEON                    | 60        | 71     | 0.45%   |
| SPCC                      | 57        | 74     | 0.43%   |
| OCZ                       | 56        | 72     | 0.42%   |
| Phison Electronics        | 50        | 65     | 0.38%   |
| XPG                       | 49        | 64     | 0.37%   |
| Transcend                 | 46        | 53     | 0.35%   |
| Patriot                   | 44        | 59     | 0.33%   |
| Team                      | 43        | 52     | 0.32%   |
| Realtek Semiconductor     | 42        | 47     | 0.32%   |
| Corsair                   | 42        | 56     | 0.32%   |
| LITEONIT                  | 39        | 49     | 0.29%   |
| Maxtor                    | 35        | 36     | 0.26%   |
| JMicron Technology        | 34        | 50     | 0.26%   |
| Intenso                   | 31        | 35     | 0.23%   |
| ADATA Technology          | 31        | 40     | 0.23%   |
| KingSpec                  | 29        | 34     | 0.22%   |
| Hewlett-Packard           | 29        | 39     | 0.22%   |
| Lexar                     | 27        | 29     | 0.2%    |
| Netac                     | 26        | 27     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB                          | 197       | 1.34%   |
| Kingston SA400S37240G 240GB SSD                     | 195       | 1.32%   |
| Samsung NVMe SSD Drive 500GB                        | 178       | 1.21%   |
| Seagate ST1000LM035-1RK172 1TB                      | 124       | 0.84%   |
| Samsung SSD 850 EVO 250GB                           | 119       | 0.81%   |
| Samsung NVMe SSD Drive 512GB                        | 118       | 0.8%    |
| Samsung SSD 860 EVO 500GB                           | 110       | 0.75%   |
| SanDisk NVMe SSD Drive 1TB                          | 109       | 0.74%   |
| Samsung SSD 850 EVO 500GB                           | 106       | 0.72%   |
| Unknown MMC Card  64GB                              | 104       | 0.71%   |
| Samsung SSD 860 EVO 1TB                             | 101       | 0.69%   |
| Seagate ST2000DM008-2FR102 2TB                      | 98        | 0.67%   |
| SanDisk NVMe SSD Drive 500GB                        | 97        | 0.66%   |
| Seagate ST1000DM010-2EP102 1TB                      | 93        | 0.63%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 91        | 0.62%   |
| Kingston SA400S37120G 120GB SSD                     | 88        | 0.6%    |
| Kingston SA400S37480G 480GB SSD                     | 84        | 0.57%   |
| HGST HTS721010A9E630 1TB                            | 83        | 0.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 80        | 0.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 78        | 0.53%   |
| Seagate ST500DM002-1BD142 500GB                     | 77        | 0.52%   |
| Toshiba MQ01ABD100 1TB                              | 75        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB                         | 75        | 0.51%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 74        | 0.5%    |
| SanDisk NVMe SSD Drive 512GB                        | 71        | 0.48%   |
| Crucial CT500MX500SSD1 500GB                        | 71        | 0.48%   |
| Intel NVMe SSD Drive 512GB                          | 69        | 0.47%   |
| Unknown MMC Card  32GB                              | 68        | 0.46%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 66        | 0.45%   |
| Crucial CT240BX500SSD1 240GB                        | 65        | 0.44%   |
| SK hynix NVMe SSD Drive 512GB                       | 61        | 0.41%   |
| Samsung NVMe SSD Drive 2TB                          | 59        | 0.4%    |
| Samsung NVMe SSD Drive 1024GB                       | 58        | 0.39%   |
| Unknown MMC Card  128GB                             | 53        | 0.36%   |
| Samsung SSD 970 EVO Plus 1TB                        | 53        | 0.36%   |
| Samsung SSD 860 EVO 250GB                           | 53        | 0.36%   |
| Unknown SD/MMC/MS PRO 64GB                          | 52        | 0.35%   |
| Seagate Expansion+ 2TB                              | 52        | 0.35%   |
| Intel NVMe SSD Drive 1024GB                         | 52        | 0.35%   |
| Kingston SV300S37A120G 120GB SSD                    | 50        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1719      | 2415   | 38.64%  |
| WDC                 | 1375      | 1890   | 30.91%  |
| Toshiba             | 496       | 597    | 11.15%  |
| Hitachi             | 266       | 333    | 5.98%   |
| HGST                | 228       | 272    | 5.12%   |
| Samsung Electronics | 139       | 164    | 3.12%   |
| Unknown             | 56        | 68     | 1.26%   |
| Apple               | 48        | 60     | 1.08%   |
| Maxtor              | 27        | 28     | 0.61%   |
| Fujitsu             | 24        | 26     | 0.54%   |
| SABRENT             | 18        | 22     | 0.4%    |
| ASMT                | 16        | 23     | 0.36%   |
| JMicron Technology  | 5         | 13     | 0.11%   |
| USB                 | 3         | 4      | 0.07%   |
| Intenso             | 3         | 4      | 0.07%   |
| Hewlett-Packard     | 3         | 5      | 0.07%   |
| ExcelStor           | 3         | 3      | 0.07%   |
| RSH-339             | 2         | 2      | 0.04%   |
| PHD 3.0             | 2         | 2      | 0.04%   |
| Magnetic Data       | 2         | 2      | 0.04%   |
| HGST HTS            | 2         | 2      | 0.04%   |
| USB3.0              | 1         | 1      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| OEM                 | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 2      | 0.02%   |
| LaCie               | 1         | 1      | 0.02%   |
| HGST HDN            | 1         | 1      | 0.02%   |
| H/W                 | 1         | 1      | 0.02%   |
| Glyph               | 1         | 2      | 0.02%   |
| DAS                 | 1         | 4      | 0.02%   |
| ASMT109x            | 1         | 1      | 0.02%   |
| ASMedia             | 1         | 1      | 0.02%   |
| Asm                 | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1132      | 1661   | 24.4%   |
| Kingston            | 598       | 738    | 12.89%  |
| Crucial             | 495       | 650    | 10.67%  |
| SanDisk             | 435       | 554    | 9.38%   |
| WDC                 | 311       | 388    | 6.7%    |
| A-DATA Technology   | 155       | 194    | 3.34%   |
| PNY                 | 125       | 160    | 2.69%   |
| China               | 117       | 156    | 2.52%   |
| Intel               | 105       | 130    | 2.26%   |
| Apple               | 103       | 109    | 2.22%   |
| SK hynix            | 86        | 111    | 1.85%   |
| Micron Technology   | 75        | 82     | 1.62%   |
| Toshiba             | 70        | 81     | 1.51%   |
| OCZ                 | 55        | 68     | 1.19%   |
| LITEON              | 55        | 66     | 1.19%   |
| SPCC                | 51        | 63     | 1.1%    |
| Transcend           | 45        | 52     | 0.97%   |
| Patriot             | 44        | 59     | 0.95%   |
| LITEONIT            | 39        | 49     | 0.84%   |
| Team                | 36        | 45     | 0.78%   |
| Seagate             | 32        | 48     | 0.69%   |
| Corsair             | 32        | 39     | 0.69%   |
| KingSpec            | 29        | 34     | 0.63%   |
| Lexar               | 24        | 25     | 0.52%   |
| Netac               | 23        | 24     | 0.5%    |
| Hewlett-Packard     | 22        | 30     | 0.47%   |
| Intenso             | 20        | 23     | 0.43%   |
| JMicron Technology  | 17        | 18     | 0.37%   |
| Goodram             | 15        | 17     | 0.32%   |
| Apacer              | 15        | 23     | 0.32%   |
| KingDian            | 13        | 19     | 0.28%   |
| TO Exter            | 12        | 15     | 0.26%   |
| Plextor             | 12        | 16     | 0.26%   |
| Mushkin             | 12        | 15     | 0.26%   |
| Gigabyte Technology | 12        | 14     | 0.26%   |
| Dogfish             | 10        | 14     | 0.22%   |
| OWC                 | 8         | 17     | 0.17%   |
| Maxtor              | 8         | 8      | 0.17%   |
| PNY USB             | 6         | 13     | 0.13%   |
| KIOXIA-EXCERIA      | 6         | 6      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 4022      | 6039   | 33.74%  |
| HDD     | 3796      | 5952   | 31.85%  |
| NVMe    | 3554      | 5271   | 29.82%  |
| MMC     | 328       | 408    | 2.75%   |
| Unknown | 220       | 311    | 1.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6195      | 11542  | 58.48%  |
| NVMe | 3547      | 5250   | 33.48%  |
| SAS  | 524       | 781    | 4.95%   |
| MMC  | 328       | 408    | 3.1%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 4511      | 6744   | 55.18%  |
| 0.51-1.0        | 2460      | 3406   | 30.09%  |
| 1.01-2.0        | 715       | 1010   | 8.75%   |
| 3.01-4.0        | 189       | 310    | 2.31%   |
| 4.01-10.0       | 141       | 259    | 1.72%   |
| 2.01-3.0        | 140       | 214    | 1.71%   |
| 10.01-20.0      | 15        | 43     | 0.18%   |
| More than 100.0 | 4         | 5      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2664      | 29.63%  |
| 251-500        | 2248      | 25.01%  |
| 501-1000       | 1676      | 18.64%  |
| 1001-2000      | 836       | 9.3%    |
| More than 3000 | 412       | 4.58%   |
| 51-100         | 408       | 4.54%   |
| 2001-3000      | 279       | 3.1%    |
| 1-20           | 212       | 2.36%   |
| 21-50          | 198       | 2.2%    |
| Unknown        | 57        | 0.63%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3465      | 36.84%  |
| 21-50          | 1897      | 20.17%  |
| 101-250        | 1169      | 12.43%  |
| 51-100         | 1129      | 12%     |
| 251-500        | 712       | 7.57%   |
| 501-1000       | 468       | 4.98%   |
| 1001-2000      | 270       | 2.87%   |
| More than 3000 | 148       | 1.57%   |
| 2001-3000      | 91        | 0.97%   |
| Unknown        | 57        | 0.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB    | 7         | 7      | 2.68%   |
| HGST HTS725050A7E630 500GB            | 6         | 9      | 2.3%    |
| HGST HTS721010A9E630 1TB              | 5         | 5      | 1.92%   |
| Seagate ST1000LM035-1RK172 1TB        | 4         | 4      | 1.53%   |
| HGST HTS541010A9E680 1TB              | 4         | 4      | 1.53%   |
| WDC WD10JPCX-24UE4T0 1TB              | 3         | 3      | 1.15%   |
| Seagate ST500LT012-9WS142 500GB       | 3         | 4      | 1.15%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 1.15%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 3         | 3      | 1.15%   |
| Seagate ST500DM002-1BD142 500GB       | 3         | 3      | 1.15%   |
| Seagate ST1500DL003-9VT16L 1TB        | 3         | 4      | 1.15%   |
| Seagate ST1000LX015-1U7172 1TB        | 3         | 3      | 1.15%   |
| Seagate ST1000DM003-9YN162 1TB        | 3         | 3      | 1.15%   |
| Samsung Electronics HD502HI 500GB     | 3         | 4      | 1.15%   |
| Kingston SV300S37A120G 120GB SSD      | 3         | 5      | 1.15%   |
| Kingston SA400S37120G 120GB SSD       | 3         | 5      | 1.15%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 5      | 1.15%   |
| Crucial CT525MX300SSD1 528GB          | 3         | 3      | 1.15%   |
| Crucial CT1000P1SSD8 1TB              | 3         | 3      | 1.15%   |
| WDC WD3200AAKS-75B3A0 320GB           | 2         | 2      | 0.77%   |
| WDC WD10JPVX-60JC3T0 1TB              | 2         | 2      | 0.77%   |
| WDC WD10EZEX-60WN4A0 1TB              | 2         | 2      | 0.77%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2         | 2      | 0.77%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 0.77%   |
| Toshiba HDWD110 1TB                   | 2         | 2      | 0.77%   |
| SK hynix PC711 HFS001TDE9X073N 1TB    | 2         | 2      | 0.77%   |
| Seagate ST9750420AS 752GB             | 2         | 2      | 0.77%   |
| Seagate ST9500325AS 500GB             | 2         | 3      | 0.77%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 0.77%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 2      | 0.77%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 2         | 2      | 0.77%   |
| Samsung Electronics SSD 850 EVO 500GB | 2         | 2      | 0.77%   |
| Samsung Electronics HD103SJ 1TB       | 2         | 2      | 0.77%   |
| Kingston SUV400S37120G 120GB SSD      | 2         | 2      | 0.77%   |
| Hitachi HDP725050GLA360 500GB         | 2         | 2      | 0.77%   |
| HGST HTS545050A7E680 500GB            | 2         | 2      | 0.77%   |
| A-DATA Technology SU800 512GB SSD     | 2         | 2      | 0.77%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.38%   |
| WDC WD7500BPVT-60HXZT1 752GB          | 1         | 1      | 0.38%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 1         | 1      | 0.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 62        | 71     | 24.12%  |
| WDC                 | 54        | 62     | 21.01%  |
| Samsung Electronics | 26        | 31     | 10.12%  |
| HGST                | 19        | 22     | 7.39%   |
| Toshiba             | 18        | 19     | 7%      |
| Kingston            | 12        | 16     | 4.67%   |
| Hitachi             | 12        | 15     | 4.67%   |
| Crucial             | 9         | 9      | 3.5%    |
| SK hynix            | 8         | 10     | 3.11%   |
| Intel               | 7         | 7      | 2.72%   |
| Micron Technology   | 6         | 8      | 2.33%   |
| A-DATA Technology   | 6         | 6      | 2.33%   |
| SanDisk             | 3         | 3      | 1.17%   |
| China               | 2         | 2      | 0.78%   |
| Team                | 1         | 1      | 0.39%   |
| SPCC                | 1         | 1      | 0.39%   |
| SABRENT             | 1         | 1      | 0.39%   |
| S3+                 | 1         | 1      | 0.39%   |
| Plextor             | 1         | 1      | 0.39%   |
| Maxtor              | 1         | 1      | 0.39%   |
| LITEON              | 1         | 1      | 0.39%   |
| Lexar               | 1         | 1      | 0.39%   |
| Leven               | 1         | 1      | 0.39%   |
| Intenso             | 1         | 1      | 0.39%   |
| BAITITON            | 1         | 1      | 0.39%   |
| ASMT                | 1         | 1      | 0.39%   |
| Apple               | 1         | 1      | 0.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 62        | 71     | 35.63%  |
| WDC                 | 52        | 60     | 29.89%  |
| HGST                | 19        | 22     | 10.92%  |
| Toshiba             | 15        | 15     | 8.62%   |
| Hitachi             | 12        | 15     | 6.9%    |
| Samsung Electronics | 10        | 11     | 5.75%   |
| SABRENT             | 1         | 1      | 0.57%   |
| Maxtor              | 1         | 1      | 0.57%   |
| ASMT                | 1         | 1      | 0.57%   |
| Apple               | 1         | 1      | 0.57%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 162       | 198    | 66.12%  |
| SSD  | 61        | 72     | 24.9%   |
| NVMe | 22        | 24     | 8.98%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST3500418ASQ 500GB        | 1         | 1      | 25%     |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 25%     |
| Patriot Pyro SSD 120GB            | 1         | 2      | 25%     |
| KingDian S400 120GB SSD           | 1         | 2      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |
| Patriot             | 1         | 2      | 25%     |
| KingDian            | 1         | 2      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 7010      | 14679  | 77.3%   |
| Works    | 1816      | 3001   | 20.02%  |
| Malfunc  | 238       | 294    | 2.62%   |
| Failed   | 4         | 6      | 0.04%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5307      | 44.89%  |
| AMD                              | 2141      | 18.11%  |
| Samsung Electronics              | 1424      | 12.05%  |
| SanDisk                          | 596       | 5.04%   |
| SK hynix                         | 292       | 2.47%   |
| Phison Electronics               | 292       | 2.47%   |
| ASMedia Technology               | 197       | 1.67%   |
| Kingston Technology Company      | 160       | 1.35%   |
| Toshiba America Info Systems     | 153       | 1.29%   |
| Nvidia                           | 152       | 1.29%   |
| Micron/Crucial Technology        | 151       | 1.28%   |
| Micron Technology                | 137       | 1.16%   |
| Silicon Motion                   | 132       | 1.12%   |
| ADATA Technology                 | 109       | 0.92%   |
| Marvell Technology Group         | 107       | 0.91%   |
| JMicron Technology               | 84        | 0.71%   |
| KIOXIA                           | 67        | 0.57%   |
| Realtek Semiconductor            | 56        | 0.47%   |
| Solid State Storage Technology   | 36        | 0.3%    |
| Union Memory (Shenzhen)          | 35        | 0.3%    |
| Broadcom / LSI                   | 27        | 0.23%   |
| Seagate Technology               | 25        | 0.21%   |
| Apple                            | 22        | 0.19%   |
| LSI Logic / Symbios Logic        | 19        | 0.16%   |
| Lite-On Technology               | 16        | 0.14%   |
| Shenzhen Longsys Electronics     | 13        | 0.11%   |
| VIA Technologies                 | 10        | 0.08%   |
| Silicon Integrated Systems [SiS] | 10        | 0.08%   |
| Silicon Image                    | 7         | 0.06%   |
| Lenovo                           | 7         | 0.06%   |
| Hewlett-Packard                  | 7         | 0.06%   |
| INNOGRIT                         | 6         | 0.05%   |
| Adaptec                          | 6         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.04%   |
| HighPoint Technologies           | 3         | 0.03%   |
| OCZ Technology Group             | 2         | 0.02%   |
| Yangtze Memory Technologies      | 1         | 0.01%   |
| Transcend                        | 1         | 0.01%   |
| O2 Micro                         | 1         | 0.01%   |
| Netac Technology                 | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1605      | 12.01%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 805       | 6.03%   |
| AMD 400 Series Chipset SATA Controller                                         | 440       | 3.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 430       | 3.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 351       | 2.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 347       | 2.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 323       | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 269       | 2.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 242       | 1.81%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 218       | 1.63%   |
| AMD 500 Series Chipset SATA Controller                                         | 217       | 1.62%   |
| Samsung NVMe SSD Controller 980                                                | 193       | 1.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 189       | 1.41%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 188       | 1.41%   |
| Intel Volume Management Device NVMe RAID Controller                            | 181       | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 172       | 1.29%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 171       | 1.28%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 170       | 1.27%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 168       | 1.26%   |
| Intel SATA Controller [RAID mode]                                              | 159       | 1.19%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 158       | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 150       | 1.12%   |
| Phison E12 NVMe Controller                                                     | 149       | 1.12%   |
| Intel SSD 660P Series                                                          | 143       | 1.07%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 140       | 1.05%   |
| Micron NVMe Storage Controller                                                 | 133       | 1%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 132       | 0.99%   |
| Intel Comet Lake SATA AHCI Controller                                          | 131       | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 130       | 0.97%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 130       | 0.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 114       | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 112       | 0.84%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 108       | 0.81%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 106       | 0.79%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 102       | 0.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 97        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 95        | 0.71%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 90        | 0.67%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 84        | 0.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 79        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 6502      | 56.05%  |
| NVMe | 3546      | 30.57%  |
| RAID | 771       | 6.65%   |
| IDE  | 727       | 6.27%   |
| SAS  | 39        | 0.34%   |
| SCSI | 15        | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 6110      | 70.63%  |
| AMD    | 2524      | 29.18%  |
| ARM    | 17        | 0.2%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 148       | 1.71%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 123       | 1.42%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 112       | 1.29%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 105       | 1.21%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 100       | 1.15%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 96        | 1.11%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 94        | 1.08%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 87        | 1%      |
| Intel Core i5-7200U CPU @ 2.50GHz             | 78        | 0.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 75        | 0.86%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 74        | 0.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 72        | 0.83%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 71        | 0.82%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 70        | 0.81%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 70        | 0.81%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 67        | 0.77%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 67        | 0.77%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 66        | 0.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 59        | 0.68%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 56        | 0.65%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 55        | 0.63%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 53        | 0.61%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 52        | 0.6%    |
| AMD Ryzen 5 1600 Six-Core Processor           | 51        | 0.59%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 49        | 0.57%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 47        | 0.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 47        | 0.54%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 47        | 0.54%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 46        | 0.53%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 44        | 0.51%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 44        | 0.51%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 43        | 0.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 43        | 0.5%    |
| Intel Core i5-2400 CPU @ 3.10GHz              | 43        | 0.5%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 43        | 0.5%    |
| AMD Ryzen 9 5900X 12-Core Processor           | 43        | 0.5%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 42        | 0.48%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 41        | 0.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 40        | 0.46%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 40        | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 2066      | 23.84%  |
| Intel Core i5           | 1891      | 21.82%  |
| AMD Ryzen 5             | 817       | 9.43%   |
| AMD Ryzen 7             | 633       | 7.31%   |
| Other                   | 530       | 6.12%   |
| Intel Core i3           | 489       | 5.64%   |
| Intel Core 2 Duo        | 250       | 2.89%   |
| AMD Ryzen 9             | 242       | 2.79%   |
| Intel Celeron           | 221       | 2.55%   |
| Intel Xeon              | 192       | 2.22%   |
| AMD FX                  | 125       | 1.44%   |
| AMD Ryzen 3             | 124       | 1.43%   |
| Intel Pentium           | 107       | 1.23%   |
| Intel Core i9           | 105       | 1.21%   |
| AMD A6                  | 63        | 0.73%   |
| Intel Pentium Dual-Core | 61        | 0.7%    |
| Intel Atom              | 61        | 0.7%    |
| AMD A8                  | 61        | 0.7%    |
| AMD A10                 | 57        | 0.66%   |
| Intel Core 2 Quad       | 49        | 0.57%   |
| AMD Ryzen Threadripper  | 47        | 0.54%   |
| AMD A4                  | 37        | 0.43%   |
| AMD Ryzen 7 PRO         | 36        | 0.42%   |
| Intel Core 2            | 32        | 0.37%   |
| AMD Phenom II X4        | 32        | 0.37%   |
| AMD Athlon              | 27        | 0.31%   |
| Intel Pentium Dual      | 21        | 0.24%   |
| AMD Athlon II X2        | 21        | 0.24%   |
| AMD Ryzen 5 PRO         | 20        | 0.23%   |
| Intel Genuine           | 16        | 0.18%   |
| Intel Core m3           | 16        | 0.18%   |
| AMD Athlon II X4        | 14        | 0.16%   |
| AMD Phenom II X6        | 13        | 0.15%   |
| AMD E1                  | 13        | 0.15%   |
| Intel Pentium Silver    | 12        | 0.14%   |
| AMD E                   | 12        | 0.14%   |
| AMD Athlon 64 X2        | 12        | 0.14%   |
| Intel Pentium Gold      | 9         | 0.1%    |
| AMD Phenom              | 9         | 0.1%    |
| AMD E2                  | 9         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 3217      | 37.13%  |
| 2       | 2702      | 31.18%  |
| 6       | 1242      | 14.33%  |
| 8       | 957       | 11.04%  |
| 12      | 187       | 2.16%   |
| 16      | 92        | 1.06%   |
| 10      | 60        | 0.69%   |
| 1       | 56        | 0.65%   |
| 3       | 51        | 0.59%   |
| 14      | 49        | 0.57%   |
| 24      | 19        | 0.22%   |
| 32      | 16        | 0.18%   |
| Unknown | 6         | 0.07%   |
| 64      | 4         | 0.05%   |
| 40      | 1         | 0.01%   |
| 36      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |
| 20      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |
| 7       | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 8596      | 99.35%  |
| 2       | 50        | 0.58%   |
| Unknown | 6         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 6637      | 76.61%  |
| 1       | 2020      | 23.32%  |
| Unknown | 6         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 8626      | 99.71%  |
| 64-bit         | 14        | 0.16%   |
| Unknown        | 11        | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5858      | 66.09%  |
| 0x906ea    | 192       | 2.17%   |
| 0x306a9    | 166       | 1.87%   |
| 0x206a7    | 146       | 1.65%   |
| 0x306c3    | 133       | 1.5%    |
| 0x806ea    | 125       | 1.41%   |
| 0x806ec    | 124       | 1.4%    |
| 0x806c1    | 117       | 1.32%   |
| 0x08701021 | 103       | 1.16%   |
| 0x406e3    | 94        | 1.06%   |
| 0x906e9    | 88        | 0.99%   |
| 0x40651    | 86        | 0.97%   |
| 0x806e9    | 79        | 0.89%   |
| 0x506e3    | 79        | 0.89%   |
| 0x08701013 | 76        | 0.86%   |
| 0xa0652    | 74        | 0.83%   |
| 0x0800820d | 73        | 0.82%   |
| 0x1067a    | 63        | 0.71%   |
| 0x0a50000c | 57        | 0.64%   |
| 0x08108109 | 52        | 0.59%   |
| 0x08108102 | 47        | 0.53%   |
| 0x906ed    | 44        | 0.5%    |
| 0x306d4    | 44        | 0.5%    |
| 0x08600106 | 44        | 0.5%    |
| 0x806d1    | 38        | 0.43%   |
| 0x806eb    | 37        | 0.42%   |
| 0x20655    | 30        | 0.34%   |
| 0x706e5    | 27        | 0.3%    |
| 0x08001138 | 27        | 0.3%    |
| 0x406c4    | 26        | 0.29%   |
| 0x0a201016 | 26        | 0.29%   |
| 0x08608103 | 26        | 0.29%   |
| 0x906a3    | 25        | 0.28%   |
| 0x08600104 | 25        | 0.28%   |
| 0x0810100b | 25        | 0.28%   |
| 0x06000852 | 24        | 0.27%   |
| 0x06006705 | 19        | 0.21%   |
| 0x06001119 | 19        | 0.21%   |
| 0x706a1    | 18        | 0.2%    |
| 0x08600103 | 18        | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1587      | 18.31%  |
| Haswell          | 803       | 9.27%   |
| Zen 2            | 699       | 8.07%   |
| IvyBridge        | 587       | 6.77%   |
| SandyBridge      | 582       | 6.72%   |
| Skylake          | 481       | 5.55%   |
| Zen+             | 462       | 5.33%   |
| Zen 3            | 415       | 4.79%   |
| Unknown          | 322       | 3.72%   |
| Penryn           | 316       | 3.65%   |
| CometLake        | 287       | 3.31%   |
| TigerLake        | 262       | 3.02%   |
| Zen              | 231       | 2.67%   |
| Westmere         | 206       | 2.38%   |
| Broadwell        | 194       | 2.24%   |
| Piledriver       | 179       | 2.07%   |
| Silvermont       | 142       | 1.64%   |
| Core             | 136       | 1.57%   |
| K10              | 112       | 1.29%   |
| IceLake          | 112       | 1.29%   |
| Nehalem          | 95        | 1.1%    |
| Excavator        | 85        | 0.98%   |
| Goldmont plus    | 73        | 0.84%   |
| Alderlake Hybrid | 45        | 0.52%   |
| Puma             | 44        | 0.51%   |
| Steamroller      | 39        | 0.45%   |
| Goldmont         | 31        | 0.36%   |
| K8 Hammer        | 29        | 0.33%   |
| Bobcat           | 27        | 0.31%   |
| K10 Llano        | 25        | 0.29%   |
| Jaguar           | 19        | 0.22%   |
| Bulldozer        | 13        | 0.15%   |
| NetBurst         | 9         | 0.1%    |
| K8 & K10 hybrid  | 8         | 0.09%   |
| Bonnell          | 6         | 0.07%   |
| Tremont          | 3         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4538      | 42.99%  |
| Nvidia                           | 3516      | 33.31%  |
| AMD                              | 2475      | 23.45%  |
| Matrox Electronics Systems       | 14        | 0.13%   |
| Silicon Integrated Systems [SiS] | 8         | 0.08%   |
| ASPEED Technology                | 3         | 0.03%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 406       | 3.75%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 322       | 2.97%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 321       | 2.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 261       | 2.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 255       | 2.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 251       | 2.32%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 242       | 2.23%   |
| Intel UHD Graphics 620                                                                   | 238       | 2.2%    |
| AMD Renoir                                                                               | 211       | 1.95%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 188       | 1.74%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 171       | 1.58%   |
| Intel HD Graphics 620                                                                    | 169       | 1.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 163       | 1.51%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 157       | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 153       | 1.41%   |
| Intel HD Graphics 630                                                                    | 146       | 1.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 138       | 1.27%   |
| Intel HD Graphics 5500                                                                   | 125       | 1.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 124       | 1.15%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 123       | 1.14%   |
| Intel Core Processor Integrated Graphics Controller                                      | 121       | 1.12%   |
| Intel HD Graphics 530                                                                    | 118       | 1.09%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 116       | 1.07%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 108       | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 93        | 0.86%   |
| AMD Lucienne                                                                             | 89        | 0.82%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 88        | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 85        | 0.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 83        | 0.77%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 81        | 0.75%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 78        | 0.72%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 75        | 0.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 69        | 0.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 68        | 0.63%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 66        | 0.61%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 65        | 0.6%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 65        | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 64        | 0.59%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 62        | 0.57%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 61        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 2964      | 33.92%  |
| 1 x Nvidia              | 1934      | 22.13%  |
| 1 x AMD                 | 1875      | 21.46%  |
| Intel + Nvidia          | 1264      | 14.47%  |
| AMD + Nvidia            | 247       | 2.83%   |
| Intel + AMD             | 211       | 2.41%   |
| 2 x AMD                 | 144       | 1.65%   |
| 2 x Nvidia              | 44        | 0.5%    |
| Other                   | 20        | 0.23%   |
| 1 x SiS                 | 8         | 0.09%   |
| 1 x Matrox              | 8         | 0.09%   |
| Intel + 2 x Nvidia      | 4         | 0.05%   |
| Nvidia + Matrox         | 3         | 0.03%   |
| Nvidia + ASPEED         | 3         | 0.03%   |
| AMD + Matrox            | 2         | 0.02%   |
| 5 x Nvidia              | 1         | 0.01%   |
| 4 x Nvidia              | 1         | 0.01%   |
| 3 x Nvidia              | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia    | 1         | 0.01%   |
| 1 x S3 Graphics         | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5566      | 63.62%  |
| Proprietary | 2819      | 32.22%  |
| Unknown     | 364       | 4.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5902      | 66.83%  |
| 1.01-2.0   | 640       | 7.25%   |
| 3.01-4.0   | 602       | 6.82%   |
| 7.01-8.0   | 554       | 6.27%   |
| 5.01-6.0   | 420       | 4.76%   |
| 0.01-0.5   | 271       | 3.07%   |
| 0.51-1.0   | 185       | 2.09%   |
| 8.01-16.0  | 153       | 1.73%   |
| 2.01-3.0   | 80        | 0.91%   |
| 16.01-24.0 | 20        | 0.23%   |
| 4.01-5.0   | 3         | 0.03%   |
| 32.01-64.0 | 1         | 0.01%   |
| 24.01-32.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1173      | 12.04%  |
| AU Optronics            | 1049      | 10.77%  |
| Chimei Innolux          | 849       | 8.71%   |
| LG Display              | 829       | 8.51%   |
| BOE                     | 756       | 7.76%   |
| Goldstar                | 618       | 6.34%   |
| Dell                    | 607       | 6.23%   |
| Acer                    | 396       | 4.06%   |
| Hewlett-Packard         | 297       | 3.05%   |
| Apple                   | 284       | 2.91%   |
| AOC                     | 273       | 2.8%    |
| Sharp                   | 228       | 2.34%   |
| Ancor Communications    | 217       | 2.23%   |
| BenQ                    | 216       | 2.22%   |
| ASUSTek Computer        | 159       | 1.63%   |
| Philips                 | 158       | 1.62%   |
| Lenovo                  | 144       | 1.48%   |
| PANDA                   | 140       | 1.44%   |
| ViewSonic               | 89        | 0.91%   |
| Chi Mei Optoelectronics | 85        | 0.87%   |
| Iiyama                  | 69        | 0.71%   |
| Sony                    | 67        | 0.69%   |
| InfoVision              | 59        | 0.61%   |
| MSI                     | 53        | 0.54%   |
| Sceptre Tech            | 52        | 0.53%   |
| Vizio                   | 44        | 0.45%   |
| Panasonic               | 41        | 0.42%   |
| Toshiba                 | 33        | 0.34%   |
| CSO                     | 31        | 0.32%   |
| Gigabyte Technology     | 26        | 0.27%   |
| Unknown                 | 25        | 0.26%   |
| Insignia                | 22        | 0.23%   |
| NEC Computers           | 21        | 0.22%   |
| Eizo                    | 20        | 0.21%   |
| Fujitsu Siemens         | 19        | 0.19%   |
| Hitachi                 | 18        | 0.18%   |
| Vestel Elektronik       | 17        | 0.17%   |
| LG Electronics          | 17        | 0.17%   |
| MStar                   | 15        | 0.15%   |
| HannStar                | 15        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 69        | 0.69%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 63        | 0.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 55        | 0.55%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 49        | 0.49%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 45        | 0.45%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch       | 45        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 43        | 0.43%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 39        | 0.39%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 35        | 0.35%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 34        | 0.34%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 30        | 0.3%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 28        | 0.28%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 28        | 0.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 26        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 26        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 26        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch        | 25        | 0.25%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 24        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch        | 24        | 0.24%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 23        | 0.23%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 23        | 0.23%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 23        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 21        | 0.21%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch        | 21        | 0.21%   |
| AOC 24G2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 21        | 0.21%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 20        | 0.2%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 20        | 0.2%    |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                      | 20        | 0.2%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch          | 20        | 0.2%    |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch           | 19        | 0.19%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 19        | 0.19%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 19        | 0.19%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                | 18        | 0.18%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch               | 18        | 0.18%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 18        | 0.18%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch       | 18        | 0.18%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 17        | 0.17%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch          | 17        | 0.17%   |
| AOC 24B1W AOC2401 1920x1080 521x293mm 23.5-inch                        | 17        | 0.17%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                | 16        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 4340      | 47.17%  |
| 1366x768 (WXGA)    | 1450      | 15.76%  |
| 3840x2160 (4K)     | 787       | 8.55%   |
| 2560x1440 (QHD)    | 552       | 6%      |
| 1600x900 (HD+)     | 294       | 3.2%    |
| 1920x1200 (WUXGA)  | 198       | 2.15%   |
| 1440x900 (WXGA+)   | 178       | 1.93%   |
| 1680x1050 (WSXGA+) | 176       | 1.91%   |
| 3440x1440          | 170       | 1.85%   |
| 2560x1080          | 168       | 1.83%   |
| 1280x1024 (SXGA)   | 157       | 1.71%   |
| 1280x800 (WXGA)    | 128       | 1.39%   |
| 2560x1600          | 88        | 0.96%   |
| 2880x1800          | 62        | 0.67%   |
| 1360x768           | 61        | 0.66%   |
| 1920x540           | 44        | 0.48%   |
| 3840x1080          | 41        | 0.45%   |
| 3840x2400          | 33        | 0.36%   |
| Unknown            | 33        | 0.36%   |
| 2160x1440          | 29        | 0.32%   |
| 3200x1800 (QHD+)   | 18        | 0.2%    |
| 2736x1824          | 18        | 0.2%    |
| 2256x1504          | 15        | 0.16%   |
| 3840x1600          | 14        | 0.15%   |
| 1600x1200          | 14        | 0.15%   |
| 1024x768 (XGA)     | 14        | 0.15%   |
| 3000x2000          | 13        | 0.14%   |
| 1280x720 (HD)      | 12        | 0.13%   |
| 3456x2160          | 6         | 0.07%   |
| 3200x2000          | 6         | 0.07%   |
| 3072x1920          | 6         | 0.07%   |
| 1920x1280          | 6         | 0.07%   |
| 2048x1152          | 5         | 0.05%   |
| 4480x1440          | 4         | 0.04%   |
| 3840x1200          | 4         | 0.04%   |
| 2288x1287          | 4         | 0.04%   |
| 3840x1100          | 3         | 0.03%   |
| 2560x1700          | 3         | 0.03%   |
| 2304x1440          | 3         | 0.03%   |
| 800x1280           | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2446      | 25.13%  |
| 13      | 964       | 9.9%    |
| 27      | 865       | 8.89%   |
| 24      | 744       | 7.64%   |
| 14      | 681       | 7%      |
| 23      | 612       | 6.29%   |
| 21      | 500       | 5.14%   |
| 17      | 489       | 5.02%   |
| 31      | 317       | 3.26%   |
| 34      | 288       | 2.96%   |
| 19      | 190       | 1.95%   |
| Unknown | 172       | 1.77%   |
| 18      | 152       | 1.56%   |
| 12      | 149       | 1.53%   |
| 22      | 121       | 1.24%   |
| 20      | 108       | 1.11%   |
| 84      | 100       | 1.03%   |
| 32      | 89        | 0.91%   |
| 11      | 78        | 0.8%    |
| 72      | 74        | 0.76%   |
| 16      | 73        | 0.75%   |
| 40      | 57        | 0.59%   |
| 54      | 43        | 0.44%   |
| 26      | 39        | 0.4%    |
| 25      | 37        | 0.38%   |
| 48      | 36        | 0.37%   |
| 35      | 26        | 0.27%   |
| 28      | 25        | 0.26%   |
| 49      | 24        | 0.25%   |
| 65      | 23        | 0.24%   |
| 52      | 23        | 0.24%   |
| 46      | 18        | 0.18%   |
| 29      | 17        | 0.17%   |
| 37      | 16        | 0.16%   |
| 36      | 14        | 0.14%   |
| 47      | 13        | 0.13%   |
| 33      | 13        | 0.13%   |
| 42      | 11        | 0.11%   |
| 74      | 9         | 0.09%   |
| 43      | 9         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3652      | 38.3%   |
| 501-600        | 2013      | 21.11%  |
| 401-500        | 963       | 10.1%   |
| 201-300        | 727       | 7.62%   |
| 351-400        | 598       | 6.27%   |
| 601-700        | 472       | 4.95%   |
| 701-800        | 396       | 4.15%   |
| 1001-1500      | 208       | 2.18%   |
| 1501-2000      | 190       | 1.99%   |
| Unknown        | 172       | 1.8%    |
| 801-900        | 114       | 1.2%    |
| 901-1000       | 25        | 0.26%   |
| More than 2000 | 2         | 0.02%   |
| 101-200        | 2         | 0.02%   |
| 1-100          | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 6816      | 79.61%  |
| 16/10   | 934       | 10.91%  |
| 21/9    | 343       | 4.01%   |
| 5/4     | 156       | 1.82%   |
| Unknown | 100       | 1.17%   |
| 3/2     | 92        | 1.07%   |
| 4/3     | 47        | 0.55%   |
| 32/9    | 46        | 0.54%   |
| 6/5     | 9         | 0.11%   |
| 1.96    | 5         | 0.06%   |
| 3.40    | 3         | 0.04%   |
| 3.20    | 3         | 0.04%   |
| 3.73    | 2         | 0.02%   |
| 0.62    | 2         | 0.02%   |
| 1.00    | 1         | 0.01%   |
| 0.67    | 1         | 0.01%   |
| 0.63    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2449      | 25.45%  |
| 201-250        | 1570      | 16.32%  |
| 81-90          | 1285      | 13.35%  |
| 301-350        | 889       | 9.24%   |
| 351-500        | 735       | 7.64%   |
| 151-200        | 444       | 4.61%   |
| 121-130        | 391       | 4.06%   |
| 71-80          | 372       | 3.87%   |
| More than 1000 | 324       | 3.37%   |
| 251-300        | 275       | 2.86%   |
| 501-1000       | 200       | 2.08%   |
| 141-150        | 195       | 2.03%   |
| Unknown        | 172       | 1.79%   |
| 61-70          | 125       | 1.3%    |
| 51-60          | 81        | 0.84%   |
| 111-120        | 58        | 0.6%    |
| 131-140        | 31        | 0.32%   |
| 91-100         | 16        | 0.17%   |
| 41-50          | 8         | 0.08%   |
| 1-40           | 3         | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2927      | 31.58%  |
| 121-160       | 2700      | 29.13%  |
| 101-120       | 2326      | 25.09%  |
| 161-240       | 583       | 6.29%   |
| More than 240 | 293       | 3.16%   |
| 1-50          | 268       | 2.89%   |
| Unknown       | 172       | 1.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 6607      | 74.63%  |
| 2     | 1611      | 18.2%   |
| 0     | 428       | 4.83%   |
| 3     | 190       | 2.15%   |
| 4     | 15        | 0.17%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4698      | 35.31%  |
| Intel                             | 4469      | 33.59%  |
| Qualcomm Atheros                  | 1408      | 10.58%  |
| Broadcom                          | 772       | 5.8%    |
| Broadcom Limited                  | 179       | 1.35%   |
| MediaTek                          | 161       | 1.21%   |
| TP-Link                           | 152       | 1.14%   |
| Ralink Technology                 | 141       | 1.06%   |
| Marvell Technology Group          | 128       | 0.96%   |
| Nvidia                            | 116       | 0.87%   |
| Ralink                            | 98        | 0.74%   |
| Samsung Electronics               | 78        | 0.59%   |
| Microsoft                         | 71        | 0.53%   |
| ASIX Electronics                  | 67        | 0.5%    |
| NetGear                           | 50        | 0.38%   |
| Xiaomi                            | 43        | 0.32%   |
| DisplayLink                       | 39        | 0.29%   |
| Qualcomm Atheros Communications   | 37        | 0.28%   |
| Google                            | 36        | 0.27%   |
| Aquantia                          | 34        | 0.26%   |
| InterBiometrics                   | 33        | 0.25%   |
| Dell                              | 29        | 0.22%   |
| D-Link                            | 29        | 0.22%   |
| Lenovo                            | 28        | 0.21%   |
| Huawei Technologies               | 28        | 0.21%   |
| ASUSTek Computer                  | 27        | 0.2%    |
| Qualcomm                          | 24        | 0.18%   |
| Sierra Wireless                   | 23        | 0.17%   |
| Ericsson Business Mobile Networks | 21        | 0.16%   |
| Linksys                           | 20        | 0.15%   |
| OnePlus Technology (Shenzhen)     | 19        | 0.14%   |
| JMicron Technology                | 18        | 0.14%   |
| Motorola PCS                      | 15        | 0.11%   |
| Edimax Technology                 | 15        | 0.11%   |
| D-Link System                     | 14        | 0.11%   |
| Hewlett-Packard                   | 13        | 0.1%    |
| OPPO Electronics                  | 11        | 0.08%   |
| Belkin Components                 | 10        | 0.08%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.07%   |
| Apple                             | 8         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3253      | 20.82%  |
| Intel Wi-Fi 6 AX200                                               | 689       | 4.41%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 460       | 2.94%   |
| Intel I211 Gigabit Network Connection                             | 397       | 2.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 298       | 1.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 266       | 1.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 266       | 1.7%    |
| Intel Wireless 8265 / 8275                                        | 264       | 1.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 247       | 1.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 210       | 1.34%   |
| Intel Wi-Fi 6 AX201                                               | 204       | 1.31%   |
| Intel Wireless 7265                                               | 193       | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 179       | 1.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 178       | 1.14%   |
| Intel Wireless 7260                                               | 177       | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 175       | 1.12%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 161       | 1.03%   |
| Intel Wireless 8260                                               | 159       | 1.02%   |
| Intel Wireless-AC 9260                                            | 153       | 0.98%   |
| Intel Ethernet Connection (2) I219-V                              | 149       | 0.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 143       | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 143       | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 142       | 0.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 140       | 0.9%    |
| Intel Ethernet Controller I225-V                                  | 136       | 0.87%   |
| Intel Ethernet Connection I217-LM                                 | 122       | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 111       | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 109       | 0.7%    |
| Intel Ethernet Connection (7) I219-V                              | 108       | 0.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 103       | 0.66%   |
| Intel Wireless 3165                                               | 99        | 0.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 90        | 0.58%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 88        | 0.56%   |
| Broadcom BCM43142 802.11b/g/n                                     | 83        | 0.53%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 82        | 0.52%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 78        | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 77        | 0.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 76        | 0.49%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 73        | 0.47%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 73        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3522      | 47.54%  |
| Realtek Semiconductor                 | 1114      | 15.04%  |
| Qualcomm Atheros                      | 1095      | 14.78%  |
| Broadcom                              | 591       | 7.98%   |
| MediaTek                              | 152       | 2.05%   |
| Ralink Technology                     | 141       | 1.9%    |
| TP-Link                               | 139       | 1.88%   |
| Broadcom Limited                      | 138       | 1.86%   |
| Ralink                                | 98        | 1.32%   |
| Microsoft                             | 66        | 0.89%   |
| NetGear                               | 48        | 0.65%   |
| Qualcomm Atheros Communications       | 37        | 0.5%    |
| Marvell Technology Group              | 34        | 0.46%   |
| D-Link                                | 28        | 0.38%   |
| Dell                                  | 26        | 0.35%   |
| ASUSTek Computer                      | 25        | 0.34%   |
| Sierra Wireless                       | 23        | 0.31%   |
| Qualcomm                              | 18        | 0.24%   |
| Linksys                               | 16        | 0.22%   |
| Edimax Technology                     | 15        | 0.2%    |
| D-Link System                         | 10        | 0.13%   |
| Belkin Components                     | 10        | 0.13%   |
| AVM                                   | 7         | 0.09%   |
| Sitecom Europe                        | 6         | 0.08%   |
| FIBOCOM                               | 6         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 6         | 0.08%   |
| Hewlett-Packard                       | 5         | 0.07%   |
| Gemtek                                | 5         | 0.07%   |
| Mercucys                              | 4         | 0.05%   |
| IMC Networks                          | 3         | 0.04%   |
| Accton Technology                     | 3         | 0.04%   |
| ZyDAS                                 | 2         | 0.03%   |
| Wilocity                              | 2         | 0.03%   |
| Samsung Electronics                   | 2         | 0.03%   |
| Ovislink                              | 2         | 0.03%   |
| Micro Star International              | 2         | 0.03%   |
| Wacom                                 | 1         | 0.01%   |
| TRENDnet                              | 1         | 0.01%   |
| Texas Instruments                     | 1         | 0.01%   |
| Philips (or NXP)                      | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 689       | 9.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 266       | 3.56%   |
| Intel Wireless 8265 / 8275                                     | 264       | 3.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 210       | 2.81%   |
| Intel Wi-Fi 6 AX201                                            | 204       | 2.73%   |
| Intel Wireless 7265                                            | 193       | 2.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 179       | 2.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 178       | 2.38%   |
| Intel Wireless 7260                                            | 177       | 2.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 175       | 2.34%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 161       | 2.16%   |
| Intel Wireless 8260                                            | 159       | 2.13%   |
| Intel Wireless-AC 9260                                         | 153       | 2.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 143       | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 143       | 1.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 142       | 1.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 140       | 1.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 111       | 1.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 109       | 1.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 103       | 1.38%   |
| Intel Wireless 3165                                            | 99        | 1.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 90        | 1.21%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 88        | 1.18%   |
| Broadcom BCM43142 802.11b/g/n                                  | 83        | 1.11%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 82        | 1.1%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 78        | 1.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 77        | 1.03%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 73        | 0.98%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 73        | 0.98%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 69        | 0.92%   |
| Realtek 802.11ac NIC                                           | 68        | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 67        | 0.9%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 65        | 0.87%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 62        | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 62        | 0.83%   |
| Intel Wireless 3160                                            | 59        | 0.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 58        | 0.78%   |
| Ralink MT7601U Wireless Adapter                                | 53        | 0.71%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 52        | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 51        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 4256      | 54.03%  |
| Intel                            | 2112      | 26.81%  |
| Qualcomm Atheros                 | 429       | 5.45%   |
| Broadcom                         | 318       | 4.04%   |
| Nvidia                           | 116       | 1.47%   |
| Marvell Technology Group         | 94        | 1.19%   |
| Samsung Electronics              | 76        | 0.96%   |
| ASIX Electronics                 | 67        | 0.85%   |
| Broadcom Limited                 | 45        | 0.57%   |
| Xiaomi                           | 43        | 0.55%   |
| DisplayLink                      | 39        | 0.5%    |
| Google                           | 36        | 0.46%   |
| Aquantia                         | 34        | 0.43%   |
| Lenovo                           | 28        | 0.36%   |
| Huawei Technologies              | 25        | 0.32%   |
| JMicron Technology               | 18        | 0.23%   |
| OnePlus Technology (Shenzhen)    | 15        | 0.19%   |
| TP-Link                          | 13        | 0.17%   |
| OPPO Electronics                 | 11        | 0.14%   |
| Motorola PCS                     | 11        | 0.14%   |
| Silicon Integrated Systems [SiS] | 9         | 0.11%   |
| MediaTek                         | 8         | 0.1%    |
| Qualcomm                         | 6         | 0.08%   |
| Apple                            | 6         | 0.08%   |
| VIA Technologies                 | 5         | 0.06%   |
| Microsoft                        | 5         | 0.06%   |
| ICS Advent                       | 5         | 0.06%   |
| Linksys                          | 4         | 0.05%   |
| D-Link System                    | 4         | 0.05%   |
| T & A Mobile Phones              | 3         | 0.04%   |
| Mellanox Technologies            | 3         | 0.04%   |
| LG Electronics                   | 3         | 0.04%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.03%   |
| NetGear                          | 2         | 0.03%   |
| LSI                              | 2         | 0.03%   |
| Hewlett-Packard                  | 2         | 0.03%   |
| ASUSTek Computer                 | 2         | 0.03%   |
| 3Com                             | 2         | 0.03%   |
| Tehuti Networks                  | 1         | 0.01%   |
| Solarflare Communications        | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3253      | 40.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 460       | 5.73%   |
| Intel I211 Gigabit Network Connection                             | 397       | 4.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 298       | 3.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 266       | 3.31%   |
| Realtek RTL8125 2.5GbE Controller                                 | 247       | 3.07%   |
| Intel Ethernet Connection (2) I219-V                              | 149       | 1.85%   |
| Intel Ethernet Controller I225-V                                  | 136       | 1.69%   |
| Intel Ethernet Connection I217-LM                                 | 122       | 1.52%   |
| Intel Ethernet Connection (7) I219-V                              | 108       | 1.34%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 76        | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 69        | 0.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 67        | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                             | 65        | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 57        | 0.71%   |
| Nvidia MCP79 Ethernet                                             | 56        | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 55        | 0.68%   |
| Intel 82579V Gigabit Network Connection                           | 55        | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 54        | 0.67%   |
| Intel Ethernet Connection I218-LM                                 | 52        | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 52        | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 50        | 0.62%   |
| Intel Ethernet Connection I217-V                                  | 49        | 0.61%   |
| Intel Ethernet Connection (2) I218-V                              | 45        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 44        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 43        | 0.54%   |
| Intel Ethernet Connection (3) I218-LM                             | 39        | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 36        | 0.45%   |
| Intel Ethernet Connection (4) I219-V                              | 36        | 0.45%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 36        | 0.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 36        | 0.45%   |
| Nvidia MCP61 Ethernet                                             | 35        | 0.44%   |
| Intel I210 Gigabit Network Connection                             | 34        | 0.42%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 33        | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                             | 33        | 0.41%   |
| Intel 82577LM Gigabit Network Connection                          | 33        | 0.41%   |
| Intel Ethernet Connection (6) I219-V                              | 32        | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 31        | 0.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 29        | 0.36%   |
| Google Nexus/Pixel Device (tether)                                | 27        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 7350      | 50.79%  |
| WiFi     | 7001      | 48.38%  |
| Modem    | 94        | 0.65%   |
| Unknown  | 27        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 5433      | 59.28%  |
| Ethernet | 3729      | 40.69%  |
| Unknown  | 3         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4827      | 55.62%  |
| 1     | 3495      | 40.27%  |
| 3     | 206       | 2.37%   |
| 0     | 110       | 1.27%   |
| 4     | 31        | 0.36%   |
| 5     | 5         | 0.06%   |
| 10    | 2         | 0.02%   |
| 6     | 2         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6916      | 78.76%  |
| Yes  | 1865      | 21.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3060      | 51.89%  |
| Realtek Semiconductor           | 471       | 7.99%   |
| Qualcomm Atheros Communications | 463       | 7.85%   |
| Apple                           | 342       | 5.8%    |
| Cambridge Silicon Radio         | 324       | 5.49%   |
| Broadcom                        | 252       | 4.27%   |
| IMC Networks                    | 229       | 3.88%   |
| Lite-On Technology              | 194       | 3.29%   |
| Foxconn / Hon Hai               | 138       | 2.34%   |
| ASUSTek Computer                | 99        | 1.68%   |
| Dell                            | 64        | 1.09%   |
| Marvell Semiconductor           | 36        | 0.61%   |
| Realtek                         | 31        | 0.53%   |
| Toshiba                         | 30        | 0.51%   |
| Ralink                          | 30        | 0.51%   |
| Hewlett-Packard                 | 30        | 0.51%   |
| MediaTek                        | 15        | 0.25%   |
| Foxconn International           | 11        | 0.19%   |
| TP-Link                         | 10        | 0.17%   |
| Ralink Technology               | 8         | 0.14%   |
| Dynex                           | 7         | 0.12%   |
| Alps Electric                   | 7         | 0.12%   |
| Smart Modular Technologies      | 4         | 0.07%   |
| HTC (High Tech Computer)        | 4         | 0.07%   |
| Askey Computer                  | 4         | 0.07%   |
| USI                             | 3         | 0.05%   |
| Taiyo Yuden                     | 3         | 0.05%   |
| SINO WEALTH                     | 3         | 0.05%   |
| Qcom                            | 3         | 0.05%   |
| Opticis                         | 3         | 0.05%   |
| Micro Star International        | 3         | 0.05%   |
| Integrated System Solution      | 3         | 0.05%   |
| Creative Technology             | 3         | 0.05%   |
| Fujitsu                         | 2         | 0.03%   |
| Conwise Technology              | 2         | 0.03%   |
| Belkin Components               | 2         | 0.03%   |
| Primax Electronics              | 1         | 0.02%   |
| Logitech                        | 1         | 0.02%   |
| Edimax Technology               | 1         | 0.02%   |
| Actions                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 918       | 15.55%  |
| Intel AX200 Bluetooth                               | 660       | 11.18%  |
| Intel AX201 Bluetooth                               | 527       | 8.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 427       | 7.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 324       | 5.49%   |
| Realtek Bluetooth Radio                             | 289       | 4.9%    |
| Qualcomm Atheros  Bluetooth Device                  | 255       | 4.32%   |
| Apple Bluetooth Host Controller                     | 173       | 2.93%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 144       | 2.44%   |
| Intel Wireless-AC 3168 Bluetooth                    | 138       | 2.34%   |
| Realtek  Bluetooth 4.2 Adapter                      | 125       | 2.12%   |
| Apple Bluetooth USB Host Controller                 | 97        | 1.64%   |
| Intel AX210 Bluetooth                               | 83        | 1.41%   |
| IMC Networks Bluetooth Radio                        | 74        | 1.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 71        | 1.2%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 69        | 1.17%   |
| Intel Bluetooth Device                              | 60        | 1.02%   |
| Foxconn / Hon Hai Bluetooth Device                  | 59        | 1%      |
| IMC Networks Wireless_Device                        | 58        | 0.98%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 56        | 0.95%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 53        | 0.9%    |
| IMC Networks Bluetooth Device                       | 51        | 0.86%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 45        | 0.76%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 45        | 0.76%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 44        | 0.75%   |
| Lite-On Bluetooth Device                            | 44        | 0.75%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 40        | 0.68%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 39        | 0.66%   |
| Foxconn / Hon Hai Wireless_Device                   | 35        | 0.59%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 32        | 0.54%   |
| Apple Bluetooth HCI                                 | 32        | 0.54%   |
| Realtek Bluetooth Radio                             | 31        | 0.53%   |
| Ralink RT3290 Bluetooth                             | 30        | 0.51%   |
| Broadcom BCM2045B (BDC-2.1)                         | 30        | 0.51%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 0.42%   |
| Marvell Bluetooth and Wireless LAN Composite        | 24        | 0.41%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 22        | 0.37%   |
| Dell DW375 Bluetooth Module                         | 22        | 0.37%   |
| Lite-On Atheros AR3012 Bluetooth                    | 21        | 0.36%   |
| ASUS Bluetooth Radio                                | 21        | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 5854      | 44.35%  |
| AMD                                             | 2944      | 22.3%   |
| Nvidia                                          | 2782      | 21.08%  |
| C-Media Electronics                             | 232       | 1.76%   |
| Logitech                                        | 133       | 1.01%   |
| JMTek                                           | 71        | 0.54%   |
| Creative Labs                                   | 66        | 0.5%    |
| Kingston Technology                             | 64        | 0.48%   |
| Razer USA                                       | 61        | 0.46%   |
| Corsair                                         | 61        | 0.46%   |
| Texas Instruments                               | 55        | 0.42%   |
| Realtek Semiconductor                           | 52        | 0.39%   |
| SteelSeries ApS                                 | 46        | 0.35%   |
| Focusrite-Novation                              | 43        | 0.33%   |
| ASUSTek Computer                                | 39        | 0.3%    |
| Generalplus Technology                          | 35        | 0.27%   |
| GN Netcom                                       | 33        | 0.25%   |
| Creative Technology                             | 31        | 0.23%   |
| Blue Microphones                                | 30        | 0.23%   |
| Sony                                            | 27        | 0.2%    |
| Lenovo                                          | 26        | 0.2%    |
| Plantronics                                     | 20        | 0.15%   |
| Apple                                           | 19        | 0.14%   |
| Micro Star International                        | 18        | 0.14%   |
| Astro Gaming                                    | 17        | 0.13%   |
| Giga-Byte Technology                            | 16        | 0.12%   |
| Samson Technologies                             | 15        | 0.11%   |
| Hewlett-Packard                                 | 15        | 0.11%   |
| Tenx Technology                                 | 14        | 0.11%   |
| Turtle Beach                                    | 13        | 0.1%    |
| FiiO Electronics Technology                     | 13        | 0.1%    |
| Yamaha                                          | 12        | 0.09%   |
| DSEA A/S                                        | 12        | 0.09%   |
| Sennheiser Communications                       | 11        | 0.08%   |
| SAVITECH                                        | 11        | 0.08%   |
| M-Audio                                         | 11        | 0.08%   |
| Valve Software                                  | 10        | 0.08%   |
| Thesycon Systemsoftware & Consulting            | 10        | 0.08%   |
| Silicon Integrated Systems [SiS]                | 10        | 0.08%   |
| Licensed by Sony Computer Entertainment America | 9         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 923       | 5.88%   |
| AMD Starship/Matisse HD Audio Controller                                   | 675       | 4.3%    |
| Intel Sunrise Point-LP HD Audio                                            | 655       | 4.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 559       | 3.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 535       | 3.41%   |
| Intel Cannon Lake PCH cAVS                                                 | 480       | 3.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 426       | 2.71%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 420       | 2.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 323       | 2.06%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 301       | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 267       | 1.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 262       | 1.67%   |
| Intel 8 Series HD Audio Controller                                         | 258       | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 255       | 1.62%   |
| Intel Haswell-ULT HD Audio Controller                                      | 254       | 1.62%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 252       | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                            | 236       | 1.5%    |
| Nvidia TU106 High Definition Audio Controller                              | 231       | 1.47%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 214       | 1.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 212       | 1.35%   |
| Intel Comet Lake PCH cAVS                                                  | 211       | 1.34%   |
| AMD FCH Azalia Controller                                                  | 211       | 1.34%   |
| Nvidia GP104 High Definition Audio Controller                              | 206       | 1.31%   |
| Nvidia TU116 High Definition Audio Controller                              | 187       | 1.19%   |
| Intel Broadwell-U Audio Controller                                         | 186       | 1.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 185       | 1.18%   |
| Nvidia GP106 High Definition Audio Controller                              | 183       | 1.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 182       | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                               | 178       | 1.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 177       | 1.13%   |
| Intel 200 Series PCH HD Audio                                              | 176       | 1.12%   |
| AMD Navi 10 HDMI Audio                                                     | 158       | 1.01%   |
| Nvidia GA104 High Definition Audio Controller                              | 151       | 0.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 147       | 0.94%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 138       | 0.88%   |
| Intel CM238 HD Audio Controller                                            | 135       | 0.86%   |
| Nvidia TU104 HD Audio Controller                                           | 129       | 0.82%   |
| Nvidia GA106 High Definition Audio Controller                              | 114       | 0.73%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 114       | 0.73%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 103       | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 545       | 23.42%  |
| SK hynix            | 419       | 18.01%  |
| Micron Technology   | 250       | 10.74%  |
| Kingston            | 244       | 10.49%  |
| Corsair             | 163       | 7%      |
| Crucial             | 153       | 6.57%   |
| Unknown             | 113       | 4.86%   |
| G.Skill             | 110       | 4.73%   |
| A-DATA Technology   | 53        | 2.28%   |
| Smart               | 31        | 1.33%   |
| Team                | 30        | 1.29%   |
| Ramaxel Technology  | 28        | 1.2%    |
| Goldkey             | 21        | 0.9%    |
| Elpida              | 21        | 0.9%    |
| Neo Forza           | 19        | 0.82%   |
| Unknown (ABCD)      | 14        | 0.6%    |
| Patriot             | 11        | 0.47%   |
| Unknown             | 11        | 0.47%   |
| Smart Brazil        | 10        | 0.43%   |
| Teikon              | 7         | 0.3%    |
| Nanya Technology    | 7         | 0.3%    |
| Apacer              | 6         | 0.26%   |
| Avant               | 5         | 0.21%   |
| Transcend           | 4         | 0.17%   |
| PNY                 | 4         | 0.17%   |
| Silicon Power       | 3         | 0.13%   |
| High Bridge         | 3         | 0.13%   |
| GSkill              | 3         | 0.13%   |
| GOODRAM             | 3         | 0.13%   |
| CSX                 | 3         | 0.13%   |
| Timetec             | 2         | 0.09%   |
| Patriot Memory      | 2         | 0.09%   |
| OLOY                | 2         | 0.09%   |
| Gold Key            | 2         | 0.09%   |
| ChangXin Memory     | 2         | 0.09%   |
| AMD                 | 2         | 0.09%   |
| Unknown (8A02)      | 1         | 0.04%   |
| Unknown (898F)      | 1         | 0.04%   |
| Unknown (09B6)      | 1         | 0.04%   |
| Unknown (09A4)      | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 40        | 1.64%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 30        | 1.23%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 28        | 1.15%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 25        | 1.02%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 20        | 0.82%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 20        | 0.82%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 19        | 0.78%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 18        | 0.74%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.7%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 17        | 0.7%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 0.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 17        | 0.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 17        | 0.7%    |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 15        | 0.61%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 0.57%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 0.57%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.57%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 0.53%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 13        | 0.53%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.49%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 12        | 0.49%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 12        | 0.49%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 12        | 0.49%   |
| Unknown                                                          | 11        | 0.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 10        | 0.41%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 10        | 0.41%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 10        | 0.41%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 10        | 0.41%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 10        | 0.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.37%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.37%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 9         | 0.37%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.37%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 9         | 0.37%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 9         | 0.37%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s        | 9         | 0.37%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.37%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 9         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1355      | 67.38%  |
| DDR3    | 398       | 19.79%  |
| LPDDR4  | 86        | 4.28%   |
| LPDDR3  | 71        | 3.53%   |
| DDR5    | 27        | 1.34%   |
| DDR2    | 23        | 1.14%   |
| Unknown | 20        | 0.99%   |
| LPDDR5  | 18        | 0.9%    |
| SDRAM   | 11        | 0.55%   |
| DDR     | 2         | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1246      | 61.32%  |
| DIMM         | 556       | 27.36%  |
| Row Of Chips | 214       | 10.53%  |
| Chip         | 13        | 0.64%   |
| Unknown      | 2         | 0.1%    |
| RIMM         | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 992       | 45.57%  |
| 4096  | 496       | 22.78%  |
| 16384 | 435       | 19.98%  |
| 32768 | 117       | 5.37%   |
| 2048  | 115       | 5.28%   |
| 1024  | 20        | 0.92%   |
| 512   | 2         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 460       | 21.14%  |
| 3200    | 453       | 20.82%  |
| 1600    | 280       | 12.87%  |
| 2400    | 189       | 8.69%   |
| 2133    | 116       | 5.33%   |
| 3600    | 104       | 4.78%   |
| 1333    | 73        | 3.35%   |
| 4267    | 46        | 2.11%   |
| 1867    | 44        | 2.02%   |
| 3266    | 30        | 1.38%   |
| 1334    | 29        | 1.33%   |
| 3000    | 26        | 1.19%   |
| 4800    | 24        | 1.1%    |
| 3400    | 24        | 1.1%    |
| 8400    | 20        | 0.92%   |
| 6400    | 19        | 0.87%   |
| 3466    | 19        | 0.87%   |
| 800     | 19        | 0.87%   |
| 3800    | 18        | 0.83%   |
| 3733    | 17        | 0.78%   |
| 3866    | 16        | 0.74%   |
| 2933    | 15        | 0.69%   |
| 4266    | 13        | 0.6%    |
| 1866    | 12        | 0.55%   |
| 1067    | 12        | 0.55%   |
| 667     | 11        | 0.51%   |
| 2800    | 9         | 0.41%   |
| 2666    | 8         | 0.37%   |
| Unknown | 8         | 0.37%   |
| 3666    | 5         | 0.23%   |
| 3534    | 5         | 0.23%   |
| 3333    | 5         | 0.23%   |
| 4400    | 4         | 0.18%   |
| 1800    | 4         | 0.18%   |
| 1066    | 4         | 0.18%   |
| 4000    | 3         | 0.14%   |
| 3100    | 3         | 0.14%   |
| 5200    | 2         | 0.09%   |
| 4199    | 2         | 0.09%   |
| 3533    | 2         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 55        | 31.98%  |
| Brother Industries    | 33        | 19.19%  |
| Canon                 | 26        | 15.12%  |
| Samsung Electronics   | 19        | 11.05%  |
| Seiko Epson           | 18        | 10.47%  |
| Dymo-CoStar           | 4         | 2.33%   |
| Fuji Xerox            | 3         | 1.74%   |
| Xerox                 | 2         | 1.16%   |
| STMicroelectronics    | 2         | 1.16%   |
| QinHeng Electronics   | 2         | 1.16%   |
| Prolific Technology   | 1         | 0.58%   |
| Oki Data              | 1         | 0.58%   |
| MIIIW                 | 1         | 0.58%   |
| Lexmark International | 1         | 0.58%   |
| Kyocera               | 1         | 0.58%   |
| ICS Advent            | 1         | 0.58%   |
| Dell                  | 1         | 0.58%   |
| Apple                 | 1         | 0.58%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| HP Deskjet 3050 J610 series                                | 5         | 2.89%   |
| Samsung M2020 Series                                       | 4         | 2.31%   |
| Seiko Epson ET-2700 Series                                 | 3         | 1.73%   |
| Samsung SCX-3400 Series                                    | 3         | 1.73%   |
| Samsung ML-1640 Series Laser Printer                       | 3         | 1.73%   |
| Canon PIXMA MX920 Series                                   | 3         | 1.73%   |
| Brother Printer                                            | 3         | 1.73%   |
| Brother HL-2270DW Laser Printer                            | 3         | 1.73%   |
| Brother HL-2130 series                                     | 3         | 1.73%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44  | 2         | 1.16%   |
| Seiko Epson WF-3520 Series                                 | 2         | 1.16%   |
| Seiko Epson L396 Series                                    | 2         | 1.16%   |
| Seiko Epson L355 Series                                    | 2         | 1.16%   |
| Seiko Epson L3110 Series                                   | 2         | 1.16%   |
| Samsung M2070 Series                                       | 2         | 1.16%   |
| QinHeng CH340S                                             | 2         | 1.16%   |
| HP OfficeJet 3830 series                                   | 2         | 1.16%   |
| HP LaserJet Professional P 1102w                           | 2         | 1.16%   |
| HP ENVY Photo 6200 series                                  | 2         | 1.16%   |
| HP ENVY 4520 series                                        | 2         | 1.16%   |
| HP ENVY 4500 series                                        | 2         | 1.16%   |
| HP DeskJet F4100 Printer series                            | 2         | 1.16%   |
| HP DeskJet 2600 series                                     | 2         | 1.16%   |
| HP Deskjet 2540 series                                     | 2         | 1.16%   |
| HP Deskjet 1000 J110 series                                | 2         | 1.16%   |
| Fuji Xerox DocuPrint CM315/318 z                           | 2         | 1.16%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                     | 2         | 1.16%   |
| Canon PIXMA MG2500 Series                                  | 2         | 1.16%   |
| Brother HL-L3230CDW series                                 | 2         | 1.16%   |
| Brother HL-1110 series                                     | 2         | 1.16%   |
| Xerox Phaser 6000B                                         | 1         | 0.58%   |
| Xerox B215                                                 | 1         | 0.58%   |
| Seiko Epson WF-4830 Series                                 | 1         | 0.58%   |
| Seiko Epson L365 Series                                    | 1         | 0.58%   |
| Seiko Epson L132 Series                                    | 1         | 0.58%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 0.58%   |
| Seiko Epson ET-3760 Series                                 | 1         | 0.58%   |
| Seiko Epson ET-3750 Series                                 | 1         | 0.58%   |
| Seiko Epson ET-2800 Series                                 | 1         | 0.58%   |
| Samsung SCX-4200 series                                    | 1         | 0.58%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 11        | 64.71%  |
| Seiko Epson     | 3         | 17.65%  |
| Hewlett-Packard | 2         | 11.76%  |
| Mustek Systems  | 1         | 5.88%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seiko Epson Scanner                    | 2         | 11.76%  |
| Canon CanoScan N1240U/LiDE 30          | 2         | 11.76%  |
| Canon CanoScan LiDE 210                | 2         | 11.76%  |
| Seiko Epson GT-X700 [Perfection 4870]  | 1         | 5.88%   |
| Mustek Systems ScanExpress 1200 UB     | 1         | 5.88%   |
| HP Scanjet 300                         | 1         | 5.88%   |
| HP ScanJet 2400c                       | 1         | 5.88%   |
| Canon CanoScan N650U/N656U             | 1         | 5.88%   |
| Canon CanoScan LiDE 60                 | 1         | 5.88%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1         | 5.88%   |
| Canon CanoScan LiDE 220                | 1         | 5.88%   |
| Canon CanoScan LiDE 200                | 1         | 5.88%   |
| Canon CanoScan LiDE 110                | 1         | 5.88%   |
| Canon CanoScan 9000F Mark II           | 1         | 5.88%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1093      | 20.88%  |
| IMC Networks                           | 493       | 9.42%   |
| Microdia                               | 488       | 9.32%   |
| Acer                                   | 415       | 7.93%   |
| Realtek Semiconductor                  | 390       | 7.45%   |
| Logitech                               | 354       | 6.76%   |
| Sunplus Innovation Technology          | 270       | 5.16%   |
| Apple                                  | 269       | 5.14%   |
| Quanta                                 | 233       | 4.45%   |
| Cheng Uei Precision Industry (Foxlink) | 162       | 3.09%   |
| Suyin                                  | 127       | 2.43%   |
| Syntek                                 | 121       | 2.31%   |
| Lite-On Technology                     | 99        | 1.89%   |
| Luxvisions Innotech Limited            | 66        | 1.26%   |
| Microsoft                              | 63        | 1.2%    |
| Silicon Motion                         | 61        | 1.17%   |
| Bison Electronics                      | 47        | 0.9%    |
| Samsung Electronics                    | 40        | 0.76%   |
| Ricoh                                  | 37        | 0.71%   |
| Alcor Micro                            | 32        | 0.61%   |
| Generalplus Technology                 | 25        | 0.48%   |
| Z-Star Microelectronics                | 20        | 0.38%   |
| Sonix Technology                       | 19        | 0.36%   |
| SunplusIT                              | 15        | 0.29%   |
| Razer USA                              | 15        | 0.29%   |
| ARC International                      | 15        | 0.29%   |
| MacroSilicon                           | 14        | 0.27%   |
| ALi                                    | 13        | 0.25%   |
| Primax Electronics                     | 11        | 0.21%   |
| Lenovo                                 | 10        | 0.19%   |
| KYE Systems (Mouse Systems)            | 10        | 0.19%   |
| Jieli Technology                       | 10        | 0.19%   |
| Intel                                  | 10        | 0.19%   |
| DigiTech                               | 10        | 0.19%   |
| Valve Software                         | 9         | 0.17%   |
| Importek                               | 9         | 0.17%   |
| Creative Technology                    | 9         | 0.17%   |
| AVerMedia Technologies                 | 8         | 0.15%   |
| LG Electronics                         | 7         | 0.13%   |
| OmniVision Technologies                | 6         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD           | 239       | 4.52%   |
| Chicony Integrated Camera               | 220       | 4.16%   |
| Realtek Integrated_Webcam_HD            | 160       | 3.03%   |
| IMC Networks USB2.0 HD UVC WebCam       | 160       | 3.03%   |
| IMC Networks Integrated Camera          | 145       | 2.74%   |
| Chicony HD Webcam                       | 131       | 2.48%   |
| Chicony USB2.0 Camera                   | 98        | 1.85%   |
| Acer BisonCam,NB Pro                    | 95        | 1.8%    |
| Apple Built-in iSight                   | 86        | 1.63%   |
| Acer Integrated Camera                  | 77        | 1.46%   |
| Syntek Integrated Camera                | 76        | 1.44%   |
| Logitech HD Pro Webcam C920             | 76        | 1.44%   |
| Sunplus Integrated_Webcam_HD            | 75        | 1.42%   |
| Logitech Webcam C270                    | 68        | 1.29%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 65        | 1.23%   |
| Apple FaceTime HD Camera                | 60        | 1.14%   |
| Acer HD Webcam                          | 54        | 1.02%   |
| Quanta HD User Facing                   | 53        | 1%      |
| IMC Networks USB2.0 VGA UVC WebCam      | 47        | 0.89%   |
| Apple FaceTime HD Camera (Built-in)     | 47        | 0.89%   |
| Acer BisonCam, NB Pro                   | 39        | 0.74%   |
| Samsung Galaxy A5 (MTP)                 | 37        | 0.7%    |
| Lite-On Integrated Camera               | 37        | 0.7%    |
| Chicony USB 2.0 Camera                  | 36        | 0.68%   |
| Chicony HP Wide Vision HD Camera        | 35        | 0.66%   |
| Microdia Integrated Webcam              | 34        | 0.64%   |
| Chicony HP HD Camera                    | 34        | 0.64%   |
| Logitech C922 Pro Stream Webcam         | 33        | 0.62%   |
| Chicony TOSHIBA Web Camera - HD         | 33        | 0.62%   |
| Chicony Integrated Camera (1280x720@30) | 33        | 0.62%   |
| Microdia Webcam Vitade AF               | 32        | 0.61%   |
| Chicony HD User Facing                  | 32        | 0.61%   |
| Sunplus HD WebCam                       | 31        | 0.59%   |
| Chicony USB2.0 HD UVC WebCam            | 30        | 0.57%   |
| Sunplus ASUS Webcam                     | 29        | 0.55%   |
| Microdia Laptop_Integrated_Webcam_HD    | 29        | 0.55%   |
| Acer SunplusIT Integrated Camera        | 29        | 0.55%   |
| Quanta HD Webcam                        | 28        | 0.53%   |
| Acer EasyCamera                         | 27        | 0.51%   |
| Realtek Integrated Webcam               | 26        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 314       | 33.12%  |
| Validity Sensors                   | 268       | 28.27%  |
| Shenzhen Goodix Technology         | 181       | 19.09%  |
| Elan Microelectronics              | 53        | 5.59%   |
| Upek                               | 46        | 4.85%   |
| LighTuning Technology              | 39        | 4.11%   |
| AuthenTec                          | 28        | 2.95%   |
| STMicroelectronics                 | 7         | 0.74%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.32%   |
| Focal-systems.Corp                 | 3         | 0.32%   |
| Samsung Electronics                | 2         | 0.21%   |
| HOLTEK                             | 2         | 0.21%   |
| DigitalPersona                     | 2         | 0.21%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 79        | 8.33%   |
| Shenzhen Goodix  Fingerprint Device                                        | 72        | 7.59%   |
| Shenzhen Goodix Fingerprint Reader                                         | 62        | 6.54%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 56        | 5.91%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 48        | 5.06%   |
| Synaptics UWP WBDI                                                         | 47        | 4.96%   |
| Shenzhen Goodix FingerPrint                                                | 47        | 4.96%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 42        | 4.43%   |
| Elan ELAN:Fingerprint                                                      | 37        | 3.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 35        | 3.69%   |
| Synaptics  WBDI                                                            | 23        | 2.43%   |
| Validity Sensors Synaptics WBDI                                            | 21        | 2.22%   |
| Validity Sensors Fingerprint scanner                                       | 20        | 2.11%   |
| Synaptics WBDI                                                             | 20        | 2.11%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 20        | 2.11%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 2%      |
| Validity Sensors VFS491                                                    | 18        | 1.9%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 18        | 1.9%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 18        | 1.9%    |
| Synaptics WBDI Device                                                      | 18        | 1.9%    |
| Unknown                                                                    | 16        | 1.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 15        | 1.58%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 15        | 1.58%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 15        | 1.58%   |
| Elan ELAN:ARM-M4                                                           | 14        | 1.48%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 12        | 1.27%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 1.16%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.16%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 9         | 0.95%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 0.95%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 0.95%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 8         | 0.84%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 0.74%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.74%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.74%   |
| AuthenTec AES2810                                                          | 7         | 0.74%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 0.63%   |
| Synaptics UWP WBDI Device                                                  | 5         | 0.53%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.42%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.42%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 153       | 45.4%   |
| Alcor Micro               | 89        | 26.41%  |
| Upek                      | 29        | 8.61%   |
| O2 Micro                  | 24        | 7.12%   |
| Lenovo                    | 19        | 5.64%   |
| SCM Microsystems          | 7         | 2.08%   |
| OmniKey                   | 5         | 1.48%   |
| Realtek Semiconductor     | 2         | 0.59%   |
| Gemalto (was Gemplus)     | 2         | 0.59%   |
| Aladdin Knowledge Systems | 2         | 0.59%   |
| Advanced Card Systems     | 2         | 0.59%   |
| Giesecke & Devrient       | 1         | 0.3%    |
| Clay Logic                | 1         | 0.3%    |
| Chicony Electronics       | 1         | 0.3%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 88        | 26.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 45        | 13.35%  |
| Broadcom 5880                                                                | 42        | 12.46%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 40        | 11.87%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 29        | 8.61%   |
| Broadcom 58200                                                               | 24        | 7.12%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 20        | 5.93%   |
| Lenovo Integrated Smart Card Reader                                          | 19        | 5.64%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 5         | 1.48%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.19%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.59%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.59%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.59%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.59%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.3%    |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.3%    |
| OmniKey CardMan 4321                                                         | 1         | 0.3%    |
| OmniKey CardMan 1021                                                         | 1         | 0.3%    |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.3%    |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.3%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.3%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.3%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.3%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.3%    |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.3%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.3%    |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.3%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 6082      | 68.98%  |
| 1     | 2237      | 25.37%  |
| 2     | 427       | 4.84%   |
| 3     | 60        | 0.68%   |
| 4     | 8         | 0.09%   |
| 5     | 2         | 0.02%   |
| 7     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 928       | 29.02%  |
| Net/wireless             | 555       | 17.35%  |
| Graphics card            | 545       | 17.04%  |
| Multimedia controller    | 372       | 11.63%  |
| Chipcard                 | 326       | 10.19%  |
| Bluetooth                | 85        | 2.66%   |
| Communication controller | 57        | 1.78%   |
| Camera                   | 57        | 1.78%   |
| Unassigned class         | 50        | 1.56%   |
| Sound                    | 49        | 1.53%   |
| Net/ethernet             | 42        | 1.31%   |
| Storage                  | 37        | 1.16%   |
| Card reader              | 23        | 0.72%   |
| Network                  | 22        | 0.69%   |
| Storage/raid             | 13        | 0.41%   |
| Storage/ide              | 11        | 0.34%   |
| Modem                    | 10        | 0.31%   |
| Storage/nvme             | 6         | 0.19%   |
| Firewire controller      | 4         | 0.13%   |
| Flash memory             | 2         | 0.06%   |
| Dvb card                 | 2         | 0.06%   |
| Wireless                 | 1         | 0.03%   |
| Unclassified device      | 1         | 0.03%   |

