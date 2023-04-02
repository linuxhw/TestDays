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

Total: 283

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Medion        | E6214                       | [5766389c97](https://linux-hardware.org/?probe=5766389c97) | Apr 01, 2023 |
| Acer          | Aspire A514-53              | [4bb2babc0a](https://linux-hardware.org/?probe=4bb2babc0a) | Mar 31, 2023 |
| Medion        | E6214                       | [298e2f9c69](https://linux-hardware.org/?probe=298e2f9c69) | Mar 31, 2023 |
| HP            | Pavilion dm4                | [b7f2f9e2ab](https://linux-hardware.org/?probe=b7f2f9e2ab) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [976d8a1a13](https://linux-hardware.org/?probe=976d8a1a13) | Mar 30, 2023 |
| HP            | Pavilion Notebook           | [3844e429b1](https://linux-hardware.org/?probe=3844e429b1) | Mar 30, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [e7e49e22ba](https://linux-hardware.org/?probe=e7e49e22ba) | Mar 30, 2023 |
| HP            | Pavilion Notebook           | [9cb1834208](https://linux-hardware.org/?probe=9cb1834208) | Mar 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [701b74ce3e](https://linux-hardware.org/?probe=701b74ce3e) | Mar 27, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [6ac9c53a7e](https://linux-hardware.org/?probe=6ac9c53a7e) | Mar 26, 2023 |
| Medion        | E6214                       | [8ff346be04](https://linux-hardware.org/?probe=8ff346be04) | Mar 26, 2023 |
| Haier         | S15                         | [497105206c](https://linux-hardware.org/?probe=497105206c) | Mar 25, 2023 |
| Acer          | Aspire E1-572G              | [ce4febfe16](https://linux-hardware.org/?probe=ce4febfe16) | Mar 25, 2023 |
| Haier         | S15                         | [083feb0355](https://linux-hardware.org/?probe=083feb0355) | Mar 25, 2023 |
| Toshiba       | Satellite Pro A50-C         | [2fe9003124](https://linux-hardware.org/?probe=2fe9003124) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | [95c5c45220](https://linux-hardware.org/?probe=95c5c45220) | Mar 24, 2023 |
| Star Labs     | StarBook                    | [b3957ad08f](https://linux-hardware.org/?probe=b3957ad08f) | Mar 22, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [2a3bb3e212](https://linux-hardware.org/?probe=2a3bb3e212) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [56fab2cb17](https://linux-hardware.org/?probe=56fab2cb17) | Mar 18, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [f7727e4bcb](https://linux-hardware.org/?probe=f7727e4bcb) | Mar 17, 2023 |
| Acer          | Swift SF314-51              | [b410a4c017](https://linux-hardware.org/?probe=b410a4c017) | Mar 14, 2023 |
| HP            | Pavilion dv6                | [f649c78020](https://linux-hardware.org/?probe=f649c78020) | Mar 13, 2023 |
| Lenovo        | ThinkPad X230 2325Y2S       | [7f15f7ce79](https://linux-hardware.org/?probe=7f15f7ce79) | Mar 12, 2023 |
| Dell          | Inspiron 5515               | [22dd14abae](https://linux-hardware.org/?probe=22dd14abae) | Mar 11, 2023 |
| Dynabook      | Satellite Pro C50-G         | [835785f6a7](https://linux-hardware.org/?probe=835785f6a7) | Mar 10, 2023 |
| Lenovo        | ThinkPad Z61m 9450HAG       | [5aa66edd35](https://linux-hardware.org/?probe=5aa66edd35) | Mar 04, 2023 |
| Acer          | Aspire 5732Z                | [bff68efdba](https://linux-hardware.org/?probe=bff68efdba) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | [906cb4b50a](https://linux-hardware.org/?probe=906cb4b50a) | Mar 03, 2023 |
| HP            | Pavilion Notebook           | [2173dea5df](https://linux-hardware.org/?probe=2173dea5df) | Mar 02, 2023 |
| HIPER         | WORKBOOK                    | [85085220c9](https://linux-hardware.org/?probe=85085220c9) | Mar 01, 2023 |
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
| 5.10.0-21-amd64        | 33        | 15.21%  |
| 5.10.0-19-amd64        | 29        | 13.36%  |
| 5.10.0-12-amd64        | 25        | 11.52%  |
| 5.10.0-14-amd64        | 20        | 9.22%   |
| 5.10.0-20-amd64        | 17        | 7.83%   |
| 5.10.0-15-amd64        | 16        | 7.37%   |
| 5.10.0-18-amd64        | 14        | 6.45%   |
| 5.10.0-13-amd64        | 14        | 6.45%   |
| 5.10.0-16-amd64        | 11        | 5.07%   |
| 5.10.0-17-amd64        | 9         | 4.15%   |
| 5.10.0-13-686          | 5         | 2.3%    |
| 5.18.0-0.bpo.1-amd64   | 4         | 1.84%   |
| 5.16.0-0.bpo.4-amd64   | 3         | 1.38%   |
| 5.19.0-0.deb11.2-amd64 | 2         | 0.92%   |
| 5.10.0-12-686          | 2         | 0.92%   |
| 6.1.11-x64v1-xanmod1   | 1         | 0.46%   |
| 5.19.10-xanmod1        | 1         | 0.46%   |
| 5.18.0-4-amd64         | 1         | 0.46%   |
| 5.18.0-3-amd64         | 1         | 0.46%   |
| 5.16.0-0.bpo.3-amd64   | 1         | 0.46%   |
| 5.15.78-xanmod1        | 1         | 0.46%   |
| 5.15.70-xanmod1        | 1         | 0.46%   |
| 5.15.0-0.bpo.3-amd64   | 1         | 0.46%   |
| 5.10.0-20-686          | 1         | 0.46%   |
| 5.10.0-19-686          | 1         | 0.46%   |
| 5.10.0-17-686          | 1         | 0.46%   |
| 5.10.0-14-686          | 1         | 0.46%   |
| 4.19.0-23-amd64        | 1         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 188       | 91.71%  |
| 5.18.0  | 6         | 2.93%   |
| 5.16.0  | 3         | 1.46%   |
| 5.19.0  | 2         | 0.98%   |
| 6.1.11  | 1         | 0.49%   |
| 5.19.10 | 1         | 0.49%   |
| 5.15.78 | 1         | 0.49%   |
| 5.15.70 | 1         | 0.49%   |
| 5.15.0  | 1         | 0.49%   |
| 4.19.0  | 1         | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 188       | 92.16%  |
| 5.18    | 6         | 2.94%   |
| 5.19    | 3         | 1.47%   |
| 5.16    | 3         | 1.47%   |
| 5.15    | 2         | 0.98%   |
| 6.1     | 1         | 0.49%   |
| 4.19    | 1         | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 190       | 94.53%  |
| i686   | 11        | 5.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 176       | 86.7%   |
| Cinnamon   | 21        | 10.34%  |
| MATE       | 3         | 1.48%   |
| XFCE       | 1         | 0.49%   |
| awesome    | 1         | 0.49%   |
| Unknown    | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 201       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 116       | 57.14%  |
| LightDM | 87        | 42.86%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 66        | 32.67%  |
| de_DE | 32        | 15.84%  |
| ru_RU | 21        | 10.4%   |
| pt_BR | 12        | 5.94%   |
| en_GB | 12        | 5.94%   |
| fr_FR | 8         | 3.96%   |
| pl_PL | 7         | 3.47%   |
| it_IT | 7         | 3.47%   |
| es_ES | 5         | 2.48%   |
| es_MX | 3         | 1.49%   |
| tr_TR | 2         | 0.99%   |
| pt_PT | 2         | 0.99%   |
| ko_KR | 2         | 0.99%   |
| es_BO | 2         | 0.99%   |
| en_NZ | 2         | 0.99%   |
| en_IE | 2         | 0.99%   |
| da_DK | 2         | 0.99%   |
| nn_NO | 1         | 0.5%    |
| nl_AW | 1         | 0.5%    |
| hu_HU | 1         | 0.5%    |
| fr_BE | 1         | 0.5%    |
| es_VE | 1         | 0.5%    |
| es_PE | 1         | 0.5%    |
| es_EC | 1         | 0.5%    |
| es_CR | 1         | 0.5%    |
| en_SG | 1         | 0.5%    |
| en_IN | 1         | 0.5%    |
| en_CA | 1         | 0.5%    |
| el_GR | 1         | 0.5%    |
| de_CH | 1         | 0.5%    |
| de_AT | 1         | 0.5%    |
| cs_CZ | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 132       | 65.35%  |
| BIOS | 70        | 34.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 186       | 92.54%  |
| Overlay | 6         | 2.99%   |
| Btrfs   | 5         | 2.49%   |
| Xfs     | 2         | 1%      |
| Tmpfs   | 2         | 1%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 115       | 56.65%  |
| GPT     | 63        | 31.03%  |
| MBR     | 25        | 12.32%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 187       | 92.57%  |
| Yes       | 15        | 7.43%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 179       | 88.61%  |
| Yes       | 23        | 11.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 48        | 23.88%  |
| Lenovo              | 40        | 19.9%   |
| Dell                | 27        | 13.43%  |
| Acer                | 19        | 9.45%   |
| ASUSTek Computer    | 14        | 6.97%   |
| Toshiba             | 8         | 3.98%   |
| Apple               | 7         | 3.48%   |
| Sony                | 3         | 1.49%   |
| Medion              | 3         | 1.49%   |
| Google              | 3         | 1.49%   |
| Fujitsu             | 3         | 1.49%   |
| Star Labs           | 2         | 1%      |
| Samsung Electronics | 2         | 1%      |
| MSI                 | 2         | 1%      |
| Compaq              | 2         | 1%      |
| Unknown             | 2         | 1%      |
| Wortmann AG         | 1         | 0.5%    |
| TUXEDO              | 1         | 0.5%    |
| Philco              | 1         | 0.5%    |
| Packard Bell        | 1         | 0.5%    |
| Multilaser          | 1         | 0.5%    |
| Microtech           | 1         | 0.5%    |
| LincPlus            | 1         | 0.5%    |
| Kruger&Matz         | 1         | 0.5%    |
| itel Mobile Limited | 1         | 0.5%    |
| Howard Computers    | 1         | 0.5%    |
| HIPER               | 1         | 0.5%    |
| Framework           | 1         | 0.5%    |
| Dynabook            | 1         | 0.5%    |
| Dixonsxp            | 1         | 0.5%    |
| AMI                 | 1         | 0.5%    |
| Alienware           | 1         | 0.5%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 4         | 1.99%   |
| Star Labs StarBook                  | 2         | 1%      |
| Lenovo IdeaPad 3 15ITL6 82H8        | 2         | 1%      |
| Lenovo IdeaPad 3 15ADA05 81W1       | 2         | 1%      |
| Lenovo G500 20236                   | 2         | 1%      |
| HP Pavilion Notebook                | 2         | 1%      |
| HP Pavilion dv6                     | 2         | 1%      |
| HP Notebook                         | 2         | 1%      |
| HP Laptop 15z-ef2xxx                | 2         | 1%      |
| HP Laptop 15-dw3xxx                 | 2         | 1%      |
| HP 250 G8 Notebook PC               | 2         | 1%      |
| Dell Latitude E6400                 | 2         | 1%      |
| Dell Latitude E5540                 | 2         | 1%      |
| Compaq 420                          | 2         | 1%      |
| Acer Aspire E1-570G                 | 2         | 1%      |
| Acer Aspire 5930                    | 2         | 1%      |
| Wortmann AG TERRA_MOBILE_1713A      | 1         | 0.5%    |
| TUXEDO N8xxEZ                       | 1         | 0.5%    |
| Toshiba Satellite Pro A50-C         | 1         | 0.5%    |
| Toshiba Satellite M55               | 1         | 0.5%    |
| Toshiba Satellite L855D             | 1         | 0.5%    |
| Toshiba Satellite L455              | 1         | 0.5%    |
| Toshiba Satellite L305              | 1         | 0.5%    |
| Toshiba Satellite L300              | 1         | 0.5%    |
| Toshiba PORTEGE Z30-B               | 1         | 0.5%    |
| Toshiba PORTEGE M780                | 1         | 0.5%    |
| Sony SVF1532W4E                     | 1         | 0.5%    |
| Sony SVE1713Y1RB                    | 1         | 0.5%    |
| Sony SVE1512G1RW                    | 1         | 0.5%    |
| Samsung RV415/RV515                 | 1         | 0.5%    |
| Samsung 355V4C/356V4C/3445VC/3545VC | 1         | 0.5%    |
| Philco 10D                          | 1         | 0.5%    |
| Packard Bell DOT S                  | 1         | 0.5%    |
| Multilaser PC150                    | 1         | 0.5%    |
| MSI U180                            | 1         | 0.5%    |
| MSI GL73 8SE                        | 1         | 0.5%    |
| Microtech ebookPro                  | 1         | 0.5%    |
| Medion P15648                       | 1         | 0.5%    |
| Medion E6220                        | 1         | 0.5%    |
| Medion E6214                        | 1         | 0.5%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 17        | 8.46%   |
| Acer Aspire        | 16        | 7.96%   |
| Lenovo IdeaPad     | 11        | 5.47%   |
| HP Laptop          | 11        | 5.47%   |
| Dell Latitude      | 9         | 4.48%   |
| HP Pavilion        | 7         | 3.48%   |
| Dell Inspiron      | 7         | 3.48%   |
| Toshiba Satellite  | 6         | 2.99%   |
| HP EliteBook       | 6         | 2.99%   |
| ASUS VivoBook      | 5         | 2.49%   |
| HP ProBook         | 4         | 1.99%   |
| Dell Precision     | 4         | 1.99%   |
| Unknown            | 4         | 1.99%   |
| Dell Vostro        | 3         | 1.49%   |
| Toshiba PORTEGE    | 2         | 1%      |
| Star Labs StarBook | 2         | 1%      |
| Lenovo ThinkBook   | 2         | 1%      |
| Lenovo Legion      | 2         | 1%      |
| Lenovo G500        | 2         | 1%      |
| HP ZBook           | 2         | 1%      |
| HP Notebook        | 2         | 1%      |
| HP Compaq          | 2         | 1%      |
| HP 255             | 2         | 1%      |
| HP 250             | 2         | 1%      |
| Fujitsu LIFEBOOK   | 2         | 1%      |
| Dell XPS           | 2         | 1%      |
| Compaq 420         | 2         | 1%      |
| ASUS ROG           | 2         | 1%      |
| Wortmann AG TERRA  | 1         | 0.5%    |
| TUXEDO N8xxEZ      | 1         | 0.5%    |
| Sony SVF1532W4E    | 1         | 0.5%    |
| Sony SVE1713Y1RB   | 1         | 0.5%    |
| Sony SVE1512G1RW   | 1         | 0.5%    |
| Samsung RV415      | 1         | 0.5%    |
| Samsung 355V4C     | 1         | 0.5%    |
| Philco 10D         | 1         | 0.5%    |
| Packard Bell DOT   | 1         | 0.5%    |
| Multilaser PC150   | 1         | 0.5%    |
| MSI U180           | 1         | 0.5%    |
| MSI GL73           | 1         | 0.5%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 28        | 13.93%  |
| 2020 | 19        | 9.45%   |
| 2013 | 17        | 8.46%   |
| 2012 | 14        | 6.97%   |
| 2010 | 14        | 6.97%   |
| 2016 | 13        | 6.47%   |
| 2019 | 12        | 5.97%   |
| 2017 | 11        | 5.47%   |
| 2015 | 11        | 5.47%   |
| 2022 | 10        | 4.98%   |
| 2018 | 10        | 4.98%   |
| 2009 | 9         | 4.48%   |
| 2008 | 9         | 4.48%   |
| 2014 | 7         | 3.48%   |
| 2011 | 7         | 3.48%   |
| 2007 | 5         | 2.49%   |
| 2006 | 3         | 1.49%   |
| 2023 | 2         | 1%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 201       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 178       | 88.12%  |
| Enabled  | 24        | 11.88%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 195       | 97.01%  |
| Yes  | 6         | 2.99%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 59        | 29.35%  |
| 3.01-4.0    | 48        | 23.88%  |
| 8.01-16.0   | 32        | 15.92%  |
| 16.01-24.0  | 31        | 15.42%  |
| 1.01-2.0    | 12        | 5.97%   |
| 32.01-64.0  | 9         | 4.48%   |
| 2.01-3.0    | 7         | 3.48%   |
| 64.01-256.0 | 3         | 1.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 97        | 45.54%  |
| 2.01-3.0   | 67        | 31.46%  |
| 3.01-4.0   | 20        | 9.39%   |
| 4.01-8.0   | 16        | 7.51%   |
| 0.51-1.0   | 11        | 5.16%   |
| 32.01-64.0 | 1         | 0.47%   |
| 8.01-16.0  | 1         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 156       | 76.47%  |
| 2      | 39        | 19.12%  |
| 3      | 8         | 3.92%   |
| 4      | 1         | 0.49%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 135       | 66.83%  |
| Yes       | 67        | 33.17%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 156       | 77.61%  |
| No        | 45        | 22.39%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 199       | 99%     |
| No        | 2         | 1%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 69.8%   |
| No        | 61        | 30.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Germany     | 36        | 17.73%  |
| USA         | 32        | 15.76%  |
| Russia      | 22        | 10.84%  |
| Italy       | 12        | 5.91%   |
| Brazil      | 12        | 5.91%   |
| Poland      | 9         | 4.43%   |
| UK          | 8         | 3.94%   |
| France      | 8         | 3.94%   |
| Spain       | 6         | 2.96%   |
| Belarus     | 4         | 1.97%   |
| Portugal    | 3         | 1.48%   |
| Mexico      | 3         | 1.48%   |
| Canada      | 3         | 1.48%   |
| Belgium     | 3         | 1.48%   |
| Turkey      | 2         | 0.99%   |
| South Korea | 2         | 0.99%   |
| Romania     | 2         | 0.99%   |
| New Zealand | 2         | 0.99%   |
| Indonesia   | 2         | 0.99%   |
| Hungary     | 2         | 0.99%   |
| Greece      | 2         | 0.99%   |
| Denmark     | 2         | 0.99%   |
| Chile       | 2         | 0.99%   |
| Bolivia     | 2         | 0.99%   |
| Austria     | 2         | 0.99%   |
| Vietnam     | 1         | 0.49%   |
| Venezuela   | 1         | 0.49%   |
| Sweden      | 1         | 0.49%   |
| Slovenia    | 1         | 0.49%   |
| Serbia      | 1         | 0.49%   |
| Peru        | 1         | 0.49%   |
| Paraguay    | 1         | 0.49%   |
| Norway      | 1         | 0.49%   |
| Malaysia    | 1         | 0.49%   |
| Lithuania   | 1         | 0.49%   |
| Kenya       | 1         | 0.49%   |
| Kazakhstan  | 1         | 0.49%   |
| Japan       | 1         | 0.49%   |
| Ireland     | 1         | 0.49%   |
| India       | 1         | 0.49%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Moscow               | 7         | 3.38%   |
| St Petersburg        | 4         | 1.93%   |
| Berlin               | 4         | 1.93%   |
| San Jose             | 2         | 0.97%   |
| Rome                 | 2         | 0.97%   |
| Oruro                | 2         | 0.97%   |
| Nuremberg            | 2         | 0.97%   |
| Neasden              | 2         | 0.97%   |
| Munich               | 2         | 0.97%   |
| Miami                | 2         | 0.97%   |
| Madrid               | 2         | 0.97%   |
| Lisbon               | 2         | 0.97%   |
| Krakow               | 2         | 0.97%   |
| Hrodna               | 2         | 0.97%   |
| Freiburg im Breisgau | 2         | 0.97%   |
| Bergamo              | 2         | 0.97%   |
| Auckland             | 2         | 0.97%   |
| Zaragoza             | 1         | 0.48%   |
| Yekaterinburg        | 1         | 0.48%   |
| Wroclaw              | 1         | 0.48%   |
| West Hartford        | 1         | 0.48%   |
| Weimar               | 1         | 0.48%   |
| Warsaw               | 1         | 0.48%   |
| Voronezh             | 1         | 0.48%   |
| Volos                | 1         | 0.48%   |
| Vilshofen            | 1         | 0.48%   |
| Vilnius              | 1         | 0.48%   |
| Viggianello          | 1         | 0.48%   |
| Viet Tri             | 1         | 0.48%   |
| Vienna               | 1         | 0.48%   |
| Veurne               | 1         | 0.48%   |
| Vaslui               | 1         | 0.48%   |
| Vancouver            | 1         | 0.48%   |
| Valsoyfjord          | 1         | 0.48%   |
| Uiwang               | 1         | 0.48%   |
| Turku                | 1         | 0.48%   |
| Tula                 | 1         | 0.48%   |
| Troisdorf            | 1         | 0.48%   |
| Toyota               | 1         | 0.48%   |
| Toulouse             | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 31        | 34     | 12.4%   |
| WDC                            | 27        | 30     | 10.8%   |
| Seagate                        | 26        | 31     | 10.4%   |
| Unknown                        | 18        | 26     | 7.2%    |
| SanDisk                        | 17        | 21     | 6.8%    |
| Kingston                       | 12        | 13     | 4.8%    |
| Toshiba                        | 11        | 12     | 4.4%    |
| SK hynix                       | 9         | 9      | 3.6%    |
| Intel                          | 8         | 9      | 3.2%    |
| Hitachi                        | 8         | 8      | 3.2%    |
| Crucial                        | 6         | 7      | 2.4%    |
| A-DATA Technology              | 6         | 7      | 2.4%    |
| Micron Technology              | 5         | 5      | 2%      |
| China                          | 5         | 6      | 2%      |
| Apple                          | 5         | 10     | 2%      |
| PNY                            | 4         | 5      | 1.6%    |
| HGST                           | 4         | 5      | 1.6%    |
| Patriot                        | 3         | 3      | 1.2%    |
| Transcend                      | 2         | 2      | 0.8%    |
| Team                           | 2         | 2      | 0.8%    |
| Star Drive                     | 2         | 2      | 0.8%    |
| Phison                         | 2         | 2      | 0.8%    |
| KIOXIA                         | 2         | 5      | 0.8%    |
| KingSpec                       | 2         | 2      | 0.8%    |
| GOODRAM                        | 2         | 2      | 0.8%    |
| Fujitsu                        | 2         | 2      | 0.8%    |
| Unknown                        | 2         | 2      | 0.8%    |
| WINTEC                         | 1         | 1      | 0.4%    |
| Union Memory                   | 1         | 1      | 0.4%    |
| UMIS                           | 1         | 1      | 0.4%    |
| SSD PHIS                       | 1         | 1      | 0.4%    |
| Solid State Storage Technology | 1         | 1      | 0.4%    |
| ShiJi                          | 1         | 1      | 0.4%    |
| SABRENT                        | 1         | 1      | 0.4%    |
| Oyen                           | 1         | 1      | 0.4%    |
| ORICO                          | 1         | 1      | 0.4%    |
| Microtech                      | 1         | 2      | 0.4%    |
| Micron/Crucial Technology      | 1         | 2      | 0.4%    |
| MAXSUN                         | 1         | 1      | 0.4%    |
| LITEON                         | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 8         | 3.1%    |
| Unknown SD/MMC/MS PRO 64GB           | 3         | 1.16%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 1.16%   |
| SanDisk NVMe SSD Drive 256GB         | 3         | 1.16%   |
| Kingston SA400S37480G 480GB SSD      | 3         | 1.16%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 1.16%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 0.78%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 2         | 0.78%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB | 2         | 0.78%   |
| Unknown SC128  128GB                 | 2         | 0.78%   |
| Unknown MMC Card  64GB               | 2         | 0.78%   |
| Unknown MMC Card  32GB               | 2         | 0.78%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.78%   |
| Star Drive PCIe SSD 480GB            | 2         | 0.78%   |
| Seagate ST9250315AS 250GB            | 2         | 0.78%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 2         | 0.78%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB | 2         | 0.78%   |
| Samsung SSD 980 1TB                  | 2         | 0.78%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.78%   |
| Samsung SSD 840 EVO 250GB            | 2         | 0.78%   |
| Samsung PM991a NVMe 512GB            | 2         | 0.78%   |
| Patriot Burst 240GB SSD              | 2         | 0.78%   |
| Micron NVMe SSD Drive 512GB          | 2         | 0.78%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.78%   |
| Crucial CT1000BX500SSD1 1TB          | 2         | 0.78%   |
| Apple SSD SD0128F 121GB              | 2         | 0.78%   |
| A-DATA SU650 240GB SSD               | 2         | 0.78%   |
| A-DATA ED600 1TB SSD                 | 2         | 0.78%   |
| Unknown                              | 2         | 0.78%   |
| WINTEC 240GB SATA3 SF2281 SSD        | 1         | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.39%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD     | 1         | 0.39%   |
| WDC WDS100T3X0C-00SJG0 1TB           | 1         | 0.39%   |
| WDC WDBNCE5000PNC 500GB SSD          | 1         | 0.39%   |
| WDC WD7500BPVT-22HXZT3 752GB         | 1         | 0.39%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.39%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.39%   |
| WDC WD5000BPVX-00JC3T0 500GB         | 1         | 0.39%   |
| WDC WD5000BEVT-22A0RT0 500GB         | 1         | 0.39%   |
| WDC WD3200BEVT-60ZCT0 320GB          | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 31     | 36.62%  |
| WDC                 | 16        | 18     | 22.54%  |
| Toshiba             | 8         | 9      | 11.27%  |
| Hitachi             | 8         | 8      | 11.27%  |
| HGST                | 4         | 5      | 5.63%   |
| Unknown             | 3         | 3      | 4.23%   |
| Fujitsu             | 2         | 2      | 2.82%   |
| Samsung Electronics | 1         | 1      | 1.41%   |
| SABRENT             | 1         | 1      | 1.41%   |
| Intenso             | 1         | 1      | 1.41%   |
| ASMT                | 1         | 1      | 1.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 16     | 15.05%  |
| Kingston            | 11        | 12     | 11.83%  |
| SanDisk             | 7         | 8      | 7.53%   |
| Crucial             | 6         | 7      | 6.45%   |
| A-DATA Technology   | 6         | 7      | 6.45%   |
| PNY                 | 4         | 5      | 4.3%    |
| Intel               | 4         | 4      | 4.3%    |
| China               | 4         | 5      | 4.3%    |
| Apple               | 4         | 4      | 4.3%    |
| WDC                 | 3         | 3      | 3.23%   |
| Patriot             | 3         | 3      | 3.23%   |
| Transcend           | 2         | 2      | 2.15%   |
| Toshiba             | 2         | 2      | 2.15%   |
| Team                | 2         | 2      | 2.15%   |
| KingSpec            | 2         | 2      | 2.15%   |
| GOODRAM             | 2         | 2      | 2.15%   |
| Unknown             | 2         | 2      | 2.15%   |
| WINTEC              | 1         | 1      | 1.08%   |
| SSD PHIS            | 1         | 1      | 1.08%   |
| ORICO               | 1         | 1      | 1.08%   |
| Microtech           | 1         | 2      | 1.08%   |
| Micron Technology   | 1         | 1      | 1.08%   |
| LITEON              | 1         | 1      | 1.08%   |
| Lexar               | 1         | 1      | 1.08%   |
| Initio              | 1         | 1      | 1.08%   |
| HXY                 | 1         | 1      | 1.08%   |
| Gigabyte Technology | 1         | 2      | 1.08%   |
| FORESEE             | 1         | 3      | 1.08%   |
| Emtec               | 1         | 1      | 1.08%   |
| Corsair             | 1         | 1      | 1.08%   |
| BHT                 | 1         | 2      | 1.08%   |
| Acer                | 1         | 1      | 1.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 85        | 106    | 36.17%  |
| HDD     | 68        | 80     | 28.94%  |
| NVMe    | 59        | 78     | 25.11%  |
| MMC     | 15        | 22     | 6.38%   |
| Unknown | 8         | 9      | 3.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 139       | 180    | 62.33%  |
| NVMe | 59        | 78     | 26.46%  |
| MMC  | 15        | 22     | 6.73%   |
| SAS  | 10        | 15     | 4.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 107       | 131    | 72.3%   |
| 0.51-1.0   | 35        | 48     | 23.65%  |
| 1.01-2.0   | 3         | 4      | 2.03%   |
| 2.01-3.0   | 2         | 2      | 1.35%   |
| 4.01-10.0  | 1         | 1      | 0.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 74        | 36.27%  |
| 251-500        | 55        | 26.96%  |
| 501-1000       | 26        | 12.75%  |
| 1001-2000      | 13        | 6.37%   |
| 51-100         | 12        | 5.88%   |
| 21-50          | 10        | 4.9%    |
| 1-20           | 7         | 3.43%   |
| 2001-3000      | 5         | 2.45%   |
| More than 3000 | 2         | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 99        | 46.48%  |
| 21-50     | 46        | 21.6%   |
| 101-250   | 24        | 11.27%  |
| 51-100    | 23        | 10.8%   |
| 501-1000  | 11        | 5.16%   |
| 251-500   | 9         | 4.23%   |
| 2001-3000 | 1         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WINTEC 240GB SATA3 SF2281 SSD         | 1         | 1      | 5.88%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 5.88%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 5.88%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 5.88%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 5.88%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 5.88%   |
| Seagate ST500LT032-1E9142 500GB       | 1         | 1      | 5.88%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 2      | 5.88%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 5.88%   |
| Samsung Electronics SSD 850 EVO 500GB | 1         | 1      | 5.88%   |
| Samsung Electronics HM160HC 160GB     | 1         | 1      | 5.88%   |
| Phison ES 512GB                       | 1         | 1      | 5.88%   |
| Intel SSDSCKKF256G8 SATA 256GB        | 1         | 1      | 5.88%   |
| Intel SSDSC2CT240A3 240GB             | 1         | 1      | 5.88%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 5.88%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 5.88%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 5      | 25%     |
| Seagate             | 2         | 2      | 12.5%   |
| Intel               | 2         | 2      | 12.5%   |
| Hitachi             | 2         | 2      | 12.5%   |
| WINTEC              | 1         | 1      | 6.25%   |
| WDC                 | 1         | 2      | 6.25%   |
| Toshiba             | 1         | 1      | 6.25%   |
| SK hynix            | 1         | 1      | 6.25%   |
| Phison              | 1         | 1      | 6.25%   |
| HGST                | 1         | 1      | 6.25%   |

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
| HDD  | 7         | 8      | 43.75%  |
| SSD  | 6         | 6      | 37.5%   |
| NVMe | 3         | 4      | 18.75%  |

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
| Detected | 129       | 182    | 58.37%  |
| Works    | 76        | 95     | 34.39%  |
| Malfunc  | 16        | 18     | 7.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 140       | 60.34%  |
| AMD                            | 29        | 12.5%   |
| Samsung Electronics            | 17        | 7.33%   |
| SanDisk                        | 15        | 6.47%   |
| SK hynix                       | 9         | 3.88%   |
| Phison Electronics             | 4         | 1.72%   |
| Micron Technology              | 4         | 1.72%   |
| KIOXIA                         | 3         | 1.29%   |
| Union Memory (Shenzhen)        | 2         | 0.86%   |
| Marvell Technology Group       | 2         | 0.86%   |
| Toshiba America Info Systems   | 1         | 0.43%   |
| Solid State Storage Technology | 1         | 0.43%   |
| Nvidia                         | 1         | 0.43%   |
| Micron/Crucial Technology      | 1         | 0.43%   |
| Kingston Technology Company    | 1         | 0.43%   |
| Apple                          | 1         | 0.43%   |
| ADATA Technology               | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 25        | 9.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 6.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 14        | 5.51%   |
| Intel Volume Management Device NVMe RAID Controller                              | 13        | 5.12%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 13        | 5.12%   |
| Intel Tiger Lake-LP SATA Controller                                              | 10        | 3.94%   |
| Samsung NVMe SSD Controller 980                                                  | 9         | 3.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 3.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 3.15%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 2.76%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 6         | 2.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 2.36%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 5         | 1.97%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 5         | 1.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 1.57%   |
| Micron NVMe Storage Controller                                                   | 4         | 1.57%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 1.57%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 1.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.57%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 1.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.57%   |
| SanDisk NVMe Controller                                                          | 3         | 1.18%   |
| SanDisk Non-Volatile memory controller                                           | 3         | 1.18%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 3         | 1.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.18%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 3         | 1.18%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 3         | 1.18%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.79%   |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.79%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.79%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 2         | 0.79%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 0.79%   |
| Intel SSD 660P Series                                                            | 2         | 0.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.79%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.79%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 0.79%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 144       | 58.3%   |
| NVMe | 60        | 24.29%  |
| RAID | 27        | 10.93%  |
| IDE  | 16        | 6.48%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 161       | 80.1%   |
| AMD    | 40        | 19.9%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 8         | 3.98%   |
| Intel Core i5-3230M CPU @ 2.60GHz            | 6         | 2.99%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 5         | 2.49%   |
| AMD Ryzen 5 5500U with Radeon Graphics       | 5         | 2.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 4         | 1.99%   |
| Intel Atom CPU N2600 @ 1.60GHz               | 4         | 1.99%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz      | 4         | 1.99%   |
| Intel Core i5-3320M CPU @ 2.60GHz            | 3         | 1.49%   |
| Intel Core i3-2310M CPU @ 2.10GHz            | 3         | 1.49%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz           | 3         | 1.49%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz      | 3         | 1.49%   |
| AMD Ryzen 7 5700U with Radeon Graphics       | 3         | 1.49%   |
| Intel Pentium M processor 1.73GHz            | 2         | 1%      |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz  | 2         | 1%      |
| Intel Pentium CPU P6000 @ 1.87GHz            | 2         | 1%      |
| Intel Pentium CPU N3700 @ 1.60GHz            | 2         | 1%      |
| Intel Core i7-8750H CPU @ 2.20GHz            | 2         | 1%      |
| Intel Core i7-7500U CPU @ 2.70GHz            | 2         | 1%      |
| Intel Core i7-4810MQ CPU @ 2.80GHz           | 2         | 1%      |
| Intel Core i7-3612QM CPU @ 2.10GHz           | 2         | 1%      |
| Intel Core i7 CPU Q 720 @ 1.60GHz            | 2         | 1%      |
| Intel Core i5-8265U CPU @ 1.60GHz            | 2         | 1%      |
| Intel Core i3-4010U CPU @ 1.70GHz            | 2         | 1%      |
| Intel Core i3 CPU M 330 @ 2.13GHz            | 2         | 1%      |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz         | 2         | 1%      |
| Intel Celeron N4000 CPU @ 1.10GHz            | 2         | 1%      |
| Intel Celeron CPU N3060 @ 1.60GHz            | 2         | 1%      |
| Intel Atom CPU N270 @ 1.60GHz                | 2         | 1%      |
| Intel 12th Gen Core i7-1260P                 | 2         | 1%      |
| AMD Ryzen 5 5600H with Radeon Graphics       | 2         | 1%      |
| AMD Ryzen 3 3250U with Radeon Graphics       | 2         | 1%      |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G | 2         | 1%      |
| Intel Pentium Silver N6000 @ 1.10GHz         | 1         | 0.5%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz     | 1         | 0.5%    |
| Intel Pentium Gold 7505 @ 2.00GHz            | 1         | 0.5%    |
| Intel Pentium Dual CPU T3400 @ 2.16GHz       | 1         | 0.5%    |
| Intel Pentium CPU P6100 @ 2.00GHz            | 1         | 0.5%    |
| Intel Pentium CPU N3710 @ 1.60GHz            | 1         | 0.5%    |
| Intel Pentium CPU N3540 @ 2.16GHz            | 1         | 0.5%    |
| Intel Pentium CPU B980 @ 2.40GHz             | 1         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 42        | 20.9%   |
| Intel Core i7           | 24        | 11.94%  |
| Other                   | 22        | 10.95%  |
| Intel Core i3           | 22        | 10.95%  |
| Intel Celeron           | 11        | 5.47%   |
| AMD Ryzen 5             | 11        | 5.47%   |
| Intel Core 2 Duo        | 10        | 4.98%   |
| Intel Atom              | 9         | 4.48%   |
| Intel Pentium           | 8         | 3.98%   |
| AMD Ryzen 7             | 8         | 3.98%   |
| AMD Ryzen 3             | 3         | 1.49%   |
| AMD A10                 | 3         | 1.49%   |
| Intel Pentium Silver    | 2         | 1%      |
| Intel Pentium M         | 2         | 1%      |
| Intel Pentium Dual-Core | 2         | 1%      |
| Intel Core 2            | 2         | 1%      |
| Intel Celeron M         | 2         | 1%      |
| AMD E2                  | 2         | 1%      |
| AMD E1                  | 2         | 1%      |
| AMD A4                  | 2         | 1%      |
| Intel Pentium Gold      | 1         | 0.5%    |
| Intel Pentium Dual      | 1         | 0.5%    |
| Intel Genuine           | 1         | 0.5%    |
| Intel Core i9           | 1         | 0.5%    |
| Intel Core 2 Extreme    | 1         | 0.5%    |
| AMD Ryzen 9             | 1         | 0.5%    |
| AMD E                   | 1         | 0.5%    |
| AMD C-50                | 1         | 0.5%    |
| AMD Athlon II           | 1         | 0.5%    |
| AMD Athlon              | 1         | 0.5%    |
| AMD A8                  | 1         | 0.5%    |
| AMD A6                  | 1         | 0.5%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 117       | 58.21%  |
| 4      | 50        | 24.88%  |
| 6      | 13        | 6.47%   |
| 8      | 10        | 4.98%   |
| 1      | 8         | 3.98%   |
| 12     | 2         | 1%      |
| 10     | 1         | 0.5%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 201       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 142       | 70.65%  |
| 1      | 59        | 29.35%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 194       | 96.52%  |
| 32-bit         | 7         | 3.48%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 16        | 7.8%    |
| 0x306a9    | 16        | 7.8%    |
| 0x40651    | 11        | 5.37%   |
| 0x406e3    | 10        | 4.88%   |
| Unknown    | 9         | 4.39%   |
| 0x206a7    | 8         | 3.9%    |
| 0x08608103 | 8         | 3.9%    |
| 0x806ec    | 7         | 3.41%   |
| 0x806e9    | 6         | 2.93%   |
| 0x6fd      | 6         | 2.93%   |
| 0x1067a    | 6         | 2.93%   |
| 0x08108109 | 6         | 2.93%   |
| 0x406c4    | 5         | 2.44%   |
| 0x306c3    | 5         | 2.44%   |
| 0x30661    | 4         | 1.95%   |
| 0x20652    | 4         | 1.95%   |
| 0x06006705 | 4         | 1.95%   |
| 0x906ea    | 3         | 1.46%   |
| 0x806ea    | 3         | 1.46%   |
| 0x706e5    | 3         | 1.46%   |
| 0x706a1    | 3         | 1.46%   |
| 0x6f6      | 3         | 1.46%   |
| 0x30678    | 3         | 1.46%   |
| 0x20655    | 3         | 1.46%   |
| 0x106e5    | 3         | 1.46%   |
| 0x106c2    | 3         | 1.46%   |
| 0x10676    | 3         | 1.46%   |
| 0x0a50000c | 3         | 1.46%   |
| 0xa0652    | 2         | 0.98%   |
| 0x806eb    | 2         | 0.98%   |
| 0x6d8      | 2         | 0.98%   |
| 0x506e3    | 2         | 0.98%   |
| 0x406c3    | 2         | 0.98%   |
| 0x306d4    | 2         | 0.98%   |
| 0x0a50000d | 2         | 0.98%   |
| 0x06001119 | 2         | 0.98%   |
| 0x906ed    | 1         | 0.49%   |
| 0x906e9    | 1         | 0.49%   |
| 0x906c0    | 1         | 0.49%   |
| 0x906a4    | 1         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 23        | 11.39%  |
| TigerLake        | 17        | 8.42%   |
| IvyBridge        | 16        | 7.92%   |
| Haswell          | 16        | 7.92%   |
| Skylake          | 12        | 5.94%   |
| Unknown          | 12        | 5.94%   |
| Silvermont       | 11        | 5.45%   |
| Penryn           | 9         | 4.46%   |
| Core             | 9         | 4.46%   |
| Westmere         | 8         | 3.96%   |
| SandyBridge      | 8         | 3.96%   |
| Bonnell          | 8         | 3.96%   |
| Zen+             | 7         | 3.47%   |
| Excavator        | 7         | 3.47%   |
| Zen 3            | 6         | 2.97%   |
| Icelake          | 4         | 1.98%   |
| Goldmont plus    | 4         | 1.98%   |
| P6               | 3         | 1.49%   |
| Nehalem          | 3         | 1.49%   |
| Broadwell        | 3         | 1.49%   |
| Zen 2            | 2         | 0.99%   |
| Puma             | 2         | 0.99%   |
| Piledriver       | 2         | 0.99%   |
| Jaguar           | 2         | 0.99%   |
| CometLake        | 2         | 0.99%   |
| Bobcat           | 2         | 0.99%   |
| Tremont          | 1         | 0.5%    |
| K10              | 1         | 0.5%    |
| Goldmont         | 1         | 0.5%    |
| Alderlake Hybrid | 1         | 0.5%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 143       | 60.08%  |
| AMD    | 50        | 21.01%  |
| Nvidia | 45        | 18.91%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 15        | 6%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 4.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 4%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 4%      |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 3.2%    |
| AMD Lucienne                                                                             | 8         | 3.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 2.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 2.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.4%    |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 5         | 2%      |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 2%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 2%      |
| Intel HD Graphics 620                                                                    | 5         | 2%      |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 2%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.6%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 1.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.6%    |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 1.2%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.2%    |
| Intel UHD Graphics 620                                                                   | 3         | 1.2%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 1.2%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.2%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.2%    |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 3         | 1.2%    |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.8%    |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 2         | 0.8%    |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.8%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.8%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.8%    |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 0.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.8%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.8%    |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 0.8%    |
| Intel HD Graphics 5500                                                                   | 2         | 0.8%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 109       | 54.23%  |
| 1 x AMD        | 37        | 18.41%  |
| Intel + Nvidia | 29        | 14.43%  |
| 1 x Nvidia     | 13        | 6.47%   |
| 2 x AMD        | 5         | 2.49%   |
| Intel + AMD    | 5         | 2.49%   |
| AMD + Nvidia   | 3         | 1.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 182       | 89.66%  |
| Proprietary | 13        | 6.4%    |
| Unknown     | 8         | 3.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 126       | 61.76%  |
| 0.01-0.5   | 35        | 17.16%  |
| 1.01-2.0   | 23        | 11.27%  |
| 0.51-1.0   | 10        | 4.9%    |
| 3.01-4.0   | 7         | 3.43%   |
| 5.01-6.0   | 2         | 0.98%   |
| 2.01-3.0   | 1         | 0.49%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 43        | 20.67%  |
| LG Display              | 34        | 16.35%  |
| Chimei Innolux          | 31        | 14.9%   |
| BOE                     | 25        | 12.02%  |
| Samsung Electronics     | 15        | 7.21%   |
| Apple                   | 7         | 3.37%   |
| Chi Mei Optoelectronics | 6         | 2.88%   |
| Sharp                   | 5         | 2.4%    |
| LG Philips              | 5         | 2.4%    |
| InfoVision              | 5         | 2.4%    |
| Goldstar                | 4         | 1.92%   |
| Dell                    | 4         | 1.92%   |
| Lenovo                  | 3         | 1.44%   |
| HannStar                | 3         | 1.44%   |
| SLD                     | 2         | 0.96%   |
| PANDA                   | 2         | 0.96%   |
| Vestel Elektronik       | 1         | 0.48%   |
| TR_                     | 1         | 0.48%   |
| Sceptre Tech            | 1         | 0.48%   |
| Quanta Display          | 1         | 0.48%   |
| Planar                  | 1         | 0.48%   |
| Philips                 | 1         | 0.48%   |
| Panasonic               | 1         | 0.48%   |
| Packard Bell            | 1         | 0.48%   |
| Insignia                | 1         | 0.48%   |
| IBM                     | 1         | 0.48%   |
| HKC                     | 1         | 0.48%   |
| Hewlett-Packard         | 1         | 0.48%   |
| DENON                   | 1         | 0.48%   |
| Acer                    | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 1.44%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 1.44%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 3         | 1.44%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 3         | 1.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 3         | 1.44%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                     | 2         | 0.96%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 2         | 0.96%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch              | 2         | 0.96%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 2         | 0.96%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 0.96%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 344x193mm 15.5-inch             | 2         | 0.96%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 2         | 0.96%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch         | 2         | 0.96%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.96%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 2         | 0.96%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch           | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.96%   |
| AU Optronics LCD Monitor AUO32EC 1366x768 344x193mm 15.5-inch            | 2         | 0.96%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 1         | 0.48%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                     | 1         | 0.48%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 1         | 0.48%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                  | 1         | 0.48%   |
| Sharp LQ133M1JW02 SHP141A 1920x1080 294x165mm 13.3-inch                  | 1         | 0.48%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 294x165mm 13.3-inch                  | 1         | 0.48%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 1         | 0.48%   |
| Sceptre Tech Sceptre B34 SPT0D52 2560x1080 797x334mm 34.0-inch           | 1         | 0.48%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 331x207mm 15.4-inch    | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch    | 1         | 0.48%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch     | 1         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 83        | 41.09%  |
| 1366x768 (WXGA)    | 70        | 34.65%  |
| 1600x900 (HD+)     | 9         | 4.46%   |
| 1920x1200 (WUXGA)  | 7         | 3.47%   |
| 1280x800 (WXGA)    | 7         | 3.47%   |
| 1024x600           | 6         | 2.97%   |
| 3840x2160 (4K)     | 5         | 2.48%   |
| 1440x900 (WXGA+)   | 4         | 1.98%   |
| 2880x1800          | 2         | 0.99%   |
| 1280x1024 (SXGA)   | 2         | 0.99%   |
| 2560x1600          | 1         | 0.5%    |
| 2560x1440 (QHD)    | 1         | 0.5%    |
| 2560x1080          | 1         | 0.5%    |
| 2256x1504          | 1         | 0.5%    |
| 1680x1050 (WSXGA+) | 1         | 0.5%    |
| 1280x768           | 1         | 0.5%    |
| 1280x720 (HD)      | 1         | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 101       | 48.33%  |
| 13      | 31        | 14.83%  |
| 14      | 21        | 10.05%  |
| 17      | 14        | 6.7%    |
| 24      | 8         | 3.83%   |
| 12      | 6         | 2.87%   |
| 10      | 6         | 2.87%   |
| 11      | 4         | 1.91%   |
| 23      | 3         | 1.44%   |
| Unknown | 3         | 1.44%   |
| 27      | 2         | 0.96%   |
| 21      | 2         | 0.96%   |
| 84      | 1         | 0.48%   |
| 72      | 1         | 0.48%   |
| 40      | 1         | 0.48%   |
| 34      | 1         | 0.48%   |
| 31      | 1         | 0.48%   |
| 18      | 1         | 0.48%   |
| 16      | 1         | 0.48%   |
| 8       | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 138       | 66.99%  |
| 201-300     | 30        | 14.56%  |
| 351-400     | 14        | 6.8%    |
| 501-600     | 12        | 5.83%   |
| 401-500     | 3         | 1.46%   |
| Unknown     | 3         | 1.46%   |
| 1501-2000   | 2         | 0.97%   |
| 801-900     | 1         | 0.49%   |
| 701-800     | 1         | 0.49%   |
| 601-700     | 1         | 0.49%   |
| 101-200     | 1         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 166       | 84.69%  |
| 16/10   | 24        | 12.24%  |
| 5/4     | 2         | 1.02%   |
| Unknown | 2         | 1.02%   |
| 3/2     | 1         | 0.51%   |
| 21/9    | 1         | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 101       | 48.33%  |
| 81-90          | 39        | 18.66%  |
| 71-80          | 13        | 6.22%   |
| 201-250        | 9         | 4.31%   |
| 121-130        | 9         | 4.31%   |
| 61-70          | 6         | 2.87%   |
| 41-50          | 6         | 2.87%   |
| 51-60          | 4         | 1.91%   |
| 251-300        | 4         | 1.91%   |
| 141-150        | 3         | 1.44%   |
| 131-140        | 3         | 1.44%   |
| Unknown        | 3         | 1.44%   |
| More than 1000 | 2         | 0.96%   |
| 351-500        | 2         | 0.96%   |
| 301-350        | 2         | 0.96%   |
| 1-40           | 1         | 0.48%   |
| 501-1000       | 1         | 0.48%   |
| 91-100         | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 85        | 40.87%  |
| 101-120       | 75        | 36.06%  |
| 51-100        | 29        | 13.94%  |
| 161-240       | 12        | 5.77%   |
| More than 240 | 3         | 1.44%   |
| Unknown       | 3         | 1.44%   |
| 1-50          | 1         | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 178       | 87.25%  |
| 2     | 17        | 8.33%   |
| 0     | 8         | 3.92%   |
| 3     | 1         | 0.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 101       | 33.44%  |
| Intel                           | 94        | 31.13%  |
| Qualcomm Atheros                | 44        | 14.57%  |
| Broadcom                        | 26        | 8.61%   |
| Broadcom Limited                | 7         | 2.32%   |
| TP-Link                         | 4         | 1.32%   |
| MediaTek                        | 4         | 1.32%   |
| Marvell Technology Group        | 3         | 0.99%   |
| Xiaomi                          | 2         | 0.66%   |
| Ralink Technology               | 2         | 0.66%   |
| Dell                            | 2         | 0.66%   |
| Spreadtrum Communications       | 1         | 0.33%   |
| Sierra Wireless                 | 1         | 0.33%   |
| Samsung Electronics             | 1         | 0.33%   |
| Ralink                          | 1         | 0.33%   |
| Qualcomm Atheros Communications | 1         | 0.33%   |
| OnePlus Technology (Shenzhen)   | 1         | 0.33%   |
| Nvidia                          | 1         | 0.33%   |
| Lenovo                          | 1         | 0.33%   |
| JMicron Technology              | 1         | 0.33%   |
| Hewlett-Packard                 | 1         | 0.33%   |
| Google                          | 1         | 0.33%   |
| Edimax Technology               | 1         | 0.33%   |
| Davicom Semiconductor           | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49        | 12.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 5.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 14        | 3.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 2.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 2.11%   |
| Intel Wireless 8265 / 8275                                        | 8         | 2.11%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 2.11%   |
| Intel Wireless 8260                                               | 7         | 1.84%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 1.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 7         | 1.84%   |
| Intel Wireless 7260                                               | 6         | 1.58%   |
| Intel Wireless 3165                                               | 6         | 1.58%   |
| Intel Ethernet Connection I219-V                                  | 6         | 1.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.32%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 1.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 1.32%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 4         | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 1.05%   |
| Intel Wireless 7265                                               | 4         | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.05%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.05%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 4         | 1.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.79%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.79%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.79%   |
| Intel WiFi Link 5100                                              | 3         | 0.79%   |
| Intel Ultimate N WiFi Link 5300                                   | 3         | 0.79%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.79%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 0.79%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.79%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 2         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 90        | 42.86%  |
| Realtek Semiconductor           | 48        | 22.86%  |
| Qualcomm Atheros                | 32        | 15.24%  |
| Broadcom                        | 20        | 9.52%   |
| Broadcom Limited                | 5         | 2.38%   |
| TP-Link                         | 4         | 1.9%    |
| MediaTek                        | 3         | 1.43%   |
| Ralink Technology               | 2         | 0.95%   |
| Xiaomi                          | 1         | 0.48%   |
| Sierra Wireless                 | 1         | 0.48%   |
| Ralink                          | 1         | 0.48%   |
| Qualcomm Atheros Communications | 1         | 0.48%   |
| Edimax Technology               | 1         | 0.48%   |
| Dell                            | 1         | 0.48%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 6.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 3.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 3.7%    |
| Intel Wireless 8265 / 8275                                              | 8         | 3.7%    |
| Intel Wi-Fi 6 AX201                                                     | 8         | 3.7%    |
| Intel Wireless 8260                                                     | 7         | 3.24%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 3.24%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 3.24%   |
| Intel Wireless 7260                                                     | 6         | 2.78%   |
| Intel Wireless 3165                                                     | 6         | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 2.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 2.31%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 4         | 1.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 1.85%   |
| Intel Wireless 7265                                                     | 4         | 1.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 1.39%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.39%   |
| Intel WiFi Link 5100                                                    | 3         | 1.39%   |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 1.39%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 1.39%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.39%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 2         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.93%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 2         | 0.93%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 2         | 0.93%   |
| Realtek RTL8187B Wireless Adapter                                       | 2         | 0.93%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.93%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.93%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.93%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 0.93%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.93%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 2         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 81        | 50%     |
| Intel                         | 37        | 22.84%  |
| Qualcomm Atheros              | 21        | 12.96%  |
| Broadcom                      | 7         | 4.32%   |
| Marvell Technology Group      | 3         | 1.85%   |
| Broadcom Limited              | 2         | 1.23%   |
| Xiaomi                        | 1         | 0.62%   |
| Spreadtrum Communications     | 1         | 0.62%   |
| Samsung Electronics           | 1         | 0.62%   |
| OnePlus Technology (Shenzhen) | 1         | 0.62%   |
| Nvidia                        | 1         | 0.62%   |
| MediaTek                      | 1         | 0.62%   |
| Lenovo                        | 1         | 0.62%   |
| JMicron Technology            | 1         | 0.62%   |
| Hewlett-Packard               | 1         | 0.62%   |
| Google                        | 1         | 0.62%   |
| Davicom Semiconductor         | 1         | 0.62%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49        | 30.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 13.58%  |
| Intel Ethernet Connection I219-V                                  | 6         | 3.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 3.09%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 3.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 3.09%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 2.47%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 4         | 2.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.85%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 1.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.85%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 1.85%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.85%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.23%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 1.23%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 1.23%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.23%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.23%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.23%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.62%   |
| Spreadtrum Nokia G21                                              | 1         | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.62%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.62%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.62%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.62%   |
| OnePlus (Shenzhen) Android                                        | 1         | 0.62%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.62%   |
| MediaTek KINGKONG_MINI                                            | 1         | 0.62%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.62%   |
| Lenovo ThinkPad Lan                                               | 1         | 0.62%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.62%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.62%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.62%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.62%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.62%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 199       | 55.9%   |
| Ethernet | 155       | 43.54%  |
| Modem    | 2         | 0.56%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 150       | 72.12%  |
| Ethernet | 58        | 27.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 142       | 70.65%  |
| 1     | 51        | 25.37%  |
| 0     | 8         | 3.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 139       | 69.15%  |
| Yes  | 62        | 30.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 45.39%  |
| Realtek Semiconductor           | 29        | 20.57%  |
| Foxconn / Hon Hai               | 9         | 6.38%   |
| Broadcom                        | 7         | 4.96%   |
| Qualcomm Atheros Communications | 6         | 4.26%   |
| Lite-On Technology              | 6         | 4.26%   |
| Apple                           | 5         | 3.55%   |
| Hewlett-Packard                 | 4         | 2.84%   |
| Dell                            | 4         | 2.84%   |
| IMC Networks                    | 3         | 2.13%   |
| Foxconn International           | 2         | 1.42%   |
| Chicony Electronics             | 1         | 0.71%   |
| Cambridge Silicon Radio         | 1         | 0.71%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 29        | 20.57%  |
| Realtek Bluetooth Radio                                     | 20        | 14.18%  |
| Intel AX201 Bluetooth                                       | 13        | 9.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 10        | 7.09%   |
| Intel AX200 Bluetooth                                       | 6         | 4.26%   |
| Realtek  Bluetooth 4.2 Adapter                              | 5         | 3.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 2.13%   |
| Intel AX210 Bluetooth                                       | 3         | 2.13%   |
| Foxconn / Hon Hai Wireless_Device                           | 3         | 2.13%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 1.42%   |
| Qualcomm Atheros  Bluetooth Device                          | 2         | 1.42%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.42%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 1.42%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 1.42%   |
| HP Broadcom 2070 Bluetooth Combo                            | 2         | 1.42%   |
| Foxconn International BCM43142A0 Bluetooth module           | 2         | 1.42%   |
| Foxconn / Hon Hai Bluetooth Device                          | 2         | 1.42%   |
| Dell Wireless 370 Bluetooth Mini-card                       | 2         | 1.42%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.42%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 2         | 1.42%   |
| Apple Bluetooth USB Host Controller                         | 2         | 1.42%   |
| Apple Bluetooth Host Controller                             | 2         | 1.42%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.71%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.71%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.71%   |
| Lite-On Bluetooth Device                                    | 1         | 0.71%   |
| Intel Bluetooth Device                                      | 1         | 0.71%   |
| IMC Networks Bluetooth Radio                                | 1         | 0.71%   |
| IMC Networks Bluetooth Device                               | 1         | 0.71%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.71%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.71%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.71%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller             | 1         | 0.71%   |
| Foxconn / Hon Hai BCM43142A0                                | 1         | 0.71%   |
| Foxconn / Hon Hai Acer Module                               | 1         | 0.71%   |
| Foxconn / Hon Hai Acer Bluetooth module                     | 1         | 0.71%   |
| Dell Broadcom BCM20702A0 Bluetooth                          | 1         | 0.71%   |
| Dell BCM20702A0 Bluetooth Module                            | 1         | 0.71%   |
| Chicony Bluetooth (RTL8723BE)                               | 1         | 0.71%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 158       | 67.23%  |
| AMD                   | 48        | 20.43%  |
| Nvidia                | 22        | 9.36%   |
| Texas Instruments     | 3         | 1.28%   |
| Yamaha                | 1         | 0.43%   |
| Realtek Semiconductor | 1         | 0.43%   |
| GN Netcom             | 1         | 0.43%   |
| Audioengine           | 1         | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 24        | 8.28%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 6.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 6.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 17        | 5.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 4.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 3.79%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 3.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 3.79%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 3.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 3.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 2.41%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 2.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 2.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 2.07%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 2.07%   |
| AMD FCH Azalia Controller                                                                         | 6         | 2.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.72%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.38%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.03%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 1.03%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.03%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 1.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.03%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.03%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.03%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 1.03%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.03%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.03%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 1.03%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.69%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.69%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.69%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 29        | 29%     |
| SK hynix                     | 21        | 21%     |
| Unknown                      | 12        | 12%     |
| Micron Technology            | 9         | 9%      |
| Kingston                     | 7         | 7%      |
| G.Skill                      | 3         | 3%      |
| A-DATA Technology            | 3         | 3%      |
| Unknown (ABCD)               | 2         | 2%      |
| Ramaxel Technology           | 2         | 2%      |
| Nanya Technology             | 2         | 2%      |
| GSkill                       | 2         | 2%      |
| Crucial                      | 2         | 2%      |
| Strontium                    | 1         | 1%      |
| Patriot Memory (PDP Systems) | 1         | 1%      |
| Lexar Co Limited             | 1         | 1%      |
| Corsair                      | 1         | 1%      |
| AMD                          | 1         | 1%      |
| Unknown                      | 1         | 1%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                               | 2         | 1.87%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s          | 2         | 1.87%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                              | 2         | 1.87%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 2         | 1.87%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                     | 2         | 1.87%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.87%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 2         | 1.87%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s                     | 2         | 1.87%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                               | 1         | 0.93%   |
| Unknown RAM Module 8GB SODIMM DDR3                                        | 1         | 0.93%   |
| Unknown RAM Module 512MB SODIMM DDR                                       | 1         | 0.93%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                               | 1         | 0.93%   |
| Unknown RAM Module 2GB SODIMM SDRAM                                       | 1         | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 1         | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                                | 1         | 0.93%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 1         | 0.93%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                       | 1         | 0.93%   |
| Unknown RAM Module 1GB SODIMM DDR2                                        | 1         | 0.93%   |
| Unknown RAM Module 1GB SODIMM DDR                                         | 1         | 0.93%   |
| Strontium RAM SRT4G86S0-H9H 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.93%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                             | 1         | 0.93%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                             | 1         | 0.93%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s                     | 1         | 0.93%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.93%   |
| SK hynix RAM HMT451S6MFR8A-PB 4096MB SODIMM DDR3 1600MT/s                 | 1         | 0.93%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.93%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                    | 1         | 0.93%   |
| SK hynix RAM HMT425S6AFR6A-H9 2GB SODIMM DDR3 1333MT/s                    | 1         | 0.93%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.93%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.93%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s                    | 1         | 0.93%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                    | 1         | 0.93%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s                    | 1         | 0.93%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.93%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s                    | 1         | 0.93%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.93%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 1         | 0.93%   |
| SK hynix RAM 161616161616161616161616161616161616 1GB SODIMM DDR2 667MT/s | 1         | 0.93%   |
| SK hynix RAM 0C0C0C0C0C0C0C0C0C0C0C0C0C0C0C0C0C0C 1GB SODIMM DDR2 667MT/s | 1         | 0.93%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                               | 1         | 0.93%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 41        | 46.07%  |
| DDR3   | 31        | 34.83%  |
| DDR2   | 7         | 7.87%   |
| SDRAM  | 4         | 4.49%   |
| LPDDR4 | 3         | 3.37%   |
| LPDDR3 | 2         | 2.25%   |
| DDR    | 1         | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 85        | 94.44%  |
| Row Of Chips | 4         | 4.44%   |
| Unknown      | 1         | 1.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 34        | 35.42%  |
| 4096  | 23        | 23.96%  |
| 2048  | 22        | 22.92%  |
| 16384 | 10        | 10.42%  |
| 32768 | 3         | 3.13%   |
| 1024  | 3         | 3.13%   |
| 512   | 1         | 1.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 25        | 26.88%  |
| 1600    | 20        | 21.51%  |
| 2667    | 13        | 13.98%  |
| 2400    | 7         | 7.53%   |
| Unknown | 5         | 5.38%   |
| 1067    | 4         | 4.3%    |
| 667     | 4         | 4.3%    |
| 1334    | 3         | 3.23%   |
| 4199    | 2         | 2.15%   |
| 2133    | 2         | 2.15%   |
| 4267    | 1         | 1.08%   |
| 3266    | 1         | 1.08%   |
| 2267    | 1         | 1.08%   |
| 2048    | 1         | 1.08%   |
| 1867    | 1         | 1.08%   |
| 1333    | 1         | 1.08%   |
| 1200    | 1         | 1.08%   |
| 533     | 1         | 1.08%   |

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
| Chicony Electronics                    | 37        | 21.76%  |
| Microdia                               | 20        | 11.76%  |
| IMC Networks                           | 17        | 10%     |
| Suyin                                  | 13        | 7.65%   |
| Realtek Semiconductor                  | 12        | 7.06%   |
| Acer                                   | 12        | 7.06%   |
| Quanta                                 | 11        | 6.47%   |
| Luxvisions Innotech Limited            | 8         | 4.71%   |
| Sunplus Innovation Technology          | 7         | 4.12%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.12%   |
| Alcor Micro                            | 4         | 2.35%   |
| Importek                               | 3         | 1.76%   |
| Bison Electronics                      | 3         | 1.76%   |
| Apple                                  | 3         | 1.76%   |
| Syntek                                 | 2         | 1.18%   |
| Silicon Motion                         | 2         | 1.18%   |
| Lenovo                                 | 2         | 1.18%   |
| Z-Star Microelectronics                | 1         | 0.59%   |
| USB Camera                             | 1         | 0.59%   |
| Lite-On Technology                     | 1         | 0.59%   |
| Intel                                  | 1         | 0.59%   |
| eMPIA Technology                       | 1         | 0.59%   |
| Alpha Imaging Technology               | 1         | 0.59%   |
| ALi                                    | 1         | 0.59%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 11        | 6.47%   |
| Chicony Integrated Camera                               | 11        | 6.47%   |
| Acer Integrated Camera                                  | 7         | 4.12%   |
| Realtek USB2.0 camera                                   | 4         | 2.35%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 4         | 2.35%   |
| IMC Networks Integrated Camera                          | 4         | 2.35%   |
| Chicony HP TrueVision HD Camera                         | 4         | 2.35%   |
| Chicony HD WebCam                                       | 4         | 2.35%   |
| Realtek Lenovo EasyCamera                               | 3         | 1.76%   |
| Quanta HP TrueVision HD Camera                          | 3         | 1.76%   |
| Microdia USB 2.0 Camera                                 | 3         | 1.76%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera    | 3         | 1.76%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 1.76%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 3         | 1.76%   |
| Syntek Integrated Camera                                | 2         | 1.18%   |
| Suyin HP TrueVision HD                                  | 2         | 1.18%   |
| Suyin HD WebCam                                         | 2         | 1.18%   |
| Suyin Acer HD Crystal Eye webcam                        | 2         | 1.18%   |
| Sunplus HD WebCam                                       | 2         | 1.18%   |
| Quanta HP Webcam                                        | 2         | 1.18%   |
| Quanta HP HD Camera                                     | 2         | 1.18%   |
| IMC Networks EasyCamera                                 | 2         | 1.18%   |
| Chicony TOSHIBA Web Camera - FHD                        | 2         | 1.18%   |
| Chicony HP HD Camera                                    | 2         | 1.18%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.18%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 2         | 1.18%   |
| Bison USB2.0 Camera                                     | 2         | 1.18%   |
| Alcor Micro USB 2.0 Camera                              | 2         | 1.18%   |
| Z-Star WebCam SC-03FFL11739P                            | 1         | 0.59%   |
| USB Camera USB Camera                                   | 1         | 0.59%   |
| Suyin Lenovo EasyCamera                                 | 1         | 0.59%   |
| Suyin Integrated_Webcam_HD                              | 1         | 0.59%   |
| Suyin HP Webcam-101                                     | 1         | 0.59%   |
| Suyin HP TrueVision HD Integrated Webcam                | 1         | 0.59%   |
| Suyin Acer/Lenovo Webcam [CN0316]                       | 1         | 0.59%   |
| Suyin Acer CrystalEye Webcam                            | 1         | 0.59%   |
| Suyin 1.3M HD WebCam                                    | 1         | 0.59%   |
| Sunplus USB Camera                                      | 1         | 0.59%   |
| Sunplus Laptop Integrated Webcam FHD                    | 1         | 0.59%   |
| Sunplus HP TrueVision HD Camera                         | 1         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 48.28%  |
| Synaptics                  | 3         | 10.34%  |
| AuthenTec                  | 3         | 10.34%  |
| STMicroelectronics         | 2         | 6.9%    |
| Shenzhen Goodix Technology | 2         | 6.9%    |
| Upek                       | 1         | 3.45%   |
| Microsoft                  | 1         | 3.45%   |
| LighTuning Technology      | 1         | 3.45%   |
| Focal-systems.Corp         | 1         | 3.45%   |
| Elan Microelectronics      | 1         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader               | 3         | 10.34%  |
| Validity Sensors Synaptics WBDI                          | 2         | 6.9%    |
| Validity Sensors Fingerprint scanner                     | 2         | 6.9%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 6.9%    |
| STMicroelectronics Fingerprint Reader                    | 2         | 6.9%    |
| Shenzhen Goodix  FingerPrint Device                      | 2         | 6.9%    |
| AuthenTec AES1600                                        | 2         | 6.9%    |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 3.45%   |
| Validity Sensors VFS491                                  | 1         | 3.45%   |
| Validity Sensors VFS451 Fingerprint Reader               | 1         | 3.45%   |
| Validity Sensors VFS301 Fingerprint Reader               | 1         | 3.45%   |
| Validity Sensors VFS Fingerprint sensor                  | 1         | 3.45%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 3.45%   |
| Validity Sensors Swipe Fingerprint Sensor                | 1         | 3.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 1         | 3.45%   |
| Synaptics UWP WBDI Device                                | 1         | 3.45%   |
| Microsoft Fingerprint Reader                             | 1         | 3.45%   |
| LighTuning Fingerprint Reader                            | 1         | 3.45%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 3.45%   |
| Elan ELAN:Fingerprint                                    | 1         | 3.45%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 1         | 3.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 45.45%  |
| O2 Micro    | 2         | 18.18%  |
| Alcor Micro | 2         | 18.18%  |
| Upek        | 1         | 9.09%   |
| Lenovo      | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor             | 3         | 27.27%  |
| O2 Micro OZ776 CCID Smartcard Reader                       | 2         | 18.18%  |
| Alcor Micro AU9540 Smartcard Reader                        | 2         | 18.18%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 9.09%   |
| Lenovo Integrated Smart Card Reader                        | 1         | 9.09%   |
| Broadcom 5880                                              | 1         | 9.09%   |
| Broadcom 58200                                             | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 135       | 65.53%  |
| 1     | 57        | 27.67%  |
| 2     | 11        | 5.34%   |
| 4     | 2         | 0.97%   |
| 3     | 1         | 0.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 28        | 31.46%  |
| Net/wireless             | 19        | 21.35%  |
| Multimedia controller    | 13        | 14.61%  |
| Graphics card            | 13        | 14.61%  |
| Chipcard                 | 10        | 11.24%  |
| Communication controller | 2         | 2.25%   |
| Bluetooth                | 2         | 2.25%   |
| Dvb card                 | 1         | 1.12%   |
| Card reader              | 1         | 1.12%   |

