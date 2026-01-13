Elementary - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------

A project to collect tested hardware configurations for Elementary.

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

Total: 2495

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 15 Notebook PC              | [15a218e733](https://linux-hardware.org/?probe=15a218e733) | Dec 31, 2025 |
| Lenovo        | LOQ 15APH8 82XT             | [f58d4c35ba](https://linux-hardware.org/?probe=f58d4c35ba) | Dec 31, 2025 |
| Dell          | Latitude E5550              | [636764d2b2](https://linux-hardware.org/?probe=636764d2b2) | Dec 28, 2025 |
| Apple         | MacBookPro8,1               | [5c77a53c22](https://linux-hardware.org/?probe=5c77a53c22) | Dec 25, 2025 |
| ASUSTek       | K93SV                       | [45c8a2efd7](https://linux-hardware.org/?probe=45c8a2efd7) | Dec 25, 2025 |
| Dell          | XPS 15 9530                 | [3d19ddb3ef](https://linux-hardware.org/?probe=3d19ddb3ef) | Dec 25, 2025 |
| Dell          | XPS 15 9530                 | [75e5963f66](https://linux-hardware.org/?probe=75e5963f66) | Dec 25, 2025 |
| ASUSTek       | K93SV                       | [468f690e44](https://linux-hardware.org/?probe=468f690e44) | Dec 23, 2025 |
| Casper        | W7x0S                       | [2620e4e75d](https://linux-hardware.org/?probe=2620e4e75d) | Dec 21, 2025 |
| Timi          | TM1701                      | [e791021e4c](https://linux-hardware.org/?probe=e791021e4c) | Dec 20, 2025 |
| Lenovo        | G50-80 80L0                 | [0fdc5cbe39](https://linux-hardware.org/?probe=0fdc5cbe39) | Dec 20, 2025 |
| Apple         | MacBookPro8,1               | [68c7d0358e](https://linux-hardware.org/?probe=68c7d0358e) | Dec 17, 2025 |
| Apple         | MacBookPro11,1              | [df8461eb0e](https://linux-hardware.org/?probe=df8461eb0e) | Dec 17, 2025 |
| HP            | Victus by Gaming Laptop ... | [96d1e843c6](https://linux-hardware.org/?probe=96d1e843c6) | Dec 17, 2025 |
| Dell          | Latitude 5580               | [3c615a7827](https://linux-hardware.org/?probe=3c615a7827) | Dec 16, 2025 |
| Dell          | Vostro1710                  | [c89e03644c](https://linux-hardware.org/?probe=c89e03644c) | Dec 15, 2025 |
| Acer          | Aspire E1-572               | [baad0ebb61](https://linux-hardware.org/?probe=baad0ebb61) | Dec 15, 2025 |
| Dell          | Latitude 5580               | [577d0c916a](https://linux-hardware.org/?probe=577d0c916a) | Dec 15, 2025 |
| Dell          | Latitude E5470              | [e5400c2e38](https://linux-hardware.org/?probe=e5400c2e38) | Dec 13, 2025 |
| HP            | Pavilion dv6                | [eff37a462b](https://linux-hardware.org/?probe=eff37a462b) | Dec 12, 2025 |
| HP            | Pavilion dv7                | [514e74de8d](https://linux-hardware.org/?probe=514e74de8d) | Dec 12, 2025 |
| HP            | Laptop 15-bs1xx             | [7f123d305e](https://linux-hardware.org/?probe=7f123d305e) | Dec 12, 2025 |
| Apple         | MacBookPro9,1               | [551fe38305](https://linux-hardware.org/?probe=551fe38305) | Dec 08, 2025 |
| Apple         | MacBookPro8,1               | [dc1e0eff2b](https://linux-hardware.org/?probe=dc1e0eff2b) | Dec 07, 2025 |
| Apple         | MacBookPro8,1               | [a077455bdc](https://linux-hardware.org/?probe=a077455bdc) | Dec 07, 2025 |
| HP            | ProBook 455 G8 Notebook ... | [0ea33de05c](https://linux-hardware.org/?probe=0ea33de05c) | Dec 07, 2025 |
| ASUSTek       | GL752VW                     | [ff85424fb4](https://linux-hardware.org/?probe=ff85424fb4) | Dec 06, 2025 |
| Apple         | MacBookPro9,2               | [6a37e56e72](https://linux-hardware.org/?probe=6a37e56e72) | Dec 05, 2025 |
| Apple         | MacBookPro9,2               | [f54a4a4f69](https://linux-hardware.org/?probe=f54a4a4f69) | Dec 05, 2025 |
| Apple         | MacBookPro8,1               | [eb6e2fa808](https://linux-hardware.org/?probe=eb6e2fa808) | Dec 04, 2025 |
| Dell          | Latitude 7480               | [d8dd6efc6f](https://linux-hardware.org/?probe=d8dd6efc6f) | Dec 03, 2025 |
| HP            | EliteBook 845 G7 Noteboo... | [25c8c68d2b](https://linux-hardware.org/?probe=25c8c68d2b) | Dec 03, 2025 |
| Dell          | Vostro1710                  | [03fd0bc5e8](https://linux-hardware.org/?probe=03fd0bc5e8) | Dec 02, 2025 |
| Dell          | Latitude 7480               | [791cf3c99f](https://linux-hardware.org/?probe=791cf3c99f) | Dec 02, 2025 |
| ASUSTek       | UX303LB                     | [4926819f4f](https://linux-hardware.org/?probe=4926819f4f) | Nov 30, 2025 |
| ASUSTek       | UX303LB                     | [8bc2e68390](https://linux-hardware.org/?probe=8bc2e68390) | Nov 30, 2025 |
| Dell          | XPS 15 9500                 | [a2bf61d881](https://linux-hardware.org/?probe=a2bf61d881) | Nov 30, 2025 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | [679084cf58](https://linux-hardware.org/?probe=679084cf58) | Nov 29, 2025 |
| Acer          | Aspire 7715Z                | [3ee36053d6](https://linux-hardware.org/?probe=3ee36053d6) | Nov 29, 2025 |
| Lenovo        | ThinkPad T14 Gen 4 21HES... | [9c47040b32](https://linux-hardware.org/?probe=9c47040b32) | Nov 29, 2025 |
| Lenovo        | ThinkPad T14 Gen 4 21HES... | [4a51a30c0c](https://linux-hardware.org/?probe=4a51a30c0c) | Nov 29, 2025 |
| Apple         | MacBookAir5,2               | [313ee19aab](https://linux-hardware.org/?probe=313ee19aab) | Nov 27, 2025 |
| HP            | Laptop 15-bs1xx             | [38eaee6ffe](https://linux-hardware.org/?probe=38eaee6ffe) | Nov 24, 2025 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [02bb00984c](https://linux-hardware.org/?probe=02bb00984c) | Nov 23, 2025 |
| Dell          | Inspiron 3541               | [3b7290f600](https://linux-hardware.org/?probe=3b7290f600) | Nov 23, 2025 |
| Dell          | Inspiron 3541               | [14add25ddb](https://linux-hardware.org/?probe=14add25ddb) | Nov 23, 2025 |
| Timi          | TM1701                      | [9298267905](https://linux-hardware.org/?probe=9298267905) | Nov 22, 2025 |
| Apple         | MacBookPro7,1               | [435b4312b6](https://linux-hardware.org/?probe=435b4312b6) | Nov 21, 2025 |
| Lenovo        | V14 G2 ITL 82KA             | [60c3603a43](https://linux-hardware.org/?probe=60c3603a43) | Nov 21, 2025 |
| Apple         | MacBookAir7,2               | [21479e5252](https://linux-hardware.org/?probe=21479e5252) | Nov 21, 2025 |
| Apple         | MacBookPro7,1               | [7312ab1846](https://linux-hardware.org/?probe=7312ab1846) | Nov 21, 2025 |
| Lenovo        | ThinkPad T490 20N2004HAD    | [673ef1ec1f](https://linux-hardware.org/?probe=673ef1ec1f) | Nov 20, 2025 |
| Acer          | Aspire 5755                 | [2d5f49bf19](https://linux-hardware.org/?probe=2d5f49bf19) | Nov 20, 2025 |
| Google        | Kefka                       | [18a8d258c8](https://linux-hardware.org/?probe=18a8d258c8) | Nov 19, 2025 |
| Dell          | Inspiron 15-3567            | [79b85f3ced](https://linux-hardware.org/?probe=79b85f3ced) | Nov 18, 2025 |
| Lenovo        | IdeaPad Y500 20193          | [ab107435ca](https://linux-hardware.org/?probe=ab107435ca) | Nov 18, 2025 |
| Apple         | MacBookPro11,2              | [097647805e](https://linux-hardware.org/?probe=097647805e) | Nov 17, 2025 |
| Dell          | Latitude E5470              | [8fd76cb9e2](https://linux-hardware.org/?probe=8fd76cb9e2) | Nov 17, 2025 |
| Dell          | Latitude E5470              | [1d15cc30a6](https://linux-hardware.org/?probe=1d15cc30a6) | Nov 17, 2025 |
| Chuwi         | CoreBook X                  | [e938f7de5a](https://linux-hardware.org/?probe=e938f7de5a) | Nov 16, 2025 |
| Apple         | MacBookPro8,1               | [d713ff600d](https://linux-hardware.org/?probe=d713ff600d) | Nov 15, 2025 |
| Timi          | TM1701                      | [bc38ca3830](https://linux-hardware.org/?probe=bc38ca3830) | Nov 15, 2025 |
| Lenovo        | ThinkPad T490 20N2004HAD    | [50eec0b73e](https://linux-hardware.org/?probe=50eec0b73e) | Nov 14, 2025 |
| HP            | Pavilion 14                 | [777782644a](https://linux-hardware.org/?probe=777782644a) | Nov 10, 2025 |
| Lenovo        | Yoga Pro 16 IAH10 83L0      | [a8872c086c](https://linux-hardware.org/?probe=a8872c086c) | Nov 09, 2025 |
| HP            | Pavilion 17                 | [97d0bd94a2](https://linux-hardware.org/?probe=97d0bd94a2) | Nov 08, 2025 |
| Dell          | Venue 11 Pro 7140           | [b7005bcb7d](https://linux-hardware.org/?probe=b7005bcb7d) | Nov 08, 2025 |
| HP            | Pavilion dv6                | [f031d90e6c](https://linux-hardware.org/?probe=f031d90e6c) | Nov 05, 2025 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [d53eb4c9f3](https://linux-hardware.org/?probe=d53eb4c9f3) | Nov 05, 2025 |
| Apple         | MacBookPro9,2               | [711674bf50](https://linux-hardware.org/?probe=711674bf50) | Nov 05, 2025 |
| Apple         | MacBookPro9,2               | [f454fbffa6](https://linux-hardware.org/?probe=f454fbffa6) | Nov 04, 2025 |
| HP            | Pavilion dv6                | [4fb3464b2f](https://linux-hardware.org/?probe=4fb3464b2f) | Nov 03, 2025 |
| Timi          | Mi NoteBook Ultra           | [73b9f7cc41](https://linux-hardware.org/?probe=73b9f7cc41) | Nov 02, 2025 |
| Dell          | Latitude 5320               | [8b12054048](https://linux-hardware.org/?probe=8b12054048) | Nov 02, 2025 |
| Thomson       | N14C4WH64                   | [1c383dd8ff](https://linux-hardware.org/?probe=1c383dd8ff) | Nov 02, 2025 |
| Apple         | MacBookPro8,1               | [232acaf17b](https://linux-hardware.org/?probe=232acaf17b) | Oct 31, 2025 |
| Apple         | MacBookPro8,1               | [cb1f3b706e](https://linux-hardware.org/?probe=cb1f3b706e) | Oct 30, 2025 |
| Apple         | MacBookPro8,1               | [9fdff90cbd](https://linux-hardware.org/?probe=9fdff90cbd) | Oct 30, 2025 |
| NEC Comput... | PC-VK24LXZCE                | [423e99f492](https://linux-hardware.org/?probe=423e99f492) | Oct 30, 2025 |
| HP            | Pavilion dv7                | [d15a848934](https://linux-hardware.org/?probe=d15a848934) | Oct 29, 2025 |
| AiStone       | X4SP4NAL                    | [0ba7202723](https://linux-hardware.org/?probe=0ba7202723) | Oct 28, 2025 |
| Apple         | MacBook6,1                  | [5a53960e9a](https://linux-hardware.org/?probe=5a53960e9a) | Oct 28, 2025 |
| Toshiba       | PORTEGE Z20t-B              | [c89b53f809](https://linux-hardware.org/?probe=c89b53f809) | Oct 28, 2025 |
| Acer          | Aspire E5-571G              | [b1a8be9b38](https://linux-hardware.org/?probe=b1a8be9b38) | Oct 26, 2025 |
| HP            | Pavilion 14                 | [e9c2f6c104](https://linux-hardware.org/?probe=e9c2f6c104) | Oct 26, 2025 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [2089a12776](https://linux-hardware.org/?probe=2089a12776) | Oct 26, 2025 |
| Apple         | MacBook6,1                  | [dbc8f4f3ab](https://linux-hardware.org/?probe=dbc8f4f3ab) | Oct 23, 2025 |
| HP            | Pavilion 14                 | [17eefe70ce](https://linux-hardware.org/?probe=17eefe70ce) | Oct 21, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [4eeb3ec1c1](https://linux-hardware.org/?probe=4eeb3ec1c1) | Oct 20, 2025 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | [6ec3d409c6](https://linux-hardware.org/?probe=6ec3d409c6) | Oct 18, 2025 |
| ASUSTek       | ASUS EXPERTBOOK P5405CSA    | [9546ac0511](https://linux-hardware.org/?probe=9546ac0511) | Oct 15, 2025 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [ee2874cf10](https://linux-hardware.org/?probe=ee2874cf10) | Oct 15, 2025 |
| HP            | Pavilion dv6                | [66f3b1f2e0](https://linux-hardware.org/?probe=66f3b1f2e0) | Oct 14, 2025 |
| HP            | Pavilion g6                 | [57b550a6dc](https://linux-hardware.org/?probe=57b550a6dc) | Oct 10, 2025 |
| Dell          | Latitude E4310              | [99bd07799b](https://linux-hardware.org/?probe=99bd07799b) | Oct 10, 2025 |
| GPD           | P2 MAX                      | [8199ae0920](https://linux-hardware.org/?probe=8199ae0920) | Oct 10, 2025 |
| Apple         | MacBookPro10,1              | [e011121814](https://linux-hardware.org/?probe=e011121814) | Oct 07, 2025 |
| HP            | Laptop 15s-fq1xxx           | [a54f167e56](https://linux-hardware.org/?probe=a54f167e56) | Oct 06, 2025 |
| HP            | Laptop 15s-fq1xxx           | [11541f7d00](https://linux-hardware.org/?probe=11541f7d00) | Oct 06, 2025 |
| Dell          | Inspiron 7558               | [2e86658229](https://linux-hardware.org/?probe=2e86658229) | Oct 04, 2025 |
| Apple         | MacBook5,1                  | [28277351fb](https://linux-hardware.org/?probe=28277351fb) | Oct 04, 2025 |
| HP            | Pavilion dv7                | [d4a2d26dfe](https://linux-hardware.org/?probe=d4a2d26dfe) | Oct 04, 2025 |
| Dell          | Latitude E6420              | [5efb6c4bc2](https://linux-hardware.org/?probe=5efb6c4bc2) | Oct 04, 2025 |
| Sony          | SVF14415CLW                 | [b952b4f37a](https://linux-hardware.org/?probe=b952b4f37a) | Oct 03, 2025 |
| Alienware     | 15 R3                       | [1a9c18a905](https://linux-hardware.org/?probe=1a9c18a905) | Oct 02, 2025 |
| Apple         | MacBookAir4,1               | [8b9a9abff8](https://linux-hardware.org/?probe=8b9a9abff8) | Sep 30, 2025 |
| Unknown       | Unknown                     | [6177830fc2](https://linux-hardware.org/?probe=6177830fc2) | Sep 28, 2025 |
| Unknown       | Unknown                     | [5f042fc8a2](https://linux-hardware.org/?probe=5f042fc8a2) | Sep 28, 2025 |
| HP            | ZBook 15                    | [787e1db37e](https://linux-hardware.org/?probe=787e1db37e) | Sep 27, 2025 |
| Lenovo        | ThinkPad T430 2349G4G       | [97f9cad42a](https://linux-hardware.org/?probe=97f9cad42a) | Sep 27, 2025 |
| Apple         | MacBook5,1                  | [2ae8722b75](https://linux-hardware.org/?probe=2ae8722b75) | Sep 26, 2025 |
| Apple         | MacBook5,1                  | [b45d8858f1](https://linux-hardware.org/?probe=b45d8858f1) | Sep 26, 2025 |
| Proline       | V1165C4                     | [4a0d7d946a](https://linux-hardware.org/?probe=4a0d7d946a) | Sep 25, 2025 |
| Proline       | V1165C4                     | [cfc2c58da9](https://linux-hardware.org/?probe=cfc2c58da9) | Sep 25, 2025 |
| HP            | ProBook 450 G6              | [aed4d96c7f](https://linux-hardware.org/?probe=aed4d96c7f) | Sep 25, 2025 |
| HP            | ProBook 450 G6              | [8b7bff69be](https://linux-hardware.org/?probe=8b7bff69be) | Sep 25, 2025 |
| eMachines     | G730                        | [a2ef1e57ba](https://linux-hardware.org/?probe=a2ef1e57ba) | Sep 24, 2025 |
| AZW           | GT-R                        | [e44ff94248](https://linux-hardware.org/?probe=e44ff94248) | Sep 23, 2025 |
| Pegatron      | A15                         | [68690e3c1c](https://linux-hardware.org/?probe=68690e3c1c) | Sep 22, 2025 |
| Acer          | Aspire E1-571G              | [59066ba058](https://linux-hardware.org/?probe=59066ba058) | Sep 21, 2025 |
| Acer          | Aspire E1-571G              | [6d1ba185b3](https://linux-hardware.org/?probe=6d1ba185b3) | Sep 21, 2025 |
| Lenovo        | Legion y540 15IRH 81SX      | [25fff34c25](https://linux-hardware.org/?probe=25fff34c25) | Sep 21, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | [8818091701](https://linux-hardware.org/?probe=8818091701) | Sep 15, 2025 |
| Lenovo        | B590 20208                  | [8d909bb349](https://linux-hardware.org/?probe=8d909bb349) | Sep 12, 2025 |
| Apple         | MacBookAir5,2               | [16f403a6e1](https://linux-hardware.org/?probe=16f403a6e1) | Sep 12, 2025 |
| Positivo      | N4340                       | [fa5b180e90](https://linux-hardware.org/?probe=fa5b180e90) | Sep 10, 2025 |
| Positivo      | N4340                       | [09080bb232](https://linux-hardware.org/?probe=09080bb232) | Sep 10, 2025 |
| Apple         | MacBookPro11,2              | [d18d63f46a](https://linux-hardware.org/?probe=d18d63f46a) | Sep 08, 2025 |
| Apple         | MacBookPro12,1              | [e3d8342efd](https://linux-hardware.org/?probe=e3d8342efd) | Sep 07, 2025 |
| Apple         | MacBookPro11,2              | [e67eeef57c](https://linux-hardware.org/?probe=e67eeef57c) | Sep 03, 2025 |
| Acer          | Aspire 4739                 | [2144d6fb23](https://linux-hardware.org/?probe=2144d6fb23) | Sep 03, 2025 |
| Dell          | Latitude E5420              | [622d7ea264](https://linux-hardware.org/?probe=622d7ea264) | Sep 02, 2025 |
| Star Labs     | StarBook                    | [ce9448d5e8](https://linux-hardware.org/?probe=ce9448d5e8) | Aug 31, 2025 |
| Acer          | Aspire 7540                 | [d622492cf3](https://linux-hardware.org/?probe=d622492cf3) | Aug 30, 2025 |
| Pegatron      | A15                         | [ee67a9066e](https://linux-hardware.org/?probe=ee67a9066e) | Aug 30, 2025 |
| Dell          | Inspiron N5110              | [f21399e094](https://linux-hardware.org/?probe=f21399e094) | Aug 26, 2025 |
| HP            | Laptop 15-dy2xxx            | [c88d8b09bf](https://linux-hardware.org/?probe=c88d8b09bf) | Aug 24, 2025 |
| Lenovo        | ThinkPad T530 23595JU       | [9d62dd71ce](https://linux-hardware.org/?probe=9d62dd71ce) | Aug 23, 2025 |
| Lenovo        | ThinkPad T530 23595JU       | [d1a6eb1eb1](https://linux-hardware.org/?probe=d1a6eb1eb1) | Aug 23, 2025 |
| Apple         | MacBookPro8,1               | [d932ad5888](https://linux-hardware.org/?probe=d932ad5888) | Aug 20, 2025 |
| Dell          | Vostro 1015                 | [768a7d4849](https://linux-hardware.org/?probe=768a7d4849) | Aug 18, 2025 |
| Toshiba       | Satellite U840              | [5d9ded6b5e](https://linux-hardware.org/?probe=5d9ded6b5e) | Aug 15, 2025 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [f22865b542](https://linux-hardware.org/?probe=f22865b542) | Aug 13, 2025 |
| Dell          | Latitude E7470              | [0ca5330918](https://linux-hardware.org/?probe=0ca5330918) | Aug 11, 2025 |
| ASUSTek       | X406UAR                     | [b817bc940d](https://linux-hardware.org/?probe=b817bc940d) | Aug 11, 2025 |
| HP            | Laptop 15s-eq0xxx           | [fb1d1e0705](https://linux-hardware.org/?probe=fb1d1e0705) | Aug 11, 2025 |
| Dell          | Latitude E6320              | [724cbbacb6](https://linux-hardware.org/?probe=724cbbacb6) | Aug 10, 2025 |
| Acer          | Aspire A515-45              | [ae5ea08bd6](https://linux-hardware.org/?probe=ae5ea08bd6) | Aug 05, 2025 |
| Apple         | MacBookAir7,2               | [4009991bb8](https://linux-hardware.org/?probe=4009991bb8) | Aug 05, 2025 |
| Apple         | MacBookAir7,2               | [aeff5dd520](https://linux-hardware.org/?probe=aeff5dd520) | Aug 05, 2025 |
| Apple         | MacBookPro11,5              | [16ad2ffc69](https://linux-hardware.org/?probe=16ad2ffc69) | Aug 04, 2025 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [87d2be3cec](https://linux-hardware.org/?probe=87d2be3cec) | Aug 02, 2025 |
| HP            | Notebook                    | [2860a347b6](https://linux-hardware.org/?probe=2860a347b6) | Aug 01, 2025 |
| HP            | Notebook                    | [bd44fff337](https://linux-hardware.org/?probe=bd44fff337) | Aug 01, 2025 |
| Apple         | MacBookPro11,5              | [45e006e8f0](https://linux-hardware.org/?probe=45e006e8f0) | Aug 01, 2025 |
| Apple         | MacBookAir7,2               | [2b0e8cc054](https://linux-hardware.org/?probe=2b0e8cc054) | Aug 01, 2025 |
| ASUSTek       | K93SV                       | [972fc344be](https://linux-hardware.org/?probe=972fc344be) | Jul 31, 2025 |
| Apple         | MacBookAir7,2               | [85f6fbba81](https://linux-hardware.org/?probe=85f6fbba81) | Jul 31, 2025 |
| Notebook      | W35xSS_370SS                | [aad43c31b1](https://linux-hardware.org/?probe=aad43c31b1) | Jul 31, 2025 |
| Dell          | XPS L412Z                   | [f7afa8d724](https://linux-hardware.org/?probe=f7afa8d724) | Jul 27, 2025 |
| ASUSTek       | X555LA                      | [1eec7134a2](https://linux-hardware.org/?probe=1eec7134a2) | Jul 24, 2025 |
| Lenovo        | V330-14IGM 81B3             | [1f8b2fa7d1](https://linux-hardware.org/?probe=1f8b2fa7d1) | Jul 23, 2025 |
| Google        | Joxer                       | [bc774d1258](https://linux-hardware.org/?probe=bc774d1258) | Jul 23, 2025 |
| Dell          | Inspiron 5520               | [53d6949846](https://linux-hardware.org/?probe=53d6949846) | Jul 22, 2025 |
| Medion        | S5610                       | [82d257e335](https://linux-hardware.org/?probe=82d257e335) | Jul 21, 2025 |
| Apple         | MacBookPro11,1              | [42ab6e3bd2](https://linux-hardware.org/?probe=42ab6e3bd2) | Jul 20, 2025 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [57d34f4fce](https://linux-hardware.org/?probe=57d34f4fce) | Jul 20, 2025 |
| Sony          | SVE14A27CLS                 | [2b6cf71203](https://linux-hardware.org/?probe=2b6cf71203) | Jul 18, 2025 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [8b1d790084](https://linux-hardware.org/?probe=8b1d790084) | Jul 17, 2025 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [2f713fce4d](https://linux-hardware.org/?probe=2f713fce4d) | Jul 16, 2025 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [44bb83c372](https://linux-hardware.org/?probe=44bb83c372) | Jul 16, 2025 |
| HP            | EliteBook 8470p             | [543bb5c5ee](https://linux-hardware.org/?probe=543bb5c5ee) | Jul 16, 2025 |
| HP            | EliteBook 8470p             | [ceb27b6e9a](https://linux-hardware.org/?probe=ceb27b6e9a) | Jul 16, 2025 |
| Apple         | MacBookPro9,2               | [2dd8366e0b](https://linux-hardware.org/?probe=2dd8366e0b) | Jul 15, 2025 |
| HP            | Pavilion dv6                | [13a04e6371](https://linux-hardware.org/?probe=13a04e6371) | Jul 15, 2025 |
| HP            | Pavilion dv7                | [7e04c5ff73](https://linux-hardware.org/?probe=7e04c5ff73) | Jul 14, 2025 |
| Lenovo        | G505 20240                  | [db89bc9e33](https://linux-hardware.org/?probe=db89bc9e33) | Jul 12, 2025 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [7bc74950ff](https://linux-hardware.org/?probe=7bc74950ff) | Jul 10, 2025 |
| ASUSTek       | X450EA                      | [1ec63ddd6b](https://linux-hardware.org/?probe=1ec63ddd6b) | Jul 10, 2025 |
| Apple         | MacBookPro7,1               | [a90c9e156d](https://linux-hardware.org/?probe=a90c9e156d) | Jul 09, 2025 |
| Apple         | MacBookPro11,1              | [2da9644a1f](https://linux-hardware.org/?probe=2da9644a1f) | Jul 05, 2025 |
| Apple         | MacBookPro11,1              | [2952563cb5](https://linux-hardware.org/?probe=2952563cb5) | Jul 05, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [1e777ac3b2](https://linux-hardware.org/?probe=1e777ac3b2) | Jul 05, 2025 |
| TUXEDO        | N85_N87HCHNHZ               | [944efa8a15](https://linux-hardware.org/?probe=944efa8a15) | Jul 03, 2025 |
| ASUSTek       | K55A                        | [f540fa0209](https://linux-hardware.org/?probe=f540fa0209) | Jul 01, 2025 |
| HP            | EliteBook 8770w             | [32840687a2](https://linux-hardware.org/?probe=32840687a2) | Jul 01, 2025 |
| Apple         | MacBook8,1                  | [1a8a0dadc4](https://linux-hardware.org/?probe=1a8a0dadc4) | Jul 01, 2025 |
| Google        | Frostflow                   | [f960b3c8fc](https://linux-hardware.org/?probe=f960b3c8fc) | Jun 29, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [89fce5afd8](https://linux-hardware.org/?probe=89fce5afd8) | Jun 28, 2025 |
| Acer          | Aspire A315-24PT            | [96ed77cc5b](https://linux-hardware.org/?probe=96ed77cc5b) | Jun 26, 2025 |
| Acer          | Aspire A315-24PT            | [3b65852f6c](https://linux-hardware.org/?probe=3b65852f6c) | Jun 26, 2025 |
| HP            | 255 15.6 inch G10 Notebo... | [c1d5a9441e](https://linux-hardware.org/?probe=c1d5a9441e) | Jun 26, 2025 |
| Apple         | MacBookAir7,2               | [631e136e6b](https://linux-hardware.org/?probe=631e136e6b) | Jun 25, 2025 |
| Apple         | MacBook5,1                  | [3b40a9285e](https://linux-hardware.org/?probe=3b40a9285e) | Jun 24, 2025 |
| HP            | Notebook                    | [9b254818da](https://linux-hardware.org/?probe=9b254818da) | Jun 23, 2025 |
| Apple         | MacBookPro11,3              | [ac2010480b](https://linux-hardware.org/?probe=ac2010480b) | Jun 23, 2025 |
| Apple         | MacBookAir6,2               | [d285c790b0](https://linux-hardware.org/?probe=d285c790b0) | Jun 23, 2025 |
| HP            | 255 15.6 inch G10 Notebo... | [985bc51e87](https://linux-hardware.org/?probe=985bc51e87) | Jun 22, 2025 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [f3ca605115](https://linux-hardware.org/?probe=f3ca605115) | Jun 20, 2025 |
| Sony          | SVE15133CNW                 | [82e61cb2c7](https://linux-hardware.org/?probe=82e61cb2c7) | Jun 18, 2025 |
| HP            | 14                          | [652477232e](https://linux-hardware.org/?probe=652477232e) | Jun 17, 2025 |
| HP            | 635                         | [479d8459c0](https://linux-hardware.org/?probe=479d8459c0) | Jun 17, 2025 |
| HP            | ProBook 440 G4              | [64ab630b9c](https://linux-hardware.org/?probe=64ab630b9c) | Jun 15, 2025 |
| Apple         | MacBookPro9,1               | [77b85c37ed](https://linux-hardware.org/?probe=77b85c37ed) | Jun 15, 2025 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [38351db67b](https://linux-hardware.org/?probe=38351db67b) | Jun 14, 2025 |
| Apple         | MacBookPro11,1              | [96435d53d9](https://linux-hardware.org/?probe=96435d53d9) | Jun 14, 2025 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [ff8ea04712](https://linux-hardware.org/?probe=ff8ea04712) | Jun 13, 2025 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d2724d6f18](https://linux-hardware.org/?probe=d2724d6f18) | Jun 12, 2025 |
| Apple         | MacBook5,1                  | [f3336d6280](https://linux-hardware.org/?probe=f3336d6280) | Jun 09, 2025 |
| Sony          | VPCCB2S1E                   | [2bded87a77](https://linux-hardware.org/?probe=2bded87a77) | Jun 09, 2025 |
| Sony          | VPCCB2S1E                   | [d71077fe64](https://linux-hardware.org/?probe=d71077fe64) | Jun 09, 2025 |
| Apple         | MacBookAir7,2               | [9e33c3ae46](https://linux-hardware.org/?probe=9e33c3ae46) | Jun 08, 2025 |
| Toshiba       | Satellite C660              | [909792452b](https://linux-hardware.org/?probe=909792452b) | Jun 07, 2025 |
| Apple         | MacBookAir5,2               | [2c06794b01](https://linux-hardware.org/?probe=2c06794b01) | Jun 05, 2025 |
| Alienware     | M11x                        | [28e13fa7d6](https://linux-hardware.org/?probe=28e13fa7d6) | Jun 04, 2025 |
| HP            | Unknown                     | [c6f2e73a9e](https://linux-hardware.org/?probe=c6f2e73a9e) | Jun 03, 2025 |
| Apple         | MacBookAir6,2               | [6db04e9ade](https://linux-hardware.org/?probe=6db04e9ade) | Jun 02, 2025 |
| Dell          | Vostro 3300                 | [e24f84ce5c](https://linux-hardware.org/?probe=e24f84ce5c) | Jun 01, 2025 |
| Toshiba       | Satellite L50-B             | [65d84e16b9](https://linux-hardware.org/?probe=65d84e16b9) | May 31, 2025 |
| Toshiba       | Satellite L50-B             | [22f45326e2](https://linux-hardware.org/?probe=22f45326e2) | May 31, 2025 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [205c33e738](https://linux-hardware.org/?probe=205c33e738) | May 30, 2025 |
| MSI           | Modern 14 C7M               | [d0a3efc2a4](https://linux-hardware.org/?probe=d0a3efc2a4) | May 30, 2025 |
| Positivo      | Mobile                      | [a6cde8e043](https://linux-hardware.org/?probe=a6cde8e043) | May 30, 2025 |
| HP            | Laptop 17-cp2xxx            | [73c78eed44](https://linux-hardware.org/?probe=73c78eed44) | May 29, 2025 |
| Apple         | MacBookPro10,1              | [643474230c](https://linux-hardware.org/?probe=643474230c) | May 29, 2025 |
| Apple         | MacBookPro10,1              | [a132a12adb](https://linux-hardware.org/?probe=a132a12adb) | May 28, 2025 |
| HP            | Pavilion Laptop 15-cw1xx... | [7f1edd5b3f](https://linux-hardware.org/?probe=7f1edd5b3f) | May 27, 2025 |
| Dell          | Latitude E6420              | [42d5692ec5](https://linux-hardware.org/?probe=42d5692ec5) | May 26, 2025 |
| HONOR         | BMH-WDX9                    | [3b0953da0c](https://linux-hardware.org/?probe=3b0953da0c) | May 21, 2025 |
| HONOR         | BMH-WDX9                    | [21b8d516ed](https://linux-hardware.org/?probe=21b8d516ed) | May 21, 2025 |
| Dell          | Latitude E5570              | [4644f38290](https://linux-hardware.org/?probe=4644f38290) | May 19, 2025 |
| HP            | ProBook 650 G3              | [063bdc9c85](https://linux-hardware.org/?probe=063bdc9c85) | May 16, 2025 |
| HP            | 240 G4 Notebook PC          | [8b2fecec4b](https://linux-hardware.org/?probe=8b2fecec4b) | May 16, 2025 |
| HP            | Pavilion dm4                | [00223b4a35](https://linux-hardware.org/?probe=00223b4a35) | May 15, 2025 |
| HP            | ProBook 430 G5              | [9c40451ead](https://linux-hardware.org/?probe=9c40451ead) | May 14, 2025 |
| Apple         | MacBookPro5,5               | [2b7f0d49ad](https://linux-hardware.org/?probe=2b7f0d49ad) | May 13, 2025 |
| Acer          | Aspire ES1-521              | [51356a260c](https://linux-hardware.org/?probe=51356a260c) | May 13, 2025 |
| Acer          | Aspire ES1-521              | [82ce3477e5](https://linux-hardware.org/?probe=82ce3477e5) | May 13, 2025 |
| Apple         | MacBookPro9,2               | [aa8390baa6](https://linux-hardware.org/?probe=aa8390baa6) | May 13, 2025 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | [f117b0e455](https://linux-hardware.org/?probe=f117b0e455) | May 12, 2025 |
| Dell          | Latitude E6520              | [baa6186588](https://linux-hardware.org/?probe=baa6186588) | May 12, 2025 |
| HP            | EliteBook 2570p             | [3102539d4d](https://linux-hardware.org/?probe=3102539d4d) | May 07, 2025 |
| Lenovo        | ThinkPad Edge E130 3358A... | [2987fa1bca](https://linux-hardware.org/?probe=2987fa1bca) | May 07, 2025 |
| Lenovo        | ThinkPad Edge E130 3358A... | [664601b72c](https://linux-hardware.org/?probe=664601b72c) | May 07, 2025 |
| Acer          | Swift SF713-51              | [e37cd51aa0](https://linux-hardware.org/?probe=e37cd51aa0) | May 06, 2025 |
| Apple         | MacBookPro9,2               | [43142d40aa](https://linux-hardware.org/?probe=43142d40aa) | May 05, 2025 |
| Sony          | VPCCW1S1E                   | [6766f4cf01](https://linux-hardware.org/?probe=6766f4cf01) | May 05, 2025 |
| HP            | ENVY 17                     | [817cef050a](https://linux-hardware.org/?probe=817cef050a) | May 04, 2025 |
| TongFang      | Standard                    | [5d358787ca](https://linux-hardware.org/?probe=5d358787ca) | May 04, 2025 |
| TongFang      | Standard                    | [06e06c45c0](https://linux-hardware.org/?probe=06e06c45c0) | May 04, 2025 |
| Unknown       | K16                         | [668e7a80bf](https://linux-hardware.org/?probe=668e7a80bf) | May 03, 2025 |
| Fujitsu       | LIFEBOOK U772               | [5d1ae06d47](https://linux-hardware.org/?probe=5d1ae06d47) | May 02, 2025 |
| Fujitsu       | LIFEBOOK U772               | [6ca8928193](https://linux-hardware.org/?probe=6ca8928193) | May 02, 2025 |
| HP            | EliteBook 2570p             | [eaeaf4f57d](https://linux-hardware.org/?probe=eaeaf4f57d) | May 02, 2025 |
| Samsung       | SBB-DA                      | [227f005e60](https://linux-hardware.org/?probe=227f005e60) | May 01, 2025 |
| Samsung       | SBB-DA                      | [0f6e59728c](https://linux-hardware.org/?probe=0f6e59728c) | Apr 30, 2025 |
| Dell          | Latitude E5570              | [53866531f2](https://linux-hardware.org/?probe=53866531f2) | Apr 28, 2025 |
| Acer          | Aspire A315-41G             | [c398a7ed29](https://linux-hardware.org/?probe=c398a7ed29) | Apr 27, 2025 |
| Acer          | Aspire V3-571               | [3d4aef7438](https://linux-hardware.org/?probe=3d4aef7438) | Apr 26, 2025 |
| Sony          | SVJ20236CXW                 | [ecbc00414b](https://linux-hardware.org/?probe=ecbc00414b) | Apr 26, 2025 |
| HP            | Laptop 15-fd0xxx            | [9093a619c7](https://linux-hardware.org/?probe=9093a619c7) | Apr 25, 2025 |
| Samsung       | 750XDA                      | [daa961232a](https://linux-hardware.org/?probe=daa961232a) | Apr 24, 2025 |
| Samsung       | 750XDA                      | [3f300c8d3d](https://linux-hardware.org/?probe=3f300c8d3d) | Apr 24, 2025 |
| HP            | Pavilion Laptop 15-eg0xx... | [c8ee1f92ba](https://linux-hardware.org/?probe=c8ee1f92ba) | Apr 23, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [ffe6a7e1d6](https://linux-hardware.org/?probe=ffe6a7e1d6) | Apr 22, 2025 |
| Sony          | SVJ20236CXW                 | [420898862c](https://linux-hardware.org/?probe=420898862c) | Apr 21, 2025 |
| Lenovo        | G70-70 80HW                 | [59676e322d](https://linux-hardware.org/?probe=59676e322d) | Apr 21, 2025 |
| Clevo         | M860TU                      | [19839c5808](https://linux-hardware.org/?probe=19839c5808) | Apr 20, 2025 |
| Dell          | Inspiron 1525               | [c02590fff8](https://linux-hardware.org/?probe=c02590fff8) | Apr 19, 2025 |
| Dell          | Latitude E7470              | [5d70f86783](https://linux-hardware.org/?probe=5d70f86783) | Apr 18, 2025 |
| Dell          | Latitude E7470              | [1c6dcea31c](https://linux-hardware.org/?probe=1c6dcea31c) | Apr 18, 2025 |
| Dell          | Inspiron 1525               | [f5e08a7a78](https://linux-hardware.org/?probe=f5e08a7a78) | Apr 16, 2025 |
| Dell          | Inspiron 15 3515            | [142f88c0e7](https://linux-hardware.org/?probe=142f88c0e7) | Apr 15, 2025 |
| HP            | Laptop 15-fc0xxx            | [edb5e85937](https://linux-hardware.org/?probe=edb5e85937) | Apr 13, 2025 |
| Dell          | Latitude E6500              | [756c367ddc](https://linux-hardware.org/?probe=756c367ddc) | Apr 13, 2025 |
| HUAWEI        | MRC-WX0                     | [4007d809cb](https://linux-hardware.org/?probe=4007d809cb) | Apr 07, 2025 |
| Apple         | MacBookPro6,2               | [feb743c270](https://linux-hardware.org/?probe=feb743c270) | Apr 06, 2025 |
| Kanji         | KJ-NTB1001                  | [04da5ff6d2](https://linux-hardware.org/?probe=04da5ff6d2) | Apr 06, 2025 |
| Dell          | Latitude E5550              | [2f0c001219](https://linux-hardware.org/?probe=2f0c001219) | Apr 05, 2025 |
| Samsung       | 750XGK                      | [92f6215d81](https://linux-hardware.org/?probe=92f6215d81) | Apr 04, 2025 |
| Dell          | Vostro 5581                 | [f218978bf3](https://linux-hardware.org/?probe=f218978bf3) | Apr 04, 2025 |
| Lenovo        | ThinkPad SL510 2847CZU      | [a6daef060e](https://linux-hardware.org/?probe=a6daef060e) | Apr 03, 2025 |
| HP            | Presario CQ42               | [6c3e4078ad](https://linux-hardware.org/?probe=6c3e4078ad) | Apr 03, 2025 |
| Lenovo        | G50-70 20351                | [416ae54e4f](https://linux-hardware.org/?probe=416ae54e4f) | Apr 02, 2025 |
| Lenovo        | G50-70 20351                | [e78beaea72](https://linux-hardware.org/?probe=e78beaea72) | Mar 31, 2025 |
| Sony          | SVS151190X                  | [7ffeb7fab1](https://linux-hardware.org/?probe=7ffeb7fab1) | Mar 30, 2025 |
| Fujitsu       | LIFEBOOK U728               | [bf5f9d0bd7](https://linux-hardware.org/?probe=bf5f9d0bd7) | Mar 29, 2025 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [2fa9f94e9e](https://linux-hardware.org/?probe=2fa9f94e9e) | Mar 29, 2025 |
| Toshiba       | Satellite L15W-B            | [2cbc15f4f1](https://linux-hardware.org/?probe=2cbc15f4f1) | Mar 28, 2025 |
| Dell          | XPS L701X                   | [8fc24251a6](https://linux-hardware.org/?probe=8fc24251a6) | Mar 26, 2025 |
| HP            | G62                         | [3657b456c2](https://linux-hardware.org/?probe=3657b456c2) | Mar 25, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e02ff3872b](https://linux-hardware.org/?probe=e02ff3872b) | Mar 24, 2025 |
| ASUSTek       | TP300LA                     | [116335b0c6](https://linux-hardware.org/?probe=116335b0c6) | Mar 24, 2025 |
| HP            | EliteBook 8440p             | [cd1f9ebd2d](https://linux-hardware.org/?probe=cd1f9ebd2d) | Mar 23, 2025 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [6b1af2a5b7](https://linux-hardware.org/?probe=6b1af2a5b7) | Mar 22, 2025 |
| Acer          | Aspire E5-571G              | [c5b57bccce](https://linux-hardware.org/?probe=c5b57bccce) | Mar 21, 2025 |
| Acer          | Aspire E5-571G              | [463ced67dd](https://linux-hardware.org/?probe=463ced67dd) | Mar 21, 2025 |
| HP            | Compaq 6730b (KE717AV)      | [4d05160c8f](https://linux-hardware.org/?probe=4d05160c8f) | Mar 21, 2025 |
| Acer          | Aspire E1-531               | [d7352bf64a](https://linux-hardware.org/?probe=d7352bf64a) | Mar 21, 2025 |
| ASUSTek       | K93SV                       | [73a0b56351](https://linux-hardware.org/?probe=73a0b56351) | Mar 19, 2025 |
| Lenovo        | G50-80 80L0                 | [0f2e61271e](https://linux-hardware.org/?probe=0f2e61271e) | Mar 19, 2025 |
| HP            | Laptop 15-dw3xxx            | [d3f5528817](https://linux-hardware.org/?probe=d3f5528817) | Mar 17, 2025 |
| Dell          | Latitude 7490               | [fd9f8b4136](https://linux-hardware.org/?probe=fd9f8b4136) | Mar 16, 2025 |
| Lenovo        | Z50-70 20354                | [097d7e970a](https://linux-hardware.org/?probe=097d7e970a) | Mar 14, 2025 |
| Lenovo        | G50-80 80L0                 | [b9326709c0](https://linux-hardware.org/?probe=b9326709c0) | Mar 13, 2025 |
| Infinix       | INBOOK X2 SLIM              | [4cdf6fc06b](https://linux-hardware.org/?probe=4cdf6fc06b) | Mar 12, 2025 |
| Toshiba       | Satellite L50D-B            | [ddd4722bd9](https://linux-hardware.org/?probe=ddd4722bd9) | Mar 12, 2025 |
| HP            | ProBook 640 G8 Notebook ... | [6d76c73345](https://linux-hardware.org/?probe=6d76c73345) | Mar 10, 2025 |
| Apple         | MacBookAir4,2               | [d016461357](https://linux-hardware.org/?probe=d016461357) | Mar 10, 2025 |
| Google        | Morphius                    | [4583655d0a](https://linux-hardware.org/?probe=4583655d0a) | Mar 10, 2025 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [388597b49e](https://linux-hardware.org/?probe=388597b49e) | Mar 09, 2025 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [dd1188499d](https://linux-hardware.org/?probe=dd1188499d) | Mar 09, 2025 |
| MSI           | PS42 8RB                    | [78230fb07b](https://linux-hardware.org/?probe=78230fb07b) | Mar 09, 2025 |
| ACCENT        | SMART 140                   | [dc5161eba0](https://linux-hardware.org/?probe=dc5161eba0) | Mar 09, 2025 |
| HP            | Pavilion g7                 | [832283d8a1](https://linux-hardware.org/?probe=832283d8a1) | Mar 08, 2025 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [64a94d8784](https://linux-hardware.org/?probe=64a94d8784) | Mar 08, 2025 |
| HP            | Laptop 14-cf1xxx            | [6dbdba4503](https://linux-hardware.org/?probe=6dbdba4503) | Mar 08, 2025 |
| HP            | OMEN by Laptop              | [62ec362c9e](https://linux-hardware.org/?probe=62ec362c9e) | Mar 07, 2025 |
| HP            | OMEN by Laptop              | [88e4bd362c](https://linux-hardware.org/?probe=88e4bd362c) | Mar 07, 2025 |
| Acer          | Aspire A515-46              | [70b67664c7](https://linux-hardware.org/?probe=70b67664c7) | Mar 06, 2025 |
| ASUSTek       | X751LD                      | [18516d05b3](https://linux-hardware.org/?probe=18516d05b3) | Mar 06, 2025 |
| Dell          | Precision M4800             | [77bd8a8709](https://linux-hardware.org/?probe=77bd8a8709) | Mar 05, 2025 |
| Samsung       | RV410/RV510/S3510/E3510     | [247af323ec](https://linux-hardware.org/?probe=247af323ec) | Mar 04, 2025 |
| ASUSTek       | TP300LA                     | [bd5141417a](https://linux-hardware.org/?probe=bd5141417a) | Mar 03, 2025 |
| ASUSTek       | TP300LA                     | [d34ec4e1c9](https://linux-hardware.org/?probe=d34ec4e1c9) | Mar 01, 2025 |
| HUAWEI        | MACHD-WXX9                  | [53e7ec6bd5](https://linux-hardware.org/?probe=53e7ec6bd5) | Mar 01, 2025 |
| Apple         | MacBookPro8,1               | [84b16f9e0b](https://linux-hardware.org/?probe=84b16f9e0b) | Feb 28, 2025 |
| HP            | Laptop 14-cf1xxx            | [d188eaf072](https://linux-hardware.org/?probe=d188eaf072) | Feb 28, 2025 |
| Apple         | MacBookAir6,2               | [d59756e98b](https://linux-hardware.org/?probe=d59756e98b) | Feb 28, 2025 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | [f855a3facf](https://linux-hardware.org/?probe=f855a3facf) | Feb 27, 2025 |
| Lenovo        | G50-80 80L0                 | [0381a48ff6](https://linux-hardware.org/?probe=0381a48ff6) | Feb 27, 2025 |
| Dell          | Precision 5530              | [40c558699b](https://linux-hardware.org/?probe=40c558699b) | Feb 26, 2025 |
| Dell          | Precision 5530              | [eb8a047c35](https://linux-hardware.org/?probe=eb8a047c35) | Feb 26, 2025 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [f6cd9296cf](https://linux-hardware.org/?probe=f6cd9296cf) | Feb 25, 2025 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [a934b12213](https://linux-hardware.org/?probe=a934b12213) | Feb 25, 2025 |
| Lenovo        | G560 20042                  | [c4003cae51](https://linux-hardware.org/?probe=c4003cae51) | Feb 24, 2025 |
| Lenovo        | G560 20042                  | [728057bf55](https://linux-hardware.org/?probe=728057bf55) | Feb 24, 2025 |
| HP            | Laptop 14-ck0xxx            | [5fab8982a9](https://linux-hardware.org/?probe=5fab8982a9) | Feb 21, 2025 |
| ASUSTek       | X201EP                      | [ef79469334](https://linux-hardware.org/?probe=ef79469334) | Feb 21, 2025 |
| Acer          | TravelMate B113             | [c39a4b0239](https://linux-hardware.org/?probe=c39a4b0239) | Feb 20, 2025 |
| HP            | Laptop 17-by3xxx            | [98f0606758](https://linux-hardware.org/?probe=98f0606758) | Feb 19, 2025 |
| Acer          | TravelMate B113             | [449d7ffd1c](https://linux-hardware.org/?probe=449d7ffd1c) | Feb 19, 2025 |
| Lenovo        | ThinkPad T570 W10DG 20JW... | [bb3561f31c](https://linux-hardware.org/?probe=bb3561f31c) | Feb 18, 2025 |
| Lenovo        | ThinkPad T570 W10DG 20JW... | [5120c6795a](https://linux-hardware.org/?probe=5120c6795a) | Feb 18, 2025 |
| Lenovo        | ThinkPad T530 23595JU       | [6aa540def5](https://linux-hardware.org/?probe=6aa540def5) | Feb 17, 2025 |
| HP            | Pavilion dv7                | [527154a620](https://linux-hardware.org/?probe=527154a620) | Feb 14, 2025 |
| Acer          | Swift SF114-34              | [1a20c83b5f](https://linux-hardware.org/?probe=1a20c83b5f) | Feb 14, 2025 |
| MSI           | GL65 Leopard 10SCXK         | [eceec59e78](https://linux-hardware.org/?probe=eceec59e78) | Feb 13, 2025 |
| ASUSTek       | X751LD                      | [02b451f50a](https://linux-hardware.org/?probe=02b451f50a) | Feb 13, 2025 |
| Sony          | SVF1521A1EW                 | [b31f8e7865](https://linux-hardware.org/?probe=b31f8e7865) | Feb 13, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [018d6a2976](https://linux-hardware.org/?probe=018d6a2976) | Feb 11, 2025 |
| Lenovo        | ThinkPad A475 20KMS05X1A    | [de9c7d0e0d](https://linux-hardware.org/?probe=de9c7d0e0d) | Feb 09, 2025 |
| Apple         | MacBookPro10,2              | [cac68d80c4](https://linux-hardware.org/?probe=cac68d80c4) | Feb 08, 2025 |
| HP            | Compaq 6735b                | [18b728a0f3](https://linux-hardware.org/?probe=18b728a0f3) | Feb 05, 2025 |
| HUAWEI        | MACHD-WXX9                  | [1ad66896cc](https://linux-hardware.org/?probe=1ad66896cc) | Feb 02, 2025 |
| HP            | ZBook 15                    | [e7809c4c4d](https://linux-hardware.org/?probe=e7809c4c4d) | Feb 01, 2025 |
| Apple         | MacBookPro8,3               | [cb543048e9](https://linux-hardware.org/?probe=cb543048e9) | Feb 01, 2025 |
| Alienware     | 15 R3                       | [b4c03288d7](https://linux-hardware.org/?probe=b4c03288d7) | Jan 31, 2025 |
| Thomson       | N17V3C8WH512                | [12cead9c03](https://linux-hardware.org/?probe=12cead9c03) | Jan 29, 2025 |
| Apple         | MacBookPro9,2               | [a35023f16c](https://linux-hardware.org/?probe=a35023f16c) | Jan 29, 2025 |
| Dell          | System Vostro 3750          | [d51079ff85](https://linux-hardware.org/?probe=d51079ff85) | Jan 28, 2025 |
| Thomson       | N17V3C8WH512                | [7bf5e0c404](https://linux-hardware.org/?probe=7bf5e0c404) | Jan 27, 2025 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | [0079d4634b](https://linux-hardware.org/?probe=0079d4634b) | Jan 26, 2025 |
| Lenovo        | Z710 20250                  | [c5c8052d20](https://linux-hardware.org/?probe=c5c8052d20) | Jan 25, 2025 |
| Apple         | MacBookPro10,2              | [43ba3065b1](https://linux-hardware.org/?probe=43ba3065b1) | Jan 24, 2025 |
| Apple         | MacBookAir6,2               | [340a1c98c0](https://linux-hardware.org/?probe=340a1c98c0) | Jan 23, 2025 |
| Acer          | Aspire 5750ZG               | [b55d95dc40](https://linux-hardware.org/?probe=b55d95dc40) | Jan 23, 2025 |
| Acer          | Aspire 5750ZG               | [fa9b739c95](https://linux-hardware.org/?probe=fa9b739c95) | Jan 23, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [fde29a0789](https://linux-hardware.org/?probe=fde29a0789) | Jan 22, 2025 |
| HP            | ProBook 440 G1              | [f06739d6c0](https://linux-hardware.org/?probe=f06739d6c0) | Jan 21, 2025 |
| Apple         | MacBookPro9,2               | [add0826738](https://linux-hardware.org/?probe=add0826738) | Jan 21, 2025 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [4d186a07ef](https://linux-hardware.org/?probe=4d186a07ef) | Jan 20, 2025 |
| Toshiba       | Satellite Pro C50-A-1MX     | [5e87f5ed4b](https://linux-hardware.org/?probe=5e87f5ed4b) | Jan 20, 2025 |
| HP            | Laptop 17-by3xxx            | [93544fbfaa](https://linux-hardware.org/?probe=93544fbfaa) | Jan 18, 2025 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [71486dacb8](https://linux-hardware.org/?probe=71486dacb8) | Jan 18, 2025 |
| HP            | EliteBook 840 G2            | [fa0fd7dffc](https://linux-hardware.org/?probe=fa0fd7dffc) | Jan 17, 2025 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [fd586e36f3](https://linux-hardware.org/?probe=fd586e36f3) | Jan 15, 2025 |
| HP            | Notebook                    | [f011276919](https://linux-hardware.org/?probe=f011276919) | Jan 15, 2025 |
| Apple         | MacBookAir7,2               | [1c4187a80e](https://linux-hardware.org/?probe=1c4187a80e) | Jan 15, 2025 |
| Apple         | MacBookAir6,2               | [47815cfe5b](https://linux-hardware.org/?probe=47815cfe5b) | Jan 14, 2025 |
| Apple         | MacBookPro10,1              | [86cc3c8042](https://linux-hardware.org/?probe=86cc3c8042) | Jan 14, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [bc2fc5f436](https://linux-hardware.org/?probe=bc2fc5f436) | Jan 13, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3e5ea876fa](https://linux-hardware.org/?probe=3e5ea876fa) | Jan 13, 2025 |
| HP            | Notebook                    | [3b15487100](https://linux-hardware.org/?probe=3b15487100) | Jan 12, 2025 |
| Toshiba       | Satellite C50-B             | [6030ba6297](https://linux-hardware.org/?probe=6030ba6297) | Jan 12, 2025 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | [92181b0356](https://linux-hardware.org/?probe=92181b0356) | Jan 11, 2025 |
| Apple         | MacBookPro8,1               | [ec217c6326](https://linux-hardware.org/?probe=ec217c6326) | Jan 11, 2025 |
| Dell          | Latitude E7470              | [06c5f3289c](https://linux-hardware.org/?probe=06c5f3289c) | Jan 11, 2025 |
| HONOR         | NBR-WAX9                    | [243ef437b7](https://linux-hardware.org/?probe=243ef437b7) | Jan 10, 2025 |
| Toshiba       | Satellite C50-B             | [ecea6f880e](https://linux-hardware.org/?probe=ecea6f880e) | Jan 10, 2025 |
| Panasonic     | CF-31SFLEC1M                | [d3a94176d7](https://linux-hardware.org/?probe=d3a94176d7) | Jan 10, 2025 |
| Acer          | Nitro AN515-47              | [6382503044](https://linux-hardware.org/?probe=6382503044) | Jan 09, 2025 |
| Apple         | MacBookPro5,4               | [38c695b157](https://linux-hardware.org/?probe=38c695b157) | Jan 07, 2025 |
| Dell          | Latitude 5580               | [7bc4688d7d](https://linux-hardware.org/?probe=7bc4688d7d) | Jan 07, 2025 |
| HUAWEI        | MACHD-WXX9                  | [f10a2b06fd](https://linux-hardware.org/?probe=f10a2b06fd) | Jan 06, 2025 |
| Samsung       | 900X3C/900X4C/900X4D        | [cbe6ed9631](https://linux-hardware.org/?probe=cbe6ed9631) | Jan 05, 2025 |
| Dell          | Inspiron 1545               | [6d5ccbb5f9](https://linux-hardware.org/?probe=6d5ccbb5f9) | Jan 05, 2025 |
| Dell          | XPS L412Z                   | [d8b969a9e6](https://linux-hardware.org/?probe=d8b969a9e6) | Jan 05, 2025 |
| Dell          | XPS L412Z                   | [f4cfef6dcc](https://linux-hardware.org/?probe=f4cfef6dcc) | Jan 05, 2025 |
| Apple         | MacBook3,1                  | [be78213991](https://linux-hardware.org/?probe=be78213991) | Jan 05, 2025 |
| HUAWEI        | BoDE-WXX9                   | [d5f19c64ad](https://linux-hardware.org/?probe=d5f19c64ad) | Jan 04, 2025 |
| Apple         | MacBookPro7,1               | [7961299452](https://linux-hardware.org/?probe=7961299452) | Jan 04, 2025 |
| Dell          | Latitude E5430 non-vPro     | [bbf6d05761](https://linux-hardware.org/?probe=bbf6d05761) | Jan 03, 2025 |
| Apple         | MacBookPro8,1               | [c208215b7f](https://linux-hardware.org/?probe=c208215b7f) | Jan 03, 2025 |
| Dell          | Latitude E5430 non-vPro     | [7b1adcdde1](https://linux-hardware.org/?probe=7b1adcdde1) | Jan 03, 2025 |
| HUAWEI        | BoDE-WXX9                   | [cacf1ad26f](https://linux-hardware.org/?probe=cacf1ad26f) | Jan 02, 2025 |
| Lenovo        | G585 20137                  | [f7dac7bbad](https://linux-hardware.org/?probe=f7dac7bbad) | Jan 02, 2025 |
| Medion        | Akoya E6240T                | [dc4b306a46](https://linux-hardware.org/?probe=dc4b306a46) | Jan 02, 2025 |
| Dell          | Latitude 5400               | [7a418a2cca](https://linux-hardware.org/?probe=7a418a2cca) | Jan 01, 2025 |
| HUAWEI        | MACHD-WXX9                  | [f7cc7cc8d1](https://linux-hardware.org/?probe=f7cc7cc8d1) | Jan 01, 2025 |
| HP            | Laptop 15s-fq1xxx           | [1de7d2e8fb](https://linux-hardware.org/?probe=1de7d2e8fb) | Dec 30, 2024 |
| ASUSTek       | X555LDB                     | [f11b5b7320](https://linux-hardware.org/?probe=f11b5b7320) | Dec 29, 2024 |
| Lenovo        | IdeaPad Y560                | [e36139662d](https://linux-hardware.org/?probe=e36139662d) | Dec 28, 2024 |
| HP            | EliteBook 830 G5            | [3dd541f1a9](https://linux-hardware.org/?probe=3dd541f1a9) | Dec 28, 2024 |
| HP            | ProBook 645 G2              | [b57a3a877b](https://linux-hardware.org/?probe=b57a3a877b) | Dec 27, 2024 |
| NEC Comput... | PC-LL750MSW                 | [55d20a7230](https://linux-hardware.org/?probe=55d20a7230) | Dec 27, 2024 |
| Dell          | Inspiron 15-3552            | [1d01677080](https://linux-hardware.org/?probe=1d01677080) | Dec 27, 2024 |
| Packard Be... | EasyNote TJ75               | [7a5bc8251a](https://linux-hardware.org/?probe=7a5bc8251a) | Dec 27, 2024 |
| Packard Be... | EasyNote TJ75               | [b46109e7f3](https://linux-hardware.org/?probe=b46109e7f3) | Dec 27, 2024 |
| Sony          | SVF14213CLB                 | [dbcabf3c36](https://linux-hardware.org/?probe=dbcabf3c36) | Dec 27, 2024 |
| Pegatron      | A15                         | [2649401416](https://linux-hardware.org/?probe=2649401416) | Dec 26, 2024 |
| Apple         | MacBookPro10,1              | [4225950551](https://linux-hardware.org/?probe=4225950551) | Dec 25, 2024 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | [d1227bd0de](https://linux-hardware.org/?probe=d1227bd0de) | Dec 25, 2024 |
| HP            | Laptop 15-dy5xxx            | [2729b6a19c](https://linux-hardware.org/?probe=2729b6a19c) | Dec 25, 2024 |
| Acer          | Aspire 5755G                | [d824794995](https://linux-hardware.org/?probe=d824794995) | Dec 23, 2024 |
| Samsung       | SR58P                       | [70e6a978b7](https://linux-hardware.org/?probe=70e6a978b7) | Dec 23, 2024 |
| Dell          | Latitude E6520              | [2bae6e63bb](https://linux-hardware.org/?probe=2bae6e63bb) | Dec 23, 2024 |
| Dell          | XPS 15 9550                 | [f1502af093](https://linux-hardware.org/?probe=f1502af093) | Dec 23, 2024 |
| Acer          | Aspire ES1-571              | [cb4b9da83f](https://linux-hardware.org/?probe=cb4b9da83f) | Dec 22, 2024 |
| Acer          | Aspire ES1-571              | [48537b040b](https://linux-hardware.org/?probe=48537b040b) | Dec 22, 2024 |
| Apple         | MacBookAir7,2               | [762ab31569](https://linux-hardware.org/?probe=762ab31569) | Dec 22, 2024 |
| ASUSTek       | X555LDB                     | [783e6ed502](https://linux-hardware.org/?probe=783e6ed502) | Dec 20, 2024 |
| ASUSTek       | UX30                        | [d75f3afdf6](https://linux-hardware.org/?probe=d75f3afdf6) | Dec 18, 2024 |
| Dell          | Precision 5530              | [3292cf1103](https://linux-hardware.org/?probe=3292cf1103) | Dec 18, 2024 |
| ASUSTek       | X751MA                      | [016d948a0c](https://linux-hardware.org/?probe=016d948a0c) | Dec 17, 2024 |
| HP            | Pavilion dv6                | [89ec19d64a](https://linux-hardware.org/?probe=89ec19d64a) | Dec 17, 2024 |
| HP            | Laptop 17-by3xxx            | [cb8341eaca](https://linux-hardware.org/?probe=cb8341eaca) | Dec 17, 2024 |
| Pegatron      | A15                         | [266dd27eba](https://linux-hardware.org/?probe=266dd27eba) | Dec 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [abfa48ae27](https://linux-hardware.org/?probe=abfa48ae27) | Dec 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [256e4c3f4a](https://linux-hardware.org/?probe=256e4c3f4a) | Dec 15, 2024 |
| HP            | ProBook 6570b               | [70dbe6620b](https://linux-hardware.org/?probe=70dbe6620b) | Dec 14, 2024 |
| Dell          | Inspiron 5547               | [4427bcded0](https://linux-hardware.org/?probe=4427bcded0) | Dec 14, 2024 |
| Dell          | Inspiron 5547               | [5641fb7941](https://linux-hardware.org/?probe=5641fb7941) | Dec 14, 2024 |
| Acer          | Aspire 8730                 | [8c0f6ed012](https://linux-hardware.org/?probe=8c0f6ed012) | Dec 14, 2024 |
| Acer          | Aspire A515-48M             | [1bd13cf77f](https://linux-hardware.org/?probe=1bd13cf77f) | Dec 14, 2024 |
| Acer          | Aspire 8730                 | [1ab4a28fcf](https://linux-hardware.org/?probe=1ab4a28fcf) | Dec 13, 2024 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [37664cf5d9](https://linux-hardware.org/?probe=37664cf5d9) | Dec 13, 2024 |
| Sony          | SVS1313V9RB                 | [52421e92ce](https://linux-hardware.org/?probe=52421e92ce) | Dec 12, 2024 |
| Sony          | SVS1313V9RB                 | [53c77f8751](https://linux-hardware.org/?probe=53c77f8751) | Dec 12, 2024 |
| Unknown       | Unknown                     | [2e17fa2c66](https://linux-hardware.org/?probe=2e17fa2c66) | Dec 12, 2024 |
| Chuwi         | UBook                       | [08e88467cb](https://linux-hardware.org/?probe=08e88467cb) | Dec 12, 2024 |
| ASUSTek       | X550CL                      | [e471757e1c](https://linux-hardware.org/?probe=e471757e1c) | Dec 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [8444dbbcc1](https://linux-hardware.org/?probe=8444dbbcc1) | Dec 10, 2024 |
| Microtech     | ebookPro                    | [4e6f89ca56](https://linux-hardware.org/?probe=4e6f89ca56) | Dec 10, 2024 |
| Acer          | Swift SF314-56G             | [64815f9248](https://linux-hardware.org/?probe=64815f9248) | Dec 09, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | [fc797d558c](https://linux-hardware.org/?probe=fc797d558c) | Dec 08, 2024 |
| Unknown       | Unknown                     | [bd30f7f45d](https://linux-hardware.org/?probe=bd30f7f45d) | Dec 08, 2024 |
| Dell          | Latitude 3340               | [07c627667a](https://linux-hardware.org/?probe=07c627667a) | Dec 07, 2024 |
| HP            | Laptop 17z-ca100            | [e6144203c6](https://linux-hardware.org/?probe=e6144203c6) | Dec 07, 2024 |
| eMachines     | eME732Z                     | [1c64772130](https://linux-hardware.org/?probe=1c64772130) | Dec 06, 2024 |
| Panasonic     | CF-52PFP54QL                | [bcafd21454](https://linux-hardware.org/?probe=bcafd21454) | Dec 06, 2024 |
| Apple         | MacBookAir3,1               | [477a7b324b](https://linux-hardware.org/?probe=477a7b324b) | Dec 06, 2024 |
| Lenovo        | IdeaPad S205 1038D8G        | [78b460173f](https://linux-hardware.org/?probe=78b460173f) | Dec 05, 2024 |
| Chuwi         | UBook                       | [ddba94874a](https://linux-hardware.org/?probe=ddba94874a) | Dec 04, 2024 |
| HP            | Pavilion dv7                | [8d22c82b8d](https://linux-hardware.org/?probe=8d22c82b8d) | Dec 04, 2024 |
| Apple         | MacBook4,1                  | [915a1dbb22](https://linux-hardware.org/?probe=915a1dbb22) | Dec 04, 2024 |
| HP            | EliteBook 2170p             | [39de9fd95f](https://linux-hardware.org/?probe=39de9fd95f) | Dec 04, 2024 |
| Apple         | MacBookAir3,1               | [8517a48127](https://linux-hardware.org/?probe=8517a48127) | Dec 03, 2024 |
| Dell          | Inspiron 5567               | [085d5938c0](https://linux-hardware.org/?probe=085d5938c0) | Dec 03, 2024 |
| Dell          | Inspiron 5567               | [99cb99a15c](https://linux-hardware.org/?probe=99cb99a15c) | Dec 03, 2024 |
| Toshiba       | Satellite L50-B             | [f0195c6929](https://linux-hardware.org/?probe=f0195c6929) | Dec 02, 2024 |
| Apple         | MacBookPro8,1               | [424834b527](https://linux-hardware.org/?probe=424834b527) | Dec 01, 2024 |
| Apple         | MacBookPro12,1              | [deda79f6f5](https://linux-hardware.org/?probe=deda79f6f5) | Dec 01, 2024 |
| ASUSTek       | K93SV                       | [53af6a8e17](https://linux-hardware.org/?probe=53af6a8e17) | Nov 30, 2024 |
| Toshiba       | Satellite L50-B             | [344eaec320](https://linux-hardware.org/?probe=344eaec320) | Nov 29, 2024 |
| Dell          | Inspiron N5010              | [f7578fb476](https://linux-hardware.org/?probe=f7578fb476) | Nov 29, 2024 |
| Apple         | MacBookPro8,1               | [a817c04b09](https://linux-hardware.org/?probe=a817c04b09) | Nov 29, 2024 |
| HP            | Pavilion dv7                | [1ae9d9a604](https://linux-hardware.org/?probe=1ae9d9a604) | Nov 29, 2024 |
| Dell          | Latitude 5420               | [9e6c2d1825](https://linux-hardware.org/?probe=9e6c2d1825) | Nov 28, 2024 |
| MicroByte     | ezbook                      | [167d9d082a](https://linux-hardware.org/?probe=167d9d082a) | Nov 28, 2024 |
| Google        | Delbin                      | [e4f8dab394](https://linux-hardware.org/?probe=e4f8dab394) | Nov 27, 2024 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [7e022f0097](https://linux-hardware.org/?probe=7e022f0097) | Nov 27, 2024 |
| Acer          | Aspire E3-111               | [f90ddc6433](https://linux-hardware.org/?probe=f90ddc6433) | Nov 26, 2024 |
| Apple         | MacBookAir6,1               | [a42587525c](https://linux-hardware.org/?probe=a42587525c) | Nov 25, 2024 |
| Apple         | MacBookAir6,1               | [1d464cc8ce](https://linux-hardware.org/?probe=1d464cc8ce) | Nov 25, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | [d24fd529d4](https://linux-hardware.org/?probe=d24fd529d4) | Nov 25, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | [d7914ef50d](https://linux-hardware.org/?probe=d7914ef50d) | Nov 22, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [8ecfb38136](https://linux-hardware.org/?probe=8ecfb38136) | Nov 22, 2024 |
| HP            | Pavilion Sleekbook 15 PC    | [c785c1f7dd](https://linux-hardware.org/?probe=c785c1f7dd) | Nov 21, 2024 |
| HP            | ProBook 6560b               | [72ddcb1cf2](https://linux-hardware.org/?probe=72ddcb1cf2) | Nov 20, 2024 |
| HP            | Laptop 17-cn0xxx            | [058f6bf1ac](https://linux-hardware.org/?probe=058f6bf1ac) | Nov 20, 2024 |
| HP            | Laptop 17-cn0xxx            | [541dd7b9fb](https://linux-hardware.org/?probe=541dd7b9fb) | Nov 19, 2024 |
| Apple         | MacBookPro5,5               | [3f2eff0083](https://linux-hardware.org/?probe=3f2eff0083) | Nov 18, 2024 |
| Lenovo        | ThinkPad X260 20F5A2FXTH    | [8609525ceb](https://linux-hardware.org/?probe=8609525ceb) | Nov 18, 2024 |
| Apple         | MacBookPro7,1               | [7d86d39596](https://linux-hardware.org/?probe=7d86d39596) | Nov 17, 2024 |
| Apple         | MacBookPro5,5               | [001f8b1280](https://linux-hardware.org/?probe=001f8b1280) | Nov 17, 2024 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | [8715440da3](https://linux-hardware.org/?probe=8715440da3) | Nov 17, 2024 |
| Dell          | Inspiron N5030              | [acf692231b](https://linux-hardware.org/?probe=acf692231b) | Nov 17, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [0d4cb9a88f](https://linux-hardware.org/?probe=0d4cb9a88f) | Nov 16, 2024 |
| Lenovo        | G50-80 80L0                 | [d31664cad1](https://linux-hardware.org/?probe=d31664cad1) | Nov 15, 2024 |
| Apple         | MacBookPro8,2               | [0259216292](https://linux-hardware.org/?probe=0259216292) | Nov 15, 2024 |
| Apple         | MacBookPro9,2               | [7029186fa5](https://linux-hardware.org/?probe=7029186fa5) | Nov 14, 2024 |
| Apple         | MacBookPro8,1               | [2f0fa7a4fa](https://linux-hardware.org/?probe=2f0fa7a4fa) | Nov 11, 2024 |
| Apple         | MacBookPro5,2               | [a0db5bcf03](https://linux-hardware.org/?probe=a0db5bcf03) | Nov 08, 2024 |
| Acer          | Aspire E5-771               | [9b889ed10a](https://linux-hardware.org/?probe=9b889ed10a) | Nov 08, 2024 |
| Apple         | MacBookPro8,1               | [0b5989c295](https://linux-hardware.org/?probe=0b5989c295) | Nov 06, 2024 |
| Lenovo        | G580 20150                  | [71249fccac](https://linux-hardware.org/?probe=71249fccac) | Nov 06, 2024 |
| Lenovo        | G580 20150                  | [ebcff700e9](https://linux-hardware.org/?probe=ebcff700e9) | Nov 06, 2024 |
| LTD Delovo... | 15Y                         | [5553e46796](https://linux-hardware.org/?probe=5553e46796) | Nov 04, 2024 |
| LTD Delovo... | 15Y                         | [0187f0b5ab](https://linux-hardware.org/?probe=0187f0b5ab) | Nov 04, 2024 |
| Samsung       | 940XFG                      | [8d09e8db06](https://linux-hardware.org/?probe=8d09e8db06) | Nov 04, 2024 |
| HUAWEI        | BOM-WXX9                    | [f0b28bde30](https://linux-hardware.org/?probe=f0b28bde30) | Nov 03, 2024 |
| Dell          | Latitude 7420               | [2454ee0dbb](https://linux-hardware.org/?probe=2454ee0dbb) | Nov 03, 2024 |
| Lenovo        | G700 20251                  | [3af4ad6599](https://linux-hardware.org/?probe=3af4ad6599) | Nov 01, 2024 |
| Acer          | Aspire V3-772               | [9d4e69ab29](https://linux-hardware.org/?probe=9d4e69ab29) | Nov 01, 2024 |
| Acer          | Aspire V3-772               | [a48e5acfb4](https://linux-hardware.org/?probe=a48e5acfb4) | Nov 01, 2024 |
| HP            | Laptop 14-fq0xxx            | [a8d14fa552](https://linux-hardware.org/?probe=a8d14fa552) | Nov 01, 2024 |
| HP            | Laptop 15-bw0xx             | [55ef342a18](https://linux-hardware.org/?probe=55ef342a18) | Oct 31, 2024 |
| HP            | ProBook 4535s               | [f66c124f3a](https://linux-hardware.org/?probe=f66c124f3a) | Oct 31, 2024 |
| Apple         | MacBookPro8,1               | [3fe4d1a80a](https://linux-hardware.org/?probe=3fe4d1a80a) | Oct 31, 2024 |
| ASUSTek       | K46CB                       | [e081c9ab8c](https://linux-hardware.org/?probe=e081c9ab8c) | Oct 30, 2024 |
| Apple         | MacBookPro9,2               | [91eb0db216](https://linux-hardware.org/?probe=91eb0db216) | Oct 30, 2024 |
| HP            | Laptop 15s-eq2xxx           | [1755d407c9](https://linux-hardware.org/?probe=1755d407c9) | Oct 29, 2024 |
| HP            | Compaq 15                   | [fd2b849a08](https://linux-hardware.org/?probe=fd2b849a08) | Oct 28, 2024 |
| Apple         | MacBookPro9,2               | [59f6758081](https://linux-hardware.org/?probe=59f6758081) | Oct 25, 2024 |
| Apple         | MacBookAir7,2               | [73fb34d315](https://linux-hardware.org/?probe=73fb34d315) | Oct 25, 2024 |
| HUAWEI        | BOD-WXX9                    | [c4829d7d0c](https://linux-hardware.org/?probe=c4829d7d0c) | Oct 25, 2024 |
| HUAWEI        | BOHB-WAX9                   | [e114c5afe5](https://linux-hardware.org/?probe=e114c5afe5) | Oct 24, 2024 |
| Dell          | Latitude 7370               | [355bbe7ecc](https://linux-hardware.org/?probe=355bbe7ecc) | Oct 24, 2024 |
| Apple         | MacBookAir7,2               | [92672f3d2c](https://linux-hardware.org/?probe=92672f3d2c) | Oct 23, 2024 |
| Apple         | MacBookAir7,2               | [8bbb5c5a53](https://linux-hardware.org/?probe=8bbb5c5a53) | Oct 23, 2024 |
| HP            | ProBook 6465b               | [3afb9ebed6](https://linux-hardware.org/?probe=3afb9ebed6) | Oct 23, 2024 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | [18058066d2](https://linux-hardware.org/?probe=18058066d2) | Oct 22, 2024 |
| Apple         | MacBookAir4,1               | [a899fd963a](https://linux-hardware.org/?probe=a899fd963a) | Oct 22, 2024 |
| Apple         | MacBookAir4,1               | [6c25a578b8](https://linux-hardware.org/?probe=6c25a578b8) | Oct 22, 2024 |
| Sony          | VPCEJ1Z1E                   | [d1da65abb4](https://linux-hardware.org/?probe=d1da65abb4) | Oct 22, 2024 |
| Lenovo        | V15-ADA 82C7                | [76d8c86d01](https://linux-hardware.org/?probe=76d8c86d01) | Oct 22, 2024 |
| HUAWEI        | KLVL-WXX9                   | [faeb5479f8](https://linux-hardware.org/?probe=faeb5479f8) | Oct 21, 2024 |
| HUAWEI        | NBLB-WAX9N                  | [e188597923](https://linux-hardware.org/?probe=e188597923) | Oct 19, 2024 |
| Apple         | MacBookAir7,2               | [f63adab3c7](https://linux-hardware.org/?probe=f63adab3c7) | Oct 19, 2024 |
| Fujitsu       | LIFEBOOK A530               | [afb324991b](https://linux-hardware.org/?probe=afb324991b) | Oct 18, 2024 |
| Fujitsu       | LIFEBOOK A530               | [3337802835](https://linux-hardware.org/?probe=3337802835) | Oct 18, 2024 |
| Apple         | MacBookPro8,1               | [83508d3840](https://linux-hardware.org/?probe=83508d3840) | Oct 17, 2024 |
| Samsung       | 940XFG                      | [741f7a6544](https://linux-hardware.org/?probe=741f7a6544) | Oct 17, 2024 |
| Apple         | MacBook6,1                  | [d3b5f5da93](https://linux-hardware.org/?probe=d3b5f5da93) | Oct 17, 2024 |
| HP            | Laptop 15s-eq2xxx           | [d0ac53c68a](https://linux-hardware.org/?probe=d0ac53c68a) | Oct 16, 2024 |
| Acer          | Aspire 7736                 | [be7f2e237f](https://linux-hardware.org/?probe=be7f2e237f) | Oct 15, 2024 |
| ASUSTek       | X555LPB                     | [2f3f2073da](https://linux-hardware.org/?probe=2f3f2073da) | Oct 14, 2024 |
| Acer          | Aspire 7736                 | [96c83e0281](https://linux-hardware.org/?probe=96c83e0281) | Oct 14, 2024 |
| Apple         | MacBookPro8,1               | [d2d644c166](https://linux-hardware.org/?probe=d2d644c166) | Oct 13, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | [cee555c4f8](https://linux-hardware.org/?probe=cee555c4f8) | Oct 13, 2024 |
| Apple         | MacBookPro8,3               | [030dbaca80](https://linux-hardware.org/?probe=030dbaca80) | Oct 13, 2024 |
| Positivo      | VJF154                      | [dbd1be19a4](https://linux-hardware.org/?probe=dbd1be19a4) | Oct 12, 2024 |
| Positivo      | VJF154                      | [11a95affa0](https://linux-hardware.org/?probe=11a95affa0) | Oct 12, 2024 |
| Sony          | VPCEJ1Z1E                   | [627da18a5d](https://linux-hardware.org/?probe=627da18a5d) | Oct 12, 2024 |
| Apple         | MacBookPro8,3               | [8a25a02400](https://linux-hardware.org/?probe=8a25a02400) | Oct 12, 2024 |
| HP            | Compaq 6530b (GW688AV)      | [2db6bf65e8](https://linux-hardware.org/?probe=2db6bf65e8) | Oct 12, 2024 |
| HP            | Compaq 6530b (GW688AV)      | [a9cb352415](https://linux-hardware.org/?probe=a9cb352415) | Oct 12, 2024 |
| Apple         | MacBookPro8,3               | [ca109e5057](https://linux-hardware.org/?probe=ca109e5057) | Oct 12, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [08d25ef16b](https://linux-hardware.org/?probe=08d25ef16b) | Oct 12, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [6c5d0a8a4b](https://linux-hardware.org/?probe=6c5d0a8a4b) | Oct 12, 2024 |
| HP            | 15                          | [812b65f0fe](https://linux-hardware.org/?probe=812b65f0fe) | Oct 11, 2024 |
| Apple         | MacBook6,1                  | [3623e327b2](https://linux-hardware.org/?probe=3623e327b2) | Oct 11, 2024 |
| HP            | EliteBook 830 G5            | [64cebe30ad](https://linux-hardware.org/?probe=64cebe30ad) | Oct 10, 2024 |
| Lenovo        | V15 G3 ABA 82TV             | [bf025aaa26](https://linux-hardware.org/?probe=bf025aaa26) | Oct 08, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | [ecf4696b37](https://linux-hardware.org/?probe=ecf4696b37) | Oct 07, 2024 |
| Apple         | MacBookAir3,1               | [01cd6549a5](https://linux-hardware.org/?probe=01cd6549a5) | Oct 06, 2024 |
| Apple         | MacBookPro9,2               | [0f138dcac0](https://linux-hardware.org/?probe=0f138dcac0) | Oct 06, 2024 |
| HP            | EliteBook 830 G5            | [c8c6a6269b](https://linux-hardware.org/?probe=c8c6a6269b) | Oct 06, 2024 |
| ARCELIK       | 1M7-GNB1595B6I7             | [cbf522f76a](https://linux-hardware.org/?probe=cbf522f76a) | Oct 05, 2024 |
| Sony          | VPCEC3L1E                   | [748694aa38](https://linux-hardware.org/?probe=748694aa38) | Oct 05, 2024 |
| Positivo      | VJF154                      | [70bb906734](https://linux-hardware.org/?probe=70bb906734) | Oct 04, 2024 |
| Dell          | Latitude E6520              | [5af0de6a9c](https://linux-hardware.org/?probe=5af0de6a9c) | Oct 04, 2024 |
| Dell          | Precision 5530              | [7d736763e8](https://linux-hardware.org/?probe=7d736763e8) | Oct 04, 2024 |
| Alienware     | 17 R3                       | [b22f85d157](https://linux-hardware.org/?probe=b22f85d157) | Oct 03, 2024 |
| Samsung       | 900X3F                      | [12e6b46207](https://linux-hardware.org/?probe=12e6b46207) | Oct 03, 2024 |
| Samsung       | 900X3F                      | [5b7f51059a](https://linux-hardware.org/?probe=5b7f51059a) | Oct 03, 2024 |
| HP            | G60                         | [b2cbfa9c26](https://linux-hardware.org/?probe=b2cbfa9c26) | Oct 02, 2024 |
| HP            | Laptop 15-bw0xx             | [1046a844db](https://linux-hardware.org/?probe=1046a844db) | Sep 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [bfd414e273](https://linux-hardware.org/?probe=bfd414e273) | Sep 30, 2024 |
| Dell          | Inspiron N5110              | [39053cddd2](https://linux-hardware.org/?probe=39053cddd2) | Sep 29, 2024 |
| Apple         | MacBookPro5,1               | [ea1547836b](https://linux-hardware.org/?probe=ea1547836b) | Sep 27, 2024 |
| Apple         | MacBookAir3,1               | [ce465db6d8](https://linux-hardware.org/?probe=ce465db6d8) | Sep 26, 2024 |
| realme        | RMNBXXXX                    | [a56e71a36d](https://linux-hardware.org/?probe=a56e71a36d) | Sep 25, 2024 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [eb1144d5d0](https://linux-hardware.org/?probe=eb1144d5d0) | Sep 23, 2024 |
| Apple         | MacBookPro9,2               | [d02c3ea8d2](https://linux-hardware.org/?probe=d02c3ea8d2) | Sep 22, 2024 |
| Apple         | MacBookPro9,2               | [de3ad3dcb2](https://linux-hardware.org/?probe=de3ad3dcb2) | Sep 22, 2024 |
| Acer          | Aspire E5-511G              | [eb212c1295](https://linux-hardware.org/?probe=eb212c1295) | Sep 21, 2024 |
| Samsung       | 900X3J                      | [84b81dc973](https://linux-hardware.org/?probe=84b81dc973) | Sep 19, 2024 |
| Apple         | MacBook6,1                  | [754a9d1a14](https://linux-hardware.org/?probe=754a9d1a14) | Sep 19, 2024 |
| Acer          | Nitro AN515-52              | [0bc35e551d](https://linux-hardware.org/?probe=0bc35e551d) | Sep 18, 2024 |
| Apple         | MacBookPro9,2               | [e386b9f60a](https://linux-hardware.org/?probe=e386b9f60a) | Sep 18, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | [22c790176f](https://linux-hardware.org/?probe=22c790176f) | Sep 18, 2024 |
| Lenovo        | G400 20235                  | [96ebcfea10](https://linux-hardware.org/?probe=96ebcfea10) | Sep 18, 2024 |
| Acer          | Aspire E5-511G              | [0b1a846a69](https://linux-hardware.org/?probe=0b1a846a69) | Sep 17, 2024 |
| HP            | EliteBook 840 G1            | [a2f78f9d5a](https://linux-hardware.org/?probe=a2f78f9d5a) | Sep 17, 2024 |
| HP            | Pavilion 17                 | [fb7884d776](https://linux-hardware.org/?probe=fb7884d776) | Sep 16, 2024 |
| HP            | Pavilion dv6700             | [79316bc8bf](https://linux-hardware.org/?probe=79316bc8bf) | Sep 16, 2024 |
| Acer          | Aspire 5750                 | [d030037b8b](https://linux-hardware.org/?probe=d030037b8b) | Sep 14, 2024 |
| Acer          | Aspire 7745G                | [76a55f9bb1](https://linux-hardware.org/?probe=76a55f9bb1) | Sep 14, 2024 |
| Dell          | Inspiron 3721               | [dd0fd36c69](https://linux-hardware.org/?probe=dd0fd36c69) | Sep 14, 2024 |
| Lenovo        | V14 G2 ITL 82KA             | [156f5f004e](https://linux-hardware.org/?probe=156f5f004e) | Sep 13, 2024 |
| Apple         | MacBookPro11,3              | [ce91008479](https://linux-hardware.org/?probe=ce91008479) | Sep 13, 2024 |
| Dell          | XPS 13 9343                 | [ca52ff1c29](https://linux-hardware.org/?probe=ca52ff1c29) | Sep 13, 2024 |
| Alienware     | 17 R3                       | [d95edb94cd](https://linux-hardware.org/?probe=d95edb94cd) | Sep 13, 2024 |
| Toshiba       | Satellite L50-B             | [bb130f4634](https://linux-hardware.org/?probe=bb130f4634) | Sep 11, 2024 |
| Acer          | Aspire 5750                 | [0c7144d06b](https://linux-hardware.org/?probe=0c7144d06b) | Sep 10, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [cd6caa40b8](https://linux-hardware.org/?probe=cd6caa40b8) | Sep 10, 2024 |
| Lenovo        | B590 20206                  | [38ef54ca0c](https://linux-hardware.org/?probe=38ef54ca0c) | Sep 09, 2024 |
| Lenovo        | B590 20206                  | [3e57e1486e](https://linux-hardware.org/?probe=3e57e1486e) | Sep 09, 2024 |
| Sony          | SVF15A1B4E                  | [08c43f2d50](https://linux-hardware.org/?probe=08c43f2d50) | Sep 09, 2024 |
| Dell          | Inspiron 3721               | [8c75a1af97](https://linux-hardware.org/?probe=8c75a1af97) | Sep 05, 2024 |
| Dell          | Inspiron 3721               | [8a051dce97](https://linux-hardware.org/?probe=8a051dce97) | Sep 03, 2024 |
| Acer          | TravelMate 5735Z            | [b59bdd3310](https://linux-hardware.org/?probe=b59bdd3310) | Sep 02, 2024 |
| Dell          | Latitude 5510               | [634228ff35](https://linux-hardware.org/?probe=634228ff35) | Sep 02, 2024 |
| Apple         | MacBookPro9,1               | [41e0375932](https://linux-hardware.org/?probe=41e0375932) | Sep 02, 2024 |
| Apple         | MacBookPro8,1               | [c1c6557769](https://linux-hardware.org/?probe=c1c6557769) | Sep 01, 2024 |
| Apple         | MacBookPro6,2               | [7a30d49834](https://linux-hardware.org/?probe=7a30d49834) | Sep 01, 2024 |
| Lenovo        | G50-70 20351                | [8175aeac94](https://linux-hardware.org/?probe=8175aeac94) | Aug 31, 2024 |
| Apple         | MacBookPro9,2               | [60e3c48bbc](https://linux-hardware.org/?probe=60e3c48bbc) | Aug 30, 2024 |
| ASUSTek       | TP300LA                     | [55fb687fea](https://linux-hardware.org/?probe=55fb687fea) | Aug 30, 2024 |
| Dell          | Latitude E5420              | [1aa4784afb](https://linux-hardware.org/?probe=1aa4784afb) | Aug 29, 2024 |
| ASUSTek       | 1015PX                      | [b83d98a551](https://linux-hardware.org/?probe=b83d98a551) | Aug 29, 2024 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [9f47f2b01b](https://linux-hardware.org/?probe=9f47f2b01b) | Aug 29, 2024 |
| Gigabyte      | G5 GD                       | [2840fa5a43](https://linux-hardware.org/?probe=2840fa5a43) | Aug 27, 2024 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [2aa427ea2b](https://linux-hardware.org/?probe=2aa427ea2b) | Aug 27, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [a0dc16409e](https://linux-hardware.org/?probe=a0dc16409e) | Aug 26, 2024 |
| Apple         | MacBookPro5,1               | [5add020da3](https://linux-hardware.org/?probe=5add020da3) | Aug 25, 2024 |
| Toshiba       | Satellite C660D             | [fb51658e06](https://linux-hardware.org/?probe=fb51658e06) | Aug 23, 2024 |
| MSI           | GF63 8RC                    | [ea6d76ec59](https://linux-hardware.org/?probe=ea6d76ec59) | Aug 23, 2024 |
| Apple         | MacBook4,1                  | [b366ec9d80](https://linux-hardware.org/?probe=b366ec9d80) | Aug 23, 2024 |
| Apple         | MacBookPro8,1               | [a8f4d7f114](https://linux-hardware.org/?probe=a8f4d7f114) | Aug 22, 2024 |
| Apple         | MacBookPro8,1               | [de194919c2](https://linux-hardware.org/?probe=de194919c2) | Aug 21, 2024 |
| Dell          | XPS 13 9343                 | [e9a7ac7834](https://linux-hardware.org/?probe=e9a7ac7834) | Aug 21, 2024 |
| Apple         | MacBookPro11,5              | [b31f952991](https://linux-hardware.org/?probe=b31f952991) | Aug 19, 2024 |
| Dell          | Inspiron 15-3567            | [5040de05ac](https://linux-hardware.org/?probe=5040de05ac) | Aug 18, 2024 |
| Apple         | MacBookPro8,1               | [b7eb460f7e](https://linux-hardware.org/?probe=b7eb460f7e) | Aug 17, 2024 |
| Apple         | MacBookPro8,1               | [dc84101f95](https://linux-hardware.org/?probe=dc84101f95) | Aug 17, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2ffa4f7ffc](https://linux-hardware.org/?probe=2ffa4f7ffc) | Aug 15, 2024 |
| Dell          | G15 5510                    | [bd868cf551](https://linux-hardware.org/?probe=bd868cf551) | Aug 15, 2024 |
| Apple         | MacBookAir1,1               | [46b20c4ffe](https://linux-hardware.org/?probe=46b20c4ffe) | Aug 10, 2024 |
| Apple         | MacBookAir4,2               | [463b931271](https://linux-hardware.org/?probe=463b931271) | Aug 08, 2024 |
| HP            | G56                         | [28f40c35e9](https://linux-hardware.org/?probe=28f40c35e9) | Aug 07, 2024 |
| HP            | Compaq 6730b (KE717AV)      | [c6ce1872c3](https://linux-hardware.org/?probe=c6ce1872c3) | Aug 07, 2024 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [9359d579a1](https://linux-hardware.org/?probe=9359d579a1) | Aug 07, 2024 |
| HP            | Laptop 17-ca3xxx            | [917cec826a](https://linux-hardware.org/?probe=917cec826a) | Aug 04, 2024 |
| Lenovo        | Unknown                     | [f228fbc5ba](https://linux-hardware.org/?probe=f228fbc5ba) | Aug 04, 2024 |
| HP            | ProBook 440 G8 Notebook ... | [bb3e675ece](https://linux-hardware.org/?probe=bb3e675ece) | Aug 04, 2024 |
| Lenovo        | G400 20235                  | [ffa298e6de](https://linux-hardware.org/?probe=ffa298e6de) | Aug 03, 2024 |
| Lenovo        | B50-80 80EW                 | [39cd7e2e3c](https://linux-hardware.org/?probe=39cd7e2e3c) | Aug 03, 2024 |
| Lenovo        | ThinkPad T480 20L6S0HG00    | [641f0fa927](https://linux-hardware.org/?probe=641f0fa927) | Aug 03, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [6332bb4a7c](https://linux-hardware.org/?probe=6332bb4a7c) | Jul 29, 2024 |
| HUAWEI        | BOM-WXX9                    | [00af61adcc](https://linux-hardware.org/?probe=00af61adcc) | Jul 29, 2024 |
| Google        | Dratini                     | [8bb5dafec1](https://linux-hardware.org/?probe=8bb5dafec1) | Jul 28, 2024 |
| MSI           | GP63 Leopard 8RE            | [fd419bc9ef](https://linux-hardware.org/?probe=fd419bc9ef) | Jul 27, 2024 |
| Unknown       | Unknown                     | [350031c0ed](https://linux-hardware.org/?probe=350031c0ed) | Jul 27, 2024 |
| Apple         | MacBookAir4,2               | [9d37505b50](https://linux-hardware.org/?probe=9d37505b50) | Jul 26, 2024 |
| Lenovo        | G460 20041                  | [67670a0f4a](https://linux-hardware.org/?probe=67670a0f4a) | Jul 25, 2024 |
| Lenovo        | ThinkPad T490s 20NYS12E0... | [1e7a4734ce](https://linux-hardware.org/?probe=1e7a4734ce) | Jul 25, 2024 |
| Lenovo        | ThinkPad T490s 20NYS12E0... | [c80f2e729d](https://linux-hardware.org/?probe=c80f2e729d) | Jul 23, 2024 |
| Lenovo        | B50-80 80EW                 | [1896ed136c](https://linux-hardware.org/?probe=1896ed136c) | Jul 23, 2024 |
| Apple         | MacBookPro6,2               | [72c27fa1c1](https://linux-hardware.org/?probe=72c27fa1c1) | Jul 23, 2024 |
| HP            | ENVY 17                     | [8d586d3909](https://linux-hardware.org/?probe=8d586d3909) | Jul 22, 2024 |
| HP            | ENVY 17                     | [f97fdd96f8](https://linux-hardware.org/?probe=f97fdd96f8) | Jul 22, 2024 |
| HP            | Pavilion 17                 | [ea65b65978](https://linux-hardware.org/?probe=ea65b65978) | Jul 22, 2024 |
| Sony          | VPCEB2H4E                   | [144fb934d0](https://linux-hardware.org/?probe=144fb934d0) | Jul 22, 2024 |
| Apple         | MacBookPro6,2               | [298b035882](https://linux-hardware.org/?probe=298b035882) | Jul 22, 2024 |
| HP            | ProBook 450 G3              | [2bac99deff](https://linux-hardware.org/?probe=2bac99deff) | Jul 21, 2024 |
| Lenovo        | G460 20041                  | [2baabb5540](https://linux-hardware.org/?probe=2baabb5540) | Jul 20, 2024 |
| HP            | 250 G5 Notebook PC          | [687e56399a](https://linux-hardware.org/?probe=687e56399a) | Jul 20, 2024 |
| Lenovo        | ThinkPad E480 20KN009QGE    | [96b86c74c8](https://linux-hardware.org/?probe=96b86c74c8) | Jul 19, 2024 |
| Dell          | Inspiron 3580               | [8ef4654d8c](https://linux-hardware.org/?probe=8ef4654d8c) | Jul 18, 2024 |
| Dell          | Inspiron 3583               | [dccbf42cb3](https://linux-hardware.org/?probe=dccbf42cb3) | Jul 16, 2024 |
| Apple         | MacBookPro9,2               | [4f3c1e544b](https://linux-hardware.org/?probe=4f3c1e544b) | Jul 15, 2024 |
| Apple         | MacBookPro8,1               | [e673ae4869](https://linux-hardware.org/?probe=e673ae4869) | Jul 14, 2024 |
| Apple         | MacBookPro8,1               | [20850127a9](https://linux-hardware.org/?probe=20850127a9) | Jul 14, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [4da9ebe6b5](https://linux-hardware.org/?probe=4da9ebe6b5) | Jul 13, 2024 |
| Dell          | Inspiron 3580               | [7a2073b0b4](https://linux-hardware.org/?probe=7a2073b0b4) | Jul 13, 2024 |
| Apple         | MacBook6,1                  | [54ed747270](https://linux-hardware.org/?probe=54ed747270) | Jul 13, 2024 |
| HP            | G42                         | [1ab8c40d0d](https://linux-hardware.org/?probe=1ab8c40d0d) | Jul 11, 2024 |
| Apple         | MacBookPro9,1               | [5e25885998](https://linux-hardware.org/?probe=5e25885998) | Jul 09, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | [fdb5740619](https://linux-hardware.org/?probe=fdb5740619) | Jul 08, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | [344a3a1381](https://linux-hardware.org/?probe=344a3a1381) | Jul 08, 2024 |
| Lenovo        | ThinkPad E480 20KN003TUS    | [389c663679](https://linux-hardware.org/?probe=389c663679) | Jul 08, 2024 |
| Lenovo        | ThinkPad E480 20KN003TUS    | [72dc55770d](https://linux-hardware.org/?probe=72dc55770d) | Jul 08, 2024 |
| Apple         | MacBookPro8,3               | [7f3622744d](https://linux-hardware.org/?probe=7f3622744d) | Jul 07, 2024 |
| Apple         | MacBookPro8,3               | [bb167dd1e3](https://linux-hardware.org/?probe=bb167dd1e3) | Jul 07, 2024 |
| Compaq        | Presario CQ-17              | [ac298b1a45](https://linux-hardware.org/?probe=ac298b1a45) | Jul 04, 2024 |
| Dell          | Precision 7720              | [26f2413f41](https://linux-hardware.org/?probe=26f2413f41) | Jul 04, 2024 |
| Lenovo        | Y520-15IKBA 80WY            | [e3fc209866](https://linux-hardware.org/?probe=e3fc209866) | Jul 03, 2024 |
| Apple         | MacBookPro7,1               | [22f634f998](https://linux-hardware.org/?probe=22f634f998) | Jul 02, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | [e09d0fb605](https://linux-hardware.org/?probe=e09d0fb605) | Jul 01, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | [f91526c63f](https://linux-hardware.org/?probe=f91526c63f) | Jul 01, 2024 |
| HP            | Pavilion dv6                | [25259c90d4](https://linux-hardware.org/?probe=25259c90d4) | Jun 27, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [bed62e6b3c](https://linux-hardware.org/?probe=bed62e6b3c) | Jun 26, 2024 |
| Lenovo        | IdeaPad 1 14ADA7 82R0       | [c8bce44bed](https://linux-hardware.org/?probe=c8bce44bed) | Jun 26, 2024 |
| Samsung       | 305V4A/305V5A               | [e4f376bd36](https://linux-hardware.org/?probe=e4f376bd36) | Jun 26, 2024 |
| Apple         | MacBookPro5,5               | [85c379a6a8](https://linux-hardware.org/?probe=85c379a6a8) | Jun 25, 2024 |
| Dell          | Latitude E4310              | [c2303e5967](https://linux-hardware.org/?probe=c2303e5967) | Jun 25, 2024 |
| Dell          | Latitude E4310              | [f985372e98](https://linux-hardware.org/?probe=f985372e98) | Jun 25, 2024 |
| HP            | Pavilion dv2000 (GM691LA... | [de1b028bbb](https://linux-hardware.org/?probe=de1b028bbb) | Jun 24, 2024 |
| ASUSTek       | K42F                        | [384052ea34](https://linux-hardware.org/?probe=384052ea34) | Jun 24, 2024 |
| ASUSTek       | K42F                        | [7978cdf8b4](https://linux-hardware.org/?probe=7978cdf8b4) | Jun 24, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [6e291c60fd](https://linux-hardware.org/?probe=6e291c60fd) | Jun 22, 2024 |
| Acer          | Aspire A515-54              | [14565c27bf](https://linux-hardware.org/?probe=14565c27bf) | Jun 22, 2024 |
| Lenovo        | ThinkPad T530 2392CTO       | [e7921f65ce](https://linux-hardware.org/?probe=e7921f65ce) | Jun 20, 2024 |
| Dell          | Latitude E7440              | [5fc427cc24](https://linux-hardware.org/?probe=5fc427cc24) | Jun 20, 2024 |
| Dell          | Inspiron N4010              | [dad60b8122](https://linux-hardware.org/?probe=dad60b8122) | Jun 20, 2024 |
| Apple         | MacBookPro9,2               | [59ab2f562b](https://linux-hardware.org/?probe=59ab2f562b) | Jun 19, 2024 |
| Apple         | MacBookPro9,2               | [c2e291249c](https://linux-hardware.org/?probe=c2e291249c) | Jun 19, 2024 |
| Apple         | MacBookAir7,2               | [e381ac4c82](https://linux-hardware.org/?probe=e381ac4c82) | Jun 19, 2024 |
| Lenovo        | ThinkPad T440p 20AN00DEU... | [f476dc9a4c](https://linux-hardware.org/?probe=f476dc9a4c) | Jun 18, 2024 |
| Dell          | System XPS L502X            | [58023857ae](https://linux-hardware.org/?probe=58023857ae) | Jun 17, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [14aecfba4d](https://linux-hardware.org/?probe=14aecfba4d) | Jun 16, 2024 |
| Dell          | Latitude 5424 Rugged        | [8ce01f0186](https://linux-hardware.org/?probe=8ce01f0186) | Jun 16, 2024 |
| Dell          | XPS 15 9500                 | [36b06bd4db](https://linux-hardware.org/?probe=36b06bd4db) | Jun 15, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [e2f4b2305a](https://linux-hardware.org/?probe=e2f4b2305a) | Jun 15, 2024 |
| ASUSTek       | G750JS                      | [1be0b00e6a](https://linux-hardware.org/?probe=1be0b00e6a) | Jun 15, 2024 |
| Dell          | Latitude 5424 Rugged        | [2286699120](https://linux-hardware.org/?probe=2286699120) | Jun 14, 2024 |
| Chuwi         | UBook XPro                  | [1a9ca58ced](https://linux-hardware.org/?probe=1a9ca58ced) | Jun 13, 2024 |
| ASUSTek       | K501UX                      | [ccf68ea2d8](https://linux-hardware.org/?probe=ccf68ea2d8) | Jun 13, 2024 |
| Myway         | U1306i                      | [a029a374de](https://linux-hardware.org/?probe=a029a374de) | Jun 12, 2024 |
| HP            | EliteBook 8460p             | [ef3581ab2b](https://linux-hardware.org/?probe=ef3581ab2b) | Jun 12, 2024 |
| Google        | Nospike                     | [da6fe22637](https://linux-hardware.org/?probe=da6fe22637) | Jun 12, 2024 |
| Google        | Nospike                     | [86096b4ac8](https://linux-hardware.org/?probe=86096b4ac8) | Jun 11, 2024 |
| Apple         | MacBookPro7,1               | [cbccdbbf42](https://linux-hardware.org/?probe=cbccdbbf42) | Jun 10, 2024 |
| HP            | Compaq Presario CQ61        | [ab0cc4ab6b](https://linux-hardware.org/?probe=ab0cc4ab6b) | Jun 09, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [f30cff4982](https://linux-hardware.org/?probe=f30cff4982) | Jun 09, 2024 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [2bde6824fc](https://linux-hardware.org/?probe=2bde6824fc) | Jun 09, 2024 |
| ASUSTek       | X45U                        | [21e364e5a7](https://linux-hardware.org/?probe=21e364e5a7) | Jun 07, 2024 |
| Dell          | Latitude E6440              | [74814a37e4](https://linux-hardware.org/?probe=74814a37e4) | Jun 05, 2024 |
| ASUSTek       | X553MA                      | [d20ab5f5be](https://linux-hardware.org/?probe=d20ab5f5be) | Jun 03, 2024 |
| HP            | ProBook 450 G3              | [14d13ac22c](https://linux-hardware.org/?probe=14d13ac22c) | Jun 03, 2024 |
| Lenovo        | V580c 20160                 | [7895c2caac](https://linux-hardware.org/?probe=7895c2caac) | Jun 03, 2024 |
| ASUSTek       | X555LAB                     | [93f930012f](https://linux-hardware.org/?probe=93f930012f) | Jun 02, 2024 |
| HP            | ProBook 445 G8 Notebook ... | [a627db0998](https://linux-hardware.org/?probe=a627db0998) | Jun 02, 2024 |
| Apple         | MacBookAir5,2               | [11cbeead14](https://linux-hardware.org/?probe=11cbeead14) | May 31, 2024 |
| Dell          | Latitude E6320              | [356970f66c](https://linux-hardware.org/?probe=356970f66c) | May 30, 2024 |
| Apple         | MacBookPro8,1               | [b545c96334](https://linux-hardware.org/?probe=b545c96334) | May 28, 2024 |
| Dell          | Latitude E4310              | [28638e3182](https://linux-hardware.org/?probe=28638e3182) | May 27, 2024 |
| HP            | 15 Notebook PC              | [640586659d](https://linux-hardware.org/?probe=640586659d) | May 24, 2024 |
| HP            | 15 Notebook PC              | [174405df46](https://linux-hardware.org/?probe=174405df46) | May 24, 2024 |
| Apple         | MacBookPro8,2               | [2919242003](https://linux-hardware.org/?probe=2919242003) | May 23, 2024 |
| HP            | ProBook 450 G3              | [5a3bf3b0e5](https://linux-hardware.org/?probe=5a3bf3b0e5) | May 23, 2024 |
| Apple         | MacBookPro5,3               | [67d2c0a830](https://linux-hardware.org/?probe=67d2c0a830) | May 23, 2024 |
| Apple         | MacBookPro5,3               | [8789f1352d](https://linux-hardware.org/?probe=8789f1352d) | May 23, 2024 |
| Dell          | Inspiron 3442               | [3fa98588d7](https://linux-hardware.org/?probe=3fa98588d7) | May 20, 2024 |
| HP            | ProBook 440 G8 Notebook ... | [e010a46aaa](https://linux-hardware.org/?probe=e010a46aaa) | May 20, 2024 |
| Apple         | MacBookPro9,1               | [81ca91875c](https://linux-hardware.org/?probe=81ca91875c) | May 19, 2024 |
| Apple         | MacBookPro9,1               | [9af9e45749](https://linux-hardware.org/?probe=9af9e45749) | May 19, 2024 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [ef53a24225](https://linux-hardware.org/?probe=ef53a24225) | May 19, 2024 |
| Lenovo        | U41-70 80JV                 | [5570ce9cbf](https://linux-hardware.org/?probe=5570ce9cbf) | May 18, 2024 |
| HP            | Compaq 6730b (KE717AV)      | [3832c9ecea](https://linux-hardware.org/?probe=3832c9ecea) | May 14, 2024 |
| HP            | Victus by Gaming Laptop ... | [2b749bf5c4](https://linux-hardware.org/?probe=2b749bf5c4) | May 14, 2024 |
| HP            | Pavilion 17                 | [1a80d822d4](https://linux-hardware.org/?probe=1a80d822d4) | May 14, 2024 |
| HP            | Pavilion g4                 | [e4d725eba3](https://linux-hardware.org/?probe=e4d725eba3) | May 11, 2024 |
| Apple         | MacBookPro9,2               | [5b949515c2](https://linux-hardware.org/?probe=5b949515c2) | May 11, 2024 |
| Dell          | Latitude E6320              | [3d34ee9056](https://linux-hardware.org/?probe=3d34ee9056) | May 10, 2024 |
| Dell          | Inspiron 3481               | [78cf24846f](https://linux-hardware.org/?probe=78cf24846f) | May 09, 2024 |
| Packard Be... | EasyNote LM81               | [0ea4d18648](https://linux-hardware.org/?probe=0ea4d18648) | May 06, 2024 |
| Samsung       | 550XDA                      | [1ea7dfb8ae](https://linux-hardware.org/?probe=1ea7dfb8ae) | May 06, 2024 |
| Apple         | MacBookPro11,4              | [3c0f7c8c00](https://linux-hardware.org/?probe=3c0f7c8c00) | May 06, 2024 |
| HP            | EliteBook 830 G5            | [7ad59bc402](https://linux-hardware.org/?probe=7ad59bc402) | May 05, 2024 |
| HP            | EliteBook 830 G5            | [a88155be11](https://linux-hardware.org/?probe=a88155be11) | May 05, 2024 |
| Lenovo        | IdeaPad S340-14API 81NB     | [80f71c25c1](https://linux-hardware.org/?probe=80f71c25c1) | May 05, 2024 |
| Apple         | MacBookAir4,1               | [2e67b6ba22](https://linux-hardware.org/?probe=2e67b6ba22) | May 04, 2024 |
| Lenovo        | ThinkPad T530 2429HR5       | [c5640e6fae](https://linux-hardware.org/?probe=c5640e6fae) | May 04, 2024 |
| Dell          | Latitude 5490               | [b31473028c](https://linux-hardware.org/?probe=b31473028c) | May 04, 2024 |
| Packard Be... | EasyNote LM81               | [44ead9f439](https://linux-hardware.org/?probe=44ead9f439) | May 03, 2024 |
| Google        | Nospike                     | [549d690ae1](https://linux-hardware.org/?probe=549d690ae1) | May 02, 2024 |
| Dell          | Latitude 5490               | [c83e9f5562](https://linux-hardware.org/?probe=c83e9f5562) | May 01, 2024 |
| Lenovo        | IdeaPad P400 Touch 20211    | [cacd80cba3](https://linux-hardware.org/?probe=cacd80cba3) | May 01, 2024 |
| HP            | ProBook 470 G5              | [8ba873e85d](https://linux-hardware.org/?probe=8ba873e85d) | Apr 30, 2024 |
| MSI           | GT62VR 6RE                  | [b7768b7ee9](https://linux-hardware.org/?probe=b7768b7ee9) | Apr 28, 2024 |
| HP            | EliteBook 8440p             | [0dbed15c85](https://linux-hardware.org/?probe=0dbed15c85) | Apr 27, 2024 |
| HUAWEI        | KPL-W0X                     | [0ce65136da](https://linux-hardware.org/?probe=0ce65136da) | Apr 27, 2024 |
| Apple         | MacBook5,1                  | [8da3b01d13](https://linux-hardware.org/?probe=8da3b01d13) | Apr 26, 2024 |
| HP            | EliteBook 745 G4            | [f38a6451f0](https://linux-hardware.org/?probe=f38a6451f0) | Apr 24, 2024 |
| HP            | Pavilion dv6                | [c8d73c3a23](https://linux-hardware.org/?probe=c8d73c3a23) | Apr 24, 2024 |
| HP            | Pavilion dv6                | [08f01fc7ed](https://linux-hardware.org/?probe=08f01fc7ed) | Apr 24, 2024 |
| Acer          | Aspire A515-43              | [ff74a6262e](https://linux-hardware.org/?probe=ff74a6262e) | Apr 23, 2024 |
| Apple         | MacBookAir7,2               | [674850b624](https://linux-hardware.org/?probe=674850b624) | Apr 23, 2024 |
| Unknown       | Unknown                     | [def20611a4](https://linux-hardware.org/?probe=def20611a4) | Apr 23, 2024 |
| Apple         | MacBookAir7,2               | [c7cbc009ef](https://linux-hardware.org/?probe=c7cbc009ef) | Apr 23, 2024 |
| Acer          | Aspire 5750G                | [39ed7553a3](https://linux-hardware.org/?probe=39ed7553a3) | Apr 23, 2024 |
| TECNO         | MEGABOOK T1                 | [01fc56cf5b](https://linux-hardware.org/?probe=01fc56cf5b) | Apr 22, 2024 |
| Apple         | MacBookPro11,1              | [3f4e9ae066](https://linux-hardware.org/?probe=3f4e9ae066) | Apr 21, 2024 |
| Apple         | MacBookPro11,1              | [e70b7338c2](https://linux-hardware.org/?probe=e70b7338c2) | Apr 21, 2024 |
| Acer          | Aspire 5750                 | [9e2621b213](https://linux-hardware.org/?probe=9e2621b213) | Apr 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [8740fd113c](https://linux-hardware.org/?probe=8740fd113c) | Apr 19, 2024 |
| HP            | Pavilion Notebook           | [8b925ca8f0](https://linux-hardware.org/?probe=8b925ca8f0) | Apr 19, 2024 |
| ASUSTek       | K42F                        | [d127923f98](https://linux-hardware.org/?probe=d127923f98) | Apr 17, 2024 |
| HP            | Pavilion x2 Detachable      | [9e5556a266](https://linux-hardware.org/?probe=9e5556a266) | Apr 17, 2024 |
| Apple         | MacBookPro16,1              | [40fd2c63cb](https://linux-hardware.org/?probe=40fd2c63cb) | Apr 16, 2024 |
| DEPO Compu... | W25CEW                      | [6653a2975d](https://linux-hardware.org/?probe=6653a2975d) | Apr 15, 2024 |
| Apple         | MacBookAir7,1               | [c1be5d2dd6](https://linux-hardware.org/?probe=c1be5d2dd6) | Apr 14, 2024 |
| Apple         | MacBookPro9,2               | [5a62c14a1f](https://linux-hardware.org/?probe=5a62c14a1f) | Apr 14, 2024 |
| Apple         | MacBookPro9,2               | [97f0209510](https://linux-hardware.org/?probe=97f0209510) | Apr 14, 2024 |
| Acer          | Aspire 6935                 | [d26ee0494f](https://linux-hardware.org/?probe=d26ee0494f) | Apr 13, 2024 |
| Apple         | MacBookPro8,2               | [e57c02860c](https://linux-hardware.org/?probe=e57c02860c) | Apr 13, 2024 |
| Acer          | Aspire 5750                 | [f64263bd19](https://linux-hardware.org/?probe=f64263bd19) | Apr 12, 2024 |
| Apple         | MacBookAir7,2               | [569f9614a5](https://linux-hardware.org/?probe=569f9614a5) | Apr 12, 2024 |
| HP            | ProBook 6360b               | [81b9d0706b](https://linux-hardware.org/?probe=81b9d0706b) | Apr 11, 2024 |
| Apple         | MacBookPro8,2               | [461d5dfd8d](https://linux-hardware.org/?probe=461d5dfd8d) | Apr 11, 2024 |
| Lenovo        | ThinkPad E480 20KN003TUS    | [35b206d8f8](https://linux-hardware.org/?probe=35b206d8f8) | Apr 10, 2024 |
| HP            | EliteBook 745 G4            | [0d92302707](https://linux-hardware.org/?probe=0d92302707) | Apr 09, 2024 |
| Apple         | MacBookPro8,1               | [ac137b7cb7](https://linux-hardware.org/?probe=ac137b7cb7) | Apr 09, 2024 |
| Apple         | MacBookPro8,1               | [e964beb301](https://linux-hardware.org/?probe=e964beb301) | Apr 09, 2024 |
| Apple         | MacBookPro5,4               | [3ab1d66e10](https://linux-hardware.org/?probe=3ab1d66e10) | Apr 08, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | [9099f440bc](https://linux-hardware.org/?probe=9099f440bc) | Apr 08, 2024 |
| Apple         | MacBookPro8,1               | [7efef6a0ae](https://linux-hardware.org/?probe=7efef6a0ae) | Apr 07, 2024 |
| Apple         | MacBookPro8,1               | [d28398beb7](https://linux-hardware.org/?probe=d28398beb7) | Apr 07, 2024 |
| Dell          | XPS 15 9570                 | [ccdb5dcad9](https://linux-hardware.org/?probe=ccdb5dcad9) | Apr 07, 2024 |
| Apple         | MacBookPro9,2               | [a90b694613](https://linux-hardware.org/?probe=a90b694613) | Apr 06, 2024 |
| Acer          | Aspire 5750                 | [27d64e5b3c](https://linux-hardware.org/?probe=27d64e5b3c) | Apr 05, 2024 |
| Apple         | MacBookPro8,1               | [733d6c6e2b](https://linux-hardware.org/?probe=733d6c6e2b) | Apr 05, 2024 |
| Lenovo        | ThinkPad E480 20KN003TUS    | [3d64dfc3a9](https://linux-hardware.org/?probe=3d64dfc3a9) | Apr 04, 2024 |
| Acer          | Aspire 5750                 | [e2cef27ef8](https://linux-hardware.org/?probe=e2cef27ef8) | Apr 03, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9bc584b914](https://linux-hardware.org/?probe=9bc584b914) | Apr 03, 2024 |
| Toshiba       | Satellite L10W-B-101        | [eaa5927086](https://linux-hardware.org/?probe=eaa5927086) | Apr 03, 2024 |
| HP            | Pavilion dv7                | [483e1957a4](https://linux-hardware.org/?probe=483e1957a4) | Apr 02, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [fe5490324f](https://linux-hardware.org/?probe=fe5490324f) | Apr 01, 2024 |
| Medion        | E6217                       | [c2ca377a05](https://linux-hardware.org/?probe=c2ca377a05) | Mar 31, 2024 |
| HP            | Pavilion dv7                | [a86e8cccf5](https://linux-hardware.org/?probe=a86e8cccf5) | Mar 31, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b68181d354](https://linux-hardware.org/?probe=b68181d354) | Mar 29, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [5b4456a2d6](https://linux-hardware.org/?probe=5b4456a2d6) | Mar 29, 2024 |
| Dell          | Inspiron 5423               | [0c6c4c6a58](https://linux-hardware.org/?probe=0c6c4c6a58) | Mar 29, 2024 |
| Lenovo        | ThinkPad W500 40623CG       | [71c868292f](https://linux-hardware.org/?probe=71c868292f) | Mar 27, 2024 |
| Lenovo        | ThinkPad W500 40623CG       | [01d1ef9c31](https://linux-hardware.org/?probe=01d1ef9c31) | Mar 26, 2024 |
| Lenovo        | ThinkPad T410 2537CQ7       | [8b91ec68dd](https://linux-hardware.org/?probe=8b91ec68dd) | Mar 26, 2024 |
| Lenovo        | ThinkPad T450s 20BX0011G... | [3e86099c28](https://linux-hardware.org/?probe=3e86099c28) | Mar 26, 2024 |
| Lenovo        | ThinkPad T450s 20BX0011G... | [598015ca49](https://linux-hardware.org/?probe=598015ca49) | Mar 24, 2024 |
| Samsung       | 535U3C                      | [6b29450ac6](https://linux-hardware.org/?probe=6b29450ac6) | Mar 23, 2024 |
| HUAWEI        | BOM-WXX9                    | [20d2290d1c](https://linux-hardware.org/?probe=20d2290d1c) | Mar 23, 2024 |
| HUAWEI        | NBLB-WAX9N                  | [e5c5d49216](https://linux-hardware.org/?probe=e5c5d49216) | Mar 22, 2024 |
| HP            | ProBook 450 G3              | [a32e851ddd](https://linux-hardware.org/?probe=a32e851ddd) | Mar 21, 2024 |
| HP            | ENVY 17                     | [0ee4da384d](https://linux-hardware.org/?probe=0ee4da384d) | Mar 20, 2024 |
| MSI           | GE70 2QE                    | [31b45c6de7](https://linux-hardware.org/?probe=31b45c6de7) | Mar 17, 2024 |
| HP            | Laptop 17-by3xxx            | [430290e97d](https://linux-hardware.org/?probe=430290e97d) | Mar 17, 2024 |
| Dell          | Latitude E6420              | [dc953135d3](https://linux-hardware.org/?probe=dc953135d3) | Mar 16, 2024 |
| Dell          | Latitude E7240              | [d159f296d4](https://linux-hardware.org/?probe=d159f296d4) | Mar 16, 2024 |
| ASUSTek       | X541UAK                     | [4b33512569](https://linux-hardware.org/?probe=4b33512569) | Mar 16, 2024 |
| Dell          | Latitude E7470              | [4addfb5619](https://linux-hardware.org/?probe=4addfb5619) | Mar 14, 2024 |
| Dell          | Latitude E7470              | [fbf1fe3963](https://linux-hardware.org/?probe=fbf1fe3963) | Mar 14, 2024 |
| Acer          | Aspire E5-573G              | [36653be57c](https://linux-hardware.org/?probe=36653be57c) | Mar 13, 2024 |
| ASUSTek       | X555LAB                     | [8b2310099c](https://linux-hardware.org/?probe=8b2310099c) | Mar 13, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | [cfb2591a20](https://linux-hardware.org/?probe=cfb2591a20) | Mar 12, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | [9160e106f1](https://linux-hardware.org/?probe=9160e106f1) | Mar 12, 2024 |
| Apple         | MacBookAir7,2               | [89b268f1f8](https://linux-hardware.org/?probe=89b268f1f8) | Mar 11, 2024 |
| HP            | Pavilion Laptop 15-cs0xx... | [22f1633f40](https://linux-hardware.org/?probe=22f1633f40) | Mar 09, 2024 |
| ASUSTek       | X541UAK                     | [8b527dc9c9](https://linux-hardware.org/?probe=8b527dc9c9) | Mar 09, 2024 |
| HP            | ENVY Notebook               | [6ab7868737](https://linux-hardware.org/?probe=6ab7868737) | Mar 08, 2024 |
| Apple         | MacBookPro11,2              | [486387c7ef](https://linux-hardware.org/?probe=486387c7ef) | Mar 08, 2024 |
| Apple         | MacBookAir7,2               | [f701ce67f5](https://linux-hardware.org/?probe=f701ce67f5) | Mar 07, 2024 |
| Apple         | MacBookAir7,2               | [4c046066f7](https://linux-hardware.org/?probe=4c046066f7) | Mar 05, 2024 |
| Lenovo        | ThinkPad X250 20CLS3NA00    | [ecea244114](https://linux-hardware.org/?probe=ecea244114) | Mar 03, 2024 |
| Unknown       | Unknown                     | [2ca2d631cc](https://linux-hardware.org/?probe=2ca2d631cc) | Mar 02, 2024 |
| HP            | ENVY Laptop 13-ad1xx        | [d7d8cc5cc7](https://linux-hardware.org/?probe=d7d8cc5cc7) | Mar 02, 2024 |
| HP            | ProBook 4540s               | [46cdfe37d6](https://linux-hardware.org/?probe=46cdfe37d6) | Mar 02, 2024 |
| HP            | ProBook 4540s               | [ec5752452f](https://linux-hardware.org/?probe=ec5752452f) | Mar 02, 2024 |
| HP            | 250 G8 Notebook PC          | [bcac46fe58](https://linux-hardware.org/?probe=bcac46fe58) | Mar 01, 2024 |
| Apple         | MacBookPro5,4               | [681e76d909](https://linux-hardware.org/?probe=681e76d909) | Feb 29, 2024 |
| Apple         | MacBookPro5,4               | [ca45519759](https://linux-hardware.org/?probe=ca45519759) | Feb 29, 2024 |
| UNOWHY        | Y13G011S4EI                 | [f785899192](https://linux-hardware.org/?probe=f785899192) | Feb 29, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [11a760c545](https://linux-hardware.org/?probe=11a760c545) | Feb 28, 2024 |
| HP            | 15                          | [6fb113d856](https://linux-hardware.org/?probe=6fb113d856) | Feb 28, 2024 |
| Dell          | Inspiron 5567               | [9a57de6e15](https://linux-hardware.org/?probe=9a57de6e15) | Feb 27, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [49ac7f8a77](https://linux-hardware.org/?probe=49ac7f8a77) | Feb 27, 2024 |
| Apple         | MacBookPro9,2               | [7167de20ce](https://linux-hardware.org/?probe=7167de20ce) | Feb 27, 2024 |
| Lenovo        | V15 G1 IML 82NB             | [b51e9d56f2](https://linux-hardware.org/?probe=b51e9d56f2) | Feb 27, 2024 |
| HUAWEI        | KLVL-WXX9                   | [b1c31d32ab](https://linux-hardware.org/?probe=b1c31d32ab) | Feb 27, 2024 |
| ASUSTek       | X441UA                      | [1185900ace](https://linux-hardware.org/?probe=1185900ace) | Feb 26, 2024 |
| Lenovo        | IdeaPad S400 Touch VIUS3    | [61e571e08f](https://linux-hardware.org/?probe=61e571e08f) | Feb 26, 2024 |
| Acer          | TravelMate P256-MG          | [abcfd5362f](https://linux-hardware.org/?probe=abcfd5362f) | Feb 25, 2024 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [ca33f4c1c6](https://linux-hardware.org/?probe=ca33f4c1c6) | Feb 25, 2024 |
| HP            | Pavilion Laptop 15-cd0xx    | [6d31b35e19](https://linux-hardware.org/?probe=6d31b35e19) | Feb 25, 2024 |
| Apple         | MacBook5,1                  | [be026cabc8](https://linux-hardware.org/?probe=be026cabc8) | Feb 24, 2024 |
| Acer          | Swift SF314-43              | [56b060901d](https://linux-hardware.org/?probe=56b060901d) | Feb 23, 2024 |
| HP            | Pavilion Laptop 15-cd0xx    | [83bf2661f0](https://linux-hardware.org/?probe=83bf2661f0) | Feb 23, 2024 |
| Apple         | MacBookAir7,2               | [627c4721b6](https://linux-hardware.org/?probe=627c4721b6) | Feb 21, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | [96fb9606bf](https://linux-hardware.org/?probe=96fb9606bf) | Feb 20, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | [520188b3c6](https://linux-hardware.org/?probe=520188b3c6) | Feb 20, 2024 |
| HP            | ProBook 450 G1              | [ba02f5d2ae](https://linux-hardware.org/?probe=ba02f5d2ae) | Feb 18, 2024 |
| Slimbook      | Essential 14                | [05c319f707](https://linux-hardware.org/?probe=05c319f707) | Feb 18, 2024 |
| Apple         | MacBookAir6,1               | [f11ff820e7](https://linux-hardware.org/?probe=f11ff820e7) | Feb 18, 2024 |
| HP            | ProBook 430 G2              | [a4b236fd41](https://linux-hardware.org/?probe=a4b236fd41) | Feb 17, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [b5bad706ef](https://linux-hardware.org/?probe=b5bad706ef) | Feb 15, 2024 |
| HP            | 245 G8                      | [c66563da68](https://linux-hardware.org/?probe=c66563da68) | Feb 14, 2024 |
| Dell          | Vostro 1540                 | [ed9ed14ad8](https://linux-hardware.org/?probe=ed9ed14ad8) | Feb 14, 2024 |
| HP            | ZBook 15                    | [bcb41f3b4c](https://linux-hardware.org/?probe=bcb41f3b4c) | Feb 14, 2024 |
| MSI           | GF72VR 7RF                  | [8fb108b426](https://linux-hardware.org/?probe=8fb108b426) | Feb 13, 2024 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [d1856c355f](https://linux-hardware.org/?probe=d1856c355f) | Feb 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [498af1a9a2](https://linux-hardware.org/?probe=498af1a9a2) | Feb 06, 2024 |
| Teclast       | F7                          | [04b33deb97](https://linux-hardware.org/?probe=04b33deb97) | Feb 04, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [fdc21a05c2](https://linux-hardware.org/?probe=fdc21a05c2) | Feb 02, 2024 |
| Acer          | AOD255                      | [43304c651c](https://linux-hardware.org/?probe=43304c651c) | Feb 01, 2024 |
| HUAWEI        | BOD-WXX9                    | [d1a7f0cddb](https://linux-hardware.org/?probe=d1a7f0cddb) | Jan 31, 2024 |
| HP            | Pavilion g6                 | [acd0ae9c04](https://linux-hardware.org/?probe=acd0ae9c04) | Jan 31, 2024 |
| Apple         | MacBookPro7,1               | [973c263365](https://linux-hardware.org/?probe=973c263365) | Jan 30, 2024 |
| Fujitsu       | LIFEBOOK E734               | [7b3a60ae2d](https://linux-hardware.org/?probe=7b3a60ae2d) | Jan 30, 2024 |
| Acer          | Aspire E5-571               | [6ebe6ae5be](https://linux-hardware.org/?probe=6ebe6ae5be) | Jan 28, 2024 |
| Lenovo        | ThinkPad L440 20AT0030MD    | [1c0f2e8a2f](https://linux-hardware.org/?probe=1c0f2e8a2f) | Jan 26, 2024 |
| Dell          | Latitude E7240              | [d8e5d4a8da](https://linux-hardware.org/?probe=d8e5d4a8da) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [81338699ce](https://linux-hardware.org/?probe=81338699ce) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [9f021a2102](https://linux-hardware.org/?probe=9f021a2102) | Jan 25, 2024 |
| Samsung       | RC410/RC510/RC710           | [34369cc7eb](https://linux-hardware.org/?probe=34369cc7eb) | Jan 25, 2024 |
| Samsung       | RC410/RC510/RC710           | [d48bdbaec0](https://linux-hardware.org/?probe=d48bdbaec0) | Jan 24, 2024 |
| Acer          | Aspire E5-573G              | [14eec10d5e](https://linux-hardware.org/?probe=14eec10d5e) | Jan 24, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [3361cf9ae9](https://linux-hardware.org/?probe=3361cf9ae9) | Jan 23, 2024 |
| Lenovo        | V17 G2 ITL 82NX             | [40f906871e](https://linux-hardware.org/?probe=40f906871e) | Jan 22, 2024 |
| Lenovo        | ThinkPad T480 20L6S3ED18    | [63d8796a60](https://linux-hardware.org/?probe=63d8796a60) | Jan 20, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [86d22c9b40](https://linux-hardware.org/?probe=86d22c9b40) | Jan 17, 2024 |
| Apple         | MacBook6,1                  | [641df770ba](https://linux-hardware.org/?probe=641df770ba) | Jan 17, 2024 |
| Packard Be... | EasyNote TS11HR             | [41076ef28d](https://linux-hardware.org/?probe=41076ef28d) | Jan 14, 2024 |
| Apple         | MacBookPro9,2               | [7cf8b59aee](https://linux-hardware.org/?probe=7cf8b59aee) | Jan 10, 2024 |
| Apple         | MacBook5,1                  | [75835b3764](https://linux-hardware.org/?probe=75835b3764) | Jan 09, 2024 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [c3a6a2da37](https://linux-hardware.org/?probe=c3a6a2da37) | Jan 09, 2024 |
| Apple         | MacBook5,1                  | [3a4a960ff8](https://linux-hardware.org/?probe=3a4a960ff8) | Jan 06, 2024 |
| Apple         | MacBookPro7,1               | [75fc0fa74a](https://linux-hardware.org/?probe=75fc0fa74a) | Jan 06, 2024 |
| TECNO Mobi... | MEGABOOK T14TA              | [deadd2cf3d](https://linux-hardware.org/?probe=deadd2cf3d) | Jan 05, 2024 |
| HP            | Laptop 17-by3xxx            | [32486bf070](https://linux-hardware.org/?probe=32486bf070) | Jan 04, 2024 |
| Dell          | Latitude E7440              | [75ba78537c](https://linux-hardware.org/?probe=75ba78537c) | Jan 03, 2024 |
| Positivo      | C4128A-15                   | [52bd86685b](https://linux-hardware.org/?probe=52bd86685b) | Jan 03, 2024 |
| Medion        | E11202                      | [cb45690620](https://linux-hardware.org/?probe=cb45690620) | Jan 01, 2024 |
| HP            | EliteBook 840 G1            | [9ab6343dd7](https://linux-hardware.org/?probe=9ab6343dd7) | Jan 01, 2024 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [0120368c3a](https://linux-hardware.org/?probe=0120368c3a) | Jan 01, 2024 |
| Positivo      | C4128A-15                   | [6416d967b8](https://linux-hardware.org/?probe=6416d967b8) | Dec 30, 2023 |
| Positivo      | C4128A-15                   | [bd9afc6d73](https://linux-hardware.org/?probe=bd9afc6d73) | Dec 30, 2023 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [a55f917cf6](https://linux-hardware.org/?probe=a55f917cf6) | Dec 29, 2023 |
| Medion        | E11202                      | [9db140d63c](https://linux-hardware.org/?probe=9db140d63c) | Dec 28, 2023 |
| HP            | Laptop 15-dw3xxx            | [76305a2c98](https://linux-hardware.org/?probe=76305a2c98) | Dec 28, 2023 |
| Acer          | Swift SFX14-41G             | [d39de69e1b](https://linux-hardware.org/?probe=d39de69e1b) | Dec 27, 2023 |
| THTF          | WUJIE 14                    | [c402523a2c](https://linux-hardware.org/?probe=c402523a2c) | Dec 25, 2023 |
| THTF          | WUJIE 14                    | [39ee354a27](https://linux-hardware.org/?probe=39ee354a27) | Dec 25, 2023 |
| Medion        | E11202                      | [af0c7baf03](https://linux-hardware.org/?probe=af0c7baf03) | Dec 22, 2023 |
| ASUSTek       | X555LAB                     | [8a8a35c616](https://linux-hardware.org/?probe=8a8a35c616) | Dec 21, 2023 |
| Apple         | MacBook5,1                  | [9839cacb3a](https://linux-hardware.org/?probe=9839cacb3a) | Dec 19, 2023 |
| Apple         | MacBook5,1                  | [8268b72759](https://linux-hardware.org/?probe=8268b72759) | Dec 19, 2023 |
| Acer          | Aspire 4736Z                | [38866fae79](https://linux-hardware.org/?probe=38866fae79) | Dec 17, 2023 |
| Dell          | Precision 7560              | [0f83098df3](https://linux-hardware.org/?probe=0f83098df3) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [abc0a9283d](https://linux-hardware.org/?probe=abc0a9283d) | Dec 14, 2023 |
| ASUSTek       | X75A1                       | [e7d274ca96](https://linux-hardware.org/?probe=e7d274ca96) | Dec 13, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [4d416a35fa](https://linux-hardware.org/?probe=4d416a35fa) | Dec 12, 2023 |
| Sony          | SVE11115ELW                 | [68fa8c6081](https://linux-hardware.org/?probe=68fa8c6081) | Dec 10, 2023 |
| Sony          | SVE11115ELW                 | [567787c7d3](https://linux-hardware.org/?probe=567787c7d3) | Dec 10, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5a75d4827a](https://linux-hardware.org/?probe=5a75d4827a) | Dec 10, 2023 |
| Lenovo        | ThinkPad P51s 20HBCTO1WW    | [4c18329d9d](https://linux-hardware.org/?probe=4c18329d9d) | Dec 09, 2023 |
| HP            | Laptop 15-dw3xxx            | [8167f60069](https://linux-hardware.org/?probe=8167f60069) | Dec 05, 2023 |
| Dell          | Inspiron 15-3552            | [8ca2d01e7c](https://linux-hardware.org/?probe=8ca2d01e7c) | Dec 05, 2023 |
| Acer          | Aspire 4736Z                | [844b16d408](https://linux-hardware.org/?probe=844b16d408) | Dec 03, 2023 |
| HP            | EliteBook 840 G3            | [fa8d37e46b](https://linux-hardware.org/?probe=fa8d37e46b) | Nov 30, 2023 |
| UMAX          | VisionBook 14Wr Plus        | [a0d4963838](https://linux-hardware.org/?probe=a0d4963838) | Nov 28, 2023 |
| HP            | Pavilion dv7                | [c617d0a2d4](https://linux-hardware.org/?probe=c617d0a2d4) | Nov 26, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [cf1e883f11](https://linux-hardware.org/?probe=cf1e883f11) | Nov 25, 2023 |
| Samsung       | RF510/RF410/RF710           | [a642075264](https://linux-hardware.org/?probe=a642075264) | Nov 25, 2023 |
| Dell          | Inspiron N5040              | [3b51468cdf](https://linux-hardware.org/?probe=3b51468cdf) | Nov 24, 2023 |
| Apple         | MacBookPro5,5               | [a2d556bc01](https://linux-hardware.org/?probe=a2d556bc01) | Nov 20, 2023 |
| Apple         | MacBookPro5,5               | [cdc6379993](https://linux-hardware.org/?probe=cdc6379993) | Nov 19, 2023 |
| Apple         | MacBookPro5,5               | [840adf8528](https://linux-hardware.org/?probe=840adf8528) | Nov 19, 2023 |
| HP            | OMEN by Laptop              | [886c5bc9a6](https://linux-hardware.org/?probe=886c5bc9a6) | Nov 19, 2023 |
| HP            | OMEN by Laptop              | [bcd7007cde](https://linux-hardware.org/?probe=bcd7007cde) | Nov 19, 2023 |
| iOTA          | IOTA2320                    | [5c4d630f23](https://linux-hardware.org/?probe=5c4d630f23) | Nov 19, 2023 |
| HP            | Pavilion dv7                | [4c482baa30](https://linux-hardware.org/?probe=4c482baa30) | Nov 18, 2023 |
| HP            | Pavilion dv7                | [e05cf328e2](https://linux-hardware.org/?probe=e05cf328e2) | Nov 18, 2023 |
| Fujitsu       | LIFEBOOK E780               | [d3a64f5368](https://linux-hardware.org/?probe=d3a64f5368) | Nov 16, 2023 |
| Unknown       | Unknown                     | [66296a4edd](https://linux-hardware.org/?probe=66296a4edd) | Nov 12, 2023 |
| Alienware     | 15 R3                       | [c920563c0b](https://linux-hardware.org/?probe=c920563c0b) | Nov 12, 2023 |
| Apple         | MacBookAir6,2               | [3595c8f9d1](https://linux-hardware.org/?probe=3595c8f9d1) | Nov 12, 2023 |
| HP            | 245 G8                      | [0b471d312a](https://linux-hardware.org/?probe=0b471d312a) | Nov 11, 2023 |
| HP            | 245 G8                      | [b29efc88ec](https://linux-hardware.org/?probe=b29efc88ec) | Nov 11, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | [9b881d355c](https://linux-hardware.org/?probe=9b881d355c) | Nov 09, 2023 |
| Dell          | Vostro 3500                 | [860fc63d0d](https://linux-hardware.org/?probe=860fc63d0d) | Nov 09, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [5c39f44ed5](https://linux-hardware.org/?probe=5c39f44ed5) | Nov 08, 2023 |
| Dell          | G7 7500                     | [91adca1093](https://linux-hardware.org/?probe=91adca1093) | Nov 07, 2023 |
| Timi          | Redmi G 2022                | [f8cecbac55](https://linux-hardware.org/?probe=f8cecbac55) | Nov 07, 2023 |
| ASUSTek       | X555LAB                     | [2d3d09097d](https://linux-hardware.org/?probe=2d3d09097d) | Nov 06, 2023 |
| Dell          | G7 7500                     | [3678c5437b](https://linux-hardware.org/?probe=3678c5437b) | Nov 06, 2023 |
| Apple         | MacBookPro11,1              | [2d84377719](https://linux-hardware.org/?probe=2d84377719) | Nov 06, 2023 |
| HP            | 245 G8                      | [e9c1cc78b8](https://linux-hardware.org/?probe=e9c1cc78b8) | Nov 06, 2023 |
| HP            | Spectre Pro G1              | [78bce56071](https://linux-hardware.org/?probe=78bce56071) | Nov 05, 2023 |
| HP            | ProBook 6545b               | [a81427fffa](https://linux-hardware.org/?probe=a81427fffa) | Nov 05, 2023 |
| Acer          | Aspire E5-551G              | [f8e737dbde](https://linux-hardware.org/?probe=f8e737dbde) | Nov 03, 2023 |
| HONOR         | NMH-WDX9                    | [11e32e2482](https://linux-hardware.org/?probe=11e32e2482) | Nov 03, 2023 |
| Alienware     | 14                          | [3d3be9ce75](https://linux-hardware.org/?probe=3d3be9ce75) | Nov 01, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [e25974d32d](https://linux-hardware.org/?probe=e25974d32d) | Oct 31, 2023 |
| Dell          | Inspiron 1545               | [5a1d90c1a7](https://linux-hardware.org/?probe=5a1d90c1a7) | Oct 30, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [300d56f39e](https://linux-hardware.org/?probe=300d56f39e) | Oct 29, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [29a362f501](https://linux-hardware.org/?probe=29a362f501) | Oct 29, 2023 |
| Apple         | MacBook7,1                  | [61b133ac1e](https://linux-hardware.org/?probe=61b133ac1e) | Oct 27, 2023 |
| Dell          | Latitude E6520              | [dbbca588de](https://linux-hardware.org/?probe=dbbca588de) | Oct 26, 2023 |
| ASUSTek       | X555LAB                     | [a8b1ad0f53](https://linux-hardware.org/?probe=a8b1ad0f53) | Oct 25, 2023 |
| Dell          | Vostro 15 3515              | [5713b2f30e](https://linux-hardware.org/?probe=5713b2f30e) | Oct 24, 2023 |
| Dell          | Latitude E6400              | [250c9ddcfe](https://linux-hardware.org/?probe=250c9ddcfe) | Oct 24, 2023 |
| Apple         | MacBookPro6,2               | [89f29afb19](https://linux-hardware.org/?probe=89f29afb19) | Oct 24, 2023 |
| Dell          | Latitude E6400              | [6a3537c763](https://linux-hardware.org/?probe=6a3537c763) | Oct 23, 2023 |
| Dell          | Latitude E6520              | [c2fd0014ab](https://linux-hardware.org/?probe=c2fd0014ab) | Oct 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3431e88cbe](https://linux-hardware.org/?probe=3431e88cbe) | Oct 22, 2023 |
| Google        | Cave                        | [287887d308](https://linux-hardware.org/?probe=287887d308) | Oct 20, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [b11aafb048](https://linux-hardware.org/?probe=b11aafb048) | Oct 20, 2023 |
| HP            | Pavilion 17                 | [855c6109eb](https://linux-hardware.org/?probe=855c6109eb) | Oct 20, 2023 |
| HP            | Pavilion dv7                | [13b6b396e9](https://linux-hardware.org/?probe=13b6b396e9) | Oct 18, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Elementary/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Elementary 6.1   | 474       | 26.39%  |
| Elementary 7.1   | 412       | 22.94%  |
| Elementary 8     | 293       | 16.31%  |
| Elementary 7     | 158       | 8.8%    |
| Elementary 5.1.7 | 156       | 8.69%   |
| Elementary 6     | 144       | 8.02%   |
| Elementary 5.0   | 34        | 1.89%   |
| Elementary 5.1.6 | 29        | 1.61%   |
| Elementary 5.1   | 25        | 1.39%   |
| Elementary 5.1.4 | 23        | 1.28%   |
| Elementary 5.1.2 | 16        | 0.89%   |
| Elementary 5.1.3 | 12        | 0.67%   |
| Elementary 5.1.5 | 8         | 0.45%   |
| Elementary 0.4.1 | 8         | 0.45%   |
| Elementary 6.0   | 4         | 0.22%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Elementary | 1743      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.11.0-43-generic | 89        | 4.62%   |
| 6.2.0-33-generic  | 79        | 4.1%    |
| 5.15.0-58-generic | 57        | 2.96%   |
| 6.8.0-51-generic  | 52        | 2.7%    |
| 6.8.0-49-generic  | 47        | 2.44%   |
| 6.11.0-19-generic | 46        | 2.39%   |
| 6.8.0-40-generic  | 39        | 2.02%   |
| 5.15.0-46-generic | 32        | 1.66%   |
| 5.13.0-28-generic | 32        | 1.66%   |
| 5.11.0-40-generic | 32        | 1.66%   |
| 5.11.0-41-generic | 28        | 1.45%   |
| 6.5.0-41-generic  | 27        | 1.4%    |
| 6.5.0-35-generic  | 27        | 1.4%    |
| 6.14.0-29-generic | 27        | 1.4%    |
| 5.15.0-56-generic | 27        | 1.4%    |
| 5.13.0-30-generic | 27        | 1.4%    |
| 5.11.0-27-generic | 27        | 1.4%    |
| 6.11.0-26-generic | 25        | 1.3%    |
| 6.5.0-28-generic  | 24        | 1.24%   |
| 5.13.0-27-generic | 24        | 1.24%   |
| 6.8.0-45-generic  | 21        | 1.09%   |
| 5.4.0-42-generic  | 21        | 1.09%   |
| 5.3.0-62-generic  | 19        | 0.99%   |
| 5.15.0-52-generic | 19        | 0.99%   |
| 5.15.0-48-generic | 19        | 0.99%   |
| 5.15.0-41-generic | 19        | 0.99%   |
| 5.11.0-38-generic | 19        | 0.99%   |
| 5.19.0-41-generic | 18        | 0.93%   |
| 6.8.0-48-generic  | 17        | 0.88%   |
| 6.8.0-47-generic  | 17        | 0.88%   |
| 5.13.0-40-generic | 17        | 0.88%   |
| 5.13.0-39-generic | 17        | 0.88%   |
| 6.2.0-26-generic  | 16        | 0.83%   |
| 5.19.0-35-generic | 16        | 0.83%   |
| 5.11.0-37-generic | 16        | 0.83%   |
| 5.19.0-46-generic | 15        | 0.78%   |
| 6.14.0-36-generic | 14        | 0.73%   |
| 6.11.0-25-generic | 14        | 0.73%   |
| 5.11.0-44-generic | 14        | 0.73%   |
| 6.8.0-52-generic  | 13        | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 252       | 13.76%  |
| 5.15.0  | 227       | 12.39%  |
| 6.8.0   | 213       | 11.63%  |
| 5.13.0  | 173       | 9.44%   |
| 6.5.0   | 165       | 9.01%   |
| 6.2.0   | 146       | 7.97%   |
| 5.4.0   | 141       | 7.7%    |
| 6.11.0  | 129       | 7.04%   |
| 5.19.0  | 89        | 4.86%   |
| 6.14.0  | 88        | 4.8%    |
| 5.3.0   | 77        | 4.2%    |
| 4.15.0  | 60        | 3.28%   |
| 5.0.0   | 15        | 0.82%   |
| 5.8.0   | 8         | 0.44%   |
| 5.10.0  | 3         | 0.16%   |
| 4.13.0  | 3         | 0.16%   |
| 5.14.0  | 2         | 0.11%   |
| 6.7.3   | 1         | 0.05%   |
| 6.5.7   | 1         | 0.05%   |
| 6.5.5   | 1         | 0.05%   |
| 6.3.13  | 1         | 0.05%   |
| 6.2.7   | 1         | 0.05%   |
| 6.16.0  | 1         | 0.05%   |
| 6.13.6  | 1         | 0.05%   |
| 6.1.9   | 1         | 0.05%   |
| 6.1.6   | 1         | 0.05%   |
| 6.1.0   | 1         | 0.05%   |
| 6.0.0   | 1         | 0.05%   |
| 5.9.1   | 1         | 0.05%   |
| 5.8.5   | 1         | 0.05%   |
| 5.8.13  | 1         | 0.05%   |
| 5.6.2   | 1         | 0.05%   |
| 5.6.19  | 1         | 0.05%   |
| 5.6.14  | 1         | 0.05%   |
| 5.5.8   | 1         | 0.05%   |
| 5.5.6   | 1         | 0.05%   |
| 5.4.1   | 1         | 0.05%   |
| 5.3.6   | 1         | 0.05%   |
| 5.3.11  | 1         | 0.05%   |
| 5.19.3  | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 252       | 13.78%  |
| 5.15    | 234       | 12.79%  |
| 6.8     | 213       | 11.65%  |
| 5.13    | 173       | 9.46%   |
| 6.5     | 167       | 9.13%   |
| 6.2     | 147       | 8.04%   |
| 5.4     | 142       | 7.76%   |
| 6.11    | 129       | 7.05%   |
| 5.19    | 92        | 5.03%   |
| 6.14    | 88        | 4.81%   |
| 5.3     | 79        | 4.32%   |
| 4.15    | 60        | 3.28%   |
| 5.0     | 15        | 0.82%   |
| 5.8     | 10        | 0.55%   |
| 5.14    | 5         | 0.27%   |
| 5.10    | 4         | 0.22%   |
| 6.1     | 3         | 0.16%   |
| 4.13    | 3         | 0.16%   |
| 5.5     | 2         | 0.11%   |
| 5.16    | 2         | 0.11%   |
| 6.7     | 1         | 0.05%   |
| 6.3     | 1         | 0.05%   |
| 6.16    | 1         | 0.05%   |
| 6.13    | 1         | 0.05%   |
| 6.0     | 1         | 0.05%   |
| 5.9     | 1         | 0.05%   |
| 5.6     | 1         | 0.05%   |
| 5.18    | 1         | 0.05%   |
| 4.10    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1743      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Pantheon      | 1669      | 95.15%  |
| Unknown       | 65        | 3.71%   |
| GNOME         | 9         | 0.51%   |
| X-Cinnamon    | 4         | 0.23%   |
| KDE5          | 3         | 0.17%   |
| XFCE          | 1         | 0.06%   |
| Unity         | 1         | 0.06%   |
| GNOME Classic | 1         | 0.06%   |
| Budgie        | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1683      | 96.39%  |
| Wayland | 62        | 3.55%   |
| Unknown | 1         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1444      | 82.09%  |
| LightDM | 261       | 14.84%  |
| TDM     | 49        | 2.79%   |
| GDM     | 4         | 0.23%   |
| SDDM    | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 732       | 41.76%  |
| de_DE   | 199       | 11.35%  |
| es_ES   | 135       | 7.7%    |
| ru_RU   | 111       | 6.33%   |
| pt_BR   | 73        | 4.16%   |
| fr_FR   | 68        | 3.88%   |
| en_GB   | 67        | 3.82%   |
| it_IT   | 63        | 3.59%   |
| pl_PL   | 41        | 2.34%   |
| Unknown | 34        | 1.94%   |
| en_AU   | 23        | 1.31%   |
| nl_NL   | 22        | 1.25%   |
| en_CA   | 19        | 1.08%   |
| tr_TR   | 17        | 0.97%   |
| pt_PT   | 14        | 0.8%    |
| hu_HU   | 12        | 0.68%   |
| nb_NO   | 9         | 0.51%   |
| en_IN   | 9         | 0.51%   |
| cs_CZ   | 9         | 0.51%   |
| sv_SE   | 7         | 0.4%    |
| id_ID   | 7         | 0.4%    |
| zh_CN   | 6         | 0.34%   |
| uk_UA   | 6         | 0.34%   |
| de_CH   | 6         | 0.34%   |
| es_MX   | 5         | 0.29%   |
| el_GR   | 5         | 0.29%   |
| da_DK   | 5         | 0.29%   |
| fi_FI   | 4         | 0.23%   |
| bg_BG   | 4         | 0.23%   |
| hr_HR   | 3         | 0.17%   |
| fr_CA   | 3         | 0.17%   |
| es_EC   | 3         | 0.17%   |
| es_AR   | 3         | 0.17%   |
| en_ZA   | 3         | 0.17%   |
| zh_TW   | 2         | 0.11%   |
| vi_VN   | 2         | 0.11%   |
| et_EE   | 2         | 0.11%   |
| es_CL   | 2         | 0.11%   |
| ca_ES   | 2         | 0.11%   |
| C       | 2         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1115      | 63.14%  |
| EFI  | 651       | 36.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1656      | 94.52%  |
| Tmpfs   | 32        | 1.83%   |
| Overlay | 24        | 1.37%   |
| Btrfs   | 21        | 1.2%    |
| Unknown | 12        | 0.68%   |
| Xfs     | 6         | 0.34%   |
| Ext3    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1476      | 83.77%  |
| GPT     | 232       | 13.17%  |
| MBR     | 54        | 3.06%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1702      | 97.65%  |
| Yes       | 41        | 2.35%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1610      | 91.79%  |
| Yes       | 144       | 8.21%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 325       | 18.65%  |
| Hewlett-Packard     | 310       | 17.79%  |
| Apple               | 252       | 14.46%  |
| Dell                | 216       | 12.39%  |
| ASUSTek Computer    | 149       | 8.55%   |
| Acer                | 128       | 7.34%   |
| Toshiba             | 43        | 2.47%   |
| HUAWEI              | 39        | 2.24%   |
| Samsung Electronics | 35        | 2.01%   |
| Sony                | 32        | 1.84%   |
| MSI                 | 23        | 1.32%   |
| Google              | 17        | 0.98%   |
| Fujitsu             | 12        | 0.69%   |
| Unknown             | 11        | 0.63%   |
| Medion              | 9         | 0.52%   |
| Alienware           | 9         | 0.52%   |
| Packard Bell        | 7         | 0.4%    |
| Timi                | 6         | 0.34%   |
| Star Labs           | 6         | 0.34%   |
| Positivo            | 6         | 0.34%   |
| Notebook            | 6         | 0.34%   |
| Chuwi               | 6         | 0.34%   |
| HONOR               | 5         | 0.29%   |
| TUXEDO              | 4         | 0.23%   |
| LG Electronics      | 4         | 0.23%   |
| eMachines           | 4         | 0.23%   |
| Compaq              | 4         | 0.23%   |
| Clevo               | 4         | 0.23%   |
| Razer               | 3         | 0.17%   |
| Panasonic           | 3         | 0.17%   |
| Gigabyte Technology | 3         | 0.17%   |
| Wortmann AG         | 2         | 0.11%   |
| TrekStor            | 2         | 0.11%   |
| Thomson             | 2         | 0.11%   |
| Teclast             | 2         | 0.11%   |
| SLIMBOOK            | 2         | 0.11%   |
| NEC Computers       | 2         | 0.11%   |
| Multilaser          | 2         | 0.11%   |
| Monster             | 2         | 0.11%   |
| GPD                 | 2         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Apple MacBookPro8,1           | 29        | 1.66%   |
| Apple MacBookPro9,2           | 25        | 1.43%   |
| Apple MacBookAir7,2           | 25        | 1.43%   |
| Unknown                       | 15        | 0.86%   |
| HP Notebook                   | 10        | 0.57%   |
| Apple MacBookPro7,1           | 10        | 0.57%   |
| Apple MacBookAir6,2           | 10        | 0.57%   |
| Apple MacBook5,1              | 10        | 0.57%   |
| Apple MacBookPro8,2           | 9         | 0.52%   |
| Apple MacBookPro6,2           | 9         | 0.52%   |
| Apple MacBookPro5,5           | 9         | 0.52%   |
| Apple MacBookPro9,1           | 8         | 0.46%   |
| Apple MacBookPro11,2          | 8         | 0.46%   |
| HP Pavilion g6                | 7         | 0.4%    |
| HP Pavilion dv6               | 7         | 0.4%    |
| HP Pavilion 17                | 7         | 0.4%    |
| Dell Inspiron 15-3567         | 7         | 0.4%    |
| Apple MacBookPro11,1          | 7         | 0.4%    |
| Apple MacBookPro10,1          | 7         | 0.4%    |
| HP Pavilion dv7               | 6         | 0.34%   |
| Apple MacBookAir4,2           | 6         | 0.34%   |
| Apple MacBookAir3,1           | 6         | 0.34%   |
| Apple MacBook4,1              | 6         | 0.34%   |
| Lenovo G50-45 80E3            | 5         | 0.29%   |
| HUAWEI NBLB-WAX9N             | 5         | 0.29%   |
| HUAWEI MACHD-WXX9             | 5         | 0.29%   |
| HP Laptop 15-bw0xx            | 5         | 0.29%   |
| HP EliteBook 840 G3           | 5         | 0.29%   |
| HP 15                         | 5         | 0.29%   |
| Dell Latitude E6400           | 5         | 0.29%   |
| Dell Latitude E5470           | 5         | 0.29%   |
| Dell Inspiron N5110           | 5         | 0.29%   |
| Dell Inspiron 1545            | 5         | 0.29%   |
| ASUS ZenBook UX425EA_UX425EA  | 5         | 0.29%   |
| Apple MacBookPro8,3           | 5         | 0.29%   |
| Apple MacBookPro11,3          | 5         | 0.29%   |
| Star Labs StarBook            | 4         | 0.23%   |
| Lenovo IdeaPad 310-15IKB 80TV | 4         | 0.23%   |
| HUAWEI NBLK-WAX9X             | 4         | 0.23%   |
| HUAWEI BOD-WXX9               | 4         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 143       | 8.2%    |
| Lenovo IdeaPad        | 103       | 5.91%   |
| Acer Aspire           | 94        | 5.39%   |
| Dell Latitude         | 84        | 4.82%   |
| HP Pavilion           | 72        | 4.13%   |
| Dell Inspiron         | 65        | 3.73%   |
| HP ProBook            | 56        | 3.21%   |
| HP Laptop             | 50        | 2.87%   |
| HP EliteBook          | 46        | 2.64%   |
| Apple MacBookPro8     | 43        | 2.47%   |
| Toshiba Satellite     | 34        | 1.95%   |
| Apple MacBookPro9     | 33        | 1.89%   |
| ASUS VivoBook         | 32        | 1.84%   |
| Apple MacBookAir7     | 27        | 1.55%   |
| Apple MacBookPro11    | 26        | 1.49%   |
| Dell XPS              | 24        | 1.38%   |
| Apple MacBookPro5     | 20        | 1.15%   |
| Acer Swift            | 17        | 0.98%   |
| Dell Vostro           | 16        | 0.92%   |
| ASUS ZenBook          | 16        | 0.92%   |
| Unknown               | 15        | 0.86%   |
| Apple MacBookAir6     | 14        | 0.8%    |
| Fujitsu LIFEBOOK      | 12        | 0.69%   |
| Dell Precision        | 12        | 0.69%   |
| Apple MacBook5        | 12        | 0.69%   |
| Apple MacBookPro10    | 11        | 0.63%   |
| Lenovo Legion         | 10        | 0.57%   |
| HP Notebook           | 10        | 0.57%   |
| HP ENVY               | 10        | 0.57%   |
| Apple MacBookPro7     | 10        | 0.57%   |
| Apple MacBookPro6     | 9         | 0.52%   |
| Apple MacBookAir4     | 9         | 0.52%   |
| HP 250                | 8         | 0.46%   |
| Packard Bell EasyNote | 7         | 0.4%    |
| HP 15                 | 7         | 0.4%    |
| ASUS ASUS             | 7         | 0.4%    |
| Apple MacBookAir3     | 7         | 0.4%    |
| Lenovo Yoga           | 6         | 0.34%   |
| HP Compaq             | 6         | 0.34%   |
| HP 255                | 6         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 182       | 10.44%  |
| 2013    | 146       | 8.38%   |
| 2011    | 145       | 8.32%   |
| 2020    | 141       | 8.09%   |
| 2018    | 123       | 7.06%   |
| 2021    | 117       | 6.71%   |
| 2010    | 113       | 6.48%   |
| 2019    | 106       | 6.08%   |
| 2017    | 106       | 6.08%   |
| 2016    | 104       | 5.97%   |
| 2014    | 100       | 5.74%   |
| 2015    | 98        | 5.62%   |
| 2009    | 71        | 4.07%   |
| 2008    | 66        | 3.79%   |
| 2022    | 39        | 2.24%   |
| 2023    | 29        | 1.66%   |
| 2006    | 28        | 1.61%   |
| 2007    | 12        | 0.69%   |
| 2024    | 11        | 0.63%   |
| 2025    | 5         | 0.29%   |
| Unknown | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1743      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1607      | 91.67%  |
| Enabled  | 146       | 8.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1719      | 98.62%  |
| Yes  | 24        | 1.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 623       | 35.38%  |
| 3.01-4.0    | 381       | 21.64%  |
| 16.01-24.0  | 310       | 17.6%   |
| 8.01-16.0   | 276       | 15.67%  |
| 32.01-64.0  | 63        | 3.58%   |
| 1.01-2.0    | 55        | 3.12%   |
| 2.01-3.0    | 24        | 1.36%   |
| 24.01-32.0  | 18        | 1.02%   |
| 64.01-256.0 | 9         | 0.51%   |
| 0.51-1.0    | 2         | 0.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 650       | 34.63%  |
| 1.01-2.0   | 617       | 32.87%  |
| 3.01-4.0   | 302       | 16.09%  |
| 4.01-8.0   | 212       | 11.29%  |
| 0.51-1.0   | 55        | 2.93%   |
| 8.01-16.0  | 38        | 2.02%   |
| 16.01-24.0 | 2         | 0.11%   |
| 24.01-32.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1341      | 75.98%  |
| 2      | 377       | 21.36%  |
| 3      | 28        | 1.59%   |
| 4      | 9         | 0.51%   |
| 0      | 7         | 0.4%    |
| 5      | 3         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1119      | 63.94%  |
| Yes       | 631       | 36.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1347      | 77.24%  |
| No        | 397       | 22.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1715      | 98.34%  |
| No        | 29        | 1.66%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1495      | 85.38%  |
| No        | 256       | 14.62%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 265       | 15.18%  |
| Germany      | 204       | 11.68%  |
| Russia       | 107       | 6.13%   |
| Brazil       | 100       | 5.73%   |
| Italy        | 73        | 4.18%   |
| UK           | 69        | 3.95%   |
| India        | 67        | 3.84%   |
| Spain        | 58        | 3.32%   |
| France       | 58        | 3.32%   |
| Poland       | 47        | 2.69%   |
| Canada       | 44        | 2.52%   |
| Indonesia    | 43        | 2.46%   |
| Mexico       | 40        | 2.29%   |
| Australia    | 37        | 2.12%   |
| Netherlands  | 34        | 1.95%   |
| Turkey       | 28        | 1.6%    |
| Argentina    | 25        | 1.43%   |
| Portugal     | 20        | 1.15%   |
| Austria      | 20        | 1.15%   |
| Chile        | 19        | 1.09%   |
| Belgium      | 18        | 1.03%   |
| Ukraine      | 16        | 0.92%   |
| Hungary      | 16        | 0.92%   |
| Sweden       | 15        | 0.86%   |
| Romania      | 15        | 0.86%   |
| Switzerland  | 14        | 0.8%    |
| Norway       | 14        | 0.8%    |
| Colombia     | 14        | 0.8%    |
| South Africa | 12        | 0.69%   |
| Czechia      | 12        | 0.69%   |
| Finland      | 11        | 0.63%   |
| Greece       | 9         | 0.52%   |
| Bulgaria     | 9         | 0.52%   |
| New Zealand  | 8         | 0.46%   |
| Ireland      | 8         | 0.46%   |
| Thailand     | 7         | 0.4%    |
| Denmark      | 7         | 0.4%    |
| China        | 7         | 0.4%    |
| Vietnam      | 6         | 0.34%   |
| Slovakia     | 6         | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 31        | 1.7%    |
| Berlin            | 19        | 1.04%   |
| Madrid            | 16        | 0.88%   |
| St Petersburg     | 14        | 0.77%   |
| Milan             | 13        | 0.71%   |
| Istanbul          | 13        | 0.71%   |
| Warsaw            | 12        | 0.66%   |
| Vienna            | 12        | 0.66%   |
| Sao Paulo         | 12        | 0.66%   |
| Sydney            | 10        | 0.55%   |
| Rome              | 10        | 0.55%   |
| Munich            | 10        | 0.55%   |
| Jakarta           | 10        | 0.55%   |
| Hamburg           | 10        | 0.55%   |
| Melbourne         | 9         | 0.49%   |
| Delhi             | 9         | 0.49%   |
| Budapest          | 9         | 0.49%   |
| Santiago          | 8         | 0.44%   |
| Perth             | 8         | 0.44%   |
| Paris             | 8         | 0.44%   |
| Stuttgart         | 7         | 0.38%   |
| Rio de Janeiro    | 7         | 0.38%   |
| Los Angeles       | 7         | 0.38%   |
| Córdoba          | 7         | 0.38%   |
| Buenos Aires      | 7         | 0.38%   |
| The Hague         | 6         | 0.33%   |
| Surabaya          | 6         | 0.33%   |
| Oslo              | 6         | 0.33%   |
| Novosibirsk       | 6         | 0.33%   |
| Mexico City       | 6         | 0.33%   |
| Fortaleza         | 6         | 0.33%   |
| Cologne           | 6         | 0.33%   |
| Yekaterinburg     | 5         | 0.27%   |
| Prague            | 5         | 0.27%   |
| Phoenix           | 5         | 0.27%   |
| Louisville        | 5         | 0.27%   |
| Krakow            | 5         | 0.27%   |
| Ho Chi Minh City  | 5         | 0.27%   |
| Frankfurt am Main | 5         | 0.27%   |
| Dresden           | 5         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 286       | 349    | 13.47%  |
| WDC                          | 186       | 222    | 8.76%   |
| Seagate                      | 174       | 195    | 8.19%   |
| Toshiba                      | 164       | 185    | 7.72%   |
| SanDisk                      | 162       | 193    | 7.63%   |
| Unknown                      | 122       | 145    | 5.74%   |
| Kingston                     | 114       | 136    | 5.37%   |
| Apple                        | 106       | 119    | 4.99%   |
| Crucial                      | 89        | 104    | 4.19%   |
| SK hynix                     | 60        | 72     | 2.82%   |
| HGST                         | 59        | 73     | 2.78%   |
| Hitachi                      | 58        | 64     | 2.73%   |
| Intel                        | 52        | 71     | 2.45%   |
| Micron Technology            | 34        | 37     | 1.6%    |
| A-DATA Technology            | 33        | 37     | 1.55%   |
| KIOXIA                       | 24        | 38     | 1.13%   |
| China                        | 23        | 26     | 1.08%   |
| Fujitsu                      | 16        | 19     | 0.75%   |
| Phison Electronics           | 15        | 15     | 0.71%   |
| Silicon Motion               | 14        | 15     | 0.66%   |
| Phison                       | 13        | 14     | 0.61%   |
| LITEON                       | 13        | 13     | 0.61%   |
| Unknown                      | 13        | 14     | 0.61%   |
| SPCC                         | 11        | 11     | 0.52%   |
| JMicron Technology           | 10        | 10     | 0.47%   |
| Intenso                      | 10        | 11     | 0.47%   |
| Patriot                      | 9         | 11     | 0.42%   |
| Kingston Technology Company  | 9         | 9      | 0.42%   |
| PNY                          | 8         | 10     | 0.38%   |
| Micron/Crucial Technology    | 8         | 8      | 0.38%   |
| Transcend                    | 7         | 8      | 0.33%   |
| Fanxiang                     | 7         | 7      | 0.33%   |
| KingSpec                     | 6         | 10     | 0.28%   |
| KingDian                     | 6         | 8      | 0.28%   |
| Hewlett-Packard              | 6         | 8      | 0.28%   |
| Apacer                       | 6         | 10     | 0.28%   |
| Yangtze Memory Technologies  | 5         | 5      | 0.24%   |
| Union Memory                 | 5         | 9      | 0.24%   |
| Shenzhen Longsys Electronics | 5         | 6      | 0.24%   |
| OCZ                          | 5         | 6      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                               | 30        | 1.37%   |
| Toshiba MQ01ABD100 1TB                               | 29        | 1.33%   |
| Kingston SA400S37240G 240GB SSD                      | 28        | 1.28%   |
| Unknown MMC Card  32GB                               | 26        | 1.19%   |
| Seagate ST1000LM035-1RK172 1TB                       | 24        | 1.1%    |
| Seagate ST500LT012-1DG142 500GB                      | 22        | 1.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 19        | 0.87%   |
| Unknown MMC Card  128GB                              | 18        | 0.82%   |
| Toshiba MQ04ABF100 1TB                               | 17        | 0.78%   |
| Toshiba MQ01ABF050 500GB                             | 17        | 0.78%   |
| Samsung NVMe SSD Drive 512GB                         | 17        | 0.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 17        | 0.78%   |
| Apple SSD SM0128G 121GB                              | 17        | 0.78%   |
| HGST HTS721010A9E630 1TB                             | 16        | 0.73%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 15        | 0.69%   |
| SanDisk NVMe SSD Drive 512GB                         | 15        | 0.69%   |
| Samsung SSD 860 EVO 500GB                            | 14        | 0.64%   |
| Samsung NVMe SSD Drive 256GB                         | 14        | 0.64%   |
| Crucial CT240BX500SSD1 240GB                         | 14        | 0.64%   |
| Unknown MMC Card  16GB                               | 13        | 0.6%    |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                | 13        | 0.6%    |
| Kingston SA400S37120G 120GB SSD                      | 13        | 0.6%    |
| Unknown                                              | 13        | 0.6%    |
| HGST HTS545050A7E680 500GB                           | 12        | 0.55%   |
| Samsung SSD 860 EVO 250GB                            | 11        | 0.5%    |
| Samsung SSD 850 EVO 500GB                            | 11        | 0.5%    |
| Apple SSD SM0256F 256GB                              | 11        | 0.5%    |
| Samsung SSD 850 EVO 250GB                            | 10        | 0.46%   |
| Crucial CT500MX500SSD1 500GB                         | 10        | 0.46%   |
| WDC WD5000LPVX-22V0TT0 500GB                         | 9         | 0.41%   |
| HGST HTS541010A9E680 1TB                             | 9         | 0.41%   |
| Apple SSD SM0256G 256GB                              | 9         | 0.41%   |
| SK hynix BC501 NVMe Solid State Drive 512GB          | 8         | 0.37%   |
| Kingston SA400S37480G 480GB SSD                      | 8         | 0.37%   |
| Intel NVMe SSD Drive 512GB                           | 8         | 0.37%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 7         | 0.32%   |
| SK hynix NVMe SSD Drive 512GB                        | 7         | 0.32%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB     | 7         | 0.32%   |
| SanDisk NVMe SSD Drive 256GB                         | 7         | 0.32%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB | 7         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 171       | 191    | 28.36%  |
| Toshiba             | 128       | 141    | 21.23%  |
| WDC                 | 127       | 150    | 21.06%  |
| HGST                | 59        | 73     | 9.78%   |
| Hitachi             | 58        | 64     | 9.62%   |
| Fujitsu             | 16        | 19     | 2.65%   |
| Apple               | 11        | 11     | 1.82%   |
| Samsung Electronics | 9         | 11     | 1.49%   |
| Unknown             | 6         | 6      | 1%      |
| TO Exter            | 4         | 4      | 0.66%   |
| JMicron Technology  | 4         | 4      | 0.66%   |
| External            | 2         | 2      | 0.33%   |
| USB                 | 1         | 1      | 0.17%   |
| T-FORCE             | 1         | 1      | 0.17%   |
| StoreJet            | 1         | 1      | 0.17%   |
| SSK                 | 1         | 1      | 0.17%   |
| JetFlash            | 1         | 2      | 0.17%   |
| Generic-            | 1         | 1      | 0.17%   |
| ASMT                | 1         | 1      | 0.17%   |
| Unknown             | 1         | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 152       | 180    | 17.65%  |
| Kingston            | 99        | 116    | 11.5%   |
| Apple               | 91        | 103    | 10.57%  |
| Crucial             | 88        | 103    | 10.22%  |
| SanDisk             | 85        | 105    | 9.87%   |
| WDC                 | 47        | 53     | 5.46%   |
| A-DATA Technology   | 28        | 31     | 3.25%   |
| China               | 23        | 26     | 2.67%   |
| Intel               | 22        | 27     | 2.56%   |
| Micron Technology   | 16        | 18     | 1.86%   |
| Toshiba             | 15        | 19     | 1.74%   |
| LITEON              | 12        | 12     | 1.39%   |
| SPCC                | 11        | 11     | 1.28%   |
| SK hynix            | 11        | 11     | 1.28%   |
| Patriot             | 9         | 11     | 1.05%   |
| Intenso             | 9         | 10     | 1.05%   |
| PNY                 | 8         | 10     | 0.93%   |
| Transcend           | 7         | 8      | 0.81%   |
| KingSpec            | 6         | 10     | 0.7%    |
| Hewlett-Packard     | 6         | 8      | 0.7%    |
| Apacer              | 6         | 10     | 0.7%    |
| OCZ                 | 5         | 6      | 0.58%   |
| LITEONIT            | 5         | 5      | 0.58%   |
| Lexar               | 5         | 5      | 0.58%   |
| KingDian            | 5         | 6      | 0.58%   |
| Unknown             | 5         | 5      | 0.58%   |
| SABRENT             | 4         | 4      | 0.46%   |
| OWC                 | 4         | 4      | 0.46%   |
| NGFF                | 4         | 5      | 0.46%   |
| Team                | 3         | 3      | 0.35%   |
| Netac               | 3         | 3      | 0.35%   |
| GOODRAM             | 3         | 4      | 0.35%   |
| Gigabyte Technology | 3         | 3      | 0.35%   |
| Fanxiang            | 3         | 3      | 0.35%   |
| BIWIN               | 3         | 3      | 0.35%   |
| VISIPRO             | 2         | 2      | 0.23%   |
| Verbatim            | 2         | 2      | 0.23%   |
| V-GeN               | 2         | 2      | 0.23%   |
| Star                | 2         | 2      | 0.23%   |
| Phison              | 2         | 3      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 811       | 1001   | 39.97%  |
| HDD     | 577       | 685    | 28.44%  |
| NVMe    | 476       | 608    | 23.46%  |
| MMC     | 115       | 138    | 5.67%   |
| Unknown | 50        | 55     | 2.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1287      | 1660   | 65.97%  |
| NVMe | 473       | 603    | 24.24%  |
| MMC  | 115       | 138    | 5.89%   |
| SAS  | 76        | 86     | 3.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 996       | 1249   | 72.38%  |
| 0.51-1.0   | 325       | 375    | 23.62%  |
| 1.01-2.0   | 49        | 56     | 3.56%   |
| 3.01-4.0   | 6         | 6      | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 732       | 41.12%  |
| 251-500        | 510       | 28.65%  |
| 501-1000       | 243       | 13.65%  |
| 51-100         | 126       | 7.08%   |
| 21-50          | 62        | 3.48%   |
| 1001-2000      | 59        | 3.31%   |
| 1-20           | 21        | 1.18%   |
| 2001-3000      | 13        | 0.73%   |
| More than 3000 | 10        | 0.56%   |
| Unknown        | 4         | 0.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 849       | 45.89%  |
| 21-50          | 516       | 27.89%  |
| 51-100         | 196       | 10.59%  |
| 101-250        | 162       | 8.76%   |
| 251-500        | 71        | 3.84%   |
| 501-1000       | 34        | 1.84%   |
| 1001-2000      | 13        | 0.7%    |
| 2001-3000      | 4         | 0.22%   |
| Unknown        | 4         | 0.22%   |
| More than 3000 | 1         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Notebooks | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD            | 1         | 1      | 3.57%   |
| WDC WD5000BPKT-75PK4T0 500GB                | 1         | 1      | 3.57%   |
| WDC WD10SPZX-24Z10 1TB                      | 1         | 1      | 3.57%   |
| WDC WD10JPCX-24UE4T0 1TB                    | 1         | 1      | 3.57%   |
| Toshiba MQ01ABD100 1TB                      | 1         | 1      | 3.57%   |
| Toshiba MK3259GSXP 320GB                    | 1         | 1      | 3.57%   |
| Seagate ST500LM030-2E717D 500GB             | 1         | 1      | 3.57%   |
| Seagate ST320LT020-9YG142 320GB             | 1         | 1      | 3.57%   |
| Seagate ST1000LM035-1RK172 1TB              | 1         | 1      | 3.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB          | 1         | 1      | 3.57%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD         | 1         | 1      | 3.57%   |
| SanDisk SD7SB3Q256G1002 256GB SSD           | 1         | 1      | 3.57%   |
| Samsung Electronics HM320II 320GB           | 1         | 1      | 3.57%   |
| LS 128GB M300                               | 1         | 1      | 3.57%   |
| Kingston SV300S37A240G 240GB SSD            | 1         | 1      | 3.57%   |
| Kingston SUV400S37480G 480GB SSD            | 1         | 1      | 3.57%   |
| Intel SSDPEKKF512G7H BTPY71141D7T512F 512GB | 1         | 1      | 3.57%   |
| Hitachi HTS547564A9E384 640GB               | 1         | 1      | 3.57%   |
| HGST HTS725050A7E630 500GB                  | 1         | 1      | 3.57%   |
| HGST HTS545050A7E680 500GB                  | 1         | 1      | 3.57%   |
| HGST HTS541010A9E680 1TB                    | 1         | 1      | 3.57%   |
| Fujitsu MHZ2160BH G2 160GB                  | 1         | 2      | 3.57%   |
| Crucial CT512M550SSD3 512GB                 | 1         | 1      | 3.57%   |
| Crucial CT240M500SSD3 240GB                 | 1         | 1      | 3.57%   |
| China SSD 256GB                             | 1         | 1      | 3.57%   |
| BIWIN SSD 64GB                              | 1         | 1      | 3.57%   |
| Apple SSD SM256C 256GB                      | 1         | 1      | 3.57%   |
| A-DATA Technology SP900NS38 128GB SSD       | 1         | 1      | 3.57%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 14.29%  |
| Seagate             | 4         | 4      | 14.29%  |
| HGST                | 3         | 3      | 10.71%  |
| Toshiba             | 2         | 2      | 7.14%   |
| SanDisk             | 2         | 2      | 7.14%   |
| Kingston            | 2         | 2      | 7.14%   |
| Crucial             | 2         | 2      | 7.14%   |
| Samsung Electronics | 1         | 1      | 3.57%   |
| LS                  | 1         | 1      | 3.57%   |
| Intel               | 1         | 1      | 3.57%   |
| Hitachi             | 1         | 1      | 3.57%   |
| Fujitsu             | 1         | 2      | 3.57%   |
| China               | 1         | 1      | 3.57%   |
| BIWIN               | 1         | 1      | 3.57%   |
| Apple               | 1         | 1      | 3.57%   |
| A-DATA Technology   | 1         | 1      | 3.57%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 4         | 4      | 26.67%  |
| WDC                 | 3         | 3      | 20%     |
| HGST                | 3         | 3      | 20%     |
| Toshiba             | 2         | 2      | 13.33%  |
| Samsung Electronics | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |
| Fujitsu             | 1         | 2      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 16     | 53.57%  |
| SSD  | 12        | 12     | 42.86%  |
| NVMe | 1         | 1      | 3.57%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10SPZX-75Z10T1 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1551      | 2191   | 86.6%   |
| Works    | 211       | 266    | 11.78%  |
| Malfunc  | 28        | 29     | 1.56%   |
| Failed   | 1         | 1      | 0.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1211      | 61.41%  |
| Samsung Electronics              | 176       | 8.92%   |
| AMD                              | 169       | 8.57%   |
| Sandisk                          | 92        | 4.67%   |
| Nvidia                           | 56        | 2.84%   |
| SK hynix                         | 48        | 2.43%   |
| Phison Electronics               | 30        | 1.52%   |
| Kingston Technology Company      | 25        | 1.27%   |
| Toshiba America Info Systems     | 24        | 1.22%   |
| KIOXIA                           | 23        | 1.17%   |
| Micron Technology                | 18        | 0.91%   |
| Silicon Motion                   | 15        | 0.76%   |
| Union Memory (Shenzhen)          | 10        | 0.51%   |
| Marvell Technology Group         | 10        | 0.51%   |
| Micron/Crucial Technology        | 9         | 0.46%   |
| ADATA Technology                 | 9         | 0.46%   |
| Solid State Storage Technology   | 6         | 0.3%    |
| Yangtze Memory Technologies      | 5         | 0.25%   |
| Shenzhen Longsys Electronics     | 5         | 0.25%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.25%   |
| Lite-On Technology               | 5         | 0.25%   |
| Realtek Semiconductor            | 4         | 0.2%    |
| Apple                            | 4         | 0.2%    |
| Biwin Storage Technology         | 3         | 0.15%   |
| ASMedia Technology               | 3         | 0.15%   |
| JMicron Technology               | 2         | 0.1%    |
| VIA Technologies                 | 1         | 0.05%   |
| Solidigm                         | 1         | 0.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |
| Shenzhen Techwinsemi Technology  | 1         | 0.05%   |
| INNOGRIT                         | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 180       | 8.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 163       | 7.87%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 149       | 7.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 130       | 6.27%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 90        | 4.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 70        | 3.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 59        | 2.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 48        | 2.32%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 44        | 2.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 43        | 2.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 41        | 1.98%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 41        | 1.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 41        | 1.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 40        | 1.93%   |
| Nvidia MCP79 AHCI Controller                                                           | 34        | 1.64%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                             | 32        | 1.54%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 30        | 1.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 29        | 1.4%    |
| Intel Tiger Lake-LP SATA Controller                                                    | 28        | 1.35%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 27        | 1.3%    |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)              | 22        | 1.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 21        | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 21        | 1.01%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 20        | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 19        | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 18        | 0.87%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 17        | 0.82%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                                     | 17        | 0.82%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 17        | 0.82%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                   | 16        | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 16        | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 16        | 0.77%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 14        | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 13        | 0.63%   |
| Intel SSD 660P Series                                                                  | 13        | 0.63%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 13        | 0.63%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 12        | 0.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 12        | 0.58%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                    | 11        | 0.53%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 11        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1318      | 65.6%   |
| NVMe | 471       | 23.44%  |
| RAID | 143       | 7.12%   |
| IDE  | 77        | 3.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1476      | 84.68%  |
| AMD    | 267       | 15.32%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3210M CPU @ 2.50GHz             | 38        | 2.18%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 32        | 1.83%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 29        | 1.66%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 26        | 1.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 24        | 1.38%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 23        | 1.32%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 23        | 1.32%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 19        | 1.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 18        | 1.03%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 18        | 1.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 18        | 1.03%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 17        | 0.97%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 16        | 0.92%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 16        | 0.92%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 0.92%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 15        | 0.86%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 0.8%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 14        | 0.8%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 14        | 0.8%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 14        | 0.8%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 14        | 0.8%    |
| Intel Core i5-2415M CPU @ 2.30GHz             | 13        | 0.75%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 13        | 0.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 0.69%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 12        | 0.69%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 12        | 0.69%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 12        | 0.69%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 12        | 0.69%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 11        | 0.63%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 11        | 0.63%   |
| Intel Core i5-2435M CPU @ 2.40GHz             | 11        | 0.63%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 11        | 0.63%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 11        | 0.63%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 11        | 0.63%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 11        | 0.63%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 0.57%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 10        | 0.57%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 10        | 0.57%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 10        | 0.57%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 10        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 484       | 27.75%  |
| Intel Core i7           | 362       | 20.76%  |
| Intel Core i3           | 165       | 9.46%   |
| Other                   | 130       | 7.45%   |
| Intel Core 2 Duo        | 110       | 6.31%   |
| Intel Celeron           | 104       | 5.96%   |
| AMD Ryzen 5             | 74        | 4.24%   |
| Intel Pentium           | 45        | 2.58%   |
| AMD Ryzen 7             | 43        | 2.47%   |
| Intel Pentium Dual-Core | 18        | 1.03%   |
| Intel Atom              | 18        | 1.03%   |
| AMD Ryzen 3             | 17        | 0.97%   |
| AMD A4                  | 16        | 0.92%   |
| AMD A8                  | 15        | 0.86%   |
| AMD A6                  | 15        | 0.86%   |
| Intel Pentium Silver    | 13        | 0.75%   |
| AMD A10                 | 11        | 0.63%   |
| Intel Core 2            | 8         | 0.46%   |
| AMD A12                 | 8         | 0.46%   |
| Intel Core m3           | 6         | 0.34%   |
| AMD Ryzen 5 PRO         | 6         | 0.34%   |
| AMD E1                  | 6         | 0.34%   |
| Intel Pentium Dual      | 5         | 0.29%   |
| Intel Genuine           | 5         | 0.29%   |
| Intel Celeron Dual-Core | 5         | 0.29%   |
| AMD Ryzen 7 PRO         | 5         | 0.29%   |
| AMD E                   | 5         | 0.29%   |
| AMD Athlon              | 5         | 0.29%   |
| AMD E2                  | 4         | 0.23%   |
| Intel Xeon              | 3         | 0.17%   |
| Intel Core m5           | 3         | 0.17%   |
| Intel Core M            | 3         | 0.17%   |
| AMD V140                | 3         | 0.17%   |
| AMD Ryzen 9             | 3         | 0.17%   |
| Intel Core              | 2         | 0.11%   |
| AMD Turion II Dual-Core | 2         | 0.11%   |
| AMD Phenom II           | 2         | 0.11%   |
| AMD C-60                | 2         | 0.11%   |
| Intel Core m7           | 1         | 0.06%   |
| Intel Core i9           | 1         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1049      | 60.15%  |
| 4      | 520       | 29.82%  |
| 6      | 80        | 4.59%   |
| 8      | 62        | 3.56%   |
| 1      | 16        | 0.92%   |
| 10     | 7         | 0.4%    |
| 12     | 5         | 0.29%   |
| 14     | 3         | 0.17%   |
| 16     | 1         | 0.06%   |
| 5      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1743      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1310      | 75.03%  |
| 1      | 436       | 24.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1739      | 99.77%  |
| Unknown        | 4         | 0.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 897       | 50.56%  |
| 0x206a7    | 91        | 5.13%   |
| 0x306a9    | 72        | 4.06%   |
| 0x40651    | 48        | 2.71%   |
| 0x1067a    | 43        | 2.42%   |
| 0x806c1    | 39        | 2.2%    |
| 0x406e3    | 38        | 2.14%   |
| 0x806ea    | 36        | 2.03%   |
| 0x806e9    | 36        | 2.03%   |
| 0x306d4    | 33        | 1.86%   |
| 0x806ec    | 31        | 1.75%   |
| 0x20655    | 27        | 1.52%   |
| 0x306c3    | 24        | 1.35%   |
| 0x20652    | 17        | 0.96%   |
| 0x30678    | 16        | 0.9%    |
| 0x706e5    | 15        | 0.85%   |
| 0x08108109 | 15        | 0.85%   |
| 0x06006705 | 15        | 0.85%   |
| 0x906ea    | 14        | 0.79%   |
| 0x406c3    | 14        | 0.79%   |
| 0x806eb    | 13        | 0.73%   |
| 0x706a1    | 13        | 0.73%   |
| 0xa0652    | 12        | 0.68%   |
| 0x706a8    | 12        | 0.68%   |
| 0x08600106 | 12        | 0.68%   |
| 0x906e9    | 11        | 0.62%   |
| 0x506c9    | 11        | 0.62%   |
| 0x10676    | 11        | 0.62%   |
| 0x08608103 | 11        | 0.62%   |
| 0x40661    | 8         | 0.45%   |
| 0x0a50000c | 8         | 0.45%   |
| 0x08108102 | 8         | 0.45%   |
| 0x07030105 | 8         | 0.45%   |
| 0x6fd      | 7         | 0.39%   |
| 0x506e3    | 7         | 0.39%   |
| 0x406c4    | 7         | 0.39%   |
| 0x06001119 | 7         | 0.39%   |
| 0x05000119 | 6         | 0.34%   |
| 0x6fb      | 5         | 0.28%   |
| 0x6f6      | 5         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| KabyLake           | 256       | 14.67%  |
| SandyBridge        | 178       | 10.2%   |
| IvyBridge          | 164       | 9.4%    |
| Haswell            | 163       | 9.34%   |
| Penryn             | 127       | 7.28%   |
| Skylake            | 99        | 5.67%   |
| Westmere           | 85        | 4.87%   |
| TigerLake          | 85        | 4.87%   |
| Broadwell          | 78        | 4.47%   |
| Unknown            | 68        | 3.9%    |
| Silvermont         | 60        | 3.44%   |
| Goldmont plus      | 48        | 2.75%   |
| Zen+               | 42        | 2.41%   |
| Excavator          | 41        | 2.35%   |
| IceLake            | 30        | 1.72%   |
| Zen 2              | 29        | 1.66%   |
| Core               | 29        | 1.66%   |
| Zen 3              | 23        | 1.32%   |
| Puma               | 21        | 1.2%    |
| CometLake          | 21        | 1.2%    |
| Goldmont           | 16        | 0.92%   |
| Zen                | 15        | 0.86%   |
| Bobcat             | 11        | 0.63%   |
| Piledriver         | 10        | 0.57%   |
| K10                | 10        | 0.57%   |
| Jaguar             | 8         | 0.46%   |
| Alderlake Hybrid   | 7         | 0.4%    |
| K10 Llano          | 5         | 0.29%   |
| Bonnell            | 5         | 0.29%   |
| Nehalem            | 3         | 0.17%   |
| Steamroller        | 2         | 0.11%   |
| K8 & K10 hybrid    | 2         | 0.11%   |
| Tremont            | 1         | 0.06%   |
| Lunarlake Hybrid   | 1         | 0.06%   |
| K8 Hammer          | 1         | 0.06%   |
| ArrowLake-H Hybrid | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 1329      | 62.63%  |
| Nvidia           | 407       | 19.18%  |
| AMD              | 385       | 18.14%  |
| VIA Technologies | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 163       | 7.46%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 154       | 7.05%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 95        | 4.35%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 72        | 3.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 71        | 3.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 69        | 3.16%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 61        | 2.79%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 56        | 2.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 51        | 2.34%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 44        | 2.01%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 42        | 1.92%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 42        | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 42        | 1.92%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 36        | 1.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 34        | 1.56%   |
| Nvidia C79 [GeForce 9400M]                                                               | 33        | 1.51%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 30        | 1.37%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 29        | 1.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 28        | 1.28%   |
| Intel Broadwell-U GT3 [HD Graphics 6000]                                                 | 28        | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 26        | 1.19%   |
| AMD Lucienne                                                                             | 26        | 1.19%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 24        | 1.1%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 21        | 0.96%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 20        | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 20        | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 20        | 0.92%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 20        | 0.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 18        | 0.82%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 18        | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 17        | 0.78%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 17        | 0.78%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 17        | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 16        | 0.73%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 16        | 0.73%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 16        | 0.73%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 16        | 0.73%   |
| Nvidia GP108M [GeForce MX150]                                                            | 15        | 0.69%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 15        | 0.69%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 15        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 966       | 55.39%  |
| Intel + Nvidia | 277       | 15.88%  |
| 1 x AMD        | 256       | 14.68%  |
| 1 x Nvidia     | 105       | 6.02%   |
| Intel + AMD    | 80        | 4.59%   |
| 2 x AMD        | 30        | 1.72%   |
| AMD + Nvidia   | 17        | 0.97%   |
| 2 x Nvidia     | 8         | 0.46%   |
| Other          | 4         | 0.23%   |
| 1 x VIA        | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1605      | 91.61%  |
| Proprietary | 118       | 6.74%   |
| Unknown     | 29        | 1.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1361      | 77.29%  |
| 1.01-2.0   | 142       | 8.06%   |
| 0.01-0.5   | 122       | 6.93%   |
| 0.51-1.0   | 72        | 4.09%   |
| 3.01-4.0   | 46        | 2.61%   |
| 5.01-6.0   | 10        | 0.57%   |
| 7.01-8.0   | 6         | 0.34%   |
| 2.01-3.0   | 2         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 328       | 17.33%  |
| LG Display              | 265       | 14%     |
| BOE                     | 260       | 13.73%  |
| Apple                   | 249       | 13.15%  |
| Chimei Innolux          | 240       | 12.68%  |
| Samsung Electronics     | 160       | 8.45%   |
| Chi Mei Optoelectronics | 40        | 2.11%   |
| Sharp                   | 39        | 2.06%   |
| Lenovo                  | 36        | 1.9%    |
| Dell                    | 33        | 1.74%   |
| PANDA                   | 24        | 1.27%   |
| Goldstar                | 19        | 1%      |
| Hewlett-Packard         | 17        | 0.9%    |
| BenQ                    | 12        | 0.63%   |
| Acer                    | 12        | 0.63%   |
| InfoVision              | 8         | 0.42%   |
| CSO                     | 8         | 0.42%   |
| AOC                     | 8         | 0.42%   |
| Toshiba                 | 7         | 0.37%   |
| Sony                    | 7         | 0.37%   |
| Panasonic               | 7         | 0.37%   |
| ViewSonic               | 6         | 0.32%   |
| LG Philips              | 6         | 0.32%   |
| HannStar                | 6         | 0.32%   |
| CPT                     | 6         | 0.32%   |
| Philips                 | 5         | 0.26%   |
| Ancor Communications    | 5         | 0.26%   |
| HKC                     | 4         | 0.21%   |
| ASUSTek Computer        | 4         | 0.21%   |
| Unknown                 | 3         | 0.16%   |
| TMX                     | 3         | 0.16%   |
| Mi                      | 3         | 0.16%   |
| Fujitsu Siemens         | 3         | 0.16%   |
| CSOT                    | 3         | 0.16%   |
| Vizio                   | 2         | 0.11%   |
| Vestel Elektronik       | 2         | 0.11%   |
| Unknown (XXX)           | 2         | 0.11%   |
| LGD                     | 2         | 0.11%   |
| KDC                     | 2         | 0.11%   |
| KDB                     | 2         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 21        | 1.1%    |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 21        | 1.1%    |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                   | 19        | 0.99%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 16        | 0.84%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 15        | 0.78%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 14        | 0.73%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 13        | 0.68%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 12        | 0.63%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 12        | 0.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.63%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                   | 12        | 0.63%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                     | 12        | 0.63%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 11        | 0.57%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 10        | 0.52%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 10        | 0.52%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                   | 10        | 0.52%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 9         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 9         | 0.47%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 9         | 0.47%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 9         | 0.47%   |
| Apple Color LCD APPA019 2880x1800 331x207mm 15.4-inch                    | 9         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 8         | 0.42%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 8         | 0.42%   |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch                   | 8         | 0.42%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch                   | 8         | 0.42%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                     | 8         | 0.42%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                     | 8         | 0.42%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 7         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 7         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 7         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 7         | 0.37%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 7         | 0.37%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 7         | 0.37%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 7         | 0.37%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch         | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 6         | 0.31%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 6         | 0.31%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 6         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 665       | 36.56%  |
| 1366x768 (WXGA)    | 579       | 31.83%  |
| 1280x800 (WXGA)    | 135       | 7.42%   |
| 1600x900 (HD+)     | 97        | 5.33%   |
| 1440x900 (WXGA+)   | 84        | 4.62%   |
| 3840x2160 (4K)     | 49        | 2.69%   |
| 2880x1800          | 35        | 1.92%   |
| 1920x1200 (WUXGA)  | 34        | 1.87%   |
| 2560x1440 (QHD)    | 30        | 1.65%   |
| 2560x1600          | 25        | 1.37%   |
| 1680x1050 (WSXGA+) | 14        | 0.77%   |
| 3000x2000          | 7         | 0.38%   |
| 2160x1440          | 7         | 0.38%   |
| 1280x1024 (SXGA)   | 7         | 0.38%   |
| 1024x600           | 6         | 0.33%   |
| 2560x1080          | 5         | 0.27%   |
| 3840x2400          | 4         | 0.22%   |
| 3200x1800 (QHD+)   | 4         | 0.22%   |
| 1920x540           | 4         | 0.22%   |
| 1360x768           | 4         | 0.22%   |
| 3440x1440          | 3         | 0.16%   |
| Unknown            | 3         | 0.16%   |
| 3072x1920          | 2         | 0.11%   |
| 1920x1280          | 2         | 0.11%   |
| 1680x945           | 2         | 0.11%   |
| 1400x1050          | 2         | 0.11%   |
| 4240x1080          | 1         | 0.05%   |
| 3840x1100          | 1         | 0.05%   |
| 3840x1080          | 1         | 0.05%   |
| 3200x2000          | 1         | 0.05%   |
| 2304x1440          | 1         | 0.05%   |
| 2256x1504          | 1         | 0.05%   |
| 1920x515           | 1         | 0.05%   |
| 1600x2560          | 1         | 0.05%   |
| 1600x1200          | 1         | 0.05%   |
| 1280x720 (HD)      | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 733       | 38.56%  |
| 13      | 424       | 22.3%   |
| 14      | 225       | 11.84%  |
| 17      | 121       | 6.37%   |
| 11      | 58        | 3.05%   |
| 27      | 44        | 2.31%   |
| 24      | 43        | 2.26%   |
| 12      | 38        | 2%      |
| 23      | 34        | 1.79%   |
| 21      | 27        | 1.42%   |
| Unknown | 22        | 1.16%   |
| 16      | 20        | 1.05%   |
| 31      | 19        | 1%      |
| 18      | 14        | 0.74%   |
| 19      | 12        | 0.63%   |
| 84      | 9         | 0.47%   |
| 10      | 8         | 0.42%   |
| 72      | 5         | 0.26%   |
| 54      | 5         | 0.26%   |
| 25      | 5         | 0.26%   |
| 22      | 5         | 0.26%   |
| 34      | 4         | 0.21%   |
| 32      | 4         | 0.21%   |
| 74      | 3         | 0.16%   |
| 63      | 3         | 0.16%   |
| 20      | 3         | 0.16%   |
| 52      | 2         | 0.11%   |
| 86      | 1         | 0.05%   |
| 69      | 1         | 0.05%   |
| 65      | 1         | 0.05%   |
| 60      | 1         | 0.05%   |
| 48      | 1         | 0.05%   |
| 43      | 1         | 0.05%   |
| 40      | 1         | 0.05%   |
| 37      | 1         | 0.05%   |
| 35      | 1         | 0.05%   |
| 33      | 1         | 0.05%   |
| 26      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1110      | 58.85%  |
| 201-300     | 374       | 19.83%  |
| 351-400     | 145       | 7.69%   |
| 501-600     | 114       | 6.04%   |
| 401-500     | 53        | 2.81%   |
| 601-700     | 23        | 1.22%   |
| Unknown     | 22        | 1.17%   |
| 1501-2000   | 18        | 0.95%   |
| 1001-1500   | 14        | 0.74%   |
| 701-800     | 9         | 0.48%   |
| 801-900     | 3         | 0.16%   |
| 901-1000    | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1338      | 77.48%  |
| 16/10   | 329       | 19.05%  |
| 3/2     | 24        | 1.39%   |
| Unknown | 18        | 1.04%   |
| 5/4     | 7         | 0.41%   |
| 21/9    | 5         | 0.29%   |
| 4/3     | 2         | 0.12%   |
| 3.73    | 1         | 0.06%   |
| 3.40    | 1         | 0.06%   |
| 1.96    | 1         | 0.06%   |
| 0.56    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 729       | 38.45%  |
| 81-90          | 503       | 26.53%  |
| 71-80          | 142       | 7.49%   |
| 121-130        | 95        | 5.01%   |
| 201-250        | 88        | 4.64%   |
| 51-60          | 59        | 3.11%   |
| 301-350        | 44        | 2.32%   |
| 61-70          | 38        | 2%      |
| More than 1000 | 31        | 1.64%   |
| 351-500        | 29        | 1.53%   |
| 131-140        | 25        | 1.32%   |
| Unknown        | 22        | 1.16%   |
| 151-200        | 21        | 1.11%   |
| 111-120        | 21        | 1.11%   |
| 251-300        | 16        | 0.84%   |
| 141-150        | 16        | 0.84%   |
| 41-50          | 8         | 0.42%   |
| 91-100         | 5         | 0.26%   |
| 501-1000       | 4         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 720       | 38.56%  |
| 121-160       | 717       | 38.4%   |
| 51-100        | 209       | 11.19%  |
| 161-240       | 138       | 7.39%   |
| More than 240 | 37        | 1.98%   |
| 1-50          | 24        | 1.29%   |
| Unknown       | 22        | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1532      | 86.65%  |
| 2     | 199       | 11.26%  |
| 0     | 20        | 1.13%   |
| 3     | 16        | 0.9%    |
| 4     | 1         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 816       | 29.9%   |
| Intel                             | 743       | 27.23%  |
| Qualcomm Atheros                  | 360       | 13.19%  |
| Broadcom                          | 360       | 13.19%  |
| Broadcom Limited                  | 95        | 3.48%   |
| MediaTek                          | 46        | 1.69%   |
| Nvidia                            | 39        | 1.43%   |
| Marvell Technology Group          | 33        | 1.21%   |
| Ralink                            | 22        | 0.81%   |
| TP-Link                           | 18        | 0.66%   |
| Samsung Electronics               | 18        | 0.66%   |
| ASIX Electronics                  | 17        | 0.62%   |
| Ralink Technology                 | 15        | 0.55%   |
| Sierra Wireless                   | 14        | 0.51%   |
| Xiaomi                            | 12        | 0.44%   |
| Qualcomm                          | 10        | 0.37%   |
| Huawei Technologies               | 10        | 0.37%   |
| Hewlett-Packard                   | 9         | 0.33%   |
| Shenzhen Goodix Technology        | 8         | 0.29%   |
| Ericsson Business Mobile Networks | 8         | 0.29%   |
| Dell                              | 8         | 0.29%   |
| D-Link                            | 6         | 0.22%   |
| Apple                             | 5         | 0.18%   |
| Lenovo                            | 4         | 0.15%   |
| Google                            | 4         | 0.15%   |
| Qualcomm Atheros Communications   | 3         | 0.11%   |
| OPPO Electronics                  | 3         | 0.11%   |
| JMicron Technology                | 3         | 0.11%   |
| ICS Advent                        | 3         | 0.11%   |
| D-Link System                     | 3         | 0.11%   |
| ASUSTek Computer                  | 3         | 0.11%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.07%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.07%   |
| NetGear                           | 2         | 0.07%   |
| Motorola PCS                      | 2         | 0.07%   |
| Edimax Technology                 | 2         | 0.07%   |
| Attansic Technology               | 2         | 0.07%   |
| ZyDAS                             | 1         | 0.04%   |
| Wacom                             | 1         | 0.04%   |
| VIA Technologies                  | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 465       | 14.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 168       | 5.13%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 81        | 2.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 76        | 2.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 65        | 1.99%   |
| Intel Wi-Fi 6 AX201                                                    | 65        | 1.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 61        | 1.86%   |
| Intel Wireless 8260                                                    | 60        | 1.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 57        | 1.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 55        | 1.68%   |
| Intel Wireless 7265                                                    | 53        | 1.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 52        | 1.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 49        | 1.5%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 49        | 1.5%    |
| Intel Wireless 8265 / 8275                                             | 48        | 1.47%   |
| Intel Wireless 7260                                                    | 46        | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 45        | 1.38%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 44        | 1.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 40        | 1.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 40        | 1.22%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 38        | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 37        | 1.13%   |
| Broadcom BCM43142 802.11b/g/n                                          | 36        | 1.1%    |
| Nvidia MCP79 Ethernet                                                  | 35        | 1.07%   |
| Intel Wi-Fi 6 AX200                                                    | 34        | 1.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 30        | 0.92%   |
| Intel Wireless 3165                                                    | 30        | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 29        | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 27        | 0.83%   |
| Intel Ethernet Connection I219-LM                                      | 23        | 0.7%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                      | 22        | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 21        | 0.64%   |
| Intel 82577LM Gigabit Network Connection                               | 21        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 20        | 0.61%   |
| Intel Wireless 3160                                                    | 20        | 0.61%   |
| Intel Ethernet Connection I218-LM                                      | 20        | 0.61%   |
| Intel Centrino Advanced-N 6235                                         | 20        | 0.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 20        | 0.61%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 20        | 0.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 19        | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 699       | 38.32%  |
| Broadcom                        | 323       | 17.71%  |
| Qualcomm Atheros                | 309       | 16.94%  |
| Realtek Semiconductor           | 272       | 14.91%  |
| Broadcom Limited                | 81        | 4.44%   |
| MediaTek                        | 38        | 2.08%   |
| Ralink                          | 22        | 1.21%   |
| TP-Link                         | 18        | 0.99%   |
| Ralink Technology               | 15        | 0.82%   |
| Sierra Wireless                 | 14        | 0.77%   |
| Qualcomm                        | 6         | 0.33%   |
| Dell                            | 4         | 0.22%   |
| D-Link                          | 4         | 0.22%   |
| Qualcomm Atheros Communications | 3         | 0.16%   |
| D-Link System                   | 3         | 0.16%   |
| ASUSTek Computer                | 3         | 0.16%   |
| Edimax Technology               | 2         | 0.11%   |
| ZyDAS                           | 1         | 0.05%   |
| Wacom                           | 1         | 0.05%   |
| TRENDnet                        | 1         | 0.05%   |
| Sitecom Europe                  | 1         | 0.05%   |
| NetGear                         | 1         | 0.05%   |
| Hewlett-Packard                 | 1         | 0.05%   |
| Fibocom                         | 1         | 0.05%   |
| AVM                             | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4331 802.11a/b/g/n                                       | 81        | 4.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 65        | 3.54%   |
| Intel Wi-Fi 6 AX201                                                  | 65        | 3.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 61        | 3.32%   |
| Intel Wireless 8260                                                  | 60        | 3.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 55        | 3%      |
| Intel Wireless 7265                                                  | 53        | 2.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 52        | 2.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 49        | 2.67%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 49        | 2.67%   |
| Intel Wireless 8265 / 8275                                           | 48        | 2.61%   |
| Intel Wireless 7260                                                  | 46        | 2.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 45        | 2.45%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 44        | 2.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 40        | 2.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 40        | 2.18%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 38        | 2.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 37        | 2.02%   |
| Broadcom BCM43142 802.11b/g/n                                        | 36        | 1.96%   |
| Intel Wi-Fi 6 AX200                                                  | 34        | 1.85%   |
| Intel Wireless 3165                                                  | 30        | 1.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 29        | 1.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 27        | 1.47%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 22        | 1.2%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 21        | 1.14%   |
| Intel Wireless 3160                                                  | 20        | 1.09%   |
| Intel Centrino Advanced-N 6235                                       | 20        | 1.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 20        | 1.09%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 19        | 1.03%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 18        | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 18        | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 18        | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 17        | 0.93%   |
| Intel Centrino Advanced-N 6200                                       | 16        | 0.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 15        | 0.82%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 14        | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 14        | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 14        | 0.76%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 14        | 0.76%   |
| Intel Centrino Wireless-N 2230                                       | 13        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 678       | 48.81%  |
| Intel                         | 269       | 19.37%  |
| Broadcom                      | 151       | 10.87%  |
| Qualcomm Atheros              | 95        | 6.84%   |
| Nvidia                        | 39        | 2.81%   |
| Marvell Technology Group      | 33        | 2.38%   |
| Samsung Electronics           | 18        | 1.3%    |
| ASIX Electronics              | 17        | 1.22%   |
| Broadcom Limited              | 15        | 1.08%   |
| Xiaomi                        | 12        | 0.86%   |
| MediaTek                      | 10        | 0.72%   |
| Huawei Technologies           | 7         | 0.5%    |
| Apple                         | 5         | 0.36%   |
| Qualcomm                      | 4         | 0.29%   |
| Lenovo                        | 4         | 0.29%   |
| Google                        | 4         | 0.29%   |
| OPPO Electronics              | 3         | 0.22%   |
| JMicron Technology            | 3         | 0.22%   |
| ICS Advent                    | 3         | 0.22%   |
| Motorola PCS                  | 2         | 0.14%   |
| Hewlett-Packard               | 2         | 0.14%   |
| D-Link                        | 2         | 0.14%   |
| Attansic Technology           | 2         | 0.14%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.07%   |
| VIA Technologies              | 1         | 0.07%   |
| OnePlus Technology (Shenzhen) | 1         | 0.07%   |
| NetGear                       | 1         | 0.07%   |
| Motorcomm Microelectronics.   | 1         | 0.07%   |
| LSI                           | 1         | 0.07%   |
| Linksys                       | 1         | 0.07%   |
| LG Electronics                | 1         | 0.07%   |
| HMD Global                    | 1         | 0.07%   |
| DisplayLink                   | 1         | 0.07%   |
| ADMtek                        | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 465       | 33.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 168       | 12%     |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 76        | 5.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 57        | 4.07%   |
| Nvidia MCP79 Ethernet                                                          | 35        | 2.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 30        | 2.14%   |
| Intel Ethernet Connection I219-LM                                              | 23        | 1.64%   |
| Intel 82577LM Gigabit Network Connection                                       | 21        | 1.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 20        | 1.43%   |
| Intel Ethernet Connection I218-LM                                              | 20        | 1.43%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 20        | 1.43%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 17        | 1.21%   |
| Intel Ethernet Connection I217-LM                                              | 15        | 1.07%   |
| Intel Ethernet Connection (4) I219-LM                                          | 15        | 1.07%   |
| Intel Ethernet Connection (4) I219-V                                           | 14        | 1%      |
| Intel Ethernet Connection (3) I218-LM                                          | 14        | 1%      |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 14        | 1%      |
| ASIX AX88179 Gigabit Ethernet                                                  | 14        | 1%      |
| Samsung Galaxy series, misc. (tethering mode)                                  | 12        | 0.86%   |
| Intel Ethernet Connection I219-V                                               | 12        | 0.86%   |
| Intel 82567LM Gigabit Network Connection                                       | 12        | 0.86%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 11        | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 9         | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 9         | 0.64%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 9         | 0.64%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 8         | 0.57%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 8         | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 7         | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 7         | 0.5%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 7         | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 7         | 0.5%    |
| MediaTek Infinix HOT 50i                                                       | 7         | 0.5%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 7         | 0.5%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 7         | 0.5%    |
| Intel 82579V Gigabit Network Connection                                        | 7         | 0.5%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 6         | 0.43%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 6         | 0.43%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 6         | 0.43%   |
| Intel Ethernet Connection I217-V                                               | 6         | 0.43%   |
| Intel Ethernet Connection (13) I219-V                                          | 6         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1718      | 55.56%  |
| Ethernet | 1338      | 43.27%  |
| Modem    | 34        | 1.1%    |
| Unknown  | 2         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1444      | 81.81%  |
| Ethernet | 321       | 18.19%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1223      | 70.09%  |
| 1     | 483       | 27.68%  |
| 0     | 29        | 1.66%   |
| 3     | 10        | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 1270      | 71.83%  |
| Yes     | 497       | 28.11%  |
| Unknown | 1         | 0.06%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 572       | 37.93%  |
| Apple                           | 249       | 16.51%  |
| Realtek Semiconductor           | 160       | 10.61%  |
| Qualcomm Atheros Communications | 126       | 8.36%   |
| Broadcom                        | 74        | 4.91%   |
| Foxconn / Hon Hai               | 67        | 4.44%   |
| Lite-On Technology              | 62        | 4.11%   |
| IMC Networks                    | 53        | 3.51%   |
| Dell                            | 27        | 1.79%   |
| Hewlett-Packard                 | 26        | 1.72%   |
| Toshiba                         | 21        | 1.39%   |
| Cambridge Silicon Radio         | 20        | 1.33%   |
| Realtek                         | 14        | 0.93%   |
| Ralink                          | 14        | 0.93%   |
| Foxconn International           | 4         | 0.27%   |
| MediaTek                        | 3         | 0.2%    |
| ASUSTek Computer                | 3         | 0.2%    |
| Qcom                            | 2         | 0.13%   |
| Askey Computer                  | 2         | 0.13%   |
| Alps Electric                   | 2         | 0.13%   |
| USI                             | 1         | 0.07%   |
| Taiyo Yuden                     | 1         | 0.07%   |
| Ralink Technology               | 1         | 0.07%   |
| Opticis                         | 1         | 0.07%   |
| Logitech                        | 1         | 0.07%   |
| Fujitsu                         | 1         | 0.07%   |
| Unknown                         | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 263       | 17.44%  |
| Apple Bluetooth Host Controller                                                     | 138       | 9.15%   |
| Intel AX201 Bluetooth                                                               | 107       | 7.1%    |
| Realtek Bluetooth Radio                                                             | 91        | 6.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 88        | 5.84%   |
| Apple Bluetooth USB Host Controller                                                 | 85        | 5.64%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 66        | 4.38%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 45        | 2.98%   |
| Intel AX200 Bluetooth                                                               | 34        | 2.25%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 30        | 1.99%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 24        | 1.59%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 21        | 1.39%   |
| IMC Networks Wireless_Device                                                        | 20        | 1.33%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 20        | 1.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 20        | 1.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 16        | 1.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 16        | 1.06%   |
| Dell DW375 Bluetooth Module                                                         | 16        | 1.06%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 16        | 1.06%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 15        | 0.99%   |
| Realtek Bluetooth Radio                                                             | 14        | 0.93%   |
| Ralink RT3290 Bluetooth                                                             | 14        | 0.93%   |
| Lite-On Bluetooth Device                                                            | 14        | 0.93%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 14        | 0.93%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 13        | 0.86%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 13        | 0.86%   |
| IMC Networks Bluetooth Radio                                                        | 12        | 0.8%    |
| Apple Bluetooth HCI                                                                 | 12        | 0.8%    |
| Realtek RTL8821A Bluetooth                                                          | 11        | 0.73%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 11        | 0.73%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 11        | 0.73%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 10        | 0.66%   |
| Intel Bluetooth Device                                                              | 9         | 0.6%    |
| Intel AX210 Bluetooth                                                               | 8         | 0.53%   |
| IMC Networks Bluetooth Device                                                       | 8         | 0.53%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 8         | 0.53%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 7         | 0.46%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 7         | 0.46%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 7         | 0.46%   |
| Lite-On Wireless_Device                                                             | 6         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1406      | 69.19%  |
| AMD                                  | 324       | 15.94%  |
| Nvidia                               | 229       | 11.27%  |
| C-Media Electronics                  | 11        | 0.54%   |
| Logitech                             | 9         | 0.44%   |
| Generalplus Technology               | 6         | 0.3%    |
| Realtek Semiconductor                | 4         | 0.2%    |
| Texas Instruments                    | 3         | 0.15%   |
| GN Netcom                            | 3         | 0.15%   |
| JMTek                                | 2         | 0.1%    |
| Huawei Technologies                  | 2         | 0.1%    |
| Hewlett-Packard                      | 2         | 0.1%    |
| ESS Technology                       | 2         | 0.1%    |
| Dell                                 | 2         | 0.1%    |
| BEHRINGER International              | 2         | 0.1%    |
| Apple                                | 2         | 0.1%    |
| YUAN High-Tech Development           | 1         | 0.05%   |
| VIA Technologies                     | 1         | 0.05%   |
| Trust                                | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.05%   |
| TerraTec Electronic                  | 1         | 0.05%   |
| TEAC                                 | 1         | 0.05%   |
| SteelSeries ApS                      | 1         | 0.05%   |
| Sony                                 | 1         | 0.05%   |
| Nordic Semiconductor ASA             | 1         | 0.05%   |
| No brand                             | 1         | 0.05%   |
| Native Instruments                   | 1         | 0.05%   |
| Midiplus                             | 1         | 0.05%   |
| Microsoft                            | 1         | 0.05%   |
| liyuany                              | 1         | 0.05%   |
| Lenovo                               | 1         | 0.05%   |
| Kingston Technology                  | 1         | 0.05%   |
| JBL                                  | 1         | 0.05%   |
| HECATE G4 TE GAMING HEADSET          | 1         | 0.05%   |
| Guillemot                            | 1         | 0.05%   |
| Goldvish                             | 1         | 0.05%   |
| fifine Microphones                   | 1         | 0.05%   |
| Corsair                              | 1         | 0.05%   |
| Cambridge Audio                      | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 210       | 8.38%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 190       | 7.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 152       | 6.06%   |
| AMD Ryzen HD Audio Controller                                                                     | 144       | 5.74%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 96        | 3.83%   |
| Intel 8 Series HD Audio Controller                                                                | 96        | 3.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 88        | 3.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 85        | 3.39%   |
| Intel Broadwell-U Audio Controller                                                                | 78        | 3.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 77        | 3.07%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 75        | 2.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 68        | 2.71%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 68        | 2.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 53        | 2.11%   |
| AMD FCH Azalia Controller                                                                         | 52        | 2.07%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 48        | 1.91%   |
| AMD Kabini HDMI/DP Audio                                                                          | 46        | 1.83%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 44        | 1.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 43        | 1.72%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 41        | 1.64%   |
| Nvidia MCP79 High Definition Audio                                                                | 35        | 1.4%    |
| Intel Cannon Lake PCH cAVS                                                                        | 33        | 1.32%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 30        | 1.2%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 26        | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 26        | 1.04%   |
| AMD High Definition Audio Controller                                                              | 24        | 0.96%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 23        | 0.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 22        | 0.88%   |
| Intel CM238 HD Audio Controller                                                                   | 22        | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 22        | 0.88%   |
| Nvidia MCP89 High Definition Audio                                                                | 20        | 0.8%    |
| Intel Comet Lake PCH cAVS                                                                         | 20        | 0.8%    |
| AMD Radeon High Definition Audio Controller                                                       | 19        | 0.76%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 18        | 0.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 18        | 0.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 16        | 0.64%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 16        | 0.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 16        | 0.64%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 15        | 0.6%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 14        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 135       | 28.91%  |
| SK hynix            | 91        | 19.49%  |
| Micron Technology   | 67        | 14.35%  |
| Kingston            | 39        | 8.35%   |
| Unknown             | 25        | 5.35%   |
| Crucial             | 20        | 4.28%   |
| Elpida              | 18        | 3.85%   |
| Unknown (ABCD)      | 10        | 2.14%   |
| Ramaxel Technology  | 10        | 2.14%   |
| A-DATA Technology   | 9         | 1.93%   |
| Corsair             | 5         | 1.07%   |
| Smart               | 4         | 0.86%   |
| Transcend           | 3         | 0.64%   |
| GSkill              | 3         | 0.64%   |
| G.Skill             | 3         | 0.64%   |
| Timetec             | 2         | 0.43%   |
| Nanya Technology    | 2         | 0.43%   |
| Multilaser          | 2         | 0.43%   |
| Unknown             | 2         | 0.43%   |
| Unknown (0x0C26)    | 1         | 0.21%   |
| Toshiba             | 1         | 0.21%   |
| Team                | 1         | 0.21%   |
| Smart Brazil        | 1         | 0.21%   |
| SHARETRONIC         | 1         | 0.21%   |
| Qimonda             | 1         | 0.21%   |
| pqi                 | 1         | 0.21%   |
| PNY                 | 1         | 0.21%   |
| Patriot             | 1         | 0.21%   |
| Melco               | 1         | 0.21%   |
| Magnum Tech         | 1         | 0.21%   |
| Kllisre             | 1         | 0.21%   |
| Avant               | 1         | 0.21%   |
| ASint Technology    | 1         | 0.21%   |
| AMD                 | 1         | 0.21%   |
| Aeneon              | 1         | 0.21%   |
| A Force             | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 9         | 1.81%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 1.81%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 1.61%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 1.41%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 5         | 1.01%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s            | 5         | 1.01%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 4         | 0.8%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.8%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.8%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.8%    |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 4         | 0.8%    |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 4         | 0.8%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.8%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 4         | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.8%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                   | 3         | 0.6%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 0.6%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 3         | 0.6%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GiB SODIMM DDR3 2667MT/s          | 3         | 0.6%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.6%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.6%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.6%    |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                      | 3         | 0.6%    |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s         | 3         | 0.6%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.6%    |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 3         | 0.6%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.6%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.6%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 3         | 0.6%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 3         | 0.6%    |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 3         | 0.6%    |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 3         | 0.6%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 0.6%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 3         | 0.6%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.6%    |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 3         | 0.6%    |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR 800MT/s              | 2         | 0.4%    |
| Smart RAM SG564283FG8NWKF-Z1 1024MB SODIMM DDR2 800MT/s          | 2         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 156       | 40.1%   |
| DDR3   | 156       | 40.1%   |
| LPDDR4 | 31        | 7.97%   |
| DDR2   | 18        | 4.63%   |
| LPDDR3 | 15        | 3.86%   |
| SDRAM  | 5         | 1.29%   |
| LPDDR5 | 5         | 1.29%   |
| DDR5   | 3         | 0.77%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 340       | 86.51%  |
| Row Of Chips | 45        | 11.45%  |
| Chip         | 4         | 1.02%   |
| DIMM         | 3         | 0.76%   |
| Unknown      | 1         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 178       | 40.09%  |
| 4096  | 135       | 30.41%  |
| 2048  | 64        | 14.41%  |
| 16384 | 44        | 9.91%   |
| 1024  | 12        | 2.7%    |
| 32768 | 11        | 2.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 103       | 24.01%  |
| 2667    | 79        | 18.41%  |
| 3200    | 64        | 14.92%  |
| 2133    | 32        | 7.46%   |
| 2400    | 28        | 6.53%   |
| 1333    | 23        | 5.36%   |
| 1334    | 15        | 3.5%    |
| 4267    | 13        | 3.03%   |
| 1067    | 11        | 2.56%   |
| 667     | 10        | 2.33%   |
| 800     | 9         | 2.1%    |
| 8400    | 6         | 1.4%    |
| 1867    | 6         | 1.4%    |
| 1066    | 5         | 1.17%   |
| 3266    | 4         | 0.93%   |
| 4266    | 3         | 0.7%    |
| 4199    | 3         | 0.7%    |
| 7500    | 2         | 0.47%   |
| 6400    | 2         | 0.47%   |
| 4800    | 2         | 0.47%   |
| 2048    | 2         | 0.47%   |
| 975     | 2         | 0.47%   |
| Unknown | 2         | 0.47%   |
| 8533    | 1         | 0.23%   |
| 5600    | 1         | 0.23%   |
| 3733    | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Canon                           | 4         | 22.22%  |
| Brother Industries              | 3         | 16.67%  |
| Xerox                           | 2         | 11.11%  |
| Seiko Epson                     | 2         | 11.11%  |
| Samsung Electronics             | 2         | 11.11%  |
| Hewlett-Packard                 | 2         | 11.11%  |
| Prolific Technology             | 1         | 5.56%   |
| Lexmark International           | 1         | 5.56%   |
| cab Produkttechnik GmbH & Co KG | 1         | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Xerox Phaser 3610                        | 1         | 5.56%   |
| Xerox Phaser 3320                        | 1         | 5.56%   |
| Seiko Epson L355 Series                  | 1         | 5.56%   |
| Seiko Epson EPSON XP-205 207 Series      | 1         | 5.56%   |
| Samsung M2020 Series                     | 1         | 5.56%   |
| Samsung C48x Series                      | 1         | 5.56%   |
| Prolific PL2305 Parallel Port            | 1         | 5.56%   |
| Lexmark International f+ imaging M40adn  | 1         | 5.56%   |
| HP Deskjet F4500 series                  | 1         | 5.56%   |
| HP DeskJet 2600 series                   | 1         | 5.56%   |
| Canon PIXMA MG2500 Series                | 1         | 5.56%   |
| Canon LiDE 400                           | 1         | 5.56%   |
| Canon LBP3360                            | 1         | 5.56%   |
| Canon G3000 series                       | 1         | 5.56%   |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 5.56%   |
| Brother MFC-T800W                        | 1         | 5.56%   |
| Brother HL-2250DN Laser Printer          | 1         | 5.56%   |
| Brother HL-1110 series                   | 1         | 5.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 50%     |
| Canon CanoScan LiDE 110                                 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 311       | 19.85%  |
| Apple                                  | 189       | 12.06%  |
| Realtek Semiconductor                  | 133       | 8.49%   |
| IMC Networks                           | 118       | 7.53%   |
| Microdia                               | 108       | 6.89%   |
| Bison Electronics                      | 104       | 6.64%   |
| Sunplus Innovation Technology          | 92        | 5.87%   |
| Quanta                                 | 88        | 5.62%   |
| Cheng Uei Precision Industry (Foxlink) | 72        | 4.59%   |
| Suyin                                  | 56        | 3.57%   |
| Syntek                                 | 49        | 3.13%   |
| Silicon Motion                         | 32        | 2.04%   |
| Lite-On Technology                     | 32        | 2.04%   |
| Luxvisions Innotech Limited            | 27        | 1.72%   |
| Alcor Micro                            | 26        | 1.66%   |
| Ricoh                                  | 15        | 0.96%   |
| Lenovo                                 | 12        | 0.77%   |
| Samsung Electronics                    | 8         | 0.51%   |
| Logitech                               | 7         | 0.45%   |
| Importek                               | 7         | 0.45%   |
| Primax Electronics                     | 6         | 0.38%   |
| SunplusIT                              | 5         | 0.32%   |
| Sonix Technology                       | 5         | 0.32%   |
| ShineTech                              | 5         | 0.32%   |
| ALi                                    | 5         | 0.32%   |
| Acer                                   | 5         | 0.32%   |
| LG Electronics                         | 4         | 0.26%   |
| Foxconn / Hon Hai                      | 4         | 0.26%   |
| Y Media                                | 3         | 0.19%   |
| Intel                                  | 3         | 0.19%   |
| icSpring                               | 3         | 0.19%   |
| Unknown                                | 3         | 0.19%   |
| Z-Star Microelectronics                | 2         | 0.13%   |
| Sunplus Technology                     | 2         | 0.13%   |
| Shine-optics                           | 2         | 0.13%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.13%   |
| KYE Systems (Mouse Systems)            | 2         | 0.13%   |
| kingcome                               | 2         | 0.13%   |
| GEMBIRD                                | 2         | 0.13%   |
| webcam                                 | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Apple FaceTime HD Camera                | 76        | 4.82%   |
| Chicony Integrated Camera               | 65        | 4.12%   |
| Apple Built-in iSight                   | 56        | 3.55%   |
| Microdia Integrated_Webcam_HD           | 36        | 2.28%   |
| Chicony HD WebCam                       | 36        | 2.28%   |
| IMC Networks USB2.0 HD UVC WebCam       | 35        | 2.22%   |
| Realtek Integrated_Webcam_HD            | 32        | 2.03%   |
| IMC Networks Integrated Camera          | 30        | 1.9%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 27        | 1.71%   |
| Sunplus Integrated_Webcam_HD            | 24        | 1.52%   |
| Syntek Integrated Camera                | 23        | 1.46%   |
| Bison Integrated Camera                 | 18        | 1.14%   |
| Apple FaceTime Camera                   | 16        | 1.01%   |
| Microdia Integrated Webcam              | 15        | 0.95%   |
| Lite-On Integrated Camera               | 15        | 0.95%   |
| Apple FaceTime HD Camera (Built-in)     | 15        | 0.95%   |
| Quanta HP Webcam                        | 14        | 0.89%   |
| Chicony HP Truevision HD                | 14        | 0.89%   |
| Bison Lenovo EasyCamera                 | 14        | 0.89%   |
| Realtek USB Camera                      | 13        | 0.82%   |
| Chicony HP TrueVision HD Camera         | 13        | 0.82%   |
| Syntek Lenovo EasyCamera                | 12        | 0.76%   |
| Syntek EasyCamera                       | 12        | 0.76%   |
| Quanta HP TrueVision HD Camera          | 12        | 0.76%   |
| Chicony HP HD Webcam [Fixed]            | 12        | 0.76%   |
| Chicony EasyCamera                      | 12        | 0.76%   |
| Sunplus HD WebCam                       | 11        | 0.7%    |
| Realtek Integrated Webcam               | 11        | 0.7%    |
| Quanta HD User Facing                   | 11        | 0.7%    |
| Realtek USB2.0 HD UVC WebCam            | 10        | 0.63%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 10        | 0.63%   |
| Bison SunplusIT Integrated Camera       | 10        | 0.63%   |
| Chicony USB2.0 VGA UVC WebCam           | 9         | 0.57%   |
| Samsung Galaxy series, misc. (MTP mode) | 8         | 0.51%   |
| Quanta HD Camera                        | 8         | 0.51%   |
| Chicony VGA WebCam                      | 8         | 0.51%   |
| Chicony TOSHIBA Web Camera - HD         | 8         | 0.51%   |
| Chicony Lenovo EasyCamera               | 8         | 0.51%   |
| Chicony HP HD Webcam                    | 8         | 0.51%   |
| Chicony HP HD Camera                    | 8         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 104       | 40.31%  |
| Synaptics                  | 50        | 19.38%  |
| Shenzhen Goodix Technology | 42        | 16.28%  |
| LighTuning Technology      | 18        | 6.98%   |
| Upek                       | 13        | 5.04%   |
| Elan Microelectronics      | 13        | 5.04%   |
| AuthenTec                  | 13        | 5.04%   |
| STMicroelectronics         | 2         | 0.78%   |
| Focal-systems.Corp         | 2         | 0.78%   |
| Samsung Electronics        | 1         | 0.39%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 33        | 12.79%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 22        | 8.53%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 16        | 6.2%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 5.04%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 5.04%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 5.04%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 4.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 3.88%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 3.49%   |
| Elan ELAN:Fingerprint                                                      | 9         | 3.49%   |
| Validity Sensors VFS491                                                    | 8         | 3.1%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 3.1%    |
| Validity Sensors Synaptics WBDI                                            | 6         | 2.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 2.33%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.94%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 1.94%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 1.94%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.94%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 1.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.55%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.55%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 1.55%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.55%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.55%   |
| AuthenTec AES2810                                                          | 4         | 1.55%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 1.16%   |
| Synaptics  WBDI                                                            | 3         | 1.16%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.16%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.78%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.78%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 0.78%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 0.78%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.78%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 0.78%   |
| AuthenTec AES1600                                                          | 2         | 0.78%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.39%   |
| Synaptics WBDI                                                             | 1         | 0.39%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.39%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.39%   |
| Synaptics Prometheus Fingerprint Reader                                    | 1         | 0.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 62        | 56.36%  |
| Alcor Micro           | 25        | 22.73%  |
| Upek                  | 8         | 7.27%   |
| O2 Micro              | 7         | 6.36%   |
| Lenovo                | 6         | 5.45%   |
| SCM Microsystems      | 1         | 0.91%   |
| Gemalto (was Gemplus) | 1         | 0.91%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 27        | 24.55%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 25        | 22.73%  |
| Broadcom 5880                                                                | 15        | 13.64%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 10%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 7.27%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 5.45%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 5.45%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 6         | 5.45%   |
| Broadcom 58200                                                               | 3         | 2.73%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.91%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.91%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.91%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1083      | 61.46%  |
| 1     | 542       | 30.76%  |
| 2     | 122       | 6.92%   |
| 3     | 13        | 0.74%   |
| 9     | 1         | 0.06%   |
| 7     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 256       | 30.81%  |
| Net/wireless             | 143       | 17.21%  |
| Graphics card            | 138       | 16.61%  |
| Multimedia controller    | 108       | 13%     |
| Chipcard                 | 107       | 12.88%  |
| Storage                  | 18        | 2.17%   |
| Bluetooth                | 16        | 1.93%   |
| Net/ethernet             | 15        | 1.81%   |
| Camera                   | 14        | 1.68%   |
| Sound                    | 5         | 0.6%    |
| Card reader              | 4         | 0.48%   |
| Communication controller | 3         | 0.36%   |
| Storage/ata              | 1         | 0.12%   |
| Network                  | 1         | 0.12%   |
| Modem                    | 1         | 0.12%   |
| Flash memory             | 1         | 0.12%   |

