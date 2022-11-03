Linux in Moldova - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Moldova.

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

Total: 160

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| Google   | Droid                       | [c8e4007ce4](https://linux-hardware.org/?probe=c8e4007ce4) | Oct 26, 2022 |
| Lenovo   | IdeaPad 5 Pro 16ACH6 82L... | [71f188e90c](https://linux-hardware.org/?probe=71f188e90c) | Oct 19, 2022 |
| Acer     | Extensa 215-32              | [3e6ce67bb5](https://linux-hardware.org/?probe=3e6ce67bb5) | Oct 08, 2022 |
| Acer     | Extensa 215-32              | [366f0e7930](https://linux-hardware.org/?probe=366f0e7930) | Oct 08, 2022 |
| Acer     | Aspire A315-56              | [644bb082f4](https://linux-hardware.org/?probe=644bb082f4) | Sep 18, 2022 |
| ASUSTek  | VivoBook_ASUSLaptop X509... | [3c214d75b2](https://linux-hardware.org/?probe=3c214d75b2) | Sep 10, 2022 |
| HP       | ProBook 450 G7              | [5fa4bf5fc8](https://linux-hardware.org/?probe=5fa4bf5fc8) | Aug 29, 2022 |
| Lenovo   | Legion 5 Pro 16ITH6H 82J... | [681486095a](https://linux-hardware.org/?probe=681486095a) | Aug 27, 2022 |
| Timi     | TM1701                      | [5b62dea22f](https://linux-hardware.org/?probe=5b62dea22f) | Aug 03, 2022 |
| Timi     | TM1701                      | [cddc7cb825](https://linux-hardware.org/?probe=cddc7cb825) | Aug 03, 2022 |
| Lenovo   | ThinkPad X1 Carbon 5th 2... | [d77ac14ae9](https://linux-hardware.org/?probe=d77ac14ae9) | Aug 01, 2022 |
| HP       | EliteBook 820 G3            | [a96c616d62](https://linux-hardware.org/?probe=a96c616d62) | Jul 28, 2022 |
| Dell     | Latitude 5480               | [151c4b8c85](https://linux-hardware.org/?probe=151c4b8c85) | Jul 21, 2022 |
| HP       | ProBook 450 G7              | [e011908e80](https://linux-hardware.org/?probe=e011908e80) | Jul 18, 2022 |
| HP       | ENVY 15                     | [9c0990eedf](https://linux-hardware.org/?probe=9c0990eedf) | Jul 18, 2022 |
| HP       | ProBook 450 G7              | [5d41d810e8](https://linux-hardware.org/?probe=5d41d810e8) | Jul 18, 2022 |
| ASUSTek  | TUF Gaming FX705DT_FX705... | [1d5a0f6177](https://linux-hardware.org/?probe=1d5a0f6177) | Jul 12, 2022 |
| Lenovo   | IdeaPad Gaming 3 15ARH05... | [567077c28d](https://linux-hardware.org/?probe=567077c28d) | Jul 08, 2022 |
| Lenovo   | IdeaPad L340-15API 81LW     | [dda5fb9c20](https://linux-hardware.org/?probe=dda5fb9c20) | Jun 21, 2022 |
| ASUSTek  | X555LD                      | [d5d6eeb639](https://linux-hardware.org/?probe=d5d6eeb639) | Jun 11, 2022 |
| Lenovo   | Legion 5 15IMH05 82AU       | [cd7bc92bcd](https://linux-hardware.org/?probe=cd7bc92bcd) | Jun 06, 2022 |
| Lenovo   | IdeaPad 100-15IBY 80MJ      | [db944454c8](https://linux-hardware.org/?probe=db944454c8) | May 23, 2022 |
| Lenovo   | Legion Y530-15ICH 81FV      | [428509b262](https://linux-hardware.org/?probe=428509b262) | May 01, 2022 |
| ASUSTek  | X541NC                      | [d1dc342eb9](https://linux-hardware.org/?probe=d1dc342eb9) | Apr 17, 2022 |
| Lenovo   | ThinkPad X240 20AL0067RT    | [f246d643b4](https://linux-hardware.org/?probe=f246d643b4) | Feb 26, 2022 |
| Sony     | VPCEB1J8E                   | [b00a6a15b2](https://linux-hardware.org/?probe=b00a6a15b2) | Feb 20, 2022 |
| ASUSTek  | U32U                        | [f7b7d4d2db](https://linux-hardware.org/?probe=f7b7d4d2db) | Feb 20, 2022 |
| ASUSTek  | U32U                        | [1cb943e596](https://linux-hardware.org/?probe=1cb943e596) | Feb 20, 2022 |
| Acer     | Swift SF314-57              | [de92ca9fec](https://linux-hardware.org/?probe=de92ca9fec) | Feb 05, 2022 |
| Lenovo   | ThinkPad E15 Gen 2 20TD0... | [4c95ae549f](https://linux-hardware.org/?probe=4c95ae549f) | Jan 21, 2022 |
| HP       | Unknown                     | [1fbb31af8d](https://linux-hardware.org/?probe=1fbb31af8d) | Jan 05, 2022 |
| Jumper   | EZbook                      | [6e9ee100f8](https://linux-hardware.org/?probe=6e9ee100f8) | Dec 22, 2021 |
| HP       | Pavilion Laptop 15-eh1xx... | [ab93ce9eb8](https://linux-hardware.org/?probe=ab93ce9eb8) | Dec 21, 2021 |
| Jumper   | EZbook                      | [992b2479e4](https://linux-hardware.org/?probe=992b2479e4) | Dec 21, 2021 |
| HP       | EliteBook 8470p             | [8ab831bf5f](https://linux-hardware.org/?probe=8ab831bf5f) | Dec 21, 2021 |
| Chuwi    | GemiBook Pro                | [493d55cb16](https://linux-hardware.org/?probe=493d55cb16) | Dec 11, 2021 |
| Dell     | Latitude 3520               | [8fb7494494](https://linux-hardware.org/?probe=8fb7494494) | Dec 06, 2021 |
| Acer     | Aspire 5253G                | [f7c885dedd](https://linux-hardware.org/?probe=f7c885dedd) | Nov 08, 2021 |
| Toshiba  | Satellite Pro S300L         | [93c5def444](https://linux-hardware.org/?probe=93c5def444) | Oct 06, 2021 |
| ASUSTek  | VivoBook S15 X510UF         | [336bbdae35](https://linux-hardware.org/?probe=336bbdae35) | Oct 02, 2021 |
| Lenovo   | ThinkPad E15 Gen 2 20TD0... | [7820254b55](https://linux-hardware.org/?probe=7820254b55) | Sep 23, 2021 |
| Dell     | Latitude 5591               | [0235ac49c6](https://linux-hardware.org/?probe=0235ac49c6) | Sep 15, 2021 |
| Lenovo   | ThinkPad E15 Gen 3 20YG0... | [02666996c0](https://linux-hardware.org/?probe=02666996c0) | Sep 12, 2021 |
| Lenovo   | ThinkPad E15 Gen 3 20YG0... | [97b45da8a7](https://linux-hardware.org/?probe=97b45da8a7) | Sep 12, 2021 |
| HP       | Laptop 15-da1xxx            | [c6f3848c20](https://linux-hardware.org/?probe=c6f3848c20) | Sep 12, 2021 |
| HP       | Laptop 15-da1xxx            | [b73b5ecab7](https://linux-hardware.org/?probe=b73b5ecab7) | Sep 11, 2021 |
| HP       | ProBook 450 G6              | [227d87ab66](https://linux-hardware.org/?probe=227d87ab66) | Aug 20, 2021 |
| Toshiba  | TECRA Z40-B                 | [d353412a4f](https://linux-hardware.org/?probe=d353412a4f) | Jul 29, 2021 |
| Lenovo   | IdeaPad 5 15ARE05 81YQ      | [8430084f74](https://linux-hardware.org/?probe=8430084f74) | Jul 15, 2021 |
| System76 | Adder WS                    | [d128c1d16b](https://linux-hardware.org/?probe=d128c1d16b) | Jul 08, 2021 |
| Lenovo   | ThinkPad T440 20B7S1N809    | [b9ab49e917](https://linux-hardware.org/?probe=b9ab49e917) | Jul 07, 2021 |
| Dell     | Vostro 5590                 | [1cc0df9bfd](https://linux-hardware.org/?probe=1cc0df9bfd) | Jun 28, 2021 |
| Dell     | Vostro 5590                 | [0caade1304](https://linux-hardware.org/?probe=0caade1304) | Jun 28, 2021 |
| ASUSTek  | X555LJ                      | [aab7280bd9](https://linux-hardware.org/?probe=aab7280bd9) | Jun 20, 2021 |
| Timi     | A35S                        | [226823eb5b](https://linux-hardware.org/?probe=226823eb5b) | Jun 19, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X521... | [79e70ff708](https://linux-hardware.org/?probe=79e70ff708) | Jun 17, 2021 |
| ASUSTek  | TUF Gaming FX705DT_FX705... | [447e508593](https://linux-hardware.org/?probe=447e508593) | Jun 14, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X521... | [47d894d771](https://linux-hardware.org/?probe=47d894d771) | Jun 12, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X521... | [5c14296bc9](https://linux-hardware.org/?probe=5c14296bc9) | Jun 12, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X521... | [73e1185f6e](https://linux-hardware.org/?probe=73e1185f6e) | Jun 12, 2021 |
| ASUSTek  | TUF Gaming FX705DT_FX705... | [666ddeb09c](https://linux-hardware.org/?probe=666ddeb09c) | May 19, 2021 |
| Dell     | Inspiron 3541               | [88d0f731fd](https://linux-hardware.org/?probe=88d0f731fd) | Apr 29, 2021 |
| Dell     | Inspiron 3541               | [4267385ad8](https://linux-hardware.org/?probe=4267385ad8) | Apr 29, 2021 |
| Dell     | Inspiron 3593               | [5facbef10b](https://linux-hardware.org/?probe=5facbef10b) | Apr 24, 2021 |
| Dell     | Latitude E7440              | [c59d5358b3](https://linux-hardware.org/?probe=c59d5358b3) | Apr 04, 2021 |
| HP       | Pavilion dv7                | [b7756075fd](https://linux-hardware.org/?probe=b7756075fd) | Mar 15, 2021 |
| Lenovo   | Legion Y530-15ICH 81FV      | [bd5d97f7e7](https://linux-hardware.org/?probe=bd5d97f7e7) | Mar 07, 2021 |
| HP       | ZBook Fury 15 G7 Mobile ... | [c2435842e1](https://linux-hardware.org/?probe=c2435842e1) | Mar 04, 2021 |
| HP       | ZBook Fury 15 G7 Mobile ... | [5cc3d3f3ed](https://linux-hardware.org/?probe=5cc3d3f3ed) | Mar 04, 2021 |
| Lenovo   | IdeaPad 330-15IKB 81DE      | [16d0cd0b17](https://linux-hardware.org/?probe=16d0cd0b17) | Mar 04, 2021 |
| Lenovo   | IdeaPad 330-15IKB 81DE      | [7a3239606c](https://linux-hardware.org/?probe=7a3239606c) | Mar 04, 2021 |
| Lenovo   | Legion Y530-15ICH 81FV      | [88bab7f6e7](https://linux-hardware.org/?probe=88bab7f6e7) | Feb 22, 2021 |
| ASUSTek  | ZenBook UX333FA_UX333FA     | [454ea43e4a](https://linux-hardware.org/?probe=454ea43e4a) | Feb 11, 2021 |
| HP       | ProBook 650 G2              | [043b7f867b](https://linux-hardware.org/?probe=043b7f867b) | Jan 23, 2021 |
| HP       | Laptop 15-dw0xxx            | [a69f5fa59f](https://linux-hardware.org/?probe=a69f5fa59f) | Jan 17, 2021 |
| Gateway  | NV55S                       | [8ed7215a68](https://linux-hardware.org/?probe=8ed7215a68) | Jan 17, 2021 |
| ASUSTek  | ZenBook UX333FA_UX333FA     | [a2da0e78db](https://linux-hardware.org/?probe=a2da0e78db) | Jan 14, 2021 |
| ASUSTek  | ZenBook UX333FA_UX333FA     | [84f50057c5](https://linux-hardware.org/?probe=84f50057c5) | Jan 14, 2021 |
| ASUSTek  | ZenBook UX333FA_UX333FA     | [c3b5acb8ff](https://linux-hardware.org/?probe=c3b5acb8ff) | Jan 14, 2021 |
| Gateway  | NV55S                       | [149e658abf](https://linux-hardware.org/?probe=149e658abf) | Jan 10, 2021 |
| HP       | EliteBook 855 G7 Noteboo... | [9f70a6e397](https://linux-hardware.org/?probe=9f70a6e397) | Jan 06, 2021 |
| HP       | Pavilion 17                 | [ac1360247b](https://linux-hardware.org/?probe=ac1360247b) | Dec 22, 2020 |
| HP       | EliteBook 855 G7 Noteboo... | [049fa926a1](https://linux-hardware.org/?probe=049fa926a1) | Dec 21, 2020 |
| HP       | EliteBook 855 G7 Noteboo... | [69e21f1387](https://linux-hardware.org/?probe=69e21f1387) | Nov 09, 2020 |
| Lenovo   | ThinkPad Yoga 11e 3rd Ge... | [bc1158d1d3](https://linux-hardware.org/?probe=bc1158d1d3) | Nov 09, 2020 |
| HP       | EliteBook 855 G7 Noteboo... | [8725886c61](https://linux-hardware.org/?probe=8725886c61) | Nov 06, 2020 |
| Dell     | Inspiron N5110              | [ee5fa15c46](https://linux-hardware.org/?probe=ee5fa15c46) | Nov 06, 2020 |
| ASUSTek  | Strix 17 GL703GE            | [6e4daa0a3c](https://linux-hardware.org/?probe=6e4daa0a3c) | Nov 05, 2020 |
| ASUSTek  | Strix 17 GL703GE            | [3a9f43c320](https://linux-hardware.org/?probe=3a9f43c320) | Nov 04, 2020 |
| HUAWEI   | NBLK-WAX9X                  | [4088a13026](https://linux-hardware.org/?probe=4088a13026) | Oct 09, 2020 |
| ASUSTek  | X200MA                      | [794220eee6](https://linux-hardware.org/?probe=794220eee6) | Sep 26, 2020 |
| Lenovo   | G710 20252                  | [c166b56839](https://linux-hardware.org/?probe=c166b56839) | Aug 26, 2020 |
| ASUSTek  | X541NA                      | [3f4978f463](https://linux-hardware.org/?probe=3f4978f463) | Aug 03, 2020 |
| HP       | ProBook 6465b               | [378cd77f66](https://linux-hardware.org/?probe=378cd77f66) | Jul 26, 2020 |
| ASUSTek  | VivoBook S15 X510UF         | [66a180cdab](https://linux-hardware.org/?probe=66a180cdab) | Jul 24, 2020 |
| ASUSTek  | VivoBook S15 X510UF         | [ed25557a01](https://linux-hardware.org/?probe=ed25557a01) | Jul 20, 2020 |
| HP       | Compaq Presario CQ60        | [8d24316f6b](https://linux-hardware.org/?probe=8d24316f6b) | Jul 15, 2020 |
| HP       | ProBook 450 G7              | [3638848f89](https://linux-hardware.org/?probe=3638848f89) | Jun 24, 2020 |
| Dell     | XPS 15 9570                 | [c14028664d](https://linux-hardware.org/?probe=c14028664d) | Jun 23, 2020 |
| ASUSTek  | X541NA                      | [6d3495ee91](https://linux-hardware.org/?probe=6d3495ee91) | Jun 14, 2020 |
| HP       | ProBook 470 G2              | [bce3965ebb](https://linux-hardware.org/?probe=bce3965ebb) | Jun 13, 2020 |
| Lenovo   | IdeaPad 130-15IKB 81H7      | [54b25b6a82](https://linux-hardware.org/?probe=54b25b6a82) | Apr 18, 2020 |
| HP       | EliteBook 850 G6            | [92d96a7e87](https://linux-hardware.org/?probe=92d96a7e87) | Apr 11, 2020 |
| Samsung  | RV413/RV513                 | [996451817e](https://linux-hardware.org/?probe=996451817e) | Mar 12, 2020 |
| Lenovo   | IdeaPad 330-15IGM 81D1      | [c0c091dee5](https://linux-hardware.org/?probe=c0c091dee5) | Feb 22, 2020 |
| Lenovo   | IdeaPad 330-15IGM 81D1      | [f1e8d4fb95](https://linux-hardware.org/?probe=f1e8d4fb95) | Feb 22, 2020 |
| ASUSTek  | X541NA                      | [3df0912982](https://linux-hardware.org/?probe=3df0912982) | Feb 15, 2020 |
| Lenovo   | G710 20252                  | [7df7fd3c10](https://linux-hardware.org/?probe=7df7fd3c10) | Feb 15, 2020 |
| Toshiba  | Satellite C55D-A            | [19713fa1aa](https://linux-hardware.org/?probe=19713fa1aa) | Feb 05, 2020 |
| Dell     | Inspiron 3582               | [6916c1087b](https://linux-hardware.org/?probe=6916c1087b) | Jan 21, 2020 |
| Dell     | Inspiron 3582               | [b873ab0117](https://linux-hardware.org/?probe=b873ab0117) | Jan 16, 2020 |
| Dell     | Inspiron 3582               | [cf3745ead4](https://linux-hardware.org/?probe=cf3745ead4) | Jan 16, 2020 |
| ASUSTek  | K54C                        | [42b284e62d](https://linux-hardware.org/?probe=42b284e62d) | Dec 17, 2019 |
| ASUSTek  | X542UR                      | [8c29a78852](https://linux-hardware.org/?probe=8c29a78852) | Dec 15, 2019 |
| ASUSTek  | X542UR                      | [106dcde5e2](https://linux-hardware.org/?probe=106dcde5e2) | Oct 24, 2019 |
| ASUSTek  | X542UR                      | [d5d9fe7ed0](https://linux-hardware.org/?probe=d5d9fe7ed0) | Oct 15, 2019 |
| ASUSTek  | X542UR                      | [f0e44b13bf](https://linux-hardware.org/?probe=f0e44b13bf) | Sep 15, 2019 |
| ASUSTek  | X541SA                      | [f4ec1608f1](https://linux-hardware.org/?probe=f4ec1608f1) | Aug 19, 2019 |
| Samsung  | RV413/RV513                 | [a569d1638b](https://linux-hardware.org/?probe=a569d1638b) | Aug 16, 2019 |
| HP       | Compaq 6910p                | [2b9b5142af](https://linux-hardware.org/?probe=2b9b5142af) | Jul 02, 2019 |
| Dell     | Inspiron 3521               | [5129fbc2b3](https://linux-hardware.org/?probe=5129fbc2b3) | Jun 13, 2019 |
| Dell     | Inspiron 3521               | [de72a9023b](https://linux-hardware.org/?probe=de72a9023b) | Jun 12, 2019 |
| Timi     | TM1701                      | [b2b217c7ba](https://linux-hardware.org/?probe=b2b217c7ba) | Jun 04, 2019 |
| Lenovo   | IdeaPad 330S-14IKB 81F4     | [1df14b9671](https://linux-hardware.org/?probe=1df14b9671) | May 31, 2019 |
| Acer     | Aspire E1-572G              | [d7c9cc59b9](https://linux-hardware.org/?probe=d7c9cc59b9) | May 17, 2019 |
| ASUSTek  | X550JX                      | [a268d267b1](https://linux-hardware.org/?probe=a268d267b1) | May 14, 2019 |
| Toshiba  | Satellite A210              | [b08d78a7fe](https://linux-hardware.org/?probe=b08d78a7fe) | May 12, 2019 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [adff6b4ec1](https://linux-hardware.org/?probe=adff6b4ec1) | May 08, 2019 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [1427bdb593](https://linux-hardware.org/?probe=1427bdb593) | May 08, 2019 |
| HP       | Compaq Presario CQ60        | [c4ee62ecc8](https://linux-hardware.org/?probe=c4ee62ecc8) | Mar 21, 2019 |
| Acer     | Aspire A515-51G             | [bc2c6a0308](https://linux-hardware.org/?probe=bc2c6a0308) | Jan 21, 2019 |
| Acer     | Aspire A515-51G             | [a4fa6be429](https://linux-hardware.org/?probe=a4fa6be429) | Jan 21, 2019 |
| Samsung  | 300E4C/300E5C/300E7C        | [761e996b51](https://linux-hardware.org/?probe=761e996b51) | Jan 13, 2019 |
| HP       | 635                         | [26ac239a00](https://linux-hardware.org/?probe=26ac239a00) | Jan 13, 2019 |
| HP       | 635                         | [88b6088e86](https://linux-hardware.org/?probe=88b6088e86) | Jan 13, 2019 |
| Dell     | Latitude E5420              | [58a37ca1d7](https://linux-hardware.org/?probe=58a37ca1d7) | Jan 08, 2019 |
| HP       | Compaq CQ58                 | [f930811937](https://linux-hardware.org/?probe=f930811937) | Dec 25, 2018 |
| HP       | Compaq CQ58                 | [092addb321](https://linux-hardware.org/?probe=092addb321) | Dec 25, 2018 |
| Samsung  | R517/R717                   | [cf1386553c](https://linux-hardware.org/?probe=cf1386553c) | Dec 11, 2018 |
| HP       | ENVY m6                     | [a2443c2500](https://linux-hardware.org/?probe=a2443c2500) | Nov 28, 2018 |
| Lenovo   | ThinkPad X131e 33711T0      | [d765880811](https://linux-hardware.org/?probe=d765880811) | Nov 20, 2018 |
| ASUSTek  | K56CM                       | [9801230a74](https://linux-hardware.org/?probe=9801230a74) | Oct 11, 2018 |
| Lenovo   | G710 20252                  | [67b5fc31a6](https://linux-hardware.org/?probe=67b5fc31a6) | Sep 03, 2018 |
| ASUSTek  | K50AB                       | [5309fc98bb](https://linux-hardware.org/?probe=5309fc98bb) | Jun 21, 2018 |
| Lenovo   | Y520-15IKBN 80WK            | [9c2fa220c0](https://linux-hardware.org/?probe=9c2fa220c0) | Jun 07, 2018 |
| Lenovo   | Y520-15IKBN 80WK            | [23cd9fcd79](https://linux-hardware.org/?probe=23cd9fcd79) | Jun 07, 2018 |
| ASUSTek  | K52N                        | [9b6027f7f9](https://linux-hardware.org/?probe=9b6027f7f9) | Mar 04, 2018 |
| ASUSTek  | K52N                        | [a31f696968](https://linux-hardware.org/?probe=a31f696968) | Jan 27, 2018 |
| ASUSTek  | E502SA                      | [f82780c45f](https://linux-hardware.org/?probe=f82780c45f) | Dec 22, 2017 |
| Samsung  | R517/R717                   | [88501ec4d2](https://linux-hardware.org/?probe=88501ec4d2) | Nov 23, 2017 |
| Acer     | Aspire E5-575               | [d7a774808d](https://linux-hardware.org/?probe=d7a774808d) | Nov 07, 2017 |
| Lenovo   | V580 20147                  | [7b4ec145fd](https://linux-hardware.org/?probe=7b4ec145fd) | Sep 05, 2017 |
| ASUSTek  | E502SA                      | [f80e3a3361](https://linux-hardware.org/?probe=f80e3a3361) | Jul 02, 2017 |
| Acer     | AO756                       | [750d61ea27](https://linux-hardware.org/?probe=750d61ea27) | Jun 28, 2017 |
| ASUSTek  | E502SA                      | [e638970390](https://linux-hardware.org/?probe=e638970390) | Jun 27, 2017 |
| Samsung  | R517/R717                   | [a037b05f1c](https://linux-hardware.org/?probe=a037b05f1c) | Jun 07, 2017 |
| Lenovo   | V580 20147                  | [e4a66b20cf](https://linux-hardware.org/?probe=e4a66b20cf) | May 09, 2017 |
| HP       | 550                         | [21d69ed69f](https://linux-hardware.org/?probe=21d69ed69f) | Feb 14, 2017 |
| Acer     | Aspire E1-531G              | [0481735487](https://linux-hardware.org/?probe=0481735487) | Dec 19, 2016 |
| MSI      | CR610                       | [fa269a3f05](https://linux-hardware.org/?probe=fa269a3f05) | Nov 20, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 18.04      | 12        | 10.08%  |
| Ubuntu 20.04      | 11        | 9.24%   |
| ROSA R10          | 9         | 7.56%   |
| ROSA R11          | 6         | 5.04%   |
| Linux Mint 20.1   | 5         | 4.2%    |
| Ubuntu 22.04      | 4         | 3.36%   |
| KDE neon 20.04    | 4         | 3.36%   |
| Arch              | 4         | 3.36%   |
| ROSA R9           | 3         | 2.52%   |
| ROSA R8           | 3         | 2.52%   |
| ROSA R11.1        | 3         | 2.52%   |
| Linux Mint 19.1   | 3         | 2.52%   |
| Fedora 36         | 3         | 2.52%   |
| Fedora 34         | 3         | 2.52%   |
| Zorin 16          | 2         | 1.68%   |
| Ubuntu 19.10      | 2         | 1.68%   |
| ROSA R8.1         | 2         | 1.68%   |
| ROSA 12.2         | 2         | 1.68%   |
| Pop!_OS 21.04     | 2         | 1.68%   |
| OpenMandriva 4.3  | 2         | 1.68%   |
| Manjaro           | 2         | 1.68%   |
| Linux Mint 20.2   | 2         | 1.68%   |
| BlackPanther 18.1 | 2         | 1.68%   |
| Ubuntu 21.04      | 1         | 0.84%   |
| Ubuntu 16.04      | 1         | 0.84%   |
| SteamOS 3.3       | 1         | 0.84%   |
| ROSA 12.1         | 1         | 0.84%   |
| Pop!_OS 20.10     | 1         | 0.84%   |
| OpenMandriva 4.50 | 1         | 0.84%   |
| Manjaro 22.0.0    | 1         | 0.84%   |
| Manjaro 20.2.1    | 1         | 0.84%   |
| Manjaro 20.2      | 1         | 0.84%   |
| Manjaro 19.0.2    | 1         | 0.84%   |
| Manjaro 18.0.4    | 1         | 0.84%   |
| Linux Mint 20.3   | 1         | 0.84%   |
| Linux Mint 20     | 1         | 0.84%   |
| Linux Mint 19.3   | 1         | 0.84%   |
| Kubuntu 20.10     | 1         | 0.84%   |
| Kubuntu 20.04     | 1         | 0.84%   |
| Kali 2021.3       | 1         | 0.84%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 31        | 27.19%  |
| ROSA         | 26        | 22.81%  |
| Linux Mint   | 13        | 11.4%   |
| Fedora       | 9         | 7.89%   |
| Manjaro      | 7         | 6.14%   |
| KDE neon     | 4         | 3.51%   |
| Arch         | 4         | 3.51%   |
| Pop!_OS      | 3         | 2.63%   |
| OpenMandriva | 3         | 2.63%   |
| Endless      | 3         | 2.63%   |
| Zorin        | 2         | 1.75%   |
| Kubuntu      | 2         | 1.75%   |
| Debian       | 2         | 1.75%   |
| BlackPanther | 2         | 1.75%   |
| SteamOS      | 1         | 0.88%   |
| Kali         | 1         | 0.88%   |
| BuildRoot    | 1         | 0.88%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.15.0-41-generic                  | 4         | 3.15%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 4         | 3.15%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 4         | 3.15%   |
| 5.8.0-33-generic                   | 3         | 2.36%   |
| 4.9.60-nrj-desktop-1rosa-i586      | 3         | 2.36%   |
| 5.4.0-37-generic                   | 2         | 1.57%   |
| 5.16.7-desktop-1omv4003            | 2         | 1.57%   |
| 5.11.0-7614-generic                | 2         | 1.57%   |
| 5.11.0-41-generic                  | 2         | 1.57%   |
| 5.11.0-34-generic                  | 2         | 1.57%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 2         | 1.57%   |
| 5.10.2-2-MANJARO                   | 2         | 1.57%   |
| 4.9.95-nrj-desktop-2rosa-x86_64    | 2         | 1.57%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 2         | 1.57%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 2         | 1.57%   |
| 4.15.0-desktop-68.5rosa-x86_64     | 2         | 1.57%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 2         | 1.57%   |
| 5.9.3-1-MANJARO                    | 1         | 0.79%   |
| 5.8.18-100.fc31.x86_64             | 1         | 0.79%   |
| 5.8.18-1-MANJARO                   | 1         | 0.79%   |
| 5.8.0-36-generic                   | 1         | 0.79%   |
| 5.8.0-25-lowlatency                | 1         | 0.79%   |
| 5.6.14-desktop-2bP                 | 1         | 0.79%   |
| 5.4.49-nrj-desktop-1rosa-x86_64    | 1         | 0.79%   |
| 5.4.32-generic-2rosa-x86_64        | 1         | 0.79%   |
| 5.4.0-86-generic                   | 1         | 0.79%   |
| 5.4.0-84-generic                   | 1         | 0.79%   |
| 5.4.0-72-generic                   | 1         | 0.79%   |
| 5.4.0-70-generic                   | 1         | 0.79%   |
| 5.4.0-67-generic                   | 1         | 0.79%   |
| 5.4.0-58-generic                   | 1         | 0.79%   |
| 5.4.0-52-generic                   | 1         | 0.79%   |
| 5.4.0-48-generic                   | 1         | 0.79%   |
| 5.4.0-42-generic                   | 1         | 0.79%   |
| 5.4.0-40-generic                   | 1         | 0.79%   |
| 5.3.0-59-generic                   | 1         | 0.79%   |
| 5.3.0-42-generic                   | 1         | 0.79%   |
| 5.3.0-40-generic                   | 1         | 0.79%   |
| 5.3.0-23-generic                   | 1         | 0.79%   |
| 5.19.7-arch1-1                     | 1         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.15.0  | 15        | 12.2%   |
| 5.4.0   | 12        | 9.76%   |
| 5.11.0  | 11        | 8.94%   |
| 5.15.0  | 7         | 5.69%   |
| 4.9.60  | 6         | 4.88%   |
| 5.8.0   | 5         | 4.07%   |
| 5.3.0   | 4         | 3.25%   |
| 4.9.20  | 4         | 3.25%   |
| 5.0.0   | 3         | 2.44%   |
| 4.18.0  | 3         | 2.44%   |
| 5.8.18  | 2         | 1.63%   |
| 5.18.1  | 2         | 1.63%   |
| 5.16.7  | 2         | 1.63%   |
| 5.13.0  | 2         | 1.63%   |
| 5.10.74 | 2         | 1.63%   |
| 5.10.2  | 2         | 1.63%   |
| 5.10.0  | 2         | 1.63%   |
| 4.9.95  | 2         | 1.63%   |
| 4.9.41  | 2         | 1.63%   |
| 4.9.155 | 2         | 1.63%   |
| 5.9.3   | 1         | 0.81%   |
| 5.6.14  | 1         | 0.81%   |
| 5.4.49  | 1         | 0.81%   |
| 5.4.32  | 1         | 0.81%   |
| 5.19.7  | 1         | 0.81%   |
| 5.19.4  | 1         | 0.81%   |
| 5.18.5  | 1         | 0.81%   |
| 5.18.15 | 1         | 0.81%   |
| 5.18.13 | 1         | 0.81%   |
| 5.17.3  | 1         | 0.81%   |
| 5.17.11 | 1         | 0.81%   |
| 5.16.0  | 1         | 0.81%   |
| 5.15.71 | 1         | 0.81%   |
| 5.15.49 | 1         | 0.81%   |
| 5.15.2  | 1         | 0.81%   |
| 5.14.7  | 1         | 0.81%   |
| 5.13.10 | 1         | 0.81%   |
| 5.12.9  | 1         | 0.81%   |
| 5.12.12 | 1         | 0.81%   |
| 5.11.12 | 1         | 0.81%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 15        | 12.61%  |
| 4.15    | 15        | 12.61%  |
| 5.4     | 14        | 11.76%  |
| 5.11    | 12        | 10.08%  |
| 5.15    | 10        | 8.4%    |
| 5.10    | 8         | 6.72%   |
| 5.8     | 7         | 5.88%   |
| 5.18    | 5         | 4.2%    |
| 5.3     | 4         | 3.36%   |
| 5.0     | 4         | 3.36%   |
| 5.16    | 3         | 2.52%   |
| 5.13    | 3         | 2.52%   |
| 4.18    | 3         | 2.52%   |
| 4.1     | 3         | 2.52%   |
| 5.19    | 2         | 1.68%   |
| 5.17    | 2         | 1.68%   |
| 5.12    | 2         | 1.68%   |
| 5.9     | 1         | 0.84%   |
| 5.6     | 1         | 0.84%   |
| 5.14    | 1         | 0.84%   |
| 5.1     | 1         | 0.84%   |
| 4.19    | 1         | 0.84%   |
| 4.16    | 1         | 0.84%   |
| 4.10    | 1         | 0.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 109       | 94.78%  |
| i686   | 6         | 5.22%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 35        | 30.17%  |
| KDE5            | 27        | 23.28%  |
| KDE4            | 19        | 16.38%  |
| Unknown         | 14        | 12.07%  |
| X-Cinnamon      | 9         | 7.76%   |
| XFCE            | 4         | 3.45%   |
| MATE            | 2         | 1.72%   |
| Cinnamon        | 2         | 1.72%   |
| sway            | 1         | 0.86%   |
| LXQt            | 1         | 0.86%   |
| KDE             | 1         | 0.86%   |
| GNOME Flashback | 1         | 0.86%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 87        | 75.65%  |
| Wayland | 18        | 15.65%  |
| Unknown | 10        | 8.7%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 44        | 37.61%  |
| SDDM    | 20        | 17.09%  |
| KDM     | 19        | 16.24%  |
| GDM     | 18        | 15.38%  |
| TDM     | 6         | 5.13%   |
| LightDM | 5         | 4.27%   |
| GDM3    | 5         | 4.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 39        | 34.21%  |
| en_US   | 38        | 33.33%  |
| ru_RU   | 21        | 18.42%  |
| ro_RO   | 7         | 6.14%   |
| C       | 3         | 2.63%   |
| en_GB   | 2         | 1.75%   |
| ru_UA   | 1         | 0.88%   |
| nl_NL   | 1         | 0.88%   |
| en_150  | 1         | 0.88%   |
| de_DE   | 1         | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 61        | 53.51%  |
| BIOS | 53        | 46.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 82        | 71.93%  |
| Unknown | 16        | 14.04%  |
| Btrfs   | 8         | 7.02%   |
| Overlay | 6         | 5.26%   |
| Xfs     | 2         | 1.75%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 51        | 44.35%  |
| GPT     | 41        | 35.65%  |
| MBR     | 23        | 20%     |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 106       | 92.98%  |
| Yes       | 8         | 7.02%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 85        | 74.56%  |
| Yes       | 29        | 25.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 25        | 22.12%  |
| Lenovo              | 24        | 21.24%  |
| ASUSTek Computer    | 24        | 21.24%  |
| Dell                | 12        | 10.62%  |
| Acer                | 9         | 7.96%   |
| Toshiba             | 4         | 3.54%   |
| Samsung Electronics | 4         | 3.54%   |
| Timi                | 3         | 2.65%   |
| System76            | 1         | 0.88%   |
| Sony                | 1         | 0.88%   |
| MSI                 | 1         | 0.88%   |
| Jumper              | 1         | 0.88%   |
| HUAWEI              | 1         | 0.88%   |
| Google              | 1         | 0.88%   |
| Gateway             | 1         | 0.88%   |
| Chuwi               | 1         | 0.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop X521IA_D533IA      | 3         | 2.65%   |
| Timi TM1701                                 | 2         | 1.77%   |
| Samsung RV413/RV513                         | 2         | 1.77%   |
| Lenovo Legion Y530-15ICH 81FV               | 2         | 1.77%   |
| HP ProBook 450 G7                           | 2         | 1.77%   |
| HP Compaq Presario CQ60                     | 2         | 1.77%   |
| ASUS VivoBook S15 X510UF                    | 2         | 1.77%   |
| Toshiba TECRA Z40-B                         | 1         | 0.88%   |
| Toshiba Satellite Pro S300L                 | 1         | 0.88%   |
| Toshiba Satellite C55D-A                    | 1         | 0.88%   |
| Toshiba Satellite A210                      | 1         | 0.88%   |
| Timi A35S                                   | 1         | 0.88%   |
| System76 Adder WS                           | 1         | 0.88%   |
| Sony VPCEB1J8E                              | 1         | 0.88%   |
| Samsung R517/R717                           | 1         | 0.88%   |
| Samsung 300E4C/300E5C/300E7C                | 1         | 0.88%   |
| MSI CR610                                   | 1         | 0.88%   |
| Lenovo Y520-15IKBN 80WK                     | 1         | 0.88%   |
| Lenovo V580 20147                           | 1         | 0.88%   |
| Lenovo ThinkPad Yoga 11e 3rd Gen 20G8S0MG00 | 1         | 0.88%   |
| Lenovo ThinkPad X240 20AL0067RT             | 1         | 0.88%   |
| Lenovo ThinkPad X131e 33711T0               | 1         | 0.88%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR002MMX    | 1         | 0.88%   |
| Lenovo ThinkPad T440 20B7S1N809             | 1         | 0.88%   |
| Lenovo ThinkPad E15 Gen 3 20YG004BRT        | 1         | 0.88%   |
| Lenovo ThinkPad E15 Gen 2 20TD003TRT        | 1         | 0.88%   |
| Lenovo ThinkPad E15 Gen 2 20TD002NRA        | 1         | 0.88%   |
| Lenovo Legion 5 Pro 16ITH6H 82JD            | 1         | 0.88%   |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 0.88%   |
| Lenovo IdeaPad L340-15API 81LW              | 1         | 0.88%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY        | 1         | 0.88%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5            | 1         | 0.88%   |
| Lenovo IdeaPad 5 15ARE05 81YQ               | 1         | 0.88%   |
| Lenovo IdeaPad 330S-14IKB 81F4              | 1         | 0.88%   |
| Lenovo IdeaPad 330-15IKB 81DE               | 1         | 0.88%   |
| Lenovo IdeaPad 330-15IGM 81D1               | 1         | 0.88%   |
| Lenovo IdeaPad 130-15IKB 81H7               | 1         | 0.88%   |
| Lenovo IdeaPad 100-15IBY 80MJ               | 1         | 0.88%   |
| Lenovo G710 20252                           | 1         | 0.88%   |
| Jumper EZbook                               | 1         | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 9         | 7.96%   |
| Lenovo ThinkPad    | 8         | 7.08%   |
| ASUS VivoBook      | 7         | 6.19%   |
| HP ProBook         | 6         | 5.31%   |
| Acer Aspire        | 6         | 5.31%   |
| Dell Latitude      | 5         | 4.42%   |
| Dell Inspiron      | 5         | 4.42%   |
| Lenovo Legion      | 4         | 3.54%   |
| HP EliteBook       | 4         | 3.54%   |
| HP Compaq          | 4         | 3.54%   |
| Toshiba Satellite  | 3         | 2.65%   |
| HP Pavilion        | 3         | 2.65%   |
| Timi TM1701        | 2         | 1.77%   |
| Samsung RV413      | 2         | 1.77%   |
| HP Laptop          | 2         | 1.77%   |
| HP ENVY            | 2         | 1.77%   |
| Toshiba TECRA      | 1         | 0.88%   |
| Timi A35S          | 1         | 0.88%   |
| System76 Adder     | 1         | 0.88%   |
| Sony VPCEB1J8E     | 1         | 0.88%   |
| Samsung R517       | 1         | 0.88%   |
| Samsung 300E4C     | 1         | 0.88%   |
| MSI CR610          | 1         | 0.88%   |
| Lenovo Y520-15IKBN | 1         | 0.88%   |
| Lenovo V580        | 1         | 0.88%   |
| Lenovo G710        | 1         | 0.88%   |
| Jumper EZbook      | 1         | 0.88%   |
| HUAWEI NBLK-WAX9X  | 1         | 0.88%   |
| HP ZBook           | 1         | 0.88%   |
| HP 635             | 1         | 0.88%   |
| HP 550             | 1         | 0.88%   |
| Google Droid       | 1         | 0.88%   |
| Gateway NV55S      | 1         | 0.88%   |
| Dell XPS           | 1         | 0.88%   |
| Dell Vostro        | 1         | 0.88%   |
| Chuwi GemiBook     | 1         | 0.88%   |
| ASUS ZenBook       | 1         | 0.88%   |
| ASUS X555LJ        | 1         | 0.88%   |
| ASUS X555LD        | 1         | 0.88%   |
| ASUS X550JX        | 1         | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 15        | 13.27%  |
| 2021 | 12        | 10.62%  |
| 2018 | 12        | 10.62%  |
| 2017 | 11        | 9.73%   |
| 2011 | 11        | 9.73%   |
| 2012 | 9         | 7.96%   |
| 2020 | 7         | 6.19%   |
| 2013 | 7         | 6.19%   |
| 2016 | 6         | 5.31%   |
| 2015 | 5         | 4.42%   |
| 2014 | 4         | 3.54%   |
| 2009 | 4         | 3.54%   |
| 2008 | 4         | 3.54%   |
| 2010 | 3         | 2.65%   |
| 2007 | 2         | 1.77%   |
| 2022 | 1         | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 113       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 105       | 92.92%  |
| Enabled  | 8         | 7.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 112       | 99.12%  |
| Yes  | 1         | 0.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 32        | 28.32%  |
| 3.01-4.0    | 31        | 27.43%  |
| 8.01-16.0   | 20        | 17.7%   |
| 16.01-24.0  | 14        | 12.39%  |
| 32.01-64.0  | 6         | 5.31%   |
| 1.01-2.0    | 5         | 4.42%   |
| 2.01-3.0    | 4         | 3.54%   |
| 64.01-256.0 | 1         | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 44        | 36.67%  |
| 2.01-3.0   | 23        | 19.17%  |
| 4.01-8.0   | 17        | 14.17%  |
| 0.51-1.0   | 17        | 14.17%  |
| 3.01-4.0   | 12        | 10%     |
| 8.01-16.0  | 4         | 3.33%   |
| 16.01-24.0 | 2         | 1.67%   |
| 24.01-32.0 | 1         | 0.83%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 91        | 80.53%  |
| 2      | 19        | 16.81%  |
| 3      | 3         | 2.65%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 79        | 69.91%  |
| Yes       | 34        | 30.09%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 83.33%  |
| No        | 19        | 16.67%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 99.12%  |
| No        | 1         | 0.88%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 73.68%  |
| No        | 30        | 26.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Moldova | 113       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Chisinau        | 73        | 62.93%  |
| Tiraspol        | 14        | 12.07%  |
| Bălţi         | 4         | 3.45%   |
| Straseni        | 3         | 2.59%   |
| Tighina         | 2         | 1.72%   |
| Soroca          | 2         | 1.72%   |
| Hincesti        | 2         | 1.72%   |
| Zaicana         | 1         | 0.86%   |
| Soldanesti      | 1         | 0.86%   |
| Sofia           | 1         | 0.86%   |
| Rautel          | 1         | 0.86%   |
| Prajila         | 1         | 0.86%   |
| Pociumbeni      | 1         | 0.86%   |
| Ialoveni        | 1         | 0.86%   |
| Gangura         | 1         | 0.86%   |
| Floresti        | 1         | 0.86%   |
| Floreni         | 1         | 0.86%   |
| Donduseni       | 1         | 0.86%   |
| Criuleni        | 1         | 0.86%   |
| Crasnoarmeiscoe | 1         | 0.86%   |
| Cenac           | 1         | 0.86%   |
| Căușeni       | 1         | 0.86%   |
| Cahul           | 1         | 0.86%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 33     | 19.26%  |
| WDC                 | 16        | 17     | 11.85%  |
| Toshiba             | 16        | 20     | 11.85%  |
| Seagate             | 13        | 15     | 9.63%   |
| Hitachi             | 11        | 12     | 8.15%   |
| SanDisk             | 8         | 8      | 5.93%   |
| Kingston            | 7         | 9      | 5.19%   |
| SK hynix            | 5         | 5      | 3.7%    |
| Unknown             | 4         | 4      | 2.96%   |
| Micron Technology   | 4         | 6      | 2.96%   |
| HGST                | 3         | 3      | 2.22%   |
| Intel               | 2         | 4      | 1.48%   |
| Fujitsu             | 2         | 2      | 1.48%   |
| A-DATA Technology   | 2         | 2      | 1.48%   |
| ZOTAC               | 1         | 3      | 0.74%   |
| Transcend           | 1         | 1      | 0.74%   |
| Solid State Storage | 1         | 1      | 0.74%   |
| PNY                 | 1         | 1      | 0.74%   |
| Phison              | 1         | 2      | 0.74%   |
| OCZ                 | 1         | 1      | 0.74%   |
| Netac               | 1         | 1      | 0.74%   |
| LITEONIT            | 1         | 1      | 0.74%   |
| Lenovo              | 1         | 1      | 0.74%   |
| KIOXIA              | 1         | 1      | 0.74%   |
| Intenso             | 1         | 1      | 0.74%   |
| GOODRAM             | 1         | 1      | 0.74%   |
| Crucial             | 1         | 1      | 0.74%   |
| China               | 1         | 1      | 0.74%   |
| ASMT                | 1         | 1      | 0.74%   |
| Apacer              | 1         | 1      | 0.74%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB        | 6         | 4.41%   |
| Toshiba MQ01ABD100 1TB              | 4         | 2.94%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 2.94%   |
| Kingston SHFS37A120G 120GB SSD      | 4         | 2.94%   |
| Toshiba MQ04ABF100 1TB              | 3         | 2.21%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 2.21%   |
| SanDisk NVMe SSD Drive 512GB        | 3         | 2.21%   |
| Hitachi HTS543232A7A384 320GB       | 3         | 2.21%   |
| WDC WD10SPZX-24Z10T0 1TB            | 2         | 1.47%   |
| Unknown MMC Card  64GB              | 2         | 1.47%   |
| Toshiba MQ01ACF032 320GB            | 2         | 1.47%   |
| Toshiba MQ01ABF050 500GB            | 2         | 1.47%   |
| SK hynix NVMe SSD Drive 256GB       | 2         | 1.47%   |
| Samsung SSD 860 EVO 500GB           | 2         | 1.47%   |
| Samsung MZVLW256HEHP-00000 256GB    | 2         | 1.47%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 2         | 1.47%   |
| Hitachi HTS547575A9E384 752GB       | 2         | 1.47%   |
| ZOTAC ZTSSD-S11-240G-P 240GB        | 1         | 0.74%   |
| WDC WDS512G1X0C-00ENX0 512GB        | 1         | 0.74%   |
| WDC WD5000LPVX-80V0TT0 500GB        | 1         | 0.74%   |
| WDC WD5000LPVX-75V0TT0 500GB        | 1         | 0.74%   |
| WDC WD5000LPCX-75VHAT1 500GB        | 1         | 0.74%   |
| WDC WD5000BPVT-08HXZT3 500GB        | 1         | 0.74%   |
| WDC WD5000BEVT-22A0RT0 500GB        | 1         | 0.74%   |
| WDC WD3200BPVT-80JJ5T0 320GB        | 1         | 0.74%   |
| WDC WD3200BEVT-63ZCT0 320GB         | 1         | 0.74%   |
| WDC WD3200BEVT-22A23T0 320GB        | 1         | 0.74%   |
| WDC WD3200BEVT-00ZCT0 320GB         | 1         | 0.74%   |
| WDC WD1600BEVS-07RST0 160GB         | 1         | 0.74%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 0.74%   |
| WDC WD10SPZX-22Z10T1 1TB            | 1         | 0.74%   |
| WDC WD10SPSX-60A6WT0 1TB            | 1         | 0.74%   |
| Unknown TO  64GB                    | 1         | 0.74%   |
| Unknown SD/MMC/MS PRO 1TB           | 1         | 0.74%   |
| Transcend TS120GMTS420S 120GB SSD   | 1         | 0.74%   |
| Toshiba THNSNJ128GMCU 128GB SSD     | 1         | 0.74%   |
| Toshiba MQ01ABD050 500GB            | 1         | 0.74%   |
| Toshiba MK1252GSX 120GB             | 1         | 0.74%   |
| Toshiba KXG60ZNV512G NVMe 512GB     | 1         | 0.74%   |
| Toshiba KXG60ZNV1T02 KIOXIA 1TB     | 1         | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 15        | 16     | 25.42%  |
| Toshiba | 13        | 17     | 22.03%  |
| Seagate | 13        | 15     | 22.03%  |
| Hitachi | 11        | 12     | 18.64%  |
| HGST    | 3         | 3      | 5.08%   |
| Fujitsu | 2         | 2      | 3.39%   |
| Unknown | 1         | 1      | 1.69%   |
| ASMT    | 1         | 1      | 1.69%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 11     | 25%     |
| Kingston            | 6         | 8      | 18.75%  |
| SanDisk             | 3         | 3      | 9.38%   |
| Micron Technology   | 2         | 2      | 6.25%   |
| ZOTAC               | 1         | 3      | 3.13%   |
| Transcend           | 1         | 1      | 3.13%   |
| Toshiba             | 1         | 1      | 3.13%   |
| PNY                 | 1         | 1      | 3.13%   |
| OCZ                 | 1         | 1      | 3.13%   |
| Netac               | 1         | 1      | 3.13%   |
| LITEONIT            | 1         | 1      | 3.13%   |
| Intenso             | 1         | 1      | 3.13%   |
| GOODRAM             | 1         | 1      | 3.13%   |
| Crucial             | 1         | 1      | 3.13%   |
| China               | 1         | 1      | 3.13%   |
| Apacer              | 1         | 1      | 3.13%   |
| A-DATA Technology   | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 59        | 67     | 44.7%   |
| NVMe | 40        | 50     | 30.3%   |
| SSD  | 30        | 39     | 22.73%  |
| MMC  | 3         | 3      | 2.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 81        | 104    | 64.29%  |
| NVMe | 40        | 50     | 31.75%  |
| MMC  | 3         | 3      | 2.38%   |
| SAS  | 2         | 2      | 1.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 62        | 78     | 72.09%  |
| 0.51-1.0   | 24        | 28     | 27.91%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 39        | 32.77%  |
| 101-250    | 37        | 31.09%  |
| 501-1000   | 17        | 14.29%  |
| 51-100     | 9         | 7.56%   |
| 1-20       | 5         | 4.2%    |
| Unknown    | 5         | 4.2%    |
| 1001-2000  | 4         | 3.36%   |
| 21-50      | 3         | 2.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 53        | 43.09%  |
| 21-50    | 21        | 17.07%  |
| 51-100   | 16        | 13.01%  |
| 101-250  | 14        | 11.38%  |
| 251-500  | 10        | 8.13%   |
| Unknown  | 5         | 4.07%   |
| 501-1000 | 4         | 3.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB   | 3         | 3      | 20%     |
| Hitachi HTS547575A9E384 752GB     | 2         | 2      | 13.33%  |
| WDC WD3200BEVT-22A23T0 320GB      | 1         | 1      | 6.67%   |
| WDC WD1600BEVS-07RST0 160GB       | 1         | 1      | 6.67%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 6.67%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 6.67%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 6.67%   |
| SanDisk SD7UB3Q256G1001 256GB SSD | 1         | 1      | 6.67%   |
| Kingston SHFS37A120G 120GB SSD    | 1         | 3      | 6.67%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 6.67%   |
| Fujitsu MHW2080BH PL 80GB         | 1         | 1      | 6.67%   |
| A-DATA Technology SX900 256GB SSD | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 5         | 5      | 33.33%  |
| Hitachi           | 3         | 3      | 20%     |
| WDC               | 2         | 2      | 13.33%  |
| Toshiba           | 1         | 1      | 6.67%   |
| SanDisk           | 1         | 1      | 6.67%   |
| Kingston          | 1         | 3      | 6.67%   |
| Fujitsu           | 1         | 1      | 6.67%   |
| A-DATA Technology | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 41.67%  |
| Hitachi | 3         | 3      | 25%     |
| WDC     | 2         | 2      | 16.67%  |
| Toshiba | 1         | 1      | 8.33%   |
| Fujitsu | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 80%     |
| SSD  | 3         | 5      | 20%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9250315AS 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 54        | 77     | 45.38%  |
| Detected | 49        | 64     | 41.18%  |
| Malfunc  | 15        | 17     | 12.61%  |
| Failed   | 1         | 1      | 0.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 72        | 51.06%  |
| AMD                            | 28        | 19.86%  |
| Samsung Electronics            | 18        | 12.77%  |
| SanDisk                        | 6         | 4.26%   |
| SK hynix                       | 5         | 3.55%   |
| Toshiba America Info Systems   | 2         | 1.42%   |
| Nvidia                         | 2         | 1.42%   |
| Micron Technology              | 2         | 1.42%   |
| Solid State Storage Technology | 1         | 0.71%   |
| Phison Electronics             | 1         | 0.71%   |
| Lenovo                         | 1         | 0.71%   |
| KIOXIA                         | 1         | 0.71%   |
| Kingston Technology Company    | 1         | 0.71%   |
| ADATA Technology               | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 12.58%  |
| Samsung NVMe SSD Controller 980                                                  | 11        | 7.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 6.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 4.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 4.64%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 3.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 3.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 2.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 2.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.99%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.99%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.99%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 1.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.99%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.99%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.32%   |
| SK hynix Gold P31 SSD                                                            | 2         | 1.32%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 1.32%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 2         | 1.32%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 2         | 1.32%   |
| Micron Non-Volatile memory controller                                            | 2         | 1.32%   |
| Intel SSD 660P Series                                                            | 2         | 1.32%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.32%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.32%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 1.32%   |
| Solid State Storage Non-Volatile memory controller                               | 1         | 0.66%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 0.66%   |
| SK hynix BC511                                                                   | 1         | 0.66%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.66%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.66%   |
| SanDisk WD Black NVMe SSD                                                        | 1         | 0.66%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.66%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 0.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.66%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 92        | 62.16%  |
| NVMe | 40        | 27.03%  |
| IDE  | 9         | 6.08%   |
| RAID | 7         | 4.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 80        | 70.8%   |
| AMD    | 33        | 29.2%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 2.65%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.65%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 2.65%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 2.65%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 3         | 2.65%   |
| AMD E-450 APU with Radeon HD Graphics         | 3         | 2.65%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 1.77%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.77%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.77%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.77%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.77%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.77%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 1.77%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 2         | 1.77%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.77%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.77%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.77%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.77%   |
| AMD E-300 APU with Radeon HD Graphics         | 2         | 1.77%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.88%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.88%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.88%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.88%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.88%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.88%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.88%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.88%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.88%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.88%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 0.88%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.88%   |
| Intel Core i5-8400H CPU @ 2.50GHz             | 1         | 0.88%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.88%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.88%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 1         | 0.88%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 26        | 23.01%  |
| Intel Core i7                  | 15        | 13.27%  |
| Intel Core i3                  | 13        | 11.5%   |
| Intel Celeron                  | 10        | 8.85%   |
| AMD Ryzen 5                    | 7         | 6.19%   |
| Intel Pentium                  | 5         | 4.42%   |
| AMD Ryzen 7                    | 5         | 4.42%   |
| AMD E                          | 5         | 4.42%   |
| Other                          | 4         | 3.54%   |
| Intel Core 2 Duo               | 3         | 2.65%   |
| AMD E1                         | 3         | 2.65%   |
| Intel Pentium Silver           | 2         | 1.77%   |
| AMD Sempron                    | 2         | 1.77%   |
| AMD A4                         | 2         | 1.77%   |
| AMD A10                        | 2         | 1.77%   |
| Intel Pentium Dual-Core        | 1         | 0.88%   |
| Intel Core i9                  | 1         | 0.88%   |
| AMD V140                       | 1         | 0.88%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.88%   |
| AMD Ryzen 5 PRO                | 1         | 0.88%   |
| AMD Ryzen 3                    | 1         | 0.88%   |
| AMD Athlon 64 X2               | 1         | 0.88%   |
| AMD Athlon                     | 1         | 0.88%   |
| AMD A6                         | 1         | 0.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 56        | 49.56%  |
| 4       | 38        | 33.63%  |
| 6       | 10        | 8.85%   |
| 8       | 6         | 5.31%   |
| 1       | 2         | 1.77%   |
| Unknown | 1         | 0.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 113       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 70        | 61.95%  |
| 1       | 42        | 37.17%  |
| Unknown | 1         | 0.88%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 110       | 97.35%  |
| Unknown        | 3         | 2.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 14.91%  |
| 0x806ea    | 8         | 7.02%   |
| 0x206a7    | 8         | 7.02%   |
| 0x05000119 | 8         | 7.02%   |
| 0x806ec    | 6         | 5.26%   |
| 0x906ea    | 4         | 3.51%   |
| 0x40651    | 4         | 3.51%   |
| 0x306c3    | 4         | 3.51%   |
| 0x08600106 | 4         | 3.51%   |
| 0x806e9    | 3         | 2.63%   |
| 0x506c9    | 3         | 2.63%   |
| 0x406e3    | 3         | 2.63%   |
| 0x306d4    | 3         | 2.63%   |
| 0x306a9    | 3         | 2.63%   |
| 0xa0652    | 2         | 1.75%   |
| 0x806c1    | 2         | 1.75%   |
| 0x706e5    | 2         | 1.75%   |
| 0x706a1    | 2         | 1.75%   |
| 0x406c4    | 2         | 1.75%   |
| 0x30678    | 2         | 1.75%   |
| 0x0a50000c | 2         | 1.75%   |
| 0x08608103 | 2         | 1.75%   |
| 0x08108102 | 2         | 1.75%   |
| 0x06001119 | 2         | 1.75%   |
| 0x03000027 | 2         | 1.75%   |
| 0x02000057 | 2         | 1.75%   |
| 0x906e9    | 1         | 0.88%   |
| 0x806d1    | 1         | 0.88%   |
| 0x706a8    | 1         | 0.88%   |
| 0x6fd      | 1         | 0.88%   |
| 0x6fb      | 1         | 0.88%   |
| 0x406c3    | 1         | 0.88%   |
| 0x20652    | 1         | 0.88%   |
| 0x1067a    | 1         | 0.88%   |
| 0x08108109 | 1         | 0.88%   |
| 0x02000032 | 1         | 0.88%   |
| 0x010000c8 | 1         | 0.88%   |
| 0x0100009f | 1         | 0.88%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 27        | 23.89%  |
| Haswell         | 9         | 7.96%   |
| SandyBridge     | 8         | 7.08%   |
| Bobcat          | 8         | 7.08%   |
| Zen 2           | 6         | 5.31%   |
| Silvermont      | 5         | 4.42%   |
| Zen+            | 4         | 3.54%   |
| IceLake         | 4         | 3.54%   |
| Goldmont plus   | 4         | 3.54%   |
| TigerLake       | 3         | 2.65%   |
| Skylake         | 3         | 2.65%   |
| K8 & K10 hybrid | 3         | 2.65%   |
| IvyBridge       | 3         | 2.65%   |
| Goldmont        | 3         | 2.65%   |
| Core            | 3         | 2.65%   |
| Broadwell       | 3         | 2.65%   |
| Unknown         | 3         | 2.65%   |
| Zen 3           | 2         | 1.77%   |
| Piledriver      | 2         | 1.77%   |
| K10 Llano       | 2         | 1.77%   |
| K10             | 2         | 1.77%   |
| CometLake       | 2         | 1.77%   |
| Westmere        | 1         | 0.88%   |
| Puma            | 1         | 0.88%   |
| Penryn          | 1         | 0.88%   |
| K8 Hammer       | 1         | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 78        | 55.32%  |
| AMD    | 34        | 24.11%  |
| Nvidia | 29        | 20.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 8         | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 5.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 4.17%   |
| AMD Renoir                                                                               | 6         | 4.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 3.47%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 3.47%   |
| Intel HD Graphics 620                                                                    | 4         | 2.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.78%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.78%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 2.08%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 2.08%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 2.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.08%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 2.08%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.08%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 2.08%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 3         | 2.08%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 2.08%   |
| Nvidia TU117M                                                                            | 2         | 1.39%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.39%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 1.39%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 2         | 1.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.39%   |
| Intel HD Graphics 500                                                                    | 2         | 1.39%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.39%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.39%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 1.39%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.39%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 1.39%   |
| AMD Lucienne                                                                             | 2         | 1.39%   |
| AMD Cezanne                                                                              | 2         | 1.39%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.69%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.69%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.69%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.69%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 51        | 45.13%  |
| 1 x AMD        | 27        | 23.89%  |
| Intel + Nvidia | 23        | 20.35%  |
| 1 x Nvidia     | 4         | 3.54%   |
| Intel + AMD    | 3         | 2.65%   |
| 2 x AMD        | 2         | 1.77%   |
| AMD + Nvidia   | 2         | 1.77%   |
| Other          | 1         | 0.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 97        | 83.62%  |
| Proprietary | 14        | 12.07%  |
| Unknown     | 5         | 4.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 51.28%  |
| 0.01-0.5   | 25        | 21.37%  |
| 1.01-2.0   | 23        | 19.66%  |
| 3.01-4.0   | 7         | 5.98%   |
| 7.01-8.0   | 1         | 0.85%   |
| 0.51-1.0   | 1         | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 31        | 24.22%  |
| LG Display              | 20        | 15.63%  |
| Chimei Innolux          | 19        | 14.84%  |
| Samsung Electronics     | 12        | 9.38%   |
| BOE                     | 12        | 9.38%   |
| Philips                 | 7         | 5.47%   |
| Chi Mei Optoelectronics | 5         | 3.91%   |
| InfoVision              | 4         | 3.13%   |
| Dell                    | 4         | 3.13%   |
| Sharp                   | 3         | 2.34%   |
| AOC                     | 3         | 2.34%   |
| Lenovo                  | 2         | 1.56%   |
| Goldstar                | 2         | 1.56%   |
| CSO                     | 2         | 1.56%   |
| PANDA                   | 1         | 0.78%   |
| BenQ                    | 1         | 0.78%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 4         | 3.1%    |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 3         | 2.33%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 2.33%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 3         | 2.33%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 2.33%   |
| Philips 223E PHLC049 1920x1080 476x268mm 21.5-inch                    | 2         | 1.55%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 2         | 1.55%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch       | 2         | 1.55%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                 | 2         | 1.55%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 2         | 1.55%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 1.55%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.78%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.78%   |
| Sharp LCD Monitor SHP13CF 1280x800 331x207mm 15.4-inch                | 1         | 0.78%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch     | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1         | 0.78%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5842 1366x768 309x174mm 14.0-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch | 1         | 0.78%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch              | 1         | 0.78%   |
| Philips PHL 243S7 PHL090F 1920x1080 527x296mm 23.8-inch               | 1         | 0.78%   |
| Philips PHL 223V7 PHLC154 1920x1080 480x270mm 21.7-inch               | 1         | 0.78%   |
| Philips 247ELH PHLC085 1920x1080 521x293mm 23.5-inch                  | 1         | 0.78%   |
| Philips 227E4LH PHLC0AC 1920x1080 477x268mm 21.5-inch                 | 1         | 0.78%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.78%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 1         | 0.78%   |
| LG Display LCD Monitor LGD06E0 1920x1080 344x194mm 15.5-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD05CE 1920x1080 344x194mm 15.5-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 1         | 0.78%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 52        | 44.07%  |
| 1366x768 (WXGA)    | 43        | 36.44%  |
| 1600x900 (HD+)     | 8         | 6.78%   |
| 3840x2160 (4K)     | 3         | 2.54%   |
| 2560x1440 (QHD)    | 3         | 2.54%   |
| 1280x800 (WXGA)    | 3         | 2.54%   |
| 2560x1600          | 2         | 1.69%   |
| 3456x2160          | 1         | 0.85%   |
| 2160x1440          | 1         | 0.85%   |
| 1680x1050 (WSXGA+) | 1         | 0.85%   |
| 1280x1024 (SXGA)   | 1         | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 78        | 60.47%  |
| 14     | 10        | 7.75%   |
| 17     | 6         | 4.65%   |
| 13     | 6         | 4.65%   |
| 24     | 5         | 3.88%   |
| 21     | 5         | 3.88%   |
| 27     | 4         | 3.1%    |
| 23     | 4         | 3.1%    |
| 11     | 4         | 3.1%    |
| 16     | 2         | 1.55%   |
| 12     | 2         | 1.55%   |
| 31     | 1         | 0.78%   |
| 22     | 1         | 0.78%   |
| 19     | 1         | 0.78%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 92        | 71.88%  |
| 501-600     | 11        | 8.59%   |
| 201-300     | 9         | 7.03%   |
| 351-400     | 8         | 6.25%   |
| 401-500     | 6         | 4.69%   |
| 601-700     | 2         | 1.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 101       | 91.82%  |
| 16/10 | 7         | 6.36%   |
| 5/4   | 1         | 0.91%   |
| 3/2   | 1         | 0.91%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 78        | 60.94%  |
| 81-90          | 14        | 10.94%  |
| 201-250        | 12        | 9.38%   |
| 51-60          | 4         | 3.13%   |
| 301-350        | 4         | 3.13%   |
| 121-130        | 4         | 3.13%   |
| 151-200        | 3         | 2.34%   |
| 71-80          | 2         | 1.56%   |
| 61-70          | 2         | 1.56%   |
| 131-140        | 2         | 1.56%   |
| 111-120        | 2         | 1.56%   |
| 351-500        | 1         | 0.78%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 57        | 45.6%   |
| 101-120       | 44        | 35.2%   |
| 51-100        | 17        | 13.6%   |
| 161-240       | 5         | 4%      |
| More than 240 | 2         | 1.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 94        | 81.74%  |
| 2     | 20        | 17.39%  |
| 0     | 1         | 0.87%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 73        | 39.89%  |
| Intel                             | 43        | 23.5%   |
| Qualcomm Atheros                  | 36        | 19.67%  |
| Broadcom                          | 10        | 5.46%   |
| Xiaomi                            | 3         | 1.64%   |
| Ralink                            | 3         | 1.64%   |
| Broadcom Limited                  | 3         | 1.64%   |
| Nvidia                            | 2         | 1.09%   |
| TP-Link                           | 1         | 0.55%   |
| Sierra Wireless                   | 1         | 0.55%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.55%   |
| MediaTek                          | 1         | 0.55%   |
| Marvell Technology Group          | 1         | 0.55%   |
| JMicron Technology                | 1         | 0.55%   |
| ICS Advent                        | 1         | 0.55%   |
| Huawei Technologies               | 1         | 0.55%   |
| Hewlett-Packard                   | 1         | 0.55%   |
| Ericsson Business Mobile Networks | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 44        | 20.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 19        | 8.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 4.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 4.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 3.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 3.26%   |
| Intel Wireless 8265 / 8275                                              | 7         | 3.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 3         | 1.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.4%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.4%    |
| Intel Wireless 7260                                                     | 3         | 1.4%    |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.4%    |
| Intel Wi-Fi 6 AX200                                                     | 3         | 1.4%    |
| Intel Ethernet Connection I218-LM                                       | 3         | 1.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.4%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.93%   |
| Nvidia MCP77 Ethernet                                                   | 2         | 0.93%   |
| Intel Wireless 8260                                                     | 2         | 0.93%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.93%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.93%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 2         | 0.93%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 0.93%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.47%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 1         | 0.47%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.47%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.47%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.47%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.47%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]        | 1         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 41        | 35.65%  |
| Qualcomm Atheros      | 34        | 29.57%  |
| Realtek Semiconductor | 26        | 22.61%  |
| Broadcom              | 7         | 6.09%   |
| Ralink                | 3         | 2.61%   |
| TP-Link               | 1         | 0.87%   |
| Sierra Wireless       | 1         | 0.87%   |
| MediaTek              | 1         | 0.87%   |
| Broadcom Limited      | 1         | 0.87%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 7.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 7.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 6.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 6.09%   |
| Intel Wireless 8265 / 8275                                              | 7         | 6.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 3.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 3.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.61%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 2.61%   |
| Intel Wireless 7260                                                     | 3         | 2.61%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 2.61%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 2.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.74%   |
| Intel Wireless 8260                                                     | 2         | 1.74%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.74%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.74%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.74%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.87%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 1         | 0.87%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.87%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.87%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.87%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.87%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]        | 1         | 0.87%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.87%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.87%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.87%   |
| Intel Wireless 7265                                                     | 1         | 0.87%   |
| Intel Wireless 3165                                                     | 1         | 0.87%   |
| Intel Wireless 3160                                                     | 1         | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 64        | 65.98%  |
| Intel                    | 15        | 15.46%  |
| Xiaomi                   | 3         | 3.09%   |
| Qualcomm Atheros         | 3         | 3.09%   |
| Broadcom                 | 3         | 3.09%   |
| Nvidia                   | 2         | 2.06%   |
| Broadcom Limited         | 2         | 2.06%   |
| Marvell Technology Group | 1         | 1.03%   |
| JMicron Technology       | 1         | 1.03%   |
| ICS Advent               | 1         | 1.03%   |
| Huawei Technologies      | 1         | 1.03%   |
| Hewlett-Packard          | 1         | 1.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 44        | 44.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 19        | 19.39%  |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 3.06%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 3.06%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 2.04%   |
| Nvidia MCP77 Ethernet                                                          | 2         | 2.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 2.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.02%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 1.02%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 1.02%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.02%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 1.02%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.02%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.02%   |
| Intel Ethernet Connection I217-V                                               | 1         | 1.02%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 1.02%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 1.02%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.02%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 1.02%   |
| Intel Ethernet Connection (10) I219-LM                                         | 1         | 1.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 1.02%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 1.02%   |
| Intel 82562GT 10/100 Network Connection                                        | 1         | 1.02%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 1.02%   |
| Huawei E353/E3131                                                              | 1         | 1.02%   |
| HP HP lt4120 Snapdragon X5 LTE                                                 | 1         | 1.02%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 1.02%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 1.02%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 1.02%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 112       | 53.59%  |
| Ethernet | 95        | 45.45%  |
| Modem    | 1         | 0.48%   |
| Unknown  | 1         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 87        | 74.36%  |
| Ethernet | 30        | 25.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 88        | 77.88%  |
| 1     | 25        | 22.12%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 109       | 96.46%  |
| Yes  | 4         | 3.54%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 39.29%  |
| Qualcomm Atheros Communications | 12        | 14.29%  |
| Realtek Semiconductor           | 11        | 13.1%   |
| IMC Networks                    | 10        | 11.9%   |
| Lite-On Technology              | 5         | 5.95%   |
| Broadcom                        | 5         | 5.95%   |
| Foxconn / Hon Hai               | 3         | 3.57%   |
| Toshiba                         | 1         | 1.19%   |
| Realtek                         | 1         | 1.19%   |
| Ralink Technology               | 1         | 1.19%   |
| Hewlett-Packard                 | 1         | 1.19%   |
| Dell                            | 1         | 1.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 14        | 16.67%  |
| Realtek Bluetooth Radio                                                             | 9         | 10.71%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 9.52%   |
| Intel AX201 Bluetooth                                                               | 8         | 9.52%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 5.95%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 5.95%   |
| IMC Networks Bluetooth Device                                                       | 4         | 4.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 3.57%   |
| Intel AX200 Bluetooth                                                               | 3         | 3.57%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 2.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 2.38%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 2.38%   |
| Broadcom BCM20702A0                                                                 | 2         | 2.38%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 1.19%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.19%   |
| Ralink CSR BS8510                                                                   | 1         | 1.19%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.19%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.19%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 1.19%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.19%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.19%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 1.19%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.19%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 1.19%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.19%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.19%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.19%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 1.19%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 1.19%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 1.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 80        | 63.49%  |
| AMD         | 31        | 24.6%   |
| Nvidia      | 12        | 9.52%   |
| Logitech    | 2         | 1.59%   |
| Plantronics | 1         | 0.79%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 9.09%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 14        | 8.48%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 5.45%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 5.45%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 4.85%   |
| AMD FCH Azalia Controller                                                                         | 8         | 4.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 4.24%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 3.64%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 3.03%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.03%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 2.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 2.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 2.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.82%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.82%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 1.21%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.21%   |
| Logitech H600 [Wireless Headset]                                                                  | 2         | 1.21%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.21%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.21%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.21%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 1.21%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 1.21%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 1.21%   |
| Plantronics Audio 622 USB                                                                         | 1         | 0.61%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.61%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.61%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.61%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 32.93%  |
| SK hynix            | 17        | 20.73%  |
| Kingston            | 7         | 8.54%   |
| Micron Technology   | 6         | 7.32%   |
| Unknown             | 5         | 6.1%    |
| GOODRAM             | 4         | 4.88%   |
| Unknown (ABCD)      | 2         | 2.44%   |
| Transcend           | 2         | 2.44%   |
| Ramaxel Technology  | 2         | 2.44%   |
| Elpida              | 2         | 2.44%   |
| Unifosa             | 1         | 1.22%   |
| Nanya Technology    | 1         | 1.22%   |
| Crucial             | 1         | 1.22%   |
| Corsair             | 1         | 1.22%   |
| Axiom               | 1         | 1.22%   |
| ASint Technology    | 1         | 1.22%   |
| Apacer              | 1         | 1.22%   |
| A-DATA Technology   | 1         | 1.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 3.45%   |
| Unknown RAM Module 2048MB SODIMM DRAM 667MT/s                    | 2         | 2.3%    |
| Unknown RAM Module 1024MB SODIMM DRAM 667MT/s                    | 2         | 2.3%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.3%    |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.3%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.3%    |
| Samsung RAM M471B2873FHS-CF8 1GB SODIMM DDR3 1067MT/s            | 2         | 2.3%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 2.3%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 2.3%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.15%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.15%   |
| Unknown RAM Module 2048MB SODIMM DDR2 400MT/s                    | 1         | 1.15%   |
| Unifosa RAM GU672203EP0200 1GB SODIMM DDR3 1333MT/s              | 1         | 1.15%   |
| Transcend RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 1         | 1.15%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s           | 1         | 1.15%   |
| SK hynix RAM Module 32GB SODIMM DDR4 2667MT/s                    | 1         | 1.15%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM SDRAM 2048MT/s          | 1         | 1.15%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT125S6TFR8C-H9 2048MB SODIMM DDR3 4199MT/s        | 1         | 1.15%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 1.15%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.15%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.15%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.15%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.15%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.15%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.15%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 1         | 1.15%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.15%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.15%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.15%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| Samsung RAM M471B5173BH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.15%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.15%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 31        | 42.47%  |
| DDR4   | 27        | 36.99%  |
| SDRAM  | 4         | 5.48%   |
| LPDDR4 | 4         | 5.48%   |
| DDR2   | 3         | 4.11%   |
| LPDDR3 | 2         | 2.74%   |
| DRAM   | 2         | 2.74%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 63        | 90%     |
| Row Of Chips | 7         | 10%     |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 30        | 37.97%  |
| 8192  | 20        | 25.32%  |
| 2048  | 13        | 16.46%  |
| 16384 | 8         | 10.13%  |
| 1024  | 6         | 7.59%   |
| 32768 | 2         | 2.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 22        | 28.57%  |
| 2667    | 19        | 24.68%  |
| 3200    | 6         | 7.79%   |
| 1334    | 5         | 6.49%   |
| 2400    | 4         | 5.19%   |
| 1333    | 4         | 5.19%   |
| 4199    | 2         | 2.6%    |
| 2133    | 2         | 2.6%    |
| 2048    | 2         | 2.6%    |
| 1067    | 2         | 2.6%    |
| 667     | 2         | 2.6%    |
| 400     | 2         | 2.6%    |
| 4800    | 1         | 1.3%    |
| 3266    | 1         | 1.3%    |
| 1867    | 1         | 1.3%    |
| 975     | 1         | 1.3%    |
| Unknown | 1         | 1.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Notebooks | Percent |
|---------------------|-----------|---------|
| Canon iP7200 series | 1         | 100%    |

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
| Chicony Electronics                    | 25        | 24.27%  |
| IMC Networks                           | 22        | 21.36%  |
| Realtek Semiconductor                  | 12        | 11.65%  |
| Microdia                               | 7         | 6.8%    |
| Acer                                   | 6         | 5.83%   |
| Quanta                                 | 5         | 4.85%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.85%   |
| Syntek                                 | 3         | 2.91%   |
| Sunplus Innovation Technology          | 3         | 2.91%   |
| Silicon Motion                         | 3         | 2.91%   |
| Lite-On Technology                     | 3         | 2.91%   |
| Suyin                                  | 2         | 1.94%   |
| Luxvisions Innotech Limited            | 2         | 1.94%   |
| Alcor Micro                            | 2         | 1.94%   |
| Z-Star Microelectronics                | 1         | 0.97%   |
| Samsung Electronics                    | 1         | 0.97%   |
| Importek                               | 1         | 0.97%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                           | 5         | 4.85%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 5         | 4.85%   |
| Chicony Integrated Camera                                    | 5         | 4.85%   |
| IMC Networks Integrated Camera                               | 4         | 3.88%   |
| Realtek Integrated_Webcam_HD                                 | 3         | 2.91%   |
| Quanta HP HD Camera                                          | 3         | 2.91%   |
| Chicony HD WebCam                                            | 3         | 2.91%   |
| Syntek Lenovo EasyCamera                                     | 2         | 1.94%   |
| Silicon Motion WebCam SC-0311139N                            | 2         | 1.94%   |
| Realtek USB Camera                                           | 2         | 1.94%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 2         | 1.94%   |
| Microdia Integrated_Webcam_HD                                | 2         | 1.94%   |
| Lite-On HP HD Webcam                                         | 2         | 1.94%   |
| IMC Networks VGA UVC WebCam                                  | 2         | 1.94%   |
| Chicony USB2.0 VGA UVC WebCam                                | 2         | 1.94%   |
| Chicony Integrated Camera (1280x720@30)                      | 2         | 1.94%   |
| Chicony EasyCamera                                           | 2         | 1.94%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 2         | 1.94%   |
| Z-Star WebCam SCB-0320N                                      | 1         | 0.97%   |
| Syntek Integrated Camera                                     | 1         | 0.97%   |
| Suyin HP Truevision HD                                       | 1         | 0.97%   |
| Suyin HD WebCam                                              | 1         | 0.97%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.97%   |
| Sunplus Integrated_Webcam_HD                                 | 1         | 0.97%   |
| Sunplus HD WebCam                                            | 1         | 0.97%   |
| Silicon Motion WebCam SC-13HDL11939N                         | 1         | 0.97%   |
| Samsung Galaxy series, misc. (MTP mode)                      | 1         | 0.97%   |
| Realtek USB2.0 VGA UVC WebCam                                | 1         | 0.97%   |
| Realtek TOSHIBA Web Camera                                   | 1         | 0.97%   |
| Realtek Integrated Webcam_HD                                 | 1         | 0.97%   |
| Realtek Integrated Webcam HD                                 | 1         | 0.97%   |
| Realtek HP Truevision HD                                     | 1         | 0.97%   |
| Realtek HP "Truevision HD" laptop camera                     | 1         | 0.97%   |
| Realtek HD WebCam                                            | 1         | 0.97%   |
| Quanta VGA WebCam                                            | 1         | 0.97%   |
| Quanta HP TrueVision HD Camera                               | 1         | 0.97%   |
| Microdia Webcam Vitade AF                                    | 1         | 0.97%   |
| Microdia Webcam                                              | 1         | 0.97%   |
| Microdia Integrated Webcam                                   | 1         | 0.97%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera         | 1         | 0.97%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 36%     |
| Synaptics                  | 7         | 28%     |
| Shenzhen Goodix Technology | 3         | 12%     |
| Elan Microelectronics      | 3         | 12%     |
| Upek                       | 1         | 4%      |
| LighTuning Technology      | 1         | 4%      |
| AuthenTec                  | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 4         | 16%     |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 12%     |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 8%      |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 8%      |
| Validity Sensors Fingerprint scanner                       | 2         | 8%      |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 8%      |
| Elan ELAN:Fingerprint                                      | 2         | 8%      |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 4%      |
| Validity Sensors Synaptics WBDI                            | 1         | 4%      |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 4%      |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 4%      |
| Elan ELAN:ARM-M4                                           | 1         | 4%      |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 4%      |
| Unknown                                                    | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 1         | 50%     |
| O2 Micro              | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1         | 50%     |
| O2 Micro OZ776 CCID Smartcard Reader              | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 74        | 63.25%  |
| 1     | 34        | 29.06%  |
| 2     | 8         | 6.84%   |
| 3     | 1         | 0.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 25        | 51.02%  |
| Graphics card         | 13        | 26.53%  |
| Net/wireless          | 4         | 8.16%   |
| Multimedia controller | 2         | 4.08%   |
| Chipcard              | 2         | 4.08%   |
| Storage               | 1         | 2.04%   |
| Sound                 | 1         | 2.04%   |
| Camera                | 1         | 2.04%   |

