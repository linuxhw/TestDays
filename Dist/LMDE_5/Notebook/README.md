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

Total: 253

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite L300              | [c1b163bee0](https://linux-hardware.org/?probe=c1b163bee0) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | [76e5b62eec](https://linux-hardware.org/?probe=76e5b62eec) | Feb 25, 2023 |
| HP            | 2000                        | [2e234233cc](https://linux-hardware.org/?probe=2e234233cc) | Feb 25, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [5ad40efe5c](https://linux-hardware.org/?probe=5ad40efe5c) | Feb 24, 2023 |
| HP            | 250 G8 Notebook PC          | [08d9bfbb41](https://linux-hardware.org/?probe=08d9bfbb41) | Feb 24, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [7acab84e04](https://linux-hardware.org/?probe=7acab84e04) | Feb 22, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [aa5d23bc20](https://linux-hardware.org/?probe=aa5d23bc20) | Feb 19, 2023 |
| itel Mobil... | SPIRIT 2                    | [8c370ddf38](https://linux-hardware.org/?probe=8c370ddf38) | Feb 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [392442adfb](https://linux-hardware.org/?probe=392442adfb) | Feb 16, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [da4802f871](https://linux-hardware.org/?probe=da4802f871) | Feb 12, 2023 |
| Compaq        | 420                         | [2028e7c97c](https://linux-hardware.org/?probe=2028e7c97c) | Feb 12, 2023 |
| HP            | ProBook 650 G2              | [b8854f5844](https://linux-hardware.org/?probe=b8854f5844) | Feb 12, 2023 |
| Star Labs     | StarBook                    | [08e31c8ad5](https://linux-hardware.org/?probe=08e31c8ad5) | Feb 10, 2023 |
| Dell          | Precision M4800             | [3f97bef125](https://linux-hardware.org/?probe=3f97bef125) | Feb 08, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [3e0851346e](https://linux-hardware.org/?probe=3e0851346e) | Feb 08, 2023 |
| TUXEDO        | N8xxEZ                      | [680bdf5ada](https://linux-hardware.org/?probe=680bdf5ada) | Feb 07, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | [3301121a5c](https://linux-hardware.org/?probe=3301121a5c) | Feb 04, 2023 |
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
| 5.10.0-19-amd64        | 29        | 14.65%  |
| 5.10.0-12-amd64        | 23        | 11.62%  |
| 5.10.0-14-amd64        | 20        | 10.1%   |
| 5.10.0-21-amd64        | 17        | 8.59%   |
| 5.10.0-20-amd64        | 17        | 8.59%   |
| 5.10.0-15-amd64        | 16        | 8.08%   |
| 5.10.0-18-amd64        | 14        | 7.07%   |
| 5.10.0-13-amd64        | 14        | 7.07%   |
| 5.10.0-16-amd64        | 11        | 5.56%   |
| 5.10.0-17-amd64        | 9         | 4.55%   |
| 5.10.0-13-686          | 5         | 2.53%   |
| 5.18.0-0.bpo.1-amd64   | 4         | 2.02%   |
| 5.16.0-0.bpo.4-amd64   | 3         | 1.52%   |
| 5.10.0-12-686          | 2         | 1.01%   |
| 6.1.11-x64v1-xanmod1   | 1         | 0.51%   |
| 5.19.10-xanmod1        | 1         | 0.51%   |
| 5.19.0-0.deb11.2-amd64 | 1         | 0.51%   |
| 5.18.0-4-amd64         | 1         | 0.51%   |
| 5.18.0-3-amd64         | 1         | 0.51%   |
| 5.16.0-0.bpo.3-amd64   | 1         | 0.51%   |
| 5.15.78-xanmod1        | 1         | 0.51%   |
| 5.15.70-xanmod1        | 1         | 0.51%   |
| 5.15.0-0.bpo.3-amd64   | 1         | 0.51%   |
| 5.10.0-20-686          | 1         | 0.51%   |
| 5.10.0-19-686          | 1         | 0.51%   |
| 5.10.0-17-686          | 1         | 0.51%   |
| 5.10.0-14-686          | 1         | 0.51%   |
| 4.19.0-23-amd64        | 1         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 170       | 91.4%   |
| 5.18.0  | 6         | 3.23%   |
| 5.16.0  | 3         | 1.61%   |
| 6.1.11  | 1         | 0.54%   |
| 5.19.10 | 1         | 0.54%   |
| 5.19.0  | 1         | 0.54%   |
| 5.15.78 | 1         | 0.54%   |
| 5.15.70 | 1         | 0.54%   |
| 5.15.0  | 1         | 0.54%   |
| 4.19.0  | 1         | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 170       | 91.89%  |
| 5.18    | 6         | 3.24%   |
| 5.16    | 3         | 1.62%   |
| 5.19    | 2         | 1.08%   |
| 5.15    | 2         | 1.08%   |
| 6.1     | 1         | 0.54%   |
| 4.19    | 1         | 0.54%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 171       | 93.96%  |
| i686   | 11        | 6.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 162       | 88.52%  |
| Cinnamon   | 16        | 8.74%   |
| MATE       | 2         | 1.09%   |
| XFCE       | 1         | 0.55%   |
| awesome    | 1         | 0.55%   |
| Unknown    | 1         | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 182       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 106       | 57.61%  |
| LightDM | 78        | 42.39%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 60        | 32.79%  |
| de_DE | 28        | 15.3%   |
| ru_RU | 19        | 10.38%  |
| pt_BR | 12        | 6.56%   |
| en_GB | 11        | 6.01%   |
| fr_FR | 8         | 4.37%   |
| it_IT | 6         | 3.28%   |
| es_ES | 5         | 2.73%   |
| pl_PL | 4         | 2.19%   |
| es_MX | 3         | 1.64%   |
| tr_TR | 2         | 1.09%   |
| ko_KR | 2         | 1.09%   |
| es_BO | 2         | 1.09%   |
| en_NZ | 2         | 1.09%   |
| en_IE | 2         | 1.09%   |
| da_DK | 2         | 1.09%   |
| pt_PT | 1         | 0.55%   |
| nn_NO | 1         | 0.55%   |
| nl_AW | 1         | 0.55%   |
| hu_HU | 1         | 0.55%   |
| fr_BE | 1         | 0.55%   |
| es_VE | 1         | 0.55%   |
| es_PE | 1         | 0.55%   |
| es_EC | 1         | 0.55%   |
| es_CR | 1         | 0.55%   |
| en_SG | 1         | 0.55%   |
| en_IN | 1         | 0.55%   |
| en_CA | 1         | 0.55%   |
| el_GR | 1         | 0.55%   |
| de_CH | 1         | 0.55%   |
| cs_CZ | 1         | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 121       | 66.12%  |
| BIOS | 62        | 33.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 169       | 92.86%  |
| Overlay | 5         | 2.75%   |
| Btrfs   | 4         | 2.2%    |
| Xfs     | 2         | 1.1%    |
| Tmpfs   | 2         | 1.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 105       | 57.07%  |
| GPT     | 56        | 30.43%  |
| MBR     | 23        | 12.5%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 168       | 91.8%   |
| Yes       | 15        | 8.2%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 162       | 88.52%  |
| Yes       | 21        | 11.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 44        | 24.18%  |
| Lenovo              | 35        | 19.23%  |
| Dell                | 25        | 13.74%  |
| Acer                | 16        | 8.79%   |
| ASUSTek Computer    | 13        | 7.14%   |
| Toshiba             | 7         | 3.85%   |
| Apple               | 7         | 3.85%   |
| Sony                | 3         | 1.65%   |
| Google              | 3         | 1.65%   |
| Fujitsu             | 3         | 1.65%   |
| Samsung Electronics | 2         | 1.1%    |
| MSI                 | 2         | 1.1%    |
| Medion              | 2         | 1.1%    |
| Compaq              | 2         | 1.1%    |
| Unknown             | 2         | 1.1%    |
| Wortmann AG         | 1         | 0.55%   |
| TUXEDO              | 1         | 0.55%   |
| Star Labs           | 1         | 0.55%   |
| Philco              | 1         | 0.55%   |
| Packard Bell        | 1         | 0.55%   |
| Multilaser          | 1         | 0.55%   |
| Microtech           | 1         | 0.55%   |
| LincPlus            | 1         | 0.55%   |
| Kruger&Matz         | 1         | 0.55%   |
| itel Mobile Limited | 1         | 0.55%   |
| Howard Computers    | 1         | 0.55%   |
| Framework           | 1         | 0.55%   |
| Dynabook            | 1         | 0.55%   |
| Dixonsxp            | 1         | 0.55%   |
| AMI                 | 1         | 0.55%   |
| Alienware           | 1         | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 4         | 2.2%    |
| Lenovo IdeaPad 3 15ITL6 82H8        | 2         | 1.1%    |
| Lenovo IdeaPad 3 15ADA05 81W1       | 2         | 1.1%    |
| Lenovo G500 20236                   | 2         | 1.1%    |
| HP Notebook                         | 2         | 1.1%    |
| HP Laptop 15z-ef2xxx                | 2         | 1.1%    |
| HP Laptop 15-dw3xxx                 | 2         | 1.1%    |
| HP 250 G8 Notebook PC               | 2         | 1.1%    |
| Dell Latitude E6400                 | 2         | 1.1%    |
| Dell Latitude E5540                 | 2         | 1.1%    |
| Compaq 420                          | 2         | 1.1%    |
| Acer Aspire E1-570G                 | 2         | 1.1%    |
| Acer Aspire 5930                    | 2         | 1.1%    |
| Wortmann AG TERRA_MOBILE_1713A      | 1         | 0.55%   |
| TUXEDO N8xxEZ                       | 1         | 0.55%   |
| Toshiba Satellite M55               | 1         | 0.55%   |
| Toshiba Satellite L855D             | 1         | 0.55%   |
| Toshiba Satellite L455              | 1         | 0.55%   |
| Toshiba Satellite L305              | 1         | 0.55%   |
| Toshiba Satellite L300              | 1         | 0.55%   |
| Toshiba PORTEGE Z30-B               | 1         | 0.55%   |
| Toshiba PORTEGE M780                | 1         | 0.55%   |
| Star Labs StarBook                  | 1         | 0.55%   |
| Sony SVF1532W4E                     | 1         | 0.55%   |
| Sony SVE1713Y1RB                    | 1         | 0.55%   |
| Sony SVE1512G1RW                    | 1         | 0.55%   |
| Samsung RV415/RV515                 | 1         | 0.55%   |
| Samsung 355V4C/356V4C/3445VC/3545VC | 1         | 0.55%   |
| Philco 10D                          | 1         | 0.55%   |
| Packard Bell DOT S                  | 1         | 0.55%   |
| Multilaser PC150                    | 1         | 0.55%   |
| MSI U180                            | 1         | 0.55%   |
| MSI GL73 8SE                        | 1         | 0.55%   |
| Microtech ebookPro                  | 1         | 0.55%   |
| Medion P15648                       | 1         | 0.55%   |
| Medion E6220                        | 1         | 0.55%   |
| LincPlus LINNCPLUS P1               | 1         | 0.55%   |
| Lenovo Z50-70 20354                 | 1         | 0.55%   |
| Lenovo Yoga 2 11 20332              | 1         | 0.55%   |
| Lenovo V145-15AST 81MT              | 1         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 13        | 7.14%   |
| Acer Aspire        | 13        | 7.14%   |
| HP Laptop          | 11        | 6.04%   |
| Lenovo IdeaPad     | 10        | 5.49%   |
| Dell Latitude      | 9         | 4.95%   |
| HP EliteBook       | 6         | 3.3%    |
| Dell Inspiron      | 6         | 3.3%    |
| Toshiba Satellite  | 5         | 2.75%   |
| ASUS VivoBook      | 5         | 2.75%   |
| HP ProBook         | 4         | 2.2%    |
| Dell Precision     | 4         | 2.2%    |
| Unknown            | 4         | 2.2%    |
| HP Pavilion        | 3         | 1.65%   |
| Dell Vostro        | 3         | 1.65%   |
| Toshiba PORTEGE    | 2         | 1.1%    |
| Lenovo ThinkBook   | 2         | 1.1%    |
| Lenovo Legion      | 2         | 1.1%    |
| Lenovo G500        | 2         | 1.1%    |
| HP ZBook           | 2         | 1.1%    |
| HP Notebook        | 2         | 1.1%    |
| HP Compaq          | 2         | 1.1%    |
| HP 255             | 2         | 1.1%    |
| HP 250             | 2         | 1.1%    |
| Fujitsu LIFEBOOK   | 2         | 1.1%    |
| Dell XPS           | 2         | 1.1%    |
| Compaq 420         | 2         | 1.1%    |
| ASUS ROG           | 2         | 1.1%    |
| Wortmann AG TERRA  | 1         | 0.55%   |
| TUXEDO N8xxEZ      | 1         | 0.55%   |
| Star Labs StarBook | 1         | 0.55%   |
| Sony SVF1532W4E    | 1         | 0.55%   |
| Sony SVE1713Y1RB   | 1         | 0.55%   |
| Sony SVE1512G1RW   | 1         | 0.55%   |
| Samsung RV415      | 1         | 0.55%   |
| Samsung 355V4C     | 1         | 0.55%   |
| Philco 10D         | 1         | 0.55%   |
| Packard Bell DOT   | 1         | 0.55%   |
| Multilaser PC150   | 1         | 0.55%   |
| MSI U180           | 1         | 0.55%   |
| MSI GL73           | 1         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 26        | 14.29%  |
| 2020 | 18        | 9.89%   |
| 2013 | 15        | 8.24%   |
| 2012 | 13        | 7.14%   |
| 2010 | 12        | 6.59%   |
| 2019 | 11        | 6.04%   |
| 2017 | 11        | 6.04%   |
| 2016 | 11        | 6.04%   |
| 2018 | 10        | 5.49%   |
| 2015 | 9         | 4.95%   |
| 2022 | 8         | 4.4%    |
| 2009 | 8         | 4.4%    |
| 2008 | 8         | 4.4%    |
| 2014 | 7         | 3.85%   |
| 2011 | 7         | 3.85%   |
| 2007 | 5         | 2.75%   |
| 2006 | 2         | 1.1%    |
| 2023 | 1         | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 182       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 161       | 87.98%  |
| Enabled  | 22        | 12.02%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 177       | 97.25%  |
| Yes  | 5         | 2.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 55        | 30.22%  |
| 3.01-4.0    | 41        | 22.53%  |
| 8.01-16.0   | 29        | 15.93%  |
| 16.01-24.0  | 27        | 14.84%  |
| 1.01-2.0    | 12        | 6.59%   |
| 32.01-64.0  | 8         | 4.4%    |
| 2.01-3.0    | 7         | 3.85%   |
| 64.01-256.0 | 3         | 1.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 87        | 45.31%  |
| 2.01-3.0   | 61        | 31.77%  |
| 3.01-4.0   | 18        | 9.38%   |
| 4.01-8.0   | 13        | 6.77%   |
| 0.51-1.0   | 11        | 5.73%   |
| 32.01-64.0 | 1         | 0.52%   |
| 8.01-16.0  | 1         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 140       | 75.68%  |
| 2      | 37        | 20%     |
| 3      | 7         | 3.78%   |
| 4      | 1         | 0.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 123       | 67.58%  |
| Yes       | 59        | 32.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 142       | 78.02%  |
| No        | 40        | 21.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 179       | 98.35%  |
| No        | 3         | 1.65%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 69.95%  |
| No        | 55        | 30.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 31        | 16.85%  |
| USA         | 30        | 16.3%   |
| Russia      | 20        | 10.87%  |
| Brazil      | 12        | 6.52%   |
| Italy       | 10        | 5.43%   |
| UK          | 8         | 4.35%   |
| France      | 8         | 4.35%   |
| Poland      | 6         | 3.26%   |
| Spain       | 5         | 2.72%   |
| Belarus     | 4         | 2.17%   |
| Mexico      | 3         | 1.63%   |
| Canada      | 3         | 1.63%   |
| Belgium     | 3         | 1.63%   |
| Turkey      | 2         | 1.09%   |
| South Korea | 2         | 1.09%   |
| Romania     | 2         | 1.09%   |
| Portugal    | 2         | 1.09%   |
| New Zealand | 2         | 1.09%   |
| Hungary     | 2         | 1.09%   |
| Greece      | 2         | 1.09%   |
| Denmark     | 2         | 1.09%   |
| Chile       | 2         | 1.09%   |
| Bolivia     | 2         | 1.09%   |
| Vietnam     | 1         | 0.54%   |
| Venezuela   | 1         | 0.54%   |
| Sweden      | 1         | 0.54%   |
| Slovenia    | 1         | 0.54%   |
| Serbia      | 1         | 0.54%   |
| Peru        | 1         | 0.54%   |
| Paraguay    | 1         | 0.54%   |
| Norway      | 1         | 0.54%   |
| Malaysia    | 1         | 0.54%   |
| Lithuania   | 1         | 0.54%   |
| Kenya       | 1         | 0.54%   |
| Kazakhstan  | 1         | 0.54%   |
| Japan       | 1         | 0.54%   |
| Ireland     | 1         | 0.54%   |
| Indonesia   | 1         | 0.54%   |
| India       | 1         | 0.54%   |
| Finland     | 1         | 0.54%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Moscow               | 6         | 3.21%   |
| St Petersburg        | 3         | 1.6%    |
| Berlin               | 3         | 1.6%    |
| San Jose             | 2         | 1.07%   |
| Rome                 | 2         | 1.07%   |
| Oruro                | 2         | 1.07%   |
| Nuremberg            | 2         | 1.07%   |
| Neasden              | 2         | 1.07%   |
| Munich               | 2         | 1.07%   |
| Miami                | 2         | 1.07%   |
| Krakow               | 2         | 1.07%   |
| Hrodna               | 2         | 1.07%   |
| Freiburg im Breisgau | 2         | 1.07%   |
| Auckland             | 2         | 1.07%   |
| Zaragoza             | 1         | 0.53%   |
| Yekaterinburg        | 1         | 0.53%   |
| Wroclaw              | 1         | 0.53%   |
| Weimar               | 1         | 0.53%   |
| Voronezh             | 1         | 0.53%   |
| Volos                | 1         | 0.53%   |
| Vilshofen            | 1         | 0.53%   |
| Vilnius              | 1         | 0.53%   |
| Viggianello          | 1         | 0.53%   |
| Viet Tri             | 1         | 0.53%   |
| Veurne               | 1         | 0.53%   |
| Vaslui               | 1         | 0.53%   |
| Vancouver            | 1         | 0.53%   |
| Valsoyfjord          | 1         | 0.53%   |
| Uiwang               | 1         | 0.53%   |
| Turku                | 1         | 0.53%   |
| Tula                 | 1         | 0.53%   |
| Troisdorf            | 1         | 0.53%   |
| Toyota               | 1         | 0.53%   |
| Toulouse             | 1         | 0.53%   |
| Toulon               | 1         | 0.53%   |
| Toronto              | 1         | 0.53%   |
| Tipton               | 1         | 0.53%   |
| Spearfish            | 1         | 0.53%   |
| Smolensk             | 1         | 0.53%   |
| Shrewsbury           | 1         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 28        | 31     | 12.23%  |
| WDC                            | 26        | 29     | 11.35%  |
| Seagate                        | 23        | 27     | 10.04%  |
| Unknown                        | 17        | 25     | 7.42%   |
| SanDisk                        | 16        | 20     | 6.99%   |
| Kingston                       | 10        | 10     | 4.37%   |
| Toshiba                        | 9         | 10     | 3.93%   |
| SK hynix                       | 8         | 8      | 3.49%   |
| Hitachi                        | 8         | 8      | 3.49%   |
| Intel                          | 7         | 7      | 3.06%   |
| Crucial                        | 6         | 7      | 2.62%   |
| A-DATA Technology              | 6         | 7      | 2.62%   |
| Micron Technology              | 5         | 5      | 2.18%   |
| Apple                          | 5         | 10     | 2.18%   |
| PNY                            | 4         | 5      | 1.75%   |
| HGST                           | 4         | 5      | 1.75%   |
| China                          | 4         | 5      | 1.75%   |
| Patriot                        | 3         | 3      | 1.31%   |
| Team                           | 2         | 2      | 0.87%   |
| Phison                         | 2         | 2      | 0.87%   |
| KIOXIA                         | 2         | 5      | 0.87%   |
| KingSpec                       | 2         | 2      | 0.87%   |
| Fujitsu                        | 2         | 2      | 0.87%   |
| Unknown                        | 2         | 2      | 0.87%   |
| Union Memory                   | 1         | 1      | 0.44%   |
| UMIS                           | 1         | 1      | 0.44%   |
| Transcend                      | 1         | 1      | 0.44%   |
| Star Drive                     | 1         | 1      | 0.44%   |
| SSD PHIS                       | 1         | 1      | 0.44%   |
| Solid State Storage Technology | 1         | 1      | 0.44%   |
| ShiJi                          | 1         | 1      | 0.44%   |
| SABRENT                        | 1         | 1      | 0.44%   |
| Oyen                           | 1         | 1      | 0.44%   |
| ORICO                          | 1         | 1      | 0.44%   |
| Microtech                      | 1         | 2      | 0.44%   |
| Micron/Crucial Technology      | 1         | 2      | 0.44%   |
| MAXSUN                         | 1         | 1      | 0.44%   |
| LITEON                         | 1         | 1      | 0.44%   |
| Lexar                          | 1         | 1      | 0.44%   |
| Intenso                        | 1         | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 7         | 2.97%   |
| Unknown SD/MMC/MS PRO 16GB           | 3         | 1.27%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 1.27%   |
| SanDisk NVMe SSD Drive 256GB         | 3         | 1.27%   |
| Kingston SA400S37480G 480GB SSD      | 3         | 1.27%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 0.85%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 2         | 0.85%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB | 2         | 0.85%   |
| Unknown SC128  128GB                 | 2         | 0.85%   |
| Unknown MMC Card  64GB               | 2         | 0.85%   |
| Unknown MMC Card  32GB               | 2         | 0.85%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.85%   |
| Seagate ST9250315AS 250GB            | 2         | 0.85%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 2         | 0.85%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB   | 2         | 0.85%   |
| Samsung SSD 980 1TB                  | 2         | 0.85%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.85%   |
| Samsung PM991a NVMe 512GB            | 2         | 0.85%   |
| Patriot Burst 240GB SSD              | 2         | 0.85%   |
| Micron NVMe SSD Drive 512GB          | 2         | 0.85%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 0.85%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.85%   |
| Crucial CT1000BX500SSD1 1TB          | 2         | 0.85%   |
| Apple SSD SD0128F 121GB              | 2         | 0.85%   |
| A-DATA SU650 240GB SSD               | 2         | 0.85%   |
| A-DATA ED600 1TB SSD                 | 2         | 0.85%   |
| Unknown                              | 2         | 0.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.42%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1         | 0.42%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.42%   |
| WDC WDBNCE5000PNC 500GB SSD          | 1         | 0.42%   |
| WDC WD7500BPVT-22HXZT3 752GB         | 1         | 0.42%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.42%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.42%   |
| WDC WD5000BPVX-00JC3T0 500GB         | 1         | 0.42%   |
| WDC WD5000BEVT-22A0RT0 500GB         | 1         | 0.42%   |
| WDC WD3200BEVT-60ZCT0 320GB          | 1         | 0.42%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.42%   |
| WDC WD30 EFRX-68EUZN0 3TB            | 1         | 0.42%   |
| WDC WD20SPZX-22UA7T0 2TB             | 1         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 27     | 35.38%  |
| WDC                 | 16        | 18     | 24.62%  |
| Hitachi             | 8         | 8      | 12.31%  |
| Toshiba             | 6         | 7      | 9.23%   |
| HGST                | 4         | 5      | 6.15%   |
| Unknown             | 3         | 3      | 4.62%   |
| Fujitsu             | 2         | 2      | 3.08%   |
| Samsung Electronics | 1         | 1      | 1.54%   |
| SABRENT             | 1         | 1      | 1.54%   |
| Intenso             | 1         | 1      | 1.54%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 14     | 14.12%  |
| Kingston            | 9         | 9      | 10.59%  |
| SanDisk             | 6         | 7      | 7.06%   |
| Crucial             | 6         | 7      | 7.06%   |
| A-DATA Technology   | 6         | 7      | 7.06%   |
| PNY                 | 4         | 5      | 4.71%   |
| Intel               | 4         | 4      | 4.71%   |
| China               | 4         | 5      | 4.71%   |
| Apple               | 4         | 4      | 4.71%   |
| WDC                 | 3         | 3      | 3.53%   |
| Patriot             | 3         | 3      | 3.53%   |
| Toshiba             | 2         | 2      | 2.35%   |
| Team                | 2         | 2      | 2.35%   |
| KingSpec            | 2         | 2      | 2.35%   |
| Unknown             | 2         | 2      | 2.35%   |
| Transcend           | 1         | 1      | 1.18%   |
| SSD PHIS            | 1         | 1      | 1.18%   |
| ORICO               | 1         | 1      | 1.18%   |
| Microtech           | 1         | 2      | 1.18%   |
| Micron Technology   | 1         | 1      | 1.18%   |
| LITEON              | 1         | 1      | 1.18%   |
| Lexar               | 1         | 1      | 1.18%   |
| Initio              | 1         | 1      | 1.18%   |
| HXY                 | 1         | 1      | 1.18%   |
| Gigabyte Technology | 1         | 2      | 1.18%   |
| FORESEE             | 1         | 2      | 1.18%   |
| Emtec               | 1         | 1      | 1.18%   |
| Corsair             | 1         | 1      | 1.18%   |
| BHT                 | 1         | 2      | 1.18%   |
| ASMT                | 1         | 1      | 1.18%   |
| Acer                | 1         | 1      | 1.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 76        | 96     | 35.68%  |
| HDD     | 62        | 73     | 29.11%  |
| NVMe    | 54        | 72     | 25.35%  |
| MMC     | 14        | 21     | 6.57%   |
| Unknown | 7         | 8      | 3.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 125       | 162    | 61.58%  |
| NVMe | 54        | 72     | 26.6%   |
| MMC  | 14        | 21     | 6.9%    |
| SAS  | 10        | 15     | 4.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 97        | 119    | 71.85%  |
| 0.51-1.0   | 33        | 44     | 24.44%  |
| 1.01-2.0   | 2         | 3      | 1.48%   |
| 3.01-4.0   | 1         | 1      | 0.74%   |
| 2.01-3.0   | 1         | 1      | 0.74%   |
| 4.01-10.0  | 1         | 1      | 0.74%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 67        | 36.22%  |
| 251-500        | 48        | 25.95%  |
| 501-1000       | 24        | 12.97%  |
| 1001-2000      | 12        | 6.49%   |
| 51-100         | 11        | 5.95%   |
| 21-50          | 10        | 5.41%   |
| 1-20           | 6         | 3.24%   |
| 2001-3000      | 5         | 2.7%    |
| More than 3000 | 2         | 1.08%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 91        | 47.15%  |
| 21-50     | 40        | 20.73%  |
| 101-250   | 22        | 11.4%   |
| 51-100    | 21        | 10.88%  |
| 501-1000  | 11        | 5.7%    |
| 251-500   | 7         | 3.63%   |
| 2001-3000 | 1         | 0.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 6.25%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 6.25%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 6.25%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 6.25%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 6.25%   |
| Seagate ST500LT032-1E9142 500GB       | 1         | 1      | 6.25%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 2      | 6.25%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 6.25%   |
| Samsung Electronics SSD 850 EVO 500GB | 1         | 1      | 6.25%   |
| Samsung Electronics HM160HC 160GB     | 1         | 1      | 6.25%   |
| Phison ES 512GB                       | 1         | 1      | 6.25%   |
| Intel SSDSCKKF256G8 SATA 256GB        | 1         | 1      | 6.25%   |
| Intel SSDSC2CT240A3 240GB             | 1         | 1      | 6.25%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 6.25%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 6.25%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 5      | 26.67%  |
| Seagate             | 2         | 2      | 13.33%  |
| Intel               | 2         | 2      | 13.33%  |
| Hitachi             | 2         | 2      | 13.33%  |
| WDC                 | 1         | 2      | 6.67%   |
| Toshiba             | 1         | 1      | 6.67%   |
| SK hynix            | 1         | 1      | 6.67%   |
| Phison              | 1         | 1      | 6.67%   |
| HGST                | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 28.57%  |
| Hitachi             | 2         | 2      | 28.57%  |
| WDC                 | 1         | 2      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| HGST                | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 7         | 8      | 46.67%  |
| SSD  | 5         | 5      | 33.33%  |
| NVMe | 3         | 4      | 20%     |

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
| Detected | 118       | 168    | 58.71%  |
| Works    | 68        | 85     | 33.83%  |
| Malfunc  | 15        | 17     | 7.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 126       | 59.43%  |
| AMD                            | 27        | 12.74%  |
| Samsung Electronics            | 16        | 7.55%   |
| SanDisk                        | 14        | 6.6%    |
| SK hynix                       | 8         | 3.77%   |
| Micron Technology              | 4         | 1.89%   |
| Phison Electronics             | 3         | 1.42%   |
| KIOXIA                         | 3         | 1.42%   |
| Union Memory (Shenzhen)        | 2         | 0.94%   |
| Marvell Technology Group       | 2         | 0.94%   |
| Toshiba America Info Systems   | 1         | 0.47%   |
| Solid State Storage Technology | 1         | 0.47%   |
| Nvidia                         | 1         | 0.47%   |
| Micron/Crucial Technology      | 1         | 0.47%   |
| Kingston Technology Company    | 1         | 0.47%   |
| Apple                          | 1         | 0.47%   |
| ADATA Technology               | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 23        | 9.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 6.06%   |
| Intel Volume Management Device NVMe RAID Controller                              | 13        | 5.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 13        | 5.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 12        | 5.19%   |
| Intel Tiger Lake-LP SATA Controller                                              | 10        | 4.33%   |
| Samsung NVMe SSD Controller 980                                                  | 9         | 3.9%    |
| SanDisk Non-Volatile memory controller                                           | 7         | 3.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 3.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 3.03%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 6         | 2.6%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 2.6%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 4         | 1.73%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 1.73%   |
| Micron Non-Volatile memory controller                                            | 4         | 1.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 1.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.73%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 4         | 1.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 1.73%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 3         | 1.3%    |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.3%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.3%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 3         | 1.3%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.3%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.87%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.87%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 2         | 0.87%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 0.87%   |
| Intel SSD 660P Series                                                            | 2         | 0.87%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.87%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.87%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.87%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.43%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 x4 NVMe SSD Controller                    | 1         | 0.43%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.43%   |
| Solid State Storage Non-Volatile memory controller                               | 1         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 130       | 57.78%  |
| NVMe | 55        | 24.44%  |
| RAID | 26        | 11.56%  |
| IDE  | 14        | 6.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 144       | 79.12%  |
| AMD    | 38        | 20.88%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 8         | 4.4%    |
| Intel Core i5-3230M CPU @ 2.60GHz            | 6         | 3.3%    |
| Intel Core i5-6200U CPU @ 2.30GHz            | 4         | 2.2%    |
| Intel Atom CPU N2600 @ 1.60GHz               | 4         | 2.2%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz      | 4         | 2.2%    |
| AMD Ryzen 5 5500U with Radeon Graphics       | 4         | 2.2%    |
| Intel Core i5-10210U CPU @ 1.60GHz           | 3         | 1.65%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz      | 3         | 1.65%   |
| AMD Ryzen 7 5700U with Radeon Graphics       | 3         | 1.65%   |
| Intel Pentium M processor 1.73GHz            | 2         | 1.1%    |
| Intel Pentium CPU P6000 @ 1.87GHz            | 2         | 1.1%    |
| Intel Pentium CPU N3700 @ 1.60GHz            | 2         | 1.1%    |
| Intel Core i7-8750H CPU @ 2.20GHz            | 2         | 1.1%    |
| Intel Core i7-7500U CPU @ 2.70GHz            | 2         | 1.1%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz           | 2         | 1.1%    |
| Intel Core i7-3612QM CPU @ 2.10GHz           | 2         | 1.1%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz            | 2         | 1.1%    |
| Intel Core i3-4010U CPU @ 1.70GHz            | 2         | 1.1%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz           | 2         | 1.1%    |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz         | 2         | 1.1%    |
| Intel Celeron N4000 CPU @ 1.10GHz            | 2         | 1.1%    |
| Intel Celeron CPU N3060 @ 1.60GHz            | 2         | 1.1%    |
| Intel Atom CPU N270 @ 1.60GHz                | 2         | 1.1%    |
| AMD Ryzen 5 5600H with Radeon Graphics       | 2         | 1.1%    |
| AMD Ryzen 3 3250U with Radeon Graphics       | 2         | 1.1%    |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G | 2         | 1.1%    |
| Intel Pentium Silver N6000 @ 1.10GHz         | 1         | 0.55%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz     | 1         | 0.55%   |
| Intel Pentium Gold 7505 @ 2.00GHz            | 1         | 0.55%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz  | 1         | 0.55%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz       | 1         | 0.55%   |
| Intel Pentium CPU P6100 @ 2.00GHz            | 1         | 0.55%   |
| Intel Pentium CPU N3710 @ 1.60GHz            | 1         | 0.55%   |
| Intel Pentium CPU B980 @ 2.40GHz             | 1         | 0.55%   |
| Intel Genuine CPU U7300 @ 1.30GHz            | 1         | 0.55%   |
| Intel Core i9-9880H CPU @ 2.30GHz            | 1         | 0.55%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 1         | 0.55%   |
| Intel Core i7-8565U CPU @ 1.80GHz            | 1         | 0.55%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 1         | 0.55%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz           | 1         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 35        | 19.23%  |
| Intel Core i7           | 24        | 13.19%  |
| Other                   | 20        | 10.99%  |
| Intel Core i3           | 17        | 9.34%   |
| Intel Celeron           | 11        | 6.04%   |
| Intel Core 2 Duo        | 10        | 5.49%   |
| AMD Ryzen 5             | 10        | 5.49%   |
| Intel Atom              | 9         | 4.95%   |
| AMD Ryzen 7             | 8         | 4.4%    |
| Intel Pentium           | 7         | 3.85%   |
| AMD Ryzen 3             | 3         | 1.65%   |
| Intel Pentium Silver    | 2         | 1.1%    |
| Intel Pentium M         | 2         | 1.1%    |
| Intel Celeron M         | 2         | 1.1%    |
| AMD E2                  | 2         | 1.1%    |
| AMD E1                  | 2         | 1.1%    |
| AMD A4                  | 2         | 1.1%    |
| AMD A10                 | 2         | 1.1%    |
| Intel Pentium Gold      | 1         | 0.55%   |
| Intel Pentium Dual-Core | 1         | 0.55%   |
| Intel Pentium Dual      | 1         | 0.55%   |
| Intel Genuine           | 1         | 0.55%   |
| Intel Core i9           | 1         | 0.55%   |
| Intel Core 2 Extreme    | 1         | 0.55%   |
| Intel Core 2            | 1         | 0.55%   |
| AMD Ryzen 9             | 1         | 0.55%   |
| AMD E                   | 1         | 0.55%   |
| AMD C-50                | 1         | 0.55%   |
| AMD Athlon II           | 1         | 0.55%   |
| AMD Athlon              | 1         | 0.55%   |
| AMD A8                  | 1         | 0.55%   |
| AMD A6                  | 1         | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 104       | 57.14%  |
| 4      | 47        | 25.82%  |
| 6      | 12        | 6.59%   |
| 8      | 10        | 5.49%   |
| 1      | 8         | 4.4%    |
| 12     | 1         | 0.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 182       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 127       | 69.78%  |
| 1      | 55        | 30.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 175       | 96.15%  |
| 32-bit         | 7         | 3.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 16        | 8.6%    |
| 0x306a9    | 14        | 7.53%   |
| 0x406e3    | 9         | 4.84%   |
| 0x40651    | 9         | 4.84%   |
| Unknown    | 9         | 4.84%   |
| 0x08608103 | 7         | 3.76%   |
| 0x806ec    | 6         | 3.23%   |
| 0x6fd      | 6         | 3.23%   |
| 0x206a7    | 6         | 3.23%   |
| 0x08108109 | 6         | 3.23%   |
| 0x806e9    | 5         | 2.69%   |
| 0x406c4    | 5         | 2.69%   |
| 0x306c3    | 5         | 2.69%   |
| 0x1067a    | 5         | 2.69%   |
| 0x30661    | 4         | 2.15%   |
| 0x06006705 | 4         | 2.15%   |
| 0x906ea    | 3         | 1.61%   |
| 0x806ea    | 3         | 1.61%   |
| 0x706a1    | 3         | 1.61%   |
| 0x20655    | 3         | 1.61%   |
| 0x20652    | 3         | 1.61%   |
| 0x106e5    | 3         | 1.61%   |
| 0x106c2    | 3         | 1.61%   |
| 0x10676    | 3         | 1.61%   |
| 0x0a50000c | 3         | 1.61%   |
| 0xa0652    | 2         | 1.08%   |
| 0x706e5    | 2         | 1.08%   |
| 0x6f6      | 2         | 1.08%   |
| 0x6d8      | 2         | 1.08%   |
| 0x506e3    | 2         | 1.08%   |
| 0x406c3    | 2         | 1.08%   |
| 0x306d4    | 2         | 1.08%   |
| 0x30678    | 2         | 1.08%   |
| 0x0a50000d | 2         | 1.08%   |
| 0x06001119 | 2         | 1.08%   |
| 0x906ed    | 1         | 0.54%   |
| 0x906e9    | 1         | 0.54%   |
| 0x906c0    | 1         | 0.54%   |
| 0x806eb    | 1         | 0.54%   |
| 0x806d1    | 1         | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 20        | 10.93%  |
| TigerLake     | 17        | 9.29%   |
| IvyBridge     | 14        | 7.65%   |
| Haswell       | 14        | 7.65%   |
| Skylake       | 11        | 6.01%   |
| Silvermont    | 10        | 5.46%   |
| Unknown       | 10        | 5.46%   |
| Penryn        | 8         | 4.37%   |
| Core          | 8         | 4.37%   |
| Bonnell       | 8         | 4.37%   |
| Zen+          | 7         | 3.83%   |
| Westmere      | 7         | 3.83%   |
| Zen 3         | 6         | 3.28%   |
| SandyBridge   | 6         | 3.28%   |
| Excavator     | 6         | 3.28%   |
| Goldmont plus | 4         | 2.19%   |
| P6            | 3         | 1.64%   |
| Nehalem       | 3         | 1.64%   |
| IceLake       | 3         | 1.64%   |
| Broadwell     | 3         | 1.64%   |
| Zen 2         | 2         | 1.09%   |
| Puma          | 2         | 1.09%   |
| Piledriver    | 2         | 1.09%   |
| Jaguar        | 2         | 1.09%   |
| CometLake     | 2         | 1.09%   |
| Bobcat        | 2         | 1.09%   |
| Tremont       | 1         | 0.55%   |
| K10           | 1         | 0.55%   |
| Goldmont      | 1         | 0.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 127       | 59.07%  |
| AMD    | 45        | 20.93%  |
| Nvidia | 43        | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 5.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 5.31%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 3.98%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 3.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 3.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 3.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 3.1%    |
| AMD Lucienne                                                                             | 7         | 3.1%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 5         | 2.21%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 2.21%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 2.21%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 2.21%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.77%   |
| Intel HD Graphics 620                                                                    | 4         | 1.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.77%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 1.77%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.77%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 1.33%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.33%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.33%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 1.33%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.33%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 3         | 1.33%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.88%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 2         | 0.88%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.88%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.88%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 0.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.88%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.88%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 0.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.88%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 97        | 53.3%   |
| 1 x AMD        | 35        | 19.23%  |
| Intel + Nvidia | 27        | 14.84%  |
| 1 x Nvidia     | 13        | 7.14%   |
| 2 x AMD        | 4         | 2.2%    |
| Intel + AMD    | 3         | 1.65%   |
| AMD + Nvidia   | 3         | 1.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 166       | 90.22%  |
| Proprietary | 11        | 5.98%   |
| Unknown     | 7         | 3.8%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 113       | 61.08%  |
| 0.01-0.5   | 32        | 17.3%   |
| 1.01-2.0   | 21        | 11.35%  |
| 0.51-1.0   | 9         | 4.86%   |
| 3.01-4.0   | 7         | 3.78%   |
| 5.01-6.0   | 2         | 1.08%   |
| 2.01-3.0   | 1         | 0.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 38        | 20%     |
| LG Display              | 30        | 15.79%  |
| Chimei Innolux          | 28        | 14.74%  |
| BOE                     | 24        | 12.63%  |
| Samsung Electronics     | 13        | 6.84%   |
| Apple                   | 7         | 3.68%   |
| Sharp                   | 5         | 2.63%   |
| LG Philips              | 5         | 2.63%   |
| InfoVision              | 5         | 2.63%   |
| Chi Mei Optoelectronics | 5         | 2.63%   |
| Goldstar                | 4         | 2.11%   |
| Lenovo                  | 3         | 1.58%   |
| HannStar                | 3         | 1.58%   |
| Dell                    | 3         | 1.58%   |
| SLD                     | 2         | 1.05%   |
| PANDA                   | 2         | 1.05%   |
| Vestel Elektronik       | 1         | 0.53%   |
| TR_                     | 1         | 0.53%   |
| Sceptre Tech            | 1         | 0.53%   |
| Quanta Display          | 1         | 0.53%   |
| Planar                  | 1         | 0.53%   |
| Philips                 | 1         | 0.53%   |
| Panasonic               | 1         | 0.53%   |
| Packard Bell            | 1         | 0.53%   |
| Insignia                | 1         | 0.53%   |
| HKC                     | 1         | 0.53%   |
| Hewlett-Packard         | 1         | 0.53%   |
| DENON                   | 1         | 0.53%   |
| Acer                    | 1         | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 3         | 1.57%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 1.57%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch        | 3         | 1.57%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.57%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                  | 2         | 1.05%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch  | 2         | 1.05%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch           | 2         | 1.05%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 1.05%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch           | 2         | 1.05%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 1.05%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 1.05%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.05%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch       | 2         | 1.05%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch      | 2         | 1.05%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 1.05%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 1.05%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 2         | 1.05%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                      | 1         | 0.52%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                  | 1         | 0.52%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.52%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 0.52%   |
| Sharp LQ133M1JW02 SHP141A 1920x1080 294x165mm 13.3-inch               | 1         | 0.52%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 1         | 0.52%   |
| Sharp LCD Monitor SHP141B 1920x1080 294x165mm 13.3-inch               | 1         | 0.52%   |
| Sceptre Tech Sceptre B34 SPT0D52 2560x1080 797x334mm 34.0-inch        | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                     | 1         | 0.52%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.52%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.52%   |
| Quanta Display LCD Monitor QDS004B 1280x800 331x207mm 15.4-inch       | 1         | 0.52%   |
| Planar PLL2210W PLN2210 1920x1080 476x268mm 21.5-inch                 | 1         | 0.52%   |
| Philips PHL 241B7Q PHL0909 1920x1080 527x296mm 23.8-inch              | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 76        | 41.3%   |
| 1366x768 (WXGA)   | 60        | 32.61%  |
| 1600x900 (HD+)    | 9         | 4.89%   |
| 1920x1200 (WUXGA) | 7         | 3.8%    |
| 1280x800 (WXGA)   | 7         | 3.8%    |
| 1024x600          | 6         | 3.26%   |
| 3840x2160 (4K)    | 5         | 2.72%   |
| 1440x900 (WXGA+)  | 4         | 2.17%   |
| 2880x1800         | 2         | 1.09%   |
| 1280x1024 (SXGA)  | 2         | 1.09%   |
| 2560x1600         | 1         | 0.54%   |
| 2560x1440 (QHD)   | 1         | 0.54%   |
| 2560x1080         | 1         | 0.54%   |
| 2256x1504         | 1         | 0.54%   |
| 1280x768          | 1         | 0.54%   |
| 1280x720 (HD)     | 1         | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 92        | 48.17%  |
| 13      | 28        | 14.66%  |
| 14      | 19        | 9.95%   |
| 17      | 14        | 7.33%   |
| 24      | 7         | 3.66%   |
| 10      | 6         | 3.14%   |
| 12      | 4         | 2.09%   |
| 11      | 4         | 2.09%   |
| 23      | 3         | 1.57%   |
| Unknown | 3         | 1.57%   |
| 27      | 2         | 1.05%   |
| 21      | 2         | 1.05%   |
| 84      | 1         | 0.52%   |
| 72      | 1         | 0.52%   |
| 40      | 1         | 0.52%   |
| 34      | 1         | 0.52%   |
| 31      | 1         | 0.52%   |
| 16      | 1         | 0.52%   |
| 8       | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 125       | 66.49%  |
| 201-300     | 27        | 14.36%  |
| 351-400     | 14        | 7.45%   |
| 501-600     | 11        | 5.85%   |
| Unknown     | 3         | 1.6%    |
| 401-500     | 2         | 1.06%   |
| 1501-2000   | 2         | 1.06%   |
| 801-900     | 1         | 0.53%   |
| 701-800     | 1         | 0.53%   |
| 601-700     | 1         | 0.53%   |
| 101-200     | 1         | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 150       | 83.8%   |
| 16/10   | 23        | 12.85%  |
| 5/4     | 2         | 1.12%   |
| Unknown | 2         | 1.12%   |
| 3/2     | 1         | 0.56%   |
| 21/9    | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 92        | 48.17%  |
| 81-90          | 35        | 18.32%  |
| 71-80          | 12        | 6.28%   |
| 121-130        | 9         | 4.71%   |
| 201-250        | 8         | 4.19%   |
| 41-50          | 6         | 3.14%   |
| 61-70          | 4         | 2.09%   |
| 51-60          | 4         | 2.09%   |
| 251-300        | 4         | 2.09%   |
| 131-140        | 3         | 1.57%   |
| Unknown        | 3         | 1.57%   |
| More than 1000 | 2         | 1.05%   |
| 351-500        | 2         | 1.05%   |
| 301-350        | 2         | 1.05%   |
| 141-150        | 2         | 1.05%   |
| 1-40           | 1         | 0.52%   |
| 501-1000       | 1         | 0.52%   |
| 91-100         | 1         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 78        | 41.05%  |
| 101-120       | 67        | 35.26%  |
| 51-100        | 27        | 14.21%  |
| 161-240       | 11        | 5.79%   |
| More than 240 | 3         | 1.58%   |
| Unknown       | 3         | 1.58%   |
| 1-50          | 1         | 0.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 161       | 87.03%  |
| 2     | 16        | 8.65%   |
| 0     | 7         | 3.78%   |
| 3     | 1         | 0.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 95        | 34.93%  |
| Intel                         | 82        | 30.15%  |
| Qualcomm Atheros              | 40        | 14.71%  |
| Broadcom                      | 23        | 8.46%   |
| Broadcom Limited              | 6         | 2.21%   |
| TP-Link                       | 4         | 1.47%   |
| MediaTek                      | 3         | 1.1%    |
| Marvell Technology Group      | 3         | 1.1%    |
| Xiaomi                        | 2         | 0.74%   |
| Ralink Technology             | 2         | 0.74%   |
| Spreadtrum Communications     | 1         | 0.37%   |
| Sierra Wireless               | 1         | 0.37%   |
| Ralink                        | 1         | 0.37%   |
| OnePlus Technology (Shenzhen) | 1         | 0.37%   |
| Nvidia                        | 1         | 0.37%   |
| Lenovo                        | 1         | 0.37%   |
| JMicron Technology            | 1         | 0.37%   |
| Hewlett-Packard               | 1         | 0.37%   |
| Google                        | 1         | 0.37%   |
| Edimax Technology             | 1         | 0.37%   |
| Dell                          | 1         | 0.37%   |
| Davicom Semiconductor         | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 13.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 5.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 14        | 4.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 2.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 2.33%   |
| Intel Wireless 8265 / 8275                                        | 8         | 2.33%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 2.33%   |
| Intel Wireless 8260                                               | 6         | 1.75%   |
| Intel Wireless 7260                                               | 6         | 1.75%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 1.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.46%   |
| Intel Wireless 3165                                               | 5         | 1.46%   |
| Intel Ethernet Connection I219-V                                  | 5         | 1.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.46%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 4         | 1.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 1.17%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 1.17%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.87%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.87%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.87%   |
| Intel Wireless 7265                                               | 3         | 0.87%   |
| Intel WiFi Link 5100                                              | 3         | 0.87%   |
| Intel Ultimate N WiFi Link 5300                                   | 3         | 0.87%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 0.87%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 0.87%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.87%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 2         | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.58%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.58%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.58%   |
| Realtek RTL8187B Wireless Adapter                                 | 2         | 0.58%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 78        | 41.49%  |
| Realtek Semiconductor | 45        | 23.94%  |
| Qualcomm Atheros      | 30        | 15.96%  |
| Broadcom              | 18        | 9.57%   |
| Broadcom Limited      | 5         | 2.66%   |
| TP-Link               | 4         | 2.13%   |
| Ralink Technology     | 2         | 1.06%   |
| MediaTek              | 2         | 1.06%   |
| Xiaomi                | 1         | 0.53%   |
| Sierra Wireless       | 1         | 0.53%   |
| Ralink                | 1         | 0.53%   |
| Edimax Technology     | 1         | 0.53%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 7.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 4.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 4.15%   |
| Intel Wireless 8265 / 8275                                              | 8         | 4.15%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 4.15%   |
| Intel Wireless 8260                                                     | 6         | 3.11%   |
| Intel Wireless 7260                                                     | 6         | 3.11%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 3.11%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 3.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.59%   |
| Intel Wireless 3165                                                     | 5         | 2.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 2.59%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 4         | 2.07%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 2.07%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.55%   |
| Intel Wireless 7265                                                     | 3         | 1.55%   |
| Intel WiFi Link 5100                                                    | 3         | 1.55%   |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 1.55%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 1.55%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.55%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 2         | 1.04%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.04%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.04%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 1.04%   |
| Realtek RTL8187B Wireless Adapter                                       | 2         | 1.04%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 1.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 2         | 1.04%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.04%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 1.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.04%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 1.04%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.04%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 2         | 1.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.04%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.04%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 76        | 51.35%  |
| Intel                         | 34        | 22.97%  |
| Qualcomm Atheros              | 18        | 12.16%  |
| Broadcom                      | 6         | 4.05%   |
| Marvell Technology Group      | 3         | 2.03%   |
| Xiaomi                        | 1         | 0.68%   |
| Spreadtrum Communications     | 1         | 0.68%   |
| OnePlus Technology (Shenzhen) | 1         | 0.68%   |
| Nvidia                        | 1         | 0.68%   |
| MediaTek                      | 1         | 0.68%   |
| Lenovo                        | 1         | 0.68%   |
| JMicron Technology            | 1         | 0.68%   |
| Hewlett-Packard               | 1         | 0.68%   |
| Google                        | 1         | 0.68%   |
| Davicom Semiconductor         | 1         | 0.68%   |
| Broadcom Limited              | 1         | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 31.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 13.51%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 3.38%   |
| Intel Ethernet Connection I219-V                                  | 5         | 3.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 2.7%    |
| Intel 82567LM Gigabit Network Connection                          | 4         | 2.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 2.03%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 2.03%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.03%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 2.03%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.35%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.35%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 1.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 1.35%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 1.35%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.35%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.35%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.35%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.35%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.68%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.68%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.68%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.68%   |
| OnePlus (Shenzhen) Android                                        | 1         | 0.68%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 1         | 0.68%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.68%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.68%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.68%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.68%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.68%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.68%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 179       | 55.59%  |
| Ethernet | 141       | 43.79%  |
| Modem    | 2         | 0.62%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 135       | 70.68%  |
| Ethernet | 56        | 29.32%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 128       | 70.33%  |
| 1     | 47        | 25.82%  |
| 0     | 7         | 3.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 123       | 67.58%  |
| Yes  | 59        | 32.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 42.97%  |
| Realtek Semiconductor           | 29        | 22.66%  |
| Foxconn / Hon Hai               | 9         | 7.03%   |
| Qualcomm Atheros Communications | 6         | 4.69%   |
| Lite-On Technology              | 5         | 3.91%   |
| Broadcom                        | 5         | 3.91%   |
| Apple                           | 5         | 3.91%   |
| Hewlett-Packard                 | 4         | 3.13%   |
| Dell                            | 4         | 3.13%   |
| IMC Networks                    | 3         | 2.34%   |
| Foxconn International           | 2         | 1.56%   |
| Cambridge Silicon Radio         | 1         | 0.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 26        | 20.31%  |
| Realtek Bluetooth Radio                                     | 20        | 15.63%  |
| Intel AX201 Bluetooth                                       | 12        | 9.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 9         | 7.03%   |
| Realtek  Bluetooth 4.2 Adapter                              | 5         | 3.91%   |
| Intel AX200 Bluetooth                                       | 5         | 3.91%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 2.34%   |
| Foxconn / Hon Hai Wireless_Device                           | 3         | 2.34%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 1.56%   |
| Qualcomm Atheros  Bluetooth Device                          | 2         | 1.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 1.56%   |
| HP Broadcom 2070 Bluetooth Combo                            | 2         | 1.56%   |
| Foxconn International BCM43142A0 Bluetooth module           | 2         | 1.56%   |
| Foxconn / Hon Hai Bluetooth Device                          | 2         | 1.56%   |
| Dell Wireless 370 Bluetooth Mini-card                       | 2         | 1.56%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.56%   |
| Apple Bluetooth USB Host Controller                         | 2         | 1.56%   |
| Apple Bluetooth Host Controller                             | 2         | 1.56%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.78%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.78%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.78%   |
| Lite-On Bluetooth Device                                    | 1         | 0.78%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 0.78%   |
| Intel AX210 Bluetooth                                       | 1         | 0.78%   |
| IMC Networks Bluetooth Radio                                | 1         | 0.78%   |
| IMC Networks Bluetooth Device                               | 1         | 0.78%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.78%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.78%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.78%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller             | 1         | 0.78%   |
| Foxconn / Hon Hai BCM43142A0                                | 1         | 0.78%   |
| Foxconn / Hon Hai Acer Module                               | 1         | 0.78%   |
| Foxconn / Hon Hai Acer Bluetooth module                     | 1         | 0.78%   |
| Dell Broadcom BCM20702A0 Bluetooth                          | 1         | 0.78%   |
| Dell BCM20702A0 Bluetooth Module                            | 1         | 0.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 0.78%   |
| Broadcom HP Portable SoftSailing                            | 1         | 0.78%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                        | 1         | 0.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 141       | 65.89%  |
| AMD                   | 46        | 21.5%   |
| Nvidia                | 21        | 9.81%   |
| Texas Instruments     | 2         | 0.93%   |
| Yamaha                | 1         | 0.47%   |
| Realtek Semiconductor | 1         | 0.47%   |
| GN Netcom             | 1         | 0.47%   |
| Audioengine           | 1         | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 23        | 8.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 17        | 6.42%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 6.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 16        | 6.04%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 13        | 4.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 3.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 3.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 3.77%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 3.4%    |
| Intel 8 Series HD Audio Controller                                                                | 9         | 3.4%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 2.26%   |
| AMD FCH Azalia Controller                                                                         | 6         | 2.26%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 2.26%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.89%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.89%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.51%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.51%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 1.51%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.13%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 1.13%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.13%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 1.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.13%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.13%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.13%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 1.13%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.75%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.75%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.75%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.75%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 27        | 30%     |
| SK hynix                     | 20        | 22.22%  |
| Unknown                      | 11        | 12.22%  |
| Micron Technology            | 8         | 8.89%   |
| Kingston                     | 6         | 6.67%   |
| Unknown (ABCD)               | 2         | 2.22%   |
| Ramaxel Technology           | 2         | 2.22%   |
| Nanya Technology             | 2         | 2.22%   |
| G.Skill                      | 2         | 2.22%   |
| Crucial                      | 2         | 2.22%   |
| A-DATA Technology            | 2         | 2.22%   |
| Strontium                    | 1         | 1.11%   |
| Patriot Memory (PDP Systems) | 1         | 1.11%   |
| Lexar Co Limited             | 1         | 1.11%   |
| GSkill                       | 1         | 1.11%   |
| Corsair                      | 1         | 1.11%   |
| Unknown                      | 1         | 1.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                               | 2         | 2.08%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s          | 2         | 2.08%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                     | 2         | 2.08%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s                  | 2         | 2.08%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 2.08%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                               | 1         | 1.04%   |
| Unknown RAM Module 8GB SODIMM DDR3                                        | 1         | 1.04%   |
| Unknown RAM Module 512MB SODIMM DDR                                       | 1         | 1.04%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                               | 1         | 1.04%   |
| Unknown RAM Module 2GB SODIMM SDRAM                                       | 1         | 1.04%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 1         | 1.04%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                                | 1         | 1.04%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                       | 1         | 1.04%   |
| Unknown RAM Module 1GB SODIMM DDR2                                        | 1         | 1.04%   |
| Unknown RAM Module 1GB SODIMM DDR                                         | 1         | 1.04%   |
| Strontium RAM SRT4G86S0-H9H 4GB SODIMM DDR3 1067MT/s                      | 1         | 1.04%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                             | 1         | 1.04%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                              | 1         | 1.04%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                             | 1         | 1.04%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s                      | 1         | 1.04%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.04%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.04%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                    | 1         | 1.04%   |
| SK hynix RAM HMT425S6AFR6A-H9 2GB SODIMM DDR3 1333MT/s                    | 1         | 1.04%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.04%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.04%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 1.04%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 1         | 1.04%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s                 | 1         | 1.04%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                    | 1         | 1.04%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s                    | 1         | 1.04%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.04%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s                    | 1         | 1.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 1         | 1.04%   |
| SK hynix RAM 161616161616161616161616161616161616 1GB SODIMM DDR2 667MT/s | 1         | 1.04%   |
| SK hynix RAM 0C0C0C0C0C0C0C0C0C0C0C0C0C0C0C0C0C0C 1GB SODIMM DDR2 667MT/s | 1         | 1.04%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                               | 1         | 1.04%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                              | 1         | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 38        | 47.5%   |
| DDR3   | 27        | 33.75%  |
| DDR2   | 6         | 7.5%    |
| SDRAM  | 4         | 5%      |
| LPDDR4 | 3         | 3.75%   |
| LPDDR3 | 1         | 1.25%   |
| DDR    | 1         | 1.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 77        | 95.06%  |
| Row Of Chips | 3         | 3.7%    |
| Unknown      | 1         | 1.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 31        | 35.63%  |
| 4096  | 21        | 24.14%  |
| 2048  | 19        | 21.84%  |
| 16384 | 9         | 10.34%  |
| 32768 | 3         | 3.45%   |
| 1024  | 3         | 3.45%   |
| 512   | 1         | 1.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 22        | 26.51%  |
| 1600    | 17        | 20.48%  |
| 2667    | 12        | 14.46%  |
| 2400    | 7         | 8.43%   |
| 667     | 4         | 4.82%   |
| Unknown | 4         | 4.82%   |
| 1334    | 3         | 3.61%   |
| 1067    | 3         | 3.61%   |
| 4199    | 2         | 2.41%   |
| 4267    | 1         | 1.2%    |
| 3266    | 1         | 1.2%    |
| 2267    | 1         | 1.2%    |
| 2133    | 1         | 1.2%    |
| 2048    | 1         | 1.2%    |
| 1867    | 1         | 1.2%    |
| 1333    | 1         | 1.2%    |
| 1200    | 1         | 1.2%    |
| 533     | 1         | 1.2%    |

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
| Chicony Electronics                    | 33        | 21.57%  |
| Microdia                               | 17        | 11.11%  |
| IMC Networks                           | 16        | 10.46%  |
| Acer                                   | 12        | 7.84%   |
| Suyin                                  | 11        | 7.19%   |
| Realtek Semiconductor                  | 10        | 6.54%   |
| Quanta                                 | 10        | 6.54%   |
| Sunplus Innovation Technology          | 7         | 4.58%   |
| Luxvisions Innotech Limited            | 7         | 4.58%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.92%   |
| Alcor Micro                            | 4         | 2.61%   |
| Apple                                  | 3         | 1.96%   |
| Syntek                                 | 2         | 1.31%   |
| Silicon Motion                         | 2         | 1.31%   |
| Lenovo                                 | 2         | 1.31%   |
| Importek                               | 2         | 1.31%   |
| Bison Electronics                      | 2         | 1.31%   |
| Z-Star Microelectronics                | 1         | 0.65%   |
| Lite-On Technology                     | 1         | 0.65%   |
| Intel                                  | 1         | 0.65%   |
| icSpring                               | 1         | 0.65%   |
| eMPIA Technology                       | 1         | 0.65%   |
| DLEQNA19IFK6G2                         | 1         | 0.65%   |
| ALi                                    | 1         | 0.65%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                        | 10        | 6.54%   |
| Chicony Integrated Camera                            | 9         | 5.88%   |
| Acer Integrated Camera                               | 7         | 4.58%   |
| IMC Networks Integrated Camera                       | 4         | 2.61%   |
| Chicony HP TrueVision HD Camera                      | 4         | 2.61%   |
| Chicony HD WebCam                                    | 4         | 2.61%   |
| Realtek MTD camera                                   | 3         | 1.96%   |
| Realtek Lenovo EasyCamera                            | 3         | 1.96%   |
| Quanta HP TrueVision HD Camera                       | 3         | 1.96%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 3         | 1.96%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 3         | 1.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 3         | 1.96%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 3         | 1.96%   |
| Syntek Integrated Camera                             | 2         | 1.31%   |
| Suyin HP TrueVision HD                               | 2         | 1.31%   |
| Suyin Acer HD Crystal Eye webcam                     | 2         | 1.31%   |
| Sunplus HD WebCam                                    | 2         | 1.31%   |
| Quanta HP Webcam                                     | 2         | 1.31%   |
| Quanta HP HD Camera                                  | 2         | 1.31%   |
| Microdia CameraA                                     | 2         | 1.31%   |
| IMC Networks EasyCamera                              | 2         | 1.31%   |
| Chicony HP HD Camera                                 | 2         | 1.31%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam     | 2         | 1.31%   |
| Bison USB2.0 Camera                                  | 2         | 1.31%   |
| Alcor Micro USB Camera                               | 2         | 1.31%   |
| Z-Star WebCam SC-03FFL11739P                         | 1         | 0.65%   |
| Suyin Lenovo EasyCamera                              | 1         | 0.65%   |
| Suyin Integrated_Webcam_HD                           | 1         | 0.65%   |
| Suyin HP Webcam-101                                  | 1         | 0.65%   |
| Suyin HD WebCam                                      | 1         | 0.65%   |
| Suyin Acer/Lenovo Webcam [CN0316]                    | 1         | 0.65%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 0.65%   |
| Suyin 1.3M HD WebCam                                 | 1         | 0.65%   |
| Sunplus USB Camera                                   | 1         | 0.65%   |
| Sunplus Laptop Integrated Webcam FHD                 | 1         | 0.65%   |
| Sunplus HP TrueVision HD Camera                      | 1         | 0.65%   |
| Sunplus Aukey-PC-LM1E Camera                         | 1         | 0.65%   |
| Sunplus 1.3M HD WebCam                               | 1         | 0.65%   |
| Silicon Motion WebCam SC-0311139N                    | 1         | 0.65%   |
| Silicon Motion 300k Pixel Camera                     | 1         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 48%     |
| AuthenTec                  | 3         | 12%     |
| Synaptics                  | 2         | 8%      |
| Shenzhen Goodix Technology | 2         | 8%      |
| Upek                       | 1         | 4%      |
| STMicroelectronics         | 1         | 4%      |
| Microsoft                  | 1         | 4%      |
| LighTuning Technology      | 1         | 4%      |
| Focal-systems.Corp         | 1         | 4%      |
| Elan Microelectronics      | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 12%     |
| Validity Sensors Synaptics WBDI                        | 2         | 8%      |
| Shenzhen Goodix  FingerPrint Device                    | 2         | 8%      |
| AuthenTec AES1600                                      | 2         | 8%      |
| Unknown                                                | 2         | 8%      |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4%      |
| Validity Sensors VFS491                                | 1         | 4%      |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 4%      |
| Validity Sensors VFS301 Fingerprint Reader             | 1         | 4%      |
| Validity Sensors VFS Fingerprint sensor                | 1         | 4%      |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4%      |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4%      |
| STMicroelectronics Fingerprint Reader                  | 1         | 4%      |
| Microsoft Fingerprint Reader                           | 1         | 4%      |
| LighTuning Fingerprint Reader                          | 1         | 4%      |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 4%      |
| Elan ELAN:Fingerprint                                  | 1         | 4%      |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 50%     |
| O2 Micro    | 2         | 20%     |
| Alcor Micro | 2         | 20%     |
| Lenovo      | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 30%     |
| O2 Micro OZ776 CCID Smartcard Reader           | 2         | 20%     |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 20%     |
| Lenovo Integrated Smart Card Reader            | 1         | 10%     |
| Broadcom 5880                                  | 1         | 10%     |
| Broadcom 58200                                 | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 121       | 64.71%  |
| 1     | 53        | 28.34%  |
| 2     | 11        | 5.88%   |
| 4     | 1         | 0.53%   |
| 3     | 1         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 24        | 29.63%  |
| Net/wireless             | 18        | 22.22%  |
| Multimedia controller    | 13        | 16.05%  |
| Graphics card            | 12        | 14.81%  |
| Chipcard                 | 9         | 11.11%  |
| Communication controller | 2         | 2.47%   |
| Dvb card                 | 1         | 1.23%   |
| Card reader              | 1         | 1.23%   |
| Bluetooth                | 1         | 1.23%   |

