LMDE 5 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for LMDE 5.

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

Total: 236

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Samsung       | RV415/RV515                 | [ea50188d5c](https://linux-hardware.org/?probe=ea50188d5c) | Jan 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [5e5231a159](https://linux-hardware.org/?probe=5e5231a159) | Jan 31, 2023 |
| Samsung       | RV415/RV515                 | [c5999dc406](https://linux-hardware.org/?probe=c5999dc406) | Jan 29, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [a732875be3](https://linux-hardware.org/?probe=a732875be3) | Jan 29, 2023 |
| Acer          | Aspire 3810T                | [a7b93a7119](https://linux-hardware.org/?probe=a7b93a7119) | Jan 29, 2023 |
| Google        | Candy                       | [2b2368d61b](https://linux-hardware.org/?probe=2b2368d61b) | Jan 28, 2023 |
| Acer          | Aspire 3810T                | [c77f7df143](https://linux-hardware.org/?probe=c77f7df143) | Jan 27, 2023 |
| Kruger&Mat... | KM1406                      | [c944e8058f](https://linux-hardware.org/?probe=c944e8058f) | Jan 27, 2023 |
| Compaq        | 420                         | [9ed9e081c4](https://linux-hardware.org/?probe=9ed9e081c4) | Jan 24, 2023 |
| HP            | Laptop 15s-eq3xxx           | [b871955b27](https://linux-hardware.org/?probe=b871955b27) | Jan 23, 2023 |
| Toshiba       | Satellite L305              | [d1a0c1ddf7](https://linux-hardware.org/?probe=d1a0c1ddf7) | Jan 23, 2023 |
| Dell          | Precision 5520              | [f2b0c15a6d](https://linux-hardware.org/?probe=f2b0c15a6d) | Jan 22, 2023 |
| Dell          | Precision 5520              | [c202a2fa19](https://linux-hardware.org/?probe=c202a2fa19) | Jan 22, 2023 |
| Fujitsu       | M2010                       | [dec6151200](https://linux-hardware.org/?probe=dec6151200) | Jan 20, 2023 |
| Toshiba       | PORTEGE M780                | [cf65ef4cf0](https://linux-hardware.org/?probe=cf65ef4cf0) | Jan 20, 2023 |
| Google        | Candy                       | [f1609bed25](https://linux-hardware.org/?probe=f1609bed25) | Jan 16, 2023 |
| Toshiba       | PORTEGE Z30-B               | [4c5c663576](https://linux-hardware.org/?probe=4c5c663576) | Jan 14, 2023 |
| Lenovo        | B50-70 20384                | [0153a9926a](https://linux-hardware.org/?probe=0153a9926a) | Jan 13, 2023 |
| Lenovo        | B560                        | [e5a272b9c1](https://linux-hardware.org/?probe=e5a272b9c1) | Jan 13, 2023 |
| ASUSTek       | K54L                        | [5c67103146](https://linux-hardware.org/?probe=5c67103146) | Jan 09, 2023 |
| Fujitsu       | LIFEBOOK E736               | [96cf85d764](https://linux-hardware.org/?probe=96cf85d764) | Jan 08, 2023 |
| Dynabook      | Satellite Pro C50-G         | [978b828ce6](https://linux-hardware.org/?probe=978b828ce6) | Jan 08, 2023 |
| Chuwi         | GemiBook Pro                | [ed8c1ab25e](https://linux-hardware.org/?probe=ed8c1ab25e) | Jan 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [fa19ac7348](https://linux-hardware.org/?probe=fa19ac7348) | Jan 03, 2023 |
| Fujitsu       | LIFEBOOK S751               | [5fbed33610](https://linux-hardware.org/?probe=5fbed33610) | Jan 03, 2023 |
| Dell          | Vostro 1700                 | [66199c3f54](https://linux-hardware.org/?probe=66199c3f54) | Jan 02, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [fb967bb48d](https://linux-hardware.org/?probe=fb967bb48d) | Jan 01, 2023 |
| Google        | Ultima                      | [b389ad5a98](https://linux-hardware.org/?probe=b389ad5a98) | Dec 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | [9a2f55886f](https://linux-hardware.org/?probe=9a2f55886f) | Dec 25, 2022 |
| HP            | EliteBook 8440p             | [571afe8b70](https://linux-hardware.org/?probe=571afe8b70) | Dec 24, 2022 |
| Fujitsu       | LIFEBOOK S751               | [f3dc3c0121](https://linux-hardware.org/?probe=f3dc3c0121) | Dec 22, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [bc0e60b586](https://linux-hardware.org/?probe=bc0e60b586) | Dec 21, 2022 |
| TUXEDO        | N8xxEZ                      | [2e8ecb2ca4](https://linux-hardware.org/?probe=2e8ecb2ca4) | Dec 20, 2022 |
| TUXEDO        | N8xxEZ                      | [1055ea57f9](https://linux-hardware.org/?probe=1055ea57f9) | Dec 20, 2022 |
| ASUSTek       | X550VC                      | [5d5f66f67a](https://linux-hardware.org/?probe=5d5f66f67a) | Dec 20, 2022 |
| Apple         | MacBookAir5,1               | [f80de6076d](https://linux-hardware.org/?probe=f80de6076d) | Dec 18, 2022 |
| HP            | Notebook                    | [ef017285ee](https://linux-hardware.org/?probe=ef017285ee) | Dec 18, 2022 |
| Dell          | Latitude E5530 non-vPro     | [917150ffce](https://linux-hardware.org/?probe=917150ffce) | Dec 18, 2022 |
| Apple         | MacBookPro13,3              | [26a498297f](https://linux-hardware.org/?probe=26a498297f) | Dec 16, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [76e4dff90a](https://linux-hardware.org/?probe=76e4dff90a) | Dec 13, 2022 |
| HP            | Laptop 15s-fq2xxx           | [129c077e02](https://linux-hardware.org/?probe=129c077e02) | Dec 11, 2022 |
| Lenovo        | ThinkPad T520 4243W19       | [86064a54c0](https://linux-hardware.org/?probe=86064a54c0) | Dec 10, 2022 |
| Acer          | TravelMate 4070             | [8f9e4c0e26](https://linux-hardware.org/?probe=8f9e4c0e26) | Dec 10, 2022 |
| HP            | Madoo                       | [6a38e78ecf](https://linux-hardware.org/?probe=6a38e78ecf) | Dec 10, 2022 |
| HP            | 250 G8 Notebook PC          | [5a1593a360](https://linux-hardware.org/?probe=5a1593a360) | Dec 08, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [6e40fd6fd3](https://linux-hardware.org/?probe=6e40fd6fd3) | Dec 08, 2022 |
| HP            | ZBook 15 G2                 | [83117100d0](https://linux-hardware.org/?probe=83117100d0) | Dec 08, 2022 |
| Acer          | TravelMate 4070             | [ec589662a2](https://linux-hardware.org/?probe=ec589662a2) | Dec 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [7ef192d30d](https://linux-hardware.org/?probe=7ef192d30d) | Dec 06, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [bb589ef99d](https://linux-hardware.org/?probe=bb589ef99d) | Dec 04, 2022 |
| Acer          | Aspire E1-570G              | [b41442c5a1](https://linux-hardware.org/?probe=b41442c5a1) | Dec 01, 2022 |
| Apple         | MacBook6,1                  | [b8145a2349](https://linux-hardware.org/?probe=b8145a2349) | Dec 01, 2022 |
| Acer          | Aspire E1-570G              | [bbb8e289a9](https://linux-hardware.org/?probe=bbb8e289a9) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | [def1faf044](https://linux-hardware.org/?probe=def1faf044) | Nov 28, 2022 |
| HP            | Mini 110-1100               | [8f28854dfa](https://linux-hardware.org/?probe=8f28854dfa) | Nov 28, 2022 |
| HP            | Victus by Gaming Laptop ... | [e1dcd6d119](https://linux-hardware.org/?probe=e1dcd6d119) | Nov 28, 2022 |
| HP            | EliteBook 820 G3            | [3ca3320525](https://linux-hardware.org/?probe=3ca3320525) | Nov 24, 2022 |
| Kruger&Mat... | KM1406                      | [d639be7513](https://linux-hardware.org/?probe=d639be7513) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | [a7e0207e4b](https://linux-hardware.org/?probe=a7e0207e4b) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | [2bfa796e90](https://linux-hardware.org/?probe=2bfa796e90) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | [afcb386e71](https://linux-hardware.org/?probe=afcb386e71) | Nov 23, 2022 |
| Lenovo        | ThinkPad W510 43192PU       | [98fac29e02](https://linux-hardware.org/?probe=98fac29e02) | Nov 22, 2022 |
| Lenovo        | ThinkPad W510 43192PU       | [53882f751e](https://linux-hardware.org/?probe=53882f751e) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | [3f043b96c0](https://linux-hardware.org/?probe=3f043b96c0) | Nov 19, 2022 |
| Dell          | G15 5510                    | [5d9d96d71e](https://linux-hardware.org/?probe=5d9d96d71e) | Nov 16, 2022 |
| HP            | Laptop 15-dw3xxx            | [e656990178](https://linux-hardware.org/?probe=e656990178) | Nov 16, 2022 |
| HP            | Laptop 14-cf3xxx            | [21d31ce6b0](https://linux-hardware.org/?probe=21d31ce6b0) | Nov 15, 2022 |
| Sony          | SVF1532W4E                  | [33d278cd7a](https://linux-hardware.org/?probe=33d278cd7a) | Nov 12, 2022 |
| ASUSTek       | K54LY                       | [721020a0fe](https://linux-hardware.org/?probe=721020a0fe) | Nov 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [b9f262d40b](https://linux-hardware.org/?probe=b9f262d40b) | Nov 10, 2022 |
| HP            | ProBook 650 G4              | [2aec71897b](https://linux-hardware.org/?probe=2aec71897b) | Nov 08, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [2e0c6e37a4](https://linux-hardware.org/?probe=2e0c6e37a4) | Nov 07, 2022 |
| HP            | Unknown                     | [fe07901ad1](https://linux-hardware.org/?probe=fe07901ad1) | Nov 06, 2022 |
| HP            | Unknown                     | [495b046a6b](https://linux-hardware.org/?probe=495b046a6b) | Nov 06, 2022 |
| Toshiba       | Satellite L855D             | [8ac5a3b401](https://linux-hardware.org/?probe=8ac5a3b401) | Nov 03, 2022 |
| Lenovo        | V145-15AST 81MT             | [077d7d4379](https://linux-hardware.org/?probe=077d7d4379) | Nov 03, 2022 |
| HP            | Pavilion dv6                | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
| HP            | Laptop 15-dw3xxx            | [0c281b6b5e](https://linux-hardware.org/?probe=0c281b6b5e) | Oct 29, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [c6031ce122](https://linux-hardware.org/?probe=c6031ce122) | Oct 28, 2022 |
| Unknown       | Unknown                     | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| HP            | Laptop 14-cf3xxx            | [a782c95632](https://linux-hardware.org/?probe=a782c95632) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7bf16d5a25](https://linux-hardware.org/?probe=7bf16d5a25) | Oct 25, 2022 |
| ASUSTek       | X510UQR                     | [c03f0f4b6a](https://linux-hardware.org/?probe=c03f0f4b6a) | Oct 24, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [3b8452c3c6](https://linux-hardware.org/?probe=3b8452c3c6) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [a5d65724fa](https://linux-hardware.org/?probe=a5d65724fa) | Oct 21, 2022 |
| Dell          | XPS L701X                   | [53c5b7ea24](https://linux-hardware.org/?probe=53c5b7ea24) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | [09dcc1a805](https://linux-hardware.org/?probe=09dcc1a805) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | [ac86cf3035](https://linux-hardware.org/?probe=ac86cf3035) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| Sony          | SVF1532W4E                  | [e66750b690](https://linux-hardware.org/?probe=e66750b690) | Oct 18, 2022 |
| HP            | Laptop 14-cf3xxx            | [7664f462d0](https://linux-hardware.org/?probe=7664f462d0) | Oct 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [e31e511d7b](https://linux-hardware.org/?probe=e31e511d7b) | Oct 04, 2022 |
| ASUSTek       | K54LY                       | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| Unknown       | Unknown                     | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | Inspiron 5420               | [71f7e67ca7](https://linux-hardware.org/?probe=71f7e67ca7) | Oct 01, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [d277bf47ec](https://linux-hardware.org/?probe=d277bf47ec) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [fb7029173f](https://linux-hardware.org/?probe=fb7029173f) | Sep 25, 2022 |
| HP            | Laptop 14-cf3xxx            | [9386d6b529](https://linux-hardware.org/?probe=9386d6b529) | Sep 23, 2022 |
| HP            | Laptop 14-cf3xxx            | [3ba944192e](https://linux-hardware.org/?probe=3ba944192e) | Sep 22, 2022 |
| Medion        | P15648                      | [e3d7873a30](https://linux-hardware.org/?probe=e3d7873a30) | Sep 19, 2022 |
| HP            | EliteBook 850 G6            | [8b24c3dd3b](https://linux-hardware.org/?probe=8b24c3dd3b) | Sep 19, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| HP            | G72                         | [d00cd9a9bd](https://linux-hardware.org/?probe=d00cd9a9bd) | Sep 14, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [65ef8d235d](https://linux-hardware.org/?probe=65ef8d235d) | Sep 08, 2022 |
| Lenovo        | Yoga 2 11 20332             | [9b6635c1db](https://linux-hardware.org/?probe=9b6635c1db) | Sep 06, 2022 |
| Dell          | Latitude E6430              | [b8b0464d70](https://linux-hardware.org/?probe=b8b0464d70) | Sep 05, 2022 |
| Acer          | Aspire 5930                 | [db2b212059](https://linux-hardware.org/?probe=db2b212059) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | [98812c04d7](https://linux-hardware.org/?probe=98812c04d7) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | [6fe42dd16d](https://linux-hardware.org/?probe=6fe42dd16d) | Sep 03, 2022 |
| Lenovo        | G50-45 80E3                 | [8e05735fc7](https://linux-hardware.org/?probe=8e05735fc7) | Sep 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| Dell          | Latitude E6330              | [eb89774723](https://linux-hardware.org/?probe=eb89774723) | Aug 29, 2022 |
| Lenovo        | G500 20236                  | [da93b01660](https://linux-hardware.org/?probe=da93b01660) | Aug 22, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [8b1d8459e2](https://linux-hardware.org/?probe=8b1d8459e2) | Aug 20, 2022 |
| Microtech     | ebookPro                    | [b6c6859a02](https://linux-hardware.org/?probe=b6c6859a02) | Aug 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | [ee7cbda038](https://linux-hardware.org/?probe=ee7cbda038) | Aug 17, 2022 |
| Dell          | Vostro 5490                 | [3de3bd4b06](https://linux-hardware.org/?probe=3de3bd4b06) | Aug 15, 2022 |
| Dell          | Latitude E5540              | [7d8a8607f8](https://linux-hardware.org/?probe=7d8a8607f8) | Aug 13, 2022 |
| Acer          | Aspire 3820                 | [3b01398aeb](https://linux-hardware.org/?probe=3b01398aeb) | Aug 11, 2022 |
| HP            | Compaq Presario CQ71        | [68c8f97537](https://linux-hardware.org/?probe=68c8f97537) | Aug 11, 2022 |
| Wortmann      | TERRA_MOBILE_1713A          | [09f3eadbcf](https://linux-hardware.org/?probe=09f3eadbcf) | Aug 07, 2022 |
| Dynabook      | Satellite Pro C50-G         | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| Acer          | Aspire 3820                 | [5c3cec3fb9](https://linux-hardware.org/?probe=5c3cec3fb9) | Aug 03, 2022 |
| Acer          | Aspire 3820                 | [07f925d91c](https://linux-hardware.org/?probe=07f925d91c) | Aug 03, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| Framework     | Laptop                      | [426cf376b2](https://linux-hardware.org/?probe=426cf376b2) | Jul 30, 2022 |
| Dell          | Latitude E5540              | [67063fe669](https://linux-hardware.org/?probe=67063fe669) | Jul 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [21fc33de37](https://linux-hardware.org/?probe=21fc33de37) | Jul 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [0b664049a0](https://linux-hardware.org/?probe=0b664049a0) | Jul 28, 2022 |
| Microtech     | ebookPro                    | [12215b6984](https://linux-hardware.org/?probe=12215b6984) | Jul 27, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [47420083a3](https://linux-hardware.org/?probe=47420083a3) | Jul 23, 2022 |
| Acer          | Aspire A315-21              | [1754eeae39](https://linux-hardware.org/?probe=1754eeae39) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | [a05a04fae5](https://linux-hardware.org/?probe=a05a04fae5) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | [67c590c532](https://linux-hardware.org/?probe=67c590c532) | Jul 20, 2022 |
| Apple         | MacBookPro14,1              | [786f399d7a](https://linux-hardware.org/?probe=786f399d7a) | Jul 19, 2022 |
| Apple         | MacBookPro14,1              | [19d55ade50](https://linux-hardware.org/?probe=19d55ade50) | Jul 19, 2022 |
| HP            | Laptop 14-dk1xxx            | [cf03561efa](https://linux-hardware.org/?probe=cf03561efa) | Jul 17, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3d9f189ad0](https://linux-hardware.org/?probe=3d9f189ad0) | Jul 13, 2022 |
| Google        | Akemi                       | [d4a36d2743](https://linux-hardware.org/?probe=d4a36d2743) | Jul 13, 2022 |
| MSI           | GL73 8SE                    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [24cd72e0bf](https://linux-hardware.org/?probe=24cd72e0bf) | Jul 08, 2022 |
| Apple         | MacBookPro11,1              | [9be78f4466](https://linux-hardware.org/?probe=9be78f4466) | Jul 07, 2022 |
| AMI           | T3 MRD                      | [bf634565fd](https://linux-hardware.org/?probe=bf634565fd) | Jul 02, 2022 |
| Sony          | SVE1512G1RW                 | [cf5ff8285e](https://linux-hardware.org/?probe=cf5ff8285e) | Jul 02, 2022 |
| HP            | Pavilion 17                 | [1efb06e77e](https://linux-hardware.org/?probe=1efb06e77e) | Jul 01, 2022 |
| HP            | Compaq 15                   | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
| Framework     | Laptop                      | [61a6480a38](https://linux-hardware.org/?probe=61a6480a38) | Jun 30, 2022 |
| Dell          | Inspiron 5370               | [e848f3258c](https://linux-hardware.org/?probe=e848f3258c) | Jun 26, 2022 |
| Unknown       | Unknown                     | [a8b7e4a9fe](https://linux-hardware.org/?probe=a8b7e4a9fe) | Jun 26, 2022 |
| HP            | Laptop 15z-ef2xxx           | [f54df47fa0](https://linux-hardware.org/?probe=f54df47fa0) | Jun 25, 2022 |
| Dell          | Inspiron 3505               | [1eaa95f069](https://linux-hardware.org/?probe=1eaa95f069) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | [64e65ab80b](https://linux-hardware.org/?probe=64e65ab80b) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | [879d7a231f](https://linux-hardware.org/?probe=879d7a231f) | Jun 24, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | [0c96d2bc24](https://linux-hardware.org/?probe=0c96d2bc24) | Jun 24, 2022 |
| HP            | Laptop 15-bw0xx             | [a55d01829f](https://linux-hardware.org/?probe=a55d01829f) | Jun 23, 2022 |
| HP            | EliteBook 8730w             | [14135356d6](https://linux-hardware.org/?probe=14135356d6) | Jun 20, 2022 |
| MSI           | U180                        | [7aa374e07e](https://linux-hardware.org/?probe=7aa374e07e) | Jun 20, 2022 |
| Acer          | Aspire 5930                 | [348ec06fd0](https://linux-hardware.org/?probe=348ec06fd0) | Jun 18, 2022 |
| ASUSTek       | 1005P                       | [4bd178fe29](https://linux-hardware.org/?probe=4bd178fe29) | Jun 14, 2022 |
| Apple         | MacBookPro14,1              | [88294cb5aa](https://linux-hardware.org/?probe=88294cb5aa) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | [281724432e](https://linux-hardware.org/?probe=281724432e) | Jun 12, 2022 |
| Acer          | Aspire One 522              | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| HP            | 255 G5 Notebook PC          | [519a18864f](https://linux-hardware.org/?probe=519a18864f) | Jun 09, 2022 |
| Sony          | SVE1713Y1RB                 | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Lenovo        | Z50-70 20354                | [57582f68b6](https://linux-hardware.org/?probe=57582f68b6) | Jun 08, 2022 |
| Multilaser    | PC150                       | [ee0a35cc62](https://linux-hardware.org/?probe=ee0a35cc62) | Jun 08, 2022 |
| Lenovo        | Z50-70 20354                | [870233669c](https://linux-hardware.org/?probe=870233669c) | Jun 07, 2022 |
| Alienware     | 14                          | [7dabcbc673](https://linux-hardware.org/?probe=7dabcbc673) | Jun 07, 2022 |
| Acer          | Swift SF515-51T             | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [0e59a69b8d](https://linux-hardware.org/?probe=0e59a69b8d) | May 30, 2022 |
| HP            | Laptop 14-cf3xxx            | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| HP            | Laptop 14-df0xxx            | [94992083bc](https://linux-hardware.org/?probe=94992083bc) | May 24, 2022 |
| Acer          | Aspire One 522              | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | [8757941b52](https://linux-hardware.org/?probe=8757941b52) | May 17, 2022 |
| Acer          | Aspire V3-571G              | [91700e1cb8](https://linux-hardware.org/?probe=91700e1cb8) | May 16, 2022 |
| Dell          | XPS 13 9305                 | [e9310a7ede](https://linux-hardware.org/?probe=e9310a7ede) | May 15, 2022 |
| Dell          | XPS 13 9305                 | [3f8becd67d](https://linux-hardware.org/?probe=3f8becd67d) | May 15, 2022 |
| Dell          | Inspiron 5566               | [d01652f69f](https://linux-hardware.org/?probe=d01652f69f) | May 15, 2022 |
| Dell          | Inspiron 5559               | [4b0c466a88](https://linux-hardware.org/?probe=4b0c466a88) | May 15, 2022 |
| Howard Com... | R7X                         | [bc6d6a31eb](https://linux-hardware.org/?probe=bc6d6a31eb) | May 13, 2022 |
| HP            | Notebook                    | [200c1dabff](https://linux-hardware.org/?probe=200c1dabff) | May 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [0d64940271](https://linux-hardware.org/?probe=0d64940271) | May 09, 2022 |
| HP            | ENVY 17                     | [a503de2c1f](https://linux-hardware.org/?probe=a503de2c1f) | May 08, 2022 |
| Apple         | MacBookAir7,2               | [54815db142](https://linux-hardware.org/?probe=54815db142) | May 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | [57e085245c](https://linux-hardware.org/?probe=57e085245c) | May 07, 2022 |
| Philco        | 10D                         | [d2f71d99cd](https://linux-hardware.org/?probe=d2f71d99cd) | May 05, 2022 |
| Philco        | 10D                         | [9882f4ca80](https://linux-hardware.org/?probe=9882f4ca80) | May 05, 2022 |
| Acer          | Aspire E1-532               | [a7305e2070](https://linux-hardware.org/?probe=a7305e2070) | May 04, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Toshiba       | Satellite M55               | [9d5733c6fc](https://linux-hardware.org/?probe=9d5733c6fc) | May 02, 2022 |
| HP            | Presario C500 (GF581UA#A... | [0e01914db4](https://linux-hardware.org/?probe=0e01914db4) | Apr 30, 2022 |
| HP            | EliteBook 840 G1            | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| Acer          | AOD270                      | [d0fae524f9](https://linux-hardware.org/?probe=d0fae524f9) | Apr 29, 2022 |
| Acer          | AOD270                      | [44d897bc15](https://linux-hardware.org/?probe=44d897bc15) | Apr 29, 2022 |
| Acer          | Aspire E5-553G              | [00a648bda6](https://linux-hardware.org/?probe=00a648bda6) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | [4646f6cd23](https://linux-hardware.org/?probe=4646f6cd23) | Apr 28, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [ff8e46a260](https://linux-hardware.org/?probe=ff8e46a260) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [0a6534997e](https://linux-hardware.org/?probe=0a6534997e) | Apr 27, 2022 |
| Apple         | MacBookPro14,1              | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| Dixonsxp      | Unknown                     | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| Toshiba       | Satellite L455              | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| Dell          | 0X574R                      | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| HP            | 14                          | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Dell          | Latitude 3410               | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| ASUSTek       | N61Jv                       | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Acer          | AOA110                      | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| Howard Com... | R7X                         | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Howard Com... | R7X                         | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | [613d6e7d3c](https://linux-hardware.org/?probe=613d6e7d3c) | Apr 07, 2022 |
| Dell          | Latitude 5511               | [2cb0a3e451](https://linux-hardware.org/?probe=2cb0a3e451) | Apr 06, 2022 |
| Dell          | Precision 7520              | [7404842400](https://linux-hardware.org/?probe=7404842400) | Apr 05, 2022 |
| LincPlus      | LINNCPLUS P1                | [22406313dc](https://linux-hardware.org/?probe=22406313dc) | Apr 02, 2022 |
| Toshiba       | Satellite L455              | [699e7d272d](https://linux-hardware.org/?probe=699e7d272d) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| HP            | ProBook 6570b               | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Packard Be... | DOT S                       | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| Dell          | Latitude E6400              | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Toshiba       | Satellite L455              | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.10.0-19-amd64        | 29        | 15.59%  |
| 5.10.0-12-amd64        | 23        | 12.37%  |
| 5.10.0-14-amd64        | 20        | 10.75%  |
| 5.10.0-20-amd64        | 17        | 9.14%   |
| 5.10.0-15-amd64        | 16        | 8.6%    |
| 5.10.0-18-amd64        | 14        | 7.53%   |
| 5.10.0-13-amd64        | 14        | 7.53%   |
| 5.10.0-16-amd64        | 11        | 5.91%   |
| 5.10.0-17-amd64        | 9         | 4.84%   |
| 5.10.0-21-amd64        | 6         | 3.23%   |
| 5.10.0-13-686          | 5         | 2.69%   |
| 5.18.0-0.bpo.1-amd64   | 4         | 2.15%   |
| 5.16.0-0.bpo.4-amd64   | 3         | 1.61%   |
| 5.10.0-12-686          | 2         | 1.08%   |
| 5.19.10-xanmod1        | 1         | 0.54%   |
| 5.19.0-0.deb11.2-amd64 | 1         | 0.54%   |
| 5.18.0-4-amd64         | 1         | 0.54%   |
| 5.18.0-3-amd64         | 1         | 0.54%   |
| 5.16.0-0.bpo.3-amd64   | 1         | 0.54%   |
| 5.15.78-xanmod1        | 1         | 0.54%   |
| 5.15.70-xanmod1        | 1         | 0.54%   |
| 5.15.0-0.bpo.3-amd64   | 1         | 0.54%   |
| 5.10.0-20-686          | 1         | 0.54%   |
| 5.10.0-19-686          | 1         | 0.54%   |
| 5.10.0-17-686          | 1         | 0.54%   |
| 5.10.0-14-686          | 1         | 0.54%   |
| 4.19.0-23-amd64        | 1         | 0.54%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 160       | 91.43%  |
| 5.18.0  | 6         | 3.43%   |
| 5.16.0  | 3         | 1.71%   |
| 5.19.10 | 1         | 0.57%   |
| 5.19.0  | 1         | 0.57%   |
| 5.15.78 | 1         | 0.57%   |
| 5.15.70 | 1         | 0.57%   |
| 5.15.0  | 1         | 0.57%   |
| 4.19.0  | 1         | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 160       | 91.95%  |
| 5.18    | 6         | 3.45%   |
| 5.16    | 3         | 1.72%   |
| 5.19    | 2         | 1.15%   |
| 5.15    | 2         | 1.15%   |
| 4.19    | 1         | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 160       | 93.57%  |
| i686   | 11        | 6.43%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 152       | 88.37%  |
| Cinnamon   | 15        | 8.72%   |
| MATE       | 2         | 1.16%   |
| XFCE       | 1         | 0.58%   |
| awesome    | 1         | 0.58%   |
| Unknown    | 1         | 0.58%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 171       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 99        | 57.23%  |
| LightDM | 74        | 42.77%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 56        | 32.56%  |
| de_DE | 27        | 15.7%   |
| ru_RU | 16        | 9.3%    |
| pt_BR | 11        | 6.4%    |
| en_GB | 10        | 5.81%   |
| fr_FR | 8         | 4.65%   |
| it_IT | 6         | 3.49%   |
| es_ES | 5         | 2.91%   |
| pl_PL | 4         | 2.33%   |
| es_MX | 3         | 1.74%   |
| tr_TR | 2         | 1.16%   |
| ko_KR | 2         | 1.16%   |
| es_BO | 2         | 1.16%   |
| en_NZ | 2         | 1.16%   |
| en_IE | 2         | 1.16%   |
| da_DK | 2         | 1.16%   |
| pt_PT | 1         | 0.58%   |
| nn_NO | 1         | 0.58%   |
| nl_AW | 1         | 0.58%   |
| hu_HU | 1         | 0.58%   |
| fr_BE | 1         | 0.58%   |
| es_VE | 1         | 0.58%   |
| es_PE | 1         | 0.58%   |
| es_EC | 1         | 0.58%   |
| es_CR | 1         | 0.58%   |
| en_IN | 1         | 0.58%   |
| en_CA | 1         | 0.58%   |
| el_GR | 1         | 0.58%   |
| de_CH | 1         | 0.58%   |
| cs_CZ | 1         | 0.58%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 111       | 64.53%  |
| BIOS | 61        | 35.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 158       | 92.4%   |
| Overlay | 5         | 2.92%   |
| Btrfs   | 4         | 2.34%   |
| Xfs     | 2         | 1.17%   |
| Tmpfs   | 2         | 1.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 98        | 56.65%  |
| GPT     | 52        | 30.06%  |
| MBR     | 23        | 13.29%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 158       | 91.86%  |
| Yes       | 14        | 8.14%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 152       | 88.37%  |
| Yes       | 20        | 11.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 41        | 23.98%  |
| Lenovo              | 32        | 18.71%  |
| Dell                | 24        | 14.04%  |
| Acer                | 16        | 9.36%   |
| ASUSTek Computer    | 13        | 7.6%    |
| Apple               | 7         | 4.09%   |
| Toshiba             | 6         | 3.51%   |
| Sony                | 3         | 1.75%   |
| Google              | 3         | 1.75%   |
| Fujitsu             | 3         | 1.75%   |
| Samsung Electronics | 2         | 1.17%   |
| MSI                 | 2         | 1.17%   |
| Medion              | 2         | 1.17%   |
| Unknown             | 2         | 1.17%   |
| Wortmann AG         | 1         | 0.58%   |
| TUXEDO              | 1         | 0.58%   |
| Philco              | 1         | 0.58%   |
| Packard Bell        | 1         | 0.58%   |
| Multilaser          | 1         | 0.58%   |
| Microtech           | 1         | 0.58%   |
| LincPlus            | 1         | 0.58%   |
| Kruger&Matz         | 1         | 0.58%   |
| Howard Computers    | 1         | 0.58%   |
| Framework           | 1         | 0.58%   |
| Dynabook            | 1         | 0.58%   |
| Dixonsxp            | 1         | 0.58%   |
| Compaq              | 1         | 0.58%   |
| AMI                 | 1         | 0.58%   |
| Alienware           | 1         | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 4         | 2.34%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 2         | 1.17%   |
| Lenovo IdeaPad 3 15ADA05 81W1         | 2         | 1.17%   |
| Lenovo G500 20236                     | 2         | 1.17%   |
| HP Notebook                           | 2         | 1.17%   |
| HP Laptop 15z-ef2xxx                  | 2         | 1.17%   |
| HP Laptop 15-dw3xxx                   | 2         | 1.17%   |
| Dell Latitude E6400                   | 2         | 1.17%   |
| Dell Latitude E5540                   | 2         | 1.17%   |
| Acer Aspire E1-570G                   | 2         | 1.17%   |
| Acer Aspire 5930                      | 2         | 1.17%   |
| Wortmann AG TERRA_MOBILE_1713A        | 1         | 0.58%   |
| TUXEDO N8xxEZ                         | 1         | 0.58%   |
| Toshiba Satellite M55                 | 1         | 0.58%   |
| Toshiba Satellite L855D               | 1         | 0.58%   |
| Toshiba Satellite L455                | 1         | 0.58%   |
| Toshiba Satellite L305                | 1         | 0.58%   |
| Toshiba PORTEGE Z30-B                 | 1         | 0.58%   |
| Toshiba PORTEGE M780                  | 1         | 0.58%   |
| Sony SVF1532W4E                       | 1         | 0.58%   |
| Sony SVE1713Y1RB                      | 1         | 0.58%   |
| Sony SVE1512G1RW                      | 1         | 0.58%   |
| Samsung RV415/RV515                   | 1         | 0.58%   |
| Samsung 355V4C/356V4C/3445VC/3545VC   | 1         | 0.58%   |
| Philco 10D                            | 1         | 0.58%   |
| Packard Bell DOT S                    | 1         | 0.58%   |
| Multilaser PC150                      | 1         | 0.58%   |
| MSI U180                              | 1         | 0.58%   |
| MSI GL73 8SE                          | 1         | 0.58%   |
| Microtech ebookPro                    | 1         | 0.58%   |
| Medion P15648                         | 1         | 0.58%   |
| Medion E6220                          | 1         | 0.58%   |
| LincPlus LINNCPLUS P1                 | 1         | 0.58%   |
| Lenovo Z50-70 20354                   | 1         | 0.58%   |
| Lenovo Yoga 2 11 20332                | 1         | 0.58%   |
| Lenovo V145-15AST 81MT                | 1         | 0.58%   |
| Lenovo ThinkPad X270 W10DG 20K5S3HG00 | 1         | 0.58%   |
| Lenovo ThinkPad W541 20EGS24J00       | 1         | 0.58%   |
| Lenovo ThinkPad W510 43192PU          | 1         | 0.58%   |
| Lenovo ThinkPad T61 7661A16           | 1         | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Acer Aspire        | 13        | 7.6%    |
| Lenovo ThinkPad    | 11        | 6.43%   |
| HP Laptop          | 11        | 6.43%   |
| Lenovo IdeaPad     | 10        | 5.85%   |
| Dell Latitude      | 9         | 5.26%   |
| HP EliteBook       | 6         | 3.51%   |
| Dell Inspiron      | 6         | 3.51%   |
| ASUS VivoBook      | 5         | 2.92%   |
| Toshiba Satellite  | 4         | 2.34%   |
| Unknown            | 4         | 2.34%   |
| HP ProBook         | 3         | 1.75%   |
| HP Pavilion        | 3         | 1.75%   |
| Dell Vostro        | 3         | 1.75%   |
| Dell Precision     | 3         | 1.75%   |
| Toshiba PORTEGE    | 2         | 1.17%   |
| Lenovo Legion      | 2         | 1.17%   |
| Lenovo G500        | 2         | 1.17%   |
| HP ZBook           | 2         | 1.17%   |
| HP Notebook        | 2         | 1.17%   |
| HP Compaq          | 2         | 1.17%   |
| HP 255             | 2         | 1.17%   |
| Fujitsu LIFEBOOK   | 2         | 1.17%   |
| Dell XPS           | 2         | 1.17%   |
| ASUS ROG           | 2         | 1.17%   |
| Wortmann AG TERRA  | 1         | 0.58%   |
| TUXEDO N8xxEZ      | 1         | 0.58%   |
| Sony SVF1532W4E    | 1         | 0.58%   |
| Sony SVE1713Y1RB   | 1         | 0.58%   |
| Sony SVE1512G1RW   | 1         | 0.58%   |
| Samsung RV415      | 1         | 0.58%   |
| Samsung 355V4C     | 1         | 0.58%   |
| Philco 10D         | 1         | 0.58%   |
| Packard Bell DOT   | 1         | 0.58%   |
| Multilaser PC150   | 1         | 0.58%   |
| MSI U180           | 1         | 0.58%   |
| MSI GL73           | 1         | 0.58%   |
| Microtech ebookPro | 1         | 0.58%   |
| Medion P15648      | 1         | 0.58%   |
| Medion E6220       | 1         | 0.58%   |
| LincPlus LINNCPLUS | 1         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 24        | 14.04%  |
| 2020 | 16        | 9.36%   |
| 2013 | 14        | 8.19%   |
| 2012 | 13        | 7.6%    |
| 2010 | 12        | 7.02%   |
| 2019 | 11        | 6.43%   |
| 2017 | 11        | 6.43%   |
| 2018 | 10        | 5.85%   |
| 2016 | 9         | 5.26%   |
| 2015 | 9         | 5.26%   |
| 2009 | 8         | 4.68%   |
| 2022 | 7         | 4.09%   |
| 2014 | 7         | 4.09%   |
| 2008 | 7         | 4.09%   |
| 2011 | 6         | 3.51%   |
| 2007 | 5         | 2.92%   |
| 2006 | 2         | 1.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 171       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 153       | 88.95%  |
| Enabled  | 19        | 11.05%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 167       | 97.66%  |
| Yes  | 4         | 2.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 51        | 29.82%  |
| 3.01-4.0    | 39        | 22.81%  |
| 8.01-16.0   | 28        | 16.37%  |
| 16.01-24.0  | 26        | 15.2%   |
| 1.01-2.0    | 11        | 6.43%   |
| 2.01-3.0    | 7         | 4.09%   |
| 32.01-64.0  | 6         | 3.51%   |
| 64.01-256.0 | 3         | 1.75%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 84        | 46.41%  |
| 2.01-3.0   | 55        | 30.39%  |
| 3.01-4.0   | 17        | 9.39%   |
| 4.01-8.0   | 12        | 6.63%   |
| 0.51-1.0   | 11        | 6.08%   |
| 32.01-64.0 | 1         | 0.55%   |
| 8.01-16.0  | 1         | 0.55%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 129       | 74.14%  |
| 2      | 37        | 21.26%  |
| 3      | 7         | 4.02%   |
| 4      | 1         | 0.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 116       | 67.84%  |
| Yes       | 55        | 32.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 133       | 77.78%  |
| No        | 38        | 22.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 169       | 98.83%  |
| No        | 2         | 1.17%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 70.35%  |
| No        | 51        | 29.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 29        | 16.76%  |
| USA         | 27        | 15.61%  |
| Russia      | 18        | 10.4%   |
| Brazil      | 12        | 6.94%   |
| Italy       | 10        | 5.78%   |
| UK          | 8         | 4.62%   |
| France      | 8         | 4.62%   |
| Poland      | 6         | 3.47%   |
| Spain       | 5         | 2.89%   |
| Mexico      | 3         | 1.73%   |
| Canada      | 3         | 1.73%   |
| Belgium     | 3         | 1.73%   |
| Turkey      | 2         | 1.16%   |
| South Korea | 2         | 1.16%   |
| Romania     | 2         | 1.16%   |
| Portugal    | 2         | 1.16%   |
| New Zealand | 2         | 1.16%   |
| Hungary     | 2         | 1.16%   |
| Greece      | 2         | 1.16%   |
| Denmark     | 2         | 1.16%   |
| Chile       | 2         | 1.16%   |
| Bolivia     | 2         | 1.16%   |
| Belarus     | 2         | 1.16%   |
| Vietnam     | 1         | 0.58%   |
| Venezuela   | 1         | 0.58%   |
| Sweden      | 1         | 0.58%   |
| Slovenia    | 1         | 0.58%   |
| Serbia      | 1         | 0.58%   |
| Peru        | 1         | 0.58%   |
| Paraguay    | 1         | 0.58%   |
| Norway      | 1         | 0.58%   |
| Malaysia    | 1         | 0.58%   |
| Lithuania   | 1         | 0.58%   |
| Kenya       | 1         | 0.58%   |
| Kazakhstan  | 1         | 0.58%   |
| Ireland     | 1         | 0.58%   |
| India       | 1         | 0.58%   |
| Finland     | 1         | 0.58%   |
| Ecuador     | 1         | 0.58%   |
| Czechia     | 1         | 0.58%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Moscow               | 6         | 3.43%   |
| St Petersburg        | 3         | 1.71%   |
| Berlin               | 3         | 1.71%   |
| San Jose             | 2         | 1.14%   |
| Rome                 | 2         | 1.14%   |
| Oruro                | 2         | 1.14%   |
| Neasden              | 2         | 1.14%   |
| Munich               | 2         | 1.14%   |
| Krakow               | 2         | 1.14%   |
| Freiburg im Breisgau | 2         | 1.14%   |
| Auckland             | 2         | 1.14%   |
| Zaragoza             | 1         | 0.57%   |
| Wroclaw              | 1         | 0.57%   |
| Weimar               | 1         | 0.57%   |
| Voronezh             | 1         | 0.57%   |
| Volos                | 1         | 0.57%   |
| Vilshofen            | 1         | 0.57%   |
| Vilnius              | 1         | 0.57%   |
| Viggianello          | 1         | 0.57%   |
| Viet Tri             | 1         | 0.57%   |
| Veurne               | 1         | 0.57%   |
| Vaslui               | 1         | 0.57%   |
| Valsoyfjord          | 1         | 0.57%   |
| Uiwang               | 1         | 0.57%   |
| Turku                | 1         | 0.57%   |
| Tula                 | 1         | 0.57%   |
| Troisdorf            | 1         | 0.57%   |
| Toulouse             | 1         | 0.57%   |
| Toulon               | 1         | 0.57%   |
| Toronto              | 1         | 0.57%   |
| Tipton               | 1         | 0.57%   |
| Spearfish            | 1         | 0.57%   |
| Smolensk             | 1         | 0.57%   |
| Shrewsbury           | 1         | 0.57%   |
| Scarborough          | 1         | 0.57%   |
| Saratov              | 1         | 0.57%   |
| Sao Paulo            | 1         | 0.57%   |
| Santiago             | 1         | 0.57%   |
| Salvador             | 1         | 0.57%   |
| Salem                | 1         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 26        | 28     | 11.93%  |
| Samsung Electronics            | 24        | 26     | 11.01%  |
| Seagate                        | 23        | 27     | 10.55%  |
| Unknown                        | 17        | 25     | 7.8%    |
| Sandisk                        | 16        | 20     | 7.34%   |
| Kingston                       | 10        | 10     | 4.59%   |
| Toshiba                        | 9         | 10     | 4.13%   |
| SK hynix                       | 7         | 7      | 3.21%   |
| Intel                          | 7         | 7      | 3.21%   |
| Hitachi                        | 7         | 7      | 3.21%   |
| Micron Technology              | 5         | 5      | 2.29%   |
| Crucial                        | 5         | 6      | 2.29%   |
| Apple                          | 5         | 10     | 2.29%   |
| A-DATA Technology              | 5         | 6      | 2.29%   |
| PNY                            | 4         | 5      | 1.83%   |
| HGST                           | 4         | 5      | 1.83%   |
| China                          | 4         | 5      | 1.83%   |
| Patriot                        | 3         | 3      | 1.38%   |
| Team                           | 2         | 2      | 0.92%   |
| Phison                         | 2         | 2      | 0.92%   |
| KIOXIA                         | 2         | 5      | 0.92%   |
| KingSpec                       | 2         | 2      | 0.92%   |
| Fujitsu                        | 2         | 2      | 0.92%   |
| Unknown                        | 2         | 2      | 0.92%   |
| Union Memory                   | 1         | 1      | 0.46%   |
| UMIS                           | 1         | 1      | 0.46%   |
| Transcend                      | 1         | 1      | 0.46%   |
| SSD PHIS                       | 1         | 1      | 0.46%   |
| Solid State Storage Technology | 1         | 1      | 0.46%   |
| ShiJi                          | 1         | 1      | 0.46%   |
| SABRENT                        | 1         | 1      | 0.46%   |
| Oyen                           | 1         | 1      | 0.46%   |
| ORICO                          | 1         | 1      | 0.46%   |
| Microtech                      | 1         | 2      | 0.46%   |
| Micron/Crucial Technology      | 1         | 2      | 0.46%   |
| MAXSUN                         | 1         | 1      | 0.46%   |
| LITEON                         | 1         | 1      | 0.46%   |
| Intenso                        | 1         | 1      | 0.46%   |
| Initio                         | 1         | 1      | 0.46%   |
| HXY                            | 1         | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 7         | 3.11%   |
| Unknown SD/MMC/MS PRO 2GB            | 3         | 1.33%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 1.33%   |
| SanDisk NVMe SSD Drive 256GB         | 3         | 1.33%   |
| Kingston SA400S37480G 480GB SSD      | 3         | 1.33%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 0.89%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 2         | 0.89%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB | 2         | 0.89%   |
| Unknown SC128  128GB                 | 2         | 0.89%   |
| Unknown MMC Card  64GB               | 2         | 0.89%   |
| Unknown MMC Card  32GB               | 2         | 0.89%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.89%   |
| Seagate ST9250315AS 250GB            | 2         | 0.89%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 2         | 0.89%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB   | 2         | 0.89%   |
| Samsung SSD 980 1TB                  | 2         | 0.89%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.89%   |
| Samsung PM991a NVMe 512GB            | 2         | 0.89%   |
| Patriot Burst 240GB SSD              | 2         | 0.89%   |
| Micron NVMe SSD Drive 512GB          | 2         | 0.89%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 0.89%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.89%   |
| Crucial CT1000BX500SSD1 1TB          | 2         | 0.89%   |
| Apple SSD SD0128F 121GB              | 2         | 0.89%   |
| A-DATA ED600 1TB SSD                 | 2         | 0.89%   |
| Unknown                              | 2         | 0.89%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.44%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1         | 0.44%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.44%   |
| WDC WDBNCE5000PNC 500GB SSD          | 1         | 0.44%   |
| WDC WD7500BPVT-22HXZT3 752GB         | 1         | 0.44%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.44%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.44%   |
| WDC WD5000BPVX-00JC3T0 500GB         | 1         | 0.44%   |
| WDC WD5000BEVT-22A0RT0 500GB         | 1         | 0.44%   |
| WDC WD3200BEVT-60ZCT0 320GB          | 1         | 0.44%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.44%   |
| WDC WD30 EFRX-68EUZN0 3TB            | 1         | 0.44%   |
| WDC WD20SPZX-22UA7T0 2TB             | 1         | 0.44%   |
| WDC WD1600BEVT-60ZCT1 160GB          | 1         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 27     | 35.94%  |
| WDC                 | 16        | 17     | 25%     |
| Hitachi             | 7         | 7      | 10.94%  |
| Toshiba             | 6         | 7      | 9.38%   |
| HGST                | 4         | 5      | 6.25%   |
| Unknown             | 3         | 3      | 4.69%   |
| Fujitsu             | 2         | 2      | 3.13%   |
| Samsung Electronics | 1         | 1      | 1.56%   |
| SABRENT             | 1         | 1      | 1.56%   |
| Intenso             | 1         | 1      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 12     | 12.5%   |
| Kingston            | 9         | 9      | 11.25%  |
| SanDisk             | 6         | 7      | 7.5%    |
| Crucial             | 5         | 6      | 6.25%   |
| A-DATA Technology   | 5         | 6      | 6.25%   |
| PNY                 | 4         | 5      | 5%      |
| Intel               | 4         | 4      | 5%      |
| China               | 4         | 5      | 5%      |
| Apple               | 4         | 4      | 5%      |
| WDC                 | 3         | 3      | 3.75%   |
| Patriot             | 3         | 3      | 3.75%   |
| Toshiba             | 2         | 2      | 2.5%    |
| Team                | 2         | 2      | 2.5%    |
| KingSpec            | 2         | 2      | 2.5%    |
| Unknown             | 2         | 2      | 2.5%    |
| Transcend           | 1         | 1      | 1.25%   |
| SSD PHIS            | 1         | 1      | 1.25%   |
| ORICO               | 1         | 1      | 1.25%   |
| Microtech           | 1         | 2      | 1.25%   |
| Micron Technology   | 1         | 1      | 1.25%   |
| LITEON              | 1         | 1      | 1.25%   |
| Initio              | 1         | 1      | 1.25%   |
| HXY                 | 1         | 1      | 1.25%   |
| Gigabyte Technology | 1         | 2      | 1.25%   |
| FORESEE             | 1         | 2      | 1.25%   |
| Emtec               | 1         | 1      | 1.25%   |
| Corsair             | 1         | 1      | 1.25%   |
| BHT                 | 1         | 2      | 1.25%   |
| ASMT                | 1         | 1      | 1.25%   |
| Acer                | 1         | 1      | 1.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 71        | 91     | 35.15%  |
| HDD     | 61        | 71     | 30.2%   |
| NVMe    | 50        | 67     | 24.75%  |
| MMC     | 14        | 21     | 6.93%   |
| Unknown | 6         | 7      | 2.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 118       | 154    | 61.46%  |
| NVMe | 50        | 67     | 26.04%  |
| MMC  | 14        | 21     | 7.29%   |
| SAS  | 10        | 15     | 5.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 91        | 113    | 70.54%  |
| 0.51-1.0   | 32        | 43     | 24.81%  |
| 1.01-2.0   | 2         | 2      | 1.55%   |
| 4.01-10.0  | 2         | 2      | 1.55%   |
| 3.01-4.0   | 1         | 1      | 0.78%   |
| 2.01-3.0   | 1         | 1      | 0.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 63        | 36.21%  |
| 251-500        | 42        | 24.14%  |
| 501-1000       | 24        | 13.79%  |
| 1001-2000      | 11        | 6.32%   |
| 51-100         | 11        | 6.32%   |
| 21-50          | 10        | 5.75%   |
| 1-20           | 6         | 3.45%   |
| 2001-3000      | 5         | 2.87%   |
| More than 3000 | 2         | 1.15%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 86        | 47.25%  |
| 21-50     | 37        | 20.33%  |
| 101-250   | 20        | 10.99%  |
| 51-100    | 20        | 10.99%  |
| 501-1000  | 11        | 6.04%   |
| 251-500   | 7         | 3.85%   |
| 2001-3000 | 1         | 0.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 6.67%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 6.67%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 6.67%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 6.67%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 6.67%   |
| Seagate ST500LT032-1E9142 500GB       | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 850 EVO 500GB | 1         | 1      | 6.67%   |
| Samsung Electronics HM160HC 160GB     | 1         | 1      | 6.67%   |
| Phison ES 512GB                       | 1         | 1      | 6.67%   |
| Intel SSDSCKKF256G8 SATA 256GB        | 1         | 1      | 6.67%   |
| Intel SSDSC2CT240A3 240GB             | 1         | 1      | 6.67%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 6.67%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 28.57%  |
| Seagate             | 2         | 2      | 14.29%  |
| Intel               | 2         | 2      | 14.29%  |
| WDC                 | 1         | 2      | 7.14%   |
| Toshiba             | 1         | 1      | 7.14%   |
| SK hynix            | 1         | 1      | 7.14%   |
| Phison              | 1         | 1      | 7.14%   |
| Hitachi             | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 33.33%  |
| WDC                 | 1         | 2      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| Hitachi             | 1         | 1      | 16.67%  |
| HGST                | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 7      | 42.86%  |
| SSD  | 5         | 5      | 35.71%  |
| NVMe | 3         | 3      | 21.43%  |

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
| Detected | 111       | 161    | 58.42%  |
| Works    | 65        | 81     | 34.21%  |
| Malfunc  | 14        | 15     | 7.37%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 118       | 59.3%   |
| AMD                            | 26        | 13.07%  |
| SanDisk                        | 14        | 7.04%   |
| Samsung Electronics            | 14        | 7.04%   |
| SK hynix                       | 7         | 3.52%   |
| Micron Technology              | 4         | 2.01%   |
| KIOXIA                         | 3         | 1.51%   |
| Union Memory (Shenzhen)        | 2         | 1.01%   |
| Phison Electronics             | 2         | 1.01%   |
| Marvell Technology Group       | 2         | 1.01%   |
| Toshiba America Info Systems   | 1         | 0.5%    |
| Solid State Storage Technology | 1         | 0.5%    |
| Nvidia                         | 1         | 0.5%    |
| Micron/Crucial Technology      | 1         | 0.5%    |
| Kingston Technology Company    | 1         | 0.5%    |
| Apple                          | 1         | 0.5%    |
| ADATA Technology               | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 22        | 10.19%  |
| Intel Volume Management Device NVMe RAID Controller                              | 12        | 5.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 5.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 12        | 5.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 5.09%   |
| Intel Tiger Lake-LP SATA Controller                                              | 8         | 3.7%    |
| SanDisk Non-Volatile memory controller                                           | 7         | 3.24%   |
| Samsung NVMe SSD Controller 980                                                  | 7         | 3.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 3.24%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 3.24%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 6         | 2.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 2.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 1.85%   |
| Micron Non-Volatile memory controller                                            | 4         | 1.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 1.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 4         | 1.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 1.85%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 3         | 1.39%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 3         | 1.39%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.39%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 1.39%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.39%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.93%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.93%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 2         | 0.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 0.93%   |
| Intel SSD 660P Series                                                            | 2         | 0.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 0.93%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.46%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 x4 NVMe SSD Controller                    | 1         | 0.46%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.46%   |
| Solid State Storage Non-Volatile memory controller                               | 1         | 0.46%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 122       | 58.1%   |
| NVMe | 51        | 24.29%  |
| RAID | 24        | 11.43%  |
| IDE  | 13        | 6.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 135       | 78.95%  |
| AMD    | 36        | 21.05%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 8         | 4.68%   |
| Intel Core i5-3230M CPU @ 2.60GHz            | 6         | 3.51%   |
| Intel Atom CPU N2600 @ 1.60GHz               | 4         | 2.34%   |
| AMD Ryzen 5 5500U with Radeon Graphics       | 4         | 2.34%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 3         | 1.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz      | 3         | 1.75%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz      | 3         | 1.75%   |
| Intel Pentium M processor 1.73GHz            | 2         | 1.17%   |
| Intel Pentium CPU P6000 @ 1.87GHz            | 2         | 1.17%   |
| Intel Core i7-8750H CPU @ 2.20GHz            | 2         | 1.17%   |
| Intel Core i7-7500U CPU @ 2.70GHz            | 2         | 1.17%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz           | 2         | 1.17%   |
| Intel Core i7-3612QM CPU @ 2.10GHz           | 2         | 1.17%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz            | 2         | 1.17%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 2         | 1.17%   |
| Intel Core i3-4010U CPU @ 1.70GHz            | 2         | 1.17%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz           | 2         | 1.17%   |
| Intel Celeron N4000 CPU @ 1.10GHz            | 2         | 1.17%   |
| Intel Celeron CPU N3060 @ 1.60GHz            | 2         | 1.17%   |
| Intel Atom CPU N270 @ 1.60GHz                | 2         | 1.17%   |
| AMD Ryzen 7 5700U with Radeon Graphics       | 2         | 1.17%   |
| AMD Ryzen 5 5600H with Radeon Graphics       | 2         | 1.17%   |
| AMD Ryzen 3 3250U with Radeon Graphics       | 2         | 1.17%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G | 2         | 1.17%   |
| Intel Pentium Silver N6000 @ 1.10GHz         | 1         | 0.58%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz     | 1         | 0.58%   |
| Intel Pentium Gold 7505 @ 2.00GHz            | 1         | 0.58%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz  | 1         | 0.58%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz       | 1         | 0.58%   |
| Intel Pentium CPU P6100 @ 2.00GHz            | 1         | 0.58%   |
| Intel Pentium CPU N3710 @ 1.60GHz            | 1         | 0.58%   |
| Intel Pentium CPU N3700 @ 1.60GHz            | 1         | 0.58%   |
| Intel Pentium CPU B980 @ 2.40GHz             | 1         | 0.58%   |
| Intel Genuine CPU U7300 @ 1.30GHz            | 1         | 0.58%   |
| Intel Core i9-9880H CPU @ 2.30GHz            | 1         | 0.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 1         | 0.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 1         | 0.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 1         | 0.58%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz           | 1         | 0.58%   |
| Intel Core i7-6920HQ CPU @ 2.90GHz           | 1         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 33        | 19.3%   |
| Intel Core i7           | 23        | 13.45%  |
| Other                   | 17        | 9.94%   |
| Intel Core i3           | 16        | 9.36%   |
| Intel Celeron           | 11        | 6.43%   |
| Intel Core 2 Duo        | 9         | 5.26%   |
| Intel Atom              | 9         | 5.26%   |
| AMD Ryzen 5             | 9         | 5.26%   |
| AMD Ryzen 7             | 7         | 4.09%   |
| Intel Pentium           | 6         | 3.51%   |
| AMD Ryzen 3             | 3         | 1.75%   |
| Intel Pentium Silver    | 2         | 1.17%   |
| Intel Pentium M         | 2         | 1.17%   |
| Intel Celeron M         | 2         | 1.17%   |
| AMD E2                  | 2         | 1.17%   |
| AMD E1                  | 2         | 1.17%   |
| AMD A4                  | 2         | 1.17%   |
| AMD A10                 | 2         | 1.17%   |
| Intel Pentium Gold      | 1         | 0.58%   |
| Intel Pentium Dual-Core | 1         | 0.58%   |
| Intel Pentium Dual      | 1         | 0.58%   |
| Intel Genuine           | 1         | 0.58%   |
| Intel Core i9           | 1         | 0.58%   |
| Intel Core 2 Extreme    | 1         | 0.58%   |
| Intel Core 2            | 1         | 0.58%   |
| AMD Ryzen 9             | 1         | 0.58%   |
| AMD E                   | 1         | 0.58%   |
| AMD C-50                | 1         | 0.58%   |
| AMD Athlon II           | 1         | 0.58%   |
| AMD Athlon              | 1         | 0.58%   |
| AMD A8                  | 1         | 0.58%   |
| AMD A6                  | 1         | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 99        | 57.89%  |
| 4      | 44        | 25.73%  |
| 6      | 11        | 6.43%   |
| 8      | 9         | 5.26%   |
| 1      | 8         | 4.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 171       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 120       | 70.18%  |
| 1      | 51        | 29.82%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 164       | 95.91%  |
| 32-bit         | 7         | 4.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 15        | 8.57%   |
| 0x306a9    | 14        | 8%      |
| 0x40651    | 9         | 5.14%   |
| 0x406e3    | 7         | 4%      |
| Unknown    | 7         | 4%      |
| 0x806ec    | 6         | 3.43%   |
| 0x08608103 | 6         | 3.43%   |
| 0x08108109 | 6         | 3.43%   |
| 0x806e9    | 5         | 2.86%   |
| 0x6fd      | 5         | 2.86%   |
| 0x406c4    | 5         | 2.86%   |
| 0x206a7    | 5         | 2.86%   |
| 0x1067a    | 5         | 2.86%   |
| 0x306c3    | 4         | 2.29%   |
| 0x30661    | 4         | 2.29%   |
| 0x06006705 | 4         | 2.29%   |
| 0x906ea    | 3         | 1.71%   |
| 0x806ea    | 3         | 1.71%   |
| 0x706a1    | 3         | 1.71%   |
| 0x20655    | 3         | 1.71%   |
| 0x20652    | 3         | 1.71%   |
| 0x106e5    | 3         | 1.71%   |
| 0x106c2    | 3         | 1.71%   |
| 0x10676    | 3         | 1.71%   |
| 0x0a50000c | 3         | 1.71%   |
| 0xa0652    | 2         | 1.14%   |
| 0x706e5    | 2         | 1.14%   |
| 0x6f6      | 2         | 1.14%   |
| 0x6d8      | 2         | 1.14%   |
| 0x506e3    | 2         | 1.14%   |
| 0x306d4    | 2         | 1.14%   |
| 0x30678    | 2         | 1.14%   |
| 0x0a50000d | 2         | 1.14%   |
| 0x06001119 | 2         | 1.14%   |
| 0x906ed    | 1         | 0.57%   |
| 0x906e9    | 1         | 0.57%   |
| 0x906c0    | 1         | 0.57%   |
| 0x806eb    | 1         | 0.57%   |
| 0x806d1    | 1         | 0.57%   |
| 0x706a8    | 1         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 20        | 11.63%  |
| TigerLake     | 15        | 8.72%   |
| IvyBridge     | 14        | 8.14%   |
| Haswell       | 13        | 7.56%   |
| Skylake       | 9         | 5.23%   |
| Silvermont    | 9         | 5.23%   |
| Penryn        | 8         | 4.65%   |
| Bonnell       | 8         | 4.65%   |
| Unknown       | 8         | 4.65%   |
| Zen+          | 7         | 4.07%   |
| Westmere      | 7         | 4.07%   |
| Core          | 7         | 4.07%   |
| Zen 3         | 6         | 3.49%   |
| Excavator     | 6         | 3.49%   |
| SandyBridge   | 5         | 2.91%   |
| Goldmont plus | 4         | 2.33%   |
| P6            | 3         | 1.74%   |
| Nehalem       | 3         | 1.74%   |
| IceLake       | 3         | 1.74%   |
| Broadwell     | 3         | 1.74%   |
| Puma          | 2         | 1.16%   |
| Piledriver    | 2         | 1.16%   |
| Jaguar        | 2         | 1.16%   |
| CometLake     | 2         | 1.16%   |
| Bobcat        | 2         | 1.16%   |
| Zen 2         | 1         | 0.58%   |
| Tremont       | 1         | 0.58%   |
| K10           | 1         | 0.58%   |
| Goldmont      | 1         | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 118       | 58.13%  |
| AMD    | 43        | 21.18%  |
| Nvidia | 42        | 20.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 6.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 5.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 4.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 3.29%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 3.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 3.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.82%   |
| AMD Lucienne                                                                             | 6         | 2.82%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 2.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.35%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 2.35%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.88%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 4         | 1.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.88%   |
| Intel HD Graphics 620                                                                    | 4         | 1.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.88%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 1.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 4         | 1.88%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 1.41%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.41%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.41%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 1.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.41%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 3         | 1.41%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.94%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 2         | 0.94%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.94%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.94%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.94%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 0.94%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.94%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.94%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 0.94%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.94%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.94%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.94%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.94%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 0.94%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 89        | 52.05%  |
| 1 x AMD        | 33        | 19.3%   |
| Intel + Nvidia | 26        | 15.2%   |
| 1 x Nvidia     | 13        | 7.6%    |
| 2 x AMD        | 4         | 2.34%   |
| Intel + AMD    | 3         | 1.75%   |
| AMD + Nvidia   | 3         | 1.75%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 157       | 90.75%  |
| Proprietary | 10        | 5.78%   |
| Unknown     | 6         | 3.47%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 59.77%  |
| 0.01-0.5   | 32        | 18.39%  |
| 1.01-2.0   | 20        | 11.49%  |
| 0.51-1.0   | 8         | 4.6%    |
| 3.01-4.0   | 7         | 4.02%   |
| 5.01-6.0   | 2         | 1.15%   |
| 2.01-3.0   | 1         | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 35        | 19.66%  |
| LG Display              | 29        | 16.29%  |
| Chimei Innolux          | 27        | 15.17%  |
| BOE                     | 24        | 13.48%  |
| Samsung Electronics     | 12        | 6.74%   |
| Apple                   | 7         | 3.93%   |
| Sharp                   | 5         | 2.81%   |
| LG Philips              | 5         | 2.81%   |
| InfoVision              | 4         | 2.25%   |
| Goldstar                | 4         | 2.25%   |
| Chi Mei Optoelectronics | 4         | 2.25%   |
| Lenovo                  | 3         | 1.69%   |
| HannStar                | 3         | 1.69%   |
| Dell                    | 3         | 1.69%   |
| PANDA                   | 2         | 1.12%   |
| Vestel Elektronik       | 1         | 0.56%   |
| TR_                     | 1         | 0.56%   |
| SLD                     | 1         | 0.56%   |
| Quanta Display          | 1         | 0.56%   |
| Planar                  | 1         | 0.56%   |
| Philips                 | 1         | 0.56%   |
| Panasonic               | 1         | 0.56%   |
| Packard Bell            | 1         | 0.56%   |
| Insignia                | 1         | 0.56%   |
| DENON                   | 1         | 0.56%   |
| Acer                    | 1         | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 3         | 1.68%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 1.68%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch        | 3         | 1.68%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 1.68%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch           | 2         | 1.12%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 1.12%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 2         | 1.12%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch              | 2         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch       | 2         | 1.12%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch      | 2         | 1.12%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 1.12%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 1         | 0.56%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                  | 1         | 0.56%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                  | 1         | 0.56%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.56%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 0.56%   |
| Sharp LQ133M1JW02 SHP141A 1920x1080 294x165mm 13.3-inch               | 1         | 0.56%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 294x165mm 13.3-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.56%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                     | 1         | 0.56%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.56%   |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch       | 1         | 0.56%   |
| Planar PLL2210W PLN2210 1920x1080 476x268mm 21.5-inch                 | 1         | 0.56%   |
| Philips PHL 241B7Q PHL0909 1920x1080 527x296mm 23.8-inch              | 1         | 0.56%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.56%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 0.56%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 1         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 71        | 41.04%  |
| 1366x768 (WXGA)   | 55        | 31.79%  |
| 1600x900 (HD+)    | 9         | 5.2%    |
| 1920x1200 (WUXGA) | 7         | 4.05%   |
| 1280x800 (WXGA)   | 7         | 4.05%   |
| 1024x600          | 6         | 3.47%   |
| 3840x2160 (4K)    | 5         | 2.89%   |
| 1440x900 (WXGA+)  | 4         | 2.31%   |
| 2880x1800         | 2         | 1.16%   |
| 1280x1024 (SXGA)  | 2         | 1.16%   |
| 2560x1600         | 1         | 0.58%   |
| 2560x1440 (QHD)   | 1         | 0.58%   |
| 2256x1504         | 1         | 0.58%   |
| 1280x768          | 1         | 0.58%   |
| 1280x720 (HD)     | 1         | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 85        | 47.49%  |
| 13      | 27        | 15.08%  |
| 14      | 18        | 10.06%  |
| 17      | 14        | 7.82%   |
| 24      | 6         | 3.35%   |
| 10      | 6         | 3.35%   |
| 11      | 4         | 2.23%   |
| 23      | 3         | 1.68%   |
| 12      | 3         | 1.68%   |
| Unknown | 3         | 1.68%   |
| 27      | 2         | 1.12%   |
| 21      | 2         | 1.12%   |
| 84      | 1         | 0.56%   |
| 72      | 1         | 0.56%   |
| 40      | 1         | 0.56%   |
| 31      | 1         | 0.56%   |
| 16      | 1         | 0.56%   |
| 8       | 1         | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 116       | 65.91%  |
| 201-300     | 26        | 14.77%  |
| 351-400     | 14        | 7.95%   |
| 501-600     | 10        | 5.68%   |
| Unknown     | 3         | 1.7%    |
| 401-500     | 2         | 1.14%   |
| 1501-2000   | 2         | 1.14%   |
| 801-900     | 1         | 0.57%   |
| 601-700     | 1         | 0.57%   |
| 101-200     | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 141       | 84.43%  |
| 16/10   | 21        | 12.57%  |
| 5/4     | 2         | 1.2%    |
| Unknown | 2         | 1.2%    |
| 3/2     | 1         | 0.6%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 85        | 47.49%  |
| 81-90          | 33        | 18.44%  |
| 71-80          | 12        | 6.7%    |
| 121-130        | 9         | 5.03%   |
| 201-250        | 8         | 4.47%   |
| 41-50          | 6         | 3.35%   |
| 51-60          | 4         | 2.23%   |
| 61-70          | 3         | 1.68%   |
| 251-300        | 3         | 1.68%   |
| 131-140        | 3         | 1.68%   |
| Unknown        | 3         | 1.68%   |
| More than 1000 | 2         | 1.12%   |
| 301-350        | 2         | 1.12%   |
| 141-150        | 2         | 1.12%   |
| 351-500        | 1         | 0.56%   |
| 1-40           | 1         | 0.56%   |
| 501-1000       | 1         | 0.56%   |
| 91-100         | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 72        | 40.45%  |
| 101-120       | 65        | 36.52%  |
| 51-100        | 23        | 12.92%  |
| 161-240       | 11        | 6.18%   |
| More than 240 | 3         | 1.69%   |
| Unknown       | 3         | 1.69%   |
| 1-50          | 1         | 0.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 152       | 87.86%  |
| 2     | 14        | 8.09%   |
| 0     | 6         | 3.47%   |
| 3     | 1         | 0.58%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 88        | 34.38%  |
| Intel                         | 76        | 29.69%  |
| Qualcomm Atheros              | 40        | 15.63%  |
| Broadcom                      | 23        | 8.98%   |
| Broadcom Limited              | 5         | 1.95%   |
| TP-Link                       | 3         | 1.17%   |
| Marvell Technology Group      | 3         | 1.17%   |
| Xiaomi                        | 2         | 0.78%   |
| Ralink Technology             | 2         | 0.78%   |
| MediaTek                      | 2         | 0.78%   |
| Spreadtrum Communications     | 1         | 0.39%   |
| Sierra Wireless               | 1         | 0.39%   |
| Ralink                        | 1         | 0.39%   |
| OnePlus Technology (Shenzhen) | 1         | 0.39%   |
| Nvidia                        | 1         | 0.39%   |
| Lenovo                        | 1         | 0.39%   |
| JMicron Technology            | 1         | 0.39%   |
| Hewlett-Packard               | 1         | 0.39%   |
| Google                        | 1         | 0.39%   |
| Edimax Technology             | 1         | 0.39%   |
| Dell                          | 1         | 0.39%   |
| Davicom Semiconductor         | 1         | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43        | 13.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 5.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13        | 4.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 2.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 2.48%   |
| Intel Wireless 8265 / 8275                                        | 8         | 2.48%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 2.17%   |
| Intel Wireless 7260                                               | 6         | 1.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 1.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.55%   |
| Intel Wireless 3165                                               | 5         | 1.55%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.24%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 1.24%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 1.24%   |
| Intel Wireless 8260                                               | 4         | 1.24%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.24%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.93%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 3         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.93%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.93%   |
| Intel Wireless 7265                                               | 3         | 0.93%   |
| Intel WiFi Link 5100                                              | 3         | 0.93%   |
| Intel Ultimate N WiFi Link 5300                                   | 3         | 0.93%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 0.93%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 0.93%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.62%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.62%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.62%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.62%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 73        | 41.01%  |
| Realtek Semiconductor | 42        | 23.6%   |
| Qualcomm Atheros      | 30        | 16.85%  |
| Broadcom              | 18        | 10.11%  |
| Broadcom Limited      | 4         | 2.25%   |
| TP-Link               | 3         | 1.69%   |
| Ralink Technology     | 2         | 1.12%   |
| MediaTek              | 2         | 1.12%   |
| Xiaomi                | 1         | 0.56%   |
| Sierra Wireless       | 1         | 0.56%   |
| Ralink                | 1         | 0.56%   |
| Edimax Technology     | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 13        | 7.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 4.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 4.4%    |
| Intel Wireless 8265 / 8275                                              | 8         | 4.4%    |
| Intel Wi-Fi 6 AX201                                                     | 7         | 3.85%   |
| Intel Wireless 7260                                                     | 6         | 3.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 3.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.75%   |
| Intel Wireless 3165                                                     | 5         | 2.75%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 2.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 2.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 2.2%    |
| Intel Wireless 8260                                                     | 4         | 2.2%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.65%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 3         | 1.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.65%   |
| Intel Wireless 7265                                                     | 3         | 1.65%   |
| Intel WiFi Link 5100                                                    | 3         | 1.65%   |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 1.65%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 1.65%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.1%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.1%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 1.1%    |
| Realtek 802.11n WLAN Adapter                                            | 2         | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.1%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.1%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.1%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.1%    |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 2         | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.1%    |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.1%    |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.1%    |
| Broadcom BCM43225 802.11b/g/n                                           | 2         | 1.1%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1.1%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 70        | 50.72%  |
| Intel                         | 31        | 22.46%  |
| Qualcomm Atheros              | 18        | 13.04%  |
| Broadcom                      | 6         | 4.35%   |
| Marvell Technology Group      | 3         | 2.17%   |
| Xiaomi                        | 1         | 0.72%   |
| Spreadtrum Communications     | 1         | 0.72%   |
| OnePlus Technology (Shenzhen) | 1         | 0.72%   |
| Nvidia                        | 1         | 0.72%   |
| Lenovo                        | 1         | 0.72%   |
| JMicron Technology            | 1         | 0.72%   |
| Hewlett-Packard               | 1         | 0.72%   |
| Google                        | 1         | 0.72%   |
| Davicom Semiconductor         | 1         | 0.72%   |
| Broadcom Limited              | 1         | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43        | 31.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 13.04%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.9%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 2.9%    |
| Intel 82567LM Gigabit Network Connection                          | 4         | 2.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 2.17%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 2.17%   |
| Intel Ethernet Connection I219-V                                  | 3         | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.17%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 2.17%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.45%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 1.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 1.45%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 1.45%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.45%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.45%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.45%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.45%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.72%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.72%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.72%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.72%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.72%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.72%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.72%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.72%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.72%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.72%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.72%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.72%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.72%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 169       | 55.78%  |
| Ethernet | 132       | 43.56%  |
| Modem    | 2         | 0.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 130       | 72.63%  |
| Ethernet | 49        | 27.37%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 122       | 71.35%  |
| 1     | 43        | 25.15%  |
| 0     | 6         | 3.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 116       | 67.84%  |
| Yes  | 55        | 32.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 42.62%  |
| Realtek Semiconductor           | 28        | 22.95%  |
| Foxconn / Hon Hai               | 8         | 6.56%   |
| Qualcomm Atheros Communications | 6         | 4.92%   |
| Lite-On Technology              | 5         | 4.1%    |
| Broadcom                        | 5         | 4.1%    |
| Apple                           | 5         | 4.1%    |
| Hewlett-Packard                 | 4         | 3.28%   |
| IMC Networks                    | 3         | 2.46%   |
| Dell                            | 3         | 2.46%   |
| Foxconn International           | 2         | 1.64%   |
| Cambridge Silicon Radio         | 1         | 0.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 25        | 20.49%  |
| Realtek Bluetooth Radio                                     | 19        | 15.57%  |
| Intel Bluetooth Device                                      | 12        | 9.84%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 8         | 6.56%   |
| Realtek  Bluetooth 4.2 Adapter                              | 5         | 4.1%    |
| Lite-On Bluetooth Device                                    | 4         | 3.28%   |
| Intel AX200 Bluetooth                                       | 4         | 3.28%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 1.64%   |
| Qualcomm Atheros  Bluetooth Device                          | 2         | 1.64%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.64%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 1.64%   |
| HP Broadcom 2070 Bluetooth Combo                            | 2         | 1.64%   |
| Foxconn International BCM43142A0 Bluetooth module           | 2         | 1.64%   |
| Foxconn / Hon Hai Wireless_Device                           | 2         | 1.64%   |
| Foxconn / Hon Hai Bluetooth Device                          | 2         | 1.64%   |
| Dell Wireless 370 Bluetooth Mini-card                       | 2         | 1.64%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.64%   |
| Apple Bluetooth USB Host Controller                         | 2         | 1.64%   |
| Apple Bluetooth Host Controller                             | 2         | 1.64%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.82%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.82%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.82%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.82%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 0.82%   |
| Intel AX210 Bluetooth                                       | 1         | 0.82%   |
| IMC Networks Bluetooth Radio                                | 1         | 0.82%   |
| IMC Networks Bluetooth Device                               | 1         | 0.82%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.82%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.82%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.82%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller             | 1         | 0.82%   |
| Foxconn / Hon Hai BCM43142A0                                | 1         | 0.82%   |
| Foxconn / Hon Hai Acer Module                               | 1         | 0.82%   |
| Foxconn / Hon Hai Acer Bluetooth module                     | 1         | 0.82%   |
| Dell BCM20702A0 Bluetooth Module                            | 1         | 0.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 0.82%   |
| Broadcom HP Portable SoftSailing                            | 1         | 0.82%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 1         | 0.82%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 0.82%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 0.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 132       | 65.35%  |
| AMD                   | 44        | 21.78%  |
| Nvidia                | 20        | 9.9%    |
| Texas Instruments     | 2         | 0.99%   |
| Yamaha                | 1         | 0.5%    |
| Realtek Semiconductor | 1         | 0.5%    |
| GN Netcom             | 1         | 0.5%    |
| Audioengine           | 1         | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 21        | 8.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 15        | 6%      |
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 6%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 15        | 6%      |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 4.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 4%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 4%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 4%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 3.6%    |
| Intel 8 Series HD Audio Controller                                                                | 9         | 3.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.8%    |
| AMD FCH Azalia Controller                                                                         | 6         | 2.4%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 2.4%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 2%      |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 2%      |
| AMD High Definition Audio Controller                                                              | 5         | 2%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.6%    |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 1.6%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.2%    |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.2%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 1.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.2%    |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.2%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.2%    |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 1.2%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.8%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.8%    |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.8%    |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.8%    |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.8%    |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 26        | 30.95%  |
| SK hynix                     | 20        | 23.81%  |
| Unknown                      | 11        | 13.1%   |
| Micron Technology            | 6         | 7.14%   |
| Kingston                     | 6         | 7.14%   |
| Unknown (ABCD)               | 2         | 2.38%   |
| Nanya Technology             | 2         | 2.38%   |
| G.Skill                      | 2         | 2.38%   |
| Crucial                      | 2         | 2.38%   |
| A-DATA Technology            | 2         | 2.38%   |
| Strontium                    | 1         | 1.19%   |
| Ramaxel Technology           | 1         | 1.19%   |
| Patriot Memory (PDP Systems) | 1         | 1.19%   |
| Corsair                      | 1         | 1.19%   |
| Unknown                      | 1         | 1.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                               | 2         | 2.22%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s          | 2         | 2.22%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 2         | 2.22%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                     | 2         | 2.22%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 2         | 2.22%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 2.22%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                               | 1         | 1.11%   |
| Unknown RAM Module 8GB SODIMM DDR3                                        | 1         | 1.11%   |
| Unknown RAM Module 512MB SODIMM DDR                                       | 1         | 1.11%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                               | 1         | 1.11%   |
| Unknown RAM Module 2GB SODIMM SDRAM                                       | 1         | 1.11%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 1         | 1.11%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                                | 1         | 1.11%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                       | 1         | 1.11%   |
| Unknown RAM Module 1GB SODIMM DDR2                                        | 1         | 1.11%   |
| Unknown RAM Module 1GB SODIMM DDR                                         | 1         | 1.11%   |
| Strontium RAM SRT4G86S0-H9H 4GB SODIMM DDR3 1067MT/s                      | 1         | 1.11%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                             | 1         | 1.11%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                              | 1         | 1.11%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                             | 1         | 1.11%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s                     | 1         | 1.11%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.11%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.11%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.11%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                    | 1         | 1.11%   |
| SK hynix RAM HMT425S6AFR6A-H9 2GB SODIMM DDR3 1333MT/s                    | 1         | 1.11%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.11%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.11%   |
| SK hynix RAM HMT325S6EFR8A-PB 2048MB SODIMM DDR3 1600MT/s                 | 1         | 1.11%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                    | 1         | 1.11%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s                    | 1         | 1.11%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.11%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s                    | 1         | 1.11%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4                             | 1         | 1.11%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s                 | 1         | 1.11%   |
| SK hynix RAM 161616161616161616161616161616161616 1GB SODIMM DDR2 667MT/s | 1         | 1.11%   |
| SK hynix RAM 0C0C0C0C0C0C0C0C0C0C0C0C0C0C0C0C0C0C 1GB SODIMM DDR2 667MT/s | 1         | 1.11%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                               | 1         | 1.11%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                              | 1         | 1.11%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                               | 1         | 1.11%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 35        | 46.05%  |
| DDR3   | 26        | 34.21%  |
| DDR2   | 6         | 7.89%   |
| SDRAM  | 4         | 5.26%   |
| LPDDR4 | 3         | 3.95%   |
| LPDDR3 | 1         | 1.32%   |
| DDR    | 1         | 1.32%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 73        | 94.81%  |
| Row Of Chips | 3         | 3.9%    |
| Unknown      | 1         | 1.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 30        | 36.14%  |
| 4096  | 20        | 24.1%   |
| 2048  | 19        | 22.89%  |
| 16384 | 7         | 8.43%   |
| 32768 | 3         | 3.61%   |
| 1024  | 3         | 3.61%   |
| 512   | 1         | 1.2%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 19        | 24.05%  |
| 1600    | 17        | 21.52%  |
| 2667    | 12        | 15.19%  |
| 2400    | 7         | 8.86%   |
| 667     | 4         | 5.06%   |
| Unknown | 4         | 5.06%   |
| 1067    | 3         | 3.8%    |
| 4199    | 2         | 2.53%   |
| 1334    | 2         | 2.53%   |
| 4267    | 1         | 1.27%   |
| 3266    | 1         | 1.27%   |
| 2267    | 1         | 1.27%   |
| 2133    | 1         | 1.27%   |
| 2048    | 1         | 1.27%   |
| 1867    | 1         | 1.27%   |
| 1333    | 1         | 1.27%   |
| 1200    | 1         | 1.27%   |
| 533     | 1         | 1.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 30        | 20.98%  |
| IMC Networks                           | 16        | 11.19%  |
| Microdia                               | 15        | 10.49%  |
| Acer                                   | 14        | 9.79%   |
| Suyin                                  | 11        | 7.69%   |
| Quanta                                 | 10        | 6.99%   |
| Realtek Semiconductor                  | 9         | 6.29%   |
| Sunplus Innovation Technology          | 7         | 4.9%    |
| Luxvisions Innotech Limited            | 7         | 4.9%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.8%    |
| Alcor Micro                            | 4         | 2.8%    |
| Apple                                  | 3         | 2.1%    |
| Silicon Motion                         | 2         | 1.4%    |
| Lenovo                                 | 2         | 1.4%    |
| Importek                               | 2         | 1.4%    |
| Z-Star Microelectronics                | 1         | 0.7%    |
| Syntek                                 | 1         | 0.7%    |
| Lite-On Technology                     | 1         | 0.7%    |
| Intel                                  | 1         | 0.7%    |
| icSpring                               | 1         | 0.7%    |
| eMPIA Technology                       | 1         | 0.7%    |
| ALi                                    | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                        | 10        | 6.99%   |
| Chicony Integrated Camera                            | 7         | 4.9%    |
| Acer Integrated Camera                               | 7         | 4.9%    |
| IMC Networks Integrated Camera                       | 4         | 2.8%    |
| Chicony HP TrueVision HD Camera                      | 4         | 2.8%    |
| Chicony HD WebCam                                    | 4         | 2.8%    |
| Realtek Lenovo EasyCamera                            | 3         | 2.1%    |
| Quanta HP TrueVision HD Camera                       | 3         | 2.1%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 3         | 2.1%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 3         | 2.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                   | 3         | 2.1%    |
| IMC Networks USB2.0 HD UVC WebCam                    | 3         | 2.1%    |
| Suyin HP TrueVision HD                               | 2         | 1.4%    |
| Suyin HD Video WebCam                                | 2         | 1.4%    |
| Sunplus HD WebCam                                    | 2         | 1.4%    |
| Realtek MTD camera                                   | 2         | 1.4%    |
| Quanta HP Webcam                                     | 2         | 1.4%    |
| Quanta HP HD Camera                                  | 2         | 1.4%    |
| IMC Networks EasyCamera                              | 2         | 1.4%    |
| Chicony HP HD Camera                                 | 2         | 1.4%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam     | 2         | 1.4%    |
| Alcor Micro USB Camera                               | 2         | 1.4%    |
| Acer USB2.0 Camera                                   | 2         | 1.4%    |
| Z-Star WebCam SC-03FFL11739P                         | 1         | 0.7%    |
| Syntek Integrated Camera                             | 1         | 0.7%    |
| Suyin Lenovo EasyCamera                              | 1         | 0.7%    |
| Suyin Integrated_Webcam_HD                           | 1         | 0.7%    |
| Suyin HP Webcam-101                                  | 1         | 0.7%    |
| Suyin HD WebCam                                      | 1         | 0.7%    |
| Suyin Acer/Lenovo Webcam [CN0316]                    | 1         | 0.7%    |
| Suyin Acer CrystalEye Webcam                         | 1         | 0.7%    |
| Suyin 1.3M HD WebCam                                 | 1         | 0.7%    |
| Sunplus USB Camera                                   | 1         | 0.7%    |
| Sunplus Laptop Integrated Webcam FHD                 | 1         | 0.7%    |
| Sunplus HP TrueVision HD Camera                      | 1         | 0.7%    |
| Sunplus Aukey-PC-LM1E Camera                         | 1         | 0.7%    |
| Sunplus 1.3M HD WebCam                               | 1         | 0.7%    |
| Silicon Motion WebCam SC-0311139N                    | 1         | 0.7%    |
| Silicon Motion 300k Pixel Camera                     | 1         | 0.7%    |
| Realtek Integrated_Webcam_HD                         | 1         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 45.83%  |
| AuthenTec                  | 3         | 12.5%   |
| Synaptics                  | 2         | 8.33%   |
| Shenzhen Goodix Technology | 2         | 8.33%   |
| Upek                       | 1         | 4.17%   |
| STMicroelectronics         | 1         | 4.17%   |
| Microsoft                  | 1         | 4.17%   |
| LighTuning Technology      | 1         | 4.17%   |
| Focal-systems.Corp         | 1         | 4.17%   |
| Elan Microelectronics      | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 12.5%   |
| Validity Sensors Synaptics WBDI                        | 2         | 8.33%   |
| Shenzhen Goodix  FingerPrint Device                    | 2         | 8.33%   |
| AuthenTec AES1600                                      | 2         | 8.33%   |
| Unknown                                                | 2         | 8.33%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4.17%   |
| Validity Sensors VFS491                                | 1         | 4.17%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 4.17%   |
| Validity Sensors VFS301 Fingerprint Reader             | 1         | 4.17%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 4.17%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 4.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4.17%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 4.17%   |
| Microsoft Fingerprint Reader                           | 1         | 4.17%   |
| LighTuning Fingerprint Reader                          | 1         | 4.17%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 4.17%   |
| Elan ELAN:Fingerprint                                  | 1         | 4.17%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 4.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 55.56%  |
| O2 Micro    | 2         | 22.22%  |
| Lenovo      | 1         | 11.11%  |
| Alcor Micro | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 33.33%  |
| O2 Micro OZ776 CCID Smartcard Reader           | 2         | 22.22%  |
| Lenovo Integrated Smart Card Reader            | 1         | 11.11%  |
| Broadcom 5880                                  | 1         | 11.11%  |
| Broadcom 58200                                 | 1         | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 114       | 64.77%  |
| 1     | 50        | 28.41%  |
| 2     | 9         | 5.11%   |
| 3     | 2         | 1.14%   |
| 4     | 1         | 0.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 23        | 30.26%  |
| Net/wireless             | 17        | 22.37%  |
| Multimedia controller    | 12        | 15.79%  |
| Graphics card            | 12        | 15.79%  |
| Chipcard                 | 8         | 10.53%  |
| Dvb card                 | 1         | 1.32%   |
| Communication controller | 1         | 1.32%   |
| Card reader              | 1         | 1.32%   |
| Bluetooth                | 1         | 1.32%   |

