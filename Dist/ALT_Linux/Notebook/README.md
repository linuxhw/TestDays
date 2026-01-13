ALT Linux - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for ALT Linux.

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

Total: 747

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | G570 20079                  | [6a21938418](https://linux-hardware.org/?probe=6a21938418) | Jan 02, 2026 |
| MSI           | Cyborg 15 B13WEKG           | [6fc3b6c3ac](https://linux-hardware.org/?probe=6fc3b6c3ac) | Dec 26, 2025 |
| Lenovo        | ThinkPad X13 Gen 2i 20WL... | [26e9e874ed](https://linux-hardware.org/?probe=26e9e874ed) | Dec 25, 2025 |
| ICL           | RAYbook Bi1504              | [f8987c77c0](https://linux-hardware.org/?probe=f8987c77c0) | Dec 25, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [005dcb2031](https://linux-hardware.org/?probe=005dcb2031) | Dec 23, 2025 |
| Lenovo        | G50-45 80E3                 | [83cb9c04d2](https://linux-hardware.org/?probe=83cb9c04d2) | Dec 22, 2025 |
| Aquarius      | NS685U R11                  | [7b547c107c](https://linux-hardware.org/?probe=7b547c107c) | Dec 19, 2025 |
| Lenovo        | B50-30 20382                | [d1e9734088](https://linux-hardware.org/?probe=d1e9734088) | Dec 18, 2025 |
| XIAOMI        | Redmi Book Pro 14 2024      | [dcb15b1ba8](https://linux-hardware.org/?probe=dcb15b1ba8) | Dec 17, 2025 |
| MSI           | Cyborg 15 B13WEKG           | [a1f0013017](https://linux-hardware.org/?probe=a1f0013017) | Dec 17, 2025 |
| Lenovo        | V15 G4 IRU 83A1             | [31c01fc5f8](https://linux-hardware.org/?probe=31c01fc5f8) | Dec 17, 2025 |
| ICL           | RAYbook Si1512              | [1d48d4ce35](https://linux-hardware.org/?probe=1d48d4ce35) | Dec 17, 2025 |
| HP            | Stream Notebook PC 11       | [ca335dd63a](https://linux-hardware.org/?probe=ca335dd63a) | Dec 15, 2025 |
| KVADRA        | NAU LE15T                   | [5c987775f5](https://linux-hardware.org/?probe=5c987775f5) | Dec 15, 2025 |
| ICL Techno    | B150i                       | [b483c152c7](https://linux-hardware.org/?probe=b483c152c7) | Dec 15, 2025 |
| Dell          | Inspiron 1525               | [16e6de888a](https://linux-hardware.org/?probe=16e6de888a) | Dec 13, 2025 |
| ICL           | S1523 G2R                   | [93fd185a4d](https://linux-hardware.org/?probe=93fd185a4d) | Dec 13, 2025 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | [f6516af3f7](https://linux-hardware.org/?probe=f6516af3f7) | Dec 12, 2025 |
| Aquarius      | NS685U R11                  | [ff64382536](https://linux-hardware.org/?probe=ff64382536) | Dec 12, 2025 |
| Acer          | TravelMate P215-53          | [47c631b9cb](https://linux-hardware.org/?probe=47c631b9cb) | Dec 12, 2025 |
| HP            | ProBook 4740s               | [98fc942dc5](https://linux-hardware.org/?probe=98fc942dc5) | Dec 12, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [b41bbbccd8](https://linux-hardware.org/?probe=b41bbbccd8) | Dec 11, 2025 |
| MSI           | Modern 14 C12MO             | [160ac79e85](https://linux-hardware.org/?probe=160ac79e85) | Dec 11, 2025 |
| Aquarius      | NS685U R11                  | [4b4e7ae459](https://linux-hardware.org/?probe=4b4e7ae459) | Dec 11, 2025 |
| Aquarius      | NS685U R11                  | [cfd5d20089](https://linux-hardware.org/?probe=cfd5d20089) | Dec 10, 2025 |
| Lenovo        | IdeaPad Slim 3 16IAH8 83... | [9656173e90](https://linux-hardware.org/?probe=9656173e90) | Dec 10, 2025 |
| DEPO Compu... | DPA156                      | [a2b32f6913](https://linux-hardware.org/?probe=a2b32f6913) | Dec 10, 2025 |
| ICL Techno    | F150a                       | [73bcb364a3](https://linux-hardware.org/?probe=73bcb364a3) | Dec 10, 2025 |
| Aquarius      | NS685U R11                  | [50dff82ef0](https://linux-hardware.org/?probe=50dff82ef0) | Dec 09, 2025 |
| HIPER Tech... | HIPER WORKBOOK              | [0475893176](https://linux-hardware.org/?probe=0475893176) | Dec 08, 2025 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [5dae3f6c72](https://linux-hardware.org/?probe=5dae3f6c72) | Dec 08, 2025 |
| Acer          | TravelMate P259-MG          | [203141bf35](https://linux-hardware.org/?probe=203141bf35) | Dec 07, 2025 |
| Acer          | TravelMate P259-MG          | [85e671b32b](https://linux-hardware.org/?probe=85e671b32b) | Dec 07, 2025 |
| Aquarius      | NS685U R11                  | [4c862fdee5](https://linux-hardware.org/?probe=4c862fdee5) | Dec 07, 2025 |
| MSI           | Thin 15 B12UCX              | [7ea3664f29](https://linux-hardware.org/?probe=7ea3664f29) | Dec 06, 2025 |
| ASUSTek       | X75VC                       | [0f19e12155](https://linux-hardware.org/?probe=0f19e12155) | Dec 05, 2025 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [41db734d35](https://linux-hardware.org/?probe=41db734d35) | Dec 05, 2025 |
| HP            | Laptop 15s-fq2xxx           | [7014704a94](https://linux-hardware.org/?probe=7014704a94) | Dec 03, 2025 |
| Samsung       | R428/P428                   | [bb0a9e0e82](https://linux-hardware.org/?probe=bb0a9e0e82) | Dec 03, 2025 |
| HP            | ProBook 445 G7              | [bbd70afdd2](https://linux-hardware.org/?probe=bbd70afdd2) | Nov 26, 2025 |
| ICL           | RAYbook Si1512              | [c2234581d0](https://linux-hardware.org/?probe=c2234581d0) | Nov 25, 2025 |
| ASUSTek       | N55SL                       | [21e70455f0](https://linux-hardware.org/?probe=21e70455f0) | Nov 23, 2025 |
| Lenovo        | ThinkPad T430 2347HM4       | [09150691a8](https://linux-hardware.org/?probe=09150691a8) | Nov 22, 2025 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [3a933c5efa](https://linux-hardware.org/?probe=3a933c5efa) | Nov 21, 2025 |
| Lenovo        | B50-30 20382                | [6e381bf622](https://linux-hardware.org/?probe=6e381bf622) | Nov 20, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | [6ddf85f653](https://linux-hardware.org/?probe=6ddf85f653) | Nov 19, 2025 |
| ASUSTek       | X75VC                       | [bf06213c40](https://linux-hardware.org/?probe=bf06213c40) | Nov 16, 2025 |
| ASUSTek       | X75VC                       | [c8a519a28d](https://linux-hardware.org/?probe=c8a519a28d) | Nov 16, 2025 |
| ICL           | RAYbook Si1514              | [60ea0e327e](https://linux-hardware.org/?probe=60ea0e327e) | Nov 16, 2025 |
| Unknown       | Unknown                     | [942ead11f1](https://linux-hardware.org/?probe=942ead11f1) | Nov 14, 2025 |
| HP            | Laptop 15s-eq0xxx           | [c4002e4738](https://linux-hardware.org/?probe=c4002e4738) | Nov 13, 2025 |
| ICL           | S1523 G1R                   | [1f8df1f4d3](https://linux-hardware.org/?probe=1f8df1f4d3) | Nov 13, 2025 |
| HP            | ProBook 440 G5              | [36d79e378d](https://linux-hardware.org/?probe=36d79e378d) | Nov 12, 2025 |
| Dell          | Inspiron 3542               | [4e9afd31e7](https://linux-hardware.org/?probe=4e9afd31e7) | Nov 12, 2025 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [a24d184f63](https://linux-hardware.org/?probe=a24d184f63) | Nov 06, 2025 |
| Dell          | Vostro 3460                 | [39a1b02911](https://linux-hardware.org/?probe=39a1b02911) | Nov 06, 2025 |
| n\a           | Unknown                     | [1eacb3ac3b](https://linux-hardware.org/?probe=1eacb3ac3b) | Nov 06, 2025 |
| ASUSTek       | X553MA                      | [6970923a5b](https://linux-hardware.org/?probe=6970923a5b) | Nov 05, 2025 |
| Acer          | Aspire 7738                 | [6bd8a5fc50](https://linux-hardware.org/?probe=6bd8a5fc50) | Nov 05, 2025 |
| ASUSTek       | K43SJ                       | [4cfa9a0eb2](https://linux-hardware.org/?probe=4cfa9a0eb2) | Nov 04, 2025 |
| Toshiba       | Satellite L850D-C6W         | [d07c8dc5da](https://linux-hardware.org/?probe=d07c8dc5da) | Nov 04, 2025 |
| Lenovo        | B590 20206                  | [984585e2e9](https://linux-hardware.org/?probe=984585e2e9) | Nov 02, 2025 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [bcd80bae0e](https://linux-hardware.org/?probe=bcd80bae0e) | Nov 01, 2025 |
| Lenovo        | Yoga Slim 7 14APU8 83AA     | [85140176a9](https://linux-hardware.org/?probe=85140176a9) | Nov 01, 2025 |
| Notebook      | N230WU                      | [10eb9d62e7](https://linux-hardware.org/?probe=10eb9d62e7) | Nov 01, 2025 |
| Lenovo        | B50-45 20388                | [9426c1bdb6](https://linux-hardware.org/?probe=9426c1bdb6) | Oct 31, 2025 |
| Dell          | Inspiron 3582               | [80543bd631](https://linux-hardware.org/?probe=80543bd631) | Oct 31, 2025 |
| ASUSTek       | K56CM                       | [04ec4c3b36](https://linux-hardware.org/?probe=04ec4c3b36) | Oct 29, 2025 |
| Apple         | MacBookPro5,5               | [3695ded55a](https://linux-hardware.org/?probe=3695ded55a) | Oct 29, 2025 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [4c3dd256bc](https://linux-hardware.org/?probe=4c3dd256bc) | Oct 29, 2025 |
| Aquarius      | CMP NS685U_4                | [34ed86c5c1](https://linux-hardware.org/?probe=34ed86c5c1) | Oct 28, 2025 |
| Acer          | Aspire A515-45              | [40c5a37f16](https://linux-hardware.org/?probe=40c5a37f16) | Oct 24, 2025 |
| XIAOMI        | Redmi Book Pro 14 2024      | [b579f09738](https://linux-hardware.org/?probe=b579f09738) | Oct 20, 2025 |
| HONOR         | FRI-HXX                     | [effc682978](https://linux-hardware.org/?probe=effc682978) | Oct 18, 2025 |
| HUAWEI        | RLEF-XX                     | [e7020e9a9b](https://linux-hardware.org/?probe=e7020e9a9b) | Oct 18, 2025 |
| Aquarius      | NS685U R11                  | [897261961b](https://linux-hardware.org/?probe=897261961b) | Oct 16, 2025 |
| HUAWEI        | BoDE-WXX9                   | [e349e61c48](https://linux-hardware.org/?probe=e349e61c48) | Oct 13, 2025 |
| XIAOMI        | Redmi Book Pro 14 2024      | [97d3d7533d](https://linux-hardware.org/?probe=97d3d7533d) | Oct 13, 2025 |
| Lenovo        | IdeaPad S340-14API 81NB     | [f18681b542](https://linux-hardware.org/?probe=f18681b542) | Oct 12, 2025 |
| Lenovo        | ThinkPad X13 Gen 1 20T3A... | [972ae6d16a](https://linux-hardware.org/?probe=972ae6d16a) | Oct 11, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5b293b2f9b](https://linux-hardware.org/?probe=5b293b2f9b) | Oct 03, 2025 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [fc011d0c04](https://linux-hardware.org/?probe=fc011d0c04) | Oct 02, 2025 |
| ICL           | S1523 G1R                   | [1d517f94a2](https://linux-hardware.org/?probe=1d517f94a2) | Oct 01, 2025 |
| ASUSTek       | TX300CA                     | [08b7ccb629](https://linux-hardware.org/?probe=08b7ccb629) | Oct 01, 2025 |
| XIAOMI        | Redmi Book Pro 14 2024      | [853403f11a](https://linux-hardware.org/?probe=853403f11a) | Sep 30, 2025 |
| Dell          | G3 3779                     | [cdcece12c4](https://linux-hardware.org/?probe=cdcece12c4) | Sep 26, 2025 |
| Lenovo        | V15 G4 AMN 82YU             | [62febec209](https://linux-hardware.org/?probe=62febec209) | Sep 26, 2025 |
| HP            | Pavilion Gaming Laptop 1... | [e61a602a03](https://linux-hardware.org/?probe=e61a602a03) | Sep 24, 2025 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [6ae8f9160c](https://linux-hardware.org/?probe=6ae8f9160c) | Sep 23, 2025 |
| Toshiba       | PORTEGE R930                | [54c1e32380](https://linux-hardware.org/?probe=54c1e32380) | Sep 22, 2025 |
| Unknown       | Unknown                     | [1091e8ef9c](https://linux-hardware.org/?probe=1091e8ef9c) | Sep 22, 2025 |
| HP            | 655                         | [f2e2c05b98](https://linux-hardware.org/?probe=f2e2c05b98) | Sep 20, 2025 |
| Unknown       | Unknown                     | [0518e9a30e](https://linux-hardware.org/?probe=0518e9a30e) | Sep 20, 2025 |
| HP            | Pavilion Laptop 15-eh1xx... | [37147e088e](https://linux-hardware.org/?probe=37147e088e) | Sep 19, 2025 |
| Unknown       | TG-1554                     | [fa7e6d3308](https://linux-hardware.org/?probe=fa7e6d3308) | Sep 19, 2025 |
| HP            | ProBook 450 G8 Notebook ... | [7ee68d890b](https://linux-hardware.org/?probe=7ee68d890b) | Sep 15, 2025 |
| Digma Pro     | Pro Cursus DN15R5-ADXW10    | [37d41a4e19](https://linux-hardware.org/?probe=37d41a4e19) | Sep 12, 2025 |
| TECNO Mobi... | MEGABOOK K15S AMD           | [d3f32b4761](https://linux-hardware.org/?probe=d3f32b4761) | Sep 05, 2025 |
| Dell          | Inspiron 15-3573            | [63a4b1180c](https://linux-hardware.org/?probe=63a4b1180c) | Aug 29, 2025 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [f4ba4e349a](https://linux-hardware.org/?probe=f4ba4e349a) | Aug 29, 2025 |
| HP            | 15                          | [118680a713](https://linux-hardware.org/?probe=118680a713) | Aug 27, 2025 |
| Acer          | Swift SF314-57              | [4f2d11e5ad](https://linux-hardware.org/?probe=4f2d11e5ad) | Aug 24, 2025 |
| Acer          | Swift SF314-57              | [a239a7b542](https://linux-hardware.org/?probe=a239a7b542) | Aug 24, 2025 |
| ICL Techno    | F150a                       | [cc2044bd96](https://linux-hardware.org/?probe=cc2044bd96) | Aug 19, 2025 |
| HP            | 655                         | [368a8fe849](https://linux-hardware.org/?probe=368a8fe849) | Aug 16, 2025 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [81d954fea4](https://linux-hardware.org/?probe=81d954fea4) | Aug 10, 2025 |
| HIPER         | SLIM                        | [46893f2bf5](https://linux-hardware.org/?probe=46893f2bf5) | Aug 07, 2025 |
| Acer          | Aspire A315-24P             | [d1c0bc5706](https://linux-hardware.org/?probe=d1c0bc5706) | Aug 06, 2025 |
| Razer         | Blade Stealth               | [61db124e05](https://linux-hardware.org/?probe=61db124e05) | Aug 03, 2025 |
| HP            | 255 15.6 inch G10           | [a92229701d](https://linux-hardware.org/?probe=a92229701d) | Aug 02, 2025 |
| iRU           | PC-B1811                    | [09272d0615](https://linux-hardware.org/?probe=09272d0615) | Jul 22, 2025 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [8b1c73fe54](https://linux-hardware.org/?probe=8b1c73fe54) | Jul 21, 2025 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [fba0700a47](https://linux-hardware.org/?probe=fba0700a47) | Jul 21, 2025 |
| Apple         | MacBookAir4,1               | [879c7df4a0](https://linux-hardware.org/?probe=879c7df4a0) | Jul 15, 2025 |
| DIGMA Pro     | Fortis M DN15R5-ADXW07      | [bf4579658c](https://linux-hardware.org/?probe=bf4579658c) | Jul 13, 2025 |
| Aquarius      | NS685U R11                  | [4c9a697997](https://linux-hardware.org/?probe=4c9a697997) | Jul 13, 2025 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [2726e85542](https://linux-hardware.org/?probe=2726e85542) | Jul 12, 2025 |
| Kraftway      | ACCORD                      | [ef230d8453](https://linux-hardware.org/?probe=ef230d8453) | Jul 10, 2025 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ce7e82abab](https://linux-hardware.org/?probe=ce7e82abab) | Jul 07, 2025 |
| Toshiba       | Satellite A660              | [bd0ff4663b](https://linux-hardware.org/?probe=bd0ff4663b) | Jul 06, 2025 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [556c8221b4](https://linux-hardware.org/?probe=556c8221b4) | Jul 05, 2025 |
| XIAOMI        | Redmi Book Pro 14 2024      | [9e4b658393](https://linux-hardware.org/?probe=9e4b658393) | Jul 01, 2025 |
| HP            | Pavilion Laptop 15-eh1xx... | [e47630738d](https://linux-hardware.org/?probe=e47630738d) | Jun 16, 2025 |
| Sony          | SVE1712S1RB                 | [afbdec3973](https://linux-hardware.org/?probe=afbdec3973) | Jun 15, 2025 |
| Sony          | VPCSB3M1R                   | [9ae1a40082](https://linux-hardware.org/?probe=9ae1a40082) | Jun 11, 2025 |
| XIAOMI        | Redmi Book Pro 14 2024      | [dfa515711c](https://linux-hardware.org/?probe=dfa515711c) | Jun 08, 2025 |
| HP            | Laptop 17-cp0xxx            | [5a79c3a432](https://linux-hardware.org/?probe=5a79c3a432) | Jun 02, 2025 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | [ed791c55b0](https://linux-hardware.org/?probe=ed791c55b0) | May 27, 2025 |
| XIAOMI        | Redmi Book Pro 14 2024      | [5ea6f3d91f](https://linux-hardware.org/?probe=5ea6f3d91f) | May 26, 2025 |
| Acer          | Aspire 5750G                | [9fc735cc96](https://linux-hardware.org/?probe=9fc735cc96) | May 25, 2025 |
| DEXP          | Atlas M15-I5W303            | [d32b07907f](https://linux-hardware.org/?probe=d32b07907f) | May 22, 2025 |
| HP            | ENVY 15                     | [3ac594e5ee](https://linux-hardware.org/?probe=3ac594e5ee) | May 21, 2025 |
| HP            | ENVY 15                     | [56588cc705](https://linux-hardware.org/?probe=56588cc705) | May 21, 2025 |
| HP            | Pavilion Gaming Laptop 1... | [ad2005d122](https://linux-hardware.org/?probe=ad2005d122) | May 12, 2025 |
| HP            | Pavilion Gaming Laptop 1... | [4cb6898e83](https://linux-hardware.org/?probe=4cb6898e83) | May 11, 2025 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [6416be7654](https://linux-hardware.org/?probe=6416be7654) | May 10, 2025 |
| HP            | Pavilion Laptop 15-eh1xx... | [7499feb73a](https://linux-hardware.org/?probe=7499feb73a) | May 06, 2025 |
| Lenovo        | V330-15IKB 81AX             | [fbc9a65d6f](https://linux-hardware.org/?probe=fbc9a65d6f) | May 06, 2025 |
| Fujitsu Si... | LIFEBOOK C1320              | [f413143ce5](https://linux-hardware.org/?probe=f413143ce5) | May 06, 2025 |
| Fujitsu Si... | LIFEBOOK C1320              | [c072b98d15](https://linux-hardware.org/?probe=c072b98d15) | May 06, 2025 |
| XIAOMI        | Redmi Book Pro 14 2024      | [0149e9472b](https://linux-hardware.org/?probe=0149e9472b) | May 05, 2025 |
| Graviton      | N14i-T                      | [81c50fb33f](https://linux-hardware.org/?probe=81c50fb33f) | May 04, 2025 |
| ASUSTek       | ASUS EXPERTBOOK BM1403CD... | [36612f8d5f](https://linux-hardware.org/?probe=36612f8d5f) | May 04, 2025 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [6753b934af](https://linux-hardware.org/?probe=6753b934af) | May 03, 2025 |
| Graviton      | N15i                        | [e16a9a36ee](https://linux-hardware.org/?probe=e16a9a36ee) | May 01, 2025 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [440f7741a1](https://linux-hardware.org/?probe=440f7741a1) | Apr 29, 2025 |
| TECNO Mobi... | MEGABOOK T14AA              | [aaf0cd7adb](https://linux-hardware.org/?probe=aaf0cd7adb) | Apr 28, 2025 |
| Acer          | Aspire ES1-732              | [36f8cd7ad4](https://linux-hardware.org/?probe=36f8cd7ad4) | Apr 27, 2025 |
| HONOR         | BRN-FXXC                    | [35d41fcbe3](https://linux-hardware.org/?probe=35d41fcbe3) | Apr 27, 2025 |
| XIAOMI        | Redmi Book Pro 14 2024      | [7e457b7c16](https://linux-hardware.org/?probe=7e457b7c16) | Apr 25, 2025 |
| MSI           | Modern 14 C7M               | [4012ed7b2f](https://linux-hardware.org/?probe=4012ed7b2f) | Apr 24, 2025 |
| Dell          | G15 5511                    | [22355c5b56](https://linux-hardware.org/?probe=22355c5b56) | Apr 17, 2025 |
| HUAWEI        | RLEF-XX                     | [3baa5ccf57](https://linux-hardware.org/?probe=3baa5ccf57) | Apr 13, 2025 |
| Lenovo        | ThinkBook 16 G6+ AHP 21L... | [bf0bb8e4d9](https://linux-hardware.org/?probe=bf0bb8e4d9) | Apr 10, 2025 |
| Purism        | Librem 15 v3                | [dd40993678](https://linux-hardware.org/?probe=dd40993678) | Apr 07, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | [1942e3e6cd](https://linux-hardware.org/?probe=1942e3e6cd) | Apr 06, 2025 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [46dff9bbb2](https://linux-hardware.org/?probe=46dff9bbb2) | Apr 05, 2025 |
| Lenovo        | XiaoXinPro 16 AHP9 83D5     | [6676dba951](https://linux-hardware.org/?probe=6676dba951) | Apr 04, 2025 |
| Machcreato... | Prime X16                   | [1e5716d77d](https://linux-hardware.org/?probe=1e5716d77d) | Apr 04, 2025 |
| MSI           | Modern 14 C7M               | [073f3cb6e6](https://linux-hardware.org/?probe=073f3cb6e6) | Mar 31, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [7482a3ddc0](https://linux-hardware.org/?probe=7482a3ddc0) | Mar 31, 2025 |
| MSI           | Modern 14 C7M               | [8a17398e93](https://linux-hardware.org/?probe=8a17398e93) | Mar 29, 2025 |
| XIAOMI        | Redmi Book Pro 14 2024      | [88ba9371aa](https://linux-hardware.org/?probe=88ba9371aa) | Mar 27, 2025 |
| Aquarius      | NS483                       | [4c81c8c123](https://linux-hardware.org/?probe=4c81c8c123) | Mar 26, 2025 |
| MSI           | Modern 14 C7M               | [f9ea81f75a](https://linux-hardware.org/?probe=f9ea81f75a) | Mar 25, 2025 |
| Unknown       | Unknown                     | [e70c6faa9d](https://linux-hardware.org/?probe=e70c6faa9d) | Mar 17, 2025 |
| MSI           | Modern 14 C7M               | [454e285a9a](https://linux-hardware.org/?probe=454e285a9a) | Mar 13, 2025 |
| Machcreato... | Prime X16                   | [8cba4b3eb0](https://linux-hardware.org/?probe=8cba4b3eb0) | Mar 10, 2025 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | [e5efb5ebdb](https://linux-hardware.org/?probe=e5efb5ebdb) | Mar 09, 2025 |
| HP            | Pavilion Laptop 15-eh1xx... | [c53182a1e2](https://linux-hardware.org/?probe=c53182a1e2) | Mar 09, 2025 |
| ICL Techno    | F140a                       | [a190664923](https://linux-hardware.org/?probe=a190664923) | Mar 06, 2025 |
| MSI           | Modern 15 A5M               | [57aa336a9a](https://linux-hardware.org/?probe=57aa336a9a) | Mar 06, 2025 |
| XIAOMI        | Redmi Book Pro 14 2024      | [86f376f101](https://linux-hardware.org/?probe=86f376f101) | Feb 28, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [1a42ef1714](https://linux-hardware.org/?probe=1a42ef1714) | Feb 28, 2025 |
| ICL Techno    | F160a                       | [635a0cd96b](https://linux-hardware.org/?probe=635a0cd96b) | Feb 24, 2025 |
| ICL Techno    | F160a                       | [bc5d7ad61b](https://linux-hardware.org/?probe=bc5d7ad61b) | Feb 24, 2025 |
| Unknown       | P142                        | [62bcb30d69](https://linux-hardware.org/?probe=62bcb30d69) | Feb 23, 2025 |
| Unknown       | P142                        | [ad8cd65650](https://linux-hardware.org/?probe=ad8cd65650) | Feb 23, 2025 |
| MSI           | Bravo 15 B5DD               | [e695452eb2](https://linux-hardware.org/?probe=e695452eb2) | Feb 23, 2025 |
| Acer          | Aspire A315-24P             | [0f1bbc0f44](https://linux-hardware.org/?probe=0f1bbc0f44) | Feb 20, 2025 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [62c509ab44](https://linux-hardware.org/?probe=62c509ab44) | Feb 20, 2025 |
| Dell          | Vostro 14 5410              | [abcbca9f5e](https://linux-hardware.org/?probe=abcbca9f5e) | Feb 20, 2025 |
| HONOR         | FMI-XX                      | [bc52ef391c](https://linux-hardware.org/?probe=bc52ef391c) | Feb 15, 2025 |
| Acer          | Nitro AN515-46              | [41f3d6b750](https://linux-hardware.org/?probe=41f3d6b750) | Feb 08, 2025 |
| XIAOMI        | Redmi Book Pro 14 2024      | [ad0f402b7b](https://linux-hardware.org/?probe=ad0f402b7b) | Feb 05, 2025 |
| MSI           | Unknown                     | [1222750843](https://linux-hardware.org/?probe=1222750843) | Feb 03, 2025 |
| Acer          | Extensa 5620                | [9321ab00fd](https://linux-hardware.org/?probe=9321ab00fd) | Feb 03, 2025 |
| HUAWEI        | BOM-WXX9                    | [47c90a0619](https://linux-hardware.org/?probe=47c90a0619) | Feb 02, 2025 |
| mtech         | MTL1578                     | [233976f37a](https://linux-hardware.org/?probe=233976f37a) | Jan 26, 2025 |
| mtech         | MTL1578                     | [52c0a17c9c](https://linux-hardware.org/?probe=52c0a17c9c) | Jan 26, 2025 |
| Dell          | Latitude 3480               | [ad53f73631](https://linux-hardware.org/?probe=ad53f73631) | Jan 25, 2025 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [98b225b8b3](https://linux-hardware.org/?probe=98b225b8b3) | Jan 25, 2025 |
| Lenovo        | ThinkPad T480 20L6S57T00    | [98d3c9aea0](https://linux-hardware.org/?probe=98d3c9aea0) | Jan 25, 2025 |
| ICL           | RAYbook Si1512              | [9240e6bf22](https://linux-hardware.org/?probe=9240e6bf22) | Jan 23, 2025 |
| ICL           | RAYbook Si1512              | [c1de9ebc8f](https://linux-hardware.org/?probe=c1de9ebc8f) | Jan 23, 2025 |
| XIAOMI        | Redmi Book Pro 14 2024      | [6326456fb3](https://linux-hardware.org/?probe=6326456fb3) | Jan 17, 2025 |
| Lenovo        | ThinkBook 16 G6+ AHP 21L... | [525bcfa022](https://linux-hardware.org/?probe=525bcfa022) | Jan 16, 2025 |
| Aquarius      | NE355                       | [ce0456e189](https://linux-hardware.org/?probe=ce0456e189) | Jan 14, 2025 |
| Aquarius      | NE355                       | [d7fb9e48b3](https://linux-hardware.org/?probe=d7fb9e48b3) | Jan 14, 2025 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [14b60f1b40](https://linux-hardware.org/?probe=14b60f1b40) | Jan 13, 2025 |
| Aquarius      | CMP NS616                   | [f58415bb80](https://linux-hardware.org/?probe=f58415bb80) | Jan 10, 2025 |
| Aquarius      | CMP NS616                   | [bcf8a673b3](https://linux-hardware.org/?probe=bcf8a673b3) | Jan 10, 2025 |
| Apple         | MacBookPro16,1              | [ae1161bbb2](https://linux-hardware.org/?probe=ae1161bbb2) | Jan 07, 2025 |
| HP            | Pavilion Laptop 15-eh1xx... | [c6252ac077](https://linux-hardware.org/?probe=c6252ac077) | Jan 07, 2025 |
| Lenovo        | G505 20240                  | [b6181c89ff](https://linux-hardware.org/?probe=b6181c89ff) | Jan 05, 2025 |
| Apple         | MacBookPro16,1              | [ba278c0390](https://linux-hardware.org/?probe=ba278c0390) | Jan 04, 2025 |
| Apple         | MacBookPro16,1              | [d49932671f](https://linux-hardware.org/?probe=d49932671f) | Jan 04, 2025 |
| ASUSTek       | K50IJ                       | [9c75aa0285](https://linux-hardware.org/?probe=9c75aa0285) | Jan 04, 2025 |
| HP            | Pavilion Laptop 15-eh1xx... | [8c51d26687](https://linux-hardware.org/?probe=8c51d26687) | Dec 27, 2024 |
| Acer          | Extensa 215-23              | [97337ddb76](https://linux-hardware.org/?probe=97337ddb76) | Dec 26, 2024 |
| Infinix       | INBOOK Y4H Max              | [e5a91667f9](https://linux-hardware.org/?probe=e5a91667f9) | Dec 21, 2024 |
| Lenovo        | B50-30 20382                | [4ccf2f7c9a](https://linux-hardware.org/?probe=4ccf2f7c9a) | Dec 17, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [991cc2d32a](https://linux-hardware.org/?probe=991cc2d32a) | Dec 13, 2024 |
| LTD Delovo... | 14TLH                       | [8c4728d52e](https://linux-hardware.org/?probe=8c4728d52e) | Dec 12, 2024 |
| Acer          | Aspire E5-573G              | [90ff703a16](https://linux-hardware.org/?probe=90ff703a16) | Dec 09, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [5b43ecc284](https://linux-hardware.org/?probe=5b43ecc284) | Dec 08, 2024 |
| Maibenben     | Perfectum Series            | [02a7c3fca7](https://linux-hardware.org/?probe=02a7c3fca7) | Nov 29, 2024 |
| Maibenben     | Perfectum Series            | [eb0de561cc](https://linux-hardware.org/?probe=eb0de561cc) | Nov 28, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [ab329aa759](https://linux-hardware.org/?probe=ab329aa759) | Nov 24, 2024 |
| ASUSTek       | X75VC                       | [806fb829db](https://linux-hardware.org/?probe=806fb829db) | Nov 23, 2024 |
| Samsung       | RV413/RV513                 | [fc599fadf9](https://linux-hardware.org/?probe=fc599fadf9) | Nov 21, 2024 |
| Samsung       | RV413/RV513                 | [5df100f2d2](https://linux-hardware.org/?probe=5df100f2d2) | Nov 21, 2024 |
| Acer          | Swift SF114-34              | [55147661fe](https://linux-hardware.org/?probe=55147661fe) | Nov 18, 2024 |
| Acer          | Aspire 3820                 | [166c3be5a7](https://linux-hardware.org/?probe=166c3be5a7) | Nov 16, 2024 |
| ASUSTek       | UX310UA                     | [104830f2b8](https://linux-hardware.org/?probe=104830f2b8) | Oct 20, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [8e6ad7a9bc](https://linux-hardware.org/?probe=8e6ad7a9bc) | Oct 17, 2024 |
| Lenovo        | ThinkPad X240 20AMS3AE04    | [fcb1f007a5](https://linux-hardware.org/?probe=fcb1f007a5) | Oct 16, 2024 |
| Unknown       | Unknown                     | [af5eaabfc2](https://linux-hardware.org/?probe=af5eaabfc2) | Oct 14, 2024 |
| Maibenben     | Perfectum Series            | [055b2907a1](https://linux-hardware.org/?probe=055b2907a1) | Oct 12, 2024 |
| Digma         | ES6022EW                    | [9962907672](https://linux-hardware.org/?probe=9962907672) | Oct 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [a64d1227cd](https://linux-hardware.org/?probe=a64d1227cd) | Oct 07, 2024 |
| Maibenben     | Perfectum Series            | [3ca7c3595a](https://linux-hardware.org/?probe=3ca7c3595a) | Oct 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [f8ec20365c](https://linux-hardware.org/?probe=f8ec20365c) | Oct 02, 2024 |
| HUAWEI        | BOM-WXX9                    | [5cab2e516c](https://linux-hardware.org/?probe=5cab2e516c) | Sep 28, 2024 |
| HUAWEI        | BOM-WXX9                    | [004f265b76](https://linux-hardware.org/?probe=004f265b76) | Sep 28, 2024 |
| Dell          | Inspiron 5520               | [7674f2b4d4](https://linux-hardware.org/?probe=7674f2b4d4) | Sep 27, 2024 |
| MSI           | Modern 15 A5M               | [7983ebe0a8](https://linux-hardware.org/?probe=7983ebe0a8) | Sep 26, 2024 |
| HP            | Laptop 15-bw0xx             | [b080df96d5](https://linux-hardware.org/?probe=b080df96d5) | Sep 26, 2024 |
| Acer          | Aspire A315-44P             | [7345591513](https://linux-hardware.org/?probe=7345591513) | Sep 26, 2024 |
| Acer          | Aspire A315-44P             | [169fa55862](https://linux-hardware.org/?probe=169fa55862) | Sep 26, 2024 |
| KUANLITU      | S series                    | [dfbb1b67c9](https://linux-hardware.org/?probe=dfbb1b67c9) | Sep 18, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [3f6b5da510](https://linux-hardware.org/?probe=3f6b5da510) | Sep 15, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [dd9c45fac7](https://linux-hardware.org/?probe=dd9c45fac7) | Sep 14, 2024 |
| DEPO Compu... | DPC156                      | [a869ccaa68](https://linux-hardware.org/?probe=a869ccaa68) | Sep 13, 2024 |
| DEPO Compu... | DPC156                      | [4ce9fbc296](https://linux-hardware.org/?probe=4ce9fbc296) | Sep 13, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [f67b0818c6](https://linux-hardware.org/?probe=f67b0818c6) | Sep 11, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [e83c9c0dc1](https://linux-hardware.org/?probe=e83c9c0dc1) | Sep 09, 2024 |
| Acer          | Swift SF114-34              | [5024e5c57a](https://linux-hardware.org/?probe=5024e5c57a) | Sep 03, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [0232ff85b0](https://linux-hardware.org/?probe=0232ff85b0) | Sep 02, 2024 |
| HONOR         | GLO-GXXX                    | [a9c3bcdc17](https://linux-hardware.org/?probe=a9c3bcdc17) | Aug 28, 2024 |
| Maibenben     | Perfectum Series            | [174965af02](https://linux-hardware.org/?probe=174965af02) | Aug 27, 2024 |
| Maibenben     | Perfectum Series            | [5664d23a84](https://linux-hardware.org/?probe=5664d23a84) | Aug 26, 2024 |
| Digma         | Pro Fortis M DN15P3-8CXN... | [14b631992b](https://linux-hardware.org/?probe=14b631992b) | Aug 26, 2024 |
| HONOR         | GLO-GXXX                    | [2455c48ab5](https://linux-hardware.org/?probe=2455c48ab5) | Aug 25, 2024 |
| Lenovo        | ThinkPad T480 20L6S57T00    | [10256fb963](https://linux-hardware.org/?probe=10256fb963) | Aug 24, 2024 |
| HUAWEI        | RLEF-XX                     | [34f2013170](https://linux-hardware.org/?probe=34f2013170) | Aug 22, 2024 |
| ASUSTek       | ROG Strix G733QM_G733QM     | [598d872013](https://linux-hardware.org/?probe=598d872013) | Aug 20, 2024 |
| ASUSTek       | ROG Strix G733QM_G733QM     | [b969d73cb0](https://linux-hardware.org/?probe=b969d73cb0) | Aug 20, 2024 |
| HP            | EliteBook 8470p             | [82c857ca2e](https://linux-hardware.org/?probe=82c857ca2e) | Aug 17, 2024 |
| Sony          | VGN-AR51J                   | [68abb3faf1](https://linux-hardware.org/?probe=68abb3faf1) | Aug 15, 2024 |
| ASUSTek       | 1015BXO                     | [f842010ab4](https://linux-hardware.org/?probe=f842010ab4) | Aug 13, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [e85becff2f](https://linux-hardware.org/?probe=e85becff2f) | Aug 10, 2024 |
| Timi          | RedmiBook 14-APCS           | [7b98bc1efa](https://linux-hardware.org/?probe=7b98bc1efa) | Aug 03, 2024 |
| Timi          | RedmiBook 14-APCS           | [52bfb9882c](https://linux-hardware.org/?probe=52bfb9882c) | Aug 03, 2024 |
| LG Electro... | 15Z90ST-G.AAW4U1            | [9cf11c7129](https://linux-hardware.org/?probe=9cf11c7129) | Aug 02, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [4bdee79709](https://linux-hardware.org/?probe=4bdee79709) | Aug 01, 2024 |
| 3Logic Gro... | Graviton N15i               | [28794c402f](https://linux-hardware.org/?probe=28794c402f) | Aug 01, 2024 |
| HONOR         | HYM-WXX                     | [497089dc56](https://linux-hardware.org/?probe=497089dc56) | Jul 30, 2024 |
| Apple         | MacBookPro14,3              | [4727ea5521](https://linux-hardware.org/?probe=4727ea5521) | Jul 29, 2024 |
| Acer          | Aspire V3-571G              | [8db668cfb5](https://linux-hardware.org/?probe=8db668cfb5) | Jul 27, 2024 |
| ICL Techno    | F140a                       | [6c9498bc2f](https://linux-hardware.org/?probe=6c9498bc2f) | Jul 24, 2024 |
| HONOR         | NMH-WCX9                    | [9d91f90ded](https://linux-hardware.org/?probe=9d91f90ded) | Jul 22, 2024 |
| Intel         | H81U                        | [db7284262b](https://linux-hardware.org/?probe=db7284262b) | Jul 21, 2024 |
| Sony          | VPCCA2S1R                   | [65ea977de0](https://linux-hardware.org/?probe=65ea977de0) | Jul 17, 2024 |
| MACHENIKE     | L17A                        | [5d481d8baf](https://linux-hardware.org/?probe=5d481d8baf) | Jul 09, 2024 |
| MACHENIKE     | L17A                        | [25167c9d0b](https://linux-hardware.org/?probe=25167c9d0b) | Jul 09, 2024 |
| Acer          | Aspire A515-57              | [1b9c516078](https://linux-hardware.org/?probe=1b9c516078) | Jul 09, 2024 |
| Acer          | Aspire E3-112               | [8dde0e933a](https://linux-hardware.org/?probe=8dde0e933a) | Jul 05, 2024 |
| Acer          | Aspire E3-112               | [9a9c5efccd](https://linux-hardware.org/?probe=9a9c5efccd) | Jul 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [5ecae8cb36](https://linux-hardware.org/?probe=5ecae8cb36) | Jun 28, 2024 |
| Infinix       | INBOOK Y1 PLUS              | [2b099e1636](https://linux-hardware.org/?probe=2b099e1636) | Jun 26, 2024 |
| MACHENIKE     | S16C                        | [6e918896fd](https://linux-hardware.org/?probe=6e918896fd) | Jun 20, 2024 |
| HONOR         | NMH-WCX9                    | [6b87d089e7](https://linux-hardware.org/?probe=6b87d089e7) | Jun 19, 2024 |
| ASUSTek       | K43SJ                       | [01cca13919](https://linux-hardware.org/?probe=01cca13919) | Jun 11, 2024 |
| Dell          | Inspiron M5110              | [fe89ff584f](https://linux-hardware.org/?probe=fe89ff584f) | Jun 10, 2024 |
| Lenovo        | V15 G2 ALC 82KD             | [fc313f3019](https://linux-hardware.org/?probe=fc313f3019) | Jun 04, 2024 |
| HP            | Pavilion 15                 | [5c070443f1](https://linux-hardware.org/?probe=5c070443f1) | Jun 01, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [9696b9931a](https://linux-hardware.org/?probe=9696b9931a) | May 31, 2024 |
| HP            | EliteBook 850 G1            | [36e9f75edd](https://linux-hardware.org/?probe=36e9f75edd) | May 30, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [7d3f6f86dd](https://linux-hardware.org/?probe=7d3f6f86dd) | May 30, 2024 |
| ASUSTek       | K43SJ                       | [527d676304](https://linux-hardware.org/?probe=527d676304) | May 30, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | [f26b84f0e9](https://linux-hardware.org/?probe=f26b84f0e9) | May 26, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a3e3a8bc39](https://linux-hardware.org/?probe=a3e3a8bc39) | May 25, 2024 |
| Acer          | Aspire 5742G                | [5fcd94ffeb](https://linux-hardware.org/?probe=5fcd94ffeb) | May 25, 2024 |
| Unknown       | Unknown                     | [63b860d0cc](https://linux-hardware.org/?probe=63b860d0cc) | May 22, 2024 |
| Unknown       | Unknown                     | [5aa1cb0e36](https://linux-hardware.org/?probe=5aa1cb0e36) | May 22, 2024 |
| Kraftway      | ACCORD                      | [73d302e1ec](https://linux-hardware.org/?probe=73d302e1ec) | May 21, 2024 |
| Lenovo        | IdeaPad S340-14API 81NB     | [12c1f66b60](https://linux-hardware.org/?probe=12c1f66b60) | May 12, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f83dfd7434](https://linux-hardware.org/?probe=f83dfd7434) | May 11, 2024 |
| ASUSTek       | X550CC                      | [47b8006c42](https://linux-hardware.org/?probe=47b8006c42) | May 05, 2024 |
| Infinix       | INBOOK X2 GEN11             | [9002e7e3c5](https://linux-hardware.org/?probe=9002e7e3c5) | May 04, 2024 |
| HP            | ProBook 6450b               | [c4d1788222](https://linux-hardware.org/?probe=c4d1788222) | May 03, 2024 |
| Lenovo        | V130-15IKB 81HN             | [d00e301298](https://linux-hardware.org/?probe=d00e301298) | May 03, 2024 |
| Echips Imp... | NX140A-S                    | [dec569991b](https://linux-hardware.org/?probe=dec569991b) | Apr 30, 2024 |
| Lenovo        | ThinkPad T480 20L6S7MP00    | [ea3db5dd3c](https://linux-hardware.org/?probe=ea3db5dd3c) | Apr 29, 2024 |
| ASUSTek       | N53Jf                       | [02cf0c80c7](https://linux-hardware.org/?probe=02cf0c80c7) | Apr 29, 2024 |
| Intel Clie... | LAPAC71H                    | [a1a6c57c02](https://linux-hardware.org/?probe=a1a6c57c02) | Apr 28, 2024 |
| Intel Clie... | LAPAC71H                    | [c365e08c03](https://linux-hardware.org/?probe=c365e08c03) | Apr 20, 2024 |
| HP            | Laptop 15-bw0xx             | [1291c4934f](https://linux-hardware.org/?probe=1291c4934f) | Apr 18, 2024 |
| Aquarius      | NS685U R11                  | [b5b6ca6e69](https://linux-hardware.org/?probe=b5b6ca6e69) | Apr 18, 2024 |
| ICL Techno    | F140a                       | [bd46cdda52](https://linux-hardware.org/?probe=bd46cdda52) | Apr 16, 2024 |
| IP3 Tech      | ZEN1                        | [d85ba98172](https://linux-hardware.org/?probe=d85ba98172) | Apr 13, 2024 |
| HP            | ProBook 4520s               | [6886f7483d](https://linux-hardware.org/?probe=6886f7483d) | Apr 09, 2024 |
| HUAWEI        | BOM-WXX9                    | [a5ab134bcf](https://linux-hardware.org/?probe=a5ab134bcf) | Apr 07, 2024 |
| HP            | Laptop 15-gw0xxx            | [ba96d62394](https://linux-hardware.org/?probe=ba96d62394) | Apr 04, 2024 |
| DEPO Compu... | DPC156                      | [9320cdbb02](https://linux-hardware.org/?probe=9320cdbb02) | Apr 04, 2024 |
| HP            | Unknown                     | [8247de95f8](https://linux-hardware.org/?probe=8247de95f8) | Mar 22, 2024 |
| TECNO Mobi... | MEGABOOK T15DA              | [c9580df31c](https://linux-hardware.org/?probe=c9580df31c) | Mar 20, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [09805af67f](https://linux-hardware.org/?probe=09805af67f) | Mar 20, 2024 |
| Valve         | Jupiter                     | [5685e8711f](https://linux-hardware.org/?probe=5685e8711f) | Mar 15, 2024 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [898f0686a4](https://linux-hardware.org/?probe=898f0686a4) | Mar 14, 2024 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [fa3d8709e3](https://linux-hardware.org/?probe=fa3d8709e3) | Mar 14, 2024 |
| Dell          | G15 5511                    | [ff19732587](https://linux-hardware.org/?probe=ff19732587) | Mar 11, 2024 |
| HP            | Pavilion dv6                | [89a9407fb7](https://linux-hardware.org/?probe=89a9407fb7) | Mar 06, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1502CVA... | [0222a2f98a](https://linux-hardware.org/?probe=0222a2f98a) | Mar 05, 2024 |
| ICL Techno    | F140a                       | [2bdc9718e7](https://linux-hardware.org/?probe=2bdc9718e7) | Mar 03, 2024 |
| HP            | Pavilion dv6                | [4ed39c3833](https://linux-hardware.org/?probe=4ed39c3833) | Mar 03, 2024 |
| ASUSTek       | K53SJ                       | [4f8e5147ba](https://linux-hardware.org/?probe=4f8e5147ba) | Feb 27, 2024 |
| ASUSTek       | X550CC                      | [d9b2c3a575](https://linux-hardware.org/?probe=d9b2c3a575) | Feb 26, 2024 |
| TECNO Mobi... | MEGABOOK T14TA              | [9874f5d3c1](https://linux-hardware.org/?probe=9874f5d3c1) | Feb 20, 2024 |
| iRU           | 15TLI                       | [2af6577cf0](https://linux-hardware.org/?probe=2af6577cf0) | Feb 19, 2024 |
| HP            | ProBook 6450b               | [1a4b4a3788](https://linux-hardware.org/?probe=1a4b4a3788) | Feb 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [8317f520c9](https://linux-hardware.org/?probe=8317f520c9) | Feb 16, 2024 |
| Acer          | Aspire E5-571G              | [29a77bf074](https://linux-hardware.org/?probe=29a77bf074) | Feb 14, 2024 |
| HP            | ENVY 6                      | [ccd623bfad](https://linux-hardware.org/?probe=ccd623bfad) | Feb 13, 2024 |
| Lenovo        | ThinkPad E490 20N80017RT    | [bad3f7f138](https://linux-hardware.org/?probe=bad3f7f138) | Feb 09, 2024 |
| Lenovo        | V370 HuronRiver Platform    | [1ad82367ba](https://linux-hardware.org/?probe=1ad82367ba) | Feb 07, 2024 |
| Sony          | VPCSA2Z9R                   | [88e21aee02](https://linux-hardware.org/?probe=88e21aee02) | Feb 06, 2024 |
| Aquarius      | CMP NS685U_4                | [1115097f9a](https://linux-hardware.org/?probe=1115097f9a) | Feb 05, 2024 |
| MSI           | Modern 14 B11MOU            | [a5b3665f64](https://linux-hardware.org/?probe=a5b3665f64) | Feb 02, 2024 |
| Unknown       | Unknown                     | [737a25372c](https://linux-hardware.org/?probe=737a25372c) | Jan 03, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [1372c9e7e6](https://linux-hardware.org/?probe=1372c9e7e6) | Dec 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [a4d9a001ff](https://linux-hardware.org/?probe=a4d9a001ff) | Dec 29, 2023 |
| HP            | ProBook 6460b               | [4a6a6b9b9d](https://linux-hardware.org/?probe=4a6a6b9b9d) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7fdd8a3f38](https://linux-hardware.org/?probe=7fdd8a3f38) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a1fd8cc737](https://linux-hardware.org/?probe=a1fd8cc737) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [188dea7b4b](https://linux-hardware.org/?probe=188dea7b4b) | Dec 19, 2023 |
| Dell          | Inspiron 1545               | [cd3471d9e5](https://linux-hardware.org/?probe=cd3471d9e5) | Dec 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a53b2d9ba9](https://linux-hardware.org/?probe=a53b2d9ba9) | Dec 15, 2023 |
| Lenovo        | G700                        | [97b63677f6](https://linux-hardware.org/?probe=97b63677f6) | Dec 11, 2023 |
| Lenovo        | 3000 G410                   | [439199aff4](https://linux-hardware.org/?probe=439199aff4) | Dec 04, 2023 |
| Acer          | Nitro AN517-52              | [80b6f0b84a](https://linux-hardware.org/?probe=80b6f0b84a) | Dec 02, 2023 |
| MSI           | GT70 2PC                    | [0806985a42](https://linux-hardware.org/?probe=0806985a42) | Nov 29, 2023 |
| Dell          | Inspiron 15-3565            | [7d7541ceb2](https://linux-hardware.org/?probe=7d7541ceb2) | Nov 29, 2023 |
| Lenovo        | G700                        | [3c8ae88b16](https://linux-hardware.org/?probe=3c8ae88b16) | Nov 29, 2023 |
| HUAWEI        | CREF-XX                     | [630d8838dc](https://linux-hardware.org/?probe=630d8838dc) | Nov 27, 2023 |
| MSI           | GT70 2PC                    | [c4589b53bb](https://linux-hardware.org/?probe=c4589b53bb) | Nov 26, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [7078ba99e1](https://linux-hardware.org/?probe=7078ba99e1) | Nov 26, 2023 |
| HP            | Laptop 17-cn2xxx            | [59c09c7be1](https://linux-hardware.org/?probe=59c09c7be1) | Nov 11, 2023 |
| Dell          | Inspiron N5050              | [2ec8097b67](https://linux-hardware.org/?probe=2ec8097b67) | Oct 31, 2023 |
| Acer          | Extensa 2520G               | [bcc4e567f3](https://linux-hardware.org/?probe=bcc4e567f3) | Oct 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [856d9c4a75](https://linux-hardware.org/?probe=856d9c4a75) | Oct 28, 2023 |
| HP            | Laptop 15-bw0xx             | [63c6987bfa](https://linux-hardware.org/?probe=63c6987bfa) | Oct 28, 2023 |
| Acer          | Ferrari 3200                | [52f9e06bf9](https://linux-hardware.org/?probe=52f9e06bf9) | Oct 25, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [f8f7f85d08](https://linux-hardware.org/?probe=f8f7f85d08) | Oct 25, 2023 |
| Acer          | Extensa 2520G               | [d0e546f6d6](https://linux-hardware.org/?probe=d0e546f6d6) | Oct 25, 2023 |
| Lenovo        | V580c 20160                 | [178fe3a497](https://linux-hardware.org/?probe=178fe3a497) | Oct 25, 2023 |
| HONOR         | NMH-WDX9                    | [3a0782c335](https://linux-hardware.org/?probe=3a0782c335) | Oct 25, 2023 |
| Acer          | Extensa 2520G               | [1b58a52442](https://linux-hardware.org/?probe=1b58a52442) | Oct 25, 2023 |
| Unknown       | Unknown                     | [1e239308b1](https://linux-hardware.org/?probe=1e239308b1) | Oct 21, 2023 |
| Unknown       | Unknown                     | [125d0eedc8](https://linux-hardware.org/?probe=125d0eedc8) | Oct 21, 2023 |
| HP            | 255 G4                      | [0290beac3f](https://linux-hardware.org/?probe=0290beac3f) | Oct 19, 2023 |
| Maibenben     | MaiBook X series            | [901cc6bd8a](https://linux-hardware.org/?probe=901cc6bd8a) | Oct 14, 2023 |
| ASUSTek       | T100TAM                     | [b809251676](https://linux-hardware.org/?probe=b809251676) | Oct 11, 2023 |
| Unknown       | Unknown                     | [52694348d2](https://linux-hardware.org/?probe=52694348d2) | Oct 10, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | [7f32c31118](https://linux-hardware.org/?probe=7f32c31118) | Oct 09, 2023 |
| ROMBICA       | myBook Eclipse              | [d56fec4995](https://linux-hardware.org/?probe=d56fec4995) | Oct 07, 2023 |
| MSI           | Modern 15 B12M              | [1bbe75aa56](https://linux-hardware.org/?probe=1bbe75aa56) | Oct 04, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [61278c0720](https://linux-hardware.org/?probe=61278c0720) | Oct 04, 2023 |
| HUAWEI        | RLEF-XX                     | [06499eec7c](https://linux-hardware.org/?probe=06499eec7c) | Oct 04, 2023 |
| F-PLUS EQU... | Unknown                     | [104a5f30e4](https://linux-hardware.org/?probe=104a5f30e4) | Oct 04, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [90cb02d71d](https://linux-hardware.org/?probe=90cb02d71d) | Oct 04, 2023 |
| F-PLUS EQU... | FNB-156-P1                  | [aa9a99ccb5](https://linux-hardware.org/?probe=aa9a99ccb5) | Oct 04, 2023 |
| F-PLUS EQU... | FNB-156-P1                  | [200217831d](https://linux-hardware.org/?probe=200217831d) | Oct 04, 2023 |
| Lenovo        | G700                        | [7090569f96](https://linux-hardware.org/?probe=7090569f96) | Oct 03, 2023 |
| HIPER         | WORKBOOK                    | [902f508256](https://linux-hardware.org/?probe=902f508256) | Oct 03, 2023 |
| ROMBICA       | myBook Eclipse              | [004e1dc4fd](https://linux-hardware.org/?probe=004e1dc4fd) | Sep 28, 2023 |
| Infinix       | INBOOK X2 GEN11             | [2ac0204275](https://linux-hardware.org/?probe=2ac0204275) | Sep 28, 2023 |
| Kraftway      | ACCORD                      | [df4d5654d5](https://linux-hardware.org/?probe=df4d5654d5) | Sep 21, 2023 |
| iRU           | 17ALC                       | [2d0b23c813](https://linux-hardware.org/?probe=2d0b23c813) | Sep 18, 2023 |
| Lenovo        | ThinkPad X250 20CMS0A200    | [43df4bd3f3](https://linux-hardware.org/?probe=43df4bd3f3) | Sep 18, 2023 |
| Infinix       | INBOOK X2 GEN11             | [5e87de3be1](https://linux-hardware.org/?probe=5e87de3be1) | Sep 11, 2023 |
| Toshiba       | Satellite A200              | [439b7547a5](https://linux-hardware.org/?probe=439b7547a5) | Sep 04, 2023 |
| Acer          | Aspire 3690                 | [503b015d34](https://linux-hardware.org/?probe=503b015d34) | Sep 04, 2023 |
| Infinix       | INBOOK X2 GEN11             | [b196e48c97](https://linux-hardware.org/?probe=b196e48c97) | Aug 30, 2023 |
| Infinix       | INBOOK X2 GEN11             | [d8f8a287e6](https://linux-hardware.org/?probe=d8f8a287e6) | Aug 27, 2023 |
| ASUSTek       | 1215N                       | [35853f5b92](https://linux-hardware.org/?probe=35853f5b92) | Aug 04, 2023 |
| HP            | Laptop 15-ef2xxx            | [1096cf2959](https://linux-hardware.org/?probe=1096cf2959) | Jul 31, 2023 |
| Acer          | Aspire V3-551G              | [a90eeb2fa3](https://linux-hardware.org/?probe=a90eeb2fa3) | Jul 31, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [c3523b3823](https://linux-hardware.org/?probe=c3523b3823) | Jul 29, 2023 |
| INSYS         | IP1-XN23                    | [4212432f00](https://linux-hardware.org/?probe=4212432f00) | Jul 24, 2023 |
| ASUSTek       | X55A                        | [6818ec7338](https://linux-hardware.org/?probe=6818ec7338) | Jul 21, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [a24026d3c6](https://linux-hardware.org/?probe=a24026d3c6) | Jul 14, 2023 |
| HP            | ProBook 640 G1              | [8c2fd03132](https://linux-hardware.org/?probe=8c2fd03132) | Jul 06, 2023 |
| Graviton      | N15I-T                      | [b457883ad3](https://linux-hardware.org/?probe=b457883ad3) | Jul 04, 2023 |
| Graviton      | N15I-T                      | [305390c16e](https://linux-hardware.org/?probe=305390c16e) | Jul 03, 2023 |
| 3Logic Gro... | Graviton N15i               | [1f7adfe250](https://linux-hardware.org/?probe=1f7adfe250) | Jun 27, 2023 |
| Clevo         | NL41MU2                     | [91bb626fa8](https://linux-hardware.org/?probe=91bb626fa8) | Jun 26, 2023 |
| Dell          | Vostro 3525                 | [308ee62292](https://linux-hardware.org/?probe=308ee62292) | Jun 21, 2023 |
| Alienware     | M14xR2                      | [2eb0cc2d0e](https://linux-hardware.org/?probe=2eb0cc2d0e) | Jun 17, 2023 |
| Dell          | Vostro 3525                 | [fb399aebb6](https://linux-hardware.org/?probe=fb399aebb6) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [6d434209eb](https://linux-hardware.org/?probe=6d434209eb) | Jun 07, 2023 |
| Lenovo        | G70-70 80HW                 | [0d46480e90](https://linux-hardware.org/?probe=0d46480e90) | Jun 06, 2023 |
| HP            | EliteBook 2560p             | [3ed00534ed](https://linux-hardware.org/?probe=3ed00534ed) | Jun 05, 2023 |
| HP            | Mini 210-1000               | [96f41af422](https://linux-hardware.org/?probe=96f41af422) | Jun 05, 2023 |
| Dell          | Vostro 3525                 | [e4b62aaf28](https://linux-hardware.org/?probe=e4b62aaf28) | Jun 05, 2023 |
| ICL           | RAYbook Si1407              | [5956bb96ff](https://linux-hardware.org/?probe=5956bb96ff) | May 30, 2023 |
| Timi          | TM1701                      | [94105aa58f](https://linux-hardware.org/?probe=94105aa58f) | May 26, 2023 |
| Clevo         | NL41MU2                     | [41f9a8d4b1](https://linux-hardware.org/?probe=41f9a8d4b1) | May 25, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [5762961675](https://linux-hardware.org/?probe=5762961675) | May 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [85f2338e54](https://linux-hardware.org/?probe=85f2338e54) | May 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [39fa0ce7e9](https://linux-hardware.org/?probe=39fa0ce7e9) | May 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c795e3e6ac](https://linux-hardware.org/?probe=c795e3e6ac) | May 18, 2023 |
| Clevo         | NL41MU2                     | [3c0893a822](https://linux-hardware.org/?probe=3c0893a822) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [ce24dc022b](https://linux-hardware.org/?probe=ce24dc022b) | May 10, 2023 |
| Clevo         | NL41MU2                     | [1d50da2ba5](https://linux-hardware.org/?probe=1d50da2ba5) | May 05, 2023 |
| F-PLUS EQU... | FNB-140-P1                  | [f78d6739f5](https://linux-hardware.org/?probe=f78d6739f5) | May 03, 2023 |
| Clevo         | NL41MU2                     | [67b2580836](https://linux-hardware.org/?probe=67b2580836) | May 03, 2023 |
| Acer          | Aspire 5935                 | [1ba45b2b8f](https://linux-hardware.org/?probe=1ba45b2b8f) | May 03, 2023 |
| HUAWEI        | BOM-WXX9                    | [a69dab4a99](https://linux-hardware.org/?probe=a69dab4a99) | Apr 29, 2023 |
| Valve         | Jupiter                     | [583e105bbf](https://linux-hardware.org/?probe=583e105bbf) | Apr 28, 2023 |
| Acer          | Aspire 5935                 | [9dfeeff104](https://linux-hardware.org/?probe=9dfeeff104) | Apr 28, 2023 |
| Valve         | Jupiter                     | [37534616d7](https://linux-hardware.org/?probe=37534616d7) | Apr 27, 2023 |
| Clevo         | NL41MU2                     | [4f2ffb4273](https://linux-hardware.org/?probe=4f2ffb4273) | Apr 26, 2023 |
| Acer          | Aspire 5935                 | [0430d21b33](https://linux-hardware.org/?probe=0430d21b33) | Apr 26, 2023 |
| Clevo         | NL41MU2                     | [2f1b310ca2](https://linux-hardware.org/?probe=2f1b310ca2) | Apr 21, 2023 |
| Clevo         | NL41MU2                     | [322f62ae77](https://linux-hardware.org/?probe=322f62ae77) | Apr 11, 2023 |
| Clevo         | NL41MU2                     | [720eed31f6](https://linux-hardware.org/?probe=720eed31f6) | Apr 10, 2023 |
| HP            | Pavilion dv6                | [5fddb7053d](https://linux-hardware.org/?probe=5fddb7053d) | Apr 07, 2023 |
| HP            | Pavilion dv6                | [67615ec9ff](https://linux-hardware.org/?probe=67615ec9ff) | Apr 05, 2023 |
| Timi          | TM1701                      | [5fc6e30961](https://linux-hardware.org/?probe=5fc6e30961) | Apr 04, 2023 |
| Fujitsu       | LIFEBOOK NH532              | [68a8171c0a](https://linux-hardware.org/?probe=68a8171c0a) | Mar 31, 2023 |
| ASUSTek       | K52JB                       | [45162c9123](https://linux-hardware.org/?probe=45162c9123) | Mar 30, 2023 |
| ASUSTek       | K52JB                       | [c19cd604b3](https://linux-hardware.org/?probe=c19cd604b3) | Mar 30, 2023 |
| DEPO Compu... | DPC156                      | [fc942702db](https://linux-hardware.org/?probe=fc942702db) | Mar 30, 2023 |
| DEPO Compu... | DPC156                      | [ab5d4b339b](https://linux-hardware.org/?probe=ab5d4b339b) | Mar 30, 2023 |
| Clevo         | NL41MU2                     | [69abc76758](https://linux-hardware.org/?probe=69abc76758) | Mar 29, 2023 |
| Clevo         | NL41MU2                     | [60191a33b8](https://linux-hardware.org/?probe=60191a33b8) | Mar 27, 2023 |
| Clevo         | NL41MU2                     | [b56bf816d5](https://linux-hardware.org/?probe=b56bf816d5) | Mar 23, 2023 |
| Clevo         | NL41MU2                     | [88a5d2eb30](https://linux-hardware.org/?probe=88a5d2eb30) | Mar 23, 2023 |
| Clevo         | NL41MU2                     | [430f11129e](https://linux-hardware.org/?probe=430f11129e) | Mar 22, 2023 |
| HP            | Pavilion g7                 | [9fbef1354b](https://linux-hardware.org/?probe=9fbef1354b) | Mar 21, 2023 |
| ASUSTek       | X55A                        | [743d04e5fc](https://linux-hardware.org/?probe=743d04e5fc) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [9e620a10f2](https://linux-hardware.org/?probe=9e620a10f2) | Mar 09, 2023 |
| HUAWEI        | HVY-WXX9                    | [dcc115a880](https://linux-hardware.org/?probe=dcc115a880) | Mar 02, 2023 |
| Clevo         | NL41MU2                     | [29df87f87f](https://linux-hardware.org/?probe=29df87f87f) | Feb 28, 2023 |
| Clevo         | NL41MU2                     | [b91dfc602e](https://linux-hardware.org/?probe=b91dfc602e) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [f8dd8a7ee9](https://linux-hardware.org/?probe=f8dd8a7ee9) | Feb 18, 2023 |
| Clevo         | NL41MU2                     | [d15806c6c2](https://linux-hardware.org/?probe=d15806c6c2) | Feb 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [9606f5546e](https://linux-hardware.org/?probe=9606f5546e) | Feb 15, 2023 |
| Clevo         | NL41MU2                     | [516a173dcb](https://linux-hardware.org/?probe=516a173dcb) | Feb 14, 2023 |
| Clevo         | NL41MU2                     | [2809288f6f](https://linux-hardware.org/?probe=2809288f6f) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | [56ecf82de8](https://linux-hardware.org/?probe=56ecf82de8) | Feb 13, 2023 |
| Clevo         | NL41MU2                     | [95af064bd1](https://linux-hardware.org/?probe=95af064bd1) | Feb 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c3909421c3](https://linux-hardware.org/?probe=c3909421c3) | Feb 07, 2023 |
| Lenovo        | ThinkPad X220 4290RV5       | [8fb9d5ae65](https://linux-hardware.org/?probe=8fb9d5ae65) | Feb 06, 2023 |
| Lenovo        | ThinkPad X220 4290RV5       | [ced0a536d0](https://linux-hardware.org/?probe=ced0a536d0) | Feb 06, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [9dcc7bb41d](https://linux-hardware.org/?probe=9dcc7bb41d) | Feb 03, 2023 |
| Clevo         | NL41MU2                     | [95dac05397](https://linux-hardware.org/?probe=95dac05397) | Jan 31, 2023 |
| ASUSTek       | N53Ta                       | [30131c7409](https://linux-hardware.org/?probe=30131c7409) | Jan 31, 2023 |
| Clevo         | NL41MU2                     | [86e493728f](https://linux-hardware.org/?probe=86e493728f) | Jan 27, 2023 |
| Clevo         | NL41MU2                     | [82e558cf16](https://linux-hardware.org/?probe=82e558cf16) | Jan 25, 2023 |
| Clevo         | NL41MU2                     | [831e02a268](https://linux-hardware.org/?probe=831e02a268) | Jan 24, 2023 |
| Lenovo        | B560                        | [b474faa82b](https://linux-hardware.org/?probe=b474faa82b) | Jan 23, 2023 |
| Acer          | Aspire E1-530G              | [b4f6567b3f](https://linux-hardware.org/?probe=b4f6567b3f) | Jan 22, 2023 |
| Dell          | Latitude 5580               | [9cfd456bd4](https://linux-hardware.org/?probe=9cfd456bd4) | Jan 22, 2023 |
| HP            | ProBook 440 G4              | [43b8eec1e2](https://linux-hardware.org/?probe=43b8eec1e2) | Jan 18, 2023 |
| Clevo         | NL41MU2                     | [c1c0617217](https://linux-hardware.org/?probe=c1c0617217) | Jan 17, 2023 |
| Timi          | Redmi Book Pro 14S          | [911075716c](https://linux-hardware.org/?probe=911075716c) | Jan 13, 2023 |
| Unknown       | Unknown                     | [45ea0a8983](https://linux-hardware.org/?probe=45ea0a8983) | Jan 11, 2023 |
| Intel         | Jasper Lake Client Platf... | [3000408196](https://linux-hardware.org/?probe=3000408196) | Jan 11, 2023 |
| Clevo         | NL41MU2                     | [6aaaf2e570](https://linux-hardware.org/?probe=6aaaf2e570) | Dec 28, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [4d7e3586e2](https://linux-hardware.org/?probe=4d7e3586e2) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | [0c71831ff4](https://linux-hardware.org/?probe=0c71831ff4) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | [50c31f6b47](https://linux-hardware.org/?probe=50c31f6b47) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | [190bb1537d](https://linux-hardware.org/?probe=190bb1537d) | Dec 26, 2022 |
| Clevo         | NL41MU2                     | [0574ad6c44](https://linux-hardware.org/?probe=0574ad6c44) | Dec 26, 2022 |
| LTD Delovo... | 15Y                         | [286aa3fb96](https://linux-hardware.org/?probe=286aa3fb96) | Dec 25, 2022 |
| Clevo         | NL41MU2                     | [f9b6dc975b](https://linux-hardware.org/?probe=f9b6dc975b) | Dec 23, 2022 |
| HP            | ProBook 440 G4              | [c93f96de9e](https://linux-hardware.org/?probe=c93f96de9e) | Dec 22, 2022 |
| Pegatron      | C15B                        | [865b882e8a](https://linux-hardware.org/?probe=865b882e8a) | Dec 18, 2022 |
| Aquarius      | Pro, Std, Elt Series        | [59b7fca136](https://linux-hardware.org/?probe=59b7fca136) | Dec 18, 2022 |
| Apple         | MacBook4,1                  | [26bb5af1a4](https://linux-hardware.org/?probe=26bb5af1a4) | Dec 16, 2022 |
| Irbis         | NB264                       | [14764ec4e5](https://linux-hardware.org/?probe=14764ec4e5) | Dec 15, 2022 |
| Unknown       | Unknown                     | [24bebac773](https://linux-hardware.org/?probe=24bebac773) | Dec 15, 2022 |
| Unknown       | Unknown                     | [643cb41a84](https://linux-hardware.org/?probe=643cb41a84) | Dec 15, 2022 |
| Dell          | Vostro 14 5410              | [af22c1db61](https://linux-hardware.org/?probe=af22c1db61) | Dec 08, 2022 |
| Apple         | MacBook7,1                  | [317fdfd70b](https://linux-hardware.org/?probe=317fdfd70b) | Dec 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [619fd919a1](https://linux-hardware.org/?probe=619fd919a1) | Dec 07, 2022 |
| HP            | 255 G4                      | [33b2fb7f31](https://linux-hardware.org/?probe=33b2fb7f31) | Nov 30, 2022 |
| Pegatron      | C15B                        | [92271ab582](https://linux-hardware.org/?probe=92271ab582) | Nov 30, 2022 |
| Samsung       | R560                        | [936ae4b775](https://linux-hardware.org/?probe=936ae4b775) | Nov 29, 2022 |
| Timi          | TM1701                      | [64ee057496](https://linux-hardware.org/?probe=64ee057496) | Nov 28, 2022 |
| Acer          | TravelMate 4200             | [14b60c4afa](https://linux-hardware.org/?probe=14b60c4afa) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [52da79e88f](https://linux-hardware.org/?probe=52da79e88f) | Nov 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4a758bfcc8](https://linux-hardware.org/?probe=4a758bfcc8) | Nov 25, 2022 |
| Clevo         | NL41MU2                     | [0736d8a48f](https://linux-hardware.org/?probe=0736d8a48f) | Nov 24, 2022 |
| Panasonic     | CF-C2CH2CBMG                | [cf87bdba01](https://linux-hardware.org/?probe=cf87bdba01) | Nov 24, 2022 |
| Acer          | Aspire 5940                 | [33325564e7](https://linux-hardware.org/?probe=33325564e7) | Nov 22, 2022 |
| Samsung       | SR70S/SR71S                 | [27c34cd9df](https://linux-hardware.org/?probe=27c34cd9df) | Nov 22, 2022 |
| HUAWEI        | NBD-WXX9                    | [bd18dfe05f](https://linux-hardware.org/?probe=bd18dfe05f) | Nov 20, 2022 |
| Timi          | TM1701                      | [e77b655bb8](https://linux-hardware.org/?probe=e77b655bb8) | Nov 16, 2022 |
| HUAWEI        | NBD-WXX9                    | [72ebef559b](https://linux-hardware.org/?probe=72ebef559b) | Nov 16, 2022 |
| HP            | Mini 110-3700               | [8ca62a1880](https://linux-hardware.org/?probe=8ca62a1880) | Nov 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6e9bc709d9](https://linux-hardware.org/?probe=6e9bc709d9) | Nov 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [49162725d5](https://linux-hardware.org/?probe=49162725d5) | Nov 13, 2022 |
| Clevo         | NL41MU2                     | [65226dd80a](https://linux-hardware.org/?probe=65226dd80a) | Nov 11, 2022 |
| Clevo         | NL41MU2                     | [a25dd1174c](https://linux-hardware.org/?probe=a25dd1174c) | Nov 11, 2022 |
| Acer          | TravelMate 6292             | [c7dcad2d0f](https://linux-hardware.org/?probe=c7dcad2d0f) | Nov 10, 2022 |
| Apple         | MacBookPro5,5               | [cc051268d8](https://linux-hardware.org/?probe=cc051268d8) | Nov 05, 2022 |
| ASUSTek       | T100TAM                     | [d409557d4b](https://linux-hardware.org/?probe=d409557d4b) | Nov 03, 2022 |
| ASUSTek       | T100TAM                     | [a2a70b919d](https://linux-hardware.org/?probe=a2a70b919d) | Oct 31, 2022 |
| Toshiba       | dynabook Satellite T87/8... | [10f344a2b3](https://linux-hardware.org/?probe=10f344a2b3) | Oct 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [bfb6c03047](https://linux-hardware.org/?probe=bfb6c03047) | Oct 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [5a8ac06ce5](https://linux-hardware.org/?probe=5a8ac06ce5) | Oct 19, 2022 |
| DEPO Compu... | DPC156                      | [4820b94a4a](https://linux-hardware.org/?probe=4820b94a4a) | Oct 18, 2022 |
| Samsung       | R509                        | [ce3166845f](https://linux-hardware.org/?probe=ce3166845f) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [73145a883c](https://linux-hardware.org/?probe=73145a883c) | Oct 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [fd73da4fee](https://linux-hardware.org/?probe=fd73da4fee) | Oct 11, 2022 |
| Acer          | AOA150                      | [b8780da9ef](https://linux-hardware.org/?probe=b8780da9ef) | Oct 02, 2022 |
| HUAWEI        | NBD-WXX9                    | [c1c976ba69](https://linux-hardware.org/?probe=c1c976ba69) | Sep 27, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | [b47b842550](https://linux-hardware.org/?probe=b47b842550) | Sep 25, 2022 |
| Acer          | AO722                       | [f2c6378873](https://linux-hardware.org/?probe=f2c6378873) | Sep 25, 2022 |
| ICL           | NLx0MU                      | [d8e7f39201](https://linux-hardware.org/?probe=d8e7f39201) | Sep 23, 2022 |
| Clevo         | NL41MU2                     | [226bbaa11e](https://linux-hardware.org/?probe=226bbaa11e) | Sep 23, 2022 |
| ASUSTek       | T100TAM                     | [65a37e4802](https://linux-hardware.org/?probe=65a37e4802) | Sep 19, 2022 |
| HUAWEI        | BOD-WXX9                    | [8391d18411](https://linux-hardware.org/?probe=8391d18411) | Sep 05, 2022 |
| HUAWEI        | BOD-WXX9                    | [aee6f1bdbb](https://linux-hardware.org/?probe=aee6f1bdbb) | Sep 05, 2022 |
| HUAWEI        | NBD-WXX9                    | [899d0fc360](https://linux-hardware.org/?probe=899d0fc360) | Aug 30, 2022 |
| Compumax C... | ONIX-CEL-0001               | [272ca2c7b7](https://linux-hardware.org/?probe=272ca2c7b7) | Aug 27, 2022 |
| DEPO Compu... | DPC156                      | [7c97a519fe](https://linux-hardware.org/?probe=7c97a519fe) | Aug 26, 2022 |
| Lenovo        | G460 20041                  | [ac9bf296d8](https://linux-hardware.org/?probe=ac9bf296d8) | Aug 25, 2022 |
| IP3 Tech      | TGLUP3                      | [a4f803f8a1](https://linux-hardware.org/?probe=a4f803f8a1) | Aug 24, 2022 |
| Unknown       | Unknown                     | [57d5700736](https://linux-hardware.org/?probe=57d5700736) | Aug 21, 2022 |
| 3Logic Gro... | Graviton N15i               | [cfa6cef53d](https://linux-hardware.org/?probe=cfa6cef53d) | Aug 18, 2022 |
| 3Logic Gro... | Graviton N15i               | [840fa733f4](https://linux-hardware.org/?probe=840fa733f4) | Aug 18, 2022 |
| ASUSTek       | X550ZE                      | [3a9d682c2f](https://linux-hardware.org/?probe=3a9d682c2f) | Aug 16, 2022 |
| HP            | Pavilion g7                 | [93adb73648](https://linux-hardware.org/?probe=93adb73648) | Aug 08, 2022 |
| Lenovo        | G570 20079                  | [982a6e3241](https://linux-hardware.org/?probe=982a6e3241) | Jul 30, 2022 |
| ICL           | NLx0MU                      | [af0922946a](https://linux-hardware.org/?probe=af0922946a) | Jul 25, 2022 |
| Dell          | XPS 13 9360                 | [f870753f2f](https://linux-hardware.org/?probe=f870753f2f) | Jul 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | [42a2639fcf](https://linux-hardware.org/?probe=42a2639fcf) | Jul 20, 2022 |
| HUAWEI        | KLVL-WXXW                   | [337e6e0efa](https://linux-hardware.org/?probe=337e6e0efa) | Jul 18, 2022 |
| 3Logic Gro... | Graviton N15i               | [5df194f626](https://linux-hardware.org/?probe=5df194f626) | Jul 13, 2022 |
| Dell          | Vostro 14 5410              | [2faa8bf726](https://linux-hardware.org/?probe=2faa8bf726) | Jul 12, 2022 |
| HP            | ProBook 4710s               | [4fe41da4e8](https://linux-hardware.org/?probe=4fe41da4e8) | Jul 09, 2022 |
| HP            | ProBook 4710s               | [932822fdc7](https://linux-hardware.org/?probe=932822fdc7) | Jul 09, 2022 |
| HUAWEI        | KLVL-WXXW                   | [5d2d940ec2](https://linux-hardware.org/?probe=5d2d940ec2) | Jul 07, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [a8888a6627](https://linux-hardware.org/?probe=a8888a6627) | Jul 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [b3da1e4cdb](https://linux-hardware.org/?probe=b3da1e4cdb) | Jul 05, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [3a07a4c8db](https://linux-hardware.org/?probe=3a07a4c8db) | Jun 21, 2022 |
| HP            | Pavilion dv7                | [19be007666](https://linux-hardware.org/?probe=19be007666) | Jun 04, 2022 |
| Kraftway      | ACCORD                      | [bc4e085e40](https://linux-hardware.org/?probe=bc4e085e40) | May 31, 2022 |
| Panasonic     | CF-20-1                     | [a0a97f2bd1](https://linux-hardware.org/?probe=a0a97f2bd1) | May 27, 2022 |
| IP3 Techno... | APN23                       | [4395a91f24](https://linux-hardware.org/?probe=4395a91f24) | May 25, 2022 |
| IP3 Techno... | APN23                       | [281f1263dc](https://linux-hardware.org/?probe=281f1263dc) | May 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [692cdfaf7e](https://linux-hardware.org/?probe=692cdfaf7e) | May 24, 2022 |
| ICL           | Unknown                     | [07ff87175d](https://linux-hardware.org/?probe=07ff87175d) | May 24, 2022 |
| Lenovo        | V130-15IKB 81HN             | [9fbbff1973](https://linux-hardware.org/?probe=9fbbff1973) | May 21, 2022 |
| Apple         | MacBook7,1                  | [de4e9f2e03](https://linux-hardware.org/?probe=de4e9f2e03) | May 20, 2022 |
| Sony          | SVE1512H1RB                 | [3894ca4fe2](https://linux-hardware.org/?probe=3894ca4fe2) | May 19, 2022 |
| ICL           | NJ50_70CU                   | [c16ccbe95b](https://linux-hardware.org/?probe=c16ccbe95b) | May 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f512156dc8](https://linux-hardware.org/?probe=f512156dc8) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [6767fef6cf](https://linux-hardware.org/?probe=6767fef6cf) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [28c62dd04c](https://linux-hardware.org/?probe=28c62dd04c) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [f37b79c82d](https://linux-hardware.org/?probe=f37b79c82d) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [086e18d971](https://linux-hardware.org/?probe=086e18d971) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [75dc798956](https://linux-hardware.org/?probe=75dc798956) | May 16, 2022 |
| HP            | ZBook 17 G5                 | [6881a4923e](https://linux-hardware.org/?probe=6881a4923e) | May 16, 2022 |
| Sony          | SVE1512H1RB                 | [60dba4994d](https://linux-hardware.org/?probe=60dba4994d) | May 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ce128aaf56](https://linux-hardware.org/?probe=ce128aaf56) | May 15, 2022 |
| Apple         | MacBookPro16,2              | [b1ef2f3b4f](https://linux-hardware.org/?probe=b1ef2f3b4f) | May 12, 2022 |
| Notebook      | NLx0MU                      | [eb70f159f4](https://linux-hardware.org/?probe=eb70f159f4) | May 06, 2022 |
| Lenovo        | G570 20079                  | [9bf9254f54](https://linux-hardware.org/?probe=9bf9254f54) | Apr 28, 2022 |
| HP            | ZBook 17 G5                 | [6c1227313d](https://linux-hardware.org/?probe=6c1227313d) | Apr 27, 2022 |
| HP            | ZBook 17 G5                 | [4f49f3d6c2](https://linux-hardware.org/?probe=4f49f3d6c2) | Apr 27, 2022 |
| HP            | EliteBook 840 G4            | [a1b9c91836](https://linux-hardware.org/?probe=a1b9c91836) | Apr 25, 2022 |
| HP            | 250 G7 Notebook PC          | [a58503065e](https://linux-hardware.org/?probe=a58503065e) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [c9f37aca9b](https://linux-hardware.org/?probe=c9f37aca9b) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [4505d43267](https://linux-hardware.org/?probe=4505d43267) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [bc8b33e0d2](https://linux-hardware.org/?probe=bc8b33e0d2) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | [fa53bb24d9](https://linux-hardware.org/?probe=fa53bb24d9) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | [9590ee5812](https://linux-hardware.org/?probe=9590ee5812) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [ccf6fb39e5](https://linux-hardware.org/?probe=ccf6fb39e5) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [ca58a7218c](https://linux-hardware.org/?probe=ca58a7218c) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [2da4cb3427](https://linux-hardware.org/?probe=2da4cb3427) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [77b103e672](https://linux-hardware.org/?probe=77b103e672) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [25b490f8a8](https://linux-hardware.org/?probe=25b490f8a8) | Apr 19, 2022 |
| HP            | ProBook 450 G3              | [f31bad1291](https://linux-hardware.org/?probe=f31bad1291) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | [1f7e277528](https://linux-hardware.org/?probe=1f7e277528) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | [e03dec259a](https://linux-hardware.org/?probe=e03dec259a) | Apr 19, 2022 |
| HP            | ProBook 440 G5              | [39189517e8](https://linux-hardware.org/?probe=39189517e8) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [d0a06db2b3](https://linux-hardware.org/?probe=d0a06db2b3) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [33a738be3b](https://linux-hardware.org/?probe=33a738be3b) | Apr 18, 2022 |
| HP            | 250 G6 Notebook PC          | [a5bb696691](https://linux-hardware.org/?probe=a5bb696691) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [a6631d6c9a](https://linux-hardware.org/?probe=a6631d6c9a) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [7b60ea8e45](https://linux-hardware.org/?probe=7b60ea8e45) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [d78747839a](https://linux-hardware.org/?probe=d78747839a) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [65fa83d729](https://linux-hardware.org/?probe=65fa83d729) | Apr 18, 2022 |
| ICL           | RAYbook Si1512              | [aa2de26f4f](https://linux-hardware.org/?probe=aa2de26f4f) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [41a7060cbe](https://linux-hardware.org/?probe=41a7060cbe) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | [6225568c92](https://linux-hardware.org/?probe=6225568c92) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [be57c6ecd1](https://linux-hardware.org/?probe=be57c6ecd1) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [9202f2e9ef](https://linux-hardware.org/?probe=9202f2e9ef) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [f51e697243](https://linux-hardware.org/?probe=f51e697243) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | [7e24715646](https://linux-hardware.org/?probe=7e24715646) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [a739d61b7b](https://linux-hardware.org/?probe=a739d61b7b) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [86a59150d4](https://linux-hardware.org/?probe=86a59150d4) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | [e83eeef31e](https://linux-hardware.org/?probe=e83eeef31e) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | [a0246c4b50](https://linux-hardware.org/?probe=a0246c4b50) | Apr 18, 2022 |
| Timi          | TM1701                      | [1eb7df8700](https://linux-hardware.org/?probe=1eb7df8700) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | [f9202afa63](https://linux-hardware.org/?probe=f9202afa63) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | [c5048041ee](https://linux-hardware.org/?probe=c5048041ee) | Apr 15, 2022 |
| HP            | EliteBook 840 G4            | [ee523553f4](https://linux-hardware.org/?probe=ee523553f4) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [efa4160e79](https://linux-hardware.org/?probe=efa4160e79) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [d2c072abdf](https://linux-hardware.org/?probe=d2c072abdf) | Apr 14, 2022 |
| HP            | 250 G6 Notebook PC          | [3cde2f0fd5](https://linux-hardware.org/?probe=3cde2f0fd5) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [86164212e5](https://linux-hardware.org/?probe=86164212e5) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | [37ebd7e15e](https://linux-hardware.org/?probe=37ebd7e15e) | Apr 14, 2022 |
| Dell          | Latitude 3420               | [f3278afeb0](https://linux-hardware.org/?probe=f3278afeb0) | Apr 13, 2022 |
| Dell          | Latitude 3420               | [2388ba39b8](https://linux-hardware.org/?probe=2388ba39b8) | Apr 13, 2022 |
| HP            | EliteBook 840 G4            | [87deb321d4](https://linux-hardware.org/?probe=87deb321d4) | Apr 13, 2022 |
| HP            | 250 G6 Notebook PC          | [2b8e6fdd29](https://linux-hardware.org/?probe=2b8e6fdd29) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [c2e18d9346](https://linux-hardware.org/?probe=c2e18d9346) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [0e2380e59d](https://linux-hardware.org/?probe=0e2380e59d) | Apr 13, 2022 |
| Dell          | Latitude 3420               | [ecdf7b8de0](https://linux-hardware.org/?probe=ecdf7b8de0) | Apr 12, 2022 |
| Dell          | Latitude 3420               | [4361233072](https://linux-hardware.org/?probe=4361233072) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [19f3a71bf4](https://linux-hardware.org/?probe=19f3a71bf4) | Apr 12, 2022 |
| HP            | 250 G7 Notebook PC          | [0860ee5a64](https://linux-hardware.org/?probe=0860ee5a64) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [4f1aa9470b](https://linux-hardware.org/?probe=4f1aa9470b) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [7537241f1d](https://linux-hardware.org/?probe=7537241f1d) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [d6792fe869](https://linux-hardware.org/?probe=d6792fe869) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | [e3236de077](https://linux-hardware.org/?probe=e3236de077) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [2d62dd7b61](https://linux-hardware.org/?probe=2d62dd7b61) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [0eae0dfd04](https://linux-hardware.org/?probe=0eae0dfd04) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | [65b8e561ab](https://linux-hardware.org/?probe=65b8e561ab) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | [b95e628a8f](https://linux-hardware.org/?probe=b95e628a8f) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [d05023771a](https://linux-hardware.org/?probe=d05023771a) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [655584ea45](https://linux-hardware.org/?probe=655584ea45) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [a6527519c6](https://linux-hardware.org/?probe=a6527519c6) | Apr 12, 2022 |
| Acer          | TravelMate 5760             | [b6f41e002d](https://linux-hardware.org/?probe=b6f41e002d) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | [f8931a9e1e](https://linux-hardware.org/?probe=f8931a9e1e) | Apr 12, 2022 |
| Acer          | Aspire A514-52K             | [085e03c893](https://linux-hardware.org/?probe=085e03c893) | Apr 11, 2022 |
| Acer          | Aspire A514-52K             | [0157eea2f6](https://linux-hardware.org/?probe=0157eea2f6) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | [7289268e39](https://linux-hardware.org/?probe=7289268e39) | Apr 11, 2022 |
| Dell          | Latitude 3420               | [d436f78355](https://linux-hardware.org/?probe=d436f78355) | Apr 11, 2022 |
| Acer          | TravelMate 5760             | [958de67015](https://linux-hardware.org/?probe=958de67015) | Apr 11, 2022 |
| Lenovo        | B590 20206                  | [e027a7672d](https://linux-hardware.org/?probe=e027a7672d) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | [5f90eb0f80](https://linux-hardware.org/?probe=5f90eb0f80) | Apr 11, 2022 |
| Dell          | Latitude 3420               | [5dbdb89f95](https://linux-hardware.org/?probe=5dbdb89f95) | Apr 11, 2022 |
| Acer          | Aspire 5745G                | [4a6e981204](https://linux-hardware.org/?probe=4a6e981204) | Apr 04, 2022 |
| Lenovo        | V510-15IKB 80WQ             | [dfdb44695a](https://linux-hardware.org/?probe=dfdb44695a) | Apr 01, 2022 |
| HP            | Unknown                     | [e989736b06](https://linux-hardware.org/?probe=e989736b06) | Mar 30, 2022 |
| HP            | Unknown                     | [672d3c8b62](https://linux-hardware.org/?probe=672d3c8b62) | Mar 29, 2022 |
| HP            | 250 G3                      | [22f691edac](https://linux-hardware.org/?probe=22f691edac) | Mar 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e4b8a2cc11](https://linux-hardware.org/?probe=e4b8a2cc11) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [64baae5b88](https://linux-hardware.org/?probe=64baae5b88) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | [247859eb78](https://linux-hardware.org/?probe=247859eb78) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | [b9e82b8490](https://linux-hardware.org/?probe=b9e82b8490) | Mar 22, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [58fdf49095](https://linux-hardware.org/?probe=58fdf49095) | Mar 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [eaa9fb6aad](https://linux-hardware.org/?probe=eaa9fb6aad) | Mar 14, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [72eefd2811](https://linux-hardware.org/?probe=72eefd2811) | Mar 14, 2022 |
| Dell          | G5 5590                     | [9b95f2ae1d](https://linux-hardware.org/?probe=9b95f2ae1d) | Mar 06, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [13bc7e73f1](https://linux-hardware.org/?probe=13bc7e73f1) | Mar 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ef592cb1a7](https://linux-hardware.org/?probe=ef592cb1a7) | Feb 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c907453bf5](https://linux-hardware.org/?probe=c907453bf5) | Feb 18, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3986a62bca](https://linux-hardware.org/?probe=3986a62bca) | Feb 15, 2022 |
| ASUSTek       | X200MA                      | [b2f1d59884](https://linux-hardware.org/?probe=b2f1d59884) | Feb 12, 2022 |
| Timi          | TM1701                      | [4edeb14964](https://linux-hardware.org/?probe=4edeb14964) | Feb 05, 2022 |
| DEPO Compu... | DPC156                      | [4fb49336e5](https://linux-hardware.org/?probe=4fb49336e5) | Feb 03, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a08b9de6fa](https://linux-hardware.org/?probe=a08b9de6fa) | Jan 28, 2022 |
| Dell          | Latitude 3590               | [e2a6ef3266](https://linux-hardware.org/?probe=e2a6ef3266) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [00f8c9d649](https://linux-hardware.org/?probe=00f8c9d649) | Jan 02, 2022 |
| Samsung       | 750XDA                      | [8fe8612ccb](https://linux-hardware.org/?probe=8fe8612ccb) | Dec 21, 2021 |
| Acer          | Aspire 5750G                | [58cdbcf87e](https://linux-hardware.org/?probe=58cdbcf87e) | Dec 18, 2021 |
| ASUSTek       | N46VZ                       | [aaf9eff6bd](https://linux-hardware.org/?probe=aaf9eff6bd) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [2839eb3d12](https://linux-hardware.org/?probe=2839eb3d12) | Oct 09, 2021 |
| HP            | Laptop 15s-fq0xxx           | [516882d907](https://linux-hardware.org/?probe=516882d907) | Sep 23, 2021 |
| Timi          | TM1701                      | [b13b26d7ca](https://linux-hardware.org/?probe=b13b26d7ca) | Sep 16, 2021 |
| ASUSTek       | N46VZ                       | [40c97b439e](https://linux-hardware.org/?probe=40c97b439e) | Sep 12, 2021 |
| Acer          | Aspire A317-32              | [09342414f3](https://linux-hardware.org/?probe=09342414f3) | Sep 09, 2021 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [6648ff785e](https://linux-hardware.org/?probe=6648ff785e) | Sep 08, 2021 |
| ASUSTek       | N46VZ                       | [eb37b7db1e](https://linux-hardware.org/?probe=eb37b7db1e) | Aug 11, 2021 |
| Acer          | Swift SF314-57              | [2872bd6b13](https://linux-hardware.org/?probe=2872bd6b13) | Aug 05, 2021 |
| Durabook      | Z14                         | [7abdb375e2](https://linux-hardware.org/?probe=7abdb375e2) | Jul 27, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [a85464aae6](https://linux-hardware.org/?probe=a85464aae6) | Jul 06, 2021 |
| Aquarius      | NS585                       | [bc10f2ffbd](https://linux-hardware.org/?probe=bc10f2ffbd) | Jun 27, 2021 |
| Dell          | G3 3779                     | [eaf53820e5](https://linux-hardware.org/?probe=eaf53820e5) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [9f3a13c865](https://linux-hardware.org/?probe=9f3a13c865) | May 27, 2021 |
| HP            | Laptop 17-by0xxx            | [a3f263e12b](https://linux-hardware.org/?probe=a3f263e12b) | May 26, 2021 |
| Dell          | Inspiron 3542               | [e1a816cc42](https://linux-hardware.org/?probe=e1a816cc42) | May 25, 2021 |
| MSI           | GE72 7RE                    | [a6a5258971](https://linux-hardware.org/?probe=a6a5258971) | May 20, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [59740e6ccf](https://linux-hardware.org/?probe=59740e6ccf) | Apr 29, 2021 |
| HP            | EliteBook 8470p             | [632deaf397](https://linux-hardware.org/?probe=632deaf397) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8185306af7](https://linux-hardware.org/?probe=8185306af7) | Apr 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ea2ab7cbc7](https://linux-hardware.org/?probe=ea2ab7cbc7) | Apr 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3afcb7ca65](https://linux-hardware.org/?probe=3afcb7ca65) | Mar 29, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [66f3887fa2](https://linux-hardware.org/?probe=66f3887fa2) | Mar 20, 2021 |
| HP            | Pavilion Laptop 15-cc5xx    | [2c576fb8a9](https://linux-hardware.org/?probe=2c576fb8a9) | Mar 17, 2021 |
| HP            | Laptop 15s-fq2xxx           | [2d8bd02af5](https://linux-hardware.org/?probe=2d8bd02af5) | Feb 09, 2021 |
| Lenovo        | B50-10 80QR                 | [211bf1a4b4](https://linux-hardware.org/?probe=211bf1a4b4) | Jan 15, 2021 |
| Acer          | NC-ES1-131-C1NL             | [1cae46f14f](https://linux-hardware.org/?probe=1cae46f14f) | Jan 09, 2021 |
| HP            | Laptop 15s-fq0xxx           | [2437a45956](https://linux-hardware.org/?probe=2437a45956) | Jan 07, 2021 |
| HP            | EliteBook 8470p             | [ed90389918](https://linux-hardware.org/?probe=ed90389918) | Dec 22, 2020 |
| Lenovo        | ThinkPad X220 4291M85       | [f2c165b2d8](https://linux-hardware.org/?probe=f2c165b2d8) | Dec 22, 2020 |
| ASUSTek       | X510UNR                     | [53ef89172e](https://linux-hardware.org/?probe=53ef89172e) | Dec 21, 2020 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [00824d4fae](https://linux-hardware.org/?probe=00824d4fae) | Nov 19, 2020 |
| HP            | Laptop 14s-dq1xxx           | [f6e0ab4b2b](https://linux-hardware.org/?probe=f6e0ab4b2b) | Nov 13, 2020 |
| Toshiba       | Satellite A100              | [f09cd03fff](https://linux-hardware.org/?probe=f09cd03fff) | Nov 09, 2020 |
| MSI           | X300/X340/X400 series       | [1fd45a8e47](https://linux-hardware.org/?probe=1fd45a8e47) | Oct 23, 2020 |
| Lenovo        | B50-10 80QR                 | [ae14993850](https://linux-hardware.org/?probe=ae14993850) | Sep 28, 2020 |
| ASUSTek       | N46VZ                       | [d1ba7fa191](https://linux-hardware.org/?probe=d1ba7fa191) | Sep 23, 2020 |
| ASUSTek       | N46VZ                       | [ee23f7cefc](https://linux-hardware.org/?probe=ee23f7cefc) | Sep 14, 2020 |
| ASUSTek       | N46VZ                       | [52930a9597](https://linux-hardware.org/?probe=52930a9597) | Sep 03, 2020 |
| ASUSTek       | N46VZ                       | [9998e51d1c](https://linux-hardware.org/?probe=9998e51d1c) | Aug 14, 2020 |
| Samsung       | R510/P510                   | [e20ff4ae24](https://linux-hardware.org/?probe=e20ff4ae24) | Jul 12, 2020 |
| Lenovo        | B50-10 80QR                 | [a50e0f999e](https://linux-hardware.org/?probe=a50e0f999e) | Jul 07, 2020 |
| HP            | 255 G2                      | [3d4e8b4672](https://linux-hardware.org/?probe=3d4e8b4672) | May 27, 2020 |
| Acer          | Aspire E1-571G              | [3290540c34](https://linux-hardware.org/?probe=3290540c34) | Mar 13, 2020 |
| Lenovo        | 3000 G430 4153/200          | [0315e41f8c](https://linux-hardware.org/?probe=0315e41f8c) | Dec 26, 2019 |
| HP            | Pavilion dv6700             | [1031d661db](https://linux-hardware.org/?probe=1031d661db) | Nov 24, 2019 |
| HP            | Pavilion dv6700             | [c2fc59b6de](https://linux-hardware.org/?probe=c2fc59b6de) | Nov 23, 2019 |
| ASUSTek       | N46VZ                       | [bee323a814](https://linux-hardware.org/?probe=bee323a814) | Oct 29, 2019 |
| eMachines     | eME728                      | [83010f511e](https://linux-hardware.org/?probe=83010f511e) | Oct 25, 2019 |
| ASUSTek       | X200MA                      | [595d1ddd1b](https://linux-hardware.org/?probe=595d1ddd1b) | Oct 25, 2019 |
| MSI           | MEGA BOOK S430              | [6380916978](https://linux-hardware.org/?probe=6380916978) | Sep 15, 2019 |
| Lenovo        | G505s 20255                 | [46308d3b71](https://linux-hardware.org/?probe=46308d3b71) | Aug 30, 2019 |
| Lenovo        | G505s 20255                 | [c840002848](https://linux-hardware.org/?probe=c840002848) | Aug 30, 2019 |
| ASUSTek       | 1101HA                      | [f221bcd7e4](https://linux-hardware.org/?probe=f221bcd7e4) | Aug 16, 2019 |
| ASUSTek       | N46VZ                       | [aec6cff1b5](https://linux-hardware.org/?probe=aec6cff1b5) | Aug 15, 2019 |
| Samsung       | RV413/RV513/E3413           | [3e37ab573a](https://linux-hardware.org/?probe=3e37ab573a) | Apr 24, 2019 |
| Samsung       | RV413/RV513/E3413           | [447cdad389](https://linux-hardware.org/?probe=447cdad389) | Apr 23, 2019 |
| Acer          | Aspire ES1-523              | [0f6abd34f2](https://linux-hardware.org/?probe=0f6abd34f2) | Dec 17, 2018 |
| ASUSTek       | 1001PXD                     | [1a4aa87d78](https://linux-hardware.org/?probe=1a4aa87d78) | Oct 29, 2018 |
| Acer          | Aspire ES1-523              | [5e9a049dce](https://linux-hardware.org/?probe=5e9a049dce) | Oct 08, 2018 |
| ASUSTek       | K52JT                       | [7fdee4e7bb](https://linux-hardware.org/?probe=7fdee4e7bb) | Jun 18, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ALT_Linux/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| ALT Linux 11.0     | 86        | 15.19%  |
| ALT Linux 10.1     | 68        | 12.01%  |
| Kometa P10         | 54        | 9.54%   |
| ALT Linux 10.2     | 49        | 8.66%   |
| MOS 10             | 41        | 7.24%   |
| ALT Linux 10.4     | 34        | 6.01%   |
| ALT Linux 20240122 | 33        | 5.83%   |
| ALT Linux 10.0     | 33        | 5.83%   |
| ALT Linux 11.1     | 29        | 5.12%   |
| ALT Linux 10.3     | 27        | 4.77%   |
| ALT Linux 9.1      | 22        | 3.89%   |
| ALT Linux 9.2      | 10        | 1.77%   |
| ALT Linux 9.0      | 9         | 1.59%   |
| ALT Linux P10      | 6         | 1.06%   |
| ALT Linux 11       | 6         | 1.06%   |
| ALT Linux 10       | 5         | 0.88%   |
| ALT Linux 0.9.3    | 5         | 0.88%   |
| ALT Linux 0.9.2    | 5         | 0.88%   |
| ALT Linux 20250612 | 4         | 0.71%   |
| ALT Linux 10.1.900 | 4         | 0.71%   |
| ALT Linux 20201124 | 3         | 0.53%   |
| ALT Linux 10.0.900 | 3         | 0.53%   |
| ALT Linux P9       | 2         | 0.35%   |
| ALT Linux P8       | 2         | 0.35%   |
| ALT Linux 8.2      | 2         | 0.35%   |
| ALT Linux 20220110 | 2         | 0.35%   |
| ALT Linux 20191026 | 2         | 0.35%   |
| ALT Linux 11.0.900 | 2         | 0.35%   |
| ALT Linux 0.9.1    | 2         | 0.35%   |
| ALT Linux 9        | 1         | 0.18%   |
| ALT Linux 8.990    | 1         | 0.18%   |
| ALT Linux 8.920    | 1         | 0.18%   |
| ALT Linux 8.3      | 1         | 0.18%   |
| ALT Linux 8.0.0    | 1         | 0.18%   |
| ALT Linux 20240112 | 1         | 0.18%   |
| ALT Linux 20230819 | 1         | 0.18%   |
| ALT Linux 20190624 | 1         | 0.18%   |
| ALT Linux 11.2     | 1         | 0.18%   |
| ALT Linux 10.920   | 1         | 0.18%   |
| ALT Linux 10.900   | 1         | 0.18%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| ALT Linux | 527       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 6.12.34-6.12-alt1     | 49        | 8.11%   |
| 5.10.102-std-def-alt1 | 38        | 6.29%   |
| 5.10.109-std-def-alt1 | 19        | 3.15%   |
| 5.10.139-std-def-alt1 | 16        | 2.65%   |
| 6.1.115-un-def-alt1   | 13        | 2.15%   |
| 5.10.198-std-def-alt1 | 13        | 2.15%   |
| 5.10.164-std-def-alt1 | 13        | 2.15%   |
| 6.12.21-6.12-alt1     | 11        | 1.82%   |
| 6.1.81-un-def-alt1    | 11        | 1.82%   |
| 5.10.156-std-def-alt1 | 11        | 1.82%   |
| 5.15.72-un-def-alt1   | 9         | 1.49%   |
| 5.10.88-std-def-alt1  | 9         | 1.49%   |
| 6.12.51-6.12-alt1     | 8         | 1.32%   |
| 5.15.80-un-def-alt1   | 8         | 1.32%   |
| 5.15.34-un-def-alt1   | 8         | 1.32%   |
| 6.12.45-6.12-alt1     | 7         | 1.16%   |
| 6.12.41-6.12-alt1     | 7         | 1.16%   |
| 5.10.152-std-def-alt1 | 7         | 1.16%   |
| 5.10.123-std-def-alt1 | 7         | 1.16%   |
| 6.1.57-un-def-alt1    | 6         | 0.99%   |
| 6.1.55-un-def-alt1    | 6         | 0.99%   |
| 6.1.49-un-def-alt1    | 6         | 0.99%   |
| 6.12.59-6.12-alt1     | 5         | 0.83%   |
| 6.1.54-un-def-alt1    | 5         | 0.83%   |
| 6.1.111-un-def-alt1   | 5         | 0.83%   |
| 5.15.76-un-def-alt1   | 5         | 0.83%   |
| 5.10.82-std-def-alt1  | 5         | 0.83%   |
| 6.14.0-6.14-alt1      | 4         | 0.66%   |
| 6.12.61-6.12-alt1     | 4         | 0.66%   |
| 6.12.24-6.12-alt1     | 4         | 0.66%   |
| 6.1.79-un-def-alt1    | 4         | 0.66%   |
| 6.6.47-un-def-alt1    | 3         | 0.5%    |
| 6.12.55-6.12-alt1     | 3         | 0.5%    |
| 6.12.42-6.12-alt1     | 3         | 0.5%    |
| 6.12.29-6.12-alt1     | 3         | 0.5%    |
| 6.12.17-6.12-alt1     | 3         | 0.5%    |
| 6.12.12-6.12-alt1     | 3         | 0.5%    |
| 6.12.11-6.12-alt1     | 3         | 0.5%    |
| 6.1.77-un-def-alt1    | 3         | 0.5%    |
| 6.1.38-un-def-alt1    | 3         | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 6.12.34  | 49        | 8.11%   |
| 5.10.102 | 38        | 6.29%   |
| 5.10.109 | 19        | 3.15%   |
| 5.10.139 | 16        | 2.65%   |
| 6.1.115  | 13        | 2.15%   |
| 5.10.198 | 13        | 2.15%   |
| 5.10.164 | 13        | 2.15%   |
| 6.12.21  | 11        | 1.82%   |
| 6.1.81   | 11        | 1.82%   |
| 5.10.156 | 11        | 1.82%   |
| 5.15.80  | 9         | 1.49%   |
| 5.15.72  | 9         | 1.49%   |
| 5.10.88  | 9         | 1.49%   |
| 6.12.51  | 8         | 1.32%   |
| 5.15.34  | 8         | 1.32%   |
| 6.12.45  | 7         | 1.16%   |
| 6.12.41  | 7         | 1.16%   |
| 6.1.55   | 7         | 1.16%   |
| 5.10.152 | 7         | 1.16%   |
| 5.10.123 | 7         | 1.16%   |
| 6.1.57   | 6         | 0.99%   |
| 6.1.49   | 6         | 0.99%   |
| 6.12.59  | 5         | 0.83%   |
| 6.1.54   | 5         | 0.83%   |
| 6.1.111  | 5         | 0.83%   |
| 5.15.76  | 5         | 0.83%   |
| 5.10.82  | 5         | 0.83%   |
| 6.14.0   | 4         | 0.66%   |
| 6.12.61  | 4         | 0.66%   |
| 6.12.24  | 4         | 0.66%   |
| 6.11.0   | 4         | 0.66%   |
| 6.1.79   | 4         | 0.66%   |
| 6.6.52   | 3         | 0.5%    |
| 6.6.47   | 3         | 0.5%    |
| 6.12.55  | 3         | 0.5%    |
| 6.12.42  | 3         | 0.5%    |
| 6.12.29  | 3         | 0.5%    |
| 6.12.17  | 3         | 0.5%    |
| 6.12.12  | 3         | 0.5%    |
| 6.12.11  | 3         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 186       | 32.98%  |
| 6.12    | 125       | 22.16%  |
| 6.1     | 100       | 17.73%  |
| 5.15    | 55        | 9.75%   |
| 6.6     | 36        | 6.38%   |
| 5.4     | 20        | 3.55%   |
| 4.19    | 11        | 1.95%   |
| 6.14    | 4         | 0.71%   |
| 6.11    | 4         | 0.71%   |
| 6.2     | 3         | 0.53%   |
| 4.9     | 3         | 0.53%   |
| 6.9     | 2         | 0.35%   |
| 6.5     | 2         | 0.35%   |
| 5.18    | 2         | 0.35%   |
| 5.13    | 2         | 0.35%   |
| 6.18    | 1         | 0.18%   |
| 6.17    | 1         | 0.18%   |
| 6.16    | 1         | 0.18%   |
| 6.15    | 1         | 0.18%   |
| 6.13    | 1         | 0.18%   |
| 5.7     | 1         | 0.18%   |
| 5.3     | 1         | 0.18%   |
| 5.16    | 1         | 0.18%   |
| 4.4     | 1         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 513       | 97.34%  |
| i686   | 14        | 2.66%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE5            | 233       | 42.91%  |
| XFCE            | 107       | 19.71%  |
| Unknown         | 88        | 16.21%  |
| GNOME           | 61        | 11.23%  |
| MATE            | 20        | 3.68%   |
| LXQt            | 9         | 1.66%   |
| KDE:KDE-Wayland | 9         | 1.66%   |
| Cinnamon        | 5         | 0.92%   |
| KDE6            | 4         | 0.74%   |
| X-Cinnamon      | 2         | 0.37%   |
| GNOME Flashback | 2         | 0.37%   |
| LXDE            | 1         | 0.18%   |
| KDE:KDE-X11     | 1         | 0.18%   |
| KDE             | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 425       | 79%     |
| Wayland | 65        | 12.08%  |
| Unknown | 43        | 7.99%   |
| Tty     | 5         | 0.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 237       | 43.89%  |
| SDDM    | 144       | 26.67%  |
| Unknown | 105       | 19.44%  |
| GDM     | 30        | 5.56%   |
| TDM     | 22        | 4.07%   |
| XDM     | 2         | 0.37%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| ru_RU       | 482       | 90.09%  |
| Unknown     | 27        | 5.05%   |
| en_US       | 21        | 3.93%   |
| POSIX       | 2         | 0.37%   |
| ru_RU.utf-8 | 1         | 0.19%   |
| it_IT@euro  | 1         | 0.19%   |
| C           | 1         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 353       | 66.48%  |
| BIOS | 178       | 33.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 403       | 75.33%  |
| Btrfs   | 98        | 18.32%  |
| Overlay | 28        | 5.23%   |
| Tmpfs   | 3         | 0.56%   |
| Unknown | 2         | 0.37%   |
| Xfs     | 1         | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 326       | 61.05%  |
| Unknown | 106       | 19.85%  |
| MBR     | 102       | 19.1%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 496       | 92.54%  |
| Yes       | 40        | 7.46%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 392       | 73.55%  |
| Yes       | 141       | 26.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                              | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Hewlett-Packard                   | 93        | 17.65%  |
| Lenovo                            | 71        | 13.47%  |
| ASUSTek Computer                  | 59        | 11.2%   |
| Acer                              | 42        | 7.97%   |
| Clevo                             | 32        | 6.07%   |
| Dell                              | 23        | 4.36%   |
| ICL                               | 19        | 3.61%   |
| HUAWEI                            | 16        | 3.04%   |
| Aquarius                          | 15        | 2.85%   |
| MSI                               | 14        | 2.66%   |
| Unknown                           | 13        | 2.47%   |
| Samsung Electronics               | 10        | 1.9%    |
| Apple                             | 9         | 1.71%   |
| DEPO Computers                    | 8         | 1.52%   |
| ICL Techno                        | 7         | 1.33%   |
| HONOR                             | 7         | 1.33%   |
| 3Logic Group                      | 7         | 1.33%   |
| Toshiba                           | 6         | 1.14%   |
| Sony                              | 6         | 1.14%   |
| TECNO Mobile Limited              | 4         | 0.76%   |
| Maibenben                         | 4         | 0.76%   |
| Kraftway                          | 4         | 0.76%   |
| Timi                              | 3         | 0.57%   |
| iRU                               | 3         | 0.57%   |
| Infinix                           | 3         | 0.57%   |
| Graviton                          | 3         | 0.57%   |
| F-PLUS EQUIPMENT AND DEVELOPMENTS | 3         | 0.57%   |
| XIAOMI                            | 2         | 0.38%   |
| Panasonic                         | 2         | 0.38%   |
| MACHENIKE                         | 2         | 0.38%   |
| Machcreator                       | 2         | 0.38%   |
| LTD Delovoy Office                | 2         | 0.38%   |
| IP3 Tech                          | 2         | 0.38%   |
| Intel                             | 2         | 0.38%   |
| HIPER                             | 2         | 0.38%   |
| DIGMA Pro                         | 2         | 0.38%   |
| Digma                             | 2         | 0.38%   |
| Valve                             | 1         | 0.19%   |
| ROMBICA                           | 1         | 0.19%   |
| Razer                             | 1         | 0.19%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Clevo NL41MU2                                                                            | 32        | 6.07%   |
| Unknown                                                                                  | 19        | 3.61%   |
| HP 250 G7 Notebook PC                                                                    | 12        | 2.28%   |
| ICL RAYbook Si1512                                                                       | 9         | 1.71%   |
| HP ZBook 17 G5                                                                           | 9         | 1.71%   |
| HP ProBook 440 G5                                                                        | 9         | 1.71%   |
| Aquarius NS685U R11                                                                      | 8         | 1.52%   |
| DEPO Computers DPC156                                                                    | 7         | 1.33%   |
| Lenovo ThinkBook 15 G2 ITL 20VE                                                          | 4         | 0.76%   |
| Kraftway ACCORD                                                                          | 4         | 0.76%   |
| 3Logic Group Graviton N15i                                                               | 4         | 0.76%   |
| Maibenben Perfectum Series                                                               | 3         | 0.57%   |
| Lenovo ThinkPad E15 Gen 4 21ED004YRT                                                     | 3         | 0.57%   |
| Lenovo B50-30 20382                                                                      | 3         | 0.57%   |
| ICL Techno F140a                                                                         | 3         | 0.57%   |
| HUAWEI RLEF-XX                                                                           | 3         | 0.57%   |
| HUAWEI NBD-WXX9                                                                          | 3         | 0.57%   |
| HP Pavilion dv6                                                                          | 3         | 0.57%   |
| HP Laptop 15-bw0xx                                                                       | 3         | 0.57%   |
| HP EliteBook 8470p                                                                       | 3         | 0.57%   |
| HP EliteBook 840 G4                                                                      | 3         | 0.57%   |
| HP 250 G6 Notebook PC                                                                    | 3         | 0.57%   |
| Dell Latitude 3420                                                                       | 3         | 0.57%   |
| ASUS VivoBook_ASUSLaptop M1503QA_M1503QA                                                 | 3         | 0.57%   |
| 3Logic Group Graviton N15i-K2                                                            | 3         | 0.57%   |
| XIAOMI Redmi Book Pro 14 2024                                                            | 2         | 0.38%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 2         | 0.38%   |
| Machcreator Prime X16                                                                    | 2         | 0.38%   |
| Lenovo V15 G4 AMN 82YU                                                                   | 2         | 0.38%   |
| Lenovo ThinkPad L13 Gen 2 20VH001WRT                                                     | 2         | 0.38%   |
| Lenovo IdeaPad S340-14API 81NB                                                           | 2         | 0.38%   |
| Lenovo G570 20079                                                                        | 2         | 0.38%   |
| Lenovo B590 20206                                                                        | 2         | 0.38%   |
| ICL Techno F150a                                                                         | 2         | 0.38%   |
| ICL S1523 G1R                                                                            | 2         | 0.38%   |
| ICL NJ50_70CU                                                                            | 2         | 0.38%   |
| HUAWEI KLVL-WXXW                                                                         | 2         | 0.38%   |
| HUAWEI BOM-WXX9                                                                          | 2         | 0.38%   |
| HP ProBook 440 G4                                                                        | 2         | 0.38%   |
| HP Pavilion Laptop 15-eh1xxx                                                             | 2         | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Clevo NL41MU2                 | 32        | 6.07%   |
| Acer Aspire                   | 24        | 4.55%   |
| HP ProBook                    | 19        | 3.61%   |
| Unknown                       | 19        | 3.61%   |
| Lenovo ThinkPad               | 18        | 3.42%   |
| Lenovo IdeaPad                | 17        | 3.23%   |
| HP 250                        | 17        | 3.23%   |
| ASUS VivoBook                 | 17        | 3.23%   |
| HP Pavilion                   | 15        | 2.85%   |
| HP Laptop                     | 13        | 2.47%   |
| ICL RAYbook                   | 12        | 2.28%   |
| ASUS ASUS                     | 11        | 2.09%   |
| Dell Inspiron                 | 10        | 1.9%    |
| HP ZBook                      | 9         | 1.71%   |
| HP EliteBook                  | 9         | 1.71%   |
| Aquarius NS685U               | 8         | 1.52%   |
| DEPO Computers DPC156         | 7         | 1.33%   |
| 3Logic Group Graviton         | 7         | 1.33%   |
| Dell Latitude                 | 6         | 1.14%   |
| Acer TravelMate               | 6         | 1.14%   |
| MSI Modern                    | 5         | 0.95%   |
| Lenovo V15                    | 5         | 0.95%   |
| Lenovo ThinkBook              | 5         | 0.95%   |
| Toshiba Satellite             | 4         | 0.76%   |
| TECNO Mobile Limited MEGABOOK | 4         | 0.76%   |
| Kraftway ACCORD               | 4         | 0.76%   |
| Maibenben Perfectum           | 3         | 0.57%   |
| Lenovo B50-30                 | 3         | 0.57%   |
| Infinix INBOOK                | 3         | 0.57%   |
| ICL Techno F140a              | 3         | 0.57%   |
| ICL S1523                     | 3         | 0.57%   |
| HUAWEI RLEF-XX                | 3         | 0.57%   |
| HUAWEI NBD-WXX9               | 3         | 0.57%   |
| HP 255                        | 3         | 0.57%   |
| Dell Vostro                   | 3         | 0.57%   |
| Aquarius CMP                  | 3         | 0.57%   |
| Apple MacBookPro16            | 3         | 0.57%   |
| Acer Swift                    | 3         | 0.57%   |
| Acer Extensa                  | 3         | 0.57%   |
| XIAOMI Redmi                  | 2         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 95        | 18.03%  |
| 2021 | 61        | 11.57%  |
| 2023 | 37        | 7.02%   |
| 2020 | 37        | 7.02%   |
| 2018 | 34        | 6.45%   |
| 2019 | 32        | 6.07%   |
| 2024 | 30        | 5.69%   |
| 2017 | 30        | 5.69%   |
| 2011 | 27        | 5.12%   |
| 2012 | 26        | 4.93%   |
| 2014 | 21        | 3.98%   |
| 2010 | 19        | 3.61%   |
| 2013 | 17        | 3.23%   |
| 2008 | 13        | 2.47%   |
| 2016 | 12        | 2.28%   |
| 2009 | 10        | 1.9%    |
| 2015 | 8         | 1.52%   |
| 2007 | 8         | 1.52%   |
| 2025 | 5         | 0.95%   |
| 2006 | 3         | 0.57%   |
| 2005 | 1         | 0.19%   |
| 2004 | 1         | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 527       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 444       | 83.15%  |
| Enabled  | 90        | 16.85%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 526       | 99.81%  |
| Yes  | 1         | 0.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 221       | 41.39%  |
| 16.01-24.0  | 109       | 20.41%  |
| 8.01-16.0   | 83        | 15.54%  |
| 3.01-4.0    | 62        | 11.61%  |
| 1.01-2.0    | 25        | 4.68%   |
| 32.01-64.0  | 19        | 3.56%   |
| 2.01-3.0    | 6         | 1.12%   |
| 24.01-32.0  | 4         | 0.75%   |
| 0.51-1.0    | 3         | 0.56%   |
| 64.01-256.0 | 2         | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 235       | 41.37%  |
| 2.01-3.0  | 130       | 22.89%  |
| 4.01-8.0  | 64        | 11.27%  |
| 3.01-4.0  | 63        | 11.09%  |
| 0.51-1.0  | 51        | 8.98%   |
| 8.01-16.0 | 18        | 3.17%   |
| 0.01-0.5  | 7         | 1.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 430       | 80.07%  |
| 2      | 92        | 17.13%  |
| 3      | 10        | 1.86%   |
| 0      | 3         | 0.56%   |
| 4      | 2         | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 402       | 75.71%  |
| Yes       | 129       | 24.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 423       | 80.27%  |
| No        | 104       | 19.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 508       | 96.21%  |
| No        | 20        | 3.79%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 454       | 85.66%  |
| No        | 76        | 14.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Russia      | 489       | 92.61%  |
| Greece      | 6         | 1.14%   |
| Belarus     | 6         | 1.14%   |
| Ukraine     | 4         | 0.76%   |
| Switzerland | 2         | 0.38%   |
| Spain       | 2         | 0.38%   |
| Estonia     | 2         | 0.38%   |
| Egypt       | 2         | 0.38%   |
| Uzbekistan  | 1         | 0.19%   |
| USA         | 1         | 0.19%   |
| UK          | 1         | 0.19%   |
| Thailand    | 1         | 0.19%   |
| Netherlands | 1         | 0.19%   |
| Moldova     | 1         | 0.19%   |
| Kazakhstan  | 1         | 0.19%   |
| Italy       | 1         | 0.19%   |
| Germany     | 1         | 0.19%   |
| France      | 1         | 0.19%   |
| Czechia     | 1         | 0.19%   |
| Costa Rica  | 1         | 0.19%   |
| Colombia    | 1         | 0.19%   |
| Bulgaria    | 1         | 0.19%   |
| Australia   | 1         | 0.19%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 222       | 41.04%  |
| St Petersburg    | 36        | 6.65%   |
| Novosibirsk      | 16        | 2.96%   |
| Kazan’         | 11        | 2.03%   |
| Krasnoyarsk      | 8         | 1.48%   |
| Barnaul          | 7         | 1.29%   |
| Yekaterinburg    | 6         | 1.11%   |
| Voronezh         | 6         | 1.11%   |
| Tver             | 6         | 1.11%   |
| Samara           | 6         | 1.11%   |
| Perm             | 6         | 1.11%   |
| Obninsk          | 6         | 1.11%   |
| Saratov          | 4         | 0.74%   |
| Rostov-on-Don    | 4         | 0.74%   |
| Krasnodar        | 4         | 0.74%   |
| Khabarovsk       | 4         | 0.74%   |
| Vladimir         | 3         | 0.55%   |
| Veliky Novgorod  | 3         | 0.55%   |
| Ufa              | 3         | 0.55%   |
| Tyumen           | 3         | 0.55%   |
| Surgut           | 3         | 0.55%   |
| Omsk             | 3         | 0.55%   |
| Nizhniy Novgorod | 3         | 0.55%   |
| Lipetsk          | 3         | 0.55%   |
| Kemerovo         | 3         | 0.55%   |
| Kaliningrad      | 3         | 0.55%   |
| Izhevsk          | 3         | 0.55%   |
| Irkutsk          | 3         | 0.55%   |
| Chelyabinsk      | 3         | 0.55%   |
| Bezhetsk         | 3         | 0.55%   |
| Astrakhan        | 3         | 0.55%   |
| Anapa            | 3         | 0.55%   |
| Vitebsk          | 2         | 0.37%   |
| Valencia         | 2         | 0.37%   |
| Ulyanovsk        | 2         | 0.37%   |
| Tura             | 2         | 0.37%   |
| Tula             | 2         | 0.37%   |
| Tolyatti         | 2         | 0.37%   |
| Thessaloniki     | 2         | 0.37%   |
| Tambov           | 2         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 67        | 94     | 10.65%  |
| Seagate                      | 49        | 54     | 7.79%   |
| WDC                          | 43        | 50     | 6.84%   |
| Intel                        | 38        | 52     | 6.04%   |
| BIWIN                        | 34        | 35     | 5.41%   |
| Kingston                     | 32        | 42     | 5.09%   |
| SK hynix                     | 28        | 31     | 4.45%   |
| A-DATA Technology            | 26        | 28     | 4.13%   |
| Toshiba                      | 22        | 26     | 3.5%    |
| SanDisk                      | 22        | 23     | 3.5%    |
| Micron Technology            | 18        | 20     | 2.86%   |
| Unknown                      | 16        | 25     | 2.54%   |
| Foxline                      | 14        | 14     | 2.23%   |
| China                        | 13        | 13     | 2.07%   |
| Hitachi                      | 12        | 12     | 1.91%   |
| Apacer                       | 11        | 12     | 1.75%   |
| MAXIO Technology (Hangzhou)  | 9         | 17     | 1.43%   |
| KIOXIA                       | 9         | 12     | 1.43%   |
| Phison                       | 8         | 9      | 1.27%   |
| FORESEE                      | 8         | 10     | 1.27%   |
| KingSpec                     | 7         | 7      | 1.11%   |
| Gigabyte Technology          | 7         | 7      | 1.11%   |
| Wodposit                     | 6         | 6      | 0.95%   |
| HGST                         | 6         | 6      | 0.95%   |
| Unknown                      | 6         | 7      | 0.95%   |
| XPG                          | 5         | 8      | 0.79%   |
| Patriot                      | 5         | 6      | 0.79%   |
| Netac                        | 5         | 5      | 0.79%   |
| Fujitsu                      | 5         | 5      | 0.79%   |
| Apple                        | 5         | 5      | 0.79%   |
| Transcend                    | 4         | 4      | 0.64%   |
| Crucial                      | 4         | 4      | 0.64%   |
| AMD                          | 4         | 4      | 0.64%   |
| ADATA Technology             | 4         | 4      | 0.64%   |
| YMTC                         | 3         | 3      | 0.48%   |
| UDSS                         | 3         | 3      | 0.48%   |
| SSSTC                        | 3         | 3      | 0.48%   |
| Silicon Motion               | 3         | 3      | 0.48%   |
| Shenzhen Longsys Electronics | 3         | 3      | 0.48%   |
| SCY                          | 3         | 3      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| BIWIN CE480T5D101-256 256GB                      | 32        | 4.98%   |
| Foxline FLSSD256M80E13TCX5 256GB                 | 13        | 2.02%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB          | 12        | 1.87%   |
| Intel SSDPEKNU512GZ 512GB                        | 10        | 1.56%   |
| Seagate ST1000LM049-2GH172 1TB                   | 9         | 1.4%    |
| Intel SSDPEMKF256G8H 256GB                       | 8         | 1.25%   |
| Intel SSDPEKKF256G7H 256GB                       | 8         | 1.25%   |
| Kingston SA400S37240G 240GB SSD                  | 7         | 1.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 6         | 0.93%   |
| SanDisk NVMe SSD Drive 512GB                     | 6         | 0.93%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB | 6         | 0.93%   |
| Apacer AS2280P4 256GB                            | 6         | 0.93%   |
| Unknown                                          | 6         | 0.93%   |
| Phison 311CD0512GB                               | 5         | 0.78%   |
| A-DATA SU800NS38 256GB SSD                       | 5         | 0.78%   |
| Toshiba MQ01ABF050 500GB                         | 4         | 0.62%   |
| Seagate ST9250315AS 250GB                        | 4         | 0.62%   |
| Seagate ST500LT012-1DG142 500GB                  | 4         | 0.62%   |
| Samsung SSD 860 EVO 250GB                        | 4         | 0.62%   |
| Samsung MZALQ256HAJD-000L2 256GB                 | 4         | 0.62%   |
| Micron 2400_MTFDKBA512QFM 512GB                  | 4         | 0.62%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB                 | 4         | 0.62%   |
| A-DATA SX6000PNP 256GB                           | 4         | 0.62%   |
| Wodposit NVMe SSD Drive 512GB                    | 3         | 0.47%   |
| Wodposit NVMe SSD 1TB                            | 3         | 0.47%   |
| Unknown NVMe SSD Drive 512GB                     | 3         | 0.47%   |
| Unknown MMC Card  32GB                           | 3         | 0.47%   |
| Shenzhen Longsys FORESEE XP1000F512G 512GB       | 3         | 0.47%   |
| Seagate ST1000LM035-1RK172 1TB                   | 3         | 0.47%   |
| Samsung MZVL4512HBLU-00BTW 512GB                 | 3         | 0.47%   |
| Kingston SA400S37480G 480GB SSD                  | 3         | 0.47%   |
| Kingston SA400S37120G 120GB SSD                  | 3         | 0.47%   |
| Kingston OM8PDP3256B-A01 256GB                   | 3         | 0.47%   |
| Intel SSDPEKNW512G8H 512GB                       | 3         | 0.47%   |
| HGST HTS721010A9E630 1TB                         | 3         | 0.47%   |
| FORESEE XP1000F256G 256GB                        | 3         | 0.47%   |
| External USB3.0 250GB                            | 3         | 0.47%   |
| China SSD 512GB                                  | 3         | 0.47%   |
| China SSD 240GB                                  | 3         | 0.47%   |
| Apple SSD AP0512N 500GB                          | 3         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 49        | 54     | 38.58%  |
| WDC      | 34        | 37     | 26.77%  |
| Toshiba  | 18        | 22     | 14.17%  |
| Hitachi  | 12        | 12     | 9.45%   |
| HGST     | 6         | 6      | 4.72%   |
| Fujitsu  | 5         | 5      | 3.94%   |
| External | 3         | 5      | 2.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 31     | 14.72%  |
| Kingston            | 20        | 29     | 12.27%  |
| A-DATA Technology   | 14        | 14     | 8.59%   |
| China               | 13        | 13     | 7.98%   |
| SanDisk             | 6         | 7      | 3.68%   |
| WDC                 | 5         | 8      | 3.07%   |
| Patriot             | 5         | 6      | 3.07%   |
| KingSpec            | 5         | 5      | 3.07%   |
| Unknown             | 5         | 6      | 3.07%   |
| Transcend           | 4         | 4      | 2.45%   |
| Intel               | 4         | 4      | 2.45%   |
| Apacer              | 4         | 5      | 2.45%   |
| AMD                 | 4         | 4      | 2.45%   |
| SK hynix            | 3         | 4      | 1.84%   |
| Micron Technology   | 3         | 3      | 1.84%   |
| Gigabyte Technology | 3         | 3      | 1.84%   |
| Crucial             | 3         | 3      | 1.84%   |
| XrayDisk            | 2         | 2      | 1.23%   |
| Smartbuy            | 2         | 2      | 1.23%   |
| Qumo                | 2         | 2      | 1.23%   |
| PNY                 | 2         | 2      | 1.23%   |
| Plextor             | 2         | 3      | 1.23%   |
| OCZ                 | 2         | 2      | 1.23%   |
| Netac               | 2         | 2      | 1.23%   |
| KingDian            | 2         | 2      | 1.23%   |
| GOODRAM             | 2         | 2      | 1.23%   |
| Foxline             | 2         | 2      | 1.23%   |
| Biwintech           | 2         | 3      | 1.23%   |
| Wdxsky              | 1         | 1      | 0.61%   |
| Union Memory        | 1         | 1      | 0.61%   |
| Team                | 1         | 1      | 0.61%   |
| SPCC                | 1         | 1      | 0.61%   |
| QUANXING            | 1         | 1      | 0.61%   |
| QOPP                | 1         | 1      | 0.61%   |
| LuminouTek          | 1         | 1      | 0.61%   |
| LS                  | 1         | 1      | 0.61%   |
| FORESEE             | 1         | 1      | 0.61%   |
| Fanxiang            | 1         | 1      | 0.61%   |
| Colorful            | 1         | 1      | 0.61%   |
| Bestoss             | 1         | 1      | 0.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 299       | 387    | 50.08%  |
| SSD     | 155       | 189    | 25.96%  |
| HDD     | 126       | 141    | 21.11%  |
| MMC     | 14        | 20     | 2.35%   |
| Unknown | 3         | 3      | 0.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 299       | 384    | 52.36%  |
| SATA | 245       | 321    | 42.91%  |
| MMC  | 14        | 20     | 2.45%   |
| SAS  | 13        | 15     | 2.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 203       | 248    | 74.63%  |
| 0.51-1.0   | 61        | 74     | 22.43%  |
| 1.01-2.0   | 7         | 7      | 2.57%   |
| 3.01-4.0   | 1         | 1      | 0.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 242       | 43.92%  |
| 251-500        | 109       | 19.78%  |
| 501-1000       | 66        | 11.98%  |
| 51-100         | 48        | 8.71%   |
| 1001-2000      | 34        | 6.17%   |
| 1-20           | 19        | 3.45%   |
| 21-50          | 18        | 3.27%   |
| 2001-3000      | 7         | 1.27%   |
| More than 3000 | 4         | 0.73%   |
| Unknown        | 4         | 0.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 210       | 37.37%  |
| 21-50          | 161       | 28.65%  |
| 51-100         | 77        | 13.7%   |
| 101-250        | 43        | 7.65%   |
| 251-500        | 33        | 5.87%   |
| 501-1000       | 23        | 4.09%   |
| 1001-2000      | 10        | 1.78%   |
| Unknown        | 4         | 0.71%   |
| More than 3000 | 1         | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                  | Notebooks | Drives | Percent |
|--------------------------------------------------------|-----------|--------|---------|
| Seagate ST9250315AS 250GB                              | 3         | 3      | 6.38%   |
| Toshiba MQ01ABD050 500GB                               | 2         | 2      | 4.26%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                  | 2         | 3      | 4.26%   |
| Seagate ST500LT012-1DG142 500GB                        | 2         | 2      | 4.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                     | 2         | 7      | 4.26%   |
| XrayDisk 240GB SSD                                     | 1         | 1      | 2.13%   |
| WDC WD6400BPVT-00HXZT1 640GB                           | 1         | 1      | 2.13%   |
| WDC WD5000LPVX-60V0TT0 500GB                           | 1         | 1      | 2.13%   |
| WDC WD5000LPLX-60ZNTT2 500GB                           | 1         | 1      | 2.13%   |
| WDC WD2500BEVT-80A23T0 250GB                           | 1         | 2      | 2.13%   |
| WDC WD1200BEVS-60UST0 120GB                            | 1         | 1      | 2.13%   |
| WDC WD1200BEVS-07LAT0 120GB                            | 1         | 1      | 2.13%   |
| Toshiba MK2555GSX 250GB                                | 1         | 1      | 2.13%   |
| Toshiba MK1637GSX 160GB                                | 1         | 1      | 2.13%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB                | 1         | 1      | 2.13%   |
| Shenzhen Longsys Electronics FORESEE XP1000F512G 512GB | 1         | 1      | 2.13%   |
| Seagate ST9640320AS 640GB                              | 1         | 1      | 2.13%   |
| Seagate ST9500325AS 500GB                              | 1         | 1      | 2.13%   |
| Seagate ST9320423AS 320GB                              | 1         | 1      | 2.13%   |
| Seagate ST9160827AS 160GB                              | 1         | 1      | 2.13%   |
| Seagate ST500LT012-9WS142 500GB                        | 1         | 1      | 2.13%   |
| SanDisk SD9SN8W-256G-1006 256GB SSD                    | 1         | 1      | 2.13%   |
| Samsung Electronics MZVLQ512HBLU-00BTW 512GB           | 1         | 1      | 2.13%   |
| Kingston SA400S37120G 120GB SSD                        | 1         | 1      | 2.13%   |
| KingSpec MSH-256 256GB SSD                             | 1         | 1      | 2.13%   |
| Intel SSDSCKKF256H6H 256GB                             | 1         | 1      | 2.13%   |
| Intel SSDSC2CW120A3 120GB                              | 1         | 1      | 2.13%   |
| Intel SSDSC2BW480A4 480GB                              | 1         | 1      | 2.13%   |
| Hitachi HTS725050A9A364 500GB                          | 1         | 1      | 2.13%   |
| Hitachi HTS723232A7A364 320GB                          | 1         | 1      | 2.13%   |
| Hitachi HTS543225L9A300 250GB                          | 1         | 1      | 2.13%   |
| Hitachi HTS542525K9A300 250GB                          | 1         | 1      | 2.13%   |
| Hitachi HTS541610J9SA00 100GB                          | 1         | 1      | 2.13%   |
| HGST HTS545050A7E680 500GB                             | 1         | 1      | 2.13%   |
| Fujitsu MHX2250BT 250GB                                | 1         | 1      | 2.13%   |
| Fujitsu MHW2160BH PL 160GB                             | 1         | 1      | 2.13%   |
| China SSD 240GB                                        | 1         | 1      | 2.13%   |
| China SSD 128GB                                        | 1         | 1      | 2.13%   |
| AMD R5SL120G 120GB SSD                                 | 1         | 1      | 2.13%   |
| A-DATA Technology SX6000PNP 256GB                      | 1         | 1      | 2.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 12        | 17     | 25.53%  |
| WDC                          | 6         | 7      | 12.77%  |
| Hitachi                      | 5         | 5      | 10.64%  |
| Toshiba                      | 4         | 4      | 8.51%   |
| SK hynix                     | 3         | 4      | 6.38%   |
| Intel                        | 3         | 3      | 6.38%   |
| Fujitsu                      | 2         | 2      | 4.26%   |
| China                        | 2         | 2      | 4.26%   |
| A-DATA Technology            | 2         | 2      | 4.26%   |
| XrayDisk                     | 1         | 1      | 2.13%   |
| Shenzhen Longsys Electronics | 1         | 1      | 2.13%   |
| SanDisk                      | 1         | 1      | 2.13%   |
| Samsung Electronics          | 1         | 1      | 2.13%   |
| Kingston                     | 1         | 1      | 2.13%   |
| KingSpec                     | 1         | 1      | 2.13%   |
| HGST                         | 1         | 1      | 2.13%   |
| AMD                          | 1         | 1      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 12        | 17     | 40%     |
| WDC     | 6         | 7      | 20%     |
| Hitachi | 5         | 5      | 16.67%  |
| Toshiba | 4         | 4      | 13.33%  |
| Fujitsu | 2         | 2      | 6.67%   |
| HGST    | 1         | 1      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 36     | 63.83%  |
| SSD  | 13        | 14     | 27.66%  |
| NVMe | 4         | 4      | 8.51%   |

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
| Works    | 375       | 500    | 67.32%  |
| Detected | 135       | 186    | 24.24%  |
| Malfunc  | 47        | 54     | 8.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 353       | 50.72%  |
| AMD                                     | 53        | 7.61%   |
| Samsung Electronics                     | 43        | 6.18%   |
| INNOGRIT                                | 33        | 4.74%   |
| Phison Electronics                      | 31        | 4.45%   |
| SK hynix                                | 24        | 3.45%   |
| SanDisk                                 | 21        | 3.02%   |
| Micron Technology                       | 15        | 2.16%   |
| MAXIO Technology (Hangzhou)             | 15        | 2.16%   |
| Kingston Technology Company             | 15        | 2.16%   |
| ADATA Technology                        | 13        | 1.87%   |
| Shenzhen Longsys Electronics            | 11        | 1.58%   |
| KIOXIA                                  | 9         | 1.29%   |
| Silicon Motion                          | 7         | 1.01%   |
| Unknown                                 | 7         | 1.01%   |
| Nvidia                                  | 6         | 0.86%   |
| Yangtze Memory Technologies             | 5         | 0.72%   |
| Realtek Semiconductor                   | 5         | 0.72%   |
| Toshiba America Info Systems            | 4         | 0.57%   |
| Solid State Storage Technology          | 4         | 0.57%   |
| TenaFe                                  | 3         | 0.43%   |
| Shenzhen Shichuangyi Electronics        | 3         | 0.43%   |
| Netac Technology                        | 3         | 0.43%   |
| Micron/Crucial Technology               | 3         | 0.43%   |
| Apple                                   | 3         | 0.43%   |
| VIA Technologies                        | 2         | 0.29%   |
| Zhaoxin                                 | 1         | 0.14%   |
| Union Memory (Shenzhen)                 | 1         | 0.14%   |
| Shenzhen Unionmemory Information System | 1         | 0.14%   |
| Jiangsu Huacun Elec.                    | 1         | 0.14%   |
| Hosin Global Electronics                | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                                              | Notebooks | Percent |
|--------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Tiger Lake-LP SATA Controller                                                                                | 59        | 7.93%   |
| AMD FCH SATA Controller [AHCI mode]                                                                                | 48        | 6.45%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                                                 | 39        | 5.24%   |
| INNOGRIT NVMe SSD Controller IG5216 [Shasta+] (DRAM-less)                                                          | 33        | 4.44%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                                                | 27        | 3.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                                                   | 26        | 3.49%   |
| Intel Comet Lake SATA AHCI Controller                                                                              | 25        | 3.36%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                                                     | 22        | 2.96%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                                                  | 20        | 2.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller                                       | 18        | 2.42%   |
| Intel Volume Management Device NVMe RAID Controller                                                                | 16        | 2.15%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                                                        | 15        | 2.02%   |
| SK hynix BC501 NVMe Solid State Drive                                                                              | 14        | 1.88%   |
| Intel Alder Lake-P SATA AHCI Controller                                                                            | 14        | 1.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                                                      | 13        | 1.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                                                  | 13        | 1.75%   |
| Intel SSD 670p Series [Keystone Harbor]                                                                            | 12        | 1.61%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                                             | 12        | 1.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                                              | 12        | 1.61%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                                           | 11        | 1.48%   |
| Shenzhen Longsys FORESEE XP1000 / Lexar Professional CFexpress Type B Gold series, NM620 PCIe NVME SSD (DRAM-less) | 9         | 1.21%   |
| Intel SSD 600P Series                                                                                              | 9         | 1.21%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                                             | 9         | 1.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                                                       | 9         | 1.21%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                                                     | 9         | 1.21%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                                                   | 8         | 1.08%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                                                   | 8         | 1.08%   |
| ADATA XPG GAMMIXS1 1L, XPG GAMMIX S5, LEGEND 710 / 740, SWORDFISH NVMe SSD (DRAM-less)                             | 7         | 0.94%   |
| Unknown                                                                                                            | 7         | 0.94%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                                                       | 6         | 0.81%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                                                      | 6         | 0.81%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                                                         | 6         | 0.81%   |
| Kingston Company OM3PDP3 NVMe SSD                                                                                  | 6         | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                                                      | 6         | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                                                   | 6         | 0.81%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                                                  | 5         | 0.67%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                                                 | 5         | 0.67%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                                               | 4         | 0.54%   |
| SK hynix BC511 NVMe SSD                                                                                            | 4         | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                                                     | 4         | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 354       | 49.17%  |
| NVMe | 297       | 41.25%  |
| RAID | 41        | 5.69%   |
| IDE  | 28        | 3.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 398       | 75.52%  |
| AMD          | 127       | 24.1%   |
| CentaurHauls | 2         | 0.38%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 52        | 9.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 23        | 4.36%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 2.65%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 13        | 2.46%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 13        | 2.46%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 11        | 2.08%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 1.89%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 9         | 1.7%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 8         | 1.52%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 1.33%   |
| Intel 12th Gen Core i5-12450H                 | 7         | 1.33%   |
| Intel 12th Gen Core i5-1235U                  | 7         | 1.33%   |
| Intel Core i5-8279U CPU @ 2.40GHz             | 6         | 1.14%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.14%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 6         | 1.14%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 6         | 1.14%   |
| Intel 11th Gen Core i3-1125G4 @ 2.00GHz       | 6         | 1.14%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 0.95%   |
| AMD Ryzen 5 5560U with Radeon Graphics        | 5         | 0.95%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.95%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 4         | 0.76%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 0.76%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 4         | 0.76%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 4         | 0.76%   |
| Intel 12th Gen Core i7-12700H                 | 4         | 0.76%   |
| Intel 11th Gen Core i5-1155G7 @ 2.50GHz       | 4         | 0.76%   |
| AMD Ryzen 5 7430U with Radeon Graphics        | 4         | 0.76%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 4         | 0.76%   |
| Intel Core Ultra 5 125H                       | 3         | 0.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.57%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.57%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 0.57%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 3         | 0.57%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 3         | 0.57%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.57%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 0.57%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 0.57%   |
| Intel 12th Gen Core i3-1215U                  | 3         | 0.57%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.57%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 3         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Other                   | 118       | 22.35%  |
| Intel Core i5           | 107       | 20.27%  |
| Intel Core i3           | 54        | 10.23%  |
| AMD Ryzen 5             | 49        | 9.28%   |
| Intel Core i7           | 41        | 7.77%   |
| AMD Ryzen 7             | 28        | 5.3%    |
| Intel Celeron           | 24        | 4.55%   |
| Intel Core 2 Duo        | 18        | 3.41%   |
| Intel Pentium           | 10        | 1.89%   |
| AMD Ryzen 3             | 10        | 1.89%   |
| Intel Atom              | 9         | 1.7%    |
| AMD A8                  | 7         | 1.33%   |
| AMD A6                  | 6         | 1.14%   |
| Intel Core              | 5         | 0.95%   |
| AMD E1                  | 4         | 0.76%   |
| Intel Pentium Silver    | 3         | 0.57%   |
| AMD Athlon              | 3         | 0.57%   |
| AMD A10                 | 3         | 0.57%   |
| Intel Pentium Gold      | 2         | 0.38%   |
| Intel Pentium Dual-Core | 2         | 0.38%   |
| Intel Pentium Dual      | 2         | 0.38%   |
| Intel Celeron Dual-Core | 2         | 0.38%   |
| AMD E2                  | 2         | 0.38%   |
| AMD E                   | 2         | 0.38%   |
| Intel Pentium M         | 1         | 0.19%   |
| Intel Genuine           | 1         | 0.19%   |
| Intel Core m5           | 1         | 0.19%   |
| Intel Core Duo          | 1         | 0.19%   |
| Intel Core 2 Solo       | 1         | 0.19%   |
| Intel Celeron M         | 1         | 0.19%   |
| CentaurHauls VIA C7     | 1         | 0.19%   |
| AMD Turion 64 X2 Mobile | 1         | 0.19%   |
| AMD Ryzen 9             | 1         | 0.19%   |
| AMD Ryzen 7 PRO         | 1         | 0.19%   |
| AMD Mobile Athlon 64    | 1         | 0.19%   |
| AMD FX                  | 1         | 0.19%   |
| AMD C-60                | 1         | 0.19%   |
| AMD C-50                | 1         | 0.19%   |
| AMD Athlon 64 X2        | 1         | 0.19%   |
| AMD A4                  | 1         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 198       | 37.36%  |
| 2      | 193       | 36.42%  |
| 6      | 60        | 11.32%  |
| 8      | 37        | 6.98%   |
| 10     | 15        | 2.83%   |
| 1      | 13        | 2.45%   |
| 14     | 8         | 1.51%   |
| 12     | 4         | 0.75%   |
| 16     | 1         | 0.19%   |
| 7      | 1         | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 527       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 423       | 80.11%  |
| 1      | 105       | 19.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 519       | 98.48%  |
| 32-bit         | 7         | 1.33%   |
| Unknown        | 1         | 0.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 244       | 45.1%   |
| 0x806c1    | 56        | 10.35%  |
| 0x806ec    | 21        | 3.88%   |
| 0x806ea    | 21        | 3.88%   |
| 0x806e9    | 19        | 3.51%   |
| 0x906ea    | 12        | 2.22%   |
| 0x306a9    | 10        | 1.85%   |
| 0x206a7    | 10        | 1.85%   |
| 0x1067a    | 9         | 1.66%   |
| 0x0a50000c | 9         | 1.66%   |
| 0xa0660    | 8         | 1.48%   |
| 0x08108109 | 7         | 1.29%   |
| 0x906a4    | 6         | 1.11%   |
| 0x706e5    | 6         | 1.11%   |
| 0x906a3    | 5         | 0.92%   |
| 0x806c2    | 5         | 0.92%   |
| 0x6fd      | 5         | 0.92%   |
| 0x406e3    | 5         | 0.92%   |
| 0x30678    | 5         | 0.92%   |
| 0x40651    | 4         | 0.74%   |
| 0x08600106 | 4         | 0.74%   |
| 0x20655    | 3         | 0.55%   |
| 0x106ca    | 3         | 0.55%   |
| 0x10676    | 3         | 0.55%   |
| 0x0700010f | 3         | 0.55%   |
| 0x06001119 | 3         | 0.55%   |
| 0x906c0    | 2         | 0.37%   |
| 0x706a8    | 2         | 0.37%   |
| 0x706a1    | 2         | 0.37%   |
| 0x6e8      | 2         | 0.37%   |
| 0x506c9    | 2         | 0.37%   |
| 0x306c3    | 2         | 0.37%   |
| 0x106c2    | 2         | 0.37%   |
| 0x0a404107 | 2         | 0.37%   |
| 0x0a404102 | 2         | 0.37%   |
| 0x08608108 | 2         | 0.37%   |
| 0x08608103 | 2         | 0.37%   |
| 0x08608102 | 2         | 0.37%   |
| 0xb06a3    | 1         | 0.18%   |
| 0xb06a2    | 1         | 0.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 108       | 20.45%  |
| TigerLake         | 78        | 14.77%  |
| Unknown           | 51        | 9.66%   |
| Zen 3             | 35        | 6.63%   |
| IvyBridge         | 26        | 4.92%   |
| Alderlake Hybrid  | 26        | 4.92%   |
| SandyBridge       | 23        | 4.36%   |
| Penryn            | 16        | 3.03%   |
| Zen+              | 14        | 2.65%   |
| Haswell           | 14        | 2.65%   |
| Silvermont        | 13        | 2.46%   |
| Westmere          | 12        | 2.27%   |
| Goldmont plus     | 12        | 2.27%   |
| CometLake         | 11        | 2.08%   |
| Core              | 9         | 1.7%    |
| Skylake           | 8         | 1.52%   |
| IceLake           | 8         | 1.52%   |
| Zen 2             | 7         | 1.33%   |
| Piledriver        | 7         | 1.33%   |
| Bonnell           | 7         | 1.33%   |
| Excavator         | 6         | 1.14%   |
| Bobcat            | 5         | 0.95%   |
| Puma              | 4         | 0.76%   |
| P6                | 4         | 0.76%   |
| Meteorlake Hybrid | 4         | 0.76%   |
| K10 Llano         | 4         | 0.76%   |
| Tremont           | 3         | 0.57%   |
| K8 Hammer         | 3         | 0.57%   |
| Jaguar            | 3         | 0.57%   |
| Goldmont          | 2         | 0.38%   |
| Broadwell         | 2         | 0.38%   |
| Steamroller       | 1         | 0.19%   |
| Nehalem           | 1         | 0.19%   |
| Gracemont         | 1         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 370       | 60.56%  |
| AMD              | 148       | 24.22%  |
| Nvidia           | 91        | 14.89%  |
| Zhaoxin          | 1         | 0.16%   |
| VIA Technologies | 1         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 63        | 9.87%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                   | 27        | 4.23%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 25        | 3.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 21        | 3.29%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 21        | 3.29%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 19        | 2.98%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                          | 19        | 2.98%   |
| AMD Lucienne                                                              | 16        | 2.51%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 15        | 2.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 14        | 2.19%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 14        | 2.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 14        | 2.19%   |
| AMD Barcelo                                                               | 13        | 2.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 11        | 1.72%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                  | 10        | 1.57%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 10        | 1.57%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                     | 9         | 1.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 9         | 1.41%   |
| AMD Rembrandt [Radeon 680M]                                               | 9         | 1.41%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 8         | 1.25%   |
| Intel Comet Lake UHD Graphics                                             | 8         | 1.25%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                     | 8         | 1.25%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 7         | 1.1%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 7         | 1.1%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]               | 7         | 1.1%    |
| Intel Skylake-U GT2 [HD Graphics 520]                                     | 6         | 0.94%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 6         | 0.94%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 6         | 0.94%   |
| Intel Raptor Lake-P [UHD Graphics]                                        | 5         | 0.78%   |
| Intel Core Processor Integrated Graphics Controller                       | 5         | 0.78%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                   | 5         | 0.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 5         | 0.78%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                    | 5         | 0.78%   |
| AMD Mendocino [Radeon 610M]                                               | 5         | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 4         | 0.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 4         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 4         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 4         | 0.63%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                  | 4         | 0.63%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 293       | 55.49%  |
| 1 x AMD        | 106       | 20.08%  |
| Intel + Nvidia | 62        | 11.74%  |
| 2 x AMD        | 19        | 3.6%    |
| 1 x Nvidia     | 19        | 3.6%    |
| Intel + AMD    | 13        | 2.46%   |
| AMD + Nvidia   | 10        | 1.89%   |
| 2 x Intel      | 3         | 0.57%   |
| Other          | 1         | 0.19%   |
| 1 x Zhaoxin    | 1         | 0.19%   |
| 1 x VIA        | 1         | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 463       | 87.36%  |
| Proprietary | 34        | 6.42%   |
| Unknown     | 33        | 6.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 407       | 76.22%  |
| 0.01-0.5   | 73        | 13.67%  |
| 0.51-1.0   | 24        | 4.49%   |
| 1.01-2.0   | 15        | 2.81%   |
| 3.01-4.0   | 14        | 2.62%   |
| 5.01-6.0   | 1         | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 150       | 26.46%  |
| Chimei Innolux          | 107       | 18.87%  |
| AU Optronics            | 68        | 11.99%  |
| LG Display              | 46        | 8.11%   |
| Samsung Electronics     | 41        | 7.23%   |
| PANDA                   | 18        | 3.17%   |
| Chi Mei Optoelectronics | 12        | 2.12%   |
| Sharp                   | 10        | 1.76%   |
| Apple                   | 9         | 1.59%   |
| HKC                     | 8         | 1.41%   |
| BenQ                    | 7         | 1.23%   |
| STA                     | 6         | 1.06%   |
| AOC                     | 6         | 1.06%   |
| PRM                     | 5         | 0.88%   |
| InfoVision              | 4         | 0.71%   |
| Goldstar                | 4         | 0.71%   |
| Dell                    | 4         | 0.71%   |
| CSW                     | 4         | 0.71%   |
| CSOT                    | 4         | 0.71%   |
| TMX                     | 3         | 0.53%   |
| Philips                 | 3         | 0.53%   |
| OOO                     | 3         | 0.53%   |
| HUAWEI                  | 3         | 0.53%   |
| HannStar                | 3         | 0.53%   |
| AGO                     | 3         | 0.53%   |
| VIE                     | 2         | 0.35%   |
| Mi                      | 2         | 0.35%   |
| JDZ                     | 2         | 0.35%   |
| InnoLux Display         | 2         | 0.35%   |
| CPT                     | 2         | 0.35%   |
| Valve                   | 1         | 0.18%   |
| TR_                     | 1         | 0.18%   |
| Toshiba                 | 1         | 0.18%   |
| SYM                     | 1         | 0.18%   |
| Sony                    | 1         | 0.18%   |
| SKG                     | 1         | 0.18%   |
| SBI                     | 1         | 0.18%   |
| SAC                     | 1         | 0.18%   |
| S2-Tek                  | 1         | 0.18%   |
| RGT                     | 1         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE09C5 1920x1080 345x194mm 15.6-inch                | 15        | 2.63%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 13        | 2.28%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 11        | 1.93%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch              | 9         | 1.58%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch     | 9         | 1.58%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 9         | 1.58%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                | 8         | 1.4%    |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                | 7         | 1.23%   |
| STA LCD Monitor STAAFC9 1920x1080 344x194mm 15.5-inch                | 6         | 1.05%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 6         | 1.05%   |
| BOE LCD Monitor BOE0AF7 1920x1080 344x194mm 15.5-inch                | 6         | 1.05%   |
| BOE LCD Monitor BOE09EF 1920x1080 344x194mm 15.5-inch                | 6         | 1.05%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 6         | 1.05%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                | 5         | 0.88%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 5         | 0.88%   |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch       | 5         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 4         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 4         | 0.7%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 4         | 0.7%    |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch     | 4         | 0.7%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 4         | 0.7%    |
| BOE LCD Monitor BOE07D0 1920x1080 294x165mm 13.3-inch                | 4         | 0.7%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 4         | 0.7%    |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch              | 3         | 0.53%   |
| Sharp LCD Monitor SHP1540 1920x1080 309x174mm 14.0-inch              | 3         | 0.53%   |
| OOO DP OOO2700 2560x1440 597x336mm 27.0-inch                         | 3         | 0.53%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch         | 3         | 0.53%   |
| Chimei Innolux LCD Monitor CMN153C 1920x1080 344x193mm 15.5-inch     | 3         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch     | 3         | 0.53%   |
| Chimei Innolux LCD Monitor CMN142B 1920x1080 309x173mm 13.9-inch     | 3         | 0.53%   |
| BOE LCD Monitor BOE0A74 1920x1200 345x215mm 16.0-inch                | 3         | 0.53%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 3         | 0.53%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                | 3         | 0.53%   |
| BOE LCD Monitor BOE081D 1920x1080 309x174mm 14.0-inch                | 3         | 0.53%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch        | 3         | 0.53%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 3         | 0.53%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch        | 3         | 0.53%   |
| VIE IM27VL1 VIE2120 1920x1080 600x330mm 27.0-inch                    | 2         | 0.35%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 2         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 309       | 57.76%  |
| 1366x768 (WXGA)    | 98        | 18.32%  |
| 2560x1600          | 24        | 4.49%   |
| 1920x1200 (WUXGA)  | 18        | 3.36%   |
| 1600x900 (HD+)     | 17        | 3.18%   |
| 1280x800 (WXGA)    | 15        | 2.8%    |
| 2560x1440 (QHD)    | 9         | 1.68%   |
| 3840x2160 (4K)     | 6         | 1.12%   |
| 2880x1800          | 6         | 1.12%   |
| 1280x1024 (SXGA)   | 6         | 1.12%   |
| 1680x1050 (WSXGA+) | 4         | 0.75%   |
| 1024x600           | 4         | 0.75%   |
| 1440x900 (WXGA+)   | 3         | 0.56%   |
| 3072x1920          | 2         | 0.37%   |
| 2160x1440          | 2         | 0.37%   |
| 800x1280           | 1         | 0.19%   |
| 3840x2560          | 1         | 0.19%   |
| 3840x2400          | 1         | 0.19%   |
| 3200x2000          | 1         | 0.19%   |
| 3200x1800 (QHD+)   | 1         | 0.19%   |
| 3000x2000          | 1         | 0.19%   |
| 2944x1840          | 1         | 0.19%   |
| 2880x1620          | 1         | 0.19%   |
| 2520x1680          | 1         | 0.19%   |
| 2240x1400          | 1         | 0.19%   |
| 1400x1050          | 1         | 0.19%   |
| 1024x768 (XGA)     | 1         | 0.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 261       | 45.95%  |
| 14      | 76        | 13.38%  |
| 13      | 76        | 13.38%  |
| 17      | 37        | 6.51%   |
| 16      | 23        | 4.05%   |
| 24      | 15        | 2.64%   |
| 27      | 14        | 2.46%   |
| 12      | 11        | 1.94%   |
| 21      | 9         | 1.58%   |
| 23      | 8         | 1.41%   |
| Unknown | 8         | 1.41%   |
| 11      | 7         | 1.23%   |
| 31      | 5         | 0.88%   |
| 10      | 4         | 0.7%    |
| 19      | 3         | 0.53%   |
| 59      | 1         | 0.18%   |
| 52      | 1         | 0.18%   |
| 50      | 1         | 0.18%   |
| 49      | 1         | 0.18%   |
| 42      | 1         | 0.18%   |
| 40      | 1         | 0.18%   |
| 34      | 1         | 0.18%   |
| 28      | 1         | 0.18%   |
| 22      | 1         | 0.18%   |
| 8       | 1         | 0.18%   |
| 7       | 1         | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 409       | 72.39%  |
| 201-300     | 45        | 7.96%   |
| 351-400     | 43        | 7.61%   |
| 501-600     | 33        | 5.84%   |
| 401-500     | 12        | 2.12%   |
| Unknown     | 8         | 1.42%   |
| 601-700     | 6         | 1.06%   |
| 1001-1500   | 4         | 0.71%   |
| 801-900     | 1         | 0.18%   |
| 701-800     | 1         | 0.18%   |
| 101-200     | 1         | 0.18%   |
| 901-1000    | 1         | 0.18%   |
| 1-100       | 1         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 428       | 81.06%  |
| 16/10 | 78        | 14.77%  |
| 3/2   | 7         | 1.33%   |
| 4/3   | 6         | 1.14%   |
| 5/4   | 5         | 0.95%   |
| 6/5   | 1         | 0.19%   |
| 32/9  | 1         | 0.19%   |
| 21/9  | 1         | 0.19%   |
| 0.67  | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 249       | 43.92%  |
| 81-90          | 137       | 24.16%  |
| 121-130        | 35        | 6.17%   |
| 111-120        | 35        | 6.17%   |
| 201-250        | 23        | 4.06%   |
| 71-80          | 16        | 2.82%   |
| 301-350        | 14        | 2.47%   |
| 61-70          | 8         | 1.41%   |
| Unknown        | 8         | 1.41%   |
| 51-60          | 7         | 1.23%   |
| 351-500        | 7         | 1.23%   |
| 251-300        | 7         | 1.23%   |
| 41-50          | 4         | 0.71%   |
| 151-200        | 4         | 0.71%   |
| More than 1000 | 3         | 0.53%   |
| 501-1000       | 3         | 0.53%   |
| 91-100         | 3         | 0.53%   |
| 1-40           | 2         | 0.35%   |
| 131-140        | 2         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 319       | 56.56%  |
| 101-120       | 109       | 19.33%  |
| 51-100        | 62        | 10.99%  |
| 161-240       | 54        | 9.57%   |
| More than 240 | 9         | 1.6%    |
| Unknown       | 8         | 1.42%   |
| 1-50          | 3         | 0.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 461       | 86.33%  |
| 2     | 58        | 10.86%  |
| 0     | 11        | 2.06%   |
| 3     | 4         | 0.75%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 267       | 34.23%  |
| Realtek Semiconductor           | 265       | 33.97%  |
| Qualcomm Atheros                | 83        | 10.64%  |
| Broadcom                        | 55        | 7.05%   |
| MediaTek                        | 33        | 4.23%   |
| Marvell Technology Group        | 10        | 1.28%   |
| Broadcom Limited                | 8         | 1.03%   |
| ASIX Electronics                | 8         | 1.03%   |
| D-Link                          | 7         | 0.9%    |
| Nvidia                          | 6         | 0.77%   |
| Qualcomm                        | 5         | 0.64%   |
| Ralink Technology               | 4         | 0.51%   |
| Ralink                          | 4         | 0.51%   |
| JMicron Technology              | 3         | 0.38%   |
| Huawei Technologies             | 3         | 0.38%   |
| Sierra Wireless                 | 2         | 0.26%   |
| Lenovo                          | 2         | 0.26%   |
| Attansic Technology             | 2         | 0.26%   |
| ASUSTek Computer                | 2         | 0.26%   |
| ZTopInc                         | 1         | 0.13%   |
| Xiaomi                          | 1         | 0.13%   |
| TP-Link                         | 1         | 0.13%   |
| Samsung Electronics             | 1         | 0.13%   |
| Qualcomm Atheros Communications | 1         | 0.13%   |
| OPPO Electronics                | 1         | 0.13%   |
| Motorola PCS                    | 1         | 0.13%   |
| Micro Star International        | 1         | 0.13%   |
| Hewlett-Packard                 | 1         | 0.13%   |
| DisplayLink                     | 1         | 0.13%   |
| D-Link System                   | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 175       | 17.88%  |
| Intel Wi-Fi 6 AX201                                                    | 65        | 6.64%   |
| Intel Ethernet Connection (13) I219-V                                  | 48        | 4.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 31        | 3.17%   |
| Intel Wireless 7265                                                    | 31        | 3.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 28        | 2.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 25        | 2.55%   |
| Intel Wireless 8265 / 8275                                             | 21        | 2.15%   |
| Intel Ethernet Connection (10) I219-V                                  | 21        | 2.15%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 20        | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 17        | 1.74%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 15        | 1.53%   |
| Intel Ethernet Connection (6) I219-V                                   | 15        | 1.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 14        | 1.43%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 14        | 1.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 13        | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 13        | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 13        | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 12        | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                          | 12        | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 9         | 0.92%   |
| Intel Wireless 3165                                                    | 9         | 0.92%   |
| Intel Ethernet Connection (7) I219-LM                                  | 9         | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 8         | 0.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 0.82%   |
| Intel Wireless 7260                                                    | 8         | 0.82%   |
| Intel Wi-Fi 6 AX200                                                    | 8         | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 8         | 0.82%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 7         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 7         | 0.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 0.72%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                      | 7         | 0.72%   |
| ASIX AX88179 Gigabit Ethernet                                          | 7         | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 6         | 0.61%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 6         | 0.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 5         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 5         | 0.51%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]   | 5         | 0.51%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 5         | 0.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 5         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 246       | 46.77%  |
| Realtek Semiconductor           | 109       | 20.72%  |
| Qualcomm Atheros                | 70        | 13.31%  |
| Broadcom                        | 44        | 8.37%   |
| MediaTek                        | 31        | 5.89%   |
| Broadcom Limited                | 5         | 0.95%   |
| Ralink Technology               | 4         | 0.76%   |
| Ralink                          | 4         | 0.76%   |
| Qualcomm                        | 4         | 0.76%   |
| Sierra Wireless                 | 2         | 0.38%   |
| ASUSTek Computer                | 2         | 0.38%   |
| ZTopInc                         | 1         | 0.19%   |
| Qualcomm Atheros Communications | 1         | 0.19%   |
| Micro Star International        | 1         | 0.19%   |
| D-Link System                   | 1         | 0.19%   |
| D-Link                          | 1         | 0.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 65        | 12.31%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 31        | 5.87%   |
| Intel Wireless 7265                                                     | 31        | 5.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 28        | 5.3%    |
| Intel Wireless 8265 / 8275                                              | 21        | 3.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 3.22%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 15        | 2.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 2.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 14        | 2.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 2.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 2.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 13        | 2.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 12        | 2.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 12        | 2.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.7%    |
| Intel Wireless 3165                                                     | 9         | 1.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 1.52%   |
| Intel Wireless 7260                                                     | 8         | 1.52%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 1.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.52%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 7         | 1.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 1.33%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 7         | 1.33%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 6         | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 0.95%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 5         | 0.95%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.95%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.95%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 4         | 0.76%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 4         | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.76%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 4         | 0.76%   |
| Intel WiFi Link 5100                                                    | 4         | 0.76%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 4         | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 0.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 0.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 217       | 48.87%  |
| Intel                    | 134       | 30.18%  |
| Qualcomm Atheros         | 27        | 6.08%   |
| Broadcom                 | 14        | 3.15%   |
| Marvell Technology Group | 10        | 2.25%   |
| ASIX Electronics         | 8         | 1.8%    |
| Nvidia                   | 6         | 1.35%   |
| D-Link                   | 6         | 1.35%   |
| JMicron Technology       | 3         | 0.68%   |
| Huawei Technologies      | 3         | 0.68%   |
| Broadcom Limited         | 3         | 0.68%   |
| MediaTek                 | 2         | 0.45%   |
| Lenovo                   | 2         | 0.45%   |
| Attansic Technology      | 2         | 0.45%   |
| Xiaomi                   | 1         | 0.23%   |
| TP-Link                  | 1         | 0.23%   |
| Samsung Electronics      | 1         | 0.23%   |
| Qualcomm                 | 1         | 0.23%   |
| OPPO Electronics         | 1         | 0.23%   |
| Motorola PCS             | 1         | 0.23%   |
| DisplayLink              | 1         | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 175       | 38.89%  |
| Intel Ethernet Connection (13) I219-V                                  | 48        | 10.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 25        | 5.56%   |
| Intel Ethernet Connection (10) I219-V                                  | 21        | 4.67%   |
| Intel Ethernet Connection (6) I219-V                                   | 15        | 3.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 13        | 2.89%   |
| Intel Ethernet Connection (7) I219-LM                                  | 9         | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 8         | 1.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 7         | 1.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 1.56%   |
| ASIX AX88179 Gigabit Ethernet                                          | 7         | 1.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 6         | 1.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 5         | 1.11%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 5         | 1.11%   |
| Intel Ethernet Connection (4) I219-V                                   | 4         | 0.89%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                               | 4         | 0.89%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 3         | 0.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3         | 0.67%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 3         | 0.67%   |
| Intel WiMAX Connection 2400m                                           | 3         | 0.67%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 0.67%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 0.67%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.44%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.44%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 2         | 0.44%   |
| Nvidia MCP89 Ethernet                                                  | 2         | 0.44%   |
| Nvidia MCP79 Ethernet                                                  | 2         | 0.44%   |
| MediaTek Infinix HOT 50i                                               | 2         | 0.44%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 2         | 0.44%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.44%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.44%   |
| Intel Ethernet Connection (23) I219-V                                  | 2         | 0.44%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]           | 2         | 0.44%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.44%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 2         | 0.44%   |
| Attansic AR8152 v2.0 Fast Ethernet                                     | 2         | 0.44%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.22%   |
| TP-Link USB 10/100 LAN                                                 | 1         | 0.22%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 508       | 54.51%  |
| Ethernet | 423       | 45.39%  |
| Modem    | 1         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 401       | 72.78%  |
| Ethernet | 150       | 27.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 384       | 72.73%  |
| 1     | 136       | 25.76%  |
| 0     | 6         | 1.14%   |
| 3     | 2         | 0.38%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 495       | 93.4%   |
| Yes  | 35        | 6.6%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 235       | 51.54%  |
| Realtek Semiconductor           | 68        | 14.91%  |
| IMC Networks                    | 34        | 7.46%   |
| Foxconn / Hon Hai               | 24        | 5.26%   |
| Qualcomm Atheros Communications | 20        | 4.39%   |
| Broadcom                        | 20        | 4.39%   |
| Lite-On Technology              | 14        | 3.07%   |
| Hewlett-Packard                 | 7         | 1.54%   |
| MediaTek                        | 6         | 1.32%   |
| Apple                           | 6         | 1.32%   |
| Realtek                         | 5         | 1.1%    |
| Toshiba                         | 3         | 0.66%   |
| Ralink                          | 3         | 0.66%   |
| Foxconn International           | 2         | 0.44%   |
| ASUSTek Computer                | 2         | 0.44%   |
| USI                             | 1         | 0.22%   |
| TP-Link                         | 1         | 0.22%   |
| Opticis                         | 1         | 0.22%   |
| Dell                            | 1         | 0.22%   |
| Chicony Electronics             | 1         | 0.22%   |
| Cambridge Silicon Radio         | 1         | 0.22%   |
| Alps Electric                   | 1         | 0.22%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                             | 87        | 19.08%  |
| Intel Bluetooth wireless interface                | 73        | 16.01%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 37        | 8.11%   |
| Realtek Bluetooth Radio                           | 36        | 7.89%   |
| Realtek 802.11ac WLAN Adapter                     | 17        | 3.73%   |
| IMC Networks Wireless_Device                      | 15        | 3.29%   |
| Intel Wireless-AC 3168 Bluetooth                  | 14        | 3.07%   |
| Qualcomm Atheros  Bluetooth Device                | 11        | 2.41%   |
| Intel Bluetooth Device                            | 9         | 1.97%   |
| Realtek  Bluetooth 4.2 Adapter                    | 8         | 1.75%   |
| Intel AX200 Bluetooth                             | 8         | 1.75%   |
| IMC Networks Bluetooth Radio                      | 8         | 1.75%   |
| Foxconn / Hon Hai Bluetooth Device                | 8         | 1.75%   |
| MediaTek Wireless_Device                          | 6         | 1.32%   |
| Realtek Bluetooth Radio                           | 5         | 1.1%    |
| IMC Networks Bluetooth Device                     | 5         | 1.1%    |
| Realtek RTL8723B Bluetooth                        | 4         | 0.88%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 4         | 0.88%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 4         | 0.88%   |
| HP Broadcom 2070 Bluetooth Combo                  | 4         | 0.88%   |
| Foxconn / Hon Hai Wireless_Device                 | 4         | 0.88%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter      | 4         | 0.88%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR              | 4         | 0.88%   |
| Broadcom BCM2045 Bluetooth                        | 4         | 0.88%   |
| Apple Bluetooth Host Controller                   | 4         | 0.88%   |
| Ralink RT3290 Bluetooth                           | 3         | 0.66%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device      | 3         | 0.66%   |
| Lite-On Atheros AR3012 Bluetooth                  | 3         | 0.66%   |
| Intel AX210 Bluetooth                             | 3         | 0.66%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller   | 3         | 0.66%   |
| Realtek RTL8821A Bluetooth                        | 2         | 0.44%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 0.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 2         | 0.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 0.44%   |
| Lite-On Qualcomm Atheros Bluetooth                | 2         | 0.44%   |
| Lite-On Bluetooth Device                          | 2         | 0.44%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 2         | 0.44%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 2         | 0.44%   |
| Foxconn International BCM43142A0 Bluetooth module | 2         | 0.44%   |
| Broadcom HP Portable Bumble Bee                   | 2         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 389       | 60.59%  |
| AMD                                          | 136       | 21.18%  |
| Nvidia                                       | 51        | 7.94%   |
| C-Media Electronics                          | 36        | 5.61%   |
| Promethean Limited                           | 7         | 1.09%   |
| Lenovo                                       | 3         | 0.47%   |
| Apple                                        | 3         | 0.47%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.31%   |
| VIA Technologies                             | 2         | 0.31%   |
| Huawei Technologies                          | 2         | 0.31%   |
| GN Netcom                                    | 2         | 0.31%   |
| ASUSTek Computer                             | 2         | 0.31%   |
| Zhaoxin                                      | 1         | 0.16%   |
| Walmart                                      | 1         | 0.16%   |
| Realtek Semiconductor                        | 1         | 0.16%   |
| MV-SILICON                                   | 1         | 0.16%   |
| Logitech                                     | 1         | 0.16%   |
| JMTek                                        | 1         | 0.16%   |
| Focusrite-Novation                           | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 86        | 11.13%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 78        | 10.09%  |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 55        | 7.12%   |
| Intel Sunrise Point-LP HD Audio                                            | 46        | 5.95%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 33        | 4.27%   |
| C-Media Electronics USB Advanced Audio Device                              | 33        | 4.27%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 29        | 3.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 28        | 3.62%   |
| Intel Comet Lake PCH-LP cAVS                                               | 27        | 3.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 20        | 2.59%   |
| AMD FCH Azalia Controller                                                  | 20        | 2.59%   |
| AMD Radeon High Definition Audio Controller                                | 19        | 2.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 14        | 1.81%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 14        | 1.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 13        | 1.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 13        | 1.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 12        | 1.55%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10        | 1.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 10        | 1.29%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9         | 1.16%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 1.16%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 1.16%   |
| AMD Kabini HDMI/DP Audio                                                   | 9         | 1.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 8         | 1.03%   |
| Promethean Limited Audio                                                   | 7         | 0.91%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 7         | 0.91%   |
| AMD Trinity HDMI Audio Controller                                          | 7         | 0.91%   |
| Nvidia GA107 High Definition Audio Controller                              | 6         | 0.78%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 6         | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6         | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                              | 5         | 0.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 0.65%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 0.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 0.52%   |
| Intel Meteor Lake-P HD Audio Controller                                    | 4         | 0.52%   |
| AMD Wrestler HDMI Audio                                                    | 4         | 0.52%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 0.52%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 4         | 0.52%   |
| AMD High Definition Audio Controller                                       | 4         | 0.52%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 4         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 125       | 27.23%  |
| SK hynix                     | 76        | 16.56%  |
| Micron Technology            | 46        | 10.02%  |
| Unknown                      | 33        | 7.19%   |
| ACPI Digital                 | 32        | 6.97%   |
| Kingston                     | 30        | 6.54%   |
| Crucial                      | 22        | 4.79%   |
| Foxline                      | 20        | 4.36%   |
| A-DATA Technology            | 14        | 3.05%   |
| Unknown                      | 13        | 2.83%   |
| Elpida                       | 6         | 1.31%   |
| Unknown (ABCD)               | 5         | 1.09%   |
| Nanya Technology             | 5         | 1.09%   |
| Ramaxel Technology           | 4         | 0.87%   |
| Patriot                      | 4         | 0.87%   |
| ChangXin Memory              | 4         | 0.87%   |
| Lexar Co Limited             | 3         | 0.65%   |
| AMD                          | 3         | 0.65%   |
| Wodposit                     | 2         | 0.44%   |
| Unknown (0x0B92)             | 1         | 0.22%   |
| Shenzhen WODPOSIT            | 1         | 0.22%   |
| Shenzhen Longsys             | 1         | 0.22%   |
| Shenzhen Giant Hui Kang Tech | 1         | 0.22%   |
| SHARETRONIC                  | 1         | 0.22%   |
| PUSKILL                      | 1         | 0.22%   |
| Kllisre                      | 1         | 0.22%   |
| KingSpec                     | 1         | 0.22%   |
| Kimtigo                      | 1         | 0.22%   |
| GOODRAM                      | 1         | 0.22%   |
| Corsair                      | 1         | 0.22%   |
| Apacer                       | 1         | 0.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| ACPI Digital RAM CMB6-DHDA1BAR08D00 16GB SODIMM DDR4 3200MT/s    | 32        | 6.74%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 13        | 2.74%   |
| Unknown                                                          | 13        | 2.74%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 10        | 2.11%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 9         | 1.89%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 8         | 1.68%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 1.68%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 7         | 1.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 1.26%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 1.26%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.26%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 6         | 1.26%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 1.05%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 5         | 1.05%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 1.05%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 1.05%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 5         | 1.05%   |
| Foxline RAM FL3200D4S22-8G 8GB SODIMM DDR4 3200MT/s              | 5         | 1.05%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 4         | 0.84%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 4         | 0.84%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.84%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.84%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 4         | 0.84%   |
| Crucial RAM CT8G4SFRA266.C4FE 8GB SODIMM DDR4 2667MT/s           | 4         | 0.84%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 3         | 0.63%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.63%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 0.63%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 3         | 0.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.63%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 3         | 0.63%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.63%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 3         | 0.63%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.63%   |
| Samsung RAM M471A1G44CB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.63%   |
| Lexar Co Limited RAM LD4AS008G-3200ST 8GB SODIMM DDR4 3200MT/s   | 3         | 0.63%   |
| Kingston RAM KF3200C20S4/16G 16GB SODIMM DDR4 3200MT/s           | 3         | 0.63%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s           | 3         | 0.63%   |
| Foxline RAM FL2400D4S17S-8G 8GB SODIMM DDR4 2400MT/s             | 3         | 0.63%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 3         | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 247       | 59.95%  |
| DDR3    | 73        | 17.72%  |
| LPDDR4  | 27        | 6.55%   |
| DDR2    | 25        | 6.07%   |
| LPDDR5  | 18        | 4.37%   |
| DDR5    | 10        | 2.43%   |
| SDRAM   | 7         | 1.7%    |
| LPDDR3  | 2         | 0.49%   |
| Unknown | 2         | 0.49%   |
| DDR     | 1         | 0.24%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 357       | 86.65%  |
| Row Of Chips | 54        | 13.11%  |
| DIMM         | 1         | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 196       | 45.27%  |
| 4096  | 91        | 21.02%  |
| 16384 | 71        | 16.4%   |
| 2048  | 50        | 11.55%  |
| 1024  | 15        | 3.46%   |
| 32768 | 6         | 1.39%   |
| 512   | 2         | 0.46%   |
| 6144  | 1         | 0.23%   |
| 1536  | 1         | 0.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 142       | 32.64%  |
| 2667    | 83        | 19.08%  |
| 1600    | 47        | 10.8%   |
| 2400    | 20        | 4.6%    |
| 2133    | 19        | 4.37%   |
| 667     | 14        | 3.22%   |
| 1334    | 13        | 2.99%   |
| 4267    | 11        | 2.53%   |
| Unknown | 11        | 2.53%   |
| 6400    | 10        | 2.3%    |
| 1333    | 10        | 2.3%    |
| 4800    | 7         | 1.61%   |
| 4199    | 6         | 1.38%   |
| 3266    | 6         | 1.38%   |
| 3733    | 5         | 1.15%   |
| 1067    | 5         | 1.15%   |
| 7500    | 4         | 0.92%   |
| 800     | 4         | 0.92%   |
| 8533    | 3         | 0.69%   |
| 5600    | 3         | 0.69%   |
| 8400    | 2         | 0.46%   |
| 2933    | 2         | 0.46%   |
| 1867    | 2         | 0.46%   |
| 8600    | 1         | 0.23%   |
| 2666    | 1         | 0.23%   |
| 2048    | 1         | 0.23%   |
| 533     | 1         | 0.23%   |
| 333     | 1         | 0.23%   |
| 266     | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Kyocera                | 5         | 20%     |
| Canon                  | 5         | 20%     |
| Brother Industries     | 3         | 12%     |
| Xerox                  | 2         | 8%      |
| Samsung Electronics    | 2         | 8%      |
| Ricoh                  | 2         | 8%      |
| Pantum                 | 2         | 8%      |
| Hewlett-Packard        | 2         | 8%      |
| Seiko Epson            | 1         | 4%      |
| Panasonic (Matsushita) | 1         | 4%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Samsung SCX-3400 Series           | 2         | 8%      |
| Pantum M7100DN series             | 2         | 8%      |
| Kyocera FS-1040                   | 2         | 8%      |
| Brother HL-L2300D series          | 2         | 8%      |
| Xerox WorkCentre 5222             | 1         | 4%      |
| Xerox WorkCentre 3220             | 1         | 4%      |
| Seiko Epson EPSON L132 Series     | 1         | 4%      |
| Ricoh RICOH SP 211SU              | 1         | 4%      |
| Ricoh Aficio SP C240DN            | 1         | 4%      |
| Panasonic (Matsushita) KX-MB283RU | 1         | 4%      |
| Kyocera Kyocera ECOSYS M2640idw   | 1         | 4%      |
| Kyocera Kyocera ECOSYS M2040dn    | 1         | 4%      |
| Kyocera ECOSYS M5521cdn           | 1         | 4%      |
| HP LaserJet 400 M401dne           | 1         | 4%      |
| HP LaserJet 1010                  | 1         | 4%      |
| Canon PIXMA MP190                 | 1         | 4%      |
| Canon MF4410                      | 1         | 4%      |
| Canon MF440 Series                | 1         | 4%      |
| Canon MF4010 series               | 1         | 4%      |
| Canon I-SENSYS MF4550d            | 1         | 4%      |
| Brother MFC-L2700DN               | 1         | 4%      |

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
| Chicony Electronics                    | 107       | 21.88%  |
| Bison Electronics                      | 66        | 13.5%   |
| Sunplus Innovation Technology          | 52        | 10.63%  |
| IMC Networks                           | 43        | 8.79%   |
| Cheng Uei Precision Industry (Foxlink) | 35        | 7.16%   |
| Realtek Semiconductor                  | 25        | 5.11%   |
| Quanta                                 | 25        | 5.11%   |
| Microdia                               | 18        | 3.68%   |
| Syntek                                 | 13        | 2.66%   |
| Suyin                                  | 13        | 2.66%   |
| Sonix Technology                       | 12        | 2.45%   |
| Luxvisions Innotech Limited            | 9         | 1.84%   |
| Alcor Micro                            | 7         | 1.43%   |
| Silicon Motion                         | 6         | 1.23%   |
| Apple                                  | 6         | 1.23%   |
| SunplusIT                              | 5         | 1.02%   |
| Lite-On Technology                     | 5         | 1.02%   |
| Z-Star Microelectronics                | 4         | 0.82%   |
| ShineTech                              | 4         | 0.82%   |
| ShineOptics                            | 4         | 0.82%   |
| Unknown                                | 4         | 0.82%   |
| Ricoh                                  | 3         | 0.61%   |
| icSpring                               | 3         | 0.61%   |
| Importek                               | 2         | 0.41%   |
| BRS 2Mp Camera                         | 2         | 0.41%   |
| ALi                                    | 2         | 0.41%   |
| Acer                                   | 2         | 0.41%   |
| Y Media                                | 1         | 0.2%    |
| USB Camera CS                          | 1         | 0.2%    |
| Unknown                                | 1         | 0.2%    |
| Shine-optics                           | 1         | 0.2%    |
| Primax Electronics                     | 1         | 0.2%    |
| OPPO Electronics                       | 1         | 0.2%    |
| OmniVision Technologies                | 1         | 0.2%    |
| KYT-240522-A                           | 1         | 0.2%    |
| Generalplus Technology                 | 1         | 0.2%    |
| DX-240528-H                            | 1         | 0.2%    |
| DX-231115-J                            | 1         | 0.2%    |
| Alpha Imaging Technology               | 1         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Bison BisonCam,NB Pro                                          | 38        | 7.76%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 16        | 3.27%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 15        | 3.06%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                  | 14        | 2.86%   |
| Chicony USB2.0 FHD UVC WebCam                                  | 12        | 2.45%   |
| Chicony HP HD Camera                                           | 12        | 2.45%   |
| Chicony HD Webcam                                              | 12        | 2.45%   |
| Chicony Integrated Camera                                      | 11        | 2.24%   |
| Realtek USB2.0 camera                                          | 10        | 2.04%   |
| Syntek Integrated Camera                                       | 9         | 1.84%   |
| Sunplus Integrated_Webcam_HD                                   | 9         | 1.84%   |
| Sunplus Integrated Camera                                      | 8         | 1.63%   |
| Sunplus BKX Usb FHD Camera                                     | 7         | 1.43%   |
| Chicony USB2.0 Camera                                          | 7         | 1.43%   |
| Sunplus USB 2.0 Camera                                         | 6         | 1.22%   |
| Microdia USB 2.0 Camera                                        | 6         | 1.22%   |
| IMC Networks Integrated Camera                                 | 6         | 1.22%   |
| IMC Networks HD Camera                                         | 6         | 1.22%   |
| Sunplus Asus Webcam                                            | 5         | 1.02%   |
| Quanta ov9734_techfront_camera                                 | 5         | 1.02%   |
| Microdia Integrated_Webcam_HD                                  | 5         | 1.02%   |
| Chicony ACER HD User Facing                                    | 5         | 1.02%   |
| Bison HD Webcam                                                | 5         | 1.02%   |
| Unknown                                                        | 5         | 1.02%   |
| Sunplus USB2.0 camera                                          | 4         | 0.82%   |
| ShineOptics HD Camera                                          | 4         | 0.82%   |
| Realtek Lenovo EasyCamera                                      | 4         | 0.82%   |
| Quanta HP TrueVision HD Camera                                 | 4         | 0.82%   |
| Bison Lenovo EasyCamera                                        | 4         | 0.82%   |
| Bison Integrated RGB Camera                                    | 4         | 0.82%   |
| Apple Built-in iSight                                          | 4         | 0.82%   |
| Syntek Lenovo EasyCamera                                       | 3         | 0.61%   |
| Suyin HP Truevision HD                                         | 3         | 0.61%   |
| Suyin 1.3M HD WebCam                                           | 3         | 0.61%   |
| Sunplus XiaoMi Webcam                                          | 3         | 0.61%   |
| Sunplus Hy FHD B200 Came                                       | 3         | 0.61%   |
| Sonix USB2.0 HD UVC WebCam                                     | 3         | 0.61%   |
| Sonix USB 2.0 Camera                                           | 3         | 0.61%   |
| Ricoh USB2.0 Camera                                            | 3         | 0.61%   |
| Realtek USB Camera                                             | 3         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 21        | 26.25%  |
| Shenzhen Goodix Technology         | 17        | 21.25%  |
| Elan Microelectronics              | 10        | 12.5%   |
| Synaptics                          | 9         | 11.25%  |
| LighTuning Technology              | 7         | 8.75%   |
| Focal-systems.Corp                 | 6         | 7.5%    |
| Upek                               | 3         | 3.75%   |
| HOLTEK                             | 3         | 3.75%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 2.5%    |
| AuthenTec                          | 2         | 2.5%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                             | 17        | 21.25%  |
| Validity Sensors VFS5011 Fingerprint Reader                     | 7         | 8.75%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 6         | 7.5%    |
| Elan ELAN:Fingerprint                                           | 6         | 7.5%    |
| Validity Sensors VFS495 Fingerprint Reader                      | 4         | 5%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 4         | 5%      |
| LighTuning Fingerprint Reader                                   | 4         | 5%      |
| Elan ELAN:ARM-M4                                                | 4         | 5%      |
| Validity Sensors VFS491                                         | 3         | 3.75%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 3         | 3.75%   |
| HOLTEK FocalTech Fingerprint Device                             | 3         | 3.75%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 2         | 2.5%    |
| Validity Sensors Fingerprint scanner                            | 2         | 2.5%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 2.5%    |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 2.5%    |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 1.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 1.25%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 1.25%   |
| Synaptics UWP WBDI Device                                       | 1         | 1.25%   |
| Synaptics  WBDI                                                 | 1         | 1.25%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 1         | 1.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 1.25%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 1.25%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 1         | 1.25%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 1.25%   |
| AuthenTec AES1660 Fingerprint Sensor                            | 1         | 1.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 4         | 50%     |
| O2 Micro                  | 1         | 12.5%   |
| Broadcom                  | 1         | 12.5%   |
| Aladdin R.D.              | 1         | 12.5%   |
| Aladdin Knowledge Systems | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader  | 4         | 50%     |
| O2 Micro OZ776 CCID Smartcard Reader | 1         | 12.5%   |
| Broadcom 5880                        | 1         | 12.5%   |
| Aladdin R.D. JaCarta                 | 1         | 12.5%   |
| Aladdin Knowledge Systems Token JC   | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 376       | 70.81%  |
| 1     | 122       | 22.98%  |
| 2     | 27        | 5.08%   |
| 3     | 4         | 0.75%   |
| 4     | 2         | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 80        | 43.01%  |
| Graphics card            | 35        | 18.82%  |
| Net/wireless             | 18        | 9.68%   |
| Multimedia controller    | 18        | 9.68%   |
| Communication controller | 10        | 5.38%   |
| Chipcard                 | 6         | 3.23%   |
| Bluetooth                | 5         | 2.69%   |
| Net/ethernet             | 4         | 2.15%   |
| Camera                   | 4         | 2.15%   |
| Sound                    | 3         | 1.61%   |
| Flash memory             | 2         | 1.08%   |
| Card reader              | 1         | 0.54%   |

