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

Total: 293

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion g7                 | [b3dc228560](https://linux-hardware.org/?probe=b3dc228560) | Nov 02, 2023 |
| Apple         | MacBookPro7,1               | [cb27a04bd5](https://linux-hardware.org/?probe=cb27a04bd5) | Oct 26, 2023 |
| ASUSTek       | X442UAR                     | [454f454638](https://linux-hardware.org/?probe=454f454638) | Oct 21, 2023 |
| ASUSTek       | X450LCP                     | [ae3fec47c6](https://linux-hardware.org/?probe=ae3fec47c6) | Oct 19, 2023 |
| HP            | Laptop 15-da0xxx            | [cb3ee2550b](https://linux-hardware.org/?probe=cb3ee2550b) | Oct 17, 2023 |
| HP            | Laptop 15-da0xxx            | [e57363450f](https://linux-hardware.org/?probe=e57363450f) | Oct 17, 2023 |
| HP            | ProBook 450 G3              | [53c0055ced](https://linux-hardware.org/?probe=53c0055ced) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c63ae3378d](https://linux-hardware.org/?probe=c63ae3378d) | Sep 22, 2023 |
| Dell          | Inspiron 15-3567            | [0f189d3c2a](https://linux-hardware.org/?probe=0f189d3c2a) | Sep 21, 2023 |
| Acer          | TravelMate P246-MG          | [197b2c18c7](https://linux-hardware.org/?probe=197b2c18c7) | Sep 21, 2023 |
| HUAWEI        | RLEF-XX                     | [1e8bb82a4a](https://linux-hardware.org/?probe=1e8bb82a4a) | Sep 16, 2023 |
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
| Ubuntu 20.04                 | 35        | 15.91%  |
| ArcoLinux Rolling            | 10        | 4.55%   |
| Arch                         | 9         | 4.09%   |
| Ubuntu 22.04                 | 7         | 3.18%   |
| Arch Rolling                 | 7         | 3.18%   |
| Pop!_OS 22.04                | 6         | 2.73%   |
| Manjaro                      | 6         | 2.73%   |
| KDE neon 20.04               | 6         | 2.73%   |
| Zorin 16                     | 5         | 2.27%   |
| Ubuntu 19.10                 | 4         | 1.82%   |
| Ubuntu 18.04                 | 4         | 1.82%   |
| Fedora 38                    | 4         | 1.82%   |
| Fedora 33                    | 4         | 1.82%   |
| EndeavourOS Rolling          | 4         | 1.82%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 1.36%   |
| OpenMandriva 4.2             | 3         | 1.36%   |
| Manjaro 20.0.1               | 3         | 1.36%   |
| Fedora 37                    | 3         | 1.36%   |
| Debian 11                    | 3         | 1.36%   |
| Zorin 15                     | 2         | 0.91%   |
| Ubuntu 23.04                 | 2         | 0.91%   |
| Ubuntu 22.10                 | 2         | 0.91%   |
| Ubuntu 19.04                 | 2         | 0.91%   |
| Ubuntu 18.10                 | 2         | 0.91%   |
| Pop!_OS 21.10                | 2         | 0.91%   |
| OpenMandriva 4.90            | 2         | 0.91%   |
| OpenMandriva 4.3             | 2         | 0.91%   |
| MX 21                        | 2         | 0.91%   |
| Manjaro 21.2.6               | 2         | 0.91%   |
| Manjaro 18.0.4               | 2         | 0.91%   |
| Linux Mint 20.1              | 2         | 0.91%   |
| Linux Mint 20                | 2         | 0.91%   |
| Kubuntu 20.04                | 2         | 0.91%   |
| KDE neon 22.04               | 2         | 0.91%   |
| Kali 2023.3                  | 2         | 0.91%   |
| Kali 2022.4                  | 2         | 0.91%   |
| Kali 2022.3                  | 2         | 0.91%   |
| Fedora 34                    | 2         | 0.91%   |
| Debian 12                    | 2         | 0.91%   |
| Ubuntu Unity 16.04           | 1         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 58        | 28.43%  |
| Manjaro      | 19        | 9.31%   |
| Arch         | 15        | 7.35%   |
| Fedora       | 13        | 6.37%   |
| Pop!_OS      | 10        | 4.9%    |
| ArcoLinux    | 10        | 4.9%    |
| Linux Mint   | 9         | 4.41%   |
| KDE neon     | 8         | 3.92%   |
| Zorin        | 7         | 3.43%   |
| OpenMandriva | 7         | 3.43%   |
| Kubuntu      | 7         | 3.43%   |
| Debian       | 7         | 3.43%   |
| Kali         | 6         | 2.94%   |
| Endless      | 5         | 2.45%   |
| EndeavourOS  | 5         | 2.45%   |
| Parrot       | 3         | 1.47%   |
| openSUSE     | 3         | 1.47%   |
| MX           | 2         | 0.98%   |
| Artix        | 2         | 0.98%   |
| Ubuntu Unity | 1         | 0.49%   |
| Lubuntu      | 1         | 0.49%   |
| LMDE         | 1         | 0.49%   |
| Devuan       | 1         | 0.49%   |
| Deepin       | 1         | 0.49%   |
| Clear Linux  | 1         | 0.49%   |
| CentOS       | 1         | 0.49%   |
| BlackPanther | 1         | 0.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 7         | 2.93%   |
| 5.4.0-52-generic         | 3         | 1.26%   |
| 5.4.0-40-generic         | 3         | 1.26%   |
| 5.4.0-29-generic         | 3         | 1.26%   |
| 5.10.14-desktop-1omv4002 | 3         | 1.26%   |
| 6.2.9-300.fc38.x86_64    | 2         | 0.84%   |
| 6.2.0-32-generic         | 2         | 0.84%   |
| 6.0.9-zen1-1-zen         | 2         | 0.84%   |
| 6.0.0-kali6-amd64        | 2         | 0.84%   |
| 5.9.16-1-MANJARO         | 2         | 0.84%   |
| 5.8.0-50-generic         | 2         | 0.84%   |
| 5.8.0-41-generic         | 2         | 0.84%   |
| 5.8.0-14-generic         | 2         | 0.84%   |
| 5.7.19-2-MANJARO         | 2         | 0.84%   |
| 5.6.11-1-MANJARO         | 2         | 0.84%   |
| 5.4.8-arch1-1            | 2         | 0.84%   |
| 5.4.0-53-generic         | 2         | 0.84%   |
| 5.4.0-19-generic         | 2         | 0.84%   |
| 5.3.0-24-generic         | 2         | 0.84%   |
| 5.3.0-23-generic         | 2         | 0.84%   |
| 5.19.0-kali2-amd64       | 2         | 0.84%   |
| 5.19.0-35-generic        | 2         | 0.84%   |
| 5.19.0-29-generic        | 2         | 0.84%   |
| 5.18.12-desktop-3omv4090 | 2         | 0.84%   |
| 5.15.0-53-generic        | 2         | 0.84%   |
| 5.15.0-52-generic        | 2         | 0.84%   |
| 5.15.0-48-generic        | 2         | 0.84%   |
| 5.15.0-46-generic        | 2         | 0.84%   |
| 5.13.0-28-generic        | 2         | 0.84%   |
| 5.11.0-40-generic        | 2         | 0.84%   |
| 5.11.0-27-generic        | 2         | 0.84%   |
| 5.10.52-1-lts            | 2         | 0.84%   |
| 5.10.0-13-amd64          | 2         | 0.84%   |
| 6.5.7-200.fc38.x86_64    | 1         | 0.42%   |
| 6.5.2-arch1-1            | 1         | 0.42%   |
| 6.5.0-kali3-amd64        | 1         | 0.42%   |
| 6.5.0-kali2-amd64        | 1         | 0.42%   |
| 6.5.0-9-generic          | 1         | 0.42%   |
| 6.5.0-1-MANJARO          | 1         | 0.42%   |
| 6.4.0-1-amd64            | 1         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 28        | 12.28%  |
| 5.15.0  | 16        | 7.02%   |
| 5.8.0   | 13        | 5.7%    |
| 5.11.0  | 12        | 5.26%   |
| 5.19.0  | 8         | 3.51%   |
| 5.13.0  | 8         | 3.51%   |
| 5.10.0  | 7         | 3.07%   |
| 5.3.0   | 6         | 2.63%   |
| 6.0.0   | 5         | 2.19%   |
| 6.5.0   | 4         | 1.75%   |
| 6.2.0   | 4         | 1.75%   |
| 5.0.0   | 4         | 1.75%   |
| 4.18.0  | 4         | 1.75%   |
| 4.15.0  | 4         | 1.75%   |
| 6.0.12  | 3         | 1.32%   |
| 5.9.16  | 3         | 1.32%   |
| 5.18.12 | 3         | 1.32%   |
| 5.10.14 | 3         | 1.32%   |
| 4.19.0  | 3         | 1.32%   |
| 6.2.9   | 2         | 0.88%   |
| 6.2.7   | 2         | 0.88%   |
| 6.1.0   | 2         | 0.88%   |
| 6.0.9   | 2         | 0.88%   |
| 5.7.19  | 2         | 0.88%   |
| 5.6.11  | 2         | 0.88%   |
| 5.4.8   | 2         | 0.88%   |
| 5.16.15 | 2         | 0.88%   |
| 5.15.5  | 2         | 0.88%   |
| 5.10.52 | 2         | 0.88%   |
| 6.5.7   | 1         | 0.44%   |
| 6.5.2   | 1         | 0.44%   |
| 6.4.0   | 1         | 0.44%   |
| 6.3.3   | 1         | 0.44%   |
| 6.3.2   | 1         | 0.44%   |
| 6.3.1   | 1         | 0.44%   |
| 6.2.8   | 1         | 0.44%   |
| 6.2.15  | 1         | 0.44%   |
| 6.2.12  | 1         | 0.44%   |
| 6.1.9   | 1         | 0.44%   |
| 6.1.8   | 1         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 34        | 15.53%  |
| 5.15    | 25        | 11.42%  |
| 5.8     | 16        | 7.31%   |
| 5.10    | 16        | 7.31%   |
| 5.11    | 15        | 6.85%   |
| 6.2     | 11        | 5.02%   |
| 6.0     | 11        | 5.02%   |
| 5.19    | 10        | 4.57%   |
| 5.13    | 9         | 4.11%   |
| 5.16    | 8         | 3.65%   |
| 6.1     | 7         | 3.2%    |
| 6.5     | 6         | 2.74%   |
| 5.3     | 6         | 2.74%   |
| 5.18    | 6         | 2.74%   |
| 4.18    | 5         | 2.28%   |
| 5.9     | 4         | 1.83%   |
| 5.0     | 4         | 1.83%   |
| 4.19    | 4         | 1.83%   |
| 4.15    | 4         | 1.83%   |
| 6.3     | 3         | 1.37%   |
| 5.7     | 3         | 1.37%   |
| 5.17    | 3         | 1.37%   |
| 5.6     | 2         | 0.91%   |
| 5.14    | 2         | 0.91%   |
| 5.12    | 2         | 0.91%   |
| 5.1     | 2         | 0.91%   |
| 6.4     | 1         | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 193       | 98.97%  |
| i686   | 2         | 1.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| GNOME          | 96        | 47.06%  |
| KDE5           | 48        | 23.53%  |
| Unknown        | 18        | 8.82%   |
| XFCE           | 16        | 7.84%   |
| X-Cinnamon     | 8         | 3.92%   |
| MATE           | 3         | 1.47%   |
| awesome        | 3         | 1.47%   |
| KDE            | 2         | 0.98%   |
| i3-with-shmlog | 2         | 0.98%   |
| Unity          | 1         | 0.49%   |
| qtile          | 1         | 0.49%   |
| LXQt           | 1         | 0.49%   |
| LXDE           | 1         | 0.49%   |
| i3             | 1         | 0.49%   |
| DWM            | 1         | 0.49%   |
| Deepin         | 1         | 0.49%   |
| bspwm          | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 159       | 76.81%  |
| Wayland | 36        | 17.39%  |
| Unknown | 10        | 4.83%   |
| Tty     | 2         | 0.97%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 95        | 46.12%  |
| SDDM    | 36        | 17.48%  |
| GDM     | 30        | 14.56%  |
| LightDM | 20        | 9.71%   |
| GDM3    | 19        | 9.22%   |
| TDM     | 6         | 2.91%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 165       | 83.33%  |
| Unknown | 16        | 8.08%   |
| en_GB   | 7         | 3.54%   |
| C       | 5         | 2.53%   |
| en_IE   | 1         | 0.51%   |
| en_EN   | 1         | 0.51%   |
| en_CA   | 1         | 0.51%   |
| en_AG   | 1         | 0.51%   |
| Default | 1         | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 106       | 52.74%  |
| BIOS | 95        | 47.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 153       | 77.27%  |
| Btrfs   | 22        | 11.11%  |
| Overlay | 16        | 8.08%   |
| Tmpfs   | 3         | 1.52%   |
| Unknown | 3         | 1.52%   |
| Xfs     | 1         | 0.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 103       | 50.74%  |
| GPT     | 78        | 38.42%  |
| MBR     | 22        | 10.84%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 174       | 87.88%  |
| Yes       | 24        | 12.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 117       | 58.79%  |
| Yes       | 82        | 41.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 51        | 26.15%  |
| Hewlett-Packard     | 48        | 24.62%  |
| Lenovo              | 27        | 13.85%  |
| Dell                | 26        | 13.33%  |
| Acer                | 20        | 10.26%  |
| MSI                 | 7         | 3.59%   |
| Notebook            | 4         | 2.05%   |
| Toshiba             | 3         | 1.54%   |
| Apple               | 2         | 1.03%   |
| win element         | 1         | 0.51%   |
| Timi                | 1         | 0.51%   |
| Samsung Electronics | 1         | 0.51%   |
| HUAWEI              | 1         | 0.51%   |
| Fujitsu             | 1         | 0.51%   |
| Daffodil Computers  | 1         | 0.51%   |
| Unknown             | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| HP ProBook 450 G4                                     | 5         | 2.56%   |
| HP Notebook                                           | 4         | 2.05%   |
| MSI Modern 15 A5M                                     | 3         | 1.54%   |
| ASUS VivoBook_ASUSLaptop X530FN_S530FN                | 3         | 1.54%   |
| MSI Modern 14 B10MW                                   | 2         | 1.03%   |
| HP ProBook 4540s                                      | 2         | 1.03%   |
| HP ProBook 450 G2                                     | 2         | 1.03%   |
| HP ProBook 440 G8 Notebook PC                         | 2         | 1.03%   |
| HP EliteBook 840 G3                                   | 2         | 1.03%   |
| HP 15                                                 | 2         | 1.03%   |
| HP 14                                                 | 2         | 1.03%   |
| Dell Inspiron 3442                                    | 2         | 1.03%   |
| ASUS X556UQK                                          | 2         | 1.03%   |
| ASUS X510UQ                                           | 2         | 1.03%   |
| ASUS VivoBook_ASUSLaptop X531FL_S531FL                | 2         | 1.03%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA                | 2         | 1.03%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA                | 2         | 1.03%   |
| ASUS VivoBook_ASUSLaptop X509DA                       | 2         | 1.03%   |
| ASUS VivoBook 14_ASUS Laptop X407UA                   | 2         | 1.03%   |
| ASUS P453UA                                           | 2         | 1.03%   |
| Acer Nitro AN515-43                                   | 2         | 1.03%   |
| win element MoreFine S500+                            | 1         | 0.51%   |
| Toshiba Satellite Pro L510                            | 1         | 0.51%   |
| Toshiba Satellite L645                                | 1         | 0.51%   |
| Toshiba Satellite C660                                | 1         | 0.51%   |
| Timi Mi NoteBook Pro                                  | 1         | 0.51%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.51%   |
| Notebook W9x0LU                                       | 1         | 0.51%   |
| Notebook N750BU                                       | 1         | 0.51%   |
| Notebook N2x0LU                                       | 1         | 0.51%   |
| Notebook DCL C483                                     | 1         | 0.51%   |
| MSI Summit B14 A11MOT                                 | 1         | 0.51%   |
| MSI GS63 7RD                                          | 1         | 0.51%   |
| Lenovo V330-14IKB 81B0                                | 1         | 0.51%   |
| Lenovo ThinkPad X230 2324F51                          | 1         | 0.51%   |
| Lenovo ThinkPad X230 2324A82                          | 1         | 0.51%   |
| Lenovo ThinkPad X220 4290CTO                          | 1         | 0.51%   |
| Lenovo ThinkPad T470s 20HGS23V06                      | 1         | 0.51%   |
| Lenovo ThinkPad T450 20BUS2021M                       | 1         | 0.51%   |
| Lenovo ThinkPad T430s 2356GPU                         | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| ASUS VivoBook             | 24        | 12.31%  |
| HP ProBook                | 20        | 10.26%  |
| Acer Aspire               | 15        | 7.69%   |
| Dell Inspiron             | 13        | 6.67%   |
| Lenovo IdeaPad            | 12        | 6.15%   |
| Lenovo ThinkPad           | 9         | 4.62%   |
| Dell Latitude             | 8         | 4.1%    |
| HP EliteBook              | 7         | 3.59%   |
| MSI Modern                | 5         | 2.56%   |
| HP Notebook               | 4         | 2.05%   |
| Toshiba Satellite         | 3         | 1.54%   |
| HP Pavilion               | 3         | 1.54%   |
| HP Laptop                 | 3         | 1.54%   |
| HP 15                     | 3         | 1.54%   |
| Acer Nitro                | 3         | 1.54%   |
| HP ENVY                   | 2         | 1.03%   |
| HP 14                     | 2         | 1.03%   |
| Dell XPS                  | 2         | 1.03%   |
| Dell Vostro               | 2         | 1.03%   |
| ASUS X556UQK              | 2         | 1.03%   |
| ASUS X510UQ               | 2         | 1.03%   |
| ASUS P453UA               | 2         | 1.03%   |
| Acer TravelMate           | 2         | 1.03%   |
| win element MoreFine      | 1         | 0.51%   |
| Timi Mi                   | 1         | 0.51%   |
| Samsung 300E5EV           | 1         | 0.51%   |
| Notebook W9x0LU           | 1         | 0.51%   |
| Notebook N750BU           | 1         | 0.51%   |
| Notebook N2x0LU           | 1         | 0.51%   |
| Notebook DCL              | 1         | 0.51%   |
| MSI Summit                | 1         | 0.51%   |
| MSI GS63                  | 1         | 0.51%   |
| Lenovo V330-14IKB         | 1         | 0.51%   |
| Lenovo S20-30             | 1         | 0.51%   |
| Lenovo S10-3              | 1         | 0.51%   |
| Lenovo LEGION5PRO-16ACH6H | 1         | 0.51%   |
| Lenovo Legion             | 1         | 0.51%   |
| Lenovo G40-70             | 1         | 0.51%   |
| HUAWEI RLEF-XX            | 1         | 0.51%   |
| HP ZHAN                   | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2016 | 28        | 14.36%  |
| 2017 | 23        | 11.79%  |
| 2018 | 21        | 10.77%  |
| 2021 | 18        | 9.23%   |
| 2019 | 18        | 9.23%   |
| 2015 | 16        | 8.21%   |
| 2014 | 14        | 7.18%   |
| 2020 | 12        | 6.15%   |
| 2012 | 12        | 6.15%   |
| 2013 | 10        | 5.13%   |
| 2011 | 9         | 4.62%   |
| 2010 | 6         | 3.08%   |
| 2022 | 4         | 2.05%   |
| 2009 | 3         | 1.54%   |
| 2008 | 1         | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 195       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 176       | 88.44%  |
| Enabled  | 23        | 11.56%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 195       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 76        | 38.38%  |
| 3.01-4.0    | 53        | 26.77%  |
| 8.01-16.0   | 40        | 20.2%   |
| 16.01-24.0  | 19        | 9.6%    |
| 1.01-2.0    | 6         | 3.03%   |
| 2.01-3.0    | 2         | 1.01%   |
| 32.01-64.0  | 1         | 0.51%   |
| 64.01-256.0 | 1         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 73        | 33.33%  |
| 2.01-3.0  | 72        | 32.88%  |
| 3.01-4.0  | 40        | 18.26%  |
| 4.01-8.0  | 22        | 10.05%  |
| 0.51-1.0  | 9         | 4.11%   |
| 8.01-16.0 | 2         | 0.91%   |
| 0.01-0.5  | 1         | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 132       | 66.67%  |
| 2      | 63        | 31.82%  |
| 3      | 3         | 1.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 131       | 66.84%  |
| Yes       | 65        | 33.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 150       | 76.14%  |
| No        | 47        | 23.86%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 190       | 97.44%  |
| No        | 5         | 2.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 165       | 83.33%  |
| No        | 33        | 16.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Bangladesh | 195       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dhaka             | 121       | 58.74%  |
| Chittagong        | 14        | 6.8%    |
| Rajshahi          | 9         | 4.37%   |
| Jessore           | 6         | 2.91%   |
| Tongi             | 5         | 2.43%   |
| Khulna            | 5         | 2.43%   |
| Narayanganj       | 4         | 1.94%   |
| Sylhet            | 3         | 1.46%   |
| Mirpur            | 3         | 1.46%   |
| Comilla           | 3         | 1.46%   |
| Wari              | 2         | 0.97%   |
| Sherpur           | 2         | 0.97%   |
| Savar Upazila     | 2         | 0.97%   |
| Narail            | 2         | 0.97%   |
| Azimpur           | 2         | 0.97%   |
| Tejgaon           | 1         | 0.49%   |
| Srimangal         | 1         | 0.49%   |
| Sirajganj         | 1         | 0.49%   |
| Rangpur City      | 1         | 0.49%   |
| Pirganj           | 1         | 0.49%   |
| Paltan            | 1         | 0.49%   |
| Pabna Sadar       | 1         | 0.49%   |
| Pabna             | 1         | 0.49%   |
| NДЃrДЃyanganj | 1         | 0.49%   |
| Nilphamari        | 1         | 0.49%   |
| Natore            | 1         | 0.49%   |
| Nalitabari        | 1         | 0.49%   |
| Mymensingh        | 1         | 0.49%   |
| LДЃkshДЃm     | 1         | 0.49%   |
| Khilgaon          | 1         | 0.49%   |
| Jamalpur          | 1         | 0.49%   |
| Habiganj          | 1         | 0.49%   |
| Gulshan           | 1         | 0.49%   |
| Faridpur          | 1         | 0.49%   |
| Dhunot            | 1         | 0.49%   |
| Dewangonj         | 1         | 0.49%   |
| Bogra             | 1         | 0.49%   |
| Belkuchi          | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate                        | 47        | 59     | 18.22%  |
| WDC                            | 43        | 57     | 16.67%  |
| Toshiba                        | 36        | 45     | 13.95%  |
| Samsung Electronics            | 13        | 19     | 5.04%   |
| Transcend                      | 12        | 13     | 4.65%   |
| HGST                           | 12        | 12     | 4.65%   |
| SanDisk                        | 10        | 10     | 3.88%   |
| Intel                          | 9         | 11     | 3.49%   |
| Hitachi                        | 8         | 10     | 3.1%    |
| Micron Technology              | 7         | 7      | 2.71%   |
| Kingston                       | 7         | 9      | 2.71%   |
| A-DATA Technology              | 7         | 7      | 2.71%   |
| SK hynix                       | 4         | 4      | 1.55%   |
| Silicon Motion                 | 4         | 10     | 1.55%   |
| Team                           | 3         | 3      | 1.16%   |
| Corsair                        | 3         | 5      | 1.16%   |
| Ramsta                         | 2         | 2      | 0.78%   |
| KingSpec                       | 2         | 2      | 0.78%   |
| Crucial                        | 2         | 3      | 0.78%   |
| Apacer                         | 2         | 3      | 0.78%   |
| WDC WDS4                       | 1         | 1      | 0.39%   |
| WALTON                         | 1         | 2      | 0.39%   |
| Unknown                        | 1         | 1      | 0.39%   |
| Teutons                        | 1         | 1      | 0.39%   |
| Solid State Storage Technology | 1         | 1      | 0.39%   |
| Shenzhen Longsys Electronics   | 1         | 1      | 0.39%   |
| Realtek Semiconductor          | 1         | 1      | 0.39%   |
| Realtek                        | 1         | 1      | 0.39%   |
| PNY                            | 1         | 1      | 0.39%   |
| Phison Electronics             | 1         | 1      | 0.39%   |
| Phison                         | 1         | 1      | 0.39%   |
| Netac                          | 1         | 1      | 0.39%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 0.39%   |
| Lexar                          | 1         | 2      | 0.39%   |
| KIOXIA                         | 1         | 1      | 0.39%   |
| Kingsand                       | 1         | 1      | 0.39%   |
| HS-SSD-E100                    | 1         | 1      | 0.39%   |
| Hewlett-Packard                | 1         | 1      | 0.39%   |
| Gigabyte Technology            | 1         | 1      | 0.39%   |
| GeIL                           | 1         | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 20        | 7.6%    |
| Toshiba MQ04ABF100 1TB                            | 16        | 6.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 6         | 2.28%   |
| WDC WD10JPVX-60JC3T0 1TB                          | 5         | 1.9%    |
| Toshiba MQ01ABD100 1TB                            | 5         | 1.9%    |
| Seagate ST500LT012-1DG142 500GB                   | 5         | 1.9%    |
| HGST HTS541010A9E680 1TB                          | 5         | 1.9%    |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 4         | 1.52%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 4         | 1.52%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                  | 3         | 1.14%   |
| Transcend TS120GMTS420S 120GB SSD                 | 3         | 1.14%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 2TB | 3         | 1.14%   |
| Seagate ST9500325AS 500GB                         | 3         | 1.14%   |
| Seagate ST500LT012-9WS142 500GB                   | 3         | 1.14%   |
| Seagate ST1000LM049-2GH172 1TB                    | 3         | 1.14%   |
| SanDisk NVMe SSD Drive 512GB                      | 3         | 1.14%   |
| Samsung SSD 860 EVO 500GB                         | 3         | 1.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3         | 1.14%   |
| Intel SSD 660P Series 1024GB                      | 3         | 1.14%   |
| Intel NVMe SSD Drive 512GB                        | 3         | 1.14%   |
| HGST HTS545050A7E680 500GB                        | 3         | 1.14%   |
| A-DATA SU650 240GB SSD                            | 3         | 1.14%   |
| WDC WD10SPZX-24Z10T0 1TB                          | 2         | 0.76%   |
| WDC WD10JPVX-75JC3T0 1TB                          | 2         | 0.76%   |
| WDC WD10JPVX-60JC3T1 1TB                          | 2         | 0.76%   |
| WDC PC SN520 SDAPNUW-256G-1002 256GB              | 2         | 0.76%   |
| Transcend TS256GSSD230S 256GB                     | 2         | 0.76%   |
| Transcend TS240GMTS820S 240GB SSD                 | 2         | 0.76%   |
| Toshiba THNSNK128GVN8 128GB SSD                   | 2         | 0.76%   |
| Toshiba MQ01ACF050 500GB                          | 2         | 0.76%   |
| Toshiba MQ01ABD050 500GB                          | 2         | 0.76%   |
| Ramsta SSD R800 120GB                             | 2         | 0.76%   |
| Micron MTFDDAV512TBN-1AR1ZABHA 512GB SSD          | 2         | 0.76%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD               | 2         | 0.76%   |
| Kingston OM8PCP3512F-AI1 512GB                    | 2         | 0.76%   |
| Hitachi HTS547550A9E384 500GB                     | 2         | 0.76%   |
| Hitachi HTS543232A7A384 320GB                     | 2         | 0.76%   |
| HGST HTS541010B7E610 1TB                          | 2         | 0.76%   |
| Corsair Force MP510 240GB                         | 2         | 0.76%   |
| WDC WDS4 80G2G0B-00EPW0 480GB SSD                 | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 47        | 59     | 37.9%   |
| Toshiba | 30        | 38     | 24.19%  |
| WDC     | 27        | 36     | 21.77%  |
| HGST    | 12        | 12     | 9.68%   |
| Hitachi | 8         | 10     | 6.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 14     | 14.67%  |
| Transcend           | 11        | 12     | 14.67%  |
| Samsung Electronics | 7         | 10     | 9.33%   |
| A-DATA Technology   | 7         | 7      | 9.33%   |
| SanDisk             | 6         | 6      | 8%      |
| Micron Technology   | 6         | 6      | 8%      |
| Toshiba             | 2         | 3      | 2.67%   |
| Team                | 2         | 2      | 2.67%   |
| Ramsta              | 2         | 2      | 2.67%   |
| KingSpec            | 2         | 2      | 2.67%   |
| Crucial             | 2         | 3      | 2.67%   |
| Apacer              | 2         | 3      | 2.67%   |
| WDC WDS4            | 1         | 1      | 1.33%   |
| WALTON              | 1         | 2      | 1.33%   |
| Teutons             | 1         | 1      | 1.33%   |
| SK hynix            | 1         | 1      | 1.33%   |
| PNY                 | 1         | 1      | 1.33%   |
| Netac               | 1         | 1      | 1.33%   |
| Kingston            | 1         | 1      | 1.33%   |
| Intel               | 1         | 1      | 1.33%   |
| HS-SSD-E100         | 1         | 1      | 1.33%   |
| Hewlett-Packard     | 1         | 1      | 1.33%   |
| Gigabyte Technology | 1         | 1      | 1.33%   |
| GeIL                | 1         | 1      | 1.33%   |
| Corsair             | 1         | 2      | 1.33%   |
| China               | 1         | 1      | 1.33%   |
| ASMT                | 1         | 1      | 1.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 124       | 155    | 49.6%   |
| SSD     | 72        | 87     | 28.8%   |
| NVMe    | 49        | 71     | 19.6%   |
| Unknown | 5         | 5      | 2%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 161       | 243    | 74.88%  |
| NVMe | 49        | 70     | 22.79%  |
| SAS  | 5         | 5      | 2.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 97        | 124    | 51.32%  |
| 0.51-1.0   | 88        | 113    | 46.56%  |
| 1.01-2.0   | 3         | 4      | 1.59%   |
| 3.01-4.0   | 1         | 1      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 54        | 25.96%  |
| 251-500        | 53        | 25.48%  |
| 501-1000       | 40        | 19.23%  |
| 51-100         | 20        | 9.62%   |
| 1001-2000      | 15        | 7.21%   |
| 1-20           | 10        | 4.81%   |
| 21-50          | 9         | 4.33%   |
| Unknown        | 4         | 1.92%   |
| More than 3000 | 3         | 1.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 70        | 32.41%  |
| 51-100         | 41        | 18.98%  |
| 21-50          | 40        | 18.52%  |
| 101-250        | 37        | 17.13%  |
| 251-500        | 13        | 6.02%   |
| 501-1000       | 8         | 3.7%    |
| Unknown        | 4         | 1.85%   |
| 1001-2000      | 2         | 0.93%   |
| More than 3000 | 1         | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                             | Notebooks | Drives | Percent |
|---------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                            | 3         | 5      | 11.54%  |
| Toshiba MQ01ABD050 500GB                          | 2         | 2      | 7.69%   |
| HGST HTS545050A7E680 500GB                        | 2         | 2      | 7.69%   |
| HGST HTS541010A9E680 1TB                          | 2         | 2      | 7.69%   |
| WDC WD5000LPCX-22VHAT0 500GB                      | 1         | 1      | 3.85%   |
| WDC WD5000BPVT-22HXZT3 500GB                      | 1         | 1      | 3.85%   |
| WDC WD10SPZX-24Z10T0 1TB                          | 1         | 1      | 3.85%   |
| WDC WD10JPVX-60JC3T0 1TB                          | 1         | 2      | 3.85%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD             | 1         | 1      | 3.85%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 2TB | 1         | 1      | 3.85%   |
| Seagate ST9500325AS 500GB                         | 1         | 1      | 3.85%   |
| Seagate ST500LT012-9WS142 500GB                   | 1         | 1      | 3.85%   |
| Seagate ST500LT012-1DG142 500GB                   | 1         | 1      | 3.85%   |
| Seagate ST320LT012-9WS14C 320GB                   | 1         | 1      | 3.85%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                | 1         | 1      | 3.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 1         | 1      | 3.85%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD    | 1         | 1      | 3.85%   |
| Intel SSDSCKKW240H6 240GB                         | 1         | 1      | 3.85%   |
| Hitachi HTS545025B9A300 250GB                     | 1         | 1      | 3.85%   |
| HGST HTS545050A7E380 500GB                        | 1         | 1      | 3.85%   |
| Hewlett-Packard SSD S600 240GB                    | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 6      | 23.08%  |
| Toshiba           | 5         | 7      | 19.23%  |
| HGST              | 5         | 5      | 19.23%  |
| WDC               | 4         | 5      | 15.38%  |
| SK hynix          | 1         | 1      | 3.85%   |
| Silicon Motion    | 1         | 1      | 3.85%   |
| Micron Technology | 1         | 1      | 3.85%   |
| Intel             | 1         | 1      | 3.85%   |
| Hitachi           | 1         | 1      | 3.85%   |
| Hewlett-Packard   | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 28.57%  |
| Toshiba | 5         | 7      | 23.81%  |
| HGST    | 5         | 5      | 23.81%  |
| WDC     | 4         | 5      | 19.05%  |
| Hitachi | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 24     | 80.77%  |
| SSD  | 4         | 4      | 15.38%  |
| NVMe | 1         | 1      | 3.85%   |

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
| Detected | 113       | 178    | 53.55%  |
| Works    | 72        | 111    | 34.12%  |
| Malfunc  | 26        | 29     | 12.32%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 163       | 72.12%  |
| AMD                            | 17        | 7.52%   |
| SanDisk                        | 9         | 3.98%   |
| Samsung Electronics            | 6         | 2.65%   |
| Kingston Technology Company    | 6         | 2.65%   |
| Silicon Motion                 | 4         | 1.77%   |
| Phison Electronics             | 4         | 1.77%   |
| SK hynix                       | 3         | 1.33%   |
| Shenzhen Longsys Electronics   | 3         | 1.33%   |
| KIOXIA                         | 3         | 1.33%   |
| Toshiba America Info Systems   | 2         | 0.88%   |
| Solid State Storage Technology | 1         | 0.44%   |
| Realtek Semiconductor          | 1         | 0.44%   |
| Nvidia                         | 1         | 0.44%   |
| Micron Technology              | 1         | 0.44%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.44%   |
| Biwin Storage Technology       | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 55        | 22.92%  |
| AMD FCH SATA Controller [AHCI mode]                                              | 17        | 7.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 16        | 6.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 5%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 12        | 5%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 11        | 4.58%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 10        | 4.17%   |
| Intel Volume Management Device NVMe RAID Controller                              | 9         | 3.75%   |
| Intel SSD 660P Series                                                            | 6         | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 2.5%    |
| Intel Tiger Lake-LP SATA Controller                                              | 5         | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 2.08%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                    | 4         | 1.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.67%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 3         | 1.25%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 3         | 1.25%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 3         | 1.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.25%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 3         | 1.25%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.25%   |
| Shenzhen Longsys Lexar NM620 NVME SSD (DRAM-less)                                | 2         | 0.83%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 2         | 0.83%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.83%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 2         | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 0.83%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.83%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 2         | 0.83%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 1         | 0.42%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.42%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                   | 1         | 0.42%   |
| SK hynix PC611 NVMe Solid State Drive                                            | 1         | 0.42%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 1         | 0.42%   |
| SK hynix BC511 NVMe SSD                                                          | 1         | 0.42%   |
| Silicon Motion Non-Volatile memory controller                                    | 1         | 0.42%   |
| Shenzhen Longsys FORESEE P900 BGA NVMe SSD (DRAM-less)                           | 1         | 0.42%   |
| SanDisk WD PC SN540 / Green SN350 NVMe SSD 1 TB (DRAM-less)                      | 1         | 0.42%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 0.42%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                      | 1         | 0.42%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 157       | 67.09%  |
| NVMe | 49        | 20.94%  |
| RAID | 24        | 10.26%  |
| IDE  | 4         | 1.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 173       | 88.72%  |
| AMD    | 22        | 11.28%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 7.18%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 4.62%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 4.1%    |
| Intel Core i3-7100U CPU @ 2.40GHz             | 8         | 4.1%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 3.59%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 3.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 2.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 2.56%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 5         | 2.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.05%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 2.05%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 2.05%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 2.05%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 2.05%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 2.05%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 2.05%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 2.05%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 1.54%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.54%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 3         | 1.54%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.54%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 1.54%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 1.54%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 3         | 1.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.03%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.03%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.03%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 2         | 1.03%   |
| Intel Core i3-7130U CPU @ 2.70GHz             | 2         | 1.03%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 2         | 1.03%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.03%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 1.03%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz          | 2         | 1.03%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.03%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 2         | 1.03%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.03%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 1.03%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.51%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.51%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 79        | 40.51%  |
| Intel Core i3           | 44        | 22.56%  |
| Intel Core i7           | 17        | 8.72%   |
| Other                   | 15        | 7.69%   |
| AMD Ryzen 5             | 8         | 4.1%    |
| AMD Ryzen 7             | 6         | 3.08%   |
| Intel Pentium           | 5         | 2.56%   |
| Intel Celeron           | 5         | 2.56%   |
| Intel Core 2 Duo        | 4         | 2.05%   |
| AMD Ryzen 3             | 3         | 1.54%   |
| Intel Atom              | 2         | 1.03%   |
| Intel Pentium Dual-Core | 1         | 0.51%   |
| Intel Celeron Dual-Core | 1         | 0.51%   |
| AMD Ryzen 9             | 1         | 0.51%   |
| AMD E2                  | 1         | 0.51%   |
| AMD A8                  | 1         | 0.51%   |
| AMD A6                  | 1         | 0.51%   |
| AMD A4                  | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 127       | 65.13%  |
| 4      | 53        | 27.18%  |
| 8      | 8         | 4.1%    |
| 6      | 6         | 3.08%   |
| 1      | 1         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 195       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 174       | 88.78%  |
| 1      | 22        | 11.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 194       | 99.49%  |
| Unknown        | 1         | 0.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 29.13%  |
| 0x806e9    | 23        | 11.17%  |
| 0x806ea    | 15        | 7.28%   |
| 0x406e3    | 11        | 5.34%   |
| 0x40651    | 10        | 4.85%   |
| 0x306d4    | 10        | 4.85%   |
| 0x206a7    | 8         | 3.88%   |
| 0x806ec    | 7         | 3.4%    |
| 0x806c1    | 7         | 3.4%    |
| 0x306a9    | 7         | 3.4%    |
| 0x806eb    | 6         | 2.91%   |
| 0x706e5    | 5         | 2.43%   |
| 0x406c4    | 4         | 1.94%   |
| 0x1067a    | 4         | 1.94%   |
| 0x08108109 | 3         | 1.46%   |
| 0x08108102 | 3         | 1.46%   |
| 0xa0652    | 2         | 0.97%   |
| 0x306c3    | 2         | 0.97%   |
| 0x20655    | 2         | 0.97%   |
| 0x0a50000c | 2         | 0.97%   |
| 0x08608103 | 2         | 0.97%   |
| 0x906e9    | 1         | 0.49%   |
| 0x906a3    | 1         | 0.49%   |
| 0x806d1    | 1         | 0.49%   |
| 0x506e3    | 1         | 0.49%   |
| 0x406c3    | 1         | 0.49%   |
| 0x30678    | 1         | 0.49%   |
| 0x30661    | 1         | 0.49%   |
| 0x106ca    | 1         | 0.49%   |
| 0x10676    | 1         | 0.49%   |
| 0x0a50000d | 1         | 0.49%   |
| 0x08600104 | 1         | 0.49%   |
| 0x0810100b | 1         | 0.49%   |
| 0x06006705 | 1         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 68        | 34.87%  |
| Skylake          | 17        | 8.72%   |
| Haswell          | 15        | 7.69%   |
| Broadwell        | 13        | 6.67%   |
| TigerLake        | 12        | 6.15%   |
| IvyBridge        | 11        | 5.64%   |
| SandyBridge      | 10        | 5.13%   |
| Zen+             | 7         | 3.59%   |
| Silvermont       | 7         | 3.59%   |
| Penryn           | 6         | 3.08%   |
| IceLake          | 6         | 3.08%   |
| Zen 3            | 5         | 2.56%   |
| Unknown          | 3         | 1.54%   |
| Zen 2            | 2         | 1.03%   |
| Westmere         | 2         | 1.03%   |
| Excavator        | 2         | 1.03%   |
| CometLake        | 2         | 1.03%   |
| Bonnell          | 2         | 1.03%   |
| Alderlake Hybrid | 2         | 1.03%   |
| Zen              | 1         | 0.51%   |
| Puma             | 1         | 0.51%   |
| K10 Llano        | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 171       | 69.8%   |
| Nvidia | 46        | 18.78%  |
| AMD    | 28        | 11.43%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 31        | 12.5%   |
| Intel UHD Graphics 620                                                                   | 16        | 6.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 6.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 5.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 5.24%   |
| Intel HD Graphics 5500                                                                   | 12        | 4.84%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 4.44%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 4.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 4.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.82%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 2.42%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 2.02%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 2.02%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 2.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 2.02%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 1.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.21%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 1.21%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.21%   |
| AMD Lucienne                                                                             | 3         | 1.21%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 0.81%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.81%   |
| Intel HD Graphics 630                                                                    | 2         | 0.81%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.81%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.81%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 0.81%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.81%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 2         | 0.81%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 0.81%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.4%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.4%    |
| Nvidia TU104M [GeForce RTX 2070 SUPER Mobile / Max-Q]                                    | 1         | 0.4%    |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.4%    |
| Nvidia GP107M [GeForce MX350]                                                            | 1         | 0.4%    |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.4%    |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 127       | 65.13%  |
| Intel + Nvidia | 39        | 20%     |
| 1 x AMD        | 14        | 7.18%   |
| AMD + Nvidia   | 6         | 3.08%   |
| Intel + AMD    | 5         | 2.56%   |
| 2 x AMD        | 3         | 1.54%   |
| 1 x Nvidia     | 1         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 174       | 87%     |
| Proprietary | 24        | 12%     |
| Unknown     | 2         | 1%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 157       | 78.89%  |
| 1.01-2.0   | 22        | 11.06%  |
| 3.01-4.0   | 9         | 4.52%   |
| 0.01-0.5   | 7         | 3.52%   |
| 7.01-8.0   | 2         | 1.01%   |
| 5.01-6.0   | 1         | 0.5%    |
| 0.51-1.0   | 1         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 52        | 24.07%  |
| AU Optronics            | 47        | 21.76%  |
| Chimei Innolux          | 39        | 18.06%  |
| LG Display              | 33        | 15.28%  |
| Samsung Electronics     | 15        | 6.94%   |
| Dell                    | 6         | 2.78%   |
| PANDA                   | 5         | 2.31%   |
| Hewlett-Packard         | 4         | 1.85%   |
| Goldstar                | 4         | 1.85%   |
| Chi Mei Optoelectronics | 3         | 1.39%   |
| Apple                   | 2         | 0.93%   |
| ViewSonic               | 1         | 0.46%   |
| Sharp                   | 1         | 0.46%   |
| MSI                     | 1         | 0.46%   |
| ASUSTek Computer        | 1         | 0.46%   |
| AOC                     | 1         | 0.46%   |
| Ancor Communications    | 1         | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 10        | 4.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 2.78%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 4         | 1.85%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 3         | 1.39%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 3         | 1.39%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 1.39%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 3         | 1.39%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 3         | 1.39%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 3         | 1.39%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch         | 2         | 0.93%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch             | 2         | 0.93%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch             | 2         | 0.93%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch              | 2         | 0.93%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch              | 2         | 0.93%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 2         | 0.93%   |
| LG Display LCD Monitor LGD0466 1366x768 309x174mm 14.0-inch              | 2         | 0.93%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch              | 2         | 0.93%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch              | 2         | 0.93%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN14A1 1366x768 309x174mm 14.0-inch          | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 309x174mm 14.0-inch          | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 2         | 0.93%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 2         | 0.93%   |
| BOE LCD Monitor BOE07B4 1366x768 344x194mm 15.5-inch                     | 2         | 0.93%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 2         | 0.93%   |
| BOE LCD Monitor BOE0698 1366x768 309x173mm 13.9-inch                     | 2         | 0.93%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 2         | 0.93%   |
| ViewSonic VA2259 Series VSC5E32 1920x1080 476x268mm 21.5-inch            | 1         | 0.46%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM043E 1600x1200 520x320mm 24.0-inch     | 1         | 0.46%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch        | 1         | 0.46%   |
| Samsung Electronics S19C300 SAM0A12 1366x768 410x230mm 18.5-inch         | 1         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 100       | 48.54%  |
| 1920x1080 (FHD)   | 85        | 41.26%  |
| 1600x900 (HD+)    | 5         | 2.43%   |
| 3840x2160 (4K)    | 3         | 1.46%   |
| 1280x800 (WXGA)   | 3         | 1.46%   |
| 2560x1600         | 2         | 0.97%   |
| 1920x1200 (WUXGA) | 2         | 0.97%   |
| 1024x600          | 2         | 0.97%   |
| 3840x2400         | 1         | 0.49%   |
| 2560x1440 (QHD)   | 1         | 0.49%   |
| 2240x1400         | 1         | 0.49%   |
| 1280x1024 (SXGA)  | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 90        | 41.86%  |
| 13      | 45        | 20.93%  |
| 14      | 37        | 17.21%  |
| 21      | 10        | 4.65%   |
| 18      | 8         | 3.72%   |
| 12      | 6         | 2.79%   |
| 23      | 3         | 1.4%    |
| 17      | 3         | 1.4%    |
| 16      | 3         | 1.4%    |
| 11      | 3         | 1.4%    |
| 10      | 2         | 0.93%   |
| 27      | 1         | 0.47%   |
| 26      | 1         | 0.47%   |
| 24      | 1         | 0.47%   |
| 19      | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 164       | 76.64%  |
| 201-300     | 21        | 9.81%   |
| 401-500     | 20        | 9.35%   |
| 501-600     | 5         | 2.34%   |
| 351-400     | 3         | 1.4%    |
| Unknown     | 1         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 183       | 94.82%  |
| 16/10 | 9         | 4.66%   |
| 5/4   | 1         | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 90        | 42.06%  |
| 81-90          | 73        | 34.11%  |
| 201-250        | 9         | 4.21%   |
| 141-150        | 9         | 4.21%   |
| 71-80          | 8         | 3.74%   |
| 61-70          | 6         | 2.8%    |
| 151-200        | 4         | 1.87%   |
| 51-60          | 3         | 1.4%    |
| 111-120        | 3         | 1.4%    |
| 41-50          | 2         | 0.93%   |
| 251-300        | 2         | 0.93%   |
| 301-350        | 1         | 0.47%   |
| 131-140        | 1         | 0.47%   |
| 121-130        | 1         | 0.47%   |
| 91-100         | 1         | 0.47%   |
| Unknown        | 1         | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 95        | 45.67%  |
| 121-160       | 86        | 41.35%  |
| 51-100        | 17        | 8.17%   |
| 161-240       | 7         | 3.37%   |
| More than 240 | 2         | 0.96%   |
| Unknown       | 1         | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 173       | 87.37%  |
| 2     | 23        | 11.62%  |
| 3     | 1         | 0.51%   |
| 0     | 1         | 0.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 127       | 41.64%  |
| Intel                 | 92        | 30.16%  |
| Qualcomm Atheros      | 57        | 18.69%  |
| Broadcom              | 8         | 2.62%   |
| MediaTek              | 6         | 1.97%   |
| Ralink Technology     | 4         | 1.31%   |
| Xiaomi                | 3         | 0.98%   |
| Ralink                | 2         | 0.66%   |
| TP-Link               | 1         | 0.33%   |
| Samsung Electronics   | 1         | 0.33%   |
| OPPO Electronics      | 1         | 0.33%   |
| Dell                  | 1         | 0.33%   |
| ASIX Electronics      | 1         | 0.33%   |
| Arduino SA            | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 78        | 22.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31        | 8.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 23        | 6.55%   |
| Intel Wireless 8265 / 8275                                        | 16        | 4.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 13        | 3.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 3.42%   |
| Intel Wi-Fi 6 AX201                                               | 11        | 3.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 9         | 2.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 8         | 2.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 1.99%   |
| Intel Wireless 3165                                               | 7         | 1.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.42%   |
| Intel Wireless 8260                                               | 5         | 1.42%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.14%   |
| Intel Wireless 7265                                               | 4         | 1.14%   |
| Intel Wireless 7260                                               | 4         | 1.14%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 1.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.85%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 3         | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.85%   |
| Intel Wireless 3160                                               | 3         | 0.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.85%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.57%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.57%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.57%   |
| Intel Wi-Fi 6 AX200                                               | 2         | 0.57%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.57%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 88        | 44.67%  |
| Qualcomm Atheros      | 54        | 27.41%  |
| Realtek Semiconductor | 36        | 18.27%  |
| MediaTek              | 6         | 3.05%   |
| Broadcom              | 5         | 2.54%   |
| Ralink Technology     | 4         | 2.03%   |
| Ralink                | 2         | 1.02%   |
| TP-Link               | 1         | 0.51%   |
| Dell                  | 1         | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 23        | 11.68%  |
| Intel Wireless 8265 / 8275                                     | 16        | 8.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 13        | 6.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 12        | 6.09%   |
| Intel Wi-Fi 6 AX201                                            | 11        | 5.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 9         | 4.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 8         | 4.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 3.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 3.55%   |
| Intel Wireless 3165                                            | 7         | 3.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 2.54%   |
| Intel Wireless 8260                                            | 5         | 2.54%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 2.03%   |
| Intel Wireless 7265                                            | 4         | 2.03%   |
| Intel Wireless 7260                                            | 4         | 2.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 1.52%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 1.52%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.52%   |
| Intel Wireless 3160                                            | 3         | 1.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 1.52%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.52%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.02%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.02%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 1.02%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.02%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.51%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.51%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.51%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.51%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 113       | 74.34%  |
| Intel                 | 22        | 14.47%  |
| Qualcomm Atheros      | 7         | 4.61%   |
| Broadcom              | 4         | 2.63%   |
| Xiaomi                | 3         | 1.97%   |
| Samsung Electronics   | 1         | 0.66%   |
| OPPO Electronics      | 1         | 0.66%   |
| ASIX Electronics      | 1         | 0.66%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 78        | 50.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31        | 20.26%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 4.58%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 2.61%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.96%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.31%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 1.31%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.31%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.65%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.65%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.65%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.65%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.65%   |
| OPPO RMX2027                                                      | 1         | 0.65%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 1         | 0.65%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.65%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.65%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.65%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 190       | 55.88%  |
| Ethernet | 149       | 43.82%  |
| Modem    | 1         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 166       | 83.84%  |
| Ethernet | 32        | 16.16%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 136       | 69.74%  |
| 1     | 58        | 29.74%  |
| 3     | 1         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 194       | 99.49%  |
| Yes  | 1         | 0.51%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 74        | 44.58%  |
| IMC Networks                    | 26        | 15.66%  |
| Realtek Semiconductor           | 19        | 11.45%  |
| Qualcomm Atheros Communications | 15        | 9.04%   |
| Lite-On Technology              | 11        | 6.63%   |
| Broadcom                        | 7         | 4.22%   |
| Foxconn / Hon Hai               | 4         | 2.41%   |
| Ralink                          | 2         | 1.2%    |
| MediaTek                        | 2         | 1.2%    |
| Toshiba                         | 1         | 0.6%    |
| Hewlett-Packard                 | 1         | 0.6%    |
| Foxconn International           | 1         | 0.6%    |
| Dell                            | 1         | 0.6%    |
| Cambridge Silicon Radio         | 1         | 0.6%    |
| Apple                           | 1         | 0.6%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 38        | 22.89%  |
| IMC Networks Bluetooth Device                       | 14        | 8.43%   |
| Intel AX201 Bluetooth                               | 13        | 7.83%   |
| Realtek Bluetooth Radio                             | 12        | 7.23%   |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 6.63%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 5.42%   |
| IMC Networks Bluetooth Radio                        | 9         | 5.42%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 4.82%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 7         | 4.22%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.41%   |
| Lite-On Bluetooth Device                            | 3         | 1.81%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 1.2%    |
| Ralink RT3290 Bluetooth                             | 2         | 1.2%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.2%    |
| MediaTek Wireless_Device                            | 2         | 1.2%    |
| Intel AX200 Bluetooth                               | 2         | 1.2%    |
| IMC Networks Wireless_Device                        | 2         | 1.2%    |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.2%    |
| Broadcom HP Portable SoftSailing                    | 2         | 1.2%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.2%    |
| Toshiba Bluetooth Radio                             | 1         | 0.6%    |
| Realtek RTL8821A Bluetooth                          | 1         | 0.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.6%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.6%    |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.6%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.6%    |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.6%    |
| Intel Bluetooth Device                              | 1         | 0.6%    |
| Intel AX210 Bluetooth                               | 1         | 0.6%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.6%    |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.6%    |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.6%    |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.6%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.6%    |
| Dell Wireless 360 Bluetooth                         | 1         | 0.6%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.6%    |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 0.6%    |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.6%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.6%    |
| Apple Bluetooth Host Controller                     | 1         | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 171       | 84.24%  |
| AMD                    | 22        | 10.84%  |
| Nvidia                 | 9         | 4.43%   |
| Generalplus Technology | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 63        | 25.1%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 18        | 7.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 14        | 5.58%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 5.18%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 5.18%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 5.18%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 5.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 5.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 4.78%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 3.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 2.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.99%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.99%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 0.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.8%    |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.8%    |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.8%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 2         | 0.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 0.8%    |
| AMD High Definition Audio Controller                                                              | 2         | 0.8%    |
| AMD FCH Azalia Controller                                                                         | 2         | 0.8%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.4%    |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.4%    |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.4%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.4%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.4%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.4%    |
| Intel USB PnP Sound Device                                                                        | 1         | 0.4%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.4%    |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.4%    |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.4%    |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 41        | 29.08%  |
| SK hynix            | 36        | 25.53%  |
| Micron Technology   | 19        | 13.48%  |
| A-DATA Technology   | 8         | 5.67%   |
| Kingston            | 6         | 4.26%   |
| Unknown             | 5         | 3.55%   |
| G.Skill             | 5         | 3.55%   |
| Transcend           | 4         | 2.84%   |
| Team                | 3         | 2.13%   |
| Ramaxel Technology  | 2         | 1.42%   |
| Nanya Technology    | 2         | 1.42%   |
| Crucial             | 2         | 1.42%   |
| Unknown (C509)      | 1         | 0.71%   |
| Unknown (768A)      | 1         | 0.71%   |
| Toshiba             | 1         | 0.71%   |
| Hewlett-Packard     | 1         | 0.71%   |
| Elpida              | 1         | 0.71%   |
| ASint Technology    | 1         | 0.71%   |
| Apacer              | 1         | 0.71%   |
| Unknown             | 1         | 0.71%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 6         | 4.2%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 5         | 3.5%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 4         | 2.8%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 2.1%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 3         | 2.1%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s    | 3         | 2.1%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 2.1%    |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 2         | 1.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 1.4%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 1.4%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.4%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 2         | 1.4%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 2         | 1.4%    |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s     | 2         | 1.4%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s    | 2         | 1.4%    |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s     | 2         | 1.4%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 1.4%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 2         | 1.4%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s      | 2         | 1.4%    |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s      | 2         | 1.4%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s     | 2         | 1.4%    |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s     | 2         | 1.4%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s    | 2         | 1.4%    |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.7%    |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s               | 1         | 0.7%    |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s               | 1         | 0.7%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.7%    |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 0.7%    |
| Unknown RAM Module 2048MB Row Of Chips LPDDR4 4267MT/s    | 1         | 0.7%    |
| Unknown (C509) RAM Module 4GB SODIMM DDR4 2400MT/s        | 1         | 0.7%    |
| Unknown (768A) RAM Module 8192MB SODIMM DDR4 3200MT/s     | 1         | 0.7%    |
| Transcend RAM JM3200HSB-8G 8GB SODIMM DDR4 3200MT/s       | 1         | 0.7%    |
| Transcend RAM JM2666HSG-8G 8GB SODIMM DDR4 2667MT/s       | 1         | 0.7%    |
| Transcend RAM JM2400HSB-8G 8GB SODIMM DDR4 2400MT/s       | 1         | 0.7%    |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s       | 1         | 0.7%    |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s        | 1         | 0.7%    |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM DDR2 1066MT/s    | 1         | 0.7%    |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s      | 1         | 0.7%    |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s     | 1         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 69        | 65.09%  |
| DDR3   | 28        | 26.42%  |
| LPDDR4 | 5         | 4.72%   |
| LPDDR3 | 2         | 1.89%   |
| SDRAM  | 1         | 0.94%   |
| DDR2   | 1         | 0.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 98        | 95.15%  |
| Row Of Chips | 5         | 4.85%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 55        | 46.22%  |
| 4096  | 42        | 35.29%  |
| 16384 | 9         | 7.56%   |
| 2048  | 8         | 6.72%   |
| 32768 | 4         | 3.36%   |
| 1024  | 1         | 0.84%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 34        | 29.57%  |
| 3200  | 22        | 19.13%  |
| 1600  | 20        | 17.39%  |
| 2400  | 11        | 9.57%   |
| 2133  | 10        | 8.7%    |
| 1067  | 5         | 4.35%   |
| 1334  | 3         | 2.61%   |
| 3266  | 2         | 1.74%   |
| 1333  | 2         | 1.74%   |
| 8400  | 1         | 0.87%   |
| 4267  | 1         | 0.87%   |
| 4199  | 1         | 0.87%   |
| 2134  | 1         | 0.87%   |
| 1867  | 1         | 0.87%   |
| 1066  | 1         | 0.87%   |

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
| Chicony Electronics                    | 41        | 23.03%  |
| IMC Networks                           | 35        | 19.66%  |
| Cheng Uei Precision Industry (Foxlink) | 17        | 9.55%   |
| Realtek Semiconductor                  | 12        | 6.74%   |
| Quanta                                 | 11        | 6.18%   |
| Microdia                               | 11        | 6.18%   |
| Sunplus Innovation Technology          | 10        | 5.62%   |
| Bison Electronics                      | 9         | 5.06%   |
| Lite-On Technology                     | 7         | 3.93%   |
| Suyin                                  | 5         | 2.81%   |
| Luxvisions Innotech Limited            | 5         | 2.81%   |
| Acer                                   | 3         | 1.69%   |
| Syntek                                 | 2         | 1.12%   |
| Sonix Technology                       | 2         | 1.12%   |
| Silicon Motion                         | 2         | 1.12%   |
| Primax Electronics                     | 2         | 1.12%   |
| Apple                                  | 2         | 1.12%   |
| Importek                               | 1         | 0.56%   |
| Alcor Micro                            | 1         | 0.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 12        | 6.74%   |
| Chicony USB2.0 VGA UVC WebCam                           | 11        | 6.18%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 10        | 5.62%   |
| Chicony HD WebCam                                       | 6         | 3.37%   |
| Microdia Integrated_Webcam_HD                           | 5         | 2.81%   |
| IMC Networks VGA UVC WebCam                             | 5         | 2.81%   |
| Luxvisions Innotech Limited HP HD Camera                | 4         | 2.25%   |
| Lite-On HP HD Camera                                    | 4         | 2.25%   |
| IMC Networks Integrated Camera                          | 4         | 2.25%   |
| Suyin Integrated_Webcam_HD                              | 3         | 1.69%   |
| Realtek Integrated_Webcam_HD                            | 3         | 1.69%   |
| IMC Networks USB2.0 HD IR UVC WebCam                    | 3         | 1.69%   |
| Chicony HP HD Camera                                    | 3         | 1.69%   |
| Chicony EasyCamera                                      | 3         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 3         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 1.69%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 3         | 1.69%   |
| Bison HD Webcam                                         | 3         | 1.69%   |
| Suyin HP Truevision HD                                  | 2         | 1.12%   |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 1.12%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.12%   |
| Realtek USB2.0 VGA UVC WebCam                           | 2         | 1.12%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 1.12%   |
| Quanta VGA WebCam                                       | 2         | 1.12%   |
| Quanta HP HD Camera                                     | 2         | 1.12%   |
| Quanta HD Webcam                                        | 2         | 1.12%   |
| Quanta HD User Facing                                   | 2         | 1.12%   |
| Primax HP HD Webcam [Fixed]                             | 2         | 1.12%   |
| Microdia HP Webcam-101                                  | 2         | 1.12%   |
| Lite-On Integrated Camera                               | 2         | 1.12%   |
| Chicony USB2.0 HD UVC WebCam                            | 2         | 1.12%   |
| Chicony USB2.0 Camera                                   | 2         | 1.12%   |
| Chicony Integrated Camera                               | 2         | 1.12%   |
| Chicony HP Truevision HD camera                         | 2         | 1.12%   |
| Chicony HP HD Webcam                                    | 2         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam     | 2         | 1.12%   |
| Bison Lenovo EasyCamera                                 | 2         | 1.12%   |
| Bison Integrated Camera                                 | 2         | 1.12%   |
| Bison EasyCamera                                        | 2         | 1.12%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 27        | 79.41%  |
| Synaptics                  | 3         | 8.82%   |
| Elan Microelectronics      | 2         | 5.88%   |
| Upek                       | 1         | 2.94%   |
| Shenzhen Goodix Technology | 1         | 2.94%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 44.12%  |
| Validity Sensors VFS491                                                    | 4         | 11.76%  |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 8.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 5.88%   |
| Elan ELAN:Fingerprint                                                      | 2         | 5.88%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.94%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.94%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.94%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.94%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.94%   |
| Synaptics  WBDI                                                            | 1         | 2.94%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.94%   |

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
| 0     | 134       | 65.69%  |
| 1     | 62        | 30.39%  |
| 2     | 6         | 2.94%   |
| 5     | 1         | 0.49%   |
| 3     | 1         | 0.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 34        | 43.59%  |
| Graphics card         | 19        | 24.36%  |
| Chipcard              | 6         | 7.69%   |
| Net/wireless          | 5         | 6.41%   |
| Camera                | 5         | 6.41%   |
| Bluetooth             | 4         | 5.13%   |
| Multimedia controller | 3         | 3.85%   |
| Sound                 | 1         | 1.28%   |
| Card reader           | 1         | 1.28%   |

