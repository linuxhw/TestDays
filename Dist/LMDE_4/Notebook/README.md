LMDE 4 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for LMDE 4.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 347

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | AOD270                      | [b53cedd40c](https://linux-hardware.org/?probe=b53cedd40c) | Apr 23, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [6fbd04d8fd](https://linux-hardware.org/?probe=6fbd04d8fd) | Apr 11, 2022 |
| ASUSTek       | 901                         | [d118ee90d5](https://linux-hardware.org/?probe=d118ee90d5) | Apr 01, 2022 |
| Lenovo        | IdeaPad S110 20126          | [9113320f2f](https://linux-hardware.org/?probe=9113320f2f) | Mar 31, 2022 |
| Lenovo        | IdeaPad S110 20126          | [d02cab0935](https://linux-hardware.org/?probe=d02cab0935) | Mar 30, 2022 |
| Dell          | Latitude D620               | [172cd26e35](https://linux-hardware.org/?probe=172cd26e35) | Mar 26, 2022 |
| HP            | ProBook 6465b               | [2e1792442b](https://linux-hardware.org/?probe=2e1792442b) | Mar 24, 2022 |
| HP            | ProBook 6465b               | [51a296abf8](https://linux-hardware.org/?probe=51a296abf8) | Mar 24, 2022 |
| Acer          | TravelMate 420              | [13cae0e399](https://linux-hardware.org/?probe=13cae0e399) | Mar 14, 2022 |
| Lenovo        | IdeaPad Z470                | [b1ca65b3e0](https://linux-hardware.org/?probe=b1ca65b3e0) | Mar 08, 2022 |
| ASUSTek       | X101CH                      | [486f5c28ad](https://linux-hardware.org/?probe=486f5c28ad) | Mar 07, 2022 |
| Dell          | Latitude D620               | [d4e50f40f3](https://linux-hardware.org/?probe=d4e50f40f3) | Mar 06, 2022 |
| HP            | ENVY 6                      | [23f60a7428](https://linux-hardware.org/?probe=23f60a7428) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z470                | [d163816373](https://linux-hardware.org/?probe=d163816373) | Mar 02, 2022 |
| ASUSTek       | UX490UAR                    | [6b6c4bd7b7](https://linux-hardware.org/?probe=6b6c4bd7b7) | Feb 28, 2022 |
| ASUSTek       | UX490UAR                    | [544979fc4f](https://linux-hardware.org/?probe=544979fc4f) | Feb 27, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | [4bd308dadf](https://linux-hardware.org/?probe=4bd308dadf) | Feb 26, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | [ec2491adc1](https://linux-hardware.org/?probe=ec2491adc1) | Feb 26, 2022 |
| Acer          | Swift SF315-52              | [74009233c2](https://linux-hardware.org/?probe=74009233c2) | Feb 19, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [e2ab1c19df](https://linux-hardware.org/?probe=e2ab1c19df) | Feb 18, 2022 |
| HP            | Laptop 14-bs0xx             | [2b5b67148b](https://linux-hardware.org/?probe=2b5b67148b) | Feb 18, 2022 |
| EVOO          | EVC141-12                   | [25710a76b8](https://linux-hardware.org/?probe=25710a76b8) | Feb 18, 2022 |
| Samsung       | NC210/NC110                 | [bf2672168d](https://linux-hardware.org/?probe=bf2672168d) | Feb 14, 2022 |
| Samsung       | NC210/NC110                 | [bcbb1884aa](https://linux-hardware.org/?probe=bcbb1884aa) | Feb 13, 2022 |
| ASUSTek       | X101CH                      | [82661c6a9b](https://linux-hardware.org/?probe=82661c6a9b) | Feb 12, 2022 |
| ASUSTek       | 901                         | [27a497fdf8](https://linux-hardware.org/?probe=27a497fdf8) | Feb 04, 2022 |
| Acer          | Aspire 3820                 | [e6091c93a9](https://linux-hardware.org/?probe=e6091c93a9) | Feb 02, 2022 |
| Toshiba       | Satellite A200              | [9086ec49b6](https://linux-hardware.org/?probe=9086ec49b6) | Jan 21, 2022 |
| LG Electro... | A530-T.BE76P1               | [9fdbf19ebf](https://linux-hardware.org/?probe=9fdbf19ebf) | Jan 09, 2022 |
| Google        | Falco                       | [f450676688](https://linux-hardware.org/?probe=f450676688) | Jan 09, 2022 |
| Packard Be... | EasyNote TE69BM             | [526fc1b476](https://linux-hardware.org/?probe=526fc1b476) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | [675eb28882](https://linux-hardware.org/?probe=675eb28882) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | [203577c78f](https://linux-hardware.org/?probe=203577c78f) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | [41e93113b5](https://linux-hardware.org/?probe=41e93113b5) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | [c977f6d6af](https://linux-hardware.org/?probe=c977f6d6af) | Jan 05, 2022 |
| ASUSTek       | K46CA                       | [61978f9418](https://linux-hardware.org/?probe=61978f9418) | Jan 04, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [9d4bddea4d](https://linux-hardware.org/?probe=9d4bddea4d) | Jan 03, 2022 |
| Advent        | Monza T100                  | [7355d1ae53](https://linux-hardware.org/?probe=7355d1ae53) | Dec 23, 2021 |
| Acer          | Aspire V5-573G              | [4c03d73b65](https://linux-hardware.org/?probe=4c03d73b65) | Dec 18, 2021 |
| HP            | Pavilion 14                 | [be9e6368e4](https://linux-hardware.org/?probe=be9e6368e4) | Dec 17, 2021 |
| Acer          | Aspire 3820                 | [b2f24124da](https://linux-hardware.org/?probe=b2f24124da) | Dec 14, 2021 |
| Acer          | Aspire 3820                 | [c4ed088328](https://linux-hardware.org/?probe=c4ed088328) | Dec 14, 2021 |
| Sony          | VPCP116KG                   | [237c9f66e1](https://linux-hardware.org/?probe=237c9f66e1) | Dec 13, 2021 |
| Fujitsu       | STYLISTIC Q550              | [e5d7b73e7f](https://linux-hardware.org/?probe=e5d7b73e7f) | Dec 12, 2021 |
| Fujitsu       | STYLISTIC Q550              | [8138236f20](https://linux-hardware.org/?probe=8138236f20) | Dec 12, 2021 |
| Lenovo        | G40-30 80FY                 | [43ff865e00](https://linux-hardware.org/?probe=43ff865e00) | Nov 28, 2021 |
| HP            | Pavilion dv6                | [5300296119](https://linux-hardware.org/?probe=5300296119) | Nov 27, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [bb0a461d82](https://linux-hardware.org/?probe=bb0a461d82) | Nov 21, 2021 |
| Lenovo        | G50-45 80E3                 | [024686087f](https://linux-hardware.org/?probe=024686087f) | Nov 20, 2021 |
| Samsung       | 305U1A                      | [c602ad4903](https://linux-hardware.org/?probe=c602ad4903) | Nov 18, 2021 |
| Acer          | Aspire 3000                 | [86d2f89f59](https://linux-hardware.org/?probe=86d2f89f59) | Nov 12, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [688e4047ce](https://linux-hardware.org/?probe=688e4047ce) | Nov 11, 2021 |
| Acer          | Aspire 3000                 | [dad287d5a1](https://linux-hardware.org/?probe=dad287d5a1) | Nov 11, 2021 |
| Toshiba       | Satellite L50-C             | [5a9ebbcad0](https://linux-hardware.org/?probe=5a9ebbcad0) | Nov 09, 2021 |
| Acer          | Aspire E5-411               | [0155c64e23](https://linux-hardware.org/?probe=0155c64e23) | Nov 04, 2021 |
| Acer          | Aspire E5-411               | [63287ab4e6](https://linux-hardware.org/?probe=63287ab4e6) | Nov 02, 2021 |
| Dell          | Latitude D630               | [ac9f57ab8f](https://linux-hardware.org/?probe=ac9f57ab8f) | Nov 02, 2021 |
| TUXEDO        | BC1510 1710                 | [90be7d16be](https://linux-hardware.org/?probe=90be7d16be) | Oct 24, 2021 |
| TUXEDO        | BC1510 1710                 | [49b52175c5](https://linux-hardware.org/?probe=49b52175c5) | Oct 24, 2021 |
| Acer          | Aspire A315-55G             | [5b965ea234](https://linux-hardware.org/?probe=5b965ea234) | Oct 17, 2021 |
| Acer          | Aspire A315-55G             | [3a5976d4eb](https://linux-hardware.org/?probe=3a5976d4eb) | Oct 17, 2021 |
| Acer          | Swift SF515-51T             | [203a3b399d](https://linux-hardware.org/?probe=203a3b399d) | Oct 13, 2021 |
| Medion        | P6670 MD99960               | [eaa186d207](https://linux-hardware.org/?probe=eaa186d207) | Oct 12, 2021 |
| Medion        | P6670 MD99960               | [d42f345fc5](https://linux-hardware.org/?probe=d42f345fc5) | Oct 12, 2021 |
| HP            | 520                         | [4aea2d24b1](https://linux-hardware.org/?probe=4aea2d24b1) | Oct 10, 2021 |
| Dell          | Precision M2800             | [b046a9dfe3](https://linux-hardware.org/?probe=b046a9dfe3) | Oct 08, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | [633c289440](https://linux-hardware.org/?probe=633c289440) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | [a6d07be7c9](https://linux-hardware.org/?probe=a6d07be7c9) | Sep 27, 2021 |
| Apple         | MacBookPro5,4               | [d5625a9406](https://linux-hardware.org/?probe=d5625a9406) | Sep 24, 2021 |
| Sony          | VPCS131FM                   | [b5bba0e07f](https://linux-hardware.org/?probe=b5bba0e07f) | Sep 22, 2021 |
| Sony          | VPCS131FM                   | [54923e2372](https://linux-hardware.org/?probe=54923e2372) | Sep 22, 2021 |
| Qbex          | UDPAIOQBEX01                | [34c385cfe4](https://linux-hardware.org/?probe=34c385cfe4) | Sep 13, 2021 |
| Acer          | Aspire 4320                 | [fae514c059](https://linux-hardware.org/?probe=fae514c059) | Sep 12, 2021 |
| IBM           | ThinkPad T41 23737JY        | [86cf78a3cf](https://linux-hardware.org/?probe=86cf78a3cf) | Sep 09, 2021 |
| HP            | 250 G2                      | [64f9cfdbab](https://linux-hardware.org/?probe=64f9cfdbab) | Sep 09, 2021 |
| HP            | 250 G2                      | [4fb0a2eab3](https://linux-hardware.org/?probe=4fb0a2eab3) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | [10052076e0](https://linux-hardware.org/?probe=10052076e0) | Sep 09, 2021 |
| Acer          | Aspire A315-31              | [8a0df29327](https://linux-hardware.org/?probe=8a0df29327) | Sep 09, 2021 |
| LG Electro... | A530-T.BE76P1               | [844d7b2492](https://linux-hardware.org/?probe=844d7b2492) | Sep 09, 2021 |
| Matsushita... | CF-19DDGZXVM                | [6f54a42d76](https://linux-hardware.org/?probe=6f54a42d76) | Sep 08, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [fdb725803b](https://linux-hardware.org/?probe=fdb725803b) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | [52474e968d](https://linux-hardware.org/?probe=52474e968d) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | [c4e6145a5f](https://linux-hardware.org/?probe=c4e6145a5f) | Sep 01, 2021 |
| Dell          | XPS M1330                   | [9dbd1f4ad9](https://linux-hardware.org/?probe=9dbd1f4ad9) | Aug 28, 2021 |
| ASUSTek       | 1201HA                      | [eadb8752c9](https://linux-hardware.org/?probe=eadb8752c9) | Aug 28, 2021 |
| HP            | Pavilion dv2000 (RD665EA... | [3b6dfaf6db](https://linux-hardware.org/?probe=3b6dfaf6db) | Aug 25, 2021 |
| Fujitsu       | LIFEBOOK A556/G             | [7706314dbc](https://linux-hardware.org/?probe=7706314dbc) | Aug 24, 2021 |
| Itautec       | W7655                       | [82b2d38326](https://linux-hardware.org/?probe=82b2d38326) | Aug 24, 2021 |
| Itautec       | W7655                       | [5952ec3a0f](https://linux-hardware.org/?probe=5952ec3a0f) | Aug 24, 2021 |
| HP            | 14                          | [e6bbdc5a92](https://linux-hardware.org/?probe=e6bbdc5a92) | Aug 24, 2021 |
| ASUSTek       | M51Sn                       | [5acb8c28ad](https://linux-hardware.org/?probe=5acb8c28ad) | Aug 21, 2021 |
| Packard Be... | EasyNote_NJ66               | [03c09865f3](https://linux-hardware.org/?probe=03c09865f3) | Aug 19, 2021 |
| ASUSTek       | N550JV                      | [f56a2bd3fa](https://linux-hardware.org/?probe=f56a2bd3fa) | Aug 14, 2021 |
| Toshiba       | Satellite M100              | [8dff0ec788](https://linux-hardware.org/?probe=8dff0ec788) | Aug 10, 2021 |
| Toshiba       | Satellite M100              | [06e766539d](https://linux-hardware.org/?probe=06e766539d) | Aug 10, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [8648635717](https://linux-hardware.org/?probe=8648635717) | Aug 07, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [16bec20604](https://linux-hardware.org/?probe=16bec20604) | Aug 06, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [dec7f65882](https://linux-hardware.org/?probe=dec7f65882) | Aug 06, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [53ee243536](https://linux-hardware.org/?probe=53ee243536) | Aug 01, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [eafe3a403f](https://linux-hardware.org/?probe=eafe3a403f) | Jul 30, 2021 |
| Toshiba       | Satellite L855              | [354b3bf7c6](https://linux-hardware.org/?probe=354b3bf7c6) | Jul 30, 2021 |
| ASUSTek       | 1201NL                      | [1ff8ed5a66](https://linux-hardware.org/?probe=1ff8ed5a66) | Jul 29, 2021 |
| ASUSTek       | 1201NL                      | [78fb5dfca9](https://linux-hardware.org/?probe=78fb5dfca9) | Jul 29, 2021 |
| HP            | EliteBook 8470p             | [5ea0d9d644](https://linux-hardware.org/?probe=5ea0d9d644) | Jul 29, 2021 |
| Dell          | Inspiron 15-3567            | [19a4054ab4](https://linux-hardware.org/?probe=19a4054ab4) | Jul 28, 2021 |
| Dell          | Inspiron 15-3567            | [bc64d314a1](https://linux-hardware.org/?probe=bc64d314a1) | Jul 28, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [10ca362cf0](https://linux-hardware.org/?probe=10ca362cf0) | Jul 19, 2021 |
| Dell          | XPS M1330                   | [55de50364d](https://linux-hardware.org/?probe=55de50364d) | Jul 17, 2021 |
| HP            | Compaq nc6400 (RH478EA#A... | [a3f3785bc1](https://linux-hardware.org/?probe=a3f3785bc1) | Jul 15, 2021 |
| Dell          | Latitude E5520              | [9278405254](https://linux-hardware.org/?probe=9278405254) | Jul 13, 2021 |
| Fujitsu Si... | AMILO Pa 2510               | [a4303cc0cf](https://linux-hardware.org/?probe=a4303cc0cf) | Jul 12, 2021 |
| Qbex          | UDPAIOQBEX01                | [9b96573429](https://linux-hardware.org/?probe=9b96573429) | Jul 11, 2021 |
| Dell          | Inspiron 1526               | [515fc96089](https://linux-hardware.org/?probe=515fc96089) | Jul 11, 2021 |
| ASUSTek       | M6Ne                        | [ae1c7d3df6](https://linux-hardware.org/?probe=ae1c7d3df6) | Jul 11, 2021 |
| Dell          | Inspiron 7520               | [fbc1ae17b4](https://linux-hardware.org/?probe=fbc1ae17b4) | Jul 10, 2021 |
| Dell          | Inspiron 7520               | [e9bbf0622c](https://linux-hardware.org/?probe=e9bbf0622c) | Jul 10, 2021 |
| HP            | Laptop 14-df0xxx            | [ce0ac9c2fe](https://linux-hardware.org/?probe=ce0ac9c2fe) | Jul 10, 2021 |
| Samsung       | R59/R60/R61                 | [c0f5798a5b](https://linux-hardware.org/?probe=c0f5798a5b) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [f9a80b7b6b](https://linux-hardware.org/?probe=f9a80b7b6b) | Jun 28, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [c7ddbbda0a](https://linux-hardware.org/?probe=c7ddbbda0a) | Jun 27, 2021 |
| Lenovo        | ThinkPad X100e 28762FP      | [95661d2e39](https://linux-hardware.org/?probe=95661d2e39) | Jun 27, 2021 |
| SAELITE       | ES1AU11                     | [267ea9c15e](https://linux-hardware.org/?probe=267ea9c15e) | Jun 26, 2021 |
| Acer          | Aspire 3000                 | [d0c68c57a8](https://linux-hardware.org/?probe=d0c68c57a8) | Jun 26, 2021 |
| Samsung       | RV413/RV513                 | [f6aab08062](https://linux-hardware.org/?probe=f6aab08062) | Jun 26, 2021 |
| Gateway       | M675                        | [ebdf5aa678](https://linux-hardware.org/?probe=ebdf5aa678) | Jun 25, 2021 |
| Acer          | Aspire one                  | [adae8c183d](https://linux-hardware.org/?probe=adae8c183d) | Jun 22, 2021 |
| HP            | Compaq nc6400 (RH478EA#A... | [b96ab4b06e](https://linux-hardware.org/?probe=b96ab4b06e) | Jun 18, 2021 |
| HP            | Presario R4100 (EC375UA#... | [9072bce23d](https://linux-hardware.org/?probe=9072bce23d) | Jun 17, 2021 |
| HP            | Presario R4100 (EC375UA#... | [b557ccbf94](https://linux-hardware.org/?probe=b557ccbf94) | Jun 17, 2021 |
| Dell          | Latitude E6410              | [bd3a2db03c](https://linux-hardware.org/?probe=bd3a2db03c) | Jun 16, 2021 |
| HP            | Notebook                    | [611efdde0d](https://linux-hardware.org/?probe=611efdde0d) | Jun 15, 2021 |
| ASUSTek       | X550LN                      | [67bbff8363](https://linux-hardware.org/?probe=67bbff8363) | Jun 11, 2021 |
| Gateway       | LT40                        | [fe2551cb8b](https://linux-hardware.org/?probe=fe2551cb8b) | Jun 11, 2021 |
| Acer          | Aspire 3000                 | [f6a944ee4a](https://linux-hardware.org/?probe=f6a944ee4a) | Jun 09, 2021 |
| Sony          | VPCEB3L1E                   | [bc3c3b537b](https://linux-hardware.org/?probe=bc3c3b537b) | Jun 06, 2021 |
| HP            | Laptop 15-dw0xxx            | [4f752689ed](https://linux-hardware.org/?probe=4f752689ed) | Jun 03, 2021 |
| Gateway       | LT40                        | [6a966fe471](https://linux-hardware.org/?probe=6a966fe471) | Jun 01, 2021 |
| ASUSTek       | X555UJ                      | [9c148a1665](https://linux-hardware.org/?probe=9c148a1665) | May 25, 2021 |
| HP            | Pavilion dv6                | [fb309a7f37](https://linux-hardware.org/?probe=fb309a7f37) | May 17, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
| ASUSTek       | X550LN                      | [4f117c46f3](https://linux-hardware.org/?probe=4f117c46f3) | May 09, 2021 |
| Acer          | Aspire E5-571               | [2c91167099](https://linux-hardware.org/?probe=2c91167099) | May 07, 2021 |
| Acer          | Aspire E5-571               | [c0b2f54ba4](https://linux-hardware.org/?probe=c0b2f54ba4) | May 07, 2021 |
| HP            | 530                         | [e94b7216d1](https://linux-hardware.org/?probe=e94b7216d1) | May 06, 2021 |
| HP            | 530                         | [8e3d65488a](https://linux-hardware.org/?probe=8e3d65488a) | May 06, 2021 |
| Acer          | Aspire A515-41G             | [38e06153e9](https://linux-hardware.org/?probe=38e06153e9) | May 04, 2021 |
| Dell          | Inspiron 7520               | [3a72f19dd7](https://linux-hardware.org/?probe=3a72f19dd7) | May 01, 2021 |
| Toshiba       | dynabook Satellite J61 1... | [0b4c4a93f1](https://linux-hardware.org/?probe=0b4c4a93f1) | Apr 29, 2021 |
| Lenovo        | ThinkPad X60 1706AA7        | [34a54e1198](https://linux-hardware.org/?probe=34a54e1198) | Apr 27, 2021 |
| Lenovo        | ThinkPad SL510 28752NG      | [66346c1594](https://linux-hardware.org/?probe=66346c1594) | Apr 26, 2021 |
| Unknown       | Unknown                     | [e45a412c3d](https://linux-hardware.org/?probe=e45a412c3d) | Apr 26, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [f961a0339b](https://linux-hardware.org/?probe=f961a0339b) | Apr 22, 2021 |
| HP            | Pavilion dv7                | [662a781c83](https://linux-hardware.org/?probe=662a781c83) | Apr 22, 2021 |
| HP            | Pavilion dv7                | [edf38b6c4a](https://linux-hardware.org/?probe=edf38b6c4a) | Apr 21, 2021 |
| HP            | 255 G7 Notebook PC          | [b243c0380f](https://linux-hardware.org/?probe=b243c0380f) | Apr 21, 2021 |
| HP            | Pavilion dv7                | [0c3668cad6](https://linux-hardware.org/?probe=0c3668cad6) | Apr 19, 2021 |
| Toshiba       | NI 1403                     | [a3789d1a53](https://linux-hardware.org/?probe=a3789d1a53) | Apr 15, 2021 |
| HP            | Pavilion dv5                | [2df1512442](https://linux-hardware.org/?probe=2df1512442) | Apr 12, 2021 |
| HP            | Pavilion dv5                | [963a9c98df](https://linux-hardware.org/?probe=963a9c98df) | Apr 12, 2021 |
| ASUSTek       | X101CH                      | [c1b96ff3fa](https://linux-hardware.org/?probe=c1b96ff3fa) | Apr 04, 2021 |
| LG Electro... | X300-L.CR31B1               | [728ce1cec3](https://linux-hardware.org/?probe=728ce1cec3) | Apr 02, 2021 |
| HP            | Mini 210-1100               | [4b8539128d](https://linux-hardware.org/?probe=4b8539128d) | Apr 01, 2021 |
| HP            | Mini 210-1100               | [a2a1a61099](https://linux-hardware.org/?probe=a2a1a61099) | Apr 01, 2021 |
| LG Electro... | X300-L.CR31B1               | [2dee5439bd](https://linux-hardware.org/?probe=2dee5439bd) | Apr 01, 2021 |
| HP            | Compaq 6530b (GW688AV#AK... | [4644bc75a5](https://linux-hardware.org/?probe=4644bc75a5) | Mar 29, 2021 |
| HP            | Unknown                     | [984ec41c5f](https://linux-hardware.org/?probe=984ec41c5f) | Mar 28, 2021 |
| HP            | Unknown                     | [2f594364bb](https://linux-hardware.org/?probe=2f594364bb) | Mar 20, 2021 |
| Toshiba       | Satellite L750              | [06207199fa](https://linux-hardware.org/?probe=06207199fa) | Mar 16, 2021 |
| ASUSTek       | X542UAR                     | [4a2b4a2f3d](https://linux-hardware.org/?probe=4a2b4a2f3d) | Mar 15, 2021 |
| ASUSTek       | X542UAR                     | [824a5703c6](https://linux-hardware.org/?probe=824a5703c6) | Mar 15, 2021 |
| Sony          | VGN-FZ140E                  | [1d611ce57d](https://linux-hardware.org/?probe=1d611ce57d) | Mar 13, 2021 |
| Sony          | VGN-FZ140E                  | [3bfba9b2a3](https://linux-hardware.org/?probe=3bfba9b2a3) | Mar 13, 2021 |
| ASUSTek       | K46CA                       | [553bb797b4](https://linux-hardware.org/?probe=553bb797b4) | Mar 09, 2021 |
| HP            | EliteBook 8540w             | [8589da1141](https://linux-hardware.org/?probe=8589da1141) | Mar 06, 2021 |
| Lenovo        | ThinkPad T400 64741EG       | [1d54256d1d](https://linux-hardware.org/?probe=1d54256d1d) | Mar 04, 2021 |
| HP            | Compaq Presario CQ71        | [fba2e0f27a](https://linux-hardware.org/?probe=fba2e0f27a) | Mar 01, 2021 |
| HP            | Compaq Presario CQ71        | [65e004cebd](https://linux-hardware.org/?probe=65e004cebd) | Mar 01, 2021 |
| HP            | Compaq nx7400 (EY294ET#A... | [b253d7d3fa](https://linux-hardware.org/?probe=b253d7d3fa) | Mar 01, 2021 |
| Dell          | Inspiron 5559               | [0ca0e1f04f](https://linux-hardware.org/?probe=0ca0e1f04f) | Feb 28, 2021 |
| Dell          | Inspiron 5559               | [0dcf8f701e](https://linux-hardware.org/?probe=0dcf8f701e) | Feb 27, 2021 |
| Samsung       | NC10                        | [968b0bf5ba](https://linux-hardware.org/?probe=968b0bf5ba) | Feb 26, 2021 |
| HP            | Pavilion dv6                | [1baf6f6c70](https://linux-hardware.org/?probe=1baf6f6c70) | Feb 26, 2021 |
| Lenovo        | Y50-70 20378                | [b0a6138136](https://linux-hardware.org/?probe=b0a6138136) | Feb 25, 2021 |
| Acer          | Aspire 7750G                | [68c2e2956e](https://linux-hardware.org/?probe=68c2e2956e) | Feb 21, 2021 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [078eb9c9b9](https://linux-hardware.org/?probe=078eb9c9b9) | Feb 19, 2021 |
| Acer          | Aspire 6930ZG               | [5e2260251a](https://linux-hardware.org/?probe=5e2260251a) | Feb 19, 2021 |
| Google        | Gnawty                      | [f2d007d3b0](https://linux-hardware.org/?probe=f2d007d3b0) | Feb 16, 2021 |
| Google        | Gnawty                      | [cf74012060](https://linux-hardware.org/?probe=cf74012060) | Feb 16, 2021 |
| Google        | Gnawty                      | [802daa9713](https://linux-hardware.org/?probe=802daa9713) | Feb 16, 2021 |
| Dell          | Latitude E6520              | [132c1f74fc](https://linux-hardware.org/?probe=132c1f74fc) | Feb 14, 2021 |
| Notebook      | WID2010                     | [289d2b0685](https://linux-hardware.org/?probe=289d2b0685) | Feb 10, 2021 |
| LG Electro... | X120-G.C7VPG                | [349c20610a](https://linux-hardware.org/?probe=349c20610a) | Feb 10, 2021 |
| Dell          | Inspiron 7520               | [f4995bc45c](https://linux-hardware.org/?probe=f4995bc45c) | Feb 07, 2021 |
| Acer          | Aspire 5630                 | [26e90cd431](https://linux-hardware.org/?probe=26e90cd431) | Feb 02, 2021 |
| Acer          | Aspire 5630                 | [61a1c29323](https://linux-hardware.org/?probe=61a1c29323) | Feb 02, 2021 |
| Maibenben     | XiaoMai5                    | [bd1f26e401](https://linux-hardware.org/?probe=bd1f26e401) | Feb 01, 2021 |
| Toshiba       | Satellite C50-A-1DN         | [b5e359a765](https://linux-hardware.org/?probe=b5e359a765) | Jan 28, 2021 |
| Toshiba       | Satellite C50-A-1DN         | [701f078d13](https://linux-hardware.org/?probe=701f078d13) | Jan 28, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [4845dac1e6](https://linux-hardware.org/?probe=4845dac1e6) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [f86be88365](https://linux-hardware.org/?probe=f86be88365) | Jan 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [e6066c8531](https://linux-hardware.org/?probe=e6066c8531) | Jan 26, 2021 |
| ASUSTek       | F5N                         | [5a1b1f9f7a](https://linux-hardware.org/?probe=5a1b1f9f7a) | Jan 26, 2021 |
| Sony          | SVE1511N1ESI                | [aa8a372738](https://linux-hardware.org/?probe=aa8a372738) | Jan 23, 2021 |
| Sony          | SVE1511N1ESI                | [69689785e4](https://linux-hardware.org/?probe=69689785e4) | Jan 22, 2021 |
| Matsushita... | CF-19CHB23BE                | [e9fa72450f](https://linux-hardware.org/?probe=e9fa72450f) | Jan 14, 2021 |
| Acer          | Aspire 5930                 | [0826a741c2](https://linux-hardware.org/?probe=0826a741c2) | Jan 13, 2021 |
| Acer          | Aspire 5930                 | [e9f548f926](https://linux-hardware.org/?probe=e9f548f926) | Jan 13, 2021 |
| Dell          | Inspiron 7520               | [f894e05226](https://linux-hardware.org/?probe=f894e05226) | Jan 09, 2021 |
| Acer          | AOD270                      | [89562751d7](https://linux-hardware.org/?probe=89562751d7) | Jan 08, 2021 |
| Exper         | E10IL1                      | [8a1f9ff144](https://linux-hardware.org/?probe=8a1f9ff144) | Dec 31, 2020 |
| Dell          | Precision M4800             | [10bfd0b228](https://linux-hardware.org/?probe=10bfd0b228) | Dec 27, 2020 |
| ASUSTek       | K55N                        | [e3edf30a97](https://linux-hardware.org/?probe=e3edf30a97) | Dec 26, 2020 |
| ASUSTek       | K55N                        | [d7630d7410](https://linux-hardware.org/?probe=d7630d7410) | Dec 26, 2020 |
| Apple         | MacBookPro5,5               | [95d4d575bf](https://linux-hardware.org/?probe=95d4d575bf) | Dec 26, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | [c0f1039074](https://linux-hardware.org/?probe=c0f1039074) | Dec 24, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | [5584ad5871](https://linux-hardware.org/?probe=5584ad5871) | Dec 24, 2020 |
| Dell          | Inspiron 1010               | [0b958b270d](https://linux-hardware.org/?probe=0b958b270d) | Dec 22, 2020 |
| Dell          | Inspiron 1010               | [94d64e448f](https://linux-hardware.org/?probe=94d64e448f) | Dec 21, 2020 |
| Acer          | Aspire 5735                 | [d1a973f77f](https://linux-hardware.org/?probe=d1a973f77f) | Dec 21, 2020 |
| Acer          | Aspire 5735                 | [a9ece8f5d0](https://linux-hardware.org/?probe=a9ece8f5d0) | Dec 21, 2020 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | [7f143b3e74](https://linux-hardware.org/?probe=7f143b3e74) | Dec 20, 2020 |
| Unknown       | Unknown                     | [64b25942e1](https://linux-hardware.org/?probe=64b25942e1) | Dec 20, 2020 |
| Toshiba       | NI 1403                     | [192f91ada6](https://linux-hardware.org/?probe=192f91ada6) | Dec 19, 2020 |
| Exo           | Unknown                     | [a6c445344b](https://linux-hardware.org/?probe=a6c445344b) | Dec 17, 2020 |
| Lenovo        | ThinkPad T440p 20AWA1NAU... | [1b627fe180](https://linux-hardware.org/?probe=1b627fe180) | Dec 15, 2020 |
| Acer          | Aspire one                  | [556332908d](https://linux-hardware.org/?probe=556332908d) | Dec 14, 2020 |
| HP            | Laptop 15-bw0xx             | [dc7e6d3f5d](https://linux-hardware.org/?probe=dc7e6d3f5d) | Dec 14, 2020 |
| HP            | Pavilion ze2000 (EA772AV... | [15284f8c6e](https://linux-hardware.org/?probe=15284f8c6e) | Dec 07, 2020 |
| Dell          | Precision M4600             | [690e349224](https://linux-hardware.org/?probe=690e349224) | Dec 06, 2020 |
| Dell          | Precision M4600             | [f2023ec8ae](https://linux-hardware.org/?probe=f2023ec8ae) | Dec 06, 2020 |
| Acer          | Extensa 4620                | [1bda4268f4](https://linux-hardware.org/?probe=1bda4268f4) | Dec 04, 2020 |
| Matsushita... | CF-19CHB23BE                | [a81d111827](https://linux-hardware.org/?probe=a81d111827) | Nov 25, 2020 |
| ASUSTek       | X550VX                      | [b22a35a959](https://linux-hardware.org/?probe=b22a35a959) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [18d99f9e4f](https://linux-hardware.org/?probe=18d99f9e4f) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [c17dc0982c](https://linux-hardware.org/?probe=c17dc0982c) | Nov 22, 2020 |
| Lenovo        | ThinkPad T60p 8742C4G       | [9d369e30fd](https://linux-hardware.org/?probe=9d369e30fd) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | [dbac4eb570](https://linux-hardware.org/?probe=dbac4eb570) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | [b070b2d112](https://linux-hardware.org/?probe=b070b2d112) | Nov 18, 2020 |
| HP            | Compaq Presario CQ60        | [c9f4c7eefd](https://linux-hardware.org/?probe=c9f4c7eefd) | Nov 16, 2020 |
| HP            | Unknown                     | [b525a6fdd2](https://linux-hardware.org/?probe=b525a6fdd2) | Nov 15, 2020 |
| ASUSTek       | N90SC                       | [219009d9ea](https://linux-hardware.org/?probe=219009d9ea) | Nov 13, 2020 |
| ASUSTek       | N90SC                       | [1b802fbae0](https://linux-hardware.org/?probe=1b802fbae0) | Nov 13, 2020 |
| HP            | Pavilion dv6000 (RV216UA... | [d07adf47aa](https://linux-hardware.org/?probe=d07adf47aa) | Nov 11, 2020 |
| Lenovo        | ThinkPad T420s 4174EK3      | [256f53a883](https://linux-hardware.org/?probe=256f53a883) | Nov 08, 2020 |
| Acer          | Aspire 5735                 | [3863a67ce4](https://linux-hardware.org/?probe=3863a67ce4) | Nov 07, 2020 |
| Acer          | Aspire 5735                 | [80c240fcef](https://linux-hardware.org/?probe=80c240fcef) | Nov 07, 2020 |
| HP            | Laptop 17-ca0xxx            | [ac476c2272](https://linux-hardware.org/?probe=ac476c2272) | Nov 05, 2020 |
| Dell          | Latitude 5400               | [014e9b7e76](https://linux-hardware.org/?probe=014e9b7e76) | Nov 04, 2020 |
| HP            | Laptop 17-ca0xxx            | [ab7e244449](https://linux-hardware.org/?probe=ab7e244449) | Nov 03, 2020 |
| HP            | Compaq 8510p                | [587f5db4a7](https://linux-hardware.org/?probe=587f5db4a7) | Nov 02, 2020 |
| Dell          | Latitude E6220              | [b3af9d8439](https://linux-hardware.org/?probe=b3af9d8439) | Oct 30, 2020 |
| Dell          | Latitude E6220              | [7df244c05f](https://linux-hardware.org/?probe=7df244c05f) | Oct 30, 2020 |
| Dell          | Inspiron 3521               | [c85f72911e](https://linux-hardware.org/?probe=c85f72911e) | Oct 29, 2020 |
| HP            | EliteBook 8470p             | [dd6fd8b99c](https://linux-hardware.org/?probe=dd6fd8b99c) | Oct 24, 2020 |
| ASUSTek       | X551MA                      | [bc2de7b987](https://linux-hardware.org/?probe=bc2de7b987) | Oct 23, 2020 |
| ASUSTek       | X551MA                      | [ad50a3e36d](https://linux-hardware.org/?probe=ad50a3e36d) | Oct 22, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [c00341fecd](https://linux-hardware.org/?probe=c00341fecd) | Oct 21, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [83c0ae72b0](https://linux-hardware.org/?probe=83c0ae72b0) | Oct 21, 2020 |
| Unknown       | Unknown                     | [f786cfb7ca](https://linux-hardware.org/?probe=f786cfb7ca) | Oct 18, 2020 |
| ASUSTek       | GL503VM                     | [a6705573f8](https://linux-hardware.org/?probe=a6705573f8) | Oct 11, 2020 |
| HP            | EliteBook 8470p             | [27fe34d7e1](https://linux-hardware.org/?probe=27fe34d7e1) | Oct 09, 2020 |
| Acer          | Aspire 5680                 | [3ef4868294](https://linux-hardware.org/?probe=3ef4868294) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [0053b1ef76](https://linux-hardware.org/?probe=0053b1ef76) | Oct 07, 2020 |
| Lenovo        | B71-80 80RJ                 | [a5135ffb54](https://linux-hardware.org/?probe=a5135ffb54) | Oct 04, 2020 |
| Dell          | Latitude E6400              | [5d51e1eab7](https://linux-hardware.org/?probe=5d51e1eab7) | Oct 04, 2020 |
| Unknown       | Unknown                     | [fd16de3c7f](https://linux-hardware.org/?probe=fd16de3c7f) | Oct 03, 2020 |
| Lenovo        | B71-80 80RJ                 | [7f6ed6799f](https://linux-hardware.org/?probe=7f6ed6799f) | Oct 03, 2020 |
| Positivo      | H14CU01                     | [3a0013a489](https://linux-hardware.org/?probe=3a0013a489) | Sep 28, 2020 |
| Positivo      | H14CU01                     | [e0d8261056](https://linux-hardware.org/?probe=e0d8261056) | Sep 28, 2020 |
| Dell          | Inspiron 5566               | [a93a422684](https://linux-hardware.org/?probe=a93a422684) | Sep 23, 2020 |
| HP            | TouchSmart tm2              | [1a91d6cc06](https://linux-hardware.org/?probe=1a91d6cc06) | Sep 22, 2020 |
| ASUSTek       | GL503VM                     | [349cf8d805](https://linux-hardware.org/?probe=349cf8d805) | Sep 17, 2020 |
| Toshiba       | NI 1403                     | [d2f6023c70](https://linux-hardware.org/?probe=d2f6023c70) | Sep 17, 2020 |
| Lenovo        | V145-15AST 81MT             | [401a915579](https://linux-hardware.org/?probe=401a915579) | Sep 10, 2020 |
| Fujitsu       | LIFEBOOK A556/G             | [9484700de9](https://linux-hardware.org/?probe=9484700de9) | Sep 10, 2020 |
| MSI           | FX610                       | [61fe175928](https://linux-hardware.org/?probe=61fe175928) | Sep 04, 2020 |
| Acer          | Aspire A315-41              | [2f541fa7c6](https://linux-hardware.org/?probe=2f541fa7c6) | Aug 23, 2020 |
| HP            | EliteBook 2540p             | [682d1b7a8c](https://linux-hardware.org/?probe=682d1b7a8c) | Aug 22, 2020 |
| Acer          | Extensa 4620                | [9421ec33ce](https://linux-hardware.org/?probe=9421ec33ce) | Aug 18, 2020 |
| HP            | Laptop 15-bs0xx             | [f6678c3632](https://linux-hardware.org/?probe=f6678c3632) | Aug 17, 2020 |
| Acer          | Extensa 4620                | [a7701181d6](https://linux-hardware.org/?probe=a7701181d6) | Aug 17, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [eed0bce682](https://linux-hardware.org/?probe=eed0bce682) | Aug 14, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [532d54162a](https://linux-hardware.org/?probe=532d54162a) | Aug 14, 2020 |
| Dell          | Latitude E5430 non-vPro     | [2a8cc9f92c](https://linux-hardware.org/?probe=2a8cc9f92c) | Aug 04, 2020 |
| HP            | Laptop 15-bs0xx             | [467112cf04](https://linux-hardware.org/?probe=467112cf04) | Jul 31, 2020 |
| Positivo      | W310CZ-T                    | [0a1a913ef9](https://linux-hardware.org/?probe=0a1a913ef9) | Jul 19, 2020 |
| Acer          | Aspire 1640                 | [187a648c68](https://linux-hardware.org/?probe=187a648c68) | Jul 16, 2020 |
| Lenovo        | ThinkPad T61 6457W9X        | [ccd11debcb](https://linux-hardware.org/?probe=ccd11debcb) | Jul 11, 2020 |
| HP            | ProBook 430 G5              | [ea27ca7285](https://linux-hardware.org/?probe=ea27ca7285) | Jul 01, 2020 |
| ASUSTek       | E402SA                      | [46b87025ae](https://linux-hardware.org/?probe=46b87025ae) | Jul 01, 2020 |
| Acer          | Aspire 5750G                | [1f45c104e4](https://linux-hardware.org/?probe=1f45c104e4) | Jun 26, 2020 |
| Acer          | Aspire 5750G                | [5613253a47](https://linux-hardware.org/?probe=5613253a47) | Jun 26, 2020 |
| Dell          | Inspiron 3442               | [8c0a32e7f4](https://linux-hardware.org/?probe=8c0a32e7f4) | Jun 19, 2020 |
| Dell          | Inspiron 3442               | [8ed5aa8505](https://linux-hardware.org/?probe=8ed5aa8505) | Jun 19, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | [012f3cadc0](https://linux-hardware.org/?probe=012f3cadc0) | Jun 16, 2020 |
| ASUSTek       | K50C                        | [1d98006287](https://linux-hardware.org/?probe=1d98006287) | Jun 15, 2020 |
| ASUSTek       | K50C                        | [141d18f0ca](https://linux-hardware.org/?probe=141d18f0ca) | Jun 15, 2020 |
| HP            | 350 G2                      | [ac2b06957f](https://linux-hardware.org/?probe=ac2b06957f) | Jun 11, 2020 |
| ASUSTek       | 1005PX                      | [8d5b0aa8df](https://linux-hardware.org/?probe=8d5b0aa8df) | Jun 03, 2020 |
| Sony          | VGN-AW41MF_H                | [baf800f176](https://linux-hardware.org/?probe=baf800f176) | May 29, 2020 |
| Samsung       | RV411/RV511/E3511/S3511/... | [f4679ca184](https://linux-hardware.org/?probe=f4679ca184) | May 29, 2020 |
| HP            | EliteBook 8540w             | [4fb041418f](https://linux-hardware.org/?probe=4fb041418f) | May 29, 2020 |
| HP            | EliteBook 8540w             | [b36f5a9ddf](https://linux-hardware.org/?probe=b36f5a9ddf) | May 28, 2020 |
| ASUSTek       | K50IJ                       | [7f22ac48a8](https://linux-hardware.org/?probe=7f22ac48a8) | May 26, 2020 |
| ASUSTek       | K50IJ                       | [be86e3ea15](https://linux-hardware.org/?probe=be86e3ea15) | May 26, 2020 |
| HP            | Presario CQ61               | [28b3078708](https://linux-hardware.org/?probe=28b3078708) | May 25, 2020 |
| Acer          | Aspire 7551                 | [d9c150f3ee](https://linux-hardware.org/?probe=d9c150f3ee) | May 24, 2020 |
| Dell          | Inspiron N5110              | [e2ba0ca3f4](https://linux-hardware.org/?probe=e2ba0ca3f4) | May 22, 2020 |
| Acer          | Aspire 4830T                | [5494761310](https://linux-hardware.org/?probe=5494761310) | May 20, 2020 |
| ASUSTek       | X550LC                      | [9c46a8ee24](https://linux-hardware.org/?probe=9c46a8ee24) | May 20, 2020 |
| ASUSTek       | X550LC                      | [b7665aa8e1](https://linux-hardware.org/?probe=b7665aa8e1) | May 20, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [4d4f673fb2](https://linux-hardware.org/?probe=4d4f673fb2) | May 16, 2020 |
| HP            | EliteBook 8570p             | [4ede694438](https://linux-hardware.org/?probe=4ede694438) | May 14, 2020 |
| HP            | EliteBook 8570p             | [530b229976](https://linux-hardware.org/?probe=530b229976) | May 14, 2020 |
| Dell          | G3 3590                     | [6b37af517b](https://linux-hardware.org/?probe=6b37af517b) | May 12, 2020 |
| Toshiba       | Satellite U300              | [ef95fa82d7](https://linux-hardware.org/?probe=ef95fa82d7) | May 11, 2020 |
| HP            | G61                         | [7393752623](https://linux-hardware.org/?probe=7393752623) | May 11, 2020 |
| Dell          | Latitude E5570              | [1c8dda10a4](https://linux-hardware.org/?probe=1c8dda10a4) | May 08, 2020 |
| Dell          | Latitude E5570              | [20fc42be1b](https://linux-hardware.org/?probe=20fc42be1b) | May 06, 2020 |
| Dell          | System Inspiron N411Z       | [246dd5ce2a](https://linux-hardware.org/?probe=246dd5ce2a) | May 05, 2020 |
| Dell          | Latitude E5570              | [a1b049e54c](https://linux-hardware.org/?probe=a1b049e54c) | May 05, 2020 |
| Toshiba       | Satellite U300              | [3bd62e1a59](https://linux-hardware.org/?probe=3bd62e1a59) | May 05, 2020 |
| HP            | Laptop 15-bs2xx             | [6d47f83eac](https://linux-hardware.org/?probe=6d47f83eac) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | [154605446a](https://linux-hardware.org/?probe=154605446a) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | [e9544d771b](https://linux-hardware.org/?probe=e9544d771b) | May 02, 2020 |
| HP            | G42                         | [be1ea8571f](https://linux-hardware.org/?probe=be1ea8571f) | Apr 28, 2020 |
| Lenovo        | ThinkPad E490 20N80017RT    | [7f84d5a0f2](https://linux-hardware.org/?probe=7f84d5a0f2) | Apr 28, 2020 |
| HP            | G42                         | [8ea8320eac](https://linux-hardware.org/?probe=8ea8320eac) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | [b314d76130](https://linux-hardware.org/?probe=b314d76130) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | [7984248cab](https://linux-hardware.org/?probe=7984248cab) | Apr 26, 2020 |
| Acer          | Aspire E1-572               | [e64e2fe71c](https://linux-hardware.org/?probe=e64e2fe71c) | Apr 23, 2020 |
| HP            | Laptop 15-bs2xx             | [477c5d9ffa](https://linux-hardware.org/?probe=477c5d9ffa) | Apr 17, 2020 |
| Positivo      | Mobile                      | [c7cc7cd357](https://linux-hardware.org/?probe=c7cc7cd357) | Apr 17, 2020 |
| Positivo      | Mobile                      | [55b84972df](https://linux-hardware.org/?probe=55b84972df) | Apr 17, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [4d06bdc501](https://linux-hardware.org/?probe=4d06bdc501) | Apr 14, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [67167458d8](https://linux-hardware.org/?probe=67167458d8) | Apr 14, 2020 |
| Acer          | Aspire E1-572               | [941e12751c](https://linux-hardware.org/?probe=941e12751c) | Apr 14, 2020 |
| Acer          | Aspire E1-570G              | [e727c9003c](https://linux-hardware.org/?probe=e727c9003c) | Apr 10, 2020 |
| Acer          | Aspire E1-570G              | [fe1196d306](https://linux-hardware.org/?probe=fe1196d306) | Apr 09, 2020 |
| Dell          | Latitude E6510              | [5f62bf8564](https://linux-hardware.org/?probe=5f62bf8564) | Apr 07, 2020 |
| Toshiba       | Satellite P300              | [93b28f5a7c](https://linux-hardware.org/?probe=93b28f5a7c) | Apr 03, 2020 |
| ASUSTek       | ZenBook UX431FA             | [3251d5e710](https://linux-hardware.org/?probe=3251d5e710) | Apr 03, 2020 |
| Dell          | Latitude D610               | [44901c9eb2](https://linux-hardware.org/?probe=44901c9eb2) | Mar 30, 2020 |
| Dell          | Latitude D610               | [5bfecb6e64](https://linux-hardware.org/?probe=5bfecb6e64) | Mar 30, 2020 |
| Dell          | Inspiron 3543               | [5055c4067a](https://linux-hardware.org/?probe=5055c4067a) | Mar 20, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 4.19.0-8-amd64       | 27        | 11.16%  |
| 4.19.0-18-amd64      | 24        | 9.92%   |
| 4.19.0-17-amd64      | 20        | 8.26%   |
| 4.19.0-9-amd64       | 18        | 7.44%   |
| 4.19.0-16-amd64      | 16        | 6.61%   |
| 4.19.0-8-686         | 14        | 5.79%   |
| 4.19.0-17-686        | 14        | 5.79%   |
| 4.19.0-14-amd64      | 13        | 5.37%   |
| 4.19.0-13-amd64      | 12        | 4.96%   |
| 4.19.0-16-686        | 11        | 4.55%   |
| 4.19.0-10-amd64      | 11        | 4.55%   |
| 4.19.0-18-686        | 10        | 4.13%   |
| 4.19.0-12-amd64      | 10        | 4.13%   |
| 4.19.0-13-686        | 7         | 2.89%   |
| 4.19.0-11-amd64      | 6         | 2.48%   |
| 4.19.0-12-686        | 5         | 2.07%   |
| 4.19.0-19-686        | 3         | 1.24%   |
| 4.19.0-14-686        | 3         | 1.24%   |
| 5.4.0-0.bpo.4-amd64  | 2         | 0.83%   |
| 5.10.0-0.bpo.5-amd64 | 2         | 0.83%   |
| 5.9.12-davius        | 1         | 0.41%   |
| 5.9.0-0.bpo.5-amd64  | 1         | 0.41%   |
| 5.8.0-0.bpo.2-amd64  | 1         | 0.41%   |
| 5.6.0-2-amd64        | 1         | 0.41%   |
| 5.6.0-2-686-pae      | 1         | 0.41%   |
| 5.4.44-xanmod1       | 1         | 0.41%   |
| 5.10.0-0.bpo.9-amd64 | 1         | 0.41%   |
| 5.10.0-0.bpo.3-amd64 | 1         | 0.41%   |
| 4.19.0-9-686         | 1         | 0.41%   |
| 4.19.0-20-amd64      | 1         | 0.41%   |
| 4.19.0-20-686        | 1         | 0.41%   |
| 4.19.0-14-686-pae    | 1         | 0.41%   |
| 4.19.0-12-rt-amd64   | 1         | 0.41%   |
| 4.19.0-10-686        | 1         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19.0  | 209       | 94.57%  |
| 5.10.0  | 4         | 1.81%   |
| 5.6.0   | 2         | 0.9%    |
| 5.4.0   | 2         | 0.9%    |
| 5.9.12  | 1         | 0.45%   |
| 5.9.0   | 1         | 0.45%   |
| 5.8.0   | 1         | 0.45%   |
| 5.4.44  | 1         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19    | 209       | 94.57%  |
| 5.10    | 4         | 1.81%   |
| 5.4     | 3         | 1.36%   |
| 5.9     | 2         | 0.9%    |
| 5.6     | 2         | 0.9%    |
| 5.8     | 1         | 0.45%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 151       | 68.95%  |
| i686   | 68        | 31.05%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 204       | 91.48%  |
| Cinnamon   | 7         | 3.14%   |
| MATE       | 4         | 1.79%   |
| Unknown    | 4         | 1.79%   |
| XFCE       | 1         | 0.45%   |
| Trinity    | 1         | 0.45%   |
| LXDE       | 1         | 0.45%   |
| KDE        | 1         | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 219       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 197       | 89.55%  |
| LightDM | 13        | 5.91%   |
| TDM     | 10        | 4.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 64        | 28.96%  |
| pt_BR   | 23        | 10.41%  |
| de_DE   | 22        | 9.95%   |
| ru_RU   | 12        | 5.43%   |
| en_GB   | 10        | 4.52%   |
| pl_PL   | 9         | 4.07%   |
| it_IT   | 7         | 3.17%   |
| es_ES   | 6         | 2.71%   |
| es_AR   | 6         | 2.71%   |
| en_AU   | 6         | 2.71%   |
| fr_FR   | 5         | 2.26%   |
| es_MX   | 5         | 2.26%   |
| de_CH   | 5         | 2.26%   |
| en_CA   | 4         | 1.81%   |
| nl_NL   | 3         | 1.36%   |
| ja_JP   | 3         | 1.36%   |
| el_GR   | 3         | 1.36%   |
| en_ZA   | 2         | 0.9%    |
| en_PH   | 2         | 0.9%    |
| en_IN   | 2         | 0.9%    |
| de_AT   | 2         | 0.9%    |
| bg_BG   | 2         | 0.9%    |
| zh_CN   | 1         | 0.45%   |
| unm_US  | 1         | 0.45%   |
| uk_UA   | 1         | 0.45%   |
| tr_TR   | 1         | 0.45%   |
| sk_SK   | 1         | 0.45%   |
| ru_UA   | 1         | 0.45%   |
| pt_PT   | 1         | 0.45%   |
| nl_BE   | 1         | 0.45%   |
| it_CH   | 1         | 0.45%   |
| hr_HR   | 1         | 0.45%   |
| fr_BE   | 1         | 0.45%   |
| et_EE   | 1         | 0.45%   |
| es_CL   | 1         | 0.45%   |
| en_SG   | 1         | 0.45%   |
| en_NZ   | 1         | 0.45%   |
| da_DK   | 1         | 0.45%   |
| ca_ES   | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 161       | 72.85%  |
| EFI  | 60        | 27.15%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 212       | 96.8%   |
| Btrfs   | 4         | 1.83%   |
| Tmpfs   | 2         | 0.91%   |
| Overlay | 1         | 0.46%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 193       | 88.13%  |
| MBR     | 13        | 5.94%   |
| GPT     | 13        | 5.94%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 210       | 95.89%  |
| Yes       | 9         | 4.11%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 211       | 96.35%  |
| Yes       | 8         | 3.65%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 47        | 21.46%  |
| Acer                           | 29        | 13.24%  |
| Lenovo                         | 28        | 12.79%  |
| Dell                           | 28        | 12.79%  |
| ASUSTek Computer               | 26        | 11.87%  |
| Toshiba                        | 9         | 4.11%   |
| Samsung Electronics            | 7         | 3.2%    |
| Sony                           | 5         | 2.28%   |
| Fujitsu Siemens                | 5         | 2.28%   |
| LG Electronics                 | 4         | 1.83%   |
| Positivo                       | 3         | 1.37%   |
| Packard Bell                   | 2         | 0.91%   |
| MSI                            | 2         | 0.91%   |
| Matsushita Electric Industrial | 2         | 0.91%   |
| Gateway                        | 2         | 0.91%   |
| Fujitsu                        | 2         | 0.91%   |
| Apple                          | 2         | 0.91%   |
| Unknown                        | 2         | 0.91%   |
| TUXEDO                         | 1         | 0.46%   |
| Semp Toshiba                   | 1         | 0.46%   |
| SAELITE                        | 1         | 0.46%   |
| Qbex                           | 1         | 0.46%   |
| Notebook                       | 1         | 0.46%   |
| Medion                         | 1         | 0.46%   |
| Maibenben                      | 1         | 0.46%   |
| Itautec                        | 1         | 0.46%   |
| IBM                            | 1         | 0.46%   |
| Google                         | 1         | 0.46%   |
| Exper                          | 1         | 0.46%   |
| Exo                            | 1         | 0.46%   |
| EVOO                           | 1         | 0.46%   |
| Advent                         | 1         | 0.46%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 6         | 2.74%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 3         | 1.37%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 2         | 0.91%   |
| HP Pavilion dv6                             | 2         | 0.91%   |
| HP EliteBook 8540w                          | 2         | 0.91%   |
| ASUS X101CH                                 | 2         | 0.91%   |
| Acer Aspire 5735                            | 2         | 0.91%   |
| Acer Aspire 3000                            | 2         | 0.91%   |
| Acer AOD270                                 | 2         | 0.91%   |
| TUXEDO BC1510 1710                          | 1         | 0.46%   |
| Toshiba Satellite U300                      | 1         | 0.46%   |
| Toshiba Satellite P300                      | 1         | 0.46%   |
| Toshiba Satellite M100                      | 1         | 0.46%   |
| Toshiba Satellite L855                      | 1         | 0.46%   |
| Toshiba Satellite L750                      | 1         | 0.46%   |
| Toshiba Satellite L50-C                     | 1         | 0.46%   |
| Toshiba Satellite C50-A-1DN                 | 1         | 0.46%   |
| Toshiba Satellite A200                      | 1         | 0.46%   |
| Toshiba dynabook Satellite J61 173C/5       | 1         | 0.46%   |
| Sony VPCS131FM                              | 1         | 0.46%   |
| Sony VPCP116KG                              | 1         | 0.46%   |
| Sony VGN-FZ140E                             | 1         | 0.46%   |
| Sony VGN-AW41MF_H                           | 1         | 0.46%   |
| Sony SVE1511N1ESI                           | 1         | 0.46%   |
| Semp Toshiba NI 1403                        | 1         | 0.46%   |
| Samsung RV413/RV513                         | 1         | 0.46%   |
| Samsung R59/R60/R61                         | 1         | 0.46%   |
| Samsung NC10                                | 1         | 0.46%   |
| Samsung 305U1A                              | 1         | 0.46%   |
| SAELITE ES1AU11                             | 1         | 0.46%   |
| Qbex UDPAIOQBEX01                           | 1         | 0.46%   |
| Positivo W310CZ-T                           | 1         | 0.46%   |
| Positivo Mobile                             | 1         | 0.46%   |
| Positivo H14CU01                            | 1         | 0.46%   |
| Packard Bell EasyNote_NJ66                  | 1         | 0.46%   |
| Packard Bell EasyNote TE69BM                | 1         | 0.46%   |
| Notebook WID2010                            | 1         | 0.46%   |
| MSI GT70 2PC                                | 1         | 0.46%   |
| MSI FX610                                   | 1         | 0.46%   |
| Medion P6670 MD99960                        | 1         | 0.46%   |
| Matsushita Electric Industrial CF-19DDGZXVM | 1         | 0.46%   |
| Matsushita Electric Industrial CF-19CHB23BE | 1         | 0.46%   |
| Maibenben XiaoMai5                          | 1         | 0.46%   |
| LG X300-L.CR31B1                            | 1         | 0.46%   |
| LG X120-G.C7VPG                             | 1         | 0.46%   |
| LG E500-S.AP17B                             | 1         | 0.46%   |
| LG A530-T.BE76P1                            | 1         | 0.46%   |
| Lenovo Yoga 2 11 20428                      | 1         | 0.46%   |
| Lenovo Y50-70 20378                         | 1         | 0.46%   |
| Lenovo V145-15AST 81MT                      | 1         | 0.46%   |
| Lenovo ThinkPad X60 1706AA7                 | 1         | 0.46%   |
| Lenovo ThinkPad X230 2325CN3                | 1         | 0.46%   |
| Lenovo ThinkPad X100e 28762FP               | 1         | 0.46%   |
| Lenovo ThinkPad W541 20EGS24J00             | 1         | 0.46%   |
| Lenovo ThinkPad T61 6457W9X                 | 1         | 0.46%   |
| Lenovo ThinkPad T60p 8742C4G                | 1         | 0.46%   |
| Lenovo ThinkPad T530 2394BK7                | 1         | 0.46%   |
| Lenovo ThinkPad T440p 20AWA1NAUK            | 1         | 0.46%   |
| Lenovo ThinkPad T420s 4174EK3               | 1         | 0.46%   |
| Lenovo ThinkPad T400 64741EG                | 1         | 0.46%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Acer Aspire                                 | 23        | 10.5%   |
| Lenovo ThinkPad                             | 14        | 6.39%   |
| Dell Latitude                               | 12        | 5.48%   |
| HP Pavilion                                 | 10        | 4.57%   |
| Dell Inspiron                               | 9         | 4.11%   |
| Toshiba Satellite                           | 8         | 3.65%   |
| Lenovo IdeaPad                              | 7         | 3.2%    |
| HP Laptop                                   | 7         | 3.2%    |
| HP Compaq                                   | 6         | 2.74%   |
| Unknown                                     | 6         | 2.74%   |
| HP EliteBook                                | 5         | 2.28%   |
| Samsung RV411                               | 3         | 1.37%   |
| Fujitsu Siemens ESPRIMO                     | 3         | 1.37%   |
| Dell Precision                              | 3         | 1.37%   |
| Packard Bell EasyNote                       | 2         | 0.91%   |
| HP ProBook                                  | 2         | 0.91%   |
| HP Presario                                 | 2         | 0.91%   |
| Dell System                                 | 2         | 0.91%   |
| ASUS X101CH                                 | 2         | 0.91%   |
| Apple MacBookPro5                           | 2         | 0.91%   |
| Acer Swift                                  | 2         | 0.91%   |
| Acer AOD270                                 | 2         | 0.91%   |
| TUXEDO BC1510                               | 1         | 0.46%   |
| Toshiba dynabook                            | 1         | 0.46%   |
| Sony VPCS131FM                              | 1         | 0.46%   |
| Sony VPCP116KG                              | 1         | 0.46%   |
| Sony VGN-FZ140E                             | 1         | 0.46%   |
| Sony VGN-AW41MF                             | 1         | 0.46%   |
| Sony SVE1511N1ESI                           | 1         | 0.46%   |
| Semp Toshiba NI                             | 1         | 0.46%   |
| Samsung RV413                               | 1         | 0.46%   |
| Samsung R59                                 | 1         | 0.46%   |
| Samsung NC10                                | 1         | 0.46%   |
| Samsung 305U1A                              | 1         | 0.46%   |
| SAELITE ES1AU11                             | 1         | 0.46%   |
| Qbex UDPAIOQBEX01                           | 1         | 0.46%   |
| Positivo W310CZ-T                           | 1         | 0.46%   |
| Positivo Mobile                             | 1         | 0.46%   |
| Positivo H14CU01                            | 1         | 0.46%   |
| Notebook WID2010                            | 1         | 0.46%   |
| MSI GT70                                    | 1         | 0.46%   |
| MSI FX610                                   | 1         | 0.46%   |
| Medion P6670                                | 1         | 0.46%   |
| Matsushita Electric Industrial CF-19DDGZXVM | 1         | 0.46%   |
| Matsushita Electric Industrial CF-19CHB23BE | 1         | 0.46%   |
| Maibenben XiaoMai5                          | 1         | 0.46%   |
| LG X300-L.CR31B1                            | 1         | 0.46%   |
| LG X120-G.C7VPG                             | 1         | 0.46%   |
| LG E500-S.AP17B                             | 1         | 0.46%   |
| LG A530-T.BE76P1                            | 1         | 0.46%   |
| Lenovo Yoga                                 | 1         | 0.46%   |
| Lenovo Y50-70                               | 1         | 0.46%   |
| Lenovo V145-15AST                           | 1         | 0.46%   |
| Lenovo G50-45                               | 1         | 0.46%   |
| Lenovo G40-30                               | 1         | 0.46%   |
| Lenovo E41-25                               | 1         | 0.46%   |
| Lenovo B71-80                               | 1         | 0.46%   |
| Itautec Infoway                             | 1         | 0.46%   |
| IBM ThinkPad                                | 1         | 0.46%   |
| HP TouchSmart                               | 1         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 23        | 10.5%   |
| 2009    | 22        | 10.05%  |
| 2012    | 20        | 9.13%   |
| 2010    | 19        | 8.68%   |
| 2007    | 19        | 8.68%   |
| 2008    | 16        | 7.31%   |
| 2018    | 15        | 6.85%   |
| 2013    | 14        | 6.39%   |
| 2014    | 13        | 5.94%   |
| 2015    | 10        | 4.57%   |
| 2006    | 10        | 4.57%   |
| 2019    | 9         | 4.11%   |
| 2005    | 7         | 3.2%    |
| 2020    | 6         | 2.74%   |
| 2017    | 6         | 2.74%   |
| 2016    | 6         | 2.74%   |
| 2004    | 1         | 0.46%   |
| 2003    | 1         | 0.46%   |
| 2002    | 1         | 0.46%   |
| Unknown | 1         | 0.46%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 219       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 209       | 95%     |
| Enabled  | 11        | 5%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 218       | 99.54%  |
| Yes  | 1         | 0.46%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 67        | 30.45%  |
| 2.01-3.0   | 39        | 17.73%  |
| 4.01-8.0   | 37        | 16.82%  |
| 1.01-2.0   | 29        | 13.18%  |
| 16.01-24.0 | 23        | 10.45%  |
| 8.01-16.0  | 13        | 5.91%   |
| 0.51-1.0   | 9         | 4.09%   |
| 32.01-64.0 | 2         | 0.91%   |
| 24.01-32.0 | 1         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 120       | 50.85%  |
| 0.51-1.0  | 55        | 23.31%  |
| 2.01-3.0  | 34        | 14.41%  |
| 3.01-4.0  | 17        | 7.2%    |
| 4.01-8.0  | 4         | 1.69%   |
| 8.01-16.0 | 3         | 1.27%   |
| 0.01-0.5  | 3         | 1.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 160       | 71.75%  |
| 2      | 49        | 21.97%  |
| 3      | 6         | 2.69%   |
| 0      | 4         | 1.79%   |
| 4      | 2         | 0.9%    |
| 6      | 1         | 0.45%   |
| 5      | 1         | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 134       | 60.63%  |
| No        | 87        | 39.37%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 206       | 94.06%  |
| No        | 13        | 5.94%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 215       | 98.17%  |
| No        | 4         | 1.83%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 54.34%  |
| No        | 100       | 45.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 26        | 11.87%  |
| Germany             | 24        | 10.96%  |
| Brazil              | 24        | 10.96%  |
| Russia              | 9         | 4.11%   |
| Poland              | 9         | 4.11%   |
| UK                  | 8         | 3.65%   |
| Italy               | 8         | 3.65%   |
| Spain               | 7         | 3.2%    |
| Australia           | 7         | 3.2%    |
| Switzerland         | 6         | 2.74%   |
| Netherlands         | 6         | 2.74%   |
| Mexico              | 6         | 2.74%   |
| France              | 6         | 2.74%   |
| Bulgaria            | 6         | 2.74%   |
| Argentina           | 6         | 2.74%   |
| Ukraine             | 5         | 2.28%   |
| Canada              | 5         | 2.28%   |
| Turkey              | 3         | 1.37%   |
| Philippines         | 3         | 1.37%   |
| Indonesia           | 3         | 1.37%   |
| India               | 3         | 1.37%   |
| Greece              | 3         | 1.37%   |
| Bahrain             | 3         | 1.37%   |
| Austria             | 3         | 1.37%   |
| Tunisia             | 2         | 0.91%   |
| South Africa        | 2         | 0.91%   |
| Portugal            | 2         | 0.91%   |
| Japan               | 2         | 0.91%   |
| China               | 2         | 0.91%   |
| Belarus             | 2         | 0.91%   |
| Venezuela           | 1         | 0.46%   |
| Trinidad and Tobago | 1         | 0.46%   |
| Sweden              | 1         | 0.46%   |
| Singapore           | 1         | 0.46%   |
| Romania             | 1         | 0.46%   |
| New Zealand         | 1         | 0.46%   |
| Myanmar             | 1         | 0.46%   |
| Luxembourg          | 1         | 0.46%   |
| Ireland             | 1         | 0.46%   |
| Honduras            | 1         | 0.46%   |
| Estonia             | 1         | 0.46%   |
| Egypt               | 1         | 0.46%   |
| Dominican Republic  | 1         | 0.46%   |
| Denmark             | 1         | 0.46%   |
| Croatia             | 1         | 0.46%   |
| Chile               | 1         | 0.46%   |
| Belgium             | 1         | 0.46%   |
| Bangladesh          | 1         | 0.46%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Sao Paulo                 | 5         | 2.2%    |
| Wohlen                    | 3         | 1.32%   |
| St Petersburg             | 3         | 1.32%   |
| Seville                   | 3         | 1.32%   |
| Poznan                    | 3         | 1.32%   |
| Manama                    | 3         | 1.32%   |
| Zurich                    | 2         | 0.88%   |
| Wroclaw                   | 2         | 0.88%   |
| Stuttgart                 | 2         | 0.88%   |
| Sofia                     | 2         | 0.88%   |
| Perth                     | 2         | 0.88%   |
| Frankfurt am Main         | 2         | 0.88%   |
| Foz do Iguaçu            | 2         | 0.88%   |
| Denver                    | 2         | 0.88%   |
| Cologne                   | 2         | 0.88%   |
| Chelyabinsk               | 2         | 0.88%   |
| Caroline                  | 2         | 0.88%   |
| Bursa                     | 2         | 0.88%   |
| Athens                    | 2         | 0.88%   |
| Zoetermeer                | 1         | 0.44%   |
| Zhongshan                 | 1         | 0.44%   |
| Zapopan                   | 1         | 0.44%   |
| Zagreb                    | 1         | 0.44%   |
| Zabrze                    | 1         | 0.44%   |
| Yokohama                  | 1         | 0.44%   |
| Yevpatoriya               | 1         | 0.44%   |
| Yan’an                  | 1         | 0.44%   |
| Wittichenau               | 1         | 0.44%   |
| Wilberforce               | 1         | 0.44%   |
| Whittier                  | 1         | 0.44%   |
| Wellington                | 1         | 0.44%   |
| Voluntari                 | 1         | 0.44%   |
| Vitebsk                   | 1         | 0.44%   |
| Vila Matias               | 1         | 0.44%   |
| Vicosa                    | 1         | 0.44%   |
| Verona                    | 1         | 0.44%   |
| Veghel                    | 1         | 0.44%   |
| Uttoxeter                 | 1         | 0.44%   |
| Turin                     | 1         | 0.44%   |
| Tunis                     | 1         | 0.44%   |
| Tulbagh                   | 1         | 0.44%   |
| Tilburg                   | 1         | 0.44%   |
| Thessaloniki              | 1         | 0.44%   |
| The Hague                 | 1         | 0.44%   |
| Taquaritinga              | 1         | 0.44%   |
| Surabaya                  | 1         | 0.44%   |
| Supply                    | 1         | 0.44%   |
| Stockholm                 | 1         | 0.44%   |
| Stamsried                 | 1         | 0.44%   |
| St Louis                  | 1         | 0.44%   |
| Springfield               | 1         | 0.44%   |
| Singapore                 | 1         | 0.44%   |
| Sfax                      | 1         | 0.44%   |
| Sao Luís                 | 1         | 0.44%   |
| Sao Jose                  | 1         | 0.44%   |
| Santo Domingo Tehuantepec | 1         | 0.44%   |
| Santo Domingo Este        | 1         | 0.44%   |
| Santa Rosa                | 1         | 0.44%   |
| Santa Rita do Araguaia    | 1         | 0.44%   |
| Sanchaung                 | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 43        | 49     | 16.17%  |
| Seagate             | 37        | 48     | 13.91%  |
| Samsung Electronics | 36        | 40     | 13.53%  |
| Toshiba             | 20        | 21     | 7.52%   |
| Hitachi             | 18        | 18     | 6.77%   |
| Unknown             | 15        | 16     | 5.64%   |
| Kingston            | 11        | 13     | 4.14%   |
| HGST                | 10        | 11     | 3.76%   |
| SanDisk             | 9         | 13     | 3.38%   |
| Fujitsu             | 7         | 7      | 2.63%   |
| Crucial             | 7         | 8      | 2.63%   |
| Intel               | 6         | 6      | 2.26%   |
| SK Hynix            | 4         | 6      | 1.5%    |
| China               | 4         | 4      | 1.5%    |
| Transcend           | 3         | 4      | 1.13%   |
| KingDian            | 3         | 4      | 1.13%   |
| GOODRAM             | 3         | 3      | 1.13%   |
| Phison              | 2         | 3      | 0.75%   |
| Patriot             | 2         | 3      | 0.75%   |
| Micron Technology   | 2         | 2      | 0.75%   |
| KingSpec            | 2         | 2      | 0.75%   |
| Intenso             | 2         | 2      | 0.75%   |
| IBM/Hitachi         | 2         | 2      | 0.75%   |
| Gigabyte Technology | 2         | 3      | 0.75%   |
| USB30               | 1         | 2      | 0.38%   |
| PNY                 | 1         | 1      | 0.38%   |
| Netac               | 1         | 1      | 0.38%   |
| Mushkin             | 1         | 1      | 0.38%   |
| JMicron             | 1         | 2      | 0.38%   |
| HUAWEI              | 1         | 1      | 0.38%   |
| Hikvision           | 1         | 1      | 0.38%   |
| Hewlett-Packard     | 1         | 2      | 0.38%   |
| GALAX               | 1         | 1      | 0.38%   |
| FORESEE             | 1         | 1      | 0.38%   |
| DREVO               | 1         | 2      | 0.38%   |
| DAS                 | 1         | 4      | 0.38%   |
| CORSAIR             | 1         | 1      | 0.38%   |
| BIWIN               | 1         | 1      | 0.38%   |
| BAITITON            | 1         | 1      | 0.38%   |
| ASUS-PHISON         | 1         | 2      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB          | 6         | 2.22%   |
| Unknown MMC Card  7GB              | 4         | 1.48%   |
| Samsung SSD 860 EVO 1TB            | 4         | 1.48%   |
| WDC WD3200BEVT-60ZCT1 320GB        | 3         | 1.11%   |
| Unknown MMC Card  32GB             | 3         | 1.11%   |
| Toshiba MQ01ABF050 500GB           | 3         | 1.11%   |
| Toshiba MQ01ABD100 1TB             | 3         | 1.11%   |
| Seagate ST9500325AS 500GB          | 3         | 1.11%   |
| Seagate ST500LT012-1DG142 500GB    | 3         | 1.11%   |
| Kingston SA400S37240G 240GB SSD    | 3         | 1.11%   |
| WDC WD7500BPVT-75HXZT3 752GB       | 2         | 0.74%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 0.74%   |
| WDC WD2500BEVT-22ZCT0 250GB        | 2         | 0.74%   |
| WDC WD1200BEVS-22UST0 120GB        | 2         | 0.74%   |
| Unknown MMC Card  4GB              | 2         | 0.74%   |
| Unknown MMC Card  16GB             | 2         | 0.74%   |
| Toshiba MQ01ABD032 320GB           | 2         | 0.74%   |
| Seagate ST9320423AS 320GB          | 2         | 0.74%   |
| Seagate ST9250315AS 250GB          | 2         | 0.74%   |
| Seagate ST9120821AS 120GB          | 2         | 0.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.74%   |
| Seagate Expansion 4TB              | 2         | 0.74%   |
| Sandisk NVMe SSD Drive 256GB       | 2         | 0.74%   |
| Samsung SSD 860 EVO 250GB          | 2         | 0.74%   |
| Samsung SSD 850 EVO 500GB          | 2         | 0.74%   |
| KingDian S280 120GB SSD            | 2         | 0.74%   |
| Hitachi HTS725050A9A364 500GB      | 2         | 0.74%   |
| Hitachi HTS545032B9A300 320GB      | 2         | 0.74%   |
| Hitachi HTS543216L9A300 160GB      | 2         | 0.74%   |
| HGST HTS721010A9E630 1TB           | 2         | 0.74%   |
| HGST HTS545050A7E680 500GB         | 2         | 0.74%   |
| HGST HTS545050A7E380 500GB         | 2         | 0.74%   |
| HGST HTS541010A9E680 1TB           | 2         | 0.74%   |
| GOODRAM SSDPR-CL100-120-G3 120GB   | 2         | 0.74%   |
| Gigabyte GP-GSTFS31120GNTD 120GB   | 2         | 0.74%   |
| Fujitsu MHV2080BH 80GB             | 2         | 0.74%   |
| China SATA SSD 120GB               | 2         | 0.74%   |
| WDC WDS240G2G0B 240GB SSD          | 1         | 0.37%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1         | 0.37%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1         | 0.37%   |
| WDC WDBNCE5000PNC 500GB SSD        | 1         | 0.37%   |
| WDC WD800BEVE-00A0HT0 80GB         | 1         | 0.37%   |
| WDC WD7500BPVT-24HXZT1 752GB       | 1         | 0.37%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 0.37%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 0.37%   |
| WDC WD5000LPCX-22VHAT1 500GB       | 1         | 0.37%   |
| WDC WD5000LPCX-00VHAT0 500GB       | 1         | 0.37%   |
| WDC WD5000BPVT-22HXZT1 500GB       | 1         | 0.37%   |
| WDC WD5000BEVT-60A0RT0 500GB       | 1         | 0.37%   |
| WDC WD3200LPLX-75ZNTT0 320GB       | 1         | 0.37%   |
| WDC WD3200BPVT-35ZEST0 320GB       | 1         | 0.37%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 0.37%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 0.37%   |
| WDC WD3200BEVT-11ZCT0 320GB        | 1         | 0.37%   |
| WDC WD2500BEVT-75ZCT2 250GB        | 1         | 0.37%   |
| WDC WD2500BEVT-75A23T0 250GB       | 1         | 0.37%   |
| WDC WD1600BUCT-63TWBY0 160GB       | 1         | 0.37%   |
| WDC WD1600BEVT-75ZCT2 160GB        | 1         | 0.37%   |
| WDC WD1600BEVT-60ZCT1 160GB        | 1         | 0.37%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 38        | 44     | 28.36%  |
| Seagate             | 36        | 46     | 26.87%  |
| Hitachi             | 18        | 18     | 13.43%  |
| Toshiba             | 17        | 18     | 12.69%  |
| HGST                | 10        | 11     | 7.46%   |
| Fujitsu             | 7         | 7      | 5.22%   |
| Samsung Electronics | 4         | 4      | 2.99%   |
| IBM/Hitachi         | 2         | 2      | 1.49%   |
| Unknown             | 1         | 1      | 0.75%   |
| DAS                 | 1         | 4      | 0.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 30        | 34     | 30%     |
| Kingston            | 10        | 12     | 10%     |
| Crucial             | 7         | 8      | 7%      |
| SanDisk             | 6         | 10     | 6%      |
| WDC                 | 4         | 4      | 4%      |
| Intel               | 4         | 4      | 4%      |
| Transcend           | 3         | 4      | 3%      |
| Toshiba             | 3         | 3      | 3%      |
| KingDian            | 3         | 4      | 3%      |
| GOODRAM             | 3         | 3      | 3%      |
| China               | 3         | 3      | 3%      |
| SK Hynix            | 2         | 3      | 2%      |
| Patriot             | 2         | 3      | 2%      |
| Micron Technology   | 2         | 2      | 2%      |
| Gigabyte Technology | 2         | 3      | 2%      |
| USB30               | 1         | 2      | 1%      |
| Unknown             | 1         | 1      | 1%      |
| PNY                 | 1         | 1      | 1%      |
| Netac               | 1         | 1      | 1%      |
| Mushkin             | 1         | 1      | 1%      |
| KingSpec            | 1         | 1      | 1%      |
| Intenso             | 1         | 1      | 1%      |
| Hikvision           | 1         | 1      | 1%      |
| Hewlett-Packard     | 1         | 2      | 1%      |
| GALAX               | 1         | 1      | 1%      |
| FORESEE             | 1         | 1      | 1%      |
| DREVO               | 1         | 2      | 1%      |
| CORSAIR             | 1         | 1      | 1%      |
| BIWIN               | 1         | 1      | 1%      |
| BAITITON            | 1         | 1      | 1%      |
| ASUS-PHISON         | 1         | 2      | 1%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 129       | 155    | 51.81%  |
| SSD     | 88        | 120    | 35.34%  |
| MMC     | 13        | 14     | 5.22%   |
| NVMe    | 13        | 15     | 5.22%   |
| Unknown | 6         | 8      | 2.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 205       | 262    | 83.67%  |
| SAS  | 14        | 21     | 5.71%   |
| NVMe | 13        | 15     | 5.31%   |
| MMC  | 13        | 14     | 5.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 179       | 223    | 82.11%  |
| 0.51-1.0   | 33        | 43     | 15.14%  |
| 3.01-4.0   | 3         | 6      | 1.38%   |
| 4.01-10.0  | 2         | 2      | 0.92%   |
| 1.01-2.0   | 1         | 1      | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 95        | 42.6%   |
| 251-500        | 53        | 23.77%  |
| 51-100         | 26        | 11.66%  |
| 501-1000       | 22        | 9.87%   |
| 21-50          | 10        | 4.48%   |
| More than 3000 | 6         | 2.69%   |
| 1001-2000      | 6         | 2.69%   |
| 2001-3000      | 2         | 0.9%    |
| 1-20           | 2         | 0.9%    |
| Unknown        | 1         | 0.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 111       | 47.84%  |
| 21-50          | 53        | 22.84%  |
| 101-250        | 28        | 12.07%  |
| 51-100         | 22        | 9.48%   |
| 501-1000       | 5         | 2.16%   |
| 251-500        | 4         | 1.72%   |
| More than 3000 | 3         | 1.29%   |
| 2001-3000      | 3         | 1.29%   |
| 1001-2000      | 2         | 0.86%   |
| Unknown        | 1         | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate STM9120817AS 120GB          | 1         | 1      | 12.5%   |
| Seagate ST9640423AS 640GB           | 1         | 1      | 12.5%   |
| Seagate ST9120821AS 120GB           | 1         | 1      | 12.5%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 12.5%   |
| Samsung Electronics MP0402H 40GB    | 1         | 1      | 12.5%   |
| Kingston SV300S37A120G 120GB SSD    | 1         | 1      | 12.5%   |
| Fujitsu MHZ2080BJ FFS G2 80GB       | 1         | 1      | 12.5%   |
| Crucial M4-CT256M4SSD2 256GB        | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 37.5%   |
| SanDisk             | 1         | 1      | 12.5%   |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Kingston            | 1         | 1      | 12.5%   |
| Fujitsu             | 1         | 1      | 12.5%   |
| Crucial             | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 60%     |
| Samsung Electronics | 1         | 1      | 20%     |
| Fujitsu             | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 62.5%   |
| SSD  | 3         | 3      | 37.5%   |

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
| Detected | 194       | 283    | 88.99%  |
| Works    | 16        | 21     | 7.34%   |
| Malfunc  | 8         | 8      | 3.67%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 172       | 76.44%  |
| AMD                              | 28        | 12.44%  |
| Silicon Integrated Systems [SiS] | 6         | 2.67%   |
| Nvidia                           | 6         | 2.67%   |
| Sandisk                          | 4         | 1.78%   |
| SK Hynix                         | 2         | 0.89%   |
| Samsung Electronics              | 2         | 0.89%   |
| Phison Electronics               | 2         | 0.89%   |
| VIA Technologies                 | 1         | 0.44%   |
| Toshiba America Info Systems     | 1         | 0.44%   |
| Kingston Technology Company      | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 17        | 6.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 14        | 5.2%    |
| AMD FCH SATA Controller [AHCI mode]                                                    | 14        | 5.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 13        | 4.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 12        | 4.46%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 10        | 3.72%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 10        | 3.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 10        | 3.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 9         | 3.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 9         | 3.35%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 9         | 3.35%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 8         | 2.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 8         | 2.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 8         | 2.97%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 6         | 2.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 6         | 2.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 6         | 2.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 5         | 1.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 5         | 1.86%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 4         | 1.49%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                             | 4         | 1.49%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.49%   |
| Sandisk Non-Volatile memory controller                                                 | 3         | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 3         | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 3         | 1.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 3         | 1.12%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 3         | 1.12%   |
| AMD SB600 IDE                                                                          | 3         | 1.12%   |
| AMD IXP SB4x0 IDE Controller                                                           | 3         | 1.12%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 2         | 0.74%   |
| Phison E12 NVMe Controller                                                             | 2         | 0.74%   |
| Nvidia MCP79 AHCI Controller                                                           | 2         | 0.74%   |
| Nvidia MCP67 IDE Controller                                                            | 2         | 0.74%   |
| Nvidia MCP67 AHCI Controller                                                           | 2         | 0.74%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 2         | 0.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 2         | 0.74%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 2         | 0.74%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 2         | 0.74%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                               | 2         | 0.74%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                           | 2         | 0.74%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                                 | 2         | 0.74%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 2         | 0.74%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 2         | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 2         | 0.74%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 1         | 0.37%   |
| VIA VT8237A SATA 2-Port Controller                                                     | 1         | 0.37%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 1         | 0.37%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 1         | 0.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 1         | 0.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.37%   |
| Nvidia MCP79 SATA Controller                                                           | 1         | 0.37%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                           | 1         | 0.37%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                       | 1         | 0.37%   |
| Kingston Company A2000 NVMe SSD                                                        | 1         | 0.37%   |
| Intel SSD 660P Series                                                                  | 1         | 0.37%   |
| Intel SSD 600P Series                                                                  | 1         | 0.37%   |
| Intel SM35 Chipset SATA AHCI Controller                                                | 1         | 0.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 159       | 63.1%   |
| IDE  | 68        | 26.98%  |
| NVMe | 14        | 5.56%   |
| RAID | 11        | 4.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 184       | 84.02%  |
| AMD    | 35        | 15.98%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom CPU N2600 @ 1.60GHz                | 6         | 2.74%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 5         | 2.28%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 5         | 2.28%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 4         | 1.83%   |
| Intel Genuine CPU T2300 @ 1.66GHz             | 3         | 1.37%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.37%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.37%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.37%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.37%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 3         | 1.37%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 3         | 1.37%   |
| Intel Pentium M processor 2.00GHz             | 2         | 0.91%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.91%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 2         | 0.91%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 0.91%   |
| Intel Genuine CPU T2130 @ 1.86GHz             | 2         | 0.91%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.91%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.91%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 0.91%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 0.91%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.91%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 2         | 0.91%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.91%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.91%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.91%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.91%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.91%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 2         | 0.91%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.91%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 0.91%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.91%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 0.91%   |
| Intel Core Duo CPU T2400 @ 1.83GHz            | 2         | 0.91%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.91%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 2         | 0.91%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.91%   |
| Intel Celeron CPU 900 @ 2.20GHz               | 2         | 0.91%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 0.91%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 0.91%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G | 2         | 0.91%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 0.91%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 2         | 0.91%   |
| AMD 3020e with Radeon Graphics                | 2         | 0.91%   |
| Intel Pentium M processor 1600MHz             | 1         | 0.46%   |
| Intel Pentium M processor 1.86GHz             | 1         | 0.46%   |
| Intel Pentium M processor 1.73GHz             | 1         | 0.46%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.46%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.46%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 1         | 0.46%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.46%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 0.46%   |
| Intel Pentium Dual CPU T2310 @ 1.46GHz        | 1         | 0.46%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.46%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.46%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.46%   |
| Intel Pentium CPU 4415U @ 2.30GHz             | 1         | 0.46%   |
| Intel Pentium CPU 4405U @ 2.10GHz             | 1         | 0.46%   |
| Intel Pentium 4 CPU 2.80GHz                   | 1         | 0.46%   |
| Intel Pentium 4 CPU 2.00GHz                   | 1         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 32        | 14.61%  |
| Intel Core i7                  | 31        | 14.16%  |
| Intel Core 2 Duo               | 22        | 10.05%  |
| Intel Atom                     | 21        | 9.59%   |
| Intel Core i3                  | 19        | 8.68%   |
| Intel Celeron                  | 16        | 7.31%   |
| Intel Pentium                  | 8         | 3.65%   |
| Intel Genuine                  | 8         | 3.65%   |
| Intel Pentium Dual             | 6         | 2.74%   |
| Intel Core 2                   | 6         | 2.74%   |
| Other                          | 5         | 2.28%   |
| Intel Pentium M                | 5         | 2.28%   |
| Intel Pentium Dual-Core        | 4         | 1.83%   |
| AMD Ryzen 5                    | 4         | 1.83%   |
| AMD A4                         | 4         | 1.83%   |
| Intel Core Duo                 | 3         | 1.37%   |
| AMD Turion 64 X2 Mobile        | 3         | 1.37%   |
| Intel Pentium 4                | 2         | 0.91%   |
| AMD Sempron                    | 2         | 0.91%   |
| AMD Mobile Sempron             | 2         | 0.91%   |
| AMD E2                         | 2         | 0.91%   |
| AMD E                          | 2         | 0.91%   |
| AMD Athlon II                  | 2         | 0.91%   |
| Intel Mobile Pentium 4         | 1         | 0.46%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.46%   |
| AMD Turion 64 Mobile           | 1         | 0.46%   |
| AMD Ryzen 7                    | 1         | 0.46%   |
| AMD Phenom II                  | 1         | 0.46%   |
| AMD Athlon Neo                 | 1         | 0.46%   |
| AMD Athlon 64 X2               | 1         | 0.46%   |
| AMD Athlon                     | 1         | 0.46%   |
| AMD A8                         | 1         | 0.46%   |
| AMD A6                         | 1         | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 147       | 66.82%  |
| 4      | 38        | 17.27%  |
| 1      | 34        | 15.45%  |
| 6      | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 219       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 112       | 51.14%  |
| 1      | 107       | 48.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 182       | 83.11%  |
| 32-bit         | 37        | 16.89%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 8.11%   |
| 0x206a7    | 17        | 7.66%   |
| 0x1067a    | 16        | 7.21%   |
| 0x306a9    | 15        | 6.76%   |
| 0x6fd      | 10        | 4.5%    |
| 0x106c2    | 10        | 4.5%    |
| 0x40651    | 8         | 3.6%    |
| 0x30661    | 8         | 3.6%    |
| 0x20655    | 8         | 3.6%    |
| 0x406e3    | 7         | 3.15%   |
| 0x06006705 | 7         | 3.15%   |
| 0x806ea    | 6         | 2.7%    |
| 0x6f6      | 6         | 2.7%    |
| 0x6ec      | 6         | 2.7%    |
| 0x306c3    | 6         | 2.7%    |
| 0x6e8      | 5         | 2.25%   |
| 0x30678    | 5         | 2.25%   |
| 0x10676    | 4         | 1.8%    |
| 0x806eb    | 3         | 1.35%   |
| 0x6d8      | 3         | 1.35%   |
| 0x506e3    | 3         | 1.35%   |
| 0x306d4    | 3         | 1.35%   |
| 0x20652    | 3         | 1.35%   |
| 0x08108102 | 3         | 1.35%   |
| 0x010000c8 | 3         | 1.35%   |
| 0xf29      | 2         | 0.9%    |
| 0x806ec    | 2         | 0.9%    |
| 0x806e9    | 2         | 0.9%    |
| 0x706a1    | 2         | 0.9%    |
| 0x406c3    | 2         | 0.9%    |
| 0x106e5    | 2         | 0.9%    |
| 0x106ca    | 2         | 0.9%    |
| 0x10661    | 2         | 0.9%    |
| 0x08200103 | 2         | 0.9%    |
| 0x02000032 | 2         | 0.9%    |
| 0xf24      | 1         | 0.45%   |
| 0x906ed    | 1         | 0.45%   |
| 0x906ea    | 1         | 0.45%   |
| 0x906e9    | 1         | 0.45%   |
| 0x6fb      | 1         | 0.45%   |
| 0x6fa      | 1         | 0.45%   |
| 0x6d6      | 1         | 0.45%   |
| 0x695      | 1         | 0.45%   |
| 0x406c4    | 1         | 0.45%   |
| 0x30673    | 1         | 0.45%   |
| 0x20661    | 1         | 0.45%   |
| 0x08101016 | 1         | 0.45%   |
| 0x0810100b | 1         | 0.45%   |
| 0x07030106 | 1         | 0.45%   |
| 0x07030105 | 1         | 0.45%   |
| 0x06001119 | 1         | 0.45%   |
| 0x05000119 | 1         | 0.45%   |
| 0x05000029 | 1         | 0.45%   |
| 0x03000027 | 1         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Penryn          | 22        | 10.05%  |
| Bonnell         | 21        | 9.59%   |
| Core            | 20        | 9.13%   |
| SandyBridge     | 18        | 8.22%   |
| KabyLake        | 17        | 7.76%   |
| P6              | 16        | 7.31%   |
| IvyBridge       | 15        | 6.85%   |
| Haswell         | 15        | 6.85%   |
| Westmere        | 11        | 5.02%   |
| Skylake         | 10        | 4.57%   |
| Silvermont      | 9         | 4.11%   |
| K8 Hammer       | 9         | 4.11%   |
| Excavator       | 7         | 3.2%    |
| Zen             | 4         | 1.83%   |
| K10             | 4         | 1.83%   |
| Zen+            | 3         | 1.37%   |
| NetBurst        | 3         | 1.37%   |
| Broadwell       | 3         | 1.37%   |
| Puma            | 2         | 0.91%   |
| Nehalem         | 2         | 0.91%   |
| K8 & K10 hybrid | 2         | 0.91%   |
| Goldmont plus   | 2         | 0.91%   |
| Bobcat          | 2         | 0.91%   |
| Piledriver      | 1         | 0.46%   |
| K10 Llano       | 1         | 0.46%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 141       | 55.73%  |
| AMD                              | 55        | 21.74%  |
| Nvidia                           | 51        | 20.16%  |
| Silicon Integrated Systems [SiS] | 5         | 1.98%   |
| VIA Technologies                 | 1         | 0.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Notebooks | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 14        | 5.11%   |
| Intel 3rd Gen Core processor Graphics Controller                                           | 14        | 5.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 14        | 5.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 13        | 4.74%   |
| Intel Core Processor Integrated Graphics Controller                                        | 8         | 2.92%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                            | 8         | 2.92%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 7         | 2.55%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 7         | 2.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 7         | 2.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 7         | 2.55%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 7         | 2.55%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                                 | 6         | 2.19%   |
| Intel UHD Graphics 620                                                                     | 6         | 2.19%   |
| Intel Skylake GT2 [HD Graphics 520]                                                        | 6         | 2.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 6         | 2.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 5         | 1.82%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 5         | 1.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 5         | 1.82%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 4         | 1.46%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 4         | 1.46%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 3         | 1.09%   |
| Nvidia GF108M [GeForce GT 525M]                                                            | 3         | 1.09%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 3         | 1.09%   |
| Intel HD Graphics 530                                                                      | 3         | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 3         | 1.09%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                          | 3         | 1.09%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 2         | 0.73%   |
| Nvidia GT218M [NVS 3100M]                                                                  | 2         | 0.73%   |
| Nvidia GM108M [GeForce 940MX]                                                              | 2         | 0.73%   |
| Nvidia GM107M [GeForce GTX 960M]                                                           | 2         | 0.73%   |
| Nvidia GK107M [GeForce GT 750M]                                                            | 2         | 0.73%   |
| Nvidia GK106GLM [Quadro K2100M]                                                            | 2         | 0.73%   |
| Nvidia GF119M [NVS 4200M]                                                                  | 2         | 0.73%   |
| Nvidia GF108GLM [Quadro 1000M]                                                             | 2         | 0.73%   |
| Nvidia G96CM [GeForce 9600M GT]                                                            | 2         | 0.73%   |
| Nvidia C79 [GeForce 9400M]                                                                 | 2         | 0.73%   |
| Intel HD Graphics 5500                                                                     | 2         | 0.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 2         | 0.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                  | 2         | 0.73%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                    | 2         | 0.73%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]              | 2         | 0.73%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                              | 2         | 0.73%   |
| AMD RV200/M7 [Mobility Radeon 7500]                                                        | 2         | 0.73%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 2         | 0.73%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                    | 2         | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2         | 0.73%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                               | 2         | 0.73%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                          | 1         | 0.36%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                            | 1         | 0.36%   |
| Nvidia NV34M [GeForce FX Go5300 / Go5350]                                                  | 1         | 0.36%   |
| Nvidia GT216M [GeForce GT 230M]                                                            | 1         | 0.36%   |
| Nvidia GP108M [GeForce MX230]                                                              | 1         | 0.36%   |
| Nvidia GP108M [GeForce MX150]                                                              | 1         | 0.36%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                    | 1         | 0.36%   |
| Nvidia GM108M [GeForce 840M]                                                               | 1         | 0.36%   |
| Nvidia GM107M [GeForce GTX 950M]                                                           | 1         | 0.36%   |
| Nvidia GK208M [GeForce GT 740M]                                                            | 1         | 0.36%   |
| Nvidia GK208BM [GeForce 920M]                                                              | 1         | 0.36%   |
| Nvidia GK104M [GeForce GTX 870M]                                                           | 1         | 0.36%   |
| Nvidia GF119M [GeForce GT 520M]                                                            | 1         | 0.36%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 107       | 48.86%  |
| 1 x AMD        | 45        | 20.55%  |
| 1 x Nvidia     | 26        | 11.87%  |
| Intel + Nvidia | 25        | 11.42%  |
| Intel + AMD    | 9         | 4.11%   |
| 1 x SiS        | 5         | 2.28%   |
| 2 x AMD        | 1         | 0.46%   |
| 1 x VIA        | 1         | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 189       | 85.91%  |
| Unknown     | 21        | 9.55%   |
| Proprietary | 10        | 4.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 147       | 67.12%  |
| 0.01-0.5   | 40        | 18.26%  |
| 1.01-2.0   | 16        | 7.31%   |
| 0.51-1.0   | 13        | 5.94%   |
| 5.01-6.0   | 1         | 0.46%   |
| 3.01-4.0   | 1         | 0.46%   |
| 2.01-3.0   | 1         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 36        | 17.56%  |
| Samsung Electronics     | 31        | 15.12%  |
| LG Display              | 31        | 15.12%  |
| BOE                     | 22        | 10.73%  |
| Chimei Innolux          | 19        | 9.27%   |
| Chi Mei Optoelectronics | 10        | 4.88%   |
| LG Philips              | 8         | 3.9%    |
| HannStar                | 6         | 2.93%   |
| Goldstar                | 6         | 2.93%   |
| Lenovo                  | 5         | 2.44%   |
| BenQ                    | 4         | 1.95%   |
| CPT                     | 3         | 1.46%   |
| Apple                   | 3         | 1.46%   |
| Sony                    | 2         | 0.98%   |
| Quanta Display          | 2         | 0.98%   |
| InfoVision              | 2         | 0.98%   |
| AOC                     | 2         | 0.98%   |
| Acer                    | 2         | 0.98%   |
| ViewSonic               | 1         | 0.49%   |
| Unknown                 | 1         | 0.49%   |
| Seiko/Epson             | 1         | 0.49%   |
| Philips                 | 1         | 0.49%   |
| PANDA                   | 1         | 0.49%   |
| Panasonic               | 1         | 0.49%   |
| MLT                     | 1         | 0.49%   |
| InnoLux Display         | 1         | 0.49%   |
| Hewlett-Packard         | 1         | 0.49%   |
| Dell                    | 1         | 0.49%   |
| Belinea                 | 1         | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 4         | 1.92%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 3         | 1.44%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 3         | 1.44%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 1.44%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 1.44%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 2         | 0.96%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 2         | 0.96%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 2         | 0.96%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 344x194mm 15.5-inch     | 2         | 0.96%   |
| Quanta Display LCD Monitor QDS0025 1024x768 304x228mm 15.0-inch          | 2         | 0.96%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.96%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 2         | 0.96%   |
| HannStar HSD101PFW4A HSD03ED 1024x600 223x125mm 10.1-inch                | 2         | 0.96%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 2         | 0.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO1558 1366x768 344x193mm 15.5-inch | 2         | 0.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 2         | 0.96%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 2         | 0.96%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 2         | 0.96%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 2         | 0.96%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                   | 1         | 0.48%   |
| Unknown LCD Monitor XXX AAA                                              | 1         | 0.48%   |
| Sony TV SNYA301 1920x1080 1600x900mm 72.3-inch                           | 1         | 0.48%   |
| Sony AVAMP SNYF700 1920x540                                              | 1         | 0.48%   |
| Seiko/Epson LCD Monitor 1920x1080                                        | 1         | 0.48%   |
| Samsung Electronics SMB2230H SAM0648 1920x1080                           | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC554E 1024x600 223x125mm 10.1-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC4642 1280x800 303x190mm 14.1-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 303x190mm 14.1-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3659 1600x900 344x194mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3450 1400x1050 286x214mm 14.1-inch    | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3445 1280x800 331x207mm 15.4-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3151 1366x768 344x194mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4447 1366x768 344x193mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch    | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC3250 1920x1080 344x194mm 15.5-inch    | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch   | 1         | 0.48%   |
| Philips PHL 15"XGATV PHL4650 1024x768 304x228mm 15.0-inch                | 1         | 0.48%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 1         | 0.48%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch             | 1         | 0.48%   |
| MLT LCD TV MLT9901 1366x768 409x230mm 18.5-inch                          | 1         | 0.48%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 1         | 0.48%   |
| LG Philips LCD Monitor LPLEF00 1280x800 304x190mm 14.1-inch              | 1         | 0.48%   |
| LG Philips LCD Monitor LPLB400 1280x800 331x207mm 15.4-inch              | 1         | 0.48%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch              | 1         | 0.48%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch              | 1         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 80        | 39.41%  |
| 1920x1080 (FHD)    | 49        | 24.14%  |
| 1280x800 (WXGA)    | 27        | 13.3%   |
| 1600x900 (HD+)     | 13        | 6.4%    |
| 1024x600           | 11        | 5.42%   |
| 3840x2160 (4K)     | 4         | 1.97%   |
| 1440x900 (WXGA+)   | 4         | 1.97%   |
| 1680x1050 (WSXGA+) | 2         | 0.99%   |
| 1280x1024 (SXGA)   | 2         | 0.99%   |
| 1024x768 (XGA)     | 2         | 0.99%   |
| 3840x1080          | 1         | 0.49%   |
| 2560x1440 (QHD)    | 1         | 0.49%   |
| 2560x1080          | 1         | 0.49%   |
| 1920x540           | 1         | 0.49%   |
| 1920x1200 (WUXGA)  | 1         | 0.49%   |
| 1400x1050          | 1         | 0.49%   |
| 1360x768           | 1         | 0.49%   |
| 1280x768           | 1         | 0.49%   |
| Unknown            | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 97        | 47.55%  |
| 14      | 27        | 13.24%  |
| 13      | 18        | 8.82%   |
| 17      | 13        | 6.37%   |
| 10      | 10        | 4.9%    |
| 18      | 5         | 2.45%   |
| 12      | 5         | 2.45%   |
| 11      | 5         | 2.45%   |
| 23      | 4         | 1.96%   |
| Unknown | 4         | 1.96%   |
| 72      | 2         | 0.98%   |
| 34      | 2         | 0.98%   |
| 27      | 2         | 0.98%   |
| 24      | 2         | 0.98%   |
| 21      | 2         | 0.98%   |
| 19      | 2         | 0.98%   |
| 48      | 1         | 0.49%   |
| 31      | 1         | 0.49%   |
| 20      | 1         | 0.49%   |
| 8       | 1         | 0.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 132       | 65.02%  |
| 201-300     | 26        | 12.81%  |
| 351-400     | 18        | 8.87%   |
| 401-500     | 9         | 4.43%   |
| 501-600     | 7         | 3.45%   |
| Unknown     | 4         | 1.97%   |
| 701-800     | 2         | 0.99%   |
| 1501-2000   | 2         | 0.99%   |
| 601-700     | 1         | 0.49%   |
| 101-200     | 1         | 0.49%   |
| 1001-1500   | 1         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 148       | 77.08%  |
| 16/10   | 34        | 17.71%  |
| 4/3     | 3         | 1.56%   |
| 5/4     | 2         | 1.04%   |
| Unknown | 2         | 1.04%   |
| 32/9    | 1         | 0.52%   |
| 3/2     | 1         | 0.52%   |
| 21/9    | 1         | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 97        | 47.32%  |
| 81-90          | 41        | 20%     |
| 41-50          | 10        | 4.88%   |
| 121-130        | 10        | 4.88%   |
| 201-250        | 7         | 3.41%   |
| 61-70          | 5         | 2.44%   |
| 51-60          | 5         | 2.44%   |
| 141-150        | 5         | 2.44%   |
| 151-200        | 4         | 1.95%   |
| Unknown        | 4         | 1.95%   |
| More than 1000 | 3         | 1.46%   |
| 71-80          | 3         | 1.46%   |
| 131-140        | 3         | 1.46%   |
| 351-500        | 2         | 0.98%   |
| 301-350        | 2         | 0.98%   |
| 91-100         | 2         | 0.98%   |
| 1-40           | 1         | 0.49%   |
| 501-1000       | 1         | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 97        | 48.26%  |
| 121-160       | 46        | 22.89%  |
| 51-100        | 45        | 22.39%  |
| 1-50          | 4         | 1.99%   |
| Unknown       | 4         | 1.99%   |
| 161-240       | 3         | 1.49%   |
| More than 240 | 2         | 1%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 184       | 82.88%  |
| 2     | 22        | 9.91%   |
| 0     | 16        | 7.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 122       | 31.36%  |
| Intel                                 | 82        | 21.08%  |
| Qualcomm Atheros                      | 78        | 20.05%  |
| Broadcom                              | 38        | 9.77%   |
| Marvell Technology Group              | 9         | 2.31%   |
| Broadcom Limited                      | 9         | 2.31%   |
| Ralink                                | 6         | 1.54%   |
| Silicon Integrated Systems [SiS]      | 5         | 1.29%   |
| Samsung Electronics                   | 5         | 1.29%   |
| Nvidia                                | 5         | 1.29%   |
| Ericsson Business Mobile Networks     | 3         | 0.77%   |
| JMicron Technology                    | 2         | 0.51%   |
| Huawei Technologies                   | 2         | 0.51%   |
| Attansic Technology                   | 2         | 0.51%   |
| AMD                                   | 2         | 0.51%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.26%   |
| Xiaomi                                | 1         | 0.26%   |
| VIA Technologies                      | 1         | 0.26%   |
| TP-Link                               | 1         | 0.26%   |
| ST-Ericsson                           | 1         | 0.26%   |
| Sierra Wireless                       | 1         | 0.26%   |
| Ralink Technology                     | 1         | 0.26%   |
| NetGear                               | 1         | 0.26%   |
| MediaTek                              | 1         | 0.26%   |
| Manta                                 | 1         | 0.26%   |
| Linksys                               | 1         | 0.26%   |
| Lenovo                                | 1         | 0.26%   |
| Intersil                              | 1         | 0.26%   |
| Gemtek                                | 1         | 0.26%   |
| DisplayLink                           | 1         | 0.26%   |
| Dell                                  | 1         | 0.26%   |
| Cisco Aironet Wireless Communications | 1         | 0.26%   |
| ASUSTek Computer                      | 1         | 0.26%   |
| Askey Computer                        | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 64        | 13.85%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 39        | 8.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 3.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 2.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 2.6%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 12        | 2.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 7         | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 1.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 1.52%   |
| Intel Wireless 7260                                                     | 6         | 1.3%    |
| Intel WiFi Link 5100                                                    | 6         | 1.3%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 1.08%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 1.08%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 4         | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 0.87%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 0.87%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.87%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.87%   |
| Intel 82573L Gigabit Ethernet Controller                                | 4         | 0.87%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 3         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.65%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.65%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.65%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.65%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 3         | 0.65%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                 | 3         | 0.65%   |
| Intel Wireless 8265 / 8275                                              | 3         | 0.65%   |
| Intel Wireless 3160                                                     | 3         | 0.65%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 3         | 0.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 0.65%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express          | 3         | 0.65%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 0.65%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 3         | 0.65%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 2         | 0.43%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 2         | 0.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.43%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.43%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.43%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.43%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 2         | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.43%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 0.43%   |
| Nvidia MCP79 Ethernet                                                   | 2         | 0.43%   |
| Nvidia MCP67 Ethernet                                                   | 2         | 0.43%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 0.43%   |
| Intel Wireless 8260                                                     | 2         | 0.43%   |
| Intel Wireless 7265                                                     | 2         | 0.43%   |
| Intel PRO/100 VE Network Connection                                     | 2         | 0.43%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.43%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 71        | 31.56%  |
| Intel                                 | 69        | 30.67%  |
| Realtek Semiconductor                 | 39        | 17.33%  |
| Broadcom                              | 28        | 12.44%  |
| Ralink                                | 6         | 2.67%   |
| Broadcom Limited                      | 4         | 1.78%   |
| TP-Link                               | 1         | 0.44%   |
| Sierra Wireless                       | 1         | 0.44%   |
| Ralink Technology                     | 1         | 0.44%   |
| NetGear                               | 1         | 0.44%   |
| Linksys                               | 1         | 0.44%   |
| Cisco Aironet Wireless Communications | 1         | 0.44%   |
| ASUSTek Computer                      | 1         | 0.44%   |
| Askey Computer                        | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 15        | 6.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 13        | 5.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 12        | 5.26%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 12        | 5.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 11        | 4.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 9         | 3.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 8         | 3.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 7         | 3.07%   |
| Intel Wireless 7260                                                            | 6         | 2.63%   |
| Intel WiFi Link 5100                                                           | 6         | 2.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 5         | 2.19%   |
| Intel Centrino Ultimate-N 6300                                                 | 5         | 2.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4         | 1.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 4         | 1.75%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 4         | 1.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 3         | 1.32%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 3         | 1.32%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 3         | 1.32%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 3         | 1.32%   |
| Intel Wireless 8265 / 8275                                                     | 3         | 1.32%   |
| Intel Wireless 3160                                                            | 3         | 1.32%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 3         | 1.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 3         | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 3         | 1.32%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                         | 3         | 1.32%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 3         | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                                     | 2         | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 2         | 0.88%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                       | 2         | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 2         | 0.88%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 2         | 0.88%   |
| Intel Wireless 8260                                                            | 2         | 0.88%   |
| Intel Wireless 7265                                                            | 2         | 0.88%   |
| Intel Gemini Lake PCH CNVi WiFi                                                | 2         | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 2         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                | 2         | 0.88%   |
| Broadcom BCM43228 802.11a/b/g/n                                                | 2         | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 2         | 0.88%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                    | 1         | 0.44%   |
| Sierra Wireless MC8305 Modem                                                   | 1         | 0.44%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1         | 0.44%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.44%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 1         | 0.44%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                    | 1         | 0.44%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1         | 0.44%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.44%   |
| Realtek RTL8187SE Wireless LAN Controller                                      | 1         | 0.44%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 1         | 0.44%   |
| Realtek 802.11ac NIC                                                           | 1         | 0.44%   |
| Ralink MT7601U Wireless Adapter                                                | 1         | 0.44%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]               | 1         | 0.44%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.44%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                      | 1         | 0.44%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                     | 1         | 0.44%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                               | 1         | 0.44%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 0.44%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)        | 1         | 0.44%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                                | 1         | 0.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 110       | 50.69%  |
| Intel                            | 34        | 15.67%  |
| Qualcomm Atheros                 | 17        | 7.83%   |
| Broadcom                         | 15        | 6.91%   |
| Marvell Technology Group         | 9         | 4.15%   |
| Silicon Integrated Systems [SiS] | 5         | 2.3%    |
| Samsung Electronics              | 5         | 2.3%    |
| Nvidia                           | 5         | 2.3%    |
| Broadcom Limited                 | 5         | 2.3%    |
| JMicron Technology               | 2         | 0.92%   |
| Attansic Technology              | 2         | 0.92%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.46%   |
| Xiaomi                           | 1         | 0.46%   |
| VIA Technologies                 | 1         | 0.46%   |
| MediaTek                         | 1         | 0.46%   |
| Lenovo                           | 1         | 0.46%   |
| Huawei Technologies              | 1         | 0.46%   |
| Gemtek                           | 1         | 0.46%   |
| DisplayLink                      | 1         | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 64        | 29.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 39        | 17.97%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 7         | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 3.23%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 2.3%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 4         | 1.84%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 1.84%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 1.84%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 4         | 1.84%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 3         | 1.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 3         | 1.38%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 3         | 1.38%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 3         | 1.38%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 2         | 0.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.92%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 0.92%   |
| Nvidia MCP67 Ethernet                                                          | 2         | 0.92%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.92%   |
| Intel PRO/100 VE Network Connection                                            | 2         | 0.92%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.92%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 0.92%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile           | 2         | 0.92%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.92%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 2         | 0.92%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 0.92%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 0.92%   |
| ZTE WCDMA MSM Z6201V                                                           | 1         | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.46%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.46%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 1         | 0.46%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.46%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.46%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.46%   |
| MediaTek Le                                                                    | 1         | 0.46%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.46%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.46%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.46%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.46%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.46%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.46%   |
| Lenovo ThinkPad Lan                                                            | 1         | 0.46%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 0.46%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.46%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.46%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.46%   |
| Intel 82801CAM (ICH3) PRO/100 VE (LOM) Ethernet Controller                     | 1         | 0.46%   |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                             | 1         | 0.46%   |
| Huawei E353/E3131                                                              | 1         | 0.46%   |
| Gemtek WLTUBA-107 [Yota 4G LTE]                                                | 1         | 0.46%   |
| DisplayLink Dell D3100 Docking Station                                         | 1         | 0.46%   |
| Broadcom NetXtreme BCM5788 Gigabit Ethernet                                    | 1         | 0.46%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 1         | 0.46%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                       | 1         | 0.46%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 1         | 0.46%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                       | 1         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 215       | 49.09%  |
| Ethernet | 206       | 47.03%  |
| Modem    | 14        | 3.2%    |
| Unknown  | 3         | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 166       | 75.11%  |
| Ethernet | 55        | 24.89%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 193       | 88.13%  |
| 1     | 22        | 10.05%  |
| 3     | 2         | 0.91%   |
| 4     | 1         | 0.46%   |
| 0     | 1         | 0.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 191       | 86.43%  |
| Yes  | 30        | 13.57%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 27        | 22.31%  |
| Realtek Semiconductor           | 15        | 12.4%   |
| Qualcomm Atheros Communications | 14        | 11.57%  |
| Broadcom                        | 14        | 11.57%  |
| Foxconn / Hon Hai               | 9         | 7.44%   |
| Hewlett-Packard                 | 8         | 6.61%   |
| Lite-On Technology              | 6         | 4.96%   |
| IMC Networks                    | 5         | 4.13%   |
| Dell                            | 5         | 4.13%   |
| Cambridge Silicon Radio         | 3         | 2.48%   |
| ASUSTek Computer                | 3         | 2.48%   |
| Toshiba                         | 2         | 1.65%   |
| Apple                           | 2         | 1.65%   |
| Taiyo Yuden                     | 1         | 0.83%   |
| Realtek                         | 1         | 0.83%   |
| Ralink Technology               | 1         | 0.83%   |
| Ralink                          | 1         | 0.83%   |
| Qcom                            | 1         | 0.83%   |
| Foxconn International           | 1         | 0.83%   |
| Askey Computer                  | 1         | 0.83%   |
| Alps Electric                   | 1         | 0.83%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 16        | 13.22%  |
| Qualcomm Atheros  Bluetooth Device                                                  | 8         | 6.61%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 7         | 5.79%   |
| Realtek Bluetooth Radio                                                             | 7         | 5.79%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 5         | 4.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 3.31%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 4         | 3.31%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 3.31%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 3         | 2.48%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 2.48%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 2.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 2.48%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 2.48%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.65%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 1.65%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.65%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.65%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.65%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.65%   |
| Foxconn / Hon Hai Acer Module                                                       | 2         | 1.65%   |
| Broadcom Bluetooth                                                                  | 2         | 1.65%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 1.65%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 1.65%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.65%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.65%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.83%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.83%   |
| Taiyo Yuden Bluetooth Device(BC04-External)                                         | 1         | 0.83%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.83%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.83%   |
| Ralink CSR BS8510                                                                   | 1         | 0.83%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.83%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.83%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.83%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.83%   |
| Intel AX200 Bluetooth                                                               | 1         | 0.83%   |
| IMC Networks Broadcom Bluetooth 2.1                                                 | 1         | 0.83%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.83%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.83%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.83%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.83%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.83%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.83%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.83%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.83%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.83%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 0.83%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 1         | 0.83%   |
| Askey Bluetooth Device                                                              | 1         | 0.83%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 0.83%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 173       | 68.92%  |
| AMD                              | 41        | 16.33%  |
| Nvidia                           | 25        | 9.96%   |
| Silicon Integrated Systems [SiS] | 6         | 2.39%   |
| C-Media Electronics              | 2         | 0.8%    |
| VIA Technologies                 | 1         | 0.4%    |
| Tenx Technology                  | 1         | 0.4%    |
| Generalplus Technology           | 1         | 0.4%    |
| Dell                             | 1         | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 29        | 9.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 19        | 6.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 6.12%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 5.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 5.1%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 4.42%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 3.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 3.4%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.72%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 2.72%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 2.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 2.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.38%   |
| AMD High Definition Audio Controller                                                              | 7         | 2.38%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 2.38%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 2.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 2.04%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 1.36%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 4         | 1.36%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 4         | 1.36%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.36%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 1.02%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.02%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.02%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.02%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 1.02%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 2         | 0.68%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.68%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.68%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.68%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.68%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 2         | 0.68%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                                              | 2         | 0.68%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.68%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.68%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.68%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.68%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 2         | 0.68%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.34%   |
| Tenx Technology USB AUDIO                                                                         | 1         | 0.34%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.34%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.34%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.34%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.34%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.34%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.34%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.34%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.34%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.34%   |
| Intel Moorestown Audio Ctrl                                                                       | 1         | 0.34%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.34%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 0.34%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 1         | 0.34%   |
| Generalplus Technology Usb Audio Device                                                           | 1         | 0.34%   |
| Dell AC511 Sound Bar                                                                              | 1         | 0.34%   |
| C-Media Electronics KIMU PRO                                                                      | 1         | 0.34%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 9         | 27.27%  |
| Samsung Electronics | 6         | 18.18%  |
| Unknown             | 4         | 12.12%  |
| Kingston            | 4         | 12.12%  |
| Smart               | 2         | 6.06%   |
| Ramaxel Technology  | 2         | 6.06%   |
| Nanya Technology    | 2         | 6.06%   |
| Transcend           | 1         | 3.03%   |
| Micron Technology   | 1         | 3.03%   |
| G.Skill             | 1         | 3.03%   |
| A-DATA Technology   | 1         | 3.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM Module SODIMM DDR                                | 1         | 2.86%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s               | 1         | 2.86%   |
| Unknown RAM Module 2GB SODIMM DDR3                           | 1         | 2.86%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                | 1         | 2.86%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 975MT/s            | 1         | 2.86%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s        | 1         | 2.86%   |
| Smart RAM SH564128FJ8NWRNSQG 4096MB SODIMM DDR3 1600MT/s     | 1         | 2.86%   |
| SK Hynix RAM Module 512MB SODIMM DDR 533MT/s                 | 1         | 2.86%   |
| SK Hynix RAM HYMP125S64CP8-Y5 2048MB SODIMM DDR 667MT/s      | 1         | 2.86%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s         | 1         | 2.86%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 2.86%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 2.86%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 1         | 2.86%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s    | 1         | 2.86%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 2.86%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s    | 1         | 2.86%   |
| SK Hynix RAM HMP125S6EFR8C-S6 2048MB SODIMM DDR2 800MT/s     | 1         | 2.86%   |
| SK Hynix RAM HMP112S6EFR6C-S6 1024MB SODIMM DDR 800MT/s      | 1         | 2.86%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s     | 1         | 2.86%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 1         | 2.86%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.86%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 2.86%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 1         | 2.86%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s       | 1         | 2.86%   |
| Ramaxel RAM RMSA3260MF68H9F-2666 4096MB SODIMM DDR4 2400MT/s | 1         | 2.86%   |
| Ramaxel RAM RMN1150EC48D7W-800 1024MB SODIMM DDR2 800MT/s    | 1         | 2.86%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s         | 1         | 2.86%   |
| Nanya RAM Module 1024MB SODIMM DDR 533MT/s                   | 1         | 2.86%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s      | 1         | 2.86%   |
| Kingston RAM 9905711-016.A00G 4GB SODIMM DDR4 2667MT/s       | 1         | 2.86%   |
| Kingston RAM 9905700-024.A00G 8GB SODIMM DDR4 2400MT/s       | 1         | 2.86%   |
| Kingston RAM 9905624-059.A00G 8192MB SODIMM DDR4 2667MT/s    | 1         | 2.86%   |
| Kingston RAM 9905428-155.A00LF 8GB SODIMM DDR3 1600MT/s      | 1         | 2.86%   |
| G.Skill RAM F3-10666CL9-8GBSQ 8192MB SODIMM DDR3 1333MT/s    | 1         | 2.86%   |
| A-DATA RAM AO1P26KC8T1-BXPS 8GB SODIMM DDR4 2667MT/s         | 1         | 2.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR3  | 12        | 41.38%  |
| DDR4  | 8         | 27.59%  |
| DDR2  | 5         | 17.24%  |
| SDRAM | 2         | 6.9%    |
| DDR   | 2         | 6.9%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 27        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 12        | 37.5%   |
| 4096    | 7         | 21.88%  |
| 2048    | 7         | 21.88%  |
| 1024    | 4         | 12.5%   |
| 512     | 1         | 3.13%   |
| Unknown | 1         | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 8         | 25.81%  |
| 1600    | 7         | 22.58%  |
| 1333    | 3         | 9.68%   |
| 2400    | 2         | 6.45%   |
| 975     | 2         | 6.45%   |
| 800     | 2         | 6.45%   |
| 533     | 2         | 6.45%   |
| Unknown | 2         | 6.45%   |
| 3266    | 1         | 3.23%   |
| 2048    | 1         | 3.23%   |
| 667     | 1         | 3.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 1         | 50%     |
| Hewlett-Packard | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Seiko Epson XP-3100 Series | 1         | 50%     |
| HP DeskJet 2700 series     | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 38        | 23.17%  |
| IMC Networks                           | 16        | 9.76%   |
| Suyin                                  | 14        | 8.54%   |
| Sunplus Innovation Technology          | 14        | 8.54%   |
| Acer                                   | 13        | 7.93%   |
| Quanta                                 | 11        | 6.71%   |
| Realtek Semiconductor                  | 9         | 5.49%   |
| Microdia                               | 8         | 4.88%   |
| Silicon Motion                         | 7         | 4.27%   |
| Ricoh                                  | 6         | 3.66%   |
| Apple                                  | 5         | 3.05%   |
| Syntek                                 | 4         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.44%   |
| Z-Star Microelectronics                | 2         | 1.22%   |
| Sunplus Technology                     | 2         | 1.22%   |
| Importek                               | 2         | 1.22%   |
| ALi                                    | 2         | 1.22%   |
| Samsung Electronics                    | 1         | 0.61%   |
| OmniVision Technologies                | 1         | 0.61%   |
| Lite-On Technology                     | 1         | 0.61%   |
| LG Electronics                         | 1         | 0.61%   |
| Lenovo                                 | 1         | 0.61%   |
| Generalplus Technology                 | 1         | 0.61%   |
| Alcor Micro                            | 1         | 0.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Quanta HP Webcam                                    | 5         | 3.03%   |
| Chicony Integrated Camera                           | 5         | 3.03%   |
| Suyin HP TrueVision HD                              | 3         | 1.82%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 3         | 1.82%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 3         | 1.82%   |
| Realtek USB2.0 VGA UVC WebCam                       | 3         | 1.82%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 1.82%   |
| Chicony USB 2.0 Camera                              | 3         | 1.82%   |
| Chicony HD WebCam                                   | 3         | 1.82%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 3         | 1.82%   |
| Apple iPhone 5/5C/5S/6/SE                           | 3         | 1.82%   |
| Acer Lenovo EasyCamera                              | 3         | 1.82%   |
| Syntek Sonix USB 2.0 Camera                         | 2         | 1.21%   |
| Suyin 1.3M HD WebCam                                | 2         | 1.21%   |
| Sunplus Laptop Integrated WebCam HD                 | 2         | 1.21%   |
| Sunplus HP TrueVision HD Camera                     | 2         | 1.21%   |
| Silicon Motion WebCam SCB-0385N                     | 2         | 1.21%   |
| Silicon Motion WebCam SC-0311139N                   | 2         | 1.21%   |
| Silicon Motion HP Webcam-101                        | 2         | 1.21%   |
| Ricoh Sony Visual Communication Camera              | 2         | 1.21%   |
| Realtek Integrated_Webcam_HD                        | 2         | 1.21%   |
| Quanta VGA WebCam                                   | 2         | 1.21%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.21%   |
| Microdia Sonix USB 2.0 Camera                       | 2         | 1.21%   |
| Microdia Integrated Webcam HD                       | 2         | 1.21%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 1.21%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 1.21%   |
| IMC Networks USB 2.0 UVC VGA WebCam                 | 2         | 1.21%   |
| IMC Networks Integrated Camera                      | 2         | 1.21%   |
| IMC Networks EasyCamera                             | 2         | 1.21%   |
| Chicony TOSHIBA Web Camera - HD                     | 2         | 1.21%   |
| Chicony HP Truevision HD camera                     | 2         | 1.21%   |
| Chicony HD WebCam (Acer)                            | 2         | 1.21%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 1.21%   |
| Apple Built-in iSight                               | 2         | 1.21%   |
| Acer USB HD Webcam                                  | 2         | 1.21%   |
| Acer HD Webcam                                      | 2         | 1.21%   |
| Z-Star Namuga 1.3M Webcam                           | 1         | 0.61%   |
| Z-Star Lenovo EasyCamera                            | 1         | 0.61%   |
| Syntek Integrated Webcam                            | 1         | 0.61%   |
| Syntek HP Webcam                                    | 1         | 0.61%   |
| Suyin WebCam                                        | 1         | 0.61%   |
| Suyin HP Webcam                                     | 1         | 0.61%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 0.61%   |
| Suyin HD WebCam                                     | 1         | 0.61%   |
| Suyin HD Video WebCam                               | 1         | 0.61%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.61%   |
| Sunplus 1.3M WebCam                                 | 1         | 0.61%   |
| Sunplus 1.3M HD WebCam                              | 1         | 0.61%   |
| Sunplus Lenovo EasyCamera                           | 1         | 0.61%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.61%   |
| Sunplus Integrated Webcam                           | 1         | 0.61%   |
| Sunplus HD WebCam                                   | 1         | 0.61%   |
| Sunplus Dell HD Webcam                              | 1         | 0.61%   |
| Sunplus Dell E5570 integrated webcam                | 1         | 0.61%   |
| Sunplus Asus Webcam                                 | 1         | 0.61%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 0.61%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 0.61%   |
| Ricoh Visual Communication Camera VGP-VCC9 [R5U870] | 1         | 0.61%   |
| Ricoh Visual Communication Camera VGP-VCC4 [R5U870] | 1         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 9         | 36%     |
| AuthenTec             | 8         | 32%     |
| STMicroelectronics    | 3         | 12%     |
| LighTuning Technology | 2         | 8%      |
| Upek                  | 1         | 4%      |
| Synaptics             | 1         | 4%      |
| Elan Microelectronics | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| STMicroelectronics Fingerprint Reader                  | 3         | 12%     |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 8%      |
| Validity Sensors VFS301 Fingerprint Reader             | 2         | 8%      |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 8%      |
| AuthenTec Fingerprint Sensor                           | 2         | 8%      |
| AuthenTec AES2810                                      | 2         | 8%      |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 8%      |
| AuthenTec AES1600                                      | 2         | 8%      |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4%      |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 4%      |
| Validity Sensors VFS491                                | 1         | 4%      |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 4%      |
| Validity Sensors Fingerprint scanner                   | 1         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4%      |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 4%      |
| Elan ELAN:Fingerprint                                  | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 8         | 61.54%  |
| O2 Micro              | 3         | 23.08%  |
| Gemalto (was Gemplus) | 1         | 7.69%   |
| Alcor Micro           | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 30.77%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 23.08%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 15.38%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 7.69%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 7.69%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 141       | 64.09%  |
| 1     | 55        | 25%     |
| 2     | 17        | 7.73%   |
| 3     | 6         | 2.73%   |
| 6     | 1         | 0.45%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 32        | 30.48%  |
| Fingerprint reader       | 25        | 23.81%  |
| Net/wireless             | 16        | 15.24%  |
| Chipcard                 | 12        | 11.43%  |
| Storage                  | 6         | 5.71%   |
| Multimedia controller    | 6         | 5.71%   |
| Communication controller | 3         | 2.86%   |
| Flash memory             | 2         | 1.9%    |
| Network                  | 1         | 0.95%   |
| Camera                   | 1         | 0.95%   |
| Bluetooth                | 1         | 0.95%   |

