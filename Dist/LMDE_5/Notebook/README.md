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

Total: 209

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.10.0-19-amd64        | 29        | 17.58%  |
| 5.10.0-12-amd64        | 23        | 13.94%  |
| 5.10.0-14-amd64        | 20        | 12.12%  |
| 5.10.0-15-amd64        | 16        | 9.7%    |
| 5.10.0-13-amd64        | 14        | 8.48%   |
| 5.10.0-18-amd64        | 13        | 7.88%   |
| 5.10.0-16-amd64        | 11        | 6.67%   |
| 5.10.0-17-amd64        | 8         | 4.85%   |
| 5.10.0-20-amd64        | 7         | 4.24%   |
| 5.10.0-13-686          | 5         | 3.03%   |
| 5.18.0-0.bpo.1-amd64   | 4         | 2.42%   |
| 5.16.0-0.bpo.4-amd64   | 3         | 1.82%   |
| 5.19.10-xanmod1        | 1         | 0.61%   |
| 5.19.0-0.deb11.2-amd64 | 1         | 0.61%   |
| 5.18.0-4-amd64         | 1         | 0.61%   |
| 5.18.0-3-amd64         | 1         | 0.61%   |
| 5.16.0-0.bpo.3-amd64   | 1         | 0.61%   |
| 5.15.78-xanmod1        | 1         | 0.61%   |
| 5.15.70-xanmod1        | 1         | 0.61%   |
| 5.15.0-0.bpo.3-amd64   | 1         | 0.61%   |
| 5.10.0-19-686          | 1         | 0.61%   |
| 5.10.0-17-686          | 1         | 0.61%   |
| 5.10.0-14-686          | 1         | 0.61%   |
| 5.10.0-12-686          | 1         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 143       | 91.08%  |
| 5.18.0  | 6         | 3.82%   |
| 5.16.0  | 3         | 1.91%   |
| 5.19.10 | 1         | 0.64%   |
| 5.19.0  | 1         | 0.64%   |
| 5.15.78 | 1         | 0.64%   |
| 5.15.70 | 1         | 0.64%   |
| 5.15.0  | 1         | 0.64%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 143       | 91.67%  |
| 5.18    | 6         | 3.85%   |
| 5.16    | 3         | 1.92%   |
| 5.19    | 2         | 1.28%   |
| 5.15    | 2         | 1.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 144       | 94.12%  |
| i686   | 9         | 5.88%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 138       | 89.61%  |
| Cinnamon   | 13        | 8.44%   |
| XFCE       | 1         | 0.65%   |
| MATE       | 1         | 0.65%   |
| Unknown    | 1         | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 153       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 91        | 58.71%  |
| LightDM | 64        | 41.29%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 53        | 34.42%  |
| de_DE | 24        | 15.58%  |
| ru_RU | 13        | 8.44%   |
| pt_BR | 9         | 5.84%   |
| en_GB | 9         | 5.84%   |
| fr_FR | 6         | 3.9%    |
| it_IT | 5         | 3.25%   |
| pl_PL | 4         | 2.6%    |
| es_ES | 4         | 2.6%    |
| es_MX | 3         | 1.95%   |
| tr_TR | 2         | 1.3%    |
| ko_KR | 2         | 1.3%    |
| es_BO | 2         | 1.3%    |
| en_IE | 2         | 1.3%    |
| da_DK | 2         | 1.3%    |
| pt_PT | 1         | 0.65%   |
| nn_NO | 1         | 0.65%   |
| nl_AW | 1         | 0.65%   |
| hu_HU | 1         | 0.65%   |
| fr_BE | 1         | 0.65%   |
| es_VE | 1         | 0.65%   |
| es_PE | 1         | 0.65%   |
| es_EC | 1         | 0.65%   |
| es_CR | 1         | 0.65%   |
| en_NZ | 1         | 0.65%   |
| en_IN | 1         | 0.65%   |
| en_CA | 1         | 0.65%   |
| de_CH | 1         | 0.65%   |
| cs_CZ | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 104       | 67.53%  |
| BIOS | 50        | 32.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 141       | 92.16%  |
| Overlay | 5         | 3.27%   |
| Btrfs   | 3         | 1.96%   |
| Xfs     | 2         | 1.31%   |
| Tmpfs   | 2         | 1.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 90        | 58.06%  |
| GPT     | 49        | 31.61%  |
| MBR     | 16        | 10.32%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 144       | 93.51%  |
| Yes       | 10        | 6.49%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 138       | 90.2%   |
| Yes       | 15        | 9.8%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 40        | 26.14%  |
| Lenovo              | 27        | 17.65%  |
| Dell                | 22        | 14.38%  |
| Acer                | 15        | 9.8%    |
| ASUSTek Computer    | 12        | 7.84%   |
| Apple               | 7         | 4.58%   |
| Toshiba             | 3         | 1.96%   |
| Sony                | 3         | 1.96%   |
| MSI                 | 2         | 1.31%   |
| Medion              | 2         | 1.31%   |
| Google              | 2         | 1.31%   |
| Unknown             | 2         | 1.31%   |
| Wortmann AG         | 1         | 0.65%   |
| TUXEDO              | 1         | 0.65%   |
| Samsung Electronics | 1         | 0.65%   |
| Philco              | 1         | 0.65%   |
| Packard Bell        | 1         | 0.65%   |
| Multilaser          | 1         | 0.65%   |
| Microtech           | 1         | 0.65%   |
| LincPlus            | 1         | 0.65%   |
| Kruger&Matz         | 1         | 0.65%   |
| Howard Computers    | 1         | 0.65%   |
| Fujitsu             | 1         | 0.65%   |
| Framework           | 1         | 0.65%   |
| Dynabook            | 1         | 0.65%   |
| Dixonsxp            | 1         | 0.65%   |
| AMI                 | 1         | 0.65%   |
| Alienware           | 1         | 0.65%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 4         | 2.61%   |
| Lenovo IdeaPad 3 15ADA05 81W1         | 2         | 1.31%   |
| Lenovo G500 20236                     | 2         | 1.31%   |
| HP Notebook                           | 2         | 1.31%   |
| HP Laptop 15z-ef2xxx                  | 2         | 1.31%   |
| HP Laptop 15-dw3xxx                   | 2         | 1.31%   |
| Dell Latitude E6400                   | 2         | 1.31%   |
| Dell Latitude E5540                   | 2         | 1.31%   |
| Acer Aspire E1-570G                   | 2         | 1.31%   |
| Acer Aspire 5930                      | 2         | 1.31%   |
| Wortmann AG TERRA_MOBILE_1713A        | 1         | 0.65%   |
| TUXEDO N8xxEZ                         | 1         | 0.65%   |
| Toshiba Satellite M55                 | 1         | 0.65%   |
| Toshiba Satellite L855D               | 1         | 0.65%   |
| Toshiba Satellite L455                | 1         | 0.65%   |
| Sony SVF1532W4E                       | 1         | 0.65%   |
| Sony SVE1713Y1RB                      | 1         | 0.65%   |
| Sony SVE1512G1RW                      | 1         | 0.65%   |
| Samsung 355V4C/356V4C/3445VC/3545VC   | 1         | 0.65%   |
| Philco 10D                            | 1         | 0.65%   |
| Packard Bell DOT S                    | 1         | 0.65%   |
| Multilaser PC150                      | 1         | 0.65%   |
| MSI U180                              | 1         | 0.65%   |
| MSI GL73 8SE                          | 1         | 0.65%   |
| Microtech ebookPro                    | 1         | 0.65%   |
| Medion P15648                         | 1         | 0.65%   |
| Medion E6220                          | 1         | 0.65%   |
| LincPlus LINNCPLUS P1                 | 1         | 0.65%   |
| Lenovo Z50-70 20354                   | 1         | 0.65%   |
| Lenovo Yoga 2 11 20332                | 1         | 0.65%   |
| Lenovo V145-15AST 81MT                | 1         | 0.65%   |
| Lenovo ThinkPad X270 W10DG 20K5S3HG00 | 1         | 0.65%   |
| Lenovo ThinkPad W510 43192PU          | 1         | 0.65%   |
| Lenovo ThinkPad T61 7661A16           | 1         | 0.65%   |
| Lenovo ThinkPad T520 4243W19          | 1         | 0.65%   |
| Lenovo ThinkPad T480 20L6S1RN00       | 1         | 0.65%   |
| Lenovo ThinkPad T470s 20HF0047UK      | 1         | 0.65%   |
| Lenovo ThinkPad T470 W10DG 20JM000CUS | 1         | 0.65%   |
| Lenovo ThinkPad T450 20BUS0QT04       | 1         | 0.65%   |
| Lenovo ThinkPad E15 Gen 4 21EES00100  | 1         | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Acer Aspire        | 12        | 7.84%   |
| Lenovo ThinkPad    | 10        | 6.54%   |
| HP Laptop          | 10        | 6.54%   |
| Dell Latitude      | 9         | 5.88%   |
| Lenovo IdeaPad     | 8         | 5.23%   |
| HP EliteBook       | 6         | 3.92%   |
| Dell Inspiron      | 6         | 3.92%   |
| ASUS VivoBook      | 5         | 3.27%   |
| Unknown            | 4         | 2.61%   |
| Toshiba Satellite  | 3         | 1.96%   |
| HP ProBook         | 3         | 1.96%   |
| HP Pavilion        | 3         | 1.96%   |
| Lenovo Legion      | 2         | 1.31%   |
| Lenovo G500        | 2         | 1.31%   |
| HP ZBook           | 2         | 1.31%   |
| HP Notebook        | 2         | 1.31%   |
| HP Compaq          | 2         | 1.31%   |
| HP 255             | 2         | 1.31%   |
| Dell XPS           | 2         | 1.31%   |
| Dell Vostro        | 2         | 1.31%   |
| Dell Precision     | 2         | 1.31%   |
| ASUS ROG           | 2         | 1.31%   |
| Wortmann AG TERRA  | 1         | 0.65%   |
| TUXEDO N8xxEZ      | 1         | 0.65%   |
| Sony SVF1532W4E    | 1         | 0.65%   |
| Sony SVE1713Y1RB   | 1         | 0.65%   |
| Sony SVE1512G1RW   | 1         | 0.65%   |
| Samsung 355V4C     | 1         | 0.65%   |
| Philco 10D         | 1         | 0.65%   |
| Packard Bell DOT   | 1         | 0.65%   |
| Multilaser PC150   | 1         | 0.65%   |
| MSI U180           | 1         | 0.65%   |
| MSI GL73           | 1         | 0.65%   |
| Microtech ebookPro | 1         | 0.65%   |
| Medion P15648      | 1         | 0.65%   |
| Medion E6220       | 1         | 0.65%   |
| LincPlus LINNCPLUS | 1         | 0.65%   |
| Lenovo Z50-70      | 1         | 0.65%   |
| Lenovo Yoga        | 1         | 0.65%   |
| Lenovo V145-15AST  | 1         | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 22        | 14.38%  |
| 2020 | 16        | 10.46%  |
| 2013 | 14        | 9.15%   |
| 2012 | 13        | 8.5%    |
| 2019 | 11        | 7.19%   |
| 2018 | 10        | 6.54%   |
| 2010 | 10        | 6.54%   |
| 2017 | 9         | 5.88%   |
| 2016 | 8         | 5.23%   |
| 2015 | 7         | 4.58%   |
| 2014 | 6         | 3.92%   |
| 2009 | 6         | 3.92%   |
| 2008 | 6         | 3.92%   |
| 2022 | 5         | 3.27%   |
| 2011 | 4         | 2.61%   |
| 2007 | 4         | 2.61%   |
| 2006 | 2         | 1.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 153       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 137       | 88.96%  |
| Enabled  | 17        | 11.04%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 150       | 98.04%  |
| Yes  | 3         | 1.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 47        | 30.72%  |
| 3.01-4.0    | 35        | 22.88%  |
| 16.01-24.0  | 24        | 15.69%  |
| 8.01-16.0   | 23        | 15.03%  |
| 1.01-2.0    | 10        | 6.54%   |
| 2.01-3.0    | 6         | 3.92%   |
| 32.01-64.0  | 5         | 3.27%   |
| 64.01-256.0 | 3         | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 70        | 43.75%  |
| 2.01-3.0   | 52        | 32.5%   |
| 3.01-4.0   | 17        | 10.63%  |
| 4.01-8.0   | 10        | 6.25%   |
| 0.51-1.0   | 9         | 5.63%   |
| 32.01-64.0 | 1         | 0.63%   |
| 8.01-16.0  | 1         | 0.63%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 119       | 76.28%  |
| 2      | 32        | 20.51%  |
| 3      | 4         | 2.56%   |
| 4      | 1         | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 102       | 66.67%  |
| Yes       | 51        | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 77.78%  |
| No        | 34        | 22.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 151       | 98.69%  |
| No        | 2         | 1.31%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 73.86%  |
| No        | 40        | 26.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 26        | 16.77%  |
| USA         | 23        | 14.84%  |
| Russia      | 16        | 10.32%  |
| Brazil      | 10        | 6.45%   |
| Italy       | 9         | 5.81%   |
| UK          | 8         | 5.16%   |
| France      | 7         | 4.52%   |
| Poland      | 6         | 3.87%   |
| Spain       | 4         | 2.58%   |
| Mexico      | 3         | 1.94%   |
| Canada      | 3         | 1.94%   |
| Belgium     | 3         | 1.94%   |
| Turkey      | 2         | 1.29%   |
| South Korea | 2         | 1.29%   |
| Romania     | 2         | 1.29%   |
| Portugal    | 2         | 1.29%   |
| Hungary     | 2         | 1.29%   |
| Denmark     | 2         | 1.29%   |
| Chile       | 2         | 1.29%   |
| Bolivia     | 2         | 1.29%   |
| Belarus     | 2         | 1.29%   |
| Vietnam     | 1         | 0.65%   |
| Venezuela   | 1         | 0.65%   |
| Sweden      | 1         | 0.65%   |
| Slovenia    | 1         | 0.65%   |
| Peru        | 1         | 0.65%   |
| Paraguay    | 1         | 0.65%   |
| Norway      | 1         | 0.65%   |
| New Zealand | 1         | 0.65%   |
| Malaysia    | 1         | 0.65%   |
| Lithuania   | 1         | 0.65%   |
| Kenya       | 1         | 0.65%   |
| Ireland     | 1         | 0.65%   |
| India       | 1         | 0.65%   |
| Greece      | 1         | 0.65%   |
| Finland     | 1         | 0.65%   |
| Ecuador     | 1         | 0.65%   |
| Czechia     | 1         | 0.65%   |
| Costa Rica  | 1         | 0.65%   |
| Austria     | 1         | 0.65%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Moscow               | 5         | 3.21%   |
| Berlin               | 3         | 1.92%   |
| St Petersburg        | 2         | 1.28%   |
| Rome                 | 2         | 1.28%   |
| Oruro                | 2         | 1.28%   |
| Neasden              | 2         | 1.28%   |
| Krakow               | 2         | 1.28%   |
| Freiburg im Breisgau | 2         | 1.28%   |
| Zaragoza             | 1         | 0.64%   |
| Wroclaw              | 1         | 0.64%   |
| Weimar               | 1         | 0.64%   |
| Voronezh             | 1         | 0.64%   |
| Vilshofen            | 1         | 0.64%   |
| Vilnius              | 1         | 0.64%   |
| Viggianello          | 1         | 0.64%   |
| Viet Tri             | 1         | 0.64%   |
| Veurne               | 1         | 0.64%   |
| Vaslui               | 1         | 0.64%   |
| Valsoyfjord          | 1         | 0.64%   |
| Uiwang               | 1         | 0.64%   |
| Turku                | 1         | 0.64%   |
| Tula                 | 1         | 0.64%   |
| Troisdorf            | 1         | 0.64%   |
| Toulouse             | 1         | 0.64%   |
| Toulon               | 1         | 0.64%   |
| Toronto              | 1         | 0.64%   |
| Tipton               | 1         | 0.64%   |
| Spearfish            | 1         | 0.64%   |
| Smolensk             | 1         | 0.64%   |
| Shrewsbury           | 1         | 0.64%   |
| Scarborough          | 1         | 0.64%   |
| Saratov              | 1         | 0.64%   |
| Sao Paulo            | 1         | 0.64%   |
| Santiago             | 1         | 0.64%   |
| San Jose             | 1         | 0.64%   |
| Salvador             | 1         | 0.64%   |
| Salamina             | 1         | 0.64%   |
| Rottenburg           | 1         | 0.64%   |
| Rochester            | 1         | 0.64%   |
| Recife               | 1         | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 24        | 26     | 12.57%  |
| Samsung Electronics            | 21        | 22     | 10.99%  |
| Seagate                        | 19        | 23     | 9.95%   |
| Unknown                        | 15        | 20     | 7.85%   |
| Sandisk                        | 14        | 17     | 7.33%   |
| Kingston                       | 10        | 10     | 5.24%   |
| Toshiba                        | 7         | 8      | 3.66%   |
| Hitachi                        | 7         | 7      | 3.66%   |
| SK hynix                       | 6         | 6      | 3.14%   |
| Intel                          | 6         | 6      | 3.14%   |
| Micron Technology              | 5         | 5      | 2.62%   |
| Apple                          | 5         | 10     | 2.62%   |
| PNY                            | 4         | 5      | 2.09%   |
| Crucial                        | 4         | 5      | 2.09%   |
| China                          | 4         | 5      | 2.09%   |
| Patriot                        | 3         | 3      | 1.57%   |
| HGST                           | 3         | 3      | 1.57%   |
| A-DATA Technology              | 3         | 4      | 1.57%   |
| Team                           | 2         | 2      | 1.05%   |
| Phison                         | 2         | 2      | 1.05%   |
| KIOXIA                         | 2         | 5      | 1.05%   |
| KingSpec                       | 2         | 2      | 1.05%   |
| Unknown                        | 2         | 2      | 1.05%   |
| Union Memory                   | 1         | 1      | 0.52%   |
| UMIS                           | 1         | 1      | 0.52%   |
| SSD PHIS                       | 1         | 1      | 0.52%   |
| Solid State Storage Technology | 1         | 1      | 0.52%   |
| ShiJi                          | 1         | 1      | 0.52%   |
| SABRENT                        | 1         | 1      | 0.52%   |
| Oyen                           | 1         | 1      | 0.52%   |
| ORICO                          | 1         | 1      | 0.52%   |
| Microtech                      | 1         | 2      | 0.52%   |
| Micron/Crucial Technology      | 1         | 2      | 0.52%   |
| LITEON                         | 1         | 1      | 0.52%   |
| Intenso                        | 1         | 1      | 0.52%   |
| Initio                         | 1         | 1      | 0.52%   |
| HXY                            | 1         | 1      | 0.52%   |
| Gigabyte Technology            | 1         | 2      | 0.52%   |
| Fujitsu                        | 1         | 1      | 0.52%   |
| FORESEE                        | 1         | 1      | 0.52%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 6         | 3.05%   |
| Unknown SD/MMC/MS PRO 64GB           | 3         | 1.52%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 1.52%   |
| SanDisk NVMe SSD Drive 256GB         | 3         | 1.52%   |
| Kingston SA400S37480G 480GB SSD      | 3         | 1.52%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 1.02%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 2         | 1.02%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB | 2         | 1.02%   |
| Unknown SC128  128GB                 | 2         | 1.02%   |
| Unknown MMC Card  64GB               | 2         | 1.02%   |
| Unknown MMC Card  32GB               | 2         | 1.02%   |
| Toshiba MQ01ABD100 1TB               | 2         | 1.02%   |
| Samsung SSD 980 1TB                  | 2         | 1.02%   |
| Samsung SSD 850 EVO 500GB            | 2         | 1.02%   |
| Samsung PM991a NVMe 512GB            | 2         | 1.02%   |
| Patriot Burst 240GB SSD              | 2         | 1.02%   |
| Micron NVMe SSD Drive 512GB          | 2         | 1.02%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 1.02%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 1.02%   |
| Apple SSD SD0128F 121GB              | 2         | 1.02%   |
| Unknown                              | 2         | 1.02%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.51%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1         | 0.51%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.51%   |
| WDC WDBNCE5000PNC 500GB SSD          | 1         | 0.51%   |
| WDC WD7500BPVT-22HXZT3 752GB         | 1         | 0.51%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.51%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.51%   |
| WDC WD5000BPVX-00JC3T0 500GB         | 1         | 0.51%   |
| WDC WD5000BEVT-22A0RT0 500GB         | 1         | 0.51%   |
| WDC WD3200BEVT-60ZCT0 320GB          | 1         | 0.51%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.51%   |
| WDC WD30 EFRX-68EUZN0 3TB            | 1         | 0.51%   |
| WDC WD20SPZX-22UA7T0 2TB             | 1         | 0.51%   |
| WDC WD1600BEVT-60ZCT1 160GB          | 1         | 0.51%   |
| WDC WD10SPZX-60Z10T1 1TB             | 1         | 0.51%   |
| WDC WD10JPVT-55A1YT0 1TB             | 1         | 0.51%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB | 1         | 0.51%   |
| WDC PC SN530 NVMe 256GB              | 1         | 0.51%   |
| WDC PC SA530 SDASN8Y1T00 1024GB      | 1         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 23     | 33.93%  |
| WDC                 | 15        | 16     | 26.79%  |
| Hitachi             | 7         | 7      | 12.5%   |
| Toshiba             | 5         | 6      | 8.93%   |
| Unknown             | 3         | 3      | 5.36%   |
| HGST                | 3         | 3      | 5.36%   |
| Samsung Electronics | 1         | 1      | 1.79%   |
| Intenso             | 1         | 1      | 1.79%   |
| Initio              | 1         | 1      | 1.79%   |
| Fujitsu             | 1         | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 9         | 9      | 13.43%  |
| Samsung Electronics | 7         | 8      | 10.45%  |
| SanDisk             | 5         | 5      | 7.46%   |
| PNY                 | 4         | 5      | 5.97%   |
| Crucial             | 4         | 5      | 5.97%   |
| China               | 4         | 5      | 5.97%   |
| Apple               | 4         | 4      | 5.97%   |
| WDC                 | 3         | 3      | 4.48%   |
| Patriot             | 3         | 3      | 4.48%   |
| Intel               | 3         | 3      | 4.48%   |
| A-DATA Technology   | 3         | 4      | 4.48%   |
| Team                | 2         | 2      | 2.99%   |
| KingSpec            | 2         | 2      | 2.99%   |
| Unknown             | 2         | 2      | 2.99%   |
| Toshiba             | 1         | 1      | 1.49%   |
| SSD PHIS            | 1         | 1      | 1.49%   |
| ORICO               | 1         | 1      | 1.49%   |
| Microtech           | 1         | 2      | 1.49%   |
| Micron Technology   | 1         | 1      | 1.49%   |
| LITEON              | 1         | 1      | 1.49%   |
| HXY                 | 1         | 1      | 1.49%   |
| Gigabyte Technology | 1         | 2      | 1.49%   |
| FORESEE             | 1         | 1      | 1.49%   |
| Corsair             | 1         | 1      | 1.49%   |
| BHT                 | 1         | 2      | 1.49%   |
| Acer                | 1         | 1      | 1.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 62        | 75     | 34.44%  |
| HDD     | 54        | 62     | 30%     |
| NVMe    | 48        | 65     | 26.67%  |
| MMC     | 12        | 16     | 6.67%   |
| Unknown | 4         | 5      | 2.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 103       | 130    | 60.59%  |
| NVMe | 47        | 64     | 27.65%  |
| MMC  | 12        | 16     | 7.06%   |
| SAS  | 8         | 13     | 4.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 79        | 97     | 70.54%  |
| 0.51-1.0   | 29        | 36     | 25.89%  |
| 1.01-2.0   | 2         | 2      | 1.79%   |
| 2.01-3.0   | 1         | 1      | 0.89%   |
| 4.01-10.0  | 1         | 1      | 0.89%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 55        | 35.26%  |
| 251-500        | 40        | 25.64%  |
| 501-1000       | 20        | 12.82%  |
| 51-100         | 11        | 7.05%   |
| 1001-2000      | 10        | 6.41%   |
| 21-50          | 8         | 5.13%   |
| 1-20           | 6         | 3.85%   |
| 2001-3000      | 4         | 2.56%   |
| More than 3000 | 2         | 1.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 80        | 49.69%  |
| 21-50     | 31        | 19.25%  |
| 51-100    | 19        | 11.8%   |
| 101-250   | 14        | 8.7%    |
| 501-1000  | 9         | 5.59%   |
| 251-500   | 7         | 4.35%   |
| 2001-3000 | 1         | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 8.33%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 8.33%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 8.33%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 8.33%   |
| Seagate ST500LT032-1E9142 500GB       | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 850 EVO 500GB | 1         | 1      | 8.33%   |
| Samsung Electronics HM160HC 160GB     | 1         | 1      | 8.33%   |
| Phison ES 512GB                       | 1         | 1      | 8.33%   |
| Intel SSDSCKKF256G8 SATA 256GB        | 1         | 1      | 8.33%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 8.33%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 27.27%  |
| WDC                 | 1         | 2      | 9.09%   |
| Toshiba             | 1         | 1      | 9.09%   |
| SK hynix            | 1         | 1      | 9.09%   |
| Seagate             | 1         | 1      | 9.09%   |
| Phison              | 1         | 1      | 9.09%   |
| Intel               | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |
| HGST                | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 2      | 20%     |
| Seagate             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| Hitachi             | 1         | 1      | 20%     |
| HGST                | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 45.45%  |
| NVMe | 3         | 3      | 27.27%  |
| SSD  | 3         | 3      | 27.27%  |

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
| Detected | 99        | 140    | 59.28%  |
| Works    | 57        | 71     | 34.13%  |
| Malfunc  | 11        | 12     | 6.59%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 104       | 57.78%  |
| AMD                            | 24        | 13.33%  |
| Samsung Electronics            | 14        | 7.78%   |
| SanDisk                        | 12        | 6.67%   |
| SK hynix                       | 6         | 3.33%   |
| Micron Technology              | 4         | 2.22%   |
| KIOXIA                         | 3         | 1.67%   |
| Union Memory (Shenzhen)        | 2         | 1.11%   |
| Phison Electronics             | 2         | 1.11%   |
| Marvell Technology Group       | 2         | 1.11%   |
| Toshiba America Info Systems   | 1         | 0.56%   |
| Solid State Storage Technology | 1         | 0.56%   |
| Nvidia                         | 1         | 0.56%   |
| Micron/Crucial Technology      | 1         | 0.56%   |
| Kingston Technology Company    | 1         | 0.56%   |
| Apple                          | 1         | 0.56%   |
| ADATA Technology               | 1         | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 21        | 10.77%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 12        | 6.15%   |
| Intel Volume Management Device NVMe RAID Controller                              | 11        | 5.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 5.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 5.64%   |
| Samsung NVMe SSD Controller 980                                                  | 7         | 3.59%   |
| Intel Tiger Lake-LP SATA Controller                                              | 7         | 3.59%   |
| SanDisk Non-Volatile memory controller                                           | 6         | 3.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 3.08%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 5         | 2.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 2.05%   |
| Micron Non-Volatile memory controller                                            | 4         | 2.05%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 2.05%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 2.05%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 4         | 2.05%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 3         | 1.54%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 3         | 1.54%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 1.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 3         | 1.54%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.54%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 1.03%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 1.03%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 2         | 1.03%   |
| Intel SSD 660P Series                                                            | 2         | 1.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.03%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.51%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 x4 NVMe SSD Controller                    | 1         | 0.51%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.51%   |
| Solid State Storage Non-Volatile memory controller                               | 1         | 0.51%   |
| SK hynix BC511                                                                   | 1         | 0.51%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 107       | 56.61%  |
| NVMe | 48        | 25.4%   |
| RAID | 23        | 12.17%  |
| IDE  | 11        | 5.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 120       | 78.43%  |
| AMD    | 33        | 21.57%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 8         | 5.23%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 6         | 3.92%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 4         | 2.61%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 4         | 2.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 1.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 1.96%   |
| Intel Pentium M processor 1.73GHz           | 2         | 1.31%   |
| Intel Pentium CPU P6000 @ 1.87GHz           | 2         | 1.31%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 1.31%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 1.31%   |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 2         | 1.31%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 2         | 1.31%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.31%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 1.31%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 2         | 1.31%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 1.31%   |
| Intel Atom CPU N270 @ 1.60GHz               | 2         | 1.31%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 1.31%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 2         | 1.31%   |
| AMD Ryzen 5 5600H with Radeon Graphics      | 2         | 1.31%   |
| AMD Ryzen 3 3250U with Radeon Graphics      | 2         | 1.31%   |
| Intel Pentium Silver N6000 @ 1.10GHz        | 1         | 0.65%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.65%   |
| Intel Pentium Gold 7505 @ 2.00GHz           | 1         | 0.65%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.65%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.65%   |
| Intel Pentium CPU B980 @ 2.40GHz            | 1         | 0.65%   |
| Intel Core i9-9880H CPU @ 2.30GHz           | 1         | 0.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.65%   |
| Intel Core i7-6920HQ CPU @ 2.90GHz          | 1         | 0.65%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 1         | 0.65%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.65%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz          | 1         | 0.65%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.65%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 1         | 0.65%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.65%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz           | 1         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 32        | 20.92%  |
| Intel Core i7           | 20        | 13.07%  |
| Other                   | 15        | 9.8%    |
| Intel Core i3           | 13        | 8.5%    |
| Intel Celeron           | 10        | 6.54%   |
| Intel Core 2 Duo        | 8         | 5.23%   |
| Intel Atom              | 8         | 5.23%   |
| AMD Ryzen 5             | 8         | 5.23%   |
| AMD Ryzen 7             | 7         | 4.58%   |
| Intel Pentium           | 4         | 2.61%   |
| AMD Ryzen 3             | 3         | 1.96%   |
| Intel Pentium Silver    | 2         | 1.31%   |
| Intel Pentium M         | 2         | 1.31%   |
| Intel Celeron M         | 2         | 1.31%   |
| AMD E2                  | 2         | 1.31%   |
| AMD E1                  | 2         | 1.31%   |
| AMD A4                  | 2         | 1.31%   |
| AMD A10                 | 2         | 1.31%   |
| Intel Pentium Gold      | 1         | 0.65%   |
| Intel Pentium Dual-Core | 1         | 0.65%   |
| Intel Core i9           | 1         | 0.65%   |
| Intel Core 2 Extreme    | 1         | 0.65%   |
| Intel Core 2            | 1         | 0.65%   |
| AMD Ryzen 9             | 1         | 0.65%   |
| AMD C-50                | 1         | 0.65%   |
| AMD Athlon II           | 1         | 0.65%   |
| AMD Athlon              | 1         | 0.65%   |
| AMD A8                  | 1         | 0.65%   |
| AMD A6                  | 1         | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 86        | 56.21%  |
| 4      | 41        | 26.8%   |
| 6      | 10        | 6.54%   |
| 8      | 9         | 5.88%   |
| 1      | 7         | 4.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 153       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 110       | 71.9%   |
| 1      | 43        | 28.1%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 147       | 96.08%  |
| 32-bit         | 6         | 3.92%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 14        | 8.92%   |
| 0x306a9    | 14        | 8.92%   |
| 0x40651    | 8         | 5.1%    |
| Unknown    | 7         | 4.46%   |
| 0x806ec    | 6         | 3.82%   |
| 0x406e3    | 6         | 3.82%   |
| 0x08608103 | 6         | 3.82%   |
| 0x08108109 | 6         | 3.82%   |
| 0x806e9    | 5         | 3.18%   |
| 0x406c4    | 5         | 3.18%   |
| 0x30661    | 4         | 2.55%   |
| 0x206a7    | 4         | 2.55%   |
| 0x1067a    | 4         | 2.55%   |
| 0x906ea    | 3         | 1.91%   |
| 0x806ea    | 3         | 1.91%   |
| 0x706a1    | 3         | 1.91%   |
| 0x6fd      | 3         | 1.91%   |
| 0x306c3    | 3         | 1.91%   |
| 0x20652    | 3         | 1.91%   |
| 0x106e5    | 3         | 1.91%   |
| 0x10676    | 3         | 1.91%   |
| 0x0a50000c | 3         | 1.91%   |
| 0x06006705 | 3         | 1.91%   |
| 0xa0652    | 2         | 1.27%   |
| 0x706e5    | 2         | 1.27%   |
| 0x6f6      | 2         | 1.27%   |
| 0x6d8      | 2         | 1.27%   |
| 0x506e3    | 2         | 1.27%   |
| 0x106c2    | 2         | 1.27%   |
| 0x06001119 | 2         | 1.27%   |
| 0x906ed    | 1         | 0.64%   |
| 0x906c0    | 1         | 0.64%   |
| 0x806eb    | 1         | 0.64%   |
| 0x806d1    | 1         | 0.64%   |
| 0x706a8    | 1         | 0.64%   |
| 0x6ec      | 1         | 0.64%   |
| 0x506c9    | 1         | 0.64%   |
| 0x306d4    | 1         | 0.64%   |
| 0x30678    | 1         | 0.64%   |
| 0x30673    | 1         | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 19        | 12.34%  |
| TigerLake     | 14        | 9.09%   |
| IvyBridge     | 14        | 9.09%   |
| Haswell       | 11        | 7.14%   |
| Skylake       | 8         | 5.19%   |
| Unknown       | 8         | 5.19%   |
| Zen+          | 7         | 4.55%   |
| Silvermont    | 7         | 4.55%   |
| Penryn        | 7         | 4.55%   |
| Bonnell       | 7         | 4.55%   |
| Zen 3         | 5         | 3.25%   |
| Westmere      | 5         | 3.25%   |
| Excavator     | 5         | 3.25%   |
| Core          | 5         | 3.25%   |
| SandyBridge   | 4         | 2.6%    |
| Goldmont plus | 4         | 2.6%    |
| P6            | 3         | 1.95%   |
| Nehalem       | 3         | 1.95%   |
| IceLake       | 3         | 1.95%   |
| Puma          | 2         | 1.3%    |
| Piledriver    | 2         | 1.3%    |
| Jaguar        | 2         | 1.3%    |
| CometLake     | 2         | 1.3%    |
| Broadwell     | 2         | 1.3%    |
| Zen 2         | 1         | 0.65%   |
| Tremont       | 1         | 0.65%   |
| K10           | 1         | 0.65%   |
| Goldmont      | 1         | 0.65%   |
| Bobcat        | 1         | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 105       | 57.38%  |
| Nvidia | 39        | 21.31%  |
| AMD    | 39        | 21.31%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 6.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 5.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 4.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 3.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 3.14%   |
| AMD Lucienne                                                                             | 6         | 3.14%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.62%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 2.09%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 2.09%   |
| Intel HD Graphics 620                                                                    | 4         | 2.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 2.09%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 2.09%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 2.09%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 1.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.57%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.57%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 3         | 1.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.57%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.57%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 3         | 1.57%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 1.05%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.05%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 1.05%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 1.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.05%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.05%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.05%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 1.05%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.05%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.05%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 1.05%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.52%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.52%   |
| Nvidia GT216M [GeForce GT 325M]                                                          | 1         | 0.52%   |
| Nvidia GT216GLM [Quadro FX 880M]                                                         | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 78        | 50.98%  |
| 1 x AMD        | 30        | 19.61%  |
| Intel + Nvidia | 24        | 15.69%  |
| 1 x Nvidia     | 12        | 7.84%   |
| 2 x AMD        | 3         | 1.96%   |
| Intel + AMD    | 3         | 1.96%   |
| AMD + Nvidia   | 3         | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 141       | 90.97%  |
| Proprietary | 9         | 5.81%   |
| Unknown     | 5         | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 91        | 58.33%  |
| 0.01-0.5   | 28        | 17.95%  |
| 1.01-2.0   | 19        | 12.18%  |
| 0.51-1.0   | 8         | 5.13%   |
| 3.01-4.0   | 7         | 4.49%   |
| 5.01-6.0   | 2         | 1.28%   |
| 2.01-3.0   | 1         | 0.64%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 34        | 21.12%  |
| LG Display              | 25        | 15.53%  |
| Chimei Innolux          | 25        | 15.53%  |
| BOE                     | 23        | 14.29%  |
| Samsung Electronics     | 9         | 5.59%   |
| Apple                   | 7         | 4.35%   |
| LG Philips              | 5         | 3.11%   |
| InfoVision              | 4         | 2.48%   |
| Goldstar                | 4         | 2.48%   |
| Chi Mei Optoelectronics | 4         | 2.48%   |
| Lenovo                  | 3         | 1.86%   |
| HannStar                | 3         | 1.86%   |
| Sharp                   | 2         | 1.24%   |
| PANDA                   | 2         | 1.24%   |
| Dell                    | 2         | 1.24%   |
| Vestel Elektronik       | 1         | 0.62%   |
| TR_                     | 1         | 0.62%   |
| Quanta Display          | 1         | 0.62%   |
| Planar                  | 1         | 0.62%   |
| Philips                 | 1         | 0.62%   |
| Packard Bell            | 1         | 0.62%   |
| Insignia                | 1         | 0.62%   |
| DENON                   | 1         | 0.62%   |
| Acer                    | 1         | 0.62%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 3         | 1.85%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch        | 3         | 1.85%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.85%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch           | 2         | 1.23%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 1.23%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 2         | 1.23%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch              | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch       | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch      | 2         | 1.23%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 1.23%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch  | 1         | 0.62%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                  | 1         | 0.62%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.62%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 0.62%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 0.62%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                     | 1         | 0.62%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.62%   |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch       | 1         | 0.62%   |
| Planar PLL2210W PLN2210 1920x1080 476x268mm 21.5-inch                 | 1         | 0.62%   |
| Philips PHL 241B7Q PHL0909 1920x1080 527x296mm 23.8-inch              | 1         | 0.62%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.62%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch               | 1         | 0.62%   |
| Packard Bell Viseo 230Ws PKB00C1 1920x1080 509x286mm 23.0-inch        | 1         | 0.62%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch           | 1         | 0.62%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch           | 1         | 0.62%   |
| LG Philips LCD Monitor LPL0001 1280x768 305x183mm 14.0-inch           | 1         | 0.62%   |
| LG Display LCD Monitor LGD3A01 1920x1200 367x230mm 17.1-inch          | 1         | 0.62%   |
| LG Display LCD Monitor LGD06FF 1920x1080 344x194mm 15.5-inch          | 1         | 0.62%   |
| LG Display LCD Monitor LGD069C 1920x1080 309x174mm 14.0-inch          | 1         | 0.62%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch          | 1         | 0.62%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 67        | 42.68%  |
| 1366x768 (WXGA)   | 46        | 29.3%   |
| 1600x900 (HD+)    | 9         | 5.73%   |
| 1920x1200 (WUXGA) | 7         | 4.46%   |
| 1280x800 (WXGA)   | 7         | 4.46%   |
| 1024x600          | 5         | 3.18%   |
| 1440x900 (WXGA+)  | 4         | 2.55%   |
| 3840x2160 (4K)    | 3         | 1.91%   |
| 2880x1800         | 2         | 1.27%   |
| 1280x1024 (SXGA)  | 2         | 1.27%   |
| 2560x1600         | 1         | 0.64%   |
| 2560x1440 (QHD)   | 1         | 0.64%   |
| 2256x1504         | 1         | 0.64%   |
| 1280x768          | 1         | 0.64%   |
| 1280x720 (HD)     | 1         | 0.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 78        | 48.15%  |
| 13      | 23        | 14.2%   |
| 14      | 17        | 10.49%  |
| 17      | 13        | 8.02%   |
| 24      | 5         | 3.09%   |
| 10      | 5         | 3.09%   |
| 27      | 3         | 1.85%   |
| 12      | 3         | 1.85%   |
| 11      | 3         | 1.85%   |
| Unknown | 3         | 1.85%   |
| 23      | 2         | 1.23%   |
| 21      | 2         | 1.23%   |
| 84      | 1         | 0.62%   |
| 72      | 1         | 0.62%   |
| 31      | 1         | 0.62%   |
| 16      | 1         | 0.62%   |
| 8       | 1         | 0.62%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 107       | 67.3%   |
| 201-300     | 21        | 13.21%  |
| 351-400     | 13        | 8.18%   |
| 501-600     | 9         | 5.66%   |
| Unknown     | 3         | 1.89%   |
| 401-500     | 2         | 1.26%   |
| 1501-2000   | 2         | 1.26%   |
| 601-700     | 1         | 0.63%   |
| 101-200     | 1         | 0.63%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 126       | 83.44%  |
| 16/10   | 20        | 13.25%  |
| 5/4     | 2         | 1.32%   |
| Unknown | 2         | 1.32%   |
| 3/2     | 1         | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 78        | 48.15%  |
| 81-90          | 31        | 19.14%  |
| 71-80          | 9         | 5.56%   |
| 121-130        | 8         | 4.94%   |
| 201-250        | 6         | 3.7%    |
| 41-50          | 5         | 3.09%   |
| 61-70          | 3         | 1.85%   |
| 51-60          | 3         | 1.85%   |
| 301-350        | 3         | 1.85%   |
| 251-300        | 3         | 1.85%   |
| 131-140        | 3         | 1.85%   |
| Unknown        | 3         | 1.85%   |
| More than 1000 | 2         | 1.23%   |
| 141-150        | 2         | 1.23%   |
| 351-500        | 1         | 0.62%   |
| 1-40           | 1         | 0.62%   |
| 91-100         | 1         | 0.62%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 70        | 43.48%  |
| 101-120       | 57        | 35.4%   |
| 51-100        | 20        | 12.42%  |
| 161-240       | 9         | 5.59%   |
| Unknown       | 3         | 1.86%   |
| More than 240 | 1         | 0.62%   |
| 1-50          | 1         | 0.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 136       | 87.74%  |
| 2     | 13        | 8.39%   |
| 0     | 5         | 3.23%   |
| 3     | 1         | 0.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 81        | 35.22%  |
| Intel                         | 67        | 29.13%  |
| Qualcomm Atheros              | 34        | 14.78%  |
| Broadcom                      | 23        | 10%     |
| Broadcom Limited              | 4         | 1.74%   |
| Marvell Technology Group      | 3         | 1.3%    |
| Xiaomi                        | 2         | 0.87%   |
| TP-Link                       | 2         | 0.87%   |
| Ralink Technology             | 2         | 0.87%   |
| MediaTek                      | 2         | 0.87%   |
| Ralink                        | 1         | 0.43%   |
| OnePlus Technology (Shenzhen) | 1         | 0.43%   |
| Nvidia                        | 1         | 0.43%   |
| Lenovo                        | 1         | 0.43%   |
| JMicron Technology            | 1         | 0.43%   |
| Hewlett-Packard               | 1         | 0.43%   |
| Google                        | 1         | 0.43%   |
| Edimax Technology             | 1         | 0.43%   |
| Dell                          | 1         | 0.43%   |
| Davicom Semiconductor         | 1         | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 42        | 14.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 4.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 13        | 4.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 2.78%   |
| Intel Wireless 8265 / 8275                                        | 7         | 2.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 2.08%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 2.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.74%   |
| Intel Wireless 3165                                               | 5         | 1.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.39%   |
| Realtek 802.11n WLAN Adapter                                      | 4         | 1.39%   |
| Intel Wireless 7260                                               | 4         | 1.39%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.39%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.39%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 1.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 1.04%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 1.04%   |
| Intel Wireless 8260                                               | 3         | 1.04%   |
| Intel Wireless 7265                                               | 3         | 1.04%   |
| Intel WiFi Link 5100                                              | 3         | 1.04%   |
| Intel Ultimate N WiFi Link 5300                                   | 3         | 1.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.04%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 1.04%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 1.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.69%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.69%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.69%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 0.69%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.69%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.69%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 64        | 40.25%  |
| Realtek Semiconductor | 39        | 24.53%  |
| Qualcomm Atheros      | 25        | 15.72%  |
| Broadcom              | 18        | 11.32%  |
| Broadcom Limited      | 4         | 2.52%   |
| TP-Link               | 2         | 1.26%   |
| Ralink Technology     | 2         | 1.26%   |
| MediaTek              | 2         | 1.26%   |
| Xiaomi                | 1         | 0.63%   |
| Ralink                | 1         | 0.63%   |
| Edimax Technology     | 1         | 0.63%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 13        | 7.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 4.91%   |
| Intel Wireless 8265 / 8275                                     | 7         | 4.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 3.68%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 3.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 3.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 3.07%   |
| Intel Wireless 3165                                            | 5         | 3.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 3.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.45%   |
| Realtek 802.11n WLAN Adapter                                   | 4         | 2.45%   |
| Intel Wireless 7260                                            | 4         | 2.45%   |
| Intel Wi-Fi 6 AX200                                            | 4         | 2.45%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 1.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.84%   |
| Intel Wireless 8260                                            | 3         | 1.84%   |
| Intel Wireless 7265                                            | 3         | 1.84%   |
| Intel WiFi Link 5100                                           | 3         | 1.84%   |
| Intel Ultimate N WiFi Link 5300                                | 3         | 1.84%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 1.84%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.23%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 1.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.23%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.23%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection       | 2         | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.23%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 2         | 1.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 1.23%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.23%   |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 1.23%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.23%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                              | 1         | 0.61%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 0.61%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 0.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 65        | 52.85%  |
| Intel                         | 26        | 21.14%  |
| Qualcomm Atheros              | 15        | 12.2%   |
| Broadcom                      | 6         | 4.88%   |
| Marvell Technology Group      | 3         | 2.44%   |
| Xiaomi                        | 1         | 0.81%   |
| OnePlus Technology (Shenzhen) | 1         | 0.81%   |
| Nvidia                        | 1         | 0.81%   |
| Lenovo                        | 1         | 0.81%   |
| JMicron Technology            | 1         | 0.81%   |
| Hewlett-Packard               | 1         | 0.81%   |
| Google                        | 1         | 0.81%   |
| Davicom Semiconductor         | 1         | 0.81%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 42        | 34.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 14        | 11.38%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 3.25%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 3.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 2.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.44%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 2.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.63%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 1.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 1.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.63%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 1.63%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.63%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.63%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.63%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.63%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.81%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.81%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.81%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.81%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.81%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.81%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.81%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.81%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.81%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.81%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.81%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.81%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 0.81%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.81%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.81%   |
| HP lt4120 Snapdragon X5 LTE                                       | 1         | 0.81%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 151       | 55.72%  |
| Ethernet | 118       | 43.54%  |
| Modem    | 2         | 0.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 119       | 75.32%  |
| Ethernet | 39        | 24.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 110       | 71.9%   |
| 1     | 38        | 24.84%  |
| 0     | 5         | 3.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 107       | 69.93%  |
| Yes  | 46        | 30.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 42.11%  |
| Realtek Semiconductor           | 26        | 22.81%  |
| Foxconn / Hon Hai               | 7         | 6.14%   |
| Qualcomm Atheros Communications | 5         | 4.39%   |
| Lite-On Technology              | 5         | 4.39%   |
| Broadcom                        | 5         | 4.39%   |
| Apple                           | 5         | 4.39%   |
| Hewlett-Packard                 | 4         | 3.51%   |
| IMC Networks                    | 3         | 2.63%   |
| Dell                            | 3         | 2.63%   |
| Foxconn International           | 2         | 1.75%   |
| Cambridge Silicon Radio         | 1         | 0.88%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 22        | 19.3%   |
| Realtek Bluetooth Radio                                     | 19        | 16.67%  |
| Intel AX201 Bluetooth                                       | 11        | 9.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 8         | 7.02%   |
| Realtek  Bluetooth 4.2 Adapter                              | 5         | 4.39%   |
| Intel AX200 Bluetooth                                       | 4         | 3.51%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 2.63%   |
| Qualcomm Atheros  Bluetooth Device                          | 2         | 1.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.75%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 1.75%   |
| HP Broadcom 2070 Bluetooth Combo                            | 2         | 1.75%   |
| Foxconn International BCM43142A0 Bluetooth module           | 2         | 1.75%   |
| Foxconn / Hon Hai Wireless_Device                           | 2         | 1.75%   |
| Dell Wireless 370 Bluetooth Mini-card                       | 2         | 1.75%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.75%   |
| Apple Bluetooth USB Host Controller                         | 2         | 1.75%   |
| Apple Bluetooth Host Controller                             | 2         | 1.75%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.88%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.88%   |
| Lite-On Bluetooth Device                                    | 1         | 0.88%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 0.88%   |
| Intel AX210 Bluetooth                                       | 1         | 0.88%   |
| IMC Networks Bluetooth Radio                                | 1         | 0.88%   |
| IMC Networks Bluetooth Device                               | 1         | 0.88%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.88%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.88%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.88%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller             | 1         | 0.88%   |
| Foxconn / Hon Hai Bluetooth Device                          | 1         | 0.88%   |
| Foxconn / Hon Hai BCM43142A0                                | 1         | 0.88%   |
| Foxconn / Hon Hai Acer Module                               | 1         | 0.88%   |
| Foxconn / Hon Hai Acer Bluetooth module                     | 1         | 0.88%   |
| Dell BCM20702A0 Bluetooth Module                            | 1         | 0.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 0.88%   |
| Broadcom HP Portable SoftSailing                            | 1         | 0.88%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 1         | 0.88%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 0.88%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 0.88%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 117       | 64.29%  |
| AMD                   | 40        | 21.98%  |
| Nvidia                | 19        | 10.44%  |
| Texas Instruments     | 2         | 1.1%    |
| Yamaha                | 1         | 0.55%   |
| Realtek Semiconductor | 1         | 0.55%   |
| GN Netcom             | 1         | 0.55%   |
| Audioengine           | 1         | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 8.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 15        | 6.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 6.25%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 6.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 4.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 4.02%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 3.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 3.57%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 3.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 3.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 3.13%   |
| AMD FCH Azalia Controller                                                                         | 6         | 2.68%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.23%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 2.23%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 2.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.79%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.79%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.34%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.34%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 1.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.34%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 1.34%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 1.34%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.89%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 2         | 0.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 0.89%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 0.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.89%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.89%   |
| Intel Broadwell-U Audio Controller                                                                | 2         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.89%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.89%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.89%   |
| Yamaha Steinberg UR22mkII                                                                         | 1         | 0.45%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 1         | 0.45%   |
| Texas Instruments PCM2702 16-bit stereo audio DAC                                                 | 1         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 23        | 31.94%  |
| SK hynix                     | 18        | 25%     |
| Unknown                      | 10        | 13.89%  |
| Micron Technology            | 4         | 5.56%   |
| Kingston                     | 4         | 5.56%   |
| Unknown (ABCD)               | 2         | 2.78%   |
| Nanya Technology             | 2         | 2.78%   |
| Crucial                      | 2         | 2.78%   |
| A-DATA Technology            | 2         | 2.78%   |
| Ramaxel Technology           | 1         | 1.39%   |
| Patriot Memory (PDP Systems) | 1         | 1.39%   |
| G.Skill                      | 1         | 1.39%   |
| Corsair                      | 1         | 1.39%   |
| Unknown                      | 1         | 1.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 2.63%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.63%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 2.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 2.63%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.63%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 1.32%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 1.32%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 1.32%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 1.32%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 1.32%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.32%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 1.32%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 1.32%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 1.32%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 1.32%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 1.32%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 1         | 1.32%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 1         | 1.32%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.32%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.32%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.32%   |
| SK hynix RAM HMT425S6AFR6A-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.32%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.32%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.32%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.32%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.32%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.32%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.32%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.32%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.32%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.32%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                     | 1         | 1.32%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 1.32%   |
| Samsung RAM M471B5773DH0-CK0 2048MB SODIMM DDR3 1600MT/s         | 1         | 1.32%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.32%   |
| Samsung RAM M471B5673EH1-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.32%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.32%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.32%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.32%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 33        | 50%     |
| DDR3   | 22        | 33.33%  |
| SDRAM  | 3         | 4.55%   |
| LPDDR4 | 3         | 4.55%   |
| DDR2   | 3         | 4.55%   |
| LPDDR3 | 1         | 1.52%   |
| DDR    | 1         | 1.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 95.52%  |
| Row Of Chips | 2         | 2.99%   |
| Unknown      | 1         | 1.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 28        | 38.36%  |
| 4096  | 17        | 23.29%  |
| 2048  | 15        | 20.55%  |
| 16384 | 7         | 9.59%   |
| 32768 | 3         | 4.11%   |
| 1024  | 2         | 2.74%   |
| 512   | 1         | 1.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 17        | 25%     |
| 1600    | 16        | 23.53%  |
| 2667    | 11        | 16.18%  |
| 2400    | 7         | 10.29%  |
| Unknown | 4         | 5.88%   |
| 1334    | 2         | 2.94%   |
| 667     | 2         | 2.94%   |
| 4267    | 1         | 1.47%   |
| 4199    | 1         | 1.47%   |
| 3266    | 1         | 1.47%   |
| 2267    | 1         | 1.47%   |
| 2048    | 1         | 1.47%   |
| 1867    | 1         | 1.47%   |
| 1333    | 1         | 1.47%   |
| 1200    | 1         | 1.47%   |
| 1067    | 1         | 1.47%   |

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
| Chicony Electronics                    | 26        | 20.16%  |
| IMC Networks                           | 15        | 11.63%  |
| Microdia                               | 14        | 10.85%  |
| Acer                                   | 13        | 10.08%  |
| Suyin                                  | 9         | 6.98%   |
| Quanta                                 | 9         | 6.98%   |
| Sunplus Innovation Technology          | 7         | 5.43%   |
| Realtek Semiconductor                  | 7         | 5.43%   |
| Luxvisions Innotech Limited            | 7         | 5.43%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.1%    |
| Apple                                  | 3         | 2.33%   |
| Alcor Micro                            | 3         | 2.33%   |
| Lenovo                                 | 2         | 1.55%   |
| Importek                               | 2         | 1.55%   |
| Z-Star Microelectronics                | 1         | 0.78%   |
| USB Camera                             | 1         | 0.78%   |
| Syntek                                 | 1         | 0.78%   |
| Silicon Motion                         | 1         | 0.78%   |
| Lite-On Technology                     | 1         | 0.78%   |
| Intel                                  | 1         | 0.78%   |
| eMPIA Technology                       | 1         | 0.78%   |
| ALi                                    | 1         | 0.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                        | 9         | 6.98%   |
| Chicony Integrated Camera                            | 7         | 5.43%   |
| Acer Integrated Camera                               | 6         | 4.65%   |
| Chicony HD WebCam                                    | 4         | 3.1%    |
| Sunplus HD WebCam                                    | 3         | 2.33%   |
| Quanta HP TrueVision HD Camera                       | 3         | 2.33%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 3         | 2.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 3         | 2.33%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 3         | 2.33%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 3         | 2.33%   |
| IMC Networks Integrated Camera                       | 3         | 2.33%   |
| Chicony HP TrueVision HD Camera                      | 3         | 2.33%   |
| Suyin HP TrueVision HD                               | 2         | 1.55%   |
| Suyin HD Video WebCam                                | 2         | 1.55%   |
| Realtek Lenovo EasyCamera                            | 2         | 1.55%   |
| Quanta HP Webcam                                     | 2         | 1.55%   |
| Quanta HP HD Camera                                  | 2         | 1.55%   |
| IMC Networks EasyCamera                              | 2         | 1.55%   |
| Chicony HP HD Camera                                 | 2         | 1.55%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam     | 2         | 1.55%   |
| Alcor Micro USB 2.0 Camera                           | 2         | 1.55%   |
| Acer USB2.0 Camera                                   | 2         | 1.55%   |
| Z-Star WebCam SC-03FFL11739P                         | 1         | 0.78%   |
| USB Camera USB Camera                                | 1         | 0.78%   |
| Syntek Integrated Camera                             | 1         | 0.78%   |
| Suyin HP Webcam-101                                  | 1         | 0.78%   |
| Suyin HD WebCam                                      | 1         | 0.78%   |
| Suyin Acer/Lenovo Webcam [CN0316]                    | 1         | 0.78%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 0.78%   |
| Suyin 1.3M HD WebCam                                 | 1         | 0.78%   |
| Sunplus Laptop Integrated Webcam FHD                 | 1         | 0.78%   |
| Sunplus HP TrueVision HD Camera                      | 1         | 0.78%   |
| Sunplus Aukey-PC-LM1E Camera                         | 1         | 0.78%   |
| Sunplus 1.3M HD WebCam                               | 1         | 0.78%   |
| Silicon Motion 300k Pixel Camera                     | 1         | 0.78%   |
| Realtek USB2.0 camera                                | 1         | 0.78%   |
| Realtek Integrated_Webcam_HD                         | 1         | 0.78%   |
| Realtek HP Truevision HD integrated webcam           | 1         | 0.78%   |
| Realtek HP Truevision HD                             | 1         | 0.78%   |
| Realtek HP "Truevision HD" laptop camera             | 1         | 0.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 47.37%  |
| Synaptics                  | 2         | 10.53%  |
| Shenzhen Goodix Technology | 2         | 10.53%  |
| AuthenTec                  | 2         | 10.53%  |
| Upek                       | 1         | 5.26%   |
| STMicroelectronics         | 1         | 5.26%   |
| Focal-systems.Corp         | 1         | 5.26%   |
| Elan Microelectronics      | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 15.79%  |
| Validity Sensors Synaptics WBDI                        | 2         | 10.53%  |
| Shenzhen Goodix  FingerPrint Device                    | 2         | 10.53%  |
| Unknown                                                | 2         | 10.53%  |
| Validity Sensors VFS491                                | 1         | 5.26%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 5.26%   |
| Validity Sensors VFS301 Fingerprint Reader             | 1         | 5.26%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 5.26%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5.26%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 5.26%   |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 5.26%   |
| Elan ELAN:Fingerprint                                  | 1         | 5.26%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 5.26%   |
| AuthenTec AES1600                                      | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 62.5%   |
| O2 Micro    | 1         | 12.5%   |
| Lenovo      | 1         | 12.5%   |
| Alcor Micro | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 37.5%   |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 12.5%   |
| Lenovo Integrated Smart Card Reader            | 1         | 12.5%   |
| Broadcom 5880                                  | 1         | 12.5%   |
| Broadcom 58200                                 | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 101       | 64.33%  |
| 1     | 46        | 29.3%   |
| 2     | 8         | 5.1%    |
| 4     | 1         | 0.64%   |
| 3     | 1         | 0.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 18        | 26.87%  |
| Net/wireless             | 17        | 25.37%  |
| Multimedia controller    | 12        | 17.91%  |
| Graphics card            | 9         | 13.43%  |
| Chipcard                 | 7         | 10.45%  |
| Dvb card                 | 1         | 1.49%   |
| Communication controller | 1         | 1.49%   |
| Card reader              | 1         | 1.49%   |
| Bluetooth                | 1         | 1.49%   |

