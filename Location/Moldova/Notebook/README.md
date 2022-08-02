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

Total: 150

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Ubuntu 18.04           | 12        | 10.71%  |
| Ubuntu 20.04           | 11        | 9.82%   |
| ROSA R10               | 9         | 8.04%   |
| ROSA R11               | 6         | 5.36%   |
| Linux Mint 20.1        | 5         | 4.46%   |
| KDE neon 20.04         | 4         | 3.57%   |
| ROSA R9                | 3         | 2.68%   |
| ROSA R8                | 3         | 2.68%   |
| ROSA R11.1             | 3         | 2.68%   |
| Linux Mint 19.1        | 3         | 2.68%   |
| Fedora 36              | 3         | 2.68%   |
| Fedora 34              | 3         | 2.68%   |
| Arch                   | 3         | 2.68%   |
| Zorin 16               | 2         | 1.79%   |
| Ubuntu 22.04           | 2         | 1.79%   |
| Ubuntu 19.10           | 2         | 1.79%   |
| ROSA R8.1              | 2         | 1.79%   |
| Pop!_OS 21.04          | 2         | 1.79%   |
| OpenMandriva 4.3       | 2         | 1.79%   |
| Manjaro                | 2         | 1.79%   |
| Linux Mint 20.2        | 2         | 1.79%   |
| BlackPanther 18.1      | 2         | 1.79%   |
| Ubuntu 21.04           | 1         | 0.89%   |
| Ubuntu 16.04           | 1         | 0.89%   |
| ROSA 12.2              | 1         | 0.89%   |
| ROSA 12.1              | 1         | 0.89%   |
| Pop!_OS 20.10          | 1         | 0.89%   |
| OpenMandriva 4.50      | 1         | 0.89%   |
| Manjaro 20.2.1         | 1         | 0.89%   |
| Manjaro 20.2           | 1         | 0.89%   |
| Manjaro 19.0.2         | 1         | 0.89%   |
| Manjaro 18.0.4         | 1         | 0.89%   |
| Linux Mint 20.3        | 1         | 0.89%   |
| Linux Mint 20          | 1         | 0.89%   |
| Linux Mint 19.3        | 1         | 0.89%   |
| Kubuntu 20.10          | 1         | 0.89%   |
| Kubuntu 20.04          | 1         | 0.89%   |
| Kali 2021.3            | 1         | 0.89%   |
| Fedora 33              | 1         | 0.89%   |
| Fedora 31              | 1         | 0.89%   |
| Endless 3.7.5          | 1         | 0.89%   |
| Endless 3.6.4          | 1         | 0.89%   |
| Endless 3.6.3          | 1         | 0.89%   |
| Endless 3.4.3-nexthw1  | 1         | 0.89%   |
| Endless 3.3.16-nexthw1 | 1         | 0.89%   |
| Debian Unstable        | 1         | 0.89%   |
| Debian 11              | 1         | 0.89%   |
| BuildRoot 2021.08.2    | 1         | 0.89%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 29        | 27.1%   |
| ROSA         | 25        | 23.36%  |
| Linux Mint   | 13        | 12.15%  |
| Fedora       | 8         | 7.48%   |
| Manjaro      | 6         | 5.61%   |
| KDE neon     | 4         | 3.74%   |
| Pop!_OS      | 3         | 2.8%    |
| OpenMandriva | 3         | 2.8%    |
| Endless      | 3         | 2.8%    |
| Arch         | 3         | 2.8%    |
| Zorin        | 2         | 1.87%   |
| Kubuntu      | 2         | 1.87%   |
| Debian       | 2         | 1.87%   |
| BlackPanther | 2         | 1.87%   |
| Kali         | 1         | 0.93%   |
| BuildRoot    | 1         | 0.93%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.15.0-41-generic                  | 4         | 3.36%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 4         | 3.36%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 4         | 3.36%   |
| 5.8.0-33-generic                   | 3         | 2.52%   |
| 4.9.60-nrj-desktop-1rosa-i586      | 3         | 2.52%   |
| 5.4.0-37-generic                   | 2         | 1.68%   |
| 5.16.7-desktop-1omv4003            | 2         | 1.68%   |
| 5.11.0-7614-generic                | 2         | 1.68%   |
| 5.11.0-41-generic                  | 2         | 1.68%   |
| 5.11.0-34-generic                  | 2         | 1.68%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 2         | 1.68%   |
| 5.10.2-2-MANJARO                   | 2         | 1.68%   |
| 4.9.95-nrj-desktop-2rosa-x86_64    | 2         | 1.68%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 2         | 1.68%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 2         | 1.68%   |
| 4.15.0-desktop-68.5rosa-x86_64     | 2         | 1.68%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 2         | 1.68%   |
| 5.9.3-1-MANJARO                    | 1         | 0.84%   |
| 5.8.18-100.fc31.x86_64             | 1         | 0.84%   |
| 5.8.18-1-MANJARO                   | 1         | 0.84%   |
| 5.8.0-36-generic                   | 1         | 0.84%   |
| 5.8.0-25-lowlatency                | 1         | 0.84%   |
| 5.6.14-desktop-2bP                 | 1         | 0.84%   |
| 5.4.49-nrj-desktop-1rosa-x86_64    | 1         | 0.84%   |
| 5.4.32-generic-2rosa-x86_64        | 1         | 0.84%   |
| 5.4.0-86-generic                   | 1         | 0.84%   |
| 5.4.0-84-generic                   | 1         | 0.84%   |
| 5.4.0-72-generic                   | 1         | 0.84%   |
| 5.4.0-70-generic                   | 1         | 0.84%   |
| 5.4.0-67-generic                   | 1         | 0.84%   |
| 5.4.0-58-generic                   | 1         | 0.84%   |
| 5.4.0-52-generic                   | 1         | 0.84%   |
| 5.4.0-48-generic                   | 1         | 0.84%   |
| 5.4.0-42-generic                   | 1         | 0.84%   |
| 5.4.0-40-generic                   | 1         | 0.84%   |
| 5.3.0-59-generic                   | 1         | 0.84%   |
| 5.3.0-42-generic                   | 1         | 0.84%   |
| 5.3.0-40-generic                   | 1         | 0.84%   |
| 5.3.0-23-generic                   | 1         | 0.84%   |
| 5.18.5-201.fsync.fc36.x86_64       | 1         | 0.84%   |
| 5.18.15-arch1-1                    | 1         | 0.84%   |
| 5.18.13-200.fc36.x86_64            | 1         | 0.84%   |
| 5.18.1-arch1-1                     | 1         | 0.84%   |
| 5.17.3-302.fc36.x86_64             | 1         | 0.84%   |
| 5.16.0-trunk-amd64                 | 1         | 0.84%   |
| 5.15.49-1-MANJARO                  | 1         | 0.84%   |
| 5.15.2                             | 1         | 0.84%   |
| 5.15.0-35-generic                  | 1         | 0.84%   |
| 5.14.7-desktop-1omv4050            | 1         | 0.84%   |
| 5.13.10-200.fc34.x86_64            | 1         | 0.84%   |
| 5.13.0-30-generic                  | 1         | 0.84%   |
| 5.13.0-27-generic                  | 1         | 0.84%   |
| 5.12.9-300.fc34.x86_64             | 1         | 0.84%   |
| 5.12.12-300.fc34.x86_64            | 1         | 0.84%   |
| 5.11.12-300.fc34.x86_64            | 1         | 0.84%   |
| 5.11.0-7620-generic                | 1         | 0.84%   |
| 5.11.0-43-generic                  | 1         | 0.84%   |
| 5.11.0-38-generic                  | 1         | 0.84%   |
| 5.11.0-37-generic                  | 1         | 0.84%   |
| 5.11.0-25-generic                  | 1         | 0.84%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.15.0   | 15        | 12.93%  |
| 5.4.0    | 12        | 10.34%  |
| 5.11.0   | 11        | 9.48%   |
| 4.9.60   | 6         | 5.17%   |
| 5.8.0    | 5         | 4.31%   |
| 5.15.0   | 5         | 4.31%   |
| 5.3.0    | 4         | 3.45%   |
| 4.9.20   | 4         | 3.45%   |
| 5.0.0    | 3         | 2.59%   |
| 4.18.0   | 3         | 2.59%   |
| 5.8.18   | 2         | 1.72%   |
| 5.16.7   | 2         | 1.72%   |
| 5.13.0   | 2         | 1.72%   |
| 5.10.74  | 2         | 1.72%   |
| 5.10.2   | 2         | 1.72%   |
| 5.10.0   | 2         | 1.72%   |
| 4.9.95   | 2         | 1.72%   |
| 4.9.41   | 2         | 1.72%   |
| 4.9.155  | 2         | 1.72%   |
| 5.9.3    | 1         | 0.86%   |
| 5.6.14   | 1         | 0.86%   |
| 5.4.49   | 1         | 0.86%   |
| 5.4.32   | 1         | 0.86%   |
| 5.18.5   | 1         | 0.86%   |
| 5.18.15  | 1         | 0.86%   |
| 5.18.13  | 1         | 0.86%   |
| 5.18.1   | 1         | 0.86%   |
| 5.17.3   | 1         | 0.86%   |
| 5.16.0   | 1         | 0.86%   |
| 5.15.49  | 1         | 0.86%   |
| 5.15.2   | 1         | 0.86%   |
| 5.14.7   | 1         | 0.86%   |
| 5.13.10  | 1         | 0.86%   |
| 5.12.9   | 1         | 0.86%   |
| 5.12.12  | 1         | 0.86%   |
| 5.11.12  | 1         | 0.86%   |
| 5.10.47  | 1         | 0.86%   |
| 5.10.19  | 1         | 0.86%   |
| 5.10.13  | 1         | 0.86%   |
| 5.1.15   | 1         | 0.86%   |
| 5.0.18   | 1         | 0.86%   |
| 4.9.124  | 1         | 0.86%   |
| 4.9.111  | 1         | 0.86%   |
| 4.19.114 | 1         | 0.86%   |
| 4.16.0   | 1         | 0.86%   |
| 4.10.0   | 1         | 0.86%   |
| 4.1.38   | 1         | 0.86%   |
| 4.1.34   | 1         | 0.86%   |
| 4.1.25   | 1         | 0.86%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 15        | 13.39%  |
| 4.15    | 15        | 13.39%  |
| 5.4     | 14        | 12.5%   |
| 5.11    | 12        | 10.71%  |
| 5.10    | 8         | 7.14%   |
| 5.8     | 7         | 6.25%   |
| 5.15    | 7         | 6.25%   |
| 5.3     | 4         | 3.57%   |
| 5.18    | 4         | 3.57%   |
| 5.0     | 4         | 3.57%   |
| 5.16    | 3         | 2.68%   |
| 5.13    | 3         | 2.68%   |
| 4.18    | 3         | 2.68%   |
| 4.1     | 3         | 2.68%   |
| 5.12    | 2         | 1.79%   |
| 5.9     | 1         | 0.89%   |
| 5.6     | 1         | 0.89%   |
| 5.17    | 1         | 0.89%   |
| 5.14    | 1         | 0.89%   |
| 5.1     | 1         | 0.89%   |
| 4.19    | 1         | 0.89%   |
| 4.16    | 1         | 0.89%   |
| 4.10    | 1         | 0.89%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 102       | 94.44%  |
| i686   | 6         | 5.56%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 31        | 28.44%  |
| KDE5            | 24        | 22.02%  |
| KDE4            | 19        | 17.43%  |
| Unknown         | 14        | 12.84%  |
| X-Cinnamon      | 9         | 8.26%   |
| XFCE            | 4         | 3.67%   |
| MATE            | 2         | 1.83%   |
| Cinnamon        | 2         | 1.83%   |
| sway            | 1         | 0.92%   |
| LXQt            | 1         | 0.92%   |
| KDE             | 1         | 0.92%   |
| GNOME Flashback | 1         | 0.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 86        | 80.37%  |
| Wayland | 11        | 10.28%  |
| Unknown | 10        | 9.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 41        | 37.27%  |
| KDM     | 19        | 17.27%  |
| SDDM    | 18        | 16.36%  |
| GDM     | 18        | 16.36%  |
| TDM     | 6         | 5.45%   |
| LightDM | 5         | 4.55%   |
| GDM3    | 3         | 2.73%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 39        | 36.45%  |
| en_US   | 35        | 32.71%  |
| ru_RU   | 19        | 17.76%  |
| ro_RO   | 5         | 4.67%   |
| C       | 3         | 2.8%    |
| en_GB   | 2         | 1.87%   |
| ru_UA   | 1         | 0.93%   |
| nl_NL   | 1         | 0.93%   |
| en_150  | 1         | 0.93%   |
| de_DE   | 1         | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 58        | 54.21%  |
| BIOS | 49        | 45.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 78        | 72.9%   |
| Unknown | 16        | 14.95%  |
| Overlay | 6         | 5.61%   |
| Btrfs   | 5         | 4.67%   |
| Xfs     | 2         | 1.87%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 47        | 43.52%  |
| GPT     | 38        | 35.19%  |
| MBR     | 23        | 21.3%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 99        | 92.52%  |
| Yes       | 8         | 7.48%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 79        | 73.83%  |
| Yes       | 28        | 26.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 25        | 23.58%  |
| ASUSTek Computer    | 23        | 21.7%   |
| Lenovo              | 22        | 20.75%  |
| Dell                | 12        | 11.32%  |
| Acer                | 7         | 6.6%    |
| Toshiba             | 4         | 3.77%   |
| Samsung Electronics | 4         | 3.77%   |
| Timi                | 2         | 1.89%   |
| System76            | 1         | 0.94%   |
| Sony                | 1         | 0.94%   |
| MSI                 | 1         | 0.94%   |
| Jumper              | 1         | 0.94%   |
| HUAWEI              | 1         | 0.94%   |
| Gateway             | 1         | 0.94%   |
| Chuwi               | 1         | 0.94%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop X521IA_D533IA      | 3         | 2.83%   |
| Samsung RV413/RV513                         | 2         | 1.89%   |
| Lenovo Legion Y530-15ICH 81FV               | 2         | 1.89%   |
| HP ProBook 450 G7                           | 2         | 1.89%   |
| HP Compaq Presario CQ60                     | 2         | 1.89%   |
| ASUS VivoBook S15 X510UF                    | 2         | 1.89%   |
| Toshiba TECRA Z40-B                         | 1         | 0.94%   |
| Toshiba Satellite Pro S300L                 | 1         | 0.94%   |
| Toshiba Satellite C55D-A                    | 1         | 0.94%   |
| Toshiba Satellite A210                      | 1         | 0.94%   |
| Timi TM1701                                 | 1         | 0.94%   |
| Timi A35S                                   | 1         | 0.94%   |
| System76 Adder WS                           | 1         | 0.94%   |
| Sony VPCEB1J8E                              | 1         | 0.94%   |
| Samsung R517/R717                           | 1         | 0.94%   |
| Samsung 300E4C/300E5C/300E7C                | 1         | 0.94%   |
| MSI CR610                                   | 1         | 0.94%   |
| Lenovo Y520-15IKBN 80WK                     | 1         | 0.94%   |
| Lenovo V580 20147                           | 1         | 0.94%   |
| Lenovo ThinkPad Yoga 11e 3rd Gen 20G8S0MG00 | 1         | 0.94%   |
| Lenovo ThinkPad X240 20AL0067RT             | 1         | 0.94%   |
| Lenovo ThinkPad X131e 33711T0               | 1         | 0.94%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR002MMX    | 1         | 0.94%   |
| Lenovo ThinkPad T440 20B7S1N809             | 1         | 0.94%   |
| Lenovo ThinkPad E15 Gen 3 20YG004BRT        | 1         | 0.94%   |
| Lenovo ThinkPad E15 Gen 2 20TD003TRT        | 1         | 0.94%   |
| Lenovo ThinkPad E15 Gen 2 20TD002NRA        | 1         | 0.94%   |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 0.94%   |
| Lenovo IdeaPad L340-15API 81LW              | 1         | 0.94%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY        | 1         | 0.94%   |
| Lenovo IdeaPad 5 15ARE05 81YQ               | 1         | 0.94%   |
| Lenovo IdeaPad 330S-14IKB 81F4              | 1         | 0.94%   |
| Lenovo IdeaPad 330-15IKB 81DE               | 1         | 0.94%   |
| Lenovo IdeaPad 330-15IGM 81D1               | 1         | 0.94%   |
| Lenovo IdeaPad 130-15IKB 81H7               | 1         | 0.94%   |
| Lenovo IdeaPad 100-15IBY 80MJ               | 1         | 0.94%   |
| Lenovo G710 20252                           | 1         | 0.94%   |
| Jumper EZbook                               | 1         | 0.94%   |
| HUAWEI NBLK-WAX9X                           | 1         | 0.94%   |
| HP ZBook Fury 15 G7 Mobile Workstation      | 1         | 0.94%   |
| HP ProBook 650 G2                           | 1         | 0.94%   |
| HP ProBook 6465b                            | 1         | 0.94%   |
| HP ProBook 470 G2                           | 1         | 0.94%   |
| HP ProBook 450 G6                           | 1         | 0.94%   |
| HP Pavilion Laptop 15-eh1xxx                | 1         | 0.94%   |
| HP Pavilion dv7                             | 1         | 0.94%   |
| HP Pavilion 17                              | 1         | 0.94%   |
| HP Laptop 15-dw0xxx                         | 1         | 0.94%   |
| HP Laptop 15-da1xxx                         | 1         | 0.94%   |
| HP ENVY m6                                  | 1         | 0.94%   |
| HP ENVY 15                                  | 1         | 0.94%   |
| HP EliteBook 855 G7 Notebook PC             | 1         | 0.94%   |
| HP EliteBook 850 G6                         | 1         | 0.94%   |
| HP EliteBook 8470p                          | 1         | 0.94%   |
| HP EliteBook 820 G3                         | 1         | 0.94%   |
| HP Compaq CQ58                              | 1         | 0.94%   |
| HP Compaq 6910p                             | 1         | 0.94%   |
| HP 635                                      | 1         | 0.94%   |
| HP 550                                      | 1         | 0.94%   |
| Gateway NV55S                               | 1         | 0.94%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 8         | 7.55%   |
| Lenovo IdeaPad     | 8         | 7.55%   |
| HP ProBook         | 6         | 5.66%   |
| ASUS VivoBook      | 6         | 5.66%   |
| Dell Latitude      | 5         | 4.72%   |
| Dell Inspiron      | 5         | 4.72%   |
| Acer Aspire        | 5         | 4.72%   |
| HP EliteBook       | 4         | 3.77%   |
| HP Compaq          | 4         | 3.77%   |
| Toshiba Satellite  | 3         | 2.83%   |
| Lenovo Legion      | 3         | 2.83%   |
| HP Pavilion        | 3         | 2.83%   |
| Samsung RV413      | 2         | 1.89%   |
| HP Laptop          | 2         | 1.89%   |
| HP ENVY            | 2         | 1.89%   |
| Toshiba TECRA      | 1         | 0.94%   |
| Timi TM1701        | 1         | 0.94%   |
| Timi A35S          | 1         | 0.94%   |
| System76 Adder     | 1         | 0.94%   |
| Sony VPCEB1J8E     | 1         | 0.94%   |
| Samsung R517       | 1         | 0.94%   |
| Samsung 300E4C     | 1         | 0.94%   |
| MSI CR610          | 1         | 0.94%   |
| Lenovo Y520-15IKBN | 1         | 0.94%   |
| Lenovo V580        | 1         | 0.94%   |
| Lenovo G710        | 1         | 0.94%   |
| Jumper EZbook      | 1         | 0.94%   |
| HUAWEI NBLK-WAX9X  | 1         | 0.94%   |
| HP ZBook           | 1         | 0.94%   |
| HP 635             | 1         | 0.94%   |
| HP 550             | 1         | 0.94%   |
| Gateway NV55S      | 1         | 0.94%   |
| Dell XPS           | 1         | 0.94%   |
| Dell Vostro        | 1         | 0.94%   |
| Chuwi GemiBook     | 1         | 0.94%   |
| ASUS ZenBook       | 1         | 0.94%   |
| ASUS X555LJ        | 1         | 0.94%   |
| ASUS X555LD        | 1         | 0.94%   |
| ASUS X550JX        | 1         | 0.94%   |
| ASUS X542UR        | 1         | 0.94%   |
| ASUS X541SA        | 1         | 0.94%   |
| ASUS X541NC        | 1         | 0.94%   |
| ASUS X541NA        | 1         | 0.94%   |
| ASUS X200MA        | 1         | 0.94%   |
| ASUS U32U          | 1         | 0.94%   |
| ASUS TUF           | 1         | 0.94%   |
| ASUS Strix         | 1         | 0.94%   |
| ASUS K56CM         | 1         | 0.94%   |
| ASUS K54C          | 1         | 0.94%   |
| ASUS K52N          | 1         | 0.94%   |
| ASUS K50AB         | 1         | 0.94%   |
| ASUS E502SA        | 1         | 0.94%   |
| Acer Swift         | 1         | 0.94%   |
| Acer AO756         | 1         | 0.94%   |
| Unknown            | 1         | 0.94%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 14        | 13.21%  |
| 2018 | 13        | 12.26%  |
| 2011 | 11        | 10.38%  |
| 2021 | 9         | 8.49%   |
| 2017 | 9         | 8.49%   |
| 2012 | 9         | 8.49%   |
| 2013 | 7         | 6.6%    |
| 2020 | 6         | 5.66%   |
| 2016 | 6         | 5.66%   |
| 2015 | 5         | 4.72%   |
| 2014 | 4         | 3.77%   |
| 2009 | 4         | 3.77%   |
| 2008 | 4         | 3.77%   |
| 2010 | 3         | 2.83%   |
| 2007 | 2         | 1.89%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 106       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 99        | 93.4%   |
| Enabled  | 7         | 6.6%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 106       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 30        | 28.3%   |
| 3.01-4.0    | 30        | 28.3%   |
| 8.01-16.0   | 18        | 16.98%  |
| 16.01-24.0  | 12        | 11.32%  |
| 32.01-64.0  | 6         | 5.66%   |
| 1.01-2.0    | 5         | 4.72%   |
| 2.01-3.0    | 4         | 3.77%   |
| 64.01-256.0 | 1         | 0.94%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 44        | 39.29%  |
| 2.01-3.0   | 20        | 17.86%  |
| 0.51-1.0   | 17        | 15.18%  |
| 4.01-8.0   | 16        | 14.29%  |
| 3.01-4.0   | 9         | 8.04%   |
| 8.01-16.0  | 4         | 3.57%   |
| 24.01-32.0 | 1         | 0.89%   |
| 16.01-24.0 | 1         | 0.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 87        | 82.08%  |
| 2      | 17        | 16.04%  |
| 3      | 2         | 1.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 72        | 67.92%  |
| Yes       | 34        | 32.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 92        | 85.98%  |
| No        | 15        | 14.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 99.06%  |
| No        | 1         | 0.94%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 71.96%  |
| No        | 30        | 28.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Moldova | 106       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Chisinau        | 70        | 64.22%  |
| Tiraspol        | 12        | 11.01%  |
| Straseni        | 3         | 2.75%   |
| Bălţi         | 3         | 2.75%   |
| Tighina         | 2         | 1.83%   |
| Soroca          | 2         | 1.83%   |
| Hincesti        | 2         | 1.83%   |
| Soldanesti      | 1         | 0.92%   |
| Sofia           | 1         | 0.92%   |
| Rautel          | 1         | 0.92%   |
| Prajila         | 1         | 0.92%   |
| Pociumbeni      | 1         | 0.92%   |
| Ialoveni        | 1         | 0.92%   |
| Gangura         | 1         | 0.92%   |
| Floresti        | 1         | 0.92%   |
| Floreni         | 1         | 0.92%   |
| Donduseni       | 1         | 0.92%   |
| Criuleni        | 1         | 0.92%   |
| Crasnoarmeiscoe | 1         | 0.92%   |
| Cenac           | 1         | 0.92%   |
| Căușeni       | 1         | 0.92%   |
| Cahul           | 1         | 0.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 29     | 18.55%  |
| WDC                 | 16        | 17     | 12.9%   |
| Toshiba             | 15        | 19     | 12.1%   |
| Seagate             | 13        | 15     | 10.48%  |
| Hitachi             | 11        | 12     | 8.87%   |
| Kingston            | 7         | 9      | 5.65%   |
| SanDisk             | 6         | 6      | 4.84%   |
| SK hynix            | 4         | 4      | 3.23%   |
| Micron Technology   | 4         | 6      | 3.23%   |
| Unknown             | 3         | 3      | 2.42%   |
| HGST                | 3         | 3      | 2.42%   |
| Intel               | 2         | 4      | 1.61%   |
| Fujitsu             | 2         | 2      | 1.61%   |
| A-DATA Technology   | 2         | 2      | 1.61%   |
| ZOTAC               | 1         | 3      | 0.81%   |
| Transcend           | 1         | 1      | 0.81%   |
| Solid State Storage | 1         | 1      | 0.81%   |
| Phison              | 1         | 2      | 0.81%   |
| OCZ                 | 1         | 1      | 0.81%   |
| Netac               | 1         | 1      | 0.81%   |
| LITEONIT            | 1         | 1      | 0.81%   |
| Lenovo              | 1         | 1      | 0.81%   |
| KIOXIA              | 1         | 1      | 0.81%   |
| Intenso             | 1         | 1      | 0.81%   |
| Crucial             | 1         | 1      | 0.81%   |
| China               | 1         | 1      | 0.81%   |
| Apacer              | 1         | 1      | 0.81%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB              | 6         | 4.8%    |
| Toshiba MQ01ABD100 1TB                    | 4         | 3.2%    |
| Seagate ST1000LM035-1RK172 1TB            | 4         | 3.2%    |
| Kingston SHFS37A120G 120GB SSD            | 4         | 3.2%    |
| Seagate ST500LT012-9WS142 500GB           | 3         | 2.4%    |
| SanDisk NVMe SSD Drive 512GB              | 3         | 2.4%    |
| Hitachi HTS543232A7A384 320GB             | 3         | 2.4%    |
| WDC WD10SPZX-24Z10T0 1TB                  | 2         | 1.6%    |
| Toshiba MQ04ABF100 1TB                    | 2         | 1.6%    |
| Toshiba MQ01ACF032 320GB                  | 2         | 1.6%    |
| Toshiba MQ01ABF050 500GB                  | 2         | 1.6%    |
| SK hynix NVMe SSD Drive 256GB             | 2         | 1.6%    |
| Samsung SSD 860 EVO 500GB                 | 2         | 1.6%    |
| Micron 1100_MTFDDAV256TBN 256GB SSD       | 2         | 1.6%    |
| Hitachi HTS547575A9E384 752GB             | 2         | 1.6%    |
| ZOTAC ZTSSD-S11-240G-P 240GB              | 1         | 0.8%    |
| WDC WDS512G1X0C-00ENX0 512GB              | 1         | 0.8%    |
| WDC WD5000LPVX-80V0TT0 500GB              | 1         | 0.8%    |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 0.8%    |
| WDC WD5000LPCX-75VHAT1 500GB              | 1         | 0.8%    |
| WDC WD5000BPVT-08HXZT3 500GB              | 1         | 0.8%    |
| WDC WD5000BEVT-22A0RT0 500GB              | 1         | 0.8%    |
| WDC WD3200BPVT-80JJ5T0 320GB              | 1         | 0.8%    |
| WDC WD3200BEVT-63ZCT0 320GB               | 1         | 0.8%    |
| WDC WD3200BEVT-22A23T0 320GB              | 1         | 0.8%    |
| WDC WD3200BEVT-00ZCT0 320GB               | 1         | 0.8%    |
| WDC WD1600BEVS-07RST0 160GB               | 1         | 0.8%    |
| WDC WD10SPZX-24Z10 1TB                    | 1         | 0.8%    |
| WDC WD10SPZX-22Z10T1 1TB                  | 1         | 0.8%    |
| WDC WD10SPSX-60A6WT0 1TB                  | 1         | 0.8%    |
| Unknown TO  64GB                          | 1         | 0.8%    |
| Unknown SD/MMC/MS PRO 64GB                | 1         | 0.8%    |
| Unknown MMC Card  64GB                    | 1         | 0.8%    |
| Transcend TS120GMTS420S 120GB SSD         | 1         | 0.8%    |
| Toshiba THNSNJ128GMCU 128GB SSD           | 1         | 0.8%    |
| Toshiba MQ01ABD050 500GB                  | 1         | 0.8%    |
| Toshiba MK1252GSX 120GB                   | 1         | 0.8%    |
| Toshiba KXG60ZNV512G NVMe 512GB           | 1         | 0.8%    |
| Toshiba KXG60ZNV1T02 KIOXIA 1TB           | 1         | 0.8%    |
| Solid State Storage SSSTC CL1-4D256 256GB | 1         | 0.8%    |
| SK hynix BC711 NVMe 512GB                 | 1         | 0.8%    |
| SK hynix BC501 HFM512GDJTNG-8310A 512GB   | 1         | 0.8%    |
| Seagate ST9500325AS 500GB                 | 1         | 0.8%    |
| Seagate ST9250315AS 250GB                 | 1         | 0.8%    |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 0.8%    |
| Seagate ST320LM000 HM321HI 320GB          | 1         | 0.8%    |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 0.8%    |
| SanDisk SD8SN8U128G1001 128GB SSD         | 1         | 0.8%    |
| SanDisk SD8SN8U-256G-1006 256GB SSD       | 1         | 0.8%    |
| SanDisk SD7UB3Q256G1001 256GB SSD         | 1         | 0.8%    |
| Samsung SSD PM871b M.2 2280 256GB         | 1         | 0.8%    |
| Samsung SSD PM851 mSATA 256GB             | 1         | 0.8%    |
| Samsung SSD 980 500GB                     | 1         | 0.8%    |
| Samsung SSD 860 EVO M.2 250GB             | 1         | 0.8%    |
| Samsung SSD 850 EVO 250GB                 | 1         | 0.8%    |
| Samsung SSD 750 EVO 250GB                 | 1         | 0.8%    |
| Samsung NVMe SSD Drive 256GB              | 1         | 0.8%    |
| Samsung MZVLW256HEHP-000L2 256GB          | 1         | 0.8%    |
| Samsung MZVLW256HEHP-00000 256GB          | 1         | 0.8%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 15        | 16     | 26.32%  |
| Seagate | 13        | 15     | 22.81%  |
| Toshiba | 12        | 16     | 21.05%  |
| Hitachi | 11        | 12     | 19.3%   |
| HGST    | 3         | 3      | 5.26%   |
| Fujitsu | 2         | 2      | 3.51%   |
| Unknown | 1         | 1      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 11     | 26.67%  |
| Kingston            | 6         | 8      | 20%     |
| SanDisk             | 3         | 3      | 10%     |
| Micron Technology   | 2         | 2      | 6.67%   |
| ZOTAC               | 1         | 3      | 3.33%   |
| Transcend           | 1         | 1      | 3.33%   |
| Toshiba             | 1         | 1      | 3.33%   |
| OCZ                 | 1         | 1      | 3.33%   |
| Netac               | 1         | 1      | 3.33%   |
| LITEONIT            | 1         | 1      | 3.33%   |
| Intenso             | 1         | 1      | 3.33%   |
| Crucial             | 1         | 1      | 3.33%   |
| China               | 1         | 1      | 3.33%   |
| Apacer              | 1         | 1      | 3.33%   |
| A-DATA Technology   | 1         | 1      | 3.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 57        | 65     | 47.11%  |
| NVMe | 34        | 43     | 28.1%   |
| SSD  | 28        | 37     | 23.14%  |
| MMC  | 2         | 2      | 1.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 78        | 101    | 67.83%  |
| NVMe | 34        | 43     | 29.57%  |
| MMC  | 2         | 2      | 1.74%   |
| SAS  | 1         | 1      | 0.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 60        | 76     | 73.17%  |
| 0.51-1.0   | 22        | 26     | 26.83%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 36        | 32.43%  |
| 101-250    | 36        | 32.43%  |
| 501-1000   | 15        | 13.51%  |
| 51-100     | 8         | 7.21%   |
| 1-20       | 5         | 4.5%    |
| Unknown    | 5         | 4.5%    |
| 21-50      | 3         | 2.7%    |
| 1001-2000  | 3         | 2.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 49        | 42.61%  |
| 21-50    | 20        | 17.39%  |
| 51-100   | 16        | 13.91%  |
| 101-250  | 12        | 10.43%  |
| 251-500  | 9         | 7.83%   |
| Unknown  | 5         | 4.35%   |
| 501-1000 | 4         | 3.48%   |

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
| Works    | 52        | 75     | 46.43%  |
| Detected | 44        | 54     | 39.29%  |
| Malfunc  | 15        | 17     | 13.39%  |
| Failed   | 1         | 1      | 0.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 69        | 53.08%  |
| AMD                            | 26        | 20%     |
| Samsung Electronics            | 15        | 11.54%  |
| SK hynix                       | 4         | 3.08%   |
| SanDisk                        | 4         | 3.08%   |
| Toshiba America Info Systems   | 2         | 1.54%   |
| Nvidia                         | 2         | 1.54%   |
| Micron Technology              | 2         | 1.54%   |
| Solid State Storage Technology | 1         | 0.77%   |
| Phison Electronics             | 1         | 0.77%   |
| Lenovo                         | 1         | 0.77%   |
| KIOXIA                         | 1         | 0.77%   |
| Kingston Technology Company    | 1         | 0.77%   |
| ADATA Technology               | 1         | 0.77%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 17        | 12.14%  |
| Samsung NVMe SSD Controller 980                                                  | 10        | 7.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 10        | 7.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 7         | 5%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 5%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 4.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 4.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 4         | 2.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 2.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 2.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 2.14%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 2.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 2.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 2.14%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 2.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 2.14%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.43%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 2         | 1.43%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 2         | 1.43%   |
| Micron Non-Volatile memory controller                                            | 2         | 1.43%   |
| Intel SSD 660P Series                                                            | 2         | 1.43%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.43%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 1.43%   |
| Solid State Storage Non-Volatile memory controller                               | 1         | 0.71%   |
| SK hynix Non-Volatile memory controller                                          | 1         | 0.71%   |
| SK hynix Gold P31 SSD                                                            | 1         | 0.71%   |
| SK hynix BC511                                                                   | 1         | 0.71%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 1         | 0.71%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.71%   |
| SanDisk WD Black NVMe SSD                                                        | 1         | 0.71%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.71%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 0.71%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.71%   |
| Lenovo Non-Volatile memory controller                                            | 1         | 0.71%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 0.71%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.71%   |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.71%   |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 0.71%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.71%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 1         | 0.71%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 0.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 0.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 1         | 0.71%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 0.71%   |
| AMD SB600 IDE                                                                    | 1         | 0.71%   |
| AMD FCH IDE Controller                                                           | 1         | 0.71%   |
| ADATA Non-Volatile memory controller                                             | 1         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 87        | 63.5%   |
| NVMe | 34        | 24.82%  |
| IDE  | 9         | 6.57%   |
| RAID | 7         | 5.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 75        | 70.75%  |
| AMD    | 31        | 29.25%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.83%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.83%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 2.83%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 3         | 2.83%   |
| AMD E-450 APU with Radeon HD Graphics         | 3         | 2.83%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 1.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.89%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.89%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.89%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.89%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.89%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.89%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.89%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 1.89%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 2         | 1.89%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.89%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.89%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.89%   |
| AMD E-300 APU with Radeon HD Graphics         | 2         | 1.89%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.94%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.94%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.94%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.94%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.94%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.94%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.94%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.94%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 0.94%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.94%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.94%   |
| Intel Core i5-8400H CPU @ 2.50GHz             | 1         | 0.94%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.94%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 1         | 0.94%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 1         | 0.94%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 1         | 0.94%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 0.94%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 1         | 0.94%   |
| Intel Core i5-4200H CPU @ 2.80GHz             | 1         | 0.94%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 1         | 0.94%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 1         | 0.94%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 0.94%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 0.94%   |
| Intel Core i3-5010U CPU @ 2.10GHz             | 1         | 0.94%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 1         | 0.94%   |
| Intel Core i3-4010U CPU @ 1.70GHz             | 1         | 0.94%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 1         | 0.94%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 1         | 0.94%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 1         | 0.94%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 0.94%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 1         | 0.94%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 0.94%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz          | 1         | 0.94%   |
| Intel Core 2 Duo CPU T5270 @ 1.40GHz          | 1         | 0.94%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 1         | 0.94%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 1         | 0.94%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 1         | 0.94%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 26        | 24.53%  |
| Intel Core i7                  | 14        | 13.21%  |
| Intel Core i3                  | 12        | 11.32%  |
| Intel Celeron                  | 9         | 8.49%   |
| AMD Ryzen 5                    | 6         | 5.66%   |
| Intel Pentium                  | 5         | 4.72%   |
| AMD E                          | 5         | 4.72%   |
| AMD Ryzen 7                    | 4         | 3.77%   |
| Other                          | 3         | 2.83%   |
| Intel Core 2 Duo               | 3         | 2.83%   |
| AMD E1                         | 3         | 2.83%   |
| AMD Sempron                    | 2         | 1.89%   |
| AMD A4                         | 2         | 1.89%   |
| AMD A10                        | 2         | 1.89%   |
| Intel Pentium Silver           | 1         | 0.94%   |
| Intel Pentium Dual-Core        | 1         | 0.94%   |
| Intel Core i9                  | 1         | 0.94%   |
| AMD V140                       | 1         | 0.94%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.94%   |
| AMD Ryzen 5 PRO                | 1         | 0.94%   |
| AMD Ryzen 3                    | 1         | 0.94%   |
| AMD Athlon 64 X2               | 1         | 0.94%   |
| AMD Athlon                     | 1         | 0.94%   |
| AMD A6                         | 1         | 0.94%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 55        | 51.89%  |
| 4       | 34        | 32.08%  |
| 6       | 10        | 9.43%   |
| 8       | 4         | 3.77%   |
| 1       | 2         | 1.89%   |
| Unknown | 1         | 0.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 106       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 65        | 61.32%  |
| 1       | 40        | 37.74%  |
| Unknown | 1         | 0.94%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 103       | 97.17%  |
| Unknown        | 3         | 2.83%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 13        | 12.15%  |
| 0x206a7    | 8         | 7.48%   |
| 0x05000119 | 8         | 7.48%   |
| 0x806ea    | 7         | 6.54%   |
| 0x806ec    | 6         | 5.61%   |
| 0x906ea    | 4         | 3.74%   |
| 0x40651    | 4         | 3.74%   |
| 0x306c3    | 4         | 3.74%   |
| 0x08600106 | 4         | 3.74%   |
| 0x806e9    | 3         | 2.8%    |
| 0x506c9    | 3         | 2.8%    |
| 0x406e3    | 3         | 2.8%    |
| 0x306d4    | 3         | 2.8%    |
| 0x306a9    | 3         | 2.8%    |
| 0xa0652    | 2         | 1.87%   |
| 0x806c1    | 2         | 1.87%   |
| 0x706e5    | 2         | 1.87%   |
| 0x706a1    | 2         | 1.87%   |
| 0x406c4    | 2         | 1.87%   |
| 0x30678    | 2         | 1.87%   |
| 0x08608103 | 2         | 1.87%   |
| 0x08108102 | 2         | 1.87%   |
| 0x06001119 | 2         | 1.87%   |
| 0x03000027 | 2         | 1.87%   |
| 0x02000057 | 2         | 1.87%   |
| 0x906e9    | 1         | 0.93%   |
| 0x706a8    | 1         | 0.93%   |
| 0x6fd      | 1         | 0.93%   |
| 0x6fb      | 1         | 0.93%   |
| 0x406c3    | 1         | 0.93%   |
| 0x20652    | 1         | 0.93%   |
| 0x1067a    | 1         | 0.93%   |
| 0x0a50000c | 1         | 0.93%   |
| 0x08108109 | 1         | 0.93%   |
| 0x02000032 | 1         | 0.93%   |
| 0x010000c8 | 1         | 0.93%   |
| 0x0100009f | 1         | 0.93%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 26        | 24.53%  |
| Haswell         | 9         | 8.49%   |
| SandyBridge     | 8         | 7.55%   |
| Bobcat          | 8         | 7.55%   |
| Zen 2           | 6         | 5.66%   |
| Silvermont      | 5         | 4.72%   |
| Zen+            | 3         | 2.83%   |
| TigerLake       | 3         | 2.83%   |
| Skylake         | 3         | 2.83%   |
| K8 & K10 hybrid | 3         | 2.83%   |
| IvyBridge       | 3         | 2.83%   |
| Goldmont plus   | 3         | 2.83%   |
| Goldmont        | 3         | 2.83%   |
| Core            | 3         | 2.83%   |
| Broadwell       | 3         | 2.83%   |
| Piledriver      | 2         | 1.89%   |
| K10 Llano       | 2         | 1.89%   |
| K10             | 2         | 1.89%   |
| IceLake         | 2         | 1.89%   |
| CometLake       | 2         | 1.89%   |
| Unknown         | 2         | 1.89%   |
| Zen 3           | 1         | 0.94%   |
| Westmere        | 1         | 0.94%   |
| Puma            | 1         | 0.94%   |
| Penryn          | 1         | 0.94%   |
| K8 Hammer       | 1         | 0.94%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 73        | 55.3%   |
| AMD    | 32        | 24.24%  |
| Nvidia | 27        | 20.45%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 5.93%   |
| Intel UHD Graphics 620                                                                   | 7         | 5.19%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 4.44%   |
| AMD Renoir                                                                               | 6         | 4.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 3.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 3.7%    |
| Intel HD Graphics 620                                                                    | 4         | 2.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 2.96%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 2.22%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 2.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 2.22%   |
| Intel HD Graphics 5500                                                                   | 3         | 2.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 2.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.22%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 2.22%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 3         | 2.22%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 2.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 2.22%   |
| Nvidia TU117M                                                                            | 2         | 1.48%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1.48%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.48%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 1.48%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 2         | 1.48%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.48%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.48%   |
| Intel HD Graphics 500                                                                    | 2         | 1.48%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.48%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 1.48%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.48%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 1.48%   |
| AMD Lucienne                                                                             | 2         | 1.48%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.74%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.74%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.74%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.74%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.74%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.74%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.74%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.74%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 1         | 0.74%   |
| Nvidia GK107M [GeForce 810M]                                                             | 1         | 0.74%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 1         | 0.74%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                                | 1         | 0.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.74%   |
| Intel HD Graphics 630                                                                    | 1         | 0.74%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1         | 0.74%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 1         | 0.74%   |
| AMD Trinity [Radeon HD 7660G]                                                            | 1         | 0.74%   |
| AMD Topaz PRO [Radeon R5 M255]                                                           | 1         | 0.74%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 0.74%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 0.74%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 0.74%   |
| AMD Sumo [Radeon HD 6480G]                                                               | 1         | 0.74%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 1         | 0.74%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 1         | 0.74%   |
| AMD Richland [Radeon HD 8610G]                                                           | 1         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 49        | 46.23%  |
| 1 x AMD        | 25        | 23.58%  |
| Intel + Nvidia | 21        | 19.81%  |
| 1 x Nvidia     | 4         | 3.77%   |
| Intel + AMD    | 3         | 2.83%   |
| 2 x AMD        | 2         | 1.89%   |
| AMD + Nvidia   | 2         | 1.89%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 91        | 83.49%  |
| Proprietary | 13        | 11.93%  |
| Unknown     | 5         | 4.59%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 50%     |
| 0.01-0.5   | 24        | 21.82%  |
| 1.01-2.0   | 22        | 20%     |
| 3.01-4.0   | 7         | 6.36%   |
| 7.01-8.0   | 1         | 0.91%   |
| 0.51-1.0   | 1         | 0.91%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 31        | 25.62%  |
| LG Display              | 20        | 16.53%  |
| Chimei Innolux          | 18        | 14.88%  |
| Samsung Electronics     | 12        | 9.92%   |
| BOE                     | 10        | 8.26%   |
| Philips                 | 7         | 5.79%   |
| Chi Mei Optoelectronics | 5         | 4.13%   |
| Dell                    | 4         | 3.31%   |
| InfoVision              | 3         | 2.48%   |
| AOC                     | 3         | 2.48%   |
| Sharp                   | 2         | 1.65%   |
| Lenovo                  | 2         | 1.65%   |
| Goldstar                | 2         | 1.65%   |
| PANDA                   | 1         | 0.83%   |
| BenQ                    | 1         | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 4         | 3.28%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 3         | 2.46%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 3         | 2.46%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 2.46%   |
| Philips 223E PHLC049 1920x1080 476x268mm 21.5-inch                    | 2         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 1.64%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch       | 2         | 1.64%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                 | 2         | 1.64%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 1.64%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.82%   |
| Sharp LCD Monitor SHP13CF 1280x800 331x207mm 15.4-inch                | 1         | 0.82%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch     | 1         | 0.82%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch  | 1         | 0.82%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch   | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SEC5842 1366x768 309x174mm 14.0-inch  | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch  | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 340x190mm 15.3-inch  | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch  | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch  | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 331x207mm 15.4-inch  | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 1         | 0.82%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch | 1         | 0.82%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch              | 1         | 0.82%   |
| Philips PHL 243S7 PHL090F 1920x1080 527x296mm 23.8-inch               | 1         | 0.82%   |
| Philips PHL 223V7 PHLC154 1920x1080 476x268mm 21.5-inch               | 1         | 0.82%   |
| Philips 247ELH PHLC085 1920x1080 521x293mm 23.5-inch                  | 1         | 0.82%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                 | 1         | 0.82%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.82%   |
| LG Display LP156WH1-TLA3 LGD01C2 1366x768 344x194mm 15.5-inch         | 1         | 0.82%   |
| LG Display LCD Monitor LGD06E0 1920x1080 344x194mm 15.5-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD05CE 1920x1080 344x194mm 15.5-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 1         | 0.82%   |
| LG Display LCD Monitor LGD0468 1366x768 344x194mm 15.5-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD03FC 1600x900 309x174mm 14.0-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD03ED 1366x768 277x156mm 12.5-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD03E0 1366x768 345x194mm 15.6-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch           | 1         | 0.82%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch           | 1         | 0.82%   |
| Lenovo Q27q-10 LEN65F4 2560x1440 597x336mm 27.0-inch                  | 1         | 0.82%   |
| Lenovo LCD Monitor LEN40D1 1366x768 256x144mm 11.6-inch               | 1         | 0.82%   |
| InfoVision LCD Monitor IVO057E 1366x768 309x174mm 14.0-inch           | 1         | 0.82%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 1         | 0.82%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch           | 1         | 0.82%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                  | 1         | 0.82%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 1         | 0.82%   |
| Dell U2715H DELD067 2560x1440 597x336mm 27.0-inch                     | 1         | 0.82%   |
| Dell SE2419H DELF109 1920x1080 527x296mm 23.8-inch                    | 1         | 0.82%   |
| Dell P2419HC DELA11C 1920x1080 527x296mm 23.8-inch                    | 1         | 0.82%   |
| Dell P2417H DELA0DC 1920x1080 530x300mm 24.0-inch                     | 1         | 0.82%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch      | 1         | 0.82%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch       | 1         | 0.82%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 47        | 42.34%  |
| 1366x768 (WXGA)    | 43        | 38.74%  |
| 1600x900 (HD+)     | 8         | 7.21%   |
| 3840x2160 (4K)     | 3         | 2.7%    |
| 2560x1440 (QHD)    | 3         | 2.7%    |
| 1280x800 (WXGA)    | 3         | 2.7%    |
| 3456x2160          | 1         | 0.9%    |
| 2160x1440          | 1         | 0.9%    |
| 1680x1050 (WSXGA+) | 1         | 0.9%    |
| 1280x1024 (SXGA)   | 1         | 0.9%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 73        | 60.33%  |
| 14     | 9         | 7.44%   |
| 17     | 6         | 4.96%   |
| 13     | 6         | 4.96%   |
| 24     | 5         | 4.13%   |
| 21     | 5         | 4.13%   |
| 27     | 4         | 3.31%   |
| 23     | 4         | 3.31%   |
| 11     | 4         | 3.31%   |
| 12     | 2         | 1.65%   |
| 31     | 1         | 0.83%   |
| 22     | 1         | 0.83%   |
| 19     | 1         | 0.83%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 84        | 70%     |
| 501-600     | 11        | 9.17%   |
| 201-300     | 9         | 7.5%    |
| 351-400     | 8         | 6.67%   |
| 401-500     | 6         | 5%      |
| 601-700     | 2         | 1.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 96        | 93.2%   |
| 16/10 | 5         | 4.85%   |
| 5/4   | 1         | 0.97%   |
| 3/2   | 1         | 0.97%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 73        | 60.83%  |
| 81-90          | 13        | 10.83%  |
| 201-250        | 12        | 10%     |
| 51-60          | 4         | 3.33%   |
| 301-350        | 4         | 3.33%   |
| 121-130        | 4         | 3.33%   |
| 151-200        | 3         | 2.5%    |
| 71-80          | 2         | 1.67%   |
| 61-70          | 2         | 1.67%   |
| 131-140        | 2         | 1.67%   |
| 351-500        | 1         | 0.83%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 52        | 44.44%  |
| 101-120       | 43        | 36.75%  |
| 51-100        | 17        | 14.53%  |
| 161-240       | 3         | 2.56%   |
| More than 240 | 2         | 1.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 87        | 80.56%  |
| 2     | 20        | 18.52%  |
| 0     | 1         | 0.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 69        | 39.88%  |
| Intel                             | 39        | 22.54%  |
| Qualcomm Atheros                  | 35        | 20.23%  |
| Broadcom                          | 10        | 5.78%   |
| Xiaomi                            | 3         | 1.73%   |
| Ralink                            | 3         | 1.73%   |
| Broadcom Limited                  | 3         | 1.73%   |
| Nvidia                            | 2         | 1.16%   |
| TP-Link                           | 1         | 0.58%   |
| Sierra Wireless                   | 1         | 0.58%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.58%   |
| Marvell Technology Group          | 1         | 0.58%   |
| JMicron Technology                | 1         | 0.58%   |
| ICS Advent                        | 1         | 0.58%   |
| Huawei Technologies               | 1         | 0.58%   |
| Hewlett-Packard                   | 1         | 0.58%   |
| Ericsson Business Mobile Networks | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 41        | 20%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 19        | 9.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 9         | 4.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 8         | 3.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 7         | 3.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 7         | 3.41%   |
| Intel Wireless 8265 / 8275                                                     | 6         | 2.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 4         | 1.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                               | 4         | 1.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 4         | 1.95%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 1.46%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 3         | 1.46%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 3         | 1.46%   |
| Intel Wireless 7260                                                            | 3         | 1.46%   |
| Intel Wi-Fi 6 AX201                                                            | 3         | 1.46%   |
| Intel Wi-Fi 6 AX200                                                            | 3         | 1.46%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 3         | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 3         | 1.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2         | 0.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                     | 2         | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)        | 2         | 0.98%   |
| Nvidia MCP77 Ethernet                                                          | 2         | 0.98%   |
| Intel Wireless 8260                                                            | 2         | 0.98%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                  | 2         | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                | 2         | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 2         | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 2         | 0.98%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 0.98%   |
| Broadcom BCM43228 802.11a/b/g/n                                                | 2         | 0.98%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                   | 1         | 0.49%   |
| Sierra Wireless EM7455                                                         | 1         | 0.49%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                       | 1         | 0.49%   |
| Realtek RTL8723DE Wireless Network Adapter                                     | 1         | 0.49%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                         | 1         | 0.49%   |
| Realtek RTL8187B Wireless Adapter                                              | 1         | 0.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.49%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]               | 1         | 0.49%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.49%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 1         | 0.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                               | 1         | 0.49%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                 | 1         | 0.49%   |
| OnePlus (Shenzhen) OnePlus                                                     | 1         | 0.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.49%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.49%   |
| Intel Wireless 7265                                                            | 1         | 0.49%   |
| Intel Wireless 3165                                                            | 1         | 0.49%   |
| Intel Wireless 3160                                                            | 1         | 0.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                | 1         | 0.49%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.49%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.49%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.49%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.49%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.49%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.49%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 34.26%  |
| Qualcomm Atheros      | 33        | 30.56%  |
| Realtek Semiconductor | 25        | 23.15%  |
| Broadcom              | 7         | 6.48%   |
| Ralink                | 3         | 2.78%   |
| TP-Link               | 1         | 0.93%   |
| Sierra Wireless       | 1         | 0.93%   |
| Broadcom Limited      | 1         | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 8.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 7.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 6.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 6.48%   |
| Intel Wireless 8265 / 8275                                              | 6         | 5.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 3.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 3.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.78%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 2.78%   |
| Intel Wireless 7260                                                     | 3         | 2.78%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 2.78%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 2.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.78%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.85%   |
| Intel Wireless 8260                                                     | 2         | 1.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.85%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.85%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 1         | 0.93%   |
| Sierra Wireless EM7455                                                  | 1         | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.93%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.93%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.93%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.93%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]        | 1         | 0.93%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.93%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.93%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.93%   |
| Intel Wireless 7265                                                     | 1         | 0.93%   |
| Intel Wireless 3165                                                     | 1         | 0.93%   |
| Intel Wireless 3160                                                     | 1         | 0.93%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.93%   |
| Intel Centrino Wireless-N 105                                           | 1         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.93%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 1         | 0.93%   |
| Broadcom BCM43227 802.11b/g/n                                           | 1         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 61        | 64.89%  |
| Intel                    | 15        | 15.96%  |
| Xiaomi                   | 3         | 3.19%   |
| Qualcomm Atheros         | 3         | 3.19%   |
| Broadcom                 | 3         | 3.19%   |
| Nvidia                   | 2         | 2.13%   |
| Broadcom Limited         | 2         | 2.13%   |
| Marvell Technology Group | 1         | 1.06%   |
| JMicron Technology       | 1         | 1.06%   |
| ICS Advent               | 1         | 1.06%   |
| Huawei Technologies      | 1         | 1.06%   |
| Hewlett-Packard          | 1         | 1.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 41        | 43.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 19        | 20%     |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 3.16%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 3.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 2.11%   |
| Nvidia MCP77 Ethernet                                                          | 2         | 2.11%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 2.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 1.05%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 1.05%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 1.05%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.05%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 1.05%   |
| Intel Ethernet Connection I219-V                                               | 1         | 1.05%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.05%   |
| Intel Ethernet Connection I217-V                                               | 1         | 1.05%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 1.05%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 1.05%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 1.05%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 1.05%   |
| Intel Ethernet Connection (10) I219-LM                                         | 1         | 1.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 1.05%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 1.05%   |
| Intel 82562GT 10/100 Network Connection                                        | 1         | 1.05%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 1.05%   |
| Huawei E353/E3131                                                              | 1         | 1.05%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 1         | 1.05%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 1.05%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 1.05%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 1.05%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 105       | 52.76%  |
| Ethernet | 92        | 46.23%  |
| Modem    | 1         | 0.5%    |
| Unknown  | 1         | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 80        | 73.39%  |
| Ethernet | 29        | 26.61%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 85        | 80.19%  |
| 1     | 21        | 19.81%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 103       | 97.17%  |
| Yes  | 3         | 2.83%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 29        | 37.66%  |
| Qualcomm Atheros Communications | 12        | 15.58%  |
| Realtek Semiconductor           | 11        | 14.29%  |
| IMC Networks                    | 9         | 11.69%  |
| Broadcom                        | 5         | 6.49%   |
| Lite-On Technology              | 4         | 5.19%   |
| Foxconn / Hon Hai               | 2         | 2.6%    |
| Toshiba                         | 1         | 1.3%    |
| Realtek                         | 1         | 1.3%    |
| Ralink Technology               | 1         | 1.3%    |
| Hewlett-Packard                 | 1         | 1.3%    |
| Dell                            | 1         | 1.3%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 13        | 16.88%  |
| Realtek Bluetooth Radio                                                             | 9         | 11.69%  |
| Intel AX201 Bluetooth                                                               | 7         | 9.09%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 7.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 7.79%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 5.19%   |
| IMC Networks Bluetooth Device                                                       | 4         | 5.19%   |
| Intel AX200 Bluetooth                                                               | 3         | 3.9%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 2.6%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 2.6%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 2.6%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 2.6%    |
| Broadcom BCM20702A0                                                                 | 2         | 2.6%    |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 1.3%    |
| Realtek Bluetooth Radio                                                             | 1         | 1.3%    |
| Ralink CSR BS8510                                                                   | 1         | 1.3%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.3%    |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 1.3%    |
| Lite-On Bluetooth Device                                                            | 1         | 1.3%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.3%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 1.3%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.3%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.3%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.3%    |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.3%    |
| Broadcom HP Portable SoftSailing                                                    | 1         | 1.3%    |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 1.3%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 1.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Intel       | 75        | 63.56%  |
| AMD         | 29        | 24.58%  |
| Nvidia      | 11        | 9.32%   |
| Logitech    | 2         | 1.69%   |
| Plantronics | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 14        | 9.03%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 7.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 5.81%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 5.16%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 5.16%   |
| AMD FCH Azalia Controller                                                                         | 8         | 5.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 4.52%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 3.87%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.23%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 3.23%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 2.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.58%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 4         | 2.58%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.94%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.94%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.94%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.29%   |
| Logitech H600 [Wireless Headset]                                                                  | 2         | 1.29%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.29%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.29%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 1.29%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 1.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 2         | 1.29%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 1.29%   |
| Plantronics Audio 622 USB                                                                         | 1         | 0.65%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.65%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.65%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 0.65%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 25        | 31.25%  |
| SK hynix            | 17        | 21.25%  |
| Kingston            | 7         | 8.75%   |
| Micron Technology   | 6         | 7.5%    |
| Unknown             | 5         | 6.25%   |
| Goodram             | 4         | 5%      |
| Unknown (ABCD)      | 2         | 2.5%    |
| Transcend           | 2         | 2.5%    |
| Ramaxel Technology  | 2         | 2.5%    |
| Elpida              | 2         | 2.5%    |
| Unifosa             | 1         | 1.25%   |
| Nanya Technology    | 1         | 1.25%   |
| Crucial             | 1         | 1.25%   |
| Corsair             | 1         | 1.25%   |
| Axiom               | 1         | 1.25%   |
| ASint Technology    | 1         | 1.25%   |
| Apacer              | 1         | 1.25%   |
| A-DATA Technology   | 1         | 1.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 3.53%   |
| Unknown RAM Module 2048MB SODIMM DRAM 667MT/s                    | 2         | 2.35%   |
| Unknown RAM Module 1024MB SODIMM DRAM 667MT/s                    | 2         | 2.35%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 2         | 2.35%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.35%   |
| Samsung RAM M471B2873FHS-CF8 1024MB SODIMM DDR3 1067MT/s         | 2         | 2.35%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.18%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.18%   |
| Unknown RAM Module 2048MB SODIMM DDR2 400MT/s                    | 1         | 1.18%   |
| Unifosa RAM GU672203EP0200 1GB SODIMM DDR3 1333MT/s              | 1         | 1.18%   |
| Transcend RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 1         | 1.18%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s           | 1         | 1.18%   |
| SK hynix RAM Module 32GB SODIMM DDR4 2667MT/s                    | 1         | 1.18%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM SDRAM 2048MT/s          | 1         | 1.18%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 1.18%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s        | 1         | 1.18%   |
| SK hynix RAM HMT125S6TFR8C-H9 2048MB SODIMM DDR3 4199MT/s        | 1         | 1.18%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 1.18%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.18%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 1         | 1.18%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| SK hynix RAM H9HCNNNCPMALHR-NEE 8GB Row Of Chips LPDDR4 4800MT/s | 1         | 1.18%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.18%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.18%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 1         | 1.18%   |
| Samsung RAM M471B5273DH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471B5173BH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.18%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CWE 4096MB Row Of Chips DDR4 3200MT/s   | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s   | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.18%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 1.18%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.18%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.18%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.18%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.18%   |
| Samsung RAM M4 70T2864EH3-CF7 1024MB SODIMM DDR2 2048MT/s        | 1         | 1.18%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s     | 1         | 1.18%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.18%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.18%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s             | 1         | 1.18%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 1         | 1.18%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 1.18%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 1         | 1.18%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 1         | 1.18%   |
| Kingston RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.18%   |
| Kingston RAM Module 2048MB SODIMM DDR2 400MT/s                   | 1         | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 31        | 43.66%  |
| DDR4   | 25        | 35.21%  |
| SDRAM  | 4         | 5.63%   |
| LPDDR4 | 4         | 5.63%   |
| DDR2   | 3         | 4.23%   |
| LPDDR3 | 2         | 2.82%   |
| DRAM   | 2         | 2.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 62        | 91.18%  |
| Row Of Chips | 6         | 8.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 31        | 40.26%  |
| 8192  | 19        | 24.68%  |
| 2048  | 13        | 16.88%  |
| 16384 | 6         | 7.79%   |
| 1024  | 6         | 7.79%   |
| 32768 | 2         | 2.6%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 22        | 29.33%  |
| 2667    | 18        | 24%     |
| 3200    | 5         | 6.67%   |
| 1334    | 5         | 6.67%   |
| 2400    | 4         | 5.33%   |
| 1333    | 4         | 5.33%   |
| 4199    | 2         | 2.67%   |
| 2133    | 2         | 2.67%   |
| 2048    | 2         | 2.67%   |
| 1067    | 2         | 2.67%   |
| 667     | 2         | 2.67%   |
| 400     | 2         | 2.67%   |
| 4800    | 1         | 1.33%   |
| 3266    | 1         | 1.33%   |
| 1867    | 1         | 1.33%   |
| 975     | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

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
| Chicony Electronics                    | 22        | 22.68%  |
| IMC Networks                           | 21        | 21.65%  |
| Realtek Semiconductor                  | 12        | 12.37%  |
| Microdia                               | 7         | 7.22%   |
| Acer                                   | 6         | 6.19%   |
| Quanta                                 | 4         | 4.12%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.12%   |
| Syntek                                 | 3         | 3.09%   |
| Sunplus Innovation Technology          | 3         | 3.09%   |
| Silicon Motion                         | 3         | 3.09%   |
| Lite-On Technology                     | 3         | 3.09%   |
| Suyin                                  | 2         | 2.06%   |
| Luxvisions Innotech Limited            | 2         | 2.06%   |
| Alcor Micro                            | 2         | 2.06%   |
| Z-Star Microelectronics                | 1         | 1.03%   |
| Samsung Electronics                    | 1         | 1.03%   |
| Importek                               | 1         | 1.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 5         | 5.15%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 4         | 4.12%   |
| IMC Networks Integrated Camera                                             | 4         | 4.12%   |
| Chicony Integrated Camera                                                  | 4         | 4.12%   |
| Realtek Integrated_Webcam_HD                                               | 3         | 3.09%   |
| Quanta HP HD Camera                                                        | 3         | 3.09%   |
| Chicony HD WebCam                                                          | 3         | 3.09%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 2.06%   |
| Silicon Motion WebCam SC-0311139N                                          | 2         | 2.06%   |
| Realtek USB Camera                                                         | 2         | 2.06%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 2         | 2.06%   |
| Microdia Integrated_Webcam_HD                                              | 2         | 2.06%   |
| Lite-On HP HD Camera                                                       | 2         | 2.06%   |
| IMC Networks VGA UVC WebCam                                                | 2         | 2.06%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 2.06%   |
| Chicony Integrated Camera (1280x720@30)                                    | 2         | 2.06%   |
| Chicony EasyCamera                                                         | 2         | 2.06%   |
| Z-Star WebCam SCB-0320N                                                    | 1         | 1.03%   |
| Syntek Integrated Camera                                                   | 1         | 1.03%   |
| Suyin HP Truevision HD                                                     | 1         | 1.03%   |
| Suyin HD WebCam                                                            | 1         | 1.03%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 1.03%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 1.03%   |
| Sunplus HD Webcam                                                          | 1         | 1.03%   |
| Silicon Motion WebCam SC-13HDL11939N                                       | 1         | 1.03%   |
| Samsung Galaxy A5 (MTP)                                                    | 1         | 1.03%   |
| Realtek USB2.0 VGA UVC WebCam                                              | 1         | 1.03%   |
| Realtek Integrated Webcam_HD                                               | 1         | 1.03%   |
| Realtek Integrated Webcam HD                                               | 1         | 1.03%   |
| Realtek HP Truevision HD                                                   | 1         | 1.03%   |
| Realtek HP "Truevision HD" laptop camera                                   | 1         | 1.03%   |
| Realtek HD WebCam                                                          | 1         | 1.03%   |
| Realtek EasyCamera                                                         | 1         | 1.03%   |
| Quanta HP TrueVision HD Camera                                             | 1         | 1.03%   |
| Microdia Webcam                                                            | 1         | 1.03%   |
| Microdia Integrated Webcam                                                 | 1         | 1.03%   |
| Microdia Amcrest AWC2198 USB Webcam                                        | 1         | 1.03%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 1         | 1.03%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 1         | 1.03%   |
| Lite-On HP HD Webcam                                                       | 1         | 1.03%   |
| Importek TOSHIBA Web Camera - HD                                           | 1         | 1.03%   |
| IMC Networks XiaoMi Webcam                                                 | 1         | 1.03%   |
| IMC Networks UVC VGA Webcam                                                | 1         | 1.03%   |
| IMC Networks USB2.0 HD IR UVC WebCam                                       | 1         | 1.03%   |
| IMC Networks USB Camera                                                    | 1         | 1.03%   |
| IMC Networks ov9734_azurewave_camera                                       | 1         | 1.03%   |
| IMC Networks Integrated Webcam                                             | 1         | 1.03%   |
| Chicony USB2.0 HD UVC WebCam                                               | 1         | 1.03%   |
| Chicony USB2.0 0.3M UVC WebCam                                             | 1         | 1.03%   |
| Chicony USB 2.0 Camera                                                     | 1         | 1.03%   |
| Chicony TOSHIBA Web Camera - FHD                                           | 1         | 1.03%   |
| Chicony HP Webcam                                                          | 1         | 1.03%   |
| Chicony HP HD Webcam [Fixed]                                               | 1         | 1.03%   |
| Chicony HP HD Webcam                                                       | 1         | 1.03%   |
| Chicony HP HD Camera                                                       | 1         | 1.03%   |
| Chicony 1.3M Webcam                                                        | 1         | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam               | 1         | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 1         | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101                       | 1         | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 1         | 1.03%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 37.5%   |
| Synaptics                  | 7         | 29.17%  |
| Shenzhen Goodix Technology | 3         | 12.5%   |
| Elan Microelectronics      | 2         | 8.33%   |
| Upek                       | 1         | 4.17%   |
| LighTuning Technology      | 1         | 4.17%   |
| AuthenTec                  | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 4         | 16.67%  |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 8.33%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 8.33%   |
| Validity Sensors Fingerprint scanner                       | 2         | 8.33%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 8.33%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 4.17%   |
| Validity Sensors Synaptics WBDI                            | 1         | 4.17%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 4.17%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 4.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 4.17%   |
| Elan ELAN:Fingerprint                                      | 1         | 4.17%   |
| Elan ELAN:ARM-M4                                           | 1         | 4.17%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 4.17%   |
| Unknown                                                    | 1         | 4.17%   |

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
| 0     | 68        | 61.82%  |
| 1     | 34        | 30.91%  |
| 2     | 7         | 6.36%   |
| 3     | 1         | 0.91%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 24        | 51.06%  |
| Graphics card         | 12        | 25.53%  |
| Net/wireless          | 4         | 8.51%   |
| Multimedia controller | 2         | 4.26%   |
| Chipcard              | 2         | 4.26%   |
| Storage               | 1         | 2.13%   |
| Sound                 | 1         | 2.13%   |
| Camera                | 1         | 2.13%   |

