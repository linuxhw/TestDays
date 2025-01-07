Linux in Romania - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Romania.

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

Total: 2253

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Sony          | VGN-NR21E_S                 | [0ed147c4fb](https://linux-hardware.org/?probe=0ed147c4fb) | Jan 05, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [0f5c50a01c](https://linux-hardware.org/?probe=0f5c50a01c) | Jan 05, 2025 |
| ASUSTek       | ROG Strix G713RC_G713RC     | [721dbc3f65](https://linux-hardware.org/?probe=721dbc3f65) | Jan 04, 2025 |
| ASUSTek       | ROG Strix G713RC_G713RC     | [e6b0e5183e](https://linux-hardware.org/?probe=e6b0e5183e) | Jan 04, 2025 |
| Toshiba       | Satellite C660              | [0767070a44](https://linux-hardware.org/?probe=0767070a44) | Jan 03, 2025 |
| Acer          | Aspire A315-24P             | [40320094a6](https://linux-hardware.org/?probe=40320094a6) | Jan 02, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [110b5ee190](https://linux-hardware.org/?probe=110b5ee190) | Jan 02, 2025 |
| MSI           | Vector GP76HX 12UGS         | [3873360b8b](https://linux-hardware.org/?probe=3873360b8b) | Jan 02, 2025 |
| Lenovo        | ThinkPad E550 20DF007YRI    | [8ad38acc8a](https://linux-hardware.org/?probe=8ad38acc8a) | Dec 31, 2024 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [7a8e2cd7ed](https://linux-hardware.org/?probe=7a8e2cd7ed) | Dec 30, 2024 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [104b0f2168](https://linux-hardware.org/?probe=104b0f2168) | Dec 30, 2024 |
| ASUSTek       | X541UVK                     | [84cde5a12c](https://linux-hardware.org/?probe=84cde5a12c) | Dec 30, 2024 |
| HP            | Laptop 17-by3xxx            | [798564ee8d](https://linux-hardware.org/?probe=798564ee8d) | Dec 28, 2024 |
| ASUSTek       | X550VL                      | [f39f501a7f](https://linux-hardware.org/?probe=f39f501a7f) | Dec 28, 2024 |
| Acer          | Aspire E1-571G              | [6da76de24e](https://linux-hardware.org/?probe=6da76de24e) | Dec 27, 2024 |
| ASUSTek       | X541UVK                     | [e84d6fc1f1](https://linux-hardware.org/?probe=e84d6fc1f1) | Dec 26, 2024 |
| HP            | EliteBook 8460p             | [0916dd5986](https://linux-hardware.org/?probe=0916dd5986) | Dec 25, 2024 |
| HP            | EliteBook 840 G3            | [bae2eb1cb6](https://linux-hardware.org/?probe=bae2eb1cb6) | Dec 25, 2024 |
| Acer          | Aspire A517-51G             | [4c16c27b7b](https://linux-hardware.org/?probe=4c16c27b7b) | Dec 25, 2024 |
| HP            | ZBook FuRY 16 G10 Mobile    | [3914f42ba9](https://linux-hardware.org/?probe=3914f42ba9) | Dec 23, 2024 |
| Lenovo        | V330-15IKB 81AX             | [1b1e58284a](https://linux-hardware.org/?probe=1b1e58284a) | Dec 23, 2024 |
| HP            | EliteBook 8460p             | [963d7abc23](https://linux-hardware.org/?probe=963d7abc23) | Dec 21, 2024 |
| HP            | EliteBook 850 G5            | [e54906d193](https://linux-hardware.org/?probe=e54906d193) | Dec 21, 2024 |
| ASUSTek       | ASUS Vivobook S 14 M5406... | [5245e69e47](https://linux-hardware.org/?probe=5245e69e47) | Dec 20, 2024 |
| Lenovo        | ThinkBook 16 G7 IML 21MS    | [79b9b179ef](https://linux-hardware.org/?probe=79b9b179ef) | Dec 18, 2024 |
| HP            | OMEN by Laptop 17-ck1xxx    | [a39d299b50](https://linux-hardware.org/?probe=a39d299b50) | Dec 15, 2024 |
| ASUSTek       | X541UAK                     | [3b5b163084](https://linux-hardware.org/?probe=3b5b163084) | Dec 14, 2024 |
| Lenovo        | Legion S7 15IMH5 82BC       | [4a38241f5d](https://linux-hardware.org/?probe=4a38241f5d) | Dec 13, 2024 |
| Acer          | Nitro AN515-58              | [444ca7d70a](https://linux-hardware.org/?probe=444ca7d70a) | Dec 12, 2024 |
| Acer          | Nitro AN515-58              | [b18d1c210a](https://linux-hardware.org/?probe=b18d1c210a) | Dec 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [c22f3c5d77](https://linux-hardware.org/?probe=c22f3c5d77) | Dec 12, 2024 |
| ASUSTek       | X541UAK                     | [b0c9088b05](https://linux-hardware.org/?probe=b0c9088b05) | Dec 10, 2024 |
| HP            | OMEN by Laptop 17-cb1xxx    | [4c1f450872](https://linux-hardware.org/?probe=4c1f450872) | Dec 08, 2024 |
| Dell          | Precision 7530              | [0548741152](https://linux-hardware.org/?probe=0548741152) | Dec 07, 2024 |
| Acer          | Aspire 7530                 | [d3ba125ebf](https://linux-hardware.org/?probe=d3ba125ebf) | Dec 07, 2024 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | [a3dad268d2](https://linux-hardware.org/?probe=a3dad268d2) | Dec 06, 2024 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | [8ab8ddf97e](https://linux-hardware.org/?probe=8ab8ddf97e) | Dec 06, 2024 |
| Lenovo        | ThinkPad T440p 20AWS0WP0... | [1b667db1d3](https://linux-hardware.org/?probe=1b667db1d3) | Dec 04, 2024 |
| Lenovo        | ThinkPad T440p 20AWS0WP0... | [4b2d509faa](https://linux-hardware.org/?probe=4b2d509faa) | Dec 04, 2024 |
| Dell          | Vostro 15 3515              | [c220d225cc](https://linux-hardware.org/?probe=c220d225cc) | Dec 03, 2024 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | [3a866971df](https://linux-hardware.org/?probe=3a866971df) | Dec 02, 2024 |
| Lenovo        | ThinkPad T60 2007YQY        | [8d792cc626](https://linux-hardware.org/?probe=8d792cc626) | Dec 02, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [eec68584ed](https://linux-hardware.org/?probe=eec68584ed) | Dec 01, 2024 |
| Apple         | MacBookPro8,1               | [82c25b95f2](https://linux-hardware.org/?probe=82c25b95f2) | Nov 30, 2024 |
| Acer          | Predator PT316-51s          | [59b81c6d72](https://linux-hardware.org/?probe=59b81c6d72) | Nov 29, 2024 |
| HP            | EliteBook 840 G6            | [942a83432e](https://linux-hardware.org/?probe=942a83432e) | Nov 26, 2024 |
| Lenovo        | ThinkPad E550 20DF007YRI    | [8be5fd8c72](https://linux-hardware.org/?probe=8be5fd8c72) | Nov 25, 2024 |
| ASUSTek       | ROG Strix G713PU_G713PU     | [9743c11187](https://linux-hardware.org/?probe=9743c11187) | Nov 24, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [9456b52471](https://linux-hardware.org/?probe=9456b52471) | Nov 23, 2024 |
| Lenovo        | ThinkPad E550 20DF007YRI    | [f652a62a8c](https://linux-hardware.org/?probe=f652a62a8c) | Nov 23, 2024 |
| HP            | Pavilion g7                 | [059e972b96](https://linux-hardware.org/?probe=059e972b96) | Nov 23, 2024 |
| Chuwi         | GemiBook Pro                | [d9d23cdc2c](https://linux-hardware.org/?probe=d9d23cdc2c) | Nov 18, 2024 |
| Chuwi         | GemiBook Pro                | [1a57440afe](https://linux-hardware.org/?probe=1a57440afe) | Nov 18, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [840bd96126](https://linux-hardware.org/?probe=840bd96126) | Nov 18, 2024 |
| Lenovo        | Legion 7 16IRX9 83FD        | [d3c3b4b1a7](https://linux-hardware.org/?probe=d3c3b4b1a7) | Nov 17, 2024 |
| Lenovo        | Legion 7 16IRX9 83FD        | [840968c712](https://linux-hardware.org/?probe=840968c712) | Nov 17, 2024 |
| HP            | Pavilion dv6500             | [a875301ed0](https://linux-hardware.org/?probe=a875301ed0) | Nov 15, 2024 |
| Dell          | Precision 5690              | [d1160c82f8](https://linux-hardware.org/?probe=d1160c82f8) | Nov 14, 2024 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [3272a7f74d](https://linux-hardware.org/?probe=3272a7f74d) | Nov 14, 2024 |
| Apple         | MacBookPro16,2              | [1a7115becf](https://linux-hardware.org/?probe=1a7115becf) | Nov 12, 2024 |
| Apple         | MacBookPro16,2              | [612dc6bdf9](https://linux-hardware.org/?probe=612dc6bdf9) | Nov 12, 2024 |
| Toshiba       | Satellite C660              | [efca38e06f](https://linux-hardware.org/?probe=efca38e06f) | Nov 08, 2024 |
| Acer          | Aspire A515-45              | [56fa1eb0ff](https://linux-hardware.org/?probe=56fa1eb0ff) | Nov 04, 2024 |
| Dell          | Precision 5530              | [82a3124495](https://linux-hardware.org/?probe=82a3124495) | Nov 03, 2024 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [27e080a699](https://linux-hardware.org/?probe=27e080a699) | Nov 02, 2024 |
| Lenovo        | IdeaPad Pro 5 14AHP9 83D... | [e82e4d82e0](https://linux-hardware.org/?probe=e82e4d82e0) | Nov 01, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | [6c33a69b77](https://linux-hardware.org/?probe=6c33a69b77) | Oct 29, 2024 |
| Lenovo        | ThinkPad X220 42902P3       | [5224137903](https://linux-hardware.org/?probe=5224137903) | Oct 29, 2024 |
| ASUSTek       | X541UVK                     | [1bec944a0f](https://linux-hardware.org/?probe=1bec944a0f) | Oct 29, 2024 |
| ASUSTek       | X541UVK                     | [308efea806](https://linux-hardware.org/?probe=308efea806) | Oct 29, 2024 |
| Lenovo        | ThinkPad X220 42902P3       | [c4a87fec75](https://linux-hardware.org/?probe=c4a87fec75) | Oct 28, 2024 |
| Lenovo        | ThinkPad Edge E320 1298A... | [db967cf215](https://linux-hardware.org/?probe=db967cf215) | Oct 27, 2024 |
| Lenovo        | 15ARE05 81W4                | [049414e1fb](https://linux-hardware.org/?probe=049414e1fb) | Oct 27, 2024 |
| Toshiba       | Satellite C850D-119         | [e3773c1a70](https://linux-hardware.org/?probe=e3773c1a70) | Oct 27, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | [80e86c27ad](https://linux-hardware.org/?probe=80e86c27ad) | Oct 23, 2024 |
| Lenovo        | B50-70 20384                | [09f5eef685](https://linux-hardware.org/?probe=09f5eef685) | Oct 21, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | [3be6a2a535](https://linux-hardware.org/?probe=3be6a2a535) | Oct 21, 2024 |
| Acer          | Aspire V3-571G              | [58cd9eafa2](https://linux-hardware.org/?probe=58cd9eafa2) | Oct 19, 2024 |
| Lenovo        | Legion 5 15IMH6 82NL        | [7f08763473](https://linux-hardware.org/?probe=7f08763473) | Oct 19, 2024 |
| Lenovo        | Legion 5 15IMH6 82NL        | [f3ed5c74a3](https://linux-hardware.org/?probe=f3ed5c74a3) | Oct 19, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b55e37a8aa](https://linux-hardware.org/?probe=b55e37a8aa) | Oct 18, 2024 |
| System76      | Darter Pro                  | [a3b432217e](https://linux-hardware.org/?probe=a3b432217e) | Oct 17, 2024 |
| Acer          | Nitro ANV15-51              | [17d1356bba](https://linux-hardware.org/?probe=17d1356bba) | Oct 17, 2024 |
| Acer          | Nitro ANV15-51              | [65b2fb14db](https://linux-hardware.org/?probe=65b2fb14db) | Oct 17, 2024 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [facae97aa8](https://linux-hardware.org/?probe=facae97aa8) | Oct 16, 2024 |
| Acer          | Aspire A315-44P             | [2571a863c2](https://linux-hardware.org/?probe=2571a863c2) | Oct 15, 2024 |
| Lenovo        | ThinkPad X390 20Q0S1FS00    | [a8debb3ea7](https://linux-hardware.org/?probe=a8debb3ea7) | Oct 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7ce127030d](https://linux-hardware.org/?probe=7ce127030d) | Oct 13, 2024 |
| Lenovo        | G550 20023                  | [2fc18b7f13](https://linux-hardware.org/?probe=2fc18b7f13) | Oct 13, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [08db2a684b](https://linux-hardware.org/?probe=08db2a684b) | Oct 13, 2024 |
| Dell          | Inspiron 3580               | [f9d97279aa](https://linux-hardware.org/?probe=f9d97279aa) | Oct 13, 2024 |
| Dell          | Inspiron 3580               | [0900d30a08](https://linux-hardware.org/?probe=0900d30a08) | Oct 13, 2024 |
| HP            | OMEN X by Laptop 15-dg0x... | [f0f16c0be5](https://linux-hardware.org/?probe=f0f16c0be5) | Oct 12, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [48cb304978](https://linux-hardware.org/?probe=48cb304978) | Oct 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [4d3bf0cfba](https://linux-hardware.org/?probe=4d3bf0cfba) | Oct 11, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [ff68925fa4](https://linux-hardware.org/?probe=ff68925fa4) | Oct 10, 2024 |
| ASUSTek       | X556UQK                     | [b5e78247a7](https://linux-hardware.org/?probe=b5e78247a7) | Oct 09, 2024 |
| HP            | EliteBook 2570p             | [4167d934bb](https://linux-hardware.org/?probe=4167d934bb) | Oct 07, 2024 |
| ASUSTek       | X541UVK                     | [b5ad97117b](https://linux-hardware.org/?probe=b5ad97117b) | Oct 07, 2024 |
| ASUSTek       | ASUS Vivobook Pro 15 N65... | [4b1fe1b108](https://linux-hardware.org/?probe=4b1fe1b108) | Oct 01, 2024 |
| HP            | EliteBook 860 16 inch G1... | [ce12c2ab86](https://linux-hardware.org/?probe=ce12c2ab86) | Sep 30, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [645c999c2b](https://linux-hardware.org/?probe=645c999c2b) | Sep 28, 2024 |
| HP            | ZBook 15 G5                 | [d62ce9aa5a](https://linux-hardware.org/?probe=d62ce9aa5a) | Sep 25, 2024 |
| Apple         | MacBookPro11,2              | [f82874c7bf](https://linux-hardware.org/?probe=f82874c7bf) | Sep 23, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [5354d8dedb](https://linux-hardware.org/?probe=5354d8dedb) | Sep 23, 2024 |
| ASUSTek       | X550JX                      | [ed8b9a0c40](https://linux-hardware.org/?probe=ed8b9a0c40) | Sep 23, 2024 |
| ASUSTek       | ROG Strix G513IE_G513IE     | [6cdf2f1f7f](https://linux-hardware.org/?probe=6cdf2f1f7f) | Sep 22, 2024 |
| HP            | EliteBook 840 G6            | [3051525bf1](https://linux-hardware.org/?probe=3051525bf1) | Sep 22, 2024 |
| Acer          | Aspire E5-575               | [c29c98e6a0](https://linux-hardware.org/?probe=c29c98e6a0) | Sep 22, 2024 |
| Lenovo        | ThinkPad E16 Gen 2 21MA0... | [b5245f6826](https://linux-hardware.org/?probe=b5245f6826) | Sep 21, 2024 |
| ASUSTek       | ProArt P16 H7606WI_H7606... | [e0fc023be7](https://linux-hardware.org/?probe=e0fc023be7) | Sep 19, 2024 |
| Acer          | Nitro AN515-58              | [82685285ce](https://linux-hardware.org/?probe=82685285ce) | Sep 18, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [325da6b558](https://linux-hardware.org/?probe=325da6b558) | Sep 16, 2024 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [5ad05846db](https://linux-hardware.org/?probe=5ad05846db) | Sep 15, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8da5010b73](https://linux-hardware.org/?probe=8da5010b73) | Sep 12, 2024 |
| Lenovo        | ThinkPad T430 2347FF9       | [0e9f60231f](https://linux-hardware.org/?probe=0e9f60231f) | Sep 11, 2024 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [9333a17b1f](https://linux-hardware.org/?probe=9333a17b1f) | Sep 11, 2024 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | [630b6c1179](https://linux-hardware.org/?probe=630b6c1179) | Sep 11, 2024 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [6f92c6744a](https://linux-hardware.org/?probe=6f92c6744a) | Sep 10, 2024 |
| Lenovo        | V310-15ISK 80SY             | [be693955cd](https://linux-hardware.org/?probe=be693955cd) | Sep 09, 2024 |
| Complet       | MY8305                      | [fdab3231de](https://linux-hardware.org/?probe=fdab3231de) | Sep 07, 2024 |
| Acer          | Aspire A315-21G             | [1bd863c2c2](https://linux-hardware.org/?probe=1bd863c2c2) | Sep 05, 2024 |
| HP            | Laptop 17-cn3xxx            | [fe37e84853](https://linux-hardware.org/?probe=fe37e84853) | Sep 05, 2024 |
| Acer          | Aspire A515-45              | [fbffd2655c](https://linux-hardware.org/?probe=fbffd2655c) | Sep 05, 2024 |
| Schenker      | XMG PRO (E23)               | [a1b8f9dca6](https://linux-hardware.org/?probe=a1b8f9dca6) | Sep 03, 2024 |
| ASUSTek       | X550DP                      | [c3f9c0f31c](https://linux-hardware.org/?probe=c3f9c0f31c) | Sep 03, 2024 |
| ASUSTek       | X550DP                      | [e1a17da1b6](https://linux-hardware.org/?probe=e1a17da1b6) | Sep 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [ab4ea0dcac](https://linux-hardware.org/?probe=ab4ea0dcac) | Sep 01, 2024 |
| ASUSTek       | X550JX                      | [3e6e47761d](https://linux-hardware.org/?probe=3e6e47761d) | Sep 01, 2024 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [1e6412c54a](https://linux-hardware.org/?probe=1e6412c54a) | Aug 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [74da2d9a21](https://linux-hardware.org/?probe=74da2d9a21) | Aug 30, 2024 |
| HP            | OMEN Laptop 15-en0xxx       | [1e19fc2c83](https://linux-hardware.org/?probe=1e19fc2c83) | Aug 30, 2024 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [b54b92bc81](https://linux-hardware.org/?probe=b54b92bc81) | Aug 28, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [0670a48314](https://linux-hardware.org/?probe=0670a48314) | Aug 28, 2024 |
| HP            | 250 G8 Notebook PC          | [7ac05b5327](https://linux-hardware.org/?probe=7ac05b5327) | Aug 27, 2024 |
| Valve         | Galileo                     | [8f13ce096b](https://linux-hardware.org/?probe=8f13ce096b) | Aug 27, 2024 |
| Acer          | Aspire A515-47              | [f39eb3b2f9](https://linux-hardware.org/?probe=f39eb3b2f9) | Aug 23, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [d9fd7042a5](https://linux-hardware.org/?probe=d9fd7042a5) | Aug 23, 2024 |
| ASUSTek       | ASUS Vivobook S 14 M5406... | [c4fef6d124](https://linux-hardware.org/?probe=c4fef6d124) | Aug 16, 2024 |
| HP            | ProBook 450 15.6 inch G9... | [b53667784c](https://linux-hardware.org/?probe=b53667784c) | Aug 14, 2024 |
| HP            | Pavilion Notebook           | [d3a5544148](https://linux-hardware.org/?probe=d3a5544148) | Aug 14, 2024 |
| HP            | Laptop 14s-dq1xxx           | [1476999c39](https://linux-hardware.org/?probe=1476999c39) | Aug 13, 2024 |
| ASUSTek       | G750JM                      | [f7169a12d4](https://linux-hardware.org/?probe=f7169a12d4) | Aug 11, 2024 |
| Dell          | Vostro 15 3515              | [1a4a792879](https://linux-hardware.org/?probe=1a4a792879) | Aug 11, 2024 |
| Lenovo        | ThinkPad L420 78294XG       | [3378ef7e66](https://linux-hardware.org/?probe=3378ef7e66) | Aug 07, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [471cbd54ba](https://linux-hardware.org/?probe=471cbd54ba) | Aug 05, 2024 |
| Sony          | VPCEH1L0E                   | [b6126492d1](https://linux-hardware.org/?probe=b6126492d1) | Aug 05, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [dbaab84f85](https://linux-hardware.org/?probe=dbaab84f85) | Aug 05, 2024 |
| Lenovo        | LOQ 16APH8 82XU             | [022fce9e22](https://linux-hardware.org/?probe=022fce9e22) | Aug 05, 2024 |
| Lenovo        | Legion 5 15ITH6H 82JH       | [ca1e6f7786](https://linux-hardware.org/?probe=ca1e6f7786) | Aug 04, 2024 |
| Lenovo        | ThinkPad T530 2429B69       | [cfe8e9461f](https://linux-hardware.org/?probe=cfe8e9461f) | Aug 02, 2024 |
| Lenovo        | ThinkPad X200 7459LK9       | [4d3053ad8f](https://linux-hardware.org/?probe=4d3053ad8f) | Aug 01, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8bbe8fd188](https://linux-hardware.org/?probe=8bbe8fd188) | Jul 29, 2024 |
| Toshiba       | Satellite C50-A-1HF         | [429d9c2dee](https://linux-hardware.org/?probe=429d9c2dee) | Jul 28, 2024 |
| HP            | ElitePad 1000 G2            | [d7969e8d4a](https://linux-hardware.org/?probe=d7969e8d4a) | Jul 28, 2024 |
| Intel         | STCK1A32WFC H67490-303      | [b12d74f728](https://linux-hardware.org/?probe=b12d74f728) | Jul 27, 2024 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | [b505ebec8c](https://linux-hardware.org/?probe=b505ebec8c) | Jul 24, 2024 |
| Lenovo        | ThinkPad Edge E531 68856... | [37fc2e067d](https://linux-hardware.org/?probe=37fc2e067d) | Jul 23, 2024 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [6255653f2a](https://linux-hardware.org/?probe=6255653f2a) | Jul 22, 2024 |
| HP            | ProBook 455 G2              | [6e9b0d9256](https://linux-hardware.org/?probe=6e9b0d9256) | Jul 22, 2024 |
| Apple         | MacBookPro11,1              | [fa917601f3](https://linux-hardware.org/?probe=fa917601f3) | Jul 19, 2024 |
| HP            | 255 G8 Notebook PC          | [0d8bf26d80](https://linux-hardware.org/?probe=0d8bf26d80) | Jul 19, 2024 |
| HP            | EliteBook 840 14 inch G1... | [90031d618e](https://linux-hardware.org/?probe=90031d618e) | Jul 18, 2024 |
| Acer          | Aspire A515-57              | [f357c7735c](https://linux-hardware.org/?probe=f357c7735c) | Jul 16, 2024 |
| Dell          | Latitude 7480               | [c5b3a19dc6](https://linux-hardware.org/?probe=c5b3a19dc6) | Jul 16, 2024 |
| MSI           | Creator M16 HX C14VFG       | [148abc94cc](https://linux-hardware.org/?probe=148abc94cc) | Jul 15, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [a91087d3fa](https://linux-hardware.org/?probe=a91087d3fa) | Jul 09, 2024 |
| Dell          | Inspiron 5567               | [03d2cff74e](https://linux-hardware.org/?probe=03d2cff74e) | Jul 09, 2024 |
| HUAWEI        | CREF-XX                     | [eba6610b80](https://linux-hardware.org/?probe=eba6610b80) | Jul 08, 2024 |
| Valve         | Jupiter                     | [eed14819ad](https://linux-hardware.org/?probe=eed14819ad) | Jul 08, 2024 |
| Valve         | Jupiter                     | [e840ba5076](https://linux-hardware.org/?probe=e840ba5076) | Jul 08, 2024 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [1f090e0caf](https://linux-hardware.org/?probe=1f090e0caf) | Jul 07, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [f08dd79a79](https://linux-hardware.org/?probe=f08dd79a79) | Jul 06, 2024 |
| Lenovo        | ThinkPad T490s 20NYS9VG0... | [8db6b837aa](https://linux-hardware.org/?probe=8db6b837aa) | Jul 06, 2024 |
| HP            | EliteBook 820 G1            | [ed985ce59b](https://linux-hardware.org/?probe=ed985ce59b) | Jul 04, 2024 |
| Lenovo        | V310-15ISK 80SY             | [94b7066ac3](https://linux-hardware.org/?probe=94b7066ac3) | Jul 03, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [eb34572d85](https://linux-hardware.org/?probe=eb34572d85) | Jul 02, 2024 |
| Toshiba       | Satellite C50-A-1HF         | [464c82e7d2](https://linux-hardware.org/?probe=464c82e7d2) | Jun 29, 2024 |
| Lenovo        | ThinkPad T470p 20J6003DG... | [ab192cfff2](https://linux-hardware.org/?probe=ab192cfff2) | Jun 27, 2024 |
| Dell          | Precision 5570              | [46d5773924](https://linux-hardware.org/?probe=46d5773924) | Jun 26, 2024 |
| ASUSTek       | ROG Strix G713RS_G713RS     | [f33e866e3a](https://linux-hardware.org/?probe=f33e866e3a) | Jun 19, 2024 |
| ASUSTek       | T100TA                      | [2c7298ac53](https://linux-hardware.org/?probe=2c7298ac53) | Jun 17, 2024 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [f50752193a](https://linux-hardware.org/?probe=f50752193a) | Jun 15, 2024 |
| Toshiba       | Satellite A500              | [8c0070e9ab](https://linux-hardware.org/?probe=8c0070e9ab) | Jun 14, 2024 |
| Lenovo        | IdeaPad 3-15 ADA6 82KR      | [9a6d39356c](https://linux-hardware.org/?probe=9a6d39356c) | Jun 14, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [16d0d1bbdd](https://linux-hardware.org/?probe=16d0d1bbdd) | Jun 14, 2024 |
| Acer          | Aspire E5-571               | [961bd5bde2](https://linux-hardware.org/?probe=961bd5bde2) | Jun 14, 2024 |
| Dell          | System XPS L502X            | [c47c404a95](https://linux-hardware.org/?probe=c47c404a95) | Jun 13, 2024 |
| Dell          | Latitude 7480               | [c9ce520244](https://linux-hardware.org/?probe=c9ce520244) | Jun 13, 2024 |
| Myway         | U1306i                      | [a029a374de](https://linux-hardware.org/?probe=a029a374de) | Jun 12, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [10d3a7713d](https://linux-hardware.org/?probe=10d3a7713d) | Jun 12, 2024 |
| Dell          | XPS 15 9530                 | [1e145ec645](https://linux-hardware.org/?probe=1e145ec645) | Jun 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5d2466c564](https://linux-hardware.org/?probe=5d2466c564) | Jun 10, 2024 |
| HP            | 250 G7 Notebook PC          | [218c416abf](https://linux-hardware.org/?probe=218c416abf) | Jun 09, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [021499aed9](https://linux-hardware.org/?probe=021499aed9) | Jun 08, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [146cef5d74](https://linux-hardware.org/?probe=146cef5d74) | Jun 08, 2024 |
| HUAWEI        | BOM-WXX9                    | [e7e349c28e](https://linux-hardware.org/?probe=e7e349c28e) | Jun 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [72995e700f](https://linux-hardware.org/?probe=72995e700f) | Jun 07, 2024 |
| HUAWEI        | BOM-WXX9                    | [3c0ef8ae3f](https://linux-hardware.org/?probe=3c0ef8ae3f) | Jun 07, 2024 |
| Lenovo        | IdeaPad Pro 5 14IMH9 83D... | [6e7e3934c1](https://linux-hardware.org/?probe=6e7e3934c1) | Jun 05, 2024 |
| Dell          | Precision M4500             | [b04b051024](https://linux-hardware.org/?probe=b04b051024) | Jun 04, 2024 |
| Dell          | Inspiron 15-3567            | [1529cb39d6](https://linux-hardware.org/?probe=1529cb39d6) | Jun 04, 2024 |
| Dell          | XPS 15 9500                 | [5e54d8d839](https://linux-hardware.org/?probe=5e54d8d839) | Jun 02, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [187d6649ae](https://linux-hardware.org/?probe=187d6649ae) | Jun 02, 2024 |
| Lenovo        | ThinkPad T460 20FMS43Q00    | [91cbb57aa7](https://linux-hardware.org/?probe=91cbb57aa7) | May 31, 2024 |
| Dell          | Latitude E6320              | [356970f66c](https://linux-hardware.org/?probe=356970f66c) | May 30, 2024 |
| HP            | ZBook 15u G4                | [a8ce115639](https://linux-hardware.org/?probe=a8ce115639) | May 30, 2024 |
| Lenovo        | ThinkPad R60 9459WJF        | [075b8e4949](https://linux-hardware.org/?probe=075b8e4949) | May 30, 2024 |
| HP            | ProBook 6550b               | [c2fd6d6d71](https://linux-hardware.org/?probe=c2fd6d6d71) | May 27, 2024 |
| HP            | ProBook 6550b               | [05682fe802](https://linux-hardware.org/?probe=05682fe802) | May 26, 2024 |
| ASUSTek       | GL552VX                     | [9f2697991a](https://linux-hardware.org/?probe=9f2697991a) | May 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [8b30e5083a](https://linux-hardware.org/?probe=8b30e5083a) | May 26, 2024 |
| HUAWEI        | HN-WX9X                     | [8a72dd7e1b](https://linux-hardware.org/?probe=8a72dd7e1b) | May 24, 2024 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [58f66f7832](https://linux-hardware.org/?probe=58f66f7832) | May 23, 2024 |
| Acer          | Predator PHN16-72           | [288c4ba67a](https://linux-hardware.org/?probe=288c4ba67a) | May 23, 2024 |
| Jumper        | EZbook                      | [4e42f86a8c](https://linux-hardware.org/?probe=4e42f86a8c) | May 22, 2024 |
| ASUSTek       | UX310UQ                     | [766c6ca45c](https://linux-hardware.org/?probe=766c6ca45c) | May 18, 2024 |
| Toshiba       | Satellite L50-B             | [4179b24509](https://linux-hardware.org/?probe=4179b24509) | May 17, 2024 |
| Lenovo        | ThinkPad T470p 20J6003DG... | [789796e1a0](https://linux-hardware.org/?probe=789796e1a0) | May 16, 2024 |
| Dell          | Vostro 3525                 | [a9f23cadfb](https://linux-hardware.org/?probe=a9f23cadfb) | May 15, 2024 |
| Dell          | Precision 5540              | [1ac194f562](https://linux-hardware.org/?probe=1ac194f562) | May 14, 2024 |
| Lenovo        | ThinkPad T495 20NKS3YE22    | [2e301f8c1a](https://linux-hardware.org/?probe=2e301f8c1a) | May 13, 2024 |
| Dell          | Precision M4700             | [3025a7f21e](https://linux-hardware.org/?probe=3025a7f21e) | May 13, 2024 |
| Lenovo        | Legion 5 15ITH6H 82JH       | [983dacb4cb](https://linux-hardware.org/?probe=983dacb4cb) | May 12, 2024 |
| Dell          | Latitude E6320              | [3d34ee9056](https://linux-hardware.org/?probe=3d34ee9056) | May 10, 2024 |
| Acer          | Aspire A515-57              | [c7471afead](https://linux-hardware.org/?probe=c7471afead) | May 07, 2024 |
| HP            | EliteBook 840 G6            | [504b36774f](https://linux-hardware.org/?probe=504b36774f) | May 07, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [afb966db9e](https://linux-hardware.org/?probe=afb966db9e) | May 04, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [c41b2ac54b](https://linux-hardware.org/?probe=c41b2ac54b) | May 04, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [ea3a8f97a7](https://linux-hardware.org/?probe=ea3a8f97a7) | May 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [ad6d7c5f93](https://linux-hardware.org/?probe=ad6d7c5f93) | May 03, 2024 |
| ASUSTek       | X553MA                      | [1aaeefe305](https://linux-hardware.org/?probe=1aaeefe305) | May 02, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c23a3238c0](https://linux-hardware.org/?probe=c23a3238c0) | May 02, 2024 |
| Dell          | Inspiron 5567               | [caf8879e78](https://linux-hardware.org/?probe=caf8879e78) | Apr 27, 2024 |
| Toshiba       | Satellite C660              | [c2513f220d](https://linux-hardware.org/?probe=c2513f220d) | Apr 27, 2024 |
| Google        | Laser14                     | [5addd4566a](https://linux-hardware.org/?probe=5addd4566a) | Apr 27, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [86305e383e](https://linux-hardware.org/?probe=86305e383e) | Apr 25, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [113c93d444](https://linux-hardware.org/?probe=113c93d444) | Apr 25, 2024 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [f537e8aab2](https://linux-hardware.org/?probe=f537e8aab2) | Apr 24, 2024 |
| Lenovo        | ThinkPad T480 20L6S0DH0V    | [28d54c7e4d](https://linux-hardware.org/?probe=28d54c7e4d) | Apr 22, 2024 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [a206f7f2d5](https://linux-hardware.org/?probe=a206f7f2d5) | Apr 21, 2024 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | [bb18adad6a](https://linux-hardware.org/?probe=bb18adad6a) | Apr 19, 2024 |
| HP            | Pavilion Notebook           | [cee4508310](https://linux-hardware.org/?probe=cee4508310) | Apr 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [983a566cbf](https://linux-hardware.org/?probe=983a566cbf) | Apr 13, 2024 |
| BESSTAR Te... | X400                        | [0701fdbfed](https://linux-hardware.org/?probe=0701fdbfed) | Apr 12, 2024 |
| Lenovo        | ThinkPad E15 20RD005VRI     | [d7f5702701](https://linux-hardware.org/?probe=d7f5702701) | Apr 12, 2024 |
| HP            | Pavilion Notebook           | [07ccfe7f99](https://linux-hardware.org/?probe=07ccfe7f99) | Apr 11, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [85d3c8baf5](https://linux-hardware.org/?probe=85d3c8baf5) | Apr 10, 2024 |
| ASUSTek       | ROG Strix G531GU_G531GU     | [b264255cbe](https://linux-hardware.org/?probe=b264255cbe) | Apr 07, 2024 |
| ASUSTek       | ROG Strix G531GU_G531GU     | [65f080ba2d](https://linux-hardware.org/?probe=65f080ba2d) | Apr 06, 2024 |
| Google        | Landrid                     | [d4b1948b6a](https://linux-hardware.org/?probe=d4b1948b6a) | Apr 04, 2024 |
| ASUSTek       | ROG Zephyrus G16 GU605MI... | [4581288732](https://linux-hardware.org/?probe=4581288732) | Apr 04, 2024 |
| Acer          | Aspire E1-572G              | [7a19eed833](https://linux-hardware.org/?probe=7a19eed833) | Apr 03, 2024 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [054b7415b5](https://linux-hardware.org/?probe=054b7415b5) | Apr 01, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [0f82bff1ce](https://linux-hardware.org/?probe=0f82bff1ce) | Apr 01, 2024 |
| Dell          | Inspiron 5570               | [57667ea730](https://linux-hardware.org/?probe=57667ea730) | Mar 29, 2024 |
| Dell          | Inspiron 1520               | [1a4ee5c6ab](https://linux-hardware.org/?probe=1a4ee5c6ab) | Mar 27, 2024 |
| ASUSTek       | UX550VE                     | [25985cf7e8](https://linux-hardware.org/?probe=25985cf7e8) | Mar 27, 2024 |
| ASUSTek       | UX550VE                     | [433914ac7c](https://linux-hardware.org/?probe=433914ac7c) | Mar 27, 2024 |
| Acer          | Swift SF514-56T             | [37cec8bd6a](https://linux-hardware.org/?probe=37cec8bd6a) | Mar 24, 2024 |
| Lenovo        | G550 2958                   | [91d2b11e4d](https://linux-hardware.org/?probe=91d2b11e4d) | Mar 24, 2024 |
| Dell          | Inspiron 14-3452            | [1d762c03e9](https://linux-hardware.org/?probe=1d762c03e9) | Mar 21, 2024 |
| Dell          | Inspiron 14-3452            | [2951df6391](https://linux-hardware.org/?probe=2951df6391) | Mar 21, 2024 |
| Dell          | G7 7790                     | [6488d5dbe5](https://linux-hardware.org/?probe=6488d5dbe5) | Mar 21, 2024 |
| Dell          | G7 7790                     | [58718acc5f](https://linux-hardware.org/?probe=58718acc5f) | Mar 19, 2024 |
| Lenovo        | ThinkPad T480 20L6S4G72S    | [301d6aad48](https://linux-hardware.org/?probe=301d6aad48) | Mar 19, 2024 |
| HP            | ProBook 430 G5              | [cbe9e1dc0f](https://linux-hardware.org/?probe=cbe9e1dc0f) | Mar 16, 2024 |
| Dell          | Vostro 3525                 | [25cd61c444](https://linux-hardware.org/?probe=25cd61c444) | Mar 16, 2024 |
| ASUSTek       | ROG Strix G713PU_G713PU     | [307decbb24](https://linux-hardware.org/?probe=307decbb24) | Mar 16, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [18da3a8d78](https://linux-hardware.org/?probe=18da3a8d78) | Mar 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [850ae02029](https://linux-hardware.org/?probe=850ae02029) | Mar 13, 2024 |
| Acer          | Aspire A315-59              | [f1c498121d](https://linux-hardware.org/?probe=f1c498121d) | Mar 13, 2024 |
| Lenovo        | ThinkPad L14 Gen 4 21H6S... | [de4a81edcc](https://linux-hardware.org/?probe=de4a81edcc) | Mar 12, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [879e485252](https://linux-hardware.org/?probe=879e485252) | Mar 11, 2024 |
| Alienware     | m15 R7 AMD                  | [e6f85671a4](https://linux-hardware.org/?probe=e6f85671a4) | Mar 10, 2024 |
| ASUSTek       | X550JX                      | [5b8d7edfa8](https://linux-hardware.org/?probe=5b8d7edfa8) | Mar 10, 2024 |
| ASUSTek       | X550JX                      | [0fd5f29628](https://linux-hardware.org/?probe=0fd5f29628) | Mar 09, 2024 |
| ASUSTek       | X205TAW                     | [6ed323ca5c](https://linux-hardware.org/?probe=6ed323ca5c) | Mar 07, 2024 |
| ASUSTek       | X205TAW                     | [2dd874e62c](https://linux-hardware.org/?probe=2dd874e62c) | Mar 07, 2024 |
| HP            | ProBook 450 G5              | [7e89a95523](https://linux-hardware.org/?probe=7e89a95523) | Mar 06, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [23a8bcc014](https://linux-hardware.org/?probe=23a8bcc014) | Mar 06, 2024 |
| Lenovo        | V15 G3 ABA 82TV             | [e25dd52aab](https://linux-hardware.org/?probe=e25dd52aab) | Mar 06, 2024 |
| HP            | Pavilion dv6000 (GH906EA... | [be0ca4a00c](https://linux-hardware.org/?probe=be0ca4a00c) | Mar 06, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [831ff2cb1b](https://linux-hardware.org/?probe=831ff2cb1b) | Mar 02, 2024 |
| Dell          | Latitude E6420              | [bfa7f2e249](https://linux-hardware.org/?probe=bfa7f2e249) | Feb 29, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [b5cd8e1e86](https://linux-hardware.org/?probe=b5cd8e1e86) | Feb 28, 2024 |
| Toshiba       | Satellite C660              | [8a559e94c0](https://linux-hardware.org/?probe=8a559e94c0) | Feb 27, 2024 |
| HP            | OMEN by Laptop 15-dc0xxx    | [ce35471f83](https://linux-hardware.org/?probe=ce35471f83) | Feb 27, 2024 |
| Dell          | Precision M4500             | [9eb2dd262d](https://linux-hardware.org/?probe=9eb2dd262d) | Feb 26, 2024 |
| Acer          | TravelMate P256-MG          | [abcfd5362f](https://linux-hardware.org/?probe=abcfd5362f) | Feb 25, 2024 |
| Toshiba       | Satellite A500              | [ff10d941c4](https://linux-hardware.org/?probe=ff10d941c4) | Feb 25, 2024 |
| Dell          | Latitude E6510              | [a8457cc11f](https://linux-hardware.org/?probe=a8457cc11f) | Feb 25, 2024 |
| Lenovo        | ThinkPad T420 4236C92       | [57a7f3d065](https://linux-hardware.org/?probe=57a7f3d065) | Feb 25, 2024 |
| Dell          | Precision M4500             | [f6cefd913d](https://linux-hardware.org/?probe=f6cefd913d) | Feb 24, 2024 |
| Dell          | XPS 13 9370                 | [e94228e06b](https://linux-hardware.org/?probe=e94228e06b) | Feb 22, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [416de2c634](https://linux-hardware.org/?probe=416de2c634) | Feb 21, 2024 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [b8151c46bb](https://linux-hardware.org/?probe=b8151c46bb) | Feb 20, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [3260a2265c](https://linux-hardware.org/?probe=3260a2265c) | Feb 18, 2024 |
| HP            | EliteBook 850 G2            | [a398d0bc5e](https://linux-hardware.org/?probe=a398d0bc5e) | Feb 16, 2024 |
| Google        | Berknip                     | [cab3f6a686](https://linux-hardware.org/?probe=cab3f6a686) | Feb 13, 2024 |
| Dell          | XPS 13 9370                 | [11b5a42b88](https://linux-hardware.org/?probe=11b5a42b88) | Feb 11, 2024 |
| Google        | Berknip                     | [b39f5eec0b](https://linux-hardware.org/?probe=b39f5eec0b) | Feb 11, 2024 |
| HP            | ENVY Laptop 16-h1xxx        | [5690cf9537](https://linux-hardware.org/?probe=5690cf9537) | Feb 10, 2024 |
| ASUSTek       | G750JM                      | [91c1ae83cb](https://linux-hardware.org/?probe=91c1ae83cb) | Feb 10, 2024 |
| HP            | ZBook Studio G5             | [ac8738f9d5](https://linux-hardware.org/?probe=ac8738f9d5) | Feb 09, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [6700a2fd4d](https://linux-hardware.org/?probe=6700a2fd4d) | Feb 09, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [238b0e7660](https://linux-hardware.org/?probe=238b0e7660) | Feb 09, 2024 |
| ASUSTek       | K54C                        | [56b8a644da](https://linux-hardware.org/?probe=56b8a644da) | Feb 08, 2024 |
| ASUSTek       | X550VC                      | [424775f910](https://linux-hardware.org/?probe=424775f910) | Feb 07, 2024 |
| Dell          | G15 5520                    | [1e1e027895](https://linux-hardware.org/?probe=1e1e027895) | Feb 07, 2024 |
| HP            | Laptop 14s-fq0xxx           | [6ae9e4d70e](https://linux-hardware.org/?probe=6ae9e4d70e) | Feb 06, 2024 |
| Dell          | Vostro 3525                 | [655a24d376](https://linux-hardware.org/?probe=655a24d376) | Feb 06, 2024 |
| Dell          | Vostro 3525                 | [7c0c3cb665](https://linux-hardware.org/?probe=7c0c3cb665) | Feb 06, 2024 |
| Dell          | Latitude E5430 non-vPro     | [3d2ef5ec7e](https://linux-hardware.org/?probe=3d2ef5ec7e) | Feb 05, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b663434440](https://linux-hardware.org/?probe=b663434440) | Feb 04, 2024 |
| ASUSTek       | X550VC                      | [274a4704a0](https://linux-hardware.org/?probe=274a4704a0) | Feb 02, 2024 |
| ASUSTek       | ROG Strix G634JZ_G634JZ     | [4b8399084a](https://linux-hardware.org/?probe=4b8399084a) | Feb 01, 2024 |
| Acer          | Nitro AN515-58              | [84c37d0192](https://linux-hardware.org/?probe=84c37d0192) | Feb 01, 2024 |
| HP            | Elite x2 1012 G1            | [44bbb3b748](https://linux-hardware.org/?probe=44bbb3b748) | Jan 31, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [16922386a7](https://linux-hardware.org/?probe=16922386a7) | Jan 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [028ce3b254](https://linux-hardware.org/?probe=028ce3b254) | Jan 29, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [91fddd3173](https://linux-hardware.org/?probe=91fddd3173) | Jan 28, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [f05cba633f](https://linux-hardware.org/?probe=f05cba633f) | Jan 28, 2024 |
| ASUSTek       | N551JX                      | [6a0be842aa](https://linux-hardware.org/?probe=6a0be842aa) | Jan 27, 2024 |
| Dell          | Inspiron N5040              | [7cd09c7dde](https://linux-hardware.org/?probe=7cd09c7dde) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [81338699ce](https://linux-hardware.org/?probe=81338699ce) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [9f021a2102](https://linux-hardware.org/?probe=9f021a2102) | Jan 25, 2024 |
| Acer          | Aspire E1-572G              | [d94fb0b47b](https://linux-hardware.org/?probe=d94fb0b47b) | Jan 24, 2024 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [4b9301ae7f](https://linux-hardware.org/?probe=4b9301ae7f) | Jan 24, 2024 |
| Acer          | Aspire A315-35              | [40bb0f1f4d](https://linux-hardware.org/?probe=40bb0f1f4d) | Jan 24, 2024 |
| Dell          | Inspiron N5040              | [79bca2224b](https://linux-hardware.org/?probe=79bca2224b) | Jan 24, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [318e16ffb6](https://linux-hardware.org/?probe=318e16ffb6) | Jan 22, 2024 |
| Acer          | Aspire SW3-016              | [01ee7724e0](https://linux-hardware.org/?probe=01ee7724e0) | Jan 21, 2024 |
| Acer          | Aspire A315-35              | [baff1b7c03](https://linux-hardware.org/?probe=baff1b7c03) | Jan 20, 2024 |
| Acer          | Aspire A315-35              | [dafaf99dd0](https://linux-hardware.org/?probe=dafaf99dd0) | Jan 19, 2024 |
| Dell          | Latitude E6230              | [421a0c04cf](https://linux-hardware.org/?probe=421a0c04cf) | Jan 19, 2024 |
| Dell          | Latitude E6230              | [c5602b88c7](https://linux-hardware.org/?probe=c5602b88c7) | Jan 18, 2024 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [ca16a763c8](https://linux-hardware.org/?probe=ca16a763c8) | Jan 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [5ea527f9cc](https://linux-hardware.org/?probe=5ea527f9cc) | Jan 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [3c8a40dcc2](https://linux-hardware.org/?probe=3c8a40dcc2) | Jan 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [4a57c65ec3](https://linux-hardware.org/?probe=4a57c65ec3) | Jan 15, 2024 |
| Lenovo        | ThinkPad T440 20B7S1WJ00    | [215c45abef](https://linux-hardware.org/?probe=215c45abef) | Jan 11, 2024 |
| HP            | Laptop 15s-fq1xxx           | [9960b657ec](https://linux-hardware.org/?probe=9960b657ec) | Jan 11, 2024 |
| HP            | Laptop 15s-fq1xxx           | [d1041fde50](https://linux-hardware.org/?probe=d1041fde50) | Jan 11, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [a4897703b1](https://linux-hardware.org/?probe=a4897703b1) | Jan 10, 2024 |
| Complet       | MY8315XX                    | [cb08af3409](https://linux-hardware.org/?probe=cb08af3409) | Jan 07, 2024 |
| HP            | Pavilion Laptop 15-eg3xx... | [61066d4150](https://linux-hardware.org/?probe=61066d4150) | Jan 07, 2024 |
| Lenovo        | ThinkPad T480s 20L8S0R30... | [9cfe296019](https://linux-hardware.org/?probe=9cfe296019) | Jan 07, 2024 |
| HP            | 250 G7 Notebook PC          | [7f25d85205](https://linux-hardware.org/?probe=7f25d85205) | Jan 07, 2024 |
| Sony          | SVF1521H1EW                 | [1939183179](https://linux-hardware.org/?probe=1939183179) | Jan 07, 2024 |
| Sony          | SVF1521H1EW                 | [f73763fd0c](https://linux-hardware.org/?probe=f73763fd0c) | Jan 06, 2024 |
| Lenovo        | ThinkPad T410 2518FMG       | [d2e50fca98](https://linux-hardware.org/?probe=d2e50fca98) | Jan 03, 2024 |
| Lenovo        | ThinkPad T410 2518FMG       | [e1d4b75f1c](https://linux-hardware.org/?probe=e1d4b75f1c) | Jan 03, 2024 |
| HUAWEI        | KLVL-WXX9                   | [28ad8513b4](https://linux-hardware.org/?probe=28ad8513b4) | Dec 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [8f3ab867ea](https://linux-hardware.org/?probe=8f3ab867ea) | Dec 30, 2023 |
| MSI           | GP75 Leopard 9SE            | [29e0740b9d](https://linux-hardware.org/?probe=29e0740b9d) | Dec 29, 2023 |
| Fujitsu       | LIFEBOOK T902               | [050f6ca09e](https://linux-hardware.org/?probe=050f6ca09e) | Dec 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [58080b01c8](https://linux-hardware.org/?probe=58080b01c8) | Dec 27, 2023 |
| ASUSTek       | G750JM                      | [fcda025864](https://linux-hardware.org/?probe=fcda025864) | Dec 26, 2023 |
| Acer          | Aspire A315-35              | [a3c4869087](https://linux-hardware.org/?probe=a3c4869087) | Dec 24, 2023 |
| ASUSTek       | G750JM                      | [e53cfaf52c](https://linux-hardware.org/?probe=e53cfaf52c) | Dec 24, 2023 |
| Acer          | Aspire 5742Z                | [ddf1553f4b](https://linux-hardware.org/?probe=ddf1553f4b) | Dec 24, 2023 |
| HP            | EliteBook 840 G5            | [6406b552c4](https://linux-hardware.org/?probe=6406b552c4) | Dec 23, 2023 |
| Allview       | Allbook I/1                 | [960dfde4cd](https://linux-hardware.org/?probe=960dfde4cd) | Dec 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [9e521ad3e9](https://linux-hardware.org/?probe=9e521ad3e9) | Dec 22, 2023 |
| Acer          | Aspire A315-35              | [52af26d8a1](https://linux-hardware.org/?probe=52af26d8a1) | Dec 21, 2023 |
| HP            | EliteBook 840 G6            | [64ec373e84](https://linux-hardware.org/?probe=64ec373e84) | Dec 20, 2023 |
| Lenovo        | Legion 5 15IMH6 82NL        | [e54630a5d8](https://linux-hardware.org/?probe=e54630a5d8) | Dec 18, 2023 |
| Dell          | Vostro 15 3515              | [baf5b47a47](https://linux-hardware.org/?probe=baf5b47a47) | Dec 18, 2023 |
| ASUSTek       | X541UVK                     | [a6ae535887](https://linux-hardware.org/?probe=a6ae535887) | Dec 18, 2023 |
| Lenovo        | ThinkPad P52 20MAS19500     | [7067fb02ed](https://linux-hardware.org/?probe=7067fb02ed) | Dec 18, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [8507460974](https://linux-hardware.org/?probe=8507460974) | Dec 18, 2023 |
| PC Special... | MP 17 Recoil Master         | [f199dc6e36](https://linux-hardware.org/?probe=f199dc6e36) | Dec 17, 2023 |
| Toshiba       | Satellite C50-A-1HF         | [ac7985ff69](https://linux-hardware.org/?probe=ac7985ff69) | Dec 17, 2023 |
| Dell          | Inspiron 5559               | [6920e9d7c2](https://linux-hardware.org/?probe=6920e9d7c2) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [6d72d7366b](https://linux-hardware.org/?probe=6d72d7366b) | Dec 15, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [d8a98a209a](https://linux-hardware.org/?probe=d8a98a209a) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c839de638b](https://linux-hardware.org/?probe=c839de638b) | Dec 15, 2023 |
| Acer          | Aspire A315-35              | [f7b0d4b746](https://linux-hardware.org/?probe=f7b0d4b746) | Dec 14, 2023 |
| HP            | Pavilion dv6500             | [cdde8c0b3f](https://linux-hardware.org/?probe=cdde8c0b3f) | Dec 13, 2023 |
| Lenovo        | Z710 20250                  | [0ffc45c096](https://linux-hardware.org/?probe=0ffc45c096) | Dec 13, 2023 |
| HP            | Laptop 15-fc0xxx            | [0ad101e0f2](https://linux-hardware.org/?probe=0ad101e0f2) | Dec 12, 2023 |
| HP            | Presario CQ58               | [b23d694ab4](https://linux-hardware.org/?probe=b23d694ab4) | Dec 11, 2023 |
| Dell          | Precision 5530              | [eee9114e4b](https://linux-hardware.org/?probe=eee9114e4b) | Dec 10, 2023 |
| Acer          | Aspire E5-575G              | [48fffc72b6](https://linux-hardware.org/?probe=48fffc72b6) | Dec 10, 2023 |
| ASUSTek       | X550VC                      | [e2c932c285](https://linux-hardware.org/?probe=e2c932c285) | Dec 09, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [baa82e571f](https://linux-hardware.org/?probe=baa82e571f) | Dec 09, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [551b412a34](https://linux-hardware.org/?probe=551b412a34) | Dec 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [587ff35c26](https://linux-hardware.org/?probe=587ff35c26) | Dec 08, 2023 |
| Dell          | Vostro 15 3515              | [0257ed619f](https://linux-hardware.org/?probe=0257ed619f) | Dec 08, 2023 |
| Lenovo        | Z50-70 20354                | [ba354037ff](https://linux-hardware.org/?probe=ba354037ff) | Dec 07, 2023 |
| Acer          | TravelMate P645-S           | [e44f06b326](https://linux-hardware.org/?probe=e44f06b326) | Dec 07, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [46bc5ee727](https://linux-hardware.org/?probe=46bc5ee727) | Dec 06, 2023 |
| Acer          | Aspire A314-23P             | [ad97d6f3c6](https://linux-hardware.org/?probe=ad97d6f3c6) | Dec 05, 2023 |
| HP            | 550                         | [a3dc2d4062](https://linux-hardware.org/?probe=a3dc2d4062) | Dec 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [8463f6c28f](https://linux-hardware.org/?probe=8463f6c28f) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [f8a528e1d6](https://linux-hardware.org/?probe=f8a528e1d6) | Dec 03, 2023 |
| Acer          | Aspire 8951G                | [f98b449dba](https://linux-hardware.org/?probe=f98b449dba) | Dec 03, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [20a5a6a137](https://linux-hardware.org/?probe=20a5a6a137) | Dec 03, 2023 |
| Lenovo        | IdeaPad Slim 5 14IRL8 82... | [49c0a7990e](https://linux-hardware.org/?probe=49c0a7990e) | Dec 01, 2023 |
| Acer          | Aspire ES1-523              | [10c0db94d1](https://linux-hardware.org/?probe=10c0db94d1) | Nov 29, 2023 |
| Dell          | Inspiron N5030              | [cf3da3211d](https://linux-hardware.org/?probe=cf3da3211d) | Nov 28, 2023 |
| MSI           | GP75 Leopard 9SE            | [60c7835d8c](https://linux-hardware.org/?probe=60c7835d8c) | Nov 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [5fabcb33c4](https://linux-hardware.org/?probe=5fabcb33c4) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [0ddcbc9eb9](https://linux-hardware.org/?probe=0ddcbc9eb9) | Nov 27, 2023 |
| Lenovo        | 15ARE05 81W4                | [c3763733da](https://linux-hardware.org/?probe=c3763733da) | Nov 27, 2023 |
| Lenovo        | 15ARE05 81W4                | [4fa9ab8a76](https://linux-hardware.org/?probe=4fa9ab8a76) | Nov 27, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [c887e86fe4](https://linux-hardware.org/?probe=c887e86fe4) | Nov 25, 2023 |
| Dell          | Latitude 7400               | [86a9de8212](https://linux-hardware.org/?probe=86a9de8212) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [7478563980](https://linux-hardware.org/?probe=7478563980) | Nov 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a8b99ab7f3](https://linux-hardware.org/?probe=a8b99ab7f3) | Nov 23, 2023 |
| Acer          | Aspire A315-35              | [6115c9c76e](https://linux-hardware.org/?probe=6115c9c76e) | Nov 23, 2023 |
| Valve         | Jupiter                     | [0454a567a0](https://linux-hardware.org/?probe=0454a567a0) | Nov 21, 2023 |
| Dell          | Vostro 3525                 | [2995eb87c1](https://linux-hardware.org/?probe=2995eb87c1) | Nov 21, 2023 |
| Acer          | Aspire A315-35              | [78dac027a1](https://linux-hardware.org/?probe=78dac027a1) | Nov 19, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [cc9d93b28f](https://linux-hardware.org/?probe=cc9d93b28f) | Nov 19, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [f5c9812962](https://linux-hardware.org/?probe=f5c9812962) | Nov 19, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [6e4144386d](https://linux-hardware.org/?probe=6e4144386d) | Nov 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [55df37c5d0](https://linux-hardware.org/?probe=55df37c5d0) | Nov 17, 2023 |
| HP            | EliteBook 735 G5            | [49ea9a3b35](https://linux-hardware.org/?probe=49ea9a3b35) | Nov 15, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [ffc320e32c](https://linux-hardware.org/?probe=ffc320e32c) | Nov 15, 2023 |
| Dell          | Latitude 5521               | [2cd2e72764](https://linux-hardware.org/?probe=2cd2e72764) | Nov 15, 2023 |
| Lenovo        | IdeaPad Slim 5 14IAH8 83... | [e33ce14e30](https://linux-hardware.org/?probe=e33ce14e30) | Nov 14, 2023 |
| Dell          | XPS 15 7590                 | [da50e3550f](https://linux-hardware.org/?probe=da50e3550f) | Nov 14, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [e8803a2d63](https://linux-hardware.org/?probe=e8803a2d63) | Nov 13, 2023 |
| Allview       | Allbook I/1                 | [2da284e5a6](https://linux-hardware.org/?probe=2da284e5a6) | Nov 11, 2023 |
| Jumper        | EZbook                      | [f7f10f7817](https://linux-hardware.org/?probe=f7f10f7817) | Nov 11, 2023 |
| Allview       | Allbook I/1                 | [4ea9038785](https://linux-hardware.org/?probe=4ea9038785) | Nov 10, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [ea4a2b9084](https://linux-hardware.org/?probe=ea4a2b9084) | Nov 07, 2023 |
| Acer          | Aspire A315-35              | [61fdbe9ec2](https://linux-hardware.org/?probe=61fdbe9ec2) | Nov 07, 2023 |
| ASUSTek       | G750JS                      | [b64eb3798d](https://linux-hardware.org/?probe=b64eb3798d) | Nov 07, 2023 |
| ASUSTek       | N552VW                      | [b8f226f7f0](https://linux-hardware.org/?probe=b8f226f7f0) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [ce00056643](https://linux-hardware.org/?probe=ce00056643) | Nov 07, 2023 |
| Acer          | Aspire A314-23P             | [1e3cdf0bf2](https://linux-hardware.org/?probe=1e3cdf0bf2) | Nov 04, 2023 |
| Dell          | Vostro 3525                 | [48103e7e91](https://linux-hardware.org/?probe=48103e7e91) | Nov 03, 2023 |
| Dell          | Latitude 7370               | [b16724db59](https://linux-hardware.org/?probe=b16724db59) | Nov 01, 2023 |
| Google        | Akemi                       | [75082d5cf9](https://linux-hardware.org/?probe=75082d5cf9) | Nov 01, 2023 |
| ASUSTek       | X541UAK                     | [d4630a5c8b](https://linux-hardware.org/?probe=d4630a5c8b) | Nov 01, 2023 |
| Acer          | Aspire A315-35              | [c26ec81fab](https://linux-hardware.org/?probe=c26ec81fab) | Oct 31, 2023 |
| HP            | 255 G8 Notebook PC          | [941ca289ce](https://linux-hardware.org/?probe=941ca289ce) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9f0452aba6](https://linux-hardware.org/?probe=9f0452aba6) | Oct 29, 2023 |
| ASUSTek       | G750JM                      | [01e0620386](https://linux-hardware.org/?probe=01e0620386) | Oct 29, 2023 |
| ASUSTek       | G56JR                       | [8e871997f7](https://linux-hardware.org/?probe=8e871997f7) | Oct 29, 2023 |
| ASUSTek       | G56JR                       | [f8e77bd53a](https://linux-hardware.org/?probe=f8e77bd53a) | Oct 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S5FF0S    | [4a4fe99b2d](https://linux-hardware.org/?probe=4a4fe99b2d) | Oct 23, 2023 |
| Dell          | XPS 13 9370                 | [f45a5143fc](https://linux-hardware.org/?probe=f45a5143fc) | Oct 23, 2023 |
| ASUSTek       | ZenBook UX534FTC            | [a268a7a10e](https://linux-hardware.org/?probe=a268a7a10e) | Oct 22, 2023 |
| Acer          | Aspire A315-35              | [ee15c1dbea](https://linux-hardware.org/?probe=ee15c1dbea) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [77fb62615e](https://linux-hardware.org/?probe=77fb62615e) | Oct 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [43f9375597](https://linux-hardware.org/?probe=43f9375597) | Oct 21, 2023 |
| ASUSTek       | G750JM                      | [0f5885bc27](https://linux-hardware.org/?probe=0f5885bc27) | Oct 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9f9777f778](https://linux-hardware.org/?probe=9f9777f778) | Oct 17, 2023 |
| Lenovo        | 15ARE05 81W4                | [dcb09acd04](https://linux-hardware.org/?probe=dcb09acd04) | Oct 17, 2023 |
| ASUSTek       | X556UQK                     | [c430358d6a](https://linux-hardware.org/?probe=c430358d6a) | Oct 17, 2023 |
| Toshiba       | Satellite C660              | [b96d2e0be9](https://linux-hardware.org/?probe=b96d2e0be9) | Oct 16, 2023 |
| HP            | 2000                        | [c2669ff6cb](https://linux-hardware.org/?probe=c2669ff6cb) | Oct 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [471a6f3119](https://linux-hardware.org/?probe=471a6f3119) | Oct 16, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [f16973062f](https://linux-hardware.org/?probe=f16973062f) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [66a5a05425](https://linux-hardware.org/?probe=66a5a05425) | Oct 15, 2023 |
| Toshiba       | Satellite CL10-C-102        | [cdaab4e230](https://linux-hardware.org/?probe=cdaab4e230) | Oct 15, 2023 |
| Acer          | Aspire A515-57              | [ca520343c8](https://linux-hardware.org/?probe=ca520343c8) | Oct 13, 2023 |
| Lenovo        | 15ARE05 81W4                | [c0066cda83](https://linux-hardware.org/?probe=c0066cda83) | Oct 13, 2023 |
| HP            | 470 17 inch G9              | [d138f8f9f3](https://linux-hardware.org/?probe=d138f8f9f3) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [662b033cee](https://linux-hardware.org/?probe=662b033cee) | Oct 12, 2023 |
| Acer          | Aspire A315-35              | [3069c746fd](https://linux-hardware.org/?probe=3069c746fd) | Oct 12, 2023 |
| BESSTAR Te... | X400                        | [c955c44ef3](https://linux-hardware.org/?probe=c955c44ef3) | Oct 10, 2023 |
| Dell          | Vostro 3525                 | [cb78c82e7a](https://linux-hardware.org/?probe=cb78c82e7a) | Oct 09, 2023 |
| Lenovo        | G580 20150                  | [fa47449843](https://linux-hardware.org/?probe=fa47449843) | Oct 08, 2023 |
| Dell          | Vostro 3525                 | [cad844c720](https://linux-hardware.org/?probe=cad844c720) | Oct 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [60d5b8f4c0](https://linux-hardware.org/?probe=60d5b8f4c0) | Oct 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [99f8282319](https://linux-hardware.org/?probe=99f8282319) | Oct 06, 2023 |
| HP            | ProBook 6450b               | [f597cfe9d1](https://linux-hardware.org/?probe=f597cfe9d1) | Oct 05, 2023 |
| Google        | Magpie                      | [91fa583b13](https://linux-hardware.org/?probe=91fa583b13) | Oct 05, 2023 |
| HP            | OMEN by Laptop 17-an0xx     | [02ff66cc0c](https://linux-hardware.org/?probe=02ff66cc0c) | Oct 05, 2023 |
| Acer          | Aspire V5-531               | [555d578f86](https://linux-hardware.org/?probe=555d578f86) | Oct 05, 2023 |
| Dell          | Latitude E6420              | [504010f96c](https://linux-hardware.org/?probe=504010f96c) | Oct 04, 2023 |
| Acer          | Aspire V5-531               | [b6a9eaaec5](https://linux-hardware.org/?probe=b6a9eaaec5) | Oct 03, 2023 |
| Acer          | Aspire A715-51G             | [6bc4edfef5](https://linux-hardware.org/?probe=6bc4edfef5) | Oct 02, 2023 |
| Acer          | Aspire A715-51G             | [a9b3098036](https://linux-hardware.org/?probe=a9b3098036) | Oct 02, 2023 |
| Google        | Magpie                      | [32a7bba307](https://linux-hardware.org/?probe=32a7bba307) | Oct 01, 2023 |
| HP            | 470 17 inch G9              | [c6043cc6cc](https://linux-hardware.org/?probe=c6043cc6cc) | Oct 01, 2023 |
| Toshiba       | Satellite C850-D4K          | [47d93b3030](https://linux-hardware.org/?probe=47d93b3030) | Oct 01, 2023 |
| HUAWEI        | NBD-WXX9                    | [c8a525522f](https://linux-hardware.org/?probe=c8a525522f) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fb4cde69b8](https://linux-hardware.org/?probe=fb4cde69b8) | Sep 28, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | [a1e01ab80d](https://linux-hardware.org/?probe=a1e01ab80d) | Sep 25, 2023 |
| ASUSTek       | K53TK                       | [65e95a03e9](https://linux-hardware.org/?probe=65e95a03e9) | Sep 22, 2023 |
| ASUSTek       | K53TK                       | [34857762c0](https://linux-hardware.org/?probe=34857762c0) | Sep 21, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [45f00aaf92](https://linux-hardware.org/?probe=45f00aaf92) | Sep 21, 2023 |
| Dell          | Latitude 5420               | [c40b9df526](https://linux-hardware.org/?probe=c40b9df526) | Sep 21, 2023 |
| Dell          | Latitude 5420               | [9caba9ee44](https://linux-hardware.org/?probe=9caba9ee44) | Sep 21, 2023 |
| MSI           | GP75 Leopard 9SE            | [07431109a7](https://linux-hardware.org/?probe=07431109a7) | Sep 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [365a5e674f](https://linux-hardware.org/?probe=365a5e674f) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [eaa723190d](https://linux-hardware.org/?probe=eaa723190d) | Sep 15, 2023 |
| Acer          | Aspire A315-35              | [356d6d3e13](https://linux-hardware.org/?probe=356d6d3e13) | Sep 15, 2023 |
| Acer          | Aspire A315-35              | [7ae470ffa8](https://linux-hardware.org/?probe=7ae470ffa8) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [d27fa5404b](https://linux-hardware.org/?probe=d27fa5404b) | Sep 14, 2023 |
| Acer          | Nitro AN515-58              | [78a9c8ba47](https://linux-hardware.org/?probe=78a9c8ba47) | Sep 12, 2023 |
| Acer          | Nitro AN515-58              | [a8f64806fe](https://linux-hardware.org/?probe=a8f64806fe) | Sep 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e1b135961f](https://linux-hardware.org/?probe=e1b135961f) | Sep 12, 2023 |
| ASUSTek       | X550VX                      | [b1b59ca70c](https://linux-hardware.org/?probe=b1b59ca70c) | Sep 10, 2023 |
| HP            | ProBook 6570b               | [f66ec50e55](https://linux-hardware.org/?probe=f66ec50e55) | Sep 05, 2023 |
| HP            | ProBook 6570b               | [9a31047350](https://linux-hardware.org/?probe=9a31047350) | Sep 05, 2023 |
| Acer          | Nitro AN515-41              | [8d55fa5be4](https://linux-hardware.org/?probe=8d55fa5be4) | Sep 03, 2023 |
| HP            | 15                          | [db9d960b39](https://linux-hardware.org/?probe=db9d960b39) | Sep 03, 2023 |
| HP            | 250 G5 Notebook PC          | [66df65e0f0](https://linux-hardware.org/?probe=66df65e0f0) | Sep 02, 2023 |
| Toshiba       | Satellite C660              | [d3c3b72e39](https://linux-hardware.org/?probe=d3c3b72e39) | Sep 01, 2023 |
| Acer          | TMP645-M                    | [17838ce9b0](https://linux-hardware.org/?probe=17838ce9b0) | Aug 30, 2023 |
| ASUSTek       | G750JM                      | [ca4dd5a11e](https://linux-hardware.org/?probe=ca4dd5a11e) | Aug 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d036282290](https://linux-hardware.org/?probe=d036282290) | Aug 29, 2023 |
| ASUSTek       | X550LD                      | [b866599fbc](https://linux-hardware.org/?probe=b866599fbc) | Aug 29, 2023 |
| MSI           | GP75 Leopard 9SE            | [a8a97f9555](https://linux-hardware.org/?probe=a8a97f9555) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | [c4be1d7e95](https://linux-hardware.org/?probe=c4be1d7e95) | Aug 27, 2023 |
| MSI           | GP75 Leopard 9SE            | [db9336b4db](https://linux-hardware.org/?probe=db9336b4db) | Aug 26, 2023 |
| ASUSTek       | K73SV                       | [7aca2d97c0](https://linux-hardware.org/?probe=7aca2d97c0) | Aug 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b3f1d927a1](https://linux-hardware.org/?probe=b3f1d927a1) | Aug 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d7b6d2a997](https://linux-hardware.org/?probe=d7b6d2a997) | Aug 21, 2023 |
| Acer          | Aspire A315-59              | [8946b925ea](https://linux-hardware.org/?probe=8946b925ea) | Aug 18, 2023 |
| Acer          | Aspire ES1-311              | [3fa65d407a](https://linux-hardware.org/?probe=3fa65d407a) | Aug 17, 2023 |
| HP            | Compaq 6710b (FG040EC#AB... | [a0cd8c1b40](https://linux-hardware.org/?probe=a0cd8c1b40) | Aug 16, 2023 |
| Toshiba       | Satellite C660              | [8bc67959d1](https://linux-hardware.org/?probe=8bc67959d1) | Aug 16, 2023 |
| ASUSTek       | GL552JX                     | [9594a231bd](https://linux-hardware.org/?probe=9594a231bd) | Aug 16, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | [f0d90b715d](https://linux-hardware.org/?probe=f0d90b715d) | Aug 15, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [18d3d9a7c1](https://linux-hardware.org/?probe=18d3d9a7c1) | Aug 14, 2023 |
| Allview       | Allbook H                   | [1a8e5e7f8f](https://linux-hardware.org/?probe=1a8e5e7f8f) | Aug 13, 2023 |
| HP            | Pavilion Notebook           | [7fd3205fde](https://linux-hardware.org/?probe=7fd3205fde) | Aug 11, 2023 |
| ASUSTek       | X541UVK                     | [77ec1f7364](https://linux-hardware.org/?probe=77ec1f7364) | Aug 09, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [ce593ff6c7](https://linux-hardware.org/?probe=ce593ff6c7) | Aug 07, 2023 |
| Acer          | AO756                       | [60475c9d52](https://linux-hardware.org/?probe=60475c9d52) | Aug 06, 2023 |
| WEIGO         | CDA-141AU                   | [35c705bd70](https://linux-hardware.org/?probe=35c705bd70) | Aug 05, 2023 |
| HP            | Laptop 14s-fq0xxx           | [0a7b2a3fcc](https://linux-hardware.org/?probe=0a7b2a3fcc) | Aug 03, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [9171e8e6b9](https://linux-hardware.org/?probe=9171e8e6b9) | Aug 03, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [8de1f944a7](https://linux-hardware.org/?probe=8de1f944a7) | Jul 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [d1bf55b135](https://linux-hardware.org/?probe=d1bf55b135) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ea8a893b11](https://linux-hardware.org/?probe=ea8a893b11) | Jul 29, 2023 |
| Lenovo        | ThinkPad W541 20EFS00N00    | [c9f80b56fc](https://linux-hardware.org/?probe=c9f80b56fc) | Jul 28, 2023 |
| ASUSTek       | X540LJ                      | [798cadd754](https://linux-hardware.org/?probe=798cadd754) | Jul 25, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [e9a58d14e7](https://linux-hardware.org/?probe=e9a58d14e7) | Jul 20, 2023 |
| Dell          | Latitude 5590               | [93857a3b66](https://linux-hardware.org/?probe=93857a3b66) | Jul 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [dac4434339](https://linux-hardware.org/?probe=dac4434339) | Jul 18, 2023 |
| HP            | ProBook 450 G5              | [3dfd41fda9](https://linux-hardware.org/?probe=3dfd41fda9) | Jul 17, 2023 |
| HP            | ProBook 450 G5              | [c5bee4d8fe](https://linux-hardware.org/?probe=c5bee4d8fe) | Jul 17, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [501969ed00](https://linux-hardware.org/?probe=501969ed00) | Jul 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [052b5c1741](https://linux-hardware.org/?probe=052b5c1741) | Jul 12, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [9fc68063e3](https://linux-hardware.org/?probe=9fc68063e3) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [f35543549c](https://linux-hardware.org/?probe=f35543549c) | Jul 11, 2023 |
| Unknown       | HP Chromebook 14            | [63b183aa51](https://linux-hardware.org/?probe=63b183aa51) | Jul 11, 2023 |
| Fujitsu       | LIFEBOOK LH532              | [3cad86057a](https://linux-hardware.org/?probe=3cad86057a) | Jul 09, 2023 |
| Lenovo        | V145-15AST 81MT             | [a29509646a](https://linux-hardware.org/?probe=a29509646a) | Jul 08, 2023 |
| Dell          | Latitude 3500               | [38a0d6b099](https://linux-hardware.org/?probe=38a0d6b099) | Jul 08, 2023 |
| Dell          | Studio 1749                 | [fe1e5d7b8f](https://linux-hardware.org/?probe=fe1e5d7b8f) | Jul 05, 2023 |
| HP            | OMEN by Laptop 17-cb1xxx    | [dbf87e0eec](https://linux-hardware.org/?probe=dbf87e0eec) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8862b2d8db](https://linux-hardware.org/?probe=8862b2d8db) | Jun 25, 2023 |
| Acer          | Aspire A517-51G             | [dc2aebbc48](https://linux-hardware.org/?probe=dc2aebbc48) | Jun 24, 2023 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | [a74b5c2880](https://linux-hardware.org/?probe=a74b5c2880) | Jun 24, 2023 |
| Acer          | Aspire A315-58G             | [ea2b8a58b1](https://linux-hardware.org/?probe=ea2b8a58b1) | Jun 22, 2023 |
| Acer          | Swift SF314-52G             | [4eab971a60](https://linux-hardware.org/?probe=4eab971a60) | Jun 21, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [1c9456fd1d](https://linux-hardware.org/?probe=1c9456fd1d) | Jun 20, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [530f6272c9](https://linux-hardware.org/?probe=530f6272c9) | Jun 20, 2023 |
| ASUSTek       | G750JM                      | [928b30815b](https://linux-hardware.org/?probe=928b30815b) | Jun 18, 2023 |
| Acer          | Aspire A315-33              | [c6a929a9ec](https://linux-hardware.org/?probe=c6a929a9ec) | Jun 17, 2023 |
| Acer          | Aspire A315-33              | [d72b8e616f](https://linux-hardware.org/?probe=d72b8e616f) | Jun 17, 2023 |
| Acer          | Aspire A715-71G             | [0ef00ccccc](https://linux-hardware.org/?probe=0ef00ccccc) | Jun 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [2346d706e3](https://linux-hardware.org/?probe=2346d706e3) | Jun 15, 2023 |
| Dell          | Inspiron 5505               | [7747deeb57](https://linux-hardware.org/?probe=7747deeb57) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [e073b99b63](https://linux-hardware.org/?probe=e073b99b63) | Jun 13, 2023 |
| ASUSTek       | G750JM                      | [e722fda49e](https://linux-hardware.org/?probe=e722fda49e) | Jun 13, 2023 |
| MSI           | GP75 Leopard 9SE            | [9e763f2e63](https://linux-hardware.org/?probe=9e763f2e63) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b7ab29fbb5](https://linux-hardware.org/?probe=b7ab29fbb5) | Jun 06, 2023 |
| MSI           | GP75 Leopard 9SE            | [05530e670e](https://linux-hardware.org/?probe=05530e670e) | Jun 06, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ea07821e39](https://linux-hardware.org/?probe=ea07821e39) | Jun 05, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [1285aacf1b](https://linux-hardware.org/?probe=1285aacf1b) | Jun 04, 2023 |
| ASUSTek       | Zenbook UM5401RA_RM5401R... | [763a52f3e8](https://linux-hardware.org/?probe=763a52f3e8) | Jun 03, 2023 |
| HP            | ENVY 17                     | [79fd438f05](https://linux-hardware.org/?probe=79fd438f05) | Jun 03, 2023 |
| Dell          | Vostro 1015                 | [055866f703](https://linux-hardware.org/?probe=055866f703) | Jun 02, 2023 |
| Dell          | Inspiron 5567               | [bd3a6c5bd8](https://linux-hardware.org/?probe=bd3a6c5bd8) | Jun 02, 2023 |
| Acer          | Aspire A517-51G             | [dc0e29f0bb](https://linux-hardware.org/?probe=dc0e29f0bb) | Jun 02, 2023 |
| Acer          | Aspire A517-51G             | [693005f5b4](https://linux-hardware.org/?probe=693005f5b4) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [1f18cef2df](https://linux-hardware.org/?probe=1f18cef2df) | Jun 01, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [7ae3edd73e](https://linux-hardware.org/?probe=7ae3edd73e) | Jun 01, 2023 |
| Acer          | Aspire A515-45              | [f93dd394e8](https://linux-hardware.org/?probe=f93dd394e8) | May 31, 2023 |
| Dell          | Vostro 15 3515              | [6bec5a03df](https://linux-hardware.org/?probe=6bec5a03df) | May 30, 2023 |
| Dell          | Latitude E6440              | [821e3e3246](https://linux-hardware.org/?probe=821e3e3246) | May 27, 2023 |
| HP            | Laptop 17-cn0xxx            | [c8c9f63237](https://linux-hardware.org/?probe=c8c9f63237) | May 25, 2023 |
| Dell          | G15 5510                    | [325fcf6e78](https://linux-hardware.org/?probe=325fcf6e78) | May 25, 2023 |
| HP            | ProBook 6440b               | [5ed14b01a3](https://linux-hardware.org/?probe=5ed14b01a3) | May 25, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [61b85cdced](https://linux-hardware.org/?probe=61b85cdced) | May 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [b167237d46](https://linux-hardware.org/?probe=b167237d46) | May 24, 2023 |
| Valve         | Jupiter                     | [117db8031d](https://linux-hardware.org/?probe=117db8031d) | May 24, 2023 |
| Dell          | Precision 7540              | [65605ee5e8](https://linux-hardware.org/?probe=65605ee5e8) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [a1e2fa6222](https://linux-hardware.org/?probe=a1e2fa6222) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | [504a24887e](https://linux-hardware.org/?probe=504a24887e) | May 24, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [cb3e4d2c2b](https://linux-hardware.org/?probe=cb3e4d2c2b) | May 24, 2023 |
| Allview       | Allbook H                   | [8b0c0a3436](https://linux-hardware.org/?probe=8b0c0a3436) | May 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [64ceddcdd4](https://linux-hardware.org/?probe=64ceddcdd4) | May 24, 2023 |
| Dell          | G15 5510                    | [730985e467](https://linux-hardware.org/?probe=730985e467) | May 24, 2023 |
| Dell          | Inspiron 1501               | [4703a17f03](https://linux-hardware.org/?probe=4703a17f03) | May 23, 2023 |
| MSI           | Modern 14 B10MW             | [319f4883aa](https://linux-hardware.org/?probe=319f4883aa) | May 22, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [ceeff309eb](https://linux-hardware.org/?probe=ceeff309eb) | May 18, 2023 |
| ASUSTek       | X541UAK                     | [00685614c4](https://linux-hardware.org/?probe=00685614c4) | May 16, 2023 |
| ASUSTek       | N76VZ                       | [fc6d34934a](https://linux-hardware.org/?probe=fc6d34934a) | May 14, 2023 |
| Razer         | Blade 15 Studio Edition ... | [f1884eebc6](https://linux-hardware.org/?probe=f1884eebc6) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [729a4181de](https://linux-hardware.org/?probe=729a4181de) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3010c8760e](https://linux-hardware.org/?probe=3010c8760e) | May 12, 2023 |
| Acer          | Extensa 5220                | [935b52f12c](https://linux-hardware.org/?probe=935b52f12c) | May 12, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [af96be2497](https://linux-hardware.org/?probe=af96be2497) | May 11, 2023 |
| Acer          | Aspire A515-45              | [8f9a64c245](https://linux-hardware.org/?probe=8f9a64c245) | May 08, 2023 |
| Dell          | Inspiron 11-3162            | [62813124bb](https://linux-hardware.org/?probe=62813124bb) | May 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [a312f0545f](https://linux-hardware.org/?probe=a312f0545f) | May 07, 2023 |
| Acer          | Aspire 5742G                | [2a321db63e](https://linux-hardware.org/?probe=2a321db63e) | May 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [85648a82df](https://linux-hardware.org/?probe=85648a82df) | May 06, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [af9c3172bc](https://linux-hardware.org/?probe=af9c3172bc) | May 05, 2023 |
| MSI           | GP75 Leopard 9SE            | [425ecbf896](https://linux-hardware.org/?probe=425ecbf896) | May 04, 2023 |
| ASUSTek       | 1001PX                      | [7a04e30859](https://linux-hardware.org/?probe=7a04e30859) | May 03, 2023 |
| HP            | Notebook                    | [c6316b5a64](https://linux-hardware.org/?probe=c6316b5a64) | May 03, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [7c56fae21c](https://linux-hardware.org/?probe=7c56fae21c) | May 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3b04b16c3e](https://linux-hardware.org/?probe=3b04b16c3e) | May 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1234a4cf5a](https://linux-hardware.org/?probe=1234a4cf5a) | May 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5101f4e19d](https://linux-hardware.org/?probe=5101f4e19d) | May 02, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [2a4cf994ac](https://linux-hardware.org/?probe=2a4cf994ac) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ed2a323b49](https://linux-hardware.org/?probe=ed2a323b49) | May 01, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [4607549f5a](https://linux-hardware.org/?probe=4607549f5a) | May 01, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [754b22a59c](https://linux-hardware.org/?probe=754b22a59c) | May 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d1b974c33a](https://linux-hardware.org/?probe=d1b974c33a) | May 01, 2023 |
| Acer          | Aspire 5110                 | [b43b059257](https://linux-hardware.org/?probe=b43b059257) | Apr 28, 2023 |
| Dell          | Vostro 15 3515              | [f58ab8b9c4](https://linux-hardware.org/?probe=f58ab8b9c4) | Apr 27, 2023 |
| Acer          | Aspire A515-57              | [86dad710fa](https://linux-hardware.org/?probe=86dad710fa) | Apr 26, 2023 |
| Acer          | Aspire A315-35              | [33fac6ec40](https://linux-hardware.org/?probe=33fac6ec40) | Apr 26, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [e7fb8c3e44](https://linux-hardware.org/?probe=e7fb8c3e44) | Apr 26, 2023 |
| ASUSTek       | K53SM                       | [92ac292547](https://linux-hardware.org/?probe=92ac292547) | Apr 24, 2023 |
| Acer          | Aspire V5-122P              | [baf567c71f](https://linux-hardware.org/?probe=baf567c71f) | Apr 23, 2023 |
| HP            | ProBook 450 G3              | [6e52b3ea77](https://linux-hardware.org/?probe=6e52b3ea77) | Apr 22, 2023 |
| Allview       | Allbook J                   | [96a3d7d3ef](https://linux-hardware.org/?probe=96a3d7d3ef) | Apr 22, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [3f01c5df6e](https://linux-hardware.org/?probe=3f01c5df6e) | Apr 21, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [a5ef39681b](https://linux-hardware.org/?probe=a5ef39681b) | Apr 21, 2023 |
| Allview       | Allbook J                   | [4ff8627338](https://linux-hardware.org/?probe=4ff8627338) | Apr 18, 2023 |
| Acer          | Aspire E5-575G              | [39afaea9e3](https://linux-hardware.org/?probe=39afaea9e3) | Apr 14, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | [0c4578a674](https://linux-hardware.org/?probe=0c4578a674) | Apr 14, 2023 |
| Dell          | Inspiron 1545               | [653a25793d](https://linux-hardware.org/?probe=653a25793d) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | [dccecbecf9](https://linux-hardware.org/?probe=dccecbecf9) | Apr 12, 2023 |
| HP            | EliteBook 840 G5            | [da4c241466](https://linux-hardware.org/?probe=da4c241466) | Apr 10, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [5244868737](https://linux-hardware.org/?probe=5244868737) | Apr 09, 2023 |
| Lenovo        | ThinkPad T480 20L6S4G72S    | [ae8c333d72](https://linux-hardware.org/?probe=ae8c333d72) | Apr 07, 2023 |
| ASUSTek       | X55U                        | [0abf7df439](https://linux-hardware.org/?probe=0abf7df439) | Apr 06, 2023 |
| ASUSTek       | X550CL                      | [5d5862d22a](https://linux-hardware.org/?probe=5d5862d22a) | Mar 31, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [5be11a9a6e](https://linux-hardware.org/?probe=5be11a9a6e) | Mar 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [bfa850ddad](https://linux-hardware.org/?probe=bfa850ddad) | Mar 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [577947c9d3](https://linux-hardware.org/?probe=577947c9d3) | Mar 28, 2023 |
| Toshiba       | Satellite C55-A-1J8         | [c6ba40cd5c](https://linux-hardware.org/?probe=c6ba40cd5c) | Mar 27, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [08e7388619](https://linux-hardware.org/?probe=08e7388619) | Mar 27, 2023 |
| ASUSTek       | X751SA                      | [bef27b5a10](https://linux-hardware.org/?probe=bef27b5a10) | Mar 26, 2023 |
| ASUSTek       | X751SA                      | [daac2899b2](https://linux-hardware.org/?probe=daac2899b2) | Mar 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [84af25ca8c](https://linux-hardware.org/?probe=84af25ca8c) | Mar 26, 2023 |
| Acer          | Aspire 7750G                | [f99591fe95](https://linux-hardware.org/?probe=f99591fe95) | Mar 26, 2023 |
| Acer          | V5-131                      | [f35bd55401](https://linux-hardware.org/?probe=f35bd55401) | Mar 26, 2023 |
| Acer          | TravelMate 5744             | [3ad8bf7639](https://linux-hardware.org/?probe=3ad8bf7639) | Mar 22, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [c5b2997e80](https://linux-hardware.org/?probe=c5b2997e80) | Mar 21, 2023 |
| HP            | 250 G5 Notebook PC          | [4a4c44f0dd](https://linux-hardware.org/?probe=4a4c44f0dd) | Mar 18, 2023 |
| HP            | ZBook 15                    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| Valve         | Jupiter                     | [d56d3939f9](https://linux-hardware.org/?probe=d56d3939f9) | Mar 14, 2023 |
| MSI           | GF63 Thin 11UC              | [7c96c962f0](https://linux-hardware.org/?probe=7c96c962f0) | Mar 13, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [4492e72dd8](https://linux-hardware.org/?probe=4492e72dd8) | Mar 10, 2023 |
| HP            | Compaq nx9420 (ES446EA#A... | [b876c92a6e](https://linux-hardware.org/?probe=b876c92a6e) | Mar 09, 2023 |
| HP            | Compaq 6735b                | [8c664182a2](https://linux-hardware.org/?probe=8c664182a2) | Mar 05, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4fc82abdeb](https://linux-hardware.org/?probe=4fc82abdeb) | Mar 04, 2023 |
| Dell          | Inspiron 3593               | [4e2f59d17e](https://linux-hardware.org/?probe=4e2f59d17e) | Mar 04, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4c25c88937](https://linux-hardware.org/?probe=4c25c88937) | Mar 03, 2023 |
| Chuwi         | GemiBook Pro                | [1b68738664](https://linux-hardware.org/?probe=1b68738664) | Mar 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [2dea6717ae](https://linux-hardware.org/?probe=2dea6717ae) | Mar 02, 2023 |
| ASUSTek       | FX503VD                     | [46954919f7](https://linux-hardware.org/?probe=46954919f7) | Feb 27, 2023 |
| ASUSTek       | FX503VD                     | [60e1742e7e](https://linux-hardware.org/?probe=60e1742e7e) | Feb 27, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [bd2c3ecd74](https://linux-hardware.org/?probe=bd2c3ecd74) | Feb 25, 2023 |
| ASUSTek       | X541UV                      | [6765309d07](https://linux-hardware.org/?probe=6765309d07) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [562517eab4](https://linux-hardware.org/?probe=562517eab4) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [22cf774ac0](https://linux-hardware.org/?probe=22cf774ac0) | Feb 25, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | [46aedb5579](https://linux-hardware.org/?probe=46aedb5579) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [277834a459](https://linux-hardware.org/?probe=277834a459) | Feb 24, 2023 |
| Lenovo        | ThinkPad X230 2325CS6       | [ed9501bbcb](https://linux-hardware.org/?probe=ed9501bbcb) | Feb 23, 2023 |
| ASUSTek       | X553SA                      | [bf6718f1d0](https://linux-hardware.org/?probe=bf6718f1d0) | Feb 22, 2023 |
| Dell          | Latitude 5580               | [91567566be](https://linux-hardware.org/?probe=91567566be) | Feb 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [c205da78c9](https://linux-hardware.org/?probe=c205da78c9) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [8942075e7b](https://linux-hardware.org/?probe=8942075e7b) | Feb 18, 2023 |
| ASUSTek       | X553SA                      | [dc294f018e](https://linux-hardware.org/?probe=dc294f018e) | Feb 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [e614d24613](https://linux-hardware.org/?probe=e614d24613) | Feb 17, 2023 |
| Toshiba       | Satellite L650              | [553bddf256](https://linux-hardware.org/?probe=553bddf256) | Feb 15, 2023 |
| HP            | EliteBook 850 G2            | [ed0641ce38](https://linux-hardware.org/?probe=ed0641ce38) | Feb 15, 2023 |
| Dell          | Inspiron 16 5625            | [d4951f7e68](https://linux-hardware.org/?probe=d4951f7e68) | Feb 11, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [6047c68386](https://linux-hardware.org/?probe=6047c68386) | Feb 11, 2023 |
| ASUSTek       | G73Sw                       | [199c8805ee](https://linux-hardware.org/?probe=199c8805ee) | Feb 10, 2023 |
| ASUSTek       | GL753VD                     | [e7b8536ad4](https://linux-hardware.org/?probe=e7b8536ad4) | Feb 09, 2023 |
| Dell          | Inspiron 15 3525            | [2f47f8d73d](https://linux-hardware.org/?probe=2f47f8d73d) | Feb 05, 2023 |
| Toshiba       | Satellite C55-A-168         | [e92c2babc4](https://linux-hardware.org/?probe=e92c2babc4) | Feb 05, 2023 |
| Dell          | Vostro 15 3515              | [c4c5c0888a](https://linux-hardware.org/?probe=c4c5c0888a) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [0b1fbca173](https://linux-hardware.org/?probe=0b1fbca173) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ab31f6153e](https://linux-hardware.org/?probe=ab31f6153e) | Feb 01, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [6ed194a014](https://linux-hardware.org/?probe=6ed194a014) | Feb 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [e2ad5b033f](https://linux-hardware.org/?probe=e2ad5b033f) | Jan 31, 2023 |
| ASUSTek       | X556UQK                     | [6c3dd54582](https://linux-hardware.org/?probe=6c3dd54582) | Jan 30, 2023 |
| ASUSTek       | G73Sw                       | [b8891cfc9b](https://linux-hardware.org/?probe=b8891cfc9b) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | [fb0a23c0e6](https://linux-hardware.org/?probe=fb0a23c0e6) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | [24b6a47ebb](https://linux-hardware.org/?probe=24b6a47ebb) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [5d58c53672](https://linux-hardware.org/?probe=5d58c53672) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [b352f0af44](https://linux-hardware.org/?probe=b352f0af44) | Jan 27, 2023 |
| ASUSTek       | X541UVK                     | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [e030231e2c](https://linux-hardware.org/?probe=e030231e2c) | Jan 25, 2023 |
| Lenovo        | B50-80 80EW                 | [5f584c387e](https://linux-hardware.org/?probe=5f584c387e) | Jan 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ec369b35a4](https://linux-hardware.org/?probe=ec369b35a4) | Jan 24, 2023 |
| Lenovo        | B50-80 80EW                 | [61932dd31a](https://linux-hardware.org/?probe=61932dd31a) | Jan 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [62ac206f7e](https://linux-hardware.org/?probe=62ac206f7e) | Jan 23, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [8cb10f3212](https://linux-hardware.org/?probe=8cb10f3212) | Jan 23, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [36d99ec94e](https://linux-hardware.org/?probe=36d99ec94e) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | [adbc469f95](https://linux-hardware.org/?probe=adbc469f95) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | [9249ff32b3](https://linux-hardware.org/?probe=9249ff32b3) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [523d0331a1](https://linux-hardware.org/?probe=523d0331a1) | Jan 21, 2023 |
| HP            | EliteBook 850 G2            | [a7ba34fed5](https://linux-hardware.org/?probe=a7ba34fed5) | Jan 21, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | [de713cedce](https://linux-hardware.org/?probe=de713cedce) | Jan 21, 2023 |
| Acer          | V5WE2                       | [021281441e](https://linux-hardware.org/?probe=021281441e) | Jan 20, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [be320f363d](https://linux-hardware.org/?probe=be320f363d) | Jan 19, 2023 |
| Dell          | Precision M6600             | [478f51f2be](https://linux-hardware.org/?probe=478f51f2be) | Jan 17, 2023 |
| Dell          | Precision M6600             | [7511681884](https://linux-hardware.org/?probe=7511681884) | Jan 16, 2023 |
| Dell          | Inspiron 15-3567            | [020e19b05d](https://linux-hardware.org/?probe=020e19b05d) | Jan 16, 2023 |
| Dell          | Inspiron 15-3567            | [5426686264](https://linux-hardware.org/?probe=5426686264) | Jan 15, 2023 |
| Valve         | Jupiter                     | [020abf67f6](https://linux-hardware.org/?probe=020abf67f6) | Jan 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [f32463429a](https://linux-hardware.org/?probe=f32463429a) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [6f39a15710](https://linux-hardware.org/?probe=6f39a15710) | Jan 13, 2023 |
| ASUSTek       | X406UAR                     | [68da6f6220](https://linux-hardware.org/?probe=68da6f6220) | Jan 13, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [0eb36758be](https://linux-hardware.org/?probe=0eb36758be) | Jan 13, 2023 |
| ASUSTek       | X406UAR                     | [729e2e0d41](https://linux-hardware.org/?probe=729e2e0d41) | Jan 12, 2023 |
| Lenovo        | B50-80 80EW                 | [7bf9c1c7f4](https://linux-hardware.org/?probe=7bf9c1c7f4) | Jan 10, 2023 |
| Acer          | TMP645-M                    | [8e0b2f5e90](https://linux-hardware.org/?probe=8e0b2f5e90) | Jan 10, 2023 |
| VALE          | Notebook Classic C140       | [afe262fc54](https://linux-hardware.org/?probe=afe262fc54) | Jan 09, 2023 |
| ASUSTek       | K50IE                       | [4fdb15502c](https://linux-hardware.org/?probe=4fdb15502c) | Jan 09, 2023 |
| Lenovo        | ThinkPad A275 20KCS0FT02    | [fc35d7e62b](https://linux-hardware.org/?probe=fc35d7e62b) | Jan 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [69cda32447](https://linux-hardware.org/?probe=69cda32447) | Jan 08, 2023 |
| Acer          | Aspire A315-21G             | [cc98c43ea0](https://linux-hardware.org/?probe=cc98c43ea0) | Jan 07, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [9320df061f](https://linux-hardware.org/?probe=9320df061f) | Jan 06, 2023 |
| Neousys Te... | POC-200 Series              | [7c37ff8631](https://linux-hardware.org/?probe=7c37ff8631) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | [0042419ccb](https://linux-hardware.org/?probe=0042419ccb) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | [82e42c0d42](https://linux-hardware.org/?probe=82e42c0d42) | Jan 04, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [bb1b612416](https://linux-hardware.org/?probe=bb1b612416) | Dec 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8702939897](https://linux-hardware.org/?probe=8702939897) | Dec 29, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [8db34630c3](https://linux-hardware.org/?probe=8db34630c3) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1ff4c4bf09](https://linux-hardware.org/?probe=1ff4c4bf09) | Dec 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ad33bb0d6f](https://linux-hardware.org/?probe=ad33bb0d6f) | Dec 28, 2022 |
| Dell          | Latitude 7480               | [45b0f992f6](https://linux-hardware.org/?probe=45b0f992f6) | Dec 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [62869e3d8c](https://linux-hardware.org/?probe=62869e3d8c) | Dec 26, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [5aa14f474e](https://linux-hardware.org/?probe=5aa14f474e) | Dec 25, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [098390e03e](https://linux-hardware.org/?probe=098390e03e) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9ea4a13b0f](https://linux-hardware.org/?probe=9ea4a13b0f) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fa7183c982](https://linux-hardware.org/?probe=fa7183c982) | Dec 25, 2022 |
| Acer          | Aspire VX5-591G             | [7defe87998](https://linux-hardware.org/?probe=7defe87998) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fe159bf4ca](https://linux-hardware.org/?probe=fe159bf4ca) | Dec 23, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [81f7e4d804](https://linux-hardware.org/?probe=81f7e4d804) | Dec 22, 2022 |
| Acer          | Nitro AN515-58              | [041cd6f9bd](https://linux-hardware.org/?probe=041cd6f9bd) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680AA4       | [6306be2273](https://linux-hardware.org/?probe=6306be2273) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680AA4       | [cf8576151f](https://linux-hardware.org/?probe=cf8576151f) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [721bc5f662](https://linux-hardware.org/?probe=721bc5f662) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d9db7be046](https://linux-hardware.org/?probe=d9db7be046) | Dec 21, 2022 |
| ASUSTek       | N53SM                       | [9c9b1d3f5b](https://linux-hardware.org/?probe=9c9b1d3f5b) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [89b8982148](https://linux-hardware.org/?probe=89b8982148) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [082a1fb19e](https://linux-hardware.org/?probe=082a1fb19e) | Dec 20, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [20544e55bb](https://linux-hardware.org/?probe=20544e55bb) | Dec 14, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| ASUSTek       | G75VW                       | [8d2a0ec4e4](https://linux-hardware.org/?probe=8d2a0ec4e4) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [a1f1288337](https://linux-hardware.org/?probe=a1f1288337) | Dec 13, 2022 |
| ASUSTek       | GL752VW                     | [05c7382806](https://linux-hardware.org/?probe=05c7382806) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a7a3ccf712](https://linux-hardware.org/?probe=a7a3ccf712) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1a7d599cd5](https://linux-hardware.org/?probe=1a7d599cd5) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [83b02f1ffb](https://linux-hardware.org/?probe=83b02f1ffb) | Dec 10, 2022 |
| Dell          | Latitude E6520              | [ec32b72261](https://linux-hardware.org/?probe=ec32b72261) | Dec 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea7638c0f9](https://linux-hardware.org/?probe=ea7638c0f9) | Dec 07, 2022 |
| Acer          | Aspire A515-51G             | [10f8aab734](https://linux-hardware.org/?probe=10f8aab734) | Dec 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [a35bac4078](https://linux-hardware.org/?probe=a35bac4078) | Dec 06, 2022 |
| ASUSTek       | X556UQK                     | [2f693620e1](https://linux-hardware.org/?probe=2f693620e1) | Dec 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [b387887bb6](https://linux-hardware.org/?probe=b387887bb6) | Dec 03, 2022 |
| Acer          | Nitro AN515-44              | [56a2d42adc](https://linux-hardware.org/?probe=56a2d42adc) | Dec 02, 2022 |
| HUAWEI        | BOHB-WAX9                   | [3d64de28f5](https://linux-hardware.org/?probe=3d64de28f5) | Dec 01, 2022 |
| Lenovo        | ThinkPad T530 24297ZG       | [422f84a794](https://linux-hardware.org/?probe=422f84a794) | Nov 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1FR0... | [517347d2cf](https://linux-hardware.org/?probe=517347d2cf) | Nov 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [8e6e8471a7](https://linux-hardware.org/?probe=8e6e8471a7) | Nov 29, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [972f6f4355](https://linux-hardware.org/?probe=972f6f4355) | Nov 28, 2022 |
| HUAWEI        | BOD-WXX9                    | [5b2f9bfd5c](https://linux-hardware.org/?probe=5b2f9bfd5c) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | [a39632439e](https://linux-hardware.org/?probe=a39632439e) | Nov 27, 2022 |
| Acer          | Nitro AN515-58              | [4916981641](https://linux-hardware.org/?probe=4916981641) | Nov 26, 2022 |
| HP            | ProBook 450 G7              | [52d46ed47e](https://linux-hardware.org/?probe=52d46ed47e) | Nov 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0565ef1a0d](https://linux-hardware.org/?probe=0565ef1a0d) | Nov 22, 2022 |
| Dell          | Latitude E6410              | [22585074f3](https://linux-hardware.org/?probe=22585074f3) | Nov 21, 2022 |
| ASUSTek       | X541UAK                     | [75af06e026](https://linux-hardware.org/?probe=75af06e026) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c5ec7b9dcc](https://linux-hardware.org/?probe=c5ec7b9dcc) | Nov 20, 2022 |
| Lenovo        | V15 G1 IML 82NB             | [a120cac88b](https://linux-hardware.org/?probe=a120cac88b) | Nov 18, 2022 |
| Allview       | Allbook H                   | [4de72c8cba](https://linux-hardware.org/?probe=4de72c8cba) | Nov 17, 2022 |
| ASUSTek       | X550VX                      | [a1e3d4527c](https://linux-hardware.org/?probe=a1e3d4527c) | Nov 15, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [fef97563a0](https://linux-hardware.org/?probe=fef97563a0) | Nov 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [61bcea3891](https://linux-hardware.org/?probe=61bcea3891) | Nov 13, 2022 |
| Alienware     | Area-51m                    | [11c59a838f](https://linux-hardware.org/?probe=11c59a838f) | Nov 12, 2022 |
| Dell          | Latitude E7270              | [629a581a22](https://linux-hardware.org/?probe=629a581a22) | Nov 12, 2022 |
| Dell          | Latitude E7470              | [e80d2221f5](https://linux-hardware.org/?probe=e80d2221f5) | Nov 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [0144bb5a89](https://linux-hardware.org/?probe=0144bb5a89) | Nov 08, 2022 |
| Toshiba       | Satellite C50-A-1HF         | [8384350121](https://linux-hardware.org/?probe=8384350121) | Nov 08, 2022 |
| Acer          | Aspire A314-35              | [14751e1ae3](https://linux-hardware.org/?probe=14751e1ae3) | Nov 08, 2022 |
| Lenovo        | B590 20206                  | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| Valve         | Jupiter                     | [5800bb0b18](https://linux-hardware.org/?probe=5800bb0b18) | Nov 06, 2022 |
| HP            | Laptop 15-da0xxx            | [f8d2bbf15a](https://linux-hardware.org/?probe=f8d2bbf15a) | Nov 06, 2022 |
| Valve         | Jupiter                     | [55293ff823](https://linux-hardware.org/?probe=55293ff823) | Nov 05, 2022 |
| Dell          | XPS 15 9530                 | [5ffd5ed23d](https://linux-hardware.org/?probe=5ffd5ed23d) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [7dc3ed5f76](https://linux-hardware.org/?probe=7dc3ed5f76) | Nov 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [f5060f0a8d](https://linux-hardware.org/?probe=f5060f0a8d) | Nov 01, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | [1563c60737](https://linux-hardware.org/?probe=1563c60737) | Oct 31, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81A8     | [85efda7536](https://linux-hardware.org/?probe=85efda7536) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Dell          | XPS 15 9530                 | [fc7ef1ce9a](https://linux-hardware.org/?probe=fc7ef1ce9a) | Oct 29, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | [f9238c2035](https://linux-hardware.org/?probe=f9238c2035) | Oct 28, 2022 |
| Samsung       | 550P5C/550P7C               | [7dca4296ee](https://linux-hardware.org/?probe=7dca4296ee) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [7274eca48b](https://linux-hardware.org/?probe=7274eca48b) | Oct 23, 2022 |
| Timi          | Xiaomi Book Pro 14 2022     | [18e52559a4](https://linux-hardware.org/?probe=18e52559a4) | Oct 17, 2022 |
| MSI           | GV72 7RE                    | [84941aaa84](https://linux-hardware.org/?probe=84941aaa84) | Oct 14, 2022 |
| ASUSTek       | N53Jf                       | [a6a5cdbf04](https://linux-hardware.org/?probe=a6a5cdbf04) | Oct 13, 2022 |
| Acer          | Aspire E5-573G              | [bccf0a4ebe](https://linux-hardware.org/?probe=bccf0a4ebe) | Oct 13, 2022 |
| Dell          | XPS 15 9530                 | [ad2b1ab7b8](https://linux-hardware.org/?probe=ad2b1ab7b8) | Oct 12, 2022 |
| Medion        | Akoya E6239                 | [46ce690b32](https://linux-hardware.org/?probe=46ce690b32) | Oct 10, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [ef1974cfc8](https://linux-hardware.org/?probe=ef1974cfc8) | Oct 10, 2022 |
| Dell          | Latitude E6410              | [4f6730e0f2](https://linux-hardware.org/?probe=4f6730e0f2) | Oct 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| Valve         | Jupiter                     | [889099ff63](https://linux-hardware.org/?probe=889099ff63) | Oct 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d9474bd3b9](https://linux-hardware.org/?probe=d9474bd3b9) | Oct 03, 2022 |
| Dell          | XPS 15 9530                 | [abfab502a6](https://linux-hardware.org/?probe=abfab502a6) | Oct 02, 2022 |
| Medion        | Akoya P2214T                | [428205d2a5](https://linux-hardware.org/?probe=428205d2a5) | Oct 02, 2022 |
| HP            | Laptop 15-da0xxx            | [176695aa20](https://linux-hardware.org/?probe=176695aa20) | Sep 30, 2022 |
| HP            | 250 G5 Notebook PC          | [26961d1b30](https://linux-hardware.org/?probe=26961d1b30) | Sep 29, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [3e92ba3812](https://linux-hardware.org/?probe=3e92ba3812) | Sep 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [96c4c8ba02](https://linux-hardware.org/?probe=96c4c8ba02) | Sep 28, 2022 |
| Dell          | System Inspiron N7110       | [016d5e3146](https://linux-hardware.org/?probe=016d5e3146) | Sep 27, 2022 |
| Lenovo        | ThinkPad T420 4236C53       | [e0983b35fa](https://linux-hardware.org/?probe=e0983b35fa) | Sep 25, 2022 |
| Acer          | Aspire 5750Z                | [38e1cc9153](https://linux-hardware.org/?probe=38e1cc9153) | Sep 22, 2022 |
| Fusion5       | S14                         | [9b3e06c4e4](https://linux-hardware.org/?probe=9b3e06c4e4) | Sep 22, 2022 |
| Acer          | Aspire 5750Z                | [b673d5cfe9](https://linux-hardware.org/?probe=b673d5cfe9) | Sep 22, 2022 |
| Dell          | Precision 3561              | [b924a86b79](https://linux-hardware.org/?probe=b924a86b79) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | [6fb7c9c27a](https://linux-hardware.org/?probe=6fb7c9c27a) | Sep 21, 2022 |
| HP            | ProBook 640 G4              | [41cb2444c5](https://linux-hardware.org/?probe=41cb2444c5) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | [a93242008f](https://linux-hardware.org/?probe=a93242008f) | Sep 20, 2022 |
| Acer          | Aspire A515-45              | [5b0c60618f](https://linux-hardware.org/?probe=5b0c60618f) | Sep 20, 2022 |
| Acer          | Aspire 5349                 | [39f83f7692](https://linux-hardware.org/?probe=39f83f7692) | Sep 13, 2022 |
| Dell          | XPS 15 9530                 | [fbb3c09289](https://linux-hardware.org/?probe=fbb3c09289) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | [fccf3eb345](https://linux-hardware.org/?probe=fccf3eb345) | Sep 12, 2022 |
| Samsung       | R530/R730/R540              | [72aea277e6](https://linux-hardware.org/?probe=72aea277e6) | Sep 10, 2022 |
| HP            | Pavilion g6                 | [0774a3c97d](https://linux-hardware.org/?probe=0774a3c97d) | Sep 10, 2022 |
| Lenovo        | Legion Y7000P-1060 81LF     | [b018911117](https://linux-hardware.org/?probe=b018911117) | Sep 09, 2022 |
| HP            | EliteBook 8440p             | [3474424d64](https://linux-hardware.org/?probe=3474424d64) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | [e47c8e6967](https://linux-hardware.org/?probe=e47c8e6967) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | [3f805d59b5](https://linux-hardware.org/?probe=3f805d59b5) | Sep 04, 2022 |
| Acer          | Extensa 5635ZG              | [f79a7aaa6f](https://linux-hardware.org/?probe=f79a7aaa6f) | Sep 03, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [b91c67af87](https://linux-hardware.org/?probe=b91c67af87) | Sep 02, 2022 |
| Dell          | Latitude 5521               | [dcf7869cf6](https://linux-hardware.org/?probe=dcf7869cf6) | Sep 01, 2022 |
| Valve         | Jupiter                     | [6e9790c5e7](https://linux-hardware.org/?probe=6e9790c5e7) | Sep 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [b4a9d1fecc](https://linux-hardware.org/?probe=b4a9d1fecc) | Aug 30, 2022 |
| Dell          | Latitude E7470              | [568c9bfd40](https://linux-hardware.org/?probe=568c9bfd40) | Aug 28, 2022 |
| Acer          | Aspire A315-23              | [4c16a58579](https://linux-hardware.org/?probe=4c16a58579) | Aug 28, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [fbf3d4a87a](https://linux-hardware.org/?probe=fbf3d4a87a) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [02c6bde77b](https://linux-hardware.org/?probe=02c6bde77b) | Aug 27, 2022 |
| ASUSTek       | X550CC                      | [8b85141416](https://linux-hardware.org/?probe=8b85141416) | Aug 26, 2022 |
| Complet       | MY8312                      | [4db1527bde](https://linux-hardware.org/?probe=4db1527bde) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c8b4d18767](https://linux-hardware.org/?probe=c8b4d18767) | Aug 25, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [09feb7053d](https://linux-hardware.org/?probe=09feb7053d) | Aug 25, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [69281b6cc3](https://linux-hardware.org/?probe=69281b6cc3) | Aug 24, 2022 |
| Dell          | Latitude 7410               | [ae90ce90ed](https://linux-hardware.org/?probe=ae90ce90ed) | Aug 22, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [9c31fff4b2](https://linux-hardware.org/?probe=9c31fff4b2) | Aug 20, 2022 |
| Dell          | Latitude 7420               | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [1a0800fc4a](https://linux-hardware.org/?probe=1a0800fc4a) | Aug 19, 2022 |
| Dell          | Inspiron 5558               | [b4bc42c01c](https://linux-hardware.org/?probe=b4bc42c01c) | Aug 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [97fb16fc3f](https://linux-hardware.org/?probe=97fb16fc3f) | Aug 17, 2022 |
| Dell          | XPS 15 9530                 | [71f62cef7a](https://linux-hardware.org/?probe=71f62cef7a) | Aug 16, 2022 |
| Dell          | Inspiron 1501               | [11b4c83b79](https://linux-hardware.org/?probe=11b4c83b79) | Aug 15, 2022 |
| Acer          | Aspire V3-571G              | [f45a97ca40](https://linux-hardware.org/?probe=f45a97ca40) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [9e77f6044a](https://linux-hardware.org/?probe=9e77f6044a) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [eb79423b1d](https://linux-hardware.org/?probe=eb79423b1d) | Aug 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cc51e49c51](https://linux-hardware.org/?probe=cc51e49c51) | Aug 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [6826a8d40d](https://linux-hardware.org/?probe=6826a8d40d) | Aug 08, 2022 |
| ASUSTek       | X550CL                      | [83626d765b](https://linux-hardware.org/?probe=83626d765b) | Aug 08, 2022 |
| Dell          | Latitude E6540              | [d47b2c5c2b](https://linux-hardware.org/?probe=d47b2c5c2b) | Aug 06, 2022 |
| Acer          | Aspire A515-45              | [ddd717c7e6](https://linux-hardware.org/?probe=ddd717c7e6) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3025bd4ded](https://linux-hardware.org/?probe=3025bd4ded) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G713RS_G713RS     | [707ab083b3](https://linux-hardware.org/?probe=707ab083b3) | Aug 04, 2022 |
| HP            | Pavilion 15                 | [e6bfde2a29](https://linux-hardware.org/?probe=e6bfde2a29) | Jul 29, 2022 |
| Dell          | System Inspiron N7110       | [d2cbf8528a](https://linux-hardware.org/?probe=d2cbf8528a) | Jul 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8b3fd99e18](https://linux-hardware.org/?probe=8b3fd99e18) | Jul 27, 2022 |
| HP            | EliteBook 8460p             | [7b2de05256](https://linux-hardware.org/?probe=7b2de05256) | Jul 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4ee4fc0689](https://linux-hardware.org/?probe=4ee4fc0689) | Jul 26, 2022 |
| Lenovo        | ThinkPad P52 20MAS1R100     | [7a01b8819c](https://linux-hardware.org/?probe=7a01b8819c) | Jul 21, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [9a5f11c4b9](https://linux-hardware.org/?probe=9a5f11c4b9) | Jul 19, 2022 |
| HP            | EliteBook 850 G1            | [383ec7a7fd](https://linux-hardware.org/?probe=383ec7a7fd) | Jul 18, 2022 |
| Acer          | Aspire SW3-016              | [c48cdf5576](https://linux-hardware.org/?probe=c48cdf5576) | Jul 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [55efce6cdc](https://linux-hardware.org/?probe=55efce6cdc) | Jul 13, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [be909dd3b4](https://linux-hardware.org/?probe=be909dd3b4) | Jul 12, 2022 |
| HP            | 355 G2                      | [55239c5062](https://linux-hardware.org/?probe=55239c5062) | Jul 11, 2022 |
| HP            | 355 G2                      | [9b5e64b838](https://linux-hardware.org/?probe=9b5e64b838) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e7b17323df](https://linux-hardware.org/?probe=e7b17323df) | Jul 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [8f36480ad7](https://linux-hardware.org/?probe=8f36480ad7) | Jul 10, 2022 |
| HP            | 250 G4                      | [33dcd9203d](https://linux-hardware.org/?probe=33dcd9203d) | Jul 09, 2022 |
| Acer          | Nitro AN515-45              | [a9dd7c4072](https://linux-hardware.org/?probe=a9dd7c4072) | Jul 08, 2022 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | [99172a6e6f](https://linux-hardware.org/?probe=99172a6e6f) | Jul 08, 2022 |
| Dell          | Latitude 5420               | [cb302e010e](https://linux-hardware.org/?probe=cb302e010e) | Jul 08, 2022 |
| HP            | ProBook 4310s               | [86ae79b260](https://linux-hardware.org/?probe=86ae79b260) | Jul 07, 2022 |
| Acer          | Aspire A515-51G             | [3ab547df65](https://linux-hardware.org/?probe=3ab547df65) | Jul 04, 2022 |
| Acer          | Aspire A515-51G             | [98ef915ec8](https://linux-hardware.org/?probe=98ef915ec8) | Jul 03, 2022 |
| Dell          | Latitude 5521               | [2fda374f06](https://linux-hardware.org/?probe=2fda374f06) | Jun 24, 2022 |
| Dell          | Inspiron 5567               | [2791443b0d](https://linux-hardware.org/?probe=2791443b0d) | Jun 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [fc053b8a95](https://linux-hardware.org/?probe=fc053b8a95) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [70d6947d54](https://linux-hardware.org/?probe=70d6947d54) | Jun 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [1e88796016](https://linux-hardware.org/?probe=1e88796016) | Jun 15, 2022 |
| Acer          | Aspire One 522              | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| ASUSTek       | K50IJ                       | [c8bac63870](https://linux-hardware.org/?probe=c8bac63870) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | [addb86fcb0](https://linux-hardware.org/?probe=addb86fcb0) | Jun 10, 2022 |
| Dell          | Latitude E6440              | [63238f8fe9](https://linux-hardware.org/?probe=63238f8fe9) | Jun 09, 2022 |
| HUAWEI        | KLVL-WXX9                   | [992f232db5](https://linux-hardware.org/?probe=992f232db5) | Jun 08, 2022 |
| Dell          | Latitude D520               | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Prestigio     | PSB141C04CGP                | [4fa2ee47c0](https://linux-hardware.org/?probe=4fa2ee47c0) | Jun 01, 2022 |
| Acer          | Aspire A315-51              | [083e3a354a](https://linux-hardware.org/?probe=083e3a354a) | May 29, 2022 |
| ASUSTek       | N53SM                       | [83209051cb](https://linux-hardware.org/?probe=83209051cb) | May 29, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [caaf2a56b6](https://linux-hardware.org/?probe=caaf2a56b6) | May 26, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [74c64ebe72](https://linux-hardware.org/?probe=74c64ebe72) | May 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [940a448ea6](https://linux-hardware.org/?probe=940a448ea6) | May 24, 2022 |
| ASUSTek       | N53SM                       | [3115570400](https://linux-hardware.org/?probe=3115570400) | May 24, 2022 |
| Allview       | Allbook H                   | [9ea4897c6b](https://linux-hardware.org/?probe=9ea4897c6b) | May 24, 2022 |
| Dell          | Latitude E7470              | [b01633e1ae](https://linux-hardware.org/?probe=b01633e1ae) | May 24, 2022 |
| Dell          | Latitude E7470              | [815dbb114b](https://linux-hardware.org/?probe=815dbb114b) | May 23, 2022 |
| Dell          | Latitude E7470              | [9a6c29a243](https://linux-hardware.org/?probe=9a6c29a243) | May 21, 2022 |
| Acer          | Aspire One 522              | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Dell          | Latitude E6410              | [739ffac681](https://linux-hardware.org/?probe=739ffac681) | May 21, 2022 |
| Dell          | Inspiron 3542               | [949f8f3e50](https://linux-hardware.org/?probe=949f8f3e50) | May 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [4d2d33c41c](https://linux-hardware.org/?probe=4d2d33c41c) | May 20, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [59d945a9b3](https://linux-hardware.org/?probe=59d945a9b3) | May 19, 2022 |
| Lenovo        | ThinkPad P53 20QNS01900     | [158f212b30](https://linux-hardware.org/?probe=158f212b30) | May 13, 2022 |
| Dell          | Inspiron 3542               | [550824d592](https://linux-hardware.org/?probe=550824d592) | May 12, 2022 |
| Dell          | Inspiron 3542               | [324d1abe3b](https://linux-hardware.org/?probe=324d1abe3b) | May 08, 2022 |
| HP            | ProBook 4520s               | [06e044a425](https://linux-hardware.org/?probe=06e044a425) | May 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [52c2a321a4](https://linux-hardware.org/?probe=52c2a321a4) | May 07, 2022 |
| Acer          | Aspire E1-570               | [53ddeaa413](https://linux-hardware.org/?probe=53ddeaa413) | May 07, 2022 |
| HP            | Laptop 14s-dq1xxx           | [713358f855](https://linux-hardware.org/?probe=713358f855) | May 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [6537fb670a](https://linux-hardware.org/?probe=6537fb670a) | May 01, 2022 |
| Toshiba       | Satellite C55-A-1J8         | [26cd3478c5](https://linux-hardware.org/?probe=26cd3478c5) | Apr 30, 2022 |
| HP            | ProBook 4520s               | [60eab2c6c5](https://linux-hardware.org/?probe=60eab2c6c5) | Apr 30, 2022 |
| Pegatron      | Spring Peak                 | [66a1692171](https://linux-hardware.org/?probe=66a1692171) | Apr 30, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | [495a74c914](https://linux-hardware.org/?probe=495a74c914) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | [efcd6be006](https://linux-hardware.org/?probe=efcd6be006) | Apr 27, 2022 |
| Dell          | Latitude E4310              | [41db45879c](https://linux-hardware.org/?probe=41db45879c) | Apr 27, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | [afe44fa080](https://linux-hardware.org/?probe=afe44fa080) | Apr 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [8ece944a7b](https://linux-hardware.org/?probe=8ece944a7b) | Apr 27, 2022 |
| Dell          | Latitude E6520              | [1ca407a69f](https://linux-hardware.org/?probe=1ca407a69f) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | [1621e22812](https://linux-hardware.org/?probe=1621e22812) | Apr 26, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bcc0c7612d](https://linux-hardware.org/?probe=bcc0c7612d) | Apr 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1EH0... | [fae5ee6551](https://linux-hardware.org/?probe=fae5ee6551) | Apr 26, 2022 |
| Dell          | XPS 17 9710                 | [c7dfc69b32](https://linux-hardware.org/?probe=c7dfc69b32) | Apr 26, 2022 |
| HP            | ProBook 4520s               | [1621eddc70](https://linux-hardware.org/?probe=1621eddc70) | Apr 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1d1c33575f](https://linux-hardware.org/?probe=1d1c33575f) | Apr 24, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | [41276f12db](https://linux-hardware.org/?probe=41276f12db) | Apr 23, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | [55733b5ae3](https://linux-hardware.org/?probe=55733b5ae3) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [a551ef1ec7](https://linux-hardware.org/?probe=a551ef1ec7) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [fd6718859d](https://linux-hardware.org/?probe=fd6718859d) | Apr 23, 2022 |
| ASUSTek       | X450CP                      | [2518b6daad](https://linux-hardware.org/?probe=2518b6daad) | Apr 22, 2022 |
| ASUSTek       | X450CP                      | [17d51c502f](https://linux-hardware.org/?probe=17d51c502f) | Apr 22, 2022 |
| HP            | Laptop 15-ra0xx             | [bc175803f2](https://linux-hardware.org/?probe=bc175803f2) | Apr 22, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1Y90... | [de746c72d1](https://linux-hardware.org/?probe=de746c72d1) | Apr 20, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | [5d95841f54](https://linux-hardware.org/?probe=5d95841f54) | Apr 20, 2022 |
| Lenovo        | ThinkPad T560 20FJS0NT04    | [19ebdf705a](https://linux-hardware.org/?probe=19ebdf705a) | Apr 20, 2022 |
| ASUSTek       | X541UAK                     | [8b54af493a](https://linux-hardware.org/?probe=8b54af493a) | Apr 19, 2022 |
| Dell          | Latitude E6440              | [33955db41e](https://linux-hardware.org/?probe=33955db41e) | Apr 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1825f45bfa](https://linux-hardware.org/?probe=1825f45bfa) | Apr 17, 2022 |
| MSI           | Modern 14 B4MW              | [5d8e6ca082](https://linux-hardware.org/?probe=5d8e6ca082) | Apr 16, 2022 |
| HP            | Pavilion 17                 | [acb0c7fd0e](https://linux-hardware.org/?probe=acb0c7fd0e) | Apr 16, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1Y90... | [a572c901ca](https://linux-hardware.org/?probe=a572c901ca) | Apr 15, 2022 |
| HP            | Pavilion 17                 | [014f42ecee](https://linux-hardware.org/?probe=014f42ecee) | Apr 15, 2022 |
| Acer          | Aspire 5750G                | [73d1368d93](https://linux-hardware.org/?probe=73d1368d93) | Apr 15, 2022 |
| Dell          | System XPS L702X            | [9ed530100f](https://linux-hardware.org/?probe=9ed530100f) | Apr 13, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [95ddaa1dae](https://linux-hardware.org/?probe=95ddaa1dae) | Apr 13, 2022 |
| Dell          | Inspiron 5570               | [ba6f51707b](https://linux-hardware.org/?probe=ba6f51707b) | Apr 13, 2022 |
| HP            | EliteBook 2540p             | [a06e300bfd](https://linux-hardware.org/?probe=a06e300bfd) | Apr 12, 2022 |
| ASUSTek       | X541UAK                     | [ffb5635168](https://linux-hardware.org/?probe=ffb5635168) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Dell          | Vostro 15 3515              | [5fea9b2c3a](https://linux-hardware.org/?probe=5fea9b2c3a) | Apr 08, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [d49b3ef408](https://linux-hardware.org/?probe=d49b3ef408) | Apr 08, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [9cbf0f3aad](https://linux-hardware.org/?probe=9cbf0f3aad) | Apr 04, 2022 |
| Lenovo        | G510 20238                  | [beeceac759](https://linux-hardware.org/?probe=beeceac759) | Apr 04, 2022 |
| Lenovo        | B590 37612LG                | [153a6c2343](https://linux-hardware.org/?probe=153a6c2343) | Apr 04, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| HP            | 250 G4                      | [69a3535c1a](https://linux-hardware.org/?probe=69a3535c1a) | Mar 30, 2022 |
| Acer          | Aspire 5920G                | [c2d3fbb93e](https://linux-hardware.org/?probe=c2d3fbb93e) | Mar 30, 2022 |
| Acer          | Swift SF314-511             | [ffde31bd20](https://linux-hardware.org/?probe=ffde31bd20) | Mar 26, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [a05a647662](https://linux-hardware.org/?probe=a05a647662) | Mar 25, 2022 |
| Dell          | Inspiron 15-3567            | [2bbea411a6](https://linux-hardware.org/?probe=2bbea411a6) | Mar 24, 2022 |
| Dell          | Inspiron 15-3567            | [c55e29b1e9](https://linux-hardware.org/?probe=c55e29b1e9) | Mar 22, 2022 |
| Gigabyte      | AERO 15 YD                  | [ce6cc28ca1](https://linux-hardware.org/?probe=ce6cc28ca1) | Mar 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8d1c371df2](https://linux-hardware.org/?probe=8d1c371df2) | Mar 21, 2022 |
| Gigabyte      | AERO 15 YD                  | [35da4bbe2c](https://linux-hardware.org/?probe=35da4bbe2c) | Mar 21, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [626ee37f9b](https://linux-hardware.org/?probe=626ee37f9b) | Mar 21, 2022 |
| Acer          | Swift SF314-57              | [a93c59159d](https://linux-hardware.org/?probe=a93c59159d) | Mar 20, 2022 |
| Acer          | Swift SF514-55GT            | [ae09c5da41](https://linux-hardware.org/?probe=ae09c5da41) | Mar 20, 2022 |
| Acer          | Swift SF114-33              | [7e8098be12](https://linux-hardware.org/?probe=7e8098be12) | Mar 20, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [b8b480e048](https://linux-hardware.org/?probe=b8b480e048) | Mar 20, 2022 |
| Dell          | Inspiron 3583               | [a3a8154156](https://linux-hardware.org/?probe=a3a8154156) | Mar 17, 2022 |
| HP            | ProBook 450 G2              | [177d9b8820](https://linux-hardware.org/?probe=177d9b8820) | Mar 16, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Romania/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 143       | 8.58%   |
| Ubuntu 22.04                 | 92        | 5.52%   |
| Ubuntu 18.04                 | 66        | 3.96%   |
| Arch Rolling                 | 34        | 2.04%   |
| Fedora 39                    | 30        | 1.8%    |
| BlackPanther 18.1            | 30        | 1.8%    |
| OpenMandriva 4.3             | 29        | 1.74%   |
| Debian 12                    | 26        | 1.56%   |
| Manjaro                      | 25        | 1.5%    |
| Pop!_OS 22.04                | 23        | 1.38%   |
| OpenMandriva 4.2             | 23        | 1.38%   |
| openSUSE Tumbleweed-XXXXXXXX | 21        | 1.26%   |
| Zorin 16                     | 20        | 1.2%    |
| Pop!_OS 21.04                | 19        | 1.14%   |
| Debian 11                    | 19        | 1.14%   |
| ArcoLinux Rolling            | 19        | 1.14%   |
| Ubuntu 21.10                 | 18        | 1.08%   |
| Fedora 40                    | 18        | 1.08%   |
| Ubuntu 24.04                 | 17        | 1.02%   |
| OpenMandriva 23.08           | 17        | 1.02%   |
| KDE neon 20.04               | 17        | 1.02%   |
| Arch                         | 17        | 1.02%   |
| ROSA R10                     | 16        | 0.96%   |
| Linux Mint 21.2              | 16        | 0.96%   |
| Endless 3.7.8                | 16        | 0.96%   |
| Zorin 15                     | 15        | 0.9%    |
| Linux Mint 21.1              | 15        | 0.9%    |
| Endless 3.9.5                | 15        | 0.9%    |
| Endless 3.9.1                | 15        | 0.9%    |
| Fedora 38                    | 14        | 0.84%   |
| Zorin 17                     | 13        | 0.78%   |
| Pop!_OS 20.04                | 13        | 0.78%   |
| Ubuntu 23.04                 | 12        | 0.72%   |
| Endless 3.8.6                | 12        | 0.72%   |
| Endless 3.8.0                | 12        | 0.72%   |
| Linux Mint 20.3              | 11        | 0.66%   |
| Fedora 35                    | 11        | 0.66%   |
| Ubuntu 23.10                 | 10        | 0.6%    |
| Ubuntu 20.10                 | 10        | 0.6%    |
| Ubuntu 19.10                 | 10        | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 400       | 25.87%  |
| Endless      | 213       | 13.78%  |
| Fedora       | 117       | 7.57%   |
| OpenMandriva | 104       | 6.73%   |
| Linux Mint   | 102       | 6.6%    |
| Pop!_OS      | 66        | 4.27%   |
| Debian       | 57        | 3.69%   |
| Arch         | 50        | 3.23%   |
| Zorin        | 49        | 3.17%   |
| Manjaro      | 45        | 2.91%   |
| ROSA         | 35        | 2.26%   |
| BlackPanther | 32        | 2.07%   |
| openSUSE     | 25        | 1.62%   |
| Kubuntu      | 25        | 1.62%   |
| KDE neon     | 25        | 1.62%   |
| ArcoLinux    | 21        | 1.36%   |
| Xubuntu      | 18        | 1.16%   |
| Kali         | 13        | 0.84%   |
| Elementary   | 12        | 0.78%   |
| Ubuntu Unity | 11        | 0.71%   |
| EndeavourOS  | 11        | 0.71%   |
| SteamOS      | 10        | 0.65%   |
| MX           | 9         | 0.58%   |
| Gentoo       | 9         | 0.58%   |
| Ubuntu MATE  | 8         | 0.52%   |
| Clear Linux  | 8         | 0.52%   |
| Lubuntu      | 7         | 0.45%   |
| LMDE         | 6         | 0.39%   |
| Garuda Linux | 6         | 0.39%   |
| NixOS        | 5         | 0.32%   |
| Linux Lite   | 5         | 0.32%   |
| RHEL         | 4         | 0.26%   |
| Peppermint   | 4         | 0.26%   |
| Nobara       | 4         | 0.26%   |
| Artix        | 4         | 0.26%   |
| Xero         | 2         | 0.13%   |
| Slackware    | 2         | 0.13%   |
| Q4OS         | 2         | 0.13%   |
| Mageia       | 2         | 0.13%   |
| Void Linux   | 1         | 0.06%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.8.0-14-generic         | 56        | 3.21%   |
| 5.4.0-42-generic         | 39        | 2.24%   |
| 5.4.0-19-generic         | 26        | 1.49%   |
| 5.16.7-desktop-1omv4003  | 25        | 1.43%   |
| 5.10.14-desktop-1omv4002 | 23        | 1.32%   |
| 5.3.0-28-generic         | 21        | 1.2%    |
| 4.18.16-desktop-1bP      | 21        | 1.2%    |
| 5.11.0-35-generic        | 16        | 0.92%   |
| 4.18.0-15-generic        | 14        | 0.8%    |
| 5.3.0-23-generic         | 13        | 0.75%   |
| 5.0.0-25-generic         | 13        | 0.75%   |
| 6.4.11-desktop-1omv2390  | 12        | 0.69%   |
| 5.0.0-20-generic         | 10        | 0.57%   |
| 4.15.0-15-generic        | 10        | 0.57%   |
| 6.1.1-desktop-1omv2290   | 9         | 0.52%   |
| 6.2.6-desktop-1omv2390   | 8         | 0.46%   |
| 5.6.14-desktop-2bP       | 8         | 0.46%   |
| 5.3.0-46-generic         | 8         | 0.46%   |
| 5.15.0-56-generic        | 8         | 0.46%   |
| 5.15.0-52-generic        | 8         | 0.46%   |
| 5.13.0-7614-generic      | 8         | 0.46%   |
| 5.0.0-37-generic         | 8         | 0.46%   |
| 5.8.0-50-generic         | 7         | 0.4%    |
| 5.4.0-56-generic         | 7         | 0.4%    |
| 5.4.0-54-generic         | 7         | 0.4%    |
| 5.4.0-40-generic         | 7         | 0.4%    |
| 5.4.0-26-generic         | 7         | 0.4%    |
| 5.3.0-51-generic         | 7         | 0.4%    |
| 5.3.0-19-generic         | 7         | 0.4%    |
| 5.3.0-12-generic         | 7         | 0.4%    |
| 5.19.0-32-generic        | 7         | 0.4%    |
| 5.15.0-71-generic        | 7         | 0.4%    |
| 5.15.0-48-generic        | 7         | 0.4%    |
| 5.11.0-7620-generic      | 7         | 0.4%    |
| 5.0.0-7-generic          | 7         | 0.4%    |
| 6.8.0-45-generic         | 6         | 0.34%   |
| 6.8.0-31-generic         | 6         | 0.34%   |
| 6.5.11-300.fc39.x86_64   | 6         | 0.34%   |
| 6.5.0-21-generic         | 6         | 0.34%   |
| 6.2.0-36-generic         | 6         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 203       | 12.06%  |
| 5.15.0  | 117       | 6.95%   |
| 5.8.0   | 108       | 6.42%   |
| 5.3.0   | 87        | 5.17%   |
| 5.11.0  | 69        | 4.1%    |
| 5.0.0   | 63        | 3.74%   |
| 4.15.0  | 59        | 3.51%   |
| 6.5.0   | 54        | 3.21%   |
| 5.13.0  | 54        | 3.21%   |
| 6.8.0   | 48        | 2.85%   |
| 4.18.0  | 40        | 2.38%   |
| 6.2.0   | 39        | 2.32%   |
| 6.1.0   | 35        | 2.08%   |
| 5.19.0  | 33        | 1.96%   |
| 5.10.0  | 26        | 1.54%   |
| 5.16.7  | 25        | 1.49%   |
| 5.10.14 | 24        | 1.43%   |
| 4.18.16 | 21        | 1.25%   |
| 6.4.11  | 14        | 0.83%   |
| 6.2.6   | 13        | 0.77%   |
| 6.1.1   | 11        | 0.65%   |
| 6.9.3   | 9         | 0.53%   |
| 5.6.14  | 9         | 0.53%   |
| 6.6.2   | 8         | 0.48%   |
| 6.5.6   | 8         | 0.48%   |
| 4.9.60  | 8         | 0.48%   |
| 4.9.20  | 8         | 0.48%   |
| 4.13.0  | 8         | 0.48%   |
| 6.5.5   | 7         | 0.42%   |
| 6.4.8   | 7         | 0.42%   |
| 6.11.0  | 7         | 0.42%   |
| 6.5.9   | 6         | 0.36%   |
| 6.5.11  | 6         | 0.36%   |
| 6.1.12  | 6         | 0.36%   |
| 5.14.0  | 6         | 0.36%   |
| 4.19.0  | 6         | 0.36%   |
| 6.3.5   | 5         | 0.3%    |
| 6.11.3  | 5         | 0.3%    |
| 6.10.3  | 5         | 0.3%    |
| 5.17.0  | 5         | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 209       | 12.52%  |
| 5.15    | 146       | 8.75%   |
| 5.8     | 121       | 7.25%   |
| 5.3     | 94        | 5.63%   |
| 6.5     | 85        | 5.09%   |
| 5.11    | 79        | 4.73%   |
| 6.1     | 76        | 4.55%   |
| 6.8     | 65        | 3.89%   |
| 5.10    | 65        | 3.89%   |
| 5.0     | 65        | 3.89%   |
| 6.2     | 63        | 3.77%   |
| 4.18    | 63        | 3.77%   |
| 4.15    | 59        | 3.54%   |
| 5.13    | 58        | 3.48%   |
| 5.19    | 47        | 2.82%   |
| 5.16    | 43        | 2.58%   |
| 6.6     | 39        | 2.34%   |
| 4.9     | 27        | 1.62%   |
| 6.4     | 25        | 1.5%    |
| 6.9     | 24        | 1.44%   |
| 6.11    | 19        | 1.14%   |
| 6.10    | 18        | 1.08%   |
| 6.0     | 18        | 1.08%   |
| 5.6     | 17        | 1.02%   |
| 5.9     | 15        | 0.9%    |
| 5.17    | 15        | 0.9%    |
| 6.3     | 14        | 0.84%   |
| 5.18    | 14        | 0.84%   |
| 6.7     | 13        | 0.78%   |
| 5.14    | 13        | 0.78%   |
| 5.12    | 10        | 0.6%    |
| 6.12    | 9         | 0.54%   |
| 4.13    | 8         | 0.48%   |
| 4.19    | 7         | 0.42%   |
| 5.7     | 6         | 0.36%   |
| 5.5     | 5         | 0.3%    |
| 5.1     | 3         | 0.18%   |
| 4.1     | 3         | 0.18%   |
| 5.2     | 2         | 0.12%   |
| 4.12    | 2         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1445      | 97.83%  |
| i686   | 31        | 2.1%    |
| armv7l | 1         | 0.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 754       | 48.83%  |
| KDE5            | 257       | 16.65%  |
| Unknown         | 163       | 10.56%  |
| XFCE            | 96        | 6.22%   |
| X-Cinnamon      | 88        | 5.7%    |
| KDE4            | 24        | 1.55%   |
| KDE             | 23        | 1.49%   |
| MATE            | 22        | 1.42%   |
| KDE6            | 21        | 1.36%   |
| LXQt            | 14        | 0.91%   |
| Unity           | 11        | 0.71%   |
| Pantheon        | 11        | 0.71%   |
| Cinnamon        | 9         | 0.58%   |
| LXDE            | 8         | 0.52%   |
| i3              | 7         | 0.45%   |
| Hyprland        | 6         | 0.39%   |
| sway            | 5         | 0.32%   |
| Endless:GNOME   | 4         | 0.26%   |
| GNOME Classic   | 3         | 0.19%   |
| Budgie          | 3         | 0.19%   |
| xmonad          | 2         | 0.13%   |
| DWM             | 2         | 0.13%   |
| Deepin          | 2         | 0.13%   |
| ubuntu          | 1         | 0.06%   |
| qtile           | 1         | 0.06%   |
| jwm             | 1         | 0.06%   |
| i3-with-shmlog  | 1         | 0.06%   |
| GNOME Flashback | 1         | 0.06%   |
| Enlightenment   | 1         | 0.06%   |
| COSMIC          | 1         | 0.06%   |
| bspwm           | 1         | 0.06%   |
| awesome         | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1060      | 69.6%   |
| Wayland | 336       | 22.06%  |
| Unknown | 110       | 7.22%   |
| Tty     | 17        | 1.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 764       | 49.51%  |
| SDDM    | 244       | 15.81%  |
| GDM3    | 186       | 12.05%  |
| GDM     | 153       | 9.92%   |
| LightDM | 141       | 9.14%   |
| TDM     | 24        | 1.56%   |
| KDM     | 23        | 1.49%   |
| XDM     | 4         | 0.26%   |
| SLiM    | 3         | 0.19%   |
| GREETD  | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 976       | 64.04%  |
| ro_RO       | 234       | 15.35%  |
| Unknown     | 197       | 12.93%  |
| en_GB       | 33        | 2.17%   |
| C           | 26        | 1.71%   |
| hu_HU       | 12        | 0.79%   |
| it_IT       | 10        | 0.66%   |
| fr_FR       | 8         | 0.52%   |
| es_ES       | 7         | 0.46%   |
| de_DE       | 4         | 0.26%   |
| en_IL       | 3         | 0.2%    |
| C.UTF8      | 2         | 0.13%   |
| uk_UA       | 1         | 0.07%   |
| ru_RU       | 1         | 0.07%   |
| POSIX       | 1         | 0.07%   |
| fr_CH       | 1         | 0.07%   |
| en_US.UTF.8 | 1         | 0.07%   |
| en_IN       | 1         | 0.07%   |
| en_IE       | 1         | 0.07%   |
| en_DK       | 1         | 0.07%   |
| en_CA       | 1         | 0.07%   |
| en_AG       | 1         | 0.07%   |
| en_001      | 1         | 0.07%   |
| de_IT       | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 871       | 57.49%  |
| BIOS | 644       | 42.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 1053      | 69.23%  |
| Btrfs    | 165       | 10.85%  |
| Overlay  | 120       | 7.89%   |
| Unknown  | 110       | 7.23%   |
| Tmpfs    | 53        | 3.48%   |
| Xfs      | 9         | 0.59%   |
| Zfs      | 6         | 0.39%   |
| F2fs     | 2         | 0.13%   |
| Ext2     | 2         | 0.13%   |
| Bcachefs | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 787       | 52.15%  |
| GPT     | 564       | 37.38%  |
| MBR     | 158       | 10.47%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1336      | 89.19%  |
| Yes       | 162       | 10.81%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1116      | 74.35%  |
| Yes       | 385       | 25.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 405       | 27.44%  |
| Lenovo              | 336       | 22.76%  |
| Hewlett-Packard     | 204       | 13.82%  |
| Dell                | 185       | 12.53%  |
| Acer                | 138       | 9.35%   |
| Toshiba             | 32        | 2.17%   |
| MSI                 | 19        | 1.29%   |
| Sony                | 13        | 0.88%   |
| HUAWEI              | 13        | 0.88%   |
| Complet             | 11        | 0.75%   |
| Apple               | 11        | 0.75%   |
| Valve               | 10        | 0.68%   |
| Allview             | 9         | 0.61%   |
| Medion              | 8         | 0.54%   |
| Fujitsu Siemens     | 8         | 0.54%   |
| Samsung Electronics | 7         | 0.47%   |
| Fujitsu             | 6         | 0.41%   |
| Unknown             | 6         | 0.41%   |
| Google              | 5         | 0.34%   |
| Chuwi               | 5         | 0.34%   |
| Alienware           | 4         | 0.27%   |
| TUXEDO              | 3         | 0.2%    |
| Packard Bell        | 3         | 0.2%    |
| Timi                | 2         | 0.14%   |
| Jumper              | 2         | 0.14%   |
| WEIGO               | 1         | 0.07%   |
| Visual Fan          | 1         | 0.07%   |
| VALE                | 1         | 0.07%   |
| Thomson             | 1         | 0.07%   |
| System76            | 1         | 0.07%   |
| SLIMBOOK            | 1         | 0.07%   |
| Schenker            | 1         | 0.07%   |
| Razer               | 1         | 0.07%   |
| Prestigio           | 1         | 0.07%   |
| Pegatron            | 1         | 0.07%   |
| PC Specialist       | 1         | 0.07%   |
| Panasonic           | 1         | 0.07%   |
| Notebook            | 1         | 0.07%   |
| nJoy Romania        | 1         | 0.07%   |
| Neousys Technology  | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 18        | 1.22%   |
| ASUS X541NA                                | 17        | 1.15%   |
| ASUS VivoBook_ASUSLaptop X509FA_X509FA     | 10        | 0.68%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 10        | 0.68%   |
| Valve Jupiter                              | 9         | 0.61%   |
| Unknown                                    | 9         | 0.61%   |
| Dell XPS 15 9530                           | 8         | 0.54%   |
| ASUS X541UVK                               | 8         | 0.54%   |
| Lenovo Legion Y530-15ICH 81FV              | 7         | 0.47%   |
| Complet MY8312                             | 7         | 0.47%   |
| ASUS X541UAK                               | 7         | 0.47%   |
| ASUS X406UAR                               | 7         | 0.47%   |
| ASUS VivoBook_ASUSLaptop X509FB_X509FB     | 6         | 0.41%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_A540MA | 6         | 0.41%   |
| Lenovo V330-15IKB 81AX                     | 5         | 0.34%   |
| HP Notebook                                | 5         | 0.34%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA     | 5         | 0.34%   |
| ASUS VivoBook_ASUSLaptop X509DAP_M509DA    | 5         | 0.34%   |
| ASUS VivoBook_ASUS Laptop X505ZA_A505ZA    | 5         | 0.34%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 5         | 0.34%   |
| ASUS GL552JX                               | 5         | 0.34%   |
| Allview Allbook H                          | 5         | 0.34%   |
| Acer Aspire A315-21G                       | 5         | 0.34%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 4         | 0.27%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5           | 4         | 0.27%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 4         | 0.27%   |
| Lenovo IdeaPad 100-15IBD 80QQ              | 4         | 0.27%   |
| Lenovo G510 20238                          | 4         | 0.27%   |
| HP ProBook 450 G5                          | 4         | 0.27%   |
| HP Pavilion Notebook                       | 4         | 0.27%   |
| HP EliteBook 840 G6                        | 4         | 0.27%   |
| Dell Latitude E6420                        | 4         | 0.27%   |
| Dell Latitude E6410                        | 4         | 0.27%   |
| Dell Inspiron 5558                         | 4         | 0.27%   |
| Dell Inspiron 1545                         | 4         | 0.27%   |
| ASUS ZenBook UX431DA_UM431DA               | 4         | 0.27%   |
| ASUS X542UAR                               | 4         | 0.27%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA     | 4         | 0.27%   |
| ASUS VivoBook_ASUSLaptop X513EA_K513EA     | 4         | 0.27%   |
| ASUS VivoBook_ASUSLaptop X403FA_X403FA     | 4         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| ASUS VivoBook     | 147       | 9.96%   |
| Lenovo ThinkPad   | 118       | 7.99%   |
| Lenovo IdeaPad    | 107       | 7.25%   |
| Acer Aspire       | 100       | 6.78%   |
| Dell Latitude     | 64        | 4.34%   |
| Dell Inspiron     | 55        | 3.73%   |
| HP EliteBook      | 42        | 2.85%   |
| Lenovo Legion     | 38        | 2.57%   |
| HP ProBook        | 36        | 2.44%   |
| ASUS ASUS         | 32        | 2.17%   |
| Toshiba Satellite | 31        | 2.1%    |
| HP Pavilion       | 28        | 1.9%    |
| ASUS ROG          | 27        | 1.83%   |
| Dell XPS          | 22        | 1.49%   |
| HP Laptop         | 20        | 1.36%   |
| ASUS X541NA       | 17        | 1.15%   |
| ASUS ZenBook      | 16        | 1.08%   |
| Lenovo ThinkBook  | 13        | 0.88%   |
| HP 250            | 13        | 0.88%   |
| Dell Precision    | 13        | 0.88%   |
| Dell Vostro       | 12        | 0.81%   |
| HP ZBook          | 11        | 0.75%   |
| ASUS TUF          | 11        | 0.75%   |
| Valve Jupiter     | 9         | 0.61%   |
| HP OMEN           | 9         | 0.61%   |
| Allview Allbook   | 9         | 0.61%   |
| Unknown           | 9         | 0.61%   |
| Lenovo Yoga       | 8         | 0.54%   |
| ASUS X541UVK      | 8         | 0.54%   |
| Acer Swift        | 8         | 0.54%   |
| Acer Nitro        | 8         | 0.54%   |
| HP Compaq         | 7         | 0.47%   |
| Dell System       | 7         | 0.47%   |
| Complet MY8312    | 7         | 0.47%   |
| ASUS X541UAK      | 7         | 0.47%   |
| ASUS X406UAR      | 7         | 0.47%   |
| Acer Extensa      | 7         | 0.47%   |
| HP ENVY           | 6         | 0.41%   |
| Fujitsu LIFEBOOK  | 6         | 0.41%   |
| Lenovo V330-15IKB | 5         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 190       | 12.87%  |
| 2018    | 143       | 9.69%   |
| 2020    | 129       | 8.74%   |
| 2017    | 125       | 8.47%   |
| 2021    | 116       | 7.86%   |
| 2015    | 90        | 6.1%    |
| 2013    | 81        | 5.49%   |
| 2011    | 80        | 5.42%   |
| 2012    | 72        | 4.88%   |
| 2022    | 69        | 4.67%   |
| 2014    | 69        | 4.67%   |
| 2010    | 62        | 4.2%    |
| 2016    | 58        | 3.93%   |
| 2023    | 53        | 3.59%   |
| 2008    | 37        | 2.51%   |
| 2007    | 34        | 2.3%    |
| 2009    | 30        | 2.03%   |
| 2024    | 18        | 1.22%   |
| 2006    | 15        | 1.02%   |
| Unknown | 3         | 0.2%    |
| 2005    | 1         | 0.07%   |
| 2004    | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1476      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1387      | 93.34%  |
| Enabled  | 99        | 6.66%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1471      | 99.66%  |
| Yes  | 5         | 0.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 397       | 26.54%  |
| 3.01-4.0    | 395       | 26.4%   |
| 8.01-16.0   | 264       | 17.65%  |
| 16.01-24.0  | 222       | 14.84%  |
| 32.01-64.0  | 103       | 6.89%   |
| 1.01-2.0    | 54        | 3.61%   |
| 24.01-32.0  | 22        | 1.47%   |
| 2.01-3.0    | 15        | 1%      |
| 64.01-256.0 | 13        | 0.87%   |
| 0.51-1.0    | 11        | 0.74%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 567       | 34.26%  |
| 2.01-3.0   | 446       | 26.95%  |
| 4.01-8.0   | 220       | 13.29%  |
| 3.01-4.0   | 209       | 12.63%  |
| 0.51-1.0   | 137       | 8.28%   |
| 8.01-16.0  | 54        | 3.26%   |
| 0.01-0.5   | 13        | 0.79%   |
| 24.01-32.0 | 4         | 0.24%   |
| 16.01-24.0 | 4         | 0.24%   |
| 32.01-64.0 | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1141      | 75.97%  |
| 2      | 309       | 20.57%  |
| 3      | 42        | 2.8%    |
| 0      | 6         | 0.4%    |
| 4      | 3         | 0.2%    |
| 5      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 990       | 66.71%  |
| Yes       | 494       | 33.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1117      | 75.42%  |
| No        | 364       | 24.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1441      | 97.5%   |
| No        | 37        | 2.5%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1212      | 81.18%  |
| No        | 281       | 18.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Romania | 1476      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Bucharest             | 495       | 31.41%  |
| Cluj-Napoca           | 97        | 6.15%   |
| Iasi                  | 76        | 4.82%   |
| Timișoara            | 58        | 3.68%   |
| Brasov                | 46        | 2.92%   |
| Ploieşti             | 43        | 2.73%   |
| Târgu Mureş         | 42        | 2.66%   |
| Constanța            | 34        | 2.16%   |
| Sibiu                 | 27        | 1.71%   |
| Piteşti              | 25        | 1.59%   |
| Arad                  | 22        | 1.4%    |
| Oradea                | 20        | 1.27%   |
| Craiova               | 20        | 1.27%   |
| Popesti-Leordeni      | 16        | 1.02%   |
| Galati                | 16        | 1.02%   |
| Râmnicu Vâlcea      | 15        | 0.95%   |
| Baia Mare             | 15        | 0.95%   |
| Voluntari             | 14        | 0.89%   |
| Miercurea-Ciuc        | 13        | 0.82%   |
| Botosani              | 13        | 0.82%   |
| Bacau                 | 12        | 0.76%   |
| Zalău                | 11        | 0.7%    |
| Floresti              | 11        | 0.7%    |
| Buzau                 | 11        | 0.7%    |
| Mediaş               | 10        | 0.63%   |
| Deva                  | 10        | 0.63%   |
| Targoviste            | 9         | 0.57%   |
| Reşiţa              | 9         | 0.57%   |
| Tulcea                | 8         | 0.51%   |
| Suceava               | 8         | 0.51%   |
| Roman                 | 8         | 0.51%   |
| Focşani              | 8         | 0.51%   |
| Braila                | 8         | 0.51%   |
| Alba Iulia            | 8         | 0.51%   |
| Târgu Jiu            | 7         | 0.44%   |
| Slatina               | 7         | 0.44%   |
| Sighetu Marmaţiei    | 7         | 0.44%   |
| Mangalia              | 7         | 0.44%   |
| Drobeta-Turnu Severin | 6         | 0.38%   |
| Bistriţa             | 6         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 271       | 361    | 14.91%  |
| Seagate                     | 199       | 267    | 10.95%  |
| WDC                         | 183       | 221    | 10.07%  |
| Kingston                    | 172       | 214    | 9.46%   |
| Toshiba                     | 143       | 173    | 7.87%   |
| SanDisk                     | 117       | 134    | 6.44%   |
| SK hynix                    | 89        | 121    | 4.9%    |
| Unknown                     | 82        | 106    | 4.51%   |
| Intel                       | 77        | 101    | 4.24%   |
| Micron Technology           | 72        | 98     | 3.96%   |
| A-DATA Technology           | 61        | 72     | 3.36%   |
| HGST                        | 54        | 65     | 2.97%   |
| Hitachi                     | 41        | 44     | 2.26%   |
| KIOXIA                      | 20        | 21     | 1.1%    |
| Crucial                     | 19        | 25     | 1.05%   |
| Kingston Technology Company | 18        | 20     | 0.99%   |
| Phison                      | 10        | 11     | 0.55%   |
| Patriot                     | 10        | 10     | 0.55%   |
| SPCC                        | 9         | 10     | 0.5%    |
| Netac                       | 9         | 11     | 0.5%    |
| Fujitsu                     | 9         | 11     | 0.5%    |
| FORESEE                     | 9         | 10     | 0.5%    |
| Phison Electronics          | 7         | 7      | 0.39%   |
| Hewlett-Packard             | 7         | 7      | 0.39%   |
| Corsair                     | 6         | 7      | 0.33%   |
| ADATA Technology            | 6         | 7      | 0.33%   |
| Unknown                     | 6         | 6      | 0.33%   |
| Realtek Semiconductor       | 5         | 5      | 0.28%   |
| LITEON                      | 5         | 5      | 0.28%   |
| Gigabyte Technology         | 5         | 5      | 0.28%   |
| China                       | 5         | 5      | 0.28%   |
| Apple                       | 5         | 5      | 0.28%   |
| XPG                         | 4         | 5      | 0.22%   |
| OCZ                         | 4         | 6      | 0.22%   |
| ASMT                        | 4         | 4      | 0.22%   |
| Transcend                   | 3         | 4      | 0.17%   |
| Silicon Motion              | 3         | 4      | 0.17%   |
| Kingmax                     | 3         | 3      | 0.17%   |
| Intenso                     | 3         | 3      | 0.17%   |
| GOODRAM                     | 3         | 3      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                             | 47        | 2.5%    |
| Seagate ST1000LM035-1RK172 1TB                       | 44        | 2.34%   |
| Seagate ST500LT012-1DG142 500GB                      | 32        | 1.7%    |
| Kingston SA400S37240G 240GB SSD                      | 31        | 1.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 29        | 1.54%   |
| Toshiba MQ04ABF100 1TB                               | 23        | 1.22%   |
| HGST HTS721010A9E630 1TB                             | 22        | 1.17%   |
| Unknown MMC Card  32GB                               | 21        | 1.12%   |
| Kingston SA400S37480G 480GB SSD                      | 20        | 1.06%   |
| SanDisk NVMe SSD Drive 512GB                         | 19        | 1.01%   |
| Toshiba MQ01ABD100 1TB                               | 17        | 0.9%    |
| SanDisk NVMe SSD Drive 256GB                         | 17        | 0.9%    |
| Samsung NVMe SSD Drive 512GB                         | 17        | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 14        | 0.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 14        | 0.74%   |
| SK hynix NVMe SSD Drive 512GB                        | 11        | 0.58%   |
| SK hynix HFS256G39TND-N210A 256GB SSD                | 11        | 0.58%   |
| Kingston SV300S37A240G 240GB SSD                     | 11        | 0.58%   |
| HGST HTS545050A7E680 500GB                           | 11        | 0.58%   |
| Kingston Company SNV2S1000G 1TB                      | 10        | 0.53%   |
| Intel NVMe SSD Drive 512GB                           | 10        | 0.53%   |
| WDC WD10SPZX-21Z10T0 1TB                             | 9         | 0.48%   |
| SK hynix HFM001TD3JX013N 1024GB                      | 9         | 0.48%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                 | 9         | 0.48%   |
| SanDisk NVMe SSD Drive 1TB                           | 9         | 0.48%   |
| Samsung SSD 860 EVO 500GB                            | 9         | 0.48%   |
| Samsung NVMe SSD Drive 256GB                         | 9         | 0.48%   |
| Kingston SA400S37120G 120GB SSD                      | 9         | 0.48%   |
| HGST HTS541010A9E680 1TB                             | 9         | 0.48%   |
| WDC WD10JPCX-24UE4T0 1TB                             | 8         | 0.43%   |
| Unknown MMC Card  64GB                               | 8         | 0.43%   |
| Seagate Expansion 1TB                                | 8         | 0.43%   |
| Samsung SSD 850 EVO 250GB                            | 8         | 0.43%   |
| Netac SSD 256GB                                      | 8         | 0.43%   |
| Kingston SV300S37A120G 120GB SSD                     | 8         | 0.43%   |
| Kingston SUV500MS480G 480GB SSD                      | 8         | 0.43%   |
| Kingston RBUSNS8180DS3256GJ 256GB SSD                | 8         | 0.43%   |
| Intel SSDPEKNU512GZ 512GB                            | 8         | 0.43%   |
| A-DATA SU650 240GB SSD                               | 8         | 0.43%   |
| Unknown NVMe SSD Drive 512GB                         | 7         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 195       | 263    | 34.88%  |
| WDC                 | 124       | 150    | 22.18%  |
| Toshiba             | 116       | 142    | 20.75%  |
| HGST                | 54        | 65     | 9.66%   |
| Hitachi             | 41        | 44     | 7.33%   |
| Fujitsu             | 9         | 11     | 1.61%   |
| Samsung Electronics | 5         | 6      | 0.89%   |
| Unknown             | 3         | 3      | 0.54%   |
| ASMT                | 3         | 3      | 0.54%   |
| TO Exter            | 2         | 4      | 0.36%   |
| IBM/Hitachi         | 2         | 2      | 0.36%   |
| XrayDisk            | 1         | 1      | 0.18%   |
| SABRENT             | 1         | 1      | 0.18%   |
| HGST HTS            | 1         | 1      | 0.18%   |
| External            | 1         | 1      | 0.18%   |
| Apple               | 1         | 1      | 0.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 144       | 183    | 26.42%  |
| Samsung Electronics | 94        | 127    | 17.25%  |
| A-DATA Technology   | 53        | 64     | 9.72%   |
| SanDisk             | 37        | 45     | 6.79%   |
| SK hynix            | 24        | 36     | 4.4%    |
| Micron Technology   | 22        | 27     | 4.04%   |
| WDC                 | 18        | 18     | 3.3%    |
| Crucial             | 18        | 24     | 3.3%    |
| Intel               | 14        | 15     | 2.57%   |
| SPCC                | 9         | 10     | 1.65%   |
| Patriot             | 9         | 9      | 1.65%   |
| Netac               | 9         | 11     | 1.65%   |
| FORESEE             | 9         | 10     | 1.65%   |
| Toshiba             | 7         | 7      | 1.28%   |
| Hewlett-Packard     | 7         | 7      | 1.28%   |
| LITEON              | 5         | 5      | 0.92%   |
| Gigabyte Technology | 5         | 5      | 0.92%   |
| Corsair             | 5         | 6      | 0.92%   |
| China               | 5         | 5      | 0.92%   |
| OCZ                 | 4         | 6      | 0.73%   |
| Transcend           | 3         | 4      | 0.55%   |
| Kingmax             | 3         | 3      | 0.55%   |
| Intenso             | 3         | 3      | 0.55%   |
| GOODRAM             | 3         | 3      | 0.55%   |
| Apacer              | 3         | 4      | 0.55%   |
| Verbatim            | 2         | 2      | 0.37%   |
| Teclast             | 2         | 2      | 0.37%   |
| LITEONIT            | 2         | 2      | 0.37%   |
| Lite-On             | 2         | 2      | 0.37%   |
| Emtec               | 2         | 2      | 0.37%   |
| XrayDisk            | 1         | 1      | 0.18%   |
| Wibtek              | 1         | 1      | 0.18%   |
| W800S               | 1         | 1      | 0.18%   |
| Unknown             | 1         | 1      | 0.18%   |
| sobetter            | 1         | 1      | 0.18%   |
| PNY                 | 1         | 2      | 0.18%   |
| Plextor             | 1         | 2      | 0.18%   |
| MicroFrom           | 1         | 1      | 0.18%   |
| Maxtor              | 1         | 1      | 0.18%   |
| M.2 2280            | 1         | 1      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 587       | 783    | 34.11%  |
| HDD     | 544       | 698    | 31.61%  |
| SSD     | 504       | 673    | 29.29%  |
| MMC     | 75        | 98     | 4.36%   |
| Unknown | 11        | 13     | 0.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 917       | 1325   | 56.15%  |
| NVMe | 587       | 782    | 35.95%  |
| MMC  | 75        | 98     | 4.59%   |
| SAS  | 54        | 60     | 3.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 693       | 934    | 67.68%  |
| 0.51-1.0   | 299       | 379    | 29.2%   |
| 1.01-2.0   | 29        | 55     | 2.83%   |
| 3.01-4.0   | 2         | 2      | 0.2%    |
| 10.01-20.0 | 1         | 1      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 434       | 27.56%  |
| 251-500        | 382       | 24.25%  |
| 501-1000       | 275       | 17.46%  |
| 1-20           | 138       | 8.76%   |
| 51-100         | 96        | 6.1%    |
| 1001-2000      | 93        | 5.9%    |
| 21-50          | 65        | 4.13%   |
| Unknown        | 39        | 2.48%   |
| More than 3000 | 27        | 1.71%   |
| 2001-3000      | 26        | 1.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 635       | 38.93%  |
| 21-50          | 355       | 21.77%  |
| 101-250        | 197       | 12.08%  |
| 51-100         | 181       | 11.1%   |
| 251-500        | 107       | 6.56%   |
| 501-1000       | 78        | 4.78%   |
| Unknown        | 39        | 2.39%   |
| 1001-2000      | 31        | 1.9%    |
| 2001-3000      | 5         | 0.31%   |
| More than 3000 | 3         | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Hitachi HTS725032A7E630 320GB            | 7         | 7      | 6.86%   |
| HGST HTS541010A9E680 1TB                 | 5         | 5      | 4.9%    |
| Seagate ST9500420AS 500GB                | 3         | 3      | 2.94%   |
| HGST HTS545050A7E680 500GB               | 3         | 3      | 2.94%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB SSD | 2         | 2      | 1.96%   |
| Toshiba MQ01ABF050 500GB                 | 2         | 2      | 1.96%   |
| Seagate ST95005620AS 500GB               | 2         | 5      | 1.96%   |
| Seagate ST9500325AS 500GB                | 2         | 2      | 1.96%   |
| Seagate ST9160821AS 160GB                | 2         | 2      | 1.96%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 3      | 1.96%   |
| Seagate ST500LM000-1EJ162 500GB          | 2         | 3      | 1.96%   |
| Seagate ST1000LX015-1U7172 1TB           | 2         | 2      | 1.96%   |
| Hitachi HTS545016B9A300 160GB            | 2         | 2      | 1.96%   |
| HGST HTS725050A7E630 500GB               | 2         | 2      | 1.96%   |
| HGST HTS721010A9E630 1TB                 | 2         | 2      | 1.96%   |
| XrayDisk 240GB SSD                       | 1         | 1      | 0.98%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 0.98%   |
| WDC WD7500BPVT-60HXZT3 752GB             | 1         | 2      | 0.98%   |
| WDC WD7500BPVT-22HXZT3 752GB             | 1         | 1      | 0.98%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 0.98%   |
| WDC WD5000BPKT-60PK4T0 500GB             | 1         | 2      | 0.98%   |
| WDC WD5000BEVT-60A0RT0 500GB             | 1         | 1      | 0.98%   |
| WDC WD3200BPVT-22JJ5T0 320GB             | 1         | 1      | 0.98%   |
| WDC WD1600BEVS-60RST0 160GB              | 1         | 2      | 0.98%   |
| WDC WD1600BEVS-08RST2 160GB              | 1         | 2      | 0.98%   |
| WDC WD1600BEVS-07RST0 160GB              | 1         | 1      | 0.98%   |
| WDC WD10SPZX-21Z10T0 1TB                 | 1         | 1      | 0.98%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 0.98%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 1         | 2      | 0.98%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1      | 0.98%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 0.98%   |
| Toshiba MK6476GSX 640GB                  | 1         | 1      | 0.98%   |
| Toshiba MK5076GSX 500GB                  | 1         | 1      | 0.98%   |
| Toshiba MK3252GSX 320GB                  | 1         | 2      | 0.98%   |
| Toshiba MK2556GSY 250GB                  | 1         | 1      | 0.98%   |
| Toshiba MK2035GSS 200GB                  | 1         | 1      | 0.98%   |
| Teclast 360GB A850 SSD                   | 1         | 1      | 0.98%   |
| SK hynix SC210 2.5 7MM 256GB SSD         | 1         | 1      | 0.98%   |
| SK hynix HFS256G3BTND-N210A 256GB SSD    | 1         | 1      | 0.98%   |
| SK hynix HFS256G39TND-N210A 256GB SSD    | 1         | 1      | 0.98%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 26     | 21.21%  |
| Hitachi             | 16        | 18     | 16.16%  |
| WDC                 | 14        | 20     | 14.14%  |
| HGST                | 13        | 13     | 13.13%  |
| Toshiba             | 9         | 10     | 9.09%   |
| SK hynix            | 6         | 7      | 6.06%   |
| Kingston            | 4         | 4      | 4.04%   |
| Fujitsu             | 3         | 3      | 3.03%   |
| Samsung Electronics | 2         | 2      | 2.02%   |
| Hewlett-Packard     | 2         | 2      | 2.02%   |
| XrayDisk            | 1         | 1      | 1.01%   |
| Teclast             | 1         | 1      | 1.01%   |
| SanDisk             | 1         | 1      | 1.01%   |
| Patriot             | 1         | 1      | 1.01%   |
| Micron Technology   | 1         | 1      | 1.01%   |
| LITEONIT            | 1         | 1      | 1.01%   |
| Intel               | 1         | 1      | 1.01%   |
| Dogfish             | 1         | 1      | 1.01%   |
| A-DATA Technology   | 1         | 1      | 1.01%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 21        | 26     | 28.77%  |
| Hitachi | 16        | 18     | 21.92%  |
| HGST    | 13        | 13     | 17.81%  |
| WDC     | 11        | 17     | 15.07%  |
| Toshiba | 9         | 10     | 12.33%  |
| Fujitsu | 3         | 3      | 4.11%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 73        | 87     | 73.74%  |
| SSD  | 25        | 26     | 25.25%  |
| NVMe | 1         | 1      | 1.01%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-60KA9T0 320GB | 1         | 1      | 50%     |
| WDC WD2500BEVS-22UST0 250GB  | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 926       | 1369   | 58.57%  |
| Works    | 555       | 780    | 35.1%   |
| Malfunc  | 98        | 114    | 6.2%    |
| Failed   | 2         | 2      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1063      | 58.99%  |
| Samsung Electronics              | 183       | 10.16%  |
| AMD                              | 155       | 8.6%    |
| SanDisk                          | 118       | 6.55%   |
| SK hynix                         | 64        | 3.55%   |
| Micron Technology                | 51        | 2.83%   |
| Kingston Technology Company      | 47        | 2.61%   |
| KIOXIA                           | 22        | 1.22%   |
| Toshiba America Info Systems     | 20        | 1.11%   |
| Phison Electronics               | 16        | 0.89%   |
| ADATA Technology                 | 14        | 0.78%   |
| Realtek Semiconductor            | 9         | 0.5%    |
| Solidigm                         | 6         | 0.33%   |
| Silicon Integrated Systems [SiS] | 5         | 0.28%   |
| Silicon Motion                   | 4         | 0.22%   |
| Nvidia                           | 4         | 0.22%   |
| Seagate Technology               | 3         | 0.17%   |
| Micron/Crucial Technology        | 3         | 0.17%   |
| Union Memory (Shenzhen)          | 2         | 0.11%   |
| Solid State Storage Technology   | 2         | 0.11%   |
| Lenovo                           | 2         | 0.11%   |
| JMicron Technology               | 2         | 0.11%   |
| Yangtze Memory Technologies      | 1         | 0.06%   |
| VIA Technologies                 | 1         | 0.06%   |
| Silicon Image                    | 1         | 0.06%   |
| Shenzhen Longsys Electronics     | 1         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.06%   |
| Lite-On Technology               | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 138       | 7.08%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 125       | 6.42%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 99        | 5.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 78        | 4%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 77        | 3.95%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 65        | 3.34%   |
| Intel Volume Management Device NVMe RAID Controller                              | 64        | 3.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 61        | 3.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 56        | 2.87%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 53        | 2.72%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 50        | 2.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 41        | 2.1%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 39        | 2%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 39        | 2%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 36        | 1.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 33        | 1.69%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 30        | 1.54%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 29        | 1.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 27        | 1.39%   |
| Intel Tiger Lake-LP SATA Controller                                              | 26        | 1.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 26        | 1.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 26        | 1.33%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 24        | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 24        | 1.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 24        | 1.23%   |
| Intel SSD 660P Series                                                            | 23        | 1.18%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 20        | 1.03%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 18        | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                            | 18        | 0.92%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 17        | 0.87%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 16        | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 15        | 0.77%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 14        | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 13        | 0.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 12        | 0.62%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 11        | 0.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 11        | 0.56%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 11        | 0.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 11        | 0.56%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 10        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1011      | 54.21%  |
| NVMe | 589       | 31.58%  |
| RAID | 176       | 9.44%   |
| IDE  | 89        | 4.77%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1197      | 81.1%   |
| AMD    | 278       | 18.83%  |
| ARM    | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 44        | 2.98%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 30        | 2.03%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 28        | 1.89%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 27        | 1.83%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 22        | 1.49%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 20        | 1.35%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 18        | 1.22%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 18        | 1.22%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 17        | 1.15%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 17        | 1.15%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 17        | 1.15%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 17        | 1.15%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 16        | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 1.08%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 16        | 1.08%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 15        | 1.01%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 14        | 0.95%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 13        | 0.88%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 12        | 0.81%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 12        | 0.81%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 12        | 0.81%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 12        | 0.81%   |
| Intel 12th Gen Core i5-1235U                  | 11        | 0.74%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 10        | 0.68%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 10        | 0.68%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 10        | 0.68%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 10        | 0.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 10        | 0.68%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 0.68%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 10        | 0.68%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 10        | 0.68%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 10        | 0.68%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 10        | 0.68%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 10        | 0.68%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 0.61%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 9         | 0.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 9         | 0.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 9         | 0.61%   |
| AMD Custom APU 0405                           | 9         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 322       | 21.79%  |
| Intel Core i5                  | 278       | 18.81%  |
| Other                          | 151       | 10.22%  |
| Intel Core i3                  | 147       | 9.95%   |
| Intel Celeron                  | 139       | 9.4%    |
| AMD Ryzen 7                    | 76        | 5.14%   |
| AMD Ryzen 5                    | 73        | 4.94%   |
| Intel Core 2 Duo               | 48        | 3.25%   |
| Intel Pentium                  | 43        | 2.91%   |
| Intel Atom                     | 21        | 1.42%   |
| AMD Ryzen 3                    | 21        | 1.42%   |
| AMD Ryzen 9                    | 17        | 1.15%   |
| Intel Pentium Dual-Core        | 11        | 0.74%   |
| AMD A4                         | 11        | 0.74%   |
| Intel Genuine                  | 9         | 0.61%   |
| Intel Core i9                  | 8         | 0.54%   |
| Intel Core                     | 8         | 0.54%   |
| AMD Ryzen 7 PRO                | 8         | 0.54%   |
| Intel Core 2                   | 7         | 0.47%   |
| Intel Pentium Dual             | 6         | 0.41%   |
| AMD E                          | 6         | 0.41%   |
| AMD A6                         | 6         | 0.41%   |
| AMD E2                         | 5         | 0.34%   |
| AMD A10                        | 5         | 0.34%   |
| Intel Pentium Silver           | 4         | 0.27%   |
| Intel Celeron M                | 4         | 0.27%   |
| AMD Athlon                     | 4         | 0.27%   |
| Intel Core Duo                 | 3         | 0.2%    |
| AMD Turion 64 X2 Mobile        | 3         | 0.2%    |
| AMD Ryzen 5 PRO                | 3         | 0.2%    |
| AMD E1                         | 3         | 0.2%    |
| AMD A8                         | 3         | 0.2%    |
| Intel Xeon                     | 2         | 0.14%   |
| Intel Core m5                  | 2         | 0.14%   |
| Intel Celeron Dual-Core        | 2         | 0.14%   |
| AMD V140                       | 2         | 0.14%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.14%   |
| AMD FX                         | 2         | 0.14%   |
| AMD Athlon X2                  | 2         | 0.14%   |
| Intel Pentium M                | 1         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 705       | 47.7%   |
| 4      | 450       | 30.45%  |
| 8      | 118       | 7.98%   |
| 6      | 113       | 7.65%   |
| 10     | 25        | 1.69%   |
| 1      | 24        | 1.62%   |
| 14     | 15        | 1.01%   |
| 16     | 12        | 0.81%   |
| 12     | 10        | 0.68%   |
| 24     | 4         | 0.27%   |
| 20     | 2         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1475      | 99.86%  |
| 2      | 2         | 0.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1098      | 74.29%  |
| 1      | 379       | 25.64%  |
| 4      | 1         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1398      | 94.4%   |
| Unknown        | 67        | 4.52%   |
| 32-bit         | 16        | 1.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 510       | 33.31%  |
| 0x206a7    | 58        | 3.79%   |
| 0x806ec    | 57        | 3.72%   |
| 0x806ea    | 55        | 3.59%   |
| 0x306a9    | 55        | 3.59%   |
| 0x706a1    | 47        | 3.07%   |
| 0x40651    | 41        | 2.68%   |
| 0x306c3    | 39        | 2.55%   |
| 0x906ea    | 35        | 2.29%   |
| 0x806c1    | 33        | 2.16%   |
| 0x806e9    | 31        | 2.02%   |
| 0x506c9    | 31        | 2.02%   |
| 0x306d4    | 30        | 1.96%   |
| 0x20655    | 28        | 1.83%   |
| 0x1067a    | 28        | 1.83%   |
| 0x406e3    | 25        | 1.63%   |
| 0x0a50000c | 23        | 1.5%    |
| 0x806eb    | 21        | 1.37%   |
| 0x08108109 | 21        | 1.37%   |
| 0x906e9    | 20        | 1.31%   |
| 0x08108102 | 19        | 1.24%   |
| 0x706e5    | 17        | 1.11%   |
| 0x08600106 | 16        | 1.05%   |
| 0xa0652    | 14        | 0.91%   |
| 0x08600104 | 14        | 0.91%   |
| 0x506e3    | 13        | 0.85%   |
| 0x6fd      | 12        | 0.78%   |
| 0x10676    | 12        | 0.78%   |
| 0x406c3    | 11        | 0.72%   |
| 0x806d1    | 10        | 0.65%   |
| 0x906ed    | 9         | 0.59%   |
| 0x906a4    | 9         | 0.59%   |
| 0x406c4    | 9         | 0.59%   |
| 0x20652    | 9         | 0.59%   |
| 0x906a3    | 8         | 0.52%   |
| 0x706a8    | 8         | 0.52%   |
| 0x06006705 | 8         | 0.52%   |
| 0x6e8      | 7         | 0.46%   |
| 0x106ca    | 7         | 0.46%   |
| 0x6ec      | 6         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 312       | 21.08%  |
| Haswell           | 113       | 7.64%   |
| Unknown           | 90        | 6.08%   |
| SandyBridge       | 83        | 5.61%   |
| IvyBridge         | 76        | 5.14%   |
| Goldmont plus     | 66        | 4.46%   |
| Skylake           | 60        | 4.05%   |
| Westmere          | 55        | 3.72%   |
| TigerLake         | 51        | 3.45%   |
| Zen+              | 50        | 3.38%   |
| Alderlake Hybrid  | 47        | 3.18%   |
| Zen 2             | 46        | 3.11%   |
| Penryn            | 45        | 3.04%   |
| Zen 3             | 43        | 2.91%   |
| Broadwell         | 42        | 2.84%   |
| Silvermont        | 41        | 2.77%   |
| Goldmont          | 39        | 2.64%   |
| IceLake           | 38        | 2.57%   |
| Core              | 37        | 2.5%    |
| CometLake         | 26        | 1.76%   |
| Excavator         | 19        | 1.28%   |
| Zen               | 16        | 1.08%   |
| P6                | 14        | 0.95%   |
| Bonnell           | 10        | 0.68%   |
| Bobcat            | 9         | 0.61%   |
| Puma              | 7         | 0.47%   |
| Meteorlake Hybrid | 7         | 0.47%   |
| Tremont           | 6         | 0.41%   |
| Piledriver        | 5         | 0.34%   |
| K8 Hammer         | 5         | 0.34%   |
| K8 & K10 hybrid   | 5         | 0.34%   |
| K10               | 4         | 0.27%   |
| Jaguar            | 4         | 0.27%   |
| Nehalem           | 3         | 0.2%    |
| K10 Llano         | 3         | 0.2%    |
| Steamroller       | 2         | 0.14%   |
| NetBurst          | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1112      | 56.68%  |
| Nvidia                           | 482       | 24.57%  |
| AMD                              | 362       | 18.45%  |
| Silicon Integrated Systems [SiS] | 5         | 0.25%   |
| VIA Technologies                 | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 76        | 3.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 70        | 3.48%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 66        | 3.28%   |
| Intel UHD Graphics 620                                                                   | 64        | 3.18%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 64        | 3.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 60        | 2.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 55        | 2.73%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 51        | 2.53%   |
| Intel HD Graphics 620                                                                    | 50        | 2.48%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 50        | 2.48%   |
| Intel Core Processor Integrated Graphics Controller                                      | 42        | 2.09%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 42        | 2.09%   |
| Intel HD Graphics 5500                                                                   | 40        | 1.99%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 36        | 1.79%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 31        | 1.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 29        | 1.44%   |
| Intel HD Graphics 500                                                                    | 29        | 1.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 28        | 1.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 28        | 1.39%   |
| Intel HD Graphics 630                                                                    | 25        | 1.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 1.24%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 23        | 1.14%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 22        | 1.09%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 22        | 1.09%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 20        | 0.99%   |
| Intel HD Graphics 530                                                                    | 20        | 0.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 20        | 0.99%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 18        | 0.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 18        | 0.89%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 16        | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 16        | 0.79%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 16        | 0.79%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 16        | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16        | 0.79%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 16        | 0.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 16        | 0.79%   |
| AMD Rembrandt [Radeon 680M]                                                              | 16        | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.74%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 15        | 0.74%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 15        | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 683       | 46.21%  |
| Intel + Nvidia | 361       | 24.42%  |
| 1 x AMD        | 217       | 14.68%  |
| Intel + AMD    | 64        | 4.33%   |
| 1 x Nvidia     | 61        | 4.13%   |
| AMD + Nvidia   | 60        | 4.06%   |
| 2 x AMD        | 21        | 1.42%   |
| 1 x SiS        | 5         | 0.34%   |
| 2 x Intel      | 3         | 0.2%    |
| Other          | 2         | 0.14%   |
| 1 x VIA        | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1178      | 78.9%   |
| Proprietary | 276       | 18.49%  |
| Unknown     | 39        | 2.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 950       | 62.66%  |
| 1.01-2.0   | 189       | 12.47%  |
| 0.01-0.5   | 176       | 11.61%  |
| 3.01-4.0   | 96        | 6.33%   |
| 0.51-1.0   | 58        | 3.83%   |
| 5.01-6.0   | 25        | 1.65%   |
| 7.01-8.0   | 15        | 0.99%   |
| 2.01-3.0   | 6         | 0.4%    |
| 0          | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 293       | 18.09%  |
| BOE                     | 268       | 16.54%  |
| Chimei Innolux          | 258       | 15.93%  |
| LG Display              | 217       | 13.4%   |
| Samsung Electronics     | 160       | 9.88%   |
| PANDA                   | 59        | 3.64%   |
| Dell                    | 51        | 3.15%   |
| Chi Mei Optoelectronics | 39        | 2.41%   |
| Sharp                   | 37        | 2.28%   |
| Lenovo                  | 29        | 1.79%   |
| Goldstar                | 26        | 1.6%    |
| LG Philips              | 17        | 1.05%   |
| CSO                     | 15        | 0.93%   |
| BenQ                    | 14        | 0.86%   |
| Philips                 | 11        | 0.68%   |
| Apple                   | 11        | 0.68%   |
| Acer                    | 11        | 0.68%   |
| Hewlett-Packard         | 10        | 0.62%   |
| InfoVision              | 9         | 0.56%   |
| AOC                     | 8         | 0.49%   |
| Valve                   | 6         | 0.37%   |
| Ancor Communications    | 5         | 0.31%   |
| Sony                    | 4         | 0.25%   |
| LGD                     | 4         | 0.25%   |
| InnoLux Display         | 4         | 0.25%   |
| Fujitsu Siemens         | 4         | 0.25%   |
| CPT                     | 4         | 0.25%   |
| Analogix                | 4         | 0.25%   |
| Vestel Elektronik       | 3         | 0.19%   |
| Lenovo Group Limited    | 3         | 0.19%   |
| ASUSTek Computer        | 3         | 0.19%   |
| TMX                     | 2         | 0.12%   |
| Quanta Display          | 2         | 0.12%   |
| ITE                     | 2         | 0.12%   |
| Iiyama                  | 2         | 0.12%   |
| HannStar                | 2         | 0.12%   |
| Yakumo                  | 1         | 0.06%   |
| ViewSonic               | 1         | 0.06%   |
| Toshiba                 | 1         | 0.06%   |
| Seiko/Epson             | 1         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 28        | 1.71%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 26        | 1.59%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 24        | 1.47%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 22        | 1.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 17        | 1.04%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 16        | 0.98%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 14        | 0.86%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 14        | 0.86%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 12        | 0.73%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 12        | 0.73%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 12        | 0.73%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 11        | 0.67%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 11        | 0.67%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 11        | 0.67%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 11        | 0.67%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 11        | 0.67%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 10        | 0.61%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 10        | 0.61%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 10        | 0.61%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 9         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 9         | 0.55%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 9         | 0.55%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 8         | 0.49%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 8         | 0.49%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 8         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 8         | 0.49%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                  | 7         | 0.43%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.43%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                    | 7         | 0.43%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 7         | 0.43%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 7         | 0.43%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 6         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 6         | 0.37%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                  | 6         | 0.37%   |
| BOE LCD Monitor BOE07F1 1920x1080 344x193mm 15.5-inch                    | 6         | 0.37%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 6         | 0.37%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 6         | 0.37%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 5         | 0.31%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch    | 5         | 0.31%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 5         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 728       | 47.49%  |
| 1366x768 (WXGA)    | 424       | 27.66%  |
| 1600x900 (HD+)     | 60        | 3.91%   |
| 1280x800 (WXGA)    | 46        | 3%      |
| 3840x2160 (4K)     | 44        | 2.87%   |
| 1920x1200 (WUXGA)  | 33        | 2.15%   |
| 2560x1440 (QHD)    | 28        | 1.83%   |
| 2560x1600          | 25        | 1.63%   |
| 2880x1800          | 21        | 1.37%   |
| 1440x900 (WXGA+)   | 17        | 1.11%   |
| 3200x1800 (QHD+)   | 12        | 0.78%   |
| 1680x1050 (WSXGA+) | 12        | 0.78%   |
| 800x1280           | 9         | 0.59%   |
| 2160x1440          | 9         | 0.59%   |
| 1280x1024 (SXGA)   | 9         | 0.59%   |
| 2560x1080          | 8         | 0.52%   |
| 1024x600           | 8         | 0.52%   |
| 3200x2000          | 6         | 0.39%   |
| 3440x1440          | 4         | 0.26%   |
| 1360x768           | 4         | 0.26%   |
| 3840x2400          | 3         | 0.2%    |
| 2880x1620          | 3         | 0.2%    |
| 1400x1050          | 3         | 0.2%    |
| 1024x768 (XGA)     | 3         | 0.2%    |
| Unknown            | 3         | 0.2%    |
| 3926x1440          | 1         | 0.07%   |
| 3840x1080          | 1         | 0.07%   |
| 3456x2160          | 1         | 0.07%   |
| 3000x2000          | 1         | 0.07%   |
| 2520x1680          | 1         | 0.07%   |
| 2240x1400          | 1         | 0.07%   |
| 2048x1152          | 1         | 0.07%   |
| 1920x1280          | 1         | 0.07%   |
| 1680x945           | 1         | 0.07%   |
| 1280x720 (HD)      | 1         | 0.07%   |
| 1080x1920          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 857       | 53.16%  |
| 14      | 172       | 10.67%  |
| 13      | 148       | 9.18%   |
| 17      | 113       | 7.01%   |
| 24      | 51        | 3.16%   |
| 16      | 45        | 2.79%   |
| 27      | 31        | 1.92%   |
| 23      | 28        | 1.74%   |
| 21      | 23        | 1.43%   |
| 12      | 22        | 1.36%   |
| Unknown | 17        | 1.05%   |
| 34      | 13        | 0.81%   |
| 31      | 12        | 0.74%   |
| 19      | 10        | 0.62%   |
| 11      | 10        | 0.62%   |
| 10      | 10        | 0.62%   |
| 84      | 6         | 0.37%   |
| 32      | 6         | 0.37%   |
| 22      | 6         | 0.37%   |
| 7       | 6         | 0.37%   |
| 54      | 4         | 0.25%   |
| 18      | 4         | 0.25%   |
| 3       | 3         | 0.19%   |
| 42      | 2         | 0.12%   |
| 20      | 2         | 0.12%   |
| 8       | 2         | 0.12%   |
| 86      | 1         | 0.06%   |
| 72      | 1         | 0.06%   |
| 65      | 1         | 0.06%   |
| 58      | 1         | 0.06%   |
| 52      | 1         | 0.06%   |
| 48      | 1         | 0.06%   |
| 47      | 1         | 0.06%   |
| 40      | 1         | 0.06%   |
| 25      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1136      | 70.69%  |
| 351-400     | 137       | 8.53%   |
| 501-600     | 107       | 6.66%   |
| 201-300     | 107       | 6.66%   |
| 401-500     | 39        | 2.43%   |
| 701-800     | 19        | 1.18%   |
| Unknown     | 17        | 1.06%   |
| 601-700     | 14        | 0.87%   |
| 1001-1500   | 10        | 0.62%   |
| 1-100       | 9         | 0.56%   |
| 1501-2000   | 7         | 0.44%   |
| 101-200     | 2         | 0.12%   |
| 901-1000    | 2         | 0.12%   |
| 801-900     | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1248      | 84.44%  |
| 16/10   | 162       | 10.96%  |
| 3/2     | 14        | 0.95%   |
| Unknown | 14        | 0.95%   |
| 21/9    | 13        | 0.88%   |
| 5/4     | 9         | 0.61%   |
| 4/3     | 6         | 0.41%   |
| 0.67    | 5         | 0.34%   |
| 6/5     | 4         | 0.27%   |
| 0.56    | 2         | 0.14%   |
| 0.62    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 858       | 53.19%  |
| 81-90          | 268       | 16.62%  |
| 121-130        | 102       | 6.32%   |
| 201-250        | 90        | 5.58%   |
| 71-80          | 47        | 2.91%   |
| 111-120        | 41        | 2.54%   |
| 351-500        | 31        | 1.92%   |
| 301-350        | 31        | 1.92%   |
| 61-70          | 21        | 1.3%    |
| 151-200        | 18        | 1.12%   |
| Unknown        | 17        | 1.05%   |
| More than 1000 | 16        | 0.99%   |
| 251-300        | 15        | 0.93%   |
| 1-40           | 11        | 0.68%   |
| 131-140        | 11        | 0.68%   |
| 51-60          | 10        | 0.62%   |
| 41-50          | 10        | 0.62%   |
| 141-150        | 6         | 0.37%   |
| 91-100         | 6         | 0.37%   |
| 501-1000       | 4         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 711       | 44.52%  |
| 101-120       | 473       | 29.62%  |
| 51-100        | 223       | 13.96%  |
| 161-240       | 120       | 7.51%   |
| More than 240 | 43        | 2.69%   |
| Unknown       | 17        | 1.06%   |
| 1-50          | 10        | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1289      | 85.36%  |
| 2     | 177       | 11.72%  |
| 0     | 27        | 1.79%   |
| 3     | 15        | 0.99%   |
| 4     | 2         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 867       | 37.93%  |
| Intel                                  | 676       | 29.57%  |
| Qualcomm Atheros                       | 300       | 13.12%  |
| Broadcom                               | 129       | 5.64%   |
| MediaTek                               | 92        | 4.02%   |
| TP-Link                                | 35        | 1.53%   |
| Broadcom Limited                       | 26        | 1.14%   |
| Marvell Technology Group               | 18        | 0.79%   |
| Ralink                                 | 17        | 0.74%   |
| Ralink Technology                      | 12        | 0.52%   |
| Samsung Electronics                    | 11        | 0.48%   |
| Huawei Technologies                    | 10        | 0.44%   |
| ASIX Electronics                       | 10        | 0.44%   |
| Ericsson Business Mobile Networks      | 9         | 0.39%   |
| Xiaomi                                 | 8         | 0.35%   |
| Hewlett-Packard                        | 7         | 0.31%   |
| ASUSTek Computer                       | 7         | 0.31%   |
| Sierra Wireless                        | 5         | 0.22%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.17%   |
| Lenovo                                 | 4         | 0.17%   |
| JMicron Technology                     | 4         | 0.17%   |
| Google                                 | 4         | 0.17%   |
| ZTE WCDMA Technologies MSM             | 3         | 0.13%   |
| Qualcomm Atheros Communications        | 3         | 0.13%   |
| Dell                                   | 3         | 0.13%   |
| D-Link                                 | 3         | 0.13%   |
| Qualcomm                               | 2         | 0.09%   |
| DisplayLink                            | 2         | 0.09%   |
| VIA Technologies                       | 1         | 0.04%   |
| U-Blox                                 | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Sitecom Europe                         | 1         | 0.04%   |
| Qcom                                   | 1         | 0.04%   |
| Nvidia                                 | 1         | 0.04%   |
| Motorola PCS                           | 1         | 0.04%   |
| Microsoft                              | 1         | 0.04%   |
| Microchip Technology                   | 1         | 0.04%   |
| Fibocom                                | 1         | 0.04%   |
| Edimax Technology                      | 1         | 0.04%   |
| D-Link System                          | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 483       | 17.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 136       | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 86        | 3.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 79        | 2.91%   |
| Intel Wireless 8265 / 8275                                             | 68        | 2.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 58        | 2.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 55        | 2.02%   |
| Intel Wi-Fi 6 AX200                                                    | 53        | 1.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 52        | 1.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 47        | 1.73%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 45        | 1.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 42        | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 42        | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 41        | 1.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 41        | 1.51%   |
| Intel Wi-Fi 6 AX201                                                    | 37        | 1.36%   |
| Intel Wireless 7260                                                    | 34        | 1.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 32        | 1.18%   |
| Intel Wireless 7265                                                    | 31        | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 30        | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 29        | 1.07%   |
| Intel Wireless 8260                                                    | 26        | 0.96%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 25        | 0.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 23        | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 22        | 0.81%   |
| Intel Wireless 3165                                                    | 22        | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 21        | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 21        | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                          | 21        | 0.77%   |
| Intel Wireless 3160                                                    | 20        | 0.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 20        | 0.74%   |
| Intel 82577LM Gigabit Network Connection                               | 19        | 0.7%    |
| Intel Centrino Advanced-N 6200                                         | 18        | 0.66%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 17        | 0.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 17        | 0.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 17        | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                                  | 16        | 0.59%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 16        | 0.59%   |
| Realtek RTL8125 2.5GbE Controller                                      | 15        | 0.55%   |
| Intel Ethernet Connection I217-LM                                      | 14        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 648       | 42.91%  |
| Realtek Semiconductor           | 327       | 21.66%  |
| Qualcomm Atheros                | 267       | 17.68%  |
| Broadcom                        | 98        | 6.49%   |
| MediaTek                        | 73        | 4.83%   |
| TP-Link                         | 24        | 1.59%   |
| Ralink                          | 17        | 1.13%   |
| Broadcom Limited                | 16        | 1.06%   |
| Ralink Technology               | 12        | 0.79%   |
| ASUSTek Computer                | 6         | 0.4%    |
| Sierra Wireless                 | 5         | 0.33%   |
| Qualcomm Atheros Communications | 3         | 0.2%    |
| D-Link                          | 3         | 0.2%    |
| Qualcomm                        | 2         | 0.13%   |
| Sitecom Europe                  | 1         | 0.07%   |
| Qcom                            | 1         | 0.07%   |
| Microsoft                       | 1         | 0.07%   |
| Hewlett-Packard                 | 1         | 0.07%   |
| Fibocom                         | 1         | 0.07%   |
| Edimax Technology               | 1         | 0.07%   |
| D-Link System                   | 1         | 0.07%   |
| Belkin                          | 1         | 0.07%   |
| Accton Technology               | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 86        | 5.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 79        | 5.2%    |
| Intel Wireless 8265 / 8275                                              | 68        | 4.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 58        | 3.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 55        | 3.62%   |
| Intel Wi-Fi 6 AX200                                                     | 53        | 3.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 52        | 3.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 47        | 3.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 45        | 2.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 42        | 2.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 41        | 2.7%    |
| Intel Wi-Fi 6 AX201                                                     | 37        | 2.44%   |
| Intel Wireless 7260                                                     | 34        | 2.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 32        | 2.11%   |
| Intel Wireless 7265                                                     | 31        | 2.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 30        | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 29        | 1.91%   |
| Intel Wireless 8260                                                     | 26        | 1.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 23        | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 22        | 1.45%   |
| Intel Wireless 3165                                                     | 22        | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 21        | 1.38%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 21        | 1.38%   |
| Broadcom BCM43142 802.11b/g/n                                           | 21        | 1.38%   |
| Intel Wireless 3160                                                     | 20        | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 20        | 1.32%   |
| Intel Centrino Advanced-N 6200                                          | 18        | 1.19%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 17        | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 17        | 1.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 17        | 1.12%   |
| Intel Centrino Ultimate-N 6300                                          | 14        | 0.92%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 13        | 0.86%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 12        | 0.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 0.72%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 11        | 0.72%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 11        | 0.72%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 0.66%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 10        | 0.66%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 10        | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 10        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 697       | 59.88%  |
| Intel                                  | 232       | 19.93%  |
| Qualcomm Atheros                       | 66        | 5.67%   |
| Broadcom                               | 53        | 4.55%   |
| MediaTek                               | 19        | 1.63%   |
| Marvell Technology Group               | 18        | 1.55%   |
| TP-Link                                | 11        | 0.95%   |
| Broadcom Limited                       | 10        | 0.86%   |
| ASIX Electronics                       | 10        | 0.86%   |
| Xiaomi                                 | 8         | 0.69%   |
| Samsung Electronics                    | 8         | 0.69%   |
| Huawei Technologies                    | 8         | 0.69%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.34%   |
| Lenovo                                 | 4         | 0.34%   |
| JMicron Technology                     | 4         | 0.34%   |
| Google                                 | 3         | 0.26%   |
| DisplayLink                            | 2         | 0.17%   |
| VIA Technologies                       | 1         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.09%   |
| Nvidia                                 | 1         | 0.09%   |
| Motorola PCS                           | 1         | 0.09%   |
| Hewlett-Packard                        | 1         | 0.09%   |
| ASUSTek Computer                       | 1         | 0.09%   |
| Apple                                  | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 483       | 41.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 136       | 11.61%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 42        | 3.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 41        | 3.5%    |
| Intel 82577LM Gigabit Network Connection                               | 19        | 1.62%   |
| Intel Ethernet Connection (4) I219-LM                                  | 16        | 1.37%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 16        | 1.37%   |
| Realtek RTL8125 2.5GbE Controller                                      | 15        | 1.28%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 14        | 1.2%    |
| Intel Ethernet Connection I217-LM                                      | 14        | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 13        | 1.11%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 12        | 1.02%   |
| Intel Ethernet Connection I218-LM                                      | 12        | 1.02%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 11        | 0.94%   |
| Intel Ethernet Connection (7) I219-LM                                  | 11        | 0.94%   |
| Intel Ethernet Connection I219-LM                                      | 10        | 0.85%   |
| Intel Ethernet Connection (3) I218-LM                                  | 10        | 0.85%   |
| ASIX AX88179 Gigabit Ethernet                                          | 10        | 0.85%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 8         | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 8         | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 8         | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 8         | 0.68%   |
| Intel Ethernet Connection (6) I219-V                                   | 8         | 0.68%   |
| Intel 82567LM Gigabit Network Connection                               | 8         | 0.68%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 8         | 0.68%   |
| Intel Ethernet Connection (13) I219-V                                  | 7         | 0.6%    |
| Realtek Killer E2600 GbE Controller                                    | 6         | 0.51%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 6         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                                   | 6         | 0.51%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 6         | 0.51%   |
| Realtek PCIe GbE Family Controller                                     | 5         | 0.43%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 5         | 0.43%   |
| MediaTek Infinix SMART 5                                               | 5         | 0.43%   |
| Intel 82577LC Gigabit Network Connection                               | 5         | 0.43%   |
| Huawei FOA-LX9                                                         | 5         | 0.43%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 4         | 0.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4         | 0.34%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 4         | 0.34%   |
| Intel PRO/100 VE Network Connection                                    | 4         | 0.34%   |
| Intel Ethernet Connection (7) I219-V                                   | 4         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1441      | 55.74%  |
| Ethernet | 1114      | 43.09%  |
| Modem    | 29        | 1.12%   |
| Unknown  | 1         | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1211      | 78.28%  |
| Ethernet | 336       | 21.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1009      | 68.31%  |
| 1     | 433       | 29.32%  |
| 0     | 25        | 1.69%   |
| 3     | 10        | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1201      | 79.38%  |
| Yes  | 312       | 20.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 508       | 41.67%  |
| IMC Networks                    | 185       | 15.18%  |
| Realtek Semiconductor           | 159       | 13.04%  |
| Qualcomm Atheros Communications | 85        | 6.97%   |
| Lite-On Technology              | 71        | 5.82%   |
| Foxconn / Hon Hai               | 56        | 4.59%   |
| Broadcom                        | 48        | 3.94%   |
| Dell                            | 23        | 1.89%   |
| Hewlett-Packard                 | 17        | 1.39%   |
| Toshiba                         | 16        | 1.31%   |
| Ralink                          | 10        | 0.82%   |
| Apple                           | 8         | 0.66%   |
| ASUSTek Computer                | 7         | 0.57%   |
| Realtek                         | 6         | 0.49%   |
| Cambridge Silicon Radio         | 6         | 0.49%   |
| Alps Electric                   | 3         | 0.25%   |
| USI                             | 2         | 0.16%   |
| Chicony Electronics             | 2         | 0.16%   |
| SINO WEALTH                     | 1         | 0.08%   |
| Ralink Technology               | 1         | 0.08%   |
| Opticis                         | 1         | 0.08%   |
| MediaTek                        | 1         | 0.08%   |
| Foxconn International           | 1         | 0.08%   |
| Askey Computer                  | 1         | 0.08%   |
| Unknown                         | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 204       | 16.74%  |
| IMC Networks Bluetooth Radio                        | 104       | 8.53%   |
| Realtek Bluetooth Radio                             | 102       | 8.37%   |
| Intel AX201 Bluetooth                               | 95        | 7.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 81        | 6.64%   |
| Intel AX200 Bluetooth                               | 53        | 4.35%   |
| Qualcomm Atheros  Bluetooth Device                  | 46        | 3.77%   |
| IMC Networks Wireless_Device                        | 41        | 3.36%   |
| IMC Networks Bluetooth Device                       | 32        | 2.63%   |
| Intel AX211 Bluetooth                               | 29        | 2.38%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 26        | 2.13%   |
| Foxconn / Hon Hai Wireless_Device                   | 22        | 1.8%    |
| Realtek  Bluetooth 4.2 Adapter                      | 21        | 1.72%   |
| Lite-On Bluetooth Device                            | 14        | 1.15%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 13        | 1.07%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 12        | 0.98%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 12        | 0.98%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 12        | 0.98%   |
| Realtek 802.11ac WLAN Adapter                       | 11        | 0.9%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 11        | 0.9%    |
| Lite-On Wireless_Device                             | 11        | 0.9%    |
| Dell DW375 Bluetooth Module                         | 11        | 0.9%    |
| Ralink RT3290 Bluetooth                             | 10        | 0.82%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 0.82%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 0.82%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 9         | 0.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.66%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 8         | 0.66%   |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 0.66%   |
| Toshiba Bluetooth Device                            | 7         | 0.57%   |
| Intel AX210 Bluetooth                               | 7         | 0.57%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 0.57%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.57%   |
| Broadcom BCM2045B (BDC-2.1)                         | 7         | 0.57%   |
| Broadcom BCM2045A0                                  | 7         | 0.57%   |
| Realtek RTL8723B Bluetooth                          | 6         | 0.49%   |
| Realtek Bluetooth Radio                             | 6         | 0.49%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 6         | 0.49%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 0.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1182      | 64.98%  |
| AMD                              | 297       | 16.33%  |
| Nvidia                           | 257       | 14.13%  |
| C-Media Electronics              | 11        | 0.6%    |
| GN Netcom                        | 9         | 0.49%   |
| Logitech                         | 6         | 0.33%   |
| Lenovo                           | 6         | 0.33%   |
| Silicon Integrated Systems [SiS] | 5         | 0.27%   |
| Realtek Semiconductor            | 5         | 0.27%   |
| ASUSTek Computer                 | 5         | 0.27%   |
| XMOS                             | 3         | 0.16%   |
| Kingston Technology              | 3         | 0.16%   |
| Creative Technology              | 3         | 0.16%   |
| VIA Technologies                 | 2         | 0.11%   |
| Samsung Electronics              | 2         | 0.11%   |
| Razer USA                        | 2         | 0.11%   |
| Plantronics                      | 2         | 0.11%   |
| Hewlett-Packard                  | 2         | 0.11%   |
| Dell                             | 2         | 0.11%   |
| Unknown                          | 1         | 0.05%   |
| Trust                            | 1         | 0.05%   |
| Sony                             | 1         | 0.05%   |
| Sennheiser Communications        | 1         | 0.05%   |
| RME                              | 1         | 0.05%   |
| Nordic Semiconductor ASA         | 1         | 0.05%   |
| Mackie Designs                   | 1         | 0.05%   |
| LG Electronics                   | 1         | 0.05%   |
| JMTek                            | 1         | 0.05%   |
| Focusrite-Novation               | 1         | 0.05%   |
| FiiO Electronics Technology      | 1         | 0.05%   |
| DSEA A/S                         | 1         | 0.05%   |
| CMX Systems                      | 1         | 0.05%   |
| Bose                             | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 201       | 9.19%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 157       | 7.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 89        | 4.07%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 82        | 3.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 71        | 3.24%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 70        | 3.2%    |
| Intel Cannon Lake PCH cAVS                                                                        | 67        | 3.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 66        | 3.02%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 60        | 2.74%   |
| Intel 8 Series HD Audio Controller                                                                | 59        | 2.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 58        | 2.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 57        | 2.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 53        | 2.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 51        | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 50        | 2.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 42        | 1.92%   |
| Intel Broadwell-U Audio Controller                                                                | 42        | 1.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 39        | 1.78%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 38        | 1.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 38        | 1.74%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 38        | 1.74%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 31        | 1.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 31        | 1.42%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 28        | 1.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 28        | 1.28%   |
| Intel Comet Lake PCH cAVS                                                                         | 25        | 1.14%   |
| Intel CM238 HD Audio Controller                                                                   | 25        | 1.14%   |
| AMD FCH Azalia Controller                                                                         | 25        | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 23        | 1.05%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 23        | 1.05%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 23        | 1.05%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 22        | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 22        | 1.01%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 22        | 1.01%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 19        | 0.87%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 19        | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 18        | 0.82%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 17        | 0.78%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 17        | 0.78%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 16        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 272       | 30.87%  |
| SK hynix                     | 200       | 22.7%   |
| Micron Technology            | 120       | 13.62%  |
| Kingston                     | 93        | 10.56%  |
| Unknown                      | 42        | 4.77%   |
| Corsair                      | 24        | 2.72%   |
| Ramaxel Technology           | 21        | 2.38%   |
| Crucial                      | 20        | 2.27%   |
| A-DATA Technology            | 20        | 2.27%   |
| Elpida                       | 18        | 2.04%   |
| Unknown (ABCD)               | 13        | 1.48%   |
| Nanya Technology             | 13        | 1.48%   |
| Unknown                      | 5         | 0.57%   |
| Kingmax                      | 4         | 0.45%   |
| Transcend                    | 2         | 0.23%   |
| Kingmax Semiconductor        | 2         | 0.23%   |
| Apacer                       | 2         | 0.23%   |
| Unknown (0x7FDA000000000000) | 1         | 0.11%   |
| Unknown (0B45)               | 1         | 0.11%   |
| Silicon Power                | 1         | 0.11%   |
| SHARETRONIC                  | 1         | 0.11%   |
| PNY                          | 1         | 0.11%   |
| Patriot                      | 1         | 0.11%   |
| KingFast                     | 1         | 0.11%   |
| Infineon                     | 1         | 0.11%   |
| Avant                        | 1         | 0.11%   |
| ASint Technology             | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 18        | 1.91%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 1.59%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.38%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.38%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 12        | 1.27%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 12        | 1.27%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 12        | 1.27%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 11        | 1.17%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 1.06%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 1.06%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.95%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 9         | 0.95%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 0.85%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 7         | 0.74%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.74%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.74%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.64%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.64%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.64%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.64%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.64%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.53%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 5         | 0.53%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.53%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.53%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.53%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.53%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.53%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 5         | 0.53%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 5         | 0.53%   |
| Unknown                                                          | 5         | 0.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 0.42%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.42%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.42%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 4         | 0.42%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 367       | 50%     |
| DDR3    | 215       | 29.29%  |
| DDR2    | 37        | 5.04%   |
| DDR5    | 31        | 4.22%   |
| LPDDR4  | 26        | 3.54%   |
| LPDDR5  | 23        | 3.13%   |
| LPDDR3  | 19        | 2.59%   |
| SDRAM   | 11        | 1.5%    |
| DRAM    | 2         | 0.27%   |
| Unknown | 2         | 0.27%   |
| DDR     | 1         | 0.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 666       | 90.24%  |
| Row Of Chips | 65        | 8.81%   |
| Chip         | 5         | 0.68%   |
| DIMM         | 2         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 324       | 40.45%  |
| 4096  | 234       | 29.21%  |
| 16384 | 132       | 16.48%  |
| 2048  | 69        | 8.61%   |
| 1024  | 27        | 3.37%   |
| 32768 | 13        | 1.62%   |
| 512   | 2         | 0.25%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 181       | 22.15%  |
| 1600    | 155       | 18.97%  |
| 2667    | 149       | 18.24%  |
| 2400    | 77        | 9.42%   |
| 1334    | 42        | 5.14%   |
| 2133    | 31        | 3.79%   |
| 3266    | 18        | 2.2%    |
| 4800    | 16        | 1.96%   |
| 1333    | 16        | 1.96%   |
| 5600    | 15        | 1.84%   |
| 667     | 14        | 1.71%   |
| Unknown | 13        | 1.59%   |
| 1067    | 12        | 1.47%   |
| 6400    | 11        | 1.35%   |
| 975     | 9         | 1.1%    |
| 7500    | 8         | 0.98%   |
| 800     | 7         | 0.86%   |
| 1066    | 6         | 0.73%   |
| 4266    | 5         | 0.61%   |
| 4199    | 5         | 0.61%   |
| 1867    | 5         | 0.61%   |
| 4267    | 4         | 0.49%   |
| 7467    | 3         | 0.37%   |
| 2933    | 3         | 0.37%   |
| 2048    | 3         | 0.37%   |
| 533     | 3         | 0.37%   |
| 8400    | 1         | 0.12%   |
| 3733    | 1         | 0.12%   |
| 2666    | 1         | 0.12%   |
| 1639    | 1         | 0.12%   |
| 400     | 1         | 0.12%   |
| 333     | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 6         | 25%     |
| Canon                 | 6         | 25%     |
| Samsung Electronics   | 4         | 16.67%  |
| Seiko Epson           | 3         | 12.5%   |
| Brother Industries    | 2         | 8.33%   |
| Xerox                 | 1         | 4.17%   |
| Pantum                | 1         | 4.17%   |
| Lexmark International | 1         | 4.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Seiko Epson L3110 Series                   | 2         | 8.33%   |
| Samsung Composite Device                   | 2         | 8.33%   |
| Xerox Phaser 3020                          | 1         | 4.17%   |
| Seiko Epson L3150 Series                   | 1         | 4.17%   |
| Samsung ML-1660 Series                     | 1         | 4.17%   |
| Samsung M2070 Series                       | 1         | 4.17%   |
| Pantum M6500NW-series                      | 1         | 4.17%   |
| Lexmark International InkJet Color Printer | 1         | 4.17%   |
| HP LaserJet 1022                           | 1         | 4.17%   |
| HP LaserJet 1018                           | 1         | 4.17%   |
| HP HP Laser 107w                           | 1         | 4.17%   |
| HP Deskjet F4500 series                    | 1         | 4.17%   |
| HP DeskJet 2300 series                     | 1         | 4.17%   |
| HP Deskjet 2050 J510                       | 1         | 4.17%   |
| Canon PIXMA MP250                          | 1         | 4.17%   |
| Canon MF4320-4350                          | 1         | 4.17%   |
| Canon MF3200 series                        | 1         | 4.17%   |
| Canon LBP2900                              | 1         | 4.17%   |
| Canon iP7200 series                        | 1         | 4.17%   |
| Canon CanoScan LiDE 300                    | 1         | 4.17%   |
| Brother HL-1110 series                     | 1         | 4.17%   |
| Brother DCP-T310                           | 1         | 4.17%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Mustek Systems BearPaw 2448 TA Plus | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 296       | 22.49%  |
| IMC Networks                           | 288       | 21.88%  |
| Realtek Semiconductor                  | 114       | 8.66%   |
| Microdia                               | 87        | 6.61%   |
| Bison Electronics                      | 80        | 6.08%   |
| Quanta                                 | 71        | 5.4%    |
| Sunplus Innovation Technology          | 62        | 4.71%   |
| Syntek                                 | 36        | 2.74%   |
| Cheng Uei Precision Industry (Foxlink) | 34        | 2.58%   |
| Sonix Technology                       | 32        | 2.43%   |
| Luxvisions Innotech Limited            | 30        | 2.28%   |
| Lite-On Technology                     | 28        | 2.13%   |
| Alcor Micro                            | 28        | 2.13%   |
| Suyin                                  | 24        | 1.82%   |
| Acer                                   | 18        | 1.37%   |
| ShineTech                              | 13        | 0.99%   |
| Ricoh                                  | 11        | 0.84%   |
| Silicon Motion                         | 9         | 0.68%   |
| Apple                                  | 8         | 0.61%   |
| Samsung Electronics                    | 7         | 0.53%   |
| OmniVision Technologies                | 6         | 0.46%   |
| ALi                                    | 4         | 0.3%    |
| Primax Electronics                     | 3         | 0.23%   |
| Z-Star Microelectronics                | 2         | 0.15%   |
| Y Media                                | 2         | 0.15%   |
| Sunplus Technology                     | 2         | 0.15%   |
| Microsoft                              | 2         | 0.15%   |
| Logitech                               | 2         | 0.15%   |
| Lenovo                                 | 2         | 0.15%   |
| Importek                               | 2         | 0.15%   |
| Genesys Logic                          | 2         | 0.15%   |
| Trust                                  | 1         | 0.08%   |
| Shine-optics                           | 1         | 0.08%   |
| Razer USA                              | 1         | 0.08%   |
| Philips (or NXP)                       | 1         | 0.08%   |
| Intel                                  | 1         | 0.08%   |
| Google                                 | 1         | 0.08%   |
| Epiphan Systems                        | 1         | 0.08%   |
| DigiTech                               | 1         | 0.08%   |
| Cubeternet                             | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                  | 114       | 8.65%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 90        | 6.83%   |
| Chicony Integrated Camera                           | 69        | 5.24%   |
| IMC Networks Integrated Camera                      | 42        | 3.19%   |
| Realtek Integrated_Webcam_HD                        | 37        | 2.81%   |
| Microdia Integrated_Webcam_HD                       | 31        | 2.35%   |
| Sonix USB2.0 HD UVC WebCam                          | 24        | 1.82%   |
| Syntek Integrated Camera                            | 21        | 1.59%   |
| Chicony USB2.0 VGA UVC WebCam                       | 21        | 1.59%   |
| Chicony HD Webcam                                   | 21        | 1.59%   |
| Chicony USB2.0 HD UVC WebCam                        | 19        | 1.44%   |
| Bison Integrated Camera                             | 18        | 1.37%   |
| Sunplus HD WebCam                                   | 15        | 1.14%   |
| Realtek USB Camera                                  | 14        | 1.06%   |
| Chicony TOSHIBA Web Camera - HD                     | 13        | 0.99%   |
| Quanta VGA WebCam                                   | 12        | 0.91%   |
| Bison Lenovo EasyCamera                             | 12        | 0.91%   |
| Quanta ACER HD User Facing                          | 11        | 0.83%   |
| Lite-On Integrated Camera                           | 11        | 0.83%   |
| Chicony EasyCamera                                  | 11        | 0.83%   |
| Bison SunplusIT Integrated Camera                   | 11        | 0.83%   |
| Sunplus Integrated_Webcam_HD                        | 10        | 0.76%   |
| Chicony HP HD Camera                                | 10        | 0.76%   |
| Microdia Integrated Webcam                          | 9         | 0.68%   |
| Chicony VGA Webcam                                  | 9         | 0.68%   |
| Chicony HP Webcam                                   | 9         | 0.68%   |
| Bison EasyCamera                                    | 9         | 0.68%   |
| Alcor Micro USB 2.0 Camera                          | 9         | 0.68%   |
| Realtek USB2.0 HD UVC WebCam                        | 8         | 0.61%   |
| Realtek Integrated Webcam                           | 8         | 0.61%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 8         | 0.61%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 8         | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) Webcam       | 8         | 0.61%   |
| Alcor Micro USB 2.0 PC Camera                       | 8         | 0.61%   |
| Acer Integrated Camera                              | 8         | 0.61%   |
| Syntek Lenovo EasyCamera                            | 7         | 0.53%   |
| Syntek EasyCamera                                   | 7         | 0.53%   |
| Samsung Galaxy series, misc. (MTP mode)             | 7         | 0.53%   |
| Realtek USB2.0 VGA UVC WebCam                       | 7         | 0.53%   |
| Quanta HP HD Camera                                 | 7         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 73        | 35.44%  |
| Synaptics                          | 53        | 25.73%  |
| Shenzhen Goodix Technology         | 27        | 13.11%  |
| Elan Microelectronics              | 16        | 7.77%   |
| Upek                               | 13        | 6.31%   |
| AuthenTec                          | 10        | 4.85%   |
| LighTuning Technology              | 9         | 4.37%   |
| STMicroelectronics                 | 2         | 0.97%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.49%   |
| GDMicroelectronics                 | 1         | 0.49%   |
| Focal-systems.Corp                 | 1         | 0.49%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 9.22%   |
| Shenzhen Goodix  FingerPrint Device                                        | 18        | 8.74%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 16        | 7.77%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 6.31%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 5.83%   |
| Synaptics  WBDI                                                            | 10        | 4.85%   |
| Elan ELAN:Fingerprint                                                      | 9         | 4.37%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 3.88%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 3.4%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 3.4%    |
| Validity Sensors Synaptics WBDI                                            | 7         | 3.4%    |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 3.4%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 2.91%   |
| Synaptics Fingerprint reader [HP G6]                                       | 6         | 2.91%   |
| Elan ELAN:ARM-M4                                                           | 6         | 2.91%   |
| AuthenTec AES2810                                                          | 6         | 2.91%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 2.43%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 2.43%   |
| Validity Sensors VFS491                                                    | 4         | 1.94%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.46%   |
| LighTuning Fingerprint Reader                                              | 3         | 1.46%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 1.46%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.46%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 0.97%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.97%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.97%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 0.97%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 0.97%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.97%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 0.97%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.49%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.49%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.49%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.49%   |
| Synaptics WBDI                                                             | 1         | 0.49%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.49%   |
| GDMicroelectronics Touch Fingerprint Sensor                                | 1         | 0.49%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 1         | 0.49%   |
| Elan WBF Fingerprint Sensor                                                | 1         | 0.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 50        | 53.76%  |
| Alcor Micro               | 26        | 27.96%  |
| Upek                      | 5         | 5.38%   |
| Lenovo                    | 5         | 5.38%   |
| O2 Micro                  | 4         | 4.3%    |
| Gemalto (was Gemplus)     | 1         | 1.08%   |
| Aladdin Knowledge Systems | 1         | 1.08%   |
| Advanced Card Systems     | 1         | 1.08%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 26        | 27.96%  |
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 15.05%  |
| Broadcom 58200                                                               | 14        | 15.05%  |
| Broadcom 5880                                                                | 13        | 13.98%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 9.68%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 5.38%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 5.38%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 4.3%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.08%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.08%   |
| Advanced Card Systems ACR39U                                                 | 1         | 1.08%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 974       | 64.72%  |
| 1     | 420       | 27.91%  |
| 2     | 98        | 6.51%   |
| 3     | 11        | 0.73%   |
| 10    | 1         | 0.07%   |
| 4     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 204       | 31.68%  |
| Graphics card            | 148       | 22.98%  |
| Chipcard                 | 84        | 13.04%  |
| Net/wireless             | 64        | 9.94%   |
| Multimedia controller    | 40        | 6.21%   |
| Camera                   | 28        | 4.35%   |
| Bluetooth                | 17        | 2.64%   |
| Storage                  | 16        | 2.48%   |
| Communication controller | 15        | 2.33%   |
| Card reader              | 8         | 1.24%   |
| Net/ethernet             | 5         | 0.78%   |
| Modem                    | 4         | 0.62%   |
| Sound                    | 3         | 0.47%   |
| Network                  | 2         | 0.31%   |
| Flash memory             | 2         | 0.31%   |
| Dvb card                 | 2         | 0.31%   |
| Storage/nvme             | 1         | 0.16%   |
| Firewire controller      | 1         | 0.16%   |

