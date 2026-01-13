Elementary - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Elementary.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary/Desktop/README.md) and [notebooks](/Dist/Elementary/Notebook/README.md).

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

Total: 3995

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 15 Notebook PC              | Notebook    | [15a218e733](https://linux-hardware.org/?probe=15a218e733) | Dec 31, 2025 |
| Lenovo        | LOQ 15APH8 82XT             | Notebook    | [f58d4c35ba](https://linux-hardware.org/?probe=f58d4c35ba) | Dec 31, 2025 |
| Apple         | Mac-F2218FC8                | All in one  | [fe8980429f](https://linux-hardware.org/?probe=fe8980429f) | Dec 30, 2025 |
| IceWhale T... | ZBB001-BK30032 ZMB          | Desktop     | [89a72c23bf](https://linux-hardware.org/?probe=89a72c23bf) | Dec 29, 2025 |
| Dell          | Latitude E5550              | Notebook    | [636764d2b2](https://linux-hardware.org/?probe=636764d2b2) | Dec 28, 2025 |
| Apple         | Mac-F2268DC8                | All in one  | [ebcb061bf0](https://linux-hardware.org/?probe=ebcb061bf0) | Dec 26, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [5c77a53c22](https://linux-hardware.org/?probe=5c77a53c22) | Dec 25, 2025 |
| ASUSTek       | K93SV                       | Notebook    | [45c8a2efd7](https://linux-hardware.org/?probe=45c8a2efd7) | Dec 25, 2025 |
| Dell          | XPS 15 9530                 | Notebook    | [3d19ddb3ef](https://linux-hardware.org/?probe=3d19ddb3ef) | Dec 25, 2025 |
| Dell          | XPS 15 9530                 | Notebook    | [75e5963f66](https://linux-hardware.org/?probe=75e5963f66) | Dec 25, 2025 |
| Dell          | 0773VG A00                  | Desktop     | [04673177d3](https://linux-hardware.org/?probe=04673177d3) | Dec 24, 2025 |
| ASUSTek       | K93SV                       | Notebook    | [468f690e44](https://linux-hardware.org/?probe=468f690e44) | Dec 23, 2025 |
| Casper        | W7x0S                       | Notebook    | [2620e4e75d](https://linux-hardware.org/?probe=2620e4e75d) | Dec 21, 2025 |
| Timi          | TM1701                      | Notebook    | [e791021e4c](https://linux-hardware.org/?probe=e791021e4c) | Dec 20, 2025 |
| Lenovo        | G50-80 80L0                 | Notebook    | [0fdc5cbe39](https://linux-hardware.org/?probe=0fdc5cbe39) | Dec 20, 2025 |
| Apple         | Mac-F2268CC8                | All in one  | [3641b82491](https://linux-hardware.org/?probe=3641b82491) | Dec 19, 2025 |
| Acer          | Veriton Z4640G              | All in one  | [b93898c75e](https://linux-hardware.org/?probe=b93898c75e) | Dec 18, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [68c7d0358e](https://linux-hardware.org/?probe=68c7d0358e) | Dec 17, 2025 |
| Apple         | MacBookPro11,1              | Notebook    | [df8461eb0e](https://linux-hardware.org/?probe=df8461eb0e) | Dec 17, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [96d1e843c6](https://linux-hardware.org/?probe=96d1e843c6) | Dec 17, 2025 |
| Dell          | Latitude 5580               | Notebook    | [3c615a7827](https://linux-hardware.org/?probe=3c615a7827) | Dec 16, 2025 |
| Dell          | Vostro1710                  | Notebook    | [c89e03644c](https://linux-hardware.org/?probe=c89e03644c) | Dec 15, 2025 |
| Acer          | Aspire E1-572               | Notebook    | [baad0ebb61](https://linux-hardware.org/?probe=baad0ebb61) | Dec 15, 2025 |
| Dell          | Latitude 5580               | Notebook    | [577d0c916a](https://linux-hardware.org/?probe=577d0c916a) | Dec 15, 2025 |
| Dell          | Latitude E5470              | Notebook    | [e5400c2e38](https://linux-hardware.org/?probe=e5400c2e38) | Dec 13, 2025 |
| HP            | Pavilion dv6                | Notebook    | [eff37a462b](https://linux-hardware.org/?probe=eff37a462b) | Dec 12, 2025 |
| HP            | Pavilion dv7                | Notebook    | [514e74de8d](https://linux-hardware.org/?probe=514e74de8d) | Dec 12, 2025 |
| HP            | Laptop 15-bs1xx             | Notebook    | [7f123d305e](https://linux-hardware.org/?probe=7f123d305e) | Dec 12, 2025 |
| Apple         | MacBookPro9,1               | Notebook    | [551fe38305](https://linux-hardware.org/?probe=551fe38305) | Dec 08, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [dc1e0eff2b](https://linux-hardware.org/?probe=dc1e0eff2b) | Dec 07, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [a077455bdc](https://linux-hardware.org/?probe=a077455bdc) | Dec 07, 2025 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [0ea33de05c](https://linux-hardware.org/?probe=0ea33de05c) | Dec 07, 2025 |
| ASUSTek       | GL752VW                     | Notebook    | [ff85424fb4](https://linux-hardware.org/?probe=ff85424fb4) | Dec 06, 2025 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [479ecf2419](https://linux-hardware.org/?probe=479ecf2419) | Dec 06, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [6a37e56e72](https://linux-hardware.org/?probe=6a37e56e72) | Dec 05, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [f54a4a4f69](https://linux-hardware.org/?probe=f54a4a4f69) | Dec 05, 2025 |
| Biostar       | H61MLV2                     | Desktop     | [d6a9c79bdd](https://linux-hardware.org/?probe=d6a9c79bdd) | Dec 05, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [eb6e2fa808](https://linux-hardware.org/?probe=eb6e2fa808) | Dec 04, 2025 |
| Dell          | Latitude 7480               | Notebook    | [d8dd6efc6f](https://linux-hardware.org/?probe=d8dd6efc6f) | Dec 03, 2025 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [25c8c68d2b](https://linux-hardware.org/?probe=25c8c68d2b) | Dec 03, 2025 |
| Dell          | Vostro1710                  | Notebook    | [03fd0bc5e8](https://linux-hardware.org/?probe=03fd0bc5e8) | Dec 02, 2025 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [9e77f10d86](https://linux-hardware.org/?probe=9e77f10d86) | Dec 02, 2025 |
| Dell          | Latitude 7480               | Notebook    | [791cf3c99f](https://linux-hardware.org/?probe=791cf3c99f) | Dec 02, 2025 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [a110c5abe4](https://linux-hardware.org/?probe=a110c5abe4) | Dec 02, 2025 |
| Intel         | Unknown                     | Desktop     | [8a2554c6a8](https://linux-hardware.org/?probe=8a2554c6a8) | Nov 30, 2025 |
| ASUSTek       | UX303LB                     | Notebook    | [4926819f4f](https://linux-hardware.org/?probe=4926819f4f) | Nov 30, 2025 |
| ASUSTek       | UX303LB                     | Notebook    | [8bc2e68390](https://linux-hardware.org/?probe=8bc2e68390) | Nov 30, 2025 |
| Dell          | XPS 15 9500                 | Notebook    | [a2bf61d881](https://linux-hardware.org/?probe=a2bf61d881) | Nov 30, 2025 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | Notebook    | [679084cf58](https://linux-hardware.org/?probe=679084cf58) | Nov 29, 2025 |
| ASUSTek       | CM6870                      | Desktop     | [c626fb7e6a](https://linux-hardware.org/?probe=c626fb7e6a) | Nov 29, 2025 |
| Acer          | Aspire 7715Z                | Notebook    | [3ee36053d6](https://linux-hardware.org/?probe=3ee36053d6) | Nov 29, 2025 |
| Lenovo        | ThinkPad T14 Gen 4 21HES... | Notebook    | [9c47040b32](https://linux-hardware.org/?probe=9c47040b32) | Nov 29, 2025 |
| Lenovo        | ThinkPad T14 Gen 4 21HES... | Notebook    | [4a51a30c0c](https://linux-hardware.org/?probe=4a51a30c0c) | Nov 29, 2025 |
| Apple         | MacBookAir5,2               | Notebook    | [313ee19aab](https://linux-hardware.org/?probe=313ee19aab) | Nov 27, 2025 |
| Intel         | H55                         | Desktop     | [64547cb270](https://linux-hardware.org/?probe=64547cb270) | Nov 24, 2025 |
| HP            | Laptop 15-bs1xx             | Notebook    | [38eaee6ffe](https://linux-hardware.org/?probe=38eaee6ffe) | Nov 24, 2025 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [02bb00984c](https://linux-hardware.org/?probe=02bb00984c) | Nov 23, 2025 |
| Dell          | Inspiron 3541               | Notebook    | [3b7290f600](https://linux-hardware.org/?probe=3b7290f600) | Nov 23, 2025 |
| Dell          | Inspiron 3541               | Notebook    | [14add25ddb](https://linux-hardware.org/?probe=14add25ddb) | Nov 23, 2025 |
| Intel         | H55                         | Desktop     | [03919b1a0c](https://linux-hardware.org/?probe=03919b1a0c) | Nov 22, 2025 |
| Timi          | TM1701                      | Notebook    | [9298267905](https://linux-hardware.org/?probe=9298267905) | Nov 22, 2025 |
| Apple         | MacBookPro7,1               | Notebook    | [435b4312b6](https://linux-hardware.org/?probe=435b4312b6) | Nov 21, 2025 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [60c3603a43](https://linux-hardware.org/?probe=60c3603a43) | Nov 21, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [21479e5252](https://linux-hardware.org/?probe=21479e5252) | Nov 21, 2025 |
| Apple         | MacBookPro7,1               | Notebook    | [7312ab1846](https://linux-hardware.org/?probe=7312ab1846) | Nov 21, 2025 |
| Lenovo        | ThinkPad T490 20N2004HAD    | Notebook    | [673ef1ec1f](https://linux-hardware.org/?probe=673ef1ec1f) | Nov 20, 2025 |
| Acer          | Aspire 5755                 | Notebook    | [2d5f49bf19](https://linux-hardware.org/?probe=2d5f49bf19) | Nov 20, 2025 |
| Google        | Kefka                       | Notebook    | [18a8d258c8](https://linux-hardware.org/?probe=18a8d258c8) | Nov 19, 2025 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | Desktop     | [715c8abc74](https://linux-hardware.org/?probe=715c8abc74) | Nov 18, 2025 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | Desktop     | [e757512b85](https://linux-hardware.org/?probe=e757512b85) | Nov 18, 2025 |
| Dell          | Inspiron 15-3567            | Notebook    | [79b85f3ced](https://linux-hardware.org/?probe=79b85f3ced) | Nov 18, 2025 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [ab107435ca](https://linux-hardware.org/?probe=ab107435ca) | Nov 18, 2025 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [9a20fcf071](https://linux-hardware.org/?probe=9a20fcf071) | Nov 17, 2025 |
| Apple         | MacBookPro11,2              | Notebook    | [097647805e](https://linux-hardware.org/?probe=097647805e) | Nov 17, 2025 |
| Dell          | Latitude E5470              | Notebook    | [8fd76cb9e2](https://linux-hardware.org/?probe=8fd76cb9e2) | Nov 17, 2025 |
| Dell          | Latitude E5470              | Notebook    | [1d15cc30a6](https://linux-hardware.org/?probe=1d15cc30a6) | Nov 17, 2025 |
| Chuwi         | CoreBook X                  | Notebook    | [e938f7de5a](https://linux-hardware.org/?probe=e938f7de5a) | Nov 16, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [d713ff600d](https://linux-hardware.org/?probe=d713ff600d) | Nov 15, 2025 |
| Timi          | TM1701                      | Notebook    | [bc38ca3830](https://linux-hardware.org/?probe=bc38ca3830) | Nov 15, 2025 |
| Lenovo        | ThinkPad T490 20N2004HAD    | Notebook    | [50eec0b73e](https://linux-hardware.org/?probe=50eec0b73e) | Nov 14, 2025 |
| ASRock        | M3A UCC                     | Desktop     | [731a345406](https://linux-hardware.org/?probe=731a345406) | Nov 13, 2025 |
| ASUSTek       | K30BF_M32BF                 | Desktop     | [9c576d9df2](https://linux-hardware.org/?probe=9c576d9df2) | Nov 10, 2025 |
| HP            | Pavilion 14                 | Notebook    | [777782644a](https://linux-hardware.org/?probe=777782644a) | Nov 10, 2025 |
| Lenovo        | Yoga Pro 16 IAH10 83L0      | Notebook    | [a8872c086c](https://linux-hardware.org/?probe=a8872c086c) | Nov 09, 2025 |
| HP            | Pavilion 17                 | Notebook    | [97d0bd94a2](https://linux-hardware.org/?probe=97d0bd94a2) | Nov 08, 2025 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [b7005bcb7d](https://linux-hardware.org/?probe=b7005bcb7d) | Nov 08, 2025 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [aac0546a3d](https://linux-hardware.org/?probe=aac0546a3d) | Nov 08, 2025 |
| Dell          | Latitude 7275               | Tablet      | [d2c54226ce](https://linux-hardware.org/?probe=d2c54226ce) | Nov 07, 2025 |
| Dell          | Latitude 7275               | Tablet      | [4a75725427](https://linux-hardware.org/?probe=4a75725427) | Nov 07, 2025 |
| HP            | Pavilion dv6                | Notebook    | [f031d90e6c](https://linux-hardware.org/?probe=f031d90e6c) | Nov 05, 2025 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [d53eb4c9f3](https://linux-hardware.org/?probe=d53eb4c9f3) | Nov 05, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [711674bf50](https://linux-hardware.org/?probe=711674bf50) | Nov 05, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [f454fbffa6](https://linux-hardware.org/?probe=f454fbffa6) | Nov 04, 2025 |
| HP            | Pavilion dv6                | Notebook    | [4fb3464b2f](https://linux-hardware.org/?probe=4fb3464b2f) | Nov 03, 2025 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [73b9f7cc41](https://linux-hardware.org/?probe=73b9f7cc41) | Nov 02, 2025 |
| Dell          | Latitude 5320               | Notebook    | [8b12054048](https://linux-hardware.org/?probe=8b12054048) | Nov 02, 2025 |
| Thomson       | N14C4WH64                   | Notebook    | [1c383dd8ff](https://linux-hardware.org/?probe=1c383dd8ff) | Nov 02, 2025 |
| AZW           | U55                         | Mini pc     | [931b3c4023](https://linux-hardware.org/?probe=931b3c4023) | Nov 01, 2025 |
| ASRock        | B650 LiveMixer              | Desktop     | [4c9c02fe5f](https://linux-hardware.org/?probe=4c9c02fe5f) | Oct 31, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [232acaf17b](https://linux-hardware.org/?probe=232acaf17b) | Oct 31, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [cb1f3b706e](https://linux-hardware.org/?probe=cb1f3b706e) | Oct 30, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [9fdff90cbd](https://linux-hardware.org/?probe=9fdff90cbd) | Oct 30, 2025 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [c9f8bcf04c](https://linux-hardware.org/?probe=c9f8bcf04c) | Oct 30, 2025 |
| NEC Comput... | PC-VK24LXZCE                | Notebook    | [423e99f492](https://linux-hardware.org/?probe=423e99f492) | Oct 30, 2025 |
| HP            | Pavilion dv7                | Notebook    | [d15a848934](https://linux-hardware.org/?probe=d15a848934) | Oct 29, 2025 |
| AiStone       | X4SP4NAL                    | Notebook    | [0ba7202723](https://linux-hardware.org/?probe=0ba7202723) | Oct 28, 2025 |
| Apple         | MacBook6,1                  | Notebook    | [5a53960e9a](https://linux-hardware.org/?probe=5a53960e9a) | Oct 28, 2025 |
| Toshiba       | PORTEGE Z20t-B              | Notebook    | [c89b53f809](https://linux-hardware.org/?probe=c89b53f809) | Oct 28, 2025 |
| Acer          | Aspire E5-571G              | Notebook    | [b1a8be9b38](https://linux-hardware.org/?probe=b1a8be9b38) | Oct 26, 2025 |
| HP            | Pavilion 14                 | Notebook    | [e9c2f6c104](https://linux-hardware.org/?probe=e9c2f6c104) | Oct 26, 2025 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [2089a12776](https://linux-hardware.org/?probe=2089a12776) | Oct 26, 2025 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [0bce74370a](https://linux-hardware.org/?probe=0bce74370a) | Oct 24, 2025 |
| Apple         | MacBook6,1                  | Notebook    | [dbc8f4f3ab](https://linux-hardware.org/?probe=dbc8f4f3ab) | Oct 23, 2025 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c160c8268d](https://linux-hardware.org/?probe=c160c8268d) | Oct 22, 2025 |
| HP            | Pavilion 14                 | Notebook    | [17eefe70ce](https://linux-hardware.org/?probe=17eefe70ce) | Oct 21, 2025 |
| Microsoft     | Surface Pro 4               | Tablet      | [6d669763c6](https://linux-hardware.org/?probe=6d669763c6) | Oct 21, 2025 |
| Microsoft     | Surface Pro 4               | Tablet      | [606505f29a](https://linux-hardware.org/?probe=606505f29a) | Oct 21, 2025 |
| Gigabyte      | B760M DS3H DDR4             | Desktop     | [d47e2c04ff](https://linux-hardware.org/?probe=d47e2c04ff) | Oct 20, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [4eeb3ec1c1](https://linux-hardware.org/?probe=4eeb3ec1c1) | Oct 20, 2025 |
| Huanan        | X79-4MT (INTEL Xeon E5/C... | Desktop     | [0835c7c585](https://linux-hardware.org/?probe=0835c7c585) | Oct 20, 2025 |
| Dell          | 0XHGV1 A00                  | Desktop     | [d0fff0ec6e](https://linux-hardware.org/?probe=d0fff0ec6e) | Oct 19, 2025 |
| HP            | 198E                        | Desktop     | [8dfae8405a](https://linux-hardware.org/?probe=8dfae8405a) | Oct 19, 2025 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Notebook    | [6ec3d409c6](https://linux-hardware.org/?probe=6ec3d409c6) | Oct 18, 2025 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [f36ab90a13](https://linux-hardware.org/?probe=f36ab90a13) | Oct 17, 2025 |
| MSI           | H170A GAMING PRO            | Desktop     | [54178d60d8](https://linux-hardware.org/?probe=54178d60d8) | Oct 16, 2025 |
| ASUSTek       | ASUS EXPERTBOOK P5405CSA    | Notebook    | [9546ac0511](https://linux-hardware.org/?probe=9546ac0511) | Oct 15, 2025 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [ee2874cf10](https://linux-hardware.org/?probe=ee2874cf10) | Oct 15, 2025 |
| ASRock        | B850I Lightning WiFi        | Desktop     | [05ba465541](https://linux-hardware.org/?probe=05ba465541) | Oct 15, 2025 |
| HP            | Pavilion dv6                | Notebook    | [66f3b1f2e0](https://linux-hardware.org/?probe=66f3b1f2e0) | Oct 14, 2025 |
| OEM           | Unknown                     | Desktop     | [7cf476e7d5](https://linux-hardware.org/?probe=7cf476e7d5) | Oct 13, 2025 |
| MSI           | H170A GAMING PRO            | Desktop     | [714ce241a1](https://linux-hardware.org/?probe=714ce241a1) | Oct 13, 2025 |
| HP            | Pavilion g6                 | Notebook    | [57b550a6dc](https://linux-hardware.org/?probe=57b550a6dc) | Oct 10, 2025 |
| Dell          | Latitude E4310              | Notebook    | [99bd07799b](https://linux-hardware.org/?probe=99bd07799b) | Oct 10, 2025 |
| GPD           | P2 MAX                      | Notebook    | [8199ae0920](https://linux-hardware.org/?probe=8199ae0920) | Oct 10, 2025 |
| Apple         | MacBookPro10,1              | Notebook    | [e011121814](https://linux-hardware.org/?probe=e011121814) | Oct 07, 2025 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [a54f167e56](https://linux-hardware.org/?probe=a54f167e56) | Oct 06, 2025 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [11541f7d00](https://linux-hardware.org/?probe=11541f7d00) | Oct 06, 2025 |
| Intel         | NUC7i3DNB J57625-513        | Mini pc     | [22565cd1ae](https://linux-hardware.org/?probe=22565cd1ae) | Oct 04, 2025 |
| Dell          | Inspiron 7558               | Notebook    | [2e86658229](https://linux-hardware.org/?probe=2e86658229) | Oct 04, 2025 |
| Apple         | MacBook5,1                  | Notebook    | [28277351fb](https://linux-hardware.org/?probe=28277351fb) | Oct 04, 2025 |
| HP            | Pavilion dv7                | Notebook    | [d4a2d26dfe](https://linux-hardware.org/?probe=d4a2d26dfe) | Oct 04, 2025 |
| Dell          | Latitude E6420              | Notebook    | [5efb6c4bc2](https://linux-hardware.org/?probe=5efb6c4bc2) | Oct 04, 2025 |
| Sony          | SVF14415CLW                 | Notebook    | [b952b4f37a](https://linux-hardware.org/?probe=b952b4f37a) | Oct 03, 2025 |
| ASRock        | B450M Steel Legend          | Desktop     | [f0520b7456](https://linux-hardware.org/?probe=f0520b7456) | Oct 02, 2025 |
| Alienware     | 15 R3                       | Notebook    | [1a9c18a905](https://linux-hardware.org/?probe=1a9c18a905) | Oct 02, 2025 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [02fb5fc4d0](https://linux-hardware.org/?probe=02fb5fc4d0) | Oct 01, 2025 |
| Apple         | MacBookAir4,1               | Notebook    | [8b9a9abff8](https://linux-hardware.org/?probe=8b9a9abff8) | Sep 30, 2025 |
| Unknown       | Unknown                     | Notebook    | [6177830fc2](https://linux-hardware.org/?probe=6177830fc2) | Sep 28, 2025 |
| Unknown       | Unknown                     | Notebook    | [5f042fc8a2](https://linux-hardware.org/?probe=5f042fc8a2) | Sep 28, 2025 |
| HP            | ZBook 15                    | Notebook    | [787e1db37e](https://linux-hardware.org/?probe=787e1db37e) | Sep 27, 2025 |
| ASUSTek       | PRIME H310M-E R2.0/BR       | Desktop     | [de64494634](https://linux-hardware.org/?probe=de64494634) | Sep 27, 2025 |
| Lenovo        | ThinkPad T430 2349G4G       | Notebook    | [97f9cad42a](https://linux-hardware.org/?probe=97f9cad42a) | Sep 27, 2025 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [58f87f9fe5](https://linux-hardware.org/?probe=58f87f9fe5) | Sep 27, 2025 |
| Apple         | MacBook5,1                  | Notebook    | [2ae8722b75](https://linux-hardware.org/?probe=2ae8722b75) | Sep 26, 2025 |
| Apple         | MacBook5,1                  | Notebook    | [b45d8858f1](https://linux-hardware.org/?probe=b45d8858f1) | Sep 26, 2025 |
| Proline       | V1165C4                     | Notebook    | [4a0d7d946a](https://linux-hardware.org/?probe=4a0d7d946a) | Sep 25, 2025 |
| Proline       | V1165C4                     | Notebook    | [cfc2c58da9](https://linux-hardware.org/?probe=cfc2c58da9) | Sep 25, 2025 |
| HP            | ProBook 450 G6              | Notebook    | [aed4d96c7f](https://linux-hardware.org/?probe=aed4d96c7f) | Sep 25, 2025 |
| HP            | ProBook 450 G6              | Notebook    | [8b7bff69be](https://linux-hardware.org/?probe=8b7bff69be) | Sep 25, 2025 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [b813af4e2c](https://linux-hardware.org/?probe=b813af4e2c) | Sep 24, 2025 |
| eMachines     | G730                        | Notebook    | [a2ef1e57ba](https://linux-hardware.org/?probe=a2ef1e57ba) | Sep 24, 2025 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [9e761287ba](https://linux-hardware.org/?probe=9e761287ba) | Sep 24, 2025 |
| AZW           | GT-R                        | Notebook    | [e44ff94248](https://linux-hardware.org/?probe=e44ff94248) | Sep 23, 2025 |
| ASUSTek       | P8B75-V                     | Desktop     | [55a17b8069](https://linux-hardware.org/?probe=55a17b8069) | Sep 22, 2025 |
| ASUSTek       | P8B75-V                     | Desktop     | [5017ed6516](https://linux-hardware.org/?probe=5017ed6516) | Sep 22, 2025 |
| Pegatron      | A15                         | Notebook    | [68690e3c1c](https://linux-hardware.org/?probe=68690e3c1c) | Sep 22, 2025 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [9f6dce5f59](https://linux-hardware.org/?probe=9f6dce5f59) | Sep 21, 2025 |
| Acer          | Aspire E1-571G              | Notebook    | [59066ba058](https://linux-hardware.org/?probe=59066ba058) | Sep 21, 2025 |
| Acer          | Aspire E1-571G              | Notebook    | [6d1ba185b3](https://linux-hardware.org/?probe=6d1ba185b3) | Sep 21, 2025 |
| Lenovo        | Legion y540 15IRH 81SX      | Notebook    | [25fff34c25](https://linux-hardware.org/?probe=25fff34c25) | Sep 21, 2025 |
| HP            | 198E                        | Desktop     | [cfe7648075](https://linux-hardware.org/?probe=cfe7648075) | Sep 20, 2025 |
| Lenovo        | ThinkPad P14s Gen 5 AMD ... | Notebook    | [8818091701](https://linux-hardware.org/?probe=8818091701) | Sep 15, 2025 |
| Dell          | 0YJMC0 A02                  | Desktop     | [cbdc17bf9f](https://linux-hardware.org/?probe=cbdc17bf9f) | Sep 14, 2025 |
| Lenovo        | B590 20208                  | Notebook    | [8d909bb349](https://linux-hardware.org/?probe=8d909bb349) | Sep 12, 2025 |
| Apple         | MacBookAir5,2               | Notebook    | [16f403a6e1](https://linux-hardware.org/?probe=16f403a6e1) | Sep 12, 2025 |
| Positivo      | N4340                       | Notebook    | [fa5b180e90](https://linux-hardware.org/?probe=fa5b180e90) | Sep 10, 2025 |
| Positivo      | N4340                       | Notebook    | [09080bb232](https://linux-hardware.org/?probe=09080bb232) | Sep 10, 2025 |
| Apple         | MacBookPro11,2              | Notebook    | [d18d63f46a](https://linux-hardware.org/?probe=d18d63f46a) | Sep 08, 2025 |
| Apple         | MacBookPro12,1              | Notebook    | [e3d8342efd](https://linux-hardware.org/?probe=e3d8342efd) | Sep 07, 2025 |
| Apple         | MacBookPro11,2              | Notebook    | [e67eeef57c](https://linux-hardware.org/?probe=e67eeef57c) | Sep 03, 2025 |
| Acer          | Aspire 4739                 | Notebook    | [2144d6fb23](https://linux-hardware.org/?probe=2144d6fb23) | Sep 03, 2025 |
| Dell          | Latitude E5420              | Notebook    | [622d7ea264](https://linux-hardware.org/?probe=622d7ea264) | Sep 02, 2025 |
| Dell          | 0YJMC0 A02                  | Desktop     | [e9f6bbf8b4](https://linux-hardware.org/?probe=e9f6bbf8b4) | Sep 01, 2025 |
| MAXSUN        | MS-MoDT 12450H ITX WIFI ... | Desktop     | [e5fc66ced9](https://linux-hardware.org/?probe=e5fc66ced9) | Sep 01, 2025 |
| Star Labs     | StarBook                    | Notebook    | [ce9448d5e8](https://linux-hardware.org/?probe=ce9448d5e8) | Aug 31, 2025 |
| Acer          | Aspire 7540                 | Notebook    | [d622492cf3](https://linux-hardware.org/?probe=d622492cf3) | Aug 30, 2025 |
| Pegatron      | A15                         | Notebook    | [ee67a9066e](https://linux-hardware.org/?probe=ee67a9066e) | Aug 30, 2025 |
| ZOTAC         | ZBOX-CI527/CI547            | Mini pc     | [1606348598](https://linux-hardware.org/?probe=1606348598) | Aug 29, 2025 |
| ASRock        | Z390 Phantom Gaming-ITX/... | Desktop     | [711f7fd312](https://linux-hardware.org/?probe=711f7fd312) | Aug 29, 2025 |
| Dell          | Inspiron N5110              | Notebook    | [f21399e094](https://linux-hardware.org/?probe=f21399e094) | Aug 26, 2025 |
| ZOTAC         | ZBOX-CI527/CI547            | Mini pc     | [e06f470c77](https://linux-hardware.org/?probe=e06f470c77) | Aug 26, 2025 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [c88d8b09bf](https://linux-hardware.org/?probe=c88d8b09bf) | Aug 24, 2025 |
| HP            | 1497                        | Desktop     | [e80f663d27](https://linux-hardware.org/?probe=e80f663d27) | Aug 24, 2025 |
| HP            | 1497                        | Desktop     | [6a610b0d64](https://linux-hardware.org/?probe=6a610b0d64) | Aug 24, 2025 |
| Lenovo        | ThinkPad T530 23595JU       | Notebook    | [9d62dd71ce](https://linux-hardware.org/?probe=9d62dd71ce) | Aug 23, 2025 |
| Lenovo        | ThinkPad T530 23595JU       | Notebook    | [d1a6eb1eb1](https://linux-hardware.org/?probe=d1a6eb1eb1) | Aug 23, 2025 |
| Pegatron      | IPM41-D3                    | Desktop     | [d411498552](https://linux-hardware.org/?probe=d411498552) | Aug 23, 2025 |
| ASUSTek       | ProArt B760-CREATOR D4      | Desktop     | [7e96a291c7](https://linux-hardware.org/?probe=7e96a291c7) | Aug 23, 2025 |
| Pegatron      | IPM41-D3                    | Desktop     | [422732bfd6](https://linux-hardware.org/?probe=422732bfd6) | Aug 21, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [d932ad5888](https://linux-hardware.org/?probe=d932ad5888) | Aug 20, 2025 |
| Dell          | Vostro 1015                 | Notebook    | [768a7d4849](https://linux-hardware.org/?probe=768a7d4849) | Aug 18, 2025 |
| Unknown       | Unknown                     | Desktop     | [1c3d5ce606](https://linux-hardware.org/?probe=1c3d5ce606) | Aug 17, 2025 |
| Toshiba       | Satellite U840              | Notebook    | [5d9ded6b5e](https://linux-hardware.org/?probe=5d9ded6b5e) | Aug 15, 2025 |
| Intel         | DH55HC AAE70933-504         | Desktop     | [0fdf5fa883](https://linux-hardware.org/?probe=0fdf5fa883) | Aug 15, 2025 |
| HP            | 83EC                        | Desktop     | [e31cc86909](https://linux-hardware.org/?probe=e31cc86909) | Aug 14, 2025 |
| HP            | 83EC                        | Desktop     | [5cbe94892f](https://linux-hardware.org/?probe=5cbe94892f) | Aug 14, 2025 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [f22865b542](https://linux-hardware.org/?probe=f22865b542) | Aug 13, 2025 |
| MAXSUN        | MS-MoDT 12450H ITX WIFI ... | Desktop     | [4b97e2df68](https://linux-hardware.org/?probe=4b97e2df68) | Aug 13, 2025 |
| ASUSTek       | PRIME H110M2/FPT            | Desktop     | [9dff3c78bb](https://linux-hardware.org/?probe=9dff3c78bb) | Aug 12, 2025 |
| HP            | 1495                        | Desktop     | [870edad545](https://linux-hardware.org/?probe=870edad545) | Aug 12, 2025 |
| Dell          | Latitude E7470              | Notebook    | [0ca5330918](https://linux-hardware.org/?probe=0ca5330918) | Aug 11, 2025 |
| ASUSTek       | X406UAR                     | Notebook    | [b817bc940d](https://linux-hardware.org/?probe=b817bc940d) | Aug 11, 2025 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [fb1d1e0705](https://linux-hardware.org/?probe=fb1d1e0705) | Aug 11, 2025 |
| Dell          | Latitude E6320              | Notebook    | [724cbbacb6](https://linux-hardware.org/?probe=724cbbacb6) | Aug 10, 2025 |
| Microsoft     | Surface 3                   | Tablet      | [0288a2cefe](https://linux-hardware.org/?probe=0288a2cefe) | Aug 09, 2025 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [0e45e523e2](https://linux-hardware.org/?probe=0e45e523e2) | Aug 08, 2025 |
| BOSCH         | CCTV APP AEL1 1             | Desktop     | [d6029846a9](https://linux-hardware.org/?probe=d6029846a9) | Aug 07, 2025 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [0ea8cc0ee0](https://linux-hardware.org/?probe=0ea8cc0ee0) | Aug 06, 2025 |
| BOSCH         | CCTV APP AEL1 1             | Desktop     | [fc70f237b5](https://linux-hardware.org/?probe=fc70f237b5) | Aug 06, 2025 |
| Apple         | Mac-F2268CC8                | All in one  | [1eb0681b5c](https://linux-hardware.org/?probe=1eb0681b5c) | Aug 05, 2025 |
| Acer          | Aspire A515-45              | Notebook    | [ae5ea08bd6](https://linux-hardware.org/?probe=ae5ea08bd6) | Aug 05, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [4009991bb8](https://linux-hardware.org/?probe=4009991bb8) | Aug 05, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [aeff5dd520](https://linux-hardware.org/?probe=aeff5dd520) | Aug 05, 2025 |
| Apple         | Mac-F2268CC8                | All in one  | [5a6771f762](https://linux-hardware.org/?probe=5a6771f762) | Aug 04, 2025 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [77e60f03ef](https://linux-hardware.org/?probe=77e60f03ef) | Aug 04, 2025 |
| Apple         | MacBookPro11,5              | Notebook    | [16ad2ffc69](https://linux-hardware.org/?probe=16ad2ffc69) | Aug 04, 2025 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [87d2be3cec](https://linux-hardware.org/?probe=87d2be3cec) | Aug 02, 2025 |
| HP            | Notebook                    | Notebook    | [2860a347b6](https://linux-hardware.org/?probe=2860a347b6) | Aug 01, 2025 |
| HP            | Notebook                    | Notebook    | [bd44fff337](https://linux-hardware.org/?probe=bd44fff337) | Aug 01, 2025 |
| Apple         | MacBookPro11,5              | Notebook    | [45e006e8f0](https://linux-hardware.org/?probe=45e006e8f0) | Aug 01, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [2b0e8cc054](https://linux-hardware.org/?probe=2b0e8cc054) | Aug 01, 2025 |
| ASUSTek       | K93SV                       | Notebook    | [972fc344be](https://linux-hardware.org/?probe=972fc344be) | Jul 31, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [85f6fbba81](https://linux-hardware.org/?probe=85f6fbba81) | Jul 31, 2025 |
| Notebook      | W35xSS_370SS                | Notebook    | [aad43c31b1](https://linux-hardware.org/?probe=aad43c31b1) | Jul 31, 2025 |
| ASUSTek       | CM6870                      | Desktop     | [02973bf4ae](https://linux-hardware.org/?probe=02973bf4ae) | Jul 31, 2025 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [0528bca40a](https://linux-hardware.org/?probe=0528bca40a) | Jul 30, 2025 |
| HP            | 1495                        | Desktop     | [d40b21b085](https://linux-hardware.org/?probe=d40b21b085) | Jul 30, 2025 |
| Dell          | XPS L412Z                   | Notebook    | [f7afa8d724](https://linux-hardware.org/?probe=f7afa8d724) | Jul 27, 2025 |
| ASUSTek       | TUF Gaming Z790-PLUS D4     | Desktop     | [6cd807c3c7](https://linux-hardware.org/?probe=6cd807c3c7) | Jul 27, 2025 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [e78bc0db73](https://linux-hardware.org/?probe=e78bc0db73) | Jul 27, 2025 |
| Trigkey       | Key N                       | Mini pc     | [9f88b86afa](https://linux-hardware.org/?probe=9f88b86afa) | Jul 27, 2025 |
| Biostar       | G41-M7                      | Desktop     | [1f6d011ff4](https://linux-hardware.org/?probe=1f6d011ff4) | Jul 26, 2025 |
| HP            | 0B4Ch D                     | Desktop     | [3ab2a33cab](https://linux-hardware.org/?probe=3ab2a33cab) | Jul 25, 2025 |
| Unknown       | Unknown                     | Desktop     | [a298dd6726](https://linux-hardware.org/?probe=a298dd6726) | Jul 24, 2025 |
| Microsoft     | Surface Laptop              | Tablet      | [8b13f66f66](https://linux-hardware.org/?probe=8b13f66f66) | Jul 24, 2025 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [09be4abb3c](https://linux-hardware.org/?probe=09be4abb3c) | Jul 24, 2025 |
| ASUSTek       | X555LA                      | Notebook    | [1eec7134a2](https://linux-hardware.org/?probe=1eec7134a2) | Jul 24, 2025 |
| Lenovo        | V330-14IGM 81B3             | Notebook    | [1f8b2fa7d1](https://linux-hardware.org/?probe=1f8b2fa7d1) | Jul 23, 2025 |
| Google        | Joxer                       | Notebook    | [bc774d1258](https://linux-hardware.org/?probe=bc774d1258) | Jul 23, 2025 |
| Apple         | Mac-F2268DC8                | All in one  | [d264c36dc0](https://linux-hardware.org/?probe=d264c36dc0) | Jul 23, 2025 |
| Dell          | Inspiron 5520               | Notebook    | [53d6949846](https://linux-hardware.org/?probe=53d6949846) | Jul 22, 2025 |
| Toshiba       | Intel H61 Express Chipse... | All in one  | [468d5e2edc](https://linux-hardware.org/?probe=468d5e2edc) | Jul 21, 2025 |
| Medion        | S5610                       | Notebook    | [82d257e335](https://linux-hardware.org/?probe=82d257e335) | Jul 21, 2025 |
| Dell          | 00V62H A01                  | Desktop     | [5a65caa05f](https://linux-hardware.org/?probe=5a65caa05f) | Jul 21, 2025 |
| Apple         | MacBookPro11,1              | Notebook    | [42ab6e3bd2](https://linux-hardware.org/?probe=42ab6e3bd2) | Jul 20, 2025 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [57d34f4fce](https://linux-hardware.org/?probe=57d34f4fce) | Jul 20, 2025 |
| HP            | 8169                        | Desktop     | [0d335d8068](https://linux-hardware.org/?probe=0d335d8068) | Jul 19, 2025 |
| Sony          | SVE14A27CLS                 | Notebook    | [2b6cf71203](https://linux-hardware.org/?probe=2b6cf71203) | Jul 18, 2025 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [8b1d790084](https://linux-hardware.org/?probe=8b1d790084) | Jul 17, 2025 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [2f713fce4d](https://linux-hardware.org/?probe=2f713fce4d) | Jul 16, 2025 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [44bb83c372](https://linux-hardware.org/?probe=44bb83c372) | Jul 16, 2025 |
| HP            | EliteBook 8470p             | Notebook    | [543bb5c5ee](https://linux-hardware.org/?probe=543bb5c5ee) | Jul 16, 2025 |
| HP            | EliteBook 8470p             | Notebook    | [ceb27b6e9a](https://linux-hardware.org/?probe=ceb27b6e9a) | Jul 16, 2025 |
| HP            | EliteBook x360 1030 G4      | Convertible | [e2a9fb598f](https://linux-hardware.org/?probe=e2a9fb598f) | Jul 16, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [2dd8366e0b](https://linux-hardware.org/?probe=2dd8366e0b) | Jul 15, 2025 |
| HP            | Pavilion dv6                | Notebook    | [13a04e6371](https://linux-hardware.org/?probe=13a04e6371) | Jul 15, 2025 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [b3778a5f03](https://linux-hardware.org/?probe=b3778a5f03) | Jul 14, 2025 |
| Intel         | H81                         | Desktop     | [05f057c7d1](https://linux-hardware.org/?probe=05f057c7d1) | Jul 14, 2025 |
| HP            | Pavilion dv7                | Notebook    | [7e04c5ff73](https://linux-hardware.org/?probe=7e04c5ff73) | Jul 14, 2025 |
| ASRock        | B450M Steel Legend          | Desktop     | [834b575ff6](https://linux-hardware.org/?probe=834b575ff6) | Jul 13, 2025 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [a38fb52a4a](https://linux-hardware.org/?probe=a38fb52a4a) | Jul 13, 2025 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c6d988bf9e](https://linux-hardware.org/?probe=c6d988bf9e) | Jul 13, 2025 |
| Positivo      | POS-PIH81DL                 | Desktop     | [4837b80079](https://linux-hardware.org/?probe=4837b80079) | Jul 12, 2025 |
| Gigabyte      | X79-UD3                     | Desktop     | [059ea5dfe8](https://linux-hardware.org/?probe=059ea5dfe8) | Jul 12, 2025 |
| Lenovo        | G505 20240                  | Notebook    | [db89bc9e33](https://linux-hardware.org/?probe=db89bc9e33) | Jul 12, 2025 |
| Intel         | H81                         | Desktop     | [338632b69c](https://linux-hardware.org/?probe=338632b69c) | Jul 11, 2025 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [7bc74950ff](https://linux-hardware.org/?probe=7bc74950ff) | Jul 10, 2025 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [db25025716](https://linux-hardware.org/?probe=db25025716) | Jul 10, 2025 |
| ASUSTek       | X450EA                      | Notebook    | [1ec63ddd6b](https://linux-hardware.org/?probe=1ec63ddd6b) | Jul 10, 2025 |
| Acer          | Aspire C27-1700             | All in one  | [99b4949742](https://linux-hardware.org/?probe=99b4949742) | Jul 10, 2025 |
| MSI           | MPG Z790 EDGE TI MAX WIF... | Desktop     | [77d77a702d](https://linux-hardware.org/?probe=77d77a702d) | Jul 10, 2025 |
| Apple         | MacBookPro7,1               | Notebook    | [a90c9e156d](https://linux-hardware.org/?probe=a90c9e156d) | Jul 09, 2025 |
| Dell          | 0M9KCM A02                  | Desktop     | [c05464dda3](https://linux-hardware.org/?probe=c05464dda3) | Jul 08, 2025 |
| HP            | 0B4Ch D                     | Desktop     | [459fae43ed](https://linux-hardware.org/?probe=459fae43ed) | Jul 06, 2025 |
| HP            | 0B4Ch D                     | Desktop     | [36e98b328d](https://linux-hardware.org/?probe=36e98b328d) | Jul 06, 2025 |
| Apple         | MacBookPro11,1              | Notebook    | [2da9644a1f](https://linux-hardware.org/?probe=2da9644a1f) | Jul 05, 2025 |
| Apple         | MacBookPro11,1              | Notebook    | [2952563cb5](https://linux-hardware.org/?probe=2952563cb5) | Jul 05, 2025 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [1e777ac3b2](https://linux-hardware.org/?probe=1e777ac3b2) | Jul 05, 2025 |
| HP            | 0AECh D                     | Desktop     | [957baad019](https://linux-hardware.org/?probe=957baad019) | Jul 05, 2025 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [7178039d89](https://linux-hardware.org/?probe=7178039d89) | Jul 03, 2025 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [7712467a87](https://linux-hardware.org/?probe=7712467a87) | Jul 03, 2025 |
| TUXEDO        | N85_N87HCHNHZ               | Notebook    | [944efa8a15](https://linux-hardware.org/?probe=944efa8a15) | Jul 03, 2025 |
| ASUSTek       | K55A                        | Notebook    | [f540fa0209](https://linux-hardware.org/?probe=f540fa0209) | Jul 01, 2025 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [06e7cc2c95](https://linux-hardware.org/?probe=06e7cc2c95) | Jul 01, 2025 |
| HP            | EliteBook 8770w             | Notebook    | [32840687a2](https://linux-hardware.org/?probe=32840687a2) | Jul 01, 2025 |
| Apple         | MacBook8,1                  | Notebook    | [1a8a0dadc4](https://linux-hardware.org/?probe=1a8a0dadc4) | Jul 01, 2025 |
| Google        | Frostflow                   | Notebook    | [f960b3c8fc](https://linux-hardware.org/?probe=f960b3c8fc) | Jun 29, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [89fce5afd8](https://linux-hardware.org/?probe=89fce5afd8) | Jun 28, 2025 |
| Gigabyte      | B450M GAMING                | Desktop     | [78e88aacc8](https://linux-hardware.org/?probe=78e88aacc8) | Jun 27, 2025 |
| Acer          | Aspire A315-24PT            | Notebook    | [96ed77cc5b](https://linux-hardware.org/?probe=96ed77cc5b) | Jun 26, 2025 |
| Acer          | Aspire A315-24PT            | Notebook    | [3b65852f6c](https://linux-hardware.org/?probe=3b65852f6c) | Jun 26, 2025 |
| HP            | 255 15.6 inch G10 Notebo... | Notebook    | [c1d5a9441e](https://linux-hardware.org/?probe=c1d5a9441e) | Jun 26, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [631e136e6b](https://linux-hardware.org/?probe=631e136e6b) | Jun 25, 2025 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [dee212f5d9](https://linux-hardware.org/?probe=dee212f5d9) | Jun 24, 2025 |
| Apple         | MacBook5,1                  | Notebook    | [3b40a9285e](https://linux-hardware.org/?probe=3b40a9285e) | Jun 24, 2025 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [bf396ea58d](https://linux-hardware.org/?probe=bf396ea58d) | Jun 24, 2025 |
| HP            | Notebook                    | Notebook    | [9b254818da](https://linux-hardware.org/?probe=9b254818da) | Jun 23, 2025 |
| Apple         | MacBookPro11,3              | Notebook    | [ac2010480b](https://linux-hardware.org/?probe=ac2010480b) | Jun 23, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [d285c790b0](https://linux-hardware.org/?probe=d285c790b0) | Jun 23, 2025 |
| Apple         | Mac-F2268CC8                | All in one  | [e8428584a2](https://linux-hardware.org/?probe=e8428584a2) | Jun 23, 2025 |
| HP            | 255 15.6 inch G10 Notebo... | Notebook    | [985bc51e87](https://linux-hardware.org/?probe=985bc51e87) | Jun 22, 2025 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [11cd8d00eb](https://linux-hardware.org/?probe=11cd8d00eb) | Jun 22, 2025 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [f3ca605115](https://linux-hardware.org/?probe=f3ca605115) | Jun 20, 2025 |
| Sony          | SVE15133CNW                 | Notebook    | [82e61cb2c7](https://linux-hardware.org/?probe=82e61cb2c7) | Jun 18, 2025 |
| MSI           | X299 GAMING PRO CARBON      | Desktop     | [624e16050d](https://linux-hardware.org/?probe=624e16050d) | Jun 18, 2025 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [179aecdd4f](https://linux-hardware.org/?probe=179aecdd4f) | Jun 17, 2025 |
| HP            | 14                          | Notebook    | [652477232e](https://linux-hardware.org/?probe=652477232e) | Jun 17, 2025 |
| HP            | 635                         | Notebook    | [479d8459c0](https://linux-hardware.org/?probe=479d8459c0) | Jun 17, 2025 |
| HP            | ProBook 440 G4              | Notebook    | [64ab630b9c](https://linux-hardware.org/?probe=64ab630b9c) | Jun 15, 2025 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [b045f74b75](https://linux-hardware.org/?probe=b045f74b75) | Jun 15, 2025 |
| Apple         | MacBookPro9,1               | Notebook    | [77b85c37ed](https://linux-hardware.org/?probe=77b85c37ed) | Jun 15, 2025 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [38351db67b](https://linux-hardware.org/?probe=38351db67b) | Jun 14, 2025 |
| Apple         | MacBookPro11,1              | Notebook    | [96435d53d9](https://linux-hardware.org/?probe=96435d53d9) | Jun 14, 2025 |
| HP            | 8265                        | Desktop     | [330c6a4a61](https://linux-hardware.org/?probe=330c6a4a61) | Jun 13, 2025 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [ff8ea04712](https://linux-hardware.org/?probe=ff8ea04712) | Jun 13, 2025 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d2724d6f18](https://linux-hardware.org/?probe=d2724d6f18) | Jun 12, 2025 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [3798659222](https://linux-hardware.org/?probe=3798659222) | Jun 10, 2025 |
| Microsoft     | Surface Pro 3               | Tablet      | [5174f9b7e7](https://linux-hardware.org/?probe=5174f9b7e7) | Jun 10, 2025 |
| Apple         | MacBook5,1                  | Notebook    | [f3336d6280](https://linux-hardware.org/?probe=f3336d6280) | Jun 09, 2025 |
| Sony          | VPCCB2S1E                   | Notebook    | [2bded87a77](https://linux-hardware.org/?probe=2bded87a77) | Jun 09, 2025 |
| Sony          | VPCCB2S1E                   | Notebook    | [d71077fe64](https://linux-hardware.org/?probe=d71077fe64) | Jun 09, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [9e33c3ae46](https://linux-hardware.org/?probe=9e33c3ae46) | Jun 08, 2025 |
| Toshiba       | Satellite C660              | Notebook    | [909792452b](https://linux-hardware.org/?probe=909792452b) | Jun 07, 2025 |
| Apple         | MacBookAir5,2               | Notebook    | [2c06794b01](https://linux-hardware.org/?probe=2c06794b01) | Jun 05, 2025 |
| Alienware     | M11x                        | Notebook    | [28e13fa7d6](https://linux-hardware.org/?probe=28e13fa7d6) | Jun 04, 2025 |
| HP            | Unknown                     | Notebook    | [c6f2e73a9e](https://linux-hardware.org/?probe=c6f2e73a9e) | Jun 03, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [6db04e9ade](https://linux-hardware.org/?probe=6db04e9ade) | Jun 02, 2025 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [4cd3dc7b78](https://linux-hardware.org/?probe=4cd3dc7b78) | Jun 01, 2025 |
| Dell          | Vostro 3300                 | Notebook    | [e24f84ce5c](https://linux-hardware.org/?probe=e24f84ce5c) | Jun 01, 2025 |
| MSI           | Z390-A PRO                  | Desktop     | [6353bbffb5](https://linux-hardware.org/?probe=6353bbffb5) | Jun 01, 2025 |
| HP            | 8184 X4                     | Desktop     | [2902fda187](https://linux-hardware.org/?probe=2902fda187) | Jun 01, 2025 |
| Toshiba       | Satellite L50-B             | Notebook    | [65d84e16b9](https://linux-hardware.org/?probe=65d84e16b9) | May 31, 2025 |
| Toshiba       | Satellite L50-B             | Notebook    | [22f45326e2](https://linux-hardware.org/?probe=22f45326e2) | May 31, 2025 |
| MSI           | Z77A-G43                    | Desktop     | [bb580382c5](https://linux-hardware.org/?probe=bb580382c5) | May 30, 2025 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | Notebook    | [205c33e738](https://linux-hardware.org/?probe=205c33e738) | May 30, 2025 |
| MSI           | Modern 14 C7M               | Notebook    | [d0a3efc2a4](https://linux-hardware.org/?probe=d0a3efc2a4) | May 30, 2025 |
| Positivo      | Mobile                      | Notebook    | [a6cde8e043](https://linux-hardware.org/?probe=a6cde8e043) | May 30, 2025 |
| HP            | Laptop 17-cp2xxx            | Notebook    | [73c78eed44](https://linux-hardware.org/?probe=73c78eed44) | May 29, 2025 |
| Apple         | MacBookPro10,1              | Notebook    | [643474230c](https://linux-hardware.org/?probe=643474230c) | May 29, 2025 |
| Apple         | MacBookPro10,1              | Notebook    | [a132a12adb](https://linux-hardware.org/?probe=a132a12adb) | May 28, 2025 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [7f1edd5b3f](https://linux-hardware.org/?probe=7f1edd5b3f) | May 27, 2025 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c942d87784](https://linux-hardware.org/?probe=c942d87784) | May 27, 2025 |
| ASRock        | B450M Steel Legend          | Desktop     | [11e8c05339](https://linux-hardware.org/?probe=11e8c05339) | May 27, 2025 |
| ASRock        | B760M-ITX/D4 WiFi           | Desktop     | [19fb1a3c33](https://linux-hardware.org/?probe=19fb1a3c33) | May 27, 2025 |
| Dell          | Latitude E6420              | Notebook    | [42d5692ec5](https://linux-hardware.org/?probe=42d5692ec5) | May 26, 2025 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [ac660129d6](https://linux-hardware.org/?probe=ac660129d6) | May 25, 2025 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [17f1322f85](https://linux-hardware.org/?probe=17f1322f85) | May 24, 2025 |
| ASRock        | B850M-X WiFi                | Desktop     | [b33d0756d7](https://linux-hardware.org/?probe=b33d0756d7) | May 24, 2025 |
| ASRock        | B850M-X WiFi                | Desktop     | [8ea3eb0e6a](https://linux-hardware.org/?probe=8ea3eb0e6a) | May 24, 2025 |
| Gigabyte      | X58-USB3                    | Desktop     | [704b2100ab](https://linux-hardware.org/?probe=704b2100ab) | May 24, 2025 |
| Gigabyte      | X58-USB3                    | Desktop     | [27786c7b04](https://linux-hardware.org/?probe=27786c7b04) | May 24, 2025 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [7a99f1fc83](https://linux-hardware.org/?probe=7a99f1fc83) | May 24, 2025 |
| ASUSTek       | PRIME B760M-A WIFI D4       | Desktop     | [9f67585ccd](https://linux-hardware.org/?probe=9f67585ccd) | May 23, 2025 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [2726c953cf](https://linux-hardware.org/?probe=2726c953cf) | May 22, 2025 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [96bbce6853](https://linux-hardware.org/?probe=96bbce6853) | May 22, 2025 |
| HONOR         | BMH-WDX9                    | Notebook    | [3b0953da0c](https://linux-hardware.org/?probe=3b0953da0c) | May 21, 2025 |
| HONOR         | BMH-WDX9                    | Notebook    | [21b8d516ed](https://linux-hardware.org/?probe=21b8d516ed) | May 21, 2025 |
| Dell          | Latitude E5570              | Notebook    | [4644f38290](https://linux-hardware.org/?probe=4644f38290) | May 19, 2025 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [f53bf88296](https://linux-hardware.org/?probe=f53bf88296) | May 18, 2025 |
| HP            | ProBook 650 G3              | Notebook    | [063bdc9c85](https://linux-hardware.org/?probe=063bdc9c85) | May 16, 2025 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [9029bac7ad](https://linux-hardware.org/?probe=9029bac7ad) | May 16, 2025 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [54908bc09b](https://linux-hardware.org/?probe=54908bc09b) | May 16, 2025 |
| HP            | 240 G4 Notebook PC          | Notebook    | [8b2fecec4b](https://linux-hardware.org/?probe=8b2fecec4b) | May 16, 2025 |
| HP            | Pavilion dm4                | Notebook    | [00223b4a35](https://linux-hardware.org/?probe=00223b4a35) | May 15, 2025 |
| HP            | ProBook 430 G5              | Notebook    | [9c40451ead](https://linux-hardware.org/?probe=9c40451ead) | May 14, 2025 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [e0cab703f0](https://linux-hardware.org/?probe=e0cab703f0) | May 14, 2025 |
| Apple         | MacBookPro5,5               | Notebook    | [2b7f0d49ad](https://linux-hardware.org/?probe=2b7f0d49ad) | May 13, 2025 |
| Acer          | Aspire ES1-521              | Notebook    | [51356a260c](https://linux-hardware.org/?probe=51356a260c) | May 13, 2025 |
| Acer          | Aspire ES1-521              | Notebook    | [82ce3477e5](https://linux-hardware.org/?probe=82ce3477e5) | May 13, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [aa8390baa6](https://linux-hardware.org/?probe=aa8390baa6) | May 13, 2025 |
| ASUSTek       | ASUS Zenbook S 16 UM5606... | Notebook    | [f117b0e455](https://linux-hardware.org/?probe=f117b0e455) | May 12, 2025 |
| Dell          | Latitude E6520              | Notebook    | [baa6186588](https://linux-hardware.org/?probe=baa6186588) | May 12, 2025 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [3d7b307b03](https://linux-hardware.org/?probe=3d7b307b03) | May 11, 2025 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [a01996b9ce](https://linux-hardware.org/?probe=a01996b9ce) | May 10, 2025 |
| Lenovo        | SDK0J40705 WIN 342503991... | Desktop     | [566728e595](https://linux-hardware.org/?probe=566728e595) | May 10, 2025 |
| HP            | EliteBook 2570p             | Notebook    | [3102539d4d](https://linux-hardware.org/?probe=3102539d4d) | May 07, 2025 |
| Lenovo        | ThinkPad Edge E130 3358A... | Notebook    | [2987fa1bca](https://linux-hardware.org/?probe=2987fa1bca) | May 07, 2025 |
| Lenovo        | ThinkPad Edge E130 3358A... | Notebook    | [664601b72c](https://linux-hardware.org/?probe=664601b72c) | May 07, 2025 |
| Acer          | Swift SF713-51              | Notebook    | [e37cd51aa0](https://linux-hardware.org/?probe=e37cd51aa0) | May 06, 2025 |
| HP            | 83E2                        | Desktop     | [45ae65d295](https://linux-hardware.org/?probe=45ae65d295) | May 06, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [43142d40aa](https://linux-hardware.org/?probe=43142d40aa) | May 05, 2025 |
| Sony          | VPCCW1S1E                   | Notebook    | [6766f4cf01](https://linux-hardware.org/?probe=6766f4cf01) | May 05, 2025 |
| HP            | ENVY 17                     | Notebook    | [817cef050a](https://linux-hardware.org/?probe=817cef050a) | May 04, 2025 |
| TongFang      | Standard                    | Notebook    | [5d358787ca](https://linux-hardware.org/?probe=5d358787ca) | May 04, 2025 |
| TongFang      | Standard                    | Notebook    | [06e06c45c0](https://linux-hardware.org/?probe=06e06c45c0) | May 04, 2025 |
| Unknown       | K16                         | Notebook    | [668e7a80bf](https://linux-hardware.org/?probe=668e7a80bf) | May 03, 2025 |
| Fujitsu       | LIFEBOOK U772               | Notebook    | [5d1ae06d47](https://linux-hardware.org/?probe=5d1ae06d47) | May 02, 2025 |
| Fujitsu       | LIFEBOOK U772               | Notebook    | [6ca8928193](https://linux-hardware.org/?probe=6ca8928193) | May 02, 2025 |
| HP            | EliteBook 2570p             | Notebook    | [eaeaf4f57d](https://linux-hardware.org/?probe=eaeaf4f57d) | May 02, 2025 |
| Daten Tecn... | DB85PRO                     | Desktop     | [16ac21b0b7](https://linux-hardware.org/?probe=16ac21b0b7) | May 02, 2025 |
| Samsung       | SBB-DA                      | Notebook    | [227f005e60](https://linux-hardware.org/?probe=227f005e60) | May 01, 2025 |
| Samsung       | SBB-DA                      | Notebook    | [0f6e59728c](https://linux-hardware.org/?probe=0f6e59728c) | Apr 30, 2025 |
| Dell          | Latitude E5570              | Notebook    | [53866531f2](https://linux-hardware.org/?probe=53866531f2) | Apr 28, 2025 |
| Acer          | Aspire A315-41G             | Notebook    | [c398a7ed29](https://linux-hardware.org/?probe=c398a7ed29) | Apr 27, 2025 |
| Acer          | Aspire V3-571               | Notebook    | [3d4aef7438](https://linux-hardware.org/?probe=3d4aef7438) | Apr 26, 2025 |
| NEC Comput... | MS-7479MH                   | Desktop     | [2263a0ef49](https://linux-hardware.org/?probe=2263a0ef49) | Apr 26, 2025 |
| Sony          | SVJ20236CXW                 | Notebook    | [ecbc00414b](https://linux-hardware.org/?probe=ecbc00414b) | Apr 26, 2025 |
| ASRock        | X58 Extreme6                | Desktop     | [24161c8dff](https://linux-hardware.org/?probe=24161c8dff) | Apr 25, 2025 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [9093a619c7](https://linux-hardware.org/?probe=9093a619c7) | Apr 25, 2025 |
| Samsung       | 750XDA                      | Notebook    | [daa961232a](https://linux-hardware.org/?probe=daa961232a) | Apr 24, 2025 |
| Samsung       | 750XDA                      | Notebook    | [3f300c8d3d](https://linux-hardware.org/?probe=3f300c8d3d) | Apr 24, 2025 |
| Gigabyte      | H97-HD3                     | Desktop     | [95ef8ff863](https://linux-hardware.org/?probe=95ef8ff863) | Apr 23, 2025 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4c7638e9b6](https://linux-hardware.org/?probe=4c7638e9b6) | Apr 23, 2025 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [6f5ee2f252](https://linux-hardware.org/?probe=6f5ee2f252) | Apr 23, 2025 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c8ee1f92ba](https://linux-hardware.org/?probe=c8ee1f92ba) | Apr 23, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [ffe6a7e1d6](https://linux-hardware.org/?probe=ffe6a7e1d6) | Apr 22, 2025 |
| Sony          | SVJ20236CXW                 | Notebook    | [420898862c](https://linux-hardware.org/?probe=420898862c) | Apr 21, 2025 |
| ASUSTek       | PRIME B760M-AJ D4           | Desktop     | [e9f4177ebc](https://linux-hardware.org/?probe=e9f4177ebc) | Apr 21, 2025 |
| Lenovo        | G70-70 80HW                 | Notebook    | [59676e322d](https://linux-hardware.org/?probe=59676e322d) | Apr 21, 2025 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [88da2c6ce2](https://linux-hardware.org/?probe=88da2c6ce2) | Apr 20, 2025 |
| Clevo         | M860TU                      | Notebook    | [19839c5808](https://linux-hardware.org/?probe=19839c5808) | Apr 20, 2025 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [5f136d1672](https://linux-hardware.org/?probe=5f136d1672) | Apr 19, 2025 |
| ASRock        | H81M-HDS R2.0               | Desktop     | [f305fbfa16](https://linux-hardware.org/?probe=f305fbfa16) | Apr 19, 2025 |
| Dell          | Inspiron 1525               | Notebook    | [c02590fff8](https://linux-hardware.org/?probe=c02590fff8) | Apr 19, 2025 |
| MSI           | H510M PLUS V3               | Desktop     | [dce1906518](https://linux-hardware.org/?probe=dce1906518) | Apr 18, 2025 |
| HP            | 3397                        | Desktop     | [a98b71652e](https://linux-hardware.org/?probe=a98b71652e) | Apr 18, 2025 |
| Dell          | Latitude E7470              | Notebook    | [5d70f86783](https://linux-hardware.org/?probe=5d70f86783) | Apr 18, 2025 |
| Dell          | Latitude E7470              | Notebook    | [1c6dcea31c](https://linux-hardware.org/?probe=1c6dcea31c) | Apr 18, 2025 |
| Dell          | Inspiron 1525               | Notebook    | [f5e08a7a78](https://linux-hardware.org/?probe=f5e08a7a78) | Apr 16, 2025 |
| Dell          | Inspiron 15 3515            | Notebook    | [142f88c0e7](https://linux-hardware.org/?probe=142f88c0e7) | Apr 15, 2025 |
| Gigabyte      | Z390 UD                     | Desktop     | [1753f52781](https://linux-hardware.org/?probe=1753f52781) | Apr 15, 2025 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [edb5e85937](https://linux-hardware.org/?probe=edb5e85937) | Apr 13, 2025 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [73b4f5b9e1](https://linux-hardware.org/?probe=73b4f5b9e1) | Apr 13, 2025 |
| Dell          | 0H723K A00                  | Server      | [99091ee97e](https://linux-hardware.org/?probe=99091ee97e) | Apr 13, 2025 |
| Dell          | Latitude E6500              | Notebook    | [756c367ddc](https://linux-hardware.org/?probe=756c367ddc) | Apr 13, 2025 |
| ECS           | A790GXM-AD3                 | Desktop     | [791013e3d7](https://linux-hardware.org/?probe=791013e3d7) | Apr 12, 2025 |
| ASUSTek       | B85M-E                      | Desktop     | [40978b1318](https://linux-hardware.org/?probe=40978b1318) | Apr 12, 2025 |
| Acer          | Switch SA5-271              | Tablet      | [a3d57b9806](https://linux-hardware.org/?probe=a3d57b9806) | Apr 09, 2025 |
| ASUSTek       | D320MT-K                    | Desktop     | [00fa5036d1](https://linux-hardware.org/?probe=00fa5036d1) | Apr 09, 2025 |
| HUAWEI        | MRC-WX0                     | Notebook    | [4007d809cb](https://linux-hardware.org/?probe=4007d809cb) | Apr 07, 2025 |
| Apple         | MacBookPro6,2               | Notebook    | [feb743c270](https://linux-hardware.org/?probe=feb743c270) | Apr 06, 2025 |
| Kanji         | KJ-NTB1001                  | Notebook    | [04da5ff6d2](https://linux-hardware.org/?probe=04da5ff6d2) | Apr 06, 2025 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [36fbf4f170](https://linux-hardware.org/?probe=36fbf4f170) | Apr 06, 2025 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [4c6474d7fa](https://linux-hardware.org/?probe=4c6474d7fa) | Apr 06, 2025 |
| Dell          | Latitude E5550              | Notebook    | [2f0c001219](https://linux-hardware.org/?probe=2f0c001219) | Apr 05, 2025 |
| Samsung       | 750XGK                      | Notebook    | [92f6215d81](https://linux-hardware.org/?probe=92f6215d81) | Apr 04, 2025 |
| Dell          | Vostro 5581                 | Notebook    | [f218978bf3](https://linux-hardware.org/?probe=f218978bf3) | Apr 04, 2025 |
| Lenovo        | ThinkPad SL510 2847CZU      | Notebook    | [a6daef060e](https://linux-hardware.org/?probe=a6daef060e) | Apr 03, 2025 |
| HP            | Presario CQ42               | Notebook    | [6c3e4078ad](https://linux-hardware.org/?probe=6c3e4078ad) | Apr 03, 2025 |
| Lenovo        | G50-70 20351                | Notebook    | [416ae54e4f](https://linux-hardware.org/?probe=416ae54e4f) | Apr 02, 2025 |
| Dell          | 0C96W1 A03                  | Desktop     | [0105def95d](https://linux-hardware.org/?probe=0105def95d) | Apr 02, 2025 |
| Lenovo        | 32CB NOK                    | Desktop     | [c485697e16](https://linux-hardware.org/?probe=c485697e16) | Mar 31, 2025 |
| Lenovo        | G50-70 20351                | Notebook    | [e78beaea72](https://linux-hardware.org/?probe=e78beaea72) | Mar 31, 2025 |
| Sony          | SVS151190X                  | Notebook    | [7ffeb7fab1](https://linux-hardware.org/?probe=7ffeb7fab1) | Mar 30, 2025 |
| Fujitsu       | LIFEBOOK U728               | Notebook    | [bf5f9d0bd7](https://linux-hardware.org/?probe=bf5f9d0bd7) | Mar 29, 2025 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [2fa9f94e9e](https://linux-hardware.org/?probe=2fa9f94e9e) | Mar 29, 2025 |
| Toshiba       | Satellite L15W-B            | Notebook    | [2cbc15f4f1](https://linux-hardware.org/?probe=2cbc15f4f1) | Mar 28, 2025 |
| ZOTAC         | ZBOXNANO-VD01               | Mini pc     | [c80f99ccac](https://linux-hardware.org/?probe=c80f99ccac) | Mar 28, 2025 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [1fa2a5162e](https://linux-hardware.org/?probe=1fa2a5162e) | Mar 27, 2025 |
| Dell          | XPS L701X                   | Notebook    | [8fc24251a6](https://linux-hardware.org/?probe=8fc24251a6) | Mar 26, 2025 |
| HP            | G62                         | Notebook    | [3657b456c2](https://linux-hardware.org/?probe=3657b456c2) | Mar 25, 2025 |
| Microsoft     | Surface 3                   | Tablet      | [1471c40608](https://linux-hardware.org/?probe=1471c40608) | Mar 25, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e02ff3872b](https://linux-hardware.org/?probe=e02ff3872b) | Mar 24, 2025 |
| ASUSTek       | TP300LA                     | Notebook    | [116335b0c6](https://linux-hardware.org/?probe=116335b0c6) | Mar 24, 2025 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [ed4a144bef](https://linux-hardware.org/?probe=ed4a144bef) | Mar 24, 2025 |
| Apple         | Mac-F2268DC8                | All in one  | [6b8b2eccee](https://linux-hardware.org/?probe=6b8b2eccee) | Mar 24, 2025 |
| Dell          | Latitude 9330               | Convertible | [0d3d460a17](https://linux-hardware.org/?probe=0d3d460a17) | Mar 23, 2025 |
| HP            | EliteBook 8440p             | Notebook    | [cd1f9ebd2d](https://linux-hardware.org/?probe=cd1f9ebd2d) | Mar 23, 2025 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [a82f199083](https://linux-hardware.org/?probe=a82f199083) | Mar 23, 2025 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [6b1af2a5b7](https://linux-hardware.org/?probe=6b1af2a5b7) | Mar 22, 2025 |
| Acer          | Aspire E5-571G              | Notebook    | [c5b57bccce](https://linux-hardware.org/?probe=c5b57bccce) | Mar 21, 2025 |
| Acer          | Aspire E5-571G              | Notebook    | [463ced67dd](https://linux-hardware.org/?probe=463ced67dd) | Mar 21, 2025 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c4f42ccf48](https://linux-hardware.org/?probe=c4f42ccf48) | Mar 21, 2025 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [0103a16415](https://linux-hardware.org/?probe=0103a16415) | Mar 21, 2025 |
| HP            | Compaq 6730b (KE717AV)      | Notebook    | [4d05160c8f](https://linux-hardware.org/?probe=4d05160c8f) | Mar 21, 2025 |
| Acer          | Aspire E1-531               | Notebook    | [d7352bf64a](https://linux-hardware.org/?probe=d7352bf64a) | Mar 21, 2025 |
| ASUSTek       | K93SV                       | Notebook    | [73a0b56351](https://linux-hardware.org/?probe=73a0b56351) | Mar 19, 2025 |
| Lenovo        | G50-80 80L0                 | Notebook    | [0f2e61271e](https://linux-hardware.org/?probe=0f2e61271e) | Mar 19, 2025 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [01d7534529](https://linux-hardware.org/?probe=01d7534529) | Mar 18, 2025 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [d3f5528817](https://linux-hardware.org/?probe=d3f5528817) | Mar 17, 2025 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [3261531083](https://linux-hardware.org/?probe=3261531083) | Mar 17, 2025 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [dddf857184](https://linux-hardware.org/?probe=dddf857184) | Mar 17, 2025 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [7a3b2936b3](https://linux-hardware.org/?probe=7a3b2936b3) | Mar 17, 2025 |
| Apple         | Mac-F2218EA9                | All in one  | [168fc1bca1](https://linux-hardware.org/?probe=168fc1bca1) | Mar 16, 2025 |
| Dell          | Latitude 7490               | Notebook    | [fd9f8b4136](https://linux-hardware.org/?probe=fd9f8b4136) | Mar 16, 2025 |
| HP            | 3031h                       | Desktop     | [cf6acd606f](https://linux-hardware.org/?probe=cf6acd606f) | Mar 16, 2025 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [e5dcbff2b6](https://linux-hardware.org/?probe=e5dcbff2b6) | Mar 15, 2025 |
| Lenovo        | Z50-70 20354                | Notebook    | [097d7e970a](https://linux-hardware.org/?probe=097d7e970a) | Mar 14, 2025 |
| Lenovo        | G50-80 80L0                 | Notebook    | [b9326709c0](https://linux-hardware.org/?probe=b9326709c0) | Mar 13, 2025 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [cc93e40505](https://linux-hardware.org/?probe=cc93e40505) | Mar 13, 2025 |
| Infinix       | INBOOK X2 SLIM              | Notebook    | [4cdf6fc06b](https://linux-hardware.org/?probe=4cdf6fc06b) | Mar 12, 2025 |
| Apple         | Mac-F2218EA9                | All in one  | [f38b1683be](https://linux-hardware.org/?probe=f38b1683be) | Mar 12, 2025 |
| Toshiba       | Satellite L50D-B            | Notebook    | [ddd4722bd9](https://linux-hardware.org/?probe=ddd4722bd9) | Mar 12, 2025 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [6d76c73345](https://linux-hardware.org/?probe=6d76c73345) | Mar 10, 2025 |
| Apple         | MacBookAir4,2               | Notebook    | [d016461357](https://linux-hardware.org/?probe=d016461357) | Mar 10, 2025 |
| Google        | Morphius                    | Notebook    | [4583655d0a](https://linux-hardware.org/?probe=4583655d0a) | Mar 10, 2025 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [388597b49e](https://linux-hardware.org/?probe=388597b49e) | Mar 09, 2025 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [dd1188499d](https://linux-hardware.org/?probe=dd1188499d) | Mar 09, 2025 |
| MSI           | PS42 8RB                    | Notebook    | [78230fb07b](https://linux-hardware.org/?probe=78230fb07b) | Mar 09, 2025 |
| ACCENT        | SMART 140                   | Notebook    | [dc5161eba0](https://linux-hardware.org/?probe=dc5161eba0) | Mar 09, 2025 |
| HP            | Pavilion g7                 | Notebook    | [832283d8a1](https://linux-hardware.org/?probe=832283d8a1) | Mar 08, 2025 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [64a94d8784](https://linux-hardware.org/?probe=64a94d8784) | Mar 08, 2025 |
| Acer          | TravelMate Spin B311RN-3... | Convertible | [a1f0eec4bf](https://linux-hardware.org/?probe=a1f0eec4bf) | Mar 08, 2025 |
| HP            | Laptop 14-cf1xxx            | Notebook    | [6dbdba4503](https://linux-hardware.org/?probe=6dbdba4503) | Mar 08, 2025 |
| HP            | ENVY x360 Convertible 13... | Convertible | [dcf10ec46a](https://linux-hardware.org/?probe=dcf10ec46a) | Mar 07, 2025 |
| Dell          | 00V62H A01                  | Desktop     | [d8823e749c](https://linux-hardware.org/?probe=d8823e749c) | Mar 07, 2025 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [df2be654d8](https://linux-hardware.org/?probe=df2be654d8) | Mar 07, 2025 |
| HP            | OMEN by Laptop              | Notebook    | [62ec362c9e](https://linux-hardware.org/?probe=62ec362c9e) | Mar 07, 2025 |
| HP            | OMEN by Laptop              | Notebook    | [88e4bd362c](https://linux-hardware.org/?probe=88e4bd362c) | Mar 07, 2025 |
| Acer          | Aspire A515-46              | Notebook    | [70b67664c7](https://linux-hardware.org/?probe=70b67664c7) | Mar 06, 2025 |
| ASUSTek       | X751LD                      | Notebook    | [18516d05b3](https://linux-hardware.org/?probe=18516d05b3) | Mar 06, 2025 |
| Dell          | Precision M4800             | Notebook    | [77bd8a8709](https://linux-hardware.org/?probe=77bd8a8709) | Mar 05, 2025 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [247af323ec](https://linux-hardware.org/?probe=247af323ec) | Mar 04, 2025 |
| ASUSTek       | TP300LA                     | Notebook    | [bd5141417a](https://linux-hardware.org/?probe=bd5141417a) | Mar 03, 2025 |
| Dell          | 0WR7PY A01                  | Desktop     | [bc78df3255](https://linux-hardware.org/?probe=bc78df3255) | Mar 01, 2025 |
| ASUSTek       | TP300LA                     | Notebook    | [d34ec4e1c9](https://linux-hardware.org/?probe=d34ec4e1c9) | Mar 01, 2025 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [53e7ec6bd5](https://linux-hardware.org/?probe=53e7ec6bd5) | Mar 01, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [84b16f9e0b](https://linux-hardware.org/?probe=84b16f9e0b) | Feb 28, 2025 |
| MSI           | PRO A620M-E                 | Desktop     | [bd6c9835d7](https://linux-hardware.org/?probe=bd6c9835d7) | Feb 28, 2025 |
| HP            | Laptop 14-cf1xxx            | Notebook    | [d188eaf072](https://linux-hardware.org/?probe=d188eaf072) | Feb 28, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [d59756e98b](https://linux-hardware.org/?probe=d59756e98b) | Feb 28, 2025 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | Notebook    | [f855a3facf](https://linux-hardware.org/?probe=f855a3facf) | Feb 27, 2025 |
| Lenovo        | G50-80 80L0                 | Notebook    | [0381a48ff6](https://linux-hardware.org/?probe=0381a48ff6) | Feb 27, 2025 |
| ASUSTek       | H110M-A                     | Desktop     | [87343af499](https://linux-hardware.org/?probe=87343af499) | Feb 27, 2025 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [0de213192e](https://linux-hardware.org/?probe=0de213192e) | Feb 26, 2025 |
| Dell          | Precision 5530              | Notebook    | [40c558699b](https://linux-hardware.org/?probe=40c558699b) | Feb 26, 2025 |
| Dell          | Precision 5530              | Notebook    | [eb8a047c35](https://linux-hardware.org/?probe=eb8a047c35) | Feb 26, 2025 |
| Dell          | 00V62H A01                  | Desktop     | [3ac96a7d81](https://linux-hardware.org/?probe=3ac96a7d81) | Feb 26, 2025 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [f6cd9296cf](https://linux-hardware.org/?probe=f6cd9296cf) | Feb 25, 2025 |
| Lenovo        | 0x30F617AA NOK              | Desktop     | [3ecccff26d](https://linux-hardware.org/?probe=3ecccff26d) | Feb 25, 2025 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | Notebook    | [a934b12213](https://linux-hardware.org/?probe=a934b12213) | Feb 25, 2025 |
| Lenovo        | G560 20042                  | Notebook    | [c4003cae51](https://linux-hardware.org/?probe=c4003cae51) | Feb 24, 2025 |
| Lenovo        | G560 20042                  | Notebook    | [728057bf55](https://linux-hardware.org/?probe=728057bf55) | Feb 24, 2025 |
| Dell          | 0WR7PY A01                  | Desktop     | [fe278f1e68](https://linux-hardware.org/?probe=fe278f1e68) | Feb 24, 2025 |
| Google        | Eve                         | Convertible | [32790e61af](https://linux-hardware.org/?probe=32790e61af) | Feb 24, 2025 |
| Intel         | NUC7i5BNB J31144-307        | Mini pc     | [d5f509cf67](https://linux-hardware.org/?probe=d5f509cf67) | Feb 23, 2025 |
| Intel         | NUC7i5BNB J31144-307        | Mini pc     | [6417a9be15](https://linux-hardware.org/?probe=6417a9be15) | Feb 23, 2025 |
| Intel         | NUC7i5BNB J31144-307        | Mini pc     | [28ae761666](https://linux-hardware.org/?probe=28ae761666) | Feb 23, 2025 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [40358ecb17](https://linux-hardware.org/?probe=40358ecb17) | Feb 23, 2025 |
| Onda TLC      | Oliver Book A1              | Tablet      | [ba565faa60](https://linux-hardware.org/?probe=ba565faa60) | Feb 23, 2025 |
| Biostar       | A58MD                       | Desktop     | [79d6ec6b7a](https://linux-hardware.org/?probe=79d6ec6b7a) | Feb 22, 2025 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [5fab8982a9](https://linux-hardware.org/?probe=5fab8982a9) | Feb 21, 2025 |
| ASUSTek       | X201EP                      | Notebook    | [ef79469334](https://linux-hardware.org/?probe=ef79469334) | Feb 21, 2025 |
| Apple         | Mac-F2268CC8                | All in one  | [bdecd50139](https://linux-hardware.org/?probe=bdecd50139) | Feb 21, 2025 |
| Acer          | TravelMate B113             | Notebook    | [c39a4b0239](https://linux-hardware.org/?probe=c39a4b0239) | Feb 20, 2025 |
| HP            | Laptop 17-by3xxx            | Notebook    | [98f0606758](https://linux-hardware.org/?probe=98f0606758) | Feb 19, 2025 |
| Acer          | TravelMate B113             | Notebook    | [449d7ffd1c](https://linux-hardware.org/?probe=449d7ffd1c) | Feb 19, 2025 |
| Lenovo        | ThinkPad T570 W10DG 20JW... | Notebook    | [bb3561f31c](https://linux-hardware.org/?probe=bb3561f31c) | Feb 18, 2025 |
| Lenovo        | ThinkPad T570 W10DG 20JW... | Notebook    | [5120c6795a](https://linux-hardware.org/?probe=5120c6795a) | Feb 18, 2025 |
| Apple         | Mac-F2218EA9                | All in one  | [f837d32eee](https://linux-hardware.org/?probe=f837d32eee) | Feb 17, 2025 |
| Lenovo        | ThinkPad T530 23595JU       | Notebook    | [6aa540def5](https://linux-hardware.org/?probe=6aa540def5) | Feb 17, 2025 |
| HP            | Pavilion dv7                | Notebook    | [527154a620](https://linux-hardware.org/?probe=527154a620) | Feb 14, 2025 |
| Acer          | Swift SF114-34              | Notebook    | [1a20c83b5f](https://linux-hardware.org/?probe=1a20c83b5f) | Feb 14, 2025 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [51336fd7e0](https://linux-hardware.org/?probe=51336fd7e0) | Feb 13, 2025 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [6a27bc1436](https://linux-hardware.org/?probe=6a27bc1436) | Feb 13, 2025 |
| MSI           | GL65 Leopard 10SCXK         | Notebook    | [eceec59e78](https://linux-hardware.org/?probe=eceec59e78) | Feb 13, 2025 |
| ASUSTek       | X751LD                      | Notebook    | [02b451f50a](https://linux-hardware.org/?probe=02b451f50a) | Feb 13, 2025 |
| Sony          | SVF1521A1EW                 | Notebook    | [b31f8e7865](https://linux-hardware.org/?probe=b31f8e7865) | Feb 13, 2025 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [763541c663](https://linux-hardware.org/?probe=763541c663) | Feb 11, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [018d6a2976](https://linux-hardware.org/?probe=018d6a2976) | Feb 11, 2025 |
| Lenovo        | ThinkPad A475 20KMS05X1A    | Notebook    | [de9c7d0e0d](https://linux-hardware.org/?probe=de9c7d0e0d) | Feb 09, 2025 |
| Apple         | MacBookPro10,2              | Notebook    | [cac68d80c4](https://linux-hardware.org/?probe=cac68d80c4) | Feb 08, 2025 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [809dfbac41](https://linux-hardware.org/?probe=809dfbac41) | Feb 07, 2025 |
| HP            | Compaq 6735b                | Notebook    | [18b728a0f3](https://linux-hardware.org/?probe=18b728a0f3) | Feb 05, 2025 |
| Intel         | D946GZIS AAD66165-502       | Desktop     | [d3539a4af6](https://linux-hardware.org/?probe=d3539a4af6) | Feb 04, 2025 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [52786de2ac](https://linux-hardware.org/?probe=52786de2ac) | Feb 03, 2025 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [1ad66896cc](https://linux-hardware.org/?probe=1ad66896cc) | Feb 02, 2025 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [f276b0cec6](https://linux-hardware.org/?probe=f276b0cec6) | Feb 02, 2025 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [d00a2ec04e](https://linux-hardware.org/?probe=d00a2ec04e) | Feb 02, 2025 |
| HP            | ZBook 15                    | Notebook    | [e7809c4c4d](https://linux-hardware.org/?probe=e7809c4c4d) | Feb 01, 2025 |
| Apple         | MacBookPro8,3               | Notebook    | [cb543048e9](https://linux-hardware.org/?probe=cb543048e9) | Feb 01, 2025 |
| Alienware     | 15 R3                       | Notebook    | [b4c03288d7](https://linux-hardware.org/?probe=b4c03288d7) | Jan 31, 2025 |
| BESSTAR Te... | GB7B                        | Mini pc     | [82f71048ae](https://linux-hardware.org/?probe=82f71048ae) | Jan 30, 2025 |
| Thomson       | N17V3C8WH512                | Notebook    | [12cead9c03](https://linux-hardware.org/?probe=12cead9c03) | Jan 29, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [a35023f16c](https://linux-hardware.org/?probe=a35023f16c) | Jan 29, 2025 |
| Dell          | System Vostro 3750          | Notebook    | [d51079ff85](https://linux-hardware.org/?probe=d51079ff85) | Jan 28, 2025 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [c6364f1e5c](https://linux-hardware.org/?probe=c6364f1e5c) | Jan 27, 2025 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ae91f051ec](https://linux-hardware.org/?probe=ae91f051ec) | Jan 27, 2025 |
| Thomson       | N17V3C8WH512                | Notebook    | [7bf5e0c404](https://linux-hardware.org/?probe=7bf5e0c404) | Jan 27, 2025 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Notebook    | [0079d4634b](https://linux-hardware.org/?probe=0079d4634b) | Jan 26, 2025 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [7f6ddaaa50](https://linux-hardware.org/?probe=7f6ddaaa50) | Jan 25, 2025 |
| Lenovo        | Z710 20250                  | Notebook    | [c5c8052d20](https://linux-hardware.org/?probe=c5c8052d20) | Jan 25, 2025 |
| Acer          | Veriton N4640G              | Desktop     | [d6ef6686cb](https://linux-hardware.org/?probe=d6ef6686cb) | Jan 24, 2025 |
| Apple         | MacBookPro10,2              | Notebook    | [43ba3065b1](https://linux-hardware.org/?probe=43ba3065b1) | Jan 24, 2025 |
| OEM           | X79-Turbo                   | Desktop     | [15b2eded0d](https://linux-hardware.org/?probe=15b2eded0d) | Jan 23, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [340a1c98c0](https://linux-hardware.org/?probe=340a1c98c0) | Jan 23, 2025 |
| Acer          | Aspire 5750ZG               | Notebook    | [b55d95dc40](https://linux-hardware.org/?probe=b55d95dc40) | Jan 23, 2025 |
| Acer          | Aspire 5750ZG               | Notebook    | [fa9b739c95](https://linux-hardware.org/?probe=fa9b739c95) | Jan 23, 2025 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [e82bc0c198](https://linux-hardware.org/?probe=e82bc0c198) | Jan 23, 2025 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [bf5db2a6e3](https://linux-hardware.org/?probe=bf5db2a6e3) | Jan 23, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [fde29a0789](https://linux-hardware.org/?probe=fde29a0789) | Jan 22, 2025 |
| HP            | ProBook 440 G1              | Notebook    | [f06739d6c0](https://linux-hardware.org/?probe=f06739d6c0) | Jan 21, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [add0826738](https://linux-hardware.org/?probe=add0826738) | Jan 21, 2025 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [e46469150e](https://linux-hardware.org/?probe=e46469150e) | Jan 21, 2025 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [4d186a07ef](https://linux-hardware.org/?probe=4d186a07ef) | Jan 20, 2025 |
| Toshiba       | Satellite Pro C50-A-1MX     | Notebook    | [5e87f5ed4b](https://linux-hardware.org/?probe=5e87f5ed4b) | Jan 20, 2025 |
| ASRock        | H67M-ITX                    | Desktop     | [c651095205](https://linux-hardware.org/?probe=c651095205) | Jan 19, 2025 |
| ASRock        | H67M-ITX                    | Desktop     | [420a17a67a](https://linux-hardware.org/?probe=420a17a67a) | Jan 18, 2025 |
| HP            | Laptop 17-by3xxx            | Notebook    | [93544fbfaa](https://linux-hardware.org/?probe=93544fbfaa) | Jan 18, 2025 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [71486dacb8](https://linux-hardware.org/?probe=71486dacb8) | Jan 18, 2025 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [5c60cb5bbf](https://linux-hardware.org/?probe=5c60cb5bbf) | Jan 17, 2025 |
| HP            | EliteBook 840 G2            | Notebook    | [fa0fd7dffc](https://linux-hardware.org/?probe=fa0fd7dffc) | Jan 17, 2025 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [fd586e36f3](https://linux-hardware.org/?probe=fd586e36f3) | Jan 15, 2025 |
| HP            | Notebook                    | Notebook    | [f011276919](https://linux-hardware.org/?probe=f011276919) | Jan 15, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [1c4187a80e](https://linux-hardware.org/?probe=1c4187a80e) | Jan 15, 2025 |
| Dell          | 09M8Y8 A01                  | Desktop     | [fb46c2e3a4](https://linux-hardware.org/?probe=fb46c2e3a4) | Jan 14, 2025 |
| Dell          | 09M8Y8 A01                  | Desktop     | [e9d0c75a0c](https://linux-hardware.org/?probe=e9d0c75a0c) | Jan 14, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [47815cfe5b](https://linux-hardware.org/?probe=47815cfe5b) | Jan 14, 2025 |
| Apple         | MacBookPro10,1              | Notebook    | [86cc3c8042](https://linux-hardware.org/?probe=86cc3c8042) | Jan 14, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [bc2fc5f436](https://linux-hardware.org/?probe=bc2fc5f436) | Jan 13, 2025 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [3e5ea876fa](https://linux-hardware.org/?probe=3e5ea876fa) | Jan 13, 2025 |
| HP            | Notebook                    | Notebook    | [3b15487100](https://linux-hardware.org/?probe=3b15487100) | Jan 12, 2025 |
| Toshiba       | Satellite C50-B             | Notebook    | [6030ba6297](https://linux-hardware.org/?probe=6030ba6297) | Jan 12, 2025 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [2cc9d00747](https://linux-hardware.org/?probe=2cc9d00747) | Jan 12, 2025 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [ef02e1e9f9](https://linux-hardware.org/?probe=ef02e1e9f9) | Jan 12, 2025 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | Notebook    | [92181b0356](https://linux-hardware.org/?probe=92181b0356) | Jan 11, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [ec217c6326](https://linux-hardware.org/?probe=ec217c6326) | Jan 11, 2025 |
| Dell          | Latitude E7470              | Notebook    | [06c5f3289c](https://linux-hardware.org/?probe=06c5f3289c) | Jan 11, 2025 |
| Shenzhen M... | F7BSC                       | Mini pc     | [c52dd861ff](https://linux-hardware.org/?probe=c52dd861ff) | Jan 11, 2025 |
| HONOR         | NBR-WAX9                    | Notebook    | [243ef437b7](https://linux-hardware.org/?probe=243ef437b7) | Jan 10, 2025 |
| HP            | 83E8                        | Desktop     | [c6edbdb9e8](https://linux-hardware.org/?probe=c6edbdb9e8) | Jan 10, 2025 |
| Toshiba       | Satellite C50-B             | Notebook    | [ecea6f880e](https://linux-hardware.org/?probe=ecea6f880e) | Jan 10, 2025 |
| Panasonic     | CF-31SFLEC1M                | Notebook    | [d3a94176d7](https://linux-hardware.org/?probe=d3a94176d7) | Jan 10, 2025 |
| ASRock        | B650M-H/M.2+                | Desktop     | [44990dc3cf](https://linux-hardware.org/?probe=44990dc3cf) | Jan 09, 2025 |
| Acer          | Nitro AN515-47              | Notebook    | [6382503044](https://linux-hardware.org/?probe=6382503044) | Jan 09, 2025 |
| Gigabyte      | MRHM3AP                     | Desktop     | [38c0271497](https://linux-hardware.org/?probe=38c0271497) | Jan 08, 2025 |
| Apple         | MacBookPro5,4               | Notebook    | [38c695b157](https://linux-hardware.org/?probe=38c695b157) | Jan 07, 2025 |
| Dell          | Latitude 5580               | Notebook    | [7bc4688d7d](https://linux-hardware.org/?probe=7bc4688d7d) | Jan 07, 2025 |
| Apple         | Mac-F2208EC8                | Mini pc     | [e1afcdc469](https://linux-hardware.org/?probe=e1afcdc469) | Jan 07, 2025 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [f10a2b06fd](https://linux-hardware.org/?probe=f10a2b06fd) | Jan 06, 2025 |
| MSI           | G31TM-P21                   | Desktop     | [7f868dd6f9](https://linux-hardware.org/?probe=7f868dd6f9) | Jan 06, 2025 |
| Samsung       | 900X3C/900X4C/900X4D        | Notebook    | [cbe6ed9631](https://linux-hardware.org/?probe=cbe6ed9631) | Jan 05, 2025 |
| Digma Pro     | Minimax U1 DPP5-8CXN01      | Mini pc     | [c6d2f011fa](https://linux-hardware.org/?probe=c6d2f011fa) | Jan 05, 2025 |
| Dell          | Inspiron 1545               | Notebook    | [6d5ccbb5f9](https://linux-hardware.org/?probe=6d5ccbb5f9) | Jan 05, 2025 |
| Dell          | XPS L412Z                   | Notebook    | [d8b969a9e6](https://linux-hardware.org/?probe=d8b969a9e6) | Jan 05, 2025 |
| Dell          | XPS L412Z                   | Notebook    | [f4cfef6dcc](https://linux-hardware.org/?probe=f4cfef6dcc) | Jan 05, 2025 |
| Apple         | MacBook3,1                  | Notebook    | [be78213991](https://linux-hardware.org/?probe=be78213991) | Jan 05, 2025 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [79752b904b](https://linux-hardware.org/?probe=79752b904b) | Jan 04, 2025 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [d5f19c64ad](https://linux-hardware.org/?probe=d5f19c64ad) | Jan 04, 2025 |
| Apple         | MacBookPro7,1               | Notebook    | [7961299452](https://linux-hardware.org/?probe=7961299452) | Jan 04, 2025 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [bbf6d05761](https://linux-hardware.org/?probe=bbf6d05761) | Jan 03, 2025 |
| Apple         | MacBookPro8,1               | Notebook    | [c208215b7f](https://linux-hardware.org/?probe=c208215b7f) | Jan 03, 2025 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [7b1adcdde1](https://linux-hardware.org/?probe=7b1adcdde1) | Jan 03, 2025 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [cacf1ad26f](https://linux-hardware.org/?probe=cacf1ad26f) | Jan 02, 2025 |
| Lenovo        | G585 20137                  | Notebook    | [f7dac7bbad](https://linux-hardware.org/?probe=f7dac7bbad) | Jan 02, 2025 |
| Intel         | H61                         | Desktop     | [0f76193421](https://linux-hardware.org/?probe=0f76193421) | Jan 02, 2025 |
| Medion        | Akoya E6240T                | Notebook    | [dc4b306a46](https://linux-hardware.org/?probe=dc4b306a46) | Jan 02, 2025 |
| Dell          | Latitude 5400               | Notebook    | [7a418a2cca](https://linux-hardware.org/?probe=7a418a2cca) | Jan 01, 2025 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [f7cc7cc8d1](https://linux-hardware.org/?probe=f7cc7cc8d1) | Jan 01, 2025 |
| MSI           | A88XM-E35 V2                | Desktop     | [d3df8a394a](https://linux-hardware.org/?probe=d3df8a394a) | Dec 30, 2024 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [1de7d2e8fb](https://linux-hardware.org/?probe=1de7d2e8fb) | Dec 30, 2024 |
| ASUSTek       | H110M-D                     | Desktop     | [a61b42dd42](https://linux-hardware.org/?probe=a61b42dd42) | Dec 29, 2024 |
| ASUSTek       | X555LDB                     | Notebook    | [f11b5b7320](https://linux-hardware.org/?probe=f11b5b7320) | Dec 29, 2024 |
| Lenovo        | IdeaPad Y560                | Notebook    | [e36139662d](https://linux-hardware.org/?probe=e36139662d) | Dec 28, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [3dd541f1a9](https://linux-hardware.org/?probe=3dd541f1a9) | Dec 28, 2024 |
| HP            | ProBook 645 G2              | Notebook    | [b57a3a877b](https://linux-hardware.org/?probe=b57a3a877b) | Dec 27, 2024 |
| NEC Comput... | PC-LL750MSW                 | Notebook    | [55d20a7230](https://linux-hardware.org/?probe=55d20a7230) | Dec 27, 2024 |
| Dell          | Inspiron 15-3552            | Notebook    | [1d01677080](https://linux-hardware.org/?probe=1d01677080) | Dec 27, 2024 |
| Packard Be... | EasyNote TJ75               | Notebook    | [7a5bc8251a](https://linux-hardware.org/?probe=7a5bc8251a) | Dec 27, 2024 |
| Packard Be... | EasyNote TJ75               | Notebook    | [b46109e7f3](https://linux-hardware.org/?probe=b46109e7f3) | Dec 27, 2024 |
| Sony          | SVF14213CLB                 | Notebook    | [dbcabf3c36](https://linux-hardware.org/?probe=dbcabf3c36) | Dec 27, 2024 |
| Pegatron      | A15                         | Notebook    | [2649401416](https://linux-hardware.org/?probe=2649401416) | Dec 26, 2024 |
| ASRock        | X570 Extreme4               | Desktop     | [65cad1da61](https://linux-hardware.org/?probe=65cad1da61) | Dec 26, 2024 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [8230b0cf45](https://linux-hardware.org/?probe=8230b0cf45) | Dec 25, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [f288e84971](https://linux-hardware.org/?probe=f288e84971) | Dec 25, 2024 |
| Apple         | MacBookPro10,1              | Notebook    | [4225950551](https://linux-hardware.org/?probe=4225950551) | Dec 25, 2024 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | Notebook    | [d1227bd0de](https://linux-hardware.org/?probe=d1227bd0de) | Dec 25, 2024 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [4c23073f21](https://linux-hardware.org/?probe=4c23073f21) | Dec 25, 2024 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [2729b6a19c](https://linux-hardware.org/?probe=2729b6a19c) | Dec 25, 2024 |
| Gigabyte      | B85M-HD3                    | Desktop     | [83d5947a2c](https://linux-hardware.org/?probe=83d5947a2c) | Dec 24, 2024 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [4e79bebde8](https://linux-hardware.org/?probe=4e79bebde8) | Dec 24, 2024 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [89e8e5ad41](https://linux-hardware.org/?probe=89e8e5ad41) | Dec 24, 2024 |
| Acer          | Aspire 5755G                | Notebook    | [d824794995](https://linux-hardware.org/?probe=d824794995) | Dec 23, 2024 |
| Samsung       | SR58P                       | Notebook    | [70e6a978b7](https://linux-hardware.org/?probe=70e6a978b7) | Dec 23, 2024 |
| Dell          | Latitude E6520              | Notebook    | [2bae6e63bb](https://linux-hardware.org/?probe=2bae6e63bb) | Dec 23, 2024 |
| Dell          | XPS 15 9550                 | Notebook    | [f1502af093](https://linux-hardware.org/?probe=f1502af093) | Dec 23, 2024 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [a649caaa82](https://linux-hardware.org/?probe=a649caaa82) | Dec 23, 2024 |
| Acer          | Aspire ES1-571              | Notebook    | [cb4b9da83f](https://linux-hardware.org/?probe=cb4b9da83f) | Dec 22, 2024 |
| MSI           | PRO B760-P WIFI DDR4        | Desktop     | [59c289d5b9](https://linux-hardware.org/?probe=59c289d5b9) | Dec 22, 2024 |
| Acer          | Aspire ES1-571              | Notebook    | [48537b040b](https://linux-hardware.org/?probe=48537b040b) | Dec 22, 2024 |
| Dell          | 0MWYPT A00                  | Desktop     | [98cc5ad973](https://linux-hardware.org/?probe=98cc5ad973) | Dec 22, 2024 |
| Dell          | 0MWYPT A00                  | Desktop     | [dd73af7555](https://linux-hardware.org/?probe=dd73af7555) | Dec 22, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [762ab31569](https://linux-hardware.org/?probe=762ab31569) | Dec 22, 2024 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [4c934647d2](https://linux-hardware.org/?probe=4c934647d2) | Dec 21, 2024 |
| ASUSTek       | X555LDB                     | Notebook    | [783e6ed502](https://linux-hardware.org/?probe=783e6ed502) | Dec 20, 2024 |
| AWOW          | NY PC BOX                   | Mini pc     | [d787dd8103](https://linux-hardware.org/?probe=d787dd8103) | Dec 20, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [8e8317c6a6](https://linux-hardware.org/?probe=8e8317c6a6) | Dec 19, 2024 |
| ASUSTek       | UX30                        | Notebook    | [d75f3afdf6](https://linux-hardware.org/?probe=d75f3afdf6) | Dec 18, 2024 |
| Dell          | Precision 5530              | Notebook    | [3292cf1103](https://linux-hardware.org/?probe=3292cf1103) | Dec 18, 2024 |
| Gigabyte      | Z77-D3H                     | Desktop     | [9a64691207](https://linux-hardware.org/?probe=9a64691207) | Dec 17, 2024 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [987844d0b8](https://linux-hardware.org/?probe=987844d0b8) | Dec 17, 2024 |
| HP            | 8266                        | Desktop     | [ccd7d6b235](https://linux-hardware.org/?probe=ccd7d6b235) | Dec 17, 2024 |
| ASUSTek       | X751MA                      | Notebook    | [016d948a0c](https://linux-hardware.org/?probe=016d948a0c) | Dec 17, 2024 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [03d550b439](https://linux-hardware.org/?probe=03d550b439) | Dec 17, 2024 |
| GEEKOM        | A8                          | Desktop     | [821fae98e5](https://linux-hardware.org/?probe=821fae98e5) | Dec 17, 2024 |
| HP            | Pavilion dv6                | Notebook    | [89ec19d64a](https://linux-hardware.org/?probe=89ec19d64a) | Dec 17, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [28d3412139](https://linux-hardware.org/?probe=28d3412139) | Dec 17, 2024 |
| HP            | Laptop 17-by3xxx            | Notebook    | [cb8341eaca](https://linux-hardware.org/?probe=cb8341eaca) | Dec 17, 2024 |
| Pegatron      | A15                         | Notebook    | [266dd27eba](https://linux-hardware.org/?probe=266dd27eba) | Dec 16, 2024 |
| HP            | 83E8                        | Desktop     | [77d40d025a](https://linux-hardware.org/?probe=77d40d025a) | Dec 16, 2024 |
| Intel         | Unknown                     | Desktop     | [fcbbdc5c06](https://linux-hardware.org/?probe=fcbbdc5c06) | Dec 16, 2024 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [f521816a4d](https://linux-hardware.org/?probe=f521816a4d) | Dec 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [abfa48ae27](https://linux-hardware.org/?probe=abfa48ae27) | Dec 15, 2024 |
| Dell          | 0F6X5P A00                  | Desktop     | [059cf0cd47](https://linux-hardware.org/?probe=059cf0cd47) | Dec 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [256e4c3f4a](https://linux-hardware.org/?probe=256e4c3f4a) | Dec 15, 2024 |
| HP            | ProBook 6570b               | Notebook    | [70dbe6620b](https://linux-hardware.org/?probe=70dbe6620b) | Dec 14, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [4a2f8153d2](https://linux-hardware.org/?probe=4a2f8153d2) | Dec 14, 2024 |
| Dell          | 0F6X5P A00                  | Desktop     | [f9eae65d13](https://linux-hardware.org/?probe=f9eae65d13) | Dec 14, 2024 |
| Dell          | Inspiron 5547               | Notebook    | [4427bcded0](https://linux-hardware.org/?probe=4427bcded0) | Dec 14, 2024 |
| Dell          | Inspiron 5547               | Notebook    | [5641fb7941](https://linux-hardware.org/?probe=5641fb7941) | Dec 14, 2024 |
| HP            | 8299                        | Desktop     | [44a762b74e](https://linux-hardware.org/?probe=44a762b74e) | Dec 14, 2024 |
| HP            | 8299                        | Desktop     | [f0c7982d81](https://linux-hardware.org/?probe=f0c7982d81) | Dec 14, 2024 |
| Acer          | Aspire 8730                 | Notebook    | [8c0f6ed012](https://linux-hardware.org/?probe=8c0f6ed012) | Dec 14, 2024 |
| Acer          | Aspire A515-48M             | Notebook    | [1bd13cf77f](https://linux-hardware.org/?probe=1bd13cf77f) | Dec 14, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [262a2aa975](https://linux-hardware.org/?probe=262a2aa975) | Dec 13, 2024 |
| Acer          | Aspire 8730                 | Notebook    | [1ab4a28fcf](https://linux-hardware.org/?probe=1ab4a28fcf) | Dec 13, 2024 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [37664cf5d9](https://linux-hardware.org/?probe=37664cf5d9) | Dec 13, 2024 |
| Sony          | SVS1313V9RB                 | Notebook    | [52421e92ce](https://linux-hardware.org/?probe=52421e92ce) | Dec 12, 2024 |
| Sony          | SVS1313V9RB                 | Notebook    | [53c77f8751](https://linux-hardware.org/?probe=53c77f8751) | Dec 12, 2024 |
| Unknown       | Unknown                     | Notebook    | [2e17fa2c66](https://linux-hardware.org/?probe=2e17fa2c66) | Dec 12, 2024 |
| Chuwi         | UBook                       | Notebook    | [08e88467cb](https://linux-hardware.org/?probe=08e88467cb) | Dec 12, 2024 |
| Apple         | Mac-F2268DC8                | All in one  | [ad8b7d1b8f](https://linux-hardware.org/?probe=ad8b7d1b8f) | Dec 12, 2024 |
| Apple         | Mac-F2268DC8                | All in one  | [6b05e8feb0](https://linux-hardware.org/?probe=6b05e8feb0) | Dec 12, 2024 |
| ASUSTek       | X550CL                      | Notebook    | [e471757e1c](https://linux-hardware.org/?probe=e471757e1c) | Dec 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [8444dbbcc1](https://linux-hardware.org/?probe=8444dbbcc1) | Dec 10, 2024 |
| Microtech     | ebookPro                    | Notebook    | [4e6f89ca56](https://linux-hardware.org/?probe=4e6f89ca56) | Dec 10, 2024 |
| Acer          | Swift SF314-56G             | Notebook    | [64815f9248](https://linux-hardware.org/?probe=64815f9248) | Dec 09, 2024 |
| Intel         | NUC7i3BNB J22859-309        | Mini pc     | [9319560a05](https://linux-hardware.org/?probe=9319560a05) | Dec 09, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | Notebook    | [fc797d558c](https://linux-hardware.org/?probe=fc797d558c) | Dec 08, 2024 |
| Unknown       | Unknown                     | Notebook    | [bd30f7f45d](https://linux-hardware.org/?probe=bd30f7f45d) | Dec 08, 2024 |
| HP            | 82C0                        | Mini pc     | [f6987473a1](https://linux-hardware.org/?probe=f6987473a1) | Dec 07, 2024 |
| Dell          | Latitude 3340               | Notebook    | [07c627667a](https://linux-hardware.org/?probe=07c627667a) | Dec 07, 2024 |
| HP            | Laptop 17z-ca100            | Notebook    | [e6144203c6](https://linux-hardware.org/?probe=e6144203c6) | Dec 07, 2024 |
| SK hynix      | 10WWA464B                   | Tablet      | [56ca392159](https://linux-hardware.org/?probe=56ca392159) | Dec 07, 2024 |
| eMachines     | eME732Z                     | Notebook    | [1c64772130](https://linux-hardware.org/?probe=1c64772130) | Dec 06, 2024 |
| Panasonic     | CF-52PFP54QL                | Notebook    | [bcafd21454](https://linux-hardware.org/?probe=bcafd21454) | Dec 06, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [3c0b439ef8](https://linux-hardware.org/?probe=3c0b439ef8) | Dec 06, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [477a7b324b](https://linux-hardware.org/?probe=477a7b324b) | Dec 06, 2024 |
| HUAWEI        | BC11HGSA0 V100R003          | Server      | [ea4033794a](https://linux-hardware.org/?probe=ea4033794a) | Dec 05, 2024 |
| Lenovo        | IdeaPad S205 1038D8G        | Notebook    | [78b460173f](https://linux-hardware.org/?probe=78b460173f) | Dec 05, 2024 |
| Chuwi         | UBook                       | Notebook    | [ddba94874a](https://linux-hardware.org/?probe=ddba94874a) | Dec 04, 2024 |
| HP            | Pavilion dv7                | Notebook    | [8d22c82b8d](https://linux-hardware.org/?probe=8d22c82b8d) | Dec 04, 2024 |
| Apple         | MacBook4,1                  | Notebook    | [915a1dbb22](https://linux-hardware.org/?probe=915a1dbb22) | Dec 04, 2024 |
| HP            | EliteBook 2170p             | Notebook    | [39de9fd95f](https://linux-hardware.org/?probe=39de9fd95f) | Dec 04, 2024 |
| Intel         | B75 V1.1                    | Desktop     | [d6aad9d651](https://linux-hardware.org/?probe=d6aad9d651) | Dec 03, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [8517a48127](https://linux-hardware.org/?probe=8517a48127) | Dec 03, 2024 |
| Apple         | Mac-F2268DC8                | All in one  | [c2dd28599e](https://linux-hardware.org/?probe=c2dd28599e) | Dec 03, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [085d5938c0](https://linux-hardware.org/?probe=085d5938c0) | Dec 03, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [99cb99a15c](https://linux-hardware.org/?probe=99cb99a15c) | Dec 03, 2024 |
| Toshiba       | Satellite L50-B             | Notebook    | [f0195c6929](https://linux-hardware.org/?probe=f0195c6929) | Dec 02, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [a12ee189e3](https://linux-hardware.org/?probe=a12ee189e3) | Dec 02, 2024 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [1a9a544a72](https://linux-hardware.org/?probe=1a9a544a72) | Dec 02, 2024 |
| Intel         | X99-P4 V5.11                | Desktop     | [b5079a1a8d](https://linux-hardware.org/?probe=b5079a1a8d) | Dec 02, 2024 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [114cab1a48](https://linux-hardware.org/?probe=114cab1a48) | Dec 02, 2024 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [ffa565d696](https://linux-hardware.org/?probe=ffa565d696) | Dec 02, 2024 |
| Intel         | D945GCL AAD75361-301        | Desktop     | [f04b1a58c2](https://linux-hardware.org/?probe=f04b1a58c2) | Dec 01, 2024 |
| Intel         | D945GCL AAD75361-301        | Desktop     | [fc715bb336](https://linux-hardware.org/?probe=fc715bb336) | Dec 01, 2024 |
| Intel         | NUC5i5RYB H40999-504        | Mini pc     | [dde09fe131](https://linux-hardware.org/?probe=dde09fe131) | Dec 01, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [424834b527](https://linux-hardware.org/?probe=424834b527) | Dec 01, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [deda79f6f5](https://linux-hardware.org/?probe=deda79f6f5) | Dec 01, 2024 |
| ASRock        | H310CM-HG4                  | Desktop     | [86f4d79f62](https://linux-hardware.org/?probe=86f4d79f62) | Dec 01, 2024 |
| ASUSTek       | K93SV                       | Notebook    | [53af6a8e17](https://linux-hardware.org/?probe=53af6a8e17) | Nov 30, 2024 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [7b063d3dd7](https://linux-hardware.org/?probe=7b063d3dd7) | Nov 30, 2024 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [b69d5786a5](https://linux-hardware.org/?probe=b69d5786a5) | Nov 30, 2024 |
| Toshiba       | Satellite L50-B             | Notebook    | [344eaec320](https://linux-hardware.org/?probe=344eaec320) | Nov 29, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [f7578fb476](https://linux-hardware.org/?probe=f7578fb476) | Nov 29, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [a817c04b09](https://linux-hardware.org/?probe=a817c04b09) | Nov 29, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [dbc6940414](https://linux-hardware.org/?probe=dbc6940414) | Nov 29, 2024 |
| HP            | Pavilion dv7                | Notebook    | [1ae9d9a604](https://linux-hardware.org/?probe=1ae9d9a604) | Nov 29, 2024 |
| Dell          | Latitude 5420               | Notebook    | [9e6c2d1825](https://linux-hardware.org/?probe=9e6c2d1825) | Nov 28, 2024 |
| MicroByte     | ezbook                      | Notebook    | [167d9d082a](https://linux-hardware.org/?probe=167d9d082a) | Nov 28, 2024 |
| HP            | 3647h                       | Desktop     | [de1eb15f76](https://linux-hardware.org/?probe=de1eb15f76) | Nov 28, 2024 |
| Google        | Delbin                      | Notebook    | [e4f8dab394](https://linux-hardware.org/?probe=e4f8dab394) | Nov 27, 2024 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [7e022f0097](https://linux-hardware.org/?probe=7e022f0097) | Nov 27, 2024 |
| Apple         | Mac-F2218FA9                | All in one  | [3972b418fc](https://linux-hardware.org/?probe=3972b418fc) | Nov 27, 2024 |
| Lenovo        | ThinkCentre M81 7517A2F     | Desktop     | [51de0395d0](https://linux-hardware.org/?probe=51de0395d0) | Nov 27, 2024 |
| Acer          | Aspire E3-111               | Notebook    | [f90ddc6433](https://linux-hardware.org/?probe=f90ddc6433) | Nov 26, 2024 |
| Lenovo        | ThinkCentre M81 7517A2F     | Desktop     | [6ae2f479e0](https://linux-hardware.org/?probe=6ae2f479e0) | Nov 26, 2024 |
| Apple         | Mac-F2218FA9                | All in one  | [73767665be](https://linux-hardware.org/?probe=73767665be) | Nov 26, 2024 |
| Apple         | MacBookAir6,1               | Notebook    | [a42587525c](https://linux-hardware.org/?probe=a42587525c) | Nov 25, 2024 |
| Apple         | MacBookAir6,1               | Notebook    | [1d464cc8ce](https://linux-hardware.org/?probe=1d464cc8ce) | Nov 25, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | Notebook    | [d24fd529d4](https://linux-hardware.org/?probe=d24fd529d4) | Nov 25, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [0b3205081d](https://linux-hardware.org/?probe=0b3205081d) | Nov 22, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | Notebook    | [d7914ef50d](https://linux-hardware.org/?probe=d7914ef50d) | Nov 22, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [8ecfb38136](https://linux-hardware.org/?probe=8ecfb38136) | Nov 22, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [582b81fd6f](https://linux-hardware.org/?probe=582b81fd6f) | Nov 22, 2024 |
| ASRock        | 945GCM-S                    | Desktop     | [c1060979e3](https://linux-hardware.org/?probe=c1060979e3) | Nov 21, 2024 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [c785c1f7dd](https://linux-hardware.org/?probe=c785c1f7dd) | Nov 21, 2024 |
| HP            | ProBook 6560b               | Notebook    | [72ddcb1cf2](https://linux-hardware.org/?probe=72ddcb1cf2) | Nov 20, 2024 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [058f6bf1ac](https://linux-hardware.org/?probe=058f6bf1ac) | Nov 20, 2024 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [541dd7b9fb](https://linux-hardware.org/?probe=541dd7b9fb) | Nov 19, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [3f2eff0083](https://linux-hardware.org/?probe=3f2eff0083) | Nov 18, 2024 |
| Apple         | Mac-F2218EA9                | All in one  | [bf3651f419](https://linux-hardware.org/?probe=bf3651f419) | Nov 18, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b5f2062c2c](https://linux-hardware.org/?probe=b5f2062c2c) | Nov 18, 2024 |
| Lenovo        | ThinkPad X260 20F5A2FXTH    | Notebook    | [8609525ceb](https://linux-hardware.org/?probe=8609525ceb) | Nov 18, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [7d86d39596](https://linux-hardware.org/?probe=7d86d39596) | Nov 17, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [001f8b1280](https://linux-hardware.org/?probe=001f8b1280) | Nov 17, 2024 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | Notebook    | [8715440da3](https://linux-hardware.org/?probe=8715440da3) | Nov 17, 2024 |
| Dell          | Inspiron N5030              | Notebook    | [acf692231b](https://linux-hardware.org/?probe=acf692231b) | Nov 17, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [0d4cb9a88f](https://linux-hardware.org/?probe=0d4cb9a88f) | Nov 16, 2024 |
| HP            | 1998                        | Desktop     | [021e8262ce](https://linux-hardware.org/?probe=021e8262ce) | Nov 16, 2024 |
| Lenovo        | G50-80 80L0                 | Notebook    | [d31664cad1](https://linux-hardware.org/?probe=d31664cad1) | Nov 15, 2024 |
| HP            | 212B                        | Desktop     | [35097b8ab0](https://linux-hardware.org/?probe=35097b8ab0) | Nov 15, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [0259216292](https://linux-hardware.org/?probe=0259216292) | Nov 15, 2024 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [9d0d676179](https://linux-hardware.org/?probe=9d0d676179) | Nov 14, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [7029186fa5](https://linux-hardware.org/?probe=7029186fa5) | Nov 14, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [2f0fa7a4fa](https://linux-hardware.org/?probe=2f0fa7a4fa) | Nov 11, 2024 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [fc06ee6598](https://linux-hardware.org/?probe=fc06ee6598) | Nov 10, 2024 |
| Dell          | 0T4VP9 A00                  | All in one  | [939efc4955](https://linux-hardware.org/?probe=939efc4955) | Nov 10, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [68c27eb24c](https://linux-hardware.org/?probe=68c27eb24c) | Nov 10, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [a6930afc53](https://linux-hardware.org/?probe=a6930afc53) | Nov 10, 2024 |
| Dell          | Latitude 3390 2-in-1        | Convertible | [155af73dbd](https://linux-hardware.org/?probe=155af73dbd) | Nov 10, 2024 |
| Winnovo       | Vocbook                     | Convertible | [be7ba030af](https://linux-hardware.org/?probe=be7ba030af) | Nov 09, 2024 |
| Apple         | MacBookPro5,2               | Notebook    | [a0db5bcf03](https://linux-hardware.org/?probe=a0db5bcf03) | Nov 08, 2024 |
| Acer          | Aspire E5-771               | Notebook    | [9b889ed10a](https://linux-hardware.org/?probe=9b889ed10a) | Nov 08, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [41cbe4313e](https://linux-hardware.org/?probe=41cbe4313e) | Nov 06, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [0b5989c295](https://linux-hardware.org/?probe=0b5989c295) | Nov 06, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [71249fccac](https://linux-hardware.org/?probe=71249fccac) | Nov 06, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [ebcff700e9](https://linux-hardware.org/?probe=ebcff700e9) | Nov 06, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f37b129292](https://linux-hardware.org/?probe=f37b129292) | Nov 05, 2024 |
| LTD Delovo... | 15Y                         | Notebook    | [5553e46796](https://linux-hardware.org/?probe=5553e46796) | Nov 04, 2024 |
| LTD Delovo... | 15Y                         | Notebook    | [0187f0b5ab](https://linux-hardware.org/?probe=0187f0b5ab) | Nov 04, 2024 |
| Samsung       | 940XFG                      | Notebook    | [8d09e8db06](https://linux-hardware.org/?probe=8d09e8db06) | Nov 04, 2024 |
| Gigabyte      | B550 UD AC-Y1               | Desktop     | [f146362156](https://linux-hardware.org/?probe=f146362156) | Nov 04, 2024 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [f0b28bde30](https://linux-hardware.org/?probe=f0b28bde30) | Nov 03, 2024 |
| Dell          | Latitude 7420               | Notebook    | [2454ee0dbb](https://linux-hardware.org/?probe=2454ee0dbb) | Nov 03, 2024 |
| Lenovo        | G700 20251                  | Notebook    | [3af4ad6599](https://linux-hardware.org/?probe=3af4ad6599) | Nov 01, 2024 |
| Acer          | Aspire V3-772               | Notebook    | [9d4e69ab29](https://linux-hardware.org/?probe=9d4e69ab29) | Nov 01, 2024 |
| Acer          | Aspire V3-772               | Notebook    | [a48e5acfb4](https://linux-hardware.org/?probe=a48e5acfb4) | Nov 01, 2024 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [a8d14fa552](https://linux-hardware.org/?probe=a8d14fa552) | Nov 01, 2024 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [b39c2af6f5](https://linux-hardware.org/?probe=b39c2af6f5) | Oct 31, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [55ef342a18](https://linux-hardware.org/?probe=55ef342a18) | Oct 31, 2024 |
| HP            | ProBook 4535s               | Notebook    | [f66c124f3a](https://linux-hardware.org/?probe=f66c124f3a) | Oct 31, 2024 |
| Apple         | Mac-F2218EA9                | All in one  | [ed3df2f39c](https://linux-hardware.org/?probe=ed3df2f39c) | Oct 31, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [3fe4d1a80a](https://linux-hardware.org/?probe=3fe4d1a80a) | Oct 31, 2024 |
| ASUSTek       | K46CB                       | Notebook    | [e081c9ab8c](https://linux-hardware.org/?probe=e081c9ab8c) | Oct 30, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [91eb0db216](https://linux-hardware.org/?probe=91eb0db216) | Oct 30, 2024 |
| ASRock        | Z390 Phantom Gaming-ITX/... | Desktop     | [0e0a0fd3c5](https://linux-hardware.org/?probe=0e0a0fd3c5) | Oct 30, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [1755d407c9](https://linux-hardware.org/?probe=1755d407c9) | Oct 29, 2024 |
| HP            | Compaq 15                   | Notebook    | [fd2b849a08](https://linux-hardware.org/?probe=fd2b849a08) | Oct 28, 2024 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [3cf2d45223](https://linux-hardware.org/?probe=3cf2d45223) | Oct 28, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [cd7ca76c96](https://linux-hardware.org/?probe=cd7ca76c96) | Oct 27, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [59f6758081](https://linux-hardware.org/?probe=59f6758081) | Oct 25, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [73fb34d315](https://linux-hardware.org/?probe=73fb34d315) | Oct 25, 2024 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [c4829d7d0c](https://linux-hardware.org/?probe=c4829d7d0c) | Oct 25, 2024 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [e114c5afe5](https://linux-hardware.org/?probe=e114c5afe5) | Oct 24, 2024 |
| Dell          | Latitude 7370               | Notebook    | [355bbe7ecc](https://linux-hardware.org/?probe=355bbe7ecc) | Oct 24, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [92672f3d2c](https://linux-hardware.org/?probe=92672f3d2c) | Oct 23, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [8bbb5c5a53](https://linux-hardware.org/?probe=8bbb5c5a53) | Oct 23, 2024 |
| HP            | ProBook 6465b               | Notebook    | [3afb9ebed6](https://linux-hardware.org/?probe=3afb9ebed6) | Oct 23, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [ee7a3727e4](https://linux-hardware.org/?probe=ee7a3727e4) | Oct 23, 2024 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [1d8bed869f](https://linux-hardware.org/?probe=1d8bed869f) | Oct 23, 2024 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | Notebook    | [18058066d2](https://linux-hardware.org/?probe=18058066d2) | Oct 22, 2024 |
| Apple         | MacBookAir4,1               | Notebook    | [a899fd963a](https://linux-hardware.org/?probe=a899fd963a) | Oct 22, 2024 |
| Apple         | MacBookAir4,1               | Notebook    | [6c25a578b8](https://linux-hardware.org/?probe=6c25a578b8) | Oct 22, 2024 |
| Sony          | VPCEJ1Z1E                   | Notebook    | [d1da65abb4](https://linux-hardware.org/?probe=d1da65abb4) | Oct 22, 2024 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [25dc97604a](https://linux-hardware.org/?probe=25dc97604a) | Oct 22, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [76d8c86d01](https://linux-hardware.org/?probe=76d8c86d01) | Oct 22, 2024 |
| Lenovo        | Win8 STD EM DPK IPG         | All in one  | [5cca2e9488](https://linux-hardware.org/?probe=5cca2e9488) | Oct 22, 2024 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [faeb5479f8](https://linux-hardware.org/?probe=faeb5479f8) | Oct 21, 2024 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e188597923](https://linux-hardware.org/?probe=e188597923) | Oct 19, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [f63adab3c7](https://linux-hardware.org/?probe=f63adab3c7) | Oct 19, 2024 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [afb324991b](https://linux-hardware.org/?probe=afb324991b) | Oct 18, 2024 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [3337802835](https://linux-hardware.org/?probe=3337802835) | Oct 18, 2024 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [c16cede43b](https://linux-hardware.org/?probe=c16cede43b) | Oct 18, 2024 |
| Lenovo        | Win8 STD EM DPK IPG         | All in one  | [4792d62928](https://linux-hardware.org/?probe=4792d62928) | Oct 17, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [83508d3840](https://linux-hardware.org/?probe=83508d3840) | Oct 17, 2024 |
| Samsung       | 940XFG                      | Notebook    | [741f7a6544](https://linux-hardware.org/?probe=741f7a6544) | Oct 17, 2024 |
| Apple         | MacBook6,1                  | Notebook    | [d3b5f5da93](https://linux-hardware.org/?probe=d3b5f5da93) | Oct 17, 2024 |
| HP            | 2B3B                        | All in one  | [83af71f2e9](https://linux-hardware.org/?probe=83af71f2e9) | Oct 16, 2024 |
| HP            | 2B3B                        | All in one  | [6eb2a2cd32](https://linux-hardware.org/?probe=6eb2a2cd32) | Oct 16, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d0ac53c68a](https://linux-hardware.org/?probe=d0ac53c68a) | Oct 16, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [043f4904ae](https://linux-hardware.org/?probe=043f4904ae) | Oct 15, 2024 |
| Acer          | Aspire 7736                 | Notebook    | [be7f2e237f](https://linux-hardware.org/?probe=be7f2e237f) | Oct 15, 2024 |
| ASUSTek       | X555LPB                     | Notebook    | [2f3f2073da](https://linux-hardware.org/?probe=2f3f2073da) | Oct 14, 2024 |
| Acer          | Aspire 7736                 | Notebook    | [96c83e0281](https://linux-hardware.org/?probe=96c83e0281) | Oct 14, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [d2d644c166](https://linux-hardware.org/?probe=d2d644c166) | Oct 13, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [0615e499e7](https://linux-hardware.org/?probe=0615e499e7) | Oct 13, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | Notebook    | [cee555c4f8](https://linux-hardware.org/?probe=cee555c4f8) | Oct 13, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [030dbaca80](https://linux-hardware.org/?probe=030dbaca80) | Oct 13, 2024 |
| Positivo      | VJF154                      | Notebook    | [dbd1be19a4](https://linux-hardware.org/?probe=dbd1be19a4) | Oct 12, 2024 |
| Positivo      | VJF154                      | Notebook    | [11a95affa0](https://linux-hardware.org/?probe=11a95affa0) | Oct 12, 2024 |
| Sony          | VPCEJ1Z1E                   | Notebook    | [627da18a5d](https://linux-hardware.org/?probe=627da18a5d) | Oct 12, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [8a25a02400](https://linux-hardware.org/?probe=8a25a02400) | Oct 12, 2024 |
| HP            | Compaq 6530b (GW688AV)      | Notebook    | [2db6bf65e8](https://linux-hardware.org/?probe=2db6bf65e8) | Oct 12, 2024 |
| HP            | Compaq 6530b (GW688AV)      | Notebook    | [a9cb352415](https://linux-hardware.org/?probe=a9cb352415) | Oct 12, 2024 |
| Apple         | MacBookPro8,3               | Notebook    | [ca109e5057](https://linux-hardware.org/?probe=ca109e5057) | Oct 12, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [08d25ef16b](https://linux-hardware.org/?probe=08d25ef16b) | Oct 12, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [6c5d0a8a4b](https://linux-hardware.org/?probe=6c5d0a8a4b) | Oct 12, 2024 |
| HP            | 15                          | Notebook    | [812b65f0fe](https://linux-hardware.org/?probe=812b65f0fe) | Oct 11, 2024 |
| HP            | 829E                        | Mini pc     | [ef4f5e2642](https://linux-hardware.org/?probe=ef4f5e2642) | Oct 11, 2024 |
| Apple         | MacBook6,1                  | Notebook    | [3623e327b2](https://linux-hardware.org/?probe=3623e327b2) | Oct 11, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [64cebe30ad](https://linux-hardware.org/?probe=64cebe30ad) | Oct 10, 2024 |
| Lenovo        | Win8 STD EM DPK IPG         | All in one  | [c6f89b972d](https://linux-hardware.org/?probe=c6f89b972d) | Oct 09, 2024 |
| Lenovo        | Win8 STD EM DPK IPG         | All in one  | [425000adaf](https://linux-hardware.org/?probe=425000adaf) | Oct 08, 2024 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [bf025aaa26](https://linux-hardware.org/?probe=bf025aaa26) | Oct 08, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | Notebook    | [ecf4696b37](https://linux-hardware.org/?probe=ecf4696b37) | Oct 07, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [01cd6549a5](https://linux-hardware.org/?probe=01cd6549a5) | Oct 06, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [0f138dcac0](https://linux-hardware.org/?probe=0f138dcac0) | Oct 06, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [c8c6a6269b](https://linux-hardware.org/?probe=c8c6a6269b) | Oct 06, 2024 |
| ARCELIK       | 1M7-GNB1595B6I7             | Notebook    | [cbf522f76a](https://linux-hardware.org/?probe=cbf522f76a) | Oct 05, 2024 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [38dabad22e](https://linux-hardware.org/?probe=38dabad22e) | Oct 05, 2024 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [11ca375fb2](https://linux-hardware.org/?probe=11ca375fb2) | Oct 05, 2024 |
| Sony          | VPCEC3L1E                   | Notebook    | [748694aa38](https://linux-hardware.org/?probe=748694aa38) | Oct 05, 2024 |
| Dell          | 0P096C A00                  | Desktop     | [29a648fa32](https://linux-hardware.org/?probe=29a648fa32) | Oct 05, 2024 |
| Dell          | 0P096C A00                  | Desktop     | [5a4a3dac5c](https://linux-hardware.org/?probe=5a4a3dac5c) | Oct 05, 2024 |
| Positivo      | VJF154                      | Notebook    | [70bb906734](https://linux-hardware.org/?probe=70bb906734) | Oct 04, 2024 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [bafb1e1519](https://linux-hardware.org/?probe=bafb1e1519) | Oct 04, 2024 |
| Dell          | Latitude E6520              | Notebook    | [5af0de6a9c](https://linux-hardware.org/?probe=5af0de6a9c) | Oct 04, 2024 |
| Dell          | Precision 5530              | Notebook    | [7d736763e8](https://linux-hardware.org/?probe=7d736763e8) | Oct 04, 2024 |
| Alienware     | 17 R3                       | Notebook    | [b22f85d157](https://linux-hardware.org/?probe=b22f85d157) | Oct 03, 2024 |
| Samsung       | 900X3F                      | Notebook    | [12e6b46207](https://linux-hardware.org/?probe=12e6b46207) | Oct 03, 2024 |
| Samsung       | 900X3F                      | Notebook    | [5b7f51059a](https://linux-hardware.org/?probe=5b7f51059a) | Oct 03, 2024 |
| Intel         | JSL MRD                     | Desktop     | [6be233c711](https://linux-hardware.org/?probe=6be233c711) | Oct 02, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a3cab13a1b](https://linux-hardware.org/?probe=a3cab13a1b) | Oct 02, 2024 |
| HP            | G60                         | Notebook    | [b2cbfa9c26](https://linux-hardware.org/?probe=b2cbfa9c26) | Oct 02, 2024 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [b9f265012b](https://linux-hardware.org/?probe=b9f265012b) | Oct 01, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1046a844db](https://linux-hardware.org/?probe=1046a844db) | Sep 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [bfd414e273](https://linux-hardware.org/?probe=bfd414e273) | Sep 30, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [39053cddd2](https://linux-hardware.org/?probe=39053cddd2) | Sep 29, 2024 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [add5dd6115](https://linux-hardware.org/?probe=add5dd6115) | Sep 29, 2024 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [a0e31d8395](https://linux-hardware.org/?probe=a0e31d8395) | Sep 29, 2024 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [f6c50cc494](https://linux-hardware.org/?probe=f6c50cc494) | Sep 28, 2024 |
| Apple         | MacBookPro5,1               | Notebook    | [ea1547836b](https://linux-hardware.org/?probe=ea1547836b) | Sep 27, 2024 |
| Intel         | IPC-ADN2L                   | Desktop     | [7aaa04ef0f](https://linux-hardware.org/?probe=7aaa04ef0f) | Sep 27, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [ce465db6d8](https://linux-hardware.org/?probe=ce465db6d8) | Sep 26, 2024 |
| realme        | RMNBXXXX                    | Notebook    | [a56e71a36d](https://linux-hardware.org/?probe=a56e71a36d) | Sep 25, 2024 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [eb1144d5d0](https://linux-hardware.org/?probe=eb1144d5d0) | Sep 23, 2024 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [8fe6745261](https://linux-hardware.org/?probe=8fe6745261) | Sep 23, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [d02c3ea8d2](https://linux-hardware.org/?probe=d02c3ea8d2) | Sep 22, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [de3ad3dcb2](https://linux-hardware.org/?probe=de3ad3dcb2) | Sep 22, 2024 |
| Acer          | Aspire E5-511G              | Notebook    | [eb212c1295](https://linux-hardware.org/?probe=eb212c1295) | Sep 21, 2024 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [7259f3460a](https://linux-hardware.org/?probe=7259f3460a) | Sep 21, 2024 |
| Samsung       | 900X3J                      | Notebook    | [84b81dc973](https://linux-hardware.org/?probe=84b81dc973) | Sep 19, 2024 |
| Apple         | MacBook6,1                  | Notebook    | [754a9d1a14](https://linux-hardware.org/?probe=754a9d1a14) | Sep 19, 2024 |
| Acer          | Nitro AN515-52              | Notebook    | [0bc35e551d](https://linux-hardware.org/?probe=0bc35e551d) | Sep 18, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [e386b9f60a](https://linux-hardware.org/?probe=e386b9f60a) | Sep 18, 2024 |
| Lenovo        | ThinkPad L380 20M6S11800    | Notebook    | [22c790176f](https://linux-hardware.org/?probe=22c790176f) | Sep 18, 2024 |
| Lenovo        | G400 20235                  | Notebook    | [96ebcfea10](https://linux-hardware.org/?probe=96ebcfea10) | Sep 18, 2024 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [a44bd15d85](https://linux-hardware.org/?probe=a44bd15d85) | Sep 17, 2024 |
| Acer          | Aspire E5-511G              | Notebook    | [0b1a846a69](https://linux-hardware.org/?probe=0b1a846a69) | Sep 17, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [a2f78f9d5a](https://linux-hardware.org/?probe=a2f78f9d5a) | Sep 17, 2024 |
| HP            | Pavilion 17                 | Notebook    | [fb7884d776](https://linux-hardware.org/?probe=fb7884d776) | Sep 16, 2024 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [f73ff9c739](https://linux-hardware.org/?probe=f73ff9c739) | Sep 16, 2024 |
| HP            | Pavilion dv6700             | Notebook    | [79316bc8bf](https://linux-hardware.org/?probe=79316bc8bf) | Sep 16, 2024 |
| Acer          | Aspire 5750                 | Notebook    | [d030037b8b](https://linux-hardware.org/?probe=d030037b8b) | Sep 14, 2024 |
| Acer          | Aspire 7745G                | Notebook    | [76a55f9bb1](https://linux-hardware.org/?probe=76a55f9bb1) | Sep 14, 2024 |
| Dell          | Inspiron 3721               | Notebook    | [dd0fd36c69](https://linux-hardware.org/?probe=dd0fd36c69) | Sep 14, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7a6f092e7a](https://linux-hardware.org/?probe=7a6f092e7a) | Sep 13, 2024 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [156f5f004e](https://linux-hardware.org/?probe=156f5f004e) | Sep 13, 2024 |
| Apple         | MacBookPro11,3              | Notebook    | [ce91008479](https://linux-hardware.org/?probe=ce91008479) | Sep 13, 2024 |
| Dell          | XPS 13 9343                 | Notebook    | [ca52ff1c29](https://linux-hardware.org/?probe=ca52ff1c29) | Sep 13, 2024 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [9f8697d54c](https://linux-hardware.org/?probe=9f8697d54c) | Sep 13, 2024 |
| Alienware     | 17 R3                       | Notebook    | [d95edb94cd](https://linux-hardware.org/?probe=d95edb94cd) | Sep 13, 2024 |
| Toshiba       | Satellite L50-B             | Notebook    | [bb130f4634](https://linux-hardware.org/?probe=bb130f4634) | Sep 11, 2024 |
| ASUSTek       | ET2700I                     | Desktop     | [0faf2541ce](https://linux-hardware.org/?probe=0faf2541ce) | Sep 11, 2024 |
| Acer          | Aspire 5750                 | Notebook    | [0c7144d06b](https://linux-hardware.org/?probe=0c7144d06b) | Sep 10, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [cd6caa40b8](https://linux-hardware.org/?probe=cd6caa40b8) | Sep 10, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [62da51972f](https://linux-hardware.org/?probe=62da51972f) | Sep 10, 2024 |
| HP            | 8620                        | Mini pc     | [08d49cd98c](https://linux-hardware.org/?probe=08d49cd98c) | Sep 10, 2024 |
| Lenovo        | B590 20206                  | Notebook    | [38ef54ca0c](https://linux-hardware.org/?probe=38ef54ca0c) | Sep 09, 2024 |
| Lenovo        | B590 20206                  | Notebook    | [3e57e1486e](https://linux-hardware.org/?probe=3e57e1486e) | Sep 09, 2024 |
| Intel         | IPC-ADN2L                   | Desktop     | [274c57803d](https://linux-hardware.org/?probe=274c57803d) | Sep 09, 2024 |
| Sony          | SVF15A1B4E                  | Notebook    | [08c43f2d50](https://linux-hardware.org/?probe=08c43f2d50) | Sep 09, 2024 |
| Pegatron      | 2A94h                       | Desktop     | [5a721a5edc](https://linux-hardware.org/?probe=5a721a5edc) | Sep 08, 2024 |
| HP            | Elite x360 1040 14 inch ... | Convertible | [c5902bc488](https://linux-hardware.org/?probe=c5902bc488) | Sep 06, 2024 |
| Gigabyte      | H81M-S2H                    | Desktop     | [8c3768316c](https://linux-hardware.org/?probe=8c3768316c) | Sep 05, 2024 |
| Dell          | Inspiron 3721               | Notebook    | [8c75a1af97](https://linux-hardware.org/?probe=8c75a1af97) | Sep 05, 2024 |
| Acidanther... | Mac-63001698E7A34814 iMa... | All in one  | [fd799d8177](https://linux-hardware.org/?probe=fd799d8177) | Sep 04, 2024 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [efc36fa140](https://linux-hardware.org/?probe=efc36fa140) | Sep 03, 2024 |
| Dell          | Inspiron 3721               | Notebook    | [8a051dce97](https://linux-hardware.org/?probe=8a051dce97) | Sep 03, 2024 |
| Acer          | TravelMate 5735Z            | Notebook    | [b59bdd3310](https://linux-hardware.org/?probe=b59bdd3310) | Sep 02, 2024 |
| Lenovo        | ThinkCentre Edge71 1607R... | Desktop     | [29cdb0e2f5](https://linux-hardware.org/?probe=29cdb0e2f5) | Sep 02, 2024 |
| Dell          | Latitude 5510               | Notebook    | [634228ff35](https://linux-hardware.org/?probe=634228ff35) | Sep 02, 2024 |
| Apple         | MacBookPro9,1               | Notebook    | [41e0375932](https://linux-hardware.org/?probe=41e0375932) | Sep 02, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [c1c6557769](https://linux-hardware.org/?probe=c1c6557769) | Sep 01, 2024 |
| Apple         | MacBookPro6,2               | Notebook    | [7a30d49834](https://linux-hardware.org/?probe=7a30d49834) | Sep 01, 2024 |
| ASRock        | J5040-ITX                   | Desktop     | [fcfa738334](https://linux-hardware.org/?probe=fcfa738334) | Sep 01, 2024 |
| Lenovo        | G50-70 20351                | Notebook    | [8175aeac94](https://linux-hardware.org/?probe=8175aeac94) | Aug 31, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [60e3c48bbc](https://linux-hardware.org/?probe=60e3c48bbc) | Aug 30, 2024 |
| ASUSTek       | TP300LA                     | Notebook    | [55fb687fea](https://linux-hardware.org/?probe=55fb687fea) | Aug 30, 2024 |
| Dell          | Latitude E5420              | Notebook    | [1aa4784afb](https://linux-hardware.org/?probe=1aa4784afb) | Aug 29, 2024 |
| ASUSTek       | 1015PX                      | Notebook    | [b83d98a551](https://linux-hardware.org/?probe=b83d98a551) | Aug 29, 2024 |
| Dell          | XPS 13 9365                 | Convertible | [d28dc2d575](https://linux-hardware.org/?probe=d28dc2d575) | Aug 29, 2024 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [9f47f2b01b](https://linux-hardware.org/?probe=9f47f2b01b) | Aug 29, 2024 |
| MSI           | H77MA-G43                   | Desktop     | [73df0e9be3](https://linux-hardware.org/?probe=73df0e9be3) | Aug 28, 2024 |
| MSI           | H77MA-G43                   | Desktop     | [c3687b0959](https://linux-hardware.org/?probe=c3687b0959) | Aug 28, 2024 |
| Gigabyte      | Z790 UD                     | Desktop     | [fd328d5314](https://linux-hardware.org/?probe=fd328d5314) | Aug 28, 2024 |
| Gigabyte      | Z790 UD                     | Desktop     | [01f402c213](https://linux-hardware.org/?probe=01f402c213) | Aug 28, 2024 |
| ASUSTek       | ET2700I                     | Desktop     | [46b00a17dd](https://linux-hardware.org/?probe=46b00a17dd) | Aug 28, 2024 |
| ASUSTek       | ET2700I                     | Desktop     | [69b47ec3cd](https://linux-hardware.org/?probe=69b47ec3cd) | Aug 28, 2024 |
| ASRock        | B450M/ac R2.0               | Desktop     | [0946b4faad](https://linux-hardware.org/?probe=0946b4faad) | Aug 28, 2024 |
| Gigabyte      | G5 GD                       | Notebook    | [2840fa5a43](https://linux-hardware.org/?probe=2840fa5a43) | Aug 27, 2024 |
| HP            | 0B54h D                     | Desktop     | [3e361ce6dd](https://linux-hardware.org/?probe=3e361ce6dd) | Aug 27, 2024 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [2aa427ea2b](https://linux-hardware.org/?probe=2aa427ea2b) | Aug 27, 2024 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [a0dc16409e](https://linux-hardware.org/?probe=a0dc16409e) | Aug 26, 2024 |
| Pegatron      | 2A94h                       | Desktop     | [6ec199373b](https://linux-hardware.org/?probe=6ec199373b) | Aug 25, 2024 |
| ASRock        | B450M/ac R2.0               | Desktop     | [0026cbe5e3](https://linux-hardware.org/?probe=0026cbe5e3) | Aug 25, 2024 |
| Apple         | MacBookPro5,1               | Notebook    | [5add020da3](https://linux-hardware.org/?probe=5add020da3) | Aug 25, 2024 |
| HP            | 1495                        | Desktop     | [76595d0137](https://linux-hardware.org/?probe=76595d0137) | Aug 24, 2024 |
| HP            | 1495                        | Desktop     | [d7f96fb46e](https://linux-hardware.org/?probe=d7f96fb46e) | Aug 24, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Elementary/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Elementary 6.1   | 745       | 26.21%  |
| Elementary 7.1   | 626       | 22.03%  |
| Elementary 8     | 483       | 17%     |
| Elementary 7     | 257       | 9.04%   |
| Elementary 5.1.7 | 242       | 8.52%   |
| Elementary 6     | 233       | 8.2%    |
| Elementary 5.0   | 55        | 1.94%   |
| Elementary 5.1   | 46        | 1.62%   |
| Elementary 5.1.6 | 35        | 1.23%   |
| Elementary 5.1.4 | 33        | 1.16%   |
| Elementary 5.1.2 | 29        | 1.02%   |
| Elementary 5.1.3 | 23        | 0.81%   |
| Elementary 0.4.1 | 17        | 0.6%    |
| Elementary 5.1.5 | 11        | 0.39%   |
| Elementary 6.0   | 7         | 0.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Elementary | 2741      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-43-generic | 138       | 4.51%   |
| 6.2.0-33-generic  | 110       | 3.59%   |
| 5.15.0-58-generic | 92        | 3%      |
| 6.8.0-49-generic  | 86        | 2.81%   |
| 6.11.0-19-generic | 82        | 2.68%   |
| 6.8.0-51-generic  | 75        | 2.45%   |
| 5.11.0-40-generic | 57        | 1.86%   |
| 6.8.0-40-generic  | 56        | 1.83%   |
| 5.15.0-46-generic | 55        | 1.8%    |
| 5.13.0-28-generic | 54        | 1.76%   |
| 5.11.0-41-generic | 52        | 1.7%    |
| 5.15.0-56-generic | 46        | 1.5%    |
| 6.5.0-35-generic  | 40        | 1.31%   |
| 5.11.0-27-generic | 40        | 1.31%   |
| 6.14.0-29-generic | 39        | 1.27%   |
| 6.11.0-26-generic | 39        | 1.27%   |
| 6.5.0-41-generic  | 38        | 1.24%   |
| 5.13.0-30-generic | 38        | 1.24%   |
| 5.13.0-27-generic | 36        | 1.18%   |
| 5.13.0-39-generic | 35        | 1.14%   |
| 6.8.0-45-generic  | 33        | 1.08%   |
| 6.5.0-28-generic  | 33        | 1.08%   |
| 5.4.0-42-generic  | 32        | 1.04%   |
| 6.5.0-26-generic  | 29        | 0.95%   |
| 6.8.0-48-generic  | 28        | 0.91%   |
| 5.15.0-52-generic | 28        | 0.91%   |
| 5.13.0-40-generic | 27        | 0.88%   |
| 5.11.0-38-generic | 27        | 0.88%   |
| 6.8.0-47-generic  | 25        | 0.82%   |
| 6.2.0-26-generic  | 25        | 0.82%   |
| 5.15.0-41-generic | 25        | 0.82%   |
| 5.11.0-37-generic | 25        | 0.82%   |
| 5.0.0-37-generic  | 25        | 0.82%   |
| 5.19.0-46-generic | 24        | 0.78%   |
| 5.19.0-41-generic | 23        | 0.75%   |
| 5.15.0-48-generic | 23        | 0.75%   |
| 5.13.0-35-generic | 23        | 0.75%   |
| 6.2.0-36-generic  | 22        | 0.72%   |
| 5.19.0-35-generic | 22        | 0.72%   |
| 5.19.0-32-generic | 22        | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 391       | 13.55%  |
| 5.15.0  | 354       | 12.27%  |
| 6.8.0   | 334       | 11.57%  |
| 5.13.0  | 284       | 9.84%   |
| 6.5.0   | 252       | 8.73%   |
| 6.2.0   | 227       | 7.87%   |
| 5.4.0   | 222       | 7.69%   |
| 6.11.0  | 221       | 7.66%   |
| 5.19.0  | 136       | 4.71%   |
| 6.14.0  | 131       | 4.54%   |
| 5.3.0   | 111       | 3.85%   |
| 4.15.0  | 89        | 3.08%   |
| 5.0.0   | 32        | 1.11%   |
| 5.8.0   | 14        | 0.49%   |
| 5.14.0  | 4         | 0.14%   |
| 4.18.0  | 4         | 0.14%   |
| 4.13.0  | 4         | 0.14%   |
| 5.10.0  | 3         | 0.1%    |
| 4.4.0   | 3         | 0.1%    |
| 6.5.5   | 2         | 0.07%   |
| 5.15.5  | 2         | 0.07%   |
| 5.15.36 | 2         | 0.07%   |
| 5.15.12 | 2         | 0.07%   |
| 4.10.0  | 2         | 0.07%   |
| 6.8.8   | 1         | 0.03%   |
| 6.7.3   | 1         | 0.03%   |
| 6.7.10  | 1         | 0.03%   |
| 6.5.7   | 1         | 0.03%   |
| 6.4.5   | 1         | 0.03%   |
| 6.3.13  | 1         | 0.03%   |
| 6.2.8   | 1         | 0.03%   |
| 6.2.7   | 1         | 0.03%   |
| 6.2.2   | 1         | 0.03%   |
| 6.2.14  | 1         | 0.03%   |
| 6.16.0  | 1         | 0.03%   |
| 6.13.6  | 1         | 0.03%   |
| 6.12.6  | 1         | 0.03%   |
| 6.11.5  | 1         | 0.03%   |
| 6.1.9   | 1         | 0.03%   |
| 6.1.8   | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 391       | 13.57%  |
| 5.15    | 367       | 12.73%  |
| 6.8     | 335       | 11.62%  |
| 5.13    | 284       | 9.85%   |
| 6.5     | 255       | 8.85%   |
| 6.2     | 230       | 7.98%   |
| 5.4     | 224       | 7.77%   |
| 6.11    | 222       | 7.7%    |
| 5.19    | 140       | 4.86%   |
| 6.14    | 131       | 4.55%   |
| 5.3     | 113       | 3.92%   |
| 4.15    | 89        | 3.09%   |
| 5.0     | 33        | 1.15%   |
| 5.8     | 16        | 0.56%   |
| 5.14    | 8         | 0.28%   |
| 6.1     | 4         | 0.14%   |
| 5.16    | 4         | 0.14%   |
| 5.10    | 4         | 0.14%   |
| 4.18    | 4         | 0.14%   |
| 4.13    | 4         | 0.14%   |
| 5.17    | 3         | 0.1%    |
| 4.4     | 3         | 0.1%    |
| 6.7     | 2         | 0.07%   |
| 6.0     | 2         | 0.07%   |
| 5.5     | 2         | 0.07%   |
| 4.10    | 2         | 0.07%   |
| 6.4     | 1         | 0.03%   |
| 6.3     | 1         | 0.03%   |
| 6.16    | 1         | 0.03%   |
| 6.13    | 1         | 0.03%   |
| 6.12    | 1         | 0.03%   |
| 5.9     | 1         | 0.03%   |
| 5.7     | 1         | 0.03%   |
| 5.6     | 1         | 0.03%   |
| 5.2     | 1         | 0.03%   |
| 5.18    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2740      | 99.96%  |
| aarch64 | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pantheon      | 2626      | 95.11%  |
| Unknown       | 106       | 3.84%   |
| GNOME         | 16        | 0.58%   |
| X-Cinnamon    | 4         | 0.14%   |
| KDE5          | 3         | 0.11%   |
| XFCE          | 1         | 0.04%   |
| Unity         | 1         | 0.04%   |
| sway          | 1         | 0.04%   |
| MATE          | 1         | 0.04%   |
| GNOME Classic | 1         | 0.04%   |
| Budgie        | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2656      | 96.72%  |
| Wayland | 87        | 3.17%   |
| Unknown | 2         | 0.07%   |
| Tty     | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2302      | 83.07%  |
| LightDM | 391       | 14.11%  |
| TDM     | 69        | 2.49%   |
| GDM     | 5         | 0.18%   |
| SDDM    | 2         | 0.07%   |
| GDM3    | 2         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1132      | 40.88%  |
| de_DE   | 318       | 11.48%  |
| es_ES   | 220       | 7.95%   |
| ru_RU   | 156       | 5.63%   |
| pt_BR   | 111       | 4.01%   |
| fr_FR   | 110       | 3.97%   |
| en_GB   | 108       | 3.9%    |
| it_IT   | 96        | 3.47%   |
| Unknown | 65        | 2.35%   |
| pl_PL   | 64        | 2.31%   |
| nl_NL   | 39        | 1.41%   |
| en_CA   | 37        | 1.34%   |
| en_AU   | 35        | 1.26%   |
| tr_TR   | 25        | 0.9%    |
| pt_PT   | 23        | 0.83%   |
| hu_HU   | 22        | 0.79%   |
| sv_SE   | 19        | 0.69%   |
| de_CH   | 14        | 0.51%   |
| nb_NO   | 13        | 0.47%   |
| cs_CZ   | 13        | 0.47%   |
| zh_CN   | 11        | 0.4%    |
| en_IN   | 11        | 0.4%    |
| es_MX   | 9         | 0.33%   |
| ja_JP   | 8         | 0.29%   |
| id_ID   | 8         | 0.29%   |
| el_GR   | 8         | 0.29%   |
| uk_UA   | 7         | 0.25%   |
| fi_FI   | 7         | 0.25%   |
| da_DK   | 7         | 0.25%   |
| fr_CA   | 6         | 0.22%   |
| hr_HR   | 5         | 0.18%   |
| es_EC   | 4         | 0.14%   |
| en_ZA   | 4         | 0.14%   |
| ca_ES   | 4         | 0.14%   |
| C       | 4         | 0.14%   |
| bg_BG   | 4         | 0.14%   |
| zh_TW   | 3         | 0.11%   |
| es_AR   | 3         | 0.11%   |
| ar_EG   | 3         | 0.11%   |
| vi_VN   | 2         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1799      | 64.69%  |
| EFI  | 982       | 35.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 2605      | 94.49%  |
| Tmpfs    | 43        | 1.56%   |
| Btrfs    | 42        | 1.52%   |
| Overlay  | 29        | 1.05%   |
| Unknown  | 21        | 0.76%   |
| Xfs      | 14        | 0.51%   |
| Reiserfs | 1         | 0.04%   |
| Ext3     | 1         | 0.04%   |
| Ext2     | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2349      | 84.74%  |
| GPT     | 339       | 12.23%  |
| MBR     | 84        | 3.03%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2664      | 97.05%  |
| Yes       | 81        | 2.95%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2527      | 91.59%  |
| Yes       | 232       | 8.41%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 410       | 14.96%  |
| Apple               | 393       | 14.34%  |
| Lenovo              | 376       | 13.72%  |
| ASUSTek Computer    | 324       | 11.82%  |
| Dell                | 294       | 10.73%  |
| Acer                | 149       | 5.44%   |
| Gigabyte Technology | 112       | 4.09%   |
| MSI                 | 99        | 3.61%   |
| ASRock              | 54        | 1.97%   |
| Toshiba             | 44        | 1.61%   |
| HUAWEI              | 40        | 1.46%   |
| Intel               | 38        | 1.39%   |
| Samsung Electronics | 36        | 1.31%   |
| Sony                | 32        | 1.17%   |
| Unknown             | 23        | 0.84%   |
| Microsoft           | 20        | 0.73%   |
| Google              | 18        | 0.66%   |
| Fujitsu             | 18        | 0.66%   |
| Biostar             | 13        | 0.47%   |
| Medion              | 12        | 0.44%   |
| Alienware           | 10        | 0.36%   |
| Pegatron            | 9         | 0.33%   |
| Packard Bell        | 9         | 0.33%   |
| Chuwi               | 9         | 0.33%   |
| Positivo            | 7         | 0.26%   |
| Foxconn             | 7         | 0.26%   |
| Timi                | 6         | 0.22%   |
| Star Labs           | 6         | 0.22%   |
| Notebook            | 6         | 0.22%   |
| LG Electronics      | 6         | 0.22%   |
| ECS                 | 6         | 0.22%   |
| HONOR               | 5         | 0.18%   |
| eMachines           | 5         | 0.18%   |
| AZW                 | 5         | 0.18%   |
| AMI                 | 5         | 0.18%   |
| TUXEDO              | 4         | 0.15%   |
| Panasonic           | 4         | 0.15%   |
| Compaq              | 4         | 0.15%   |
| Clevo               | 4         | 0.15%   |
| Wortmann AG         | 3         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Apple MacBookPro8,1   | 29        | 1.06%   |
| Unknown               | 29        | 1.06%   |
| Apple MacBookPro9,2   | 25        | 0.91%   |
| Apple MacBookAir7,2   | 25        | 0.91%   |
| ASUS All Series       | 13        | 0.47%   |
| Apple iMac7,1         | 13        | 0.47%   |
| Apple iMac8,1         | 11        | 0.4%    |
| Apple iMac10,1        | 11        | 0.4%    |
| HP Notebook           | 10        | 0.36%   |
| Apple MacBookPro7,1   | 10        | 0.36%   |
| Apple MacBookAir6,2   | 10        | 0.36%   |
| Apple MacBook5,1      | 10        | 0.36%   |
| Apple MacBookPro8,2   | 9         | 0.33%   |
| Apple MacBookPro6,2   | 9         | 0.33%   |
| Apple MacBookPro5,5   | 9         | 0.33%   |
| Apple MacBookPro9,1   | 8         | 0.29%   |
| Apple MacBookPro11,2  | 8         | 0.29%   |
| Apple iMac9,1         | 8         | 0.29%   |
| Apple iMac12,1        | 8         | 0.29%   |
| Apple iMac11,3        | 8         | 0.29%   |
| HP Pavilion g6        | 7         | 0.26%   |
| HP Pavilion dv6       | 7         | 0.26%   |
| HP Pavilion 17        | 7         | 0.26%   |
| Dell Inspiron 15-3567 | 7         | 0.26%   |
| Apple Macmini7,1      | 7         | 0.26%   |
| Apple Macmini6,1      | 7         | 0.26%   |
| Apple MacBookPro11,1  | 7         | 0.26%   |
| Apple MacBookPro10,1  | 7         | 0.26%   |
| Apple iMac14,1        | 7         | 0.26%   |
| HP Pavilion dv7       | 6         | 0.22%   |
| ASUS PRIME A320M-K    | 6         | 0.22%   |
| Apple Macmini5,1      | 6         | 0.22%   |
| Apple MacBookAir4,2   | 6         | 0.22%   |
| Apple MacBookAir3,1   | 6         | 0.22%   |
| Apple MacBook4,1      | 6         | 0.22%   |
| Lenovo G50-45 80E3    | 5         | 0.18%   |
| HUAWEI NBLB-WAX9N     | 5         | 0.18%   |
| HUAWEI MACHD-WXX9     | 5         | 0.18%   |
| HP Laptop 15-bw0xx    | 5         | 0.18%   |
| HP EliteBook 840 G3   | 5         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 148       | 5.4%    |
| Lenovo IdeaPad     | 106       | 3.87%   |
| Acer Aspire        | 103       | 3.76%   |
| Dell Latitude      | 88        | 3.21%   |
| HP Pavilion        | 82        | 2.99%   |
| Dell Inspiron      | 76        | 2.77%   |
| HP ProBook         | 58        | 2.12%   |
| HP Laptop          | 50        | 1.82%   |
| HP EliteBook       | 49        | 1.79%   |
| Apple MacBookPro8  | 43        | 1.57%   |
| ASUS PRIME         | 40        | 1.46%   |
| Dell OptiPlex      | 37        | 1.35%   |
| Toshiba Satellite  | 34        | 1.24%   |
| ASUS VivoBook      | 33        | 1.2%    |
| Apple MacBookPro9  | 33        | 1.2%    |
| Dell XPS           | 31        | 1.13%   |
| Unknown            | 29        | 1.06%   |
| ASUS ROG           | 27        | 0.99%   |
| Apple MacBookAir7  | 27        | 0.99%   |
| Apple MacBookPro11 | 26        | 0.95%   |
| Lenovo ThinkCentre | 23        | 0.84%   |
| HP Compaq          | 22        | 0.8%    |
| Dell Precision     | 22        | 0.8%    |
| ASUS Zenbook       | 22        | 0.8%    |
| HP ENVY            | 21        | 0.77%   |
| Microsoft Surface  | 20        | 0.73%   |
| Apple MacBookPro5  | 20        | 0.73%   |
| Dell Vostro        | 19        | 0.69%   |
| ASUS TUF           | 17        | 0.62%   |
| Acer Swift         | 17        | 0.62%   |
| Apple MacBookAir6  | 14        | 0.51%   |
| Lenovo Yoga        | 13        | 0.47%   |
| ASUS All           | 13        | 0.47%   |
| Apple iMac7        | 13        | 0.47%   |
| Apple iMac14       | 13        | 0.47%   |
| Apple iMac12       | 13        | 0.47%   |
| Apple iMac11       | 13        | 0.47%   |
| Fujitsu LIFEBOOK   | 12        | 0.44%   |
| Apple MacBook5     | 12        | 0.44%   |
| HP ProDesk         | 11        | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 276       | 10.07%  |
| 2018    | 225       | 8.21%   |
| 2011    | 215       | 7.84%   |
| 2013    | 212       | 7.73%   |
| 2020    | 200       | 7.3%    |
| 2019    | 186       | 6.79%   |
| 2010    | 178       | 6.49%   |
| 2015    | 168       | 6.13%   |
| 2021    | 160       | 5.84%   |
| 2014    | 157       | 5.73%   |
| 2017    | 156       | 5.69%   |
| 2016    | 151       | 5.51%   |
| 2009    | 128       | 4.67%   |
| 2008    | 105       | 3.83%   |
| 2022    | 80        | 2.92%   |
| 2023    | 50        | 1.82%   |
| 2007    | 32        | 1.17%   |
| 2006    | 31        | 1.13%   |
| 2024    | 21        | 0.77%   |
| 2025    | 7         | 0.26%   |
| Unknown | 2         | 0.07%   |
| 2005    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1743      | 63.59%  |
| Desktop        | 684       | 24.95%  |
| All in one     | 131       | 4.78%   |
| Mini pc        | 71        | 2.59%   |
| Convertible    | 64        | 2.33%   |
| Tablet         | 39        | 1.42%   |
| Server         | 8         | 0.29%   |
| System on chip | 1         | 0.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2573      | 93.46%  |
| Enabled  | 180       | 6.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2716      | 99.09%  |
| Yes  | 25        | 0.91%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 824       | 29.78%  |
| 16.01-24.0  | 536       | 19.37%  |
| 3.01-4.0    | 528       | 19.08%  |
| 8.01-16.0   | 476       | 17.2%   |
| 32.01-64.0  | 198       | 7.16%   |
| 1.01-2.0    | 78        | 2.82%   |
| 24.01-32.0  | 49        | 1.77%   |
| 64.01-256.0 | 40        | 1.45%   |
| 2.01-3.0    | 36        | 1.3%    |
| 0.51-1.0    | 2         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 996       | 33.4%   |
| 1.01-2.0   | 964       | 32.33%  |
| 3.01-4.0   | 491       | 16.47%  |
| 4.01-8.0   | 385       | 12.91%  |
| 0.51-1.0   | 71        | 2.38%   |
| 8.01-16.0  | 70        | 2.35%   |
| 16.01-24.0 | 3         | 0.1%    |
| 32.01-64.0 | 1         | 0.03%   |
| 24.01-32.0 | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1849      | 66.3%   |
| 2       | 681       | 24.42%  |
| 3       | 135       | 4.84%   |
| 4       | 56        | 2.01%   |
| 5       | 31        | 1.11%   |
| 0       | 14        | 0.5%    |
| 6       | 13        | 0.47%   |
| 7       | 6         | 0.22%   |
| 9       | 2         | 0.07%   |
| 8       | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1750      | 63.34%  |
| Yes       | 1013      | 36.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2255      | 82.24%  |
| No        | 487       | 17.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2368      | 86.02%  |
| No        | 385       | 13.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2037      | 73.86%  |
| No        | 721       | 26.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 425       | 15.47%  |
| Germany      | 320       | 11.64%  |
| Brazil       | 156       | 5.68%   |
| Russia       | 151       | 5.49%   |
| UK           | 115       | 4.18%   |
| Italy        | 111       | 4.04%   |
| Spain        | 104       | 3.78%   |
| France       | 92        | 3.35%   |
| Canada       | 84        | 3.06%   |
| India        | 81        | 2.95%   |
| Poland       | 72        | 2.62%   |
| Mexico       | 68        | 2.47%   |
| Australia    | 60        | 2.18%   |
| Netherlands  | 59        | 2.15%   |
| Indonesia    | 58        | 2.11%   |
| Argentina    | 41        | 1.49%   |
| Turkey       | 39        | 1.42%   |
| Austria      | 37        | 1.35%   |
| Sweden       | 31        | 1.13%   |
| Belgium      | 31        | 1.13%   |
| Switzerland  | 30        | 1.09%   |
| Portugal     | 30        | 1.09%   |
| Hungary      | 26        | 0.95%   |
| Chile        | 23        | 0.84%   |
| Ukraine      | 21        | 0.76%   |
| Czechia      | 21        | 0.76%   |
| Romania      | 19        | 0.69%   |
| Norway       | 19        | 0.69%   |
| Greece       | 19        | 0.69%   |
| Colombia     | 19        | 0.69%   |
| Finland      | 18        | 0.66%   |
| South Africa | 17        | 0.62%   |
| Malaysia     | 16        | 0.58%   |
| Ireland      | 14        | 0.51%   |
| China        | 14        | 0.51%   |
| Bulgaria     | 13        | 0.47%   |
| New Zealand  | 12        | 0.44%   |
| Japan        | 12        | 0.44%   |
| Denmark      | 12        | 0.44%   |
| Vietnam      | 10        | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 44        | 1.53%   |
| Berlin            | 32        | 1.11%   |
| Warsaw            | 22        | 0.76%   |
| Madrid            | 22        | 0.76%   |
| Munich            | 20        | 0.69%   |
| St Petersburg     | 19        | 0.66%   |
| Vienna            | 18        | 0.62%   |
| Milan             | 18        | 0.62%   |
| Istanbul          | 18        | 0.62%   |
| Sao Paulo         | 17        | 0.59%   |
| Hamburg           | 17        | 0.59%   |
| Sydney            | 16        | 0.56%   |
| Melbourne         | 15        | 0.52%   |
| Paris             | 13        | 0.45%   |
| Los Angeles       | 13        | 0.45%   |
| Santiago          | 12        | 0.42%   |
| Rome              | 12        | 0.42%   |
| Rio de Janeiro    | 12        | 0.42%   |
| Jakarta           | 12        | 0.42%   |
| Fortaleza         | 11        | 0.38%   |
| Budapest          | 11        | 0.38%   |
| Perth             | 10        | 0.35%   |
| Delhi             | 10        | 0.35%   |
| Stuttgart         | 9         | 0.31%   |
| Novosibirsk       | 9         | 0.31%   |
| Montreal          | 9         | 0.31%   |
| Mexico City       | 9         | 0.31%   |
| Brisbane          | 9         | 0.31%   |
| Krakow            | 8         | 0.28%   |
| Dublin            | 8         | 0.28%   |
| Córdoba          | 8         | 0.28%   |
| Athens            | 8         | 0.28%   |
| Valencia          | 7         | 0.24%   |
| Toronto           | 7         | 0.24%   |
| The Hague         | 7         | 0.24%   |
| Surabaya          | 7         | 0.24%   |
| San José         | 7         | 0.24%   |
| Prague            | 7         | 0.24%   |
| Nuremberg         | 7         | 0.24%   |
| Frankfurt am Main | 7         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 504       | 691    | 13.49%  |
| WDC                         | 425       | 566    | 11.37%  |
| Seagate                     | 399       | 519    | 10.68%  |
| Sandisk                     | 243       | 286    | 6.5%    |
| Toshiba                     | 241       | 298    | 6.45%   |
| Kingston                    | 214       | 276    | 5.73%   |
| Unknown                     | 164       | 210    | 4.39%   |
| Crucial                     | 153       | 187    | 4.09%   |
| Apple                       | 145       | 173    | 3.88%   |
| Hitachi                     | 104       | 115    | 2.78%   |
| SK hynix                    | 82        | 97     | 2.19%   |
| Intel                       | 79        | 106    | 2.11%   |
| HGST                        | 75        | 93     | 2.01%   |
| A-DATA Technology           | 56        | 63     | 1.5%    |
| China                       | 52        | 70     | 1.39%   |
| Micron Technology           | 48        | 52     | 1.28%   |
| KIOXIA                      | 33        | 48     | 0.88%   |
| PNY                         | 30        | 40     | 0.8%    |
| Silicon Motion              | 29        | 35     | 0.78%   |
| Micron/Crucial Technology   | 28        | 36     | 0.75%   |
| Unknown                     | 24        | 27     | 0.64%   |
| Phison                      | 20        | 22     | 0.54%   |
| JMicron Technology          | 20        | 20     | 0.54%   |
| Phison Electronics          | 19        | 19     | 0.51%   |
| LITEON                      | 19        | 19     | 0.51%   |
| Intenso                     | 19        | 22     | 0.51%   |
| Transcend                   | 18        | 21     | 0.48%   |
| SPCC                        | 18        | 18     | 0.48%   |
| Patriot                     | 18        | 21     | 0.48%   |
| Fujitsu                     | 18        | 21     | 0.48%   |
| MAXIO Technology (Hangzhou) | 15        | 18     | 0.4%    |
| OCZ                         | 14        | 22     | 0.37%   |
| Kingston Technology Company | 14        | 14     | 0.37%   |
| Hewlett-Packard             | 13        | 18     | 0.35%   |
| Team                        | 12        | 15     | 0.32%   |
| Realtek Semiconductor       | 11        | 14     | 0.29%   |
| Apacer                      | 11        | 15     | 0.29%   |
| Netac                       | 10        | 11     | 0.27%   |
| Gigabyte Technology         | 10        | 10     | 0.27%   |
| Corsair                     | 10        | 11     | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 61        | 1.53%   |
| Unknown MMC Card  64GB                                | 37        | 0.93%   |
| Toshiba MQ01ABD100 1TB                                | 34        | 0.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 34        | 0.85%   |
| Unknown MMC Card  32GB                                | 32        | 0.8%    |
| Samsung SSD 850 EVO 250GB                             | 28        | 0.7%    |
| Samsung SSD 860 EVO 500GB                             | 26        | 0.65%   |
| Kingston SA400S37120G 120GB SSD                       | 26        | 0.65%   |
| Seagate ST1000LM035-1RK172 1TB                        | 25        | 0.63%   |
| Crucial CT240BX500SSD1 240GB                          | 25        | 0.63%   |
| Unknown MMC Card  128GB                               | 24        | 0.6%    |
| Seagate ST500LT012-1DG142 500GB                       | 24        | 0.6%    |
| Unknown                                               | 24        | 0.6%    |
| Samsung NVMe SSD Drive 512GB                          | 22        | 0.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 21        | 0.53%   |
| Samsung NVMe SSD Drive 256GB                          | 21        | 0.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 20        | 0.5%    |
| Samsung SSD 850 EVO 500GB                             | 20        | 0.5%    |
| HGST HTS721010A9E630 1TB                              | 20        | 0.5%    |
| Crucial CT500MX500SSD1 500GB                          | 20        | 0.5%    |
| Toshiba MQ01ABF050 500GB                              | 19        | 0.48%   |
| Seagate ST500DM002-1BD142 500GB                       | 19        | 0.48%   |
| Toshiba MQ04ABF100 1TB                                | 18        | 0.45%   |
| Samsung SSD 860 EVO 250GB                             | 18        | 0.45%   |
| Kingston SA400S37480G 480GB SSD                       | 18        | 0.45%   |
| Apple SSD SM0128G 121GB                               | 17        | 0.43%   |
| Unknown MMC Card  16GB                                | 16        | 0.4%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 16        | 0.4%    |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                 | 16        | 0.4%    |
| SanDisk NVMe SSD Drive 512GB                          | 16        | 0.4%    |
| Samsung NVMe SSD Drive 500GB                          | 16        | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB                              | 15        | 0.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 15        | 0.38%   |
| Kingston SV300S37A120G 120GB SSD                      | 15        | 0.38%   |
| Samsung SSD 840 EVO 250GB                             | 14        | 0.35%   |
| HGST HTS545050A7E680 500GB                            | 14        | 0.35%   |
| Apple SSD SM0256F 256GB                               | 14        | 0.35%   |
| Samsung SSD 860 EVO 1TB                               | 13        | 0.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 13        | 0.33%   |
| Apple HDD HTS541010A9E662 1TB                         | 13        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 390       | 502    | 31.25%  |
| WDC                 | 333       | 438    | 26.68%  |
| Toshiba             | 190       | 234    | 15.22%  |
| Hitachi             | 104       | 115    | 8.33%   |
| HGST                | 75        | 93     | 6.01%   |
| Samsung Electronics | 42        | 48     | 3.37%   |
| Apple               | 42        | 47     | 3.37%   |
| Fujitsu             | 18        | 21     | 1.44%   |
| Unknown             | 11        | 12     | 0.88%   |
| JMicron Technology  | 8         | 8      | 0.64%   |
| Maxtor              | 6         | 6      | 0.48%   |
| TO Exter            | 4         | 4      | 0.32%   |
| Hewlett-Packard     | 4         | 7      | 0.32%   |
| ASMT                | 3         | 3      | 0.24%   |
| SSK                 | 2         | 3      | 0.16%   |
| External            | 2         | 2      | 0.16%   |
| Unknown             | 2         | 2      | 0.16%   |
| WALRAM              | 1         | 1      | 0.08%   |
| USB                 | 1         | 1      | 0.08%   |
| T-FORCE             | 1         | 1      | 0.08%   |
| StoreJet            | 1         | 1      | 0.08%   |
| Shenzhen            | 1         | 1      | 0.08%   |
| PRO Z               | 1         | 2      | 0.08%   |
| NETAPP              | 1         | 1      | 0.08%   |
| JetFlash            | 1         | 2      | 0.08%   |
| Generic-            | 1         | 1      | 0.08%   |
| FC-1307             | 1         | 1      | 0.08%   |
| Ext Hard            | 1         | 1      | 0.08%   |
| ExcelStor           | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 268       | 355    | 18.03%  |
| Kingston            | 190       | 232    | 12.79%  |
| Crucial             | 150       | 183    | 10.09%  |
| SanDisk             | 134       | 159    | 9.02%   |
| Apple               | 102       | 116    | 6.86%   |
| WDC                 | 77        | 94     | 5.18%   |
| China               | 51        | 69     | 3.43%   |
| A-DATA Technology   | 49        | 55     | 3.3%    |
| Intel               | 33        | 41     | 2.22%   |
| PNY                 | 30        | 40     | 2.02%   |
| Micron Technology   | 21        | 23     | 1.41%   |
| Toshiba             | 20        | 24     | 1.35%   |
| Transcend           | 18        | 21     | 1.21%   |
| SPCC                | 18        | 18     | 1.21%   |
| Patriot             | 18        | 21     | 1.21%   |
| LITEON              | 18        | 18     | 1.21%   |
| Intenso             | 18        | 21     | 1.21%   |
| SK hynix            | 17        | 17     | 1.14%   |
| OCZ                 | 14        | 22     | 0.94%   |
| Team                | 12        | 15     | 0.81%   |
| Apacer              | 11        | 15     | 0.74%   |
| Unknown             | 11        | 11     | 0.74%   |
| Netac               | 9         | 10     | 0.61%   |
| Hewlett-Packard     | 9         | 11     | 0.61%   |
| GOODRAM             | 9         | 13     | 0.61%   |
| Corsair             | 9         | 10     | 0.61%   |
| Lexar               | 8         | 9      | 0.54%   |
| KingSpec            | 8         | 12     | 0.54%   |
| NGFF                | 7         | 8      | 0.47%   |
| KingDian            | 7         | 10     | 0.47%   |
| LITEONIT            | 6         | 6      | 0.4%    |
| Gigabyte Technology | 6         | 6      | 0.4%    |
| SABRENT             | 5         | 5      | 0.34%   |
| Plextor             | 5         | 7      | 0.34%   |
| OWC                 | 5         | 5      | 0.34%   |
| HUSKY               | 5         | 10     | 0.34%   |
| Verbatim            | 4         | 4      | 0.27%   |
| Seagate             | 4         | 6      | 0.27%   |
| Emtec               | 4         | 6      | 0.27%   |
| Leven               | 3         | 3      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1339      | 1817   | 38.88%  |
| HDD     | 1107      | 1559   | 32.14%  |
| NVMe    | 751       | 1010   | 21.81%  |
| MMC     | 145       | 177    | 4.21%   |
| Unknown | 102       | 138    | 2.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2114      | 3332   | 67.09%  |
| NVMe | 747       | 1003   | 23.71%  |
| SAS  | 145       | 189    | 4.6%    |
| MMC  | 145       | 177    | 4.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1640      | 2307   | 67.13%  |
| 0.51-1.0   | 610       | 809    | 24.97%  |
| 1.01-2.0   | 125       | 163    | 5.12%   |
| 3.01-4.0   | 27        | 30     | 1.11%   |
| 2.01-3.0   | 26        | 46     | 1.06%   |
| 4.01-10.0  | 14        | 20     | 0.57%   |
| 10.01-20.0 | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1100      | 39.05%  |
| 251-500        | 765       | 27.16%  |
| 501-1000       | 419       | 14.87%  |
| 51-100         | 187       | 6.64%   |
| 1001-2000      | 134       | 4.76%   |
| 21-50          | 95        | 3.37%   |
| More than 3000 | 44        | 1.56%   |
| 2001-3000      | 37        | 1.31%   |
| 1-20           | 30        | 1.06%   |
| Unknown        | 6         | 0.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1310      | 44.44%  |
| 21-50          | 776       | 26.32%  |
| 51-100         | 310       | 10.52%  |
| 101-250        | 273       | 9.26%   |
| 251-500        | 125       | 4.24%   |
| 501-1000       | 83        | 2.82%   |
| 1001-2000      | 43        | 1.46%   |
| 2001-3000      | 13        | 0.44%   |
| More than 3000 | 9         | 0.31%   |
| Unknown        | 6         | 0.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 1         | 1      | 1.49%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 1      | 1.49%   |
| WDC WD5000BPKT-75PK4T0 500GB        | 1         | 1      | 1.49%   |
| WDC WD5000AAKX-22ERMA0 500GB        | 1         | 1      | 1.49%   |
| WDC WD5000AAKX-221CA1 500GB         | 1         | 1      | 1.49%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 1         | 1      | 1.49%   |
| WDC WD5000AAKS-00UU3A0 500GB        | 1         | 1      | 1.49%   |
| WDC WD3200AAJS-56B4A0 320GB         | 1         | 1      | 1.49%   |
| WDC WD3000HLFS-01G6U0 304GB         | 1         | 1      | 1.49%   |
| WDC WD2002FFSX-68PF8N0 2TB          | 1         | 1      | 1.49%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 1.49%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 1      | 1.49%   |
| WDC WD10EZEX-00KUWA0 1TB            | 1         | 1      | 1.49%   |
| WDC WD1003FZEX-00MK2A0 1TB          | 1         | 1      | 1.49%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 1.49%   |
| Toshiba MK3259GSXP 320GB            | 1         | 1      | 1.49%   |
| Toshiba KBG30ZPZ128G 128GB          | 1         | 1      | 1.49%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 1.49%   |
| Seagate ST500LM030-2E717D 500GB     | 1         | 1      | 1.49%   |
| Seagate ST500DM002-1BD142 500GB     | 1         | 1      | 1.49%   |
| Seagate ST3500414CS 500GB           | 1         | 2      | 1.49%   |
| Seagate ST3500312CS 500GB           | 1         | 1      | 1.49%   |
| Seagate ST3320613AS 320GB           | 1         | 1      | 1.49%   |
| Seagate ST3250820AS 250GB           | 1         | 1      | 1.49%   |
| Seagate ST3250312AS 250GB           | 1         | 1      | 1.49%   |
| Seagate ST320LT020-9YG142 320GB     | 1         | 1      | 1.49%   |
| Seagate ST3160813AS 160GB           | 1         | 1      | 1.49%   |
| Seagate ST3160318AS 160GB           | 1         | 1      | 1.49%   |
| Seagate ST2000DM006-2DM164 2TB      | 1         | 1      | 1.49%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB | 1         | 1      | 1.49%   |
| Seagate ST1000LM035-1RK172 1TB      | 1         | 1      | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 1.49%   |
| SanDisk SSD PLUS 240GB              | 1         | 1      | 1.49%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD | 1         | 1      | 1.49%   |
| SanDisk SD7SB3Q256G1002 256GB SSD   | 1         | 1      | 1.49%   |
| Samsung Electronics HM320II 320GB   | 1         | 1      | 1.49%   |
| Samsung Electronics HD322GJ 320GB   | 1         | 1      | 1.49%   |
| Samsung Electronics HD204UI 2TB     | 1         | 1      | 1.49%   |
| Samsung Electronics HD160JJ 160GB   | 1         | 1      | 1.49%   |
| Samsung Electronics HD103UJ 1TB     | 1         | 1      | 1.49%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 16     | 22.39%  |
| WDC                 | 14        | 14     | 20.9%   |
| Samsung Electronics | 5         | 5      | 7.46%   |
| Hitachi             | 5         | 5      | 7.46%   |
| HGST                | 5         | 5      | 7.46%   |
| Kingston            | 4         | 4      | 5.97%   |
| Toshiba             | 3         | 3      | 4.48%   |
| SanDisk             | 3         | 3      | 4.48%   |
| Crucial             | 3         | 3      | 4.48%   |
| Apple               | 3         | 3      | 4.48%   |
| OCZ                 | 1         | 2      | 1.49%   |
| LS                  | 1         | 1      | 1.49%   |
| Intel               | 1         | 1      | 1.49%   |
| Fujitsu             | 1         | 2      | 1.49%   |
| China               | 1         | 1      | 1.49%   |
| BIWIN               | 1         | 1      | 1.49%   |
| A-DATA Technology   | 1         | 1      | 1.49%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 16     | 31.91%  |
| WDC                 | 12        | 12     | 25.53%  |
| Samsung Electronics | 5         | 5      | 10.64%  |
| Hitachi             | 5         | 5      | 10.64%  |
| HGST                | 5         | 5      | 10.64%  |
| Toshiba             | 2         | 2      | 4.26%   |
| Apple               | 2         | 2      | 4.26%   |
| Fujitsu             | 1         | 2      | 2.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 43        | 49     | 68.25%  |
| SSD  | 18        | 19     | 28.57%  |
| NVMe | 2         | 2      | 3.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10SPZX-75Z10T1 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2451      | 4165   | 86.73%  |
| Works    | 312       | 465    | 11.04%  |
| Malfunc  | 62        | 70     | 2.19%   |
| Failed   | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1916      | 58.45%  |
| AMD                              | 363       | 11.07%  |
| Samsung Electronics              | 280       | 8.54%   |
| SanDisk                          | 132       | 4.03%   |
| Nvidia                           | 95        | 2.9%    |
| SK hynix                         | 63        | 1.92%   |
| Phison Electronics               | 42        | 1.28%   |
| Kingston Technology Company      | 40        | 1.22%   |
| Toshiba America Info Systems     | 37        | 1.13%   |
| KIOXIA                           | 32        | 0.98%   |
| Micron/Crucial Technology        | 31        | 0.95%   |
| Marvell Technology Group         | 31        | 0.95%   |
| Silicon Motion                   | 30        | 0.92%   |
| Micron Technology                | 27        | 0.82%   |
| ASMedia Technology               | 27        | 0.82%   |
| JMicron Technology               | 17        | 0.52%   |
| ADATA Technology                 | 17        | 0.52%   |
| MAXIO Technology (Hangzhou)      | 16        | 0.49%   |
| Realtek Semiconductor            | 13        | 0.4%    |
| Union Memory (Shenzhen)          | 10        | 0.31%   |
| Shenzhen Longsys Electronics     | 9         | 0.27%   |
| Solid State Storage Technology   | 6         | 0.18%   |
| Lite-On Technology               | 6         | 0.18%   |
| Yangtze Memory Technologies      | 5         | 0.15%   |
| LSI Logic / Symbios Logic        | 5         | 0.15%   |
| VIA Technologies                 | 4         | 0.12%   |
| Apple                            | 4         | 0.12%   |
| Seagate Technology               | 3         | 0.09%   |
| INNOGRIT                         | 3         | 0.09%   |
| Broadcom / LSI                   | 3         | 0.09%   |
| Biwin Storage Technology         | 3         | 0.09%   |
| Silicon Image                    | 2         | 0.06%   |
| Hewlett-Packard                  | 2         | 0.06%   |
| Solidigm                         | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| Shenzhen Techwinsemi Technology  | 1         | 0.03%   |
| Hosin Global Electronics         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 264       | 7.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 196       | 5.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 177       | 4.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 140       | 3.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 111       | 3.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 95        | 2.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 87        | 2.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 80        | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 67        | 1.84%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 63        | 1.73%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 61        | 1.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 59        | 1.62%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 55        | 1.51%   |
| Nvidia MCP79 AHCI Controller                                                            | 54        | 1.48%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 48        | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 48        | 1.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 48        | 1.32%   |
| Intel SATA Controller [RAID mode]                                                       | 47        | 1.29%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 47        | 1.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 44        | 1.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 43        | 1.18%   |
| AMD 400 Series Chipset SATA Controller                                                  | 42        | 1.15%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 41        | 1.13%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 40        | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 37        | 1.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 36        | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 34        | 0.93%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                              | 33        | 0.91%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 30        | 0.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 29        | 0.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 28        | 0.77%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 27        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 27        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 27        | 0.74%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 26        | 0.71%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 26        | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 25        | 0.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 25        | 0.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 25        | 0.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 23        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2084      | 62.7%   |
| NVMe | 746       | 22.44%  |
| IDE  | 262       | 7.88%   |
| RAID | 226       | 6.8%    |
| SAS  | 3         | 0.09%   |
| SCSI | 3         | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2255      | 82.27%  |
| AMD          | 484       | 17.66%  |
| CentaurHauls | 1         | 0.04%   |
| ARM          | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3210M CPU @ 2.50GHz             | 46        | 1.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 36        | 1.31%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 33        | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 27        | 0.98%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 26        | 0.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 26        | 0.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 25        | 0.91%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 23        | 0.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 20        | 0.73%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 20        | 0.73%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 19        | 0.69%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 19        | 0.69%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 19        | 0.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 17        | 0.62%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 17        | 0.62%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 16        | 0.58%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 16        | 0.58%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 16        | 0.58%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 16        | 0.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 15        | 0.55%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 15        | 0.55%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 15        | 0.55%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 14        | 0.51%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 14        | 0.51%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 14        | 0.51%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 13        | 0.47%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 13        | 0.47%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 13        | 0.47%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 13        | 0.47%   |
| AMD Ryzen 5 3600 6-Core Processor             | 13        | 0.47%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 0.44%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 12        | 0.44%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 12        | 0.44%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 12        | 0.44%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 11        | 0.4%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 11        | 0.4%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 11        | 0.4%    |
| Intel Core i5-2435M CPU @ 2.40GHz             | 11        | 0.4%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 11        | 0.4%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 11        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 732       | 26.68%  |
| Intel Core i7           | 509       | 18.55%  |
| Intel Core i3           | 246       | 8.97%   |
| Other                   | 182       | 6.63%   |
| Intel Core 2 Duo        | 178       | 6.49%   |
| Intel Celeron           | 149       | 5.43%   |
| AMD Ryzen 5             | 131       | 4.77%   |
| AMD Ryzen 7             | 83        | 3.02%   |
| Intel Pentium           | 62        | 2.26%   |
| Intel Xeon              | 56        | 2.04%   |
| Intel Pentium Dual-Core | 32        | 1.17%   |
| AMD Ryzen 3             | 31        | 1.13%   |
| Intel Atom              | 29        | 1.06%   |
| AMD A8                  | 25        | 0.91%   |
| AMD Ryzen 9             | 22        | 0.8%    |
| AMD FX                  | 21        | 0.77%   |
| AMD A6                  | 20        | 0.73%   |
| AMD A4                  | 20        | 0.73%   |
| Intel Pentium Silver    | 19        | 0.69%   |
| Intel Core 2 Quad       | 16        | 0.58%   |
| AMD A10                 | 16        | 0.58%   |
| Intel Core i9           | 12        | 0.44%   |
| AMD Phenom II X4        | 12        | 0.44%   |
| Intel Core 2            | 9         | 0.33%   |
| Intel Pentium Dual      | 8         | 0.29%   |
| Intel Core m3           | 8         | 0.29%   |
| AMD Ryzen 5 PRO         | 8         | 0.29%   |
| AMD E1                  | 8         | 0.29%   |
| AMD Athlon              | 8         | 0.29%   |
| AMD A12                 | 8         | 0.29%   |
| Intel Genuine           | 5         | 0.18%   |
| Intel Celeron Dual-Core | 5         | 0.18%   |
| AMD Ryzen 7 PRO         | 5         | 0.18%   |
| AMD E                   | 5         | 0.18%   |
| Intel Core m5           | 4         | 0.15%   |
| AMD E2                  | 4         | 0.15%   |
| AMD Athlon II X4        | 4         | 0.15%   |
| AMD Athlon II X2        | 4         | 0.15%   |
| Intel Core M            | 3         | 0.11%   |
| AMD V140                | 3         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1338      | 48.73%  |
| 4      | 967       | 35.21%  |
| 6      | 185       | 6.74%   |
| 8      | 145       | 5.28%   |
| 12     | 31        | 1.13%   |
| 1      | 28        | 1.02%   |
| 10     | 20        | 0.73%   |
| 16     | 11        | 0.4%    |
| 3      | 9         | 0.33%   |
| 14     | 6         | 0.22%   |
| 5      | 2         | 0.07%   |
| 28     | 1         | 0.04%   |
| 24     | 1         | 0.04%   |
| 20     | 1         | 0.04%   |
| 18     | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 2726      | 99.45%  |
| 2      | 15        | 0.55%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1852      | 67.42%  |
| 1      | 895       | 32.58%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2730      | 99.56%  |
| Unknown        | 11        | 0.4%    |
| 64-bit         | 1         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1418      | 50.72%  |
| 0x206a7    | 142       | 5.08%   |
| 0x306a9    | 106       | 3.79%   |
| 0x306c3    | 71        | 2.54%   |
| 0x1067a    | 64        | 2.29%   |
| 0x40651    | 52        | 1.86%   |
| 0x806e9    | 44        | 1.57%   |
| 0x806c1    | 44        | 1.57%   |
| 0x406e3    | 43        | 1.54%   |
| 0x806ea    | 40        | 1.43%   |
| 0x806ec    | 39        | 1.39%   |
| 0x306d4    | 34        | 1.22%   |
| 0x20655    | 31        | 1.11%   |
| 0x906ea    | 28        | 1%      |
| 0x906e9    | 28        | 1%      |
| 0x08108109 | 25        | 0.89%   |
| 0x10676    | 24        | 0.86%   |
| 0x20652    | 22        | 0.79%   |
| 0x30678    | 21        | 0.75%   |
| 0x506e3    | 20        | 0.72%   |
| 0x706a1    | 19        | 0.68%   |
| 0x706e5    | 18        | 0.64%   |
| 0x08701021 | 18        | 0.64%   |
| 0x806eb    | 15        | 0.54%   |
| 0x06006705 | 15        | 0.54%   |
| 0x706a8    | 14        | 0.5%    |
| 0x406c3    | 14        | 0.5%    |
| 0x106e5    | 14        | 0.5%    |
| 0x506c9    | 13        | 0.46%   |
| 0x08600106 | 13        | 0.46%   |
| 0xa0652    | 12        | 0.43%   |
| 0x6fb      | 12        | 0.43%   |
| 0x906ed    | 11        | 0.39%   |
| 0x406c4    | 11        | 0.39%   |
| 0x08608103 | 11        | 0.39%   |
| 0x0800820d | 11        | 0.39%   |
| 0x06001119 | 11        | 0.39%   |
| 0x010000c8 | 11        | 0.39%   |
| 0x40661    | 10        | 0.36%   |
| 0x0a50000c | 10        | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| KabyLake           | 395       | 14.4%   |
| SandyBridge        | 274       | 9.99%   |
| Haswell            | 273       | 9.95%   |
| IvyBridge          | 252       | 9.18%   |
| Penryn             | 201       | 7.33%   |
| Skylake            | 146       | 5.32%   |
| Unknown            | 123       | 4.48%   |
| Westmere           | 108       | 3.94%   |
| TigerLake          | 93        | 3.39%   |
| Broadwell          | 90        | 3.28%   |
| Zen+               | 76        | 2.77%   |
| Silvermont         | 75        | 2.73%   |
| Goldmont plus      | 71        | 2.59%   |
| Zen 2              | 68        | 2.48%   |
| Core               | 63        | 2.3%    |
| Excavator          | 49        | 1.79%   |
| Zen 3              | 48        | 1.75%   |
| IceLake            | 41        | 1.49%   |
| Zen                | 40        | 1.46%   |
| CometLake          | 40        | 1.46%   |
| K10                | 35        | 1.28%   |
| Piledriver         | 31        | 1.13%   |
| Nehalem            | 30        | 1.09%   |
| Puma               | 25        | 0.91%   |
| Goldmont           | 20        | 0.73%   |
| Bobcat             | 14        | 0.51%   |
| Steamroller        | 11        | 0.4%    |
| Jaguar             | 11        | 0.4%    |
| Alderlake Hybrid   | 9         | 0.33%   |
| K10 Llano          | 6         | 0.22%   |
| Bulldozer          | 6         | 0.22%   |
| Bonnell            | 6         | 0.22%   |
| Tremont            | 5         | 0.18%   |
| NetBurst           | 3         | 0.11%   |
| K8 Hammer          | 2         | 0.07%   |
| K8 & K10 hybrid    | 2         | 0.07%   |
| Lunarlake Hybrid   | 1         | 0.04%   |
| ArrowLake-H Hybrid | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1766      | 55.03%  |
| Nvidia                     | 724       | 22.56%  |
| AMD                        | 710       | 22.13%  |
| VIA Technologies           | 2         | 0.06%   |
| Matrox Electronics Systems | 2         | 0.06%   |
| ATI Technologies           | 2         | 0.06%   |
| Huawei Technologies        | 1         | 0.03%   |
| Conexant Systems           | 1         | 0.03%   |
| ASPEED Technology          | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 224       | 6.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 170       | 5.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 107       | 3.25%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 78        | 2.37%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 76        | 2.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 75        | 2.27%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 73        | 2.21%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 62        | 1.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 57        | 1.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 54        | 1.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 52        | 1.58%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 49        | 1.49%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 46        | 1.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 45        | 1.36%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 41        | 1.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 40        | 1.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 38        | 1.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 38        | 1.15%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 36        | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 34        | 1.03%   |
| Nvidia C79 [GeForce 9400M]                                                               | 33        | 1%      |
| Intel Broadwell-U GT3 [HD Graphics 6000]                                                 | 29        | 0.88%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 28        | 0.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 28        | 0.85%   |
| AMD Lucienne                                                                             | 28        | 0.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 25        | 0.76%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 25        | 0.76%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 24        | 0.73%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 23        | 0.7%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 23        | 0.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 21        | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 21        | 0.64%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 21        | 0.64%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 21        | 0.64%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 19        | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 18        | 0.55%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 18        | 0.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 18        | 0.55%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 18        | 0.55%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                          | 18        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| 1 x Intel                      | 1333      | 48.49%  |
| 1 x AMD                        | 551       | 20.04%  |
| 1 x Nvidia                     | 388       | 14.11%  |
| Intel + Nvidia                 | 296       | 10.77%  |
| Intel + AMD                    | 89        | 3.24%   |
| 2 x AMD                        | 40        | 1.46%   |
| AMD + Nvidia                   | 26        | 0.95%   |
| 2 x Nvidia                     | 12        | 0.44%   |
| Other                          | 5         | 0.18%   |
| 1 x VIA                        | 2         | 0.07%   |
| 1 x Matrox                     | 2         | 0.07%   |
| Intel + 2 x AMD                | 2         | 0.07%   |
| 2 x AMD + 1 x Conexant Systems | 1         | 0.04%   |
| Nvidia + ASPEED                | 1         | 0.04%   |
| 1 x Huawei Technologies        | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2453      | 88.97%  |
| Proprietary | 248       | 9%      |
| Unknown     | 56        | 2.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2000      | 71.86%  |
| 1.01-2.0   | 237       | 8.52%   |
| 0.01-0.5   | 185       | 6.65%   |
| 0.51-1.0   | 141       | 5.07%   |
| 3.01-4.0   | 106       | 3.81%   |
| 7.01-8.0   | 58        | 2.08%   |
| 5.01-6.0   | 30        | 1.08%   |
| 8.01-16.0  | 16        | 0.57%   |
| 2.01-3.0   | 9         | 0.32%   |
| 16.01-24.0 | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Apple                   | 355       | 12.16%  |
| AU Optronics            | 348       | 11.92%  |
| Samsung Electronics     | 301       | 10.31%  |
| BOE                     | 278       | 9.52%   |
| LG Display              | 276       | 9.46%   |
| Chimei Innolux          | 247       | 8.46%   |
| Dell                    | 115       | 3.94%   |
| Goldstar                | 114       | 3.91%   |
| Hewlett-Packard         | 85        | 2.91%   |
| Acer                    | 69        | 2.36%   |
| AOC                     | 60        | 2.06%   |
| Sharp                   | 56        | 1.92%   |
| Lenovo                  | 53        | 1.82%   |
| BenQ                    | 45        | 1.54%   |
| Philips                 | 42        | 1.44%   |
| Chi Mei Optoelectronics | 40        | 1.37%   |
| Ancor Communications    | 30        | 1.03%   |
| PANDA                   | 25        | 0.86%   |
| ViewSonic               | 21        | 0.72%   |
| LG Electronics          | 18        | 0.62%   |
| Panasonic               | 17        | 0.58%   |
| InfoVision              | 16        | 0.55%   |
| Sony                    | 15        | 0.51%   |
| ASUSTek Computer        | 14        | 0.48%   |
| Vizio                   | 13        | 0.45%   |
| Unknown                 | 12        | 0.41%   |
| MSI                     | 11        | 0.38%   |
| Fujitsu Siemens         | 11        | 0.38%   |
| Iiyama                  | 10        | 0.34%   |
| NEC Computers           | 9         | 0.31%   |
| HKC                     | 9         | 0.31%   |
| HannStar                | 9         | 0.31%   |
| CSO                     | 8         | 0.27%   |
| Toshiba                 | 7         | 0.24%   |
| Eizo                    | 7         | 0.24%   |
| LG Philips              | 6         | 0.21%   |
| CPT                     | 6         | 0.21%   |
| Mi                      | 5         | 0.17%   |
| ___                     | 4         | 0.14%   |
| Unknown (XXX)           | 4         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 21        | 0.7%    |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                 | 21        | 0.7%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 19        | 0.63%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch               | 19        | 0.63%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 16        | 0.53%   |
| Apple iMac APPA012 1920x1080 475x267mm 21.5-inch                     | 15        | 0.5%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 14        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 13        | 0.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 12        | 0.4%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 12        | 0.4%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 12        | 0.4%    |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 12        | 0.4%    |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                 | 12        | 0.4%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 11        | 0.37%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 11        | 0.37%   |
| Apple Color LCD APP9C6B 1680x1050 433x270mm 20.1-inch                | 11        | 0.37%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 10        | 0.33%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 10        | 0.33%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch               | 10        | 0.33%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 9         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 9         | 0.3%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 9         | 0.3%    |
| Apple Color LCD APPA019 2880x1800 331x207mm 15.4-inch                | 9         | 0.3%    |
| Panasonic VVX11F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch         | 8         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 8         | 0.27%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 8         | 0.27%   |
| Apple LCD Monitor APP9CCB 1280x800 286x179mm 13.3-inch               | 8         | 0.27%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch               | 8         | 0.27%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                     | 8         | 0.27%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                 | 8         | 0.27%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 8         | 0.27%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 7         | 0.23%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 7         | 0.23%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 7         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 7         | 0.23%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 7         | 0.23%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 7         | 0.23%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 7         | 0.23%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch        | 7         | 0.23%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 7         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1121      | 39.65%  |
| 1366x768 (WXGA)    | 627       | 22.18%  |
| 3840x2160 (4K)     | 160       | 5.66%   |
| 1280x800 (WXGA)    | 136       | 4.81%   |
| 1600x900 (HD+)     | 127       | 4.49%   |
| 2560x1440 (QHD)    | 116       | 4.1%    |
| 1440x900 (WXGA+)   | 100       | 3.54%   |
| 1680x1050 (WSXGA+) | 81        | 2.87%   |
| 1920x1200 (WUXGA)  | 61        | 2.16%   |
| 1280x1024 (SXGA)   | 42        | 1.49%   |
| 2880x1800          | 38        | 1.34%   |
| 2560x1600          | 30        | 1.06%   |
| 2560x1080          | 23        | 0.81%   |
| Unknown            | 20        | 0.71%   |
| 3440x1440          | 18        | 0.64%   |
| 1360x768           | 16        | 0.57%   |
| 2160x1440          | 11        | 0.39%   |
| 3840x1080          | 10        | 0.35%   |
| 1920x540           | 8         | 0.28%   |
| 3000x2000          | 7         | 0.25%   |
| 3840x2400          | 6         | 0.21%   |
| 1024x600           | 6         | 0.21%   |
| 3200x1800 (QHD+)   | 5         | 0.18%   |
| 1600x1200          | 5         | 0.18%   |
| 2880x1920          | 4         | 0.14%   |
| 1920x1280          | 4         | 0.14%   |
| 5120x1440          | 3         | 0.11%   |
| 2736x1824          | 3         | 0.11%   |
| 1280x720 (HD)      | 3         | 0.11%   |
| 3840x1200          | 2         | 0.07%   |
| 3072x1920          | 2         | 0.07%   |
| 2288x1287          | 2         | 0.07%   |
| 2048x1152          | 2         | 0.07%   |
| 1680x945           | 2         | 0.07%   |
| 1400x1050          | 2         | 0.07%   |
| 1024x768 (XGA)     | 2         | 0.07%   |
| 7680x2160          | 1         | 0.04%   |
| 7680x1600          | 1         | 0.04%   |
| 5760x2160          | 1         | 0.04%   |
| 5760x1080          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 759       | 25.96%  |
| 13      | 452       | 15.46%  |
| 14      | 248       | 8.48%   |
| 27      | 184       | 6.29%   |
| 24      | 155       | 5.3%    |
| 17      | 141       | 4.82%   |
| 21      | 138       | 4.72%   |
| 23      | 128       | 4.38%   |
| Unknown | 113       | 3.86%   |
| 31      | 72        | 2.46%   |
| 11      | 64        | 2.19%   |
| 20      | 52        | 1.78%   |
| 19      | 48        | 1.64%   |
| 12      | 48        | 1.64%   |
| 18      | 44        | 1.5%    |
| 22      | 40        | 1.37%   |
| 34      | 26        | 0.89%   |
| 84      | 21        | 0.72%   |
| 32      | 21        | 0.72%   |
| 16      | 20        | 0.68%   |
| 54      | 18        | 0.62%   |
| 72      | 14        | 0.48%   |
| 26      | 12        | 0.41%   |
| 10      | 12        | 0.41%   |
| 25      | 10        | 0.34%   |
| 40      | 9         | 0.31%   |
| 63      | 6         | 0.21%   |
| 36      | 6         | 0.21%   |
| 28      | 6         | 0.21%   |
| 65      | 5         | 0.17%   |
| 29      | 5         | 0.17%   |
| 74      | 4         | 0.14%   |
| 49      | 4         | 0.14%   |
| 48      | 4         | 0.14%   |
| 43      | 4         | 0.14%   |
| 42      | 4         | 0.14%   |
| 33      | 4         | 0.14%   |
| 60      | 3         | 0.1%    |
| 64      | 2         | 0.07%   |
| 57      | 2         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1182      | 40.97%  |
| 501-600        | 451       | 15.63%  |
| 201-300        | 417       | 14.45%  |
| 401-500        | 294       | 10.19%  |
| 351-400        | 162       | 5.62%   |
| Unknown        | 113       | 3.92%   |
| 601-700        | 95        | 3.29%   |
| 701-800        | 56        | 1.94%   |
| 1001-1500      | 50        | 1.73%   |
| 1501-2000      | 40        | 1.39%   |
| 801-900        | 16        | 0.55%   |
| 901-1000       | 8         | 0.28%   |
| More than 2000 | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1992      | 74.33%  |
| 16/10   | 453       | 16.9%   |
| Unknown | 101       | 3.77%   |
| 3/2     | 41        | 1.53%   |
| 5/4     | 38        | 1.42%   |
| 21/9    | 34        | 1.27%   |
| 4/3     | 9         | 0.34%   |
| 32/9    | 4         | 0.15%   |
| 6/5     | 2         | 0.07%   |
| 3.73    | 1         | 0.04%   |
| 3.40    | 1         | 0.04%   |
| 3.20    | 1         | 0.04%   |
| 1.96    | 1         | 0.04%   |
| 1.00    | 1         | 0.04%   |
| 0.56    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 754       | 25.96%  |
| 81-90          | 531       | 18.29%  |
| 201-250        | 364       | 12.53%  |
| 301-350        | 191       | 6.58%   |
| 71-80          | 165       | 5.68%   |
| 151-200        | 132       | 4.55%   |
| 351-500        | 130       | 4.48%   |
| Unknown        | 113       | 3.89%   |
| 121-130        | 95        | 3.27%   |
| More than 1000 | 84        | 2.89%   |
| 251-300        | 71        | 2.44%   |
| 51-60          | 65        | 2.24%   |
| 141-150        | 60        | 2.07%   |
| 61-70          | 47        | 1.62%   |
| 501-1000       | 35        | 1.21%   |
| 131-140        | 27        | 0.93%   |
| 111-120        | 22        | 0.76%   |
| 41-50          | 12        | 0.41%   |
| 91-100         | 6         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 916       | 32.24%  |
| 121-160       | 783       | 27.56%  |
| 51-100        | 710       | 24.99%  |
| 161-240       | 192       | 6.76%   |
| Unknown       | 113       | 3.98%   |
| 1-50          | 73        | 2.57%   |
| More than 240 | 54        | 1.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2392      | 86.01%  |
| 2     | 321       | 11.54%  |
| 0     | 37        | 1.33%   |
| 3     | 29        | 1.04%   |
| 4     | 2         | 0.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1336      | 31.62%  |
| Intel                             | 1113      | 26.34%  |
| Broadcom                          | 530       | 12.54%  |
| Qualcomm Atheros                  | 463       | 10.96%  |
| Broadcom Limited                  | 120       | 2.84%   |
| Marvell Technology Group          | 81        | 1.92%   |
| Nvidia                            | 71        | 1.68%   |
| TP-Link                           | 61        | 1.44%   |
| MediaTek                          | 61        | 1.44%   |
| Ralink Technology                 | 46        | 1.09%   |
| Samsung Electronics               | 35        | 0.83%   |
| Ralink                            | 32        | 0.76%   |
| ASIX Electronics                  | 28        | 0.66%   |
| Xiaomi                            | 24        | 0.57%   |
| Sierra Wireless                   | 15        | 0.36%   |
| Huawei Technologies               | 14        | 0.33%   |
| Qualcomm                          | 13        | 0.31%   |
| Qualcomm Atheros Communications   | 11        | 0.26%   |
| D-Link                            | 11        | 0.26%   |
| Shenzhen Goodix Technology        | 9         | 0.21%   |
| Hewlett-Packard                   | 9         | 0.21%   |
| D-Link System                     | 9         | 0.21%   |
| OPPO Electronics                  | 8         | 0.19%   |
| Ericsson Business Mobile Networks | 8         | 0.19%   |
| Dell                              | 8         | 0.19%   |
| NetGear                           | 7         | 0.17%   |
| Google                            | 7         | 0.17%   |
| Microsoft                         | 6         | 0.14%   |
| ASUSTek Computer                  | 6         | 0.14%   |
| Apple                             | 6         | 0.14%   |
| Linksys                           | 5         | 0.12%   |
| Lenovo                            | 4         | 0.09%   |
| ICS Advent                        | 4         | 0.09%   |
| Edimax Technology                 | 4         | 0.09%   |
| VIA Technologies                  | 3         | 0.07%   |
| Motorola PCS                      | 3         | 0.07%   |
| JMicron Technology                | 3         | 0.07%   |
| Aquantia                          | 3         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.05%   |
| TRENDnet                          | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 846       | 16.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 195       | 3.9%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 102       | 2.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 95        | 1.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 94        | 1.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 75        | 1.5%    |
| Intel Wi-Fi 6 AX201                                                    | 71        | 1.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 67        | 1.34%   |
| Intel Wireless 7265                                                    | 67        | 1.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 66        | 1.32%   |
| Intel Wireless 8260                                                    | 66        | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 64        | 1.28%   |
| Intel Wireless 8265 / 8275                                             | 64        | 1.28%   |
| Intel Wi-Fi 6 AX200                                                    | 62        | 1.24%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 57        | 1.14%   |
| Nvidia MCP79 Ethernet                                                  | 55        | 1.1%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 54        | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 52        | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 52        | 1.04%   |
| Intel Wireless 7260                                                    | 51        | 1.02%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 50        | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 47        | 0.94%   |
| Intel Wireless 3165                                                    | 42        | 0.84%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 42        | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                      | 41        | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 41        | 0.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 39        | 0.78%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 38        | 0.76%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 38        | 0.76%   |
| Broadcom BCM43142 802.11b/g/n                                          | 38        | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 37        | 0.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 37        | 0.74%   |
| Broadcom BCM4321 802.11a/b/g/n                                         | 36        | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 33        | 0.66%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 33        | 0.66%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 33        | 0.66%   |
| Intel Ethernet Connection I217-LM                                      | 32        | 0.64%   |
| Realtek 802.11ac NIC                                                   | 28        | 0.56%   |
| Intel I211 Gigabit Network Connection                                  | 28        | 0.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 28        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 876       | 34.76%  |
| Broadcom                              | 429       | 17.02%  |
| Realtek Semiconductor                 | 414       | 16.43%  |
| Qualcomm Atheros                      | 388       | 15.4%   |
| Broadcom Limited                      | 105       | 4.17%   |
| TP-Link                               | 60        | 2.38%   |
| MediaTek                              | 50        | 1.98%   |
| Ralink Technology                     | 46        | 1.83%   |
| Ralink                                | 32        | 1.27%   |
| Marvell Technology Group              | 18        | 0.71%   |
| Sierra Wireless                       | 15        | 0.6%    |
| Qualcomm Atheros Communications       | 11        | 0.44%   |
| D-Link                                | 9         | 0.36%   |
| D-Link System                         | 8         | 0.32%   |
| Qualcomm                              | 6         | 0.24%   |
| NetGear                               | 6         | 0.24%   |
| ASUSTek Computer                      | 6         | 0.24%   |
| Microsoft                             | 5         | 0.2%    |
| Linksys                               | 4         | 0.16%   |
| Edimax Technology                     | 4         | 0.16%   |
| Dell                                  | 4         | 0.16%   |
| TRENDnet                              | 2         | 0.08%   |
| Mercucys                              | 2         | 0.08%   |
| Fibocom                               | 2         | 0.08%   |
| BUFFALO                               | 2         | 0.08%   |
| Belkin Components                     | 2         | 0.08%   |
| AVM                                   | 2         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.08%   |
| ZyXEL Communications                  | 1         | 0.04%   |
| ZyDAS                                 | 1         | 0.04%   |
| Wacom                                 | 1         | 0.04%   |
| Sitecom Europe                        | 1         | 0.04%   |
| Realtek                               | 1         | 0.04%   |
| LG Electronics                        | 1         | 0.04%   |
| Hewlett-Packard                       | 1         | 0.04%   |
| AirTies Wireless Networks             | 1         | 0.04%   |
| Accton Technology                     | 1         | 0.04%   |
| AboCom Systems                        | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4331 802.11a/b/g/n                                       | 95        | 3.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 75        | 2.95%   |
| Intel Wi-Fi 6 AX201                                                  | 71        | 2.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 67        | 2.64%   |
| Intel Wireless 7265                                                  | 67        | 2.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 66        | 2.6%    |
| Intel Wireless 8260                                                  | 66        | 2.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 64        | 2.52%   |
| Intel Wireless 8265 / 8275                                           | 64        | 2.52%   |
| Intel Wi-Fi 6 AX200                                                  | 62        | 2.44%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 57        | 2.24%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller               | 54        | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 52        | 2.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 52        | 2.05%   |
| Intel Wireless 7260                                                  | 51        | 2.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 47        | 1.85%   |
| Intel Wireless 3165                                                  | 42        | 1.65%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 42        | 1.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 41        | 1.61%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 38        | 1.5%    |
| Broadcom BCM43142 802.11b/g/n                                        | 38        | 1.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 37        | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 37        | 1.46%   |
| Broadcom BCM4321 802.11a/b/g/n                                       | 36        | 1.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 33        | 1.3%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)       | 33        | 1.3%    |
| Realtek 802.11ac NIC                                                 | 28        | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 28        | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 27        | 1.06%   |
| Ralink MT7601U Wireless Adapter                                      | 26        | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 26        | 1.02%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 25        | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 24        | 0.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 24        | 0.94%   |
| Intel Wireless 3160                                                  | 23        | 0.91%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 23        | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 22        | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 22        | 0.87%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                    | 22        | 0.87%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 21        | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1138      | 47.77%  |
| Intel                             | 527       | 22.12%  |
| Broadcom                          | 263       | 11.04%  |
| Qualcomm Atheros                  | 122       | 5.12%   |
| Nvidia                            | 71        | 2.98%   |
| Marvell Technology Group          | 63        | 2.64%   |
| Samsung Electronics               | 35        | 1.47%   |
| ASIX Electronics                  | 28        | 1.18%   |
| Xiaomi                            | 24        | 1.01%   |
| Broadcom Limited                  | 16        | 0.67%   |
| MediaTek                          | 13        | 0.55%   |
| Huawei Technologies               | 11        | 0.46%   |
| OPPO Electronics                  | 8         | 0.34%   |
| Qualcomm                          | 7         | 0.29%   |
| Google                            | 7         | 0.29%   |
| Apple                             | 6         | 0.25%   |
| Lenovo                            | 4         | 0.17%   |
| ICS Advent                        | 4         | 0.17%   |
| VIA Technologies                  | 3         | 0.13%   |
| Motorola PCS                      | 3         | 0.13%   |
| JMicron Technology                | 3         | 0.13%   |
| Aquantia                          | 3         | 0.13%   |
| Hewlett-Packard                   | 2         | 0.08%   |
| D-Link                            | 2         | 0.08%   |
| Attansic Technology               | 2         | 0.08%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.04%   |
| vivo                              | 1         | 0.04%   |
| TP-Link                           | 1         | 0.04%   |
| Sundance Technology Inc / IC Plus | 1         | 0.04%   |
| Qualcomm Technologies             | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.04%   |
| NetGear                           | 1         | 0.04%   |
| Motorcomm Microelectronics.       | 1         | 0.04%   |
| Microsoft                         | 1         | 0.04%   |
| LSI                               | 1         | 0.04%   |
| Linksys                           | 1         | 0.04%   |
| LG Electronics                    | 1         | 0.04%   |
| HMD Global                        | 1         | 0.04%   |
| DisplayLink                       | 1         | 0.04%   |
| D-Link System                     | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 846       | 35.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 195       | 8.07%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 102       | 4.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 94        | 3.89%   |
| Nvidia MCP79 Ethernet                                                  | 55        | 2.28%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 50        | 2.07%   |
| Realtek RTL8125 2.5GbE Controller                                      | 41        | 1.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 39        | 1.61%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 38        | 1.57%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 33        | 1.37%   |
| Intel Ethernet Connection I217-LM                                      | 32        | 1.32%   |
| Intel I211 Gigabit Network Connection                                  | 28        | 1.16%   |
| Intel Ethernet Connection (2) I219-V                                   | 26        | 1.08%   |
| Intel Ethernet Connection I219-LM                                      | 25        | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 24        | 0.99%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 22        | 0.91%   |
| ASIX AX88179 Gigabit Ethernet                                          | 22        | 0.91%   |
| Intel 82577LM Gigabit Network Connection                               | 21        | 0.87%   |
| Intel Ethernet Connection I218-LM                                      | 20        | 0.83%   |
| Intel Ethernet Connection (7) I219-V                                   | 20        | 0.83%   |
| Intel 82579V Gigabit Network Connection                                | 20        | 0.83%   |
| Intel Ethernet Controller I225-V                                       | 19        | 0.79%   |
| Intel Ethernet Connection (4) I219-V                                   | 19        | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 18        | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 17        | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                                  | 16        | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 15        | 0.62%   |
| Intel Ethernet Connection I217-V                                       | 14        | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                                  | 14        | 0.58%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 14        | 0.58%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 13        | 0.54%   |
| Intel Ethernet Connection I219-V                                       | 12        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                                  | 12        | 0.5%    |
| Intel 82567LM Gigabit Network Connection                               | 12        | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 11        | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 11        | 0.46%   |
| Intel 82574L Gigabit Network Connection                                | 11        | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 9         | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 9         | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 9         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2373      | 50.9%   |
| Ethernet | 2248      | 48.22%  |
| Modem    | 38        | 0.82%   |
| Unknown  | 3         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1869      | 66.44%  |
| Ethernet | 944       | 33.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1633      | 59.45%  |
| 1     | 1023      | 37.24%  |
| 0     | 45        | 1.64%   |
| 3     | 40        | 1.46%   |
| 4     | 5         | 0.18%   |
| 5     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 1980      | 71.2%   |
| Yes     | 800       | 28.77%  |
| Unknown | 1         | 0.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 750       | 36.39%  |
| Apple                           | 389       | 18.87%  |
| Realtek Semiconductor           | 216       | 10.48%  |
| Qualcomm Atheros Communications | 145       | 7.04%   |
| Cambridge Silicon Radio         | 90        | 4.37%   |
| Broadcom                        | 89        | 4.32%   |
| Foxconn / Hon Hai               | 72        | 3.49%   |
| Lite-On Technology              | 63        | 3.06%   |
| IMC Networks                    | 62        | 3.01%   |
| Dell                            | 27        | 1.31%   |
| Hewlett-Packard                 | 26        | 1.26%   |
| Toshiba                         | 22        | 1.07%   |
| Marvell Semiconductor           | 17        | 0.82%   |
| ASUSTek Computer                | 17        | 0.82%   |
| Ralink                          | 16        | 0.78%   |
| Realtek                         | 14        | 0.68%   |
| MediaTek                        | 10        | 0.49%   |
| Unknown                         | 7         | 0.34%   |
| TP-Link                         | 5         | 0.24%   |
| Foxconn International           | 4         | 0.19%   |
| Qcom                            | 3         | 0.15%   |
| Belkin Components               | 2         | 0.1%    |
| Askey Computer                  | 2         | 0.1%    |
| Alps Electric                   | 2         | 0.1%    |
| Actions                         | 2         | 0.1%    |
| USI                             | 1         | 0.05%   |
| Taiyo Yuden                     | 1         | 0.05%   |
| Smart Modular Technologies      | 1         | 0.05%   |
| Ralink Technology               | 1         | 0.05%   |
| Opticis                         | 1         | 0.05%   |
| Logitech                        | 1         | 0.05%   |
| Fujitsu                         | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| 3Com                            | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 322       | 15.62%  |
| Apple Bluetooth Host Controller                     | 176       | 8.54%   |
| Intel AX201 Bluetooth                               | 135       | 6.55%   |
| Realtek Bluetooth Radio                             | 131       | 6.36%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 115       | 5.58%   |
| Apple Bluetooth USB Host Controller                 | 113       | 5.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 90        | 4.37%   |
| Qualcomm Atheros  Bluetooth Device                  | 75        | 3.64%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 62        | 3.01%   |
| Intel AX200 Bluetooth                               | 61        | 2.96%   |
| Realtek  Bluetooth 4.2 Adapter                      | 53        | 2.57%   |
| Apple Bluetooth HCI                                 | 38        | 1.84%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 32        | 1.55%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 26        | 1.26%   |
| Intel AX210 Bluetooth                               | 24        | 1.16%   |
| Foxconn / Hon Hai Bluetooth Device                  | 23        | 1.12%   |
| IMC Networks Wireless_Device                        | 22        | 1.07%   |
| HP Broadcom 2070 Bluetooth Combo                    | 21        | 1.02%   |
| Intel Wireless-AC 3168 Bluetooth                    | 19        | 0.92%   |
| Intel Bluetooth Device                              | 19        | 0.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 18        | 0.87%   |
| Ralink RT3290 Bluetooth                             | 16        | 0.78%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 0.78%   |
| IMC Networks Bluetooth Radio                        | 16        | 0.78%   |
| Dell DW375 Bluetooth Module                         | 16        | 0.78%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 16        | 0.78%   |
| Lite-On Bluetooth Device                            | 15        | 0.73%   |
| Realtek Bluetooth Radio                             | 14        | 0.68%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 13        | 0.63%   |
| Lite-On Atheros AR3012 Bluetooth                    | 13        | 0.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 13        | 0.63%   |
| Marvell Bluetooth and Wireless LAN Composite        | 12        | 0.58%   |
| Realtek RTL8821A Bluetooth                          | 11        | 0.53%   |
| Broadcom BCM2045B (BDC-2.1)                         | 11        | 0.53%   |
| MediaTek Wireless_Device                            | 10        | 0.49%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 0.49%   |
| Broadcom BCM43142A0 Bluetooth Device                | 10        | 0.49%   |
| IMC Networks Bluetooth Device                       | 9         | 0.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.39%   |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2129      | 58.93%  |
| AMD                                          | 676       | 18.71%  |
| Nvidia                                       | 536       | 14.84%  |
| C-Media Electronics                          | 61        | 1.69%   |
| Logitech                                     | 27        | 0.75%   |
| Generalplus Technology                       | 17        | 0.47%   |
| Creative Labs                                | 17        | 0.47%   |
| JMTek                                        | 10        | 0.28%   |
| Texas Instruments                            | 9         | 0.25%   |
| GN Netcom                                    | 8         | 0.22%   |
| Realtek Semiconductor                        | 6         | 0.17%   |
| BEHRINGER International                      | 6         | 0.17%   |
| Razer USA                                    | 5         | 0.14%   |
| Creative Technology                          | 5         | 0.14%   |
| Corsair                                      | 5         | 0.14%   |
| VIA Technologies                             | 4         | 0.11%   |
| Plantronics                                  | 4         | 0.11%   |
| Micro Star International                     | 4         | 0.11%   |
| Hewlett-Packard                              | 4         | 0.11%   |
| Dell                                         | 4         | 0.11%   |
| ASUSTek Computer                             | 4         | 0.11%   |
| Thesycon Systemsoftware & Consulting         | 3         | 0.08%   |
| Cambridge Silicon Radio                      | 3         | 0.08%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.06%   |
| SteelSeries ApS                              | 2         | 0.06%   |
| Sony                                         | 2         | 0.06%   |
| Nordic Semiconductor ASA                     | 2         | 0.06%   |
| Native Instruments                           | 2         | 0.06%   |
| Microsoft                                    | 2         | 0.06%   |
| M-Audio                                      | 2         | 0.06%   |
| KTMicro                                      | 2         | 0.06%   |
| Kingston Technology                          | 2         | 0.06%   |
| Jieli Technology                             | 2         | 0.06%   |
| Huawei Technologies                          | 2         | 0.06%   |
| Guillemot                                    | 2         | 0.06%   |
| Goldvish                                     | 2         | 0.06%   |
| Focusrite-Novation                           | 2         | 0.06%   |
| fifine Microphones                           | 2         | 0.06%   |
| ESS Technology                               | 2         | 0.06%   |
| Apple                                        | 2         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 256       | 5.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 253       | 5.85%   |
| Intel Sunrise Point-LP HD Audio                                            | 244       | 5.64%   |
| AMD Ryzen HD Audio Controller                                              | 203       | 4.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 147       | 3.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 121       | 2.8%    |
| Intel Haswell-ULT HD Audio Controller                                      | 109       | 2.52%   |
| Intel 8 Series HD Audio Controller                                         | 109       | 2.52%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 94        | 2.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 93        | 2.15%   |
| Intel Broadwell-U Audio Controller                                         | 88        | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 87        | 2.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 82        | 1.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 79        | 1.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 79        | 1.83%   |
| Intel Cannon Lake PCH cAVS                                                 | 77        | 1.78%   |
| AMD FCH Azalia Controller                                                  | 77        | 1.78%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 71        | 1.64%   |
| AMD Kabini HDMI/DP Audio                                                   | 58        | 1.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 57        | 1.32%   |
| Nvidia MCP79 High Definition Audio                                         | 55        | 1.27%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 54        | 1.25%   |
| Intel Comet Lake PCH-LP cAVS                                               | 52        | 1.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 50        | 1.16%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 48        | 1.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 46        | 1.06%   |
| AMD Starship/Matisse HD Audio Controller                                   | 45        | 1.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 42        | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 42        | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                            | 40        | 0.92%   |
| Intel 200 Series PCH HD Audio                                              | 40        | 0.92%   |
| Nvidia GK107 HDMI Audio Controller                                         | 38        | 0.88%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 36        | 0.83%   |
| AMD Radeon High Definition Audio Controller                                | 31        | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                              | 30        | 0.69%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 29        | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 29        | 0.67%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 29        | 0.67%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 29        | 0.67%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 28        | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 163       | 23.76%  |
| SK hynix                     | 119       | 17.35%  |
| Micron Technology            | 84        | 12.24%  |
| Kingston                     | 82        | 11.95%  |
| Unknown                      | 49        | 7.14%   |
| Crucial                      | 35        | 5.1%    |
| Corsair                      | 20        | 2.92%   |
| Elpida                       | 19        | 2.77%   |
| Unknown (ABCD)               | 14        | 2.04%   |
| Ramaxel Technology           | 13        | 1.9%    |
| A-DATA Technology            | 13        | 1.9%    |
| G.Skill                      | 12        | 1.75%   |
| Nanya Technology             | 6         | 0.87%   |
| Transcend                    | 5         | 0.73%   |
| Unknown                      | 5         | 0.73%   |
| Smart                        | 4         | 0.58%   |
| Patriot                      | 4         | 0.58%   |
| Timetec                      | 3         | 0.44%   |
| Team                         | 3         | 0.44%   |
| GSkill                       | 3         | 0.44%   |
| Apacer                       | 3         | 0.44%   |
| PNY                          | 2         | 0.29%   |
| Multilaser                   | 2         | 0.29%   |
| AMD                          | 2         | 0.29%   |
| Unknown (82B5)               | 1         | 0.15%   |
| Unknown (0x5846)             | 1         | 0.15%   |
| Unknown (0x198)              | 1         | 0.15%   |
| Unknown (0x0C26)             | 1         | 0.15%   |
| Unknown (0x038A)             | 1         | 0.15%   |
| Toshiba                      | 1         | 0.15%   |
| Smart Brazil                 | 1         | 0.15%   |
| SHARETRONIC                  | 1         | 0.15%   |
| Qimonda                      | 1         | 0.15%   |
| pqi                          | 1         | 0.15%   |
| Patriot Memory (PDP Systems) | 1         | 0.15%   |
| Neo Forza                    | 1         | 0.15%   |
| Melco                        | 1         | 0.15%   |
| Magnum Tech                  | 1         | 0.15%   |
| Kllisre                      | 1         | 0.15%   |
| Hewlett-Packard              | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 12        | 1.66%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 1.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 1.1%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 0.97%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.69%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.69%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 5         | 0.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 0.69%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s            | 5         | 0.69%   |
| Unknown                                                          | 5         | 0.69%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 4         | 0.55%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 4         | 0.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.55%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.55%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 4         | 0.55%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 4         | 0.55%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 4         | 0.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.55%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 4         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                   | 3         | 0.41%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 3         | 0.41%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 3         | 0.41%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GiB SODIMM DDR3 2667MT/s          | 3         | 0.41%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.41%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.41%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 3         | 0.41%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                      | 3         | 0.41%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s         | 3         | 0.41%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.41%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.41%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 3         | 0.41%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 0.41%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.41%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 3         | 0.41%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 3         | 0.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.41%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 3         | 0.41%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 3         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 231       | 40.46%  |
| DDR4    | 222       | 38.88%  |
| LPDDR4  | 40        | 7.01%   |
| DDR2    | 27        | 4.73%   |
| LPDDR3  | 19        | 3.33%   |
| SDRAM   | 13        | 2.28%   |
| Unknown | 8         | 1.4%    |
| LPDDR5  | 5         | 0.88%   |
| DDR5    | 4         | 0.7%    |
| DRAM    | 1         | 0.18%   |
| DDR     | 1         | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 395       | 68.94%  |
| DIMM         | 117       | 20.42%  |
| Row Of Chips | 54        | 9.42%   |
| Chip         | 4         | 0.7%    |
| Unknown      | 2         | 0.35%   |
| FB-DIMM      | 1         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 255       | 39.66%  |
| 4096  | 191       | 29.7%   |
| 2048  | 91        | 14.15%  |
| 16384 | 73        | 11.35%  |
| 1024  | 18        | 2.8%    |
| 32768 | 14        | 2.18%   |
| 512   | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 138       | 21.84%  |
| 2667    | 96        | 15.19%  |
| 3200    | 76        | 12.03%  |
| 1333    | 56        | 8.86%   |
| 2400    | 49        | 7.75%   |
| 2133    | 41        | 6.49%   |
| 4267    | 16        | 2.53%   |
| 667     | 16        | 2.53%   |
| 1334    | 15        | 2.37%   |
| 800     | 15        | 2.37%   |
| 1867    | 14        | 2.22%   |
| 1067    | 13        | 2.06%   |
| 1066    | 9         | 1.42%   |
| 3600    | 8         | 1.27%   |
| 8400    | 6         | 0.95%   |
| 3266    | 6         | 0.95%   |
| 3733    | 5         | 0.79%   |
| 1866    | 4         | 0.63%   |
| 4800    | 3         | 0.47%   |
| 4266    | 3         | 0.47%   |
| 4199    | 3         | 0.47%   |
| 1800    | 3         | 0.47%   |
| 975     | 3         | 0.47%   |
| Unknown | 3         | 0.47%   |
| 7500    | 2         | 0.32%   |
| 6400    | 2         | 0.32%   |
| 3466    | 2         | 0.32%   |
| 3066    | 2         | 0.32%   |
| 2933    | 2         | 0.32%   |
| 2048    | 2         | 0.32%   |
| 1639    | 2         | 0.32%   |
| 8533    | 1         | 0.16%   |
| 7200    | 1         | 0.16%   |
| 5600    | 1         | 0.16%   |
| 4000    | 1         | 0.16%   |
| 3866    | 1         | 0.16%   |
| 3400    | 1         | 0.16%   |
| 3334    | 1         | 0.16%   |
| 3007    | 1         | 0.16%   |
| 3000    | 1         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 15        | 26.79%  |
| Brother Industries              | 11        | 19.64%  |
| Canon                           | 9         | 16.07%  |
| Samsung Electronics             | 7         | 12.5%   |
| Seiko Epson                     | 5         | 8.93%   |
| Lexmark International           | 3         | 5.36%   |
| Xerox                           | 2         | 3.57%   |
| Prolific Technology             | 1         | 1.79%   |
| PM                              | 1         | 1.79%   |
| Dymo-CoStar                     | 1         | 1.79%   |
| cab Produkttechnik GmbH & Co KG | 1         | 1.79%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Samsung M2020 Series                       | 3         | 5.36%   |
| Samsung M2070 Series                       | 2         | 3.57%   |
| Xerox Phaser 3610                          | 1         | 1.79%   |
| Xerox Phaser 3320                          | 1         | 1.79%   |
| Seiko Epson XP-4100 Series                 | 1         | 1.79%   |
| Seiko Epson L355 Series                    | 1         | 1.79%   |
| Seiko Epson L3050 Series                   | 1         | 1.79%   |
| Seiko Epson EPSON XP-205 207 Series        | 1         | 1.79%   |
| Seiko Epson EPSON WF-3520 Series           | 1         | 1.79%   |
| Samsung M288x Series                       | 1         | 1.79%   |
| Samsung C48x Series                        | 1         | 1.79%   |
| Prolific PL2305 Parallel Port              | 1         | 1.79%   |
| PM PM241-BT                                | 1         | 1.79%   |
| Lexmark International Laser Printer E210   | 1         | 1.79%   |
| Lexmark International InkJet Color Printer | 1         | 1.79%   |
| Lexmark International f+ imaging M40adn    | 1         | 1.79%   |
| HP Smart Tank 580-590 series               | 1         | 1.79%   |
| HP Printing Support                        | 1         | 1.79%   |
| HP OfficeJet 5200 series                   | 1         | 1.79%   |
| HP LaserJet Pro M201dw                     | 1         | 1.79%   |
| HP LaserJet 1320                           | 1         | 1.79%   |
| HP LaserJet 1300                           | 1         | 1.79%   |
| HP LaserJet 1020                           | 1         | 1.79%   |
| HP Ink Tank 110 series                     | 1         | 1.79%   |
| HP HP LaserJet M101-M106                   | 1         | 1.79%   |
| HP Deskjet F4500 series                    | 1         | 1.79%   |
| HP Deskjet 3520 series                     | 1         | 1.79%   |
| HP DeskJet 2700 series                     | 1         | 1.79%   |
| HP DeskJet 2600 series                     | 1         | 1.79%   |
| HP Deskjet 2050 J510                       | 1         | 1.79%   |
| HP Deskjet 1000 J110 series                | 1         | 1.79%   |
| Dymo-CoStar LabelWriter 450                | 1         | 1.79%   |
| Canon TR8500 series                        | 1         | 1.79%   |
| Canon PIXMA MX390 Series                   | 1         | 1.79%   |
| Canon PIXMA MG3600 Series                  | 1         | 1.79%   |
| Canon PIXMA MG2500 Series                  | 1         | 1.79%   |
| Canon MF4320-4350                          | 1         | 1.79%   |
| Canon LiDE 400                             | 1         | 1.79%   |
| Canon LiDE 300                             | 1         | 1.79%   |
| Canon LBP3360                              | 1         | 1.79%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 4         | 66.67%  |
| Seiko Epson | 2         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 16.67%  |
| Seiko Epson ES-H300 [GT-2500]                           | 1         | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 16.67%  |
| Canon CanoScan LIDE 25                                  | 1         | 16.67%  |
| Canon CanoScan LiDE 110                                 | 1         | 16.67%  |
| Canon CanoScan LiDE 100                                 | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 338       | 17.75%  |
| Apple                                  | 298       | 15.65%  |
| Realtek Semiconductor                  | 149       | 7.83%   |
| IMC Networks                           | 130       | 6.83%   |
| Microdia                               | 127       | 6.67%   |
| Bison Electronics                      | 109       | 5.72%   |
| Sunplus Innovation Technology          | 98        | 5.15%   |
| Quanta                                 | 95        | 4.99%   |
| Cheng Uei Precision Industry (Foxlink) | 77        | 4.04%   |
| Suyin                                  | 59        | 3.1%    |
| Syntek                                 | 53        | 2.78%   |
| Logitech                               | 48        | 2.52%   |
| Silicon Motion                         | 34        | 1.79%   |
| Lite-On Technology                     | 34        | 1.79%   |
| Alcor Micro                            | 31        | 1.63%   |
| Luxvisions Innotech Limited            | 29        | 1.52%   |
| Microsoft                              | 18        | 0.95%   |
| Ricoh                                  | 15        | 0.79%   |
| Samsung Electronics                    | 14        | 0.74%   |
| Lenovo                                 | 13        | 0.68%   |
| Generalplus Technology                 | 9         | 0.47%   |
| Z-Star Microelectronics                | 7         | 0.37%   |
| SunplusIT                              | 7         | 0.37%   |
| Importek                               | 7         | 0.37%   |
| Sonix Technology                       | 6         | 0.32%   |
| Primax Electronics                     | 6         | 0.32%   |
| ShineTech                              | 5         | 0.26%   |
| LG Electronics                         | 5         | 0.26%   |
| ALi                                    | 5         | 0.26%   |
| Acer                                   | 5         | 0.26%   |
| KYE Systems (Mouse Systems)            | 4         | 0.21%   |
| icSpring                               | 4         | 0.21%   |
| GEMBIRD                                | 4         | 0.21%   |
| Foxconn / Hon Hai                      | 4         | 0.21%   |
| Cubeternet                             | 4         | 0.21%   |
| Y Media                                | 3         | 0.16%   |
| Jieli Technology                       | 3         | 0.16%   |
| Intel                                  | 3         | 0.16%   |
| Unknown                                | 3         | 0.16%   |
| Sunplus Technology                     | 2         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Apple Built-in iSight                   | 112       | 5.82%   |
| Apple FaceTime HD Camera                | 76        | 3.95%   |
| Chicony Integrated Camera               | 67        | 3.48%   |
| Apple FaceTime HD Camera (Built-in)     | 61        | 3.17%   |
| Realtek Integrated_Webcam_HD            | 40        | 2.08%   |
| IMC Networks USB2.0 HD UVC WebCam       | 39        | 2.03%   |
| Microdia Integrated_Webcam_HD           | 37        | 1.92%   |
| Chicony HD WebCam                       | 37        | 1.92%   |
| IMC Networks Integrated Camera          | 35        | 1.82%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 32        | 1.66%   |
| Syntek Integrated Camera                | 25        | 1.3%    |
| Sunplus Integrated_Webcam_HD            | 25        | 1.3%    |
| Bison Integrated Camera                 | 20        | 1.04%   |
| Apple FaceTime Camera                   | 16        | 0.83%   |
| Microdia Integrated Webcam              | 15        | 0.78%   |
| Lite-On Integrated Camera               | 15        | 0.78%   |
| Realtek USB Camera                      | 14        | 0.73%   |
| Quanta HP Webcam                        | 14        | 0.73%   |
| Chicony HP Truevision HD                | 14        | 0.73%   |
| Bison Lenovo EasyCamera                 | 14        | 0.73%   |
| Samsung Galaxy series, misc. (MTP mode) | 13        | 0.68%   |
| Chicony HP TrueVision HD Camera         | 13        | 0.68%   |
| Chicony EasyCamera                      | 13        | 0.68%   |
| Syntek Lenovo EasyCamera                | 12        | 0.62%   |
| Syntek EasyCamera                       | 12        | 0.62%   |
| Quanta HP TrueVision HD Camera          | 12        | 0.62%   |
| Quanta HD User Facing                   | 12        | 0.62%   |
| Logitech HD Pro Webcam C920             | 12        | 0.62%   |
| Chicony HP HD Webcam [Fixed]            | 12        | 0.62%   |
| Sunplus HD WebCam                       | 11        | 0.57%   |
| Realtek Integrated Webcam               | 11        | 0.57%   |
| Realtek USB2.0 HD UVC WebCam            | 10        | 0.52%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 10        | 0.52%   |
| Bison SunplusIT Integrated Camera       | 10        | 0.52%   |
| Bison EasyCamera                        | 10        | 0.52%   |
| Microdia USB 2.0 Camera                 | 9         | 0.47%   |
| Chicony USB2.0 VGA UVC WebCam           | 9         | 0.47%   |
| Chicony HP HD Camera                    | 9         | 0.47%   |
| Alcor Micro USB 2.0 Camera              | 9         | 0.47%   |
| Realtek Integrated Webcam HD            | 8         | 0.42%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 108       | 37.76%  |
| Synaptics                  | 69        | 24.13%  |
| Shenzhen Goodix Technology | 45        | 15.73%  |
| LighTuning Technology      | 19        | 6.64%   |
| Upek                       | 13        | 4.55%   |
| Elan Microelectronics      | 13        | 4.55%   |
| AuthenTec                  | 13        | 4.55%   |
| STMicroelectronics         | 2         | 0.7%    |
| Focal-systems.Corp         | 2         | 0.7%    |
| Samsung Electronics        | 1         | 0.35%   |
| Microsoft                  | 1         | 0.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 34        | 11.89%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 22        | 7.69%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 17        | 5.94%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 4.55%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 4.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 4.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 12        | 4.2%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 3.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 3.15%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 3.15%   |
| Elan ELAN:Fingerprint                                                      | 9         | 3.15%   |
| Validity Sensors VFS491                                                    | 8         | 2.8%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.8%    |
| Synaptics UWP WBDI                                                         | 7         | 2.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 2.1%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 2.1%    |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 2.1%    |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.75%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 1.75%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.75%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 1.75%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.4%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.4%    |
| Synaptics WBDI                                                             | 4         | 1.4%    |
| Synaptics  WBDI                                                            | 4         | 1.4%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.4%    |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 1.4%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.4%    |
| Elan ELAN:ARM-M4                                                           | 4         | 1.4%    |
| AuthenTec AES2810                                                          | 4         | 1.4%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 1.05%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.7%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.7%    |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.7%    |
| STMicroelectronics Fingerprint Reader                                      | 2         | 0.7%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.7%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 0.7%    |
| AuthenTec AES1600                                                          | 2         | 0.7%    |
| Synaptics UWP WBDI Device                                                  | 1         | 0.35%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 62        | 52.54%  |
| Alcor Micro                       | 28        | 23.73%  |
| Upek                              | 8         | 6.78%   |
| O2 Micro                          | 7         | 5.93%   |
| Lenovo                            | 6         | 5.08%   |
| VASCO Data Security International | 1         | 0.85%   |
| SCM Microsystems                  | 1         | 0.85%   |
| OmniKey                           | 1         | 0.85%   |
| Jing-Mold Enterprise              | 1         | 0.85%   |
| Gemalto (was Gemplus)             | 1         | 0.85%   |
| Feitian Technologies              | 1         | 0.85%   |
| Chicony Electronics               | 1         | 0.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 28        | 23.73%  |
| Broadcom BCM5880 Secure Applications Processor                               | 27        | 22.88%  |
| Broadcom 5880                                                                | 15        | 12.71%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 9.32%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 6.78%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 5.08%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 5.08%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 6         | 5.08%   |
| Broadcom 58200                                                               | 3         | 2.54%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.85%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.85%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.85%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.85%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard            | 1         | 0.85%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.85%   |
| Feitian Technologies SCR301                                                  | 1         | 0.85%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1915      | 68.96%  |
| 1     | 696       | 25.06%  |
| 2     | 145       | 5.22%   |
| 3     | 16        | 0.58%   |
| 4     | 3         | 0.11%   |
| 9     | 1         | 0.04%   |
| 7     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 283       | 27.19%  |
| Net/wireless             | 221       | 21.23%  |
| Graphics card            | 177       | 17%     |
| Multimedia controller    | 123       | 11.82%  |
| Chipcard                 | 112       | 10.76%  |
| Bluetooth                | 20        | 1.92%   |
| Storage                  | 18        | 1.73%   |
| Net/ethernet             | 18        | 1.73%   |
| Camera                   | 16        | 1.54%   |
| Sound                    | 15        | 1.44%   |
| Communication controller | 11        | 1.06%   |
| Unassigned class         | 8         | 0.77%   |
| Card reader              | 7         | 0.67%   |
| Network                  | 5         | 0.48%   |
| Storage/raid             | 3         | 0.29%   |
| Storage/ide              | 1         | 0.1%    |
| Storage/ata              | 1         | 0.1%    |
| Modem                    | 1         | 0.1%    |
| Flash memory             | 1         | 0.1%    |

