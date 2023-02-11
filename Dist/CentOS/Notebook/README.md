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

Total: 292

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| CentOS 8      | 118       | 56.46%  |
| CentOS 7      | 66        | 31.58%  |
| CentOS 9      | 19        | 9.09%   |
| CentOS Stream | 5         | 2.39%   |
| CentOS 6      | 1         | 0.48%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| CentOS | 207       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.18.0-147.8.1.el8_1.x86_64  | 11        | 4.95%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 9         | 4.05%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 8         | 3.6%    |
| 4.18.0-80.11.2.el8_0.x86_64  | 7         | 3.15%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 7         | 3.15%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 6         | 2.7%    |
| 4.18.0-240.15.1.el8_3.x86_64 | 5         | 2.25%   |
| 4.18.0-193.14.2.el8_2.x86_64 | 5         | 2.25%   |
| 4.18.0-305.3.1.el8.x86_64    | 4         | 1.8%    |
| 4.18.0-294.el8.x86_64        | 4         | 1.8%    |
| 4.18.0-240.22.1.el8_3.x86_64 | 4         | 1.8%    |
| 4.18.0-147.3.1.el8_1.x86_64  | 4         | 1.8%    |
| 4.18.0-348.7.1.el8_5.x86_64  | 3         | 1.35%   |
| 4.18.0-338.el8.x86_64        | 3         | 1.35%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 3         | 1.35%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 3         | 1.35%   |
| 4.18.0-277.el8.x86_64        | 3         | 1.35%   |
| 4.18.0-240.el8.x86_64        | 3         | 1.35%   |
| 4.18.0-193.el8.x86_64        | 3         | 1.35%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 3         | 1.35%   |
| 4.18.0-147.6.el8.x86_64      | 3         | 1.35%   |
| 3.10.0-957.27.2.el7.x86_64   | 3         | 1.35%   |
| 3.10.0-957.10.1.el7.x86_64   | 3         | 1.35%   |
| 3.10.0-1160.80.1.el7.x86_64  | 3         | 1.35%   |
| 3.10.0-1160.66.1.el7.x86_64  | 3         | 1.35%   |
| 3.10.0-1160.15.2.el7.x86_64  | 3         | 1.35%   |
| 3.10.0-1127.19.1.el7.x86_64  | 3         | 1.35%   |
| 5.15.11-1.el8.elrepo.x86_64  | 2         | 0.9%    |
| 5.14.0-86.el9.x86_64         | 2         | 0.9%    |
| 5.14.0-134.el9.x86_64        | 2         | 0.9%    |
| 4.18.0-80.el8.x86_64         | 2         | 0.9%    |
| 4.18.0-408.el8.x86_64        | 2         | 0.9%    |
| 4.18.0-348.el8.x86_64        | 2         | 0.9%    |
| 4.18.0-348.2.1.el8_5.x86_64  | 2         | 0.9%    |
| 4.18.0-301.1.el8.x86_64      | 2         | 0.9%    |
| 4.18.0-240.10.1.el8_3.x86_64 | 2         | 0.9%    |
| 4.18.0-147.el8.x86_64        | 2         | 0.9%    |
| 3.10.0-957.el7.x86_64        | 2         | 0.9%    |
| 3.10.0-957.1.3.el7.x86_64    | 2         | 0.9%    |
| 3.10.0-862.14.4.el7.x86_64   | 2         | 0.9%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 114       | 54.29%  |
| 3.10.0  | 57        | 27.14%  |
| 5.14.0  | 18        | 8.57%   |
| 5.15.11 | 2         | 0.95%   |
| 6.1.1   | 1         | 0.48%   |
| 5.9.12  | 1         | 0.48%   |
| 5.9.1   | 1         | 0.48%   |
| 5.8.13  | 1         | 0.48%   |
| 5.8.11  | 1         | 0.48%   |
| 5.6.8   | 1         | 0.48%   |
| 5.4.6   | 1         | 0.48%   |
| 5.4.225 | 1         | 0.48%   |
| 5.4.125 | 1         | 0.48%   |
| 5.4.121 | 1         | 0.48%   |
| 5.18.13 | 1         | 0.48%   |
| 5.17.2  | 1         | 0.48%   |
| 5.14.15 | 1         | 0.48%   |
| 5.13.7  | 1         | 0.48%   |
| 5.11.0  | 1         | 0.48%   |
| 5.10.75 | 1         | 0.48%   |
| 4.20.8  | 1         | 0.48%   |
| 4.19.8  | 1         | 0.48%   |
| 2.6.32  | 1         | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 114       | 54.55%  |
| 3.10    | 57        | 27.27%  |
| 5.14    | 19        | 9.09%   |
| 5.4     | 3         | 1.44%   |
| 5.9     | 2         | 0.96%   |
| 5.8     | 2         | 0.96%   |
| 5.15    | 2         | 0.96%   |
| 6.1     | 1         | 0.48%   |
| 5.6     | 1         | 0.48%   |
| 5.18    | 1         | 0.48%   |
| 5.17    | 1         | 0.48%   |
| 5.13    | 1         | 0.48%   |
| 5.11    | 1         | 0.48%   |
| 5.10    | 1         | 0.48%   |
| 4.20    | 1         | 0.48%   |
| 4.19    | 1         | 0.48%   |
| 2.6     | 1         | 0.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 203       | 98.07%  |
| i686   | 4         | 1.93%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 150       | 71.77%  |
| GNOME Classic | 16        | 7.66%   |
| KDE4          | 13        | 6.22%   |
| Unknown       | 12        | 5.74%   |
| MATE          | 7         | 3.35%   |
| XFCE          | 4         | 1.91%   |
| Cinnamon      | 4         | 1.91%   |
| KDE5          | 2         | 0.96%   |
| KDE           | 1         | 0.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 113       | 52.56%  |
| Wayland | 95        | 44.19%  |
| Unknown | 5         | 2.33%   |
| Web     | 1         | 0.47%   |
| Tty     | 1         | 0.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 103       | 48.82%  |
| Unknown | 100       | 47.39%  |
| LightDM | 4         | 1.9%    |
| TDM     | 3         | 1.42%   |
| SDDM    | 1         | 0.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 107       | 50.95%  |
| Unknown     | 23        | 10.95%  |
| en_GB       | 15        | 7.14%   |
| pt_BR       | 9         | 4.29%   |
| fr_FR       | 9         | 4.29%   |
| de_DE       | 9         | 4.29%   |
| ru_RU       | 8         | 3.81%   |
| zh_CN       | 3         | 1.43%   |
| ko_KR       | 3         | 1.43%   |
| en_IN       | 3         | 1.43%   |
| en_CA       | 3         | 1.43%   |
| pl_PL       | 2         | 0.95%   |
| nb_NO       | 2         | 0.95%   |
| it_IT       | 2         | 0.95%   |
| es_ES       | 2         | 0.95%   |
| es_AR       | 2         | 0.95%   |
| pt_PT       | 1         | 0.48%   |
| ja_JP       | 1         | 0.48%   |
| es_PE       | 1         | 0.48%   |
| es_MX       | 1         | 0.48%   |
| en_ZA       | 1         | 0.48%   |
| en_US.utf-8 | 1         | 0.48%   |
| en_IE       | 1         | 0.48%   |
| da_DK       | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 112       | 53.59%  |
| BIOS | 97        | 46.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 164       | 78.1%   |
| Ext4    | 34        | 16.19%  |
| Unknown | 9         | 4.29%   |
| Overlay | 1         | 0.48%   |
| Ext3    | 1         | 0.48%   |
| Ext2    | 1         | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 98        | 46.67%  |
| GPT     | 68        | 32.38%  |
| MBR     | 44        | 20.95%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 181       | 87.44%  |
| Yes       | 26        | 12.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 169       | 80.86%  |
| Yes       | 40        | 19.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 56        | 27.05%  |
| Dell                   | 42        | 20.29%  |
| Hewlett-Packard        | 41        | 19.81%  |
| ASUSTek Computer       | 15        | 7.25%   |
| Acer                   | 13        | 6.28%   |
| Sony                   | 6         | 2.9%    |
| Samsung Electronics    | 6         | 2.9%    |
| MSI                    | 5         | 2.42%   |
| Toshiba                | 3         | 1.45%   |
| Timi                   | 3         | 1.45%   |
| LG Electronics         | 2         | 0.97%   |
| Apple                  | 2         | 0.97%   |
| Unknown                | 2         | 0.97%   |
| TUXEDO                 | 1         | 0.48%   |
| RM Education           | 1         | 0.48%   |
| Razer                  | 1         | 0.48%   |
| Panasonic              | 1         | 0.48%   |
| Notebook               | 1         | 0.48%   |
| Medion                 | 1         | 0.48%   |
| HONOR                  | 1         | 0.48%   |
| Gigabyte Technology    | 1         | 0.48%   |
| Fujitsu                | 1         | 0.48%   |
| COPELION INTERNATIONAL | 1         | 0.48%   |
| Clevo                  | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Lenovo Z50-70 20354                                   | 2         | 0.97%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK                 | 2         | 0.97%   |
| HP ProBook 450 G5                                     | 2         | 0.97%   |
| HP Notebook                                           | 2         | 0.97%   |
| HP EliteBook 840 G5                                   | 2         | 0.97%   |
| Dell Studio 1747                                      | 2         | 0.97%   |
| Dell Latitude E5470                                   | 2         | 0.97%   |
| Dell Inspiron N4050                                   | 2         | 0.97%   |
| Unknown                                               | 2         | 0.97%   |
| TUXEDO Pulse 15 Gen1                                  | 1         | 0.48%   |
| Toshiba Satellite Radius 12 P20W-C-106                | 1         | 0.48%   |
| Toshiba Satellite L15W-B                              | 1         | 0.48%   |
| Toshiba Satellite A135                                | 1         | 0.48%   |
| Timi TM1709                                           | 1         | 0.48%   |
| Timi RedmiBook 16                                     | 1         | 0.48%   |
| Timi Mi NoteBook Horizon Edition 14                   | 1         | 0.48%   |
| Sony VPCSB19GG                                        | 1         | 0.48%   |
| Sony VPCEH26EN                                        | 1         | 0.48%   |
| Sony VPCEH15FX                                        | 1         | 0.48%   |
| Sony VPCEG15FB                                        | 1         | 0.48%   |
| Sony VGN-N19VP_B                                      | 1         | 0.48%   |
| Sony SVT11215CGW                                      | 1         | 0.48%   |
| Samsung R560                                          | 1         | 0.48%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B                   | 1         | 0.48%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S     | 1         | 0.48%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.48%   |
| Samsung 300E4A/300E5A/300E7A                          | 1         | 0.48%   |
| Samsung 270E5J/2570EJ                                 | 1         | 0.48%   |
| RM Education RM                                       | 1         | 0.48%   |
| Razer Blade 15 (2022) - RZ09-0421                     | 1         | 0.48%   |
| Panasonic CF-19ADNAXDY                                | 1         | 0.48%   |
| Notebook WA50SRQ                                      | 1         | 0.48%   |
| MSI Katana GF76 12UE                                  | 1         | 0.48%   |
| MSI GP75 Leopard 10SFK                                | 1         | 0.48%   |
| MSI GP62MVR 7RFX                                      | 1         | 0.48%   |
| MSI GL63 8SD                                          | 1         | 0.48%   |
| MSI GE73VR 7RF                                        | 1         | 0.48%   |
| Medion P6622                                          | 1         | 0.48%   |
| LG Z435-GE40K                                         | 1         | 0.48%   |
| LG 15UD480-GX50K                                      | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 37        | 17.87%  |
| HP EliteBook           | 16        | 7.73%   |
| Dell Latitude          | 16        | 7.73%   |
| Lenovo IdeaPad         | 9         | 4.35%   |
| Dell Inspiron          | 9         | 4.35%   |
| Acer Aspire            | 9         | 4.35%   |
| HP ProBook             | 8         | 3.86%   |
| Dell Precision         | 5         | 2.42%   |
| HP ZBook               | 4         | 1.93%   |
| HP Pavilion            | 4         | 1.93%   |
| HP Laptop              | 4         | 1.93%   |
| Dell XPS               | 4         | 1.93%   |
| Dell Vostro            | 4         | 1.93%   |
| Toshiba Satellite      | 3         | 1.45%   |
| ASUS VivoBook          | 3         | 1.45%   |
| Lenovo Z50-70          | 2         | 0.97%   |
| HP Notebook            | 2         | 0.97%   |
| Dell Studio            | 2         | 0.97%   |
| Unknown                | 2         | 0.97%   |
| TUXEDO Pulse           | 1         | 0.48%   |
| Timi TM1709            | 1         | 0.48%   |
| Timi RedmiBook         | 1         | 0.48%   |
| Timi Mi                | 1         | 0.48%   |
| Sony VPCSB19GG         | 1         | 0.48%   |
| Sony VPCEH26EN         | 1         | 0.48%   |
| Sony VPCEH15FX         | 1         | 0.48%   |
| Sony VPCEG15FB         | 1         | 0.48%   |
| Sony VGN-N19VP         | 1         | 0.48%   |
| Sony SVT11215CGW       | 1         | 0.48%   |
| Samsung R560           | 1         | 0.48%   |
| Samsung 700Z3A         | 1         | 0.48%   |
| Samsung 500R4K         | 1         | 0.48%   |
| Samsung 300E5EV        | 1         | 0.48%   |
| Samsung 300E4A         | 1         | 0.48%   |
| Samsung 270E5J         | 1         | 0.48%   |
| RM Education RM        | 1         | 0.48%   |
| Razer Blade            | 1         | 0.48%   |
| Panasonic CF-19ADNAXDY | 1         | 0.48%   |
| Notebook WA50SRQ       | 1         | 0.48%   |
| MSI Katana             | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 24        | 11.59%  |
| 2019 | 23        | 11.11%  |
| 2016 | 21        | 10.14%  |
| 2013 | 19        | 9.18%   |
| 2014 | 18        | 8.7%    |
| 2018 | 15        | 7.25%   |
| 2020 | 14        | 6.76%   |
| 2011 | 14        | 6.76%   |
| 2010 | 12        | 5.8%    |
| 2017 | 11        | 5.31%   |
| 2015 | 11        | 5.31%   |
| 2021 | 6         | 2.9%    |
| 2008 | 5         | 2.42%   |
| 2022 | 4         | 1.93%   |
| 2007 | 4         | 1.93%   |
| 2009 | 3         | 1.45%   |
| 2006 | 2         | 0.97%   |
| 2001 | 1         | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 207       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 188       | 90.38%  |
| Enabled  | 20        | 9.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 206       | 99.52%  |
| Yes  | 1         | 0.48%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 81        | 39.13%  |
| 3.01-4.0    | 35        | 16.91%  |
| 16.01-24.0  | 31        | 14.98%  |
| 8.01-16.0   | 28        | 13.53%  |
| 32.01-64.0  | 21        | 10.14%  |
| 1.01-2.0    | 4         | 1.93%   |
| 24.01-32.0  | 2         | 0.97%   |
| 64.01-256.0 | 2         | 0.97%   |
| 0.51-1.0    | 2         | 0.97%   |
| 2.01-3.0    | 1         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 72        | 32.43%  |
| 4.01-8.0   | 43        | 19.37%  |
| 1.01-2.0   | 43        | 19.37%  |
| 3.01-4.0   | 37        | 16.67%  |
| 8.01-16.0  | 11        | 4.95%   |
| 0.51-1.0   | 11        | 4.95%   |
| 24.01-32.0 | 2         | 0.9%    |
| 32.01-64.0 | 1         | 0.45%   |
| 0.01-0.5   | 1         | 0.45%   |
| Unknown    | 1         | 0.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 150       | 72.12%  |
| 2      | 45        | 21.63%  |
| 3      | 8         | 3.85%   |
| 4      | 3         | 1.44%   |
| 0      | 2         | 0.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 129       | 62.32%  |
| Yes       | 78        | 37.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 181       | 87.44%  |
| No        | 26        | 12.56%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 206       | 99.52%  |
| No        | 1         | 0.48%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 159       | 76.81%  |
| No        | 48        | 23.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 30        | 14.42%  |
| Germany      | 16        | 7.69%   |
| Russia       | 13        | 6.25%   |
| France       | 11        | 5.29%   |
| UK           | 10        | 4.81%   |
| Brazil       | 10        | 4.81%   |
| China        | 9         | 4.33%   |
| India        | 7         | 3.37%   |
| Sweden       | 6         | 2.88%   |
| Canada       | 6         | 2.88%   |
| Spain        | 5         | 2.4%    |
| Poland       | 5         | 2.4%    |
| Mexico       | 5         | 2.4%    |
| Belgium      | 5         | 2.4%    |
| Ukraine      | 4         | 1.92%   |
| South Korea  | 4         | 1.92%   |
| Italy        | 4         | 1.92%   |
| Netherlands  | 3         | 1.44%   |
| Finland      | 3         | 1.44%   |
| Bulgaria     | 3         | 1.44%   |
| Turkey       | 2         | 0.96%   |
| Switzerland  | 2         | 0.96%   |
| South Africa | 2         | 0.96%   |
| Peru         | 2         | 0.96%   |
| Norway       | 2         | 0.96%   |
| Malaysia     | 2         | 0.96%   |
| Kazakhstan   | 2         | 0.96%   |
| Japan        | 2         | 0.96%   |
| Israel       | 2         | 0.96%   |
| Ireland      | 2         | 0.96%   |
| Indonesia    | 2         | 0.96%   |
| Greece       | 2         | 0.96%   |
| Chile        | 2         | 0.96%   |
| Austria      | 2         | 0.96%   |
| Australia    | 2         | 0.96%   |
| Argentina    | 2         | 0.96%   |
| Vietnam      | 1         | 0.48%   |
| Uzbekistan   | 1         | 0.48%   |
| Taiwan       | 1         | 0.48%   |
| Slovakia     | 1         | 0.48%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Moscow        | 7         | 3.27%   |
| Sofia         | 3         | 1.4%    |
| Sao Paulo     | 3         | 1.4%    |
| Mexico City   | 3         | 1.4%    |
| Helsinki      | 3         | 1.4%    |
| Yekaterinburg | 2         | 0.93%   |
| Touget        | 2         | 0.93%   |
| Toronto       | 2         | 0.93%   |
| Sollentuna    | 2         | 0.93%   |
| Paris         | 2         | 0.93%   |
| Munich        | 2         | 0.93%   |
| Mumbai        | 2         | 0.93%   |
| Lima          | 2         | 0.93%   |
| Kyiv          | 2         | 0.93%   |
| Krasnodar     | 2         | 0.93%   |
| Guangzhou     | 2         | 0.93%   |
| Grovedale     | 2         | 0.93%   |
| Denver        | 2         | 0.93%   |
| Buenos Aires  | 2         | 0.93%   |
| Beijing       | 2         | 0.93%   |
| Albuquerque   | 2         | 0.93%   |
| Zirndorf      | 1         | 0.47%   |
| Zagreb        | 1         | 0.47%   |
| Yeonsu-gu     | 1         | 0.47%   |
| Yangpu        | 1         | 0.47%   |
| Xuhui         | 1         | 0.47%   |
| Wheeling      | 1         | 0.47%   |
| West Chester  | 1         | 0.47%   |
| Waltham       | 1         | 0.47%   |
| Vilnius       | 1         | 0.47%   |
| Viladecans    | 1         | 0.47%   |
| Vancouver     | 1         | 0.47%   |
| Utrecht       | 1         | 0.47%   |
| Tygelsjoe     | 1         | 0.47%   |
| Turnhout      | 1         | 0.47%   |
| Toyama        | 1         | 0.47%   |
| Tolosa        | 1         | 0.47%   |
| Tel Aviv      | 1         | 0.47%   |
| Tehran        | 1         | 0.47%   |
| Tashkent      | 1         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 47        | 62     | 17.74%  |
| Seagate                      | 33        | 37     | 12.45%  |
| Toshiba                      | 23        | 28     | 8.68%   |
| WDC                          | 22        | 25     | 8.3%    |
| Kingston                     | 19        | 21     | 7.17%   |
| SanDisk                      | 16        | 17     | 6.04%   |
| Unknown                      | 14        | 16     | 5.28%   |
| Intel                        | 11        | 13     | 4.15%   |
| HGST                         | 11        | 12     | 4.15%   |
| SK hynix                     | 8         | 8      | 3.02%   |
| Hitachi                      | 8         | 9      | 3.02%   |
| Micron Technology            | 7         | 7      | 2.64%   |
| Crucial                      | 7         | 8      | 2.64%   |
| SPCC                         | 3         | 5      | 1.13%   |
| LITEON                       | 3         | 4      | 1.13%   |
| UMIS                         | 2         | 2      | 0.75%   |
| StoreJet                     | 2         | 2      | 0.75%   |
| LITEONIT                     | 2         | 2      | 0.75%   |
| Lenovo                       | 2         | 3      | 0.75%   |
| KIOXIA                       | 2         | 3      | 0.75%   |
| A-DATA Technology            | 2         | 2      | 0.75%   |
| XrayDisk                     | 1         | 1      | 0.38%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.38%   |
| Union Memory                 | 1         | 1      | 0.38%   |
| Transcend                    | 1         | 2      | 0.38%   |
| Toshiba America Info Systems | 1         | 2      | 0.38%   |
| SSD                          | 1         | 1      | 0.38%   |
| Smartbuy                     | 1         | 1      | 0.38%   |
| Silicon Motion               | 1         | 1      | 0.38%   |
| Plextor                      | 1         | 1      | 0.38%   |
| OCZ                          | 1         | 2      | 0.38%   |
| Lexar                        | 1         | 1      | 0.38%   |
| Kingston Technology Company  | 1         | 1      | 0.38%   |
| JetFlash                     | 1         | 1      | 0.38%   |
| Intenso                      | 1         | 1      | 0.38%   |
| Hjwdz                        | 1         | 1      | 0.38%   |
| Hewlett-Packard              | 1         | 1      | 0.38%   |
| GOODRAM                      | 1         | 1      | 0.38%   |
| Fujitsu                      | 1         | 1      | 0.38%   |
| Biostar                      | 1         | 1      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                              | 5         | 1.82%   |
| Seagate ST1000LM035-1RK172 1TB                      | 5         | 1.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5         | 1.82%   |
| Samsung NVMe SSD Drive 512GB                        | 5         | 1.82%   |
| Kingston SA400S37240G 240GB SSD                     | 5         | 1.82%   |
| Unknown MMC Card  32GB                              | 3         | 1.09%   |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 1.09%   |
| SanDisk NVMe SSD Drive 512GB                        | 3         | 1.09%   |
| Kingston SA400S37120G 120GB SSD                     | 3         | 1.09%   |
| Kingston SA400M8240G 240GB SSD                      | 3         | 1.09%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 2         | 0.73%   |
| Toshiba TR200 240GB SSD                             | 2         | 0.73%   |
| StoreJet Transcend 240GB                            | 2         | 0.73%   |
| SPCC Solid State Disk 256GB                         | 2         | 0.73%   |
| SK hynix SC210 mSATA 256GB SSD                      | 2         | 0.73%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 2         | 0.73%   |
| Seagate BUP Slim 2TB                                | 2         | 0.73%   |
| SanDisk NVMe SSD Drive 500GB                        | 2         | 0.73%   |
| Samsung SSD 860 EVO 500GB                           | 2         | 0.73%   |
| Samsung SSD 860 EVO 1TB                             | 2         | 0.73%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 2         | 0.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2         | 0.73%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD                | 2         | 0.73%   |
| Samsung MZNLH512HALU-00000 512GB SSD                | 2         | 0.73%   |
| Micron 2450_MTFDKBA512TFK 512GB                     | 2         | 0.73%   |
| Intel SSDPEKKF256G8L 256GB                          | 2         | 0.73%   |
| Hitachi HTS547550A9E384 500GB                       | 2         | 0.73%   |
| HGST HTS725032A7E630 320GB                          | 2         | 0.73%   |
| HGST HTS721010A9E630 1TB                            | 2         | 0.73%   |
| HGST HTS545050A7E680 500GB                          | 2         | 0.73%   |
| HGST HTS545050A7E380 500GB                          | 2         | 0.73%   |
| XrayDisk SSD 240GB                                  | 1         | 0.36%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                    | 1         | 0.36%   |
| WDC WDS500G1R0B-68A4Z0 500GB SSD                    | 1         | 0.36%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1         | 0.36%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD                      | 1         | 0.36%   |
| WDC WD7500BPKX-22HPJT0 752GB                        | 1         | 0.36%   |
| WDC WD7500BPKX-00HPJT0 752GB                        | 1         | 0.36%   |
| WDC WD6400BEVT-22A0RT0 640GB                        | 1         | 0.36%   |
| WDC WD5000LPLX-60ZNTT1 500GB                        | 1         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 36     | 37.65%  |
| WDC                 | 16        | 18     | 18.82%  |
| Toshiba             | 14        | 18     | 16.47%  |
| HGST                | 11        | 12     | 12.94%  |
| Hitachi             | 8         | 9      | 9.41%   |
| Samsung Electronics | 2         | 2      | 2.35%   |
| Unknown             | 1         | 1      | 1.18%   |
| Fujitsu             | 1         | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 39     | 28.32%  |
| Kingston            | 18        | 20     | 15.93%  |
| SanDisk             | 9         | 10     | 7.96%   |
| Toshiba             | 8         | 9      | 7.08%   |
| Intel               | 7         | 8      | 6.19%   |
| Crucial             | 6         | 7      | 5.31%   |
| SK hynix            | 4         | 4      | 3.54%   |
| WDC                 | 3         | 4      | 2.65%   |
| SPCC                | 3         | 5      | 2.65%   |
| Micron Technology   | 3         | 3      | 2.65%   |
| LITEON              | 3         | 4      | 2.65%   |
| StoreJet            | 2         | 2      | 1.77%   |
| LITEONIT            | 2         | 2      | 1.77%   |
| XrayDisk            | 1         | 1      | 0.88%   |
| Transcend           | 1         | 2      | 0.88%   |
| SSD                 | 1         | 1      | 0.88%   |
| Smartbuy            | 1         | 1      | 0.88%   |
| Plextor             | 1         | 1      | 0.88%   |
| OCZ                 | 1         | 2      | 0.88%   |
| Lenovo              | 1         | 2      | 0.88%   |
| Intenso             | 1         | 1      | 0.88%   |
| Hewlett-Packard     | 1         | 1      | 0.88%   |
| GOODRAM             | 1         | 1      | 0.88%   |
| Biostar             | 1         | 1      | 0.88%   |
| Apple               | 1         | 1      | 0.88%   |
| A-DATA Technology   | 1         | 1      | 0.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 106       | 133    | 41.25%  |
| HDD     | 84        | 97     | 32.68%  |
| NVMe    | 50        | 61     | 19.46%  |
| MMC     | 13        | 15     | 5.06%   |
| Unknown | 4         | 4      | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 166       | 223    | 69.75%  |
| NVMe | 50        | 61     | 21.01%  |
| MMC  | 13        | 15     | 5.46%   |
| SAS  | 9         | 11     | 3.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 129       | 162    | 68.98%  |
| 0.51-1.0   | 51        | 61     | 27.27%  |
| 1.01-2.0   | 6         | 6      | 3.21%   |
| 3.01-4.0   | 1         | 1      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 61        | 29.19%  |
| 101-250        | 61        | 29.19%  |
| 501-1000       | 32        | 15.31%  |
| 51-100         | 20        | 9.57%   |
| 1001-2000      | 14        | 6.7%    |
| 21-50          | 8         | 3.83%   |
| 1-20           | 4         | 1.91%   |
| Unknown        | 4         | 1.91%   |
| More than 3000 | 3         | 1.44%   |
| 2001-3000      | 2         | 0.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 83        | 38.6%   |
| 21-50          | 37        | 17.21%  |
| 101-250        | 28        | 13.02%  |
| 51-100         | 28        | 13.02%  |
| 251-500        | 19        | 8.84%   |
| 501-1000       | 11        | 5.12%   |
| 1001-2000      | 4         | 1.86%   |
| Unknown        | 4         | 1.86%   |
| More than 3000 | 1         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                              | 2         | 5      | 7.14%   |
| WDC WD5000LPLX-60ZNTT1 500GB                        | 1         | 1      | 3.57%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 1         | 1      | 3.57%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD                | 1         | 1      | 3.57%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1      | 3.57%   |
| Toshiba MK8032GSX 80GB                              | 1         | 1      | 3.57%   |
| Smartbuy SSD 120GB                                  | 1         | 1      | 3.57%   |
| SK hynix SC210 mSATA 256GB SSD                      | 1         | 1      | 3.57%   |
| Seagate ST9750420AS 752GB                           | 1         | 1      | 3.57%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 3.57%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 3.57%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 1         | 1      | 3.57%   |
| SanDisk SSD PLUS 480GB                              | 1         | 1      | 3.57%   |
| SanDisk SD9SN8W256G1009 256GB SSD                   | 1         | 1      | 3.57%   |
| Micron Technology MTFDDAK256MAY-1AH1ZABHA 256GB SSD | 1         | 1      | 3.57%   |
| Micron Technology 1100 SATA 256GB SSD               | 1         | 1      | 3.57%   |
| LITEONIT LSS-16L6G-HP 16GB SSD                      | 1         | 1      | 3.57%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 1         | 1      | 3.57%   |
| Intel SSDSC2KW240H6 240GB                           | 1         | 1      | 3.57%   |
| Intel SSDSC2KW180H6 180GB                           | 1         | 1      | 3.57%   |
| Intel SSDSC2BW240A4 240GB                           | 1         | 2      | 3.57%   |
| Hitachi HTS727575A9E364 752GB                       | 1         | 1      | 3.57%   |
| Hitachi HTS545032B9A302 320GB                       | 1         | 1      | 3.57%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 3.57%   |
| Hitachi HTS543216L9SA00 160GB                       | 1         | 1      | 3.57%   |
| Hitachi HTS541680J9SA00 80GB                        | 1         | 1      | 3.57%   |
| Crucial CT480M500SSD1 480GB                         | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 5         | 8      | 17.86%  |
| Hitachi           | 5         | 5      | 17.86%  |
| Seagate           | 4         | 4      | 14.29%  |
| Intel             | 3         | 4      | 10.71%  |
| WDC               | 2         | 2      | 7.14%   |
| SanDisk           | 2         | 2      | 7.14%   |
| Micron Technology | 2         | 2      | 7.14%   |
| Smartbuy          | 1         | 1      | 3.57%   |
| SK hynix          | 1         | 1      | 3.57%   |
| LITEONIT          | 1         | 1      | 3.57%   |
| LITEON            | 1         | 1      | 3.57%   |
| Crucial           | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 5         | 5      | 33.33%  |
| Toshiba | 4         | 7      | 26.67%  |
| Seagate | 4         | 4      | 26.67%  |
| WDC     | 2         | 2      | 13.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 18     | 53.57%  |
| SSD  | 13        | 14     | 46.43%  |

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
| Detected | 109       | 170    | 49.1%   |
| Works    | 85        | 107    | 38.29%  |
| Malfunc  | 27        | 32     | 12.16%  |
| Failed   | 1         | 1      | 0.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 179       | 74.9%   |
| Samsung Electronics              | 17        | 7.11%   |
| SanDisk                          | 9         | 3.77%   |
| AMD                              | 9         | 3.77%   |
| SK hynix                         | 4         | 1.67%   |
| Micron Technology                | 4         | 1.67%   |
| Union Memory (Shenzhen)          | 3         | 1.26%   |
| Toshiba America Info Systems     | 2         | 0.84%   |
| KIOXIA                           | 2         | 0.84%   |
| Kingston Technology Company      | 2         | 0.84%   |
| Silicon Motion                   | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |
| Shenzhen Longsys Electronics     | 1         | 0.42%   |
| Nvidia                           | 1         | 0.42%   |
| Micron/Crucial Technology        | 1         | 0.42%   |
| Marvell Technology Group         | 1         | 0.42%   |
| Lenovo                           | 1         | 0.42%   |
| ADATA Technology                 | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 26        | 10.2%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 22        | 8.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 17        | 6.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 16        | 6.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 14        | 5.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 4.31%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 3.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 3.14%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 3.14%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 7         | 2.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 2.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 2.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 1.96%   |
| Micron Non-Volatile memory controller                                            | 4         | 1.57%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.57%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 1.57%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 1.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 4         | 1.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 1.57%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 3         | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.18%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 1.18%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 1.18%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.18%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 1.18%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.78%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.78%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.78%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 0.78%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.78%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.78%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2         | 0.78%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 2         | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.78%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.39%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 1         | 0.39%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.39%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 164       | 66.67%  |
| NVMe | 50        | 20.33%  |
| RAID | 20        | 8.13%   |
| IDE  | 12        | 4.88%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 197       | 95.17%  |
| AMD    | 10        | 4.83%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz       | 6         | 2.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz       | 5         | 2.42%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 5         | 2.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 5         | 2.42%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 5         | 2.42%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 5         | 2.42%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 1.93%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 4         | 1.93%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 4         | 1.93%   |
| Intel Core i3-2330M CPU @ 2.20GHz       | 4         | 1.93%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 3         | 1.45%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 3         | 1.45%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 3         | 1.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 3         | 1.45%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 1.45%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 3         | 1.45%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 3         | 1.45%   |
| Intel Pentium CPU P6200 @ 2.13GHz       | 2         | 0.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 2         | 0.97%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 0.97%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 2         | 0.97%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 0.97%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 2         | 0.97%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 0.97%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 0.97%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 2         | 0.97%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 0.97%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 2         | 0.97%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 0.97%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 0.97%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 0.97%   |
| Intel Core i5 CPU M 560 @ 2.67GHz       | 2         | 0.97%   |
| Intel Core i3-7020U CPU @ 2.30GHz       | 2         | 0.97%   |
| Intel Core i3-6100U CPU @ 2.30GHz       | 2         | 0.97%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 2         | 0.97%   |
| Intel Core i3-3120M CPU @ 2.50GHz       | 2         | 0.97%   |
| Intel Core i3-2370M CPU @ 2.40GHz       | 2         | 0.97%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 2         | 0.97%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 2         | 0.97%   |
| Intel 12th Gen Core i7-12700H           | 2         | 0.97%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 71        | 34.3%   |
| Intel Core i7    | 63        | 30.43%  |
| Intel Core i3    | 23        | 11.11%  |
| Other            | 11        | 5.31%   |
| Intel Core 2 Duo | 10        | 4.83%   |
| Intel Celeron    | 7         | 3.38%   |
| Intel Pentium    | 6         | 2.9%    |
| AMD Ryzen 7      | 3         | 1.45%   |
| AMD Ryzen 5      | 3         | 1.45%   |
| Intel Genuine    | 2         | 0.97%   |
| Intel Core i9    | 2         | 0.97%   |
| Intel Xeon       | 1         | 0.48%   |
| Intel Pentium 4  | 1         | 0.48%   |
| Intel Atom       | 1         | 0.48%   |
| AMD Ryzen 3 PRO  | 1         | 0.48%   |
| AMD Ryzen 3      | 1         | 0.48%   |
| AMD A4           | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 118       | 57%     |
| 4      | 70        | 33.82%  |
| 6      | 10        | 4.83%   |
| 14     | 3         | 1.45%   |
| 8      | 3         | 1.45%   |
| 1      | 2         | 0.97%   |
| 12     | 1         | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 207       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 171       | 82.61%  |
| 1      | 36        | 17.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 198       | 95.19%  |
| Unknown        | 6         | 2.88%   |
| 32-bit         | 4         | 1.92%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 23        | 11%     |
| 0x206a7    | 20        | 9.57%   |
| 0x40651    | 17        | 8.13%   |
| 0x806ea    | 13        | 6.22%   |
| 0x406e3    | 13        | 6.22%   |
| 0x306c3    | 13        | 6.22%   |
| 0x806ec    | 10        | 4.78%   |
| 0x306d4    | 9         | 4.31%   |
| 0x20655    | 9         | 4.31%   |
| Unknown    | 7         | 3.35%   |
| 0x906e9    | 6         | 2.87%   |
| 0x806e9    | 6         | 2.87%   |
| 0x806c1    | 6         | 2.87%   |
| 0x906ea    | 5         | 2.39%   |
| 0x706e5    | 5         | 2.39%   |
| 0x506e3    | 5         | 2.39%   |
| 0xa0652    | 4         | 1.91%   |
| 0x906a3    | 4         | 1.91%   |
| 0x1067a    | 4         | 1.91%   |
| 0x906ed    | 3         | 1.44%   |
| 0x106e5    | 3         | 1.44%   |
| 0x10676    | 3         | 1.44%   |
| 0x6fb      | 2         | 0.96%   |
| 0x406c3    | 2         | 0.96%   |
| 0x30678    | 2         | 0.96%   |
| 0x20652    | 2         | 0.96%   |
| 0x08600106 | 2         | 0.96%   |
| 0x06006705 | 2         | 0.96%   |
| 0xf24      | 1         | 0.48%   |
| 0x806eb    | 1         | 0.48%   |
| 0x6fd      | 1         | 0.48%   |
| 0x6ec      | 1         | 0.48%   |
| 0x6e8      | 1         | 0.48%   |
| 0x106c2    | 1         | 0.48%   |
| 0x08600103 | 1         | 0.48%   |
| 0x08108109 | 1         | 0.48%   |
| 0x08108102 | 1         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 45        | 21.74%  |
| Haswell          | 30        | 14.49%  |
| IvyBridge        | 23        | 11.11%  |
| SandyBridge      | 20        | 9.66%   |
| Skylake          | 19        | 9.18%   |
| Westmere         | 11        | 5.31%   |
| Broadwell        | 9         | 4.35%   |
| Penryn           | 7         | 3.38%   |
| TigerLake        | 6         | 2.9%    |
| IceLake          | 5         | 2.42%   |
| Zen+             | 4         | 1.93%   |
| Zen 2            | 4         | 1.93%   |
| Silvermont       | 4         | 1.93%   |
| CometLake        | 4         | 1.93%   |
| Alderlake Hybrid | 4         | 1.93%   |
| Nehalem          | 3         | 1.45%   |
| Core             | 3         | 1.45%   |
| P6               | 2         | 0.97%   |
| Excavator        | 2         | 0.97%   |
| NetBurst         | 1         | 0.48%   |
| Bonnell          | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 175       | 63.41%  |
| Nvidia                           | 68        | 24.64%  |
| AMD                              | 32        | 11.59%  |
| Silicon Integrated Systems [SiS] | 1         | 0.36%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 22        | 7.83%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 17        | 6.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 16        | 5.69%   |
| Intel UHD Graphics 620                                                                | 14        | 4.98%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 14        | 4.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 10        | 3.56%   |
| Intel Core Processor Integrated Graphics Controller                                   | 8         | 2.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 7         | 2.49%   |
| Intel HD Graphics 5500                                                                | 7         | 2.49%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 2.14%   |
| Intel HD Graphics 620                                                                 | 6         | 2.14%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 6         | 2.14%   |
| Intel HD Graphics 630                                                                 | 5         | 1.78%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 5         | 1.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 4         | 1.42%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 4         | 1.42%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 4         | 1.42%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 4         | 1.42%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 4         | 1.42%   |
| AMD Renoir                                                                            | 4         | 1.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 4         | 1.42%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 3         | 1.07%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 3         | 1.07%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 3         | 1.07%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 3         | 1.07%   |
| Intel Iris Plus Graphics G7                                                           | 3         | 1.07%   |
| Nvidia GT218M [GeForce 310M]                                                          | 2         | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 0.71%   |
| Nvidia GM108M [GeForce MX110]                                                         | 2         | 0.71%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 2         | 0.71%   |
| Nvidia GM108M [GeForce 840M]                                                          | 2         | 0.71%   |
| Nvidia GM107M [GeForce GTX 850M]                                                      | 2         | 0.71%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                 | 2         | 0.71%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 2         | 0.71%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 2         | 0.71%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 2         | 0.71%   |
| Nvidia GK107GLM [Quadro K1100M]                                                       | 2         | 0.71%   |
| Nvidia GK104GLM [Quadro K3100M]                                                       | 2         | 0.71%   |
| Nvidia GF108M [NVS 5400M]                                                             | 2         | 0.71%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller         | 2         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 108       | 52.17%  |
| Intel + Nvidia | 52        | 25.12%  |
| Intel + AMD    | 15        | 7.25%   |
| 1 x AMD        | 15        | 7.25%   |
| 1 x Nvidia     | 14        | 6.76%   |
| AMD + Nvidia   | 2         | 0.97%   |
| 1 x SiS        | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 183       | 88.41%  |
| Unknown     | 14        | 6.76%   |
| Proprietary | 10        | 4.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 125       | 60.39%  |
| 1.01-2.0   | 33        | 15.94%  |
| 3.01-4.0   | 18        | 8.7%    |
| 0.51-1.0   | 15        | 7.25%   |
| 0.01-0.5   | 12        | 5.8%    |
| 7.01-8.0   | 1         | 0.48%   |
| 5.01-6.0   | 1         | 0.48%   |
| 2.01-3.0   | 1         | 0.48%   |
| 8.01-16.0  | 1         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 44        | 18.26%  |
| LG Display              | 39        | 16.18%  |
| Chimei Innolux          | 37        | 15.35%  |
| Samsung Electronics     | 27        | 11.2%   |
| BOE                     | 23        | 9.54%   |
| Dell                    | 14        | 5.81%   |
| Lenovo                  | 9         | 3.73%   |
| Acer                    | 6         | 2.49%   |
| Sharp                   | 5         | 2.07%   |
| PANDA                   | 4         | 1.66%   |
| Panasonic               | 4         | 1.66%   |
| Hewlett-Packard         | 4         | 1.66%   |
| Goldstar                | 4         | 1.66%   |
| Philips                 | 2         | 0.83%   |
| InnoLux Display         | 2         | 0.83%   |
| Apple                   | 2         | 0.83%   |
| Vizio                   | 1         | 0.41%   |
| TMX                     | 1         | 0.41%   |
| Sony                    | 1         | 0.41%   |
| SKY                     | 1         | 0.41%   |
| Onkyo                   | 1         | 0.41%   |
| MSI                     | 1         | 0.41%   |
| MIT                     | 1         | 0.41%   |
| LG Philips              | 1         | 0.41%   |
| InfoVision              | 1         | 0.41%   |
| HannStar                | 1         | 0.41%   |
| Gateway                 | 1         | 0.41%   |
| Chi Mei Optoelectronics | 1         | 0.41%   |
| CHD                     | 1         | 0.41%   |
| AOC                     | 1         | 0.41%   |
| ALP                     | 1         | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 3         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 1.23%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.23%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 3         | 1.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.82%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 2         | 0.82%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.82%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch           | 2         | 0.82%   |
| InnoLux Display LCD Monitor INL0014 1366x768 309x174mm 14.0-inch      | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch      | 2         | 0.82%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 2         | 0.82%   |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                 | 2         | 0.82%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                 | 2         | 0.82%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 0.82%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 2         | 0.82%   |
| AU Optronics LCD Monitor 1920x1080                                    | 2         | 0.82%   |
| Vizio E370VL VIZ0070 1920x1080 820x461mm 37.0-inch                    | 1         | 0.41%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 0.41%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                    | 1         | 0.41%   |
| SKY 22X1-M225F SKY2150 1920x1080 476x268mm 21.5-inch                  | 1         | 0.41%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.41%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.41%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.41%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.41%   |
| Sharp LCD Monitor SHP144D 3840x2160 276x156mm 12.5-inch               | 1         | 0.41%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 1         | 0.41%   |
| Samsung Electronics SMT22A350 SAM07A7 1920x1080 477x268mm 21.5-inch   | 1         | 0.41%   |
| Samsung Electronics SMBX2450 SAM0721 1920x1080 530x300mm 24.0-inch    | 1         | 0.41%   |
| Samsung Electronics SA300/SA350 SAM078E 1920x1080 477x268mm 21.5-inch | 1         | 0.41%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 1         | 0.41%   |
| Samsung Electronics S22B420 SAM0979 1680x1050 473x291mm 21.9-inch     | 1         | 0.41%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 630x360mm 28.6-inch     | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3848 1920x1200 367x230mm 17.1-inch | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 98        | 43.75%  |
| 1366x768 (WXGA)    | 65        | 29.02%  |
| 1600x900 (HD+)     | 15        | 6.7%    |
| 1280x800 (WXGA)    | 10        | 4.46%   |
| 3840x2160 (4K)     | 9         | 4.02%   |
| 1680x1050 (WSXGA+) | 5         | 2.23%   |
| 1280x1024 (SXGA)   | 5         | 2.23%   |
| 2560x1440 (QHD)    | 4         | 1.79%   |
| 1920x1200 (WUXGA)  | 3         | 1.34%   |
| 2560x1600          | 2         | 0.89%   |
| 1440x900 (WXGA+)   | 2         | 0.89%   |
| 3456x2160          | 1         | 0.45%   |
| 3440x1440          | 1         | 0.45%   |
| 3200x2000          | 1         | 0.45%   |
| 1600x1200          | 1         | 0.45%   |
| 1280x720 (HD)      | 1         | 0.45%   |
| 1024x600           | 1         | 0.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 96        | 39.51%  |
| 14      | 33        | 13.58%  |
| 13      | 26        | 10.7%   |
| 17      | 20        | 8.23%   |
| 12      | 12        | 4.94%   |
| 24      | 11        | 4.53%   |
| 23      | 10        | 4.12%   |
| 21      | 6         | 2.47%   |
| 27      | 4         | 1.65%   |
| 19      | 4         | 1.65%   |
| Unknown | 3         | 1.23%   |
| 31      | 2         | 0.82%   |
| 20      | 2         | 0.82%   |
| 11      | 2         | 0.82%   |
| 55      | 1         | 0.41%   |
| 52      | 1         | 0.41%   |
| 42      | 1         | 0.41%   |
| 40      | 1         | 0.41%   |
| 36      | 1         | 0.41%   |
| 34      | 1         | 0.41%   |
| 32      | 1         | 0.41%   |
| 29      | 1         | 0.41%   |
| 28      | 1         | 0.41%   |
| 18      | 1         | 0.41%   |
| 16      | 1         | 0.41%   |
| 10      | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 145       | 60.67%  |
| 351-400     | 24        | 10.04%  |
| 501-600     | 21        | 8.79%   |
| 201-300     | 21        | 8.79%   |
| 401-500     | 13        | 5.44%   |
| 601-700     | 5         | 2.09%   |
| 701-800     | 3         | 1.26%   |
| Unknown     | 3         | 1.26%   |
| 1001-1500   | 2         | 0.84%   |
| 801-900     | 1         | 0.42%   |
| 901-1000    | 1         | 0.42%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 174       | 84.47%  |
| 16/10   | 20        | 9.71%   |
| 5/4     | 5         | 2.43%   |
| 3/2     | 3         | 1.46%   |
| Unknown | 2         | 0.97%   |
| 4/3     | 1         | 0.49%   |
| 21/9    | 1         | 0.49%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 95        | 39.26%  |
| 81-90          | 55        | 22.73%  |
| 201-250        | 21        | 8.68%   |
| 121-130        | 15        | 6.2%    |
| 61-70          | 12        | 4.96%   |
| 151-200        | 8         | 3.31%   |
| 351-500        | 6         | 2.48%   |
| 71-80          | 4         | 1.65%   |
| 301-350        | 4         | 1.65%   |
| 141-150        | 4         | 1.65%   |
| 251-300        | 3         | 1.24%   |
| 501-1000       | 3         | 1.24%   |
| Unknown        | 3         | 1.24%   |
| More than 1000 | 2         | 0.83%   |
| 51-60          | 2         | 0.83%   |
| 131-140        | 2         | 0.83%   |
| 41-50          | 1         | 0.41%   |
| 111-120        | 1         | 0.41%   |
| 91-100         | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 106       | 44.92%  |
| 101-120       | 65        | 27.54%  |
| 51-100        | 47        | 19.92%  |
| More than 240 | 8         | 3.39%   |
| 161-240       | 5         | 2.12%   |
| Unknown       | 3         | 1.27%   |
| 1-50          | 2         | 0.85%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 158       | 73.83%  |
| 2     | 41        | 19.16%  |
| 0     | 10        | 4.67%   |
| 3     | 5         | 2.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 133       | 41.56%  |
| Realtek Semiconductor             | 91        | 28.44%  |
| Qualcomm Atheros                  | 50        | 15.63%  |
| Broadcom                          | 15        | 4.69%   |
| TP-Link                           | 3         | 0.94%   |
| Ralink                            | 3         | 0.94%   |
| Ericsson Business Mobile Networks | 3         | 0.94%   |
| Ralink Technology                 | 2         | 0.63%   |
| Marvell Technology Group          | 2         | 0.63%   |
| Dell                              | 2         | 0.63%   |
| Broadcom Limited                  | 2         | 0.63%   |
| ASIX Electronics                  | 2         | 0.63%   |
| Xilinx                            | 1         | 0.31%   |
| Xiaomi                            | 1         | 0.31%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.31%   |
| Sierra Wireless                   | 1         | 0.31%   |
| Samsung Electronics               | 1         | 0.31%   |
| Qualcomm Atheros Communications   | 1         | 0.31%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.31%   |
| Nvidia                            | 1         | 0.31%   |
| Huawei Technologies               | 1         | 0.31%   |
| Edimax Technology                 | 1         | 0.31%   |
| D-Link                            | 1         | 0.31%   |
| ASUSTek Computer                  | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 62        | 14.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 4.35%   |
| Intel Wireless 7260                                               | 17        | 4.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 3.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 2.9%    |
| Intel Wireless 8260                                               | 11        | 2.66%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.93%   |
| Intel Wi-Fi 6 AX200                                               | 8         | 1.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 8         | 1.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 1.69%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 1.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.45%   |
| Intel Wireless 7265                                               | 6         | 1.45%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 1.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.21%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.21%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.21%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.21%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 1.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.97%   |
| Intel Wireless 3165                                               | 4         | 0.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.97%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.97%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.97%   |
| Intel Centrino Advanced-N 6200                                    | 4         | 0.97%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 0.97%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.72%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 126       | 57.8%   |
| Qualcomm Atheros                | 42        | 19.27%  |
| Realtek Semiconductor           | 25        | 11.47%  |
| Broadcom                        | 10        | 4.59%   |
| Ralink                          | 3         | 1.38%   |
| Ralink Technology               | 2         | 0.92%   |
| Dell                            | 2         | 0.92%   |
| Broadcom Limited                | 2         | 0.92%   |
| TP-Link                         | 1         | 0.46%   |
| Sierra Wireless                 | 1         | 0.46%   |
| Qualcomm Atheros Communications | 1         | 0.46%   |
| Edimax Technology               | 1         | 0.46%   |
| D-Link                          | 1         | 0.46%   |
| ASUSTek Computer                | 1         | 0.46%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                     | 17        | 7.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 12        | 5.5%    |
| Intel Wireless 8260                                                     | 11        | 5.05%   |
| Intel Wireless 8265 / 8275                                              | 8         | 3.67%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 3.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 3.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 3.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 2.75%   |
| Intel Wireless 7265                                                     | 6         | 2.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 2.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 2.29%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2.29%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 2.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 1.83%   |
| Intel Wireless 3165                                                     | 4         | 1.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.83%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.83%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.83%   |
| Intel Centrino Advanced-N 6200                                          | 4         | 1.83%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 1.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.38%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.38%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.38%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 3         | 1.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.92%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.92%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.92%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.92%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 0.92%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 84        | 44.44%  |
| Intel                            | 72        | 38.1%   |
| Qualcomm Atheros                 | 15        | 7.94%   |
| Broadcom                         | 5         | 2.65%   |
| TP-Link                          | 2         | 1.06%   |
| Marvell Technology Group         | 2         | 1.06%   |
| ASIX Electronics                 | 2         | 1.06%   |
| Xilinx                           | 1         | 0.53%   |
| Xiaomi                           | 1         | 0.53%   |
| Silicon Integrated Systems [SiS] | 1         | 0.53%   |
| Samsung Electronics              | 1         | 0.53%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.53%   |
| Nvidia                           | 1         | 0.53%   |
| Huawei Technologies              | 1         | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 62        | 32.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 9.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 7.81%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 3.65%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 3.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.6%    |
| Intel Ethernet Connection I219-LM                                 | 5         | 2.6%    |
| Intel Ethernet Connection I218-LM                                 | 5         | 2.6%    |
| Intel Ethernet Connection (4) I219-V                              | 4         | 2.08%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 2.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 1.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 1.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.56%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 1.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.04%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.04%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.04%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.04%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.04%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.04%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.04%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.04%   |
| Xilinx Ethernet controller                                        | 1         | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.52%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.52%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.52%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet         | 1         | 0.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.52%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.52%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.52%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.52%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 206       | 52.82%  |
| Ethernet | 180       | 46.15%  |
| Modem    | 4         | 1.03%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 163       | 72.44%  |
| Ethernet | 62        | 27.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 174       | 84.06%  |
| 1     | 32        | 15.46%  |
| 3     | 1         | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 179       | 85.65%  |
| Yes  | 30        | 14.35%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 83        | 51.55%  |
| Qualcomm Atheros Communications | 26        | 16.15%  |
| Realtek Semiconductor           | 19        | 11.8%   |
| Broadcom                        | 11        | 6.83%   |
| Lite-On Technology              | 4         | 2.48%   |
| IMC Networks                    | 3         | 1.86%   |
| Dell                            | 3         | 1.86%   |
| Hewlett-Packard                 | 2         | 1.24%   |
| Foxconn / Hon Hai               | 2         | 1.24%   |
| Cambridge Silicon Radio         | 2         | 1.24%   |
| Apple                           | 2         | 1.24%   |
| Toshiba                         | 1         | 0.62%   |
| Ralink                          | 1         | 0.62%   |
| ASUSTek Computer                | 1         | 0.62%   |
| Alps Electric                   | 1         | 0.62%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 43        | 26.71%  |
| Realtek Bluetooth Radio                                                             | 13        | 8.07%   |
| Intel Bluetooth Device                                                              | 13        | 8.07%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 5.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 8         | 4.97%   |
| Intel AX200 Bluetooth                                                               | 8         | 4.97%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 4.35%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 2.48%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 4         | 2.48%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 2.48%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 1.86%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 1.86%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.24%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.24%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.24%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.24%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.24%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.24%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.24%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 1.24%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.24%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.24%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.62%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.62%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.62%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.62%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.62%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.62%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.62%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.62%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.62%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.62%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.62%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.62%   |
| Broadcom Bluetooth 3.0 USB Dongle                                                   | 1         | 0.62%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.62%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.62%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.62%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 192       | 76.19%  |
| Nvidia                           | 30        | 11.9%   |
| AMD                              | 18        | 7.14%   |
| GN Netcom                        | 3         | 1.19%   |
| Logitech                         | 2         | 0.79%   |
| Tenx Technology                  | 1         | 0.4%    |
| Silicon Integrated Systems [SiS] | 1         | 0.4%    |
| Realtek Semiconductor            | 1         | 0.4%    |
| Plantronics                      | 1         | 0.4%    |
| Lenovo                           | 1         | 0.4%    |
| Kingston Technology              | 1         | 0.4%    |
| Asahi Kasei Microsystems         | 1         | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 32        | 10.77%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 8.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 6.06%   |
| Intel 8 Series HD Audio Controller                                                                | 17        | 5.72%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 5.39%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 4.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 13        | 4.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 3.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 3.03%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 3.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 2.69%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 8         | 2.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 2.36%   |
| Intel CM238 HD Audio Controller                                                                   | 7         | 2.36%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 2.36%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 2.02%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.68%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.35%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.35%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.35%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 1.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.01%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.67%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.67%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.67%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.67%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.67%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.67%   |
| Tenx Technology USB AUDIO                                                                         | 1         | 0.34%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 0.34%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.34%   |
| Plantronics Calisto 800 Series                                                                    | 1         | 0.34%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 28.36%  |
| SK hynix            | 30        | 22.39%  |
| Kingston            | 21        | 15.67%  |
| Unknown             | 11        | 8.21%   |
| Micron Technology   | 8         | 5.97%   |
| A-DATA Technology   | 7         | 5.22%   |
| Crucial             | 4         | 2.99%   |
| Elpida              | 3         | 2.24%   |
| Ramaxel Technology  | 2         | 1.49%   |
| Corsair             | 2         | 1.49%   |
| Apacer              | 2         | 1.49%   |
| Wilk                | 1         | 0.75%   |
| Transcend           | 1         | 0.75%   |
| Smart Brazil        | 1         | 0.75%   |
| SHARETRONIC         | 1         | 0.75%   |
| Nanya Technology    | 1         | 0.75%   |
| G.Skill             | 1         | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 3         | 2.16%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 1.44%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.44%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 2         | 1.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s    | 2         | 1.44%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 2         | 1.44%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s        | 2         | 1.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 2         | 1.44%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 2         | 1.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 1.44%   |
| Kingston RAM 99U5469-041.A00LF 4GB SODIMM DDR3 1600MT/s      | 2         | 1.44%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s      | 2         | 1.44%   |
| Wilk RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s         | 1         | 0.72%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                  | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                   | 1         | 0.72%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s               | 1         | 0.72%   |
| Unknown RAM Module 4096MB SODIMM DDR3                        | 1         | 0.72%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 0.72%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s               | 1         | 0.72%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                | 1         | 0.72%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                       | 1         | 0.72%   |
| Unknown RAM Module 1024MB SODIMM DRAM                        | 1         | 0.72%   |
| Transcend RAM JM2666HSB-16G 16GB SODIMM DDR4 2667MT/s        | 1         | 0.72%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s | 1         | 0.72%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                 | 1         | 0.72%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s              | 1         | 0.72%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s              | 1         | 0.72%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                | 1         | 0.72%   |
| SK hynix RAM HMT851S6AMR6R-PB N0 4GB Chip DDR3 1600MT/s      | 1         | 0.72%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 0.72%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.72%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.72%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s       | 1         | 0.72%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 1         | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 53        | 46.09%  |
| DDR4   | 46        | 40%     |
| DDR2   | 6         | 5.22%   |
| LPDDR4 | 3         | 2.61%   |
| LPDDR3 | 3         | 2.61%   |
| SDRAM  | 2         | 1.74%   |
| DRAM   | 1         | 0.87%   |
| DDR5   | 1         | 0.87%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 107       | 93.04%  |
| Row Of Chips | 7         | 6.09%   |
| Chip         | 1         | 0.87%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 48        | 39.02%  |
| 8192  | 38        | 30.89%  |
| 16384 | 16        | 13.01%  |
| 2048  | 16        | 13.01%  |
| 1024  | 3         | 2.44%   |
| 32768 | 2         | 1.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 33        | 26.4%   |
| 2667    | 29        | 23.2%   |
| 1333    | 12        | 9.6%    |
| 3200    | 8         | 6.4%    |
| 2400    | 7         | 5.6%    |
| 1334    | 7         | 5.6%    |
| 2133    | 6         | 4.8%    |
| 667     | 5         | 4%      |
| 4267    | 3         | 2.4%    |
| 3266    | 3         | 2.4%    |
| 1067    | 3         | 2.4%    |
| Unknown | 3         | 2.4%    |
| 800     | 2         | 1.6%    |
| 4800    | 1         | 0.8%    |
| 4199    | 1         | 0.8%    |
| 1866    | 1         | 0.8%    |
| 1066    | 1         | 0.8%    |

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
| Chicony Electronics                    | 46        | 25.84%  |
| Microdia                               | 20        | 11.24%  |
| Acer                                   | 19        | 10.67%  |
| IMC Networks                           | 15        | 8.43%   |
| Sunplus Innovation Technology          | 12        | 6.74%   |
| Realtek Semiconductor                  | 12        | 6.74%   |
| Lite-On Technology                     | 9         | 5.06%   |
| Quanta                                 | 8         | 4.49%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 3.93%   |
| Syntek                                 | 4         | 2.25%   |
| Suyin                                  | 4         | 2.25%   |
| Silicon Motion                         | 3         | 1.69%   |
| Microsoft                              | 3         | 1.69%   |
| Logitech                               | 3         | 1.69%   |
| Apple                                  | 3         | 1.69%   |
| Samsung Electronics                    | 2         | 1.12%   |
| Ricoh                                  | 2         | 1.12%   |
| Alcor Micro                            | 2         | 1.12%   |
| Sunplus Technology                     | 1         | 0.56%   |
| Luxvisions Innotech Limited            | 1         | 0.56%   |
| Intel                                  | 1         | 0.56%   |
| Generalplus Technology                 | 1         | 0.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 9         | 5.06%   |
| Chicony Integrated Camera                           | 8         | 4.49%   |
| IMC Networks Integrated Camera                      | 7         | 3.93%   |
| Sunplus Integrated_Webcam_HD                        | 6         | 3.37%   |
| Chicony HD WebCam                                   | 5         | 2.81%   |
| Acer Integrated Camera                              | 5         | 2.81%   |
| Lite-On HP HD Camera                                | 4         | 2.25%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 2.25%   |
| Chicony HP TrueVision HD                            | 4         | 2.25%   |
| Acer Lenovo EasyCamera                              | 4         | 2.25%   |
| Lite-On Integrated Camera                           | 3         | 1.69%   |
| Chicony USB2.0 VGA UVC WebCam                       | 3         | 1.69%   |
| Chicony Integrated Camera (1280x720@30)             | 3         | 1.69%   |
| Chicony HP Webcam [2 MP Macro]                      | 3         | 1.69%   |
| Chicony HP HD Camera                                | 3         | 1.69%   |
| Acer HD Webcam                                      | 3         | 1.69%   |
| Suyin Integrated Webcam                             | 2         | 1.12%   |
| Samsung Galaxy A5 (MTP)                             | 2         | 1.12%   |
| Realtek Lenovo EasyCamera                           | 2         | 1.12%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.12%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 1.12%   |
| Microdia Laptop_Integrated_Webcam_2M                | 2         | 1.12%   |
| Microdia Dell Integrated HD Webcam                  | 2         | 1.12%   |
| Lite-On HP HD Webcam                                | 2         | 1.12%   |
| Chicony USB2.0 Camera                               | 2         | 1.12%   |
| Chicony Thinkpad T430 camera                        | 2         | 1.12%   |
| Chicony HP HD Webcam                                | 2         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 1.12%   |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 1.12%   |
| Syntek USB2.0 UVC PC Camera                         | 1         | 0.56%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.56%   |
| Syntek Integrated Camera                            | 1         | 0.56%   |
| Syntek EasyCamera                                   | 1         | 0.56%   |
| Suyin Sony Visual Communication Camera              | 1         | 0.56%   |
| Suyin Asus Integrated Webcam [CN031B]               | 1         | 0.56%   |
| Sunplus 1.3M WebCam                                 | 1         | 0.56%   |
| Sunplus USB Video Device                            | 1         | 0.56%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 0.56%   |
| Sunplus Integrated_Webcam_FHD                       | 1         | 0.56%   |
| Sunplus Integrated Webcam                           | 1         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 27        | 50.94%  |
| Synaptics                  | 11        | 20.75%  |
| AuthenTec                  | 5         | 9.43%   |
| Upek                       | 3         | 5.66%   |
| Shenzhen Goodix Technology | 3         | 5.66%   |
| STMicroelectronics         | 2         | 3.77%   |
| Elan Microelectronics      | 2         | 3.77%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 16.98%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 9.43%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 9.43%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 5.66%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 5.66%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 5.66%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 5.66%   |
| AuthenTec AES2810                                                          | 3         | 5.66%   |
| Validity Sensors VFS491                                                    | 2         | 3.77%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 3.77%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 3.77%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 3.77%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.77%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 3.77%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.89%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.89%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.89%   |
| Synaptics  WBDI                                                            | 1         | 1.89%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.89%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.89%   |
| Unknown                                                                    | 1         | 1.89%   |

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
| 0     | 96        | 45.93%  |
| 1     | 85        | 40.67%  |
| 2     | 21        | 10.05%  |
| 5     | 2         | 0.96%   |
| 4     | 2         | 0.96%   |
| 3     | 2         | 0.96%   |
| 6     | 1         | 0.48%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 53        | 36.81%  |
| Graphics card            | 34        | 23.61%  |
| Net/wireless             | 15        | 10.42%  |
| Chipcard                 | 13        | 9.03%   |
| Communication controller | 9         | 6.25%   |
| Multimedia controller    | 7         | 4.86%   |
| Storage                  | 3         | 2.08%   |
| Sound                    | 3         | 2.08%   |
| Net/ethernet             | 3         | 2.08%   |
| Bluetooth                | 2         | 1.39%   |
| Storage/raid             | 1         | 0.69%   |
| Camera                   | 1         | 0.69%   |

