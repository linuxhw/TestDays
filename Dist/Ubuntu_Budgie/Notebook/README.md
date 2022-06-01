Ubuntu Budgie - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie.

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

Total: 410

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 5570               | [ea74ff47bc](https://linux-hardware.org/?probe=ea74ff47bc) | May 27, 2022 |
| Dell          | Inspiron 5570               | [83e0c49ab0](https://linux-hardware.org/?probe=83e0c49ab0) | May 27, 2022 |
| HP            | Pavilion g6                 | [ef71909561](https://linux-hardware.org/?probe=ef71909561) | May 26, 2022 |
| HP            | Pavilion g6                 | [41d1e81397](https://linux-hardware.org/?probe=41d1e81397) | May 26, 2022 |
| Chuwi         | HeroBook Pro                | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [b128814505](https://linux-hardware.org/?probe=b128814505) | May 21, 2022 |
| Apple         | MacBookPro5,4               | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| Avell High... | B.ON                        | [9069ca4c66](https://linux-hardware.org/?probe=9069ca4c66) | May 13, 2022 |
| MSI           | Modern 15 A10M              | [88c226c079](https://linux-hardware.org/?probe=88c226c079) | May 09, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [296dc11e4b](https://linux-hardware.org/?probe=296dc11e4b) | May 08, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [ca08dea33b](https://linux-hardware.org/?probe=ca08dea33b) | May 07, 2022 |
| Google        | Boten                       | [6204cff7de](https://linux-hardware.org/?probe=6204cff7de) | May 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4f2714e3fe](https://linux-hardware.org/?probe=4f2714e3fe) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [ff291ff9e3](https://linux-hardware.org/?probe=ff291ff9e3) | May 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [0c5f20e02c](https://linux-hardware.org/?probe=0c5f20e02c) | May 02, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [0d006e41fc](https://linux-hardware.org/?probe=0d006e41fc) | May 01, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [ef265ae548](https://linux-hardware.org/?probe=ef265ae548) | Apr 29, 2022 |
| Sony          | SVS13A25PBS                 | [c1be74b619](https://linux-hardware.org/?probe=c1be74b619) | Apr 25, 2022 |
| Acer          | Swift SF315-52              | [089d81a936](https://linux-hardware.org/?probe=089d81a936) | Apr 23, 2022 |
| Apple         | MacBookPro9,2               | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| Dell          | XPS 13 9305                 | [51daefb9d3](https://linux-hardware.org/?probe=51daefb9d3) | Apr 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [3b76e2f5ab](https://linux-hardware.org/?probe=3b76e2f5ab) | Apr 21, 2022 |
| Lenovo        | ThinkPad T430s 2356H83      | [714396bc62](https://linux-hardware.org/?probe=714396bc62) | Apr 20, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [70547d6581](https://linux-hardware.org/?probe=70547d6581) | Apr 19, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | [c1a5e02fa5](https://linux-hardware.org/?probe=c1a5e02fa5) | Apr 17, 2022 |
| Acer          | Swift SF114-34              | [ca66ed7272](https://linux-hardware.org/?probe=ca66ed7272) | Apr 14, 2022 |
| Dell          | Inspiron 5570               | [a75a1551fa](https://linux-hardware.org/?probe=a75a1551fa) | Apr 09, 2022 |
| Alienware     | m15                         | [0cd462faaa](https://linux-hardware.org/?probe=0cd462faaa) | Apr 07, 2022 |
| Lenovo        | ThinkPad E490 20N9001MBR    | [1b041100a3](https://linux-hardware.org/?probe=1b041100a3) | Apr 07, 2022 |
| TUXEDO        | Aura 15 Gen1                | [cda73dafa0](https://linux-hardware.org/?probe=cda73dafa0) | Apr 04, 2022 |
| TUXEDO        | InfinityBook S 14 v5        | [6a5061e741](https://linux-hardware.org/?probe=6a5061e741) | Apr 03, 2022 |
| Dell          | Inspiron 14 5401            | [995691e022](https://linux-hardware.org/?probe=995691e022) | Apr 01, 2022 |
| TUXEDO        | InfinityBook S 14 Gen6      | [847b8f0788](https://linux-hardware.org/?probe=847b8f0788) | Apr 01, 2022 |
| Packard Be... | ENLE11BZ                    | [4fb836698c](https://linux-hardware.org/?probe=4fb836698c) | Mar 26, 2022 |
| ASUSTek       | G752VY                      | [2b82008ffc](https://linux-hardware.org/?probe=2b82008ffc) | Mar 23, 2022 |
| Apple         | MacBookPro15,1              | [0fe3cba205](https://linux-hardware.org/?probe=0fe3cba205) | Mar 23, 2022 |
| ASUSTek       | G752VY                      | [ffc0cdf0bd](https://linux-hardware.org/?probe=ffc0cdf0bd) | Mar 22, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [63ea3e99c5](https://linux-hardware.org/?probe=63ea3e99c5) | Mar 14, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [08525a320d](https://linux-hardware.org/?probe=08525a320d) | Mar 13, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | [b61991cef4](https://linux-hardware.org/?probe=b61991cef4) | Mar 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [22452f39c2](https://linux-hardware.org/?probe=22452f39c2) | Mar 11, 2022 |
| HP            | ZBook 15u G6                | [42921aebfd](https://linux-hardware.org/?probe=42921aebfd) | Mar 10, 2022 |
| MSI           | Vector GP66 12UGS           | [be60e729e2](https://linux-hardware.org/?probe=be60e729e2) | Mar 06, 2022 |
| HP            | Pavilion dm4                | [4786fbfbdd](https://linux-hardware.org/?probe=4786fbfbdd) | Mar 04, 2022 |
| HP            | Pavilion dm4                | [8adb026a31](https://linux-hardware.org/?probe=8adb026a31) | Mar 04, 2022 |
| Google        | Rammus                      | [a326a69db9](https://linux-hardware.org/?probe=a326a69db9) | Mar 02, 2022 |
| Google        | Rammus                      | [b395780983](https://linux-hardware.org/?probe=b395780983) | Mar 02, 2022 |
| Apple         | MacBookAir7,2               | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| ASUSTek       | UX303UA                     | [0ed28fa881](https://linux-hardware.org/?probe=0ed28fa881) | Feb 23, 2022 |
| HP            | Compaq Presario C700        | [52cff70be5](https://linux-hardware.org/?probe=52cff70be5) | Feb 21, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [e58eb70913](https://linux-hardware.org/?probe=e58eb70913) | Feb 19, 2022 |
| ASUSTek       | T200TAC                     | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| TUXEDO        | Aura 15 Gen1                | [536a1e49b0](https://linux-hardware.org/?probe=536a1e49b0) | Feb 17, 2022 |
| Samsung       | 305V4A/305V5A               | [07233a144c](https://linux-hardware.org/?probe=07233a144c) | Feb 09, 2022 |
| Lenovo        | G500 20236                  | [2dd47c0a4b](https://linux-hardware.org/?probe=2dd47c0a4b) | Feb 08, 2022 |
| Viglen        | VUB1                        | [13f512e2d1](https://linux-hardware.org/?probe=13f512e2d1) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | [87e9ca3a01](https://linux-hardware.org/?probe=87e9ca3a01) | Feb 07, 2022 |
| Razer         | Blade Stealth               | [de6e279575](https://linux-hardware.org/?probe=de6e279575) | Feb 07, 2022 |
| Razer         | Blade Stealth               | [c85996c28c](https://linux-hardware.org/?probe=c85996c28c) | Feb 07, 2022 |
| HP            | ProBook 440 G5              | [5f6a923aa2](https://linux-hardware.org/?probe=5f6a923aa2) | Feb 05, 2022 |
| HP            | ProBook 440 G5              | [6ff30e8299](https://linux-hardware.org/?probe=6ff30e8299) | Feb 05, 2022 |
| Apple         | MacBookPro11,5              | [46ba4fcc12](https://linux-hardware.org/?probe=46ba4fcc12) | Feb 04, 2022 |
| Acer          | Aspire 8940G                | [686119ea77](https://linux-hardware.org/?probe=686119ea77) | Feb 03, 2022 |
| HP            | Laptop 15s-fq1xxx           | [81f3f014e7](https://linux-hardware.org/?probe=81f3f014e7) | Feb 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [f9e76db452](https://linux-hardware.org/?probe=f9e76db452) | Jan 31, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [74533ff76f](https://linux-hardware.org/?probe=74533ff76f) | Jan 28, 2022 |
| Lenovo        | V145-15AST 81MT             | [07192f2b7d](https://linux-hardware.org/?probe=07192f2b7d) | Jan 27, 2022 |
| Lenovo        | G50-45 80E3                 | [f7fafa6976](https://linux-hardware.org/?probe=f7fafa6976) | Jan 26, 2022 |
| TUXEDO        | Book XP1511                 | [9a62ad3fe4](https://linux-hardware.org/?probe=9a62ad3fe4) | Jan 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [909aca1407](https://linux-hardware.org/?probe=909aca1407) | Jan 22, 2022 |
| Dell          | Latitude 5510               | [ab7eee3de9](https://linux-hardware.org/?probe=ab7eee3de9) | Jan 21, 2022 |
| Lenovo        | G50-45 80E3                 | [e45b9230c9](https://linux-hardware.org/?probe=e45b9230c9) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | [edc7be1068](https://linux-hardware.org/?probe=edc7be1068) | Jan 18, 2022 |
| Lenovo        | G50-45 80E3                 | [98ff0f7580](https://linux-hardware.org/?probe=98ff0f7580) | Jan 17, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [585aa2aa39](https://linux-hardware.org/?probe=585aa2aa39) | Jan 16, 2022 |
| HP            | EliteBook 8570w             | [e324ae4a05](https://linux-hardware.org/?probe=e324ae4a05) | Jan 16, 2022 |
| Viglen        | VUB1                        | [d16d7f30b3](https://linux-hardware.org/?probe=d16d7f30b3) | Jan 16, 2022 |
| HP            | EliteBook 8570w             | [dd6c66b4dc](https://linux-hardware.org/?probe=dd6c66b4dc) | Jan 15, 2022 |
| Lenovo        | V145-15AST 81MT             | [03a777b7b1](https://linux-hardware.org/?probe=03a777b7b1) | Jan 13, 2022 |
| Lenovo        | V145-15AST 81MT             | [43ea5ed123](https://linux-hardware.org/?probe=43ea5ed123) | Jan 12, 2022 |
| EVOO          | EV-C-116-7                  | [3fe03ac079](https://linux-hardware.org/?probe=3fe03ac079) | Jan 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [e55162d481](https://linux-hardware.org/?probe=e55162d481) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [ee6ede67e9](https://linux-hardware.org/?probe=ee6ede67e9) | Jan 02, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [a76fb98d8d](https://linux-hardware.org/?probe=a76fb98d8d) | Jan 01, 2022 |
| Apple         | MacBookPro8,1               | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |
| TUXEDO        | Unknown                     | [339ee3ca1c](https://linux-hardware.org/?probe=339ee3ca1c) | Dec 28, 2021 |
| Lenovo        | V310-15ISK 80SY             | [16855d1282](https://linux-hardware.org/?probe=16855d1282) | Dec 27, 2021 |
| TUXEDO        | Unknown                     | [14323d7f2a](https://linux-hardware.org/?probe=14323d7f2a) | Dec 27, 2021 |
| Acer          | Swift SF314-52              | [67fb871b2f](https://linux-hardware.org/?probe=67fb871b2f) | Dec 24, 2021 |
| TUXEDO        | Aura 15 Gen1                | [c860a1c3c5](https://linux-hardware.org/?probe=c860a1c3c5) | Dec 22, 2021 |
| HP            | Pavilion tx1000             | [a3639ffcd5](https://linux-hardware.org/?probe=a3639ffcd5) | Dec 21, 2021 |
| HP            | Pavilion dm1                | [5e63d24312](https://linux-hardware.org/?probe=5e63d24312) | Dec 17, 2021 |
| GPU Compan... | GWTN156-11                  | [f586c51674](https://linux-hardware.org/?probe=f586c51674) | Dec 17, 2021 |
| Acer          | E3-112M-C6BV                | [81a7f64292](https://linux-hardware.org/?probe=81a7f64292) | Dec 15, 2021 |
| HP            | Pavilion tx1000             | [e568b07f70](https://linux-hardware.org/?probe=e568b07f70) | Dec 14, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [49234a5c74](https://linux-hardware.org/?probe=49234a5c74) | Dec 10, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [7cf830d39e](https://linux-hardware.org/?probe=7cf830d39e) | Dec 10, 2021 |
| Lenovo        | ThinkPad W530 244743G       | [4aff204627](https://linux-hardware.org/?probe=4aff204627) | Dec 10, 2021 |
| Toshiba       | Satellite S55-C             | [b6c63776b5](https://linux-hardware.org/?probe=b6c63776b5) | Dec 10, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [b2d2913170](https://linux-hardware.org/?probe=b2d2913170) | Dec 07, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [429851405d](https://linux-hardware.org/?probe=429851405d) | Dec 07, 2021 |
| Toshiba       | Satellite S55-C             | [9721dbfb66](https://linux-hardware.org/?probe=9721dbfb66) | Dec 07, 2021 |
| Toshiba       | Satellite S55-C             | [0e41e47583](https://linux-hardware.org/?probe=0e41e47583) | Dec 05, 2021 |
| Sony          | VPCEA47FX                   | [088fab187c](https://linux-hardware.org/?probe=088fab187c) | Dec 03, 2021 |
| Sony          | VPCEA47FX                   | [2f6f3b14de](https://linux-hardware.org/?probe=2f6f3b14de) | Dec 03, 2021 |
| Sony          | VPCEJ1L1E                   | [a48a00bdbc](https://linux-hardware.org/?probe=a48a00bdbc) | Dec 02, 2021 |
| TUXEDO        | P95_HP                      | [859d674cfe](https://linux-hardware.org/?probe=859d674cfe) | Dec 02, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [cd9d182e6e](https://linux-hardware.org/?probe=cd9d182e6e) | Nov 22, 2021 |
| Dell          | Vostro 1700                 | [86f23cb2f4](https://linux-hardware.org/?probe=86f23cb2f4) | Nov 22, 2021 |
| Dell          | Vostro 1700                 | [2aee39d91c](https://linux-hardware.org/?probe=2aee39d91c) | Nov 21, 2021 |
| Acer          | Swift SF114-32              | [008cd729a5](https://linux-hardware.org/?probe=008cd729a5) | Nov 14, 2021 |
| TUXEDO        | Unknown                     | [cb21aae05f](https://linux-hardware.org/?probe=cb21aae05f) | Nov 07, 2021 |
| Unknown       | Unknown                     | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| Dell          | Inspiron 5515               | [35d04dc3b9](https://linux-hardware.org/?probe=35d04dc3b9) | Nov 01, 2021 |
| Apple         | MacBookPro9,2               | [ef04c3c27a](https://linux-hardware.org/?probe=ef04c3c27a) | Oct 31, 2021 |
| TUXEDO        | Book XP15 / XP17 Gen12      | [4a518a759f](https://linux-hardware.org/?probe=4a518a759f) | Oct 25, 2021 |
| Apple         | MacBookPro8,2               | [571936bc0d](https://linux-hardware.org/?probe=571936bc0d) | Oct 23, 2021 |
| Acer          | Aspire 4752                 | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| Lenovo        | G570 4334                   | [7a9034f398](https://linux-hardware.org/?probe=7a9034f398) | Oct 12, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [1bea81fd91](https://linux-hardware.org/?probe=1bea81fd91) | Oct 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [d5ea22ef16](https://linux-hardware.org/?probe=d5ea22ef16) | Oct 09, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [b665ef94e7](https://linux-hardware.org/?probe=b665ef94e7) | Oct 01, 2021 |
| ASUSTek       | X302LJ                      | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b640e5da6d](https://linux-hardware.org/?probe=b640e5da6d) | Sep 17, 2021 |
| Dell          | Inspiron 5570               | [3ea6af2159](https://linux-hardware.org/?probe=3ea6af2159) | Sep 09, 2021 |
| Dell          | Inspiron 5570               | [981856c740](https://linux-hardware.org/?probe=981856c740) | Sep 09, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [4b6f0833eb](https://linux-hardware.org/?probe=4b6f0833eb) | Sep 02, 2021 |
| ASUSTek       | UX410UQK                    | [d2804fad00](https://linux-hardware.org/?probe=d2804fad00) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | [819b70e8cb](https://linux-hardware.org/?probe=819b70e8cb) | Sep 01, 2021 |
| HP            | ZBook Studio G3             | [d0b29312b8](https://linux-hardware.org/?probe=d0b29312b8) | Aug 31, 2021 |
| HP            | x360 310 G2 PC              | [429d94dd0f](https://linux-hardware.org/?probe=429d94dd0f) | Aug 31, 2021 |
| Fujitsu       | LIFEBOOK U9311A             | [7d5eeb6448](https://linux-hardware.org/?probe=7d5eeb6448) | Aug 30, 2021 |
| Dell          | XPS 15 9560                 | [55f224e5c3](https://linux-hardware.org/?probe=55f224e5c3) | Aug 26, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [aabe23e7a8](https://linux-hardware.org/?probe=aabe23e7a8) | Aug 20, 2021 |
| Google        | Peppy                       | [b0be7ddeac](https://linux-hardware.org/?probe=b0be7ddeac) | Aug 18, 2021 |
| TUXEDO        | Book XP1511                 | [3312e66e9f](https://linux-hardware.org/?probe=3312e66e9f) | Aug 15, 2021 |
| Unknown       | Unknown                     | [8ffbb927af](https://linux-hardware.org/?probe=8ffbb927af) | Aug 13, 2021 |
| Lenovo        | ThinkPad E490 20N8S07A00    | [bd4a6e1eaf](https://linux-hardware.org/?probe=bd4a6e1eaf) | Aug 05, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [9452fd6e14](https://linux-hardware.org/?probe=9452fd6e14) | Aug 02, 2021 |
| TUXEDO        | Book_XA1510                 | [bc0cfb6203](https://linux-hardware.org/?probe=bc0cfb6203) | Jul 29, 2021 |
| TUXEDO        | P95_HR                      | [60f8b3ac61](https://linux-hardware.org/?probe=60f8b3ac61) | Jul 26, 2021 |
| PC Special... | OctaneVI 15                 | [05e8f69907](https://linux-hardware.org/?probe=05e8f69907) | Jul 26, 2021 |
| Fujitsu       | LIFEBOOK E756               | [6afad8262f](https://linux-hardware.org/?probe=6afad8262f) | Jul 26, 2021 |
| TUXEDO        | Unknown                     | [b2586cfeba](https://linux-hardware.org/?probe=b2586cfeba) | Jul 05, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [19f235e9dd](https://linux-hardware.org/?probe=19f235e9dd) | Jul 04, 2021 |
| Lenovo        | Y50-70 20378                | [cd4215f3d2](https://linux-hardware.org/?probe=cd4215f3d2) | Jul 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [bbda9475cc](https://linux-hardware.org/?probe=bbda9475cc) | Jul 02, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [d2d1c6e65e](https://linux-hardware.org/?probe=d2d1c6e65e) | Jun 28, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | [5e91d6296d](https://linux-hardware.org/?probe=5e91d6296d) | Jun 27, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | [4e3ee76cd4](https://linux-hardware.org/?probe=4e3ee76cd4) | Jun 27, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [f8795e30bf](https://linux-hardware.org/?probe=f8795e30bf) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [143827e2e8](https://linux-hardware.org/?probe=143827e2e8) | Jun 16, 2021 |
| HP            | Notebook                    | [43b2a0f397](https://linux-hardware.org/?probe=43b2a0f397) | Jun 16, 2021 |
| BANGHO        | MAX G5 i1                   | [ca05e3a059](https://linux-hardware.org/?probe=ca05e3a059) | Jun 15, 2021 |
| Acer          | TravelMate P446-M           | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| Toshiba       | Satellite P300              | [f19856109a](https://linux-hardware.org/?probe=f19856109a) | Jun 09, 2021 |
| Acer          | Aspire A515-44              | [0f80210c56](https://linux-hardware.org/?probe=0f80210c56) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | [8f5cb26311](https://linux-hardware.org/?probe=8f5cb26311) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [b7f26cced7](https://linux-hardware.org/?probe=b7f26cced7) | Jun 01, 2021 |
| AWOW          | AK41                        | [ca1ba6ce75](https://linux-hardware.org/?probe=ca1ba6ce75) | May 27, 2021 |
| Dell          | Latitude E6410              | [124fdcdccb](https://linux-hardware.org/?probe=124fdcdccb) | May 25, 2021 |
| Dell          | Latitude E6410              | [5715f12aee](https://linux-hardware.org/?probe=5715f12aee) | May 24, 2021 |
| Toshiba       | Satellite P300              | [34d9279028](https://linux-hardware.org/?probe=34d9279028) | May 24, 2021 |
| TUXEDO        | Unknown                     | [d39c5e1f70](https://linux-hardware.org/?probe=d39c5e1f70) | May 23, 2021 |
| ASUSTek       | K45DR                       | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| Acer          | Aspire A515-51G             | [ad8fffaf05](https://linux-hardware.org/?probe=ad8fffaf05) | May 20, 2021 |
| ASUSTek       | N53SM                       | [fb4667be90](https://linux-hardware.org/?probe=fb4667be90) | May 19, 2021 |
| Dell          | Latitude E6540              | [6399cecb6f](https://linux-hardware.org/?probe=6399cecb6f) | May 19, 2021 |
| HP            | EliteBook 850 G1            | [5533f32102](https://linux-hardware.org/?probe=5533f32102) | May 18, 2021 |
| Toshiba       | Satellite P300              | [62ac427393](https://linux-hardware.org/?probe=62ac427393) | May 16, 2021 |
| TUXEDO        | Aura 15 Gen1                | [7aa1f41d1e](https://linux-hardware.org/?probe=7aa1f41d1e) | May 12, 2021 |
| Dell          | Latitude 5480               | [e6d8aca46a](https://linux-hardware.org/?probe=e6d8aca46a) | May 11, 2021 |
| Packard Be... | EasyNote TM98               | [2bb98626e9](https://linux-hardware.org/?probe=2bb98626e9) | May 03, 2021 |
| Dell          | Latitude D531               | [096370a055](https://linux-hardware.org/?probe=096370a055) | Apr 29, 2021 |
| Dell          | XPS 15 9500                 | [fbba77b949](https://linux-hardware.org/?probe=fbba77b949) | Apr 28, 2021 |
| Dell          | XPS 15 9500                 | [aba1faeb69](https://linux-hardware.org/?probe=aba1faeb69) | Apr 28, 2021 |
| Dell          | Vostro 5460                 | [cf32099d64](https://linux-hardware.org/?probe=cf32099d64) | Apr 27, 2021 |
| HUAWEI        | KLVL-WXX9                   | [d7318b3c30](https://linux-hardware.org/?probe=d7318b3c30) | Apr 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | [ceee3d709c](https://linux-hardware.org/?probe=ceee3d709c) | Apr 26, 2021 |
| HP            | Pavilion g6                 | [e22e43c0b5](https://linux-hardware.org/?probe=e22e43c0b5) | Apr 22, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | [0d25287be0](https://linux-hardware.org/?probe=0d25287be0) | Apr 16, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | [a74abd0b52](https://linux-hardware.org/?probe=a74abd0b52) | Apr 16, 2021 |
| Sony          | SVS13A25PBS                 | [c693fe6603](https://linux-hardware.org/?probe=c693fe6603) | Apr 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [09dc9d1375](https://linux-hardware.org/?probe=09dc9d1375) | Apr 14, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [3c414d527a](https://linux-hardware.org/?probe=3c414d527a) | Apr 05, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [383e2af37d](https://linux-hardware.org/?probe=383e2af37d) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| Acer          | Aspire E1-431               | [0a6108eb22](https://linux-hardware.org/?probe=0a6108eb22) | Apr 04, 2021 |
| TUXEDO        | Aura 15 Gen1                | [7fbbadb983](https://linux-hardware.org/?probe=7fbbadb983) | Mar 27, 2021 |
| HP            | ProBook 640 G2              | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | [835766dc3a](https://linux-hardware.org/?probe=835766dc3a) | Mar 21, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | [fb954b806d](https://linux-hardware.org/?probe=fb954b806d) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [153e336d81](https://linux-hardware.org/?probe=153e336d81) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [fa3b417784](https://linux-hardware.org/?probe=fa3b417784) | Mar 21, 2021 |
| Unknown       | Unknown                     | [282adc38a9](https://linux-hardware.org/?probe=282adc38a9) | Mar 20, 2021 |
| Unknown       | Unknown                     | [c368ac7bac](https://linux-hardware.org/?probe=c368ac7bac) | Mar 20, 2021 |
| Apple         | MacBookPro11,1              | [17a2a64f30](https://linux-hardware.org/?probe=17a2a64f30) | Mar 10, 2021 |
| HP            | ENVY 15                     | [5c1bfc1459](https://linux-hardware.org/?probe=5c1bfc1459) | Mar 05, 2021 |
| Timi          | TM1701                      | [a47b371c00](https://linux-hardware.org/?probe=a47b371c00) | Mar 03, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | [12212ad362](https://linux-hardware.org/?probe=12212ad362) | Feb 27, 2021 |
| Dell          | Latitude 5590               | [95fa6d8570](https://linux-hardware.org/?probe=95fa6d8570) | Feb 26, 2021 |
| Dell          | Latitude 7490               | [c72d91886b](https://linux-hardware.org/?probe=c72d91886b) | Feb 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [290d20ab8b](https://linux-hardware.org/?probe=290d20ab8b) | Feb 23, 2021 |
| HP            | ENVY 15 x360 PC             | [1a67eafe01](https://linux-hardware.org/?probe=1a67eafe01) | Feb 22, 2021 |
| Dell          | Latitude E4300              | [ba125a9cb8](https://linux-hardware.org/?probe=ba125a9cb8) | Feb 22, 2021 |
| Lenovo        | ThinkPad P1 20MES01400      | [640ff77fea](https://linux-hardware.org/?probe=640ff77fea) | Feb 11, 2021 |
| Fujitsu       | LIFEBOOK A555               | [2028548034](https://linux-hardware.org/?probe=2028548034) | Feb 07, 2021 |
| Dell          | XPS 13 7390                 | [db6b98f685](https://linux-hardware.org/?probe=db6b98f685) | Feb 05, 2021 |
| HP            | ZBook Studio G3             | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| Dell          | Latitude 5580               | [b9ac308476](https://linux-hardware.org/?probe=b9ac308476) | Feb 04, 2021 |
| Dell          | XPS 13 7390                 | [771cb653c6](https://linux-hardware.org/?probe=771cb653c6) | Feb 03, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c94818db0e](https://linux-hardware.org/?probe=c94818db0e) | Feb 03, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | [748cc10c8c](https://linux-hardware.org/?probe=748cc10c8c) | Feb 03, 2021 |
| ASUSTek       | X551CA                      | [1857586e3a](https://linux-hardware.org/?probe=1857586e3a) | Feb 03, 2021 |
| Positivo      | C14CR21TV                   | [2133a41335](https://linux-hardware.org/?probe=2133a41335) | Feb 02, 2021 |
| MSI           | Prestige 14 A10SC           | [4af6bad702](https://linux-hardware.org/?probe=4af6bad702) | Jan 31, 2021 |
| HUAWEI        | KLVC-WXX9                   | [f519b82ae5](https://linux-hardware.org/?probe=f519b82ae5) | Jan 26, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [47517be667](https://linux-hardware.org/?probe=47517be667) | Jan 23, 2021 |
| Lenovo        | G40-30 80FY                 | [2ade08670a](https://linux-hardware.org/?probe=2ade08670a) | Jan 22, 2021 |
| HP            | Laptop 15-da0xxx            | [3d5f8c3cd2](https://linux-hardware.org/?probe=3d5f8c3cd2) | Jan 21, 2021 |
| MSI           | GP73 Leopard 8RE            | [c554fa2a9d](https://linux-hardware.org/?probe=c554fa2a9d) | Jan 17, 2021 |
| Dell          | XPS L322X                   | [e65c21cdd5](https://linux-hardware.org/?probe=e65c21cdd5) | Jan 16, 2021 |
| ASUSTek       | N53SM                       | [41bf2f638a](https://linux-hardware.org/?probe=41bf2f638a) | Jan 13, 2021 |
| MSI           | GE70 2PC\2PE                | [805e6fac6b](https://linux-hardware.org/?probe=805e6fac6b) | Jan 08, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [92c9f3e6c5](https://linux-hardware.org/?probe=92c9f3e6c5) | Jan 07, 2021 |
| Acer          | TravelMate P446-M           | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Acer          | TravelMate P446-M           | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Acer          | Aspire V3-771               | [450e8c59cc](https://linux-hardware.org/?probe=450e8c59cc) | Jan 02, 2021 |
| Acer          | Aspire V3-771               | [4122ea4b04](https://linux-hardware.org/?probe=4122ea4b04) | Jan 02, 2021 |
| Acer          | TravelMate P446-M           | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| Toshiba       | Satellite P750              | [3d7045dbbf](https://linux-hardware.org/?probe=3d7045dbbf) | Dec 28, 2020 |
| HP            | Pavilion 17                 | [b07af847e2](https://linux-hardware.org/?probe=b07af847e2) | Dec 26, 2020 |
| HP            | Stream Laptop 14-cb1xxx     | [4f8b9f90d8](https://linux-hardware.org/?probe=4f8b9f90d8) | Dec 21, 2020 |
| TUXEDO        | Aura 15 Gen1                | [c85ead3218](https://linux-hardware.org/?probe=c85ead3218) | Dec 19, 2020 |
| Unknown       | Unknown                     | [e81e3d85d6](https://linux-hardware.org/?probe=e81e3d85d6) | Dec 15, 2020 |
| Dell          | XPS 13 9380                 | [1eae71a2dd](https://linux-hardware.org/?probe=1eae71a2dd) | Dec 14, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | [ff0cd7f2bc](https://linux-hardware.org/?probe=ff0cd7f2bc) | Dec 13, 2020 |
| ASUSTek       | F9E                         | [0070b5eda7](https://linux-hardware.org/?probe=0070b5eda7) | Dec 12, 2020 |
| HP            | EliteBook 850 G1            | [671d151ab9](https://linux-hardware.org/?probe=671d151ab9) | Dec 12, 2020 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [a603cda0d7](https://linux-hardware.org/?probe=a603cda0d7) | Dec 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [c04e40195e](https://linux-hardware.org/?probe=c04e40195e) | Dec 11, 2020 |
| Fujitsu       | LIFEBOOK E756               | [ccb7d3edd7](https://linux-hardware.org/?probe=ccb7d3edd7) | Dec 10, 2020 |
| HP            | Pavilion dv1000 (EW999LA... | [6675bde630](https://linux-hardware.org/?probe=6675bde630) | Dec 07, 2020 |
| Lenovo        | ThinkPad T480 20L50011US    | [d47823099d](https://linux-hardware.org/?probe=d47823099d) | Dec 02, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [465bfd7567](https://linux-hardware.org/?probe=465bfd7567) | Nov 28, 2020 |
| Acer          | Aspire E1-532               | [c4db9a001e](https://linux-hardware.org/?probe=c4db9a001e) | Nov 25, 2020 |
| ASUSTek       | FX503VD                     | [f391747dd0](https://linux-hardware.org/?probe=f391747dd0) | Nov 24, 2020 |
| Packard Be... | EasyNote LE69KB             | [0afa851fa7](https://linux-hardware.org/?probe=0afa851fa7) | Nov 22, 2020 |
| HP            | Laptop 17-ak0xx             | [81d47c5bbd](https://linux-hardware.org/?probe=81d47c5bbd) | Nov 14, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [7e8af2342a](https://linux-hardware.org/?probe=7e8af2342a) | Nov 12, 2020 |
| ASUSTek       | K52De                       | [d95e3b8198](https://linux-hardware.org/?probe=d95e3b8198) | Nov 12, 2020 |
| ASUSTek       | K52De                       | [9aec230d46](https://linux-hardware.org/?probe=9aec230d46) | Nov 12, 2020 |
| HP            | Laptop 17-ak0xx             | [bb3de0e33d](https://linux-hardware.org/?probe=bb3de0e33d) | Nov 08, 2020 |
| Sony          | SVS13A25PBS                 | [ec54069f90](https://linux-hardware.org/?probe=ec54069f90) | Nov 06, 2020 |
| TUXEDO        | Unknown                     | [ccab34bcd7](https://linux-hardware.org/?probe=ccab34bcd7) | Nov 03, 2020 |
| Lenovo        | IdeaPad S100 20109          | [8f26323f1e](https://linux-hardware.org/?probe=8f26323f1e) | Nov 02, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | [f403df4c45](https://linux-hardware.org/?probe=f403df4c45) | Nov 01, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | [2e03e273f1](https://linux-hardware.org/?probe=2e03e273f1) | Oct 31, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | [4a619e003e](https://linux-hardware.org/?probe=4a619e003e) | Oct 31, 2020 |
| Fujitsu       | LIFEBOOK E756               | [7e515b01ea](https://linux-hardware.org/?probe=7e515b01ea) | Oct 30, 2020 |
| Acer          | Aspire SW3-016              | [be195992d0](https://linux-hardware.org/?probe=be195992d0) | Oct 30, 2020 |
| Dell          | Latitude E6540              | [45ad219146](https://linux-hardware.org/?probe=45ad219146) | Oct 29, 2020 |
| HP            | ZBook 14                    | [b282051085](https://linux-hardware.org/?probe=b282051085) | Oct 27, 2020 |
| HP            | Elite x2 1012 G1            | [7a593747a4](https://linux-hardware.org/?probe=7a593747a4) | Oct 26, 2020 |
| HP            | Elite x2 1012 G1            | [82ff46fe7f](https://linux-hardware.org/?probe=82ff46fe7f) | Oct 26, 2020 |
| Dell          | Latitude 5400               | [9594ef7488](https://linux-hardware.org/?probe=9594ef7488) | Oct 20, 2020 |
| Dell          | Latitude 5400               | [d016f37257](https://linux-hardware.org/?probe=d016f37257) | Oct 20, 2020 |
| HP            | Laptop 14-dk0xxx            | [2f2b699bf6](https://linux-hardware.org/?probe=2f2b699bf6) | Oct 11, 2020 |
| Lenovo        | ThinkPad P43s 20RH0013US    | [e540cc2901](https://linux-hardware.org/?probe=e540cc2901) | Oct 09, 2020 |
| Lenovo        | 20SL                        | [bda45231ce](https://linux-hardware.org/?probe=bda45231ce) | Oct 07, 2020 |
| Apple         | MacBookPro8,1               | [3f17f3c6e8](https://linux-hardware.org/?probe=3f17f3c6e8) | Oct 06, 2020 |
| TUXEDO        | P7xxTM1                     | [1c64a38e1e](https://linux-hardware.org/?probe=1c64a38e1e) | Oct 05, 2020 |
| MSI           | Modern 14 A10RB             | [67d9e1d5e4](https://linux-hardware.org/?probe=67d9e1d5e4) | Sep 30, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [2ebce35736](https://linux-hardware.org/?probe=2ebce35736) | Sep 29, 2020 |
| ASUSTek       | UX430UQ                     | [c201929d1a](https://linux-hardware.org/?probe=c201929d1a) | Sep 27, 2020 |
| Dell          | Latitude 5400               | [763c1287a5](https://linux-hardware.org/?probe=763c1287a5) | Sep 23, 2020 |
| HP            | ProBook 4730s               | [4363da5d51](https://linux-hardware.org/?probe=4363da5d51) | Sep 19, 2020 |
| Dell          | Inspiron 7560               | [4a1a3140a7](https://linux-hardware.org/?probe=4a1a3140a7) | Sep 15, 2020 |
| Fujitsu       | LIFEBOOK A512               | [0ce417fed7](https://linux-hardware.org/?probe=0ce417fed7) | Sep 08, 2020 |
| HP            | Pavilion g6                 | [522ff3c9c7](https://linux-hardware.org/?probe=522ff3c9c7) | Sep 03, 2020 |
| Dell          | G7 7588                     | [d6cd49b568](https://linux-hardware.org/?probe=d6cd49b568) | Sep 02, 2020 |
| Dell          | Inspiron 11-3168            | [bf9ae88e59](https://linux-hardware.org/?probe=bf9ae88e59) | Aug 20, 2020 |
| Dell          | Inspiron 11-3168            | [c168661ada](https://linux-hardware.org/?probe=c168661ada) | Aug 20, 2020 |
| ASUSTek       | U47A                        | [39d5bde56a](https://linux-hardware.org/?probe=39d5bde56a) | Aug 19, 2020 |
| Sony          | VPCEK20AL                   | [2147eeff89](https://linux-hardware.org/?probe=2147eeff89) | Aug 16, 2020 |
| MSI           | Prestige 15 A10SC           | [4cea086204](https://linux-hardware.org/?probe=4cea086204) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | [d24b0f8f6a](https://linux-hardware.org/?probe=d24b0f8f6a) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | [6bdfa3f1ad](https://linux-hardware.org/?probe=6bdfa3f1ad) | Aug 16, 2020 |
| ASUSTek       | U47A                        | [55022416f8](https://linux-hardware.org/?probe=55022416f8) | Aug 14, 2020 |
| ASUSTek       | U47A                        | [1c4676a5d6](https://linux-hardware.org/?probe=1c4676a5d6) | Aug 13, 2020 |
| Standard      | MT40II                      | [974f5398ca](https://linux-hardware.org/?probe=974f5398ca) | Aug 06, 2020 |
| Lenovo        | ThinkPad T430s 23539WU      | [3ff86ae696](https://linux-hardware.org/?probe=3ff86ae696) | Aug 03, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [5caeef5a4f](https://linux-hardware.org/?probe=5caeef5a4f) | Aug 03, 2020 |
| Apple         | MacBook3,1                  | [7da122d44a](https://linux-hardware.org/?probe=7da122d44a) | Jul 29, 2020 |
| HUAWEI        | MACH-WX9                    | [999f65d55e](https://linux-hardware.org/?probe=999f65d55e) | Jul 28, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [6a0fabe139](https://linux-hardware.org/?probe=6a0fabe139) | Jul 28, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ccd785c473](https://linux-hardware.org/?probe=ccd785c473) | Jul 27, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | [4f80b590f5](https://linux-hardware.org/?probe=4f80b590f5) | Jul 25, 2020 |
| HP            | Pavilion 14                 | [3243fbe29b](https://linux-hardware.org/?probe=3243fbe29b) | Jul 25, 2020 |
| HP            | Pavilion dv6                | [24b46efa49](https://linux-hardware.org/?probe=24b46efa49) | Jul 25, 2020 |
| HP            | EliteBook 2560p             | [dd251c0a0c](https://linux-hardware.org/?probe=dd251c0a0c) | Jul 25, 2020 |
| Dell          | Latitude E6320              | [d9ac43486e](https://linux-hardware.org/?probe=d9ac43486e) | Jul 25, 2020 |
| Dell          | G3 3579                     | [b129bccbcf](https://linux-hardware.org/?probe=b129bccbcf) | Jul 24, 2020 |
| Dell          | G7 7588                     | [cb6c4a378b](https://linux-hardware.org/?probe=cb6c4a378b) | Jul 24, 2020 |
| Dell          | Inspiron 5437               | [bae63d5905](https://linux-hardware.org/?probe=bae63d5905) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [a4ff18fb01](https://linux-hardware.org/?probe=a4ff18fb01) | Jul 24, 2020 |
| Acer          | Aspire A315-41              | [689b63d743](https://linux-hardware.org/?probe=689b63d743) | Jul 24, 2020 |
| ASUSTek       | K53E                        | [965c0a5e03](https://linux-hardware.org/?probe=965c0a5e03) | Jul 20, 2020 |
| MSI           | GL62M 7RD                   | [ddfb055569](https://linux-hardware.org/?probe=ddfb055569) | Jul 18, 2020 |
| MSI           | GP72 7RE                    | [66efd09dbc](https://linux-hardware.org/?probe=66efd09dbc) | Jul 12, 2020 |
| ASUSTek       | X510UAR                     | [a8f39d2061](https://linux-hardware.org/?probe=a8f39d2061) | Jul 08, 2020 |
| HP            | EliteBook 840 G6            | [1a175eee47](https://linux-hardware.org/?probe=1a175eee47) | Jul 07, 2020 |
| Dell          | Inspiron 3537               | [803b8c9adc](https://linux-hardware.org/?probe=803b8c9adc) | Jul 06, 2020 |
| Dell          | Inspiron 3537               | [38640e68c7](https://linux-hardware.org/?probe=38640e68c7) | Jul 06, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [e2f2937842](https://linux-hardware.org/?probe=e2f2937842) | Jul 05, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [e6480fdb93](https://linux-hardware.org/?probe=e6480fdb93) | Jul 04, 2020 |
| Dell          | XPS L401X                   | [291b1c0a01](https://linux-hardware.org/?probe=291b1c0a01) | Jul 03, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [c67e3d5b3d](https://linux-hardware.org/?probe=c67e3d5b3d) | Jul 02, 2020 |
| TUXEDO        | Unknown                     | [dd10caa4c9](https://linux-hardware.org/?probe=dd10caa4c9) | Jun 26, 2020 |
| Dell          | Latitude E6220              | [2177469041](https://linux-hardware.org/?probe=2177469041) | Jun 25, 2020 |
| HP            | Laptop 15-dw0xxx            | [a9c582ba02](https://linux-hardware.org/?probe=a9c582ba02) | Jun 19, 2020 |
| Acer          | Aspire R3-131T              | [b51cceda3f](https://linux-hardware.org/?probe=b51cceda3f) | Jun 17, 2020 |
| Acer          | Aspire R3-131T              | [52d48f4c11](https://linux-hardware.org/?probe=52d48f4c11) | Jun 17, 2020 |
| TUXEDO        | InfinityBook Pro 15 v4      | [7d351b71dc](https://linux-hardware.org/?probe=7d351b71dc) | Jun 17, 2020 |
| HP            | ENVY 17                     | [8ee27ae156](https://linux-hardware.org/?probe=8ee27ae156) | Jun 16, 2020 |
| Dell          | Inspiron 7590               | [1e4d9a97b8](https://linux-hardware.org/?probe=1e4d9a97b8) | Jun 15, 2020 |
| Sony          | VPCCW25FL                   | [2e9d3ed45b](https://linux-hardware.org/?probe=2e9d3ed45b) | Jun 14, 2020 |
| HP            | ENVY 17                     | [6717ca8025](https://linux-hardware.org/?probe=6717ca8025) | Jun 14, 2020 |
| TUXEDO        | Unknown                     | [7c4e814d03](https://linux-hardware.org/?probe=7c4e814d03) | Jun 13, 2020 |
| TUXEDO        | Unknown                     | [10875bae28](https://linux-hardware.org/?probe=10875bae28) | Jun 13, 2020 |
| Acer          | Aspire V3-572G              | [d780f9b6ef](https://linux-hardware.org/?probe=d780f9b6ef) | Jun 13, 2020 |
| ASUSTek       | X540LA                      | [99651c1c86](https://linux-hardware.org/?probe=99651c1c86) | Jun 12, 2020 |
| HP            | ENVY 17                     | [19571ad1c9](https://linux-hardware.org/?probe=19571ad1c9) | Jun 11, 2020 |
| HP            | ENVY 15                     | [3fa91961e1](https://linux-hardware.org/?probe=3fa91961e1) | Jun 07, 2020 |
| HP            | ENVY 17                     | [16c895ce30](https://linux-hardware.org/?probe=16c895ce30) | Jun 07, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | [95097be9d3](https://linux-hardware.org/?probe=95097be9d3) | Jun 02, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | [d4c8c1735b](https://linux-hardware.org/?probe=d4c8c1735b) | May 31, 2020 |
| HUAWEI        | MACH-WX9                    | [f3ca082840](https://linux-hardware.org/?probe=f3ca082840) | May 31, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [6ad038b762](https://linux-hardware.org/?probe=6ad038b762) | May 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [3552bfc82b](https://linux-hardware.org/?probe=3552bfc82b) | May 29, 2020 |
| HP            | ENVY 17                     | [0bb6be8c85](https://linux-hardware.org/?probe=0bb6be8c85) | May 27, 2020 |
| HP            | ENVY 17                     | [4f1caa50f6](https://linux-hardware.org/?probe=4f1caa50f6) | May 27, 2020 |
| Lenovo        | ThinkPad X260 20F5S2HF06    | [fb34ca6c06](https://linux-hardware.org/?probe=fb34ca6c06) | May 26, 2020 |
| Lenovo        | ThinkPad T430 2349P74       | [50dbda3211](https://linux-hardware.org/?probe=50dbda3211) | May 21, 2020 |
| ASUSTek       | S400CA                      | [3e3bb3f13e](https://linux-hardware.org/?probe=3e3bb3f13e) | May 19, 2020 |
| ASUSTek       | X510UNR                     | [23cb30a022](https://linux-hardware.org/?probe=23cb30a022) | May 16, 2020 |
| ASUSTek       | X510UNR                     | [d28985973f](https://linux-hardware.org/?probe=d28985973f) | May 16, 2020 |
| Acer          | Aspire F5-573G              | [7eea93aa65](https://linux-hardware.org/?probe=7eea93aa65) | May 16, 2020 |
| TUXEDO        | Unknown                     | [9eb9f125bf](https://linux-hardware.org/?probe=9eb9f125bf) | May 15, 2020 |
| Dell          | Latitude 5400               | [cfdf75da7b](https://linux-hardware.org/?probe=cfdf75da7b) | May 14, 2020 |
| Acer          | Swift SF315-52              | [39a7bd47d7](https://linux-hardware.org/?probe=39a7bd47d7) | May 12, 2020 |
| Lenovo        | G550 2958                   | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo        | G550 2958                   | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| TUXEDO        | Unknown                     | [f06dc42b2a](https://linux-hardware.org/?probe=f06dc42b2a) | May 10, 2020 |
| TUXEDO        | Unknown                     | [3a72ff2108](https://linux-hardware.org/?probe=3a72ff2108) | May 09, 2020 |
| ASUSTek       | S551LN                      | [51bb777f10](https://linux-hardware.org/?probe=51bb777f10) | May 08, 2020 |
| ASUSTek       | S551LN                      | [b81e2e0679](https://linux-hardware.org/?probe=b81e2e0679) | May 08, 2020 |
| Quanta        | QL3 TBD                     | [680a32b94c](https://linux-hardware.org/?probe=680a32b94c) | May 08, 2020 |
| Gigabyte      | GB-BKi7A-7500               | [a4c4bc09fb](https://linux-hardware.org/?probe=a4c4bc09fb) | May 08, 2020 |
| HP            | EliteBook 840 G5            | [5c81f4ef61](https://linux-hardware.org/?probe=5c81f4ef61) | May 07, 2020 |
| ASUSTek       | G55VW                       | [9cb0c68aa1](https://linux-hardware.org/?probe=9cb0c68aa1) | May 07, 2020 |
| HP            | EliteBook 8560w             | [e2fca9899f](https://linux-hardware.org/?probe=e2fca9899f) | May 07, 2020 |
| Acer          | Aspire F5-573G              | [0b67b7c423](https://linux-hardware.org/?probe=0b67b7c423) | May 06, 2020 |
| Dell          | Inspiron 1545               | [ac74330be2](https://linux-hardware.org/?probe=ac74330be2) | May 03, 2020 |
| HP            | Notebook                    | [d666fee133](https://linux-hardware.org/?probe=d666fee133) | May 02, 2020 |
| Lenovo        | ThinkPad W530 2447GW3       | [69f36d1be1](https://linux-hardware.org/?probe=69f36d1be1) | Apr 30, 2020 |
| Lenovo        | ThinkPad X230 2306CTO       | [80111dac4b](https://linux-hardware.org/?probe=80111dac4b) | Apr 24, 2020 |
| Dell          | Latitude 5400               | [7319cff553](https://linux-hardware.org/?probe=7319cff553) | Apr 22, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [cba2c66659](https://linux-hardware.org/?probe=cba2c66659) | Apr 20, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [e2fabad799](https://linux-hardware.org/?probe=e2fabad799) | Apr 13, 2020 |
| Lenovo        | ThinkPad T410 2537H21       | [0140b2344a](https://linux-hardware.org/?probe=0140b2344a) | Apr 08, 2020 |
| HP            | EliteBook 8470p             | [d39e8563ca](https://linux-hardware.org/?probe=d39e8563ca) | Apr 07, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [f309322c77](https://linux-hardware.org/?probe=f309322c77) | Apr 04, 2020 |
| Dell          | Inspiron 5770               | [5a5984be1c](https://linux-hardware.org/?probe=5a5984be1c) | Mar 29, 2020 |
| Dell          | Inspiron 5770               | [afcbaaf5c5](https://linux-hardware.org/?probe=afcbaaf5c5) | Mar 29, 2020 |
| HP            | Compaq 6720s                | [7a81993a9b](https://linux-hardware.org/?probe=7a81993a9b) | Mar 22, 2020 |
| Lenovo        | ThinkPad P53 20QQS1JE00     | [6692834531](https://linux-hardware.org/?probe=6692834531) | Mar 18, 2020 |
| ASUSTek       | X750JB                      | [6d8e7e2bf9](https://linux-hardware.org/?probe=6d8e7e2bf9) | Mar 15, 2020 |
| Dell          | Latitude 5400               | [3bda0aef33](https://linux-hardware.org/?probe=3bda0aef33) | Mar 14, 2020 |
| HP            | 2000                        | [fa3539bb75](https://linux-hardware.org/?probe=fa3539bb75) | Mar 14, 2020 |
| Standard      | MT40II                      | [f11c251d38](https://linux-hardware.org/?probe=f11c251d38) | Mar 13, 2020 |
| Dell          | Latitude E6420              | [7653562a2f](https://linux-hardware.org/?probe=7653562a2f) | Mar 07, 2020 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [c4b9b4ab26](https://linux-hardware.org/?probe=c4b9b4ab26) | Mar 07, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | [4b844d95eb](https://linux-hardware.org/?probe=4b844d95eb) | Mar 05, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | [b88f46d2eb](https://linux-hardware.org/?probe=b88f46d2eb) | Mar 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [1dba6c5acf](https://linux-hardware.org/?probe=1dba6c5acf) | Mar 03, 2020 |
| Dell          | XPS 13 9380                 | [5a7b311c84](https://linux-hardware.org/?probe=5a7b311c84) | Mar 02, 2020 |
| ASUSTek       | N751JK                      | [a08a81ed83](https://linux-hardware.org/?probe=a08a81ed83) | Mar 01, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [435f7d1017](https://linux-hardware.org/?probe=435f7d1017) | Feb 21, 2020 |
| TUXEDO        | Unknown                     | [002a2b6abe](https://linux-hardware.org/?probe=002a2b6abe) | Feb 21, 2020 |
| ASUSTek       | N501VW                      | [9e101537c5](https://linux-hardware.org/?probe=9e101537c5) | Feb 17, 2020 |
| ASUSTek       | N501VW                      | [31a6b6bac8](https://linux-hardware.org/?probe=31a6b6bac8) | Feb 15, 2020 |
| Acer          | Aspire A515-51G             | [ac2755b222](https://linux-hardware.org/?probe=ac2755b222) | Feb 12, 2020 |
| Acer          | Aspire A515-51G             | [317f9ded14](https://linux-hardware.org/?probe=317f9ded14) | Feb 12, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [81d2b1c515](https://linux-hardware.org/?probe=81d2b1c515) | Jan 25, 2020 |
| Unknown       | Unknown                     | [5603e706a3](https://linux-hardware.org/?probe=5603e706a3) | Jan 19, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | [912a2fc0df](https://linux-hardware.org/?probe=912a2fc0df) | Jan 16, 2020 |
| HP            | 2000                        | [adde2680e0](https://linux-hardware.org/?probe=adde2680e0) | Jan 08, 2020 |
| Lenovo        | ThinkPad T530 23943V0       | [fdb43e275c](https://linux-hardware.org/?probe=fdb43e275c) | Jan 05, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [ae8aac83f4](https://linux-hardware.org/?probe=ae8aac83f4) | Jan 05, 2020 |
| TUXEDO        | Unknown                     | [282e4941e2](https://linux-hardware.org/?probe=282e4941e2) | Dec 27, 2019 |
| HP            | Compaq 8460p USAO           | [3eab448396](https://linux-hardware.org/?probe=3eab448396) | Dec 21, 2019 |
| ASUSTek       | N751JK                      | [a6b5f083ca](https://linux-hardware.org/?probe=a6b5f083ca) | Nov 21, 2019 |
| ASUSTek       | N751JK                      | [2c44aa3122](https://linux-hardware.org/?probe=2c44aa3122) | Nov 21, 2019 |
| Dell          | Inspiron 5559               | [6571c933d2](https://linux-hardware.org/?probe=6571c933d2) | Mar 08, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu Budgie 20.04 | 158       | 53.74%  |
| Ubuntu Budgie 20.10 | 34        | 11.56%  |
| Ubuntu Budgie 21.10 | 29        | 9.86%   |
| Ubuntu Budgie 18.04 | 22        | 7.48%   |
| Ubuntu Budgie 21.04 | 19        | 6.46%   |
| Ubuntu Budgie 22.04 | 16        | 5.44%   |
| Ubuntu Budgie 19.10 | 13        | 4.42%   |
| Ubuntu Budgie 16.04 | 2         | 0.68%   |
| Ubuntu Budgie       | 1         | 0.34%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Budgie | 288       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 18        | 5.7%    |
| 5.3.0-40-generic  | 10        | 3.16%   |
| 5.13.0-22-generic | 10        | 3.16%   |
| 5.4.0-40-generic  | 9         | 2.85%   |
| 5.8.0-41-generic  | 7         | 2.22%   |
| 5.15.0-27-generic | 7         | 2.22%   |
| 5.13.0-28-generic | 7         | 2.22%   |
| 5.4.0-37-generic  | 6         | 1.9%    |
| 5.4.0-29-generic  | 6         | 1.9%    |
| 5.13.0-39-generic | 6         | 1.9%    |
| 5.8.0-53-generic  | 5         | 1.58%   |
| 5.8.0-48-generic  | 5         | 1.58%   |
| 5.4.0-52-generic  | 5         | 1.58%   |
| 5.4.0-48-generic  | 5         | 1.58%   |
| 5.4.0-33-generic  | 5         | 1.58%   |
| 5.13.0-40-generic | 5         | 1.58%   |
| 5.8.0-44-generic  | 4         | 1.27%   |
| 5.8.0-33-generic  | 4         | 1.27%   |
| 5.8.0-29-generic  | 4         | 1.27%   |
| 5.4.0-58-generic  | 4         | 1.27%   |
| 5.4.0-31-generic  | 4         | 1.27%   |
| 5.13.0-35-generic | 4         | 1.27%   |
| 5.13.0-30-generic | 4         | 1.27%   |
| 5.13.0-19-generic | 4         | 1.27%   |
| 5.11.0-34-generic | 4         | 1.27%   |
| 5.11.0-16-generic | 4         | 1.27%   |
| 5.8.0-45-generic  | 3         | 0.95%   |
| 5.4.0-91-generic  | 3         | 0.95%   |
| 5.4.0-73-generic  | 3         | 0.95%   |
| 5.4.0-28-generic  | 3         | 0.95%   |
| 5.15.0-30-generic | 3         | 0.95%   |
| 5.11.0-41-generic | 3         | 0.95%   |
| 5.11.0-31-generic | 3         | 0.95%   |
| 5.11.0-27-generic | 3         | 0.95%   |
| 5.11.0-25-generic | 3         | 0.95%   |
| 5.8.0-63-generic  | 2         | 0.63%   |
| 5.8.0-59-generic  | 2         | 0.63%   |
| 5.8.0-49-generic  | 2         | 0.63%   |
| 5.8.0-43-generic  | 2         | 0.63%   |
| 5.8.0-38-generic  | 2         | 0.63%   |
| 5.8.0-34-generic  | 2         | 0.63%   |
| 5.8.0-26-generic  | 2         | 0.63%   |
| 5.4.0-89-generic  | 2         | 0.63%   |
| 5.4.0-80-generic  | 2         | 0.63%   |
| 5.4.0-74-generic  | 2         | 0.63%   |
| 5.4.0-72-generic  | 2         | 0.63%   |
| 5.4.0-60-generic  | 2         | 0.63%   |
| 5.4.0-59-generic  | 2         | 0.63%   |
| 5.4.0-56-generic  | 2         | 0.63%   |
| 5.4.0-47-generic  | 2         | 0.63%   |
| 5.4.0-26-generic  | 2         | 0.63%   |
| 5.3.0-42-generic  | 2         | 0.63%   |
| 5.3.0-24-generic  | 2         | 0.63%   |
| 5.15.0-33-generic | 2         | 0.63%   |
| 5.13.0-27-generic | 2         | 0.63%   |
| 5.11.0-22-generic | 2         | 0.63%   |
| 5.11.0-17-generic | 2         | 0.63%   |
| 5.0.0-37-generic  | 2         | 0.63%   |
| 4.18.0-17-generic | 2         | 0.63%   |
| 4.15.0-99-generic | 2         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 100       | 33.67%  |
| 5.8.0   | 54        | 18.18%  |
| 5.13.0  | 47        | 15.82%  |
| 5.11.0  | 31        | 10.44%  |
| 5.3.0   | 21        | 7.07%   |
| 5.15.0  | 17        | 5.72%   |
| 4.15.0  | 9         | 3.03%   |
| 5.6.0   | 3         | 1.01%   |
| 5.12.0  | 2         | 0.67%   |
| 5.0.0   | 2         | 0.67%   |
| 4.18.0  | 2         | 0.67%   |
| 5.9.0   | 1         | 0.34%   |
| 5.8.11  | 1         | 0.34%   |
| 5.6.7   | 1         | 0.34%   |
| 5.5.0   | 1         | 0.34%   |
| 5.16.14 | 1         | 0.34%   |
| 5.15.11 | 1         | 0.34%   |
| 5.10.11 | 1         | 0.34%   |
| 5.10.0  | 1         | 0.34%   |
| 4.4.0   | 1         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 100       | 33.67%  |
| 5.8     | 55        | 18.52%  |
| 5.13    | 47        | 15.82%  |
| 5.11    | 31        | 10.44%  |
| 5.3     | 21        | 7.07%   |
| 5.15    | 18        | 6.06%   |
| 4.15    | 9         | 3.03%   |
| 5.6     | 4         | 1.35%   |
| 5.12    | 2         | 0.67%   |
| 5.10    | 2         | 0.67%   |
| 5.0     | 2         | 0.67%   |
| 4.18    | 2         | 0.67%   |
| 5.9     | 1         | 0.34%   |
| 5.5     | 1         | 0.34%   |
| 5.16    | 1         | 0.34%   |
| 4.4     | 1         | 0.34%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 285       | 98.96%  |
| i686   | 3         | 1.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 283       | 98.26%  |
| GNOME  | 4         | 1.39%   |
| XFCE   | 1         | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 279       | 96.88%  |
| Wayland | 9         | 3.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 122       | 41.92%  |
| LightDM | 79        | 27.15%  |
| TDM     | 58        | 19.93%  |
| GDM     | 23        | 7.9%    |
| GDM3    | 8         | 2.75%   |
| SDDM    | 1         | 0.34%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 94        | 32.53%  |
| de_DE   | 42        | 14.53%  |
| pt_BR   | 21        | 7.27%   |
| en_GB   | 18        | 6.23%   |
| fr_FR   | 17        | 5.88%   |
| en_CA   | 10        | 3.46%   |
| ru_RU   | 9         | 3.11%   |
| it_IT   | 8         | 2.77%   |
| en_IN   | 8         | 2.77%   |
| es_AR   | 7         | 2.42%   |
| es_MX   | 6         | 2.08%   |
| es_ES   | 5         | 1.73%   |
| hu_HU   | 3         | 1.04%   |
| es_CL   | 3         | 1.04%   |
| en_AU   | 3         | 1.04%   |
| de_AT   | 3         | 1.04%   |
| C       | 3         | 1.04%   |
| Unknown | 3         | 1.04%   |
| pt_PT   | 2         | 0.69%   |
| pl_PL   | 2         | 0.69%   |
| fi_FI   | 2         | 0.69%   |
| en_IE   | 2         | 0.69%   |
| de_CH   | 2         | 0.69%   |
| zh_CN   | 1         | 0.35%   |
| uk_UA   | 1         | 0.35%   |
| tr_TR   | 1         | 0.35%   |
| nl_NL   | 1         | 0.35%   |
| nl_BE   | 1         | 0.35%   |
| nb_NO   | 1         | 0.35%   |
| lv_LV   | 1         | 0.35%   |
| id_ID   | 1         | 0.35%   |
| fr_CH   | 1         | 0.35%   |
| fr_BE   | 1         | 0.35%   |
| es_US   | 1         | 0.35%   |
| es_SV   | 1         | 0.35%   |
| es_GT   | 1         | 0.35%   |
| es_EC   | 1         | 0.35%   |
| en_ZA   | 1         | 0.35%   |
| en_SG   | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 186       | 63.27%  |
| BIOS | 108       | 36.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 271       | 93.77%  |
| Zfs     | 8         | 2.77%   |
| Xfs     | 3         | 1.04%   |
| Overlay | 3         | 1.04%   |
| Btrfs   | 3         | 1.04%   |
| Jfs     | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 153       | 52.94%  |
| GPT     | 114       | 39.45%  |
| MBR     | 22        | 7.61%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 261       | 89.69%  |
| Yes       | 30        | 10.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 202       | 69.66%  |
| Yes       | 88        | 30.34%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 57        | 19.79%  |
| Hewlett-Packard        | 45        | 15.63%  |
| Dell                   | 37        | 12.85%  |
| TUXEDO                 | 33        | 11.46%  |
| ASUSTek Computer       | 30        | 10.42%  |
| Acer                   | 19        | 6.6%    |
| Apple                  | 11        | 3.82%   |
| MSI                    | 10        | 3.47%   |
| Sony                   | 5         | 1.74%   |
| Samsung Electronics    | 5         | 1.74%   |
| HUAWEI                 | 5         | 1.74%   |
| Toshiba                | 3         | 1.04%   |
| Packard Bell           | 3         | 1.04%   |
| Google                 | 3         | 1.04%   |
| Fujitsu                | 3         | 1.04%   |
| Unknown                | 3         | 1.04%   |
| Standard               | 2         | 0.69%   |
| Viglen                 | 1         | 0.35%   |
| Timi                   | 1         | 0.35%   |
| Razer                  | 1         | 0.35%   |
| Quanta                 | 1         | 0.35%   |
| Positivo               | 1         | 0.35%   |
| PC Specialist          | 1         | 0.35%   |
| GPU Company            | 1         | 0.35%   |
| Gigabyte Technology    | 1         | 0.35%   |
| EVOO                   | 1         | 0.35%   |
| Chuwi                  | 1         | 0.35%   |
| BANGHO                 | 1         | 0.35%   |
| AWOW                   | 1         | 0.35%   |
| Avell High Performance | 1         | 0.35%   |
| Alienware              | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 13        | 4.51%   |
| HP Pavilion g6                                        | 3         | 1.04%   |
| TUXEDO Polaris 15 AMD Gen1                            | 2         | 0.69%   |
| TUXEDO InfinityBook S 15 Gen6                         | 2         | 0.69%   |
| TUXEDO InfinityBook S 14 Gen6                         | 2         | 0.69%   |
| TUXEDO InfinityBook Pro 14 Gen6                       | 2         | 0.69%   |
| TUXEDO Aura 15 Gen1                                   | 2         | 0.69%   |
| Standard MT40II                                       | 2         | 0.69%   |
| Lenovo IdeaPad 5 15ARE05 81YQ                         | 2         | 0.69%   |
| Lenovo IdeaPad 330S-15ARR 81FB                        | 2         | 0.69%   |
| Lenovo IdeaPad 320-15IKB 80XL                         | 2         | 0.69%   |
| HP ZBook Studio G3                                    | 2         | 0.69%   |
| HP Notebook                                           | 2         | 0.69%   |
| HP ENVY 15                                            | 2         | 0.69%   |
| HP 2000                                               | 2         | 0.69%   |
| Dell XPS 13 9380                                      | 2         | 0.69%   |
| Dell Latitude E6540                                   | 2         | 0.69%   |
| Dell Latitude 5400                                    | 2         | 0.69%   |
| Dell Inspiron 5570                                    | 2         | 0.69%   |
| ASUS VivoBook_ASUSLaptop X571GT_F571GT                | 2         | 0.69%   |
| Apple MacBookPro8,1                                   | 2         | 0.69%   |
| Acer TravelMate P446-M                                | 2         | 0.69%   |
| Viglen VUB1                                           | 1         | 0.35%   |
| TUXEDO Stellaris Intel Gen3 (TGL)                     | 1         | 0.35%   |
| TUXEDO Stellaris AMD Gen3 (CZN)                       | 1         | 0.35%   |
| TUXEDO Pulse 15 Gen1                                  | 1         | 0.35%   |
| TUXEDO Polaris AMD Gen3 (CZN)                         | 1         | 0.35%   |
| TUXEDO Polaris 17 AMD Gen1                            | 1         | 0.35%   |
| TUXEDO P95_HR                                         | 1         | 0.35%   |
| TUXEDO P95_HP                                         | 1         | 0.35%   |
| TUXEDO P7xxTM1                                        | 1         | 0.35%   |
| TUXEDO InfinityBook S 14 v5                           | 1         | 0.35%   |
| TUXEDO InfinityBook Pro 15 v4                         | 1         | 0.35%   |
| TUXEDO Book_XA1510                                    | 1         | 0.35%   |
| TUXEDO Book XP1511                                    | 1         | 0.35%   |
| TUXEDO Book XP15 / XP17 Gen12                         | 1         | 0.35%   |
| Toshiba Satellite S55-C                               | 1         | 0.35%   |
| Toshiba Satellite P750                                | 1         | 0.35%   |
| Toshiba Satellite P300                                | 1         | 0.35%   |
| Timi TM1701                                           | 1         | 0.35%   |
| Sony VPCEK20AL                                        | 1         | 0.35%   |
| Sony VPCEJ1L1E                                        | 1         | 0.35%   |
| Sony VPCEA47FX                                        | 1         | 0.35%   |
| Sony VPCCW25FL                                        | 1         | 0.35%   |
| Sony SVS13A25PBS                                      | 1         | 0.35%   |
| Samsung 905S3G/906S3G/915S3G/9305SG                   | 1         | 0.35%   |
| Samsung 530U3C/530U4C/532U3C                          | 1         | 0.35%   |
| Samsung 340XAA/350XAA/550XAA                          | 1         | 0.35%   |
| Samsung 305V4A/305V5A                                 | 1         | 0.35%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.35%   |
| Razer Blade Stealth                                   | 1         | 0.35%   |
| Quanta R460-L.BG22P1                                  | 1         | 0.35%   |
| Positivo C14CR21TV                                    | 1         | 0.35%   |
| PC Specialist OctaneVI 15                             | 1         | 0.35%   |
| Packard Bell ENLE11BZ                                 | 1         | 0.35%   |
| Packard Bell EasyNote TM98                            | 1         | 0.35%   |
| Packard Bell EasyNote LE69KB                          | 1         | 0.35%   |
| MSI Vector GP66 12UGS                                 | 1         | 0.35%   |
| MSI Prestige 15 A10SC                                 | 1         | 0.35%   |
| MSI Prestige 14 A10SC                                 | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 28        | 9.72%   |
| Dell Latitude          | 15        | 5.21%   |
| Lenovo IdeaPad         | 14        | 4.86%   |
| Unknown                | 13        | 4.51%   |
| Acer Aspire            | 12        | 4.17%   |
| HP Pavilion            | 11        | 3.82%   |
| Dell Inspiron          | 11        | 3.82%   |
| TUXEDO InfinityBook    | 8         | 2.78%   |
| HP EliteBook           | 8         | 2.78%   |
| Dell XPS               | 7         | 2.43%   |
| ASUS VivoBook          | 6         | 2.08%   |
| HP ENVY                | 5         | 1.74%   |
| TUXEDO Polaris         | 4         | 1.39%   |
| HP ZBook               | 4         | 1.39%   |
| HP Laptop              | 4         | 1.39%   |
| Acer Swift             | 4         | 1.39%   |
| TUXEDO Book            | 3         | 1.04%   |
| Toshiba Satellite      | 3         | 1.04%   |
| Lenovo ThinkBook       | 3         | 1.04%   |
| HP ProBook             | 3         | 1.04%   |
| HP Compaq              | 3         | 1.04%   |
| Fujitsu LIFEBOOK       | 3         | 1.04%   |
| Apple MacBookPro8      | 3         | 1.04%   |
| TUXEDO Stellaris       | 2         | 0.69%   |
| TUXEDO P95             | 2         | 0.69%   |
| TUXEDO Aura            | 2         | 0.69%   |
| Standard MT40II        | 2         | 0.69%   |
| Packard Bell EasyNote  | 2         | 0.69%   |
| MSI Prestige           | 2         | 0.69%   |
| MSI Modern             | 2         | 0.69%   |
| Lenovo Yoga            | 2         | 0.69%   |
| HP Notebook            | 2         | 0.69%   |
| HP 2000                | 2         | 0.69%   |
| Dell Vostro            | 2         | 0.69%   |
| Apple MacBookPro11     | 2         | 0.69%   |
| Acer TravelMate        | 2         | 0.69%   |
| Viglen VUB1            | 1         | 0.35%   |
| TUXEDO Pulse           | 1         | 0.35%   |
| TUXEDO P7xxTM1         | 1         | 0.35%   |
| Timi TM1701            | 1         | 0.35%   |
| Sony VPCEK20AL         | 1         | 0.35%   |
| Sony VPCEJ1L1E         | 1         | 0.35%   |
| Sony VPCEA47FX         | 1         | 0.35%   |
| Sony VPCCW25FL         | 1         | 0.35%   |
| Sony SVS13A25PBS       | 1         | 0.35%   |
| Samsung 905S3G         | 1         | 0.35%   |
| Samsung 530U3C         | 1         | 0.35%   |
| Samsung 340XAA         | 1         | 0.35%   |
| Samsung 305V4A         | 1         | 0.35%   |
| Samsung 300E5EV        | 1         | 0.35%   |
| Razer Blade            | 1         | 0.35%   |
| Quanta R460-L.BG22P1   | 1         | 0.35%   |
| Positivo C14CR21TV     | 1         | 0.35%   |
| PC Specialist OctaneVI | 1         | 0.35%   |
| Packard Bell ENLE11BZ  | 1         | 0.35%   |
| MSI Vector             | 1         | 0.35%   |
| MSI GP73               | 1         | 0.35%   |
| MSI GP72               | 1         | 0.35%   |
| MSI GL62M              | 1         | 0.35%   |
| MSI GE70               | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 47        | 16.32%  |
| 2018 | 36        | 12.5%   |
| 2020 | 29        | 10.07%  |
| 2011 | 24        | 8.33%   |
| 2017 | 21        | 7.29%   |
| 2012 | 21        | 7.29%   |
| 2021 | 18        | 6.25%   |
| 2013 | 17        | 5.9%    |
| 2014 | 16        | 5.56%   |
| 2016 | 15        | 5.21%   |
| 2015 | 15        | 5.21%   |
| 2010 | 9         | 3.13%   |
| 2008 | 7         | 2.43%   |
| 2009 | 6         | 2.08%   |
| 2007 | 6         | 2.08%   |
| 2022 | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 288       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 256       | 88.58%  |
| Enabled  | 33        | 11.42%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 285       | 98.96%  |
| Yes  | 3         | 1.04%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 86        | 29.66%  |
| 16.01-24.0  | 57        | 19.66%  |
| 3.01-4.0    | 49        | 16.9%   |
| 8.01-16.0   | 49        | 16.9%   |
| 32.01-64.0  | 29        | 10%     |
| 64.01-256.0 | 8         | 2.76%   |
| 1.01-2.0    | 7         | 2.41%   |
| 24.01-32.0  | 3         | 1.03%   |
| 2.01-3.0    | 2         | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 95        | 30.94%  |
| 1.01-2.0   | 84        | 27.36%  |
| 4.01-8.0   | 56        | 18.24%  |
| 3.01-4.0   | 54        | 17.59%  |
| 8.01-16.0  | 14        | 4.56%   |
| 0.51-1.0   | 3         | 0.98%   |
| 16.01-24.0 | 1         | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 212       | 73.1%   |
| 2      | 70        | 24.14%  |
| 3      | 7         | 2.41%   |
| 0      | 1         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 199       | 69.1%   |
| Yes       | 89        | 30.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 230       | 79.58%  |
| No        | 59        | 20.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 286       | 99.31%  |
| No        | 2         | 0.69%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 241       | 83.39%  |
| No        | 48        | 16.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 48        | 16.67%  |
| USA                | 36        | 12.5%   |
| Brazil             | 23        | 7.99%   |
| France             | 16        | 5.56%   |
| Russia             | 11        | 3.82%   |
| Italy              | 11        | 3.82%   |
| UK                 | 10        | 3.47%   |
| India              | 10        | 3.47%   |
| Argentina          | 9         | 3.13%   |
| Canada             | 8         | 2.78%   |
| Netherlands        | 7         | 2.43%   |
| Mexico             | 7         | 2.43%   |
| Spain              | 6         | 2.08%   |
| Poland             | 6         | 2.08%   |
| Austria            | 5         | 1.74%   |
| Ukraine            | 4         | 1.39%   |
| Switzerland        | 4         | 1.39%   |
| Hungary            | 4         | 1.39%   |
| Finland            | 4         | 1.39%   |
| Turkey             | 3         | 1.04%   |
| South Africa       | 3         | 1.04%   |
| Portugal           | 3         | 1.04%   |
| Norway             | 3         | 1.04%   |
| Iran               | 3         | 1.04%   |
| Greece             | 3         | 1.04%   |
| Dominican Republic | 3         | 1.04%   |
| Chile              | 3         | 1.04%   |
| Belgium            | 3         | 1.04%   |
| Australia          | 3         | 1.04%   |
| Sweden             | 2         | 0.69%   |
| Malaysia           | 2         | 0.69%   |
| Japan              | 2         | 0.69%   |
| Ireland            | 2         | 0.69%   |
| Indonesia          | 2         | 0.69%   |
| Ecuador            | 2         | 0.69%   |
| Slovenia           | 1         | 0.35%   |
| Singapore          | 1         | 0.35%   |
| Serbia             | 1         | 0.35%   |
| Philippines        | 1         | 0.35%   |
| Myanmar            | 1         | 0.35%   |
| Libya              | 1         | 0.35%   |
| Latvia             | 1         | 0.35%   |
| Kenya              | 1         | 0.35%   |
| Jordan             | 1         | 0.35%   |
| Hong Kong          | 1         | 0.35%   |
| Honduras           | 1         | 0.35%   |
| Guatemala          | 1         | 0.35%   |
| Ghana              | 1         | 0.35%   |
| El Salvador        | 1         | 0.35%   |
| Egypt              | 1         | 0.35%   |
| Croatia            | 1         | 0.35%   |
| Colombia           | 1         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 6         | 2.05%   |
| Moscow             | 5         | 1.71%   |
| Ravensburg         | 4         | 1.37%   |
| Budapest           | 4         | 1.37%   |
| Berlin             | 4         | 1.37%   |
| Tehran             | 3         | 1.03%   |
| Santo Domingo Este | 3         | 1.03%   |
| Montreal           | 3         | 1.03%   |
| Hamburg            | 3         | 1.03%   |
| Athens             | 3         | 1.03%   |
| Vienna             | 2         | 0.68%   |
| Stuttgart          | 2         | 0.68%   |
| St Petersburg      | 2         | 0.68%   |
| San Miguel         | 2         | 0.68%   |
| San Francisco      | 2         | 0.68%   |
| Paris              | 2         | 0.68%   |
| Niterói           | 2         | 0.68%   |
| Munich             | 2         | 0.68%   |
| Mumbai             | 2         | 0.68%   |
| Milan              | 2         | 0.68%   |
| Lisbon             | 2         | 0.68%   |
| Kyiv               | 2         | 0.68%   |
| Kassel             | 2         | 0.68%   |
| Istanbul           | 2         | 0.68%   |
| Gurgaon            | 2         | 0.68%   |
| Dublin             | 2         | 0.68%   |
| Cologne            | 2         | 0.68%   |
| Burzaco            | 2         | 0.68%   |
| Brasília          | 2         | 0.68%   |
| Belo Horizonte     | 2         | 0.68%   |
| Bamberg            | 2         | 0.68%   |
| Austin             | 2         | 0.68%   |
| Zurich             | 1         | 0.34%   |
| Zambrów           | 1         | 0.34%   |
| Zagreb             | 1         | 0.34%   |
| Yuma               | 1         | 0.34%   |
| Yangon             | 1         | 0.34%   |
| Wuppertal          | 1         | 0.34%   |
| Wolfsburg          | 1         | 0.34%   |
| Woking             | 1         | 0.34%   |
| West Jordan        | 1         | 0.34%   |
| West End           | 1         | 0.34%   |
| Waterloo           | 1         | 0.34%   |
| Warsaw             | 1         | 0.34%   |
| Waiblingen         | 1         | 0.34%   |
| Vista Serrana      | 1         | 0.34%   |
| Vernier            | 1         | 0.34%   |
| Vendelso           | 1         | 0.34%   |
| Vear               | 1         | 0.34%   |
| Vantaa             | 1         | 0.34%   |
| Vancouver          | 1         | 0.34%   |
| Valros             | 1         | 0.34%   |
| Usingen            | 1         | 0.34%   |
| Uniontown          | 1         | 0.34%   |
| Udine              | 1         | 0.34%   |
| Tuscola            | 1         | 0.34%   |
| Turku              | 1         | 0.34%   |
| Trzin              | 1         | 0.34%   |
| Tripoli            | 1         | 0.34%   |
| Totana             | 1         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives  | Percent |
|---------------------------|-----------|---------|---------|
| Samsung Electronics       | 80        | 103     | 22.41%  |
| WDC                       | 40        | 42      | 11.2%   |
| Seagate                   | 38        | 41      | 10.64%  |
| Toshiba                   | 30        | 33      | 8.4%    |
| Unknown                   | 23        | 26      | 6.44%   |
| Sandisk                   | 23        | 26      | 6.44%   |
| Kingston                  | 14        | 14      | 3.92%   |
| SK Hynix                  | 12        | 14      | 3.36%   |
| Crucial                   | 12        | 14      | 3.36%   |
| Intel                     | 11        | 14      | 3.08%   |
| HGST                      | 8         | 11      | 2.24%   |
| A-DATA Technology         | 8         | 9       | 2.24%   |
| Micron Technology         | 6         | 7       | 1.68%   |
| Hitachi                   | 6         | 6       | 1.68%   |
| China                     | 5         | 6       | 1.4%    |
| Apple                     | 5         | 5       | 1.4%    |
| SPCC                      | 4         | 4       | 1.12%   |
| PNY                       | 4         | 6       | 1.12%   |
| LITEON                    | 2         | 2       | 0.56%   |
| Lenovo                    | 2         | 2       | 0.56%   |
| Intenso                   | 2         | 3       | 0.56%   |
| Vaseky                    | 1         | 1       | 0.28%   |
| USB30                     | 1         | 1       | 0.28%   |
| Union Memory              | 1         | 1       | 0.28%   |
| TO Exter                  | 1         | 1       | 0.28%   |
| Realtek Semiconductor     | 1         | 2       | 0.28%   |
| OWC                       | 1         | 1       | 0.28%   |
| Netac                     | 1         | 1       | 0.28%   |
| Micron/Crucial Technology | 1         | 1       | 0.28%   |
| LITEONIT                  | 1         | 1       | 0.28%   |
| LaCie                     | 1         | 1       | 0.28%   |
| KIOXIA                    | 1         | 1       | 0.28%   |
| KingSpec                  | 1         | 1       | 0.28%   |
| KimMiDi                   | 1         | 1       | 0.28%   |
| JMicron                   | 1         | 1       | 0.28%   |
| Hewlett-Packard           | 1         | Unknown | 0.28%   |
| Gigabyte Technology       | 1         | 1       | 0.28%   |
| GALAX TA                  | 1         | 1       | 0.28%   |
| Fujitsu                   | 1         | 1       | 0.28%   |
| DOGFISH                   | 1         | 1       | 0.28%   |
| Corsair                   | 1         | 1       | 0.28%   |
| BIWIN                     | 1         | 1       | 0.28%   |
| Unknown                   | 1         | 1       | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  64GB               | 5         | 1.36%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 1.36%   |
| Samsung NVMe SSD Drive 1TB           | 5         | 1.36%   |
| Unknown MMC Card  32GB               | 4         | 1.09%   |
| Toshiba MQ04ABF100 1TB               | 4         | 1.09%   |
| Toshiba MQ01ABD100 1TB               | 4         | 1.09%   |
| SK Hynix NVMe SSD Drive 256GB        | 4         | 1.09%   |
| Seagate ST9500325AS 500GB            | 4         | 1.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 1.09%   |
| Sandisk NVMe SSD Drive 512GB         | 4         | 1.09%   |
| Samsung SSD 970 EVO Plus 1TB         | 4         | 1.09%   |
| Samsung SSD 860 EVO M.2 250GB        | 4         | 1.09%   |
| Samsung NVMe SSD Drive 512GB         | 4         | 1.09%   |
| Samsung NVMe SSD Drive 500GB         | 4         | 1.09%   |
| WDC WD10JPVX-22JC3T0 1TB             | 3         | 0.82%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.82%   |
| Seagate ST1000LX015-1U7172 1TB       | 3         | 0.82%   |
| Samsung SSD 860 EVO M.2 500GB        | 3         | 0.82%   |
| Samsung SSD 860 EVO 500GB            | 3         | 0.82%   |
| Samsung SSD 750 EVO 250GB            | 3         | 0.82%   |
| Samsung NVMe SSD Drive 2TB           | 3         | 0.82%   |
| Samsung NVMe SSD Drive 250GB         | 3         | 0.82%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.54%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 2         | 0.54%   |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 0.54%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 0.54%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB | 2         | 0.54%   |
| Unknown SD64G  64GB                  | 2         | 0.54%   |
| Unknown SD/MMC/MS PRO 999GB          | 2         | 0.54%   |
| Unknown MMC128  128GB                | 2         | 0.54%   |
| Unknown MMC Card  16GB               | 2         | 0.54%   |
| Toshiba MQ01ACF050 500GB             | 2         | 0.54%   |
| SPCC Solid State Disk 120GB          | 2         | 0.54%   |
| Seagate Expansion Desk 10TB          | 2         | 0.54%   |
| Seagate BUP Slim BK 1TB              | 2         | 0.54%   |
| SanDisk X400 M.2 2280 512GB SSD      | 2         | 0.54%   |
| SanDisk SSD PLUS 480GB               | 2         | 0.54%   |
| SanDisk SSD PLUS 120GB               | 2         | 0.54%   |
| SanDisk SDSSDA240G 240GB             | 2         | 0.54%   |
| Samsung SSD 980 PRO 1TB              | 2         | 0.54%   |
| Samsung SSD 970 EVO Plus 500GB       | 2         | 0.54%   |
| Samsung SSD 970 EVO 500GB            | 2         | 0.54%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.54%   |
| Samsung SSD 850 EVO 250GB            | 2         | 0.54%   |
| Samsung NVMe SSD Drive 1024GB        | 2         | 0.54%   |
| Samsung MZVLB256HAHQ-00000 256GB     | 2         | 0.54%   |
| Samsung MZALQ512HALU-000L2 512GB     | 2         | 0.54%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 2         | 0.54%   |
| Kingston SA400S37480G 480GB SSD      | 2         | 0.54%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 0.54%   |
| Intel NVMe SSD Drive 512GB           | 2         | 0.54%   |
| Hitachi HTS547550A9E384 500GB        | 2         | 0.54%   |
| Hitachi HTS545050A7E380 500GB        | 2         | 0.54%   |
| HGST HTS725050A7E630 500GB           | 2         | 0.54%   |
| HGST HTS545050A7E380 500GB           | 2         | 0.54%   |
| Crucial CT250MX500SSD1 250GB         | 2         | 0.54%   |
| China SATA SSD 240GB                 | 2         | 0.54%   |
| WDC WDS500G3X0C-00SJG0 500GB         | 1         | 0.27%   |
| WDC WDS500G2B0B-00YS70 500GB SSD     | 1         | 0.27%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 38     | 36.46%  |
| WDC                 | 22        | 24     | 22.92%  |
| Toshiba             | 21        | 24     | 21.88%  |
| HGST                | 8         | 11     | 8.33%   |
| Hitachi             | 6         | 6      | 6.25%   |
| Unknown             | 2         | 2      | 2.08%   |
| Samsung Electronics | 1         | 1      | 1.04%   |
| Fujitsu             | 1         | 1      | 1.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 39        | 49     | 29.32%  |
| SanDisk             | 16        | 16     | 12.03%  |
| Kingston            | 11        | 11     | 8.27%   |
| Crucial             | 11        | 13     | 8.27%   |
| WDC                 | 7         | 7      | 5.26%   |
| A-DATA Technology   | 6         | 7      | 4.51%   |
| China               | 5         | 6      | 3.76%   |
| SPCC                | 4         | 4      | 3.01%   |
| PNY                 | 4         | 6      | 3.01%   |
| Apple               | 4         | 4      | 3.01%   |
| Micron Technology   | 3         | 4      | 2.26%   |
| Seagate             | 2         | 2      | 1.5%    |
| LITEON              | 2         | 2      | 1.5%    |
| Intenso             | 2         | 3      | 1.5%    |
| Intel               | 2         | 2      | 1.5%    |
| Vaseky              | 1         | 1      | 0.75%   |
| USB30               | 1         | 1      | 0.75%   |
| Unknown             | 1         | 1      | 0.75%   |
| Union Memory        | 1         | 1      | 0.75%   |
| Toshiba             | 1         | 1      | 0.75%   |
| TO Exter            | 1         | 1      | 0.75%   |
| SK Hynix            | 1         | 1      | 0.75%   |
| OWC                 | 1         | 1      | 0.75%   |
| Netac               | 1         | 1      | 0.75%   |
| LITEONIT            | 1         | 1      | 0.75%   |
| KingSpec            | 1         | 1      | 0.75%   |
| JMicron             | 1         | 1      | 0.75%   |
| Gigabyte Technology | 1         | 1      | 0.75%   |
| DOGFISH             | 1         | 1      | 0.75%   |
| BIWIN               | 1         | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 122       | 151    | 35.67%  |
| NVMe    | 101       | 124    | 29.53%  |
| HDD     | 93        | 107    | 27.19%  |
| MMC     | 21        | 24     | 6.14%   |
| Unknown | 5         | 4      | 1.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 186       | 248    | 57.76%  |
| NVMe | 101       | 124    | 31.37%  |
| MMC  | 21        | 24     | 6.52%   |
| SAS  | 14        | 14     | 4.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 139       | 168    | 64.95%  |
| 0.51-1.0   | 65        | 78     | 30.37%  |
| 1.01-2.0   | 7         | 9      | 3.27%   |
| 4.01-10.0  | 2         | 2      | 0.93%   |
| 3.01-4.0   | 1         | 1      | 0.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 90        | 30.82%  |
| 251-500        | 87        | 29.79%  |
| 501-1000       | 40        | 13.7%   |
| 51-100         | 25        | 8.56%   |
| 1001-2000      | 16        | 5.48%   |
| 21-50          | 15        | 5.14%   |
| 1-20           | 7         | 2.4%    |
| 2001-3000      | 6         | 2.05%   |
| More than 3000 | 3         | 1.03%   |
| Unknown        | 3         | 1.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 101       | 34.01%  |
| 101-250        | 58        | 19.53%  |
| 21-50          | 56        | 18.86%  |
| 51-100         | 40        | 13.47%  |
| 251-500        | 20        | 6.73%   |
| 501-1000       | 13        | 4.38%   |
| 1001-2000      | 4         | 1.35%   |
| Unknown        | 3         | 1.01%   |
| More than 3000 | 2         | 0.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 11.76%  |
| WDC WD6400BPVT-60HXZT3 640GB        | 1         | 1      | 5.88%   |
| WDC WD5000BPVT-00HXZT1 500GB        | 1         | 1      | 5.88%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 5.88%   |
| Toshiba MK5055GSX 500GB             | 1         | 1      | 5.88%   |
| Toshiba MK2561GSYN 250GB            | 1         | 1      | 5.88%   |
| Seagate ST9750420AS 752GB           | 1         | 1      | 5.88%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 5.88%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 5.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 5.88%   |
| PNY SSD2SC120G3LC709B121-460I 120GB | 1         | 1      | 5.88%   |
| Kingston SNS4151S316G 16GB SSD      | 1         | 1      | 5.88%   |
| HGST HTS725032A7E630 320GB          | 1         | 2      | 5.88%   |
| HGST HTS541075A9E680 752GB          | 1         | 1      | 5.88%   |
| Crucial CT500P1SSD8 500GB           | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 6         | 6      | 35.29%  |
| Seagate  | 4         | 4      | 23.53%  |
| WDC      | 2         | 2      | 11.76%  |
| HGST     | 2         | 3      | 11.76%  |
| PNY      | 1         | 1      | 5.88%   |
| Kingston | 1         | 1      | 5.88%   |
| Crucial  | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 6         | 6      | 42.86%  |
| Seagate | 4         | 4      | 28.57%  |
| WDC     | 2         | 2      | 14.29%  |
| HGST    | 2         | 3      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 15     | 82.35%  |
| SSD  | 2         | 2      | 11.76%  |
| NVMe | 1         | 1      | 5.88%   |

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
| Detected | 167       | 236    | 54.75%  |
| Works    | 121       | 156    | 39.67%  |
| Malfunc  | 17        | 18     | 5.57%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 204       | 61.82%  |
| Samsung Electronics          | 45        | 13.64%  |
| AMD                          | 24        | 7.27%   |
| Sandisk                      | 17        | 5.15%   |
| SK Hynix                     | 10        | 3.03%   |
| Toshiba America Info Systems | 7         | 2.12%   |
| Micron Technology            | 3         | 0.91%   |
| Kingston Technology Company  | 3         | 0.91%   |
| Realtek Semiconductor        | 2         | 0.61%   |
| Nvidia                       | 2         | 0.61%   |
| Micron/Crucial Technology    | 2         | 0.61%   |
| Lenovo                       | 2         | 0.61%   |
| KIOXIA                       | 2         | 0.61%   |
| ADATA Technology             | 2         | 0.61%   |
| Union Memory (Shenzhen)      | 1         | 0.3%    |
| Silicon Motion               | 1         | 0.3%    |
| Shenzhen Longsys Electronics | 1         | 0.3%    |
| Phison Electronics           | 1         | 0.3%    |
| Apple                        | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 30        | 8.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 29        | 8.36%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 26        | 7.49%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 21        | 6.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 18        | 5.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 14        | 4.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 12        | 3.46%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 3.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9         | 2.59%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 8         | 2.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8         | 2.31%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 2.31%   |
| Samsung NVMe SSD Controller 980                                                  | 7         | 2.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 2.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 1.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 1.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 1.73%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 1.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 1.44%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 1.15%   |
| Sandisk PC SN520 NVMe SSD                                                        | 4         | 1.15%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4         | 1.15%   |
| Intel SSD 660P Series                                                            | 4         | 1.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.15%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 1.15%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.86%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.86%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 0.86%   |
| Micron Non-Volatile memory controller                                            | 3         | 0.86%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 0.86%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.86%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 0.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 0.86%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 2         | 0.58%   |
| SK Hynix Non-Volatile memory controller                                          | 2         | 0.58%   |
| SK Hynix Gold P31 SSD                                                            | 2         | 0.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.58%   |
| Samsung Electronics SATA controller                                              | 2         | 0.58%   |
| Realtek Realtek Non-Volatile memory controller                                   | 2         | 0.58%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 0.58%   |
| KIOXIA Non-Volatile memory controller                                            | 2         | 0.58%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 2         | 0.58%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 2         | 0.58%   |
| Intel Non-Volatile memory controller                                             | 2         | 0.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 0.58%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2         | 0.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 0.58%   |
| ADATA Non-Volatile memory controller                                             | 2         | 0.58%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.29%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.29%   |
| SK Hynix BC511                                                                   | 1         | 0.29%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.29%   |
| Shenzhen Longsys Non-Volatile memory controller                                  | 1         | 0.29%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.29%   |
| Samsung Apple PCIe SSD                                                           | 1         | 0.29%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.29%   |
| Nvidia MCP79 AHCI Controller                                                     | 1         | 0.29%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 0.29%   |
| Nvidia MCP51 IDE                                                                 | 1         | 0.29%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 208       | 61.18%  |
| NVMe | 103       | 30.29%  |
| RAID | 18        | 5.29%   |
| IDE  | 11        | 3.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 251       | 87.15%  |
| AMD    | 37        | 12.85%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 4.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 10        | 3.47%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 3.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 9         | 3.13%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 2.08%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 2.08%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.74%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.39%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.39%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 1.39%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 1.39%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 4         | 1.39%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.39%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.39%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 1.39%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 1.04%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 1.04%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 1.04%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.04%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.04%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.04%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 1.04%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.04%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 1.04%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.04%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.04%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 1.04%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz        | 2         | 0.69%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 2         | 0.69%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.69%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 0.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.69%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 0.69%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.69%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.69%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.69%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 0.69%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.69%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 0.69%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 0.69%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.69%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.69%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.69%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 2         | 0.69%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.69%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.69%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.69%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 0.69%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 0.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 0.69%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.69%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 0.69%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 0.69%   |
| AMD E-300 APU with Radeon HD Graphics         | 2         | 0.69%   |
| Intel Processor 5Y70 CPU @ 1.10GHz            | 1         | 0.35%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.35%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.35%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.35%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 106       | 36.81%  |
| Intel Core i5           | 70        | 24.31%  |
| Intel Core i3           | 18        | 6.25%   |
| Other                   | 15        | 5.21%   |
| Intel Celeron           | 12        | 4.17%   |
| AMD Ryzen 5             | 12        | 4.17%   |
| Intel Core 2 Duo        | 9         | 3.13%   |
| AMD Ryzen 7             | 9         | 3.13%   |
| Intel Pentium           | 7         | 2.43%   |
| Intel Pentium Silver    | 3         | 1.04%   |
| Intel Atom              | 3         | 1.04%   |
| AMD E                   | 3         | 1.04%   |
| AMD A8                  | 3         | 1.04%   |
| Intel Pentium Dual      | 2         | 0.69%   |
| Intel Genuine           | 2         | 0.69%   |
| AMD Turion 64 X2 Mobile | 2         | 0.69%   |
| AMD Ryzen 9             | 2         | 0.69%   |
| AMD A6                  | 2         | 0.69%   |
| Intel Pentium Dual-Core | 1         | 0.35%   |
| Intel Core m5           | 1         | 0.35%   |
| Intel Core m3           | 1         | 0.35%   |
| Intel Core i9           | 1         | 0.35%   |
| AMD Quad-Core           | 1         | 0.35%   |
| AMD E1                  | 1         | 0.35%   |
| AMD Athlon II           | 1         | 0.35%   |
| AMD A10                 | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 124       | 43.06%  |
| 2      | 123       | 42.71%  |
| 6      | 23        | 7.99%   |
| 8      | 14        | 4.86%   |
| 1      | 2         | 0.69%   |
| 16     | 1         | 0.35%   |
| 14     | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 288       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 224       | 77.78%  |
| 1      | 64        | 22.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 287       | 99.65%  |
| 32-bit         | 1         | 0.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 22.71%  |
| 0x206a7    | 20        | 6.78%   |
| 0x806ec    | 19        | 6.44%   |
| 0x306a9    | 19        | 6.44%   |
| 0x906ea    | 13        | 4.41%   |
| 0x806ea    | 13        | 4.41%   |
| 0x40651    | 11        | 3.73%   |
| 0x806e9    | 10        | 3.39%   |
| 0x806c1    | 10        | 3.39%   |
| 0x306c3    | 9         | 3.05%   |
| 0x406e3    | 8         | 2.71%   |
| 0x906e9    | 7         | 2.37%   |
| 0x306d4    | 7         | 2.37%   |
| 0x806eb    | 5         | 1.69%   |
| 0x08600103 | 5         | 1.69%   |
| 0xa0652    | 4         | 1.36%   |
| 0x1067a    | 4         | 1.36%   |
| 0xa0660    | 3         | 1.02%   |
| 0x706e5    | 3         | 1.02%   |
| 0x506e3    | 3         | 1.02%   |
| 0x406c3    | 3         | 1.02%   |
| 0x30678    | 3         | 1.02%   |
| 0x20655    | 3         | 1.02%   |
| 0x10676    | 3         | 1.02%   |
| 0x0a50000c | 3         | 1.02%   |
| 0x08600106 | 3         | 1.02%   |
| 0x08108109 | 3         | 1.02%   |
| 0x0810100b | 3         | 1.02%   |
| 0x05000119 | 3         | 1.02%   |
| 0x706a8    | 2         | 0.68%   |
| 0x706a1    | 2         | 0.68%   |
| 0x6fd      | 2         | 0.68%   |
| 0x20652    | 2         | 0.68%   |
| 0x08600104 | 2         | 0.68%   |
| 0x906ed    | 1         | 0.34%   |
| 0x906c0    | 1         | 0.34%   |
| 0x906a3    | 1         | 0.34%   |
| 0x806d1    | 1         | 0.34%   |
| 0x6fb      | 1         | 0.34%   |
| 0x506c9    | 1         | 0.34%   |
| 0x406c4    | 1         | 0.34%   |
| 0x40661    | 1         | 0.34%   |
| 0x106e5    | 1         | 0.34%   |
| 0x106ca    | 1         | 0.34%   |
| 0x08701013 | 1         | 0.34%   |
| 0x08608103 | 1         | 0.34%   |
| 0x08600102 | 1         | 0.34%   |
| 0x07030105 | 1         | 0.34%   |
| 0x0700010f | 1         | 0.34%   |
| 0x06006705 | 1         | 0.34%   |
| 0x0600611a | 1         | 0.34%   |
| 0x06001119 | 1         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 91        | 31.6%   |
| IvyBridge        | 24        | 8.33%   |
| SandyBridge      | 23        | 7.99%   |
| Haswell          | 22        | 7.64%   |
| Zen 2            | 13        | 4.51%   |
| Skylake          | 13        | 4.51%   |
| TigerLake        | 12        | 4.17%   |
| Silvermont       | 9         | 3.13%   |
| Penryn           | 9         | 3.13%   |
| CometLake        | 9         | 3.13%   |
| Broadwell        | 9         | 3.13%   |
| Goldmont plus    | 7         | 2.43%   |
| Westmere         | 6         | 2.08%   |
| IceLake          | 6         | 2.08%   |
| Core             | 4         | 1.39%   |
| Zen+             | 3         | 1.04%   |
| Zen 3            | 3         | 1.04%   |
| Zen              | 3         | 1.04%   |
| Bobcat           | 3         | 1.04%   |
| Puma             | 2         | 0.69%   |
| K8 Hammer        | 2         | 0.69%   |
| Jaguar           | 2         | 0.69%   |
| Excavator        | 2         | 0.69%   |
| Unknown          | 2         | 0.69%   |
| Tremont          | 1         | 0.35%   |
| Piledriver       | 1         | 0.35%   |
| P6               | 1         | 0.35%   |
| Nehalem          | 1         | 0.35%   |
| K10 Llano        | 1         | 0.35%   |
| K10              | 1         | 0.35%   |
| Goldmont         | 1         | 0.35%   |
| Bonnell          | 1         | 0.35%   |
| Alderlake Hybrid | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 234       | 63.07%  |
| Nvidia | 82        | 22.1%   |
| AMD    | 55        | 14.82%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 5.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 21        | 5.56%   |
| Intel UHD Graphics 620                                                                   | 21        | 5.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 5.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 3.17%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 3.17%   |
| AMD Renoir                                                                               | 12        | 3.17%   |
| Intel HD Graphics 620                                                                    | 11        | 2.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 2.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 2.65%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 2.38%   |
| Intel HD Graphics 630                                                                    | 8         | 2.12%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 1.85%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.32%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.32%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.32%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.32%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.06%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 1.06%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 1.06%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.06%   |
| Intel Comet Lake UHD Graphics                                                            | 4         | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.06%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.79%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.79%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.79%   |
| Intel HD Graphics 530                                                                    | 3         | 0.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.79%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 0.79%   |
| AMD Cezanne                                                                              | 3         | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.53%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 2         | 0.53%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.53%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 2         | 0.53%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 2         | 0.53%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.53%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 2         | 0.53%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.53%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.53%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 0.53%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.53%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.53%   |
| AMD Mars [Radeon HD 8730M]                                                               | 2         | 0.53%   |
| AMD Mars XTX [Radeon HD 8790M]                                                           | 2         | 0.53%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.26%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.26%   |
| Nvidia TU106BM [GeForce RTX 2060 Mobile]                                                 | 1         | 0.26%   |
| Nvidia TU104BM [GeForce RTX 2080 SUPER Mobile / Max-Q]                                   | 1         | 0.26%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.26%   |
| Nvidia GT215M [GeForce GTS 250M]                                                         | 1         | 0.26%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.26%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 157       | 54.51%  |
| Intel + Nvidia | 61        | 21.18%  |
| 1 x AMD        | 30        | 10.42%  |
| Intel + AMD    | 16        | 5.56%   |
| 1 x Nvidia     | 15        | 5.21%   |
| AMD + Nvidia   | 6         | 2.08%   |
| 2 x AMD        | 3         | 1.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 229       | 78.97%  |
| Proprietary | 57        | 19.66%  |
| Unknown     | 4         | 1.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 199       | 68.15%  |
| 1.01-2.0   | 30        | 10.27%  |
| 0.01-0.5   | 17        | 5.82%   |
| 3.01-4.0   | 15        | 5.14%   |
| 0.51-1.0   | 15        | 5.14%   |
| 5.01-6.0   | 8         | 2.74%   |
| 7.01-8.0   | 7         | 2.4%    |
| 2.01-3.0   | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 67        | 19.42%  |
| AU Optronics            | 60        | 17.39%  |
| LG Display              | 41        | 11.88%  |
| BOE                     | 41        | 11.88%  |
| Samsung Electronics     | 29        | 8.41%   |
| Dell                    | 13        | 3.77%   |
| Goldstar                | 10        | 2.9%    |
| Apple                   | 10        | 2.9%    |
| Chi Mei Optoelectronics | 8         | 2.32%   |
| Sharp                   | 7         | 2.03%   |
| PANDA                   | 6         | 1.74%   |
| Hewlett-Packard         | 6         | 1.74%   |
| Lenovo                  | 5         | 1.45%   |
| BenQ                    | 5         | 1.45%   |
| Acer                    | 5         | 1.45%   |
| Philips                 | 3         | 0.87%   |
| LGD                     | 3         | 0.87%   |
| InfoVision              | 3         | 0.87%   |
| Ancor Communications    | 3         | 0.87%   |
| Unknown (AAA)           | 2         | 0.58%   |
| Fujitsu Siemens         | 2         | 0.58%   |
| ASUSTek Computer        | 2         | 0.58%   |
| AOC                     | 2         | 0.58%   |
| Vestel Elektronik       | 1         | 0.29%   |
| UPD                     | 1         | 0.29%   |
| Unknown                 | 1         | 0.29%   |
| LG Philips              | 1         | 0.29%   |
| Lacie                   | 1         | 0.29%   |
| KTC                     | 1         | 0.29%   |
| JDI                     | 1         | 0.29%   |
| InnoLux Display         | 1         | 0.29%   |
| Iiyama                  | 1         | 0.29%   |
| GDH                     | 1         | 0.29%   |
| Eizo                    | 1         | 0.29%   |
| CSO                     | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 1.42%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 4         | 1.14%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch      | 4         | 1.14%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.85%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 3         | 0.85%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 3         | 0.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.85%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 0.85%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 3         | 0.85%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch        | 3         | 0.85%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.85%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 2         | 0.57%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 2         | 0.57%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 2         | 0.57%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.57%   |
| LGD LCD Monitor 1920x1080                                             | 2         | 0.57%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 2         | 0.57%   |
| LG Display LCD Monitor LGD053F 1920x1080 340x190mm 15.3-inch          | 2         | 0.57%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 0.57%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 2         | 0.57%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch           | 2         | 0.57%   |
| Dell U3415W DELA0AA 3440x1440 798x335mm 34.1-inch                     | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch      | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch      | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 0.57%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                 | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch         | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO282B 3840x2160 293x165mm 13.2-inch        | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch         | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 340x190mm 15.3-inch        | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch         | 2         | 0.57%   |
| Ancor Communications ASUS PB238 ACI23A2 1920x1080 509x286mm 23.0-inch | 2         | 0.57%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                         | 1         | 0.28%   |
| UPD LCD801 UPD4843 1920x1080 708x398mm 32.0-inch                      | 1         | 0.28%   |
| Unknown LCD Monitor Sony Nvidia Default Flat Panel 1366x768           | 1         | 0.28%   |
| Unknown (AAA) LCDTV AAA3393 1360x768 890x500mm 40.2-inch              | 1         | 0.28%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch              | 1         | 0.28%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.28%   |
| Sharp LQ133Z1JW26 SHP1493 3200x1800 294x165mm 13.3-inch               | 1         | 0.28%   |
| Sharp LQ133M1JW48A SHP1531 1920x1080 294x165mm 13.3-inch              | 1         | 0.28%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.28%   |
| Sharp LCD Monitor SHP14C6 1920x1080 344x194mm 15.5-inch               | 1         | 0.28%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch               | 1         | 0.28%   |
| Sharp LCD Monitor SHP1445 3840x2160 350x190mm 15.7-inch               | 1         | 0.28%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch     | 1         | 0.28%   |
| Samsung Electronics SyncMaster SAM060D 1920x1080 531x299mm 24.0-inch  | 1         | 0.28%   |
| Samsung Electronics SyncMaster SAM041D 1920x1200 459x296mm 21.5-inch  | 1         | 0.28%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 518x324mm 24.1-inch   | 1         | 0.28%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch     | 1         | 0.28%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 0.28%   |
| Samsung Electronics S22B350 SAM08D4 1920x1080 477x268mm 21.5-inch     | 1         | 0.28%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 0.28%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.28%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 1         | 0.28%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.28%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch  | 1         | 0.28%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch  | 1         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 145       | 45.45%  |
| 1366x768 (WXGA)   | 89        | 27.9%   |
| 2560x1440 (QHD)   | 16        | 5.02%   |
| 1600x900 (HD+)    | 13        | 4.08%   |
| 3840x2160 (4K)    | 10        | 3.13%   |
| 1280x800 (WXGA)   | 10        | 3.13%   |
| 1440x900 (WXGA+)  | 6         | 1.88%   |
| 2880x1800         | 4         | 1.25%   |
| 1920x1200 (WUXGA) | 4         | 1.25%   |
| 3440x1440         | 3         | 0.94%   |
| 3200x1800 (QHD+)  | 3         | 0.94%   |
| 2560x1080         | 2         | 0.63%   |
| 2160x1440         | 2         | 0.63%   |
| 1280x1024 (SXGA)  | 2         | 0.63%   |
| 3840x2400         | 1         | 0.31%   |
| 3840x1100         | 1         | 0.31%   |
| 3840x1080         | 1         | 0.31%   |
| 3000x2000         | 1         | 0.31%   |
| 2560x1600         | 1         | 0.31%   |
| 2256x1504         | 1         | 0.31%   |
| 1920x1280         | 1         | 0.31%   |
| 1600x1200         | 1         | 0.31%   |
| 1360x768          | 1         | 0.31%   |
| 1280x768          | 1         | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 132       | 37.82%  |
| 13      | 61        | 17.48%  |
| 14      | 44        | 12.61%  |
| 24      | 19        | 5.44%   |
| 17      | 17        | 4.87%   |
| 27      | 13        | 3.72%   |
| 23      | 11        | 3.15%   |
| 11      | 9         | 2.58%   |
| 21      | 6         | 1.72%   |
| 34      | 5         | 1.43%   |
| 12      | 5         | 1.43%   |
| Unknown | 5         | 1.43%   |
| 31      | 4         | 1.15%   |
| 19      | 4         | 1.15%   |
| 48      | 2         | 0.57%   |
| 40      | 2         | 0.57%   |
| 32      | 2         | 0.57%   |
| 18      | 2         | 0.57%   |
| 84      | 1         | 0.29%   |
| 72      | 1         | 0.29%   |
| 54      | 1         | 0.29%   |
| 44      | 1         | 0.29%   |
| 29      | 1         | 0.29%   |
| 22      | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 203       | 59.01%  |
| 201-300     | 44        | 12.79%  |
| 501-600     | 39        | 11.34%  |
| 351-400     | 22        | 6.4%    |
| 401-500     | 11        | 3.2%    |
| 701-800     | 7         | 2.03%   |
| 601-700     | 5         | 1.45%   |
| Unknown     | 5         | 1.45%   |
| 1001-1500   | 3         | 0.87%   |
| 801-900     | 2         | 0.58%   |
| 1501-2000   | 2         | 0.58%   |
| 901-1000    | 1         | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 251       | 83.39%  |
| 16/10   | 30        | 9.97%   |
| 3/2     | 5         | 1.66%   |
| 21/9    | 5         | 1.66%   |
| Unknown | 5         | 1.66%   |
| 5/4     | 2         | 0.66%   |
| 4/3     | 1         | 0.33%   |
| 32/9    | 1         | 0.33%   |
| 3.40    | 1         | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 132       | 38.04%  |
| 81-90          | 81        | 23.34%  |
| 201-250        | 28        | 8.07%   |
| 71-80          | 23        | 6.63%   |
| 121-130        | 14        | 4.03%   |
| 301-350        | 13        | 3.75%   |
| 351-500        | 12        | 3.46%   |
| 51-60          | 10        | 2.88%   |
| 251-300        | 7         | 2.02%   |
| 61-70          | 5         | 1.44%   |
| Unknown        | 5         | 1.44%   |
| More than 1000 | 4         | 1.15%   |
| 151-200        | 4         | 1.15%   |
| 501-1000       | 4         | 1.15%   |
| 131-140        | 3         | 0.86%   |
| 141-150        | 2         | 0.58%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 130       | 38.35%  |
| 101-120       | 102       | 30.09%  |
| 51-100        | 57        | 16.81%  |
| 161-240       | 23        | 6.78%   |
| More than 240 | 15        | 4.42%   |
| 1-50          | 7         | 2.06%   |
| Unknown       | 5         | 1.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 230       | 78.23%  |
| 2     | 50        | 17.01%  |
| 3     | 10        | 3.4%    |
| 0     | 4         | 1.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 172       | 36.6%   |
| Realtek Semiconductor                 | 150       | 31.91%  |
| Qualcomm Atheros                      | 67        | 14.26%  |
| Broadcom                              | 24        | 5.11%   |
| Broadcom Limited                      | 11        | 2.34%   |
| Marvell Technology Group              | 6         | 1.28%   |
| Ralink                                | 5         | 1.06%   |
| MediaTek                              | 3         | 0.64%   |
| Hewlett-Packard                       | 3         | 0.64%   |
| ASIX Electronics                      | 3         | 0.64%   |
| Sierra Wireless                       | 2         | 0.43%   |
| Nvidia                                | 2         | 0.43%   |
| Lenovo                                | 2         | 0.43%   |
| JMicron Technology                    | 2         | 0.43%   |
| Huawei Technologies                   | 2         | 0.43%   |
| Xiaomi                                | 1         | 0.21%   |
| TP-Link                               | 1         | 0.21%   |
| Samsung Electronics                   | 1         | 0.21%   |
| Ralink Technology                     | 1         | 0.21%   |
| Qualcomm Atheros Communications       | 1         | 0.21%   |
| Novatek Microelectronics              | 1         | 0.21%   |
| NetGear                               | 1         | 0.21%   |
| Google                                | 1         | 0.21%   |
| Ericsson Business Mobile Networks     | 1         | 0.21%   |
| Edimax Technology                     | 1         | 0.21%   |
| DisplayLink                           | 1         | 0.21%   |
| Dell                                  | 1         | 0.21%   |
| BUFFALO                               | 1         | 0.21%   |
| ASUSTek Computer                      | 1         | 0.21%   |
| Apple                                 | 1         | 0.21%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.21%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 89        | 15.86%  |
| Intel Wi-Fi 6 AX200                                               | 31        | 5.53%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 4.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 22        | 3.92%   |
| Intel Wireless 8265 / 8275                                        | 20        | 3.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 2.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 15        | 2.67%   |
| Intel Wireless-AC 9260                                            | 13        | 2.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 1.78%   |
| Intel Wireless 7265                                               | 10        | 1.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.6%    |
| Intel Wireless 8260                                               | 9         | 1.6%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 9         | 1.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.43%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 1.07%   |
| Intel Wireless 7260                                               | 6         | 1.07%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 1.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.89%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 0.89%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 0.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.71%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.71%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.71%   |
| Intel Wireless 3165                                               | 4         | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.71%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.71%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.53%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.53%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.53%   |
| Intel WiFi Link 5100                                              | 3         | 0.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.53%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.53%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.53%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 0.53%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 0.53%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.53%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.36%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.36%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 2         | 0.36%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.36%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.36%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.36%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.36%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.36%   |
| Intel Wireless 3160                                               | 2         | 0.36%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 2         | 0.36%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2         | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 167       | 55.3%   |
| Qualcomm Atheros                      | 55        | 18.21%  |
| Realtek Semiconductor                 | 34        | 11.26%  |
| Broadcom                              | 20        | 6.62%   |
| Broadcom Limited                      | 8         | 2.65%   |
| Ralink                                | 5         | 1.66%   |
| MEDIATEK                              | 3         | 0.99%   |
| Sierra Wireless                       | 2         | 0.66%   |
| TP-Link                               | 1         | 0.33%   |
| Ralink Technology                     | 1         | 0.33%   |
| Qualcomm Atheros Communications       | 1         | 0.33%   |
| NetGear                               | 1         | 0.33%   |
| Edimax Technology                     | 1         | 0.33%   |
| BUFFALO                               | 1         | 0.33%   |
| ASUSTek Computer                      | 1         | 0.33%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 31        | 10.23%  |
| Intel Wireless 8265 / 8275                                     | 20        | 6.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 15        | 4.95%   |
| Intel Wireless-AC 9260                                         | 13        | 4.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 3.3%    |
| Intel Wireless 7265                                            | 10        | 3.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 2.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 2.97%   |
| Intel Wireless 8260                                            | 9         | 2.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 9         | 2.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 2.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 2.64%   |
| Intel Wireless 7260                                            | 6         | 1.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 6         | 1.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.65%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 1.65%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 1.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.32%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.32%   |
| Intel Wireless 3165                                            | 4         | 1.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 1.32%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.32%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 1.32%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.99%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 0.99%   |
| Intel WiFi Link 5100                                           | 3         | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 0.99%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.99%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 0.99%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.66%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.66%   |
| Realtek 802.11n WLAN Adapter                                   | 2         | 0.66%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 0.66%   |
| Intel Wireless 3160                                            | 2         | 0.66%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 2         | 0.66%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 0.66%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 0.66%   |
| Intel Centrino Wireless-N 2200                                 | 2         | 0.66%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.66%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 0.66%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 0.66%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 2         | 0.66%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 0.66%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 2         | 0.66%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 0.66%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 1         | 0.33%   |
| Sierra Wireless EM7421                                         | 1         | 0.33%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.33%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.33%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 1         | 0.33%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.33%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.33%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 133       | 54.73%  |
| Intel                    | 57        | 23.46%  |
| Qualcomm Atheros         | 19        | 7.82%   |
| Broadcom                 | 10        | 4.12%   |
| Marvell Technology Group | 6         | 2.47%   |
| Broadcom Limited         | 3         | 1.23%   |
| ASIX Electronics         | 3         | 1.23%   |
| Nvidia                   | 2         | 0.82%   |
| Lenovo                   | 2         | 0.82%   |
| JMicron Technology       | 2         | 0.82%   |
| Xiaomi                   | 1         | 0.41%   |
| Samsung Electronics      | 1         | 0.41%   |
| Hewlett-Packard          | 1         | 0.41%   |
| Google                   | 1         | 0.41%   |
| DisplayLink              | 1         | 0.41%   |
| Apple                    | 1         | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 89        | 35.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 23        | 9.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 22        | 8.76%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 6.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 6         | 2.39%   |
| Intel Ethernet Connection (6) I219-V                                           | 5         | 1.99%   |
| Intel Ethernet Connection (4) I219-LM                                          | 5         | 1.99%   |
| Realtek RTL8125 2.5GbE Controller                                              | 4         | 1.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 4         | 1.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 1.59%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.2%    |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.2%    |
| Intel Ethernet Connection (6) I219-LM                                          | 3         | 1.2%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.2%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.8%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.8%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.8%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 0.8%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.8%    |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.8%    |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.8%    |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.8%    |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.8%    |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.8%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.4%    |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.4%    |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.4%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.4%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.4%    |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.4%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.4%    |
| Lenovo ThinkPad TBT3 LAN                                                       | 1         | 0.4%    |
| Lenovo Thinkpad LAN                                                            | 1         | 0.4%    |
| Intel PRO/100 VE Network Connection                                            | 1         | 0.4%    |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.4%    |
| Intel Ethernet Connection I219-V                                               | 1         | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.4%    |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.4%    |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.4%    |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.4%    |
| Intel Ethernet Connection (10) I219-LM                                         | 1         | 0.4%    |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.4%    |
| Intel 82562GT 10/100 Network Connection                                        | 1         | 0.4%    |
| HP lt4120 Snapdragon X5 LTE                                                    | 1         | 0.4%    |
| Google Nexus/Pixel Device (tether)                                             | 1         | 0.4%    |
| DisplayLink Sabrent Docking                                                    | 1         | 0.4%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.4%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                              | 1         | 0.4%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 1         | 0.4%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 1         | 0.4%    |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 1         | 0.4%    |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe                        | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 286       | 54.68%  |
| Ethernet | 230       | 43.98%  |
| Modem    | 7         | 1.34%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 251       | 82.03%  |
| Ethernet | 55        | 17.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 214       | 74.05%  |
| 1     | 70        | 24.22%  |
| 0     | 4         | 1.38%   |
| 3     | 1         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 253       | 86.94%  |
| Yes  | 38        | 13.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 131       | 53.91%  |
| Qualcomm Atheros Communications | 25        | 10.29%  |
| Realtek Semiconductor           | 18        | 7.41%   |
| Broadcom                        | 12        | 4.94%   |
| Apple                           | 10        | 4.12%   |
| Lite-On Technology              | 9         | 3.7%    |
| Foxconn / Hon Hai               | 8         | 3.29%   |
| IMC Networks                    | 7         | 2.88%   |
| Hewlett-Packard                 | 5         | 2.06%   |
| Dell                            | 4         | 1.65%   |
| Realtek                         | 3         | 1.23%   |
| Ralink                          | 3         | 1.23%   |
| Toshiba                         | 2         | 0.82%   |
| Cambridge Silicon Radio         | 2         | 0.82%   |
| Unknown                         | 1         | 0.41%   |
| Integrated System Solution      | 1         | 0.41%   |
| Foxconn International           | 1         | 0.41%   |
| Belkin Components               | 1         | 0.41%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 49        | 20.16%  |
| Intel AX200 Bluetooth                                                               | 29        | 11.93%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 15        | 6.17%   |
| Intel AX201 Bluetooth                                                               | 15        | 6.17%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 14        | 5.76%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 13        | 5.35%   |
| Realtek Bluetooth Radio                                                             | 11        | 4.53%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 2.47%   |
| Apple Bluetooth Host Controller                                                     | 6         | 2.47%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 1.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 1.65%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 1.65%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.65%   |
| Realtek Bluetooth Radio                                                             | 3         | 1.23%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.23%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.23%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 1.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 1.23%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.82%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.82%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.82%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.82%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.82%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.82%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.82%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 0.82%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.82%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 0.82%   |
| Apple Bluetooth HCI                                                                 | 2         | 0.82%   |
| Unknown Bluetooth Device                                                            | 1         | 0.41%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.41%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.41%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.41%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.41%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.41%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.41%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.41%   |
| Intel Bluetooth Device                                                              | 1         | 0.41%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.41%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 0.41%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.41%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology                         | 1         | 0.41%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.41%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.41%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.41%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.41%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.41%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.41%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.41%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module                                            | 1         | 0.41%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.41%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.41%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.41%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.41%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.41%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                               | 1         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 247       | 68.8%   |
| AMD                       | 43        | 11.98%  |
| Nvidia                    | 41        | 11.42%  |
| Realtek Semiconductor     | 6         | 1.67%   |
| Logitech                  | 2         | 0.56%   |
| Kingston Technology       | 2         | 0.56%   |
| GN Netcom                 | 2         | 0.56%   |
| C-Media Electronics       | 2         | 0.56%   |
| XMOS                      | 1         | 0.28%   |
| Sennheiser Communications | 1         | 0.28%   |
| Samson Technologies       | 1         | 0.28%   |
| Razer USA                 | 1         | 0.28%   |
| Plantronics               | 1         | 0.28%   |
| No brand                  | 1         | 0.28%   |
| Lenovo                    | 1         | 0.28%   |
| JMTek                     | 1         | 0.28%   |
| Hewlett-Packard           | 1         | 0.28%   |
| Generalplus Technology    | 1         | 0.28%   |
| Conexant Systems          | 1         | 0.28%   |
| CMX Systems               | 1         | 0.28%   |
| Cambridge Audio           | 1         | 0.28%   |
| Apple                     | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 43        | 10.29%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 27        | 6.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 22        | 5.26%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 22        | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 4.78%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 15        | 3.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 2.87%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 2.87%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 2.87%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 2.87%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 2.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 2.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 2.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 2.15%   |
| Intel CM238 HD Audio Controller                                                                   | 9         | 2.15%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 2.15%   |
| AMD FCH Azalia Controller                                                                         | 8         | 1.91%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 1.67%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 1.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 1.67%   |
| Realtek Semiconductor USB Audio                                                                   | 6         | 1.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.44%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.44%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.2%    |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.2%    |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.2%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 0.96%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 0.96%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 0.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.72%   |
| Nvidia Audio device                                                                               | 3         | 0.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.72%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.72%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.48%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.48%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.48%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.48%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.48%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 0.48%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 0.48%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.48%   |
| XMOS BLUE USB Audio 2.0                                                                           | 1         | 0.24%   |
| Sennheiser Communications Sennheiser DECT                                                         | 1         | 0.24%   |
| Samson Technologies Q2U handheld mic with XLR                                                     | 1         | 0.24%   |
| Razer USA Kraken Tournament Edition                                                               | 1         | 0.24%   |
| Plantronics C320-M                                                                                | 1         | 0.24%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.24%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.24%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.24%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.24%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.24%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.24%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.24%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.24%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.24%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 68        | 34.34%  |
| SK Hynix            | 48        | 24.24%  |
| Micron Technology   | 22        | 11.11%  |
| Kingston            | 11        | 5.56%   |
| Ramaxel Technology  | 9         | 4.55%   |
| Unknown             | 8         | 4.04%   |
| Crucial             | 8         | 4.04%   |
| Unknown (ABCD)      | 3         | 1.52%   |
| Corsair             | 3         | 1.52%   |
| A-DATA Technology   | 3         | 1.52%   |
| Smart               | 2         | 1.01%   |
| Elpida              | 2         | 1.01%   |
| Unknown             | 2         | 1.01%   |
| Teikon              | 1         | 0.51%   |
| SMART Brazil        | 1         | 0.51%   |
| PNY                 | 1         | 0.51%   |
| Patriot             | 1         | 0.51%   |
| Nanya Technology    | 1         | 0.51%   |
| Kingmax             | 1         | 0.51%   |
| Goldkey             | 1         | 0.51%   |
| Cors                | 1         | 0.51%   |
| ASint Technology    | 1         | 0.51%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s         | 5         | 2.37%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s         | 5         | 2.37%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 1.9%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 4         | 1.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 4         | 1.9%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 4         | 1.9%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s      | 4         | 1.9%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s | 3         | 1.42%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s       | 3         | 1.42%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s         | 3         | 1.42%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s         | 3         | 1.42%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s   | 3         | 1.42%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 3         | 1.42%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s         | 3         | 1.42%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.95%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 2         | 0.95%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 2         | 0.95%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s         | 2         | 0.95%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 2         | 0.95%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s          | 2         | 0.95%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s       | 2         | 0.95%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.95%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 2         | 0.95%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s      | 2         | 0.95%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 0.95%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s          | 2         | 0.95%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 0.95%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s      | 2         | 0.95%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s       | 2         | 0.95%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s         | 2         | 0.95%   |
| Unknown                                                        | 2         | 0.95%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                    | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3                             | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                  | 1         | 0.47%   |
| Unknown RAM Module 4096MB SODIMM                               | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                    | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3                             | 1         | 0.47%   |
| Unknown RAM Module 2048MB SODIMM DDR3                          | 1         | 0.47%   |
| Unknown RAM Module 2048MB Row Of Chips LPDDR4 4267MT/s         | 1         | 0.47%   |
| Teikon RAM TMT451S6BFR8A-PBAJ 4096MB SODIMM DDR3 1600MT/s      | 1         | 0.47%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s          | 1         | 0.47%   |
| Smart RAM SH564128FJ8NWRNSQG 4096MB SODIMM DDR3 1600MT/s       | 1         | 0.47%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s          | 1         | 0.47%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s   | 1         | 0.47%   |
| SK Hynix RAM Module 8GB SODIMM DDR3 1600MT/s                   | 1         | 0.47%   |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s           | 1         | 0.47%   |
| SK Hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s              | 1         | 0.47%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                | 1         | 0.47%   |
| SK Hynix RAM Module 2048MB SODIMM DDR2 667MT/s                 | 1         | 0.47%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 533MT/s                    | 1         | 0.47%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2133MT/s               | 1         | 0.47%   |
| SK Hynix RAM HT5SMRAP 4GB SODIMM DDR3 1600MT/s                 | 1         | 0.47%   |
| SK Hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.47%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.47%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 0.47%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 0.47%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB Chip DDR3 1600MT/s           | 1         | 0.47%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 86        | 50.59%  |
| DDR3    | 57        | 33.53%  |
| LPDDR3  | 10        | 5.88%   |
| LPDDR4  | 9         | 5.29%   |
| SDRAM   | 3         | 1.76%   |
| DDR2    | 2         | 1.18%   |
| Unknown | 2         | 1.18%   |
| DDR     | 1         | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 146       | 87.95%  |
| Row Of Chips | 18        | 10.84%  |
| Chip         | 1         | 0.6%    |
| Unknown      | 1         | 0.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 67        | 36.22%  |
| 8192  | 62        | 33.51%  |
| 16384 | 29        | 15.68%  |
| 2048  | 15        | 8.11%   |
| 32768 | 9         | 4.86%   |
| 1024  | 3         | 1.62%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 55        | 28.95%  |
| 1600    | 41        | 21.58%  |
| 3200    | 20        | 10.53%  |
| 2133    | 17        | 8.95%   |
| 2400    | 14        | 7.37%   |
| 1333    | 9         | 4.74%   |
| 1334    | 8         | 4.21%   |
| 3266    | 4         | 2.11%   |
| 1067    | 4         | 2.11%   |
| 4267    | 3         | 1.58%   |
| 4199    | 3         | 1.58%   |
| 1867    | 3         | 1.58%   |
| Unknown | 3         | 1.58%   |
| 667     | 2         | 1.05%   |
| 4266    | 1         | 0.53%   |
| 3733    | 1         | 0.53%   |
| 1066    | 1         | 0.53%   |
| 533     | 1         | 0.53%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |
| Canon               | 1         | 25%     |
| Brother Industries  | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung M2020 Series   | 1         | 25%     |
| HP DeskJet 2130 series | 1         | 25%     |
| Canon LiDE 400         | 1         | 25%     |
| Brother MFC-1810       | 1         | 25%     |

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


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 73        | 28.08%  |
| IMC Networks                           | 25        | 9.62%   |
| Acer                                   | 25        | 9.62%   |
| Sunplus Innovation Technology          | 23        | 8.85%   |
| Realtek Semiconductor                  | 23        | 8.85%   |
| Microdia                               | 20        | 7.69%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 3.85%   |
| Apple                                  | 10        | 3.85%   |
| Syntek                                 | 9         | 3.46%   |
| Suyin                                  | 8         | 3.08%   |
| Quanta                                 | 7         | 2.69%   |
| Silicon Motion                         | 6         | 2.31%   |
| Ricoh                                  | 3         | 1.15%   |
| Lite-On Technology                     | 3         | 1.15%   |
| Luxvisions Innotech Limited            | 2         | 0.77%   |
| Alcor Micro                            | 2         | 0.77%   |
| Z-Star Microelectronics                | 1         | 0.38%   |
| USB Camera                             | 1         | 0.38%   |
| Sonix Technology                       | 1         | 0.38%   |
| Samsung Electronics                    | 1         | 0.38%   |
| Primax Electronics                     | 1         | 0.38%   |
| Logitech                               | 1         | 0.38%   |
| LG Electronics                         | 1         | 0.38%   |
| Importek                               | 1         | 0.38%   |
| Generalplus Technology                 | 1         | 0.38%   |
| Creative Technology                    | 1         | 0.38%   |
| Unknown                                | 1         | 0.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 Camera                                                      | 14        | 5.38%   |
| Chicony HD Webcam                                                          | 12        | 4.62%   |
| Chicony Integrated Camera                                                  | 11        | 4.23%   |
| Microdia Integrated_Webcam_HD                                              | 9         | 3.46%   |
| IMC Networks Integrated Camera                                             | 8         | 3.08%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 7         | 2.69%   |
| Realtek Integrated_Webcam_HD                                               | 6         | 2.31%   |
| Chicony HP HD Camera                                                       | 5         | 1.92%   |
| Acer HD Webcam                                                             | 5         | 1.92%   |
| Acer BisonCam,NB Pro                                                       | 5         | 1.92%   |
| Syntek Integrated Camera                                                   | 4         | 1.54%   |
| Sunplus HD WebCam                                                          | 4         | 1.54%   |
| IMC Networks VGA UVC WebCam                                                | 4         | 1.54%   |
| Apple FaceTime HD Camera                                                   | 4         | 1.54%   |
| Acer Integrated Camera                                                     | 4         | 1.54%   |
| Sunplus Asus Webcam                                                        | 3         | 1.15%   |
| Realtek USB2.0 HD UVC WebCam                                               | 3         | 1.15%   |
| Realtek Integrated Webcam                                                  | 3         | 1.15%   |
| IMC Networks ov9734_azurewave_camera                                       | 3         | 1.15%   |
| Chicony Integrated Camera [ThinkPad]                                       | 3         | 1.15%   |
| Chicony Integrated Camera (1280x720@30)                                    | 3         | 1.15%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 1.15%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 3         | 1.15%   |
| Acer BisonCam, NB Pro                                                      | 3         | 1.15%   |
| Syntek EasyCamera                                                          | 2         | 0.77%   |
| Suyin HP Truevision HD                                                     | 2         | 0.77%   |
| Sunplus Lenovo EasyCamera                                                  | 2         | 0.77%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 0.77%   |
| Sunplus HP HD Webcam [Fixed]                                               | 2         | 0.77%   |
| Sunplus HD User Facing                                                     | 2         | 0.77%   |
| Realtek Lenovo EasyCamera                                                  | 2         | 0.77%   |
| Realtek HP "Truevision HD" laptop camera                                   | 2         | 0.77%   |
| Realtek HD WebCam                                                          | 2         | 0.77%   |
| Microdia Sonix USB 2.0 Camera                                              | 2         | 0.77%   |
| Chicony thinkpad t430s camera                                              | 2         | 0.77%   |
| Chicony HP Integrated Webcam                                               | 2         | 0.77%   |
| Chicony HD WebCam (Asus N-series)                                          | 2         | 0.77%   |
| Chicony FJ Camera                                                          | 2         | 0.77%   |
| Chicony EasyCamera                                                         | 2         | 0.77%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 0.77%   |
| Apple Built-in iSight                                                      | 2         | 0.77%   |
| Acer SunplusIT Integrated Camera                                           | 2         | 0.77%   |
| Acer EasyCamera                                                            | 2         | 0.77%   |
| Z-Star Lenovo EasyCamera                                                   | 1         | 0.38%   |
| USB Camera USB Camera                                                      | 1         | 0.38%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                                       | 1         | 0.38%   |
| Syntek USB2.0 Camera                                                       | 1         | 0.38%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.38%   |
| Suyin USB 2.0 Camera                                                       | 1         | 0.38%   |
| Suyin Sony Visual Communication Camera                                     | 1         | 0.38%   |
| Suyin HP Webcam 101                                                        | 1         | 0.38%   |
| Suyin HD WebCam                                                            | 1         | 0.38%   |
| Suyin HD Video WebCam                                                      | 1         | 0.38%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)                | 1         | 0.38%   |
| Sunplus USB Camera                                                         | 1         | 0.38%   |
| Sunplus MTD Camera                                                         | 1         | 0.38%   |
| Sunplus Laptop_Integrated_Webcam_HD                                        | 1         | 0.38%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 1         | 0.38%   |
| Sunplus Laptop Integrated WebCam HD                                        | 1         | 0.38%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 0.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 25        | 37.88%  |
| Validity Sensors           | 21        | 31.82%  |
| Shenzhen Goodix Technology | 9         | 13.64%  |
| LighTuning Technology      | 6         | 9.09%   |
| Elan Microelectronics      | 3         | 4.55%   |
| AuthenTec                  | 2         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 12.12%  |
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 12.12%  |
| Unknown                                                                    | 7         | 10.61%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 9.09%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 6.06%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 6.06%   |
| Synaptics WBDI Device                                                      | 4         | 6.06%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 4.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 4.55%   |
| Elan ELAN:Fingerprint                                                      | 3         | 4.55%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 3.03%   |
| Validity Sensors VFS491                                                    | 2         | 3.03%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 3.03%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 3.03%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 3.03%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.52%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.52%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.52%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.52%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.52%   |
| AuthenTec AES1600                                                          | 1         | 1.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 45%     |
| Upek        | 5         | 25%     |
| Alcor Micro | 4         | 20%     |
| Lenovo      | 2         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 15%     |
| Broadcom 5880                                                                | 3         | 15%     |
| Lenovo Integrated Smart Card Reader                                          | 2         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 10%     |
| Broadcom 58200                                                               | 1         | 5%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 164       | 56.55%  |
| 1     | 102       | 35.17%  |
| 2     | 21        | 7.24%   |
| 3     | 2         | 0.69%   |
| 4     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 65        | 44.22%  |
| Graphics card            | 22        | 14.97%  |
| Chipcard                 | 19        | 12.93%  |
| Communication controller | 12        | 8.16%   |
| Net/wireless             | 11        | 7.48%   |
| Multimedia controller    | 4         | 2.72%   |
| Camera                   | 4         | 2.72%   |
| Storage                  | 3         | 2.04%   |
| Card reader              | 3         | 2.04%   |
| Bluetooth                | 3         | 2.04%   |
| Net/ethernet             | 1         | 0.68%   |

