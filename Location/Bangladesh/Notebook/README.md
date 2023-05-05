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

Total: 260

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 450 G7              | [a1c1008bf1](https://linux-hardware.org/?probe=a1c1008bf1) | Apr 29, 2023 |
| Dell          | Inspiron 15 3520            | [f767bfff00](https://linux-hardware.org/?probe=f767bfff00) | Apr 29, 2023 |
| Toshiba       | Satellite C660              | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Lenovo        | S20-30 20421                | [b9846b05e7](https://linux-hardware.org/?probe=b9846b05e7) | Apr 22, 2023 |
| HUAWEI        | RLEF-XX                     | [802d7b7c3f](https://linux-hardware.org/?probe=802d7b7c3f) | Apr 07, 2023 |
| HUAWEI        | RLEF-XX                     | [874157891b](https://linux-hardware.org/?probe=874157891b) | Apr 06, 2023 |
| Lenovo        | ThinkPad X220 4290CTO       | [5dd9277838](https://linux-hardware.org/?probe=5dd9277838) | Apr 04, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | [6af08c4bfe](https://linux-hardware.org/?probe=6af08c4bfe) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | [6f0d3fd82b](https://linux-hardware.org/?probe=6f0d3fd82b) | Mar 30, 2023 |
| HUAWEI        | RLEF-XX                     | [b860e76ead](https://linux-hardware.org/?probe=b860e76ead) | Mar 26, 2023 |
| MSI           | Modern 14 B10MW             | [2940ea3b40](https://linux-hardware.org/?probe=2940ea3b40) | Mar 21, 2023 |
| Acer          | Aspire F5-573G              | [ec2390af74](https://linux-hardware.org/?probe=ec2390af74) | Mar 21, 2023 |
| Acer          | Aspire F5-573G              | [e3e0efa236](https://linux-hardware.org/?probe=e3e0efa236) | Mar 20, 2023 |
| Lenovo        | LEGION5PRO-16ACH6H 82JQ     | [4f3cbedf85](https://linux-hardware.org/?probe=4f3cbedf85) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [a0cf486df2](https://linux-hardware.org/?probe=a0cf486df2) | Mar 19, 2023 |
| MSI           | Modern 15 A5M               | [7d708fea96](https://linux-hardware.org/?probe=7d708fea96) | Mar 06, 2023 |
| Dell          | Inspiron N4010              | [612418b6e7](https://linux-hardware.org/?probe=612418b6e7) | Feb 25, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [6cda8724a4](https://linux-hardware.org/?probe=6cda8724a4) | Feb 14, 2023 |
| Toshiba       | Satellite Pro L510          | [c8dc3a76e5](https://linux-hardware.org/?probe=c8dc3a76e5) | Feb 06, 2023 |
| Acer          | Aspire 4736Z                | [a2ab102eeb](https://linux-hardware.org/?probe=a2ab102eeb) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [ddb7f53b34](https://linux-hardware.org/?probe=ddb7f53b34) | Feb 03, 2023 |
| Lenovo        | ThinkPad X230 2324A82       | [2793159580](https://linux-hardware.org/?probe=2793159580) | Feb 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [af63cfc79a](https://linux-hardware.org/?probe=af63cfc79a) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| Acer          | Nitro AN515-57              | [cf6bdca9c4](https://linux-hardware.org/?probe=cf6bdca9c4) | Jan 23, 2023 |
| Dell          | Vostro 1014                 | [f7ff3312f2](https://linux-hardware.org/?probe=f7ff3312f2) | Jan 21, 2023 |
| Dell          | Vostro 1014                 | [724939f0cf](https://linux-hardware.org/?probe=724939f0cf) | Jan 21, 2023 |
| MSI           | Modern 14 B10MW             | [c3f150a8f4](https://linux-hardware.org/?probe=c3f150a8f4) | Jan 18, 2023 |
| MSI           | Modern 14 B10MW             | [d2ac110bfb](https://linux-hardware.org/?probe=d2ac110bfb) | Jan 18, 2023 |
| MSI           | Modern 14 B10MW             | [ad5c9e7f6a](https://linux-hardware.org/?probe=ad5c9e7f6a) | Jan 18, 2023 |
| HP            | Notebook                    | [fbdf174a63](https://linux-hardware.org/?probe=fbdf174a63) | Jan 16, 2023 |
| Dell          | Latitude 5300               | [8149377926](https://linux-hardware.org/?probe=8149377926) | Jan 15, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [e5773ce5f8](https://linux-hardware.org/?probe=e5773ce5f8) | Jan 11, 2023 |
| Acer          | Nitro AN515-57              | [53043b7d75](https://linux-hardware.org/?probe=53043b7d75) | Jan 10, 2023 |
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
| Ubuntu 20.04                 | 35        | 17.86%  |
| Arch                         | 9         | 4.59%   |
| ArcoLinux Rolling            | 8         | 4.08%   |
| Ubuntu 22.04                 | 7         | 3.57%   |
| Manjaro                      | 6         | 3.06%   |
| Arch Rolling                 | 6         | 3.06%   |
| Pop!_OS 22.04                | 5         | 2.55%   |
| KDE neon 20.04               | 5         | 2.55%   |
| Ubuntu 19.10                 | 4         | 2.04%   |
| Ubuntu 18.04                 | 4         | 2.04%   |
| Fedora 33                    | 4         | 2.04%   |
| EndeavourOS Rolling          | 4         | 2.04%   |
| Zorin 16                     | 3         | 1.53%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 1.53%   |
| OpenMandriva 4.2             | 3         | 1.53%   |
| Manjaro 20.0.1               | 3         | 1.53%   |
| Fedora 37                    | 3         | 1.53%   |
| Debian 11                    | 3         | 1.53%   |
| Zorin 15                     | 2         | 1.02%   |
| Ubuntu 22.10                 | 2         | 1.02%   |
| Ubuntu 19.04                 | 2         | 1.02%   |
| Ubuntu 18.10                 | 2         | 1.02%   |
| Pop!_OS 21.10                | 2         | 1.02%   |
| OpenMandriva 4.90            | 2         | 1.02%   |
| MX 21                        | 2         | 1.02%   |
| Manjaro 21.2.6               | 2         | 1.02%   |
| Manjaro 18.0.4               | 2         | 1.02%   |
| Linux Mint 20.1              | 2         | 1.02%   |
| Linux Mint 20                | 2         | 1.02%   |
| Kubuntu 20.04                | 2         | 1.02%   |
| KDE neon 22.04               | 2         | 1.02%   |
| Kali 2022.4                  | 2         | 1.02%   |
| Kali 2022.3                  | 2         | 1.02%   |
| Fedora 34                    | 2         | 1.02%   |
| Ubuntu Unity 16.04           | 1         | 0.51%   |
| Ubuntu 21.04                 | 1         | 0.51%   |
| Ubuntu 20.10                 | 1         | 0.51%   |
| Pop!_OS 21.04                | 1         | 0.51%   |
| Pop!_OS 20.10                | 1         | 0.51%   |
| Parrot 5.1                   | 1         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 56        | 30.94%  |
| Manjaro      | 18        | 9.94%   |
| Arch         | 14        | 7.73%   |
| Fedora       | 10        | 5.52%   |
| Pop!_OS      | 9         | 4.97%   |
| Linux Mint   | 8         | 4.42%   |
| ArcoLinux    | 8         | 4.42%   |
| KDE neon     | 7         | 3.87%   |
| OpenMandriva | 6         | 3.31%   |
| Zorin        | 5         | 2.76%   |
| Kubuntu      | 5         | 2.76%   |
| Endless      | 5         | 2.76%   |
| EndeavourOS  | 5         | 2.76%   |
| Debian       | 5         | 2.76%   |
| Parrot       | 3         | 1.66%   |
| openSUSE     | 3         | 1.66%   |
| Kali         | 3         | 1.66%   |
| MX           | 2         | 1.1%    |
| Ubuntu Unity | 1         | 0.55%   |
| Lubuntu      | 1         | 0.55%   |
| LMDE         | 1         | 0.55%   |
| Devuan       | 1         | 0.55%   |
| Deepin       | 1         | 0.55%   |
| Clear Linux  | 1         | 0.55%   |
| CentOS       | 1         | 0.55%   |
| BlackPanther | 1         | 0.55%   |
| Artix        | 1         | 0.55%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 7         | 3.29%   |
| 5.4.0-52-generic         | 3         | 1.41%   |
| 5.4.0-40-generic         | 3         | 1.41%   |
| 5.4.0-29-generic         | 3         | 1.41%   |
| 5.10.14-desktop-1omv4002 | 3         | 1.41%   |
| 6.0.9-zen1-1-zen         | 2         | 0.94%   |
| 6.0.0-kali6-amd64        | 2         | 0.94%   |
| 5.9.16-1-MANJARO         | 2         | 0.94%   |
| 5.8.0-50-generic         | 2         | 0.94%   |
| 5.8.0-41-generic         | 2         | 0.94%   |
| 5.8.0-14-generic         | 2         | 0.94%   |
| 5.7.19-2-MANJARO         | 2         | 0.94%   |
| 5.6.11-1-MANJARO         | 2         | 0.94%   |
| 5.4.8-arch1-1            | 2         | 0.94%   |
| 5.4.0-53-generic         | 2         | 0.94%   |
| 5.4.0-19-generic         | 2         | 0.94%   |
| 5.3.0-24-generic         | 2         | 0.94%   |
| 5.3.0-23-generic         | 2         | 0.94%   |
| 5.19.0-kali2-amd64       | 2         | 0.94%   |
| 5.19.0-35-generic        | 2         | 0.94%   |
| 5.19.0-29-generic        | 2         | 0.94%   |
| 5.18.12-desktop-3omv4090 | 2         | 0.94%   |
| 5.15.0-53-generic        | 2         | 0.94%   |
| 5.15.0-48-generic        | 2         | 0.94%   |
| 5.15.0-46-generic        | 2         | 0.94%   |
| 5.13.0-28-generic        | 2         | 0.94%   |
| 5.11.0-40-generic        | 2         | 0.94%   |
| 5.11.0-27-generic        | 2         | 0.94%   |
| 5.10.52-1-lts            | 2         | 0.94%   |
| 5.10.0-13-amd64          | 2         | 0.94%   |
| 6.2.8-arch1-1            | 1         | 0.47%   |
| 6.2.7-zen1-1-zen         | 1         | 0.47%   |
| 6.2.7-200.fc37.x86_64    | 1         | 0.47%   |
| 6.2.12-1-MANJARO         | 1         | 0.47%   |
| 6.1.9-arch1-1            | 1         | 0.47%   |
| 6.1.8-1-default          | 1         | 0.47%   |
| 6.1.7-200.fc37.x86_64    | 1         | 0.47%   |
| 6.1.18-200.fc37.x86_64   | 1         | 0.47%   |
| 6.1.12-arch1-1           | 1         | 0.47%   |
| 6.0.6-76060006-generic   | 1         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 28        | 13.79%  |
| 5.8.0   | 13        | 6.4%    |
| 5.15.0  | 12        | 5.91%   |
| 5.11.0  | 12        | 5.91%   |
| 5.19.0  | 8         | 3.94%   |
| 5.13.0  | 8         | 3.94%   |
| 5.10.0  | 7         | 3.45%   |
| 5.3.0   | 6         | 2.96%   |
| 6.0.0   | 5         | 2.46%   |
| 5.0.0   | 4         | 1.97%   |
| 4.18.0  | 4         | 1.97%   |
| 4.15.0  | 4         | 1.97%   |
| 6.0.12  | 3         | 1.48%   |
| 5.9.16  | 3         | 1.48%   |
| 5.18.12 | 3         | 1.48%   |
| 5.10.14 | 3         | 1.48%   |
| 4.19.0  | 3         | 1.48%   |
| 6.2.7   | 2         | 0.99%   |
| 6.0.9   | 2         | 0.99%   |
| 5.7.19  | 2         | 0.99%   |
| 5.6.11  | 2         | 0.99%   |
| 5.4.8   | 2         | 0.99%   |
| 5.16.15 | 2         | 0.99%   |
| 5.15.5  | 2         | 0.99%   |
| 5.10.52 | 2         | 0.99%   |
| 6.2.8   | 1         | 0.49%   |
| 6.2.12  | 1         | 0.49%   |
| 6.1.9   | 1         | 0.49%   |
| 6.1.8   | 1         | 0.49%   |
| 6.1.7   | 1         | 0.49%   |
| 6.1.18  | 1         | 0.49%   |
| 6.1.12  | 1         | 0.49%   |
| 6.0.6   | 1         | 0.49%   |
| 6.0.2   | 1         | 0.49%   |
| 5.9.11  | 1         | 0.49%   |
| 5.8.4   | 1         | 0.49%   |
| 5.8.16  | 1         | 0.49%   |
| 5.8.12  | 1         | 0.49%   |
| 5.7.0   | 1         | 0.49%   |
| 5.4.81  | 1         | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 17.53%  |
| 5.15    | 21        | 10.82%  |
| 5.8     | 16        | 8.25%   |
| 5.10    | 16        | 8.25%   |
| 5.11    | 15        | 7.73%   |
| 6.0     | 11        | 5.67%   |
| 5.19    | 10        | 5.15%   |
| 5.13    | 9         | 4.64%   |
| 5.3     | 6         | 3.09%   |
| 5.18    | 6         | 3.09%   |
| 5.16    | 6         | 3.09%   |
| 6.1     | 5         | 2.58%   |
| 4.18    | 5         | 2.58%   |
| 6.2     | 4         | 2.06%   |
| 5.9     | 4         | 2.06%   |
| 5.0     | 4         | 2.06%   |
| 4.19    | 4         | 2.06%   |
| 4.15    | 4         | 2.06%   |
| 5.7     | 3         | 1.55%   |
| 5.17    | 3         | 1.55%   |
| 5.6     | 2         | 1.03%   |
| 5.14    | 2         | 1.03%   |
| 5.12    | 2         | 1.03%   |
| 5.1     | 2         | 1.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 175       | 98.87%  |
| i686   | 2         | 1.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| GNOME          | 88        | 47.83%  |
| KDE5           | 41        | 22.28%  |
| Unknown        | 18        | 9.78%   |
| XFCE           | 13        | 7.07%   |
| X-Cinnamon     | 7         | 3.8%    |
| MATE           | 3         | 1.63%   |
| awesome        | 3         | 1.63%   |
| KDE            | 2         | 1.09%   |
| i3-with-shmlog | 2         | 1.09%   |
| Unity          | 1         | 0.54%   |
| LXQt           | 1         | 0.54%   |
| LXDE           | 1         | 0.54%   |
| i3             | 1         | 0.54%   |
| DWM            | 1         | 0.54%   |
| Deepin         | 1         | 0.54%   |
| bspwm          | 1         | 0.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 147       | 79.46%  |
| Wayland | 26        | 14.05%  |
| Unknown | 10        | 5.41%   |
| Tty     | 2         | 1.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 86        | 46.74%  |
| SDDM    | 31        | 16.85%  |
| GDM     | 28        | 15.22%  |
| LightDM | 17        | 9.24%   |
| GDM3    | 16        | 8.7%    |
| TDM     | 6         | 3.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 147       | 82.12%  |
| Unknown | 16        | 8.94%   |
| en_GB   | 7         | 3.91%   |
| C       | 4         | 2.23%   |
| en_IE   | 1         | 0.56%   |
| en_EN   | 1         | 0.56%   |
| en_CA   | 1         | 0.56%   |
| en_AG   | 1         | 0.56%   |
| Default | 1         | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 93        | 51.38%  |
| BIOS | 88        | 48.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 143       | 79.89%  |
| Btrfs   | 17        | 9.5%    |
| Overlay | 15        | 8.38%   |
| Unknown | 3         | 1.68%   |
| Xfs     | 1         | 0.56%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 94        | 51.65%  |
| GPT     | 68        | 37.36%  |
| MBR     | 20        | 10.99%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 156       | 87.15%  |
| Yes       | 23        | 12.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 103       | 57.54%  |
| Yes       | 76        | 42.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 46        | 25.99%  |
| Hewlett-Packard     | 43        | 24.29%  |
| Lenovo              | 25        | 14.12%  |
| Dell                | 24        | 13.56%  |
| Acer                | 19        | 10.73%  |
| MSI                 | 6         | 3.39%   |
| Notebook            | 4         | 2.26%   |
| Toshiba             | 3         | 1.69%   |
| Timi                | 1         | 0.56%   |
| Samsung Electronics | 1         | 0.56%   |
| HUAWEI              | 1         | 0.56%   |
| Fujitsu             | 1         | 0.56%   |
| Daffodil Computers  | 1         | 0.56%   |
| Apple               | 1         | 0.56%   |
| Unknown             | 1         | 0.56%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP ProBook 450 G4                                     | 5         | 2.82%   |
| HP Notebook                                           | 3         | 1.69%   |
| ASUS VivoBook_ASUSLaptop X530FN_S530FN                | 3         | 1.69%   |
| MSI Modern 15 A5M                                     | 2         | 1.13%   |
| MSI Modern 14 B10MW                                   | 2         | 1.13%   |
| HP ProBook 450 G2                                     | 2         | 1.13%   |
| HP ProBook 440 G8 Notebook PC                         | 2         | 1.13%   |
| HP EliteBook 840 G3                                   | 2         | 1.13%   |
| HP 15                                                 | 2         | 1.13%   |
| HP 14                                                 | 2         | 1.13%   |
| Dell Inspiron 3442                                    | 2         | 1.13%   |
| ASUS X510UQ                                           | 2         | 1.13%   |
| ASUS VivoBook_ASUSLaptop X531FL_S531FL                | 2         | 1.13%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA                | 2         | 1.13%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA                | 2         | 1.13%   |
| ASUS VivoBook 14_ASUS Laptop X407UA                   | 2         | 1.13%   |
| ASUS P453UA                                           | 2         | 1.13%   |
| Acer Nitro AN515-43                                   | 2         | 1.13%   |
| Toshiba Satellite Pro L510                            | 1         | 0.56%   |
| Toshiba Satellite L645                                | 1         | 0.56%   |
| Toshiba Satellite C660                                | 1         | 0.56%   |
| Timi Mi NoteBook Pro                                  | 1         | 0.56%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.56%   |
| Notebook W9x0LU                                       | 1         | 0.56%   |
| Notebook N750BU                                       | 1         | 0.56%   |
| Notebook N2x0LU                                       | 1         | 0.56%   |
| Notebook DCL C483                                     | 1         | 0.56%   |
| MSI Summit B14 A11MOT                                 | 1         | 0.56%   |
| MSI GS63 7RD                                          | 1         | 0.56%   |
| Lenovo V330-14IKB 81B0                                | 1         | 0.56%   |
| Lenovo ThinkPad X230 2324F51                          | 1         | 0.56%   |
| Lenovo ThinkPad X230 2324A82                          | 1         | 0.56%   |
| Lenovo ThinkPad X220 4290CTO                          | 1         | 0.56%   |
| Lenovo ThinkPad T470s 20HGS23V06                      | 1         | 0.56%   |
| Lenovo ThinkPad T450 20BUS2021M                       | 1         | 0.56%   |
| Lenovo ThinkPad T430s 2356GPU                         | 1         | 0.56%   |
| Lenovo ThinkPad L380 20M6S22500                       | 1         | 0.56%   |
| Lenovo ThinkPad E490 20N9S1XE00                       | 1         | 0.56%   |
| Lenovo ThinkPad E470 20H1A029SG                       | 1         | 0.56%   |
| Lenovo S20-30 20421                                   | 1         | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| ASUS VivoBook             | 22        | 12.43%  |
| HP ProBook                | 18        | 10.17%  |
| Acer Aspire               | 15        | 8.47%   |
| Dell Inspiron             | 12        | 6.78%   |
| Lenovo IdeaPad            | 10        | 5.65%   |
| Lenovo ThinkPad           | 9         | 5.08%   |
| Dell Latitude             | 8         | 4.52%   |
| HP EliteBook              | 7         | 3.95%   |
| MSI Modern                | 4         | 2.26%   |
| Toshiba Satellite         | 3         | 1.69%   |
| HP Notebook               | 3         | 1.69%   |
| HP 15                     | 3         | 1.69%   |
| Acer Nitro                | 3         | 1.69%   |
| HP Pavilion               | 2         | 1.13%   |
| HP Laptop                 | 2         | 1.13%   |
| HP ENVY                   | 2         | 1.13%   |
| HP 14                     | 2         | 1.13%   |
| Dell XPS                  | 2         | 1.13%   |
| ASUS X510UQ               | 2         | 1.13%   |
| ASUS P453UA               | 2         | 1.13%   |
| Timi Mi                   | 1         | 0.56%   |
| Samsung 300E5EV           | 1         | 0.56%   |
| Notebook W9x0LU           | 1         | 0.56%   |
| Notebook N750BU           | 1         | 0.56%   |
| Notebook N2x0LU           | 1         | 0.56%   |
| Notebook DCL              | 1         | 0.56%   |
| MSI Summit                | 1         | 0.56%   |
| MSI GS63                  | 1         | 0.56%   |
| Lenovo V330-14IKB         | 1         | 0.56%   |
| Lenovo S20-30             | 1         | 0.56%   |
| Lenovo S10-3              | 1         | 0.56%   |
| Lenovo LEGION5PRO-16ACH6H | 1         | 0.56%   |
| Lenovo Legion             | 1         | 0.56%   |
| Lenovo G40-70             | 1         | 0.56%   |
| HUAWEI RLEF-XX            | 1         | 0.56%   |
| HP ZHAN                   | 1         | 0.56%   |
| HP Mini                   | 1         | 0.56%   |
| HP 250                    | 1         | 0.56%   |
| HP 240                    | 1         | 0.56%   |
| Fujitsu LIFEBOOK          | 1         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2016 | 26        | 14.69%  |
| 2017 | 22        | 12.43%  |
| 2018 | 20        | 11.3%   |
| 2019 | 17        | 9.6%    |
| 2015 | 15        | 8.47%   |
| 2021 | 14        | 7.91%   |
| 2014 | 13        | 7.34%   |
| 2012 | 11        | 6.21%   |
| 2020 | 10        | 5.65%   |
| 2013 | 9         | 5.08%   |
| 2011 | 8         | 4.52%   |
| 2022 | 4         | 2.26%   |
| 2010 | 4         | 2.26%   |
| 2009 | 3         | 1.69%   |
| 2008 | 1         | 0.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 177       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 161       | 89.44%  |
| Enabled  | 19        | 10.56%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 177       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 71        | 39.44%  |
| 3.01-4.0   | 49        | 27.22%  |
| 8.01-16.0  | 34        | 18.89%  |
| 16.01-24.0 | 17        | 9.44%   |
| 1.01-2.0   | 6         | 3.33%   |
| 2.01-3.0   | 2         | 1.11%   |
| 32.01-64.0 | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 69        | 35.2%   |
| 2.01-3.0  | 61        | 31.12%  |
| 3.01-4.0  | 36        | 18.37%  |
| 4.01-8.0  | 18        | 9.18%   |
| 0.51-1.0  | 9         | 4.59%   |
| 8.01-16.0 | 2         | 1.02%   |
| 0.01-0.5  | 1         | 0.51%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 121       | 67.6%   |
| 2      | 56        | 31.28%  |
| 3      | 2         | 1.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 119       | 66.85%  |
| Yes       | 59        | 33.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 136       | 75.98%  |
| No        | 43        | 24.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 98.31%  |
| No        | 3         | 1.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 149       | 83.71%  |
| No        | 29        | 16.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Bangladesh | 177       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dhaka             | 107       | 57.53%  |
| Chittagong        | 11        | 5.91%   |
| Rajshahi          | 8         | 4.3%    |
| Jessore           | 6         | 3.23%   |
| Tongi             | 5         | 2.69%   |
| Khulna            | 5         | 2.69%   |
| Savar Upazila     | 4         | 2.15%   |
| Sylhet            | 3         | 1.61%   |
| Narayanganj       | 3         | 1.61%   |
| Comilla           | 3         | 1.61%   |
| Wari              | 2         | 1.08%   |
| Sherpur           | 2         | 1.08%   |
| Mirpur            | 2         | 1.08%   |
| Bogra             | 2         | 1.08%   |
| Azimpur           | 2         | 1.08%   |
| Srimangal         | 1         | 0.54%   |
| Sirajganj         | 1         | 0.54%   |
| Rangpur City      | 1         | 0.54%   |
| Pirganj           | 1         | 0.54%   |
| Pabna Sadar       | 1         | 0.54%   |
| Pabna             | 1         | 0.54%   |
| NДЃrДЃyanganj | 1         | 0.54%   |
| Nilphamari        | 1         | 0.54%   |
| Natore            | 1         | 0.54%   |
| Narail            | 1         | 0.54%   |
| Nalitabari        | 1         | 0.54%   |
| Nalchiti          | 1         | 0.54%   |
| Manirampur        | 1         | 0.54%   |
| LДЃkshДЃm     | 1         | 0.54%   |
| Khilgaon          | 1         | 0.54%   |
| Jamalpur          | 1         | 0.54%   |
| Gulshan           | 1         | 0.54%   |
| Fatullah          | 1         | 0.54%   |
| Faridpur          | 1         | 0.54%   |
| Dewangonj         | 1         | 0.54%   |
| Belkuchi          | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate                        | 43        | 54     | 18.78%  |
| WDC                            | 42        | 56     | 18.34%  |
| Toshiba                        | 32        | 41     | 13.97%  |
| Samsung Electronics            | 11        | 16     | 4.8%    |
| HGST                           | 11        | 11     | 4.8%    |
| Transcend                      | 10        | 11     | 4.37%   |
| Intel                          | 9         | 11     | 3.93%   |
| SanDisk                        | 8         | 8      | 3.49%   |
| Hitachi                        | 8         | 9      | 3.49%   |
| Micron Technology              | 6         | 6      | 2.62%   |
| Kingston                       | 6         | 8      | 2.62%   |
| A-DATA Technology              | 5         | 5      | 2.18%   |
| SK hynix                       | 3         | 3      | 1.31%   |
| Silicon Motion                 | 3         | 6      | 1.31%   |
| Corsair                        | 3         | 5      | 1.31%   |
| Ramsta                         | 2         | 2      | 0.87%   |
| KingSpec                       | 2         | 2      | 0.87%   |
| Apacer                         | 2         | 3      | 0.87%   |
| WDC WDS4                       | 1         | 1      | 0.44%   |
| WALTON                         | 1         | 2      | 0.44%   |
| Unknown                        | 1         | 1      | 0.44%   |
| Teutons                        | 1         | 1      | 0.44%   |
| Solid State Storage Technology | 1         | 1      | 0.44%   |
| Shenzhen Longsys Electronics   | 1         | 1      | 0.44%   |
| Realtek                        | 1         | 1      | 0.44%   |
| PNY                            | 1         | 1      | 0.44%   |
| Phison                         | 1         | 1      | 0.44%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 0.44%   |
| Lexar                          | 1         | 2      | 0.44%   |
| KIOXIA                         | 1         | 1      | 0.44%   |
| Kingsand                       | 1         | 1      | 0.44%   |
| HS-SSD-E100                    | 1         | 1      | 0.44%   |
| Hewlett-Packard                | 1         | 1      | 0.44%   |
| Gigabyte Technology            | 1         | 1      | 0.44%   |
| GeIL                           | 1         | 1      | 0.44%   |
| Crucial                        | 1         | 2      | 0.44%   |
| Colorful                       | 1         | 1      | 0.44%   |
| China                          | 1         | 1      | 0.44%   |
| BIWIN                          | 1         | 1      | 0.44%   |
| ASMT                           | 1         | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 970GB                  | 18        | 7.69%   |
| Toshiba MQ04ABF100 1TB                            | 15        | 6.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 6         | 2.56%   |
| WDC WD10JPVX-60JC3T0 1TB                          | 5         | 2.14%   |
| Seagate ST500LT012-1DG142 500GB                   | 5         | 2.14%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 4         | 1.71%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 4         | 1.71%   |
| Toshiba MQ01ABD100 1TB                            | 4         | 1.71%   |
| HGST HTS541010A9E680 1TB                          | 4         | 1.71%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                  | 3         | 1.28%   |
| Transcend TS120GMTS420S 120GB SSD                 | 3         | 1.28%   |
| Seagate ST500LT012-9WS142 500GB                   | 3         | 1.28%   |
| Seagate ST1000LM049-2GH172 1TB                    | 3         | 1.28%   |
| SanDisk NVMe SSD Drive 512GB                      | 3         | 1.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3         | 1.28%   |
| Intel SSD 660P Series 512GB                       | 3         | 1.28%   |
| Intel NVMe SSD Drive 512GB                        | 3         | 1.28%   |
| HGST HTS545050A7E680 500GB                        | 3         | 1.28%   |
| WDC WD10SPZX-24Z10T0 1TB                          | 2         | 0.85%   |
| WDC WD10JPVX-75JC3T0 1TB                          | 2         | 0.85%   |
| WDC WD10JPVX-60JC3T1 1TB                          | 2         | 0.85%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB              | 2         | 0.85%   |
| Transcend TS240GMTS820S 240GB SSD                 | 2         | 0.85%   |
| Toshiba THNSNK128GVN8 128GB SSD                   | 2         | 0.85%   |
| Toshiba MQ01ACF050 500GB                          | 2         | 0.85%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB | 2         | 0.85%   |
| Seagate ST9500325AS 500GB                         | 2         | 0.85%   |
| Samsung SSD 860 EVO 500GB                         | 2         | 0.85%   |
| Ramsta SSD R800 120GB                             | 2         | 0.85%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD               | 2         | 0.85%   |
| Hitachi HTS547550A9E384 500GB                     | 2         | 0.85%   |
| Hitachi HTS543232A7A384 320GB                     | 2         | 0.85%   |
| HGST HTS541010B7E610 1TB                          | 2         | 0.85%   |
| Corsair Force MP510 240GB                         | 2         | 0.85%   |
| A-DATA SU650 240GB SSD                            | 2         | 0.85%   |
| WDC WDS4 80G2G0B-00EPW0 480GB SSD                 | 1         | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 1         | 0.43%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD                  | 1         | 0.43%   |
| WDC WDS120G2G0A-00 120GB SSD                      | 1         | 0.43%   |
| WDC WD5000LPVX-75V0TT0 500GB                      | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 43        | 54     | 37.07%  |
| WDC     | 27        | 36     | 23.28%  |
| Toshiba | 27        | 35     | 23.28%  |
| HGST    | 11        | 11     | 9.48%   |
| Hitachi | 8         | 9      | 6.9%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 14     | 17.19%  |
| Transcend           | 10        | 11     | 15.63%  |
| SanDisk             | 5         | 5      | 7.81%   |
| Samsung Electronics | 5         | 7      | 7.81%   |
| Micron Technology   | 5         | 5      | 7.81%   |
| A-DATA Technology   | 5         | 5      | 7.81%   |
| Toshiba             | 2         | 3      | 3.13%   |
| Ramsta              | 2         | 2      | 3.13%   |
| KingSpec            | 2         | 2      | 3.13%   |
| Apacer              | 2         | 3      | 3.13%   |
| WDC WDS4            | 1         | 1      | 1.56%   |
| WALTON              | 1         | 2      | 1.56%   |
| Teutons             | 1         | 1      | 1.56%   |
| SK hynix            | 1         | 1      | 1.56%   |
| PNY                 | 1         | 1      | 1.56%   |
| Kingston            | 1         | 1      | 1.56%   |
| Intel               | 1         | 1      | 1.56%   |
| HS-SSD-E100         | 1         | 1      | 1.56%   |
| Hewlett-Packard     | 1         | 1      | 1.56%   |
| Gigabyte Technology | 1         | 1      | 1.56%   |
| GeIL                | 1         | 1      | 1.56%   |
| Crucial             | 1         | 2      | 1.56%   |
| Corsair             | 1         | 2      | 1.56%   |
| China               | 1         | 1      | 1.56%   |
| ASMT                | 1         | 1      | 1.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 116       | 145    | 51.79%  |
| SSD     | 61        | 75     | 27.23%  |
| NVMe    | 42        | 58     | 18.75%  |
| Unknown | 5         | 5      | 2.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 147       | 222    | 76.17%  |
| NVMe | 42        | 57     | 21.76%  |
| SAS  | 4         | 4      | 2.07%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 86        | 112    | 50.59%  |
| 0.51-1.0   | 81        | 105    | 47.65%  |
| 1.01-2.0   | 3         | 3      | 1.76%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 49        | 26.34%  |
| 251-500        | 48        | 25.81%  |
| 501-1000       | 37        | 19.89%  |
| 51-100         | 16        | 8.6%    |
| 1001-2000      | 13        | 6.99%   |
| 1-20           | 10        | 5.38%   |
| 21-50          | 8         | 4.3%    |
| Unknown        | 3         | 1.61%   |
| More than 3000 | 2         | 1.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 67        | 34.72%  |
| 51-100         | 36        | 18.65%  |
| 101-250        | 33        | 17.1%   |
| 21-50          | 32        | 16.58%  |
| 251-500        | 11        | 5.7%    |
| 501-1000       | 8         | 4.15%   |
| Unknown        | 3         | 1.55%   |
| 1001-2000      | 2         | 1.04%   |
| More than 3000 | 1         | 0.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                             | Notebooks | Drives | Percent |
|---------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                            | 2         | 4      | 8.33%   |
| HGST HTS545050A7E680 500GB                        | 2         | 2      | 8.33%   |
| HGST HTS541010A9E680 1TB                          | 2         | 2      | 8.33%   |
| WDC WD5000LPCX-22VHAT0 500GB                      | 1         | 1      | 4.17%   |
| WDC WD5000BPVT-22HXZT3 500GB                      | 1         | 1      | 4.17%   |
| WDC WD10SPZX-24Z10T0 1TB                          | 1         | 1      | 4.17%   |
| WDC WD10JPVX-60JC3T0 1TB                          | 1         | 2      | 4.17%   |
| Toshiba MQ01ABD050 500GB                          | 1         | 1      | 4.17%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD             | 1         | 1      | 4.17%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1TB | 1         | 1      | 4.17%   |
| Seagate ST9500325AS 500GB                         | 1         | 1      | 4.17%   |
| Seagate ST500LT012-9WS142 500GB                   | 1         | 1      | 4.17%   |
| Seagate ST500LT012-1DG142 500GB                   | 1         | 1      | 4.17%   |
| Seagate ST320LT012-9WS14C 320GB                   | 1         | 1      | 4.17%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                | 1         | 1      | 4.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 1         | 1      | 4.17%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD    | 1         | 1      | 4.17%   |
| Intel SSDSCKKW240H6 240GB                         | 1         | 1      | 4.17%   |
| Hitachi HTS545025B9A300 250GB                     | 1         | 1      | 4.17%   |
| HGST HTS545050A7E380 500GB                        | 1         | 1      | 4.17%   |
| Hewlett-Packard SSD S600 240GB                    | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 6      | 25%     |
| HGST              | 5         | 5      | 20.83%  |
| WDC               | 4         | 5      | 16.67%  |
| Toshiba           | 3         | 5      | 12.5%   |
| SK hynix          | 1         | 1      | 4.17%   |
| Silicon Motion    | 1         | 1      | 4.17%   |
| Micron Technology | 1         | 1      | 4.17%   |
| Intel             | 1         | 1      | 4.17%   |
| Hitachi           | 1         | 1      | 4.17%   |
| Hewlett-Packard   | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 31.58%  |
| HGST    | 5         | 5      | 26.32%  |
| WDC     | 4         | 5      | 21.05%  |
| Toshiba | 3         | 5      | 15.79%  |
| Hitachi | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 22     | 79.17%  |
| SSD  | 4         | 4      | 16.67%  |
| NVMe | 1         | 1      | 4.17%   |

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
| Detected | 102       | 159    | 53.4%   |
| Works    | 65        | 97     | 34.03%  |
| Malfunc  | 24        | 27     | 12.57%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 151       | 75.12%  |
| AMD                            | 13        | 6.47%   |
| SanDisk                        | 8         | 3.98%   |
| Samsung Electronics            | 6         | 2.99%   |
| Kingston Technology Company    | 5         | 2.49%   |
| Silicon Motion                 | 3         | 1.49%   |
| Phison Electronics             | 3         | 1.49%   |
| Toshiba America Info Systems   | 2         | 1%      |
| SK hynix                       | 2         | 1%      |
| Shenzhen Longsys Electronics   | 2         | 1%      |
| KIOXIA                         | 2         | 1%      |
| Solid State Storage Technology | 1         | 0.5%    |
| Micron Technology              | 1         | 0.5%    |
| MAXIO Technology (Hangzhou)    | 1         | 0.5%    |
| Biwin Storage Technology       | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 51        | 23.83%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 14        | 6.54%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 13        | 6.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 5.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 11        | 5.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 4.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 10        | 4.67%   |
| Intel Volume Management Device NVMe RAID Controller                              | 8         | 3.74%   |
| Intel SSD 660P Series                                                            | 6         | 2.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 2.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 2.34%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.87%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 1.4%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 1.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.4%    |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 1.4%    |
| Intel Tiger Lake-LP SATA Controller                                              | 3         | 1.4%    |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.4%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 2         | 0.93%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.93%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.93%   |
| Intel Non-Volatile memory controller                                             | 2         | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 0.93%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 1         | 0.47%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.47%   |
| Solid State Storage Non-Volatile memory controller                               | 1         | 0.47%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 0.47%   |
| SK hynix BC511                                                                   | 1         | 0.47%   |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 0.47%   |
| Shenzhen Longsys Non-Volatile memory controller                                  | 1         | 0.47%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                      | 1         | 0.47%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.47%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 0.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.47%   |
| Samsung NVMe SSD Controller PM9B1                                                | 1         | 0.47%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.47%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 140       | 66.99%  |
| NVMe | 42        | 20.1%   |
| RAID | 23        | 11%     |
| IDE  | 4         | 1.91%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 160       | 90.4%   |
| AMD    | 17        | 9.6%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 12        | 6.78%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 4.52%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 7         | 3.95%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 3.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 3.39%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 3.39%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 2.82%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 2.82%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.26%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 2.26%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 2.26%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 2.26%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 4         | 2.26%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 2.26%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 2.26%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 1.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.69%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 3         | 1.69%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.69%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 1.69%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 1.69%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 1.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.13%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 1.13%   |
| Intel Core i3-7130U CPU @ 2.70GHz             | 2         | 1.13%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.13%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.13%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 1.13%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz          | 2         | 1.13%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.13%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 2         | 1.13%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.13%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.56%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.56%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.56%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.56%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.56%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 1         | 0.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 74        | 41.81%  |
| Intel Core i3           | 40        | 22.6%   |
| Intel Core i7           | 16        | 9.04%   |
| Other                   | 13        | 7.34%   |
| AMD Ryzen 5             | 7         | 3.95%   |
| Intel Pentium           | 5         | 2.82%   |
| Intel Celeron           | 5         | 2.82%   |
| AMD Ryzen 7             | 5         | 2.82%   |
| Intel Core 2 Duo        | 3         | 1.69%   |
| Intel Atom              | 2         | 1.13%   |
| AMD Ryzen 3             | 2         | 1.13%   |
| Intel Pentium Dual-Core | 1         | 0.56%   |
| Intel Celeron Dual-Core | 1         | 0.56%   |
| AMD E2                  | 1         | 0.56%   |
| AMD A8                  | 1         | 0.56%   |
| AMD A4                  | 1         | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 116       | 65.54%  |
| 4      | 49        | 27.68%  |
| 8      | 6         | 3.39%   |
| 6      | 5         | 2.82%   |
| 1      | 1         | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 177       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 158       | 89.27%  |
| 1      | 19        | 10.73%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 176       | 99.44%  |
| Unknown        | 1         | 0.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 24.46%  |
| 0x806e9    | 23        | 12.5%   |
| 0x806ea    | 15        | 8.15%   |
| 0x406e3    | 11        | 5.98%   |
| 0x40651    | 10        | 5.43%   |
| 0x306d4    | 9         | 4.89%   |
| 0x206a7    | 8         | 4.35%   |
| 0x806ec    | 7         | 3.8%    |
| 0x306a9    | 7         | 3.8%    |
| 0x806eb    | 6         | 3.26%   |
| 0x806c1    | 6         | 3.26%   |
| 0x706e5    | 4         | 2.17%   |
| 0x406c4    | 4         | 2.17%   |
| 0x1067a    | 3         | 1.63%   |
| 0x08108102 | 3         | 1.63%   |
| 0xa0652    | 2         | 1.09%   |
| 0x306c3    | 2         | 1.09%   |
| 0x20655    | 2         | 1.09%   |
| 0x0a50000c | 2         | 1.09%   |
| 0x08108109 | 2         | 1.09%   |
| 0x906e9    | 1         | 0.54%   |
| 0x906a3    | 1         | 0.54%   |
| 0x806d1    | 1         | 0.54%   |
| 0x506e3    | 1         | 0.54%   |
| 0x406c3    | 1         | 0.54%   |
| 0x30678    | 1         | 0.54%   |
| 0x30661    | 1         | 0.54%   |
| 0x106ca    | 1         | 0.54%   |
| 0x10676    | 1         | 0.54%   |
| 0x08608103 | 1         | 0.54%   |
| 0x08600104 | 1         | 0.54%   |
| 0x0810100b | 1         | 0.54%   |
| 0x06006705 | 1         | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 63        | 35.59%  |
| Skylake          | 16        | 9.04%   |
| Haswell          | 14        | 7.91%   |
| Broadwell        | 12        | 6.78%   |
| TigerLake        | 10        | 5.65%   |
| SandyBridge      | 10        | 5.65%   |
| IvyBridge        | 10        | 5.65%   |
| Silvermont       | 7         | 3.95%   |
| Zen+             | 6         | 3.39%   |
| Penryn           | 5         | 2.82%   |
| IceLake          | 5         | 2.82%   |
| Zen 3            | 3         | 1.69%   |
| Zen 2            | 2         | 1.13%   |
| Westmere         | 2         | 1.13%   |
| Excavator        | 2         | 1.13%   |
| CometLake        | 2         | 1.13%   |
| Bonnell          | 2         | 1.13%   |
| Alderlake Hybrid | 2         | 1.13%   |
| Unknown          | 2         | 1.13%   |
| Zen              | 1         | 0.56%   |
| Puma             | 1         | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 159       | 71.3%   |
| Nvidia | 42        | 18.83%  |
| AMD    | 22        | 9.87%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 28        | 12.39%  |
| Intel UHD Graphics 620                                                                   | 15        | 6.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 6.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 6.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 5.31%   |
| Intel HD Graphics 5500                                                                   | 11        | 4.87%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 10        | 4.42%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 4.42%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 3.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.65%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 2.21%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 2.21%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.21%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 1.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.77%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.77%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 1.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.88%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.88%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.88%   |
| AMD Renoir                                                                               | 2         | 0.88%   |
| AMD Lucienne                                                                             | 2         | 0.88%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 0.88%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.44%   |
| Nvidia TU117M                                                                            | 1         | 0.44%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.44%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.44%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.44%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.44%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.44%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 118       | 66.67%  |
| Intel + Nvidia | 37        | 20.9%   |
| 1 x AMD        | 10        | 5.65%   |
| AMD + Nvidia   | 5         | 2.82%   |
| Intel + AMD    | 4         | 2.26%   |
| 2 x AMD        | 3         | 1.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 157       | 86.26%  |
| Proprietary | 23        | 12.64%  |
| Unknown     | 2         | 1.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 144       | 79.56%  |
| 1.01-2.0   | 20        | 11.05%  |
| 3.01-4.0   | 8         | 4.42%   |
| 0.01-0.5   | 5         | 2.76%   |
| 7.01-8.0   | 2         | 1.1%    |
| 5.01-6.0   | 1         | 0.55%   |
| 0.51-1.0   | 1         | 0.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 49        | 25.13%  |
| AU Optronics            | 42        | 21.54%  |
| Chimei Innolux          | 34        | 17.44%  |
| LG Display              | 31        | 15.9%   |
| Samsung Electronics     | 12        | 6.15%   |
| PANDA                   | 5         | 2.56%   |
| Dell                    | 5         | 2.56%   |
| Goldstar                | 4         | 2.05%   |
| Hewlett-Packard         | 3         | 1.54%   |
| Chi Mei Optoelectronics | 3         | 1.54%   |
| ViewSonic               | 1         | 0.51%   |
| Sharp                   | 1         | 0.51%   |
| MSI                     | 1         | 0.51%   |
| ASUSTek Computer        | 1         | 0.51%   |
| Apple                   | 1         | 0.51%   |
| AOC                     | 1         | 0.51%   |
| Ancor Communications    | 1         | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 9         | 4.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 4         | 2.05%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 3         | 1.54%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 3         | 1.54%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 3         | 1.54%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 3         | 1.54%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 3         | 1.54%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch             | 2         | 1.03%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch              | 2         | 1.03%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch              | 2         | 1.03%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 2         | 1.03%   |
| LG Display LCD Monitor LGD0466 1366x768 309x174mm 14.0-inch              | 2         | 1.03%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch              | 2         | 1.03%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 2         | 1.03%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 2         | 1.03%   |
| BOE LCD Monitor BOE07B4 1366x768 344x194mm 15.5-inch                     | 2         | 1.03%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 2         | 1.03%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 2         | 1.03%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                     | 2         | 1.03%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 2         | 1.03%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch            | 1         | 0.51%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.51%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 0.51%   |
| Samsung Electronics SyncMaster SAM043E 1600x1200 520x320mm 24.0-inch     | 1         | 0.51%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch        | 1         | 0.51%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch         | 1         | 0.51%   |
| Samsung Electronics S19C300 SAM0A12 1366x768 410x230mm 18.5-inch         | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 309x174mm 14.0-inch     | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch     | 1         | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 93        | 50.27%  |
| 1920x1080 (FHD)   | 74        | 40%     |
| 1600x900 (HD+)    | 4         | 2.16%   |
| 3840x2160 (4K)    | 3         | 1.62%   |
| 2560x1600         | 2         | 1.08%   |
| 1920x1200 (WUXGA) | 2         | 1.08%   |
| 1280x800 (WXGA)   | 2         | 1.08%   |
| 1024x600          | 2         | 1.08%   |
| 2560x1440 (QHD)   | 1         | 0.54%   |
| 2240x1400         | 1         | 0.54%   |
| 1280x1024 (SXGA)  | 1         | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 80        | 41.24%  |
| 13      | 41        | 21.13%  |
| 14      | 36        | 18.56%  |
| 21      | 8         | 4.12%   |
| 18      | 7         | 3.61%   |
| 12      | 6         | 3.09%   |
| 11      | 3         | 1.55%   |
| 23      | 2         | 1.03%   |
| 17      | 2         | 1.03%   |
| 16      | 2         | 1.03%   |
| 10      | 2         | 1.03%   |
| 27      | 1         | 0.52%   |
| 26      | 1         | 0.52%   |
| 24      | 1         | 0.52%   |
| 19      | 1         | 0.52%   |
| Unknown | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 149       | 77.2%   |
| 201-300     | 20        | 10.36%  |
| 401-500     | 17        | 8.81%   |
| 501-600     | 4         | 2.07%   |
| 351-400     | 2         | 1.04%   |
| Unknown     | 1         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 167       | 95.43%  |
| 16/10 | 7         | 4%      |
| 5/4   | 1         | 0.57%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 80        | 41.45%  |
| 81-90          | 68        | 35.23%  |
| 71-80          | 8         | 4.15%   |
| 141-150        | 8         | 4.15%   |
| 201-250        | 7         | 3.63%   |
| 61-70          | 6         | 3.11%   |
| 51-60          | 3         | 1.55%   |
| 151-200        | 3         | 1.55%   |
| 41-50          | 2         | 1.04%   |
| 251-300        | 2         | 1.04%   |
| 111-120        | 2         | 1.04%   |
| 301-350        | 1         | 0.52%   |
| 121-130        | 1         | 0.52%   |
| 91-100         | 1         | 0.52%   |
| Unknown        | 1         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 86        | 45.74%  |
| 121-160       | 78        | 41.49%  |
| 51-100        | 15        | 7.98%   |
| 161-240       | 7         | 3.72%   |
| More than 240 | 1         | 0.53%   |
| Unknown       | 1         | 0.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 157       | 87.71%  |
| 2     | 20        | 11.17%  |
| 3     | 1         | 0.56%   |
| 0     | 1         | 0.56%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 116       | 42.18%  |
| Intel                 | 85        | 30.91%  |
| Qualcomm Atheros      | 51        | 18.55%  |
| Broadcom              | 7         | 2.55%   |
| MediaTek              | 4         | 1.45%   |
| Ralink Technology     | 3         | 1.09%   |
| Xiaomi                | 2         | 0.73%   |
| TP-Link               | 1         | 0.36%   |
| Samsung Electronics   | 1         | 0.36%   |
| Ralink                | 1         | 0.36%   |
| OPPO Electronics      | 1         | 0.36%   |
| Dell                  | 1         | 0.36%   |
| ASIX Electronics      | 1         | 0.36%   |
| Arduino SA            | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 71        | 22.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 8.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 20        | 6.27%   |
| Intel Wireless 8265 / 8275                                        | 15        | 4.7%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 12        | 3.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 3.45%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 3.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 9         | 2.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 8         | 2.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 2.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.19%   |
| Intel Wireless 3165                                               | 6         | 1.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.57%   |
| Intel Wireless 8260                                               | 5         | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.25%   |
| Intel Wireless 7265                                               | 4         | 1.25%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.94%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 0.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.94%   |
| Intel Wireless 7260                                               | 3         | 0.94%   |
| Intel Wireless 3160                                               | 3         | 0.94%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.94%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.94%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.94%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.63%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.63%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2         | 0.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.63%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.63%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 0.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.31%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 82        | 45.56%  |
| Qualcomm Atheros      | 49        | 27.22%  |
| Realtek Semiconductor | 34        | 18.89%  |
| Broadcom              | 5         | 2.78%   |
| MediaTek              | 4         | 2.22%   |
| Ralink Technology     | 3         | 1.67%   |
| TP-Link               | 1         | 0.56%   |
| Ralink                | 1         | 0.56%   |
| Dell                  | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 20        | 11.11%  |
| Intel Wireless 8265 / 8275                                     | 15        | 8.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12        | 6.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 6.11%   |
| Intel Wi-Fi 6 AX201                                            | 10        | 5.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 9         | 5%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 8         | 4.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 3.89%   |
| Intel Wireless 3165                                            | 6         | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 2.78%   |
| Intel Wireless 8260                                            | 5         | 2.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.22%   |
| Intel Wireless 7265                                            | 4         | 2.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.67%   |
| Ralink MT7601U Wireless Adapter                                | 3         | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 1.67%   |
| Intel Wireless 7260                                            | 3         | 1.67%   |
| Intel Wireless 3160                                            | 3         | 1.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 1.67%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.67%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.11%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 2         | 1.11%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.11%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.11%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.11%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.11%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.56%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.56%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.56%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.56%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 103       | 74.64%  |
| Intel                 | 21        | 15.22%  |
| Qualcomm Atheros      | 6         | 4.35%   |
| Broadcom              | 3         | 2.17%   |
| Xiaomi                | 2         | 1.45%   |
| Samsung Electronics   | 1         | 0.72%   |
| OPPO Electronics      | 1         | 0.72%   |
| ASIX Electronics      | 1         | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 71        | 51.45%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 20.29%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 5.07%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 2.9%    |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.45%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 1.45%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.72%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.72%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.72%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.72%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.72%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                              | 1         | 0.72%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.72%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.72%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.72%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.72%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 174       | 55.95%  |
| Ethernet | 136       | 43.73%  |
| Modem    | 1         | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 154       | 84.62%  |
| Ethernet | 28        | 15.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 126       | 71.19%  |
| 1     | 51        | 28.81%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 177       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 68        | 45.33%  |
| IMC Networks                    | 22        | 14.67%  |
| Realtek Semiconductor           | 18        | 12%     |
| Qualcomm Atheros Communications | 13        | 8.67%   |
| Lite-On Technology              | 11        | 7.33%   |
| Broadcom                        | 7         | 4.67%   |
| Foxconn / Hon Hai               | 4         | 2.67%   |
| Toshiba                         | 1         | 0.67%   |
| Ralink                          | 1         | 0.67%   |
| MediaTek                        | 1         | 0.67%   |
| Hewlett-Packard                 | 1         | 0.67%   |
| Foxconn International           | 1         | 0.67%   |
| Dell                            | 1         | 0.67%   |
| Cambridge Silicon Radio         | 1         | 0.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 36        | 24%     |
| Realtek Bluetooth Radio                             | 12        | 8%      |
| Intel AX201 Bluetooth                               | 12        | 8%      |
| IMC Networks Bluetooth Device                       | 12        | 8%      |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 6.67%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 5.33%   |
| IMC Networks Bluetooth Radio                        | 8         | 5.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 7         | 4.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 4.67%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 2%      |
| Lite-On Bluetooth Device                            | 3         | 2%      |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 1.33%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.33%   |
| Intel AX200 Bluetooth                               | 2         | 1.33%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.33%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.33%   |
| Toshiba Bluetooth Radio                             | 1         | 0.67%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.67%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.67%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.67%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.67%   |
| MediaTek Wireless_Device                            | 1         | 0.67%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.67%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.67%   |
| IMC Networks Wireless_Device                        | 1         | 0.67%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.67%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.67%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.67%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.67%   |
| Dell Wireless 360 Bluetooth                         | 1         | 0.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.67%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.67%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 159       | 85.95%  |
| AMD                    | 17        | 9.19%   |
| Nvidia                 | 8         | 4.32%   |
| Generalplus Technology | 1         | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 58        | 25.66%  |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 14        | 6.19%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 14        | 6.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 5.31%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 5.31%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 5.31%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 5.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 5.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 4.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 3.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.65%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 2.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 2.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 2.21%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 0.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.88%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.88%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 0.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 0.88%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.88%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.44%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.44%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.44%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.44%   |
| Intel USB PnP Sound Device                                                                        | 1         | 0.44%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.44%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.44%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.44%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.44%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.44%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 37        | 28.68%  |
| SK hynix            | 34        | 26.36%  |
| Micron Technology   | 17        | 13.18%  |
| A-DATA Technology   | 7         | 5.43%   |
| Kingston            | 6         | 4.65%   |
| Unknown             | 4         | 3.1%    |
| Transcend           | 4         | 3.1%    |
| G.Skill             | 4         | 3.1%    |
| Team                | 2         | 1.55%   |
| Ramaxel Technology  | 2         | 1.55%   |
| Nanya Technology    | 2         | 1.55%   |
| Crucial             | 2         | 1.55%   |
| Unknown (C509)      | 1         | 0.78%   |
| Unknown (768A)      | 1         | 0.78%   |
| Toshiba             | 1         | 0.78%   |
| Hewlett-Packard     | 1         | 0.78%   |
| Elpida              | 1         | 0.78%   |
| ASint Technology    | 1         | 0.78%   |
| Apacer              | 1         | 0.78%   |
| Unknown             | 1         | 0.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s | 6         | 4.62%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s | 4         | 3.08%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s  | 4         | 3.08%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 3         | 2.31%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s | 3         | 2.31%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s | 3         | 2.31%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s  | 3         | 2.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s | 2         | 1.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s | 2         | 1.54%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s | 2         | 1.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 2         | 1.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s  | 2         | 1.54%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s  | 2         | 1.54%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s  | 2         | 1.54%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s | 2         | 1.54%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s  | 2         | 1.54%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s  | 2         | 1.54%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s   | 2         | 1.54%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s   | 2         | 1.54%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s  | 2         | 1.54%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s  | 2         | 1.54%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s | 2         | 1.54%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s         | 1         | 0.77%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s            | 1         | 0.77%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.77%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s    | 1         | 0.77%   |
| Unknown (C509) RAM Module 4GB SODIMM DDR4 2400MT/s     | 1         | 0.77%   |
| Unknown (768A) RAM Module 8192MB SODIMM DDR4 3200MT/s  | 1         | 0.77%   |
| Transcend RAM JM3200HSB-8G 8GB SODIMM DDR4 3200MT/s    | 1         | 0.77%   |
| Transcend RAM JM2666HSG-8G 8GB SODIMM DDR4 2667MT/s    | 1         | 0.77%   |
| Transcend RAM JM2400HSB-8G 8GB SODIMM DDR4 2400MT/s    | 1         | 0.77%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM 1334MT/s         | 1         | 0.77%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s     | 1         | 0.77%   |
| Toshiba RAM 64T128020EDL2.5C2 1GB SODIMM 1066MT/s      | 1         | 0.77%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s  | 1         | 0.77%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s  | 1         | 0.77%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s        | 1         | 0.77%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2133MT/s        | 1         | 0.77%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 0.77%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s | 1         | 0.77%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 62        | 63.92%  |
| DDR3   | 26        | 26.8%   |
| LPDDR4 | 5         | 5.15%   |
| LPDDR3 | 2         | 2.06%   |
| SDRAM  | 1         | 1.03%   |
| DDR2   | 1         | 1.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 89        | 95.7%   |
| Row Of Chips | 4         | 4.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 48        | 44.86%  |
| 4096  | 43        | 40.19%  |
| 16384 | 7         | 6.54%   |
| 2048  | 7         | 6.54%   |
| 32768 | 1         | 0.93%   |
| 1024  | 1         | 0.93%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 30        | 28.85%  |
| 1600  | 19        | 18.27%  |
| 3200  | 16        | 15.38%  |
| 2400  | 13        | 12.5%   |
| 2133  | 10        | 9.62%   |
| 1067  | 4         | 3.85%   |
| 1334  | 3         | 2.88%   |
| 3266  | 2         | 1.92%   |
| 1333  | 2         | 1.92%   |
| 8400  | 1         | 0.96%   |
| 4267  | 1         | 0.96%   |
| 4199  | 1         | 0.96%   |
| 1867  | 1         | 0.96%   |
| 1066  | 1         | 0.96%   |

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
| Chicony Electronics                    | 37        | 22.56%  |
| IMC Networks                           | 31        | 18.9%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 9.15%   |
| Realtek Semiconductor                  | 12        | 7.32%   |
| Quanta                                 | 11        | 6.71%   |
| Sunplus Innovation Technology          | 10        | 6.1%    |
| Microdia                               | 10        | 6.1%    |
| Lite-On Technology                     | 7         | 4.27%   |
| Bison Electronics                      | 6         | 3.66%   |
| Suyin                                  | 5         | 3.05%   |
| Luxvisions Innotech Limited            | 5         | 3.05%   |
| Acer                                   | 5         | 3.05%   |
| Syntek                                 | 2         | 1.22%   |
| Sonix Technology                       | 2         | 1.22%   |
| Silicon Motion                         | 2         | 1.22%   |
| Primax Electronics                     | 2         | 1.22%   |
| Importek                               | 1         | 0.61%   |
| Apple                                  | 1         | 0.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 10        | 6.1%    |
| Chicony USB2.0 VGA UVC WebCam                           | 10        | 6.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 9         | 5.49%   |
| IMC Networks VGA UVC WebCam                             | 5         | 3.05%   |
| Chicony HD WebCam                                       | 5         | 3.05%   |
| Microdia Integrated_Webcam_HD                           | 4         | 2.44%   |
| Luxvisions Innotech Limited HP HD Camera                | 4         | 2.44%   |
| Lite-On HP HD Camera                                    | 4         | 2.44%   |
| Suyin Integrated_Webcam_HD                              | 3         | 1.83%   |
| Realtek Integrated_Webcam_HD                            | 3         | 1.83%   |
| Quanta HD Webcam                                        | 3         | 1.83%   |
| IMC Networks USB2.0 HD IR UVC WebCam                    | 3         | 1.83%   |
| IMC Networks Integrated Camera                          | 3         | 1.83%   |
| Chicony EasyCamera                                      | 3         | 1.83%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 3         | 1.83%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 3         | 1.83%   |
| Suyin HP Truevision HD                                  | 2         | 1.22%   |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 1.22%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.22%   |
| Realtek USB2.0 VGA UVC WebCam                           | 2         | 1.22%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.22%   |
| Quanta HP HD Camera                                     | 2         | 1.22%   |
| Quanta HD User Facing                                   | 2         | 1.22%   |
| Primax HP HD Webcam [Fixed]                             | 2         | 1.22%   |
| Microdia HP Integrated Webcam                           | 2         | 1.22%   |
| Lite-On Integrated Camera                               | 2         | 1.22%   |
| Chicony USB2.0 Camera                                   | 2         | 1.22%   |
| Chicony Integrated Camera                               | 2         | 1.22%   |
| Chicony HP Truevision HD camera                         | 2         | 1.22%   |
| Chicony HP HD Webcam                                    | 2         | 1.22%   |
| Chicony HP HD Camera                                    | 2         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 2         | 1.22%   |
| Bison Integrated Camera                                 | 2         | 1.22%   |
| Bison HD Webcam                                         | 2         | 1.22%   |
| Bison EasyCamera                                        | 2         | 1.22%   |
| Acer Lenovo EasyCamera                                  | 2         | 1.22%   |
| Acer HD Webcam                                          | 2         | 1.22%   |
| Syntek Integrated Camera                                | 1         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 25        | 78.13%  |
| Synaptics                  | 3         | 9.38%   |
| Elan Microelectronics      | 2         | 6.25%   |
| Upek                       | 1         | 3.13%   |
| Shenzhen Goodix Technology | 1         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 43.75%  |
| Validity Sensors VFS491                                                    | 3         | 9.38%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 9.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 6.25%   |
| Elan ELAN:Fingerprint                                                      | 2         | 6.25%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.13%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 3.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 3.13%   |
| Synaptics  WBDI                                                            | 1         | 3.13%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 3.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 6         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 33.33%  |
| Broadcom 5880                                                                | 2         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 16.67%  |
| Broadcom 58200                                                               | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 124       | 67.39%  |
| 1     | 51        | 27.72%  |
| 2     | 7         | 3.8%    |
| 5     | 1         | 0.54%   |
| 3     | 1         | 0.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 32        | 46.38%  |
| Graphics card         | 17        | 24.64%  |
| Chipcard              | 6         | 8.7%    |
| Net/wireless          | 4         | 5.8%    |
| Camera                | 4         | 5.8%    |
| Multimedia controller | 2         | 2.9%    |
| Bluetooth             | 2         | 2.9%    |
| Sound                 | 1         | 1.45%   |
| Card reader           | 1         | 1.45%   |

