LMDE 4 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for LMDE 4.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| HP            | Pavilion dv6                | [b4200dd39c](https://linux-hardware.org/?probe=b4200dd39c) | Oct 13, 2021 |
| Medion        | P6670 MD99960               | [eaa186d207](https://linux-hardware.org/?probe=eaa186d207) | Oct 12, 2021 |
| Medion        | P6670 MD99960               | [d42f345fc5](https://linux-hardware.org/?probe=d42f345fc5) | Oct 12, 2021 |
| HP            | 520                         | [4aea2d24b1](https://linux-hardware.org/?probe=4aea2d24b1) | Oct 10, 2021 |
| LG Electro... | A530-T.BE76P1               | [393852d904](https://linux-hardware.org/?probe=393852d904) | Oct 10, 2021 |
| Dell          | Precision M2800             | [b046a9dfe3](https://linux-hardware.org/?probe=b046a9dfe3) | Oct 08, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | [633c289440](https://linux-hardware.org/?probe=633c289440) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | [a6d07be7c9](https://linux-hardware.org/?probe=a6d07be7c9) | Sep 27, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [759b25b6a9](https://linux-hardware.org/?probe=759b25b6a9) | Sep 27, 2021 |
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
| Dell          | XPS M1330                   | [f4e126fba9](https://linux-hardware.org/?probe=f4e126fba9) | Aug 28, 2021 |
| ASUSTek       | 1201HA                      | [eadb8752c9](https://linux-hardware.org/?probe=eadb8752c9) | Aug 28, 2021 |
| HP            | Pavilion dv2000 (RD665EA... | [3b6dfaf6db](https://linux-hardware.org/?probe=3b6dfaf6db) | Aug 25, 2021 |
| Fujitsu       | LIFEBOOK A556/G             | [7706314dbc](https://linux-hardware.org/?probe=7706314dbc) | Aug 24, 2021 |
| Itautec       | W7655                       | [82b2d38326](https://linux-hardware.org/?probe=82b2d38326) | Aug 24, 2021 |
| Itautec       | W7655                       | [5952ec3a0f](https://linux-hardware.org/?probe=5952ec3a0f) | Aug 24, 2021 |
| HP            | 14                          | [e6bbdc5a92](https://linux-hardware.org/?probe=e6bbdc5a92) | Aug 24, 2021 |
| ASUSTek       | X101CH                      | [42ca8c45b4](https://linux-hardware.org/?probe=42ca8c45b4) | Aug 22, 2021 |
| ASUSTek       | X101CH                      | [31ed530084](https://linux-hardware.org/?probe=31ed530084) | Aug 22, 2021 |
| ASUSTek       | M51Sn                       | [5acb8c28ad](https://linux-hardware.org/?probe=5acb8c28ad) | Aug 21, 2021 |
| Packard Be... | EasyNote_NJ66               | [03c09865f3](https://linux-hardware.org/?probe=03c09865f3) | Aug 19, 2021 |
| ASUSTek       | N550JV                      | [f56a2bd3fa](https://linux-hardware.org/?probe=f56a2bd3fa) | Aug 14, 2021 |
| Toshiba       | Satellite M100              | [8dff0ec788](https://linux-hardware.org/?probe=8dff0ec788) | Aug 10, 2021 |
| Toshiba       | Satellite M100              | [06e766539d](https://linux-hardware.org/?probe=06e766539d) | Aug 10, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [8648635717](https://linux-hardware.org/?probe=8648635717) | Aug 07, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [16bec20604](https://linux-hardware.org/?probe=16bec20604) | Aug 06, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [dec7f65882](https://linux-hardware.org/?probe=dec7f65882) | Aug 06, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [322a210197](https://linux-hardware.org/?probe=322a210197) | Aug 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [c930d1c587](https://linux-hardware.org/?probe=c930d1c587) | Aug 03, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [eb5ff22307](https://linux-hardware.org/?probe=eb5ff22307) | Aug 03, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [2ffa81b543](https://linux-hardware.org/?probe=2ffa81b543) | Aug 01, 2021 |
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
| ASUSTek       | X550LN                      | [b37374d9f8](https://linux-hardware.org/?probe=b37374d9f8) | Jun 11, 2021 |
| Gateway       | LT40                        | [fe2551cb8b](https://linux-hardware.org/?probe=fe2551cb8b) | Jun 11, 2021 |
| Acer          | Aspire 3000                 | [57f93cbf62](https://linux-hardware.org/?probe=57f93cbf62) | Jun 09, 2021 |
| Acer          | Aspire 3000                 | [f6a944ee4a](https://linux-hardware.org/?probe=f6a944ee4a) | Jun 09, 2021 |
| Sony          | VPCEB3L1E                   | [bc3c3b537b](https://linux-hardware.org/?probe=bc3c3b537b) | Jun 06, 2021 |
| HP            | Laptop 15-dw0xxx            | [4f752689ed](https://linux-hardware.org/?probe=4f752689ed) | Jun 03, 2021 |
| Gateway       | LT40                        | [9defd288c4](https://linux-hardware.org/?probe=9defd288c4) | Jun 01, 2021 |
| Gateway       | LT40                        | [6a966fe471](https://linux-hardware.org/?probe=6a966fe471) | Jun 01, 2021 |
| ASUSTek       | X555UJ                      | [9c148a1665](https://linux-hardware.org/?probe=9c148a1665) | May 25, 2021 |
| HP            | Pavilion dv6                | [fb309a7f37](https://linux-hardware.org/?probe=fb309a7f37) | May 17, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
| ASUSTek       | X550LN                      | [7023b380c0](https://linux-hardware.org/?probe=7023b380c0) | May 11, 2021 |
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
| Toshiba       | NI 1403                     | [6587e3e02c](https://linux-hardware.org/?probe=6587e3e02c) | Apr 11, 2021 |
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
| Fujitsu       | LIFEBOOK A556/G             | [6ce455b6ab](https://linux-hardware.org/?probe=6ce455b6ab) | Mar 08, 2021 |
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
| Dell          | Inspiron 7520               | [6494901310](https://linux-hardware.org/?probe=6494901310) | Feb 24, 2021 |
| Acer          | Aspire 7750G                | [68c2e2956e](https://linux-hardware.org/?probe=68c2e2956e) | Feb 21, 2021 |
| Toshiba       | NI 1403                     | [4e907477e1](https://linux-hardware.org/?probe=4e907477e1) | Feb 21, 2021 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [078eb9c9b9](https://linux-hardware.org/?probe=078eb9c9b9) | Feb 19, 2021 |
| Acer          | Aspire 6930ZG               | [5e2260251a](https://linux-hardware.org/?probe=5e2260251a) | Feb 19, 2021 |
| Google        | Gnawty                      | [f2d007d3b0](https://linux-hardware.org/?probe=f2d007d3b0) | Feb 16, 2021 |
| Google        | Gnawty                      | [cf74012060](https://linux-hardware.org/?probe=cf74012060) | Feb 16, 2021 |
| Google        | Gnawty                      | [802daa9713](https://linux-hardware.org/?probe=802daa9713) | Feb 16, 2021 |
| Dell          | Latitude E6520              | [132c1f74fc](https://linux-hardware.org/?probe=132c1f74fc) | Feb 14, 2021 |
| Toshiba       | NI 1403                     | [509417cf38](https://linux-hardware.org/?probe=509417cf38) | Feb 13, 2021 |
| Unknown       | Unknown                     | [289d2b0685](https://linux-hardware.org/?probe=289d2b0685) | Feb 10, 2021 |
| LG Electro... | X120-G.C7VPG                | [349c20610a](https://linux-hardware.org/?probe=349c20610a) | Feb 10, 2021 |
| Dell          | Inspiron 7520               | [f4995bc45c](https://linux-hardware.org/?probe=f4995bc45c) | Feb 07, 2021 |
| Toshiba       | NI 1403                     | [8dd19e0d5b](https://linux-hardware.org/?probe=8dd19e0d5b) | Feb 06, 2021 |
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
| Toshiba       | NI 1403                     | [c65b4686c1](https://linux-hardware.org/?probe=c65b4686c1) | Jan 16, 2021 |
| Matsushita... | CF-19CHB23BE                | [e9fa72450f](https://linux-hardware.org/?probe=e9fa72450f) | Jan 14, 2021 |
| Acer          | Aspire 5930                 | [0826a741c2](https://linux-hardware.org/?probe=0826a741c2) | Jan 13, 2021 |
| Acer          | Aspire 5930                 | [e9f548f926](https://linux-hardware.org/?probe=e9f548f926) | Jan 13, 2021 |
| Toshiba       | NI 1403                     | [f2a6c004f5](https://linux-hardware.org/?probe=f2a6c004f5) | Jan 10, 2021 |
| Dell          | Inspiron 7520               | [f894e05226](https://linux-hardware.org/?probe=f894e05226) | Jan 09, 2021 |
| Unknown       | Unknown                     | [89562751d7](https://linux-hardware.org/?probe=89562751d7) | Jan 08, 2021 |
| Exper         | E10IL1                      | [8a1f9ff144](https://linux-hardware.org/?probe=8a1f9ff144) | Dec 31, 2020 |
| Dell          | Precision M4800             | [10bfd0b228](https://linux-hardware.org/?probe=10bfd0b228) | Dec 27, 2020 |
| Toshiba       | NI 1403                     | [d361c2fd53](https://linux-hardware.org/?probe=d361c2fd53) | Dec 27, 2020 |
| ASUSTek       | K55N                        | [e3edf30a97](https://linux-hardware.org/?probe=e3edf30a97) | Dec 26, 2020 |
| ASUSTek       | K55N                        | [d7630d7410](https://linux-hardware.org/?probe=d7630d7410) | Dec 26, 2020 |
| Apple         | MacBookPro5,5               | [95d4d575bf](https://linux-hardware.org/?probe=95d4d575bf) | Dec 26, 2020 |
| Toshiba       | NI 1403                     | [6fd8e6692a](https://linux-hardware.org/?probe=6fd8e6692a) | Dec 26, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | [c0f1039074](https://linux-hardware.org/?probe=c0f1039074) | Dec 24, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | [5584ad5871](https://linux-hardware.org/?probe=5584ad5871) | Dec 24, 2020 |
| Toshiba       | NI 1403                     | [e3b15b9aab](https://linux-hardware.org/?probe=e3b15b9aab) | Dec 23, 2020 |
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
| Toshiba       | NI 1403                     | [73fff8bebf](https://linux-hardware.org/?probe=73fff8bebf) | Dec 13, 2020 |
| Toshiba       | NI 1403                     | [e8b1e86c0c](https://linux-hardware.org/?probe=e8b1e86c0c) | Dec 12, 2020 |
| Toshiba       | NI 1403                     | [761cc07d16](https://linux-hardware.org/?probe=761cc07d16) | Dec 11, 2020 |
| Toshiba       | NI 1403                     | [d811cc41d8](https://linux-hardware.org/?probe=d811cc41d8) | Dec 09, 2020 |
| HP            | Pavilion ze2000 (EA772AV... | [15284f8c6e](https://linux-hardware.org/?probe=15284f8c6e) | Dec 07, 2020 |
| Dell          | Precision M4600             | [690e349224](https://linux-hardware.org/?probe=690e349224) | Dec 06, 2020 |
| Dell          | Precision M4600             | [f2023ec8ae](https://linux-hardware.org/?probe=f2023ec8ae) | Dec 06, 2020 |
| Acer          | Extensa 4620                | [1bda4268f4](https://linux-hardware.org/?probe=1bda4268f4) | Dec 04, 2020 |
| Matsushita... | CF-19CHB23BE                | [26a940a651](https://linux-hardware.org/?probe=26a940a651) | Dec 01, 2020 |
| Matsushita... | CF-19CHB23BE                | [a81d111827](https://linux-hardware.org/?probe=a81d111827) | Nov 25, 2020 |
| ASUSTek       | X550VX                      | [b22a35a959](https://linux-hardware.org/?probe=b22a35a959) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [18d99f9e4f](https://linux-hardware.org/?probe=18d99f9e4f) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [c17dc0982c](https://linux-hardware.org/?probe=c17dc0982c) | Nov 22, 2020 |
| Lenovo        | ThinkPad T60p 8742C4G       | [9d369e30fd](https://linux-hardware.org/?probe=9d369e30fd) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | [dbac4eb570](https://linux-hardware.org/?probe=dbac4eb570) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | [b070b2d112](https://linux-hardware.org/?probe=b070b2d112) | Nov 18, 2020 |
| HP            | Compaq Presario CQ60        | [c9f4c7eefd](https://linux-hardware.org/?probe=c9f4c7eefd) | Nov 16, 2020 |
| HP            | Unknown                     | [b525a6fdd2](https://linux-hardware.org/?probe=b525a6fdd2) | Nov 15, 2020 |
| Toshiba       | NI 1403                     | [7c9600b0bb](https://linux-hardware.org/?probe=7c9600b0bb) | Nov 14, 2020 |
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
| Toshiba       | NI 1403                     | [07e61e6f8d](https://linux-hardware.org/?probe=07e61e6f8d) | Nov 02, 2020 |
| Dell          | Latitude E6220              | [b3af9d8439](https://linux-hardware.org/?probe=b3af9d8439) | Oct 30, 2020 |
| Dell          | Latitude E6220              | [7df244c05f](https://linux-hardware.org/?probe=7df244c05f) | Oct 30, 2020 |
| Dell          | Inspiron 3521               | [c85f72911e](https://linux-hardware.org/?probe=c85f72911e) | Oct 29, 2020 |
| HP            | EliteBook 8470p             | [dd6fd8b99c](https://linux-hardware.org/?probe=dd6fd8b99c) | Oct 24, 2020 |
| HP            | EliteBook 8470p             | [da38172964](https://linux-hardware.org/?probe=da38172964) | Oct 24, 2020 |
| ASUSTek       | X551MA                      | [bc2de7b987](https://linux-hardware.org/?probe=bc2de7b987) | Oct 23, 2020 |
| ASUSTek       | X551MA                      | [ad50a3e36d](https://linux-hardware.org/?probe=ad50a3e36d) | Oct 22, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [c00341fecd](https://linux-hardware.org/?probe=c00341fecd) | Oct 21, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [83c0ae72b0](https://linux-hardware.org/?probe=83c0ae72b0) | Oct 21, 2020 |
| Unknown       | Unknown                     | [f786cfb7ca](https://linux-hardware.org/?probe=f786cfb7ca) | Oct 18, 2020 |
| ASUSTek       | GL503VM                     | [a6705573f8](https://linux-hardware.org/?probe=a6705573f8) | Oct 11, 2020 |
| HP            | EliteBook 8470p             | [27fe34d7e1](https://linux-hardware.org/?probe=27fe34d7e1) | Oct 09, 2020 |
| Acer          | Aspire 5680                 | [3ef4868294](https://linux-hardware.org/?probe=3ef4868294) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [0053b1ef76](https://linux-hardware.org/?probe=0053b1ef76) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [e63d95d346](https://linux-hardware.org/?probe=e63d95d346) | Oct 07, 2020 |
| Lenovo        | B71-80 80RJ                 | [a5135ffb54](https://linux-hardware.org/?probe=a5135ffb54) | Oct 04, 2020 |
| Dell          | Latitude E6400              | [5d51e1eab7](https://linux-hardware.org/?probe=5d51e1eab7) | Oct 04, 2020 |
| Lenovo        | B71-80 80RJ                 | [ac6a6e6885](https://linux-hardware.org/?probe=ac6a6e6885) | Oct 03, 2020 |
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
| HP            | EliteBook 8540w             | [7846423802](https://linux-hardware.org/?probe=7846423802) | May 28, 2020 |
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
| Toshiba       | Satellite U300              | [8859e175ba](https://linux-hardware.org/?probe=8859e175ba) | May 06, 2020 |
| Dell          | Latitude E5570              | [20fc42be1b](https://linux-hardware.org/?probe=20fc42be1b) | May 06, 2020 |
| Dell          | Inspiron N411Z              | [246dd5ce2a](https://linux-hardware.org/?probe=246dd5ce2a) | May 05, 2020 |
| Dell          | Latitude E5570              | [a1b049e54c](https://linux-hardware.org/?probe=a1b049e54c) | May 05, 2020 |
| Toshiba       | Satellite U300              | [3bd62e1a59](https://linux-hardware.org/?probe=3bd62e1a59) | May 05, 2020 |
| HP            | Laptop 15-bs2xx             | [6d47f83eac](https://linux-hardware.org/?probe=6d47f83eac) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | [154605446a](https://linux-hardware.org/?probe=154605446a) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | [e9544d771b](https://linux-hardware.org/?probe=e9544d771b) | May 02, 2020 |
| HP            | G42                         | [be1ea8571f](https://linux-hardware.org/?probe=be1ea8571f) | Apr 28, 2020 |
| Lenovo        | ThinkPad E490 20N80017RT    | [7f84d5a0f2](https://linux-hardware.org/?probe=7f84d5a0f2) | Apr 28, 2020 |
| HP            | G42                         | [e1ec91bd2e](https://linux-hardware.org/?probe=e1ec91bd2e) | Apr 27, 2020 |
| HP            | G42                         | [8ea8320eac](https://linux-hardware.org/?probe=8ea8320eac) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | [b314d76130](https://linux-hardware.org/?probe=b314d76130) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | [7984248cab](https://linux-hardware.org/?probe=7984248cab) | Apr 26, 2020 |
| Acer          | Aspire E1-572               | [e64e2fe71c](https://linux-hardware.org/?probe=e64e2fe71c) | Apr 23, 2020 |
| HP            | Laptop 15-bs2xx             | [477c5d9ffa](https://linux-hardware.org/?probe=477c5d9ffa) | Apr 17, 2020 |
| Positivo      | MOBILE                      | [c7cc7cd357](https://linux-hardware.org/?probe=c7cc7cd357) | Apr 17, 2020 |
| Positivo      | MOBILE                      | [55b84972df](https://linux-hardware.org/?probe=55b84972df) | Apr 17, 2020 |
| Unknown       | Unknown                     | [4d06bdc501](https://linux-hardware.org/?probe=4d06bdc501) | Apr 14, 2020 |
| Unknown       | Unknown                     | [d5bf1ee748](https://linux-hardware.org/?probe=d5bf1ee748) | Apr 14, 2020 |
| Unknown       | Unknown                     | [67167458d8](https://linux-hardware.org/?probe=67167458d8) | Apr 14, 2020 |
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
| 4.19.0-8-amd64       | 27        | 12.27%  |
| 4.19.0-17-amd64      | 20        | 9.09%   |
| 4.19.0-9-amd64       | 18        | 8.18%   |
| 4.19.0-16-amd64      | 16        | 7.27%   |
| 4.19.0-14-amd64      | 15        | 6.82%   |
| 4.19.0-18-amd64      | 13        | 5.91%   |
| 4.19.0-17-686        | 13        | 5.91%   |
| 4.19.0-13-amd64      | 12        | 5.45%   |
| 4.19.0-10-amd64      | 12        | 5.45%   |
| 4.19.0-8-686         | 11        | 5%      |
| 4.19.0-16-686        | 11        | 5%      |
| 4.19.0-12-amd64      | 11        | 5%      |
| 4.19.0-13-686        | 7         | 3.18%   |
| 4.19.0-11-amd64      | 6         | 2.73%   |
| 4.19.0-18-686        | 5         | 2.27%   |
| 4.19.0-12-686        | 5         | 2.27%   |
| 4.19.0-14-686        | 3         | 1.36%   |
| 5.4.0-0.bpo.4-amd64  | 2         | 0.91%   |
| 5.10.0-0.bpo.5-amd64 | 2         | 0.91%   |
| 5.9.12-davius        | 1         | 0.45%   |
| 5.9.0-0.bpo.5-amd64  | 1         | 0.45%   |
| 5.8.0-0.bpo.2-amd64  | 1         | 0.45%   |
| 5.6.0-2-amd64        | 1         | 0.45%   |
| 5.6.0-2-686-pae      | 1         | 0.45%   |
| 5.4.44-xanmod1       | 1         | 0.45%   |
| 5.10.0-0.bpo.3-amd64 | 1         | 0.45%   |
| 4.19.0-9-686         | 1         | 0.45%   |
| 4.19.0-14-686-pae    | 1         | 0.45%   |
| 4.19.0-12-rt-amd64   | 1         | 0.45%   |
| 4.19.0-10-686        | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19.0  | 189       | 94.5%   |
| 5.10.0  | 3         | 1.5%    |
| 5.6.0   | 2         | 1%      |
| 5.4.0   | 2         | 1%      |
| 5.9.12  | 1         | 0.5%    |
| 5.9.0   | 1         | 0.5%    |
| 5.8.0   | 1         | 0.5%    |
| 5.4.44  | 1         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19    | 189       | 94.5%   |
| 5.4     | 3         | 1.5%    |
| 5.10    | 3         | 1.5%    |
| 5.9     | 2         | 1%      |
| 5.6     | 2         | 1%      |
| 5.8     | 1         | 0.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 142       | 71.36%  |
| i686   | 57        | 28.64%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 184       | 92%     |
| Cinnamon   | 7         | 3.5%    |
| Unknown    | 4         | 2%      |
| MATE       | 2         | 1%      |
| XFCE       | 1         | 0.5%    |
| Trinity    | 1         | 0.5%    |
| KDE        | 1         | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 199       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 180       | 90.45%  |
| TDM     | 10        | 5.03%   |
| LightDM | 9         | 4.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 56        | 27.86%  |
| pt_BR   | 21        | 10.45%  |
| de_DE   | 21        | 10.45%  |
| pl_PL   | 9         | 4.48%   |
| en_GB   | 9         | 4.48%   |
| ru_RU   | 8         | 3.98%   |
| es_AR   | 6         | 2.99%   |
| en_AU   | 6         | 2.99%   |
| it_IT   | 5         | 2.49%   |
| fr_FR   | 5         | 2.49%   |
| es_MX   | 5         | 2.49%   |
| es_ES   | 5         | 2.49%   |
| de_CH   | 5         | 2.49%   |
| en_CA   | 4         | 1.99%   |
| nl_NL   | 3         | 1.49%   |
| ja_JP   | 3         | 1.49%   |
| en_ZA   | 2         | 1%      |
| en_PH   | 2         | 1%      |
| en_IN   | 2         | 1%      |
| el_GR   | 2         | 1%      |
| de_AT   | 2         | 1%      |
| bg_BG   | 2         | 1%      |
| zh_CN   | 1         | 0.5%    |
| unm_US  | 1         | 0.5%    |
| uk_UA   | 1         | 0.5%    |
| tr_TR   | 1         | 0.5%    |
| sk_SK   | 1         | 0.5%    |
| ru_UA   | 1         | 0.5%    |
| pt_PT   | 1         | 0.5%    |
| nl_BE   | 1         | 0.5%    |
| it_CH   | 1         | 0.5%    |
| hr_HR   | 1         | 0.5%    |
| fr_BE   | 1         | 0.5%    |
| et_EE   | 1         | 0.5%    |
| es_CL   | 1         | 0.5%    |
| en_SG   | 1         | 0.5%    |
| en_NZ   | 1         | 0.5%    |
| da_DK   | 1         | 0.5%    |
| ca_ES   | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 144       | 71.64%  |
| EFI  | 57        | 28.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 192       | 96.48%  |
| Btrfs   | 4         | 2.01%   |
| Tmpfs   | 2         | 1.01%   |
| Overlay | 1         | 0.5%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 175       | 87.94%  |
| GPT     | 13        | 6.53%   |
| MBR     | 11        | 5.53%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 190       | 95.48%  |
| Yes       | 9         | 4.52%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 192       | 96.48%  |
| Yes       | 7         | 3.52%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 44        | 22.11%  |
| Dell                           | 26        | 13.07%  |
| Lenovo                         | 25        | 12.56%  |
| Acer                           | 25        | 12.56%  |
| ASUSTek Computer               | 23        | 11.56%  |
| Toshiba                        | 8         | 4.02%   |
| Samsung Electronics            | 6         | 3.02%   |
| Sony                           | 5         | 2.51%   |
| Fujitsu Siemens                | 4         | 2.01%   |
| Unknown                        | 4         | 2.01%   |
| Positivo                       | 3         | 1.51%   |
| LG Electronics                 | 3         | 1.51%   |
| MSI                            | 2         | 1.01%   |
| Matsushita Electric Industrial | 2         | 1.01%   |
| Gateway                        | 2         | 1.01%   |
| Fujitsu                        | 2         | 1.01%   |
| Apple                          | 2         | 1.01%   |
| TUXEDO                         | 1         | 0.5%    |
| Semp Toshiba                   | 1         | 0.5%    |
| SAELITE                        | 1         | 0.5%    |
| Qbex                           | 1         | 0.5%    |
| Packard Bell                   | 1         | 0.5%    |
| Medion                         | 1         | 0.5%    |
| Maibenben                      | 1         | 0.5%    |
| Itautec                        | 1         | 0.5%    |
| IBM                            | 1         | 0.5%    |
| Google                         | 1         | 0.5%    |
| Exper                          | 1         | 0.5%    |
| Exo                            | 1         | 0.5%    |
| Advent                         | 1         | 0.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 8         | 4.02%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 2         | 1.01%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 2         | 1.01%   |
| HP Pavilion dv6                             | 2         | 1.01%   |
| HP EliteBook 8540w                          | 2         | 1.01%   |
| Acer Aspire 5735                            | 2         | 1.01%   |
| Acer Aspire 3000                            | 2         | 1.01%   |
| TUXEDO BC1510 1710                          | 1         | 0.5%    |
| Toshiba Satellite U300                      | 1         | 0.5%    |
| Toshiba Satellite P300                      | 1         | 0.5%    |
| Toshiba Satellite M100                      | 1         | 0.5%    |
| Toshiba Satellite L855                      | 1         | 0.5%    |
| Toshiba Satellite L750                      | 1         | 0.5%    |
| Toshiba Satellite L50-C                     | 1         | 0.5%    |
| Toshiba Satellite C50-A-1DN                 | 1         | 0.5%    |
| Toshiba dynabook Satellite J61 173C/5       | 1         | 0.5%    |
| Sony VPCS131FM                              | 1         | 0.5%    |
| Sony VPCP116KG                              | 1         | 0.5%    |
| Sony VGN-FZ140E                             | 1         | 0.5%    |
| Sony VGN-AW41MF_H                           | 1         | 0.5%    |
| Sony SVE1511N1ESI                           | 1         | 0.5%    |
| Semp Toshiba NI 1403                        | 1         | 0.5%    |
| Samsung RV413/RV513                         | 1         | 0.5%    |
| Samsung R59/R60/R61                         | 1         | 0.5%    |
| Samsung NC10                                | 1         | 0.5%    |
| Samsung 305U1A                              | 1         | 0.5%    |
| SAELITE ES1AU11                             | 1         | 0.5%    |
| Qbex UDPAIOQBEX01                           | 1         | 0.5%    |
| Positivo W310CZ-T                           | 1         | 0.5%    |
| Positivo MOBILE                             | 1         | 0.5%    |
| Positivo H14CU01                            | 1         | 0.5%    |
| Packard Bell EasyNote_NJ66                  | 1         | 0.5%    |
| MSI GT70 2PC                                | 1         | 0.5%    |
| MSI FX610                                   | 1         | 0.5%    |
| Medion P6670 MD99960                        | 1         | 0.5%    |
| Matsushita Electric Industrial CF-19DDGZXVM | 1         | 0.5%    |
| Matsushita Electric Industrial CF-19CHB23BE | 1         | 0.5%    |
| Maibenben XiaoMai5                          | 1         | 0.5%    |
| LG X300-L.CR31B1                            | 1         | 0.5%    |
| LG X120-G.C7VPG                             | 1         | 0.5%    |
| LG A530-T.BE76P1                            | 1         | 0.5%    |
| Lenovo Yoga 2 11 20428                      | 1         | 0.5%    |
| Lenovo Y50-70 20378                         | 1         | 0.5%    |
| Lenovo V145-15AST 81MT                      | 1         | 0.5%    |
| Lenovo ThinkPad X60 1706AA7                 | 1         | 0.5%    |
| Lenovo ThinkPad X230 2325CN3                | 1         | 0.5%    |
| Lenovo ThinkPad X100e 28762FP               | 1         | 0.5%    |
| Lenovo ThinkPad T61 6457W9X                 | 1         | 0.5%    |
| Lenovo ThinkPad T60p 8742C4G                | 1         | 0.5%    |
| Lenovo ThinkPad T530 2394BK7                | 1         | 0.5%    |
| Lenovo ThinkPad T440p 20AWA1NAUK            | 1         | 0.5%    |
| Lenovo ThinkPad T420s 4174EK3               | 1         | 0.5%    |
| Lenovo ThinkPad T400 64741EG                | 1         | 0.5%    |
| Lenovo ThinkPad SL510 28752NG               | 1         | 0.5%    |
| Lenovo ThinkPad L450 20DSS00N18             | 1         | 0.5%    |
| Lenovo ThinkPad E495 20NE001MRT             | 1         | 0.5%    |
| Lenovo ThinkPad E490 20N80017RT             | 1         | 0.5%    |
| Lenovo IdeaPad Y700 Touch-15ISK 80NW        | 1         | 0.5%    |
| Lenovo IdeaPad 330S-14AST 81F8              | 1         | 0.5%    |
| Lenovo IdeaPad 330-15AST 81D6               | 1         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Acer Aspire                                 | 23        | 11.56%  |
| Lenovo ThinkPad                             | 13        | 6.53%   |
| Dell Latitude                               | 11        | 5.53%   |
| HP Pavilion                                 | 10        | 5.03%   |
| Dell Inspiron                               | 10        | 5.03%   |
| Unknown                                     | 8         | 4.02%   |
| Toshiba Satellite                           | 7         | 3.52%   |
| HP Laptop                                   | 6         | 3.02%   |
| HP Compaq                                   | 6         | 3.02%   |
| Lenovo IdeaPad                              | 5         | 2.51%   |
| HP EliteBook                                | 5         | 2.51%   |
| Fujitsu Siemens ESPRIMO                     | 3         | 1.51%   |
| Dell Precision                              | 3         | 1.51%   |
| Samsung RV411                               | 2         | 1.01%   |
| HP Presario                                 | 2         | 1.01%   |
| Apple MacBookPro5                           | 2         | 1.01%   |
| TUXEDO BC1510                               | 1         | 0.5%    |
| Toshiba dynabook                            | 1         | 0.5%    |
| Sony VPCS131FM                              | 1         | 0.5%    |
| Sony VPCP116KG                              | 1         | 0.5%    |
| Sony VGN-FZ140E                             | 1         | 0.5%    |
| Sony VGN-AW41MF                             | 1         | 0.5%    |
| Sony SVE1511N1ESI                           | 1         | 0.5%    |
| Semp Toshiba NI                             | 1         | 0.5%    |
| Samsung RV413                               | 1         | 0.5%    |
| Samsung R59                                 | 1         | 0.5%    |
| Samsung NC10                                | 1         | 0.5%    |
| Samsung 305U1A                              | 1         | 0.5%    |
| SAELITE ES1AU11                             | 1         | 0.5%    |
| Qbex UDPAIOQBEX01                           | 1         | 0.5%    |
| Positivo W310CZ-T                           | 1         | 0.5%    |
| Positivo MOBILE                             | 1         | 0.5%    |
| Positivo H14CU01                            | 1         | 0.5%    |
| Packard Bell EasyNote                       | 1         | 0.5%    |
| MSI GT70                                    | 1         | 0.5%    |
| MSI FX610                                   | 1         | 0.5%    |
| Medion P6670                                | 1         | 0.5%    |
| Matsushita Electric Industrial CF-19DDGZXVM | 1         | 0.5%    |
| Matsushita Electric Industrial CF-19CHB23BE | 1         | 0.5%    |
| Maibenben XiaoMai5                          | 1         | 0.5%    |
| LG X300-L.CR31B1                            | 1         | 0.5%    |
| LG X120-G.C7VPG                             | 1         | 0.5%    |
| LG A530-T.BE76P1                            | 1         | 0.5%    |
| Lenovo Yoga                                 | 1         | 0.5%    |
| Lenovo Y50-70                               | 1         | 0.5%    |
| Lenovo V145-15AST                           | 1         | 0.5%    |
| Lenovo G50-45                               | 1         | 0.5%    |
| Lenovo G40-30                               | 1         | 0.5%    |
| Lenovo E41-25                               | 1         | 0.5%    |
| Lenovo B71-80                               | 1         | 0.5%    |
| Itautec Infoway                             | 1         | 0.5%    |
| IBM ThinkPad                                | 1         | 0.5%    |
| HP TouchSmart                               | 1         | 0.5%    |
| HP ProBook                                  | 1         | 0.5%    |
| HP Notebook                                 | 1         | 0.5%    |
| HP Mini                                     | 1         | 0.5%    |
| HP G61                                      | 1         | 0.5%    |
| HP G42                                      | 1         | 0.5%    |
| HP 530                                      | 1         | 0.5%    |
| HP 520                                      | 1         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 25        | 12.56%  |
| 2009    | 23        | 11.56%  |
| 2010    | 17        | 8.54%   |
| 2012    | 16        | 8.04%   |
| 2020    | 14        | 7.04%   |
| 2013    | 14        | 7.04%   |
| 2008    | 13        | 6.53%   |
| 2015    | 12        | 6.03%   |
| 2007    | 12        | 6.03%   |
| 2014    | 11        | 5.53%   |
| 2011    | 11        | 5.53%   |
| 2006    | 8         | 4.02%   |
| 2016    | 7         | 3.52%   |
| 2018    | 6         | 3.02%   |
| 2017    | 4         | 2.01%   |
| 2005    | 4         | 2.01%   |
| 2003    | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 199       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 191       | 95.5%   |
| Enabled  | 9         | 4.5%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 198       | 99.5%   |
| Yes  | 1         | 0.5%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 63        | 31.5%   |
| 4.01-8.0   | 34        | 17%     |
| 2.01-3.0   | 32        | 16%     |
| 1.01-2.0   | 28        | 14%     |
| 16.01-24.0 | 21        | 10.5%   |
| 8.01-16.0  | 12        | 6%      |
| 0.51-1.0   | 7         | 3.5%    |
| 32.01-64.0 | 2         | 1%      |
| 24.01-32.0 | 1         | 0.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 110       | 51.64%  |
| 0.51-1.0  | 49        | 23%     |
| 2.01-3.0  | 30        | 14.08%  |
| 3.01-4.0  | 14        | 6.57%   |
| 4.01-8.0  | 4         | 1.88%   |
| 8.01-16.0 | 3         | 1.41%   |
| 0.01-0.5  | 3         | 1.41%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 146       | 71.92%  |
| 2      | 45        | 22.17%  |
| 3      | 6         | 2.96%   |
| 0      | 3         | 1.48%   |
| 6      | 1         | 0.49%   |
| 5      | 1         | 0.49%   |
| 4      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 125       | 62.19%  |
| No        | 76        | 37.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 188       | 94.47%  |
| No        | 11        | 5.53%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 196       | 98.49%  |
| No        | 3         | 1.51%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 54.77%  |
| No        | 90        | 45.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 24        | 12.06%  |
| Germany             | 23        | 11.56%  |
| Brazil              | 22        | 11.06%  |
| Poland              | 9         | 4.52%   |
| UK                  | 8         | 4.02%   |
| Italy               | 7         | 3.52%   |
| Australia           | 7         | 3.52%   |
| Switzerland         | 6         | 3.02%   |
| Spain               | 6         | 3.02%   |
| Netherlands         | 6         | 3.02%   |
| Mexico              | 6         | 3.02%   |
| Bulgaria            | 6         | 3.02%   |
| Argentina           | 6         | 3.02%   |
| France              | 5         | 2.51%   |
| Canada              | 5         | 2.51%   |
| Ukraine             | 4         | 2.01%   |
| Russia              | 4         | 2.01%   |
| Philippines         | 3         | 1.51%   |
| India               | 3         | 1.51%   |
| Bahrain             | 3         | 1.51%   |
| Austria             | 3         | 1.51%   |
| Turkey              | 2         | 1.01%   |
| Tunisia             | 2         | 1.01%   |
| South Africa        | 2         | 1.01%   |
| Japan               | 2         | 1.01%   |
| Indonesia           | 2         | 1.01%   |
| Greece              | 2         | 1.01%   |
| China               | 2         | 1.01%   |
| Belarus             | 2         | 1.01%   |
| Venezuela           | 1         | 0.5%    |
| Trinidad and Tobago | 1         | 0.5%    |
| Singapore           | 1         | 0.5%    |
| Romania             | 1         | 0.5%    |
| Portugal            | 1         | 0.5%    |
| New Zealand         | 1         | 0.5%    |
| Luxembourg          | 1         | 0.5%    |
| Ireland             | 1         | 0.5%    |
| Honduras            | 1         | 0.5%    |
| Estonia             | 1         | 0.5%    |
| Egypt               | 1         | 0.5%    |
| Dominican Republic  | 1         | 0.5%    |
| Denmark             | 1         | 0.5%    |
| Croatia             | 1         | 0.5%    |
| Chile               | 1         | 0.5%    |
| Belgium             | 1         | 0.5%    |
| Bangladesh          | 1         | 0.5%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Zurich            | 5         | 2.38%   |
| Sofia             | 3         | 1.43%   |
| Poznan            | 3         | 1.43%   |
| Manama            | 3         | 1.43%   |
| Frankfurt am Main | 3         | 1.43%   |
| Wroclaw           | 2         | 0.95%   |
| São Paulo        | 2         | 0.95%   |
| Sydney            | 2         | 0.95%   |
| Seville           | 2         | 0.95%   |
| Perth             | 2         | 0.95%   |
| Penhold           | 2         | 0.95%   |
| Paris             | 2         | 0.95%   |
| Manila            | 2         | 0.95%   |
| Madrid            | 2         | 0.95%   |
| Foz do Iguaçu    | 2         | 0.95%   |
| Denver            | 2         | 0.95%   |
| Cologne           | 2         | 0.95%   |
| Cape Town         | 2         | 0.95%   |
| Buenos Aires      | 2         | 0.95%   |
| Zhukovskiy        | 1         | 0.48%   |
| Zhongshan         | 1         | 0.48%   |
| Zapopan           | 1         | 0.48%   |
| Zagreb            | 1         | 0.48%   |
| Yokohama          | 1         | 0.48%   |
| Yevpatoriya       | 1         | 0.48%   |
| Yan'anshi         | 1         | 0.48%   |
| Wünnenberg       | 1         | 0.48%   |
| Whittier          | 1         | 0.48%   |
| Wellington        | 1         | 0.48%   |
| Weatherford       | 1         | 0.48%   |
| Warsaw            | 1         | 0.48%   |
| Waalre            | 1         | 0.48%   |
| Voluntari         | 1         | 0.48%   |
| Vitebsk           | 1         | 0.48%   |
| Vila Matias       | 1         | 0.48%   |
| Vicosa            | 1         | 0.48%   |
| Verona            | 1         | 0.48%   |
| Vaassen           | 1         | 0.48%   |
| Turin             | 1         | 0.48%   |
| Tunis             | 1         | 0.48%   |
| Tilburg           | 1         | 0.48%   |
| Thessaloniki      | 1         | 0.48%   |
| The Hague         | 1         | 0.48%   |
| Taquaritinga      | 1         | 0.48%   |
| São Luís        | 1         | 0.48%   |
| Surabaya          | 1         | 0.48%   |
| Stuttgart         | 1         | 0.48%   |
| St Petersburg     | 1         | 0.48%   |
| St Louis          | 1         | 0.48%   |
| Springfield       | 1         | 0.48%   |
| Soborg            | 1         | 0.48%   |
| Singapore         | 1         | 0.48%   |
| Siemysl           | 1         | 0.48%   |
| Sicamous          | 1         | 0.48%   |
| Sfax              | 1         | 0.48%   |
| Scarborough       | 1         | 0.48%   |
| S??o Paulo        | 1         | 0.48%   |
| Sarow             | 1         | 0.48%   |
| Sao Sebastiao     | 1         | 0.48%   |
| Sao Jose          | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 39        | 46     | 16.12%  |
| Seagate             | 34        | 46     | 14.05%  |
| Samsung Electronics | 34        | 37     | 14.05%  |
| Toshiba             | 19        | 21     | 7.85%   |
| Hitachi             | 17        | 17     | 7.02%   |
| Unknown             | 13        | 14     | 5.37%   |
| Kingston            | 11        | 13     | 4.55%   |
| HGST                | 9         | 9      | 3.72%   |
| SanDisk             | 8         | 11     | 3.31%   |
| Crucial             | 7         | 9      | 2.89%   |
| Fujitsu             | 6         | 6      | 2.48%   |
| Intel               | 5         | 5      | 2.07%   |
| SK Hynix            | 4         | 8      | 1.65%   |
| GOODRAM             | 3         | 3      | 1.24%   |
| China               | 3         | 3      | 1.24%   |
| Transcend           | 2         | 2      | 0.83%   |
| Phison              | 2         | 3      | 0.83%   |
| Micron Technology   | 2         | 2      | 0.83%   |
| KingSpec            | 2         | 2      | 0.83%   |
| KingDian            | 2         | 3      | 0.83%   |
| Intenso             | 2         | 2      | 0.83%   |
| IBM/Hitachi         | 2         | 2      | 0.83%   |
| USB30               | 1         | 2      | 0.41%   |
| PNY                 | 1         | 1      | 0.41%   |
| Patriot             | 1         | 3      | 0.41%   |
| Netac               | 1         | 1      | 0.41%   |
| Mushkin             | 1         | 1      | 0.41%   |
| JMicron             | 1         | 2      | 0.41%   |
| HUAWEI              | 1         | 1      | 0.41%   |
| Hikvision           | 1         | 1      | 0.41%   |
| Hewlett-Packard     | 1         | 2      | 0.41%   |
| Gigabyte Technology | 1         | 2      | 0.41%   |
| GALAX               | 1         | 1      | 0.41%   |
| FORESEE             | 1         | 1      | 0.41%   |
| DREVO               | 1         | 1      | 0.41%   |
| DAS                 | 1         | 4      | 0.41%   |
| CORSAIR             | 1         | 1      | 0.41%   |
| BAITITON            | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB          | 6         | 2.44%   |
| Samsung SSD 860 EVO 1TB            | 4         | 1.63%   |
| WDC WD3200BEVT-60ZCT1 320GB        | 3         | 1.22%   |
| Unknown MMC Card  7GB              | 3         | 1.22%   |
| Unknown MMC Card  32GB             | 3         | 1.22%   |
| Toshiba MQ01ABD100 1TB             | 3         | 1.22%   |
| Seagate ST9500325AS 500GB          | 3         | 1.22%   |
| Seagate ST500LT012-1DG142 500GB    | 3         | 1.22%   |
| Kingston SA400S37240G 240GB SSD    | 3         | 1.22%   |
| WDC WD7500BPVT-75HXZT3 752GB       | 2         | 0.81%   |
| WDC WD2500BEVT-22ZCT0 250GB        | 2         | 0.81%   |
| WDC WD1200BEVS-22UST0 120GB        | 2         | 0.81%   |
| Unknown MMC Card  16GB             | 2         | 0.81%   |
| Toshiba MQ01ABF050 500GB           | 2         | 0.81%   |
| Toshiba MQ01ABD032 320GB           | 2         | 0.81%   |
| Seagate ST9250315AS 250GB          | 2         | 0.81%   |
| Seagate ST9120821AS 120GB          | 2         | 0.81%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.81%   |
| Seagate Expansion 1TB              | 2         | 0.81%   |
| Sandisk NVMe SSD Drive 256GB       | 2         | 0.81%   |
| Samsung SSD 860 EVO 250GB          | 2         | 0.81%   |
| Samsung SSD 850 EVO 500GB          | 2         | 0.81%   |
| Hitachi HTS725050A9A364 500GB      | 2         | 0.81%   |
| Hitachi HTS545032B9A300 320GB      | 2         | 0.81%   |
| Hitachi HTS543216L9A300 160GB      | 2         | 0.81%   |
| HGST HTS721010A9E630 1TB           | 2         | 0.81%   |
| HGST HTS545050A7E680 500GB         | 2         | 0.81%   |
| HGST HTS541010A9E680 1TB           | 2         | 0.81%   |
| GOODRAM SSDPR-CL100-120-G3 120GB   | 2         | 0.81%   |
| China SATA SSD 120GB               | 2         | 0.81%   |
| WDC WDS240G2G0B 240GB SSD          | 1         | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1         | 0.41%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 1         | 0.41%   |
| WDC WDBNCE5000PNC 500GB SSD        | 1         | 0.41%   |
| WDC WD800BEVE-00A0HT0 80GB         | 1         | 0.41%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 0.41%   |
| WDC WD5000LPCX-60VHAT1 500GB       | 1         | 0.41%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 0.41%   |
| WDC WD5000LPCX-22VHAT1 500GB       | 1         | 0.41%   |
| WDC WD5000LPCX-00VHAT0 500GB       | 1         | 0.41%   |
| WDC WD5000BPVT-22HXZT1 500GB       | 1         | 0.41%   |
| WDC WD5000BEVT-60A0RT0 500GB       | 1         | 0.41%   |
| WDC WD3200LPLX-75ZNTT0 320GB       | 1         | 0.41%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 0.41%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 0.41%   |
| WDC WD3200BEVT-11ZCT0 320GB        | 1         | 0.41%   |
| WDC WD2500BEVT-75ZCT2 250GB        | 1         | 0.41%   |
| WDC WD2500BEVT-75A23T0 250GB       | 1         | 0.41%   |
| WDC WD1600BUCT-63TWBY0 160GB       | 1         | 0.41%   |
| WDC WD1600BEVT-75ZCT2 160GB        | 1         | 0.41%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 1         | 0.41%   |
| WDC WD1600BEVT-22A23T0 160GB       | 1         | 0.41%   |
| WDC WD1600BEVS-22RST0 160GB        | 1         | 0.41%   |
| WDC WD10SPZX-75Z10T1 1TB           | 1         | 0.41%   |
| WDC WD10SPZX-60Z10T0 1TB           | 1         | 0.41%   |
| WDC WD10SPZX-22Z10T0 1TB           | 1         | 0.41%   |
| WDC WD10SPZX-21Z10T0 1TB           | 1         | 0.41%   |
| WDC WD10SPZX-00Z10T0 1TB           | 1         | 0.41%   |
| WDC WD10SPCX-00KHST0 1TB           | 1         | 0.41%   |
| WDC PC SN530 NVMe 256GB            | 1         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 34        | 41     | 28.1%   |
| Seagate             | 33        | 45     | 27.27%  |
| Hitachi             | 17        | 17     | 14.05%  |
| Toshiba             | 16        | 18     | 13.22%  |
| HGST                | 9         | 9      | 7.44%   |
| Fujitsu             | 6         | 6      | 4.96%   |
| Samsung Electronics | 3         | 3      | 2.48%   |
| IBM/Hitachi         | 2         | 2      | 1.65%   |
| Unknown             | 1         | 1      | 0.83%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 30        | 33     | 32.26%  |
| Kingston            | 10        | 12     | 10.75%  |
| Crucial             | 7         | 9      | 7.53%   |
| SanDisk             | 5         | 8      | 5.38%   |
| WDC                 | 4         | 4      | 4.3%    |
| Intel               | 4         | 4      | 4.3%    |
| Toshiba             | 3         | 3      | 3.23%   |
| GOODRAM             | 3         | 3      | 3.23%   |
| China               | 3         | 3      | 3.23%   |
| Transcend           | 2         | 2      | 2.15%   |
| SK Hynix            | 2         | 4      | 2.15%   |
| Micron Technology   | 2         | 2      | 2.15%   |
| KingDian            | 2         | 3      | 2.15%   |
| USB30               | 1         | 2      | 1.08%   |
| Unknown             | 1         | 1      | 1.08%   |
| PNY                 | 1         | 1      | 1.08%   |
| Patriot             | 1         | 3      | 1.08%   |
| Netac               | 1         | 1      | 1.08%   |
| Mushkin             | 1         | 1      | 1.08%   |
| KingSpec            | 1         | 1      | 1.08%   |
| Intenso             | 1         | 1      | 1.08%   |
| Hikvision           | 1         | 1      | 1.08%   |
| Hewlett-Packard     | 1         | 2      | 1.08%   |
| Gigabyte Technology | 1         | 2      | 1.08%   |
| GALAX               | 1         | 1      | 1.08%   |
| FORESEE             | 1         | 1      | 1.08%   |
| DREVO               | 1         | 1      | 1.08%   |
| CORSAIR             | 1         | 1      | 1.08%   |
| BAITITON            | 1         | 1      | 1.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 116       | 142    | 51.33%  |
| SSD     | 82        | 111    | 36.28%  |
| MMC     | 11        | 12     | 4.87%   |
| NVMe    | 11        | 14     | 4.87%   |
| Unknown | 6         | 10     | 2.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 188       | 242    | 83.93%  |
| SAS  | 14        | 21     | 6.25%   |
| NVMe | 11        | 14     | 4.91%   |
| MMC  | 11        | 12     | 4.91%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 165       | 208    | 83.33%  |
| 0.51-1.0   | 31        | 42     | 15.66%  |
| 1.01-2.0   | 1         | 2      | 0.51%   |
| 4.01-10.0  | 1         | 1      | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 87        | 42.65%  |
| 251-500        | 46        | 22.55%  |
| 51-100         | 24        | 11.76%  |
| 501-1000       | 20        | 9.8%    |
| 21-50          | 10        | 4.9%    |
| More than 3000 | 6         | 2.94%   |
| 1001-2000      | 6         | 2.94%   |
| 2001-3000      | 2         | 0.98%   |
| 1-20           | 2         | 0.98%   |
| Unknown        | 1         | 0.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 99        | 46.05%  |
| 21-50          | 49        | 22.79%  |
| 101-250        | 28        | 13.02%  |
| 51-100         | 21        | 9.77%   |
| 501-1000       | 5         | 2.33%   |
| 251-500        | 4         | 1.86%   |
| More than 3000 | 3         | 1.4%    |
| 2001-3000      | 3         | 1.4%    |
| 1001-2000      | 2         | 0.93%   |
| Unknown        | 1         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate STM9120817AS 120GB          | 1         | 1      | 14.29%  |
| Seagate ST9120821AS 120GB           | 1         | 1      | 14.29%  |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 14.29%  |
| Samsung Electronics MP0402H 40GB    | 1         | 1      | 14.29%  |
| Kingston SV300S37A120G 120GB SSD    | 1         | 1      | 14.29%  |
| Fujitsu MHZ2080BJ FFS G2 80GB       | 1         | 1      | 14.29%  |
| Crucial M4-CT256M4SSD2 256GB        | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 28.57%  |
| SanDisk             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Kingston            | 1         | 1      | 14.29%  |
| Fujitsu             | 1         | 1      | 14.29%  |
| Crucial             | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 50%     |
| Samsung Electronics | 1         | 1      | 25%     |
| Fujitsu             | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 57.14%  |
| SSD  | 3         | 3      | 42.86%  |

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
| Detected | 177       | 264    | 88.94%  |
| Works    | 15        | 18     | 7.54%   |
| Malfunc  | 7         | 7      | 3.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 155       | 75.61%  |
| AMD                              | 26        | 12.68%  |
| Silicon Integrated Systems [SiS] | 6         | 2.93%   |
| Nvidia                           | 6         | 2.93%   |
| Sandisk                          | 4         | 1.95%   |
| SK Hynix                         | 2         | 0.98%   |
| Phison Electronics               | 2         | 0.98%   |
| VIA Technologies                 | 1         | 0.49%   |
| Toshiba America Info Systems     | 1         | 0.49%   |
| Samsung Electronics              | 1         | 0.49%   |
| Kingston Technology Company      | 1         | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 17        | 6.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 14        | 5.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 12        | 4.92%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 12        | 4.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 4.51%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 10        | 4.1%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 10        | 4.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 3.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 8         | 3.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 8         | 3.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 3.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 8         | 3.28%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 7         | 2.87%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 6         | 2.46%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 5         | 2.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 2.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 2.05%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 4         | 1.64%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 4         | 1.64%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 1.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 1.64%   |
| Sandisk Non-Volatile memory controller                                           | 3         | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.23%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.23%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 3         | 1.23%   |
| AMD SB600 IDE                                                                    | 3         | 1.23%   |
| AMD IXP SB4x0 IDE Controller                                                     | 3         | 1.23%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 2         | 0.82%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.82%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.82%   |
| Nvidia MCP67 IDE Controller                                                      | 2         | 0.82%   |
| Nvidia MCP67 AHCI Controller                                                     | 2         | 0.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 2         | 0.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.82%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                     | 2         | 0.82%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 0.82%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 0.82%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 0.82%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.41%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.41%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.41%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.41%   |
| Nvidia MCP79 SATA Controller                                                     | 1         | 0.41%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 0.41%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 0.41%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 0.41%   |
| Intel SSD 660P Series                                                            | 1         | 0.41%   |
| Intel SM35 Chipset SATA AHCI Controller                                          | 1         | 0.41%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.41%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                      | 1         | 0.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.41%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 1         | 0.41%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 0.41%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 147       | 64.19%  |
| IDE  | 60        | 26.2%   |
| NVMe | 12        | 5.24%   |
| RAID | 10        | 4.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 166       | 83.42%  |
| AMD    | 33        | 16.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 5         | 2.51%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 4         | 2.01%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 4         | 2.01%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 4         | 2.01%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.51%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.51%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.51%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 3         | 1.51%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 3         | 1.51%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 1.01%   |
| Intel Genuine CPU T2300 @ 1.66GHz             | 2         | 1.01%   |
| Intel Genuine CPU T2130 @ 1.86GHz             | 2         | 1.01%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.01%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.01%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 1.01%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 1.01%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 2         | 1.01%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 1.01%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.01%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.01%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 1.01%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.01%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 2         | 1.01%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 2         | 1.01%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 1.01%   |
| Intel Core Duo CPU T2400 @ 1.83GHz            | 2         | 1.01%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 1.01%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 2         | 1.01%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.01%   |
| Intel Celeron CPU 900 @ 2.20GHz               | 2         | 1.01%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 1.01%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G | 2         | 1.01%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 1.01%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G  | 2         | 1.01%   |
| AMD 3020e with Radeon Graphics                | 2         | 1.01%   |
| Intel Pentium M processor 2.00GHz             | 1         | 0.5%    |
| Intel Pentium M processor 1600MHz             | 1         | 0.5%    |
| Intel Pentium M processor 1.86GHz             | 1         | 0.5%    |
| Intel Pentium M processor 1.73GHz             | 1         | 0.5%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.5%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.5%    |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 0.5%    |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 1         | 0.5%    |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.5%    |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 0.5%    |
| Intel Pentium Dual CPU T2310 @ 1.46GHz        | 1         | 0.5%    |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.5%    |
| Intel Pentium CPU P6100 @ 2.00GHz             | 1         | 0.5%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.5%    |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.5%    |
| Intel Pentium CPU 4415U @ 2.30GHz             | 1         | 0.5%    |
| Intel Pentium CPU 4405U @ 2.10GHz             | 1         | 0.5%    |
| Intel Pentium 4 CPU 2.80GHz                   | 1         | 0.5%    |
| Intel Pentium 3805U @ 1.90GHz                 | 1         | 0.5%    |
| Intel Mobile Pentium 4 CPU 3.06GHz            | 1         | 0.5%    |
| Intel Genuine CPU U2400 @ 1.06GHz             | 1         | 0.5%    |
| Intel Genuine CPU T2400 @ 1.83GHz             | 1         | 0.5%    |
| Intel Genuine CPU T2080 @ 1.73GHz             | 1         | 0.5%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 30        | 15.08%  |
| Intel Core i7                  | 28        | 14.07%  |
| Intel Core 2 Duo               | 21        | 10.55%  |
| Intel Core i3                  | 17        | 8.54%   |
| Intel Atom                     | 17        | 8.54%   |
| Intel Celeron                  | 15        | 7.54%   |
| Intel Pentium                  | 7         | 3.52%   |
| Intel Genuine                  | 7         | 3.52%   |
| Intel Core 2                   | 6         | 3.02%   |
| Other                          | 5         | 2.51%   |
| Intel Pentium Dual             | 5         | 2.51%   |
| Intel Pentium M                | 4         | 2.01%   |
| Intel Pentium Dual-Core        | 4         | 2.01%   |
| Intel Core Duo                 | 3         | 1.51%   |
| AMD Turion 64 X2 Mobile        | 3         | 1.51%   |
| AMD Ryzen 5                    | 3         | 1.51%   |
| AMD A4                         | 3         | 1.51%   |
| AMD Sempron                    | 2         | 1.01%   |
| AMD Mobile Sempron             | 2         | 1.01%   |
| AMD E2                         | 2         | 1.01%   |
| AMD E                          | 2         | 1.01%   |
| AMD Athlon II                  | 2         | 1.01%   |
| Intel Pentium 4                | 1         | 0.5%    |
| Intel Mobile Pentium 4         | 1         | 0.5%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.5%    |
| AMD Turion 64 Mobile           | 1         | 0.5%    |
| AMD Ryzen 7                    | 1         | 0.5%    |
| AMD Phenom II                  | 1         | 0.5%    |
| AMD Athlon Neo                 | 1         | 0.5%    |
| AMD Athlon 64 X2               | 1         | 0.5%    |
| AMD Athlon                     | 1         | 0.5%    |
| AMD A8                         | 1         | 0.5%    |
| AMD A6                         | 1         | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 136       | 68%     |
| 4      | 32        | 16%     |
| 1      | 31        | 15.5%   |
| 6      | 1         | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 199       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 100       | 50.25%  |
| 1      | 99        | 49.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 168       | 84.42%  |
| 32-bit         | 31        | 15.58%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 8.46%   |
| 0x1067a    | 16        | 7.96%   |
| 0x206a7    | 15        | 7.46%   |
| 0x306a9    | 14        | 6.97%   |
| 0x6fd      | 9         | 4.48%   |
| 0x106c2    | 9         | 4.48%   |
| 0x40651    | 8         | 3.98%   |
| 0x20655    | 7         | 3.48%   |
| 0x06006705 | 7         | 3.48%   |
| 0x6f6      | 6         | 2.99%   |
| 0x6ec      | 6         | 2.99%   |
| 0x406e3    | 6         | 2.99%   |
| 0x306c3    | 5         | 2.49%   |
| 0x30678    | 5         | 2.49%   |
| 0x30661    | 5         | 2.49%   |
| 0x806ea    | 4         | 1.99%   |
| 0x6e8      | 4         | 1.99%   |
| 0x10676    | 4         | 1.99%   |
| 0x806eb    | 3         | 1.49%   |
| 0x506e3    | 3         | 1.49%   |
| 0x306d4    | 3         | 1.49%   |
| 0x20652    | 3         | 1.49%   |
| 0x010000c8 | 3         | 1.49%   |
| 0xf29      | 2         | 1%      |
| 0x806ec    | 2         | 1%      |
| 0x806e9    | 2         | 1%      |
| 0x706a1    | 2         | 1%      |
| 0x6d8      | 2         | 1%      |
| 0x406c3    | 2         | 1%      |
| 0x106e5    | 2         | 1%      |
| 0x106ca    | 2         | 1%      |
| 0x10661    | 2         | 1%      |
| 0x08200103 | 2         | 1%      |
| 0x08108102 | 2         | 1%      |
| 0x02000032 | 2         | 1%      |
| 0x906ed    | 1         | 0.5%    |
| 0x906ea    | 1         | 0.5%    |
| 0x906e9    | 1         | 0.5%    |
| 0x6fb      | 1         | 0.5%    |
| 0x6d6      | 1         | 0.5%    |
| 0x695      | 1         | 0.5%    |
| 0x406c4    | 1         | 0.5%    |
| 0x20661    | 1         | 0.5%    |
| 0x08101016 | 1         | 0.5%    |
| 0x0810100b | 1         | 0.5%    |
| 0x07030106 | 1         | 0.5%    |
| 0x07030105 | 1         | 0.5%    |
| 0x06001119 | 1         | 0.5%    |
| 0x05000119 | 1         | 0.5%    |
| 0x05000029 | 1         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Penryn          | 22        | 11.06%  |
| Core            | 18        | 9.05%   |
| Bonnell         | 17        | 8.54%   |
| SandyBridge     | 16        | 8.04%   |
| KabyLake        | 15        | 7.54%   |
| P6              | 14        | 7.04%   |
| IvyBridge       | 14        | 7.04%   |
| Haswell         | 14        | 7.04%   |
| Westmere        | 10        | 5.03%   |
| Skylake         | 9         | 4.52%   |
| K8 Hammer       | 9         | 4.52%   |
| Silvermont      | 8         | 4.02%   |
| Excavator       | 7         | 3.52%   |
| Zen             | 4         | 2.01%   |
| K10             | 4         | 2.01%   |
| Broadwell       | 3         | 1.51%   |
| Zen+            | 2         | 1.01%   |
| Puma            | 2         | 1.01%   |
| NetBurst        | 2         | 1.01%   |
| Nehalem         | 2         | 1.01%   |
| K8 & K10 hybrid | 2         | 1.01%   |
| Goldmont plus   | 2         | 1.01%   |
| Bobcat          | 2         | 1.01%   |
| Piledriver      | 1         | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 126       | 55.02%  |
| AMD                              | 50        | 21.83%  |
| Nvidia                           | 47        | 20.52%  |
| Silicon Integrated Systems [SiS] | 5         | 2.18%   |
| VIA Technologies                 | 1         | 0.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Notebooks | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 13        | 5.24%   |
| Intel 3rd Gen Core processor Graphics Controller                                           | 13        | 5.24%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 12        | 4.84%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 12        | 4.84%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 7         | 2.82%   |
| Intel Core Processor Integrated Graphics Controller                                        | 7         | 2.82%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 7         | 2.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                                 | 6         | 2.42%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                                 | 6         | 2.42%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 6         | 2.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 6         | 2.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                        | 5         | 2.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 5         | 2.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 5         | 2.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 5         | 2.02%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                            | 5         | 2.02%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                        | 4         | 1.61%   |
| Intel UHD Graphics 620                                                                     | 4         | 1.61%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                  | 4         | 1.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 4         | 1.61%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 3         | 1.21%   |
| Intel HD Graphics 530                                                                      | 3         | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 3         | 1.21%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                          | 3         | 1.21%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 2         | 0.81%   |
| Nvidia GT218M [NVS 3100M]                                                                  | 2         | 0.81%   |
| Nvidia GM108M [GeForce 940MX]                                                              | 2         | 0.81%   |
| Nvidia GM107M [GeForce GTX 960M]                                                           | 2         | 0.81%   |
| Nvidia GK107M [GeForce GT 750M]                                                            | 2         | 0.81%   |
| Nvidia GF119M [NVS 4200M]                                                                  | 2         | 0.81%   |
| Nvidia GF108M [GeForce GT 525M]                                                            | 2         | 0.81%   |
| Nvidia GF108GLM [Quadro 1000M]                                                             | 2         | 0.81%   |
| Nvidia G96CM [GeForce 9600M GT]                                                            | 2         | 0.81%   |
| Nvidia C79 [GeForce 9400M]                                                                 | 2         | 0.81%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                  | 2         | 0.81%   |
| Intel HD Graphics 5500                                                                     | 2         | 0.81%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 2         | 0.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                  | 2         | 0.81%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                    | 2         | 0.81%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]              | 2         | 0.81%   |
| AMD RV350/M10 / RV360/M11 [Mobility Radeon 9600 (PRO) / 9700]                              | 2         | 0.81%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 2         | 0.81%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                    | 2         | 0.81%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 2         | 0.81%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                               | 2         | 0.81%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                          | 1         | 0.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                            | 1         | 0.4%    |
| Nvidia NV34M [GeForce FX Go5300 / Go5350]                                                  | 1         | 0.4%    |
| Nvidia GT216M [GeForce GT 230M]                                                            | 1         | 0.4%    |
| Nvidia GP108M [GeForce MX230]                                                              | 1         | 0.4%    |
| Nvidia GP108M [GeForce MX150]                                                              | 1         | 0.4%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                    | 1         | 0.4%    |
| Nvidia GM108M [GeForce 840M]                                                               | 1         | 0.4%    |
| Nvidia GM107M [GeForce GTX 950M]                                                           | 1         | 0.4%    |
| Nvidia GK208M [GeForce GT 740M]                                                            | 1         | 0.4%    |
| Nvidia GK208BM [GeForce 920M]                                                              | 1         | 0.4%    |
| Nvidia GK106GLM [Quadro K2100M]                                                            | 1         | 0.4%    |
| Nvidia GK104M [GeForce GTX 870M]                                                           | 1         | 0.4%    |
| Nvidia GF119M [GeForce GT 520M]                                                            | 1         | 0.4%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                       | 1         | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 96        | 48.24%  |
| 1 x AMD        | 41        | 20.6%   |
| 1 x Nvidia     | 25        | 12.56%  |
| Intel + Nvidia | 22        | 11.06%  |
| Intel + AMD    | 8         | 4.02%   |
| 1 x SiS        | 5         | 2.51%   |
| 2 x AMD        | 1         | 0.5%    |
| 1 x VIA        | 1         | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 171       | 85.07%  |
| Unknown     | 19        | 9.45%   |
| Proprietary | 11        | 5.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 135       | 67.5%   |
| 0.01-0.5   | 37        | 18.5%   |
| 1.01-2.0   | 13        | 6.5%    |
| 0.51-1.0   | 12        | 6%      |
| 5.01-6.0   | 1         | 0.5%    |
| 3.01-4.0   | 1         | 0.5%    |
| 2.01-3.0   | 1         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 32        | 17.39%  |
| Samsung Electronics     | 30        | 16.3%   |
| LG Display              | 28        | 15.22%  |
| BOE                     | 20        | 10.87%  |
| Chimei Innolux          | 17        | 9.24%   |
| Chi Mei Optoelectronics | 9         | 4.89%   |
| LG Philips              | 7         | 3.8%    |
| Lenovo                  | 5         | 2.72%   |
| HannStar                | 5         | 2.72%   |
| Goldstar                | 5         | 2.72%   |
| CPT                     | 3         | 1.63%   |
| Apple                   | 3         | 1.63%   |
| Sony                    | 2         | 1.09%   |
| Quanta Display          | 2         | 1.09%   |
| InfoVision              | 2         | 1.09%   |
| BenQ                    | 2         | 1.09%   |
| ViewSonic               | 1         | 0.54%   |
| Unknown                 | 1         | 0.54%   |
| Seiko/Epson             | 1         | 0.54%   |
| Philips                 | 1         | 0.54%   |
| PANDA                   | 1         | 0.54%   |
| MLT                     | 1         | 0.54%   |
| InnoLux Display         | 1         | 0.54%   |
| Hewlett-Packard         | 1         | 0.54%   |
| Dell                    | 1         | 0.54%   |
| Belinea                 | 1         | 0.54%   |
| AOC                     | 1         | 0.54%   |
| Acer                    | 1         | 0.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 4         | 2.14%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch          | 3         | 1.6%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 340x190mm 15.3-inch            | 3         | 1.6%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 1.07%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 2         | 1.07%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch     | 2         | 1.07%   |
| Quanta Display LCD Monitor QDS0025 1024x768 304x228mm 15.0-inch          | 2         | 1.07%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 2         | 1.07%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 2         | 1.07%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 1.07%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 2         | 1.07%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 2         | 1.07%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 310x170mm 13.9-inch          | 2         | 1.07%   |
| Chi Mei Optoelectronics LCD Monitor CMO1558 1366x768 344x193mm 15.5-inch | 2         | 1.07%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 2         | 1.07%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 2         | 1.07%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 2         | 1.07%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 2         | 1.07%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 2         | 1.07%   |
| ViewSonic VX2457 VSCB931 1920x1080 520x290mm 23.4-inch                   | 1         | 0.53%   |
| Unknown LCD Monitor XXX AAA                                              | 1         | 0.53%   |
| Sony TV SNYA301 1920x1080 1600x900mm 72.3-inch                           | 1         | 0.53%   |
| Sony AVAMP SNYF700 1920x540                                              | 1         | 0.53%   |
| Seiko/Epson LCD Monitor 1920x1080                                        | 1         | 0.53%   |
| Samsung Electronics SMB2230H SAM0648 1920x1080                           | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC554E 1024x600 223x125mm 10.1-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4642 1280x800 303x190mm 14.1-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 303x190mm 14.1-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 303x190mm 14.1-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3659 1600x900 344x194mm 15.5-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3651 1366x768 344x194mm 15.5-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3450 1400x1050 286x214mm 14.1-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3445 1280x800 331x207mm 15.4-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC324C 1366x768 353x198mm 15.9-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3151 1366x768 344x194mm 15.5-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC304C 1920x1080 353x198mm 15.9-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 409x230mm 18.5-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 340x190mm 15.3-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4447 1366x768 340x190mm 15.3-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 340x190mm 15.3-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC3250 1920x1080 344x194mm 15.5-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch   | 1         | 0.53%   |
| Philips LCD Monitor PHL4650 1280x768 530x398mm 26.1-inch                 | 1         | 0.53%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 1         | 0.53%   |
| MLT LCD TV MLT9901 1366x768 409x230mm 18.5-inch                          | 1         | 0.53%   |
| LG Philips LCD Monitor LPLEF00 1280x800 304x190mm 14.1-inch              | 1         | 0.53%   |
| LG Philips LCD Monitor LPLB400 1280x800 331x207mm 15.4-inch              | 1         | 0.53%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch              | 1         | 0.53%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch              | 1         | 0.53%   |
| LG Philips LCD Monitor LPL1F01 1280x800 331x207mm 15.4-inch              | 1         | 0.53%   |
| LG Philips LCD Monitor LPL1901 1680x1050 331x207mm 15.4-inch             | 1         | 0.53%   |
| LG Philips LCD Monitor LPL0A01 1440x900 367x230mm 17.1-inch              | 1         | 0.53%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 1         | 0.53%   |
| LG Display LP116WH2-TLB1 LGD028B 1366x768 256x144mm 11.6-inch            | 1         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 74        | 40.44%  |
| 1920x1080 (FHD)    | 45        | 24.59%  |
| 1280x800 (WXGA)    | 25        | 13.66%  |
| 1600x900 (HD+)     | 12        | 6.56%   |
| 1024x600           | 7         | 3.83%   |
| 1440x900 (WXGA+)   | 4         | 2.19%   |
| 3840x2160 (4K)     | 2         | 1.09%   |
| 1680x1050 (WSXGA+) | 2         | 1.09%   |
| 1024x768 (XGA)     | 2         | 1.09%   |
| 3840x1080          | 1         | 0.55%   |
| 2560x1440 (QHD)    | 1         | 0.55%   |
| 2560x1080          | 1         | 0.55%   |
| 1920x540           | 1         | 0.55%   |
| 1920x1200 (WUXGA)  | 1         | 0.55%   |
| 1400x1050          | 1         | 0.55%   |
| 1360x768           | 1         | 0.55%   |
| 1280x768           | 1         | 0.55%   |
| 1280x1024 (SXGA)   | 1         | 0.55%   |
| Unknown            | 1         | 0.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 92        | 50.27%  |
| 14      | 23        | 12.57%  |
| 13      | 16        | 8.74%   |
| 17      | 11        | 6.01%   |
| 10      | 7         | 3.83%   |
| 12      | 5         | 2.73%   |
| 11      | 5         | 2.73%   |
| 23      | 4         | 2.19%   |
| 18      | 4         | 2.19%   |
| Unknown | 4         | 2.19%   |
| 72      | 2         | 1.09%   |
| 27      | 2         | 1.09%   |
| 21      | 2         | 1.09%   |
| 48      | 1         | 0.55%   |
| 34      | 1         | 0.55%   |
| 31      | 1         | 0.55%   |
| 24      | 1         | 0.55%   |
| 20      | 1         | 0.55%   |
| 19      | 1         | 0.55%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 122       | 66.67%  |
| 201-300     | 22        | 12.02%  |
| 351-400     | 16        | 8.74%   |
| 401-500     | 8         | 4.37%   |
| 501-600     | 6         | 3.28%   |
| Unknown     | 4         | 2.19%   |
| 1501-2000   | 2         | 1.09%   |
| 701-800     | 1         | 0.55%   |
| 601-700     | 1         | 0.55%   |
| 1001-1500   | 1         | 0.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 132       | 76.74%  |
| 16/10   | 31        | 18.02%  |
| 4/3     | 3         | 1.74%   |
| Unknown | 2         | 1.16%   |
| 5/4     | 1         | 0.58%   |
| 32/9    | 1         | 0.58%   |
| 3/2     | 1         | 0.58%   |
| 21/9    | 1         | 0.58%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 92        | 50%     |
| 81-90          | 36        | 19.57%  |
| 121-130        | 8         | 4.35%   |
| 41-50          | 7         | 3.8%    |
| 201-250        | 6         | 3.26%   |
| 61-70          | 5         | 2.72%   |
| 51-60          | 5         | 2.72%   |
| 141-150        | 4         | 2.17%   |
| Unknown        | 4         | 2.17%   |
| More than 1000 | 3         | 1.63%   |
| 151-200        | 3         | 1.63%   |
| 131-140        | 3         | 1.63%   |
| 71-80          | 2         | 1.09%   |
| 351-500        | 2         | 1.09%   |
| 301-350        | 2         | 1.09%   |
| 91-100         | 2         | 1.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 87        | 48.33%  |
| 121-160       | 43        | 23.89%  |
| 51-100        | 40        | 22.22%  |
| Unknown       | 4         | 2.22%   |
| 1-50          | 3         | 1.67%   |
| 161-240       | 2         | 1.11%   |
| More than 240 | 1         | 0.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 166       | 82.59%  |
| 2     | 19        | 9.45%   |
| 0     | 16        | 7.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 110       | 30.99%  |
| Intel                                 | 76        | 21.41%  |
| Qualcomm Atheros                      | 72        | 20.28%  |
| Broadcom                              | 32        | 9.01%   |
| Marvell Technology Group              | 9         | 2.54%   |
| Broadcom Limited                      | 9         | 2.54%   |
| Silicon Integrated Systems [SiS]      | 5         | 1.41%   |
| Samsung Electronics                   | 5         | 1.41%   |
| Ralink                                | 5         | 1.41%   |
| Nvidia                                | 5         | 1.41%   |
| Ericsson Business Mobile Networks     | 3         | 0.85%   |
| JMicron Technology                    | 2         | 0.56%   |
| Huawei Technologies                   | 2         | 0.56%   |
| AMD                                   | 2         | 0.56%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.28%   |
| Xiaomi                                | 1         | 0.28%   |
| VIA Technologies                      | 1         | 0.28%   |
| TP-Link                               | 1         | 0.28%   |
| ST-Ericsson                           | 1         | 0.28%   |
| Sierra Wireless                       | 1         | 0.28%   |
| NetGear                               | 1         | 0.28%   |
| MediaTek                              | 1         | 0.28%   |
| Manta                                 | 1         | 0.28%   |
| Linksys                               | 1         | 0.28%   |
| Lenovo                                | 1         | 0.28%   |
| Intersil                              | 1         | 0.28%   |
| Gemtek                                | 1         | 0.28%   |
| DisplayLink                           | 1         | 0.28%   |
| Dell                                  | 1         | 0.28%   |
| Cisco Aironet Wireless Communications | 1         | 0.28%   |
| Attansic Technology                   | 1         | 0.28%   |
| Askey Computer                        | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 58        | 13.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 33        | 7.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 3.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 12        | 2.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 12        | 2.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 2.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 7         | 1.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 1.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 1.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 1.65%   |
| Intel WiFi Link 5100                                                    | 6         | 1.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 1.18%   |
| Intel Wireless 7260                                                     | 5         | 1.18%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.18%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 1.18%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 4         | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.94%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 0.94%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 0.94%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.94%   |
| Intel 82573L Gigabit Ethernet Controller                                | 4         | 0.94%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 3         | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.71%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.71%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.71%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.71%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                 | 3         | 0.71%   |
| Intel Wireless 3160                                                     | 3         | 0.71%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 0.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3         | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 0.71%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express          | 3         | 0.71%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 0.71%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet               | 2         | 0.47%   |
| Silicon Integrated Systems [SiS] AC'97 Modem Controller                 | 2         | 0.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.47%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.47%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.47%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 2         | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 2         | 0.47%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 2         | 0.47%   |
| Nvidia MCP79 Ethernet                                                   | 2         | 0.47%   |
| Nvidia MCP67 Ethernet                                                   | 2         | 0.47%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 2         | 0.47%   |
| Intel Wireless 8265 / 8275                                              | 2         | 0.47%   |
| Intel Wireless 8260                                                     | 2         | 0.47%   |
| Intel PRO/100 VE Network Connection                                     | 2         | 0.47%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.47%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.47%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 0.47%   |
| Intel 82567LM Gigabit Network Connection                                | 2         | 0.47%   |
| Intel 82566MM Gigabit Network Connection                                | 2         | 0.47%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile    | 2         | 0.47%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                       | 2         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 66        | 32.04%  |
| Intel                                 | 64        | 31.07%  |
| Realtek Semiconductor                 | 38        | 18.45%  |
| Broadcom                              | 23        | 11.17%  |
| Ralink                                | 5         | 2.43%   |
| Broadcom Limited                      | 4         | 1.94%   |
| TP-Link                               | 1         | 0.49%   |
| Sierra Wireless                       | 1         | 0.49%   |
| NetGear                               | 1         | 0.49%   |
| Linksys                               | 1         | 0.49%   |
| Cisco Aironet Wireless Communications | 1         | 0.49%   |
| Askey Computer                        | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 14        | 6.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 12        | 5.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                          | 12        | 5.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 10        | 4.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 8         | 3.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 8         | 3.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 7         | 3.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 7         | 3.35%   |
| Intel WiFi Link 5100                                                           | 6         | 2.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 5         | 2.39%   |
| Intel Wireless 7260                                                            | 5         | 2.39%   |
| Intel Centrino Ultimate-N 6300                                                 | 5         | 2.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 4         | 1.91%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 4         | 1.91%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 4         | 1.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 3         | 1.44%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                    | 3         | 1.44%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 3         | 1.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 3         | 1.44%   |
| Intel Wireless 3160                                                            | 3         | 1.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                   | 3         | 1.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 3         | 1.44%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                         | 3         | 1.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 2         | 0.96%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                       | 2         | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 2         | 0.96%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                          | 2         | 0.96%   |
| Intel Wireless 8265 / 8275                                                     | 2         | 0.96%   |
| Intel Wireless 8260                                                            | 2         | 0.96%   |
| Intel Gemini Lake PCH CNVi WiFi                                                | 2         | 0.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                | 2         | 0.96%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                  | 2         | 0.96%   |
| Broadcom BCM43228 802.11a/b/g/n                                                | 2         | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 2         | 0.96%   |
| Broadcom BCM4311 802.11b/g WLAN                                                | 2         | 0.96%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                    | 1         | 0.48%   |
| Sierra Wireless MC8305 Modem                                                   | 1         | 0.48%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 1         | 0.48%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                       | 1         | 0.48%   |
| Realtek RTL8723DE Wireless Network Adapter                                     | 1         | 0.48%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                | 1         | 0.48%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                    | 1         | 0.48%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                          | 1         | 0.48%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                        | 1         | 0.48%   |
| Realtek RTL8187SE Wireless LAN Controller                                      | 1         | 0.48%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                      | 1         | 0.48%   |
| Realtek 802.11ac NIC                                                           | 1         | 0.48%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]               | 1         | 0.48%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.48%   |
| Qualcomm Atheros QCA6164 802.11ac Wireless Network Adapter                     | 1         | 0.48%   |
| Qualcomm Atheros AR922X Wireless Network Adapter                               | 1         | 0.48%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg] | 1         | 0.48%   |
| Qualcomm Atheros AR2427 802.11bg Wireless Network Adapter (PCI-Express)        | 1         | 0.48%   |
| NetGear WNA1100 Wireless-N 150 [Atheros AR9271]                                | 1         | 0.48%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]                              | 1         | 0.48%   |
| Intel Wireless-AC 9260                                                         | 1         | 0.48%   |
| Intel Wireless 7265                                                            | 1         | 0.48%   |
| Intel Wireless 3165                                                            | 1         | 0.48%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 98        | 49.25%  |
| Intel                            | 32        | 16.08%  |
| Qualcomm Atheros                 | 16        | 8.04%   |
| Broadcom                         | 13        | 6.53%   |
| Marvell Technology Group         | 9         | 4.52%   |
| Silicon Integrated Systems [SiS] | 5         | 2.51%   |
| Samsung Electronics              | 5         | 2.51%   |
| Nvidia                           | 5         | 2.51%   |
| Broadcom Limited                 | 5         | 2.51%   |
| JMicron Technology               | 2         | 1.01%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.5%    |
| Xiaomi                           | 1         | 0.5%    |
| VIA Technologies                 | 1         | 0.5%    |
| MediaTek                         | 1         | 0.5%    |
| Lenovo                           | 1         | 0.5%    |
| Huawei Technologies              | 1         | 0.5%    |
| Gemtek                           | 1         | 0.5%    |
| DisplayLink                      | 1         | 0.5%    |
| Attansic Technology              | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 58        | 29.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 33        | 16.58%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 7         | 3.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 3.52%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 2.51%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 4         | 2.01%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 2.01%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 4         | 2.01%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 3         | 1.51%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 3         | 1.51%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.51%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 3         | 1.51%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 2         | 1.01%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 1.01%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2         | 1.01%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 1.01%   |
| Nvidia MCP67 Ethernet                                                          | 2         | 1.01%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 1.01%   |
| Intel PRO/100 VE Network Connection                                            | 2         | 1.01%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.01%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 1.01%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile           | 2         | 1.01%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 1.01%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 2         | 1.01%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 2         | 1.01%   |
| ZTE WCDMA MSM Spreadtrum Phone                                                 | 1         | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.5%    |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.5%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.5%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 1         | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.5%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.5%    |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.5%    |
| MediaTek Le                                                                    | 1         | 0.5%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.5%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.5%    |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.5%    |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.5%    |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.5%    |
| Lenovo ThinkPad Lan                                                            | 1         | 0.5%    |
| Intel WiMAX Connection 2400m                                                   | 1         | 0.5%    |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.5%    |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                                          | 1         | 0.5%    |
| Intel 82540EP Gigabit Ethernet Controller (Mobile)                             | 1         | 0.5%    |
| Huawei E353/E3131                                                              | 1         | 0.5%    |
| Gemtek WLTUBA-107 [Yota 4G LTE]                                                | 1         | 0.5%    |
| DisplayLink Dell D3100 USB3.0 Dock                                             | 1         | 0.5%    |
| Broadcom NetXtreme BCM5788 Gigabit Ethernet                                    | 1         | 0.5%    |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 1         | 0.5%    |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express                       | 1         | 0.5%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 1         | 0.5%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 0.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 196       | 49%     |
| Ethernet | 188       | 47%     |
| Modem    | 13        | 3.25%   |
| Unknown  | 3         | 0.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 180       | 50.85%  |
| Ethernet | 173       | 48.87%  |
| Modem    | 1         | 0.28%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 178       | 89.45%  |
| 1     | 17        | 8.54%   |
| 3     | 2         | 1.01%   |
| 4     | 1         | 0.5%    |
| 0     | 1         | 0.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 175       | 87.06%  |
| Yes  | 26        | 12.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 23        | 20.72%  |
| Realtek Semiconductor           | 14        | 12.61%  |
| Qualcomm Atheros Communications | 14        | 12.61%  |
| Broadcom                        | 13        | 11.71%  |
| Hewlett-Packard                 | 8         | 7.21%   |
| Foxconn / Hon Hai               | 7         | 6.31%   |
| Lite-On Technology              | 6         | 5.41%   |
| IMC Networks                    | 5         | 4.5%    |
| Dell                            | 5         | 4.5%    |
| Toshiba                         | 2         | 1.8%    |
| Cambridge Silicon Radio         | 2         | 1.8%    |
| ASUSTek Computer                | 2         | 1.8%    |
| Apple                           | 2         | 1.8%    |
| Taiyo Yuden                     | 1         | 0.9%    |
| Realtek                         | 1         | 0.9%    |
| Ralink Technology               | 1         | 0.9%    |
| Ralink                          | 1         | 0.9%    |
| Qcom                            | 1         | 0.9%    |
| Foxconn International           | 1         | 0.9%    |
| Askey Computer                  | 1         | 0.9%    |
| Alps Electric                   | 1         | 0.9%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 10        | 9.01%   |
| Intel Bluetooth Device                                                              | 8         | 7.21%   |
| Realtek Bluetooth Radio                                                             | 7         | 6.31%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 6.31%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 5.41%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 5         | 4.5%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 3.6%    |
| Dell DW375 Bluetooth Module                                                         | 4         | 3.6%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 2.7%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 2.7%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 1.8%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.8%    |
| Lite-On Atheros Bluetooth                                                           | 2         | 1.8%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.8%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.8%    |
| IMC Networks Bluetooth Device                                                       | 2         | 1.8%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 1.8%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.8%    |
| Broadcom Bluetooth                                                                  | 2         | 1.8%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 2         | 1.8%    |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.8%    |
| Apple Bluetooth Host Controller                                                     | 2         | 1.8%    |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.9%    |
| Toshiba Bluetooth Device                                                            | 1         | 0.9%    |
| Taiyo Yuden Bluetooth Device(BC04-External)                                         | 1         | 0.9%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.9%    |
| Realtek Bluetooth Radio                                                             | 1         | 0.9%    |
| Ralink CSR BS8510                                                                   | 1         | 0.9%    |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.9%    |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.9%    |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.9%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.9%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.9%    |
| Intel AX200 Bluetooth                                                               | 1         | 0.9%    |
| IMC Networks Broadcom Bluetooth 2.1                                                 | 1         | 0.9%    |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.9%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.9%    |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.9%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.9%    |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.9%    |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.9%    |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.9%    |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.9%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.9%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.9%    |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.9%    |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 1         | 0.9%    |
| Askey Bluetooth Device                                                              | 1         | 0.9%    |
| Alps Electric BCM2046 Bluetooth Device                                              | 1         | 0.9%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 155       | 68.58%  |
| AMD                              | 38        | 16.81%  |
| Nvidia                           | 22        | 9.73%   |
| Silicon Integrated Systems [SiS] | 6         | 2.65%   |
| C-Media Electronics              | 2         | 0.88%   |
| VIA Technologies                 | 1         | 0.44%   |
| Tenx Technology                  | 1         | 0.44%   |
| Dell                             | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 24        | 9.02%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 19        | 7.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 6.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 4.89%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 4.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 4.51%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 4.14%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 3.01%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 3.01%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 3.01%   |
| AMD High Definition Audio Controller                                                              | 7         | 2.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 2.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 2.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.26%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 6         | 2.26%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 1.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.88%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 1.5%    |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 4         | 1.5%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 4         | 1.5%    |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 1.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.13%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.13%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 1.13%   |
| AMD FCH Azalia Controller                                                                         | 3         | 1.13%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 2         | 0.75%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.75%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 0.75%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                                              | 2         | 0.75%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.75%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.75%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.75%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.75%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 2         | 0.75%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 1         | 0.38%   |
| Tenx Technology USB AUDIO                                                                         | 1         | 0.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.38%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.38%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.38%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.38%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.38%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.38%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.38%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.38%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.38%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.38%   |
| Intel Moorestown Audio Ctrl                                                                       | 1         | 0.38%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.38%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 0.38%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 0.38%   |
| Dell AC511 Sound Bar                                                                              | 1         | 0.38%   |
| C-Media Electronics KIMU PRO                                                                      | 1         | 0.38%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 1         | 0.38%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 8         | 25.81%  |
| Samsung Electronics | 6         | 19.35%  |
| Unknown             | 4         | 12.9%   |
| Kingston            | 4         | 12.9%   |
| Ramaxel Technology  | 2         | 6.45%   |
| Nanya Technology    | 2         | 6.45%   |
| Transcend           | 1         | 3.23%   |
| Smart               | 1         | 3.23%   |
| Micron Technology   | 1         | 3.23%   |
| G.Skill             | 1         | 3.23%   |
| A-DATA Technology   | 1         | 3.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown RAM Module SODIMM DDR                                | 1         | 3.13%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s               | 1         | 3.13%   |
| Unknown RAM Module 2GB SODIMM DDR3                           | 1         | 3.13%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                | 1         | 3.13%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 975MT/s            | 1         | 3.13%   |
| Smart RAM SH564128FJ8NWRNSQG 4096MB SODIMM DDR3 1600MT/s     | 1         | 3.13%   |
| SK Hynix RAM Module 512MB SODIMM DDR 533MT/s                 | 1         | 3.13%   |
| SK Hynix RAM HYMP125S64CP8-Y5 2048MB SODIMM DDR2 667MT/s     | 1         | 3.13%   |
| SK Hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s     | 1         | 3.13%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s    | 1         | 3.13%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s    | 1         | 3.13%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 3.13%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 3.13%   |
| SK Hynix RAM HMP125S6EFR8C-S6 2048MB SODIMM DDR2 800MT/s     | 1         | 3.13%   |
| SK Hynix RAM HMP112S6EFR6C-S6 1024MB SODIMM DDR2 800MT/s     | 1         | 3.13%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 2667MT/s     | 1         | 3.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 1         | 3.13%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 1         | 3.13%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s     | 1         | 3.13%   |
| Samsung RAM M471A1K43CB1-CRC 8192MB SODIMM DDR4 2667MT/s     | 1         | 3.13%   |
| Samsung RAM M4 70T5663QZ3-CF7 2048MB SODIMM DDR2 2048MT/s    | 1         | 3.13%   |
| Ramaxel RAM RMSA3260MF68H9F-2666 4096MB SODIMM DDR4 2400MT/s | 1         | 3.13%   |
| Ramaxel RAM RMN1150EC48D7W-800 1024MB SODIMM DDR2 800MT/s    | 1         | 3.13%   |
| Nanya RAM NT2GC64B88G0NS-CG 2GB SODIMM DDR3 1600MT/s         | 1         | 3.13%   |
| Nanya RAM Module 1024MB SODIMM DDR 533MT/s                   | 1         | 3.13%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 1         | 3.13%   |
| Kingston RAM 9905711-016.A00G 4096MB SODIMM DDR4 2667MT/s    | 1         | 3.13%   |
| Kingston RAM 9905700-024.A00G 8GB SODIMM DDR4 2400MT/s       | 1         | 3.13%   |
| Kingston RAM 9905624-059.A00G 8192MB SODIMM DDR4 2667MT/s    | 1         | 3.13%   |
| Kingston RAM 9905428-155.A00LF 8GB SODIMM DDR3 1600MT/s      | 1         | 3.13%   |
| G.Skill RAM F3-10666CL9-8GBSQ 8192MB SODIMM DDR3 1333MT/s    | 1         | 3.13%   |
| A-DATA RAM AO1P26KC8T1-BXPS 8GB SODIMM DDR4 2667MT/s         | 1         | 3.13%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind  | Notebooks | Percent |
|-------|-----------|---------|
| DDR3  | 11        | 39.29%  |
| DDR4  | 8         | 28.57%  |
| DDR2  | 5         | 17.86%  |
| SDRAM | 2         | 7.14%   |
| DDR   | 2         | 7.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| SODIMM | 26        | 100%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 12        | 41.38%  |
| 2048    | 6         | 20.69%  |
| 4096    | 5         | 17.24%  |
| 1024    | 4         | 13.79%  |
| 512     | 1         | 3.45%   |
| Unknown | 1         | 3.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 8         | 26.67%  |
| 1600    | 7         | 23.33%  |
| 2400    | 2         | 6.67%   |
| 1333    | 2         | 6.67%   |
| 975     | 2         | 6.67%   |
| 800     | 2         | 6.67%   |
| 533     | 2         | 6.67%   |
| Unknown | 2         | 6.67%   |
| 3266    | 1         | 3.33%   |
| 2048    | 1         | 3.33%   |
| 667     | 1         | 3.33%   |

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
| Chicony Electronics                    | 34        | 22.82%  |
| IMC Networks                           | 14        | 9.4%    |
| Suyin                                  | 12        | 8.05%   |
| Sunplus Innovation Technology          | 12        | 8.05%   |
| Quanta                                 | 11        | 7.38%   |
| Acer                                   | 10        | 6.71%   |
| Realtek Semiconductor                  | 9         | 6.04%   |
| Microdia                               | 8         | 5.37%   |
| Silicon Motion                         | 6         | 4.03%   |
| Ricoh                                  | 6         | 4.03%   |
| Apple                                  | 5         | 3.36%   |
| Syntek                                 | 4         | 2.68%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.68%   |
| Sunplus Technology                     | 2         | 1.34%   |
| Importek                               | 2         | 1.34%   |
| ALi                                    | 2         | 1.34%   |
| Z-Star Microelectronics                | 1         | 0.67%   |
| Samsung Electronics                    | 1         | 0.67%   |
| OmniVision Technologies                | 1         | 0.67%   |
| Lite-On Technology                     | 1         | 0.67%   |
| LG Electronics                         | 1         | 0.67%   |
| Lenovo                                 | 1         | 0.67%   |
| Generalplus Technology                 | 1         | 0.67%   |
| Alcor Micro                            | 1         | 0.67%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Quanta HP Webcam                                    | 5         | 3.33%   |
| Chicony Integrated Camera                           | 5         | 3.33%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 3         | 2%      |
| Realtek USB2.0 VGA UVC WebCam                       | 3         | 2%      |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 2%      |
| Apple iPhone 5/5C/5S/6/SE                           | 3         | 2%      |
| Acer HD Webcam                                      | 3         | 2%      |
| Syntek Sonix USB 2.0 Camera                         | 2         | 1.33%   |
| Suyin HP Truevision HD                              | 2         | 1.33%   |
| Suyin 1.3M HD WebCam                                | 2         | 1.33%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 2         | 1.33%   |
| Sunplus Laptop Integrated WebCam HD                 | 2         | 1.33%   |
| Silicon Motion WebCam SC-0311139N                   | 2         | 1.33%   |
| Silicon Motion HP Webcam-101                        | 2         | 1.33%   |
| Ricoh Sony Visual Communication Camera              | 2         | 1.33%   |
| Realtek Integrated_Webcam_HD                        | 2         | 1.33%   |
| Quanta VGA WebCam                                   | 2         | 1.33%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.33%   |
| Microdia Sonix USB 2.0 Camera                       | 2         | 1.33%   |
| Microdia Integrated Webcam HD                       | 2         | 1.33%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 1.33%   |
| IMC Networks Integrated Camera                      | 2         | 1.33%   |
| IMC Networks EasyCamera                             | 2         | 1.33%   |
| Chicony USB 2.0 Camera                              | 2         | 1.33%   |
| Chicony TOSHIBA Web Camera - HD                     | 2         | 1.33%   |
| Chicony HP Truevision HD camera                     | 2         | 1.33%   |
| Chicony HD WebCam                                   | 2         | 1.33%   |
| Chicony 2.0M UVC Webcam / CNF7129                   | 2         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 1.33%   |
| Apple Built-in iSight                               | 2         | 1.33%   |
| Acer Lenovo EasyCamera                              | 2         | 1.33%   |
| Z-Star Namuga 1.3M Webcam                           | 1         | 0.67%   |
| Syntek Integrated Webcam                            | 1         | 0.67%   |
| Syntek HP Webcam                                    | 1         | 0.67%   |
| Suyin HP Webcam                                     | 1         | 0.67%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 0.67%   |
| Suyin HD WebCam                                     | 1         | 0.67%   |
| Suyin Acer HD Crystal Eye webcam                    | 1         | 0.67%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.67%   |
| Sunplus 1.3M WebCam                                 | 1         | 0.67%   |
| Sunplus 1.3M HD WebCam                              | 1         | 0.67%   |
| Sunplus Lenovo EasyCamera                           | 1         | 0.67%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.67%   |
| Sunplus Integrated Webcam                           | 1         | 0.67%   |
| Sunplus HP TrueVision HD Camera                     | 1         | 0.67%   |
| Sunplus HD WebCam                                   | 1         | 0.67%   |
| Sunplus Dell HD Webcam                              | 1         | 0.67%   |
| Sunplus Dell E5570 integrated webcam                | 1         | 0.67%   |
| Sunplus Asus Webcam                                 | 1         | 0.67%   |
| Silicon Motion WebCam SCB-1100N                     | 1         | 0.67%   |
| Silicon Motion WebCam SCB-0385N                     | 1         | 0.67%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 0.67%   |
| Ricoh Visual Communication Camera VGP-VCC9 [R5U870] | 1         | 0.67%   |
| Ricoh Visual Communication Camera VGP-VCC4 [R5U870] | 1         | 0.67%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.67%   |
| Ricoh HD Webcam                                     | 1         | 0.67%   |
| Realtek USB Camera                                  | 1         | 0.67%   |
| Realtek Lenovo EasyCamera                           | 1         | 0.67%   |
| Realtek Laptop_Integrated_Webcam_HD                 | 1         | 0.67%   |
| Realtek HP Truevision HD integrated webcam          | 1         | 0.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 9         | 39.13%  |
| AuthenTec             | 8         | 34.78%  |
| STMicroelectronics    | 3         | 13.04%  |
| Upek                  | 1         | 4.35%   |
| Synaptics             | 1         | 4.35%   |
| LighTuning Technology | 1         | 4.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| STMicroelectronics Fingerprint Reader                  | 3         | 13.04%  |
| Validity Sensors VFS451 Fingerprint Reader             | 2         | 8.7%    |
| Validity Sensors VFS301 Fingerprint Reader             | 2         | 8.7%    |
| AuthenTec Fingerprint Sensor                           | 2         | 8.7%    |
| AuthenTec AES2810                                      | 2         | 8.7%    |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 8.7%    |
| AuthenTec AES1600                                      | 2         | 8.7%    |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4.35%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 4.35%   |
| Validity Sensors VFS491                                | 1         | 4.35%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 4.35%   |
| Validity Sensors Fingerprint scanner                   | 1         | 4.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4.35%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 4.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 4.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 8         | 66.67%  |
| O2 Micro              | 2         | 16.67%  |
| Gemalto (was Gemplus) | 1         | 8.33%   |
| Alcor Micro           | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 25%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 16.67%  |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 127       | 63.18%  |
| 1     | 53        | 26.37%  |
| 2     | 14        | 6.97%   |
| 3     | 6         | 2.99%   |
| 6     | 1         | 0.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 30        | 31.25%  |
| Fingerprint reader       | 23        | 23.96%  |
| Net/wireless             | 14        | 14.58%  |
| Chipcard                 | 11        | 11.46%  |
| Storage                  | 5         | 5.21%   |
| Multimedia controller    | 5         | 5.21%   |
| Communication controller | 3         | 3.13%   |
| Flash memory             | 2         | 2.08%   |
| Network                  | 1         | 1.04%   |
| Camera                   | 1         | 1.04%   |
| Bluetooth                | 1         | 1.04%   |

