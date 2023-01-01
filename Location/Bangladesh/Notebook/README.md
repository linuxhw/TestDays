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

Total: 226

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | P453UA                      | [0bf89f0f8f](https://linux-hardware.org/?probe=0bf89f0f8f) | Dec 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3a505870ba](https://linux-hardware.org/?probe=3a505870ba) | Dec 22, 2022 |
| HP            | 15                          | [cce5eb4078](https://linux-hardware.org/?probe=cce5eb4078) | Dec 19, 2022 |
| Dell          | Inspiron 3442               | [4b44d6e506](https://linux-hardware.org/?probe=4b44d6e506) | Dec 12, 2022 |
| Acer          | Aspire E5-471               | [3e9c2f0201](https://linux-hardware.org/?probe=3e9c2f0201) | Dec 02, 2022 |
| HP            | ProBook 450 G7 HP NOTEBO... | [2fe5c76c3c](https://linux-hardware.org/?probe=2fe5c76c3c) | Dec 02, 2022 |
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
| Ubuntu 20.04                 | 35        | 20.59%  |
| Arch                         | 9         | 5.29%   |
| ArcoLinux Rolling            | 8         | 4.71%   |
| Pop!_OS 22.04                | 5         | 2.94%   |
| KDE neon 20.04               | 5         | 2.94%   |
| Ubuntu 22.04                 | 4         | 2.35%   |
| Ubuntu 19.10                 | 4         | 2.35%   |
| Ubuntu 18.04                 | 4         | 2.35%   |
| Manjaro                      | 4         | 2.35%   |
| Fedora 33                    | 4         | 2.35%   |
| Arch Rolling                 | 4         | 2.35%   |
| Zorin 16                     | 3         | 1.76%   |
| OpenMandriva 4.2             | 3         | 1.76%   |
| Manjaro 20.0.1               | 3         | 1.76%   |
| Debian 11                    | 3         | 1.76%   |
| Zorin 15                     | 2         | 1.18%   |
| Ubuntu 19.04                 | 2         | 1.18%   |
| Ubuntu 18.10                 | 2         | 1.18%   |
| Pop!_OS 21.10                | 2         | 1.18%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 1.18%   |
| OpenMandriva 4.90            | 2         | 1.18%   |
| Manjaro 21.2.6               | 2         | 1.18%   |
| Manjaro 18.0.4               | 2         | 1.18%   |
| Linux Mint 20.1              | 2         | 1.18%   |
| Linux Mint 20                | 2         | 1.18%   |
| Kubuntu 20.04                | 2         | 1.18%   |
| Kali 2022.3                  | 2         | 1.18%   |
| Fedora 34                    | 2         | 1.18%   |
| EndeavourOS Rolling          | 2         | 1.18%   |
| Ubuntu Unity 16.04           | 1         | 0.59%   |
| Ubuntu 21.04                 | 1         | 0.59%   |
| Ubuntu 20.10                 | 1         | 0.59%   |
| Pop!_OS 21.04                | 1         | 0.59%   |
| Pop!_OS 20.10                | 1         | 0.59%   |
| Parrot 5.1                   | 1         | 0.59%   |
| Parrot 4.5                   | 1         | 0.59%   |
| Parrot 4.11                  | 1         | 0.59%   |
| Parrot 4.10                  | 1         | 0.59%   |
| Manjaro 21.2.1               | 1         | 0.59%   |
| Manjaro 21.1.2               | 1         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 52        | 32.91%  |
| Manjaro      | 17        | 10.76%  |
| Arch         | 12        | 7.59%   |
| Pop!_OS      | 9         | 5.7%    |
| Linux Mint   | 8         | 5.06%   |
| ArcoLinux    | 8         | 5.06%   |
| Fedora       | 7         | 4.43%   |
| Zorin        | 5         | 3.16%   |
| OpenMandriva | 5         | 3.16%   |
| KDE neon     | 5         | 3.16%   |
| Endless      | 5         | 3.16%   |
| Kubuntu      | 4         | 2.53%   |
| Debian       | 4         | 2.53%   |
| Parrot       | 3         | 1.9%    |
| EndeavourOS  | 3         | 1.9%    |
| openSUSE     | 2         | 1.27%   |
| Kali         | 2         | 1.27%   |
| Ubuntu Unity | 1         | 0.63%   |
| LMDE         | 1         | 0.63%   |
| Deepin       | 1         | 0.63%   |
| Clear Linux  | 1         | 0.63%   |
| CentOS       | 1         | 0.63%   |
| BlackPanther | 1         | 0.63%   |
| Artix        | 1         | 0.63%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 7         | 3.74%   |
| 5.4.0-52-generic         | 3         | 1.6%    |
| 5.4.0-40-generic         | 3         | 1.6%    |
| 5.4.0-29-generic         | 3         | 1.6%    |
| 5.10.14-desktop-1omv4002 | 3         | 1.6%    |
| 6.0.9-zen1-1-zen         | 2         | 1.07%   |
| 5.9.16-1-MANJARO         | 2         | 1.07%   |
| 5.8.0-50-generic         | 2         | 1.07%   |
| 5.8.0-41-generic         | 2         | 1.07%   |
| 5.8.0-14-generic         | 2         | 1.07%   |
| 5.7.19-2-MANJARO         | 2         | 1.07%   |
| 5.6.11-1-MANJARO         | 2         | 1.07%   |
| 5.4.8-arch1-1            | 2         | 1.07%   |
| 5.4.0-53-generic         | 2         | 1.07%   |
| 5.4.0-19-generic         | 2         | 1.07%   |
| 5.3.0-24-generic         | 2         | 1.07%   |
| 5.3.0-23-generic         | 2         | 1.07%   |
| 5.19.0-kali2-amd64       | 2         | 1.07%   |
| 5.18.12-desktop-3omv4090 | 2         | 1.07%   |
| 5.15.0-48-generic        | 2         | 1.07%   |
| 5.15.0-46-generic        | 2         | 1.07%   |
| 5.13.0-28-generic        | 2         | 1.07%   |
| 5.11.0-40-generic        | 2         | 1.07%   |
| 5.11.0-27-generic        | 2         | 1.07%   |
| 5.10.52-1-lts            | 2         | 1.07%   |
| 6.0.6-76060006-generic   | 1         | 0.53%   |
| 6.0.2-76060002-generic   | 1         | 0.53%   |
| 6.0.12-zen1-1-zen        | 1         | 0.53%   |
| 6.0.12-76060006-generic  | 1         | 0.53%   |
| 6.0.12-1-default         | 1         | 0.53%   |
| 6.0.0-2parrot1-amd64     | 1         | 0.53%   |
| 5.9.16-200.fc33.x86_64   | 1         | 0.53%   |
| 5.9.11-200.fc33.x86_64   | 1         | 0.53%   |
| 5.8.4-200.fc32.x86_64    | 1         | 0.53%   |
| 5.8.16.a-1-hardened      | 1         | 0.53%   |
| 5.8.12-1-default         | 1         | 0.53%   |
| 5.8.0-7630-generic       | 1         | 0.53%   |
| 5.8.0-63-generic         | 1         | 0.53%   |
| 5.8.0-55-generic         | 1         | 0.53%   |
| 5.8.0-44-generic         | 1         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 28        | 15.73%  |
| 5.8.0   | 13        | 7.3%    |
| 5.11.0  | 12        | 6.74%   |
| 5.15.0  | 9         | 5.06%   |
| 5.13.0  | 8         | 4.49%   |
| 5.3.0   | 6         | 3.37%   |
| 5.10.0  | 5         | 2.81%   |
| 5.0.0   | 4         | 2.25%   |
| 4.18.0  | 4         | 2.25%   |
| 4.15.0  | 4         | 2.25%   |
| 6.0.12  | 3         | 1.69%   |
| 5.9.16  | 3         | 1.69%   |
| 5.19.0  | 3         | 1.69%   |
| 5.18.12 | 3         | 1.69%   |
| 5.10.14 | 3         | 1.69%   |
| 4.19.0  | 3         | 1.69%   |
| 6.0.9   | 2         | 1.12%   |
| 5.7.19  | 2         | 1.12%   |
| 5.6.11  | 2         | 1.12%   |
| 5.4.8   | 2         | 1.12%   |
| 5.16.15 | 2         | 1.12%   |
| 5.15.5  | 2         | 1.12%   |
| 5.10.52 | 2         | 1.12%   |
| 6.0.6   | 1         | 0.56%   |
| 6.0.2   | 1         | 0.56%   |
| 6.0.0   | 1         | 0.56%   |
| 5.9.11  | 1         | 0.56%   |
| 5.8.4   | 1         | 0.56%   |
| 5.8.16  | 1         | 0.56%   |
| 5.8.12  | 1         | 0.56%   |
| 5.7.0   | 1         | 0.56%   |
| 5.4.81  | 1         | 0.56%   |
| 5.4.68  | 1         | 0.56%   |
| 5.4.64  | 1         | 0.56%   |
| 5.4.40  | 1         | 0.56%   |
| 5.4.15  | 1         | 0.56%   |
| 5.19.9  | 1         | 0.56%   |
| 5.19.4  | 1         | 0.56%   |
| 5.18.6  | 1         | 0.56%   |
| 5.18.16 | 1         | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 20%     |
| 5.15    | 18        | 10.59%  |
| 5.8     | 16        | 9.41%   |
| 5.11    | 15        | 8.82%   |
| 5.10    | 14        | 8.24%   |
| 5.13    | 9         | 5.29%   |
| 6.0     | 7         | 4.12%   |
| 5.3     | 6         | 3.53%   |
| 5.18    | 6         | 3.53%   |
| 5.19    | 5         | 2.94%   |
| 5.16    | 5         | 2.94%   |
| 4.18    | 5         | 2.94%   |
| 5.9     | 4         | 2.35%   |
| 5.0     | 4         | 2.35%   |
| 4.19    | 4         | 2.35%   |
| 4.15    | 4         | 2.35%   |
| 5.7     | 3         | 1.76%   |
| 5.17    | 3         | 1.76%   |
| 5.6     | 2         | 1.18%   |
| 5.14    | 2         | 1.18%   |
| 5.12    | 2         | 1.18%   |
| 5.1     | 2         | 1.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 153       | 98.71%  |
| i686   | 2         | 1.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| GNOME          | 82        | 51.25%  |
| KDE5           | 30        | 18.75%  |
| Unknown        | 17        | 10.63%  |
| XFCE           | 8         | 5%      |
| X-Cinnamon     | 7         | 4.38%   |
| MATE           | 3         | 1.88%   |
| awesome        | 3         | 1.88%   |
| KDE            | 2         | 1.25%   |
| i3-with-shmlog | 2         | 1.25%   |
| Unity          | 1         | 0.63%   |
| LXDE           | 1         | 0.63%   |
| i3             | 1         | 0.63%   |
| DWM            | 1         | 0.63%   |
| Deepin         | 1         | 0.63%   |
| bspwm          | 1         | 0.63%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 131       | 81.37%  |
| Wayland | 20        | 12.42%  |
| Unknown | 9         | 5.59%   |
| Tty     | 1         | 0.62%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 80        | 50%     |
| GDM     | 26        | 16.25%  |
| SDDM    | 23        | 14.38%  |
| LightDM | 13        | 8.13%   |
| GDM3    | 12        | 7.5%    |
| TDM     | 6         | 3.75%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 130       | 82.8%   |
| Unknown | 15        | 9.55%   |
| en_GB   | 4         | 2.55%   |
| C       | 4         | 2.55%   |
| en_IE   | 1         | 0.64%   |
| en_EN   | 1         | 0.64%   |
| en_CA   | 1         | 0.64%   |
| en_AG   | 1         | 0.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 83        | 52.2%   |
| BIOS | 76        | 47.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 126       | 80.77%  |
| Overlay | 13        | 8.33%   |
| Btrfs   | 13        | 8.33%   |
| Unknown | 3         | 1.92%   |
| Xfs     | 1         | 0.64%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 90        | 56.25%  |
| GPT     | 56        | 35%     |
| MBR     | 14        | 8.75%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 135       | 85.99%  |
| Yes       | 22        | 14.01%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 89        | 56.69%  |
| Yes       | 68        | 43.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 44        | 28.39%  |
| Hewlett-Packard     | 41        | 26.45%  |
| Dell                | 20        | 12.9%   |
| Lenovo              | 19        | 12.26%  |
| Acer                | 17        | 10.97%  |
| Notebook            | 4         | 2.58%   |
| MSI                 | 3         | 1.94%   |
| Toshiba             | 1         | 0.65%   |
| Timi                | 1         | 0.65%   |
| Samsung Electronics | 1         | 0.65%   |
| Fujitsu             | 1         | 0.65%   |
| Daffodil Computers  | 1         | 0.65%   |
| Apple               | 1         | 0.65%   |
| Unknown             | 1         | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP ProBook 450 G4                                     | 5         | 3.23%   |
| HP ProBook 450 G2                                     | 2         | 1.29%   |
| HP ProBook 440 G8 Notebook PC                         | 2         | 1.29%   |
| HP Notebook                                           | 2         | 1.29%   |
| HP EliteBook 840 G3                                   | 2         | 1.29%   |
| HP 15                                                 | 2         | 1.29%   |
| HP 14                                                 | 2         | 1.29%   |
| Dell Inspiron 3442                                    | 2         | 1.29%   |
| ASUS X510UQ                                           | 2         | 1.29%   |
| ASUS VivoBook_ASUSLaptop X531FL_S531FL                | 2         | 1.29%   |
| ASUS VivoBook_ASUSLaptop X530FN_S530FN                | 2         | 1.29%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA                | 2         | 1.29%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA                | 2         | 1.29%   |
| ASUS VivoBook 14_ASUS Laptop X407UA                   | 2         | 1.29%   |
| ASUS P453UA                                           | 2         | 1.29%   |
| Acer Nitro AN515-43                                   | 2         | 1.29%   |
| Toshiba Satellite L645                                | 1         | 0.65%   |
| Timi Mi NoteBook Pro                                  | 1         | 0.65%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.65%   |
| Notebook W9x0LU                                       | 1         | 0.65%   |
| Notebook N750BU                                       | 1         | 0.65%   |
| Notebook N2x0LU                                       | 1         | 0.65%   |
| Notebook DCL C483                                     | 1         | 0.65%   |
| MSI Summit B14 A11MOT                                 | 1         | 0.65%   |
| MSI Modern 15 A5M                                     | 1         | 0.65%   |
| MSI GS63 7RD                                          | 1         | 0.65%   |
| Lenovo V330-14IKB 81B0                                | 1         | 0.65%   |
| Lenovo ThinkPad X230 2324F51                          | 1         | 0.65%   |
| Lenovo ThinkPad X230 2324A82                          | 1         | 0.65%   |
| Lenovo ThinkPad T450 20BUS2021M                       | 1         | 0.65%   |
| Lenovo ThinkPad T430s 2356GPU                         | 1         | 0.65%   |
| Lenovo ThinkPad L380 20M6S22500                       | 1         | 0.65%   |
| Lenovo ThinkPad E490 20N9S1XE00                       | 1         | 0.65%   |
| Lenovo ThinkPad E470 20H1A029SG                       | 1         | 0.65%   |
| Lenovo S10-3                                          | 1         | 0.65%   |
| Lenovo Legion 5 15ARH05H 82B1                         | 1         | 0.65%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7                      | 1         | 0.65%   |
| Lenovo IdeaPad 330-15IKB 81DE                         | 1         | 0.65%   |
| Lenovo IdeaPad 320-15IKB 81BG                         | 1         | 0.65%   |
| Lenovo IdeaPad 320-15IKB 80XL                         | 1         | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| ASUS VivoBook          | 20        | 12.9%   |
| HP ProBook             | 17        | 10.97%  |
| Acer Aspire            | 13        | 8.39%   |
| Dell Inspiron          | 10        | 6.45%   |
| Lenovo IdeaPad         | 8         | 5.16%   |
| Lenovo ThinkPad        | 7         | 4.52%   |
| HP EliteBook           | 7         | 4.52%   |
| Dell Latitude          | 7         | 4.52%   |
| HP 15                  | 3         | 1.94%   |
| Acer Nitro             | 3         | 1.94%   |
| HP Pavilion            | 2         | 1.29%   |
| HP Notebook            | 2         | 1.29%   |
| HP Laptop              | 2         | 1.29%   |
| HP ENVY                | 2         | 1.29%   |
| HP 14                  | 2         | 1.29%   |
| Dell XPS               | 2         | 1.29%   |
| ASUS X510UQ            | 2         | 1.29%   |
| ASUS P453UA            | 2         | 1.29%   |
| Toshiba Satellite      | 1         | 0.65%   |
| Timi Mi                | 1         | 0.65%   |
| Samsung 300E5EV        | 1         | 0.65%   |
| Notebook W9x0LU        | 1         | 0.65%   |
| Notebook N750BU        | 1         | 0.65%   |
| Notebook N2x0LU        | 1         | 0.65%   |
| Notebook DCL           | 1         | 0.65%   |
| MSI Summit             | 1         | 0.65%   |
| MSI Modern             | 1         | 0.65%   |
| MSI GS63               | 1         | 0.65%   |
| Lenovo V330-14IKB      | 1         | 0.65%   |
| Lenovo S10-3           | 1         | 0.65%   |
| Lenovo Legion          | 1         | 0.65%   |
| Lenovo G40-70          | 1         | 0.65%   |
| HP ZHAN                | 1         | 0.65%   |
| HP Mini                | 1         | 0.65%   |
| HP 250                 | 1         | 0.65%   |
| HP 240                 | 1         | 0.65%   |
| Fujitsu LIFEBOOK       | 1         | 0.65%   |
| Dell G7                | 1         | 0.65%   |
| Daffodil Computers DCL | 1         | 0.65%   |
| ASUS ZenBook           | 1         | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2016 | 23        | 14.84%  |
| 2017 | 21        | 13.55%  |
| 2018 | 18        | 11.61%  |
| 2019 | 15        | 9.68%   |
| 2015 | 15        | 9.68%   |
| 2021 | 12        | 7.74%   |
| 2014 | 12        | 7.74%   |
| 2012 | 11        | 7.1%    |
| 2013 | 9         | 5.81%   |
| 2020 | 8         | 5.16%   |
| 2011 | 7         | 4.52%   |
| 2010 | 2         | 1.29%   |
| 2022 | 1         | 0.65%   |
| 2008 | 1         | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 155       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 141       | 89.24%  |
| Enabled  | 17        | 10.76%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 155       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 64        | 40.51%  |
| 3.01-4.0   | 46        | 29.11%  |
| 8.01-16.0  | 27        | 17.09%  |
| 16.01-24.0 | 15        | 9.49%   |
| 1.01-2.0   | 5         | 3.16%   |
| 32.01-64.0 | 1         | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 59        | 34.3%   |
| 2.01-3.0  | 54        | 31.4%   |
| 3.01-4.0  | 33        | 19.19%  |
| 4.01-8.0  | 15        | 8.72%   |
| 0.51-1.0  | 8         | 4.65%   |
| 8.01-16.0 | 2         | 1.16%   |
| 0.01-0.5  | 1         | 0.58%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 106       | 67.52%  |
| 2      | 49        | 31.21%  |
| 3      | 2         | 1.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 104       | 66.67%  |
| Yes       | 52        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 76.28%  |
| No        | 37        | 23.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 152       | 98.06%  |
| No        | 3         | 1.94%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 132       | 84.62%  |
| No        | 24        | 15.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Bangladesh | 155       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dhaka             | 96        | 58.9%   |
| Chittagong        | 10        | 6.13%   |
| Rajshahi          | 8         | 4.91%   |
| Jessore           | 6         | 3.68%   |
| Khulna            | 5         | 3.07%   |
| Tongi             | 4         | 2.45%   |
| Comilla           | 3         | 1.84%   |
| Wari              | 2         | 1.23%   |
| Sherpur           | 2         | 1.23%   |
| Narayanganj       | 2         | 1.23%   |
| Mirpur            | 2         | 1.23%   |
| Azimpur           | 2         | 1.23%   |
| Sylhet            | 1         | 0.61%   |
| Srimangal         | 1         | 0.61%   |
| Sirajganj         | 1         | 0.61%   |
| Savar Upazila     | 1         | 0.61%   |
| Rangpur City      | 1         | 0.61%   |
| Pirganj           | 1         | 0.61%   |
| Pabna Sadar       | 1         | 0.61%   |
| Pabna             | 1         | 0.61%   |
| NДЃrДЃyanganj | 1         | 0.61%   |
| Nilphamari        | 1         | 0.61%   |
| Natore            | 1         | 0.61%   |
| Narail            | 1         | 0.61%   |
| Nalitabari        | 1         | 0.61%   |
| LДЃkshДЃm     | 1         | 0.61%   |
| Khilgaon          | 1         | 0.61%   |
| Jamalpur          | 1         | 0.61%   |
| Gulshan           | 1         | 0.61%   |
| Faridpur          | 1         | 0.61%   |
| Dewangonj         | 1         | 0.61%   |
| Bogra             | 1         | 0.61%   |
| Belkuchi          | 1         | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate                        | 40        | 51     | 19.8%   |
| WDC                            | 36        | 49     | 17.82%  |
| Toshiba                        | 31        | 40     | 15.35%  |
| Transcend                      | 10        | 11     | 4.95%   |
| HGST                           | 9         | 9      | 4.46%   |
| SanDisk                        | 8         | 8      | 3.96%   |
| Intel                          | 8         | 9      | 3.96%   |
| Samsung Electronics            | 7         | 12     | 3.47%   |
| Micron Technology              | 6         | 6      | 2.97%   |
| Kingston                       | 5         | 6      | 2.48%   |
| Hitachi                        | 5         | 6      | 2.48%   |
| A-DATA Technology              | 4         | 4      | 1.98%   |
| SK hynix                       | 3         | 3      | 1.49%   |
| Corsair                        | 3         | 5      | 1.49%   |
| Ramsta                         | 2         | 2      | 0.99%   |
| KingSpec                       | 2         | 2      | 0.99%   |
| WDC WDS4                       | 1         | 1      | 0.5%    |
| WALTON                         | 1         | 2      | 0.5%    |
| Teutons                        | 1         | 1      | 0.5%    |
| Solid State Storage Technology | 1         | 1      | 0.5%    |
| Silicon Motion                 | 1         | 3      | 0.5%    |
| Shenzhen Longsys Electronics   | 1         | 1      | 0.5%    |
| Realtek                        | 1         | 1      | 0.5%    |
| PNY                            | 1         | 1      | 0.5%    |
| Phison                         | 1         | 1      | 0.5%    |
| Lexar                          | 1         | 2      | 0.5%    |
| KIOXIA                         | 1         | 1      | 0.5%    |
| Kingsand                       | 1         | 1      | 0.5%    |
| HS-SSD-E100                    | 1         | 1      | 0.5%    |
| Hewlett-Packard                | 1         | 1      | 0.5%    |
| Gigabyte Technology            | 1         | 1      | 0.5%    |
| GeIL                           | 1         | 1      | 0.5%    |
| Crucial                        | 1         | 2      | 0.5%    |
| Colorful                       | 1         | 1      | 0.5%    |
| China                          | 1         | 1      | 0.5%    |
| BIWIN                          | 1         | 1      | 0.5%    |
| ASMT                           | 1         | 1      | 0.5%    |
| Apacer                         | 1         | 1      | 0.5%    |
| Unknown                        | 1         | 1      | 0.5%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 17        | 8.21%   |
| Toshiba MQ04ABF100 1TB               | 15        | 7.25%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 6         | 2.9%    |
| WDC WD10JPVX-60JC3T0 1TB             | 5         | 2.42%   |
| Seagate ST500LT012-1DG142 500GB      | 5         | 2.42%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 4         | 1.93%   |
| Toshiba MQ01ABD100 1TB               | 4         | 1.93%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 3         | 1.45%   |
| WDC WD10SPZX-60Z10T0 1TB             | 3         | 1.45%   |
| Transcend TS120GMTS420S 120GB SSD    | 3         | 1.45%   |
| Seagate ST500LT012-9WS142 500GB      | 3         | 1.45%   |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 1.45%   |
| SanDisk NVMe SSD Drive 512GB         | 3         | 1.45%   |
| Intel SSD 660P Series 1024GB         | 3         | 1.45%   |
| Intel NVMe SSD Drive 512GB           | 3         | 1.45%   |
| HGST HTS541010A9E680 1TB             | 3         | 1.45%   |
| WDC WD10SPZX-24Z10T0 1TB             | 2         | 0.97%   |
| WDC WD10JPVX-75JC3T0 1TB             | 2         | 0.97%   |
| WDC WD10JPVX-60JC3T1 1TB             | 2         | 0.97%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 2         | 0.97%   |
| Transcend TS240GMTS820S 240GB SSD    | 2         | 0.97%   |
| Toshiba THNSNK128GVN8 128GB SSD      | 2         | 0.97%   |
| Toshiba MQ01ACF050 500GB             | 2         | 0.97%   |
| Seagate ST9500325AS 500GB            | 2         | 0.97%   |
| Samsung SSD 860 EVO 500GB            | 2         | 0.97%   |
| Ramsta SSD R800 120GB                | 2         | 0.97%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 2         | 0.97%   |
| HGST HTS545050A7E680 500GB           | 2         | 0.97%   |
| HGST HTS541010B7E610 1TB             | 2         | 0.97%   |
| Corsair Force MP510 240GB            | 2         | 0.97%   |
| A-DATA SU650 240GB SSD               | 2         | 0.97%   |
| WDC WDS4 80G2G0B-00EPW0 480GB SSD    | 1         | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.48%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1         | 0.48%   |
| WDC WDS120G2G0A-00 120GB SSD         | 1         | 0.48%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.48%   |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 0.48%   |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 0.48%   |
| WDC WD3200BPVT-60JJ5T0 320GB         | 1         | 0.48%   |
| WDC WD3200BPVT-00ZEST0 320GB         | 1         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 40        | 51     | 38.1%   |
| Toshiba | 27        | 35     | 25.71%  |
| WDC     | 23        | 32     | 21.9%   |
| HGST    | 9         | 9      | 8.57%   |
| Hitachi | 5         | 6      | 4.76%   |
| ASMT    | 1         | 1      | 0.95%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 13     | 18.03%  |
| Transcend           | 10        | 11     | 16.39%  |
| SanDisk             | 5         | 5      | 8.2%    |
| Samsung Electronics | 5         | 7      | 8.2%    |
| Micron Technology   | 5         | 5      | 8.2%    |
| A-DATA Technology   | 4         | 4      | 6.56%   |
| Toshiba             | 2         | 3      | 3.28%   |
| Ramsta              | 2         | 2      | 3.28%   |
| KingSpec            | 2         | 2      | 3.28%   |
| WDC WDS4            | 1         | 1      | 1.64%   |
| WALTON              | 1         | 2      | 1.64%   |
| Teutons             | 1         | 1      | 1.64%   |
| SK hynix            | 1         | 1      | 1.64%   |
| PNY                 | 1         | 1      | 1.64%   |
| Kingston            | 1         | 1      | 1.64%   |
| Intel               | 1         | 1      | 1.64%   |
| HS-SSD-E100         | 1         | 1      | 1.64%   |
| Hewlett-Packard     | 1         | 1      | 1.64%   |
| Gigabyte Technology | 1         | 1      | 1.64%   |
| GeIL                | 1         | 1      | 1.64%   |
| Crucial             | 1         | 2      | 1.64%   |
| Corsair             | 1         | 2      | 1.64%   |
| China               | 1         | 1      | 1.64%   |
| Apacer              | 1         | 1      | 1.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 105       | 134    | 53.03%  |
| SSD     | 58        | 70     | 29.29%  |
| NVMe    | 31        | 43     | 15.66%  |
| Unknown | 4         | 4      | 2.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 133       | 206    | 79.64%  |
| NVMe | 31        | 42     | 18.56%  |
| SAS  | 3         | 3      | 1.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 80        | 104    | 51.28%  |
| 0.51-1.0   | 74        | 98     | 47.44%  |
| 1.01-2.0   | 2         | 2      | 1.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 45        | 27.61%  |
| 251-500        | 38        | 23.31%  |
| 501-1000       | 34        | 20.86%  |
| 51-100         | 15        | 9.2%    |
| 1001-2000      | 13        | 7.98%   |
| 1-20           | 8         | 4.91%   |
| 21-50          | 7         | 4.29%   |
| Unknown        | 2         | 1.23%   |
| More than 3000 | 1         | 0.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 59        | 34.5%   |
| 21-50     | 31        | 18.13%  |
| 101-250   | 30        | 17.54%  |
| 51-100    | 29        | 16.96%  |
| 251-500   | 10        | 5.85%   |
| 501-1000  | 8         | 4.68%   |
| 1001-2000 | 2         | 1.17%   |
| Unknown   | 2         | 1.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                         | 2         | 4      | 10.53%  |
| HGST HTS541010A9E680 1TB                       | 2         | 2      | 10.53%  |
| WDC WD5000LPCX-22VHAT0 500GB                   | 1         | 1      | 5.26%   |
| WDC WD5000BPVT-22HXZT3 500GB                   | 1         | 1      | 5.26%   |
| WDC WD10SPZX-24Z10T0 1TB                       | 1         | 1      | 5.26%   |
| WDC WD10JPVX-60JC3T0 1TB                       | 1         | 2      | 5.26%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 5.26%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD          | 1         | 1      | 5.26%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 5.26%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 5.26%   |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 5.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 1         | 1      | 5.26%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 5.26%   |
| Intel SSDSCKKW240H6 240GB                      | 1         | 1      | 5.26%   |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 5.26%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 5.26%   |
| Hewlett-Packard SSD S600 240GB                 | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 4         | 5      | 21.05%  |
| Seagate           | 4         | 4      | 21.05%  |
| HGST              | 4         | 4      | 21.05%  |
| Toshiba           | 3         | 5      | 15.79%  |
| SK hynix          | 1         | 1      | 5.26%   |
| Micron Technology | 1         | 1      | 5.26%   |
| Intel             | 1         | 1      | 5.26%   |
| Hewlett-Packard   | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 5      | 26.67%  |
| Seagate | 4         | 4      | 26.67%  |
| HGST    | 4         | 4      | 26.67%  |
| Toshiba | 3         | 5      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 18     | 78.95%  |
| SSD  | 4         | 4      | 21.05%  |

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
| Detected | 94        | 148    | 56.29%  |
| Works    | 54        | 81     | 32.34%  |
| Malfunc  | 19        | 22     | 11.38%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 138       | 79.31%  |
| AMD                            | 10        | 5.75%   |
| SanDisk                        | 6         | 3.45%   |
| Kingston Technology Company    | 4         | 2.3%    |
| Phison Electronics             | 3         | 1.72%   |
| Toshiba America Info Systems   | 2         | 1.15%   |
| SK hynix                       | 2         | 1.15%   |
| Shenzhen Longsys Electronics   | 2         | 1.15%   |
| Samsung Electronics            | 2         | 1.15%   |
| Solid State Storage Technology | 1         | 0.57%   |
| Silicon Motion                 | 1         | 0.57%   |
| Micron Technology              | 1         | 0.57%   |
| KIOXIA                         | 1         | 0.57%   |
| Biwin Storage Technology       | 1         | 0.57%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 50        | 27.03%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 14        | 7.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 5.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 5.95%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 5.41%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9         | 4.86%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 9         | 4.86%   |
| Intel Volume Management Device NVMe RAID Controller                              | 7         | 3.78%   |
| Intel SSD 660P Series                                                            | 6         | 3.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 2.7%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 1.62%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.08%   |
| Phison E12 NVMe Controller                                                       | 2         | 1.08%   |
| Kingston Company Company Non-Volatile memory controller                          | 2         | 1.08%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.08%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 1         | 0.54%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.54%   |
| Solid State Storage Non-Volatile memory controller                               | 1         | 0.54%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 0.54%   |
| SK hynix BC511                                                                   | 1         | 0.54%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.54%   |
| Shenzhen Longsys Non-Volatile memory controller                                  | 1         | 0.54%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                      | 1         | 0.54%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.54%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.54%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.54%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.54%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 0.54%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.54%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 1         | 0.54%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.54%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.54%   |
| Intel Comet Lake PCH-H RAID                                                      | 1         | 0.54%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 125       | 69.06%  |
| NVMe | 31        | 17.13%  |
| RAID | 22        | 12.15%  |
| IDE  | 3         | 1.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 142       | 91.61%  |
| AMD    | 13        | 8.39%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 7.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 4.52%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 7         | 4.52%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 3.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 3.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 3.87%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 3.23%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 3.23%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 2.58%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 2.58%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 2.58%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 4         | 2.58%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 2.58%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 2.58%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 1.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.94%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.94%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 1.94%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 1.94%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 1.29%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.29%   |
| Intel Core i3-7130U CPU @ 2.70GHz             | 2         | 1.29%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.29%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.29%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.29%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 2         | 1.29%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.65%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.65%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.65%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 0.65%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.65%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 0.65%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 0.65%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 0.65%   |
| Intel Core i5-4200H CPU @ 2.80GHz             | 1         | 0.65%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 0.65%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 0.65%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 68        | 43.87%  |
| Intel Core i3    | 37        | 23.87%  |
| Intel Core i7    | 15        | 9.68%   |
| Other            | 10        | 6.45%   |
| AMD Ryzen 5      | 6         | 3.87%   |
| Intel Pentium    | 5         | 3.23%   |
| Intel Celeron    | 4         | 2.58%   |
| AMD Ryzen 7      | 4         | 2.58%   |
| Intel Atom       | 2         | 1.29%   |
| AMD Ryzen 3      | 2         | 1.29%   |
| Intel Core 2 Duo | 1         | 0.65%   |
| AMD E2           | 1         | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 103       | 66.45%  |
| 4      | 44        | 28.39%  |
| 8      | 4         | 2.58%   |
| 6      | 3         | 1.94%   |
| 1      | 1         | 0.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 155       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 143       | 92.26%  |
| 1      | 12        | 7.74%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 154       | 99.35%  |
| Unknown        | 1         | 0.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 35        | 21.6%   |
| 0x806e9    | 22        | 13.58%  |
| 0x806ea    | 15        | 9.26%   |
| 0x406e3    | 11        | 6.79%   |
| 0x40651    | 10        | 6.17%   |
| 0x306d4    | 9         | 5.56%   |
| 0x306a9    | 7         | 4.32%   |
| 0x206a7    | 7         | 4.32%   |
| 0x806eb    | 6         | 3.7%    |
| 0x806ec    | 5         | 3.09%   |
| 0x806c1    | 5         | 3.09%   |
| 0x706e5    | 4         | 2.47%   |
| 0x406c4    | 4         | 2.47%   |
| 0x08108102 | 3         | 1.85%   |
| 0xa0652    | 2         | 1.23%   |
| 0x306c3    | 2         | 1.23%   |
| 0x08108109 | 2         | 1.23%   |
| 0x906e9    | 1         | 0.62%   |
| 0x806d1    | 1         | 0.62%   |
| 0x506e3    | 1         | 0.62%   |
| 0x406c3    | 1         | 0.62%   |
| 0x30678    | 1         | 0.62%   |
| 0x30661    | 1         | 0.62%   |
| 0x20655    | 1         | 0.62%   |
| 0x106ca    | 1         | 0.62%   |
| 0x10676    | 1         | 0.62%   |
| 0x0a50000c | 1         | 0.62%   |
| 0x08600104 | 1         | 0.62%   |
| 0x0810100b | 1         | 0.62%   |
| 0x06006705 | 1         | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 56        | 36.13%  |
| Skylake     | 16        | 10.32%  |
| Haswell     | 14        | 9.03%   |
| Broadwell   | 11        | 7.1%    |
| IvyBridge   | 10        | 6.45%   |
| TigerLake   | 9         | 5.81%   |
| SandyBridge | 9         | 5.81%   |
| Zen+        | 6         | 3.87%   |
| Silvermont  | 6         | 3.87%   |
| Icelake     | 5         | 3.23%   |
| Zen 3       | 2         | 1.29%   |
| Zen 2       | 2         | 1.29%   |
| CometLake   | 2         | 1.29%   |
| Bonnell     | 2         | 1.29%   |
| Zen         | 1         | 0.65%   |
| Westmere    | 1         | 0.65%   |
| Penryn      | 1         | 0.65%   |
| Excavator   | 1         | 0.65%   |
| Unknown     | 1         | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 142       | 71.72%  |
| Nvidia | 39        | 19.7%   |
| AMD    | 17        | 8.59%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 26        | 13%     |
| Intel UHD Graphics 620                                                                   | 15        | 7.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 7.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 6%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 6%      |
| Intel HD Graphics 5500                                                                   | 10        | 5%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 5%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.5%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 4%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 3%      |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 2.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.5%    |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 2%      |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 2%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 2%      |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 2%      |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 1.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1%      |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 1%      |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1%      |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1%      |
| AMD Renoir                                                                               | 2         | 1%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1%      |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 1%      |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.5%    |
| Nvidia TU117M                                                                            | 1         | 0.5%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.5%    |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.5%    |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.5%    |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.5%    |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.5%    |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.5%    |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.5%    |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.5%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.5%    |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.5%    |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.5%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 103       | 66.45%  |
| Intel + Nvidia | 35        | 22.58%  |
| 1 x AMD        | 7         | 4.52%   |
| Intel + AMD    | 4         | 2.58%   |
| AMD + Nvidia   | 4         | 2.58%   |
| 2 x AMD        | 2         | 1.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 137       | 86.16%  |
| Proprietary | 20        | 12.58%  |
| Unknown     | 2         | 1.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 126       | 79.25%  |
| 1.01-2.0   | 20        | 12.58%  |
| 3.01-4.0   | 7         | 4.4%    |
| 0.01-0.5   | 3         | 1.89%   |
| 7.01-8.0   | 1         | 0.63%   |
| 5.01-6.0   | 1         | 0.63%   |
| 0.51-1.0   | 1         | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 43        | 24.43%  |
| AU Optronics            | 40        | 22.73%  |
| Chimei Innolux          | 33        | 18.75%  |
| LG Display              | 26        | 14.77%  |
| Samsung Electronics     | 9         | 5.11%   |
| Dell                    | 5         | 2.84%   |
| PANDA                   | 4         | 2.27%   |
| Goldstar                | 4         | 2.27%   |
| Hewlett-Packard         | 3         | 1.7%    |
| Chi Mei Optoelectronics | 2         | 1.14%   |
| ViewSonic               | 1         | 0.57%   |
| Sharp                   | 1         | 0.57%   |
| MSI                     | 1         | 0.57%   |
| ASUSTek Computer        | 1         | 0.57%   |
| Apple                   | 1         | 0.57%   |
| AOC                     | 1         | 0.57%   |
| Ancor Communications    | 1         | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 9         | 5.11%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 4         | 2.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 2.27%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 3         | 1.7%    |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                 | 3         | 1.7%    |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 3         | 1.7%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 3         | 1.7%    |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 1.14%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 2         | 1.14%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch           | 2         | 1.14%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 1.14%   |
| LG Display LCD Monitor LGD0466 1366x768 309x174mm 14.0-inch           | 2         | 1.14%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 2         | 1.14%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch       | 2         | 1.14%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 1.14%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 1.14%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                  | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 2         | 1.14%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 1.14%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch         | 1         | 0.57%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM043E 1600x1200 520x320mm 24.0-inch  | 1         | 0.57%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch     | 1         | 0.57%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch      | 1         | 0.57%   |
| Samsung Electronics S19C300 SAM0A12 1366x768 410x230mm 18.5-inch      | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch  | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4751 1366x768 344x194mm 15.5-inch  | 1         | 0.57%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.57%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.57%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.57%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.57%   |
| MSI MP241 MSI3BA9 1920x1080 527x296mm 23.8-inch                       | 1         | 0.57%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 81        | 48.8%   |
| 1920x1080 (FHD)   | 69        | 41.57%  |
| 1600x900 (HD+)    | 4         | 2.41%   |
| 3840x2160 (4K)    | 3         | 1.81%   |
| 1280x800 (WXGA)   | 2         | 1.2%    |
| 1024x600          | 2         | 1.2%    |
| 2560x1600         | 1         | 0.6%    |
| 2560x1440 (QHD)   | 1         | 0.6%    |
| 2240x1400         | 1         | 0.6%    |
| 1920x1200 (WUXGA) | 1         | 0.6%    |
| 1280x1024 (SXGA)  | 1         | 0.6%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 74        | 42.29%  |
| 13     | 40        | 22.86%  |
| 14     | 29        | 16.57%  |
| 21     | 8         | 4.57%   |
| 18     | 7         | 4%      |
| 12     | 5         | 2.86%   |
| 23     | 2         | 1.14%   |
| 17     | 2         | 1.14%   |
| 11     | 2         | 1.14%   |
| 10     | 2         | 1.14%   |
| 27     | 1         | 0.57%   |
| 26     | 1         | 0.57%   |
| 24     | 1         | 0.57%   |
| 19     | 1         | 0.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 135       | 77.59%  |
| 401-500     | 17        | 9.77%   |
| 201-300     | 17        | 9.77%   |
| 501-600     | 4         | 2.3%    |
| 351-400     | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 150       | 96.15%  |
| 16/10 | 5         | 3.21%   |
| 5/4   | 1         | 0.64%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 74        | 42.53%  |
| 81-90          | 62        | 35.63%  |
| 141-150        | 8         | 4.6%    |
| 71-80          | 7         | 4.02%   |
| 201-250        | 7         | 4.02%   |
| 61-70          | 5         | 2.87%   |
| 151-200        | 3         | 1.72%   |
| 51-60          | 2         | 1.15%   |
| 41-50          | 2         | 1.15%   |
| 251-300        | 2         | 1.15%   |
| 301-350        | 1         | 0.57%   |
| 121-130        | 1         | 0.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 78        | 46.15%  |
| 121-160       | 71        | 42.01%  |
| 51-100        | 13        | 7.69%   |
| 161-240       | 6         | 3.55%   |
| More than 240 | 1         | 0.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 136       | 86.62%  |
| 2     | 19        | 12.1%   |
| 3     | 1         | 0.64%   |
| 0     | 1         | 0.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 105       | 42.86%  |
| Intel                 | 76        | 31.02%  |
| Qualcomm Atheros      | 45        | 18.37%  |
| Broadcom              | 6         | 2.45%   |
| Ralink Technology     | 3         | 1.22%   |
| MediaTek              | 3         | 1.22%   |
| Xiaomi                | 2         | 0.82%   |
| TP-Link               | 1         | 0.41%   |
| Samsung Electronics   | 1         | 0.41%   |
| Ralink                | 1         | 0.41%   |
| Dell                  | 1         | 0.41%   |
| Arduino SA            | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67        | 23.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 7.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 18        | 6.43%   |
| Intel Wireless 8265 / 8275                                        | 14        | 5%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 4.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 3.93%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 3.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 8         | 2.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7         | 2.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 2.14%   |
| Intel Wireless 3165                                               | 6         | 2.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.14%   |
| Intel Wireless 8260                                               | 5         | 1.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.43%   |
| Intel Wireless 7265                                               | 4         | 1.43%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.43%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 1.07%   |
| Intel Wireless 7260                                               | 3         | 1.07%   |
| Intel Wireless 3160                                               | 3         | 1.07%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.07%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 1.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.71%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.71%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.71%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.71%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.71%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.36%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.36%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.36%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.36%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 74        | 46.84%  |
| Qualcomm Atheros      | 44        | 27.85%  |
| Realtek Semiconductor | 27        | 17.09%  |
| Broadcom              | 4         | 2.53%   |
| Ralink Technology     | 3         | 1.9%    |
| MediaTek              | 3         | 1.9%    |
| TP-Link               | 1         | 0.63%   |
| Ralink                | 1         | 0.63%   |
| Dell                  | 1         | 0.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 18        | 11.39%  |
| Intel Wireless 8265 / 8275                                     | 14        | 8.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12        | 7.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 6.96%   |
| Intel Wi-Fi 6 AX201                                            | 9         | 5.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 5.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 4.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 3.8%    |
| Intel Wireless 3165                                            | 6         | 3.8%    |
| Intel Wireless 8260                                            | 5         | 3.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.53%   |
| Intel Wireless 7265                                            | 4         | 2.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.53%   |
| Ralink MT7601U Wireless Adapter                                | 3         | 1.9%    |
| Intel Wireless 7260                                            | 3         | 1.9%    |
| Intel Wireless 3160                                            | 3         | 1.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.27%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.27%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 1.27%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.27%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.63%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.63%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.63%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 0.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.63%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 0.63%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 0.63%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 0.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 0.63%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 1         | 0.63%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 0.63%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 93        | 76.86%  |
| Intel                 | 18        | 14.88%  |
| Qualcomm Atheros      | 4         | 3.31%   |
| Broadcom              | 3         | 2.48%   |
| Xiaomi                | 2         | 1.65%   |
| Samsung Electronics   | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67        | 55.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 18.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 4.96%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 3.31%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.65%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.83%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.83%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.83%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.83%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.83%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.83%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.83%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.83%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.83%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.83%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 152       | 55.88%  |
| Ethernet | 119       | 43.75%  |
| Modem    | 1         | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 136       | 86.08%  |
| Ethernet | 22        | 13.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 111       | 71.61%  |
| 1     | 44        | 28.39%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 155       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 62        | 46.97%  |
| IMC Networks                    | 21        | 15.91%  |
| Realtek Semiconductor           | 14        | 10.61%  |
| Qualcomm Atheros Communications | 11        | 8.33%   |
| Lite-On Technology              | 10        | 7.58%   |
| Broadcom                        | 7         | 5.3%    |
| Foxconn / Hon Hai               | 4         | 3.03%   |
| Toshiba                         | 1         | 0.76%   |
| Ralink                          | 1         | 0.76%   |
| Hewlett-Packard                 | 1         | 0.76%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 35        | 26.52%  |
| IMC Networks Bluetooth Device                     | 12        | 9.09%   |
| Realtek Bluetooth Radio                           | 10        | 7.58%   |
| Intel Wireless-AC 3168 Bluetooth                  | 10        | 7.58%   |
| Intel AX201 Bluetooth                             | 10        | 7.58%   |
| IMC Networks Bluetooth Radio                      | 7         | 5.3%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 6         | 4.55%   |
| Qualcomm Atheros  Bluetooth Device                | 5         | 3.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 4         | 3.03%   |
| Realtek  Bluetooth 4.2 Adapter                    | 3         | 2.27%   |
| Lite-On Bluetooth Device                          | 3         | 2.27%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 2         | 1.52%   |
| Intel AX200 Bluetooth                             | 2         | 1.52%   |
| Foxconn / Hon Hai Bluetooth Device                | 2         | 1.52%   |
| Broadcom HP Portable SoftSailing                  | 2         | 1.52%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 2         | 1.52%   |
| Toshiba Bluetooth Radio                           | 1         | 0.76%   |
| Realtek RTL8821A Bluetooth                        | 1         | 0.76%   |
| Ralink RT3290 Bluetooth                           | 1         | 0.76%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 0.76%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 0.76%   |
| Qualcomm Atheros AR3012 Bluetooth                 | 1         | 0.76%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 1         | 0.76%   |
| Lite-On Atheros AR3012 Bluetooth                  | 1         | 0.76%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 0.76%   |
| IMC Networks Wireless_Device                      | 1         | 0.76%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 1         | 0.76%   |
| HP Broadcom 2070 Bluetooth Combo                  | 1         | 0.76%   |
| Foxconn / Hon Hai Wireless_Device                 | 1         | 0.76%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller   | 1         | 0.76%   |
| Broadcom BCM43142A0 Bluetooth 4.0                 | 1         | 0.76%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 1         | 0.76%   |
| Broadcom BCM20702A0 Bluetooth 4.0                 | 1         | 0.76%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 141       | 87.04%  |
| AMD                    | 13        | 8.02%   |
| Nvidia                 | 7         | 4.32%   |
| Generalplus Technology | 1         | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 56        | 28.14%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 6.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 12        | 6.03%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 6.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 6.03%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 6.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 5.53%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 5.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 4.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 3.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 2.51%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 2.01%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.01%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.01%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.01%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.01%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.01%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.5%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Intel USB PnP Sound Device                                                                        | 1         | 0.5%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.5%    |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 0.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.5%    |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.5%    |
| AMD High Definition Audio Controller                                                              | 1         | 0.5%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 29.91%  |
| SK hynix            | 28        | 26.17%  |
| Micron Technology   | 15        | 14.02%  |
| A-DATA Technology   | 6         | 5.61%   |
| Kingston            | 5         | 4.67%   |
| G.Skill             | 4         | 3.74%   |
| Unknown             | 3         | 2.8%    |
| Transcend           | 3         | 2.8%    |
| Team                | 2         | 1.87%   |
| Ramaxel Technology  | 2         | 1.87%   |
| Nanya Technology    | 2         | 1.87%   |
| Unknown (C509)      | 1         | 0.93%   |
| Unknown (768A)      | 1         | 0.93%   |
| Elpida              | 1         | 0.93%   |
| Crucial             | 1         | 0.93%   |
| Unknown             | 1         | 0.93%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 4.67%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 3.74%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s         | 3         | 2.8%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 2.8%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.8%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.87%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 1.87%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.87%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.87%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.87%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.87%   |
| Samsung RAM M471A1K44BM0-CRC 8192MB SODIMM DDR4 2400MT/s         | 2         | 1.87%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.87%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.87%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 2         | 1.87%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 2         | 1.87%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 2         | 1.87%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.93%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.93%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.93%   |
| Unknown (C509) RAM Module 4GB SODIMM DDR4 2400MT/s               | 1         | 0.93%   |
| Unknown (768A) RAM Module 8192MB SODIMM DDR4 3200MT/s            | 1         | 0.93%   |
| Transcend RAM JM3200HSB-8G 8GB SODIMM DDR4 3200MT/s              | 1         | 0.93%   |
| Transcend RAM JM2666HSG-8G 8GB SODIMM DDR4 2667MT/s              | 1         | 0.93%   |
| Transcend RAM JM2400HSB-8G 8GB SODIMM DDR4 2400MT/s              | 1         | 0.93%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 1         | 0.93%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s            | 1         | 0.93%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 1         | 0.93%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2133MT/s                  | 1         | 0.93%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.93%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.93%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.93%   |
| SK hynix RAM H9CCNNNBJTMLAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.93%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 53        | 66.25%  |
| DDR3   | 22        | 27.5%   |
| LPDDR4 | 3         | 3.75%   |
| LPDDR3 | 2         | 2.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 75        | 96.15%  |
| Row Of Chips | 3         | 3.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 40        | 44.44%  |
| 8192  | 38        | 42.22%  |
| 16384 | 7         | 7.78%   |
| 2048  | 4         | 4.44%   |
| 32768 | 1         | 1.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 27        | 31.03%  |
| 1600  | 18        | 20.69%  |
| 2400  | 13        | 14.94%  |
| 3200  | 10        | 11.49%  |
| 2133  | 10        | 11.49%  |
| 3266  | 2         | 2.3%    |
| 1334  | 2         | 2.3%    |
| 1067  | 2         | 2.3%    |
| 8400  | 1         | 1.15%   |
| 1867  | 1         | 1.15%   |
| 1333  | 1         | 1.15%   |

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
| Chicony Electronics                    | 34        | 23.29%  |
| IMC Networks                           | 28        | 19.18%  |
| Cheng Uei Precision Industry (Foxlink) | 15        | 10.27%  |
| Realtek Semiconductor                  | 12        | 8.22%   |
| Sunplus Innovation Technology          | 9         | 6.16%   |
| Quanta                                 | 9         | 6.16%   |
| Acer                                   | 8         | 5.48%   |
| Microdia                               | 7         | 4.79%   |
| Lite-On Technology                     | 7         | 4.79%   |
| Suyin                                  | 5         | 3.42%   |
| Luxvisions Innotech Limited            | 5         | 3.42%   |
| Silicon Motion                         | 2         | 1.37%   |
| Primax Electronics                     | 2         | 1.37%   |
| Syntek                                 | 1         | 0.68%   |
| Sonix Technology                       | 1         | 0.68%   |
| Apple                                  | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                           | 10        | 6.85%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 9         | 6.16%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 8         | 5.48%   |
| IMC Networks VGA UVC WebCam                             | 5         | 3.42%   |
| Microdia Integrated_Webcam_HD                           | 4         | 2.74%   |
| Luxvisions Innotech Limited HP HD Camera                | 4         | 2.74%   |
| Lite-On HP HD Camera                                    | 4         | 2.74%   |
| Chicony HD WebCam                                       | 4         | 2.74%   |
| Suyin Integrated_Webcam_HD                              | 3         | 2.05%   |
| Realtek Integrated_Webcam_HD                            | 3         | 2.05%   |
| Quanta HD Webcam                                        | 3         | 2.05%   |
| IMC Networks USB2.0 HD IR UVC WebCam                    | 3         | 2.05%   |
| IMC Networks Integrated Camera                          | 3         | 2.05%   |
| Chicony EasyCamera                                      | 3         | 2.05%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 3         | 2.05%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 3         | 2.05%   |
| Acer HD Webcam                                          | 3         | 2.05%   |
| Suyin HP Truevision HD                                  | 2         | 1.37%   |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 1.37%   |
| Realtek USB2.0 VGA UVC WebCam                           | 2         | 1.37%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.37%   |
| Realtek USB Camera                                      | 2         | 1.37%   |
| Quanta HD User Facing                                   | 2         | 1.37%   |
| Primax HP HD Webcam [Fixed]                             | 2         | 1.37%   |
| Lite-On Integrated Camera                               | 2         | 1.37%   |
| Chicony USB2.0 Camera                                   | 2         | 1.37%   |
| Chicony Integrated Camera                               | 2         | 1.37%   |
| Chicony HP Truevision HD camera                         | 2         | 1.37%   |
| Chicony HP HD Webcam                                    | 2         | 1.37%   |
| Chicony HP HD Camera                                    | 2         | 1.37%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.37%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.37%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 2         | 1.37%   |
| Acer Lenovo EasyCamera                                  | 2         | 1.37%   |
| Syntek Integrated Camera                                | 1         | 0.68%   |
| Sunplus XiaoMi USB 2.0 Webcam                           | 1         | 0.68%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 0.68%   |
| Sunplus Integrated Webcam                               | 1         | 0.68%   |
| Sunplus HP HD Webcam [Fixed]                            | 1         | 0.68%   |
| Sunplus HD WebCam                                       | 1         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 25        | 80.65%  |
| Synaptics                  | 3         | 9.68%   |
| Elan Microelectronics      | 2         | 6.45%   |
| Shenzhen Goodix Technology | 1         | 3.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 45.16%  |
| Validity Sensors VFS491                                                    | 3         | 9.68%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 9.68%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 6.45%   |
| Elan ELAN:Fingerprint                                                      | 2         | 6.45%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.23%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.23%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.23%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 3.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.23%   |
| Synaptics  WBDI                                                            | 1         | 3.23%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 3.23%   |

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
| 0     | 104       | 64.6%   |
| 1     | 50        | 31.06%  |
| 2     | 6         | 3.73%   |
| 3     | 1         | 0.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 31        | 50.82%  |
| Graphics card         | 15        | 24.59%  |
| Chipcard              | 5         | 8.2%    |
| Net/wireless          | 3         | 4.92%   |
| Camera                | 3         | 4.92%   |
| Multimedia controller | 2         | 3.28%   |
| Card reader           | 1         | 1.64%   |
| Bluetooth             | 1         | 1.64%   |

