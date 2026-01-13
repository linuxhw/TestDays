OpenMandriva 24.07 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 24.07.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 652

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | PORTEGE R930                | [c424552903](https://linux-hardware.org/?probe=c424552903) | Dec 31, 2025 |
| ASUSTek       | UL30A                       | [f53a318199](https://linux-hardware.org/?probe=f53a318199) | Dec 30, 2025 |
| Dell          | System Inspiron N7110       | [c5c2861973](https://linux-hardware.org/?probe=c5c2861973) | Dec 27, 2025 |
| Medion        | Akoya E1317T                | [b27563db99](https://linux-hardware.org/?probe=b27563db99) | Dec 24, 2025 |
| Lenovo        | ThinkPad X220 4291CF3       | [3dbf7f1b45](https://linux-hardware.org/?probe=3dbf7f1b45) | Dec 03, 2025 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [1c5ef6c390](https://linux-hardware.org/?probe=1c5ef6c390) | Oct 27, 2025 |
| Lenovo        | IdeaPad Slim 3 14IAH8 83... | [da6c2342bc](https://linux-hardware.org/?probe=da6c2342bc) | Oct 04, 2025 |
| Sony          | VGN-CR260FE                 | [ad507d5c9b](https://linux-hardware.org/?probe=ad507d5c9b) | Sep 29, 2025 |
| Toshiba       | QOSMIO X505                 | [4f200a13ce](https://linux-hardware.org/?probe=4f200a13ce) | Sep 12, 2025 |
| HP            | Compaq Presario C700        | [37ccee051c](https://linux-hardware.org/?probe=37ccee051c) | Sep 04, 2025 |
| HP            | OMEN by Gaming Laptop 16... | [8499ae4538](https://linux-hardware.org/?probe=8499ae4538) | Aug 27, 2025 |
| Lenovo        | B575e 36852DG               | [4459e655aa](https://linux-hardware.org/?probe=4459e655aa) | Aug 18, 2025 |
| Samsung       | 550XED                      | [9f5414b8d1](https://linux-hardware.org/?probe=9f5414b8d1) | Aug 17, 2025 |
| Dell          | Inspiron 3520               | [18da1c823c](https://linux-hardware.org/?probe=18da1c823c) | Aug 14, 2025 |
| Toshiba       | Satellite A505              | [92e88e3d4b](https://linux-hardware.org/?probe=92e88e3d4b) | Aug 03, 2025 |
| HP            | ProBook 6475b               | [dcf341be09](https://linux-hardware.org/?probe=dcf341be09) | Aug 02, 2025 |
| Dell          | Latitude E5550              | [8fedc01826](https://linux-hardware.org/?probe=8fedc01826) | Jul 28, 2025 |
| HP            | ProBook 4510s               | [9ac1f88828](https://linux-hardware.org/?probe=9ac1f88828) | Jul 11, 2025 |
| ADVAN         | 1701                        | [2bd256412d](https://linux-hardware.org/?probe=2bd256412d) | Jul 03, 2025 |
| Dell          | Latitude 3350               | [b90cb489b8](https://linux-hardware.org/?probe=b90cb489b8) | Jun 28, 2025 |
| Lenovo        | 3000 N200 0769AL3           | [1cc8a86b76](https://linux-hardware.org/?probe=1cc8a86b76) | May 29, 2025 |
| MSI           | CR420                       | [81e0b6440d](https://linux-hardware.org/?probe=81e0b6440d) | May 27, 2025 |
| HUAWEI        | CREM-WXX9                   | [b9bf8b478c](https://linux-hardware.org/?probe=b9bf8b478c) | May 25, 2025 |
| Dell          | Studio 1558                 | [754114fb85](https://linux-hardware.org/?probe=754114fb85) | May 20, 2025 |
| HP            | Notebook                    | [6c92df3ba8](https://linux-hardware.org/?probe=6c92df3ba8) | May 18, 2025 |
| Toshiba       | Satellite L350              | [5dd08a2183](https://linux-hardware.org/?probe=5dd08a2183) | May 18, 2025 |
| HP            | Pavilion dv5000 (EP420UA... | [319bce7241](https://linux-hardware.org/?probe=319bce7241) | May 14, 2025 |
| Acer          | Aspire E1-531G              | [324de60ab6](https://linux-hardware.org/?probe=324de60ab6) | May 02, 2025 |
| Lenovo        | V14 G2 ALC 82KC             | [79ed7c1999](https://linux-hardware.org/?probe=79ed7c1999) | Apr 26, 2025 |
| Acer          | Aspire R3-131T              | [a1db17949f](https://linux-hardware.org/?probe=a1db17949f) | Apr 20, 2025 |
| ASUSTek       | K52JT                       | [3a3eb9d804](https://linux-hardware.org/?probe=3a3eb9d804) | Apr 08, 2025 |
| HP            | 246                         | [61f81892b6](https://linux-hardware.org/?probe=61f81892b6) | Mar 31, 2025 |
| Lenovo        | IdeaPad Slim 3 14IAH8 83... | [2dfc01251f](https://linux-hardware.org/?probe=2dfc01251f) | Mar 29, 2025 |
| Lenovo        | ThinkPad Edge 32597AU       | [af33317fc3](https://linux-hardware.org/?probe=af33317fc3) | Mar 27, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [002a8d7441](https://linux-hardware.org/?probe=002a8d7441) | Mar 27, 2025 |
| Dell          | Inspiron 3585               | [5bd9576c9e](https://linux-hardware.org/?probe=5bd9576c9e) | Mar 13, 2025 |
| Toshiba       | Satellite S45-A             | [e8f5280666](https://linux-hardware.org/?probe=e8f5280666) | Mar 02, 2025 |
| Acer          | Aspire V3-771               | [e360a517f2](https://linux-hardware.org/?probe=e360a517f2) | Feb 27, 2025 |
| Lenovo        | ThinkPad Edge E530 3259H... | [d282936889](https://linux-hardware.org/?probe=d282936889) | Feb 26, 2025 |
| Dell          | Inspiron 1764               | [ee1147d849](https://linux-hardware.org/?probe=ee1147d849) | Feb 20, 2025 |
| ASUSTek       | A7U                         | [ad4ef35c3a](https://linux-hardware.org/?probe=ad4ef35c3a) | Feb 13, 2025 |
| Dell          | Inspiron 5520               | [7f66df86bd](https://linux-hardware.org/?probe=7f66df86bd) | Feb 10, 2025 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [dbecb935af](https://linux-hardware.org/?probe=dbecb935af) | Feb 04, 2025 |
| Haier         | U1520HD                     | [fed3f845d0](https://linux-hardware.org/?probe=fed3f845d0) | Feb 02, 2025 |
| Fujitsu       | LIFEBOOK U904               | [c563f0f3c9](https://linux-hardware.org/?probe=c563f0f3c9) | Jan 17, 2025 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [fb088c26c9](https://linux-hardware.org/?probe=fb088c26c9) | Jan 16, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [195b1e2d7e](https://linux-hardware.org/?probe=195b1e2d7e) | Jan 07, 2025 |
| HP            | ProBook 455 G8 Notebook ... | [963fcdd477](https://linux-hardware.org/?probe=963fcdd477) | Jan 06, 2025 |
| HP            | ProBook 640 G1              | [f901f7b9aa](https://linux-hardware.org/?probe=f901f7b9aa) | Jan 03, 2025 |
| Dell          | Latitude 5300               | [d3d6e520f5](https://linux-hardware.org/?probe=d3d6e520f5) | Jan 03, 2025 |
| Infinix       | Y3 Plus                     | [a5d0c097a5](https://linux-hardware.org/?probe=a5d0c097a5) | Dec 30, 2024 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [145b300a77](https://linux-hardware.org/?probe=145b300a77) | Dec 26, 2024 |
| Dell          | Inspiron 1525               | [cd4f5695b9](https://linux-hardware.org/?probe=cd4f5695b9) | Dec 22, 2024 |
| ASUSTek       | S451LA                      | [a766d0caae](https://linux-hardware.org/?probe=a766d0caae) | Dec 19, 2024 |
| Sony          | VPCEH39FJ                   | [f0627de40e](https://linux-hardware.org/?probe=f0627de40e) | Dec 16, 2024 |
| Dell          | Latitude E6500              | [1c4c62551f](https://linux-hardware.org/?probe=1c4c62551f) | Dec 14, 2024 |
| ASUSTek       | G60JX                       | [b1cc4820a3](https://linux-hardware.org/?probe=b1cc4820a3) | Dec 13, 2024 |
| HP            | 620                         | [152ec63b24](https://linux-hardware.org/?probe=152ec63b24) | Dec 12, 2024 |
| Sony          | VPCEJ2E1E                   | [11625e4a3c](https://linux-hardware.org/?probe=11625e4a3c) | Dec 12, 2024 |
| Dell          | Latitude E6440              | [c3aebd55c6](https://linux-hardware.org/?probe=c3aebd55c6) | Dec 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [4a452b8790](https://linux-hardware.org/?probe=4a452b8790) | Dec 11, 2024 |
| ASUSTek       | X550JX                      | [825a9b88c3](https://linux-hardware.org/?probe=825a9b88c3) | Dec 11, 2024 |
| HP            | Laptop 17-cp0xxx            | [3730405110](https://linux-hardware.org/?probe=3730405110) | Dec 11, 2024 |
| HP            | ProBook 4530s               | [e8e3959577](https://linux-hardware.org/?probe=e8e3959577) | Dec 11, 2024 |
| Notebook      | 14M2                        | [30b428ea7b](https://linux-hardware.org/?probe=30b428ea7b) | Dec 11, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [986d807d00](https://linux-hardware.org/?probe=986d807d00) | Dec 10, 2024 |
| Dell          | Inspiron 15 3515            | [a073fbc9bc](https://linux-hardware.org/?probe=a073fbc9bc) | Dec 10, 2024 |
| Acer          | Aspire A315-24P             | [a632326872](https://linux-hardware.org/?probe=a632326872) | Dec 09, 2024 |
| HP            | EliteBook 820 G4            | [180e325043](https://linux-hardware.org/?probe=180e325043) | Dec 09, 2024 |
| ASUSTek       | Z450LA                      | [2281fa41ae](https://linux-hardware.org/?probe=2281fa41ae) | Dec 08, 2024 |
| Lenovo        | ThinkPad T410 2537K96       | [ae6d2e915b](https://linux-hardware.org/?probe=ae6d2e915b) | Dec 06, 2024 |
| HP            | Unknown                     | [c5d5bb8ffc](https://linux-hardware.org/?probe=c5d5bb8ffc) | Dec 06, 2024 |
| ASUSTek       | X550CC                      | [c395078c21](https://linux-hardware.org/?probe=c395078c21) | Dec 05, 2024 |
| Lenovo        | ThinkPad T480s 20L8SF100... | [e33bd93e90](https://linux-hardware.org/?probe=e33bd93e90) | Dec 04, 2024 |
| HP            | EliteBook 850 G6            | [af2a2b7059](https://linux-hardware.org/?probe=af2a2b7059) | Dec 04, 2024 |
| ASUSTek       | K52JK                       | [1e978f8201](https://linux-hardware.org/?probe=1e978f8201) | Dec 03, 2024 |
| Toshiba       | Satellite S70-A             | [fdbc12af06](https://linux-hardware.org/?probe=fdbc12af06) | Dec 03, 2024 |
| HP            | Pavilion dv6                | [f72bd7ca67](https://linux-hardware.org/?probe=f72bd7ca67) | Dec 03, 2024 |
| Fujitsu       | FMVA42MW2                   | [a5a7a4a6f1](https://linux-hardware.org/?probe=a5a7a4a6f1) | Dec 03, 2024 |
| Acer          | Nitro ANV15-51              | [ac43db5c18](https://linux-hardware.org/?probe=ac43db5c18) | Dec 02, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [83800e0dd2](https://linux-hardware.org/?probe=83800e0dd2) | Dec 01, 2024 |
| HP            | EliteBook 850 G5            | [39d29e9e31](https://linux-hardware.org/?probe=39d29e9e31) | Nov 30, 2024 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [c7fb17104d](https://linux-hardware.org/?probe=c7fb17104d) | Nov 29, 2024 |
| Acer          | Aspire A315-34              | [16257c3b4b](https://linux-hardware.org/?probe=16257c3b4b) | Nov 27, 2024 |
| Acer          | Aspire ES1-512              | [dfc7a551d9](https://linux-hardware.org/?probe=dfc7a551d9) | Nov 26, 2024 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [d208c8829e](https://linux-hardware.org/?probe=d208c8829e) | Nov 24, 2024 |
| Google        | Lillipup rev3               | [26051de0da](https://linux-hardware.org/?probe=26051de0da) | Nov 24, 2024 |
| Dell          | Latitude D630               | [135fedf2cd](https://linux-hardware.org/?probe=135fedf2cd) | Nov 22, 2024 |
| HP            | 240 G8 Notebook PC          | [33374fdc29](https://linux-hardware.org/?probe=33374fdc29) | Nov 22, 2024 |
| Itautec       | Infoway                     | [466651a218](https://linux-hardware.org/?probe=466651a218) | Nov 21, 2024 |
| Unknown       | AX16PRO                     | [97a667e749](https://linux-hardware.org/?probe=97a667e749) | Nov 21, 2024 |
| HP            | Laptop 15-dw0xxx            | [00fc7a8d8b](https://linux-hardware.org/?probe=00fc7a8d8b) | Nov 21, 2024 |
| Dell          | Latitude 5490               | [50f3de2c58](https://linux-hardware.org/?probe=50f3de2c58) | Nov 21, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [b3d142c510](https://linux-hardware.org/?probe=b3d142c510) | Nov 21, 2024 |
| Lenovo        | Legion 5 15ARH05 82B5       | [69a4d1cdc5](https://linux-hardware.org/?probe=69a4d1cdc5) | Nov 21, 2024 |
| Acer          | Aspire A515-48M             | [7e76e833e3](https://linux-hardware.org/?probe=7e76e833e3) | Nov 20, 2024 |
| HP            | Laptop 15g-br1xx            | [f51b7c2e9d](https://linux-hardware.org/?probe=f51b7c2e9d) | Nov 20, 2024 |
| HP            | EliteBook 840 G6            | [9dfd49751f](https://linux-hardware.org/?probe=9dfd49751f) | Nov 19, 2024 |
| Lenovo        | ThinkPad X61 7675CTO        | [772ab308c2](https://linux-hardware.org/?probe=772ab308c2) | Nov 19, 2024 |
| Toshiba       | Satellite U845t             | [a73248a89d](https://linux-hardware.org/?probe=a73248a89d) | Nov 18, 2024 |
| Dell          | Latitude 3420               | [9db39167d7](https://linux-hardware.org/?probe=9db39167d7) | Nov 17, 2024 |
| Lenovo        | ThinkPad Edge E530c 3366... | [06da77f5c0](https://linux-hardware.org/?probe=06da77f5c0) | Nov 16, 2024 |
| HP            | EliteBook 2730p             | [5ce55a50da](https://linux-hardware.org/?probe=5ce55a50da) | Nov 15, 2024 |
| Dell          | Inspiron 3505               | [42bed8b241](https://linux-hardware.org/?probe=42bed8b241) | Nov 14, 2024 |
| ASUSTek       | 1018P                       | [eef1555906](https://linux-hardware.org/?probe=eef1555906) | Nov 13, 2024 |
| Dell          | Precision M6700             | [81ed3cc9db](https://linux-hardware.org/?probe=81ed3cc9db) | Nov 13, 2024 |
| Acer          | Aspire 5742G                | [46d5cbc974](https://linux-hardware.org/?probe=46d5cbc974) | Nov 13, 2024 |
| Acer          | Aspire 5250                 | [6afaf552dd](https://linux-hardware.org/?probe=6afaf552dd) | Nov 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M370... | [d655b85ff6](https://linux-hardware.org/?probe=d655b85ff6) | Nov 12, 2024 |
| Samsung       | R510/P510                   | [45941aa5d5](https://linux-hardware.org/?probe=45941aa5d5) | Nov 11, 2024 |
| Dell          | Vostro 1310                 | [add2298606](https://linux-hardware.org/?probe=add2298606) | Nov 11, 2024 |
| Fujitsu       | FMVC07003                   | [9fe5e42140](https://linux-hardware.org/?probe=9fe5e42140) | Nov 10, 2024 |
| Lenovo        | ThinkPad L440 20ASS11T00    | [9e63659c87](https://linux-hardware.org/?probe=9e63659c87) | Nov 09, 2024 |
| Apple         | MacBookPro6,1               | [24c0858a39](https://linux-hardware.org/?probe=24c0858a39) | Nov 09, 2024 |
| Dell          | Inspiron 3520               | [e129134b01](https://linux-hardware.org/?probe=e129134b01) | Nov 08, 2024 |
| ASUSTek       | X550CA                      | [9de1e927a9](https://linux-hardware.org/?probe=9de1e927a9) | Nov 07, 2024 |
| ASUSTek       | E202SA                      | [18a63b065d](https://linux-hardware.org/?probe=18a63b065d) | Nov 07, 2024 |
| Acer          | Swift SF314-43              | [c55af0c24c](https://linux-hardware.org/?probe=c55af0c24c) | Nov 07, 2024 |
| Lenovo        | ThinkPad L420 7829GH2       | [33efc8a835](https://linux-hardware.org/?probe=33efc8a835) | Nov 07, 2024 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [b0ca914a02](https://linux-hardware.org/?probe=b0ca914a02) | Nov 06, 2024 |
| Positivo      | C14CU51                     | [910164dc5c](https://linux-hardware.org/?probe=910164dc5c) | Nov 06, 2024 |
| HP            | Pavilion g4                 | [2f7cb31cab](https://linux-hardware.org/?probe=2f7cb31cab) | Nov 06, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [689c7827b7](https://linux-hardware.org/?probe=689c7827b7) | Nov 06, 2024 |
| Lenovo        | ThinkPad T420 4180CC4       | [f3899bf09d](https://linux-hardware.org/?probe=f3899bf09d) | Nov 04, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [4cab1133bf](https://linux-hardware.org/?probe=4cab1133bf) | Nov 04, 2024 |
| Lenovo        | ThinkPad X230 23256V1       | [08af8a55a1](https://linux-hardware.org/?probe=08af8a55a1) | Nov 03, 2024 |
| Fujitsu       | LIFEBOOK E743               | [be7c6d7a43](https://linux-hardware.org/?probe=be7c6d7a43) | Nov 03, 2024 |
| Toshiba       | TECRA A10                   | [f7cfa0f796](https://linux-hardware.org/?probe=f7cfa0f796) | Nov 02, 2024 |
| HP            | Laptop 17-ca1xxx            | [860ef2c633](https://linux-hardware.org/?probe=860ef2c633) | Nov 01, 2024 |
| Apple         | MacBookPro8,1               | [5c2dacf3d8](https://linux-hardware.org/?probe=5c2dacf3d8) | Nov 01, 2024 |
| Acer          | Aspire 7736                 | [9426ed7aff](https://linux-hardware.org/?probe=9426ed7aff) | Nov 01, 2024 |
| Lenovo        | IdeaPad Y400 20192          | [af8c167505](https://linux-hardware.org/?probe=af8c167505) | Oct 31, 2024 |
| Sony          | SVF1521G6EW                 | [5b4ce22a73](https://linux-hardware.org/?probe=5b4ce22a73) | Oct 31, 2024 |
| HP            | EliteBook 660 16 inch G1... | [7de8e9c733](https://linux-hardware.org/?probe=7de8e9c733) | Oct 29, 2024 |
| Acer          | Aspire A315-59              | [ef0b873549](https://linux-hardware.org/?probe=ef0b873549) | Oct 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | [a8f6e54a85](https://linux-hardware.org/?probe=a8f6e54a85) | Oct 29, 2024 |
| ASUSTek       | X553MA                      | [ea7d1235b1](https://linux-hardware.org/?probe=ea7d1235b1) | Oct 28, 2024 |
| Samsung       | RV420/RV520/RV720/E3530/... | [862c7cc007](https://linux-hardware.org/?probe=862c7cc007) | Oct 27, 2024 |
| HP            | Unknown                     | [f8c7a5f55f](https://linux-hardware.org/?probe=f8c7a5f55f) | Oct 27, 2024 |
| HP            | Laptop 15-ef2xxx            | [b4a0691988](https://linux-hardware.org/?probe=b4a0691988) | Oct 27, 2024 |
| Lenovo        | ThinkPad E16 Gen 2 21M5C... | [5a31a97e2b](https://linux-hardware.org/?probe=5a31a97e2b) | Oct 26, 2024 |
| Acer          | Aspire E5-571G              | [0801976824](https://linux-hardware.org/?probe=0801976824) | Oct 26, 2024 |
| HP            | 15                          | [6a2e246381](https://linux-hardware.org/?probe=6a2e246381) | Oct 25, 2024 |
| Lenovo        | ThinkPad P51 20HJS52P00     | [ab7bfcceb7](https://linux-hardware.org/?probe=ab7bfcceb7) | Oct 24, 2024 |
| Acer          | Aspire 7736                 | [213995eb9a](https://linux-hardware.org/?probe=213995eb9a) | Oct 24, 2024 |
| Lenovo        | G50-80 80E5                 | [38f6fb752d](https://linux-hardware.org/?probe=38f6fb752d) | Oct 23, 2024 |
| HP            | Pavilion 17                 | [fe2ac723ed](https://linux-hardware.org/?probe=fe2ac723ed) | Oct 23, 2024 |
| Toshiba       | Satellite L55-B             | [e3b609b13a](https://linux-hardware.org/?probe=e3b609b13a) | Oct 22, 2024 |
| HP            | Victus by Laptop 16-e0xx... | [053292a4a6](https://linux-hardware.org/?probe=053292a4a6) | Oct 21, 2024 |
| Lenovo        | Unknown                     | [0c10558175](https://linux-hardware.org/?probe=0c10558175) | Oct 21, 2024 |
| HP            | Presario CQ61               | [87aea4a07b](https://linux-hardware.org/?probe=87aea4a07b) | Oct 20, 2024 |
| Lenovo        | B50-10 80QR                 | [6b27d730b2](https://linux-hardware.org/?probe=6b27d730b2) | Oct 20, 2024 |
| Dell          | Venue 8 Pro 5855            | [305bc7f736](https://linux-hardware.org/?probe=305bc7f736) | Oct 17, 2024 |
| Acer          | Aspire A515-44              | [6a2f0efb2e](https://linux-hardware.org/?probe=6a2f0efb2e) | Oct 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [5a3c293945](https://linux-hardware.org/?probe=5a3c293945) | Oct 15, 2024 |
| ASUSTek       | UL80VT                      | [c6cc761721](https://linux-hardware.org/?probe=c6cc761721) | Oct 13, 2024 |
| Dell          | Latitude 7280               | [82d8484f17](https://linux-hardware.org/?probe=82d8484f17) | Oct 12, 2024 |
| Lenovo        | ThinkPad 20BHS18200         | [c576999dfa](https://linux-hardware.org/?probe=c576999dfa) | Oct 11, 2024 |
| ASUSTek       | K95VJ                       | [a3388fefc3](https://linux-hardware.org/?probe=a3388fefc3) | Oct 11, 2024 |
| Acer          | Aspire E5-772G              | [972163fef5](https://linux-hardware.org/?probe=972163fef5) | Oct 11, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [27e0df94ae](https://linux-hardware.org/?probe=27e0df94ae) | Oct 10, 2024 |
| Packard Be... | EasyNote LS11HR             | [298822d4c4](https://linux-hardware.org/?probe=298822d4c4) | Oct 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [243cf71860](https://linux-hardware.org/?probe=243cf71860) | Oct 08, 2024 |
| Fujitsu       | LIFEBOOK N532               | [4b20b9cc8e](https://linux-hardware.org/?probe=4b20b9cc8e) | Oct 08, 2024 |
| HP            | 15 Notebook PC              | [09ec6297c1](https://linux-hardware.org/?probe=09ec6297c1) | Oct 08, 2024 |
| ASUSTek       | X551MA                      | [c405b895c9](https://linux-hardware.org/?probe=c405b895c9) | Oct 08, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | [22a99a1444](https://linux-hardware.org/?probe=22a99a1444) | Oct 06, 2024 |
| Acer          | Aspire 4738                 | [d7bd115a64](https://linux-hardware.org/?probe=d7bd115a64) | Oct 05, 2024 |
| Dell          | Latitude 5420               | [e65d154af3](https://linux-hardware.org/?probe=e65d154af3) | Oct 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [57602cd2d9](https://linux-hardware.org/?probe=57602cd2d9) | Oct 04, 2024 |
| Unknown       | Unknown                     | [5b967ea1be](https://linux-hardware.org/?probe=5b967ea1be) | Oct 04, 2024 |
| ASUSTek       | K53E                        | [62915aba3a](https://linux-hardware.org/?probe=62915aba3a) | Oct 03, 2024 |
| Dell          | Inspiron N5040              | [d09e43e3e6](https://linux-hardware.org/?probe=d09e43e3e6) | Oct 01, 2024 |
| Acer          | Aspire ES1-531              | [16c5519c67](https://linux-hardware.org/?probe=16c5519c67) | Sep 30, 2024 |
| Positivo      | R516512AI-15                | [ea6017ef32](https://linux-hardware.org/?probe=ea6017ef32) | Sep 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [36174c650c](https://linux-hardware.org/?probe=36174c650c) | Sep 30, 2024 |
| HP            | Laptop 17-cp2xxx            | [8d69c2070e](https://linux-hardware.org/?probe=8d69c2070e) | Sep 29, 2024 |
| Medion        | Akoya P7632                 | [4a73c4ece4](https://linux-hardware.org/?probe=4a73c4ece4) | Sep 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M370... | [b94dbc9df1](https://linux-hardware.org/?probe=b94dbc9df1) | Sep 28, 2024 |
| Unknown       | AX15                        | [cdbf528af6](https://linux-hardware.org/?probe=cdbf528af6) | Sep 28, 2024 |
| Medion        | P17619                      | [42d84ccf7c](https://linux-hardware.org/?probe=42d84ccf7c) | Sep 27, 2024 |
| HP            | EliteBook 725 G3            | [59140deeed](https://linux-hardware.org/?probe=59140deeed) | Sep 26, 2024 |
| Lenovo        | ThinkPad X13 Gen 4 21EXS... | [9cec35ca8e](https://linux-hardware.org/?probe=9cec35ca8e) | Sep 26, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [f7c17077ac](https://linux-hardware.org/?probe=f7c17077ac) | Sep 26, 2024 |
| Acer          | Aspire 2920                 | [bf3d0d6e64](https://linux-hardware.org/?probe=bf3d0d6e64) | Sep 24, 2024 |
| Dell          | System XPS L321X            | [461ff95992](https://linux-hardware.org/?probe=461ff95992) | Sep 24, 2024 |
| HP            | ProBook 4445s               | [64c920edf6](https://linux-hardware.org/?probe=64c920edf6) | Sep 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ecb482f9a9](https://linux-hardware.org/?probe=ecb482f9a9) | Sep 24, 2024 |
| HP            | Laptop 15-bw0xx             | [c2b79a6905](https://linux-hardware.org/?probe=c2b79a6905) | Sep 23, 2024 |
| HP            | Compaq 2510p                | [d0b68bbc55](https://linux-hardware.org/?probe=d0b68bbc55) | Sep 23, 2024 |
| ASUSTek       | M50Vn                       | [2e22fd3bd2](https://linux-hardware.org/?probe=2e22fd3bd2) | Sep 22, 2024 |
| ASUSTek       | X555LJ                      | [9dc481d73a](https://linux-hardware.org/?probe=9dc481d73a) | Sep 22, 2024 |
| Dell          | Latitude E5520m             | [a2933b9960](https://linux-hardware.org/?probe=a2933b9960) | Sep 22, 2024 |
| Toshiba       | Satellite C645              | [1a789a141f](https://linux-hardware.org/?probe=1a789a141f) | Sep 21, 2024 |
| Acer          | Aspire A315-24P             | [8cd51dbb86](https://linux-hardware.org/?probe=8cd51dbb86) | Sep 21, 2024 |
| Lenovo        | V15 G2 IJL 82QY             | [8b47709edb](https://linux-hardware.org/?probe=8b47709edb) | Sep 19, 2024 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [cc853b4c1a](https://linux-hardware.org/?probe=cc853b4c1a) | Sep 17, 2024 |
| Positivo      | EC10IS1                     | [e715b4c073](https://linux-hardware.org/?probe=e715b4c073) | Sep 16, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [5ea056f887](https://linux-hardware.org/?probe=5ea056f887) | Sep 14, 2024 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [661cd77af8](https://linux-hardware.org/?probe=661cd77af8) | Sep 13, 2024 |
| Acer          | Aspire A315-22              | [b2466dce41](https://linux-hardware.org/?probe=b2466dce41) | Sep 13, 2024 |
| ASUSTek       | X55U                        | [ce77419d34](https://linux-hardware.org/?probe=ce77419d34) | Sep 12, 2024 |
| Lenovo        | IdeaPad Y580                | [885fa56235](https://linux-hardware.org/?probe=885fa56235) | Sep 10, 2024 |
| Positivo      | R78256AI-15                 | [c848ae7984](https://linux-hardware.org/?probe=c848ae7984) | Sep 10, 2024 |
| HP            | EliteBook 6930p             | [7559a6af2d](https://linux-hardware.org/?probe=7559a6af2d) | Sep 08, 2024 |
| Dell          | Inspiron 3585               | [16ca949774](https://linux-hardware.org/?probe=16ca949774) | Sep 07, 2024 |
| HP            | EliteBook 8470p             | [0fd5cb15da](https://linux-hardware.org/?probe=0fd5cb15da) | Sep 07, 2024 |
| HP            | ZBook 17 G5                 | [1a6e1fc880](https://linux-hardware.org/?probe=1a6e1fc880) | Sep 06, 2024 |
| Lenovo        | ThinkPad T430 2347AY1       | [2f46f3ae95](https://linux-hardware.org/?probe=2f46f3ae95) | Sep 06, 2024 |
| Samsung       | R530/R730                   | [ca05ca0a68](https://linux-hardware.org/?probe=ca05ca0a68) | Sep 06, 2024 |
| Acer          | Aspire 7250                 | [fcf41d5a9d](https://linux-hardware.org/?probe=fcf41d5a9d) | Sep 05, 2024 |
| Acer          | Peppy                       | [e797f3ccb1](https://linux-hardware.org/?probe=e797f3ccb1) | Sep 05, 2024 |
| Acer          | Aspire A315-21G             | [1bd863c2c2](https://linux-hardware.org/?probe=1bd863c2c2) | Sep 05, 2024 |
| Dell          | Latitude E7450              | [c8f4f19e88](https://linux-hardware.org/?probe=c8f4f19e88) | Sep 05, 2024 |
| HP            | EliteBook 840 G1            | [453cbe339f](https://linux-hardware.org/?probe=453cbe339f) | Sep 05, 2024 |
| Dell          | Latitude 5580               | [dc0f01dc48](https://linux-hardware.org/?probe=dc0f01dc48) | Sep 04, 2024 |
| Philco        | 14H                         | [77e51c14b8](https://linux-hardware.org/?probe=77e51c14b8) | Sep 04, 2024 |
| Quanta        | QL3 TBD                     | [f3a35430d8](https://linux-hardware.org/?probe=f3a35430d8) | Sep 04, 2024 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [7ff9eab924](https://linux-hardware.org/?probe=7ff9eab924) | Sep 03, 2024 |
| Dell          | Inspiron N5110              | [118508fdea](https://linux-hardware.org/?probe=118508fdea) | Sep 03, 2024 |
| Dell          | Studio 1749                 | [d74513a21f](https://linux-hardware.org/?probe=d74513a21f) | Sep 03, 2024 |
| Lenovo        | IdeaPad Slim 5 16IMH9 83... | [ad77d695dc](https://linux-hardware.org/?probe=ad77d695dc) | Sep 02, 2024 |
| ASUSTek       | N53SN                       | [ebce5d0691](https://linux-hardware.org/?probe=ebce5d0691) | Sep 02, 2024 |
| ASUSTek       | K72F                        | [972b65066a](https://linux-hardware.org/?probe=972b65066a) | Sep 02, 2024 |
| Positivo      | S14BW01                     | [436d9031f2](https://linux-hardware.org/?probe=436d9031f2) | Sep 02, 2024 |
| Google        | Auron_Paine                 | [1b6d737594](https://linux-hardware.org/?probe=1b6d737594) | Sep 02, 2024 |
| HP            | Pavilion dv6700             | [d9b6ec66bd](https://linux-hardware.org/?probe=d9b6ec66bd) | Sep 02, 2024 |
| Acer          | Swift SFG16-71              | [99dba8223c](https://linux-hardware.org/?probe=99dba8223c) | Sep 02, 2024 |
| HP            | EliteBook 2170p             | [8b5d0ed681](https://linux-hardware.org/?probe=8b5d0ed681) | Sep 02, 2024 |
| HP            | 255 G7 Notebook PC          | [4519bc4d0b](https://linux-hardware.org/?probe=4519bc4d0b) | Sep 01, 2024 |
| HP            | EliteBook 2170p             | [84a821b49c](https://linux-hardware.org/?probe=84a821b49c) | Sep 01, 2024 |
| ASUSTek       | K53TA                       | [97e98f408d](https://linux-hardware.org/?probe=97e98f408d) | Sep 01, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [d1faa56159](https://linux-hardware.org/?probe=d1faa56159) | Aug 30, 2024 |
| Acer          | Swift SFE16-44              | [bce51aa43e](https://linux-hardware.org/?probe=bce51aa43e) | Aug 30, 2024 |
| JP.ik         | T304                        | [bf5d965733](https://linux-hardware.org/?probe=bf5d965733) | Aug 30, 2024 |
| Compaq        | Presario CQ-21              | [4c41e71d5a](https://linux-hardware.org/?probe=4c41e71d5a) | Aug 30, 2024 |
| HP            | Presario CQ58               | [5ab969b08b](https://linux-hardware.org/?probe=5ab969b08b) | Aug 29, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [8962b342ad](https://linux-hardware.org/?probe=8962b342ad) | Aug 29, 2024 |
| Medion        | E6214                       | [255b7c37ae](https://linux-hardware.org/?probe=255b7c37ae) | Aug 28, 2024 |
| Apple         | MacBook5,1                  | [223cfb4921](https://linux-hardware.org/?probe=223cfb4921) | Aug 28, 2024 |
| Packard Be... | EasyNote LS11HR             | [06c70b0344](https://linux-hardware.org/?probe=06c70b0344) | Aug 28, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [fc08bf5897](https://linux-hardware.org/?probe=fc08bf5897) | Aug 28, 2024 |
| Lenovo        | ThinkPad X130e 0629A12      | [c751cc848d](https://linux-hardware.org/?probe=c751cc848d) | Aug 28, 2024 |
| Acer          | Aspire R3-131T              | [210b362894](https://linux-hardware.org/?probe=210b362894) | Aug 28, 2024 |
| Dell          | Latitude E7470              | [cd0b24759b](https://linux-hardware.org/?probe=cd0b24759b) | Aug 27, 2024 |
| Dell          | Inspiron 3481               | [eb002a3b83](https://linux-hardware.org/?probe=eb002a3b83) | Aug 27, 2024 |
| HP            | EliteBook 840 G5            | [1ef6676af1](https://linux-hardware.org/?probe=1ef6676af1) | Aug 27, 2024 |
| Toshiba       | Satellite A505              | [61aa2bba95](https://linux-hardware.org/?probe=61aa2bba95) | Aug 26, 2024 |
| Apple         | MacBookPro11,1              | [9dcdd198a6](https://linux-hardware.org/?probe=9dcdd198a6) | Aug 26, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [ce456c4a98](https://linux-hardware.org/?probe=ce456c4a98) | Aug 26, 2024 |
| Apple         | MacBook5,1                  | [69ab889544](https://linux-hardware.org/?probe=69ab889544) | Aug 26, 2024 |
| Dell          | Inspiron 3541               | [27ed9be416](https://linux-hardware.org/?probe=27ed9be416) | Aug 26, 2024 |
| Lenovo        | G70-70 80HW                 | [b801955e87](https://linux-hardware.org/?probe=b801955e87) | Aug 26, 2024 |
| Toshiba       | Satellite C845              | [e043e1d64a](https://linux-hardware.org/?probe=e043e1d64a) | Aug 25, 2024 |
| Fujitsu       | LIFEBOOK A555               | [0e7587f9eb](https://linux-hardware.org/?probe=0e7587f9eb) | Aug 25, 2024 |
| Dynabook      | TECRA A40-G                 | [3ac4ac4f7a](https://linux-hardware.org/?probe=3ac4ac4f7a) | Aug 24, 2024 |
| AMI           | Intel                       | [fb6e4c51ed](https://linux-hardware.org/?probe=fb6e4c51ed) | Aug 23, 2024 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [ebc8f6a03b](https://linux-hardware.org/?probe=ebc8f6a03b) | Aug 23, 2024 |
| Acer          | Aspire E1-570               | [d5cfa10750](https://linux-hardware.org/?probe=d5cfa10750) | Aug 22, 2024 |
| Gigabyte      | AERO 16 XE4                 | [491d0f5415](https://linux-hardware.org/?probe=491d0f5415) | Aug 22, 2024 |
| MSI           | Bravo 15 B5DD               | [7e7ea801a9](https://linux-hardware.org/?probe=7e7ea801a9) | Aug 22, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [0cd831a254](https://linux-hardware.org/?probe=0cd831a254) | Aug 22, 2024 |
| Dell          | Inspiron 15-3565            | [c90ce327f2](https://linux-hardware.org/?probe=c90ce327f2) | Aug 21, 2024 |
| Dell          | Inspiron 1525               | [29292480d1](https://linux-hardware.org/?probe=29292480d1) | Aug 19, 2024 |
| Lenovo        | 100e 2nd Gen 81M8           | [080d34db04](https://linux-hardware.org/?probe=080d34db04) | Aug 19, 2024 |
| Acer          | Aspire E5-571               | [e804efc22d](https://linux-hardware.org/?probe=e804efc22d) | Aug 18, 2024 |
| ASUSTek       | X551MA                      | [b113e06e29](https://linux-hardware.org/?probe=b113e06e29) | Aug 18, 2024 |
| Unknown       | DeeQ                        | [4edc858d59](https://linux-hardware.org/?probe=4edc858d59) | Aug 15, 2024 |
| Acer          | Extensa 5220                | [26093b3071](https://linux-hardware.org/?probe=26093b3071) | Aug 15, 2024 |
| Dell          | Inspiron 15 5510            | [7fd5e88801](https://linux-hardware.org/?probe=7fd5e88801) | Aug 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [252054bbbb](https://linux-hardware.org/?probe=252054bbbb) | Aug 14, 2024 |
| Acer          | Aspire A114-33              | [2a74f324ac](https://linux-hardware.org/?probe=2a74f324ac) | Aug 14, 2024 |
| ASUSTek       | X55SV                       | [4b41f17fba](https://linux-hardware.org/?probe=4b41f17fba) | Aug 14, 2024 |
| ASUSTek       | X541NA                      | [0d55582f37](https://linux-hardware.org/?probe=0d55582f37) | Aug 14, 2024 |
| HP            | Laptop 17-ca1xxx            | [259992a3f9](https://linux-hardware.org/?probe=259992a3f9) | Aug 14, 2024 |
| Apple         | MacBookAir5,2               | [500702385c](https://linux-hardware.org/?probe=500702385c) | Aug 14, 2024 |
| HP            | EliteBook 830 G5            | [a091b4e48d](https://linux-hardware.org/?probe=a091b4e48d) | Aug 14, 2024 |
| MSI           | Alpha 15 A3DDK              | [5a00bfee31](https://linux-hardware.org/?probe=5a00bfee31) | Aug 14, 2024 |
| Positivo      | N1103                       | [299d981b42](https://linux-hardware.org/?probe=299d981b42) | Aug 14, 2024 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [a8e5c14cab](https://linux-hardware.org/?probe=a8e5c14cab) | Aug 13, 2024 |
| Dell          | Latitude E4200              | [320805a7cd](https://linux-hardware.org/?probe=320805a7cd) | Aug 13, 2024 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [ecf1f5843f](https://linux-hardware.org/?probe=ecf1f5843f) | Aug 13, 2024 |
| MSI           | GS70 2OD                    | [eb85cc42f6](https://linux-hardware.org/?probe=eb85cc42f6) | Aug 13, 2024 |
| Unknown       | Unknown                     | [0468a241e4](https://linux-hardware.org/?probe=0468a241e4) | Aug 13, 2024 |
| HP            | ProBook 650 G1              | [948de2035b](https://linux-hardware.org/?probe=948de2035b) | Aug 13, 2024 |
| Acer          | Extensa 5220                | [69c707d263](https://linux-hardware.org/?probe=69c707d263) | Aug 13, 2024 |
| HP            | 15                          | [a1f14f42dc](https://linux-hardware.org/?probe=a1f14f42dc) | Aug 12, 2024 |
| Dell          | Vostro 1700                 | [f8337e3827](https://linux-hardware.org/?probe=f8337e3827) | Aug 12, 2024 |
| HP            | Pavilion dv6                | [032f5f2535](https://linux-hardware.org/?probe=032f5f2535) | Aug 12, 2024 |
| ASUSTek       | K53SM                       | [b3f8198314](https://linux-hardware.org/?probe=b3f8198314) | Aug 12, 2024 |
| VIT           | P2400                       | [b103ea6da4](https://linux-hardware.org/?probe=b103ea6da4) | Aug 12, 2024 |
| Samsung       | RC530/RC730                 | [04e7201341](https://linux-hardware.org/?probe=04e7201341) | Aug 11, 2024 |
| ASUSTek       | X750LA                      | [798b53356b](https://linux-hardware.org/?probe=798b53356b) | Aug 11, 2024 |
| Sony          | SVE14A25CFP                 | [35a1034271](https://linux-hardware.org/?probe=35a1034271) | Aug 11, 2024 |
| Dell          | Latitude 7390               | [1f851389e7](https://linux-hardware.org/?probe=1f851389e7) | Aug 11, 2024 |
| Packard Be... | EasyNote TK11BZ             | [105ff99feb](https://linux-hardware.org/?probe=105ff99feb) | Aug 11, 2024 |
| Acer          | Extensa 215-22              | [a4cb78601b](https://linux-hardware.org/?probe=a4cb78601b) | Aug 11, 2024 |
| Acer          | Aspire V5-471PG             | [cffec3a7cb](https://linux-hardware.org/?probe=cffec3a7cb) | Aug 11, 2024 |
| Fujitsu       | LIFEBOOK A512               | [aca5a2c925](https://linux-hardware.org/?probe=aca5a2c925) | Aug 10, 2024 |
| HP            | Unknown                     | [13b4b0bc1c](https://linux-hardware.org/?probe=13b4b0bc1c) | Aug 10, 2024 |
| HP            | Pavilion dv4                | [884ea6b76d](https://linux-hardware.org/?probe=884ea6b76d) | Aug 10, 2024 |
| Dell          | Latitude 7480               | [4b3df98ff0](https://linux-hardware.org/?probe=4b3df98ff0) | Aug 09, 2024 |
| Toshiba       | Satellite C75D-B            | [5be070a7d0](https://linux-hardware.org/?probe=5be070a7d0) | Aug 09, 2024 |
| HP            | EliteBook 650 15.6 inch ... | [a832b68002](https://linux-hardware.org/?probe=a832b68002) | Aug 09, 2024 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [13fcfc23c2](https://linux-hardware.org/?probe=13fcfc23c2) | Aug 08, 2024 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [6b4b54be9c](https://linux-hardware.org/?probe=6b4b54be9c) | Aug 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [7d0bd59b78](https://linux-hardware.org/?probe=7d0bd59b78) | Aug 08, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | [ed48c84db2](https://linux-hardware.org/?probe=ed48c84db2) | Aug 08, 2024 |
| Dell          | Inspiron 3521               | [46039bc018](https://linux-hardware.org/?probe=46039bc018) | Aug 08, 2024 |
| Lenovo        | G570 20079                  | [e9ceb63ac4](https://linux-hardware.org/?probe=e9ceb63ac4) | Aug 08, 2024 |
| ASUSTek       | N56VM                       | [c30ce9231a](https://linux-hardware.org/?probe=c30ce9231a) | Aug 08, 2024 |
| HP            | Laptop 14-bs0xx             | [6923eb858a](https://linux-hardware.org/?probe=6923eb858a) | Aug 08, 2024 |
| Matsushita... | CF-30FTSAZBG                | [4d1cfe156e](https://linux-hardware.org/?probe=4d1cfe156e) | Aug 07, 2024 |
| Packard Be... | EasyNote LJ71               | [4b758953f5](https://linux-hardware.org/?probe=4b758953f5) | Aug 07, 2024 |
| Lenovo        | ThinkPad T450 20BUA13XPB    | [5df0222220](https://linux-hardware.org/?probe=5df0222220) | Aug 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [8ef861a7c1](https://linux-hardware.org/?probe=8ef861a7c1) | Aug 07, 2024 |
| Lenovo        | ThinkPad X230 2325L19       | [c3a54deca3](https://linux-hardware.org/?probe=c3a54deca3) | Aug 07, 2024 |
| Lenovo        | G50-30 80G0                 | [655bb3c7f9](https://linux-hardware.org/?probe=655bb3c7f9) | Aug 07, 2024 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [79efba5905](https://linux-hardware.org/?probe=79efba5905) | Aug 07, 2024 |
| Lenovo        | G70-80 80FF                 | [98e7b18535](https://linux-hardware.org/?probe=98e7b18535) | Aug 07, 2024 |
| HP            | Victus by Laptop 16-e0xx... | [801fc7231c](https://linux-hardware.org/?probe=801fc7231c) | Aug 07, 2024 |
| ASUSTek       | X401U                       | [ea3228e385](https://linux-hardware.org/?probe=ea3228e385) | Aug 07, 2024 |
| HP            | Pavilion dv4                | [9d3424e152](https://linux-hardware.org/?probe=9d3424e152) | Aug 07, 2024 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | [0188b1f00f](https://linux-hardware.org/?probe=0188b1f00f) | Aug 07, 2024 |
| Lenovo        | ThinkPad X301 4057WSQ       | [49d51f4fe2](https://linux-hardware.org/?probe=49d51f4fe2) | Aug 06, 2024 |
| Acer          | Aspire V5-573G              | [15e763080f](https://linux-hardware.org/?probe=15e763080f) | Aug 06, 2024 |
| Lenovo        | Flex 2-14 20404             | [e61443fbcd](https://linux-hardware.org/?probe=e61443fbcd) | Aug 06, 2024 |
| HP            | EliteBook Folio 9470m       | [1dad4cc854](https://linux-hardware.org/?probe=1dad4cc854) | Aug 06, 2024 |
| Dell          | Latitude E5520              | [fd2e8fc100](https://linux-hardware.org/?probe=fd2e8fc100) | Aug 06, 2024 |
| Acer          | Aspire E5-573G              | [6a38f3c326](https://linux-hardware.org/?probe=6a38f3c326) | Aug 06, 2024 |
| Acer          | Chapala                     | [06e1fcaa92](https://linux-hardware.org/?probe=06e1fcaa92) | Aug 06, 2024 |
| Dell          | Latitude E7250              | [7b85835719](https://linux-hardware.org/?probe=7b85835719) | Aug 05, 2024 |
| Lenovo        | G710 20252                  | [47543598c1](https://linux-hardware.org/?probe=47543598c1) | Aug 05, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [dbaab84f85](https://linux-hardware.org/?probe=dbaab84f85) | Aug 05, 2024 |
| Timi          | Redmi G 2022                | [bd14ac1c75](https://linux-hardware.org/?probe=bd14ac1c75) | Aug 05, 2024 |
| Lenovo        | IdeaPad Z580                | [cb672c1d21](https://linux-hardware.org/?probe=cb672c1d21) | Aug 05, 2024 |
| Samsung       | 300E4A/300E5A/300E7A        | [0e789558e1](https://linux-hardware.org/?probe=0e789558e1) | Aug 05, 2024 |
| HP            | 620                         | [b5047e656c](https://linux-hardware.org/?probe=b5047e656c) | Aug 05, 2024 |
| HP            | 15                          | [a8346ebc6c](https://linux-hardware.org/?probe=a8346ebc6c) | Aug 04, 2024 |
| GPU Compan... | GWTN156-11                  | [98f2badc5a](https://linux-hardware.org/?probe=98f2badc5a) | Aug 04, 2024 |
| Sony          | SVE14118FXW                 | [a8a2ecde8e](https://linux-hardware.org/?probe=a8a2ecde8e) | Aug 04, 2024 |
| ASUSTek       | K72F                        | [49b3023981](https://linux-hardware.org/?probe=49b3023981) | Aug 04, 2024 |
| Acer          | Aspire F5-571G              | [c6894a9467](https://linux-hardware.org/?probe=c6894a9467) | Aug 04, 2024 |
| HP            | Sona                        | [e88aa4fb3a](https://linux-hardware.org/?probe=e88aa4fb3a) | Aug 04, 2024 |
| HP            | G62                         | [a4d69df472](https://linux-hardware.org/?probe=a4d69df472) | Aug 04, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [e89575b9ca](https://linux-hardware.org/?probe=e89575b9ca) | Aug 04, 2024 |
| Acer          | Aspire E5-553G              | [672e3df75a](https://linux-hardware.org/?probe=672e3df75a) | Aug 04, 2024 |
| Lenovo        | ThinkPad T61 7659CA1        | [8c59adcf60](https://linux-hardware.org/?probe=8c59adcf60) | Aug 04, 2024 |
| Packard Be... | EasyNote TS44HR             | [8365b8e869](https://linux-hardware.org/?probe=8365b8e869) | Aug 03, 2024 |
| Lenovo        | B50-45 20388                | [f21309b152](https://linux-hardware.org/?probe=f21309b152) | Aug 03, 2024 |
| Lenovo        | ThinkPad X250 20CLS4PA00    | [56c7ccb272](https://linux-hardware.org/?probe=56c7ccb272) | Aug 03, 2024 |
| ASUSTek       | X540LJ                      | [8034e44b49](https://linux-hardware.org/?probe=8034e44b49) | Aug 03, 2024 |
| ASUSTek       | X200MA                      | [fd40aa906e](https://linux-hardware.org/?probe=fd40aa906e) | Aug 02, 2024 |
| Acer          | Aspire E5-532               | [f999845c79](https://linux-hardware.org/?probe=f999845c79) | Aug 02, 2024 |
| Lenovo        | ThinkPad X61s 76693KG       | [26fdf1c09d](https://linux-hardware.org/?probe=26fdf1c09d) | Aug 02, 2024 |
| HP            | Laptop 15-da0xxx            | [3ee11f2047](https://linux-hardware.org/?probe=3ee11f2047) | Aug 02, 2024 |
| Lenovo        | ThinkPad X200 7459LK9       | [4d3053ad8f](https://linux-hardware.org/?probe=4d3053ad8f) | Aug 01, 2024 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [6abf02ed98](https://linux-hardware.org/?probe=6abf02ed98) | Aug 01, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [c10e613a60](https://linux-hardware.org/?probe=c10e613a60) | Aug 01, 2024 |
| HP            | Laptop 14-bs0xx             | [f994ec5854](https://linux-hardware.org/?probe=f994ec5854) | Aug 01, 2024 |
| HP            | 255 G5 Notebook PC          | [2a13961522](https://linux-hardware.org/?probe=2a13961522) | Aug 01, 2024 |
| HP            | Laptop 15-rb0xx             | [c1316462ab](https://linux-hardware.org/?probe=c1316462ab) | Aug 01, 2024 |
| Lenovo        | ThinkPad T450 20BUS04U00    | [720b525240](https://linux-hardware.org/?probe=720b525240) | Jul 31, 2024 |
| Dell          | Latitude E6510              | [3ee852d371](https://linux-hardware.org/?probe=3ee852d371) | Jul 31, 2024 |
| Acer          | Aspire ES1-132              | [0539a9e223](https://linux-hardware.org/?probe=0539a9e223) | Jul 31, 2024 |
| Dell          | Inspiron 7400               | [8e52b6d214](https://linux-hardware.org/?probe=8e52b6d214) | Jul 31, 2024 |
| Lenovo        | ThinkPad T400 276552G       | [4311887bdf](https://linux-hardware.org/?probe=4311887bdf) | Jul 31, 2024 |
| Acer          | Aspire A315-41G             | [0f89433c33](https://linux-hardware.org/?probe=0f89433c33) | Jul 31, 2024 |
| Dell          | Precision M4500             | [0204ade296](https://linux-hardware.org/?probe=0204ade296) | Jul 31, 2024 |
| LG Electro... | 17Z90Q-G.AD78B              | [1f16333414](https://linux-hardware.org/?probe=1f16333414) | Jul 31, 2024 |
| LG Electro... | 16Z90S-H.ADB9U1             | [12d15d7d6f](https://linux-hardware.org/?probe=12d15d7d6f) | Jul 31, 2024 |
| Lenovo        | IdeaPad Y460                | [3addb65842](https://linux-hardware.org/?probe=3addb65842) | Jul 31, 2024 |
| TUXEDO        | Unknown                     | [d64cec791c](https://linux-hardware.org/?probe=d64cec791c) | Jul 30, 2024 |
| HP            | Compaq CQ58                 | [3c25ad374a](https://linux-hardware.org/?probe=3c25ad374a) | Jul 30, 2024 |
| Acer          | Aspire 5720                 | [8992cd5c88](https://linux-hardware.org/?probe=8992cd5c88) | Jul 30, 2024 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [2432557e37](https://linux-hardware.org/?probe=2432557e37) | Jul 30, 2024 |
| Sony          | VPCEJ1E1E                   | [d4f667801b](https://linux-hardware.org/?probe=d4f667801b) | Jul 30, 2024 |
| HP            | Pavilion Laptop 15-cw0xx... | [ce44067016](https://linux-hardware.org/?probe=ce44067016) | Jul 30, 2024 |
| HP            | Stream Laptop 11-ah0XX      | [d996c69b4e](https://linux-hardware.org/?probe=d996c69b4e) | Jul 30, 2024 |
| HP            | Pavilion Laptop 13-an0xx... | [1b74560bae](https://linux-hardware.org/?probe=1b74560bae) | Jul 30, 2024 |
| Dell          | Inspiron 15-3573            | [4eb1fa267c](https://linux-hardware.org/?probe=4eb1fa267c) | Jul 30, 2024 |
| HP            | 250 G2                      | [056a1d00e3](https://linux-hardware.org/?probe=056a1d00e3) | Jul 30, 2024 |
| Packard Be... | ENLE11BZ                    | [ecf5210a02](https://linux-hardware.org/?probe=ecf5210a02) | Jul 30, 2024 |
| HP            | ProBook 4530s               | [e89d3446a9](https://linux-hardware.org/?probe=e89d3446a9) | Jul 30, 2024 |
| HP            | Pavilion 17                 | [abce85daa2](https://linux-hardware.org/?probe=abce85daa2) | Jul 30, 2024 |
| Acer          | Aspire M5-583P              | [330749cccb](https://linux-hardware.org/?probe=330749cccb) | Jul 30, 2024 |
| HP            | 15                          | [dabb43e3d4](https://linux-hardware.org/?probe=dabb43e3d4) | Jul 29, 2024 |
| HP            | Laptop 15-db0xxx            | [a8ee53866e](https://linux-hardware.org/?probe=a8ee53866e) | Jul 29, 2024 |
| HP            | G70                         | [62cb43930d](https://linux-hardware.org/?probe=62cb43930d) | Jul 29, 2024 |
| Dell          | XPS 15 9530                 | [33f7d2da39](https://linux-hardware.org/?probe=33f7d2da39) | Jul 29, 2024 |
| eMachines     | E725                        | [6f99103190](https://linux-hardware.org/?probe=6f99103190) | Jul 29, 2024 |
| HP            | Notebook                    | [5dcd24bbc1](https://linux-hardware.org/?probe=5dcd24bbc1) | Jul 29, 2024 |
| HP            | ProBook 6570b               | [de1d8f4d47](https://linux-hardware.org/?probe=de1d8f4d47) | Jul 29, 2024 |
| Lenovo        | ThinkPad X230 2325KZ5       | [0c86e846cb](https://linux-hardware.org/?probe=0c86e846cb) | Jul 29, 2024 |
| HONOR         | BMH-WDX9                    | [34156676c7](https://linux-hardware.org/?probe=34156676c7) | Jul 28, 2024 |
| Lenovo        | G510 20238                  | [400a375f95](https://linux-hardware.org/?probe=400a375f95) | Jul 28, 2024 |
| ASUSTek       | F3L                         | [1a3fd6736d](https://linux-hardware.org/?probe=1a3fd6736d) | Jul 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [6f233277df](https://linux-hardware.org/?probe=6f233277df) | Jul 28, 2024 |
| Acer          | Aspire A515-58M             | [eacf7d3932](https://linux-hardware.org/?probe=eacf7d3932) | Jul 28, 2024 |
| HP            | Laptop 14s-fq1xxx           | [aaa0951afb](https://linux-hardware.org/?probe=aaa0951afb) | Jul 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [14e87e23b4](https://linux-hardware.org/?probe=14e87e23b4) | Jul 28, 2024 |
| HP            | Laptop 15-dy2xxx            | [cea9613aba](https://linux-hardware.org/?probe=cea9613aba) | Jul 28, 2024 |
| HP            | EliteBook 745 G6            | [d4583a12a6](https://linux-hardware.org/?probe=d4583a12a6) | Jul 27, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [e5c379682b](https://linux-hardware.org/?probe=e5c379682b) | Jul 27, 2024 |
| Samsung       | 305E4A/305E5A/305E7A        | [f407127565](https://linux-hardware.org/?probe=f407127565) | Jul 27, 2024 |
| HP            | Compaq CQ58                 | [5a0573bdb0](https://linux-hardware.org/?probe=5a0573bdb0) | Jul 27, 2024 |
| HUAWEI        | BOHK-WAX9X                  | [723eb360ba](https://linux-hardware.org/?probe=723eb360ba) | Jul 27, 2024 |
| Apple         | MacBook6,1                  | [d172ade2ae](https://linux-hardware.org/?probe=d172ade2ae) | Jul 27, 2024 |
| HP            | Laptop 17-ak0xx             | [d039ad143d](https://linux-hardware.org/?probe=d039ad143d) | Jul 27, 2024 |
| HASEE Comp... | K590P                       | [6bae6674d2](https://linux-hardware.org/?probe=6bae6674d2) | Jul 27, 2024 |
| Unknown       | M15S                        | [9cdf0f110e](https://linux-hardware.org/?probe=9cdf0f110e) | Jul 27, 2024 |
| ASUSTek       | X75A1                       | [d5b8f20d0f](https://linux-hardware.org/?probe=d5b8f20d0f) | Jul 27, 2024 |
| MSI           | Katana 15 B13VEK            | [c8c421d5c3](https://linux-hardware.org/?probe=c8c421d5c3) | Jul 26, 2024 |
| Medion        | Crawler E30                 | [5b75756a90](https://linux-hardware.org/?probe=5b75756a90) | Jul 26, 2024 |
| Dell          | Inspiron 3582               | [3f49954088](https://linux-hardware.org/?probe=3f49954088) | Jul 26, 2024 |
| Medion        | A17                         | [b8cfeb8572](https://linux-hardware.org/?probe=b8cfeb8572) | Jul 26, 2024 |
| ASUSTek       | ROG Strix G713QR_G713QR     | [fb831802d5](https://linux-hardware.org/?probe=fb831802d5) | Jul 26, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [8333b31ce7](https://linux-hardware.org/?probe=8333b31ce7) | Jul 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [75ea2b1938](https://linux-hardware.org/?probe=75ea2b1938) | Jul 26, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [9ca37a4776](https://linux-hardware.org/?probe=9ca37a4776) | Jul 26, 2024 |
| HP            | Notebook                    | [d223891862](https://linux-hardware.org/?probe=d223891862) | Jul 26, 2024 |
| HP            | OMEN Transcend Gaming La... | [f9b83b0d11](https://linux-hardware.org/?probe=f9b83b0d11) | Jul 26, 2024 |
| Lenovo        | Z50-70 20354                | [ba90eed6e2](https://linux-hardware.org/?probe=ba90eed6e2) | Jul 25, 2024 |
| Dell          | Latitude E5550              | [5a773c0eae](https://linux-hardware.org/?probe=5a773c0eae) | Jul 25, 2024 |
| ASUSTek       | K53SD                       | [ae42160a71](https://linux-hardware.org/?probe=ae42160a71) | Jul 25, 2024 |
| Toshiba       | PORTEGE Z930                | [0818704a46](https://linux-hardware.org/?probe=0818704a46) | Jul 25, 2024 |
| HP            | 255 G5                      | [738dcbcc7b](https://linux-hardware.org/?probe=738dcbcc7b) | Jul 25, 2024 |
| Maibenben     | MaiBook M                   | [45264e3652](https://linux-hardware.org/?probe=45264e3652) | Jul 25, 2024 |
| HP            | Laptop 17-by0xxx            | [29acbbfa9a](https://linux-hardware.org/?probe=29acbbfa9a) | Jul 25, 2024 |
| Acer          | Aspire 5750                 | [2c7aa20c2a](https://linux-hardware.org/?probe=2c7aa20c2a) | Jul 25, 2024 |
| Lenovo        | ThinkPad P53 20QQS74W00     | [11359334f2](https://linux-hardware.org/?probe=11359334f2) | Jul 25, 2024 |
| Lenovo        | ThinkPad E550 20DF0030US    | [ebc0fc9568](https://linux-hardware.org/?probe=ebc0fc9568) | Jul 25, 2024 |
| Dell          | Inspiron 5542               | [058371d745](https://linux-hardware.org/?probe=058371d745) | Jul 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c3d85476a7](https://linux-hardware.org/?probe=c3d85476a7) | Jul 25, 2024 |
| ASUSTek       | K53U                        | [811341b025](https://linux-hardware.org/?probe=811341b025) | Jul 25, 2024 |
| Fujitsu       | FMVNFA40J                   | [0dc6a87a7e](https://linux-hardware.org/?probe=0dc6a87a7e) | Jul 25, 2024 |
| Samsung       | RV420/RV520/RV720/E3530/... | [ecdd3b7cd2](https://linux-hardware.org/?probe=ecdd3b7cd2) | Jul 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [37186edbaa](https://linux-hardware.org/?probe=37186edbaa) | Jul 24, 2024 |
| HP            | 255 G7 Notebook PC          | [19a51f93c3](https://linux-hardware.org/?probe=19a51f93c3) | Jul 24, 2024 |
| Dell          | Latitude E5410              | [57cc1db63b](https://linux-hardware.org/?probe=57cc1db63b) | Jul 24, 2024 |
| Acer          | Aspire 7535                 | [a5f61a888d](https://linux-hardware.org/?probe=a5f61a888d) | Jul 24, 2024 |
| Packard Be... | EasyNote TE11HC             | [e8584d4bd8](https://linux-hardware.org/?probe=e8584d4bd8) | Jul 24, 2024 |
| Fujitsu       | LIFEBOOK AH531              | [b2afe39e6f](https://linux-hardware.org/?probe=b2afe39e6f) | Jul 24, 2024 |
| ASUSTek       | 1225B                       | [e7d5e1e2c4](https://linux-hardware.org/?probe=e7d5e1e2c4) | Jul 24, 2024 |
| Dell          | Inspiron 3542               | [4ac934318c](https://linux-hardware.org/?probe=4ac934318c) | Jul 24, 2024 |
| Acer          | Aspire A315-41              | [05c607b799](https://linux-hardware.org/?probe=05c607b799) | Jul 24, 2024 |
| Lenovo        | G510 20238                  | [38180e0cf9](https://linux-hardware.org/?probe=38180e0cf9) | Jul 24, 2024 |
| Dell          | Latitude E5520              | [94532288fa](https://linux-hardware.org/?probe=94532288fa) | Jul 24, 2024 |
| ASUSTek       | K50IN                       | [707377026f](https://linux-hardware.org/?probe=707377026f) | Jul 24, 2024 |
| HP            | Victus by Gaming Laptop     | [b307a07177](https://linux-hardware.org/?probe=b307a07177) | Jul 24, 2024 |
| HUAWEI        | NBLK-WAX9X                  | [8266881b34](https://linux-hardware.org/?probe=8266881b34) | Jul 24, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [1382964de9](https://linux-hardware.org/?probe=1382964de9) | Jul 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [bd05285887](https://linux-hardware.org/?probe=bd05285887) | Jul 24, 2024 |
| Lenovo        | B50-50 80S2                 | [905eac1e60](https://linux-hardware.org/?probe=905eac1e60) | Jul 23, 2024 |
| Dell          | Inspiron N4010              | [d91c98d5f4](https://linux-hardware.org/?probe=d91c98d5f4) | Jul 23, 2024 |
| HP            | 2000                        | [d1ecc9c39e](https://linux-hardware.org/?probe=d1ecc9c39e) | Jul 23, 2024 |
| Sony          | VPCEB3F4E                   | [5b1e21f008](https://linux-hardware.org/?probe=5b1e21f008) | Jul 23, 2024 |
| Toshiba       | dynabook R734/M             | [74f02e03a1](https://linux-hardware.org/?probe=74f02e03a1) | Jul 23, 2024 |
| Dell          | System Inspiron N7110       | [9eca86601c](https://linux-hardware.org/?probe=9eca86601c) | Jul 23, 2024 |
| Medion        | E11201                      | [603f2caffa](https://linux-hardware.org/?probe=603f2caffa) | Jul 23, 2024 |
| Lenovo        | V15 G4 IRU 83A1             | [2a1301a1d4](https://linux-hardware.org/?probe=2a1301a1d4) | Jul 23, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [c6b7f59209](https://linux-hardware.org/?probe=c6b7f59209) | Jul 23, 2024 |
| Sony          | VPCYB3V1E                   | [e34ef837a0](https://linux-hardware.org/?probe=e34ef837a0) | Jul 23, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [ab92abc5df](https://linux-hardware.org/?probe=ab92abc5df) | Jul 23, 2024 |
| Acer          | Aspire 7720Z                | [22b713dcde](https://linux-hardware.org/?probe=22b713dcde) | Jul 23, 2024 |
| Lenovo        | ThinkPad Edge E531 68856... | [37fc2e067d](https://linux-hardware.org/?probe=37fc2e067d) | Jul 23, 2024 |
| ALLDOCUBE     | i1506S                      | [86c70fe18b](https://linux-hardware.org/?probe=86c70fe18b) | Jul 23, 2024 |
| HP            | G72                         | [d1b4f722ff](https://linux-hardware.org/?probe=d1b4f722ff) | Jul 23, 2024 |
| Dell          | 500                         | [81a9db8d87](https://linux-hardware.org/?probe=81a9db8d87) | Jul 23, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5d2efc60c2](https://linux-hardware.org/?probe=5d2efc60c2) | Jul 23, 2024 |
| HP            | ENVY dv6                    | [90cb34453c](https://linux-hardware.org/?probe=90cb34453c) | Jul 23, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [4e3f61c287](https://linux-hardware.org/?probe=4e3f61c287) | Jul 23, 2024 |
| Infinix       | INBOOK X3 Plus              | [bf04bfec39](https://linux-hardware.org/?probe=bf04bfec39) | Jul 23, 2024 |
| Lenovo        | ThinkPad R500 2718Y21       | [527c6d0299](https://linux-hardware.org/?probe=527c6d0299) | Jul 23, 2024 |
| Acer          | Aspire A515-43              | [edd3820814](https://linux-hardware.org/?probe=edd3820814) | Jul 23, 2024 |
| Acer          | Aspire E5-573G              | [063c27b460](https://linux-hardware.org/?probe=063c27b460) | Jul 23, 2024 |
| HP            | ProBook 470 G5              | [894e4a3a29](https://linux-hardware.org/?probe=894e4a3a29) | Jul 22, 2024 |
| HP            | Pavilion dv6                | [2a996d810e](https://linux-hardware.org/?probe=2a996d810e) | Jul 22, 2024 |
| HP            | Laptop 15-bw0xx             | [e09128a4ab](https://linux-hardware.org/?probe=e09128a4ab) | Jul 22, 2024 |
| HP            | Laptop 15s-fq4xxx           | [c872b62918](https://linux-hardware.org/?probe=c872b62918) | Jul 22, 2024 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [349b93eb77](https://linux-hardware.org/?probe=349b93eb77) | Jul 22, 2024 |
| Toshiba       | Satellite C660D             | [d5fb9be35b](https://linux-hardware.org/?probe=d5fb9be35b) | Jul 22, 2024 |
| Acer          | Aspire V5-572P              | [9a1fdd796f](https://linux-hardware.org/?probe=9a1fdd796f) | Jul 22, 2024 |
| HP            | Laptop 15-db0xxx            | [c94be31c69](https://linux-hardware.org/?probe=c94be31c69) | Jul 22, 2024 |
| Lenovo        | ThinkPad X390 20Q1S0Q900    | [1d0f6530a5](https://linux-hardware.org/?probe=1d0f6530a5) | Jul 22, 2024 |
| Positivo      | C14CU51                     | [8b409abdcb](https://linux-hardware.org/?probe=8b409abdcb) | Jul 22, 2024 |
| Acer          | Nitro AN515-43              | [acaa1594ba](https://linux-hardware.org/?probe=acaa1594ba) | Jul 22, 2024 |
| Dell          | Inspiron 5515               | [428e862b13](https://linux-hardware.org/?probe=428e862b13) | Jul 22, 2024 |
| MSI           | GE60 2OC\2OE                | [6950b59fb3](https://linux-hardware.org/?probe=6950b59fb3) | Jul 22, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [d1ad339231](https://linux-hardware.org/?probe=d1ad339231) | Jul 22, 2024 |
| Toshiba       | Satellite C50D-B            | [7b005551ad](https://linux-hardware.org/?probe=7b005551ad) | Jul 22, 2024 |
| HUAWEI        | HVY-WXX9                    | [8ee353c38c](https://linux-hardware.org/?probe=8ee353c38c) | Jul 22, 2024 |
| Lenovo        | ThinkPad X230 2306A27       | [07e6f1b674](https://linux-hardware.org/?probe=07e6f1b674) | Jul 22, 2024 |
| ASUSTek       | X55A                        | [db363010ca](https://linux-hardware.org/?probe=db363010ca) | Jul 22, 2024 |
| HP            | Pavilion 13                 | [8b052076e8](https://linux-hardware.org/?probe=8b052076e8) | Jul 22, 2024 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [81172d3a52](https://linux-hardware.org/?probe=81172d3a52) | Jul 22, 2024 |
| GPU Compan... | GWTN156-4                   | [7c1b942068](https://linux-hardware.org/?probe=7c1b942068) | Jul 22, 2024 |
| Dell          | Inspiron 3531               | [af1b6ea4a0](https://linux-hardware.org/?probe=af1b6ea4a0) | Jul 22, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [bf2a6360f0](https://linux-hardware.org/?probe=bf2a6360f0) | Jul 22, 2024 |
| Lenovo        | ThinkPad T440 20B7S1CF00    | [edf0f4d856](https://linux-hardware.org/?probe=edf0f4d856) | Jul 22, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [a3623eb22b](https://linux-hardware.org/?probe=a3623eb22b) | Jul 22, 2024 |
| Dell          | Latitude E4300              | [73f350face](https://linux-hardware.org/?probe=73f350face) | Jul 22, 2024 |
| ASUSTek       | K55A                        | [84dc32375b](https://linux-hardware.org/?probe=84dc32375b) | Jul 22, 2024 |
| Acer          | Nitro AN515-54              | [102b214250](https://linux-hardware.org/?probe=102b214250) | Jul 21, 2024 |
| Acer          | TravelMate B118-M           | [35065672a9](https://linux-hardware.org/?probe=35065672a9) | Jul 21, 2024 |
| Dell          | Precision M3800             | [ab9f1041b4](https://linux-hardware.org/?probe=ab9f1041b4) | Jul 21, 2024 |
| HP            | Laptop 17-ak0xx             | [447057c17c](https://linux-hardware.org/?probe=447057c17c) | Jul 21, 2024 |
| AMI           | Intel                       | [f35476d44f](https://linux-hardware.org/?probe=f35476d44f) | Jul 21, 2024 |
| Dell          | Inspiron 5593               | [208dc6d482](https://linux-hardware.org/?probe=208dc6d482) | Jul 21, 2024 |
| Dell          | Inspiron N4010              | [ea6e9fd832](https://linux-hardware.org/?probe=ea6e9fd832) | Jul 21, 2024 |
| Toshiba       | Satellite L510              | [97e25526be](https://linux-hardware.org/?probe=97e25526be) | Jul 21, 2024 |
| Positivo      | I38512BI-15                 | [d10b676d0e](https://linux-hardware.org/?probe=d10b676d0e) | Jul 21, 2024 |
| HP            | Laptop 15-rb0xx             | [1e91f8156a](https://linux-hardware.org/?probe=1e91f8156a) | Jul 21, 2024 |
| HP            | TouchSmart tm2              | [1b2a4ba53f](https://linux-hardware.org/?probe=1b2a4ba53f) | Jul 21, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [6ba68ff512](https://linux-hardware.org/?probe=6ba68ff512) | Jul 21, 2024 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [25aea34fde](https://linux-hardware.org/?probe=25aea34fde) | Jul 21, 2024 |
| Dell          | Latitude E7440              | [0a7920c250](https://linux-hardware.org/?probe=0a7920c250) | Jul 21, 2024 |
| Packard Be... | EasyNote LJ75               | [ff307c6aa2](https://linux-hardware.org/?probe=ff307c6aa2) | Jul 21, 2024 |
| HP            | EliteBook Folio 9480m       | [ff50b29401](https://linux-hardware.org/?probe=ff50b29401) | Jul 21, 2024 |
| MSI           | Prestige 14Evo B13M         | [ece3a7e7ad](https://linux-hardware.org/?probe=ece3a7e7ad) | Jul 21, 2024 |
| Lenovo        | ThinkPad T420 4180DR4       | [34d1b42bbb](https://linux-hardware.org/?probe=34d1b42bbb) | Jul 21, 2024 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | [7a3b21946e](https://linux-hardware.org/?probe=7a3b21946e) | Jul 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [de8bb50c0d](https://linux-hardware.org/?probe=de8bb50c0d) | Jul 21, 2024 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [580e2b3913](https://linux-hardware.org/?probe=580e2b3913) | Jul 21, 2024 |
| Lenovo        | ThinkPad L450 20DSS1DT00    | [13a4bd8ef8](https://linux-hardware.org/?probe=13a4bd8ef8) | Jul 21, 2024 |
| HP            | Pavilion Laptop 15-eh3xx... | [de956ddbce](https://linux-hardware.org/?probe=de956ddbce) | Jul 21, 2024 |
| HP            | Laptop 14s-fq0xxx           | [c55d3697bc](https://linux-hardware.org/?probe=c55d3697bc) | Jul 21, 2024 |
| HP            | Pavilion dv6                | [0e3ba969bb](https://linux-hardware.org/?probe=0e3ba969bb) | Jul 21, 2024 |
| ASUSTek       | X540SC                      | [88d86a9a73](https://linux-hardware.org/?probe=88d86a9a73) | Jul 21, 2024 |
| Panasonic     | CF-AX2LDDEEA                | [92cfd61c6b](https://linux-hardware.org/?probe=92cfd61c6b) | Jul 21, 2024 |
| Dell          | Latitude E4310              | [134a985afc](https://linux-hardware.org/?probe=134a985afc) | Jul 21, 2024 |
| Lenovo        | ThinkPad Edge E430c 3365... | [ed4ee723bc](https://linux-hardware.org/?probe=ed4ee723bc) | Jul 21, 2024 |
| Toshiba       | Satellite C660              | [682ee2b1d0](https://linux-hardware.org/?probe=682ee2b1d0) | Jul 21, 2024 |
| Lenovo        | ThinkPad T450 20BUS20301    | [045440322e](https://linux-hardware.org/?probe=045440322e) | Jul 21, 2024 |
| Unknown       | Unknown                     | [2af4aa15ea](https://linux-hardware.org/?probe=2af4aa15ea) | Jul 21, 2024 |
| Acer          | Aspire E1-571G              | [123cc38ec0](https://linux-hardware.org/?probe=123cc38ec0) | Jul 20, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [301af4ea4b](https://linux-hardware.org/?probe=301af4ea4b) | Jul 20, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [f425651aeb](https://linux-hardware.org/?probe=f425651aeb) | Jul 19, 2024 |
| Fujitsu       | LIFEBOOK U772               | [8ba4824fc8](https://linux-hardware.org/?probe=8ba4824fc8) | Jul 19, 2024 |
| Sony          | VPCF12E1E                   | [898e270b9c](https://linux-hardware.org/?probe=898e270b9c) | Jul 19, 2024 |
| Fujitsu       | LIFEBOOK E733               | [6d6b42a6fe](https://linux-hardware.org/?probe=6d6b42a6fe) | Jul 19, 2024 |
| Acer          | Aspire 7739G                | [465c544413](https://linux-hardware.org/?probe=465c544413) | Jul 19, 2024 |
| Dell          | Precision 7520              | [4b8859395d](https://linux-hardware.org/?probe=4b8859395d) | Jul 19, 2024 |
| Dell          | Latitude E7250              | [78aaef2bf3](https://linux-hardware.org/?probe=78aaef2bf3) | Jul 19, 2024 |
| Medion        | Akoya S6214T                | [42480d4114](https://linux-hardware.org/?probe=42480d4114) | Jul 17, 2024 |
| HP            | EPROM DATA AREA             | [e227613970](https://linux-hardware.org/?probe=e227613970) | Jul 17, 2024 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [be16ffa7bd](https://linux-hardware.org/?probe=be16ffa7bd) | Jul 16, 2024 |
| Toshiba       | Satellite R845              | [d0853ee968](https://linux-hardware.org/?probe=d0853ee968) | Jul 16, 2024 |
| Acer          | Aspire A315-23              | [f687f1ad13](https://linux-hardware.org/?probe=f687f1ad13) | Jul 15, 2024 |
| Lenovo        | ThinkPad T440 20B7S0W900    | [a98535cd6b](https://linux-hardware.org/?probe=a98535cd6b) | Jul 15, 2024 |
| Acer          | Aspire E5-771               | [9961171330](https://linux-hardware.org/?probe=9961171330) | Jul 15, 2024 |
| Lenovo        | IdeaPadFlex 15 20309        | [1695bfd667](https://linux-hardware.org/?probe=1695bfd667) | Jul 15, 2024 |
| Acer          | Aspire E5-432               | [9d95bfc4d2](https://linux-hardware.org/?probe=9d95bfc4d2) | Jul 15, 2024 |
| Dell          | Latitude E5540              | [bec0701727](https://linux-hardware.org/?probe=bec0701727) | Jul 15, 2024 |
| Dell          | Latitude E5530 non-vPro     | [8c6a95ec6e](https://linux-hardware.org/?probe=8c6a95ec6e) | Jul 14, 2024 |
| Samsung       | N150P/N210P/N220P           | [f0a5b1a925](https://linux-hardware.org/?probe=f0a5b1a925) | Jul 14, 2024 |
| ASUSTek       | 1001P                       | [9f0123d00c](https://linux-hardware.org/?probe=9f0123d00c) | Jul 14, 2024 |
| Lenovo        | ThinkPad X201 3680Z2T       | [e24a218e3e](https://linux-hardware.org/?probe=e24a218e3e) | Jul 14, 2024 |
| Dell          | G5 5505                     | [592a42428c](https://linux-hardware.org/?probe=592a42428c) | Jul 14, 2024 |
| HP            | Laptop 14-bp0xx             | [b937727b2f](https://linux-hardware.org/?probe=b937727b2f) | Jul 14, 2024 |
| HP            | Notebook                    | [76d1a8c671](https://linux-hardware.org/?probe=76d1a8c671) | Jul 14, 2024 |
| Lenovo        | ThinkPad T430 23426FU       | [879e794f78](https://linux-hardware.org/?probe=879e794f78) | Jul 13, 2024 |
| Toshiba       | Satellite C850D-134         | [c02034ba74](https://linux-hardware.org/?probe=c02034ba74) | Jul 13, 2024 |
| Acer          | Aspire 3810TZ               | [8a845f0a93](https://linux-hardware.org/?probe=8a845f0a93) | Jul 13, 2024 |
| HP            | Laptop 17-ca1xxx            | [7b6bf257b9](https://linux-hardware.org/?probe=7b6bf257b9) | Jul 13, 2024 |
| HP            | EliteBook 6930p             | [c192a8f718](https://linux-hardware.org/?probe=c192a8f718) | Jul 13, 2024 |
| Dell          | Latitude 7390               | [ddb7685bf1](https://linux-hardware.org/?probe=ddb7685bf1) | Jul 12, 2024 |
| HP            | ProBook 450 G2              | [eac7027b47](https://linux-hardware.org/?probe=eac7027b47) | Jul 11, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [6a13b89592](https://linux-hardware.org/?probe=6a13b89592) | Jul 11, 2024 |
| Sony          | VPCF23Z1E                   | [d6499f456e](https://linux-hardware.org/?probe=d6499f456e) | Jul 11, 2024 |
| Dell          | Latitude 3510               | [b4a2c1ff96](https://linux-hardware.org/?probe=b4a2c1ff96) | Jul 11, 2024 |
| Dell          | Latitude E7440              | [4f8117eff3](https://linux-hardware.org/?probe=4f8117eff3) | Jul 10, 2024 |
| ASUSTek       | X75A1                       | [08f8197812](https://linux-hardware.org/?probe=08f8197812) | Jul 10, 2024 |
| Toshiba       | Satellite C75-A             | [87d3b596a1](https://linux-hardware.org/?probe=87d3b596a1) | Jul 10, 2024 |
| Dell          | Latitude E5450              | [16fb580b5c](https://linux-hardware.org/?probe=16fb580b5c) | Jul 10, 2024 |
| HP            | Laptop 14s-fq1xxx           | [a7dd8bc9c0](https://linux-hardware.org/?probe=a7dd8bc9c0) | Jul 10, 2024 |
| ASUSTek       | X510UAR                     | [9e2faefcd3](https://linux-hardware.org/?probe=9e2faefcd3) | Jul 10, 2024 |
| Acer          | TravelMate 5744             | [dd44567736](https://linux-hardware.org/?probe=dd44567736) | Jul 09, 2024 |
| HP            | Laptop 15s-fq5xxx           | [5a3d2484fe](https://linux-hardware.org/?probe=5a3d2484fe) | Jul 09, 2024 |
| ASUSTek       | UL80VT                      | [f43d972a57](https://linux-hardware.org/?probe=f43d972a57) | Jul 09, 2024 |
| Lenovo        | ThinkPad L530 24814QU       | [aa9d086f8a](https://linux-hardware.org/?probe=aa9d086f8a) | Jul 09, 2024 |
| Google        | Relm                        | [b834b3e0b1](https://linux-hardware.org/?probe=b834b3e0b1) | Jul 09, 2024 |
| Dell          | Inspiron 15-3552            | [89d5f111d2](https://linux-hardware.org/?probe=89d5f111d2) | Jul 08, 2024 |
| ASUSTek       | X401A1                      | [f671942cf6](https://linux-hardware.org/?probe=f671942cf6) | Jul 08, 2024 |
| Fujitsu       | LIFEBOOK LH532              | [35121c087c](https://linux-hardware.org/?probe=35121c087c) | Jul 08, 2024 |
| Lenovo        | B50-30 20382                | [4a4df5cc6a](https://linux-hardware.org/?probe=4a4df5cc6a) | Jul 08, 2024 |
| Dell          | Inspiron 5423               | [50a824a62f](https://linux-hardware.org/?probe=50a824a62f) | Jul 08, 2024 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [7e92935a69](https://linux-hardware.org/?probe=7e92935a69) | Jul 08, 2024 |
| Dell          | Latitude 5490               | [4d6c1e6020](https://linux-hardware.org/?probe=4d6c1e6020) | Jul 07, 2024 |
| Apple         | MacBookPro5,3               | [79a2ee9967](https://linux-hardware.org/?probe=79a2ee9967) | Jul 07, 2024 |
| HP            | Pavilion g4                 | [7dc29fa0b4](https://linux-hardware.org/?probe=7dc29fa0b4) | Jul 07, 2024 |
| Toshiba       | Satellite L500              | [d41f6ae73f](https://linux-hardware.org/?probe=d41f6ae73f) | Jul 07, 2024 |
| HP            | Laptop 14-cm0xxx            | [64eb92c646](https://linux-hardware.org/?probe=64eb92c646) | Jul 07, 2024 |
| HP            | ProBook 455 G8 Notebook ... | [f907fa8f4a](https://linux-hardware.org/?probe=f907fa8f4a) | Jul 07, 2024 |
| Toshiba       | Satellite L855              | [332256325d](https://linux-hardware.org/?probe=332256325d) | Jul 07, 2024 |
| Dell          | Latitude E6540              | [433ba887b9](https://linux-hardware.org/?probe=433ba887b9) | Jul 07, 2024 |
| Sony          | VPCEG13EL                   | [17cb1e5512](https://linux-hardware.org/?probe=17cb1e5512) | Jul 07, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [751b1fe8f5](https://linux-hardware.org/?probe=751b1fe8f5) | Jul 07, 2024 |
| Lenovo        | ThinkPad X230 23301H3       | [b4a731eecc](https://linux-hardware.org/?probe=b4a731eecc) | Jul 06, 2024 |
| Dell          | Precision 7520              | [ebba75e9b2](https://linux-hardware.org/?probe=ebba75e9b2) | Jul 06, 2024 |
| Lenovo        | ThinkPad T480s 20L8S6MQ0... | [ffcefdc71a](https://linux-hardware.org/?probe=ffcefdc71a) | Jul 06, 2024 |
| Lenovo        | ThinkPad X220 4291ON2       | [a45070973a](https://linux-hardware.org/?probe=a45070973a) | Jul 06, 2024 |
| ASUSTek       | X551CAP                     | [4837b7a551](https://linux-hardware.org/?probe=4837b7a551) | Jul 06, 2024 |
| Apple         | MacBookPro11,4              | [552c996920](https://linux-hardware.org/?probe=552c996920) | Jul 06, 2024 |
| HP            | EliteBook 8570p             | [b401a89582](https://linux-hardware.org/?probe=b401a89582) | Jul 06, 2024 |
| HP            | EliteBook 8460p             | [699c333bf1](https://linux-hardware.org/?probe=699c333bf1) | Jul 06, 2024 |
| HP            | 15 Notebook PC              | [f329506b93](https://linux-hardware.org/?probe=f329506b93) | Jul 06, 2024 |
| Toshiba       | TECRA A10                   | [434ffb4727](https://linux-hardware.org/?probe=434ffb4727) | Jul 06, 2024 |
| Dell          | Latitude E7440              | [d8c472689b](https://linux-hardware.org/?probe=d8c472689b) | Jul 06, 2024 |
| ASUSTek       | ASUS Zenbook 14 UM3406HA... | [9ee61dc724](https://linux-hardware.org/?probe=9ee61dc724) | Jul 06, 2024 |
| ASUSTek       | X201EV                      | [f02eb29877](https://linux-hardware.org/?probe=f02eb29877) | Jul 06, 2024 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [d88fa4ab1a](https://linux-hardware.org/?probe=d88fa4ab1a) | Jul 06, 2024 |
| HP            | Laptop 15s-eq1xxx           | [016a725317](https://linux-hardware.org/?probe=016a725317) | Jul 06, 2024 |
| Toshiba       | TECRA M10                   | [25ddae362f](https://linux-hardware.org/?probe=25ddae362f) | Jul 06, 2024 |
| Lenovo        | B50-50 80S2                 | [b72ee7190b](https://linux-hardware.org/?probe=b72ee7190b) | Jul 06, 2024 |
| Dell          | Inspiron 5735               | [53bdd9a589](https://linux-hardware.org/?probe=53bdd9a589) | Jul 06, 2024 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [abb0c9862b](https://linux-hardware.org/?probe=abb0c9862b) | Jul 06, 2024 |
| Lenovo        | IdeaPad Z370                | [42eeaeef31](https://linux-hardware.org/?probe=42eeaeef31) | Jul 06, 2024 |
| HP            | Pavilion 15                 | [2d13b274c7](https://linux-hardware.org/?probe=2d13b274c7) | Jul 06, 2024 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [fafb799dd5](https://linux-hardware.org/?probe=fafb799dd5) | Jul 06, 2024 |
| Unknown       | Unknown                     | [1b0d823c81](https://linux-hardware.org/?probe=1b0d823c81) | Jul 05, 2024 |
| Lenovo        | ThinkPad T430 2349AR1       | [36e8dfcded](https://linux-hardware.org/?probe=36e8dfcded) | Jul 05, 2024 |
| Dell          | Latitude E6510              | [60edc326bd](https://linux-hardware.org/?probe=60edc326bd) | Jul 05, 2024 |
| Google        | Swanky                      | [4573a5540e](https://linux-hardware.org/?probe=4573a5540e) | Jul 05, 2024 |
| Positivo      | Mobile                      | [f1dc9f91c2](https://linux-hardware.org/?probe=f1dc9f91c2) | Jul 05, 2024 |
| Lenovo        | IdeaPad S210 Touch 20257    | [1aae27a11b](https://linux-hardware.org/?probe=1aae27a11b) | Jul 05, 2024 |
| HP            | OMEN by Laptop 15-dh1xxx    | [31a09f4612](https://linux-hardware.org/?probe=31a09f4612) | Jul 05, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | [e0f29e9ecb](https://linux-hardware.org/?probe=e0f29e9ecb) | Jul 05, 2024 |
| Dell          | Latitude 7490               | [6322c922de](https://linux-hardware.org/?probe=6322c922de) | Jul 05, 2024 |
| Medion        | Akoya E6418 MD99620         | [fa8b301cb0](https://linux-hardware.org/?probe=fa8b301cb0) | Jul 05, 2024 |
| Dell          | Latitude 5500               | [2c25e016f3](https://linux-hardware.org/?probe=2c25e016f3) | Jul 05, 2024 |
| Lenovo        | ThinkPad T530 2429F37       | [4865518f15](https://linux-hardware.org/?probe=4865518f15) | Jul 05, 2024 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [03c3b55154](https://linux-hardware.org/?probe=03c3b55154) | Jul 05, 2024 |
| Lenovo        | G400 20235                  | [2740ab422f](https://linux-hardware.org/?probe=2740ab422f) | Jul 05, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [68c11b0283](https://linux-hardware.org/?probe=68c11b0283) | Jul 04, 2024 |
| Notebook      | NHx0ERQ_EPS                 | [ccfcd08fd5](https://linux-hardware.org/?probe=ccfcd08fd5) | Jul 04, 2024 |
| Acer          | A315-21                     | [ad17a7e1f9](https://linux-hardware.org/?probe=ad17a7e1f9) | Jul 04, 2024 |
| Lenovo        | ThinkPad T440s 20ARS0NF0... | [051332a92e](https://linux-hardware.org/?probe=051332a92e) | Jul 04, 2024 |
| ASUSTek       | X541SA                      | [9c8da1caab](https://linux-hardware.org/?probe=9c8da1caab) | Jul 04, 2024 |
| Acer          | Aspire E1-772               | [f2ced6fdae](https://linux-hardware.org/?probe=f2ced6fdae) | Jul 04, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [ee3f4a0bf8](https://linux-hardware.org/?probe=ee3f4a0bf8) | Jul 04, 2024 |
| ASUSTek       | Zenbook UX3404VA_Q410VA     | [92ac287120](https://linux-hardware.org/?probe=92ac287120) | Jul 04, 2024 |
| Lenovo        | 3000 G410                   | [8d4dba044b](https://linux-hardware.org/?probe=8d4dba044b) | Jul 04, 2024 |
| Dell          | Latitude E6430              | [a31a3f0d63](https://linux-hardware.org/?probe=a31a3f0d63) | Jul 04, 2024 |
| Acer          | Aspire V3-571               | [08af2aa20a](https://linux-hardware.org/?probe=08af2aa20a) | Jul 04, 2024 |
| MSI           | Katana 17 B12VFK            | [bfb45fc712](https://linux-hardware.org/?probe=bfb45fc712) | Jul 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [7f8992ce0b](https://linux-hardware.org/?probe=7f8992ce0b) | Jul 04, 2024 |
| HP            | EliteBook 820 G1            | [ed985ce59b](https://linux-hardware.org/?probe=ed985ce59b) | Jul 04, 2024 |
| ASUSTek       | K53SV                       | [87d990e8b2](https://linux-hardware.org/?probe=87d990e8b2) | Jul 04, 2024 |
| AWOW          | AL34                        | [360ca3433d](https://linux-hardware.org/?probe=360ca3433d) | Jul 04, 2024 |
| Acer          | Aspire A114-32              | [ea593251ed](https://linux-hardware.org/?probe=ea593251ed) | Jul 04, 2024 |
| Gateway       | NV57H                       | [f8eca56865](https://linux-hardware.org/?probe=f8eca56865) | Jul 04, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_24.07/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.10.0-desktop-1omv2490 | 487       | 75.74%  |
| 6.9.7-desktop-1omv2490  | 133       | 20.68%  |
| 6.10.1-desktop-1omv2490 | 20        | 3.11%   |
| 6.9.9-desktop-1omv2490  | 3         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.10.0  | 487       | 75.74%  |
| 6.9.7   | 133       | 20.68%  |
| 6.10.1  | 20        | 3.11%   |
| 6.9.9   | 3         | 0.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.10    | 507       | 78.85%  |
| 6.9     | 136       | 21.15%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 643       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 401       | 62.07%  |
| LXQt    | 118       | 18.27%  |
| KDE6    | 59        | 9.13%   |
| GNOME   | 47        | 7.28%   |
| KDE5    | 21        | 3.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 357       | 55.52%  |
| Wayland | 286       | 44.48%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SDDM | 598       | 93%     |
| GDM  | 45        | 7%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 351       | 54.5%   |
| pl_PL | 40        | 6.21%   |
| fr_FR | 37        | 5.75%   |
| de_DE | 35        | 5.43%   |
| ru_RU | 31        | 4.81%   |
| en_GB | 26        | 4.04%   |
| es_ES | 16        | 2.48%   |
| it_IT | 15        | 2.33%   |
| pt_BR | 14        | 2.17%   |
| es_MX | 14        | 2.17%   |
| cs_CZ | 10        | 1.55%   |
| hu_HU | 6         | 0.93%   |
| es_AR | 5         | 0.78%   |
| en_CA | 5         | 0.78%   |
| es_CO | 4         | 0.62%   |
| en_IN | 4         | 0.62%   |
| tr_TR | 3         | 0.47%   |
| nl_NL | 3         | 0.47%   |
| es_GT | 3         | 0.47%   |
| nl_BE | 2         | 0.31%   |
| fr_CA | 2         | 0.31%   |
| es_VE | 2         | 0.31%   |
| es_PE | 2         | 0.31%   |
| es_CL | 2         | 0.31%   |
| de_AT | 2         | 0.31%   |
| uk_UA | 1         | 0.16%   |
| ru_UA | 1         | 0.16%   |
| pt_PT | 1         | 0.16%   |
| fi_FI | 1         | 0.16%   |
| es_BO | 1         | 0.16%   |
| en_PH | 1         | 0.16%   |
| en_NZ | 1         | 0.16%   |
| en_AU | 1         | 0.16%   |
| de_CH | 1         | 0.16%   |
| da_DK | 1         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 390       | 60.65%  |
| BIOS | 253       | 39.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Overlay | 417       | 64.85%  |
| Ext4    | 198       | 30.79%  |
| Btrfs   | 18        | 2.8%    |
| Xfs     | 6         | 0.93%   |
| F2fs    | 4         | 0.62%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 517       | 80.4%   |
| MBR  | 126       | 19.6%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 325       | 50.54%  |
| Yes       | 318       | 49.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 419       | 65.06%  |
| Yes       | 225       | 34.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 133       | 20.68%  |
| Hewlett-Packard                | 126       | 19.6%   |
| Dell                           | 84        | 13.06%  |
| ASUSTek Computer               | 83        | 12.91%  |
| Acer                           | 66        | 10.26%  |
| Toshiba                        | 25        | 3.89%   |
| Sony                           | 12        | 1.87%   |
| Samsung Electronics            | 11        | 1.71%   |
| Fujitsu                        | 11        | 1.71%   |
| Positivo                       | 9         | 1.4%    |
| Medion                         | 9         | 1.4%    |
| Apple                          | 9         | 1.4%    |
| Packard Bell                   | 8         | 1.24%   |
| MSI                            | 8         | 1.24%   |
| Unknown                        | 8         | 1.24%   |
| HUAWEI                         | 4         | 0.62%   |
| Google                         | 4         | 0.62%   |
| Notebook                       | 2         | 0.31%   |
| LG Electronics                 | 2         | 0.31%   |
| Infinix                        | 2         | 0.31%   |
| GPU Company                    | 2         | 0.31%   |
| Fujitsu Siemens                | 2         | 0.31%   |
| AMI                            | 2         | 0.31%   |
| VIT                            | 1         | 0.16%   |
| TUXEDO                         | 1         | 0.16%   |
| Timi                           | 1         | 0.16%   |
| Quanta                         | 1         | 0.16%   |
| Philco                         | 1         | 0.16%   |
| Panasonic                      | 1         | 0.16%   |
| Matsushita Electric Industrial | 1         | 0.16%   |
| Maibenben                      | 1         | 0.16%   |
| JP.ik                          | 1         | 0.16%   |
| Itautec                        | 1         | 0.16%   |
| HONOR                          | 1         | 0.16%   |
| HASEE Computer                 | 1         | 0.16%   |
| Haier                          | 1         | 0.16%   |
| Gigabyte Technology            | 1         | 0.16%   |
| Gateway                        | 1         | 0.16%   |
| eMachines                      | 1         | 0.16%   |
| Dynabook                       | 1         | 0.16%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Unknown                                 | 13        | 2.02%   |
| HP Pavilion dv6                         | 4         | 0.62%   |
| HP Notebook                             | 4         | 0.62%   |
| HP 15                                   | 4         | 0.62%   |
| Lenovo IdeaPad 3 15ALC6 82MF            | 3         | 0.47%   |
| HP Laptop 17-ca1xxx                     | 3         | 0.47%   |
| Dell Latitude E7440                     | 3         | 0.47%   |
| ASUS VivoBook_ASUSLaptop E410MAB_E410MA | 3         | 0.47%   |
| Toshiba TECRA A10                       | 2         | 0.31%   |
| Positivo C14CU51                        | 2         | 0.31%   |
| Packard Bell EasyNote LS11HR            | 2         | 0.31%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2     | 2         | 0.31%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5        | 2         | 0.31%   |
| Lenovo IdeaPad 100-15IBY 80MJ           | 2         | 0.31%   |
| Lenovo IdeaPad 1 15AMN7 82VG            | 2         | 0.31%   |
| Lenovo IdeaPad 1 15ALC7 82R4            | 2         | 0.31%   |
| Lenovo G510 20238                       | 2         | 0.31%   |
| Lenovo B50-50 80S2                      | 2         | 0.31%   |
| HP Victus by Laptop 16-e0xxx            | 2         | 0.31%   |
| HP ProBook 4530s                        | 2         | 0.31%   |
| HP Pavilion g4                          | 2         | 0.31%   |
| HP Pavilion dv4                         | 2         | 0.31%   |
| HP Pavilion 17                          | 2         | 0.31%   |
| HP Laptop 17-ak0xx                      | 2         | 0.31%   |
| HP Laptop 15-rb0xx                      | 2         | 0.31%   |
| HP Laptop 15-db0xxx                     | 2         | 0.31%   |
| HP Laptop 15-bw0xx                      | 2         | 0.31%   |
| HP Laptop 14s-fq1xxx                    | 2         | 0.31%   |
| HP Laptop 14-bs0xx                      | 2         | 0.31%   |
| HP EliteBook 6930p                      | 2         | 0.31%   |
| HP EliteBook 2170p                      | 2         | 0.31%   |
| HP Compaq CQ58                          | 2         | 0.31%   |
| HP 620                                  | 2         | 0.31%   |
| HP 255 G7 Notebook PC                   | 2         | 0.31%   |
| HP 255 15.6 inch G9 Notebook PC         | 2         | 0.31%   |
| HP 15 Notebook PC                       | 2         | 0.31%   |
| Fujitsu Siemens ESPRIMO Mobile V5505    | 2         | 0.31%   |
| Dell System Inspiron N7110              | 2         | 0.31%   |
| Dell Precision 7520                     | 2         | 0.31%   |
| Dell Latitude E7250                     | 2         | 0.31%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 60        | 9.33%   |
| Acer Aspire           | 53        | 8.24%   |
| Lenovo IdeaPad        | 43        | 6.69%   |
| Dell Latitude         | 39        | 6.07%   |
| HP Laptop             | 29        | 4.51%   |
| Dell Inspiron         | 29        | 4.51%   |
| HP EliteBook          | 22        | 3.42%   |
| HP Pavilion           | 19        | 2.95%   |
| ASUS VivoBook         | 19        | 2.95%   |
| Toshiba Satellite     | 18        | 2.8%    |
| Unknown               | 13        | 2.02%   |
| HP ProBook            | 11        | 1.71%   |
| Fujitsu LIFEBOOK      | 8         | 1.24%   |
| Packard Bell EasyNote | 7         | 1.09%   |
| HP 255                | 6         | 0.93%   |
| HP 15                 | 6         | 0.93%   |
| Dell Precision        | 5         | 0.78%   |
| ASUS TUF              | 5         | 0.78%   |
| Medion Akoya          | 4         | 0.62%   |
| HP Notebook           | 4         | 0.62%   |
| HP Compaq             | 4         | 0.62%   |
| ASUS ASUS             | 4         | 0.62%   |
| Toshiba TECRA         | 3         | 0.47%   |
| HP Victus             | 3         | 0.47%   |
| HP OMEN               | 3         | 0.47%   |
| Dell System           | 3         | 0.47%   |
| Acer Swift            | 3         | 0.47%   |
| Acer Nitro            | 3         | 0.47%   |
| Acer Extensa          | 3         | 0.47%   |
| Toshiba PORTEGE       | 2         | 0.31%   |
| Samsung RV420         | 2         | 0.31%   |
| Samsung 300E4A        | 2         | 0.31%   |
| Positivo C14CU51      | 2         | 0.31%   |
| MSI Katana            | 2         | 0.31%   |
| Lenovo V15            | 2         | 0.31%   |
| Lenovo ThinkBook      | 2         | 0.31%   |
| Lenovo Legion         | 2         | 0.31%   |
| Lenovo G510           | 2         | 0.31%   |
| Lenovo B50-50         | 2         | 0.31%   |
| Lenovo 3000           | 2         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 63        | 9.8%    |
| 2013 | 58        | 9.02%   |
| 2011 | 58        | 9.02%   |
| 2021 | 53        | 8.24%   |
| 2014 | 47        | 7.31%   |
| 2019 | 37        | 5.75%   |
| 2018 | 32        | 4.98%   |
| 2015 | 32        | 4.98%   |
| 2009 | 31        | 4.82%   |
| 2010 | 30        | 4.67%   |
| 2008 | 30        | 4.67%   |
| 2023 | 29        | 4.51%   |
| 2022 | 29        | 4.51%   |
| 2020 | 29        | 4.51%   |
| 2017 | 27        | 4.2%    |
| 2007 | 25        | 3.89%   |
| 2024 | 18        | 2.8%    |
| 2016 | 14        | 2.18%   |
| 2006 | 1         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 643       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 643       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 635       | 98.76%  |
| Yes  | 8         | 1.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 186       | 28.84%  |
| 4.01-8.0    | 185       | 28.68%  |
| 8.01-16.0   | 128       | 19.84%  |
| 16.01-24.0  | 77        | 11.94%  |
| 32.01-64.0  | 23        | 3.57%   |
| 1.01-2.0    | 22        | 3.41%   |
| 2.01-3.0    | 12        | 1.86%   |
| 64.01-256.0 | 5         | 0.78%   |
| 24.01-32.0  | 4         | 0.62%   |
| 0.51-1.0    | 3         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 382       | 58.95%  |
| 2.01-3.0 | 135       | 20.83%  |
| 0.51-1.0 | 88        | 13.58%  |
| 3.01-4.0 | 18        | 2.78%   |
| 0.01-0.5 | 13        | 2.01%   |
| 4.01-8.0 | 12        | 1.85%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 472       | 73.07%  |
| 2      | 140       | 21.67%  |
| 3      | 23        | 3.56%   |
| 0      | 7         | 1.08%   |
| 4      | 4         | 0.62%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 383       | 59.56%  |
| Yes       | 260       | 40.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 531       | 82.58%  |
| No        | 112       | 17.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 626       | 97.2%   |
| No        | 18        | 2.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 495       | 76.86%  |
| No        | 149       | 23.14%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 81        | 12.6%   |
| Poland       | 54        | 8.4%    |
| Germany      | 54        | 8.4%    |
| France       | 46        | 7.15%   |
| Russia       | 37        | 5.75%   |
| Brazil       | 28        | 4.35%   |
| UK           | 27        | 4.2%    |
| Italy        | 27        | 4.2%    |
| Spain        | 22        | 3.42%   |
| Mexico       | 21        | 3.27%   |
| Canada       | 16        | 2.49%   |
| Belgium      | 13        | 2.02%   |
| Czechia      | 11        | 1.71%   |
| Netherlands  | 10        | 1.56%   |
| India        | 10        | 1.56%   |
| Indonesia    | 9         | 1.4%    |
| Hungary      | 9         | 1.4%    |
| Norway       | 7         | 1.09%   |
| Japan        | 7         | 1.09%   |
| Argentina    | 7         | 1.09%   |
| Turkey       | 6         | 0.93%   |
| Lithuania    | 6         | 0.93%   |
| Ukraine      | 5         | 0.78%   |
| Sweden       | 5         | 0.78%   |
| South Africa | 5         | 0.78%   |
| Romania      | 5         | 0.78%   |
| Greece       | 5         | 0.78%   |
| Bulgaria     | 5         | 0.78%   |
| Austria      | 5         | 0.78%   |
| Australia    | 5         | 0.78%   |
| Venezuela    | 4         | 0.62%   |
| Slovakia     | 4         | 0.62%   |
| Kazakhstan   | 4         | 0.62%   |
| Iran         | 4         | 0.62%   |
| Finland      | 4         | 0.62%   |
| Colombia     | 4         | 0.62%   |
| China        | 4         | 0.62%   |
| Belarus      | 4         | 0.62%   |
| Algeria      | 4         | 0.62%   |
| Vietnam      | 3         | 0.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Warsaw         | 8         | 1.24%   |
| Szczecin       | 7         | 1.09%   |
| Paris          | 7         | 1.09%   |
| Moscow         | 7         | 1.09%   |
| Herentals      | 6         | 0.93%   |
| Berlin         | 6         | 0.93%   |
| Krakow         | 5         | 0.78%   |
| St Petersburg  | 4         | 0.62%   |
| Madrid         | 4         | 0.62%   |
| Bengaluru      | 4         | 0.62%   |
| Vienna         | 3         | 0.47%   |
| Turin          | 3         | 0.47%   |
| Tokyo          | 3         | 0.47%   |
| Tijuana        | 3         | 0.47%   |
| Thessaloniki   | 3         | 0.47%   |
| Sunnyvale      | 3         | 0.47%   |
| Prague         | 3         | 0.47%   |
| Poznan         | 3         | 0.47%   |
| Pistoia        | 3         | 0.47%   |
| Marktredwitz   | 3         | 0.47%   |
| Hamburg        | 3         | 0.47%   |
| Guyancourt     | 3         | 0.47%   |
| Guatemala City | 3         | 0.47%   |
| Glasgow        | 3         | 0.47%   |
| Gdansk         | 3         | 0.47%   |
| Budapest       | 3         | 0.47%   |
| Zielona Góra  | 2         | 0.31%   |
| Zapopan        | 2         | 0.31%   |
| Volgograd      | 2         | 0.31%   |
| Vilnius        | 2         | 0.31%   |
| Vantaa         | 2         | 0.31%   |
| Utuado         | 2         | 0.31%   |
| Toronto        | 2         | 0.31%   |
| The Bronx      | 2         | 0.31%   |
| Taraz          | 2         | 0.31%   |
| Sydney         | 2         | 0.31%   |
| Springfield    | 2         | 0.31%   |
| Smolensk       | 2         | 0.31%   |
| Singapore      | 2         | 0.31%   |
| Sétif         | 2         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 88        | 90     | 11.22%  |
| Seagate                      | 80        | 81     | 10.2%   |
| Sandisk                      | 59        | 61     | 7.53%   |
| WDC                          | 57        | 59     | 7.27%   |
| Toshiba                      | 55        | 56     | 7.02%   |
| Unknown                      | 45        | 48     | 5.74%   |
| Kingston                     | 44        | 44     | 5.61%   |
| Crucial                      | 28        | 28     | 3.57%   |
| Hitachi                      | 26        | 26     | 3.32%   |
| China                        | 24        | 25     | 3.06%   |
| SK hynix                     | 23        | 24     | 2.93%   |
| Micron Technology            | 18        | 19     | 2.3%    |
| Intel                        | 18        | 19     | 2.3%    |
| HGST                         | 16        | 16     | 2.04%   |
| SPCC                         | 9         | 10     | 1.15%   |
| GOODRAM                      | 9         | 10     | 1.15%   |
| Intenso                      | 8         | 8      | 1.02%   |
| KIOXIA                       | 7         | 7      | 0.89%   |
| Kingston Technology Company  | 7         | 7      | 0.89%   |
| A-DATA Technology            | 7         | 7      | 0.89%   |
| MAXIO Technology (Hangzhou)  | 6         | 6      | 0.77%   |
| Lexar                        | 6         | 6      | 0.77%   |
| Unknown                      | 6         | 6      | 0.77%   |
| USB                          | 5         | 5      | 0.64%   |
| PNY                          | 5         | 5      | 0.64%   |
| Patriot                      | 5         | 5      | 0.64%   |
| Transcend                    | 4         | 4      | 0.51%   |
| Phison Electronics           | 4         | 4      | 0.51%   |
| Micron/Crucial Technology    | 4         | 4      | 0.51%   |
| ADATA Technology             | 4         | 4      | 0.51%   |
| Solid State Storage          | 3         | 3      | 0.38%   |
| Shenzhen Longsys Electronics | 3         | 3      | 0.38%   |
| Realtek Semiconductor        | 3         | 3      | 0.38%   |
| Realtek                      | 3         | 3      | 0.38%   |
| OCZ                          | 3         | 3      | 0.38%   |
| LITEONIT                     | 3         | 3      | 0.38%   |
| LITEON                       | 3         | 3      | 0.38%   |
| JMicron Technology           | 3         | 3      | 0.38%   |
| Fujitsu                      | 3         | 3      | 0.38%   |
| Fanxiang                     | 3         | 3      | 0.38%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 15        | 1.89%   |
| Unknown MMC Card  64GB                             | 13        | 1.64%   |
| Toshiba MQ01ABF050 500GB                           | 11        | 1.38%   |
| Seagate ST9500325AS 500GB                          | 10        | 1.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 10        | 1.26%   |
| Unknown MMC Card  32GB                             | 9         | 1.13%   |
| Unknown MMC Card  128GB                            | 8         | 1.01%   |
| Seagate ST500LT012-1DG142 500GB                    | 8         | 1.01%   |
| Kingston SA400S37480G 480GB SSD                    | 7         | 0.88%   |
| Toshiba MQ04ABF100 1TB                             | 6         | 0.75%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB              | 6         | 0.75%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB   | 6         | 0.75%   |
| Crucial CT240BX500SSD1 240GB                       | 6         | 0.75%   |
| Unknown                                            | 6         | 0.75%   |
| Unknown MMC Card  16GB                             | 5         | 0.63%   |
| Seagate ST1000LM048-2E7172 1TB                     | 5         | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB                     | 5         | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 5         | 0.63%   |
| Intel SSDPEKNU512GZ 512GB                          | 5         | 0.63%   |
| HGST HTS545050A7E680 500GB                         | 5         | 0.63%   |
| China SSD 256GB                                    | 5         | 0.63%   |
| WDC WD5000LPCX-24VHAT0 500GB                       | 4         | 0.5%    |
| WDC WD10JPVX-60JC3T1 1TB                           | 4         | 0.5%    |
| USB SanDisk 3.2Gen1 496GB                          | 4         | 0.5%    |
| Toshiba XG6 NVMe SSD Controller 1024GB             | 4         | 0.5%    |
| Toshiba MQ01ABD100 1TB                             | 4         | 0.5%    |
| SPCC Solid State Disk 512GB                        | 4         | 0.5%    |
| Seagate ST500LM012 HN-M500MBB 500GB                | 4         | 0.5%    |
| Sandisk WD Black SN850 1TB                         | 4         | 0.5%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB   | 4         | 0.5%    |
| SanDisk SSD PLUS 480GB                             | 4         | 0.5%    |
| Samsung SSD 860 EVO 250GB                          | 4         | 0.5%    |
| Samsung SSD 850 EVO 250GB                          | 4         | 0.5%    |
| Samsung MZVLQ512HBLU-00BH1 512GB                   | 4         | 0.5%    |
| Kingston SA400S37120G 120GB SSD                    | 4         | 0.5%    |
| Hitachi HTS547575A9E384 752GB                      | 4         | 0.5%    |
| GOODRAM SSDPR-CX400-512-G2 512GB                   | 4         | 0.5%    |
| Crucial CT500MX500SSD1 500GB                       | 4         | 0.5%    |
| Crucial CT500BX500SSD1 500GB                       | 4         | 0.5%    |
| China SSD 128GB                                    | 4         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 77        | 78     | 33.62%  |
| WDC                 | 46        | 47     | 20.09%  |
| Toshiba             | 45        | 46     | 19.65%  |
| Hitachi             | 26        | 26     | 11.35%  |
| HGST                | 16        | 16     | 6.99%   |
| Samsung Electronics | 5         | 5      | 2.18%   |
| Fujitsu             | 3         | 3      | 1.31%   |
| USB3.0              | 2         | 2      | 0.87%   |
| Unknown             | 2         | 2      | 0.87%   |
| JMicron Technology  | 2         | 2      | 0.87%   |
| USB                 | 1         | 1      | 0.44%   |
| TO Exter            | 1         | 1      | 0.44%   |
| SAGE                | 1         | 1      | 0.44%   |
| Esmart              | 1         | 1      | 0.44%   |
| ASMT                | 1         | 1      | 0.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 47        | 47     | 14.92%  |
| Kingston            | 40        | 40     | 12.7%   |
| Crucial             | 28        | 28     | 8.89%   |
| SanDisk             | 26        | 26     | 8.25%   |
| China               | 24        | 25     | 7.62%   |
| WDC                 | 11        | 12     | 3.49%   |
| SPCC                | 9         | 10     | 2.86%   |
| GOODRAM             | 9         | 10     | 2.86%   |
| Intenso             | 8         | 8      | 2.54%   |
| A-DATA Technology   | 7         | 7      | 2.22%   |
| Lexar               | 6         | 6      | 1.9%    |
| SK hynix            | 5         | 5      | 1.59%   |
| PNY                 | 5         | 5      | 1.59%   |
| Patriot             | 5         | 5      | 1.59%   |
| Unknown             | 5         | 5      | 1.59%   |
| Transcend           | 4         | 4      | 1.27%   |
| OCZ                 | 3         | 3      | 0.95%   |
| LITEONIT            | 3         | 3      | 0.95%   |
| LITEON              | 3         | 3      | 0.95%   |
| Intel               | 3         | 3      | 0.95%   |
| Apple               | 3         | 3      | 0.95%   |
| Toshiba             | 2         | 2      | 0.63%   |
| SSSTC               | 2         | 2      | 0.63%   |
| Plextor             | 2         | 2      | 0.63%   |
| Micron Technology   | 2         | 2      | 0.63%   |
| KingSpec            | 2         | 2      | 0.63%   |
| KingDian            | 2         | 2      | 0.63%   |
| Fanxiang            | 2         | 2      | 0.63%   |
| Corsair             | 2         | 2      | 0.63%   |
| ASMT                | 2         | 2      | 0.63%   |
| Apacer              | 2         | 2      | 0.63%   |
| XSTAR               | 1         | 1      | 0.32%   |
| XrayDisk            | 1         | 1      | 0.32%   |
| Verbatim            | 1         | 1      | 0.32%   |
| Thinkplus           | 1         | 1      | 0.32%   |
| Team                | 1         | 1      | 0.32%   |
| TCSUNBOW            | 1         | 1      | 0.32%   |
| Super Talent        | 1         | 1      | 0.32%   |
| sk600               | 1         | 1      | 0.32%   |
| SATA3 12            | 1         | 1      | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 289       | 321    | 39.16%  |
| HDD     | 222       | 232    | 30.08%  |
| NVMe    | 171       | 190    | 23.17%  |
| MMC     | 44        | 47     | 5.96%   |
| Unknown | 12        | 13     | 1.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 457       | 518    | 63.83%  |
| NVMe | 169       | 186    | 23.6%   |
| SAS  | 46        | 52     | 6.42%   |
| MMC  | 44        | 47     | 6.15%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 363       | 403    | 72.02%  |
| 0.51-1.0   | 122       | 131    | 24.21%  |
| 1.01-2.0   | 17        | 17     | 3.37%   |
| 3.01-4.0   | 2         | 2      | 0.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 296       | 45.96%  |
| 101-250        | 118       | 18.32%  |
| 251-500        | 84        | 13.04%  |
| 501-1000       | 39        | 6.06%   |
| 51-100         | 31        | 4.81%   |
| Unknown        | 27        | 4.19%   |
| 21-50          | 26        | 4.04%   |
| 1001-2000      | 15        | 2.33%   |
| 2001-3000      | 7         | 1.09%   |
| More than 3000 | 1         | 0.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 527       | 81.71%  |
| 21-50    | 28        | 4.34%   |
| Unknown  | 27        | 4.19%   |
| 0        | 24        | 3.72%   |
| 101-250  | 15        | 2.33%   |
| 51-100   | 13        | 2.02%   |
| 251-500  | 7         | 1.09%   |
| 501-1000 | 4         | 0.62%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB            | 6         | 6      | 5.13%   |
| Toshiba MQ01ABF050 500GB             | 5         | 6      | 4.27%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 4      | 3.42%   |
| WDC WD Green 2.5 240GB               | 3         | 3      | 2.56%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 3      | 2.56%   |
| Hitachi HTS545032B9A300 320GB        | 3         | 3      | 2.56%   |
| WDC WD10JPVX-60JC3T1 1TB             | 2         | 2      | 1.71%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 2         | 2      | 1.71%   |
| Seagate ST9160412AS 160GB            | 2         | 2      | 1.71%   |
| Seagate ST500LT012-9WS142 500GB      | 2         | 2      | 1.71%   |
| Seagate ST320LT012-9WS14C 320GB      | 2         | 2      | 1.71%   |
| Seagate ST320LT007-9ZV142 320GB      | 2         | 2      | 1.71%   |
| Hitachi HTS541612J9SA00 120GB        | 2         | 2      | 1.71%   |
| HGST HTS545050A7E680 500GB           | 2         | 2      | 1.71%   |
| Crucial CT525MX300SSD1 528GB         | 2         | 2      | 1.71%   |
| WDC WD7500BPVX-60JC3T0 752GB         | 1         | 1      | 0.85%   |
| WDC WD6400BPVT-60HXZT1 640GB         | 1         | 1      | 0.85%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 1      | 0.85%   |
| WDC WD5000LPVT-75G33T0 500GB         | 1         | 1      | 0.85%   |
| WDC WD5000LPLX-00ZNTT0 500GB         | 1         | 1      | 0.85%   |
| WDC WD5000LPCX-60VHAT1 500GB         | 1         | 1      | 0.85%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 1      | 0.85%   |
| WDC WD5000BPVT-22A1YT0 500GB         | 1         | 1      | 0.85%   |
| WDC WD5000BPVT-08HXZT3 500GB         | 1         | 1      | 0.85%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 1         | 1      | 0.85%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 1      | 0.85%   |
| Toshiba MQ04ABF100 1TB               | 1         | 1      | 0.85%   |
| Toshiba MQ01ABD100V 1TB              | 1         | 1      | 0.85%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 0.85%   |
| Toshiba MQ01ABD032 320GB             | 1         | 1      | 0.85%   |
| Toshiba MQ01ABB200 2TB               | 1         | 1      | 0.85%   |
| Toshiba MK7559GSXP 752GB             | 1         | 1      | 0.85%   |
| Toshiba MK6475GSX 640GB              | 1         | 1      | 0.85%   |
| Toshiba MK6465GSX 640GB              | 1         | 1      | 0.85%   |
| Toshiba MK3265GSX 320GB              | 1         | 1      | 0.85%   |
| Toshiba MK1676GSX H 160GB            | 1         | 1      | 0.85%   |
| Toshiba MK1234GSX 120GB              | 1         | 1      | 0.85%   |
| SSSTC CVB-8D128-HP 128GB             | 1         | 1      | 0.85%   |
| SSSTC CV8-8E128-HP 128GB SSD         | 1         | 1      | 0.85%   |
| SPCC Solid State Disk 120GB          | 1         | 1      | 0.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 33        | 33     | 28.21%  |
| WDC                         | 16        | 16     | 13.68%  |
| Toshiba                     | 16        | 17     | 13.68%  |
| Hitachi                     | 9         | 9      | 7.69%   |
| Samsung Electronics         | 6         | 6      | 5.13%   |
| HGST                        | 6         | 6      | 5.13%   |
| SanDisk                     | 4         | 4      | 3.42%   |
| Kingston                    | 4         | 4      | 3.42%   |
| SK hynix                    | 3         | 3      | 2.56%   |
| Fujitsu                     | 3         | 3      | 2.56%   |
| Crucial                     | 3         | 3      | 2.56%   |
| SSSTC                       | 2         | 2      | 1.71%   |
| China                       | 2         | 2      | 1.71%   |
| SPCC                        | 1         | 1      | 0.85%   |
| sk600                       | 1         | 1      | 0.85%   |
| Micron Technology           | 1         | 1      | 0.85%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.85%   |
| LITEONIT                    | 1         | 1      | 0.85%   |
| GLOWAY                      | 1         | 1      | 0.85%   |
| Corsair                     | 1         | 1      | 0.85%   |
| ASMT                        | 1         | 1      | 0.85%   |
| Apple                       | 1         | 1      | 0.85%   |
| Acer                        | 1         | 1      | 0.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 33     | 38.82%  |
| Toshiba             | 16        | 17     | 18.82%  |
| WDC                 | 13        | 13     | 15.29%  |
| Hitachi             | 9         | 9      | 10.59%  |
| HGST                | 6         | 6      | 7.06%   |
| Samsung Electronics | 4         | 4      | 4.71%   |
| Fujitsu             | 3         | 3      | 3.53%   |
| ASMT                | 1         | 1      | 1.18%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 85        | 86     | 72.65%  |
| SSD  | 29        | 29     | 24.79%  |
| NVMe | 3         | 3      | 2.56%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM250HI 250GB | 1         | 1      | 50%     |
| HGST HTS541010A9E680 1TB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| HGST                | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 514       | 595    | 72.19%  |
| Malfunc  | 117       | 118    | 16.43%  |
| Detected | 79        | 88     | 11.1%   |
| Failed   | 2         | 2      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 428       | 60.11%  |
| AMD                            | 110       | 15.45%  |
| Samsung Electronics            | 38        | 5.34%   |
| SanDisk                        | 33        | 4.63%   |
| SK hynix                       | 18        | 2.53%   |
| Micron Technology              | 16        | 2.25%   |
| Kingston Technology Company    | 11        | 1.54%   |
| Toshiba America Info Systems   | 8         | 1.12%   |
| KIOXIA                         | 7         | 0.98%   |
| MAXIO Technology (Hangzhou)    | 6         | 0.84%   |
| Phison Electronics             | 5         | 0.7%    |
| Nvidia                         | 5         | 0.7%    |
| Union Memory (Shenzhen)        | 4         | 0.56%   |
| Solid State Storage Technology | 4         | 0.56%   |
| Micron/Crucial Technology      | 4         | 0.56%   |
| ADATA Technology               | 4         | 0.56%   |
| Shenzhen Longsys Electronics   | 3         | 0.42%   |
| Realtek Semiconductor          | 3         | 0.42%   |
| Silicon Motion                 | 2         | 0.28%   |
| JMicron Technology             | 2         | 0.28%   |
| Marvell Technology Group       | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 95        | 12.43%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 75        | 9.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 42        | 5.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 31        | 4.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 29        | 3.8%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 27        | 3.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 26        | 3.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 23        | 3.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 22        | 2.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 20        | 2.62%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 18        | 2.36%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 17        | 2.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 17        | 2.23%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 15        | 1.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 11        | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 11        | 1.44%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                     | 10        | 1.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 1.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 10        | 1.31%   |
| Intel Volume Management Device NVMe RAID Controller                              | 9         | 1.18%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 9         | 1.18%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 1.18%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                 | 7         | 0.92%   |
| Intel Tiger Lake-LP SATA Controller                                              | 7         | 0.92%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 6         | 0.79%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 6         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 6         | 0.79%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 5         | 0.65%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                                | 5         | 0.65%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 5         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 0.65%   |
| Nvidia MCP79 AHCI Controller                                                     | 5         | 0.65%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 5         | 0.65%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 5         | 0.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 5         | 0.65%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 4         | 0.52%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 4         | 0.52%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 4         | 0.52%   |
| Intel RST Volume Management Device Controller                                    | 4         | 0.52%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 485       | 65.72%  |
| NVMe | 169       | 22.9%   |
| IDE  | 50        | 6.78%   |
| RAID | 34        | 4.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 478       | 74.34%  |
| AMD    | 165       | 25.66%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 5500U with Radeon Graphics        | 13        | 2.02%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 10        | 1.56%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 9         | 1.4%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 9         | 1.4%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 9         | 1.4%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 9         | 1.4%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 8         | 1.24%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 1.24%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 7         | 1.09%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 7         | 1.09%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 0.93%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 6         | 0.93%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 6         | 0.93%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 6         | 0.93%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 0.93%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.78%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 0.78%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 0.78%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 5         | 0.78%   |
| Intel Celeron CPU N2830 @ 2.16GHz             | 5         | 0.78%   |
| Intel 12th Gen Core i5-1235U                  | 5         | 0.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 0.78%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 0.78%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 0.78%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 0.78%   |
| AMD E-450 APU with Radeon HD Graphics         | 5         | 0.78%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 4         | 0.62%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 4         | 0.62%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 4         | 0.62%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 4         | 0.62%   |
| Intel Core i5-3427U CPU @ 1.80GHz             | 4         | 0.62%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 4         | 0.62%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.62%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 0.62%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 0.62%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 4         | 0.62%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 4         | 0.62%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 4         | 0.62%   |
| Intel Celeron CPU 1007U @ 1.50GHz             | 4         | 0.62%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 4         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 131       | 20.37%  |
| Intel Celeron                        | 78        | 12.13%  |
| Intel Core i3                        | 64        | 9.95%   |
| Other                                | 55        | 8.55%   |
| Intel Core i7                        | 53        | 8.24%   |
| AMD Ryzen 5                          | 46        | 7.15%   |
| Intel Core 2 Duo                     | 44        | 6.84%   |
| AMD Ryzen 7                          | 30        | 4.67%   |
| Intel Pentium                        | 25        | 3.89%   |
| AMD Ryzen 3                          | 11        | 1.71%   |
| Intel Pentium Dual-Core              | 8         | 1.24%   |
| AMD A8                               | 8         | 1.24%   |
| Intel Pentium Dual                   | 7         | 1.09%   |
| AMD E1                               | 7         | 1.09%   |
| AMD A6                               | 7         | 1.09%   |
| Intel Atom                           | 6         | 0.93%   |
| AMD E                                | 6         | 0.93%   |
| AMD A4                               | 6         | 0.93%   |
| AMD A10                              | 6         | 0.93%   |
| Intel Core                           | 5         | 0.78%   |
| AMD E2                               | 5         | 0.78%   |
| Intel Genuine                        | 4         | 0.62%   |
| AMD Athlon                           | 4         | 0.62%   |
| Intel Pentium Silver                 | 3         | 0.47%   |
| AMD Turion 64 X2 Mobile              | 3         | 0.47%   |
| AMD Ryzen 5 PRO                      | 3         | 0.47%   |
| Intel Xeon                           | 2         | 0.31%   |
| Intel Core i9                        | 2         | 0.31%   |
| AMD Ryzen 9                          | 2         | 0.31%   |
| AMD C-60                             | 2         | 0.31%   |
| AMD C-50                             | 2         | 0.31%   |
| Intel Pentium Gold                   | 1         | 0.16%   |
| Intel Core M                         | 1         | 0.16%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.16%   |
| AMD Turion II Dual-Core              | 1         | 0.16%   |
| AMD Turion 64 Mobile                 | 1         | 0.16%   |
| AMD Ryzen 7 PRO                      | 1         | 0.16%   |
| AMD PRO A8                           | 1         | 0.16%   |
| AMD Athlon II Dual-Core              | 1         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 400       | 62.21%  |
| 4      | 139       | 21.62%  |
| 6      | 39        | 6.07%   |
| 8      | 33        | 5.13%   |
| 10     | 11        | 1.71%   |
| 1      | 7         | 1.09%   |
| 14     | 5         | 0.78%   |
| 12     | 5         | 0.78%   |
| 16     | 4         | 0.62%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 632       | 98.29%  |
| 2      | 11        | 1.71%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 393       | 61.12%  |
| 1      | 250       | 38.88%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 643       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 643       | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| IvyBridge         | 65        | 10.11%  |
| SandyBridge       | 59        | 9.18%   |
| Haswell           | 52        | 8.09%   |
| KabyLake          | 39        | 6.07%   |
| Unknown           | 39        | 6.07%   |
| Penryn            | 38        | 5.91%   |
| Westmere          | 37        | 5.75%   |
| Silvermont        | 34        | 5.29%   |
| Core              | 29        | 4.51%   |
| Broadwell         | 28        | 4.35%   |
| Zen+              | 24        | 3.73%   |
| Alderlake Hybrid  | 24        | 3.73%   |
| Zen 3             | 23        | 3.58%   |
| Goldmont plus     | 22        | 3.42%   |
| Excavator         | 20        | 3.11%   |
| TigerLake         | 16        | 2.49%   |
| Bobcat            | 15        | 2.33%   |
| Zen 2             | 12        | 1.87%   |
| Puma              | 12        | 1.87%   |
| Zen               | 8         | 1.24%   |
| Goldmont          | 6         | 0.93%   |
| Tremont           | 5         | 0.78%   |
| Bonnell           | 5         | 0.78%   |
| Piledriver        | 4         | 0.62%   |
| Meteorlake Hybrid | 4         | 0.62%   |
| K8 Hammer         | 4         | 0.62%   |
| Jaguar            | 4         | 0.62%   |
| Nehalem           | 3         | 0.47%   |
| K10 Llano         | 3         | 0.47%   |
| Skylake           | 2         | 0.31%   |
| K10               | 2         | 0.31%   |
| Gracemont         | 2         | 0.31%   |
| K8 & K10 hybrid   | 1         | 0.16%   |
| IceLake           | 1         | 0.16%   |
| CometLake         | 1         | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 443       | 59.62%  |
| AMD    | 187       | 25.17%  |
| Nvidia | 113       | 15.21%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 63        | 7.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 56        | 7.11%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 32        | 4.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 29        | 3.68%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 28        | 3.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 27        | 3.43%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 25        | 3.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 24        | 3.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 24        | 3.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 2.54%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 19        | 2.41%   |
| AMD Lucienne                                                                             | 19        | 2.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 2.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14        | 1.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 1.78%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 13        | 1.65%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 13        | 1.65%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 12        | 1.52%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 1.4%    |
| AMD Barcelo                                                                              | 9         | 1.14%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 8         | 1.02%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 7         | 0.89%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 0.89%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 7         | 0.89%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 0.89%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 7         | 0.89%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 6         | 0.76%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 6         | 0.76%   |
| AMD Rembrandt [Radeon 680M]                                                              | 6         | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.63%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 5         | 0.63%   |
| Intel JasperLake [UHD Graphics]                                                          | 5         | 0.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 0.63%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 5         | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 0.63%   |
| AMD Mendocino [Radeon 610M]                                                              | 5         | 0.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.51%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 4         | 0.51%   |
| Nvidia C79 [GeForce 9400M]                                                               | 4         | 0.51%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                                 | 4         | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 308       | 47.9%   |
| 1 x AMD        | 135       | 21%     |
| Intel + Nvidia | 68        | 10.58%  |
| 2 x Intel      | 53        | 8.24%   |
| 1 x Nvidia     | 26        | 4.04%   |
| 2 x AMD        | 20        | 3.11%   |
| AMD + Nvidia   | 18        | 2.8%    |
| Intel + AMD    | 14        | 2.18%   |
| 2 x Nvidia     | 1         | 0.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 594       | 92.38%  |
| Unknown     | 48        | 7.47%   |
| Proprietary | 1         | 0.16%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 370       | 57.54%  |
| 0.01-0.5   | 113       | 17.57%  |
| 1.01-2.0   | 66        | 10.26%  |
| 0.51-1.0   | 52        | 8.09%   |
| 3.01-4.0   | 20        | 3.11%   |
| 7.01-8.0   | 10        | 1.56%   |
| 5.01-6.0   | 10        | 1.56%   |
| 2.01-3.0   | 2         | 0.31%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 146       | 22.15%  |
| LG Display              | 109       | 16.54%  |
| BOE                     | 98        | 14.87%  |
| Chimei Innolux          | 92        | 13.96%  |
| Samsung Electronics     | 84        | 12.75%  |
| Chi Mei Optoelectronics | 14        | 2.12%   |
| LG Philips              | 11        | 1.67%   |
| Lenovo                  | 10        | 1.52%   |
| InfoVision              | 9         | 1.37%   |
| Apple                   | 9         | 1.37%   |
| Dell                    | 8         | 1.21%   |
| Acer                    | 8         | 1.21%   |
| Sharp                   | 6         | 0.91%   |
| PANDA                   | 6         | 0.91%   |
| AOC                     | 6         | 0.91%   |
| Toshiba                 | 4         | 0.61%   |
| InnoLux Display         | 4         | 0.61%   |
| CSO                     | 4         | 0.61%   |
| JDZ                     | 3         | 0.46%   |
| Iiyama                  | 3         | 0.46%   |
| Philips                 | 2         | 0.3%    |
| Hewlett-Packard         | 2         | 0.3%    |
| Ancor Communications    | 2         | 0.3%    |
| Vizio                   | 1         | 0.15%   |
| ViewSonic               | 1         | 0.15%   |
| TVW                     | 1         | 0.15%   |
| STA                     | 1         | 0.15%   |
| Sony                    | 1         | 0.15%   |
| Sceptre Tech            | 1         | 0.15%   |
| RLT                     | 1         | 0.15%   |
| Medion                  | 1         | 0.15%   |
| MDT                     | 1         | 0.15%   |
| KDC                     | 1         | 0.15%   |
| HUAWEI                  | 1         | 0.15%   |
| HKC                     | 1         | 0.15%   |
| HannStar                | 1         | 0.15%   |
| GVE                     | 1         | 0.15%   |
| Goldstar                | 1         | 0.15%   |
| Gigabyte Technology     | 1         | 0.15%   |
| Fujitsu Siemens         | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 7         | 1.06%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 7         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.91%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 6         | 0.91%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 5         | 0.76%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 5         | 0.76%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 4         | 0.6%    |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch     | 4         | 0.6%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 4         | 0.6%    |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 4         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 4         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 4         | 0.6%    |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                    | 4         | 0.6%    |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch            | 4         | 0.6%    |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 4         | 0.6%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.6%    |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 4         | 0.6%    |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 3         | 0.45%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 3         | 0.45%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 3         | 0.45%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 3         | 0.45%   |
| LG Display LCD Monitor LGD01CA 1600x900 382x215mm 17.3-inch              | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1745 1600x900 382x214mm 17.2-inch          | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 3         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1472 1366x768 309x174mm 14.0-inch          | 3         | 0.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO8074 1280x800 331x207mm 15.4-inch            | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch            | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch            | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch            | 3         | 0.45%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 3         | 0.45%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 2         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 278       | 42.9%   |
| 1920x1080 (FHD)    | 188       | 29.01%  |
| 1600x900 (HD+)     | 61        | 9.41%   |
| 1280x800 (WXGA)    | 33        | 5.09%   |
| 1920x1200 (WUXGA)  | 21        | 3.24%   |
| 1440x900 (WXGA+)   | 12        | 1.85%   |
| 3840x2160 (4K)     | 10        | 1.54%   |
| 2560x1600          | 8         | 1.23%   |
| 2560x1440 (QHD)    | 8         | 1.23%   |
| 2880x1800          | 5         | 0.77%   |
| 3200x2000          | 4         | 0.62%   |
| 3200x1800 (QHD+)   | 3         | 0.46%   |
| 1024x600           | 3         | 0.46%   |
| 3840x2400          | 2         | 0.31%   |
| 3440x1440          | 2         | 0.31%   |
| 1920x540           | 2         | 0.31%   |
| 1680x1050 (WSXGA+) | 2         | 0.31%   |
| 2880x1620          | 1         | 0.15%   |
| 2520x1680          | 1         | 0.15%   |
| 2288x1287          | 1         | 0.15%   |
| 1680x945           | 1         | 0.15%   |
| 1360x768           | 1         | 0.15%   |
| 1280x1024 (SXGA)   | 1         | 0.15%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 305       | 46.07%  |
| 14      | 96        | 14.5%   |
| 17      | 68        | 10.27%  |
| 13      | 62        | 9.37%   |
| 16      | 21        | 3.17%   |
| 12      | 21        | 3.17%   |
| 11      | 21        | 3.17%   |
| 18      | 11        | 1.66%   |
| 24      | 10        | 1.51%   |
| 23      | 9         | 1.36%   |
| 21      | 8         | 1.21%   |
| 27      | 6         | 0.91%   |
| 10      | 4         | 0.6%    |
| 31      | 3         | 0.45%   |
| 84      | 2         | 0.3%    |
| 40      | 2         | 0.3%    |
| 34      | 2         | 0.3%    |
| 32      | 2         | 0.3%    |
| 22      | 2         | 0.3%    |
| 19      | 2         | 0.3%    |
| 54      | 1         | 0.15%   |
| 28      | 1         | 0.15%   |
| 25      | 1         | 0.15%   |
| 20      | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 443       | 66.92%  |
| 351-400     | 82        | 12.39%  |
| 201-300     | 74        | 11.18%  |
| 501-600     | 25        | 3.78%   |
| 401-500     | 23        | 3.47%   |
| 601-700     | 5         | 0.76%   |
| 701-800     | 4         | 0.6%    |
| 801-900     | 2         | 0.3%    |
| 1501-2000   | 2         | 0.3%    |
| 1001-1500   | 1         | 0.15%   |
| Unknown     | 1         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 538       | 85.53%  |
| 16/10 | 85        | 13.51%  |
| 3/2   | 3         | 0.48%   |
| 21/9  | 2         | 0.32%   |
| 5/4   | 1         | 0.16%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 309       | 46.75%  |
| 81-90          | 134       | 20.27%  |
| 121-130        | 55        | 8.32%   |
| 71-80          | 22        | 3.33%   |
| 61-70          | 21        | 3.18%   |
| 51-60          | 21        | 3.18%   |
| 201-250        | 21        | 3.18%   |
| 111-120        | 17        | 2.57%   |
| 131-140        | 12        | 1.82%   |
| 141-150        | 11        | 1.66%   |
| 351-500        | 8         | 1.21%   |
| 251-300        | 7         | 1.06%   |
| 301-350        | 6         | 0.91%   |
| 151-200        | 5         | 0.76%   |
| 41-50          | 4         | 0.61%   |
| More than 1000 | 3         | 0.45%   |
| 501-1000       | 2         | 0.3%    |
| 91-100         | 2         | 0.3%    |
| Unknown        | 1         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 295       | 45.18%  |
| 121-160       | 217       | 33.23%  |
| 51-100        | 90        | 13.78%  |
| 161-240       | 37        | 5.67%   |
| More than 240 | 11        | 1.68%   |
| 1-50          | 2         | 0.31%   |
| Unknown       | 1         | 0.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 579       | 90.05%  |
| 2     | 45        | 7%      |
| 0     | 19        | 2.95%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 363       | 36.63%  |
| Intel                             | 268       | 27.04%  |
| Qualcomm Atheros                  | 178       | 17.96%  |
| Broadcom                          | 70        | 7.06%   |
| MediaTek                          | 24        | 2.42%   |
| Marvell Technology Group          | 12        | 1.21%   |
| Broadcom Limited                  | 11        | 1.11%   |
| Ralink                            | 8         | 0.81%   |
| ASIX Electronics                  | 8         | 0.81%   |
| Ericsson Business Mobile Networks | 6         | 0.61%   |
| Sierra Wireless                   | 5         | 0.5%    |
| Nvidia                            | 4         | 0.4%    |
| TP-Link                           | 3         | 0.3%    |
| Qualcomm                          | 3         | 0.3%    |
| JMicron Technology                | 3         | 0.3%    |
| Hewlett-Packard                   | 3         | 0.3%    |
| Dell                              | 3         | 0.3%    |
| Xiaomi                            | 2         | 0.2%    |
| Ralink Technology                 | 2         | 0.2%    |
| Mercucys                          | 2         | 0.2%    |
| Edimax Technology                 | 2         | 0.2%    |
| ZTE WCDMA Technologies MSM        | 1         | 0.1%    |
| Toshiba                           | 1         | 0.1%    |
| ROCCAT                            | 1         | 0.1%    |
| Qualcomm Atheros Communications   | 1         | 0.1%    |
| OPPO Electronics                  | 1         | 0.1%    |
| Microsoft                         | 1         | 0.1%    |
| Huawei Technologies               | 1         | 0.1%    |
| DisplayLink                       | 1         | 0.1%    |
| Apple                             | 1         | 0.1%    |
| AMD                               | 1         | 0.1%    |
| ADMtek                            | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 188       | 15.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 90        | 7.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 40        | 3.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 35        | 2.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 32        | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 25        | 2.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 25        | 2.05%   |
| Intel Wireless 7260                                                     | 24        | 1.97%   |
| Intel Wireless 8265 / 8275                                              | 22        | 1.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 22        | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 21        | 1.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 20        | 1.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 18        | 1.48%   |
| Intel Wireless 7265                                                     | 16        | 1.31%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 1.31%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 15        | 1.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 15        | 1.23%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 14        | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 1.07%   |
| Intel Wireless 3160                                                     | 12        | 0.98%   |
| Intel Wi-Fi 6 AX201                                                     | 12        | 0.98%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 11        | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 11        | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 11        | 0.9%    |
| Intel Ethernet Connection I218-LM                                       | 11        | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 10        | 0.82%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 10        | 0.82%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 10        | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                                   | 10        | 0.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 10        | 0.82%   |
| Intel 82567LM Gigabit Network Connection                                | 10        | 0.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                                   | 9         | 0.74%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 8         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 0.66%   |
| Intel Wireless 3165                                                     | 8         | 0.66%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 0.66%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.66%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.57%   |
| Intel Centrino Advanced-N 6235                                          | 7         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 250       | 38.46%  |
| Qualcomm Atheros                  | 155       | 23.85%  |
| Realtek Semiconductor             | 140       | 21.54%  |
| Broadcom                          | 45        | 6.92%   |
| MediaTek                          | 23        | 3.54%   |
| Ralink                            | 8         | 1.23%   |
| Broadcom Limited                  | 6         | 0.92%   |
| Sierra Wireless                   | 5         | 0.77%   |
| TP-Link                           | 3         | 0.46%   |
| Qualcomm                          | 3         | 0.46%   |
| Dell                              | 3         | 0.46%   |
| Ralink Technology                 | 2         | 0.31%   |
| Mercucys                          | 2         | 0.31%   |
| Edimax Technology                 | 2         | 0.31%   |
| Qualcomm Atheros Communications   | 1         | 0.15%   |
| Microsoft                         | 1         | 0.15%   |
| Ericsson Business Mobile Networks | 1         | 0.15%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 40        | 6.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 35        | 5.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 32        | 4.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 25        | 3.83%   |
| Intel Wireless 7260                                                     | 24        | 3.68%   |
| Intel Wireless 8265 / 8275                                              | 22        | 3.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 22        | 3.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 21        | 3.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 20        | 3.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 18        | 2.76%   |
| Intel Wireless 7265                                                     | 16        | 2.45%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 2.45%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 15        | 2.3%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 14        | 2.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 1.99%   |
| Intel Wireless 3160                                                     | 12        | 1.84%   |
| Intel Wi-Fi 6 AX201                                                     | 12        | 1.84%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 11        | 1.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 11        | 1.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 1.38%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 9         | 1.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 1.23%   |
| Intel Wireless 3165                                                     | 8         | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 1.23%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 1.23%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 7         | 1.07%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 1.07%   |
| Intel Centrino Advanced-N 6235                                          | 7         | 1.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 0.92%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 6         | 0.92%   |
| Intel Centrino Wireless-N 2200                                          | 6         | 0.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 0.92%   |
| Intel Centrino Advanced-N 6200                                          | 6         | 0.92%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 0.77%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 5         | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.77%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 5         | 0.77%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 300       | 54.35%  |
| Intel                      | 125       | 22.64%  |
| Qualcomm Atheros           | 53        | 9.6%    |
| Broadcom                   | 31        | 5.62%   |
| Marvell Technology Group   | 12        | 2.17%   |
| ASIX Electronics           | 8         | 1.45%   |
| Broadcom Limited           | 6         | 1.09%   |
| Nvidia                     | 4         | 0.72%   |
| JMicron Technology         | 3         | 0.54%   |
| Xiaomi                     | 2         | 0.36%   |
| ZTE WCDMA Technologies MSM | 1         | 0.18%   |
| OPPO Electronics           | 1         | 0.18%   |
| MediaTek                   | 1         | 0.18%   |
| Huawei Technologies        | 1         | 0.18%   |
| Hewlett-Packard            | 1         | 0.18%   |
| DisplayLink                | 1         | 0.18%   |
| Apple                      | 1         | 0.18%   |
| ADMtek                     | 1         | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 188       | 33.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 90        | 16.19%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 25        | 4.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 15        | 2.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 11        | 1.98%   |
| Intel Ethernet Connection I218-LM                                      | 11        | 1.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 10        | 1.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 10        | 1.8%    |
| Intel Ethernet Connection (4) I219-LM                                  | 10        | 1.8%    |
| Intel 82567LM Gigabit Network Connection                               | 10        | 1.8%    |
| Intel Ethernet Connection (3) I218-LM                                  | 9         | 1.62%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 7         | 1.26%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 7         | 1.26%   |
| ASIX AX88179 Gigabit Ethernet                                          | 7         | 1.26%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 6         | 1.08%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 6         | 1.08%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 1.08%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5         | 0.9%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 4         | 0.72%   |
| Nvidia MCP79 Ethernet                                                  | 4         | 0.72%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 0.72%   |
| Intel Ethernet Connection (5) I219-LM                                  | 4         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                                   | 4         | 0.72%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.72%   |
| Intel 82566MM Gigabit Network Connection                               | 4         | 0.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 4         | 0.72%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 4         | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 0.54%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 3         | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 3         | 0.54%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 3         | 0.54%   |
| Intel WiMAX Connection 2400m                                           | 3         | 0.54%   |
| Intel Ethernet Connection I217-V                                       | 3         | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 0.54%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 0.54%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 0.54%   |
| Intel Ethernet Connection (3) I218-V                                   | 3         | 0.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 0.54%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 3         | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 627       | 53.73%  |
| Ethernet | 530       | 45.42%  |
| Modem    | 9         | 0.77%   |
| Unknown  | 1         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 466       | 73.04%  |
| Ethernet | 172       | 26.96%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 500       | 77.64%  |
| 1     | 137       | 21.27%  |
| 0     | 6         | 0.93%   |
| 3     | 1         | 0.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 420       | 65.02%  |
| Yes  | 226       | 34.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 179       | 36.09%  |
| Realtek Semiconductor           | 85        | 17.14%  |
| Qualcomm Atheros Communications | 45        | 9.07%   |
| Foxconn / Hon Hai               | 33        | 6.65%   |
| Broadcom                        | 33        | 6.65%   |
| IMC Networks                    | 29        | 5.85%   |
| Lite-On Technology              | 24        | 4.84%   |
| Dell                            | 13        | 2.62%   |
| Toshiba                         | 12        | 2.42%   |
| Hewlett-Packard                 | 8         | 1.61%   |
| Apple                           | 8         | 1.61%   |
| Cambridge Silicon Radio         | 7         | 1.41%   |
| ASUSTek Computer                | 5         | 1.01%   |
| Realtek                         | 3         | 0.6%    |
| Alps Electric                   | 3         | 0.6%    |
| Chicony Electronics             | 2         | 0.4%    |
| USI                             | 1         | 0.2%    |
| Ralink Technology               | 1         | 0.2%    |
| Ralink                          | 1         | 0.2%    |
| Qcom                            | 1         | 0.2%    |
| Fujitsu                         | 1         | 0.2%    |
| Foxconn International           | 1         | 0.2%    |
| Edimax Technology               | 1         | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 82        | 16.53%  |
| Realtek Bluetooth Radio                             | 51        | 10.28%  |
| Realtek  Bluetooth 4.2 Adapter                      | 24        | 4.84%   |
| Qualcomm Atheros  Bluetooth Device                  | 18        | 3.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 17        | 3.43%   |
| Intel Bluetooth Device                              | 16        | 3.23%   |
| Intel AX201 Bluetooth                               | 15        | 3.02%   |
| Intel AX200 Bluetooth                               | 15        | 3.02%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 14        | 2.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 13        | 2.62%   |
| IMC Networks Bluetooth Radio                        | 11        | 2.22%   |
| Foxconn / Hon Hai Bluetooth Device                  | 11        | 2.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 2.02%   |
| IMC Networks Wireless_Device                        | 8         | 1.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 1.41%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 1.41%   |
| Dell DW375 Bluetooth Module                         | 7         | 1.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7         | 1.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 1.41%   |
| Apple Bluetooth Host Controller                     | 7         | 1.41%   |
| Foxconn / Hon Hai Wireless_Device                   | 6         | 1.21%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 6         | 1.21%   |
| Broadcom BCM2045B (BDC-2.1)                         | 6         | 1.21%   |
| Realtek RTL8723B Bluetooth                          | 5         | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 1.01%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 1.01%   |
| Intel AX210 Bluetooth                               | 5         | 1.01%   |
| Toshiba Integrated Bluetooth HCI                    | 4         | 0.81%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.81%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 0.81%   |
| Lite-On Bluetooth Device                            | 4         | 0.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 0.81%   |
| IMC Networks Bluetooth Device                       | 4         | 0.81%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.81%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 4         | 0.81%   |
| Toshiba Bluetooth Device                            | 3         | 0.6%    |
| Realtek Bluetooth Radio                             | 3         | 0.6%    |
| Lite-On Wireless_Device                             | 3         | 0.6%    |
| Lite-On Bluetooth Radio                             | 3         | 0.6%    |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 472       | 63.96%  |
| AMD                                          | 177       | 23.98%  |
| Nvidia                                       | 77        | 10.43%  |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.27%   |
| PreSonus Audio Electronics                   | 2         | 0.27%   |
| Generalplus Technology                       | 2         | 0.27%   |
| C-Media Electronics                          | 2         | 0.27%   |
| Logitech                                     | 1         | 0.14%   |
| Hewlett-Packard                              | 1         | 0.14%   |
| GN Netcom                                    | 1         | 0.14%   |
| ASUSTek Computer                             | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 99        | 10.22%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 80        | 8.26%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 50        | 5.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 44        | 4.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 40        | 4.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 34        | 3.51%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 32        | 3.3%    |
| Intel 8 Series HD Audio Controller                                                                | 32        | 3.3%    |
| AMD FCH Azalia Controller                                                                         | 30        | 3.1%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 28        | 2.89%   |
| Intel Broadwell-U Audio Controller                                                                | 28        | 2.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 28        | 2.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 27        | 2.79%   |
| AMD Kabini HDMI/DP Audio                                                                          | 23        | 2.37%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 22        | 2.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 22        | 2.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 20        | 2.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 20        | 2.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 20        | 2.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 17        | 1.75%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 16        | 1.65%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 14        | 1.44%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 14        | 1.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 13        | 1.34%   |
| AMD Wrestler HDMI Audio                                                                           | 13        | 1.34%   |
| AMD Radeon High Definition Audio Controller                                                       | 13        | 1.34%   |
| AMD High Definition Audio Controller                                                              | 13        | 1.34%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 12        | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 11        | 1.14%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 9         | 0.93%   |
| Nvidia High Definition Audio Controller                                                           | 8         | 0.83%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 0.62%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 0.52%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 0.52%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 5         | 0.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 0.52%   |
| Intel Meteor Lake-P HD Audio Controller                                                           | 5         | 0.52%   |
| Intel Jasper Lake HD Audio                                                                        | 5         | 0.52%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 198       | 25.45%  |
| SK hynix                     | 170       | 21.85%  |
| Micron Technology            | 93        | 11.95%  |
| Kingston                     | 81        | 10.41%  |
| Unknown                      | 57        | 7.33%   |
| Crucial                      | 31        | 3.98%   |
| Ramaxel Technology           | 22        | 2.83%   |
| Elpida                       | 20        | 2.57%   |
| A-DATA Technology            | 18        | 2.31%   |
| Unknown                      | 16        | 2.06%   |
| Nanya Technology             | 11        | 1.41%   |
| Smart                        | 6         | 0.77%   |
| Unknown (ABCD)               | 5         | 0.64%   |
| Corsair                      | 5         | 0.64%   |
| Transcend                    | 3         | 0.39%   |
| Timetec                      | 3         | 0.39%   |
| Team                         | 3         | 0.39%   |
| G.Skill                      | 3         | 0.39%   |
| Unknown (0x2C0C)             | 2         | 0.26%   |
| Smart Brazil                 | 2         | 0.26%   |
| Qimonda                      | 2         | 0.26%   |
| GOODRAM                      | 2         | 0.26%   |
| ASint Technology             | 2         | 0.26%   |
| AMD                          | 2         | 0.26%   |
| Wodposit                     | 1         | 0.13%   |
| Unknown (0x5846)             | 1         | 0.13%   |
| Unknown (0x260C)             | 1         | 0.13%   |
| Unknown (0x0E9D)             | 1         | 0.13%   |
| Unknown (0x0B5E)             | 1         | 0.13%   |
| Toshiba                      | 1         | 0.13%   |
| Teikon                       | 1         | 0.13%   |
| Standard                     | 1         | 0.13%   |
| Smart Modular                | 1         | 0.13%   |
| PNY                          | 1         | 0.13%   |
| Patriot Memory (PDP Systems) | 1         | 0.13%   |
| Patriot                      | 1         | 0.13%   |
| Neo Forza                    | 1         | 0.13%   |
| Lexar Co Limited             | 1         | 0.13%   |
| Kingmax                      | 1         | 0.13%   |
| CXMT                         | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 2.01%   |
| Unknown                                                          | 16        | 1.89%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 15        | 1.77%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 11        | 1.3%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 1.3%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 10        | 1.18%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 1.18%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.18%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 1.06%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 1.06%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.94%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 7         | 0.83%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 6         | 0.71%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 6         | 0.71%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 6         | 0.71%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 6         | 0.71%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 6         | 0.71%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 5         | 0.59%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.59%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.59%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 5         | 0.59%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 5         | 0.59%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.59%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 5         | 0.59%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 5         | 0.59%   |
| Micron RAM MT40A1G16TB-062E:F 8GB Row Of Chips DDR4 3200MT/s     | 5         | 0.59%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.59%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 5         | 0.59%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 5         | 0.59%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 4         | 0.47%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.47%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 4         | 0.47%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.47%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 4         | 0.47%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 4         | 0.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 311       | 48.07%  |
| DDR4    | 201       | 31.07%  |
| DDR2    | 52        | 8.04%   |
| SDRAM   | 22        | 3.4%    |
| LPDDR5  | 21        | 3.25%   |
| LPDDR4  | 17        | 2.63%   |
| DDR5    | 12        | 1.85%   |
| LPDDR3  | 5         | 0.77%   |
| Unknown | 4         | 0.62%   |
| DRAM    | 1         | 0.15%   |
| DDR     | 1         | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 586       | 91.28%  |
| Row Of Chips | 45        | 7.01%   |
| Unknown      | 6         | 0.93%   |
| DIMM         | 3         | 0.47%   |
| Chip         | 2         | 0.31%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 278       | 37.82%  |
| 8192  | 244       | 33.2%   |
| 2048  | 121       | 16.46%  |
| 16384 | 55        | 7.48%   |
| 1024  | 25        | 3.4%    |
| 32768 | 9         | 1.22%   |
| 512   | 3         | 0.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 230       | 32.03%  |
| 3200    | 104       | 14.48%  |
| 2667    | 78        | 10.86%  |
| 2400    | 46        | 6.41%   |
| 1334    | 38        | 5.29%   |
| 1333    | 34        | 4.74%   |
| 667     | 32        | 4.46%   |
| 1067    | 18        | 2.51%   |
| 800     | 17        | 2.37%   |
| 6400    | 14        | 1.95%   |
| 4199    | 13        | 1.81%   |
| Unknown | 10        | 1.39%   |
| 5600    | 9         | 1.25%   |
| 3266    | 9         | 1.25%   |
| 2133    | 8         | 1.11%   |
| 2048    | 8         | 1.11%   |
| 1867    | 6         | 0.84%   |
| 1066    | 6         | 0.84%   |
| 975     | 6         | 0.84%   |
| 533     | 6         | 0.84%   |
| 4266    | 4         | 0.56%   |
| 8400    | 3         | 0.42%   |
| 4800    | 3         | 0.42%   |
| 4267    | 3         | 0.42%   |
| 8533    | 2         | 0.28%   |
| 7500    | 2         | 0.28%   |
| 5500    | 2         | 0.28%   |
| 7467    | 1         | 0.14%   |
| 2933    | 1         | 0.14%   |
| 1866    | 1         | 0.14%   |
| 1639    | 1         | 0.14%   |
| 1200    | 1         | 0.14%   |
| 333     | 1         | 0.14%   |
| 266     | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Notebooks | Percent |
|---------------------|-----------|---------|
| HP LaserJet 1000    | 1         | 50%     |
| Canon TS3400 series | 1         | 50%     |

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
| Chicony Electronics                    | 157       | 28.29%  |
| IMC Networks                           | 55        | 9.91%   |
| Sunplus Innovation Technology          | 45        | 8.11%   |
| Realtek Semiconductor                  | 40        | 7.21%   |
| Bison Electronics                      | 35        | 6.31%   |
| Quanta                                 | 34        | 6.13%   |
| Microdia                               | 34        | 6.13%   |
| Suyin                                  | 24        | 4.32%   |
| Luxvisions Innotech Limited            | 18        | 3.24%   |
| Cheng Uei Precision Industry (Foxlink) | 17        | 3.06%   |
| Syntek                                 | 9         | 1.62%   |
| Silicon Motion                         | 9         | 1.62%   |
| Apple                                  | 9         | 1.62%   |
| Alcor Micro                            | 8         | 1.44%   |
| Acer                                   | 7         | 1.26%   |
| Ricoh                                  | 6         | 1.08%   |
| Lite-On Technology                     | 6         | 1.08%   |
| ShineTech                              | 5         | 0.9%    |
| Lenovo                                 | 5         | 0.9%    |
| OmniVision Technologies                | 3         | 0.54%   |
| Importek                               | 3         | 0.54%   |
| Unknown                                | 3         | 0.54%   |
| Z-Star Microelectronics                | 2         | 0.36%   |
| SunplusIT                              | 2         | 0.36%   |
| Sonix Technology                       | 2         | 0.36%   |
| Shine-optics                           | 2         | 0.36%   |
| Genesys Logic                          | 2         | 0.36%   |
| Y Media                                | 1         | 0.18%   |
| Sunplus Technology                     | 1         | 0.18%   |
| Primax Electronics                     | 1         | 0.18%   |
| OYT Tech                               | 1         | 0.18%   |
| Logitech                               | 1         | 0.18%   |
| KYT-240222-A                           | 1         | 0.18%   |
| icSpring                               | 1         | 0.18%   |
| Hangzhou Riyue Electronic              | 1         | 0.18%   |
| Goodong                                | 1         | 0.18%   |
| Generalplus Technology                 | 1         | 0.18%   |
| Foxconn / Hon Hai                      | 1         | 0.18%   |
| DigiTech                               | 1         | 0.18%   |
| ALi                                    | 1         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 26        | 4.68%   |
| IMC Networks Integrated Camera                                 | 16        | 2.88%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 15        | 2.7%    |
| Chicony HD WebCam                                              | 13        | 2.34%   |
| Microdia Integrated_Webcam_HD                                  | 9         | 1.62%   |
| Sunplus HD WebCam                                              | 8         | 1.44%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 8         | 1.44%   |
| Chicony TOSHIBA Web Camera - HD                                | 8         | 1.44%   |
| Chicony HP TrueVision HD Camera                                | 8         | 1.44%   |
| Sunplus Integrated_Webcam_HD                                   | 7         | 1.26%   |
| Realtek Integrated_Webcam_HD                                   | 7         | 1.26%   |
| IMC Networks UVC VGA Webcam                                    | 7         | 1.26%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 7         | 1.26%   |
| Chicony FJ Camera                                              | 7         | 1.26%   |
| Bison Lenovo EasyCamera                                        | 7         | 1.26%   |
| Sunplus Laptop Integrated Webcam HD                            | 6         | 1.08%   |
| Realtek USB Camera                                             | 6         | 1.08%   |
| Quanta HP TrueVision HD Camera                                 | 6         | 1.08%   |
| Microdia Integrated Webcam                                     | 6         | 1.08%   |
| Syntek Integrated Camera                                       | 5         | 0.9%    |
| Quanta HP Wide Vision HD Camera                                | 5         | 0.9%    |
| Quanta HP Webcam                                               | 5         | 0.9%    |
| IMC Networks Integrated Webcam                                 | 5         | 0.9%    |
| Chicony VGA WebCam                                             | 5         | 0.9%    |
| Chicony USB2.0 HD UVC WebCam                                   | 5         | 0.9%    |
| Bison Integrated Camera                                        | 5         | 0.9%    |
| Apple Built-in iSight                                          | 5         | 0.9%    |
| Acer Integrated Camera                                         | 5         | 0.9%    |
| Silicon Motion WebCam SC-0311139N                              | 4         | 0.72%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 4         | 0.72%   |
| Chicony HP Webcam                                              | 4         | 0.72%   |
| Chicony HP TrueVision HD                                       | 4         | 0.72%   |
| Chicony HD User Facing                                         | 4         | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 4         | 0.72%   |
| Suyin Laptop_Integrated_Webcam_HD                              | 3         | 0.54%   |
| Suyin 1.3M HD WebCam                                           | 3         | 0.54%   |
| Sunplus Laptop_Integrated_Webcam_HD                            | 3         | 0.54%   |
| Sunplus Integrated Camera                                      | 3         | 0.54%   |
| Sunplus Asus Webcam                                            | 3         | 0.54%   |
| Shinetech USB2.0 FHD UVC WebCam                                | 3         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 27        | 36%     |
| AuthenTec                          | 16        | 21.33%  |
| Synaptics                          | 13        | 17.33%  |
| Elan Microelectronics              | 6         | 8%      |
| Upek                               | 5         | 6.67%   |
| Shenzhen Goodix Technology         | 5         | 6.67%   |
| STMicroelectronics                 | 1         | 1.33%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.33%   |
| Focal-systems.Corp                 | 1         | 1.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 9.33%   |
| Elan ELAN:ARM-M4                                                           | 6         | 8%      |
| AuthenTec AES2810                                                          | 6         | 8%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 6.67%   |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 6.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 5.33%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 5.33%   |
| Validity Sensors VFS491                                                    | 4         | 5.33%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 5.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 4%      |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 4%      |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 4%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 2.67%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 2.67%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 2.67%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2.67%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.67%   |
| AuthenTec AES1600                                                          | 2         | 2.67%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.33%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.33%   |
| Synaptics TouchPad                                                         | 1         | 1.33%   |
| Synaptics Prometheus Fingerprint Reader                                    | 1         | 1.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.33%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.33%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 1.33%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 1.33%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 21        | 48.84%  |
| Alcor Micro | 10        | 23.26%  |
| Lenovo      | 5         | 11.63%  |
| O2 Micro    | 4         | 9.3%    |
| Upek        | 3         | 6.98%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 30.23%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 23.26%  |
| Lenovo Integrated Smart Card Reader                                          | 5         | 11.63%  |
| Broadcom 5880                                                                | 5         | 11.63%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 9.3%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 6.98%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 6.98%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 463       | 71.89%  |
| 1     | 155       | 24.07%  |
| 2     | 25        | 3.88%   |
| 3     | 1         | 0.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 75        | 36.95%  |
| Graphics card            | 63        | 31.03%  |
| Chipcard                 | 41        | 20.2%   |
| Net/wireless             | 10        | 4.93%   |
| Storage                  | 5         | 2.46%   |
| Multimedia controller    | 2         | 0.99%   |
| Communication controller | 2         | 0.99%   |
| Tv card                  | 1         | 0.49%   |
| Modem                    | 1         | 0.49%   |
| Card reader              | 1         | 0.49%   |
| Camera                   | 1         | 0.49%   |
| Bluetooth                | 1         | 0.49%   |

