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

Total: 448

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6410              | [98545a1050](https://linux-hardware.org/?probe=98545a1050) | Sep 30, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [15d9ea100b](https://linux-hardware.org/?probe=15d9ea100b) | Sep 26, 2022 |
| TUXEDO        | Book BA1510                 | [76a485fe7e](https://linux-hardware.org/?probe=76a485fe7e) | Sep 22, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Lenovo        | G50-45 80E3                 | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Lenovo        | G500 20236                  | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| TUXEDO        | InfinityBook Pro 14 v4      | [cc583599ef](https://linux-hardware.org/?probe=cc583599ef) | Aug 28, 2022 |
| Google        | Rabbid                      | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
| Lenovo        | G500 20236                  | [81ba48faa1](https://linux-hardware.org/?probe=81ba48faa1) | Aug 20, 2022 |
| Lenovo        | G500 20236                  | [45df8f9be9](https://linux-hardware.org/?probe=45df8f9be9) | Aug 18, 2022 |
| Lenovo        | G500 20236                  | [6974cf32ce](https://linux-hardware.org/?probe=6974cf32ce) | Aug 17, 2022 |
| Acer          | TravelMate P653-M           | [1e33abf031](https://linux-hardware.org/?probe=1e33abf031) | Aug 17, 2022 |
| TUXEDO        | Book XUX7 Gen11             | [ecf8be45de](https://linux-hardware.org/?probe=ecf8be45de) | Aug 16, 2022 |
| TUXEDO        | Book XUX7 Gen11             | [c5c7e42e91](https://linux-hardware.org/?probe=c5c7e42e91) | Aug 16, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [5d50a29ca9](https://linux-hardware.org/?probe=5d50a29ca9) | Aug 13, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [8c6f00600e](https://linux-hardware.org/?probe=8c6f00600e) | Aug 12, 2022 |
| Dell          | Inspiron 3793               | [15f2e25089](https://linux-hardware.org/?probe=15f2e25089) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [e82d2e1076](https://linux-hardware.org/?probe=e82d2e1076) | Jul 28, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [2a95697c62](https://linux-hardware.org/?probe=2a95697c62) | Jul 25, 2022 |
| Alienware     | M11xR3                      | [e479dcdefb](https://linux-hardware.org/?probe=e479dcdefb) | Jul 22, 2022 |
| HP            | EliteBook 840 G3            | [e34f81fcfa](https://linux-hardware.org/?probe=e34f81fcfa) | Jul 18, 2022 |
| MSI           | GE75 Raider 10SE            | [d2ed25b6e8](https://linux-hardware.org/?probe=d2ed25b6e8) | Jul 16, 2022 |
| TUXEDO        | InfinityBook_Pro13_14_v4    | [f1dcf09169](https://linux-hardware.org/?probe=f1dcf09169) | Jul 14, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | [47bddb4e10](https://linux-hardware.org/?probe=47bddb4e10) | Jul 10, 2022 |
| HP            | ENVY 17                     | [2d97952e56](https://linux-hardware.org/?probe=2d97952e56) | Jul 08, 2022 |
| Dell          | Latitude E7450              | [34913911ca](https://linux-hardware.org/?probe=34913911ca) | Jul 05, 2022 |
| Dell          | Latitude E7450              | [60e633e563](https://linux-hardware.org/?probe=60e633e563) | Jul 04, 2022 |
| Positivo      | Q232A                       | [c297e38afb](https://linux-hardware.org/?probe=c297e38afb) | Jun 27, 2022 |
| Positivo      | Q232A                       | [8774fcf3a2](https://linux-hardware.org/?probe=8774fcf3a2) | Jun 27, 2022 |
| Acer          | Aspire E5-573G              | [9f14a273b0](https://linux-hardware.org/?probe=9f14a273b0) | Jun 26, 2022 |
| Lenovo        | ThinkPad T400 6475AT3       | [55fd247328](https://linux-hardware.org/?probe=55fd247328) | Jun 26, 2022 |
| HP            | ElitePad 1000 G2            | [e478f31175](https://linux-hardware.org/?probe=e478f31175) | Jun 25, 2022 |
| MSI           | GL62 6QF                    | [39e2d35166](https://linux-hardware.org/?probe=39e2d35166) | Jun 20, 2022 |
| Timi          | TM1604                      | [2f45cc25b4](https://linux-hardware.org/?probe=2f45cc25b4) | Jun 20, 2022 |
| HP            | Pavilion dv7                | [add98928e5](https://linux-hardware.org/?probe=add98928e5) | Jun 18, 2022 |
| HP            | Pavilion dv7                | [bfecf091a6](https://linux-hardware.org/?probe=bfecf091a6) | Jun 18, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [d4ad64d715](https://linux-hardware.org/?probe=d4ad64d715) | Jun 15, 2022 |
| ASUSTek       | X555LAB                     | [8e47a3c188](https://linux-hardware.org/?probe=8e47a3c188) | Jun 10, 2022 |
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
| Ubuntu Budgie 20.04 | 165       | 51.08%  |
| Ubuntu Budgie 20.10 | 34        | 10.53%  |
| Ubuntu Budgie 22.04 | 33        | 10.22%  |
| Ubuntu Budgie 21.10 | 32        | 9.91%   |
| Ubuntu Budgie 18.04 | 23        | 7.12%   |
| Ubuntu Budgie 21.04 | 20        | 6.19%   |
| Ubuntu Budgie 19.10 | 13        | 4.02%   |
| Ubuntu Budgie 16.04 | 2         | 0.62%   |
| Ubuntu Budgie       | 1         | 0.31%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Budgie | 317       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 18        | 5.17%   |
| 5.3.0-40-generic  | 10        | 2.87%   |
| 5.13.0-22-generic | 10        | 2.87%   |
| 5.4.0-40-generic  | 9         | 2.59%   |
| 5.8.0-41-generic  | 7         | 2.01%   |
| 5.15.0-27-generic | 7         | 2.01%   |
| 5.13.0-28-generic | 7         | 2.01%   |
| 5.4.0-37-generic  | 6         | 1.72%   |
| 5.4.0-29-generic  | 6         | 1.72%   |
| 5.13.0-39-generic | 6         | 1.72%   |
| 5.8.0-53-generic  | 5         | 1.44%   |
| 5.8.0-48-generic  | 5         | 1.44%   |
| 5.4.0-52-generic  | 5         | 1.44%   |
| 5.4.0-48-generic  | 5         | 1.44%   |
| 5.4.0-33-generic  | 5         | 1.44%   |
| 5.13.0-40-generic | 5         | 1.44%   |
| 5.13.0-35-generic | 5         | 1.44%   |
| 5.13.0-30-generic | 5         | 1.44%   |
| 5.13.0-19-generic | 5         | 1.44%   |
| 5.8.0-44-generic  | 4         | 1.15%   |
| 5.8.0-33-generic  | 4         | 1.15%   |
| 5.8.0-29-generic  | 4         | 1.15%   |
| 5.4.0-58-generic  | 4         | 1.15%   |
| 5.4.0-31-generic  | 4         | 1.15%   |
| 5.15.0-46-generic | 4         | 1.15%   |
| 5.11.0-41-generic | 4         | 1.15%   |
| 5.11.0-34-generic | 4         | 1.15%   |
| 5.11.0-16-generic | 4         | 1.15%   |
| 5.8.0-45-generic  | 3         | 0.86%   |
| 5.4.0-91-generic  | 3         | 0.86%   |
| 5.4.0-73-generic  | 3         | 0.86%   |
| 5.4.0-28-generic  | 3         | 0.86%   |
| 5.15.0-40-generic | 3         | 0.86%   |
| 5.15.0-39-generic | 3         | 0.86%   |
| 5.15.0-30-generic | 3         | 0.86%   |
| 5.11.0-31-generic | 3         | 0.86%   |
| 5.11.0-27-generic | 3         | 0.86%   |
| 5.11.0-25-generic | 3         | 0.86%   |
| 5.8.0-63-generic  | 2         | 0.57%   |
| 5.8.0-59-generic  | 2         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 102       | 31.19%  |
| 5.8.0   | 54        | 16.51%  |
| 5.13.0  | 53        | 16.21%  |
| 5.15.0  | 36        | 11.01%  |
| 5.11.0  | 32        | 9.79%   |
| 5.3.0   | 21        | 6.42%   |
| 4.15.0  | 10        | 3.06%   |
| 5.6.0   | 3         | 0.92%   |
| 5.12.0  | 2         | 0.61%   |
| 5.0.0   | 2         | 0.61%   |
| 4.18.0  | 2         | 0.61%   |
| 5.9.0   | 1         | 0.31%   |
| 5.8.11  | 1         | 0.31%   |
| 5.6.7   | 1         | 0.31%   |
| 5.5.0   | 1         | 0.31%   |
| 5.19.0  | 1         | 0.31%   |
| 5.16.14 | 1         | 0.31%   |
| 5.15.11 | 1         | 0.31%   |
| 5.10.11 | 1         | 0.31%   |
| 5.10.0  | 1         | 0.31%   |
| 4.4.0   | 1         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 102       | 31.19%  |
| 5.8     | 55        | 16.82%  |
| 5.13    | 53        | 16.21%  |
| 5.15    | 37        | 11.31%  |
| 5.11    | 32        | 9.79%   |
| 5.3     | 21        | 6.42%   |
| 4.15    | 10        | 3.06%   |
| 5.6     | 4         | 1.22%   |
| 5.12    | 2         | 0.61%   |
| 5.10    | 2         | 0.61%   |
| 5.0     | 2         | 0.61%   |
| 4.18    | 2         | 0.61%   |
| 5.9     | 1         | 0.31%   |
| 5.5     | 1         | 0.31%   |
| 5.19    | 1         | 0.31%   |
| 5.16    | 1         | 0.31%   |
| 4.4     | 1         | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 314       | 99.05%  |
| i686   | 3         | 0.95%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Budgie | 311       | 98.11%  |
| GNOME  | 5         | 1.58%   |
| XFCE   | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 306       | 96.53%  |
| Wayland | 11        | 3.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 126       | 39.38%  |
| LightDM | 97        | 30.31%  |
| TDM     | 58        | 18.13%  |
| GDM     | 25        | 7.81%   |
| GDM3    | 13        | 4.06%   |
| SDDM    | 1         | 0.31%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 104       | 32.7%   |
| de_DE   | 47        | 14.78%  |
| pt_BR   | 22        | 6.92%   |
| fr_FR   | 21        | 6.6%    |
| en_GB   | 19        | 5.97%   |
| en_CA   | 13        | 4.09%   |
| ru_RU   | 9         | 2.83%   |
| en_IN   | 9         | 2.83%   |
| it_IT   | 8         | 2.52%   |
| es_AR   | 7         | 2.2%    |
| es_MX   | 6         | 1.89%   |
| C       | 6         | 1.89%   |
| es_ES   | 5         | 1.57%   |
| hu_HU   | 3         | 0.94%   |
| es_CL   | 3         | 0.94%   |
| en_AU   | 3         | 0.94%   |
| de_AT   | 3         | 0.94%   |
| Unknown | 3         | 0.94%   |
| pt_PT   | 2         | 0.63%   |
| pl_PL   | 2         | 0.63%   |
| fi_FI   | 2         | 0.63%   |
| en_IE   | 2         | 0.63%   |
| de_CH   | 2         | 0.63%   |
| zh_TW   | 1         | 0.31%   |
| zh_CN   | 1         | 0.31%   |
| uk_UA   | 1         | 0.31%   |
| tr_TR   | 1         | 0.31%   |
| nl_NL   | 1         | 0.31%   |
| nl_BE   | 1         | 0.31%   |
| nb_NO   | 1         | 0.31%   |
| lv_LV   | 1         | 0.31%   |
| id_ID   | 1         | 0.31%   |
| fr_CH   | 1         | 0.31%   |
| fr_BE   | 1         | 0.31%   |
| es_US   | 1         | 0.31%   |
| es_SV   | 1         | 0.31%   |
| es_GT   | 1         | 0.31%   |
| es_EC   | 1         | 0.31%   |
| en_ZA   | 1         | 0.31%   |
| en_SG   | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 197       | 60.99%  |
| BIOS | 126       | 39.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 297       | 93.4%   |
| Zfs     | 8         | 2.52%   |
| Overlay | 6         | 1.89%   |
| Xfs     | 3         | 0.94%   |
| Btrfs   | 3         | 0.94%   |
| Jfs     | 1         | 0.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 168       | 52.83%  |
| GPT     | 125       | 39.31%  |
| MBR     | 25        | 7.86%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 284       | 88.75%  |
| Yes       | 36        | 11.25%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 221       | 69.28%  |
| Yes       | 98        | 30.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 62        | 19.56%  |
| Hewlett-Packard        | 50        | 15.77%  |
| Dell                   | 40        | 12.62%  |
| TUXEDO                 | 38        | 11.99%  |
| ASUSTek Computer       | 33        | 10.41%  |
| Acer                   | 21        | 6.62%   |
| MSI                    | 12        | 3.79%   |
| Apple                  | 11        | 3.47%   |
| Sony                   | 5         | 1.58%   |
| Samsung Electronics    | 5         | 1.58%   |
| HUAWEI                 | 5         | 1.58%   |
| Google                 | 4         | 1.26%   |
| Toshiba                | 3         | 0.95%   |
| Packard Bell           | 3         | 0.95%   |
| Fujitsu                | 3         | 0.95%   |
| Unknown                | 3         | 0.95%   |
| Timi                   | 2         | 0.63%   |
| Standard               | 2         | 0.63%   |
| Positivo               | 2         | 0.63%   |
| Alienware              | 2         | 0.63%   |
| Viglen                 | 1         | 0.32%   |
| Razer                  | 1         | 0.32%   |
| Quanta                 | 1         | 0.32%   |
| PC Specialist          | 1         | 0.32%   |
| GPU Company            | 1         | 0.32%   |
| Gigabyte Technology    | 1         | 0.32%   |
| EVOO                   | 1         | 0.32%   |
| Chuwi                  | 1         | 0.32%   |
| BANGHO                 | 1         | 0.32%   |
| AWOW                   | 1         | 0.32%   |
| Avell High Performance | 1         | 0.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 13        | 4.1%    |
| HP Pavilion g6                         | 3         | 0.95%   |
| TUXEDO Pulse 15 Gen1                   | 2         | 0.63%   |
| TUXEDO Polaris 15 AMD Gen1             | 2         | 0.63%   |
| TUXEDO InfinityBook S 15 Gen6          | 2         | 0.63%   |
| TUXEDO InfinityBook S 14 Gen6          | 2         | 0.63%   |
| TUXEDO InfinityBook Pro 14 Gen6        | 2         | 0.63%   |
| TUXEDO Aura 15 Gen1                    | 2         | 0.63%   |
| Standard MT40II                        | 2         | 0.63%   |
| Lenovo ThinkBook 14-IML 20RV           | 2         | 0.63%   |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 2         | 0.63%   |
| Lenovo IdeaPad 330S-15ARR 81FB         | 2         | 0.63%   |
| Lenovo IdeaPad 320-15IKB 80XL          | 2         | 0.63%   |
| Lenovo G500 20236                      | 2         | 0.63%   |
| Lenovo G50-45 80E3                     | 2         | 0.63%   |
| HP ZBook Studio G3                     | 2         | 0.63%   |
| HP Notebook                            | 2         | 0.63%   |
| HP ENVY 17                             | 2         | 0.63%   |
| HP ENVY 15                             | 2         | 0.63%   |
| HP 2000                                | 2         | 0.63%   |
| Dell XPS 13 9380                       | 2         | 0.63%   |
| Dell Latitude E6540                    | 2         | 0.63%   |
| Dell Latitude E6410                    | 2         | 0.63%   |
| Dell Latitude 5400                     | 2         | 0.63%   |
| Dell Inspiron 5570                     | 2         | 0.63%   |
| ASUS VivoBook_ASUSLaptop X571GT_F571GT | 2         | 0.63%   |
| Apple MacBookPro8,1                    | 2         | 0.63%   |
| Acer TravelMate P446-M                 | 2         | 0.63%   |
| Viglen VUB1                            | 1         | 0.32%   |
| TUXEDO Stellaris Intel Gen3 (TGL)      | 1         | 0.32%   |
| TUXEDO Stellaris AMD Gen3 (CZN)        | 1         | 0.32%   |
| TUXEDO Polaris AMD Gen3 (CZN)          | 1         | 0.32%   |
| TUXEDO Polaris 17 AMD Gen1             | 1         | 0.32%   |
| TUXEDO P95_HR                          | 1         | 0.32%   |
| TUXEDO P95_HP                          | 1         | 0.32%   |
| TUXEDO P7xxTM1                         | 1         | 0.32%   |
| TUXEDO InfinityBook_Pro13_14_v4        | 1         | 0.32%   |
| TUXEDO InfinityBook S 14 v5            | 1         | 0.32%   |
| TUXEDO InfinityBook Pro 15 v4          | 1         | 0.32%   |
| TUXEDO InfinityBook Pro 14 v4          | 1         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 30        | 9.46%   |
| Dell Latitude         | 17        | 5.36%   |
| Lenovo IdeaPad        | 14        | 4.42%   |
| Acer Aspire           | 13        | 4.1%    |
| Unknown               | 13        | 4.1%    |
| HP Pavilion           | 12        | 3.79%   |
| Dell Inspiron         | 12        | 3.79%   |
| TUXEDO InfinityBook   | 10        | 3.15%   |
| HP EliteBook          | 9         | 2.84%   |
| Dell XPS              | 7         | 2.21%   |
| ASUS VivoBook         | 7         | 2.21%   |
| HP ENVY               | 6         | 1.89%   |
| TUXEDO Book           | 5         | 1.58%   |
| TUXEDO Polaris        | 4         | 1.26%   |
| Lenovo ThinkBook      | 4         | 1.26%   |
| HP ZBook              | 4         | 1.26%   |
| HP ProBook            | 4         | 1.26%   |
| HP Laptop             | 4         | 1.26%   |
| Acer Swift            | 4         | 1.26%   |
| Toshiba Satellite     | 3         | 0.95%   |
| HP Compaq             | 3         | 0.95%   |
| Fujitsu LIFEBOOK      | 3         | 0.95%   |
| Apple MacBookPro8     | 3         | 0.95%   |
| Acer TravelMate       | 3         | 0.95%   |
| TUXEDO Stellaris      | 2         | 0.63%   |
| TUXEDO Pulse          | 2         | 0.63%   |
| TUXEDO P95            | 2         | 0.63%   |
| TUXEDO Aura           | 2         | 0.63%   |
| Standard MT40II       | 2         | 0.63%   |
| Packard Bell EasyNote | 2         | 0.63%   |
| MSI Prestige          | 2         | 0.63%   |
| MSI Modern            | 2         | 0.63%   |
| Lenovo Yoga           | 2         | 0.63%   |
| Lenovo G500           | 2         | 0.63%   |
| Lenovo G50-45         | 2         | 0.63%   |
| HP Notebook           | 2         | 0.63%   |
| HP 2000               | 2         | 0.63%   |
| Dell Vostro           | 2         | 0.63%   |
| ASUS ZenBook          | 2         | 0.63%   |
| Apple MacBookPro11    | 2         | 0.63%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 49        | 15.46%  |
| 2018 | 39        | 12.3%   |
| 2020 | 36        | 11.36%  |
| 2012 | 23        | 7.26%   |
| 2011 | 23        | 7.26%   |
| 2017 | 22        | 6.94%   |
| 2014 | 20        | 6.31%   |
| 2021 | 18        | 5.68%   |
| 2013 | 18        | 5.68%   |
| 2015 | 17        | 5.36%   |
| 2016 | 16        | 5.05%   |
| 2010 | 12        | 3.79%   |
| 2008 | 10        | 3.15%   |
| 2009 | 6         | 1.89%   |
| 2007 | 6         | 1.89%   |
| 2022 | 2         | 0.63%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 317       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 284       | 89.31%  |
| Enabled  | 34        | 10.69%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 313       | 98.74%  |
| Yes  | 4         | 1.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 94        | 29.47%  |
| 16.01-24.0  | 65        | 20.38%  |
| 3.01-4.0    | 54        | 16.93%  |
| 8.01-16.0   | 52        | 16.3%   |
| 32.01-64.0  | 30        | 9.4%    |
| 64.01-256.0 | 10        | 3.13%   |
| 1.01-2.0    | 8         | 2.51%   |
| 24.01-32.0  | 4         | 1.25%   |
| 2.01-3.0    | 2         | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 102       | 30.36%  |
| 1.01-2.0   | 94        | 27.98%  |
| 4.01-8.0   | 65        | 19.35%  |
| 3.01-4.0   | 55        | 16.37%  |
| 8.01-16.0  | 14        | 4.17%   |
| 0.51-1.0   | 3         | 0.89%   |
| 16.01-24.0 | 2         | 0.6%    |
| 24.01-32.0 | 1         | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 229       | 71.79%  |
| 2      | 80        | 25.08%  |
| 3      | 9         | 2.82%   |
| 0      | 1         | 0.31%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 223       | 70.13%  |
| Yes       | 95        | 29.87%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 254       | 79.87%  |
| No        | 64        | 20.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 314       | 99.05%  |
| No        | 3         | 0.95%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 266       | 83.65%  |
| No        | 52        | 16.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 54        | 17.03%  |
| USA                | 42        | 13.25%  |
| Brazil             | 25        | 7.89%   |
| France             | 19        | 5.99%   |
| UK                 | 11        | 3.47%   |
| Russia             | 11        | 3.47%   |
| Italy              | 11        | 3.47%   |
| India              | 11        | 3.47%   |
| Canada             | 11        | 3.47%   |
| Argentina          | 9         | 2.84%   |
| Mexico             | 8         | 2.52%   |
| Netherlands        | 7         | 2.21%   |
| Spain              | 6         | 1.89%   |
| Poland             | 6         | 1.89%   |
| Austria            | 5         | 1.58%   |
| Ukraine            | 4         | 1.26%   |
| Switzerland        | 4         | 1.26%   |
| Hungary            | 4         | 1.26%   |
| Greece             | 4         | 1.26%   |
| Finland            | 4         | 1.26%   |
| Turkey             | 3         | 0.95%   |
| South Africa       | 3         | 0.95%   |
| Portugal           | 3         | 0.95%   |
| Norway             | 3         | 0.95%   |
| Iran               | 3         | 0.95%   |
| Dominican Republic | 3         | 0.95%   |
| Chile              | 3         | 0.95%   |
| Belgium            | 3         | 0.95%   |
| Australia          | 3         | 0.95%   |
| Sweden             | 2         | 0.63%   |
| Slovenia           | 2         | 0.63%   |
| Malaysia           | 2         | 0.63%   |
| Japan              | 2         | 0.63%   |
| Ireland            | 2         | 0.63%   |
| Indonesia          | 2         | 0.63%   |
| Ecuador            | 2         | 0.63%   |
| Colombia           | 2         | 0.63%   |
| Taiwan             | 1         | 0.32%   |
| Singapore          | 1         | 0.32%   |
| Serbia             | 1         | 0.32%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 6         | 1.86%   |
| Berlin             | 6         | 1.86%   |
| Moscow             | 5         | 1.55%   |
| Ravensburg         | 4         | 1.24%   |
| Budapest           | 4         | 1.24%   |
| Athens             | 4         | 1.24%   |
| Tehran             | 3         | 0.93%   |
| Santo Domingo Este | 3         | 0.93%   |
| Montreal           | 3         | 0.93%   |
| Hamburg            | 3         | 0.93%   |
| Brasília          | 3         | 0.93%   |
| Austin             | 3         | 0.93%   |
| Wolfsburg          | 2         | 0.62%   |
| Vienna             | 2         | 0.62%   |
| Vancouver          | 2         | 0.62%   |
| Stuttgart          | 2         | 0.62%   |
| St Petersburg      | 2         | 0.62%   |
| San Miguel         | 2         | 0.62%   |
| San Francisco      | 2         | 0.62%   |
| Pune               | 2         | 0.62%   |
| Portland           | 2         | 0.62%   |
| Paris              | 2         | 0.62%   |
| Nuremberg          | 2         | 0.62%   |
| Niterói           | 2         | 0.62%   |
| Munich             | 2         | 0.62%   |
| Mumbai             | 2         | 0.62%   |
| Milan              | 2         | 0.62%   |
| Lisbon             | 2         | 0.62%   |
| Kyiv               | 2         | 0.62%   |
| Kassel             | 2         | 0.62%   |
| Istanbul           | 2         | 0.62%   |
| Gurgaon            | 2         | 0.62%   |
| Dublin             | 2         | 0.62%   |
| Cologne            | 2         | 0.62%   |
| Burzaco            | 2         | 0.62%   |
| Belo Horizonte     | 2         | 0.62%   |
| Bamberg            | 2         | 0.62%   |
| Zurich             | 1         | 0.31%   |
| Zambrów           | 1         | 0.31%   |
| Zagreb             | 1         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 88        | 112    | 22.06%  |
| WDC                       | 43        | 46     | 10.78%  |
| Seagate                   | 42        | 45     | 10.53%  |
| Toshiba                   | 33        | 38     | 8.27%   |
| Unknown                   | 27        | 30     | 6.77%   |
| SanDisk                   | 24        | 27     | 6.02%   |
| Kingston                  | 15        | 15     | 3.76%   |
| SK hynix                  | 14        | 16     | 3.51%   |
| Intel                     | 14        | 18     | 3.51%   |
| Crucial                   | 14        | 16     | 3.51%   |
| Micron Technology         | 8         | 9      | 2.01%   |
| HGST                      | 8         | 11     | 2.01%   |
| A-DATA Technology         | 8         | 9      | 2.01%   |
| Hitachi                   | 7         | 7      | 1.75%   |
| China                     | 6         | 7      | 1.5%    |
| SPCC                      | 5         | 5      | 1.25%   |
| Apple                     | 5         | 5      | 1.25%   |
| PNY                       | 4         | 6      | 1%      |
| JMicron Technology        | 3         | 3      | 0.75%   |
| LITEON                    | 2         | 2      | 0.5%    |
| Lenovo                    | 2         | 2      | 0.5%    |
| Intenso                   | 2         | 3      | 0.5%    |
| Hewlett-Packard           | 2         | 1      | 0.5%    |
| Corsair                   | 2         | 3      | 0.5%    |
| Unknown                   | 2         | 2      | 0.5%    |
| Vaseky                    | 1         | 1      | 0.25%   |
| USB30                     | 1         | 1      | 0.25%   |
| Union Memory              | 1         | 1      | 0.25%   |
| TO Exter                  | 1         | 1      | 0.25%   |
| Realtek Semiconductor     | 1         | 2      | 0.25%   |
| Patriot                   | 1         | 1      | 0.25%   |
| OWC                       | 1         | 1      | 0.25%   |
| Netac                     | 1         | 1      | 0.25%   |
| Micron/Crucial Technology | 1         | 1      | 0.25%   |
| LITEONIT                  | 1         | 1      | 0.25%   |
| LaCie                     | 1         | 1      | 0.25%   |
| KIOXIA                    | 1         | 1      | 0.25%   |
| KingSpec                  | 1         | 1      | 0.25%   |
| KimMiDi                   | 1         | 1      | 0.25%   |
| Gigabyte Technology       | 1         | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB               | 6         | 1.46%   |
| WDC WD10JPVX-22JC3T0 1TB             | 5         | 1.22%   |
| Unknown MMC Card  64GB               | 5         | 1.22%   |
| Unknown MMC Card  32GB               | 5         | 1.22%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 1.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 1.22%   |
| Samsung SSD 860 EVO M.2 500GB        | 5         | 1.22%   |
| Samsung SSD 860 EVO M.2 250GB        | 5         | 1.22%   |
| Samsung NVMe SSD Drive 1TB           | 5         | 1.22%   |
| Toshiba MQ04ABF100 1TB               | 4         | 0.97%   |
| SK hynix NVMe SSD Drive 256GB        | 4         | 0.97%   |
| Seagate ST9500325AS 500GB            | 4         | 0.97%   |
| SanDisk NVMe SSD Drive 512GB         | 4         | 0.97%   |
| Samsung SSD 970 EVO Plus 1TB         | 4         | 0.97%   |
| Samsung NVMe SSD Drive 512GB         | 4         | 0.97%   |
| Samsung NVMe SSD Drive 500GB         | 4         | 0.97%   |
| Unknown SD64G  64GB                  | 3         | 0.73%   |
| SPCC Solid State Disk 120GB          | 3         | 0.73%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.73%   |
| Seagate ST1000LX015-1U7172 1TB       | 3         | 0.73%   |
| Samsung SSD 970 EVO Plus 500GB       | 3         | 0.73%   |
| Samsung SSD 970 EVO 500GB            | 3         | 0.73%   |
| Samsung SSD 860 EVO 500GB            | 3         | 0.73%   |
| Samsung SSD 750 EVO 250GB            | 3         | 0.73%   |
| Samsung NVMe SSD Drive 2TB           | 3         | 0.73%   |
| Samsung NVMe SSD Drive 250GB         | 3         | 0.73%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.49%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 2         | 0.49%   |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 0.49%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 0.49%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB | 2         | 0.49%   |
| Unknown SD/MMC/MS PRO 2GB            | 2         | 0.49%   |
| Unknown MMC128  128GB                | 2         | 0.49%   |
| Unknown MMC Card  16GB               | 2         | 0.49%   |
| Toshiba MQ01ACF050 500GB             | 2         | 0.49%   |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 0.49%   |
| Seagate Expansion Desk 2TB           | 2         | 0.49%   |
| Seagate BUP Slim BK 500GB            | 2         | 0.49%   |
| SanDisk X400 M.2 2280 512GB SSD      | 2         | 0.49%   |
| SanDisk SSD PLUS 480GB               | 2         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 42     | 37.14%  |
| WDC                 | 24        | 26     | 22.86%  |
| Toshiba             | 23        | 26     | 21.9%   |
| HGST                | 8         | 11     | 7.62%   |
| Hitachi             | 7         | 7      | 6.67%   |
| Unknown             | 2         | 2      | 1.9%    |
| Samsung Electronics | 1         | 1      | 0.95%   |
| Fujitsu             | 1         | 1      | 0.95%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 43        | 53     | 28.86%  |
| SanDisk             | 16        | 16     | 10.74%  |
| Crucial             | 13        | 15     | 8.72%   |
| Kingston            | 12        | 12     | 8.05%   |
| WDC                 | 7         | 7      | 4.7%    |
| China               | 6         | 7      | 4.03%   |
| A-DATA Technology   | 6         | 7      | 4.03%   |
| SPCC                | 5         | 5      | 3.36%   |
| Micron Technology   | 5         | 6      | 3.36%   |
| PNY                 | 4         | 6      | 2.68%   |
| Intel               | 4         | 4      | 2.68%   |
| Apple               | 4         | 4      | 2.68%   |
| Toshiba             | 2         | 2      | 1.34%   |
| Seagate             | 2         | 2      | 1.34%   |
| LITEON              | 2         | 2      | 1.34%   |
| Intenso             | 2         | 3      | 1.34%   |
| Vaseky              | 1         | 1      | 0.67%   |
| USB30               | 1         | 1      | 0.67%   |
| Unknown             | 1         | 1      | 0.67%   |
| Union Memory        | 1         | 1      | 0.67%   |
| TO Exter            | 1         | 1      | 0.67%   |
| SK hynix            | 1         | 1      | 0.67%   |
| Patriot             | 1         | 1      | 0.67%   |
| OWC                 | 1         | 1      | 0.67%   |
| Netac               | 1         | 1      | 0.67%   |
| LITEONIT            | 1         | 1      | 0.67%   |
| KingSpec            | 1         | 1      | 0.67%   |
| Hewlett-Packard     | 1         | 1      | 0.67%   |
| Gigabyte Technology | 1         | 1      | 0.67%   |
| Dogfish             | 1         | 1      | 0.67%   |
| Corsair             | 1         | 2      | 0.67%   |
| BIWIN               | 1         | 1      | 0.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 136       | 168    | 35.79%  |
| NVMe    | 110       | 138    | 28.95%  |
| HDD     | 102       | 116    | 26.84%  |
| MMC     | 26        | 31     | 6.84%   |
| Unknown | 6         | 5      | 1.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 206       | 275    | 57.7%   |
| NVMe | 109       | 136    | 30.53%  |
| MMC  | 26        | 31     | 7.28%   |
| SAS  | 16        | 16     | 4.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 155       | 187    | 65.13%  |
| 0.51-1.0   | 73        | 85     | 30.67%  |
| 1.01-2.0   | 10        | 12     | 4.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 100       | 31.15%  |
| 101-250        | 96        | 29.91%  |
| 501-1000       | 43        | 13.4%   |
| 51-100         | 29        | 9.03%   |
| 1001-2000      | 17        | 5.3%    |
| 21-50          | 16        | 4.98%   |
| 1-20           | 7         | 2.18%   |
| 2001-3000      | 6         | 1.87%   |
| More than 3000 | 4         | 1.25%   |
| Unknown        | 3         | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 105       | 32.11%  |
| 101-250        | 63        | 19.27%  |
| 21-50          | 62        | 18.96%  |
| 51-100         | 48        | 14.68%  |
| 251-500        | 26        | 7.95%   |
| 501-1000       | 13        | 3.98%   |
| 1001-2000      | 5         | 1.53%   |
| Unknown        | 3         | 0.92%   |
| More than 3000 | 2         | 0.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB               | 2         | 2      | 10.53%  |
| WDC WD6400BPVT-60HXZT3 640GB         | 1         | 1      | 5.26%   |
| WDC WD5000BPVT-00HXZT1 500GB         | 1         | 1      | 5.26%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 5.26%   |
| Toshiba MK5055GSX 500GB              | 1         | 1      | 5.26%   |
| Toshiba MK2561GSYN 250GB             | 1         | 1      | 5.26%   |
| Seagate ST9750420AS 752GB            | 1         | 1      | 5.26%   |
| Seagate ST9500423AS 500GB            | 1         | 1      | 5.26%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 5.26%   |
| Seagate ST500LX012-1LM162-SSHD 500GB | 1         | 1      | 5.26%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 5.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 1      | 5.26%   |
| PNY SSD2SC120G3LC709B121-460I 120GB  | 1         | 1      | 5.26%   |
| Kingston SNS4151S316G 16GB SSD       | 1         | 1      | 5.26%   |
| HGST HTS725032A7E630 320GB           | 1         | 2      | 5.26%   |
| HGST HTS541075A9E680 752GB           | 1         | 1      | 5.26%   |
| Crucial CT500P1SSD8 500GB            | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 6         | 6      | 31.58%  |
| Seagate  | 6         | 6      | 31.58%  |
| WDC      | 2         | 2      | 10.53%  |
| HGST     | 2         | 3      | 10.53%  |
| PNY      | 1         | 1      | 5.26%   |
| Kingston | 1         | 1      | 5.26%   |
| Crucial  | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 6         | 6      | 37.5%   |
| Seagate | 6         | 6      | 37.5%   |
| WDC     | 2         | 2      | 12.5%   |
| HGST    | 2         | 3      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 17     | 84.21%  |
| SSD  | 2         | 2      | 10.53%  |
| NVMe | 1         | 1      | 5.26%   |

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
| Detected | 185       | 264    | 55.06%  |
| Works    | 132       | 174    | 39.29%  |
| Malfunc  | 19        | 20     | 5.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 226       | 62.43%  |
| Samsung Electronics          | 49        | 13.54%  |
| AMD                          | 27        | 7.46%   |
| SanDisk                      | 19        | 5.25%   |
| SK hynix                     | 11        | 3.04%   |
| Toshiba America Info Systems | 7         | 1.93%   |
| Micron Technology            | 3         | 0.83%   |
| Kingston Technology Company  | 3         | 0.83%   |
| Realtek Semiconductor        | 2         | 0.55%   |
| Nvidia                       | 2         | 0.55%   |
| Micron/Crucial Technology    | 2         | 0.55%   |
| Lenovo                       | 2         | 0.55%   |
| KIOXIA                       | 2         | 0.55%   |
| ADATA Technology             | 2         | 0.55%   |
| Union Memory (Shenzhen)      | 1         | 0.28%   |
| Silicon Motion               | 1         | 0.28%   |
| Shenzhen Longsys Electronics | 1         | 0.28%   |
| Phison Electronics           | 1         | 0.28%   |
| Apple                        | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 32        | 8.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 31        | 8.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 28        | 7.31%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 24        | 6.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 20        | 5.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 15        | 3.92%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 14        | 3.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 3.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 2.61%   |
| Intel Comet Lake SATA AHCI Controller                                            | 10        | 2.61%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 9         | 2.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9         | 2.35%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 8         | 2.09%   |
| Samsung NVMe SSD Controller 980                                                  | 7         | 1.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 1.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 1.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 1.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 1.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 1.31%   |
| Intel SSD 660P Series                                                            | 5         | 1.31%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 1.31%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 1.04%   |
| SanDisk PC SN520 NVMe SSD                                                        | 4         | 1.04%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 1.04%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 1.04%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 1.04%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.78%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.78%   |
| SK hynix Non-Volatile memory controller                                          | 3         | 0.78%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.78%   |
| Micron Non-Volatile memory controller                                            | 3         | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 0.78%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 2         | 0.52%   |
| SK hynix Gold P31 SSD                                                            | 2         | 0.52%   |
| Samsung Electronics SATA controller                                              | 2         | 0.52%   |
| Realtek Realtek Non-Volatile memory controller                                   | 2         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 231       | 61.76%  |
| NVMe | 111       | 29.68%  |
| RAID | 20        | 5.35%   |
| IDE  | 12        | 3.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 277       | 87.38%  |
| AMD    | 40        | 12.62%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 17        | 5.36%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 3.47%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 2.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 9         | 2.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.89%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 1.89%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 1.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.26%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.26%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 1.26%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 1.26%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 4         | 1.26%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.26%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 1.26%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.26%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 1.26%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 1.26%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.95%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 0.95%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 0.95%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.95%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 0.95%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.95%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.95%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.95%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.95%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.95%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 0.95%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 0.95%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 0.63%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz        | 2         | 0.63%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 2         | 0.63%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.63%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 0.63%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.63%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 0.63%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.63%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 115       | 36.28%  |
| Intel Core i5           | 77        | 24.29%  |
| Intel Core i3           | 20        | 6.31%   |
| Other                   | 16        | 5.05%   |
| Intel Celeron           | 13        | 4.1%    |
| AMD Ryzen 5             | 13        | 4.1%    |
| Intel Core 2 Duo        | 11        | 3.47%   |
| AMD Ryzen 7             | 10        | 3.15%   |
| Intel Pentium           | 7         | 2.21%   |
| Intel Atom              | 5         | 1.58%   |
| Intel Pentium Silver    | 4         | 1.26%   |
| AMD A8                  | 4         | 1.26%   |
| AMD E                   | 3         | 0.95%   |
| Intel Pentium Dual      | 2         | 0.63%   |
| Intel Genuine           | 2         | 0.63%   |
| Intel Core i9           | 2         | 0.63%   |
| AMD Turion 64 X2 Mobile | 2         | 0.63%   |
| AMD Ryzen 9             | 2         | 0.63%   |
| AMD A6                  | 2         | 0.63%   |
| Intel Pentium Dual-Core | 1         | 0.32%   |
| Intel Core m5           | 1         | 0.32%   |
| Intel Core m3           | 1         | 0.32%   |
| AMD Quad-Core           | 1         | 0.32%   |
| AMD E1                  | 1         | 0.32%   |
| AMD Athlon II           | 1         | 0.32%   |
| AMD A10                 | 1         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 139       | 43.85%  |
| 2      | 134       | 42.27%  |
| 6      | 24        | 7.57%   |
| 8      | 15        | 4.73%   |
| 1      | 2         | 0.63%   |
| 16     | 1         | 0.32%   |
| 14     | 1         | 0.32%   |
| 10     | 1         | 0.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 317       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 245       | 77.29%  |
| 1      | 72        | 22.71%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 316       | 99.68%  |
| 32-bit         | 1         | 0.32%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 25.31%  |
| 0x206a7    | 22        | 6.79%   |
| 0x806ec    | 20        | 6.17%   |
| 0x306a9    | 19        | 5.86%   |
| 0x906ea    | 13        | 4.01%   |
| 0x806ea    | 13        | 4.01%   |
| 0x806c1    | 11        | 3.4%    |
| 0x40651    | 11        | 3.4%    |
| 0x806e9    | 10        | 3.09%   |
| 0x306d4    | 9         | 2.78%   |
| 0x306c3    | 9         | 2.78%   |
| 0x806eb    | 8         | 2.47%   |
| 0x406e3    | 8         | 2.47%   |
| 0x906e9    | 7         | 2.16%   |
| 0x08600103 | 5         | 1.54%   |
| 0xa0652    | 4         | 1.23%   |
| 0x20655    | 4         | 1.23%   |
| 0x1067a    | 4         | 1.23%   |
| 0x10676    | 4         | 1.23%   |
| 0xa0660    | 3         | 0.93%   |
| 0x706e5    | 3         | 0.93%   |
| 0x506e3    | 3         | 0.93%   |
| 0x406c3    | 3         | 0.93%   |
| 0x30678    | 3         | 0.93%   |
| 0x0a50000c | 3         | 0.93%   |
| 0x08600106 | 3         | 0.93%   |
| 0x08108109 | 3         | 0.93%   |
| 0x0810100b | 3         | 0.93%   |
| 0x05000119 | 3         | 0.93%   |
| 0x706a8    | 2         | 0.62%   |
| 0x706a1    | 2         | 0.62%   |
| 0x6fd      | 2         | 0.62%   |
| 0x506c9    | 2         | 0.62%   |
| 0x20652    | 2         | 0.62%   |
| 0x08600104 | 2         | 0.62%   |
| 0x906ed    | 1         | 0.31%   |
| 0x906c0    | 1         | 0.31%   |
| 0x906a3    | 1         | 0.31%   |
| 0x806d1    | 1         | 0.31%   |
| 0x6fb      | 1         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 96        | 30.28%  |
| IvyBridge        | 26        | 8.2%    |
| SandyBridge      | 25        | 7.89%   |
| Haswell          | 23        | 7.26%   |
| Skylake          | 15        | 4.73%   |
| Zen 2            | 14        | 4.42%   |
| TigerLake        | 13        | 4.1%    |
| Broadwell        | 12        | 3.79%   |
| Silvermont       | 11        | 3.47%   |
| Penryn           | 11        | 3.47%   |
| CometLake        | 11        | 3.47%   |
| Goldmont plus    | 8         | 2.52%   |
| Westmere         | 7         | 2.21%   |
| IceLake          | 7         | 2.21%   |
| Zen+             | 4         | 1.26%   |
| Core             | 4         | 1.26%   |
| Zen 3            | 3         | 0.95%   |
| Zen              | 3         | 0.95%   |
| Puma             | 3         | 0.95%   |
| Bobcat           | 3         | 0.95%   |
| K8 Hammer        | 2         | 0.63%   |
| Jaguar           | 2         | 0.63%   |
| Goldmont         | 2         | 0.63%   |
| Excavator        | 2         | 0.63%   |
| Unknown          | 2         | 0.63%   |
| Tremont          | 1         | 0.32%   |
| Piledriver       | 1         | 0.32%   |
| P6               | 1         | 0.32%   |
| Nehalem          | 1         | 0.32%   |
| K10 Llano        | 1         | 0.32%   |
| K10              | 1         | 0.32%   |
| Bonnell          | 1         | 0.32%   |
| Alderlake Hybrid | 1         | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 259       | 63.33%  |
| Nvidia | 92        | 22.49%  |
| AMD    | 58        | 14.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 24        | 5.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 24        | 5.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 23        | 5.52%   |
| Intel UHD Graphics 620                                                                   | 21        | 5.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 3.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 3.12%   |
| AMD Renoir                                                                               | 13        | 3.12%   |
| Intel HD Graphics 620                                                                    | 12        | 2.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 2.88%   |
| Intel HD Graphics 5500                                                                   | 10        | 2.4%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 2.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 2.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 1.92%   |
| Intel HD Graphics 630                                                                    | 8         | 1.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.68%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.44%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.44%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.2%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.2%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.2%    |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.96%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 0.96%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.96%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.96%   |
| Intel HD Graphics 530                                                                    | 4         | 0.96%   |
| Intel Comet Lake UHD Graphics                                                            | 4         | 0.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 0.96%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.72%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.72%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.72%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.72%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.72%   |
| AMD Cezanne                                                                              | 3         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 172       | 54.26%  |
| Intel + Nvidia | 70        | 22.08%  |
| 1 x AMD        | 32        | 10.09%  |
| 1 x Nvidia     | 16        | 5.05%   |
| Intel + AMD    | 16        | 5.05%   |
| AMD + Nvidia   | 6         | 1.89%   |
| 2 x AMD        | 4         | 1.26%   |
| Other          | 1         | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 252       | 79%     |
| Proprietary | 62        | 19.44%  |
| Unknown     | 5         | 1.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 222       | 69.16%  |
| 1.01-2.0   | 33        | 10.28%  |
| 0.01-0.5   | 17        | 5.3%    |
| 3.01-4.0   | 16        | 4.98%   |
| 0.51-1.0   | 16        | 4.98%   |
| 7.01-8.0   | 8         | 2.49%   |
| 5.01-6.0   | 8         | 2.49%   |
| 2.01-3.0   | 1         | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 76        | 19.95%  |
| AU Optronics            | 66        | 17.32%  |
| BOE                     | 44        | 11.55%  |
| LG Display              | 43        | 11.29%  |
| Samsung Electronics     | 32        | 8.4%    |
| Dell                    | 14        | 3.67%   |
| Goldstar                | 12        | 3.15%   |
| Chi Mei Optoelectronics | 11        | 2.89%   |
| Apple                   | 10        | 2.62%   |
| Sharp                   | 9         | 2.36%   |
| Lenovo                  | 7         | 1.84%   |
| PANDA                   | 6         | 1.57%   |
| Hewlett-Packard         | 6         | 1.57%   |
| BenQ                    | 6         | 1.57%   |
| Acer                    | 5         | 1.31%   |
| Ancor Communications    | 4         | 1.05%   |
| Philips                 | 3         | 0.79%   |
| LGD                     | 3         | 0.79%   |
| InfoVision              | 3         | 0.79%   |
| Unknown (AAA)           | 2         | 0.52%   |
| Fujitsu Siemens         | 2         | 0.52%   |
| ASUSTek Computer        | 2         | 0.52%   |
| AOC                     | 2         | 0.52%   |
| Vestel Elektronik       | 1         | 0.26%   |
| UPD                     | 1         | 0.26%   |
| Unknown                 | 1         | 0.26%   |
| LG Philips              | 1         | 0.26%   |
| LaCie                   | 1         | 0.26%   |
| KTC                     | 1         | 0.26%   |
| JDI                     | 1         | 0.26%   |
| InnoLux Display         | 1         | 0.26%   |
| Iiyama                  | 1         | 0.26%   |
| IBM                     | 1         | 0.26%   |
| GDH                     | 1         | 0.26%   |
| Eizo                    | 1         | 0.26%   |
| CSO                     | 1         | 0.26%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 6         | 1.55%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch         | 6         | 1.55%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 5         | 1.29%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.78%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.78%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 3         | 0.78%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch           | 3         | 0.78%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.78%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 2         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 2         | 0.52%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 2         | 0.52%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 2         | 0.52%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.52%   |
| LGD LCD Monitor 1920x1080                                                | 2         | 0.52%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 2         | 0.52%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 2         | 0.52%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch              | 2         | 0.52%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 2         | 0.52%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 0.52%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch              | 2         | 0.52%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 2         | 0.52%   |
| Dell U3415W DELA0AA 3440x1440 798x335mm 34.1-inch                        | 2         | 0.52%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                         | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch         | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch         | 2         | 0.52%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 2         | 0.52%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.52%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                    | 2         | 0.52%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.52%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.52%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 2         | 0.52%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 2         | 0.52%   |
| AU Optronics LCD Monitor AUO282B 3840x2160 293x165mm 13.2-inch           | 2         | 0.52%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.52%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 380x210mm 17.1-inch           | 2         | 0.52%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch            | 2         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 156       | 44.32%  |
| 1366x768 (WXGA)    | 99        | 28.13%  |
| 2560x1440 (QHD)    | 17        | 4.83%   |
| 1600x900 (HD+)     | 15        | 4.26%   |
| 3840x2160 (4K)     | 12        | 3.41%   |
| 1280x800 (WXGA)    | 12        | 3.41%   |
| 1440x900 (WXGA+)   | 6         | 1.7%    |
| 1920x1200 (WUXGA)  | 5         | 1.42%   |
| 2880x1800          | 4         | 1.14%   |
| 1680x1050 (WSXGA+) | 4         | 1.14%   |
| 3440x1440          | 3         | 0.85%   |
| 3200x1800 (QHD+)   | 3         | 0.85%   |
| 2560x1080          | 2         | 0.57%   |
| 2160x1440          | 2         | 0.57%   |
| 1280x1024 (SXGA)   | 2         | 0.57%   |
| 3840x2400          | 1         | 0.28%   |
| 3840x1100          | 1         | 0.28%   |
| 3840x1080          | 1         | 0.28%   |
| 3000x2000          | 1         | 0.28%   |
| 2560x1600          | 1         | 0.28%   |
| 2256x1504          | 1         | 0.28%   |
| 1920x1280          | 1         | 0.28%   |
| 1600x1200          | 1         | 0.28%   |
| 1360x768           | 1         | 0.28%   |
| 1280x768           | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 141       | 36.62%  |
| 13      | 69        | 17.92%  |
| 14      | 46        | 11.95%  |
| 17      | 23        | 5.97%   |
| 24      | 20        | 5.19%   |
| 27      | 15        | 3.9%    |
| 23      | 12        | 3.12%   |
| 11      | 10        | 2.6%    |
| 21      | 7         | 1.82%   |
| 34      | 5         | 1.3%    |
| 12      | 5         | 1.3%    |
| Unknown | 5         | 1.3%    |
| 31      | 4         | 1.04%   |
| 19      | 4         | 1.04%   |
| 40      | 3         | 0.78%   |
| 84      | 2         | 0.52%   |
| 48      | 2         | 0.52%   |
| 32      | 2         | 0.52%   |
| 22      | 2         | 0.52%   |
| 18      | 2         | 0.52%   |
| 72      | 1         | 0.26%   |
| 54      | 1         | 0.26%   |
| 44      | 1         | 0.26%   |
| 29      | 1         | 0.26%   |
| 20      | 1         | 0.26%   |
| 10      | 1         | 0.26%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 221       | 58.16%  |
| 201-300     | 47        | 12.37%  |
| 501-600     | 42        | 11.05%  |
| 351-400     | 28        | 7.37%   |
| 401-500     | 15        | 3.95%   |
| 701-800     | 7         | 1.84%   |
| 601-700     | 5         | 1.32%   |
| Unknown     | 5         | 1.32%   |
| 801-900     | 3         | 0.79%   |
| 1501-2000   | 3         | 0.79%   |
| 1001-1500   | 3         | 0.79%   |
| 901-1000    | 1         | 0.26%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 275       | 82.58%  |
| 16/10   | 37        | 11.11%  |
| 3/2     | 6         | 1.8%    |
| 21/9    | 5         | 1.5%    |
| Unknown | 5         | 1.5%    |
| 5/4     | 2         | 0.6%    |
| 4/3     | 1         | 0.3%    |
| 32/9    | 1         | 0.3%    |
| 3.40    | 1         | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 141       | 36.81%  |
| 81-90          | 90        | 23.5%   |
| 201-250        | 31        | 8.09%   |
| 71-80          | 24        | 6.27%   |
| 121-130        | 19        | 4.96%   |
| 301-350        | 15        | 3.92%   |
| 351-500        | 12        | 3.13%   |
| 51-60          | 11        | 2.87%   |
| 251-300        | 8         | 2.09%   |
| More than 1000 | 5         | 1.31%   |
| 61-70          | 5         | 1.31%   |
| 151-200        | 5         | 1.31%   |
| 501-1000       | 5         | 1.31%   |
| Unknown        | 5         | 1.31%   |
| 131-140        | 4         | 1.04%   |
| 141-150        | 2         | 0.52%   |
| 41-50          | 1         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 141       | 37.6%   |
| 101-120       | 116       | 30.93%  |
| 51-100        | 64        | 17.07%  |
| 161-240       | 26        | 6.93%   |
| More than 240 | 16        | 4.27%   |
| 1-50          | 7         | 1.87%   |
| Unknown       | 5         | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 250       | 77.16%  |
| 2     | 59        | 18.21%  |
| 3     | 10        | 3.09%   |
| 0     | 5         | 1.54%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 191       | 36.87%  |
| Realtek Semiconductor                 | 164       | 31.66%  |
| Qualcomm Atheros                      | 75        | 14.48%  |
| Broadcom                              | 27        | 5.21%   |
| Broadcom Limited                      | 12        | 2.32%   |
| Marvell Technology Group              | 6         | 1.16%   |
| Ralink                                | 5         | 0.97%   |
| Hewlett-Packard                       | 5         | 0.97%   |
| MediaTek                              | 3         | 0.58%   |
| ASIX Electronics                      | 3         | 0.58%   |
| Sierra Wireless                       | 2         | 0.39%   |
| Nvidia                                | 2         | 0.39%   |
| Lenovo                                | 2         | 0.39%   |
| JMicron Technology                    | 2         | 0.39%   |
| Huawei Technologies                   | 2         | 0.39%   |
| DisplayLink                           | 2         | 0.39%   |
| Xiaomi                                | 1         | 0.19%   |
| TP-Link                               | 1         | 0.19%   |
| Samsung Electronics                   | 1         | 0.19%   |
| Ralink Technology                     | 1         | 0.19%   |
| Qualcomm Atheros Communications       | 1         | 0.19%   |
| Novatek Microelectronics              | 1         | 0.19%   |
| NetGear                               | 1         | 0.19%   |
| Google                                | 1         | 0.19%   |
| Ericsson Business Mobile Networks     | 1         | 0.19%   |
| Edimax Technology                     | 1         | 0.19%   |
| Dell                                  | 1         | 0.19%   |
| BUFFALO                               | 1         | 0.19%   |
| ASUSTek Computer                      | 1         | 0.19%   |
| Apple                                 | 1         | 0.19%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 101       | 16.4%   |
| Intel Wi-Fi 6 AX200                                               | 33        | 5.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 3.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 23        | 3.73%   |
| Intel Wireless 8265 / 8275                                        | 22        | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 16        | 2.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 2.6%    |
| Intel Wireless-AC 9260                                            | 14        | 2.27%   |
| Intel Wireless 7265                                               | 11        | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 1.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 1.62%   |
| Intel Wireless 8260                                               | 10        | 1.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 1.62%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 1.14%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 1.14%   |
| Intel Wireless 7260                                               | 6         | 0.97%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.81%   |
| Intel Wireless 3165                                               | 5         | 0.81%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5         | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.65%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.65%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 4         | 0.65%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.65%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.49%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.49%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 184       | 55.76%  |
| Qualcomm Atheros                      | 59        | 17.88%  |
| Realtek Semiconductor                 | 37        | 11.21%  |
| Broadcom                              | 22        | 6.67%   |
| Broadcom Limited                      | 9         | 2.73%   |
| Ralink                                | 5         | 1.52%   |
| MediaTek                              | 3         | 0.91%   |
| Sierra Wireless                       | 2         | 0.61%   |
| TP-Link                               | 1         | 0.3%    |
| Ralink Technology                     | 1         | 0.3%    |
| Qualcomm Atheros Communications       | 1         | 0.3%    |
| NetGear                               | 1         | 0.3%    |
| Hewlett-Packard                       | 1         | 0.3%    |
| Edimax Technology                     | 1         | 0.3%    |
| BUFFALO                               | 1         | 0.3%    |
| ASUSTek Computer                      | 1         | 0.3%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 33        | 9.97%   |
| Intel Wireless 8265 / 8275                                     | 22        | 6.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 16        | 4.83%   |
| Intel Wireless-AC 9260                                         | 14        | 4.23%   |
| Intel Wireless 7265                                            | 11        | 3.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 3.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 3.02%   |
| Intel Wireless 8260                                            | 10        | 3.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 10        | 3.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 2.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 2.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 2.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 7         | 2.11%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 2.11%   |
| Intel Wireless 7260                                            | 6         | 1.81%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 1.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 1.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.51%   |
| Intel Wireless 3165                                            | 5         | 1.51%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5         | 1.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.21%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 1.21%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 4         | 1.21%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.21%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 1.21%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.91%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 0.91%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.91%   |
| Intel WiFi Link 5100                                           | 3         | 0.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 0.91%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.91%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 0.91%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 0.91%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 3         | 0.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 0.91%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.6%    |
| Realtek 802.11n WLAN Adapter                                   | 2         | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 147       | 54.65%  |
| Intel                    | 62        | 23.05%  |
| Qualcomm Atheros         | 23        | 8.55%   |
| Broadcom                 | 11        | 4.09%   |
| Marvell Technology Group | 6         | 2.23%   |
| Broadcom Limited         | 3         | 1.12%   |
| ASIX Electronics         | 3         | 1.12%   |
| Nvidia                   | 2         | 0.74%   |
| Lenovo                   | 2         | 0.74%   |
| JMicron Technology       | 2         | 0.74%   |
| Hewlett-Packard          | 2         | 0.74%   |
| DisplayLink              | 2         | 0.74%   |
| Xiaomi                   | 1         | 0.37%   |
| Samsung Electronics      | 1         | 0.37%   |
| Google                   | 1         | 0.37%   |
| Apple                    | 1         | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 101       | 36.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 24        | 8.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 23        | 8.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 5.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 2.52%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 5         | 1.8%    |
| Intel Ethernet Connection (6) I219-V                                           | 5         | 1.8%    |
| Intel Ethernet Connection (4) I219-LM                                          | 5         | 1.8%    |
| Realtek RTL8125 2.5GbE Controller                                              | 4         | 1.44%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 1.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 1.08%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.08%   |
| Intel Ethernet Connection (6) I219-LM                                          | 3         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.08%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 1.08%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.08%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.72%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.72%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.72%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 0.72%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.72%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.72%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.72%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.72%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 2         | 0.72%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.36%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.36%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.36%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.36%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.36%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 314       | 54.61%  |
| Ethernet | 254       | 44.17%  |
| Modem    | 7         | 1.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 273       | 81.49%  |
| Ethernet | 62        | 18.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 238       | 74.84%  |
| 1     | 73        | 22.96%  |
| 0     | 6         | 1.89%   |
| 3     | 1         | 0.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 271       | 84.69%  |
| Yes  | 49        | 15.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 144       | 53.73%  |
| Qualcomm Atheros Communications | 26        | 9.7%    |
| Realtek Semiconductor           | 19        | 7.09%   |
| Broadcom                        | 16        | 5.97%   |
| Apple                           | 10        | 3.73%   |
| Lite-On Technology              | 9         | 3.36%   |
| Foxconn / Hon Hai               | 9         | 3.36%   |
| IMC Networks                    | 8         | 2.99%   |
| Dell                            | 6         | 2.24%   |
| Hewlett-Packard                 | 5         | 1.87%   |
| Realtek                         | 4         | 1.49%   |
| Ralink                          | 3         | 1.12%   |
| Toshiba                         | 2         | 0.75%   |
| Foxconn International           | 2         | 0.75%   |
| Cambridge Silicon Radio         | 2         | 0.75%   |
| Unknown                         | 1         | 0.37%   |
| Integrated System Solution      | 1         | 0.37%   |
| Belkin Components               | 1         | 0.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 54        | 20.15%  |
| Intel AX200 Bluetooth                               | 31        | 11.57%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 17        | 6.34%   |
| Intel AX201 Bluetooth                               | 17        | 6.34%   |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 5.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 14        | 5.22%   |
| Realtek Bluetooth Radio                             | 11        | 4.1%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 2.24%   |
| Apple Bluetooth Host Controller                     | 6         | 2.24%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 1.87%   |
| Dell DW375 Bluetooth Module                         | 5         | 1.87%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.49%   |
| Realtek Bluetooth Radio                             | 4         | 1.49%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 1.49%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 1.49%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.49%   |
| Realtek RTL8723B Bluetooth                          | 3         | 1.12%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.12%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.12%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.12%   |
| Lite-On Bluetooth Device                            | 2         | 0.75%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.75%   |
| IMC Networks Wireless_Device                        | 2         | 0.75%   |
| IMC Networks Bluetooth Radio                        | 2         | 0.75%   |
| IMC Networks Bluetooth Device                       | 2         | 0.75%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.75%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.75%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.75%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.75%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.75%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.75%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.75%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.75%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.75%   |
| Apple Bluetooth HCI                                 | 2         | 0.75%   |
| Unknown Bluetooth Device                            | 1         | 0.37%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.37%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.37%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.37%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 271       | 68.78%  |
| Nvidia                    | 46        | 11.68%  |
| AMD                       | 46        | 11.68%  |
| Realtek Semiconductor     | 7         | 1.78%   |
| GN Netcom                 | 3         | 0.76%   |
| Logitech                  | 2         | 0.51%   |
| Kingston Technology       | 2         | 0.51%   |
| C-Media Electronics       | 2         | 0.51%   |
| XMOS                      | 1         | 0.25%   |
| Sennheiser Communications | 1         | 0.25%   |
| Samson Technologies       | 1         | 0.25%   |
| Razer USA                 | 1         | 0.25%   |
| Plantronics               | 1         | 0.25%   |
| No brand                  | 1         | 0.25%   |
| Lenovo                    | 1         | 0.25%   |
| JMTek                     | 1         | 0.25%   |
| Hewlett-Packard           | 1         | 0.25%   |
| GYROCOM C&C               | 1         | 0.25%   |
| Generalplus Technology    | 1         | 0.25%   |
| Conexant Systems          | 1         | 0.25%   |
| CMX Systems               | 1         | 0.25%   |
| Cambridge Audio           | 1         | 0.25%   |
| Apple                     | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 45        | 9.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 29        | 6.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 25        | 5.43%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 24        | 5.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 22        | 4.78%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 16        | 3.48%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 2.83%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 2.83%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 2.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 2.61%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 2.61%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 2.61%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 12        | 2.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 1.96%   |
| Intel CM238 HD Audio Controller                                                                   | 9         | 1.96%   |
| AMD FCH Azalia Controller                                                                         | 9         | 1.96%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 8         | 1.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 1.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 1.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 1.74%   |
| Realtek Semiconductor USB Audio                                                                   | 7         | 1.52%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.52%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 1.3%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.3%    |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.3%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 5         | 1.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 0.87%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.65%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.65%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 0.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.65%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.65%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.65%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.43%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 76        | 34.86%  |
| SK hynix            | 50        | 22.94%  |
| Micron Technology   | 24        | 11.01%  |
| Kingston            | 14        | 6.42%   |
| Unknown             | 9         | 4.13%   |
| Ramaxel Technology  | 9         | 4.13%   |
| Crucial             | 9         | 4.13%   |
| Unknown (ABCD)      | 3         | 1.38%   |
| Corsair             | 3         | 1.38%   |
| A-DATA Technology   | 3         | 1.38%   |
| Unknown             | 3         | 1.38%   |
| Teikon              | 2         | 0.92%   |
| Smart               | 2         | 0.92%   |
| Elpida              | 2         | 0.92%   |
| Smart Brazil        | 1         | 0.46%   |
| PNY                 | 1         | 0.46%   |
| Patriot             | 1         | 0.46%   |
| Nanya Technology    | 1         | 0.46%   |
| Kingmax             | 1         | 0.46%   |
| Goldkey             | 1         | 0.46%   |
| fef5                | 1         | 0.46%   |
| Cors                | 1         | 0.46%   |
| ASint Technology    | 1         | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 7         | 3%      |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 5         | 2.15%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 2.15%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 2.15%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 2.15%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 1.72%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 3         | 1.29%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 3         | 1.29%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 1.29%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 1.29%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 1.29%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 3         | 1.29%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 3         | 1.29%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 1.29%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 1.29%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 3         | 1.29%   |
| Unknown                                                          | 3         | 1.29%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                    | 2         | 0.86%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.86%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.86%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.86%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.86%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 2         | 0.86%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.86%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 2         | 0.86%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.86%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.86%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.86%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.86%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.86%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.86%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.86%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.86%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 0.86%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s        | 2         | 0.86%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.86%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                   | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.43%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 95        | 50.8%   |
| DDR3    | 62        | 33.16%  |
| LPDDR4  | 10        | 5.35%   |
| LPDDR3  | 10        | 5.35%   |
| SDRAM   | 3         | 1.6%    |
| DDR2    | 3         | 1.6%    |
| Unknown | 3         | 1.6%    |
| DDR     | 1         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 161       | 88.46%  |
| Row Of Chips | 18        | 9.89%   |
| Unknown      | 2         | 1.1%    |
| Chip         | 1         | 0.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 72        | 35.82%  |
| 8192  | 70        | 34.83%  |
| 16384 | 30        | 14.93%  |
| 2048  | 14        | 6.97%   |
| 32768 | 11        | 5.47%   |
| 1024  | 4         | 1.99%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 56        | 26.79%  |
| 1600    | 44        | 21.05%  |
| 3200    | 24        | 11.48%  |
| 2133    | 18        | 8.61%   |
| 2400    | 17        | 8.13%   |
| 1334    | 9         | 4.31%   |
| 1333    | 9         | 4.31%   |
| 3266    | 5         | 2.39%   |
| 1067    | 5         | 2.39%   |
| 8400    | 3         | 1.44%   |
| 4267    | 3         | 1.44%   |
| 4199    | 3         | 1.44%   |
| 1867    | 3         | 1.44%   |
| 667     | 3         | 1.44%   |
| Unknown | 3         | 1.44%   |
| 4266    | 1         | 0.48%   |
| 3733    | 1         | 0.48%   |
| 1066    | 1         | 0.48%   |
| 533     | 1         | 0.48%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |
| Canon               | 1         | 20%     |
| Brother Industries  | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung M2020 Series   | 1         | 20%     |
| HP LaserJet 1320       | 1         | 20%     |
| HP DeskJet 2130 series | 1         | 20%     |
| Canon LiDE 400         | 1         | 20%     |
| Brother MFC-1810       | 1         | 20%     |

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
| Chicony Electronics                    | 84        | 29.47%  |
| Sunplus Innovation Technology          | 26        | 9.12%   |
| IMC Networks                           | 26        | 9.12%   |
| Acer                                   | 26        | 9.12%   |
| Realtek Semiconductor                  | 25        | 8.77%   |
| Microdia                               | 20        | 7.02%   |
| Syntek                                 | 10        | 3.51%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 3.51%   |
| Apple                                  | 10        | 3.51%   |
| Suyin                                  | 9         | 3.16%   |
| Quanta                                 | 8         | 2.81%   |
| Silicon Motion                         | 6         | 2.11%   |
| Lite-On Technology                     | 4         | 1.4%    |
| Ricoh                                  | 3         | 1.05%   |
| Luxvisions Innotech Limited            | 3         | 1.05%   |
| Alcor Micro                            | 3         | 1.05%   |
| Logitech                               | 2         | 0.7%    |
| Z-Star Microelectronics                | 1         | 0.35%   |
| Sonix Technology                       | 1         | 0.35%   |
| Samsung Electronics                    | 1         | 0.35%   |
| Primax Electronics                     | 1         | 0.35%   |
| LG Electronics                         | 1         | 0.35%   |
| Importek                               | 1         | 0.35%   |
| icSpring                               | 1         | 0.35%   |
| Generalplus Technology                 | 1         | 0.35%   |
| Creative Technology                    | 1         | 0.35%   |
| Unknown                                | 1         | 0.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony USB2.0 Camera                                   | 17        | 5.96%   |
| Chicony HD Webcam                                       | 15        | 5.26%   |
| Chicony Integrated Camera                               | 11        | 3.86%   |
| Microdia Integrated_Webcam_HD                           | 10        | 3.51%   |
| IMC Networks Integrated Camera                          | 8         | 2.81%   |
| Realtek Integrated_Webcam_HD                            | 7         | 2.46%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 7         | 2.46%   |
| Chicony HP HD Camera                                    | 6         | 2.11%   |
| Acer HD Webcam                                          | 6         | 2.11%   |
| Sunplus HD WebCam                                       | 5         | 1.75%   |
| Acer BisonCam,NB Pro                                    | 5         | 1.75%   |
| Syntek Integrated Camera                                | 4         | 1.4%    |
| IMC Networks VGA UVC WebCam                             | 4         | 1.4%    |
| Apple FaceTime HD Camera                                | 4         | 1.4%    |
| Sunplus Integrated_Webcam_HD                            | 3         | 1.05%   |
| Realtek Lenovo EasyCamera                               | 3         | 1.05%   |
| Realtek Integrated Webcam                               | 3         | 1.05%   |
| IMC Networks ov9734_azurewave_camera                    | 3         | 1.05%   |
| Chicony Integrated Camera [ThinkPad]                    | 3         | 1.05%   |
| Chicony Integrated Camera (1280x720@30)                 | 3         | 1.05%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 3         | 1.05%   |
| Apple iPhone5/5C/5S/6                                   | 3         | 1.05%   |
| Acer Integrated Camera                                  | 3         | 1.05%   |
| Acer BisonCam, NB Pro                                   | 3         | 1.05%   |
| Syntek Lenovo EasyCamera                                | 2         | 0.7%    |
| Syntek EasyCamera                                       | 2         | 0.7%    |
| Suyin HP Truevision HD                                  | 2         | 0.7%    |
| Sunplus Lenovo EasyCamera                               | 2         | 0.7%    |
| Sunplus HP HD Webcam [Fixed]                            | 2         | 0.7%    |
| Sunplus HD User Facing                                  | 2         | 0.7%    |
| Sunplus Aukey-PC-LM1E Camera                            | 2         | 0.7%    |
| Sunplus ASUS Webcam                                     | 2         | 0.7%    |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 0.7%    |
| Realtek HP "Truevision HD" laptop camera                | 2         | 0.7%    |
| Realtek HD WebCam                                       | 2         | 0.7%    |
| Microdia Sonix USB 2.0 Camera                           | 2         | 0.7%    |
| Lite-On Integrated Camera                               | 2         | 0.7%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 2         | 0.7%    |
| Chicony XiaoMi USB 2.0 Webcam                           | 2         | 0.7%    |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 26        | 35.14%  |
| Validity Sensors           | 24        | 32.43%  |
| Shenzhen Goodix Technology | 10        | 13.51%  |
| LighTuning Technology      | 7         | 9.46%   |
| Elan Microelectronics      | 4         | 5.41%   |
| AuthenTec                  | 3         | 4.05%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 9         | 12.16%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 10.81%  |
| Unknown                                                                    | 8         | 10.81%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 9.46%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 6.76%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.41%   |
| Synaptics WBDI Device                                                      | 4         | 5.41%   |
| Elan ELAN:Fingerprint                                                      | 4         | 5.41%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 4.05%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 4.05%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 4.05%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 4.05%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.7%    |
| Validity Sensors VFS491                                                    | 2         | 2.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.35%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.35%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.35%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.35%   |
| AuthenTec AES2810                                                          | 1         | 1.35%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.35%   |
| AuthenTec AES1600                                                          | 1         | 1.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 11        | 47.83%  |
| Upek                  | 5         | 21.74%  |
| Alcor Micro           | 4         | 17.39%  |
| Lenovo                | 2         | 8.7%    |
| Gemalto (was Gemplus) | 1         | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 21.74%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 21.74%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 17.39%  |
| Broadcom 5880                                                                | 3         | 13.04%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 8.7%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 8.7%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 4.35%   |
| Broadcom 58200                                                               | 1         | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 179       | 56.11%  |
| 1     | 111       | 34.8%   |
| 2     | 25        | 7.84%   |
| 3     | 2         | 0.63%   |
| 6     | 1         | 0.31%   |
| 4     | 1         | 0.31%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 73        | 43.71%  |
| Graphics card            | 24        | 14.37%  |
| Chipcard                 | 22        | 13.17%  |
| Net/wireless             | 13        | 7.78%   |
| Communication controller | 13        | 7.78%   |
| Camera                   | 5         | 2.99%   |
| Multimedia controller    | 4         | 2.4%    |
| Bluetooth                | 4         | 2.4%    |
| Storage                  | 3         | 1.8%    |
| Card reader              | 3         | 1.8%    |
| Sound                    | 2         | 1.2%    |
| Net/ethernet             | 1         | 0.6%    |

