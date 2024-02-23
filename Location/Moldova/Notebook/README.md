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

Total: 206

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek  | ROG Strix G713RW_G713RW     | [20827e6f82](https://linux-hardware.org/?probe=20827e6f82) | Jan 26, 2024 |
| ASUSTek  | VivoBook_ASUSLaptop X415... | [1427f84afd](https://linux-hardware.org/?probe=1427f84afd) | Jan 18, 2024 |
| Lenovo   | IdeaPad 5 Pro 14ACN6 82L... | [123bf2b824](https://linux-hardware.org/?probe=123bf2b824) | Jan 17, 2024 |
| Lenovo   | IdeaPad 310-15ISK 80SM      | [8494044b32](https://linux-hardware.org/?probe=8494044b32) | Jan 11, 2024 |
| Lenovo   | LOQ 15IRH8 82XV             | [494b496889](https://linux-hardware.org/?probe=494b496889) | Jan 01, 2024 |
| ASUSTek  | UX32VD                      | [e073ccab15](https://linux-hardware.org/?probe=e073ccab15) | Dec 13, 2023 |
| Lenovo   | Z51-70 80K6                 | [2894d2f78d](https://linux-hardware.org/?probe=2894d2f78d) | Dec 06, 2023 |
| Apple    | MacBookPro9,2               | [c120b25f0f](https://linux-hardware.org/?probe=c120b25f0f) | Nov 17, 2023 |
| HP       | 250 G8 Notebook PC          | [a6d12193c7](https://linux-hardware.org/?probe=a6d12193c7) | Nov 17, 2023 |
| HP       | ProBook 4320s               | [0da6b1026b](https://linux-hardware.org/?probe=0da6b1026b) | Nov 15, 2023 |
| ASUSTek  | ROG Strix G712LU_G712LU     | [50087ec971](https://linux-hardware.org/?probe=50087ec971) | Oct 08, 2023 |
| ASUSTek  | ROG Strix G712LU_G712LU     | [6f7b1474d0](https://linux-hardware.org/?probe=6f7b1474d0) | Oct 06, 2023 |
| Lenovo   | ThinkBook 15-IML 20RW       | [a8c067b868](https://linux-hardware.org/?probe=a8c067b868) | Sep 22, 2023 |
| Lenovo   | ThinkBook 15 G4 IAP 21DJ    | [367454b6bc](https://linux-hardware.org/?probe=367454b6bc) | Sep 16, 2023 |
| Dell     | Latitude 7490               | [c03e42edee](https://linux-hardware.org/?probe=c03e42edee) | Sep 05, 2023 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | [ded378b5da](https://linux-hardware.org/?probe=ded378b5da) | Aug 30, 2023 |
| Timi     | A34R                        | [f2998bab84](https://linux-hardware.org/?probe=f2998bab84) | Aug 25, 2023 |
| Dell     | Latitude 7490               | [90685f1b4d](https://linux-hardware.org/?probe=90685f1b4d) | Aug 21, 2023 |
| Dell     | Inspiron 15 7000 Gaming     | [7da49ac1c3](https://linux-hardware.org/?probe=7da49ac1c3) | Aug 17, 2023 |
| Dell     | Latitude 7490               | [efb4abea09](https://linux-hardware.org/?probe=efb4abea09) | Aug 16, 2023 |
| ASUSTek  | ROG Strix G713RW_G713RW     | [91887235b2](https://linux-hardware.org/?probe=91887235b2) | Jul 31, 2023 |
| HP       | EliteBook 850 G1            | [3e08f1644a](https://linux-hardware.org/?probe=3e08f1644a) | Jun 24, 2023 |
| HP       | EliteBook 850 G1            | [574653afac](https://linux-hardware.org/?probe=574653afac) | Jun 24, 2023 |
| HP       | EliteBook 850 G1            | [fa6b09cc1d](https://linux-hardware.org/?probe=fa6b09cc1d) | Jun 23, 2023 |
| Dell     | Vostro 3525                 | [308ee62292](https://linux-hardware.org/?probe=308ee62292) | Jun 21, 2023 |
| Acer     | AOD257                      | [d3510be962](https://linux-hardware.org/?probe=d3510be962) | Jun 18, 2023 |
| Dell     | Vostro 3525                 | [fb399aebb6](https://linux-hardware.org/?probe=fb399aebb6) | Jun 11, 2023 |
| Dell     | Vostro 3525                 | [e4b62aaf28](https://linux-hardware.org/?probe=e4b62aaf28) | Jun 05, 2023 |
| Acer     | Aspire A515-54G             | [a6c2011fb0](https://linux-hardware.org/?probe=a6c2011fb0) | May 25, 2023 |
| Acer     | Aspire A515-54G             | [e58d4b4aee](https://linux-hardware.org/?probe=e58d4b4aee) | May 25, 2023 |
| Sony     | VPCF13WFX                   | [6500c354c7](https://linux-hardware.org/?probe=6500c354c7) | May 01, 2023 |
| Lenovo   | B50-30 80ES                 | [d84727b8e4](https://linux-hardware.org/?probe=d84727b8e4) | Apr 29, 2023 |
| Toshiba  | Satellite S50-B             | [e9d26a9e89](https://linux-hardware.org/?probe=e9d26a9e89) | Apr 12, 2023 |
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


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 18.04        | 12        | 7.69%   |
| Ubuntu 20.04        | 11        | 7.05%   |
| Ubuntu 22.04        | 9         | 5.77%   |
| ROSA R10            | 9         | 5.77%   |
| ROSA R11            | 6         | 3.85%   |
| Linux Mint 20.1     | 5         | 3.21%   |
| Linux Mint 21.1     | 4         | 2.56%   |
| KDE neon 20.04      | 4         | 2.56%   |
| Arch                | 4         | 2.56%   |
| ROSA R9             | 3         | 1.92%   |
| ROSA R8             | 3         | 1.92%   |
| ROSA R11.1          | 3         | 1.92%   |
| Linux Mint 19.1     | 3         | 1.92%   |
| Fedora 36           | 3         | 1.92%   |
| Fedora 34           | 3         | 1.92%   |
| Arch Rolling        | 3         | 1.92%   |
| Zorin 16            | 2         | 1.28%   |
| Ubuntu 22.10        | 2         | 1.28%   |
| Ubuntu 19.10        | 2         | 1.28%   |
| ROSA R8.1           | 2         | 1.28%   |
| ROSA 12.2           | 2         | 1.28%   |
| Pop!_OS 21.04       | 2         | 1.28%   |
| OpenMandriva 4.3    | 2         | 1.28%   |
| OpenMandriva 23.08  | 2         | 1.28%   |
| Manjaro             | 2         | 1.28%   |
| Linux Mint 21.2     | 2         | 1.28%   |
| Linux Mint 20.2     | 2         | 1.28%   |
| EndeavourOS Rolling | 2         | 1.28%   |
| BlackPanther 18.1   | 2         | 1.28%   |
| Ubuntu Budgie 23.04 | 1         | 0.64%   |
| Ubuntu 23.10        | 1         | 0.64%   |
| Ubuntu 23.04        | 1         | 0.64%   |
| Ubuntu 21.04        | 1         | 0.64%   |
| Ubuntu 16.04        | 1         | 0.64%   |
| SteamOS 3.3.2       | 1         | 0.64%   |
| SteamOS 3.3         | 1         | 0.64%   |
| ROSA 12.4           | 1         | 0.64%   |
| ROSA 12.3           | 1         | 0.64%   |
| ROSA 12.1           | 1         | 0.64%   |
| Pop!_OS 22.04       | 1         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 40        | 26.85%  |
| ROSA          | 27        | 18.12%  |
| Linux Mint    | 19        | 12.75%  |
| Fedora        | 10        | 6.71%   |
| Manjaro       | 8         | 5.37%   |
| Arch          | 7         | 4.7%    |
| OpenMandriva  | 6         | 4.03%   |
| Pop!_OS       | 4         | 2.68%   |
| KDE neon      | 4         | 2.68%   |
| Kali          | 4         | 2.68%   |
| Endless       | 3         | 2.01%   |
| Debian        | 3         | 2.01%   |
| Zorin         | 2         | 1.34%   |
| SteamOS       | 2         | 1.34%   |
| Kubuntu       | 2         | 1.34%   |
| EndeavourOS   | 2         | 1.34%   |
| BlackPanther  | 2         | 1.34%   |
| Ubuntu Budgie | 1         | 0.67%   |
| BuildRoot     | 1         | 0.67%   |
| ArcoLinux     | 1         | 0.67%   |
| ALT Linux     | 1         | 0.67%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.15.0-41-generic                  | 4         | 2.41%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 4         | 2.41%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 4         | 2.41%   |
| 5.8.0-33-generic                   | 3         | 1.81%   |
| 4.9.60-nrj-desktop-1rosa-i586      | 3         | 1.81%   |
| 6.6.8-arch1-1                      | 2         | 1.2%    |
| 5.4.0-37-generic                   | 2         | 1.2%    |
| 5.16.7-desktop-1omv4003            | 2         | 1.2%    |
| 5.15.0-88-generic                  | 2         | 1.2%    |
| 5.15.0-58-generic                  | 2         | 1.2%    |
| 5.11.0-7614-generic                | 2         | 1.2%    |
| 5.11.0-41-generic                  | 2         | 1.2%    |
| 5.11.0-34-generic                  | 2         | 1.2%    |
| 5.10.74-generic-2rosa2021.1-x86_64 | 2         | 1.2%    |
| 5.10.2-2-MANJARO                   | 2         | 1.2%    |
| 4.9.95-nrj-desktop-2rosa-x86_64    | 2         | 1.2%    |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 2         | 1.2%    |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 2         | 1.2%    |
| 4.15.0-desktop-68.5rosa-x86_64     | 2         | 1.2%    |
| 4.15.0-desktop-45.1rosa-x86_64     | 2         | 1.2%    |
| 6.7.0-arch3-1-g14                  | 1         | 0.6%    |
| 6.6.2-desktop-1omv2390             | 1         | 0.6%    |
| 6.6.10-zen1-1-zen                  | 1         | 0.6%    |
| 6.5.0-kali3-amd64                  | 1         | 0.6%    |
| 6.5.0-kali1-amd64                  | 1         | 0.6%    |
| 6.5.0-9-generic                    | 1         | 0.6%    |
| 6.4.8-desktop-2omv2390             | 1         | 0.6%    |
| 6.4.6-arch1-1-g14                  | 1         | 0.6%    |
| 6.4.13-200.fc38.x86_64             | 1         | 0.6%    |
| 6.4.11-desktop-1omv2390            | 1         | 0.6%    |
| 6.4.10-200.fc38.x86_64             | 1         | 0.6%    |
| 6.2.8-arch1-1                      | 1         | 0.6%    |
| 6.2.6-76060206-generic             | 1         | 0.6%    |
| 6.2.10-arch1-1                     | 1         | 0.6%    |
| 6.2.0-32-generic                   | 1         | 0.6%    |
| 6.2.0-26-generic                   | 1         | 0.6%    |
| 6.2.0-20-generic                   | 1         | 0.6%    |
| 6.1.31-2-MANJARO                   | 1         | 0.6%    |
| 6.1.1-desktop-1omv2290             | 1         | 0.6%    |
| 6.1.0-7-amd64                      | 1         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 16        | 9.88%   |
| 4.15.0  | 15        | 9.26%   |
| 5.4.0   | 12        | 7.41%   |
| 5.11.0  | 11        | 6.79%   |
| 4.9.60  | 6         | 3.7%    |
| 5.8.0   | 5         | 3.09%   |
| 5.3.0   | 4         | 2.47%   |
| 4.9.20  | 4         | 2.47%   |
| 6.5.0   | 3         | 1.85%   |
| 6.2.0   | 3         | 1.85%   |
| 5.13.0  | 3         | 1.85%   |
| 5.0.0   | 3         | 1.85%   |
| 4.18.0  | 3         | 1.85%   |
| 6.6.8   | 2         | 1.23%   |
| 5.8.18  | 2         | 1.23%   |
| 5.19.0  | 2         | 1.23%   |
| 5.18.1  | 2         | 1.23%   |
| 5.16.7  | 2         | 1.23%   |
| 5.10.74 | 2         | 1.23%   |
| 5.10.2  | 2         | 1.23%   |
| 5.10.0  | 2         | 1.23%   |
| 4.9.95  | 2         | 1.23%   |
| 4.9.41  | 2         | 1.23%   |
| 4.9.155 | 2         | 1.23%   |
| 6.7.0   | 1         | 0.62%   |
| 6.6.2   | 1         | 0.62%   |
| 6.6.10  | 1         | 0.62%   |
| 6.4.8   | 1         | 0.62%   |
| 6.4.6   | 1         | 0.62%   |
| 6.4.13  | 1         | 0.62%   |
| 6.4.11  | 1         | 0.62%   |
| 6.4.10  | 1         | 0.62%   |
| 6.2.8   | 1         | 0.62%   |
| 6.2.6   | 1         | 0.62%   |
| 6.2.10  | 1         | 0.62%   |
| 6.1.31  | 1         | 0.62%   |
| 6.1.1   | 1         | 0.62%   |
| 6.1.0   | 1         | 0.62%   |
| 5.9.3   | 1         | 0.62%   |
| 5.6.14  | 1         | 0.62%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 22        | 14.01%  |
| 4.9     | 15        | 9.55%   |
| 4.15    | 15        | 9.55%   |
| 5.4     | 14        | 8.92%   |
| 5.11    | 12        | 7.64%   |
| 5.10    | 8         | 5.1%    |
| 5.8     | 7         | 4.46%   |
| 6.2     | 6         | 3.82%   |
| 5.18    | 6         | 3.82%   |
| 6.6     | 4         | 2.55%   |
| 6.4     | 4         | 2.55%   |
| 5.3     | 4         | 2.55%   |
| 5.19    | 4         | 2.55%   |
| 5.13    | 4         | 2.55%   |
| 5.0     | 4         | 2.55%   |
| 6.5     | 3         | 1.91%   |
| 6.1     | 3         | 1.91%   |
| 5.17    | 3         | 1.91%   |
| 5.16    | 3         | 1.91%   |
| 4.18    | 3         | 1.91%   |
| 4.1     | 3         | 1.91%   |
| 5.12    | 2         | 1.27%   |
| 6.7     | 1         | 0.64%   |
| 5.9     | 1         | 0.64%   |
| 5.6     | 1         | 0.64%   |
| 5.14    | 1         | 0.64%   |
| 5.1     | 1         | 0.64%   |
| 4.19    | 1         | 0.64%   |
| 4.16    | 1         | 0.64%   |
| 4.10    | 1         | 0.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 143       | 95.33%  |
| i686   | 7         | 4.67%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 49        | 32.03%  |
| KDE5            | 38        | 24.84%  |
| KDE4            | 19        | 12.42%  |
| X-Cinnamon      | 14        | 9.15%   |
| Unknown         | 14        | 9.15%   |
| XFCE            | 8         | 5.23%   |
| MATE            | 2         | 1.31%   |
| LXQt            | 2         | 1.31%   |
| Cinnamon        | 2         | 1.31%   |
| sway            | 1         | 0.65%   |
| KDE             | 1         | 0.65%   |
| i3              | 1         | 0.65%   |
| GNOME Flashback | 1         | 0.65%   |
| Budgie          | 1         | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 111       | 73.03%  |
| Wayland | 30        | 19.74%  |
| Unknown | 11        | 7.24%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 53        | 34.42%  |
| SDDM    | 30        | 19.48%  |
| GDM     | 20        | 12.99%  |
| KDM     | 19        | 12.34%  |
| GDM3    | 14        | 9.09%   |
| LightDM | 12        | 7.79%   |
| TDM     | 6         | 3.9%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 61        | 40.67%  |
| Unknown | 39        | 26%     |
| ru_RU   | 30        | 20%     |
| ro_RO   | 7         | 4.67%   |
| C       | 6         | 4%      |
| en_GB   | 2         | 1.33%   |
| uk_UA   | 1         | 0.67%   |
| ru_UA   | 1         | 0.67%   |
| nl_NL   | 1         | 0.67%   |
| en_150  | 1         | 0.67%   |
| de_DE   | 1         | 0.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 83        | 55.7%   |
| BIOS | 66        | 44.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 102       | 68%     |
| Unknown | 16        | 10.67%  |
| Btrfs   | 15        | 10%     |
| Overlay | 10        | 6.67%   |
| Tmpfs   | 5         | 3.33%   |
| Xfs     | 2         | 1.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 65        | 43.33%  |
| Unknown | 59        | 39.33%  |
| MBR     | 26        | 17.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 137       | 91.33%  |
| Yes       | 13        | 8.67%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 109       | 72.19%  |
| Yes       | 42        | 27.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 34        | 22.97%  |
| ASUSTek Computer    | 32        | 21.62%  |
| Hewlett-Packard     | 29        | 19.59%  |
| Dell                | 15        | 10.14%  |
| Acer                | 11        | 7.43%   |
| Toshiba             | 5         | 3.38%   |
| Timi                | 5         | 3.38%   |
| Samsung Electronics | 4         | 2.7%    |
| Sony                | 2         | 1.35%   |
| Apple               | 2         | 1.35%   |
| Valve               | 1         | 0.68%   |
| System76            | 1         | 0.68%   |
| MSI                 | 1         | 0.68%   |
| Jumper              | 1         | 0.68%   |
| HUAWEI              | 1         | 0.68%   |
| Google              | 1         | 0.68%   |
| Gateway             | 1         | 0.68%   |
| Chuwi               | 1         | 0.68%   |
| Unknown             | 1         | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Timi TM1701                                 | 3         | 2.03%   |
| ASUS VivoBook_ASUSLaptop X521IA_D533IA      | 3         | 2.03%   |
| Samsung RV413/RV513                         | 2         | 1.35%   |
| Lenovo Legion Y530-15ICH 81FV               | 2         | 1.35%   |
| HP ProBook 450 G7                           | 2         | 1.35%   |
| HP Compaq Presario CQ60                     | 2         | 1.35%   |
| ASUS VivoBook S15 X510UF                    | 2         | 1.35%   |
| Unknown                                     | 2         | 1.35%   |
| Valve Jupiter                               | 1         | 0.68%   |
| Toshiba TECRA Z40-B                         | 1         | 0.68%   |
| Toshiba Satellite S50-B                     | 1         | 0.68%   |
| Toshiba Satellite Pro S300L                 | 1         | 0.68%   |
| Toshiba Satellite C55D-A                    | 1         | 0.68%   |
| Toshiba Satellite A210                      | 1         | 0.68%   |
| Timi A35S                                   | 1         | 0.68%   |
| Timi A34R                                   | 1         | 0.68%   |
| System76 Adder WS                           | 1         | 0.68%   |
| Sony VPCF13WFX                              | 1         | 0.68%   |
| Sony VPCEB1J8E                              | 1         | 0.68%   |
| Samsung R517/R717                           | 1         | 0.68%   |
| Samsung 300E4C/300E5C/300E7C                | 1         | 0.68%   |
| MSI CR610                                   | 1         | 0.68%   |
| Lenovo Z51-70 80K6                          | 1         | 0.68%   |
| Lenovo Y520-15IKBN 80WK                     | 1         | 0.68%   |
| Lenovo V580 20147                           | 1         | 0.68%   |
| Lenovo ThinkPad Yoga 11e 3rd Gen 20G8S0MG00 | 1         | 0.68%   |
| Lenovo ThinkPad X240 20AL0067RT             | 1         | 0.68%   |
| Lenovo ThinkPad X131e 33711T0               | 1         | 0.68%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR002MMX    | 1         | 0.68%   |
| Lenovo ThinkPad W520 4282BA9                | 1         | 0.68%   |
| Lenovo ThinkPad T440 20B7S1N809             | 1         | 0.68%   |
| Lenovo ThinkPad E15 Gen 3 20YG004BRT        | 1         | 0.68%   |
| Lenovo ThinkPad E15 Gen 2 20TD003TRT        | 1         | 0.68%   |
| Lenovo ThinkPad E15 Gen 2 20TD002NRA        | 1         | 0.68%   |
| Lenovo ThinkBook 15-IML 20RW                | 1         | 0.68%   |
| Lenovo ThinkBook 15 G4 IAP 21DJ             | 1         | 0.68%   |
| Lenovo LOQ 15IRH8 82XV                      | 1         | 0.68%   |
| Lenovo Legion 5 Pro 16ITH6H 82JD            | 1         | 0.68%   |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 0.68%   |
| Lenovo IdeaPad L340-15API 81LW              | 1         | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 13        | 8.78%   |
| Lenovo ThinkPad    | 9         | 6.08%   |
| ASUS VivoBook      | 9         | 6.08%   |
| HP ProBook         | 7         | 4.73%   |
| Acer Aspire        | 7         | 4.73%   |
| Dell Latitude      | 6         | 4.05%   |
| Dell Inspiron      | 6         | 4.05%   |
| HP EliteBook       | 5         | 3.38%   |
| Toshiba Satellite  | 4         | 2.7%    |
| Lenovo Legion      | 4         | 2.7%    |
| HP Pavilion        | 4         | 2.7%    |
| HP Compaq          | 4         | 2.7%    |
| Timi TM1701        | 3         | 2.03%   |
| ASUS ROG           | 3         | 2.03%   |
| Samsung RV413      | 2         | 1.35%   |
| Lenovo ThinkBook   | 2         | 1.35%   |
| HP Laptop          | 2         | 1.35%   |
| HP ENVY            | 2         | 1.35%   |
| Dell Vostro        | 2         | 1.35%   |
| ASUS ZenBook       | 2         | 1.35%   |
| Unknown            | 2         | 1.35%   |
| Valve Jupiter      | 1         | 0.68%   |
| Toshiba TECRA      | 1         | 0.68%   |
| Timi A35S          | 1         | 0.68%   |
| Timi A34R          | 1         | 0.68%   |
| System76 Adder     | 1         | 0.68%   |
| Sony VPCF13WFX     | 1         | 0.68%   |
| Sony VPCEB1J8E     | 1         | 0.68%   |
| Samsung R517       | 1         | 0.68%   |
| Samsung 300E4C     | 1         | 0.68%   |
| MSI CR610          | 1         | 0.68%   |
| Lenovo Z51-70      | 1         | 0.68%   |
| Lenovo Y520-15IKBN | 1         | 0.68%   |
| Lenovo V580        | 1         | 0.68%   |
| Lenovo LOQ         | 1         | 0.68%   |
| Lenovo G710        | 1         | 0.68%   |
| Lenovo B50-30      | 1         | 0.68%   |
| Jumper EZbook      | 1         | 0.68%   |
| HUAWEI NBLK-WAX9X  | 1         | 0.68%   |
| HP ZBook           | 1         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 19        | 12.84%  |
| 2021 | 16        | 10.81%  |
| 2018 | 15        | 10.14%  |
| 2011 | 14        | 9.46%   |
| 2017 | 13        | 8.78%   |
| 2012 | 12        | 8.11%   |
| 2020 | 10        | 6.76%   |
| 2016 | 7         | 4.73%   |
| 2015 | 7         | 4.73%   |
| 2014 | 7         | 4.73%   |
| 2013 | 7         | 4.73%   |
| 2022 | 5         | 3.38%   |
| 2010 | 5         | 3.38%   |
| 2009 | 4         | 2.7%    |
| 2008 | 4         | 2.7%    |
| 2007 | 2         | 1.35%   |
| 2023 | 1         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 148       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 138       | 93.24%  |
| Enabled  | 10        | 6.76%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 147       | 99.32%  |
| Yes  | 1         | 0.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 38        | 25.68%  |
| 3.01-4.0    | 36        | 24.32%  |
| 8.01-16.0   | 27        | 18.24%  |
| 16.01-24.0  | 23        | 15.54%  |
| 32.01-64.0  | 10        | 6.76%   |
| 1.01-2.0    | 6         | 4.05%   |
| 2.01-3.0    | 4         | 2.7%    |
| 24.01-32.0  | 2         | 1.35%   |
| 64.01-256.0 | 2         | 1.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 53        | 34.19%  |
| 2.01-3.0   | 29        | 18.71%  |
| 4.01-8.0   | 26        | 16.77%  |
| 3.01-4.0   | 19        | 12.26%  |
| 0.51-1.0   | 18        | 11.61%  |
| 8.01-16.0  | 6         | 3.87%   |
| 16.01-24.0 | 3         | 1.94%   |
| 24.01-32.0 | 1         | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 116       | 78.38%  |
| 2      | 27        | 18.24%  |
| 3      | 4         | 2.7%    |
| 0      | 1         | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 108       | 72.97%  |
| Yes       | 40        | 27.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 81.21%  |
| No        | 28        | 18.79%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 147       | 99.32%  |
| No        | 1         | 0.68%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 77.85%  |
| No        | 33        | 22.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Moldova | 148       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Chisinau        | 95        | 62.91%  |
| Tiraspol        | 16        | 10.6%   |
| Bălţi         | 5         | 3.31%   |
| Straseni        | 3         | 1.99%   |
| Tighina         | 2         | 1.32%   |
| Soroca          | 2         | 1.32%   |
| Hincesti        | 2         | 1.32%   |
| Floresti        | 2         | 1.32%   |
| Congaz          | 2         | 1.32%   |
| Zaicana         | 1         | 0.66%   |
| Tvardița       | 1         | 0.66%   |
| Soldanesti      | 1         | 0.66%   |
| Sofia           | 1         | 0.66%   |
| Rautel          | 1         | 0.66%   |
| Prajila         | 1         | 0.66%   |
| Pociumbeni      | 1         | 0.66%   |
| Orhei           | 1         | 0.66%   |
| Nisporeni       | 1         | 0.66%   |
| Mascauti        | 1         | 0.66%   |
| Ilenuta         | 1         | 0.66%   |
| Ialoveni        | 1         | 0.66%   |
| Gangura         | 1         | 0.66%   |
| Floreni         | 1         | 0.66%   |
| Donduseni       | 1         | 0.66%   |
| Criuleni        | 1         | 0.66%   |
| Cricova         | 1         | 0.66%   |
| Crasnoarmeiscoe | 1         | 0.66%   |
| Cenac           | 1         | 0.66%   |
| Căușeni       | 1         | 0.66%   |
| Cantemir        | 1         | 0.66%   |
| Cahul           | 1         | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 34        | 43     | 19.21%  |
| Toshiba                     | 20        | 24     | 11.3%   |
| WDC                         | 17        | 18     | 9.6%    |
| Seagate                     | 15        | 19     | 8.47%   |
| Hitachi                     | 13        | 14     | 7.34%   |
| Kingston                    | 11        | 14     | 6.21%   |
| SanDisk                     | 10        | 10     | 5.65%   |
| SK hynix                    | 7         | 7      | 3.95%   |
| Micron Technology           | 7         | 10     | 3.95%   |
| Unknown                     | 5         | 5      | 2.82%   |
| Intel                       | 4         | 6      | 2.26%   |
| HGST                        | 3         | 3      | 1.69%   |
| A-DATA Technology           | 3         | 3      | 1.69%   |
| UMIS                        | 2         | 2      | 1.13%   |
| Transcend                   | 2         | 2      | 1.13%   |
| Netac                       | 2         | 2      | 1.13%   |
| KIOXIA                      | 2         | 2      | 1.13%   |
| Kingston Technology Company | 2         | 2      | 1.13%   |
| Intenso                     | 2         | 2      | 1.13%   |
| Fujitsu                     | 2         | 2      | 1.13%   |
| ZOTAC                       | 1         | 3      | 0.56%   |
| Solid State Storage         | 1         | 1      | 0.56%   |
| PNY                         | 1         | 1      | 0.56%   |
| Phison                      | 1         | 2      | 0.56%   |
| OCZ                         | 1         | 1      | 0.56%   |
| O2 Micro                    | 1         | 1      | 0.56%   |
| LITEONIT                    | 1         | 1      | 0.56%   |
| Lenovo                      | 1         | 1      | 0.56%   |
| GOODRAM                     | 1         | 1      | 0.56%   |
| Crucial                     | 1         | 1      | 0.56%   |
| China                       | 1         | 1      | 0.56%   |
| ASMT                        | 1         | 1      | 0.56%   |
| Apacer                      | 1         | 1      | 0.56%   |
| AMD                         | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB        | 6         | 3.35%   |
| Toshiba MQ04ABF100 1TB              | 4         | 2.23%   |
| Toshiba MQ01ABD100 1TB              | 4         | 2.23%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 2.23%   |
| Kingston SHFS37A120G 120GB SSD      | 4         | 2.23%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 1.68%   |
| SanDisk NVMe SSD Drive 512GB        | 3         | 1.68%   |
| Samsung MZVLW256HEHP-00000 256GB    | 3         | 1.68%   |
| Hitachi HTS543232A7A384 320GB       | 3         | 1.68%   |
| WDC WD10SPZX-24Z10T0 1TB            | 2         | 1.12%   |
| Unknown MMC Card  64GB              | 2         | 1.12%   |
| Transcend TS120GMTS420S 120GB SSD   | 2         | 1.12%   |
| Toshiba MQ01ACF032 320GB            | 2         | 1.12%   |
| Toshiba MQ01ABF050 500GB            | 2         | 1.12%   |
| SK hynix NVMe SSD Drive 256GB       | 2         | 1.12%   |
| Seagate ST9500325AS 500GB           | 2         | 1.12%   |
| Samsung SSD 980 500GB               | 2         | 1.12%   |
| Samsung SSD 860 EVO 500GB           | 2         | 1.12%   |
| Netac SSD 256GB                     | 2         | 1.12%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 2         | 1.12%   |
| KIOXIA KBG40ZNV512G 512GB           | 2         | 1.12%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 1.12%   |
| Hitachi HTS547575A9E384 752GB       | 2         | 1.12%   |
| ZOTAC ZTSSD-S11-240G-P 240GB        | 1         | 0.56%   |
| WDC WDS512G1X0C-00ENX0 512GB        | 1         | 0.56%   |
| WDC WD5000LPVX-80V0TT0 500GB        | 1         | 0.56%   |
| WDC WD5000LPVX-75V0TT0 500GB        | 1         | 0.56%   |
| WDC WD5000LPCX-75VHAT1 500GB        | 1         | 0.56%   |
| WDC WD5000BPVT-08HXZT3 500GB        | 1         | 0.56%   |
| WDC WD5000BEVT-22A0RT0 500GB        | 1         | 0.56%   |
| WDC WD3200BPVT-80JJ5T0 320GB        | 1         | 0.56%   |
| WDC WD3200BEVT-63ZCT0 320GB         | 1         | 0.56%   |
| WDC WD3200BEVT-22A23T0 320GB        | 1         | 0.56%   |
| WDC WD3200BEVT-00ZCT0 320GB         | 1         | 0.56%   |
| WDC WD1600BEVS-07RST0 160GB         | 1         | 0.56%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 0.56%   |
| WDC WD10SPZX-22Z10T1 1TB            | 1         | 0.56%   |
| WDC WD10SPSX-60A6WT0 1TB            | 1         | 0.56%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 0.56%   |
| Unknown TO  64GB                    | 1         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 17     | 23.53%  |
| Toshiba             | 16        | 20     | 23.53%  |
| Seagate             | 15        | 19     | 22.06%  |
| Hitachi             | 13        | 14     | 19.12%  |
| HGST                | 3         | 3      | 4.41%   |
| Fujitsu             | 2         | 2      | 2.94%   |
| Unknown             | 1         | 1      | 1.47%   |
| Samsung Electronics | 1         | 1      | 1.47%   |
| ASMT                | 1         | 1      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 14     | 24.44%  |
| Kingston            | 8         | 11     | 17.78%  |
| SanDisk             | 5         | 5      | 11.11%  |
| Transcend           | 2         | 2      | 4.44%   |
| Toshiba             | 2         | 2      | 4.44%   |
| Netac               | 2         | 2      | 4.44%   |
| Micron Technology   | 2         | 2      | 4.44%   |
| Intenso             | 2         | 2      | 4.44%   |
| ZOTAC               | 1         | 3      | 2.22%   |
| PNY                 | 1         | 1      | 2.22%   |
| OCZ                 | 1         | 1      | 2.22%   |
| LITEONIT            | 1         | 1      | 2.22%   |
| Intel               | 1         | 1      | 2.22%   |
| GOODRAM             | 1         | 1      | 2.22%   |
| Crucial             | 1         | 1      | 2.22%   |
| China               | 1         | 1      | 2.22%   |
| Apacer              | 1         | 1      | 2.22%   |
| AMD                 | 1         | 1      | 2.22%   |
| A-DATA Technology   | 1         | 1      | 2.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 68        | 78     | 40%     |
| NVMe | 56        | 72     | 32.94%  |
| SSD  | 42        | 53     | 24.71%  |
| MMC  | 4         | 4      | 2.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 101       | 129    | 61.96%  |
| NVMe | 56        | 72     | 34.36%  |
| MMC  | 4         | 4      | 2.45%   |
| SAS  | 2         | 2      | 1.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 77        | 95     | 71.3%   |
| 0.51-1.0   | 29        | 34     | 26.85%  |
| 1.01-2.0   | 2         | 2      | 1.85%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 45        | 28.66%  |
| 101-250        | 45        | 28.66%  |
| 501-1000       | 25        | 15.92%  |
| 51-100         | 12        | 7.64%   |
| 1-20           | 11        | 7.01%   |
| 1001-2000      | 6         | 3.82%   |
| Unknown        | 6         | 3.82%   |
| 21-50          | 5         | 3.18%   |
| More than 3000 | 2         | 1.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 68        | 42.5%   |
| 21-50     | 26        | 16.25%  |
| 51-100    | 22        | 13.75%  |
| 101-250   | 18        | 11.25%  |
| 251-500   | 13        | 8.13%   |
| 501-1000  | 6         | 3.75%   |
| Unknown   | 6         | 3.75%   |
| 1001-2000 | 1         | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB   | 3         | 3      | 18.75%  |
| Hitachi HTS547575A9E384 752GB     | 2         | 2      | 12.5%   |
| WDC WD3200BEVT-22A23T0 320GB      | 1         | 1      | 6.25%   |
| WDC WD1600BEVS-07RST0 160GB       | 1         | 1      | 6.25%   |
| WDC WD10JPCX-24UE4T0 1TB          | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 6.25%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 6.25%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 6.25%   |
| SanDisk SD7UB3Q256G1001 256GB SSD | 1         | 1      | 6.25%   |
| Kingston SHFS37A120G 120GB SSD    | 1         | 3      | 6.25%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 6.25%   |
| Fujitsu MHW2080BH PL 80GB         | 1         | 1      | 6.25%   |
| A-DATA Technology SX900 256GB SSD | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 5         | 5      | 31.25%  |
| WDC               | 3         | 3      | 18.75%  |
| Hitachi           | 3         | 3      | 18.75%  |
| Toshiba           | 1         | 1      | 6.25%   |
| SanDisk           | 1         | 1      | 6.25%   |
| Kingston          | 1         | 3      | 6.25%   |
| Fujitsu           | 1         | 1      | 6.25%   |
| A-DATA Technology | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 38.46%  |
| WDC     | 3         | 3      | 23.08%  |
| Hitachi | 3         | 3      | 23.08%  |
| Toshiba | 1         | 1      | 7.69%   |
| Fujitsu | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 13     | 81.25%  |
| SSD  | 3         | 5      | 18.75%  |

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
| Works    | 72        | 104    | 47.06%  |
| Detected | 64        | 84     | 41.83%  |
| Malfunc  | 16        | 18     | 10.46%  |
| Failed   | 1         | 1      | 0.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 93        | 50.54%  |
| AMD                            | 32        | 17.39%  |
| Samsung Electronics            | 22        | 11.96%  |
| SK hynix                       | 7         | 3.8%    |
| SanDisk                        | 6         | 3.26%   |
| Micron Technology              | 5         | 2.72%   |
| Kingston Technology Company    | 5         | 2.72%   |
| Union Memory (Shenzhen)        | 2         | 1.09%   |
| Toshiba America Info Systems   | 2         | 1.09%   |
| Nvidia                         | 2         | 1.09%   |
| KIOXIA                         | 2         | 1.09%   |
| Solid State Storage Technology | 1         | 0.54%   |
| Realtek Semiconductor          | 1         | 0.54%   |
| Phison Electronics             | 1         | 0.54%   |
| O2 Micro                       | 1         | 0.54%   |
| Lenovo                         | 1         | 0.54%   |
| ADATA Technology               | 1         | 0.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 23        | 11.79%  |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 12        | 6.15%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 6.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 9         | 4.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 8         | 4.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 3.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 3.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 3.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 2.56%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 2.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 2.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 2.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 2.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 1.54%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 1.54%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 1.54%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.03%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 2         | 1.03%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 1.03%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 2         | 1.03%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 2         | 1.03%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 2         | 1.03%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 2         | 1.03%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 2         | 1.03%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 1.03%   |
| Intel SSD 660P Series                                                            | 2         | 1.03%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.03%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 1.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 1.03%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 NVMe SSD 256GB                            | 1         | 0.51%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 512GB                            | 1         | 0.51%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                   | 1         | 0.51%   |
| SK hynix PC611 NVMe Solid State Drive                                            | 1         | 0.51%   |
| SK hynix PC601 NVMe Solid State Drive                                            | 1         | 0.51%   |
| SK hynix BC511 NVMe SSD                                                          | 1         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 113       | 60.11%  |
| NVMe | 56        | 29.79%  |
| IDE  | 10        | 5.32%   |
| RAID | 9         | 4.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 106       | 71.62%  |
| AMD    | 42        | 28.38%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 2.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 2.7%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 2.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.03%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.03%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.03%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 2.03%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 2.03%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 2.03%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 2.03%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 2.03%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 3         | 2.03%   |
| AMD E-450 APU with Radeon HD Graphics         | 3         | 2.03%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 1.35%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 1.35%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.35%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.35%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.35%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.35%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 1.35%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.35%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 2         | 1.35%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.35%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.35%   |
| AMD E-300 APU with Radeon HD Graphics         | 2         | 1.35%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.68%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.68%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.68%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.68%   |
| Intel Pentium CPU B980 @ 2.40GHz              | 1         | 0.68%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.68%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.68%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.68%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.68%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.68%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.68%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.68%   |
| Intel Core i7-3517U CPU @ 1.90GHz             | 1         | 0.68%   |
| Intel Core i7-2820QM CPU @ 2.30GHz            | 1         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 35        | 23.65%  |
| Intel Core i7                  | 23        | 15.54%  |
| Intel Core i3                  | 14        | 9.46%   |
| Intel Celeron                  | 12        | 8.11%   |
| AMD Ryzen 5                    | 11        | 7.43%   |
| Other                          | 8         | 5.41%   |
| AMD Ryzen 7                    | 8         | 5.41%   |
| Intel Pentium                  | 6         | 4.05%   |
| AMD E                          | 5         | 3.38%   |
| Intel Pentium Silver           | 3         | 2.03%   |
| Intel Core 2 Duo               | 3         | 2.03%   |
| AMD E1                         | 3         | 2.03%   |
| AMD Sempron                    | 2         | 1.35%   |
| AMD A4                         | 2         | 1.35%   |
| AMD A10                        | 2         | 1.35%   |
| Intel Pentium Dual-Core        | 1         | 0.68%   |
| Intel Core i9                  | 1         | 0.68%   |
| Intel Atom                     | 1         | 0.68%   |
| AMD V140                       | 1         | 0.68%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.68%   |
| AMD Ryzen 9                    | 1         | 0.68%   |
| AMD Ryzen 5 PRO                | 1         | 0.68%   |
| AMD Ryzen 3                    | 1         | 0.68%   |
| AMD Athlon 64 X2               | 1         | 0.68%   |
| AMD Athlon                     | 1         | 0.68%   |
| AMD A6                         | 1         | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 69        | 46.62%  |
| 4       | 51        | 34.46%  |
| 6       | 13        | 8.78%   |
| 8       | 11        | 7.43%   |
| 1       | 2         | 1.35%   |
| 10      | 1         | 0.68%   |
| Unknown | 1         | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 148       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 99        | 66.89%  |
| 1       | 48        | 32.43%  |
| Unknown | 1         | 0.68%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 145       | 97.97%  |
| Unknown        | 3         | 2.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 25.83%  |
| 0x806ea    | 9         | 5.96%   |
| 0x206a7    | 8         | 5.3%    |
| 0x05000119 | 8         | 5.3%    |
| 0x806ec    | 7         | 4.64%   |
| 0x40651    | 5         | 3.31%   |
| 0x906ea    | 4         | 2.65%   |
| 0x406e3    | 4         | 2.65%   |
| 0x306c3    | 4         | 2.65%   |
| 0x306a9    | 4         | 2.65%   |
| 0x08600106 | 4         | 2.65%   |
| 0x806e9    | 3         | 1.99%   |
| 0x706a1    | 3         | 1.99%   |
| 0x506c9    | 3         | 1.99%   |
| 0x306d4    | 3         | 1.99%   |
| 0x0a50000c | 3         | 1.99%   |
| 0xa0652    | 2         | 1.32%   |
| 0x806c1    | 2         | 1.32%   |
| 0x706e5    | 2         | 1.32%   |
| 0x406c4    | 2         | 1.32%   |
| 0x30678    | 2         | 1.32%   |
| 0x08608103 | 2         | 1.32%   |
| 0x08108109 | 2         | 1.32%   |
| 0x08108102 | 2         | 1.32%   |
| 0x06001119 | 2         | 1.32%   |
| 0x03000027 | 2         | 1.32%   |
| 0x02000057 | 2         | 1.32%   |
| 0x906e9    | 1         | 0.66%   |
| 0x906a4    | 1         | 0.66%   |
| 0x806d1    | 1         | 0.66%   |
| 0x706a8    | 1         | 0.66%   |
| 0x6fd      | 1         | 0.66%   |
| 0x6fb      | 1         | 0.66%   |
| 0x406c3    | 1         | 0.66%   |
| 0x20655    | 1         | 0.66%   |
| 0x20652    | 1         | 0.66%   |
| 0x106e5    | 1         | 0.66%   |
| 0x106ca    | 1         | 0.66%   |
| 0x1067a    | 1         | 0.66%   |
| 0x0a50000b | 1         | 0.66%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 32        | 21.62%  |
| SandyBridge      | 11        | 7.43%   |
| Haswell          | 10        | 6.76%   |
| Bobcat           | 8         | 5.41%   |
| Zen 2            | 7         | 4.73%   |
| Zen 3            | 6         | 4.05%   |
| Silvermont       | 6         | 4.05%   |
| Goldmont plus    | 6         | 4.05%   |
| Zen+             | 5         | 3.38%   |
| Skylake          | 5         | 3.38%   |
| IvyBridge        | 5         | 3.38%   |
| IceLake          | 5         | 3.38%   |
| Broadwell        | 5         | 3.38%   |
| Unknown          | 5         | 3.38%   |
| TigerLake        | 4         | 2.7%    |
| K8 & K10 hybrid  | 3         | 2.03%   |
| Goldmont         | 3         | 2.03%   |
| Core             | 3         | 2.03%   |
| CometLake        | 3         | 2.03%   |
| Westmere         | 2         | 1.35%   |
| Piledriver       | 2         | 1.35%   |
| K10 Llano        | 2         | 1.35%   |
| K10              | 2         | 1.35%   |
| Alderlake Hybrid | 2         | 1.35%   |
| Zen              | 1         | 0.68%   |
| Puma             | 1         | 0.68%   |
| Penryn           | 1         | 0.68%   |
| Nehalem          | 1         | 0.68%   |
| K8 Hammer        | 1         | 0.68%   |
| Bonnell          | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 103       | 53.93%  |
| AMD    | 45        | 23.56%  |
| Nvidia | 43        | 22.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 5.67%   |
| Intel UHD Graphics 620                                                                   | 10        | 5.15%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 7         | 3.61%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 3.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 3.09%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.58%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.58%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.58%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 2.58%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.58%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 5         | 2.58%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 2.06%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 2.06%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.06%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 2.06%   |
| Intel HD Graphics 620                                                                    | 4         | 2.06%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.55%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.55%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.55%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 1.55%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.55%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 3         | 1.55%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 1.55%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 1.03%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 2         | 1.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.03%   |
| Intel HD Graphics 630                                                                    | 2         | 1.03%   |
| Intel HD Graphics 500                                                                    | 2         | 1.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.03%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 1.03%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.03%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.03%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 1.03%   |
| AMD Lucienne                                                                             | 2         | 1.03%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.52%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 65        | 43.92%  |
| Intel + Nvidia | 32        | 21.62%  |
| 1 x AMD        | 32        | 21.62%  |
| AMD + Nvidia   | 6         | 4.05%   |
| 1 x Nvidia     | 5         | 3.38%   |
| Intel + AMD    | 5         | 3.38%   |
| 2 x AMD        | 2         | 1.35%   |
| Other          | 1         | 0.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 125       | 82.78%  |
| Proprietary | 20        | 13.25%  |
| Unknown     | 6         | 3.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 53.59%  |
| 1.01-2.0   | 28        | 18.3%   |
| 0.01-0.5   | 28        | 18.3%   |
| 3.01-4.0   | 9         | 5.88%   |
| 0.51-1.0   | 4         | 2.61%   |
| 7.01-8.0   | 1         | 0.65%   |
| 5.01-6.0   | 1         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 37        | 22.16%  |
| Chimei Innolux          | 26        | 15.57%  |
| LG Display              | 22        | 13.17%  |
| BOE                     | 20        | 11.98%  |
| Samsung Electronics     | 14        | 8.38%   |
| Philips                 | 8         | 4.79%   |
| Dell                    | 6         | 3.59%   |
| Chi Mei Optoelectronics | 5         | 2.99%   |
| PANDA                   | 4         | 2.4%    |
| InfoVision              | 4         | 2.4%    |
| Sharp                   | 3         | 1.8%    |
| Lenovo                  | 3         | 1.8%    |
| CSO                     | 3         | 1.8%    |
| AOC                     | 3         | 1.8%    |
| Goldstar                | 2         | 1.2%    |
| Apple                   | 2         | 1.2%    |
| Valve                   | 1         | 0.6%    |
| Sony                    | 1         | 0.6%    |
| ITE                     | 1         | 0.6%    |
| GreenWood               | 1         | 0.6%    |
| BenQ                    | 1         | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 5         | 2.98%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 2.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 2.38%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 3         | 1.79%   |
| BOE LCD Monitor BOE0747 1920x1080 345x195mm 15.6-inch                 | 3         | 1.79%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 3         | 1.79%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 3         | 1.79%   |
| Philips 223E PHLC049 1920x1080 476x268mm 21.5-inch                    | 2         | 1.19%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 2         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch       | 2         | 1.19%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                 | 2         | 1.19%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 1.19%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.6%    |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch  | 1         | 0.6%    |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.6%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.6%    |
| Sharp LCD Monitor SHP13CF 1280x800 331x207mm 15.4-inch                | 1         | 0.6%    |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch     | 1         | 0.6%    |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 380x300mm 19.1-inch  | 1         | 0.6%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.6%    |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC5842 1366x768 309x174mm 14.0-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3355 1366x768 293x165mm 13.2-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch | 1         | 0.6%    |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch              | 1         | 0.6%    |
| Philips PHL 243S7 PHL090F 1920x1080 527x296mm 23.8-inch               | 1         | 0.6%    |
| Philips PHL 234E5 PHLC0C7 1920x1080 509x286mm 23.0-inch               | 1         | 0.6%    |
| Philips PHL 223V7 PHLC154 1920x1080 476x268mm 21.5-inch               | 1         | 0.6%    |
| Philips 247ELH PHLC085 1920x1080 521x293mm 23.5-inch                  | 1         | 0.6%    |
| Philips 227E4LH PHLC0AC 1920x1080 477x268mm 21.5-inch                 | 1         | 0.6%    |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 73        | 47.4%   |
| 1366x768 (WXGA)    | 47        | 30.52%  |
| 1600x900 (HD+)     | 9         | 5.84%   |
| 2560x1440 (QHD)    | 7         | 4.55%   |
| 1280x800 (WXGA)    | 5         | 3.25%   |
| 3840x2160 (4K)     | 3         | 1.95%   |
| 2560x1600          | 3         | 1.95%   |
| 800x1280           | 1         | 0.65%   |
| 3456x2160          | 1         | 0.65%   |
| 2880x1800          | 1         | 0.65%   |
| 2160x1440          | 1         | 0.65%   |
| 1680x1050 (WSXGA+) | 1         | 0.65%   |
| 1280x1024 (SXGA)   | 1         | 0.65%   |
| 1024x600           | 1         | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 99        | 58.93%  |
| 14     | 15        | 8.93%   |
| 17     | 9         | 5.36%   |
| 13     | 9         | 5.36%   |
| 24     | 6         | 3.57%   |
| 23     | 6         | 3.57%   |
| 27     | 5         | 2.98%   |
| 21     | 5         | 2.98%   |
| 11     | 4         | 2.38%   |
| 16     | 2         | 1.19%   |
| 12     | 2         | 1.19%   |
| 72     | 1         | 0.6%    |
| 31     | 1         | 0.6%    |
| 22     | 1         | 0.6%    |
| 19     | 1         | 0.6%    |
| 10     | 1         | 0.6%    |
| 7      | 1         | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 118       | 70.66%  |
| 501-600     | 15        | 8.98%   |
| 201-300     | 13        | 7.78%   |
| 351-400     | 11        | 6.59%   |
| 401-500     | 6         | 3.59%   |
| 601-700     | 2         | 1.2%    |
| 1501-2000   | 1         | 0.6%    |
| 1-100       | 1         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 130       | 90.28%  |
| 16/10 | 11        | 7.64%   |
| 5/4   | 1         | 0.69%   |
| 3/2   | 1         | 0.69%   |
| 0.67  | 1         | 0.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 99        | 59.28%  |
| 81-90          | 21        | 12.57%  |
| 201-250        | 14        | 8.38%   |
| 121-130        | 7         | 4.19%   |
| 301-350        | 5         | 2.99%   |
| 51-60          | 4         | 2.4%    |
| 71-80          | 3         | 1.8%    |
| 151-200        | 3         | 1.8%    |
| 61-70          | 2         | 1.2%    |
| 131-140        | 2         | 1.2%    |
| 111-120        | 2         | 1.2%    |
| More than 1000 | 1         | 0.6%    |
| 351-500        | 1         | 0.6%    |
| 41-50          | 1         | 0.6%    |
| 1-40           | 1         | 0.6%    |
| 251-300        | 1         | 0.6%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 77        | 46.95%  |
| 101-120       | 53        | 32.32%  |
| 51-100        | 20        | 12.2%   |
| 161-240       | 10        | 6.1%    |
| More than 240 | 3         | 1.83%   |
| 1-50          | 1         | 0.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 123       | 82%     |
| 2     | 25        | 16.67%  |
| 0     | 2         | 1.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 96        | 40.68%  |
| Intel                             | 57        | 24.15%  |
| Qualcomm Atheros                  | 41        | 17.37%  |
| Broadcom                          | 14        | 5.93%   |
| Ralink                            | 4         | 1.69%   |
| MediaTek                          | 4         | 1.69%   |
| Xiaomi                            | 3         | 1.27%   |
| Broadcom Limited                  | 3         | 1.27%   |
| TP-Link                           | 2         | 0.85%   |
| Nvidia                            | 2         | 0.85%   |
| Marvell Technology Group          | 2         | 0.85%   |
| Huawei Technologies               | 2         | 0.85%   |
| Sierra Wireless                   | 1         | 0.42%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.42%   |
| JMicron Technology                | 1         | 0.42%   |
| ICS Advent                        | 1         | 0.42%   |
| Hewlett-Packard                   | 1         | 0.42%   |
| Ericsson Business Mobile Networks | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 61        | 21.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 20        | 7.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 3.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 10        | 3.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 3.23%   |
| Intel Wireless 8265 / 8275                                              | 9         | 3.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 2.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 1.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 1.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.43%   |
| Intel Wireless 7260                                                     | 4         | 1.43%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.43%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.43%   |
| Intel Ethernet Connection I218-LM                                       | 4         | 1.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.43%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 3         | 1.08%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.08%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.08%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.08%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.72%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.72%   |
| Nvidia MCP77 Ethernet                                                   | 2         | 0.72%   |
| Intel Wireless 8260                                                     | 2         | 0.72%   |
| Intel Wireless 3165                                                     | 2         | 0.72%   |
| Intel Wireless 3160                                                     | 2         | 0.72%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                                   | 2         | 0.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 2         | 0.72%   |
| Huawei E353/E3131                                                       | 2         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 54        | 35.76%  |
| Qualcomm Atheros      | 39        | 25.83%  |
| Realtek Semiconductor | 35        | 23.18%  |
| Broadcom              | 11        | 7.28%   |
| Ralink                | 4         | 2.65%   |
| MediaTek              | 4         | 2.65%   |
| TP-Link               | 2         | 1.32%   |
| Sierra Wireless       | 1         | 0.66%   |
| Broadcom Limited      | 1         | 0.66%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 7.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 10        | 6.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 5.96%   |
| Intel Wireless 8265 / 8275                                              | 9         | 5.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 4.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 3.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 3.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 3.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2.65%   |
| Intel Wireless 7260                                                     | 4         | 2.65%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 2.65%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 2.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.99%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.99%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.99%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.99%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 1.32%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.32%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.32%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.32%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.32%   |
| Intel Wireless 8260                                                     | 2         | 1.32%   |
| Intel Wireless 3165                                                     | 2         | 1.32%   |
| Intel Wireless 3160                                                     | 2         | 1.32%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.32%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.32%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.32%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.32%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.66%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.66%   |
| Sierra Wireless EM7455                                                  | 1         | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.66%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.66%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.66%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.66%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]        | 1         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 84        | 67.2%   |
| Intel                    | 19        | 15.2%   |
| Broadcom                 | 5         | 4%      |
| Xiaomi                   | 3         | 2.4%    |
| Qualcomm Atheros         | 3         | 2.4%    |
| Nvidia                   | 2         | 1.6%    |
| Marvell Technology Group | 2         | 1.6%    |
| Huawei Technologies      | 2         | 1.6%    |
| Broadcom Limited         | 2         | 1.6%    |
| JMicron Technology       | 1         | 0.8%    |
| ICS Advent               | 1         | 0.8%    |
| Hewlett-Packard          | 1         | 0.8%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 61        | 48.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 20        | 15.87%  |
| Intel Ethernet Connection I218-LM                                              | 4         | 3.17%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 2.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 1.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 1.59%   |
| Nvidia MCP77 Ethernet                                                          | 2         | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 1.59%   |
| Huawei E353/E3131                                                              | 2         | 1.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 1.59%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.79%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.79%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.79%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.79%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.79%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.79%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.79%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.79%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.79%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.79%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.79%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.79%   |
| Intel Ethernet Connection (16) I219-V                                          | 1         | 0.79%   |
| Intel Ethernet Connection (10) I219-LM                                         | 1         | 0.79%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.79%   |
| Intel 82562GT 10/100 Network Connection                                        | 1         | 0.79%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.79%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 1         | 0.79%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.79%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 0.79%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 0.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 147       | 54.44%  |
| Ethernet | 121       | 44.81%  |
| Modem    | 1         | 0.37%   |
| Unknown  | 1         | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 120       | 77.92%  |
| Ethernet | 34        | 22.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 114       | 77.03%  |
| 1     | 34        | 22.97%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 143       | 96.62%  |
| Yes  | 5         | 3.38%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 37.93%  |
| Realtek Semiconductor           | 17        | 14.66%  |
| IMC Networks                    | 16        | 13.79%  |
| Qualcomm Atheros Communications | 15        | 12.93%  |
| Lite-On Technology              | 5         | 4.31%   |
| Foxconn / Hon Hai               | 5         | 4.31%   |
| Broadcom                        | 5         | 4.31%   |
| Ralink Technology               | 2         | 1.72%   |
| Apple                           | 2         | 1.72%   |
| Toshiba                         | 1         | 0.86%   |
| Realtek                         | 1         | 0.86%   |
| Hewlett-Packard                 | 1         | 0.86%   |
| Dell                            | 1         | 0.86%   |
| Cambridge Silicon Radio         | 1         | 0.86%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 18        | 15.52%  |
| Realtek Bluetooth Radio                                                             | 13        | 11.21%  |
| Intel AX201 Bluetooth                                                               | 11        | 9.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 6.9%    |
| IMC Networks Bluetooth Radio                                                        | 8         | 6.9%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 6.03%   |
| Intel AX200 Bluetooth                                                               | 4         | 3.45%   |
| IMC Networks Bluetooth Device                                                       | 4         | 3.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 2.59%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 3         | 2.59%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 1.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.72%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.72%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 1.72%   |
| Broadcom BCM20702A0                                                                 | 2         | 1.72%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.86%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.86%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.86%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.86%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.86%   |
| Ralink CSR BS8510                                                                   | 1         | 0.86%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.86%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.86%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.86%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.86%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.86%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.86%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.86%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.86%   |
| IMC Networks Bluetooth Module                                                       | 1         | 0.86%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.86%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.86%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.86%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 0.86%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.86%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.86%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.86%   |
| Apple Bluetooth USB Host Controller                                                 | 1         | 0.86%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 106       | 62.35%  |
| AMD         | 40        | 23.53%  |
| Nvidia      | 20        | 11.76%  |
| Plantronics | 2         | 1.18%   |
| Logitech    | 2         | 1.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 22        | 10.09%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 8.72%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 6.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 4.59%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 4.13%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 3.67%   |
| AMD FCH Azalia Controller                                                                         | 8         | 3.67%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 2.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.75%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 2.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 2.29%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.29%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 2.29%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 2.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.83%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.83%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.83%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.38%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.38%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 0.92%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.92%   |
| Logitech H600 [Wireless Headset]                                                                  | 2         | 0.92%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.92%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 0.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.92%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.92%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.92%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.92%   |
| Plantronics Blackwire 3220 Series                                                                 | 1         | 0.46%   |
| Plantronics Audio 622 USB                                                                         | 1         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 32.14%  |
| SK hynix            | 25        | 22.32%  |
| Kingston            | 11        | 9.82%   |
| Micron Technology   | 8         | 7.14%   |
| Unknown             | 7         | 6.25%   |
| Transcend           | 4         | 3.57%   |
| GOODRAM             | 4         | 3.57%   |
| Unknown (ABCD)      | 2         | 1.79%   |
| Ramaxel Technology  | 2         | 1.79%   |
| Elpida              | 2         | 1.79%   |
| Apacer              | 2         | 1.79%   |
| Wilk                | 1         | 0.89%   |
| Unifosa             | 1         | 0.89%   |
| Nanya Technology    | 1         | 0.89%   |
| Crucial             | 1         | 0.89%   |
| Corsair             | 1         | 0.89%   |
| Axiom               | 1         | 0.89%   |
| Avant               | 1         | 0.89%   |
| ASint Technology    | 1         | 0.89%   |
| A-DATA Technology   | 1         | 0.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 2.54%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 2.54%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 2         | 1.69%   |
| Unknown RAM Module 2048MB SODIMM DRAM 667MT/s                       | 2         | 1.69%   |
| Unknown RAM Module 1024MB SODIMM DRAM 667MT/s                       | 2         | 1.69%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 1.69%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 1.69%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 2         | 1.69%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.69%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.69%   |
| Samsung RAM M471B2873FHS-CF8 1GB SODIMM DDR3 1067MT/s               | 2         | 1.69%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.69%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 2         | 1.69%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 2         | 1.69%   |
| Wilk RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s                | 1         | 0.85%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 1         | 0.85%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM DDR2 400MT/s                       | 1         | 0.85%   |
| Unknown RAM Module 1GB SODIMM LPDDR4 2400MT/s                       | 1         | 0.85%   |
| Unifosa RAM GU672203EP0200 1GB SODIMM DDR3 1333MT/s                 | 1         | 0.85%   |
| Transcend RAM TS1GSK64W6H 8GB SODIMM DDR3 1600MT/s                  | 1         | 0.85%   |
| Transcend RAM Module 8192MB SODIMM DDR4 2133MT/s                    | 1         | 0.85%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s               | 1         | 0.85%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s                 | 1         | 0.85%   |
| SK hynix RAM Module 32GB SODIMM DDR4 2667MT/s                       | 1         | 0.85%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM SDRAM                   | 1         | 0.85%   |
| SK hynix RAM HMT451S6MFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.85%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.85%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.85%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s           | 1         | 0.85%   |
| SK hynix RAM HMT125S6TFR8C-H9 2048MB SODIMM DDR3 4199MT/s           | 1         | 0.85%   |
| SK hynix RAM HMCG66AGBSA092N 8GB SODIMM DDR5 5600MT/s               | 1         | 0.85%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s             | 1         | 0.85%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 1         | 0.85%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.85%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 1         | 0.85%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 0.85%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 40        | 41.67%  |
| DDR3   | 38        | 39.58%  |
| LPDDR4 | 5         | 5.21%   |
| SDRAM  | 4         | 4.17%   |
| DDR2   | 3         | 3.13%   |
| LPDDR3 | 2         | 2.08%   |
| DRAM   | 2         | 2.08%   |
| DDR5   | 2         | 2.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 85        | 90.43%  |
| Row Of Chips | 9         | 9.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 33        | 30.84%  |
| 4096  | 32        | 29.91%  |
| 2048  | 16        | 14.95%  |
| 16384 | 14        | 13.08%  |
| 1024  | 7         | 6.54%   |
| 32768 | 5         | 4.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 26        | 25.49%  |
| 2667    | 25        | 24.51%  |
| 3200    | 14        | 13.73%  |
| 2400    | 6         | 5.88%   |
| 1334    | 5         | 4.9%    |
| 1333    | 4         | 3.92%   |
| 667     | 3         | 2.94%   |
| 4800    | 2         | 1.96%   |
| 4199    | 2         | 1.96%   |
| 3266    | 2         | 1.96%   |
| 2133    | 2         | 1.96%   |
| 2048    | 2         | 1.96%   |
| 1067    | 2         | 1.96%   |
| 400     | 2         | 1.96%   |
| Unknown | 2         | 1.96%   |
| 5600    | 1         | 0.98%   |
| 1867    | 1         | 0.98%   |
| 975     | 1         | 0.98%   |

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
| Chicony Electronics                    | 29        | 21.97%  |
| IMC Networks                           | 25        | 18.94%  |
| Realtek Semiconductor                  | 15        | 11.36%  |
| Quanta                                 | 8         | 6.06%   |
| Microdia                               | 8         | 6.06%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 5.3%    |
| Bison Electronics                      | 6         | 4.55%   |
| Syntek                                 | 4         | 3.03%   |
| Sunplus Innovation Technology          | 4         | 3.03%   |
| Silicon Motion                         | 3         | 2.27%   |
| Luxvisions Innotech Limited            | 3         | 2.27%   |
| Lite-On Technology                     | 3         | 2.27%   |
| Acer                                   | 3         | 2.27%   |
| Suyin                                  | 2         | 1.52%   |
| Apple                                  | 2         | 1.52%   |
| Alcor Micro                            | 2         | 1.52%   |
| Z-Star Microelectronics                | 1         | 0.76%   |
| Sonix Technology                       | 1         | 0.76%   |
| Samsung Electronics                    | 1         | 0.76%   |
| Ricoh                                  | 1         | 0.76%   |
| Primax Electronics                     | 1         | 0.76%   |
| Importek                               | 1         | 0.76%   |
| ezcap                                  | 1         | 0.76%   |
| ALi                                    | 1         | 0.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                           | 6         | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 6         | 4.55%   |
| Chicony Integrated Camera                                    | 6         | 4.55%   |
| Realtek Integrated_Webcam_HD                                 | 5         | 3.79%   |
| IMC Networks Integrated Camera                               | 4         | 3.03%   |
| Syntek Lenovo EasyCamera                                     | 3         | 2.27%   |
| Quanta HP TrueVision HD Camera                               | 3         | 2.27%   |
| Quanta HP HD Camera                                          | 3         | 2.27%   |
| Microdia Integrated_Webcam_HD                                | 3         | 2.27%   |
| Chicony HD WebCam                                            | 3         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 3         | 2.27%   |
| Silicon Motion WebCam SC-0311139N                            | 2         | 1.52%   |
| Realtek USB Camera                                           | 2         | 1.52%   |
| Realtek EasyCamera                                           | 2         | 1.52%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 2         | 1.52%   |
| Lite-On HP HD Webcam                                         | 2         | 1.52%   |
| IMC Networks VGA UVC WebCam                                  | 2         | 1.52%   |
| Chicony USB2.0 VGA UVC WebCam                                | 2         | 1.52%   |
| Chicony Integrated Camera (1280x720@30)                      | 2         | 1.52%   |
| Chicony EasyCamera                                           | 2         | 1.52%   |
| Bison Integrated Camera                                      | 2         | 1.52%   |
| Apple FaceTime HD Camera                                     | 2         | 1.52%   |
| Acer SunplusIT Integrated Camera                             | 2         | 1.52%   |
| Z-Star WebCam SCB-0320N                                      | 1         | 0.76%   |
| Syntek Integrated Camera                                     | 1         | 0.76%   |
| Suyin HP Truevision HD                                       | 1         | 0.76%   |
| Suyin HD WebCam                                              | 1         | 0.76%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.76%   |
| Sunplus Integrated_Webcam_HD                                 | 1         | 0.76%   |
| Sunplus HD WebCam                                            | 1         | 0.76%   |
| Sunplus Asus Webcam                                          | 1         | 0.76%   |
| Sonix USB2.0 HD UVC WebCam                                   | 1         | 0.76%   |
| Silicon Motion WebCam SC-13HDL11939N                         | 1         | 0.76%   |
| Samsung Galaxy series, misc. (MTP mode)                      | 1         | 0.76%   |
| Ricoh Sony Visual Communication Camera                       | 1         | 0.76%   |
| Realtek USB2.0 VGA UVC WebCam                                | 1         | 0.76%   |
| Realtek Integrated Webcam_HD                                 | 1         | 0.76%   |
| Realtek Integrated Webcam                                    | 1         | 0.76%   |
| Realtek HP Truevision HD                                     | 1         | 0.76%   |
| Realtek HP "Truevision HD" laptop camera                     | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 34.48%  |
| Synaptics                  | 7         | 24.14%  |
| Shenzhen Goodix Technology | 4         | 13.79%  |
| Elan Microelectronics      | 4         | 13.79%  |
| Upek                       | 2         | 6.9%    |
| LighTuning Technology      | 1         | 3.45%   |
| AuthenTec                  | 1         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 4         | 13.79%  |
| Shenzhen Goodix  FingerPrint Device                       | 4         | 13.79%  |
| Validity Sensors VFS495 Fingerprint Reader                | 3         | 10.34%  |
| Elan ELAN:Fingerprint                                     | 3         | 10.34%  |
| Validity Sensors VFS 5011 fingerprint sensor              | 2         | 6.9%    |
| Validity Sensors Fingerprint scanner                      | 2         | 6.9%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 2         | 6.9%    |
| Synaptics Fingerprint reader [HP G6]                      | 2         | 6.9%    |
| Validity Sensors VFS Fingerprint sensor                   | 1         | 3.45%   |
| Validity Sensors Synaptics WBDI                           | 1         | 3.45%   |
| Validity Sensors Swipe Fingerprint Sensor                 | 1         | 3.45%   |
| Synaptics TouchPad                                        | 1         | 3.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor               | 1         | 3.45%   |
| Elan ELAN:ARM-M4                                          | 1         | 3.45%   |
| AuthenTec AES2501 Fingerprint Sensor                      | 1         | 3.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 1         | 33.33%  |
| O2 Micro              | 1         | 33.33%  |
| Broadcom              | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1         | 33.33%  |
| O2 Micro OZ776 CCID Smartcard Reader              | 1         | 33.33%  |
| Broadcom 5880                                     | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 101       | 66.45%  |
| 1     | 39        | 25.66%  |
| 2     | 11        | 7.24%   |
| 3     | 1         | 0.66%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 29        | 50.88%  |
| Graphics card         | 16        | 28.07%  |
| Net/wireless          | 4         | 7.02%   |
| Sound                 | 2         | 3.51%   |
| Multimedia controller | 2         | 3.51%   |
| Chipcard              | 2         | 3.51%   |
| Storage               | 1         | 1.75%   |
| Camera                | 1         | 1.75%   |

