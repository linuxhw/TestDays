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

Total: 527

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [683d3101d8](https://linux-hardware.org/?probe=683d3101d8) | Mar 31, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [1c517ff300](https://linux-hardware.org/?probe=1c517ff300) | Mar 27, 2023 |
| Dell          | Inspiron 3543               | [d714304a67](https://linux-hardware.org/?probe=d714304a67) | Mar 27, 2023 |
| Dell          | Inspiron 3543               | [f733f5b792](https://linux-hardware.org/?probe=f733f5b792) | Mar 27, 2023 |
| Lenovo        | ThinkPad E15 20RD003KHV     | [8701ff9985](https://linux-hardware.org/?probe=8701ff9985) | Mar 26, 2023 |
| MSI           | Alpha 15 B5EEK              | [03f3f846eb](https://linux-hardware.org/?probe=03f3f846eb) | Mar 24, 2023 |
| HP            | ZBook 15 G4                 | [ebd974c40f](https://linux-hardware.org/?probe=ebd974c40f) | Mar 23, 2023 |
| Dell          | Latitude 7480               | [0301ad09f6](https://linux-hardware.org/?probe=0301ad09f6) | Mar 23, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [a3339e152a](https://linux-hardware.org/?probe=a3339e152a) | Mar 18, 2023 |
| ASUSTek       | X555LAB                     | [18bf88d413](https://linux-hardware.org/?probe=18bf88d413) | Mar 17, 2023 |
| Apple         | MacBookPro11,3              | [1ade706194](https://linux-hardware.org/?probe=1ade706194) | Mar 17, 2023 |
| Apple         | MacBookPro11,3              | [45537ae306](https://linux-hardware.org/?probe=45537ae306) | Mar 17, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [a7d30f68b1](https://linux-hardware.org/?probe=a7d30f68b1) | Mar 12, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [d7ed4aaf2c](https://linux-hardware.org/?probe=d7ed4aaf2c) | Mar 11, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e97141469](https://linux-hardware.org/?probe=6e97141469) | Mar 10, 2023 |
| ASUSTek       | K52F                        | [8fa6eaf7cf](https://linux-hardware.org/?probe=8fa6eaf7cf) | Mar 10, 2023 |
| MSI           | Raider GE76 12UE            | [b78033fddd](https://linux-hardware.org/?probe=b78033fddd) | Mar 08, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [8a70478523](https://linux-hardware.org/?probe=8a70478523) | Mar 06, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [6e08a2dcf9](https://linux-hardware.org/?probe=6e08a2dcf9) | Mar 06, 2023 |
| HP            | ZBook 15 G4                 | [38a0ce48ed](https://linux-hardware.org/?probe=38a0ce48ed) | Mar 04, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | [ceb6fb20b2](https://linux-hardware.org/?probe=ceb6fb20b2) | Mar 02, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [b80c1e685f](https://linux-hardware.org/?probe=b80c1e685f) | Feb 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [e3578290d2](https://linux-hardware.org/?probe=e3578290d2) | Feb 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | [6b2160527d](https://linux-hardware.org/?probe=6b2160527d) | Feb 23, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | [2daf635e15](https://linux-hardware.org/?probe=2daf635e15) | Feb 18, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [12f305c12f](https://linux-hardware.org/?probe=12f305c12f) | Feb 17, 2023 |
| Google        | Boten                       | [5562b4af15](https://linux-hardware.org/?probe=5562b4af15) | Feb 11, 2023 |
| Google        | Boten                       | [d07e5295bb](https://linux-hardware.org/?probe=d07e5295bb) | Feb 11, 2023 |
| HP            | Laptop 14-cm0xxx            | [5dfc3e2280](https://linux-hardware.org/?probe=5dfc3e2280) | Feb 08, 2023 |
| Apple         | MacBookAir7,2               | [b5f0169944](https://linux-hardware.org/?probe=b5f0169944) | Jan 28, 2023 |
| Dell          | Latitude E6420              | [a772965137](https://linux-hardware.org/?probe=a772965137) | Jan 27, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [ee44dc2539](https://linux-hardware.org/?probe=ee44dc2539) | Jan 27, 2023 |
| HP            | ProBook 450 G7              | [1d507a3cdc](https://linux-hardware.org/?probe=1d507a3cdc) | Jan 27, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [7bf2d60c0b](https://linux-hardware.org/?probe=7bf2d60c0b) | Jan 21, 2023 |
| Google        | Banjo                       | [30a528ac6b](https://linux-hardware.org/?probe=30a528ac6b) | Jan 14, 2023 |
| Google        | Banjo                       | [66dc97b0de](https://linux-hardware.org/?probe=66dc97b0de) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [d83005eb10](https://linux-hardware.org/?probe=d83005eb10) | Jan 03, 2023 |
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

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_Budgie/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu Budgie 20.04 | 167       | 44.53%  |
| Ubuntu Budgie 22.04 | 61        | 16.27%  |
| Ubuntu Budgie 20.10 | 34        | 9.07%   |
| Ubuntu Budgie 21.10 | 33        | 8.8%    |
| Ubuntu Budgie 18.04 | 24        | 6.4%    |
| Ubuntu Budgie 21.04 | 21        | 5.6%    |
| Ubuntu Budgie 22.10 | 19        | 5.07%   |
| Ubuntu Budgie 19.10 | 13        | 3.47%   |
| Ubuntu Budgie 16.04 | 2         | 0.53%   |
| Ubuntu Budgie       | 1         | 0.27%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu Budgie | 365       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 18        | 4.41%   |
| 5.3.0-40-generic  | 10        | 2.45%   |
| 5.13.0-22-generic | 10        | 2.45%   |
| 5.4.0-40-generic  | 9         | 2.21%   |
| 5.8.0-41-generic  | 7         | 1.72%   |
| 5.15.0-27-generic | 7         | 1.72%   |
| 5.13.0-28-generic | 7         | 1.72%   |
| 5.4.0-37-generic  | 6         | 1.47%   |
| 5.4.0-29-generic  | 6         | 1.47%   |
| 5.13.0-39-generic | 6         | 1.47%   |
| 5.8.0-53-generic  | 5         | 1.23%   |
| 5.8.0-48-generic  | 5         | 1.23%   |
| 5.4.0-52-generic  | 5         | 1.23%   |
| 5.4.0-48-generic  | 5         | 1.23%   |
| 5.4.0-33-generic  | 5         | 1.23%   |
| 5.19.0-35-generic | 5         | 1.23%   |
| 5.15.0-50-generic | 5         | 1.23%   |
| 5.15.0-48-generic | 5         | 1.23%   |
| 5.13.0-40-generic | 5         | 1.23%   |
| 5.13.0-35-generic | 5         | 1.23%   |
| 5.13.0-30-generic | 5         | 1.23%   |
| 5.13.0-19-generic | 5         | 1.23%   |
| 5.11.0-41-generic | 5         | 1.23%   |
| 5.8.0-44-generic  | 4         | 0.98%   |
| 5.8.0-33-generic  | 4         | 0.98%   |
| 5.8.0-29-generic  | 4         | 0.98%   |
| 5.4.0-58-generic  | 4         | 0.98%   |
| 5.4.0-31-generic  | 4         | 0.98%   |
| 5.19.0-26-generic | 4         | 0.98%   |
| 5.15.0-52-generic | 4         | 0.98%   |
| 5.15.0-46-generic | 4         | 0.98%   |
| 5.11.0-34-generic | 4         | 0.98%   |
| 5.11.0-16-generic | 4         | 0.98%   |
| 5.8.0-45-generic  | 3         | 0.74%   |
| 5.4.0-91-generic  | 3         | 0.74%   |
| 5.4.0-73-generic  | 3         | 0.74%   |
| 5.4.0-28-generic  | 3         | 0.74%   |
| 5.19.0-31-generic | 3         | 0.74%   |
| 5.19.0-29-generic | 3         | 0.74%   |
| 5.19.0-23-generic | 3         | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 104       | 27.3%   |
| 5.15.0  | 63        | 16.54%  |
| 5.8.0   | 54        | 14.17%  |
| 5.13.0  | 54        | 14.17%  |
| 5.11.0  | 34        | 8.92%   |
| 5.19.0  | 22        | 5.77%   |
| 5.3.0   | 21        | 5.51%   |
| 4.15.0  | 10        | 2.62%   |
| 5.6.0   | 3         | 0.79%   |
| 5.12.0  | 2         | 0.52%   |
| 5.0.0   | 2         | 0.52%   |
| 4.18.0  | 2         | 0.52%   |
| 6.1.0   | 1         | 0.26%   |
| 5.9.0   | 1         | 0.26%   |
| 5.8.11  | 1         | 0.26%   |
| 5.6.7   | 1         | 0.26%   |
| 5.5.0   | 1         | 0.26%   |
| 5.16.14 | 1         | 0.26%   |
| 5.15.11 | 1         | 0.26%   |
| 5.10.11 | 1         | 0.26%   |
| 5.10.0  | 1         | 0.26%   |
| 4.4.0   | 1         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 104       | 27.3%   |
| 5.15    | 64        | 16.8%   |
| 5.8     | 55        | 14.44%  |
| 5.13    | 54        | 14.17%  |
| 5.11    | 34        | 8.92%   |
| 5.19    | 22        | 5.77%   |
| 5.3     | 21        | 5.51%   |
| 4.15    | 10        | 2.62%   |
| 5.6     | 4         | 1.05%   |
| 5.12    | 2         | 0.52%   |
| 5.10    | 2         | 0.52%   |
| 5.0     | 2         | 0.52%   |
| 4.18    | 2         | 0.52%   |
| 6.1     | 1         | 0.26%   |
| 5.9     | 1         | 0.26%   |
| 5.5     | 1         | 0.26%   |
| 5.16    | 1         | 0.26%   |
| 4.4     | 1         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 362       | 99.18%  |
| i686   | 3         | 0.82%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Budgie     | 357       | 97.81%  |
| GNOME      | 6         | 1.64%   |
| XFCE       | 1         | 0.27%   |
| X-Cinnamon | 1         | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 353       | 96.45%  |
| Wayland | 11        | 3.01%   |
| Tty     | 2         | 0.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 137       | 37.23%  |
| Unknown | 133       | 36.14%  |
| TDM     | 58        | 15.76%  |
| GDM     | 25        | 6.79%   |
| GDM3    | 14        | 3.8%    |
| SDDM    | 1         | 0.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 119       | 32.51%  |
| de_DE   | 51        | 13.93%  |
| fr_FR   | 26        | 7.1%    |
| pt_BR   | 25        | 6.83%   |
| en_GB   | 23        | 6.28%   |
| en_CA   | 13        | 3.55%   |
| it_IT   | 12        | 3.28%   |
| ru_RU   | 11        | 3.01%   |
| en_IN   | 11        | 3.01%   |
| es_AR   | 7         | 1.91%   |
| es_MX   | 6         | 1.64%   |
| C       | 6         | 1.64%   |
| es_ES   | 5         | 1.37%   |
| es_CL   | 4         | 1.09%   |
| pl_PL   | 3         | 0.82%   |
| hu_HU   | 3         | 0.82%   |
| en_AU   | 3         | 0.82%   |
| de_AT   | 3         | 0.82%   |
| Unknown | 3         | 0.82%   |
| pt_PT   | 2         | 0.55%   |
| fr_BE   | 2         | 0.55%   |
| fi_FI   | 2         | 0.55%   |
| en_IE   | 2         | 0.55%   |
| de_CH   | 2         | 0.55%   |
| cs_CZ   | 2         | 0.55%   |
| zh_TW   | 1         | 0.27%   |
| zh_CN   | 1         | 0.27%   |
| uk_UA   | 1         | 0.27%   |
| tr_TR   | 1         | 0.27%   |
| nl_NL   | 1         | 0.27%   |
| nl_BE   | 1         | 0.27%   |
| nb_NO   | 1         | 0.27%   |
| mt_MT   | 1         | 0.27%   |
| lv_LV   | 1         | 0.27%   |
| ja_JP   | 1         | 0.27%   |
| id_ID   | 1         | 0.27%   |
| fr_CH   | 1         | 0.27%   |
| es_US   | 1         | 0.27%   |
| es_SV   | 1         | 0.27%   |
| es_PE   | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 214       | 57.68%  |
| BIOS | 157       | 42.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 341       | 93.17%  |
| Zfs     | 10        | 2.73%   |
| Overlay | 7         | 1.91%   |
| Btrfs   | 4         | 1.09%   |
| Xfs     | 3         | 0.82%   |
| Jfs     | 1         | 0.27%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 175       | 47.43%  |
| GPT     | 166       | 44.99%  |
| MBR     | 28        | 7.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 326       | 88.59%  |
| Yes       | 42        | 11.41%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 253       | 68.75%  |
| Yes       | 115       | 31.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 71        | 19.45%  |
| Hewlett-Packard        | 55        | 15.07%  |
| Dell                   | 50        | 13.7%   |
| TUXEDO                 | 42        | 11.51%  |
| ASUSTek Computer       | 38        | 10.41%  |
| Acer                   | 21        | 5.75%   |
| MSI                    | 16        | 4.38%   |
| Apple                  | 13        | 3.56%   |
| Sony                   | 6         | 1.64%   |
| Samsung Electronics    | 5         | 1.37%   |
| HUAWEI                 | 5         | 1.37%   |
| Google                 | 5         | 1.37%   |
| Toshiba                | 4         | 1.1%    |
| Unknown                | 4         | 1.1%    |
| Packard Bell           | 3         | 0.82%   |
| Fujitsu                | 3         | 0.82%   |
| Timi                   | 2         | 0.55%   |
| Standard               | 2         | 0.55%   |
| Razer                  | 2         | 0.55%   |
| Positivo               | 2         | 0.55%   |
| Alienware              | 2         | 0.55%   |
| Viglen                 | 1         | 0.27%   |
| THUNDEROBOT            | 1         | 0.27%   |
| Thomson                | 1         | 0.27%   |
| Quanta                 | 1         | 0.27%   |
| PC Specialist          | 1         | 0.27%   |
| GPU Company            | 1         | 0.27%   |
| Gigabyte Technology    | 1         | 0.27%   |
| EVOO                   | 1         | 0.27%   |
| Digibras               | 1         | 0.27%   |
| Chuwi                  | 1         | 0.27%   |
| BANGHO                 | 1         | 0.27%   |
| AXIOO                  | 1         | 0.27%   |
| AWOW                   | 1         | 0.27%   |
| Avell High Performance | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 14        | 3.84%   |
| TUXEDO InfinityBook S 15 Gen6           | 3         | 0.82%   |
| TUXEDO Aura 15 Gen1                     | 3         | 0.82%   |
| HP Pavilion g6                          | 3         | 0.82%   |
| TUXEDO Pulse 15 Gen1                    | 2         | 0.55%   |
| TUXEDO Polaris 15 AMD Gen1              | 2         | 0.55%   |
| TUXEDO InfinityBook S 14 Gen6           | 2         | 0.55%   |
| TUXEDO InfinityBook Pro 14 Gen6         | 2         | 0.55%   |
| Standard MT40II                         | 2         | 0.55%   |
| Lenovo ThinkBook 14-IML 20RV            | 2         | 0.55%   |
| Lenovo IdeaPad 5 15ARE05 81YQ           | 2         | 0.55%   |
| Lenovo IdeaPad 330S-15ARR 81FB          | 2         | 0.55%   |
| Lenovo IdeaPad 320-15IKB 80XL           | 2         | 0.55%   |
| Lenovo G500 20236                       | 2         | 0.55%   |
| Lenovo G50-45 80E3                      | 2         | 0.55%   |
| HP ZBook Studio G3                      | 2         | 0.55%   |
| HP ZBook 15 G4                          | 2         | 0.55%   |
| HP Notebook                             | 2         | 0.55%   |
| HP ENVY 17                              | 2         | 0.55%   |
| HP ENVY 15                              | 2         | 0.55%   |
| HP 2000                                 | 2         | 0.55%   |
| Dell XPS 13 9380                        | 2         | 0.55%   |
| Dell Latitude E6540                     | 2         | 0.55%   |
| Dell Latitude E6420                     | 2         | 0.55%   |
| Dell Latitude E6410                     | 2         | 0.55%   |
| Dell Latitude 5400                      | 2         | 0.55%   |
| Dell Inspiron 5570                      | 2         | 0.55%   |
| ASUS VivoBook_ASUSLaptop X705MAR_X705MA | 2         | 0.55%   |
| ASUS VivoBook_ASUSLaptop X571GT_F571GT  | 2         | 0.55%   |
| Apple MacBookPro8,1                     | 2         | 0.55%   |
| Apple MacBookAir7,2                     | 2         | 0.55%   |
| Acer TravelMate P446-M                  | 2         | 0.55%   |
| Viglen VUB1                             | 1         | 0.27%   |
| TUXEDO Stellaris Intel Gen3 (TGL)       | 1         | 0.27%   |
| TUXEDO Stellaris AMD Gen3 (CZN)         | 1         | 0.27%   |
| TUXEDO Polaris Intel Gen3 (TGL)         | 1         | 0.27%   |
| TUXEDO Polaris AMD Gen3 (CZN)           | 1         | 0.27%   |
| TUXEDO Polaris 17 AMD Gen1              | 1         | 0.27%   |
| TUXEDO Polaris (CML/Gen2)               | 1         | 0.27%   |
| TUXEDO P95_HR                           | 1         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 32        | 8.77%   |
| Dell Latitude         | 20        | 5.48%   |
| Lenovo IdeaPad        | 19        | 5.21%   |
| Dell Inspiron         | 14        | 3.84%   |
| Unknown               | 14        | 3.84%   |
| Acer Aspire           | 13        | 3.56%   |
| HP Pavilion           | 12        | 3.29%   |
| TUXEDO InfinityBook   | 11        | 3.01%   |
| HP EliteBook          | 9         | 2.47%   |
| Dell XPS              | 9         | 2.47%   |
| ASUS VivoBook         | 8         | 2.19%   |
| TUXEDO Polaris        | 6         | 1.64%   |
| HP ZBook              | 6         | 1.64%   |
| HP ProBook            | 6         | 1.64%   |
| HP ENVY               | 6         | 1.64%   |
| TUXEDO Book           | 5         | 1.37%   |
| HP Laptop             | 5         | 1.37%   |
| Toshiba Satellite     | 4         | 1.1%    |
| Lenovo ThinkBook      | 4         | 1.1%    |
| Acer Swift            | 4         | 1.1%    |
| TUXEDO Aura           | 3         | 0.82%   |
| HP Compaq             | 3         | 0.82%   |
| Fujitsu LIFEBOOK      | 3         | 0.82%   |
| Dell Vostro           | 3         | 0.82%   |
| ASUS ASUS             | 3         | 0.82%   |
| Apple MacBookPro8     | 3         | 0.82%   |
| Apple MacBookPro11    | 3         | 0.82%   |
| Acer TravelMate       | 3         | 0.82%   |
| TUXEDO Stellaris      | 2         | 0.55%   |
| TUXEDO Pulse          | 2         | 0.55%   |
| TUXEDO P95            | 2         | 0.55%   |
| Standard MT40II       | 2         | 0.55%   |
| Razer Blade           | 2         | 0.55%   |
| Packard Bell EasyNote | 2         | 0.55%   |
| MSI Prestige          | 2         | 0.55%   |
| MSI Modern            | 2         | 0.55%   |
| MSI GL65              | 2         | 0.55%   |
| Lenovo Yoga           | 2         | 0.55%   |
| Lenovo G500           | 2         | 0.55%   |
| Lenovo G50-45         | 2         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 51        | 13.97%  |
| 2020 | 45        | 12.33%  |
| 2018 | 41        | 11.23%  |
| 2021 | 30        | 8.22%   |
| 2011 | 27        | 7.4%    |
| 2017 | 26        | 7.12%   |
| 2012 | 24        | 6.58%   |
| 2014 | 22        | 6.03%   |
| 2013 | 20        | 5.48%   |
| 2016 | 19        | 5.21%   |
| 2015 | 18        | 4.93%   |
| 2010 | 13        | 3.56%   |
| 2008 | 10        | 2.74%   |
| 2009 | 8         | 2.19%   |
| 2007 | 6         | 1.64%   |
| 2022 | 5         | 1.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 365       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 328       | 89.62%  |
| Enabled  | 38        | 10.38%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 360       | 98.63%  |
| Yes  | 5         | 1.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 110       | 29.81%  |
| 16.01-24.0  | 80        | 21.68%  |
| 3.01-4.0    | 58        | 15.72%  |
| 8.01-16.0   | 57        | 15.45%  |
| 32.01-64.0  | 34        | 9.21%   |
| 64.01-256.0 | 14        | 3.79%   |
| 1.01-2.0    | 10        | 2.71%   |
| 24.01-32.0  | 4         | 1.08%   |
| 2.01-3.0    | 2         | 0.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 116       | 29.59%  |
| 1.01-2.0   | 108       | 27.55%  |
| 4.01-8.0   | 78        | 19.9%   |
| 3.01-4.0   | 64        | 16.33%  |
| 8.01-16.0  | 19        | 4.85%   |
| 0.51-1.0   | 4         | 1.02%   |
| 16.01-24.0 | 2         | 0.51%   |
| 24.01-32.0 | 1         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 266       | 72.09%  |
| 2      | 92        | 24.93%  |
| 3      | 9         | 2.44%   |
| 0      | 2         | 0.54%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 262       | 71.58%  |
| Yes       | 104       | 28.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 293       | 79.84%  |
| No        | 74        | 20.16%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 361       | 98.9%   |
| No        | 4         | 1.1%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 308       | 83.92%  |
| No        | 59        | 16.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 59        | 16.16%  |
| USA                | 49        | 13.42%  |
| Brazil             | 28        | 7.67%   |
| France             | 26        | 7.12%   |
| Italy              | 15        | 4.11%   |
| UK                 | 14        | 3.84%   |
| India              | 13        | 3.56%   |
| Russia             | 12        | 3.29%   |
| Canada             | 11        | 3.01%   |
| Netherlands        | 9         | 2.47%   |
| Argentina          | 9         | 2.47%   |
| Mexico             | 8         | 2.19%   |
| Spain              | 7         | 1.92%   |
| Poland             | 7         | 1.92%   |
| Austria            | 5         | 1.37%   |
| Ukraine            | 4         | 1.1%    |
| Switzerland        | 4         | 1.1%    |
| Hungary            | 4         | 1.1%    |
| Greece             | 4         | 1.1%    |
| Finland            | 4         | 1.1%    |
| Chile              | 4         | 1.1%    |
| Belgium            | 4         | 1.1%    |
| Turkey             | 3         | 0.82%   |
| Sweden             | 3         | 0.82%   |
| South Africa       | 3         | 0.82%   |
| Portugal           | 3         | 0.82%   |
| Norway             | 3         | 0.82%   |
| Japan              | 3         | 0.82%   |
| Iran               | 3         | 0.82%   |
| Indonesia          | 3         | 0.82%   |
| Dominican Republic | 3         | 0.82%   |
| Australia          | 3         | 0.82%   |
| Slovenia           | 2         | 0.55%   |
| Malaysia           | 2         | 0.55%   |
| Ireland            | 2         | 0.55%   |
| Ecuador            | 2         | 0.55%   |
| Czechia            | 2         | 0.55%   |
| Colombia           | 2         | 0.55%   |
| Taiwan             | 1         | 0.27%   |
| Singapore          | 1         | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 6         | 1.61%   |
| Berlin             | 6         | 1.61%   |
| Moscow             | 5         | 1.34%   |
| Ravensburg         | 4         | 1.07%   |
| Budapest           | 4         | 1.07%   |
| Athens             | 4         | 1.07%   |
| Tehran             | 3         | 0.8%    |
| St Petersburg      | 3         | 0.8%    |
| Santo Domingo Este | 3         | 0.8%    |
| Pune               | 3         | 0.8%    |
| Munich             | 3         | 0.8%    |
| Montreal           | 3         | 0.8%    |
| Hamburg            | 3         | 0.8%    |
| Brasília          | 3         | 0.8%    |
| Austin             | 3         | 0.8%    |
| Amsterdam          | 3         | 0.8%    |
| Wolfsburg          | 2         | 0.54%   |
| Warsaw             | 2         | 0.54%   |
| Vienna             | 2         | 0.54%   |
| Vancouver          | 2         | 0.54%   |
| Sunnyvale          | 2         | 0.54%   |
| Stuttgart          | 2         | 0.54%   |
| San Miguel         | 2         | 0.54%   |
| San Francisco      | 2         | 0.54%   |
| Portland           | 2         | 0.54%   |
| Paris              | 2         | 0.54%   |
| Nuremberg          | 2         | 0.54%   |
| Nuneaton           | 2         | 0.54%   |
| Niterói           | 2         | 0.54%   |
| Mumbai             | 2         | 0.54%   |
| Milan              | 2         | 0.54%   |
| Los Angeles        | 2         | 0.54%   |
| Lisbon             | 2         | 0.54%   |
| Kyiv               | 2         | 0.54%   |
| Kassel             | 2         | 0.54%   |
| Istanbul           | 2         | 0.54%   |
| Gurgaon            | 2         | 0.54%   |
| Dublin             | 2         | 0.54%   |
| Cologne            | 2         | 0.54%   |
| Burzaco            | 2         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 99        | 127    | 21.66%  |
| Seagate                        | 46        | 49     | 10.07%  |
| WDC                            | 45        | 48     | 9.85%   |
| Toshiba                        | 40        | 49     | 8.75%   |
| Unknown                        | 31        | 35     | 6.78%   |
| SanDisk                        | 26        | 29     | 5.69%   |
| SK hynix                       | 17        | 19     | 3.72%   |
| Kingston                       | 17        | 18     | 3.72%   |
| Crucial                        | 17        | 19     | 3.72%   |
| Intel                          | 15        | 20     | 3.28%   |
| Micron Technology              | 14        | 16     | 3.06%   |
| HGST                           | 8         | 11     | 1.75%   |
| A-DATA Technology              | 8         | 9      | 1.75%   |
| Hitachi                        | 7         | 7      | 1.53%   |
| China                          | 7         | 9      | 1.53%   |
| Apple                          | 6         | 6      | 1.31%   |
| SPCC                           | 5         | 5      | 1.09%   |
| PNY                            | 5         | 7      | 1.09%   |
| KIOXIA                         | 3         | 3      | 0.66%   |
| JMicron Technology             | 3         | 3      | 0.66%   |
| Micron/Crucial Technology      | 2         | 2      | 0.44%   |
| LITEON                         | 2         | 2      | 0.44%   |
| Lenovo                         | 2         | 2      | 0.44%   |
| Intenso                        | 2         | 3      | 0.44%   |
| Hewlett-Packard                | 2         | 1      | 0.44%   |
| Corsair                        | 2         | 3      | 0.44%   |
| Unknown                        | 2         | 2      | 0.44%   |
| VISIPRO                        | 1         | 1      | 0.22%   |
| Vaseky                         | 1         | 1      | 0.22%   |
| USB30                          | 1         | 1      | 0.22%   |
| Union Memory                   | 1         | 1      | 0.22%   |
| TO Exter                       | 1         | 1      | 0.22%   |
| Teclast                        | 1         | 2      | 0.22%   |
| SSSTC                          | 1         | 2      | 0.22%   |
| Solid State Storage Technology | 1         | 1      | 0.22%   |
| Realtek Semiconductor          | 1         | 2      | 0.22%   |
| Phison Electronics             | 1         | 1      | 0.22%   |
| Phison                         | 1         | 1      | 0.22%   |
| Patriot                        | 1         | 1      | 0.22%   |
| OWC                            | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                 | 6         | 1.27%   |
| Toshiba MQ04ABF100 1TB                 | 6         | 1.27%   |
| Toshiba MQ01ABD100 1TB                 | 6         | 1.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 6         | 1.27%   |
| Samsung SSD 860 EVO M.2 500GB          | 6         | 1.27%   |
| WDC WD10JPVX-22JC3T0 1TB               | 5         | 1.06%   |
| Unknown MMC Card  32GB                 | 5         | 1.06%   |
| Seagate ST1000LM035-1RK172 1TB         | 5         | 1.06%   |
| Samsung SSD 860 EVO M.2 250GB          | 5         | 1.06%   |
| Samsung NVMe SSD Drive 1TB             | 5         | 1.06%   |
| SK hynix NVMe SSD Drive 256GB          | 4         | 0.85%   |
| Seagate ST9500325AS 500GB              | 4         | 0.85%   |
| SanDisk NVMe SSD Drive 512GB           | 4         | 0.85%   |
| Samsung SSD 970 EVO Plus 1TB           | 4         | 0.85%   |
| Samsung NVMe SSD Drive 512GB           | 4         | 0.85%   |
| Samsung NVMe SSD Drive 500GB           | 4         | 0.85%   |
| Unknown SD64G  64GB                    | 3         | 0.64%   |
| Unknown MMC Card  16GB                 | 3         | 0.64%   |
| SPCC Solid State Disk 120GB            | 3         | 0.64%   |
| Seagate ST500LT012-1DG142 500GB        | 3         | 0.64%   |
| Seagate ST1000LX015-1U7172 1TB         | 3         | 0.64%   |
| Samsung SSD 980 500GB                  | 3         | 0.64%   |
| Samsung SSD 970 EVO Plus 500GB         | 3         | 0.64%   |
| Samsung SSD 970 EVO 500GB              | 3         | 0.64%   |
| Samsung SSD 860 EVO 500GB              | 3         | 0.64%   |
| Samsung SSD 750 EVO 250GB              | 3         | 0.64%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB | 3         | 0.64%   |
| Samsung NVMe SSD Drive 2TB             | 3         | 0.64%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 2         | 0.42%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 2         | 0.42%   |
| WDC WD10SPZX-60Z10T0 1TB               | 2         | 0.42%   |
| WDC WD10SPZX-24Z10 1TB                 | 2         | 0.42%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB   | 2         | 0.42%   |
| Unknown SD/MMC/MS PRO 64GB             | 2         | 0.42%   |
| Unknown MMC128  128GB                  | 2         | 0.42%   |
| Toshiba MQ01ACF050 500GB               | 2         | 0.42%   |
| Seagate ST500LT012-9WS142 500GB        | 2         | 0.42%   |
| Seagate ST1000LM049-2GH172 1TB         | 2         | 0.42%   |
| Seagate ST1000LM048-2E7172 1TB         | 2         | 0.42%   |
| Seagate Expansion Desk 8TB             | 2         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 43        | 46     | 37.39%  |
| Toshiba             | 27        | 31     | 23.48%  |
| WDC                 | 26        | 28     | 22.61%  |
| HGST                | 8         | 11     | 6.96%   |
| Hitachi             | 7         | 7      | 6.09%   |
| Unknown             | 2         | 2      | 1.74%   |
| Samsung Electronics | 1         | 1      | 0.87%   |
| Fujitsu             | 1         | 1      | 0.87%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 46        | 57     | 27.06%  |
| SanDisk             | 17        | 17     | 10%     |
| Crucial             | 16        | 18     | 9.41%   |
| Kingston            | 13        | 13     | 7.65%   |
| WDC                 | 7         | 7      | 4.12%   |
| Micron Technology   | 7         | 8      | 4.12%   |
| China               | 7         | 9      | 4.12%   |
| A-DATA Technology   | 6         | 7      | 3.53%   |
| SPCC                | 5         | 5      | 2.94%   |
| PNY                 | 5         | 7      | 2.94%   |
| Intel               | 5         | 5      | 2.94%   |
| Apple               | 5         | 5      | 2.94%   |
| Toshiba             | 3         | 3      | 1.76%   |
| SK hynix            | 2         | 2      | 1.18%   |
| Seagate             | 2         | 2      | 1.18%   |
| LITEON              | 2         | 2      | 1.18%   |
| JMicron Technology  | 2         | 2      | 1.18%   |
| Intenso             | 2         | 3      | 1.18%   |
| VISIPRO             | 1         | 1      | 0.59%   |
| Vaseky              | 1         | 1      | 0.59%   |
| USB30               | 1         | 1      | 0.59%   |
| Unknown             | 1         | 1      | 0.59%   |
| Union Memory        | 1         | 1      | 0.59%   |
| TO Exter            | 1         | 1      | 0.59%   |
| Teclast             | 1         | 2      | 0.59%   |
| Patriot             | 1         | 1      | 0.59%   |
| OWC                 | 1         | 1      | 0.59%   |
| Netac               | 1         | 1      | 0.59%   |
| LITEONIT            | 1         | 1      | 0.59%   |
| KingSpec            | 1         | 1      | 0.59%   |
| Hewlett-Packard     | 1         | 1      | 0.59%   |
| Gigabyte Technology | 1         | 1      | 0.59%   |
| FORESEE             | 1         | 1      | 0.59%   |
| Dogfish             | 1         | 1      | 0.59%   |
| Corsair             | 1         | 2      | 0.59%   |
| BIWIN               | 1         | 1      | 0.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 155       | 192    | 35.55%  |
| NVMe    | 133       | 171    | 30.5%   |
| HDD     | 112       | 127    | 25.69%  |
| MMC     | 30        | 36     | 6.88%   |
| Unknown | 6         | 5      | 1.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 233       | 308    | 56.55%  |
| NVMe | 133       | 171    | 32.28%  |
| MMC  | 30        | 36     | 7.28%   |
| SAS  | 16        | 16     | 3.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 173       | 208    | 64.79%  |
| 0.51-1.0   | 81        | 96     | 30.34%  |
| 1.01-2.0   | 11        | 13     | 4.12%   |
| 4.01-10.0  | 2         | 2      | 0.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 116       | 31.44%  |
| 101-250        | 110       | 29.81%  |
| 501-1000       | 48        | 13.01%  |
| 51-100         | 31        | 8.4%    |
| 1001-2000      | 20        | 5.42%   |
| 21-50          | 19        | 5.15%   |
| 1-20           | 11        | 2.98%   |
| 2001-3000      | 7         | 1.9%    |
| More than 3000 | 4         | 1.08%   |
| Unknown        | 3         | 0.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 122       | 32.02%  |
| 21-50          | 76        | 19.95%  |
| 101-250        | 73        | 19.16%  |
| 51-100         | 53        | 13.91%  |
| 251-500        | 32        | 8.4%    |
| 501-1000       | 15        | 3.94%   |
| 1001-2000      | 5         | 1.31%   |
| Unknown        | 3         | 0.79%   |
| More than 3000 | 2         | 0.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB               | 2         | 2      | 8.7%    |
| WDC WD6400BPVT-60HXZT3 640GB         | 1         | 1      | 4.35%   |
| WDC WD5000BPVT-00HXZT1 500GB         | 1         | 1      | 4.35%   |
| WDC WD2500BEKT-75PVMT1 250GB         | 1         | 1      | 4.35%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 4.35%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 4.35%   |
| Toshiba MQ01ABD050 500GB             | 1         | 1      | 4.35%   |
| Toshiba MK5055GSX 500GB              | 1         | 1      | 4.35%   |
| Toshiba MK3265GSXN 320GB             | 1         | 1      | 4.35%   |
| Toshiba MK2561GSYN 250GB             | 1         | 1      | 4.35%   |
| Seagate ST9750420AS 752GB            | 1         | 1      | 4.35%   |
| Seagate ST9500423AS 500GB            | 1         | 1      | 4.35%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 4.35%   |
| Seagate ST500LX012-1LM162-SSHD 500GB | 1         | 1      | 4.35%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 4.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 1      | 4.35%   |
| PNY SSD2SC120G3LC709B121-460I 120GB  | 1         | 1      | 4.35%   |
| Kingston SNS4151S316G 16GB SSD       | 1         | 1      | 4.35%   |
| HGST HTS725032A7E630 320GB           | 1         | 2      | 4.35%   |
| HGST HTS541075A9E680 752GB           | 1         | 1      | 4.35%   |
| Crucial CT500P1SSD8 500GB            | 1         | 1      | 4.35%   |
| China SSD 256GB                      | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Toshiba  | 8         | 8      | 34.78%  |
| Seagate  | 6         | 6      | 26.09%  |
| WDC      | 3         | 3      | 13.04%  |
| HGST     | 2         | 3      | 8.7%    |
| PNY      | 1         | 1      | 4.35%   |
| Kingston | 1         | 1      | 4.35%   |
| Crucial  | 1         | 1      | 4.35%   |
| China    | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 8         | 8      | 42.11%  |
| Seagate | 6         | 6      | 31.58%  |
| WDC     | 3         | 3      | 15.79%  |
| HGST    | 2         | 3      | 10.53%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 20     | 82.61%  |
| SSD  | 3         | 3      | 13.04%  |
| NVMe | 1         | 1      | 4.35%   |

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
| Detected | 214       | 303    | 55.73%  |
| Works    | 148       | 204    | 38.54%  |
| Malfunc  | 22        | 24     | 5.73%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 257       | 60.47%  |
| Samsung Electronics            | 59        | 13.88%  |
| AMD                            | 32        | 7.53%   |
| SanDisk                        | 20        | 4.71%   |
| SK hynix                       | 13        | 3.06%   |
| Toshiba America Info Systems   | 9         | 2.12%   |
| Micron Technology              | 7         | 1.65%   |
| KIOXIA                         | 4         | 0.94%   |
| Kingston Technology Company    | 4         | 0.94%   |
| Phison Electronics             | 3         | 0.71%   |
| Micron/Crucial Technology      | 3         | 0.71%   |
| Solid State Storage Technology | 2         | 0.47%   |
| Realtek Semiconductor          | 2         | 0.47%   |
| Nvidia                         | 2         | 0.47%   |
| Lenovo                         | 2         | 0.47%   |
| ADATA Technology               | 2         | 0.47%   |
| Union Memory (Shenzhen)        | 1         | 0.24%   |
| Silicon Motion                 | 1         | 0.24%   |
| Shenzhen Longsys Electronics   | 1         | 0.24%   |
| Apple                          | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 34        | 7.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 33        | 7.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 30        | 6.73%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 29        | 6.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 22        | 4.93%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 17        | 3.81%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 14        | 3.14%   |
| Samsung NVMe SSD Controller 980                                                  | 12        | 2.69%   |
| Intel Comet Lake SATA AHCI Controller                                            | 12        | 2.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 2.69%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 11        | 2.47%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 10        | 2.24%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10        | 2.24%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 9         | 2.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 8         | 1.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 1.57%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 7         | 1.57%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6         | 1.35%   |
| Micron NVMe Storage Controller                                                   | 6         | 1.35%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 1.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 1.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 6         | 1.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 1.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 1.35%   |
| Intel SSD 660P Series                                                            | 5         | 1.12%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 1.12%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 4         | 0.9%    |
| SK hynix Non-Volatile memory controller                                          | 4         | 0.9%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 0.9%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 0.9%    |
| SanDisk PC SN520 NVMe SSD                                                        | 4         | 0.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 0.9%    |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 0.9%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 0.9%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.67%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 0.67%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 3         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 264       | 60.69%  |
| NVMe | 135       | 31.03%  |
| RAID | 24        | 5.52%   |
| IDE  | 12        | 2.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 316       | 86.58%  |
| AMD    | 49        | 13.42%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 17        | 4.66%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 12        | 3.29%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 2.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 9         | 2.47%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 2.19%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 1.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.64%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 1.64%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 1.37%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 1.37%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 1.37%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 1.37%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.37%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.1%    |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 1.1%    |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 1.1%    |
| Intel Core i7-10710U CPU @ 1.10GHz            | 4         | 1.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.1%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 1.1%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.1%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 1.1%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 4         | 1.1%    |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 3         | 0.82%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.82%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 0.82%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 3         | 0.82%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 3         | 0.82%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 0.82%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 0.82%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.82%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 3         | 0.82%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 0.82%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.82%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.82%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.82%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 0.82%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.82%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 0.82%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 0.82%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 0.82%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 130       | 35.62%  |
| Intel Core i5           | 81        | 22.19%  |
| Other                   | 24        | 6.58%   |
| Intel Core i3           | 24        | 6.58%   |
| Intel Celeron           | 18        | 4.93%   |
| AMD Ryzen 5             | 15        | 4.11%   |
| AMD Ryzen 7             | 12        | 3.29%   |
| Intel Core 2 Duo        | 11        | 3.01%   |
| Intel Pentium           | 9         | 2.47%   |
| Intel Atom              | 6         | 1.64%   |
| Intel Pentium Silver    | 4         | 1.1%    |
| AMD A8                  | 4         | 1.1%    |
| AMD Ryzen 9             | 3         | 0.82%   |
| AMD E                   | 3         | 0.82%   |
| AMD A6                  | 3         | 0.82%   |
| Intel Pentium Dual      | 2         | 0.55%   |
| Intel Genuine           | 2         | 0.55%   |
| Intel Core i9           | 2         | 0.55%   |
| AMD Turion 64 X2 Mobile | 2         | 0.55%   |
| AMD Ryzen 3             | 2         | 0.55%   |
| Intel Pentium Dual-Core | 1         | 0.27%   |
| Intel Core m5           | 1         | 0.27%   |
| Intel Core m3           | 1         | 0.27%   |
| AMD Ryzen 7 PRO         | 1         | 0.27%   |
| AMD Quad-Core           | 1         | 0.27%   |
| AMD E1                  | 1         | 0.27%   |
| AMD Athlon II           | 1         | 0.27%   |
| AMD A10                 | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 157       | 43.01%  |
| 2      | 150       | 41.1%   |
| 6      | 28        | 7.67%   |
| 8      | 24        | 6.58%   |
| 14     | 2         | 0.55%   |
| 1      | 2         | 0.55%   |
| 16     | 1         | 0.27%   |
| 10     | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 365       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 281       | 76.99%  |
| 1      | 84        | 23.01%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 364       | 99.73%  |
| 32-bit         | 1         | 0.27%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 109       | 29.07%  |
| 0x206a7    | 24        | 6.4%    |
| 0x806ec    | 22        | 5.87%   |
| 0x306a9    | 19        | 5.07%   |
| 0x906ea    | 14        | 3.73%   |
| 0x806ea    | 13        | 3.47%   |
| 0x806c1    | 11        | 2.93%   |
| 0x40651    | 11        | 2.93%   |
| 0x806e9    | 10        | 2.67%   |
| 0x406e3    | 9         | 2.4%    |
| 0x306d4    | 9         | 2.4%    |
| 0x306c3    | 9         | 2.4%    |
| 0x906e9    | 8         | 2.13%   |
| 0x806eb    | 8         | 2.13%   |
| 0xa0652    | 7         | 1.87%   |
| 0x20655    | 6         | 1.6%    |
| 0x08600106 | 5         | 1.33%   |
| 0x08600103 | 5         | 1.33%   |
| 0x1067a    | 4         | 1.07%   |
| 0x10676    | 4         | 1.07%   |
| 0x0a50000c | 4         | 1.07%   |
| 0xa0660    | 3         | 0.8%    |
| 0x806d1    | 3         | 0.8%    |
| 0x706e5    | 3         | 0.8%    |
| 0x706a8    | 3         | 0.8%    |
| 0x506e3    | 3         | 0.8%    |
| 0x406c3    | 3         | 0.8%    |
| 0x30678    | 3         | 0.8%    |
| 0x08108109 | 3         | 0.8%    |
| 0x0810100b | 3         | 0.8%    |
| 0x05000119 | 3         | 0.8%    |
| 0x906a3    | 2         | 0.53%   |
| 0x706a1    | 2         | 0.53%   |
| 0x6fd      | 2         | 0.53%   |
| 0x506c9    | 2         | 0.53%   |
| 0x40661    | 2         | 0.53%   |
| 0x20652    | 2         | 0.53%   |
| 0x106e5    | 2         | 0.53%   |
| 0x08600104 | 2         | 0.53%   |
| 0x08108102 | 2         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 103       | 28.22%  |
| SandyBridge      | 28        | 7.67%   |
| IvyBridge        | 28        | 7.67%   |
| Haswell          | 25        | 6.85%   |
| Zen 2            | 17        | 4.66%   |
| Skylake          | 17        | 4.66%   |
| TigerLake        | 16        | 4.38%   |
| CometLake        | 14        | 3.84%   |
| Broadwell        | 14        | 3.84%   |
| Silvermont       | 13        | 3.56%   |
| Penryn           | 11        | 3.01%   |
| Goldmont plus    | 11        | 3.01%   |
| Westmere         | 9         | 2.47%   |
| IceLake          | 9         | 2.47%   |
| Zen+             | 5         | 1.37%   |
| Zen 3            | 5         | 1.37%   |
| Unknown          | 5         | 1.37%   |
| Zen              | 4         | 1.1%    |
| Goldmont         | 4         | 1.1%    |
| Core             | 4         | 1.1%    |
| Puma             | 3         | 0.82%   |
| Jaguar           | 3         | 0.82%   |
| Bobcat           | 3         | 0.82%   |
| Nehalem          | 2         | 0.55%   |
| K8 Hammer        | 2         | 0.55%   |
| Excavator        | 2         | 0.55%   |
| Alderlake Hybrid | 2         | 0.55%   |
| Tremont          | 1         | 0.27%   |
| Piledriver       | 1         | 0.27%   |
| P6               | 1         | 0.27%   |
| K10 Llano        | 1         | 0.27%   |
| K10              | 1         | 0.27%   |
| Bonnell          | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 294       | 62.42%  |
| Nvidia | 108       | 22.93%  |
| AMD    | 69        | 14.65%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 26        | 5.42%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 5.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 24        | 5%      |
| Intel UHD Graphics 620                                                                   | 22        | 4.58%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 16        | 3.33%   |
| AMD Renoir                                                                               | 16        | 3.33%   |
| Intel HD Graphics 620                                                                    | 14        | 2.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 2.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 2.71%   |
| Intel HD Graphics 5500                                                                   | 11        | 2.29%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 2.29%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 2.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 1.88%   |
| Intel HD Graphics 630                                                                    | 9         | 1.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 1.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 1.67%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 1.46%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.46%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.25%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.04%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 1.04%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 1.04%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 5         | 1.04%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.04%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.83%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 0.83%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.83%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 4         | 0.83%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.83%   |
| Intel HD Graphics 530                                                                    | 4         | 0.83%   |
| Intel Comet Lake UHD Graphics                                                            | 4         | 0.83%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.83%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 0.83%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 3         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 194       | 53.15%  |
| Intel + Nvidia | 82        | 22.47%  |
| 1 x AMD        | 40        | 10.96%  |
| 1 x Nvidia     | 19        | 5.21%   |
| Intel + AMD    | 17        | 4.66%   |
| AMD + Nvidia   | 7         | 1.92%   |
| 2 x AMD        | 5         | 1.37%   |
| Other          | 1         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 290       | 78.8%   |
| Proprietary | 71        | 19.29%  |
| Unknown     | 7         | 1.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 259       | 70.19%  |
| 1.01-2.0   | 36        | 9.76%   |
| 0.01-0.5   | 20        | 5.42%   |
| 0.51-1.0   | 18        | 4.88%   |
| 3.01-4.0   | 17        | 4.61%   |
| 5.01-6.0   | 9         | 2.44%   |
| 7.01-8.0   | 8         | 2.17%   |
| 2.01-3.0   | 1         | 0.27%   |
| 8.01-16.0  | 1         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 81        | 18.71%  |
| AU Optronics            | 73        | 16.86%  |
| BOE                     | 60        | 13.86%  |
| LG Display              | 53        | 12.24%  |
| Samsung Electronics     | 38        | 8.78%   |
| Dell                    | 15        | 3.46%   |
| Goldstar                | 12        | 2.77%   |
| Apple                   | 12        | 2.77%   |
| Sharp                   | 11        | 2.54%   |
| Chi Mei Optoelectronics | 11        | 2.54%   |
| Lenovo                  | 7         | 1.62%   |
| PANDA                   | 6         | 1.39%   |
| Hewlett-Packard         | 6         | 1.39%   |
| BenQ                    | 5         | 1.15%   |
| Acer                    | 5         | 1.15%   |
| Philips                 | 4         | 0.92%   |
| Ancor Communications    | 4         | 0.92%   |
| LGD                     | 3         | 0.69%   |
| InfoVision              | 3         | 0.69%   |
| Unknown (AAA)           | 2         | 0.46%   |
| Fujitsu Siemens         | 2         | 0.46%   |
| ASUSTek Computer        | 2         | 0.46%   |
| AOC                     | 2         | 0.46%   |
| Vestel Elektronik       | 1         | 0.23%   |
| UPD                     | 1         | 0.23%   |
| Unknown                 | 1         | 0.23%   |
| Sony                    | 1         | 0.23%   |
| MStar                   | 1         | 0.23%   |
| LG Philips              | 1         | 0.23%   |
| LaCie                   | 1         | 0.23%   |
| KTC                     | 1         | 0.23%   |
| JDI                     | 1         | 0.23%   |
| InnoLux Display         | 1         | 0.23%   |
| Iiyama                  | 1         | 0.23%   |
| IBM                     | 1         | 0.23%   |
| GDH                     | 1         | 0.23%   |
| Eizo                    | 1         | 0.23%   |
| Daewoo                  | 1         | 0.23%   |
| CSO                     | 1         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 6         | 1.37%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch         | 6         | 1.37%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 5         | 1.14%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                    | 4         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.68%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 3         | 0.68%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch           | 3         | 0.68%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.68%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                  | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch     | 2         | 0.46%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 2         | 0.46%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 2         | 0.46%   |
| LGD LCD Monitor 1920x1080                                                | 2         | 0.46%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch             | 2         | 0.46%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 2         | 0.46%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch             | 2         | 0.46%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 2         | 0.46%   |
| LG Display LCD Monitor LGD04AF 1366x768 344x194mm 15.5-inch              | 2         | 0.46%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 2         | 0.46%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 0.46%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 0.46%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch              | 2         | 0.46%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 2         | 0.46%   |
| Dell U3415W DELA0AA 3440x1440 798x335mm 34.1-inch                        | 2         | 0.46%   |
| Dell U2415 DELA0BA 1920x1080 518x324mm 24.1-inch                         | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch         | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch         | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 2         | 0.46%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.46%   |
| BOE LCD Monitor BOE07D8 1920x1080 344x194mm 15.5-inch                    | 2         | 0.46%   |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 2         | 0.46%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 175       | 43.64%  |
| 1366x768 (WXGA)    | 113       | 28.18%  |
| 2560x1440 (QHD)    | 20        | 4.99%   |
| 1600x900 (HD+)     | 19        | 4.74%   |
| 3840x2160 (4K)     | 13        | 3.24%   |
| 1280x800 (WXGA)    | 12        | 2.99%   |
| 1440x900 (WXGA+)   | 7         | 1.75%   |
| 1920x1200 (WUXGA)  | 6         | 1.5%    |
| 3440x1440          | 5         | 1.25%   |
| 2880x1800          | 5         | 1.25%   |
| 1680x1050 (WSXGA+) | 4         | 1%      |
| 3200x1800 (QHD+)   | 3         | 0.75%   |
| 2560x1600          | 2         | 0.5%    |
| 2560x1080          | 2         | 0.5%    |
| 2160x1440          | 2         | 0.5%    |
| 1360x768           | 2         | 0.5%    |
| 1280x1024 (SXGA)   | 2         | 0.5%    |
| 3840x2400          | 1         | 0.25%   |
| 3840x1100          | 1         | 0.25%   |
| 3840x1080          | 1         | 0.25%   |
| 3456x2160          | 1         | 0.25%   |
| 3000x2000          | 1         | 0.25%   |
| 2256x1504          | 1         | 0.25%   |
| 1920x1280          | 1         | 0.25%   |
| 1600x1200          | 1         | 0.25%   |
| 1280x768           | 1         | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 166       | 37.99%  |
| 13      | 77        | 17.62%  |
| 14      | 53        | 12.13%  |
| 17      | 27        | 6.18%   |
| 24      | 20        | 4.58%   |
| 27      | 15        | 3.43%   |
| 23      | 13        | 2.97%   |
| 11      | 11        | 2.52%   |
| 34      | 7         | 1.6%    |
| 21      | 7         | 1.6%    |
| Unknown | 6         | 1.37%   |
| 31      | 5         | 1.14%   |
| 12      | 5         | 1.14%   |
| 19      | 4         | 0.92%   |
| 84      | 3         | 0.69%   |
| 40      | 3         | 0.69%   |
| 48      | 2         | 0.46%   |
| 32      | 2         | 0.46%   |
| 22      | 2         | 0.46%   |
| 18      | 2         | 0.46%   |
| 72      | 1         | 0.23%   |
| 60      | 1         | 0.23%   |
| 54      | 1         | 0.23%   |
| 44      | 1         | 0.23%   |
| 29      | 1         | 0.23%   |
| 20      | 1         | 0.23%   |
| 10      | 1         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 256       | 59.12%  |
| 201-300     | 52        | 12.01%  |
| 501-600     | 44        | 10.16%  |
| 351-400     | 33        | 7.62%   |
| 401-500     | 15        | 3.46%   |
| 701-800     | 9         | 2.08%   |
| 601-700     | 6         | 1.39%   |
| Unknown     | 6         | 1.39%   |
| 1501-2000   | 4         | 0.92%   |
| 1001-1500   | 4         | 0.92%   |
| 801-900     | 3         | 0.69%   |
| 901-1000    | 1         | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 316       | 82.94%  |
| 16/10   | 42        | 11.02%  |
| 21/9    | 7         | 1.84%   |
| 3/2     | 6         | 1.57%   |
| Unknown | 5         | 1.31%   |
| 5/4     | 2         | 0.52%   |
| 4/3     | 1         | 0.26%   |
| 32/9    | 1         | 0.26%   |
| 3.40    | 1         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 165       | 37.93%  |
| 81-90          | 103       | 23.68%  |
| 201-250        | 33        | 7.59%   |
| 71-80          | 26        | 5.98%   |
| 121-130        | 23        | 5.29%   |
| 351-500        | 15        | 3.45%   |
| 301-350        | 15        | 3.45%   |
| 51-60          | 12        | 2.76%   |
| More than 1000 | 7         | 1.61%   |
| 251-300        | 7         | 1.61%   |
| Unknown        | 6         | 1.38%   |
| 61-70          | 5         | 1.15%   |
| 151-200        | 5         | 1.15%   |
| 501-1000       | 5         | 1.15%   |
| 131-140        | 4         | 0.92%   |
| 141-150        | 2         | 0.46%   |
| 41-50          | 1         | 0.23%   |
| 91-100         | 1         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 165       | 38.64%  |
| 101-120       | 131       | 30.68%  |
| 51-100        | 67        | 15.69%  |
| 161-240       | 32        | 7.49%   |
| More than 240 | 17        | 3.98%   |
| 1-50          | 9         | 2.11%   |
| Unknown       | 6         | 1.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 291       | 77.81%  |
| 2     | 66        | 17.65%  |
| 3     | 10        | 2.67%   |
| 0     | 7         | 1.87%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 218       | 36.76%  |
| Realtek Semiconductor                 | 194       | 32.72%  |
| Qualcomm Atheros                      | 80        | 13.49%  |
| Broadcom                              | 30        | 5.06%   |
| Broadcom Limited                      | 14        | 2.36%   |
| Marvell Technology Group              | 7         | 1.18%   |
| Ralink                                | 5         | 0.84%   |
| MediaTek                              | 5         | 0.84%   |
| Hewlett-Packard                       | 5         | 0.84%   |
| ASIX Electronics                      | 4         | 0.67%   |
| JMicron Technology                    | 3         | 0.51%   |
| Huawei Technologies                   | 3         | 0.51%   |
| Xiaomi                                | 2         | 0.34%   |
| TP-Link                               | 2         | 0.34%   |
| Sierra Wireless                       | 2         | 0.34%   |
| Nvidia                                | 2         | 0.34%   |
| Lenovo                                | 2         | 0.34%   |
| DisplayLink                           | 2         | 0.34%   |
| Samsung Electronics                   | 1         | 0.17%   |
| Ralink Technology                     | 1         | 0.17%   |
| Qualcomm Atheros Communications       | 1         | 0.17%   |
| Novatek Microelectronics              | 1         | 0.17%   |
| NetGear                               | 1         | 0.17%   |
| Google                                | 1         | 0.17%   |
| Ericsson Business Mobile Networks     | 1         | 0.17%   |
| Edimax Technology                     | 1         | 0.17%   |
| Dell                                  | 1         | 0.17%   |
| BUFFALO                               | 1         | 0.17%   |
| ASUSTek Computer                      | 1         | 0.17%   |
| Apple                                 | 1         | 0.17%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 119       | 16.86%  |
| Intel Wi-Fi 6 AX200                                               | 35        | 4.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 4.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26        | 3.68%   |
| Intel Wireless 8265 / 8275                                        | 24        | 3.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 17        | 2.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 2.41%   |
| Intel Wireless-AC 9260                                            | 14        | 1.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 12        | 1.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 12        | 1.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11        | 1.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 1.56%   |
| Intel Wireless 7265                                               | 11        | 1.56%   |
| Intel Wireless 8260                                               | 10        | 1.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 10        | 1.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.27%   |
| Intel Wireless 7260                                               | 8         | 1.13%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 1.13%   |
| Broadcom BCM43142 802.11b/g/n                                     | 8         | 1.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 0.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.71%   |
| Intel Wireless 3165                                               | 5         | 0.71%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5         | 0.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.57%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 0.57%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.57%   |
| Intel Centrino Wireless-N 2230                                    | 4         | 0.57%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 4         | 0.57%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 209       | 55.29%  |
| Qualcomm Atheros                      | 64        | 16.93%  |
| Realtek Semiconductor                 | 48        | 12.7%   |
| Broadcom                              | 25        | 6.61%   |
| Broadcom Limited                      | 10        | 2.65%   |
| Ralink                                | 5         | 1.32%   |
| MediaTek                              | 5         | 1.32%   |
| TP-Link                               | 2         | 0.53%   |
| Sierra Wireless                       | 2         | 0.53%   |
| Ralink Technology                     | 1         | 0.26%   |
| Qualcomm Atheros Communications       | 1         | 0.26%   |
| NetGear                               | 1         | 0.26%   |
| Hewlett-Packard                       | 1         | 0.26%   |
| Edimax Technology                     | 1         | 0.26%   |
| BUFFALO                               | 1         | 0.26%   |
| ASUSTek Computer                      | 1         | 0.26%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 35        | 9.23%   |
| Intel Wireless 8265 / 8275                                     | 24        | 6.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 17        | 4.49%   |
| Intel Wireless-AC 9260                                         | 14        | 3.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 12        | 3.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 12        | 3.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11        | 2.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 2.9%    |
| Intel Wireless 7265                                            | 11        | 2.9%    |
| Intel Wireless 8260                                            | 10        | 2.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 10        | 2.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 2.37%   |
| Intel Wireless 7260                                            | 8         | 2.11%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 2.11%   |
| Broadcom BCM43142 802.11b/g/n                                  | 8         | 2.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 7         | 1.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 7         | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 6         | 1.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 1.58%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 1.58%   |
| Intel Wireless 3165                                            | 5         | 1.32%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 5         | 1.32%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 5         | 1.32%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 1.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 1.06%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 1.06%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 4         | 1.06%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 4         | 1.06%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 0.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 0.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 0.79%   |
| Realtek 802.11n WLAN Adapter                                   | 3         | 0.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.79%   |
| Intel WiFi Link 5100                                           | 3         | 0.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 0.79%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 0.79%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 0.79%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 176       | 56.96%  |
| Intel                    | 68        | 22.01%  |
| Qualcomm Atheros         | 23        | 7.44%   |
| Broadcom                 | 11        | 3.56%   |
| Marvell Technology Group | 7         | 2.27%   |
| Broadcom Limited         | 4         | 1.29%   |
| ASIX Electronics         | 4         | 1.29%   |
| JMicron Technology       | 3         | 0.97%   |
| Xiaomi                   | 2         | 0.65%   |
| Nvidia                   | 2         | 0.65%   |
| Lenovo                   | 2         | 0.65%   |
| Hewlett-Packard          | 2         | 0.65%   |
| DisplayLink              | 2         | 0.65%   |
| Samsung Electronics      | 1         | 0.32%   |
| Google                   | 1         | 0.32%   |
| Apple                    | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 119       | 37.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 29        | 9.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 26        | 8.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 17        | 5.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 2.19%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 1.88%   |
| Intel Ethernet Connection (4) I219-LM                                          | 6         | 1.88%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 5         | 1.57%   |
| Intel Ethernet Connection (6) I219-V                                           | 5         | 1.57%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.25%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4         | 1.25%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 1.25%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 4         | 1.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 3         | 0.94%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.94%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 0.94%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 0.94%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 0.94%   |
| Intel Ethernet Connection (6) I219-LM                                          | 3         | 0.94%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 0.94%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 0.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.63%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.63%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.63%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 0.63%   |
| Intel Ethernet Connection (7) I219-V                                           | 2         | 0.63%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.63%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.63%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.63%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 2         | 0.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.63%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.31%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.31%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.31%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.31%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 360       | 54.46%  |
| Ethernet | 293       | 44.33%  |
| Modem    | 8         | 1.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 310       | 80.31%  |
| Ethernet | 76        | 19.69%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 272       | 74.32%  |
| 1     | 84        | 22.95%  |
| 0     | 9         | 2.46%   |
| 3     | 1         | 0.27%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 302       | 81.62%  |
| Yes  | 68        | 18.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 169       | 54.52%  |
| Qualcomm Atheros Communications | 29        | 9.35%   |
| Realtek Semiconductor           | 23        | 7.42%   |
| Broadcom                        | 17        | 5.48%   |
| Apple                           | 12        | 3.87%   |
| Foxconn / Hon Hai               | 11        | 3.55%   |
| IMC Networks                    | 10        | 3.23%   |
| Lite-On Technology              | 9         | 2.9%    |
| Dell                            | 8         | 2.58%   |
| Hewlett-Packard                 | 5         | 1.61%   |
| Realtek                         | 4         | 1.29%   |
| Ralink                          | 3         | 0.97%   |
| Toshiba                         | 2         | 0.65%   |
| Foxconn International           | 2         | 0.65%   |
| Cambridge Silicon Radio         | 2         | 0.65%   |
| Smart Modular Technologies      | 1         | 0.32%   |
| MediaTek                        | 1         | 0.32%   |
| Integrated System Solution      | 1         | 0.32%   |
| Belkin Components               | 1         | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 62        | 20%     |
| Intel AX200 Bluetooth                                                               | 33        | 10.65%  |
| Intel AX201 Bluetooth                                                               | 27        | 8.71%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 19        | 6.13%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 16        | 5.16%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 14        | 4.52%   |
| Realtek Bluetooth Radio                                                             | 11        | 3.55%   |
| Dell DW375 Bluetooth Module                                                         | 7         | 2.26%   |
| Apple Bluetooth Host Controller                                                     | 7         | 2.26%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 1.94%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 1.61%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 1.61%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 1.61%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 1.29%   |
| Realtek Bluetooth Radio                                                             | 4         | 1.29%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 1.29%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 1.29%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 1.29%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 0.97%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 0.97%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 0.97%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 0.97%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.65%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.65%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 0.65%   |
| Intel AX210 Bluetooth                                                               | 2         | 0.65%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.65%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.65%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.65%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.65%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.65%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.65%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 0.65%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.65%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 2         | 0.65%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.65%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 308       | 67.25%  |
| Nvidia                 | 60        | 13.1%   |
| AMD                    | 56        | 12.23%  |
| Realtek Semiconductor  | 7         | 1.53%   |
| Logitech               | 3         | 0.66%   |
| GN Netcom              | 3         | 0.66%   |
| Plantronics            | 2         | 0.44%   |
| Kingston Technology    | 2         | 0.44%   |
| C-Media Electronics    | 2         | 0.44%   |
| XMOS                   | 1         | 0.22%   |
| Samson Technologies    | 1         | 0.22%   |
| Razer USA              | 1         | 0.22%   |
| No brand               | 1         | 0.22%   |
| LINE TECH INDUSTRIAL   | 1         | 0.22%   |
| Lenovo                 | 1         | 0.22%   |
| JMTek                  | 1         | 0.22%   |
| Hewlett-Packard        | 1         | 0.22%   |
| GYROCOM C&C            | 1         | 0.22%   |
| Generalplus Technology | 1         | 0.22%   |
| DSEA A/S               | 1         | 0.22%   |
| Conexant Systems       | 1         | 0.22%   |
| CMX Systems            | 1         | 0.22%   |
| Cambridge Audio        | 1         | 0.22%   |
| Apple                  | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 49        | 9.12%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 32        | 5.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 31        | 5.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 25        | 4.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 25        | 4.66%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 18        | 3.35%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 18        | 3.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 16        | 2.98%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 14        | 2.61%   |
| Intel Broadwell-U Audio Controller                                                                | 14        | 2.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 2.42%   |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 2.42%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 2.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 2.23%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 2.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 2.05%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 1.86%   |
| Intel Comet Lake PCH cAVS                                                                         | 10        | 1.86%   |
| Intel CM238 HD Audio Controller                                                                   | 10        | 1.86%   |
| AMD FCH Azalia Controller                                                                         | 10        | 1.86%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 9         | 1.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 1.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 1.49%   |
| Realtek Semiconductor USB Audio                                                                   | 7         | 1.3%    |
| Nvidia GA106 High Definition Audio Controller                                                     | 7         | 1.3%    |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.3%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 1.12%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.12%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 0.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.93%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 0.74%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 85        | 34%     |
| SK hynix            | 59        | 23.6%   |
| Micron Technology   | 28        | 11.2%   |
| Kingston            | 18        | 7.2%    |
| Ramaxel Technology  | 11        | 4.4%    |
| Unknown             | 10        | 4%      |
| Crucial             | 10        | 4%      |
| Unknown (ABCD)      | 4         | 1.6%    |
| Elpida              | 3         | 1.2%    |
| Corsair             | 3         | 1.2%    |
| A-DATA Technology   | 3         | 1.2%    |
| Teikon              | 2         | 0.8%    |
| Smart               | 2         | 0.8%    |
| Unknown             | 2         | 0.8%    |
| Smart Brazil        | 1         | 0.4%    |
| PNY                 | 1         | 0.4%    |
| Patriot             | 1         | 0.4%    |
| Nanya Technology    | 1         | 0.4%    |
| Kingmax             | 1         | 0.4%    |
| Goldkey             | 1         | 0.4%    |
| fef5                | 1         | 0.4%    |
| Cors                | 1         | 0.4%    |
| ASint Technology    | 1         | 0.4%    |
| 8945000080AD        | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 8         | 3.01%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 2.26%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 1.88%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 1.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 1.88%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 1.88%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 1.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.5%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 4         | 1.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 1.5%    |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 3         | 1.13%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 3         | 1.13%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 1.13%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 1.13%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 3         | 1.13%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 3         | 1.13%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 3         | 1.13%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 3         | 1.13%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 3         | 1.13%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                    | 2         | 0.75%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.75%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.75%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                    | 2         | 0.75%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.75%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.75%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 2         | 0.75%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.75%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 0.75%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 2         | 0.75%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.75%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.75%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.75%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.75%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.75%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.75%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.75%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 2         | 0.75%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.75%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 2         | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 113       | 52.8%   |
| DDR3    | 69        | 32.24%  |
| LPDDR4  | 11        | 5.14%   |
| LPDDR3  | 10        | 4.67%   |
| SDRAM   | 3         | 1.4%    |
| DDR2    | 3         | 1.4%    |
| Unknown | 3         | 1.4%    |
| DDR5    | 1         | 0.47%   |
| DDR     | 1         | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 189       | 90%     |
| Row Of Chips | 18        | 8.57%   |
| Unknown      | 2         | 0.95%   |
| Chip         | 1         | 0.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 85        | 37.12%  |
| 4096  | 73        | 31.88%  |
| 16384 | 36        | 15.72%  |
| 2048  | 16        | 6.99%   |
| 32768 | 15        | 6.55%   |
| 1024  | 4         | 1.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 61        | 25.52%  |
| 1600    | 49        | 20.5%   |
| 3200    | 35        | 14.64%  |
| 2400    | 20        | 8.37%   |
| 2133    | 20        | 8.37%   |
| 1334    | 10        | 4.18%   |
| 1333    | 10        | 4.18%   |
| 3266    | 5         | 2.09%   |
| 1067    | 5         | 2.09%   |
| Unknown | 4         | 1.67%   |
| 8400    | 3         | 1.26%   |
| 4267    | 3         | 1.26%   |
| 4199    | 3         | 1.26%   |
| 1867    | 3         | 1.26%   |
| 667     | 3         | 1.26%   |
| 4800    | 1         | 0.42%   |
| 4266    | 1         | 0.42%   |
| 3733    | 1         | 0.42%   |
| 1066    | 1         | 0.42%   |
| 533     | 1         | 0.42%   |

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
| Chicony Electronics                    | 95        | 29.14%  |
| IMC Networks                           | 31        | 9.51%   |
| Acer                                   | 31        | 9.51%   |
| Sunplus Innovation Technology          | 28        | 8.59%   |
| Realtek Semiconductor                  | 28        | 8.59%   |
| Microdia                               | 23        | 7.06%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 3.68%   |
| Syntek                                 | 11        | 3.37%   |
| Suyin                                  | 10        | 3.07%   |
| Apple                                  | 10        | 3.07%   |
| Quanta                                 | 9         | 2.76%   |
| Silicon Motion                         | 6         | 1.84%   |
| Luxvisions Innotech Limited            | 5         | 1.53%   |
| Lite-On Technology                     | 4         | 1.23%   |
| Ricoh                                  | 3         | 0.92%   |
| Alcor Micro                            | 3         | 0.92%   |
| Logitech                               | 2         | 0.61%   |
| Bison Electronics                      | 2         | 0.61%   |
| Unknown                                | 2         | 0.61%   |
| Z-Star Microelectronics                | 1         | 0.31%   |
| USB Camera                             | 1         | 0.31%   |
| Sonix Technology                       | 1         | 0.31%   |
| Samsung Electronics                    | 1         | 0.31%   |
| Primax Electronics                     | 1         | 0.31%   |
| Polycom                                | 1         | 0.31%   |
| LG Electronics                         | 1         | 0.31%   |
| Importek                               | 1         | 0.31%   |
| Generalplus Technology                 | 1         | 0.31%   |
| Denron                                 | 1         | 0.31%   |
| Creative Technology                    | 1         | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony USB2.0 Camera                                                      | 18        | 5.52%   |
| Chicony HD Webcam                                                          | 14        | 4.29%   |
| Microdia Integrated_Webcam_HD                                              | 11        | 3.37%   |
| Chicony Integrated Camera                                                  | 11        | 3.37%   |
| Realtek Integrated_Webcam_HD                                               | 9         | 2.76%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 9         | 2.76%   |
| IMC Networks Integrated Camera                                             | 9         | 2.76%   |
| Chicony HP HD Camera                                                       | 6         | 1.84%   |
| Acer HD Webcam                                                             | 6         | 1.84%   |
| Acer BisonCam,NB Pro                                                       | 6         | 1.84%   |
| Syntek Integrated Camera                                                   | 5         | 1.53%   |
| Sunplus HD WebCam                                                          | 5         | 1.53%   |
| Chicony Integrated IR Camera                                               | 5         | 1.53%   |
| Acer Integrated Camera                                                     | 5         | 1.53%   |
| Sunplus Integrated_Webcam_HD                                               | 4         | 1.23%   |
| IMC Networks VGA UVC WebCam                                                | 4         | 1.23%   |
| Apple FaceTime HD Camera                                                   | 4         | 1.23%   |
| Sunplus Asus Webcam                                                        | 3         | 0.92%   |
| Realtek USB2.0 HD UVC WebCam                                               | 3         | 0.92%   |
| Realtek Lenovo EasyCamera                                                  | 3         | 0.92%   |
| Realtek Integrated Webcam                                                  | 3         | 0.92%   |
| Realtek HD WebCam                                                          | 3         | 0.92%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 0.92%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 3         | 0.92%   |
| Chicony Integrated Camera [ThinkPad]                                       | 3         | 0.92%   |
| Chicony Integrated Camera (1280x720@30)                                    | 3         | 0.92%   |
| Chicony EasyCamera                                                         | 3         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 3         | 0.92%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 3         | 0.92%   |
| Acer SunplusIT Integrated Camera                                           | 3         | 0.92%   |
| Acer EasyCamera                                                            | 3         | 0.92%   |
| Acer BisonCam, NB Pro                                                      | 3         | 0.92%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 0.61%   |
| Syntek EasyCamera                                                          | 2         | 0.61%   |
| Suyin USB 2.0 Camera                                                       | 2         | 0.61%   |
| Suyin HP Truevision HD                                                     | 2         | 0.61%   |
| Sunplus USB Camera                                                         | 2         | 0.61%   |
| Sunplus Lenovo EasyCamera                                                  | 2         | 0.61%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 2         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 28        | 35.44%  |
| Validity Sensors           | 25        | 31.65%  |
| Shenzhen Goodix Technology | 12        | 15.19%  |
| LighTuning Technology      | 7         | 8.86%   |
| Elan Microelectronics      | 4         | 5.06%   |
| AuthenTec                  | 3         | 3.8%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 9         | 11.39%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 10.13%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 10.13%  |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 6.33%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.06%   |
| Synaptics WBDI Device                                                      | 4         | 5.06%   |
| Elan ELAN:Fingerprint                                                      | 4         | 5.06%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 3.8%    |
| Synaptics UWP WBDI                                                         | 3         | 3.8%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 3.8%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 3.8%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 3.8%    |
| Unknown                                                                    | 3         | 3.8%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.53%   |
| Validity Sensors VFS491                                                    | 2         | 2.53%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 2.53%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.53%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 2.53%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.27%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.27%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.27%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.27%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.27%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.27%   |
| AuthenTec AES2810                                                          | 1         | 1.27%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.27%   |
| AuthenTec AES1600                                                          | 1         | 1.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 13        | 50%     |
| Upek                  | 5         | 19.23%  |
| Alcor Micro           | 5         | 19.23%  |
| Lenovo                | 2         | 7.69%   |
| Gemalto (was Gemplus) | 1         | 3.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 23.08%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 19.23%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 19.23%  |
| Broadcom 5880                                                                | 4         | 15.38%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 7.69%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 3.85%   |
| Broadcom 58200                                                               | 1         | 3.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 208       | 56.22%  |
| 1     | 124       | 33.51%  |
| 2     | 31        | 8.38%   |
| 3     | 4         | 1.08%   |
| 6     | 1         | 0.27%   |
| 5     | 1         | 0.27%   |
| 4     | 1         | 0.27%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 78        | 39.39%  |
| Graphics card            | 33        | 16.67%  |
| Chipcard                 | 25        | 12.63%  |
| Communication controller | 17        | 8.59%   |
| Net/wireless             | 16        | 8.08%   |
| Multimedia controller    | 6         | 3.03%   |
| Camera                   | 6         | 3.03%   |
| Bluetooth                | 5         | 2.53%   |
| Storage                  | 4         | 2.02%   |
| Sound                    | 4         | 2.02%   |
| Card reader              | 3         | 1.52%   |
| Net/ethernet             | 1         | 0.51%   |

