Linux in Australia - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Australia.

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

Total: 2127

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X260 20F5002NAU    | [7fcb72c132](https://linux-hardware.org/?probe=7fcb72c132) | May 01, 2023 |
| ASUSTek       | X501A1                      | [66b02cc148](https://linux-hardware.org/?probe=66b02cc148) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7a86bdd993](https://linux-hardware.org/?probe=7a86bdd993) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | [6206b317f2](https://linux-hardware.org/?probe=6206b317f2) | Apr 30, 2023 |
| Acer          | ConceptD CN315-71P          | [3cc902ff5c](https://linux-hardware.org/?probe=3cc902ff5c) | Apr 28, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [73141c5006](https://linux-hardware.org/?probe=73141c5006) | Apr 27, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [0cb164ac2f](https://linux-hardware.org/?probe=0cb164ac2f) | Apr 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3f44947226](https://linux-hardware.org/?probe=3f44947226) | Apr 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [198fa6162e](https://linux-hardware.org/?probe=198fa6162e) | Apr 27, 2023 |
| ASUSTek       | X550CA                      | [a63293fe36](https://linux-hardware.org/?probe=a63293fe36) | Apr 26, 2023 |
| Dell          | Inspiron 5548               | [42908a7ab7](https://linux-hardware.org/?probe=42908a7ab7) | Apr 25, 2023 |
| Dell          | System XPS L702X            | [d1aa167e90](https://linux-hardware.org/?probe=d1aa167e90) | Apr 25, 2023 |
| Acer          | E5-551G-871W                | [2730a30d89](https://linux-hardware.org/?probe=2730a30d89) | Apr 25, 2023 |
| MSI           | GE72VR 6RF                  | [89cb17ee72](https://linux-hardware.org/?probe=89cb17ee72) | Apr 25, 2023 |
| Dell          | Precision 5520              | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| Valve         | Jupiter                     | [b5be7aa6ff](https://linux-hardware.org/?probe=b5be7aa6ff) | Apr 21, 2023 |
| Acer          | Predator G9-793             | [664d6de816](https://linux-hardware.org/?probe=664d6de816) | Apr 20, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [8daf9af9b5](https://linux-hardware.org/?probe=8daf9af9b5) | Apr 20, 2023 |
| Acer          | Aspire 5733Z                | [de205c8c62](https://linux-hardware.org/?probe=de205c8c62) | Apr 19, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [7da02a75b5](https://linux-hardware.org/?probe=7da02a75b5) | Apr 18, 2023 |
| Toshiba       | Satellite E45-B             | [ec0bb6bfc6](https://linux-hardware.org/?probe=ec0bb6bfc6) | Apr 17, 2023 |
| Dell          | Inspiron 13-5378            | [bcb18ae818](https://linux-hardware.org/?probe=bcb18ae818) | Apr 17, 2023 |
| HP            | Pavilion dv6                | [fc41269cf8](https://linux-hardware.org/?probe=fc41269cf8) | Apr 16, 2023 |
| Dell          | Latitude 5420               | [03247dc98c](https://linux-hardware.org/?probe=03247dc98c) | Apr 16, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [71e03c5459](https://linux-hardware.org/?probe=71e03c5459) | Apr 15, 2023 |
| Apple         | MacBookPro7,1               | [3470b35550](https://linux-hardware.org/?probe=3470b35550) | Apr 15, 2023 |
| Toshiba       | QOSMIO F750                 | [590801670a](https://linux-hardware.org/?probe=590801670a) | Apr 15, 2023 |
| Toshiba       | Satellite L850              | [dc9e77bd65](https://linux-hardware.org/?probe=dc9e77bd65) | Apr 14, 2023 |
| Dell          | Latitude E6540              | [61ab891b01](https://linux-hardware.org/?probe=61ab891b01) | Apr 13, 2023 |
| Dell          | Vostro 7590                 | [f759d8ab72](https://linux-hardware.org/?probe=f759d8ab72) | Apr 13, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [8e641b5fd5](https://linux-hardware.org/?probe=8e641b5fd5) | Apr 13, 2023 |
| Acer          | Aspire 5720Z                | [1ac7eb0d0c](https://linux-hardware.org/?probe=1ac7eb0d0c) | Apr 13, 2023 |
| Acer          | TM6495T                     | [435ae018a2](https://linux-hardware.org/?probe=435ae018a2) | Apr 11, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | [a8090f51bc](https://linux-hardware.org/?probe=a8090f51bc) | Apr 09, 2023 |
| Dell          | Inspiron 1720               | [a2e3b07f6b](https://linux-hardware.org/?probe=a2e3b07f6b) | Apr 09, 2023 |
| Dell          | Latitude E5470              | [3e49e9c541](https://linux-hardware.org/?probe=3e49e9c541) | Apr 08, 2023 |
| Apple         | MacBookAir7,2               | [5aad90904c](https://linux-hardware.org/?probe=5aad90904c) | Apr 07, 2023 |
| Acer          | TravelMate 8572T            | [04f50662d8](https://linux-hardware.org/?probe=04f50662d8) | Apr 07, 2023 |
| Toshiba       | Satellite P70-A             | [6ffb7a79ef](https://linux-hardware.org/?probe=6ffb7a79ef) | Apr 06, 2023 |
| HP            | Pavilion dv6                | [be695e2cd4](https://linux-hardware.org/?probe=be695e2cd4) | Apr 06, 2023 |
| HP            | ZBook 17 G2                 | [258f32d502](https://linux-hardware.org/?probe=258f32d502) | Apr 05, 2023 |
| HUAWEI        | MACHD-WXX9                  | [7e5be74f0b](https://linux-hardware.org/?probe=7e5be74f0b) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | [473a8c1d7b](https://linux-hardware.org/?probe=473a8c1d7b) | Apr 05, 2023 |
| HP            | Notebook                    | [50c03e608d](https://linux-hardware.org/?probe=50c03e608d) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | [56079f49e3](https://linux-hardware.org/?probe=56079f49e3) | Apr 04, 2023 |
| Apple         | MacBookPro8,1               | [4ef5210167](https://linux-hardware.org/?probe=4ef5210167) | Apr 04, 2023 |
| HP            | EliteBook Folio 1040 G3     | [9e25dfd6bb](https://linux-hardware.org/?probe=9e25dfd6bb) | Apr 02, 2023 |
| HP            | ProBook 650 G2              | [89622c73d1](https://linux-hardware.org/?probe=89622c73d1) | Apr 02, 2023 |
| Dell          | XPS 15 9570                 | [7beef34820](https://linux-hardware.org/?probe=7beef34820) | Apr 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [2a881cc01e](https://linux-hardware.org/?probe=2a881cc01e) | Apr 01, 2023 |
| HP            | ProBook 450 G5              | [89dfecad7e](https://linux-hardware.org/?probe=89dfecad7e) | Mar 30, 2023 |
| Dell          | XPS 15 9570                 | [8d0c93e1a8](https://linux-hardware.org/?probe=8d0c93e1a8) | Mar 30, 2023 |
| Dell          | Precision 5550              | [c7244f1e31](https://linux-hardware.org/?probe=c7244f1e31) | Mar 30, 2023 |
| Dell          | G3 3590                     | [f61ce9bb82](https://linux-hardware.org/?probe=f61ce9bb82) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | [6f4e3ec28b](https://linux-hardware.org/?probe=6f4e3ec28b) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | [9dd1b67b2f](https://linux-hardware.org/?probe=9dd1b67b2f) | Mar 28, 2023 |
| HUAWEI        | NBD-WXX9                    | [8060aec150](https://linux-hardware.org/?probe=8060aec150) | Mar 25, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [9edd5002f0](https://linux-hardware.org/?probe=9edd5002f0) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | [1672158957](https://linux-hardware.org/?probe=1672158957) | Mar 24, 2023 |
| HP            | ProBook 470 G5              | [383b333f72](https://linux-hardware.org/?probe=383b333f72) | Mar 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [fc1c184c05](https://linux-hardware.org/?probe=fc1c184c05) | Mar 23, 2023 |
| Acer          | ConceptD CN315-71P          | [14b71e7a26](https://linux-hardware.org/?probe=14b71e7a26) | Mar 22, 2023 |
| HP            | EliteBook 8470p             | [61025e6e8b](https://linux-hardware.org/?probe=61025e6e8b) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [80d1a2d67d](https://linux-hardware.org/?probe=80d1a2d67d) | Mar 22, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [eb718edb23](https://linux-hardware.org/?probe=eb718edb23) | Mar 22, 2023 |
| Dell          | Latitude E6520              | [857fdb4095](https://linux-hardware.org/?probe=857fdb4095) | Mar 21, 2023 |
| Dell          | Inspiron 5559               | [6f98b39459](https://linux-hardware.org/?probe=6f98b39459) | Mar 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [786fded1ce](https://linux-hardware.org/?probe=786fded1ce) | Mar 17, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [49bb337156](https://linux-hardware.org/?probe=49bb337156) | Mar 17, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [d762fe2bf3](https://linux-hardware.org/?probe=d762fe2bf3) | Mar 17, 2023 |
| Valve         | Jupiter                     | [8f51ab644e](https://linux-hardware.org/?probe=8f51ab644e) | Mar 17, 2023 |
| Dell          | G3 3590                     | [9ef42643d8](https://linux-hardware.org/?probe=9ef42643d8) | Mar 16, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [ca6ab3c197](https://linux-hardware.org/?probe=ca6ab3c197) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [684375b9a0](https://linux-hardware.org/?probe=684375b9a0) | Mar 16, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [787dfaa7d4](https://linux-hardware.org/?probe=787dfaa7d4) | Mar 15, 2023 |
| Acer          | Swift SFX14-41G             | [59478f318e](https://linux-hardware.org/?probe=59478f318e) | Mar 14, 2023 |
| Dell          | XPS 13 9360                 | [954055245e](https://linux-hardware.org/?probe=954055245e) | Mar 14, 2023 |
| Dell          | Inspiron M5010              | [0a5d0c9169](https://linux-hardware.org/?probe=0a5d0c9169) | Mar 14, 2023 |
| Acer          | Aspire E5-511               | [5343f73c67](https://linux-hardware.org/?probe=5343f73c67) | Mar 13, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| Lenovo        | ThinkPad E590 20NBA000AU    | [47bfd44610](https://linux-hardware.org/?probe=47bfd44610) | Mar 12, 2023 |
| Maibenben     | P748                        | [a44d1bb8e4](https://linux-hardware.org/?probe=a44d1bb8e4) | Mar 11, 2023 |
| Dell          | XPS 15 9570                 | [9d14bee09f](https://linux-hardware.org/?probe=9d14bee09f) | Mar 10, 2023 |
| HP            | Laptop 15-db0xxx            | [ded87de736](https://linux-hardware.org/?probe=ded87de736) | Mar 09, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [54ad36532c](https://linux-hardware.org/?probe=54ad36532c) | Mar 07, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [61e3840465](https://linux-hardware.org/?probe=61e3840465) | Mar 07, 2023 |
| HP            | Compaq Presario C700        | [fe1c136403](https://linux-hardware.org/?probe=fe1c136403) | Mar 06, 2023 |
| HP            | Compaq Presario C700        | [0b29805ec8](https://linux-hardware.org/?probe=0b29805ec8) | Mar 06, 2023 |
| HP            | ENVY 17                     | [ce2278a2e4](https://linux-hardware.org/?probe=ce2278a2e4) | Mar 05, 2023 |
| Google        | Ultima                      | [5e42f67839](https://linux-hardware.org/?probe=5e42f67839) | Mar 04, 2023 |
| Valve         | Jupiter                     | [65a9e7ef52](https://linux-hardware.org/?probe=65a9e7ef52) | Mar 04, 2023 |
| HP            | Pavilion Notebook           | [906cb4b50a](https://linux-hardware.org/?probe=906cb4b50a) | Mar 03, 2023 |
| Lenovo        | V14-ADA 82C6                | [f043beec18](https://linux-hardware.org/?probe=f043beec18) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | [2173dea5df](https://linux-hardware.org/?probe=2173dea5df) | Mar 02, 2023 |
| Toshiba       | TECRA Z50-C                 | [c30ead38bd](https://linux-hardware.org/?probe=c30ead38bd) | Mar 02, 2023 |
| Apple         | MacBookPro14,3              | [6f952b4c9b](https://linux-hardware.org/?probe=6f952b4c9b) | Mar 01, 2023 |
| Intel Clie... | LAPRC510                    | [925c24b3db](https://linux-hardware.org/?probe=925c24b3db) | Feb 28, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [021853dafb](https://linux-hardware.org/?probe=021853dafb) | Feb 28, 2023 |
| Intel Clie... | LAPRC510                    | [6d9a8edb0c](https://linux-hardware.org/?probe=6d9a8edb0c) | Feb 28, 2023 |
| Apple         | MacBookPro10,1              | [816a4eb27e](https://linux-hardware.org/?probe=816a4eb27e) | Feb 26, 2023 |
| HP            | Notebook                    | [4a72575c17](https://linux-hardware.org/?probe=4a72575c17) | Feb 25, 2023 |
| Toshiba       | Satellite C850              | [99d4efbb52](https://linux-hardware.org/?probe=99d4efbb52) | Feb 25, 2023 |
| Apple         | MacBookAir7,2               | [72e11db1c0](https://linux-hardware.org/?probe=72e11db1c0) | Feb 24, 2023 |
| MSI           | Vector GP66 12UEO           | [9b6bf9479e](https://linux-hardware.org/?probe=9b6bf9479e) | Feb 24, 2023 |
| HUAWEI        | NBD-WXX9                    | [ea2663126f](https://linux-hardware.org/?probe=ea2663126f) | Feb 24, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [fa9427d71f](https://linux-hardware.org/?probe=fa9427d71f) | Feb 22, 2023 |
| Lenovo        | ThinkPad X131e 3367AH5      | [3c1cec4c1c](https://linux-hardware.org/?probe=3c1cec4c1c) | Feb 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8110c575e9](https://linux-hardware.org/?probe=8110c575e9) | Feb 22, 2023 |
| Acer          | TravelMate 8572T            | [20d7321f8f](https://linux-hardware.org/?probe=20d7321f8f) | Feb 21, 2023 |
| Dell          | Latitude 5430               | [69fd82c453](https://linux-hardware.org/?probe=69fd82c453) | Feb 21, 2023 |
| Dell          | Latitude E6430              | [42750c43b5](https://linux-hardware.org/?probe=42750c43b5) | Feb 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [d4663db4e0](https://linux-hardware.org/?probe=d4663db4e0) | Feb 19, 2023 |
| HP            | 250 G5 Notebook PC          | [ca676dc566](https://linux-hardware.org/?probe=ca676dc566) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [9b0ecbd3c7](https://linux-hardware.org/?probe=9b0ecbd3c7) | Feb 19, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [cc44156b99](https://linux-hardware.org/?probe=cc44156b99) | Feb 17, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [bc234d0b32](https://linux-hardware.org/?probe=bc234d0b32) | Feb 17, 2023 |
| Toshiba       | Satellite P750              | [6f5f99b514](https://linux-hardware.org/?probe=6f5f99b514) | Feb 16, 2023 |
| HUAWEI        | NBD-WXX9                    | [8f5697ea3a](https://linux-hardware.org/?probe=8f5697ea3a) | Feb 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [1a20fdd090](https://linux-hardware.org/?probe=1a20fdd090) | Feb 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [3384ced1ca](https://linux-hardware.org/?probe=3384ced1ca) | Feb 14, 2023 |
| MSI           | Vector GP66 12UEO           | [040bddeff8](https://linux-hardware.org/?probe=040bddeff8) | Feb 14, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| ASUSTek       | K45VS                       | [faf4fc0251](https://linux-hardware.org/?probe=faf4fc0251) | Feb 12, 2023 |
| HP            | 250 G5 Notebook PC          | [72b0ba099a](https://linux-hardware.org/?probe=72b0ba099a) | Feb 11, 2023 |
| Acer          | Aspire One 753              | [b3ef912b35](https://linux-hardware.org/?probe=b3ef912b35) | Feb 10, 2023 |
| Dell          | G15 5520                    | [121b06f3cc](https://linux-hardware.org/?probe=121b06f3cc) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [b79b2f3f75](https://linux-hardware.org/?probe=b79b2f3f75) | Feb 09, 2023 |
| Dell          | G15 5520                    | [7f4d36cea1](https://linux-hardware.org/?probe=7f4d36cea1) | Feb 08, 2023 |
| Alienware     | m15 R7                      | [254ab40fcf](https://linux-hardware.org/?probe=254ab40fcf) | Feb 07, 2023 |
| HP            | Laptop 15s-eq2xxx           | [4a647dd6b9](https://linux-hardware.org/?probe=4a647dd6b9) | Feb 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8b26ec07a6](https://linux-hardware.org/?probe=8b26ec07a6) | Feb 07, 2023 |
| Acer          | Aspire E3-111               | [a7c14e51ff](https://linux-hardware.org/?probe=a7c14e51ff) | Feb 06, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a0fc4f78ea](https://linux-hardware.org/?probe=a0fc4f78ea) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [5a7ae4b151](https://linux-hardware.org/?probe=5a7ae4b151) | Feb 05, 2023 |
| HUAWEI        | NBD-WXX9                    | [0eb4367fb4](https://linux-hardware.org/?probe=0eb4367fb4) | Feb 04, 2023 |
| ASUSTek       | X550LC                      | [f22682c35f](https://linux-hardware.org/?probe=f22682c35f) | Feb 04, 2023 |
| Toshiba       | Satellite P500              | [78ebd7c272](https://linux-hardware.org/?probe=78ebd7c272) | Feb 04, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [13bdc2b06c](https://linux-hardware.org/?probe=13bdc2b06c) | Feb 03, 2023 |
| Toshiba       | Satellite C660              | [9cabffbc86](https://linux-hardware.org/?probe=9cabffbc86) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| Lenovo        | ThinkPad T420s 4173CTO      | [232ff7a382](https://linux-hardware.org/?probe=232ff7a382) | Feb 02, 2023 |
| HP            | 250 G5 Notebook PC          | [687b1ec2d7](https://linux-hardware.org/?probe=687b1ec2d7) | Feb 02, 2023 |
| Dell          | Latitude E6520              | [548b13cd43](https://linux-hardware.org/?probe=548b13cd43) | Feb 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [465114aa14](https://linux-hardware.org/?probe=465114aa14) | Feb 01, 2023 |
| Acer          | Predator PH315-52           | [b1c77eb9c7](https://linux-hardware.org/?probe=b1c77eb9c7) | Jan 31, 2023 |
| ASUSTek       | X550LC                      | [4c50999862](https://linux-hardware.org/?probe=4c50999862) | Jan 30, 2023 |
| ASUSTek       | X550LC                      | [41d606bbe8](https://linux-hardware.org/?probe=41d606bbe8) | Jan 30, 2023 |
| Dell          | Inspiron 5770               | [b5612c2501](https://linux-hardware.org/?probe=b5612c2501) | Jan 29, 2023 |
| Dell          | Latitude 5400               | [80651273e4](https://linux-hardware.org/?probe=80651273e4) | Jan 29, 2023 |
| Dell          | Latitude 5400               | [eb97e73f08](https://linux-hardware.org/?probe=eb97e73f08) | Jan 29, 2023 |
| Apple         | MacBook8,1                  | [02cd28549c](https://linux-hardware.org/?probe=02cd28549c) | Jan 27, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | [d2a46bd14a](https://linux-hardware.org/?probe=d2a46bd14a) | Jan 26, 2023 |
| Apple         | MacBook5,1                  | [b7759508d9](https://linux-hardware.org/?probe=b7759508d9) | Jan 26, 2023 |
| Apple         | MacBook5,1                  | [72f2c3fddc](https://linux-hardware.org/?probe=72f2c3fddc) | Jan 26, 2023 |
| Panasonic     | FZ55-2                      | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [26abf66da5](https://linux-hardware.org/?probe=26abf66da5) | Jan 25, 2023 |
| Acer          | Aspire A315-22              | [7c048a8058](https://linux-hardware.org/?probe=7c048a8058) | Jan 24, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [c2226035ce](https://linux-hardware.org/?probe=c2226035ce) | Jan 24, 2023 |
| Alienware     | 15 R4                       | [8833335118](https://linux-hardware.org/?probe=8833335118) | Jan 23, 2023 |
| Dell          | XPS 13 9350                 | [223ab1f016](https://linux-hardware.org/?probe=223ab1f016) | Jan 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS2JV01    | [932148f478](https://linux-hardware.org/?probe=932148f478) | Jan 21, 2023 |
| Dell          | XPS 9315                    | [9dfb19b7c1](https://linux-hardware.org/?probe=9dfb19b7c1) | Jan 21, 2023 |
| Dell          | Latitude 5300               | [e8c4218110](https://linux-hardware.org/?probe=e8c4218110) | Jan 21, 2023 |
| Apple         | MacBookPro11,3              | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Apple         | MacBookAir7,2               | [ead0a07135](https://linux-hardware.org/?probe=ead0a07135) | Jan 20, 2023 |
| Apple         | MacBookAir5,2               | [03e73c44b7](https://linux-hardware.org/?probe=03e73c44b7) | Jan 20, 2023 |
| Apple         | MacBookPro14,3              | [82a49878eb](https://linux-hardware.org/?probe=82a49878eb) | Jan 19, 2023 |
| Dell          | XPS 15 7590                 | [9a7659a260](https://linux-hardware.org/?probe=9a7659a260) | Jan 18, 2023 |
| Dell          | Precision 3561              | [9528d74be6](https://linux-hardware.org/?probe=9528d74be6) | Jan 18, 2023 |
| Dell          | Precision 3561              | [5f23addbde](https://linux-hardware.org/?probe=5f23addbde) | Jan 18, 2023 |
| Lenovo        | ThinkPad X230 2325CW1       | [44a8ae0b56](https://linux-hardware.org/?probe=44a8ae0b56) | Jan 17, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [a80f36a4eb](https://linux-hardware.org/?probe=a80f36a4eb) | Jan 16, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [f0b2886993](https://linux-hardware.org/?probe=f0b2886993) | Jan 15, 2023 |
| Acer          | Aspire R3-131T              | [268413b274](https://linux-hardware.org/?probe=268413b274) | Jan 15, 2023 |
| Valve         | Jupiter                     | [8830efc64d](https://linux-hardware.org/?probe=8830efc64d) | Jan 15, 2023 |
| HP            | Laptop 14s-dk0xxx           | [6efb68b8da](https://linux-hardware.org/?probe=6efb68b8da) | Jan 14, 2023 |
| Lenovo        | V14-IIL 82C4                | [3837db6f8a](https://linux-hardware.org/?probe=3837db6f8a) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | [493f0e9608](https://linux-hardware.org/?probe=493f0e9608) | Jan 13, 2023 |
| Dell          | Latitude 5300               | [148745c883](https://linux-hardware.org/?probe=148745c883) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | [ac0b81bf2e](https://linux-hardware.org/?probe=ac0b81bf2e) | Jan 13, 2023 |
| Acer          | Predator PH315-52           | [c6a710b940](https://linux-hardware.org/?probe=c6a710b940) | Jan 13, 2023 |
| Dell          | Inspiron 5770               | [7435d85aca](https://linux-hardware.org/?probe=7435d85aca) | Jan 12, 2023 |
| Dell          | XPS 17 9700                 | [09f6a754d6](https://linux-hardware.org/?probe=09f6a754d6) | Jan 12, 2023 |
| Acer          | Swift SF514-54T             | [98a18475e8](https://linux-hardware.org/?probe=98a18475e8) | Jan 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [511306775e](https://linux-hardware.org/?probe=511306775e) | Jan 11, 2023 |
| Dell          | Inspiron 3543               | [c7c7419fd5](https://linux-hardware.org/?probe=c7c7419fd5) | Jan 10, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [17dc10d7bb](https://linux-hardware.org/?probe=17dc10d7bb) | Jan 10, 2023 |
| Lenovo        | ThinkPad T430s 2356AF9      | [eca34fb600](https://linux-hardware.org/?probe=eca34fb600) | Jan 09, 2023 |
| Dell          | XPS 13 9333                 | [f291c4d057](https://linux-hardware.org/?probe=f291c4d057) | Jan 09, 2023 |
| HP            | EliteBook Folio 9470m       | [1c4f7f2f2a](https://linux-hardware.org/?probe=1c4f7f2f2a) | Jan 09, 2023 |
| Dell          | Latitude 7280               | [931dcfb8be](https://linux-hardware.org/?probe=931dcfb8be) | Jan 08, 2023 |
| Dell          | Latitude E7450              | [635ef7be4a](https://linux-hardware.org/?probe=635ef7be4a) | Jan 08, 2023 |
| Lenovo        | ThinkPad W530 2463B87       | [5ac9828d4c](https://linux-hardware.org/?probe=5ac9828d4c) | Jan 08, 2023 |
| Acer          | Predator G9-793             | [5256ec6943](https://linux-hardware.org/?probe=5256ec6943) | Jan 07, 2023 |
| Apple         | MacBookPro12,1              | [67f40c78ec](https://linux-hardware.org/?probe=67f40c78ec) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [58f2e834d8](https://linux-hardware.org/?probe=58f2e834d8) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | [263354b92e](https://linux-hardware.org/?probe=263354b92e) | Jan 06, 2023 |
| Dell          | Precision M4700             | [414d8c4701](https://linux-hardware.org/?probe=414d8c4701) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | [99bf8fff2f](https://linux-hardware.org/?probe=99bf8fff2f) | Jan 06, 2023 |
| GPU Compan... | GWTN156-2BK                 | [d9fa2355b0](https://linux-hardware.org/?probe=d9fa2355b0) | Jan 05, 2023 |
| HP            | Laptop 15s-fq1xxx           | [488e1f656c](https://linux-hardware.org/?probe=488e1f656c) | Jan 03, 2023 |
| HP            | Laptop 15s-fq1xxx           | [d0ac402ed9](https://linux-hardware.org/?probe=d0ac402ed9) | Jan 03, 2023 |
| HP            | Pavilion                    | [466e855af1](https://linux-hardware.org/?probe=466e855af1) | Jan 03, 2023 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [3f68b8438c](https://linux-hardware.org/?probe=3f68b8438c) | Jan 02, 2023 |
| HP            | EliteBook 2760p             | [91741e63eb](https://linux-hardware.org/?probe=91741e63eb) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | [6ac462efda](https://linux-hardware.org/?probe=6ac462efda) | Jan 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [cf40d3f30c](https://linux-hardware.org/?probe=cf40d3f30c) | Dec 31, 2022 |
| Apple         | MacBookAir7,2               | [8b84042dc6](https://linux-hardware.org/?probe=8b84042dc6) | Dec 30, 2022 |
| Apple         | MacBookAir7,2               | [dae09ec15f](https://linux-hardware.org/?probe=dae09ec15f) | Dec 30, 2022 |
| Dell          | XPS 15 9570                 | [cc31efb32d](https://linux-hardware.org/?probe=cc31efb32d) | Dec 30, 2022 |
| ASUSTek       | X555UJ                      | [f4ba8643aa](https://linux-hardware.org/?probe=f4ba8643aa) | Dec 30, 2022 |
| AMI           | F3C2                        | [ed7d4a2a13](https://linux-hardware.org/?probe=ed7d4a2a13) | Dec 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1cf63ef1ad](https://linux-hardware.org/?probe=1cf63ef1ad) | Dec 28, 2022 |
| Acer          | Aspire 5742G                | [f58bb411b8](https://linux-hardware.org/?probe=f58bb411b8) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [d1f63174e4](https://linux-hardware.org/?probe=d1f63174e4) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [6eaa690ff2](https://linux-hardware.org/?probe=6eaa690ff2) | Dec 28, 2022 |
| Toshiba       | PORTEGE Z30-C               | [03dad182bb](https://linux-hardware.org/?probe=03dad182bb) | Dec 28, 2022 |
| MSI           | Raider GE77HX 12UGS         | [9f7185ccd7](https://linux-hardware.org/?probe=9f7185ccd7) | Dec 27, 2022 |
| MSI           | GP62M 7REX                  | [f49c90b8dc](https://linux-hardware.org/?probe=f49c90b8dc) | Dec 25, 2022 |
| Dell          | Latitude E6520              | [33a51c934d](https://linux-hardware.org/?probe=33a51c934d) | Dec 25, 2022 |
| MSI           | GS60 6QE                    | [aa2f6b0f24](https://linux-hardware.org/?probe=aa2f6b0f24) | Dec 24, 2022 |
| Toshiba       | Satellite C50D-C            | [5f2debe594](https://linux-hardware.org/?probe=5f2debe594) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [5f75bb423d](https://linux-hardware.org/?probe=5f75bb423d) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [844f589d20](https://linux-hardware.org/?probe=844f589d20) | Dec 22, 2022 |
| Acer          | Nitro AN515-52              | [4732443b9e](https://linux-hardware.org/?probe=4732443b9e) | Dec 22, 2022 |
| Acer          | Nitro AN515-52              | [354b048898](https://linux-hardware.org/?probe=354b048898) | Dec 21, 2022 |
| HP            | Pavilion dv6                | [8b0f82599c](https://linux-hardware.org/?probe=8b0f82599c) | Dec 20, 2022 |
| HUAWEI        | NBD-WXX9                    | [1fec8c22dc](https://linux-hardware.org/?probe=1fec8c22dc) | Dec 20, 2022 |
| HUAWEI        | NBD-WXX9                    | [b0a4a9919c](https://linux-hardware.org/?probe=b0a4a9919c) | Dec 18, 2022 |
| ASUSTek       | X550LD                      | [2960bdb195](https://linux-hardware.org/?probe=2960bdb195) | Dec 16, 2022 |
| Apple         | MacBookPro14,2              | [702a622854](https://linux-hardware.org/?probe=702a622854) | Dec 14, 2022 |
| Apple         | MacBookAir7,2               | [b1386d66d5](https://linux-hardware.org/?probe=b1386d66d5) | Dec 13, 2022 |
| Kogan         | KAL11C250SB                 | [e7ad1c21ad](https://linux-hardware.org/?probe=e7ad1c21ad) | Dec 13, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [265ba7b252](https://linux-hardware.org/?probe=265ba7b252) | Dec 13, 2022 |
| Dell          | XPS L521X                   | [c69c906797](https://linux-hardware.org/?probe=c69c906797) | Dec 12, 2022 |
| ASUSTek       | K56CB                       | [94b056f1f4](https://linux-hardware.org/?probe=94b056f1f4) | Dec 12, 2022 |
| Acer          | Aspire A515-45              | [26f5bfeb45](https://linux-hardware.org/?probe=26f5bfeb45) | Dec 09, 2022 |
| HP            | Laptop 15-db0xxx            | [b0de030271](https://linux-hardware.org/?probe=b0de030271) | Dec 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b5f311cc8f](https://linux-hardware.org/?probe=b5f311cc8f) | Dec 07, 2022 |
| Dell          | G15 5511                    | [999ed53283](https://linux-hardware.org/?probe=999ed53283) | Dec 05, 2022 |
| Apple         | MacBookPro15,1              | [36732e2602](https://linux-hardware.org/?probe=36732e2602) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [c458ba13c3](https://linux-hardware.org/?probe=c458ba13c3) | Dec 05, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [bd9f0dc967](https://linux-hardware.org/?probe=bd9f0dc967) | Dec 05, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fb96bd56ad](https://linux-hardware.org/?probe=fb96bd56ad) | Dec 04, 2022 |
| Unknown       | Unknown                     | [54c6593c53](https://linux-hardware.org/?probe=54c6593c53) | Dec 03, 2022 |
| Unknown       | Unknown                     | [7668b4d9a2](https://linux-hardware.org/?probe=7668b4d9a2) | Dec 03, 2022 |
| Apple         | MacBookPro8,1               | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| Acer          | ConceptD CN315-71P          | [370356b4a8](https://linux-hardware.org/?probe=370356b4a8) | Dec 02, 2022 |
| Acer          | ConceptD CN315-71P          | [bbdfc25e56](https://linux-hardware.org/?probe=bbdfc25e56) | Dec 02, 2022 |
| Intel Clie... | LAPBC510                    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | [ca1fab4db1](https://linux-hardware.org/?probe=ca1fab4db1) | Dec 02, 2022 |
| Dell          | XPS 13 9310                 | [2adab1a5b2](https://linux-hardware.org/?probe=2adab1a5b2) | Dec 02, 2022 |
| AMI           | Intel                       | [3e2e312c6e](https://linux-hardware.org/?probe=3e2e312c6e) | Nov 29, 2022 |
| Razer         | Blade                       | [de6f0ebcad](https://linux-hardware.org/?probe=de6f0ebcad) | Nov 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3433fd5db6](https://linux-hardware.org/?probe=3433fd5db6) | Nov 28, 2022 |
| Apple         | MacBookAir6,2               | [ed4692d2a7](https://linux-hardware.org/?probe=ed4692d2a7) | Nov 28, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [ea6f1fc82e](https://linux-hardware.org/?probe=ea6f1fc82e) | Nov 28, 2022 |
| Dell          | XPS 15 9500                 | [f149afb5d1](https://linux-hardware.org/?probe=f149afb5d1) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Dell          | Latitude E7440              | [3709af0366](https://linux-hardware.org/?probe=3709af0366) | Nov 27, 2022 |
| Apple         | MacBookPro15,2              | [446ef54cb5](https://linux-hardware.org/?probe=446ef54cb5) | Nov 26, 2022 |
| Apple         | MacBookAir8,1               | [6656b4e315](https://linux-hardware.org/?probe=6656b4e315) | Nov 26, 2022 |
| Kogan         | KAL11C250SB                 | [9ca4f71bb9](https://linux-hardware.org/?probe=9ca4f71bb9) | Nov 26, 2022 |
| Razer         | Blade Pro                   | [dabfd64904](https://linux-hardware.org/?probe=dabfd64904) | Nov 25, 2022 |
| MSI           | GS60 6QE                    | [80d61ee685](https://linux-hardware.org/?probe=80d61ee685) | Nov 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [16f086de33](https://linux-hardware.org/?probe=16f086de33) | Nov 25, 2022 |
| Acer          | Aspire R3-131T              | [5395a2556c](https://linux-hardware.org/?probe=5395a2556c) | Nov 24, 2022 |
| Acer          | ConceptD CN315-71P          | [db3ccac179](https://linux-hardware.org/?probe=db3ccac179) | Nov 23, 2022 |
| Apple         | MacBookPro5,1               | [62c77a0e63](https://linux-hardware.org/?probe=62c77a0e63) | Nov 23, 2022 |
| Apple         | MacBookPro5,1               | [06c02ff303](https://linux-hardware.org/?probe=06c02ff303) | Nov 21, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | [06a337fda3](https://linux-hardware.org/?probe=06a337fda3) | Nov 20, 2022 |
| Samsung       | RC410/RC510/RC710           | [965d9d2f5c](https://linux-hardware.org/?probe=965d9d2f5c) | Nov 20, 2022 |
| MSI           | GP62M 7REX                  | [2125546b68](https://linux-hardware.org/?probe=2125546b68) | Nov 19, 2022 |
| MSI           | GP62M 7REX                  | [6ea684de8c](https://linux-hardware.org/?probe=6ea684de8c) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [2cb56b8c63](https://linux-hardware.org/?probe=2cb56b8c63) | Nov 17, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [2d0fb1c5d1](https://linux-hardware.org/?probe=2d0fb1c5d1) | Nov 16, 2022 |
| AMI           | Intel                       | [ac36a02403](https://linux-hardware.org/?probe=ac36a02403) | Nov 16, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [66737bb1cc](https://linux-hardware.org/?probe=66737bb1cc) | Nov 15, 2022 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | [ccbda507a9](https://linux-hardware.org/?probe=ccbda507a9) | Nov 14, 2022 |
| ASUSTek       | X550CC                      | [d37b8f7bbd](https://linux-hardware.org/?probe=d37b8f7bbd) | Nov 13, 2022 |
| Acer          | ConceptD CN315-71P          | [2d3a3f4ac8](https://linux-hardware.org/?probe=2d3a3f4ac8) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [57368a1129](https://linux-hardware.org/?probe=57368a1129) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | [755a70132f](https://linux-hardware.org/?probe=755a70132f) | Nov 12, 2022 |
| Apple         | MacBook9,1                  | [4371465097](https://linux-hardware.org/?probe=4371465097) | Nov 12, 2022 |
| HP            | Pavilion Notebook           | [1d6ae45d45](https://linux-hardware.org/?probe=1d6ae45d45) | Nov 11, 2022 |
| MSI           | GS60 6QE                    | [a571dc503c](https://linux-hardware.org/?probe=a571dc503c) | Nov 11, 2022 |
| Toshiba       | TECRA A40-D                 | [ab2d9e2712](https://linux-hardware.org/?probe=ab2d9e2712) | Nov 11, 2022 |
| Acer          | Aspire A315-22              | [cde0b24cde](https://linux-hardware.org/?probe=cde0b24cde) | Nov 10, 2022 |
| Lenovo        | ThinkPad T420 4180PEM       | [ad4d7f338d](https://linux-hardware.org/?probe=ad4d7f338d) | Nov 09, 2022 |
| HP            | ProBook 640 G1              | [3189f08179](https://linux-hardware.org/?probe=3189f08179) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | [a7de751ce8](https://linux-hardware.org/?probe=a7de751ce8) | Nov 09, 2022 |
| Dell          | XPS 13 9310                 | [5f358af327](https://linux-hardware.org/?probe=5f358af327) | Nov 08, 2022 |
| MSI           | GS60 6QE                    | [c843b1ff5e](https://linux-hardware.org/?probe=c843b1ff5e) | Nov 08, 2022 |
| ASUSTek       | K53E                        | [07d6d01b99](https://linux-hardware.org/?probe=07d6d01b99) | Nov 06, 2022 |
| Dell          | Latitude E6430              | [fcd82d5966](https://linux-hardware.org/?probe=fcd82d5966) | Nov 06, 2022 |
| Toshiba       | Satellite L500              | [0d6bb9cde0](https://linux-hardware.org/?probe=0d6bb9cde0) | Nov 05, 2022 |
| Toshiba       | Satellite L500              | [3d7692d178](https://linux-hardware.org/?probe=3d7692d178) | Nov 05, 2022 |
| MSI           | Katana GF76 12UC            | [3cb05bdb95](https://linux-hardware.org/?probe=3cb05bdb95) | Nov 04, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [c39a19fa2f](https://linux-hardware.org/?probe=c39a19fa2f) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [cc28dc5c8b](https://linux-hardware.org/?probe=cc28dc5c8b) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | [a8f3260004](https://linux-hardware.org/?probe=a8f3260004) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | [e24f2a2f57](https://linux-hardware.org/?probe=e24f2a2f57) | Nov 03, 2022 |
| ASUSTek       | 1005HA                      | [1d386943d6](https://linux-hardware.org/?probe=1d386943d6) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Cube          | i18-BL                      | [725100a829](https://linux-hardware.org/?probe=725100a829) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| HP            | Notebook                    | [27d097b522](https://linux-hardware.org/?probe=27d097b522) | Nov 01, 2022 |
| Acer          | Aspire 3000                 | [02693e03ca](https://linux-hardware.org/?probe=02693e03ca) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| ASUSTek       | X501A                       | [d5a34df414](https://linux-hardware.org/?probe=d5a34df414) | Nov 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [c3ea4065c4](https://linux-hardware.org/?probe=c3ea4065c4) | Oct 29, 2022 |
| ASUSTek       | U50Vg                       | [5f2997ec95](https://linux-hardware.org/?probe=5f2997ec95) | Oct 28, 2022 |
| HP            | ProBook 640 G1              | [b096155d39](https://linux-hardware.org/?probe=b096155d39) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Apple         | MacBookAir6,2               | [cca0d420fe](https://linux-hardware.org/?probe=cca0d420fe) | Oct 27, 2022 |
| HP            | G71                         | [3223e2fcc8](https://linux-hardware.org/?probe=3223e2fcc8) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ffd604fea](https://linux-hardware.org/?probe=4ffd604fea) | Oct 25, 2022 |
| Apple         | MacBookAir7,2               | [6f72d6443c](https://linux-hardware.org/?probe=6f72d6443c) | Oct 23, 2022 |
| Apple         | MacBookAir6,2               | [edd13bcc76](https://linux-hardware.org/?probe=edd13bcc76) | Oct 23, 2022 |
| Notebook      | W650EH                      | [6bb1a8b1f1](https://linux-hardware.org/?probe=6bb1a8b1f1) | Oct 23, 2022 |
| Purism        | Librem 13 v2                | [5296ed1e19](https://linux-hardware.org/?probe=5296ed1e19) | Oct 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [cb901021a7](https://linux-hardware.org/?probe=cb901021a7) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [63751816bc](https://linux-hardware.org/?probe=63751816bc) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | [31d7e67080](https://linux-hardware.org/?probe=31d7e67080) | Oct 21, 2022 |
| Acer          | Aspire 5600                 | [202a7e570e](https://linux-hardware.org/?probe=202a7e570e) | Oct 20, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [2cd92a7da8](https://linux-hardware.org/?probe=2cd92a7da8) | Oct 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | [5086e64fed](https://linux-hardware.org/?probe=5086e64fed) | Oct 19, 2022 |
| Dell          | Inspiron M5010              | [026a7a8cd3](https://linux-hardware.org/?probe=026a7a8cd3) | Oct 18, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [926d661756](https://linux-hardware.org/?probe=926d661756) | Oct 17, 2022 |
| HP            | G71                         | [46b6033e1e](https://linux-hardware.org/?probe=46b6033e1e) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | [50c44df4fb](https://linux-hardware.org/?probe=50c44df4fb) | Oct 17, 2022 |
| Dell          | Inspiron 1545               | [d9928a4ee9](https://linux-hardware.org/?probe=d9928a4ee9) | Oct 16, 2022 |
| System76      | Galago Pro                  | [ec92c5a918](https://linux-hardware.org/?probe=ec92c5a918) | Oct 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | [5f0c4b3acb](https://linux-hardware.org/?probe=5f0c4b3acb) | Oct 13, 2022 |
| Apple         | MacBookPro15,2              | [705e4f406a](https://linux-hardware.org/?probe=705e4f406a) | Oct 13, 2022 |
| HP            | EliteBook 8540p             | [cd65876f22](https://linux-hardware.org/?probe=cd65876f22) | Oct 12, 2022 |
| Apple         | MacBookPro15,2              | [56fc798c2e](https://linux-hardware.org/?probe=56fc798c2e) | Oct 11, 2022 |
| Acer          | Aspire A315-22              | [07870a3cde](https://linux-hardware.org/?probe=07870a3cde) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1ae81569dd](https://linux-hardware.org/?probe=1ae81569dd) | Oct 11, 2022 |
| Dell          | Inspiron 16 5620            | [72151cd0e8](https://linux-hardware.org/?probe=72151cd0e8) | Oct 10, 2022 |
| Gigabyte      | P34V7                       | [c1423fce9e](https://linux-hardware.org/?probe=c1423fce9e) | Oct 10, 2022 |
| System76      | Galago Pro                  | [28e36afa26](https://linux-hardware.org/?probe=28e36afa26) | Oct 10, 2022 |
| HP            | ProBook 470 G5              | [a7b96649da](https://linux-hardware.org/?probe=a7b96649da) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [439e2c8122](https://linux-hardware.org/?probe=439e2c8122) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [bc5820629b](https://linux-hardware.org/?probe=bc5820629b) | Oct 09, 2022 |
| Dell          | XPS 15 9510                 | [6b62586012](https://linux-hardware.org/?probe=6b62586012) | Oct 09, 2022 |
| Apple         | MacBookAir7,2               | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| HP            | Presario V4000 (EQ608PA#... | [f462d80b2a](https://linux-hardware.org/?probe=f462d80b2a) | Oct 06, 2022 |
| Dell          | XPS 15 9510                 | [99f16967b2](https://linux-hardware.org/?probe=99f16967b2) | Oct 05, 2022 |
| Gigabyte      | AORUS 7 SB                  | [444224d1e0](https://linux-hardware.org/?probe=444224d1e0) | Oct 04, 2022 |
| Acer          | TravelMate 8572T            | [6abaaf4aa6](https://linux-hardware.org/?probe=6abaaf4aa6) | Oct 03, 2022 |
| Dell          | Inspiron 15 7510            | [521636075a](https://linux-hardware.org/?probe=521636075a) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| HP            | ProBook 450 G4              | [9c6340e585](https://linux-hardware.org/?probe=9c6340e585) | Oct 01, 2022 |
| Toshiba       | PORTEGE Z10t-A              | [1aa913c010](https://linux-hardware.org/?probe=1aa913c010) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Acer          | TravelMate 8572T            | [927bf01e34](https://linux-hardware.org/?probe=927bf01e34) | Sep 30, 2022 |
| Gigabyte      | AORUS 17 YE5                | [54b271c3fd](https://linux-hardware.org/?probe=54b271c3fd) | Sep 30, 2022 |
| Acer          | Aspire 5742G                | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | [ac3079df8c](https://linux-hardware.org/?probe=ac3079df8c) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | [144cad649c](https://linux-hardware.org/?probe=144cad649c) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [fbc4f29134](https://linux-hardware.org/?probe=fbc4f29134) | Sep 28, 2022 |
| HP            | EliteBook 8770w             | [e5ec559da4](https://linux-hardware.org/?probe=e5ec559da4) | Sep 28, 2022 |
| Dell          | Latitude E7450              | [daeb4afb69](https://linux-hardware.org/?probe=daeb4afb69) | Sep 28, 2022 |
| Gigabyte      | P34V7                       | [27b9651432](https://linux-hardware.org/?probe=27b9651432) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| System76      | Galago Pro                  | [6b2de473b7](https://linux-hardware.org/?probe=6b2de473b7) | Sep 26, 2022 |
| Gigabyte      | AORUS 7 SB                  | [3e8222ad7c](https://linux-hardware.org/?probe=3e8222ad7c) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| Dell          | G15 5511                    | [f960f38940](https://linux-hardware.org/?probe=f960f38940) | Sep 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [6c0c9c0037](https://linux-hardware.org/?probe=6c0c9c0037) | Sep 25, 2022 |
| Apple         | MacBookAir7,2               | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| HP            | Pavilion dv6                | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [24b2810c64](https://linux-hardware.org/?probe=24b2810c64) | Sep 24, 2022 |
| Acer          | TMP645-M                    | [83b27c389c](https://linux-hardware.org/?probe=83b27c389c) | Sep 23, 2022 |
| Dell          | Precision 7760              | [f47fe0314b](https://linux-hardware.org/?probe=f47fe0314b) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | [a01352810a](https://linux-hardware.org/?probe=a01352810a) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen2... | [87a3d977b1](https://linux-hardware.org/?probe=87a3d977b1) | Sep 22, 2022 |
| Apple         | MacBookPro8,1               | [d97b8fc0ed](https://linux-hardware.org/?probe=d97b8fc0ed) | Sep 21, 2022 |
| Apple         | MacBookPro10,2              | [ecc3b7e71d](https://linux-hardware.org/?probe=ecc3b7e71d) | Sep 19, 2022 |
| ASUSTek       | 1005HA                      | [3b5d6a5b1d](https://linux-hardware.org/?probe=3b5d6a5b1d) | Sep 18, 2022 |
| ASUSTek       | 1005HA                      | [3b1ce0471e](https://linux-hardware.org/?probe=3b1ce0471e) | Sep 18, 2022 |
| Lenovo        | V310-15ISK 80SY             | [fbd66d36f4](https://linux-hardware.org/?probe=fbd66d36f4) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Acer          | Aspire A315-42              | [6121dfd67d](https://linux-hardware.org/?probe=6121dfd67d) | Sep 13, 2022 |
| HP            | ENVY 15                     | [fdb07294df](https://linux-hardware.org/?probe=fdb07294df) | Sep 13, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [d477c1084d](https://linux-hardware.org/?probe=d477c1084d) | Sep 10, 2022 |
| Acer          | Aspire A315-22              | [82058771f7](https://linux-hardware.org/?probe=82058771f7) | Sep 09, 2022 |
| Dell          | Latitude E7470              | [4a2f647549](https://linux-hardware.org/?probe=4a2f647549) | Sep 08, 2022 |
| Acer          | Aspire A315-22              | [49d54ac5c5](https://linux-hardware.org/?probe=49d54ac5c5) | Sep 07, 2022 |
| ASUSTek       | K55VD                       | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| HP            | Pavilion dv6500             | [c37bace401](https://linux-hardware.org/?probe=c37bace401) | Sep 05, 2022 |
| Dell          | XPS 13 9350                 | [dc37712dfc](https://linux-hardware.org/?probe=dc37712dfc) | Sep 02, 2022 |
| Lenovo        | Z50-70 20354                | [8ac8531142](https://linux-hardware.org/?probe=8ac8531142) | Sep 01, 2022 |
| Toshiba       | Satellite C850              | [6cf6d8fca8](https://linux-hardware.org/?probe=6cf6d8fca8) | Sep 01, 2022 |
| ASUSTek       | X550CC                      | [21f3eb8b1d](https://linux-hardware.org/?probe=21f3eb8b1d) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | [6e245e4c63](https://linux-hardware.org/?probe=6e245e4c63) | Sep 01, 2022 |
| HP            | Notebook                    | [ee135c3930](https://linux-hardware.org/?probe=ee135c3930) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | [5d7cb36794](https://linux-hardware.org/?probe=5d7cb36794) | Aug 31, 2022 |
| HP            | EliteBook 830 G6            | [897046248f](https://linux-hardware.org/?probe=897046248f) | Aug 30, 2022 |
| Lenovo        | V14-ADA 82C6                | [ce25a77e25](https://linux-hardware.org/?probe=ce25a77e25) | Aug 29, 2022 |
| HP            | EW7-I7D22875GR1             | [307b75624e](https://linux-hardware.org/?probe=307b75624e) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| IT Channel... | NH5xAx                      | [66573b4b48](https://linux-hardware.org/?probe=66573b4b48) | Aug 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [f30320f76e](https://linux-hardware.org/?probe=f30320f76e) | Aug 27, 2022 |
| Acer          | Aspire V5-531               | [75b841b0b8](https://linux-hardware.org/?probe=75b841b0b8) | Aug 26, 2022 |
| HP            | Laptop 15-da1xxx            | [51e23209a4](https://linux-hardware.org/?probe=51e23209a4) | Aug 26, 2022 |
| Dell          | Latitude 5300               | [f336b3aeaf](https://linux-hardware.org/?probe=f336b3aeaf) | Aug 26, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [416e5db831](https://linux-hardware.org/?probe=416e5db831) | Aug 26, 2022 |
| Acer          | Aspire V5-531               | [4ae228e219](https://linux-hardware.org/?probe=4ae228e219) | Aug 25, 2022 |
| Dell          | XPS 13 7390                 | [d609bf3253](https://linux-hardware.org/?probe=d609bf3253) | Aug 24, 2022 |
| Alienware     | 15 R4                       | [f53260e0c2](https://linux-hardware.org/?probe=f53260e0c2) | Aug 23, 2022 |
| Dell          | Inspiron 5770               | [49314a1dfe](https://linux-hardware.org/?probe=49314a1dfe) | Aug 23, 2022 |
| Apple         | MacBook9,1                  | [a6726b8439](https://linux-hardware.org/?probe=a6726b8439) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | [aff9259c2c](https://linux-hardware.org/?probe=aff9259c2c) | Aug 22, 2022 |
| Samsung       | 550P5C/550P7C               | [75f94f8fa5](https://linux-hardware.org/?probe=75f94f8fa5) | Aug 21, 2022 |
| Samsung       | 550P5C/550P7C               | [c369daf6b0](https://linux-hardware.org/?probe=c369daf6b0) | Aug 21, 2022 |
| ASUSTek       | X756UAK                     | [6db3b2a7bc](https://linux-hardware.org/?probe=6db3b2a7bc) | Aug 20, 2022 |
| Dell          | G3 3779                     | [a2b721ca15](https://linux-hardware.org/?probe=a2b721ca15) | Aug 19, 2022 |
| Dell          | XPS 15 9530                 | [9e6a3e80b4](https://linux-hardware.org/?probe=9e6a3e80b4) | Aug 19, 2022 |
| Dell          | Inspiron M5010              | [266f9fc41d](https://linux-hardware.org/?probe=266f9fc41d) | Aug 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e500790878](https://linux-hardware.org/?probe=e500790878) | Aug 18, 2022 |
| Lenovo        | ThinkPad T480s 20L70044A... | [f90559618b](https://linux-hardware.org/?probe=f90559618b) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [26f646cca0](https://linux-hardware.org/?probe=26f646cca0) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [98b5311ef6](https://linux-hardware.org/?probe=98b5311ef6) | Aug 17, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [e32eeecfaa](https://linux-hardware.org/?probe=e32eeecfaa) | Aug 15, 2022 |
| Apple         | MacBookAir6,2               | [2c210a5825](https://linux-hardware.org/?probe=2c210a5825) | Aug 14, 2022 |
| Toshiba       | Satellite L500              | [0d58c17039](https://linux-hardware.org/?probe=0d58c17039) | Aug 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [26c131aca1](https://linux-hardware.org/?probe=26c131aca1) | Aug 13, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [662f0801b7](https://linux-hardware.org/?probe=662f0801b7) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [166edbd7db](https://linux-hardware.org/?probe=166edbd7db) | Aug 12, 2022 |
| Dell          | Latitude 6430U              | [d21ca8c2e6](https://linux-hardware.org/?probe=d21ca8c2e6) | Aug 11, 2022 |
| HP            | ProBook 430 G5              | [72a09e7b69](https://linux-hardware.org/?probe=72a09e7b69) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [abaec227ae](https://linux-hardware.org/?probe=abaec227ae) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | [a1effa04c3](https://linux-hardware.org/?probe=a1effa04c3) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [209cd4bc66](https://linux-hardware.org/?probe=209cd4bc66) | Aug 05, 2022 |
| Acer          | Nitro AN515-52              | [8b737740c3](https://linux-hardware.org/?probe=8b737740c3) | Aug 05, 2022 |
| Acer          | Aspire A515-55              | [3ef0714d78](https://linux-hardware.org/?probe=3ef0714d78) | Aug 04, 2022 |
| Toshiba       | Satellite Pro L670          | [302749341d](https://linux-hardware.org/?probe=302749341d) | Aug 03, 2022 |
| Dell          | XPS 9320                    | [9b24b29553](https://linux-hardware.org/?probe=9b24b29553) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | [e6189ba78c](https://linux-hardware.org/?probe=e6189ba78c) | Aug 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [a67d881d6f](https://linux-hardware.org/?probe=a67d881d6f) | Aug 02, 2022 |
| HP            | EliteBook 2570p             | [b352b7e051](https://linux-hardware.org/?probe=b352b7e051) | Aug 02, 2022 |
| Apple         | MacBook9,1                  | [77687a9bac](https://linux-hardware.org/?probe=77687a9bac) | Aug 02, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [370b872aa5](https://linux-hardware.org/?probe=370b872aa5) | Aug 01, 2022 |
| Acer          | ConceptD CN315-71P          | [c7ed484a1f](https://linux-hardware.org/?probe=c7ed484a1f) | Jul 30, 2022 |
| Dell          | Inspiron M5010              | [bd4cf45b33](https://linux-hardware.org/?probe=bd4cf45b33) | Jul 30, 2022 |
| Acer          | Aspire 5742G                | [e42501aacb](https://linux-hardware.org/?probe=e42501aacb) | Jul 28, 2022 |
| ASUSTek       | X555YA                      | [ddd00fbeea](https://linux-hardware.org/?probe=ddd00fbeea) | Jul 28, 2022 |
| Dell          | Latitude E7250              | [26a8591f1d](https://linux-hardware.org/?probe=26a8591f1d) | Jul 27, 2022 |
| HP            | Laptop 17-cp0xxx            | [761563e485](https://linux-hardware.org/?probe=761563e485) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Dell          | Latitude 3400               | [3412e8deac](https://linux-hardware.org/?probe=3412e8deac) | Jul 26, 2022 |
| Lenovo        | G570 4334                   | [e4c223e83e](https://linux-hardware.org/?probe=e4c223e83e) | Jul 25, 2022 |
| Apple         | MacBookAir6,1               | [ede7f6cdae](https://linux-hardware.org/?probe=ede7f6cdae) | Jul 23, 2022 |
| Acer          | Nitro AN515-55              | [85f2ffe45a](https://linux-hardware.org/?probe=85f2ffe45a) | Jul 22, 2022 |
| Acer          | ConceptD CN315-71P          | [2723b19c18](https://linux-hardware.org/?probe=2723b19c18) | Jul 22, 2022 |
| Google        | Peppy                       | [3bfdae8e5e](https://linux-hardware.org/?probe=3bfdae8e5e) | Jul 21, 2022 |
| Acer          | Aspire One 753              | [eff74923d7](https://linux-hardware.org/?probe=eff74923d7) | Jul 21, 2022 |
| Dell          | Latitude 5430               | [f02c4072c1](https://linux-hardware.org/?probe=f02c4072c1) | Jul 21, 2022 |
| Acer          | Aspire R3-131T              | [c3722806fe](https://linux-hardware.org/?probe=c3722806fe) | Jul 21, 2022 |
| Apple         | MacBookPro9,2               | [add1e46d7e](https://linux-hardware.org/?probe=add1e46d7e) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | [2360c35ac1](https://linux-hardware.org/?probe=2360c35ac1) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | [5cb9487776](https://linux-hardware.org/?probe=5cb9487776) | Jul 20, 2022 |
| Dell          | Inspiron 1545               | [b0e3b75c3b](https://linux-hardware.org/?probe=b0e3b75c3b) | Jul 19, 2022 |
| Acer          | TravelMate 8572T            | [54e7b50fc7](https://linux-hardware.org/?probe=54e7b50fc7) | Jul 18, 2022 |
| Alienware     | x17 R1                      | [9fc2d6416d](https://linux-hardware.org/?probe=9fc2d6416d) | Jul 16, 2022 |
| Apple         | MacBookAir7,2               | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | [5fd8a1dcf4](https://linux-hardware.org/?probe=5fd8a1dcf4) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | [de83d4ef43](https://linux-hardware.org/?probe=de83d4ef43) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | [01e6c30eff](https://linux-hardware.org/?probe=01e6c30eff) | Jul 15, 2022 |
| Dell          | Inspiron 16 Plus 7620       | [73be4f7864](https://linux-hardware.org/?probe=73be4f7864) | Jul 14, 2022 |
| Acer          | Nitro AN515-56              | [2418745195](https://linux-hardware.org/?probe=2418745195) | Jul 14, 2022 |
| Dell          | Inspiron M5010              | [56be64f444](https://linux-hardware.org/?probe=56be64f444) | Jul 14, 2022 |
| ASUSTek       | GL702ZC                     | [755f571a3e](https://linux-hardware.org/?probe=755f571a3e) | Jul 14, 2022 |
| Dell          | XPS 13 9360                 | [ef3bc84295](https://linux-hardware.org/?probe=ef3bc84295) | Jul 13, 2022 |
| Acer          | Aspire R3-131T              | [4126a95603](https://linux-hardware.org/?probe=4126a95603) | Jul 13, 2022 |
| Apple         | MacBook9,1                  | [0ce6078768](https://linux-hardware.org/?probe=0ce6078768) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | [facbace782](https://linux-hardware.org/?probe=facbace782) | Jul 12, 2022 |
| Acer          | Aspire 1830T                | [d2ff08ade8](https://linux-hardware.org/?probe=d2ff08ade8) | Jul 10, 2022 |
| HP            | EliteBook 8470p             | [c048bb9697](https://linux-hardware.org/?probe=c048bb9697) | Jul 09, 2022 |
| Apple         | MacBookPro9,2               | [663a6c9413](https://linux-hardware.org/?probe=663a6c9413) | Jul 08, 2022 |
| Acer          | Aspire R3-131T              | [749a597089](https://linux-hardware.org/?probe=749a597089) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | [e34a9c3166](https://linux-hardware.org/?probe=e34a9c3166) | Jul 08, 2022 |
| HP            | EliteBook 850 G1            | [1a2485b399](https://linux-hardware.org/?probe=1a2485b399) | Jul 06, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [ce6d3ec137](https://linux-hardware.org/?probe=ce6d3ec137) | Jul 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [e24a6dd845](https://linux-hardware.org/?probe=e24a6dd845) | Jul 05, 2022 |
| HP            | EliteBook 840 G6            | [d6dccd6ed7](https://linux-hardware.org/?probe=d6dccd6ed7) | Jul 05, 2022 |
| HUAWEI        | KLVD-WXX9                   | [422a12c217](https://linux-hardware.org/?probe=422a12c217) | Jul 05, 2022 |
| HP            | Pavilion g6                 | [0cd693879d](https://linux-hardware.org/?probe=0cd693879d) | Jul 05, 2022 |
| Acer          | ConceptD CN315-71P          | [76d6073818](https://linux-hardware.org/?probe=76d6073818) | Jul 05, 2022 |
| Dell          | Precision M4700             | [48cbbf8dd2](https://linux-hardware.org/?probe=48cbbf8dd2) | Jul 05, 2022 |
| Acer          | Aspire R3-131T              | [748f42be21](https://linux-hardware.org/?probe=748f42be21) | Jul 05, 2022 |
| Apple         | MacBookPro10,2              | [40d0cb89c5](https://linux-hardware.org/?probe=40d0cb89c5) | Jul 04, 2022 |
| HP            | EliteBook 8470p             | [4600681149](https://linux-hardware.org/?probe=4600681149) | Jul 03, 2022 |
| HP            | EliteBook 8470p             | [85c5a62101](https://linux-hardware.org/?probe=85c5a62101) | Jul 03, 2022 |
| Acer          | Aspire A315-21G             | [bcc3835be5](https://linux-hardware.org/?probe=bcc3835be5) | Jul 03, 2022 |
| Acer          | Aspire A315-21G             | [5f3197f581](https://linux-hardware.org/?probe=5f3197f581) | Jul 03, 2022 |
| Acer          | Swift SF114-34              | [dd9610011c](https://linux-hardware.org/?probe=dd9610011c) | Jul 02, 2022 |
| Apple         | MacBookPro9,2               | [4f6364d861](https://linux-hardware.org/?probe=4f6364d861) | Jul 02, 2022 |
| Dell          | Inspiron M5010              | [14b9aa33d2](https://linux-hardware.org/?probe=14b9aa33d2) | Jul 01, 2022 |
| HP            | EliteBook 8470p             | [cd488e4f64](https://linux-hardware.org/?probe=cd488e4f64) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [52dfa0a4ee](https://linux-hardware.org/?probe=52dfa0a4ee) | Jun 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3a423eae14](https://linux-hardware.org/?probe=3a423eae14) | Jun 30, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [1b5babe2aa](https://linux-hardware.org/?probe=1b5babe2aa) | Jun 29, 2022 |
| AMI           | Intel                       | [2b592e2f4a](https://linux-hardware.org/?probe=2b592e2f4a) | Jun 29, 2022 |
| Dell          | Latitude 5430               | [119502eddb](https://linux-hardware.org/?probe=119502eddb) | Jun 29, 2022 |
| Dell          | G3 3500                     | [0df1b9607c](https://linux-hardware.org/?probe=0df1b9607c) | Jun 27, 2022 |
| HUAWEI        | KLVD-WXX9                   | [b947b14fe4](https://linux-hardware.org/?probe=b947b14fe4) | Jun 27, 2022 |
| Alienware     | 14                          | [8846f2e474](https://linux-hardware.org/?probe=8846f2e474) | Jun 24, 2022 |
| Apple         | MacBook9,1                  | [e6f1068c91](https://linux-hardware.org/?probe=e6f1068c91) | Jun 24, 2022 |
| HP            | Presario CQ62               | [2f136051c9](https://linux-hardware.org/?probe=2f136051c9) | Jun 24, 2022 |
| HP            | Presario CQ62               | [9beeb6d3c2](https://linux-hardware.org/?probe=9beeb6d3c2) | Jun 23, 2022 |
| Lenovo        | ThinkPad E490s 20NG0002A... | [4cce05dc1c](https://linux-hardware.org/?probe=4cce05dc1c) | Jun 23, 2022 |
| Apple         | MacBook9,1                  | [3656b8227f](https://linux-hardware.org/?probe=3656b8227f) | Jun 23, 2022 |
| Toshiba       | TECRA A40-D                 | [6307594332](https://linux-hardware.org/?probe=6307594332) | Jun 23, 2022 |
| Acer          | Nitro AN515-55              | [bc159b637c](https://linux-hardware.org/?probe=bc159b637c) | Jun 22, 2022 |
| HP            | 250 G6 Notebook PC          | [30d0a46d81](https://linux-hardware.org/?probe=30d0a46d81) | Jun 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [f013ebb91b](https://linux-hardware.org/?probe=f013ebb91b) | Jun 20, 2022 |
| Acer          | Iconia                      | [2d1f1a2c32](https://linux-hardware.org/?probe=2d1f1a2c32) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [b3da04a3af](https://linux-hardware.org/?probe=b3da04a3af) | Jun 20, 2022 |
| Framework     | Laptop                      | [f5ece7ce85](https://linux-hardware.org/?probe=f5ece7ce85) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [b88b88ba84](https://linux-hardware.org/?probe=b88b88ba84) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | [ec132b0ba5](https://linux-hardware.org/?probe=ec132b0ba5) | Jun 19, 2022 |
| Acer          | ConceptD CN315-71P          | [66d09f029f](https://linux-hardware.org/?probe=66d09f029f) | Jun 18, 2022 |
| Dell          | Precision 5540              | [6d3f2c188b](https://linux-hardware.org/?probe=6d3f2c188b) | Jun 17, 2022 |
| Acer          | ConceptD CN315-71P          | [9b162f339b](https://linux-hardware.org/?probe=9b162f339b) | Jun 16, 2022 |
| HUAWEI        | KLVD-WXX9                   | [4c97b8cc3a](https://linux-hardware.org/?probe=4c97b8cc3a) | Jun 16, 2022 |
| Alienware     | m15 R7                      | [9775a12e11](https://linux-hardware.org/?probe=9775a12e11) | Jun 16, 2022 |
| Acer          | Nitro AN515-55              | [bb631825e3](https://linux-hardware.org/?probe=bb631825e3) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [76fd9cba2e](https://linux-hardware.org/?probe=76fd9cba2e) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [b3259c0af4](https://linux-hardware.org/?probe=b3259c0af4) | Jun 14, 2022 |
| MSI           | Modern 15 A5M               | [bd16d5829c](https://linux-hardware.org/?probe=bd16d5829c) | Jun 14, 2022 |
| Apple         | MacBookPro11,1              | [57b90afcda](https://linux-hardware.org/?probe=57b90afcda) | Jun 14, 2022 |
| Dell          | Vostro 1500                 | [748a8a831b](https://linux-hardware.org/?probe=748a8a831b) | Jun 12, 2022 |
| HP            | Compaq 6730b                | [dd94c9145b](https://linux-hardware.org/?probe=dd94c9145b) | Jun 11, 2022 |
| ASUSTek       | Unknown                     | [1cc4adfa36](https://linux-hardware.org/?probe=1cc4adfa36) | Jun 09, 2022 |
| Alienware     | x17 R2                      | [78b867a06e](https://linux-hardware.org/?probe=78b867a06e) | Jun 08, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [75d6b8489b](https://linux-hardware.org/?probe=75d6b8489b) | Jun 08, 2022 |
| Acer          | Aspire R3-131T              | [1dab354de2](https://linux-hardware.org/?probe=1dab354de2) | Jun 07, 2022 |
| Acer          | Nitro AN515-55              | [4ab9f94abe](https://linux-hardware.org/?probe=4ab9f94abe) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [d98f987b46](https://linux-hardware.org/?probe=d98f987b46) | Jun 06, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2KW1... | [686fcbebd3](https://linux-hardware.org/?probe=686fcbebd3) | Jun 06, 2022 |
| Lenovo        | Yoga710-14ISK 80TY          | [116abb675e](https://linux-hardware.org/?probe=116abb675e) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | [1b09ad54c8](https://linux-hardware.org/?probe=1b09ad54c8) | Jun 05, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [57e7433cc5](https://linux-hardware.org/?probe=57e7433cc5) | Jun 04, 2022 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | [b5bb3c0725](https://linux-hardware.org/?probe=b5bb3c0725) | Jun 02, 2022 |
| Apple         | MacBookAir4,2               | [86902cb11f](https://linux-hardware.org/?probe=86902cb11f) | Jun 02, 2022 |
| Dell          | G15 5515                    | [24ddbd70dc](https://linux-hardware.org/?probe=24ddbd70dc) | Jun 02, 2022 |
| HP            | 250 G6 Notebook PC          | [878274dbce](https://linux-hardware.org/?probe=878274dbce) | Jun 02, 2022 |
| Acer          | Aspire A315-58              | [b63e54900e](https://linux-hardware.org/?probe=b63e54900e) | Jun 02, 2022 |
| Dell          | Latitude E6540              | [9cbdc3f892](https://linux-hardware.org/?probe=9cbdc3f892) | Jun 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ae39e96b1a](https://linux-hardware.org/?probe=ae39e96b1a) | Jun 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | [57f540db26](https://linux-hardware.org/?probe=57f540db26) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Dell          | Inspiron 5770               | [02b32c935c](https://linux-hardware.org/?probe=02b32c935c) | May 31, 2022 |
| IT Channel... | PA70Hx                      | [091ad22c2d](https://linux-hardware.org/?probe=091ad22c2d) | May 30, 2022 |
| Apple         | MacBookPro9,1               | [6fe2c4a416](https://linux-hardware.org/?probe=6fe2c4a416) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | [e34608096b](https://linux-hardware.org/?probe=e34608096b) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | [d21454c335](https://linux-hardware.org/?probe=d21454c335) | May 29, 2022 |
| MSI           | GT70 2OC/2OD                | [43144c3166](https://linux-hardware.org/?probe=43144c3166) | May 28, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [37d87b9245](https://linux-hardware.org/?probe=37d87b9245) | May 27, 2022 |
| Toshiba       | Satellite P850              | [9ec49310ff](https://linux-hardware.org/?probe=9ec49310ff) | May 25, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [00baf8a2ff](https://linux-hardware.org/?probe=00baf8a2ff) | May 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [32f7f3aa4b](https://linux-hardware.org/?probe=32f7f3aa4b) | May 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [43a374c1d4](https://linux-hardware.org/?probe=43a374c1d4) | May 23, 2022 |
| Acer          | Nitro AN515-45              | [293712cc51](https://linux-hardware.org/?probe=293712cc51) | May 23, 2022 |
| Apple         | MacBookPro6,1               | [40d33cea3f](https://linux-hardware.org/?probe=40d33cea3f) | May 23, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1d8684d1f5](https://linux-hardware.org/?probe=1d8684d1f5) | May 23, 2022 |
| Gigabyte      | P34V5                       | [6fa844b91e](https://linux-hardware.org/?probe=6fa844b91e) | May 23, 2022 |
| Gigabyte      | P34V5                       | [3ad8e4b239](https://linux-hardware.org/?probe=3ad8e4b239) | May 23, 2022 |
| Toshiba       | TECRA R850                  | [aa0bfd6c6a](https://linux-hardware.org/?probe=aa0bfd6c6a) | May 22, 2022 |
| Dell          | G3 3500                     | [49f86cc226](https://linux-hardware.org/?probe=49f86cc226) | May 22, 2022 |
| Dell          | Inspiron 1545               | [890010e793](https://linux-hardware.org/?probe=890010e793) | May 21, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | [5d150789cb](https://linux-hardware.org/?probe=5d150789cb) | May 19, 2022 |
| Dell          | Inspiron 7572               | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| Dell          | XPS 13 7390                 | [98752f9fb4](https://linux-hardware.org/?probe=98752f9fb4) | May 18, 2022 |
| Acer          | Aspire A515-55              | [c01f14c77f](https://linux-hardware.org/?probe=c01f14c77f) | May 18, 2022 |
| Dell          | Latitude E7450              | [26b07c8dfc](https://linux-hardware.org/?probe=26b07c8dfc) | May 18, 2022 |
| Toshiba       | Satellite C850              | [5927aac0b7](https://linux-hardware.org/?probe=5927aac0b7) | May 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d4f9f894b6](https://linux-hardware.org/?probe=d4f9f894b6) | May 16, 2022 |
| Dell          | Inspiron 5570               | [faf97fa9a0](https://linux-hardware.org/?probe=faf97fa9a0) | May 16, 2022 |
| Gigabyte      | A7 K1                       | [9cd1ec32e4](https://linux-hardware.org/?probe=9cd1ec32e4) | May 16, 2022 |
| Dell          | XPS 15 9560                 | [04f0e074cb](https://linux-hardware.org/?probe=04f0e074cb) | May 14, 2022 |
| Toshiba       | Satellite L50-A             | [30a7bebcd3](https://linux-hardware.org/?probe=30a7bebcd3) | May 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [6251446c92](https://linux-hardware.org/?probe=6251446c92) | May 13, 2022 |
| Dell          | Inspiron 15 3515            | [dd8e112250](https://linux-hardware.org/?probe=dd8e112250) | May 12, 2022 |
| HP            | Pavilion g6                 | [5662b515c3](https://linux-hardware.org/?probe=5662b515c3) | May 12, 2022 |
| Acer          | Aspire V5-573G              | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [a22c347eaf](https://linux-hardware.org/?probe=a22c347eaf) | May 11, 2022 |
| HP            | 250 G6 Notebook PC          | [f2f010a36d](https://linux-hardware.org/?probe=f2f010a36d) | May 11, 2022 |
| Apple         | MacBookPro12,1              | [0d9616886e](https://linux-hardware.org/?probe=0d9616886e) | May 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [ce3addb8a4](https://linux-hardware.org/?probe=ce3addb8a4) | May 10, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [7d146e5dec](https://linux-hardware.org/?probe=7d146e5dec) | May 10, 2022 |
| Apple         | MacBookPro7,1               | [7ff6997105](https://linux-hardware.org/?probe=7ff6997105) | May 08, 2022 |
| Dell          | Studio XPS 1645             | [0d213120b4](https://linux-hardware.org/?probe=0d213120b4) | May 08, 2022 |
| HP            | Compaq Presario CQ60        | [9d27bd494e](https://linux-hardware.org/?probe=9d27bd494e) | May 08, 2022 |
| HP            | Folio 13 - 2000             | [e859aed666](https://linux-hardware.org/?probe=e859aed666) | May 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [3d07e8a45e](https://linux-hardware.org/?probe=3d07e8a45e) | May 05, 2022 |
| Dell          | Studio 1555                 | [c02949a388](https://linux-hardware.org/?probe=c02949a388) | May 05, 2022 |
| Acer          | Aspire A315-34              | [3ed5a6d961](https://linux-hardware.org/?probe=3ed5a6d961) | May 04, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | [43dcfa4094](https://linux-hardware.org/?probe=43dcfa4094) | May 03, 2022 |
| Framework     | Laptop                      | [0d35134041](https://linux-hardware.org/?probe=0d35134041) | May 02, 2022 |
| HP            | 250 G5 Notebook PC          | [0e6717d54b](https://linux-hardware.org/?probe=0e6717d54b) | May 02, 2022 |
| HP            | EliteBook 850 G3            | [ab86c0118b](https://linux-hardware.org/?probe=ab86c0118b) | May 02, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [7206b41211](https://linux-hardware.org/?probe=7206b41211) | May 01, 2022 |
| Lenovo        | Legion Y9000X 2020 81TH     | [c335cbb270](https://linux-hardware.org/?probe=c335cbb270) | May 01, 2022 |
| HUAWEI        | BOM-WXX9                    | [faa7213f5c](https://linux-hardware.org/?probe=faa7213f5c) | Apr 30, 2022 |
| Apple         | MacBookPro8,1               | [8826e1d451](https://linux-hardware.org/?probe=8826e1d451) | Apr 30, 2022 |
| HP            | ZBook 15 G6                 | [f948921cba](https://linux-hardware.org/?probe=f948921cba) | Apr 30, 2022 |
| Dell          | Inspiron 3543               | [6165b0554d](https://linux-hardware.org/?probe=6165b0554d) | Apr 28, 2022 |
| Lenovo        | ThinkPad X250 20CLS52P0F    | [a4d291ccda](https://linux-hardware.org/?probe=a4d291ccda) | Apr 27, 2022 |
| Acer          | Aspire 5750G                | [3a96bf8237](https://linux-hardware.org/?probe=3a96bf8237) | Apr 27, 2022 |
| HP            | ProBook 4710s               | [03d5c4c5b2](https://linux-hardware.org/?probe=03d5c4c5b2) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | [981d5e03b3](https://linux-hardware.org/?probe=981d5e03b3) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | [0b3a1039fb](https://linux-hardware.org/?probe=0b3a1039fb) | Apr 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [b1b4ea439d](https://linux-hardware.org/?probe=b1b4ea439d) | Apr 25, 2022 |
| HP            | ProBook 470 G5              | [e0def5bddc](https://linux-hardware.org/?probe=e0def5bddc) | Apr 25, 2022 |
| HUAWEI        | BOM-WXX9                    | [a771d771b2](https://linux-hardware.org/?probe=a771d771b2) | Apr 24, 2022 |
| HUAWEI        | BOM-WXX9                    | [1a195527a4](https://linux-hardware.org/?probe=1a195527a4) | Apr 24, 2022 |
| Dell          | Latitude E5500              | [c954cb4ba4](https://linux-hardware.org/?probe=c954cb4ba4) | Apr 24, 2022 |
| Dell          | Latitude E5500              | [ab88dc2482](https://linux-hardware.org/?probe=ab88dc2482) | Apr 24, 2022 |
| HP            | EliteBook 2530p             | [bfaeba4483](https://linux-hardware.org/?probe=bfaeba4483) | Apr 22, 2022 |
| Dell          | Latitude 7490               | [2b8d24f8ae](https://linux-hardware.org/?probe=2b8d24f8ae) | Apr 22, 2022 |
| HP            | EliteBook 2530p             | [a68c57ea30](https://linux-hardware.org/?probe=a68c57ea30) | Apr 22, 2022 |
| MSI           | GS65 Stealth Thin 8RE       | [cbb3f353a5](https://linux-hardware.org/?probe=cbb3f353a5) | Apr 21, 2022 |
| HP            | Laptop 14s-dk0xxx           | [ec7bef597a](https://linux-hardware.org/?probe=ec7bef597a) | Apr 20, 2022 |
| HP            | Laptop 14s-dk0xxx           | [1edc356b52](https://linux-hardware.org/?probe=1edc356b52) | Apr 20, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | [d6bf3c27ef](https://linux-hardware.org/?probe=d6bf3c27ef) | Apr 20, 2022 |
| Dell          | XPS 13 7390                 | [80c38b1425](https://linux-hardware.org/?probe=80c38b1425) | Apr 19, 2022 |
| Timi          | A35S                        | [e7d8adf61f](https://linux-hardware.org/?probe=e7d8adf61f) | Apr 19, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [4c845dc459](https://linux-hardware.org/?probe=4c845dc459) | Apr 19, 2022 |
| HP            | 250 G5 Notebook PC          | [5cb8325ed4](https://linux-hardware.org/?probe=5cb8325ed4) | Apr 18, 2022 |
| Acer          | Aspire R3-131T              | [48f584f713](https://linux-hardware.org/?probe=48f584f713) | Apr 17, 2022 |
| Apple         | MacBookPro5,4               | [918fef81c3](https://linux-hardware.org/?probe=918fef81c3) | Apr 17, 2022 |
| Dell          | Studio XPS 1645             | [6e722019b4](https://linux-hardware.org/?probe=6e722019b4) | Apr 16, 2022 |
| Dell          | Inspiron 1012               | [4659a757bf](https://linux-hardware.org/?probe=4659a757bf) | Apr 15, 2022 |
| Dell          | Inspiron 1012               | [ebfcf670fc](https://linux-hardware.org/?probe=ebfcf670fc) | Apr 15, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [c43bc1fcba](https://linux-hardware.org/?probe=c43bc1fcba) | Apr 15, 2022 |
| Dell          | Latitude E6530              | [d6f985e2ca](https://linux-hardware.org/?probe=d6f985e2ca) | Apr 15, 2022 |
| Dell          | Latitude E6230              | [19e2fe3c97](https://linux-hardware.org/?probe=19e2fe3c97) | Apr 14, 2022 |
| Dell          | Latitude 5590               | [c306b97fcd](https://linux-hardware.org/?probe=c306b97fcd) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 4291IU6       | [a4c2a2bff9](https://linux-hardware.org/?probe=a4c2a2bff9) | Apr 14, 2022 |
| Lenovo        | ThinkPad T430 2350BC6       | [c2ffb2a421](https://linux-hardware.org/?probe=c2ffb2a421) | Apr 14, 2022 |
| ASUSTek       | X580VD                      | [4c5ccfbe60](https://linux-hardware.org/?probe=4c5ccfbe60) | Apr 12, 2022 |
| Toshiba       | Satellite L50-A             | [9a4f7c7381](https://linux-hardware.org/?probe=9a4f7c7381) | Apr 09, 2022 |
| Toshiba       | Satellite L50-A             | [ce1ec01972](https://linux-hardware.org/?probe=ce1ec01972) | Apr 09, 2022 |
| Apple         | MacBookPro9,2               | [8ae799c372](https://linux-hardware.org/?probe=8ae799c372) | Apr 08, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | [c8a1f60191](https://linux-hardware.org/?probe=c8a1f60191) | Apr 05, 2022 |
| HP            | Pavilion g6                 | [a2d8dcb1bf](https://linux-hardware.org/?probe=a2d8dcb1bf) | Apr 05, 2022 |
| Toshiba       | Satellite L50-A             | [b51d99ad47](https://linux-hardware.org/?probe=b51d99ad47) | Apr 04, 2022 |
| Kogan         | KAL11C250SB                 | [ea426eda5e](https://linux-hardware.org/?probe=ea426eda5e) | Apr 03, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6154972f18](https://linux-hardware.org/?probe=6154972f18) | Apr 03, 2022 |
| ASUSTek       | P552LA                      | [94ef2678d5](https://linux-hardware.org/?probe=94ef2678d5) | Apr 03, 2022 |
| ASUSTek       | P552LA                      | [9166f15878](https://linux-hardware.org/?probe=9166f15878) | Apr 03, 2022 |
| Lenovo        | ThinkPad T410s 2912BR7      | [04098ae404](https://linux-hardware.org/?probe=04098ae404) | Apr 02, 2022 |
| Toshiba       | TECRA M11                   | [c81e18c0f3](https://linux-hardware.org/?probe=c81e18c0f3) | Apr 01, 2022 |
| Dell          | Precision 5540              | [d923ae2736](https://linux-hardware.org/?probe=d923ae2736) | Apr 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [39b70e2f99](https://linux-hardware.org/?probe=39b70e2f99) | Apr 01, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | [339d70da8c](https://linux-hardware.org/?probe=339d70da8c) | Mar 30, 2022 |
| Dell          | Studio 1555                 | [db9f06343c](https://linux-hardware.org/?probe=db9f06343c) | Mar 30, 2022 |
| Toshiba       | Satellite Radius L10W-C     | [fc18e171f3](https://linux-hardware.org/?probe=fc18e171f3) | Mar 29, 2022 |
| HP            | Notebook                    | [c53a6a41a2](https://linux-hardware.org/?probe=c53a6a41a2) | Mar 29, 2022 |
| ASUSTek       | K55VD                       | [5c65461fe1](https://linux-hardware.org/?probe=5c65461fe1) | Mar 28, 2022 |
| Dell          | Inspiron 1545               | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Apple         | MacBook7,1                  | [70413280df](https://linux-hardware.org/?probe=70413280df) | Mar 26, 2022 |
| Apple         | MacBookPro10,1              | [a9caf3d428](https://linux-hardware.org/?probe=a9caf3d428) | Mar 25, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [20f2d24112](https://linux-hardware.org/?probe=20f2d24112) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | [64718709d1](https://linux-hardware.org/?probe=64718709d1) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | [f123e292b9](https://linux-hardware.org/?probe=f123e292b9) | Mar 23, 2022 |
| HP            | ProBook 430 G2              | [57038c6fd7](https://linux-hardware.org/?probe=57038c6fd7) | Mar 21, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [fef247389a](https://linux-hardware.org/?probe=fef247389a) | Mar 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [7dcf73063d](https://linux-hardware.org/?probe=7dcf73063d) | Mar 19, 2022 |
| HP            | ZBook Firefly 14 inch G8... | [207eca584c](https://linux-hardware.org/?probe=207eca584c) | Mar 17, 2022 |
| Toshiba       | TECRA M11                   | [34167a6878](https://linux-hardware.org/?probe=34167a6878) | Mar 17, 2022 |
| Dell          | XPS 17 9710                 | [34da0f3cdb](https://linux-hardware.org/?probe=34da0f3cdb) | Mar 16, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [f1f12206d5](https://linux-hardware.org/?probe=f1f12206d5) | Mar 15, 2022 |
| HP            | Pavilion g6                 | [378424911d](https://linux-hardware.org/?probe=378424911d) | Mar 15, 2022 |
| Dell          | XPS 15 7590                 | [527b0d7066](https://linux-hardware.org/?probe=527b0d7066) | Mar 14, 2022 |
| Toshiba       | Satellite P850              | [0cd9132f27](https://linux-hardware.org/?probe=0cd9132f27) | Mar 14, 2022 |
| Lenovo        | G40-30 80FY                 | [7b54425ba2](https://linux-hardware.org/?probe=7b54425ba2) | Mar 13, 2022 |
| Acer          | Aspire A315-21G             | [4e85fcd677](https://linux-hardware.org/?probe=4e85fcd677) | Mar 13, 2022 |
| HP            | 250 G5 Notebook PC          | [3e67ab27db](https://linux-hardware.org/?probe=3e67ab27db) | Mar 13, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [ab25401c99](https://linux-hardware.org/?probe=ab25401c99) | Mar 12, 2022 |
| Dell          | Latitude E5450              | [3d2d8b93fe](https://linux-hardware.org/?probe=3d2d8b93fe) | Mar 12, 2022 |
| Metabox       | Edge-Pro NS50MU             | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| Lenovo        | ThinkPad T480 20L5A07TAU    | [755854f7d4](https://linux-hardware.org/?probe=755854f7d4) | Mar 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [4f65353f3e](https://linux-hardware.org/?probe=4f65353f3e) | Mar 10, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | [a83a1ffe1a](https://linux-hardware.org/?probe=a83a1ffe1a) | Mar 09, 2022 |
| Apple         | MacBookPro6,1               | [b227e92b83](https://linux-hardware.org/?probe=b227e92b83) | Mar 07, 2022 |
| Apple         | MacBookPro6,1               | [ef72c023ac](https://linux-hardware.org/?probe=ef72c023ac) | Mar 07, 2022 |
| Toshiba       | Satellite Radius L10W-C     | [db90921ddd](https://linux-hardware.org/?probe=db90921ddd) | Mar 07, 2022 |
| HP            | ENVY TS 15                  | [c2305ed449](https://linux-hardware.org/?probe=c2305ed449) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [2d5c05af33](https://linux-hardware.org/?probe=2d5c05af33) | Mar 06, 2022 |
| HP            | Notebook                    | [d8b2e4567e](https://linux-hardware.org/?probe=d8b2e4567e) | Mar 05, 2022 |
| HP            | Notebook                    | [cafa2c6f1a](https://linux-hardware.org/?probe=cafa2c6f1a) | Mar 05, 2022 |
| HP            | ProBook 430 G5              | [9b130dbcb5](https://linux-hardware.org/?probe=9b130dbcb5) | Mar 04, 2022 |
| Acer          | Aspire R3-131T              | [98d5649b75](https://linux-hardware.org/?probe=98d5649b75) | Mar 03, 2022 |
| Acer          | Aspire V3-371               | [038cc99ead](https://linux-hardware.org/?probe=038cc99ead) | Mar 02, 2022 |
| Apple         | MacBookPro5,5               | [678e1eb19b](https://linux-hardware.org/?probe=678e1eb19b) | Feb 26, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [f3ec55a392](https://linux-hardware.org/?probe=f3ec55a392) | Feb 25, 2022 |
| HP            | ProBook 450 G1              | [1f26dfd88f](https://linux-hardware.org/?probe=1f26dfd88f) | Feb 22, 2022 |
| HP            | ProBook 430 G5              | [b9cb7cad60](https://linux-hardware.org/?probe=b9cb7cad60) | Feb 22, 2022 |
| HP            | ZBook 15 G6                 | [c5079e020e](https://linux-hardware.org/?probe=c5079e020e) | Feb 21, 2022 |
| Dell          | Precision 3561              | [d46fbe1d5f](https://linux-hardware.org/?probe=d46fbe1d5f) | Feb 21, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [8a6f28fc9d](https://linux-hardware.org/?probe=8a6f28fc9d) | Feb 21, 2022 |
| Toshiba       | Satellite Pro C850          | [132557a51b](https://linux-hardware.org/?probe=132557a51b) | Feb 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [fb981fe5b0](https://linux-hardware.org/?probe=fb981fe5b0) | Feb 20, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [f08a9db4fb](https://linux-hardware.org/?probe=f08a9db4fb) | Feb 20, 2022 |
| HP            | Notebook                    | [1e57c317b4](https://linux-hardware.org/?probe=1e57c317b4) | Feb 19, 2022 |
| HP            | Notebook                    | [583b61ead6](https://linux-hardware.org/?probe=583b61ead6) | Feb 19, 2022 |
| IT Channel... | P95xER                      | [c8add471fb](https://linux-hardware.org/?probe=c8add471fb) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [f7e1ab4276](https://linux-hardware.org/?probe=f7e1ab4276) | Feb 18, 2022 |
| HP            | ProBook 470 G2              | [0ef953e74d](https://linux-hardware.org/?probe=0ef953e74d) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [8791991562](https://linux-hardware.org/?probe=8791991562) | Feb 17, 2022 |
| Apple         | MacBookPro8,1               | [983c62bf72](https://linux-hardware.org/?probe=983c62bf72) | Feb 17, 2022 |
| Apple         | MacBookPro16,1              | [3e35c49d6c](https://linux-hardware.org/?probe=3e35c49d6c) | Feb 16, 2022 |
| Dell          | Inspiron 7591               | [f5cc709342](https://linux-hardware.org/?probe=f5cc709342) | Feb 16, 2022 |
| Toshiba       | Satellite C50-A             | [e88fd90806](https://linux-hardware.org/?probe=e88fd90806) | Feb 15, 2022 |
| HP            | ProBook 450 G6              | [e54664c1be](https://linux-hardware.org/?probe=e54664c1be) | Feb 15, 2022 |
| Dell          | System Vostro 3750          | [4a5289bfbe](https://linux-hardware.org/?probe=4a5289bfbe) | Feb 14, 2022 |
| Toshiba       | QOSMIO X70-A                | [c3c921f8e2](https://linux-hardware.org/?probe=c3c921f8e2) | Feb 14, 2022 |
| Lenovo        | ThinkPad T420 4178A47       | [cda9da09dc](https://linux-hardware.org/?probe=cda9da09dc) | Feb 14, 2022 |
| ASUSTek       | UX330UAK                    | [8731a73bfa](https://linux-hardware.org/?probe=8731a73bfa) | Feb 13, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2afbdea066](https://linux-hardware.org/?probe=2afbdea066) | Feb 13, 2022 |
| Toshiba       | Satellite C50-A283          | [66f810c5f5](https://linux-hardware.org/?probe=66f810c5f5) | Feb 13, 2022 |
| Kogan         | KAL11C250SB                 | [600104b8e2](https://linux-hardware.org/?probe=600104b8e2) | Feb 12, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | [9ce361abd3](https://linux-hardware.org/?probe=9ce361abd3) | Feb 12, 2022 |
| Samsung       | 700T                        | [076ad3b906](https://linux-hardware.org/?probe=076ad3b906) | Feb 11, 2022 |
| Acer          | Aspire 5600                 | [4b2259f040](https://linux-hardware.org/?probe=4b2259f040) | Feb 10, 2022 |
| HP            | Compaq CQ45                 | [3c75fd14fb](https://linux-hardware.org/?probe=3c75fd14fb) | Feb 09, 2022 |
| HP            | Pavilion dv6                | [efb945cc4f](https://linux-hardware.org/?probe=efb945cc4f) | Feb 09, 2022 |
| ASUSTek       | G74Sx                       | [d0f48fef55](https://linux-hardware.org/?probe=d0f48fef55) | Feb 08, 2022 |
| Samsung       | R580                        | [f822930ecf](https://linux-hardware.org/?probe=f822930ecf) | Feb 08, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | [1110112a7f](https://linux-hardware.org/?probe=1110112a7f) | Feb 06, 2022 |
| Star Labs     | StarBook                    | [e53bcff920](https://linux-hardware.org/?probe=e53bcff920) | Feb 06, 2022 |
| Unknown       | Unknown                     | [7848918b1d](https://linux-hardware.org/?probe=7848918b1d) | Feb 05, 2022 |
| Acer          | Aspire A515-43              | [6bc39a1855](https://linux-hardware.org/?probe=6bc39a1855) | Feb 04, 2022 |
| Lenovo        | ThinkPad Mini10 3507A31     | [f49f0801c0](https://linux-hardware.org/?probe=f49f0801c0) | Feb 03, 2022 |
| Acer          | Aspire 5741                 | [175d1e66d3](https://linux-hardware.org/?probe=175d1e66d3) | Feb 02, 2022 |
| Toshiba       | Satellite P500              | [2403a2d0f9](https://linux-hardware.org/?probe=2403a2d0f9) | Feb 02, 2022 |
| HP            | ProBook 450 G6              | [1de51c3e3b](https://linux-hardware.org/?probe=1de51c3e3b) | Feb 01, 2022 |
| HP            | ProBook 450 G6              | [e6dfa0f8ec](https://linux-hardware.org/?probe=e6dfa0f8ec) | Feb 01, 2022 |
| Apple         | MacBookPro8,1               | [1615c253fc](https://linux-hardware.org/?probe=1615c253fc) | Feb 01, 2022 |
| Dell          | XPS 15 9550                 | [e8acac784c](https://linux-hardware.org/?probe=e8acac784c) | Jan 31, 2022 |
| Dell          | XPS 15 9550                 | [33a9d5357e](https://linux-hardware.org/?probe=33a9d5357e) | Jan 31, 2022 |
| Apple         | MacBookPro8,1               | [0591806d5c](https://linux-hardware.org/?probe=0591806d5c) | Jan 31, 2022 |
| HP            | EliteBook 840 G5            | [01c1515f57](https://linux-hardware.org/?probe=01c1515f57) | Jan 28, 2022 |
| ASUSTek       | X550WA                      | [e146d6a0f8](https://linux-hardware.org/?probe=e146d6a0f8) | Jan 27, 2022 |
| Toshiba       | Satellite P850              | [9fed64bb7e](https://linux-hardware.org/?probe=9fed64bb7e) | Jan 27, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [c021622ad4](https://linux-hardware.org/?probe=c021622ad4) | Jan 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [f7c5fb7450](https://linux-hardware.org/?probe=f7c5fb7450) | Jan 26, 2022 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [36a39bf7eb](https://linux-hardware.org/?probe=36a39bf7eb) | Jan 26, 2022 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [9d12ae4f9a](https://linux-hardware.org/?probe=9d12ae4f9a) | Jan 26, 2022 |
| Intel Clie... | LAPBC710                    | [586a7bef92](https://linux-hardware.org/?probe=586a7bef92) | Jan 25, 2022 |
| Kogan         | KAL11C250SB                 | [ba3fd61313](https://linux-hardware.org/?probe=ba3fd61313) | Jan 23, 2022 |
| Toshiba       | Satellite L640              | [280b5d9630](https://linux-hardware.org/?probe=280b5d9630) | Jan 22, 2022 |
| Lenovo        | ThinkPad W530 2463B87       | [bb1640db6c](https://linux-hardware.org/?probe=bb1640db6c) | Jan 21, 2022 |
| HP            | ProBook 6560b               | [d5dc02b800](https://linux-hardware.org/?probe=d5dc02b800) | Jan 21, 2022 |
| Dell          | Inspiron 7591               | [2f1c294587](https://linux-hardware.org/?probe=2f1c294587) | Jan 21, 2022 |
| HP            | ProBook 470 G5              | [b4c6ea0b27](https://linux-hardware.org/?probe=b4c6ea0b27) | Jan 18, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [a61f1b9d56](https://linux-hardware.org/?probe=a61f1b9d56) | Jan 16, 2022 |
| Dell          | Latitude 7280               | [d05eb9657d](https://linux-hardware.org/?probe=d05eb9657d) | Jan 16, 2022 |
| ASUSTek       | Unknown                     | [0baed0f9c8](https://linux-hardware.org/?probe=0baed0f9c8) | Jan 16, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [6bda3e5854](https://linux-hardware.org/?probe=6bda3e5854) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [d62f3c4bf5](https://linux-hardware.org/?probe=d62f3c4bf5) | Jan 14, 2022 |
| ASUSTek       | TP500LNG                    | [85762ec0a0](https://linux-hardware.org/?probe=85762ec0a0) | Jan 14, 2022 |
| Dell          | Inspiron M5010              | [21dddfe6a8](https://linux-hardware.org/?probe=21dddfe6a8) | Jan 14, 2022 |
| Acer          | Swift SF514-54T             | [dffa1b1708](https://linux-hardware.org/?probe=dffa1b1708) | Jan 14, 2022 |
| Apple         | MacBookPro16,1              | [ca163c9952](https://linux-hardware.org/?probe=ca163c9952) | Jan 14, 2022 |
| Acer          | Swift SF514-54T             | [cf529c7ad0](https://linux-hardware.org/?probe=cf529c7ad0) | Jan 14, 2022 |
| HP            | EliteBook 8770w             | [d78d315a83](https://linux-hardware.org/?probe=d78d315a83) | Jan 13, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [f7ea85c311](https://linux-hardware.org/?probe=f7ea85c311) | Jan 13, 2022 |
| HP            | Pavilion g6                 | [e14f742bb9](https://linux-hardware.org/?probe=e14f742bb9) | Jan 12, 2022 |
| HP            | Pavilion g6                 | [62f049acf1](https://linux-hardware.org/?probe=62f049acf1) | Jan 12, 2022 |
| Apple         | MacBookPro8,1               | [a462f4b26f](https://linux-hardware.org/?probe=a462f4b26f) | Jan 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c781a61663](https://linux-hardware.org/?probe=c781a61663) | Jan 11, 2022 |
| Dell          | Precision 7550              | [0b72e489be](https://linux-hardware.org/?probe=0b72e489be) | Jan 10, 2022 |
| Dell          | Latitude E7440              | [9d89ac124e](https://linux-hardware.org/?probe=9d89ac124e) | Jan 08, 2022 |
| Acer          | Aspire A315-35              | [1e6abae11a](https://linux-hardware.org/?probe=1e6abae11a) | Jan 08, 2022 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [7ba01d7327](https://linux-hardware.org/?probe=7ba01d7327) | Jan 07, 2022 |
| Kogan         | KAL11C250SB                 | [a153354498](https://linux-hardware.org/?probe=a153354498) | Jan 07, 2022 |
| MSI           | GE62 2QD                    | [5f35b0b1ab](https://linux-hardware.org/?probe=5f35b0b1ab) | Jan 07, 2022 |
| Lenovo        | ThinkPad T560 20FJS4FV00    | [4bd9bb5f20](https://linux-hardware.org/?probe=4bd9bb5f20) | Jan 05, 2022 |
| HP            | EliteBook 8570p             | [f49baae9b5](https://linux-hardware.org/?probe=f49baae9b5) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [5496b24a51](https://linux-hardware.org/?probe=5496b24a51) | Jan 05, 2022 |
| Apple         | MacBookAir6,2               | [faaaf3cc89](https://linux-hardware.org/?probe=faaaf3cc89) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| Alienware     | m17                         | [13da9fa1b3](https://linux-hardware.org/?probe=13da9fa1b3) | Jan 02, 2022 |
| HP            | ENVY 17                     | [bd8db07a0a](https://linux-hardware.org/?probe=bd8db07a0a) | Jan 02, 2022 |
| Dell          | Inspiron 5770               | [0e81199f2c](https://linux-hardware.org/?probe=0e81199f2c) | Jan 02, 2022 |
| Apple         | MacBookPro11,5              | [1c88a2bad0](https://linux-hardware.org/?probe=1c88a2bad0) | Jan 02, 2022 |
| HP            | ENVY 17                     | [a140a1a272](https://linux-hardware.org/?probe=a140a1a272) | Jan 02, 2022 |
| Dell          | Latitude E5430 vPro         | [a073f421c1](https://linux-hardware.org/?probe=a073f421c1) | Jan 01, 2022 |
| Notebook      | P65xHP                      | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| Notebook      | P65xHP                      | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Apple         | MacBookPro9,2               | [601fb323dc](https://linux-hardware.org/?probe=601fb323dc) | Dec 30, 2021 |
| Dell          | Latitude E5420              | [dc28d41913](https://linux-hardware.org/?probe=dc28d41913) | Dec 30, 2021 |
| HP            | 250 G7 Notebook PC          | [9ee8c0f205](https://linux-hardware.org/?probe=9ee8c0f205) | Dec 29, 2021 |
| HP            | EliteBook 2760p             | [1cd129ee35](https://linux-hardware.org/?probe=1cd129ee35) | Dec 27, 2021 |
| HP            | EliteBook 2760p             | [f2deb9ec59](https://linux-hardware.org/?probe=f2deb9ec59) | Dec 27, 2021 |
| Dell          | Inspiron M5010              | [e576e17ed7](https://linux-hardware.org/?probe=e576e17ed7) | Dec 26, 2021 |
| Lenovo        | ThinkPad W530 2463B87       | [e82b5e9a8a](https://linux-hardware.org/?probe=e82b5e9a8a) | Dec 26, 2021 |
| Dell          | XPS 15 9550                 | [fc814dc489](https://linux-hardware.org/?probe=fc814dc489) | Dec 25, 2021 |
| LEADER        | NH5BT11                     | [763efa7eb2](https://linux-hardware.org/?probe=763efa7eb2) | Dec 25, 2021 |
| Toshiba       | Satellite C660              | [b13c6ceb2c](https://linux-hardware.org/?probe=b13c6ceb2c) | Dec 25, 2021 |
| HP            | EliteBook 2560p             | [4081d9b42b](https://linux-hardware.org/?probe=4081d9b42b) | Dec 24, 2021 |
| Acer          | Aspire 5740                 | [baf5d23f31](https://linux-hardware.org/?probe=baf5d23f31) | Dec 24, 2021 |
| Samsung       | 700T                        | [dcd96a051e](https://linux-hardware.org/?probe=dcd96a051e) | Dec 23, 2021 |
| Dell          | XPS 15 7590                 | [5cbe59259b](https://linux-hardware.org/?probe=5cbe59259b) | Dec 23, 2021 |
| Dell          | Latitude E6400              | [46422c0062](https://linux-hardware.org/?probe=46422c0062) | Dec 22, 2021 |
| Google        | Edgar                       | [dc1b8b8c81](https://linux-hardware.org/?probe=dc1b8b8c81) | Dec 20, 2021 |
| Google        | Edgar                       | [96597eb5fd](https://linux-hardware.org/?probe=96597eb5fd) | Dec 20, 2021 |
| Apple         | MacBookPro8,1               | [70ebf43f36](https://linux-hardware.org/?probe=70ebf43f36) | Dec 20, 2021 |
| Dell          | XPS 15 9500                 | [e5592dfde0](https://linux-hardware.org/?probe=e5592dfde0) | Dec 20, 2021 |
| Toshiba       | Satellite C660              | [6f860db242](https://linux-hardware.org/?probe=6f860db242) | Dec 18, 2021 |
| Apple         | MacBookPro8,1               | [08df885431](https://linux-hardware.org/?probe=08df885431) | Dec 17, 2021 |
| Dell          | XPS 15 9500                 | [4d52a02213](https://linux-hardware.org/?probe=4d52a02213) | Dec 16, 2021 |
| Apple         | MacBookPro9,2               | [ef78b011ef](https://linux-hardware.org/?probe=ef78b011ef) | Dec 16, 2021 |
| Lenovo        | ThinkPad W540 20BG0011US    | [ead3a18508](https://linux-hardware.org/?probe=ead3a18508) | Dec 15, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [ba92d0772e](https://linux-hardware.org/?probe=ba92d0772e) | Dec 14, 2021 |
| MSI           | PS42 Modern 8RC             | [2686d73cb8](https://linux-hardware.org/?probe=2686d73cb8) | Dec 13, 2021 |
| Lenovo        | ThinkPad T440 20B7S02A00    | [5b3ec8682e](https://linux-hardware.org/?probe=5b3ec8682e) | Dec 13, 2021 |
| Acer          | Aspire 5600                 | [25b1e50c64](https://linux-hardware.org/?probe=25b1e50c64) | Dec 12, 2021 |
| Acer          | ConceptD CN315-71P          | [ac834a5768](https://linux-hardware.org/?probe=ac834a5768) | Dec 11, 2021 |
| Dell          | Latitude 7370               | [d2bbf57105](https://linux-hardware.org/?probe=d2bbf57105) | Dec 11, 2021 |
| HP            | ProBook 470 G5              | [3a17215293](https://linux-hardware.org/?probe=3a17215293) | Dec 11, 2021 |
| HP            | ProBook 470 G5              | [36e4d31312](https://linux-hardware.org/?probe=36e4d31312) | Dec 10, 2021 |
| HP            | Pavilion g6                 | [a50dca2bf2](https://linux-hardware.org/?probe=a50dca2bf2) | Dec 10, 2021 |
| ASUSTek       | X550JX                      | [818c536fda](https://linux-hardware.org/?probe=818c536fda) | Dec 10, 2021 |
| HP            | 250 G6 Notebook PC          | [3b955f362a](https://linux-hardware.org/?probe=3b955f362a) | Dec 10, 2021 |
| HP            | ZBook 14u G5                | [21df45023e](https://linux-hardware.org/?probe=21df45023e) | Dec 09, 2021 |
| HP            | ZBook 14u G5                | [b01068d8cc](https://linux-hardware.org/?probe=b01068d8cc) | Dec 09, 2021 |
| Apple         | MacBookPro14,3              | [6e7dbbfd7a](https://linux-hardware.org/?probe=6e7dbbfd7a) | Dec 08, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6f3bd18b3f](https://linux-hardware.org/?probe=6f3bd18b3f) | Dec 06, 2021 |
| MSI           | GE62 2QD                    | [f37c114570](https://linux-hardware.org/?probe=f37c114570) | Dec 05, 2021 |
| HUAWEI        | HN-WX9X                     | [a4266720ec](https://linux-hardware.org/?probe=a4266720ec) | Dec 05, 2021 |
| Lenovo        | Legion Y7000 2019 81NS      | [fbe30211c6](https://linux-hardware.org/?probe=fbe30211c6) | Dec 05, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [ee5c6147f7](https://linux-hardware.org/?probe=ee5c6147f7) | Dec 04, 2021 |
| Toshiba       | Satellite C660              | [47b40007ee](https://linux-hardware.org/?probe=47b40007ee) | Dec 04, 2021 |
| Toshiba       | Satellite C660              | [4d64247a8a](https://linux-hardware.org/?probe=4d64247a8a) | Dec 04, 2021 |
| Acer          | Aspire R3-131T              | [3fd499b264](https://linux-hardware.org/?probe=3fd499b264) | Dec 04, 2021 |
| Gigabyte      | AERO 15 KB                  | [a7d3041cd2](https://linux-hardware.org/?probe=a7d3041cd2) | Dec 03, 2021 |
| Panasonic     | CF-19RDRAMGA                | [5aaebfbf19](https://linux-hardware.org/?probe=5aaebfbf19) | Nov 29, 2021 |
| Toshiba       | Satellite C660              | [2799629c61](https://linux-hardware.org/?probe=2799629c61) | Nov 28, 2021 |
| Toshiba       | Satellite C660              | [1e80d1c181](https://linux-hardware.org/?probe=1e80d1c181) | Nov 28, 2021 |
| Apple         | MacBook7,1                  | [22e54de439](https://linux-hardware.org/?probe=22e54de439) | Nov 27, 2021 |
| HP            | Pavilion Notebook           | [092ae35663](https://linux-hardware.org/?probe=092ae35663) | Nov 27, 2021 |
| Apple         | MacBookPro8,1               | [a0b9aec393](https://linux-hardware.org/?probe=a0b9aec393) | Nov 26, 2021 |
| Apple         | MacBookPro8,1               | [62a1aeadc4](https://linux-hardware.org/?probe=62a1aeadc4) | Nov 26, 2021 |
| ASUSTek       | Unknown                     | [1627a50b96](https://linux-hardware.org/?probe=1627a50b96) | Nov 25, 2021 |
| Toshiba       | Satellite L640              | [0a00178792](https://linux-hardware.org/?probe=0a00178792) | Nov 25, 2021 |
| Toshiba       | Satellite P50t-A            | [33add9e294](https://linux-hardware.org/?probe=33add9e294) | Nov 25, 2021 |
| Apple         | MacBookPro9,2               | [ab60997b9e](https://linux-hardware.org/?probe=ab60997b9e) | Nov 24, 2021 |
| LG Electro... | 14Z960-GR3HK                | [7dd0d53cef](https://linux-hardware.org/?probe=7dd0d53cef) | Nov 24, 2021 |
| HP            | Pavilion g6                 | [f7da6c6d2d](https://linux-hardware.org/?probe=f7da6c6d2d) | Nov 23, 2021 |
| Dell          | G5 5590                     | [3a149ffc5e](https://linux-hardware.org/?probe=3a149ffc5e) | Nov 23, 2021 |
| Apple         | MacBookPro16,1              | [9d02768642](https://linux-hardware.org/?probe=9d02768642) | Nov 23, 2021 |
| MSI           | Creator Z16 Hiroshi F A1... | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| Lenovo        | Legion Y7000 2019 81NS      | [19ce916e45](https://linux-hardware.org/?probe=19ce916e45) | Nov 22, 2021 |
| Dell          | Latitude 3400               | [62dd7a6ea2](https://linux-hardware.org/?probe=62dd7a6ea2) | Nov 21, 2021 |
| Lenovo        | G50-45 80E3                 | [024686087f](https://linux-hardware.org/?probe=024686087f) | Nov 20, 2021 |
| Acer          | Aspire 5560                 | [5725ae4593](https://linux-hardware.org/?probe=5725ae4593) | Nov 20, 2021 |
| AFTERSHOCK... | VAPOR 15X                   | [6433612bed](https://linux-hardware.org/?probe=6433612bed) | Nov 18, 2021 |
| ASUSTek       | K50IJ                       | [9e28f131eb](https://linux-hardware.org/?probe=9e28f131eb) | Nov 18, 2021 |
| Dell          | Inspiron 7586               | [188923fc9c](https://linux-hardware.org/?probe=188923fc9c) | Nov 17, 2021 |
| Toshiba       | Satellite L50-B             | [867287fb63](https://linux-hardware.org/?probe=867287fb63) | Nov 16, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [d8acfef1ef](https://linux-hardware.org/?probe=d8acfef1ef) | Nov 16, 2021 |
| Dell          | Inspiron 7566               | [b868de3306](https://linux-hardware.org/?probe=b868de3306) | Nov 16, 2021 |
| Lenovo        | V110-15IAP 80TG             | [c6aebae4da](https://linux-hardware.org/?probe=c6aebae4da) | Nov 16, 2021 |
| HP            | Pavilion dv5                | [ec4890a33b](https://linux-hardware.org/?probe=ec4890a33b) | Nov 15, 2021 |
| HP            | Pavilion dv5                | [4ddaeca48c](https://linux-hardware.org/?probe=4ddaeca48c) | Nov 15, 2021 |
| LG Electro... | 16Z90P-G.AA75A              | [d15e199bb4](https://linux-hardware.org/?probe=d15e199bb4) | Nov 14, 2021 |
| Apple         | MacBookPro8,1               | [ea402fa75e](https://linux-hardware.org/?probe=ea402fa75e) | Nov 14, 2021 |
| HP            | Pavilion 15                 | [6b4486db02](https://linux-hardware.org/?probe=6b4486db02) | Nov 13, 2021 |
| HP            | Pavilion 15                 | [d0e343d3b7](https://linux-hardware.org/?probe=d0e343d3b7) | Nov 13, 2021 |
| ASUSTek       | K55A                        | [60377bce60](https://linux-hardware.org/?probe=60377bce60) | Nov 13, 2021 |
| HP            | Pavilion dv6                | [30c1df8961](https://linux-hardware.org/?probe=30c1df8961) | Nov 13, 2021 |
| Apple         | MacBook7,1                  | [b898d5a09c](https://linux-hardware.org/?probe=b898d5a09c) | Nov 13, 2021 |
| Toshiba       | Satellite Pro L50-A         | [36bc6d2ebd](https://linux-hardware.org/?probe=36bc6d2ebd) | Nov 12, 2021 |
| Acer          | Aspire 5720Z                | [ba74c7653a](https://linux-hardware.org/?probe=ba74c7653a) | Nov 12, 2021 |
| Acer          | Aspire 5720Z                | [d11d9b16b0](https://linux-hardware.org/?probe=d11d9b16b0) | Nov 12, 2021 |
| COM1          | NBINF-O5-4R5G5              | [b8a99864aa](https://linux-hardware.org/?probe=b8a99864aa) | Nov 12, 2021 |
| Acer          | Aspire 3000                 | [86d2f89f59](https://linux-hardware.org/?probe=86d2f89f59) | Nov 12, 2021 |
| Acer          | Aspire 3000                 | [dad287d5a1](https://linux-hardware.org/?probe=dad287d5a1) | Nov 11, 2021 |
| Apple         | MacBookAir6,1               | [588c351d40](https://linux-hardware.org/?probe=588c351d40) | Nov 10, 2021 |
| LG Electro... | 14Z90P-G.AR53A              | [a1fb8771db](https://linux-hardware.org/?probe=a1fb8771db) | Nov 10, 2021 |
| COM1          | NBINF-O5-4R5G5              | [e1cd2bd1cc](https://linux-hardware.org/?probe=e1cd2bd1cc) | Nov 10, 2021 |
| Apple         | MacBookPro8,1               | [d499b22b03](https://linux-hardware.org/?probe=d499b22b03) | Nov 09, 2021 |
| Toshiba       | Satellite Pro L50-A         | [6212422e34](https://linux-hardware.org/?probe=6212422e34) | Nov 09, 2021 |
| Unknown       | D15D                        | [5b15ae8ff3](https://linux-hardware.org/?probe=5b15ae8ff3) | Nov 07, 2021 |
| AFTERSHOCK... | VAPOR 15X                   | [cc21cf13c8](https://linux-hardware.org/?probe=cc21cf13c8) | Nov 07, 2021 |
| Samsung       | RF511/RF411/RF711           | [899657b967](https://linux-hardware.org/?probe=899657b967) | Nov 07, 2021 |
| HP            | Pavilion dv6                | [bd084f3ccd](https://linux-hardware.org/?probe=bd084f3ccd) | Nov 07, 2021 |
| Acer          | Aspire ES1-521              | [5ef4af5924](https://linux-hardware.org/?probe=5ef4af5924) | Nov 06, 2021 |
| MSI           | GT72 2QD                    | [d558e0270e](https://linux-hardware.org/?probe=d558e0270e) | Nov 06, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [e2180a6c85](https://linux-hardware.org/?probe=e2180a6c85) | Nov 04, 2021 |
| HP            | Pavilion g6                 | [c289308c14](https://linux-hardware.org/?probe=c289308c14) | Nov 04, 2021 |
| ASUSTek       | BU403UA                     | [acb1038124](https://linux-hardware.org/?probe=acb1038124) | Nov 03, 2021 |
| HP            | EliteBook 840 G3            | [a2ddc44da4](https://linux-hardware.org/?probe=a2ddc44da4) | Nov 02, 2021 |
| Toshiba       | Satellite L750D             | [143e009499](https://linux-hardware.org/?probe=143e009499) | Nov 02, 2021 |
| Toshiba       | Satellite P500              | [e69f994b81](https://linux-hardware.org/?probe=e69f994b81) | Nov 02, 2021 |
| MSI           | GT72VR 6RE                  | [4e8a3e6a15](https://linux-hardware.org/?probe=4e8a3e6a15) | Nov 01, 2021 |
| MSI           | GT72VR 6RE                  | [343f246595](https://linux-hardware.org/?probe=343f246595) | Nov 01, 2021 |
| COM1          | NBINF-O5-4R5G5              | [a3b154116b](https://linux-hardware.org/?probe=a3b154116b) | Oct 31, 2021 |
| Lenovo        | ThinkPad R400 7439CTO       | [9a7be426f5](https://linux-hardware.org/?probe=9a7be426f5) | Oct 30, 2021 |
| Toshiba       | Satellite Pro L50-A         | [a817ed896e](https://linux-hardware.org/?probe=a817ed896e) | Oct 29, 2021 |
| Toshiba       | Satellite Pro L50-A         | [5c23460bb8](https://linux-hardware.org/?probe=5c23460bb8) | Oct 27, 2021 |
| Acer          | Aspire 5600                 | [7e2da6d3e9](https://linux-hardware.org/?probe=7e2da6d3e9) | Oct 26, 2021 |
| HP            | Laptop 15s-du1xxx           | [23c770232c](https://linux-hardware.org/?probe=23c770232c) | Oct 25, 2021 |
| Dell          | Inspiron 3505               | [fe09832e42](https://linux-hardware.org/?probe=fe09832e42) | Oct 25, 2021 |
| Toshiba       | Satellite L850              | [066f99ecbc](https://linux-hardware.org/?probe=066f99ecbc) | Oct 25, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | [98720c7a44](https://linux-hardware.org/?probe=98720c7a44) | Oct 24, 2021 |
| Acer          | Aspire ES1-521              | [248ab157b8](https://linux-hardware.org/?probe=248ab157b8) | Oct 23, 2021 |
| HP            | 250 G3                      | [820dcd95a7](https://linux-hardware.org/?probe=820dcd95a7) | Oct 23, 2021 |
| Dell          | Latitude E7450              | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| HP            | Stream Laptop               | [95df1a4e45](https://linux-hardware.org/?probe=95df1a4e45) | Oct 22, 2021 |
| IT Channel... | PCX0DX                      | [fb1bf80085](https://linux-hardware.org/?probe=fb1bf80085) | Oct 22, 2021 |
| Lenovo        | ThinkPad E490s 20NGA000A... | [c2a180845c](https://linux-hardware.org/?probe=c2a180845c) | Oct 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [463b15301d](https://linux-hardware.org/?probe=463b15301d) | Oct 21, 2021 |
| Notebook      | W840SN Series               | [4baeb2cafc](https://linux-hardware.org/?probe=4baeb2cafc) | Oct 20, 2021 |
| Apple         | MacBookPro8,1               | [e72b8e6ba0](https://linux-hardware.org/?probe=e72b8e6ba0) | Oct 20, 2021 |
| HP            | Pavilion Notebook           | [fe8dbfde1b](https://linux-hardware.org/?probe=fe8dbfde1b) | Oct 19, 2021 |
| Acer          | Aspire E5-571               | [aec49e7b35](https://linux-hardware.org/?probe=aec49e7b35) | Oct 19, 2021 |
| HP            | Pavilion Notebook           | [4b53959f48](https://linux-hardware.org/?probe=4b53959f48) | Oct 19, 2021 |
| MSI           | CX70 2QF                    | [f91a0f1380](https://linux-hardware.org/?probe=f91a0f1380) | Oct 19, 2021 |
| MSI           | CX70 2QF                    | [9d4c9ccf89](https://linux-hardware.org/?probe=9d4c9ccf89) | Oct 18, 2021 |
| ASUSTek       | X501A                       | [b3e4d8035d](https://linux-hardware.org/?probe=b3e4d8035d) | Oct 17, 2021 |
| Acer          | ConceptD CN315-71P          | [50385dde8b](https://linux-hardware.org/?probe=50385dde8b) | Oct 16, 2021 |
| Apple         | MacBookAir7,2               | [370b129f3f](https://linux-hardware.org/?probe=370b129f3f) | Oct 16, 2021 |
| Dell          | G7 7700                     | [273e51402c](https://linux-hardware.org/?probe=273e51402c) | Oct 15, 2021 |
| Alienware     | M17xR4                      | [98464fe67b](https://linux-hardware.org/?probe=98464fe67b) | Oct 15, 2021 |
| Alienware     | M17xR4                      | [ea79d2496d](https://linux-hardware.org/?probe=ea79d2496d) | Oct 15, 2021 |
| Lenovo        | ThinkPad T410 2522PT3       | [b2214c65d5](https://linux-hardware.org/?probe=b2214c65d5) | Oct 15, 2021 |
| Samsung       | RF511/RF411/RF711           | [ebd0874d7c](https://linux-hardware.org/?probe=ebd0874d7c) | Oct 13, 2021 |
| Samsung       | RF511/RF411/RF711           | [7a4ede4a67](https://linux-hardware.org/?probe=7a4ede4a67) | Oct 13, 2021 |
| HP            | Laptop 15s-du1xxx           | [6b3505b5f2](https://linux-hardware.org/?probe=6b3505b5f2) | Oct 13, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [471414140c](https://linux-hardware.org/?probe=471414140c) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e3a8d1ca32](https://linux-hardware.org/?probe=e3a8d1ca32) | Oct 11, 2021 |
| Dell          | Inspiron 3505               | [8628621ed3](https://linux-hardware.org/?probe=8628621ed3) | Oct 11, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c7c4a74bb8](https://linux-hardware.org/?probe=c7c4a74bb8) | Oct 11, 2021 |
| Lenovo        | ThinkPad T410 2522ED2       | [c8c010b75c](https://linux-hardware.org/?probe=c8c010b75c) | Oct 11, 2021 |
| Lenovo        | ThinkPad E15 20RD0011AU     | [85c8487ca5](https://linux-hardware.org/?probe=85c8487ca5) | Oct 11, 2021 |
| Toshiba       | Satellite L830              | [e8652672c3](https://linux-hardware.org/?probe=e8652672c3) | Oct 10, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [68865693c7](https://linux-hardware.org/?probe=68865693c7) | Oct 09, 2021 |
| Lenovo        | ThinkPad E14 20RA0020AU     | [f8efee6741](https://linux-hardware.org/?probe=f8efee6741) | Oct 09, 2021 |
| Dell          | Latitude 5400               | [77c9ee3548](https://linux-hardware.org/?probe=77c9ee3548) | Oct 07, 2021 |
| Dell          | Inspiron 7586               | [2ecf794b47](https://linux-hardware.org/?probe=2ecf794b47) | Oct 07, 2021 |
| Acer          | Aspire E5-571               | [8e65153ce2](https://linux-hardware.org/?probe=8e65153ce2) | Oct 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c86e0b677e](https://linux-hardware.org/?probe=c86e0b677e) | Oct 03, 2021 |
| Toshiba       | Satellite C55t-C            | [a6f33aa565](https://linux-hardware.org/?probe=a6f33aa565) | Oct 03, 2021 |
| Dell          | Latitude 5410               | [6928f4237f](https://linux-hardware.org/?probe=6928f4237f) | Oct 01, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [00b95678dd](https://linux-hardware.org/?probe=00b95678dd) | Sep 27, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [55c08d7759](https://linux-hardware.org/?probe=55c08d7759) | Sep 27, 2021 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [23dbed3ab1](https://linux-hardware.org/?probe=23dbed3ab1) | Sep 26, 2021 |
| Lenovo        | ThinkPad X61s 7667DE3       | [9d3daab4b3](https://linux-hardware.org/?probe=9d3daab4b3) | Sep 25, 2021 |
| Dell          | Inspiron 11-3168            | [4c7c72b321](https://linux-hardware.org/?probe=4c7c72b321) | Sep 25, 2021 |
| Kogan         | KAL11C250SB                 | [b76a44f6d5](https://linux-hardware.org/?probe=b76a44f6d5) | Sep 24, 2021 |
| Notebook      | W840SN Series               | [15f25a62a8](https://linux-hardware.org/?probe=15f25a62a8) | Sep 23, 2021 |
| Lenovo        | Mixx-700-12ISK 80QL         | [090e25b77c](https://linux-hardware.org/?probe=090e25b77c) | Sep 22, 2021 |
| Dell          | Precision 5560              | [c31c2d637b](https://linux-hardware.org/?probe=c31c2d637b) | Sep 21, 2021 |
| Dell          | Precision 5560              | [7b8db74bd5](https://linux-hardware.org/?probe=7b8db74bd5) | Sep 21, 2021 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3C... | [4698844ec0](https://linux-hardware.org/?probe=4698844ec0) | Sep 20, 2021 |
| Toshiba       | Satellite L20               | [654c60e971](https://linux-hardware.org/?probe=654c60e971) | Sep 20, 2021 |
| Acer          | Aspire 5600                 | [6d6b90c8e8](https://linux-hardware.org/?probe=6d6b90c8e8) | Sep 19, 2021 |
| ASUSTek       | U31F                        | [908a7184ae](https://linux-hardware.org/?probe=908a7184ae) | Sep 19, 2021 |
| ASUSTek       | U31F                        | [7cf4ac39de](https://linux-hardware.org/?probe=7cf4ac39de) | Sep 18, 2021 |
| Unknown       | Unknown                     | [f620b10ff0](https://linux-hardware.org/?probe=f620b10ff0) | Sep 14, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | [d238092077](https://linux-hardware.org/?probe=d238092077) | Sep 14, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | [68eacd0e30](https://linux-hardware.org/?probe=68eacd0e30) | Sep 13, 2021 |
| HP            | Pavilion dv6                | [b0e257ccca](https://linux-hardware.org/?probe=b0e257ccca) | Sep 13, 2021 |
| Acer          | Aspire R3-131T              | [e872ba288e](https://linux-hardware.org/?probe=e872ba288e) | Sep 12, 2021 |
| ASUSTek       | N750JV                      | [e24cb69cc0](https://linux-hardware.org/?probe=e24cb69cc0) | Sep 11, 2021 |
| Metabox       | Alpha-X NH77DC              | [0b6122c2ce](https://linux-hardware.org/?probe=0b6122c2ce) | Sep 10, 2021 |
| Metabox       | Alpha-X NH77DC              | [98364c4883](https://linux-hardware.org/?probe=98364c4883) | Sep 10, 2021 |
| Dell          | XPS 13 9370                 | [db0606cb42](https://linux-hardware.org/?probe=db0606cb42) | Sep 10, 2021 |
| Dell          | XPS 15 9560                 | [b33af6d329](https://linux-hardware.org/?probe=b33af6d329) | Sep 10, 2021 |
| Lenovo        | ThinkPad R400 7439CTO       | [5b2fb97960](https://linux-hardware.org/?probe=5b2fb97960) | Sep 10, 2021 |
| Alienware     | 17                          | [49c757651f](https://linux-hardware.org/?probe=49c757651f) | Sep 09, 2021 |
| Apple         | MacBookPro8,1               | [5be67e3cb8](https://linux-hardware.org/?probe=5be67e3cb8) | Sep 07, 2021 |
| Dell          | Latitude E6430s             | [0995d2317b](https://linux-hardware.org/?probe=0995d2317b) | Sep 06, 2021 |
| Timi          | TM1613                      | [530a9daa43](https://linux-hardware.org/?probe=530a9daa43) | Sep 06, 2021 |
| Toshiba       | Satellite P750              | [ee2674ad2e](https://linux-hardware.org/?probe=ee2674ad2e) | Sep 06, 2021 |
| Dell          | Latitude E5430 non-vPro     | [e26b6d083b](https://linux-hardware.org/?probe=e26b6d083b) | Sep 06, 2021 |
| Dell          | Latitude E5430 non-vPro     | [f4d430c0f9](https://linux-hardware.org/?probe=f4d430c0f9) | Sep 06, 2021 |
| Apple         | MacBookPro8,1               | [a865b060fa](https://linux-hardware.org/?probe=a865b060fa) | Sep 06, 2021 |
| Metabox       | NP50DE                      | [355939bc8d](https://linux-hardware.org/?probe=355939bc8d) | Sep 05, 2021 |
| ASUSTek       | K72F                        | [718b264baf](https://linux-hardware.org/?probe=718b264baf) | Sep 05, 2021 |
| ASUSTek       | K72F                        | [68b6deb2e1](https://linux-hardware.org/?probe=68b6deb2e1) | Sep 05, 2021 |
| Toshiba       | Satellite L50-B             | [e8f5eb9453](https://linux-hardware.org/?probe=e8f5eb9453) | Sep 04, 2021 |
| HP            | Presario CQ62               | [4cdec89015](https://linux-hardware.org/?probe=4cdec89015) | Sep 04, 2021 |
| Metabox       | Alpha-S NP70HJ              | [7b477b4fae](https://linux-hardware.org/?probe=7b477b4fae) | Sep 04, 2021 |
| Metabox       | Alpha-S NP70HJ              | [a72cca0cf9](https://linux-hardware.org/?probe=a72cca0cf9) | Sep 04, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Australia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 197       | 13.48%  |
| Ubuntu 18.04       | 82        | 5.61%   |
| Ubuntu 22.04       | 47        | 3.22%   |
| Pop!_OS 22.04      | 37        | 2.53%   |
| Debian 11          | 32        | 2.19%   |
| KDE neon 20.04     | 30        | 2.05%   |
| Fedora 36          | 29        | 1.98%   |
| Linux Mint 20.2    | 28        | 1.92%   |
| Zorin 16           | 27        | 1.85%   |
| Pop!_OS 21.04      | 27        | 1.85%   |
| Arch Rolling       | 26        | 1.78%   |
| Pop!_OS 20.04      | 25        | 1.71%   |
| OpenMandriva 4.3   | 25        | 1.71%   |
| Linux Mint 20.3    | 25        | 1.71%   |
| Arch               | 24        | 1.64%   |
| Linux Mint 20      | 22        | 1.51%   |
| Fedora 37          | 22        | 1.51%   |
| Ubuntu 20.10       | 21        | 1.44%   |
| OpenMandriva 4.2   | 20        | 1.37%   |
| Pop!_OS 20.10      | 19        | 1.3%    |
| Linux Mint 20.1    | 19        | 1.3%    |
| Ubuntu 21.10       | 18        | 1.23%   |
| Ubuntu 19.04       | 18        | 1.23%   |
| Manjaro            | 18        | 1.23%   |
| Ubuntu 19.10       | 17        | 1.16%   |
| Fedora 33          | 16        | 1.1%    |
| Zorin 15           | 15        | 1.03%   |
| ArcoLinux Rolling  | 15        | 1.03%   |
| Ubuntu 21.04       | 14        | 0.96%   |
| Fedora 35          | 14        | 0.96%   |
| Xubuntu 18.04      | 13        | 0.89%   |
| Ubuntu 22.10       | 13        | 0.89%   |
| Linux Mint 21.1    | 13        | 0.89%   |
| Linux Mint 21      | 12        | 0.82%   |
| Fedora 32          | 12        | 0.82%   |
| OpenMandriva 23.01 | 11        | 0.75%   |
| Xubuntu 20.04      | 10        | 0.68%   |
| OpenMandriva 23.03 | 10        | 0.68%   |
| Linux Mint 19.3    | 9         | 0.62%   |
| Kubuntu 20.04      | 9         | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 415       | 30.38%  |
| Linux Mint    | 129       | 9.44%   |
| Pop!_OS       | 110       | 8.05%   |
| Fedora        | 96        | 7.03%   |
| OpenMandriva  | 77        | 5.64%   |
| Debian        | 50        | 3.66%   |
| Zorin         | 49        | 3.59%   |
| Arch          | 49        | 3.59%   |
| Manjaro       | 43        | 3.15%   |
| KDE neon      | 41        | 3%      |
| Xubuntu       | 35        | 2.56%   |
| Kubuntu       | 29        | 2.12%   |
| Elementary    | 23        | 1.68%   |
| Kali          | 18        | 1.32%   |
| Gentoo        | 17        | 1.24%   |
| ArcoLinux     | 15        | 1.1%    |
| Clear Linux   | 13        | 0.95%   |
| Lubuntu       | 11        | 0.81%   |
| Endless       | 11        | 0.81%   |
| Ubuntu Unity  | 10        | 0.73%   |
| ROSA          | 10        | 0.73%   |
| openSUSE      | 10        | 0.73%   |
| EndeavourOS   | 9         | 0.66%   |
| Ubuntu MATE   | 8         | 0.59%   |
| LMDE          | 8         | 0.59%   |
| Parrot        | 7         | 0.51%   |
| SteamOS       | 6         | 0.44%   |
| MX            | 6         | 0.44%   |
| LinuxFX       | 6         | 0.44%   |
| BlackPanther  | 5         | 0.37%   |
| Reborn OS     | 4         | 0.29%   |
| Ubuntu Budgie | 3         | 0.22%   |
| Solus         | 3         | 0.22%   |
| Xero          | 2         | 0.15%   |
| Void Linux    | 2         | 0.15%   |
| RHEL          | 2         | 0.15%   |
| PureOS        | 2         | 0.15%   |
| Oracle Linux  | 2         | 0.15%   |
| Nobara        | 2         | 0.15%   |
| Linux Lite    | 2         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 33        | 2.03%   |
| 5.16.7-desktop-1omv4003  | 24        | 1.48%   |
| 5.10.14-desktop-1omv4002 | 20        | 1.23%   |
| 5.4.0-58-generic         | 18        | 1.11%   |
| 5.4.0-26-generic         | 15        | 0.92%   |
| 5.4.0-40-generic         | 14        | 0.86%   |
| 5.15.0-56-generic        | 14        | 0.86%   |
| 5.11.0-7620-generic      | 14        | 0.86%   |
| 5.4.0-29-generic         | 13        | 0.8%    |
| 5.4.0-48-generic         | 12        | 0.74%   |
| 5.11.0-38-generic        | 12        | 0.74%   |
| 5.17.5-76051705-generic  | 11        | 0.68%   |
| 5.15.0-58-generic        | 11        | 0.68%   |
| 5.11.0-37-generic        | 11        | 0.68%   |
| 5.11.0-27-generic        | 11        | 0.68%   |
| 6.2.6-desktop-1omv2390   | 10        | 0.61%   |
| 6.1.1-desktop-1omv2290   | 10        | 0.61%   |
| 5.4.0-52-generic         | 10        | 0.61%   |
| 5.8.0-63-generic         | 9         | 0.55%   |
| 5.4.0-81-generic         | 9         | 0.55%   |
| 5.4.0-74-generic         | 9         | 0.55%   |
| 5.3.0-40-generic         | 9         | 0.55%   |
| 5.8.0-7630-generic       | 8         | 0.49%   |
| 5.8.0-59-generic         | 8         | 0.49%   |
| 5.4.0-7634-generic       | 8         | 0.49%   |
| 5.4.0-65-generic         | 8         | 0.49%   |
| 5.4.0-54-generic         | 8         | 0.49%   |
| 5.3.0-28-generic         | 8         | 0.49%   |
| 5.15.0-52-generic        | 8         | 0.49%   |
| 5.15.0-46-generic        | 8         | 0.49%   |
| 5.13.0-7620-generic      | 8         | 0.49%   |
| 5.13.0-40-generic        | 8         | 0.49%   |
| 5.11.0-40-generic        | 8         | 0.49%   |
| 5.0.0-13-generic         | 8         | 0.49%   |
| 5.8.0-7642-generic       | 7         | 0.43%   |
| 5.8.0-53-generic         | 7         | 0.43%   |
| 5.8.0-50-generic         | 7         | 0.43%   |
| 5.4.0-91-generic         | 7         | 0.43%   |
| 5.4.0-7642-generic       | 7         | 0.43%   |
| 5.4.0-47-generic         | 7         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 264       | 17.52%  |
| 5.15.0  | 105       | 6.97%   |
| 5.11.0  | 101       | 6.7%    |
| 5.8.0   | 84        | 5.57%   |
| 5.13.0  | 83        | 5.51%   |
| 4.15.0  | 69        | 4.58%   |
| 5.3.0   | 52        | 3.45%   |
| 5.10.0  | 44        | 2.92%   |
| 5.0.0   | 41        | 2.72%   |
| 5.19.0  | 40        | 2.65%   |
| 4.18.0  | 30        | 1.99%   |
| 5.16.7  | 25        | 1.66%   |
| 5.10.14 | 20        | 1.33%   |
| 5.17.5  | 17        | 1.13%   |
| 6.1.1   | 14        | 0.93%   |
| 6.2.6   | 12        | 0.8%    |
| 6.0.0   | 11        | 0.73%   |
| 4.19.0  | 11        | 0.73%   |
| 6.0.12  | 9         | 0.6%    |
| 5.18.0  | 9         | 0.6%    |
| 5.18.10 | 8         | 0.53%   |
| 5.14.0  | 7         | 0.46%   |
| 6.2.0   | 6         | 0.4%    |
| 6.0.9   | 6         | 0.4%    |
| 6.0.7   | 6         | 0.4%    |
| 5.18.12 | 6         | 0.4%    |
| 5.17.15 | 6         | 0.4%    |
| 5.8.16  | 5         | 0.33%   |
| 5.16.11 | 5         | 0.33%   |
| 5.16.0  | 5         | 0.33%   |
| 5.12.4  | 5         | 0.33%   |
| 4.9.60  | 5         | 0.33%   |
| 4.4.0   | 5         | 0.33%   |
| 6.1.11  | 4         | 0.27%   |
| 6.1.0   | 4         | 0.27%   |
| 6.0.6   | 4         | 0.27%   |
| 5.9.16  | 4         | 0.27%   |
| 5.18.7  | 4         | 0.27%   |
| 5.16.2  | 4         | 0.27%   |
| 5.16.19 | 4         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 287       | 19.39%  |
| 5.15    | 141       | 9.53%   |
| 5.11    | 115       | 7.77%   |
| 5.8     | 101       | 6.82%   |
| 5.13    | 97        | 6.55%   |
| 5.10    | 88        | 5.95%   |
| 4.15    | 69        | 4.66%   |
| 5.16    | 58        | 3.92%   |
| 5.19    | 57        | 3.85%   |
| 5.3     | 56        | 3.78%   |
| 6.0     | 47        | 3.18%   |
| 5.0     | 45        | 3.04%   |
| 6.1     | 41        | 2.77%   |
| 5.17    | 38        | 2.57%   |
| 5.18    | 36        | 2.43%   |
| 4.18    | 35        | 2.36%   |
| 6.2     | 29        | 1.96%   |
| 5.6     | 18        | 1.22%   |
| 5.9     | 17        | 1.15%   |
| 5.14    | 17        | 1.15%   |
| 5.12    | 15        | 1.01%   |
| 4.19    | 14        | 0.95%   |
| 5.5     | 12        | 0.81%   |
| 5.7     | 11        | 0.74%   |
| 4.9     | 11        | 0.74%   |
| 5.2     | 5         | 0.34%   |
| 4.4     | 5         | 0.34%   |
| 4.1     | 3         | 0.2%    |
| 5.1     | 2         | 0.14%   |
| 4.20    | 2         | 0.14%   |
| 3.16    | 2         | 0.14%   |
| 3.10    | 2         | 0.14%   |
| 4.8     | 1         | 0.07%   |
| 4.14    | 1         | 0.07%   |
| 4.13    | 1         | 0.07%   |
| 4.11    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1250      | 97.35%  |
| i686    | 30        | 2.34%   |
| i586    | 2         | 0.16%   |
| aarch64 | 2         | 0.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 611       | 44.47%  |
| KDE5            | 216       | 15.72%  |
| Unknown         | 147       | 10.7%   |
| X-Cinnamon      | 113       | 8.22%   |
| XFCE            | 99        | 7.21%   |
| KDE             | 32        | 2.33%   |
| MATE            | 31        | 2.26%   |
| Cinnamon        | 22        | 1.6%    |
| Pantheon        | 21        | 1.53%   |
| i3              | 13        | 0.95%   |
| Unity           | 12        | 0.87%   |
| LXQt            | 10        | 0.73%   |
| LXDE            | 9         | 0.66%   |
| KDE4            | 8         | 0.58%   |
| Deepin          | 6         | 0.44%   |
| Budgie          | 6         | 0.44%   |
| BunsenLabs      | 3         | 0.22%   |
| awesome         | 3         | 0.22%   |
| Openbox         | 2         | 0.15%   |
| GNOME Flashback | 2         | 0.15%   |
| sway            | 1         | 0.07%   |
| qtile           | 1         | 0.07%   |
| LeftWM          | 1         | 0.07%   |
| icewm           | 1         | 0.07%   |
| Hyprland        | 1         | 0.07%   |
| herbstluftwm    | 1         | 0.07%   |
| dwm             | 1         | 0.07%   |
| dusk            | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1036      | 77.6%   |
| Wayland | 190       | 14.23%  |
| Unknown | 81        | 6.07%   |
| Tty     | 28        | 2.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 718       | 53.3%   |
| SDDM    | 177       | 13.14%  |
| GDM     | 165       | 12.25%  |
| LightDM | 125       | 9.28%   |
| GDM3    | 109       | 8.09%   |
| TDM     | 39        | 2.9%    |
| KDM     | 8         | 0.59%   |
| SLiM    | 2         | 0.15%   |
| LXDM    | 2         | 0.15%   |
| XDM     | 1         | 0.07%   |
| GREETD  | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| en_AU        | 943       | 70.64%  |
| en_US        | 199       | 14.91%  |
| Unknown      | 132       | 9.89%   |
| C            | 31        | 2.32%   |
| en_GB        | 16        | 1.2%    |
| C.UTF8       | 4         | 0.3%    |
| zh_CN        | 1         | 0.07%   |
| ru_RU        | 1         | 0.07%   |
| it_IT        | 1         | 0.07%   |
| fr_FR        | 1         | 0.07%   |
| es_ES        | 1         | 0.07%   |
| en_IN        | 1         | 0.07%   |
| en_GB.UTF-12 | 1         | 0.07%   |
| en_CA        | 1         | 0.07%   |
| en_AU.UFT-8  | 1         | 0.07%   |
| de_DE        | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 676       | 51.21%  |
| BIOS | 644       | 48.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1023      | 77.27%  |
| Btrfs   | 121       | 9.14%   |
| Overlay | 92        | 6.95%   |
| Unknown | 39        | 2.95%   |
| Xfs     | 19        | 1.44%   |
| Zfs     | 13        | 0.98%   |
| Tmpfs   | 5         | 0.38%   |
| Ext2    | 5         | 0.38%   |
| XXXXXXX | 3         | 0.23%   |
| Ext3    | 3         | 0.23%   |
| F2fs    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 761       | 57.87%  |
| GPT     | 439       | 33.38%  |
| MBR     | 115       | 8.75%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1152      | 88.21%  |
| Yes       | 154       | 11.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1014      | 77.4%   |
| Yes       | 296       | 22.6%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 233       | 18.17%  |
| Dell                           | 226       | 17.63%  |
| Lenovo                         | 213       | 16.61%  |
| ASUSTek Computer               | 121       | 9.44%   |
| Acer                           | 115       | 8.97%   |
| Toshiba                        | 96        | 7.49%   |
| Apple                          | 87        | 6.79%   |
| MSI                            | 30        | 2.34%   |
| Alienware                      | 15        | 1.17%   |
| Samsung Electronics            | 13        | 1.01%   |
| Sony                           | 10        | 0.78%   |
| Notebook                       | 10        | 0.78%   |
| Gigabyte Technology            | 9         | 0.7%    |
| Timi                           | 8         | 0.62%   |
| Panasonic                      | 7         | 0.55%   |
| IT Channel Pty                 | 7         | 0.55%   |
| HUAWEI                         | 7         | 0.55%   |
| Razer                          | 6         | 0.47%   |
| Metabox                        | 6         | 0.47%   |
| Unknown                        | 6         | 0.47%   |
| Valve                          | 4         | 0.31%   |
| System76                       | 4         | 0.31%   |
| Intel Client Systems           | 4         | 0.31%   |
| Google                         | 4         | 0.31%   |
| AMI                            | 4         | 0.31%   |
| Medion                         | 3         | 0.23%   |
| LG Electronics                 | 3         | 0.23%   |
| Framework                      | 3         | 0.23%   |
| Purism                         | 2         | 0.16%   |
| Pine Microsystems              | 2         | 0.16%   |
| Kogan                          | 2         | 0.16%   |
| IBM                            | 2         | 0.16%   |
| Star Labs                      | 1         | 0.08%   |
| Pendo Industries               | 1         | 0.08%   |
| ONE-NETBOOK TECHNOLOGY         | 1         | 0.08%   |
| One Education                  | 1         | 0.08%   |
| OEM                            | 1         | 0.08%   |
| Matsushita Electric Industrial | 1         | 0.08%   |
| Maibenben                      | 1         | 0.08%   |
| LEADER                         | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HP Pavilion dv6                        | 16        | 1.25%   |
| HP Pavilion g6                         | 11        | 0.86%   |
| HP Notebook                            | 11        | 0.86%   |
| Unknown                                | 9         | 0.7%    |
| HP Pavilion 15                         | 8         | 0.62%   |
| Apple MacBookPro10,1                   | 8         | 0.62%   |
| Dell XPS 15 9570                       | 7         | 0.55%   |
| Apple MacBookPro9,2                    | 7         | 0.55%   |
| Apple MacBookAir7,2                    | 7         | 0.55%   |
| Apple MacBookPro8,1                    | 6         | 0.47%   |
| Acer ConceptD CN315-71P                | 6         | 0.47%   |
| Toshiba Satellite P750                 | 5         | 0.39%   |
| Toshiba Satellite L850                 | 5         | 0.39%   |
| Dell XPS 15 9560                       | 5         | 0.39%   |
| Dell XPS 13 9360                       | 5         | 0.39%   |
| Dell Latitude E7450                    | 5         | 0.39%   |
| Acer Aspire 5750G                      | 5         | 0.39%   |
| Valve Jupiter                          | 4         | 0.31%   |
| Toshiba Satellite L500                 | 4         | 0.31%   |
| Toshiba Satellite L50-A                | 4         | 0.31%   |
| Toshiba Satellite C660                 | 4         | 0.31%   |
| Lenovo ThinkPad T470s W10DG 20JTS0HT00 | 4         | 0.31%   |
| Lenovo IdeaPad 1 14IGL05 81VU          | 4         | 0.31%   |
| Lenovo G50-45 80E3                     | 4         | 0.31%   |
| HP Pavilion Notebook                   | 4         | 0.31%   |
| HP Laptop 15s-eq2xxx                   | 4         | 0.31%   |
| HP ENVY 17                             | 4         | 0.31%   |
| Dell XPS 15 9500                       | 4         | 0.31%   |
| Dell XPS 15 7590                       | 4         | 0.31%   |
| Dell XPS 13 9370                       | 4         | 0.31%   |
| Dell XPS 13 7390                       | 4         | 0.31%   |
| Dell Precision 5530                    | 4         | 0.31%   |
| Dell Latitude E7440                    | 4         | 0.31%   |
| Dell Latitude E6430                    | 4         | 0.31%   |
| Dell Inspiron 1545                     | 4         | 0.31%   |
| Apple MacBookAir6,2                    | 4         | 0.31%   |
| Acer Swift SF514-54T                   | 4         | 0.31%   |
| Acer Aspire One 753                    | 4         | 0.31%   |
| Toshiba Satellite P850                 | 3         | 0.23%   |
| Toshiba Satellite L750                 | 3         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 137       | 10.69%  |
| Acer Aspire        | 79        | 6.16%   |
| Toshiba Satellite  | 78        | 6.08%   |
| Dell Latitude      | 74        | 5.77%   |
| HP Pavilion        | 63        | 4.91%   |
| Dell Inspiron      | 54        | 4.21%   |
| Dell XPS           | 53        | 4.13%   |
| HP EliteBook       | 42        | 3.28%   |
| Lenovo IdeaPad     | 37        | 2.89%   |
| HP ProBook         | 30        | 2.34%   |
| HP Laptop          | 24        | 1.87%   |
| Dell Precision     | 21        | 1.64%   |
| HP ENVY            | 13        | 1.01%   |
| Lenovo Yoga        | 11        | 0.86%   |
| HP Notebook        | 11        | 0.86%   |
| ASUS ZenBook       | 11        | 0.86%   |
| ASUS VivoBook      | 11        | 0.86%   |
| Apple MacBookPro10 | 11        | 0.86%   |
| Acer Swift         | 11        | 0.86%   |
| ASUS ROG           | 9         | 0.7%    |
| Unknown            | 9         | 0.7%    |
| Toshiba PORTEGE    | 8         | 0.62%   |
| HP 250             | 8         | 0.62%   |
| Apple MacBookPro9  | 8         | 0.62%   |
| Toshiba TECRA      | 7         | 0.55%   |
| HP ZBook           | 7         | 0.55%   |
| HP Compaq          | 7         | 0.55%   |
| ASUS TUF           | 7         | 0.55%   |
| Apple MacBookAir7  | 7         | 0.55%   |
| Apple MacBookAir6  | 7         | 0.55%   |
| Razer Blade        | 6         | 0.47%   |
| Lenovo Legion      | 6         | 0.47%   |
| Dell G3            | 6         | 0.47%   |
| Apple MacBookPro8  | 6         | 0.47%   |
| Apple MacBookPro11 | 6         | 0.47%   |
| Acer Nitro         | 6         | 0.47%   |
| Acer ConceptD      | 6         | 0.47%   |
| HP Presario        | 5         | 0.39%   |
| HP OMEN            | 5         | 0.39%   |
| Dell Vostro        | 5         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 124       | 9.67%   |
| 2020    | 115       | 8.97%   |
| 2012    | 106       | 8.27%   |
| 2011    | 104       | 8.11%   |
| 2018    | 101       | 7.88%   |
| 2013    | 101       | 7.88%   |
| 2014    | 84        | 6.55%   |
| 2021    | 81        | 6.32%   |
| 2017    | 77        | 6.01%   |
| 2016    | 76        | 5.93%   |
| 2015    | 76        | 5.93%   |
| 2010    | 76        | 5.93%   |
| 2008    | 48        | 3.74%   |
| 2022    | 38        | 2.96%   |
| 2009    | 38        | 2.96%   |
| 2007    | 21        | 1.64%   |
| 2006    | 5         | 0.39%   |
| 2005    | 5         | 0.39%   |
| Unknown | 5         | 0.39%   |
| 2003    | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1282      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1150      | 88.8%   |
| Enabled  | 145       | 11.2%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1273      | 99.3%   |
| Yes  | 9         | 0.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 366       | 28.18%  |
| 16.01-24.0  | 276       | 21.25%  |
| 3.01-4.0    | 265       | 20.4%   |
| 8.01-16.0   | 192       | 14.78%  |
| 32.01-64.0  | 108       | 8.31%   |
| 1.01-2.0    | 50        | 3.85%   |
| 64.01-256.0 | 14        | 1.08%   |
| 2.01-3.0    | 11        | 0.85%   |
| 24.01-32.0  | 10        | 0.77%   |
| 0.51-1.0    | 4         | 0.31%   |
| 0.01-0.5    | 3         | 0.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 521       | 35.23%  |
| 2.01-3.0   | 411       | 27.79%  |
| 3.01-4.0   | 185       | 12.51%  |
| 4.01-8.0   | 184       | 12.44%  |
| 0.51-1.0   | 88        | 5.95%   |
| 8.01-16.0  | 67        | 4.53%   |
| 0.01-0.5   | 15        | 1.01%   |
| 16.01-24.0 | 4         | 0.27%   |
| 24.01-32.0 | 2         | 0.14%   |
| 0          | 2         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 934       | 70.07%  |
| 2      | 315       | 23.63%  |
| 3      | 54        | 4.05%   |
| 0      | 17        | 1.28%   |
| 4      | 10        | 0.75%   |
| 5      | 2         | 0.15%   |
| 7      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 815       | 63.03%  |
| Yes       | 478       | 36.97%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1049      | 81.63%  |
| No        | 236       | 18.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1260      | 98.13%  |
| No        | 24        | 1.87%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1011      | 77.53%  |
| No        | 293       | 22.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Australia | 1282      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sydney         | 354       | 25.82%  |
| Melbourne      | 286       | 20.86%  |
| Brisbane       | 218       | 15.9%   |
| Perth          | 104       | 7.59%   |
| Adelaide       | 76        | 5.54%   |
| Canberra       | 26        | 1.9%    |
| Hobart         | 18        | 1.31%   |
| Launceston     | 7         | 0.51%   |
| Central Coast  | 7         | 0.51%   |
| Southport      | 6         | 0.44%   |
| Newcastle      | 6         | 0.44%   |
| Woolloongabba  | 5         | 0.36%   |
| Parramatta     | 5         | 0.36%   |
| Mitcham        | 5         | 0.36%   |
| Gold Coast     | 5         | 0.36%   |
| Wollongong     | 4         | 0.29%   |
| West End       | 4         | 0.29%   |
| Wahroonga      | 4         | 0.29%   |
| Traralgon      | 4         | 0.29%   |
| Point Cook     | 4         | 0.29%   |
| Mandurah       | 4         | 0.29%   |
| Geraldton      | 4         | 0.29%   |
| Geelong        | 4         | 0.29%   |
| Artarmon       | 4         | 0.29%   |
| Alexandria     | 4         | 0.29%   |
| Townsville     | 3         | 0.22%   |
| Surry Hills    | 3         | 0.22%   |
| Spring Field   | 3         | 0.22%   |
| Richmond       | 3         | 0.22%   |
| Parkdale       | 3         | 0.22%   |
| Mount Waverley | 3         | 0.22%   |
| Hawthorn       | 3         | 0.22%   |
| Doncaster      | 3         | 0.22%   |
| Clifton Hill   | 3         | 0.22%   |
| Brighton       | 3         | 0.22%   |
| Ballarat       | 3         | 0.22%   |
| Warragul       | 2         | 0.15%   |
| Sunshine Coast | 2         | 0.15%   |
| Sandy Bay      | 2         | 0.15%   |
| Ryde           | 2         | 0.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 292       | 372    | 18.14%  |
| Seagate                   | 176       | 260    | 10.93%  |
| WDC                       | 172       | 246    | 10.68%  |
| Toshiba                   | 147       | 213    | 9.13%   |
| Unknown                   | 81        | 107    | 5.03%   |
| SanDisk                   | 75        | 98     | 4.66%   |
| Intel                     | 70        | 103    | 4.35%   |
| Kingston                  | 64        | 80     | 3.98%   |
| SK hynix                  | 63        | 82     | 3.91%   |
| Crucial                   | 59        | 77     | 3.66%   |
| Hitachi                   | 55        | 68     | 3.42%   |
| Apple                     | 53        | 71     | 3.29%   |
| HGST                      | 45        | 63     | 2.8%    |
| Micron Technology         | 41        | 53     | 2.55%   |
| KIOXIA                    | 20        | 22     | 1.24%   |
| Fujitsu                   | 14        | 18     | 0.87%   |
| Phison                    | 13        | 17     | 0.81%   |
| LITEON                    | 12        | 16     | 0.75%   |
| A-DATA Technology         | 11        | 14     | 0.68%   |
| Phison Electronics        | 9         | 13     | 0.56%   |
| LITEONIT                  | 8         | 10     | 0.5%    |
| SPCC                      | 6         | 8      | 0.37%   |
| OCZ                       | 6         | 8      | 0.37%   |
| Micron/Crucial Technology | 6         | 6      | 0.37%   |
| JMicron Technology        | 6         | 8      | 0.37%   |
| Transcend                 | 5         | 7      | 0.31%   |
| KingSpec                  | 5         | 8      | 0.31%   |
| ASMT                      | 5         | 7      | 0.31%   |
| Unknown                   | 5         | 6      | 0.31%   |
| Patriot                   | 4         | 6      | 0.25%   |
| China                     | 4         | 4      | 0.25%   |
| XPG                       | 3         | 3      | 0.19%   |
| OWC                       | 3         | 8      | 0.19%   |
| Lite-On                   | 3         | 3      | 0.19%   |
| LaCie                     | 3         | 7      | 0.19%   |
| Gigabyte Technology       | 3         | 6      | 0.19%   |
| USB                       | 2         | 3      | 0.12%   |
| TO Exter                  | 2         | 2      | 0.12%   |
| T-FORCE                   | 2         | 2      | 0.12%   |
| Solid State Storage       | 2         | 2      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                | 19        | 1.13%   |
| Toshiba MQ01ABD100 1TB                            | 18        | 1.07%   |
| Unknown MMC Card  64GB                            | 17        | 1.01%   |
| Seagate ST500LT012-1DG142 500GB                   | 14        | 0.83%   |
| Seagate Expansion 4TB                             | 14        | 0.83%   |
| SanDisk NVMe SSD Drive 512GB                      | 14        | 0.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 14        | 0.83%   |
| Toshiba MQ01ABF050 500GB                          | 13        | 0.78%   |
| Samsung SSD 860 EVO 500GB                         | 13        | 0.78%   |
| Samsung NVMe SSD Drive 512GB                      | 13        | 0.78%   |
| Seagate ST1000LM035-1RK172 970GB                  | 12        | 0.72%   |
| HGST HTS721010A9E630 1TB                          | 12        | 0.72%   |
| Unknown MMC Card  32GB                            | 11        | 0.66%   |
| Samsung NVMe SSD Drive 256GB                      | 10        | 0.6%    |
| Toshiba MQ01ABD075 752GB                          | 9         | 0.54%   |
| SK hynix NVMe SSD Drive 256GB                     | 9         | 0.54%   |
| Seagate ST2000LM007-1R8174 2TB                    | 9         | 0.54%   |
| Samsung SSD 850 EVO 250GB                         | 9         | 0.54%   |
| Kingston SA400S37240G 240GB SSD                   | 9         | 0.54%   |
| HGST HTS545050A7E680 500GB                        | 9         | 0.54%   |
| Crucial CT500MX500SSD1 500GB                      | 9         | 0.54%   |
| Crucial CT1000MX500SSD1 1TB                       | 9         | 0.54%   |
| Unknown MMC Card  128GB                           | 8         | 0.48%   |
| Toshiba NVMe SSD Drive 512GB                      | 8         | 0.48%   |
| Toshiba MQ04ABF100 1TB                            | 8         | 0.48%   |
| Seagate ST9500325AS 500GB                         | 8         | 0.48%   |
| SanDisk NVMe SSD Drive 256GB                      | 8         | 0.48%   |
| Samsung SSD 850 EVO 500GB                         | 8         | 0.48%   |
| Intel NVMe SSD Drive 512GB                        | 8         | 0.48%   |
| HGST HTS541010A9E680 1TB                          | 8         | 0.48%   |
| Crucial CT1000BX500SSD1 1TB                       | 8         | 0.48%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 7         | 0.42%   |
| Unknown SD/MMC/MS PRO 249GB                       | 7         | 0.42%   |
| Unknown MMC Card  16GB                            | 7         | 0.42%   |
| Samsung NVMe SSD Drive 500GB                      | 7         | 0.42%   |
| Micron NVMe SSD Drive 512GB                       | 7         | 0.42%   |
| Kingston SA400S37120G 120GB SSD                   | 7         | 0.42%   |
| Hitachi HTS547575A9E384 752GB                     | 7         | 0.42%   |
| Hitachi HTS545050B9A300 500GB                     | 7         | 0.42%   |
| HGST HTS725050A7E630 500GB                        | 7         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 171       | 253    | 31.73%  |
| WDC                 | 119       | 171    | 22.08%  |
| Toshiba             | 92        | 141    | 17.07%  |
| Hitachi             | 55        | 68     | 10.2%   |
| HGST                | 45        | 63     | 8.35%   |
| Fujitsu             | 14        | 18     | 2.6%    |
| Samsung Electronics | 12        | 14     | 2.23%   |
| Unknown             | 7         | 7      | 1.3%    |
| JMicron Technology  | 5         | 6      | 0.93%   |
| Apple               | 5         | 6      | 0.93%   |
| LaCie               | 3         | 6      | 0.56%   |
| ASMT                | 3         | 5      | 0.56%   |
| KESU                | 2         | 2      | 0.37%   |
| HGST HUS            | 2         | 2      | 0.37%   |
| USB                 | 1         | 2      | 0.19%   |
| T-CREATE            | 1         | 1      | 0.19%   |
| IBM/Hitachi         | 1         | 1      | 0.19%   |
| AAPL                | 1         | 1      | 0.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 148       | 185    | 28.96%  |
| Crucial             | 51        | 68     | 9.98%   |
| Kingston            | 43        | 55     | 8.41%   |
| SanDisk             | 41        | 50     | 8.02%   |
| Apple               | 36        | 41     | 7.05%   |
| WDC                 | 25        | 31     | 4.89%   |
| Intel               | 24        | 43     | 4.7%    |
| SK hynix            | 23        | 29     | 4.5%    |
| Toshiba             | 22        | 30     | 4.31%   |
| Micron Technology   | 14        | 14     | 2.74%   |
| LITEON              | 11        | 15     | 2.15%   |
| LITEONIT            | 8         | 10     | 1.57%   |
| SPCC                | 6         | 8      | 1.17%   |
| OCZ                 | 6         | 8      | 1.17%   |
| A-DATA Technology   | 6         | 8      | 1.17%   |
| Transcend           | 5         | 7      | 0.98%   |
| KingSpec            | 5         | 8      | 0.98%   |
| Patriot             | 4         | 6      | 0.78%   |
| China               | 4         | 4      | 0.78%   |
| Seagate             | 3         | 4      | 0.59%   |
| OWC                 | 3         | 8      | 0.59%   |
| TO Exter            | 2         | 2      | 0.39%   |
| Plextor             | 2         | 6      | 0.39%   |
| Gigabyte Technology | 2         | 2      | 0.39%   |
| FORESEE             | 2         | 2      | 0.39%   |
| External            | 2         | 2      | 0.39%   |
| SAMSWEET            | 1         | 1      | 0.2%    |
| Mushkin             | 1         | 1      | 0.2%    |
| Kston               | 1         | 1      | 0.2%    |
| Kingmax             | 1         | 1      | 0.2%    |
| KingFast            | 1         | 1      | 0.2%    |
| KingDian            | 1         | 1      | 0.2%    |
| Drevo               | 1         | 1      | 0.2%    |
| Corsair             | 1         | 1      | 0.2%    |
| Colorful            | 1         | 1      | 0.2%    |
| BP4e                | 1         | 2      | 0.2%    |
| BIWIN               | 1         | 1      | 0.2%    |
| ASMT                | 1         | 1      | 0.2%    |
| addlink             | 1         | 1      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 505       | 767    | 33.33%  |
| SSD     | 482       | 660    | 31.82%  |
| NVMe    | 428       | 618    | 28.25%  |
| MMC     | 76        | 100    | 5.02%   |
| Unknown | 24        | 26     | 1.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 869       | 1330   | 59.52%  |
| NVMe | 428       | 616    | 29.32%  |
| SAS  | 87        | 125    | 5.96%   |
| MMC  | 76        | 100    | 5.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 632       | 905    | 63.65%  |
| 0.51-1.0   | 279       | 395    | 28.1%   |
| 1.01-2.0   | 50        | 79     | 5.04%   |
| 3.01-4.0   | 22        | 32     | 2.22%   |
| 4.01-10.0  | 8         | 14     | 0.81%   |
| 10.01-20.0 | 2         | 2      | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 366       | 26.56%  |
| 251-500        | 331       | 24.02%  |
| 501-1000       | 223       | 16.18%  |
| 1-20           | 123       | 8.93%   |
| 51-100         | 99        | 7.18%   |
| 1001-2000      | 97        | 7.04%   |
| More than 3000 | 43        | 3.12%   |
| 21-50          | 36        | 2.61%   |
| Unknown        | 31        | 2.25%   |
| 2001-3000      | 29        | 2.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 610       | 41.75%  |
| 21-50          | 270       | 18.48%  |
| 51-100         | 164       | 11.23%  |
| 101-250        | 158       | 10.81%  |
| 251-500        | 113       | 7.73%   |
| 501-1000       | 62        | 4.24%   |
| Unknown        | 31        | 2.12%   |
| 1001-2000      | 28        | 1.92%   |
| 2001-3000      | 12        | 0.82%   |
| More than 3000 | 11        | 0.75%   |
| 0              | 2         | 0.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 4      | 4.05%   |
| HGST HTS545050A7E680 500GB              | 3         | 4      | 4.05%   |
| Toshiba MQ01ABF050 500GB                | 2         | 2      | 2.7%    |
| Toshiba MQ01ABD100 1TB                  | 2         | 2      | 2.7%    |
| Seagate ST9500325AS 500GB               | 2         | 2      | 2.7%    |
| Seagate ST500LT012-1DG142 500GB         | 2         | 2      | 2.7%    |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 2      | 2.7%    |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 2         | 2      | 2.7%    |
| Hitachi HTS547564A9E384 640GB           | 2         | 2      | 2.7%    |
| WDC WD6400BEVT-22A0RT0 640GB            | 1         | 2      | 1.35%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 2      | 1.35%   |
| WDC WD5000BEVT-60ZAT1 500GB             | 1         | 3      | 1.35%   |
| WDC WD3200BPVT-22ZEST0 320GB            | 1         | 1      | 1.35%   |
| WDC WD3200BEVT-75ZCT0 320GB             | 1         | 1      | 1.35%   |
| WDC WD2500BEVT-35A23T0 250GB            | 1         | 1      | 1.35%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 2      | 1.35%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 2      | 1.35%   |
| Transcend TS256GSSD230S 256GB           | 1         | 1      | 1.35%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD    | 1         | 1      | 1.35%   |
| Toshiba MQ01ABD050 500GB                | 1         | 1      | 1.35%   |
| Toshiba MK5065GSX 500GB                 | 1         | 1      | 1.35%   |
| Toshiba MK5055GSX 500GB                 | 1         | 5      | 1.35%   |
| Toshiba MK3265GSX 320GB                 | 1         | 1      | 1.35%   |
| SK hynix SC308 SATA 256GB SSD           | 1         | 1      | 1.35%   |
| Seagate ST9500423AS 500GB               | 1         | 2      | 1.35%   |
| Seagate ST9500325ASG 500GB              | 1         | 1      | 1.35%   |
| Seagate ST9320423AS 320GB               | 1         | 2      | 1.35%   |
| Seagate ST9250410AS 250GB               | 1         | 1      | 1.35%   |
| Seagate ST9250315AS 250GB               | 1         | 1      | 1.35%   |
| Seagate ST9160821AS 160GB               | 1         | 5      | 1.35%   |
| Seagate ST9160310AS 160GB               | 1         | 1      | 1.35%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 2      | 1.35%   |
| Seagate ST500LM000-1EJ162 500GB         | 1         | 2      | 1.35%   |
| Seagate ST320LT007-9ZV142 320GB         | 1         | 1      | 1.35%   |
| SanDisk SSD PLUS 240 GB                 | 1         | 1      | 1.35%   |
| Samsung Electronics SSD 970 EVO 2TB     | 1         | 1      | 1.35%   |
| Samsung Electronics SSD 850 EVO 1TB     | 1         | 1      | 1.35%   |
| Samsung Electronics SSD 750 EVO 250GB   | 1         | 1      | 1.35%   |
| Samsung Electronics PM961 NVMe 512GB    | 1         | 1      | 1.35%   |
| Samsung Electronics HM641JI 640GB       | 1         | 1      | 1.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                   | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate                  | 19        | 28     | 25.68%  |
| Hitachi                  | 10        | 10     | 13.51%  |
| Toshiba                  | 9         | 13     | 12.16%  |
| WDC                      | 8         | 14     | 10.81%  |
| HGST                     | 6         | 7      | 8.11%   |
| Samsung Electronics      | 5         | 5      | 6.76%   |
| Fujitsu                  | 4         | 4      | 5.41%   |
| Kingston                 | 3         | 3      | 4.05%   |
| Crucial                  | 2         | 2      | 2.7%    |
| Transcend                | 1         | 1      | 1.35%   |
| SK hynix                 | 1         | 1      | 1.35%   |
| SanDisk                  | 1         | 1      | 1.35%   |
| KingSpec                 | 1         | 3      | 1.35%   |
| Intel                    | 1         | 2      | 1.35%   |
| Biwin Storage Technology | 1         | 1      | 1.35%   |
| Apple                    | 1         | 1      | 1.35%   |
| A-DATA Technology        | 1         | 1      | 1.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 28     | 33.93%  |
| Hitachi             | 10        | 10     | 17.86%  |
| WDC                 | 8         | 14     | 14.29%  |
| Toshiba             | 8         | 12     | 14.29%  |
| HGST                | 6         | 7      | 10.71%  |
| Fujitsu             | 4         | 4      | 7.14%   |
| Samsung Electronics | 1         | 1      | 1.79%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 55        | 76     | 75.34%  |
| SSD  | 15        | 18     | 20.55%  |
| NVMe | 3         | 3      | 4.11%   |

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
| Detected | 827       | 1396   | 61.44%  |
| Works    | 446       | 678    | 33.14%  |
| Malfunc  | 73        | 97     | 5.42%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 910       | 60.75%  |
| Samsung Electronics              | 157       | 10.48%  |
| AMD                              | 124       | 8.28%   |
| SanDisk                          | 61        | 4.07%   |
| SK hynix                         | 40        | 2.67%   |
| Toshiba America Info Systems     | 33        | 2.2%    |
| Micron Technology                | 27        | 1.8%    |
| Phison Electronics               | 23        | 1.54%   |
| Kingston Technology Company      | 22        | 1.47%   |
| KIOXIA                           | 18        | 1.2%    |
| Nvidia                           | 15        | 1%      |
| Micron/Crucial Technology        | 15        | 1%      |
| Apple                            | 12        | 0.8%    |
| ADATA Technology                 | 9         | 0.6%    |
| Marvell Technology Group         | 7         | 0.47%   |
| Solid State Storage Technology   | 4         | 0.27%   |
| Silicon Motion                   | 4         | 0.27%   |
| Lite-On Technology               | 4         | 0.27%   |
| Union Memory (Shenzhen)          | 2         | 0.13%   |
| Silicon Integrated Systems [SiS] | 2         | 0.13%   |
| Realtek Semiconductor            | 2         | 0.13%   |
| Lenovo                           | 2         | 0.13%   |
| ULi Electronics                  | 1         | 0.07%   |
| Shenzhen Longsys Electronics     | 1         | 0.07%   |
| JMicron Technology               | 1         | 0.07%   |
| Biwin Storage Technology         | 1         | 0.07%   |
| ASMedia Technology               | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 110       | 6.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 108       | 6.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 96        | 6.02%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 96        | 6.02%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 82        | 5.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 81        | 5.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 54        | 3.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 49        | 3.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 48        | 3.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 42        | 2.63%   |
| Intel Volume Management Device NVMe RAID Controller                            | 35        | 2.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 34        | 2.13%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 34        | 2.13%   |
| Micron NVMe Storage Controller                                                 | 26        | 1.63%   |
| Samsung NVMe SSD Controller 980                                                | 25        | 1.57%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 25        | 1.57%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 22        | 1.38%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 18        | 1.13%   |
| Intel SSD 660P Series                                                          | 18        | 1.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 17        | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 16        | 1%      |
| KIOXIA NVMe SSD Controller BG4                                                 | 16        | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 16        | 1%      |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 16        | 1%      |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 15        | 0.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 15        | 0.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 14        | 0.88%   |
| Intel Comet Lake SATA AHCI Controller                                          | 12        | 0.75%   |
| Samsung Electronics SATA controller                                            | 11        | 0.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 11        | 0.69%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 10        | 0.63%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 10        | 0.63%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 10        | 0.63%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 10        | 0.63%   |
| Phison PS5013 E13 NVMe Controller                                              | 10        | 0.63%   |
| Phison E12 NVMe Controller                                                     | 10        | 0.63%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 10        | 0.63%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 9         | 0.56%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 9         | 0.56%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 9         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 885       | 57.96%  |
| NVMe | 431       | 28.23%  |
| RAID | 135       | 8.84%   |
| IDE  | 76        | 4.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1096      | 85.49%  |
| AMD    | 184       | 14.35%  |
| ARM    | 2         | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 32        | 2.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 25        | 1.95%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 22        | 1.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 21        | 1.64%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 19        | 1.48%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 19        | 1.48%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 17        | 1.32%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 16        | 1.25%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 16        | 1.25%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 16        | 1.25%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 16        | 1.25%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 15        | 1.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 15        | 1.17%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 14        | 1.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 14        | 1.09%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 13        | 1.01%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 13        | 1.01%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 12        | 0.93%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 12        | 0.93%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 12        | 0.93%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 12        | 0.93%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 11        | 0.86%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 11        | 0.86%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 11        | 0.86%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 10        | 0.78%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 10        | 0.78%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 10        | 0.78%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 10        | 0.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 10        | 0.78%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 10        | 0.78%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 9         | 0.7%    |
| Intel Core i7-3740QM CPU @ 2.70GHz      | 9         | 0.7%    |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 9         | 0.7%    |
| Intel Core i5-5300U CPU @ 2.30GHz       | 9         | 0.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz       | 9         | 0.7%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 9         | 0.7%    |
| AMD Ryzen 5 5500U with Radeon Graphics  | 9         | 0.7%    |
| Intel Core i7-8850H CPU @ 2.60GHz       | 8         | 0.62%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 8         | 0.62%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 8         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 437       | 34.06%  |
| Intel Core i5                  | 321       | 25.02%  |
| Other                          | 95        | 7.4%    |
| Intel Core 2 Duo               | 57        | 4.44%   |
| Intel Core i3                  | 53        | 4.13%   |
| Intel Celeron                  | 52        | 4.05%   |
| AMD Ryzen 7                    | 36        | 2.81%   |
| AMD Ryzen 5                    | 29        | 2.26%   |
| Intel Pentium                  | 26        | 2.03%   |
| AMD A6                         | 20        | 1.56%   |
| AMD A4                         | 17        | 1.33%   |
| Intel Atom                     | 15        | 1.17%   |
| AMD Ryzen 9                    | 8         | 0.62%   |
| AMD E2                         | 8         | 0.62%   |
| Intel Pentium Dual-Core        | 7         | 0.55%   |
| Intel Core 2                   | 7         | 0.55%   |
| AMD Ryzen 7 PRO                | 7         | 0.55%   |
| AMD E1                         | 7         | 0.55%   |
| AMD A8                         | 7         | 0.55%   |
| AMD A10                        | 7         | 0.55%   |
| Intel Genuine                  | 6         | 0.47%   |
| Intel Core i9                  | 6         | 0.47%   |
| Intel Core m3                  | 5         | 0.39%   |
| Intel Core M                   | 5         | 0.39%   |
| AMD Ryzen 3                    | 5         | 0.39%   |
| Intel Xeon                     | 4         | 0.31%   |
| Intel Celeron Dual-Core        | 4         | 0.31%   |
| AMD E                          | 4         | 0.31%   |
| Intel Pentium Dual             | 3         | 0.23%   |
| Intel Pentium M                | 2         | 0.16%   |
| Intel Core m7                  | 2         | 0.16%   |
| Intel Core Duo                 | 2         | 0.16%   |
| Intel Celeron M                | 2         | 0.16%   |
| AMD V120                       | 2         | 0.16%   |
| AMD FX                         | 2         | 0.16%   |
| AMD A12                        | 2         | 0.16%   |
| Intel Mobile Pentium 4         | 1         | 0.08%   |
| Intel Core m5                  | 1         | 0.08%   |
| AMD V140                       | 1         | 0.08%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 623       | 48.56%  |
| 4      | 433       | 33.75%  |
| 6      | 109       | 8.5%    |
| 8      | 67        | 5.22%   |
| 1      | 30        | 2.34%   |
| 14     | 8         | 0.62%   |
| 12     | 6         | 0.47%   |
| 10     | 5         | 0.39%   |
| 16     | 1         | 0.08%   |
| 5      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1280      | 99.84%  |
| 2      | 2         | 0.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1010      | 78.72%  |
| 1      | 271       | 21.12%  |
| 8      | 1         | 0.08%   |
| 4      | 1         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1256      | 97.36%  |
| 32-bit         | 17        | 1.32%   |
| Unknown        | 16        | 1.24%   |
| 64-bit         | 1         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 356       | 26.55%  |
| 0x206a7    | 85        | 6.34%   |
| 0x306a9    | 79        | 5.89%   |
| 0x406e3    | 50        | 3.73%   |
| 0x40651    | 50        | 3.73%   |
| 0x906ea    | 48        | 3.58%   |
| 0x306d4    | 41        | 3.06%   |
| 0x806ec    | 40        | 2.98%   |
| 0x1067a    | 40        | 2.98%   |
| 0x806ea    | 36        | 2.68%   |
| 0x20655    | 36        | 2.68%   |
| 0x306c3    | 35        | 2.61%   |
| 0x806c1    | 33        | 2.46%   |
| 0x806e9    | 30        | 2.24%   |
| 0xa0652    | 21        | 1.57%   |
| 0x906e9    | 21        | 1.57%   |
| 0x20652    | 19        | 1.42%   |
| 0x806eb    | 15        | 1.12%   |
| 0x0a50000c | 15        | 1.12%   |
| 0x06006705 | 15        | 1.12%   |
| 0x30678    | 14        | 1.04%   |
| 0x706e5    | 13        | 0.97%   |
| 0x506e3    | 13        | 0.97%   |
| 0x07030105 | 13        | 0.97%   |
| 0x806d1    | 12        | 0.89%   |
| 0x106e5    | 11        | 0.82%   |
| 0x0700010f | 11        | 0.82%   |
| 0x906a3    | 10        | 0.75%   |
| 0x10676    | 10        | 0.75%   |
| 0x08108109 | 9         | 0.67%   |
| 0x406c4    | 8         | 0.6%    |
| 0x08108102 | 8         | 0.6%    |
| 0x6fd      | 7         | 0.52%   |
| 0x406c3    | 7         | 0.52%   |
| 0x08600103 | 7         | 0.52%   |
| 0x06001119 | 7         | 0.52%   |
| 0x6f6      | 6         | 0.45%   |
| 0x08608103 | 6         | 0.45%   |
| 0x506c9    | 5         | 0.37%   |
| 0x08600106 | 5         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 253       | 19.72%  |
| IvyBridge        | 117       | 9.12%   |
| Haswell          | 113       | 8.81%   |
| SandyBridge      | 107       | 8.34%   |
| Skylake          | 89        | 6.94%   |
| Westmere         | 65        | 5.07%   |
| Penryn           | 62        | 4.83%   |
| Broadwell        | 50        | 3.9%    |
| TigerLake        | 42        | 3.27%   |
| CometLake        | 37        | 2.88%   |
| Unknown          | 35        | 2.73%   |
| Silvermont       | 33        | 2.57%   |
| IceLake          | 31        | 2.42%   |
| Excavator        | 27        | 2.1%    |
| Zen 2            | 21        | 1.64%   |
| Zen+             | 20        | 1.56%   |
| Zen 3            | 20        | 1.56%   |
| Core             | 20        | 1.56%   |
| Puma             | 18        | 1.4%    |
| Alderlake Hybrid | 14        | 1.09%   |
| Nehalem          | 12        | 0.94%   |
| Jaguar           | 12        | 0.94%   |
| Goldmont plus    | 12        | 0.94%   |
| P6               | 11        | 0.86%   |
| Zen              | 10        | 0.78%   |
| Piledriver       | 9         | 0.7%    |
| Bonnell          | 8         | 0.62%   |
| Goldmont         | 7         | 0.55%   |
| K10 Llano        | 6         | 0.47%   |
| K10              | 6         | 0.47%   |
| Bobcat           | 5         | 0.39%   |
| Steamroller      | 4         | 0.31%   |
| Tremont          | 3         | 0.23%   |
| K8 & K10 hybrid  | 2         | 0.16%   |
| NetBurst         | 1         | 0.08%   |
| K8 Hammer        | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 962       | 57.54%  |
| Nvidia                           | 423       | 25.3%   |
| AMD                              | 283       | 16.93%  |
| Silicon Integrated Systems [SiS] | 2         | 0.12%   |
| Neomagic                         | 2         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 102       | 5.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 96        | 5.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 67        | 3.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 62        | 3.58%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 61        | 3.52%   |
| Intel UHD Graphics 620                                                                   | 50        | 2.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 46        | 2.66%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 45        | 2.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 40        | 2.31%   |
| Intel HD Graphics 5500                                                                   | 34        | 1.96%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 34        | 1.96%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 33        | 1.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 31        | 1.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 28        | 1.62%   |
| Intel HD Graphics 620                                                                    | 27        | 1.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 23        | 1.33%   |
| Intel HD Graphics 630                                                                    | 22        | 1.27%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 22        | 1.27%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 20        | 1.15%   |
| AMD Renoir                                                                               | 20        | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 17        | 0.98%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 17        | 0.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16        | 0.92%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 15        | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.87%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 15        | 0.87%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 15        | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 0.81%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 14        | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 14        | 0.81%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 14        | 0.81%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 14        | 0.81%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 14        | 0.81%   |
| Intel HD Graphics 530                                                                    | 13        | 0.75%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 13        | 0.75%   |
| AMD Lucienne                                                                             | 13        | 0.75%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 0.69%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 11        | 0.64%   |
| Intel Iris Plus Graphics G7                                                              | 11        | 0.64%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 10        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 600       | 46.48%  |
| Intel + Nvidia           | 304       | 23.55%  |
| 1 x AMD                  | 166       | 12.86%  |
| 1 x Nvidia               | 92        | 7.13%   |
| Intel + AMD              | 52        | 4.03%   |
| 2 x AMD                  | 39        | 3.02%   |
| AMD + Nvidia             | 26        | 2.01%   |
| Other                    | 2         | 0.15%   |
| 2 x Intel                | 2         | 0.15%   |
| 1 x SiS                  | 2         | 0.15%   |
| 1 x Neomagic             | 2         | 0.15%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.15%   |
| 2 x Nvidia               | 1         | 0.08%   |
| Intel + 2 x Nvidia       | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1069      | 81.17%  |
| Proprietary | 208       | 15.79%  |
| Unknown     | 40        | 3.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 820       | 61.89%  |
| 1.01-2.0   | 153       | 11.55%  |
| 0.01-0.5   | 132       | 9.96%   |
| 3.01-4.0   | 88        | 6.64%   |
| 0.51-1.0   | 77        | 5.81%   |
| 5.01-6.0   | 25        | 1.89%   |
| 7.01-8.0   | 18        | 1.36%   |
| 2.01-3.0   | 8         | 0.6%    |
| 8.01-16.0  | 4         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 298       | 19.92%  |
| LG Display              | 215       | 14.37%  |
| Chimei Innolux          | 165       | 11.03%  |
| Samsung Electronics     | 145       | 9.69%   |
| BOE                     | 130       | 8.69%   |
| Apple                   | 85        | 5.68%   |
| Sharp                   | 64        | 4.28%   |
| Dell                    | 45        | 3.01%   |
| Chi Mei Optoelectronics | 40        | 2.67%   |
| Lenovo                  | 29        | 1.94%   |
| Hewlett-Packard         | 22        | 1.47%   |
| Goldstar                | 21        | 1.4%    |
| BenQ                    | 21        | 1.4%    |
| PANDA                   | 20        | 1.34%   |
| Acer                    | 20        | 1.34%   |
| Philips                 | 18        | 1.2%    |
| Sony                    | 11        | 0.74%   |
| AOC                     | 10        | 0.67%   |
| ViewSonic               | 8         | 0.53%   |
| Ancor Communications    | 8         | 0.53%   |
| InfoVision              | 7         | 0.47%   |
| Toshiba                 | 6         | 0.4%    |
| LG Philips              | 6         | 0.4%    |
| CPT                     | 6         | 0.4%    |
| Unknown                 | 5         | 0.33%   |
| Panasonic               | 5         | 0.33%   |
| LGD                     | 5         | 0.33%   |
| Hitachi                 | 5         | 0.33%   |
| Valve                   | 4         | 0.27%   |
| SAC                     | 4         | 0.27%   |
| Kogan                   | 4         | 0.27%   |
| HannStar                | 4         | 0.27%   |
| GKK                     | 4         | 0.27%   |
| GDH                     | 4         | 0.27%   |
| eMachines               | 4         | 0.27%   |
| CSO                     | 4         | 0.27%   |
| ASUSTek Computer        | 4         | 0.27%   |
| InnoLux Display         | 3         | 0.2%    |
| Unknown (XXX)           | 2         | 0.13%   |
| TMX                     | 2         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 17        | 1.11%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 11        | 0.72%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 11        | 0.72%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 10        | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 9         | 0.59%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 9         | 0.59%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 9         | 0.59%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 8         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 7         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 7         | 0.46%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 7         | 0.46%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 7         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 6         | 0.39%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 6         | 0.39%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 6         | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch         | 6         | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 6         | 0.39%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                     | 6         | 0.39%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 6         | 0.39%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 6         | 0.39%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 6         | 0.39%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.39%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 5         | 0.33%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 5         | 0.33%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 5         | 0.33%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 5         | 0.33%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 5         | 0.33%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 5         | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 5         | 0.33%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 4         | 0.26%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 4         | 0.26%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 4         | 0.26%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 4         | 0.26%   |
| eMachines E190HQV EMA0212 1366x768 409x230mm 18.5-inch                   | 4         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 535       | 38.38%  |
| 1366x768 (WXGA)    | 437       | 31.35%  |
| 3840x2160 (4K)     | 86        | 6.17%   |
| 1280x800 (WXGA)    | 58        | 4.16%   |
| 1600x900 (HD+)     | 48        | 3.44%   |
| 1440x900 (WXGA+)   | 33        | 2.37%   |
| 2560x1440 (QHD)    | 27        | 1.94%   |
| 1920x1200 (WUXGA)  | 22        | 1.58%   |
| 2880x1800          | 18        | 1.29%   |
| 2560x1600          | 18        | 1.29%   |
| 3840x2400          | 12        | 0.86%   |
| 1680x1050 (WSXGA+) | 12        | 0.86%   |
| 1280x1024 (SXGA)   | 10        | 0.72%   |
| 3200x1800 (QHD+)   | 9         | 0.65%   |
| 3440x1440          | 8         | 0.57%   |
| 1024x600           | 6         | 0.43%   |
| 1360x768           | 5         | 0.36%   |
| Unknown            | 5         | 0.36%   |
| 800x1280           | 4         | 0.29%   |
| 3840x1080          | 4         | 0.29%   |
| 3072x1920          | 4         | 0.29%   |
| 2240x1400          | 4         | 0.29%   |
| 2160x1440          | 4         | 0.29%   |
| 2256x1504          | 3         | 0.22%   |
| 5760x2160          | 2         | 0.14%   |
| 3456x2160          | 2         | 0.14%   |
| 3286x1080          | 2         | 0.14%   |
| 3200x2000          | 2         | 0.14%   |
| 2304x1440          | 2         | 0.14%   |
| 1280x720 (HD)      | 2         | 0.14%   |
| 1024x768 (XGA)     | 2         | 0.14%   |
| 3840x1600          | 1         | 0.07%   |
| 3840x1100          | 1         | 0.07%   |
| 3000x2000          | 1         | 0.07%   |
| 2726x768           | 1         | 0.07%   |
| 2288x1287          | 1         | 0.07%   |
| 1920x540           | 1         | 0.07%   |
| 1720x1440          | 1         | 0.07%   |
| 1680x945           | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 600       | 40.08%  |
| 13      | 211       | 14.09%  |
| 14      | 157       | 10.49%  |
| 17      | 96        | 6.41%   |
| 27      | 61        | 4.07%   |
| 24      | 53        | 3.54%   |
| 12      | 45        | 3.01%   |
| 11      | 40        | 2.67%   |
| 23      | 38        | 2.54%   |
| 21      | 27        | 1.8%    |
| Unknown | 25        | 1.67%   |
| 31      | 19        | 1.27%   |
| 16      | 15        | 1%      |
| 84      | 10        | 0.67%   |
| 18      | 10        | 0.67%   |
| 72      | 9         | 0.6%    |
| 19      | 9         | 0.6%    |
| 22      | 7         | 0.47%   |
| 10      | 7         | 0.47%   |
| 52      | 6         | 0.4%    |
| 40      | 6         | 0.4%    |
| 20      | 6         | 0.4%    |
| 34      | 5         | 0.33%   |
| 54      | 4         | 0.27%   |
| 7       | 4         | 0.27%   |
| 48      | 3         | 0.2%    |
| 35      | 3         | 0.2%    |
| 26      | 3         | 0.2%    |
| 46      | 2         | 0.13%   |
| 37      | 2         | 0.13%   |
| 32      | 2         | 0.13%   |
| 8       | 2         | 0.13%   |
| 142     | 1         | 0.07%   |
| 78      | 1         | 0.07%   |
| 63      | 1         | 0.07%   |
| 55      | 1         | 0.07%   |
| 49      | 1         | 0.07%   |
| 38      | 1         | 0.07%   |
| 36      | 1         | 0.07%   |
| 29      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 833       | 56.25%  |
| 201-300        | 219       | 14.79%  |
| 501-600        | 131       | 8.85%   |
| 351-400        | 124       | 8.37%   |
| 401-500        | 53        | 3.58%   |
| 601-700        | 31        | 2.09%   |
| Unknown        | 25        | 1.69%   |
| 1501-2000      | 20        | 1.35%   |
| 1001-1500      | 18        | 1.22%   |
| 801-900        | 12        | 0.81%   |
| 701-800        | 8         | 0.54%   |
| 1-100          | 4         | 0.27%   |
| 101-200        | 2         | 0.14%   |
| More than 2000 | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1044      | 80.8%   |
| 16/10   | 179       | 13.85%  |
| Unknown | 19        | 1.47%   |
| 3/2     | 14        | 1.08%   |
| 21/9    | 9         | 0.7%    |
| 5/4     | 8         | 0.62%   |
| 4/3     | 6         | 0.46%   |
| 32/9    | 5         | 0.39%   |
| 0.67    | 4         | 0.31%   |
| 6/5     | 1         | 0.08%   |
| 3.40    | 1         | 0.08%   |
| 1.00    | 1         | 0.08%   |
| 0.62    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 600       | 40.27%  |
| 81-90          | 278       | 18.66%  |
| 201-250        | 104       | 6.98%   |
| 71-80          | 93        | 6.24%   |
| 121-130        | 83        | 5.57%   |
| 301-350        | 63        | 4.23%   |
| 61-70          | 41        | 2.75%   |
| 51-60          | 41        | 2.75%   |
| More than 1000 | 32        | 2.15%   |
| 351-500        | 29        | 1.95%   |
| Unknown        | 25        | 1.68%   |
| 151-200        | 24        | 1.61%   |
| 501-1000       | 16        | 1.07%   |
| 111-120        | 14        | 0.94%   |
| 251-300        | 11        | 0.74%   |
| 141-150        | 10        | 0.67%   |
| 131-140        | 10        | 0.67%   |
| 41-50          | 8         | 0.54%   |
| 1-40           | 6         | 0.4%    |
| 91-100         | 2         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 525       | 36.23%  |
| 101-120       | 430       | 29.68%  |
| 51-100        | 244       | 16.84%  |
| 161-240       | 117       | 8.07%   |
| More than 240 | 81        | 5.59%   |
| 1-50          | 27        | 1.86%   |
| Unknown       | 25        | 1.73%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1036      | 77.49%  |
| 2     | 223       | 16.68%  |
| 0     | 40        | 2.99%   |
| 3     | 33        | 2.47%   |
| 4     | 5         | 0.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 703       | 33.44%  |
| Realtek Semiconductor             | 648       | 30.83%  |
| Qualcomm Atheros                  | 287       | 13.65%  |
| Broadcom                          | 156       | 7.42%   |
| Broadcom Limited                  | 51        | 2.43%   |
| Ralink                            | 27        | 1.28%   |
| Sierra Wireless                   | 18        | 0.86%   |
| MediaTek                          | 17        | 0.81%   |
| Marvell Technology Group          | 16        | 0.76%   |
| DisplayLink                       | 14        | 0.67%   |
| Samsung Electronics               | 12        | 0.57%   |
| Dell                              | 12        | 0.57%   |
| Huawei Technologies               | 10        | 0.48%   |
| Nvidia                            | 9         | 0.43%   |
| Apple                             | 9         | 0.43%   |
| Ralink Technology                 | 8         | 0.38%   |
| NetGear                           | 8         | 0.38%   |
| Lenovo                            | 8         | 0.38%   |
| Hewlett-Packard                   | 8         | 0.38%   |
| ZTE WCDMA Technologies MSM        | 7         | 0.33%   |
| TP-Link                           | 7         | 0.33%   |
| Edimax Technology                 | 7         | 0.33%   |
| ASIX Electronics                  | 7         | 0.33%   |
| OPPO Electronics                  | 6         | 0.29%   |
| Google                            | 4         | 0.19%   |
| ASUSTek Computer                  | 4         | 0.19%   |
| Xiaomi                            | 3         | 0.14%   |
| Qualcomm                          | 3         | 0.14%   |
| Motorola PCS                      | 3         | 0.14%   |
| JMicron Technology                | 3         | 0.14%   |
| Ericsson Business Mobile Networks | 3         | 0.14%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.1%    |
| Qualcomm Atheros Communications   | 2         | 0.1%    |
| ICS Advent                        | 2         | 0.1%    |
| D-Link                            | 2         | 0.1%    |
| Arduino SA                        | 2         | 0.1%    |
| Wilocity                          | 1         | 0.05%   |
| ULi Electronics                   | 1         | 0.05%   |
| Toshiba                           | 1         | 0.05%   |
| T & A Mobile Phones               | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 386       | 15.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 114       | 4.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 72        | 2.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 63        | 2.5%    |
| Intel Wi-Fi 6 AX200                                               | 56        | 2.22%   |
| Intel Wireless 8260                                               | 53        | 2.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 45        | 1.78%   |
| Intel Wireless 8265 / 8275                                        | 45        | 1.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 44        | 1.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 43        | 1.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 39        | 1.55%   |
| Intel Wireless 7260                                               | 39        | 1.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 36        | 1.43%   |
| Intel Wi-Fi 6 AX201                                               | 34        | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 33        | 1.31%   |
| Intel Wireless 3165                                               | 33        | 1.31%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 33        | 1.31%   |
| Intel Centrino Ultimate-N 6300                                    | 32        | 1.27%   |
| Intel Wireless 7265                                               | 29        | 1.15%   |
| Intel Ethernet Connection I219-LM                                 | 29        | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 25        | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 25        | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 24        | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 23        | 0.91%   |
| Intel Wireless-AC 9260                                            | 20        | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 20        | 0.79%   |
| Intel 82577LM Gigabit Network Connection                          | 19        | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 18        | 0.71%   |
| Intel Wireless 3160                                               | 18        | 0.71%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 18        | 0.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 17        | 0.67%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 17        | 0.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 17        | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 0.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 16        | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 0.63%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 15        | 0.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 14        | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 14        | 0.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 14        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 681       | 50.78%  |
| Qualcomm Atheros                | 241       | 17.97%  |
| Realtek Semiconductor           | 142       | 10.59%  |
| Broadcom                        | 126       | 9.4%    |
| Broadcom Limited                | 41        | 3.06%   |
| Ralink                          | 27        | 2.01%   |
| Sierra Wireless                 | 17        | 1.27%   |
| MediaTek                        | 16        | 1.19%   |
| Ralink Technology               | 8         | 0.6%    |
| NetGear                         | 8         | 0.6%    |
| Edimax Technology               | 7         | 0.52%   |
| Dell                            | 7         | 0.52%   |
| TP-Link                         | 6         | 0.45%   |
| ASUSTek Computer                | 4         | 0.3%    |
| Qualcomm Atheros Communications | 2         | 0.15%   |
| Qualcomm                        | 2         | 0.15%   |
| D-Link                          | 2         | 0.15%   |
| Xiaomi                          | 1         | 0.07%   |
| Wilocity                        | 1         | 0.07%   |
| Hewlett-Packard                 | 1         | 0.07%   |
| Belkin Components               | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 56        | 4.15%   |
| Intel Wireless 8260                                            | 53        | 3.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 45        | 3.34%   |
| Intel Wireless 8265 / 8275                                     | 45        | 3.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 44        | 3.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 43        | 3.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 39        | 2.89%   |
| Intel Wireless 7260                                            | 39        | 2.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 36        | 2.67%   |
| Intel Wi-Fi 6 AX201                                            | 34        | 2.52%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 33        | 2.45%   |
| Intel Wireless 3165                                            | 33        | 2.45%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 33        | 2.45%   |
| Intel Centrino Ultimate-N 6300                                 | 32        | 2.37%   |
| Intel Wireless 7265                                            | 29        | 2.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 25        | 1.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 25        | 1.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 24        | 1.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 23        | 1.71%   |
| Intel Wireless-AC 9260                                         | 20        | 1.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 20        | 1.48%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 18        | 1.34%   |
| Intel Wireless 3160                                            | 18        | 1.34%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 18        | 1.34%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 17        | 1.26%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 17        | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 17        | 1.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 16        | 1.19%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 15        | 1.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 14        | 1.04%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 14        | 1.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 14        | 1.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 14        | 1.04%   |
| Intel Centrino Advanced-N 6200                                 | 13        | 0.96%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 12        | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                  | 12        | 0.89%   |
| Intel WiFi Link 5100                                           | 11        | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 11        | 0.82%   |
| Intel Centrino Advanced-N 6235                                 | 11        | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 586       | 52.51%  |
| Intel                            | 252       | 22.58%  |
| Qualcomm Atheros                 | 88        | 7.89%   |
| Broadcom                         | 67        | 6%      |
| Marvell Technology Group         | 16        | 1.43%   |
| DisplayLink                      | 14        | 1.25%   |
| Broadcom Limited                 | 10        | 0.9%    |
| Nvidia                           | 9         | 0.81%   |
| Apple                            | 9         | 0.81%   |
| Samsung Electronics              | 8         | 0.72%   |
| Lenovo                           | 8         | 0.72%   |
| ZTE WCDMA Technologies MSM       | 7         | 0.63%   |
| Huawei Technologies              | 7         | 0.63%   |
| ASIX Electronics                 | 7         | 0.63%   |
| OPPO Electronics                 | 6         | 0.54%   |
| Google                           | 4         | 0.36%   |
| JMicron Technology               | 3         | 0.27%   |
| Hewlett-Packard                  | 3         | 0.27%   |
| Xiaomi                           | 2         | 0.18%   |
| Silicon Integrated Systems [SiS] | 2         | 0.18%   |
| ICS Advent                       | 2         | 0.18%   |
| T & A Mobile Phones              | 1         | 0.09%   |
| Sierra Wireless                  | 1         | 0.09%   |
| Qualcomm                         | 1         | 0.09%   |
| Motorola PCS                     | 1         | 0.09%   |
| Microsoft                        | 1         | 0.09%   |
| Attansic Technology              | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 386       | 34.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 114       | 10.04%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 72        | 6.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 63        | 5.55%   |
| Intel Ethernet Connection I219-LM                                 | 29        | 2.56%   |
| Intel 82577LM Gigabit Network Connection                          | 19        | 1.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 1.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 1.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 14        | 1.23%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 1.06%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 1.06%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 12        | 1.06%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.97%   |
| Intel Ethernet Connection (4) I219-V                              | 11        | 0.97%   |
| Intel Ethernet Connection I219-V                                  | 10        | 0.88%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 10        | 0.88%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 9         | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.79%   |
| Intel 82567LM Gigabit Network Connection                          | 9         | 0.79%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 9         | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 0.7%    |
| Intel Ethernet Connection I217-LM                                 | 8         | 0.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 8         | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7         | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.62%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 0.62%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 0.53%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 6         | 0.53%   |
| OPPO KALAMA-MTP_CID:0437_SN:AEEEF597                              | 6         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.53%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 0.53%   |
| Realtek Killer E3000 2.5GbE Controller                            | 5         | 0.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 0.44%   |
| Nvidia MCP79 Ethernet                                             | 5         | 0.44%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 5         | 0.44%   |
| DisplayLink Dell Universal Dock D6000                             | 5         | 0.44%   |
| ZTE WCDMA MSM ZTE BLADE A530                                      | 4         | 0.35%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1260      | 53.82%  |
| Ethernet | 1044      | 44.6%   |
| Modem    | 34        | 1.45%   |
| Unknown  | 3         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1043      | 78.19%  |
| Ethernet | 291       | 21.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 946       | 73.56%  |
| 1     | 319       | 24.81%  |
| 0     | 12        | 0.93%   |
| 3     | 9         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1143      | 87.65%  |
| Yes  | 161       | 12.35%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 510       | 49.8%   |
| Qualcomm Atheros Communications | 85        | 8.3%    |
| Apple                           | 73        | 7.13%   |
| Broadcom                        | 69        | 6.74%   |
| Realtek Semiconductor           | 56        | 5.47%   |
| Lite-On Technology              | 39        | 3.81%   |
| IMC Networks                    | 37        | 3.61%   |
| Toshiba                         | 36        | 3.52%   |
| Foxconn / Hon Hai               | 35        | 3.42%   |
| Hewlett-Packard                 | 18        | 1.76%   |
| Dell                            | 17        | 1.66%   |
| Ralink                          | 14        | 1.37%   |
| Cambridge Silicon Radio         | 9         | 0.88%   |
| ASUSTek Computer                | 6         | 0.59%   |
| Alps Electric                   | 6         | 0.59%   |
| Realtek                         | 5         | 0.49%   |
| Ralink Technology               | 4         | 0.39%   |
| USI                             | 2         | 0.2%    |
| Opticis                         | 1         | 0.1%    |
| MediaTek                        | 1         | 0.1%    |
| Belkin Components               | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 204       | 19.92%  |
| Intel AX201 Bluetooth                               | 104       | 10.16%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 59        | 5.76%   |
| Intel AX200 Bluetooth                               | 57        | 5.57%   |
| Qualcomm Atheros  Bluetooth Device                  | 54        | 5.27%   |
| Apple Bluetooth Host Controller                     | 39        | 3.81%   |
| Realtek Bluetooth Radio                             | 30        | 2.93%   |
| Apple Bluetooth USB Host Controller                 | 27        | 2.64%   |
| Realtek  Bluetooth 4.2 Adapter                      | 18        | 1.76%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 1.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 18        | 1.76%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 17        | 1.66%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 1.56%   |
| Intel Bluetooth Device                              | 15        | 1.46%   |
| Ralink RT3290 Bluetooth                             | 14        | 1.37%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 1.37%   |
| Intel AX210 Bluetooth                               | 14        | 1.37%   |
| Toshiba Bluetooth Device                            | 13        | 1.27%   |
| Lite-On Atheros AR3012 Bluetooth                    | 13        | 1.27%   |
| IMC Networks Bluetooth Radio                        | 13        | 1.27%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 1.27%   |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 1.07%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 11        | 1.07%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 0.98%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 9         | 0.88%   |
| Lite-On Bluetooth Device                            | 9         | 0.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 0.88%   |
| Toshiba Integrated Bluetooth HCI                    | 8         | 0.78%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 0.78%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.78%   |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 0.68%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.68%   |
| Foxconn / Hon Hai Wireless_Device                   | 6         | 0.59%   |
| Dell DW375 Bluetooth Module                         | 6         | 0.59%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 6         | 0.59%   |
| IMC Networks Wireless_Device                        | 5         | 0.49%   |
| IMC Networks Bluetooth                              | 5         | 0.49%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.49%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 5         | 0.49%   |
| Broadcom BCM20702A0                                 | 5         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1065      | 63.81%  |
| Nvidia                                       | 234       | 14.02%  |
| AMD                                          | 232       | 13.9%   |
| Realtek Semiconductor                        | 18        | 1.08%   |
| Apple                                        | 8         | 0.48%   |
| Logitech                                     | 7         | 0.42%   |
| Lenovo                                       | 7         | 0.42%   |
| GN Netcom                                    | 7         | 0.42%   |
| Razer USA                                    | 6         | 0.36%   |
| Creative Technology                          | 6         | 0.36%   |
| C-Media Electronics                          | 6         | 0.36%   |
| Kingston Technology                          | 5         | 0.3%    |
| Generalplus Technology                       | 5         | 0.3%    |
| Texas Instruments                            | 4         | 0.24%   |
| JMTek                                        | 4         | 0.24%   |
| Hewlett-Packard                              | 4         | 0.24%   |
| Plantronics                                  | 3         | 0.18%   |
| OPPO Electronics                             | 3         | 0.18%   |
| Microsoft                                    | 3         | 0.18%   |
| Thermaltake                                  | 2         | 0.12%   |
| SteelSeries ApS                              | 2         | 0.12%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.12%   |
| Samsung Electronics                          | 2         | 0.12%   |
| Native Instruments                           | 2         | 0.12%   |
| Micro Star International                     | 2         | 0.12%   |
| M-Audio                                      | 2         | 0.12%   |
| Dell                                         | 2         | 0.12%   |
| Conexant Systems                             | 2         | 0.12%   |
| Chicony Electronics                          | 2         | 0.12%   |
| Blue Microphones                             | 2         | 0.12%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.06%   |
| ZOOM                                         | 1         | 0.06%   |
| XMOS                                         | 1         | 0.06%   |
| ULi Electronics                              | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.06%   |
| Sony                                         | 1         | 0.06%   |
| Sennheiser electronic                        | 1         | 0.06%   |
| RODE Microphones                             | 1         | 0.06%   |
| No brand                                     | 1         | 0.06%   |
| LG Electronics                               | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 157       | 7.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 130       | 6.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 93        | 4.67%   |
| AMD Family 17h/19h HD Audio Controller                                     | 87        | 4.37%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 77        | 3.87%   |
| Intel Cannon Lake PCH cAVS                                                 | 67        | 3.37%   |
| Intel 8 Series HD Audio Controller                                         | 63        | 3.17%   |
| Intel Haswell-ULT HD Audio Controller                                      | 62        | 3.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 50        | 2.51%   |
| Intel Broadwell-U Audio Controller                                         | 50        | 2.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 50        | 2.51%   |
| AMD FCH Azalia Controller                                                  | 50        | 2.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 44        | 2.21%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 44        | 2.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 42        | 2.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 42        | 2.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 37        | 1.86%   |
| Intel Comet Lake PCH cAVS                                                  | 36        | 1.81%   |
| AMD Kabini HDMI/DP Audio                                                   | 35        | 1.76%   |
| Intel Comet Lake PCH-LP cAVS                                               | 31        | 1.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 27        | 1.36%   |
| Intel CM238 HD Audio Controller                                            | 27        | 1.36%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 27        | 1.36%   |
| Nvidia GF108 High Definition Audio Controller                              | 24        | 1.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 23        | 1.16%   |
| AMD High Definition Audio Controller                                       | 22        | 1.11%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 21        | 1.06%   |
| Nvidia GK107 HDMI Audio Controller                                         | 20        | 1.01%   |
| Nvidia TU106 High Definition Audio Controller                              | 18        | 0.9%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 18        | 0.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 18        | 0.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 17        | 0.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 17        | 0.85%   |
| Realtek Semiconductor USB Audio                                            | 16        | 0.8%    |
| Nvidia TU116 High Definition Audio Controller                              | 16        | 0.8%    |
| Nvidia GT216 HDMI Audio Controller                                         | 15        | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 15        | 0.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14        | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 14        | 0.7%    |
| Nvidia GP104 High Definition Audio Controller                              | 12        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 229       | 31.41%  |
| SK hynix                   | 194       | 26.61%  |
| Micron Technology          | 103       | 14.13%  |
| Kingston                   | 63        | 8.64%   |
| Crucial                    | 35        | 4.8%    |
| Unknown                    | 21        | 2.88%   |
| Elpida                     | 17        | 2.33%   |
| Ramaxel Technology         | 11        | 1.51%   |
| Nanya Technology           | 9         | 1.23%   |
| Team                       | 8         | 1.1%    |
| Corsair                    | 7         | 0.96%   |
| A-DATA Technology          | 5         | 0.69%   |
| Apacer                     | 4         | 0.55%   |
| G.Skill                    | 3         | 0.41%   |
| Toshiba                    | 2         | 0.27%   |
| Smart                      | 2         | 0.27%   |
| Silicon Power              | 2         | 0.27%   |
| Unknown                    | 2         | 0.27%   |
| Unknown (0x89AD)           | 1         | 0.14%   |
| Unknown (0x873E)           | 1         | 0.14%   |
| Transcend                  | 1         | 0.14%   |
| Qimonda                    | 1         | 0.14%   |
| pqi                        | 1         | 0.14%   |
| Patriot                    | 1         | 0.14%   |
| Netlist                    | 1         | 0.14%   |
| Neo Forza                  | 1         | 0.14%   |
| GSkill                     | 1         | 0.14%   |
| Avant                      | 1         | 0.14%   |
| ASint Technology           | 1         | 0.14%   |
| Anucell Technology Holding | 1         | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 17        | 2.19%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 1.54%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 1.41%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 11        | 1.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 1.29%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 10        | 1.29%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 1.16%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 1.16%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 8         | 1.03%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.9%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.9%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.9%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.9%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 7         | 0.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.9%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.77%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.77%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.77%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 6         | 0.77%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 6         | 0.77%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 6         | 0.77%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.64%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.64%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 5         | 0.64%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s         | 5         | 0.64%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 4         | 0.51%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.51%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 4         | 0.51%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 0.51%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.51%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.51%   |
| Samsung RAM M471B1G73CB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.51%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.51%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 4         | 0.51%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.51%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.51%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s         | 4         | 0.51%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s       | 4         | 0.51%   |
| Micron RAM 8ATF1G64HZ-2G6D1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 275       | 43.31%  |
| DDR3    | 249       | 39.21%  |
| LPDDR3  | 42        | 6.61%   |
| LPDDR4  | 21        | 3.31%   |
| DDR2    | 21        | 3.31%   |
| SDRAM   | 9         | 1.42%   |
| LPDDR5  | 7         | 1.1%    |
| DDR5    | 7         | 1.1%    |
| DDR     | 2         | 0.31%   |
| DRAM    | 1         | 0.16%   |
| Unknown | 1         | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 556       | 87.42%  |
| Row Of Chips | 70        | 11.01%  |
| Chip         | 7         | 1.1%    |
| Unknown      | 2         | 0.31%   |
| DIMM         | 1         | 0.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 250       | 37.43%  |
| 4096  | 204       | 30.54%  |
| 16384 | 104       | 15.57%  |
| 2048  | 75        | 11.23%  |
| 32768 | 22        | 3.29%   |
| 1024  | 9         | 1.35%   |
| 512   | 3         | 0.45%   |
| 256   | 1         | 0.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 180       | 26.51%  |
| 2667    | 141       | 20.77%  |
| 3200    | 97        | 14.29%  |
| 1334    | 44        | 6.48%   |
| 2133    | 43        | 6.33%   |
| 2400    | 34        | 5.01%   |
| 1067    | 18        | 2.65%   |
| 1333    | 16        | 2.36%   |
| 1867    | 15        | 2.21%   |
| 4800    | 11        | 1.62%   |
| 667     | 11        | 1.62%   |
| 4267    | 10        | 1.47%   |
| Unknown | 9         | 1.33%   |
| 8400    | 7         | 1.03%   |
| 6400    | 7         | 1.03%   |
| 3266    | 7         | 1.03%   |
| 1066    | 7         | 1.03%   |
| 800     | 6         | 0.88%   |
| 4266    | 4         | 0.59%   |
| 2048    | 4         | 0.59%   |
| 4199    | 3         | 0.44%   |
| 3733    | 2         | 0.29%   |
| 975     | 2         | 0.29%   |
| 533     | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 3         | 37.5%   |
| Hewlett-Packard     | 2         | 25%     |
| Canon               | 2         | 25%     |
| Samsung Electronics | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Canon TS3100 series         | 2         | 25%     |
| Samsung ML-1865             | 1         | 12.5%   |
| HP ENVY Inspire 7900 series | 1         | 12.5%   |
| HP DeskJet 2300 series      | 1         | 12.5%   |
| Brother MFC-1810            | 1         | 12.5%   |
| Brother HL-2140 series      | 1         | 12.5%   |
| Brother HL-1110 series      | 1         | 12.5%   |

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


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 313       | 26.35%  |
| Microdia                               | 112       | 9.43%   |
| Realtek Semiconductor                  | 105       | 8.84%   |
| IMC Networks                           | 97        | 8.16%   |
| Sunplus Innovation Technology          | 91        | 7.66%   |
| Apple                                  | 68        | 5.72%   |
| Quanta                                 | 50        | 4.21%   |
| Cheng Uei Precision Industry (Foxlink) | 48        | 4.04%   |
| Suyin                                  | 45        | 3.79%   |
| Bison Electronics                      | 40        | 3.37%   |
| Acer                                   | 33        | 2.78%   |
| Logitech                               | 28        | 2.36%   |
| Lite-On Technology                     | 20        | 1.68%   |
| Syntek                                 | 15        | 1.26%   |
| Luxvisions Innotech Limited            | 15        | 1.26%   |
| Samsung Electronics                    | 11        | 0.93%   |
| Silicon Motion                         | 10        | 0.84%   |
| Importek                               | 10        | 0.84%   |
| Ricoh                                  | 9         | 0.76%   |
| Primax Electronics                     | 7         | 0.59%   |
| Lenovo                                 | 7         | 0.59%   |
| Alcor Micro                            | 7         | 0.59%   |
| Razer USA                              | 4         | 0.34%   |
| OmniVision Technologies                | 4         | 0.34%   |
| Magic Control Technology               | 4         | 0.34%   |
| DigiTech                               | 4         | 0.34%   |
| ALi                                    | 4         | 0.34%   |
| LG Electronics                         | 3         | 0.25%   |
| Z-Star Microelectronics                | 2         | 0.17%   |
| SunplusIT                              | 2         | 0.17%   |
| Sonix Technology                       | 2         | 0.17%   |
| OPPO Electronics                       | 2         | 0.17%   |
| Genesys Logic                          | 2         | 0.17%   |
| GEMBIRD                                | 2         | 0.17%   |
| Tobii Technology AB                    | 1         | 0.08%   |
| Sunplus Technology                     | 1         | 0.08%   |
| Solid Year                             | 1         | 0.08%   |
| Mimaki Engineering                     | 1         | 0.08%   |
| Microsoft                              | 1         | 0.08%   |
| lihappe8                               | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 63        | 5.24%   |
| Chicony Integrated Camera                               | 55        | 4.58%   |
| Realtek Integrated_Webcam_HD                            | 31        | 2.58%   |
| Chicony HD WebCam                                       | 30        | 2.5%    |
| Sunplus Integrated_Webcam_HD                            | 26        | 2.16%   |
| Chicony TOSHIBA Web Camera - HD                         | 26        | 2.16%   |
| IMC Networks Integrated Camera                          | 23        | 1.91%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 22        | 1.83%   |
| Apple FaceTime HD Camera (Built-in)                     | 18        | 1.5%    |
| Apple Built-in iSight                                   | 18        | 1.5%    |
| Chicony HP TrueVision HD Camera                         | 17        | 1.41%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 15        | 1.25%   |
| Chicony HP Truevision HD                                | 14        | 1.16%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 13        | 1.08%   |
| Apple FaceTime HD Camera                                | 13        | 1.08%   |
| Sunplus HD WebCam                                       | 12        | 1%      |
| Realtek USB Camera                                      | 12        | 1%      |
| Chicony USB 2.0 Camera                                  | 12        | 1%      |
| Chicony HD User Facing                                  | 12        | 1%      |
| Samsung Galaxy series, misc. (MTP mode)                 | 11        | 0.92%   |
| Quanta HD User Facing                                   | 11        | 0.92%   |
| Chicony USB2.0 Camera                                   | 11        | 0.92%   |
| Microdia Integrated Webcam                              | 10        | 0.83%   |
| Lite-On Integrated Camera                               | 10        | 0.83%   |
| Chicony HP HD Camera                                    | 10        | 0.83%   |
| Chicony CNF9055 Toshiba Webcam                          | 10        | 0.83%   |
| Acer Integrated Camera                                  | 10        | 0.83%   |
| Syntek Integrated Camera                                | 9         | 0.75%   |
| Suyin HP Truevision HD                                  | 9         | 0.75%   |
| Quanta HP TrueVision HD Camera                          | 9         | 0.75%   |
| Bison HD Webcam                                         | 9         | 0.75%   |
| Quanta HD Webcam                                        | 8         | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 8         | 0.67%   |
| Realtek USB2.0 HD UVC WebCam                            | 7         | 0.58%   |
| Realtek Integrated Webcam HD                            | 7         | 0.58%   |
| Realtek 2SF022                                          | 7         | 0.58%   |
| Quanta HP Webcam                                        | 7         | 0.58%   |
| Logitech Webcam C270                                    | 7         | 0.58%   |
| Chicony Integrated Camera (1280x720@30)                 | 7         | 0.58%   |
| Bison Integrated Camera                                 | 7         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 109       | 42.58%  |
| Synaptics                  | 50        | 19.53%  |
| Shenzhen Goodix Technology | 29        | 11.33%  |
| LighTuning Technology      | 20        | 7.81%   |
| AuthenTec                  | 15        | 5.86%   |
| Upek                       | 14        | 5.47%   |
| Elan Microelectronics      | 12        | 4.69%   |
| STMicroelectronics         | 6         | 2.34%   |
| Focal-systems.Corp         | 1         | 0.39%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 21        | 8.2%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 8.2%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 14        | 5.47%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 5.08%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 4.3%    |
| Validity Sensors VFS491                                                    | 10        | 3.91%   |
| Shenzhen Goodix  Fingerprint Device                                        | 10        | 3.91%   |
| Shenzhen Goodix FingerPrint                                                | 10        | 3.91%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 3.52%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 3.52%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 3.52%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 2.73%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 2.73%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 2.73%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 2.73%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 2.34%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 2.34%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.34%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 2.34%   |
| Elan ELAN:Fingerprint                                                      | 6         | 2.34%   |
| Elan ELAN:ARM-M4                                                           | 6         | 2.34%   |
| Synaptics WBDI Device                                                      | 5         | 1.95%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.95%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.56%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.56%   |
| Synaptics UWP WBDI                                                         | 4         | 1.56%   |
| AuthenTec AES1600                                                          | 4         | 1.56%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.17%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 1.17%   |
| Synaptics  WBDI                                                            | 3         | 1.17%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.17%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.17%   |
| AuthenTec AES2810                                                          | 2         | 0.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.39%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.39%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.39%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.39%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.39%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 34        | 61.82%  |
| Alcor Micro           | 11        | 20%     |
| Upek                  | 4         | 7.27%   |
| Lenovo                | 3         | 5.45%   |
| O2 Micro              | 2         | 3.64%   |
| Advanced Card Systems | 1         | 1.82%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 16        | 29.09%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 10.91%  |
| Broadcom 5880                                                                | 6         | 10.91%  |
| Broadcom 58200                                                               | 6         | 10.91%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 7.27%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 5.45%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.64%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.82%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 788       | 58.89%  |
| 1     | 439       | 32.81%  |
| 2     | 91        | 6.8%    |
| 3     | 13        | 0.97%   |
| 4     | 6         | 0.45%   |
| 5     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 255       | 39.41%  |
| Graphics card            | 144       | 22.26%  |
| Net/wireless             | 57        | 8.81%   |
| Chipcard                 | 50        | 7.73%   |
| Multimedia controller    | 41        | 6.34%   |
| Camera                   | 21        | 3.25%   |
| Bluetooth                | 21        | 3.25%   |
| Net/ethernet             | 12        | 1.85%   |
| Communication controller | 12        | 1.85%   |
| Storage                  | 10        | 1.55%   |
| Modem                    | 8         | 1.24%   |
| Card reader              | 7         | 1.08%   |
| Sound                    | 6         | 0.93%   |
| Unassigned class         | 1         | 0.15%   |
| Storage/ide              | 1         | 0.15%   |
| Storage/ata              | 1         | 0.15%   |

