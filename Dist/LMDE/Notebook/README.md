LMDE - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for LMDE.

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

Total: 657

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
| Acer          | Aspire 3000                 | [02693e03ca](https://linux-hardware.org/?probe=02693e03ca) | Nov 01, 2022 |
| HP            | Pavilion dv6                | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
| HP            | Laptop 15-da0xxx            | [554f0e2130](https://linux-hardware.org/?probe=554f0e2130) | Oct 30, 2022 |
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
| HP            | Laptop 15-da0xxx            | [c62874f456](https://linux-hardware.org/?probe=c62874f456) | Oct 04, 2022 |
| ASUSTek       | K54LY                       | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| Unknown       | Unknown                     | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | Inspiron 5420               | [71f7e67ca7](https://linux-hardware.org/?probe=71f7e67ca7) | Oct 01, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [d277bf47ec](https://linux-hardware.org/?probe=d277bf47ec) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [fb7029173f](https://linux-hardware.org/?probe=fb7029173f) | Sep 25, 2022 |
| HP            | Laptop 14-cf3xxx            | [9386d6b529](https://linux-hardware.org/?probe=9386d6b529) | Sep 23, 2022 |
| HP            | Laptop 14-cf3xxx            | [3ba944192e](https://linux-hardware.org/?probe=3ba944192e) | Sep 22, 2022 |
| ASUSTek       | K56CB                       | [7a7717e793](https://linux-hardware.org/?probe=7a7717e793) | Sep 21, 2022 |
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
| HP            | Notebook                    | [487cfc16fc](https://linux-hardware.org/?probe=487cfc16fc) | Aug 10, 2022 |
| HP            | Laptop 14-cf3xxx            | [2f628ea3bb](https://linux-hardware.org/?probe=2f628ea3bb) | Aug 09, 2022 |
| Wortmann      | TERRA_MOBILE_1713A          | [09f3eadbcf](https://linux-hardware.org/?probe=09f3eadbcf) | Aug 07, 2022 |
| HP            | Laptop 14-cf3xxx            | [2f565b89db](https://linux-hardware.org/?probe=2f565b89db) | Aug 06, 2022 |
| Dynabook      | Satellite Pro C50-G         | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| HP            | Laptop 14-cf3xxx            | [f6caa753ba](https://linux-hardware.org/?probe=f6caa753ba) | Aug 04, 2022 |
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
| HP            | Laptop 14-cf3xxx            | [63722e3660](https://linux-hardware.org/?probe=63722e3660) | Jul 23, 2022 |
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
| Acer          | AOD270                      | [b53cedd40c](https://linux-hardware.org/?probe=b53cedd40c) | Apr 23, 2022 |
| Dixonsxp      | Unknown                     | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| Toshiba       | Satellite L455              | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| Dell          | 0X574R                      | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| HP            | 14                          | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Dell          | Latitude 3410               | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| ASUSTek       | N61Jv                       | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Acer          | AOA110                      | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| Howard Com... | R7X                         | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [6fbd04d8fd](https://linux-hardware.org/?probe=6fbd04d8fd) | Apr 11, 2022 |
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
| ASUSTek       | 901                         | [d118ee90d5](https://linux-hardware.org/?probe=d118ee90d5) | Apr 01, 2022 |
| HP            | ProBook 6570b               | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Lenovo        | IdeaPad S110 20126          | [9113320f2f](https://linux-hardware.org/?probe=9113320f2f) | Mar 31, 2022 |
| Lenovo        | IdeaPad S110 20126          | [d02cab0935](https://linux-hardware.org/?probe=d02cab0935) | Mar 30, 2022 |
| Packard Be... | DOT S                       | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| Dell          | Latitude E6400              | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Dell          | Latitude D620               | [172cd26e35](https://linux-hardware.org/?probe=172cd26e35) | Mar 26, 2022 |
| Toshiba       | Satellite L455              | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| HP            | ProBook 6465b               | [2e1792442b](https://linux-hardware.org/?probe=2e1792442b) | Mar 24, 2022 |
| HP            | ProBook 6465b               | [51a296abf8](https://linux-hardware.org/?probe=51a296abf8) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |
| Acer          | TravelMate 420              | [13cae0e399](https://linux-hardware.org/?probe=13cae0e399) | Mar 14, 2022 |
| Lenovo        | IdeaPad Z470                | [b1ca65b3e0](https://linux-hardware.org/?probe=b1ca65b3e0) | Mar 08, 2022 |
| ASUSTek       | X101CH                      | [486f5c28ad](https://linux-hardware.org/?probe=486f5c28ad) | Mar 07, 2022 |
| Dell          | Latitude D620               | [d4e50f40f3](https://linux-hardware.org/?probe=d4e50f40f3) | Mar 06, 2022 |
| HP            | ENVY 6                      | [23f60a7428](https://linux-hardware.org/?probe=23f60a7428) | Mar 02, 2022 |
| Lenovo        | IdeaPad Z470                | [d163816373](https://linux-hardware.org/?probe=d163816373) | Mar 02, 2022 |
| ASUSTek       | UX490UAR                    | [6b6c4bd7b7](https://linux-hardware.org/?probe=6b6c4bd7b7) | Feb 28, 2022 |
| ASUSTek       | UX490UAR                    | [544979fc4f](https://linux-hardware.org/?probe=544979fc4f) | Feb 27, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | [4bd308dadf](https://linux-hardware.org/?probe=4bd308dadf) | Feb 26, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | [ec2491adc1](https://linux-hardware.org/?probe=ec2491adc1) | Feb 26, 2022 |
| Acer          | Swift SF315-52              | [74009233c2](https://linux-hardware.org/?probe=74009233c2) | Feb 19, 2022 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [e2ab1c19df](https://linux-hardware.org/?probe=e2ab1c19df) | Feb 18, 2022 |
| HP            | Laptop 14-bs0xx             | [2b5b67148b](https://linux-hardware.org/?probe=2b5b67148b) | Feb 18, 2022 |
| EVOO          | EVC141-12                   | [25710a76b8](https://linux-hardware.org/?probe=25710a76b8) | Feb 18, 2022 |
| Samsung       | NC210/NC110                 | [bf2672168d](https://linux-hardware.org/?probe=bf2672168d) | Feb 14, 2022 |
| Samsung       | NC210/NC110                 | [bcbb1884aa](https://linux-hardware.org/?probe=bcbb1884aa) | Feb 13, 2022 |
| ASUSTek       | X101CH                      | [82661c6a9b](https://linux-hardware.org/?probe=82661c6a9b) | Feb 12, 2022 |
| ASUSTek       | 901                         | [27a497fdf8](https://linux-hardware.org/?probe=27a497fdf8) | Feb 04, 2022 |
| Acer          | Aspire 3820                 | [e6091c93a9](https://linux-hardware.org/?probe=e6091c93a9) | Feb 02, 2022 |
| Toshiba       | Satellite A200              | [9086ec49b6](https://linux-hardware.org/?probe=9086ec49b6) | Jan 21, 2022 |
| LG Electro... | A530-T.BE76P1               | [9fdbf19ebf](https://linux-hardware.org/?probe=9fdbf19ebf) | Jan 09, 2022 |
| Google        | Falco                       | [f450676688](https://linux-hardware.org/?probe=f450676688) | Jan 09, 2022 |
| Packard Be... | EasyNote TE69BM             | [526fc1b476](https://linux-hardware.org/?probe=526fc1b476) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | [675eb28882](https://linux-hardware.org/?probe=675eb28882) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | [203577c78f](https://linux-hardware.org/?probe=203577c78f) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | [41e93113b5](https://linux-hardware.org/?probe=41e93113b5) | Jan 05, 2022 |
| Dell          | System Inspiron N7110       | [c977f6d6af](https://linux-hardware.org/?probe=c977f6d6af) | Jan 05, 2022 |
| ASUSTek       | K46CA                       | [61978f9418](https://linux-hardware.org/?probe=61978f9418) | Jan 04, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [9d4bddea4d](https://linux-hardware.org/?probe=9d4bddea4d) | Jan 03, 2022 |
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
| Medion        | P6670 MD99960               | [eaa186d207](https://linux-hardware.org/?probe=eaa186d207) | Oct 12, 2021 |
| Medion        | P6670 MD99960               | [d42f345fc5](https://linux-hardware.org/?probe=d42f345fc5) | Oct 12, 2021 |
| HP            | 520                         | [4aea2d24b1](https://linux-hardware.org/?probe=4aea2d24b1) | Oct 10, 2021 |
| Dell          | Precision M2800             | [b046a9dfe3](https://linux-hardware.org/?probe=b046a9dfe3) | Oct 08, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | [633c289440](https://linux-hardware.org/?probe=633c289440) | Sep 28, 2021 |
| Apple         | MacBookPro5,4               | [a6d07be7c9](https://linux-hardware.org/?probe=a6d07be7c9) | Sep 27, 2021 |
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
| ASUSTek       | 1201HA                      | [eadb8752c9](https://linux-hardware.org/?probe=eadb8752c9) | Aug 28, 2021 |
| HP            | Pavilion dv2000 (RD665EA... | [3b6dfaf6db](https://linux-hardware.org/?probe=3b6dfaf6db) | Aug 25, 2021 |
| Fujitsu       | LIFEBOOK A556/G             | [7706314dbc](https://linux-hardware.org/?probe=7706314dbc) | Aug 24, 2021 |
| Itautec       | W7655                       | [82b2d38326](https://linux-hardware.org/?probe=82b2d38326) | Aug 24, 2021 |
| Itautec       | W7655                       | [5952ec3a0f](https://linux-hardware.org/?probe=5952ec3a0f) | Aug 24, 2021 |
| HP            | 14                          | [e6bbdc5a92](https://linux-hardware.org/?probe=e6bbdc5a92) | Aug 24, 2021 |
| ASUSTek       | M51Sn                       | [5acb8c28ad](https://linux-hardware.org/?probe=5acb8c28ad) | Aug 21, 2021 |
| Packard Be... | EasyNote_NJ66               | [03c09865f3](https://linux-hardware.org/?probe=03c09865f3) | Aug 19, 2021 |
| ASUSTek       | N550JV                      | [f56a2bd3fa](https://linux-hardware.org/?probe=f56a2bd3fa) | Aug 14, 2021 |
| Toshiba       | Satellite M100              | [8dff0ec788](https://linux-hardware.org/?probe=8dff0ec788) | Aug 10, 2021 |
| Toshiba       | Satellite M100              | [06e766539d](https://linux-hardware.org/?probe=06e766539d) | Aug 10, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [8648635717](https://linux-hardware.org/?probe=8648635717) | Aug 07, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [16bec20604](https://linux-hardware.org/?probe=16bec20604) | Aug 06, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [dec7f65882](https://linux-hardware.org/?probe=dec7f65882) | Aug 06, 2021 |
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
| Gateway       | LT40                        | [fe2551cb8b](https://linux-hardware.org/?probe=fe2551cb8b) | Jun 11, 2021 |
| Acer          | Aspire 3000                 | [f6a944ee4a](https://linux-hardware.org/?probe=f6a944ee4a) | Jun 09, 2021 |
| Sony          | VPCEB3L1E                   | [bc3c3b537b](https://linux-hardware.org/?probe=bc3c3b537b) | Jun 06, 2021 |
| HP            | Laptop 15-dw0xxx            | [4f752689ed](https://linux-hardware.org/?probe=4f752689ed) | Jun 03, 2021 |
| Gateway       | LT40                        | [6a966fe471](https://linux-hardware.org/?probe=6a966fe471) | Jun 01, 2021 |
| ASUSTek       | X555UJ                      | [9c148a1665](https://linux-hardware.org/?probe=9c148a1665) | May 25, 2021 |
| HP            | Pavilion dv6                | [fb309a7f37](https://linux-hardware.org/?probe=fb309a7f37) | May 17, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
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
| Acer          | Aspire 7750G                | [68c2e2956e](https://linux-hardware.org/?probe=68c2e2956e) | Feb 21, 2021 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [078eb9c9b9](https://linux-hardware.org/?probe=078eb9c9b9) | Feb 19, 2021 |
| Acer          | Aspire 6930ZG               | [5e2260251a](https://linux-hardware.org/?probe=5e2260251a) | Feb 19, 2021 |
| Google        | Gnawty                      | [f2d007d3b0](https://linux-hardware.org/?probe=f2d007d3b0) | Feb 16, 2021 |
| Google        | Gnawty                      | [cf74012060](https://linux-hardware.org/?probe=cf74012060) | Feb 16, 2021 |
| Google        | Gnawty                      | [802daa9713](https://linux-hardware.org/?probe=802daa9713) | Feb 16, 2021 |
| Dell          | Latitude E6520              | [132c1f74fc](https://linux-hardware.org/?probe=132c1f74fc) | Feb 14, 2021 |
| Notebook      | WID2010                     | [289d2b0685](https://linux-hardware.org/?probe=289d2b0685) | Feb 10, 2021 |
| LG Electro... | X120-G.C7VPG                | [349c20610a](https://linux-hardware.org/?probe=349c20610a) | Feb 10, 2021 |
| Dell          | Inspiron 7520               | [f4995bc45c](https://linux-hardware.org/?probe=f4995bc45c) | Feb 07, 2021 |
| HP            | EliteBook 820 G3            | [b67948603a](https://linux-hardware.org/?probe=b67948603a) | Feb 04, 2021 |
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
| Matsushita... | CF-19CHB23BE                | [e9fa72450f](https://linux-hardware.org/?probe=e9fa72450f) | Jan 14, 2021 |
| Acer          | Aspire 5930                 | [0826a741c2](https://linux-hardware.org/?probe=0826a741c2) | Jan 13, 2021 |
| Acer          | Aspire 5930                 | [e9f548f926](https://linux-hardware.org/?probe=e9f548f926) | Jan 13, 2021 |
| Dell          | Inspiron 7520               | [f894e05226](https://linux-hardware.org/?probe=f894e05226) | Jan 09, 2021 |
| Acer          | AOD270                      | [89562751d7](https://linux-hardware.org/?probe=89562751d7) | Jan 08, 2021 |
| Exper         | E10IL1                      | [8a1f9ff144](https://linux-hardware.org/?probe=8a1f9ff144) | Dec 31, 2020 |
| Dell          | Precision M4800             | [10bfd0b228](https://linux-hardware.org/?probe=10bfd0b228) | Dec 27, 2020 |
| ASUSTek       | K55N                        | [e3edf30a97](https://linux-hardware.org/?probe=e3edf30a97) | Dec 26, 2020 |
| ASUSTek       | K55N                        | [d7630d7410](https://linux-hardware.org/?probe=d7630d7410) | Dec 26, 2020 |
| Apple         | MacBookPro5,5               | [95d4d575bf](https://linux-hardware.org/?probe=95d4d575bf) | Dec 26, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | [c0f1039074](https://linux-hardware.org/?probe=c0f1039074) | Dec 24, 2020 |
| Lenovo        | ThinkPad X230 2325CN3       | [5584ad5871](https://linux-hardware.org/?probe=5584ad5871) | Dec 24, 2020 |
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
| HP            | Pavilion ze2000 (EA772AV... | [15284f8c6e](https://linux-hardware.org/?probe=15284f8c6e) | Dec 07, 2020 |
| Dell          | Precision M4600             | [690e349224](https://linux-hardware.org/?probe=690e349224) | Dec 06, 2020 |
| Dell          | Precision M4600             | [f2023ec8ae](https://linux-hardware.org/?probe=f2023ec8ae) | Dec 06, 2020 |
| Acer          | Extensa 4620                | [1bda4268f4](https://linux-hardware.org/?probe=1bda4268f4) | Dec 04, 2020 |
| Matsushita... | CF-19CHB23BE                | [a81d111827](https://linux-hardware.org/?probe=a81d111827) | Nov 25, 2020 |
| ASUSTek       | X550VX                      | [b22a35a959](https://linux-hardware.org/?probe=b22a35a959) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [18d99f9e4f](https://linux-hardware.org/?probe=18d99f9e4f) | Nov 22, 2020 |
| Lenovo        | IdeaPad Y700 Touch-15ISK... | [c17dc0982c](https://linux-hardware.org/?probe=c17dc0982c) | Nov 22, 2020 |
| Lenovo        | ThinkPad T60p 8742C4G       | [9d369e30fd](https://linux-hardware.org/?probe=9d369e30fd) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | [dbac4eb570](https://linux-hardware.org/?probe=dbac4eb570) | Nov 20, 2020 |
| MSI           | GT70 2PC                    | [b070b2d112](https://linux-hardware.org/?probe=b070b2d112) | Nov 18, 2020 |
| HP            | Compaq Presario CQ60        | [c9f4c7eefd](https://linux-hardware.org/?probe=c9f4c7eefd) | Nov 16, 2020 |
| HP            | Unknown                     | [b525a6fdd2](https://linux-hardware.org/?probe=b525a6fdd2) | Nov 15, 2020 |
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
| Dell          | Latitude E6220              | [b3af9d8439](https://linux-hardware.org/?probe=b3af9d8439) | Oct 30, 2020 |
| Dell          | Latitude E6220              | [7df244c05f](https://linux-hardware.org/?probe=7df244c05f) | Oct 30, 2020 |
| Dell          | Inspiron 3521               | [c85f72911e](https://linux-hardware.org/?probe=c85f72911e) | Oct 29, 2020 |
| HP            | EliteBook 8470p             | [dd6fd8b99c](https://linux-hardware.org/?probe=dd6fd8b99c) | Oct 24, 2020 |
| ASUSTek       | X551MA                      | [bc2de7b987](https://linux-hardware.org/?probe=bc2de7b987) | Oct 23, 2020 |
| ASUSTek       | X551MA                      | [ad50a3e36d](https://linux-hardware.org/?probe=ad50a3e36d) | Oct 22, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [c00341fecd](https://linux-hardware.org/?probe=c00341fecd) | Oct 21, 2020 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [83c0ae72b0](https://linux-hardware.org/?probe=83c0ae72b0) | Oct 21, 2020 |
| Unknown       | Unknown                     | [f786cfb7ca](https://linux-hardware.org/?probe=f786cfb7ca) | Oct 18, 2020 |
| ASUSTek       | GL503VM                     | [a6705573f8](https://linux-hardware.org/?probe=a6705573f8) | Oct 11, 2020 |
| HP            | EliteBook 8470p             | [27fe34d7e1](https://linux-hardware.org/?probe=27fe34d7e1) | Oct 09, 2020 |
| Acer          | Aspire 5680                 | [3ef4868294](https://linux-hardware.org/?probe=3ef4868294) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [0053b1ef76](https://linux-hardware.org/?probe=0053b1ef76) | Oct 07, 2020 |
| Lenovo        | B71-80 80RJ                 | [a5135ffb54](https://linux-hardware.org/?probe=a5135ffb54) | Oct 04, 2020 |
| Dell          | Latitude E6400              | [5d51e1eab7](https://linux-hardware.org/?probe=5d51e1eab7) | Oct 04, 2020 |
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
| Dell          | Latitude E5570              | [20fc42be1b](https://linux-hardware.org/?probe=20fc42be1b) | May 06, 2020 |
| Dell          | System Inspiron N411Z       | [246dd5ce2a](https://linux-hardware.org/?probe=246dd5ce2a) | May 05, 2020 |
| Dell          | Latitude E5570              | [a1b049e54c](https://linux-hardware.org/?probe=a1b049e54c) | May 05, 2020 |
| Toshiba       | Satellite U300              | [3bd62e1a59](https://linux-hardware.org/?probe=3bd62e1a59) | May 05, 2020 |
| HP            | Laptop 15-bs2xx             | [6d47f83eac](https://linux-hardware.org/?probe=6d47f83eac) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | [154605446a](https://linux-hardware.org/?probe=154605446a) | May 02, 2020 |
| Lenovo        | E41-25 81FS                 | [e9544d771b](https://linux-hardware.org/?probe=e9544d771b) | May 02, 2020 |
| HP            | G42                         | [be1ea8571f](https://linux-hardware.org/?probe=be1ea8571f) | Apr 28, 2020 |
| Lenovo        | ThinkPad E490 20N80017RT    | [7f84d5a0f2](https://linux-hardware.org/?probe=7f84d5a0f2) | Apr 28, 2020 |
| HP            | G42                         | [8ea8320eac](https://linux-hardware.org/?probe=8ea8320eac) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | [b314d76130](https://linux-hardware.org/?probe=b314d76130) | Apr 27, 2020 |
| HP            | ProBook 430 G5              | [7984248cab](https://linux-hardware.org/?probe=7984248cab) | Apr 26, 2020 |
| Acer          | Aspire E1-572               | [e64e2fe71c](https://linux-hardware.org/?probe=e64e2fe71c) | Apr 23, 2020 |
| HP            | Laptop 15-bs2xx             | [477c5d9ffa](https://linux-hardware.org/?probe=477c5d9ffa) | Apr 17, 2020 |
| Positivo      | Mobile                      | [c7cc7cd357](https://linux-hardware.org/?probe=c7cc7cd357) | Apr 17, 2020 |
| Positivo      | Mobile                      | [55b84972df](https://linux-hardware.org/?probe=55b84972df) | Apr 17, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [4d06bdc501](https://linux-hardware.org/?probe=4d06bdc501) | Apr 14, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [67167458d8](https://linux-hardware.org/?probe=67167458d8) | Apr 14, 2020 |
| Acer          | Aspire E1-572               | [941e12751c](https://linux-hardware.org/?probe=941e12751c) | Apr 14, 2020 |
| Acer          | Aspire E1-570G              | [e727c9003c](https://linux-hardware.org/?probe=e727c9003c) | Apr 10, 2020 |
| Acer          | Aspire E1-570G              | [fe1196d306](https://linux-hardware.org/?probe=fe1196d306) | Apr 09, 2020 |
| Dell          | Latitude E6510              | [5f62bf8564](https://linux-hardware.org/?probe=5f62bf8564) | Apr 07, 2020 |
| Toshiba       | Satellite P300              | [93b28f5a7c](https://linux-hardware.org/?probe=93b28f5a7c) | Apr 03, 2020 |
| ASUSTek       | ZenBook UX431FA             | [3251d5e710](https://linux-hardware.org/?probe=3251d5e710) | Apr 03, 2020 |
| Dell          | Latitude D610               | [44901c9eb2](https://linux-hardware.org/?probe=44901c9eb2) | Mar 30, 2020 |
| Dell          | Latitude D610               | [5bfecb6e64](https://linux-hardware.org/?probe=5bfecb6e64) | Mar 30, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [5c90c49af6](https://linux-hardware.org/?probe=5c90c49af6) | Mar 29, 2020 |
| Dell          | Inspiron 3543               | [5055c4067a](https://linux-hardware.org/?probe=5055c4067a) | Mar 20, 2020 |
| HP            | EliteBook 820 G3            | [b2c3317256](https://linux-hardware.org/?probe=b2c3317256) | Mar 19, 2020 |
| HP            | EliteBook 820 G3            | [2cd8614e59](https://linux-hardware.org/?probe=2cd8614e59) | Mar 17, 2020 |
| HP            | EliteBook 820 G3            | [fcb4ff46b5](https://linux-hardware.org/?probe=fcb4ff46b5) | Mar 17, 2020 |
| Lenovo        | Y50-70 20378                | [7dbce6b0fc](https://linux-hardware.org/?probe=7dbce6b0fc) | Jan 15, 2020 |
| Lenovo        | Y50-70 20378                | [11b0d93285](https://linux-hardware.org/?probe=11b0d93285) | Jan 15, 2020 |
| Dell          | Inspiron 3593               | [9f8af004d3](https://linux-hardware.org/?probe=9f8af004d3) | Nov 29, 2019 |
| Dell          | Inspiron 3593               | [7f4ce08df9](https://linux-hardware.org/?probe=7f4ce08df9) | Nov 29, 2019 |
| Dell          | Inspiron 3593               | [a6ee735c5f](https://linux-hardware.org/?probe=a6ee735c5f) | Nov 29, 2019 |
| Acer          | Aspire V3-571G              | [9be63e6a28](https://linux-hardware.org/?probe=9be63e6a28) | Jan 09, 2019 |
| HP            | Pavilion dv7                | [4480bf8ff3](https://linux-hardware.org/?probe=4480bf8ff3) | Dec 24, 2018 |
| Acer          | Aspire V3-571               | [bb8f83433e](https://linux-hardware.org/?probe=bb8f83433e) | Nov 27, 2018 |
| Acer          | Aspire V3-571               | [1136588271](https://linux-hardware.org/?probe=1136588271) | Nov 27, 2018 |
| HP            | ProBook 4510s               | [dbc607e890](https://linux-hardware.org/?probe=dbc607e890) | Sep 08, 2018 |
| Dell          | Inspiron 11-3162            | [92dcc778ac](https://linux-hardware.org/?probe=92dcc778ac) | Mar 19, 2018 |
| Sony          | VPCEB1M1R                   | [25b5c0689e](https://linux-hardware.org/?probe=25b5c0689e) | Mar 16, 2018 |
| Sony          | VPCSB3M1R                   | [155309a9eb](https://linux-hardware.org/?probe=155309a9eb) | Aug 23, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/LMDE/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| LMDE 4 | 223       | 51.5%   |
| LMDE 5 | 201       | 46.42%  |
| LMDE 3 | 6         | 1.39%   |
| LMDE 2 | 3         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| LMDE | 431       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.10.0-21-amd64        | 33        | 6.95%   |
| 5.10.0-19-amd64        | 29        | 6.11%   |
| 4.19.0-8-amd64         | 27        | 5.68%   |
| 5.10.0-12-amd64        | 25        | 5.26%   |
| 4.19.0-18-amd64        | 24        | 5.05%   |
| 5.10.0-14-amd64        | 20        | 4.21%   |
| 4.19.0-17-amd64        | 20        | 4.21%   |
| 4.19.0-9-amd64         | 18        | 3.79%   |
| 5.10.0-20-amd64        | 17        | 3.58%   |
| 5.10.0-15-amd64        | 16        | 3.37%   |
| 4.19.0-16-amd64        | 16        | 3.37%   |
| 5.10.0-18-amd64        | 14        | 2.95%   |
| 5.10.0-13-amd64        | 14        | 2.95%   |
| 4.19.0-8-686           | 14        | 2.95%   |
| 4.19.0-17-686          | 14        | 2.95%   |
| 4.19.0-14-amd64        | 13        | 2.74%   |
| 4.19.0-13-amd64        | 12        | 2.53%   |
| 5.10.0-16-amd64        | 11        | 2.32%   |
| 4.19.0-16-686          | 11        | 2.32%   |
| 4.19.0-10-amd64        | 11        | 2.32%   |
| 4.19.0-18-686          | 10        | 2.11%   |
| 4.19.0-12-amd64        | 10        | 2.11%   |
| 5.10.0-17-amd64        | 9         | 1.89%   |
| 4.19.0-13-686          | 7         | 1.47%   |
| 4.19.0-11-amd64        | 6         | 1.26%   |
| 5.10.0-13-686          | 5         | 1.05%   |
| 4.19.0-12-686          | 5         | 1.05%   |
| 5.18.0-0.bpo.1-amd64   | 4         | 0.84%   |
| 4.9.0-8-amd64          | 4         | 0.84%   |
| 5.16.0-0.bpo.4-amd64   | 3         | 0.63%   |
| 4.19.0-19-686          | 3         | 0.63%   |
| 4.19.0-14-686          | 3         | 0.63%   |
| 5.4.0-0.bpo.4-amd64    | 2         | 0.42%   |
| 5.19.0-0.deb11.2-amd64 | 2         | 0.42%   |
| 5.15.59-xanmod1        | 2         | 0.42%   |
| 5.10.0-12-686          | 2         | 0.42%   |
| 5.10.0-0.bpo.5-amd64   | 2         | 0.42%   |
| 3.16.0-4-amd64         | 2         | 0.42%   |
| 6.1.11-x64v1-xanmod1   | 1         | 0.21%   |
| 5.9.12-davius          | 1         | 0.21%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19.0  | 212       | 48.18%  |
| 5.10.0  | 192       | 43.64%  |
| 5.18.0  | 6         | 1.36%   |
| 4.9.0   | 5         | 1.14%   |
| 5.16.0  | 3         | 0.68%   |
| 3.16.0  | 3         | 0.68%   |
| 5.6.0   | 2         | 0.45%   |
| 5.4.0   | 2         | 0.45%   |
| 5.19.0  | 2         | 0.45%   |
| 5.15.59 | 2         | 0.45%   |
| 6.1.11  | 1         | 0.23%   |
| 5.9.12  | 1         | 0.23%   |
| 5.9.0   | 1         | 0.23%   |
| 5.8.0   | 1         | 0.23%   |
| 5.4.44  | 1         | 0.23%   |
| 5.19.10 | 1         | 0.23%   |
| 5.15.78 | 1         | 0.23%   |
| 5.15.70 | 1         | 0.23%   |
| 5.15.64 | 1         | 0.23%   |
| 5.15.56 | 1         | 0.23%   |
| 5.15.0  | 1         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.19    | 212       | 48.51%  |
| 5.10    | 192       | 43.94%  |
| 5.18    | 6         | 1.37%   |
| 4.9     | 5         | 1.14%   |
| 5.15    | 4         | 0.92%   |
| 5.4     | 3         | 0.69%   |
| 5.19    | 3         | 0.69%   |
| 5.16    | 3         | 0.69%   |
| 3.16    | 3         | 0.69%   |
| 5.9     | 2         | 0.46%   |
| 5.6     | 2         | 0.46%   |
| 6.1     | 1         | 0.23%   |
| 5.8     | 1         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 352       | 81.67%  |
| i686   | 79        | 18.33%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| X-Cinnamon | 383       | 87.44%  |
| Cinnamon   | 34        | 7.76%   |
| MATE       | 9         | 2.05%   |
| Unknown    | 6         | 1.37%   |
| XFCE       | 2         | 0.46%   |
| Trinity    | 1         | 0.23%   |
| LXDE       | 1         | 0.23%   |
| KDE        | 1         | 0.23%   |
| awesome    | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 431       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 315       | 72.41%  |
| LightDM | 102       | 23.45%  |
| TDM     | 15        | 3.45%   |
| MDM     | 3         | 0.69%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 131       | 30.18%  |
| de_DE   | 54        | 12.44%  |
| ru_RU   | 35        | 8.06%   |
| pt_BR   | 35        | 8.06%   |
| en_GB   | 22        | 5.07%   |
| pl_PL   | 16        | 3.69%   |
| it_IT   | 13        | 3%      |
| fr_FR   | 13        | 3%      |
| es_ES   | 13        | 3%      |
| es_MX   | 8         | 1.84%   |
| Unknown | 8         | 1.84%   |
| es_AR   | 6         | 1.38%   |
| en_AU   | 6         | 1.38%   |
| de_CH   | 6         | 1.38%   |
| en_CA   | 5         | 1.15%   |
| el_GR   | 4         | 0.92%   |
| tr_TR   | 3         | 0.69%   |
| pt_PT   | 3         | 0.69%   |
| nl_NL   | 3         | 0.69%   |
| ja_JP   | 3         | 0.69%   |
| en_NZ   | 3         | 0.69%   |
| en_IN   | 3         | 0.69%   |
| de_AT   | 3         | 0.69%   |
| da_DK   | 3         | 0.69%   |
| ko_KR   | 2         | 0.46%   |
| fr_BE   | 2         | 0.46%   |
| es_BO   | 2         | 0.46%   |
| en_ZA   | 2         | 0.46%   |
| en_SG   | 2         | 0.46%   |
| en_PH   | 2         | 0.46%   |
| en_IE   | 2         | 0.46%   |
| bg_BG   | 2         | 0.46%   |
| zh_CN   | 1         | 0.23%   |
| unm_US  | 1         | 0.23%   |
| uk_UA   | 1         | 0.23%   |
| sk_SK   | 1         | 0.23%   |
| ru_UA   | 1         | 0.23%   |
| nn_NO   | 1         | 0.23%   |
| nl_BE   | 1         | 0.23%   |
| nl_AW   | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 235       | 54.15%  |
| EFI  | 199       | 45.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 404       | 93.74%  |
| Btrfs   | 10        | 2.32%   |
| Overlay | 7         | 1.62%   |
| Tmpfs   | 4         | 0.93%   |
| Unknown | 3         | 0.7%    |
| Xfs     | 2         | 0.46%   |
| Aufs    | 1         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 311       | 71.82%  |
| GPT     | 80        | 18.48%  |
| MBR     | 42        | 9.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 406       | 93.98%  |
| Yes       | 26        | 6.02%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 399       | 92.36%  |
| Yes       | 33        | 7.64%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 100       | 23.2%   |
| Lenovo                         | 68        | 15.78%  |
| Dell                           | 57        | 13.23%  |
| Acer                           | 49        | 11.37%  |
| ASUSTek Computer               | 41        | 9.51%   |
| Toshiba                        | 17        | 3.94%   |
| Sony                           | 10        | 2.32%   |
| Samsung Electronics            | 9         | 2.09%   |
| Apple                          | 9         | 2.09%   |
| Fujitsu Siemens                | 5         | 1.16%   |
| Fujitsu                        | 5         | 1.16%   |
| MSI                            | 4         | 0.93%   |
| Medion                         | 4         | 0.93%   |
| LG Electronics                 | 4         | 0.93%   |
| Google                         | 4         | 0.93%   |
| Unknown                        | 4         | 0.93%   |
| Positivo                       | 3         | 0.7%    |
| Packard Bell                   | 3         | 0.7%    |
| TUXEDO                         | 2         | 0.46%   |
| Star Labs                      | 2         | 0.46%   |
| Matsushita Electric Industrial | 2         | 0.46%   |
| Gateway                        | 2         | 0.46%   |
| Compaq                         | 2         | 0.46%   |
| Wortmann AG                    | 1         | 0.23%   |
| Semp Toshiba                   | 1         | 0.23%   |
| SAELITE                        | 1         | 0.23%   |
| Qbex                           | 1         | 0.23%   |
| Philco                         | 1         | 0.23%   |
| Notebook                       | 1         | 0.23%   |
| Multilaser                     | 1         | 0.23%   |
| Microtech                      | 1         | 0.23%   |
| Maibenben                      | 1         | 0.23%   |
| LincPlus                       | 1         | 0.23%   |
| Kruger&Matz                    | 1         | 0.23%   |
| itel Mobile Limited            | 1         | 0.23%   |
| Itautec                        | 1         | 0.23%   |
| IBM                            | 1         | 0.23%   |
| Howard Computers               | 1         | 0.23%   |
| HIPER                          | 1         | 0.23%   |
| Framework                      | 1         | 0.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 10        | 2.32%   |
| Lenovo IdeaPad 3 15ADA05 81W1               | 4         | 0.93%   |
| HP Pavilion dv6                             | 4         | 0.93%   |
| HP Notebook                                 | 4         | 0.93%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 3         | 0.7%    |
| Dell Latitude E6400                         | 3         | 0.7%    |
| Acer Aspire E1-570G                         | 3         | 0.7%    |
| Acer Aspire 5930                            | 3         | 0.7%    |
| Acer AOD270                                 | 3         | 0.7%    |
| Star Labs StarBook                          | 2         | 0.46%   |
| Lenovo V145-15AST 81MT                      | 2         | 0.46%   |
| Lenovo IdeaPad 3 15ITL6 82H8                | 2         | 0.46%   |
| Lenovo G500 20236                           | 2         | 0.46%   |
| HP Pavilion Notebook                        | 2         | 0.46%   |
| HP Pavilion dv7                             | 2         | 0.46%   |
| HP Laptop 15z-ef2xxx                        | 2         | 0.46%   |
| HP Laptop 15-dw3xxx                         | 2         | 0.46%   |
| HP Laptop 15-bw0xx                          | 2         | 0.46%   |
| HP Laptop 14-df0xxx                         | 2         | 0.46%   |
| HP EliteBook 8540w                          | 2         | 0.46%   |
| HP EliteBook 820 G3                         | 2         | 0.46%   |
| HP Compaq Presario CQ71                     | 2         | 0.46%   |
| HP 255 G7 Notebook PC                       | 2         | 0.46%   |
| HP 250 G8 Notebook PC                       | 2         | 0.46%   |
| HP 14                                       | 2         | 0.46%   |
| Dell Precision M4800                        | 2         | 0.46%   |
| Dell Latitude E5540                         | 2         | 0.46%   |
| Dell Inspiron 5566                          | 2         | 0.46%   |
| Dell Inspiron 5559                          | 2         | 0.46%   |
| Compaq 420                                  | 2         | 0.46%   |
| ASUS X101CH                                 | 2         | 0.46%   |
| Acer Aspire 5735                            | 2         | 0.46%   |
| Acer Aspire 3820                            | 2         | 0.46%   |
| Acer Aspire 3000                            | 2         | 0.46%   |
| Wortmann AG TERRA_MOBILE_1713A              | 1         | 0.23%   |
| TUXEDO N8xxEZ                               | 1         | 0.23%   |
| TUXEDO BC1510 1710                          | 1         | 0.23%   |
| Toshiba Satellite U300                      | 1         | 0.23%   |
| Toshiba Satellite Pro A50-C                 | 1         | 0.23%   |
| Toshiba Satellite P300                      | 1         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Acer Aspire             | 40        | 9.28%   |
| Lenovo ThinkPad         | 30        | 6.96%   |
| Dell Latitude           | 21        | 4.87%   |
| Lenovo IdeaPad          | 19        | 4.41%   |
| HP Laptop               | 19        | 4.41%   |
| HP Pavilion             | 18        | 4.18%   |
| Dell Inspiron           | 18        | 4.18%   |
| Toshiba Satellite       | 14        | 3.25%   |
| HP EliteBook            | 12        | 2.78%   |
| Unknown                 | 10        | 2.32%   |
| HP Compaq               | 8         | 1.86%   |
| HP ProBook              | 7         | 1.62%   |
| Dell Precision          | 7         | 1.62%   |
| ASUS VivoBook           | 6         | 1.39%   |
| HP Notebook             | 4         | 0.93%   |
| Samsung RV411           | 3         | 0.7%    |
| HP Presario             | 3         | 0.7%    |
| HP 255                  | 3         | 0.7%    |
| HP 250                  | 3         | 0.7%    |
| Fujitsu Siemens ESPRIMO | 3         | 0.7%    |
| Fujitsu LIFEBOOK        | 3         | 0.7%    |
| Dell XPS                | 3         | 0.7%    |
| Dell Vostro             | 3         | 0.7%    |
| Acer AOD270             | 3         | 0.7%    |
| Toshiba PORTEGE         | 2         | 0.46%   |
| Star Labs StarBook      | 2         | 0.46%   |
| Packard Bell EasyNote   | 2         | 0.46%   |
| Lenovo Yoga             | 2         | 0.46%   |
| Lenovo V145-15AST       | 2         | 0.46%   |
| Lenovo ThinkBook        | 2         | 0.46%   |
| Lenovo Legion           | 2         | 0.46%   |
| Lenovo G500             | 2         | 0.46%   |
| HP ZBook                | 2         | 0.46%   |
| HP Mini                 | 2         | 0.46%   |
| HP ENVY                 | 2         | 0.46%   |
| HP 14                   | 2         | 0.46%   |
| Dell System             | 2         | 0.46%   |
| Compaq 420              | 2         | 0.46%   |
| ASUS ZenBook            | 2         | 0.46%   |
| ASUS X101CH             | 2         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 35        | 8.12%   |
| 2010    | 34        | 7.89%   |
| 2013    | 33        | 7.66%   |
| 2009    | 32        | 7.42%   |
| 2011    | 31        | 7.19%   |
| 2021    | 28        | 6.5%    |
| 2018    | 26        | 6.03%   |
| 2008    | 26        | 6.03%   |
| 2020    | 25        | 5.8%    |
| 2007    | 24        | 5.57%   |
| 2019    | 22        | 5.1%    |
| 2016    | 21        | 4.87%   |
| 2015    | 20        | 4.64%   |
| 2014    | 20        | 4.64%   |
| 2017    | 18        | 4.18%   |
| 2006    | 13        | 3.02%   |
| 2022    | 10        | 2.32%   |
| 2005    | 7         | 1.62%   |
| 2023    | 2         | 0.46%   |
| 2004    | 1         | 0.23%   |
| 2003    | 1         | 0.23%   |
| 2002    | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 431       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 398       | 91.92%  |
| Enabled  | 35        | 8.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 424       | 98.38%  |
| Yes  | 7         | 1.62%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 120       | 27.78%  |
| 4.01-8.0    | 100       | 23.15%  |
| 16.01-24.0  | 54        | 12.5%   |
| 8.01-16.0   | 47        | 10.88%  |
| 2.01-3.0    | 46        | 10.65%  |
| 1.01-2.0    | 41        | 9.49%   |
| 32.01-64.0  | 11        | 2.55%   |
| 0.51-1.0    | 9         | 2.08%   |
| 64.01-256.0 | 3         | 0.69%   |
| 24.01-32.0  | 1         | 0.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 223       | 48.27%  |
| 2.01-3.0   | 104       | 22.51%  |
| 0.51-1.0   | 68        | 14.72%  |
| 3.01-4.0   | 37        | 8.01%   |
| 4.01-8.0   | 22        | 4.76%   |
| 8.01-16.0  | 4         | 0.87%   |
| 0.01-0.5   | 3         | 0.65%   |
| 32.01-64.0 | 1         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 326       | 74.26%  |
| 2      | 91        | 20.73%  |
| 3      | 13        | 2.96%   |
| 0      | 4         | 0.91%   |
| 4      | 3         | 0.68%   |
| 6      | 1         | 0.23%   |
| 5      | 1         | 0.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 228       | 52.53%  |
| Yes       | 206       | 47.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 372       | 86.31%  |
| No        | 59        | 13.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 425       | 98.61%  |
| No        | 6         | 1.39%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 269       | 62.27%  |
| No        | 163       | 37.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 60        | 13.86%  |
| USA          | 58        | 13.39%  |
| Russia       | 37        | 8.55%   |
| Brazil       | 36        | 8.31%   |
| Italy        | 19        | 4.39%   |
| Poland       | 18        | 4.16%   |
| UK           | 17        | 3.93%   |
| France       | 15        | 3.46%   |
| Spain        | 13        | 3%      |
| Mexico       | 9         | 2.08%   |
| Canada       | 8         | 1.85%   |
| Australia    | 8         | 1.85%   |
| Switzerland  | 7         | 1.62%   |
| Ukraine      | 6         | 1.39%   |
| Netherlands  | 6         | 1.39%   |
| Bulgaria     | 6         | 1.39%   |
| Belarus      | 6         | 1.39%   |
| Argentina    | 6         | 1.39%   |
| Turkey       | 5         | 1.15%   |
| Portugal     | 5         | 1.15%   |
| Indonesia    | 5         | 1.15%   |
| Greece       | 5         | 1.15%   |
| Austria      | 5         | 1.15%   |
| India        | 4         | 0.92%   |
| Belgium      | 4         | 0.92%   |
| Romania      | 3         | 0.69%   |
| Philippines  | 3         | 0.69%   |
| New Zealand  | 3         | 0.69%   |
| Japan        | 3         | 0.69%   |
| Ecuador      | 3         | 0.69%   |
| Denmark      | 3         | 0.69%   |
| Chile        | 3         | 0.69%   |
| Bahrain      | 3         | 0.69%   |
| Venezuela    | 2         | 0.46%   |
| Tunisia      | 2         | 0.46%   |
| Sweden       | 2         | 0.46%   |
| South Korea  | 2         | 0.46%   |
| South Africa | 2         | 0.46%   |
| Ireland      | 2         | 0.46%   |
| Hungary      | 2         | 0.46%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Moscow               | 9         | 2.01%   |
| St Petersburg        | 7         | 1.57%   |
| Sao Paulo            | 6         | 1.34%   |
| Berlin               | 5         | 1.12%   |
| Wroclaw              | 3         | 0.67%   |
| Wohlen               | 3         | 0.67%   |
| Seville              | 3         | 0.67%   |
| Poznan               | 3         | 0.67%   |
| Nuremberg            | 3         | 0.67%   |
| Miami                | 3         | 0.67%   |
| Manama               | 3         | 0.67%   |
| Madrid               | 3         | 0.67%   |
| Lisbon               | 3         | 0.67%   |
| Krakow               | 3         | 0.67%   |
| Guayaquil            | 3         | 0.67%   |
| Freiburg im Breisgau | 3         | 0.67%   |
| Frankfurt am Main    | 3         | 0.67%   |
| Zurich               | 2         | 0.45%   |
| Voronezh             | 2         | 0.45%   |
| Sydney               | 2         | 0.45%   |
| Stuttgart            | 2         | 0.45%   |
| Sofia                | 2         | 0.45%   |
| San Jose             | 2         | 0.45%   |
| Rome                 | 2         | 0.45%   |
| Recife               | 2         | 0.45%   |
| Perth                | 2         | 0.45%   |
| Oruro                | 2         | 0.45%   |
| New York             | 2         | 0.45%   |
| Neasden              | 2         | 0.45%   |
| Munich               | 2         | 0.45%   |
| Minsk                | 2         | 0.45%   |
| Milan                | 2         | 0.45%   |
| Mexico City          | 2         | 0.45%   |
| Mannheim             | 2         | 0.45%   |
| London               | 2         | 0.45%   |
| Lodz                 | 2         | 0.45%   |
| Hyderabad            | 2         | 0.45%   |
| Hrodna               | 2         | 0.45%   |
| Glasgow              | 2         | 0.45%   |
| Foz do Iguaçu       | 2         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 73        | 82     | 13.8%   |
| Samsung Electronics            | 70        | 77     | 13.23%  |
| Seagate                        | 64        | 82     | 12.1%   |
| Unknown                        | 33        | 42     | 6.24%   |
| Toshiba                        | 33        | 35     | 6.24%   |
| Hitachi                        | 27        | 27     | 5.1%    |
| Sandisk                        | 25        | 34     | 4.73%   |
| Kingston                       | 24        | 27     | 4.54%   |
| SK hynix                       | 14        | 16     | 2.65%   |
| Intel                          | 14        | 15     | 2.65%   |
| HGST                           | 13        | 16     | 2.46%   |
| Crucial                        | 13        | 15     | 2.46%   |
| Fujitsu                        | 9         | 9      | 1.7%    |
| China                          | 9         | 10     | 1.7%    |
| Micron Technology              | 8         | 9      | 1.51%   |
| A-DATA Technology              | 7         | 9      | 1.32%   |
| PNY                            | 5         | 6      | 0.95%   |
| Patriot                        | 5         | 6      | 0.95%   |
| GOODRAM                        | 5         | 5      | 0.95%   |
| Apple                          | 5         | 10     | 0.95%   |
| Transcend                      | 4         | 6      | 0.76%   |
| Phison                         | 4         | 5      | 0.76%   |
| KingSpec                       | 4         | 5      | 0.76%   |
| KingDian                       | 3         | 4      | 0.57%   |
| Intenso                        | 3         | 3      | 0.57%   |
| Gigabyte Technology            | 3         | 5      | 0.57%   |
| Team                           | 2         | 2      | 0.38%   |
| Star Drive                     | 2         | 2      | 0.38%   |
| KIOXIA                         | 2         | 5      | 0.38%   |
| JMicron Technology             | 2         | 3      | 0.38%   |
| IBM/Hitachi                    | 2         | 2      | 0.38%   |
| FORESEE                        | 2         | 4      | 0.38%   |
| Corsair                        | 2         | 2      | 0.38%   |
| Unknown                        | 2         | 2      | 0.38%   |
| WINTEC                         | 1         | 1      | 0.19%   |
| USB30                          | 1         | 2      | 0.19%   |
| Union Memory                   | 1         | 1      | 0.19%   |
| UMIS                           | 1         | 1      | 0.19%   |
| SSD PHIS                       | 1         | 1      | 0.19%   |
| Solid State Storage Technology | 1         | 1      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 8         | 1.48%   |
| Seagate ST500LT012-1DG142 500GB      | 7         | 1.29%   |
| Samsung SSD 860 EVO 500GB            | 6         | 1.11%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 5         | 0.92%   |
| Unknown MMC Card  32GB               | 5         | 0.92%   |
| Toshiba MQ01ABD100 1TB               | 5         | 0.92%   |
| SanDisk NVMe SSD Drive 256GB         | 5         | 0.92%   |
| Samsung SSD 860 EVO 1TB              | 5         | 0.92%   |
| Unknown SD/MMC/MS PRO 64GB           | 4         | 0.74%   |
| Unknown MMC Card  7GB                | 4         | 0.74%   |
| Toshiba MQ01ABF050 500GB             | 4         | 0.74%   |
| Seagate ST9250315AS 250GB            | 4         | 0.74%   |
| Samsung SSD 850 EVO 500GB            | 4         | 0.74%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 0.74%   |
| Kingston SA400S37240G 240GB SSD      | 4         | 0.74%   |
| Kingston SA400S37120G 120GB SSD      | 4         | 0.74%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 3         | 0.55%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 3         | 0.55%   |
| Unknown MMC Card  64GB               | 3         | 0.55%   |
| Seagate ST9500325AS 500GB            | 3         | 0.55%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 0.55%   |
| Samsung SSD 860 EVO 250GB            | 3         | 0.55%   |
| HGST HTS545050A7E680 500GB           | 3         | 0.55%   |
| GOODRAM SSDPR-CL100-120-G3 120GB     | 3         | 0.55%   |
| Gigabyte GP-GSTFS31120GNTD 120GB SSD | 3         | 0.55%   |
| A-DATA ED600 1TB SSD                 | 3         | 0.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.37%   |
| WDC WDBNCE5000PNC 500GB SSD          | 2         | 0.37%   |
| WDC WD7500BPVT-75HXZT3 752GB         | 2         | 0.37%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 0.37%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 2         | 0.37%   |
| WDC WD2500BEVT-22ZCT0 250GB          | 2         | 0.37%   |
| WDC WD1600BEVT-60ZCT1 160GB          | 2         | 0.37%   |
| WDC WD1200BEVS-22UST0 120GB          | 2         | 0.37%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB | 2         | 0.37%   |
| WDC PC SN530 NVMe 256GB              | 2         | 0.37%   |
| Unknown SC128  128GB                 | 2         | 0.37%   |
| Unknown MMC Card  4GB                | 2         | 0.37%   |
| Unknown MMC Card  16GB               | 2         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 63        | 80     | 29.86%  |
| WDC                 | 57        | 65     | 27.01%  |
| Toshiba             | 27        | 29     | 12.8%   |
| Hitachi             | 27        | 27     | 12.8%   |
| HGST                | 13        | 16     | 6.16%   |
| Fujitsu             | 9         | 9      | 4.27%   |
| Samsung Electronics | 5         | 5      | 2.37%   |
| Unknown             | 4         | 4      | 1.9%    |
| IBM/Hitachi         | 2         | 2      | 0.95%   |
| SABRENT             | 1         | 1      | 0.47%   |
| Intenso             | 1         | 1      | 0.47%   |
| DAS                 | 1         | 4      | 0.47%   |
| ASMT                | 1         | 1      | 0.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 47        | 53     | 23.62%  |
| Kingston            | 22        | 25     | 11.06%  |
| Crucial             | 13        | 15     | 6.53%   |
| SanDisk             | 12        | 18     | 6.03%   |
| Intel               | 8         | 8      | 4.02%   |
| WDC                 | 7         | 7      | 3.52%   |
| China               | 7         | 8      | 3.52%   |
| A-DATA Technology   | 7         | 9      | 3.52%   |
| Toshiba             | 5         | 5      | 2.51%   |
| PNY                 | 5         | 6      | 2.51%   |
| Patriot             | 5         | 6      | 2.51%   |
| GOODRAM             | 5         | 5      | 2.51%   |
| Transcend           | 4         | 6      | 2.01%   |
| Micron Technology   | 4         | 5      | 2.01%   |
| KingSpec            | 4         | 5      | 2.01%   |
| Apple               | 4         | 4      | 2.01%   |
| KingDian            | 3         | 4      | 1.51%   |
| Gigabyte Technology | 3         | 5      | 1.51%   |
| Team                | 2         | 2      | 1.01%   |
| SK hynix            | 2         | 3      | 1.01%   |
| FORESEE             | 2         | 4      | 1.01%   |
| Corsair             | 2         | 2      | 1.01%   |
| Unknown             | 2         | 2      | 1.01%   |
| WINTEC              | 1         | 1      | 0.5%    |
| USB30               | 1         | 2      | 0.5%    |
| Unknown             | 1         | 1      | 0.5%    |
| SSD PHIS            | 1         | 1      | 0.5%    |
| Plextor             | 1         | 1      | 0.5%    |
| ORICO               | 1         | 1      | 0.5%    |
| Netac               | 1         | 1      | 0.5%    |
| Mushkin             | 1         | 1      | 0.5%    |
| Microtech           | 1         | 2      | 0.5%    |
| LITEON              | 1         | 1      | 0.5%    |
| Lexar               | 1         | 1      | 0.5%    |
| Intenso             | 1         | 1      | 0.5%    |
| Initio              | 1         | 1      | 0.5%    |
| HXY                 | 1         | 1      | 0.5%    |
| Hikvision           | 1         | 1      | 0.5%    |
| Hewlett-Packard     | 1         | 2      | 0.5%    |
| GALAX               | 1         | 1      | 0.5%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 203       | 244    | 40.85%  |
| SSD     | 179       | 237    | 36.02%  |
| NVMe    | 73        | 94     | 14.69%  |
| MMC     | 28        | 36     | 5.63%   |
| Unknown | 14        | 17     | 2.82%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 354       | 459    | 73.6%   |
| NVMe | 73        | 94     | 15.18%  |
| MMC  | 28        | 36     | 5.82%   |
| SAS  | 26        | 39     | 5.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 293       | 370    | 78.13%  |
| 0.51-1.0   | 70        | 97     | 18.67%  |
| 1.01-2.0   | 7         | 9      | 1.87%   |
| 4.01-10.0  | 3         | 3      | 0.8%    |
| 2.01-3.0   | 2         | 2      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 173       | 39.5%   |
| 251-500        | 112       | 25.57%  |
| 501-1000       | 50        | 11.42%  |
| 51-100         | 39        | 8.9%    |
| 21-50          | 20        | 4.57%   |
| 1001-2000      | 19        | 4.34%   |
| 1-20           | 9         | 2.05%   |
| More than 3000 | 8         | 1.83%   |
| 2001-3000      | 7         | 1.6%    |
| Unknown        | 1         | 0.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 215       | 46.84%  |
| 21-50          | 103       | 22.44%  |
| 101-250        | 53        | 11.55%  |
| 51-100         | 48        | 10.46%  |
| 501-1000       | 16        | 3.49%   |
| 251-500        | 14        | 3.05%   |
| 2001-3000      | 4         | 0.87%   |
| More than 3000 | 3         | 0.65%   |
| 1001-2000      | 2         | 0.44%   |
| Unknown        | 1         | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WINTEC 240GB SATA3 SF2281 SSD         | 1         | 1      | 3.85%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 3.85%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 3.85%   |
| WDC WD3200BEVT-26A23T0 320GB          | 1         | 1      | 3.85%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 3.85%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 3.85%   |
| Seagate STM9120817AS 120GB            | 1         | 1      | 3.85%   |
| Seagate ST9640423AS 640GB             | 1         | 1      | 3.85%   |
| Seagate ST9250315AS 250GB             | 1         | 1      | 3.85%   |
| Seagate ST9120821AS 120GB             | 1         | 1      | 3.85%   |
| Seagate ST500LT032-1E9142 500GB       | 1         | 1      | 3.85%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 2      | 3.85%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 3.85%   |
| Samsung Electronics SSD 850 EVO 500GB | 1         | 1      | 3.85%   |
| Samsung Electronics MP0402H 40GB      | 1         | 1      | 3.85%   |
| Samsung Electronics HM160HC 160GB     | 1         | 1      | 3.85%   |
| Phison ES 512GB                       | 1         | 1      | 3.85%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 3.85%   |
| Intel SSDSCKKF256G8 SATA 256GB        | 1         | 1      | 3.85%   |
| Intel SSDSC2CT240A3 240GB             | 1         | 1      | 3.85%   |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 3.85%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 3.85%   |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 3.85%   |
| Fujitsu MHZ2080BJ FFS G2 80GB         | 1         | 1      | 3.85%   |
| Crucial M4-CT256M4SSD2 256GB          | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 20%     |
| Samsung Electronics | 5         | 6      | 20%     |
| WDC                 | 2         | 3      | 8%      |
| Intel               | 2         | 2      | 8%      |
| Hitachi             | 2         | 2      | 8%      |
| WINTEC              | 1         | 1      | 4%      |
| Toshiba             | 1         | 1      | 4%      |
| SK hynix            | 1         | 1      | 4%      |
| SanDisk             | 1         | 1      | 4%      |
| Phison              | 1         | 1      | 4%      |
| Kingston            | 1         | 1      | 4%      |
| HGST                | 1         | 1      | 4%      |
| Fujitsu             | 1         | 1      | 4%      |
| Crucial             | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 38.46%  |
| WDC                 | 2         | 3      | 15.38%  |
| Samsung Electronics | 2         | 2      | 15.38%  |
| Hitachi             | 2         | 2      | 15.38%  |
| HGST                | 1         | 1      | 7.69%   |
| Fujitsu             | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 14     | 52%     |
| SSD  | 9         | 9      | 36%     |
| NVMe | 3         | 4      | 12%     |

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
| Detected | 327       | 476    | 72.51%  |
| Works    | 99        | 125    | 21.95%  |
| Malfunc  | 25        | 27     | 5.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 323       | 68.87%  |
| AMD                              | 57        | 12.15%  |
| SanDisk                          | 19        | 4.05%   |
| Samsung Electronics              | 19        | 4.05%   |
| SK hynix                         | 12        | 2.56%   |
| Nvidia                           | 7         | 1.49%   |
| Silicon Integrated Systems [SiS] | 6         | 1.28%   |
| Phison Electronics               | 6         | 1.28%   |
| Micron Technology                | 4         | 0.85%   |
| KIOXIA                           | 3         | 0.64%   |
| Union Memory (Shenzhen)          | 2         | 0.43%   |
| Toshiba America Info Systems     | 2         | 0.43%   |
| Marvell Technology Group         | 2         | 0.43%   |
| Kingston Technology Company      | 2         | 0.43%   |
| VIA Technologies                 | 1         | 0.21%   |
| Solid State Storage Technology   | 1         | 0.21%   |
| Micron/Crucial Technology        | 1         | 0.21%   |
| Apple                            | 1         | 0.21%   |
| ADATA Technology                 | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 39        | 7.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 31        | 5.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 30        | 5.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 25        | 4.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 24        | 4.49%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 19        | 3.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 17        | 3.18%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 16        | 2.99%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 15        | 2.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 14        | 2.62%   |
| Intel Volume Management Device NVMe RAID Controller                              | 13        | 2.43%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 12        | 2.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 12        | 2.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 12        | 2.24%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 11        | 2.06%   |
| Intel Tiger Lake-LP SATA Controller                                              | 10        | 1.87%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 10        | 1.87%   |
| Samsung NVMe SSD Controller 980                                                  | 9         | 1.68%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9         | 1.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 8         | 1.5%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 1.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 8         | 1.5%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 6         | 1.12%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 6         | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 1.12%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 5         | 0.93%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 0.93%   |
| SanDisk NVMe Controller                                                          | 5         | 0.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 0.93%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 4         | 0.75%   |
| SanDisk Non-Volatile memory controller                                           | 4         | 0.75%   |
| Phison E12 NVMe Controller                                                       | 4         | 0.75%   |
| Micron NVMe Storage Controller                                                   | 4         | 0.75%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                       | 4         | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 0.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 0.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 0.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 4         | 0.75%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 4         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 313       | 61.25%  |
| IDE  | 84        | 16.44%  |
| NVMe | 75        | 14.68%  |
| RAID | 39        | 7.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 356       | 82.6%   |
| AMD    | 75        | 17.4%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N2600 @ 1.60GHz              | 10        | 2.32%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 8         | 1.86%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 8         | 1.86%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 7         | 1.62%   |
| Intel Atom CPU N270 @ 1.60GHz               | 7         | 1.62%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 5         | 1.16%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 5         | 1.16%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 5         | 1.16%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 5         | 1.16%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 4         | 0.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 4         | 0.93%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 0.93%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 4         | 0.93%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 4         | 0.93%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 4         | 0.93%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 4         | 0.93%   |
| Intel Celeron CPU N2830 @ 2.16GHz           | 4         | 0.93%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 4         | 0.93%   |
| Intel Pentium M processor 1.73GHz           | 3         | 0.7%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 3         | 0.7%    |
| Intel Pentium Dual CPU T3400 @ 2.16GHz      | 3         | 0.7%    |
| Intel Pentium CPU P6100 @ 2.00GHz           | 3         | 0.7%    |
| Intel Pentium CPU N3710 @ 1.60GHz           | 3         | 0.7%    |
| Intel Pentium CPU N3700 @ 1.60GHz           | 3         | 0.7%    |
| Intel Genuine CPU T2300 @ 1.66GHz           | 3         | 0.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz           | 3         | 0.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 0.7%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 3         | 0.7%    |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 3         | 0.7%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 3         | 0.7%    |
| Intel Core i5-4200U CPU @ 1.60GHz           | 3         | 0.7%    |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 0.7%    |
| Intel Core i5-2450M CPU @ 2.50GHz           | 3         | 0.7%    |
| Intel Core i3-6006U CPU @ 2.00GHz           | 3         | 0.7%    |
| Intel Core i3-3217U CPU @ 1.80GHz           | 3         | 0.7%    |
| Intel Core i3-3110M CPU @ 2.40GHz           | 3         | 0.7%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 3         | 0.7%    |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 3         | 0.7%    |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 3         | 0.7%    |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 3         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 77        | 17.87%  |
| Intel Core i7                  | 56        | 12.99%  |
| Intel Core i3                  | 46        | 10.67%  |
| Intel Core 2 Duo               | 33        | 7.66%   |
| Intel Atom                     | 30        | 6.96%   |
| Other                          | 27        | 6.26%   |
| Intel Celeron                  | 27        | 6.26%   |
| Intel Pentium                  | 17        | 3.94%   |
| AMD Ryzen 5                    | 15        | 3.48%   |
| Intel Genuine                  | 9         | 2.09%   |
| AMD Ryzen 7                    | 9         | 2.09%   |
| Intel Core 2                   | 8         | 1.86%   |
| Intel Pentium M                | 7         | 1.62%   |
| Intel Pentium Dual             | 7         | 1.62%   |
| Intel Pentium Dual-Core        | 6         | 1.39%   |
| AMD A4                         | 6         | 1.39%   |
| AMD E2                         | 4         | 0.93%   |
| Intel Core Duo                 | 3         | 0.7%    |
| AMD Turion 64 X2 Mobile        | 3         | 0.7%    |
| AMD Ryzen 3                    | 3         | 0.7%    |
| AMD E                          | 3         | 0.7%    |
| AMD Athlon II                  | 3         | 0.7%    |
| AMD A10                        | 3         | 0.7%    |
| Intel Pentium Silver           | 2         | 0.46%   |
| Intel Pentium 4                | 2         | 0.46%   |
| Intel Celeron M                | 2         | 0.46%   |
| AMD Sempron                    | 2         | 0.46%   |
| AMD Mobile Sempron             | 2         | 0.46%   |
| AMD E1                         | 2         | 0.46%   |
| AMD Athlon                     | 2         | 0.46%   |
| AMD A8                         | 2         | 0.46%   |
| AMD A6                         | 2         | 0.46%   |
| Intel Pentium Gold             | 1         | 0.23%   |
| Intel Mobile Pentium 4         | 1         | 0.23%   |
| Intel Core i9                  | 1         | 0.23%   |
| Intel Core 2 Extreme           | 1         | 0.23%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.23%   |
| AMD Turion 64 Mobile           | 1         | 0.23%   |
| AMD Ryzen 9                    | 1         | 0.23%   |
| AMD Phenom II                  | 1         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 274       | 63.43%  |
| 4      | 89        | 20.6%   |
| 1      | 42        | 9.72%   |
| 6      | 14        | 3.24%   |
| 8      | 10        | 2.31%   |
| 12     | 2         | 0.46%   |
| 10     | 1         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 431       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 263       | 61.02%  |
| 1      | 168       | 38.98%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 387       | 89.79%  |
| 32-bit         | 44        | 10.21%  |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 32        | 7.31%   |
| Unknown    | 28        | 6.39%   |
| 0x206a7    | 27        | 6.16%   |
| 0x1067a    | 22        | 5.02%   |
| 0x40651    | 19        | 4.34%   |
| 0x406e3    | 18        | 4.11%   |
| 0x806c1    | 16        | 3.65%   |
| 0x6fd      | 16        | 3.65%   |
| 0x106c2    | 13        | 2.97%   |
| 0x30661    | 12        | 2.74%   |
| 0x20655    | 12        | 2.74%   |
| 0x806ea    | 11        | 2.51%   |
| 0x06006705 | 11        | 2.51%   |
| 0x306c3    | 10        | 2.28%   |
| 0x806ec    | 9         | 2.05%   |
| 0x6f6      | 9         | 2.05%   |
| 0x806e9    | 8         | 1.83%   |
| 0x30678    | 8         | 1.83%   |
| 0x20652    | 8         | 1.83%   |
| 0x08608103 | 8         | 1.83%   |
| 0x6ec      | 7         | 1.6%    |
| 0x406c4    | 7         | 1.6%    |
| 0x10676    | 7         | 1.6%    |
| 0x306d4    | 6         | 1.37%   |
| 0x08108109 | 6         | 1.37%   |
| 0x806eb    | 5         | 1.14%   |
| 0x706a1    | 5         | 1.14%   |
| 0x6e8      | 5         | 1.14%   |
| 0x6d8      | 5         | 1.14%   |
| 0x506e3    | 5         | 1.14%   |
| 0x106e5    | 5         | 1.14%   |
| 0x906ea    | 4         | 0.91%   |
| 0x706e5    | 4         | 0.91%   |
| 0x406c3    | 4         | 0.91%   |
| 0x08108102 | 4         | 0.91%   |
| 0x010000c8 | 4         | 0.91%   |
| 0x106ca    | 3         | 0.68%   |
| 0x0a50000c | 3         | 0.68%   |
| 0x06001119 | 3         | 0.68%   |
| 0xf29      | 2         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 42        | 9.72%   |
| Penryn           | 32        | 7.41%   |
| IvyBridge        | 32        | 7.41%   |
| Haswell          | 30        | 6.94%   |
| Core             | 29        | 6.71%   |
| Bonnell          | 29        | 6.71%   |
| SandyBridge      | 28        | 6.48%   |
| Skylake          | 23        | 5.32%   |
| Westmere         | 21        | 4.86%   |
| Silvermont       | 21        | 4.86%   |
| P6               | 19        | 4.4%    |
| TigerLake        | 17        | 3.94%   |
| Excavator        | 14        | 3.24%   |
| Unknown          | 12        | 2.78%   |
| Zen+             | 10        | 2.31%   |
| K8 Hammer        | 9         | 2.08%   |
| Broadwell        | 7         | 1.62%   |
| Zen 3            | 6         | 1.39%   |
| Goldmont plus    | 6         | 1.39%   |
| Nehalem          | 5         | 1.16%   |
| K10              | 5         | 1.16%   |
| IceLake          | 5         | 1.16%   |
| Zen              | 4         | 0.93%   |
| Puma             | 4         | 0.93%   |
| Bobcat           | 4         | 0.93%   |
| Piledriver       | 3         | 0.69%   |
| NetBurst         | 3         | 0.69%   |
| Zen 2            | 2         | 0.46%   |
| K8 & K10 hybrid  | 2         | 0.46%   |
| Jaguar           | 2         | 0.46%   |
| CometLake        | 2         | 0.46%   |
| Tremont          | 1         | 0.23%   |
| K10 Llano        | 1         | 0.23%   |
| Goldmont         | 1         | 0.23%   |
| Alderlake Hybrid | 1         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 293       | 58.02%  |
| AMD                              | 109       | 21.58%  |
| Nvidia                           | 97        | 19.21%  |
| Silicon Integrated Systems [SiS] | 5         | 0.99%   |
| VIA Technologies                 | 1         | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 30        | 5.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 23        | 4.28%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 19        | 3.53%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 3.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 17        | 3.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 17        | 3.16%   |
| Intel Core Processor Integrated Graphics Controller                                      | 17        | 3.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 2.23%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 12        | 2.23%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 12        | 2.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 2.23%   |
| Intel UHD Graphics 620                                                                   | 11        | 2.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 2.04%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 10        | 1.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 10        | 1.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 1.86%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.67%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 9         | 1.67%   |
| AMD Lucienne                                                                             | 8         | 1.49%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 1.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 1.3%    |
| Intel HD Graphics 620                                                                    | 6         | 1.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.12%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.12%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.93%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 5         | 0.93%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 5         | 0.93%   |
| Intel HD Graphics 5500                                                                   | 5         | 0.93%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 0.93%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 5         | 0.93%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 5         | 0.93%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.74%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 4         | 0.74%   |
| Intel US15W/US15X SCH [Poulsbo] Graphics Controller                                      | 4         | 0.74%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.74%   |
| Intel HD Graphics 530                                                                    | 4         | 0.74%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 0.74%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.74%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 3         | 0.56%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 222       | 51.51%  |
| 1 x AMD        | 84        | 19.49%  |
| Intel + Nvidia | 55        | 12.76%  |
| 1 x Nvidia     | 39        | 9.05%   |
| Intel + AMD    | 16        | 3.71%   |
| 2 x AMD        | 6         | 1.39%   |
| 1 x SiS        | 5         | 1.16%   |
| AMD + Nvidia   | 3         | 0.7%    |
| 1 x VIA        | 1         | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 380       | 87.56%  |
| Unknown     | 30        | 6.91%   |
| Proprietary | 24        | 5.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 279       | 64.29%  |
| 0.01-0.5   | 75        | 17.28%  |
| 1.01-2.0   | 42        | 9.68%   |
| 0.51-1.0   | 24        | 5.53%   |
| 3.01-4.0   | 9         | 2.07%   |
| 5.01-6.0   | 3         | 0.69%   |
| 2.01-3.0   | 2         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 81        | 19.15%  |
| LG Display              | 67        | 15.84%  |
| Chimei Innolux          | 51        | 12.06%  |
| BOE                     | 50        | 11.82%  |
| Samsung Electronics     | 46        | 10.87%  |
| Chi Mei Optoelectronics | 17        | 4.02%   |
| LG Philips              | 13        | 3.07%   |
| Goldstar                | 10        | 2.36%   |
| Apple                   | 10        | 2.36%   |
| HannStar                | 9         | 2.13%   |
| Lenovo                  | 8         | 1.89%   |
| InfoVision              | 7         | 1.65%   |
| Sharp                   | 5         | 1.18%   |
| Dell                    | 5         | 1.18%   |
| BenQ                    | 4         | 0.95%   |
| Sony                    | 3         | 0.71%   |
| Quanta Display          | 3         | 0.71%   |
| PANDA                   | 3         | 0.71%   |
| CPT                     | 3         | 0.71%   |
| Acer                    | 3         | 0.71%   |
| SLD                     | 2         | 0.47%   |
| Philips                 | 2         | 0.47%   |
| Hewlett-Packard         | 2         | 0.47%   |
| AOC                     | 2         | 0.47%   |
| ViewSonic               | 1         | 0.24%   |
| Vestel Elektronik       | 1         | 0.24%   |
| Unknown                 | 1         | 0.24%   |
| TR_                     | 1         | 0.24%   |
| Seiko/Epson             | 1         | 0.24%   |
| Sceptre Tech            | 1         | 0.24%   |
| Planar                  | 1         | 0.24%   |
| Panasonic               | 1         | 0.24%   |
| Packard Bell            | 1         | 0.24%   |
| MLT                     | 1         | 0.24%   |
| Insignia                | 1         | 0.24%   |
| InnoLux Display         | 1         | 0.24%   |
| IBM                     | 1         | 0.24%   |
| HKC                     | 1         | 0.24%   |
| DENON                   | 1         | 0.24%   |
| BLS                     | 1         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 7         | 1.64%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 4         | 0.94%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 4         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 4         | 0.94%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.7%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.7%    |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 3         | 0.7%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 3         | 0.7%    |
| InfoVision LCD Monitor IVO03F4 1920x1080 344x193mm 15.5-inch             | 3         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch          | 3         | 0.7%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 3         | 0.7%    |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 3         | 0.7%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch           | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 0.7%    |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                     | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch     | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch     | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch    | 2         | 0.47%   |
| Quanta Display LCD Monitor QDS0025 1024x768 304x228mm 15.0-inch          | 2         | 0.47%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.47%   |
| LG Philips LCD Monitor LPL8D00 1280x800 304x190mm 14.1-inch              | 2         | 0.47%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch              | 2         | 0.47%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch              | 2         | 0.47%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch            | 2         | 0.47%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 2         | 0.47%   |
| LG Display LCD Monitor LGD027A 1600x900 382x215mm 17.3-inch              | 2         | 0.47%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 2         | 0.47%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                 | 2         | 0.47%   |
| HannStar HSD101PFW4A HSD03ED 1024x600 223x125mm 10.1-inch                | 2         | 0.47%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 2         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 157       | 37.83%  |
| 1920x1080 (FHD)    | 135       | 32.53%  |
| 1280x800 (WXGA)    | 34        | 8.19%   |
| 1600x900 (HD+)     | 23        | 5.54%   |
| 1024x600           | 17        | 4.1%    |
| 3840x2160 (4K)     | 8         | 1.93%   |
| 1920x1200 (WUXGA)  | 8         | 1.93%   |
| 1440x900 (WXGA+)   | 8         | 1.93%   |
| 1280x1024 (SXGA)   | 4         | 0.96%   |
| 1680x1050 (WSXGA+) | 3         | 0.72%   |
| 2880x1800          | 2         | 0.48%   |
| 2560x1440 (QHD)    | 2         | 0.48%   |
| 2560x1080          | 2         | 0.48%   |
| 1280x768           | 2         | 0.48%   |
| 1024x768 (XGA)     | 2         | 0.48%   |
| 3840x1080          | 1         | 0.24%   |
| 2560x1600          | 1         | 0.24%   |
| 2256x1504          | 1         | 0.24%   |
| 1920x540           | 1         | 0.24%   |
| 1400x1050          | 1         | 0.24%   |
| 1360x768           | 1         | 0.24%   |
| 1280x720 (HD)      | 1         | 0.24%   |
| Unknown            | 1         | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 205       | 48.46%  |
| 13      | 50        | 11.82%  |
| 14      | 48        | 11.35%  |
| 17      | 27        | 6.38%   |
| 10      | 16        | 3.78%   |
| 12      | 12        | 2.84%   |
| 24      | 10        | 2.36%   |
| 11      | 9         | 2.13%   |
| 23      | 7         | 1.65%   |
| Unknown | 7         | 1.65%   |
| 18      | 6         | 1.42%   |
| 27      | 4         | 0.95%   |
| 21      | 4         | 0.95%   |
| 72      | 3         | 0.71%   |
| 34      | 3         | 0.71%   |
| 19      | 3         | 0.71%   |
| 31      | 2         | 0.47%   |
| 8       | 2         | 0.47%   |
| 84      | 1         | 0.24%   |
| 48      | 1         | 0.24%   |
| 40      | 1         | 0.24%   |
| 20      | 1         | 0.24%   |
| 16      | 1         | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 278       | 66.35%  |
| 201-300     | 57        | 13.6%   |
| 351-400     | 33        | 7.88%   |
| 501-600     | 19        | 4.53%   |
| 401-500     | 12        | 2.86%   |
| Unknown     | 7         | 1.67%   |
| 1501-2000   | 4         | 0.95%   |
| 701-800     | 3         | 0.72%   |
| 601-700     | 2         | 0.48%   |
| 101-200     | 2         | 0.48%   |
| 801-900     | 1         | 0.24%   |
| 1001-1500   | 1         | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 323       | 81.16%  |
| 16/10   | 58        | 14.57%  |
| 5/4     | 5         | 1.26%   |
| Unknown | 4         | 1.01%   |
| 4/3     | 3         | 0.75%   |
| 3/2     | 2         | 0.5%    |
| 21/9    | 2         | 0.5%    |
| 32/9    | 1         | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 204       | 48.11%  |
| 81-90          | 81        | 19.1%   |
| 121-130        | 19        | 4.48%   |
| 71-80          | 16        | 3.77%   |
| 41-50          | 16        | 3.77%   |
| 201-250        | 16        | 3.77%   |
| 61-70          | 12        | 2.83%   |
| 51-60          | 9         | 2.12%   |
| 141-150        | 8         | 1.89%   |
| Unknown        | 7         | 1.65%   |
| 131-140        | 6         | 1.42%   |
| More than 1000 | 5         | 1.18%   |
| 151-200        | 5         | 1.18%   |
| 351-500        | 4         | 0.94%   |
| 301-350        | 4         | 0.94%   |
| 251-300        | 4         | 0.94%   |
| 91-100         | 4         | 0.94%   |
| 1-40           | 2         | 0.47%   |
| 501-1000       | 2         | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 178       | 42.58%  |
| 121-160       | 134       | 32.06%  |
| 51-100        | 75        | 17.94%  |
| 161-240       | 15        | 3.59%   |
| Unknown       | 7         | 1.67%   |
| 1-50          | 5         | 1.2%    |
| More than 240 | 4         | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 372       | 84.93%  |
| 2     | 40        | 9.13%   |
| 0     | 25        | 5.71%   |
| 3     | 1         | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 230       | 32.35%  |
| Intel                                 | 179       | 25.18%  |
| Qualcomm Atheros                      | 127       | 17.86%  |
| Broadcom                              | 66        | 9.28%   |
| Broadcom Limited                      | 16        | 2.25%   |
| Marvell Technology Group              | 14        | 1.97%   |
| Ralink                                | 7         | 0.98%   |
| Samsung Electronics                   | 6         | 0.84%   |
| Nvidia                                | 6         | 0.84%   |
| TP-Link                               | 5         | 0.7%    |
| Silicon Integrated Systems [SiS]      | 5         | 0.7%    |
| MediaTek                              | 5         | 0.7%    |
| Xiaomi                                | 3         | 0.42%   |
| Ralink Technology                     | 3         | 0.42%   |
| JMicron Technology                    | 3         | 0.42%   |
| Ericsson Business Mobile Networks     | 3         | 0.42%   |
| Dell                                  | 3         | 0.42%   |
| Sierra Wireless                       | 2         | 0.28%   |
| Lenovo                                | 2         | 0.28%   |
| Huawei Technologies                   | 2         | 0.28%   |
| Hewlett-Packard                       | 2         | 0.28%   |
| Attansic Technology                   | 2         | 0.28%   |
| AMD                                   | 2         | 0.28%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.14%   |
| VIA Technologies                      | 1         | 0.14%   |
| ST-Ericsson                           | 1         | 0.14%   |
| Spreadtrum Communications             | 1         | 0.14%   |
| Qualcomm Atheros Communications       | 1         | 0.14%   |
| OnePlus Technology (Shenzhen)         | 1         | 0.14%   |
| NetGear                               | 1         | 0.14%   |
| Manta                                 | 1         | 0.14%   |
| Linksys                               | 1         | 0.14%   |
| Intersil                              | 1         | 0.14%   |
| Google                                | 1         | 0.14%   |
| Gemtek                                | 1         | 0.14%   |
| Edimax Technology                     | 1         | 0.14%   |
| DisplayLink                           | 1         | 0.14%   |
| Davicom Semiconductor                 | 1         | 0.14%   |
| Cisco Aironet Wireless Communications | 1         | 0.14%   |
| ASUSTek Computer                      | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 118       | 13.66%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 63        | 7.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 25        | 2.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 2.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 19        | 2.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 17        | 1.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 16        | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 1.62%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 1.62%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 14        | 1.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 12        | 1.39%   |
| Intel Wireless 8265 / 8275                                              | 11        | 1.27%   |
| Intel Wireless 7260                                                     | 11        | 1.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 10        | 1.16%   |
| Intel Wireless 8260                                                     | 10        | 1.16%   |
| Intel WiFi Link 5100                                                    | 10        | 1.16%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 0.93%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 0.93%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.81%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 7         | 0.81%   |
| Intel Wireless 3165                                                     | 7         | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 0.81%   |
| Intel 82577LM Gigabit Network Connection                                | 7         | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 6         | 0.69%   |
| Intel Wireless 7265                                                     | 6         | 0.69%   |
| Intel Ethernet Connection I219-V                                        | 6         | 0.69%   |
| Intel Ethernet Connection I217-LM                                       | 6         | 0.69%   |
| Intel Centrino Ultimate-N 6300                                          | 6         | 0.69%   |
| Intel 82567LM Gigabit Network Connection                                | 6         | 0.69%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                       | 6         | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 5         | 0.58%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 5         | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 0.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 0.58%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.58%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                 | 5         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 162       | 36.32%  |
| Qualcomm Atheros                      | 108       | 24.22%  |
| Realtek Semiconductor                 | 89        | 19.96%  |
| Broadcom                              | 49        | 10.99%  |
| Broadcom Limited                      | 9         | 2.02%   |
| Ralink                                | 7         | 1.57%   |
| TP-Link                               | 5         | 1.12%   |
| Ralink Technology                     | 3         | 0.67%   |
| MediaTek                              | 3         | 0.67%   |
| Sierra Wireless                       | 2         | 0.45%   |
| Xiaomi                                | 1         | 0.22%   |
| Qualcomm Atheros Communications       | 1         | 0.22%   |
| NetGear                               | 1         | 0.22%   |
| Linksys                               | 1         | 0.22%   |
| Edimax Technology                     | 1         | 0.22%   |
| Dell                                  | 1         | 0.22%   |
| Cisco Aironet Wireless Communications | 1         | 0.22%   |
| ASUSTek Computer                      | 1         | 0.22%   |
| Askey Computer                        | 1         | 0.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 25        | 5.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 22        | 4.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 19        | 4.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 17        | 3.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 16        | 3.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 3.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 14        | 3.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 14        | 3.08%   |
| Intel Wireless 8265 / 8275                                              | 11        | 2.42%   |
| Intel Wireless 7260                                                     | 11        | 2.42%   |
| Intel Wireless 8260                                                     | 10        | 2.2%    |
| Intel WiFi Link 5100                                                    | 10        | 2.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 1.76%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 1.76%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 1.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 1.54%   |
| Intel Wireless 3165                                                     | 7         | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.32%   |
| Intel Wireless 7265                                                     | 6         | 1.32%   |
| Intel Centrino Ultimate-N 6300                                          | 6         | 1.32%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 5         | 1.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1.1%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 1.1%    |
| Intel Wireless 3160                                                     | 5         | 1.1%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 5         | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 1.1%    |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 1.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.88%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 4         | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 0.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 0.88%   |
| Intel Ultimate N WiFi Link 5300                                         | 4         | 0.88%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 0.88%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 0.88%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 4         | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 198       | 50.77%  |
| Intel                            | 71        | 18.21%  |
| Qualcomm Atheros                 | 38        | 9.74%   |
| Broadcom                         | 23        | 5.9%    |
| Marvell Technology Group         | 14        | 3.59%   |
| Broadcom Limited                 | 7         | 1.79%   |
| Samsung Electronics              | 6         | 1.54%   |
| Nvidia                           | 6         | 1.54%   |
| Silicon Integrated Systems [SiS] | 5         | 1.28%   |
| JMicron Technology               | 3         | 0.77%   |
| Xiaomi                           | 2         | 0.51%   |
| MediaTek                         | 2         | 0.51%   |
| Lenovo                           | 2         | 0.51%   |
| Hewlett-Packard                  | 2         | 0.51%   |
| Attansic Technology              | 2         | 0.51%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.26%   |
| VIA Technologies                 | 1         | 0.26%   |
| Spreadtrum Communications        | 1         | 0.26%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.26%   |
| Huawei Technologies              | 1         | 0.26%   |
| Google                           | 1         | 0.26%   |
| Gemtek                           | 1         | 0.26%   |
| DisplayLink                      | 1         | 0.26%   |
| Davicom Semiconductor            | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 118       | 30.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 63        | 16.15%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 12        | 3.08%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 10        | 2.56%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 7         | 1.79%   |
| Intel 82577LM Gigabit Network Connection                                       | 7         | 1.79%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 6         | 1.54%   |
| Intel Ethernet Connection I219-V                                               | 6         | 1.54%   |
| Intel Ethernet Connection I217-LM                                              | 6         | 1.54%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 1.54%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 6         | 1.54%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 5         | 1.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 5         | 1.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 1.28%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 5         | 1.28%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 1.03%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 4         | 1.03%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 3         | 0.77%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 0.77%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 3         | 0.77%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 3         | 0.77%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 0.77%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 0.77%   |
| Intel 82566MM Gigabit Network Connection                                       | 3         | 0.77%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 3         | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 0.77%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 3         | 0.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.51%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 2         | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.51%   |
| Nvidia MCP67 Ethernet                                                          | 2         | 0.51%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.51%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 2         | 0.51%   |
| Lenovo ThinkPad Lan                                                            | 2         | 0.51%   |
| Intel PRO/100 VE Network Connection                                            | 2         | 0.51%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.51%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.51%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 425       | 52.15%  |
| Ethernet | 371       | 45.52%  |
| Modem    | 16        | 1.96%   |
| Unknown  | 3         | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 327       | 74.15%  |
| Ethernet | 114       | 25.85%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 345       | 80.05%  |
| 1     | 74        | 17.17%  |
| 0     | 9         | 2.09%   |
| 3     | 2         | 0.46%   |
| 4     | 1         | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 341       | 78.39%  |
| Yes  | 94        | 21.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 94        | 34.69%  |
| Realtek Semiconductor           | 45        | 16.61%  |
| Qualcomm Atheros Communications | 23        | 8.49%   |
| Broadcom                        | 21        | 7.75%   |
| Foxconn / Hon Hai               | 19        | 7.01%   |
| Hewlett-Packard                 | 13        | 4.8%    |
| Lite-On Technology              | 12        | 4.43%   |
| Dell                            | 9         | 3.32%   |
| IMC Networks                    | 8         | 2.95%   |
| Apple                           | 7         | 2.58%   |
| Cambridge Silicon Radio         | 4         | 1.48%   |
| Foxconn International           | 3         | 1.11%   |
| ASUSTek Computer                | 3         | 1.11%   |
| Toshiba                         | 2         | 0.74%   |
| Taiyo Yuden                     | 1         | 0.37%   |
| Realtek                         | 1         | 0.37%   |
| Ralink Technology               | 1         | 0.37%   |
| Ralink                          | 1         | 0.37%   |
| Qcom                            | 1         | 0.37%   |
| Chicony Electronics             | 1         | 0.37%   |
| Askey Computer                  | 1         | 0.37%   |
| Alps Electric                   | 1         | 0.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 47        | 17.34%  |
| Realtek Bluetooth Radio                                                             | 27        | 9.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 14        | 5.17%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 13        | 4.8%    |
| Intel AX201 Bluetooth                                                               | 13        | 4.8%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 10        | 3.69%   |
| Intel AX200 Bluetooth                                                               | 7         | 2.58%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 7         | 2.58%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 6         | 2.21%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.85%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 5         | 1.85%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 1.85%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 1.85%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 1.48%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 1.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 1.48%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 4         | 1.48%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 1.48%   |
| Apple Bluetooth Host Controller                                                     | 4         | 1.48%   |
| Intel AX210 Bluetooth                                                               | 3         | 1.11%   |
| IMC Networks Bluetooth Device                                                       | 3         | 1.11%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 3         | 1.11%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 3         | 1.11%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 1.11%   |
| Foxconn / Hon Hai Acer Module                                                       | 3         | 1.11%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 3         | 1.11%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.74%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.74%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.74%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.74%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.74%   |
| Lite-On Atheros Bluetooth                                                           | 2         | 0.74%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.74%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 0.74%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 0.74%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.74%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.74%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 2         | 0.74%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.74%   |
| Broadcom Bluetooth                                                                  | 2         | 0.74%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 342       | 68.54%  |
| AMD                              | 92        | 18.44%  |
| Nvidia                           | 46        | 9.22%   |
| Silicon Integrated Systems [SiS] | 6         | 1.2%    |
| Texas Instruments                | 3         | 0.6%    |
| C-Media Electronics              | 2         | 0.4%    |
| Yamaha                           | 1         | 0.2%    |
| VIA Technologies                 | 1         | 0.2%    |
| Tenx Technology                  | 1         | 0.2%    |
| Realtek Semiconductor            | 1         | 0.2%    |
| GN Netcom                        | 1         | 0.2%    |
| Generalplus Technology           | 1         | 0.2%    |
| Dell                             | 1         | 0.2%    |
| Audioengine                      | 1         | 0.2%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 40        | 6.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 38        | 6.37%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 37        | 6.2%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 31        | 5.19%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 31        | 5.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 26        | 4.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 22        | 3.69%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 19        | 3.18%   |
| Intel 8 Series HD Audio Controller                                                                | 19        | 3.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 17        | 2.85%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 14        | 2.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 2.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 14        | 2.35%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 14        | 2.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 13        | 2.18%   |
| AMD High Definition Audio Controller                                                              | 12        | 2.01%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 1.84%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 10        | 1.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10        | 1.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 10        | 1.68%   |
| AMD FCH Azalia Controller                                                                         | 10        | 1.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 1.51%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 1.51%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.34%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.17%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 1.17%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.01%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.01%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.01%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 6         | 1.01%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 0.84%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 0.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.67%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.67%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 4         | 0.67%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 4         | 0.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 0.67%   |
| AMD Wrestler HDMI Audio                                                                           | 4         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 37        | 25.69%  |
| SK hynix                     | 32        | 22.22%  |
| Unknown                      | 18        | 12.5%   |
| Kingston                     | 14        | 9.72%   |
| Micron Technology            | 10        | 6.94%   |
| Ramaxel Technology           | 4         | 2.78%   |
| Nanya Technology             | 4         | 2.78%   |
| G.Skill                      | 4         | 2.78%   |
| A-DATA Technology            | 4         | 2.78%   |
| Crucial                      | 3         | 2.08%   |
| Unknown (ABCD)               | 2         | 1.39%   |
| Smart                        | 2         | 1.39%   |
| GSkill                       | 2         | 1.39%   |
| Transcend                    | 1         | 0.69%   |
| Strontium                    | 1         | 0.69%   |
| Patriot Memory (PDP Systems) | 1         | 0.69%   |
| Patriot                      | 1         | 0.69%   |
| Lexar Co Limited             | 1         | 0.69%   |
| Corsair                      | 1         | 0.69%   |
| AMD                          | 1         | 0.69%   |
| Unknown                      | 1         | 0.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.94%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 1.29%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.29%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 1.29%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 2         | 1.29%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.29%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.29%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 1.29%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 1.29%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.29%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.29%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.29%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.29%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.29%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.29%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s            | 2         | 1.29%   |
| Unknown RAM Module SODIMM DDR                                    | 1         | 0.65%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.65%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.65%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1600MT/s                   | 1         | 0.65%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.65%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.65%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 0.65%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 0.65%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.65%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 0.65%   |
| Unknown RAM Module 1024MB SODIMM DDR3                            | 1         | 0.65%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 0.65%   |
| Transcend RAM JM800QSU-2G 2GB SODIMM DDR2 975MT/s                | 1         | 0.65%   |
| Strontium RAM SRT4G86S0-H9H 4GB SODIMM DDR3 1067MT/s             | 1         | 0.65%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 1         | 0.65%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 1         | 0.65%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 1         | 0.65%   |
| SK hynix RAM Module 512MB SODIMM DDR 533MT/s                     | 1         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 53        | 41.73%  |
| DDR3   | 47        | 37.01%  |
| DDR2   | 13        | 10.24%  |
| SDRAM  | 6         | 4.72%   |
| LPDDR4 | 3         | 2.36%   |
| DDR    | 3         | 2.36%   |
| LPDDR3 | 2         | 1.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 121       | 96.03%  |
| Row Of Chips | 4         | 3.17%   |
| Unknown      | 1         | 0.79%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 48        | 34.78%  |
| 4096    | 35        | 25.36%  |
| 2048    | 31        | 22.46%  |
| 16384   | 10        | 7.25%   |
| 1024    | 8         | 5.8%    |
| 32768   | 3         | 2.17%   |
| 512     | 2         | 1.45%   |
| Unknown | 1         | 0.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 28        | 20.74%  |
| 3200    | 25        | 18.52%  |
| 2667    | 24        | 17.78%  |
| 2400    | 10        | 7.41%   |
| Unknown | 9         | 6.67%   |
| 1333    | 5         | 3.7%    |
| 667     | 5         | 3.7%    |
| 1067    | 4         | 2.96%   |
| 3266    | 3         | 2.22%   |
| 2133    | 3         | 2.22%   |
| 1334    | 3         | 2.22%   |
| 800     | 3         | 2.22%   |
| 533     | 3         | 2.22%   |
| 4199    | 2         | 1.48%   |
| 2048    | 2         | 1.48%   |
| 975     | 2         | 1.48%   |
| 4267    | 1         | 0.74%   |
| 2267    | 1         | 0.74%   |
| 1867    | 1         | 0.74%   |
| 1200    | 1         | 0.74%   |

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
| Chicony Electronics                    | 79        | 23.03%  |
| IMC Networks                           | 34        | 9.91%   |
| Microdia                               | 29        | 8.45%   |
| Suyin                                  | 28        | 8.16%   |
| Realtek Semiconductor                  | 22        | 6.41%   |
| Quanta                                 | 22        | 6.41%   |
| Sunplus Innovation Technology          | 21        | 6.12%   |
| Acer                                   | 21        | 6.12%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 3.79%   |
| Silicon Motion                         | 9         | 2.62%   |
| Luxvisions Innotech Limited            | 8         | 2.33%   |
| Apple                                  | 8         | 2.33%   |
| Syntek                                 | 6         | 1.75%   |
| Ricoh                                  | 6         | 1.75%   |
| Bison Electronics                      | 6         | 1.75%   |
| Importek                               | 5         | 1.46%   |
| Alcor Micro                            | 5         | 1.46%   |
| Z-Star Microelectronics                | 3         | 0.87%   |
| Lenovo                                 | 3         | 0.87%   |
| ALi                                    | 3         | 0.87%   |
| Sunplus Technology                     | 2         | 0.58%   |
| Lite-On Technology                     | 2         | 0.58%   |
| USB Camera                             | 1         | 0.29%   |
| Samsung Electronics                    | 1         | 0.29%   |
| OmniVision Technologies                | 1         | 0.29%   |
| LG Electronics                         | 1         | 0.29%   |
| Intel                                  | 1         | 0.29%   |
| Generalplus Technology                 | 1         | 0.29%   |
| eMPIA Technology                       | 1         | 0.29%   |
| Alpha Imaging Technology               | 1         | 0.29%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 16        | 4.65%   |
| Microdia Integrated_Webcam_HD                        | 12        | 3.49%   |
| Chicony HD WebCam                                    | 8         | 2.33%   |
| Quanta HP Webcam                                     | 7         | 2.03%   |
| Acer Integrated Camera                               | 7         | 2.03%   |
| IMC Networks Integrated Camera                       | 6         | 1.74%   |
| Chicony HP TrueVision HD Camera                      | 6         | 1.74%   |
| Suyin HP TrueVision HD                               | 5         | 1.45%   |
| Quanta HP TrueVision HD Camera                       | 5         | 1.45%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 5         | 1.45%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 5         | 1.45%   |
| Realtek USB2.0 camera                                | 4         | 1.16%   |
| Realtek Lenovo EasyCamera                            | 4         | 1.16%   |
| Realtek Integrated_Webcam_HD                         | 4         | 1.16%   |
| Microdia USB 2.0 Camera                              | 4         | 1.16%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 4         | 1.16%   |
| IMC Networks EasyCamera                              | 4         | 1.16%   |
| Chicony USB2.0 HD UVC WebCam                         | 4         | 1.16%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam     | 4         | 1.16%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 4         | 1.16%   |
| Suyin HD WebCam                                      | 3         | 0.87%   |
| Suyin Acer/HP Integrated Webcam [CN0314]             | 3         | 0.87%   |
| Suyin Acer HD Crystal Eye webcam                     | 3         | 0.87%   |
| Suyin 1.3M HD WebCam                                 | 3         | 0.87%   |
| Sunplus Laptop_Integrated_Webcam_HD                  | 3         | 0.87%   |
| Sunplus HP TrueVision HD Camera                      | 3         | 0.87%   |
| Sunplus HD WebCam                                    | 3         | 0.87%   |
| Silicon Motion WebCam SC-0311139N                    | 3         | 0.87%   |
| Realtek USB2.0 VGA UVC WebCam                        | 3         | 0.87%   |
| Quanta VGA WebCam                                    | 3         | 0.87%   |
| Microdia Sonix USB 2.0 Camera                        | 3         | 0.87%   |
| Microdia Integrated Webcam HD                        | 3         | 0.87%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 3         | 0.87%   |
| Chicony USB 2.0 Camera                               | 3         | 0.87%   |
| Chicony EasyCamera                                   | 3         | 0.87%   |
| Chicony 2.0M UVC Webcam / CNF7129                    | 3         | 0.87%   |
| Apple Built-in iSight                                | 3         | 0.87%   |
| Alcor Micro USB 2.0 Camera                           | 3         | 0.87%   |
| Acer Lenovo EasyCamera                               | 3         | 0.87%   |
| Acer HD Webcam                                       | 3         | 0.87%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 25        | 44.64%  |
| AuthenTec                  | 11        | 19.64%  |
| STMicroelectronics         | 5         | 8.93%   |
| Synaptics                  | 4         | 7.14%   |
| LighTuning Technology      | 3         | 5.36%   |
| Upek                       | 2         | 3.57%   |
| Shenzhen Goodix Technology | 2         | 3.57%   |
| Elan Microelectronics      | 2         | 3.57%   |
| Microsoft                  | 1         | 1.79%   |
| Focal-systems.Corp         | 1         | 1.79%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader               | 5         | 8.93%   |
| STMicroelectronics Fingerprint Reader                    | 5         | 8.93%   |
| Validity Sensors VFS301 Fingerprint Reader               | 4         | 7.14%   |
| AuthenTec AES1600                                        | 4         | 7.14%   |
| Validity Sensors VFS451 Fingerprint Reader               | 3         | 5.36%   |
| Validity Sensors Fingerprint scanner                     | 3         | 5.36%   |
| AuthenTec AES2501 Fingerprint Sensor                     | 3         | 5.36%   |
| Validity Sensors VFS5011 Fingerprint Reader              | 2         | 3.57%   |
| Validity Sensors VFS491                                  | 2         | 3.57%   |
| Validity Sensors Synaptics WBDI                          | 2         | 3.57%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 2         | 3.57%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 3.57%   |
| Shenzhen Goodix  FingerPrint Device                      | 2         | 3.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor              | 2         | 3.57%   |
| Elan ELAN:Fingerprint                                    | 2         | 3.57%   |
| AuthenTec Fingerprint Sensor                             | 2         | 3.57%   |
| AuthenTec AES2810                                        | 2         | 3.57%   |
| Validity Sensors VFS101 Fingerprint Reader               | 1         | 1.79%   |
| Validity Sensors VFS Fingerprint sensor                  | 1         | 1.79%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 1.79%   |
| Validity Sensors Swipe Fingerprint Sensor                | 1         | 1.79%   |
| Synaptics UWP WBDI Device                                | 1         | 1.79%   |
| Synaptics Metallica MOH Touch Fingerprint Reader         | 1         | 1.79%   |
| Microsoft Fingerprint Reader                             | 1         | 1.79%   |
| LighTuning Fingerprint Reader                            | 1         | 1.79%   |
| Focal-systems.Corp FT9201Fingerprint.                    | 1         | 1.79%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 13        | 54.17%  |
| O2 Micro              | 5         | 20.83%  |
| Alcor Micro           | 3         | 12.5%   |
| Upek                  | 1         | 4.17%   |
| Lenovo                | 1         | 4.17%   |
| Gemalto (was Gemplus) | 1         | 4.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 29.17%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 12.5%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4.17%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 4.17%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4.17%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 4.17%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 4.17%   |
| Broadcom 5880                                                                | 1         | 4.17%   |
| Broadcom 58200                                                               | 1         | 4.17%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 280       | 63.64%  |
| 1     | 118       | 26.82%  |
| 2     | 30        | 6.82%   |
| 3     | 9         | 2.05%   |
| 4     | 2         | 0.45%   |
| 6     | 1         | 0.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 56        | 26.67%  |
| Fingerprint reader       | 55        | 26.19%  |
| Net/wireless             | 36        | 17.14%  |
| Chipcard                 | 22        | 10.48%  |
| Multimedia controller    | 19        | 9.05%   |
| Storage                  | 6         | 2.86%   |
| Communication controller | 6         | 2.86%   |
| Bluetooth                | 3         | 1.43%   |
| Flash memory             | 2         | 0.95%   |
| Sound                    | 1         | 0.48%   |
| Network                  | 1         | 0.48%   |
| Dvb card                 | 1         | 0.48%   |
| Card reader              | 1         | 0.48%   |
| Camera                   | 1         | 0.48%   |

