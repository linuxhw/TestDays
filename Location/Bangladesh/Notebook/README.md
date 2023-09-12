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

Total: 282

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop M760... | [699fb7e97e](https://linux-hardware.org/?probe=699fb7e97e) | Sep 07, 2023 |
| ASUSTek       | X580VD                      | [989134a7c5](https://linux-hardware.org/?probe=989134a7c5) | Sep 06, 2023 |
| win elemen... | MoreFine S500+              | [9675488adc](https://linux-hardware.org/?probe=9675488adc) | Aug 28, 2023 |
| win elemen... | MoreFine S500+              | [29e062fb36](https://linux-hardware.org/?probe=29e062fb36) | Aug 27, 2023 |
| Dell          | Vostro 3500                 | [2ec62f31c9](https://linux-hardware.org/?probe=2ec62f31c9) | Aug 12, 2023 |
| MSI           | Modern 15 A5M               | [a4a6f81455](https://linux-hardware.org/?probe=a4a6f81455) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | [ef010c9d51](https://linux-hardware.org/?probe=ef010c9d51) | Aug 05, 2023 |
| HP            | Laptop 14s-dq2xxx           | [8aad3290a7](https://linux-hardware.org/?probe=8aad3290a7) | Aug 03, 2023 |
| HUAWEI        | RLEF-XX                     | [23793e7d9c](https://linux-hardware.org/?probe=23793e7d9c) | Jul 14, 2023 |
| HUAWEI        | RLEF-XX                     | [8974860f56](https://linux-hardware.org/?probe=8974860f56) | Jul 12, 2023 |
| HP            | Notebook                    | [9487146a2f](https://linux-hardware.org/?probe=9487146a2f) | Jun 09, 2023 |
| Dell          | Vostro 3500                 | [c64ff76dba](https://linux-hardware.org/?probe=c64ff76dba) | Jun 09, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [4808ee44b5](https://linux-hardware.org/?probe=4808ee44b5) | Jun 04, 2023 |
| Acer          | Aspire F5-573G              | [f8ec1083ad](https://linux-hardware.org/?probe=f8ec1083ad) | May 26, 2023 |
| Acer          | Aspire F5-573G              | [eb636c0b30](https://linux-hardware.org/?probe=eb636c0b30) | May 26, 2023 |
| HP            | ProBook 4540s               | [2a2712560e](https://linux-hardware.org/?probe=2a2712560e) | May 17, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [38482c1a10](https://linux-hardware.org/?probe=38482c1a10) | May 15, 2023 |
| Lenovo        | S20-30 20421                | [cc4f992884](https://linux-hardware.org/?probe=cc4f992884) | May 12, 2023 |
| ASUSTek       | X556UQK                     | [12d23bdebb](https://linux-hardware.org/?probe=12d23bdebb) | May 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [6fc095ce39](https://linux-hardware.org/?probe=6fc095ce39) | May 04, 2023 |
| HUAWEI        | RLEF-XX                     | [b97932d8f1](https://linux-hardware.org/?probe=b97932d8f1) | May 03, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [c4841e9b59](https://linux-hardware.org/?probe=c4841e9b59) | May 02, 2023 |
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
| Ubuntu 20.04                 | 35        | 16.59%  |
| ArcoLinux Rolling            | 10        | 4.74%   |
| Arch                         | 9         | 4.27%   |
| Ubuntu 22.04                 | 7         | 3.32%   |
| Pop!_OS 22.04                | 6         | 2.84%   |
| Manjaro                      | 6         | 2.84%   |
| Arch Rolling                 | 6         | 2.84%   |
| KDE neon 20.04               | 5         | 2.37%   |
| Zorin 16                     | 4         | 1.9%    |
| Ubuntu 19.10                 | 4         | 1.9%    |
| Ubuntu 18.04                 | 4         | 1.9%    |
| Fedora 33                    | 4         | 1.9%    |
| EndeavourOS Rolling          | 4         | 1.9%    |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 1.42%   |
| OpenMandriva 4.2             | 3         | 1.42%   |
| Manjaro 20.0.1               | 3         | 1.42%   |
| Fedora 38                    | 3         | 1.42%   |
| Fedora 37                    | 3         | 1.42%   |
| Debian 11                    | 3         | 1.42%   |
| Zorin 15                     | 2         | 0.95%   |
| Ubuntu 22.10                 | 2         | 0.95%   |
| Ubuntu 19.04                 | 2         | 0.95%   |
| Ubuntu 18.10                 | 2         | 0.95%   |
| Pop!_OS 21.10                | 2         | 0.95%   |
| OpenMandriva 4.90            | 2         | 0.95%   |
| MX 21                        | 2         | 0.95%   |
| Manjaro 21.2.6               | 2         | 0.95%   |
| Manjaro 18.0.4               | 2         | 0.95%   |
| Linux Mint 20.1              | 2         | 0.95%   |
| Linux Mint 20                | 2         | 0.95%   |
| Kubuntu 20.04                | 2         | 0.95%   |
| KDE neon 22.04               | 2         | 0.95%   |
| Kali 2022.4                  | 2         | 0.95%   |
| Kali 2022.3                  | 2         | 0.95%   |
| Fedora 34                    | 2         | 0.95%   |
| Debian 12                    | 2         | 0.95%   |
| Ubuntu Unity 16.04           | 1         | 0.47%   |
| Ubuntu 23.04                 | 1         | 0.47%   |
| Ubuntu 21.04                 | 1         | 0.47%   |
| Ubuntu 20.10                 | 1         | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 57        | 29.23%  |
| Manjaro      | 19        | 9.74%   |
| Arch         | 14        | 7.18%   |
| Fedora       | 12        | 6.15%   |
| Pop!_OS      | 10        | 5.13%   |
| ArcoLinux    | 10        | 5.13%   |
| Linux Mint   | 9         | 4.62%   |
| KDE neon     | 7         | 3.59%   |
| Debian       | 7         | 3.59%   |
| Zorin        | 6         | 3.08%   |
| OpenMandriva | 6         | 3.08%   |
| Kubuntu      | 6         | 3.08%   |
| Endless      | 5         | 2.56%   |
| EndeavourOS  | 5         | 2.56%   |
| Kali         | 4         | 2.05%   |
| Parrot       | 3         | 1.54%   |
| openSUSE     | 3         | 1.54%   |
| MX           | 2         | 1.03%   |
| Artix        | 2         | 1.03%   |
| Ubuntu Unity | 1         | 0.51%   |
| Lubuntu      | 1         | 0.51%   |
| LMDE         | 1         | 0.51%   |
| Devuan       | 1         | 0.51%   |
| Deepin       | 1         | 0.51%   |
| Clear Linux  | 1         | 0.51%   |
| CentOS       | 1         | 0.51%   |
| BlackPanther | 1         | 0.51%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 7         | 3.06%   |
| 5.4.0-52-generic         | 3         | 1.31%   |
| 5.4.0-40-generic         | 3         | 1.31%   |
| 5.4.0-29-generic         | 3         | 1.31%   |
| 5.10.14-desktop-1omv4002 | 3         | 1.31%   |
| 6.2.9-300.fc38.x86_64    | 2         | 0.87%   |
| 6.0.9-zen1-1-zen         | 2         | 0.87%   |
| 6.0.0-kali6-amd64        | 2         | 0.87%   |
| 5.9.16-1-MANJARO         | 2         | 0.87%   |
| 5.8.0-50-generic         | 2         | 0.87%   |
| 5.8.0-41-generic         | 2         | 0.87%   |
| 5.8.0-14-generic         | 2         | 0.87%   |
| 5.7.19-2-MANJARO         | 2         | 0.87%   |
| 5.6.11-1-MANJARO         | 2         | 0.87%   |
| 5.4.8-arch1-1            | 2         | 0.87%   |
| 5.4.0-53-generic         | 2         | 0.87%   |
| 5.4.0-19-generic         | 2         | 0.87%   |
| 5.3.0-24-generic         | 2         | 0.87%   |
| 5.3.0-23-generic         | 2         | 0.87%   |
| 5.19.0-kali2-amd64       | 2         | 0.87%   |
| 5.19.0-35-generic        | 2         | 0.87%   |
| 5.19.0-29-generic        | 2         | 0.87%   |
| 5.18.12-desktop-3omv4090 | 2         | 0.87%   |
| 5.15.0-53-generic        | 2         | 0.87%   |
| 5.15.0-48-generic        | 2         | 0.87%   |
| 5.15.0-46-generic        | 2         | 0.87%   |
| 5.13.0-28-generic        | 2         | 0.87%   |
| 5.11.0-40-generic        | 2         | 0.87%   |
| 5.11.0-27-generic        | 2         | 0.87%   |
| 5.10.52-1-lts            | 2         | 0.87%   |
| 5.10.0-13-amd64          | 2         | 0.87%   |
| 6.5.0-1-MANJARO          | 1         | 0.44%   |
| 6.4.0-1-amd64            | 1         | 0.44%   |
| 6.3.3-arch1-1            | 1         | 0.44%   |
| 6.3.2-artix1-1           | 1         | 0.44%   |
| 6.3.1-arch2-1            | 1         | 0.44%   |
| 6.2.8-arch1-1            | 1         | 0.44%   |
| 6.2.7-zen1-1-zen         | 1         | 0.44%   |
| 6.2.7-200.fc37.x86_64    | 1         | 0.44%   |
| 6.2.15-300.fc38.x86_64   | 1         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 28        | 12.84%  |
| 5.15.0  | 14        | 6.42%   |
| 5.8.0   | 13        | 5.96%   |
| 5.11.0  | 12        | 5.5%    |
| 5.19.0  | 8         | 3.67%   |
| 5.13.0  | 8         | 3.67%   |
| 5.10.0  | 7         | 3.21%   |
| 5.3.0   | 6         | 2.75%   |
| 6.0.0   | 5         | 2.29%   |
| 5.0.0   | 4         | 1.83%   |
| 4.18.0  | 4         | 1.83%   |
| 4.15.0  | 4         | 1.83%   |
| 6.0.12  | 3         | 1.38%   |
| 5.9.16  | 3         | 1.38%   |
| 5.18.12 | 3         | 1.38%   |
| 5.10.14 | 3         | 1.38%   |
| 4.19.0  | 3         | 1.38%   |
| 6.2.9   | 2         | 0.92%   |
| 6.2.7   | 2         | 0.92%   |
| 6.2.0   | 2         | 0.92%   |
| 6.1.0   | 2         | 0.92%   |
| 6.0.9   | 2         | 0.92%   |
| 5.7.19  | 2         | 0.92%   |
| 5.6.11  | 2         | 0.92%   |
| 5.4.8   | 2         | 0.92%   |
| 5.16.15 | 2         | 0.92%   |
| 5.15.5  | 2         | 0.92%   |
| 5.10.52 | 2         | 0.92%   |
| 6.5.0   | 1         | 0.46%   |
| 6.4.0   | 1         | 0.46%   |
| 6.3.3   | 1         | 0.46%   |
| 6.3.2   | 1         | 0.46%   |
| 6.3.1   | 1         | 0.46%   |
| 6.2.8   | 1         | 0.46%   |
| 6.2.15  | 1         | 0.46%   |
| 6.2.12  | 1         | 0.46%   |
| 6.1.9   | 1         | 0.46%   |
| 6.1.8   | 1         | 0.46%   |
| 6.1.7   | 1         | 0.46%   |
| 6.1.18  | 1         | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 16.27%  |
| 5.15    | 23        | 11%     |
| 5.8     | 16        | 7.66%   |
| 5.10    | 16        | 7.66%   |
| 5.11    | 15        | 7.18%   |
| 6.0     | 11        | 5.26%   |
| 5.19    | 10        | 4.78%   |
| 6.2     | 9         | 4.31%   |
| 5.13    | 9         | 4.31%   |
| 6.1     | 7         | 3.35%   |
| 5.16    | 7         | 3.35%   |
| 5.3     | 6         | 2.87%   |
| 5.18    | 6         | 2.87%   |
| 4.18    | 5         | 2.39%   |
| 5.9     | 4         | 1.91%   |
| 5.0     | 4         | 1.91%   |
| 4.19    | 4         | 1.91%   |
| 4.15    | 4         | 1.91%   |
| 6.3     | 3         | 1.44%   |
| 5.7     | 3         | 1.44%   |
| 5.17    | 3         | 1.44%   |
| 5.6     | 2         | 0.96%   |
| 5.14    | 2         | 0.96%   |
| 5.12    | 2         | 0.96%   |
| 5.1     | 2         | 0.96%   |
| 6.5     | 1         | 0.48%   |
| 6.4     | 1         | 0.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 185       | 98.93%  |
| i686   | 2         | 1.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| GNOME          | 93        | 47.69%  |
| KDE5           | 43        | 22.05%  |
| Unknown        | 18        | 9.23%   |
| XFCE           | 15        | 7.69%   |
| X-Cinnamon     | 8         | 4.1%    |
| MATE           | 3         | 1.54%   |
| awesome        | 3         | 1.54%   |
| KDE            | 2         | 1.03%   |
| i3-with-shmlog | 2         | 1.03%   |
| Unity          | 1         | 0.51%   |
| qtile          | 1         | 0.51%   |
| LXQt           | 1         | 0.51%   |
| LXDE           | 1         | 0.51%   |
| i3             | 1         | 0.51%   |
| DWM            | 1         | 0.51%   |
| Deepin         | 1         | 0.51%   |
| bspwm          | 1         | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 155       | 78.28%  |
| Wayland | 31        | 15.66%  |
| Unknown | 10        | 5.05%   |
| Tty     | 2         | 1.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 91        | 45.96%  |
| SDDM    | 34        | 17.17%  |
| GDM     | 29        | 14.65%  |
| LightDM | 20        | 10.1%   |
| GDM3    | 18        | 9.09%   |
| TDM     | 6         | 3.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 157       | 82.63%  |
| Unknown | 16        | 8.42%   |
| en_GB   | 7         | 3.68%   |
| C       | 5         | 2.63%   |
| en_IE   | 1         | 0.53%   |
| en_EN   | 1         | 0.53%   |
| en_CA   | 1         | 0.53%   |
| en_AG   | 1         | 0.53%   |
| Default | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 102       | 52.85%  |
| BIOS | 91        | 47.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 148       | 78.31%  |
| Btrfs   | 20        | 10.58%  |
| Overlay | 16        | 8.47%   |
| Unknown | 3         | 1.59%   |
| Xfs     | 1         | 0.53%   |
| Tmpfs   | 1         | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 99        | 50.77%  |
| GPT     | 76        | 38.97%  |
| MBR     | 20        | 10.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 166       | 87.37%  |
| Yes       | 24        | 12.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 111       | 58.12%  |
| Yes       | 80        | 41.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 49        | 26.2%   |
| Hewlett-Packard     | 45        | 24.06%  |
| Lenovo              | 27        | 14.44%  |
| Dell                | 25        | 13.37%  |
| Acer                | 19        | 10.16%  |
| MSI                 | 7         | 3.74%   |
| Notebook            | 4         | 2.14%   |
| Toshiba             | 3         | 1.6%    |
| win element         | 1         | 0.53%   |
| Timi                | 1         | 0.53%   |
| Samsung Electronics | 1         | 0.53%   |
| HUAWEI              | 1         | 0.53%   |
| Fujitsu             | 1         | 0.53%   |
| Daffodil Computers  | 1         | 0.53%   |
| Apple               | 1         | 0.53%   |
| Unknown             | 1         | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP ProBook 450 G4                                     | 5         | 2.67%   |
| HP Notebook                                           | 4         | 2.14%   |
| MSI Modern 15 A5M                                     | 3         | 1.6%    |
| ASUS VivoBook_ASUSLaptop X530FN_S530FN                | 3         | 1.6%    |
| MSI Modern 14 B10MW                                   | 2         | 1.07%   |
| HP ProBook 4540s                                      | 2         | 1.07%   |
| HP ProBook 450 G2                                     | 2         | 1.07%   |
| HP ProBook 440 G8 Notebook PC                         | 2         | 1.07%   |
| HP EliteBook 840 G3                                   | 2         | 1.07%   |
| HP 15                                                 | 2         | 1.07%   |
| HP 14                                                 | 2         | 1.07%   |
| Dell Inspiron 3442                                    | 2         | 1.07%   |
| ASUS X556UQK                                          | 2         | 1.07%   |
| ASUS X510UQ                                           | 2         | 1.07%   |
| ASUS VivoBook_ASUSLaptop X531FL_S531FL                | 2         | 1.07%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA                | 2         | 1.07%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA                | 2         | 1.07%   |
| ASUS VivoBook 14_ASUS Laptop X407UA                   | 2         | 1.07%   |
| ASUS P453UA                                           | 2         | 1.07%   |
| Acer Nitro AN515-43                                   | 2         | 1.07%   |
| win element MoreFine S500+                            | 1         | 0.53%   |
| Toshiba Satellite Pro L510                            | 1         | 0.53%   |
| Toshiba Satellite L645                                | 1         | 0.53%   |
| Toshiba Satellite C660                                | 1         | 0.53%   |
| Timi Mi NoteBook Pro                                  | 1         | 0.53%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.53%   |
| Notebook W9x0LU                                       | 1         | 0.53%   |
| Notebook N750BU                                       | 1         | 0.53%   |
| Notebook N2x0LU                                       | 1         | 0.53%   |
| Notebook DCL C483                                     | 1         | 0.53%   |
| MSI Summit B14 A11MOT                                 | 1         | 0.53%   |
| MSI GS63 7RD                                          | 1         | 0.53%   |
| Lenovo V330-14IKB 81B0                                | 1         | 0.53%   |
| Lenovo ThinkPad X230 2324F51                          | 1         | 0.53%   |
| Lenovo ThinkPad X230 2324A82                          | 1         | 0.53%   |
| Lenovo ThinkPad X220 4290CTO                          | 1         | 0.53%   |
| Lenovo ThinkPad T470s 20HGS23V06                      | 1         | 0.53%   |
| Lenovo ThinkPad T450 20BUS2021M                       | 1         | 0.53%   |
| Lenovo ThinkPad T430s 2356GPU                         | 1         | 0.53%   |
| Lenovo ThinkPad L380 20M6S22500                       | 1         | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| ASUS VivoBook             | 23        | 12.3%   |
| HP ProBook                | 19        | 10.16%  |
| Acer Aspire               | 15        | 8.02%   |
| Lenovo IdeaPad            | 12        | 6.42%   |
| Dell Inspiron             | 12        | 6.42%   |
| Lenovo ThinkPad           | 9         | 4.81%   |
| Dell Latitude             | 8         | 4.28%   |
| HP EliteBook              | 7         | 3.74%   |
| MSI Modern                | 5         | 2.67%   |
| HP Notebook               | 4         | 2.14%   |
| Toshiba Satellite         | 3         | 1.6%    |
| HP 15                     | 3         | 1.6%    |
| Acer Nitro                | 3         | 1.6%    |
| HP Pavilion               | 2         | 1.07%   |
| HP Laptop                 | 2         | 1.07%   |
| HP ENVY                   | 2         | 1.07%   |
| HP 14                     | 2         | 1.07%   |
| Dell XPS                  | 2         | 1.07%   |
| Dell Vostro               | 2         | 1.07%   |
| ASUS X556UQK              | 2         | 1.07%   |
| ASUS X510UQ               | 2         | 1.07%   |
| ASUS P453UA               | 2         | 1.07%   |
| win element MoreFine      | 1         | 0.53%   |
| Timi Mi                   | 1         | 0.53%   |
| Samsung 300E5EV           | 1         | 0.53%   |
| Notebook W9x0LU           | 1         | 0.53%   |
| Notebook N750BU           | 1         | 0.53%   |
| Notebook N2x0LU           | 1         | 0.53%   |
| Notebook DCL              | 1         | 0.53%   |
| MSI Summit                | 1         | 0.53%   |
| MSI GS63                  | 1         | 0.53%   |
| Lenovo V330-14IKB         | 1         | 0.53%   |
| Lenovo S20-30             | 1         | 0.53%   |
| Lenovo S10-3              | 1         | 0.53%   |
| Lenovo LEGION5PRO-16ACH6H | 1         | 0.53%   |
| Lenovo Legion             | 1         | 0.53%   |
| Lenovo G40-70             | 1         | 0.53%   |
| HUAWEI RLEF-XX            | 1         | 0.53%   |
| HP ZHAN                   | 1         | 0.53%   |
| HP Mini                   | 1         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2016 | 27        | 14.44%  |
| 2017 | 23        | 12.3%   |
| 2018 | 20        | 10.7%   |
| 2019 | 18        | 9.63%   |
| 2021 | 17        | 9.09%   |
| 2015 | 14        | 7.49%   |
| 2014 | 14        | 7.49%   |
| 2020 | 12        | 6.42%   |
| 2012 | 12        | 6.42%   |
| 2013 | 9         | 4.81%   |
| 2011 | 8         | 4.28%   |
| 2010 | 5         | 2.67%   |
| 2022 | 4         | 2.14%   |
| 2009 | 3         | 1.6%    |
| 2008 | 1         | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 187       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 169       | 88.48%  |
| Enabled  | 22        | 11.52%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 187       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 75        | 39.47%  |
| 3.01-4.0    | 49        | 25.79%  |
| 8.01-16.0   | 37        | 19.47%  |
| 16.01-24.0  | 19        | 10%     |
| 1.01-2.0    | 6         | 3.16%   |
| 2.01-3.0    | 2         | 1.05%   |
| 32.01-64.0  | 1         | 0.53%   |
| 64.01-256.0 | 1         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 71        | 33.97%  |
| 2.01-3.0  | 66        | 31.58%  |
| 3.01-4.0  | 39        | 18.66%  |
| 4.01-8.0  | 21        | 10.05%  |
| 0.51-1.0  | 9         | 4.31%   |
| 8.01-16.0 | 2         | 0.96%   |
| 0.01-0.5  | 1         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 128       | 67.37%  |
| 2      | 59        | 31.05%  |
| 3      | 3         | 1.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 129       | 68.62%  |
| Yes       | 59        | 31.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 142       | 75.13%  |
| No        | 47        | 24.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 184       | 98.4%   |
| No        | 3         | 1.6%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 159       | 83.68%  |
| No        | 31        | 16.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Bangladesh | 187       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dhaka             | 116       | 58.88%  |
| Chittagong        | 12        | 6.09%   |
| Rajshahi          | 8         | 4.06%   |
| Jessore           | 6         | 3.05%   |
| Tongi             | 5         | 2.54%   |
| Khulna            | 5         | 2.54%   |
| Narayanganj       | 4         | 2.03%   |
| Sylhet            | 3         | 1.52%   |
| Mirpur            | 3         | 1.52%   |
| Comilla           | 3         | 1.52%   |
| Wari              | 2         | 1.02%   |
| Sherpur           | 2         | 1.02%   |
| Savar Upazila     | 2         | 1.02%   |
| Narail            | 2         | 1.02%   |
| Azimpur           | 2         | 1.02%   |
| Tejgaon           | 1         | 0.51%   |
| Srimangal         | 1         | 0.51%   |
| Sirajganj         | 1         | 0.51%   |
| Rangpur City      | 1         | 0.51%   |
| Pirganj           | 1         | 0.51%   |
| Paltan            | 1         | 0.51%   |
| Pabna Sadar       | 1         | 0.51%   |
| Pabna             | 1         | 0.51%   |
| NДЃrДЃyanganj | 1         | 0.51%   |
| Nilphamari        | 1         | 0.51%   |
| Natore            | 1         | 0.51%   |
| Nalitabari        | 1         | 0.51%   |
| LДЃkshДЃm     | 1         | 0.51%   |
| Khilgaon          | 1         | 0.51%   |
| Jamalpur          | 1         | 0.51%   |
| Habiganj          | 1         | 0.51%   |
| Gulshan           | 1         | 0.51%   |
| Faridpur          | 1         | 0.51%   |
| Dhunot            | 1         | 0.51%   |
| Dewangonj         | 1         | 0.51%   |
| Bogra             | 1         | 0.51%   |
| Belkuchi          | 1         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate                        | 44        | 56     | 17.96%  |
| WDC                            | 43        | 57     | 17.55%  |
| Toshiba                        | 33        | 42     | 13.47%  |
| Samsung Electronics            | 13        | 19     | 5.31%   |
| Transcend                      | 12        | 13     | 4.9%    |
| HGST                           | 11        | 11     | 4.49%   |
| SanDisk                        | 9         | 9      | 3.67%   |
| Intel                          | 9         | 11     | 3.67%   |
| Hitachi                        | 8         | 10     | 3.27%   |
| Micron Technology              | 7         | 7      | 2.86%   |
| Kingston                       | 7         | 9      | 2.86%   |
| A-DATA Technology              | 6         | 6      | 2.45%   |
| SK hynix                       | 4         | 4      | 1.63%   |
| Silicon Motion                 | 4         | 9      | 1.63%   |
| Corsair                        | 3         | 5      | 1.22%   |
| Ramsta                         | 2         | 2      | 0.82%   |
| KingSpec                       | 2         | 2      | 0.82%   |
| Crucial                        | 2         | 3      | 0.82%   |
| Apacer                         | 2         | 3      | 0.82%   |
| WDC WDS4                       | 1         | 1      | 0.41%   |
| WALTON                         | 1         | 2      | 0.41%   |
| Unknown                        | 1         | 1      | 0.41%   |
| Teutons                        | 1         | 1      | 0.41%   |
| Team                           | 1         | 1      | 0.41%   |
| Solid State Storage Technology | 1         | 1      | 0.41%   |
| Shenzhen Longsys Electronics   | 1         | 1      | 0.41%   |
| Realtek Semiconductor          | 1         | 1      | 0.41%   |
| Realtek                        | 1         | 1      | 0.41%   |
| PNY                            | 1         | 1      | 0.41%   |
| Phison                         | 1         | 1      | 0.41%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 0.41%   |
| Lexar                          | 1         | 2      | 0.41%   |
| KIOXIA                         | 1         | 1      | 0.41%   |
| Kingsand                       | 1         | 1      | 0.41%   |
| HS-SSD-E100                    | 1         | 1      | 0.41%   |
| Hewlett-Packard                | 1         | 1      | 0.41%   |
| Gigabyte Technology            | 1         | 1      | 0.41%   |
| GeIL                           | 1         | 1      | 0.41%   |
| Colorful                       | 1         | 1      | 0.41%   |
| China                          | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                       | 18        | 7.2%    |
| Toshiba MQ04ABF100 1TB                               | 15        | 6%      |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 6         | 2.4%    |
| WDC WD10JPVX-60JC3T0 1TB                             | 5         | 2%      |
| Seagate ST500LT012-1DG142 500GB                      | 5         | 2%      |
| WDC WDS120G2G0A-00JH30 120GB SSD                     | 4         | 1.6%    |
| WDC WD10SPZX-60Z10T0 1TB                             | 4         | 1.6%    |
| Toshiba MQ01ABD100 1TB                               | 4         | 1.6%    |
| HGST HTS541010A9E680 1TB                             | 4         | 1.6%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD                     | 3         | 1.2%    |
| Transcend TS120GMTS420S 120GB SSD                    | 3         | 1.2%    |
| Silicon Motion SM2262/SM2262EN SSD Controller 1024GB | 3         | 1.2%    |
| Seagate ST500LT012-9WS142 500GB                      | 3         | 1.2%    |
| Seagate ST1000LM049-2GH172 1TB                       | 3         | 1.2%    |
| SanDisk NVMe SSD Drive 512GB                         | 3         | 1.2%    |
| Samsung SSD 860 EVO 500GB                            | 3         | 1.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB  | 3         | 1.2%    |
| Intel SSD 660P Series 512GB                          | 3         | 1.2%    |
| Intel NVMe SSD Drive 512GB                           | 3         | 1.2%    |
| HGST HTS545050A7E680 500GB                           | 3         | 1.2%    |
| A-DATA SU650 240GB SSD                               | 3         | 1.2%    |
| WDC WD10SPZX-24Z10T0 1TB                             | 2         | 0.8%    |
| WDC WD10JPVX-75JC3T0 1TB                             | 2         | 0.8%    |
| WDC WD10JPVX-60JC3T1 1TB                             | 2         | 0.8%    |
| WDC PC SN520 SDAPNUW-256G-1002 256GB                 | 2         | 0.8%    |
| Transcend TS256GSSD230S 256GB                        | 2         | 0.8%    |
| Transcend TS240GMTS820S 240GB SSD                    | 2         | 0.8%    |
| Toshiba THNSNK128GVN8 128GB SSD                      | 2         | 0.8%    |
| Toshiba MQ01ACF050 500GB                             | 2         | 0.8%    |
| Seagate ST9500325AS 500GB                            | 2         | 0.8%    |
| Ramsta SSD R800 120GB                                | 2         | 0.8%    |
| Micron MTFDDAV512TBN-1AR1ZABHA 512GB SSD             | 2         | 0.8%    |
| Micron 1100_MTFDDAV256TBN 256GB SSD                  | 2         | 0.8%    |
| Kingston OM8PCP3512F-AI1 512GB                       | 2         | 0.8%    |
| Hitachi HTS547550A9E384 500GB                        | 2         | 0.8%    |
| Hitachi HTS543232A7A384 320GB                        | 2         | 0.8%    |
| HGST HTS541010B7E610 1TB                             | 2         | 0.8%    |
| Corsair Force MP510 240GB                            | 2         | 0.8%    |
| WDC WDS4 80G2G0B-00EPW0 480GB SSD                    | 1         | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 44        | 56     | 37.61%  |
| WDC     | 27        | 36     | 23.08%  |
| Toshiba | 27        | 35     | 23.08%  |
| HGST    | 11        | 11     | 9.4%    |
| Hitachi | 8         | 10     | 6.84%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 14     | 15.71%  |
| Transcend           | 11        | 12     | 15.71%  |
| Samsung Electronics | 7         | 10     | 10%     |
| Micron Technology   | 6         | 6      | 8.57%   |
| A-DATA Technology   | 6         | 6      | 8.57%   |
| SanDisk             | 5         | 5      | 7.14%   |
| Toshiba             | 2         | 3      | 2.86%   |
| Ramsta              | 2         | 2      | 2.86%   |
| KingSpec            | 2         | 2      | 2.86%   |
| Crucial             | 2         | 3      | 2.86%   |
| Apacer              | 2         | 3      | 2.86%   |
| WDC WDS4            | 1         | 1      | 1.43%   |
| WALTON              | 1         | 2      | 1.43%   |
| Teutons             | 1         | 1      | 1.43%   |
| SK hynix            | 1         | 1      | 1.43%   |
| PNY                 | 1         | 1      | 1.43%   |
| Kingston            | 1         | 1      | 1.43%   |
| Intel               | 1         | 1      | 1.43%   |
| HS-SSD-E100         | 1         | 1      | 1.43%   |
| Hewlett-Packard     | 1         | 1      | 1.43%   |
| Gigabyte Technology | 1         | 1      | 1.43%   |
| GeIL                | 1         | 1      | 1.43%   |
| Corsair             | 1         | 2      | 1.43%   |
| China               | 1         | 1      | 1.43%   |
| ASMT                | 1         | 1      | 1.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 117       | 148    | 49.37%  |
| SSD     | 67        | 82     | 28.27%  |
| NVMe    | 48        | 69     | 20.25%  |
| Unknown | 5         | 5      | 2.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 153       | 231    | 74.27%  |
| NVMe | 48        | 68     | 23.3%   |
| SAS  | 5         | 5      | 2.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 91        | 118    | 51.41%  |
| 0.51-1.0   | 82        | 107    | 46.33%  |
| 1.01-2.0   | 3         | 4      | 1.69%   |
| 4.01-10.0  | 1         | 1      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 52        | 26.13%  |
| 251-500        | 51        | 25.63%  |
| 501-1000       | 39        | 19.6%   |
| 51-100         | 17        | 8.54%   |
| 1001-2000      | 15        | 7.54%   |
| 1-20           | 10        | 5.03%   |
| 21-50          | 8         | 4.02%   |
| Unknown        | 4         | 2.01%   |
| More than 3000 | 3         | 1.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 68        | 32.69%  |
| 51-100         | 39        | 18.75%  |
| 101-250        | 37        | 17.79%  |
| 21-50          | 36        | 17.31%  |
| 251-500        | 13        | 6.25%   |
| 501-1000       | 8         | 3.85%   |
| Unknown        | 4         | 1.92%   |
| 1001-2000      | 2         | 0.96%   |
| More than 3000 | 1         | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                | Notebooks | Drives | Percent |
|------------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                               | 2         | 4      | 8.33%   |
| HGST HTS545050A7E680 500GB                           | 2         | 2      | 8.33%   |
| HGST HTS541010A9E680 1TB                             | 2         | 2      | 8.33%   |
| WDC WD5000LPCX-22VHAT0 500GB                         | 1         | 1      | 4.17%   |
| WDC WD5000BPVT-22HXZT3 500GB                         | 1         | 1      | 4.17%   |
| WDC WD10SPZX-24Z10T0 1TB                             | 1         | 1      | 4.17%   |
| WDC WD10JPVX-60JC3T0 1TB                             | 1         | 2      | 4.17%   |
| Toshiba MQ01ABD050 500GB                             | 1         | 1      | 4.17%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD                | 1         | 1      | 4.17%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 1024GB | 1         | 1      | 4.17%   |
| Seagate ST9500325AS 500GB                            | 1         | 1      | 4.17%   |
| Seagate ST500LT012-9WS142 500GB                      | 1         | 1      | 4.17%   |
| Seagate ST500LT012-1DG142 500GB                      | 1         | 1      | 4.17%   |
| Seagate ST320LT012-9WS14C 320GB                      | 1         | 1      | 4.17%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                   | 1         | 1      | 4.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 1         | 1      | 4.17%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD       | 1         | 1      | 4.17%   |
| Intel SSDSCKKW240H6 240GB                            | 1         | 1      | 4.17%   |
| Hitachi HTS545025B9A300 250GB                        | 1         | 1      | 4.17%   |
| HGST HTS545050A7E380 500GB                           | 1         | 1      | 4.17%   |
| Hewlett-Packard SSD S600 240GB                       | 1         | 1      | 4.17%   |

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
| Detected | 107       | 167    | 52.71%  |
| Works    | 72        | 110    | 35.47%  |
| Malfunc  | 24        | 27     | 11.82%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 158       | 72.81%  |
| AMD                            | 15        | 6.91%   |
| SanDisk                        | 9         | 4.15%   |
| Samsung Electronics            | 6         | 2.76%   |
| Kingston Technology Company    | 6         | 2.76%   |
| Silicon Motion                 | 4         | 1.84%   |
| SK hynix                       | 3         | 1.38%   |
| Shenzhen Longsys Electronics   | 3         | 1.38%   |
| Phison Electronics             | 3         | 1.38%   |
| KIOXIA                         | 3         | 1.38%   |
| Toshiba America Info Systems   | 2         | 0.92%   |
| Solid State Storage Technology | 1         | 0.46%   |
| Realtek Semiconductor          | 1         | 0.46%   |
| Micron Technology              | 1         | 0.46%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.46%   |
| Biwin Storage Technology       | 1         | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 53        | 22.94%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 15        | 6.49%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 15        | 6.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 12        | 5.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 4.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 4.33%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 10        | 4.33%   |
| Intel Volume Management Device NVMe RAID Controller                              | 9         | 3.9%    |
| Intel SSD 660P Series                                                            | 6         | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 2.6%    |
| Intel Tiger Lake-LP SATA Controller                                              | 5         | 2.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 2.16%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                    | 4         | 1.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.73%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 3         | 1.3%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 1.3%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 1.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.3%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 3         | 1.3%    |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.3%    |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                                | 2         | 0.87%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.87%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 2         | 0.87%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 0.87%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.87%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 0.87%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 1         | 0.43%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.43%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                   | 1         | 0.43%   |
| SK hynix PC611 NVMe Solid State Drive                                            | 1         | 0.43%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 0.43%   |
| SK hynix BC511 NVMe SSD                                                          | 1         | 0.43%   |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 0.43%   |
| Shenzhen Longsys Non-Volatile memory controller                                  | 1         | 0.43%   |
| SanDisk WD Green SN350 NVMe SSD 1 TB (DRAM-less)                                 | 1         | 0.43%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.43%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 0.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.43%   |
| Samsung NVMe SSD Controller PM9B1                                                | 1         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 150       | 66.67%  |
| NVMe | 48        | 21.33%  |
| RAID | 23        | 10.22%  |
| IDE  | 4         | 1.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 167       | 89.3%   |
| AMD    | 20        | 10.7%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 6.95%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 4.81%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 4.28%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 8         | 4.28%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 3.21%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 6         | 3.21%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 2.67%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 2.67%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.14%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 2.14%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 2.14%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 2.14%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 4         | 2.14%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 2.14%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 2.14%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 2.14%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 1.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.6%    |
| Intel Core i5-7300U CPU @ 2.60GHz             | 3         | 1.6%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.6%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 1.6%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 1.6%    |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 1.6%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.07%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.07%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.07%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 1.07%   |
| Intel Core i3-7130U CPU @ 2.70GHz             | 2         | 1.07%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.07%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.07%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 1.07%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz          | 2         | 1.07%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.07%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 2         | 1.07%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.07%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.53%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.53%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.53%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 76        | 40.64%  |
| Intel Core i3           | 42        | 22.46%  |
| Intel Core i7           | 17        | 9.09%   |
| Other                   | 15        | 8.02%   |
| AMD Ryzen 5             | 8         | 4.28%   |
| AMD Ryzen 7             | 6         | 3.21%   |
| Intel Pentium           | 5         | 2.67%   |
| Intel Celeron           | 5         | 2.67%   |
| Intel Core 2 Duo        | 3         | 1.6%    |
| Intel Atom              | 2         | 1.07%   |
| AMD Ryzen 3             | 2         | 1.07%   |
| Intel Pentium Dual-Core | 1         | 0.53%   |
| Intel Celeron Dual-Core | 1         | 0.53%   |
| AMD Ryzen 9             | 1         | 0.53%   |
| AMD E2                  | 1         | 0.53%   |
| AMD A8                  | 1         | 0.53%   |
| AMD A4                  | 1         | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 120       | 64.17%  |
| 4      | 52        | 27.81%  |
| 8      | 8         | 4.28%   |
| 6      | 6         | 3.21%   |
| 1      | 1         | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 187       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 168       | 89.36%  |
| 1      | 20        | 10.64%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 186       | 99.47%  |
| Unknown        | 1         | 0.53%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 53        | 27.04%  |
| 0x806e9    | 23        | 11.73%  |
| 0x806ea    | 15        | 7.65%   |
| 0x406e3    | 11        | 5.61%   |
| 0x40651    | 10        | 5.1%    |
| 0x306d4    | 9         | 4.59%   |
| 0x206a7    | 8         | 4.08%   |
| 0x806ec    | 7         | 3.57%   |
| 0x806c1    | 7         | 3.57%   |
| 0x306a9    | 7         | 3.57%   |
| 0x806eb    | 6         | 3.06%   |
| 0x706e5    | 5         | 2.55%   |
| 0x406c4    | 4         | 2.04%   |
| 0x1067a    | 3         | 1.53%   |
| 0x08108102 | 3         | 1.53%   |
| 0xa0652    | 2         | 1.02%   |
| 0x306c3    | 2         | 1.02%   |
| 0x20655    | 2         | 1.02%   |
| 0x0a50000c | 2         | 1.02%   |
| 0x08608103 | 2         | 1.02%   |
| 0x08108109 | 2         | 1.02%   |
| 0x906e9    | 1         | 0.51%   |
| 0x906a3    | 1         | 0.51%   |
| 0x806d1    | 1         | 0.51%   |
| 0x506e3    | 1         | 0.51%   |
| 0x406c3    | 1         | 0.51%   |
| 0x30678    | 1         | 0.51%   |
| 0x30661    | 1         | 0.51%   |
| 0x106ca    | 1         | 0.51%   |
| 0x10676    | 1         | 0.51%   |
| 0x0a50000d | 1         | 0.51%   |
| 0x08600104 | 1         | 0.51%   |
| 0x0810100b | 1         | 0.51%   |
| 0x06006705 | 1         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 66        | 35.29%  |
| Skylake          | 16        | 8.56%   |
| Haswell          | 14        | 7.49%   |
| TigerLake        | 12        | 6.42%   |
| Broadwell        | 12        | 6.42%   |
| IvyBridge        | 11        | 5.88%   |
| SandyBridge      | 10        | 5.35%   |
| Silvermont       | 7         | 3.74%   |
| Zen+             | 6         | 3.21%   |
| Icelake          | 6         | 3.21%   |
| Zen 3            | 5         | 2.67%   |
| Penryn           | 5         | 2.67%   |
| Unknown          | 3         | 1.6%    |
| Zen 2            | 2         | 1.07%   |
| Westmere         | 2         | 1.07%   |
| Excavator        | 2         | 1.07%   |
| CometLake        | 2         | 1.07%   |
| Bonnell          | 2         | 1.07%   |
| Alderlake Hybrid | 2         | 1.07%   |
| Zen              | 1         | 0.53%   |
| Puma             | 1         | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 166       | 70.34%  |
| Nvidia | 45        | 19.07%  |
| AMD    | 25        | 10.59%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 30        | 12.55%  |
| Intel UHD Graphics 620                                                                   | 15        | 6.28%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 6.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 5.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 5.02%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 4.6%    |
| Intel HD Graphics 5500                                                                   | 11        | 4.6%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 4.6%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 4.18%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 2.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.51%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 2.09%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 2.09%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 2.09%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 2.09%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 1.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.67%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 1.26%   |
| AMD Lucienne                                                                             | 3         | 1.26%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.84%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.84%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.84%   |
| Intel HD Graphics 630                                                                    | 2         | 0.84%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.84%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.84%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.84%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.84%   |
| AMD Renoir                                                                               | 2         | 0.84%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 0.84%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.42%   |
| Nvidia TU117M                                                                            | 1         | 0.42%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.42%   |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.42%   |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.42%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.42%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 123       | 65.78%  |
| Intel + Nvidia | 39        | 20.86%  |
| 1 x AMD        | 12        | 6.42%   |
| AMD + Nvidia   | 6         | 3.21%   |
| Intel + AMD    | 4         | 2.14%   |
| 2 x AMD        | 3         | 1.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 166       | 86.46%  |
| Proprietary | 24        | 12.5%   |
| Unknown     | 2         | 1.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 151       | 79.06%  |
| 1.01-2.0   | 21        | 10.99%  |
| 3.01-4.0   | 9         | 4.71%   |
| 0.01-0.5   | 6         | 3.14%   |
| 7.01-8.0   | 2         | 1.05%   |
| 5.01-6.0   | 1         | 0.52%   |
| 0.51-1.0   | 1         | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 50        | 24.15%  |
| AU Optronics            | 46        | 22.22%  |
| Chimei Innolux          | 36        | 17.39%  |
| LG Display              | 32        | 15.46%  |
| Samsung Electronics     | 14        | 6.76%   |
| Dell                    | 6         | 2.9%    |
| PANDA                   | 5         | 2.42%   |
| Hewlett-Packard         | 4         | 1.93%   |
| Goldstar                | 4         | 1.93%   |
| Chi Mei Optoelectronics | 3         | 1.45%   |
| ViewSonic               | 1         | 0.48%   |
| Sharp                   | 1         | 0.48%   |
| MSI                     | 1         | 0.48%   |
| ASUSTek Computer        | 1         | 0.48%   |
| Apple                   | 1         | 0.48%   |
| AOC                     | 1         | 0.48%   |
| Ancor Communications    | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 9         | 4.35%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 2.42%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 3         | 1.45%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 3         | 1.45%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 3         | 1.45%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 3         | 1.45%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 3         | 1.45%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 3         | 1.45%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch         | 2         | 0.97%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch             | 2         | 0.97%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch             | 2         | 0.97%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch              | 2         | 0.97%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch              | 2         | 0.97%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 2         | 0.97%   |
| LG Display LCD Monitor LGD0466 1366x768 309x174mm 14.0-inch              | 2         | 0.97%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch              | 2         | 0.97%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 2         | 0.97%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 2         | 0.97%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 2         | 0.97%   |
| BOE LCD Monitor BOE07B4 1366x768 344x194mm 15.5-inch                     | 2         | 0.97%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 2         | 0.97%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 2         | 0.97%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                     | 2         | 0.97%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.97%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 2         | 0.97%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 2         | 0.97%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 0.97%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 2         | 0.97%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch            | 1         | 0.48%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM043E 1600x1200 520x320mm 24.0-inch     | 1         | 0.48%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch        | 1         | 0.48%   |
| Samsung Electronics S19C300 SAM0A12 1366x768 410x230mm 18.5-inch         | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 1         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 96        | 48.73%  |
| 1920x1080 (FHD)   | 82        | 41.62%  |
| 1600x900 (HD+)    | 4         | 2.03%   |
| 3840x2160 (4K)    | 3         | 1.52%   |
| 2560x1600         | 2         | 1.02%   |
| 1920x1200 (WUXGA) | 2         | 1.02%   |
| 1280x800 (WXGA)   | 2         | 1.02%   |
| 1024x600          | 2         | 1.02%   |
| 3840x2400         | 1         | 0.51%   |
| 2560x1440 (QHD)   | 1         | 0.51%   |
| 2240x1400         | 1         | 0.51%   |
| 1280x1024 (SXGA)  | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 86        | 41.75%  |
| 13      | 43        | 20.87%  |
| 14      | 36        | 17.48%  |
| 21      | 10        | 4.85%   |
| 18      | 8         | 3.88%   |
| 12      | 6         | 2.91%   |
| 16      | 3         | 1.46%   |
| 11      | 3         | 1.46%   |
| 23      | 2         | 0.97%   |
| 17      | 2         | 0.97%   |
| 10      | 2         | 0.97%   |
| 27      | 1         | 0.49%   |
| 26      | 1         | 0.49%   |
| 24      | 1         | 0.49%   |
| 19      | 1         | 0.49%   |
| Unknown | 1         | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 158       | 77.07%  |
| 401-500     | 20        | 9.76%   |
| 201-300     | 20        | 9.76%   |
| 501-600     | 4         | 1.95%   |
| 351-400     | 2         | 0.98%   |
| Unknown     | 1         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 176       | 95.14%  |
| 16/10 | 8         | 4.32%   |
| 5/4   | 1         | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 86        | 41.95%  |
| 81-90          | 70        | 34.15%  |
| 141-150        | 9         | 4.39%   |
| 71-80          | 8         | 3.9%    |
| 201-250        | 8         | 3.9%    |
| 61-70          | 6         | 2.93%   |
| 151-200        | 4         | 1.95%   |
| 51-60          | 3         | 1.46%   |
| 111-120        | 3         | 1.46%   |
| 41-50          | 2         | 0.98%   |
| 251-300        | 2         | 0.98%   |
| 301-350        | 1         | 0.49%   |
| 121-130        | 1         | 0.49%   |
| 91-100         | 1         | 0.49%   |
| Unknown        | 1         | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 89        | 44.72%  |
| 121-160       | 84        | 42.21%  |
| 51-100        | 16        | 8.04%   |
| 161-240       | 7         | 3.52%   |
| More than 240 | 2         | 1.01%   |
| Unknown       | 1         | 0.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 166       | 87.37%  |
| 2     | 22        | 11.58%  |
| 3     | 1         | 0.53%   |
| 0     | 1         | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 121       | 41.44%  |
| Intel                 | 90        | 30.82%  |
| Qualcomm Atheros      | 54        | 18.49%  |
| Broadcom              | 7         | 2.4%    |
| MediaTek              | 6         | 2.05%   |
| Ralink Technology     | 4         | 1.37%   |
| Xiaomi                | 3         | 1.03%   |
| TP-Link               | 1         | 0.34%   |
| Samsung Electronics   | 1         | 0.34%   |
| Ralink                | 1         | 0.34%   |
| OPPO Electronics      | 1         | 0.34%   |
| Dell                  | 1         | 0.34%   |
| ASIX Electronics      | 1         | 0.34%   |
| Arduino SA            | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 75        | 22.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 8.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 22        | 6.53%   |
| Intel Wireless 8265 / 8275                                        | 16        | 4.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 13        | 3.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 3.56%   |
| Intel Wi-Fi 6 AX201                                               | 11        | 3.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 9         | 2.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 8         | 2.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 2.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.08%   |
| Intel Wireless 3165                                               | 6         | 1.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.48%   |
| Intel Wireless 8260                                               | 5         | 1.48%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.19%   |
| Intel Wireless 7265                                               | 4         | 1.19%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.89%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 0.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.89%   |
| Intel Wireless 7260                                               | 3         | 0.89%   |
| Intel Wireless 3160                                               | 3         | 0.89%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.89%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.59%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.59%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.59%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.59%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.59%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 2         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 87        | 45.55%  |
| Qualcomm Atheros      | 52        | 27.23%  |
| Realtek Semiconductor | 34        | 17.8%   |
| MediaTek              | 6         | 3.14%   |
| Broadcom              | 5         | 2.62%   |
| Ralink Technology     | 4         | 2.09%   |
| TP-Link               | 1         | 0.52%   |
| Ralink                | 1         | 0.52%   |
| Dell                  | 1         | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 22        | 11.52%  |
| Intel Wireless 8265 / 8275                                     | 16        | 8.38%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 13        | 6.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 6.28%   |
| Intel Wi-Fi 6 AX201                                            | 11        | 5.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 9         | 4.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 8         | 4.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 3.66%   |
| Intel Wireless 3165                                            | 6         | 3.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 2.62%   |
| Intel Wireless 8260                                            | 5         | 2.62%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 2.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.09%   |
| Intel Wireless 7265                                            | 4         | 2.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 1.57%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 1.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.57%   |
| Intel Wireless 7260                                            | 3         | 1.57%   |
| Intel Wireless 3160                                            | 3         | 1.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 1.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 1.57%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.57%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.05%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 1.05%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.05%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.52%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.52%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.52%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.52%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.52%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 0.52%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 108       | 75%     |
| Intel                 | 21        | 14.58%  |
| Qualcomm Atheros      | 6         | 4.17%   |
| Xiaomi                | 3         | 2.08%   |
| Broadcom              | 3         | 2.08%   |
| Samsung Electronics   | 1         | 0.69%   |
| OPPO Electronics      | 1         | 0.69%   |
| ASIX Electronics      | 1         | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 75        | 51.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 20%     |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 4.83%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 2.76%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.07%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.07%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.38%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 1.38%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.38%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.69%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.69%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.69%   |
| OPPO OnePlus Nord                                                 | 1         | 0.69%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.69%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 184       | 56.44%  |
| Ethernet | 141       | 43.25%  |
| Modem    | 1         | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 161       | 84.74%  |
| Ethernet | 29        | 15.26%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 130       | 69.52%  |
| 1     | 56        | 29.95%  |
| 3     | 1         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 186       | 99.47%  |
| Yes  | 1         | 0.53%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 73        | 45.63%  |
| IMC Networks                    | 25        | 15.63%  |
| Realtek Semiconductor           | 18        | 11.25%  |
| Qualcomm Atheros Communications | 14        | 8.75%   |
| Lite-On Technology              | 11        | 6.88%   |
| Broadcom                        | 7         | 4.38%   |
| Foxconn / Hon Hai               | 4         | 2.5%    |
| MediaTek                        | 2         | 1.25%   |
| Toshiba                         | 1         | 0.63%   |
| Ralink                          | 1         | 0.63%   |
| Hewlett-Packard                 | 1         | 0.63%   |
| Foxconn International           | 1         | 0.63%   |
| Dell                            | 1         | 0.63%   |
| Cambridge Silicon Radio         | 1         | 0.63%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 37        | 23.13%  |
| IMC Networks Bluetooth Device                       | 14        | 8.75%   |
| Intel AX201 Bluetooth                               | 13        | 8.13%   |
| Realtek Bluetooth Radio                             | 12        | 7.5%    |
| Intel Bluetooth Device                              | 11        | 6.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 5%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 5%      |
| IMC Networks Bluetooth Radio                        | 8         | 5%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 7         | 4.38%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.88%   |
| Lite-On Bluetooth Device                            | 3         | 1.88%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 1.25%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.25%   |
| MediaTek Wireless_Device                            | 2         | 1.25%   |
| Intel AX200 Bluetooth                               | 2         | 1.25%   |
| IMC Networks Wireless_Device                        | 2         | 1.25%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.25%   |
| Broadcom HP Portable SoftSailing                    | 2         | 1.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.25%   |
| Toshiba Bluetooth Radio                             | 1         | 0.63%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.63%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.63%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.63%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.63%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.63%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.63%   |
| Intel AX210 Bluetooth                               | 1         | 0.63%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.63%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.63%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.63%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 0.63%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.63%   |
| Dell Wireless 360 Bluetooth                         | 1         | 0.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.63%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.63%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.63%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 166       | 85.13%  |
| AMD                    | 20        | 10.26%  |
| Nvidia                 | 8         | 4.1%    |
| Generalplus Technology | 1         | 0.51%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 60        | 25.1%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 7.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 14        | 5.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 5.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 5.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 5.02%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 5.02%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 5.02%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 5.02%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 3.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 2.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.51%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 2.09%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 2.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 2.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 0.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.84%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.84%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.84%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.84%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 0.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 0.84%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.84%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.84%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.42%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.42%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.42%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.42%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.42%   |
| Intel USB PnP Sound Device                                                                        | 1         | 0.42%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.42%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.42%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.42%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.42%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 29.5%   |
| SK hynix            | 34        | 24.46%  |
| Micron Technology   | 19        | 13.67%  |
| A-DATA Technology   | 8         | 5.76%   |
| Kingston            | 6         | 4.32%   |
| Unknown             | 5         | 3.6%    |
| G.Skill             | 5         | 3.6%    |
| Transcend           | 4         | 2.88%   |
| Team                | 3         | 2.16%   |
| Ramaxel Technology  | 2         | 1.44%   |
| Nanya Technology    | 2         | 1.44%   |
| Crucial             | 2         | 1.44%   |
| Unknown (C509)      | 1         | 0.72%   |
| Unknown (768A)      | 1         | 0.72%   |
| Toshiba             | 1         | 0.72%   |
| Hewlett-Packard     | 1         | 0.72%   |
| Elpida              | 1         | 0.72%   |
| ASint Technology    | 1         | 0.72%   |
| Apacer              | 1         | 0.72%   |
| Unknown             | 1         | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 6         | 4.26%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 5         | 3.55%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 4         | 2.84%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 3         | 2.13%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s    | 3         | 2.13%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 2.13%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 1.42%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 2         | 1.42%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 1.42%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 1.42%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.42%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.42%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 2         | 1.42%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 2         | 1.42%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s     | 2         | 1.42%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s    | 2         | 1.42%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s     | 2         | 1.42%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 1.42%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 2         | 1.42%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s      | 2         | 1.42%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s      | 2         | 1.42%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s     | 2         | 1.42%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s     | 2         | 1.42%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s    | 2         | 1.42%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s               | 1         | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s               | 1         | 0.71%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.71%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 0.71%   |
| Unknown RAM Module 2048MB Row Of Chips LPDDR4 4267MT/s    | 1         | 0.71%   |
| Unknown (C509) RAM Module 4GB SODIMM DDR4 2400MT/s        | 1         | 0.71%   |
| Unknown (768A) RAM Module 8192MB SODIMM DDR4 3200MT/s     | 1         | 0.71%   |
| Transcend RAM JM3200HSB-8G 8GB SODIMM DDR4 3200MT/s       | 1         | 0.71%   |
| Transcend RAM JM2666HSG-8G 8GB SODIMM DDR4 2667MT/s       | 1         | 0.71%   |
| Transcend RAM JM2400HSB-8G 8GB SODIMM DDR4 2400MT/s       | 1         | 0.71%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s       | 1         | 0.71%   |
| Toshiba RAM 8HTF12864HDY-800G1 2048MB SODIMM 1066MT/s     | 1         | 0.71%   |
| Toshiba RAM 64T128020EDL2.5C2 2048MB SODIMM 1066MT/s      | 1         | 0.71%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s      | 1         | 0.71%   |
| Team RAM TEAMGROUP-SD4-3200 8192MB SODIMM DDR4 3200MT/s   | 1         | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 69        | 66.35%  |
| DDR3   | 26        | 25%     |
| LPDDR4 | 5         | 4.81%   |
| LPDDR3 | 2         | 1.92%   |
| SDRAM  | 1         | 0.96%   |
| DDR2   | 1         | 0.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 96        | 95.05%  |
| Row Of Chips | 5         | 4.95%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 55        | 47.01%  |
| 4096  | 41        | 35.04%  |
| 16384 | 9         | 7.69%   |
| 2048  | 7         | 5.98%   |
| 32768 | 4         | 3.42%   |
| 1024  | 1         | 0.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 33        | 29.2%   |
| 3200  | 22        | 19.47%  |
| 1600  | 19        | 16.81%  |
| 2400  | 12        | 10.62%  |
| 2133  | 10        | 8.85%   |
| 1067  | 4         | 3.54%   |
| 1334  | 3         | 2.65%   |
| 3266  | 2         | 1.77%   |
| 1333  | 2         | 1.77%   |
| 8400  | 1         | 0.88%   |
| 4267  | 1         | 0.88%   |
| 4199  | 1         | 0.88%   |
| 2134  | 1         | 0.88%   |
| 1867  | 1         | 0.88%   |
| 1066  | 1         | 0.88%   |

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
| Chicony Electronics                    | 38        | 22.22%  |
| IMC Networks                           | 34        | 19.88%  |
| Cheng Uei Precision Industry (Foxlink) | 16        | 9.36%   |
| Realtek Semiconductor                  | 12        | 7.02%   |
| Quanta                                 | 11        | 6.43%   |
| Microdia                               | 11        | 6.43%   |
| Sunplus Innovation Technology          | 10        | 5.85%   |
| Bison Electronics                      | 10        | 5.85%   |
| Lite-On Technology                     | 7         | 4.09%   |
| Suyin                                  | 5         | 2.92%   |
| Luxvisions Innotech Limited            | 5         | 2.92%   |
| Syntek                                 | 2         | 1.17%   |
| Sonix Technology                       | 2         | 1.17%   |
| Silicon Motion                         | 2         | 1.17%   |
| Primax Electronics                     | 2         | 1.17%   |
| Acer                                   | 2         | 1.17%   |
| Importek                               | 1         | 0.58%   |
| Apple                                  | 1         | 0.58%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 12        | 7.02%   |
| Chicony USB2.0 VGA UVC WebCam                           | 11        | 6.43%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 9         | 5.26%   |
| Microdia Integrated_Webcam_HD                           | 5         | 2.92%   |
| IMC Networks VGA UVC WebCam                             | 5         | 2.92%   |
| Chicony HD WebCam                                       | 5         | 2.92%   |
| Luxvisions Innotech Limited HP HD Camera                | 4         | 2.34%   |
| Lite-On HP HD Camera                                    | 4         | 2.34%   |
| IMC Networks Integrated Camera                          | 4         | 2.34%   |
| Suyin Integrated_Webcam_HD                              | 3         | 1.75%   |
| Realtek Integrated_Webcam_HD                            | 3         | 1.75%   |
| Quanta HD Webcam                                        | 3         | 1.75%   |
| IMC Networks USB2.0 HD IR UVC WebCam                    | 3         | 1.75%   |
| Chicony EasyCamera                                      | 3         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 3         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 1.75%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 3         | 1.75%   |
| Bison Integrated Camera                                 | 3         | 1.75%   |
| Bison HD Webcam                                         | 3         | 1.75%   |
| Suyin HP Truevision HD                                  | 2         | 1.17%   |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 1.17%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.17%   |
| Realtek USB2.0 VGA UVC WebCam                           | 2         | 1.17%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.17%   |
| Quanta HP HD Camera                                     | 2         | 1.17%   |
| Quanta HD User Facing                                   | 2         | 1.17%   |
| Primax HP HD Webcam [Fixed]                             | 2         | 1.17%   |
| Microdia HP Integrated Webcam                           | 2         | 1.17%   |
| Lite-On Integrated Camera                               | 2         | 1.17%   |
| Chicony USB2.0 Camera                                   | 2         | 1.17%   |
| Chicony Integrated Camera                               | 2         | 1.17%   |
| Chicony HP Truevision HD camera                         | 2         | 1.17%   |
| Chicony HP HD Webcam                                    | 2         | 1.17%   |
| Chicony HP HD Camera                                    | 2         | 1.17%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.17%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 2         | 1.17%   |
| Bison Lenovo EasyCamera                                 | 2         | 1.17%   |
| Bison EasyCamera                                        | 2         | 1.17%   |
| Syntek Integrated Camera                                | 1         | 0.58%   |
| Syntek EasyCamera                                       | 1         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 26        | 78.79%  |
| Synaptics                  | 3         | 9.09%   |
| Elan Microelectronics      | 2         | 6.06%   |
| Upek                       | 1         | 3.03%   |
| Shenzhen Goodix Technology | 1         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 42.42%  |
| Validity Sensors VFS491                                                    | 4         | 12.12%  |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 9.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 6.06%   |
| Elan ELAN:Fingerprint                                                      | 2         | 6.06%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 3.03%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.03%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.03%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 3.03%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.03%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 3.03%   |
| Synaptics  WBDI                                                            | 1         | 3.03%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 3.03%   |

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
| 0     | 131       | 66.84%  |
| 1     | 57        | 29.08%  |
| 2     | 6         | 3.06%   |
| 5     | 1         | 0.51%   |
| 3     | 1         | 0.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 33        | 44.59%  |
| Graphics card         | 18        | 24.32%  |
| Chipcard              | 6         | 8.11%   |
| Net/wireless          | 5         | 6.76%   |
| Camera                | 5         | 6.76%   |
| Multimedia controller | 3         | 4.05%   |
| Bluetooth             | 2         | 2.7%    |
| Sound                 | 1         | 1.35%   |
| Card reader           | 1         | 1.35%   |

