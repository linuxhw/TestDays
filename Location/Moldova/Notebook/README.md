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

Total: 173

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | ZenBook UX425IA_UM425IA     | [3ac0a9cc94](https://linux-hardware.org/?probe=3ac0a9cc94) | Mar 31, 2023 |
| ASUSTek  | ROG Strix G533QM_G533QM     | [14f30effbe](https://linux-hardware.org/?probe=14f30effbe) | Mar 17, 2023 |
| ASUSTek  | X541NC                      | [d7e16d4472](https://linux-hardware.org/?probe=d7e16d4472) | Mar 11, 2023 |
| Apple    | MacBookPro8,1               | [60ab083fe9](https://linux-hardware.org/?probe=60ab083fe9) | Feb 25, 2023 |
| HP       | Pavilion Gaming Laptop 1... | [138e1ff0a8](https://linux-hardware.org/?probe=138e1ff0a8) | Feb 15, 2023 |
| ASUSTek  | K55A                        | [3faca30fb5](https://linux-hardware.org/?probe=3faca30fb5) | Feb 07, 2023 |
| Timi     | TM1701                      | [a474c92380](https://linux-hardware.org/?probe=a474c92380) | Jan 31, 2023 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [93fd2967ab](https://linux-hardware.org/?probe=93fd2967ab) | Jan 07, 2023 |
| Lenovo   | IdeaPad Gaming 3 15ACH6 ... | [0760eec7e2](https://linux-hardware.org/?probe=0760eec7e2) | Dec 28, 2022 |
| Valve    | Jupiter                     | [d008ed40fe](https://linux-hardware.org/?probe=d008ed40fe) | Nov 17, 2022 |
| Lenovo   | ThinkPad W520 4282BA9       | [4666660667](https://linux-hardware.org/?probe=4666660667) | Nov 12, 2022 |
| Unknown  | Unknown                     | [9247927a69](https://linux-hardware.org/?probe=9247927a69) | Nov 08, 2022 |
| Lenovo   | IdeaPad 330S-15ARR 81FB     | [8979e951e5](https://linux-hardware.org/?probe=8979e951e5) | Nov 07, 2022 |
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


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 18.04       | 12        | 9.09%   |
| Ubuntu 20.04       | 11        | 8.33%   |
| ROSA R10           | 9         | 6.82%   |
| Ubuntu 22.04       | 7         | 5.3%    |
| ROSA R11           | 6         | 4.55%   |
| Linux Mint 20.1    | 5         | 3.79%   |
| KDE neon 20.04     | 4         | 3.03%   |
| Arch               | 4         | 3.03%   |
| ROSA R9            | 3         | 2.27%   |
| ROSA R8            | 3         | 2.27%   |
| ROSA R11.1         | 3         | 2.27%   |
| Linux Mint 21.1    | 3         | 2.27%   |
| Linux Mint 19.1    | 3         | 2.27%   |
| Fedora 36          | 3         | 2.27%   |
| Fedora 34          | 3         | 2.27%   |
| Zorin 16           | 2         | 1.52%   |
| Ubuntu 22.10       | 2         | 1.52%   |
| Ubuntu 19.10       | 2         | 1.52%   |
| ROSA R8.1          | 2         | 1.52%   |
| ROSA 12.2          | 2         | 1.52%   |
| Pop!_OS 21.04      | 2         | 1.52%   |
| OpenMandriva 4.3   | 2         | 1.52%   |
| Manjaro            | 2         | 1.52%   |
| Linux Mint 20.2    | 2         | 1.52%   |
| BlackPanther 18.1  | 2         | 1.52%   |
| Ubuntu 21.04       | 1         | 0.76%   |
| Ubuntu 16.04       | 1         | 0.76%   |
| SteamOS 3.3.2      | 1         | 0.76%   |
| SteamOS 3.3        | 1         | 0.76%   |
| ROSA 12.3          | 1         | 0.76%   |
| ROSA 12.1          | 1         | 0.76%   |
| Pop!_OS 20.10      | 1         | 0.76%   |
| OpenMandriva 4.50  | 1         | 0.76%   |
| OpenMandriva 23.01 | 1         | 0.76%   |
| Manjaro 22.0.0     | 1         | 0.76%   |
| Manjaro 20.2.1     | 1         | 0.76%   |
| Manjaro 20.2       | 1         | 0.76%   |
| Manjaro 19.0.2     | 1         | 0.76%   |
| Manjaro 18.0.4     | 1         | 0.76%   |
| Linux Mint 20.3    | 1         | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 36        | 28.57%  |
| ROSA         | 26        | 20.63%  |
| Linux Mint   | 16        | 12.7%   |
| Fedora       | 9         | 7.14%   |
| Manjaro      | 7         | 5.56%   |
| OpenMandriva | 4         | 3.17%   |
| KDE neon     | 4         | 3.17%   |
| Arch         | 4         | 3.17%   |
| Pop!_OS      | 3         | 2.38%   |
| Endless      | 3         | 2.38%   |
| Zorin        | 2         | 1.59%   |
| SteamOS      | 2         | 1.59%   |
| Kubuntu      | 2         | 1.59%   |
| Kali         | 2         | 1.59%   |
| Debian       | 2         | 1.59%   |
| BlackPanther | 2         | 1.59%   |
| EndeavourOS  | 1         | 0.79%   |
| BuildRoot    | 1         | 0.79%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.15.0-41-generic                  | 4         | 2.86%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 4         | 2.86%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 4         | 2.86%   |
| 5.8.0-33-generic                   | 3         | 2.14%   |
| 4.9.60-nrj-desktop-1rosa-i586      | 3         | 2.14%   |
| 5.4.0-37-generic                   | 2         | 1.43%   |
| 5.16.7-desktop-1omv4003            | 2         | 1.43%   |
| 5.15.0-58-generic                  | 2         | 1.43%   |
| 5.11.0-7614-generic                | 2         | 1.43%   |
| 5.11.0-41-generic                  | 2         | 1.43%   |
| 5.11.0-34-generic                  | 2         | 1.43%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 2         | 1.43%   |
| 5.10.2-2-MANJARO                   | 2         | 1.43%   |
| 4.9.95-nrj-desktop-2rosa-x86_64    | 2         | 1.43%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 2         | 1.43%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 2         | 1.43%   |
| 4.15.0-desktop-68.5rosa-x86_64     | 2         | 1.43%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 2         | 1.43%   |
| 6.2.8-arch1-1                      | 1         | 0.71%   |
| 6.1.1-desktop-1omv2290             | 1         | 0.71%   |
| 5.9.3-1-MANJARO                    | 1         | 0.71%   |
| 5.8.18-100.fc31.x86_64             | 1         | 0.71%   |
| 5.8.18-1-MANJARO                   | 1         | 0.71%   |
| 5.8.0-36-generic                   | 1         | 0.71%   |
| 5.8.0-25-lowlatency                | 1         | 0.71%   |
| 5.6.14-desktop-2bP                 | 1         | 0.71%   |
| 5.4.49-nrj-desktop-1rosa-x86_64    | 1         | 0.71%   |
| 5.4.32-generic-2rosa-x86_64        | 1         | 0.71%   |
| 5.4.0-86-generic                   | 1         | 0.71%   |
| 5.4.0-84-generic                   | 1         | 0.71%   |
| 5.4.0-72-generic                   | 1         | 0.71%   |
| 5.4.0-70-generic                   | 1         | 0.71%   |
| 5.4.0-67-generic                   | 1         | 0.71%   |
| 5.4.0-58-generic                   | 1         | 0.71%   |
| 5.4.0-52-generic                   | 1         | 0.71%   |
| 5.4.0-48-generic                   | 1         | 0.71%   |
| 5.4.0-42-generic                   | 1         | 0.71%   |
| 5.4.0-40-generic                   | 1         | 0.71%   |
| 5.3.0-59-generic                   | 1         | 0.71%   |
| 5.3.0-42-generic                   | 1         | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.15.0  | 15        | 11.03%  |
| 5.15.0  | 13        | 9.56%   |
| 5.4.0   | 12        | 8.82%   |
| 5.11.0  | 11        | 8.09%   |
| 4.9.60  | 6         | 4.41%   |
| 5.8.0   | 5         | 3.68%   |
| 5.3.0   | 4         | 2.94%   |
| 4.9.20  | 4         | 2.94%   |
| 5.13.0  | 3         | 2.21%   |
| 5.0.0   | 3         | 2.21%   |
| 4.18.0  | 3         | 2.21%   |
| 5.8.18  | 2         | 1.47%   |
| 5.19.0  | 2         | 1.47%   |
| 5.18.1  | 2         | 1.47%   |
| 5.16.7  | 2         | 1.47%   |
| 5.10.74 | 2         | 1.47%   |
| 5.10.2  | 2         | 1.47%   |
| 5.10.0  | 2         | 1.47%   |
| 4.9.95  | 2         | 1.47%   |
| 4.9.41  | 2         | 1.47%   |
| 4.9.155 | 2         | 1.47%   |
| 6.2.8   | 1         | 0.74%   |
| 6.1.1   | 1         | 0.74%   |
| 5.9.3   | 1         | 0.74%   |
| 5.6.14  | 1         | 0.74%   |
| 5.4.49  | 1         | 0.74%   |
| 5.4.32  | 1         | 0.74%   |
| 5.19.7  | 1         | 0.74%   |
| 5.19.4  | 1         | 0.74%   |
| 5.18.5  | 1         | 0.74%   |
| 5.18.15 | 1         | 0.74%   |
| 5.18.13 | 1         | 0.74%   |
| 5.18.0  | 1         | 0.74%   |
| 5.17.3  | 1         | 0.74%   |
| 5.17.11 | 1         | 0.74%   |
| 5.16.0  | 1         | 0.74%   |
| 5.15.75 | 1         | 0.74%   |
| 5.15.71 | 1         | 0.74%   |
| 5.15.49 | 1         | 0.74%   |
| 5.15.2  | 1         | 0.74%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 17        | 12.88%  |
| 4.9     | 15        | 11.36%  |
| 4.15    | 15        | 11.36%  |
| 5.4     | 14        | 10.61%  |
| 5.11    | 12        | 9.09%   |
| 5.10    | 8         | 6.06%   |
| 5.8     | 7         | 5.3%    |
| 5.18    | 6         | 4.55%   |
| 5.3     | 4         | 3.03%   |
| 5.19    | 4         | 3.03%   |
| 5.13    | 4         | 3.03%   |
| 5.0     | 4         | 3.03%   |
| 5.16    | 3         | 2.27%   |
| 4.18    | 3         | 2.27%   |
| 4.1     | 3         | 2.27%   |
| 5.17    | 2         | 1.52%   |
| 5.12    | 2         | 1.52%   |
| 6.2     | 1         | 0.76%   |
| 6.1     | 1         | 0.76%   |
| 5.9     | 1         | 0.76%   |
| 5.6     | 1         | 0.76%   |
| 5.14    | 1         | 0.76%   |
| 5.1     | 1         | 0.76%   |
| 4.19    | 1         | 0.76%   |
| 4.16    | 1         | 0.76%   |
| 4.10    | 1         | 0.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 121       | 95.28%  |
| i686   | 6         | 4.72%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 39        | 30.23%  |
| KDE5            | 30        | 23.26%  |
| KDE4            | 19        | 14.73%  |
| Unknown         | 14        | 10.85%  |
| X-Cinnamon      | 12        | 9.3%    |
| XFCE            | 6         | 4.65%   |
| MATE            | 2         | 1.55%   |
| Cinnamon        | 2         | 1.55%   |
| sway            | 1         | 0.78%   |
| LXQt            | 1         | 0.78%   |
| KDE             | 1         | 0.78%   |
| i3              | 1         | 0.78%   |
| GNOME Flashback | 1         | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 96        | 75.59%  |
| Wayland | 21        | 16.54%  |
| Unknown | 10        | 7.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 49        | 37.69%  |
| SDDM    | 22        | 16.92%  |
| KDM     | 19        | 14.62%  |
| GDM     | 18        | 13.85%  |
| LightDM | 8         | 6.15%   |
| GDM3    | 8         | 6.15%   |
| TDM     | 6         | 4.62%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 47        | 37.3%   |
| Unknown | 39        | 30.95%  |
| ru_RU   | 24        | 19.05%  |
| ro_RO   | 7         | 5.56%   |
| C       | 3         | 2.38%   |
| en_GB   | 2         | 1.59%   |
| ru_UA   | 1         | 0.79%   |
| nl_NL   | 1         | 0.79%   |
| en_150  | 1         | 0.79%   |
| de_DE   | 1         | 0.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 67        | 53.17%  |
| BIOS | 59        | 46.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 89        | 70.63%  |
| Unknown | 16        | 12.7%   |
| Btrfs   | 11        | 8.73%   |
| Overlay | 8         | 6.35%   |
| Xfs     | 2         | 1.59%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 55        | 43.31%  |
| GPT     | 48        | 37.8%   |
| MBR     | 24        | 18.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 117       | 92.86%  |
| Yes       | 9         | 7.14%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 93        | 73.81%  |
| Yes       | 33        | 26.19%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 28        | 22.4%   |
| Lenovo              | 27        | 21.6%   |
| Hewlett-Packard     | 26        | 20.8%   |
| Dell                | 12        | 9.6%    |
| Acer                | 9         | 7.2%    |
| Toshiba             | 4         | 3.2%    |
| Timi                | 4         | 3.2%    |
| Samsung Electronics | 4         | 3.2%    |
| Valve               | 1         | 0.8%    |
| System76            | 1         | 0.8%    |
| Sony                | 1         | 0.8%    |
| MSI                 | 1         | 0.8%    |
| Jumper              | 1         | 0.8%    |
| HUAWEI              | 1         | 0.8%    |
| Google              | 1         | 0.8%    |
| Gateway             | 1         | 0.8%    |
| Chuwi               | 1         | 0.8%    |
| Apple               | 1         | 0.8%    |
| Unknown             | 1         | 0.8%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Timi TM1701                                 | 3         | 2.4%    |
| ASUS VivoBook_ASUSLaptop X521IA_D533IA      | 3         | 2.4%    |
| Samsung RV413/RV513                         | 2         | 1.6%    |
| Lenovo Legion Y530-15ICH 81FV               | 2         | 1.6%    |
| HP ProBook 450 G7                           | 2         | 1.6%    |
| HP Compaq Presario CQ60                     | 2         | 1.6%    |
| ASUS VivoBook S15 X510UF                    | 2         | 1.6%    |
| Unknown                                     | 2         | 1.6%    |
| Valve Jupiter                               | 1         | 0.8%    |
| Toshiba TECRA Z40-B                         | 1         | 0.8%    |
| Toshiba Satellite Pro S300L                 | 1         | 0.8%    |
| Toshiba Satellite C55D-A                    | 1         | 0.8%    |
| Toshiba Satellite A210                      | 1         | 0.8%    |
| Timi A35S                                   | 1         | 0.8%    |
| System76 Adder WS                           | 1         | 0.8%    |
| Sony VPCEB1J8E                              | 1         | 0.8%    |
| Samsung R517/R717                           | 1         | 0.8%    |
| Samsung 300E4C/300E5C/300E7C                | 1         | 0.8%    |
| MSI CR610                                   | 1         | 0.8%    |
| Lenovo Y520-15IKBN 80WK                     | 1         | 0.8%    |
| Lenovo V580 20147                           | 1         | 0.8%    |
| Lenovo ThinkPad Yoga 11e 3rd Gen 20G8S0MG00 | 1         | 0.8%    |
| Lenovo ThinkPad X240 20AL0067RT             | 1         | 0.8%    |
| Lenovo ThinkPad X131e 33711T0               | 1         | 0.8%    |
| Lenovo ThinkPad X1 Carbon 5th 20HR002MMX    | 1         | 0.8%    |
| Lenovo ThinkPad W520 4282BA9                | 1         | 0.8%    |
| Lenovo ThinkPad T440 20B7S1N809             | 1         | 0.8%    |
| Lenovo ThinkPad E15 Gen 3 20YG004BRT        | 1         | 0.8%    |
| Lenovo ThinkPad E15 Gen 2 20TD003TRT        | 1         | 0.8%    |
| Lenovo ThinkPad E15 Gen 2 20TD002NRA        | 1         | 0.8%    |
| Lenovo Legion 5 Pro 16ITH6H 82JD            | 1         | 0.8%    |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 0.8%    |
| Lenovo IdeaPad L340-15API 81LW              | 1         | 0.8%    |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY        | 1         | 0.8%    |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2         | 1         | 0.8%    |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5            | 1         | 0.8%    |
| Lenovo IdeaPad 5 15ARE05 81YQ               | 1         | 0.8%    |
| Lenovo IdeaPad 330S-15ARR 81FB              | 1         | 0.8%    |
| Lenovo IdeaPad 330S-14IKB 81F4              | 1         | 0.8%    |
| Lenovo IdeaPad 330-15IKB 81DE               | 1         | 0.8%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 11        | 8.8%    |
| Lenovo ThinkPad    | 9         | 7.2%    |
| ASUS VivoBook      | 8         | 6.4%    |
| HP ProBook         | 6         | 4.8%    |
| Acer Aspire        | 6         | 4.8%    |
| Dell Latitude      | 5         | 4%      |
| Dell Inspiron      | 5         | 4%      |
| Lenovo Legion      | 4         | 3.2%    |
| HP Pavilion        | 4         | 3.2%    |
| HP EliteBook       | 4         | 3.2%    |
| HP Compaq          | 4         | 3.2%    |
| Toshiba Satellite  | 3         | 2.4%    |
| Timi TM1701        | 3         | 2.4%    |
| Samsung RV413      | 2         | 1.6%    |
| HP Laptop          | 2         | 1.6%    |
| HP ENVY            | 2         | 1.6%    |
| ASUS ZenBook       | 2         | 1.6%    |
| Unknown            | 2         | 1.6%    |
| Valve Jupiter      | 1         | 0.8%    |
| Toshiba TECRA      | 1         | 0.8%    |
| Timi A35S          | 1         | 0.8%    |
| System76 Adder     | 1         | 0.8%    |
| Sony VPCEB1J8E     | 1         | 0.8%    |
| Samsung R517       | 1         | 0.8%    |
| Samsung 300E4C     | 1         | 0.8%    |
| MSI CR610          | 1         | 0.8%    |
| Lenovo Y520-15IKBN | 1         | 0.8%    |
| Lenovo V580        | 1         | 0.8%    |
| Lenovo G710        | 1         | 0.8%    |
| Jumper EZbook      | 1         | 0.8%    |
| HUAWEI NBLK-WAX9X  | 1         | 0.8%    |
| HP ZBook           | 1         | 0.8%    |
| HP 635             | 1         | 0.8%    |
| HP 550             | 1         | 0.8%    |
| Google Droid       | 1         | 0.8%    |
| Gateway NV55S      | 1         | 0.8%    |
| Dell XPS           | 1         | 0.8%    |
| Dell Vostro        | 1         | 0.8%    |
| Chuwi GemiBook     | 1         | 0.8%    |
| ASUS X555LJ        | 1         | 0.8%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 16        | 12.8%   |
| 2018 | 14        | 11.2%   |
| 2021 | 13        | 10.4%   |
| 2011 | 13        | 10.4%   |
| 2017 | 12        | 9.6%    |
| 2012 | 10        | 8%      |
| 2020 | 8         | 6.4%    |
| 2013 | 7         | 5.6%    |
| 2016 | 6         | 4.8%    |
| 2015 | 6         | 4.8%    |
| 2014 | 4         | 3.2%    |
| 2009 | 4         | 3.2%    |
| 2008 | 4         | 3.2%    |
| 2022 | 3         | 2.4%    |
| 2010 | 3         | 2.4%    |
| 2007 | 2         | 1.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 125       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 117       | 93.6%   |
| Enabled  | 8         | 6.4%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 124       | 99.2%   |
| Yes  | 1         | 0.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 34        | 27.2%   |
| 4.01-8.0    | 33        | 26.4%   |
| 8.01-16.0   | 24        | 19.2%   |
| 16.01-24.0  | 16        | 12.8%   |
| 32.01-64.0  | 7         | 5.6%    |
| 1.01-2.0    | 5         | 4%      |
| 2.01-3.0    | 4         | 3.2%    |
| 24.01-32.0  | 1         | 0.8%    |
| 64.01-256.0 | 1         | 0.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 47        | 35.61%  |
| 2.01-3.0   | 26        | 19.7%   |
| 4.01-8.0   | 21        | 15.91%  |
| 0.51-1.0   | 17        | 12.88%  |
| 3.01-4.0   | 14        | 10.61%  |
| 8.01-16.0  | 4         | 3.03%   |
| 16.01-24.0 | 2         | 1.52%   |
| 24.01-32.0 | 1         | 0.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 99        | 79.2%   |
| 2      | 21        | 16.8%   |
| 3      | 4         | 3.2%    |
| 0      | 1         | 0.8%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 90        | 72%     |
| Yes       | 35        | 28%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 80.95%  |
| No        | 24        | 19.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 99.2%   |
| No        | 1         | 0.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 75.4%   |
| No        | 31        | 24.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Moldova | 125       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Chisinau        | 82        | 64.06%  |
| Tiraspol        | 15        | 11.72%  |
| Bălţi         | 4         | 3.13%   |
| Straseni        | 3         | 2.34%   |
| Tighina         | 2         | 1.56%   |
| Soroca          | 2         | 1.56%   |
| Hincesti        | 2         | 1.56%   |
| Zaicana         | 1         | 0.78%   |
| Tvardița       | 1         | 0.78%   |
| Soldanesti      | 1         | 0.78%   |
| Sofia           | 1         | 0.78%   |
| Rautel          | 1         | 0.78%   |
| Prajila         | 1         | 0.78%   |
| Pociumbeni      | 1         | 0.78%   |
| Nisporeni       | 1         | 0.78%   |
| Ialoveni        | 1         | 0.78%   |
| Gangura         | 1         | 0.78%   |
| Floresti        | 1         | 0.78%   |
| Floreni         | 1         | 0.78%   |
| Donduseni       | 1         | 0.78%   |
| Criuleni        | 1         | 0.78%   |
| Crasnoarmeiscoe | 1         | 0.78%   |
| Cenac           | 1         | 0.78%   |
| Căușeni       | 1         | 0.78%   |
| Cahul           | 1         | 0.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 29        | 36     | 19.46%  |
| WDC                 | 16        | 17     | 10.74%  |
| Toshiba             | 16        | 20     | 10.74%  |
| Seagate             | 14        | 18     | 9.4%    |
| Hitachi             | 11        | 12     | 7.38%   |
| SanDisk             | 9         | 9      | 6.04%   |
| Kingston            | 9         | 11     | 6.04%   |
| Unknown             | 5         | 5      | 3.36%   |
| SK hynix            | 5         | 5      | 3.36%   |
| Micron Technology   | 5         | 7      | 3.36%   |
| Intel               | 4         | 6      | 2.68%   |
| HGST                | 3         | 3      | 2.01%   |
| Netac               | 2         | 2      | 1.34%   |
| Fujitsu             | 2         | 2      | 1.34%   |
| A-DATA Technology   | 2         | 2      | 1.34%   |
| ZOTAC               | 1         | 3      | 0.67%   |
| UMIS                | 1         | 1      | 0.67%   |
| Transcend           | 1         | 1      | 0.67%   |
| Solid State Storage | 1         | 1      | 0.67%   |
| PNY                 | 1         | 1      | 0.67%   |
| Phison              | 1         | 2      | 0.67%   |
| OCZ                 | 1         | 1      | 0.67%   |
| O2 Micro            | 1         | 1      | 0.67%   |
| LITEONIT            | 1         | 1      | 0.67%   |
| Lenovo              | 1         | 1      | 0.67%   |
| KIOXIA              | 1         | 1      | 0.67%   |
| Intenso             | 1         | 1      | 0.67%   |
| GOODRAM             | 1         | 1      | 0.67%   |
| Crucial             | 1         | 1      | 0.67%   |
| China               | 1         | 1      | 0.67%   |
| ASMT                | 1         | 1      | 0.67%   |
| Apacer              | 1         | 1      | 0.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB        | 6         | 3.97%   |
| Toshiba MQ01ABD100 1TB              | 4         | 2.65%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 2.65%   |
| Kingston SHFS37A120G 120GB SSD      | 4         | 2.65%   |
| Toshiba MQ04ABF100 1TB              | 3         | 1.99%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 1.99%   |
| SanDisk NVMe SSD Drive 512GB        | 3         | 1.99%   |
| Samsung MZVLW256HEHP-00000 256GB    | 3         | 1.99%   |
| Hitachi HTS543232A7A384 320GB       | 3         | 1.99%   |
| WDC WD10SPZX-24Z10T0 1TB            | 2         | 1.32%   |
| Unknown MMC Card  64GB              | 2         | 1.32%   |
| Toshiba MQ01ACF032 320GB            | 2         | 1.32%   |
| Toshiba MQ01ABF050 500GB            | 2         | 1.32%   |
| SK hynix NVMe SSD Drive 256GB       | 2         | 1.32%   |
| Seagate ST9500325AS 500GB           | 2         | 1.32%   |
| Samsung SSD 860 EVO 500GB           | 2         | 1.32%   |
| Netac SSD 256GB                     | 2         | 1.32%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 2         | 1.32%   |
| Hitachi HTS547575A9E384 752GB       | 2         | 1.32%   |
| ZOTAC ZTSSD-S11-240G-P 240GB        | 1         | 0.66%   |
| WDC WDS512G1X0C-00ENX0 512GB        | 1         | 0.66%   |
| WDC WD5000LPVX-80V0TT0 500GB        | 1         | 0.66%   |
| WDC WD5000LPVX-75V0TT0 500GB        | 1         | 0.66%   |
| WDC WD5000LPCX-75VHAT1 500GB        | 1         | 0.66%   |
| WDC WD5000BPVT-08HXZT3 500GB        | 1         | 0.66%   |
| WDC WD5000BEVT-22A0RT0 500GB        | 1         | 0.66%   |
| WDC WD3200BPVT-80JJ5T0 320GB        | 1         | 0.66%   |
| WDC WD3200BEVT-63ZCT0 320GB         | 1         | 0.66%   |
| WDC WD3200BEVT-22A23T0 320GB        | 1         | 0.66%   |
| WDC WD3200BEVT-00ZCT0 320GB         | 1         | 0.66%   |
| WDC WD1600BEVS-07RST0 160GB         | 1         | 0.66%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 0.66%   |
| WDC WD10SPZX-22Z10T1 1TB            | 1         | 0.66%   |
| WDC WD10SPSX-60A6WT0 1TB            | 1         | 0.66%   |
| Unknown TO  64GB                    | 1         | 0.66%   |
| Unknown SD/MMC/MS PRO 64GB          | 1         | 0.66%   |
| Unknown MMC Card  128GB             | 1         | 0.66%   |
| UMIS RPJTJ512MEE1OWX 512GB          | 1         | 0.66%   |
| Transcend TS120GMTS420S 120GB SSD   | 1         | 0.66%   |
| Toshiba THNSNJ128GMCU 128GB SSD     | 1         | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 15        | 16     | 24.59%  |
| Seagate             | 14        | 18     | 22.95%  |
| Toshiba             | 13        | 17     | 21.31%  |
| Hitachi             | 11        | 12     | 18.03%  |
| HGST                | 3         | 3      | 4.92%   |
| Fujitsu             | 2         | 2      | 3.28%   |
| Unknown             | 1         | 1      | 1.64%   |
| Samsung Electronics | 1         | 1      | 1.64%   |
| ASMT                | 1         | 1      | 1.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 12     | 24.32%  |
| Kingston            | 7         | 9      | 18.92%  |
| SanDisk             | 4         | 4      | 10.81%  |
| Netac               | 2         | 2      | 5.41%   |
| Micron Technology   | 2         | 2      | 5.41%   |
| ZOTAC               | 1         | 3      | 2.7%    |
| Transcend           | 1         | 1      | 2.7%    |
| Toshiba             | 1         | 1      | 2.7%    |
| PNY                 | 1         | 1      | 2.7%    |
| OCZ                 | 1         | 1      | 2.7%    |
| LITEONIT            | 1         | 1      | 2.7%    |
| Intenso             | 1         | 1      | 2.7%    |
| Intel               | 1         | 1      | 2.7%    |
| GOODRAM             | 1         | 1      | 2.7%    |
| Crucial             | 1         | 1      | 2.7%    |
| China               | 1         | 1      | 2.7%    |
| Apacer              | 1         | 1      | 2.7%    |
| A-DATA Technology   | 1         | 1      | 2.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 61        | 71     | 42.07%  |
| NVMe | 45        | 56     | 31.03%  |
| SSD  | 35        | 44     | 24.14%  |
| MMC  | 4         | 4      | 2.76%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 87        | 113    | 63.04%  |
| NVMe | 45        | 56     | 32.61%  |
| MMC  | 4         | 4      | 2.9%    |
| SAS  | 2         | 2      | 1.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 66        | 83     | 70.97%  |
| 0.51-1.0   | 26        | 31     | 27.96%  |
| 1.01-2.0   | 1         | 1      | 1.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 42        | 31.82%  |
| 101-250    | 40        | 30.3%   |
| 501-1000   | 19        | 14.39%  |
| 51-100     | 11        | 8.33%   |
| 1-20       | 7         | 5.3%    |
| 1001-2000  | 5         | 3.79%   |
| Unknown    | 5         | 3.79%   |
| 21-50      | 3         | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 60        | 44.12%  |
| 21-50    | 22        | 16.18%  |
| 51-100   | 19        | 13.97%  |
| 101-250  | 15        | 11.03%  |
| 251-500  | 10        | 7.35%   |
| 501-1000 | 5         | 3.68%   |
| Unknown  | 5         | 3.68%   |

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
| Works    | 59        | 84     | 45.38%  |
| Detected | 55        | 73     | 42.31%  |
| Malfunc  | 15        | 17     | 11.54%  |
| Failed   | 1         | 1      | 0.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 78        | 50.32%  |
| AMD                            | 31        | 20%     |
| Samsung Electronics            | 19        | 12.26%  |
| SanDisk                        | 6         | 3.87%   |
| SK hynix                       | 5         | 3.23%   |
| Micron Technology              | 3         | 1.94%   |
| Toshiba America Info Systems   | 2         | 1.29%   |
| Nvidia                         | 2         | 1.29%   |
| Kingston Technology Company    | 2         | 1.29%   |
| Union Memory (Shenzhen)        | 1         | 0.65%   |
| Solid State Storage Technology | 1         | 0.65%   |
| Phison Electronics             | 1         | 0.65%   |
| O2 Micro                       | 1         | 0.65%   |
| Lenovo                         | 1         | 0.65%   |
| KIOXIA                         | 1         | 0.65%   |
| ADATA Technology               | 1         | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 22        | 13.25%  |
| Samsung NVMe SSD Controller 980                                                  | 11        | 6.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 6.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 4.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 4.22%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 3.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 3.61%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 3.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 2.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 2.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 2.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.81%   |
| Micron NVMe Storage Controller                                                   | 3         | 1.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.81%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 1.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.81%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.2%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 2         | 1.2%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 2         | 1.2%    |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 2         | 1.2%    |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 2         | 1.2%    |
| Intel SSD 660P Series                                                            | 2         | 1.2%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.2%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 1.2%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.6%    |
| Solid State Storage Non-Volatile memory controller                               | 1         | 0.6%    |
| SK hynix Non-Volatile memory controller                                          | 1         | 0.6%    |
| SK hynix BC511                                                                   | 1         | 0.6%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.6%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.6%    |
| SanDisk WD Black NVMe SSD                                                        | 1         | 0.6%    |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.6%    |
| SanDisk NVMe Controller                                                          | 1         | 0.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 99        | 61.49%  |
| NVMe | 45        | 27.95%  |
| IDE  | 10        | 6.21%   |
| RAID | 7         | 4.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 86        | 68.8%   |
| AMD    | 39        | 31.2%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 3.2%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.4%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 2.4%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 2.4%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 2.4%    |
| AMD E1-1200 APU with Radeon HD Graphics       | 3         | 2.4%    |
| AMD E-450 APU with Radeon HD Graphics         | 3         | 2.4%    |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 1.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.6%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.6%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.6%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.6%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.6%    |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 1.6%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.6%    |
| Intel Celeron CPU N3450 @ 1.10GHz             | 2         | 1.6%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.6%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.6%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.6%    |
| AMD E-300 APU with Radeon HD Graphics         | 2         | 1.6%    |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.8%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.8%    |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.8%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.8%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.8%    |
| Intel Pentium CPU B980 @ 2.40GHz              | 1         | 0.8%    |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.8%    |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.8%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.8%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.8%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.8%    |
| Intel Core i7-2820QM CPU @ 2.30GHz            | 1         | 0.8%    |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 0.8%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.8%    |
| Intel Core i5-8400H CPU @ 2.50GHz             | 1         | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 27        | 21.6%   |
| Intel Core i7                  | 18        | 14.4%   |
| Intel Core i3                  | 13        | 10.4%   |
| Intel Celeron                  | 11        | 8.8%    |
| AMD Ryzen 5                    | 9         | 7.2%    |
| AMD Ryzen 7                    | 7         | 5.6%    |
| Intel Pentium                  | 6         | 4.8%    |
| Other                          | 5         | 4%      |
| AMD E                          | 5         | 4%      |
| Intel Core 2 Duo               | 3         | 2.4%    |
| AMD E1                         | 3         | 2.4%    |
| Intel Pentium Silver           | 2         | 1.6%    |
| AMD Sempron                    | 2         | 1.6%    |
| AMD A4                         | 2         | 1.6%    |
| AMD A10                        | 2         | 1.6%    |
| Intel Pentium Dual-Core        | 1         | 0.8%    |
| Intel Core i9                  | 1         | 0.8%    |
| AMD V140                       | 1         | 0.8%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.8%    |
| AMD Ryzen 9                    | 1         | 0.8%    |
| AMD Ryzen 5 PRO                | 1         | 0.8%    |
| AMD Ryzen 3                    | 1         | 0.8%    |
| AMD Athlon 64 X2               | 1         | 0.8%    |
| AMD Athlon                     | 1         | 0.8%    |
| AMD A6                         | 1         | 0.8%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 60        | 48%     |
| 4       | 43        | 34.4%   |
| 6       | 10        | 8%      |
| 8       | 9         | 7.2%    |
| 1       | 2         | 1.6%    |
| Unknown | 1         | 0.8%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 125       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 79        | 63.2%   |
| 1       | 45        | 36%     |
| Unknown | 1         | 0.8%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 122       | 97.6%   |
| Unknown        | 3         | 2.4%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 17.46%  |
| 0x806ea    | 9         | 7.14%   |
| 0x206a7    | 8         | 6.35%   |
| 0x05000119 | 8         | 6.35%   |
| 0x806ec    | 6         | 4.76%   |
| 0x906ea    | 4         | 3.17%   |
| 0x406e3    | 4         | 3.17%   |
| 0x40651    | 4         | 3.17%   |
| 0x306c3    | 4         | 3.17%   |
| 0x08600106 | 4         | 3.17%   |
| 0x806e9    | 3         | 2.38%   |
| 0x706a1    | 3         | 2.38%   |
| 0x506c9    | 3         | 2.38%   |
| 0x306d4    | 3         | 2.38%   |
| 0x306a9    | 3         | 2.38%   |
| 0x0a50000c | 3         | 2.38%   |
| 0xa0652    | 2         | 1.59%   |
| 0x806c1    | 2         | 1.59%   |
| 0x706e5    | 2         | 1.59%   |
| 0x406c4    | 2         | 1.59%   |
| 0x30678    | 2         | 1.59%   |
| 0x08608103 | 2         | 1.59%   |
| 0x08108109 | 2         | 1.59%   |
| 0x08108102 | 2         | 1.59%   |
| 0x06001119 | 2         | 1.59%   |
| 0x03000027 | 2         | 1.59%   |
| 0x02000057 | 2         | 1.59%   |
| 0x906e9    | 1         | 0.79%   |
| 0x806d1    | 1         | 0.79%   |
| 0x706a8    | 1         | 0.79%   |
| 0x6fd      | 1         | 0.79%   |
| 0x6fb      | 1         | 0.79%   |
| 0x406c3    | 1         | 0.79%   |
| 0x20652    | 1         | 0.79%   |
| 0x1067a    | 1         | 0.79%   |
| 0x0a50000b | 1         | 0.79%   |
| 0x0810100b | 1         | 0.79%   |
| 0x02000032 | 1         | 0.79%   |
| 0x010000c8 | 1         | 0.79%   |
| 0x0100009f | 1         | 0.79%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 28        | 22.4%   |
| SandyBridge     | 11        | 8.8%    |
| Haswell         | 9         | 7.2%    |
| Bobcat          | 8         | 6.4%    |
| Zen 2           | 7         | 5.6%    |
| Zen+            | 5         | 4%      |
| Silvermont      | 5         | 4%      |
| Goldmont plus   | 5         | 4%      |
| Zen 3           | 4         | 3.2%    |
| Skylake         | 4         | 3.2%    |
| IceLake         | 4         | 3.2%    |
| Unknown         | 4         | 3.2%    |
| TigerLake       | 3         | 2.4%    |
| K8 & K10 hybrid | 3         | 2.4%    |
| IvyBridge       | 3         | 2.4%    |
| Goldmont        | 3         | 2.4%    |
| Core            | 3         | 2.4%    |
| Broadwell       | 3         | 2.4%    |
| Piledriver      | 2         | 1.6%    |
| K10 Llano       | 2         | 1.6%    |
| K10             | 2         | 1.6%    |
| CometLake       | 2         | 1.6%    |
| Zen             | 1         | 0.8%    |
| Westmere        | 1         | 0.8%    |
| Puma            | 1         | 0.8%    |
| Penryn          | 1         | 0.8%    |
| K8 Hammer       | 1         | 0.8%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 84        | 53.16%  |
| AMD    | 40        | 25.32%  |
| Nvidia | 34        | 21.52%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 6.83%   |
| Intel UHD Graphics 620                                                                   | 9         | 5.59%   |
| AMD Renoir                                                                               | 7         | 4.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 3.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 3.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 3.11%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 3.11%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 2.48%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.48%   |
| Intel HD Graphics 620                                                                    | 4         | 2.48%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.48%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 2.48%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.86%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.86%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.86%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.86%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.86%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.86%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 1.86%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 3         | 1.86%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 1.86%   |
| Nvidia TU117M                                                                            | 2         | 1.24%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.24%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 1.24%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 2         | 1.24%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.24%   |
| Intel HD Graphics 500                                                                    | 2         | 1.24%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.24%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 1.24%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.24%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 1.24%   |
| AMD Lucienne                                                                             | 2         | 1.24%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.62%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.62%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.62%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 55        | 44%     |
| 1 x AMD        | 30        | 24%     |
| Intel + Nvidia | 25        | 20%     |
| AMD + Nvidia   | 5         | 4%      |
| 1 x Nvidia     | 4         | 3.2%    |
| Intel + AMD    | 3         | 2.4%    |
| 2 x AMD        | 2         | 1.6%    |
| Other          | 1         | 0.8%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 106       | 82.81%  |
| Proprietary | 17        | 13.28%  |
| Unknown     | 5         | 3.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 51.94%  |
| 0.01-0.5   | 27        | 20.93%  |
| 1.01-2.0   | 24        | 18.6%   |
| 3.01-4.0   | 8         | 6.2%    |
| 0.51-1.0   | 2         | 1.55%   |
| 7.01-8.0   | 1         | 0.78%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 32        | 22.54%  |
| Chimei Innolux          | 22        | 15.49%  |
| LG Display              | 21        | 14.79%  |
| BOE                     | 14        | 9.86%   |
| Samsung Electronics     | 12        | 8.45%   |
| Philips                 | 8         | 5.63%   |
| Dell                    | 5         | 3.52%   |
| Chi Mei Optoelectronics | 5         | 3.52%   |
| InfoVision              | 4         | 2.82%   |
| Sharp                   | 3         | 2.11%   |
| Lenovo                  | 3         | 2.11%   |
| AOC                     | 3         | 2.11%   |
| PANDA                   | 2         | 1.41%   |
| Goldstar                | 2         | 1.41%   |
| CSO                     | 2         | 1.41%   |
| Valve                   | 1         | 0.7%    |
| ITE                     | 1         | 0.7%    |
| BenQ                    | 1         | 0.7%    |
| Apple                   | 1         | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 2.8%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 4         | 2.8%    |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 3         | 2.1%    |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 3         | 2.1%    |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 3         | 2.1%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 2.1%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 2.1%    |
| Philips 223E PHLC049 1920x1080 476x268mm 21.5-inch                    | 2         | 1.4%    |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 2         | 1.4%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.4%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch       | 2         | 1.4%    |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                 | 2         | 1.4%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 1.4%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.7%    |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.7%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.7%    |
| Sharp LCD Monitor SHP13CF 1280x800 331x207mm 15.4-inch                | 1         | 0.7%    |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch     | 1         | 0.7%    |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1         | 0.7%    |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch   | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC5842 1366x768 309x174mm 14.0-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch | 1         | 0.7%    |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch              | 1         | 0.7%    |
| Philips PHL 243S7 PHL090F 1920x1080 527x296mm 23.8-inch               | 1         | 0.7%    |
| Philips PHL 234E5 PHLC0C7 1920x1080 509x286mm 23.0-inch               | 1         | 0.7%    |
| Philips PHL 223V7 PHLC154 1920x1080 480x270mm 21.7-inch               | 1         | 0.7%    |
| Philips 247ELH PHLC085 1920x1080 521x293mm 23.5-inch                  | 1         | 0.7%    |
| Philips 227E4LH PHLC0AC 1920x1080 477x268mm 21.5-inch                 | 1         | 0.7%    |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.7%    |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.7%    |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 1         | 0.7%    |
| LG Display LCD Monitor LGD06E0 1920x1080 344x194mm 15.5-inch          | 1         | 0.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 58        | 44.27%  |
| 1366x768 (WXGA)    | 45        | 34.35%  |
| 1600x900 (HD+)     | 8         | 6.11%   |
| 2560x1440 (QHD)    | 6         | 4.58%   |
| 1280x800 (WXGA)    | 4         | 3.05%   |
| 3840x2160 (4K)     | 3         | 2.29%   |
| 2560x1600          | 2         | 1.53%   |
| 800x1280           | 1         | 0.76%   |
| 3456x2160          | 1         | 0.76%   |
| 2160x1440          | 1         | 0.76%   |
| 1680x1050 (WSXGA+) | 1         | 0.76%   |
| 1280x1024 (SXGA)   | 1         | 0.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 87        | 60.84%  |
| 14     | 10        | 6.99%   |
| 13     | 7         | 4.9%    |
| 17     | 6         | 4.2%    |
| 27     | 5         | 3.5%    |
| 24     | 5         | 3.5%    |
| 23     | 5         | 3.5%    |
| 21     | 5         | 3.5%    |
| 11     | 4         | 2.8%    |
| 16     | 2         | 1.4%    |
| 12     | 2         | 1.4%    |
| 72     | 1         | 0.7%    |
| 31     | 1         | 0.7%    |
| 22     | 1         | 0.7%    |
| 19     | 1         | 0.7%    |
| 7      | 1         | 0.7%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 101       | 71.13%  |
| 501-600     | 13        | 9.15%   |
| 201-300     | 10        | 7.04%   |
| 351-400     | 8         | 5.63%   |
| 401-500     | 6         | 4.23%   |
| 601-700     | 2         | 1.41%   |
| 1501-2000   | 1         | 0.7%    |
| 1-100       | 1         | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 111       | 90.98%  |
| 16/10 | 8         | 6.56%   |
| 5/4   | 1         | 0.82%   |
| 3/2   | 1         | 0.82%   |
| 0.67  | 1         | 0.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 87        | 61.27%  |
| 81-90          | 15        | 10.56%  |
| 201-250        | 13        | 9.15%   |
| 301-350        | 5         | 3.52%   |
| 51-60          | 4         | 2.82%   |
| 121-130        | 4         | 2.82%   |
| 151-200        | 3         | 2.11%   |
| 71-80          | 2         | 1.41%   |
| 61-70          | 2         | 1.41%   |
| 131-140        | 2         | 1.41%   |
| 111-120        | 2         | 1.41%   |
| More than 1000 | 1         | 0.7%    |
| 351-500        | 1         | 0.7%    |
| 1-40           | 1         | 0.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 63        | 45.32%  |
| 101-120       | 48        | 34.53%  |
| 51-100        | 18        | 12.95%  |
| 161-240       | 7         | 5.04%   |
| More than 240 | 2         | 1.44%   |
| 1-50          | 1         | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 104       | 81.89%  |
| 2     | 22        | 17.32%  |
| 0     | 1         | 0.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 80        | 40%     |
| Intel                             | 47        | 23.5%   |
| Qualcomm Atheros                  | 38        | 19%     |
| Broadcom                          | 12        | 6%      |
| Xiaomi                            | 3         | 1.5%    |
| Ralink                            | 3         | 1.5%    |
| MediaTek                          | 3         | 1.5%    |
| Broadcom Limited                  | 3         | 1.5%    |
| Nvidia                            | 2         | 1%      |
| TP-Link                           | 1         | 0.5%    |
| Sierra Wireless                   | 1         | 0.5%    |
| OnePlus Technology (Shenzhen)     | 1         | 0.5%    |
| Marvell Technology Group          | 1         | 0.5%    |
| JMicron Technology                | 1         | 0.5%    |
| ICS Advent                        | 1         | 0.5%    |
| Huawei Technologies               | 1         | 0.5%    |
| Hewlett-Packard                   | 1         | 0.5%    |
| Ericsson Business Mobile Networks | 1         | 0.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 49        | 20.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 19        | 8.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 3.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 3.42%   |
| Intel Wireless 8265 / 8275                                              | 8         | 3.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.14%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 3         | 1.28%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.28%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.28%   |
| Intel Wireless 7260                                                     | 3         | 1.28%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.28%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 1.28%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.28%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.85%   |
| Nvidia MCP77 Ethernet                                                   | 2         | 0.85%   |
| Intel Wireless 8260                                                     | 2         | 0.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 0.85%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 2         | 0.85%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 0.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.43%   |
| Sierra Wireless EM7455                                                  | 1         | 0.43%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.43%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.43%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.43%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 45        | 35.43%  |
| Qualcomm Atheros      | 36        | 28.35%  |
| Realtek Semiconductor | 28        | 22.05%  |
| Broadcom              | 9         | 7.09%   |
| Ralink                | 3         | 2.36%   |
| MediaTek              | 3         | 2.36%   |
| TP-Link               | 1         | 0.79%   |
| Sierra Wireless       | 1         | 0.79%   |
| Broadcom Limited      | 1         | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 7.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 7.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 6.3%    |
| Intel Wireless 8265 / 8275                                              | 8         | 6.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 5.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 3.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 3.94%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 3.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 3.15%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 2.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.36%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 2.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 2.36%   |
| Intel Wireless 7260                                                     | 3         | 2.36%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 2.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.36%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.57%   |
| Intel Wireless 8260                                                     | 2         | 1.57%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.57%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.57%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.79%   |
| Sierra Wireless EM7455                                                  | 1         | 0.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.79%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.79%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.79%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.79%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]        | 1         | 0.79%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.79%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.79%   |
| Intel Wireless 7265                                                     | 1         | 0.79%   |
| Intel Wireless 3165                                                     | 1         | 0.79%   |
| Intel Wireless 3160                                                     | 1         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 69        | 66.35%  |
| Intel                    | 16        | 15.38%  |
| Broadcom                 | 4         | 3.85%   |
| Xiaomi                   | 3         | 2.88%   |
| Qualcomm Atheros         | 3         | 2.88%   |
| Nvidia                   | 2         | 1.92%   |
| Broadcom Limited         | 2         | 1.92%   |
| Marvell Technology Group | 1         | 0.96%   |
| JMicron Technology       | 1         | 0.96%   |
| ICS Advent               | 1         | 0.96%   |
| Huawei Technologies      | 1         | 0.96%   |
| Hewlett-Packard          | 1         | 0.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 49        | 46.67%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 19        | 18.1%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 2.86%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 2.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 1.9%    |
| Nvidia MCP77 Ethernet                                                          | 2         | 1.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 1.9%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.95%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.95%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.95%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.95%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.95%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.95%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.95%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.95%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.95%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.95%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.95%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.95%   |
| Intel Ethernet Connection (10) I219-LM                                         | 1         | 0.95%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.95%   |
| Intel 82562GT 10/100 Network Connection                                        | 1         | 0.95%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.95%   |
| Huawei E353/E3131                                                              | 1         | 0.95%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 1         | 0.95%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.95%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 1         | 0.95%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 0.95%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 0.95%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 124       | 54.39%  |
| Ethernet | 102       | 44.74%  |
| Modem    | 1         | 0.44%   |
| Unknown  | 1         | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 75.97%  |
| Ethernet | 31        | 24.03%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 95        | 76%     |
| 1     | 30        | 24%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 121       | 96.8%   |
| Yes  | 4         | 3.2%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 37.89%  |
| IMC Networks                    | 15        | 15.79%  |
| Qualcomm Atheros Communications | 13        | 13.68%  |
| Realtek Semiconductor           | 11        | 11.58%  |
| Lite-On Technology              | 5         | 5.26%   |
| Broadcom                        | 5         | 5.26%   |
| Foxconn / Hon Hai               | 4         | 4.21%   |
| Toshiba                         | 1         | 1.05%   |
| Realtek                         | 1         | 1.05%   |
| Ralink Technology               | 1         | 1.05%   |
| Hewlett-Packard                 | 1         | 1.05%   |
| Dell                            | 1         | 1.05%   |
| Apple                           | 1         | 1.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 15        | 15.79%  |
| Realtek Bluetooth Radio                                                             | 9         | 9.47%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 8.42%   |
| Intel AX201 Bluetooth                                                               | 8         | 8.42%   |
| IMC Networks Bluetooth Radio                                                        | 7         | 7.37%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 6.32%   |
| Intel AX200 Bluetooth                                                               | 4         | 4.21%   |
| IMC Networks Bluetooth Device                                                       | 4         | 4.21%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 3.16%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 2.11%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 2.11%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 2.11%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 2.11%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 2.11%   |
| Broadcom BCM20702A0                                                                 | 2         | 2.11%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 1.05%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.05%   |
| Ralink CSR BS8510                                                                   | 1         | 1.05%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.05%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.05%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 1.05%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.05%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.05%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 1.05%   |
| IMC Networks Wireless_Device                                                        | 1         | 1.05%   |
| IMC Networks Bluetooth Module                                                       | 1         | 1.05%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.05%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.05%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.05%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.05%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 1.05%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 1.05%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 1.05%   |
| Apple Bluetooth Host Controller                                                     | 1         | 1.05%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 86        | 60.99%  |
| AMD         | 37        | 26.24%  |
| Nvidia      | 15        | 10.64%  |
| Logitech    | 2         | 1.42%   |
| Plantronics | 1         | 0.71%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 19        | 10.33%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 9.24%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 12        | 6.52%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 4.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 4.35%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 4.35%   |
| AMD FCH Azalia Controller                                                                         | 8         | 4.35%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 3.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3.26%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 2.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 2.72%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 2.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.17%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.17%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.63%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.63%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.63%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.63%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 1.09%   |
| Logitech H600 [Wireless Headset]                                                                  | 2         | 1.09%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.09%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.09%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 1.09%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 1.09%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 1.09%   |
| Plantronics Audio 622 USB                                                                         | 1         | 0.54%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.54%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.54%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 1         | 0.54%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 35.23%  |
| SK hynix            | 17        | 19.32%  |
| Micron Technology   | 7         | 7.95%   |
| Kingston            | 7         | 7.95%   |
| Unknown             | 6         | 6.82%   |
| GOODRAM             | 4         | 4.55%   |
| Unknown (ABCD)      | 2         | 2.27%   |
| Transcend           | 2         | 2.27%   |
| Ramaxel Technology  | 2         | 2.27%   |
| Elpida              | 2         | 2.27%   |
| Unifosa             | 1         | 1.14%   |
| Nanya Technology    | 1         | 1.14%   |
| Crucial             | 1         | 1.14%   |
| Corsair             | 1         | 1.14%   |
| Axiom               | 1         | 1.14%   |
| ASint Technology    | 1         | 1.14%   |
| Apacer              | 1         | 1.14%   |
| A-DATA Technology   | 1         | 1.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 3.23%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 3.23%   |
| Unknown RAM Module 2048MB SODIMM DRAM 667MT/s                    | 2         | 2.15%   |
| Unknown RAM Module 1024MB SODIMM DRAM 667MT/s                    | 2         | 2.15%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.15%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.15%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.15%   |
| Samsung RAM M471B2873FHS-CF8 1GB SODIMM DDR3 1067MT/s            | 2         | 2.15%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 2.15%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 2.15%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.08%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.08%   |
| Unknown RAM Module 2048MB SODIMM DDR2 400MT/s                    | 1         | 1.08%   |
| Unknown RAM Module 1GB SODIMM LPDDR4 2400MT/s                    | 1         | 1.08%   |
| Unifosa RAM GU672203EP0200 1GB SODIMM DDR3 1333MT/s              | 1         | 1.08%   |
| Transcend RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 1         | 1.08%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s              | 1         | 1.08%   |
| SK hynix RAM Module 32GB SODIMM DDR4 2667MT/s                    | 1         | 1.08%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM SDRAM 2048MT/s       | 1         | 1.08%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.08%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.08%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.08%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.08%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.08%   |
| SK hynix RAM HMT125S6TFR8C-H9 2048MB SODIMM DDR3 4199MT/s        | 1         | 1.08%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 1.08%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 1.08%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.08%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.08%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.08%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.08%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.08%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 1         | 1.08%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.08%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.08%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.08%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.08%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.08%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.08%   |
| Samsung RAM M471B5173BH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.08%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 32        | 40.51%  |
| DDR4   | 31        | 39.24%  |
| LPDDR4 | 5         | 6.33%   |
| SDRAM  | 4         | 5.06%   |
| DDR2   | 3         | 3.8%    |
| LPDDR3 | 2         | 2.53%   |
| DRAM   | 2         | 2.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 69        | 90.79%  |
| Row Of Chips | 7         | 9.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 29        | 34.12%  |
| 8192  | 24        | 28.24%  |
| 2048  | 13        | 15.29%  |
| 16384 | 10        | 11.76%  |
| 1024  | 7         | 8.24%   |
| 32768 | 2         | 2.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 23        | 27.71%  |
| 2667    | 20        | 24.1%   |
| 3200    | 8         | 9.64%   |
| 2400    | 5         | 6.02%   |
| 1334    | 5         | 6.02%   |
| 1333    | 4         | 4.82%   |
| 4199    | 2         | 2.41%   |
| 3266    | 2         | 2.41%   |
| 2133    | 2         | 2.41%   |
| 2048    | 2         | 2.41%   |
| 1067    | 2         | 2.41%   |
| 667     | 2         | 2.41%   |
| 400     | 2         | 2.41%   |
| 4800    | 1         | 1.2%    |
| 1867    | 1         | 1.2%    |
| 975     | 1         | 1.2%    |
| Unknown | 1         | 1.2%    |

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
| Chicony Electronics                    | 27        | 23.89%  |
| IMC Networks                           | 24        | 21.24%  |
| Realtek Semiconductor                  | 12        | 10.62%  |
| Acer                                   | 8         | 7.08%   |
| Microdia                               | 7         | 6.19%   |
| Quanta                                 | 6         | 5.31%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.42%   |
| Sunplus Innovation Technology          | 4         | 3.54%   |
| Syntek                                 | 3         | 2.65%   |
| Silicon Motion                         | 3         | 2.65%   |
| Lite-On Technology                     | 3         | 2.65%   |
| Suyin                                  | 2         | 1.77%   |
| Luxvisions Innotech Limited            | 2         | 1.77%   |
| Alcor Micro                            | 2         | 1.77%   |
| Z-Star Microelectronics                | 1         | 0.88%   |
| Samsung Electronics                    | 1         | 0.88%   |
| Importek                               | 1         | 0.88%   |
| ezcap                                  | 1         | 0.88%   |
| Apple                                  | 1         | 0.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                           | 6         | 5.31%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 6         | 5.31%   |
| Chicony Integrated Camera                                    | 5         | 4.42%   |
| IMC Networks Integrated Camera                               | 4         | 3.54%   |
| Realtek Integrated_Webcam_HD                                 | 3         | 2.65%   |
| Quanta HP HD Camera                                          | 3         | 2.65%   |
| Chicony HD WebCam                                            | 3         | 2.65%   |
| Acer Integrated Camera                                       | 3         | 2.65%   |
| Syntek Lenovo EasyCamera                                     | 2         | 1.77%   |
| Silicon Motion WebCam SC-0311139N                            | 2         | 1.77%   |
| Realtek USB Camera                                           | 2         | 1.77%   |
| Quanta HP TrueVision HD Camera                               | 2         | 1.77%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 2         | 1.77%   |
| Microdia Integrated_Webcam_HD                                | 2         | 1.77%   |
| Lite-On HP HD Webcam                                         | 2         | 1.77%   |
| IMC Networks VGA UVC WebCam                                  | 2         | 1.77%   |
| Chicony USB2.0 VGA UVC WebCam                                | 2         | 1.77%   |
| Chicony Integrated Camera (1280x720@30)                      | 2         | 1.77%   |
| Chicony EasyCamera                                           | 2         | 1.77%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 2         | 1.77%   |
| Z-Star WebCam SCB-0320N                                      | 1         | 0.88%   |
| Syntek Integrated Camera                                     | 1         | 0.88%   |
| Suyin HP Truevision HD                                       | 1         | 0.88%   |
| Suyin HD WebCam                                              | 1         | 0.88%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.88%   |
| Sunplus Integrated_Webcam_HD                                 | 1         | 0.88%   |
| Sunplus HD WebCam                                            | 1         | 0.88%   |
| Sunplus Asus Webcam                                          | 1         | 0.88%   |
| Silicon Motion WebCam SC-13HDL11939N                         | 1         | 0.88%   |
| Samsung Galaxy A5 (MTP)                                      | 1         | 0.88%   |
| Realtek USB2.0 VGA UVC WebCam                                | 1         | 0.88%   |
| Realtek Integrated Webcam_HD                                 | 1         | 0.88%   |
| Realtek Integrated Webcam HD                                 | 1         | 0.88%   |
| Realtek HP Truevision HD                                     | 1         | 0.88%   |
| Realtek HP "Truevision HD" laptop camera                     | 1         | 0.88%   |
| Realtek HD WebCam                                            | 1         | 0.88%   |
| Realtek EasyCamera                                           | 1         | 0.88%   |
| Quanta VGA WebCam                                            | 1         | 0.88%   |
| Microdia Webcam Vitade AF                                    | 1         | 0.88%   |
| Microdia Webcam                                              | 1         | 0.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 33.33%  |
| Synaptics                  | 7         | 25.93%  |
| Elan Microelectronics      | 4         | 14.81%  |
| Shenzhen Goodix Technology | 3         | 11.11%  |
| Upek                       | 2         | 7.41%   |
| LighTuning Technology      | 1         | 3.7%    |
| AuthenTec                  | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 4         | 14.81%  |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 11.11%  |
| Elan ELAN:Fingerprint                                      | 3         | 11.11%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 7.41%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 7.41%   |
| Validity Sensors Fingerprint scanner                       | 2         | 7.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 2         | 7.41%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 7.41%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 3.7%    |
| Validity Sensors Synaptics WBDI                            | 1         | 3.7%    |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 3.7%    |
| Synaptics UWP WBDI                                         | 1         | 3.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 3.7%    |
| Elan ELAN:ARM-M4                                           | 1         | 3.7%    |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 3.7%    |

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
| 0     | 85        | 65.89%  |
| 1     | 34        | 26.36%  |
| 2     | 9         | 6.98%   |
| 3     | 1         | 0.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 27        | 52.94%  |
| Graphics card         | 13        | 25.49%  |
| Net/wireless          | 4         | 7.84%   |
| Multimedia controller | 2         | 3.92%   |
| Chipcard              | 2         | 3.92%   |
| Storage               | 1         | 1.96%   |
| Sound                 | 1         | 1.96%   |
| Camera                | 1         | 1.96%   |

