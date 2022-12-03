Linux in Bangladesh - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Bangladesh.

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

Total: 220

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9836f71cb7](https://linux-hardware.org/?probe=9836f71cb7) | Nov 24, 2022 |
| Lenovo        | G40-70 20369                | [aafdfb20ff](https://linux-hardware.org/?probe=aafdfb20ff) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9b9a13f34f](https://linux-hardware.org/?probe=9b9a13f34f) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [4efc557c1b](https://linux-hardware.org/?probe=4efc557c1b) | Nov 24, 2022 |
| HP            | 15                          | [ab7c1e3bfd](https://linux-hardware.org/?probe=ab7c1e3bfd) | Nov 21, 2022 |
| Dell          | G7 7700                     | [2440bebe2c](https://linux-hardware.org/?probe=2440bebe2c) | Nov 15, 2022 |
| Acer          | TravelMate P214-53          | [2c342fa72f](https://linux-hardware.org/?probe=2c342fa72f) | Nov 14, 2022 |
| Acer          | Nitro AN515-57              | [b5080a1102](https://linux-hardware.org/?probe=b5080a1102) | Nov 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [104fb805bd](https://linux-hardware.org/?probe=104fb805bd) | Nov 09, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [1918990398](https://linux-hardware.org/?probe=1918990398) | Nov 07, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [a26a719002](https://linux-hardware.org/?probe=a26a719002) | Nov 05, 2022 |
| Dell          | Latitude E7240              | [2548bcefe0](https://linux-hardware.org/?probe=2548bcefe0) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [e1a32857ba](https://linux-hardware.org/?probe=e1a32857ba) | Oct 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [9357d641ef](https://linux-hardware.org/?probe=9357d641ef) | Oct 18, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [21a68d8c0e](https://linux-hardware.org/?probe=21a68d8c0e) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [ee4c1a5f66](https://linux-hardware.org/?probe=ee4c1a5f66) | Oct 03, 2022 |
| Dell          | Inspiron 14-3467            | [e92b56817a](https://linux-hardware.org/?probe=e92b56817a) | Sep 14, 2022 |
| Toshiba       | Satellite L645              | [642a6f7602](https://linux-hardware.org/?probe=642a6f7602) | Sep 03, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5ad5d3809b](https://linux-hardware.org/?probe=5ad5d3809b) | Sep 01, 2022 |
| ASUSTek       | X556UQK                     | [262ff7d08a](https://linux-hardware.org/?probe=262ff7d08a) | Aug 27, 2022 |
| ASUSTek       | GL552VW                     | [ae85f68d58](https://linux-hardware.org/?probe=ae85f68d58) | Aug 15, 2022 |
| Acer          | Aspire M5-581T              | [7efdb0e467](https://linux-hardware.org/?probe=7efdb0e467) | Aug 14, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [97f75c2be0](https://linux-hardware.org/?probe=97f75c2be0) | Aug 13, 2022 |
| Dell          | XPS 13 9380                 | [534c1142c2](https://linux-hardware.org/?probe=534c1142c2) | Aug 10, 2022 |
| Dell          | XPS 13 9380                 | [0724d34f68](https://linux-hardware.org/?probe=0724d34f68) | Aug 10, 2022 |
| Acer          | TravelMate P214-53          | [41f0d0b264](https://linux-hardware.org/?probe=41f0d0b264) | Aug 02, 2022 |
| MSI           | Modern 15 A5M               | [c6643cb779](https://linux-hardware.org/?probe=c6643cb779) | Jul 28, 2022 |
| HP            | EliteBook 840 G1            | [2dc0ffa0d1](https://linux-hardware.org/?probe=2dc0ffa0d1) | Jul 26, 2022 |
| Acer          | Nitro AN515-43              | [4e33f5e902](https://linux-hardware.org/?probe=4e33f5e902) | Jul 19, 2022 |
| HP            | 14                          | [816a62dde0](https://linux-hardware.org/?probe=816a62dde0) | Jul 07, 2022 |
| Timi          | Mi NoteBook Pro             | [046a18dc14](https://linux-hardware.org/?probe=046a18dc14) | Jul 03, 2022 |
| ASUSTek       | X507UB                      | [0ba0fc4089](https://linux-hardware.org/?probe=0ba0fc4089) | Jun 28, 2022 |
| Acer          | Aspire E5-573               | [dce8b618f8](https://linux-hardware.org/?probe=dce8b618f8) | May 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [99283be07b](https://linux-hardware.org/?probe=99283be07b) | May 20, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b85af00b16](https://linux-hardware.org/?probe=b85af00b16) | May 18, 2022 |
| Dell          | Latitude 5580               | [18cefe0718](https://linux-hardware.org/?probe=18cefe0718) | May 17, 2022 |
| Dell          | Inspiron 5505               | [c1353ba170](https://linux-hardware.org/?probe=c1353ba170) | May 15, 2022 |
| Dell          | Inspiron 5567               | [f09183023d](https://linux-hardware.org/?probe=f09183023d) | May 10, 2022 |
| HP            | 240 G3                      | [7062083e69](https://linux-hardware.org/?probe=7062083e69) | May 06, 2022 |
| HP            | EliteBook 840 G3            | [88f6586c4b](https://linux-hardware.org/?probe=88f6586c4b) | May 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ab11d6ac2f](https://linux-hardware.org/?probe=ab11d6ac2f) | Apr 28, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [19623aa8b6](https://linux-hardware.org/?probe=19623aa8b6) | Apr 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [287aa3ba8e](https://linux-hardware.org/?probe=287aa3ba8e) | Apr 07, 2022 |
| HP            | ZHAN 66 Pro A 14 G4 Note... | [8199781e64](https://linux-hardware.org/?probe=8199781e64) | Mar 28, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [321d0c1b4a](https://linux-hardware.org/?probe=321d0c1b4a) | Mar 23, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [5db5bac582](https://linux-hardware.org/?probe=5db5bac582) | Mar 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [da23c76a90](https://linux-hardware.org/?probe=da23c76a90) | Mar 19, 2022 |
| HP            | ProBook 450 G4              | [87d97b3c00](https://linux-hardware.org/?probe=87d97b3c00) | Mar 05, 2022 |
| Acer          | TravelMate P214-53          | [87f30f494f](https://linux-hardware.org/?probe=87f30f494f) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [62c028a881](https://linux-hardware.org/?probe=62c028a881) | Feb 16, 2022 |
| HP            | ProBook 440 G6              | [d7431ab69e](https://linux-hardware.org/?probe=d7431ab69e) | Jan 31, 2022 |
| Dell          | XPS 13 9360                 | [76d17811e3](https://linux-hardware.org/?probe=76d17811e3) | Jan 31, 2022 |
| Lenovo        | ThinkPad X230 2324A82       | [be92c29259](https://linux-hardware.org/?probe=be92c29259) | Jan 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1e89749691](https://linux-hardware.org/?probe=1e89749691) | Jan 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [88f62c8333](https://linux-hardware.org/?probe=88f62c8333) | Jan 15, 2022 |
| HP            | ProBook 450 G4              | [38a7870ece](https://linux-hardware.org/?probe=38a7870ece) | Jan 13, 2022 |
| Dell          | Inspiron N5110              | [2fb0411785](https://linux-hardware.org/?probe=2fb0411785) | Jan 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [0d69dca8f3](https://linux-hardware.org/?probe=0d69dca8f3) | Jan 04, 2022 |
| HP            | Laptop 14s-dq2xxx           | [8e8da56e93](https://linux-hardware.org/?probe=8e8da56e93) | Jan 01, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [00696e3398](https://linux-hardware.org/?probe=00696e3398) | Dec 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [d347eea0b2](https://linux-hardware.org/?probe=d347eea0b2) | Dec 19, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [5cf5b44fc8](https://linux-hardware.org/?probe=5cf5b44fc8) | Dec 13, 2021 |
| Dell          | Inspiron 5468               | [ff0b877d5a](https://linux-hardware.org/?probe=ff0b877d5a) | Dec 08, 2021 |
| Dell          | Latitude 7480               | [480ad981d9](https://linux-hardware.org/?probe=480ad981d9) | Dec 07, 2021 |
| HP            | ProBook 450 G4              | [42edbb20ce](https://linux-hardware.org/?probe=42edbb20ce) | Dec 04, 2021 |
| HP            | EliteBook 8460p             | [07bcad31f5](https://linux-hardware.org/?probe=07bcad31f5) | Dec 02, 2021 |
| ASUSTek       | UX430UQ                     | [cf0cd5c862](https://linux-hardware.org/?probe=cf0cd5c862) | Dec 01, 2021 |
| ASUSTek       | UX430UQ                     | [5cd208a361](https://linux-hardware.org/?probe=5cd208a361) | Dec 01, 2021 |
| ASUSTek       | P453UJ                      | [056cba6efd](https://linux-hardware.org/?probe=056cba6efd) | Nov 28, 2021 |
| HP            | Pavilion Notebook           | [aa0a0e67b3](https://linux-hardware.org/?probe=aa0a0e67b3) | Nov 26, 2021 |
| HP            | Pavilion Notebook           | [9bffff74e0](https://linux-hardware.org/?probe=9bffff74e0) | Nov 26, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [623b2b0ba9](https://linux-hardware.org/?probe=623b2b0ba9) | Nov 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f1f7ca30e5](https://linux-hardware.org/?probe=f1f7ca30e5) | Nov 05, 2021 |
| ASUSTek       | X442UAR                     | [0db140fa3d](https://linux-hardware.org/?probe=0db140fa3d) | Nov 03, 2021 |
| HP            | ProBook 450 G5              | [d377aa2b23](https://linux-hardware.org/?probe=d377aa2b23) | Oct 17, 2021 |
| HP            | ProBook 450 G5              | [7447071c00](https://linux-hardware.org/?probe=7447071c00) | Oct 16, 2021 |
| HP            | ProBook 450 G5              | [0bf0387391](https://linux-hardware.org/?probe=0bf0387391) | Oct 07, 2021 |
| Acer          | Aspire V5-471               | [6a5bc4355e](https://linux-hardware.org/?probe=6a5bc4355e) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | [4b9f0ceb64](https://linux-hardware.org/?probe=4b9f0ceb64) | Oct 05, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | [883e0dec71](https://linux-hardware.org/?probe=883e0dec71) | Sep 19, 2021 |
| Dell          | Latitude E7250              | [275b9204f5](https://linux-hardware.org/?probe=275b9204f5) | Sep 13, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | [6a9842e166](https://linux-hardware.org/?probe=6a9842e166) | Sep 06, 2021 |
| ASUSTek       | X456UQ                      | [6ce8e44ad3](https://linux-hardware.org/?probe=6ce8e44ad3) | Sep 02, 2021 |
| Acer          | Aspire 4349                 | [527e511232](https://linux-hardware.org/?probe=527e511232) | Aug 27, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [48853e253b](https://linux-hardware.org/?probe=48853e253b) | Aug 04, 2021 |
| HP            | EliteBook 840 G3            | [c672738a0e](https://linux-hardware.org/?probe=c672738a0e) | Aug 04, 2021 |
| ASUSTek       | VivoBook S15 X530UA         | [c22e4ce5b4](https://linux-hardware.org/?probe=c22e4ce5b4) | Jul 29, 2021 |
| HP            | 250 G7 Notebook PC          | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| Unknown       | Unknown                     | [1f6b072c8e](https://linux-hardware.org/?probe=1f6b072c8e) | Jul 24, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [dd58ecd9c7](https://linux-hardware.org/?probe=dd58ecd9c7) | Jul 23, 2021 |
| ASUSTek       | X550JK                      | [ebd01f2605](https://linux-hardware.org/?probe=ebd01f2605) | Jul 22, 2021 |
| Dell          | Inspiron 3442               | [3b153ae2f9](https://linux-hardware.org/?probe=3b153ae2f9) | Jun 24, 2021 |
| Dell          | Inspiron 3442               | [988fc9a599](https://linux-hardware.org/?probe=988fc9a599) | Jun 24, 2021 |
| HP            | 15                          | [4f6c5d8c89](https://linux-hardware.org/?probe=4f6c5d8c89) | Jun 22, 2021 |
| HP            | Laptop 14-ck0xxx            | [406cb898f1](https://linux-hardware.org/?probe=406cb898f1) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| ASUSTek       | UX310UAK                    | [4a79148721](https://linux-hardware.org/?probe=4a79148721) | Jun 03, 2021 |
| HP            | Laptop 14-ck0xxx            | [6b5f1170f9](https://linux-hardware.org/?probe=6b5f1170f9) | Jun 02, 2021 |
| HP            | Laptop 14-ck0xxx            | [e2389864db](https://linux-hardware.org/?probe=e2389864db) | Jun 02, 2021 |
| HP            | ENVY TS 14 Sleekbook        | [f52091e51e](https://linux-hardware.org/?probe=f52091e51e) | May 31, 2021 |
| HP            | 15 Notebook PC              | [b34d6d63d9](https://linux-hardware.org/?probe=b34d6d63d9) | May 22, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | [8f1510061b](https://linux-hardware.org/?probe=8f1510061b) | May 18, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | [e78b76fcf3](https://linux-hardware.org/?probe=e78b76fcf3) | May 18, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [b7e4895fd8](https://linux-hardware.org/?probe=b7e4895fd8) | May 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [1254eab2b7](https://linux-hardware.org/?probe=1254eab2b7) | May 04, 2021 |
| HP            | 15                          | [fd4d562cd2](https://linux-hardware.org/?probe=fd4d562cd2) | May 04, 2021 |
| MSI           | Summit B14 A11MOT           | [9bdd91f198](https://linux-hardware.org/?probe=9bdd91f198) | May 02, 2021 |
| HP            | ProBook 440 G7              | [dbcbb68258](https://linux-hardware.org/?probe=dbcbb68258) | Apr 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [367455807e](https://linux-hardware.org/?probe=367455807e) | Mar 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1de185d0da](https://linux-hardware.org/?probe=1de185d0da) | Mar 22, 2021 |
| Dell          | Latitude E4300              | [2ccfcf6a1b](https://linux-hardware.org/?probe=2ccfcf6a1b) | Mar 22, 2021 |
| HP            | 15                          | [860412bddc](https://linux-hardware.org/?probe=860412bddc) | Mar 20, 2021 |
| HP            | 15                          | [62447250f9](https://linux-hardware.org/?probe=62447250f9) | Mar 17, 2021 |
| Lenovo        | ThinkPad E490 20N9S1XE00    | [4ee1271923](https://linux-hardware.org/?probe=4ee1271923) | Mar 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [6343267ab7](https://linux-hardware.org/?probe=6343267ab7) | Mar 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [47123299d4](https://linux-hardware.org/?probe=47123299d4) | Mar 09, 2021 |
| HP            | ProBook 450 G4              | [a8091a8c28](https://linux-hardware.org/?probe=a8091a8c28) | Mar 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8f8fe2c911](https://linux-hardware.org/?probe=8f8fe2c911) | Mar 06, 2021 |
| ASUSTek       | X411UNV                     | [009f3bb5e5](https://linux-hardware.org/?probe=009f3bb5e5) | Feb 27, 2021 |
| HP            | 15                          | [e74fa488e9](https://linux-hardware.org/?probe=e74fa488e9) | Feb 27, 2021 |
| Apple         | MacBookPro8,1               | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| HP            | EliteBook 8470p             | [b414109f66](https://linux-hardware.org/?probe=b414109f66) | Feb 07, 2021 |
| HP            | EliteBook 8470p             | [08a1160725](https://linux-hardware.org/?probe=08a1160725) | Feb 07, 2021 |
| HP            | Notebook                    | [df39c8aaf8](https://linux-hardware.org/?probe=df39c8aaf8) | Feb 02, 2021 |
| ASUSTek       | X45C                        | [349beec2d5](https://linux-hardware.org/?probe=349beec2d5) | Jan 27, 2021 |
| HP            | ProBook 450 G2              | [c9e8f99464](https://linux-hardware.org/?probe=c9e8f99464) | Jan 21, 2021 |
| Lenovo        | ThinkPad T450 20BUS2021M    | [60929bb3d1](https://linux-hardware.org/?probe=60929bb3d1) | Jan 21, 2021 |
| HP            | Notebook                    | [d14d8fe5db](https://linux-hardware.org/?probe=d14d8fe5db) | Jan 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [5ee0809420](https://linux-hardware.org/?probe=5ee0809420) | Jan 16, 2021 |
| HP            | 15                          | [1b3597829c](https://linux-hardware.org/?probe=1b3597829c) | Jan 05, 2021 |
| HP            | ProBook 450 G4              | [150aed5937](https://linux-hardware.org/?probe=150aed5937) | Dec 28, 2020 |
| Acer          | Aspire A315-21              | [f3aaccf16d](https://linux-hardware.org/?probe=f3aaccf16d) | Dec 19, 2020 |
| HP            | ProBook 450 G2              | [eff007611b](https://linux-hardware.org/?probe=eff007611b) | Dec 16, 2020 |
| Acer          | Aspire A315-21              | [1eec63b277](https://linux-hardware.org/?probe=1eec63b277) | Dec 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [da59a1c5a8](https://linux-hardware.org/?probe=da59a1c5a8) | Dec 07, 2020 |
| MSI           | GS63 7RD                    | [51929f5d16](https://linux-hardware.org/?probe=51929f5d16) | Dec 05, 2020 |
| HP            | ProBook 450 G2              | [4d0297d500](https://linux-hardware.org/?probe=4d0297d500) | Nov 15, 2020 |
| HP            | ProBook 450 G2              | [2898db77af](https://linux-hardware.org/?probe=2898db77af) | Nov 14, 2020 |
| Acer          | Nitro AN515-43              | [399693b152](https://linux-hardware.org/?probe=399693b152) | Nov 04, 2020 |
| HP            | 15                          | [751dbba280](https://linux-hardware.org/?probe=751dbba280) | Nov 04, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [20da8831d7](https://linux-hardware.org/?probe=20da8831d7) | Oct 29, 2020 |
| Notebook      | DCL C483                    | [ed2bb10c86](https://linux-hardware.org/?probe=ed2bb10c86) | Oct 29, 2020 |
| HP            | ENVY Sleekbook 4            | [b2377a6388](https://linux-hardware.org/?probe=b2377a6388) | Oct 29, 2020 |
| Dell          | Inspiron 3521               | [c85f72911e](https://linux-hardware.org/?probe=c85f72911e) | Oct 29, 2020 |
| Acer          | Aspire E5-576               | [1f7d96b34a](https://linux-hardware.org/?probe=1f7d96b34a) | Oct 27, 2020 |
| ASUSTek       | P453UA                      | [a376addbeb](https://linux-hardware.org/?probe=a376addbeb) | Oct 21, 2020 |
| Acer          | Aspire E5-575               | [218b3ce742](https://linux-hardware.org/?probe=218b3ce742) | Oct 12, 2020 |
| Acer          | Nitro AN515-43              | [da1765fe36](https://linux-hardware.org/?probe=da1765fe36) | Oct 11, 2020 |
| Acer          | Aspire A515-51G             | [be8091856c](https://linux-hardware.org/?probe=be8091856c) | Oct 09, 2020 |
| Acer          | Nitro AN515-43              | [a6f1865423](https://linux-hardware.org/?probe=a6f1865423) | Oct 07, 2020 |
| ASUSTek       | X510UQ                      | [75933321b6](https://linux-hardware.org/?probe=75933321b6) | Oct 02, 2020 |
| Acer          | Aspire 4752                 | [ae7fe5907d](https://linux-hardware.org/?probe=ae7fe5907d) | Sep 27, 2020 |
| ASUSTek       | X555LF                      | [ed0ef70a05](https://linux-hardware.org/?probe=ed0ef70a05) | Sep 19, 2020 |
| HP            | ProBook 440 G5              | [d7b1ce1a01](https://linux-hardware.org/?probe=d7b1ce1a01) | Sep 15, 2020 |
| Notebook      | N2x0LU                      | [86354a1c26](https://linux-hardware.org/?probe=86354a1c26) | Sep 14, 2020 |
| ASUSTek       | X510UQ                      | [e289d19d20](https://linux-hardware.org/?probe=e289d19d20) | Sep 14, 2020 |
| ASUSTek       | X555LF                      | [22629ba9b2](https://linux-hardware.org/?probe=22629ba9b2) | Sep 07, 2020 |
| Lenovo        | ThinkPad E490 20N9S1XE00    | [43ddcf3c95](https://linux-hardware.org/?probe=43ddcf3c95) | Sep 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [38548d7877](https://linux-hardware.org/?probe=38548d7877) | Sep 01, 2020 |
| Acer          | Aspire A315-21              | [3edf866f94](https://linux-hardware.org/?probe=3edf866f94) | Aug 22, 2020 |
| Acer          | Aspire E5-576               | [3a9beeb9f4](https://linux-hardware.org/?probe=3a9beeb9f4) | Aug 16, 2020 |
| HP            | ProBook 450 G4              | [3c3b21f81b](https://linux-hardware.org/?probe=3c3b21f81b) | Aug 15, 2020 |
| HP            | 14                          | [b7289075c1](https://linux-hardware.org/?probe=b7289075c1) | Aug 08, 2020 |
| HP            | EliteBook 850 G2            | [1c81c3c24d](https://linux-hardware.org/?probe=1c81c3c24d) | Jul 30, 2020 |
| Acer          | Aspire E5-473               | [27a9cd08a6](https://linux-hardware.org/?probe=27a9cd08a6) | Jul 26, 2020 |
| Acer          | Aspire E5-473               | [9c3656a710](https://linux-hardware.org/?probe=9c3656a710) | Jul 24, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [3c50b289eb](https://linux-hardware.org/?probe=3c50b289eb) | Jul 21, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [e800855127](https://linux-hardware.org/?probe=e800855127) | Jul 21, 2020 |
| Dell          | Latitude E7470              | [74e59971a2](https://linux-hardware.org/?probe=74e59971a2) | Jul 09, 2020 |
| ASUSTek       | X200CA                      | [eb79a1863c](https://linux-hardware.org/?probe=eb79a1863c) | Jul 08, 2020 |
| ASUSTek       | X200CA                      | [374493e07f](https://linux-hardware.org/?probe=374493e07f) | Jul 08, 2020 |
| HP            | EliteBook 2570p             | [04f260c99a](https://linux-hardware.org/?probe=04f260c99a) | Jul 06, 2020 |
| HP            | EliteBook 2570p             | [aa5a987949](https://linux-hardware.org/?probe=aa5a987949) | Jul 06, 2020 |
| Acer          | Aspire A315-21              | [e8be3d4a45](https://linux-hardware.org/?probe=e8be3d4a45) | Jul 02, 2020 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | [bedb334316](https://linux-hardware.org/?probe=bedb334316) | Jun 11, 2020 |
| Acer          | Aspire A315-21              | [0690307575](https://linux-hardware.org/?probe=0690307575) | Jun 06, 2020 |
| Acer          | Aspire A315-21              | [2d68573dcb](https://linux-hardware.org/?probe=2d68573dcb) | Jun 04, 2020 |
| HP            | ProBook 450 G4              | [e10a133997](https://linux-hardware.org/?probe=e10a133997) | Jun 02, 2020 |
| HP            | ProBook 450 G4              | [7b57cf3668](https://linux-hardware.org/?probe=7b57cf3668) | May 30, 2020 |
| HP            | Notebook                    | [024a28eb0b](https://linux-hardware.org/?probe=024a28eb0b) | May 23, 2020 |
| Dell          | Latitude E7450              | [f3e9ca7a40](https://linux-hardware.org/?probe=f3e9ca7a40) | May 21, 2020 |
| Lenovo        | ThinkPad E470 20H1A029SG    | [6afaed7f7f](https://linux-hardware.org/?probe=6afaed7f7f) | May 21, 2020 |
| Dell          | Latitude E7450              | [e6818ffd7d](https://linux-hardware.org/?probe=e6818ffd7d) | May 21, 2020 |
| Notebook      | W9x0LU                      | [c7455fcb18](https://linux-hardware.org/?probe=c7455fcb18) | May 17, 2020 |
| Lenovo        | V330-14IKB 81B0             | [5d81beb457](https://linux-hardware.org/?probe=5d81beb457) | May 17, 2020 |
| ASUSTek       | X510UNR                     | [7b1a18ebf9](https://linux-hardware.org/?probe=7b1a18ebf9) | May 09, 2020 |
| ASUSTek       | X556URK                     | [63c6b5a357](https://linux-hardware.org/?probe=63c6b5a357) | May 08, 2020 |
| Notebook      | N750BU                      | [e3f870729f](https://linux-hardware.org/?probe=e3f870729f) | Apr 23, 2020 |
| HP            | Mini 210-4000               | [61c0ab33d8](https://linux-hardware.org/?probe=61c0ab33d8) | Feb 28, 2020 |
| HP            | ProBook 450 G4              | [729f8e494d](https://linux-hardware.org/?probe=729f8e494d) | Feb 14, 2020 |
| Dell          | Inspiron 13-5378            | [357823f120](https://linux-hardware.org/?probe=357823f120) | Feb 03, 2020 |
| HP            | ProBook 450 G4              | [e9a4da7f1c](https://linux-hardware.org/?probe=e9a4da7f1c) | Jan 31, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [4fad937155](https://linux-hardware.org/?probe=4fad937155) | Jan 10, 2020 |
| Lenovo        | ThinkPad L380 20M6S22500    | [15c43def70](https://linux-hardware.org/?probe=15c43def70) | Jan 09, 2020 |
| Dell          | Inspiron 5559               | [9d4e0d1911](https://linux-hardware.org/?probe=9d4e0d1911) | Jan 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [2d0bca85ea](https://linux-hardware.org/?probe=2d0bca85ea) | Dec 29, 2019 |
| HP            | ProBook 450 G4              | [d85b25cd22](https://linux-hardware.org/?probe=d85b25cd22) | Dec 24, 2019 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [30c00cb837](https://linux-hardware.org/?probe=30c00cb837) | Dec 14, 2019 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [e004d9f500](https://linux-hardware.org/?probe=e004d9f500) | Dec 14, 2019 |
| ASUSTek       | E202SA                      | [e052cf247b](https://linux-hardware.org/?probe=e052cf247b) | Nov 23, 2019 |
| HP            | ProBook 450 G4              | [44d09b2105](https://linux-hardware.org/?probe=44d09b2105) | Nov 19, 2019 |
| HP            | ProBook 450 G4              | [3fc910f23c](https://linux-hardware.org/?probe=3fc910f23c) | Nov 19, 2019 |
| Acer          | Aspire E5-571G              | [afc9fdb4b3](https://linux-hardware.org/?probe=afc9fdb4b3) | Nov 14, 2019 |
| Acer          | Aspire E5-571G              | [7914862967](https://linux-hardware.org/?probe=7914862967) | Nov 14, 2019 |
| HP            | ProBook 450 G1              | [671ea53b31](https://linux-hardware.org/?probe=671ea53b31) | Sep 22, 2019 |
| HP            | ProBook 450 G1              | [53b4bf1914](https://linux-hardware.org/?probe=53b4bf1914) | Sep 22, 2019 |
| ASUSTek       | X441UA                      | [6022620aee](https://linux-hardware.org/?probe=6022620aee) | Sep 17, 2019 |
| ASUSTek       | X441UA                      | [d0632368ab](https://linux-hardware.org/?probe=d0632368ab) | Sep 04, 2019 |
| HP            | Notebook                    | [2ce0b2ff35](https://linux-hardware.org/?probe=2ce0b2ff35) | Jul 04, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [298e510c05](https://linux-hardware.org/?probe=298e510c05) | Jun 22, 2019 |
| Lenovo        | ThinkPad X230 2324F51       | [9291e8f5f3](https://linux-hardware.org/?probe=9291e8f5f3) | Jun 22, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [70fecd4e42](https://linux-hardware.org/?probe=70fecd4e42) | Jun 04, 2019 |
| Acer          | Aspire A515-51              | [ee5c9fcc02](https://linux-hardware.org/?probe=ee5c9fcc02) | Jun 04, 2019 |
| Acer          | Aspire A515-51              | [424ee39d57](https://linux-hardware.org/?probe=424ee39d57) | Jun 04, 2019 |
| Lenovo        | S10-3                       | [09f132c2fa](https://linux-hardware.org/?probe=09f132c2fa) | May 27, 2019 |
| Daffodil C... | DCL S4                      | [291cd2445c](https://linux-hardware.org/?probe=291cd2445c) | May 08, 2019 |
| HP            | ProBook 4540s               | [a8b0fbe3a8](https://linux-hardware.org/?probe=a8b0fbe3a8) | Apr 22, 2019 |
| ASUSTek       | X510UQ                      | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 35        | 21.21%  |
| Arch                         | 9         | 5.45%   |
| ArcoLinux Rolling            | 8         | 4.85%   |
| KDE neon 20.04               | 5         | 3.03%   |
| Ubuntu 19.10                 | 4         | 2.42%   |
| Ubuntu 18.04                 | 4         | 2.42%   |
| Manjaro                      | 4         | 2.42%   |
| Fedora 33                    | 4         | 2.42%   |
| Arch Rolling                 | 4         | 2.42%   |
| Zorin 16                     | 3         | 1.82%   |
| Pop!_OS 22.04                | 3         | 1.82%   |
| OpenMandriva 4.2             | 3         | 1.82%   |
| Manjaro 20.0.1               | 3         | 1.82%   |
| Debian 11                    | 3         | 1.82%   |
| Zorin 15                     | 2         | 1.21%   |
| Ubuntu 22.04                 | 2         | 1.21%   |
| Ubuntu 19.04                 | 2         | 1.21%   |
| Ubuntu 18.10                 | 2         | 1.21%   |
| Pop!_OS 21.10                | 2         | 1.21%   |
| OpenMandriva 4.90            | 2         | 1.21%   |
| Manjaro 21.2.6               | 2         | 1.21%   |
| Manjaro 18.0.4               | 2         | 1.21%   |
| Linux Mint 20.1              | 2         | 1.21%   |
| Linux Mint 20                | 2         | 1.21%   |
| Kubuntu 20.04                | 2         | 1.21%   |
| Kali 2022.3                  | 2         | 1.21%   |
| Fedora 34                    | 2         | 1.21%   |
| EndeavourOS Rolling          | 2         | 1.21%   |
| Ubuntu Unity 16.04           | 1         | 0.61%   |
| Ubuntu 21.04                 | 1         | 0.61%   |
| Ubuntu 20.10                 | 1         | 0.61%   |
| Pop!_OS 21.04                | 1         | 0.61%   |
| Pop!_OS 20.10                | 1         | 0.61%   |
| Parrot 5.1                   | 1         | 0.61%   |
| Parrot 4.5                   | 1         | 0.61%   |
| Parrot 4.11                  | 1         | 0.61%   |
| Parrot 4.10                  | 1         | 0.61%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.61%   |
| Manjaro 21.2.1               | 1         | 0.61%   |
| Manjaro 21.1.2               | 1         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 50        | 32.68%  |
| Manjaro      | 17        | 11.11%  |
| Arch         | 12        | 7.84%   |
| Linux Mint   | 8         | 5.23%   |
| ArcoLinux    | 8         | 5.23%   |
| Pop!_OS      | 7         | 4.58%   |
| Fedora       | 7         | 4.58%   |
| Zorin        | 5         | 3.27%   |
| OpenMandriva | 5         | 3.27%   |
| KDE neon     | 5         | 3.27%   |
| Endless      | 5         | 3.27%   |
| Kubuntu      | 4         | 2.61%   |
| Debian       | 4         | 2.61%   |
| Parrot       | 3         | 1.96%   |
| EndeavourOS  | 3         | 1.96%   |
| Kali         | 2         | 1.31%   |
| Ubuntu Unity | 1         | 0.65%   |
| openSUSE     | 1         | 0.65%   |
| LMDE         | 1         | 0.65%   |
| Deepin       | 1         | 0.65%   |
| Clear Linux  | 1         | 0.65%   |
| CentOS       | 1         | 0.65%   |
| BlackPanther | 1         | 0.65%   |
| Artix        | 1         | 0.65%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 7         | 3.87%   |
| 5.4.0-52-generic         | 3         | 1.66%   |
| 5.4.0-40-generic         | 3         | 1.66%   |
| 5.4.0-29-generic         | 3         | 1.66%   |
| 5.10.14-desktop-1omv4002 | 3         | 1.66%   |
| 6.0.9-zen1-1-zen         | 2         | 1.1%    |
| 5.9.16-1-MANJARO         | 2         | 1.1%    |
| 5.8.0-50-generic         | 2         | 1.1%    |
| 5.8.0-41-generic         | 2         | 1.1%    |
| 5.8.0-14-generic         | 2         | 1.1%    |
| 5.7.19-2-MANJARO         | 2         | 1.1%    |
| 5.6.11-1-MANJARO         | 2         | 1.1%    |
| 5.4.8-arch1-1            | 2         | 1.1%    |
| 5.4.0-53-generic         | 2         | 1.1%    |
| 5.4.0-19-generic         | 2         | 1.1%    |
| 5.3.0-24-generic         | 2         | 1.1%    |
| 5.3.0-23-generic         | 2         | 1.1%    |
| 5.19.0-kali2-amd64       | 2         | 1.1%    |
| 5.18.12-desktop-3omv4090 | 2         | 1.1%    |
| 5.15.0-48-generic        | 2         | 1.1%    |
| 5.15.0-46-generic        | 2         | 1.1%    |
| 5.13.0-28-generic        | 2         | 1.1%    |
| 5.11.0-40-generic        | 2         | 1.1%    |
| 5.11.0-27-generic        | 2         | 1.1%    |
| 5.10.52-1-lts            | 2         | 1.1%    |
| 6.0.2-76060002-generic   | 1         | 0.55%   |
| 6.0.0-2parrot1-amd64     | 1         | 0.55%   |
| 5.9.16-200.fc33.x86_64   | 1         | 0.55%   |
| 5.9.11-200.fc33.x86_64   | 1         | 0.55%   |
| 5.8.4-200.fc32.x86_64    | 1         | 0.55%   |
| 5.8.16.a-1-hardened      | 1         | 0.55%   |
| 5.8.12-1-default         | 1         | 0.55%   |
| 5.8.0-7630-generic       | 1         | 0.55%   |
| 5.8.0-63-generic         | 1         | 0.55%   |
| 5.8.0-55-generic         | 1         | 0.55%   |
| 5.8.0-44-generic         | 1         | 0.55%   |
| 5.8.0-43-generic         | 1         | 0.55%   |
| 5.8.0-40-generic         | 1         | 0.55%   |
| 5.8.0-38-generic         | 1         | 0.55%   |
| 5.7.0-2parrot2-amd64     | 1         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 28        | 16.28%  |
| 5.8.0   | 13        | 7.56%   |
| 5.11.0  | 12        | 6.98%   |
| 5.13.0  | 8         | 4.65%   |
| 5.15.0  | 7         | 4.07%   |
| 5.3.0   | 6         | 3.49%   |
| 5.10.0  | 5         | 2.91%   |
| 5.0.0   | 4         | 2.33%   |
| 4.18.0  | 4         | 2.33%   |
| 4.15.0  | 4         | 2.33%   |
| 5.9.16  | 3         | 1.74%   |
| 5.19.0  | 3         | 1.74%   |
| 5.18.12 | 3         | 1.74%   |
| 5.10.14 | 3         | 1.74%   |
| 4.19.0  | 3         | 1.74%   |
| 6.0.9   | 2         | 1.16%   |
| 5.7.19  | 2         | 1.16%   |
| 5.6.11  | 2         | 1.16%   |
| 5.4.8   | 2         | 1.16%   |
| 5.16.15 | 2         | 1.16%   |
| 5.15.5  | 2         | 1.16%   |
| 5.10.52 | 2         | 1.16%   |
| 6.0.2   | 1         | 0.58%   |
| 6.0.0   | 1         | 0.58%   |
| 5.9.11  | 1         | 0.58%   |
| 5.8.4   | 1         | 0.58%   |
| 5.8.16  | 1         | 0.58%   |
| 5.8.12  | 1         | 0.58%   |
| 5.7.0   | 1         | 0.58%   |
| 5.4.81  | 1         | 0.58%   |
| 5.4.68  | 1         | 0.58%   |
| 5.4.64  | 1         | 0.58%   |
| 5.4.40  | 1         | 0.58%   |
| 5.4.15  | 1         | 0.58%   |
| 5.19.9  | 1         | 0.58%   |
| 5.19.4  | 1         | 0.58%   |
| 5.18.6  | 1         | 0.58%   |
| 5.18.16 | 1         | 0.58%   |
| 5.18.10 | 1         | 0.58%   |
| 5.17.9  | 1         | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 20.61%  |
| 5.8     | 16        | 9.7%    |
| 5.15    | 16        | 9.7%    |
| 5.11    | 15        | 9.09%   |
| 5.10    | 14        | 8.48%   |
| 5.13    | 9         | 5.45%   |
| 5.3     | 6         | 3.64%   |
| 5.18    | 6         | 3.64%   |
| 5.19    | 5         | 3.03%   |
| 5.16    | 5         | 3.03%   |
| 4.18    | 5         | 3.03%   |
| 6.0     | 4         | 2.42%   |
| 5.9     | 4         | 2.42%   |
| 5.0     | 4         | 2.42%   |
| 4.19    | 4         | 2.42%   |
| 4.15    | 4         | 2.42%   |
| 5.7     | 3         | 1.82%   |
| 5.17    | 3         | 1.82%   |
| 5.6     | 2         | 1.21%   |
| 5.14    | 2         | 1.21%   |
| 5.12    | 2         | 1.21%   |
| 5.1     | 2         | 1.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 148       | 98.67%  |
| i686   | 2         | 1.33%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| GNOME          | 78        | 50.32%  |
| KDE5           | 29        | 18.71%  |
| Unknown        | 17        | 10.97%  |
| XFCE           | 8         | 5.16%   |
| X-Cinnamon     | 7         | 4.52%   |
| MATE           | 3         | 1.94%   |
| awesome        | 3         | 1.94%   |
| KDE            | 2         | 1.29%   |
| i3-with-shmlog | 2         | 1.29%   |
| Unity          | 1         | 0.65%   |
| LXDE           | 1         | 0.65%   |
| i3             | 1         | 0.65%   |
| DWM            | 1         | 0.65%   |
| Deepin         | 1         | 0.65%   |
| bspwm          | 1         | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 127       | 81.94%  |
| Wayland | 18        | 11.61%  |
| Unknown | 9         | 5.81%   |
| Tty     | 1         | 0.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 77        | 49.68%  |
| GDM     | 26        | 16.77%  |
| SDDM    | 23        | 14.84%  |
| LightDM | 13        | 8.39%   |
| GDM3    | 10        | 6.45%   |
| TDM     | 6         | 3.87%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 125       | 82.24%  |
| Unknown | 15        | 9.87%   |
| en_GB   | 4         | 2.63%   |
| C       | 4         | 2.63%   |
| en_IE   | 1         | 0.66%   |
| en_EN   | 1         | 0.66%   |
| en_CA   | 1         | 0.66%   |
| en_AG   | 1         | 0.66%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 81        | 52.6%   |
| BIOS | 73        | 47.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 122       | 80.79%  |
| Overlay | 13        | 8.61%   |
| Btrfs   | 12        | 7.95%   |
| Unknown | 3         | 1.99%   |
| Xfs     | 1         | 0.66%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 87        | 56.13%  |
| GPT     | 54        | 34.84%  |
| MBR     | 14        | 9.03%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 131       | 86.18%  |
| Yes       | 21        | 13.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 85        | 55.92%  |
| Yes       | 67        | 44.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 42        | 28%     |
| Hewlett-Packard     | 40        | 26.67%  |
| Lenovo              | 19        | 12.67%  |
| Dell                | 19        | 12.67%  |
| Acer                | 16        | 10.67%  |
| Notebook            | 4         | 2.67%   |
| MSI                 | 3         | 2%      |
| Toshiba             | 1         | 0.67%   |
| Timi                | 1         | 0.67%   |
| Samsung Electronics | 1         | 0.67%   |
| Fujitsu             | 1         | 0.67%   |
| Daffodil Computers  | 1         | 0.67%   |
| Apple               | 1         | 0.67%   |
| Unknown             | 1         | 0.67%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP ProBook 450 G4                                     | 5         | 3.33%   |
| HP ProBook 450 G2                                     | 2         | 1.33%   |
| HP ProBook 440 G8 Notebook PC                         | 2         | 1.33%   |
| HP Notebook                                           | 2         | 1.33%   |
| HP EliteBook 840 G3                                   | 2         | 1.33%   |
| HP 15                                                 | 2         | 1.33%   |
| HP 14                                                 | 2         | 1.33%   |
| ASUS X510UQ                                           | 2         | 1.33%   |
| ASUS VivoBook_ASUSLaptop X531FL_S531FL                | 2         | 1.33%   |
| ASUS VivoBook_ASUSLaptop X530FN_S530FN                | 2         | 1.33%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA                | 2         | 1.33%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA                | 2         | 1.33%   |
| ASUS VivoBook 14_ASUS Laptop X407UA                   | 2         | 1.33%   |
| Acer Nitro AN515-43                                   | 2         | 1.33%   |
| Toshiba Satellite L645                                | 1         | 0.67%   |
| Timi Mi NoteBook Pro                                  | 1         | 0.67%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.67%   |
| Notebook W9x0LU                                       | 1         | 0.67%   |
| Notebook N750BU                                       | 1         | 0.67%   |
| Notebook N2x0LU                                       | 1         | 0.67%   |
| Notebook DCL C483                                     | 1         | 0.67%   |
| MSI Summit B14 A11MOT                                 | 1         | 0.67%   |
| MSI Modern 15 A5M                                     | 1         | 0.67%   |
| MSI GS63 7RD                                          | 1         | 0.67%   |
| Lenovo V330-14IKB 81B0                                | 1         | 0.67%   |
| Lenovo ThinkPad X230 2324F51                          | 1         | 0.67%   |
| Lenovo ThinkPad X230 2324A82                          | 1         | 0.67%   |
| Lenovo ThinkPad T450 20BUS2021M                       | 1         | 0.67%   |
| Lenovo ThinkPad T430s 2356GPU                         | 1         | 0.67%   |
| Lenovo ThinkPad L380 20M6S22500                       | 1         | 0.67%   |
| Lenovo ThinkPad E490 20N9S1XE00                       | 1         | 0.67%   |
| Lenovo ThinkPad E470 20H1A029SG                       | 1         | 0.67%   |
| Lenovo S10-3                                          | 1         | 0.67%   |
| Lenovo Legion 5 15ARH05H 82B1                         | 1         | 0.67%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7                      | 1         | 0.67%   |
| Lenovo IdeaPad 330-15IKB 81DE                         | 1         | 0.67%   |
| Lenovo IdeaPad 320-15IKB 81BG                         | 1         | 0.67%   |
| Lenovo IdeaPad 320-15IKB 80XL                         | 1         | 0.67%   |
| Lenovo IdeaPad 310-14ISK 80SL                         | 1         | 0.67%   |
| Lenovo IdeaPad 3 15ITL6 82H8                          | 1         | 0.67%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| ASUS VivoBook          | 19        | 12.67%  |
| HP ProBook             | 16        | 10.67%  |
| Acer Aspire            | 12        | 8%      |
| Dell Inspiron          | 9         | 6%      |
| Lenovo IdeaPad         | 8         | 5.33%   |
| Lenovo ThinkPad        | 7         | 4.67%   |
| HP EliteBook           | 7         | 4.67%   |
| Dell Latitude          | 7         | 4.67%   |
| HP 15                  | 3         | 2%      |
| Acer Nitro             | 3         | 2%      |
| HP Pavilion            | 2         | 1.33%   |
| HP Notebook            | 2         | 1.33%   |
| HP Laptop              | 2         | 1.33%   |
| HP ENVY                | 2         | 1.33%   |
| HP 14                  | 2         | 1.33%   |
| Dell XPS               | 2         | 1.33%   |
| ASUS X510UQ            | 2         | 1.33%   |
| Toshiba Satellite      | 1         | 0.67%   |
| Timi Mi                | 1         | 0.67%   |
| Samsung 300E5EV        | 1         | 0.67%   |
| Notebook W9x0LU        | 1         | 0.67%   |
| Notebook N750BU        | 1         | 0.67%   |
| Notebook N2x0LU        | 1         | 0.67%   |
| Notebook DCL           | 1         | 0.67%   |
| MSI Summit             | 1         | 0.67%   |
| MSI Modern             | 1         | 0.67%   |
| MSI GS63               | 1         | 0.67%   |
| Lenovo V330-14IKB      | 1         | 0.67%   |
| Lenovo S10-3           | 1         | 0.67%   |
| Lenovo Legion          | 1         | 0.67%   |
| Lenovo G40-70          | 1         | 0.67%   |
| HP ZHAN                | 1         | 0.67%   |
| HP Mini                | 1         | 0.67%   |
| HP 250                 | 1         | 0.67%   |
| HP 240                 | 1         | 0.67%   |
| Fujitsu LIFEBOOK       | 1         | 0.67%   |
| Dell G7                | 1         | 0.67%   |
| Daffodil Computers DCL | 1         | 0.67%   |
| ASUS ZenBook           | 1         | 0.67%   |
| ASUS X556URK           | 1         | 0.67%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2016 | 23        | 15.33%  |
| 2017 | 21        | 14%     |
| 2018 | 18        | 12%     |
| 2019 | 15        | 10%     |
| 2015 | 14        | 9.33%   |
| 2021 | 12        | 8%      |
| 2012 | 11        | 7.33%   |
| 2014 | 10        | 6.67%   |
| 2013 | 9         | 6%      |
| 2020 | 7         | 4.67%   |
| 2011 | 7         | 4.67%   |
| 2010 | 2         | 1.33%   |
| 2008 | 1         | 0.67%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 150       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 138       | 90.2%   |
| Enabled  | 15        | 9.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 150       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 62        | 40.52%  |
| 3.01-4.0   | 45        | 29.41%  |
| 8.01-16.0  | 26        | 16.99%  |
| 16.01-24.0 | 14        | 9.15%   |
| 1.01-2.0   | 5         | 3.27%   |
| 32.01-64.0 | 1         | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 58        | 34.94%  |
| 2.01-3.0  | 52        | 31.33%  |
| 3.01-4.0  | 31        | 18.67%  |
| 4.01-8.0  | 14        | 8.43%   |
| 0.51-1.0  | 8         | 4.82%   |
| 8.01-16.0 | 2         | 1.2%    |
| 0.01-0.5  | 1         | 0.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 104       | 68.42%  |
| 2      | 46        | 30.26%  |
| 3      | 2         | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 101       | 66.89%  |
| Yes       | 50        | 33.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 115       | 76.16%  |
| No        | 36        | 23.84%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 147       | 98%     |
| No        | 3         | 2%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 129       | 85.43%  |
| No        | 22        | 14.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Bangladesh | 150       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dhaka             | 94        | 59.87%  |
| Chittagong        | 10        | 6.37%   |
| Rajshahi          | 7         | 4.46%   |
| Jessore           | 6         | 3.82%   |
| Khulna            | 5         | 3.18%   |
| Tongi             | 4         | 2.55%   |
| Comilla           | 3         | 1.91%   |
| Sherpur           | 2         | 1.27%   |
| Narayanganj       | 2         | 1.27%   |
| Mirpur            | 2         | 1.27%   |
| Azimpur           | 2         | 1.27%   |
| Wari              | 1         | 0.64%   |
| Sylhet            | 1         | 0.64%   |
| Srimangal         | 1         | 0.64%   |
| Sirajganj         | 1         | 0.64%   |
| Savar Upazila     | 1         | 0.64%   |
| Rangpur City      | 1         | 0.64%   |
| Pirganj           | 1         | 0.64%   |
| Pabna Sadar       | 1         | 0.64%   |
| Pabna             | 1         | 0.64%   |
| NДЃrДЃyanganj | 1         | 0.64%   |
| Nilphamari        | 1         | 0.64%   |
| Natore            | 1         | 0.64%   |
| Nalitabari        | 1         | 0.64%   |
| LДЃkshДЃm     | 1         | 0.64%   |
| Jamalpur          | 1         | 0.64%   |
| Gulshan           | 1         | 0.64%   |
| Faridpur          | 1         | 0.64%   |
| Dewangonj         | 1         | 0.64%   |
| Bogra             | 1         | 0.64%   |
| Belkuchi          | 1         | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate                        | 38        | 48     | 19.49%  |
| WDC                            | 34        | 46     | 17.44%  |
| Toshiba                        | 31        | 40     | 15.9%   |
| Transcend                      | 10        | 11     | 5.13%   |
| HGST                           | 9         | 9      | 4.62%   |
| SanDisk                        | 8         | 8      | 4.1%    |
| Intel                          | 7         | 8      | 3.59%   |
| Samsung Electronics            | 6         | 11     | 3.08%   |
| Micron Technology              | 6         | 6      | 3.08%   |
| Kingston                       | 5         | 6      | 2.56%   |
| Hitachi                        | 5         | 6      | 2.56%   |
| A-DATA Technology              | 4         | 4      | 2.05%   |
| SK hynix                       | 3         | 3      | 1.54%   |
| Corsair                        | 3         | 5      | 1.54%   |
| Ramsta                         | 2         | 2      | 1.03%   |
| KingSpec                       | 2         | 2      | 1.03%   |
| WDC WDS4                       | 1         | 1      | 0.51%   |
| WALTON                         | 1         | 1      | 0.51%   |
| Teutons                        | 1         | 1      | 0.51%   |
| Solid State Storage Technology | 1         | 1      | 0.51%   |
| Silicon Motion                 | 1         | 3      | 0.51%   |
| Shenzhen Longsys Electronics   | 1         | 1      | 0.51%   |
| Realtek                        | 1         | 1      | 0.51%   |
| PNY                            | 1         | 1      | 0.51%   |
| Phison                         | 1         | 1      | 0.51%   |
| Lexar                          | 1         | 2      | 0.51%   |
| KIOXIA                         | 1         | 1      | 0.51%   |
| Kingsand                       | 1         | 1      | 0.51%   |
| HS-SSD-E100                    | 1         | 1      | 0.51%   |
| Hewlett-Packard                | 1         | 1      | 0.51%   |
| Gigabyte Technology            | 1         | 1      | 0.51%   |
| Crucial                        | 1         | 2      | 0.51%   |
| Colorful                       | 1         | 1      | 0.51%   |
| China                          | 1         | 1      | 0.51%   |
| BIWIN                          | 1         | 1      | 0.51%   |
| ASMT                           | 1         | 1      | 0.51%   |
| Apacer                         | 1         | 1      | 0.51%   |
| Unknown                        | 1         | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 17        | 8.54%   |
| Toshiba MQ04ABF100 1TB               | 15        | 7.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 6         | 3.02%   |
| WDC WD10JPVX-60JC3T0 1TB             | 5         | 2.51%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 4         | 2.01%   |
| Toshiba MQ01ABD100 1TB               | 4         | 2.01%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 3         | 1.51%   |
| Transcend TS120GMTS420S 120GB SSD    | 3         | 1.51%   |
| Seagate ST500LT012-9WS142 500GB      | 3         | 1.51%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 1.51%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 1.51%   |
| SanDisk NVMe SSD Drive 512GB         | 3         | 1.51%   |
| Intel NVMe SSD Drive 512GB           | 3         | 1.51%   |
| HGST HTS541010A9E680 1TB             | 3         | 1.51%   |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 1.01%   |
| WDC WD10SPZX-24Z10T0 1TB             | 2         | 1.01%   |
| WDC WD10JPVX-75JC3T0 1TB             | 2         | 1.01%   |
| WDC WD10JPVX-60JC3T1 1TB             | 2         | 1.01%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 2         | 1.01%   |
| Transcend TS240GMTS820S 240GB SSD    | 2         | 1.01%   |
| Toshiba THNSNK128GVN8 128GB SSD      | 2         | 1.01%   |
| Toshiba MQ01ACF050 500GB             | 2         | 1.01%   |
| Seagate ST9500325AS 500GB            | 2         | 1.01%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.01%   |
| Ramsta SSD R800 120GB                | 2         | 1.01%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 2         | 1.01%   |
| Intel SSD 660P Series 512GB          | 2         | 1.01%   |
| HGST HTS545050A7E680 500GB           | 2         | 1.01%   |
| HGST HTS541010B7E610 1TB             | 2         | 1.01%   |
| Corsair Force MP510 240GB            | 2         | 1.01%   |
| A-DATA SU650 240GB SSD               | 2         | 1.01%   |
| WDC WDS4 80G2G0B-00EPW0 480GB SSD    | 1         | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.5%    |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1         | 0.5%    |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.5%    |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 0.5%    |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 0.5%    |
| WDC WD3200BPVT-60JJ5T0 320GB         | 1         | 0.5%    |
| WDC WD3200BPVT-00ZEST0 320GB         | 1         | 0.5%    |
| WDC WD1600BEVT-75ZCT1 160GB          | 1         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 38        | 48     | 37.25%  |
| Toshiba | 27        | 35     | 26.47%  |
| WDC     | 22        | 31     | 21.57%  |
| HGST    | 9         | 9      | 8.82%   |
| Hitachi | 5         | 6      | 4.9%    |
| ASMT    | 1         | 1      | 0.98%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 12     | 17.24%  |
| Transcend           | 10        | 11     | 17.24%  |
| SanDisk             | 5         | 5      | 8.62%   |
| Micron Technology   | 5         | 5      | 8.62%   |
| Samsung Electronics | 4         | 6      | 6.9%    |
| A-DATA Technology   | 4         | 4      | 6.9%    |
| Toshiba             | 2         | 3      | 3.45%   |
| Ramsta              | 2         | 2      | 3.45%   |
| KingSpec            | 2         | 2      | 3.45%   |
| WDC WDS4            | 1         | 1      | 1.72%   |
| WALTON              | 1         | 1      | 1.72%   |
| Teutons             | 1         | 1      | 1.72%   |
| SK hynix            | 1         | 1      | 1.72%   |
| PNY                 | 1         | 1      | 1.72%   |
| Kingston            | 1         | 1      | 1.72%   |
| Intel               | 1         | 1      | 1.72%   |
| HS-SSD-E100         | 1         | 1      | 1.72%   |
| Hewlett-Packard     | 1         | 1      | 1.72%   |
| Gigabyte Technology | 1         | 1      | 1.72%   |
| Crucial             | 1         | 2      | 1.72%   |
| Corsair             | 1         | 2      | 1.72%   |
| China               | 1         | 1      | 1.72%   |
| Apacer              | 1         | 1      | 1.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 102       | 130    | 53.68%  |
| SSD     | 55        | 66     | 28.95%  |
| NVMe    | 30        | 42     | 15.79%  |
| Unknown | 3         | 3      | 1.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 129       | 197    | 79.63%  |
| NVMe | 30        | 41     | 18.52%  |
| SAS  | 3         | 3      | 1.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 77        | 97     | 50.66%  |
| 0.51-1.0   | 73        | 97     | 48.03%  |
| 1.01-2.0   | 2         | 2      | 1.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 43        | 27.39%  |
| 251-500    | 37        | 23.57%  |
| 501-1000   | 33        | 21.02%  |
| 51-100     | 14        | 8.92%   |
| 1001-2000  | 13        | 8.28%   |
| 1-20       | 8         | 5.1%    |
| 21-50      | 7         | 4.46%   |
| Unknown    | 2         | 1.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 58        | 35.15%  |
| 21-50     | 31        | 18.79%  |
| 101-250   | 28        | 16.97%  |
| 51-100    | 28        | 16.97%  |
| 251-500   | 9         | 5.45%   |
| 501-1000  | 7         | 4.24%   |
| 1001-2000 | 2         | 1.21%   |
| Unknown   | 2         | 1.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 2         | 4      | 11.11%  |
| HGST HTS541010A9E680 1TB                       | 2         | 2      | 11.11%  |
| WDC WD5000LPCX-22VHAT0 500GB                   | 1         | 1      | 5.56%   |
| WDC WD5000BPVT-22HXZT3 500GB                   | 1         | 1      | 5.56%   |
| WDC WD10SPZX-24Z10T0 1TB                       | 1         | 1      | 5.56%   |
| WDC WD10JPVX-60JC3T0 1TB                       | 1         | 2      | 5.56%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 5.56%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD          | 1         | 1      | 5.56%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 5.56%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 5.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 1         | 1      | 5.56%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 5.56%   |
| Intel SSDSCKKW240H6 240GB                      | 1         | 1      | 5.56%   |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 5.56%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 5.56%   |
| Hewlett-Packard SSD S600 240GB                 | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 4         | 5      | 22.22%  |
| HGST              | 4         | 4      | 22.22%  |
| Toshiba           | 3         | 5      | 16.67%  |
| Seagate           | 3         | 3      | 16.67%  |
| SK hynix          | 1         | 1      | 5.56%   |
| Micron Technology | 1         | 1      | 5.56%   |
| Intel             | 1         | 1      | 5.56%   |
| Hewlett-Packard   | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 5      | 28.57%  |
| HGST    | 4         | 4      | 28.57%  |
| Toshiba | 3         | 5      | 21.43%  |
| Seagate | 3         | 3      | 21.43%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 17     | 77.78%  |
| SSD  | 4         | 4      | 22.22%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 90        | 140    | 55.9%   |
| Works    | 53        | 80     | 32.92%  |
| Malfunc  | 18        | 21     | 11.18%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 133       | 78.7%   |
| AMD                            | 10        | 5.92%   |
| SanDisk                        | 6         | 3.55%   |
| Kingston Technology Company    | 4         | 2.37%   |
| Phison Electronics             | 3         | 1.78%   |
| Toshiba America Info Systems   | 2         | 1.18%   |
| SK hynix                       | 2         | 1.18%   |
| Shenzhen Longsys Electronics   | 2         | 1.18%   |
| Samsung Electronics            | 2         | 1.18%   |
| Solid State Storage Technology | 1         | 0.59%   |
| Silicon Motion                 | 1         | 0.59%   |
| Micron Technology              | 1         | 0.59%   |
| KIOXIA                         | 1         | 0.59%   |
| Biwin Storage Technology       | 1         | 0.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 49        | 27.37%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 14        | 7.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 6.15%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 5.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9         | 5.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 9         | 5.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 5.03%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 3.35%   |
| Intel SSD 660P Series                                                            | 5         | 2.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 2.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 2.79%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 1.68%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.12%   |
| Phison E12 NVMe Controller                                                       | 2         | 1.12%   |
| Kingston Company Company Non-Volatile memory controller                          | 2         | 1.12%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 1.12%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.12%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 1         | 0.56%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.56%   |
| Solid State Storage Non-Volatile memory controller                               | 1         | 0.56%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 0.56%   |
| SK hynix BC511                                                                   | 1         | 0.56%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.56%   |
| Shenzhen Longsys Non-Volatile memory controller                                  | 1         | 0.56%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                      | 1         | 0.56%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.56%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.56%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.56%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.56%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 0.56%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.56%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 0.56%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.56%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.56%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.56%   |
| Intel Comet Lake PCH-H RAID                                                      | 1         | 0.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 121       | 69.14%  |
| NVMe | 30        | 17.14%  |
| RAID | 21        | 12%     |
| IDE  | 3         | 1.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 137       | 91.33%  |
| AMD    | 13        | 8.67%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 7.33%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 4.67%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 7         | 4.67%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 4%      |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 4%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 4%      |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 3.33%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 3.33%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.67%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 2.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 2.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 2.67%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 4         | 2.67%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 2.67%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 2%      |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 2%      |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 2%      |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 2%      |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 2%      |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 1.33%   |
| Intel Core i3-7130U CPU @ 2.70GHz             | 2         | 1.33%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.33%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.33%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.33%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.33%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 2         | 1.33%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.67%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.67%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 0.67%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.67%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 0.67%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 0.67%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 0.67%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 0.67%   |
| Intel Core i5-4200H CPU @ 2.80GHz             | 1         | 0.67%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 0.67%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 0.67%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.67%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 67        | 44.67%  |
| Intel Core i3    | 34        | 22.67%  |
| Intel Core i7    | 15        | 10%     |
| Other            | 9         | 6%      |
| AMD Ryzen 5      | 6         | 4%      |
| Intel Pentium    | 5         | 3.33%   |
| Intel Celeron    | 4         | 2.67%   |
| AMD Ryzen 7      | 4         | 2.67%   |
| Intel Atom       | 2         | 1.33%   |
| AMD Ryzen 3      | 2         | 1.33%   |
| Intel Core 2 Duo | 1         | 0.67%   |
| AMD E2           | 1         | 0.67%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 100       | 66.67%  |
| 4      | 42        | 28%     |
| 8      | 4         | 2.67%   |
| 6      | 3         | 2%      |
| 1      | 1         | 0.67%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 150       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 138       | 92%     |
| 1      | 12        | 8%      |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 149       | 99.33%  |
| Unknown        | 1         | 0.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 20.38%  |
| 0x806e9    | 22        | 14.01%  |
| 0x806ea    | 15        | 9.55%   |
| 0x406e3    | 11        | 7.01%   |
| 0x40651    | 9         | 5.73%   |
| 0x306d4    | 9         | 5.73%   |
| 0x306a9    | 7         | 4.46%   |
| 0x206a7    | 7         | 4.46%   |
| 0x806eb    | 6         | 3.82%   |
| 0x806ec    | 5         | 3.18%   |
| 0x806c1    | 4         | 2.55%   |
| 0x706e5    | 4         | 2.55%   |
| 0x406c4    | 4         | 2.55%   |
| 0x08108102 | 3         | 1.91%   |
| 0xa0652    | 2         | 1.27%   |
| 0x306c3    | 2         | 1.27%   |
| 0x08108109 | 2         | 1.27%   |
| 0x906e9    | 1         | 0.64%   |
| 0x806d1    | 1         | 0.64%   |
| 0x506e3    | 1         | 0.64%   |
| 0x406c3    | 1         | 0.64%   |
| 0x30678    | 1         | 0.64%   |
| 0x30661    | 1         | 0.64%   |
| 0x20655    | 1         | 0.64%   |
| 0x106ca    | 1         | 0.64%   |
| 0x10676    | 1         | 0.64%   |
| 0x0a50000c | 1         | 0.64%   |
| 0x08600104 | 1         | 0.64%   |
| 0x0810100b | 1         | 0.64%   |
| 0x06006705 | 1         | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 55        | 36.67%  |
| Skylake     | 15        | 10%     |
| Haswell     | 12        | 8%      |
| Broadwell   | 11        | 7.33%   |
| IvyBridge   | 10        | 6.67%   |
| SandyBridge | 9         | 6%      |
| TigerLake   | 8         | 5.33%   |
| Zen+        | 6         | 4%      |
| Silvermont  | 6         | 4%      |
| Icelake     | 5         | 3.33%   |
| Zen 3       | 2         | 1.33%   |
| Zen 2       | 2         | 1.33%   |
| CometLake   | 2         | 1.33%   |
| Bonnell     | 2         | 1.33%   |
| Zen         | 1         | 0.67%   |
| Westmere    | 1         | 0.67%   |
| Penryn      | 1         | 0.67%   |
| Excavator   | 1         | 0.67%   |
| Unknown     | 1         | 0.67%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 137       | 70.98%  |
| Nvidia | 39        | 20.21%  |
| AMD    | 17        | 8.81%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 26        | 13.33%  |
| Intel UHD Graphics 620                                                                   | 15        | 7.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 7.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 6.15%   |
| Intel HD Graphics 5500                                                                   | 10        | 5.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 5.13%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 5.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 3.59%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 3.08%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 2.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.56%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 2.05%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 2.05%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 2.05%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 2.05%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.03%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 1.03%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.03%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.03%   |
| AMD Renoir                                                                               | 2         | 1.03%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.03%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 1.03%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.51%   |
| Nvidia TU117M                                                                            | 1         | 0.51%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.51%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.51%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.51%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.51%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.51%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.51%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.51%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.51%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.51%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.51%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.51%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 0.51%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 1         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 98        | 65.33%  |
| Intel + Nvidia | 35        | 23.33%  |
| 1 x AMD        | 7         | 4.67%   |
| Intel + AMD    | 4         | 2.67%   |
| AMD + Nvidia   | 4         | 2.67%   |
| 2 x AMD        | 2         | 1.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 131       | 85.62%  |
| Proprietary | 20        | 13.07%  |
| Unknown     | 2         | 1.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 121       | 78.57%  |
| 1.01-2.0   | 20        | 12.99%  |
| 3.01-4.0   | 7         | 4.55%   |
| 0.01-0.5   | 3         | 1.95%   |
| 7.01-8.0   | 1         | 0.65%   |
| 5.01-6.0   | 1         | 0.65%   |
| 0.51-1.0   | 1         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 41        | 24.12%  |
| AU Optronics            | 39        | 22.94%  |
| Chimei Innolux          | 33        | 19.41%  |
| LG Display              | 25        | 14.71%  |
| Samsung Electronics     | 9         | 5.29%   |
| Dell                    | 5         | 2.94%   |
| PANDA                   | 3         | 1.76%   |
| Hewlett-Packard         | 3         | 1.76%   |
| Goldstar                | 3         | 1.76%   |
| Chi Mei Optoelectronics | 2         | 1.18%   |
| ViewSonic               | 1         | 0.59%   |
| Sharp                   | 1         | 0.59%   |
| MSI                     | 1         | 0.59%   |
| ASUSTek Computer        | 1         | 0.59%   |
| Apple                   | 1         | 0.59%   |
| AOC                     | 1         | 0.59%   |
| Ancor Communications    | 1         | 0.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 9         | 5.29%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 4         | 2.35%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 2.35%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 3         | 1.76%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                 | 3         | 1.76%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 3         | 1.76%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 3         | 1.76%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 1.18%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 2         | 1.18%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 2         | 1.18%   |
| LG Display LCD Monitor LGD0466 1366x768 309x174mm 14.0-inch           | 2         | 1.18%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 2         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 1.18%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.18%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 310x170mm 13.9-inch       | 2         | 1.18%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 1.18%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 1.18%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                  | 2         | 1.18%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.18%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 2         | 1.18%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 1.18%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch         | 1         | 0.59%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.59%   |
| Samsung Electronics SyncMaster SAM043E 1600x1200 520x320mm 24.0-inch  | 1         | 0.59%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch     | 1         | 0.59%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch      | 1         | 0.59%   |
| Samsung Electronics S19C300 SAM0A12 1366x768 410x230mm 18.5-inch      | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch  | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4751 1366x768 344x194mm 15.5-inch  | 1         | 0.59%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.59%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.59%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.59%   |
| MSI MP241 MSI3BA9 1920x1080 527x296mm 23.8-inch                       | 1         | 0.59%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.59%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch           | 1         | 0.59%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.59%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 0.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 78        | 48.75%  |
| 1920x1080 (FHD)   | 67        | 41.88%  |
| 1600x900 (HD+)    | 4         | 2.5%    |
| 3840x2160 (4K)    | 2         | 1.25%   |
| 1280x800 (WXGA)   | 2         | 1.25%   |
| 1024x600          | 2         | 1.25%   |
| 2560x1600         | 1         | 0.63%   |
| 2560x1440 (QHD)   | 1         | 0.63%   |
| 2240x1400         | 1         | 0.63%   |
| 1920x1200 (WUXGA) | 1         | 0.63%   |
| 1280x1024 (SXGA)  | 1         | 0.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 72        | 42.6%   |
| 13     | 38        | 22.49%  |
| 14     | 28        | 16.57%  |
| 21     | 7         | 4.14%   |
| 18     | 7         | 4.14%   |
| 12     | 5         | 2.96%   |
| 23     | 2         | 1.18%   |
| 17     | 2         | 1.18%   |
| 11     | 2         | 1.18%   |
| 10     | 2         | 1.18%   |
| 27     | 1         | 0.59%   |
| 26     | 1         | 0.59%   |
| 24     | 1         | 0.59%   |
| 19     | 1         | 0.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 130       | 77.38%  |
| 201-300     | 17        | 10.12%  |
| 401-500     | 16        | 9.52%   |
| 501-600     | 4         | 2.38%   |
| 351-400     | 1         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 145       | 96.03%  |
| 16/10 | 5         | 3.31%   |
| 5/4   | 1         | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 72        | 42.86%  |
| 81-90          | 59        | 35.12%  |
| 141-150        | 8         | 4.76%   |
| 71-80          | 7         | 4.17%   |
| 201-250        | 6         | 3.57%   |
| 61-70          | 5         | 2.98%   |
| 151-200        | 3         | 1.79%   |
| 51-60          | 2         | 1.19%   |
| 41-50          | 2         | 1.19%   |
| 251-300        | 2         | 1.19%   |
| 301-350        | 1         | 0.6%    |
| 121-130        | 1         | 0.6%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 75        | 45.73%  |
| 121-160       | 69        | 42.07%  |
| 51-100        | 13        | 7.93%   |
| 161-240       | 6         | 3.66%   |
| More than 240 | 1         | 0.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 132       | 86.84%  |
| 2     | 18        | 11.84%  |
| 3     | 1         | 0.66%   |
| 0     | 1         | 0.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 101       | 42.98%  |
| Intel                 | 74        | 31.49%  |
| Qualcomm Atheros      | 43        | 18.3%   |
| Broadcom              | 5         | 2.13%   |
| Ralink Technology     | 3         | 1.28%   |
| MediaTek              | 3         | 1.28%   |
| Xiaomi                | 1         | 0.43%   |
| TP-Link               | 1         | 0.43%   |
| Samsung Electronics   | 1         | 0.43%   |
| Ralink                | 1         | 0.43%   |
| Dell                  | 1         | 0.43%   |
| Arduino SA            | 1         | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64        | 23.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 7.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 17        | 6.3%    |
| Intel Wireless 8265 / 8275                                        | 14        | 5.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 4.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 3.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 8         | 2.96%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 2.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7         | 2.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 2.22%   |
| Intel Wireless 3165                                               | 6         | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.22%   |
| Intel Wireless 8260                                               | 5         | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.48%   |
| Intel Wireless 7265                                               | 4         | 1.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.48%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 1.11%   |
| Intel Wireless 7260                                               | 3         | 1.11%   |
| Intel Wireless 3160                                               | 3         | 1.11%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 1.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.74%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.74%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.37%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.37%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.37%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.37%   |
| Realtek RTL8187 Wireless Adapter                                  | 1         | 0.37%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 72        | 47.06%  |
| Qualcomm Atheros      | 42        | 27.45%  |
| Realtek Semiconductor | 27        | 17.65%  |
| Ralink Technology     | 3         | 1.96%   |
| MediaTek              | 3         | 1.96%   |
| Broadcom              | 3         | 1.96%   |
| TP-Link               | 1         | 0.65%   |
| Ralink                | 1         | 0.65%   |
| Dell                  | 1         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 17        | 11.11%  |
| Intel Wireless 8265 / 8275                                     | 14        | 9.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12        | 7.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 6.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 5.23%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 5.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 4.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 3.92%   |
| Intel Wireless 3165                                            | 6         | 3.92%   |
| Intel Wireless 8260                                            | 5         | 3.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.61%   |
| Intel Wireless 7265                                            | 4         | 2.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.61%   |
| Ralink MT7601U Wireless Adapter                                | 3         | 1.96%   |
| Intel Wireless 7260                                            | 3         | 1.96%   |
| Intel Wireless 3160                                            | 3         | 1.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.31%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.31%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.31%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.31%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 1.31%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.31%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.65%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.65%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.65%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 0.65%   |
| Realtek 802.11n                                                | 1         | 0.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.65%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 0.65%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 0.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 0.65%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 0.65%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 0.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 0.65%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 1         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 89        | 76.72%  |
| Intel                 | 18        | 15.52%  |
| Qualcomm Atheros      | 4         | 3.45%   |
| Broadcom              | 3         | 2.59%   |
| Xiaomi                | 1         | 0.86%   |
| Samsung Electronics   | 1         | 0.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64        | 55.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 18.1%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 5.17%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 3.45%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.72%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.86%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.86%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.86%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.86%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.86%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.86%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.86%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.86%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.86%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.86%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.86%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 147       | 55.89%  |
| Ethernet | 115       | 43.73%  |
| Modem    | 1         | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 132       | 85.71%  |
| Ethernet | 22        | 14.29%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 107       | 71.33%  |
| 1     | 43        | 28.67%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 150       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 60        | 46.51%  |
| IMC Networks                    | 21        | 16.28%  |
| Realtek Semiconductor           | 14        | 10.85%  |
| Qualcomm Atheros Communications | 11        | 8.53%   |
| Lite-On Technology              | 10        | 7.75%   |
| Broadcom                        | 6         | 4.65%   |
| Foxconn / Hon Hai               | 4         | 3.1%    |
| Toshiba                         | 1         | 0.78%   |
| Ralink                          | 1         | 0.78%   |
| Hewlett-Packard                 | 1         | 0.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 35        | 27.13%  |
| IMC Networks Bluetooth Device                     | 12        | 9.3%    |
| Realtek Bluetooth Radio                           | 10        | 7.75%   |
| Intel Wireless-AC 3168 Bluetooth                  | 10        | 7.75%   |
| Intel AX201 Bluetooth                             | 8         | 6.2%    |
| IMC Networks Bluetooth Radio                      | 7         | 5.43%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 6         | 4.65%   |
| Qualcomm Atheros  Bluetooth Device                | 5         | 3.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 4         | 3.1%    |
| Realtek  Bluetooth 4.2 Adapter                    | 3         | 2.33%   |
| Lite-On Bluetooth Device                          | 3         | 2.33%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 2         | 1.55%   |
| Intel AX200 Bluetooth                             | 2         | 1.55%   |
| Foxconn / Hon Hai Bluetooth Device                | 2         | 1.55%   |
| Broadcom HP Portable SoftSailing                  | 2         | 1.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 2         | 1.55%   |
| Toshiba Bluetooth Radio                           | 1         | 0.78%   |
| Realtek RTL8821A Bluetooth                        | 1         | 0.78%   |
| Ralink RT3290 Bluetooth                           | 1         | 0.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 0.78%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 0.78%   |
| Qualcomm Atheros AR3012 Bluetooth                 | 1         | 0.78%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 1         | 0.78%   |
| Lite-On Atheros AR3012 Bluetooth                  | 1         | 0.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 0.78%   |
| IMC Networks Wireless_Device                      | 1         | 0.78%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 1         | 0.78%   |
| HP Broadcom 2070 Bluetooth Combo                  | 1         | 0.78%   |
| Foxconn / Hon Hai Wireless_Device                 | 1         | 0.78%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller   | 1         | 0.78%   |
| Broadcom BCM43142A0 Bluetooth 4.0                 | 1         | 0.78%   |
| Broadcom BCM20702A0 Bluetooth 4.0                 | 1         | 0.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 136       | 86.62%  |
| AMD                    | 13        | 8.28%   |
| Nvidia                 | 7         | 4.46%   |
| Generalplus Technology | 1         | 0.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 55        | 28.65%  |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 12        | 6.25%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 6.25%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 6.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 5.73%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 5.73%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 5.21%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 5.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 3.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 2.6%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 2.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.04%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.04%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.52%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.52%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.52%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.52%   |
| Intel USB PnP Sound Device                                                                        | 1         | 0.52%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.52%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.52%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 0.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.52%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.52%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.52%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 30.48%  |
| SK hynix            | 27        | 25.71%  |
| Micron Technology   | 14        | 13.33%  |
| A-DATA Technology   | 6         | 5.71%   |
| Kingston            | 5         | 4.76%   |
| G.Skill             | 4         | 3.81%   |
| Unknown             | 3         | 2.86%   |
| Transcend           | 3         | 2.86%   |
| Team                | 2         | 1.9%    |
| Ramaxel Technology  | 2         | 1.9%    |
| Nanya Technology    | 2         | 1.9%    |
| Unknown (C509)      | 1         | 0.95%   |
| Unknown (768A)      | 1         | 0.95%   |
| Elpida              | 1         | 0.95%   |
| Crucial             | 1         | 0.95%   |
| Unknown             | 1         | 0.95%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 4.76%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 3.81%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.86%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 2.86%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 2.86%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.86%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.9%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.9%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.9%    |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 1.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.9%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.9%    |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s            | 2         | 1.9%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.9%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.9%    |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 1.9%    |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 1.9%    |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.95%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.95%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.95%   |
| Unknown (C509) RAM Module 4GB SODIMM DDR4 2400MT/s               | 1         | 0.95%   |
| Unknown (768A) RAM Module 8192MB SODIMM DDR4 3200MT/s            | 1         | 0.95%   |
| Transcend RAM JM3200HSB-8G 8GB SODIMM DDR4 3200MT/s              | 1         | 0.95%   |
| Transcend RAM JM2666HSG-8G 8GB SODIMM DDR4 2667MT/s              | 1         | 0.95%   |
| Transcend RAM JM2400HSB-8G 8GB SODIMM DDR4 2400MT/s              | 1         | 0.95%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 1         | 0.95%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 1         | 0.95%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 1         | 0.95%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2133MT/s                  | 1         | 0.95%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.95%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.95%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.95%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.95%   |
| SK hynix RAM H9CCNNNBJTMLAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.95%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.95%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 0.95%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2400MT/s                   | 1         | 0.95%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.95%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 53        | 67.09%  |
| DDR3   | 21        | 26.58%  |
| LPDDR4 | 3         | 3.8%    |
| LPDDR3 | 2         | 2.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 74        | 96.1%   |
| Row Of Chips | 3         | 3.9%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 39        | 44.83%  |
| 8192  | 37        | 42.53%  |
| 16384 | 7         | 8.05%   |
| 2048  | 3         | 3.45%   |
| 32768 | 1         | 1.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 27        | 31.4%   |
| 1600  | 17        | 19.77%  |
| 2400  | 13        | 15.12%  |
| 3200  | 10        | 11.63%  |
| 2133  | 10        | 11.63%  |
| 3266  | 2         | 2.33%   |
| 1334  | 2         | 2.33%   |
| 1067  | 2         | 2.33%   |
| 8400  | 1         | 1.16%   |
| 1867  | 1         | 1.16%   |
| 1333  | 1         | 1.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Pantum      | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L132 Series | 1         | 50%     |
| Pantum PMF22 series     | 1         | 50%     |

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
| Chicony Electronics                    | 32        | 22.7%   |
| IMC Networks                           | 27        | 19.15%  |
| Cheng Uei Precision Industry (Foxlink) | 15        | 10.64%  |
| Realtek Semiconductor                  | 12        | 8.51%   |
| Sunplus Innovation Technology          | 9         | 6.38%   |
| Quanta                                 | 9         | 6.38%   |
| Acer                                   | 8         | 5.67%   |
| Microdia                               | 7         | 4.96%   |
| Lite-On Technology                     | 6         | 4.26%   |
| Luxvisions Innotech Limited            | 5         | 3.55%   |
| Suyin                                  | 4         | 2.84%   |
| Silicon Motion                         | 2         | 1.42%   |
| Primax Electronics                     | 2         | 1.42%   |
| Syntek                                 | 1         | 0.71%   |
| Sonix Technology                       | 1         | 0.71%   |
| Apple                                  | 1         | 0.71%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                           | 9         | 6.38%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 8         | 5.67%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 8         | 5.67%   |
| IMC Networks VGA UVC WebCam                             | 5         | 3.55%   |
| Luxvisions Innotech Limited HP HD Camera                | 4         | 2.84%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 4         | 2.84%   |
| Realtek Integrated_Webcam_HD                            | 3         | 2.13%   |
| Quanta HD Webcam                                        | 3         | 2.13%   |
| Microdia Integrated_Webcam_HD                           | 3         | 2.13%   |
| Lite-On HP HD Camera                                    | 3         | 2.13%   |
| IMC Networks USB2.0 HD IR UVC WebCam                    | 3         | 2.13%   |
| IMC Networks Integrated Camera                          | 3         | 2.13%   |
| Chicony HD WebCam                                       | 3         | 2.13%   |
| Chicony EasyCamera                                      | 3         | 2.13%   |
| Acer HD Webcam                                          | 3         | 2.13%   |
| Suyin Integrated_Webcam_HD                              | 2         | 1.42%   |
| Suyin HP Truevision HD                                  | 2         | 1.42%   |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 1.42%   |
| Realtek USB2.0 VGA UVC WebCam                           | 2         | 1.42%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.42%   |
| Realtek USB Camera                                      | 2         | 1.42%   |
| Quanta HD User Facing                                   | 2         | 1.42%   |
| Primax HP HD Webcam [Fixed]                             | 2         | 1.42%   |
| Lite-On Integrated Camera                               | 2         | 1.42%   |
| Chicony USB2.0 Camera                                   | 2         | 1.42%   |
| Chicony Integrated Camera                               | 2         | 1.42%   |
| Chicony HP Truevision HD camera                         | 2         | 1.42%   |
| Chicony HP HD Webcam                                    | 2         | 1.42%   |
| Chicony HP HD Camera                                    | 2         | 1.42%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 2         | 1.42%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.42%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.42%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 2         | 1.42%   |
| Acer Lenovo EasyCamera                                  | 2         | 1.42%   |
| Syntek Integrated Camera                                | 1         | 0.71%   |
| Sunplus XiaoMi USB 2.0 Webcam                           | 1         | 0.71%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 0.71%   |
| Sunplus Integrated Webcam                               | 1         | 0.71%   |
| Sunplus HP HD Webcam [Fixed]                            | 1         | 0.71%   |
| Sunplus HD WebCam                                       | 1         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 24        | 80%     |
| Synaptics                  | 3         | 10%     |
| Elan Microelectronics      | 2         | 6.67%   |
| Shenzhen Goodix Technology | 1         | 3.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 46.67%  |
| Validity Sensors VFS491                                                    | 3         | 10%     |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 6.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 6.67%   |
| Elan ELAN:Fingerprint                                                      | 2         | 6.67%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.33%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.33%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 3.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.33%   |
| Synaptics  WBDI                                                            | 1         | 3.33%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 3.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 5         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 40%     |
| Broadcom 5880                                                                | 2         | 40%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 102       | 65.81%  |
| 1     | 47        | 30.32%  |
| 2     | 5         | 3.23%   |
| 3     | 1         | 0.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 30        | 52.63%  |
| Graphics card         | 13        | 22.81%  |
| Chipcard              | 5         | 8.77%   |
| Camera                | 3         | 5.26%   |
| Net/wireless          | 2         | 3.51%   |
| Multimedia controller | 2         | 3.51%   |
| Card reader           | 1         | 1.75%   |
| Bluetooth             | 1         | 1.75%   |

