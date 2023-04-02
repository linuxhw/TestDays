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

Total: 2079

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Toshiba       | Satellite L50-B             | [696718d602](https://linux-hardware.org/?probe=696718d602) | Sep 03, 2021 |
| Dell          | XPS 15 9510                 | [d606dd2010](https://linux-hardware.org/?probe=d606dd2010) | Sep 03, 2021 |
| Dell          | Latitude E6430s             | [92a767fd0b](https://linux-hardware.org/?probe=92a767fd0b) | Sep 03, 2021 |
| Toshiba       | TECRA A40-D                 | [5afac0ef07](https://linux-hardware.org/?probe=5afac0ef07) | Sep 02, 2021 |
| Dell          | XPS 15 9500                 | [bf06fd5933](https://linux-hardware.org/?probe=bf06fd5933) | Sep 02, 2021 |
| Dell          | XPS 15 9500                 | [740118101a](https://linux-hardware.org/?probe=740118101a) | Sep 02, 2021 |
| HP            | Pavilion dv6                | [20e136bd56](https://linux-hardware.org/?probe=20e136bd56) | Aug 31, 2021 |
| Toshiba       | Satellite L670              | [4610a7f835](https://linux-hardware.org/?probe=4610a7f835) | Aug 31, 2021 |
| HP            | Presario CQ62               | [da35a133c7](https://linux-hardware.org/?probe=da35a133c7) | Aug 31, 2021 |
| HP            | Pavilion Notebook           | [846b2e2a87](https://linux-hardware.org/?probe=846b2e2a87) | Aug 30, 2021 |
| Dell          | Latitude E6230              | [055cc1b72a](https://linux-hardware.org/?probe=055cc1b72a) | Aug 30, 2021 |
| Dell          | G5 5590                     | [268f4cffb4](https://linux-hardware.org/?probe=268f4cffb4) | Aug 30, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [a900c9c170](https://linux-hardware.org/?probe=a900c9c170) | Aug 30, 2021 |
| ASUSTek       | BU403UA                     | [685da500ca](https://linux-hardware.org/?probe=685da500ca) | Aug 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [b7c59b9453](https://linux-hardware.org/?probe=b7c59b9453) | Aug 30, 2021 |
| Timi          | TM1607                      | [0dcb7e6611](https://linux-hardware.org/?probe=0dcb7e6611) | Aug 30, 2021 |
| Toshiba       | Satellite C55t-C            | [2bf7dba42f](https://linux-hardware.org/?probe=2bf7dba42f) | Aug 30, 2021 |
| Dell          | Latitude E7470              | [e047247ab4](https://linux-hardware.org/?probe=e047247ab4) | Aug 29, 2021 |
| Toshiba       | PORTEGE M780                | [3062a1ac2f](https://linux-hardware.org/?probe=3062a1ac2f) | Aug 28, 2021 |
| Lenovo        | ThinkPad SL 27464RM         | [612cb5f7a2](https://linux-hardware.org/?probe=612cb5f7a2) | Aug 28, 2021 |
| Apple         | MacBookPro5,5               | [97ed1ed910](https://linux-hardware.org/?probe=97ed1ed910) | Aug 28, 2021 |
| Apple         | MacBookPro5,5               | [e035ede092](https://linux-hardware.org/?probe=e035ede092) | Aug 27, 2021 |
| Kogan         | KAL11C250SB                 | [1c38937a42](https://linux-hardware.org/?probe=1c38937a42) | Aug 24, 2021 |
| Apple         | MacBookPro8,1               | [7b296604b3](https://linux-hardware.org/?probe=7b296604b3) | Aug 24, 2021 |
| Dell          | Latitude E5500              | [5af91644f4](https://linux-hardware.org/?probe=5af91644f4) | Aug 22, 2021 |
| HP            | Notebook                    | [5ac3618644](https://linux-hardware.org/?probe=5ac3618644) | Aug 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [ff1e83e570](https://linux-hardware.org/?probe=ff1e83e570) | Aug 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [4128c360ba](https://linux-hardware.org/?probe=4128c360ba) | Aug 22, 2021 |
| HP            | Laptop 15s-du1xxx           | [0db32c3e7e](https://linux-hardware.org/?probe=0db32c3e7e) | Aug 21, 2021 |
| Dell          | XPS 15 9570                 | [1114f42cd0](https://linux-hardware.org/?probe=1114f42cd0) | Aug 21, 2021 |
| Dell          | XPS 15 9570                 | [44188d0e94](https://linux-hardware.org/?probe=44188d0e94) | Aug 21, 2021 |
| ASUSTek       | G60JX                       | [d3844a2f0d](https://linux-hardware.org/?probe=d3844a2f0d) | Aug 19, 2021 |
| ASUSTek       | G60JX                       | [9cbac37f77](https://linux-hardware.org/?probe=9cbac37f77) | Aug 19, 2021 |
| HP            | 245 G7 Notebook PC          | [5f26581582](https://linux-hardware.org/?probe=5f26581582) | Aug 19, 2021 |
| Apple         | MacBookPro8,1               | [4678cd0f57](https://linux-hardware.org/?probe=4678cd0f57) | Aug 19, 2021 |
| Panasonic     | CF-19RDRAMGA                | [b11b688d14](https://linux-hardware.org/?probe=b11b688d14) | Aug 18, 2021 |
| Lenovo        | G560 0679                   | [897bce191e](https://linux-hardware.org/?probe=897bce191e) | Aug 18, 2021 |
| HP            | EliteBook 745 G5            | [7154f86bd2](https://linux-hardware.org/?probe=7154f86bd2) | Aug 15, 2021 |
| HP            | EliteBook 820 G3            | [9e40c4d015](https://linux-hardware.org/?probe=9e40c4d015) | Aug 15, 2021 |
| Panasonic     | CF-19RDRAMGA                | [3d6f06387e](https://linux-hardware.org/?probe=3d6f06387e) | Aug 14, 2021 |
| ASUSTek       | N550JV                      | [f56a2bd3fa](https://linux-hardware.org/?probe=f56a2bd3fa) | Aug 14, 2021 |
| ASUSTek       | UX21E                       | [d334eaddee](https://linux-hardware.org/?probe=d334eaddee) | Aug 13, 2021 |
| ASUSTek       | N550JV                      | [631e697061](https://linux-hardware.org/?probe=631e697061) | Aug 13, 2021 |
| ASUSTek       | N550JV                      | [191ce05579](https://linux-hardware.org/?probe=191ce05579) | Aug 13, 2021 |
| Dell          | G7 7790                     | [99dd172940](https://linux-hardware.org/?probe=99dd172940) | Aug 12, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c1fe9dc989](https://linux-hardware.org/?probe=c1fe9dc989) | Aug 12, 2021 |
| Lenovo        | G50-45 80E3                 | [deb2b65c2b](https://linux-hardware.org/?probe=deb2b65c2b) | Aug 12, 2021 |
| HP            | Laptop 15s-du1xxx           | [19412614ef](https://linux-hardware.org/?probe=19412614ef) | Aug 11, 2021 |

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
| Ubuntu 20.04       | 196       | 13.83%  |
| Ubuntu 18.04       | 82        | 5.79%   |
| Ubuntu 22.04       | 44        | 3.11%   |
| Pop!_OS 22.04      | 35        | 2.47%   |
| KDE neon 20.04     | 30        | 2.12%   |
| Fedora 36          | 29        | 2.05%   |
| Debian 11          | 29        | 2.05%   |
| Linux Mint 20.2    | 28        | 1.98%   |
| Pop!_OS 21.04      | 27        | 1.91%   |
| Zorin 16           | 26        | 1.83%   |
| Pop!_OS 20.04      | 25        | 1.76%   |
| OpenMandriva 4.3   | 24        | 1.69%   |
| Linux Mint 20.3    | 24        | 1.69%   |
| Arch               | 24        | 1.69%   |
| Arch Rolling       | 23        | 1.62%   |
| Linux Mint 20      | 22        | 1.55%   |
| Ubuntu 20.10       | 21        | 1.48%   |
| Fedora 37          | 21        | 1.48%   |
| OpenMandriva 4.2   | 20        | 1.41%   |
| Pop!_OS 20.10      | 19        | 1.34%   |
| Linux Mint 20.1    | 19        | 1.34%   |
| Ubuntu 21.10       | 18        | 1.27%   |
| Ubuntu 19.04       | 18        | 1.27%   |
| Manjaro            | 18        | 1.27%   |
| Ubuntu 19.10       | 17        | 1.2%    |
| Fedora 33          | 16        | 1.13%   |
| Zorin 15           | 15        | 1.06%   |
| Ubuntu 21.04       | 14        | 0.99%   |
| Fedora 35          | 14        | 0.99%   |
| ArcoLinux Rolling  | 14        | 0.99%   |
| Xubuntu 18.04      | 13        | 0.92%   |
| Ubuntu 22.10       | 12        | 0.85%   |
| Linux Mint 21      | 12        | 0.85%   |
| Fedora 32          | 12        | 0.85%   |
| OpenMandriva 23.01 | 11        | 0.78%   |
| Linux Mint 21.1    | 11        | 0.78%   |
| Xubuntu 20.04      | 10        | 0.71%   |
| Linux Mint 19.3    | 9         | 0.64%   |
| Kubuntu 20.04      | 9         | 0.64%   |
| Fedora 34          | 9         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 409       | 30.84%  |
| Linux Mint    | 127       | 9.58%   |
| Pop!_OS       | 108       | 8.14%   |
| Fedora        | 95        | 7.16%   |
| OpenMandriva  | 67        | 5.05%   |
| Zorin         | 48        | 3.62%   |
| Debian        | 47        | 3.54%   |
| Arch          | 46        | 3.47%   |
| Manjaro       | 43        | 3.24%   |
| KDE neon      | 38        | 2.87%   |
| Xubuntu       | 35        | 2.64%   |
| Kubuntu       | 28        | 2.11%   |
| Elementary    | 22        | 1.66%   |
| Kali          | 17        | 1.28%   |
| Gentoo        | 17        | 1.28%   |
| ArcoLinux     | 14        | 1.06%   |
| Clear Linux   | 13        | 0.98%   |
| Endless       | 11        | 0.83%   |
| Ubuntu Unity  | 10        | 0.75%   |
| ROSA          | 10        | 0.75%   |
| openSUSE      | 10        | 0.75%   |
| Lubuntu       | 10        | 0.75%   |
| Ubuntu MATE   | 8         | 0.6%    |
| LMDE          | 8         | 0.6%    |
| EndeavourOS   | 8         | 0.6%    |
| Parrot        | 6         | 0.45%   |
| MX            | 6         | 0.45%   |
| LinuxFX       | 6         | 0.45%   |
| SteamOS       | 5         | 0.38%   |
| BlackPanther  | 5         | 0.38%   |
| Reborn OS     | 4         | 0.3%    |
| Ubuntu Budgie | 3         | 0.23%   |
| Solus         | 3         | 0.23%   |
| Xero          | 2         | 0.15%   |
| Void Linux    | 2         | 0.15%   |
| RHEL          | 2         | 0.15%   |
| PureOS        | 2         | 0.15%   |
| Oracle Linux  | 2         | 0.15%   |
| Linux Lite    | 2         | 0.15%   |
| Feren OS      | 2         | 0.15%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 33        | 2.09%   |
| 5.16.7-desktop-1omv4003  | 23        | 1.45%   |
| 5.10.14-desktop-1omv4002 | 20        | 1.26%   |
| 5.4.0-58-generic         | 18        | 1.14%   |
| 5.4.0-26-generic         | 15        | 0.95%   |
| 5.4.0-40-generic         | 14        | 0.88%   |
| 5.11.0-7620-generic      | 14        | 0.88%   |
| 5.4.0-29-generic         | 13        | 0.82%   |
| 5.15.0-56-generic        | 13        | 0.82%   |
| 5.4.0-48-generic         | 12        | 0.76%   |
| 5.11.0-38-generic        | 12        | 0.76%   |
| 5.17.5-76051705-generic  | 11        | 0.7%    |
| 5.11.0-37-generic        | 11        | 0.7%    |
| 5.11.0-27-generic        | 11        | 0.7%    |
| 6.1.1-desktop-1omv2290   | 10        | 0.63%   |
| 5.4.0-52-generic         | 10        | 0.63%   |
| 5.15.0-58-generic        | 10        | 0.63%   |
| 5.8.0-63-generic         | 9         | 0.57%   |
| 5.4.0-81-generic         | 9         | 0.57%   |
| 5.4.0-74-generic         | 9         | 0.57%   |
| 5.3.0-40-generic         | 9         | 0.57%   |
| 5.8.0-7630-generic       | 8         | 0.51%   |
| 5.8.0-59-generic         | 8         | 0.51%   |
| 5.4.0-7634-generic       | 8         | 0.51%   |
| 5.4.0-65-generic         | 8         | 0.51%   |
| 5.4.0-54-generic         | 8         | 0.51%   |
| 5.3.0-28-generic         | 8         | 0.51%   |
| 5.15.0-46-generic        | 8         | 0.51%   |
| 5.13.0-7620-generic      | 8         | 0.51%   |
| 5.13.0-40-generic        | 8         | 0.51%   |
| 5.11.0-40-generic        | 8         | 0.51%   |
| 5.0.0-13-generic         | 8         | 0.51%   |
| 5.8.0-7642-generic       | 7         | 0.44%   |
| 5.8.0-53-generic         | 7         | 0.44%   |
| 5.8.0-50-generic         | 7         | 0.44%   |
| 5.4.0-91-generic         | 7         | 0.44%   |
| 5.4.0-7642-generic       | 7         | 0.44%   |
| 5.4.0-47-generic         | 7         | 0.44%   |
| 5.4.0-31-generic         | 7         | 0.44%   |
| 5.3.0-46-generic         | 7         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 263       | 17.98%  |
| 5.11.0  | 101       | 6.9%    |
| 5.15.0  | 99        | 6.77%   |
| 5.8.0   | 84        | 5.74%   |
| 5.13.0  | 82        | 5.6%    |
| 4.15.0  | 69        | 4.72%   |
| 5.3.0   | 52        | 3.55%   |
| 5.10.0  | 41        | 2.8%    |
| 5.0.0   | 41        | 2.8%    |
| 5.19.0  | 34        | 2.32%   |
| 4.18.0  | 30        | 2.05%   |
| 5.16.7  | 24        | 1.64%   |
| 5.10.14 | 20        | 1.37%   |
| 5.17.5  | 17        | 1.16%   |
| 6.1.1   | 14        | 0.96%   |
| 4.19.0  | 11        | 0.75%   |
| 6.0.0   | 10        | 0.68%   |
| 6.0.12  | 9         | 0.62%   |
| 5.18.0  | 9         | 0.62%   |
| 5.18.10 | 8         | 0.55%   |
| 6.0.9   | 6         | 0.41%   |
| 6.0.7   | 6         | 0.41%   |
| 5.18.12 | 6         | 0.41%   |
| 5.17.15 | 6         | 0.41%   |
| 5.14.0  | 6         | 0.41%   |
| 5.8.16  | 5         | 0.34%   |
| 5.16.11 | 5         | 0.34%   |
| 5.16.0  | 5         | 0.34%   |
| 5.12.4  | 5         | 0.34%   |
| 4.9.60  | 5         | 0.34%   |
| 4.4.0   | 5         | 0.34%   |
| 6.1.11  | 4         | 0.27%   |
| 6.0.6   | 4         | 0.27%   |
| 5.9.16  | 4         | 0.27%   |
| 5.18.7  | 4         | 0.27%   |
| 5.16.2  | 4         | 0.27%   |
| 5.16.19 | 4         | 0.27%   |
| 5.15.72 | 4         | 0.27%   |
| 5.15.11 | 4         | 0.27%   |
| 5.13.12 | 4         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 286       | 19.92%  |
| 5.15    | 135       | 9.4%    |
| 5.11    | 115       | 8.01%   |
| 5.8     | 101       | 7.03%   |
| 5.13    | 96        | 6.69%   |
| 5.10    | 85        | 5.92%   |
| 4.15    | 69        | 4.81%   |
| 5.16    | 57        | 3.97%   |
| 5.3     | 56        | 3.9%    |
| 5.19    | 51        | 3.55%   |
| 6.0     | 45        | 3.13%   |
| 5.0     | 45        | 3.13%   |
| 6.1     | 39        | 2.72%   |
| 5.17    | 38        | 2.65%   |
| 5.18    | 36        | 2.51%   |
| 4.18    | 35        | 2.44%   |
| 5.6     | 18        | 1.25%   |
| 5.9     | 17        | 1.18%   |
| 5.14    | 16        | 1.11%   |
| 5.12    | 15        | 1.04%   |
| 4.19    | 14        | 0.97%   |
| 5.5     | 12        | 0.84%   |
| 5.7     | 11        | 0.77%   |
| 4.9     | 11        | 0.77%   |
| 6.2     | 8         | 0.56%   |
| 5.2     | 5         | 0.35%   |
| 4.4     | 5         | 0.35%   |
| 4.1     | 3         | 0.21%   |
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
| x86_64  | 1212      | 97.27%  |
| i686    | 30        | 2.41%   |
| i586    | 2         | 0.16%   |
| aarch64 | 2         | 0.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 599       | 44.87%  |
| KDE5            | 200       | 14.98%  |
| Unknown         | 147       | 11.01%  |
| X-Cinnamon      | 112       | 8.39%   |
| XFCE            | 98        | 7.34%   |
| KDE             | 32        | 2.4%    |
| MATE            | 30        | 2.25%   |
| Cinnamon        | 21        | 1.57%   |
| Pantheon        | 20        | 1.5%    |
| Unity           | 12        | 0.9%    |
| i3              | 12        | 0.9%    |
| LXQt            | 9         | 0.67%   |
| LXDE            | 9         | 0.67%   |
| KDE4            | 8         | 0.6%    |
| Deepin          | 6         | 0.45%   |
| Budgie          | 6         | 0.45%   |
| awesome         | 3         | 0.22%   |
| Openbox         | 2         | 0.15%   |
| GNOME Flashback | 2         | 0.15%   |
| sway            | 1         | 0.07%   |
| qtile           | 1         | 0.07%   |
| LeftWM          | 1         | 0.07%   |
| icewm           | 1         | 0.07%   |
| dwm             | 1         | 0.07%   |
| dusk            | 1         | 0.07%   |
| BunsenLabs      | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1004      | 77.47%  |
| Wayland | 183       | 14.12%  |
| Unknown | 81        | 6.25%   |
| Tty     | 28        | 2.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 709       | 54.25%  |
| GDM     | 163       | 12.47%  |
| SDDM    | 161       | 12.32%  |
| LightDM | 118       | 9.03%   |
| GDM3    | 103       | 7.88%   |
| TDM     | 39        | 2.98%   |
| KDM     | 8         | 0.61%   |
| SLiM    | 2         | 0.15%   |
| LXDM    | 2         | 0.15%   |
| XDM     | 1         | 0.08%   |
| GREETD  | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Notebooks | Percent |
|--------------|-----------|---------|
| en_AU        | 916       | 70.68%  |
| en_US        | 188       | 14.51%  |
| Unknown      | 132       | 10.19%  |
| C            | 30        | 2.31%   |
| en_GB        | 16        | 1.23%   |
| C.UTF8       | 4         | 0.31%   |
| zh_CN        | 1         | 0.08%   |
| ru_RU        | 1         | 0.08%   |
| it_IT        | 1         | 0.08%   |
| fr_FR        | 1         | 0.08%   |
| es_ES        | 1         | 0.08%   |
| en_IN        | 1         | 0.08%   |
| en_GB.UTF-12 | 1         | 0.08%   |
| en_CA        | 1         | 0.08%   |
| en_AU.UFT-8  | 1         | 0.08%   |
| de_DE        | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 657       | 51.25%  |
| BIOS | 625       | 48.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 995       | 77.43%  |
| Btrfs   | 115       | 8.95%   |
| Overlay | 88        | 6.85%   |
| Unknown | 39        | 3.04%   |
| Xfs     | 19        | 1.48%   |
| Zfs     | 13        | 1.01%   |
| Ext2    | 5         | 0.39%   |
| Tmpfs   | 4         | 0.31%   |
| XXXXXXX | 3         | 0.23%   |
| Ext3    | 3         | 0.23%   |
| F2fs    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 752       | 58.93%  |
| GPT     | 412       | 32.29%  |
| MBR     | 112       | 8.78%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1119      | 88.32%  |
| Yes       | 148       | 11.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 984       | 77.36%  |
| Yes       | 288       | 22.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 224       | 18.01%  |
| Dell                           | 217       | 17.44%  |
| Lenovo                         | 208       | 16.72%  |
| ASUSTek Computer               | 118       | 9.49%   |
| Acer                           | 112       | 9%      |
| Toshiba                        | 92        | 7.4%    |
| Apple                          | 84        | 6.75%   |
| MSI                            | 29        | 2.33%   |
| Alienware                      | 15        | 1.21%   |
| Samsung Electronics            | 13        | 1.05%   |
| Sony                           | 10        | 0.8%    |
| Notebook                       | 10        | 0.8%    |
| Gigabyte Technology            | 9         | 0.72%   |
| Timi                           | 8         | 0.64%   |
| Panasonic                      | 7         | 0.56%   |
| IT Channel Pty                 | 7         | 0.56%   |
| HUAWEI                         | 7         | 0.56%   |
| Razer                          | 6         | 0.48%   |
| Metabox                        | 6         | 0.48%   |
| Unknown                        | 6         | 0.48%   |
| System76                       | 4         | 0.32%   |
| Intel Client Systems           | 4         | 0.32%   |
| Google                         | 4         | 0.32%   |
| AMI                            | 4         | 0.32%   |
| Valve                          | 3         | 0.24%   |
| Medion                         | 3         | 0.24%   |
| LG Electronics                 | 3         | 0.24%   |
| Framework                      | 3         | 0.24%   |
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
| HP Pavilion dv6                        | 14        | 1.13%   |
| HP Pavilion g6                         | 11        | 0.88%   |
| HP Notebook                            | 10        | 0.8%    |
| Unknown                                | 9         | 0.72%   |
| HP Pavilion 15                         | 8         | 0.64%   |
| Dell XPS 15 9570                       | 7         | 0.56%   |
| Apple MacBookPro9,2                    | 7         | 0.56%   |
| Apple MacBookPro10,1                   | 7         | 0.56%   |
| Apple MacBookPro8,1                    | 6         | 0.48%   |
| Apple MacBookAir7,2                    | 6         | 0.48%   |
| Acer ConceptD CN315-71P                | 6         | 0.48%   |
| Toshiba Satellite P750                 | 5         | 0.4%    |
| Dell XPS 15 9560                       | 5         | 0.4%    |
| Dell XPS 13 9360                       | 5         | 0.4%    |
| Dell Latitude E7450                    | 5         | 0.4%    |
| Acer Aspire 5750G                      | 5         | 0.4%    |
| Toshiba Satellite L850                 | 4         | 0.32%   |
| Toshiba Satellite L500                 | 4         | 0.32%   |
| Toshiba Satellite L50-A                | 4         | 0.32%   |
| Toshiba Satellite C660                 | 4         | 0.32%   |
| Lenovo ThinkPad T470s W10DG 20JTS0HT00 | 4         | 0.32%   |
| Lenovo IdeaPad 1 14IGL05 81VU          | 4         | 0.32%   |
| Lenovo G50-45 80E3                     | 4         | 0.32%   |
| HP Pavilion Notebook                   | 4         | 0.32%   |
| HP ENVY 17                             | 4         | 0.32%   |
| Dell XPS 15 9500                       | 4         | 0.32%   |
| Dell XPS 15 7590                       | 4         | 0.32%   |
| Dell XPS 13 9370                       | 4         | 0.32%   |
| Dell XPS 13 7390                       | 4         | 0.32%   |
| Dell Precision 5530                    | 4         | 0.32%   |
| Dell Latitude E7440                    | 4         | 0.32%   |
| Dell Latitude E6430                    | 4         | 0.32%   |
| Dell Inspiron 1545                     | 4         | 0.32%   |
| Apple MacBookAir6,2                    | 4         | 0.32%   |
| Acer Swift SF514-54T                   | 4         | 0.32%   |
| Acer Aspire One 753                    | 4         | 0.32%   |
| Valve Jupiter                          | 3         | 0.24%   |
| Toshiba Satellite P850                 | 3         | 0.24%   |
| Toshiba Satellite L750                 | 3         | 0.24%   |
| Toshiba Satellite L50-B                | 3         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 134       | 10.77%  |
| Acer Aspire        | 78        | 6.27%   |
| Toshiba Satellite  | 75        | 6.03%   |
| Dell Latitude      | 71        | 5.71%   |
| HP Pavilion        | 61        | 4.9%    |
| Dell XPS           | 53        | 4.26%   |
| Dell Inspiron      | 51        | 4.1%    |
| HP EliteBook       | 41        | 3.3%    |
| Lenovo IdeaPad     | 36        | 2.89%   |
| HP ProBook         | 29        | 2.33%   |
| HP Laptop          | 22        | 1.77%   |
| Dell Precision     | 20        | 1.61%   |
| HP ENVY            | 13        | 1.05%   |
| Lenovo Yoga        | 11        | 0.88%   |
| ASUS ZenBook       | 11        | 0.88%   |
| Acer Swift         | 11        | 0.88%   |
| HP Notebook        | 10        | 0.8%    |
| ASUS VivoBook      | 10        | 0.8%    |
| Apple MacBookPro10 | 10        | 0.8%    |
| ASUS ROG           | 9         | 0.72%   |
| Unknown            | 9         | 0.72%   |
| Toshiba PORTEGE    | 8         | 0.64%   |
| HP 250             | 8         | 0.64%   |
| Apple MacBookPro9  | 8         | 0.64%   |
| Toshiba TECRA      | 7         | 0.56%   |
| HP Compaq          | 7         | 0.56%   |
| ASUS TUF           | 7         | 0.56%   |
| Apple MacBookAir6  | 7         | 0.56%   |
| Razer Blade        | 6         | 0.48%   |
| Lenovo Legion      | 6         | 0.48%   |
| HP ZBook           | 6         | 0.48%   |
| Dell G3            | 6         | 0.48%   |
| Apple MacBookPro8  | 6         | 0.48%   |
| Apple MacBookPro11 | 6         | 0.48%   |
| Apple MacBookAir7  | 6         | 0.48%   |
| Acer Nitro         | 6         | 0.48%   |
| Acer ConceptD      | 6         | 0.48%   |
| HP Presario        | 5         | 0.4%    |
| HP OMEN            | 5         | 0.4%    |
| Apple MacBookPro6  | 5         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 123       | 9.89%   |
| 2020    | 112       | 9%      |
| 2012    | 103       | 8.28%   |
| 2011    | 101       | 8.12%   |
| 2018    | 98        | 7.88%   |
| 2013    | 94        | 7.56%   |
| 2014    | 85        | 6.83%   |
| 2021    | 80        | 6.43%   |
| 2017    | 76        | 6.11%   |
| 2010    | 73        | 5.87%   |
| 2015    | 72        | 5.79%   |
| 2016    | 71        | 5.71%   |
| 2008    | 46        | 3.7%    |
| 2009    | 38        | 3.05%   |
| 2022    | 36        | 2.89%   |
| 2007    | 20        | 1.61%   |
| 2006    | 5         | 0.4%    |
| 2005    | 5         | 0.4%    |
| Unknown | 5         | 0.4%    |
| 2003    | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1244      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1112      | 88.46%  |
| Enabled  | 145       | 11.54%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1235      | 99.28%  |
| Yes  | 9         | 0.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 351       | 27.86%  |
| 16.01-24.0  | 268       | 21.27%  |
| 3.01-4.0    | 261       | 20.71%  |
| 8.01-16.0   | 185       | 14.68%  |
| 32.01-64.0  | 105       | 8.33%   |
| 1.01-2.0    | 49        | 3.89%   |
| 64.01-256.0 | 14        | 1.11%   |
| 24.01-32.0  | 10        | 0.79%   |
| 2.01-3.0    | 10        | 0.79%   |
| 0.51-1.0    | 4         | 0.32%   |
| 0.01-0.5    | 3         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 503       | 34.98%  |
| 2.01-3.0   | 403       | 28.03%  |
| 3.01-4.0   | 179       | 12.45%  |
| 4.01-8.0   | 177       | 12.31%  |
| 0.51-1.0   | 88        | 6.12%   |
| 8.01-16.0  | 65        | 4.52%   |
| 0.01-0.5   | 15        | 1.04%   |
| 16.01-24.0 | 4         | 0.28%   |
| 24.01-32.0 | 2         | 0.14%   |
| 0          | 2         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 908       | 70.12%  |
| 2      | 303       | 23.4%   |
| 3      | 54        | 4.17%   |
| 0      | 17        | 1.31%   |
| 4      | 10        | 0.77%   |
| 5      | 2         | 0.15%   |
| 7      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 790       | 62.95%  |
| Yes       | 465       | 37.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1018      | 81.7%   |
| No        | 228       | 18.3%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1222      | 98.07%  |
| No        | 24        | 1.93%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 975       | 77.01%  |
| No        | 291       | 22.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Australia | 1244      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sydney         | 346       | 25.98%  |
| Melbourne      | 273       | 20.5%   |
| Brisbane       | 212       | 15.92%  |
| Perth          | 102       | 7.66%   |
| Adelaide       | 74        | 5.56%   |
| Canberra       | 25        | 1.88%   |
| Hobart         | 17        | 1.28%   |
| Launceston     | 7         | 0.53%   |
| Southport      | 6         | 0.45%   |
| Central Coast  | 6         | 0.45%   |
| Woolloongabba  | 5         | 0.38%   |
| Parramatta     | 5         | 0.38%   |
| Newcastle      | 5         | 0.38%   |
| Mitcham        | 5         | 0.38%   |
| Gold Coast     | 5         | 0.38%   |
| Wollongong     | 4         | 0.3%    |
| West End       | 4         | 0.3%    |
| Wahroonga      | 4         | 0.3%    |
| Traralgon      | 4         | 0.3%    |
| Point Cook     | 4         | 0.3%    |
| Mandurah       | 4         | 0.3%    |
| Geraldton      | 4         | 0.3%    |
| Artarmon       | 4         | 0.3%    |
| Alexandria     | 4         | 0.3%    |
| Townsville     | 3         | 0.23%   |
| Surry Hills    | 3         | 0.23%   |
| Spring Field   | 3         | 0.23%   |
| Richmond       | 3         | 0.23%   |
| Parkdale       | 3         | 0.23%   |
| Mount Waverley | 3         | 0.23%   |
| Hawthorn       | 3         | 0.23%   |
| Geelong        | 3         | 0.23%   |
| Doncaster      | 3         | 0.23%   |
| Clifton Hill   | 3         | 0.23%   |
| Brighton       | 3         | 0.23%   |
| Warragul       | 2         | 0.15%   |
| Sunshine Coast | 2         | 0.15%   |
| Sandy Bay      | 2         | 0.15%   |
| Ryde           | 2         | 0.15%   |
| Redfern        | 2         | 0.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 282       | 361    | 18.08%  |
| Seagate                   | 173       | 256    | 11.09%  |
| WDC                       | 169       | 243    | 10.83%  |
| Toshiba                   | 145       | 211    | 9.29%   |
| Unknown                   | 76        | 102    | 4.87%   |
| SanDisk                   | 70        | 92     | 4.49%   |
| Intel                     | 68        | 100    | 4.36%   |
| Kingston                  | 64        | 79     | 4.1%    |
| SK hynix                  | 58        | 77     | 3.72%   |
| Crucial                   | 57        | 75     | 3.65%   |
| Hitachi                   | 53        | 66     | 3.4%    |
| Apple                     | 51        | 69     | 3.27%   |
| Micron Technology         | 41        | 53     | 2.63%   |
| HGST                      | 41        | 59     | 2.63%   |
| KIOXIA                    | 20        | 22     | 1.28%   |
| Fujitsu                   | 14        | 18     | 0.9%    |
| Phison                    | 13        | 17     | 0.83%   |
| LITEON                    | 12        | 15     | 0.77%   |
| A-DATA Technology         | 10        | 13     | 0.64%   |
| Phison Electronics        | 9         | 12     | 0.58%   |
| LITEONIT                  | 8         | 10     | 0.51%   |
| SPCC                      | 6         | 8      | 0.38%   |
| OCZ                       | 6         | 8      | 0.38%   |
| JMicron Technology        | 6         | 8      | 0.38%   |
| Micron/Crucial Technology | 5         | 5      | 0.32%   |
| KingSpec                  | 5         | 8      | 0.32%   |
| ASMT                      | 5         | 7      | 0.32%   |
| Unknown                   | 5         | 6      | 0.32%   |
| Transcend                 | 4         | 6      | 0.26%   |
| Patriot                   | 4         | 6      | 0.26%   |
| China                     | 4         | 4      | 0.26%   |
| XPG                       | 3         | 3      | 0.19%   |
| OWC                       | 3         | 7      | 0.19%   |
| Lite-On                   | 3         | 3      | 0.19%   |
| LaCie                     | 3         | 7      | 0.19%   |
| USB                       | 2         | 3      | 0.13%   |
| TO Exter                  | 2         | 2      | 0.13%   |
| T-FORCE                   | 2         | 2      | 0.13%   |
| Solid State Storage       | 2         | 2      | 0.13%   |
| Realtek Semiconductor     | 2         | 3      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 18        | 1.11%   |
| Toshiba MQ01ABD100 1TB                              | 17        | 1.04%   |
| Unknown MMC Card  64GB                              | 16        | 0.98%   |
| Seagate ST500LT012-1DG142 500GB                     | 14        | 0.86%   |
| SanDisk NVMe SSD Drive 512GB                        | 14        | 0.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 14        | 0.86%   |
| Toshiba MQ01ABF050 500GB                            | 13        | 0.8%    |
| Seagate Expansion+ 2TB                              | 13        | 0.8%    |
| Samsung NVMe SSD Drive 512GB                        | 13        | 0.8%    |
| Seagate ST1000LM035-1RK172 1TB                      | 12        | 0.74%   |
| Samsung SSD 860 EVO 500GB                           | 12        | 0.74%   |
| Unknown MMC Card  32GB                              | 11        | 0.68%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 10        | 0.61%   |
| HGST HTS721010A9E630 1TB                            | 10        | 0.61%   |
| Toshiba MQ01ABD075 752GB                            | 9         | 0.55%   |
| SK hynix NVMe SSD Drive 256GB                       | 9         | 0.55%   |
| Seagate ST2000LM007-1R8174 2TB                      | 9         | 0.55%   |
| Samsung SSD 850 EVO 250GB                           | 9         | 0.55%   |
| Kingston SA400S37240G 240GB SSD                     | 9         | 0.55%   |
| Crucial CT500MX500SSD1 500GB                        | 9         | 0.55%   |
| Crucial CT1000MX500SSD1 1TB                         | 9         | 0.55%   |
| Unknown MMC Card  128GB                             | 8         | 0.49%   |
| Toshiba NVMe SSD Drive 512GB                        | 8         | 0.49%   |
| Toshiba MQ04ABF100 1TB                              | 8         | 0.49%   |
| Seagate ST9500325AS 500GB                           | 8         | 0.49%   |
| SanDisk NVMe SSD Drive 256GB                        | 8         | 0.49%   |
| Intel NVMe SSD Drive 512GB                          | 8         | 0.49%   |
| HGST HTS545050A7E680 500GB                          | 8         | 0.49%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 7         | 0.43%   |
| Unknown SD/MMC/MS PRO 64GB                          | 7         | 0.43%   |
| Unknown MMC Card  16GB                              | 7         | 0.43%   |
| Samsung SSD 850 EVO 500GB                           | 7         | 0.43%   |
| Samsung NVMe SSD Drive 500GB                        | 7         | 0.43%   |
| Micron NVMe SSD Drive 512GB                         | 7         | 0.43%   |
| Kingston SA400S37120G 120GB SSD                     | 7         | 0.43%   |
| Hitachi HTS547575A9E384 752GB                       | 7         | 0.43%   |
| Hitachi HTS545050B9A300 500GB                       | 7         | 0.43%   |
| HGST HTS725050A7E630 500GB                          | 7         | 0.43%   |
| HGST HTS541010A9E680 1TB                            | 7         | 0.43%   |
| Crucial CT1000BX500SSD1 1TB                         | 7         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 168       | 249    | 32.25%  |
| WDC                 | 116       | 168    | 22.26%  |
| Toshiba             | 90        | 139    | 17.27%  |
| Hitachi             | 53        | 66     | 10.17%  |
| HGST                | 41        | 59     | 7.87%   |
| Fujitsu             | 14        | 18     | 2.69%   |
| Samsung Electronics | 12        | 14     | 2.3%    |
| Unknown             | 7         | 7      | 1.34%   |
| Apple               | 5         | 6      | 0.96%   |
| ASMT                | 4         | 6      | 0.77%   |
| LaCie               | 3         | 6      | 0.58%   |
| KESU                | 2         | 2      | 0.38%   |
| HGST HUS            | 2         | 2      | 0.38%   |
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
| Samsung Electronics | 142       | 179    | 28.86%  |
| Crucial             | 49        | 66     | 9.96%   |
| Kingston            | 43        | 55     | 8.74%   |
| SanDisk             | 36        | 45     | 7.32%   |
| Apple               | 34        | 39     | 6.91%   |
| WDC                 | 25        | 31     | 5.08%   |
| Intel               | 24        | 42     | 4.88%   |
| Toshiba             | 22        | 30     | 4.47%   |
| SK hynix            | 19        | 25     | 3.86%   |
| Micron Technology   | 14        | 14     | 2.85%   |
| LITEON              | 11        | 14     | 2.24%   |
| LITEONIT            | 8         | 10     | 1.63%   |
| SPCC                | 6         | 8      | 1.22%   |
| OCZ                 | 6         | 8      | 1.22%   |
| A-DATA Technology   | 6         | 8      | 1.22%   |
| KingSpec            | 5         | 8      | 1.02%   |
| JMicron Technology  | 5         | 6      | 1.02%   |
| Transcend           | 4         | 6      | 0.81%   |
| Patriot             | 4         | 6      | 0.81%   |
| China               | 4         | 4      | 0.81%   |
| Seagate             | 3         | 4      | 0.61%   |
| OWC                 | 3         | 7      | 0.61%   |
| TO Exter            | 2         | 2      | 0.41%   |
| Plextor             | 2         | 6      | 0.41%   |
| FORESEE             | 2         | 2      | 0.41%   |
| SAMSWEET            | 1         | 1      | 0.2%    |
| Mushkin             | 1         | 1      | 0.2%    |
| Kston               | 1         | 1      | 0.2%    |
| Kingmax             | 1         | 1      | 0.2%    |
| KingFast            | 1         | 1      | 0.2%    |
| KingDian            | 1         | 1      | 0.2%    |
| Gigabyte Technology | 1         | 1      | 0.2%    |
| Drevo               | 1         | 1      | 0.2%    |
| Corsair             | 1         | 1      | 0.2%    |
| Colorful            | 1         | 1      | 0.2%    |
| BP4e                | 1         | 2      | 0.2%    |
| BIWIN               | 1         | 1      | 0.2%    |
| addlink             | 1         | 1      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 490       | 747    | 33.42%  |
| SSD     | 461       | 639    | 31.45%  |
| NVMe    | 420       | 606    | 28.65%  |
| MMC     | 71        | 95     | 4.84%   |
| Unknown | 24        | 26     | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 841       | 1292   | 59.35%  |
| NVMe | 420       | 603    | 29.64%  |
| SAS  | 85        | 123    | 6%      |
| MMC  | 71        | 95     | 5.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 613       | 884    | 64.19%  |
| 0.51-1.0   | 264       | 376    | 27.64%  |
| 1.01-2.0   | 60        | 98     | 6.28%   |
| 4.01-10.0  | 11        | 19     | 1.15%   |
| 3.01-4.0   | 7         | 9      | 0.73%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 358       | 26.74%  |
| 251-500        | 322       | 24.05%  |
| 501-1000       | 217       | 16.21%  |
| 1-20           | 123       | 9.19%   |
| 51-100         | 95        | 7.09%   |
| 1001-2000      | 93        | 6.95%   |
| More than 3000 | 40        | 2.99%   |
| 21-50          | 34        | 2.54%   |
| Unknown        | 30        | 2.24%   |
| 2001-3000      | 27        | 2.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 593       | 41.73%  |
| 21-50          | 265       | 18.65%  |
| 101-250        | 156       | 10.98%  |
| 51-100         | 154       | 10.84%  |
| 251-500        | 111       | 7.81%   |
| 501-1000       | 62        | 4.36%   |
| Unknown        | 30        | 2.11%   |
| 1001-2000      | 26        | 1.83%   |
| More than 3000 | 11        | 0.77%   |
| 2001-3000      | 11        | 0.77%   |
| 0              | 2         | 0.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 4      | 4.69%   |
| Toshiba MQ01ABF050 500GB                | 2         | 2      | 3.13%   |
| Seagate ST9500325AS 500GB               | 2         | 2      | 3.13%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 2      | 3.13%   |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 2      | 3.13%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 2         | 2      | 3.13%   |
| HGST HTS545050A7E680 500GB              | 2         | 3      | 3.13%   |
| WDC WD6400BEVT-22A0RT0 640GB            | 1         | 2      | 1.56%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 1         | 2      | 1.56%   |
| WDC WD5000BEVT-60ZAT1 500GB             | 1         | 3      | 1.56%   |
| WDC WD3200BPVT-22ZEST0 320GB            | 1         | 1      | 1.56%   |
| WDC WD2500BEVT-35A23T0 250GB            | 1         | 1      | 1.56%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 2      | 1.56%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 2      | 1.56%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD    | 1         | 1      | 1.56%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1      | 1.56%   |
| Toshiba MK5065GSX 500GB                 | 1         | 1      | 1.56%   |
| Toshiba MK5055GSX 500GB                 | 1         | 5      | 1.56%   |
| Toshiba MK3265GSX 320GB                 | 1         | 1      | 1.56%   |
| Seagate ST9500423AS 500GB               | 1         | 2      | 1.56%   |
| Seagate ST9500325ASG 500GB              | 1         | 1      | 1.56%   |
| Seagate ST9320423AS 320GB               | 1         | 2      | 1.56%   |
| Seagate ST9250410AS 250GB               | 1         | 1      | 1.56%   |
| Seagate ST9250315AS 250GB               | 1         | 1      | 1.56%   |
| Seagate ST9160821AS 160GB               | 1         | 5      | 1.56%   |
| Seagate ST9160310AS 160GB               | 1         | 1      | 1.56%   |
| Seagate ST500LT012-9WS142 500GB         | 1         | 2      | 1.56%   |
| Seagate ST500LM000-1EJ162 500GB         | 1         | 2      | 1.56%   |
| Seagate ST320LT007-9ZV142 320GB         | 1         | 1      | 1.56%   |
| Samsung Electronics SSD 970 EVO 2TB     | 1         | 1      | 1.56%   |
| Samsung Electronics SSD 850 EVO 1TB     | 1         | 1      | 1.56%   |
| Samsung Electronics SSD 750 EVO 250GB   | 1         | 1      | 1.56%   |
| Samsung Electronics PM961 NVMe 512GB    | 1         | 1      | 1.56%   |
| Samsung Electronics HM641JI 640GB       | 1         | 1      | 1.56%   |
| Kingston SV300S37A240G 240GB SSD        | 1         | 1      | 1.56%   |
| KingSpec PA25-128 128GB SSD             | 1         | 3      | 1.56%   |
| Intel SSDSC2CW060A3 64GB                | 1         | 2      | 1.56%   |
| Hitachi HTS725050A7E630 500GB           | 1         | 1      | 1.56%   |
| Hitachi HTS547564A9E384 640GB           | 1         | 1      | 1.56%   |
| Hitachi HTS547550A9E384 500GB           | 1         | 1      | 1.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                   | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate                  | 19        | 28     | 29.69%  |
| Hitachi                  | 8         | 8      | 12.5%   |
| WDC                      | 7         | 13     | 10.94%  |
| Toshiba                  | 7         | 11     | 10.94%  |
| Samsung Electronics      | 5         | 5      | 7.81%   |
| HGST                     | 4         | 5      | 6.25%   |
| Fujitsu                  | 4         | 4      | 6.25%   |
| Kingston                 | 3         | 3      | 4.69%   |
| Crucial                  | 2         | 2      | 3.13%   |
| KingSpec                 | 1         | 3      | 1.56%   |
| Intel                    | 1         | 2      | 1.56%   |
| Biwin Storage Technology | 1         | 1      | 1.56%   |
| Apple                    | 1         | 1      | 1.56%   |
| A-DATA Technology        | 1         | 1      | 1.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 28     | 38.78%  |
| Hitachi             | 8         | 8      | 16.33%  |
| WDC                 | 7         | 13     | 14.29%  |
| Toshiba             | 6         | 10     | 12.24%  |
| HGST                | 4         | 5      | 8.16%   |
| Fujitsu             | 4         | 4      | 8.16%   |
| Samsung Electronics | 1         | 1      | 2.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 48        | 69     | 76.19%  |
| SSD  | 12        | 15     | 19.05%  |
| NVMe | 3         | 3      | 4.76%   |

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
| Detected | 814       | 1373   | 62.38%  |
| Works    | 428       | 653    | 32.8%   |
| Malfunc  | 63        | 87     | 4.83%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 879       | 60.33%  |
| Samsung Electronics              | 152       | 10.43%  |
| AMD                              | 123       | 8.44%   |
| SanDisk                          | 61        | 4.19%   |
| SK hynix                         | 39        | 2.68%   |
| Toshiba America Info Systems     | 33        | 2.26%   |
| Micron Technology                | 27        | 1.85%   |
| Phison Electronics               | 23        | 1.58%   |
| Kingston Technology Company      | 22        | 1.51%   |
| KIOXIA                           | 18        | 1.24%   |
| Nvidia                           | 14        | 0.96%   |
| Micron/Crucial Technology        | 14        | 0.96%   |
| Apple                            | 12        | 0.82%   |
| ADATA Technology                 | 8         | 0.55%   |
| Marvell Technology Group         | 7         | 0.48%   |
| Solid State Storage Technology   | 4         | 0.27%   |
| Silicon Motion                   | 4         | 0.27%   |
| Lite-On Technology               | 4         | 0.27%   |
| Union Memory (Shenzhen)          | 2         | 0.14%   |
| Silicon Integrated Systems [SiS] | 2         | 0.14%   |
| Realtek Semiconductor            | 2         | 0.14%   |
| Lenovo                           | 2         | 0.14%   |
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
| AMD FCH SATA Controller [AHCI mode]                                            | 109       | 7.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 104       | 6.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 94        | 6.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 90        | 5.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 82        | 5.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 78        | 5.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 53        | 3.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 49        | 3.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 46        | 2.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 39        | 2.51%   |
| Intel Volume Management Device NVMe RAID Controller                            | 34        | 2.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 34        | 2.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 32        | 2.06%   |
| Micron NVMe Storage Controller                                                 | 26        | 1.68%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 24        | 1.55%   |
| Samsung NVMe SSD Controller 980                                                | 23        | 1.48%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 22        | 1.42%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 18        | 1.16%   |
| Intel SSD 660P Series                                                          | 18        | 1.16%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 16        | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 16        | 1.03%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 16        | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 15        | 0.97%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 15        | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 15        | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 14        | 0.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 14        | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                          | 12        | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 11        | 0.71%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 10        | 0.64%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 10        | 0.64%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 10        | 0.64%   |
| Samsung Electronics SATA controller                                            | 10        | 0.64%   |
| Phison PS5013 E13 NVMe Controller                                              | 10        | 0.64%   |
| Phison E12 NVMe Controller                                                     | 10        | 0.64%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 10        | 0.64%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 9         | 0.58%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 9         | 0.58%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 9         | 0.58%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 9         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 856       | 57.6%   |
| NVMe | 423       | 28.47%  |
| RAID | 132       | 8.88%   |
| IDE  | 75        | 5.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1062      | 85.37%  |
| AMD    | 180       | 14.47%  |
| ARM    | 2         | 0.16%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz       | 31        | 2.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 25        | 2.01%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 22        | 1.77%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 21        | 1.69%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 18        | 1.44%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 18        | 1.44%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 17        | 1.36%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 16        | 1.28%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 16        | 1.28%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 15        | 1.2%    |
| Intel Core i5-6300U CPU @ 2.40GHz       | 14        | 1.12%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 14        | 1.12%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 14        | 1.12%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 13        | 1.04%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 13        | 1.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 13        | 1.04%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 12        | 0.96%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 11        | 0.88%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 11        | 0.88%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 11        | 0.88%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 11        | 0.88%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 11        | 0.88%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 11        | 0.88%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 10        | 0.8%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz       | 10        | 0.8%    |
| Intel Core i5-4210U CPU @ 1.70GHz       | 10        | 0.8%    |
| Intel Core i5-3210M CPU @ 2.50GHz       | 10        | 0.8%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 10        | 0.8%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 10        | 0.8%    |
| Intel Core i7-3740QM CPU @ 2.70GHz      | 9         | 0.72%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 9         | 0.72%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 9         | 0.72%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 9         | 0.72%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 9         | 0.72%   |
| Intel Core i7-8850H CPU @ 2.60GHz       | 8         | 0.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 8         | 0.64%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 8         | 0.64%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 8         | 0.64%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 7         | 0.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 7         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 424       | 34.06%  |
| Intel Core i5                  | 310       | 24.9%   |
| Other                          | 91        | 7.31%   |
| Intel Core 2 Duo               | 55        | 4.42%   |
| Intel Core i3                  | 52        | 4.18%   |
| Intel Celeron                  | 50        | 4.02%   |
| AMD Ryzen 7                    | 36        | 2.89%   |
| AMD Ryzen 5                    | 27        | 2.17%   |
| Intel Pentium                  | 24        | 1.93%   |
| AMD A6                         | 20        | 1.61%   |
| AMD A4                         | 17        | 1.37%   |
| Intel Atom                     | 15        | 1.2%    |
| AMD Ryzen 9                    | 8         | 0.64%   |
| AMD E2                         | 8         | 0.64%   |
| Intel Pentium Dual-Core        | 7         | 0.56%   |
| Intel Core 2                   | 7         | 0.56%   |
| AMD Ryzen 7 PRO                | 7         | 0.56%   |
| AMD E1                         | 7         | 0.56%   |
| AMD A10                        | 7         | 0.56%   |
| Intel Genuine                  | 6         | 0.48%   |
| Intel Core i9                  | 6         | 0.48%   |
| AMD A8                         | 6         | 0.48%   |
| Intel Core m3                  | 5         | 0.4%    |
| Intel Core M                   | 5         | 0.4%    |
| AMD Ryzen 3                    | 5         | 0.4%    |
| Intel Xeon                     | 4         | 0.32%   |
| Intel Celeron Dual-Core        | 4         | 0.32%   |
| AMD E                          | 4         | 0.32%   |
| Intel Pentium Dual             | 3         | 0.24%   |
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
| 2      | 603       | 48.43%  |
| 4      | 419       | 33.65%  |
| 6      | 106       | 8.51%   |
| 8      | 67        | 5.38%   |
| 1      | 30        | 2.41%   |
| 14     | 8         | 0.64%   |
| 12     | 5         | 0.4%    |
| 10     | 5         | 0.4%    |
| 16     | 1         | 0.08%   |
| 5      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1242      | 99.84%  |
| 2      | 2         | 0.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 980       | 78.71%  |
| 1      | 263       | 21.12%  |
| 8      | 1         | 0.08%   |
| 4      | 1         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1218      | 97.28%  |
| 32-bit         | 17        | 1.36%   |
| Unknown        | 16        | 1.28%   |
| 64-bit         | 1         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 328       | 25.23%  |
| 0x206a7    | 84        | 6.46%   |
| 0x306a9    | 79        | 6.08%   |
| 0x40651    | 50        | 3.85%   |
| 0x906ea    | 48        | 3.69%   |
| 0x406e3    | 48        | 3.69%   |
| 0x806ec    | 40        | 3.08%   |
| 0x306d4    | 39        | 3%      |
| 0x1067a    | 39        | 3%      |
| 0x806ea    | 36        | 2.77%   |
| 0x20655    | 36        | 2.77%   |
| 0x306c3    | 34        | 2.62%   |
| 0x806c1    | 33        | 2.54%   |
| 0x806e9    | 29        | 2.23%   |
| 0xa0652    | 21        | 1.62%   |
| 0x906e9    | 21        | 1.62%   |
| 0x20652    | 19        | 1.46%   |
| 0x806eb    | 15        | 1.15%   |
| 0x0a50000c | 15        | 1.15%   |
| 0x06006705 | 15        | 1.15%   |
| 0x30678    | 14        | 1.08%   |
| 0x706e5    | 13        | 1%      |
| 0x07030105 | 13        | 1%      |
| 0x806d1    | 12        | 0.92%   |
| 0x506e3    | 12        | 0.92%   |
| 0x106e5    | 11        | 0.85%   |
| 0x0700010f | 11        | 0.85%   |
| 0x10676    | 10        | 0.77%   |
| 0x906a3    | 9         | 0.69%   |
| 0x08108109 | 9         | 0.69%   |
| 0x08108102 | 8         | 0.62%   |
| 0x6fd      | 7         | 0.54%   |
| 0x406c4    | 7         | 0.54%   |
| 0x406c3    | 7         | 0.54%   |
| 0x08600103 | 7         | 0.54%   |
| 0x06001119 | 7         | 0.54%   |
| 0x6f6      | 6         | 0.46%   |
| 0x08608103 | 6         | 0.46%   |
| 0x506c9    | 5         | 0.38%   |
| 0x08600106 | 5         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 249       | 20%     |
| IvyBridge        | 112       | 9%      |
| Haswell          | 110       | 8.84%   |
| SandyBridge      | 104       | 8.35%   |
| Skylake          | 82        | 6.59%   |
| Westmere         | 63        | 5.06%   |
| Penryn           | 60        | 4.82%   |
| Broadwell        | 47        | 3.78%   |
| TigerLake        | 40        | 3.21%   |
| CometLake        | 37        | 2.97%   |
| Silvermont       | 32        | 2.57%   |
| Unknown          | 32        | 2.57%   |
| IceLake          | 31        | 2.49%   |
| Excavator        | 27        | 2.17%   |
| Zen 2            | 21        | 1.69%   |
| Zen+             | 20        | 1.61%   |
| Zen 3            | 20        | 1.61%   |
| Core             | 20        | 1.61%   |
| Puma             | 18        | 1.45%   |
| Alderlake Hybrid | 13        | 1.04%   |
| Nehalem          | 12        | 0.96%   |
| Jaguar           | 12        | 0.96%   |
| P6               | 11        | 0.88%   |
| Goldmont plus    | 11        | 0.88%   |
| Zen              | 10        | 0.8%    |
| Piledriver       | 9         | 0.72%   |
| Bonnell          | 8         | 0.64%   |
| Goldmont         | 7         | 0.56%   |
| K10 Llano        | 6         | 0.48%   |
| K10              | 6         | 0.48%   |
| Bobcat           | 5         | 0.4%    |
| Tremont          | 3         | 0.24%   |
| Steamroller      | 3         | 0.24%   |
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
| Intel                            | 931       | 57.43%  |
| Nvidia                           | 412       | 25.42%  |
| AMD                              | 274       | 16.9%   |
| Silicon Integrated Systems [SiS] | 2         | 0.12%   |
| Neomagic                         | 2         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 98        | 5.83%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 93        | 5.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 62        | 3.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 61        | 3.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 61        | 3.63%   |
| Intel UHD Graphics 620                                                                   | 49        | 2.92%   |
| Intel Core Processor Integrated Graphics Controller                                      | 44        | 2.62%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 42        | 2.5%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 38        | 2.26%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 34        | 2.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 33        | 1.96%   |
| Intel HD Graphics 5500                                                                   | 32        | 1.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 31        | 1.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 28        | 1.67%   |
| Intel HD Graphics 620                                                                    | 26        | 1.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 23        | 1.37%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 22        | 1.31%   |
| Intel HD Graphics 630                                                                    | 21        | 1.25%   |
| AMD Renoir                                                                               | 20        | 1.19%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 19        | 1.13%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 17        | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 0.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16        | 0.95%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 15        | 0.89%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.89%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 15        | 0.89%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 14        | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 14        | 0.83%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 14        | 0.83%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 14        | 0.83%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 13        | 0.77%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 13        | 0.77%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 13        | 0.77%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 12        | 0.71%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 11        | 0.65%   |
| Intel Iris Plus Graphics G7                                                              | 11        | 0.65%   |
| Intel HD Graphics 530                                                                    | 11        | 0.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 0.65%   |
| AMD Lucienne                                                                             | 11        | 0.65%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 10        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 582       | 46.45%  |
| Intel + Nvidia           | 295       | 23.54%  |
| 1 x AMD                  | 162       | 12.93%  |
| 1 x Nvidia               | 90        | 7.18%   |
| Intel + AMD              | 48        | 3.83%   |
| 2 x AMD                  | 38        | 3.03%   |
| AMD + Nvidia             | 26        | 2.08%   |
| Other                    | 2         | 0.16%   |
| 2 x Intel                | 2         | 0.16%   |
| 1 x SiS                  | 2         | 0.16%   |
| 1 x Neomagic             | 2         | 0.16%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.16%   |
| 2 x Nvidia               | 1         | 0.08%   |
| Intel + 2 x Nvidia       | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1036      | 81%     |
| Proprietary | 203       | 15.87%  |
| Unknown     | 40        | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 791       | 61.46%  |
| 1.01-2.0   | 148       | 11.5%   |
| 0.01-0.5   | 129       | 10.02%  |
| 3.01-4.0   | 87        | 6.76%   |
| 0.51-1.0   | 77        | 5.98%   |
| 5.01-6.0   | 25        | 1.94%   |
| 7.01-8.0   | 18        | 1.4%    |
| 2.01-3.0   | 8         | 0.62%   |
| 8.01-16.0  | 4         | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 292       | 20.1%   |
| LG Display              | 207       | 14.25%  |
| Chimei Innolux          | 158       | 10.87%  |
| Samsung Electronics     | 141       | 9.7%    |
| BOE                     | 125       | 8.6%    |
| Apple                   | 82        | 5.64%   |
| Sharp                   | 63        | 4.34%   |
| Dell                    | 45        | 3.1%    |
| Chi Mei Optoelectronics | 39        | 2.68%   |
| Lenovo                  | 29        | 2%      |
| Hewlett-Packard         | 22        | 1.51%   |
| Goldstar                | 21        | 1.45%   |
| PANDA                   | 20        | 1.38%   |
| BenQ                    | 20        | 1.38%   |
| Acer                    | 19        | 1.31%   |
| Philips                 | 17        | 1.17%   |
| Sony                    | 11        | 0.76%   |
| AOC                     | 10        | 0.69%   |
| ViewSonic               | 8         | 0.55%   |
| Ancor Communications    | 8         | 0.55%   |
| Toshiba                 | 6         | 0.41%   |
| LG Philips              | 6         | 0.41%   |
| CPT                     | 6         | 0.41%   |
| Unknown                 | 5         | 0.34%   |
| Panasonic               | 5         | 0.34%   |
| LGD                     | 5         | 0.34%   |
| InfoVision              | 5         | 0.34%   |
| Hitachi                 | 5         | 0.34%   |
| SAC                     | 4         | 0.28%   |
| Kogan                   | 4         | 0.28%   |
| HannStar                | 4         | 0.28%   |
| GKK                     | 4         | 0.28%   |
| GDH                     | 4         | 0.28%   |
| eMachines               | 4         | 0.28%   |
| CSO                     | 4         | 0.28%   |
| ASUSTek Computer        | 4         | 0.28%   |
| Valve                   | 3         | 0.21%   |
| InnoLux Display         | 3         | 0.21%   |
| Unknown (XXX)           | 2         | 0.14%   |
| TMX                     | 2         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 17        | 1.14%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 11        | 0.74%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 11        | 0.74%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 10        | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 9         | 0.61%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 9         | 0.61%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 8         | 0.54%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 8         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 7         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.47%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 7         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 6         | 0.4%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch         | 6         | 0.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 6         | 0.4%    |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                     | 6         | 0.4%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 6         | 0.4%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.4%    |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 6         | 0.4%    |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 5         | 0.34%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 5         | 0.34%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 5         | 0.34%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 5         | 0.34%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 5         | 0.34%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 5         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 5         | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO1100 1366x768 256x144mm 11.6-inch | 5         | 0.34%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 5         | 0.34%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 4         | 0.27%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 4         | 0.27%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 4         | 0.27%   |
| eMachines E190HQV EMA0212 1366x768 409x230mm 18.5-inch                   | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x193mm 15.5-inch          | 4         | 0.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.27%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                    | 4         | 0.27%   |
| AU Optronics LCD Monitor AUOD0ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 520       | 38.43%  |
| 1366x768 (WXGA)    | 422       | 31.19%  |
| 3840x2160 (4K)     | 85        | 6.28%   |
| 1280x800 (WXGA)    | 57        | 4.21%   |
| 1600x900 (HD+)     | 46        | 3.4%    |
| 1440x900 (WXGA+)   | 31        | 2.29%   |
| 2560x1440 (QHD)    | 27        | 2%      |
| 1920x1200 (WUXGA)  | 21        | 1.55%   |
| 2560x1600          | 18        | 1.33%   |
| 2880x1800          | 16        | 1.18%   |
| 3840x2400          | 12        | 0.89%   |
| 1680x1050 (WSXGA+) | 12        | 0.89%   |
| 1280x1024 (SXGA)   | 10        | 0.74%   |
| 3200x1800 (QHD+)   | 9         | 0.67%   |
| 3440x1440          | 8         | 0.59%   |
| 1024x600           | 6         | 0.44%   |
| 1360x768           | 5         | 0.37%   |
| Unknown            | 5         | 0.37%   |
| 3072x1920          | 4         | 0.3%    |
| 2240x1400          | 4         | 0.3%    |
| 2160x1440          | 4         | 0.3%    |
| 800x1280           | 3         | 0.22%   |
| 3840x1080          | 3         | 0.22%   |
| 2256x1504          | 3         | 0.22%   |
| 5760x2160          | 2         | 0.15%   |
| 3456x2160          | 2         | 0.15%   |
| 3286x1080          | 2         | 0.15%   |
| 3200x2000          | 2         | 0.15%   |
| 2304x1440          | 2         | 0.15%   |
| 1280x720 (HD)      | 2         | 0.15%   |
| 1024x768 (XGA)     | 2         | 0.15%   |
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
| 15      | 584       | 40.19%  |
| 13      | 205       | 14.11%  |
| 14      | 152       | 10.46%  |
| 17      | 91        | 6.26%   |
| 27      | 61        | 4.2%    |
| 24      | 49        | 3.37%   |
| 12      | 44        | 3.03%   |
| 11      | 38        | 2.62%   |
| 23      | 37        | 2.55%   |
| 21      | 27        | 1.86%   |
| Unknown | 24        | 1.65%   |
| 31      | 19        | 1.31%   |
| 16      | 15        | 1.03%   |
| 84      | 10        | 0.69%   |
| 18      | 10        | 0.69%   |
| 72      | 9         | 0.62%   |
| 19      | 9         | 0.62%   |
| 22      | 7         | 0.48%   |
| 10      | 7         | 0.48%   |
| 52      | 6         | 0.41%   |
| 40      | 6         | 0.41%   |
| 20      | 6         | 0.41%   |
| 34      | 5         | 0.34%   |
| 54      | 4         | 0.28%   |
| 35      | 3         | 0.21%   |
| 26      | 3         | 0.21%   |
| 7       | 3         | 0.21%   |
| 48      | 2         | 0.14%   |
| 46      | 2         | 0.14%   |
| 37      | 2         | 0.14%   |
| 32      | 2         | 0.14%   |
| 8       | 2         | 0.14%   |
| 142     | 1         | 0.07%   |
| 78      | 1         | 0.07%   |
| 63      | 1         | 0.07%   |
| 55      | 1         | 0.07%   |
| 49      | 1         | 0.07%   |
| 38      | 1         | 0.07%   |
| 29      | 1         | 0.07%   |
| 25      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 810       | 56.37%  |
| 201-300        | 212       | 14.75%  |
| 501-600        | 126       | 8.77%   |
| 351-400        | 119       | 8.28%   |
| 401-500        | 53        | 3.69%   |
| 601-700        | 31        | 2.16%   |
| Unknown        | 24        | 1.67%   |
| 1501-2000      | 20        | 1.39%   |
| 1001-1500      | 17        | 1.18%   |
| 801-900        | 12        | 0.84%   |
| 701-800        | 7         | 0.49%   |
| 1-100          | 3         | 0.21%   |
| 101-200        | 2         | 0.14%   |
| More than 2000 | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1014      | 80.93%  |
| 16/10   | 173       | 13.81%  |
| Unknown | 18        | 1.44%   |
| 3/2     | 14        | 1.12%   |
| 21/9    | 9         | 0.72%   |
| 5/4     | 8         | 0.64%   |
| 4/3     | 6         | 0.48%   |
| 32/9    | 4         | 0.32%   |
| 0.67    | 3         | 0.24%   |
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
| 101-110        | 584       | 40.39%  |
| 81-90          | 270       | 18.67%  |
| 201-250        | 100       | 6.92%   |
| 71-80          | 90        | 6.22%   |
| 121-130        | 80        | 5.53%   |
| 301-350        | 63        | 4.36%   |
| 61-70          | 40        | 2.77%   |
| 51-60          | 39        | 2.7%    |
| More than 1000 | 32        | 2.21%   |
| 351-500        | 29        | 2.01%   |
| 151-200        | 24        | 1.66%   |
| Unknown        | 24        | 1.66%   |
| 111-120        | 14        | 0.97%   |
| 501-1000       | 14        | 0.97%   |
| 251-300        | 10        | 0.69%   |
| 141-150        | 10        | 0.69%   |
| 41-50          | 8         | 0.55%   |
| 131-140        | 8         | 0.55%   |
| 1-40           | 5         | 0.35%   |
| 91-100         | 2         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 509       | 36.23%  |
| 101-120       | 417       | 29.68%  |
| 51-100        | 235       | 16.73%  |
| 161-240       | 113       | 8.04%   |
| More than 240 | 80        | 5.69%   |
| 1-50          | 27        | 1.92%   |
| Unknown       | 24        | 1.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1007      | 77.52%  |
| 2     | 215       | 16.55%  |
| 0     | 39        | 3%      |
| 3     | 33        | 2.54%   |
| 4     | 5         | 0.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 682       | 33.46%  |
| Realtek Semiconductor             | 629       | 30.86%  |
| Qualcomm Atheros                  | 279       | 13.69%  |
| Broadcom                          | 152       | 7.46%   |
| Broadcom Limited                  | 48        | 2.36%   |
| Ralink                            | 25        | 1.23%   |
| Sierra Wireless                   | 18        | 0.88%   |
| MediaTek                          | 17        | 0.83%   |
| Marvell Technology Group          | 16        | 0.79%   |
| DisplayLink                       | 14        | 0.69%   |
| Samsung Electronics               | 12        | 0.59%   |
| Dell                              | 12        | 0.59%   |
| Huawei Technologies               | 10        | 0.49%   |
| Nvidia                            | 9         | 0.44%   |
| Apple                             | 9         | 0.44%   |
| NetGear                           | 8         | 0.39%   |
| ZTE WCDMA Technologies MSM        | 7         | 0.34%   |
| TP-Link                           | 7         | 0.34%   |
| Ralink Technology                 | 7         | 0.34%   |
| Lenovo                            | 7         | 0.34%   |
| Hewlett-Packard                   | 7         | 0.34%   |
| Edimax Technology                 | 7         | 0.34%   |
| ASIX Electronics                  | 6         | 0.29%   |
| OPPO Electronics                  | 5         | 0.25%   |
| Google                            | 4         | 0.2%    |
| ASUSTek Computer                  | 4         | 0.2%    |
| Qualcomm                          | 3         | 0.15%   |
| Motorola PCS                      | 3         | 0.15%   |
| JMicron Technology                | 3         | 0.15%   |
| Ericsson Business Mobile Networks | 3         | 0.15%   |
| Xiaomi                            | 2         | 0.1%    |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 377       | 15.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 112       | 4.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 69        | 2.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 62        | 2.53%   |
| Intel Wi-Fi 6 AX200                                               | 55        | 2.25%   |
| Intel Wireless 8260                                               | 48        | 1.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 44        | 1.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 44        | 1.8%    |
| Intel Wireless 8265 / 8275                                        | 44        | 1.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 40        | 1.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 38        | 1.55%   |
| Intel Wireless 7260                                               | 37        | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 35        | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 33        | 1.35%   |
| Intel Wi-Fi 6 AX201                                               | 32        | 1.31%   |
| Intel Centrino Ultimate-N 6300                                    | 32        | 1.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 31        | 1.27%   |
| Intel Wireless 3165                                               | 30        | 1.23%   |
| Intel Wireless 7265                                               | 29        | 1.19%   |
| Intel Ethernet Connection I219-LM                                 | 26        | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 25        | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 24        | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 23        | 0.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 22        | 0.9%    |
| Intel Wireless-AC 9260                                            | 20        | 0.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 20        | 0.82%   |
| Intel 82577LM Gigabit Network Connection                          | 19        | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 18        | 0.74%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 17        | 0.69%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 17        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 0.65%   |
| Intel Wireless 3160                                               | 16        | 0.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 16        | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 0.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 16        | 0.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 16        | 0.65%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 15        | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 14        | 0.57%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 14        | 0.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 14        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 660       | 50.69%  |
| Qualcomm Atheros                | 234       | 17.97%  |
| Realtek Semiconductor           | 137       | 10.52%  |
| Broadcom                        | 124       | 9.52%   |
| Broadcom Limited                | 39        | 3%      |
| Ralink                          | 25        | 1.92%   |
| Sierra Wireless                 | 18        | 1.38%   |
| MediaTek                        | 16        | 1.23%   |
| NetGear                         | 8         | 0.61%   |
| Ralink Technology               | 7         | 0.54%   |
| Edimax Technology               | 7         | 0.54%   |
| Dell                            | 7         | 0.54%   |
| TP-Link                         | 6         | 0.46%   |
| ASUSTek Computer                | 4         | 0.31%   |
| Qualcomm Atheros Communications | 2         | 0.15%   |
| Qualcomm                        | 2         | 0.15%   |
| D-Link                          | 2         | 0.15%   |
| Xiaomi                          | 1         | 0.08%   |
| Wilocity                        | 1         | 0.08%   |
| Hewlett-Packard                 | 1         | 0.08%   |
| Belkin Components               | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 55        | 4.2%    |
| Intel Wireless 8260                                            | 48        | 3.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 44        | 3.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 44        | 3.36%   |
| Intel Wireless 8265 / 8275                                     | 44        | 3.36%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 40        | 3.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 38        | 2.9%    |
| Intel Wireless 7260                                            | 37        | 2.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 35        | 2.67%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 33        | 2.52%   |
| Intel Wi-Fi 6 AX201                                            | 32        | 2.44%   |
| Intel Centrino Ultimate-N 6300                                 | 32        | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 31        | 2.37%   |
| Intel Wireless 3165                                            | 30        | 2.29%   |
| Intel Wireless 7265                                            | 29        | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 25        | 1.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 24        | 1.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 23        | 1.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 22        | 1.68%   |
| Intel Wireless-AC 9260                                         | 20        | 1.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 20        | 1.53%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 18        | 1.38%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 17        | 1.3%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 17        | 1.3%    |
| Intel Wireless 3160                                            | 16        | 1.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 16        | 1.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 16        | 1.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 16        | 1.22%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 15        | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 14        | 1.07%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 14        | 1.07%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 14        | 1.07%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 13        | 0.99%   |
| Intel Centrino Advanced-N 6200                                 | 13        | 0.99%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 12        | 0.92%   |
| Broadcom BCM43142 802.11b/g/n                                  | 12        | 0.92%   |
| Intel WiFi Link 5100                                           | 11        | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 11        | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 0.76%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 10        | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 572       | 52.72%  |
| Intel                            | 243       | 22.4%   |
| Qualcomm Atheros                 | 86        | 7.93%   |
| Broadcom                         | 64        | 5.9%    |
| Marvell Technology Group         | 16        | 1.47%   |
| DisplayLink                      | 14        | 1.29%   |
| Samsung Electronics              | 12        | 1.11%   |
| Nvidia                           | 9         | 0.83%   |
| Broadcom Limited                 | 9         | 0.83%   |
| Apple                            | 9         | 0.83%   |
| ZTE WCDMA Technologies MSM       | 7         | 0.65%   |
| Lenovo                           | 7         | 0.65%   |
| Huawei Technologies              | 7         | 0.65%   |
| ASIX Electronics                 | 6         | 0.55%   |
| OPPO Electronics                 | 5         | 0.46%   |
| Google                           | 4         | 0.37%   |
| JMicron Technology               | 3         | 0.28%   |
| Silicon Integrated Systems [SiS] | 2         | 0.18%   |
| ICS Advent                       | 2         | 0.18%   |
| Hewlett-Packard                  | 2         | 0.18%   |
| Xiaomi                           | 1         | 0.09%   |
| T & A Mobile Phones              | 1         | 0.09%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 377       | 34.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 112       | 10.14%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 69        | 6.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 62        | 5.62%   |
| Intel Ethernet Connection I219-LM                                 | 26        | 2.36%   |
| Intel 82577LM Gigabit Network Connection                          | 19        | 1.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 16        | 1.45%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 1.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 14        | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 1.09%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 1%      |
| Intel Ethernet Connection I218-LM                                 | 11        | 1%      |
| Intel Ethernet Connection (4) I219-V                              | 11        | 1%      |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 11        | 1%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 9         | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.82%   |
| Intel Ethernet Connection I219-V                                  | 9         | 0.82%   |
| Intel 82567LM Gigabit Network Connection                          | 9         | 0.82%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 9         | 0.82%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 9         | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 8         | 0.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7         | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 7         | 0.63%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 7         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 0.54%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 6         | 0.54%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.54%   |
| Realtek Killer E3000 2.5GbE Controller                            | 5         | 0.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 0.45%   |
| OPPO RMX3263                                                      | 5         | 0.45%   |
| Nvidia MCP79 Ethernet                                             | 5         | 0.45%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 5         | 0.45%   |
| DisplayLink Dell Universal Dock D6000                             | 5         | 0.45%   |
| ASIX AX88179 Gigabit Ethernet                                     | 5         | 0.45%   |
| ZTE WCDMA MSM ZTE BLADE A530                                      | 4         | 0.36%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 4         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1222      | 53.88%  |
| Ethernet | 1013      | 44.66%  |
| Modem    | 30        | 1.32%   |
| Unknown  | 3         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1014      | 78.24%  |
| Ethernet | 282       | 21.76%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 920       | 73.72%  |
| 1     | 307       | 24.6%   |
| 0     | 12        | 0.96%   |
| 3     | 9         | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1112      | 87.84%  |
| Yes  | 154       | 12.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 492       | 49.8%   |
| Qualcomm Atheros Communications | 83        | 8.4%    |
| Apple                           | 70        | 7.09%   |
| Broadcom                        | 68        | 6.88%   |
| Realtek Semiconductor           | 53        | 5.36%   |
| Lite-On Technology              | 38        | 3.85%   |
| IMC Networks                    | 36        | 3.64%   |
| Foxconn / Hon Hai               | 35        | 3.54%   |
| Toshiba                         | 34        | 3.44%   |
| Hewlett-Packard                 | 18        | 1.82%   |
| Dell                            | 16        | 1.62%   |
| Ralink                          | 14        | 1.42%   |
| Cambridge Silicon Radio         | 7         | 0.71%   |
| Alps Electric                   | 6         | 0.61%   |
| Realtek                         | 5         | 0.51%   |
| ASUSTek Computer                | 5         | 0.51%   |
| Ralink Technology               | 3         | 0.3%    |
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
| Intel Bluetooth wireless interface                  | 192       | 19.43%  |
| Intel AX201 Bluetooth                               | 102       | 10.32%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 59        | 5.97%   |
| Intel AX200 Bluetooth                               | 56        | 5.67%   |
| Apple Bluetooth Host Controller                     | 37        | 3.74%   |
| Qualcomm Atheros  Bluetooth Device                  | 33        | 3.34%   |
| Realtek Bluetooth Radio                             | 27        | 2.73%   |
| Apple Bluetooth USB Host Controller                 | 26        | 2.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 20        | 2.02%   |
| Realtek  Bluetooth 4.2 Adapter                      | 18        | 1.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 18        | 1.82%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 17        | 1.72%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 16        | 1.62%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 1.62%   |
| Ralink RT3290 Bluetooth                             | 14        | 1.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 1.42%   |
| Intel Bluetooth Device                              | 14        | 1.42%   |
| Intel AX210 Bluetooth                               | 14        | 1.42%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 1.32%   |
| Toshiba Bluetooth Device                            | 12        | 1.21%   |
| Lite-On Atheros AR3012 Bluetooth                    | 12        | 1.21%   |
| IMC Networks Bluetooth Radio                        | 12        | 1.21%   |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 1.11%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 10        | 1.01%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 9         | 0.91%   |
| Lite-On Bluetooth Device                            | 9         | 0.91%   |
| Toshiba Integrated Bluetooth HCI                    | 8         | 0.81%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 0.81%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.81%   |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 0.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 0.71%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.71%   |
| Foxconn / Hon Hai Wireless_Device                   | 6         | 0.61%   |
| Dell DW375 Bluetooth Module                         | 6         | 0.61%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 6         | 0.61%   |
| Realtek Bluetooth Radio                             | 5         | 0.51%   |
| IMC Networks Wireless_Device                        | 5         | 0.51%   |
| IMC Networks Bluetooth                              | 5         | 0.51%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1032      | 63.66%  |
| Nvidia                                       | 228       | 14.07%  |
| AMD                                          | 226       | 13.94%  |
| Realtek Semiconductor                        | 18        | 1.11%   |
| Apple                                        | 8         | 0.49%   |
| Logitech                                     | 7         | 0.43%   |
| Razer USA                                    | 6         | 0.37%   |
| Lenovo                                       | 6         | 0.37%   |
| GN Netcom                                    | 6         | 0.37%   |
| Creative Technology                          | 6         | 0.37%   |
| C-Media Electronics                          | 6         | 0.37%   |
| Kingston Technology                          | 5         | 0.31%   |
| Generalplus Technology                       | 5         | 0.31%   |
| Texas Instruments                            | 4         | 0.25%   |
| JMTek                                        | 4         | 0.25%   |
| Hewlett-Packard                              | 4         | 0.25%   |
| Plantronics                                  | 3         | 0.19%   |
| OPPO Electronics                             | 3         | 0.19%   |
| Microsoft                                    | 3         | 0.19%   |
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
| Intel Sunrise Point-LP HD Audio                                            | 150       | 7.76%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 125       | 6.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 90        | 4.65%   |
| AMD Family 17h/19h HD Audio Controller                                     | 85        | 4.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 75        | 3.88%   |
| Intel Cannon Lake PCH cAVS                                                 | 66        | 3.41%   |
| Intel 8 Series HD Audio Controller                                         | 63        | 3.26%   |
| Intel Haswell-ULT HD Audio Controller                                      | 62        | 3.21%   |
| AMD FCH Azalia Controller                                                  | 49        | 2.53%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 47        | 2.43%   |
| Intel Broadwell-U Audio Controller                                         | 47        | 2.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 47        | 2.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 44        | 2.28%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 42        | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 40        | 2.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 40        | 2.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 37        | 1.91%   |
| Intel Comet Lake PCH cAVS                                                  | 36        | 1.86%   |
| AMD Kabini HDMI/DP Audio                                                   | 35        | 1.81%   |
| Intel Comet Lake PCH-LP cAVS                                               | 31        | 1.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 27        | 1.4%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 27        | 1.4%    |
| Intel CM238 HD Audio Controller                                            | 26        | 1.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 23        | 1.19%   |
| Nvidia GF108 High Definition Audio Controller                              | 22        | 1.14%   |
| AMD High Definition Audio Controller                                       | 22        | 1.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 21        | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                         | 19        | 0.98%   |
| Nvidia TU106 High Definition Audio Controller                              | 18        | 0.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 18        | 0.93%   |
| Realtek Semiconductor USB Audio                                            | 16        | 0.83%   |
| Nvidia TU116 High Definition Audio Controller                              | 16        | 0.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 16        | 0.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 16        | 0.83%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 16        | 0.83%   |
| Nvidia GT216 HDMI Audio Controller                                         | 15        | 0.78%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 15        | 0.78%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14        | 0.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 14        | 0.72%   |
| Nvidia GP104 High Definition Audio Controller                              | 12        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 221       | 31.94%  |
| SK hynix                   | 180       | 26.01%  |
| Micron Technology          | 97        | 14.02%  |
| Kingston                   | 59        | 8.53%   |
| Crucial                    | 34        | 4.91%   |
| Unknown                    | 21        | 3.03%   |
| Elpida                     | 16        | 2.31%   |
| Ramaxel Technology         | 11        | 1.59%   |
| Nanya Technology           | 8         | 1.16%   |
| Team                       | 7         | 1.01%   |
| Corsair                    | 7         | 1.01%   |
| A-DATA Technology          | 5         | 0.72%   |
| G.Skill                    | 3         | 0.43%   |
| Apacer                     | 3         | 0.43%   |
| Toshiba                    | 2         | 0.29%   |
| Smart                      | 2         | 0.29%   |
| Silicon Power              | 2         | 0.29%   |
| Unknown                    | 2         | 0.29%   |
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
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 17        | 2.29%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 1.62%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 11        | 1.48%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 1.35%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 1.21%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 1.21%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 1.08%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.94%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.94%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.94%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.94%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 7         | 0.94%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.94%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 0.81%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.81%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.81%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.81%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 6         | 0.81%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 6         | 0.81%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 6         | 0.81%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.67%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.67%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 5         | 0.67%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.54%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 4         | 0.54%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 0.54%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 4         | 0.54%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 0.54%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.54%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 4         | 0.54%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 4         | 0.54%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.54%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 4         | 0.54%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s       | 4         | 0.54%   |
| Micron RAM 8ATF1G64HZ-2G6D1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.54%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 4         | 0.54%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 4         | 0.54%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 4         | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 265       | 43.8%   |
| DDR3    | 233       | 38.51%  |
| LPDDR3  | 42        | 6.94%   |
| LPDDR4  | 20        | 3.31%   |
| DDR2    | 20        | 3.31%   |
| SDRAM   | 9         | 1.49%   |
| DDR5    | 7         | 1.16%   |
| LPDDR5  | 6         | 0.99%   |
| DRAM    | 1         | 0.17%   |
| DDR     | 1         | 0.17%   |
| Unknown | 1         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 529       | 87.15%  |
| Row Of Chips | 68        | 11.2%   |
| Chip         | 7         | 1.15%   |
| Unknown      | 2         | 0.33%   |
| DIMM         | 1         | 0.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 236       | 36.99%  |
| 4096  | 193       | 30.25%  |
| 16384 | 101       | 15.83%  |
| 2048  | 73        | 11.44%  |
| 32768 | 22        | 3.45%   |
| 1024  | 9         | 1.41%   |
| 512   | 3         | 0.47%   |
| 256   | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 169       | 26.04%  |
| 2667    | 137       | 21.11%  |
| 3200    | 95        | 14.64%  |
| 1334    | 42        | 6.47%   |
| 2133    | 40        | 6.16%   |
| 2400    | 32        | 4.93%   |
| 1067    | 17        | 2.62%   |
| 1333    | 15        | 2.31%   |
| 1867    | 14        | 2.16%   |
| 4800    | 11        | 1.69%   |
| 667     | 10        | 1.54%   |
| 4267    | 9         | 1.39%   |
| Unknown | 9         | 1.39%   |
| 8400    | 7         | 1.08%   |
| 3266    | 7         | 1.08%   |
| 1066    | 7         | 1.08%   |
| 6400    | 6         | 0.92%   |
| 800     | 6         | 0.92%   |
| 4266    | 4         | 0.62%   |
| 2048    | 4         | 0.62%   |
| 4199    | 3         | 0.46%   |
| 3733    | 2         | 0.31%   |
| 975     | 2         | 0.31%   |
| 533     | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 3         | 42.86%  |
| Canon               | 2         | 28.57%  |
| Samsung Electronics | 1         | 14.29%  |
| Hewlett-Packard     | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Canon TS3100 series    | 2         | 28.57%  |
| Samsung ML-1865        | 1         | 14.29%  |
| HP DeskJet 2300 series | 1         | 14.29%  |
| Brother MFC-1810       | 1         | 14.29%  |
| Brother HL-2140 series | 1         | 14.29%  |
| Brother HL-1110 series | 1         | 14.29%  |

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
| Chicony Electronics                    | 305       | 26.48%  |
| Microdia                               | 110       | 9.55%   |
| Realtek Semiconductor                  | 102       | 8.85%   |
| IMC Networks                           | 94        | 8.16%   |
| Sunplus Innovation Technology          | 88        | 7.64%   |
| Apple                                  | 66        | 5.73%   |
| Acer                                   | 65        | 5.64%   |
| Quanta                                 | 48        | 4.17%   |
| Suyin                                  | 45        | 3.91%   |
| Cheng Uei Precision Industry (Foxlink) | 45        | 3.91%   |
| Logitech                               | 28        | 2.43%   |
| Lite-On Technology                     | 20        | 1.74%   |
| Syntek                                 | 15        | 1.3%    |
| Luxvisions Innotech Limited            | 13        | 1.13%   |
| Samsung Electronics                    | 11        | 0.95%   |
| Silicon Motion                         | 10        | 0.87%   |
| Importek                               | 10        | 0.87%   |
| Ricoh                                  | 9         | 0.78%   |
| Primax Electronics                     | 7         | 0.61%   |
| Lenovo                                 | 7         | 0.61%   |
| Alcor Micro                            | 6         | 0.52%   |
| Magic Control Technology               | 4         | 0.35%   |
| DigiTech                               | 4         | 0.35%   |
| Bison Electronics                      | 4         | 0.35%   |
| Razer USA                              | 3         | 0.26%   |
| OmniVision Technologies                | 3         | 0.26%   |
| LG Electronics                         | 3         | 0.26%   |
| ALi                                    | 3         | 0.26%   |
| Z-Star Microelectronics                | 2         | 0.17%   |
| SunplusIT                              | 2         | 0.17%   |
| Sonix Technology                       | 2         | 0.17%   |
| OPPO Electronics                       | 2         | 0.17%   |
| Genesys Logic                          | 2         | 0.17%   |
| GEMBIRD                                | 2         | 0.17%   |
| USB Camera                             | 1         | 0.09%   |
| Tobii Technology AB                    | 1         | 0.09%   |
| Sunplus Technology                     | 1         | 0.09%   |
| Solid Year                             | 1         | 0.09%   |
| Mimaki Engineering                     | 1         | 0.09%   |
| Microsoft                              | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 62        | 5.31%   |
| Chicony Integrated Camera                               | 55        | 4.71%   |
| Realtek Integrated_Webcam_HD                            | 32        | 2.74%   |
| Chicony HD Webcam                                       | 28        | 2.4%    |
| Sunplus Integrated_Webcam_HD                            | 24        | 2.06%   |
| Chicony TOSHIBA Web Camera - HD                         | 24        | 2.06%   |
| IMC Networks Integrated Camera                          | 23        | 1.97%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 22        | 1.89%   |
| Chicony HP TrueVision HD Camera                         | 17        | 1.46%   |
| Apple FaceTime HD Camera (Built-in)                     | 17        | 1.46%   |
| Apple Built-in iSight                                   | 17        | 1.46%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 14        | 1.2%    |
| Chicony HP Truevision HD                                | 13        | 1.11%   |
| Apple FaceTime HD Camera                                | 13        | 1.11%   |
| Acer Integrated Camera                                  | 13        | 1.11%   |
| Sunplus HD WebCam                                       | 12        | 1.03%   |
| Realtek USB Camera                                      | 12        | 1.03%   |
| Chicony USB 2.0 Camera                                  | 12        | 1.03%   |
| Chicony HD User Facing                                  | 12        | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 12        | 1.03%   |
| Samsung Galaxy A5 (MTP)                                 | 11        | 0.94%   |
| Quanta HD User Facing                                   | 11        | 0.94%   |
| Chicony USB2.0 Camera                                   | 11        | 0.94%   |
| Lite-On Integrated Camera                               | 10        | 0.86%   |
| Chicony CNF9055 Toshiba Webcam                          | 10        | 0.86%   |
| Syntek Integrated Camera                                | 9         | 0.77%   |
| Suyin HP Truevision HD                                  | 9         | 0.77%   |
| Quanta HP TrueVision HD Camera                          | 9         | 0.77%   |
| Microdia Integrated Webcam                              | 9         | 0.77%   |
| Chicony HP HD Camera                                    | 9         | 0.77%   |
| Acer HD Webcam                                          | 9         | 0.77%   |
| Quanta HD Webcam                                        | 8         | 0.69%   |
| Realtek USB2.0-Camera                                   | 7         | 0.6%    |
| Realtek USB2.0 HD UVC WebCam                            | 7         | 0.6%    |
| Logitech Webcam C270                                    | 7         | 0.6%    |
| Chicony Integrated Camera (1280x720@30)                 | 7         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 7         | 0.6%    |
| Acer EasyCamera                                         | 7         | 0.6%    |
| Sunplus Asus Webcam                                     | 6         | 0.51%   |
| Quanta HP Webcam                                        | 6         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 104       | 41.94%  |
| Synaptics                  | 50        | 20.16%  |
| Shenzhen Goodix Technology | 29        | 11.69%  |
| LighTuning Technology      | 19        | 7.66%   |
| AuthenTec                  | 15        | 6.05%   |
| Upek                       | 14        | 5.65%   |
| Elan Microelectronics      | 10        | 4.03%   |
| STMicroelectronics         | 6         | 2.42%   |
| Focal-systems.Corp         | 1         | 0.4%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 8.47%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 7.66%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 14        | 5.65%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 5.24%   |
| Validity Sensors VFS491                                                    | 10        | 4.03%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 4.03%   |
| Shenzhen Goodix  Fingerprint Device                                        | 10        | 4.03%   |
| Shenzhen Goodix FingerPrint                                                | 10        | 4.03%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 3.63%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 3.63%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 3.23%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 2.82%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 2.82%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 2.82%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 2.82%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 2.42%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 2.42%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.42%   |
| Elan ELAN:Fingerprint                                                      | 6         | 2.42%   |
| Synaptics WBDI Device                                                      | 5         | 2.02%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 2.02%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 2.02%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.61%   |
| Synaptics UWP WBDI                                                         | 4         | 1.61%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.61%   |
| AuthenTec AES1600                                                          | 4         | 1.61%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.21%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1.21%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 1.21%   |
| Synaptics  WBDI                                                            | 3         | 1.21%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.21%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.21%   |
| AuthenTec AES2810                                                          | 2         | 0.81%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.4%    |
| Synaptics UWP WBDI Device                                                  | 1         | 0.4%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.4%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.4%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.4%    |
| LighTuning Fingerprint Reader                                              | 1         | 0.4%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 33        | 61.11%  |
| Alcor Micro           | 11        | 20.37%  |
| Upek                  | 4         | 7.41%   |
| Lenovo                | 3         | 5.56%   |
| O2 Micro              | 2         | 3.7%    |
| Advanced Card Systems | 1         | 1.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 16        | 29.63%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 20.37%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 11.11%  |
| Broadcom 58200                                                               | 6         | 11.11%  |
| Broadcom 5880                                                                | 5         | 9.26%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 7.41%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 5.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.7%    |
| Advanced Card Systems ACR122U                                                | 1         | 1.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 763       | 58.69%  |
| 1     | 431       | 33.15%  |
| 2     | 87        | 6.69%   |
| 3     | 12        | 0.92%   |
| 4     | 6         | 0.46%   |
| 5     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 247       | 39.33%  |
| Graphics card            | 142       | 22.61%  |
| Net/wireless             | 53        | 8.44%   |
| Chipcard                 | 49        | 7.8%    |
| Multimedia controller    | 40        | 6.37%   |
| Camera                   | 21        | 3.34%   |
| Bluetooth                | 21        | 3.34%   |
| Communication controller | 12        | 1.91%   |
| Storage                  | 10        | 1.59%   |
| Net/ethernet             | 10        | 1.59%   |
| Modem                    | 8         | 1.27%   |
| Sound                    | 6         | 0.96%   |
| Card reader              | 6         | 0.96%   |
| Unassigned class         | 1         | 0.16%   |
| Storage/ide              | 1         | 0.16%   |
| Storage/ata              | 1         | 0.16%   |

