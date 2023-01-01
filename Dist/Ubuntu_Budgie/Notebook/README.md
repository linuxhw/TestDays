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

Total: 490

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| TUXEDO        | Polaris (CML/Gen2)          | [a14e00ab97](https://linux-hardware.org/?probe=a14e00ab97) | Dec 29, 2022 |
| TUXEDO        | Polaris (CML/Gen2)          | [00e25b3232](https://linux-hardware.org/?probe=00e25b3232) | Dec 29, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [2d653884d9](https://linux-hardware.org/?probe=2d653884d9) | Dec 29, 2022 |
| Dell          | System XPS L502X            | [db4f93ae82](https://linux-hardware.org/?probe=db4f93ae82) | Dec 22, 2022 |
| MSI           | GL65 Leopard 10SDK          | [2c6e6ec3ec](https://linux-hardware.org/?probe=2c6e6ec3ec) | Dec 21, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| HP            | ProBook 445 G7              | [b34265fdbe](https://linux-hardware.org/?probe=b34265fdbe) | Dec 14, 2022 |
| Unknown       | Unknown                     | [a6efa9c8ab](https://linux-hardware.org/?probe=a6efa9c8ab) | Dec 12, 2022 |
| Unknown       | Unknown                     | [b9b1bab552](https://linux-hardware.org/?probe=b9b1bab552) | Dec 12, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [ea74cd284c](https://linux-hardware.org/?probe=ea74cd284c) | Dec 08, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [bdc64a5196](https://linux-hardware.org/?probe=bdc64a5196) | Dec 02, 2022 |
| THUNDEROBO... | 911MT                       | [40111c09eb](https://linux-hardware.org/?probe=40111c09eb) | Dec 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | [cdd03a3498](https://linux-hardware.org/?probe=cdd03a3498) | Dec 01, 2022 |
| THUNDEROBO... | 911MT                       | [2731961e4c](https://linux-hardware.org/?probe=2731961e4c) | Nov 30, 2022 |
| Dell          | Inspiron 5566               | [a130766490](https://linux-hardware.org/?probe=a130766490) | Nov 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [be7a4a88a1](https://linux-hardware.org/?probe=be7a4a88a1) | Nov 23, 2022 |
| Sony          | VPCEA45FG                   | [cb719dbd60](https://linux-hardware.org/?probe=cb719dbd60) | Nov 19, 2022 |
| MSI           | GL65 Leopard 10SFKV         | [84668eb3a8](https://linux-hardware.org/?probe=84668eb3a8) | Nov 16, 2022 |
| MSI           | GL65 Leopard 10SFKV         | [316e275c13](https://linux-hardware.org/?probe=316e275c13) | Nov 16, 2022 |
| Thomson       | N17V3C8WH512                | [f13487a2f3](https://linux-hardware.org/?probe=f13487a2f3) | Nov 07, 2022 |
| Thomson       | N17V3C8WH512                | [58d6a21b17](https://linux-hardware.org/?probe=58d6a21b17) | Nov 06, 2022 |
| ASUSTek       | UX303UA                     | [751669286c](https://linux-hardware.org/?probe=751669286c) | Nov 05, 2022 |
| Dell          | XPS 13 9310                 | [104082422f](https://linux-hardware.org/?probe=104082422f) | Nov 04, 2022 |
| Dell          | XPS 13 9310                 | [2f2963b2fc](https://linux-hardware.org/?probe=2f2963b2fc) | Nov 04, 2022 |
| Razer         | Blade 15 Advanced Model ... | [e0a589194b](https://linux-hardware.org/?probe=e0a589194b) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | [b401e89d9c](https://linux-hardware.org/?probe=b401e89d9c) | Oct 31, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | [4650c9df06](https://linux-hardware.org/?probe=4650c9df06) | Oct 31, 2022 |
| Sony          | VPCEA45FG                   | [26a8adcee2](https://linux-hardware.org/?probe=26a8adcee2) | Oct 31, 2022 |
| Sony          | VPCEA45FG                   | [3448172ca3](https://linux-hardware.org/?probe=3448172ca3) | Oct 29, 2022 |
| TUXEDO        | Aura 15 Gen1                | [4055c79756](https://linux-hardware.org/?probe=4055c79756) | Oct 28, 2022 |
| Toshiba       | Satellite A505              | [41dafcbfb9](https://linux-hardware.org/?probe=41dafcbfb9) | Oct 25, 2022 |
| ASUSTek       | X205TA                      | [2da58f110d](https://linux-hardware.org/?probe=2da58f110d) | Oct 24, 2022 |
| TUXEDO        | Polaris (CML/Gen2)          | [3cb2ce5a02](https://linux-hardware.org/?probe=3cb2ce5a02) | Oct 24, 2022 |
| Dell          | Vostro 15 5510              | [b397c3fd26](https://linux-hardware.org/?probe=b397c3fd26) | Oct 18, 2022 |
| Dell          | Latitude E5420              | [dcc7463646](https://linux-hardware.org/?probe=dcc7463646) | Oct 16, 2022 |
| Digibras      | NH4CU03                     | [45912a4bae](https://linux-hardware.org/?probe=45912a4bae) | Oct 16, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3028d439cf](https://linux-hardware.org/?probe=3028d439cf) | Oct 14, 2022 |
| Dell          | XPS 13 9360                 | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [f4d09b3dae](https://linux-hardware.org/?probe=f4d09b3dae) | Oct 13, 2022 |
| AXIOO         | Slimbook 13                 | [221b0b500d](https://linux-hardware.org/?probe=221b0b500d) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [fee12e32e5](https://linux-hardware.org/?probe=fee12e32e5) | Oct 07, 2022 |
| Dell          | Precision 5560              | [168025b691](https://linux-hardware.org/?probe=168025b691) | Oct 03, 2022 |
| Dell          | Latitude E6410              | [98545a1050](https://linux-hardware.org/?probe=98545a1050) | Sep 30, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [15d9ea100b](https://linux-hardware.org/?probe=15d9ea100b) | Sep 26, 2022 |
| TUXEDO        | Book BA1510                 | [76a485fe7e](https://linux-hardware.org/?probe=76a485fe7e) | Sep 22, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [f185fff0a3](https://linux-hardware.org/?probe=f185fff0a3) | Sep 21, 2022 |
| Lenovo        | G50-45 80E3                 | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Lenovo        | G500 20236                  | [fc210ff2c2](https://linux-hardware.org/?probe=fc210ff2c2) | Sep 07, 2022 |
| TUXEDO        | InfinityBook Pro 14 v4      | [cc583599ef](https://linux-hardware.org/?probe=cc583599ef) | Aug 28, 2022 |
| Google        | Rabbid                      | [8049c3894c](https://linux-hardware.org/?probe=8049c3894c) | Aug 24, 2022 |
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
| Ubuntu Budgie 20.04 | 167       | 47.58%  |
| Ubuntu Budgie 22.04 | 52        | 14.81%  |
| Ubuntu Budgie 20.10 | 34        | 9.69%   |
| Ubuntu Budgie 21.10 | 32        | 9.12%   |
| Ubuntu Budgie 18.04 | 24        | 6.84%   |
| Ubuntu Budgie 21.04 | 20        | 5.7%    |
| Ubuntu Budgie 19.10 | 13        | 3.7%    |
| Ubuntu Budgie 22.10 | 6         | 1.71%   |
| Ubuntu Budgie 16.04 | 2         | 0.57%   |
| Ubuntu Budgie       | 1         | 0.28%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Budgie | 343       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 18        | 4.72%   |
| 5.3.0-40-generic  | 10        | 2.62%   |
| 5.13.0-22-generic | 10        | 2.62%   |
| 5.4.0-40-generic  | 9         | 2.36%   |
| 5.8.0-41-generic  | 7         | 1.84%   |
| 5.15.0-27-generic | 7         | 1.84%   |
| 5.13.0-28-generic | 7         | 1.84%   |
| 5.4.0-37-generic  | 6         | 1.57%   |
| 5.4.0-29-generic  | 6         | 1.57%   |
| 5.13.0-39-generic | 6         | 1.57%   |
| 5.8.0-53-generic  | 5         | 1.31%   |
| 5.8.0-48-generic  | 5         | 1.31%   |
| 5.4.0-52-generic  | 5         | 1.31%   |
| 5.4.0-48-generic  | 5         | 1.31%   |
| 5.4.0-33-generic  | 5         | 1.31%   |
| 5.15.0-50-generic | 5         | 1.31%   |
| 5.15.0-48-generic | 5         | 1.31%   |
| 5.13.0-40-generic | 5         | 1.31%   |
| 5.13.0-35-generic | 5         | 1.31%   |
| 5.13.0-30-generic | 5         | 1.31%   |
| 5.13.0-19-generic | 5         | 1.31%   |
| 5.8.0-44-generic  | 4         | 1.05%   |
| 5.8.0-33-generic  | 4         | 1.05%   |
| 5.8.0-29-generic  | 4         | 1.05%   |
| 5.4.0-58-generic  | 4         | 1.05%   |
| 5.4.0-31-generic  | 4         | 1.05%   |
| 5.15.0-52-generic | 4         | 1.05%   |
| 5.15.0-46-generic | 4         | 1.05%   |
| 5.11.0-41-generic | 4         | 1.05%   |
| 5.11.0-34-generic | 4         | 1.05%   |
| 5.11.0-16-generic | 4         | 1.05%   |
| 5.8.0-45-generic  | 3         | 0.79%   |
| 5.4.0-91-generic  | 3         | 0.79%   |
| 5.4.0-73-generic  | 3         | 0.79%   |
| 5.4.0-28-generic  | 3         | 0.79%   |
| 5.19.0-23-generic | 3         | 0.79%   |
| 5.15.0-56-generic | 3         | 0.79%   |
| 5.15.0-53-generic | 3         | 0.79%   |
| 5.15.0-40-generic | 3         | 0.79%   |
| 5.15.0-39-generic | 3         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 104       | 29.3%   |
| 5.15.0  | 56        | 15.77%  |
| 5.8.0   | 54        | 15.21%  |
| 5.13.0  | 53        | 14.93%  |
| 5.11.0  | 33        | 9.3%    |
| 5.3.0   | 21        | 5.92%   |
| 4.15.0  | 10        | 2.82%   |
| 5.19.0  | 6         | 1.69%   |
| 5.6.0   | 3         | 0.85%   |
| 5.12.0  | 2         | 0.56%   |
| 5.0.0   | 2         | 0.56%   |
| 4.18.0  | 2         | 0.56%   |
| 5.9.0   | 1         | 0.28%   |
| 5.8.11  | 1         | 0.28%   |
| 5.6.7   | 1         | 0.28%   |
| 5.5.0   | 1         | 0.28%   |
| 5.16.14 | 1         | 0.28%   |
| 5.15.11 | 1         | 0.28%   |
| 5.10.11 | 1         | 0.28%   |
| 5.10.0  | 1         | 0.28%   |
| 4.4.0   | 1         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 104       | 29.3%   |
| 5.15    | 57        | 16.06%  |
| 5.8     | 55        | 15.49%  |
| 5.13    | 53        | 14.93%  |
| 5.11    | 33        | 9.3%    |
| 5.3     | 21        | 5.92%   |
| 4.15    | 10        | 2.82%   |
| 5.19    | 6         | 1.69%   |
| 5.6     | 4         | 1.13%   |
| 5.12    | 2         | 0.56%   |
| 5.10    | 2         | 0.56%   |
| 5.0     | 2         | 0.56%   |
| 4.18    | 2         | 0.56%   |
| 5.9     | 1         | 0.28%   |
| 5.5     | 1         | 0.28%   |
| 5.16    | 1         | 0.28%   |
| 4.4     | 1         | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 340       | 99.13%  |
| i686   | 3         | 0.87%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Budgie     | 335       | 97.67%  |
| GNOME      | 6         | 1.75%   |
| XFCE       | 1         | 0.29%   |
| X-Cinnamon | 1         | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 332       | 96.51%  |
| Wayland | 11        | 3.2%    |
| Tty     | 1         | 0.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 131       | 37.86%  |
| LightDM | 117       | 33.82%  |
| TDM     | 58        | 16.76%  |
| GDM     | 25        | 7.23%   |
| GDM3    | 14        | 4.05%   |
| SDDM    | 1         | 0.29%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 111       | 32.27%  |
| de_DE   | 50        | 14.53%  |
| pt_BR   | 25        | 7.27%   |
| fr_FR   | 24        | 6.98%   |
| en_GB   | 20        | 5.81%   |
| en_CA   | 13        | 3.78%   |
| ru_RU   | 11        | 3.2%    |
| en_IN   | 11        | 3.2%    |
| it_IT   | 9         | 2.62%   |
| es_AR   | 7         | 2.03%   |
| es_MX   | 6         | 1.74%   |
| C       | 6         | 1.74%   |
| es_ES   | 5         | 1.45%   |
| es_CL   | 4         | 1.16%   |
| hu_HU   | 3         | 0.87%   |
| en_AU   | 3         | 0.87%   |
| de_AT   | 3         | 0.87%   |
| Unknown | 3         | 0.87%   |
| pt_PT   | 2         | 0.58%   |
| pl_PL   | 2         | 0.58%   |
| fi_FI   | 2         | 0.58%   |
| en_IE   | 2         | 0.58%   |
| de_CH   | 2         | 0.58%   |
| zh_TW   | 1         | 0.29%   |
| zh_CN   | 1         | 0.29%   |
| uk_UA   | 1         | 0.29%   |
| tr_TR   | 1         | 0.29%   |
| nl_NL   | 1         | 0.29%   |
| nl_BE   | 1         | 0.29%   |
| nb_NO   | 1         | 0.29%   |
| lv_LV   | 1         | 0.29%   |
| id_ID   | 1         | 0.29%   |
| fr_CH   | 1         | 0.29%   |
| fr_BE   | 1         | 0.29%   |
| es_US   | 1         | 0.29%   |
| es_SV   | 1         | 0.29%   |
| es_PE   | 1         | 0.29%   |
| es_GT   | 1         | 0.29%   |
| es_EC   | 1         | 0.29%   |
| en_ZA   | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 207       | 59.31%  |
| BIOS | 142       | 40.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 322       | 93.6%   |
| Zfs     | 8         | 2.33%   |
| Overlay | 6         | 1.74%   |
| Btrfs   | 4         | 1.16%   |
| Xfs     | 3         | 0.87%   |
| Jfs     | 1         | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 173       | 50%     |
| GPT     | 147       | 42.49%  |
| MBR     | 26        | 7.51%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 305       | 88.15%  |
| Yes       | 41        | 11.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 237       | 68.5%   |
| Yes       | 109       | 31.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 66        | 19.24%  |
| Hewlett-Packard        | 51        | 14.87%  |
| Dell                   | 47        | 13.7%   |
| TUXEDO                 | 41        | 11.95%  |
| ASUSTek Computer       | 34        | 9.91%   |
| Acer                   | 21        | 6.12%   |
| MSI                    | 14        | 4.08%   |
| Apple                  | 11        | 3.21%   |
| Sony                   | 6         | 1.75%   |
| Samsung Electronics    | 5         | 1.46%   |
| HUAWEI                 | 5         | 1.46%   |
| Toshiba                | 4         | 1.17%   |
| Google                 | 4         | 1.17%   |
| Unknown                | 4         | 1.17%   |
| Packard Bell           | 3         | 0.87%   |
| Fujitsu                | 3         | 0.87%   |
| Timi                   | 2         | 0.58%   |
| Standard               | 2         | 0.58%   |
| Razer                  | 2         | 0.58%   |
| Positivo               | 2         | 0.58%   |
| Alienware              | 2         | 0.58%   |
| Viglen                 | 1         | 0.29%   |
| THUNDEROBOT            | 1         | 0.29%   |
| Thomson                | 1         | 0.29%   |
| Quanta                 | 1         | 0.29%   |
| PC Specialist          | 1         | 0.29%   |
| GPU Company            | 1         | 0.29%   |
| Gigabyte Technology    | 1         | 0.29%   |
| EVOO                   | 1         | 0.29%   |
| Digibras               | 1         | 0.29%   |
| Chuwi                  | 1         | 0.29%   |
| BANGHO                 | 1         | 0.29%   |
| AXIOO                  | 1         | 0.29%   |
| AWOW                   | 1         | 0.29%   |
| Avell High Performance | 1         | 0.29%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 14        | 4.08%   |
| TUXEDO Aura 15 Gen1                    | 3         | 0.87%   |
| HP Pavilion g6                         | 3         | 0.87%   |
| TUXEDO Pulse 15 Gen1                   | 2         | 0.58%   |
| TUXEDO Polaris 15 AMD Gen1             | 2         | 0.58%   |
| TUXEDO InfinityBook S 15 Gen6          | 2         | 0.58%   |
| TUXEDO InfinityBook S 14 Gen6          | 2         | 0.58%   |
| TUXEDO InfinityBook Pro 14 Gen6        | 2         | 0.58%   |
| Standard MT40II                        | 2         | 0.58%   |
| Lenovo ThinkBook 14-IML 20RV           | 2         | 0.58%   |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 2         | 0.58%   |
| Lenovo IdeaPad 330S-15ARR 81FB         | 2         | 0.58%   |
| Lenovo IdeaPad 320-15IKB 80XL          | 2         | 0.58%   |
| Lenovo G500 20236                      | 2         | 0.58%   |
| Lenovo G50-45 80E3                     | 2         | 0.58%   |
| HP ZBook Studio G3                     | 2         | 0.58%   |
| HP Notebook                            | 2         | 0.58%   |
| HP ENVY 17                             | 2         | 0.58%   |
| HP ENVY 15                             | 2         | 0.58%   |
| HP 2000                                | 2         | 0.58%   |
| Dell XPS 13 9380                       | 2         | 0.58%   |
| Dell Latitude E6540                    | 2         | 0.58%   |
| Dell Latitude E6410                    | 2         | 0.58%   |
| Dell Latitude 5400                     | 2         | 0.58%   |
| Dell Inspiron 5570                     | 2         | 0.58%   |
| ASUS VivoBook_ASUSLaptop X571GT_F571GT | 2         | 0.58%   |
| Apple MacBookPro8,1                    | 2         | 0.58%   |
| Acer TravelMate P446-M                 | 2         | 0.58%   |
| Viglen VUB1                            | 1         | 0.29%   |
| TUXEDO Stellaris Intel Gen3 (TGL)      | 1         | 0.29%   |
| TUXEDO Stellaris AMD Gen3 (CZN)        | 1         | 0.29%   |
| TUXEDO Polaris Intel Gen3 (TGL)        | 1         | 0.29%   |
| TUXEDO Polaris AMD Gen3 (CZN)          | 1         | 0.29%   |
| TUXEDO Polaris 17 AMD Gen1             | 1         | 0.29%   |
| TUXEDO Polaris (CML/Gen2)              | 1         | 0.29%   |
| TUXEDO P95_HR                          | 1         | 0.29%   |
| TUXEDO P95_HP                          | 1         | 0.29%   |
| TUXEDO P7xxTM1                         | 1         | 0.29%   |
| TUXEDO InfinityBook_Pro13_14_v4        | 1         | 0.29%   |
| TUXEDO InfinityBook S 14 v5            | 1         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 30        | 8.75%   |
| Dell Latitude         | 18        | 5.25%   |
| Lenovo IdeaPad        | 16        | 4.66%   |
| Unknown               | 14        | 4.08%   |
| Dell Inspiron         | 13        | 3.79%   |
| Acer Aspire           | 13        | 3.79%   |
| HP Pavilion           | 12        | 3.5%    |
| TUXEDO InfinityBook   | 10        | 2.92%   |
| HP EliteBook          | 9         | 2.62%   |
| Dell XPS              | 9         | 2.62%   |
| ASUS VivoBook         | 7         | 2.04%   |
| TUXEDO Polaris        | 6         | 1.75%   |
| HP ENVY               | 6         | 1.75%   |
| TUXEDO Book           | 5         | 1.46%   |
| HP ProBook            | 5         | 1.46%   |
| Toshiba Satellite     | 4         | 1.17%   |
| Lenovo ThinkBook      | 4         | 1.17%   |
| HP ZBook              | 4         | 1.17%   |
| HP Laptop             | 4         | 1.17%   |
| Acer Swift            | 4         | 1.17%   |
| TUXEDO Aura           | 3         | 0.87%   |
| HP Compaq             | 3         | 0.87%   |
| Fujitsu LIFEBOOK      | 3         | 0.87%   |
| Dell Vostro           | 3         | 0.87%   |
| Apple MacBookPro8     | 3         | 0.87%   |
| Acer TravelMate       | 3         | 0.87%   |
| TUXEDO Stellaris      | 2         | 0.58%   |
| TUXEDO Pulse          | 2         | 0.58%   |
| TUXEDO P95            | 2         | 0.58%   |
| Standard MT40II       | 2         | 0.58%   |
| Razer Blade           | 2         | 0.58%   |
| Packard Bell EasyNote | 2         | 0.58%   |
| MSI Prestige          | 2         | 0.58%   |
| MSI Modern            | 2         | 0.58%   |
| MSI GL65              | 2         | 0.58%   |
| Lenovo Yoga           | 2         | 0.58%   |
| Lenovo G500           | 2         | 0.58%   |
| Lenovo G50-45         | 2         | 0.58%   |
| HP Notebook           | 2         | 0.58%   |
| HP 2000               | 2         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 50        | 14.58%  |
| 2020 | 41        | 11.95%  |
| 2018 | 40        | 11.66%  |
| 2021 | 28        | 8.16%   |
| 2011 | 26        | 7.58%   |
| 2017 | 22        | 6.41%   |
| 2012 | 22        | 6.41%   |
| 2014 | 21        | 6.12%   |
| 2016 | 19        | 5.54%   |
| 2013 | 19        | 5.54%   |
| 2015 | 17        | 4.96%   |
| 2010 | 13        | 3.79%   |
| 2008 | 10        | 2.92%   |
| 2009 | 7         | 2.04%   |
| 2007 | 6         | 1.75%   |
| 2022 | 2         | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 343       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 308       | 89.53%  |
| Enabled  | 36        | 10.47%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 339       | 98.83%  |
| Yes  | 4         | 1.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 103       | 29.77%  |
| 16.01-24.0  | 74        | 21.39%  |
| 3.01-4.0    | 55        | 15.9%   |
| 8.01-16.0   | 54        | 15.61%  |
| 32.01-64.0  | 34        | 9.83%   |
| 64.01-256.0 | 11        | 3.18%   |
| 1.01-2.0    | 9         | 2.6%    |
| 24.01-32.0  | 4         | 1.16%   |
| 2.01-3.0    | 2         | 0.58%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 106       | 28.96%  |
| 1.01-2.0   | 104       | 28.42%  |
| 4.01-8.0   | 72        | 19.67%  |
| 3.01-4.0   | 61        | 16.67%  |
| 8.01-16.0  | 17        | 4.64%   |
| 0.51-1.0   | 3         | 0.82%   |
| 16.01-24.0 | 2         | 0.55%   |
| 24.01-32.0 | 1         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 248       | 71.68%  |
| 2      | 88        | 25.43%  |
| 3      | 9         | 2.6%    |
| 0      | 1         | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 245       | 71.22%  |
| Yes       | 99        | 28.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 275       | 79.71%  |
| No        | 70        | 20.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 339       | 98.83%  |
| No        | 4         | 1.17%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 288       | 83.48%  |
| No        | 57        | 16.52%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 57        | 16.62%  |
| USA                | 44        | 12.83%  |
| Brazil             | 28        | 8.16%   |
| France             | 23        | 6.71%   |
| India              | 13        | 3.79%   |
| Russia             | 12        | 3.5%    |
| Italy              | 12        | 3.5%    |
| UK                 | 11        | 3.21%   |
| Canada             | 11        | 3.21%   |
| Argentina          | 9         | 2.62%   |
| Netherlands        | 8         | 2.33%   |
| Mexico             | 8         | 2.33%   |
| Spain              | 7         | 2.04%   |
| Poland             | 7         | 2.04%   |
| Austria            | 5         | 1.46%   |
| Ukraine            | 4         | 1.17%   |
| Switzerland        | 4         | 1.17%   |
| Hungary            | 4         | 1.17%   |
| Greece             | 4         | 1.17%   |
| Finland            | 4         | 1.17%   |
| Chile              | 4         | 1.17%   |
| Turkey             | 3         | 0.87%   |
| Sweden             | 3         | 0.87%   |
| South Africa       | 3         | 0.87%   |
| Portugal           | 3         | 0.87%   |
| Norway             | 3         | 0.87%   |
| Iran               | 3         | 0.87%   |
| Indonesia          | 3         | 0.87%   |
| Dominican Republic | 3         | 0.87%   |
| Belgium            | 3         | 0.87%   |
| Australia          | 3         | 0.87%   |
| Slovenia           | 2         | 0.58%   |
| Malaysia           | 2         | 0.58%   |
| Japan              | 2         | 0.58%   |
| Ireland            | 2         | 0.58%   |
| Ecuador            | 2         | 0.58%   |
| Colombia           | 2         | 0.58%   |
| Taiwan             | 1         | 0.29%   |
| Singapore          | 1         | 0.29%   |
| Serbia             | 1         | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 6         | 1.72%   |
| Berlin             | 6         | 1.72%   |
| Moscow             | 5         | 1.43%   |
| Ravensburg         | 4         | 1.15%   |
| Budapest           | 4         | 1.15%   |
| Athens             | 4         | 1.15%   |
| Tehran             | 3         | 0.86%   |
| St Petersburg      | 3         | 0.86%   |
| Santo Domingo Este | 3         | 0.86%   |
| Pune               | 3         | 0.86%   |
| Munich             | 3         | 0.86%   |
| Montreal           | 3         | 0.86%   |
| Hamburg            | 3         | 0.86%   |
| Brasília          | 3         | 0.86%   |
| Austin             | 3         | 0.86%   |
| Wolfsburg          | 2         | 0.57%   |
| Warsaw             | 2         | 0.57%   |
| Vienna             | 2         | 0.57%   |
| Vancouver          | 2         | 0.57%   |
| Sunnyvale          | 2         | 0.57%   |
| Stuttgart          | 2         | 0.57%   |
| San Miguel         | 2         | 0.57%   |
| San Francisco      | 2         | 0.57%   |
| Portland           | 2         | 0.57%   |
| Paris              | 2         | 0.57%   |
| Nuremberg          | 2         | 0.57%   |
| Niterói           | 2         | 0.57%   |
| Mumbai             | 2         | 0.57%   |
| Milan              | 2         | 0.57%   |
| Lisbon             | 2         | 0.57%   |
| Kyiv               | 2         | 0.57%   |
| Kassel             | 2         | 0.57%   |
| Istanbul           | 2         | 0.57%   |
| Gurgaon            | 2         | 0.57%   |
| Dublin             | 2         | 0.57%   |
| Cologne            | 2         | 0.57%   |
| Burzaco            | 2         | 0.57%   |
| Belo Horizonte     | 2         | 0.57%   |
| Bamberg            | 2         | 0.57%   |
| Amsterdam          | 2         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 95        | 121    | 21.94%  |
| WDC                            | 44        | 47     | 10.16%  |
| Seagate                        | 44        | 47     | 10.16%  |
| Toshiba                        | 38        | 45     | 8.78%   |
| Unknown                        | 29        | 32     | 6.7%    |
| SanDisk                        | 24        | 27     | 5.54%   |
| Kingston                       | 17        | 18     | 3.93%   |
| Crucial                        | 16        | 18     | 3.7%    |
| SK hynix                       | 15        | 17     | 3.46%   |
| Intel                          | 14        | 19     | 3.23%   |
| Micron Technology              | 9         | 10     | 2.08%   |
| HGST                           | 8         | 11     | 1.85%   |
| A-DATA Technology              | 8         | 9      | 1.85%   |
| Hitachi                        | 7         | 7      | 1.62%   |
| China                          | 7         | 9      | 1.62%   |
| SPCC                           | 5         | 5      | 1.15%   |
| Apple                          | 5         | 5      | 1.15%   |
| PNY                            | 4         | 6      | 0.92%   |
| JMicron Technology             | 3         | 3      | 0.69%   |
| Unknown                        | 3         | 3      | 0.69%   |
| Micron/Crucial Technology      | 2         | 2      | 0.46%   |
| LITEON                         | 2         | 2      | 0.46%   |
| Lenovo                         | 2         | 2      | 0.46%   |
| KIOXIA                         | 2         | 2      | 0.46%   |
| Intenso                        | 2         | 3      | 0.46%   |
| Hewlett-Packard                | 2         | 1      | 0.46%   |
| Corsair                        | 2         | 3      | 0.46%   |
| VISIPRO                        | 1         | 1      | 0.23%   |
| Vaseky                         | 1         | 1      | 0.23%   |
| USB30                          | 1         | 1      | 0.23%   |
| Union Memory                   | 1         | 1      | 0.23%   |
| TO Exter                       | 1         | 1      | 0.23%   |
| Teclast                        | 1         | 2      | 0.23%   |
| SSSTC                          | 1         | 2      | 0.23%   |
| Solid State Storage Technology | 1         | 1      | 0.23%   |
| Realtek Semiconductor          | 1         | 2      | 0.23%   |
| Phison Electronics             | 1         | 1      | 0.23%   |
| Phison                         | 1         | 1      | 0.23%   |
| Patriot                        | 1         | 1      | 0.23%   |
| OWC                            | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  64GB               | 6         | 1.35%   |
| Toshiba MQ01ABD100 1TB               | 6         | 1.35%   |
| WDC WD10JPVX-22JC3T0 1TB             | 5         | 1.12%   |
| Unknown MMC Card  32GB               | 5         | 1.12%   |
| Toshiba MQ04ABF100 1TB               | 5         | 1.12%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 1.12%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 1.12%   |
| Samsung SSD 860 EVO M.2 500GB        | 5         | 1.12%   |
| Samsung SSD 860 EVO M.2 250GB        | 5         | 1.12%   |
| Samsung NVMe SSD Drive 1TB           | 5         | 1.12%   |
| SK hynix NVMe SSD Drive 256GB        | 4         | 0.9%    |
| Seagate ST9500325AS 500GB            | 4         | 0.9%    |
| SanDisk NVMe SSD Drive 512GB         | 4         | 0.9%    |
| Samsung SSD 970 EVO Plus 1TB         | 4         | 0.9%    |
| Samsung NVMe SSD Drive 512GB         | 4         | 0.9%    |
| Samsung NVMe SSD Drive 500GB         | 4         | 0.9%    |
| Unknown SD64G  64GB                  | 3         | 0.67%   |
| SPCC Solid State Disk 120GB          | 3         | 0.67%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.67%   |
| Seagate ST1000LX015-1U7172 1TB       | 3         | 0.67%   |
| Samsung SSD 980 500GB                | 3         | 0.67%   |
| Samsung SSD 970 EVO Plus 500GB       | 3         | 0.67%   |
| Samsung SSD 970 EVO 500GB            | 3         | 0.67%   |
| Samsung SSD 860 EVO 500GB            | 3         | 0.67%   |
| Samsung SSD 750 EVO 250GB            | 3         | 0.67%   |
| Samsung NVMe SSD Drive 2TB           | 3         | 0.67%   |
| Samsung NVMe SSD Drive 250GB         | 3         | 0.67%   |
| Unknown                              | 3         | 0.67%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.45%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 2         | 0.45%   |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 0.45%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 0.45%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB | 2         | 0.45%   |
| Unknown SD/MMC/MS PRO 64GB           | 2         | 0.45%   |
| Unknown MMC128  128GB                | 2         | 0.45%   |
| Unknown MMC Card  16GB               | 2         | 0.45%   |
| Toshiba MQ01ACF050 500GB             | 2         | 0.45%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.45%   |
| Seagate ST1000LM049-2GH172 1TB       | 2         | 0.45%   |
| Seagate ST1000LM048-2E7172 1TB       | 2         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 41        | 44     | 37.27%  |
| WDC                 | 25        | 27     | 22.73%  |
| Toshiba             | 25        | 28     | 22.73%  |
| HGST                | 8         | 11     | 7.27%   |
| Hitachi             | 7         | 7      | 6.36%   |
| Unknown             | 2         | 2      | 1.82%   |
| Samsung Electronics | 1         | 1      | 0.91%   |
| Fujitsu             | 1         | 1      | 0.91%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 44        | 55     | 27.33%  |
| SanDisk             | 16        | 16     | 9.94%   |
| Crucial             | 15        | 17     | 9.32%   |
| Kingston            | 13        | 13     | 8.07%   |
| WDC                 | 7         | 7      | 4.35%   |
| China               | 7         | 9      | 4.35%   |
| A-DATA Technology   | 6         | 7      | 3.73%   |
| SPCC                | 5         | 5      | 3.11%   |
| Micron Technology   | 5         | 6      | 3.11%   |
| PNY                 | 4         | 6      | 2.48%   |
| Intel               | 4         | 4      | 2.48%   |
| Apple               | 4         | 4      | 2.48%   |
| Toshiba             | 3         | 3      | 1.86%   |
| Seagate             | 2         | 2      | 1.24%   |
| LITEON              | 2         | 2      | 1.24%   |
| JMicron Technology  | 2         | 2      | 1.24%   |
| Intenso             | 2         | 3      | 1.24%   |
| VISIPRO             | 1         | 1      | 0.62%   |
| Vaseky              | 1         | 1      | 0.62%   |
| USB30               | 1         | 1      | 0.62%   |
| Unknown             | 1         | 1      | 0.62%   |
| Union Memory        | 1         | 1      | 0.62%   |
| TO Exter            | 1         | 1      | 0.62%   |
| Teclast             | 1         | 2      | 0.62%   |
| SK hynix            | 1         | 1      | 0.62%   |
| Patriot             | 1         | 1      | 0.62%   |
| OWC                 | 1         | 1      | 0.62%   |
| Netac               | 1         | 1      | 0.62%   |
| LITEONIT            | 1         | 1      | 0.62%   |
| KingSpec            | 1         | 1      | 0.62%   |
| Hewlett-Packard     | 1         | 1      | 0.62%   |
| Gigabyte Technology | 1         | 1      | 0.62%   |
| FORESEE             | 1         | 1      | 0.62%   |
| Dogfish             | 1         | 1      | 0.62%   |
| Corsair             | 1         | 2      | 0.62%   |
| BIWIN               | 1         | 1      | 0.62%   |
| Unknown             | 1         | 1      | 0.62%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 147       | 183    | 35.68%  |
| NVMe    | 124       | 159    | 30.1%   |
| HDD     | 107       | 121    | 25.97%  |
| MMC     | 28        | 33     | 6.8%    |
| Unknown | 6         | 5      | 1.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 220       | 293    | 56.7%   |
| NVMe | 124       | 159    | 31.96%  |
| MMC  | 28        | 33     | 7.22%   |
| SAS  | 16        | 16     | 4.12%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 165       | 200    | 65.48%  |
| 0.51-1.0   | 76        | 91     | 30.16%  |
| 1.01-2.0   | 8         | 10     | 3.17%   |
| 4.01-10.0  | 2         | 2      | 0.79%   |
| 3.01-4.0   | 1         | 1      | 0.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 109       | 31.41%  |
| 101-250        | 103       | 29.68%  |
| 501-1000       | 46        | 13.26%  |
| 51-100         | 31        | 8.93%   |
| 1001-2000      | 19        | 5.48%   |
| 21-50          | 18        | 5.19%   |
| 2001-3000      | 7         | 2.02%   |
| 1-20           | 7         | 2.02%   |
| More than 3000 | 4         | 1.15%   |
| Unknown        | 3         | 0.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 113       | 31.65%  |
| 21-50          | 71        | 19.89%  |
| 101-250        | 71        | 19.89%  |
| 51-100         | 48        | 13.45%  |
| 251-500        | 29        | 8.12%   |
| 501-1000       | 15        | 4.2%    |
| 1001-2000      | 5         | 1.4%    |
| Unknown        | 3         | 0.84%   |
| More than 3000 | 2         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB               | 2         | 2      | 9.52%   |
| WDC WD6400BPVT-60HXZT3 640GB         | 1         | 1      | 4.76%   |
| WDC WD5000BPVT-00HXZT1 500GB         | 1         | 1      | 4.76%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 4.76%   |
| Toshiba MK5055GSX 500GB              | 1         | 1      | 4.76%   |
| Toshiba MK3265GSXN 320GB             | 1         | 1      | 4.76%   |
| Toshiba MK2561GSYN 250GB             | 1         | 1      | 4.76%   |
| Seagate ST9750420AS 752GB            | 1         | 1      | 4.76%   |
| Seagate ST9500423AS 500GB            | 1         | 1      | 4.76%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 4.76%   |
| Seagate ST500LX012-1LM162-SSHD 500GB | 1         | 1      | 4.76%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 4.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 1      | 4.76%   |
| PNY SSD2SC120G3LC709B121-460I 120GB  | 1         | 1      | 4.76%   |
| Kingston SNS4151S316G 16GB SSD       | 1         | 1      | 4.76%   |
| HGST HTS725032A7E630 320GB           | 1         | 2      | 4.76%   |
| HGST HTS541075A9E680 752GB           | 1         | 1      | 4.76%   |
| Crucial CT500P1SSD8 500GB            | 1         | 1      | 4.76%   |
| China SSD 256GB                      | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 7         | 7      | 33.33%  |
| Seagate  | 6         | 6      | 28.57%  |
| WDC      | 2         | 2      | 9.52%   |
| HGST     | 2         | 3      | 9.52%   |
| PNY      | 1         | 1      | 4.76%   |
| Kingston | 1         | 1      | 4.76%   |
| Crucial  | 1         | 1      | 4.76%   |
| China    | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 7         | 7      | 41.18%  |
| Seagate | 6         | 6      | 35.29%  |
| WDC     | 2         | 2      | 11.76%  |
| HGST    | 2         | 3      | 11.76%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 18     | 80.95%  |
| SSD  | 3         | 3      | 14.29%  |
| NVMe | 1         | 1      | 4.76%   |

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
| Detected | 202       | 286    | 55.65%  |
| Works    | 141       | 193    | 38.84%  |
| Malfunc  | 20        | 22     | 5.51%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 243       | 60.9%   |
| Samsung Electronics            | 55        | 13.78%  |
| AMD                            | 30        | 7.52%   |
| SanDisk                        | 19        | 4.76%   |
| SK hynix                       | 12        | 3.01%   |
| Toshiba America Info Systems   | 9         | 2.26%   |
| Micron Technology              | 4         | 1%      |
| Kingston Technology Company    | 4         | 1%      |
| Phison Electronics             | 3         | 0.75%   |
| Micron/Crucial Technology      | 3         | 0.75%   |
| KIOXIA                         | 3         | 0.75%   |
| Solid State Storage Technology | 2         | 0.5%    |
| Realtek Semiconductor          | 2         | 0.5%    |
| Nvidia                         | 2         | 0.5%    |
| Lenovo                         | 2         | 0.5%    |
| ADATA Technology               | 2         | 0.5%    |
| Union Memory (Shenzhen)        | 1         | 0.25%   |
| Silicon Motion                 | 1         | 0.25%   |
| Shenzhen Longsys Electronics   | 1         | 0.25%   |
| Apple                          | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 34        | 8.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 33        | 7.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 29        | 6.9%    |
| AMD FCH SATA Controller [AHCI mode]                                              | 27        | 6.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 22        | 5.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 15        | 3.57%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 14        | 3.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 2.86%   |
| Samsung NVMe SSD Controller 980                                                  | 10        | 2.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 2.38%   |
| Intel Comet Lake SATA AHCI Controller                                            | 10        | 2.38%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 9         | 2.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9         | 2.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 8         | 1.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 8         | 1.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 1.67%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 7         | 1.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6         | 1.43%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 1.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 1.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 1.43%   |
| Intel SSD 660P Series                                                            | 5         | 1.19%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 4         | 0.95%   |
| SK hynix Non-Volatile memory controller                                          | 4         | 0.95%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 0.95%   |
| SanDisk PC SN520 NVMe SSD                                                        | 4         | 0.95%   |
| Micron Non-Volatile memory controller                                            | 4         | 0.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 0.95%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 0.95%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.71%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.71%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 3         | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 0.71%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 3         | 0.71%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 2         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 249       | 60.88%  |
| NVMe | 126       | 30.81%  |
| RAID | 22        | 5.38%   |
| IDE  | 12        | 2.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 298       | 86.88%  |
| AMD    | 45        | 13.12%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 17        | 4.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 11        | 3.21%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 2.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 9         | 2.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.75%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 1.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 1.46%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.46%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 1.46%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 1.46%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.46%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 1.46%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.46%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.17%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 1.17%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 1.17%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 4         | 1.17%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.17%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.17%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 1.17%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.87%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 0.87%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 0.87%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 0.87%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 0.87%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.87%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 0.87%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.87%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.87%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.87%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.87%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 0.87%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.87%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 0.87%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 0.58%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz        | 2         | 0.58%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 2         | 0.58%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.58%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 123       | 35.86%  |
| Intel Core i5           | 78        | 22.74%  |
| Intel Core i3           | 23        | 6.71%   |
| Other                   | 22        | 6.41%   |
| Intel Celeron           | 15        | 4.37%   |
| AMD Ryzen 5             | 15        | 4.37%   |
| Intel Core 2 Duo        | 11        | 3.21%   |
| AMD Ryzen 7             | 11        | 3.21%   |
| Intel Pentium           | 7         | 2.04%   |
| Intel Atom              | 6         | 1.75%   |
| Intel Pentium Silver    | 4         | 1.17%   |
| AMD A8                  | 4         | 1.17%   |
| AMD E                   | 3         | 0.87%   |
| AMD A6                  | 3         | 0.87%   |
| Intel Pentium Dual      | 2         | 0.58%   |
| Intel Genuine           | 2         | 0.58%   |
| Intel Core i9           | 2         | 0.58%   |
| AMD Turion 64 X2 Mobile | 2         | 0.58%   |
| AMD Ryzen 9             | 2         | 0.58%   |
| Intel Pentium Dual-Core | 1         | 0.29%   |
| Intel Core m5           | 1         | 0.29%   |
| Intel Core m3           | 1         | 0.29%   |
| AMD Ryzen 3             | 1         | 0.29%   |
| AMD Quad-Core           | 1         | 0.29%   |
| AMD E1                  | 1         | 0.29%   |
| AMD Athlon II           | 1         | 0.29%   |
| AMD A10                 | 1         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 149       | 43.44%  |
| 2      | 140       | 40.82%  |
| 6      | 28        | 8.16%   |
| 8      | 21        | 6.12%   |
| 1      | 2         | 0.58%   |
| 16     | 1         | 0.29%   |
| 14     | 1         | 0.29%   |
| 10     | 1         | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 343       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 265       | 77.26%  |
| 1      | 78        | 22.74%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 342       | 99.71%  |
| 32-bit         | 1         | 0.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 94        | 26.78%  |
| 0x206a7    | 23        | 6.55%   |
| 0x806ec    | 20        | 5.7%    |
| 0x306a9    | 19        | 5.41%   |
| 0x906ea    | 14        | 3.99%   |
| 0x806ea    | 13        | 3.7%    |
| 0x806c1    | 11        | 3.13%   |
| 0x40651    | 11        | 3.13%   |
| 0x806e9    | 10        | 2.85%   |
| 0x406e3    | 9         | 2.56%   |
| 0x306d4    | 9         | 2.56%   |
| 0x306c3    | 9         | 2.56%   |
| 0x806eb    | 8         | 2.28%   |
| 0xa0652    | 7         | 1.99%   |
| 0x906e9    | 7         | 1.99%   |
| 0x20655    | 5         | 1.42%   |
| 0x08600106 | 5         | 1.42%   |
| 0x08600103 | 5         | 1.42%   |
| 0x1067a    | 4         | 1.14%   |
| 0x10676    | 4         | 1.14%   |
| 0xa0660    | 3         | 0.85%   |
| 0x806d1    | 3         | 0.85%   |
| 0x706e5    | 3         | 0.85%   |
| 0x706a8    | 3         | 0.85%   |
| 0x506e3    | 3         | 0.85%   |
| 0x406c3    | 3         | 0.85%   |
| 0x30678    | 3         | 0.85%   |
| 0x0a50000c | 3         | 0.85%   |
| 0x08108109 | 3         | 0.85%   |
| 0x0810100b | 3         | 0.85%   |
| 0x05000119 | 3         | 0.85%   |
| 0x706a1    | 2         | 0.57%   |
| 0x6fd      | 2         | 0.57%   |
| 0x506c9    | 2         | 0.57%   |
| 0x20652    | 2         | 0.57%   |
| 0x106e5    | 2         | 0.57%   |
| 0x08600104 | 2         | 0.57%   |
| 0x08108102 | 2         | 0.57%   |
| 0x0700010f | 2         | 0.57%   |
| 0x906ed    | 1         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 98        | 28.57%  |
| SandyBridge      | 27        | 7.87%   |
| IvyBridge        | 27        | 7.87%   |
| Haswell          | 23        | 6.71%   |
| Skylake          | 17        | 4.96%   |
| Zen 2            | 16        | 4.66%   |
| TigerLake        | 15        | 4.37%   |
| CometLake        | 14        | 4.08%   |
| Silvermont       | 12        | 3.5%    |
| Broadwell        | 12        | 3.5%    |
| Penryn           | 11        | 3.21%   |
| IceLake          | 9         | 2.62%   |
| Goldmont plus    | 9         | 2.62%   |
| Westmere         | 8         | 2.33%   |
| Zen+             | 5         | 1.46%   |
| Unknown          | 5         | 1.46%   |
| Core             | 4         | 1.17%   |
| Zen 3            | 3         | 0.87%   |
| Zen              | 3         | 0.87%   |
| Puma             | 3         | 0.87%   |
| Jaguar           | 3         | 0.87%   |
| Goldmont         | 3         | 0.87%   |
| Bobcat           | 3         | 0.87%   |
| Nehalem          | 2         | 0.58%   |
| K8 Hammer        | 2         | 0.58%   |
| Excavator        | 2         | 0.58%   |
| Tremont          | 1         | 0.29%   |
| Piledriver       | 1         | 0.29%   |
| P6               | 1         | 0.29%   |
| K10 Llano        | 1         | 0.29%   |
| K10              | 1         | 0.29%   |
| Bonnell          | 1         | 0.29%   |
| Alderlake Hybrid | 1         | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 278       | 62.47%  |
| Nvidia | 102       | 22.92%  |
| AMD    | 65        | 14.61%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 25        | 5.52%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 25        | 5.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 24        | 5.3%    |
| Intel UHD Graphics 620                                                                   | 22        | 4.86%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 3.31%   |
| AMD Renoir                                                                               | 15        | 3.31%   |
| Intel HD Graphics 620                                                                    | 13        | 2.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 2.87%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 2.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 2.43%   |
| Intel HD Graphics 5500                                                                   | 10        | 2.21%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 1.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 1.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.99%   |
| Intel HD Graphics 630                                                                    | 8         | 1.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.55%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 6         | 1.32%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.32%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.1%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 1.1%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 1.1%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 5         | 1.1%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.1%    |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.88%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 0.88%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.88%   |
| Intel HD Graphics 530                                                                    | 4         | 0.88%   |
| Intel Comet Lake UHD Graphics                                                            | 4         | 0.88%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.88%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 3         | 0.66%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.66%   |
| Intel HD Graphics 500                                                                    | 3         | 0.66%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 181       | 52.77%  |
| Intel + Nvidia | 79        | 23.03%  |
| 1 x AMD        | 38        | 11.08%  |
| 1 x Nvidia     | 17        | 4.96%   |
| Intel + AMD    | 17        | 4.96%   |
| AMD + Nvidia   | 6         | 1.75%   |
| 2 x AMD        | 4         | 1.17%   |
| Other          | 1         | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 271       | 78.32%  |
| Proprietary | 68        | 19.65%  |
| Unknown     | 7         | 2.02%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 240       | 69.16%  |
| 1.01-2.0   | 36        | 10.37%  |
| 0.01-0.5   | 20        | 5.76%   |
| 0.51-1.0   | 17        | 4.9%    |
| 3.01-4.0   | 16        | 4.61%   |
| 5.01-6.0   | 9         | 2.59%   |
| 7.01-8.0   | 8         | 2.31%   |
| 2.01-3.0   | 1         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 78        | 18.98%  |
| AU Optronics            | 68        | 16.55%  |
| BOE                     | 54        | 13.14%  |
| LG Display              | 48        | 11.68%  |
| Samsung Electronics     | 36        | 8.76%   |
| Dell                    | 14        | 3.41%   |
| Goldstar                | 13        | 3.16%   |
| Sharp                   | 11        | 2.68%   |
| Chi Mei Optoelectronics | 11        | 2.68%   |
| Apple                   | 10        | 2.43%   |
| Lenovo                  | 7         | 1.7%    |
| PANDA                   | 6         | 1.46%   |
| Hewlett-Packard         | 6         | 1.46%   |
| BenQ                    | 6         | 1.46%   |
| Acer                    | 5         | 1.22%   |
| Philips                 | 4         | 0.97%   |
| Ancor Communications    | 4         | 0.97%   |
| LGD                     | 3         | 0.73%   |
| InfoVision              | 3         | 0.73%   |
| Unknown (AAA)           | 2         | 0.49%   |
| Fujitsu Siemens         | 2         | 0.49%   |
| ASUSTek Computer        | 2         | 0.49%   |
| AOC                     | 2         | 0.49%   |
| Vestel Elektronik       | 1         | 0.24%   |
| UPD                     | 1         | 0.24%   |
| Unknown                 | 1         | 0.24%   |
| Sony                    | 1         | 0.24%   |
| MStar                   | 1         | 0.24%   |
| LG Philips              | 1         | 0.24%   |
| LaCie                   | 1         | 0.24%   |
| KTC                     | 1         | 0.24%   |
| JDI                     | 1         | 0.24%   |
| InnoLux Display         | 1         | 0.24%   |
| Iiyama                  | 1         | 0.24%   |
| IBM                     | 1         | 0.24%   |
| GDH                     | 1         | 0.24%   |
| Eizo                    | 1         | 0.24%   |
| Daewoo                  | 1         | 0.24%   |
| CSO                     | 1         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 6         | 1.44%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch         | 6         | 1.44%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 5         | 1.2%    |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                    | 4         | 0.96%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.72%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 3         | 0.72%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch           | 3         | 0.72%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.72%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 2         | 0.48%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch     | 2         | 0.48%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 2         | 0.48%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.48%   |
| LGD LCD Monitor 1920x1080                                                | 2         | 0.48%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch             | 2         | 0.48%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 2         | 0.48%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 2         | 0.48%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch              | 2         | 0.48%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 2         | 0.48%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 0.48%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch              | 2         | 0.48%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 2         | 0.48%   |
| Dell U3415W DELA0AA 3440x1440 798x335mm 34.1-inch                        | 2         | 0.48%   |
| Dell U2415 DELA0BA 1920x1200 520x320mm 24.0-inch                         | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch         | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch         | 2         | 0.48%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 2         | 0.48%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.48%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.48%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                     | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 2         | 0.48%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 2         | 0.48%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 165       | 43.42%  |
| 1366x768 (WXGA)    | 107       | 28.16%  |
| 2560x1440 (QHD)    | 21        | 5.53%   |
| 1600x900 (HD+)     | 17        | 4.47%   |
| 3840x2160 (4K)     | 12        | 3.16%   |
| 1280x800 (WXGA)    | 12        | 3.16%   |
| 1920x1200 (WUXGA)  | 6         | 1.58%   |
| 1440x900 (WXGA+)   | 6         | 1.58%   |
| 3440x1440          | 4         | 1.05%   |
| 2880x1800          | 4         | 1.05%   |
| 1680x1050 (WSXGA+) | 4         | 1.05%   |
| 3200x1800 (QHD+)   | 3         | 0.79%   |
| 2560x1600          | 2         | 0.53%   |
| 2560x1080          | 2         | 0.53%   |
| 2160x1440          | 2         | 0.53%   |
| 1360x768           | 2         | 0.53%   |
| 1280x1024 (SXGA)   | 2         | 0.53%   |
| 3840x2400          | 1         | 0.26%   |
| 3840x1100          | 1         | 0.26%   |
| 3840x1080          | 1         | 0.26%   |
| 3456x2160          | 1         | 0.26%   |
| 3000x2000          | 1         | 0.26%   |
| 2256x1504          | 1         | 0.26%   |
| 1920x1280          | 1         | 0.26%   |
| 1600x1200          | 1         | 0.26%   |
| 1280x768           | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 157       | 37.83%  |
| 13      | 73        | 17.59%  |
| 14      | 48        | 11.57%  |
| 17      | 24        | 5.78%   |
| 24      | 20        | 4.82%   |
| 27      | 16        | 3.86%   |
| 23      | 13        | 3.13%   |
| 11      | 11        | 2.65%   |
| 21      | 7         | 1.69%   |
| 34      | 6         | 1.45%   |
| Unknown | 6         | 1.45%   |
| 31      | 5         | 1.2%    |
| 12      | 5         | 1.2%    |
| 19      | 4         | 0.96%   |
| 40      | 3         | 0.72%   |
| 84      | 2         | 0.48%   |
| 48      | 2         | 0.48%   |
| 32      | 2         | 0.48%   |
| 22      | 2         | 0.48%   |
| 18      | 2         | 0.48%   |
| 72      | 1         | 0.24%   |
| 60      | 1         | 0.24%   |
| 54      | 1         | 0.24%   |
| 44      | 1         | 0.24%   |
| 29      | 1         | 0.24%   |
| 20      | 1         | 0.24%   |
| 10      | 1         | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 239       | 58.29%  |
| 201-300     | 51        | 12.44%  |
| 501-600     | 44        | 10.73%  |
| 351-400     | 30        | 7.32%   |
| 401-500     | 15        | 3.66%   |
| 701-800     | 8         | 1.95%   |
| 601-700     | 6         | 1.46%   |
| Unknown     | 6         | 1.46%   |
| 1001-1500   | 4         | 0.98%   |
| 801-900     | 3         | 0.73%   |
| 1501-2000   | 3         | 0.73%   |
| 901-1000    | 1         | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 297       | 82.73%  |
| 16/10   | 40        | 11.14%  |
| 3/2     | 6         | 1.67%   |
| 21/9    | 6         | 1.67%   |
| Unknown | 5         | 1.39%   |
| 5/4     | 2         | 0.56%   |
| 4/3     | 1         | 0.28%   |
| 32/9    | 1         | 0.28%   |
| 3.40    | 1         | 0.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 156       | 37.77%  |
| 81-90          | 94        | 22.76%  |
| 201-250        | 32        | 7.75%   |
| 71-80          | 26        | 6.3%    |
| 121-130        | 20        | 4.84%   |
| 301-350        | 16        | 3.87%   |
| 351-500        | 14        | 3.39%   |
| 51-60          | 12        | 2.91%   |
| 251-300        | 8         | 1.94%   |
| More than 1000 | 6         | 1.45%   |
| Unknown        | 6         | 1.45%   |
| 61-70          | 5         | 1.21%   |
| 151-200        | 5         | 1.21%   |
| 501-1000       | 5         | 1.21%   |
| 131-140        | 4         | 0.97%   |
| 141-150        | 2         | 0.48%   |
| 41-50          | 1         | 0.24%   |
| 91-100         | 1         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 152       | 37.53%  |
| 101-120       | 124       | 30.62%  |
| 51-100        | 66        | 16.3%   |
| 161-240       | 31        | 7.65%   |
| More than 240 | 17        | 4.2%    |
| 1-50          | 9         | 2.22%   |
| Unknown       | 6         | 1.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 272       | 77.27%  |
| 2     | 63        | 17.9%   |
| 3     | 10        | 2.84%   |
| 0     | 7         | 1.99%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 205       | 36.67%  |
| Realtek Semiconductor                 | 184       | 32.92%  |
| Qualcomm Atheros                      | 79        | 14.13%  |
| Broadcom                              | 27        | 4.83%   |
| Broadcom Limited                      | 13        | 2.33%   |
| Marvell Technology Group              | 7         | 1.25%   |
| Ralink                                | 5         | 0.89%   |
| Hewlett-Packard                       | 5         | 0.89%   |
| MediaTek                              | 3         | 0.54%   |
| Huawei Technologies                   | 3         | 0.54%   |
| ASIX Electronics                      | 3         | 0.54%   |
| Sierra Wireless                       | 2         | 0.36%   |
| Nvidia                                | 2         | 0.36%   |
| Lenovo                                | 2         | 0.36%   |
| JMicron Technology                    | 2         | 0.36%   |
| DisplayLink                           | 2         | 0.36%   |
| Xiaomi                                | 1         | 0.18%   |
| TP-Link                               | 1         | 0.18%   |
| Samsung Electronics                   | 1         | 0.18%   |
| Ralink Technology                     | 1         | 0.18%   |
| Qualcomm Atheros Communications       | 1         | 0.18%   |
| Novatek Microelectronics              | 1         | 0.18%   |
| NetGear                               | 1         | 0.18%   |
| Google                                | 1         | 0.18%   |
| Ericsson Business Mobile Networks     | 1         | 0.18%   |
| Edimax Technology                     | 1         | 0.18%   |
| Dell                                  | 1         | 0.18%   |
| BUFFALO                               | 1         | 0.18%   |
| ASUSTek Computer                      | 1         | 0.18%   |
| Apple                                 | 1         | 0.18%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 112       | 16.84%  |
| Intel Wi-Fi 6 AX200                                               | 34        | 5.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 4.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26        | 3.91%   |
| Intel Wireless 8265 / 8275                                        | 22        | 3.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 17        | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 2.41%   |
| Intel Wireless-AC 9260                                            | 14        | 2.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 1.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 1.65%   |
| Intel Wireless 7265                                               | 11        | 1.65%   |
| Intel Wireless 8260                                               | 10        | 1.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 1.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 10        | 1.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.35%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                     | 7         | 1.05%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 0.9%    |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 0.9%    |
| Intel Wireless 7260                                               | 6         | 0.9%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.9%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.75%   |
| Intel Wireless 3165                                               | 5         | 0.75%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5         | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.6%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 0.6%    |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.6%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 4         | 0.6%    |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 0.6%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.6%    |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 198       | 55.62%  |
| Qualcomm Atheros                      | 63        | 17.7%   |
| Realtek Semiconductor                 | 45        | 12.64%  |
| Broadcom                              | 22        | 6.18%   |
| Broadcom Limited                      | 9         | 2.53%   |
| Ralink                                | 5         | 1.4%    |
| MediaTek                              | 3         | 0.84%   |
| Sierra Wireless                       | 2         | 0.56%   |
| TP-Link                               | 1         | 0.28%   |
| Ralink Technology                     | 1         | 0.28%   |
| Qualcomm Atheros Communications       | 1         | 0.28%   |
| NetGear                               | 1         | 0.28%   |
| Hewlett-Packard                       | 1         | 0.28%   |
| Edimax Technology                     | 1         | 0.28%   |
| BUFFALO                               | 1         | 0.28%   |
| ASUSTek Computer                      | 1         | 0.28%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 34        | 9.52%   |
| Intel Wireless 8265 / 8275                                     | 22        | 6.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 17        | 4.76%   |
| Intel Wireless-AC 9260                                         | 14        | 3.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 3.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 3.08%   |
| Intel Wireless 7265                                            | 11        | 3.08%   |
| Intel Wireless 8260                                            | 10        | 2.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 10        | 2.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 10        | 2.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 2.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 2.52%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 2.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 7         | 1.96%   |
| Broadcom BCM43142 802.11b/g/n                                  | 7         | 1.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 1.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 1.68%   |
| Intel Wireless 7260                                            | 6         | 1.68%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 1.68%   |
| Intel Wireless 3165                                            | 5         | 1.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5         | 1.4%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 1.12%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 1.12%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.12%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 4         | 1.12%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.12%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 1.12%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.84%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 0.84%   |
| Realtek 802.11n WLAN Adapter                                   | 3         | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.84%   |
| Intel WiFi Link 5100                                           | 3         | 0.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 0.84%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.84%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 0.84%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 0.84%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 3         | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 166       | 57.24%  |
| Intel                    | 62        | 21.38%  |
| Qualcomm Atheros         | 23        | 7.93%   |
| Broadcom                 | 11        | 3.79%   |
| Marvell Technology Group | 7         | 2.41%   |
| Broadcom Limited         | 4         | 1.38%   |
| ASIX Electronics         | 3         | 1.03%   |
| Nvidia                   | 2         | 0.69%   |
| Lenovo                   | 2         | 0.69%   |
| JMicron Technology       | 2         | 0.69%   |
| Hewlett-Packard          | 2         | 0.69%   |
| DisplayLink              | 2         | 0.69%   |
| Xiaomi                   | 1         | 0.34%   |
| Samsung Electronics      | 1         | 0.34%   |
| Google                   | 1         | 0.34%   |
| Apple                    | 1         | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 112       | 37.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 27        | 9%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 26        | 8.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 16        | 5.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 2.33%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 2%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 5         | 1.67%   |
| Intel Ethernet Connection (6) I219-V                                           | 5         | 1.67%   |
| Intel Ethernet Connection (4) I219-LM                                          | 5         | 1.67%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 1.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 3         | 1%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 1%      |
| Intel Ethernet Connection I218-LM                                              | 3         | 1%      |
| Intel Ethernet Connection (6) I219-LM                                          | 3         | 1%      |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1%      |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 1%      |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1%      |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.67%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.67%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 0.67%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.67%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.67%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.67%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.67%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.67%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 2         | 0.67%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.33%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.33%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.33%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.33%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.33%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 339       | 54.5%   |
| Ethernet | 275       | 44.21%  |
| Modem    | 8         | 1.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 292       | 80.66%  |
| Ethernet | 70        | 19.34%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 256       | 74.42%  |
| 1     | 78        | 22.67%  |
| 0     | 9         | 2.62%   |
| 3     | 1         | 0.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 287       | 82.47%  |
| Yes  | 61        | 17.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 158       | 54.48%  |
| Qualcomm Atheros Communications | 29        | 10%     |
| Realtek Semiconductor           | 22        | 7.59%   |
| Broadcom                        | 16        | 5.52%   |
| Foxconn / Hon Hai               | 10        | 3.45%   |
| Apple                           | 10        | 3.45%   |
| Lite-On Technology              | 9         | 3.1%    |
| IMC Networks                    | 8         | 2.76%   |
| Dell                            | 7         | 2.41%   |
| Hewlett-Packard                 | 5         | 1.72%   |
| Realtek                         | 4         | 1.38%   |
| Ralink                          | 3         | 1.03%   |
| Toshiba                         | 2         | 0.69%   |
| Foxconn International           | 2         | 0.69%   |
| Cambridge Silicon Radio         | 2         | 0.69%   |
| Unknown                         | 1         | 0.34%   |
| Integrated System Solution      | 1         | 0.34%   |
| Belkin Components               | 1         | 0.34%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 57        | 19.66%  |
| Intel AX200 Bluetooth                                                               | 32        | 11.03%  |
| Intel AX201 Bluetooth                                                               | 24        | 8.28%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 6.21%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 16        | 5.52%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 14        | 4.83%   |
| Realtek Bluetooth Radio                                                             | 12        | 4.14%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 2.07%   |
| Dell DW375 Bluetooth Module                                                         | 6         | 2.07%   |
| Apple Bluetooth Host Controller                                                     | 6         | 2.07%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 1.72%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 1.38%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 1.38%   |
| Realtek Bluetooth Radio                                                             | 4         | 1.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 1.38%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 1.38%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 1.38%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 1.03%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.03%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 1.03%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.69%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.69%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.69%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.69%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.69%   |
| Intel AX210 Bluetooth                                                               | 2         | 0.69%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.69%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 0.69%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.69%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.69%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.69%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.69%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.69%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 0.69%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.69%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.69%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.69%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 0.69%   |
| Apple Bluetooth HCI                                                                 | 2         | 0.69%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 291       | 67.52%  |
| Nvidia                 | 55        | 12.76%  |
| AMD                    | 52        | 12.06%  |
| Realtek Semiconductor  | 7         | 1.62%   |
| GN Netcom              | 3         | 0.7%    |
| Plantronics            | 2         | 0.46%   |
| Logitech               | 2         | 0.46%   |
| Kingston Technology    | 2         | 0.46%   |
| C-Media Electronics    | 2         | 0.46%   |
| XMOS                   | 1         | 0.23%   |
| Samson Technologies    | 1         | 0.23%   |
| Razer USA              | 1         | 0.23%   |
| No brand               | 1         | 0.23%   |
| LINE TECH INDUSTRIAL   | 1         | 0.23%   |
| Lenovo                 | 1         | 0.23%   |
| JMTek                  | 1         | 0.23%   |
| Hewlett-Packard        | 1         | 0.23%   |
| GYROCOM C&C            | 1         | 0.23%   |
| Generalplus Technology | 1         | 0.23%   |
| DSEA A/S               | 1         | 0.23%   |
| Conexant Systems       | 1         | 0.23%   |
| CMX Systems            | 1         | 0.23%   |
| Cambridge Audio        | 1         | 0.23%   |
| Apple                  | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 48        | 9.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 30        | 5.98%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 28        | 5.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 25        | 4.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 24        | 4.78%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 16        | 3.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 15        | 2.99%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 15        | 2.99%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 2.59%   |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 2.59%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 2.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 2.39%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 2.39%   |
| Intel Comet Lake PCH cAVS                                                                         | 10        | 1.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 1.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 10        | 1.99%   |
| AMD FCH Azalia Controller                                                                         | 10        | 1.99%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 9         | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 1.79%   |
| Intel CM238 HD Audio Controller                                                                   | 9         | 1.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 1.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 1.59%   |
| Realtek Semiconductor USB Audio                                                                   | 7         | 1.39%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.39%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 6         | 1.2%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 1.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.2%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 5         | 1%      |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 1%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1%      |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 0.8%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.8%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 0.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.6%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.6%    |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 83        | 34.73%  |
| SK hynix            | 53        | 22.18%  |
| Micron Technology   | 26        | 10.88%  |
| Kingston            | 17        | 7.11%   |
| Ramaxel Technology  | 11        | 4.6%    |
| Unknown             | 10        | 4.18%   |
| Crucial             | 10        | 4.18%   |
| Unknown (ABCD)      | 4         | 1.67%   |
| Corsair             | 3         | 1.26%   |
| A-DATA Technology   | 3         | 1.26%   |
| Unknown             | 3         | 1.26%   |
| Teikon              | 2         | 0.84%   |
| Smart               | 2         | 0.84%   |
| Elpida              | 2         | 0.84%   |
| Smart Brazil        | 1         | 0.42%   |
| PNY                 | 1         | 0.42%   |
| Patriot             | 1         | 0.42%   |
| Nanya Technology    | 1         | 0.42%   |
| Kingmax             | 1         | 0.42%   |
| Goldkey             | 1         | 0.42%   |
| fef5                | 1         | 0.42%   |
| Cors                | 1         | 0.42%   |
| ASint Technology    | 1         | 0.42%   |
| 8945000080AD        | 1         | 0.42%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 8         | 3.14%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 2.35%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 1.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 1.96%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.96%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 1.96%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 1.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.57%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 1.57%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 1.57%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 3         | 1.18%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 1.18%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 1.18%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 1.18%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 1.18%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 3         | 1.18%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4096MB SODIMM DDR4 2667MT/s     | 3         | 1.18%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 1.18%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 3         | 1.18%   |
| Unknown                                                          | 3         | 1.18%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                    | 2         | 0.78%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.78%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.78%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.78%   |
| SK hynix RAM HMT351S6CFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.78%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 2         | 0.78%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.78%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 2         | 0.78%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 2         | 0.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.78%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.78%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.78%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.78%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s        | 2         | 0.78%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.78%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                   | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 107       | 52.45%  |
| DDR3    | 66        | 32.35%  |
| LPDDR4  | 11        | 5.39%   |
| LPDDR3  | 10        | 4.9%    |
| SDRAM   | 3         | 1.47%   |
| DDR2    | 3         | 1.47%   |
| Unknown | 3         | 1.47%   |
| DDR     | 1         | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 179       | 89.5%   |
| Row Of Chips | 18        | 9%      |
| Unknown      | 2         | 1%      |
| Chip         | 1         | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 82        | 37.44%  |
| 4096  | 72        | 32.88%  |
| 16384 | 33        | 15.07%  |
| 2048  | 15        | 6.85%   |
| 32768 | 13        | 5.94%   |
| 1024  | 4         | 1.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 59        | 25.99%  |
| 1600    | 46        | 20.26%  |
| 3200    | 32        | 14.1%   |
| 2400    | 19        | 8.37%   |
| 2133    | 19        | 8.37%   |
| 1333    | 10        | 4.41%   |
| 1334    | 9         | 3.96%   |
| 3266    | 5         | 2.2%    |
| 1067    | 5         | 2.2%    |
| Unknown | 4         | 1.76%   |
| 8400    | 3         | 1.32%   |
| 4267    | 3         | 1.32%   |
| 4199    | 3         | 1.32%   |
| 1867    | 3         | 1.32%   |
| 667     | 3         | 1.32%   |
| 4266    | 1         | 0.44%   |
| 3733    | 1         | 0.44%   |
| 1066    | 1         | 0.44%   |
| 533     | 1         | 0.44%   |

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
| Chicony Electronics                    | 90        | 29.22%  |
| Acer                                   | 30        | 9.74%   |
| Sunplus Innovation Technology          | 28        | 9.09%   |
| IMC Networks                           | 28        | 9.09%   |
| Realtek Semiconductor                  | 26        | 8.44%   |
| Microdia                               | 22        | 7.14%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 3.57%   |
| Syntek                                 | 10        | 3.25%   |
| Suyin                                  | 10        | 3.25%   |
| Apple                                  | 10        | 3.25%   |
| Quanta                                 | 9         | 2.92%   |
| Silicon Motion                         | 6         | 1.95%   |
| Lite-On Technology                     | 4         | 1.3%    |
| Ricoh                                  | 3         | 0.97%   |
| Alcor Micro                            | 3         | 0.97%   |
| Luxvisions Innotech Limited            | 2         | 0.65%   |
| Logitech                               | 2         | 0.65%   |
| Unknown                                | 2         | 0.65%   |
| Z-Star Microelectronics                | 1         | 0.32%   |
| USB Camera                             | 1         | 0.32%   |
| Sonix Technology                       | 1         | 0.32%   |
| Samsung Electronics                    | 1         | 0.32%   |
| Primax Electronics                     | 1         | 0.32%   |
| Polycom                                | 1         | 0.32%   |
| LG Electronics                         | 1         | 0.32%   |
| Importek                               | 1         | 0.32%   |
| Generalplus Technology                 | 1         | 0.32%   |
| DJJHFA1BIF5595                         | 1         | 0.32%   |
| Denron                                 | 1         | 0.32%   |
| Creative Technology                    | 1         | 0.32%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony HD Webcam                                                          | 19        | 6.17%   |
| Chicony USB2.0 Camera                                                      | 17        | 5.52%   |
| Microdia Integrated_Webcam_HD                                              | 11        | 3.57%   |
| Chicony Integrated Camera                                                  | 11        | 3.57%   |
| IMC Networks Integrated Camera                                             | 9         | 2.92%   |
| Realtek Integrated_Webcam_HD                                               | 8         | 2.6%    |
| IMC Networks USB2.0 HD UVC WebCam                                          | 7         | 2.27%   |
| Sunplus HD WebCam                                                          | 6         | 1.95%   |
| Chicony HP HD Camera                                                       | 6         | 1.95%   |
| Acer HD Webcam                                                             | 6         | 1.95%   |
| Acer BisonCam,NB Pro                                                       | 6         | 1.95%   |
| Acer Integrated Camera                                                     | 5         | 1.62%   |
| Syntek Integrated Camera                                                   | 4         | 1.3%    |
| Sunplus Integrated_Webcam_HD                                               | 4         | 1.3%    |
| IMC Networks VGA UVC WebCam                                                | 4         | 1.3%    |
| Apple FaceTime HD Camera                                                   | 4         | 1.3%    |
| Sunplus Asus Webcam                                                        | 3         | 0.97%   |
| Realtek Lenovo EasyCamera                                                  | 3         | 0.97%   |
| Realtek Integrated Webcam                                                  | 3         | 0.97%   |
| IMC Networks ov9734_azurewave_camera                                       | 3         | 0.97%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 3         | 0.97%   |
| Chicony Integrated Camera [ThinkPad]                                       | 3         | 0.97%   |
| Chicony Integrated Camera (1280x720@30)                                    | 3         | 0.97%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 0.97%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 0.97%   |
| Apple iPhone5/5C/5S/6                                                      | 3         | 0.97%   |
| Acer SunplusIT Integrated Camera                                           | 3         | 0.97%   |
| Acer EasyCamera                                                            | 3         | 0.97%   |
| Acer BisonCam, NB Pro                                                      | 3         | 0.97%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 0.65%   |
| Syntek EasyCamera                                                          | 2         | 0.65%   |
| Suyin USB 2.0 Camera                                                       | 2         | 0.65%   |
| Suyin HP Truevision HD                                                     | 2         | 0.65%   |
| Sunplus Lenovo EasyCamera                                                  | 2         | 0.65%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 2         | 0.65%   |
| Sunplus HP HD Webcam [Fixed]                                               | 2         | 0.65%   |
| Sunplus HD User Facing                                                     | 2         | 0.65%   |
| Sunplus Aukey-PC-LM1E Camera                                               | 2         | 0.65%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 0.65%   |
| Realtek HP "Truevision HD" laptop camera                                   | 2         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 26        | 34.21%  |
| Validity Sensors           | 24        | 31.58%  |
| Shenzhen Goodix Technology | 12        | 15.79%  |
| LighTuning Technology      | 7         | 9.21%   |
| Elan Microelectronics      | 4         | 5.26%   |
| AuthenTec                  | 3         | 3.95%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 9         | 11.84%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 10.53%  |
| Unknown                                                                    | 8         | 10.53%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 9.21%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 6.58%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.26%   |
| Synaptics WBDI Device                                                      | 4         | 5.26%   |
| Elan ELAN:Fingerprint                                                      | 4         | 5.26%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 3.95%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.95%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 3.95%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 3.95%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.63%   |
| Validity Sensors VFS491                                                    | 2         | 2.63%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.63%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 2.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.32%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.32%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.32%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.32%   |
| AuthenTec AES2810                                                          | 1         | 1.32%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.32%   |
| AuthenTec AES1600                                                          | 1         | 1.32%   |

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
| 0     | 199       | 57.35%  |
| 1     | 114       | 32.85%  |
| 2     | 28        | 8.07%   |
| 3     | 3         | 0.86%   |
| 6     | 1         | 0.29%   |
| 5     | 1         | 0.29%   |
| 4     | 1         | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 75        | 41.44%  |
| Graphics card            | 29        | 16.02%  |
| Chipcard                 | 22        | 12.15%  |
| Communication controller | 16        | 8.84%   |
| Net/wireless             | 15        | 8.29%   |
| Camera                   | 5         | 2.76%   |
| Bluetooth                | 5         | 2.76%   |
| Multimedia controller    | 4         | 2.21%   |
| Storage                  | 3         | 1.66%   |
| Sound                    | 3         | 1.66%   |
| Card reader              | 3         | 1.66%   |
| Net/ethernet             | 1         | 0.55%   |

