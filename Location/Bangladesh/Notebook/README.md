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

Total: 208

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 34        | 21.79%  |
| Arch                         | 9         | 5.77%   |
| ArcoLinux Rolling            | 8         | 5.13%   |
| KDE neon 20.04               | 5         | 3.21%   |
| Ubuntu 19.10                 | 4         | 2.56%   |
| Ubuntu 18.04                 | 4         | 2.56%   |
| Manjaro                      | 4         | 2.56%   |
| Fedora 33                    | 4         | 2.56%   |
| Zorin 16                     | 3         | 1.92%   |
| OpenMandriva 4.2             | 3         | 1.92%   |
| Manjaro 20.0.1               | 3         | 1.92%   |
| Arch Rolling                 | 3         | 1.92%   |
| Zorin 15                     | 2         | 1.28%   |
| Ubuntu 22.04                 | 2         | 1.28%   |
| Ubuntu 19.04                 | 2         | 1.28%   |
| Ubuntu 18.10                 | 2         | 1.28%   |
| Pop!_OS 22.04                | 2         | 1.28%   |
| Pop!_OS 21.10                | 2         | 1.28%   |
| OpenMandriva 4.90            | 2         | 1.28%   |
| Manjaro 21.2.6               | 2         | 1.28%   |
| Manjaro 18.0.4               | 2         | 1.28%   |
| Linux Mint 20.1              | 2         | 1.28%   |
| Linux Mint 20                | 2         | 1.28%   |
| Kubuntu 20.04                | 2         | 1.28%   |
| Fedora 34                    | 2         | 1.28%   |
| Debian 11                    | 2         | 1.28%   |
| Ubuntu Unity 16.04           | 1         | 0.64%   |
| Ubuntu 21.04                 | 1         | 0.64%   |
| Ubuntu 20.10                 | 1         | 0.64%   |
| Pop!_OS 21.04                | 1         | 0.64%   |
| Pop!_OS 20.10                | 1         | 0.64%   |
| Parrot 4.5                   | 1         | 0.64%   |
| Parrot 4.11                  | 1         | 0.64%   |
| Parrot 4.10                  | 1         | 0.64%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.64%   |
| Manjaro 21.2.1               | 1         | 0.64%   |
| Manjaro 21.1.2               | 1         | 0.64%   |
| Manjaro 21.0.5               | 1         | 0.64%   |
| Manjaro 21.0.4               | 1         | 0.64%   |
| Manjaro 21.0.3               | 1         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 49        | 33.79%  |
| Manjaro      | 17        | 11.72%  |
| Arch         | 12        | 8.28%   |
| Linux Mint   | 8         | 5.52%   |
| ArcoLinux    | 8         | 5.52%   |
| Fedora       | 7         | 4.83%   |
| Pop!_OS      | 6         | 4.14%   |
| Zorin        | 5         | 3.45%   |
| OpenMandriva | 5         | 3.45%   |
| KDE neon     | 5         | 3.45%   |
| Kubuntu      | 4         | 2.76%   |
| Endless      | 4         | 2.76%   |
| Debian       | 3         | 2.07%   |
| Parrot       | 2         | 1.38%   |
| EndeavourOS  | 2         | 1.38%   |
| Ubuntu Unity | 1         | 0.69%   |
| openSUSE     | 1         | 0.69%   |
| LMDE         | 1         | 0.69%   |
| Deepin       | 1         | 0.69%   |
| Clear Linux  | 1         | 0.69%   |
| CentOS       | 1         | 0.69%   |
| BlackPanther | 1         | 0.69%   |
| Artix        | 1         | 0.69%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 7         | 4.09%   |
| 5.4.0-52-generic         | 3         | 1.75%   |
| 5.4.0-40-generic         | 3         | 1.75%   |
| 5.4.0-29-generic         | 3         | 1.75%   |
| 5.10.14-desktop-1omv4002 | 3         | 1.75%   |
| 5.9.16-1-MANJARO         | 2         | 1.17%   |
| 5.8.0-50-generic         | 2         | 1.17%   |
| 5.8.0-41-generic         | 2         | 1.17%   |
| 5.8.0-14-generic         | 2         | 1.17%   |
| 5.7.19-2-MANJARO         | 2         | 1.17%   |
| 5.6.11-1-MANJARO         | 2         | 1.17%   |
| 5.4.8-arch1-1            | 2         | 1.17%   |
| 5.4.0-53-generic         | 2         | 1.17%   |
| 5.4.0-19-generic         | 2         | 1.17%   |
| 5.3.0-24-generic         | 2         | 1.17%   |
| 5.3.0-23-generic         | 2         | 1.17%   |
| 5.18.12-desktop-3omv4090 | 2         | 1.17%   |
| 5.15.0-48-generic        | 2         | 1.17%   |
| 5.15.0-46-generic        | 2         | 1.17%   |
| 5.13.0-28-generic        | 2         | 1.17%   |
| 5.11.0-40-generic        | 2         | 1.17%   |
| 5.11.0-27-generic        | 2         | 1.17%   |
| 5.10.52-1-lts            | 2         | 1.17%   |
| 5.9.16-200.fc33.x86_64   | 1         | 0.58%   |
| 5.9.11-200.fc33.x86_64   | 1         | 0.58%   |
| 5.8.4-200.fc32.x86_64    | 1         | 0.58%   |
| 5.8.16.a-1-hardened      | 1         | 0.58%   |
| 5.8.12-1-default         | 1         | 0.58%   |
| 5.8.0-7630-generic       | 1         | 0.58%   |
| 5.8.0-63-generic         | 1         | 0.58%   |
| 5.8.0-55-generic         | 1         | 0.58%   |
| 5.8.0-44-generic         | 1         | 0.58%   |
| 5.8.0-43-generic         | 1         | 0.58%   |
| 5.8.0-40-generic         | 1         | 0.58%   |
| 5.8.0-38-generic         | 1         | 0.58%   |
| 5.7.0-2parrot2-amd64     | 1         | 0.58%   |
| 5.4.81-1-lts             | 1         | 0.58%   |
| 5.4.68-1-lts             | 1         | 0.58%   |
| 5.4.64-1-lts             | 1         | 0.58%   |
| 5.4.40-1-MANJARO         | 1         | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 28        | 17.18%  |
| 5.8.0   | 13        | 7.98%   |
| 5.11.0  | 11        | 6.75%   |
| 5.13.0  | 8         | 4.91%   |
| 5.3.0   | 6         | 3.68%   |
| 5.15.0  | 6         | 3.68%   |
| 5.10.0  | 4         | 2.45%   |
| 5.0.0   | 4         | 2.45%   |
| 4.18.0  | 4         | 2.45%   |
| 4.15.0  | 4         | 2.45%   |
| 5.9.16  | 3         | 1.84%   |
| 5.18.12 | 3         | 1.84%   |
| 5.10.14 | 3         | 1.84%   |
| 4.19.0  | 3         | 1.84%   |
| 5.7.19  | 2         | 1.23%   |
| 5.6.11  | 2         | 1.23%   |
| 5.4.8   | 2         | 1.23%   |
| 5.16.15 | 2         | 1.23%   |
| 5.15.5  | 2         | 1.23%   |
| 5.10.52 | 2         | 1.23%   |
| 5.9.11  | 1         | 0.61%   |
| 5.8.4   | 1         | 0.61%   |
| 5.8.16  | 1         | 0.61%   |
| 5.8.12  | 1         | 0.61%   |
| 5.7.0   | 1         | 0.61%   |
| 5.4.81  | 1         | 0.61%   |
| 5.4.68  | 1         | 0.61%   |
| 5.4.64  | 1         | 0.61%   |
| 5.4.40  | 1         | 0.61%   |
| 5.4.15  | 1         | 0.61%   |
| 5.19.9  | 1         | 0.61%   |
| 5.19.4  | 1         | 0.61%   |
| 5.19.0  | 1         | 0.61%   |
| 5.18.6  | 1         | 0.61%   |
| 5.18.16 | 1         | 0.61%   |
| 5.18.10 | 1         | 0.61%   |
| 5.17.9  | 1         | 0.61%   |
| 5.17.5  | 1         | 0.61%   |
| 5.17.4  | 1         | 0.61%   |
| 5.16.20 | 1         | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 21.79%  |
| 5.8     | 16        | 10.26%  |
| 5.15    | 15        | 9.62%   |
| 5.11    | 14        | 8.97%   |
| 5.10    | 13        | 8.33%   |
| 5.13    | 9         | 5.77%   |
| 5.3     | 6         | 3.85%   |
| 5.18    | 6         | 3.85%   |
| 5.16    | 5         | 3.21%   |
| 4.18    | 5         | 3.21%   |
| 5.9     | 4         | 2.56%   |
| 5.0     | 4         | 2.56%   |
| 4.19    | 4         | 2.56%   |
| 4.15    | 4         | 2.56%   |
| 5.7     | 3         | 1.92%   |
| 5.19    | 3         | 1.92%   |
| 5.17    | 3         | 1.92%   |
| 5.6     | 2         | 1.28%   |
| 5.14    | 2         | 1.28%   |
| 5.12    | 2         | 1.28%   |
| 5.1     | 2         | 1.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 140       | 98.59%  |
| i686   | 2         | 1.41%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| GNOME          | 74        | 50.34%  |
| KDE5           | 29        | 19.73%  |
| Unknown        | 17        | 11.56%  |
| X-Cinnamon     | 7         | 4.76%   |
| XFCE           | 6         | 4.08%   |
| awesome        | 3         | 2.04%   |
| MATE           | 2         | 1.36%   |
| KDE            | 2         | 1.36%   |
| i3-with-shmlog | 2         | 1.36%   |
| Unity          | 1         | 0.68%   |
| i3             | 1         | 0.68%   |
| DWM            | 1         | 0.68%   |
| Deepin         | 1         | 0.68%   |
| bspwm          | 1         | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 119       | 80.95%  |
| Wayland | 18        | 12.24%  |
| Unknown | 9         | 6.12%   |
| Tty     | 1         | 0.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 74        | 50.34%  |
| GDM     | 26        | 17.69%  |
| SDDM    | 23        | 15.65%  |
| LightDM | 9         | 6.12%   |
| GDM3    | 9         | 6.12%   |
| TDM     | 6         | 4.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 118       | 81.94%  |
| Unknown | 15        | 10.42%  |
| en_GB   | 4         | 2.78%   |
| C       | 4         | 2.78%   |
| en_IE   | 1         | 0.69%   |
| en_CA   | 1         | 0.69%   |
| en_AG   | 1         | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 76        | 52.41%  |
| BIOS | 69        | 47.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 117       | 81.82%  |
| Overlay | 12        | 8.39%   |
| Btrfs   | 10        | 6.99%   |
| Unknown | 3         | 2.1%    |
| Xfs     | 1         | 0.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 84        | 57.53%  |
| GPT     | 49        | 33.56%  |
| MBR     | 13        | 8.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 123       | 85.42%  |
| Yes       | 21        | 14.58%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 80        | 55.56%  |
| Yes       | 64        | 44.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 40        | 28.17%  |
| Hewlett-Packard     | 38        | 26.76%  |
| Lenovo              | 18        | 12.68%  |
| Dell                | 17        | 11.97%  |
| Acer                | 15        | 10.56%  |
| Notebook            | 4         | 2.82%   |
| MSI                 | 3         | 2.11%   |
| Toshiba             | 1         | 0.7%    |
| Timi                | 1         | 0.7%    |
| Samsung Electronics | 1         | 0.7%    |
| Fujitsu             | 1         | 0.7%    |
| Daffodil Computers  | 1         | 0.7%    |
| Apple               | 1         | 0.7%    |
| Unknown             | 1         | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP ProBook 450 G4                                     | 5         | 3.52%   |
| HP ProBook 450 G2                                     | 2         | 1.41%   |
| HP Notebook                                           | 2         | 1.41%   |
| HP EliteBook 840 G3                                   | 2         | 1.41%   |
| HP 14                                                 | 2         | 1.41%   |
| ASUS X510UQ                                           | 2         | 1.41%   |
| ASUS VivoBook_ASUSLaptop X531FL_S531FL                | 2         | 1.41%   |
| ASUS VivoBook_ASUSLaptop X530FN_S530FN                | 2         | 1.41%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA                | 2         | 1.41%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA                | 2         | 1.41%   |
| ASUS VivoBook 14_ASUS Laptop X407UA                   | 2         | 1.41%   |
| Acer Nitro AN515-43                                   | 2         | 1.41%   |
| Toshiba Satellite L645                                | 1         | 0.7%    |
| Timi Mi NoteBook Pro                                  | 1         | 0.7%    |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.7%    |
| Notebook W9x0LU                                       | 1         | 0.7%    |
| Notebook N750BU                                       | 1         | 0.7%    |
| Notebook N2x0LU                                       | 1         | 0.7%    |
| Notebook DCL C483                                     | 1         | 0.7%    |
| MSI Summit B14 A11MOT                                 | 1         | 0.7%    |
| MSI Modern 15 A5M                                     | 1         | 0.7%    |
| MSI GS63 7RD                                          | 1         | 0.7%    |
| Lenovo V330-14IKB 81B0                                | 1         | 0.7%    |
| Lenovo ThinkPad X230 2324F51                          | 1         | 0.7%    |
| Lenovo ThinkPad X230 2324A82                          | 1         | 0.7%    |
| Lenovo ThinkPad T450 20BUS2021M                       | 1         | 0.7%    |
| Lenovo ThinkPad T430s 2356GPU                         | 1         | 0.7%    |
| Lenovo ThinkPad L380 20M6S22500                       | 1         | 0.7%    |
| Lenovo ThinkPad E490 20N9S1XE00                       | 1         | 0.7%    |
| Lenovo ThinkPad E470 20H1A029SG                       | 1         | 0.7%    |
| Lenovo S10-3                                          | 1         | 0.7%    |
| Lenovo Legion 5 15ARH05H 82B1                         | 1         | 0.7%    |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7                      | 1         | 0.7%    |
| Lenovo IdeaPad 330-15IKB 81DE                         | 1         | 0.7%    |
| Lenovo IdeaPad 320-15IKB 81BG                         | 1         | 0.7%    |
| Lenovo IdeaPad 320-15IKB 80XL                         | 1         | 0.7%    |
| Lenovo IdeaPad 310-14ISK 80SL                         | 1         | 0.7%    |
| Lenovo IdeaPad 3 15ITL6 82H8                          | 1         | 0.7%    |
| Lenovo IdeaPad 3 15ADA05 81W1                         | 1         | 0.7%    |
| Lenovo IdeaPad 110-15IBR 80T7                         | 1         | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| ASUS VivoBook          | 18        | 12.68%  |
| HP ProBook             | 15        | 10.56%  |
| Acer Aspire            | 12        | 8.45%   |
| Dell Inspiron          | 9         | 6.34%   |
| Lenovo IdeaPad         | 8         | 5.63%   |
| Lenovo ThinkPad        | 7         | 4.93%   |
| HP EliteBook           | 7         | 4.93%   |
| Dell Latitude          | 6         | 4.23%   |
| HP Pavilion            | 2         | 1.41%   |
| HP Notebook            | 2         | 1.41%   |
| HP Laptop              | 2         | 1.41%   |
| HP ENVY                | 2         | 1.41%   |
| HP 15                  | 2         | 1.41%   |
| HP 14                  | 2         | 1.41%   |
| Dell XPS               | 2         | 1.41%   |
| ASUS X510UQ            | 2         | 1.41%   |
| Acer Nitro             | 2         | 1.41%   |
| Toshiba Satellite      | 1         | 0.7%    |
| Timi Mi                | 1         | 0.7%    |
| Samsung 300E5EV        | 1         | 0.7%    |
| Notebook W9x0LU        | 1         | 0.7%    |
| Notebook N750BU        | 1         | 0.7%    |
| Notebook N2x0LU        | 1         | 0.7%    |
| Notebook DCL           | 1         | 0.7%    |
| MSI Summit             | 1         | 0.7%    |
| MSI Modern             | 1         | 0.7%    |
| MSI GS63               | 1         | 0.7%    |
| Lenovo V330-14IKB      | 1         | 0.7%    |
| Lenovo S10-3           | 1         | 0.7%    |
| Lenovo Legion          | 1         | 0.7%    |
| HP ZHAN                | 1         | 0.7%    |
| HP Mini                | 1         | 0.7%    |
| HP 250                 | 1         | 0.7%    |
| HP 240                 | 1         | 0.7%    |
| Fujitsu LIFEBOOK       | 1         | 0.7%    |
| Daffodil Computers DCL | 1         | 0.7%    |
| ASUS ZenBook           | 1         | 0.7%    |
| ASUS X556URK           | 1         | 0.7%    |
| ASUS X556UQK           | 1         | 0.7%    |
| ASUS X555LF            | 1         | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2016 | 23        | 16.2%   |
| 2017 | 21        | 14.79%  |
| 2018 | 18        | 12.68%  |
| 2019 | 15        | 10.56%  |
| 2015 | 14        | 9.86%   |
| 2012 | 11        | 7.75%   |
| 2021 | 9         | 6.34%   |
| 2014 | 9         | 6.34%   |
| 2013 | 7         | 4.93%   |
| 2011 | 7         | 4.93%   |
| 2020 | 5         | 3.52%   |
| 2010 | 2         | 1.41%   |
| 2008 | 1         | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 142       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 131       | 90.34%  |
| Enabled  | 14        | 9.66%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 142       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 59        | 40.69%  |
| 3.01-4.0   | 43        | 29.66%  |
| 8.01-16.0  | 24        | 16.55%  |
| 16.01-24.0 | 14        | 9.66%   |
| 1.01-2.0   | 5         | 3.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 54        | 34.18%  |
| 2.01-3.0  | 51        | 32.28%  |
| 3.01-4.0  | 29        | 18.35%  |
| 4.01-8.0  | 13        | 8.23%   |
| 0.51-1.0  | 8         | 5.06%   |
| 8.01-16.0 | 2         | 1.27%   |
| 0.01-0.5  | 1         | 0.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 98        | 68.06%  |
| 2      | 44        | 30.56%  |
| 3      | 2         | 1.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 93        | 65.03%  |
| Yes       | 50        | 34.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 108       | 75.52%  |
| No        | 35        | 24.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 97.89%  |
| No        | 3         | 2.11%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 84.62%  |
| No        | 22        | 15.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Bangladesh | 142       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dhaka             | 88        | 59.46%  |
| Chittagong        | 10        | 6.76%   |
| Rajshahi          | 7         | 4.73%   |
| Jessore           | 6         | 4.05%   |
| Tongi             | 4         | 2.7%    |
| Khulna            | 3         | 2.03%   |
| Comilla           | 3         | 2.03%   |
| Sherpur           | 2         | 1.35%   |
| Narayanganj       | 2         | 1.35%   |
| Mirpur            | 2         | 1.35%   |
| Azimpur           | 2         | 1.35%   |
| Wari              | 1         | 0.68%   |
| Sylhet            | 1         | 0.68%   |
| Sirajganj         | 1         | 0.68%   |
| Savar Upazila     | 1         | 0.68%   |
| Rangpur City      | 1         | 0.68%   |
| Pirganj           | 1         | 0.68%   |
| Pabna Sadar       | 1         | 0.68%   |
| Pabna             | 1         | 0.68%   |
| NДЃrДЃyanganj | 1         | 0.68%   |
| Nilphamari        | 1         | 0.68%   |
| Natore            | 1         | 0.68%   |
| Nalitabari        | 1         | 0.68%   |
| LДЃkshДЃm     | 1         | 0.68%   |
| Jamalpur          | 1         | 0.68%   |
| Gulshan           | 1         | 0.68%   |
| Faridpur          | 1         | 0.68%   |
| Dewangonj         | 1         | 0.68%   |
| Bogra             | 1         | 0.68%   |
| Belkuchi          | 1         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate                        | 36        | 46     | 19.46%  |
| WDC                            | 34        | 46     | 18.38%  |
| Toshiba                        | 30        | 38     | 16.22%  |
| Transcend                      | 10        | 11     | 5.41%   |
| HGST                           | 9         | 9      | 4.86%   |
| SanDisk                        | 8         | 8      | 4.32%   |
| Intel                          | 6         | 7      | 3.24%   |
| Samsung Electronics            | 5         | 9      | 2.7%    |
| Micron Technology              | 5         | 5      | 2.7%    |
| Hitachi                        | 5         | 6      | 2.7%    |
| Kingston                       | 4         | 5      | 2.16%   |
| A-DATA Technology              | 4         | 4      | 2.16%   |
| SK hynix                       | 3         | 3      | 1.62%   |
| Corsair                        | 3         | 5      | 1.62%   |
| Ramsta                         | 2         | 2      | 1.08%   |
| KingSpec                       | 2         | 2      | 1.08%   |
| WDC WDS4                       | 1         | 1      | 0.54%   |
| Teutons                        | 1         | 1      | 0.54%   |
| Solid State Storage Technology | 1         | 1      | 0.54%   |
| Silicon Motion                 | 1         | 2      | 0.54%   |
| Shenzhen Longsys Electronics   | 1         | 1      | 0.54%   |
| Realtek                        | 1         | 1      | 0.54%   |
| PNY                            | 1         | 1      | 0.54%   |
| Phison                         | 1         | 1      | 0.54%   |
| Lexar                          | 1         | 2      | 0.54%   |
| KIOXIA                         | 1         | 1      | 0.54%   |
| Kingsand                       | 1         | 1      | 0.54%   |
| HS-SSD-E100                    | 1         | 1      | 0.54%   |
| Hewlett-Packard                | 1         | 1      | 0.54%   |
| Crucial                        | 1         | 2      | 0.54%   |
| Colorful                       | 1         | 1      | 0.54%   |
| China                          | 1         | 1      | 0.54%   |
| BIWIN                          | 1         | 1      | 0.54%   |
| Apacer                         | 1         | 1      | 0.54%   |
| Unknown                        | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 17        | 9.09%   |
| Toshiba MQ04ABF100 1TB               | 14        | 7.49%   |
| WDC WD10JPVX-60JC3T0 1TB             | 5         | 2.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 2.67%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 4         | 2.14%   |
| Toshiba MQ01ABD100 1TB               | 4         | 2.14%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 3         | 1.6%    |
| Transcend TS120GMTS420S 120GB SSD    | 3         | 1.6%    |
| Seagate ST500LT012-9WS142 500GB      | 3         | 1.6%    |
| Seagate ST1000LM049-2GH172 1TB       | 3         | 1.6%    |
| SanDisk NVMe SSD Drive 512GB         | 3         | 1.6%    |
| Intel NVMe SSD Drive 512GB           | 3         | 1.6%    |
| HGST HTS541010A9E680 1TB             | 3         | 1.6%    |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 1.07%   |
| WDC WD10SPZX-24Z10T0 1TB             | 2         | 1.07%   |
| WDC WD10JPVX-75JC3T0 1TB             | 2         | 1.07%   |
| WDC WD10JPVX-60JC3T1 1TB             | 2         | 1.07%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB | 2         | 1.07%   |
| Transcend TS240GMTS820S 240GB SSD    | 2         | 1.07%   |
| Toshiba THNSNK128GVN8 128GB SSD      | 2         | 1.07%   |
| Toshiba MQ01ACF050 500GB             | 2         | 1.07%   |
| Seagate ST9500325AS 500GB            | 2         | 1.07%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 1.07%   |
| Samsung SSD 860 EVO 500GB            | 2         | 1.07%   |
| Ramsta SSD R800 120GB                | 2         | 1.07%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 2         | 1.07%   |
| HGST HTS545050A7E680 500GB           | 2         | 1.07%   |
| HGST HTS541010B7E610 1TB             | 2         | 1.07%   |
| Corsair Force MP510 240GB            | 2         | 1.07%   |
| A-DATA SU650 240GB SSD               | 2         | 1.07%   |
| WDC WDS4 80G2G0B-00EPW0 480GB SSD    | 1         | 0.53%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.53%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1         | 0.53%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.53%   |
| WDC WD5000LPCX-22VHAT0 500GB         | 1         | 0.53%   |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 0.53%   |
| WDC WD3200BPVT-60JJ5T0 320GB         | 1         | 0.53%   |
| WDC WD3200BPVT-00ZEST0 320GB         | 1         | 0.53%   |
| WDC WD1600BEVT-75ZCT1 160GB          | 1         | 0.53%   |
| WDC WD10SPZX-22Z10T1 1TB             | 1         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 36        | 46     | 36.73%  |
| Toshiba | 26        | 33     | 26.53%  |
| WDC     | 22        | 31     | 22.45%  |
| HGST    | 9         | 9      | 9.18%   |
| Hitachi | 5         | 6      | 5.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 12     | 18.18%  |
| Transcend           | 10        | 11     | 18.18%  |
| SanDisk             | 5         | 5      | 9.09%   |
| Micron Technology   | 5         | 5      | 9.09%   |
| A-DATA Technology   | 4         | 4      | 7.27%   |
| Samsung Electronics | 3         | 5      | 5.45%   |
| Toshiba             | 2         | 3      | 3.64%   |
| Ramsta              | 2         | 2      | 3.64%   |
| KingSpec            | 2         | 2      | 3.64%   |
| WDC WDS4            | 1         | 1      | 1.82%   |
| Teutons             | 1         | 1      | 1.82%   |
| SK hynix            | 1         | 1      | 1.82%   |
| PNY                 | 1         | 1      | 1.82%   |
| Kingston            | 1         | 1      | 1.82%   |
| Intel               | 1         | 1      | 1.82%   |
| HS-SSD-E100         | 1         | 1      | 1.82%   |
| Hewlett-Packard     | 1         | 1      | 1.82%   |
| Crucial             | 1         | 2      | 1.82%   |
| Corsair             | 1         | 2      | 1.82%   |
| China               | 1         | 1      | 1.82%   |
| Apacer              | 1         | 1      | 1.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 98        | 125    | 54.44%  |
| SSD     | 52        | 63     | 28.89%  |
| NVMe    | 27        | 37     | 15%     |
| Unknown | 3         | 3      | 1.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 125       | 190    | 81.17%  |
| NVMe | 27        | 36     | 17.53%  |
| SAS  | 2         | 2      | 1.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 73        | 92     | 50%     |
| 0.51-1.0   | 71        | 94     | 48.63%  |
| 1.01-2.0   | 2         | 2      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 41        | 27.7%   |
| 251-500    | 35        | 23.65%  |
| 501-1000   | 32        | 21.62%  |
| 1001-2000  | 13        | 8.78%   |
| 51-100     | 13        | 8.78%   |
| 1-20       | 7         | 4.73%   |
| 21-50      | 5         | 3.38%   |
| Unknown    | 2         | 1.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 54        | 34.84%  |
| 21-50     | 29        | 18.71%  |
| 101-250   | 28        | 18.06%  |
| 51-100    | 26        | 16.77%  |
| 251-500   | 8         | 5.16%   |
| 501-1000  | 6         | 3.87%   |
| 1001-2000 | 2         | 1.29%   |
| Unknown   | 2         | 1.29%   |

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
| Detected | 85        | 130    | 55.56%  |
| Works    | 50        | 77     | 32.68%  |
| Malfunc  | 18        | 21     | 11.76%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 125       | 78.62%  |
| AMD                            | 10        | 6.29%   |
| SanDisk                        | 6         | 3.77%   |
| Phison Electronics             | 3         | 1.89%   |
| Kingston Technology Company    | 3         | 1.89%   |
| Toshiba America Info Systems   | 2         | 1.26%   |
| SK hynix                       | 2         | 1.26%   |
| Shenzhen Longsys Electronics   | 2         | 1.26%   |
| Samsung Electronics            | 2         | 1.26%   |
| Solid State Storage Technology | 1         | 0.63%   |
| Silicon Motion                 | 1         | 0.63%   |
| KIOXIA                         | 1         | 0.63%   |
| Biwin Storage Technology       | 1         | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 49        | 29.34%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 13        | 7.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 6.59%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 10        | 5.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9         | 5.39%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 9         | 5.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 3.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 2.99%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 5         | 2.99%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 2.4%    |
| Intel SSD 660P Series                                                            | 4         | 2.4%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 1.8%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.2%    |
| Phison E12 NVMe Controller                                                       | 2         | 1.2%    |
| Kingston Company Company Non-Volatile memory controller                          | 2         | 1.2%    |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 1.2%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 1.2%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.6%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.6%    |
| Solid State Storage Non-Volatile memory controller                               | 1         | 0.6%    |
| SK hynix Non-Volatile memory controller                                          | 1         | 0.6%    |
| SK hynix BC511                                                                   | 1         | 0.6%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.6%    |
| Shenzhen Longsys Non-Volatile memory controller                                  | 1         | 0.6%    |
| Shenzhen Longsys Electronics Non-Volatile memory controller                      | 1         | 0.6%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.6%    |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.6%    |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.6%    |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 0.6%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.6%    |
| Intel Non-Volatile memory controller                                             | 1         | 0.6%    |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.6%    |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.6%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 0.6%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 0.6%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 116       | 71.17%  |
| NVMe | 27        | 16.56%  |
| RAID | 17        | 10.43%  |
| IDE  | 3         | 1.84%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 129       | 90.85%  |
| AMD    | 13        | 9.15%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 7.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 4.93%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 7         | 4.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 4.23%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 4.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 3.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 3.52%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 3.52%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.82%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 2.82%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 2.82%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 4         | 2.82%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 2.82%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 2.11%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 2.11%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 2.11%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 2.11%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 1.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.41%   |
| Intel Core i3-7130U CPU @ 2.70GHz             | 2         | 1.41%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.41%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.41%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.41%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.41%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 2         | 1.41%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.7%    |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.7%    |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 0.7%    |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 0.7%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 0.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 0.7%    |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 0.7%    |
| Intel Core i5-4200H CPU @ 2.80GHz             | 1         | 0.7%    |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 0.7%    |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 0.7%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.7%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 0.7%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.7%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 64        | 45.07%  |
| Intel Core i3    | 32        | 22.54%  |
| Intel Core i7    | 14        | 9.86%   |
| Other            | 7         | 4.93%   |
| AMD Ryzen 5      | 6         | 4.23%   |
| Intel Pentium    | 5         | 3.52%   |
| Intel Celeron    | 4         | 2.82%   |
| AMD Ryzen 7      | 4         | 2.82%   |
| Intel Atom       | 2         | 1.41%   |
| AMD Ryzen 3      | 2         | 1.41%   |
| Intel Core 2 Duo | 1         | 0.7%    |
| AMD E2           | 1         | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 96        | 67.61%  |
| 4      | 40        | 28.17%  |
| 8      | 4         | 2.82%   |
| 6      | 1         | 0.7%    |
| 1      | 1         | 0.7%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 142       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 130       | 91.55%  |
| 1      | 12        | 8.45%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 141       | 99.3%   |
| Unknown        | 1         | 0.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 19.59%  |
| 0x806e9    | 22        | 14.86%  |
| 0x806ea    | 15        | 10.14%  |
| 0x406e3    | 11        | 7.43%   |
| 0x306d4    | 9         | 6.08%   |
| 0x40651    | 7         | 4.73%   |
| 0x306a9    | 7         | 4.73%   |
| 0x206a7    | 7         | 4.73%   |
| 0x806eb    | 6         | 4.05%   |
| 0x806ec    | 5         | 3.38%   |
| 0x806c1    | 4         | 2.7%    |
| 0x406c4    | 4         | 2.7%    |
| 0x706e5    | 3         | 2.03%   |
| 0x08108102 | 3         | 2.03%   |
| 0x306c3    | 2         | 1.35%   |
| 0x08108109 | 2         | 1.35%   |
| 0x906e9    | 1         | 0.68%   |
| 0x506e3    | 1         | 0.68%   |
| 0x406c3    | 1         | 0.68%   |
| 0x30678    | 1         | 0.68%   |
| 0x30661    | 1         | 0.68%   |
| 0x20655    | 1         | 0.68%   |
| 0x106ca    | 1         | 0.68%   |
| 0x10676    | 1         | 0.68%   |
| 0x0a50000c | 1         | 0.68%   |
| 0x08600104 | 1         | 0.68%   |
| 0x0810100b | 1         | 0.68%   |
| 0x06006705 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 55        | 38.73%  |
| Skylake     | 15        | 10.56%  |
| Broadwell   | 11        | 7.75%   |
| IvyBridge   | 10        | 7.04%   |
| SandyBridge | 9         | 6.34%   |
| Haswell     | 9         | 6.34%   |
| TigerLake   | 7         | 4.93%   |
| Zen+        | 6         | 4.23%   |
| Silvermont  | 6         | 4.23%   |
| IceLake     | 3         | 2.11%   |
| Zen 3       | 2         | 1.41%   |
| Zen 2       | 2         | 1.41%   |
| Bonnell     | 2         | 1.41%   |
| Zen         | 1         | 0.7%    |
| Westmere    | 1         | 0.7%    |
| Penryn      | 1         | 0.7%    |
| Excavator   | 1         | 0.7%    |
| Unknown     | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 129       | 71.27%  |
| Nvidia | 35        | 19.34%  |
| AMD    | 17        | 9.39%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 26        | 14.21%  |
| Intel UHD Graphics 620                                                                   | 15        | 8.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 14        | 7.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 6.56%   |
| Intel HD Graphics 5500                                                                   | 10        | 5.46%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 5.46%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 4.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 3.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 3.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 3.28%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 2.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.73%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 2.19%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 2.19%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 2.19%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 1.64%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.64%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 1.09%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.09%   |
| AMD Renoir                                                                               | 2         | 1.09%   |
| AMD Cezanne                                                                              | 2         | 1.09%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 1.09%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.55%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.55%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.55%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.55%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.55%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.55%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.55%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.55%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.55%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.55%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.55%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.55%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.55%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 0.55%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.55%   |
| Intel HD Graphics 630                                                                    | 1         | 0.55%   |
| Intel HD Graphics 530                                                                    | 1         | 0.55%   |
| Intel HD Graphics                                                                        | 1         | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 94        | 66.2%   |
| Intel + Nvidia | 31        | 21.83%  |
| 1 x AMD        | 7         | 4.93%   |
| Intel + AMD    | 4         | 2.82%   |
| AMD + Nvidia   | 4         | 2.82%   |
| 2 x AMD        | 2         | 1.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 124       | 85.52%  |
| Proprietary | 19        | 13.1%   |
| Unknown     | 2         | 1.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 115       | 78.77%  |
| 1.01-2.0   | 20        | 13.7%   |
| 3.01-4.0   | 6         | 4.11%   |
| 0.01-0.5   | 3         | 2.05%   |
| 5.01-6.0   | 1         | 0.68%   |
| 0.51-1.0   | 1         | 0.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 37        | 22.84%  |
| AU Optronics            | 37        | 22.84%  |
| Chimei Innolux          | 33        | 20.37%  |
| LG Display              | 25        | 15.43%  |
| Samsung Electronics     | 9         | 5.56%   |
| Dell                    | 5         | 3.09%   |
| Hewlett-Packard         | 3         | 1.85%   |
| Goldstar                | 3         | 1.85%   |
| Chi Mei Optoelectronics | 2         | 1.23%   |
| ViewSonic               | 1         | 0.62%   |
| Sharp                   | 1         | 0.62%   |
| PANDA                   | 1         | 0.62%   |
| MSI                     | 1         | 0.62%   |
| ASUSTek Computer        | 1         | 0.62%   |
| Apple                   | 1         | 0.62%   |
| AOC                     | 1         | 0.62%   |
| Ancor Communications    | 1         | 0.62%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 9         | 5.56%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 4         | 2.47%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 2.47%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 3         | 1.85%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                 | 3         | 1.85%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 3         | 1.85%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 2         | 1.23%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 2         | 1.23%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 2         | 1.23%   |
| LG Display LCD Monitor LGD0466 1366x768 309x174mm 14.0-inch           | 2         | 1.23%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 310x170mm 13.9-inch       | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 1.23%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 1.23%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                  | 2         | 1.23%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 2         | 1.23%   |
| ViewSonic LCD Monitor VSC5E32 1920x1080 480x270mm 21.7-inch           | 1         | 0.62%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.62%   |
| Samsung Electronics SyncMaster SAM043E 1600x1200 520x320mm 24.0-inch  | 1         | 0.62%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch     | 1         | 0.62%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch      | 1         | 0.62%   |
| Samsung Electronics S19C300 SAM0A12 1366x768 410x230mm 18.5-inch      | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 410x230mm 18.5-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC4751 1366x768 344x194mm 15.5-inch  | 1         | 0.62%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.62%   |
| MSI MP241 MSI3BA9 1920x1080 527x296mm 23.8-inch                       | 1         | 0.62%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.62%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch           | 1         | 0.62%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.62%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 0.62%   |
| LG Display LCD Monitor LGD0455 1366x768 310x174mm 14.0-inch           | 1         | 0.62%   |
| LG Display LCD Monitor LGD03DF 1366x768 344x194mm 15.5-inch           | 1         | 0.62%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 74        | 48.68%  |
| 1920x1080 (FHD)   | 63        | 41.45%  |
| 1600x900 (HD+)    | 4         | 2.63%   |
| 3840x2160 (4K)    | 2         | 1.32%   |
| 1280x800 (WXGA)   | 2         | 1.32%   |
| 1024x600          | 2         | 1.32%   |
| 2560x1600         | 1         | 0.66%   |
| 2560x1440 (QHD)   | 1         | 0.66%   |
| 2240x1400         | 1         | 0.66%   |
| 1920x1200 (WUXGA) | 1         | 0.66%   |
| 1280x1024 (SXGA)  | 1         | 0.66%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 68        | 42.24%  |
| 13     | 37        | 22.98%  |
| 14     | 27        | 16.77%  |
| 21     | 7         | 4.35%   |
| 18     | 7         | 4.35%   |
| 12     | 4         | 2.48%   |
| 23     | 2         | 1.24%   |
| 11     | 2         | 1.24%   |
| 10     | 2         | 1.24%   |
| 27     | 1         | 0.62%   |
| 26     | 1         | 0.62%   |
| 24     | 1         | 0.62%   |
| 19     | 1         | 0.62%   |
| 17     | 1         | 0.62%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 124       | 77.5%   |
| 401-500     | 16        | 10%     |
| 201-300     | 16        | 10%     |
| 501-600     | 4         | 2.5%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 137       | 95.8%   |
| 16/10 | 5         | 3.5%    |
| 5/4   | 1         | 0.7%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 68        | 42.5%   |
| 81-90          | 57        | 35.63%  |
| 141-150        | 8         | 5%      |
| 71-80          | 7         | 4.38%   |
| 201-250        | 6         | 3.75%   |
| 61-70          | 4         | 2.5%    |
| 151-200        | 3         | 1.88%   |
| 51-60          | 2         | 1.25%   |
| 41-50          | 2         | 1.25%   |
| 251-300        | 2         | 1.25%   |
| 301-350        | 1         | 0.63%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 72        | 46.15%  |
| 121-160       | 64        | 41.03%  |
| 51-100        | 13        | 8.33%   |
| 161-240       | 6         | 3.85%   |
| More than 240 | 1         | 0.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 124       | 86.11%  |
| 2     | 18        | 12.5%   |
| 3     | 1         | 0.69%   |
| 0     | 1         | 0.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 94        | 42.73%  |
| Intel                 | 69        | 31.36%  |
| Qualcomm Atheros      | 43        | 19.55%  |
| Broadcom              | 5         | 2.27%   |
| Ralink Technology     | 3         | 1.36%   |
| MediaTek              | 2         | 0.91%   |
| Samsung Electronics   | 1         | 0.45%   |
| Ralink                | 1         | 0.45%   |
| Dell                  | 1         | 0.45%   |
| Arduino SA            | 1         | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 61        | 24.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 7.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 17        | 6.72%   |
| Intel Wireless 8265 / 8275                                        | 14        | 5.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 4.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 3.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7         | 2.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 2.77%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 2.77%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 2.37%   |
| Intel Wireless 3165                                               | 6         | 2.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.37%   |
| Intel Wireless 8260                                               | 5         | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.58%   |
| Intel Wireless 7265                                               | 4         | 1.58%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.19%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 1.19%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.19%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.79%   |
| Intel Wireless 7260                                               | 2         | 0.79%   |
| Intel Wireless 3160                                               | 2         | 0.79%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.79%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.4%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 1         | 0.4%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 1         | 0.4%    |
| Realtek RTL8187 Wireless Adapter                                  | 1         | 0.4%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.4%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 67        | 46.53%  |
| Qualcomm Atheros      | 42        | 29.17%  |
| Realtek Semiconductor | 25        | 17.36%  |
| Ralink Technology     | 3         | 2.08%   |
| Broadcom              | 3         | 2.08%   |
| MediaTek              | 2         | 1.39%   |
| Ralink                | 1         | 0.69%   |
| Dell                  | 1         | 0.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 17        | 11.81%  |
| Intel Wireless 8265 / 8275                                     | 14        | 9.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12        | 8.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 6.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 4.86%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 4.86%   |
| Intel Wi-Fi 6 AX201                                            | 7         | 4.86%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 4.17%   |
| Intel Wireless 3165                                            | 6         | 4.17%   |
| Intel Wireless 8260                                            | 5         | 3.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.78%   |
| Intel Wireless 7265                                            | 4         | 2.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.08%   |
| Ralink MT7601U Wireless Adapter                                | 3         | 2.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 2.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.39%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.39%   |
| Intel Wireless 7260                                            | 2         | 1.39%   |
| Intel Wireless 3160                                            | 2         | 1.39%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 1.39%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.39%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.69%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.69%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 0.69%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.69%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.69%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1         | 0.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.69%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 0.69%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 0.69%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 0.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 0.69%   |
| Dell DW5811e Snapdragonâ¢ X7 LTE                           | 1         | 0.69%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 83        | 76.85%  |
| Intel                 | 17        | 15.74%  |
| Qualcomm Atheros      | 4         | 3.7%    |
| Broadcom              | 3         | 2.78%   |
| Samsung Electronics   | 1         | 0.93%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 61        | 56.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 18.52%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 5.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 3.7%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.85%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.93%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.93%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.93%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.93%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.93%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.93%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.93%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.93%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.93%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.93%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 139       | 56.05%  |
| Ethernet | 108       | 43.55%  |
| Modem    | 1         | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 126       | 86.9%   |
| Ethernet | 19        | 13.1%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 100       | 70.42%  |
| 1     | 42        | 29.58%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 142       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 45.45%  |
| IMC Networks                    | 19        | 15.7%   |
| Realtek Semiconductor           | 13        | 10.74%  |
| Qualcomm Atheros Communications | 11        | 9.09%   |
| Lite-On Technology              | 10        | 8.26%   |
| Broadcom                        | 6         | 4.96%   |
| Foxconn / Hon Hai               | 4         | 3.31%   |
| Toshiba                         | 1         | 0.83%   |
| Ralink                          | 1         | 0.83%   |
| Hewlett-Packard                 | 1         | 0.83%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 33        | 27.27%  |
| IMC Networks Bluetooth Device                     | 12        | 9.92%   |
| Intel Wireless-AC 3168 Bluetooth                  | 10        | 8.26%   |
| Realtek Bluetooth Radio                           | 7         | 5.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 6         | 4.96%   |
| IMC Networks Bluetooth Radio                      | 6         | 4.96%   |
| Qualcomm Atheros  Bluetooth Device                | 5         | 4.13%   |
| Intel AX201 Bluetooth                             | 5         | 4.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 4         | 3.31%   |
| Realtek  Bluetooth 4.2 Adapter                    | 3         | 2.48%   |
| Lite-On Bluetooth Device                          | 3         | 2.48%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter           | 2         | 1.65%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 2         | 1.65%   |
| Intel AX200 Bluetooth                             | 2         | 1.65%   |
| Foxconn / Hon Hai Bluetooth Device                | 2         | 1.65%   |
| Broadcom HP Portable SoftSailing                  | 2         | 1.65%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 2         | 1.65%   |
| Toshiba Bluetooth Radio                           | 1         | 0.83%   |
| Realtek RTL8821A Bluetooth                        | 1         | 0.83%   |
| Ralink RT3290 Bluetooth                           | 1         | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 0.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 0.83%   |
| Qualcomm Atheros AR3012 Bluetooth                 | 1         | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 1         | 0.83%   |
| Lite-On Atheros AR3012 Bluetooth                  | 1         | 0.83%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 0.83%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 1         | 0.83%   |
| HP Broadcom 2070 Bluetooth Combo                  | 1         | 0.83%   |
| Foxconn / Hon Hai Wireless_Device                 | 1         | 0.83%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller   | 1         | 0.83%   |
| Broadcom BCM43142A0 Bluetooth 4.0                 | 1         | 0.83%   |
| Broadcom BCM20702A0 Bluetooth 4.0                 | 1         | 0.83%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 128       | 87.67%  |
| AMD                    | 13        | 8.9%    |
| Nvidia                 | 4         | 2.74%   |
| Generalplus Technology | 1         | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 55        | 30.9%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 12        | 6.74%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 6.74%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 6.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 6.18%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 6.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 3.93%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 3.93%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 3.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 3.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 2.81%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 2.25%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.12%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 1.12%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Intel USB PnP Sound Device                                                                        | 1         | 0.56%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.56%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1         | 0.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 0.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.56%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.56%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 30.69%  |
| SK hynix            | 26        | 25.74%  |
| Micron Technology   | 12        | 11.88%  |
| A-DATA Technology   | 6         | 5.94%   |
| Kingston            | 5         | 4.95%   |
| G.Skill             | 4         | 3.96%   |
| Unknown             | 3         | 2.97%   |
| Transcend           | 3         | 2.97%   |
| Team                | 2         | 1.98%   |
| Ramaxel Technology  | 2         | 1.98%   |
| Nanya Technology    | 2         | 1.98%   |
| Unknown (C509)      | 1         | 0.99%   |
| Unknown (768A)      | 1         | 0.99%   |
| Elpida              | 1         | 0.99%   |
| Crucial             | 1         | 0.99%   |
| Unknown             | 1         | 0.99%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 5         | 4.95%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 4         | 3.96%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 2.97%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 3         | 2.97%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 3         | 2.97%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 2.97%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.98%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.98%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 2         | 1.98%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s               | 2         | 1.98%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.98%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s             | 2         | 1.98%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 2         | 1.98%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                      | 1         | 0.99%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                         | 1         | 0.99%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 0.99%   |
| Unknown (C509) RAM Module 4GB SODIMM DDR4 2400MT/s                  | 1         | 0.99%   |
| Unknown (768A) RAM Module 8192MB SODIMM DDR4 3200MT/s               | 1         | 0.99%   |
| Transcend RAM JM3200HSB-8G 8GB SODIMM DDR4 3200MT/s                 | 1         | 0.99%   |
| Transcend RAM JM2666HSG-8G 8GB SODIMM DDR4 2667MT/s                 | 1         | 0.99%   |
| Transcend RAM JM2400HSB-8G 8GB SODIMM DDR4 2400MT/s                 | 1         | 0.99%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s               | 1         | 0.99%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s               | 1         | 0.99%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                     | 1         | 0.99%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2133MT/s                     | 1         | 0.99%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.99%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.99%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.99%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.99%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.99%   |
| SK hynix RAM H9CCNNNBJTMLAR-NUD 4096MB Row Of Chips LPDDR3 1867MT/s | 1         | 0.99%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 1         | 0.99%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                      | 1         | 0.99%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2400MT/s                      | 1         | 0.99%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                      | 1         | 0.99%   |
| Samsung RAM M471B5673DZ1-CF8 2GB SODIMM DDR 1067MT/s                | 1         | 0.99%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.99%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 1         | 0.99%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 50        | 66.67%  |
| DDR3   | 20        | 26.67%  |
| LPDDR4 | 3         | 4%      |
| LPDDR3 | 2         | 2.67%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 70        | 95.89%  |
| Row Of Chips | 3         | 4.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 38        | 45.78%  |
| 8192  | 35        | 42.17%  |
| 16384 | 6         | 7.23%   |
| 2048  | 3         | 3.61%   |
| 32768 | 1         | 1.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 27        | 32.93%  |
| 1600  | 16        | 19.51%  |
| 2400  | 13        | 15.85%  |
| 2133  | 10        | 12.2%   |
| 3200  | 7         | 8.54%   |
| 3266  | 2         | 2.44%   |
| 1334  | 2         | 2.44%   |
| 1067  | 2         | 2.44%   |
| 8400  | 1         | 1.22%   |
| 1867  | 1         | 1.22%   |
| 1333  | 1         | 1.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L132 Series | 1         | 100%    |

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
| Chicony Electronics                    | 30        | 22.56%  |
| IMC Networks                           | 26        | 19.55%  |
| Cheng Uei Precision Industry (Foxlink) | 15        | 11.28%  |
| Realtek Semiconductor                  | 12        | 9.02%   |
| Sunplus Innovation Technology          | 9         | 6.77%   |
| Quanta                                 | 9         | 6.77%   |
| Acer                                   | 7         | 5.26%   |
| Lite-On Technology                     | 6         | 4.51%   |
| Microdia                               | 5         | 3.76%   |
| Suyin                                  | 4         | 3.01%   |
| Luxvisions Innotech Limited            | 4         | 3.01%   |
| Silicon Motion                         | 2         | 1.5%    |
| Primax Electronics                     | 2         | 1.5%    |
| Syntek                                 | 1         | 0.75%   |
| Apple                                  | 1         | 0.75%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony USB2.0 VGA UVC WebCam                           | 9         | 6.77%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 8         | 6.02%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 7         | 5.26%   |
| IMC Networks VGA UVC WebCam                             | 5         | 3.76%   |
| Realtek Integrated_Webcam_HD                            | 3         | 2.26%   |
| Quanta HD Webcam                                        | 3         | 2.26%   |
| Luxvisions Innotech Limited HP HD Camera                | 3         | 2.26%   |
| Lite-On HP HD Camera                                    | 3         | 2.26%   |
| IMC Networks USB2.0 HD IR UVC WebCam                    | 3         | 2.26%   |
| IMC Networks Integrated Camera                          | 3         | 2.26%   |
| Chicony HD WebCam                                       | 3         | 2.26%   |
| Chicony EasyCamera                                      | 3         | 2.26%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 3         | 2.26%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 3         | 2.26%   |
| Acer HD Webcam                                          | 3         | 2.26%   |
| Suyin Integrated_Webcam_HD                              | 2         | 1.5%    |
| Suyin HP Truevision HD                                  | 2         | 1.5%    |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 1.5%    |
| Realtek USB2.0 VGA UVC WebCam                           | 2         | 1.5%    |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.5%    |
| Quanta HD User Facing                                   | 2         | 1.5%    |
| Primax HP HD Webcam [Fixed]                             | 2         | 1.5%    |
| Microdia Integrated_Webcam_HD                           | 2         | 1.5%    |
| Lite-On Integrated Camera                               | 2         | 1.5%    |
| Chicony USB2.0 Camera                                   | 2         | 1.5%    |
| Chicony Integrated Camera                               | 2         | 1.5%    |
| Chicony HP HD Webcam                                    | 2         | 1.5%    |
| Chicony HP HD Camera                                    | 2         | 1.5%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.5%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.5%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 2         | 1.5%    |
| Syntek Integrated Camera                                | 1         | 0.75%   |
| Sunplus XiaoMi USB 2.0 Webcam                           | 1         | 0.75%   |
| Sunplus Integrated_Webcam_HD                            | 1         | 0.75%   |
| Sunplus Integrated Webcam                               | 1         | 0.75%   |
| Sunplus HP HD Webcam [Fixed]                            | 1         | 0.75%   |
| Sunplus HD WebCam                                       | 1         | 0.75%   |
| Sunplus Dell HD Webcam                                  | 1         | 0.75%   |
| Sunplus Asus Webcam                                     | 1         | 0.75%   |
| Silicon Motion WebCam SC-10HDD12636N                    | 1         | 0.75%   |

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
| 0     | 96        | 65.31%  |
| 1     | 45        | 30.61%  |
| 2     | 5         | 3.4%    |
| 3     | 1         | 0.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 30        | 54.55%  |
| Graphics card         | 11        | 20%     |
| Chipcard              | 5         | 9.09%   |
| Camera                | 3         | 5.45%   |
| Net/wireless          | 2         | 3.64%   |
| Multimedia controller | 2         | 3.64%   |
| Card reader           | 1         | 1.82%   |
| Bluetooth             | 1         | 1.82%   |

