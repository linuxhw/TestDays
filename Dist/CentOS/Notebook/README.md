CentOS - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for CentOS.

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

Total: 307

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ZHAN 66 Pro A 14 G3         | [249f2a954a](https://linux-hardware.org/?probe=249f2a954a) | Nov 02, 2023 |
| Dell          | Vostro 5402                 | [f23d8804a7](https://linux-hardware.org/?probe=f23d8804a7) | Oct 11, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [6ffee2798a](https://linux-hardware.org/?probe=6ffee2798a) | Sep 08, 2023 |
| HP            | ProBook 650 G1              | [b0f558c0a2](https://linux-hardware.org/?probe=b0f558c0a2) | Aug 31, 2023 |
| Dell          | Vostro 3558                 | [61cb58f13b](https://linux-hardware.org/?probe=61cb58f13b) | Aug 23, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [dfcebaef82](https://linux-hardware.org/?probe=dfcebaef82) | Aug 09, 2023 |
| HP            | ProBook 450 G3              | [90e7667180](https://linux-hardware.org/?probe=90e7667180) | Aug 02, 2023 |
| Dell          | System XPS L702X            | [21f1d68bc1](https://linux-hardware.org/?probe=21f1d68bc1) | Jul 21, 2023 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [61408603be](https://linux-hardware.org/?probe=61408603be) | Apr 21, 2023 |
| Lenovo        | ThinkPad T420 4178A4G       | [206861226d](https://linux-hardware.org/?probe=206861226d) | Apr 09, 2023 |
| Lenovo        | ThinkPad X260 20F5S1H800    | [752a80fb19](https://linux-hardware.org/?probe=752a80fb19) | Apr 03, 2023 |
| Acer          | Aspire 7750G                | [f99591fe95](https://linux-hardware.org/?probe=f99591fe95) | Mar 26, 2023 |
| ASUSTek       | N751JK                      | [d148f91b52](https://linux-hardware.org/?probe=d148f91b52) | Mar 15, 2023 |
| ASUSTek       | Q550LF                      | [793bf0d1d8](https://linux-hardware.org/?probe=793bf0d1d8) | Mar 06, 2023 |
| Acer          | Nitro AN515-54              | [56e5f689ab](https://linux-hardware.org/?probe=56e5f689ab) | Feb 06, 2023 |
| HP            | ProBook 650 G1              | [830394a75e](https://linux-hardware.org/?probe=830394a75e) | Jan 29, 2023 |
| ASUSTek       | N751JK                      | [a67a4d078f](https://linux-hardware.org/?probe=a67a4d078f) | Jan 21, 2023 |
| ASUSTek       | N751JK                      | [259556fd6f](https://linux-hardware.org/?probe=259556fd6f) | Jan 11, 2023 |
| Lenovo        | ThinkPad T430 2349JN0       | [fceb17b32c](https://linux-hardware.org/?probe=fceb17b32c) | Jan 10, 2023 |
| Lenovo        | ThinkPad T430 2349JN0       | [04a54f4c2f](https://linux-hardware.org/?probe=04a54f4c2f) | Jan 09, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [b9522e3683](https://linux-hardware.org/?probe=b9522e3683) | Jan 02, 2023 |
| Lenovo        | ThinkPad T430 2347DE9       | [7b4305ce5a](https://linux-hardware.org/?probe=7b4305ce5a) | Dec 27, 2022 |
| Lenovo        | ThinkPad T430 2347DE9       | [afc91c5da0](https://linux-hardware.org/?probe=afc91c5da0) | Dec 24, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [1b0b5a798f](https://linux-hardware.org/?probe=1b0b5a798f) | Dec 20, 2022 |
| LG Electro... | 15UD480-GX50K               | [16be4a033d](https://linux-hardware.org/?probe=16be4a033d) | Dec 19, 2022 |
| Lenovo        | ThinkPad X260 20F6007KKR    | [9b788f857e](https://linux-hardware.org/?probe=9b788f857e) | Dec 14, 2022 |
| Dell          | Precision 7720              | [5e8014cc1b](https://linux-hardware.org/?probe=5e8014cc1b) | Dec 08, 2022 |
| HONOR         | BBR-WAX9                    | [d7d701ca15](https://linux-hardware.org/?probe=d7d701ca15) | Dec 06, 2022 |
| Acer          | Swift SF314-512             | [b2aac5194c](https://linux-hardware.org/?probe=b2aac5194c) | Dec 06, 2022 |
| Dell          | XPS 15 9520                 | [b6cf92da13](https://linux-hardware.org/?probe=b6cf92da13) | Dec 02, 2022 |
| Panasonic     | CF-19ADNAXDY                | [51120805b1](https://linux-hardware.org/?probe=51120805b1) | Dec 02, 2022 |
| Panasonic     | CF-19ADNAXDY                | [7a809e9dbd](https://linux-hardware.org/?probe=7a809e9dbd) | Dec 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [b79b60e4b3](https://linux-hardware.org/?probe=b79b60e4b3) | Nov 28, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [b981adc21a](https://linux-hardware.org/?probe=b981adc21a) | Nov 07, 2022 |
| Dell          | Latitude E6230              | [da1e32759d](https://linux-hardware.org/?probe=da1e32759d) | Nov 05, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [8bd50f112b](https://linux-hardware.org/?probe=8bd50f112b) | Oct 15, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [88497baf29](https://linux-hardware.org/?probe=88497baf29) | Oct 15, 2022 |
| Acer          | Aspire E1-570G              | [2293724ae2](https://linux-hardware.org/?probe=2293724ae2) | Sep 19, 2022 |
| Acer          | Aspire E1-570G              | [09db514840](https://linux-hardware.org/?probe=09db514840) | Sep 19, 2022 |
| Lenovo        | ThinkPad T430 2349DG5       | [740898521d](https://linux-hardware.org/?probe=740898521d) | Aug 27, 2022 |
| Timi          | Mi NoteBook Horizon Edit... | [52a0cb298b](https://linux-hardware.org/?probe=52a0cb298b) | Aug 09, 2022 |
| Lenovo        | G410 20237                  | [daea3239f0](https://linux-hardware.org/?probe=daea3239f0) | Aug 05, 2022 |
| Acer          | Aspire E1-531               | [e9161d7c33](https://linux-hardware.org/?probe=e9161d7c33) | Jul 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [8bf06ee1c1](https://linux-hardware.org/?probe=8bf06ee1c1) | Jul 21, 2022 |
| ASUSTek       | X455LJ                      | [0c08648c4d](https://linux-hardware.org/?probe=0c08648c4d) | Jul 15, 2022 |
| ASUSTek       | G752VSK                     | [16e086c77f](https://linux-hardware.org/?probe=16e086c77f) | Jun 16, 2022 |
| Dell          | G3 3500                     | [3b770a574b](https://linux-hardware.org/?probe=3b770a574b) | Jun 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [29f2cd44d5](https://linux-hardware.org/?probe=29f2cd44d5) | Jun 11, 2022 |
| Dell          | Inspiron 3584               | [27ac9bc8f9](https://linux-hardware.org/?probe=27ac9bc8f9) | Jun 07, 2022 |
| Dell          | Inspiron 3584               | [7fdce576b4](https://linux-hardware.org/?probe=7fdce576b4) | Jun 07, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [4655b6a8ed](https://linux-hardware.org/?probe=4655b6a8ed) | Jun 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8120719b26](https://linux-hardware.org/?probe=8120719b26) | May 26, 2022 |
| HP            | ProBook 470 G2              | [9a331b90a5](https://linux-hardware.org/?probe=9a331b90a5) | May 19, 2022 |
| HP            | ProBook 470 G2              | [4c3a3b2de2](https://linux-hardware.org/?probe=4c3a3b2de2) | May 17, 2022 |
| MSI           | Katana GF76 12UE            | [460e78b93a](https://linux-hardware.org/?probe=460e78b93a) | May 15, 2022 |
| HP            | EliteBook 840 G3            | [a7fb96d9aa](https://linux-hardware.org/?probe=a7fb96d9aa) | May 13, 2022 |
| Dell          | Vostro 5581                 | [cdcb310766](https://linux-hardware.org/?probe=cdcb310766) | Apr 30, 2022 |
| Lenovo        | ThinkPad T61 64665WG        | [ac1bec6053](https://linux-hardware.org/?probe=ac1bec6053) | Apr 26, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | [228ec1a5f7](https://linux-hardware.org/?probe=228ec1a5f7) | Apr 24, 2022 |
| Lenovo        | ThinkPad X61s 7667DB2       | [34ae68d221](https://linux-hardware.org/?probe=34ae68d221) | Apr 05, 2022 |
| Timi          | RedmiBook 16                | [bef46c5065](https://linux-hardware.org/?probe=bef46c5065) | Mar 20, 2022 |
| Lenovo        | G580 20150                  | [1f84b1e42d](https://linux-hardware.org/?probe=1f84b1e42d) | Mar 11, 2022 |
| Dell          | Latitude 5591               | [0bc1368ac5](https://linux-hardware.org/?probe=0bc1368ac5) | Feb 28, 2022 |
| Lenovo        | ThinkPad T460s 20FAS5WX0... | [6fa180d5fa](https://linux-hardware.org/?probe=6fa180d5fa) | Feb 06, 2022 |
| HP            | EliteBook 840 G1            | [cf90d5430c](https://linux-hardware.org/?probe=cf90d5430c) | Feb 04, 2022 |
| Dell          | Latitude 3420               | [5690460ebd](https://linux-hardware.org/?probe=5690460ebd) | Jan 31, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [6db6689862](https://linux-hardware.org/?probe=6db6689862) | Jan 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [dfe95d1e0a](https://linux-hardware.org/?probe=dfe95d1e0a) | Jan 24, 2022 |
| Fujitsu       | LIFEBOOK E752               | [e6e4d232a9](https://linux-hardware.org/?probe=e6e4d232a9) | Jan 02, 2022 |
| MSI           | GP75 Leopard 10SFK          | [f165698d96](https://linux-hardware.org/?probe=f165698d96) | Dec 29, 2021 |
| Acer          | Aspire 3820                 | [195bb81f89](https://linux-hardware.org/?probe=195bb81f89) | Dec 28, 2021 |
| Acer          | Aspire 3820                 | [149083ba5f](https://linux-hardware.org/?probe=149083ba5f) | Dec 28, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d14a949e3d](https://linux-hardware.org/?probe=d14a949e3d) | Dec 27, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [3af644f11a](https://linux-hardware.org/?probe=3af644f11a) | Dec 26, 2021 |
| Dell          | Vostro 14 5410              | [ef6f4cf593](https://linux-hardware.org/?probe=ef6f4cf593) | Dec 05, 2021 |
| Dell          | Vostro 14 5410              | [6ab102bc84](https://linux-hardware.org/?probe=6ab102bc84) | Nov 30, 2021 |
| Dell          | Latitude E6430              | [a7435eb4c7](https://linux-hardware.org/?probe=a7435eb4c7) | Nov 28, 2021 |
| Dell          | Latitude 5590               | [d8b69c36bd](https://linux-hardware.org/?probe=d8b69c36bd) | Nov 23, 2021 |
| Lenovo        | ThinkPad E15 20RD0066TX     | [7443e6aedb](https://linux-hardware.org/?probe=7443e6aedb) | Nov 21, 2021 |
| ASUSTek       | N56VJ                       | [f39e92a1f3](https://linux-hardware.org/?probe=f39e92a1f3) | Nov 16, 2021 |
| Acer          | Aspire 5740                 | [0c661cb2d6](https://linux-hardware.org/?probe=0c661cb2d6) | Nov 12, 2021 |
| Lenovo        | ThinkPad T61 6457W35        | [87e69e1105](https://linux-hardware.org/?probe=87e69e1105) | Oct 26, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [60e26c388c](https://linux-hardware.org/?probe=60e26c388c) | Oct 17, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d0fb953c7e](https://linux-hardware.org/?probe=d0fb953c7e) | Oct 11, 2021 |
| Dell          | Latitude E6430              | [3d605c2c36](https://linux-hardware.org/?probe=3d605c2c36) | Oct 05, 2021 |
| HP            | EliteBook 8540w             | [a68000e142](https://linux-hardware.org/?probe=a68000e142) | Sep 26, 2021 |
| Dell          | Latitude E6530              | [41d65e59eb](https://linux-hardware.org/?probe=41d65e59eb) | Sep 26, 2021 |
| Dell          | Latitude E5470              | [17d97e59de](https://linux-hardware.org/?probe=17d97e59de) | Sep 23, 2021 |
| Dell          | Latitude E5470              | [82aca1d7b4](https://linux-hardware.org/?probe=82aca1d7b4) | Sep 16, 2021 |
| Dell          | Latitude E5470              | [c898d2b210](https://linux-hardware.org/?probe=c898d2b210) | Sep 16, 2021 |
| Apple         | MacBookPro5,5               | [d7ee29aac3](https://linux-hardware.org/?probe=d7ee29aac3) | Sep 15, 2021 |
| Sony          | SVT11215CGW                 | [0e12747ab1](https://linux-hardware.org/?probe=0e12747ab1) | Sep 12, 2021 |
| Dell          | Latitude 3420               | [1c1ef48be6](https://linux-hardware.org/?probe=1c1ef48be6) | Sep 06, 2021 |
| Dell          | Latitude E7450              | [090d2bd5c7](https://linux-hardware.org/?probe=090d2bd5c7) | Sep 05, 2021 |
| Dell          | Latitude E7450              | [c2d943414c](https://linux-hardware.org/?probe=c2d943414c) | Sep 04, 2021 |
| HP            | EliteBook 8540w             | [fd6f5273e3](https://linux-hardware.org/?probe=fd6f5273e3) | Sep 02, 2021 |
| HP            | EliteBook 2740p             | [0beccde57d](https://linux-hardware.org/?probe=0beccde57d) | Sep 01, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [9f3d5555ce](https://linux-hardware.org/?probe=9f3d5555ce) | Aug 26, 2021 |
| HP            | NOTEBOOKE 15-AY084TU        | [fe06a5029a](https://linux-hardware.org/?probe=fe06a5029a) | Aug 22, 2021 |
| HP            | EliteBook 8540w             | [6e6d5c8f2c](https://linux-hardware.org/?probe=6e6d5c8f2c) | Aug 20, 2021 |
| HP            | Presario C700               | [fa731abf46](https://linux-hardware.org/?probe=fa731abf46) | Aug 19, 2021 |
| Lenovo        | ThinkPad P50 20EN001PUS     | [38843da0aa](https://linux-hardware.org/?probe=38843da0aa) | Aug 18, 2021 |
| Lenovo        | ThinkPad P50 20EN001PUS     | [322b1fb2ba](https://linux-hardware.org/?probe=322b1fb2ba) | Aug 18, 2021 |
| Dell          | Latitude 7420               | [67165b9d66](https://linux-hardware.org/?probe=67165b9d66) | Aug 12, 2021 |
| Dell          | XPS 15 7590                 | [1778263a70](https://linux-hardware.org/?probe=1778263a70) | Aug 08, 2021 |
| Dell          | XPS 15 9570                 | [e329149eb4](https://linux-hardware.org/?probe=e329149eb4) | Aug 06, 2021 |
| HP            | EliteBook 8440p             | [80cb2748cf](https://linux-hardware.org/?probe=80cb2748cf) | Aug 02, 2021 |
| Acer          | Nitro AN515-51              | [130fff31f2](https://linux-hardware.org/?probe=130fff31f2) | Jul 12, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [8cf37f7d3d](https://linux-hardware.org/?probe=8cf37f7d3d) | Jul 11, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [3ec82c9dc0](https://linux-hardware.org/?probe=3ec82c9dc0) | Jul 11, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | [c0af3fd295](https://linux-hardware.org/?probe=c0af3fd295) | Jul 05, 2021 |
| COPELION I... | QX-350                      | [6fd40c02da](https://linux-hardware.org/?probe=6fd40c02da) | Jul 01, 2021 |
| HP            | EliteBook 820 G2            | [4993490f00](https://linux-hardware.org/?probe=4993490f00) | Jul 01, 2021 |
| HP            | EliteBook 820 G2            | [69346a0102](https://linux-hardware.org/?probe=69346a0102) | Jul 01, 2021 |
| ASUSTek       | X455LJ                      | [b8a939ca9c](https://linux-hardware.org/?probe=b8a939ca9c) | Jun 27, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | [32d294ba2a](https://linux-hardware.org/?probe=32d294ba2a) | Jun 23, 2021 |
| HP            | EliteBook 8740w             | [9b54339e9b](https://linux-hardware.org/?probe=9b54339e9b) | Jun 16, 2021 |
| HP            | EliteBook 8740w             | [9ad5884fca](https://linux-hardware.org/?probe=9ad5884fca) | Jun 16, 2021 |
| COPELION I... | QX-350                      | [7672d01a80](https://linux-hardware.org/?probe=7672d01a80) | Jun 08, 2021 |
| COPELION I... | QX-350                      | [4181e36f84](https://linux-hardware.org/?probe=4181e36f84) | Jun 07, 2021 |
| Dell          | Latitude E6530              | [eaf1c46fce](https://linux-hardware.org/?probe=eaf1c46fce) | May 29, 2021 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [5742c8e4e5](https://linux-hardware.org/?probe=5742c8e4e5) | May 28, 2021 |
| HP            | EliteBook 840 G5            | [ef516b4f37](https://linux-hardware.org/?probe=ef516b4f37) | May 17, 2021 |
| Lenovo        | ThinkPad W540 20BG001KUK    | [ce71038513](https://linux-hardware.org/?probe=ce71038513) | May 14, 2021 |
| Lenovo        | ThinkPad E490 20N8007NTX    | [e9efa41cf8](https://linux-hardware.org/?probe=e9efa41cf8) | May 12, 2021 |
| ASUSTek       | U35JC                       | [29ea6520a1](https://linux-hardware.org/?probe=29ea6520a1) | May 08, 2021 |
| Lenovo        | ThinkPad X200 7459ZEJ       | [a4f7ad5736](https://linux-hardware.org/?probe=a4f7ad5736) | May 07, 2021 |
| HP            | ZBook 15 G6                 | [ea363ea07e](https://linux-hardware.org/?probe=ea363ea07e) | May 07, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [1133f762f5](https://linux-hardware.org/?probe=1133f762f5) | Apr 15, 2021 |
| Dell          | Precision 3551              | [4e9b5b097e](https://linux-hardware.org/?probe=4e9b5b097e) | Apr 15, 2021 |
| Lenovo        | ThinkPad W540 20BHS20700    | [30edeadde3](https://linux-hardware.org/?probe=30edeadde3) | Apr 13, 2021 |
| Lenovo        | ThinkPad T460p 20FXS0220... | [3aef8ed384](https://linux-hardware.org/?probe=3aef8ed384) | Apr 11, 2021 |
| Lenovo        | ThinkPad E15 20RD0066TX     | [c3c1d01480](https://linux-hardware.org/?probe=c3c1d01480) | Apr 09, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [d4b7cef21b](https://linux-hardware.org/?probe=d4b7cef21b) | Apr 06, 2021 |
| HP            | ZBook 17 G2                 | [c974cb6fc7](https://linux-hardware.org/?probe=c974cb6fc7) | Apr 06, 2021 |
| Lenovo        | ThinkPad E15 20RD0066TX     | [3ab392c848](https://linux-hardware.org/?probe=3ab392c848) | Apr 05, 2021 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [4b9332ae3a](https://linux-hardware.org/?probe=4b9332ae3a) | Apr 05, 2021 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [d4a7fbec30](https://linux-hardware.org/?probe=d4a7fbec30) | Apr 01, 2021 |
| HP            | EliteBook 2540p             | [46c15e3b14](https://linux-hardware.org/?probe=46c15e3b14) | Apr 01, 2021 |
| LG Electro... | Z435-GE40K                  | [41dfc50f20](https://linux-hardware.org/?probe=41dfc50f20) | Mar 27, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | [72df2af331](https://linux-hardware.org/?probe=72df2af331) | Mar 16, 2021 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [ba68c7c065](https://linux-hardware.org/?probe=ba68c7c065) | Mar 09, 2021 |
| Dell          | Latitude E7250              | [551399bf55](https://linux-hardware.org/?probe=551399bf55) | Mar 08, 2021 |
| HP            | ProBook 6560b               | [57004cab16](https://linux-hardware.org/?probe=57004cab16) | Feb 17, 2021 |
| HP            | ProBook 450 G5              | [fcc71c0314](https://linux-hardware.org/?probe=fcc71c0314) | Feb 13, 2021 |
| Acer          | Aspire V5-571G              | [6f498cb661](https://linux-hardware.org/?probe=6f498cb661) | Jan 27, 2021 |
| ASUSTek       | K54C                        | [ac91a40e03](https://linux-hardware.org/?probe=ac91a40e03) | Jan 24, 2021 |
| Lenovo        | ThinkPad T520 4243Y1N       | [66b47b2f1e](https://linux-hardware.org/?probe=66b47b2f1e) | Jan 20, 2021 |
| Sony          | VPCEG15FB                   | [badcac9c3d](https://linux-hardware.org/?probe=badcac9c3d) | Jan 17, 2021 |
| HP            | EliteBook 840 G5            | [71b67a3764](https://linux-hardware.org/?probe=71b67a3764) | Jan 14, 2021 |
| Lenovo        | V330-15IKB 81AX             | [48d877b127](https://linux-hardware.org/?probe=48d877b127) | Jan 07, 2021 |
| Acer          | Aspire 5750G                | [a448a76b2e](https://linux-hardware.org/?probe=a448a76b2e) | Jan 06, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [1ad69ae9c9](https://linux-hardware.org/?probe=1ad69ae9c9) | Jan 04, 2021 |
| Dell          | XPS L521X                   | [c109644955](https://linux-hardware.org/?probe=c109644955) | Dec 28, 2020 |
| Dell          | Latitude E7240              | [39e57b6b18](https://linux-hardware.org/?probe=39e57b6b18) | Dec 28, 2020 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [7038da6d94](https://linux-hardware.org/?probe=7038da6d94) | Dec 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [55e2883ca5](https://linux-hardware.org/?probe=55e2883ca5) | Dec 24, 2020 |
| Lenovo        | ThinkPad T460p 20FXS0220... | [048b297665](https://linux-hardware.org/?probe=048b297665) | Dec 23, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | [d87cdee8cb](https://linux-hardware.org/?probe=d87cdee8cb) | Dec 19, 2020 |
| Acer          | Aspire E1-572               | [a06266ed7f](https://linux-hardware.org/?probe=a06266ed7f) | Dec 17, 2020 |
| ASUSTek       | X455LJ                      | [54683be664](https://linux-hardware.org/?probe=54683be664) | Dec 15, 2020 |
| Acer          | Aspire A715-75G             | [814f906095](https://linux-hardware.org/?probe=814f906095) | Dec 15, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [da43f75c0c](https://linux-hardware.org/?probe=da43f75c0c) | Dec 14, 2020 |
| ASUSTek       | X455LJ                      | [9938aa76cf](https://linux-hardware.org/?probe=9938aa76cf) | Dec 10, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | [9d12f4f222](https://linux-hardware.org/?probe=9d12f4f222) | Dec 10, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | [c26814bfc2](https://linux-hardware.org/?probe=c26814bfc2) | Dec 10, 2020 |
| Lenovo        | G70-70 80HW005XUK           | [a57125fe89](https://linux-hardware.org/?probe=a57125fe89) | Dec 07, 2020 |
| Acer          | Aspire V5-431P              | [831f0df544](https://linux-hardware.org/?probe=831f0df544) | Dec 03, 2020 |
| Dell          | Studio 1747                 | [dd0085228f](https://linux-hardware.org/?probe=dd0085228f) | Nov 29, 2020 |
| HP            | ZBook 15                    | [033521235f](https://linux-hardware.org/?probe=033521235f) | Nov 29, 2020 |
| Lenovo        | ThinkPad E595 20NF0000GE    | [c58ad8f5e8](https://linux-hardware.org/?probe=c58ad8f5e8) | Nov 28, 2020 |
| Toshiba       | Satellite A135              | [310ddb721f](https://linux-hardware.org/?probe=310ddb721f) | Nov 20, 2020 |
| Lenovo        | ThinkPad X240 20AMS7XW00    | [b7783af763](https://linux-hardware.org/?probe=b7783af763) | Nov 19, 2020 |
| Sony          | VPCEH15FX                   | [cc8c7bc4c9](https://linux-hardware.org/?probe=cc8c7bc4c9) | Nov 19, 2020 |
| Acer          | Aspire V5-571G              | [b8d43abe6e](https://linux-hardware.org/?probe=b8d43abe6e) | Nov 18, 2020 |
| Lenovo        | ThinkPad X200 7459H92       | [242193b8bc](https://linux-hardware.org/?probe=242193b8bc) | Nov 17, 2020 |
| Acer          | Aspire V5-571G              | [49707be15c](https://linux-hardware.org/?probe=49707be15c) | Nov 16, 2020 |
| Dell          | Latitude 3440               | [17db1f31f6](https://linux-hardware.org/?probe=17db1f31f6) | Nov 13, 2020 |
| HP            | EliteBook 830 G6            | [0e0009bcfc](https://linux-hardware.org/?probe=0e0009bcfc) | Nov 13, 2020 |
| Lenovo        | ThinkPad T420 4238AB9       | [9c7ec388e0](https://linux-hardware.org/?probe=9c7ec388e0) | Nov 11, 2020 |
| ASUSTek       | X455LJ                      | [d0085b85ad](https://linux-hardware.org/?probe=d0085b85ad) | Nov 09, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [dbc5336b07](https://linux-hardware.org/?probe=dbc5336b07) | Nov 01, 2020 |
| Lenovo        | ThinkPad E590 20NBS03S00    | [29ae827508](https://linux-hardware.org/?probe=29ae827508) | Oct 29, 2020 |
| Dell          | Latitude E6440              | [46a2699a96](https://linux-hardware.org/?probe=46a2699a96) | Oct 21, 2020 |
| Unknown       | Unknown                     | [98cd8695de](https://linux-hardware.org/?probe=98cd8695de) | Oct 21, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [97a2b45d12](https://linux-hardware.org/?probe=97a2b45d12) | Oct 21, 2020 |
| Unknown       | Unknown                     | [a0e3328769](https://linux-hardware.org/?probe=a0e3328769) | Oct 21, 2020 |
| Dell          | Latitude E6410              | [926bbbdaf2](https://linux-hardware.org/?probe=926bbbdaf2) | Oct 18, 2020 |
| Lenovo        | G500s 20245                 | [8a975cb577](https://linux-hardware.org/?probe=8a975cb577) | Oct 07, 2020 |
| Dell          | Latitude E6410              | [a36dab9e9b](https://linux-hardware.org/?probe=a36dab9e9b) | Oct 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [50534bc0e0](https://linux-hardware.org/?probe=50534bc0e0) | Oct 01, 2020 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [b00098bf37](https://linux-hardware.org/?probe=b00098bf37) | Sep 29, 2020 |
| ASUSTek       | X556UB                      | [15790fbe92](https://linux-hardware.org/?probe=15790fbe92) | Sep 28, 2020 |
| Timi          | TM1709                      | [9d4bd50d80](https://linux-hardware.org/?probe=9d4bd50d80) | Sep 25, 2020 |
| Gigabyte      | P35V3                       | [55580f63c2](https://linux-hardware.org/?probe=55580f63c2) | Sep 14, 2020 |
| Apple         | MacBookPro12,1              | [daceea1b39](https://linux-hardware.org/?probe=daceea1b39) | Sep 08, 2020 |
| Dell          | Inspiron 3542               | [233a83b315](https://linux-hardware.org/?probe=233a83b315) | Sep 08, 2020 |
| Dell          | Inspiron 3542               | [fcb2182f02](https://linux-hardware.org/?probe=fcb2182f02) | Sep 08, 2020 |
| Unknown       | 34AS1                       | [cc188d0f25](https://linux-hardware.org/?probe=cc188d0f25) | Sep 08, 2020 |
| Unknown       | 34AS1                       | [0ab59553ea](https://linux-hardware.org/?probe=0ab59553ea) | Sep 08, 2020 |
| Dell          | Inspiron 3542               | [751df6a75b](https://linux-hardware.org/?probe=751df6a75b) | Sep 08, 2020 |
| Dell          | Inspiron 3542               | [14680221b6](https://linux-hardware.org/?probe=14680221b6) | Sep 07, 2020 |
| HP            | EliteBook 6930p             | [8fdba744ec](https://linux-hardware.org/?probe=8fdba744ec) | Sep 03, 2020 |
| Dell          | Inspiron 5567               | [d7700d73c4](https://linux-hardware.org/?probe=d7700d73c4) | Sep 03, 2020 |
| ASUSTek       | 1001HA                      | [7935f0bc4a](https://linux-hardware.org/?probe=7935f0bc4a) | Aug 23, 2020 |
| Lenovo        | ThinkPad T430s 2356CZ4      | [585b5cd200](https://linux-hardware.org/?probe=585b5cd200) | Aug 22, 2020 |
| Lenovo        | ThinkPad T430s 2356CZ4      | [b16e78abbf](https://linux-hardware.org/?probe=b16e78abbf) | Aug 21, 2020 |
| Dell          | Inspiron N4050              | [c51c0d5538](https://linux-hardware.org/?probe=c51c0d5538) | Aug 15, 2020 |
| HP            | ProBook 440 G2              | [b19e6b64a7](https://linux-hardware.org/?probe=b19e6b64a7) | Aug 07, 2020 |
| MSI           | GE73VR 7RF                  | [8f05f68c7d](https://linux-hardware.org/?probe=8f05f68c7d) | Aug 04, 2020 |
| HP            | Notebook                    | [00a853f189](https://linux-hardware.org/?probe=00a853f189) | Aug 01, 2020 |
| Samsung       | 270E5J/2570EJ               | [8907cdddd5](https://linux-hardware.org/?probe=8907cdddd5) | Jul 24, 2020 |
| Samsung       | R560                        | [4d35b24594](https://linux-hardware.org/?probe=4d35b24594) | Jul 23, 2020 |
| HP            | EliteBook 850 G3            | [529b5be1b5](https://linux-hardware.org/?probe=529b5be1b5) | Jul 14, 2020 |
| HP            | ProBook 640 G2              | [53ba25afcd](https://linux-hardware.org/?probe=53ba25afcd) | Jul 14, 2020 |
| HP            | ProBook 450 G0              | [8566dd2843](https://linux-hardware.org/?probe=8566dd2843) | Jul 11, 2020 |
| HP            | ProBook 450 G0              | [116cbdcf22](https://linux-hardware.org/?probe=116cbdcf22) | Jul 09, 2020 |
| HP            | Falco                       | [26ace050f7](https://linux-hardware.org/?probe=26ace050f7) | Jul 07, 2020 |
| Dell          | Inspiron N4050              | [2a05830be5](https://linux-hardware.org/?probe=2a05830be5) | Jul 05, 2020 |
| HP            | EliteBook 840 G5            | [8c28479e2e](https://linux-hardware.org/?probe=8c28479e2e) | Jun 19, 2020 |
| HP            | Laptop 14-bp0xx             | [6efe053f69](https://linux-hardware.org/?probe=6efe053f69) | Jun 18, 2020 |
| HP            | Laptop 14-bp0xx             | [e1611d4a8f](https://linux-hardware.org/?probe=e1611d4a8f) | Jun 18, 2020 |
| Lenovo        | Z50-70 20354                | [765261db4d](https://linux-hardware.org/?probe=765261db4d) | Jun 17, 2020 |
| Lenovo        | Z50-70 20354                | [08a9f86f96](https://linux-hardware.org/?probe=08a9f86f96) | Jun 17, 2020 |
| Dell          | Inspiron 5570               | [3d59a7abfb](https://linux-hardware.org/?probe=3d59a7abfb) | Jun 14, 2020 |
| Dell          | Inspiron 3520               | [0fe6cc7ec2](https://linux-hardware.org/?probe=0fe6cc7ec2) | Jun 11, 2020 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [4660651265](https://linux-hardware.org/?probe=4660651265) | Jun 09, 2020 |
| HP            | EliteBook 840 G5            | [2605330e8c](https://linux-hardware.org/?probe=2605330e8c) | Jun 04, 2020 |
| Sony          | VPCEG15FB                   | [764c88fff0](https://linux-hardware.org/?probe=764c88fff0) | May 30, 2020 |
| HP            | EliteBook 8440p             | [cc3e01ff0f](https://linux-hardware.org/?probe=cc3e01ff0f) | May 29, 2020 |
| Lenovo        | ThinkPad E580 20KS001JRT    | [a9b9b6f30e](https://linux-hardware.org/?probe=a9b9b6f30e) | May 29, 2020 |
| Acer          | Aspire 5750G                | [e99f24b527](https://linux-hardware.org/?probe=e99f24b527) | May 15, 2020 |
| HP            | EliteBook 840 G5            | [912c44b0ac](https://linux-hardware.org/?probe=912c44b0ac) | May 15, 2020 |
| Acer          | Aspire 5750G                | [1f49c0d636](https://linux-hardware.org/?probe=1f49c0d636) | May 06, 2020 |
| Dell          | Latitude E6220              | [a4db1d31a5](https://linux-hardware.org/?probe=a4db1d31a5) | May 05, 2020 |
| Dell          | Latitude E6220              | [c0152a3b02](https://linux-hardware.org/?probe=c0152a3b02) | May 05, 2020 |
| Toshiba       | Satellite Radius 12 P20W... | [4f272f1c99](https://linux-hardware.org/?probe=4f272f1c99) | May 03, 2020 |
| ASUSTek       | X556UB                      | [ae412b00e1](https://linux-hardware.org/?probe=ae412b00e1) | May 02, 2020 |
| HP            | EliteBook 8440p             | [5856d8fd4a](https://linux-hardware.org/?probe=5856d8fd4a) | Apr 30, 2020 |
| Medion        | P6622                       | [57721ffc8f](https://linux-hardware.org/?probe=57721ffc8f) | Apr 29, 2020 |
| Dell          | Inspiron 5437               | [0606d60ddb](https://linux-hardware.org/?probe=0606d60ddb) | Apr 29, 2020 |
| Dell          | Inspiron 5437               | [c4f288077d](https://linux-hardware.org/?probe=c4f288077d) | Apr 29, 2020 |
| HP            | Laptop 14-dq1xxx            | [16dbe6c7cf](https://linux-hardware.org/?probe=16dbe6c7cf) | Apr 28, 2020 |
| Dell          | Precision 7510              | [40e5c33fd8](https://linux-hardware.org/?probe=40e5c33fd8) | Apr 27, 2020 |
| Lenovo        | ThinkPad T500 2242CTO       | [8d383c8ba6](https://linux-hardware.org/?probe=8d383c8ba6) | Apr 25, 2020 |
| Lenovo        | ThinkPad T500 2242CTO       | [82c9bdc55a](https://linux-hardware.org/?probe=82c9bdc55a) | Apr 25, 2020 |
| Dell          | Inspiron 3520               | [30d580cc9d](https://linux-hardware.org/?probe=30d580cc9d) | Apr 23, 2020 |
| Dell          | Inspiron 3520               | [e18488f436](https://linux-hardware.org/?probe=e18488f436) | Apr 23, 2020 |
| Sony          | VGN-N19VP_B                 | [a2e6c99940](https://linux-hardware.org/?probe=a2e6c99940) | Apr 20, 2020 |
| Apple         | MacBookPro12,1              | [bf90b17b91](https://linux-hardware.org/?probe=bf90b17b91) | Apr 15, 2020 |
| Lenovo        | ThinkPad T440 20B7004JUS    | [7e54937ed3](https://linux-hardware.org/?probe=7e54937ed3) | Apr 15, 2020 |
| Apple         | MacBookPro12,1              | [e3673127d2](https://linux-hardware.org/?probe=e3673127d2) | Apr 14, 2020 |
| HP            | EliteBook Folio 9470m       | [9439de5a1c](https://linux-hardware.org/?probe=9439de5a1c) | Apr 12, 2020 |
| RM Educati... | RM                          | [548492cfc9](https://linux-hardware.org/?probe=548492cfc9) | Apr 11, 2020 |
| HP            | ProBook 430 G5              | [a1f59e373b](https://linux-hardware.org/?probe=a1f59e373b) | Apr 10, 2020 |
| Lenovo        | Z50-70 20354                | [03322f98e6](https://linux-hardware.org/?probe=03322f98e6) | Mar 24, 2020 |
| Lenovo        | B50-70 80EU                 | [32162d2fcb](https://linux-hardware.org/?probe=32162d2fcb) | Mar 19, 2020 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | [2918602e15](https://linux-hardware.org/?probe=2918602e15) | Mar 12, 2020 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | [8376f889c2](https://linux-hardware.org/?probe=8376f889c2) | Mar 12, 2020 |
| HP            | Laptop 15-da0xxx            | [d2ab3b608a](https://linux-hardware.org/?probe=d2ab3b608a) | Mar 07, 2020 |
| Acer          | One 14 Z2-485               | [d7c11b1573](https://linux-hardware.org/?probe=d7c11b1573) | Feb 24, 2020 |
| Acer          | One 14 Z2-485               | [22a7ce37ed](https://linux-hardware.org/?probe=22a7ce37ed) | Feb 24, 2020 |
| HP            | EliteBook 8570w             | [f2997e7cab](https://linux-hardware.org/?probe=f2997e7cab) | Feb 24, 2020 |
| HP            | ProBook 450 G5              | [d38140cd66](https://linux-hardware.org/?probe=d38140cd66) | Feb 24, 2020 |
| HP            | ProBook 450 G5              | [7d51d0400f](https://linux-hardware.org/?probe=7d51d0400f) | Feb 24, 2020 |
| Dell          | Precision 5510              | [97fdd683cd](https://linux-hardware.org/?probe=97fdd683cd) | Feb 23, 2020 |
| HP            | ZBook 17                    | [5937f48c97](https://linux-hardware.org/?probe=5937f48c97) | Feb 13, 2020 |
| HP            | Laptop 15-bs1xx             | [891cb66753](https://linux-hardware.org/?probe=891cb66753) | Feb 06, 2020 |
| Sony          | VPCSB19GG                   | [cc8806b4ec](https://linux-hardware.org/?probe=cc8806b4ec) | Feb 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [10a7b3c4f3](https://linux-hardware.org/?probe=10a7b3c4f3) | Feb 01, 2020 |
| Acer          | TravelMate P257-M           | [5dbe9649a7](https://linux-hardware.org/?probe=5dbe9649a7) | Jan 28, 2020 |
| Clevo         | P15xEMx                     | [e41e485e3b](https://linux-hardware.org/?probe=e41e485e3b) | Jan 25, 2020 |
| ASUSTek       | X550MJ                      | [16470618ab](https://linux-hardware.org/?probe=16470618ab) | Jan 09, 2020 |
| Dell          | Inspiron N4010              | [5b5d5fc395](https://linux-hardware.org/?probe=5b5d5fc395) | Jan 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [95488c6be1](https://linux-hardware.org/?probe=95488c6be1) | Jan 02, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [925412ddcd](https://linux-hardware.org/?probe=925412ddcd) | Jan 02, 2020 |
| HP            | EliteBook x360 1040 G6      | [7d1585f3cd](https://linux-hardware.org/?probe=7d1585f3cd) | Dec 28, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | [e795735d5b](https://linux-hardware.org/?probe=e795735d5b) | Dec 14, 2019 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | [46bfb60272](https://linux-hardware.org/?probe=46bfb60272) | Dec 14, 2019 |
| Dell          | Studio 1747                 | [e572489472](https://linux-hardware.org/?probe=e572489472) | Dec 05, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [1bb0047e0e](https://linux-hardware.org/?probe=1bb0047e0e) | Dec 03, 2019 |
| Dell          | System XPS L702X            | [ba096189bc](https://linux-hardware.org/?probe=ba096189bc) | Dec 03, 2019 |
| Toshiba       | Satellite L15W-B            | [c90b14d1e5](https://linux-hardware.org/?probe=c90b14d1e5) | Dec 03, 2019 |
| Dell          | Studio 1747                 | [24d64d118b](https://linux-hardware.org/?probe=24d64d118b) | Dec 02, 2019 |
| MSI           | GL63 8SD                    | [3cef0087aa](https://linux-hardware.org/?probe=3cef0087aa) | Dec 01, 2019 |
| ASUSTek       | E202SA                      | [e052cf247b](https://linux-hardware.org/?probe=e052cf247b) | Nov 23, 2019 |
| Toshiba       | Satellite L15W-B            | [c96da5df5e](https://linux-hardware.org/?probe=c96da5df5e) | Nov 20, 2019 |
| Toshiba       | Satellite L15W-B            | [bf3a6bb4c3](https://linux-hardware.org/?probe=bf3a6bb4c3) | Nov 20, 2019 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [df76fe3ea4](https://linux-hardware.org/?probe=df76fe3ea4) | Nov 14, 2019 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [448a81eb7c](https://linux-hardware.org/?probe=448a81eb7c) | Nov 14, 2019 |
| HP            | Notebook                    | [4aae147ff7](https://linux-hardware.org/?probe=4aae147ff7) | Nov 01, 2019 |
| Sony          | VPCEH26EN                   | [28024462ac](https://linux-hardware.org/?probe=28024462ac) | Oct 22, 2019 |
| Dell          | Vostro 5568                 | [a0b3e4d70f](https://linux-hardware.org/?probe=a0b3e4d70f) | Oct 16, 2019 |
| RM Educati... | RM                          | [4d22671841](https://linux-hardware.org/?probe=4d22671841) | Oct 03, 2019 |
| RM Educati... | RM                          | [43aad9067d](https://linux-hardware.org/?probe=43aad9067d) | Oct 02, 2019 |
| HP            | Pavilion 15                 | [7e407e7cd4](https://linux-hardware.org/?probe=7e407e7cd4) | Sep 15, 2019 |
| HP            | Pavilion 15                 | [447f75484c](https://linux-hardware.org/?probe=447f75484c) | Sep 11, 2019 |
| HP            | Pavilion 15                 | [9352d1efae](https://linux-hardware.org/?probe=9352d1efae) | Sep 11, 2019 |
| MSI           | GP62MVR 7RFX                | [5a21834bbd](https://linux-hardware.org/?probe=5a21834bbd) | Sep 01, 2019 |
| Notebook      | WA50SRQ                     | [fd99d2b5e2](https://linux-hardware.org/?probe=fd99d2b5e2) | Aug 09, 2019 |
| Dell          | Precision M4600             | [9b9a3a238d](https://linux-hardware.org/?probe=9b9a3a238d) | Apr 14, 2019 |
| Dell          | Vostro 5470                 | [e106741644](https://linux-hardware.org/?probe=e106741644) | Apr 10, 2019 |
| ASUSTek       | X540SC                      | [f513215ec6](https://linux-hardware.org/?probe=f513215ec6) | Jan 09, 2019 |
| Lenovo        | ThinkPad T440p 20AWS27B0... | [000dae069a](https://linux-hardware.org/?probe=000dae069a) | Oct 31, 2018 |
| Lenovo        | ThinkPad T530 2394AG6       | [6b8015f1e2](https://linux-hardware.org/?probe=6b8015f1e2) | Oct 26, 2018 |
| Lenovo        | ThinkPad T530 2394AG6       | [c834cadf29](https://linux-hardware.org/?probe=c834cadf29) | Oct 26, 2018 |
| HP            | EliteBook 2740p             | [1b72dbb418](https://linux-hardware.org/?probe=1b72dbb418) | Sep 17, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| CentOS 8      | 119       | 53.6%   |
| CentOS 7      | 72        | 32.43%  |
| CentOS 9      | 23        | 10.36%  |
| CentOS Stream | 7         | 3.15%   |
| CentOS 6      | 1         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| CentOS | 220       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.18.0-147.8.1.el8_1.x86_64  | 11        | 4.66%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 9         | 3.81%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 8         | 3.39%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 7         | 2.97%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 7         | 2.97%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 6         | 2.54%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 5         | 2.12%   |
| 4.18.0-193.14.2.el8_2.x86_64 | 5         | 2.12%   |
| 4.18.0-305.3.1.el8.x86_64    | 4         | 1.69%   |
| 4.18.0-294.el8.x86_64        | 4         | 1.69%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 4         | 1.69%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 4         | 1.69%   |
| 4.18.0-408.el8.x86_64        | 3         | 1.27%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 3         | 1.27%   |
| 4.18.0-338.el8.x86_64        | 3         | 1.27%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 3         | 1.27%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 3         | 1.27%   |
| 4.18.0-277.el8.x86_64        | 3         | 1.27%   |
| 4.18.0-240.el8.x86_64        | 3         | 1.27%   |
| 4.18.0-193.el8.x86_64        | 3         | 1.27%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 3         | 1.27%   |
| 4.18.0-147.6.el8.x86_64      | 3         | 1.27%   |
| 3.10.0-957.27.2.el7.x86_64   | 3         | 1.27%   |
| 3.10.0-957.10.1.el7.x86_64   | 3         | 1.27%   |
| 3.10.0-1160.80.1.el7.x86_64  | 3         | 1.27%   |
| 3.10.0-1160.66.1.el7.x86_64  | 3         | 1.27%   |
| 3.10.0-1160.15.2.el7.x86_64  | 3         | 1.27%   |
| 3.10.0-1127.19.1.el7.x86_64  | 3         | 1.27%   |
| 5.15.11-1.el8.elrepo.x86_64  | 2         | 0.85%   |
| 5.14.0-86.el9.x86_64         | 2         | 0.85%   |
| 5.14.0-134.el9.x86_64        | 2         | 0.85%   |
| 4.18.0-80.el8.x86_64         | 2         | 0.85%   |
| 4.18.0-348.el8.x86_64        | 2         | 0.85%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 2         | 0.85%   |
| 4.18.0-301.1.el8.x86_64      | 2         | 0.85%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 2         | 0.85%   |
| 4.18.0-147.el8.x86_64        | 2         | 0.85%   |
| 3.10.0-957.el7.x86_64        | 2         | 0.85%   |
| 3.10.0-957.1.3.el7.x86_64    | 2         | 0.85%   |
| 3.10.0-862.14.4.el7.x86_64   | 2         | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 117       | 52.23%  |
| 3.10.0  | 63        | 28.13%  |
| 5.14.0  | 22        | 9.82%   |
| 5.15.11 | 2         | 0.89%   |
| 6.1.8   | 1         | 0.45%   |
| 6.1.1   | 1         | 0.45%   |
| 5.9.12  | 1         | 0.45%   |
| 5.9.1   | 1         | 0.45%   |
| 5.8.13  | 1         | 0.45%   |
| 5.8.11  | 1         | 0.45%   |
| 5.6.8   | 1         | 0.45%   |
| 5.4.6   | 1         | 0.45%   |
| 5.4.225 | 1         | 0.45%   |
| 5.4.125 | 1         | 0.45%   |
| 5.4.121 | 1         | 0.45%   |
| 5.18.13 | 1         | 0.45%   |
| 5.17.2  | 1         | 0.45%   |
| 5.14.15 | 1         | 0.45%   |
| 5.13.7  | 1         | 0.45%   |
| 5.11.0  | 1         | 0.45%   |
| 5.10.75 | 1         | 0.45%   |
| 4.20.8  | 1         | 0.45%   |
| 4.19.8  | 1         | 0.45%   |
| 2.6.32  | 1         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 117       | 52.47%  |
| 3.10    | 63        | 28.25%  |
| 5.14    | 23        | 10.31%  |
| 5.4     | 3         | 1.35%   |
| 6.1     | 2         | 0.9%    |
| 5.9     | 2         | 0.9%    |
| 5.8     | 2         | 0.9%    |
| 5.15    | 2         | 0.9%    |
| 5.6     | 1         | 0.45%   |
| 5.18    | 1         | 0.45%   |
| 5.17    | 1         | 0.45%   |
| 5.13    | 1         | 0.45%   |
| 5.11    | 1         | 0.45%   |
| 5.10    | 1         | 0.45%   |
| 4.20    | 1         | 0.45%   |
| 4.19    | 1         | 0.45%   |
| 2.6     | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 216       | 98.18%  |
| i686   | 4         | 1.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 159       | 71.62%  |
| GNOME Classic | 18        | 8.11%   |
| KDE4          | 14        | 6.31%   |
| Unknown       | 12        | 5.41%   |
| MATE          | 8         | 3.6%    |
| XFCE          | 4         | 1.8%    |
| Cinnamon      | 4         | 1.8%    |
| KDE5          | 2         | 0.9%    |
| KDE           | 1         | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 120       | 52.63%  |
| Wayland | 101       | 44.3%   |
| Unknown | 5         | 2.19%   |
| Web     | 1         | 0.44%   |
| Tty     | 1         | 0.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 110       | 49.11%  |
| Unknown | 104       | 46.43%  |
| LightDM | 6         | 2.68%   |
| TDM     | 3         | 1.34%   |
| SDDM    | 1         | 0.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 116       | 52.02%  |
| Unknown     | 23        | 10.31%  |
| en_GB       | 16        | 7.17%   |
| de_DE       | 10        | 4.48%   |
| ru_RU       | 9         | 4.04%   |
| pt_BR       | 9         | 4.04%   |
| fr_FR       | 9         | 4.04%   |
| en_IN       | 4         | 1.79%   |
| zh_CN       | 3         | 1.35%   |
| ko_KR       | 3         | 1.35%   |
| en_CA       | 3         | 1.35%   |
| pl_PL       | 2         | 0.9%    |
| nb_NO       | 2         | 0.9%    |
| it_IT       | 2         | 0.9%    |
| es_ES       | 2         | 0.9%    |
| es_AR       | 2         | 0.9%    |
| pt_PT       | 1         | 0.45%   |
| ja_JP       | 1         | 0.45%   |
| es_PE       | 1         | 0.45%   |
| es_MX       | 1         | 0.45%   |
| en_ZA       | 1         | 0.45%   |
| en_US.utf-8 | 1         | 0.45%   |
| en_IE       | 1         | 0.45%   |
| da_DK       | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 122       | 54.95%  |
| BIOS | 100       | 45.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 175       | 78.48%  |
| Ext4    | 36        | 16.14%  |
| Unknown | 9         | 4.04%   |
| Overlay | 1         | 0.45%   |
| Ext3    | 1         | 0.45%   |
| Ext2    | 1         | 0.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 102       | 45.74%  |
| GPT     | 75        | 33.63%  |
| MBR     | 46        | 20.63%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 191       | 86.82%  |
| Yes       | 29        | 13.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 178       | 80.18%  |
| Yes       | 44        | 19.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 61        | 27.73%  |
| Dell                   | 45        | 20.45%  |
| Hewlett-Packard        | 43        | 19.55%  |
| ASUSTek Computer       | 16        | 7.27%   |
| Acer                   | 15        | 6.82%   |
| Sony                   | 6         | 2.73%   |
| Samsung Electronics    | 6         | 2.73%   |
| MSI                    | 5         | 2.27%   |
| Toshiba                | 3         | 1.36%   |
| Timi                   | 3         | 1.36%   |
| LG Electronics         | 2         | 0.91%   |
| Apple                  | 2         | 0.91%   |
| Unknown                | 2         | 0.91%   |
| TUXEDO                 | 1         | 0.45%   |
| RM Education           | 1         | 0.45%   |
| Razer                  | 1         | 0.45%   |
| Panasonic              | 1         | 0.45%   |
| Notebook               | 1         | 0.45%   |
| Medion                 | 1         | 0.45%   |
| HONOR                  | 1         | 0.45%   |
| Gigabyte Technology    | 1         | 0.45%   |
| Fujitsu                | 1         | 0.45%   |
| COPELION INTERNATIONAL | 1         | 0.45%   |
| Clevo                  | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Lenovo Z50-70 20354                                   | 2         | 0.91%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK                 | 2         | 0.91%   |
| HP ProBook 450 G5                                     | 2         | 0.91%   |
| HP Notebook                                           | 2         | 0.91%   |
| HP EliteBook 840 G5                                   | 2         | 0.91%   |
| Dell System XPS L702X                                 | 2         | 0.91%   |
| Dell Studio 1747                                      | 2         | 0.91%   |
| Dell Latitude E5470                                   | 2         | 0.91%   |
| Dell Inspiron N4050                                   | 2         | 0.91%   |
| Unknown                                               | 2         | 0.91%   |
| TUXEDO Pulse 15 Gen1                                  | 1         | 0.45%   |
| Toshiba Satellite Radius 12 P20W-C-106                | 1         | 0.45%   |
| Toshiba Satellite L15W-B                              | 1         | 0.45%   |
| Toshiba Satellite A135                                | 1         | 0.45%   |
| Timi TM1709                                           | 1         | 0.45%   |
| Timi RedmiBook 16                                     | 1         | 0.45%   |
| Timi Mi NoteBook Horizon Edition 14                   | 1         | 0.45%   |
| Sony VPCSB19GG                                        | 1         | 0.45%   |
| Sony VPCEH26EN                                        | 1         | 0.45%   |
| Sony VPCEH15FX                                        | 1         | 0.45%   |
| Sony VPCEG15FB                                        | 1         | 0.45%   |
| Sony VGN-N19VP_B                                      | 1         | 0.45%   |
| Sony SVT11215CGW                                      | 1         | 0.45%   |
| Samsung R560                                          | 1         | 0.45%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B                   | 1         | 0.45%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S     | 1         | 0.45%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.45%   |
| Samsung 300E4A/300E5A/300E7A                          | 1         | 0.45%   |
| Samsung 270E5J/2570EJ                                 | 1         | 0.45%   |
| RM Education RM                                       | 1         | 0.45%   |
| Razer Blade 15 (2022) - RZ09-0421                     | 1         | 0.45%   |
| Panasonic CF-19ADNAXDY                                | 1         | 0.45%   |
| Notebook WA50SRQ                                      | 1         | 0.45%   |
| MSI Katana GF76 12UE                                  | 1         | 0.45%   |
| MSI GP75 Leopard 10SFK                                | 1         | 0.45%   |
| MSI GP62MVR 7RFX                                      | 1         | 0.45%   |
| MSI GL63 8SD                                          | 1         | 0.45%   |
| MSI GE73VR 7RF                                        | 1         | 0.45%   |
| Medion P6622                                          | 1         | 0.45%   |
| LG Z435-GE40K                                         | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 40        | 18.18%  |
| HP EliteBook           | 16        | 7.27%   |
| Dell Latitude          | 16        | 7.27%   |
| Acer Aspire            | 10        | 4.55%   |
| Lenovo IdeaPad         | 9         | 4.09%   |
| HP ProBook             | 9         | 4.09%   |
| Dell Inspiron          | 9         | 4.09%   |
| Dell Vostro            | 6         | 2.73%   |
| Dell Precision         | 5         | 2.27%   |
| HP ZBook               | 4         | 1.82%   |
| HP Pavilion            | 4         | 1.82%   |
| HP Laptop              | 4         | 1.82%   |
| Dell XPS               | 4         | 1.82%   |
| Toshiba Satellite      | 3         | 1.36%   |
| ASUS VivoBook          | 3         | 1.36%   |
| Lenovo Z50-70          | 2         | 0.91%   |
| HP Notebook            | 2         | 0.91%   |
| Dell System            | 2         | 0.91%   |
| Dell Studio            | 2         | 0.91%   |
| Acer Nitro             | 2         | 0.91%   |
| Unknown                | 2         | 0.91%   |
| TUXEDO Pulse           | 1         | 0.45%   |
| Timi TM1709            | 1         | 0.45%   |
| Timi RedmiBook         | 1         | 0.45%   |
| Timi Mi                | 1         | 0.45%   |
| Sony VPCSB19GG         | 1         | 0.45%   |
| Sony VPCEH26EN         | 1         | 0.45%   |
| Sony VPCEH15FX         | 1         | 0.45%   |
| Sony VPCEG15FB         | 1         | 0.45%   |
| Sony VGN-N19VP         | 1         | 0.45%   |
| Sony SVT11215CGW       | 1         | 0.45%   |
| Samsung R560           | 1         | 0.45%   |
| Samsung 700Z3A         | 1         | 0.45%   |
| Samsung 500R4K         | 1         | 0.45%   |
| Samsung 300E5EV        | 1         | 0.45%   |
| Samsung 300E4A         | 1         | 0.45%   |
| Samsung 270E5J         | 1         | 0.45%   |
| RM Education RM        | 1         | 0.45%   |
| Razer Blade            | 1         | 0.45%   |
| Panasonic CF-19ADNAXDY | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 25        | 11.36%  |
| 2019 | 24        | 10.91%  |
| 2016 | 20        | 9.09%   |
| 2014 | 19        | 8.64%   |
| 2013 | 19        | 8.64%   |
| 2020 | 17        | 7.73%   |
| 2011 | 17        | 7.73%   |
| 2018 | 15        | 6.82%   |
| 2015 | 14        | 6.36%   |
| 2010 | 12        | 5.45%   |
| 2017 | 11        | 5%      |
| 2021 | 8         | 3.64%   |
| 2008 | 5         | 2.27%   |
| 2022 | 4         | 1.82%   |
| 2007 | 4         | 1.82%   |
| 2009 | 3         | 1.36%   |
| 2006 | 2         | 0.91%   |
| 2001 | 1         | 0.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 220       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 200       | 90.5%   |
| Enabled  | 21        | 9.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 219       | 99.55%  |
| Yes  | 1         | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 86        | 38.91%  |
| 3.01-4.0    | 36        | 16.29%  |
| 16.01-24.0  | 33        | 14.93%  |
| 8.01-16.0   | 32        | 14.48%  |
| 32.01-64.0  | 23        | 10.41%  |
| 1.01-2.0    | 4         | 1.81%   |
| 24.01-32.0  | 2         | 0.9%    |
| 64.01-256.0 | 2         | 0.9%    |
| 0.51-1.0    | 2         | 0.9%    |
| 2.01-3.0    | 1         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 76        | 32.2%   |
| 4.01-8.0   | 48        | 20.34%  |
| 1.01-2.0   | 44        | 18.64%  |
| 3.01-4.0   | 41        | 17.37%  |
| 8.01-16.0  | 11        | 4.66%   |
| 0.51-1.0   | 11        | 4.66%   |
| 24.01-32.0 | 2         | 0.85%   |
| 32.01-64.0 | 1         | 0.42%   |
| 0.01-0.5   | 1         | 0.42%   |
| Unknown    | 1         | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 157       | 71.04%  |
| 2      | 50        | 22.62%  |
| 3      | 9         | 4.07%   |
| 4      | 3         | 1.36%   |
| 0      | 2         | 0.9%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 137       | 62.27%  |
| Yes       | 83        | 37.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 194       | 88.18%  |
| No        | 26        | 11.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 219       | 99.55%  |
| No        | 1         | 0.45%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 169       | 76.82%  |
| No        | 51        | 23.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 33        | 14.93%  |
| Germany      | 18        | 8.14%   |
| Russia       | 13        | 5.88%   |
| UK           | 11        | 4.98%   |
| France       | 11        | 4.98%   |
| China        | 10        | 4.52%   |
| Brazil       | 10        | 4.52%   |
| India        | 8         | 3.62%   |
| Sweden       | 6         | 2.71%   |
| Canada       | 6         | 2.71%   |
| Spain        | 5         | 2.26%   |
| Poland       | 5         | 2.26%   |
| Mexico       | 5         | 2.26%   |
| Italy        | 5         | 2.26%   |
| Belgium      | 5         | 2.26%   |
| Ukraine      | 4         | 1.81%   |
| South Korea  | 4         | 1.81%   |
| Netherlands  | 3         | 1.36%   |
| Malaysia     | 3         | 1.36%   |
| Kazakhstan   | 3         | 1.36%   |
| Finland      | 3         | 1.36%   |
| Bulgaria     | 3         | 1.36%   |
| Turkey       | 2         | 0.9%    |
| Switzerland  | 2         | 0.9%    |
| South Africa | 2         | 0.9%    |
| Peru         | 2         | 0.9%    |
| Norway       | 2         | 0.9%    |
| Japan        | 2         | 0.9%    |
| Israel       | 2         | 0.9%    |
| Ireland      | 2         | 0.9%    |
| Iran         | 2         | 0.9%    |
| Indonesia    | 2         | 0.9%    |
| Greece       | 2         | 0.9%    |
| Chile        | 2         | 0.9%    |
| Austria      | 2         | 0.9%    |
| Australia    | 2         | 0.9%    |
| Argentina    | 2         | 0.9%    |
| Vietnam      | 1         | 0.45%   |
| Uzbekistan   | 1         | 0.45%   |
| Taiwan       | 1         | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Moscow        | 7         | 3.06%   |
| Sofia         | 3         | 1.31%   |
| Sao Paulo     | 3         | 1.31%   |
| Mexico City   | 3         | 1.31%   |
| Helsinki      | 3         | 1.31%   |
| Guangzhou     | 3         | 1.31%   |
| Yekaterinburg | 2         | 0.87%   |
| Touget        | 2         | 0.87%   |
| Toronto       | 2         | 0.87%   |
| Tehran        | 2         | 0.87%   |
| Sollentuna    | 2         | 0.87%   |
| Phoenix       | 2         | 0.87%   |
| Paris         | 2         | 0.87%   |
| Munich        | 2         | 0.87%   |
| Mumbai        | 2         | 0.87%   |
| Lima          | 2         | 0.87%   |
| Kyiv          | 2         | 0.87%   |
| Krasnodar     | 2         | 0.87%   |
| Grovedale     | 2         | 0.87%   |
| Denver        | 2         | 0.87%   |
| Buenos Aires  | 2         | 0.87%   |
| Berlin        | 2         | 0.87%   |
| Beijing       | 2         | 0.87%   |
| Albuquerque   | 2         | 0.87%   |
| Zirndorf      | 1         | 0.44%   |
| Zagreb        | 1         | 0.44%   |
| Yeonsu-gu     | 1         | 0.44%   |
| Yangpu        | 1         | 0.44%   |
| Xuhui         | 1         | 0.44%   |
| Wheeling      | 1         | 0.44%   |
| West Chester  | 1         | 0.44%   |
| Waltham       | 1         | 0.44%   |
| Vilnius       | 1         | 0.44%   |
| Viladecans    | 1         | 0.44%   |
| Vicenza       | 1         | 0.44%   |
| Vancouver     | 1         | 0.44%   |
| Utrecht       | 1         | 0.44%   |
| Tygelsjoe     | 1         | 0.44%   |
| Turnhout      | 1         | 0.44%   |
| Toyama        | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 51        | 68     | 17.96%  |
| Seagate                      | 36        | 40     | 12.68%  |
| Toshiba                      | 25        | 30     | 8.8%    |
| WDC                          | 23        | 26     | 8.1%    |
| Kingston                     | 20        | 23     | 7.04%   |
| SanDisk                      | 18        | 19     | 6.34%   |
| Unknown                      | 15        | 17     | 5.28%   |
| Intel                        | 11        | 13     | 3.87%   |
| HGST                         | 11        | 13     | 3.87%   |
| SK hynix                     | 9         | 9      | 3.17%   |
| Hitachi                      | 8         | 9      | 2.82%   |
| Micron Technology            | 7         | 7      | 2.46%   |
| Crucial                      | 7         | 8      | 2.46%   |
| LITEON                       | 4         | 5      | 1.41%   |
| SPCC                         | 3         | 5      | 1.06%   |
| A-DATA Technology            | 3         | 3      | 1.06%   |
| Union Memory                 | 2         | 2      | 0.7%    |
| UMIS                         | 2         | 2      | 0.7%    |
| StoreJet                     | 2         | 2      | 0.7%    |
| LITEONIT                     | 2         | 2      | 0.7%    |
| Lenovo                       | 2         | 3      | 0.7%    |
| KIOXIA                       | 2         | 3      | 0.7%    |
| XrayDisk                     | 1         | 1      | 0.35%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.35%   |
| Transcend                    | 1         | 2      | 0.35%   |
| Toshiba America Info Systems | 1         | 2      | 0.35%   |
| SSD                          | 1         | 1      | 0.35%   |
| Smartbuy                     | 1         | 1      | 0.35%   |
| Silicon Motion               | 1         | 1      | 0.35%   |
| Plextor                      | 1         | 1      | 0.35%   |
| OCZ                          | 1         | 2      | 0.35%   |
| Lexar                        | 1         | 1      | 0.35%   |
| Kingston Technology Company  | 1         | 1      | 0.35%   |
| Kingmax                      | 1         | 1      | 0.35%   |
| JetFlash                     | 1         | 1      | 0.35%   |
| Intenso                      | 1         | 1      | 0.35%   |
| Hjwdz                        | 1         | 1      | 0.35%   |
| Hewlett-Packard              | 1         | 1      | 0.35%   |
| GOODRAM                      | 1         | 1      | 0.35%   |
| Fujitsu                      | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                            | 6         | 2.04%   |
| Seagate ST1000LM035-1RK172 1TB                    | 6         | 2.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 6         | 2.04%   |
| Samsung NVMe SSD Drive 512GB                      | 5         | 1.7%    |
| Kingston SA400S37240G 240GB SSD                   | 5         | 1.7%    |
| Unknown MMC Card  32GB                            | 3         | 1.02%   |
| Seagate ST500LT012-1DG142 500GB                   | 3         | 1.02%   |
| SanDisk NVMe SSD Drive 512GB                      | 3         | 1.02%   |
| Kingston SA400S37120G 120GB SSD                   | 3         | 1.02%   |
| Kingston SA400M8240G 240GB SSD                    | 3         | 1.02%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 2         | 0.68%   |
| Toshiba TR200 240GB SSD                           | 2         | 0.68%   |
| Toshiba MQ04ABF100 1TB                            | 2         | 0.68%   |
| StoreJet Transcend 500GB                          | 2         | 0.68%   |
| SPCC Solid State Disk 256GB                       | 2         | 0.68%   |
| SK hynix SC210 mSATA 256GB SSD                    | 2         | 0.68%   |
| Seagate ST500LM012 HN-M500MBB 500GB               | 2         | 0.68%   |
| Seagate BUP Slim 1TB                              | 2         | 0.68%   |
| SanDisk NVMe SSD Drive 500GB                      | 2         | 0.68%   |
| Samsung SSD 860 EVO 500GB                         | 2         | 0.68%   |
| Samsung SSD 860 EVO 1TB                           | 2         | 0.68%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 2         | 0.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 0.68%   |
| Samsung NVMe SSD Controller SM981/PM981 2TB       | 2         | 0.68%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD              | 2         | 0.68%   |
| Samsung MZNLH512HALU-00000 512GB SSD              | 2         | 0.68%   |
| Micron 2450_MTFDKBA512TFK 512GB                   | 2         | 0.68%   |
| Intel SSDPEKKF256G8L 256GB                        | 2         | 0.68%   |
| Hitachi HTS547550A9E384 500GB                     | 2         | 0.68%   |
| HGST HTS725032A7E630 320GB                        | 2         | 0.68%   |
| HGST HTS721010A9E630 1TB                          | 2         | 0.68%   |
| HGST HTS545050A7E680 500GB                        | 2         | 0.68%   |
| HGST HTS545050A7E380 500GB                        | 2         | 0.68%   |
| XrayDisk SSD 240GB                                | 1         | 0.34%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                  | 1         | 0.34%   |
| WDC WDS500G1R0B-68A4Z0 500GB SSD                  | 1         | 0.34%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                    | 1         | 0.34%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD                    | 1         | 0.34%   |
| WDC WD7500BPVX-00JC3T0 752GB                      | 1         | 0.34%   |
| WDC WD7500BPKX-22HPJT0 752GB                      | 1         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 39     | 38.46%  |
| WDC                 | 17        | 19     | 18.68%  |
| Toshiba             | 16        | 20     | 17.58%  |
| HGST                | 11        | 13     | 12.09%  |
| Hitachi             | 8         | 9      | 8.79%   |
| Samsung Electronics | 2         | 2      | 2.2%    |
| Unknown             | 1         | 1      | 1.1%    |
| Fujitsu             | 1         | 1      | 1.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 34        | 42     | 28.57%  |
| Kingston            | 19        | 22     | 15.97%  |
| SanDisk             | 9         | 10     | 7.56%   |
| Toshiba             | 8         | 9      | 6.72%   |
| Intel               | 7         | 8      | 5.88%   |
| Crucial             | 6         | 7      | 5.04%   |
| SK hynix            | 4         | 4      | 3.36%   |
| LITEON              | 4         | 5      | 3.36%   |
| WDC                 | 3         | 4      | 2.52%   |
| SPCC                | 3         | 5      | 2.52%   |
| Micron Technology   | 3         | 3      | 2.52%   |
| StoreJet            | 2         | 2      | 1.68%   |
| LITEONIT            | 2         | 2      | 1.68%   |
| A-DATA Technology   | 2         | 2      | 1.68%   |
| XrayDisk            | 1         | 1      | 0.84%   |
| Transcend           | 1         | 2      | 0.84%   |
| SSD                 | 1         | 1      | 0.84%   |
| Smartbuy            | 1         | 1      | 0.84%   |
| Plextor             | 1         | 1      | 0.84%   |
| OCZ                 | 1         | 2      | 0.84%   |
| Lenovo              | 1         | 2      | 0.84%   |
| Kingmax             | 1         | 1      | 0.84%   |
| Intenso             | 1         | 1      | 0.84%   |
| Hewlett-Packard     | 1         | 1      | 0.84%   |
| GOODRAM             | 1         | 1      | 0.84%   |
| Biostar             | 1         | 1      | 0.84%   |
| Apple               | 1         | 1      | 0.84%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 112       | 141    | 40.58%  |
| HDD     | 90        | 104    | 32.61%  |
| NVMe    | 56        | 68     | 20.29%  |
| MMC     | 14        | 16     | 5.07%   |
| Unknown | 4         | 4      | 1.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 176       | 237    | 69.02%  |
| NVMe | 56        | 68     | 21.96%  |
| MMC  | 14        | 16     | 5.49%   |
| SAS  | 9         | 12     | 3.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 134       | 168    | 67.34%  |
| 0.51-1.0   | 59        | 71     | 29.65%  |
| 1.01-2.0   | 4         | 4      | 2.01%   |
| 3.01-4.0   | 2         | 2      | 1.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 67        | 30.04%  |
| 251-500        | 62        | 27.8%   |
| 501-1000       | 34        | 15.25%  |
| 51-100         | 21        | 9.42%   |
| 1001-2000      | 15        | 6.73%   |
| 21-50          | 8         | 3.59%   |
| More than 3000 | 5         | 2.24%   |
| 1-20           | 4         | 1.79%   |
| Unknown        | 4         | 1.79%   |
| 2001-3000      | 3         | 1.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 87        | 37.99%  |
| 21-50          | 39        | 17.03%  |
| 101-250        | 32        | 13.97%  |
| 51-100         | 29        | 12.66%  |
| 251-500        | 19        | 8.3%    |
| 501-1000       | 11        | 4.8%    |
| 1001-2000      | 5         | 2.18%   |
| Unknown        | 4         | 1.75%   |
| More than 3000 | 2         | 0.87%   |
| 2001-3000      | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                              | 2         | 5      | 6.9%    |
| WDC WD5000LPLX-60ZNTT1 500GB                        | 1         | 1      | 3.45%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 1         | 1      | 3.45%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD                | 1         | 1      | 3.45%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1      | 3.45%   |
| Toshiba MK8032GSX 80GB                              | 1         | 1      | 3.45%   |
| Smartbuy SSD 120GB                                  | 1         | 1      | 3.45%   |
| SK hynix SC210 mSATA 256GB SSD                      | 1         | 1      | 3.45%   |
| Seagate ST9750420AS 752GB                           | 1         | 1      | 3.45%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 3.45%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 3.45%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 3.45%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 1         | 1      | 3.45%   |
| SanDisk SSD PLUS 480GB                              | 1         | 1      | 3.45%   |
| SanDisk SD9SN8W256G1009 256GB SSD                   | 1         | 1      | 3.45%   |
| Micron Technology MTFDDAK256MAY-1AH1ZABHA 256GB SSD | 1         | 1      | 3.45%   |
| Micron Technology 1100 SATA 256GB SSD               | 1         | 1      | 3.45%   |
| LITEONIT LSS-16L6G-HP 16GB SSD                      | 1         | 1      | 3.45%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 1         | 1      | 3.45%   |
| Intel SSDSC2KW240H6 240GB                           | 1         | 1      | 3.45%   |
| Intel SSDSC2KW180H6 180GB                           | 1         | 1      | 3.45%   |
| Intel SSDSC2BW240A4 240GB                           | 1         | 2      | 3.45%   |
| Hitachi HTS727575A9E364 752GB                       | 1         | 1      | 3.45%   |
| Hitachi HTS545032B9A302 320GB                       | 1         | 1      | 3.45%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 3.45%   |
| Hitachi HTS543216L9SA00 160GB                       | 1         | 1      | 3.45%   |
| Hitachi HTS541680J9SA00 80GB                        | 1         | 1      | 3.45%   |
| Crucial CT480M500SSD1 480GB                         | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 5         | 8      | 17.24%  |
| Seagate           | 5         | 5      | 17.24%  |
| Hitachi           | 5         | 5      | 17.24%  |
| Intel             | 3         | 4      | 10.34%  |
| WDC               | 2         | 2      | 6.9%    |
| SanDisk           | 2         | 2      | 6.9%    |
| Micron Technology | 2         | 2      | 6.9%    |
| Smartbuy          | 1         | 1      | 3.45%   |
| SK hynix          | 1         | 1      | 3.45%   |
| LITEONIT          | 1         | 1      | 3.45%   |
| LITEON            | 1         | 1      | 3.45%   |
| Crucial           | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 31.25%  |
| Hitachi | 5         | 5      | 31.25%  |
| Toshiba | 4         | 7      | 25%     |
| WDC     | 2         | 2      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 19     | 55.17%  |
| SSD  | 13        | 14     | 44.83%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-00A0RT0 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 114       | 179    | 48.1%   |
| Works    | 94        | 120    | 39.66%  |
| Malfunc  | 28        | 33     | 11.81%  |
| Failed   | 1         | 1      | 0.42%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 189       | 73.54%  |
| Samsung Electronics              | 20        | 7.78%   |
| SanDisk                          | 11        | 4.28%   |
| AMD                              | 10        | 3.89%   |
| SK hynix                         | 5         | 1.95%   |
| Union Memory (Shenzhen)          | 4         | 1.56%   |
| Micron Technology                | 4         | 1.56%   |
| Toshiba America Info Systems     | 2         | 0.78%   |
| KIOXIA                           | 2         | 0.78%   |
| Kingston Technology Company      | 2         | 0.78%   |
| Silicon Motion                   | 1         | 0.39%   |
| Silicon Integrated Systems [SiS] | 1         | 0.39%   |
| Shenzhen Longsys Electronics     | 1         | 0.39%   |
| Nvidia                           | 1         | 0.39%   |
| Micron/Crucial Technology        | 1         | 0.39%   |
| Marvell Technology Group         | 1         | 0.39%   |
| Lenovo                           | 1         | 0.39%   |
| ADATA Technology                 | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 28        | 10.22%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 22        | 8.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 18        | 6.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 17        | 6.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 16        | 5.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 4.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 9         | 3.28%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 3.28%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 3.28%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 2.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 2.55%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 2.19%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 1.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 1.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.46%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 4         | 1.46%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 1.46%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 1.46%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 1.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 1.46%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 1.46%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.09%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                  | 2         | 0.73%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.73%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.73%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 2         | 0.73%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 2         | 0.73%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 2         | 0.73%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.73%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 2         | 0.73%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 0.73%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.73%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 2         | 0.73%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 2         | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.73%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.73%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 256GB                            | 1         | 0.36%   |
| Union Memory (Shenzhen) AM611 PCIe 3.0 x2 NVMe SSD 256GB                         | 1         | 0.36%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 175       | 66.29%  |
| NVMe | 56        | 21.21%  |
| RAID | 21        | 7.95%   |
| IDE  | 12        | 4.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 209       | 95%     |
| AMD    | 11        | 5%      |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz       | 6         | 2.73%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 5         | 2.27%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 5         | 2.27%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 5         | 2.27%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 5         | 2.27%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 5         | 2.27%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 5         | 2.27%   |
| Intel Core i3-2330M CPU @ 2.20GHz       | 5         | 2.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 1.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 4         | 1.82%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 4         | 1.82%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 1.36%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 3         | 1.36%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 3         | 1.36%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 3         | 1.36%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 3         | 1.36%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 3         | 1.36%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 3         | 1.36%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 1.36%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 3         | 1.36%   |
| Intel Pentium CPU P6200 @ 2.13GHz       | 2         | 0.91%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 0.91%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 2         | 0.91%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 2         | 0.91%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 0.91%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 0.91%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 2         | 0.91%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 0.91%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 2         | 0.91%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 0.91%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 0.91%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 0.91%   |
| Intel Core i5 CPU M 560 @ 2.67GHz       | 2         | 0.91%   |
| Intel Core i3-7020U CPU @ 2.30GHz       | 2         | 0.91%   |
| Intel Core i3-6100U CPU @ 2.30GHz       | 2         | 0.91%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 2         | 0.91%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 2         | 0.91%   |
| Intel Core i3-3120M CPU @ 2.50GHz       | 2         | 0.91%   |
| Intel Core i3-2370M CPU @ 2.40GHz       | 2         | 0.91%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 2         | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 73        | 33.18%  |
| Intel Core i7    | 68        | 30.91%  |
| Intel Core i3    | 25        | 11.36%  |
| Other            | 14        | 6.36%   |
| Intel Core 2 Duo | 10        | 4.55%   |
| Intel Celeron    | 7         | 3.18%   |
| Intel Pentium    | 6         | 2.73%   |
| AMD Ryzen 7      | 4         | 1.82%   |
| AMD Ryzen 5      | 3         | 1.36%   |
| Intel Genuine    | 2         | 0.91%   |
| Intel Core i9    | 2         | 0.91%   |
| Intel Xeon       | 1         | 0.45%   |
| Intel Pentium 4  | 1         | 0.45%   |
| Intel Atom       | 1         | 0.45%   |
| AMD Ryzen 3 PRO  | 1         | 0.45%   |
| AMD Ryzen 3      | 1         | 0.45%   |
| AMD A4           | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 125       | 56.82%  |
| 4      | 73        | 33.18%  |
| 6      | 12        | 5.45%   |
| 8      | 4         | 1.82%   |
| 14     | 3         | 1.36%   |
| 1      | 2         | 0.91%   |
| 12     | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 220       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 183       | 83.18%  |
| 1      | 37        | 16.82%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 211       | 95.48%  |
| Unknown        | 6         | 2.71%   |
| 32-bit         | 4         | 1.81%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 23        | 10.36%  |
| 0x206a7    | 23        | 10.36%  |
| 0x40651    | 18        | 8.11%   |
| 0x406e3    | 15        | 6.76%   |
| 0x806ea    | 13        | 5.86%   |
| 0x306c3    | 13        | 5.86%   |
| 0x806ec    | 10        | 4.5%    |
| 0x306d4    | 10        | 4.5%    |
| 0x20655    | 9         | 4.05%   |
| Unknown    | 9         | 4.05%   |
| 0x806c1    | 7         | 3.15%   |
| 0x906ea    | 6         | 2.7%    |
| 0x906e9    | 6         | 2.7%    |
| 0x806e9    | 6         | 2.7%    |
| 0xa0652    | 5         | 2.25%   |
| 0x706e5    | 5         | 2.25%   |
| 0x506e3    | 5         | 2.25%   |
| 0x906a3    | 4         | 1.8%    |
| 0x1067a    | 4         | 1.8%    |
| 0x906ed    | 3         | 1.35%   |
| 0x106e5    | 3         | 1.35%   |
| 0x10676    | 3         | 1.35%   |
| 0x6fb      | 2         | 0.9%    |
| 0x406c3    | 2         | 0.9%    |
| 0x30678    | 2         | 0.9%    |
| 0x20652    | 2         | 0.9%    |
| 0x08600106 | 2         | 0.9%    |
| 0x06006705 | 2         | 0.9%    |
| 0xf24      | 1         | 0.45%   |
| 0x806eb    | 1         | 0.45%   |
| 0x6fd      | 1         | 0.45%   |
| 0x6ec      | 1         | 0.45%   |
| 0x6e8      | 1         | 0.45%   |
| 0x106c2    | 1         | 0.45%   |
| 0x08600109 | 1         | 0.45%   |
| 0x08600103 | 1         | 0.45%   |
| 0x08108109 | 1         | 0.45%   |
| 0x08108102 | 1         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 46        | 20.91%  |
| Haswell          | 31        | 14.09%  |
| SandyBridge      | 23        | 10.45%  |
| IvyBridge        | 23        | 10.45%  |
| Skylake          | 21        | 9.55%   |
| Westmere         | 11        | 5%      |
| Broadwell        | 10        | 4.55%   |
| TigerLake        | 9         | 4.09%   |
| Penryn           | 7         | 3.18%   |
| Zen 2            | 5         | 2.27%   |
| IceLake          | 5         | 2.27%   |
| CometLake        | 5         | 2.27%   |
| Zen+             | 4         | 1.82%   |
| Silvermont       | 4         | 1.82%   |
| Alderlake Hybrid | 4         | 1.82%   |
| Nehalem          | 3         | 1.36%   |
| Core             | 3         | 1.36%   |
| P6               | 2         | 0.91%   |
| Excavator        | 2         | 0.91%   |
| NetBurst         | 1         | 0.45%   |
| Bonnell          | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 186       | 62.63%  |
| Nvidia                           | 75        | 25.25%  |
| AMD                              | 35        | 11.78%  |
| Silicon Integrated Systems [SiS] | 1         | 0.34%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 22        | 7.28%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 20        | 6.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 17        | 5.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 16        | 5.3%    |
| Intel UHD Graphics 620                                                                | 14        | 4.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 10        | 3.31%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 9         | 2.98%   |
| Intel HD Graphics 5500                                                                | 8         | 2.65%   |
| Intel Core Processor Integrated Graphics Controller                                   | 8         | 2.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 7         | 2.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 7         | 2.32%   |
| Intel HD Graphics 620                                                                 | 6         | 1.99%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 6         | 1.99%   |
| Intel HD Graphics 630                                                                 | 5         | 1.66%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                         | 5         | 1.66%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 4         | 1.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 4         | 1.32%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 4         | 1.32%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 4         | 1.32%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 4         | 1.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 4         | 1.32%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 3         | 0.99%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 3         | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 3         | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 3         | 0.99%   |
| Intel Iris Plus Graphics G7                                                           | 3         | 0.99%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                | 3         | 0.99%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 2         | 0.66%   |
| Nvidia GT218M [GeForce 310M]                                                          | 2         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 0.66%   |
| Nvidia GM108M [GeForce MX110]                                                         | 2         | 0.66%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 2         | 0.66%   |
| Nvidia GM108M [GeForce 840M]                                                          | 2         | 0.66%   |
| Nvidia GM107M [GeForce GTX 850M]                                                      | 2         | 0.66%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                 | 2         | 0.66%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 2         | 0.66%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 2         | 0.66%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 2         | 0.66%   |
| Nvidia GK107GLM [Quadro K1100M]                                                       | 2         | 0.66%   |
| Nvidia GK104GLM [Quadro K3100M]                                                       | 2         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 111       | 50.45%  |
| Intel + Nvidia | 58        | 26.36%  |
| Intel + AMD    | 17        | 7.73%   |
| 1 x AMD        | 16        | 7.27%   |
| 1 x Nvidia     | 15        | 6.82%   |
| AMD + Nvidia   | 2         | 0.91%   |
| 1 x SiS        | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 194       | 88.18%  |
| Unknown     | 15        | 6.82%   |
| Proprietary | 11        | 5%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 132       | 59.73%  |
| 1.01-2.0   | 37        | 16.74%  |
| 3.01-4.0   | 18        | 8.14%   |
| 0.51-1.0   | 17        | 7.69%   |
| 0.01-0.5   | 12        | 5.43%   |
| 5.01-6.0   | 2         | 0.9%    |
| 7.01-8.0   | 1         | 0.45%   |
| 2.01-3.0   | 1         | 0.45%   |
| 8.01-16.0  | 1         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 45        | 17.72%  |
| LG Display              | 43        | 16.93%  |
| Chimei Innolux          | 39        | 15.35%  |
| Samsung Electronics     | 28        | 11.02%  |
| BOE                     | 24        | 9.45%   |
| Dell                    | 14        | 5.51%   |
| Lenovo                  | 9         | 3.54%   |
| Acer                    | 7         | 2.76%   |
| Sharp                   | 5         | 1.97%   |
| PANDA                   | 5         | 1.97%   |
| Panasonic               | 4         | 1.57%   |
| Hewlett-Packard         | 4         | 1.57%   |
| Goldstar                | 4         | 1.57%   |
| Philips                 | 2         | 0.79%   |
| InnoLux Display         | 2         | 0.79%   |
| ASUSTek Computer        | 2         | 0.79%   |
| Apple                   | 2         | 0.79%   |
| Vizio                   | 1         | 0.39%   |
| TMX                     | 1         | 0.39%   |
| Sony                    | 1         | 0.39%   |
| SKY                     | 1         | 0.39%   |
| Onkyo                   | 1         | 0.39%   |
| MSI                     | 1         | 0.39%   |
| MIT                     | 1         | 0.39%   |
| LG Philips              | 1         | 0.39%   |
| InfoVision              | 1         | 0.39%   |
| HannStar                | 1         | 0.39%   |
| Gateway                 | 1         | 0.39%   |
| Chi Mei Optoelectronics | 1         | 0.39%   |
| CHD                     | 1         | 0.39%   |
| AOC                     | 1         | 0.39%   |
| ALP                     | 1         | 0.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 4         | 1.56%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 3         | 1.17%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 1.17%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.17%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 2         | 0.78%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 2         | 0.78%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.78%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch           | 2         | 0.78%   |
| InnoLux Display LCD Monitor INL0014 1366x768 309x174mm 14.0-inch      | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch      | 2         | 0.78%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 0.78%   |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                 | 2         | 0.78%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                 | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 0.78%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 2         | 0.78%   |
| AU Optronics LCD Monitor 1920x1080                                    | 2         | 0.78%   |
| Vizio E420VO VIZ0070 1920x1080 930x523mm 42.0-inch                    | 1         | 0.39%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 0.39%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                    | 1         | 0.39%   |
| SKY 22X1-M225F SKY2150 1920x1080 476x268mm 21.5-inch                  | 1         | 0.39%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.39%   |
| Sharp LCD Monitor SHP144D 3840x2160 276x156mm 12.5-inch               | 1         | 0.39%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 1         | 0.39%   |
| Samsung Electronics SMT22A350 SAM07A7 1920x1080 477x268mm 21.5-inch   | 1         | 0.39%   |
| Samsung Electronics SMS22A300B SAM078E 1920x1080 477x268mm 21.5-inch  | 1         | 0.39%   |
| Samsung Electronics SMBX2450 SAM0721 1920x1080 531x299mm 24.0-inch    | 1         | 0.39%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 1         | 0.39%   |
| Samsung Electronics S22B420 SAM0979 1680x1050 473x291mm 21.9-inch     | 1         | 0.39%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch  | 1         | 0.39%   |
| Samsung Electronics LCD Monitor SEC3848 1920x1200 367x230mm 17.1-inch | 1         | 0.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 104       | 44.07%  |
| 1366x768 (WXGA)    | 67        | 28.39%  |
| 1600x900 (HD+)     | 18        | 7.63%   |
| 1280x800 (WXGA)    | 10        | 4.24%   |
| 3840x2160 (4K)     | 9         | 3.81%   |
| 2560x1440 (QHD)    | 5         | 2.12%   |
| 1680x1050 (WSXGA+) | 5         | 2.12%   |
| 1280x1024 (SXGA)   | 5         | 2.12%   |
| 1920x1200 (WUXGA)  | 3         | 1.27%   |
| 2560x1600          | 2         | 0.85%   |
| 1440x900 (WXGA+)   | 2         | 0.85%   |
| 3456x2160          | 1         | 0.42%   |
| 3440x1440          | 1         | 0.42%   |
| 3200x2000          | 1         | 0.42%   |
| 1600x1200          | 1         | 0.42%   |
| 1280x720 (HD)      | 1         | 0.42%   |
| 1024x600           | 1         | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 100       | 39.06%  |
| 14      | 35        | 13.67%  |
| 13      | 26        | 10.16%  |
| 17      | 22        | 8.59%   |
| 12      | 13        | 5.08%   |
| 24      | 12        | 4.69%   |
| 23      | 10        | 3.91%   |
| 27      | 7         | 2.73%   |
| 21      | 6         | 2.34%   |
| 19      | 4         | 1.56%   |
| 31      | 2         | 0.78%   |
| 20      | 2         | 0.78%   |
| 16      | 2         | 0.78%   |
| 11      | 2         | 0.78%   |
| Unknown | 2         | 0.78%   |
| 55      | 1         | 0.39%   |
| 52      | 1         | 0.39%   |
| 42      | 1         | 0.39%   |
| 40      | 1         | 0.39%   |
| 36      | 1         | 0.39%   |
| 34      | 1         | 0.39%   |
| 32      | 1         | 0.39%   |
| 29      | 1         | 0.39%   |
| 28      | 1         | 0.39%   |
| 18      | 1         | 0.39%   |
| 10      | 1         | 0.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 152       | 60.32%  |
| 351-400     | 26        | 10.32%  |
| 501-600     | 24        | 9.52%   |
| 201-300     | 22        | 8.73%   |
| 401-500     | 13        | 5.16%   |
| 601-700     | 6         | 2.38%   |
| 701-800     | 3         | 1.19%   |
| 1001-1500   | 2         | 0.79%   |
| Unknown     | 2         | 0.79%   |
| 801-900     | 1         | 0.4%    |
| 901-1000    | 1         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 184       | 85.19%  |
| 16/10   | 20        | 9.26%   |
| 5/4     | 5         | 2.31%   |
| 3/2     | 3         | 1.39%   |
| Unknown | 2         | 0.93%   |
| 4/3     | 1         | 0.46%   |
| 21/9    | 1         | 0.46%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 99        | 38.82%  |
| 81-90          | 57        | 22.35%  |
| 201-250        | 22        | 8.63%   |
| 121-130        | 18        | 7.06%   |
| 61-70          | 13        | 5.1%    |
| 151-200        | 8         | 3.14%   |
| 301-350        | 7         | 2.75%   |
| 351-500        | 6         | 2.35%   |
| 71-80          | 4         | 1.57%   |
| 141-150        | 4         | 1.57%   |
| 251-300        | 3         | 1.18%   |
| 501-1000       | 3         | 1.18%   |
| More than 1000 | 2         | 0.78%   |
| 51-60          | 2         | 0.78%   |
| 131-140        | 2         | 0.78%   |
| Unknown        | 2         | 0.78%   |
| 41-50          | 1         | 0.39%   |
| 111-120        | 1         | 0.39%   |
| 91-100         | 1         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 113       | 45.38%  |
| 101-120       | 69        | 27.71%  |
| 51-100        | 50        | 20.08%  |
| More than 240 | 8         | 3.21%   |
| 161-240       | 5         | 2.01%   |
| 1-50          | 2         | 0.8%    |
| Unknown       | 2         | 0.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 166       | 73.13%  |
| 2     | 44        | 19.38%  |
| 0     | 12        | 5.29%   |
| 3     | 5         | 2.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 144       | 41.74%  |
| Realtek Semiconductor             | 99        | 28.7%   |
| Qualcomm Atheros                  | 53        | 15.36%  |
| Broadcom                          | 15        | 4.35%   |
| TP-Link                           | 4         | 1.16%   |
| Ralink                            | 3         | 0.87%   |
| Ericsson Business Mobile Networks | 3         | 0.87%   |
| Xiaomi                            | 2         | 0.58%   |
| Ralink Technology                 | 2         | 0.58%   |
| Marvell Technology Group          | 2         | 0.58%   |
| Dell                              | 2         | 0.58%   |
| Broadcom Limited                  | 2         | 0.58%   |
| ASIX Electronics                  | 2         | 0.58%   |
| Xilinx                            | 1         | 0.29%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.29%   |
| Sierra Wireless                   | 1         | 0.29%   |
| Samsung Electronics               | 1         | 0.29%   |
| Qualcomm Atheros Communications   | 1         | 0.29%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.29%   |
| Nvidia                            | 1         | 0.29%   |
| Huawei Technologies               | 1         | 0.29%   |
| Edimax Technology                 | 1         | 0.29%   |
| DisplayLink                       | 1         | 0.29%   |
| D-Link                            | 1         | 0.29%   |
| ASUSTek Computer                  | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 70        | 15.84%  |
| Intel Wireless 7260                                               | 19        | 4.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 4.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 3.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 2.71%   |
| Intel Wireless 8260                                               | 12        | 2.71%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 2.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 2.04%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 1.58%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 1.58%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 1.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 1.36%   |
| Intel Wireless 7265                                               | 6         | 1.36%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 1.36%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 1.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.13%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.13%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 1.13%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.9%    |
| Intel Wireless 3165                                               | 4         | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.9%    |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.9%    |
| Intel Centrino Advanced-N 6200                                    | 4         | 0.9%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 0.9%    |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.68%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3         | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.68%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 137       | 59.05%  |
| Qualcomm Atheros                | 44        | 18.97%  |
| Realtek Semiconductor           | 25        | 10.78%  |
| Broadcom                        | 10        | 4.31%   |
| Ralink                          | 3         | 1.29%   |
| TP-Link                         | 2         | 0.86%   |
| Ralink Technology               | 2         | 0.86%   |
| Dell                            | 2         | 0.86%   |
| Broadcom Limited                | 2         | 0.86%   |
| Sierra Wireless                 | 1         | 0.43%   |
| Qualcomm Atheros Communications | 1         | 0.43%   |
| Edimax Technology               | 1         | 0.43%   |
| D-Link                          | 1         | 0.43%   |
| ASUSTek Computer                | 1         | 0.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                     | 19        | 8.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 12        | 5.17%   |
| Intel Wireless 8260                                                     | 12        | 5.17%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 4.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 3.88%   |
| Intel Wireless 8265 / 8275                                              | 8         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 3.02%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 3.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 2.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 2.59%   |
| Intel Wireless 7265                                                     | 6         | 2.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 2.16%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 2.16%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 2.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 1.72%   |
| Intel Wireless 3165                                                     | 4         | 1.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.72%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 1.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.29%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.29%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.29%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.29%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 3         | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.86%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.86%   |
| Intel Wireless 3160                                                     | 2         | 0.86%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.86%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.86%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.86%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 92        | 45.32%  |
| Intel                            | 74        | 36.45%  |
| Qualcomm Atheros                 | 17        | 8.37%   |
| Broadcom                         | 5         | 2.46%   |
| Xiaomi                           | 2         | 0.99%   |
| TP-Link                          | 2         | 0.99%   |
| Marvell Technology Group         | 2         | 0.99%   |
| ASIX Electronics                 | 2         | 0.99%   |
| Xilinx                           | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |
| Samsung Electronics              | 1         | 0.49%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.49%   |
| Nvidia                           | 1         | 0.49%   |
| Huawei Technologies              | 1         | 0.49%   |
| DisplayLink                      | 1         | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 70        | 33.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 8.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 7.77%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 3.4%    |
| Intel Ethernet Connection I219-LM                                 | 6         | 2.91%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 2.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.43%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 2.43%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.94%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 1.46%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 1.46%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.46%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.46%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 1.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.97%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.97%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.97%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.97%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.97%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.97%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.97%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.97%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.97%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.97%   |
| Xilinx Ethernet controller                                        | 1         | 0.49%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.49%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.49%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.49%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.49%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.49%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.49%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 219       | 52.64%  |
| Ethernet | 193       | 46.39%  |
| Modem    | 4         | 0.96%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 174       | 73.42%  |
| Ethernet | 63        | 26.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 186       | 84.55%  |
| 1     | 33        | 15%     |
| 3     | 1         | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 190       | 85.59%  |
| Yes  | 32        | 14.41%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 92        | 53.8%   |
| Qualcomm Atheros Communications | 27        | 15.79%  |
| Realtek Semiconductor           | 19        | 11.11%  |
| Broadcom                        | 11        | 6.43%   |
| Lite-On Technology              | 4         | 2.34%   |
| IMC Networks                    | 3         | 1.75%   |
| Dell                            | 3         | 1.75%   |
| Hewlett-Packard                 | 2         | 1.17%   |
| Foxconn / Hon Hai               | 2         | 1.17%   |
| Cambridge Silicon Radio         | 2         | 1.17%   |
| Apple                           | 2         | 1.17%   |
| Toshiba                         | 1         | 0.58%   |
| Ralink                          | 1         | 0.58%   |
| ASUSTek Computer                | 1         | 0.58%   |
| Alps Electric                   | 1         | 0.58%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 46        | 26.9%   |
| Realtek Bluetooth Radio                                                             | 13        | 7.6%    |
| Intel AX201 Bluetooth                                                               | 12        | 7.02%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 10        | 5.85%   |
| Intel AX200 Bluetooth                                                               | 10        | 5.85%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 4.68%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 8         | 4.68%   |
| Intel Bluetooth Device                                                              | 7         | 4.09%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 2.34%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 4         | 2.34%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 2.34%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 1.75%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.75%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.17%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.17%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.17%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.17%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.17%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.17%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 1.17%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.17%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.17%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.58%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.58%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.58%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.58%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.58%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.58%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.58%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.58%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.58%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.58%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.58%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.58%   |
| Broadcom Bluetooth 3.0 USB Dongle                                                   | 1         | 0.58%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.58%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.58%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 204       | 76.4%   |
| Nvidia                           | 32        | 11.99%  |
| AMD                              | 19        | 7.12%   |
| GN Netcom                        | 3         | 1.12%   |
| Logitech                         | 2         | 0.75%   |
| Tenx Technology                  | 1         | 0.37%   |
| Silicon Integrated Systems [SiS] | 1         | 0.37%   |
| Realtek Semiconductor            | 1         | 0.37%   |
| Plantronics                      | 1         | 0.37%   |
| Lenovo                           | 1         | 0.37%   |
| Kingston Technology              | 1         | 0.37%   |
| Asahi Kasei Microsystems         | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 34        | 10.79%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 7.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 21        | 6.67%   |
| Intel 8 Series HD Audio Controller                                                                | 18        | 5.71%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 17        | 5.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 4.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 4.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 3.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 3.17%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 3.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 2.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 2.86%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 2.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 2.22%   |
| Intel CM238 HD Audio Controller                                                                   | 7         | 2.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 2.22%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.59%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.59%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.27%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.27%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 1.27%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.27%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.63%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.63%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.63%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.63%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.63%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.63%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.63%   |
| Tenx Technology USB AUDIO                                                                         | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 42        | 29.17%  |
| SK hynix            | 34        | 23.61%  |
| Kingston            | 21        | 14.58%  |
| Unknown             | 11        | 7.64%   |
| Micron Technology   | 8         | 5.56%   |
| A-DATA Technology   | 7         | 4.86%   |
| Crucial             | 4         | 2.78%   |
| Elpida              | 3         | 2.08%   |
| Apacer              | 3         | 2.08%   |
| Ramaxel Technology  | 2         | 1.39%   |
| Nanya Technology    | 2         | 1.39%   |
| Corsair             | 2         | 1.39%   |
| Wilk                | 1         | 0.69%   |
| Transcend           | 1         | 0.69%   |
| Smart Brazil        | 1         | 0.69%   |
| SHARETRONIC         | 1         | 0.69%   |
| G.Skill             | 1         | 0.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 3         | 2%      |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s              | 2         | 1.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.33%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 2         | 1.33%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s    | 2         | 1.33%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 2         | 1.33%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.33%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 1.33%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 2         | 1.33%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 2         | 1.33%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.33%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 1.33%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 2         | 1.33%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 1.33%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 2         | 1.33%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s    | 2         | 1.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 1.33%   |
| Kingston RAM 99U5469-041.A00LF 4GB SODIMM DDR3 1600MT/s      | 2         | 1.33%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s      | 2         | 1.33%   |
| Wilk RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s         | 1         | 0.67%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.67%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                  | 1         | 0.67%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                   | 1         | 0.67%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s               | 1         | 0.67%   |
| Unknown RAM Module 4096MB SODIMM DDR3                        | 1         | 0.67%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                | 1         | 0.67%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 0.67%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s               | 1         | 0.67%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 0.67%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                       | 1         | 0.67%   |
| Unknown RAM Module 1024MB SODIMM DRAM                        | 1         | 0.67%   |
| Transcend RAM JM2666HSB-16G 16GB SODIMM DDR4 2667MT/s        | 1         | 0.67%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s | 1         | 0.67%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 0.67%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s              | 1         | 0.67%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                | 1         | 0.67%   |
| SK hynix RAM HMT851S6AMR6R-PB N0 4GB Chip DDR3 1600MT/s      | 1         | 0.67%   |
| SK hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 0.67%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.67%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s    | 1         | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 56        | 45.16%  |
| DDR4   | 52        | 41.94%  |
| DDR2   | 6         | 4.84%   |
| LPDDR4 | 3         | 2.42%   |
| LPDDR3 | 3         | 2.42%   |
| SDRAM  | 2         | 1.61%   |
| DRAM   | 1         | 0.81%   |
| DDR5   | 1         | 0.81%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 115       | 92.74%  |
| Row Of Chips | 8         | 6.45%   |
| Chip         | 1         | 0.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 51        | 37.78%  |
| 8192  | 43        | 31.85%  |
| 16384 | 20        | 14.81%  |
| 2048  | 16        | 11.85%  |
| 1024  | 3         | 2.22%   |
| 32768 | 2         | 1.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 34        | 25.37%  |
| 2667    | 30        | 22.39%  |
| 1333    | 13        | 9.7%    |
| 3200    | 12        | 8.96%   |
| 1334    | 8         | 5.97%   |
| 2400    | 7         | 5.22%   |
| 2133    | 7         | 5.22%   |
| 667     | 5         | 3.73%   |
| 4267    | 3         | 2.24%   |
| 3266    | 3         | 2.24%   |
| 1067    | 3         | 2.24%   |
| Unknown | 3         | 2.24%   |
| 800     | 2         | 1.49%   |
| 4800    | 1         | 0.75%   |
| 4199    | 1         | 0.75%   |
| 1866    | 1         | 0.75%   |
| 1066    | 1         | 0.75%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Samsung M288x Series | 1         | 100%    |

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
| Chicony Electronics                    | 51        | 26.84%  |
| Microdia                               | 20        | 10.53%  |
| IMC Networks                           | 16        | 8.42%   |
| Bison Electronics                      | 16        | 8.42%   |
| Sunplus Innovation Technology          | 13        | 6.84%   |
| Realtek Semiconductor                  | 13        | 6.84%   |
| Quanta                                 | 9         | 4.74%   |
| Lite-On Technology                     | 9         | 4.74%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 3.68%   |
| Syntek                                 | 5         | 2.63%   |
| Suyin                                  | 5         | 2.63%   |
| Acer                                   | 4         | 2.11%   |
| Silicon Motion                         | 3         | 1.58%   |
| Microsoft                              | 3         | 1.58%   |
| Logitech                               | 3         | 1.58%   |
| Apple                                  | 3         | 1.58%   |
| Samsung Electronics                    | 2         | 1.05%   |
| Ricoh                                  | 2         | 1.05%   |
| Alcor Micro                            | 2         | 1.05%   |
| Sunplus Technology                     | 1         | 0.53%   |
| Luxvisions Innotech Limited            | 1         | 0.53%   |
| Intel                                  | 1         | 0.53%   |
| Generalplus Technology                 | 1         | 0.53%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony integrated camera                     | 10        | 5.26%   |
| Microdia Integrated_Webcam_HD                 | 9         | 4.74%   |
| IMC Networks Integrated Camera                | 7         | 3.68%   |
| Sunplus Integrated_Webcam_HD                  | 6         | 3.16%   |
| Chicony HP HD Camera                          | 5         | 2.63%   |
| Chicony HD WebCam                             | 5         | 2.63%   |
| Lite-On HP HD Camera                          | 4         | 2.11%   |
| IMC Networks USB2.0 HD UVC WebCam             | 4         | 2.11%   |
| Chicony HP TrueVision HD                      | 4         | 2.11%   |
| Bison Integrated Camera                       | 4         | 2.11%   |
| Lite-On Integrated Camera                     | 3         | 1.58%   |
| Chicony USB2.0 VGA UVC WebCam                 | 3         | 1.58%   |
| Chicony Integrated Camera (1280x720@30)       | 3         | 1.58%   |
| Chicony HP Webcam [2 MP Macro]                | 3         | 1.58%   |
| Bison Lenovo EasyCamera                       | 3         | 1.58%   |
| Bison HD Webcam                               | 3         | 1.58%   |
| Syntek Integrated Camera                      | 2         | 1.05%   |
| Suyin Integrated Webcam                       | 2         | 1.05%   |
| Samsung Galaxy series, misc. (MTP mode)       | 2         | 1.05%   |
| Realtek Lenovo EasyCamera                     | 2         | 1.05%   |
| Quanta Laptop_Integrated_Webcam_2HDM          | 2         | 1.05%   |
| Quanta HP TrueVision HD Camera                | 2         | 1.05%   |
| Microdia Laptop_Integrated_Webcam_HD          | 2         | 1.05%   |
| Microdia Laptop_Integrated_Webcam_2M          | 2         | 1.05%   |
| Microdia Dell Integrated HD Webcam            | 2         | 1.05%   |
| Lite-On HP HD Webcam                          | 2         | 1.05%   |
| Chicony USB2.0 Camera                         | 2         | 1.05%   |
| Chicony TOSHIBA Web Camera - HD               | 2         | 1.05%   |
| Chicony Thinkpad T430 camera                  | 2         | 1.05%   |
| Chicony HP HD Webcam                          | 2         | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 2         | 1.05%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X               | 2         | 1.05%   |
| Acer Integrated Camera                        | 2         | 1.05%   |
| Syntek USB2.0 UVC PC Camera                   | 1         | 0.53%   |
| Syntek Lenovo EasyCamera                      | 1         | 0.53%   |
| Syntek EasyCamera                             | 1         | 0.53%   |
| Suyin Sony Visual Communication Camera        | 1         | 0.53%   |
| Suyin Integrated_Webcam_HD                    | 1         | 0.53%   |
| Suyin Asus Integrated Webcam [CN031B]         | 1         | 0.53%   |
| Sunplus 1.3M WebCam                           | 1         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 27        | 49.09%  |
| Synaptics                  | 12        | 21.82%  |
| AuthenTec                  | 5         | 9.09%   |
| Upek                       | 4         | 7.27%   |
| Shenzhen Goodix Technology | 3         | 5.45%   |
| STMicroelectronics         | 2         | 3.64%   |
| Elan Microelectronics      | 2         | 3.64%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 16.36%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 7.27%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 7.27%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 5.45%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 5.45%   |
| AuthenTec AES2810                                                          | 3         | 5.45%   |
| Validity Sensors VFS491                                                    | 2         | 3.64%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 3.64%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 3.64%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 3.64%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.64%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 3.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.82%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.82%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.82%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.82%   |
| Synaptics  WBDI                                                            | 1         | 1.82%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.82%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.82%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 12        | 66.67%  |
| Upek             | 2         | 11.11%  |
| SCM Microsystems | 1         | 5.56%   |
| O2 Micro         | 1         | 5.56%   |
| Lenovo           | 1         | 5.56%   |
| Alcor Micro      | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 27.78%  |
| Broadcom 5880                                                                | 3         | 16.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 11.11%  |
| Broadcom 58200                                                               | 2         | 11.11%  |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 5.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.56%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 5.56%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 105       | 46.88%  |
| 1     | 92        | 41.07%  |
| 2     | 19        | 8.48%   |
| 4     | 3         | 1.34%   |
| 5     | 2         | 0.89%   |
| 3     | 2         | 0.89%   |
| 6     | 1         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 55        | 36.18%  |
| Graphics card            | 37        | 24.34%  |
| Net/wireless             | 15        | 9.87%   |
| Chipcard                 | 13        | 8.55%   |
| Communication controller | 10        | 6.58%   |
| Multimedia controller    | 8         | 5.26%   |
| Sound                    | 4         | 2.63%   |
| Storage                  | 3         | 1.97%   |
| Net/ethernet             | 3         | 1.97%   |
| Bluetooth                | 2         | 1.32%   |
| Storage/raid             | 1         | 0.66%   |
| Camera                   | 1         | 0.66%   |

