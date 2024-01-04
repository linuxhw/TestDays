Linux in Italy - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

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

Total: 7342

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Sony          | SVE1713X1EB                 | [6c3167a5a7](https://linux-hardware.org/?probe=6c3167a5a7) | Jan 02, 2024 |
| HP            | Pavilion 15                 | [277c4aa7d6](https://linux-hardware.org/?probe=277c4aa7d6) | Jan 02, 2024 |
| Acer          | Nitro AN515-58              | [b822b77797](https://linux-hardware.org/?probe=b822b77797) | Jan 02, 2024 |
| Sony          | VGN-AR51SU                  | [ad09db7b69](https://linux-hardware.org/?probe=ad09db7b69) | Jan 01, 2024 |
| Sony          | VGN-AR51SU                  | [01e1a67d40](https://linux-hardware.org/?probe=01e1a67d40) | Jan 01, 2024 |
| Acer          | Aspire A517-52G             | [fb86c6f71c](https://linux-hardware.org/?probe=fb86c6f71c) | Jan 01, 2024 |
| Sony          | SVE1713X1EB                 | [f9081b680a](https://linux-hardware.org/?probe=f9081b680a) | Jan 01, 2024 |
| Sony          | VGN-NW11S_S                 | [6d47430c42](https://linux-hardware.org/?probe=6d47430c42) | Jan 01, 2024 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [0120368c3a](https://linux-hardware.org/?probe=0120368c3a) | Jan 01, 2024 |
| Sony          | VGN-NW11S_S                 | [e898dd413e](https://linux-hardware.org/?probe=e898dd413e) | Jan 01, 2024 |
| Apple         | MacBookAir9,1               | [5dde4deb12](https://linux-hardware.org/?probe=5dde4deb12) | Dec 31, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [ec8f742a7f](https://linux-hardware.org/?probe=ec8f742a7f) | Dec 31, 2023 |
| Dell          | Latitude E4310              | [10397fd191](https://linux-hardware.org/?probe=10397fd191) | Dec 31, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [1f44330bcf](https://linux-hardware.org/?probe=1f44330bcf) | Dec 31, 2023 |
| HP            | OMEN by Laptop              | [8b1ac4e80c](https://linux-hardware.org/?probe=8b1ac4e80c) | Dec 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [d975ab384e](https://linux-hardware.org/?probe=d975ab384e) | Dec 31, 2023 |
| ASUSTek       | PRIME B360M-A               | [42b25d8ac5](https://linux-hardware.org/?probe=42b25d8ac5) | Dec 30, 2023 |
| ASUSTek       | PRIME X570-P                | [12b2d456ed](https://linux-hardware.org/?probe=12b2d456ed) | Dec 30, 2023 |
| Chuwi         | HeroBook Pro                | [7528cb1c24](https://linux-hardware.org/?probe=7528cb1c24) | Dec 30, 2023 |
| HP            | ProBook 440 G6              | [14623af544](https://linux-hardware.org/?probe=14623af544) | Dec 30, 2023 |
| Chuwi         | GemiBook                    | [3e5282eb93](https://linux-hardware.org/?probe=3e5282eb93) | Dec 30, 2023 |
| ASUSTek       | PRIME X570-P                | [596a41673a](https://linux-hardware.org/?probe=596a41673a) | Dec 30, 2023 |
| Samsung       | RC530/RC730                 | [866c256904](https://linux-hardware.org/?probe=866c256904) | Dec 30, 2023 |
| HP            | ProBook 6450b               | [ce6d3d0e7f](https://linux-hardware.org/?probe=ce6d3d0e7f) | Dec 30, 2023 |
| HP            | ProBook 6450b               | [f2128c8e8a](https://linux-hardware.org/?probe=f2128c8e8a) | Dec 30, 2023 |
| HUAWEI        | KLVL-WXX9                   | [f8aeb2c6c3](https://linux-hardware.org/?probe=f8aeb2c6c3) | Dec 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [96662ed691](https://linux-hardware.org/?probe=96662ed691) | Dec 30, 2023 |
| HP            | Pavilion 15                 | [50b4c1504f](https://linux-hardware.org/?probe=50b4c1504f) | Dec 29, 2023 |
| Chuwi         | HeroBook Pro                | [f071a372c0](https://linux-hardware.org/?probe=f071a372c0) | Dec 29, 2023 |
| Dell          | Latitude 5580               | [3079edcb81](https://linux-hardware.org/?probe=3079edcb81) | Dec 29, 2023 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | [afd9883450](https://linux-hardware.org/?probe=afd9883450) | Dec 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [55340871af](https://linux-hardware.org/?probe=55340871af) | Dec 29, 2023 |
| Sony          | VGN-CR21S_W                 | [732175d0f6](https://linux-hardware.org/?probe=732175d0f6) | Dec 29, 2023 |
| Sony          | VGN-FW21E                   | [52ff803e03](https://linux-hardware.org/?probe=52ff803e03) | Dec 29, 2023 |
| Acer          | Aspire E5-573G              | [0c4a68d81f](https://linux-hardware.org/?probe=0c4a68d81f) | Dec 29, 2023 |
| Acer          | Aspire E5-573G              | [210403cf9d](https://linux-hardware.org/?probe=210403cf9d) | Dec 29, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [751429a259](https://linux-hardware.org/?probe=751429a259) | Dec 29, 2023 |
| Dell          | Inspiron 7348               | [a55c6eef41](https://linux-hardware.org/?probe=a55c6eef41) | Dec 29, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [8e46844acc](https://linux-hardware.org/?probe=8e46844acc) | Dec 29, 2023 |
| Samsung       | RC530/RC730                 | [db448e5732](https://linux-hardware.org/?probe=db448e5732) | Dec 29, 2023 |
| Notebook      | NS5x_NS7xAU                 | [d520b97118](https://linux-hardware.org/?probe=d520b97118) | Dec 29, 2023 |
| Dell          | XPS 13 9370                 | [f2d5cce82a](https://linux-hardware.org/?probe=f2d5cce82a) | Dec 29, 2023 |
| Lenovo        | V145-15AST 81MT             | [fa95062029](https://linux-hardware.org/?probe=fa95062029) | Dec 28, 2023 |
| HP            | Pavilion 15                 | [da5644171f](https://linux-hardware.org/?probe=da5644171f) | Dec 28, 2023 |
| Unknown       | Unknown                     | [89a77455e5](https://linux-hardware.org/?probe=89a77455e5) | Dec 28, 2023 |
| Chuwi         | GemiBook                    | [15199d7550](https://linux-hardware.org/?probe=15199d7550) | Dec 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [5b2dd63a52](https://linux-hardware.org/?probe=5b2dd63a52) | Dec 28, 2023 |
| Fujitsu       | LIFEBOOK E734               | [2265b1d34f](https://linux-hardware.org/?probe=2265b1d34f) | Dec 28, 2023 |
| Unknown       | Unknown                     | [7c86c2f5dc](https://linux-hardware.org/?probe=7c86c2f5dc) | Dec 28, 2023 |
| Acer          | Aspire V5-123               | [4220993372](https://linux-hardware.org/?probe=4220993372) | Dec 28, 2023 |
| HP            | Notebook                    | [5b3e4ada9c](https://linux-hardware.org/?probe=5b3e4ada9c) | Dec 28, 2023 |
| Acer          | Aspire E5-573G              | [323f661113](https://linux-hardware.org/?probe=323f661113) | Dec 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [40c72fd8c2](https://linux-hardware.org/?probe=40c72fd8c2) | Dec 27, 2023 |
| Lenovo        | G50-45 80E3                 | [90e55e787b](https://linux-hardware.org/?probe=90e55e787b) | Dec 27, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [84bc2c3915](https://linux-hardware.org/?probe=84bc2c3915) | Dec 27, 2023 |
| Dell          | Latitude 3520               | [b5802159c7](https://linux-hardware.org/?probe=b5802159c7) | Dec 27, 2023 |
| HP            | 255 G7 Notebook PC          | [8b217c5f35](https://linux-hardware.org/?probe=8b217c5f35) | Dec 27, 2023 |
| MSI           | Modern 15 B7M               | [2c7f48c9ad](https://linux-hardware.org/?probe=2c7f48c9ad) | Dec 27, 2023 |
| MSI           | GS40 6QE Phantom            | [2946f9add8](https://linux-hardware.org/?probe=2946f9add8) | Dec 26, 2023 |
| Acer          | Aspire 5739G                | [6b4237a1ea](https://linux-hardware.org/?probe=6b4237a1ea) | Dec 26, 2023 |
| Acer          | Aspire 5739G                | [408e19e1f2](https://linux-hardware.org/?probe=408e19e1f2) | Dec 26, 2023 |
| HP            | Compaq nx7400 (RH609ES#A... | [6a6b1d3722](https://linux-hardware.org/?probe=6a6b1d3722) | Dec 26, 2023 |
| Chuwi         | GemiBook Pro                | [0fceb23d42](https://linux-hardware.org/?probe=0fceb23d42) | Dec 25, 2023 |
| HP            | 250 G8 Notebook PC          | [df812b1171](https://linux-hardware.org/?probe=df812b1171) | Dec 25, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [66915e859e](https://linux-hardware.org/?probe=66915e859e) | Dec 25, 2023 |
| HP            | Laptop 14s-fq0xxx           | [00a9997bfc](https://linux-hardware.org/?probe=00a9997bfc) | Dec 25, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [54961dd296](https://linux-hardware.org/?probe=54961dd296) | Dec 25, 2023 |
| HP            | Pavilion dv6                | [e9120b7c4e](https://linux-hardware.org/?probe=e9120b7c4e) | Dec 24, 2023 |
| HP            | Pavilion dv6                | [b3b2c1f621](https://linux-hardware.org/?probe=b3b2c1f621) | Dec 24, 2023 |
| Acer          | Aspire E5-571G              | [5004570f44](https://linux-hardware.org/?probe=5004570f44) | Dec 24, 2023 |
| Acer          | Aspire E5-571G              | [b62ffffcdb](https://linux-hardware.org/?probe=b62ffffcdb) | Dec 24, 2023 |
| TULPAR        | A5 V20.3                    | [c1abfa26d5](https://linux-hardware.org/?probe=c1abfa26d5) | Dec 24, 2023 |
| PC Special... | GK7NP5R                     | [1d97edcad7](https://linux-hardware.org/?probe=1d97edcad7) | Dec 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [40ba77bcb8](https://linux-hardware.org/?probe=40ba77bcb8) | Dec 23, 2023 |
| TULPAR        | A5 V20.3                    | [83c6679958](https://linux-hardware.org/?probe=83c6679958) | Dec 23, 2023 |
| Acer          | TravelMate 5730             | [69571c0b91](https://linux-hardware.org/?probe=69571c0b91) | Dec 23, 2023 |
| Apple         | MacBookAir6,1               | [0275987230](https://linux-hardware.org/?probe=0275987230) | Dec 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [e1225d2a37](https://linux-hardware.org/?probe=e1225d2a37) | Dec 22, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [60690b9d12](https://linux-hardware.org/?probe=60690b9d12) | Dec 22, 2023 |
| ASUSTek       | N551VW                      | [f73a190483](https://linux-hardware.org/?probe=f73a190483) | Dec 22, 2023 |
| ASUSTek       | N551VW                      | [467015083e](https://linux-hardware.org/?probe=467015083e) | Dec 22, 2023 |
| Dell          | Latitude 5501               | [0b6206153c](https://linux-hardware.org/?probe=0b6206153c) | Dec 22, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [db6db43604](https://linux-hardware.org/?probe=db6db43604) | Dec 22, 2023 |
| HP            | Notebook                    | [7541fcf0c8](https://linux-hardware.org/?probe=7541fcf0c8) | Dec 22, 2023 |
| Lenovo        | ThinkPad T490 20N3S5GP12    | [093906d110](https://linux-hardware.org/?probe=093906d110) | Dec 21, 2023 |
| Dell          | XPS 15 9520                 | [9fea6c876a](https://linux-hardware.org/?probe=9fea6c876a) | Dec 21, 2023 |
| ASUSTek       | X555LAB                     | [8a8a35c616](https://linux-hardware.org/?probe=8a8a35c616) | Dec 21, 2023 |
| Sony          | SVE1713X1EB                 | [dd67c36ae3](https://linux-hardware.org/?probe=dd67c36ae3) | Dec 21, 2023 |
| MSI           | Modern 15 B7M               | [77760018a7](https://linux-hardware.org/?probe=77760018a7) | Dec 21, 2023 |
| ASUSTek       | X550LD                      | [ebaf3f3e71](https://linux-hardware.org/?probe=ebaf3f3e71) | Dec 21, 2023 |
| Lenovo        | Yoga 2 11 20332             | [16a8e6f875](https://linux-hardware.org/?probe=16a8e6f875) | Dec 21, 2023 |
| Acer          | Swift SF314-59              | [13432c28a6](https://linux-hardware.org/?probe=13432c28a6) | Dec 21, 2023 |
| Acer          | Swift SF314-59              | [0eb55bee7d](https://linux-hardware.org/?probe=0eb55bee7d) | Dec 20, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [1c3113c9b9](https://linux-hardware.org/?probe=1c3113c9b9) | Dec 20, 2023 |
| ASUSTek       | X580VD                      | [18f5888ad5](https://linux-hardware.org/?probe=18f5888ad5) | Dec 20, 2023 |
| Lenovo        | IdeaPad S540-14IML 81NF     | [942da4e853](https://linux-hardware.org/?probe=942da4e853) | Dec 20, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [2785a8b9c6](https://linux-hardware.org/?probe=2785a8b9c6) | Dec 20, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [398a10f8ce](https://linux-hardware.org/?probe=398a10f8ce) | Dec 20, 2023 |
| MSI           | Prestige 14Evo A12M         | [23e7499358](https://linux-hardware.org/?probe=23e7499358) | Dec 20, 2023 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [06984b497c](https://linux-hardware.org/?probe=06984b497c) | Dec 20, 2023 |
| Lenovo        | ThinkPad S430 336457G       | [4acd70fc9f](https://linux-hardware.org/?probe=4acd70fc9f) | Dec 19, 2023 |
| Google        | Treeya                      | [b6541ef594](https://linux-hardware.org/?probe=b6541ef594) | Dec 19, 2023 |
| Dell          | XPS 13 9380                 | [1038e25caf](https://linux-hardware.org/?probe=1038e25caf) | Dec 19, 2023 |
| HP            | 255 G1                      | [42faa8c263](https://linux-hardware.org/?probe=42faa8c263) | Dec 18, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [cb94175bab](https://linux-hardware.org/?probe=cb94175bab) | Dec 17, 2023 |
| ASUSTek       | X550LD                      | [d1dcdfda30](https://linux-hardware.org/?probe=d1dcdfda30) | Dec 17, 2023 |
| Samsung       | 750XDA                      | [bdaba42db8](https://linux-hardware.org/?probe=bdaba42db8) | Dec 17, 2023 |
| HP            | Laptop 15-dw0xxx            | [185314f313](https://linux-hardware.org/?probe=185314f313) | Dec 17, 2023 |
| Acer          | Aspire 5920G                | [40545204ea](https://linux-hardware.org/?probe=40545204ea) | Dec 17, 2023 |
| Acer          | Aspire 5920G                | [4ace5aeebe](https://linux-hardware.org/?probe=4ace5aeebe) | Dec 17, 2023 |
| HP            | Laptop 15-dw0xxx            | [87d3b447bb](https://linux-hardware.org/?probe=87d3b447bb) | Dec 17, 2023 |
| Acer          | Swift SF314-43              | [7ff498fc83](https://linux-hardware.org/?probe=7ff498fc83) | Dec 17, 2023 |
| HP            | Notebook                    | [09981b3a71](https://linux-hardware.org/?probe=09981b3a71) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [78a88bfe8c](https://linux-hardware.org/?probe=78a88bfe8c) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [8833b0a058](https://linux-hardware.org/?probe=8833b0a058) | Dec 17, 2023 |
| Google        | Droid                       | [f08b6f3c68](https://linux-hardware.org/?probe=f08b6f3c68) | Dec 17, 2023 |
| ASUSTek       | X550LD                      | [492e654dfb](https://linux-hardware.org/?probe=492e654dfb) | Dec 17, 2023 |
| ASUSTek       | K61IC                       | [1442626988](https://linux-hardware.org/?probe=1442626988) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [7162b25b98](https://linux-hardware.org/?probe=7162b25b98) | Dec 16, 2023 |
| HP            | 250 G8 Notebook PC          | [6e6dfdc457](https://linux-hardware.org/?probe=6e6dfdc457) | Dec 16, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [2c4dba512d](https://linux-hardware.org/?probe=2c4dba512d) | Dec 16, 2023 |
| HP            | Notebook                    | [4973d42380](https://linux-hardware.org/?probe=4973d42380) | Dec 16, 2023 |
| HP            | Compaq CQ58                 | [7567b51bda](https://linux-hardware.org/?probe=7567b51bda) | Dec 16, 2023 |
| HP            | Notebook                    | [a960b17c37](https://linux-hardware.org/?probe=a960b17c37) | Dec 16, 2023 |
| ASUSTek       | X540LJ                      | [281c56510a](https://linux-hardware.org/?probe=281c56510a) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e5916c58ec](https://linux-hardware.org/?probe=e5916c58ec) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [37495b67c9](https://linux-hardware.org/?probe=37495b67c9) | Dec 15, 2023 |
| Acer          | Swift SFX14-41G             | [49d4000148](https://linux-hardware.org/?probe=49d4000148) | Dec 15, 2023 |
| HP            | Pavilion 15                 | [166f55ae0b](https://linux-hardware.org/?probe=166f55ae0b) | Dec 15, 2023 |
| HP            | ProBook 6450b               | [f63d5aa0f6](https://linux-hardware.org/?probe=f63d5aa0f6) | Dec 14, 2023 |
| HP            | ProBook 6450b               | [1a762fe797](https://linux-hardware.org/?probe=1a762fe797) | Dec 14, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [8dd696472d](https://linux-hardware.org/?probe=8dd696472d) | Dec 14, 2023 |
| ASUSTek       | K52Jc                       | [dfa5dc9cd9](https://linux-hardware.org/?probe=dfa5dc9cd9) | Dec 14, 2023 |
| Medion        | E16401                      | [0c81bbcb2b](https://linux-hardware.org/?probe=0c81bbcb2b) | Dec 14, 2023 |
| HP            | Notebook                    | [ac92e1373d](https://linux-hardware.org/?probe=ac92e1373d) | Dec 14, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [56b77e5a7d](https://linux-hardware.org/?probe=56b77e5a7d) | Dec 14, 2023 |
| HUAWEI        | MACHD-WXX9                  | [35a6370b07](https://linux-hardware.org/?probe=35a6370b07) | Dec 14, 2023 |
| HP            | 15                          | [2343c72691](https://linux-hardware.org/?probe=2343c72691) | Dec 13, 2023 |
| HP            | Laptop 17-by4xxx            | [0c728e7b27](https://linux-hardware.org/?probe=0c728e7b27) | Dec 13, 2023 |
| HUAWEI        | HKD-WXX                     | [c6a0ea6b45](https://linux-hardware.org/?probe=c6a0ea6b45) | Dec 13, 2023 |
| HP            | Laptop 15-bs1xx             | [1785db3e7b](https://linux-hardware.org/?probe=1785db3e7b) | Dec 13, 2023 |
| Acer          | Swift SF314-43              | [6e8b956266](https://linux-hardware.org/?probe=6e8b956266) | Dec 13, 2023 |
| HUAWEI        | HKD-WXX                     | [b0c03a26ce](https://linux-hardware.org/?probe=b0c03a26ce) | Dec 13, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6a497408c3](https://linux-hardware.org/?probe=6a497408c3) | Dec 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [6407db19a5](https://linux-hardware.org/?probe=6407db19a5) | Dec 13, 2023 |
| Lenovo        | G50-45 80E3                 | [cfa115323d](https://linux-hardware.org/?probe=cfa115323d) | Dec 13, 2023 |
| Valve         | Galileo                     | [d6ea0e047a](https://linux-hardware.org/?probe=d6ea0e047a) | Dec 13, 2023 |
| HP            | 15                          | [9c4fb8f41d](https://linux-hardware.org/?probe=9c4fb8f41d) | Dec 12, 2023 |
| Lenovo        | ThinkPad X270 20HMS0TD00    | [e9df2cf93b](https://linux-hardware.org/?probe=e9df2cf93b) | Dec 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [4cffef33b7](https://linux-hardware.org/?probe=4cffef33b7) | Dec 12, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | [774925ed25](https://linux-hardware.org/?probe=774925ed25) | Dec 12, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a128efcd01](https://linux-hardware.org/?probe=a128efcd01) | Dec 12, 2023 |
| HUAWEI        | KLVC-WXX9                   | [3e8d09cc67](https://linux-hardware.org/?probe=3e8d09cc67) | Dec 12, 2023 |
| Acer          | TravelMate 5720             | [27cbfe44c9](https://linux-hardware.org/?probe=27cbfe44c9) | Dec 12, 2023 |
| ASUSTek       | X550LD                      | [1e1b5e9985](https://linux-hardware.org/?probe=1e1b5e9985) | Dec 12, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [4d416a35fa](https://linux-hardware.org/?probe=4d416a35fa) | Dec 12, 2023 |
| Lenovo        | V15-IIL 82C5                | [a9d7c866c5](https://linux-hardware.org/?probe=a9d7c866c5) | Dec 12, 2023 |
| HUAWEI        | BOD-WXX9                    | [c12ada5b78](https://linux-hardware.org/?probe=c12ada5b78) | Dec 12, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [48475b71d7](https://linux-hardware.org/?probe=48475b71d7) | Dec 11, 2023 |
| HP            | 255 G5                      | [9001fa872f](https://linux-hardware.org/?probe=9001fa872f) | Dec 11, 2023 |
| HP            | 255 G5                      | [d7df759d96](https://linux-hardware.org/?probe=d7df759d96) | Dec 11, 2023 |
| Packard Be... | EasyNote MH36               | [9607b32c37](https://linux-hardware.org/?probe=9607b32c37) | Dec 11, 2023 |
| MSI           | Modern 15 B7M               | [d4c74075be](https://linux-hardware.org/?probe=d4c74075be) | Dec 11, 2023 |
| Acer          | Aspire 5750                 | [584a9a153e](https://linux-hardware.org/?probe=584a9a153e) | Dec 11, 2023 |
| Acer          | Aspire E5-571G              | [30c8f1f622](https://linux-hardware.org/?probe=30c8f1f622) | Dec 11, 2023 |
| ASUSTek       | 1005HA                      | [b9760dcf5a](https://linux-hardware.org/?probe=b9760dcf5a) | Dec 10, 2023 |
| Dell          | XPS 13 9370                 | [201fa157d6](https://linux-hardware.org/?probe=201fa157d6) | Dec 10, 2023 |
| ASUSTek       | X505BP                      | [408ad7dd06](https://linux-hardware.org/?probe=408ad7dd06) | Dec 10, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [58ad170a68](https://linux-hardware.org/?probe=58ad170a68) | Dec 10, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [bc8d773d9d](https://linux-hardware.org/?probe=bc8d773d9d) | Dec 10, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [04e25c9660](https://linux-hardware.org/?probe=04e25c9660) | Dec 10, 2023 |
| ASUSTek       | P552LA                      | [cbe77e84b7](https://linux-hardware.org/?probe=cbe77e84b7) | Dec 09, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [5e6fc96a08](https://linux-hardware.org/?probe=5e6fc96a08) | Dec 09, 2023 |
| ASUSTek       | S551LN                      | [4684efbcaa](https://linux-hardware.org/?probe=4684efbcaa) | Dec 09, 2023 |
| Acer          | AOD270                      | [b5729a6428](https://linux-hardware.org/?probe=b5729a6428) | Dec 09, 2023 |
| MSI           | Prestige 14 A10SC           | [85d6d037cc](https://linux-hardware.org/?probe=85d6d037cc) | Dec 09, 2023 |
| Dell          | Latitude 7490               | [ad002286ac](https://linux-hardware.org/?probe=ad002286ac) | Dec 09, 2023 |
| Valve         | Jupiter                     | [f61425f9af](https://linux-hardware.org/?probe=f61425f9af) | Dec 09, 2023 |
| ASUSTek       | S551LN                      | [47aafe0845](https://linux-hardware.org/?probe=47aafe0845) | Dec 08, 2023 |
| Valve         | Jupiter                     | [afd88ac5ea](https://linux-hardware.org/?probe=afd88ac5ea) | Dec 08, 2023 |
| HP            | Compaq 610                  | [6104f16206](https://linux-hardware.org/?probe=6104f16206) | Dec 07, 2023 |
| Lenovo        | ThinkBook 14 G6 IRL 21KG    | [f7511ff0d0](https://linux-hardware.org/?probe=f7511ff0d0) | Dec 07, 2023 |
| HP            | 255 G7 Notebook PC          | [a39b24be90](https://linux-hardware.org/?probe=a39b24be90) | Dec 07, 2023 |
| HP            | 255 G7 Notebook PC          | [7da432cd55](https://linux-hardware.org/?probe=7da432cd55) | Dec 07, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [7606deffc4](https://linux-hardware.org/?probe=7606deffc4) | Dec 07, 2023 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [96ab8b0be8](https://linux-hardware.org/?probe=96ab8b0be8) | Dec 07, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [8ec5586df3](https://linux-hardware.org/?probe=8ec5586df3) | Dec 07, 2023 |
| HP            | ProBook 650 G1              | [52c0a2e6fa](https://linux-hardware.org/?probe=52c0a2e6fa) | Dec 07, 2023 |
| ASUSTek       | Zenbook S 13 UX5304VA_UX... | [b539c714c4](https://linux-hardware.org/?probe=b539c714c4) | Dec 07, 2023 |
| ASUSTek       | P553UA                      | [4c19d8a91e](https://linux-hardware.org/?probe=4c19d8a91e) | Dec 06, 2023 |
| ASUSTek       | GL702VSK                    | [d8547acd71](https://linux-hardware.org/?probe=d8547acd71) | Dec 06, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [a0391f219b](https://linux-hardware.org/?probe=a0391f219b) | Dec 06, 2023 |
| ASUSTek       | K52JB                       | [2edc689735](https://linux-hardware.org/?probe=2edc689735) | Dec 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [7376c1f4cf](https://linux-hardware.org/?probe=7376c1f4cf) | Dec 06, 2023 |
| Acer          | Aspire E5-772G              | [1be5bb95d1](https://linux-hardware.org/?probe=1be5bb95d1) | Dec 05, 2023 |
| Acer          | TravelMate P414-51          | [bc31600bfa](https://linux-hardware.org/?probe=bc31600bfa) | Dec 05, 2023 |
| HP            | EliteBook 850 G5            | [aae20908c5](https://linux-hardware.org/?probe=aae20908c5) | Dec 05, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [0d7f21475d](https://linux-hardware.org/?probe=0d7f21475d) | Dec 05, 2023 |
| HP            | ProBook 650 G1              | [06fe795e93](https://linux-hardware.org/?probe=06fe795e93) | Dec 05, 2023 |
| ASUSTek       | GL702VSK                    | [20e6076fd3](https://linux-hardware.org/?probe=20e6076fd3) | Dec 05, 2023 |
| Lenovo        | ThinkPad X280 20KFS0ND00    | [b95db311ed](https://linux-hardware.org/?probe=b95db311ed) | Dec 04, 2023 |
| Acer          | AOD270                      | [868ee5d423](https://linux-hardware.org/?probe=868ee5d423) | Dec 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [3965451e6d](https://linux-hardware.org/?probe=3965451e6d) | Dec 04, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [d91e8dc1a8](https://linux-hardware.org/?probe=d91e8dc1a8) | Dec 04, 2023 |
| Dell          | XPS 15 9550                 | [b24c23dfd1](https://linux-hardware.org/?probe=b24c23dfd1) | Dec 04, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | [9acc9cef23](https://linux-hardware.org/?probe=9acc9cef23) | Dec 04, 2023 |
| Sony          | SVE1713X1EB                 | [3c8e9b9cc4](https://linux-hardware.org/?probe=3c8e9b9cc4) | Dec 04, 2023 |
| Dell          | XPS 15 9530                 | [e6d446fcd3](https://linux-hardware.org/?probe=e6d446fcd3) | Dec 04, 2023 |
| HP            | Notebook                    | [f347c4437d](https://linux-hardware.org/?probe=f347c4437d) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [b1fdfbc998](https://linux-hardware.org/?probe=b1fdfbc998) | Dec 03, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [0f16293fea](https://linux-hardware.org/?probe=0f16293fea) | Dec 03, 2023 |
| HP            | ProBook 470 G5              | [d12c9b1f20](https://linux-hardware.org/?probe=d12c9b1f20) | Dec 03, 2023 |
| Acer          | Nitro AN515-57              | [1f8c488e82](https://linux-hardware.org/?probe=1f8c488e82) | Dec 03, 2023 |
| HP            | 255 G8 Notebook PC          | [2afc97f78a](https://linux-hardware.org/?probe=2afc97f78a) | Dec 03, 2023 |
| HP            | ZBook 17 G2                 | [e1edd54ac3](https://linux-hardware.org/?probe=e1edd54ac3) | Dec 03, 2023 |
| Jumper        | EZbook                      | [54cf2bf1d4](https://linux-hardware.org/?probe=54cf2bf1d4) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [203357a4dd](https://linux-hardware.org/?probe=203357a4dd) | Dec 03, 2023 |
| HP            | Laptop 15-dw0xxx            | [288b6a2f75](https://linux-hardware.org/?probe=288b6a2f75) | Dec 02, 2023 |
| ASUSTek       | S551LN                      | [1c843db61c](https://linux-hardware.org/?probe=1c843db61c) | Dec 02, 2023 |
| Lenovo        | ThinkPad E15 20RD0019IX     | [5d53fe03da](https://linux-hardware.org/?probe=5d53fe03da) | Dec 02, 2023 |
| HP            | Notebook                    | [399699d1ce](https://linux-hardware.org/?probe=399699d1ce) | Dec 02, 2023 |
| HP            | Notebook                    | [0a554c91b1](https://linux-hardware.org/?probe=0a554c91b1) | Dec 01, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | [bf9f891fe4](https://linux-hardware.org/?probe=bf9f891fe4) | Dec 01, 2023 |
| Acer          | Aspire 5732Z                | [f79a825fcd](https://linux-hardware.org/?probe=f79a825fcd) | Dec 01, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [22263182fb](https://linux-hardware.org/?probe=22263182fb) | Dec 01, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [f17a1eb208](https://linux-hardware.org/?probe=f17a1eb208) | Dec 01, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [100228341f](https://linux-hardware.org/?probe=100228341f) | Dec 01, 2023 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | [f98f84669d](https://linux-hardware.org/?probe=f98f84669d) | Dec 01, 2023 |
| Toshiba       | Satellite L755              | [511b79d4dc](https://linux-hardware.org/?probe=511b79d4dc) | Nov 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [4ba2fc285f](https://linux-hardware.org/?probe=4ba2fc285f) | Nov 30, 2023 |
| HP            | Laptop 15-dw0xxx            | [e9e1177170](https://linux-hardware.org/?probe=e9e1177170) | Nov 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [0f9a06cc9f](https://linux-hardware.org/?probe=0f9a06cc9f) | Nov 30, 2023 |
| Apple         | MacBook4,1                  | [72fc73581b](https://linux-hardware.org/?probe=72fc73581b) | Nov 30, 2023 |
| HP            | ProBook 4540s               | [e1e15771c1](https://linux-hardware.org/?probe=e1e15771c1) | Nov 30, 2023 |
| HP            | Notebook                    | [93464a0904](https://linux-hardware.org/?probe=93464a0904) | Nov 30, 2023 |
| Apple         | MacBookPro5,4               | [bc9394652a](https://linux-hardware.org/?probe=bc9394652a) | Nov 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [e0e3a6f229](https://linux-hardware.org/?probe=e0e3a6f229) | Nov 30, 2023 |
| HP            | Pavilion dv6000 (RY647EA... | [9940416812](https://linux-hardware.org/?probe=9940416812) | Nov 30, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B5602CBA... | [0c08316018](https://linux-hardware.org/?probe=0c08316018) | Nov 29, 2023 |
| Apple         | MacBook4,1                  | [ea63175ae6](https://linux-hardware.org/?probe=ea63175ae6) | Nov 29, 2023 |
| HP            | 255 G8 Notebook PC          | [be0c718878](https://linux-hardware.org/?probe=be0c718878) | Nov 29, 2023 |
| HUAWEI        | BOM-WXX9                    | [616b02b268](https://linux-hardware.org/?probe=616b02b268) | Nov 29, 2023 |
| Olivetti      | OLIBOOK P35-XXXAEU          | [6b83c6bd43](https://linux-hardware.org/?probe=6b83c6bd43) | Nov 29, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZI... | [f7d5f758c6](https://linux-hardware.org/?probe=f7d5f758c6) | Nov 29, 2023 |
| HP            | Compaq 6730s                | [ff2ae39e03](https://linux-hardware.org/?probe=ff2ae39e03) | Nov 29, 2023 |
| ASUSTek       | X555LD                      | [363701a47c](https://linux-hardware.org/?probe=363701a47c) | Nov 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [31b8894b55](https://linux-hardware.org/?probe=31b8894b55) | Nov 29, 2023 |
| HP            | Compaq 610                  | [f0022a2c56](https://linux-hardware.org/?probe=f0022a2c56) | Nov 28, 2023 |
| Sony          | VPCEL1E1E                   | [9c88ceb0b0](https://linux-hardware.org/?probe=9c88ceb0b0) | Nov 28, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [21451de65a](https://linux-hardware.org/?probe=21451de65a) | Nov 28, 2023 |
| Dell          | Vostro 3420                 | [95a9c16f88](https://linux-hardware.org/?probe=95a9c16f88) | Nov 28, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [1f830eb37e](https://linux-hardware.org/?probe=1f830eb37e) | Nov 27, 2023 |
| HP            | 250 G3                      | [4bb11e9f60](https://linux-hardware.org/?probe=4bb11e9f60) | Nov 27, 2023 |
| ASUSTek       | ROG Zephyrus G16 GU603ZI... | [399bf1aa5b](https://linux-hardware.org/?probe=399bf1aa5b) | Nov 27, 2023 |
| ASUSTek       | F52Q                        | [705aa34dce](https://linux-hardware.org/?probe=705aa34dce) | Nov 27, 2023 |
| ASUSTek       | F52Q                        | [569db41ca1](https://linux-hardware.org/?probe=569db41ca1) | Nov 27, 2023 |
| HP            | 250 G3                      | [275991de58](https://linux-hardware.org/?probe=275991de58) | Nov 27, 2023 |
| HP            | 255 G8 Notebook PC          | [3342bb8661](https://linux-hardware.org/?probe=3342bb8661) | Nov 27, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [8474959120](https://linux-hardware.org/?probe=8474959120) | Nov 26, 2023 |
| Acer          | Aspire ES1-520              | [235bae508c](https://linux-hardware.org/?probe=235bae508c) | Nov 26, 2023 |
| ASUSTek       | K52JB                       | [c314753a7c](https://linux-hardware.org/?probe=c314753a7c) | Nov 26, 2023 |
| HP            | 630                         | [cd7a4c040d](https://linux-hardware.org/?probe=cd7a4c040d) | Nov 26, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [351dde4845](https://linux-hardware.org/?probe=351dde4845) | Nov 26, 2023 |
| HP            | 250 G1                      | [ac68122660](https://linux-hardware.org/?probe=ac68122660) | Nov 26, 2023 |
| HP            | Laptop 15s-fq2xxx           | [f0b4d1d85c](https://linux-hardware.org/?probe=f0b4d1d85c) | Nov 26, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [7ea3637c4f](https://linux-hardware.org/?probe=7ea3637c4f) | Nov 26, 2023 |
| MSI           | PS63 Modern 8RC             | [d647ccba36](https://linux-hardware.org/?probe=d647ccba36) | Nov 26, 2023 |
| Lenovo        | ThinkPad T15p Gen 1 20TM... | [c333f48b93](https://linux-hardware.org/?probe=c333f48b93) | Nov 26, 2023 |
| ASUSTek       | X75VC                       | [be2ff8350a](https://linux-hardware.org/?probe=be2ff8350a) | Nov 26, 2023 |
| HP            | Laptop 14s-fq0xxx           | [3c423ffe17](https://linux-hardware.org/?probe=3c423ffe17) | Nov 26, 2023 |
| HP            | Laptop 14s-fq0xxx           | [439d50f8cc](https://linux-hardware.org/?probe=439d50f8cc) | Nov 26, 2023 |
| HP            | ENVY 15                     | [66a7391daf](https://linux-hardware.org/?probe=66a7391daf) | Nov 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [e18bd022e8](https://linux-hardware.org/?probe=e18bd022e8) | Nov 25, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [8cba28d4a5](https://linux-hardware.org/?probe=8cba28d4a5) | Nov 25, 2023 |
| Acer          | Swift SF314-59              | [3ffe3ca5b7](https://linux-hardware.org/?probe=3ffe3ca5b7) | Nov 25, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [a80073b9be](https://linux-hardware.org/?probe=a80073b9be) | Nov 25, 2023 |
| Acer          | TravelMate P215-51          | [fd03901ed8](https://linux-hardware.org/?probe=fd03901ed8) | Nov 25, 2023 |
| MSI           | Modern 14 B11MOU            | [a3ff822987](https://linux-hardware.org/?probe=a3ff822987) | Nov 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [23914b5dc2](https://linux-hardware.org/?probe=23914b5dc2) | Nov 25, 2023 |
| HP            | Compaq CQ58                 | [51198853ca](https://linux-hardware.org/?probe=51198853ca) | Nov 25, 2023 |
| Acer          | Nitro AN515-54              | [261d00b9c1](https://linux-hardware.org/?probe=261d00b9c1) | Nov 25, 2023 |
| Acer          | Nitro AN515-54              | [fe4e9cf955](https://linux-hardware.org/?probe=fe4e9cf955) | Nov 25, 2023 |
| Dell          | Inspiron 15-7579            | [ece1644afb](https://linux-hardware.org/?probe=ece1644afb) | Nov 25, 2023 |
| Acer          | Aspire A315-24P             | [30586cdeb5](https://linux-hardware.org/?probe=30586cdeb5) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e39da12205](https://linux-hardware.org/?probe=e39da12205) | Nov 24, 2023 |
| HP            | 255 G8 Notebook PC          | [dfe4473084](https://linux-hardware.org/?probe=dfe4473084) | Nov 24, 2023 |
| Lenovo        | ThinkPad T570 20HAS0K501    | [4fe6d8f889](https://linux-hardware.org/?probe=4fe6d8f889) | Nov 24, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [422a19e5a3](https://linux-hardware.org/?probe=422a19e5a3) | Nov 24, 2023 |
| Acer          | Swift SF314-41              | [23f539995b](https://linux-hardware.org/?probe=23f539995b) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [499c7927dd](https://linux-hardware.org/?probe=499c7927dd) | Nov 23, 2023 |
| Unknown       | M17                         | [d3d7d176b4](https://linux-hardware.org/?probe=d3d7d176b4) | Nov 23, 2023 |
| Lenovo        | V15-ADA 82C7                | [95e7fd0511](https://linux-hardware.org/?probe=95e7fd0511) | Nov 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9102327ebf](https://linux-hardware.org/?probe=9102327ebf) | Nov 23, 2023 |
| HP            | ProBook 430 G5              | [1c9b64b051](https://linux-hardware.org/?probe=1c9b64b051) | Nov 23, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [9d7f74829e](https://linux-hardware.org/?probe=9d7f74829e) | Nov 23, 2023 |
| HP            | EliteBook 840 G5            | [30f2717a78](https://linux-hardware.org/?probe=30f2717a78) | Nov 23, 2023 |
| Chuwi         | X312B                       | [7f13217449](https://linux-hardware.org/?probe=7f13217449) | Nov 23, 2023 |
| ASRock        | X370 Gaming X               | [0c39910834](https://linux-hardware.org/?probe=0c39910834) | Nov 23, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [e01de3faf5](https://linux-hardware.org/?probe=e01de3faf5) | Nov 23, 2023 |
| MSI           | Katana GF66 11UC            | [53ebec827d](https://linux-hardware.org/?probe=53ebec827d) | Nov 22, 2023 |
| Apple         | MacBookPro11,3              | [f918e70d3e](https://linux-hardware.org/?probe=f918e70d3e) | Nov 22, 2023 |
| HP            | EliteBook 850 G5            | [602aeb4101](https://linux-hardware.org/?probe=602aeb4101) | Nov 22, 2023 |
| Acer          | TravelMate P2510-G2-M       | [262eaee181](https://linux-hardware.org/?probe=262eaee181) | Nov 22, 2023 |
| Apple         | MacBook3,1                  | [ceffa3f19e](https://linux-hardware.org/?probe=ceffa3f19e) | Nov 22, 2023 |
| Apple         | MacBook3,1                  | [fa85f5740d](https://linux-hardware.org/?probe=fa85f5740d) | Nov 22, 2023 |
| HP            | 250 G7 Notebook PC          | [e73f1050cc](https://linux-hardware.org/?probe=e73f1050cc) | Nov 22, 2023 |
| Acer          | Aspire A515-56              | [28729f536b](https://linux-hardware.org/?probe=28729f536b) | Nov 22, 2023 |
| Acer          | Aspire A515-56              | [4d128b611f](https://linux-hardware.org/?probe=4d128b611f) | Nov 22, 2023 |
| Acer          | Aspire F5-573G              | [e28d68acd6](https://linux-hardware.org/?probe=e28d68acd6) | Nov 21, 2023 |
| Acer          | Aspire F5-573G              | [d3f91d31f6](https://linux-hardware.org/?probe=d3f91d31f6) | Nov 21, 2023 |
| Sony          | SVE1713X1EB                 | [a6efd4193b](https://linux-hardware.org/?probe=a6efd4193b) | Nov 21, 2023 |
| Mediacom      | FlexBook edge11 - M-FBE1... | [9b0835e62d](https://linux-hardware.org/?probe=9b0835e62d) | Nov 21, 2023 |
| HP            | ProBook 4540s               | [59a7759558](https://linux-hardware.org/?probe=59a7759558) | Nov 21, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d91c731a96](https://linux-hardware.org/?probe=d91c731a96) | Nov 21, 2023 |
| HP            | Victus by Gaming Laptop ... | [7fe73d7cf1](https://linux-hardware.org/?probe=7fe73d7cf1) | Nov 21, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [4191c265d7](https://linux-hardware.org/?probe=4191c265d7) | Nov 20, 2023 |
| MSI           | Thin GF63 12VF              | [ca1a9ef401](https://linux-hardware.org/?probe=ca1a9ef401) | Nov 20, 2023 |
| Apple         | MacBookPro5,5               | [a2d556bc01](https://linux-hardware.org/?probe=a2d556bc01) | Nov 20, 2023 |
| Dell          | Latitude E6230              | [467d45ff38](https://linux-hardware.org/?probe=467d45ff38) | Nov 20, 2023 |
| ASUSTek       | X555YI                      | [4464a0ee93](https://linux-hardware.org/?probe=4464a0ee93) | Nov 20, 2023 |
| HP            | Pavilion g6                 | [b81902d8d5](https://linux-hardware.org/?probe=b81902d8d5) | Nov 20, 2023 |
| HUAWEI        | BOD-WXX9                    | [13e6e37377](https://linux-hardware.org/?probe=13e6e37377) | Nov 20, 2023 |
| Apple         | MacBookPro5,5               | [cdc6379993](https://linux-hardware.org/?probe=cdc6379993) | Nov 19, 2023 |
| Apple         | MacBookPro5,5               | [840adf8528](https://linux-hardware.org/?probe=840adf8528) | Nov 19, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [6acae93e45](https://linux-hardware.org/?probe=6acae93e45) | Nov 19, 2023 |
| Notebook      | NL5xRU                      | [7b5f6c8151](https://linux-hardware.org/?probe=7b5f6c8151) | Nov 19, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0B70... | [808b3a2a5d](https://linux-hardware.org/?probe=808b3a2a5d) | Nov 19, 2023 |
| HP            | Pavilion g6                 | [5c6de74207](https://linux-hardware.org/?probe=5c6de74207) | Nov 19, 2023 |
| Lenovo        | Ducati 5 82ES               | [04fce2b1b1](https://linux-hardware.org/?probe=04fce2b1b1) | Nov 19, 2023 |
| Lenovo        | IdeaPad U330 Touch 20268    | [63884f09c6](https://linux-hardware.org/?probe=63884f09c6) | Nov 19, 2023 |
| ASUSTek       | K56CB                       | [b20c5c71dd](https://linux-hardware.org/?probe=b20c5c71dd) | Nov 19, 2023 |
| Lenovo        | Ducati 5 82ES               | [70a8dad823](https://linux-hardware.org/?probe=70a8dad823) | Nov 19, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [d957a1a8c5](https://linux-hardware.org/?probe=d957a1a8c5) | Nov 19, 2023 |
| ASUSTek       | K501UXM                     | [727b1debe1](https://linux-hardware.org/?probe=727b1debe1) | Nov 18, 2023 |
| HP            | ENVY dv6                    | [136bb5cac4](https://linux-hardware.org/?probe=136bb5cac4) | Nov 18, 2023 |
| MSI           | Modern 14 B11MOL            | [90d21a5044](https://linux-hardware.org/?probe=90d21a5044) | Nov 18, 2023 |
| Lenovo        | ThinkPad T530 23924FJ       | [b7a94da831](https://linux-hardware.org/?probe=b7a94da831) | Nov 17, 2023 |
| ASUSTek       | X550LA                      | [eb8b271929](https://linux-hardware.org/?probe=eb8b271929) | Nov 17, 2023 |
| HP            | Compaq Presario CQ61        | [51f28bbefb](https://linux-hardware.org/?probe=51f28bbefb) | Nov 17, 2023 |
| HP            | ENVY dv6                    | [58263cedeb](https://linux-hardware.org/?probe=58263cedeb) | Nov 17, 2023 |
| SiComputer    | Nauta 01E                   | [1631e065bd](https://linux-hardware.org/?probe=1631e065bd) | Nov 17, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [cdb7f0682b](https://linux-hardware.org/?probe=cdb7f0682b) | Nov 17, 2023 |
| Acer          | Aspire E5-575G              | [41d4402bf3](https://linux-hardware.org/?probe=41d4402bf3) | Nov 17, 2023 |
| Lenovo        | ThinkPad T480 20L6S55K00    | [ba85d81d10](https://linux-hardware.org/?probe=ba85d81d10) | Nov 16, 2023 |
| Lenovo        | ThinkPad T480 20L6S55K00    | [b2c3886395](https://linux-hardware.org/?probe=b2c3886395) | Nov 16, 2023 |
| HP            | 650                         | [86c4ffd3cc](https://linux-hardware.org/?probe=86c4ffd3cc) | Nov 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7813c5e090](https://linux-hardware.org/?probe=7813c5e090) | Nov 16, 2023 |
| HUAWEI        | BOD-WXX9                    | [9096161802](https://linux-hardware.org/?probe=9096161802) | Nov 16, 2023 |
| Acer          | Aspire A515-45              | [d1800f3356](https://linux-hardware.org/?probe=d1800f3356) | Nov 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [925c8180fc](https://linux-hardware.org/?probe=925c8180fc) | Nov 16, 2023 |
| HP            | 650                         | [262ff4134d](https://linux-hardware.org/?probe=262ff4134d) | Nov 16, 2023 |
| Acer          | Extensa 5220                | [313dfe3829](https://linux-hardware.org/?probe=313dfe3829) | Nov 16, 2023 |
| Lenovo        | ThinkPad T470 20HES04Q00    | [ebb179e02e](https://linux-hardware.org/?probe=ebb179e02e) | Nov 16, 2023 |
| Dell          | Vostro 16 5630              | [5716490407](https://linux-hardware.org/?probe=5716490407) | Nov 16, 2023 |
| Acer          | Aspire A315-42              | [a21066a759](https://linux-hardware.org/?probe=a21066a759) | Nov 15, 2023 |
| Acer          | Extensa 5220                | [6b5e8902be](https://linux-hardware.org/?probe=6b5e8902be) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [378bb9c07b](https://linux-hardware.org/?probe=378bb9c07b) | Nov 15, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [492ee4603f](https://linux-hardware.org/?probe=492ee4603f) | Nov 15, 2023 |
| HP            | Pavilion dv6                | [a7404738ed](https://linux-hardware.org/?probe=a7404738ed) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [0fae742aa3](https://linux-hardware.org/?probe=0fae742aa3) | Nov 15, 2023 |
| HP            | Notebook                    | [2048deb542](https://linux-hardware.org/?probe=2048deb542) | Nov 15, 2023 |
| Dell          | Latitude E5540              | [75c5f17cf5](https://linux-hardware.org/?probe=75c5f17cf5) | Nov 14, 2023 |
| MSI           | GF63 Thin 11SC              | [5fbfbad938](https://linux-hardware.org/?probe=5fbfbad938) | Nov 14, 2023 |
| MSI           | GF63 Thin 11SC              | [a6f59c7877](https://linux-hardware.org/?probe=a6f59c7877) | Nov 14, 2023 |
| Acer          | Extensa 2540                | [22e65d0a5b](https://linux-hardware.org/?probe=22e65d0a5b) | Nov 14, 2023 |
| Packard Be... | EasyNote TK81               | [a44fd2dc7a](https://linux-hardware.org/?probe=a44fd2dc7a) | Nov 14, 2023 |
| ASUSTek       | Zephyrus S GX502GV_GX502... | [3567b57191](https://linux-hardware.org/?probe=3567b57191) | Nov 14, 2023 |
| Acer          | Aspire A315-42              | [42d05f19a2](https://linux-hardware.org/?probe=42d05f19a2) | Nov 13, 2023 |
| ASUSTek       | X55U                        | [04a09add31](https://linux-hardware.org/?probe=04a09add31) | Nov 13, 2023 |
| Dell          | Precision M4800             | [9a63057a12](https://linux-hardware.org/?probe=9a63057a12) | Nov 13, 2023 |
| HP            | ENVY 15                     | [b8ee2c11e1](https://linux-hardware.org/?probe=b8ee2c11e1) | Nov 13, 2023 |
| Acer          | TravelMate 5730             | [accf863283](https://linux-hardware.org/?probe=accf863283) | Nov 13, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [ca10e0d0f3](https://linux-hardware.org/?probe=ca10e0d0f3) | Nov 13, 2023 |
| HP            | 650                         | [c1ca175779](https://linux-hardware.org/?probe=c1ca175779) | Nov 12, 2023 |
| Dell          | Latitude 5580               | [4343277d0b](https://linux-hardware.org/?probe=4343277d0b) | Nov 12, 2023 |
| Acer          | Aspire 5735                 | [539da3b61a](https://linux-hardware.org/?probe=539da3b61a) | Nov 12, 2023 |
| HP            | ProBook 450 G2              | [872e6f2ca5](https://linux-hardware.org/?probe=872e6f2ca5) | Nov 12, 2023 |
| Dell          | Inspiron ME051              | [e0114c60de](https://linux-hardware.org/?probe=e0114c60de) | Nov 12, 2023 |
| Jumper        | EZbook                      | [682c154cdb](https://linux-hardware.org/?probe=682c154cdb) | Nov 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b9ad1f18d8](https://linux-hardware.org/?probe=b9ad1f18d8) | Nov 12, 2023 |
| HP            | EliteBook 2530p             | [4a9666ef8a](https://linux-hardware.org/?probe=4a9666ef8a) | Nov 12, 2023 |
| HP            | 15                          | [dbd704fdbb](https://linux-hardware.org/?probe=dbd704fdbb) | Nov 11, 2023 |
| HUAWEI        | BOD-WXX9                    | [0ff417d90e](https://linux-hardware.org/?probe=0ff417d90e) | Nov 11, 2023 |
| Sony          | VPCS13V9E                   | [a833e9377a](https://linux-hardware.org/?probe=a833e9377a) | Nov 11, 2023 |
| Sony          | VPCS13V9E                   | [044d37ef79](https://linux-hardware.org/?probe=044d37ef79) | Nov 11, 2023 |
| Acer          | Predator PT515-52           | [4f5c31bd64](https://linux-hardware.org/?probe=4f5c31bd64) | Nov 11, 2023 |
| Acer          | Predator PT515-52           | [ac3ab44d32](https://linux-hardware.org/?probe=ac3ab44d32) | Nov 11, 2023 |
| ASUSTek       | Zenbook S 13 UX5304VA_UX... | [a634797954](https://linux-hardware.org/?probe=a634797954) | Nov 11, 2023 |
| ASUSTek       | X202E                       | [b78da681e7](https://linux-hardware.org/?probe=b78da681e7) | Nov 11, 2023 |
| Acer          | Swift SF314-59              | [9fde81d361](https://linux-hardware.org/?probe=9fde81d361) | Nov 10, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [b88ecdebac](https://linux-hardware.org/?probe=b88ecdebac) | Nov 10, 2023 |
| Sony          | VPCEB1S1E                   | [b0d4e06348](https://linux-hardware.org/?probe=b0d4e06348) | Nov 10, 2023 |
| HP            | Pavilion g6                 | [450bb23de1](https://linux-hardware.org/?probe=450bb23de1) | Nov 10, 2023 |
| Dynabook      | PORTEGE X30L-G              | [64326392ac](https://linux-hardware.org/?probe=64326392ac) | Nov 10, 2023 |
| HP            | ProBook 440 G7              | [fab830af79](https://linux-hardware.org/?probe=fab830af79) | Nov 10, 2023 |
| ASUSTek       | Zenbook S 13 UX5304VA_UX... | [6155a9c2ec](https://linux-hardware.org/?probe=6155a9c2ec) | Nov 10, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [906f638c34](https://linux-hardware.org/?probe=906f638c34) | Nov 10, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [cfc1427577](https://linux-hardware.org/?probe=cfc1427577) | Nov 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [644bf9e936](https://linux-hardware.org/?probe=644bf9e936) | Nov 09, 2023 |
| HP            | 250 G1                      | [a06122606d](https://linux-hardware.org/?probe=a06122606d) | Nov 09, 2023 |
| Lenovo        | B50-80 80EW                 | [43c69e6055](https://linux-hardware.org/?probe=43c69e6055) | Nov 09, 2023 |
| Apple         | MacBook2,1                  | [448165ceca](https://linux-hardware.org/?probe=448165ceca) | Nov 09, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [0bb1ba6267](https://linux-hardware.org/?probe=0bb1ba6267) | Nov 09, 2023 |
| HP            | Laptop 15s-eq2xxx           | [e55e321a2e](https://linux-hardware.org/?probe=e55e321a2e) | Nov 09, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [b221326a48](https://linux-hardware.org/?probe=b221326a48) | Nov 09, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [840241bcdd](https://linux-hardware.org/?probe=840241bcdd) | Nov 09, 2023 |
| Acer          | Aspire A515-47              | [50a18dd494](https://linux-hardware.org/?probe=50a18dd494) | Nov 09, 2023 |
| Dell          | Latitude 5420               | [efa8caa859](https://linux-hardware.org/?probe=efa8caa859) | Nov 09, 2023 |
| Acer          | Aspire A315-41              | [30673db04e](https://linux-hardware.org/?probe=30673db04e) | Nov 08, 2023 |
| Acer          | Aspire A315-41              | [6f78d1f11d](https://linux-hardware.org/?probe=6f78d1f11d) | Nov 08, 2023 |
| Dell          | XPS 15 9560                 | [25fd8cabab](https://linux-hardware.org/?probe=25fd8cabab) | Nov 08, 2023 |
| Olivetti      | P55-AEU-323-4G320           | [5d53de5c7d](https://linux-hardware.org/?probe=5d53de5c7d) | Nov 08, 2023 |
| Lenovo        | ThinkPad T495 20NKS1YE00    | [ad892a8aea](https://linux-hardware.org/?probe=ad892a8aea) | Nov 07, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5e3d94c299](https://linux-hardware.org/?probe=5e3d94c299) | Nov 07, 2023 |
| Dell          | XPS 13 7390                 | [2259df96c0](https://linux-hardware.org/?probe=2259df96c0) | Nov 07, 2023 |
| Dell          | Vostro 3500                 | [c85bdae7e5](https://linux-hardware.org/?probe=c85bdae7e5) | Nov 07, 2023 |
| Sony          | SVE1513Q1ESI                | [1a8df0d5de](https://linux-hardware.org/?probe=1a8df0d5de) | Nov 07, 2023 |
| HP            | Pavilion Gaming Notebook    | [c2a37daf7d](https://linux-hardware.org/?probe=c2a37daf7d) | Nov 07, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [220d14894a](https://linux-hardware.org/?probe=220d14894a) | Nov 07, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XJ... | [5756bdb835](https://linux-hardware.org/?probe=5756bdb835) | Nov 07, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [e874ddf25c](https://linux-hardware.org/?probe=e874ddf25c) | Nov 07, 2023 |
| Chuwi         | GemiBook Pro                | [9f1e875996](https://linux-hardware.org/?probe=9f1e875996) | Nov 07, 2023 |
| Intel         | Jasper Lake Client Platf... | [75a2534386](https://linux-hardware.org/?probe=75a2534386) | Nov 07, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [f93d40f708](https://linux-hardware.org/?probe=f93d40f708) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [9755c6bf31](https://linux-hardware.org/?probe=9755c6bf31) | Nov 06, 2023 |
| ASUSTek       | X555LAB                     | [2d3d09097d](https://linux-hardware.org/?probe=2d3d09097d) | Nov 06, 2023 |
| ASUSTek       | UX310UQK                    | [98bc0094ec](https://linux-hardware.org/?probe=98bc0094ec) | Nov 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [3cd8e36ab1](https://linux-hardware.org/?probe=3cd8e36ab1) | Nov 06, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | [88cc97d0be](https://linux-hardware.org/?probe=88cc97d0be) | Nov 06, 2023 |
| Apple         | MacBookPro11,3              | [0009d8a468](https://linux-hardware.org/?probe=0009d8a468) | Nov 06, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [62b6928793](https://linux-hardware.org/?probe=62b6928793) | Nov 06, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [10f2785958](https://linux-hardware.org/?probe=10f2785958) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | [8447756322](https://linux-hardware.org/?probe=8447756322) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | [af12dd22ba](https://linux-hardware.org/?probe=af12dd22ba) | Nov 06, 2023 |
| HP            | 250 G7 Notebook PC          | [a2ad36d26c](https://linux-hardware.org/?probe=a2ad36d26c) | Nov 06, 2023 |
| HP            | EliteBook 830 G5            | [07ef51bd31](https://linux-hardware.org/?probe=07ef51bd31) | Nov 05, 2023 |
| HP            | ProBook 450 G5              | [6407166dd5](https://linux-hardware.org/?probe=6407166dd5) | Nov 05, 2023 |
| HP            | Laptop 15-db1xxx            | [3a69031984](https://linux-hardware.org/?probe=3a69031984) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8e3e7668cf](https://linux-hardware.org/?probe=8e3e7668cf) | Nov 05, 2023 |
| Sony          | VGN-N21S_W                  | [6ff4658440](https://linux-hardware.org/?probe=6ff4658440) | Nov 05, 2023 |
| Sony          | VGN-N21S_W                  | [266bedfdc3](https://linux-hardware.org/?probe=266bedfdc3) | Nov 05, 2023 |
| Unknown       | Unknown                     | [2c2d291f54](https://linux-hardware.org/?probe=2c2d291f54) | Nov 05, 2023 |
| HP            | 530                         | [710ba89827](https://linux-hardware.org/?probe=710ba89827) | Nov 05, 2023 |
| HP            | Notebook                    | [8eea1901f7](https://linux-hardware.org/?probe=8eea1901f7) | Nov 05, 2023 |
| Lenovo        | ThinkPad X250 20CM001UUK    | [b0fd9fa3c0](https://linux-hardware.org/?probe=b0fd9fa3c0) | Nov 05, 2023 |
| HP            | Pavilion 15                 | [dd81ed04ea](https://linux-hardware.org/?probe=dd81ed04ea) | Nov 04, 2023 |
| HP            | ProBook 430 G1              | [14dc35a1b9](https://linux-hardware.org/?probe=14dc35a1b9) | Nov 04, 2023 |
| HP            | Notebook                    | [f8cf975d3c](https://linux-hardware.org/?probe=f8cf975d3c) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [34e4bd156f](https://linux-hardware.org/?probe=34e4bd156f) | Nov 04, 2023 |
| HP            | ZBook 17 G3                 | [7d38ea5f87](https://linux-hardware.org/?probe=7d38ea5f87) | Nov 04, 2023 |
| HP            | EliteBook 840 G6            | [d4b22ac16a](https://linux-hardware.org/?probe=d4b22ac16a) | Nov 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [3922b02290](https://linux-hardware.org/?probe=3922b02290) | Nov 04, 2023 |
| HP            | 255 G8 Notebook PC          | [2d1116cd1b](https://linux-hardware.org/?probe=2d1116cd1b) | Nov 04, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [85e528f1bf](https://linux-hardware.org/?probe=85e528f1bf) | Nov 04, 2023 |
| Dell          | Inspiron 15 3511            | [8c23fbf7d1](https://linux-hardware.org/?probe=8c23fbf7d1) | Nov 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [bb7622a7ba](https://linux-hardware.org/?probe=bb7622a7ba) | Nov 04, 2023 |
| Dell          | XPS 15 7590                 | [8685e384af](https://linux-hardware.org/?probe=8685e384af) | Nov 04, 2023 |
| HUAWEI        | KLVL-WXX9                   | [61342b31ea](https://linux-hardware.org/?probe=61342b31ea) | Nov 03, 2023 |
| ASUSTek       | X551CA                      | [20bee22e0a](https://linux-hardware.org/?probe=20bee22e0a) | Nov 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ff0d013246](https://linux-hardware.org/?probe=ff0d013246) | Nov 03, 2023 |
| Acer          | Nitro AN515-54              | [ce98faee85](https://linux-hardware.org/?probe=ce98faee85) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [f9bdbf6371](https://linux-hardware.org/?probe=f9bdbf6371) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [b592d36d74](https://linux-hardware.org/?probe=b592d36d74) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [da695062ba](https://linux-hardware.org/?probe=da695062ba) | Nov 03, 2023 |
| Dell          | Inspiron 16 5625            | [157f3bd86a](https://linux-hardware.org/?probe=157f3bd86a) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [bcea72b22f](https://linux-hardware.org/?probe=bcea72b22f) | Nov 03, 2023 |
| ASUSTek       | X510URR                     | [645fbe9fc3](https://linux-hardware.org/?probe=645fbe9fc3) | Nov 03, 2023 |
| Acer          | Swift SF114-32              | [2314e30b70](https://linux-hardware.org/?probe=2314e30b70) | Nov 03, 2023 |
| Acer          | Swift SF114-32              | [ad12644dff](https://linux-hardware.org/?probe=ad12644dff) | Nov 03, 2023 |
| HP            | 250 G7 Notebook PC          | [1889111d8a](https://linux-hardware.org/?probe=1889111d8a) | Nov 03, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | [cf0c02a17a](https://linux-hardware.org/?probe=cf0c02a17a) | Nov 03, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | [fdb464fed7](https://linux-hardware.org/?probe=fdb464fed7) | Nov 02, 2023 |
| Notebook      | NJ50_70CU                   | [9cabd6fd2c](https://linux-hardware.org/?probe=9cabd6fd2c) | Nov 02, 2023 |
| Notebook      | NJ50_70CU                   | [3414d178f2](https://linux-hardware.org/?probe=3414d178f2) | Nov 02, 2023 |
| HUAWEI        | KPL-W0X                     | [9cdd815382](https://linux-hardware.org/?probe=9cdd815382) | Nov 02, 2023 |
| MSI           | Prestige 14Evo A11M         | [12414485a5](https://linux-hardware.org/?probe=12414485a5) | Nov 02, 2023 |
| HP            | EliteBook 830 G5            | [8ab22982cc](https://linux-hardware.org/?probe=8ab22982cc) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b0c996ac38](https://linux-hardware.org/?probe=b0c996ac38) | Nov 02, 2023 |
| Lenovo        | ThinkPad T440 20B7A0CYMH    | [4d3101d9f8](https://linux-hardware.org/?probe=4d3101d9f8) | Nov 02, 2023 |
| Samsung       | 750XDA                      | [130a1273e5](https://linux-hardware.org/?probe=130a1273e5) | Nov 02, 2023 |
| Dell          | XPS 13 9300                 | [9690e7a65f](https://linux-hardware.org/?probe=9690e7a65f) | Nov 02, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [37dc32cd03](https://linux-hardware.org/?probe=37dc32cd03) | Nov 02, 2023 |
| Lenovo        | ThinkPad P53 20QN000FIX     | [40de43c266](https://linux-hardware.org/?probe=40de43c266) | Nov 02, 2023 |
| ASUSTek       | U36SD                       | [e2045d61a5](https://linux-hardware.org/?probe=e2045d61a5) | Nov 02, 2023 |
| Lenovo        | ThinkPad T480 20L60017UK    | [e8b030e97f](https://linux-hardware.org/?probe=e8b030e97f) | Nov 02, 2023 |
| ASUSTek       | X555LAB                     | [b9532c1f86](https://linux-hardware.org/?probe=b9532c1f86) | Nov 02, 2023 |
| Acer          | One S1002                   | [a00e6d78a6](https://linux-hardware.org/?probe=a00e6d78a6) | Nov 02, 2023 |
| ASUSTek       | N550JV                      | [200e3255d9](https://linux-hardware.org/?probe=200e3255d9) | Nov 02, 2023 |
| Chuwi         | CoreBook Pro                | [ac0f4a1ea9](https://linux-hardware.org/?probe=ac0f4a1ea9) | Nov 01, 2023 |
| ASUSTek       | N550JV                      | [43a84b57f0](https://linux-hardware.org/?probe=43a84b57f0) | Nov 01, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [df4f43ca44](https://linux-hardware.org/?probe=df4f43ca44) | Nov 01, 2023 |
| Acer          | Aspire A315-56              | [2de4949247](https://linux-hardware.org/?probe=2de4949247) | Nov 01, 2023 |
| ASUSTek       | UX430UNR                    | [47abbeb9c1](https://linux-hardware.org/?probe=47abbeb9c1) | Nov 01, 2023 |
| Acer          | TravelMate P215-52          | [b9c3643e62](https://linux-hardware.org/?probe=b9c3643e62) | Nov 01, 2023 |
| ASUSTek       | K56CB                       | [9fff1dc94c](https://linux-hardware.org/?probe=9fff1dc94c) | Nov 01, 2023 |
| HP            | 630                         | [634f46006b](https://linux-hardware.org/?probe=634f46006b) | Nov 01, 2023 |
| Acer          | Nitro AN515-52              | [829c16d044](https://linux-hardware.org/?probe=829c16d044) | Nov 01, 2023 |
| Apple         | MacBook7,1                  | [60edf3f76c](https://linux-hardware.org/?probe=60edf3f76c) | Nov 01, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [ed95443390](https://linux-hardware.org/?probe=ed95443390) | Nov 01, 2023 |
| Apple         | MacBookPro16,2              | [37b53d54e8](https://linux-hardware.org/?probe=37b53d54e8) | Nov 01, 2023 |
| Acer          | Nitro AN515-56              | [7c88fdcaa3](https://linux-hardware.org/?probe=7c88fdcaa3) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2SX0... | [d5fee530ee](https://linux-hardware.org/?probe=d5fee530ee) | Nov 01, 2023 |
| Lenovo        | V15-ADA 82C7                | [0c38487bcf](https://linux-hardware.org/?probe=0c38487bcf) | Nov 01, 2023 |
| HP            | Laptop 15-bs1xx             | [1bd48815fe](https://linux-hardware.org/?probe=1bd48815fe) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5acc8f68a0](https://linux-hardware.org/?probe=5acc8f68a0) | Nov 01, 2023 |
| Sony          | VPCSA3J1E                   | [99b0d275ec](https://linux-hardware.org/?probe=99b0d275ec) | Nov 01, 2023 |
| HUAWEI        | MACH-WX9                    | [f557533925](https://linux-hardware.org/?probe=f557533925) | Nov 01, 2023 |
| Microtech     | CoreBookLite                | [1833fd5f0c](https://linux-hardware.org/?probe=1833fd5f0c) | Nov 01, 2023 |
| HUAWEI        | MACH-WX9                    | [50880de513](https://linux-hardware.org/?probe=50880de513) | Nov 01, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [cd9e941307](https://linux-hardware.org/?probe=cd9e941307) | Nov 01, 2023 |
| Dell          | Inspiron 7520               | [460c9255bd](https://linux-hardware.org/?probe=460c9255bd) | Nov 01, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0FS0... | [0b21a4419d](https://linux-hardware.org/?probe=0b21a4419d) | Nov 01, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0FS0... | [757199e3cf](https://linux-hardware.org/?probe=757199e3cf) | Nov 01, 2023 |
| HUAWEI        | BOHB-WAX9                   | [5da84da52f](https://linux-hardware.org/?probe=5da84da52f) | Oct 31, 2023 |
| HP            | 250 G5 Notebook PC          | [803bc8d1ed](https://linux-hardware.org/?probe=803bc8d1ed) | Oct 31, 2023 |
| HP            | 255 G8 Notebook PC          | [b9d1b13098](https://linux-hardware.org/?probe=b9d1b13098) | Oct 31, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6c1c4ea069](https://linux-hardware.org/?probe=6c1c4ea069) | Oct 31, 2023 |
| HUAWEI        | CREF-XX                     | [a10aa3c3e5](https://linux-hardware.org/?probe=a10aa3c3e5) | Oct 31, 2023 |
| ASUSTek       | F5N                         | [8da324b4fa](https://linux-hardware.org/?probe=8da324b4fa) | Oct 31, 2023 |
| Dell          | XPS 15 9570                 | [341114c78a](https://linux-hardware.org/?probe=341114c78a) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [aef3dccca0](https://linux-hardware.org/?probe=aef3dccca0) | Oct 31, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [1107919053](https://linux-hardware.org/?probe=1107919053) | Oct 31, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [ea29ba4b58](https://linux-hardware.org/?probe=ea29ba4b58) | Oct 31, 2023 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [8e86103e06](https://linux-hardware.org/?probe=8e86103e06) | Oct 31, 2023 |
| Samsung       | 750XED                      | [9dab50e37e](https://linux-hardware.org/?probe=9dab50e37e) | Oct 31, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [4f6d9ac7b5](https://linux-hardware.org/?probe=4f6d9ac7b5) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [98d01105c7](https://linux-hardware.org/?probe=98d01105c7) | Oct 31, 2023 |
| Dell          | XPS 15 9510                 | [d370c488e4](https://linux-hardware.org/?probe=d370c488e4) | Oct 31, 2023 |
| Samsung       | 930XDB/931XDB/930XDY        | [421368e431](https://linux-hardware.org/?probe=421368e431) | Oct 31, 2023 |
| Dell          | Vostro 3549                 | [259c646ecb](https://linux-hardware.org/?probe=259c646ecb) | Oct 31, 2023 |
| Samsung       | RC420/RC520/RC720           | [1e3f228931](https://linux-hardware.org/?probe=1e3f228931) | Oct 31, 2023 |
| Samsung       | RC420/RC520/RC720           | [10382e8ed6](https://linux-hardware.org/?probe=10382e8ed6) | Oct 31, 2023 |
| AMI           | Intel                       | [98d35ad708](https://linux-hardware.org/?probe=98d35ad708) | Oct 31, 2023 |
| Toshiba       | TECRA S11                   | [e2a669bf1a](https://linux-hardware.org/?probe=e2a669bf1a) | Oct 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS26200    | [ebcacada49](https://linux-hardware.org/?probe=ebcacada49) | Oct 31, 2023 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [a0da22e928](https://linux-hardware.org/?probe=a0da22e928) | Oct 31, 2023 |
| ASUSTek       | X550EP                      | [81fdd48960](https://linux-hardware.org/?probe=81fdd48960) | Oct 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS26200    | [d8658ea415](https://linux-hardware.org/?probe=d8658ea415) | Oct 31, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [ed27ef3491](https://linux-hardware.org/?probe=ed27ef3491) | Oct 31, 2023 |
| Alienware     | 13 R3                       | [726415f251](https://linux-hardware.org/?probe=726415f251) | Oct 31, 2023 |
| Dell          | XPS 15 9530                 | [683545565a](https://linux-hardware.org/?probe=683545565a) | Oct 31, 2023 |
| Lenovo        | G500 20236                  | [6779e74408](https://linux-hardware.org/?probe=6779e74408) | Oct 31, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [2a589a5505](https://linux-hardware.org/?probe=2a589a5505) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [53cd13281b](https://linux-hardware.org/?probe=53cd13281b) | Oct 31, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [daa299c314](https://linux-hardware.org/?probe=daa299c314) | Oct 31, 2023 |
| Dell          | Latitude 5520               | [3803e551f1](https://linux-hardware.org/?probe=3803e551f1) | Oct 31, 2023 |
| Apple         | MacBook7,1                  | [11ada26a4c](https://linux-hardware.org/?probe=11ada26a4c) | Oct 31, 2023 |
| Dell          | Inspiron 7580               | [fc223b91ed](https://linux-hardware.org/?probe=fc223b91ed) | Oct 31, 2023 |
| Lenovo        | ThinkPad E470 20H1006KIX    | [d84959fadc](https://linux-hardware.org/?probe=d84959fadc) | Oct 31, 2023 |
| HP            | 250 G6 Notebook PC          | [c1d956674a](https://linux-hardware.org/?probe=c1d956674a) | Oct 31, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [2f63bfb399](https://linux-hardware.org/?probe=2f63bfb399) | Oct 31, 2023 |
| Dell          | Inspiron 5590               | [7634c564d0](https://linux-hardware.org/?probe=7634c564d0) | Oct 31, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [54a64f0a7e](https://linux-hardware.org/?probe=54a64f0a7e) | Oct 31, 2023 |
| Dell          | Precision M6800             | [72c51649f1](https://linux-hardware.org/?probe=72c51649f1) | Oct 31, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | [38b70999b9](https://linux-hardware.org/?probe=38b70999b9) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2eaf76ce92](https://linux-hardware.org/?probe=2eaf76ce92) | Oct 31, 2023 |
| Dell          | Latitude 5414               | [fd7b086e1b](https://linux-hardware.org/?probe=fd7b086e1b) | Oct 31, 2023 |
| Timi          | RedmiBook Pro 15            | [2cad75b0fc](https://linux-hardware.org/?probe=2cad75b0fc) | Oct 31, 2023 |
| Dell          | Latitude 5420               | [c2f4052fb4](https://linux-hardware.org/?probe=c2f4052fb4) | Oct 31, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [487222ef3e](https://linux-hardware.org/?probe=487222ef3e) | Oct 31, 2023 |
| Acer          | Swift SF314-41              | [1bdd8f14ad](https://linux-hardware.org/?probe=1bdd8f14ad) | Oct 31, 2023 |
| HP            | Laptop 15-dw0xxx            | [55f41faf27](https://linux-hardware.org/?probe=55f41faf27) | Oct 31, 2023 |
| Lenovo        | Z50-70 20354                | [8d764a9632](https://linux-hardware.org/?probe=8d764a9632) | Oct 31, 2023 |
| Dell          | Inspiron 5590               | [d339ee4dbc](https://linux-hardware.org/?probe=d339ee4dbc) | Oct 30, 2023 |
| Lenovo        | G500 20236                  | [000230db12](https://linux-hardware.org/?probe=000230db12) | Oct 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [32d642cc3b](https://linux-hardware.org/?probe=32d642cc3b) | Oct 30, 2023 |
| ASUSTek       | X555LP                      | [1f57f57452](https://linux-hardware.org/?probe=1f57f57452) | Oct 30, 2023 |
| Lenovo        | ThinkPad L540 20AV005GIX    | [ca59c544ef](https://linux-hardware.org/?probe=ca59c544ef) | Oct 30, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [309695dc7e](https://linux-hardware.org/?probe=309695dc7e) | Oct 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [ab5cef69c3](https://linux-hardware.org/?probe=ab5cef69c3) | Oct 30, 2023 |
| Dell          | XPS 15 9520                 | [0fb7ced892](https://linux-hardware.org/?probe=0fb7ced892) | Oct 30, 2023 |
| Apple         | MacBookPro11,4              | [4d6c2166c8](https://linux-hardware.org/?probe=4d6c2166c8) | Oct 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [055e34b095](https://linux-hardware.org/?probe=055e34b095) | Oct 30, 2023 |
| HP            | Pavilion Gaming Notebook    | [17dd2ce988](https://linux-hardware.org/?probe=17dd2ce988) | Oct 30, 2023 |
| Acer          | Aspire A515-45              | [25431e9c91](https://linux-hardware.org/?probe=25431e9c91) | Oct 30, 2023 |
| HP            | ProBook 650 G1              | [508c244637](https://linux-hardware.org/?probe=508c244637) | Oct 30, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [5f8cf197d5](https://linux-hardware.org/?probe=5f8cf197d5) | Oct 30, 2023 |
| Lenovo        | ThinkPad T530 23924FJ       | [c8b87fb249](https://linux-hardware.org/?probe=c8b87fb249) | Oct 30, 2023 |
| ASUSTek       | X555UJ                      | [de6e2775a4](https://linux-hardware.org/?probe=de6e2775a4) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [dd2e706549](https://linux-hardware.org/?probe=dd2e706549) | Oct 30, 2023 |
| Lenovo        | ThinkPad T530 23924FJ       | [b64508402a](https://linux-hardware.org/?probe=b64508402a) | Oct 30, 2023 |
| Dell          | Precision 3541              | [6857b35adc](https://linux-hardware.org/?probe=6857b35adc) | Oct 30, 2023 |
| MSI           | Delta 15 A5EFK              | [185b65ebc1](https://linux-hardware.org/?probe=185b65ebc1) | Oct 30, 2023 |
| HP            | 255 G6 Notebook PC          | [f19f70993f](https://linux-hardware.org/?probe=f19f70993f) | Oct 30, 2023 |
| MSI           | GP66 Leopard 10UG           | [47dbfa475a](https://linux-hardware.org/?probe=47dbfa475a) | Oct 30, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d5debf7011](https://linux-hardware.org/?probe=d5debf7011) | Oct 30, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [2b883f993f](https://linux-hardware.org/?probe=2b883f993f) | Oct 30, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [0b129d4a95](https://linux-hardware.org/?probe=0b129d4a95) | Oct 30, 2023 |
| Dell          | Vostro 3525                 | [ad34d5b54f](https://linux-hardware.org/?probe=ad34d5b54f) | Oct 30, 2023 |
| ASUSTek       | F5N                         | [67f3a19888](https://linux-hardware.org/?probe=67f3a19888) | Oct 30, 2023 |
| Dell          | Inspiron 1545               | [5a1d90c1a7](https://linux-hardware.org/?probe=5a1d90c1a7) | Oct 30, 2023 |
| MSI           | GF75 Thin 10UEK             | [c9cb087088](https://linux-hardware.org/?probe=c9cb087088) | Oct 30, 2023 |
| ASUSTek       | K50IJ                       | [115cf0d371](https://linux-hardware.org/?probe=115cf0d371) | Oct 30, 2023 |
| ASUSTek       | K50IJ                       | [6fbbd2a061](https://linux-hardware.org/?probe=6fbbd2a061) | Oct 30, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [b3e37008cb](https://linux-hardware.org/?probe=b3e37008cb) | Oct 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [81a7cabe4f](https://linux-hardware.org/?probe=81a7cabe4f) | Oct 30, 2023 |
| MSI           | GF75 Thin 10UEK             | [a58fbe3576](https://linux-hardware.org/?probe=a58fbe3576) | Oct 30, 2023 |
| HP            | EliteBook 8560w             | [cd7ef88b8a](https://linux-hardware.org/?probe=cd7ef88b8a) | Oct 30, 2023 |
| HP            | EliteBook 840 G6            | [b113709ec2](https://linux-hardware.org/?probe=b113709ec2) | Oct 29, 2023 |
| Dell          | XPS 13 9300                 | [f8df9730e1](https://linux-hardware.org/?probe=f8df9730e1) | Oct 29, 2023 |
| HP            | Notebook                    | [79843ed7c3](https://linux-hardware.org/?probe=79843ed7c3) | Oct 29, 2023 |
| Acer          | Aspire 4820TG               | [a72ac510df](https://linux-hardware.org/?probe=a72ac510df) | Oct 29, 2023 |
| Dell          | Vostro 15 3515              | [3d2fe89bc1](https://linux-hardware.org/?probe=3d2fe89bc1) | Oct 29, 2023 |
| Lenovo        | ThinkPad T480 20L5000AIX    | [65b2874cbb](https://linux-hardware.org/?probe=65b2874cbb) | Oct 28, 2023 |
| HP            | Notebook                    | [791dfef3cc](https://linux-hardware.org/?probe=791dfef3cc) | Oct 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [b65d7d3b4a](https://linux-hardware.org/?probe=b65d7d3b4a) | Oct 28, 2023 |
| HP            | Laptop 15s-fq0xxx           | [e3154e94cf](https://linux-hardware.org/?probe=e3154e94cf) | Oct 28, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [198bee98eb](https://linux-hardware.org/?probe=198bee98eb) | Oct 27, 2023 |
| Apple         | MacBook7,1                  | [61b133ac1e](https://linux-hardware.org/?probe=61b133ac1e) | Oct 27, 2023 |
| HP            | 15                          | [a9e38be5d5](https://linux-hardware.org/?probe=a9e38be5d5) | Oct 27, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [1971a346bf](https://linux-hardware.org/?probe=1971a346bf) | Oct 27, 2023 |
| Apple         | MacBookPro6,2               | [af9b5b05e9](https://linux-hardware.org/?probe=af9b5b05e9) | Oct 26, 2023 |
| Lenovo        | ThinkPad T540p 20BE00B4I... | [afce107e0d](https://linux-hardware.org/?probe=afce107e0d) | Oct 26, 2023 |
| ASUSTek       | X505BP                      | [884529eef1](https://linux-hardware.org/?probe=884529eef1) | Oct 26, 2023 |
| ASUSTek       | X505BP                      | [f32e8922c8](https://linux-hardware.org/?probe=f32e8922c8) | Oct 26, 2023 |
| Acer          | Nitro AN515-58              | [f956ab0313](https://linux-hardware.org/?probe=f956ab0313) | Oct 26, 2023 |
| Chuwi         | GemiBook Pro                | [e2900eda68](https://linux-hardware.org/?probe=e2900eda68) | Oct 26, 2023 |
| ASUSTek       | X555LAB                     | [a8b1ad0f53](https://linux-hardware.org/?probe=a8b1ad0f53) | Oct 25, 2023 |
| HP            | 15                          | [629c50d53a](https://linux-hardware.org/?probe=629c50d53a) | Oct 25, 2023 |
| Acer          | Aspire 5739G                | [21f871b008](https://linux-hardware.org/?probe=21f871b008) | Oct 25, 2023 |
| ASUSTek       | X550LD                      | [cb2e25f26f](https://linux-hardware.org/?probe=cb2e25f26f) | Oct 25, 2023 |
| Dell          | Vostro 15 3515              | [5713b2f30e](https://linux-hardware.org/?probe=5713b2f30e) | Oct 24, 2023 |
| Packard Be... | EasyNote LE69KB             | [3626d833e9](https://linux-hardware.org/?probe=3626d833e9) | Oct 24, 2023 |
| Acer          | Aspire 5738                 | [0abcd8d89e](https://linux-hardware.org/?probe=0abcd8d89e) | Oct 24, 2023 |
| Acer          | Aspire 5738                 | [fb6910c3c6](https://linux-hardware.org/?probe=fb6910c3c6) | Oct 24, 2023 |
| Acer          | Aspire 5738                 | [039878b1b2](https://linux-hardware.org/?probe=039878b1b2) | Oct 24, 2023 |
| Dell          | Vostro 3420                 | [e51b3ff063](https://linux-hardware.org/?probe=e51b3ff063) | Oct 24, 2023 |
| HP            | EliteBook 8740w             | [3669a01d21](https://linux-hardware.org/?probe=3669a01d21) | Oct 24, 2023 |
| ASUSTek       | K56CM                       | [a5437fcab8](https://linux-hardware.org/?probe=a5437fcab8) | Oct 24, 2023 |
| Acer          | Extensa 5220                | [eda0099ab4](https://linux-hardware.org/?probe=eda0099ab4) | Oct 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [dc730f5631](https://linux-hardware.org/?probe=dc730f5631) | Oct 23, 2023 |
| Acer          | Nitro AN515-45              | [61791a9250](https://linux-hardware.org/?probe=61791a9250) | Oct 23, 2023 |
| ASUSTek       | X555YI                      | [0028f82c4d](https://linux-hardware.org/?probe=0028f82c4d) | Oct 23, 2023 |
| Dell          | XPS 9315                    | [d04399e8fd](https://linux-hardware.org/?probe=d04399e8fd) | Oct 23, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [7981b12a61](https://linux-hardware.org/?probe=7981b12a61) | Oct 22, 2023 |
| Dell          | XPS 9315                    | [e3c5d45e2a](https://linux-hardware.org/?probe=e3c5d45e2a) | Oct 22, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [c725f222a3](https://linux-hardware.org/?probe=c725f222a3) | Oct 22, 2023 |
| Dell          | Latitude E5450              | [0f5e45f8e4](https://linux-hardware.org/?probe=0f5e45f8e4) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3431e88cbe](https://linux-hardware.org/?probe=3431e88cbe) | Oct 22, 2023 |
| ASUSTek       | X200MA                      | [41f4b8a93a](https://linux-hardware.org/?probe=41f4b8a93a) | Oct 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [943199c6c3](https://linux-hardware.org/?probe=943199c6c3) | Oct 21, 2023 |
| LG Electro... | 17Z90R-G.AP78D              | [8d320eb314](https://linux-hardware.org/?probe=8d320eb314) | Oct 21, 2023 |
| Acer          | Nitro AN515-52              | [081a658255](https://linux-hardware.org/?probe=081a658255) | Oct 21, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [f103762ce5](https://linux-hardware.org/?probe=f103762ce5) | Oct 21, 2023 |
| Acer          | Aspire A315-23              | [147d6ad175](https://linux-hardware.org/?probe=147d6ad175) | Oct 21, 2023 |
| Samsung       | R530/R730/P590              | [6a774fbae7](https://linux-hardware.org/?probe=6a774fbae7) | Oct 21, 2023 |
| Acer          | Swift SF315-41              | [23c9a3dea4](https://linux-hardware.org/?probe=23c9a3dea4) | Oct 20, 2023 |
| Dell          | Latitude 7280               | [ec9e688b4e](https://linux-hardware.org/?probe=ec9e688b4e) | Oct 20, 2023 |
| Acer          | Aspire A114-33              | [34ffce7f83](https://linux-hardware.org/?probe=34ffce7f83) | Oct 20, 2023 |
| Dell          | Latitude 7280               | [3b88974986](https://linux-hardware.org/?probe=3b88974986) | Oct 20, 2023 |
| Lenovo        | ThinkPad T470 20HES4VB00    | [423a16c64a](https://linux-hardware.org/?probe=423a16c64a) | Oct 20, 2023 |
| Acer          | AOD270                      | [20d5a5477c](https://linux-hardware.org/?probe=20d5a5477c) | Oct 19, 2023 |
| HP            | Pavilion dv6                | [d5669e2ea8](https://linux-hardware.org/?probe=d5669e2ea8) | Oct 19, 2023 |
| Samsung       | 700T1C                      | [f5668a0ef6](https://linux-hardware.org/?probe=f5668a0ef6) | Oct 19, 2023 |
| Sony          | SVE1713X1EB                 | [ec015a6c9e](https://linux-hardware.org/?probe=ec015a6c9e) | Oct 19, 2023 |
| Dell          | Latitude E7270              | [673245c691](https://linux-hardware.org/?probe=673245c691) | Oct 19, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [d906262d01](https://linux-hardware.org/?probe=d906262d01) | Oct 18, 2023 |
| Acer          | TravelMate 5720             | [8902ce3049](https://linux-hardware.org/?probe=8902ce3049) | Oct 18, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [7aded01681](https://linux-hardware.org/?probe=7aded01681) | Oct 17, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [42292e1deb](https://linux-hardware.org/?probe=42292e1deb) | Oct 17, 2023 |
| LG Electro... | 17Z90P-G.AA86D              | [afffdd63b5](https://linux-hardware.org/?probe=afffdd63b5) | Oct 17, 2023 |
| ASUSTek       | ROG Strix G614JU_G614JU     | [bb50abd0e6](https://linux-hardware.org/?probe=bb50abd0e6) | Oct 17, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [f3bd5c6632](https://linux-hardware.org/?probe=f3bd5c6632) | Oct 17, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [843098c658](https://linux-hardware.org/?probe=843098c658) | Oct 17, 2023 |
| Dell          | Inspiron 1545               | [87edaec977](https://linux-hardware.org/?probe=87edaec977) | Oct 17, 2023 |
| Dell          | XPS 9315                    | [e629bbd153](https://linux-hardware.org/?probe=e629bbd153) | Oct 16, 2023 |
| Dell          | XPS 9315                    | [a0b5099438](https://linux-hardware.org/?probe=a0b5099438) | Oct 16, 2023 |
| ASUSTek       | ROG Strix G614JU_G614JU     | [ddeaca23b4](https://linux-hardware.org/?probe=ddeaca23b4) | Oct 16, 2023 |
| HP            | 250 G4                      | [a45d8a13df](https://linux-hardware.org/?probe=a45d8a13df) | Oct 16, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21HK... | [3b0d979b69](https://linux-hardware.org/?probe=3b0d979b69) | Oct 16, 2023 |
| Lenovo        | ThinkPad T450 20BUS1K50X    | [11ccdc870b](https://linux-hardware.org/?probe=11ccdc870b) | Oct 16, 2023 |
| ASUSTek       | X541UV                      | [c5183a57ce](https://linux-hardware.org/?probe=c5183a57ce) | Oct 16, 2023 |
| HP            | 255 G6 Notebook PC          | [5cc901b874](https://linux-hardware.org/?probe=5cc901b874) | Oct 15, 2023 |
| Toshiba       | Satellite L655              | [9bda720e30](https://linux-hardware.org/?probe=9bda720e30) | Oct 15, 2023 |
| LG Electro... | 14Z990-V.AR52D              | [9e7942d027](https://linux-hardware.org/?probe=9e7942d027) | Oct 15, 2023 |
| Lenovo        | ThinkPad T480 20L5000AIX    | [c7b57a58b7](https://linux-hardware.org/?probe=c7b57a58b7) | Oct 15, 2023 |
| HP            | Compaq 610                  | [78e999ba70](https://linux-hardware.org/?probe=78e999ba70) | Oct 15, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [88c47cfb66](https://linux-hardware.org/?probe=88c47cfb66) | Oct 15, 2023 |
| HP            | 15                          | [7cde663ae0](https://linux-hardware.org/?probe=7cde663ae0) | Oct 15, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [cf68d0c810](https://linux-hardware.org/?probe=cf68d0c810) | Oct 14, 2023 |
| ASUSTek       | X550LA                      | [0d7a699d73](https://linux-hardware.org/?probe=0d7a699d73) | Oct 14, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [d83bb1e709](https://linux-hardware.org/?probe=d83bb1e709) | Oct 14, 2023 |
| HP            | ENVY dv7                    | [0972d8543e](https://linux-hardware.org/?probe=0972d8543e) | Oct 14, 2023 |
| HP            | Laptop 15-dw0xxx            | [b7a193296f](https://linux-hardware.org/?probe=b7a193296f) | Oct 14, 2023 |
| HP            | 15                          | [f5392b4484](https://linux-hardware.org/?probe=f5392b4484) | Oct 14, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [08a6026b21](https://linux-hardware.org/?probe=08a6026b21) | Oct 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [a4dfa6f17f](https://linux-hardware.org/?probe=a4dfa6f17f) | Oct 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [c97af886ef](https://linux-hardware.org/?probe=c97af886ef) | Oct 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [abc976eaa0](https://linux-hardware.org/?probe=abc976eaa0) | Oct 12, 2023 |
| MSI           | Modern 15 A11M              | [33272a00fb](https://linux-hardware.org/?probe=33272a00fb) | Oct 12, 2023 |
| Apple         | MacBookPro5,4               | [6d6f3a40a8](https://linux-hardware.org/?probe=6d6f3a40a8) | Oct 12, 2023 |
| Apple         | MacBookAir6,1               | [906af55718](https://linux-hardware.org/?probe=906af55718) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [8368fe3d29](https://linux-hardware.org/?probe=8368fe3d29) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [d2e39b2cdd](https://linux-hardware.org/?probe=d2e39b2cdd) | Oct 12, 2023 |
| ASUSTek       | X541UJ                      | [c061e67481](https://linux-hardware.org/?probe=c061e67481) | Oct 12, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [53d9601d40](https://linux-hardware.org/?probe=53d9601d40) | Oct 12, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [f48331f12b](https://linux-hardware.org/?probe=f48331f12b) | Oct 12, 2023 |
| Dell          | Latitude E6430              | [802b70a3c0](https://linux-hardware.org/?probe=802b70a3c0) | Oct 11, 2023 |
| ASUSTek       | X541UJ                      | [0cb7dbb73b](https://linux-hardware.org/?probe=0cb7dbb73b) | Oct 11, 2023 |
| Acer          | Predator PH315-54           | [552e952ebe](https://linux-hardware.org/?probe=552e952ebe) | Oct 11, 2023 |
| Acer          | AOD270                      | [b45399c83c](https://linux-hardware.org/?probe=b45399c83c) | Oct 11, 2023 |
| Acer          | TravelMate P258-M           | [eefce4c3ad](https://linux-hardware.org/?probe=eefce4c3ad) | Oct 11, 2023 |
| Dell          | Vostro 5402                 | [f23d8804a7](https://linux-hardware.org/?probe=f23d8804a7) | Oct 11, 2023 |
| HP            | 15                          | [5dc6c32647](https://linux-hardware.org/?probe=5dc6c32647) | Oct 10, 2023 |
| Dell          | Latitude E5440              | [2f6ed33823](https://linux-hardware.org/?probe=2f6ed33823) | Oct 10, 2023 |
| Dell          | Latitude E5440              | [90b9b12b1b](https://linux-hardware.org/?probe=90b9b12b1b) | Oct 10, 2023 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | [ee4617fa73](https://linux-hardware.org/?probe=ee4617fa73) | Oct 10, 2023 |
| Lenovo        | ThinkPad P50 20EQS4QL11     | [a4d6af03fe](https://linux-hardware.org/?probe=a4d6af03fe) | Oct 10, 2023 |
| Dell          | Latitude 5530               | [95ec4384f9](https://linux-hardware.org/?probe=95ec4384f9) | Oct 10, 2023 |
| Dell          | Latitude 5530               | [4d218edfa4](https://linux-hardware.org/?probe=4d218edfa4) | Oct 10, 2023 |
| ASUSTek       | N751JK                      | [855d2e95a7](https://linux-hardware.org/?probe=855d2e95a7) | Oct 09, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [e4158a4175](https://linux-hardware.org/?probe=e4158a4175) | Oct 08, 2023 |
| Insyde        | Braswell                    | [c4261097f5](https://linux-hardware.org/?probe=c4261097f5) | Oct 07, 2023 |
| Dell          | Inspiron 3542               | [90f777d9cc](https://linux-hardware.org/?probe=90f777d9cc) | Oct 07, 2023 |
| HP            | ENVY 15                     | [082502c7d2](https://linux-hardware.org/?probe=082502c7d2) | Oct 07, 2023 |
| ASUSTek       | K50ID                       | [2763bfac4e](https://linux-hardware.org/?probe=2763bfac4e) | Oct 07, 2023 |
| ASUSTek       | T100TAS                     | [f6a5a046b6](https://linux-hardware.org/?probe=f6a5a046b6) | Oct 07, 2023 |
| ASUSTek       | T100TAS                     | [c7e6160070](https://linux-hardware.org/?probe=c7e6160070) | Oct 07, 2023 |
| Acer          | Swift SF313-52G             | [754ae78e39](https://linux-hardware.org/?probe=754ae78e39) | Oct 07, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [797b40c01f](https://linux-hardware.org/?probe=797b40c01f) | Oct 06, 2023 |
| HP            | 255 G4                      | [7097fff4ee](https://linux-hardware.org/?probe=7097fff4ee) | Oct 06, 2023 |
| HP            | EliteBook 840 G6            | [e8ae378997](https://linux-hardware.org/?probe=e8ae378997) | Oct 06, 2023 |
| Lenovo        | ThinkPad 3354DSG            | [4eb8d1761d](https://linux-hardware.org/?probe=4eb8d1761d) | Oct 06, 2023 |
| Acer          | Aspire 7730G                | [d48f861a2e](https://linux-hardware.org/?probe=d48f861a2e) | Oct 05, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | [0b0a1ecd08](https://linux-hardware.org/?probe=0b0a1ecd08) | Oct 05, 2023 |
| Notebook      | N150ZU                      | [cbaeef6994](https://linux-hardware.org/?probe=cbaeef6994) | Oct 05, 2023 |
| Notebook      | N150ZU                      | [3a555e095f](https://linux-hardware.org/?probe=3a555e095f) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [01f88bafa7](https://linux-hardware.org/?probe=01f88bafa7) | Oct 05, 2023 |
| Dell          | Latitude 5520               | [5b2909c7d8](https://linux-hardware.org/?probe=5b2909c7d8) | Oct 05, 2023 |
| Sony          | SVE1513Q1ESI                | [7cb96797da](https://linux-hardware.org/?probe=7cb96797da) | Oct 05, 2023 |
| HUAWEI        | BOM-WXX9                    | [3a3bc85a18](https://linux-hardware.org/?probe=3a3bc85a18) | Oct 05, 2023 |
| Acer          | Swift SF313-52G             | [9ccfff9167](https://linux-hardware.org/?probe=9ccfff9167) | Oct 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [480ca730da](https://linux-hardware.org/?probe=480ca730da) | Oct 05, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [e656c80657](https://linux-hardware.org/?probe=e656c80657) | Oct 05, 2023 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | [f74e0492f6](https://linux-hardware.org/?probe=f74e0492f6) | Oct 04, 2023 |
| Dell          | Vostro 15 3510              | [82f0da4421](https://linux-hardware.org/?probe=82f0da4421) | Oct 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [f8f606f04f](https://linux-hardware.org/?probe=f8f606f04f) | Oct 03, 2023 |
| Notebook      | W65_67SJ                    | [4de813ee21](https://linux-hardware.org/?probe=4de813ee21) | Oct 03, 2023 |
| ASUSTek       | K52JT                       | [30a087cc37](https://linux-hardware.org/?probe=30a087cc37) | Oct 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [98961e6b78](https://linux-hardware.org/?probe=98961e6b78) | Oct 03, 2023 |
| HUAWEI        | KLVD-WXX9                   | [b4dc684d6a](https://linux-hardware.org/?probe=b4dc684d6a) | Oct 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8e0792976d](https://linux-hardware.org/?probe=8e0792976d) | Oct 03, 2023 |
| Toshiba       | Satellite P850              | [4074b6cda1](https://linux-hardware.org/?probe=4074b6cda1) | Oct 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | [9637400928](https://linux-hardware.org/?probe=9637400928) | Oct 02, 2023 |
| Sony          | SVE1713X1EB                 | [ca5985274a](https://linux-hardware.org/?probe=ca5985274a) | Oct 02, 2023 |
| Fujitsu       | LIFEBOOK A357               | [6f11536a5f](https://linux-hardware.org/?probe=6f11536a5f) | Oct 02, 2023 |
| Panasonic     | CF-F9KWPZFFE                | [33cf16d622](https://linux-hardware.org/?probe=33cf16d622) | Oct 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [be49d6acd9](https://linux-hardware.org/?probe=be49d6acd9) | Oct 01, 2023 |
| HONOR         | HLYL-WXX9                   | [5a440c873d](https://linux-hardware.org/?probe=5a440c873d) | Oct 01, 2023 |
| HUAWEI        | KLVD-WXX9                   | [a566eb0467](https://linux-hardware.org/?probe=a566eb0467) | Oct 01, 2023 |
| HUAWEI        | VLT-WX0                     | [6778af4012](https://linux-hardware.org/?probe=6778af4012) | Oct 01, 2023 |
| HP            | 250 G4                      | [30947c6039](https://linux-hardware.org/?probe=30947c6039) | Oct 01, 2023 |
| Dell          | Vostro 3560                 | [9acebbf655](https://linux-hardware.org/?probe=9acebbf655) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | [8db3bb5b34](https://linux-hardware.org/?probe=8db3bb5b34) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ef74c51c65](https://linux-hardware.org/?probe=ef74c51c65) | Oct 01, 2023 |
| HUAWEI        | VLT-WX0                     | [a312a57d16](https://linux-hardware.org/?probe=a312a57d16) | Sep 30, 2023 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [58552d0532](https://linux-hardware.org/?probe=58552d0532) | Sep 30, 2023 |
| Toshiba       | Satellite L500              | [9c1b258088](https://linux-hardware.org/?probe=9c1b258088) | Sep 30, 2023 |
| Dell          | Latitude 7390               | [bd6d90d41e](https://linux-hardware.org/?probe=bd6d90d41e) | Sep 30, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [703170e428](https://linux-hardware.org/?probe=703170e428) | Sep 30, 2023 |
| eMachines     | eME732Z                     | [ba03824830](https://linux-hardware.org/?probe=ba03824830) | Sep 29, 2023 |
| Dell          | Latitude 7490               | [a22e4e9304](https://linux-hardware.org/?probe=a22e4e9304) | Sep 29, 2023 |
| MSI           | Prestige 15 A12SC           | [d78d241946](https://linux-hardware.org/?probe=d78d241946) | Sep 29, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [eef8975f1e](https://linux-hardware.org/?probe=eef8975f1e) | Sep 29, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [99fb3ec5e9](https://linux-hardware.org/?probe=99fb3ec5e9) | Sep 29, 2023 |
| Acer          | Aspire E1-570G              | [17584cef15](https://linux-hardware.org/?probe=17584cef15) | Sep 28, 2023 |
| MSI           | GL73 8RE                    | [670f7351b5](https://linux-hardware.org/?probe=670f7351b5) | Sep 28, 2023 |
| HP            | Laptop 15s-fq0xxx           | [4c1a2e1e21](https://linux-hardware.org/?probe=4c1a2e1e21) | Sep 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [78b1c422c7](https://linux-hardware.org/?probe=78b1c422c7) | Sep 28, 2023 |
| HP            | EliteBook 840 G6            | [5b87382fce](https://linux-hardware.org/?probe=5b87382fce) | Sep 28, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [6fc52a277a](https://linux-hardware.org/?probe=6fc52a277a) | Sep 28, 2023 |
| AMI           | Cherry Trail CR             | [41b2d006c1](https://linux-hardware.org/?probe=41b2d006c1) | Sep 27, 2023 |
| AMI           | Cherry Trail CR             | [050c423c6b](https://linux-hardware.org/?probe=050c423c6b) | Sep 27, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | [e87c0e3c00](https://linux-hardware.org/?probe=e87c0e3c00) | Sep 27, 2023 |
| HP            | Laptop 15-bw0xx             | [ba7c544fbb](https://linux-hardware.org/?probe=ba7c544fbb) | Sep 26, 2023 |
| Samsung       | R519/R719                   | [15ae7c9603](https://linux-hardware.org/?probe=15ae7c9603) | Sep 26, 2023 |
| HP            | 250 G4                      | [6e475cbb1f](https://linux-hardware.org/?probe=6e475cbb1f) | Sep 25, 2023 |
| HP            | 250 G4                      | [9543354fea](https://linux-hardware.org/?probe=9543354fea) | Sep 25, 2023 |
| Samsung       | 750XDA                      | [dd03d00004](https://linux-hardware.org/?probe=dd03d00004) | Sep 25, 2023 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [7ea3152d65](https://linux-hardware.org/?probe=7ea3152d65) | Sep 25, 2023 |
| HP            | 255 G8 Notebook PC          | [38b5be59cc](https://linux-hardware.org/?probe=38b5be59cc) | Sep 25, 2023 |
| HP            | 255 G8 Notebook PC          | [91c3333a18](https://linux-hardware.org/?probe=91c3333a18) | Sep 25, 2023 |
| Dell          | Vostro 1000                 | [38499a1a0f](https://linux-hardware.org/?probe=38499a1a0f) | Sep 25, 2023 |
| Dell          | Vostro 15 3510              | [e8868c236d](https://linux-hardware.org/?probe=e8868c236d) | Sep 25, 2023 |
| Dell          | Vostro 15 3510              | [eaa5061963](https://linux-hardware.org/?probe=eaa5061963) | Sep 25, 2023 |
| TUXEDO        | Unknown                     | [6746de397a](https://linux-hardware.org/?probe=6746de397a) | Sep 25, 2023 |
| ASUSTek       | X553MA                      | [b6b370953d](https://linux-hardware.org/?probe=b6b370953d) | Sep 24, 2023 |
| ASUSTek       | X553MA                      | [78977336f9](https://linux-hardware.org/?probe=78977336f9) | Sep 24, 2023 |
| Acer          | Aspire 5734Z                | [d5219dbfbe](https://linux-hardware.org/?probe=d5219dbfbe) | Sep 24, 2023 |
| HUAWEI        | BOD-WXX9                    | [e688665729](https://linux-hardware.org/?probe=e688665729) | Sep 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [234fc6a6fb](https://linux-hardware.org/?probe=234fc6a6fb) | Sep 24, 2023 |
| HP            | EliteBook 6930p (KK082AV... | [5e61b319b6](https://linux-hardware.org/?probe=5e61b319b6) | Sep 23, 2023 |
| AMI           | Intel                       | [ebb3577023](https://linux-hardware.org/?probe=ebb3577023) | Sep 23, 2023 |
| HP            | Pavilion dv6                | [bd8ae0385b](https://linux-hardware.org/?probe=bd8ae0385b) | Sep 23, 2023 |
| Apple         | MacBookPro11,1              | [e9478deeae](https://linux-hardware.org/?probe=e9478deeae) | Sep 23, 2023 |
| HP            | 255 G8 Notebook PC          | [7fcb0a9529](https://linux-hardware.org/?probe=7fcb0a9529) | Sep 23, 2023 |
| ASUSTek       | X510UQR                     | [364ee59aef](https://linux-hardware.org/?probe=364ee59aef) | Sep 23, 2023 |
| HP            | Compaq Presario CQ60        | [ae8071638f](https://linux-hardware.org/?probe=ae8071638f) | Sep 23, 2023 |
| HP            | Laptop 15-dw1xxx            | [be4a46768b](https://linux-hardware.org/?probe=be4a46768b) | Sep 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [830bf573b1](https://linux-hardware.org/?probe=830bf573b1) | Sep 23, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [574c2193bb](https://linux-hardware.org/?probe=574c2193bb) | Sep 23, 2023 |
| TUXEDO        | Unknown                     | [07870d9c20](https://linux-hardware.org/?probe=07870d9c20) | Sep 22, 2023 |
| HP            | Pavilion dv6                | [270b0c0878](https://linux-hardware.org/?probe=270b0c0878) | Sep 21, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [3cd9b7841a](https://linux-hardware.org/?probe=3cd9b7841a) | Sep 21, 2023 |
| HP            | 250 G7 Notebook PC          | [cc25c24fa5](https://linux-hardware.org/?probe=cc25c24fa5) | Sep 21, 2023 |
| HP            | 15                          | [d0ddd6fbc9](https://linux-hardware.org/?probe=d0ddd6fbc9) | Sep 21, 2023 |
| HP            | 255 G8 Notebook PC          | [d92a4fb2af](https://linux-hardware.org/?probe=d92a4fb2af) | Sep 21, 2023 |
| MSI           | Katana GF66 11UC            | [20dfeb32a2](https://linux-hardware.org/?probe=20dfeb32a2) | Sep 21, 2023 |
| MSI           | Summit E13FlipEvo A12MT     | [bd096f1ae3](https://linux-hardware.org/?probe=bd096f1ae3) | Sep 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [79111191a0](https://linux-hardware.org/?probe=79111191a0) | Sep 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ca0ad87f0b](https://linux-hardware.org/?probe=ca0ad87f0b) | Sep 19, 2023 |
| Dell          | Latitude E5450              | [6f16759400](https://linux-hardware.org/?probe=6f16759400) | Sep 19, 2023 |
| HP            | 255 G8 Notebook PC          | [c2cd300139](https://linux-hardware.org/?probe=c2cd300139) | Sep 19, 2023 |
| HP            | 15                          | [b016d5ee79](https://linux-hardware.org/?probe=b016d5ee79) | Sep 18, 2023 |
| Lenovo        | Z50-75 80EC                 | [e14140ad96](https://linux-hardware.org/?probe=e14140ad96) | Sep 18, 2023 |
| ASUSTek       | X550LD                      | [a466adc807](https://linux-hardware.org/?probe=a466adc807) | Sep 17, 2023 |
| ASUSTek       | S551LN                      | [50ad376e75](https://linux-hardware.org/?probe=50ad376e75) | Sep 17, 2023 |
| HP            | Pavilion 15                 | [c16424732a](https://linux-hardware.org/?probe=c16424732a) | Sep 17, 2023 |
| HP            | Pavilion 15                 | [47df3b9a6e](https://linux-hardware.org/?probe=47df3b9a6e) | Sep 17, 2023 |
| Toshiba       | Satellite Pro R50-B         | [e3a895eaa7](https://linux-hardware.org/?probe=e3a895eaa7) | Sep 17, 2023 |
| Lenovo        | ThinkPad X220 4290LT8       | [56d2386012](https://linux-hardware.org/?probe=56d2386012) | Sep 17, 2023 |
| HP            | 250 G1                      | [0e052c1de2](https://linux-hardware.org/?probe=0e052c1de2) | Sep 17, 2023 |
| ASUSTek       | X540SA                      | [68bc662ac9](https://linux-hardware.org/?probe=68bc662ac9) | Sep 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [bf532ab6ec](https://linux-hardware.org/?probe=bf532ab6ec) | Sep 16, 2023 |
| Lenovo        | IdeaPad Z500 5931           | [8de8aa75cc](https://linux-hardware.org/?probe=8de8aa75cc) | Sep 16, 2023 |
| Lenovo        | IdeaPad Z500 5931           | [0986123aac](https://linux-hardware.org/?probe=0986123aac) | Sep 16, 2023 |
| Acer          | Aspire E1-522               | [cbc5e29bf6](https://linux-hardware.org/?probe=cbc5e29bf6) | Sep 16, 2023 |
| HP            | 250 G7 Notebook PC          | [72503b214c](https://linux-hardware.org/?probe=72503b214c) | Sep 16, 2023 |
| Acer          | TravelMate 5335             | [d440c12063](https://linux-hardware.org/?probe=d440c12063) | Sep 16, 2023 |
| HP            | 15                          | [636b9a80a1](https://linux-hardware.org/?probe=636b9a80a1) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [98dbf213e7](https://linux-hardware.org/?probe=98dbf213e7) | Sep 15, 2023 |
| Apple         | MacBookAir7,2               | [2b5ed25fd3](https://linux-hardware.org/?probe=2b5ed25fd3) | Sep 15, 2023 |
| Apple         | MacBookAir7,2               | [5bb7230963](https://linux-hardware.org/?probe=5bb7230963) | Sep 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | [66b29aeb1d](https://linux-hardware.org/?probe=66b29aeb1d) | Sep 15, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | [3eb787f2ec](https://linux-hardware.org/?probe=3eb787f2ec) | Sep 15, 2023 |
| ASUSTek       | UX530UX                     | [8651a15c57](https://linux-hardware.org/?probe=8651a15c57) | Sep 14, 2023 |
| Fujitsu       | LIFEBOOK A357               | [a02233b901](https://linux-hardware.org/?probe=a02233b901) | Sep 14, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | [4f6e19f508](https://linux-hardware.org/?probe=4f6e19f508) | Sep 14, 2023 |
| HP            | ENVY Laptop 17-ch0xxx       | [e7463cdeb1](https://linux-hardware.org/?probe=e7463cdeb1) | Sep 14, 2023 |
| ASUSTek       | X556URK                     | [0996de9eac](https://linux-hardware.org/?probe=0996de9eac) | Sep 14, 2023 |
| Acer          | Swift SF113-31              | [f165d66761](https://linux-hardware.org/?probe=f165d66761) | Sep 14, 2023 |
| HP            | x2 210                      | [776f895eec](https://linux-hardware.org/?probe=776f895eec) | Sep 13, 2023 |
| Dell          | Latitude 3420               | [e78cbe0564](https://linux-hardware.org/?probe=e78cbe0564) | Sep 13, 2023 |
| HP            | Pavilion dv6                | [2174e236d6](https://linux-hardware.org/?probe=2174e236d6) | Sep 13, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [52a1dc1e19](https://linux-hardware.org/?probe=52a1dc1e19) | Sep 12, 2023 |
| Sony          | SVE1713X1EB                 | [2284d8a2dd](https://linux-hardware.org/?probe=2284d8a2dd) | Sep 12, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [4715a2425e](https://linux-hardware.org/?probe=4715a2425e) | Sep 12, 2023 |
| MSI           | GL73 8RE                    | [dca28b0d09](https://linux-hardware.org/?probe=dca28b0d09) | Sep 12, 2023 |
| MSI           | GL73 8RE                    | [6c6c4a19ec](https://linux-hardware.org/?probe=6c6c4a19ec) | Sep 12, 2023 |
| Lenovo        | V15-IGL 82C3                | [b6c8bbb82f](https://linux-hardware.org/?probe=b6c8bbb82f) | Sep 12, 2023 |
| Dell          | Inspiron 5748               | [afa0844d9f](https://linux-hardware.org/?probe=afa0844d9f) | Sep 11, 2023 |
| HUAWEI        | MACHC-WAX9                  | [3cafef18bf](https://linux-hardware.org/?probe=3cafef18bf) | Sep 11, 2023 |
| HP            | 250 G3                      | [162574954f](https://linux-hardware.org/?probe=162574954f) | Sep 11, 2023 |
| HP            | Pavilion zd8000 (EF038EA... | [f58cbb99ad](https://linux-hardware.org/?probe=f58cbb99ad) | Sep 11, 2023 |
| HP            | Pavilion zd8000 (EF038EA... | [accb107fb0](https://linux-hardware.org/?probe=accb107fb0) | Sep 11, 2023 |
| Dell          | Inspiron 5515               | [a6c468e52d](https://linux-hardware.org/?probe=a6c468e52d) | Sep 10, 2023 |
| ASUSTek       | X550CC                      | [838e1d8f4a](https://linux-hardware.org/?probe=838e1d8f4a) | Sep 10, 2023 |
| MSI           | Modern 14 B11MOU            | [394bdfe7af](https://linux-hardware.org/?probe=394bdfe7af) | Sep 10, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21HK... | [511507697a](https://linux-hardware.org/?probe=511507697a) | Sep 10, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [e8f4b3bf42](https://linux-hardware.org/?probe=e8f4b3bf42) | Sep 09, 2023 |
| Google        | Rabbid                      | [c55be85343](https://linux-hardware.org/?probe=c55be85343) | Sep 09, 2023 |
| Acer          | Aspire E1-531               | [91decda3c9](https://linux-hardware.org/?probe=91decda3c9) | Sep 09, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [69458a43ef](https://linux-hardware.org/?probe=69458a43ef) | Sep 09, 2023 |
| Dell          | System Vostro 3750          | [00a11a78f5](https://linux-hardware.org/?probe=00a11a78f5) | Sep 09, 2023 |
| HP            | ProBook 650 G1              | [d46b2b90ec](https://linux-hardware.org/?probe=d46b2b90ec) | Sep 09, 2023 |
| LG Electro... | 14Z990-V.AR52D              | [9a0f106aa0](https://linux-hardware.org/?probe=9a0f106aa0) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5fc227a0e8](https://linux-hardware.org/?probe=5fc227a0e8) | Sep 08, 2023 |
| MSI           | Prestige 14Evo A12M         | [42ba1f73b8](https://linux-hardware.org/?probe=42ba1f73b8) | Sep 08, 2023 |
| HP            | 250 G3                      | [51ef1d34d0](https://linux-hardware.org/?probe=51ef1d34d0) | Sep 08, 2023 |
| ASUSTek       | X510UQ                      | [b838a2495b](https://linux-hardware.org/?probe=b838a2495b) | Sep 08, 2023 |
| Acer          | Nitro AN515-45              | [e7d0ece5a1](https://linux-hardware.org/?probe=e7d0ece5a1) | Sep 08, 2023 |
| Apple         | MacBookPro11,2              | [d6cfec3d58](https://linux-hardware.org/?probe=d6cfec3d58) | Sep 08, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [c9d6171716](https://linux-hardware.org/?probe=c9d6171716) | Sep 08, 2023 |
| Apple         | MacBookPro11,2              | [654a62e050](https://linux-hardware.org/?probe=654a62e050) | Sep 07, 2023 |
| Clevo         | M1100M                      | [399b796d9f](https://linux-hardware.org/?probe=399b796d9f) | Sep 06, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [0468bc91fc](https://linux-hardware.org/?probe=0468bc91fc) | Sep 06, 2023 |
| ASUSTek       | X555QG                      | [8cf63afc0f](https://linux-hardware.org/?probe=8cf63afc0f) | Sep 06, 2023 |
| TUXEDO        | Unknown                     | [1e6c412d84](https://linux-hardware.org/?probe=1e6c412d84) | Sep 06, 2023 |
| HP            | Notebook                    | [ad9bafda30](https://linux-hardware.org/?probe=ad9bafda30) | Sep 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | [03f6b3b62b](https://linux-hardware.org/?probe=03f6b3b62b) | Sep 06, 2023 |
| Sony          | SVE1712C5E                  | [a5c77b2450](https://linux-hardware.org/?probe=a5c77b2450) | Sep 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0fdeca1313](https://linux-hardware.org/?probe=0fdeca1313) | Sep 06, 2023 |
| Sony          | SVE1712C5E                  | [f864c8e44a](https://linux-hardware.org/?probe=f864c8e44a) | Sep 05, 2023 |
| Sony          | SVE1713X1EB                 | [f7c65dc902](https://linux-hardware.org/?probe=f7c65dc902) | Sep 05, 2023 |
| Notebook      | N9x0TC                      | [ea9c38200b](https://linux-hardware.org/?probe=ea9c38200b) | Sep 05, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [7619d8e5e8](https://linux-hardware.org/?probe=7619d8e5e8) | Sep 05, 2023 |
| Toshiba       | Satellite C850-1DZ          | [cf916c2f33](https://linux-hardware.org/?probe=cf916c2f33) | Sep 05, 2023 |
| ASUSTek       | K52JB                       | [7944dc4ca2](https://linux-hardware.org/?probe=7944dc4ca2) | Sep 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | [522dd175b1](https://linux-hardware.org/?probe=522dd175b1) | Sep 04, 2023 |
| HP            | Notebook                    | [9be8a6b0e7](https://linux-hardware.org/?probe=9be8a6b0e7) | Sep 03, 2023 |
| HP            | Notebook                    | [d038b7106e](https://linux-hardware.org/?probe=d038b7106e) | Sep 03, 2023 |
| HP            | 240 G8 Notebook PC          | [092ae0b34d](https://linux-hardware.org/?probe=092ae0b34d) | Sep 03, 2023 |
| HP            | Laptop 15s-eq3xxx           | [399abaa799](https://linux-hardware.org/?probe=399abaa799) | Sep 02, 2023 |
| Microtech     | ebookPro                    | [ce14e0ffeb](https://linux-hardware.org/?probe=ce14e0ffeb) | Sep 02, 2023 |
| HP            | Compaq Presario CQ61        | [0cd9e98276](https://linux-hardware.org/?probe=0cd9e98276) | Sep 02, 2023 |
| Chuwi         | LapBook Pro                 | [4dd222efaa](https://linux-hardware.org/?probe=4dd222efaa) | Sep 01, 2023 |
| Acer          | Aspire 5715Z                | [1cb91dff9e](https://linux-hardware.org/?probe=1cb91dff9e) | Sep 01, 2023 |
| Acer          | Extensa 5635Z               | [da70c2acd8](https://linux-hardware.org/?probe=da70c2acd8) | Sep 01, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | [b52faa8776](https://linux-hardware.org/?probe=b52faa8776) | Sep 01, 2023 |
| HP            | EliteBook 6930p             | [f40d8bbc73](https://linux-hardware.org/?probe=f40d8bbc73) | Sep 01, 2023 |
| ASUSTek       | S301LP                      | [d33b635602](https://linux-hardware.org/?probe=d33b635602) | Aug 31, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [a45654cfd8](https://linux-hardware.org/?probe=a45654cfd8) | Aug 31, 2023 |
| Notebook      | N9x0TC                      | [f37b35c8dc](https://linux-hardware.org/?probe=f37b35c8dc) | Aug 31, 2023 |
| HP            | EliteBook 840 14 inch G9... | [ec33c11aa1](https://linux-hardware.org/?probe=ec33c11aa1) | Aug 31, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0PA0... | [89caf6d252](https://linux-hardware.org/?probe=89caf6d252) | Aug 31, 2023 |
| ASUSTek       | GL753VD                     | [649fb869a6](https://linux-hardware.org/?probe=649fb869a6) | Aug 31, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [23242fe856](https://linux-hardware.org/?probe=23242fe856) | Aug 31, 2023 |
| Acer          | Aspire 1700                 | [a76fb24570](https://linux-hardware.org/?probe=a76fb24570) | Aug 31, 2023 |
| Lenovo        | ThinkPad T470 20HES0ET0R    | [65d003a7a0](https://linux-hardware.org/?probe=65d003a7a0) | Aug 30, 2023 |
| HP            | 255 G8 Notebook PC          | [92552fa038](https://linux-hardware.org/?probe=92552fa038) | Aug 30, 2023 |
| Dell          | Inspiron 7548               | [6b6a2e7632](https://linux-hardware.org/?probe=6b6a2e7632) | Aug 30, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [4ac0615cbb](https://linux-hardware.org/?probe=4ac0615cbb) | Aug 30, 2023 |
| Acer          | Swift SF314-52              | [4f6b648f42](https://linux-hardware.org/?probe=4f6b648f42) | Aug 30, 2023 |
| Dell          | Vostro 2520                 | [73ca89b4fa](https://linux-hardware.org/?probe=73ca89b4fa) | Aug 30, 2023 |
| HUAWEI        | KLVD-WXX9                   | [98262b8471](https://linux-hardware.org/?probe=98262b8471) | Aug 30, 2023 |
| Toshiba       | Satellite P850              | [a129c031fa](https://linux-hardware.org/?probe=a129c031fa) | Aug 29, 2023 |
| Dell          | Venue 11 Pro 5130           | [38c58406bc](https://linux-hardware.org/?probe=38c58406bc) | Aug 29, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [4bdfa8b9ea](https://linux-hardware.org/?probe=4bdfa8b9ea) | Aug 29, 2023 |
| Apple         | MacBookPro7,1               | [f520b2dd72](https://linux-hardware.org/?probe=f520b2dd72) | Aug 28, 2023 |
| Dell          | XPS 15 9510                 | [4b78bfab47](https://linux-hardware.org/?probe=4b78bfab47) | Aug 28, 2023 |
| HP            | Laptop 15s-fq0xxx           | [d0453c59f5](https://linux-hardware.org/?probe=d0453c59f5) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ded7284a37](https://linux-hardware.org/?probe=ded7284a37) | Aug 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6c54b2881a](https://linux-hardware.org/?probe=6c54b2881a) | Aug 27, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | [8c616e6421](https://linux-hardware.org/?probe=8c616e6421) | Aug 27, 2023 |
| HP            | 470 G8 Notebook PC          | [b725ab24df](https://linux-hardware.org/?probe=b725ab24df) | Aug 27, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [69a4a078cd](https://linux-hardware.org/?probe=69a4a078cd) | Aug 27, 2023 |
| Sony          | SVE1713X1EB                 | [ab8f75bb84](https://linux-hardware.org/?probe=ab8f75bb84) | Aug 27, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [2ee2c8dd6c](https://linux-hardware.org/?probe=2ee2c8dd6c) | Aug 26, 2023 |
| ASUSTek       | T100HAN                     | [73c5eff054](https://linux-hardware.org/?probe=73c5eff054) | Aug 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [caf8dd1fc3](https://linux-hardware.org/?probe=caf8dd1fc3) | Aug 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [3cce8305bb](https://linux-hardware.org/?probe=3cce8305bb) | Aug 26, 2023 |
| HP            | Compaq Presario CQ60        | [b407522eb0](https://linux-hardware.org/?probe=b407522eb0) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [3eea0be3b4](https://linux-hardware.org/?probe=3eea0be3b4) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [53ba2f91cd](https://linux-hardware.org/?probe=53ba2f91cd) | Aug 24, 2023 |
| Lenovo        | V15-IIL 82C5                | [fbe986e246](https://linux-hardware.org/?probe=fbe986e246) | Aug 24, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [5c956051fb](https://linux-hardware.org/?probe=5c956051fb) | Aug 24, 2023 |
| HP            | ENVY 15                     | [6367186102](https://linux-hardware.org/?probe=6367186102) | Aug 24, 2023 |
| Lenovo        | ThinkPad T430 2347DS4       | [cbaaad3882](https://linux-hardware.org/?probe=cbaaad3882) | Aug 24, 2023 |
| Acer          | Aspire 5750G                | [b7ab89701b](https://linux-hardware.org/?probe=b7ab89701b) | Aug 24, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | [e71571b95d](https://linux-hardware.org/?probe=e71571b95d) | Aug 24, 2023 |
| HP            | 250 G4                      | [1eb6dc4c12](https://linux-hardware.org/?probe=1eb6dc4c12) | Aug 23, 2023 |
| HP            | Pavilion x2 Detachable      | [a8fb075a9a](https://linux-hardware.org/?probe=a8fb075a9a) | Aug 23, 2023 |
| Acer          | TravelMate 7730G            | [e286f4c997](https://linux-hardware.org/?probe=e286f4c997) | Aug 23, 2023 |
| Dell          | Vostro 5471                 | [342ccb8530](https://linux-hardware.org/?probe=342ccb8530) | Aug 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [f56ee94116](https://linux-hardware.org/?probe=f56ee94116) | Aug 22, 2023 |
| Acer          | Nitro AN515-56              | [530e70e1ab](https://linux-hardware.org/?probe=530e70e1ab) | Aug 22, 2023 |
| MSI           | Katana GF66 12UC            | [6651fbd434](https://linux-hardware.org/?probe=6651fbd434) | Aug 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [285b51551c](https://linux-hardware.org/?probe=285b51551c) | Aug 22, 2023 |
| HP            | Pavilion dv6                | [10badbd20d](https://linux-hardware.org/?probe=10badbd20d) | Aug 22, 2023 |
| Acer          | Aspire A315-23              | [9b3a3cd47b](https://linux-hardware.org/?probe=9b3a3cd47b) | Aug 22, 2023 |
| HP            | 530                         | [2b631777d9](https://linux-hardware.org/?probe=2b631777d9) | Aug 22, 2023 |
| Sony          | SVE1713X1EB                 | [165cab2421](https://linux-hardware.org/?probe=165cab2421) | Aug 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [0baece8878](https://linux-hardware.org/?probe=0baece8878) | Aug 21, 2023 |
| MSI           | GL73 8RE                    | [6112b46746](https://linux-hardware.org/?probe=6112b46746) | Aug 21, 2023 |
| ASUSTek       | ROG Strix G713IE_G713IE     | [22443858cb](https://linux-hardware.org/?probe=22443858cb) | Aug 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [359cd5a655](https://linux-hardware.org/?probe=359cd5a655) | Aug 21, 2023 |
| MSI           | GL73 8RE                    | [b883100fd3](https://linux-hardware.org/?probe=b883100fd3) | Aug 21, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [b6f1a58560](https://linux-hardware.org/?probe=b6f1a58560) | Aug 20, 2023 |
| Lenovo        | ThinkPad X230 2325H50       | [65dd59e7d2](https://linux-hardware.org/?probe=65dd59e7d2) | Aug 20, 2023 |
| Acer          | Nitro AN515-56              | [45264bf6e6](https://linux-hardware.org/?probe=45264bf6e6) | Aug 20, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [8e91f085b4](https://linux-hardware.org/?probe=8e91f085b4) | Aug 20, 2023 |
| ASUSTek       | X540NA                      | [2f3758945b](https://linux-hardware.org/?probe=2f3758945b) | Aug 20, 2023 |
| HP            | Pavilion 15                 | [63e1b9e62c](https://linux-hardware.org/?probe=63e1b9e62c) | Aug 20, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | [01a44fbb3b](https://linux-hardware.org/?probe=01a44fbb3b) | Aug 20, 2023 |
| PC Special... | Ionico 16                   | [96fb68dc70](https://linux-hardware.org/?probe=96fb68dc70) | Aug 20, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [e33524b456](https://linux-hardware.org/?probe=e33524b456) | Aug 20, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [66c64c5da8](https://linux-hardware.org/?probe=66c64c5da8) | Aug 19, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [c19ed9405c](https://linux-hardware.org/?probe=c19ed9405c) | Aug 19, 2023 |
| Toshiba       | Satellite P850              | [8d00e88e1c](https://linux-hardware.org/?probe=8d00e88e1c) | Aug 19, 2023 |
| HP            | 250 G4 Notebook PC          | [ea6fdc81ab](https://linux-hardware.org/?probe=ea6fdc81ab) | Aug 18, 2023 |
| PC Special... | Ionico 16                   | [da33e8f1c1](https://linux-hardware.org/?probe=da33e8f1c1) | Aug 18, 2023 |
| Notebook      | NS50MU                      | [37abf5de2d](https://linux-hardware.org/?probe=37abf5de2d) | Aug 17, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [0438f450f4](https://linux-hardware.org/?probe=0438f450f4) | Aug 17, 2023 |
| HP            | Laptop 15s-fq5xxx           | [d3926b324c](https://linux-hardware.org/?probe=d3926b324c) | Aug 16, 2023 |
| Dell          | Latitude 5414               | [74b8020613](https://linux-hardware.org/?probe=74b8020613) | Aug 16, 2023 |
| Samsung       | RC530/RC730                 | [f9ce7b0ef5](https://linux-hardware.org/?probe=f9ce7b0ef5) | Aug 15, 2023 |
| Samsung       | RC530/RC730                 | [86f3ddda0c](https://linux-hardware.org/?probe=86f3ddda0c) | Aug 15, 2023 |
| Dell          | Inspiron 7590               | [4438df6adb](https://linux-hardware.org/?probe=4438df6adb) | Aug 15, 2023 |
| HP            | 15                          | [9b9e2459a8](https://linux-hardware.org/?probe=9b9e2459a8) | Aug 15, 2023 |
| HP            | ENVY 15                     | [caa5e1d37a](https://linux-hardware.org/?probe=caa5e1d37a) | Aug 14, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [6c7c115335](https://linux-hardware.org/?probe=6c7c115335) | Aug 14, 2023 |
| ASUSTek       | X553MA                      | [b2ee5cedbe](https://linux-hardware.org/?probe=b2ee5cedbe) | Aug 14, 2023 |
| ASUSTek       | N53SV                       | [8643d609f2](https://linux-hardware.org/?probe=8643d609f2) | Aug 14, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [246c60a344](https://linux-hardware.org/?probe=246c60a344) | Aug 13, 2023 |
| Dell          | Inspiron 5584               | [9fb83333a5](https://linux-hardware.org/?probe=9fb83333a5) | Aug 13, 2023 |
| Lenovo        | V130-15IKB 81HN             | [ca2c61168c](https://linux-hardware.org/?probe=ca2c61168c) | Aug 13, 2023 |
| HP            | 250 G8 Notebook PC          | [64a738d034](https://linux-hardware.org/?probe=64a738d034) | Aug 13, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [bb650e1dd2](https://linux-hardware.org/?probe=bb650e1dd2) | Aug 12, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [fb024a9374](https://linux-hardware.org/?probe=fb024a9374) | Aug 12, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [398f85e94a](https://linux-hardware.org/?probe=398f85e94a) | Aug 12, 2023 |
| HUAWEI        | BOD-WXX9                    | [b21e9793a5](https://linux-hardware.org/?probe=b21e9793a5) | Aug 11, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [8c449cd820](https://linux-hardware.org/?probe=8c449cd820) | Aug 11, 2023 |
| Dell          | Latitude 5300               | [661051063f](https://linux-hardware.org/?probe=661051063f) | Aug 10, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [9627b6d632](https://linux-hardware.org/?probe=9627b6d632) | Aug 10, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [099d1ac0de](https://linux-hardware.org/?probe=099d1ac0de) | Aug 10, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [51fa860c87](https://linux-hardware.org/?probe=51fa860c87) | Aug 09, 2023 |
| ASUSTek       | X510URR                     | [abf7479cb8](https://linux-hardware.org/?probe=abf7479cb8) | Aug 09, 2023 |
| Acer          | Aspire V3-112P              | [e6305472c5](https://linux-hardware.org/?probe=e6305472c5) | Aug 09, 2023 |
| Lenovo        | ThinkPad X240 20AL00C6UK    | [d33c586eab](https://linux-hardware.org/?probe=d33c586eab) | Aug 09, 2023 |
| Unknown       | Unknown                     | [5f186cbc4d](https://linux-hardware.org/?probe=5f186cbc4d) | Aug 09, 2023 |
| HP            | EliteBook 8470p             | [16acf13ed8](https://linux-hardware.org/?probe=16acf13ed8) | Aug 09, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 482       | 9.12%   |
| Ubuntu 22.04                 | 372       | 7.04%   |
| Ubuntu 18.04                 | 297       | 5.62%   |
| Arch Rolling                 | 200       | 3.78%   |
| Debian 11                    | 117       | 2.21%   |
| OpenMandriva 4.2             | 108       | 2.04%   |
| OpenMandriva 4.3             | 105       | 1.99%   |
| Fedora 36                    | 94        | 1.78%   |
| Pop!_OS 22.04                | 91        | 1.72%   |
| Linux Mint 21.1              | 83        | 1.57%   |
| EndeavourOS Rolling          | 80        | 1.51%   |
| Fedora 38                    | 79        | 1.49%   |
| Zorin 16                     | 77        | 1.46%   |
| Arch                         | 75        | 1.42%   |
| Fedora 37                    | 73        | 1.38%   |
| Xubuntu 18.04                | 71        | 1.34%   |
| Ubuntu 22.10                 | 71        | 1.34%   |
| Ubuntu 19.10                 | 68        | 1.29%   |
| Linux Mint 21.2              | 66        | 1.25%   |
| Linux Mint 20.3              | 66        | 1.25%   |
| Xubuntu 20.04                | 62        | 1.17%   |
| Ubuntu 20.10                 | 61        | 1.15%   |
| OpenMandriva 23.03           | 61        | 1.15%   |
| Ubuntu 21.10                 | 58        | 1.1%    |
| Ubuntu 19.04                 | 56        | 1.06%   |
| Linux Mint 21                | 55        | 1.04%   |
| Debian 12                    | 55        | 1.04%   |
| KDE neon 20.04               | 54        | 1.02%   |
| Kubuntu 22.04                | 50        | 0.95%   |
| Zorin 15                     | 49        | 0.93%   |
| Ubuntu 23.04                 | 49        | 0.93%   |
| Debian 10                    | 46        | 0.87%   |
| openSUSE Tumbleweed-XXXXXXXX | 43        | 0.81%   |
| Fedora 35                    | 42        | 0.79%   |
| Ubuntu 21.04                 | 40        | 0.76%   |
| Ubuntu 18.10                 | 40        | 0.76%   |
| OpenMandriva 23.01           | 40        | 0.76%   |
| Fedora 39                    | 39        | 0.74%   |
| Manjaro                      | 37        | 0.7%    |
| ArcoLinux Rolling            | 37        | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1551      | 31.21%  |
| Linux Mint    | 399       | 8.03%   |
| Fedora        | 398       | 8.01%   |
| OpenMandriva  | 370       | 7.44%   |
| Arch          | 268       | 5.39%   |
| Debian        | 251       | 5.05%   |
| Xubuntu       | 200       | 4.02%   |
| Pop!_OS       | 182       | 3.66%   |
| Manjaro       | 143       | 2.88%   |
| Kubuntu       | 142       | 2.86%   |
| Zorin         | 135       | 2.72%   |
| ROSA          | 96        | 1.93%   |
| EndeavourOS   | 82        | 1.65%   |
| KDE neon      | 78        | 1.57%   |
| Lubuntu       | 70        | 1.41%   |
| openSUSE      | 66        | 1.33%   |
| Elementary    | 47        | 0.95%   |
| Ubuntu MATE   | 43        | 0.87%   |
| Endless       | 38        | 0.76%   |
| ArcoLinux     | 38        | 0.76%   |
| LMDE          | 33        | 0.66%   |
| MX            | 24        | 0.48%   |
| Kali          | 24        | 0.48%   |
| Gentoo        | 24        | 0.48%   |
| Ubuntu Unity  | 23        | 0.46%   |
| BlackPanther  | 20        | 0.4%    |
| Clear Linux   | 18        | 0.36%   |
| Ubuntu Budgie | 17        | 0.34%   |
| SteamOS       | 17        | 0.34%   |
| Garuda Linux  | 17        | 0.34%   |
| Parrot        | 13        | 0.26%   |
| Nobara        | 13        | 0.26%   |
| Peppermint    | 11        | 0.22%   |
| NixOS         | 9         | 0.18%   |
| Xero          | 7         | 0.14%   |
| LinuxFX       | 7         | 0.14%   |
| Void Linux    | 5         | 0.1%    |
| Linux Lite    | 5         | 0.1%    |
| Chrome OS     | 5         | 0.1%    |
| CentOS        | 5         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 103       | 1.76%   |
| 5.15.0-52-generic        | 98        | 1.68%   |
| 5.16.7-desktop-1omv4003  | 97        | 1.66%   |
| 5.4.0-42-generic         | 68        | 1.16%   |
| 5.15.0-56-generic        | 63        | 1.08%   |
| 6.2.6-desktop-1omv2390   | 60        | 1.03%   |
| 5.15.0-58-generic        | 44        | 0.75%   |
| 5.4.0-26-generic         | 43        | 0.74%   |
| 5.15.0-46-generic        | 41        | 0.7%    |
| 5.3.0-46-generic         | 40        | 0.68%   |
| 5.4.0-52-generic         | 36        | 0.62%   |
| 5.4.0-29-generic         | 36        | 0.62%   |
| 5.15.0-47-generic        | 35        | 0.6%    |
| 6.1.1-desktop-1omv2290   | 34        | 0.58%   |
| 5.15.0-43-generic        | 34        | 0.58%   |
| 5.4.0-58-generic         | 33        | 0.56%   |
| 5.3.0-40-generic         | 32        | 0.55%   |
| 5.3.0-42-generic         | 31        | 0.53%   |
| 5.4.0-48-generic         | 30        | 0.51%   |
| 5.15.0-41-generic        | 30        | 0.51%   |
| 5.19.0-32-generic        | 29        | 0.5%    |
| 6.0.2-arch1-1            | 28        | 0.48%   |
| 5.15.0-53-generic        | 27        | 0.46%   |
| 5.13.0-28-generic        | 27        | 0.46%   |
| 5.0.0-37-generic         | 27        | 0.46%   |
| 5.15.0-48-generic        | 25        | 0.43%   |
| 6.2.0-35-generic         | 24        | 0.41%   |
| 6.2.0-26-generic         | 24        | 0.41%   |
| 6.2.0-20-generic         | 24        | 0.41%   |
| 6.1.0-13-amd64           | 24        | 0.41%   |
| 5.15.0-76-generic        | 24        | 0.41%   |
| 5.15.0-60-generic        | 24        | 0.41%   |
| 5.10.0-19-amd64          | 24        | 0.41%   |
| 6.2.0-36-generic         | 23        | 0.39%   |
| 5.3.0-51-generic         | 23        | 0.39%   |
| 5.19.0-23-generic        | 23        | 0.39%   |
| 5.19.0-21-generic        | 23        | 0.39%   |
| 5.10.0-21-amd64          | 23        | 0.39%   |
| 6.4.11-desktop-1omv2390  | 22        | 0.38%   |
| 5.4.0-54-generic         | 22        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 704       | 12.87%  |
| 5.15.0  | 593       | 10.84%  |
| 4.15.0  | 244       | 4.46%   |
| 5.19.0  | 238       | 4.35%   |
| 5.3.0   | 224       | 4.09%   |
| 5.8.0   | 201       | 3.67%   |
| 5.13.0  | 199       | 3.64%   |
| 6.2.0   | 191       | 3.49%   |
| 5.11.0  | 169       | 3.09%   |
| 5.10.0  | 156       | 2.85%   |
| 5.0.0   | 113       | 2.07%   |
| 5.10.14 | 103       | 1.88%   |
| 5.16.7  | 99        | 1.81%   |
| 4.18.0  | 87        | 1.59%   |
| 6.1.0   | 81        | 1.48%   |
| 6.2.6   | 77        | 1.41%   |
| 6.5.0   | 57        | 1.04%   |
| 6.0.2   | 53        | 0.97%   |
| 4.19.0  | 45        | 0.82%   |
| 6.1.1   | 41        | 0.75%   |
| 6.5.9   | 35        | 0.64%   |
| 6.4.11  | 32        | 0.58%   |
| 5.19.16 | 29        | 0.53%   |
| 6.5.5   | 28        | 0.51%   |
| 6.0.0   | 27        | 0.49%   |
| 6.6.2   | 26        | 0.48%   |
| 6.0.12  | 22        | 0.4%    |
| 6.5.8   | 21        | 0.38%   |
| 5.17.5  | 20        | 0.37%   |
| 6.5.6   | 19        | 0.35%   |
| 6.2.9   | 19        | 0.35%   |
| 4.18.16 | 19        | 0.35%   |
| 6.0.7   | 18        | 0.33%   |
| 6.0.6   | 18        | 0.33%   |
| 4.9.60  | 18        | 0.33%   |
| 4.4.0   | 18        | 0.33%   |
| 4.9.20  | 17        | 0.31%   |
| 5.17.1  | 15        | 0.27%   |
| 6.5.7   | 14        | 0.26%   |
| 5.14.0  | 14        | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 751       | 13.92%  |
| 5.15    | 684       | 12.68%  |
| 6.2     | 344       | 6.38%   |
| 5.19    | 343       | 6.36%   |
| 5.10    | 317       | 5.87%   |
| 5.3     | 249       | 4.61%   |
| 4.15    | 245       | 4.54%   |
| 5.8     | 241       | 4.47%   |
| 6.1     | 238       | 4.41%   |
| 5.13    | 220       | 4.08%   |
| 6.0     | 206       | 3.82%   |
| 5.11    | 206       | 3.82%   |
| 6.5     | 198       | 3.67%   |
| 5.16    | 154       | 2.85%   |
| 5.0     | 116       | 2.15%   |
| 4.18    | 109       | 2.02%   |
| 6.4     | 97        | 1.8%    |
| 6.6     | 83        | 1.54%   |
| 5.17    | 67        | 1.24%   |
| 5.14    | 63        | 1.17%   |
| 4.9     | 62        | 1.15%   |
| 4.19    | 58        | 1.07%   |
| 6.3     | 57        | 1.06%   |
| 5.18    | 54        | 1%      |
| 5.9     | 46        | 0.85%   |
| 5.12    | 37        | 0.69%   |
| 5.6     | 34        | 0.63%   |
| 5.5     | 34        | 0.63%   |
| 5.7     | 23        | 0.43%   |
| 4.4     | 19        | 0.35%   |
| 5.2     | 9         | 0.17%   |
| 4.13    | 6         | 0.11%   |
| 4.1     | 6         | 0.11%   |
| 5.1     | 4         | 0.07%   |
| 4.12    | 4         | 0.07%   |
| 4.20    | 3         | 0.06%   |
| 4.17    | 3         | 0.06%   |
| 4.16    | 2         | 0.04%   |
| 3.10    | 2         | 0.04%   |
| 4.14    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 4517      | 95.34%  |
| i686   | 220       | 4.64%   |
| armv7l | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 2195      | 44.09%  |
| KDE5              | 974       | 19.57%  |
| XFCE              | 460       | 9.24%   |
| Unknown           | 417       | 8.38%   |
| X-Cinnamon        | 330       | 6.63%   |
| MATE              | 134       | 2.69%   |
| LXQt              | 91        | 1.83%   |
| KDE               | 69        | 1.39%   |
| KDE4              | 50        | 1%      |
| Pantheon          | 47        | 0.94%   |
| Cinnamon          | 32        | 0.64%   |
| LXDE              | 28        | 0.56%   |
| Unity             | 25        | 0.5%    |
| Budgie            | 25        | 0.5%    |
| i3                | 18        | 0.36%   |
| GNOME Flashback   | 17        | 0.34%   |
| GNOME Classic     | 9         | 0.18%   |
| sway              | 8         | 0.16%   |
| Deepin            | 7         | 0.14%   |
| Hyprland          | 6         | 0.12%   |
| bspwm             | 5         | 0.1%    |
| DWM               | 4         | 0.08%   |
| none+i3           | 3         | 0.06%   |
| xubuntu           | 2         | 0.04%   |
| Unicorn:XFCE      | 2         | 0.04%   |
| Trinity           | 2         | 0.04%   |
| qtile             | 2         | 0.04%   |
| openbox           | 2         | 0.04%   |
| lightdm-xsession  | 2         | 0.04%   |
| Enlightenment     | 2         | 0.04%   |
| awesome           | 2         | 0.04%   |
| ubuntu:pika:GNOME | 1         | 0.02%   |
| ubuntu            | 1         | 0.02%   |
| pika:GNOME        | 1         | 0.02%   |
| none+bspwm        | 1         | 0.02%   |
| jwm               | 1         | 0.02%   |
| icewm             | 1         | 0.02%   |
| gamescope         | 1         | 0.02%   |
| Cutefish          | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3541      | 71.93%  |
| Wayland | 1117      | 22.69%  |
| Unknown | 217       | 4.41%   |
| Tty     | 48        | 0.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1982      | 39.93%  |
| SDDM    | 917       | 18.47%  |
| GDM3    | 720       | 14.5%   |
| GDM     | 596       | 12.01%  |
| LightDM | 578       | 11.64%  |
| TDM     | 96        | 1.93%   |
| KDM     | 51        | 1.03%   |
| SLiM    | 8         | 0.16%   |
| XDM     | 6         | 0.12%   |
| LXDM    | 3         | 0.06%   |
| SLIMSKI | 2         | 0.04%   |
| WDM     | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |
| Ly      | 1         | 0.02%   |
| GREETD  | 1         | 0.02%   |
| EMPTTY  | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| it_IT          | 3024      | 61.87%  |
| en_US          | 1107      | 22.65%  |
| Unknown        | 436       | 8.92%   |
| en_GB          | 119       | 2.43%   |
| C              | 110       | 2.25%   |
| de_DE          | 16        | 0.33%   |
| fr_FR          | 10        | 0.2%    |
| de_IT          | 10        | 0.2%    |
| es_ES          | 9         | 0.18%   |
| POSIX          | 8         | 0.16%   |
| ru_RU          | 5         | 0.1%    |
| en_AG          | 4         | 0.08%   |
| it_IT@euro     | 3         | 0.06%   |
| en_IE          | 3         | 0.06%   |
| en_AU          | 3         | 0.06%   |
| it_CH          | 2         | 0.04%   |
| fur_IT         | 2         | 0.04%   |
| en_US.UTF8     | 2         | 0.04%   |
| ro_RO          | 1         | 0.02%   |
| pt_BR          | 1         | 0.02%   |
| pl_PL          | 1         | 0.02%   |
| it_IT.UTF -8   | 1         | 0.02%   |
| it_IT.iso88591 | 1         | 0.02%   |
| fr_BE          | 1         | 0.02%   |
| es_US          | 1         | 0.02%   |
| en_US@euro     | 1         | 0.02%   |
| en_US.utf-8    | 1         | 0.02%   |
| en_IN          | 1         | 0.02%   |
| en_DK          | 1         | 0.02%   |
| de_CH          | 1         | 0.02%   |
| de_AT          | 1         | 0.02%   |
| C.UTF8         | 1         | 0.02%   |
| bg_BG          | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2670      | 55.12%  |
| BIOS | 2174      | 44.88%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 3572      | 72.94%  |
| Btrfs    | 497       | 10.15%  |
| Overlay  | 473       | 9.66%   |
| Tmpfs    | 156       | 3.19%   |
| Unknown  | 103       | 2.1%    |
| Xfs      | 40        | 0.82%   |
| Zfs      | 26        | 0.53%   |
| Ext2     | 12        | 0.25%   |
| F2fs     | 8         | 0.16%   |
| Ext3     | 5         | 0.1%    |
| XXX4     | 2         | 0.04%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |
| Aufs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2218      | 45.52%  |
| Unknown | 2144      | 44%     |
| MBR     | 511       | 10.49%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4218      | 87.27%  |
| Yes       | 615       | 12.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3193      | 65.93%  |
| Yes       | 1650      | 34.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 1073      | 22.67%  |
| Lenovo              | 785       | 16.58%  |
| ASUSTek Computer    | 721       | 15.23%  |
| Acer                | 531       | 11.22%  |
| Dell                | 489       | 10.33%  |
| HUAWEI              | 126       | 2.66%   |
| Apple               | 121       | 2.56%   |
| Toshiba             | 109       | 2.3%    |
| MSI                 | 102       | 2.15%   |
| Sony                | 99        | 2.09%   |
| Samsung Electronics | 82        | 1.73%   |
| Fujitsu             | 42        | 0.89%   |
| Unknown             | 39        | 0.82%   |
| Mediacom            | 37        | 0.78%   |
| Packard Bell        | 34        | 0.72%   |
| Notebook            | 28        | 0.59%   |
| Chuwi               | 28        | 0.59%   |
| Teclast             | 21        | 0.44%   |
| Fujitsu Siemens     | 20        | 0.42%   |
| Timi                | 19        | 0.4%    |
| Microtech           | 19        | 0.4%    |
| TUXEDO              | 15        | 0.32%   |
| PC Specialist       | 15        | 0.32%   |
| Valve               | 14        | 0.3%    |
| Jumper              | 10        | 0.21%   |
| Google              | 10        | 0.21%   |
| SANTECH             | 9         | 0.19%   |
| Olivetti            | 9         | 0.19%   |
| LG Electronics      | 8         | 0.17%   |
| eMachines           | 8         | 0.17%   |
| TrekStor            | 7         | 0.15%   |
| Alienware           | 6         | 0.13%   |
| SiComputer          | 5         | 0.11%   |
| Intel               | 4         | 0.08%   |
| Framework           | 4         | 0.08%   |
| AMI                 | 4         | 0.08%   |
| YASHI               | 3         | 0.06%   |
| TELECOMITALIA       | 3         | 0.06%   |
| System76            | 3         | 0.06%   |
| Razer               | 3         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP Pavilion dv6                       | 59        | 1.25%   |
| Unknown                               | 54        | 1.14%   |
| HP Notebook                           | 48        | 1.01%   |
| HP Pavilion 15                        | 33        | 0.7%    |
| HP 255 G8 Notebook PC                 | 28        | 0.59%   |
| HP Pavilion g6                        | 25        | 0.53%   |
| HUAWEI NBLK-WAX9X                     | 20        | 0.42%   |
| HP 15                                 | 19        | 0.4%    |
| Mediacom SmartBook 14 FullHD - SB14UC | 17        | 0.36%   |
| Dell XPS 15 7590                      | 15        | 0.32%   |
| HP ENVY 15                            | 14        | 0.3%    |
| HP 255 G7 Notebook PC                 | 14        | 0.3%    |
| Valve Jupiter                         | 13        | 0.27%   |
| HUAWEI KLVL-WXX9                      | 13        | 0.27%   |
| HP 255 G6 Notebook PC                 | 13        | 0.27%   |
| Apple MacBook4,1                      | 13        | 0.27%   |
| Lenovo IdeaPad 3 15ADA05 81W1         | 12        | 0.25%   |
| HP Pavilion x2 Detachable             | 12        | 0.25%   |
| HP G62                                | 12        | 0.25%   |
| HP 250 G6 Notebook PC                 | 12        | 0.25%   |
| Dell XPS 15 9570                      | 12        | 0.25%   |
| Lenovo IdeaPad 330S-15IKB 81F5        | 11        | 0.23%   |
| HUAWEI BOD-WXX9                       | 11        | 0.23%   |
| HP Laptop 15s-eq2xxx                  | 11        | 0.23%   |
| HP 250 G3                             | 11        | 0.23%   |
| Acer Aspire 5920G                     | 11        | 0.23%   |
| Acer Aspire 5750G                     | 11        | 0.23%   |
| Jumper EZbook                         | 10        | 0.21%   |
| HP Pavilion dv7                       | 10        | 0.21%   |
| HP Compaq 6730s                       | 10        | 0.21%   |
| HP 250 G7 Notebook PC                 | 10        | 0.21%   |
| Dell XPS 15 9560                      | 10        | 0.21%   |
| Acer Aspire E5-571G                   | 10        | 0.21%   |
| Acer Aspire A515-45                   | 10        | 0.21%   |
| Samsung RC530/RC730                   | 9         | 0.19%   |
| Microtech ebookPro                    | 9         | 0.19%   |
| Lenovo V145-15AST 81MT                | 9         | 0.19%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 9         | 0.19%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY  | 9         | 0.19%   |
| Lenovo G50-45 80E3                    | 9         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 370       | 7.82%   |
| Acer Aspire           | 340       | 7.18%   |
| HP Pavilion           | 273       | 5.77%   |
| Lenovo IdeaPad        | 204       | 4.31%   |
| Dell Latitude         | 182       | 3.84%   |
| HP EliteBook          | 123       | 2.6%    |
| ASUS VivoBook         | 119       | 2.51%   |
| Dell XPS              | 114       | 2.41%   |
| HP ProBook            | 103       | 2.18%   |
| HP Laptop             | 103       | 2.18%   |
| Toshiba Satellite     | 93        | 1.96%   |
| Dell Inspiron         | 90        | 1.9%    |
| HP Compaq             | 77        | 1.63%   |
| HP 255                | 75        | 1.58%   |
| HP 250                | 67        | 1.42%   |
| Unknown               | 54        | 1.14%   |
| HP Notebook           | 48        | 1.01%   |
| Acer Swift            | 48        | 1.01%   |
| Dell Vostro           | 43        | 0.91%   |
| Acer TravelMate       | 43        | 0.91%   |
| Fujitsu LIFEBOOK      | 40        | 0.84%   |
| Lenovo ThinkBook      | 37        | 0.78%   |
| Dell Precision        | 37        | 0.78%   |
| Acer Extensa          | 36        | 0.76%   |
| HP ENVY               | 28        | 0.59%   |
| ASUS ROG              | 28        | 0.59%   |
| Packard Bell EasyNote | 27        | 0.57%   |
| Apple MacBookPro11    | 23        | 0.49%   |
| Acer Nitro            | 22        | 0.46%   |
| Mediacom SmartBook    | 21        | 0.44%   |
| HUAWEI NBLK-WAX9X     | 20        | 0.42%   |
| MSI Modern            | 19        | 0.4%    |
| HP OMEN               | 19        | 0.4%    |
| HP 15                 | 19        | 0.4%    |
| HP ZBook              | 18        | 0.38%   |
| ASUS ASUS             | 18        | 0.38%   |
| Lenovo Yoga           | 17        | 0.36%   |
| Lenovo Legion         | 17        | 0.36%   |
| ASUS Zenbook          | 17        | 0.36%   |
| MSI Prestige          | 15        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 433       | 9.15%   |
| 2021    | 417       | 8.81%   |
| 2019    | 400       | 8.45%   |
| 2018    | 356       | 7.52%   |
| 2013    | 322       | 6.8%    |
| 2017    | 314       | 6.63%   |
| 2012    | 277       | 5.85%   |
| 2016    | 271       | 5.72%   |
| 2010    | 260       | 5.49%   |
| 2008    | 260       | 5.49%   |
| 2014    | 259       | 5.47%   |
| 2011    | 258       | 5.45%   |
| 2015    | 256       | 5.41%   |
| 2009    | 206       | 4.35%   |
| 2022    | 158       | 3.34%   |
| 2007    | 139       | 2.94%   |
| 2006    | 65        | 1.37%   |
| 2023    | 48        | 1.01%   |
| 2005    | 24        | 0.51%   |
| Unknown | 6         | 0.13%   |
| 2004    | 3         | 0.06%   |
| 2003    | 2         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4734      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4307      | 89.77%  |
| Enabled  | 491       | 10.23%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4716      | 99.62%  |
| Yes  | 18        | 0.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1358      | 28.27%  |
| 3.01-4.0    | 1117      | 23.25%  |
| 16.01-24.0  | 802       | 16.69%  |
| 8.01-16.0   | 780       | 16.24%  |
| 1.01-2.0    | 287       | 5.97%   |
| 32.01-64.0  | 239       | 4.98%   |
| 2.01-3.0    | 102       | 2.12%   |
| 0.51-1.0    | 45        | 0.94%   |
| 24.01-32.0  | 40        | 0.83%   |
| 64.01-256.0 | 30        | 0.62%   |
| 0.01-0.5    | 4         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1927      | 36.36%  |
| 2.01-3.0   | 1313      | 24.77%  |
| 4.01-8.0   | 721       | 13.6%   |
| 3.01-4.0   | 690       | 13.02%  |
| 0.51-1.0   | 398       | 7.51%   |
| 8.01-16.0  | 187       | 3.53%   |
| 0.01-0.5   | 48        | 0.91%   |
| 16.01-24.0 | 12        | 0.23%   |
| 24.01-32.0 | 2         | 0.04%   |
| 32.01-64.0 | 1         | 0.02%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3617      | 74.96%  |
| 2      | 1039      | 21.53%  |
| 3      | 114       | 2.36%   |
| 0      | 36        | 0.75%   |
| 4      | 13        | 0.27%   |
| 6      | 3         | 0.06%   |
| 5      | 3         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2827      | 59.45%  |
| Yes       | 1928      | 40.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3732      | 78.47%  |
| No        | 1024      | 21.53%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4638      | 97.89%  |
| No        | 100       | 2.11%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3557      | 74.17%  |
| No        | 1239      | 25.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Italy   | 4734      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Milan               | 731       | 13.42%  |
| Rome                | 537       | 9.86%   |
| Turin               | 175       | 3.21%   |
| Milano              | 109       | 2%      |
| Florence            | 104       | 1.91%   |
| Naples              | 100       | 1.84%   |
| Bologna             | 99        | 1.82%   |
| Rho                 | 86        | 1.58%   |
| Genoa               | 73        | 1.34%   |
| Palermo             | 66        | 1.21%   |
| Padova              | 65        | 1.19%   |
| Verona              | 56        | 1.03%   |
| Bari                | 53        | 0.97%   |
| Catania             | 52        | 0.95%   |
| Parma               | 39        | 0.72%   |
| Trieste             | 36        | 0.66%   |
| Brescia             | 36        | 0.66%   |
| Bergamo             | 36        | 0.66%   |
| Venice              | 32        | 0.59%   |
| Pisa                | 29        | 0.53%   |
| Casalecchio di Reno | 27        | 0.5%    |
| Monza               | 25        | 0.46%   |
| Bolzano             | 25        | 0.46%   |
| Perugia             | 24        | 0.44%   |
| Modena              | 23        | 0.42%   |
| Trento              | 22        | 0.4%    |
| Salerno             | 21        | 0.39%   |
| Reggio Emilia       | 21        | 0.39%   |
| Cagliari            | 21        | 0.39%   |
| Vicenza             | 19        | 0.35%   |
| Taranto             | 19        | 0.35%   |
| Sesto San Giovanni  | 19        | 0.35%   |
| Seregno             | 18        | 0.33%   |
| Udine               | 16        | 0.29%   |
| Reggio Calabria     | 16        | 0.29%   |
| Pescara             | 16        | 0.29%   |
| Mestre              | 16        | 0.29%   |
| Legnano             | 16        | 0.29%   |
| Rimini              | 15        | 0.28%   |
| Novara              | 14        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1050      | 1442   | 18.01%  |
| WDC                         | 555       | 705    | 9.52%   |
| Seagate                     | 520       | 637    | 8.92%   |
| Sandisk                     | 374       | 503    | 6.41%   |
| Toshiba                     | 361       | 480    | 6.19%   |
| Unknown                     | 350       | 481    | 6%      |
| Kingston                    | 337       | 412    | 5.78%   |
| Crucial                     | 332       | 392    | 5.69%   |
| Hitachi                     | 243       | 296    | 4.17%   |
| SK hynix                    | 234       | 292    | 4.01%   |
| HGST                        | 197       | 259    | 3.38%   |
| Micron Technology           | 167       | 213    | 2.86%   |
| Intel                       | 158       | 204    | 2.71%   |
| KIOXIA                      | 76        | 95     | 1.3%    |
| China                       | 56        | 63     | 0.96%   |
| Fujitsu                     | 48        | 57     | 0.82%   |
| Apple                       | 45        | 48     | 0.77%   |
| Phison                      | 44        | 52     | 0.75%   |
| SPCC                        | 39        | 47     | 0.67%   |
| LITEON                      | 29        | 37     | 0.5%    |
| Transcend                   | 28        | 39     | 0.48%   |
| Intenso                     | 28        | 29     | 0.48%   |
| JMicron Technology          | 27        | 31     | 0.46%   |
| Kingston Technology Company | 25        | 30     | 0.43%   |
| Phison Electronics          | 24        | 31     | 0.41%   |
| Netac                       | 23        | 25     | 0.39%   |
| Unknown                     | 22        | 29     | 0.38%   |
| A-DATA Technology           | 20        | 24     | 0.34%   |
| Teclast                     | 18        | 23     | 0.31%   |
| Micron/Crucial Technology   | 18        | 25     | 0.31%   |
| KingDian                    | 17        | 23     | 0.29%   |
| PNY                         | 16        | 18     | 0.27%   |
| Silicon Motion              | 15        | 19     | 0.26%   |
| SABRENT                     | 12        | 12     | 0.21%   |
| Drevo                       | 12        | 13     | 0.21%   |
| SSSTC                       | 11        | 13     | 0.19%   |
| Patriot                     | 9         | 13     | 0.15%   |
| MAXIO Technology (Hangzhou) | 9         | 9      | 0.15%   |
| LITEONIT                    | 9         | 20     | 0.15%   |
| Dogfish                     | 9         | 10     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 93        | 1.53%   |
| Crucial CT500MX500SSD1 500GB                        | 84        | 1.39%   |
| Unknown MMC Card  32GB                              | 71        | 1.17%   |
| Samsung SSD 860 EVO 500GB                           | 67        | 1.11%   |
| Toshiba MQ01ABF050 500GB                            | 65        | 1.07%   |
| HGST HTS545050A7E680 500GB                          | 58        | 0.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 56        | 0.92%   |
| Seagate ST500LT012-1DG142 500GB                     | 54        | 0.89%   |
| Seagate ST1000LM035-1RK172 1TB                      | 54        | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 53        | 0.87%   |
| Samsung SSD 850 EVO 250GB                           | 52        | 0.86%   |
| HGST HTS721010A9E630 1TB                            | 49        | 0.81%   |
| Samsung SSD 850 EVO 500GB                           | 46        | 0.76%   |
| Crucial CT240BX500SSD1 240GB                        | 44        | 0.73%   |
| Unknown MMC Card  64GB                              | 43        | 0.71%   |
| Kingston SA400S37480G 480GB SSD                     | 37        | 0.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 35        | 0.58%   |
| Seagate ST9500325AS 500GB                           | 33        | 0.54%   |
| Samsung NVMe SSD Drive 512GB                        | 32        | 0.53%   |
| Toshiba MQ04ABF100 1TB                              | 31        | 0.51%   |
| Toshiba MQ01ABD100 1TB                              | 31        | 0.51%   |
| Crucial CT1000MX500SSD1 1TB                         | 31        | 0.51%   |
| Crucial CT480BX500SSD1 480GB                        | 30        | 0.49%   |
| SanDisk NVMe SSD Drive 512GB                        | 29        | 0.48%   |
| SanDisk SSD PLUS 240GB                              | 28        | 0.46%   |
| Samsung SSD 860 EVO 1TB                             | 27        | 0.45%   |
| Samsung SSD 860 EVO 250GB                           | 26        | 0.43%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 25        | 0.41%   |
| Unknown NCard  32GB                                 | 23        | 0.38%   |
| Unknown MMC Card  128GB                             | 23        | 0.38%   |
| Kingston SA400S37120G 120GB SSD                     | 23        | 0.38%   |
| HGST HTS541010A9E680 1TB                            | 23        | 0.38%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 22        | 0.36%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 22        | 0.36%   |
| Unknown                                             | 22        | 0.36%   |
| SanDisk NVMe SSD Drive 256GB                        | 21        | 0.35%   |
| Samsung MZVLQ512HALU-000H1 512GB                    | 21        | 0.35%   |
| Hitachi HTS545050A7E380 500GB                       | 21        | 0.35%   |
| Seagate M3 Portable 2TB                             | 20        | 0.33%   |
| Kingston SV300S37A120G 120GB SSD                    | 20        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 494       | 601    | 28.7%   |
| WDC                 | 380       | 486    | 22.08%  |
| Toshiba             | 249       | 309    | 14.47%  |
| Hitachi             | 243       | 296    | 14.12%  |
| HGST                | 197       | 259    | 11.45%  |
| Fujitsu             | 48        | 57     | 2.79%   |
| Samsung Electronics | 46        | 57     | 2.67%   |
| Unknown             | 23        | 24     | 1.34%   |
| SABRENT             | 12        | 12     | 0.7%    |
| External            | 5         | 6      | 0.29%   |
| TO Exter            | 3         | 3      | 0.17%   |
| ASMT                | 3         | 3      | 0.17%   |
| USB3.0              | 2         | 2      | 0.12%   |
| SSK                 | 2         | 2      | 0.12%   |
| Intenso             | 2         | 2      | 0.12%   |
| IBM/Hitachi         | 2         | 3      | 0.12%   |
| HGST HTS            | 2         | 2      | 0.12%   |
| Apple               | 2         | 2      | 0.12%   |
| StoreJet            | 1         | 1      | 0.06%   |
| Inateck             | 1         | 1      | 0.06%   |
| Generic-            | 1         | 1      | 0.06%   |
| DAS                 | 1         | 4      | 0.06%   |
| ASMedia             | 1         | 1      | 0.06%   |
| Unknown             | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 506       | 683    | 25.58%  |
| Crucial             | 310       | 369    | 15.67%  |
| Kingston            | 250       | 302    | 12.64%  |
| SanDisk             | 195       | 254    | 9.86%   |
| Micron Technology   | 61        | 81     | 3.08%   |
| WDC                 | 56        | 73     | 2.83%   |
| China               | 55        | 62     | 2.78%   |
| SK hynix            | 52        | 57     | 2.63%   |
| SPCC                | 34        | 41     | 1.72%   |
| Apple               | 34        | 36     | 1.72%   |
| Toshiba             | 29        | 44     | 1.47%   |
| Transcend           | 27        | 38     | 1.37%   |
| Intel               | 27        | 35     | 1.37%   |
| LITEON              | 25        | 28     | 1.26%   |
| Intenso             | 23        | 23     | 1.16%   |
| Netac               | 21        | 23     | 1.06%   |
| Teclast             | 18        | 23     | 0.91%   |
| KingDian            | 17        | 23     | 0.86%   |
| PNY                 | 15        | 16     | 0.76%   |
| A-DATA Technology   | 15        | 17     | 0.76%   |
| JMicron Technology  | 13        | 14     | 0.66%   |
| Drevo               | 12        | 13     | 0.61%   |
| Unknown             | 10        | 16     | 0.51%   |
| Patriot             | 9         | 13     | 0.46%   |
| LITEONIT            | 9         | 20     | 0.46%   |
| Dogfish             | 9         | 10     | 0.46%   |
| Corsair             | 9         | 10     | 0.46%   |
| Microtech           | 8         | 18     | 0.4%    |
| GOODRAM             | 7         | 8      | 0.35%   |
| Emtec               | 7         | 7      | 0.35%   |
| Team                | 6         | 8      | 0.3%    |
| Lexar               | 6         | 6      | 0.3%    |
| KingSpec            | 6         | 7      | 0.3%    |
| Fanxiang            | 6         | 6      | 0.3%    |
| Verbatim            | 5         | 11     | 0.25%   |
| TCSUNBOW            | 5         | 5      | 0.25%   |
| Hewlett-Packard     | 5         | 6      | 0.25%   |
| FORESEE             | 5         | 5      | 0.25%   |
| BAITITON            | 5         | 11     | 0.25%   |
| OCZ                 | 4         | 4      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1861      | 2494   | 33.56%  |
| HDD     | 1661      | 2135   | 29.95%  |
| NVMe    | 1587      | 2240   | 28.62%  |
| MMC     | 342       | 490    | 6.17%   |
| Unknown | 95        | 112    | 1.71%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3164      | 4478   | 59.55%  |
| NVMe | 1586      | 2236   | 29.85%  |
| MMC  | 342       | 490    | 6.44%   |
| SAS  | 221       | 267    | 4.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2555      | 3422   | 73.44%  |
| 0.51-1.0   | 795       | 1045   | 22.85%  |
| 1.01-2.0   | 112       | 142    | 3.22%   |
| 3.01-4.0   | 9         | 9      | 0.26%   |
| 4.01-10.0  | 8         | 11     | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1461      | 28.98%  |
| 251-500        | 1285      | 25.49%  |
| 501-1000       | 599       | 11.88%  |
| 1-20           | 517       | 10.25%  |
| 51-100         | 394       | 7.81%   |
| 1001-2000      | 252       | 5%      |
| 21-50          | 249       | 4.94%   |
| Unknown        | 117       | 2.32%   |
| More than 3000 | 90        | 1.79%   |
| 2001-3000      | 78        | 1.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2210      | 42.18%  |
| 21-50          | 855       | 16.32%  |
| 101-250        | 726       | 13.85%  |
| 51-100         | 642       | 12.25%  |
| 251-500        | 374       | 7.14%   |
| 501-1000       | 195       | 3.72%   |
| Unknown        | 117       | 2.23%   |
| 1001-2000      | 74        | 1.41%   |
| 2001-3000      | 24        | 0.46%   |
| More than 3000 | 23        | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                     | 18        | 22     | 5.57%   |
| Seagate ST9500325AS 500GB                      | 8         | 8      | 2.48%   |
| Seagate ST1000LM035-1RK172 1TB                 | 8         | 10     | 2.48%   |
| Toshiba MQ01ABF050 500GB                       | 7         | 8      | 2.17%   |
| Seagate ST500LT012-1DG142 500GB                | 7         | 7      | 2.17%   |
| Hitachi HTS725050A9A364 500GB                  | 6         | 7      | 1.86%   |
| HGST HTS725050A7E630 500GB                     | 6         | 8      | 1.86%   |
| HGST HTS721010A9E630 1TB                       | 6         | 6      | 1.86%   |
| WDC WD3200BEVT-60A23T0 320GB                   | 5         | 5      | 1.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 5         | 5      | 1.55%   |
| Hitachi HTS545050A7E380 500GB                  | 5         | 5      | 1.55%   |
| SK hynix HFS512G39TND-N210A 512GB SSD          | 4         | 4      | 1.24%   |
| Seagate ST9320325AS 320GB                      | 4         | 4      | 1.24%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 4         | 4      | 1.24%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 4         | 4      | 1.24%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 4         | 5      | 1.24%   |
| Hitachi HTS547550A9E384 500GB                  | 4         | 4      | 1.24%   |
| HGST HTS541010A9E680 1TB                       | 4         | 4      | 1.24%   |
| WDC WD5000LPCX-24C6HT0 500GB                   | 3         | 4      | 0.93%   |
| Toshiba MQ01ABD100 1TB                         | 3         | 5      | 0.93%   |
| Toshiba MK5065GSX 500GB                        | 3         | 4      | 0.93%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 3         | 3      | 0.93%   |
| Seagate ST500LT012-9WS142 500GB                | 3         | 3      | 0.93%   |
| Seagate ST500LM021-1KJ152 500GB                | 3         | 3      | 0.93%   |
| Hitachi HTS545032B9A300 320GB                  | 3         | 3      | 0.93%   |
| Hitachi HTS543232A7A384 320GB                  | 3         | 4      | 0.93%   |
| HGST HTS541075A9E680 752GB                     | 3         | 6      | 0.93%   |
| Crucial CT525MX300SSD1 528GB                   | 3         | 3      | 0.93%   |
| WDC WD5000BEVT-22ZAT0 500GB                    | 2         | 2      | 0.62%   |
| WDC WD3200BPVT-22ZEST0 320GB                   | 2         | 2      | 0.62%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 2         | 3      | 0.62%   |
| WDC WD10JPCX-24UE4T0 1TB                       | 2         | 2      | 0.62%   |
| Toshiba MQ04ABF100 1TB                         | 2         | 2      | 0.62%   |
| Seagate ST9320423AS 320GB                      | 2         | 2      | 0.62%   |
| Seagate ST9250315AS 250GB                      | 2         | 2      | 0.62%   |
| Seagate ST9160310AS 160GB                      | 2         | 3      | 0.62%   |
| Seagate ST750LM022 HN-M750MBB 752GB            | 2         | 2      | 0.62%   |
| Seagate ST500LM000-1EJ162 500GB                | 2         | 2      | 0.62%   |
| Seagate ST320LT020-9YG142 320GB                | 2         | 2      | 0.62%   |
| SanDisk SSD PLUS 480GB                         | 2         | 2      | 0.62%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 70        | 73     | 21.67%  |
| Hitachi                     | 50        | 52     | 15.48%  |
| HGST                        | 40        | 49     | 12.38%  |
| WDC                         | 37        | 45     | 11.46%  |
| Toshiba                     | 34        | 39     | 10.53%  |
| SK hynix                    | 15        | 17     | 4.64%   |
| Samsung Electronics         | 12        | 12     | 3.72%   |
| Crucial                     | 11        | 11     | 3.41%   |
| SanDisk                     | 8         | 8      | 2.48%   |
| Micron Technology           | 8         | 9      | 2.48%   |
| Intel                       | 7         | 12     | 2.17%   |
| Kingston                    | 5         | 5      | 1.55%   |
| Fujitsu                     | 5         | 6      | 1.55%   |
| Transcend                   | 2         | 3      | 0.62%   |
| Drevo                       | 2         | 2      | 0.62%   |
| Yangtze Memory Technologies | 1         | 1      | 0.31%   |
| WINTEC                      | 1         | 1      | 0.31%   |
| WDC WDS2                    | 1         | 1      | 0.31%   |
| Unknown                     | 1         | 1      | 0.31%   |
| Teclast                     | 1         | 1      | 0.31%   |
| Team                        | 1         | 1      | 0.31%   |
| TCSUNBOW                    | 1         | 1      | 0.31%   |
| SSSTC                       | 1         | 2      | 0.31%   |
| NGFF                        | 1         | 1      | 0.31%   |
| Netac                       | 1         | 1      | 0.31%   |
| LITEON                      | 1         | 1      | 0.31%   |
| KingSpec                    | 1         | 1      | 0.31%   |
| KingDian                    | 1         | 1      | 0.31%   |
| Dogfish                     | 1         | 1      | 0.31%   |
| China                       | 1         | 1      | 0.31%   |
| BAITITON                    | 1         | 3      | 0.31%   |
| A-DATA Technology           | 1         | 1      | 0.31%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 70        | 73     | 29.41%  |
| Hitachi             | 50        | 52     | 21.01%  |
| HGST                | 40        | 49     | 16.81%  |
| WDC                 | 36        | 44     | 15.13%  |
| Toshiba             | 32        | 37     | 13.45%  |
| Fujitsu             | 5         | 6      | 2.1%    |
| Samsung Electronics | 4         | 4      | 1.68%   |
| Unknown             | 1         | 1      | 0.42%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 236       | 266    | 73.52%  |
| SSD  | 72        | 80     | 22.43%  |
| NVMe | 13        | 17     | 4.05%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-26A0RT0 500GB                     | 1         | 1      | 10%     |
| WDC WD5000BEVT-22A0RT0 500GB                     | 1         | 1      | 10%     |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 10%     |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 10%     |
| Toshiba MK3265GSX 320GB                          | 1         | 1      | 10%     |
| Seagate ST9500420AS 500GB                        | 1         | 3      | 10%     |
| Seagate ST2000LX001-1RG174 2TB                   | 1         | 1      | 10%     |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 10%     |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 10%     |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 40%     |
| Seagate             | 2         | 4      | 20%     |
| Hitachi             | 2         | 2      | 20%     |
| Toshiba             | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 1      | 10%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2669      | 4181   | 52.76%  |
| Works    | 2060      | 2915   | 40.72%  |
| Malfunc  | 320       | 363    | 6.33%   |
| Failed   | 10        | 12     | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3263      | 59.26%  |
| Samsung Electronics              | 553       | 10.04%  |
| AMD                              | 544       | 9.88%   |
| SanDisk                          | 266       | 4.83%   |
| SK hynix                         | 171       | 3.11%   |
| Kingston Technology Company      | 111       | 2.02%   |
| Micron Technology                | 108       | 1.96%   |
| Toshiba America Info Systems     | 83        | 1.51%   |
| KIOXIA                           | 81        | 1.47%   |
| Phison Electronics               | 69        | 1.25%   |
| Nvidia                           | 61        | 1.11%   |
| Micron/Crucial Technology        | 39        | 0.71%   |
| Silicon Integrated Systems [SiS] | 26        | 0.47%   |
| Silicon Motion                   | 20        | 0.36%   |
| Solid State Storage Technology   | 15        | 0.27%   |
| Union Memory (Shenzhen)          | 13        | 0.24%   |
| MAXIO Technology (Hangzhou)      | 11        | 0.2%    |
| Apple                            | 9         | 0.16%   |
| ADATA Technology                 | 9         | 0.16%   |
| Lite-On Technology               | 8         | 0.15%   |
| VIA Technologies                 | 7         | 0.13%   |
| Lenovo                           | 7         | 0.13%   |
| Shenzhen Longsys Electronics     | 5         | 0.09%   |
| Yangtze Memory Technologies      | 4         | 0.07%   |
| Solidigm                         | 3         | 0.05%   |
| Silicon Image                    | 3         | 0.05%   |
| Seagate Technology               | 3         | 0.05%   |
| Realtek Semiconductor            | 3         | 0.05%   |
| Marvell Technology Group         | 3         | 0.05%   |
| ASMedia Technology               | 3         | 0.05%   |
| JMicron Technology               | 2         | 0.04%   |
| O2 Micro                         | 1         | 0.02%   |
| Netac Technology                 | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 456       | 7.65%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 382       | 6.41%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 289       | 4.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 264       | 4.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 243       | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 230       | 3.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 221       | 3.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 187       | 3.14%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 165       | 2.77%   |
| Intel Volume Management Device NVMe RAID Controller                              | 158       | 2.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 134       | 2.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 122       | 2.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 119       | 2%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 118       | 1.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 116       | 1.95%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 114       | 1.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 98        | 1.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 87        | 1.46%   |
| Intel Comet Lake SATA AHCI Controller                                            | 76        | 1.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 75        | 1.26%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 70        | 1.17%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 68        | 1.14%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 61        | 1.02%   |
| Intel SSD 660P Series                                                            | 60        | 1.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 59        | 0.99%   |
| Intel Tiger Lake-LP SATA Controller                                              | 56        | 0.94%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 52        | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 50        | 0.84%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 49        | 0.82%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 48        | 0.81%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 48        | 0.81%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 47        | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 46        | 0.77%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 45        | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 44        | 0.74%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 42        | 0.7%    |
| Intel SSD 670p Series [Keystone Harbor]                                          | 41        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 39        | 0.65%   |
| SK hynix BC511 NVMe SSD                                                          | 36        | 0.6%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 36        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3274      | 57.13%  |
| NVMe | 1594      | 27.81%  |
| RAID | 436       | 7.61%   |
| IDE  | 427       | 7.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 3869      | 81.73%  |
| AMD          | 861       | 18.19%  |
| CentaurHauls | 2         | 0.04%   |
| ARM          | 1         | 0.02%   |
| Unknown      | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 96        | 2.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 86        | 1.82%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 74        | 1.56%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 70        | 1.48%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 69        | 1.46%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 66        | 1.39%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 61        | 1.29%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 57        | 1.2%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 57        | 1.2%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 55        | 1.16%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 55        | 1.16%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 53        | 1.12%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 51        | 1.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 48        | 1.01%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 45        | 0.95%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 43        | 0.91%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 43        | 0.91%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 41        | 0.87%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 40        | 0.84%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 40        | 0.84%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 40        | 0.84%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 39        | 0.82%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 36        | 0.76%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 36        | 0.76%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 34        | 0.72%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 33        | 0.7%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 32        | 0.68%   |
| Intel 12th Gen Core i7-12700H                 | 32        | 0.68%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 31        | 0.65%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 31        | 0.65%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 30        | 0.63%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 29        | 0.61%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 29        | 0.61%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 29        | 0.61%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 29        | 0.61%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 28        | 0.59%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 27        | 0.57%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 26        | 0.55%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 26        | 0.55%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 26        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1127      | 23.8%   |
| Intel Core i5           | 915       | 19.32%  |
| Other                   | 427       | 9.02%   |
| Intel Core 2 Duo        | 318       | 6.71%   |
| Intel Core i3           | 313       | 6.61%   |
| Intel Celeron           | 291       | 6.14%   |
| AMD Ryzen 7             | 196       | 4.14%   |
| AMD Ryzen 5             | 189       | 3.99%   |
| Intel Atom              | 185       | 3.91%   |
| Intel Pentium           | 57        | 1.2%    |
| Intel Pentium Dual-Core | 53        | 1.12%   |
| AMD E1                  | 52        | 1.1%    |
| Intel Pentium Dual      | 38        | 0.8%    |
| AMD A10                 | 37        | 0.78%   |
| Intel Genuine           | 36        | 0.76%   |
| Intel Core 2            | 36        | 0.76%   |
| AMD A4                  | 36        | 0.76%   |
| AMD Ryzen 3             | 33        | 0.7%    |
| AMD A8                  | 33        | 0.7%    |
| AMD A6                  | 33        | 0.7%    |
| AMD Ryzen 9             | 29        | 0.61%   |
| AMD E2                  | 27        | 0.57%   |
| Intel Core i9           | 22        | 0.46%   |
| AMD Ryzen 7 PRO         | 21        | 0.44%   |
| Intel Pentium Silver    | 16        | 0.34%   |
| Intel Pentium M         | 16        | 0.34%   |
| AMD Turion 64 X2 Mobile | 16        | 0.34%   |
| Intel Celeron M         | 15        | 0.32%   |
| Intel Celeron Dual-Core | 13        | 0.27%   |
| AMD Sempron             | 13        | 0.27%   |
| AMD Ryzen 5 PRO         | 12        | 0.25%   |
| AMD E                   | 12        | 0.25%   |
| AMD Mobile Sempron      | 9         | 0.19%   |
| AMD Athlon              | 9         | 0.19%   |
| AMD A12                 | 9         | 0.19%   |
| Intel Core m3           | 8         | 0.17%   |
| AMD Athlon II           | 8         | 0.17%   |
| Intel Core M            | 6         | 0.13%   |
| Intel Pentium 4         | 5         | 0.11%   |
| Intel Core Duo          | 5         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2331      | 49.18%  |
| 4       | 1572      | 33.16%  |
| 8       | 269       | 5.68%   |
| 6       | 268       | 5.65%   |
| 1       | 179       | 3.78%   |
| 14      | 53        | 1.12%   |
| 10      | 40        | 0.84%   |
| 12      | 22        | 0.46%   |
| 24      | 2         | 0.04%   |
| 16      | 2         | 0.04%   |
| 5       | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4734      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 3350      | 70.6%   |
| 1       | 1392      | 29.34%  |
| 4       | 2         | 0.04%   |
| Unknown | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4605      | 97.17%  |
| 32-bit         | 105       | 2.22%   |
| Unknown        | 29        | 0.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1407      | 28.37%  |
| 0x306a9    | 219       | 4.42%   |
| 0x206a7    | 218       | 4.4%    |
| 0x40651    | 157       | 3.17%   |
| 0x1067a    | 150       | 3.02%   |
| 0x806ea    | 148       | 2.98%   |
| 0x806ec    | 141       | 2.84%   |
| 0x806c1    | 141       | 2.84%   |
| 0x406e3    | 130       | 2.62%   |
| 0x806e9    | 113       | 2.28%   |
| 0x6fd      | 100       | 2.02%   |
| 0x20655    | 95        | 1.92%   |
| 0x906ea    | 92        | 1.86%   |
| 0x306c3    | 91        | 1.84%   |
| 0x306d4    | 86        | 1.73%   |
| 0x08108109 | 82        | 1.65%   |
| 0x10676    | 73        | 1.47%   |
| 0x08608103 | 63        | 1.27%   |
| 0x706e5    | 60        | 1.21%   |
| 0x406c3    | 60        | 1.21%   |
| 0x0a50000c | 56        | 1.13%   |
| 0x30678    | 51        | 1.03%   |
| 0x806eb    | 50        | 1.01%   |
| 0x906e9    | 48        | 0.97%   |
| 0x20652    | 48        | 0.97%   |
| 0x06006705 | 46        | 0.93%   |
| 0xa0652    | 45        | 0.91%   |
| 0x706a8    | 44        | 0.89%   |
| 0x406c4    | 40        | 0.81%   |
| 0x106ca    | 40        | 0.81%   |
| 0x706a1    | 39        | 0.79%   |
| 0x506c9    | 35        | 0.71%   |
| 0x506e3    | 34        | 0.69%   |
| 0x08600106 | 34        | 0.69%   |
| 0x07030105 | 34        | 0.69%   |
| 0x906a3    | 33        | 0.67%   |
| 0x08600104 | 32        | 0.65%   |
| 0x08108102 | 29        | 0.58%   |
| 0x0700010f | 29        | 0.58%   |
| 0x6f6      | 27        | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 822       | 17.35%  |
| Haswell          | 352       | 7.43%   |
| Penryn           | 296       | 6.25%   |
| IvyBridge        | 290       | 6.12%   |
| SandyBridge      | 279       | 5.89%   |
| TigerLake        | 234       | 4.94%   |
| Skylake          | 233       | 4.92%   |
| Core             | 207       | 4.37%   |
| Unknown          | 200       | 4.22%   |
| Silvermont       | 195       | 4.11%   |
| Westmere         | 178       | 3.76%   |
| Zen+             | 133       | 2.81%   |
| Broadwell        | 132       | 2.79%   |
| Goldmont plus    | 120       | 2.53%   |
| Excavator        | 107       | 2.26%   |
| IceLake          | 102       | 2.15%   |
| Zen 3            | 95        | 2%      |
| Zen 2            | 93        | 1.96%   |
| Alderlake Hybrid | 88        | 1.86%   |
| Bonnell          | 87        | 1.84%   |
| CometLake        | 73        | 1.54%   |
| P6               | 61        | 1.29%   |
| Puma             | 49        | 1.03%   |
| Jaguar           | 48        | 1.01%   |
| Goldmont         | 47        | 0.99%   |
| K8 Hammer        | 39        | 0.82%   |
| Bobcat           | 34        | 0.72%   |
| Zen              | 30        | 0.63%   |
| K10              | 22        | 0.46%   |
| Nehalem          | 21        | 0.44%   |
| K8 & K10 hybrid  | 20        | 0.42%   |
| K10 Llano        | 16        | 0.34%   |
| Steamroller      | 14        | 0.3%    |
| Piledriver       | 10        | 0.21%   |
| Tremont          | 7         | 0.15%   |
| NetBurst         | 5         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3417      | 56.65%  |
| Nvidia                           | 1384      | 22.94%  |
| AMD                              | 1209      | 20.04%  |
| Silicon Integrated Systems [SiS] | 16        | 0.27%   |
| VIA Technologies                 | 5         | 0.08%   |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 272       | 4.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 245       | 3.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 217       | 3.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 208       | 3.3%    |
| Intel UHD Graphics 620                                                                   | 199       | 3.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 164       | 2.6%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 160       | 2.54%   |
| Intel HD Graphics 620                                                                    | 143       | 2.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 136       | 2.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 133       | 2.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 132       | 2.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 125       | 1.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 123       | 1.95%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 117       | 1.86%   |
| Intel HD Graphics 5500                                                                   | 112       | 1.78%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 105       | 1.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 103       | 1.63%   |
| AMD Lucienne                                                                             | 102       | 1.62%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 90        | 1.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 80        | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 80        | 1.27%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 75        | 1.19%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 73        | 1.16%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 72        | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 70        | 1.11%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 69        | 1.09%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 69        | 1.09%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 63        | 1%      |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 61        | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 59        | 0.94%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 52        | 0.82%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 51        | 0.81%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 49        | 0.78%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 49        | 0.78%   |
| Intel HD Graphics 630                                                                    | 48        | 0.76%   |
| Intel HD Graphics 530                                                                    | 48        | 0.76%   |
| Nvidia GP108M [GeForce MX150]                                                            | 46        | 0.73%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 43        | 0.68%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 41        | 0.65%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 40        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 2167      | 45.63%  |
| Intel + Nvidia  | 1017      | 21.42%  |
| 1 x AMD         | 822       | 17.31%  |
| 1 x Nvidia      | 288       | 6.06%   |
| Intel + AMD     | 201       | 4.23%   |
| 2 x AMD         | 114       | 2.4%    |
| AMD + Nvidia    | 76        | 1.6%    |
| 2 x Intel       | 32        | 0.67%   |
| 1 x SiS         | 16        | 0.34%   |
| Other           | 6         | 0.13%   |
| 1 x VIA         | 5         | 0.11%   |
| 2 x Nvidia      | 4         | 0.08%   |
| 1 x S3 Graphics | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 4072      | 84.75%  |
| Proprietary | 621       | 12.92%  |
| Unknown     | 112       | 2.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 3002      | 61.52%  |
| 0.01-0.5   | 671       | 13.75%  |
| 1.01-2.0   | 613       | 12.56%  |
| 0.51-1.0   | 310       | 6.35%   |
| 3.01-4.0   | 187       | 3.83%   |
| 5.01-6.0   | 50        | 1.02%   |
| 7.01-8.0   | 32        | 0.66%   |
| 2.01-3.0   | 11        | 0.23%   |
| 8.01-16.0  | 4         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 988       | 19.07%  |
| Chimei Innolux          | 763       | 14.73%  |
| BOE                     | 714       | 13.78%  |
| LG Display              | 678       | 13.09%  |
| Samsung Electronics     | 578       | 11.16%  |
| Chi Mei Optoelectronics | 150       | 2.9%    |
| Sharp                   | 128       | 2.47%   |
| Apple                   | 118       | 2.28%   |
| Goldstar                | 98        | 1.89%   |
| Hewlett-Packard         | 84        | 1.62%   |
| Philips                 | 78        | 1.51%   |
| LG Philips              | 70        | 1.35%   |
| Lenovo                  | 68        | 1.31%   |
| PANDA                   | 66        | 1.27%   |
| Dell                    | 62        | 1.2%    |
| Ancor Communications    | 56        | 1.08%   |
| Acer                    | 45        | 0.87%   |
| InfoVision              | 37        | 0.71%   |
| BenQ                    | 37        | 0.71%   |
| HannStar                | 35        | 0.68%   |
| CSO                     | 31        | 0.6%    |
| Sony                    | 30        | 0.58%   |
| AOC                     | 25        | 0.48%   |
| CPT                     | 23        | 0.44%   |
| ASUSTek Computer        | 15        | 0.29%   |
| Toshiba                 | 14        | 0.27%   |
| Quanta Display          | 13        | 0.25%   |
| LGD                     | 13        | 0.25%   |
| Valve                   | 12        | 0.23%   |
| TMX                     | 10        | 0.19%   |
| MSI                     | 9         | 0.17%   |
| Seiko/Epson             | 8         | 0.15%   |
| InnoLux Display         | 8         | 0.15%   |
| Panasonic               | 6         | 0.12%   |
| Eizo                    | 6         | 0.12%   |
| Vestel Elektronik       | 5         | 0.1%    |
| Tianma XM               | 5         | 0.1%    |
| Iiyama                  | 5         | 0.1%    |
| Nvidia                  | 4         | 0.08%   |
| Fujitsu Siemens         | 4         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 73        | 1.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 41        | 0.78%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 37        | 0.71%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 37        | 0.71%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 36        | 0.69%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 35        | 0.67%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 35        | 0.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 35        | 0.67%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 34        | 0.65%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 32        | 0.61%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 30        | 0.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 29        | 0.55%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 28        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 26        | 0.5%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 26        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 24        | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 23        | 0.44%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 23        | 0.44%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 23        | 0.44%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 22        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 22        | 0.42%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 21        | 0.4%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 19        | 0.36%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 19        | 0.36%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 19        | 0.36%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 18        | 0.34%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 18        | 0.34%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 16        | 0.31%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 16        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 16        | 0.31%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 16        | 0.31%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 15        | 0.29%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 15        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 15        | 0.29%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 15        | 0.29%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 15        | 0.29%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 15        | 0.29%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 14        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 14        | 0.27%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 14        | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2021      | 41.21%  |
| 1366x768 (WXGA)    | 1568      | 31.97%  |
| 1280x800 (WXGA)    | 311       | 6.34%   |
| 3840x2160 (4K)     | 159       | 3.24%   |
| 1600x900 (HD+)     | 159       | 3.24%   |
| 1920x1200 (WUXGA)  | 87        | 1.77%   |
| 2560x1440 (QHD)    | 83        | 1.69%   |
| 1440x900 (WXGA+)   | 81        | 1.65%   |
| 1024x600           | 65        | 1.33%   |
| 2560x1600          | 46        | 0.94%   |
| 2160x1440          | 44        | 0.9%    |
| 1680x1050 (WSXGA+) | 39        | 0.8%    |
| 2880x1800          | 32        | 0.65%   |
| 1280x1024 (SXGA)   | 25        | 0.51%   |
| 3840x2400          | 18        | 0.37%   |
| 2560x1080          | 17        | 0.35%   |
| 1360x768           | 15        | 0.31%   |
| 3440x1440          | 13        | 0.27%   |
| 800x1280           | 12        | 0.24%   |
| 3000x2000          | 10        | 0.2%    |
| 3200x1800 (QHD+)   | 9         | 0.18%   |
| 3072x1920          | 8         | 0.16%   |
| 1024x768 (XGA)     | 8         | 0.16%   |
| 2520x1680          | 7         | 0.14%   |
| 3200x2000          | 6         | 0.12%   |
| 2240x1400          | 6         | 0.12%   |
| 2256x1504          | 5         | 0.1%    |
| 1920x540           | 5         | 0.1%    |
| 1920x1280          | 5         | 0.1%    |
| 3456x2160          | 4         | 0.08%   |
| Unknown            | 4         | 0.08%   |
| 3840x1600          | 3         | 0.06%   |
| 3840x1080          | 3         | 0.06%   |
| 1400x1050          | 3         | 0.06%   |
| 1280x720 (HD)      | 3         | 0.06%   |
| 2880x1920          | 2         | 0.04%   |
| 2880x1620          | 2         | 0.04%   |
| 2288x1287          | 2         | 0.04%   |
| 1680x945           | 2         | 0.04%   |
| 1600x1200          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2617      | 50.59%  |
| 13      | 627       | 12.12%  |
| 14      | 472       | 9.12%   |
| 17      | 238       | 4.6%    |
| 24      | 158       | 3.05%   |
| 27      | 153       | 2.96%   |
| 12      | 132       | 2.55%   |
| 23      | 112       | 2.17%   |
| 21      | 98        | 1.89%   |
| 16      | 84        | 1.62%   |
| 11      | 75        | 1.45%   |
| 10      | 73        | 1.41%   |
| Unknown | 62        | 1.2%    |
| 19      | 35        | 0.68%   |
| 18      | 28        | 0.54%   |
| 34      | 22        | 0.43%   |
| 40      | 19        | 0.37%   |
| 22      | 19        | 0.37%   |
| 31      | 18        | 0.35%   |
| 54      | 16        | 0.31%   |
| 20      | 16        | 0.31%   |
| 7       | 12        | 0.23%   |
| 84      | 11        | 0.21%   |
| 32      | 11        | 0.21%   |
| 25      | 7         | 0.14%   |
| 72      | 6         | 0.12%   |
| 8       | 6         | 0.12%   |
| 65      | 5         | 0.1%    |
| 35      | 5         | 0.1%    |
| 26      | 5         | 0.1%    |
| 48      | 4         | 0.08%   |
| 58      | 3         | 0.06%   |
| 52      | 3         | 0.06%   |
| 37      | 3         | 0.06%   |
| 142     | 2         | 0.04%   |
| 86      | 2         | 0.04%   |
| 49      | 2         | 0.04%   |
| 46      | 2         | 0.04%   |
| 36      | 2         | 0.04%   |
| 28      | 2         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 3380      | 65.72%  |
| 201-300        | 632       | 12.29%  |
| 501-600        | 399       | 7.76%   |
| 351-400        | 314       | 6.11%   |
| 401-500        | 178       | 3.46%   |
| Unknown        | 62        | 1.21%   |
| 601-700        | 39        | 0.76%   |
| 1001-1500      | 36        | 0.7%    |
| 701-800        | 35        | 0.68%   |
| 801-900        | 28        | 0.54%   |
| 1501-2000      | 18        | 0.35%   |
| 1-100          | 12        | 0.23%   |
| 101-200        | 7         | 0.14%   |
| More than 2000 | 2         | 0.04%   |
| 901-1000       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3810      | 81.74%  |
| 16/10   | 623       | 13.37%  |
| 3/2     | 81        | 1.74%   |
| Unknown | 46        | 0.99%   |
| 21/9    | 32        | 0.69%   |
| 5/4     | 27        | 0.58%   |
| 4/3     | 16        | 0.34%   |
| 0.67    | 11        | 0.24%   |
| 32/9    | 5         | 0.11%   |
| 6/5     | 4         | 0.09%   |
| 1.00    | 2         | 0.04%   |
| 0.56    | 2         | 0.04%   |
| 2.21    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2622      | 50.79%  |
| 81-90          | 839       | 16.25%  |
| 201-250        | 317       | 6.14%   |
| 71-80          | 255       | 4.94%   |
| 121-130        | 200       | 3.87%   |
| 301-350        | 157       | 3.04%   |
| 61-70          | 126       | 2.44%   |
| 51-60          | 75        | 1.45%   |
| 41-50          | 74        | 1.43%   |
| 151-200        | 71        | 1.38%   |
| Unknown        | 62        | 1.2%    |
| 111-120        | 60        | 1.16%   |
| 351-500        | 57        | 1.1%    |
| 251-300        | 52        | 1.01%   |
| More than 1000 | 50        | 0.97%   |
| 141-150        | 39        | 0.76%   |
| 131-140        | 33        | 0.64%   |
| 501-1000       | 32        | 0.62%   |
| 91-100         | 23        | 0.45%   |
| 1-40           | 18        | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1955      | 38.43%  |
| 101-120       | 1587      | 31.2%   |
| 51-100        | 950       | 18.68%  |
| 161-240       | 365       | 7.18%   |
| More than 240 | 128       | 2.52%   |
| Unknown       | 62        | 1.22%   |
| 1-50          | 40        | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3999      | 82.39%  |
| 2     | 669       | 13.78%  |
| 0     | 127       | 2.62%   |
| 3     | 53        | 1.09%   |
| 4     | 6         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2561      | 33.92%  |
| Intel                             | 2245      | 29.73%  |
| Qualcomm Atheros                  | 1117      | 14.79%  |
| Broadcom                          | 541       | 7.16%   |
| Marvell Technology Group          | 136       | 1.8%    |
| Broadcom Limited                  | 122       | 1.62%   |
| MediaTek                          | 121       | 1.6%    |
| Ralink                            | 80        | 1.06%   |
| TP-Link                           | 69        | 0.91%   |
| Ralink Technology                 | 50        | 0.66%   |
| Nvidia                            | 42        | 0.56%   |
| ASIX Electronics                  | 36        | 0.48%   |
| Dell                              | 31        | 0.41%   |
| Huawei Technologies               | 30        | 0.4%    |
| Xiaomi                            | 28        | 0.37%   |
| Samsung Electronics               | 27        | 0.36%   |
| Ericsson Business Mobile Networks | 23        | 0.3%    |
| JMicron Technology                | 22        | 0.29%   |
| Sierra Wireless                   | 20        | 0.26%   |
| Silicon Integrated Systems [SiS]  | 19        | 0.25%   |
| Qualcomm                          | 18        | 0.24%   |
| Attansic Technology               | 17        | 0.23%   |
| Qualcomm Atheros Communications   | 13        | 0.17%   |
| OPPO Electronics                  | 13        | 0.17%   |
| Hewlett-Packard                   | 13        | 0.17%   |
| DisplayLink                       | 12        | 0.16%   |
| Sitecom Europe                    | 9         | 0.12%   |
| Lenovo                            | 9         | 0.12%   |
| NetGear                           | 8         | 0.11%   |
| Fibocom                           | 7         | 0.09%   |
| D-Link System                     | 7         | 0.09%   |
| Apple                             | 7         | 0.09%   |
| ZTE WCDMA Technologies MSM        | 6         | 0.08%   |
| T & A Mobile Phones               | 6         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 6         | 0.08%   |
| D-Link                            | 6         | 0.08%   |
| AMD                               | 6         | 0.08%   |
| ICS Advent                        | 5         | 0.07%   |
| Belkin Components                 | 5         | 0.07%   |
| Microsoft                         | 4         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1543      | 17.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 455       | 5.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 218       | 2.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 195       | 2.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 191       | 2.15%   |
| Intel Wireless 8265 / 8275                                              | 189       | 2.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 181       | 2.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 178       | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 176       | 1.98%   |
| Intel Wi-Fi 6 AX201                                                     | 164       | 1.84%   |
| Intel Wi-Fi 6 AX200                                                     | 163       | 1.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 145       | 1.63%   |
| Intel Wireless 7265                                                     | 135       | 1.52%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 126       | 1.42%   |
| Intel Wireless 3165                                                     | 124       | 1.39%   |
| Intel Wireless 7260                                                     | 108       | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 106       | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 97        | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 88        | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 86        | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 84        | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 81        | 0.91%   |
| Intel Wireless 8260                                                     | 79        | 0.89%   |
| Intel WiFi Link 5100                                                    | 77        | 0.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 75        | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                           | 75        | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 71        | 0.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 71        | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 70        | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 64        | 0.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 60        | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                                   | 57        | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 50        | 0.56%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 50        | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 45        | 0.51%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 44        | 0.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 42        | 0.47%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 42        | 0.47%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 41        | 0.46%   |
| Intel Ethernet Connection I218-LM                                       | 40        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2154      | 44.07%  |
| Qualcomm Atheros                      | 1020      | 20.87%  |
| Realtek Semiconductor                 | 794       | 16.24%  |
| Broadcom                              | 397       | 8.12%   |
| MediaTek                              | 117       | 2.39%   |
| Broadcom Limited                      | 85        | 1.74%   |
| Ralink                                | 80        | 1.64%   |
| TP-Link                               | 57        | 1.17%   |
| Ralink Technology                     | 50        | 1.02%   |
| Dell                                  | 22        | 0.45%   |
| Sierra Wireless                       | 20        | 0.41%   |
| Qualcomm Atheros Communications       | 13        | 0.27%   |
| Sitecom Europe                        | 8         | 0.16%   |
| Qualcomm                              | 8         | 0.16%   |
| NetGear                               | 8         | 0.16%   |
| Ericsson Business Mobile Networks     | 8         | 0.16%   |
| Fibocom                               | 7         | 0.14%   |
| D-Link System                         | 7         | 0.14%   |
| D-Link                                | 5         | 0.1%    |
| Belkin Components                     | 5         | 0.1%    |
| Microsoft                             | 4         | 0.08%   |
| ASUSTek Computer                      | 4         | 0.08%   |
| ZyDAS                                 | 3         | 0.06%   |
| U.S. Robotics                         | 2         | 0.04%   |
| Qcom                                  | 2         | 0.04%   |
| Hewlett-Packard                       | 2         | 0.04%   |
| Edimax Technology                     | 2         | 0.04%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| AVM                                   | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 218       | 4.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 195       | 3.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 191       | 3.89%   |
| Intel Wireless 8265 / 8275                                              | 189       | 3.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 178       | 3.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 176       | 3.58%   |
| Intel Wi-Fi 6 AX201                                                     | 164       | 3.34%   |
| Intel Wi-Fi 6 AX200                                                     | 163       | 3.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 145       | 2.95%   |
| Intel Wireless 7265                                                     | 135       | 2.75%   |
| Intel Wireless 3165                                                     | 124       | 2.52%   |
| Intel Wireless 7260                                                     | 108       | 2.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 106       | 2.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 97        | 1.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 88        | 1.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 86        | 1.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 84        | 1.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 81        | 1.65%   |
| Intel Wireless 8260                                                     | 79        | 1.61%   |
| Intel WiFi Link 5100                                                    | 77        | 1.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 75        | 1.53%   |
| Broadcom BCM43142 802.11b/g/n                                           | 75        | 1.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 71        | 1.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 71        | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 70        | 1.43%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 64        | 1.3%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 60        | 1.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 50        | 1.02%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 50        | 1.02%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 44        | 0.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 42        | 0.86%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 42        | 0.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 39        | 0.79%   |
| Intel Centrino Advanced-N 6200                                          | 39        | 0.79%   |
| Intel Wireless-AC 9260                                                  | 37        | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 36        | 0.73%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 35        | 0.71%   |
| Intel Centrino Wireless-N 2230                                          | 35        | 0.71%   |
| Intel Wireless 3160                                                     | 34        | 0.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 34        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2255      | 58.39%  |
| Intel                                  | 683       | 17.69%  |
| Qualcomm Atheros                       | 224       | 5.8%    |
| Broadcom                               | 208       | 5.39%   |
| Marvell Technology Group               | 136       | 3.52%   |
| Nvidia                                 | 41        | 1.06%   |
| Broadcom Limited                       | 38        | 0.98%   |
| ASIX Electronics                       | 36        | 0.93%   |
| Xiaomi                                 | 28        | 0.73%   |
| JMicron Technology                     | 22        | 0.57%   |
| Huawei Technologies                    | 22        | 0.57%   |
| Samsung Electronics                    | 19        | 0.49%   |
| Silicon Integrated Systems [SiS]       | 17        | 0.44%   |
| Attansic Technology                    | 17        | 0.44%   |
| OPPO Electronics                       | 13        | 0.34%   |
| TP-Link                                | 12        | 0.31%   |
| DisplayLink                            | 12        | 0.31%   |
| Qualcomm                               | 10        | 0.26%   |
| Lenovo                                 | 9         | 0.23%   |
| Apple                                  | 7         | 0.18%   |
| ZTE WCDMA Technologies MSM             | 6         | 0.16%   |
| OnePlus Technology (Shenzhen)          | 6         | 0.16%   |
| ICS Advent                             | 5         | 0.13%   |
| T & A Mobile Phones                    | 4         | 0.1%    |
| MediaTek                               | 4         | 0.1%    |
| HMD Global                             | 4         | 0.1%    |
| Hewlett-Packard                        | 4         | 0.1%    |
| VIA Technologies                       | 3         | 0.08%   |
| Motorola PCS                           | 3         | 0.08%   |
| Spreadtrum Communications              | 2         | 0.05%   |
| LG Electronics                         | 2         | 0.05%   |
| Google                                 | 2         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| Sitecom Europe                         | 1         | 0.03%   |
| MosChip Semiconductor                  | 1         | 0.03%   |
| Microchip Technology                   | 1         | 0.03%   |
| D-Link                                 | 1         | 0.03%   |
| Cypress Semiconductor                  | 1         | 0.03%   |
| ADMtek                                 | 1         | 0.03%   |
| Accton Technology                      | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1543      | 39.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 455       | 11.66%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 181       | 4.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 126       | 3.23%   |
| Intel Ethernet Connection (4) I219-LM                                          | 57        | 1.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 45        | 1.15%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 41        | 1.05%   |
| Intel Ethernet Connection I218-LM                                              | 40        | 1.02%   |
| Intel 82577LM Gigabit Network Connection                                       | 38        | 0.97%   |
| Intel 82567LM Gigabit Network Connection                                       | 38        | 0.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 37        | 0.95%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 36        | 0.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 33        | 0.85%   |
| Intel Ethernet Connection I219-LM                                              | 33        | 0.85%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 32        | 0.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 31        | 0.79%   |
| Intel Ethernet Connection I217-LM                                              | 30        | 0.77%   |
| Intel Ethernet Connection (3) I218-LM                                          | 28        | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 26        | 0.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 24        | 0.61%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 24        | 0.61%   |
| Intel Ethernet Connection (4) I219-V                                           | 24        | 0.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 23        | 0.59%   |
| Intel Ethernet Connection I219-V                                               | 23        | 0.59%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 23        | 0.59%   |
| Nvidia MCP79 Ethernet                                                          | 22        | 0.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 21        | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 20        | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 20        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 19        | 0.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 19        | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 18        | 0.46%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 18        | 0.46%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 18        | 0.46%   |
| Intel Ethernet Connection (10) I219-V                                          | 18        | 0.46%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 17        | 0.44%   |
| Intel Ethernet Connection I217-V                                               | 17        | 0.44%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 17        | 0.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 16        | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                                          | 16        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4639      | 54.93%  |
| Ethernet | 3718      | 44.02%  |
| Modem    | 83        | 0.98%   |
| Unknown  | 6         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3907      | 79.62%  |
| Ethernet | 997       | 20.32%  |
| Unknown  | 2         | 0.04%   |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3382      | 71.35%  |
| 1     | 1221      | 25.76%  |
| 0     | 107       | 2.26%   |
| 3     | 30        | 0.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4413      | 91.84%  |
| Yes  | 392       | 8.16%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1620      | 45.13%  |
| Realtek Semiconductor           | 474       | 13.2%   |
| Qualcomm Atheros Communications | 246       | 6.85%   |
| IMC Networks                    | 217       | 6.04%   |
| Lite-On Technology              | 197       | 5.49%   |
| Broadcom                        | 185       | 5.15%   |
| Foxconn / Hon Hai               | 159       | 4.43%   |
| Apple                           | 107       | 2.98%   |
| Hewlett-Packard                 | 73        | 2.03%   |
| Realtek                         | 67        | 1.87%   |
| Cambridge Silicon Radio         | 46        | 1.28%   |
| Dell                            | 45        | 1.25%   |
| Ralink                          | 39        | 1.09%   |
| Toshiba                         | 36        | 1%      |
| ASUSTek Computer                | 18        | 0.5%    |
| Alps Electric                   | 17        | 0.47%   |
| MediaTek                        | 10        | 0.28%   |
| Ralink Technology               | 7         | 0.19%   |
| Foxconn International           | 7         | 0.19%   |
| Chicony Electronics             | 4         | 0.11%   |
| Askey Computer                  | 4         | 0.11%   |
| Taiyo Yuden                     | 3         | 0.08%   |
| Integrated System Solution      | 2         | 0.06%   |
| USI                             | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Conwise Technology              | 1         | 0.03%   |
| Actions                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 658       | 18.33%  |
| Intel Bluetooth Device                                                              | 370       | 10.31%  |
| Realtek Bluetooth Radio                                                             | 334       | 9.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 242       | 6.74%   |
| Intel AX200 Bluetooth                                                               | 158       | 4.4%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 108       | 3.01%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 99        | 2.76%   |
| IMC Networks Bluetooth Device                                                       | 80        | 2.23%   |
| Realtek Bluetooth Radio                                                             | 67        | 1.87%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 65        | 1.81%   |
| Apple Bluetooth Host Controller                                                     | 60        | 1.67%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 55        | 1.53%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 49        | 1.36%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 49        | 1.36%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 48        | 1.34%   |
| IMC Networks Bluetooth Radio                                                        | 48        | 1.34%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 47        | 1.31%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 46        | 1.28%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 45        | 1.25%   |
| Lite-On Bluetooth Device                                                            | 45        | 1.25%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 40        | 1.11%   |
| Ralink RT3290 Bluetooth                                                             | 39        | 1.09%   |
| IMC Networks Wireless_Device                                                        | 39        | 1.09%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 35        | 0.97%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 35        | 0.97%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 34        | 0.95%   |
| Intel AX210 Bluetooth                                                               | 29        | 0.81%   |
| Broadcom BCM2045 Bluetooth                                                          | 26        | 0.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 24        | 0.67%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 24        | 0.67%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 21        | 0.58%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 21        | 0.58%   |
| Apple Bluetooth USB Host Controller                                                 | 21        | 0.58%   |
| Apple Bluetooth HCI                                                                 | 21        | 0.58%   |
| Lite-On Wireless_Device                                                             | 19        | 0.53%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 19        | 0.53%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 18        | 0.5%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 18        | 0.5%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 17        | 0.47%   |
| Realtek RTL8723B Bluetooth                                                          | 16        | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3704      | 66.57%  |
| AMD                                          | 998       | 17.94%  |
| Nvidia                                       | 565       | 10.15%  |
| C-Media Electronics                          | 32        | 0.58%   |
| Silicon Integrated Systems [SiS]             | 26        | 0.47%   |
| Logitech                                     | 20        | 0.36%   |
| GN Netcom                                    | 20        | 0.36%   |
| JMTek                                        | 19        | 0.34%   |
| Realtek Semiconductor                        | 15        | 0.27%   |
| Generalplus Technology                       | 13        | 0.23%   |
| CMX Systems                                  | 10        | 0.18%   |
| Texas Instruments                            | 9         | 0.16%   |
| VIA Technologies                             | 7         | 0.13%   |
| Lenovo                                       | 7         | 0.13%   |
| Apple                                        | 7         | 0.13%   |
| Hewlett-Packard                              | 6         | 0.11%   |
| Sony                                         | 5         | 0.09%   |
| Plantronics                                  | 5         | 0.09%   |
| M-Audio                                      | 5         | 0.09%   |
| BEHRINGER International                      | 5         | 0.09%   |
| Huawei Technologies                          | 4         | 0.07%   |
| Fujitsu                                      | 4         | 0.07%   |
| Creative Technology                          | 4         | 0.07%   |
| ASUSTek Computer                             | 4         | 0.07%   |
| Samson Technologies                          | 3         | 0.05%   |
| Razer USA                                    | 3         | 0.05%   |
| Medeli Electronics                           | 3         | 0.05%   |
| Focusrite-Novation                           | 3         | 0.05%   |
| BR23                                         | 3         | 0.05%   |
| Syntek                                       | 2         | 0.04%   |
| SteelSeries ApS                              | 2         | 0.04%   |
| Sennheiser Communications                    | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)                | 2         | 0.04%   |
| Mark of the Unicorn                          | 2         | 0.04%   |
| DSEA A/S                                     | 2         | 0.04%   |
| Dell                                         | 2         | 0.04%   |
| Corsair                                      | 2         | 0.04%   |
| Cambridge Silicon Radio                      | 2         | 0.04%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.02%   |
| XMOS                                         | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 529       | 7.79%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 471       | 6.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 330       | 4.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 260       | 3.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 257       | 3.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 239       | 3.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 234       | 3.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 210       | 3.09%   |
| Intel 8 Series HD Audio Controller                                                                | 210       | 3.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 199       | 2.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 155       | 2.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 154       | 2.27%   |
| AMD FCH Azalia Controller                                                                         | 153       | 2.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 143       | 2.1%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 141       | 2.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 139       | 2.05%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 138       | 2.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 134       | 1.97%   |
| Intel Broadwell-U Audio Controller                                                                | 132       | 1.94%   |
| AMD Kabini HDMI/DP Audio                                                                          | 132       | 1.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 128       | 1.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 120       | 1.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 117       | 1.72%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 106       | 1.56%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 93        | 1.37%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 76        | 1.12%   |
| AMD High Definition Audio Controller                                                              | 72        | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 69        | 1.02%   |
| Intel Comet Lake PCH cAVS                                                                         | 65        | 0.96%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 63        | 0.93%   |
| Intel CM238 HD Audio Controller                                                                   | 62        | 0.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 54        | 0.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 54        | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 49        | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 47        | 0.69%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 43        | 0.63%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 40        | 0.59%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 39        | 0.57%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 38        | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 37        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 955       | 29.38%  |
| SK hynix                     | 708       | 21.78%  |
| Micron Technology            | 418       | 12.86%  |
| Unknown                      | 281       | 8.64%   |
| Kingston                     | 275       | 8.46%   |
| Crucial                      | 154       | 4.74%   |
| Ramaxel Technology           | 75        | 2.31%   |
| Elpida                       | 75        | 2.31%   |
| Unknown (ABCD)               | 70        | 2.15%   |
| A-DATA Technology            | 48        | 1.48%   |
| Corsair                      | 44        | 1.35%   |
| Nanya Technology             | 38        | 1.17%   |
| Unknown                      | 19        | 0.58%   |
| Team                         | 13        | 0.4%    |
| Transcend                    | 10        | 0.31%   |
| Timetec                      | 6         | 0.18%   |
| G.Skill                      | 6         | 0.18%   |
| ASint Technology             | 6         | 0.18%   |
| Toshiba                      | 5         | 0.15%   |
| 48spaces                     | 5         | 0.15%   |
| Qimonda                      | 4         | 0.12%   |
| Patriot                      | 4         | 0.12%   |
| Silicon Power                | 2         | 0.06%   |
| Lexar                        | 2         | 0.06%   |
| CSX                          | 2         | 0.06%   |
| ChangXin Memory              | 2         | 0.06%   |
| Apacer                       | 2         | 0.06%   |
| Unknown (8A5D)               | 1         | 0.03%   |
| Unknown (8A02)               | 1         | 0.03%   |
| Unknown (7F7F7F7F7F7F6B00)   | 1         | 0.03%   |
| Unknown (0x5846)             | 1         | 0.03%   |
| Unknown (0x08A4FFFFFFFFFFFF) | 1         | 0.03%   |
| Unigen                       | 1         | 0.03%   |
| Unifosa                      | 1         | 0.03%   |
| Teikon                       | 1         | 0.03%   |
| Smart Brazil                 | 1         | 0.03%   |
| SHARETRONIC                  | 1         | 0.03%   |
| Sesame                       | 1         | 0.03%   |
| pqi                          | 1         | 0.03%   |
| PKI/Kingston                 | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 64        | 1.86%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 50        | 1.45%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 48        | 1.39%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 41        | 1.19%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 34        | 0.99%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 34        | 0.99%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 34        | 0.99%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 33        | 0.96%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 29        | 0.84%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 28        | 0.81%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 28        | 0.81%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 27        | 0.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 26        | 0.75%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 26        | 0.75%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 26        | 0.75%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 26        | 0.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 0.75%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 25        | 0.72%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 25        | 0.72%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 25        | 0.72%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 23        | 0.67%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 23        | 0.67%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 23        | 0.67%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 21        | 0.61%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.61%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 21        | 0.61%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 20        | 0.58%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 20        | 0.58%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 19        | 0.55%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 19        | 0.55%   |
| Unknown                                                          | 19        | 0.55%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 18        | 0.52%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 18        | 0.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 18        | 0.52%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 17        | 0.49%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 17        | 0.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 0.46%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 16        | 0.46%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 16        | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 16        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1318      | 47.04%  |
| DDR3    | 907       | 32.37%  |
| LPDDR4  | 179       | 6.39%   |
| DDR2    | 158       | 5.64%   |
| LPDDR3  | 73        | 2.61%   |
| SDRAM   | 57        | 2.03%   |
| DDR5    | 38        | 1.36%   |
| LPDDR5  | 30        | 1.07%   |
| Unknown | 22        | 0.79%   |
| DRAM    | 12        | 0.43%   |
| DDR     | 8         | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2494      | 88.16%  |
| Row Of Chips | 306       | 10.82%  |
| DIMM         | 15        | 0.53%   |
| Chip         | 10        | 0.35%   |
| Unknown      | 4         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1193      | 38.85%  |
| 4096  | 910       | 29.63%  |
| 16384 | 406       | 13.22%  |
| 2048  | 394       | 12.83%  |
| 1024  | 83        | 2.7%    |
| 32768 | 68        | 2.21%   |
| 512   | 16        | 0.52%   |
| 256   | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 597       | 19.74%  |
| 1600    | 582       | 19.25%  |
| 3200    | 569       | 18.82%  |
| 2400    | 237       | 7.84%   |
| 1334    | 152       | 5.03%   |
| 2133    | 142       | 4.7%    |
| 1333    | 98        | 3.24%   |
| Unknown | 91        | 3.01%   |
| 667     | 88        | 2.91%   |
| 4267    | 63        | 2.08%   |
| 3266    | 48        | 1.59%   |
| 1066    | 46        | 1.52%   |
| 800     | 43        | 1.42%   |
| 4800    | 39        | 1.29%   |
| 1067    | 35        | 1.16%   |
| 6400    | 30        | 0.99%   |
| 1867    | 30        | 0.99%   |
| 4199    | 23        | 0.76%   |
| 2048    | 18        | 0.6%    |
| 8400    | 17        | 0.56%   |
| 533     | 16        | 0.53%   |
| 4266    | 12        | 0.4%    |
| 975     | 11        | 0.36%   |
| 2933    | 7         | 0.23%   |
| 3733    | 4         | 0.13%   |
| 333     | 4         | 0.13%   |
| 5600    | 2         | 0.07%   |
| 3600    | 2         | 0.07%   |
| 3400    | 2         | 0.07%   |
| 1866    | 2         | 0.07%   |
| 1639    | 2         | 0.07%   |
| 1200    | 2         | 0.07%   |
| 400     | 2         | 0.07%   |
| 3000    | 1         | 0.03%   |
| 2800    | 1         | 0.03%   |
| 2666    | 1         | 0.03%   |
| 2267    | 1         | 0.03%   |
| 2134    | 1         | 0.03%   |
| 2000    | 1         | 0.03%   |
| 1776    | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 23        | 31.94%  |
| Samsung Electronics | 18        | 25%     |
| Canon               | 12        | 16.67%  |
| Brother Industries  | 7         | 9.72%   |
| Seiko Epson         | 6         | 8.33%   |
| Pantum              | 2         | 2.78%   |
| Xerox               | 1         | 1.39%   |
| Sagem               | 1         | 1.39%   |
| ICS Advent          | 1         | 1.39%   |
| Apple               | 1         | 1.39%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung M2070 Series                 | 4         | 5.48%   |
| Samsung ML-216x Series Laser Printer | 3         | 4.11%   |
| Seiko Epson Printer                  | 2         | 2.74%   |
| Samsung M267x 287x Series            | 2         | 2.74%   |
| HP OfficeJet 3830 series             | 2         | 2.74%   |
| HP Officejet 2620 series             | 2         | 2.74%   |
| Xerox B215                           | 1         | 1.37%   |
| Seiko Epson WF-2510 Series           | 1         | 1.37%   |
| Seiko Epson L355 Series              | 1         | 1.37%   |
| Seiko Epson ET-2850 Series           | 1         | 1.37%   |
| Seiko Epson ET-2810 Series           | 1         | 1.37%   |
| Samsung SCX-483x 5x3x Series         | 1         | 1.37%   |
| Samsung SCX-4623 Series              | 1         | 1.37%   |
| Samsung SCX-4300 Series              | 1         | 1.37%   |
| Samsung ML-331x Series Laser Printer | 1         | 1.37%   |
| Samsung ML-2010P Mono Laser Printer  | 1         | 1.37%   |
| Samsung ML-1865W Series              | 1         | 1.37%   |
| Samsung ML-1640 Series Laser Printer | 1         | 1.37%   |
| Samsung CLP-325 Color Laser Printer  | 1         | 1.37%   |
| Samsung C3060 Series                 | 1         | 1.37%   |
| Sagem Laser Pro LL                   | 1         | 1.37%   |
| Pantum P2500W series                 | 1         | 1.37%   |
| Pantum M6500W series                 | 1         | 1.37%   |
| ICS Advent Parallel Adapter          | 1         | 1.37%   |
| HP Officejet Pro 6230                | 1         | 1.37%   |
| HP OfficeJet 6950                    | 1         | 1.37%   |
| HP OfficeJet 5600 (USBHUB)           | 1         | 1.37%   |
| HP LaserJet P3005                    | 1         | 1.37%   |
| HP LaserJet P2055 series             | 1         | 1.37%   |
| HP LaserJet P1102                    | 1         | 1.37%   |
| HP LaserJet 1200                     | 1         | 1.37%   |
| HP LaserJet 1020                     | 1         | 1.37%   |
| HP LaserJet 1018                     | 1         | 1.37%   |
| HP LaserJet 1015                     | 1         | 1.37%   |
| HP LaserJet 1010                     | 1         | 1.37%   |
| HP ENVY Photo 6200 series            | 1         | 1.37%   |
| HP ENVY 5000 series                  | 1         | 1.37%   |
| HP ENVY 4520 series                  | 1         | 1.37%   |
| HP DeskJet 940c                      | 1         | 1.37%   |
| HP DeskJet 840c                      | 1         | 1.37%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 46.15%  |
| Seiko Epson     | 5         | 38.46%  |
| Hewlett-Packard | 2         | 15.38%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 2         | 14.29%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 7.14%   |
| Seiko Epson ES-D400 [GT-S80]                             | 1         | 7.14%   |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]               | 1         | 7.14%   |
| HP Scanjet G2710                                         | 1         | 7.14%   |
| HP ScanJet 3570c                                         | 1         | 7.14%   |
| Canon CanoScan LIDE 25                                   | 1         | 7.14%   |
| Canon CanoScan LiDE 220                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 120                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 110                                  | 1         | 7.14%   |
| Canon CanoScan LiDE 100                                  | 1         | 7.14%   |
| Canon CanoScan 4400F                                     | 1         | 7.14%   |
| Canon CanoScan 1220U                                     | 1         | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1102      | 25.86%  |
| IMC Networks                           | 520       | 12.2%   |
| Realtek Semiconductor                  | 318       | 7.46%   |
| Microdia                               | 301       | 7.06%   |
| Bison Electronics                      | 250       | 5.87%   |
| Quanta                                 | 241       | 5.65%   |
| Suyin                                  | 197       | 4.62%   |
| Cheng Uei Precision Industry (Foxlink) | 189       | 4.43%   |
| Sunplus Innovation Technology          | 178       | 4.18%   |
| Syntek                                 | 111       | 2.6%    |
| Alcor Micro                            | 108       | 2.53%   |
| Acer                                   | 98        | 2.3%    |
| Lite-On Technology                     | 97        | 2.28%   |
| Apple                                  | 94        | 2.21%   |
| Luxvisions Innotech Limited            | 90        | 2.11%   |
| Ricoh                                  | 52        | 1.22%   |
| Silicon Motion                         | 51        | 1.2%    |
| Logitech                               | 38        | 0.89%   |
| Z-Star Microelectronics                | 21        | 0.49%   |
| Sonix Technology                       | 19        | 0.45%   |
| Samsung Electronics                    | 18        | 0.42%   |
| ALi                                    | 18        | 0.42%   |
| Primax Electronics                     | 15        | 0.35%   |
| icSpring                               | 14        | 0.33%   |
| Lenovo                                 | 10        | 0.23%   |
| Sunplus Technology                     | 9         | 0.21%   |
| DigiTech                               | 9         | 0.21%   |
| Importek                               | 8         | 0.19%   |
| SunplusIT                              | 7         | 0.16%   |
| GEMBIRD                                | 6         | 0.14%   |
| ARC International                      | 6         | 0.14%   |
| Microsoft                              | 5         | 0.12%   |
| Genesys Logic                          | 5         | 0.12%   |
| ShineTech                              | 4         | 0.09%   |
| Generalplus Technology                 | 4         | 0.09%   |
| kingcome                               | 3         | 0.07%   |
| WaveRider Communications               | 2         | 0.05%   |
| USB Camera CS                          | 2         | 0.05%   |
| Unknown (3730304233333731323245)       | 2         | 0.05%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 175       | 4.09%   |
| Microdia Integrated_Webcam_HD                           | 135       | 3.15%   |
| Chicony HD WebCam                                       | 105       | 2.45%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 101       | 2.36%   |
| IMC Networks Integrated Camera                          | 90        | 2.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 77        | 1.8%    |
| Realtek USB Camera                                      | 74        | 1.73%   |
| Realtek Integrated_Webcam_HD                            | 72        | 1.68%   |
| Bison Integrated Camera                                 | 71        | 1.66%   |
| Syntek Integrated Camera                                | 63        | 1.47%   |
| Alcor Micro USB 2.0 Camera                              | 55        | 1.28%   |
| Sunplus Integrated_Webcam_HD                            | 53        | 1.24%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 53        | 1.24%   |
| Chicony USB2.0 VGA UVC WebCam                           | 52        | 1.21%   |
| Chicony HP TrueVision HD                                | 49        | 1.14%   |
| Chicony USB2.0 HD UVC WebCam                            | 46        | 1.07%   |
| IMC Networks HD Camera                                  | 44        | 1.03%   |
| Chicony HP TrueVision HD Camera                         | 44        | 1.03%   |
| Quanta HP TrueVision HD Camera                          | 41        | 0.96%   |
| Bison HD Webcam                                         | 41        | 0.96%   |
| Chicony HP Webcam                                       | 35        | 0.82%   |
| Apple iPhone 5/5C/5S/6/SE                               | 35        | 0.82%   |
| Chicony HP HD Camera                                    | 34        | 0.79%   |
| Quanta HD User Facing                                   | 33        | 0.77%   |
| Sunplus HD WebCam                                       | 32        | 0.75%   |
| Chicony FJ Camera                                       | 32        | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 31        | 0.72%   |
| Apple Built-in iSight                                   | 31        | 0.72%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 29        | 0.68%   |
| Quanta HP Webcam                                        | 29        | 0.68%   |
| Chicony USB2.0 Camera                                   | 29        | 0.68%   |
| Realtek USB2.0 VGA UVC WebCam                           | 28        | 0.65%   |
| IMC Networks ov9734_azurewave_camera                    | 28        | 0.65%   |
| Lite-On HP HD Camera                                    | 27        | 0.63%   |
| Chicony HP Wide Vision HD Camera                        | 27        | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 27        | 0.63%   |
| Suyin HP Truevision HD                                  | 26        | 0.61%   |
| Microdia Integrated Webcam                              | 26        | 0.61%   |
| Chicony HD User Facing                                  | 26        | 0.61%   |
| Alcor Micro Asus Integrated Webcam                      | 25        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 241       | 29.53%  |
| Synaptics                          | 173       | 21.2%   |
| Shenzhen Goodix Technology         | 148       | 18.14%  |
| Elan Microelectronics              | 101       | 12.38%  |
| Upek                               | 45        | 5.51%   |
| LighTuning Technology              | 45        | 5.51%   |
| AuthenTec                          | 45        | 5.51%   |
| Focal-systems.Corp                 | 7         | 0.86%   |
| STMicroelectronics                 | 6         | 0.74%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.37%   |
| Microsoft                          | 1         | 0.12%   |
| HOLTEK                             | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 115       | 14.09%  |
| Elan ELAN:ARM-M4                                                           | 68        | 8.33%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 52        | 6.37%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 50        | 6.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 39        | 4.78%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 33        | 4.04%   |
| Elan ELAN:Fingerprint                                                      | 33        | 4.04%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 26        | 3.19%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 25        | 3.06%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 25        | 3.06%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 24        | 2.94%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 23        | 2.82%   |
| Shenzhen Goodix Fingerprint Reader                                         | 19        | 2.33%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 18        | 2.21%   |
| Validity Sensors Fingerprint scanner                                       | 18        | 2.21%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 1.84%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 15        | 1.84%   |
| Shenzhen Goodix FingerPrint                                                | 14        | 1.72%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.72%   |
| Validity Sensors VFS491                                                    | 11        | 1.35%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 1.35%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 1.35%   |
| Unknown                                                                    | 11        | 1.35%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 1.23%   |
| Synaptics Fingerprint reader [HP G6]                                       | 10        | 1.23%   |
| Synaptics  WBDI                                                            | 9         | 1.1%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 8         | 0.98%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.98%   |
| AuthenTec AES2810                                                          | 8         | 0.98%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.86%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 0.86%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 7         | 0.86%   |
| AuthenTec AES1600                                                          | 7         | 0.86%   |
| Upek TCS5B Fingerprint sensor                                              | 6         | 0.74%   |
| Synaptics UWP WBDI Device                                                  | 6         | 0.74%   |
| Synaptics TouchPad                                                         | 6         | 0.74%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 0.74%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 0.74%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.61%   |
| LighTuning Fingerprint Reader                                              | 5         | 0.61%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 126       | 40.13%  |
| Alcor Micro              | 108       | 34.39%  |
| O2 Micro                 | 31        | 9.87%   |
| Lenovo                   | 16        | 5.1%    |
| Upek                     | 13        | 4.14%   |
| Advanced Card Systems    | 6         | 1.91%   |
| Gemalto (was Gemplus)    | 4         | 1.27%   |
| Bit4id                   | 4         | 1.27%   |
| Realtek Semiconductor    | 2         | 0.64%   |
| SCM Microsystems         | 1         | 0.32%   |
| Reiner SCT Kartensysteme | 1         | 0.32%   |
| OmniKey                  | 1         | 0.32%   |
| In Focus Systems         | 1         | 0.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 105       | 33.44%  |
| Broadcom BCM5880 Secure Applications Processor                               | 37        | 11.78%  |
| Broadcom 58200                                                               | 37        | 11.78%  |
| Broadcom 5880                                                                | 30        | 9.55%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 27        | 8.6%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 6.37%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 5.1%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 13        | 4.14%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.27%   |
| Bit4id miniLector EVO                                                        | 4         | 1.27%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.96%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 0.96%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 0.96%   |
| Advanced Card Systems ACR122U                                                | 3         | 0.96%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.64%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.64%   |
| SCM Microsystems uTrust 3700 F CL Reader                                     | 1         | 0.32%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.32%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.32%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.32%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.32%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2971      | 60.78%  |
| 1     | 1520      | 31.1%   |
| 2     | 349       | 7.14%   |
| 3     | 33        | 0.68%   |
| 4     | 12        | 0.25%   |
| 5     | 2         | 0.04%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 806       | 35.17%  |
| Graphics card            | 554       | 24.17%  |
| Chipcard                 | 275       | 12%     |
| Net/wireless             | 207       | 9.03%   |
| Multimedia controller    | 116       | 5.06%   |
| Camera                   | 89        | 3.88%   |
| Bluetooth                | 69        | 3.01%   |
| Storage                  | 34        | 1.48%   |
| Communication controller | 34        | 1.48%   |
| Sound                    | 22        | 0.96%   |
| Modem                    | 20        | 0.87%   |
| Flash memory             | 18        | 0.79%   |
| Net/ethernet             | 16        | 0.7%    |
| Card reader              | 15        | 0.65%   |
| Network                  | 9         | 0.39%   |
| Dvb card                 | 3         | 0.13%   |
| Storage/ide              | 2         | 0.09%   |
| Wireless                 | 1         | 0.04%   |
| Storage/raid             | 1         | 0.04%   |
| Storage/nvme             | 1         | 0.04%   |

