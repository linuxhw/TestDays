Debian 11 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 11 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

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
| HP            | 630                         | [428ee9672e](https://linux-hardware.org/?probe=428ee9672e) | Aug 07, 2021 |
| Lenovo        | ThinkPad P17 Gen 1 20SNZ... | [669874ee19](https://linux-hardware.org/?probe=669874ee19) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | [ad24cf2899](https://linux-hardware.org/?probe=ad24cf2899) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | [9f994fc086](https://linux-hardware.org/?probe=9f994fc086) | Aug 07, 2021 |
| Apple         | MacBookAir7,1               | [e2b8c558f7](https://linux-hardware.org/?probe=e2b8c558f7) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | [8cc604abc2](https://linux-hardware.org/?probe=8cc604abc2) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [c9c4b53460](https://linux-hardware.org/?probe=c9c4b53460) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | [f54c45ab89](https://linux-hardware.org/?probe=f54c45ab89) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [81fef8f548](https://linux-hardware.org/?probe=81fef8f548) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | [4e000b3710](https://linux-hardware.org/?probe=4e000b3710) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | [493e2762bc](https://linux-hardware.org/?probe=493e2762bc) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [2eb3a16b53](https://linux-hardware.org/?probe=2eb3a16b53) | Aug 06, 2021 |
| Dell          | Precision 3540              | [1b8206cd29](https://linux-hardware.org/?probe=1b8206cd29) | Aug 06, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [10811e8109](https://linux-hardware.org/?probe=10811e8109) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [bba0c0a13c](https://linux-hardware.org/?probe=bba0c0a13c) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [25f1a5ecdf](https://linux-hardware.org/?probe=25f1a5ecdf) | Aug 06, 2021 |
| HP            | EliteBook 8460p             | [a7114078e2](https://linux-hardware.org/?probe=a7114078e2) | Aug 06, 2021 |
| Lenovo        | ThinkPad W520 4284CY1       | [5e1c9e9e30](https://linux-hardware.org/?probe=5e1c9e9e30) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [639bb0ca17](https://linux-hardware.org/?probe=639bb0ca17) | Aug 06, 2021 |
| Dell          | G3 3579                     | [5a268dbc14](https://linux-hardware.org/?probe=5a268dbc14) | Aug 06, 2021 |
| Dell          | G3 3579                     | [6aae1a533f](https://linux-hardware.org/?probe=6aae1a533f) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [41d352c625](https://linux-hardware.org/?probe=41d352c625) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | [3256d646b0](https://linux-hardware.org/?probe=3256d646b0) | Aug 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [f7718b0dfe](https://linux-hardware.org/?probe=f7718b0dfe) | Aug 06, 2021 |
| Dell          | Latitude E7240              | [4dd840f3dd](https://linux-hardware.org/?probe=4dd840f3dd) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | [64b6992b74](https://linux-hardware.org/?probe=64b6992b74) | Aug 06, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [f8727e28db](https://linux-hardware.org/?probe=f8727e28db) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | [249a58dd07](https://linux-hardware.org/?probe=249a58dd07) | Aug 05, 2021 |
| Apple         | MacBookAir7,2               | [fa1f3da353](https://linux-hardware.org/?probe=fa1f3da353) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | [812e20e37e](https://linux-hardware.org/?probe=812e20e37e) | Aug 05, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [b90c18f9a0](https://linux-hardware.org/?probe=b90c18f9a0) | Aug 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [393c8e4faa](https://linux-hardware.org/?probe=393c8e4faa) | Aug 05, 2021 |
| Apple         | MacBook2,1                  | [103dba0476](https://linux-hardware.org/?probe=103dba0476) | Aug 05, 2021 |
| HP            | ProBook 6450b               | [ec02a5333b](https://linux-hardware.org/?probe=ec02a5333b) | Aug 05, 2021 |
| HP            | 3085B                       | [6be769f55c](https://linux-hardware.org/?probe=6be769f55c) | Aug 05, 2021 |
| Apple         | MacBook5,2                  | [0a79f49420](https://linux-hardware.org/?probe=0a79f49420) | Aug 05, 2021 |
| HP            | Pavilion dm4                | [7ba854b03e](https://linux-hardware.org/?probe=7ba854b03e) | Aug 05, 2021 |
| Clevo         | W240HU/W250HUQ              | [f71032cd7f](https://linux-hardware.org/?probe=f71032cd7f) | Aug 05, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| Apple         | MacBook7,1                  | [a0e7632e28](https://linux-hardware.org/?probe=a0e7632e28) | Aug 04, 2021 |
| Apple         | MacBook5,2                  | [803a6be591](https://linux-hardware.org/?probe=803a6be591) | Aug 04, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [cca5aa2900](https://linux-hardware.org/?probe=cca5aa2900) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [2c8c33becf](https://linux-hardware.org/?probe=2c8c33becf) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [97f8f86784](https://linux-hardware.org/?probe=97f8f86784) | Aug 04, 2021 |
| Notebook      | NJ50_70CU                   | [a9b3790d07](https://linux-hardware.org/?probe=a9b3790d07) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [2d764714a4](https://linux-hardware.org/?probe=2d764714a4) | Aug 04, 2021 |
| Acer          | Aspire E5-571G              | [b2a62f65d6](https://linux-hardware.org/?probe=b2a62f65d6) | Aug 04, 2021 |
| HP            | EliteBook 8460p             | [09a6257403](https://linux-hardware.org/?probe=09a6257403) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [eafaf5ece3](https://linux-hardware.org/?probe=eafaf5ece3) | Aug 04, 2021 |
| ASUSTek       | N53Ta                       | [896a02b57b](https://linux-hardware.org/?probe=896a02b57b) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [c0bf2b7b10](https://linux-hardware.org/?probe=c0bf2b7b10) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [3d29b58c58](https://linux-hardware.org/?probe=3d29b58c58) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [8b35a81ed6](https://linux-hardware.org/?probe=8b35a81ed6) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | [87bca8ecbc](https://linux-hardware.org/?probe=87bca8ecbc) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | [fbbd748072](https://linux-hardware.org/?probe=fbbd748072) | Aug 03, 2021 |
| Apple         | MacBook4,1                  | [71738ebf7e](https://linux-hardware.org/?probe=71738ebf7e) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | [06d86172a1](https://linux-hardware.org/?probe=06d86172a1) | Aug 03, 2021 |
| HP            | EliteBook 8460p             | [aa415746d6](https://linux-hardware.org/?probe=aa415746d6) | Aug 03, 2021 |
| Apple         | MacBookAir7,1               | [c8674581d0](https://linux-hardware.org/?probe=c8674581d0) | Aug 03, 2021 |
| Dell          | Latitude E4310              | [75a9aa20f2](https://linux-hardware.org/?probe=75a9aa20f2) | Aug 03, 2021 |
| Google        | Enguarde                    | [c758164470](https://linux-hardware.org/?probe=c758164470) | Aug 03, 2021 |
| Lenovo        | ThinkPad R61e 7650DHU       | [82f2f3a1a7](https://linux-hardware.org/?probe=82f2f3a1a7) | Aug 03, 2021 |
| ASUSTek       | 1005HA                      | [1f83d95a2a](https://linux-hardware.org/?probe=1f83d95a2a) | Aug 03, 2021 |
| Lenovo        | ThinkPad T410 2537W2L       | [c14dd630ed](https://linux-hardware.org/?probe=c14dd630ed) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | [99ccdd5455](https://linux-hardware.org/?probe=99ccdd5455) | Aug 02, 2021 |
| Apple         | MacBook5,2                  | [aa5aaf6fd0](https://linux-hardware.org/?probe=aa5aaf6fd0) | Aug 02, 2021 |
| Google        | Stout                       | [e4463bb3d4](https://linux-hardware.org/?probe=e4463bb3d4) | Aug 02, 2021 |
| Fujitsu       | LIFEBOOK T5010              | [75a544682e](https://linux-hardware.org/?probe=75a544682e) | Aug 02, 2021 |
| Google        | Enguarde                    | [09406c6908](https://linux-hardware.org/?probe=09406c6908) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | [01315f2df2](https://linux-hardware.org/?probe=01315f2df2) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | [e6ca37026c](https://linux-hardware.org/?probe=e6ca37026c) | Aug 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [70647a7f66](https://linux-hardware.org/?probe=70647a7f66) | Aug 02, 2021 |
| Dell          | Inspiron 7391               | [c4ac48e264](https://linux-hardware.org/?probe=c4ac48e264) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [ace43d8e9f](https://linux-hardware.org/?probe=ace43d8e9f) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [384ffe1123](https://linux-hardware.org/?probe=384ffe1123) | Aug 02, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [101a0ca1b3](https://linux-hardware.org/?probe=101a0ca1b3) | Aug 01, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [9c7fb8e911](https://linux-hardware.org/?probe=9c7fb8e911) | Aug 01, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [08fe25ec71](https://linux-hardware.org/?probe=08fe25ec71) | Aug 01, 2021 |
| Lenovo        | ThinkPad Edge E330 3354D... | [9c317f536b](https://linux-hardware.org/?probe=9c317f536b) | Aug 01, 2021 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [f851abbdf5](https://linux-hardware.org/?probe=f851abbdf5) | Aug 01, 2021 |
| Dell          | Inspiron 5570               | [5b89a99ad8](https://linux-hardware.org/?probe=5b89a99ad8) | Jul 31, 2021 |
| Dell          | Vostro 5502                 | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [60f065b770](https://linux-hardware.org/?probe=60f065b770) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [b62fb400bf](https://linux-hardware.org/?probe=b62fb400bf) | Jul 31, 2021 |
| Acer          | Aspire 7720                 | [6472272bf7](https://linux-hardware.org/?probe=6472272bf7) | Jul 30, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [b16533813f](https://linux-hardware.org/?probe=b16533813f) | Jul 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0A60... | [8a3c585de4](https://linux-hardware.org/?probe=8a3c585de4) | Jul 30, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | [a46cb950a4](https://linux-hardware.org/?probe=a46cb950a4) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | [370cea169d](https://linux-hardware.org/?probe=370cea169d) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | [a5a9ca4678](https://linux-hardware.org/?probe=a5a9ca4678) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [55c54d17ad](https://linux-hardware.org/?probe=55c54d17ad) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [1bb07ffc9f](https://linux-hardware.org/?probe=1bb07ffc9f) | Jul 29, 2021 |
| SLIMBOOK      | PROX14-AMD                  | [16aeb37a86](https://linux-hardware.org/?probe=16aeb37a86) | Jul 29, 2021 |
| Acer          | Nitro AN517-41              | [ccc850c1da](https://linux-hardware.org/?probe=ccc850c1da) | Jul 29, 2021 |
| Lenovo        | ThinkPad T420s 4174PEG      | [e448710e41](https://linux-hardware.org/?probe=e448710e41) | Jul 28, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [89d3c0f09d](https://linux-hardware.org/?probe=89d3c0f09d) | Jul 28, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | [bee4fd945a](https://linux-hardware.org/?probe=bee4fd945a) | Jul 28, 2021 |
| Lenovo        | ThinkPad T470 20HES1UD00    | [6034f6a417](https://linux-hardware.org/?probe=6034f6a417) | Jul 28, 2021 |
| Lenovo        | ThinkPad X230 2325BQ3       | [79a19ade20](https://linux-hardware.org/?probe=79a19ade20) | Jul 28, 2021 |
| Dell          | Inspiron 8600               | [2f49d18738](https://linux-hardware.org/?probe=2f49d18738) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [abdeaec5ce](https://linux-hardware.org/?probe=abdeaec5ce) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [5258847421](https://linux-hardware.org/?probe=5258847421) | Jul 28, 2021 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | [60c16ed267](https://linux-hardware.org/?probe=60c16ed267) | Jul 28, 2021 |
| Acer          | Swift SF313-52G             | [87add43827](https://linux-hardware.org/?probe=87add43827) | Jul 28, 2021 |
| Casper        | C17B                        | [6f56921ba5](https://linux-hardware.org/?probe=6f56921ba5) | Jul 27, 2021 |
| Lenovo        | ThinkPad X240 20AL008EUK    | [367150f04f](https://linux-hardware.org/?probe=367150f04f) | Jul 27, 2021 |
| HP            | Laptop 17-by0xxx            | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| HP            | ProBook 445 G7              | [bc4f8acaf2](https://linux-hardware.org/?probe=bc4f8acaf2) | Jul 27, 2021 |
| HP            | ProBook 635 Aero G7 Note... | [e6ee486690](https://linux-hardware.org/?probe=e6ee486690) | Jul 27, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [2a645d9cba](https://linux-hardware.org/?probe=2a645d9cba) | Jul 27, 2021 |
| Lenovo        | IdeaPad S540-13ITL 82H1     | [730c33a1b0](https://linux-hardware.org/?probe=730c33a1b0) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RAS13M00     | [b46ca83c19](https://linux-hardware.org/?probe=b46ca83c19) | Jul 27, 2021 |
| Dell          | Latitude 7480               | [0c79ad3dd4](https://linux-hardware.org/?probe=0c79ad3dd4) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [0172934285](https://linux-hardware.org/?probe=0172934285) | Jul 27, 2021 |
| HP            | EliteBook 820 G1            | [f3878ff548](https://linux-hardware.org/?probe=f3878ff548) | Jul 27, 2021 |
| Apple         | MacBookPro11,4              | [d58bb90557](https://linux-hardware.org/?probe=d58bb90557) | Jul 26, 2021 |
| Dell          | Inspiron 5558               | [1bbe185e86](https://linux-hardware.org/?probe=1bbe185e86) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| Quanta        | TWC                         | [1ecec0372f](https://linux-hardware.org/?probe=1ecec0372f) | Jul 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| Dell          | Vostro 5471                 | [73c1da1908](https://linux-hardware.org/?probe=73c1da1908) | Jul 26, 2021 |
| Lenovo        | G50-80 80E5                 | [eaedf12907](https://linux-hardware.org/?probe=eaedf12907) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| ASUSTek       | 701                         | [db72d4004a](https://linux-hardware.org/?probe=db72d4004a) | Jul 26, 2021 |
| ASUSTek       | 1215B                       | [ce53b40511](https://linux-hardware.org/?probe=ce53b40511) | Jul 26, 2021 |
| Dell          | Latitude E6420              | [01000461fc](https://linux-hardware.org/?probe=01000461fc) | Jul 26, 2021 |
| Dell          | Studio 1555                 | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA0036RT     | [e4f29039a8](https://linux-hardware.org/?probe=e4f29039a8) | Jul 26, 2021 |
| Apple         | MacBookPro9,2               | [c676ac21ee](https://linux-hardware.org/?probe=c676ac21ee) | Jul 26, 2021 |
| ASUSTek       | 701SD                       | [b7c888a9a7](https://linux-hardware.org/?probe=b7c888a9a7) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | X541NC                      | [500a26f588](https://linux-hardware.org/?probe=500a26f588) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Dell          | XPS 17 9700                 | [92cd785445](https://linux-hardware.org/?probe=92cd785445) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460 20FMS03600    | [84f380e2a2](https://linux-hardware.org/?probe=84f380e2a2) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [4454739a42](https://linux-hardware.org/?probe=4454739a42) | Jul 25, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [abced1dd83](https://linux-hardware.org/?probe=abced1dd83) | Jul 25, 2021 |
| Lenovo        | ThinkPad E480 20KN001NGE    | [e3b2914d19](https://linux-hardware.org/?probe=e3b2914d19) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| HP            | ProBook x360 11 G1 EE       | [90aeea53cc](https://linux-hardware.org/?probe=90aeea53cc) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [5c61fdfb49](https://linux-hardware.org/?probe=5c61fdfb49) | Jul 25, 2021 |
| Dell          | Latitude E5520              | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| HP            | 250 G7 Notebook PC          | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [b8a2299d30](https://linux-hardware.org/?probe=b8a2299d30) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [0d45d49199](https://linux-hardware.org/?probe=0d45d49199) | Jul 25, 2021 |
| PC Special... | NV4XMB,ME,MZ                | [eb789efe18](https://linux-hardware.org/?probe=eb789efe18) | Jul 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [a172262124](https://linux-hardware.org/?probe=a172262124) | Jul 25, 2021 |
| Lenovo        | ThinkPad T410 2522WUZ       | [62cddaceb1](https://linux-hardware.org/?probe=62cddaceb1) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [1217d711fb](https://linux-hardware.org/?probe=1217d711fb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L50063EU    | [c59c2aa27d](https://linux-hardware.org/?probe=c59c2aa27d) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349BW1       | [75c4d5c7a9](https://linux-hardware.org/?probe=75c4d5c7a9) | Jul 25, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [59533bd2bf](https://linux-hardware.org/?probe=59533bd2bf) | Jul 25, 2021 |
| Acer          | Aspire 5735                 | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236EV9       | [62cc86b330](https://linux-hardware.org/?probe=62cc86b330) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [b3dca0cfaa](https://linux-hardware.org/?probe=b3dca0cfaa) | Jul 25, 2021 |
| HP            | 250 G5 Notebook PC          | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [043c5815ee](https://linux-hardware.org/?probe=043c5815ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [a30a8b568e](https://linux-hardware.org/?probe=a30a8b568e) | Jul 25, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [686f21af90](https://linux-hardware.org/?probe=686f21af90) | Jul 25, 2021 |
| Dell          | XPS L322X                   | [6b0ab2e22d](https://linux-hardware.org/?probe=6b0ab2e22d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [722792ec34](https://linux-hardware.org/?probe=722792ec34) | Jul 25, 2021 |
| Dell          | Inspiron 3505               | [be67f17212](https://linux-hardware.org/?probe=be67f17212) | Jul 25, 2021 |
| Dell          | XPS 13 9300                 | [15012d7630](https://linux-hardware.org/?probe=15012d7630) | Jul 25, 2021 |
| Panasonic     | CF-AX2LDCZMF                | [31feab61fe](https://linux-hardware.org/?probe=31feab61fe) | Jul 25, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [3dae264c17](https://linux-hardware.org/?probe=3dae264c17) | Jul 25, 2021 |
| HP            | Laptop 14-ck0xxx            | [814f91322d](https://linux-hardware.org/?probe=814f91322d) | Jul 25, 2021 |
| Dell          | Inspiron 5423               | [f15c87c33c](https://linux-hardware.org/?probe=f15c87c33c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | [7275a5dc90](https://linux-hardware.org/?probe=7275a5dc90) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [8e2d810033](https://linux-hardware.org/?probe=8e2d810033) | Jul 25, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | [079f1c9006](https://linux-hardware.org/?probe=079f1c9006) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [6f137bd0e5](https://linux-hardware.org/?probe=6f137bd0e5) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| MSI           | Modern 15 A11M              | [acfcaa9077](https://linux-hardware.org/?probe=acfcaa9077) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [fb8dc2feb1](https://linux-hardware.org/?probe=fb8dc2feb1) | Jul 25, 2021 |
| HP            | Stream Notebook             | [078c5d40f8](https://linux-hardware.org/?probe=078c5d40f8) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [49198ead06](https://linux-hardware.org/?probe=49198ead06) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| Dell          | Inspiron 5402               | [f54ac49b39](https://linux-hardware.org/?probe=f54ac49b39) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S46R00    | [c72e326772](https://linux-hardware.org/?probe=c72e326772) | Jul 25, 2021 |
| Gigabyte      | AERO 15 KB                  | [d66f45fc2e](https://linux-hardware.org/?probe=d66f45fc2e) | Jul 25, 2021 |
| HP            | ProBook 640 G2              | [558f739aab](https://linux-hardware.org/?probe=558f739aab) | Jul 25, 2021 |
| Dell          | XPS 13 9370                 | [2c9c978361](https://linux-hardware.org/?probe=2c9c978361) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| Lenovo        | ThinkPad E14 20RB000UBR     | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| HP            | Laptop 15-ef1xxx            | [9f0fbc1613](https://linux-hardware.org/?probe=9f0fbc1613) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | EliteBook 820 G2            | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2347FF9       | [cdc7a6e9c8](https://linux-hardware.org/?probe=cdc7a6e9c8) | Jul 25, 2021 |
| HP            | 2000                        | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| Acer          | Aspire A515-41G             | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| Dell          | XPS 13 7390                 | [02e6821b40](https://linux-hardware.org/?probe=02e6821b40) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [4cf2681a8c](https://linux-hardware.org/?probe=4cf2681a8c) | Jul 24, 2021 |
| Apple         | MacBookPro8,1               | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [3491bd4228](https://linux-hardware.org/?probe=3491bd4228) | Jul 23, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | [dd220c0bdb](https://linux-hardware.org/?probe=dd220c0bdb) | Jul 23, 2021 |
| Gigabyte      | AERO 17-SA                  | [eaff86e276](https://linux-hardware.org/?probe=eaff86e276) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ecd10ec3a7](https://linux-hardware.org/?probe=ecd10ec3a7) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1abb08da83](https://linux-hardware.org/?probe=1abb08da83) | Jul 21, 2021 |
| HP            | Laptop 15s-fq1xxx           | [4ed280d4c8](https://linux-hardware.org/?probe=4ed280d4c8) | Jul 19, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | [acca72e9c1](https://linux-hardware.org/?probe=acca72e9c1) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Precision 3540              | [383ebf30aa](https://linux-hardware.org/?probe=383ebf30aa) | Jul 14, 2021 |
| Itautec       | Infoway                     | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [71d234aaef](https://linux-hardware.org/?probe=71d234aaef) | Jul 14, 2021 |
| Acer          | Aspire 7741                 | [6ed4934b61](https://linux-hardware.org/?probe=6ed4934b61) | Jul 13, 2021 |
| Acer          | Aspire 7741                 | [ee5a2b2029](https://linux-hardware.org/?probe=ee5a2b2029) | Jul 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [54bfb26e0f](https://linux-hardware.org/?probe=54bfb26e0f) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| Acer          | Aspire A315-23G             | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| Dell          | XPS 13 9380                 | [b31688ecfa](https://linux-hardware.org/?probe=b31688ecfa) | Jul 08, 2021 |
| Dell          | Latitude E6330              | [321bec10eb](https://linux-hardware.org/?probe=321bec10eb) | Jul 05, 2021 |
| HP            | Compaq 6830s                | [9c47e76afe](https://linux-hardware.org/?probe=9c47e76afe) | Jul 04, 2021 |
| HP            | Compaq 6830s                | [b524035304](https://linux-hardware.org/?probe=b524035304) | Jul 04, 2021 |
| Dell          | Inspiron 5570               | [b760b0d9cc](https://linux-hardware.org/?probe=b760b0d9cc) | Jul 03, 2021 |
| Acer          | Aspire A515-51              | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Dell          | Inspiron 5570               | [44b96068f2](https://linux-hardware.org/?probe=44b96068f2) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [c8cb82f74d](https://linux-hardware.org/?probe=c8cb82f74d) | Jun 30, 2021 |
| Dell          | XPS 13 9310                 | [24a52836b4](https://linux-hardware.org/?probe=24a52836b4) | Jun 30, 2021 |
| HP            | ProBook 640 G3              | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| HP            | ZBook 17 G5                 | [5557a5c23c](https://linux-hardware.org/?probe=5557a5c23c) | Jun 29, 2021 |
| Lenovo        | IdeaPad Z580                | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Dell          | Inspiron 5570               | [5335641d04](https://linux-hardware.org/?probe=5335641d04) | Jun 28, 2021 |
| Dell          | Inspiron 5570               | [0632a7bf28](https://linux-hardware.org/?probe=0632a7bf28) | Jun 28, 2021 |
| Acer          | Aspire A315-23G             | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [fda3d18cf7](https://linux-hardware.org/?probe=fda3d18cf7) | Jun 27, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| Acer          | Nitro AN515-51              | [6c4a46b4ec](https://linux-hardware.org/?probe=6c4a46b4ec) | Jun 26, 2021 |
| Dell          | Inspiron 3501               | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| MSI           | GF65 Thin 10UE              | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [9e646a384e](https://linux-hardware.org/?probe=9e646a384e) | Jun 22, 2021 |
| Dell          | Precision 3560              | [81efcf647c](https://linux-hardware.org/?probe=81efcf647c) | Jun 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | [75c4ec9e5a](https://linux-hardware.org/?probe=75c4ec9e5a) | Jun 21, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [c62a9a5058](https://linux-hardware.org/?probe=c62a9a5058) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [5a39dabe8a](https://linux-hardware.org/?probe=5a39dabe8a) | Jun 20, 2021 |
| Acer          | Aspire A315-23G             | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Dell          | Latitude E7470              | [49cb9ff0b0](https://linux-hardware.org/?probe=49cb9ff0b0) | Jun 20, 2021 |
| Acer          | Aspire 5750G                | [73d6b46b6b](https://linux-hardware.org/?probe=73d6b46b6b) | Jun 19, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a894e25838](https://linux-hardware.org/?probe=a894e25838) | Jun 19, 2021 |
| Acer          | Aspire A315-23G             | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [842c53b8e2](https://linux-hardware.org/?probe=842c53b8e2) | Jun 18, 2021 |
| Acer          | Aspire A315-23G             | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| Acer          | Aspire ES1-132              | [c26c0f6e33](https://linux-hardware.org/?probe=c26c0f6e33) | Jun 15, 2021 |
| Acer          | Aspire A315-23G             | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Acer          | Aspire V3-331               | [91f4f7aab6](https://linux-hardware.org/?probe=91f4f7aab6) | Jun 13, 2021 |
| UNOWHY        | Y13G002S4EI                 | [3d25dc9f69](https://linux-hardware.org/?probe=3d25dc9f69) | Jun 13, 2021 |
| ASUSTek       | X550LD                      | [2d1f6364aa](https://linux-hardware.org/?probe=2d1f6364aa) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | [02e288caf9](https://linux-hardware.org/?probe=02e288caf9) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1b2cda6c08](https://linux-hardware.org/?probe=1b2cda6c08) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [57684125de](https://linux-hardware.org/?probe=57684125de) | Jun 12, 2021 |
| Dell          | Latitude E7470              | [51c1f3f1f5](https://linux-hardware.org/?probe=51c1f3f1f5) | Jun 10, 2021 |
| Acer          | Aspire A315-23G             | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Dell          | Latitude E6330              | [ba88cd6328](https://linux-hardware.org/?probe=ba88cd6328) | Jun 08, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | [0195b8564e](https://linux-hardware.org/?probe=0195b8564e) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | [2db77f0d01](https://linux-hardware.org/?probe=2db77f0d01) | Jun 07, 2021 |
| Acer          | Aspire A315-23G             | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Dell          | Inspiron 3793               | [f65812f774](https://linux-hardware.org/?probe=f65812f774) | Jun 06, 2021 |
| ASUSTek       | M3N                         | [ec5f914161](https://linux-hardware.org/?probe=ec5f914161) | Jun 06, 2021 |
| ASUSTek       | M3N                         | [bd89f26d7e](https://linux-hardware.org/?probe=bd89f26d7e) | Jun 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [47e9dfd146](https://linux-hardware.org/?probe=47e9dfd146) | Jun 05, 2021 |
| Acer          | Aspire A315-23G             | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP            | ProBook 640 G8 Notebook ... | [e20b51102d](https://linux-hardware.org/?probe=e20b51102d) | Jun 03, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| Monster       | ABRA A5 V15.2               | [012bfa586d](https://linux-hardware.org/?probe=012bfa586d) | Jun 02, 2021 |
| Pegatron      | A15                         | [dec1b6b43a](https://linux-hardware.org/?probe=dec1b6b43a) | Jun 02, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [ac80feea4f](https://linux-hardware.org/?probe=ac80feea4f) | Jun 01, 2021 |
| Acer          | Aspire A315-23G             | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| Toshiba       | Satellite U800W             | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| MSI           | U90/U100                    | [477251f62e](https://linux-hardware.org/?probe=477251f62e) | May 30, 2021 |
| MSI           | U90/U100                    | [1a0476551b](https://linux-hardware.org/?probe=1a0476551b) | May 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c33e7ced42](https://linux-hardware.org/?probe=c33e7ced42) | May 29, 2021 |
| MSI           | CX700                       | [ef40976753](https://linux-hardware.org/?probe=ef40976753) | May 29, 2021 |
| Dell          | XPS 13 9310                 | [5de2c933c1](https://linux-hardware.org/?probe=5de2c933c1) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Samsung       | 370E4K                      | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| MSI           | CX700                       | [535d0016e2](https://linux-hardware.org/?probe=535d0016e2) | May 27, 2021 |
| Acer          | Aspire A315-23G             | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Acer          | Aspire A315-23G             | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [f03341d873](https://linux-hardware.org/?probe=f03341d873) | May 23, 2021 |
| HP            | EliteBook 840 G1            | [6573923d55](https://linux-hardware.org/?probe=6573923d55) | May 21, 2021 |
| Acer          | Aspire A315-23G             | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Dell          | Latitude 7480               | [0f2477786d](https://linux-hardware.org/?probe=0f2477786d) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [b9d0acf0a6](https://linux-hardware.org/?probe=b9d0acf0a6) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [97a658e572](https://linux-hardware.org/?probe=97a658e572) | May 19, 2021 |
| Acer          | Aspire A315-23G             | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| HP            | Compaq Presario C700        | [91a939ce16](https://linux-hardware.org/?probe=91a939ce16) | May 16, 2021 |
| Acer          | Aspire A315-23G             | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| HP            | Split 13 x2 PC              | [5834b6321d](https://linux-hardware.org/?probe=5834b6321d) | May 05, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [bf3e99374e](https://linux-hardware.org/?probe=bf3e99374e) | Apr 29, 2021 |
| Lenovo        | IdeaPad Z500 20202          | [a06f2bc29e](https://linux-hardware.org/?probe=a06f2bc29e) | Apr 27, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a042fd63c6](https://linux-hardware.org/?probe=a042fd63c6) | Apr 27, 2021 |
| Dell          | Inspiron 3793               | [a4c79ea8c3](https://linux-hardware.org/?probe=a4c79ea8c3) | Apr 26, 2021 |
| HP            | EliteBook 8460p             | [bcea790fba](https://linux-hardware.org/?probe=bcea790fba) | Apr 24, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Dell          | Inspiron 5468               | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.10.0-8-amd64             | 134       | 53.6%   |
| 5.10.0-7-amd64             | 60        | 24%     |
| 5.10.0-6-amd64             | 23        | 9.2%    |
| 5.10.0-8-686-pae           | 4         | 1.6%    |
| 5.12.0-19.3-liquorix-amd64 | 2         | 0.8%    |
| 5.10.0-8-686               | 2         | 0.8%    |
| 4.19.0-14-amd64            | 2         | 0.8%    |
| 5.14.0-rc3-prygun          | 1         | 0.4%    |
| 5.13.8-xanmod1             | 1         | 0.4%    |
| 5.13.5-xanmod1             | 1         | 0.4%    |
| 5.13.4-e5520               | 1         | 0.4%    |
| 5.12.10                    | 1         | 0.4%    |
| 5.12.1                     | 1         | 0.4%    |
| 5.12.0-9.2-liquorix-amd64  | 1         | 0.4%    |
| 5.12.0-14.2-liquorix-amd64 | 1         | 0.4%    |
| 5.11.9+                    | 1         | 0.4%    |
| 5.11.22-1-pve              | 1         | 0.4%    |
| 5.11.15-051115-generic     | 1         | 0.4%    |
| 5.11.14                    | 1         | 0.4%    |
| 5.11.0-rc6                 | 1         | 0.4%    |
| 5.10.40-ismynik            | 1         | 0.4%    |
| 5.10.10-64                 | 1         | 0.4%    |
| 5.10.0-io7-amd64           | 1         | 0.4%    |
| 5.10.0-6-rt-amd64          | 1         | 0.4%    |
| 5.10.0-6-686               | 1         | 0.4%    |
| 5.10.0-5-amd64             | 1         | 0.4%    |
| 5.10.0-4-amd64             | 1         | 0.4%    |
| 4.19.181-z580322           | 1         | 0.4%    |
| 4.19.0-16-amd64            | 1         | 0.4%    |
| 4.19.0-16-686-pae          | 1         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 222       | 91.36%  |
| 4.19.0   | 4         | 1.65%   |
| 5.12.0   | 3         | 1.23%   |
| 5.14.0   | 1         | 0.41%   |
| 5.13.8   | 1         | 0.41%   |
| 5.13.5   | 1         | 0.41%   |
| 5.13.4   | 1         | 0.41%   |
| 5.12.10  | 1         | 0.41%   |
| 5.12.1   | 1         | 0.41%   |
| 5.11.9   | 1         | 0.41%   |
| 5.11.22  | 1         | 0.41%   |
| 5.11.15  | 1         | 0.41%   |
| 5.11.14  | 1         | 0.41%   |
| 5.11.0   | 1         | 0.41%   |
| 5.10.40  | 1         | 0.41%   |
| 5.10.10  | 1         | 0.41%   |
| 4.19.181 | 1         | 0.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 224       | 92.18%  |
| 5.12    | 5         | 2.06%   |
| 5.11    | 5         | 2.06%   |
| 4.19    | 5         | 2.06%   |
| 5.13    | 3         | 1.23%   |
| 5.14    | 1         | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 235       | 96.71%  |
| i686   | 8         | 3.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 75        | 30.61%  |
| KDE5             | 49        | 20%     |
| Unknown          | 45        | 18.37%  |
| XFCE             | 21        | 8.57%   |
| MATE             | 12        | 4.9%    |
| LXQt             | 7         | 2.86%   |
| i3               | 7         | 2.86%   |
| LXDE             | 5         | 2.04%   |
| X-Cinnamon       | 4         | 1.63%   |
| KDE              | 4         | 1.63%   |
| Cinnamon         | 4         | 1.63%   |
| lightdm-xsession | 3         | 1.22%   |
| openbox          | 2         | 0.82%   |
| GNOME Flashback  | 2         | 0.82%   |
| sway             | 1         | 0.41%   |
| ICEWM            | 1         | 0.41%   |
| Enlightenment    | 1         | 0.41%   |
| default          | 1         | 0.41%   |
| awesome          | 1         | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 134       | 54.69%  |
| Wayland | 62        | 25.31%  |
| Unknown | 36        | 14.69%  |
| Tty     | 13        | 5.31%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 72        | 29.51%  |
| Unknown | 62        | 25.41%  |
| TDM     | 53        | 21.72%  |
| SDDM    | 53        | 21.72%  |
| LightDM | 2         | 0.82%   |
| XDM     | 1         | 0.41%   |
| KDM     | 1         | 0.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 92        | 37.86%  |
| Unknown | 24        | 9.88%   |
| ru_RU   | 18        | 7.41%   |
| en_GB   | 18        | 7.41%   |
| fr_FR   | 14        | 5.76%   |
| de_DE   | 14        | 5.76%   |
| es_ES   | 7         | 2.88%   |
| en_IN   | 7         | 2.88%   |
| pt_BR   | 6         | 2.47%   |
| pl_PL   | 5         | 2.06%   |
| it_IT   | 4         | 1.65%   |
| tr_TR   | 3         | 1.23%   |
| pt_PT   | 2         | 0.82%   |
| ja_JP   | 2         | 0.82%   |
| en_SG   | 2         | 0.82%   |
| en_AU   | 2         | 0.82%   |
| de_CH   | 2         | 0.82%   |
| cs_CZ   | 2         | 0.82%   |
| C       | 2         | 0.82%   |
| uk_UA   | 1         | 0.41%   |
| ru_UA   | 1         | 0.41%   |
| ro_RO   | 1         | 0.41%   |
| nl_BE   | 1         | 0.41%   |
| hu_HU   | 1         | 0.41%   |
| hr_HR   | 1         | 0.41%   |
| gl_ES   | 1         | 0.41%   |
| fi_FI   | 1         | 0.41%   |
| es_UY   | 1         | 0.41%   |
| es_MX   | 1         | 0.41%   |
| es_EC   | 1         | 0.41%   |
| es_CO   | 1         | 0.41%   |
| en_SI   | 1         | 0.41%   |
| en_IE   | 1         | 0.41%   |
| en_HK   | 1         | 0.41%   |
| en_CA   | 1         | 0.41%   |
| ca_ES   | 1         | 0.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 164       | 67.21%  |
| BIOS | 80        | 32.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 181       | 74.49%  |
| Overlay | 41        | 16.87%  |
| Btrfs   | 14        | 5.76%   |
| Zfs     | 2         | 0.82%   |
| Xfs     | 2         | 0.82%   |
| Unknown | 2         | 0.82%   |
| Rootfs  | 1         | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 176       | 72.13%  |
| MBR     | 49        | 20.08%  |
| Unknown | 19        | 7.79%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 212       | 86.89%  |
| Yes       | 32        | 13.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 178       | 73.25%  |
| Yes       | 65        | 26.75%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 78        | 32.1%   |
| Hewlett-Packard     | 42        | 17.28%  |
| Dell                | 37        | 15.23%  |
| ASUSTek Computer    | 21        | 8.64%   |
| Apple               | 17        | 7%      |
| Acer                | 16        | 6.58%   |
| MSI                 | 5         | 2.06%   |
| Toshiba             | 3         | 1.23%   |
| HUAWEI              | 3         | 1.23%   |
| Google              | 3         | 1.23%   |
| Fujitsu             | 3         | 1.23%   |
| Gigabyte Technology | 2         | 0.82%   |
| UNOWHY              | 1         | 0.41%   |
| TUXEDO              | 1         | 0.41%   |
| SLIMBOOK            | 1         | 0.41%   |
| Samsung Electronics | 1         | 0.41%   |
| Quanta              | 1         | 0.41%   |
| Pegatron            | 1         | 0.41%   |
| PC Specialist       | 1         | 0.41%   |
| Panasonic           | 1         | 0.41%   |
| Notebook            | 1         | 0.41%   |
| Monster             | 1         | 0.41%   |
| Itautec             | 1         | 0.41%   |
| Clevo               | 1         | 0.41%   |
| Casper              | 1         | 0.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Apple MacBookAir7,2                         | 5         | 2.06%   |
| Apple MacBookAir7,1                         | 4         | 1.65%   |
| Lenovo ThinkPad T490 20N2CTO1WW             | 2         | 0.82%   |
| Lenovo ThinkPad E475 20H40006US             | 2         | 0.82%   |
| Lenovo G50-80 80E5                          | 2         | 0.82%   |
| HUAWEI NBLK-WAX9X                           | 2         | 0.82%   |
| HP EliteBook 8460p                          | 2         | 0.82%   |
| HP Compaq nx6125 (PZ849UA#ABA)              | 2         | 0.82%   |
| HP Compaq nx6110 (PZ065UA#ABA)              | 2         | 0.82%   |
| Google Enguarde                             | 2         | 0.82%   |
| Dell XPS 13 9310                            | 2         | 0.82%   |
| Dell XPS 13 7390                            | 2         | 0.82%   |
| Dell Precision 3540                         | 2         | 0.82%   |
| Dell Latitude 7480                          | 2         | 0.82%   |
| Dell Inspiron 5570                          | 2         | 0.82%   |
| Dell Inspiron 3793                          | 2         | 0.82%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA     | 2         | 0.82%   |
| Apple MacBook5,2                            | 2         | 0.82%   |
| Acer Aspire 5315                            | 2         | 0.82%   |
| UNOWHY Y13G002S4EI                          | 1         | 0.41%   |
| TUXEDO Pulse 15 Gen1                        | 1         | 0.41%   |
| Toshiba Satellite U800W                     | 1         | 0.41%   |
| Toshiba Satellite S55-A                     | 1         | 0.41%   |
| Toshiba Satellite C45-A                     | 1         | 0.41%   |
| SLIMBOOK PROX14-AMD                         | 1         | 0.41%   |
| Samsung 370E4K                              | 1         | 0.41%   |
| Quanta TWC                                  | 1         | 0.41%   |
| Pegatron A15                                | 1         | 0.41%   |
| PC Specialist NV4XMB,ME,MZ                  | 1         | 0.41%   |
| Panasonic CF-AX2LDCZMF                      | 1         | 0.41%   |
| Notebook NJ50_70CU                          | 1         | 0.41%   |
| MSI U90/U100                                | 1         | 0.41%   |
| MSI Modern 15 A11M                          | 1         | 0.41%   |
| MSI GP60 2PE                                | 1         | 0.41%   |
| MSI GF65 Thin 10UE                          | 1         | 0.41%   |
| MSI CX700                                   | 1         | 0.41%   |
| Monster ABRA A5 V15.2                       | 1         | 0.41%   |
| Lenovo Yoga 300-11IBR 80M1                  | 1         | 0.41%   |
| Lenovo ThinkPad X270 W10DG 20K5S41E00       | 1         | 0.41%   |
| Lenovo ThinkPad X260 20F5S46R00             | 1         | 0.41%   |
| Lenovo ThinkPad X260 20F5S0JF00             | 1         | 0.41%   |
| Lenovo ThinkPad X240 20AL008EUK             | 1         | 0.41%   |
| Lenovo ThinkPad X230 2325BQ3                | 1         | 0.41%   |
| Lenovo ThinkPad X230 2325AZ8                | 1         | 0.41%   |
| Lenovo ThinkPad X201 3626ES3                | 1         | 0.41%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS | 1         | 0.41%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006JRT    | 1         | 0.41%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR002RMX    | 1         | 0.41%   |
| Lenovo ThinkPad W520 4284CY1                | 1         | 0.41%   |
| Lenovo ThinkPad T530 24296HG                | 1         | 0.41%   |
| Lenovo ThinkPad T495 20NKS0PG00             | 1         | 0.41%   |
| Lenovo ThinkPad T495 20NJCTO1WW             | 1         | 0.41%   |
| Lenovo ThinkPad T490 20RYCTO1WW             | 1         | 0.41%   |
| Lenovo ThinkPad T480s 20L8S7HF00            | 1         | 0.41%   |
| Lenovo ThinkPad T480 20L5S1S000             | 1         | 0.41%   |
| Lenovo ThinkPad T480 20L50063EU             | 1         | 0.41%   |
| Lenovo ThinkPad T470s 20HGS0A600            | 1         | 0.41%   |
| Lenovo ThinkPad T470 W10DG 20JNS42314       | 1         | 0.41%   |
| Lenovo ThinkPad T470 20HES1UD00             | 1         | 0.41%   |
| Lenovo ThinkPad T460 20FMS03600             | 1         | 0.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 61        | 25.1%   |
| Lenovo IdeaPad         | 14        | 5.76%   |
| Dell Inspiron          | 13        | 5.35%   |
| Acer Aspire            | 13        | 5.35%   |
| HP ProBook             | 10        | 4.12%   |
| Dell XPS               | 9         | 3.7%    |
| Apple MacBookAir7      | 9         | 3.7%    |
| HP EliteBook           | 8         | 3.29%   |
| Dell Latitude          | 8         | 3.29%   |
| HP Compaq              | 7         | 2.88%   |
| HP Laptop              | 5         | 2.06%   |
| ASUS VivoBook          | 5         | 2.06%   |
| ASUS ZenBook           | 4         | 1.65%   |
| Toshiba Satellite      | 3         | 1.23%   |
| Fujitsu LIFEBOOK       | 3         | 1.23%   |
| Dell Precision         | 3         | 1.23%   |
| Lenovo G50-80          | 2         | 0.82%   |
| HUAWEI NBLK-WAX9X      | 2         | 0.82%   |
| HP ZBook               | 2         | 0.82%   |
| HP OMEN                | 2         | 0.82%   |
| HP 250                 | 2         | 0.82%   |
| Google Enguarde        | 2         | 0.82%   |
| Gigabyte AERO          | 2         | 0.82%   |
| Dell Vostro            | 2         | 0.82%   |
| ASUS ROG               | 2         | 0.82%   |
| Apple MacBook5         | 2         | 0.82%   |
| Acer Nitro             | 2         | 0.82%   |
| UNOWHY Y13G002S4EI     | 1         | 0.41%   |
| TUXEDO Pulse           | 1         | 0.41%   |
| SLIMBOOK PROX14-AMD    | 1         | 0.41%   |
| Samsung 370E4K         | 1         | 0.41%   |
| Quanta TWC             | 1         | 0.41%   |
| Pegatron A15           | 1         | 0.41%   |
| PC Specialist NV4XMB   | 1         | 0.41%   |
| Panasonic CF-AX2LDCZMF | 1         | 0.41%   |
| Notebook NJ50          | 1         | 0.41%   |
| MSI U90                | 1         | 0.41%   |
| MSI Modern             | 1         | 0.41%   |
| MSI GP60               | 1         | 0.41%   |
| MSI GF65               | 1         | 0.41%   |
| MSI CX700              | 1         | 0.41%   |
| Monster ABRA           | 1         | 0.41%   |
| Lenovo Yoga            | 1         | 0.41%   |
| Itautec Infoway        | 1         | 0.41%   |
| HUAWEI BOHK-WAX9X      | 1         | 0.41%   |
| HP Stream              | 1         | 0.41%   |
| HP Split               | 1         | 0.41%   |
| HP Presario            | 1         | 0.41%   |
| HP Pavilion            | 1         | 0.41%   |
| HP 630                 | 1         | 0.41%   |
| HP 2000                | 1         | 0.41%   |
| Google Stout           | 1         | 0.41%   |
| Dell Studio            | 1         | 0.41%   |
| Dell G3                | 1         | 0.41%   |
| Clevo W240HU           | 1         | 0.41%   |
| Casper CASPER          | 1         | 0.41%   |
| ASUS X550LD            | 1         | 0.41%   |
| ASUS X541NC            | 1         | 0.41%   |
| ASUS TUF               | 1         | 0.41%   |
| ASUS N53Ta             | 1         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 53        | 21.81%  |
| 2020 | 53        | 21.81%  |
| 2019 | 36        | 14.81%  |
| 2018 | 16        | 6.58%   |
| 2013 | 13        | 5.35%   |
| 2011 | 11        | 4.53%   |
| 2012 | 10        | 4.12%   |
| 2008 | 10        | 4.12%   |
| 2016 | 8         | 3.29%   |
| 2009 | 7         | 2.88%   |
| 2014 | 6         | 2.47%   |
| 2017 | 5         | 2.06%   |
| 2015 | 5         | 2.06%   |
| 2007 | 3         | 1.23%   |
| 2010 | 2         | 0.82%   |
| 2005 | 2         | 0.82%   |
| 2004 | 2         | 0.82%   |
| 2006 | 1         | 0.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 243       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 212       | 86.53%  |
| Enabled  | 33        | 13.47%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 240       | 98.77%  |
| Yes  | 3         | 1.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 68        | 27.98%  |
| 16.01-24.0  | 60        | 24.69%  |
| 8.01-16.0   | 36        | 14.81%  |
| 3.01-4.0    | 35        | 14.4%   |
| 32.01-64.0  | 14        | 5.76%   |
| 1.01-2.0    | 14        | 5.76%   |
| 0.51-1.0    | 4         | 1.65%   |
| 0.01-0.5    | 4         | 1.65%   |
| 2.01-3.0    | 3         | 1.23%   |
| 64.01-256.0 | 3         | 1.23%   |
| 24.01-32.0  | 2         | 0.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 72        | 29.03%  |
| 2.01-3.0   | 57        | 22.98%  |
| 4.01-8.0   | 38        | 15.32%  |
| 3.01-4.0   | 27        | 10.89%  |
| 0.51-1.0   | 21        | 8.47%   |
| 8.01-16.0  | 20        | 8.06%   |
| 0.01-0.5   | 12        | 4.84%   |
| 32.01-64.0 | 1         | 0.4%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 162       | 66.67%  |
| 2      | 74        | 30.45%  |
| 3      | 3         | 1.23%   |
| 4      | 2         | 0.82%   |
| 0      | 2         | 0.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 179       | 73.66%  |
| Yes       | 64        | 26.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 193       | 79.42%  |
| No        | 50        | 20.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 237       | 97.53%  |
| No        | 6         | 2.47%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 192       | 79.01%  |
| No        | 51        | 20.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 54        | 22.22%  |
| Germany     | 22        | 9.05%   |
| France      | 22        | 9.05%   |
| Russia      | 19        | 7.82%   |
| Spain       | 10        | 4.12%   |
| Poland      | 9         | 3.7%    |
| UK          | 8         | 3.29%   |
| Brazil      | 8         | 3.29%   |
| Ukraine     | 7         | 2.88%   |
| India       | 7         | 2.88%   |
| Netherlands | 6         | 2.47%   |
| Turkey      | 5         | 2.06%   |
| Portugal    | 5         | 2.06%   |
| Greece      | 5         | 2.06%   |
| Thailand    | 4         | 1.65%   |
| Switzerland | 4         | 1.65%   |
| Kazakhstan  | 4         | 1.65%   |
| Belarus     | 4         | 1.65%   |
| Italy       | 3         | 1.23%   |
| Czechia     | 3         | 1.23%   |
| Canada      | 3         | 1.23%   |
| Slovenia    | 2         | 0.82%   |
| Mexico      | 2         | 0.82%   |
| Japan       | 2         | 0.82%   |
| Indonesia   | 2         | 0.82%   |
| Ecuador     | 2         | 0.82%   |
| Croatia     | 2         | 0.82%   |
| Australia   | 2         | 0.82%   |
| Uruguay     | 1         | 0.41%   |
| Romania     | 1         | 0.41%   |
| Philippines | 1         | 0.41%   |
| Norway      | 1         | 0.41%   |
| Mongolia    | 1         | 0.41%   |
| Malaysia    | 1         | 0.41%   |
| Ireland     | 1         | 0.41%   |
| Hungary     | 1         | 0.41%   |
| Finland     | 1         | 0.41%   |
| Denmark     | 1         | 0.41%   |
| Colombia    | 1         | 0.41%   |
| China       | 1         | 0.41%   |
| Bulgaria    | 1         | 0.41%   |
| Belgium     | 1         | 0.41%   |
| Bangladesh  | 1         | 0.41%   |
| Austria     | 1         | 0.41%   |
| Argentina   | 1         | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Portland          | 33        | 13.52%  |
| St Petersburg     | 9         | 3.69%   |
| Paris             | 8         | 3.28%   |
| Berlin            | 4         | 1.64%   |
| Bengaluru         | 4         | 1.64%   |
| Bangkok           | 4         | 1.64%   |
| Athens            | 3         | 1.23%   |
| Sunnyvale         | 2         | 0.82%   |
| Rio de Janeiro    | 2         | 0.82%   |
| Moscow            | 2         | 0.82%   |
| Mesa              | 2         | 0.82%   |
| Madrid            | 2         | 0.82%   |
| Lyon              | 2         | 0.82%   |
| London            | 2         | 0.82%   |
| Kyiv              | 2         | 0.82%   |
| Kalamazoo         | 2         | 0.82%   |
| Istanbul          | 2         | 0.82%   |
| Gorinchem         | 2         | 0.82%   |
| Gloucester        | 2         | 0.82%   |
| Fryazino          | 2         | 0.82%   |
| Denpasar          | 2         | 0.82%   |
| Ankara            | 2         | 0.82%   |
| Ajdov????ina      | 2         | 0.82%   |
| Zurich            | 1         | 0.41%   |
| Zaragoza          | 1         | 0.41%   |
| Zagreb            | 1         | 0.41%   |
| Yevpatoriya       | 1         | 0.41%   |
| Wroclaw           | 1         | 0.41%   |
| Waterloo          | 1         | 0.41%   |
| Warsaw            | 1         | 0.41%   |
| Waregem           | 1         | 0.41%   |
| Vitória          | 1         | 0.41%   |
| Vitry-sur-Seine   | 1         | 0.41%   |
| Vienna            | 1         | 0.41%   |
| Valladolid        | 1         | 0.41%   |
| Utrecht           | 1         | 0.41%   |
| Tyumen            | 1         | 0.41%   |
| Turin             | 1         | 0.41%   |
| Touques           | 1         | 0.41%   |
| Toul              | 1         | 0.41%   |
| Toronto           | 1         | 0.41%   |
| Thonex            | 1         | 0.41%   |
| The Hague         | 1         | 0.41%   |
| The Colony        | 1         | 0.41%   |
| Tarn??w           | 1         | 0.41%   |
| Sydney            | 1         | 0.41%   |
| Stepnogorsk       | 1         | 0.41%   |
| Srednyaya Akhtuba | 1         | 0.41%   |
| Solymar           | 1         | 0.41%   |
| Sofia             | 1         | 0.41%   |
| Shizuoka          | 1         | 0.41%   |
| Schleswig         | 1         | 0.41%   |
| Saynshand         | 1         | 0.41%   |
| Saratov           | 1         | 0.41%   |
| Sarand            | 1         | 0.41%   |
| San Justo         | 1         | 0.41%   |
| Sagunto           | 1         | 0.41%   |
| Runding           | 1         | 0.41%   |
| Rottenburg        | 1         | 0.41%   |
| Rio Vista         | 1         | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 59        | 67     | 18.85%  |
| WDC                 | 36        | 42     | 11.5%   |
| Seagate             | 27        | 29     | 8.63%   |
| Toshiba             | 22        | 23     | 7.03%   |
| Kingston            | 22        | 24     | 7.03%   |
| Unknown             | 15        | 17     | 4.79%   |
| SABRENT             | 12        | 12     | 3.83%   |
| Intel               | 12        | 12     | 3.83%   |
| Crucial             | 12        | 12     | 3.83%   |
| Apple               | 11        | 11     | 3.51%   |
| SK Hynix            | 10        | 10     | 3.19%   |
| Hitachi             | 9         | 9      | 2.88%   |
| SanDisk             | 7         | 9      | 2.24%   |
| A-DATA Technology   | 6         | 8      | 1.92%   |
| Micron Technology   | 5         | 5      | 1.6%    |
| China               | 5         | 5      | 1.6%    |
| KIOXIA              | 4         | 4      | 1.28%   |
| Fujitsu             | 4         | 4      | 1.28%   |
| Union Memory        | 3         | 3      | 0.96%   |
| Transcend           | 3         | 3      | 0.96%   |
| LITEONIT            | 3         | 3      | 0.96%   |
| JMicron             | 3         | 3      | 0.96%   |
| HGST                | 3         | 3      | 0.96%   |
| Patriot             | 2         | 2      | 0.64%   |
| LITEON              | 2         | 2      | 0.64%   |
| Lenovo              | 2         | 2      | 0.64%   |
| Intenso             | 2         | 2      | 0.64%   |
| ZTC                 | 1         | 1      | 0.32%   |
| XPG                 | 1         | 1      | 0.32%   |
| SILICONMOTION       | 1         | 1      | 0.32%   |
| Silicon Motion      | 1         | 2      | 0.32%   |
| PNY                 | 1         | 1      | 0.32%   |
| Phison              | 1         | 4      | 0.32%   |
| Maxtor              | 1         | 2      | 0.32%   |
| LDLC                | 1         | 1      | 0.32%   |
| GOODRAM             | 1         | 1      | 0.32%   |
| ASUS-PHISON         | 1         | 1      | 0.32%   |
| Apacer              | 1         | 1      | 0.32%   |
| AMD                 | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| SABRENT Disk 160GB                      | 12        | 3.66%   |
| Seagate ST1000LM035-1RK172 1TB          | 5         | 1.52%   |
| Apple SSD SM0128G 121GB                 | 5         | 1.52%   |
| Samsung SSD 970 EVO Plus 1TB            | 4         | 1.22%   |
| Samsung SSD 860 EVO 500GB               | 4         | 1.22%   |
| Samsung SSD 850 EVO 500GB               | 4         | 1.22%   |
| Apple SSD AP0128H 121GB                 | 4         | 1.22%   |
| WDC WD10SPZX-21Z10T0 1TB                | 3         | 0.91%   |
| Unknown DA4064  64GB                    | 3         | 0.91%   |
| Toshiba MQ04ABF100 1TB                  | 3         | 0.91%   |
| Seagate ST2000LX001-1RG174 2TB          | 3         | 0.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 0.91%   |
| Samsung SSD 970 EVO Plus 500GB          | 3         | 0.91%   |
| Samsung SSD 860 EVO M.2 1TB             | 3         | 0.91%   |
| Samsung SSD 860 EVO 1TB                 | 3         | 0.91%   |
| Samsung SSD 850 EVO 250GB               | 3         | 0.91%   |
| Samsung MZALQ256HAJD-000L1 256GB        | 3         | 0.91%   |
| Kingston SA400S37240G 240GB SSD         | 3         | 0.91%   |
| Kingston SA400S37120G 120GB SSD         | 3         | 0.91%   |
| Crucial CT500MX500SSD1 500GB            | 3         | 0.91%   |
| Crucial CT1000MX500SSD1 1TB             | 3         | 0.91%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.61%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB      | 2         | 0.61%   |
| Unknown HAG2e  16GB                     | 2         | 0.61%   |
| Toshiba MQ01ABF050 500GB                | 2         | 0.61%   |
| Toshiba KXG60PNV2T04 NVMe KIOXIA 2048GB | 2         | 0.61%   |
| Seagate ST1000LX015-1U7172 1TB          | 2         | 0.61%   |
| SanDisk SSD PLUS 240GB                  | 2         | 0.61%   |
| Samsung SSD 970 EVO 1TB                 | 2         | 0.61%   |
| Samsung SSD 850 EVO M.2 250GB           | 2         | 0.61%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 0.61%   |
| Kingston SV300S37A120G 120GB SSD        | 2         | 0.61%   |
| Kingston SUV400S37120G 120GB SSD        | 2         | 0.61%   |
| Kingston OM8PCP3512F-AI1 512GB          | 2         | 0.61%   |
| JMicron Generic 1TB                     | 2         | 0.61%   |
| Intel SSDPEKNW010T8 1TB                 | 2         | 0.61%   |
| Hitachi HTS543216L9A300 160GB           | 2         | 0.61%   |
| Hitachi HTS541040G9AT00 40GB            | 2         | 0.61%   |
| HGST HTS721010A9E630 1TB                | 2         | 0.61%   |
| Fujitsu MHZ2160BH FFS G1 160GB          | 2         | 0.61%   |
| Crucial CT1000P1SSD8 1TB                | 2         | 0.61%   |
| ZTC SM201-512G SSD                      | 1         | 0.3%    |
| XPG NVMe SSD Drive 1024GB               | 1         | 0.3%    |
| WDC WDS480G2G0A-00JH30 480GB SSD        | 1         | 0.3%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 0.3%    |
| WDC WDS100T3X0C-00SJG0 1TB              | 1         | 0.3%    |
| WDC WD7500BPVX-22JC3T0 752GB            | 1         | 0.3%    |
| WDC WD5000LPVX-55V0TT0 500GB            | 1         | 0.3%    |
| WDC WD5000BPVT-00HXZT3 500GB            | 1         | 0.3%    |
| WDC WD50 00LPCX-24VHA 500GB             | 1         | 0.3%    |
| WDC WD2500BEKT-00PVMT0 250GB            | 1         | 0.3%    |
| WDC WD1600BUDT-63DPZY0 160GB            | 1         | 0.3%    |
| WDC WD1200BEVS-60UST0 120GB             | 1         | 0.3%    |
| WDC WD10SPZX-80Z10T2 1TB                | 1         | 0.3%    |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 0.3%    |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 0.3%    |
| WDC WD10SPZX-22Z10T0 1TB                | 1         | 0.3%    |
| WDC WD10JPVT-75A1YT0 1TB                | 1         | 0.3%    |
| WDC WD10JPVT-00A1YT0 1TB                | 1         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 25     | 31.94%  |
| WDC                 | 19        | 20     | 26.39%  |
| Toshiba             | 11        | 11     | 15.28%  |
| Hitachi             | 9         | 9      | 12.5%   |
| Fujitsu             | 4         | 4      | 5.56%   |
| HGST                | 3         | 3      | 4.17%   |
| Samsung Electronics | 2         | 2      | 2.78%   |
| SILICONMOTION       | 1         | 1      | 1.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 38     | 26.19%  |
| Kingston            | 14        | 16     | 11.11%  |
| SABRENT             | 12        | 12     | 9.52%   |
| Crucial             | 8         | 8      | 6.35%   |
| Intel               | 7         | 7      | 5.56%   |
| Apple               | 7         | 7      | 5.56%   |
| SanDisk             | 6         | 8      | 4.76%   |
| China               | 5         | 5      | 3.97%   |
| WDC                 | 3         | 5      | 2.38%   |
| Transcend           | 3         | 3      | 2.38%   |
| LITEONIT            | 3         | 3      | 2.38%   |
| Toshiba             | 2         | 2      | 1.59%   |
| SK Hynix            | 2         | 2      | 1.59%   |
| Seagate             | 2         | 2      | 1.59%   |
| Patriot             | 2         | 2      | 1.59%   |
| JMicron             | 2         | 2      | 1.59%   |
| Intenso             | 2         | 2      | 1.59%   |
| A-DATA Technology   | 2         | 2      | 1.59%   |
| ZTC                 | 1         | 1      | 0.79%   |
| Union Memory        | 1         | 1      | 0.79%   |
| PNY                 | 1         | 1      | 0.79%   |
| Micron Technology   | 1         | 1      | 0.79%   |
| Maxtor              | 1         | 2      | 0.79%   |
| LITEON              | 1         | 1      | 0.79%   |
| LDLC                | 1         | 1      | 0.79%   |
| GOODRAM             | 1         | 1      | 0.79%   |
| ASUS-PHISON         | 1         | 1      | 0.79%   |
| Apacer              | 1         | 1      | 0.79%   |
| AMD                 | 1         | 1      | 0.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 114       | 138    | 38.38%  |
| NVMe    | 93        | 110    | 31.31%  |
| HDD     | 72        | 75     | 24.24%  |
| MMC     | 14        | 16     | 4.71%   |
| Unknown | 4         | 4      | 1.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 155       | 192    | 54.58%  |
| NVMe | 93        | 110    | 32.75%  |
| SAS  | 22        | 25     | 7.75%   |
| MMC  | 14        | 16     | 4.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 119       | 152    | 67.23%  |
| 0.51-1.0   | 51        | 54     | 28.81%  |
| 1.01-2.0   | 5         | 5      | 2.82%   |
| 3.01-4.0   | 1         | 1      | 0.56%   |
| 2.01-3.0   | 1         | 1      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 75        | 30.61%  |
| 251-500        | 51        | 20.82%  |
| 501-1000       | 34        | 13.88%  |
| 1001-2000      | 22        | 8.98%   |
| 1-20           | 20        | 8.16%   |
| 51-100         | 16        | 6.53%   |
| Unknown        | 11        | 4.49%   |
| 21-50          | 10        | 4.08%   |
| More than 3000 | 5         | 2.04%   |
| 2001-3000      | 1         | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 87        | 35.08%  |
| 21-50     | 34        | 13.71%  |
| 101-250   | 32        | 12.9%   |
| 51-100    | 31        | 12.5%   |
| 251-500   | 26        | 10.48%  |
| 501-1000  | 18        | 7.26%   |
| Unknown   | 11        | 4.44%   |
| 1001-2000 | 6         | 2.42%   |
| 0         | 2         | 0.81%   |
| 2001-3000 | 1         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD10JPVX-22JC3T0 1TB                     | 1         | 1      | 3.85%   |
| WDC WD10JPVT-75A1YT0 1TB                     | 1         | 1      | 3.85%   |
| Toshiba MQ04ABF100 1TB                       | 1         | 1      | 3.85%   |
| Toshiba MQ01ABF050 500GB                     | 1         | 1      | 3.85%   |
| Toshiba MQ01ABD100 1TB                       | 1         | 1      | 3.85%   |
| Seagate ST960822A 64GB                       | 1         | 1      | 3.85%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 3.85%   |
| Seagate ST9160310AS 160GB                    | 1         | 1      | 3.85%   |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 3.85%   |
| Seagate ST2000LX001-1RG174 2TB               | 1         | 1      | 3.85%   |
| Seagate ST1000LX015-1U7172 1TB               | 1         | 1      | 3.85%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 850 EVO 1TB          | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 2      | 3.85%   |
| Samsung Electronics HM321HI 320GB            | 1         | 1      | 3.85%   |
| LITEONIT LMT-64M6M-HP 64GB SSD               | 1         | 1      | 3.85%   |
| Kingston SV300S37A120G 120GB SSD             | 1         | 1      | 3.85%   |
| Intel SSDSC2KW120H6 120GB                    | 1         | 1      | 3.85%   |
| Intel SSDSC2BF180A4H 180GB                   | 1         | 1      | 3.85%   |
| Intel SSDSA2M160G2HP 160GB                   | 1         | 1      | 3.85%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 3.85%   |
| Hitachi HTS543212L9A300 120GB                | 1         | 1      | 3.85%   |
| Hitachi HTS542512K9SA00 120GB                | 1         | 1      | 3.85%   |
| Hitachi HTS541040G9AT00 40GB                 | 1         | 1      | 3.85%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 3.85%   |
| A-DATA Technology SU630 480GB SSD            | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 26.92%  |
| Hitachi             | 4         | 4      | 15.38%  |
| Toshiba             | 3         | 3      | 11.54%  |
| Samsung Electronics | 3         | 4      | 11.54%  |
| Intel               | 3         | 3      | 11.54%  |
| WDC                 | 2         | 2      | 7.69%   |
| LITEONIT            | 1         | 1      | 3.85%   |
| Kingston            | 1         | 1      | 3.85%   |
| HGST                | 1         | 1      | 3.85%   |
| A-DATA Technology   | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 38.89%  |
| Hitachi             | 4         | 4      | 22.22%  |
| Toshiba             | 3         | 3      | 16.67%  |
| WDC                 | 2         | 2      | 11.11%  |
| Samsung Electronics | 1         | 1      | 5.56%   |
| HGST                | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 18     | 69.23%  |
| SSD  | 8         | 9      | 30.77%  |

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
| Works    | 196       | 247    | 72.06%  |
| Detected | 50        | 69     | 18.38%  |
| Malfunc  | 26        | 27     | 9.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 152       | 54.68%  |
| Samsung Electronics          | 32        | 11.51%  |
| AMD                          | 23        | 8.27%   |
| Sandisk                      | 16        | 5.76%   |
| Toshiba America Info Systems | 8         | 2.88%   |
| SK Hynix                     | 8         | 2.88%   |
| Kingston Technology Company  | 8         | 2.88%   |
| KIOXIA                       | 5         | 1.8%    |
| Micron/Crucial Technology    | 4         | 1.44%   |
| Micron Technology            | 4         | 1.44%   |
| Apple                        | 4         | 1.44%   |
| ADATA Technology             | 4         | 1.44%   |
| Nvidia                       | 3         | 1.08%   |
| Union Memory (Shenzhen)      | 2         | 0.72%   |
| Lenovo                       | 2         | 0.72%   |
| Silicon Motion               | 1         | 0.36%   |
| Phison Electronics           | 1         | 0.36%   |
| Lite-On Technology           | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 23        | 7.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 19        | 6.53%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 6.53%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 6.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 17        | 5.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 14        | 4.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8         | 2.75%   |
| Intel Volume Management Device NVMe RAID Controller                              | 7         | 2.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 2.41%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 6         | 2.06%   |
| Samsung Electronics SATA controller                                              | 6         | 2.06%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 2.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 2.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 2.06%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 1.72%   |
| Samsung NVMe Controller                                                          | 5         | 1.72%   |
| KIOXIA Non-Volatile memory controller                                            | 5         | 1.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 1.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 1.72%   |
| Micron Non-Volatile memory controller                                            | 4         | 1.37%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 1.37%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 4         | 1.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 1.37%   |
| Apple S1X NVMe Controller                                                        | 4         | 1.37%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 1.03%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 1.03%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 3         | 1.03%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 1.03%   |
| Intel SSD 660P Series                                                            | 3         | 1.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.03%   |
| AMD IXP SB4x0 IDE Controller                                                     | 3         | 1.03%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 0.69%   |
| SK Hynix NVMe SSD Controller                                                     | 2         | 0.69%   |
| SK Hynix BC511                                                                   | 2         | 0.69%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.69%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 0.69%   |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 0.69%   |
| Sandisk Non-Volatile memory controller                                           | 2         | 0.69%   |
| Nvidia MCP79 AHCI Controller                                                     | 2         | 0.69%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 0.69%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 0.69%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.69%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 0.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.69%   |
| Intel 82801FBM (ICH6M) SATA Controller                                           | 2         | 0.69%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 2         | 0.69%   |
| Intel 82801DBM (ICH4-M) IDE Controller                                           | 2         | 0.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 0.69%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 2         | 0.69%   |
| ADATA Non-Volatile memory controller                                             | 2         | 0.69%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.34%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 1         | 0.34%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.34%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.34%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.34%   |
| Phison NVMe Storage Controller                                                   | 1         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 148       | 52.11%  |
| NVMe | 93        | 32.75%  |
| RAID | 24        | 8.45%   |
| IDE  | 19        | 6.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 207       | 85.19%  |
| AMD    | 36        | 14.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-5250U CPU @ 1.60GHz               | 9         | 3.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz               | 8         | 3.29%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 8         | 3.29%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 7         | 2.88%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 7         | 2.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 6         | 2.47%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 5         | 2.06%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 5         | 2.06%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 5         | 2.06%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 5         | 2.06%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 5         | 2.06%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 4         | 1.65%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 4         | 1.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 4         | 1.65%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 4         | 1.65%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 4         | 1.65%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 4         | 1.65%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 4         | 1.65%   |
| Intel Pentium CPU N4200 @ 1.10GHz               | 3         | 1.23%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 3         | 1.23%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 3         | 1.23%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 3         | 1.23%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 3         | 1.23%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 3         | 1.23%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 3         | 1.23%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 3         | 1.23%   |
| Intel Pentium M processor 1.73GHz               | 2         | 0.82%   |
| Intel Genuine CPU T1400 @ 1.73GHz               | 2         | 0.82%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 0.82%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 2         | 0.82%   |
| Intel Core i7-3612QM CPU @ 2.10GHz              | 2         | 0.82%   |
| Intel Core i7-3537U CPU @ 2.00GHz               | 2         | 0.82%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 2         | 0.82%   |
| Intel Core i7-2620M CPU @ 2.70GHz               | 2         | 0.82%   |
| Intel Core i7-10850H CPU @ 2.70GHz              | 2         | 0.82%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 2         | 0.82%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 0.82%   |
| Intel Core i5-2450M CPU @ 2.50GHz               | 2         | 0.82%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 2         | 0.82%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 2         | 0.82%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz            | 2         | 0.82%   |
| Intel Core 2 Duo CPU P7450 @ 2.13GHz            | 2         | 0.82%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                | 2         | 0.82%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 2         | 0.82%   |
| Intel Celeron M processor 900MHz                | 2         | 0.82%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 2         | 0.82%   |
| Intel Celeron CPU B800 @ 1.50GHz                | 2         | 0.82%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 2         | 0.82%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 2         | 0.82%   |
| AMD Turion 64 Mobile ML-30                      | 2         | 0.82%   |
| AMD Ryzen 7 PRO 3700U w/ Radeon Vega Mobile Gfx | 2         | 0.82%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G      | 2         | 0.82%   |
| Intel Xeon E-2176M CPU @ 2.70GHz                | 1         | 0.41%   |
| Intel Pentium M processor 1600MHz               | 1         | 0.41%   |
| Intel Pentium M processor 1500MHz               | 1         | 0.41%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz          | 1         | 0.41%   |
| Intel Pentium CPU B940 @ 2.00GHz                | 1         | 0.41%   |
| Intel Pentium CPU 4415U @ 2.30GHz               | 1         | 0.41%   |
| Intel Pentium 3556U @ 1.70GHz                   | 1         | 0.41%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 1         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 76        | 31.28%  |
| Intel Core i7        | 62        | 25.51%  |
| Other                | 19        | 7.82%   |
| Intel Celeron        | 13        | 5.35%   |
| Intel Core i3        | 10        | 4.12%   |
| Intel Core 2 Duo     | 10        | 4.12%   |
| AMD Ryzen 5          | 10        | 4.12%   |
| AMD Ryzen 7 PRO      | 7         | 2.88%   |
| AMD Ryzen 7          | 7         | 2.88%   |
| Intel Pentium        | 6         | 2.47%   |
| Intel Pentium M      | 4         | 1.65%   |
| Intel Genuine        | 2         | 0.82%   |
| Intel Core 2         | 2         | 0.82%   |
| Intel Celeron M      | 2         | 0.82%   |
| Intel Atom           | 2         | 0.82%   |
| AMD Turion 64 Mobile | 2         | 0.82%   |
| AMD Ryzen 3          | 2         | 0.82%   |
| Intel Xeon           | 1         | 0.41%   |
| Intel Pentium Dual   | 1         | 0.41%   |
| AMD Ryzen 9          | 1         | 0.41%   |
| AMD C-30             | 1         | 0.41%   |
| AMD Athlon 64        | 1         | 0.41%   |
| AMD A8               | 1         | 0.41%   |
| AMD A12              | 1         | 0.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 117       | 48.15%  |
| 4      | 82        | 33.74%  |
| 6      | 15        | 6.17%   |
| 1      | 15        | 6.17%   |
| 8      | 14        | 5.76%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 243       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 192       | 79.01%  |
| 1      | 51        | 20.99%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 235       | 96.71%  |
| 32-bit         | 8         | 3.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 16.33%  |
| 0x306a9    | 21        | 8.57%   |
| 0x306d4    | 17        | 6.94%   |
| 0x206a7    | 17        | 6.94%   |
| 0x806c1    | 14        | 5.71%   |
| 0x806ec    | 12        | 4.9%    |
| 0x806ea    | 9         | 3.67%   |
| 0x806e9    | 9         | 3.67%   |
| 0x906ea    | 8         | 3.27%   |
| 0x08600106 | 8         | 3.27%   |
| 0xa0652    | 7         | 2.86%   |
| 0x706e5    | 7         | 2.86%   |
| 0x406e3    | 6         | 2.45%   |
| 0x1067a    | 6         | 2.45%   |
| 0x08108109 | 6         | 2.45%   |
| 0x40651    | 5         | 2.04%   |
| 0x806eb    | 4         | 1.63%   |
| 0x6d8      | 4         | 1.63%   |
| 0x506c9    | 4         | 1.63%   |
| 0x20655    | 4         | 1.63%   |
| 0x6fd      | 3         | 1.22%   |
| 0x306c3    | 3         | 1.22%   |
| 0x0600611a | 3         | 1.22%   |
| 0x706a8    | 2         | 0.82%   |
| 0x6f6      | 2         | 0.82%   |
| 0x695      | 2         | 0.82%   |
| 0x30678    | 2         | 0.82%   |
| 0x106c2    | 2         | 0.82%   |
| 0x08600103 | 2         | 0.82%   |
| 0x08108102 | 2         | 0.82%   |
| 0x906e9    | 1         | 0.41%   |
| 0x6fa      | 1         | 0.41%   |
| 0x406c4    | 1         | 0.41%   |
| 0x406c3    | 1         | 0.41%   |
| 0x40661    | 1         | 0.41%   |
| 0x10676    | 1         | 0.41%   |
| 0x10661    | 1         | 0.41%   |
| 0x0a50000b | 1         | 0.41%   |
| 0x08608103 | 1         | 0.41%   |
| 0x08600104 | 1         | 0.41%   |
| 0x0810100b | 1         | 0.41%   |
| 0x06006705 | 1         | 0.41%   |
| 0x05000029 | 1         | 0.41%   |
| 0x03000027 | 1         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 53        | 21.81%  |
| IvyBridge     | 24        | 9.88%   |
| SandyBridge   | 17        | 7%      |
| Broadwell     | 17        | 7%      |
| TigerLake     | 16        | 6.58%   |
| Haswell       | 14        | 5.76%   |
| Zen 2         | 13        | 5.35%   |
| Zen+          | 10        | 4.12%   |
| Skylake       | 10        | 4.12%   |
| Penryn        | 8         | 3.29%   |
| Core          | 8         | 3.29%   |
| CometLake     | 8         | 3.29%   |
| Westmere      | 7         | 2.88%   |
| IceLake       | 7         | 2.88%   |
| P6            | 6         | 2.47%   |
| Silvermont    | 4         | 1.65%   |
| Goldmont      | 4         | 1.65%   |
| Excavator     | 4         | 1.65%   |
| K8 Hammer     | 3         | 1.23%   |
| Zen 3         | 2         | 0.82%   |
| Goldmont plus | 2         | 0.82%   |
| Bonnell       | 2         | 0.82%   |
| Zen           | 1         | 0.41%   |
| K10 Llano     | 1         | 0.41%   |
| Bobcat        | 1         | 0.41%   |
| Unknown       | 1         | 0.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 195       | 64.57%  |
| Nvidia | 55        | 18.21%  |
| AMD    | 52        | 17.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 7.3%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 5.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 4.44%   |
| Intel UHD Graphics 620                                                                   | 13        | 4.13%   |
| AMD Renoir                                                                               | 13        | 4.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 3.49%   |
| AMD Picasso                                                                              | 10        | 3.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 2.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.86%   |
| Intel HD Graphics 6000                                                                   | 9         | 2.86%   |
| Intel HD Graphics 620                                                                    | 8         | 2.54%   |
| Intel HD Graphics 5500                                                                   | 8         | 2.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.22%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 2.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 2.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 1.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 1.9%    |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.9%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 1.9%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.27%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 4         | 1.27%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.27%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 4         | 1.27%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 1.27%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.95%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.95%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.95%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                  | 3         | 0.95%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 2         | 0.63%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.63%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.63%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.63%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.63%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.63%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 2         | 0.63%   |
| Intel Tiger Lake UHD Graphics                                                            | 2         | 0.63%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 0.63%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.63%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 2         | 0.63%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.63%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.63%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.63%   |
| AMD Lexa XT [Radeon PRO WX 3100]                                                         | 2         | 0.63%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.63%   |
| AMD Cezanne                                                                              | 2         | 0.63%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.32%   |
| Nvidia TU117M                                                                            | 1         | 0.32%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 1         | 0.32%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.32%   |
| Nvidia TU104BM [GeForce RTX 2070 SUPER Mobile / Max-Q]                                   | 1         | 0.32%   |
| Nvidia NV34M [GeForce FX Go5200 64M]                                                     | 1         | 0.32%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.32%   |
| Nvidia GP108M [GeForce MX330]                                                            | 1         | 0.32%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 139       | 56.73%  |
| Intel + Nvidia | 45        | 18.37%  |
| 1 x AMD        | 35        | 14.29%  |
| Intel + AMD    | 11        | 4.49%   |
| 1 x Nvidia     | 8         | 3.27%   |
| 2 x AMD        | 3         | 1.22%   |
| AMD + Nvidia   | 3         | 1.22%   |
| Other          | 1         | 0.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 239       | 97.95%  |
| Proprietary | 3         | 1.23%   |
| Unknown     | 2         | 0.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 183       | 74.39%  |
| 0.01-0.5   | 27        | 10.98%  |
| 1.01-2.0   | 13        | 5.28%   |
| 0.51-1.0   | 13        | 5.28%   |
| 3.01-4.0   | 8         | 3.25%   |
| 7.01-8.0   | 1         | 0.41%   |
| 5.01-6.0   | 1         | 0.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 53        | 18.86%  |
| BOE                     | 40        | 14.23%  |
| Chimei Innolux          | 39        | 13.88%  |
| LG Display              | 35        | 12.46%  |
| Samsung Electronics     | 21        | 7.47%   |
| Apple                   | 17        | 6.05%   |
| Sharp                   | 10        | 3.56%   |
| Lenovo                  | 8         | 2.85%   |
| Dell                    | 8         | 2.85%   |
| Hewlett-Packard         | 5         | 1.78%   |
| Ancor Communications    | 5         | 1.78%   |
| ViewSonic               | 4         | 1.42%   |
| BenQ                    | 4         | 1.42%   |
| InfoVision              | 3         | 1.07%   |
| Chi Mei Optoelectronics | 3         | 1.07%   |
| Philips                 | 2         | 0.71%   |
| PANDA                   | 2         | 0.71%   |
| LG Philips              | 2         | 0.71%   |
| HannStar                | 2         | 0.71%   |
| Goldstar                | 2         | 0.71%   |
| CPT                     | 2         | 0.71%   |
| AOC                     | 2         | 0.71%   |
| ___                     | 1         | 0.36%   |
| Vestel Elektronik       | 1         | 0.36%   |
| Unknown                 | 1         | 0.36%   |
| NCS                     | 1         | 0.36%   |
| MSI                     | 1         | 0.36%   |
| LPL                     | 1         | 0.36%   |
| JXG                     | 1         | 0.36%   |
| JRY                     | 1         | 0.36%   |
| IOD                     | 1         | 0.36%   |
| CSO                     | 1         | 0.36%   |
| CMN                     | 1         | 0.36%   |
| ASUSTek Computer        | 1         | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch          | 4         | 1.41%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch            | 3         | 1.06%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch       | 3         | 1.06%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                   | 3         | 1.06%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 3         | 1.06%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch         | 3         | 1.06%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch          | 3         | 1.06%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                   | 3         | 1.06%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                   | 3         | 1.06%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                | 2         | 0.71%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                | 2         | 0.71%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 2         | 0.71%   |
| LG Philips LCD Monitor LPL1151 1024x768 304x228mm 15.0-inch            | 2         | 0.71%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch           | 2         | 0.71%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch           | 2         | 0.71%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch               | 2         | 0.71%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                | 2         | 0.71%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch           | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch       | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch       | 2         | 0.71%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 0.71%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.71%   |
| BOE LCD Monitor BOE0903 1920x1080 344x194mm 15.5-inch                  | 2         | 0.71%   |
| BOE LCD Monitor BOE06CE 1366x768 277x156mm 12.5-inch                   | 2         | 0.71%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                  | 2         | 0.71%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                   | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch          | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch          | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO5C2D 1920x1080 293x165mm 13.2-inch         | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO223E 1600x900 309x174mm 14.0-inch          | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch         | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch         | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch         | 2         | 0.71%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch          | 2         | 0.71%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                 | 2         | 0.71%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                   | 2         | 0.71%   |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 509x286mm 23.0-inch  | 2         | 0.71%   |
| ___ LCDTV16 ___0101 1600x1200 1600x900mm 72.3-inch                     | 1         | 0.35%   |
| ViewSonic XG2402 SERIES VSC1B35 1920x1080 531x299mm 24.0-inch          | 1         | 0.35%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch              | 1         | 0.35%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                 | 1         | 0.35%   |
| ViewSonic LCD Monitor XG2401 SERIES                                    | 1         | 0.35%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1         | 0.35%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                    | 1         | 0.35%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                | 1         | 0.35%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 1         | 0.35%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch                | 1         | 0.35%   |
| Sharp LCD Monitor SHP14D7 1920x1200 366x229mm 17.0-inch                | 1         | 0.35%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch                | 1         | 0.35%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch   | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM04D4 1920x1080 531x298mm 24.0-inch   | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch   | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0302 1680x1050 459x296mm 21.5-inch   | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0274 1440x900 410x257mm 19.1-inch    | 1         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 118       | 43.38%  |
| 1366x768 (WXGA)    | 65        | 23.9%   |
| 1600x900 (HD+)     | 15        | 5.51%   |
| 1280x800 (WXGA)    | 14        | 5.15%   |
| 3840x2160 (4K)     | 11        | 4.04%   |
| 1440x900 (WXGA+)   | 10        | 3.68%   |
| 2560x1440 (QHD)    | 8         | 2.94%   |
| 1920x1200 (WUXGA)  | 8         | 2.94%   |
| 1280x1024 (SXGA)   | 4         | 1.47%   |
| 1024x768 (XGA)     | 4         | 1.47%   |
| 1680x1050 (WSXGA+) | 3         | 1.1%    |
| 3440x1440          | 2         | 0.74%   |
| 1024x600           | 2         | 0.74%   |
| 3840x2400          | 1         | 0.37%   |
| 3840x1080          | 1         | 0.37%   |
| 2880x1800          | 1         | 0.37%   |
| 2560x1600          | 1         | 0.37%   |
| 2256x1504          | 1         | 0.37%   |
| 1792x768           | 1         | 0.37%   |
| 1600x1200          | 1         | 0.37%   |
| Unknown            | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 84        | 29.89%  |
| 13      | 62        | 22.06%  |
| 14      | 40        | 14.23%  |
| 17      | 19        | 6.76%   |
| 12      | 13        | 4.63%   |
| 11      | 13        | 4.63%   |
| 24      | 9         | 3.2%    |
| 23      | 8         | 2.85%   |
| 21      | 7         | 2.49%   |
| 27      | 3         | 1.07%   |
| 25      | 3         | 1.07%   |
| 19      | 3         | 1.07%   |
| 34      | 2         | 0.71%   |
| 31      | 2         | 0.71%   |
| 10      | 2         | 0.71%   |
| Unknown | 2         | 0.71%   |
| 84      | 1         | 0.36%   |
| 72      | 1         | 0.36%   |
| 47      | 1         | 0.36%   |
| 40      | 1         | 0.36%   |
| 33      | 1         | 0.36%   |
| 32      | 1         | 0.36%   |
| 22      | 1         | 0.36%   |
| 20      | 1         | 0.36%   |
| 18      | 1         | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 153       | 54.64%  |
| 201-300     | 60        | 21.43%  |
| 501-600     | 20        | 7.14%   |
| 351-400     | 20        | 7.14%   |
| 401-500     | 13        | 4.64%   |
| 701-800     | 4         | 1.43%   |
| 601-700     | 4         | 1.43%   |
| 1501-2000   | 2         | 0.71%   |
| Unknown     | 2         | 0.71%   |
| 801-900     | 1         | 0.36%   |
| 1001-1500   | 1         | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 200       | 78.74%  |
| 16/10   | 35        | 13.78%  |
| 4/3     | 6         | 2.36%   |
| 5/4     | 4         | 1.57%   |
| 3/2     | 4         | 1.57%   |
| 21/9    | 3         | 1.18%   |
| Unknown | 2         | 0.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 84        | 29.89%  |
| 81-90          | 79        | 28.11%  |
| 71-80          | 24        | 8.54%   |
| 201-250        | 20        | 7.12%   |
| 121-130        | 15        | 5.34%   |
| 51-60          | 13        | 4.63%   |
| 61-70          | 12        | 4.27%   |
| 351-500        | 6         | 2.14%   |
| 251-300        | 6         | 2.14%   |
| 151-200        | 6         | 2.14%   |
| 141-150        | 4         | 1.42%   |
| 301-350        | 3         | 1.07%   |
| More than 1000 | 2         | 0.71%   |
| 41-50          | 2         | 0.71%   |
| 501-1000       | 2         | 0.71%   |
| Unknown        | 2         | 0.71%   |
| 131-140        | 1         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 141       | 51.46%  |
| 101-120       | 59        | 21.53%  |
| 51-100        | 46        | 16.79%  |
| 161-240       | 18        | 6.57%   |
| More than 240 | 6         | 2.19%   |
| 1-50          | 2         | 0.73%   |
| Unknown       | 2         | 0.73%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 198       | 81.15%  |
| 2     | 39        | 15.98%  |
| 3     | 4         | 1.64%   |
| 0     | 3         | 1.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 150       | 40.43%  |
| Realtek Semiconductor             | 105       | 28.3%   |
| Qualcomm Atheros                  | 44        | 11.86%  |
| Broadcom                          | 23        | 6.2%    |
| Broadcom Limited                  | 15        | 4.04%   |
| Marvell Technology Group          | 5         | 1.35%   |
| Nvidia                            | 3         | 0.81%   |
| Ericsson Business Mobile Networks | 3         | 0.81%   |
| AMD                               | 3         | 0.81%   |
| Ralink                            | 2         | 0.54%   |
| DisplayLink                       | 2         | 0.54%   |
| Dell                              | 2         | 0.54%   |
| Cypress Semiconductor             | 2         | 0.54%   |
| Xiaomi                            | 1         | 0.27%   |
| Sierra Wireless                   | 1         | 0.27%   |
| Qualcomm                          | 1         | 0.27%   |
| Microchip Technology              | 1         | 0.27%   |
| MEDIATEK                          | 1         | 0.27%   |
| JMicron Technology                | 1         | 0.27%   |
| Huawei Technologies               | 1         | 0.27%   |
| Hewlett-Packard                   | 1         | 0.27%   |
| Fibocom                           | 1         | 0.27%   |
| Edimax Technology                 | 1         | 0.27%   |
| D-Link                            | 1         | 0.27%   |
| Attansic Technology               | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 70        | 15.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 20        | 4.35%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 2.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 12        | 2.61%   |
| Intel Wireless 8265 / 8275                                              | 12        | 2.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 2.61%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 2.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 1.96%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 9         | 1.96%   |
| Intel Wireless 7260                                                     | 8         | 1.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 1.52%   |
| Intel Wireless 8260                                                     | 7         | 1.52%   |
| Intel Ethernet Connection (4) I219-V                                    | 7         | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.3%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 1.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 1.09%   |
| Intel Wireless 7265                                                     | 5         | 1.09%   |
| Intel Wireless 3160                                                     | 5         | 1.09%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 1.09%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.87%   |
| Intel Ethernet Connection I218-LM                                       | 4         | 0.87%   |
| Intel Ethernet Connection (6) I219-V                                    | 4         | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.87%   |
| Intel Centrino Wireless-N 2230                                          | 4         | 0.87%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 0.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.65%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 3         | 0.65%   |
| Intel Wireless 3165                                                     | 3         | 0.65%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.65%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.65%   |
| AMD IXP SB400 AC'97 Modem Controller                                    | 3         | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 0.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 2         | 0.43%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.43%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 2         | 0.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.43%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.43%   |
| Nvidia MCP79 Ethernet                                                   | 2         | 0.43%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.43%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 2         | 0.43%   |
| Intel Ethernet Connection I219-V                                        | 2         | 0.43%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.43%   |
| Intel Ethernet Connection (13) I219-V                                   | 2         | 0.43%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 2         | 0.43%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Modem Controller       | 2         | 0.43%   |
| Cypress K38231_03                                                       | 2         | 0.43%   |
| Broadcom NetXtreme BCM5788 Gigabit Ethernet                             | 2         | 0.43%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                       | 2         | 0.43%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 145       | 59.18%  |
| Qualcomm Atheros                  | 38        | 15.51%  |
| Realtek Semiconductor             | 28        | 11.43%  |
| Broadcom Limited                  | 14        | 5.71%   |
| Broadcom                          | 12        | 4.9%    |
| Ralink                            | 2         | 0.82%   |
| Sierra Wireless                   | 1         | 0.41%   |
| Qualcomm                          | 1         | 0.41%   |
| MEDIATEK                          | 1         | 0.41%   |
| Fibocom                           | 1         | 0.41%   |
| Ericsson Business Mobile Networks | 1         | 0.41%   |
| Edimax Technology                 | 1         | 0.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                   | 17        | 6.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 13        | 5.28%   |
| Intel Wireless 8265 / 8275                                                            | 12        | 4.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 12        | 4.88%   |
| Intel Wi-Fi 6 AX201                                                                   | 10        | 4.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 9         | 3.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 9         | 3.66%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 9         | 3.66%   |
| Intel Wireless 7260                                                                   | 8         | 3.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 7         | 2.85%   |
| Intel Wireless 8260                                                                   | 7         | 2.85%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 7         | 2.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 7         | 2.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 6         | 2.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 6         | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 5         | 2.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 5         | 2.03%   |
| Intel Wireless 7265                                                                   | 5         | 2.03%   |
| Intel Wireless 3160                                                                   | 5         | 2.03%   |
| Intel Centrino Ultimate-N 6300                                                        | 5         | 2.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 4         | 1.63%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 4         | 1.63%   |
| Intel Centrino Wireless-N 2230                                                        | 4         | 1.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 3         | 1.22%   |
| Intel Wireless 3165                                                                   | 3         | 1.22%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                       | 3         | 1.22%   |
| Intel Centrino Advanced-N 6200                                                        | 3         | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 0.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 2         | 0.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 2         | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 2         | 0.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 0.81%   |
| Intel Wireless-AC 9260                                                                | 2         | 0.81%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                             | 2         | 0.81%   |
| Broadcom Limited BCM4318 [AirForce 54g] 802.11a/b/g PCI Express Transceiver           | 2         | 0.81%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 0.81%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 2         | 0.81%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 2         | 0.81%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                                   | 1         | 0.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1         | 0.41%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 0.41%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1         | 0.41%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.41%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                       | 1         | 0.41%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                              | 1         | 0.41%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.41%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                             | 1         | 0.41%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]                           | 1         | 0.41%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 0.41%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.41%   |
| MEDIATEK Network controller                                                           | 1         | 0.41%   |
| Intel Wireless Gigabit 17265                                                          | 1         | 0.41%   |
| Intel WiFi Link 5100                                                                  | 1         | 0.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 1         | 0.41%   |
| Intel PRO/Wireless LAN 2100 3B Mini PCI Adapter                                       | 1         | 0.41%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                               | 1         | 0.41%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 1         | 0.41%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 1         | 0.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 1         | 0.41%   |
| Intel Centrino Wireless-N 2200                                                        | 1         | 0.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 91        | 45.27%  |
| Intel                    | 64        | 31.84%  |
| Broadcom                 | 14        | 6.97%   |
| Qualcomm Atheros         | 12        | 5.97%   |
| Marvell Technology Group | 5         | 2.49%   |
| Nvidia                   | 3         | 1.49%   |
| DisplayLink              | 2         | 1%      |
| Cypress Semiconductor    | 2         | 1%      |
| Broadcom Limited         | 2         | 1%      |
| Xiaomi                   | 1         | 0.5%    |
| Microchip Technology     | 1         | 0.5%    |
| JMicron Technology       | 1         | 0.5%    |
| Huawei Technologies      | 1         | 0.5%    |
| D-Link                   | 1         | 0.5%    |
| Attansic Technology      | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 70        | 34.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20        | 9.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 5.94%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 3.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.48%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 2.48%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.98%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 1.98%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.98%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.98%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 1.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.99%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.99%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.99%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.99%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.99%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.99%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.99%   |
| Cypress K38231_03                                                 | 2         | 0.99%   |
| Broadcom NetXtreme BCM5788 Gigabit Ethernet                       | 2         | 0.99%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.99%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.99%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 0.99%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.5%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.5%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.5%    |
| Nvidia MCP89 Ethernet                                             | 1         | 0.5%    |
| Microchip LAN9512/LAN9514 Ethernet 10/100 Adapter (SAL10)         | 1         | 0.5%    |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.5%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.5%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.5%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.5%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.5%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.5%    |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.5%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.5%    |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.5%    |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.5%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.5%    |
| Intel 82801DB PRO/100 VM (MOB) Ethernet Controller                | 1         | 0.5%    |
| Intel 82577LC Gigabit Network Connection                          | 1         | 0.5%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.5%    |
| Huawei E353/E3131                                                 | 1         | 0.5%    |
| DisplayLink USB3.0 Dual Video Dock                                | 1         | 0.5%    |
| DisplayLink Dell Universal Dock D6000                             | 1         | 0.5%    |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 1         | 0.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.5%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.5%    |
| Broadcom Limited NetXtreme BCM5753M Gigabit Ethernet PCI Express  | 1         | 0.5%    |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe           | 1         | 0.5%    |
| Broadcom BCM4401 100Base-T                                        | 1         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 237       | 53.62%  |
| Ethernet | 193       | 43.67%  |
| Modem    | 12        | 2.71%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 224       | 62.4%   |
| Ethernet | 134       | 37.33%  |
| Modem    | 1         | 0.28%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 175       | 72.02%  |
| 1     | 63        | 25.93%  |
| 3     | 5         | 2.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 192       | 78.69%  |
| Yes  | 52        | 21.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 101       | 52.33%  |
| Qualcomm Atheros Communications | 18        | 9.33%   |
| Apple                           | 16        | 8.29%   |
| Realtek Semiconductor           | 15        | 7.77%   |
| Broadcom                        | 11        | 5.7%    |
| Lite-On Technology              | 8         | 4.15%   |
| IMC Networks                    | 5         | 2.59%   |
| Hewlett-Packard                 | 4         | 2.07%   |
| Realtek                         | 3         | 1.55%   |
| Foxconn / Hon Hai               | 3         | 1.55%   |
| Cambridge Silicon Radio         | 3         | 1.55%   |
| Toshiba                         | 2         | 1.04%   |
| Dell                            | 2         | 1.04%   |
| Taiyo Yuden                     | 1         | 0.52%   |
| Ralink                          | 1         | 0.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 40        | 20.73%  |
| Intel Bluetooth wireless interface                  | 35        | 18.13%  |
| Intel AX200 Bluetooth                               | 18        | 9.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 6.22%   |
| Realtek Bluetooth Radio                             | 10        | 5.18%   |
| Apple Bluetooth USB Host Controller                 | 9         | 4.66%   |
| Lite-On Bluetooth Device                            | 5         | 2.59%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 2.59%   |
| Broadcom BCM2045B (BDC-2.1)                         | 5         | 2.59%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 2.07%   |
| Realtek Bluetooth Radio                             | 3         | 1.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.55%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.55%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.55%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.55%   |
| Apple Bluetooth Host Controller                     | 3         | 1.55%   |
| Toshiba Bluetooth Device                            | 2         | 1.04%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 1.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.04%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.04%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 1.04%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 2         | 1.04%   |
| Taiyo Yuden Bluetooth Device                        | 1         | 0.52%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.52%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.52%   |
| Realtek CSR BS8510                                  | 1         | 0.52%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.52%   |
| Lite-On Wireless_Device                             | 1         | 0.52%   |
| Lite-On BCM43142A0                                  | 1         | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.52%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.52%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.52%   |
| IMC Networks Bluetooth Device                       | 1         | 0.52%   |
| IMC Networks Bluetooth                              | 1         | 0.52%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.52%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.52%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.52%   |
| Dell BCM20702A0                                     | 1         | 0.52%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 204       | 69.86%  |
| AMD                    | 40        | 13.7%   |
| Nvidia                 | 30        | 10.27%  |
| Generalplus Technology | 4         | 1.37%   |
| Plantronics            | 3         | 1.03%   |
| C-Media Electronics    | 3         | 1.03%   |
| Texas Instruments      | 2         | 0.68%   |
| Logitech               | 2         | 0.68%   |
| GN Netcom              | 2         | 0.68%   |
| Razer USA              | 1         | 0.34%   |
| Creative Technology    | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 32        | 9.01%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 27        | 7.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 26        | 7.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 17        | 4.79%   |
| Intel Broadwell-U Audio Controller                                                                | 17        | 4.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 16        | 4.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 4.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 15        | 4.23%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 3.1%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 3.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 2.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 2.54%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.25%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 2.25%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 2.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 1.97%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 7         | 1.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 1.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.41%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 1.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.13%   |
| Generalplus Technology USB Audio Device                                                           | 4         | 1.13%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.13%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.85%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 0.85%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 3         | 0.85%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.56%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.56%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.56%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 2         | 0.56%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.56%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.56%   |
| Razer USA Razer Thresher 7.1                                                                      | 1         | 0.28%   |
| Plantronics DA40                                                                                  | 1         | 0.28%   |
| Plantronics Blackwire 3225 Series                                                                 | 1         | 0.28%   |
| Plantronics Blackwire 315.1                                                                       | 1         | 0.28%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.28%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.28%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.28%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.28%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.28%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.28%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.28%   |
| Nvidia Audio device                                                                               | 1         | 0.28%   |
| Logitech USB Headset                                                                              | 1         | 0.28%   |
| Logitech Headset H340                                                                             | 1         | 0.28%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.28%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.28%   |
| GN Netcom Jabra UC VOICE 550 MS USB                                                               | 1         | 0.28%   |
| GN Netcom Jabra Link 380                                                                          | 1         | 0.28%   |
| Creative Technology Sound Blaster Play! 3                                                         | 1         | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 69        | 25.75%  |
| Samsung Electronics | 68        | 25.37%  |
| Micron Technology   | 27        | 10.07%  |
| Kingston            | 24        | 8.96%   |
| Unknown             | 19        | 7.09%   |
| Crucial             | 18        | 6.72%   |
| A-DATA Technology   | 9         | 3.36%   |
| Ramaxel Technology  | 7         | 2.61%   |
| Nanya Technology    | 6         | 2.24%   |
| Corsair             | 6         | 2.24%   |
| ELPIDA              | 4         | 1.49%   |
| Team                | 2         | 0.75%   |
| Unknown (ABCD)      | 1         | 0.37%   |
| Unifosa             | 1         | 0.37%   |
| SMART Brazil        | 1         | 0.37%   |
| Smart               | 1         | 0.37%   |
| PNY                 | 1         | 0.37%   |
| Kllisre             | 1         | 0.37%   |
| Infineon            | 1         | 0.37%   |
| GOODRAM             | 1         | 0.37%   |
| G.Skill             | 1         | 0.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 5         | 1.78%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 5         | 1.78%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s           | 4         | 1.42%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 4         | 1.42%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s            | 4         | 1.42%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 3         | 1.07%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s    | 3         | 1.07%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                         | 3         | 1.07%   |
| Samsung RAM Module 1GB SODIMM DDR2 533MT/s                          | 3         | 1.07%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s            | 3         | 1.07%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 3         | 1.07%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 3         | 1.07%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s             | 3         | 1.07%   |
| Kingston RAM 99U5469-046.A00LF 4GB SODIMM DDR3 1333MT/s             | 3         | 1.07%   |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s          | 3         | 1.07%   |
| Unknown RAM Module 512MB SODIMM DDR2 400MT/s                        | 2         | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                         | 2         | 0.71%   |
| Unknown RAM Module 1GB SODIMM SDRAM                                 | 2         | 0.71%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 800MT/s                         | 2         | 0.71%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 667MT/s                         | 2         | 0.71%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.71%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.71%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 2         | 0.71%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 2         | 0.71%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 2         | 0.71%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.71%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s              | 2         | 0.71%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                         | 2         | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.71%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.71%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 2         | 0.71%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 2         | 0.71%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 2         | 0.71%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.71%   |
| Samsung RAM M4 70L6524CU0-CB3 512MB SODIMM DDR 333MT/s              | 2         | 0.71%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4096MB SODIMM DDR4 2667MT/s        | 2         | 0.71%   |
| Nanya RAM NT512D64SH8B0GN-6K 512MB SODIMM DDR 333MT/s               | 2         | 0.71%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s      | 2         | 0.71%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 2         | 0.71%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s              | 2         | 0.71%   |
| Crucial RAM CT8G4SFRA32A.C8FE 8GB SODIMM DDR4 3200MT/s              | 2         | 0.71%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s             | 2         | 0.71%   |
| Unknown SODIMM 2GB SODIMM DDR2 667MT/s                              | 1         | 0.36%   |
| Unknown SODIMM 2GB SODIMM DDR2 533MT/s                              | 1         | 0.36%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                              | 1         | 0.36%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                         | 1         | 0.36%   |
| Unknown RAM Module 512MB SODIMM DRAM                                | 1         | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                         | 1         | 0.36%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.36%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 1         | 0.36%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.36%   |
| Unknown RAM Module 2GB DDR3 1600MT/s                                | 1         | 0.36%   |
| Unknown RAM Module 256MB SODIMM DDR 333MT/s                         | 1         | 0.36%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                          | 1         | 0.36%   |
| Unknown RAM Module 16GB Row Of Chips LPDDR4 4267MT/s                | 1         | 0.36%   |
| Unknown RAM EE73I1B1674EU 2GB SODIMM DDR3 1334MT/s                  | 1         | 0.36%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.36%   |
| Unifosa RAM GU672203EP0200 1GB SODIMM DDR3 1333MT/s                 | 1         | 0.36%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s               | 1         | 0.36%   |
| Team RAM Module 8GB SODIMM DDR4 2133MT/s                            | 1         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 105       | 46.05%  |
| DDR3   | 82        | 35.96%  |
| DDR2   | 16        | 7.02%   |
| LPDDR3 | 9         | 3.95%   |
| LPDDR4 | 7         | 3.07%   |
| DDR    | 5         | 2.19%   |
| SDRAM  | 3         | 1.32%   |
| DRAM   | 1         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 207       | 91.19%  |
| Row Of Chips | 19        | 8.37%   |
| Unknown      | 1         | 0.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 79        | 32.11%  |
| 4096  | 76        | 30.89%  |
| 16384 | 34        | 13.82%  |
| 2048  | 25        | 10.16%  |
| 1024  | 17        | 6.91%   |
| 32768 | 7         | 2.85%   |
| 512   | 6         | 2.44%   |
| 256   | 2         | 0.81%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 60        | 24.59%  |
| 2667    | 52        | 21.31%  |
| 3200    | 37        | 15.16%  |
| 2400    | 19        | 7.79%   |
| 2133    | 15        | 6.15%   |
| 1334    | 15        | 6.15%   |
| 1333    | 14        | 5.74%   |
| 667     | 5         | 2.05%   |
| 533     | 5         | 2.05%   |
| 333     | 4         | 1.64%   |
| Unknown | 4         | 1.64%   |
| 4267    | 3         | 1.23%   |
| 400     | 3         | 1.23%   |
| 1067    | 2         | 0.82%   |
| 800     | 2         | 0.82%   |
| 4266    | 1         | 0.41%   |
| 4199    | 1         | 0.41%   |
| 1867    | 1         | 0.41%   |
| 975     | 1         | 0.41%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Samsung ML-2010P Mono Laser Printer | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 50%     |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 44        | 22.45%  |
| IMC Networks                           | 33        | 16.84%  |
| Acer                                   | 22        | 11.22%  |
| Realtek Semiconductor                  | 17        | 8.67%   |
| Microdia                               | 16        | 8.16%   |
| Quanta                                 | 10        | 5.1%    |
| Lite-On Technology                     | 10        | 5.1%    |
| Sunplus Innovation Technology          | 8         | 4.08%   |
| Suyin                                  | 6         | 3.06%   |
| Luxvisions Innotech Limited            | 5         | 2.55%   |
| Apple                                  | 5         | 2.55%   |
| Syntek                                 | 4         | 2.04%   |
| Logitech                               | 4         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.04%   |
| Z-Star Microelectronics                | 1         | 0.51%   |
| Primax Electronics                     | 1         | 0.51%   |
| Pixart Imaging                         | 1         | 0.51%   |
| Lenovo                                 | 1         | 0.51%   |
| eMPIA Technology                       | 1         | 0.51%   |
| ALi                                    | 1         | 0.51%   |
| Alcor Micro                            | 1         | 0.51%   |
| A4Tech                                 | 1         | 0.51%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony Integrated Camera                     | 15        | 7.61%   |
| IMC Networks Integrated Camera                | 12        | 6.09%   |
| Microdia Integrated_Webcam_HD                 | 9         | 4.57%   |
| Realtek Integrated_Webcam_HD                  | 8         | 4.06%   |
| IMC Networks USB2.0 HD UVC WebCam             | 8         | 4.06%   |
| Acer Integrated Camera                        | 7         | 3.55%   |
| Chicony HD Webcam                             | 6         | 3.05%   |
| Chicony HP HD Camera                          | 5         | 2.54%   |
| Acer SunplusIT Integrated Camera              | 5         | 2.54%   |
| Lite-On Integrated Camera                     | 4         | 2.03%   |
| Sunplus Integrated_Webcam_HD                  | 3         | 1.52%   |
| Realtek Integrated Webcam                     | 3         | 1.52%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 3         | 1.52%   |
| Syntek Integrated Camera                      | 2         | 1.02%   |
| Quanta HD Webcam                              | 2         | 1.02%   |
| Microdia Integrated Webcam HD                 | 2         | 1.02%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 1.02%   |
| Luxvisions Innotech Limited HP HD Camera      | 2         | 1.02%   |
| Logitech C505 HD Webcam                       | 2         | 1.02%   |
| Lite-On HP Webcam                             | 2         | 1.02%   |
| Lite-On HP HD Camera                          | 2         | 1.02%   |
| IMC Networks USB2.0 HD IR UVC WebCam          | 2         | 1.02%   |
| IMC Networks ov9734_azurewave_camera          | 2         | 1.02%   |
| IMC Networks Lenovo EasyCamera                | 2         | 1.02%   |
| Chicony USB2.0 Camera                         | 2         | 1.02%   |
| Chicony ThinkPad T490 Webcam                  | 2         | 1.02%   |
| Chicony Lenovo EasyCamera                     | 2         | 1.02%   |
| Chicony Integrated Camera (1280x720@30)       | 2         | 1.02%   |
| Chicony HP HD Webcam                          | 2         | 1.02%   |
| Apple FaceTime HD Camera                      | 2         | 1.02%   |
| Acer ThinkPad Integrated Camera               | 2         | 1.02%   |
| Acer Lenovo Integrated Webcam                 | 2         | 1.02%   |
| Acer EasyCamera                               | 2         | 1.02%   |
| Z-Star Sirius USB2.0 Camera                   | 1         | 0.51%   |
| Syntek USB 2.0 UVC PC Camera                  | 1         | 0.51%   |
| Syntek Lenovo EasyCamera                      | 1         | 0.51%   |
| Suyin Laptop_Integrated_Webcam_HD             | 1         | 0.51%   |
| Suyin HP TrueVision HD Integrated Webcam      | 1         | 0.51%   |
| Suyin HP TrueVision Full HD                   | 1         | 0.51%   |
| Suyin HD WebCam                               | 1         | 0.51%   |
| Suyin Acer/HP Integrated Webcam [CN0314]      | 1         | 0.51%   |
| Suyin Acer CrystalEye Webcam                  | 1         | 0.51%   |
| Sunplus Laptop_Integrated_Webcam_HD           | 1         | 0.51%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 1         | 0.51%   |
| Sunplus Laptop Integrated Webcam FHD          | 1         | 0.51%   |
| Sunplus HP Universal Camera                   | 1         | 0.51%   |
| Sunplus 1.3M HD WebCam                        | 1         | 0.51%   |
| Realtek USB2.0-Camera                         | 1         | 0.51%   |
| Realtek USB Camera                            | 1         | 0.51%   |
| Realtek Lenovo EasyCamera                     | 1         | 0.51%   |
| Realtek HD WebCam                             | 1         | 0.51%   |
| Realtek EasyCamera                            | 1         | 0.51%   |
| Realtek Acer 640 x 480 laptop camera          | 1         | 0.51%   |
| Quanta VGA WebCam                             | 1         | 0.51%   |
| Quanta ov9734_techfront_camera                | 1         | 0.51%   |
| Quanta HP Wide Vision HD Camera               | 1         | 0.51%   |
| Quanta HP Webcam                              | 1         | 0.51%   |
| Quanta HP TrueVision HD Camera                | 1         | 0.51%   |
| Quanta HP HD Camera                           | 1         | 0.51%   |
| Quanta HD User Facing                         | 1         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 18        | 36%     |
| Validity Sensors           | 10        | 20%     |
| Shenzhen Goodix Technology | 9         | 18%     |
| Upek                       | 5         | 10%     |
| AuthenTec                  | 4         | 8%      |
| Elan Microelectronics      | 3         | 6%      |
| LighTuning Technology      | 1         | 2%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 18%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 10%     |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 10%     |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 10%     |
| Shenzhen Goodix FingerPrint                                                | 4         | 8%      |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 6%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 6%      |
| Elan ELAN:Fingerprint                                                      | 3         | 6%      |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 6%      |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4%      |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2%      |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 2%      |
| Validity Sensors Synaptics WBDI                                            | 1         | 2%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2%      |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 2%      |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 2%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 11        | 40.74%  |
| Broadcom    | 7         | 25.93%  |
| Lenovo      | 5         | 18.52%  |
| Upek        | 3         | 11.11%  |
| O2 Micro    | 1         | 3.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 40.74%  |
| Lenovo Integrated Smart Card Reader                                          | 5         | 18.52%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 7.41%   |
| Broadcom 5880                                                                | 2         | 7.41%   |
| Broadcom 58200                                                               | 2         | 7.41%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.7%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 156       | 63.41%  |
| 1     | 61        | 24.8%   |
| 2     | 27        | 10.98%  |
| 4     | 1         | 0.41%   |
| 3     | 1         | 0.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 50        | 42.02%  |
| Chipcard                 | 23        | 19.33%  |
| Graphics card            | 15        | 12.61%  |
| Multimedia controller    | 13        | 10.92%  |
| Net/wireless             | 6         | 5.04%   |
| Storage                  | 3         | 2.52%   |
| Communication controller | 3         | 2.52%   |
| Network                  | 2         | 1.68%   |
| Modem                    | 1         | 0.84%   |
| Firewire controller      | 1         | 0.84%   |
| Card reader              | 1         | 0.84%   |
| Bluetooth                | 1         | 0.84%   |

