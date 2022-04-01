Zorin 16 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 1072

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion dv6000 (GA443UA... | [b9a90b57c8](https://linux-hardware.org/?probe=b9a90b57c8) | Apr 01, 2022 |
| ASUSTek       | K55A                        | [71137b6a1e](https://linux-hardware.org/?probe=71137b6a1e) | Apr 01, 2022 |
| ASUSTek       | X102BA                      | [78ecf202d2](https://linux-hardware.org/?probe=78ecf202d2) | Apr 01, 2022 |
| Acer          | Nitro AN515-51              | [61a7788bfa](https://linux-hardware.org/?probe=61a7788bfa) | Mar 31, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d13496f68a](https://linux-hardware.org/?probe=d13496f68a) | Mar 31, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [19aa2cf50d](https://linux-hardware.org/?probe=19aa2cf50d) | Mar 31, 2022 |
| Dell          | Venue 8 Pro 5855            | [35a463a0fb](https://linux-hardware.org/?probe=35a463a0fb) | Mar 31, 2022 |
| Toshiba       | Satellite C660              | [60a6bafd86](https://linux-hardware.org/?probe=60a6bafd86) | Mar 30, 2022 |
| Acer          | Aspire ES1-572              | [bf6df72edf](https://linux-hardware.org/?probe=bf6df72edf) | Mar 29, 2022 |
| Notebook      | NJ50_70CU                   | [ba5b62756b](https://linux-hardware.org/?probe=ba5b62756b) | Mar 29, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [a6218b029c](https://linux-hardware.org/?probe=a6218b029c) | Mar 29, 2022 |
| HP            | Pavilion dv3                | [bd8d09108e](https://linux-hardware.org/?probe=bd8d09108e) | Mar 28, 2022 |
| Acer          | Nitro AN515-44              | [36681f4a2f](https://linux-hardware.org/?probe=36681f4a2f) | Mar 28, 2022 |
| ASUSTek       | T100TA                      | [fa6858ef16](https://linux-hardware.org/?probe=fa6858ef16) | Mar 28, 2022 |
| Dell          | Precision M4800             | [1eacfc1ab5](https://linux-hardware.org/?probe=1eacfc1ab5) | Mar 27, 2022 |
| Acer          | V5-171                      | [e1a668bda2](https://linux-hardware.org/?probe=e1a668bda2) | Mar 27, 2022 |
| ASUSTek       | T100TA                      | [667b0cb23e](https://linux-hardware.org/?probe=667b0cb23e) | Mar 27, 2022 |
| Acer          | Predator G9-792             | [4720698441](https://linux-hardware.org/?probe=4720698441) | Mar 27, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [09cccd4869](https://linux-hardware.org/?probe=09cccd4869) | Mar 27, 2022 |
| Dell          | Precision M4800             | [90a4438dfa](https://linux-hardware.org/?probe=90a4438dfa) | Mar 26, 2022 |
| Dell          | Inspiron M5030              | [7bc7e689a4](https://linux-hardware.org/?probe=7bc7e689a4) | Mar 26, 2022 |
| Insyde        | GeminiLake                  | [44967ed898](https://linux-hardware.org/?probe=44967ed898) | Mar 26, 2022 |
| HP            | ProBook 4530s               | [f4d3c7fddf](https://linux-hardware.org/?probe=f4d3c7fddf) | Mar 25, 2022 |
| Acer          | Aspire V3-571               | [3d2d313cc3](https://linux-hardware.org/?probe=3d2d313cc3) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | [09576b4897](https://linux-hardware.org/?probe=09576b4897) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | [610b3ad535](https://linux-hardware.org/?probe=610b3ad535) | Mar 25, 2022 |
| Dell          | Latitude E5540              | [c743515039](https://linux-hardware.org/?probe=c743515039) | Mar 25, 2022 |
| Dell          | Latitude E5540              | [0059ee485d](https://linux-hardware.org/?probe=0059ee485d) | Mar 25, 2022 |
| Toshiba       | Satellite S55t-C            | [0bebc02627](https://linux-hardware.org/?probe=0bebc02627) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | [5eac01f806](https://linux-hardware.org/?probe=5eac01f806) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | [ce0fa4ee36](https://linux-hardware.org/?probe=ce0fa4ee36) | Mar 25, 2022 |
| Lenovo        | ThinkPad SL500 274677G      | [1fcd4e44f1](https://linux-hardware.org/?probe=1fcd4e44f1) | Mar 25, 2022 |
| HP            | Laptop 15-bw0xx             | [eb140d5b4d](https://linux-hardware.org/?probe=eb140d5b4d) | Mar 25, 2022 |
| Sony          | SVT13125CLS                 | [5332da89c8](https://linux-hardware.org/?probe=5332da89c8) | Mar 25, 2022 |
| Gateway       | NV59C                       | [f00a460bfa](https://linux-hardware.org/?probe=f00a460bfa) | Mar 24, 2022 |
| Acer          | Nitro AN515-44              | [4e75dbe2d2](https://linux-hardware.org/?probe=4e75dbe2d2) | Mar 23, 2022 |
| Positivo      | C14CU51                     | [1ca3c10e9b](https://linux-hardware.org/?probe=1ca3c10e9b) | Mar 23, 2022 |
| ASUSTek       | X405UA                      | [1895364071](https://linux-hardware.org/?probe=1895364071) | Mar 22, 2022 |
| Apple         | MacBookPro12,1              | [a39345cbf9](https://linux-hardware.org/?probe=a39345cbf9) | Mar 22, 2022 |
| Gateway       | NV59C                       | [ce722c3cc0](https://linux-hardware.org/?probe=ce722c3cc0) | Mar 22, 2022 |
| MSI           | CR643                       | [24e9c1fe40](https://linux-hardware.org/?probe=24e9c1fe40) | Mar 22, 2022 |
| ASUSTek       | G75VW                       | [202d109eb5](https://linux-hardware.org/?probe=202d109eb5) | Mar 22, 2022 |
| HP            | EliteBook 8540p             | [15a215fc17](https://linux-hardware.org/?probe=15a215fc17) | Mar 22, 2022 |
| HP            | EliteBook 8540p             | [f0915a2702](https://linux-hardware.org/?probe=f0915a2702) | Mar 22, 2022 |
| HP            | Laptop 15-db0xxx            | [e0f906e560](https://linux-hardware.org/?probe=e0f906e560) | Mar 21, 2022 |
| HP            | Pavilion g6                 | [141b22c372](https://linux-hardware.org/?probe=141b22c372) | Mar 20, 2022 |
| HP            | ENVY dv7                    | [b15a265c66](https://linux-hardware.org/?probe=b15a265c66) | Mar 20, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a3859ab679](https://linux-hardware.org/?probe=a3859ab679) | Mar 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [9323d5d425](https://linux-hardware.org/?probe=9323d5d425) | Mar 19, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a2f09086d6](https://linux-hardware.org/?probe=a2f09086d6) | Mar 19, 2022 |
| HP            | Pavilion Notebook           | [02e461a122](https://linux-hardware.org/?probe=02e461a122) | Mar 19, 2022 |
| HP            | Pavilion dv3                | [3dbd970796](https://linux-hardware.org/?probe=3dbd970796) | Mar 19, 2022 |
| Apple         | MacBookPro10,1              | [6da9c9f35d](https://linux-hardware.org/?probe=6da9c9f35d) | Mar 19, 2022 |
| Dell          | Inspiron 5770               | [77492abdcf](https://linux-hardware.org/?probe=77492abdcf) | Mar 19, 2022 |
| Lenovo        | ThinkPad T520 424067G       | [3e6c1f772d](https://linux-hardware.org/?probe=3e6c1f772d) | Mar 18, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [3603330b59](https://linux-hardware.org/?probe=3603330b59) | Mar 18, 2022 |
| ASUSTek       | ZenBook UX433FN_U4300FN     | [0228881558](https://linux-hardware.org/?probe=0228881558) | Mar 18, 2022 |
| Dell          | Vostro 1500                 | [b2d732d46b](https://linux-hardware.org/?probe=b2d732d46b) | Mar 18, 2022 |
| Dell          | Vostro 1500                 | [6dbcdd388c](https://linux-hardware.org/?probe=6dbcdd388c) | Mar 18, 2022 |
| Dell          | Inspiron 7737               | [99852ed093](https://linux-hardware.org/?probe=99852ed093) | Mar 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [c3ffdf7791](https://linux-hardware.org/?probe=c3ffdf7791) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [77b0be92c8](https://linux-hardware.org/?probe=77b0be92c8) | Mar 17, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [47a984d336](https://linux-hardware.org/?probe=47a984d336) | Mar 17, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [662aed3d5d](https://linux-hardware.org/?probe=662aed3d5d) | Mar 17, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [b3fc1a1d0f](https://linux-hardware.org/?probe=b3fc1a1d0f) | Mar 17, 2022 |
| Dell          | Latitude E4200              | [7342f497b4](https://linux-hardware.org/?probe=7342f497b4) | Mar 16, 2022 |
| HP            | ProBook 450 G2              | [177d9b8820](https://linux-hardware.org/?probe=177d9b8820) | Mar 16, 2022 |
| Toshiba       | Satellite C855              | [71d2d562d7](https://linux-hardware.org/?probe=71d2d562d7) | Mar 16, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [9aa148dba8](https://linux-hardware.org/?probe=9aa148dba8) | Mar 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [116bb6c003](https://linux-hardware.org/?probe=116bb6c003) | Mar 15, 2022 |
| Sony          | VGN-FW21E                   | [1dbc74cf43](https://linux-hardware.org/?probe=1dbc74cf43) | Mar 15, 2022 |
| Insyde        | i101c                       | [1d1171c005](https://linux-hardware.org/?probe=1d1171c005) | Mar 15, 2022 |
| Gigabyte      | P64V7                       | [13f2e44186](https://linux-hardware.org/?probe=13f2e44186) | Mar 15, 2022 |
| Toshiba       | Satellite C55-C             | [8fade33706](https://linux-hardware.org/?probe=8fade33706) | Mar 15, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [0755c3c4a6](https://linux-hardware.org/?probe=0755c3c4a6) | Mar 14, 2022 |
| Acer          | Aspire E5-571P              | [dd68b81b43](https://linux-hardware.org/?probe=dd68b81b43) | Mar 14, 2022 |
| Acer          | Aspire SW3-016              | [6988255f00](https://linux-hardware.org/?probe=6988255f00) | Mar 14, 2022 |
| Lenovo        | IdeaPad Z580                | [b5a56fb84b](https://linux-hardware.org/?probe=b5a56fb84b) | Mar 14, 2022 |
| Lenovo        | IdeaPad Z580                | [80590bb756](https://linux-hardware.org/?probe=80590bb756) | Mar 14, 2022 |
| ASUSTek       | X550LC                      | [cb90a1c509](https://linux-hardware.org/?probe=cb90a1c509) | Mar 13, 2022 |
| Lenovo        | IdeaPad 320S-15IKB 81BQ     | [088d2bf23b](https://linux-hardware.org/?probe=088d2bf23b) | Mar 13, 2022 |
| HP            | Notebook                    | [2a7e60663b](https://linux-hardware.org/?probe=2a7e60663b) | Mar 13, 2022 |
| Toshiba       | Satellite C50D-A-14E        | [256e08de3d](https://linux-hardware.org/?probe=256e08de3d) | Mar 13, 2022 |
| HP            | Laptop 14-ck0xxx            | [92c7141f37](https://linux-hardware.org/?probe=92c7141f37) | Mar 12, 2022 |
| HP            | 1000                        | [c43fd3bfa5](https://linux-hardware.org/?probe=c43fd3bfa5) | Mar 11, 2022 |
| Lenovo        | V110-15IAP 80TG             | [5989c71041](https://linux-hardware.org/?probe=5989c71041) | Mar 11, 2022 |
| Sony          | VGN-FW21E                   | [93205c5e40](https://linux-hardware.org/?probe=93205c5e40) | Mar 11, 2022 |
| ASUSTek       | Vivobook_ASUSLaptop M350... | [14237b32d9](https://linux-hardware.org/?probe=14237b32d9) | Mar 11, 2022 |
| Dell          | Inspiron 5520               | [5d8f77310a](https://linux-hardware.org/?probe=5d8f77310a) | Mar 11, 2022 |
| ASUSTek       | GL552VW                     | [5e7b7a63a9](https://linux-hardware.org/?probe=5e7b7a63a9) | Mar 10, 2022 |
| Chuwi         | HeroBook Air                | [674a4fbede](https://linux-hardware.org/?probe=674a4fbede) | Mar 10, 2022 |
| HP            | 15 Notebook PC              | [8714d12640](https://linux-hardware.org/?probe=8714d12640) | Mar 09, 2022 |
| HP            | Laptop 14-dq2xxx            | [cb5d9880c6](https://linux-hardware.org/?probe=cb5d9880c6) | Mar 09, 2022 |
| Packard Be... | EasyNote LS11HR             | [7a99940861](https://linux-hardware.org/?probe=7a99940861) | Mar 08, 2022 |
| Dell          | Inspiron 13-7378            | [6c40e8cf0f](https://linux-hardware.org/?probe=6c40e8cf0f) | Mar 08, 2022 |
| Dell          | Vostro 3550                 | [25951f4351](https://linux-hardware.org/?probe=25951f4351) | Mar 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8a4f961472](https://linux-hardware.org/?probe=8a4f961472) | Mar 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4d33fc28da](https://linux-hardware.org/?probe=4d33fc28da) | Mar 08, 2022 |
| Toshiba       | Satellite L875              | [ad99a6a57b](https://linux-hardware.org/?probe=ad99a6a57b) | Mar 07, 2022 |
| Acer          | TP-W700-53334G12            | [61d5d1483d](https://linux-hardware.org/?probe=61d5d1483d) | Mar 07, 2022 |
| HP            | ProBook 640 G1              | [bf9c067da8](https://linux-hardware.org/?probe=bf9c067da8) | Mar 07, 2022 |
| Toshiba       | Satellite L875              | [a5487c84f8](https://linux-hardware.org/?probe=a5487c84f8) | Mar 07, 2022 |
| HP            | Notebook                    | [a15666c682](https://linux-hardware.org/?probe=a15666c682) | Mar 07, 2022 |
| HP            | Notebook                    | [85eb96edd4](https://linux-hardware.org/?probe=85eb96edd4) | Mar 07, 2022 |
| ASUSTek       | X550LC                      | [8c4294a84e](https://linux-hardware.org/?probe=8c4294a84e) | Mar 06, 2022 |
| ASUSTek       | X550LC                      | [97f4cf8c40](https://linux-hardware.org/?probe=97f4cf8c40) | Mar 06, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [6e8e3f12d0](https://linux-hardware.org/?probe=6e8e3f12d0) | Mar 06, 2022 |
| AXDIA Inte... | WINBOOK 13                  | [6cf2cc07ed](https://linux-hardware.org/?probe=6cf2cc07ed) | Mar 06, 2022 |
| Toshiba       | Satellite C855              | [6911de7c71](https://linux-hardware.org/?probe=6911de7c71) | Mar 05, 2022 |
| Acer          | TP-W700-53334G12            | [cf6bad7b5c](https://linux-hardware.org/?probe=cf6bad7b5c) | Mar 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [14fc889e5f](https://linux-hardware.org/?probe=14fc889e5f) | Mar 05, 2022 |
| ASUSTek       | X405UA                      | [1e2f63c24b](https://linux-hardware.org/?probe=1e2f63c24b) | Mar 05, 2022 |
| Dell          | Precision M6700             | [c5cb8cd111](https://linux-hardware.org/?probe=c5cb8cd111) | Mar 05, 2022 |
| Dell          | Latitude E5500              | [0f590ac9e5](https://linux-hardware.org/?probe=0f590ac9e5) | Mar 05, 2022 |
| Toshiba       | Satellite A660              | [1a6607437d](https://linux-hardware.org/?probe=1a6607437d) | Mar 04, 2022 |
| Toshiba       | Satellite A660              | [584c89737c](https://linux-hardware.org/?probe=584c89737c) | Mar 04, 2022 |
| HP            | ProBook 4720s               | [631600dd74](https://linux-hardware.org/?probe=631600dd74) | Mar 04, 2022 |
| ASUSTek       | T100TA                      | [6dc5f272b6](https://linux-hardware.org/?probe=6dc5f272b6) | Mar 04, 2022 |
| ASUSTek       | T100TA                      | [485c2b3aa7](https://linux-hardware.org/?probe=485c2b3aa7) | Mar 04, 2022 |
| HP            | Pavilion dv7                | [db550138fb](https://linux-hardware.org/?probe=db550138fb) | Mar 03, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [d09a669d80](https://linux-hardware.org/?probe=d09a669d80) | Mar 03, 2022 |
| Acer          | V5-171                      | [8c620eae72](https://linux-hardware.org/?probe=8c620eae72) | Mar 03, 2022 |
| Lenovo        | G560 0679                   | [07bbbdef41](https://linux-hardware.org/?probe=07bbbdef41) | Mar 03, 2022 |
| HP            | ProBook 4720s               | [8afd2b3c97](https://linux-hardware.org/?probe=8afd2b3c97) | Mar 03, 2022 |
| HP            | ProBook 640 G1              | [6acfc75347](https://linux-hardware.org/?probe=6acfc75347) | Mar 03, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82C5     | [d4b6e7276e](https://linux-hardware.org/?probe=d4b6e7276e) | Mar 03, 2022 |
| Lenovo        | HuronRiver Platform         | [a34efebccf](https://linux-hardware.org/?probe=a34efebccf) | Mar 02, 2022 |
| HP            | Compaq 6730b (NN204ET#AB... | [0a30782289](https://linux-hardware.org/?probe=0a30782289) | Mar 02, 2022 |
| HP            | Compaq 6730b (NN204ET#AB... | [f20f8759b1](https://linux-hardware.org/?probe=f20f8759b1) | Mar 02, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [fb9f8e44d0](https://linux-hardware.org/?probe=fb9f8e44d0) | Mar 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [46271114d7](https://linux-hardware.org/?probe=46271114d7) | Mar 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [1df5245912](https://linux-hardware.org/?probe=1df5245912) | Mar 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [bd438d0f08](https://linux-hardware.org/?probe=bd438d0f08) | Mar 01, 2022 |
| Dell          | Latitude 3550               | [5b0d9e3d13](https://linux-hardware.org/?probe=5b0d9e3d13) | Feb 28, 2022 |
| Dell          | Precision M4800             | [546f292b66](https://linux-hardware.org/?probe=546f292b66) | Feb 27, 2022 |
| Dell          | G5 5590                     | [f553433011](https://linux-hardware.org/?probe=f553433011) | Feb 27, 2022 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [f67c401f47](https://linux-hardware.org/?probe=f67c401f47) | Feb 27, 2022 |
| Acer          | Swift SF114-34              | [49fb58c88b](https://linux-hardware.org/?probe=49fb58c88b) | Feb 27, 2022 |
| Dell          | Latitude E5500              | [c84caad5a2](https://linux-hardware.org/?probe=c84caad5a2) | Feb 26, 2022 |
| Dell          | Latitude E5500              | [38a51b4721](https://linux-hardware.org/?probe=38a51b4721) | Feb 26, 2022 |
| HP            | 630                         | [6bf505d86b](https://linux-hardware.org/?probe=6bf505d86b) | Feb 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [359368d345](https://linux-hardware.org/?probe=359368d345) | Feb 26, 2022 |
| HP            | EliteBook 840 G6            | [fabf12f128](https://linux-hardware.org/?probe=fabf12f128) | Feb 26, 2022 |
| Dell          | Inspiron 5448               | [2458e07e0d](https://linux-hardware.org/?probe=2458e07e0d) | Feb 25, 2022 |
| Lenovo        | G40-80 80JE                 | [c55ba8cab2](https://linux-hardware.org/?probe=c55ba8cab2) | Feb 25, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [b1354ad7df](https://linux-hardware.org/?probe=b1354ad7df) | Feb 24, 2022 |
| Toshiba       | Satellite C55-B             | [ae66a9051d](https://linux-hardware.org/?probe=ae66a9051d) | Feb 24, 2022 |
| Packard Be... | DOT S                       | [e90543b727](https://linux-hardware.org/?probe=e90543b727) | Feb 24, 2022 |
| Fujitsu       | LIFEBOOK AH512              | [d7889a52d1](https://linux-hardware.org/?probe=d7889a52d1) | Feb 24, 2022 |
| HP            | Stream Laptop 11-ah0XX      | [e224468100](https://linux-hardware.org/?probe=e224468100) | Feb 23, 2022 |
| HP            | Pavilion g6                 | [1c1f4685eb](https://linux-hardware.org/?probe=1c1f4685eb) | Feb 22, 2022 |
| Dell          | XPS 15 9510                 | [6c5203e00a](https://linux-hardware.org/?probe=6c5203e00a) | Feb 22, 2022 |
| Acer          | V5-171                      | [2ef877834d](https://linux-hardware.org/?probe=2ef877834d) | Feb 22, 2022 |
| Gigabyte      | P64V7                       | [fdac76c228](https://linux-hardware.org/?probe=fdac76c228) | Feb 22, 2022 |
| Toshiba       | Satellite S55t-C            | [45b90ca745](https://linux-hardware.org/?probe=45b90ca745) | Feb 21, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [85c2284ffa](https://linux-hardware.org/?probe=85c2284ffa) | Feb 21, 2022 |
| Multilaser    | PC130                       | [4a49294d21](https://linux-hardware.org/?probe=4a49294d21) | Feb 20, 2022 |
| Multilaser    | PC130                       | [4681b7ae9e](https://linux-hardware.org/?probe=4681b7ae9e) | Feb 20, 2022 |
| Dell          | Studio 1555                 | [19d02a6eb8](https://linux-hardware.org/?probe=19d02a6eb8) | Feb 20, 2022 |
| Dell          | Precision M4800             | [9734390386](https://linux-hardware.org/?probe=9734390386) | Feb 19, 2022 |
| GEO           | GeoBook 120                 | [3eeed29e23](https://linux-hardware.org/?probe=3eeed29e23) | Feb 19, 2022 |
| GEO           | GeoBook 120                 | [5c26a23921](https://linux-hardware.org/?probe=5c26a23921) | Feb 19, 2022 |
| Google        | Akemi                       | [fc9b479395](https://linux-hardware.org/?probe=fc9b479395) | Feb 19, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4425c178f2](https://linux-hardware.org/?probe=4425c178f2) | Feb 19, 2022 |
| Lenovo        | Yoga 2 Pro 20266            | [dda75e3ba9](https://linux-hardware.org/?probe=dda75e3ba9) | Feb 19, 2022 |
| Lenovo        | ThinkPad T61 7658CTO        | [99465a8eb3](https://linux-hardware.org/?probe=99465a8eb3) | Feb 19, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [aad26f0aa8](https://linux-hardware.org/?probe=aad26f0aa8) | Feb 19, 2022 |
| ASUSTek       | X555LAB                     | [413a122ef8](https://linux-hardware.org/?probe=413a122ef8) | Feb 19, 2022 |
| Lenovo        | ThinkPad T440 20B7008ABR    | [b690de8548](https://linux-hardware.org/?probe=b690de8548) | Feb 19, 2022 |
| Dell          | Inspiron MM061              | [bc37eeb385](https://linux-hardware.org/?probe=bc37eeb385) | Feb 19, 2022 |
| Dell          | Inspiron MM061              | [e5dd39a008](https://linux-hardware.org/?probe=e5dd39a008) | Feb 18, 2022 |
| Gigabyte      | P64V7                       | [646aa28c13](https://linux-hardware.org/?probe=646aa28c13) | Feb 18, 2022 |
| Dell          | Latitude 5179               | [b28766add3](https://linux-hardware.org/?probe=b28766add3) | Feb 18, 2022 |
| HP            | 255 G2                      | [f4f4bcc310](https://linux-hardware.org/?probe=f4f4bcc310) | Feb 17, 2022 |
| HP            | 255 G2                      | [2eee7b6928](https://linux-hardware.org/?probe=2eee7b6928) | Feb 17, 2022 |
| Acer          | Predator G9-792             | [e516ba85b9](https://linux-hardware.org/?probe=e516ba85b9) | Feb 17, 2022 |
| HP            | OMEN Notebook               | [a952f9c2f2](https://linux-hardware.org/?probe=a952f9c2f2) | Feb 17, 2022 |
| ASUSTek       | ZenBook UX334FL_UX334FL     | [89c2a0f939](https://linux-hardware.org/?probe=89c2a0f939) | Feb 17, 2022 |
| Lenovo        | ThinkPad Edge E530 32599... | [d6fafc8b8b](https://linux-hardware.org/?probe=d6fafc8b8b) | Feb 17, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [59f1a1a3e0](https://linux-hardware.org/?probe=59f1a1a3e0) | Feb 16, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [a62793c371](https://linux-hardware.org/?probe=a62793c371) | Feb 16, 2022 |
| Packard Be... | EasyNote TK85               | [9abcb12076](https://linux-hardware.org/?probe=9abcb12076) | Feb 16, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [311429d9ef](https://linux-hardware.org/?probe=311429d9ef) | Feb 16, 2022 |
| Dell          | Vostro 1700                 | [efaa6a2512](https://linux-hardware.org/?probe=efaa6a2512) | Feb 16, 2022 |
| Dell          | Vostro 1700                 | [d003670f08](https://linux-hardware.org/?probe=d003670f08) | Feb 16, 2022 |
| HP            | Pavilion dv6500             | [70b0938bc3](https://linux-hardware.org/?probe=70b0938bc3) | Feb 15, 2022 |
| HP            | Pavilion dv6500             | [918d93ea7a](https://linux-hardware.org/?probe=918d93ea7a) | Feb 15, 2022 |
| Acer          | E1-510                      | [0120aaf250](https://linux-hardware.org/?probe=0120aaf250) | Feb 15, 2022 |
| Acer          | E1-510                      | [7a3678f7d1](https://linux-hardware.org/?probe=7a3678f7d1) | Feb 15, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [8306c2af49](https://linux-hardware.org/?probe=8306c2af49) | Feb 15, 2022 |
| Dell          | Vostro 1500                 | [1780b4d18b](https://linux-hardware.org/?probe=1780b4d18b) | Feb 14, 2022 |
| Dell          | XPS 15 9510                 | [79e65b1e06](https://linux-hardware.org/?probe=79e65b1e06) | Feb 14, 2022 |
| Toshiba       | QOSMIO X70-A                | [c3c921f8e2](https://linux-hardware.org/?probe=c3c921f8e2) | Feb 14, 2022 |
| Lenovo        | ThinkPad T420 4178A47       | [cda9da09dc](https://linux-hardware.org/?probe=cda9da09dc) | Feb 14, 2022 |
| e-shop.gr     | V113                        | [e9a1ae2e96](https://linux-hardware.org/?probe=e9a1ae2e96) | Feb 14, 2022 |
| Lenovo        | ThinkPad T420 4236KU9       | [0412384bc2](https://linux-hardware.org/?probe=0412384bc2) | Feb 13, 2022 |
| HP            | Unknown                     | [2f4edd8b04](https://linux-hardware.org/?probe=2f4edd8b04) | Feb 13, 2022 |
| HP            | Unknown                     | [1284e8c58f](https://linux-hardware.org/?probe=1284e8c58f) | Feb 13, 2022 |
| Toshiba       | Satellite C50-A283          | [66f810c5f5](https://linux-hardware.org/?probe=66f810c5f5) | Feb 13, 2022 |
| e-shop.gr     | V113                        | [6d015f399b](https://linux-hardware.org/?probe=6d015f399b) | Feb 12, 2022 |
| Lenovo        | Flex 2-15 20405             | [7ae6513197](https://linux-hardware.org/?probe=7ae6513197) | Feb 12, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [bd8bfe9447](https://linux-hardware.org/?probe=bd8bfe9447) | Feb 12, 2022 |
| Sony          | VGN-Z575FN                  | [4998f7ae6d](https://linux-hardware.org/?probe=4998f7ae6d) | Feb 11, 2022 |
| HP            | ProBook 4525s               | [2db6879863](https://linux-hardware.org/?probe=2db6879863) | Feb 11, 2022 |
| HP            | ProBook 450 G5              | [804f3b74e0](https://linux-hardware.org/?probe=804f3b74e0) | Feb 10, 2022 |
| HP            | ProBook 450 G5              | [9e1c3acaf3](https://linux-hardware.org/?probe=9e1c3acaf3) | Feb 10, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [3dffdcc5d3](https://linux-hardware.org/?probe=3dffdcc5d3) | Feb 09, 2022 |
| HP            | 550                         | [7e286dd830](https://linux-hardware.org/?probe=7e286dd830) | Feb 08, 2022 |
| Samsung       | 600B4B/600B5B               | [2558403513](https://linux-hardware.org/?probe=2558403513) | Feb 08, 2022 |
| Samsung       | 600B4B/600B5B               | [f37984fec2](https://linux-hardware.org/?probe=f37984fec2) | Feb 08, 2022 |
| Apple         | MacBookPro11,1              | [8233b1191c](https://linux-hardware.org/?probe=8233b1191c) | Feb 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [7f24cf6cc9](https://linux-hardware.org/?probe=7f24cf6cc9) | Feb 07, 2022 |
| Dell          | Inspiron N5010              | [d14b339c4f](https://linux-hardware.org/?probe=d14b339c4f) | Feb 07, 2022 |
| ASUSTek       | T101HA                      | [3ec67a3424](https://linux-hardware.org/?probe=3ec67a3424) | Feb 06, 2022 |
| Dell          | Vostro 1700                 | [56ab8ae4cc](https://linux-hardware.org/?probe=56ab8ae4cc) | Feb 06, 2022 |
| Lenovo        | G40-80 80JE                 | [dd6e3f3a64](https://linux-hardware.org/?probe=dd6e3f3a64) | Feb 06, 2022 |
| HP            | 635                         | [3f689c9c23](https://linux-hardware.org/?probe=3f689c9c23) | Feb 06, 2022 |
| ASUSTek       | X405UA                      | [bf196d4470](https://linux-hardware.org/?probe=bf196d4470) | Feb 05, 2022 |
| Unknown       | Unknown                     | [7848918b1d](https://linux-hardware.org/?probe=7848918b1d) | Feb 05, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [b1106ffeae](https://linux-hardware.org/?probe=b1106ffeae) | Feb 05, 2022 |
| ASUSTek       | ROG Strix G513QR            | [f562940afa](https://linux-hardware.org/?probe=f562940afa) | Feb 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [25fa8ea018](https://linux-hardware.org/?probe=25fa8ea018) | Feb 04, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [4b20e9f979](https://linux-hardware.org/?probe=4b20e9f979) | Feb 04, 2022 |
| HP            | ProBook 445 G7              | [3f45fd6cf2](https://linux-hardware.org/?probe=3f45fd6cf2) | Feb 03, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [71b93f7b57](https://linux-hardware.org/?probe=71b93f7b57) | Feb 03, 2022 |
| Novatech      | 15.6 nSpire Laptop          | [6fe78d2f4b](https://linux-hardware.org/?probe=6fe78d2f4b) | Feb 02, 2022 |
| HP            | ProBook 4310s               | [6d2a66aa1e](https://linux-hardware.org/?probe=6d2a66aa1e) | Feb 02, 2022 |
| Lenovo        | G710 20252                  | [5683d776e0](https://linux-hardware.org/?probe=5683d776e0) | Feb 02, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [e14121100b](https://linux-hardware.org/?probe=e14121100b) | Feb 02, 2022 |
| Lenovo        | ThinkPad T420 4236KU9       | [ae25a7a57d](https://linux-hardware.org/?probe=ae25a7a57d) | Feb 02, 2022 |
| Dell          | Inspiron 5748               | [07c8076d3e](https://linux-hardware.org/?probe=07c8076d3e) | Feb 01, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [3e6d5943dd](https://linux-hardware.org/?probe=3e6d5943dd) | Feb 01, 2022 |
| HP            | Pavilion Laptop 15z-eh00... | [76a973d25c](https://linux-hardware.org/?probe=76a973d25c) | Feb 01, 2022 |
| Apple         | MacBookPro8,1               | [70e86eb89a](https://linux-hardware.org/?probe=70e86eb89a) | Jan 31, 2022 |
| Sony          | SVF15213CBW                 | [cf01ca64c3](https://linux-hardware.org/?probe=cf01ca64c3) | Jan 31, 2022 |
| Sony          | SVF15213CBW                 | [17015b4fbe](https://linux-hardware.org/?probe=17015b4fbe) | Jan 30, 2022 |
| Dell          | Latitude E5420              | [89a74ff338](https://linux-hardware.org/?probe=89a74ff338) | Jan 29, 2022 |
| HP            | Pavilion dv7                | [504e2036d3](https://linux-hardware.org/?probe=504e2036d3) | Jan 29, 2022 |
| Dell          | Latitude E6220              | [808db5a1c8](https://linux-hardware.org/?probe=808db5a1c8) | Jan 29, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [95423d6649](https://linux-hardware.org/?probe=95423d6649) | Jan 28, 2022 |
| ASUSTek       | TAICHI21                    | [ccc3361d04](https://linux-hardware.org/?probe=ccc3361d04) | Jan 28, 2022 |
| Apple         | MacBookPro6,2               | [0143cbef50](https://linux-hardware.org/?probe=0143cbef50) | Jan 28, 2022 |
| ASUSTek       | TAICHI21                    | [6b9b9f727e](https://linux-hardware.org/?probe=6b9b9f727e) | Jan 28, 2022 |
| Jumper        | EZbook                      | [4fa449c0ce](https://linux-hardware.org/?probe=4fa449c0ce) | Jan 27, 2022 |
| Acer          | Aspire 5552                 | [ef57c29f8c](https://linux-hardware.org/?probe=ef57c29f8c) | Jan 27, 2022 |
| HP            | Pavilion dv7                | [927e580b5a](https://linux-hardware.org/?probe=927e580b5a) | Jan 26, 2022 |
| ASUSTek       | ROG Strix G513QR            | [fb81914651](https://linux-hardware.org/?probe=fb81914651) | Jan 26, 2022 |
| Lenovo        | ThinkPad X61 7673C44        | [ab461bd99e](https://linux-hardware.org/?probe=ab461bd99e) | Jan 26, 2022 |
| HP            | Pavilion dv7                | [c639bc4c98](https://linux-hardware.org/?probe=c639bc4c98) | Jan 25, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [7078a1a373](https://linux-hardware.org/?probe=7078a1a373) | Jan 25, 2022 |
| Acer          | Aspire V3-571               | [ed5c6cf88d](https://linux-hardware.org/?probe=ed5c6cf88d) | Jan 24, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | [cd8aef64e1](https://linux-hardware.org/?probe=cd8aef64e1) | Jan 24, 2022 |
| Toshiba       | Satellite C660              | [b3aec22953](https://linux-hardware.org/?probe=b3aec22953) | Jan 24, 2022 |
| ASUSTek       | ROG Strix G513QR            | [a31fd268eb](https://linux-hardware.org/?probe=a31fd268eb) | Jan 24, 2022 |
| ASUSTek       | X550CC                      | [5fa0a123f4](https://linux-hardware.org/?probe=5fa0a123f4) | Jan 24, 2022 |
| Dell          | Latitude E6420              | [1cf74dd114](https://linux-hardware.org/?probe=1cf74dd114) | Jan 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [06eb5b9d8d](https://linux-hardware.org/?probe=06eb5b9d8d) | Jan 23, 2022 |
| Toshiba       | TECRA A9                    | [7ba32a721d](https://linux-hardware.org/?probe=7ba32a721d) | Jan 23, 2022 |
| Acer          | NC-E1-572-54208G            | [02d40169ec](https://linux-hardware.org/?probe=02d40169ec) | Jan 23, 2022 |
| Clevo         | W24/250CU                   | [64c6f06849](https://linux-hardware.org/?probe=64c6f06849) | Jan 22, 2022 |
| ASUSTek       | T100TAS                     | [a37b7c51fd](https://linux-hardware.org/?probe=a37b7c51fd) | Jan 22, 2022 |
| HP            | Laptop 14q-cs0xxx           | [ec9061dcb1](https://linux-hardware.org/?probe=ec9061dcb1) | Jan 22, 2022 |
| Lenovo        | G780 20138                  | [4b5e81151e](https://linux-hardware.org/?probe=4b5e81151e) | Jan 22, 2022 |
| ASUSTek       | E200HA                      | [0d0222d2e9](https://linux-hardware.org/?probe=0d0222d2e9) | Jan 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [4c95ae549f](https://linux-hardware.org/?probe=4c95ae549f) | Jan 21, 2022 |
| Dell          | Latitude E5470              | [df22d71530](https://linux-hardware.org/?probe=df22d71530) | Jan 21, 2022 |
| HP            | EliteBook 820 G3            | [81cbc7d48a](https://linux-hardware.org/?probe=81cbc7d48a) | Jan 21, 2022 |
| HP            | EliteBook 820 G3            | [c56fbf1529](https://linux-hardware.org/?probe=c56fbf1529) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [c996d7e988](https://linux-hardware.org/?probe=c996d7e988) | Jan 20, 2022 |
| HP            | Notebook                    | [25a9e6d8a1](https://linux-hardware.org/?probe=25a9e6d8a1) | Jan 20, 2022 |
| ASUSTek       | X540YA                      | [99ff6cb58a](https://linux-hardware.org/?probe=99ff6cb58a) | Jan 20, 2022 |
| HP            | Pavilion dv7                | [e22a47facd](https://linux-hardware.org/?probe=e22a47facd) | Jan 20, 2022 |
| Acer          | Aspire V5-571PG             | [19c732cd05](https://linux-hardware.org/?probe=19c732cd05) | Jan 20, 2022 |
| Multilaser    | UB32X                       | [bd6f4152df](https://linux-hardware.org/?probe=bd6f4152df) | Jan 20, 2022 |
| ASUSTek       | GL552VW                     | [4544642750](https://linux-hardware.org/?probe=4544642750) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [81be3d94a3](https://linux-hardware.org/?probe=81be3d94a3) | Jan 18, 2022 |
| Acer          | Aspire ES1-531              | [d089029f6c](https://linux-hardware.org/?probe=d089029f6c) | Jan 18, 2022 |
| ASUSTek       | K93SV                       | [30f5830a2d](https://linux-hardware.org/?probe=30f5830a2d) | Jan 18, 2022 |
| ASUSTek       | T100TAS                     | [86df8cdba1](https://linux-hardware.org/?probe=86df8cdba1) | Jan 18, 2022 |
| Acer          | Predator G9-792             | [06a6edfaae](https://linux-hardware.org/?probe=06a6edfaae) | Jan 17, 2022 |
| HP            | 15                          | [4dde4c5c0e](https://linux-hardware.org/?probe=4dde4c5c0e) | Jan 17, 2022 |
| Google        | Ultima                      | [d942b9081b](https://linux-hardware.org/?probe=d942b9081b) | Jan 16, 2022 |
| HP            | 250 G4                      | [4de0cf1eb0](https://linux-hardware.org/?probe=4de0cf1eb0) | Jan 16, 2022 |
| Lenovo        | ThinkPad T460s 20FAS09Y0... | [339ea299c8](https://linux-hardware.org/?probe=339ea299c8) | Jan 16, 2022 |
| Acer          | Aspire A315-53              | [4bcdec655f](https://linux-hardware.org/?probe=4bcdec655f) | Jan 16, 2022 |
| Lenovo        | ThinkPad X230 2325WR3       | [decbecce89](https://linux-hardware.org/?probe=decbecce89) | Jan 16, 2022 |
| HP            | ProBook 445 G7              | [04e666772c](https://linux-hardware.org/?probe=04e666772c) | Jan 15, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [7136b51cd1](https://linux-hardware.org/?probe=7136b51cd1) | Jan 15, 2022 |
| Acer          | Aspire 5552                 | [5d3b462042](https://linux-hardware.org/?probe=5d3b462042) | Jan 14, 2022 |
| Lenovo        | ThinkPad T410s 292494G      | [df5d687786](https://linux-hardware.org/?probe=df5d687786) | Jan 14, 2022 |
| ASUSTek       | K52JT                       | [8545fedf93](https://linux-hardware.org/?probe=8545fedf93) | Jan 14, 2022 |
| ASUSTek       | X550CC                      | [0607e7f57e](https://linux-hardware.org/?probe=0607e7f57e) | Jan 14, 2022 |
| HP            | ProBook 640 G1              | [6261e290d6](https://linux-hardware.org/?probe=6261e290d6) | Jan 13, 2022 |
| ASUSTek       | GL552VW                     | [de99d855c5](https://linux-hardware.org/?probe=de99d855c5) | Jan 13, 2022 |
| Dell          | XPS 15 9510                 | [edb752adea](https://linux-hardware.org/?probe=edb752adea) | Jan 13, 2022 |
| ASUSTek       | K54C                        | [048477ec85](https://linux-hardware.org/?probe=048477ec85) | Jan 13, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [b694d6fa5f](https://linux-hardware.org/?probe=b694d6fa5f) | Jan 13, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [0f2222fc06](https://linux-hardware.org/?probe=0f2222fc06) | Jan 13, 2022 |
| Dell          | XPS 15 9510                 | [eb7e68d366](https://linux-hardware.org/?probe=eb7e68d366) | Jan 13, 2022 |
| Razer         | Blade Stealth               | [3e3430ddeb](https://linux-hardware.org/?probe=3e3430ddeb) | Jan 13, 2022 |
| Acer          | Aspire E5-774G              | [bd6fa29ee0](https://linux-hardware.org/?probe=bd6fa29ee0) | Jan 13, 2022 |
| Toshiba       | Satellite C660              | [a4b1346944](https://linux-hardware.org/?probe=a4b1346944) | Jan 13, 2022 |
| Mediacom      | GTZS                        | [ad6de0b39b](https://linux-hardware.org/?probe=ad6de0b39b) | Jan 12, 2022 |
| HP            | Laptop 15-dy2xxx            | [086b27dc7a](https://linux-hardware.org/?probe=086b27dc7a) | Jan 12, 2022 |
| HP            | Laptop 15-dy2xxx            | [c7e776c4f2](https://linux-hardware.org/?probe=c7e776c4f2) | Jan 12, 2022 |
| HP            | Laptop 15-dy2xxx            | [c16f448f2e](https://linux-hardware.org/?probe=c16f448f2e) | Jan 12, 2022 |
| HP            | Pavilion g6                 | [e14f742bb9](https://linux-hardware.org/?probe=e14f742bb9) | Jan 12, 2022 |
| HP            | Pavilion g6                 | [62f049acf1](https://linux-hardware.org/?probe=62f049acf1) | Jan 12, 2022 |
| ASUSTek       | X542BA                      | [d5180ebfbc](https://linux-hardware.org/?probe=d5180ebfbc) | Jan 12, 2022 |
| Lenovo        | G500 20236                  | [2e7bd2b772](https://linux-hardware.org/?probe=2e7bd2b772) | Jan 12, 2022 |
| Acer          | Predator G9-792             | [870f7b6ea5](https://linux-hardware.org/?probe=870f7b6ea5) | Jan 11, 2022 |
| Acer          | Predator G9-792             | [908edac358](https://linux-hardware.org/?probe=908edac358) | Jan 11, 2022 |
| Dell          | Vostro 1500                 | [d81572b40f](https://linux-hardware.org/?probe=d81572b40f) | Jan 11, 2022 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | [4013d5dc28](https://linux-hardware.org/?probe=4013d5dc28) | Jan 11, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [3cd5068430](https://linux-hardware.org/?probe=3cd5068430) | Jan 10, 2022 |
| HP            | ProBook 6450b               | [73b06fa964](https://linux-hardware.org/?probe=73b06fa964) | Jan 10, 2022 |
| Lenovo        | V14-IIL 82C4                | [8fd207e668](https://linux-hardware.org/?probe=8fd207e668) | Jan 10, 2022 |
| Dell          | Latitude E6510              | [df2d1f8aa1](https://linux-hardware.org/?probe=df2d1f8aa1) | Jan 09, 2022 |
| HP            | Pavilion 15                 | [95f3d87b66](https://linux-hardware.org/?probe=95f3d87b66) | Jan 09, 2022 |
| HP            | Compaq 8510p                | [94c5350957](https://linux-hardware.org/?probe=94c5350957) | Jan 09, 2022 |
| ASUSTek       | K52JT                       | [c5d880e138](https://linux-hardware.org/?probe=c5d880e138) | Jan 09, 2022 |
| Unknown       | SCHNEIDER                   | [03b1f6dfed](https://linux-hardware.org/?probe=03b1f6dfed) | Jan 09, 2022 |
| ASUSTek       | GL552VW                     | [69a4959007](https://linux-hardware.org/?probe=69a4959007) | Jan 09, 2022 |
| ASUSTek       | X553MA                      | [cdf5230fdb](https://linux-hardware.org/?probe=cdf5230fdb) | Jan 09, 2022 |
| Samsung       | R59P/R60P/R61P              | [dd061ae267](https://linux-hardware.org/?probe=dd061ae267) | Jan 08, 2022 |
| HP            | Laptop 15s-du2xxx           | [e6c704567e](https://linux-hardware.org/?probe=e6c704567e) | Jan 08, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [95c067b96e](https://linux-hardware.org/?probe=95c067b96e) | Jan 07, 2022 |
| MSI           | GE75 Raider 8SF             | [23aab4b14f](https://linux-hardware.org/?probe=23aab4b14f) | Jan 06, 2022 |
| ASUSTek       | X542BP                      | [1f13c19485](https://linux-hardware.org/?probe=1f13c19485) | Jan 06, 2022 |
| Toshiba       | Satellite A200              | [613096a5ad](https://linux-hardware.org/?probe=613096a5ad) | Jan 06, 2022 |
| HP            | Laptop 15s-dr0xxx           | [be60e498db](https://linux-hardware.org/?probe=be60e498db) | Jan 06, 2022 |
| HP            | ProBook 4510s               | [cb983f7833](https://linux-hardware.org/?probe=cb983f7833) | Jan 06, 2022 |
| Dell          | Inspiron M5030              | [1715a3e584](https://linux-hardware.org/?probe=1715a3e584) | Jan 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | [64d6a48fd3](https://linux-hardware.org/?probe=64d6a48fd3) | Jan 06, 2022 |
| Acer          | Aspire 7741                 | [2f03831c23](https://linux-hardware.org/?probe=2f03831c23) | Jan 05, 2022 |
| Acer          | E1-510                      | [f5a0998e25](https://linux-hardware.org/?probe=f5a0998e25) | Jan 05, 2022 |
| ASUSTek       | X555QG                      | [a10e6b5ec0](https://linux-hardware.org/?probe=a10e6b5ec0) | Jan 04, 2022 |
| Acer          | Aspire 6930G                | [929cea53e3](https://linux-hardware.org/?probe=929cea53e3) | Jan 04, 2022 |
| Dell          | Inspiron 1750               | [827adb411f](https://linux-hardware.org/?probe=827adb411f) | Jan 04, 2022 |
| Lenovo        | G50-70 20351                | [04b904c594](https://linux-hardware.org/?probe=04b904c594) | Jan 04, 2022 |
| NEC Comput... | PC-LL550RG                  | [43435578b7](https://linux-hardware.org/?probe=43435578b7) | Jan 04, 2022 |
| Toshiba       | TECRA A9                    | [783735cff8](https://linux-hardware.org/?probe=783735cff8) | Jan 04, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [9f6ca62b59](https://linux-hardware.org/?probe=9f6ca62b59) | Jan 04, 2022 |
| ASUSTek       | X555QG                      | [9062bc4b1d](https://linux-hardware.org/?probe=9062bc4b1d) | Jan 03, 2022 |
| Dell          | Inspiron 13-5378            | [8d019441d1](https://linux-hardware.org/?probe=8d019441d1) | Jan 03, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [22a9d41db0](https://linux-hardware.org/?probe=22a9d41db0) | Jan 02, 2022 |
| Dell          | Latitude E7440              | [9df6480d3e](https://linux-hardware.org/?probe=9df6480d3e) | Jan 02, 2022 |
| Toshiba       | Satellite C870-1C2          | [1d759e7171](https://linux-hardware.org/?probe=1d759e7171) | Jan 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [6100abe0e1](https://linux-hardware.org/?probe=6100abe0e1) | Jan 02, 2022 |
| Dell          | Latitude E7440              | [60b74121ad](https://linux-hardware.org/?probe=60b74121ad) | Jan 02, 2022 |
| Lenovo        | ThinkPad T490 20N3S6US00    | [087fbff7d6](https://linux-hardware.org/?probe=087fbff7d6) | Jan 02, 2022 |
| Dell          | Inspiron 5770               | [0e81199f2c](https://linux-hardware.org/?probe=0e81199f2c) | Jan 02, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [367ef74be3](https://linux-hardware.org/?probe=367ef74be3) | Jan 01, 2022 |
| Lenovo        | V14-IIL 82C4                | [7dcf51eb69](https://linux-hardware.org/?probe=7dcf51eb69) | Jan 01, 2022 |
| Lenovo        | ThinkPad T490 20N3S6US00    | [f748f15a80](https://linux-hardware.org/?probe=f748f15a80) | Jan 01, 2022 |
| Jumper        | EZbook                      | [aed28b71f9](https://linux-hardware.org/?probe=aed28b71f9) | Jan 01, 2022 |
| MSI           | EX705                       | [a969bd4369](https://linux-hardware.org/?probe=a969bd4369) | Dec 31, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [0bfa74fa9f](https://linux-hardware.org/?probe=0bfa74fa9f) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | [90d57a20ee](https://linux-hardware.org/?probe=90d57a20ee) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | [4db624e8a0](https://linux-hardware.org/?probe=4db624e8a0) | Dec 31, 2021 |
| HP            | EliteBook Folio 9470m       | [b79e118712](https://linux-hardware.org/?probe=b79e118712) | Dec 31, 2021 |
| MSI           | GE-700                      | [9ccf434539](https://linux-hardware.org/?probe=9ccf434539) | Dec 31, 2021 |
| MSI           | GE-700                      | [dd9998069e](https://linux-hardware.org/?probe=dd9998069e) | Dec 31, 2021 |
| Toshiba       | Satellite L300              | [fc547136cc](https://linux-hardware.org/?probe=fc547136cc) | Dec 31, 2021 |
| ASUSTek       | GL552VW                     | [42fd7ed22b](https://linux-hardware.org/?probe=42fd7ed22b) | Dec 31, 2021 |
| HP            | Pavilion dv5                | [7017ea359e](https://linux-hardware.org/?probe=7017ea359e) | Dec 31, 2021 |
| Acer          | Aspire 1810TZ               | [0b7bd5c1fa](https://linux-hardware.org/?probe=0b7bd5c1fa) | Dec 30, 2021 |
| MSI           | GT70 2OC/2OD                | [baefd0bda3](https://linux-hardware.org/?probe=baefd0bda3) | Dec 30, 2021 |
| Dell          | XPS 13 9370                 | [f20a77fa7e](https://linux-hardware.org/?probe=f20a77fa7e) | Dec 29, 2021 |
| Packard Be... | EasyNote TK85               | [cef3f4f826](https://linux-hardware.org/?probe=cef3f4f826) | Dec 28, 2021 |
| HP            | ProBook 4730s               | [08cca0b4b5](https://linux-hardware.org/?probe=08cca0b4b5) | Dec 28, 2021 |
| Lenovo        | ThinkPad L540 20AV0031MB    | [5abe6c6347](https://linux-hardware.org/?probe=5abe6c6347) | Dec 28, 2021 |
| ASUSTek       | X302LA                      | [3c747e6bb0](https://linux-hardware.org/?probe=3c747e6bb0) | Dec 28, 2021 |
| Dell          | Latitude 7490               | [044b1ea3d3](https://linux-hardware.org/?probe=044b1ea3d3) | Dec 28, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [55b2c93259](https://linux-hardware.org/?probe=55b2c93259) | Dec 28, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | [82c3a0ea01](https://linux-hardware.org/?probe=82c3a0ea01) | Dec 28, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [fa2df1f6f0](https://linux-hardware.org/?probe=fa2df1f6f0) | Dec 27, 2021 |
| MSI           | GT70 2OC/2OD                | [8445e5b6fe](https://linux-hardware.org/?probe=8445e5b6fe) | Dec 27, 2021 |
| Lenovo        | V14-IIL 82C4                | [b525e5f8c0](https://linux-hardware.org/?probe=b525e5f8c0) | Dec 27, 2021 |
| MSI           | GT70 2OC/2OD                | [624f5a11a8](https://linux-hardware.org/?probe=624f5a11a8) | Dec 27, 2021 |
| HP            | EliteBook 2760p             | [1cd129ee35](https://linux-hardware.org/?probe=1cd129ee35) | Dec 27, 2021 |
| HP            | EliteBook 2760p             | [f2deb9ec59](https://linux-hardware.org/?probe=f2deb9ec59) | Dec 27, 2021 |
| Dell          | Inspiron 3583               | [adcf14bf31](https://linux-hardware.org/?probe=adcf14bf31) | Dec 27, 2021 |
| Acer          | Aspire M5-481T              | [2515a869a5](https://linux-hardware.org/?probe=2515a869a5) | Dec 26, 2021 |
| Acer          | Aspire M5-481T              | [1ef9b940b2](https://linux-hardware.org/?probe=1ef9b940b2) | Dec 26, 2021 |
| Fusion5       | FWIN232_PLUS                | [ce10f25e8c](https://linux-hardware.org/?probe=ce10f25e8c) | Dec 25, 2021 |
| Dell          | Latitude 12 Rugged Table... | [13cc8e2abf](https://linux-hardware.org/?probe=13cc8e2abf) | Dec 25, 2021 |
| ASUSTek       | M50Vm                       | [bc36782a82](https://linux-hardware.org/?probe=bc36782a82) | Dec 25, 2021 |
| HP            | Pavilion dv7                | [67230f9226](https://linux-hardware.org/?probe=67230f9226) | Dec 25, 2021 |
| Dell          | Latitude 3440               | [e80fdcee0c](https://linux-hardware.org/?probe=e80fdcee0c) | Dec 25, 2021 |
| Toshiba       | TECRA S11                   | [b846fd9c93](https://linux-hardware.org/?probe=b846fd9c93) | Dec 24, 2021 |
| Dell          | Latitude 3540               | [7e7f291d68](https://linux-hardware.org/?probe=7e7f291d68) | Dec 24, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [3415419b6b](https://linux-hardware.org/?probe=3415419b6b) | Dec 23, 2021 |
| Acer          | Aspire E1-531               | [d1d6054fc3](https://linux-hardware.org/?probe=d1d6054fc3) | Dec 22, 2021 |
| HP            | Pavilion dv7                | [5823ca14b0](https://linux-hardware.org/?probe=5823ca14b0) | Dec 22, 2021 |
| ASUSTek       | K53E                        | [0a089d38c0](https://linux-hardware.org/?probe=0a089d38c0) | Dec 21, 2021 |
| Sony          | VGN-FW21E                   | [0c58cd8d69](https://linux-hardware.org/?probe=0c58cd8d69) | Dec 20, 2021 |
| Sony          | VPCF23M1E                   | [a7e83ee775](https://linux-hardware.org/?probe=a7e83ee775) | Dec 20, 2021 |
| Sony          | VPCF23M1E                   | [f10ab27170](https://linux-hardware.org/?probe=f10ab27170) | Dec 20, 2021 |
| HP            | EliteBook 2570p             | [462b93b05b](https://linux-hardware.org/?probe=462b93b05b) | Dec 20, 2021 |
| Digibras      | NH4CU03                     | [517425552d](https://linux-hardware.org/?probe=517425552d) | Dec 19, 2021 |
| Sony          | VGN-FW21E                   | [d90a22e7b0](https://linux-hardware.org/?probe=d90a22e7b0) | Dec 19, 2021 |
| Acer          | Aspire V3-571               | [5189bf7726](https://linux-hardware.org/?probe=5189bf7726) | Dec 19, 2021 |
| ASUSTek       | X751LD                      | [2013d9d5d8](https://linux-hardware.org/?probe=2013d9d5d8) | Dec 19, 2021 |
| ASUSTek       | X751LD                      | [67286f0d11](https://linux-hardware.org/?probe=67286f0d11) | Dec 19, 2021 |
| Packard Be... | EasyNote TE11BZ             | [24fef50189](https://linux-hardware.org/?probe=24fef50189) | Dec 19, 2021 |
| HP            | EliteBook 8440p             | [0dc23e59a4](https://linux-hardware.org/?probe=0dc23e59a4) | Dec 19, 2021 |
| HP            | EliteBook 8440p             | [6eab2c603a](https://linux-hardware.org/?probe=6eab2c603a) | Dec 19, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [897b589a83](https://linux-hardware.org/?probe=897b589a83) | Dec 19, 2021 |
| ASUSTek       | K53SD                       | [68a3cbb84c](https://linux-hardware.org/?probe=68a3cbb84c) | Dec 18, 2021 |
| HP            | Laptop 15-db1xxx            | [20f9c7a4ef](https://linux-hardware.org/?probe=20f9c7a4ef) | Dec 18, 2021 |
| Toshiba       | Satellite C660              | [6f860db242](https://linux-hardware.org/?probe=6f860db242) | Dec 18, 2021 |
| Dell          | Latitude E6500              | [5a29db9bdf](https://linux-hardware.org/?probe=5a29db9bdf) | Dec 18, 2021 |
| Lenovo        | ThinkPad X230 2325SYU       | [3b01a9e8eb](https://linux-hardware.org/?probe=3b01a9e8eb) | Dec 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dda5e17a21](https://linux-hardware.org/?probe=dda5e17a21) | Dec 17, 2021 |
| Toshiba       | TECRA A9                    | [53cba6b9d1](https://linux-hardware.org/?probe=53cba6b9d1) | Dec 16, 2021 |
| Login Info... | LOG-MB47II7                 | [58eb588f8b](https://linux-hardware.org/?probe=58eb588f8b) | Dec 16, 2021 |
| Login Info... | LOG-MB47II7                 | [84cabc70f7](https://linux-hardware.org/?probe=84cabc70f7) | Dec 16, 2021 |
| Compaq        | Presario 21                 | [86e7a85db3](https://linux-hardware.org/?probe=86e7a85db3) | Dec 16, 2021 |
| Toshiba       | QOSMIO X770                 | [c8c9ab4cf8](https://linux-hardware.org/?probe=c8c9ab4cf8) | Dec 16, 2021 |
| HP            | ZBook 17 G5                 | [761a2419e5](https://linux-hardware.org/?probe=761a2419e5) | Dec 16, 2021 |
| RCA           | WT9503W004                  | [c858eb3cbc](https://linux-hardware.org/?probe=c858eb3cbc) | Dec 15, 2021 |
| Dell          | Latitude E6400              | [dc0d35221e](https://linux-hardware.org/?probe=dc0d35221e) | Dec 15, 2021 |
| HP            | EliteBook 8730w             | [e35ce8395b](https://linux-hardware.org/?probe=e35ce8395b) | Dec 15, 2021 |
| HP            | ProBook 450 G3              | [d197761676](https://linux-hardware.org/?probe=d197761676) | Dec 15, 2021 |
| Google        | Squawks                     | [e75aa07dad](https://linux-hardware.org/?probe=e75aa07dad) | Dec 15, 2021 |
| Acer          | Aspire V3-571               | [071a8f0709](https://linux-hardware.org/?probe=071a8f0709) | Dec 15, 2021 |
| Dell          | Inspiron 3501               | [6cf66f6290](https://linux-hardware.org/?probe=6cf66f6290) | Dec 15, 2021 |
| Lenovo        | G580 20150                  | [6ff1581ca6](https://linux-hardware.org/?probe=6ff1581ca6) | Dec 14, 2021 |
| Acer          | AOD255                      | [08a007120e](https://linux-hardware.org/?probe=08a007120e) | Dec 14, 2021 |
| HP            | EliteBook Folio 9480m       | [11eea57427](https://linux-hardware.org/?probe=11eea57427) | Dec 14, 2021 |
| Toshiba       | Satellite L655              | [0db50aad32](https://linux-hardware.org/?probe=0db50aad32) | Dec 14, 2021 |
| Digibras      | NH4CU03                     | [97b0f21219](https://linux-hardware.org/?probe=97b0f21219) | Dec 14, 2021 |
| MSI           | PS42 Modern 8RC             | [2686d73cb8](https://linux-hardware.org/?probe=2686d73cb8) | Dec 13, 2021 |
| Lenovo        | ThinkPad X270 20HN0043AD    | [24160af893](https://linux-hardware.org/?probe=24160af893) | Dec 13, 2021 |
| Google        | Squawks                     | [31cb595893](https://linux-hardware.org/?probe=31cb595893) | Dec 13, 2021 |
| Digibras      | NH4CU03                     | [5ffb383677](https://linux-hardware.org/?probe=5ffb383677) | Dec 13, 2021 |
| Acer          | Aspire V3-571               | [54680bac44](https://linux-hardware.org/?probe=54680bac44) | Dec 12, 2021 |
| Dell          | Precision M4600             | [32034c26c7](https://linux-hardware.org/?probe=32034c26c7) | Dec 12, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d364ff0c44](https://linux-hardware.org/?probe=d364ff0c44) | Dec 12, 2021 |
| HP            | ProBook 450 G3              | [54846cdc88](https://linux-hardware.org/?probe=54846cdc88) | Dec 12, 2021 |
| Dell          | Latitude E5410              | [8b6bc5cf8e](https://linux-hardware.org/?probe=8b6bc5cf8e) | Dec 12, 2021 |
| Apple         | MacBook4,1                  | [7bf355c3c1](https://linux-hardware.org/?probe=7bf355c3c1) | Dec 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [807bd77769](https://linux-hardware.org/?probe=807bd77769) | Dec 12, 2021 |
| Positivo      | CHT14B                      | [6ebdfd7b1f](https://linux-hardware.org/?probe=6ebdfd7b1f) | Dec 12, 2021 |
| Acer          | Aspire 4830T                | [554d2d7ce0](https://linux-hardware.org/?probe=554d2d7ce0) | Dec 12, 2021 |
| Acer          | Aspire 4830T                | [cbf04f6efb](https://linux-hardware.org/?probe=cbf04f6efb) | Dec 12, 2021 |
| Dell          | Precision M4600             | [f3f7be37a2](https://linux-hardware.org/?probe=f3f7be37a2) | Dec 12, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [0fb07d458a](https://linux-hardware.org/?probe=0fb07d458a) | Dec 12, 2021 |
| Acer          | Aspire A517-52              | [a51b1f9eb7](https://linux-hardware.org/?probe=a51b1f9eb7) | Dec 11, 2021 |
| Acer          | Aspire A517-52              | [bbf5c7ea28](https://linux-hardware.org/?probe=bbf5c7ea28) | Dec 11, 2021 |
| Dell          | Latitude E5400              | [2444de97e0](https://linux-hardware.org/?probe=2444de97e0) | Dec 11, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [a5528e8f98](https://linux-hardware.org/?probe=a5528e8f98) | Dec 11, 2021 |
| Chuwi         | GemiBook Pro                | [493d55cb16](https://linux-hardware.org/?probe=493d55cb16) | Dec 11, 2021 |
| TCL Commun... | 8085                        | [3d795ceee0](https://linux-hardware.org/?probe=3d795ceee0) | Dec 11, 2021 |
| Dell          | Latitude E5400              | [212020992c](https://linux-hardware.org/?probe=212020992c) | Dec 11, 2021 |
| HP            | Pavilion dv3                | [484e48a117](https://linux-hardware.org/?probe=484e48a117) | Dec 11, 2021 |
| HP            | 15 Notebook PC              | [3be4065d87](https://linux-hardware.org/?probe=3be4065d87) | Dec 10, 2021 |
| HP            | 15 Notebook PC              | [c06d1d8915](https://linux-hardware.org/?probe=c06d1d8915) | Dec 10, 2021 |
| Dell          | Latitude E7440              | [ff067012c5](https://linux-hardware.org/?probe=ff067012c5) | Dec 09, 2021 |
| Samsung       | N150P/N210P/N220P           | [eed2dcde15](https://linux-hardware.org/?probe=eed2dcde15) | Dec 09, 2021 |
| Apple         | MacBook4,1                  | [cfa6005bc4](https://linux-hardware.org/?probe=cfa6005bc4) | Dec 09, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [dc07419c59](https://linux-hardware.org/?probe=dc07419c59) | Dec 08, 2021 |
| Dell          | Latitude E5400              | [a4fa2f67d3](https://linux-hardware.org/?probe=a4fa2f67d3) | Dec 08, 2021 |
| Lenovo        | ThinkPad T400 741722U       | [2739940ec1](https://linux-hardware.org/?probe=2739940ec1) | Dec 08, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [c31f062314](https://linux-hardware.org/?probe=c31f062314) | Dec 07, 2021 |
| HP            | HDX 16                      | [cf114f9094](https://linux-hardware.org/?probe=cf114f9094) | Dec 07, 2021 |
| Unknown       | Unknown                     | [9e9e0598b6](https://linux-hardware.org/?probe=9e9e0598b6) | Dec 07, 2021 |
| HP            | Stream Laptop 14-cb1XX      | [4853c251a8](https://linux-hardware.org/?probe=4853c251a8) | Dec 07, 2021 |
| Apple         | MacBookPro8,1               | [85d594af54](https://linux-hardware.org/?probe=85d594af54) | Dec 07, 2021 |
| Razer         | Blade 15 Base Model (Ear... | [9c64eb115e](https://linux-hardware.org/?probe=9c64eb115e) | Dec 07, 2021 |
| Lenovo        | ThinkPad T400 741722U       | [2933ad8c69](https://linux-hardware.org/?probe=2933ad8c69) | Dec 07, 2021 |
| Dell          | Inspiron 5748               | [77f278682e](https://linux-hardware.org/?probe=77f278682e) | Dec 06, 2021 |
| Apple         | MacBookPro11,1              | [f454c30e46](https://linux-hardware.org/?probe=f454c30e46) | Dec 05, 2021 |
| Acer          | Aspire V3-571G              | [3acb23e27c](https://linux-hardware.org/?probe=3acb23e27c) | Dec 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [fc540c3951](https://linux-hardware.org/?probe=fc540c3951) | Dec 05, 2021 |
| Dell          | Inspiron 5770               | [c8a717a1c9](https://linux-hardware.org/?probe=c8a717a1c9) | Dec 05, 2021 |
| ASUSTek       | X553MA                      | [958551b7eb](https://linux-hardware.org/?probe=958551b7eb) | Dec 05, 2021 |
| Sony          | SVF1532Z1EB                 | [d65626b69d](https://linux-hardware.org/?probe=d65626b69d) | Dec 04, 2021 |
| ASUSTek       | X553MA                      | [78414b8bc4](https://linux-hardware.org/?probe=78414b8bc4) | Dec 04, 2021 |
| Lenovo        | G700                        | [2b7a430fcd](https://linux-hardware.org/?probe=2b7a430fcd) | Dec 04, 2021 |
| Toshiba       | Satellite C660              | [4d64247a8a](https://linux-hardware.org/?probe=4d64247a8a) | Dec 04, 2021 |
| ASUSTek       | K53TK                       | [043ef58552](https://linux-hardware.org/?probe=043ef58552) | Dec 03, 2021 |
| HUAWEI        | KLVL-WXX9                   | [6c468accc0](https://linux-hardware.org/?probe=6c468accc0) | Dec 03, 2021 |
| HUAWEI        | KLVL-WXX9                   | [ee27adb248](https://linux-hardware.org/?probe=ee27adb248) | Dec 03, 2021 |
| Acer          | Aspire A315-58G             | [48e3c0e6c7](https://linux-hardware.org/?probe=48e3c0e6c7) | Dec 03, 2021 |
| HP            | OMEN Notebook               | [5b8b235c98](https://linux-hardware.org/?probe=5b8b235c98) | Dec 03, 2021 |
| Samsung       | 700T                        | [efe2d4bd92](https://linux-hardware.org/?probe=efe2d4bd92) | Dec 03, 2021 |
| Dell          | Latitude E6530              | [fe6dbdef48](https://linux-hardware.org/?probe=fe6dbdef48) | Dec 03, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [29ff3edb05](https://linux-hardware.org/?probe=29ff3edb05) | Dec 03, 2021 |
| Toshiba       | Satellite L655              | [0e3a82aad6](https://linux-hardware.org/?probe=0e3a82aad6) | Dec 03, 2021 |
| HUAWEI        | KLVL-WXX9                   | [c806323840](https://linux-hardware.org/?probe=c806323840) | Dec 03, 2021 |
| Dell          | Latitude 7280               | [8baf21a38d](https://linux-hardware.org/?probe=8baf21a38d) | Dec 02, 2021 |
| HUAWEI        | KLVL-WXX9                   | [57b4dae376](https://linux-hardware.org/?probe=57b4dae376) | Dec 02, 2021 |
| HP            | 15                          | [8d1ef12e0e](https://linux-hardware.org/?probe=8d1ef12e0e) | Dec 02, 2021 |
| HP            | ProBook 450 G3              | [ca49dc0eee](https://linux-hardware.org/?probe=ca49dc0eee) | Dec 02, 2021 |
| HP            | 15                          | [b374916ca6](https://linux-hardware.org/?probe=b374916ca6) | Dec 02, 2021 |
| Toshiba       | Satellite L55-B             | [0bc52401f0](https://linux-hardware.org/?probe=0bc52401f0) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | [cb2302b704](https://linux-hardware.org/?probe=cb2302b704) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | [f580be444b](https://linux-hardware.org/?probe=f580be444b) | Dec 02, 2021 |
| mPTech        | ARC 11.6 128GB HD           | [e2fbd06e2a](https://linux-hardware.org/?probe=e2fbd06e2a) | Dec 02, 2021 |
| TUXEDO        | Pulse 14 Gen1               | [c7eeb775f9](https://linux-hardware.org/?probe=c7eeb775f9) | Dec 02, 2021 |
| HP            | 15                          | [cb278b1a6b](https://linux-hardware.org/?probe=cb278b1a6b) | Dec 02, 2021 |
| Dell          | Latitude E5570              | [d7beab52f4](https://linux-hardware.org/?probe=d7beab52f4) | Dec 02, 2021 |
| Avell High... | B.ON                        | [a7513f22ee](https://linux-hardware.org/?probe=a7513f22ee) | Dec 02, 2021 |
| Primux        | 15R5A                       | [3aef7d25e8](https://linux-hardware.org/?probe=3aef7d25e8) | Dec 01, 2021 |
| ASUSTek       | X751LAB                     | [4383b601f4](https://linux-hardware.org/?probe=4383b601f4) | Nov 30, 2021 |
| MSI           | GF63 Thin 10SC              | [5f908f227a](https://linux-hardware.org/?probe=5f908f227a) | Nov 30, 2021 |
| HP            | EliteBook 8440p             | [cecc697189](https://linux-hardware.org/?probe=cecc697189) | Nov 30, 2021 |
| Dell          | Inspiron 15-3567            | [3a2bf12582](https://linux-hardware.org/?probe=3a2bf12582) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | [7184635417](https://linux-hardware.org/?probe=7184635417) | Nov 29, 2021 |
| Dell          | Latitude 7275               | [bf808d506c](https://linux-hardware.org/?probe=bf808d506c) | Nov 29, 2021 |
| Chuwi         | GemiBook                    | [911b855817](https://linux-hardware.org/?probe=911b855817) | Nov 28, 2021 |
| Chuwi         | GemiBook                    | [b8f87029fa](https://linux-hardware.org/?probe=b8f87029fa) | Nov 28, 2021 |
| Dell          | Latitude E5420              | [9f504b4e6b](https://linux-hardware.org/?probe=9f504b4e6b) | Nov 28, 2021 |
| ASUSTek       | P453UJ                      | [056cba6efd](https://linux-hardware.org/?probe=056cba6efd) | Nov 28, 2021 |
| ASUSTek       | X455LJ                      | [018d5bcbac](https://linux-hardware.org/?probe=018d5bcbac) | Nov 27, 2021 |
| Acer          | Aspire 4830T                | [205025f3c7](https://linux-hardware.org/?probe=205025f3c7) | Nov 27, 2021 |
| Acer          | Aspire A315-42              | [a0483c5539](https://linux-hardware.org/?probe=a0483c5539) | Nov 27, 2021 |
| Toshiba       | Satellite L500              | [24645f6ab5](https://linux-hardware.org/?probe=24645f6ab5) | Nov 26, 2021 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | [25e2834604](https://linux-hardware.org/?probe=25e2834604) | Nov 25, 2021 |
| Acer          | Aspire 4830T                | [757863f7de](https://linux-hardware.org/?probe=757863f7de) | Nov 25, 2021 |
| Notebook      | NH50_70RA                   | [baa1c5d2ca](https://linux-hardware.org/?probe=baa1c5d2ca) | Nov 24, 2021 |
| HP            | Elite x2 1012 G1            | [5e2d2a574d](https://linux-hardware.org/?probe=5e2d2a574d) | Nov 24, 2021 |
| Lenovo        | Flex 2-14 20404             | [74894434bb](https://linux-hardware.org/?probe=74894434bb) | Nov 24, 2021 |
| ASUSTek       | GL552VW                     | [77929060f7](https://linux-hardware.org/?probe=77929060f7) | Nov 24, 2021 |
| Sony          | SVE1713Y1EB                 | [755b7b85f5](https://linux-hardware.org/?probe=755b7b85f5) | Nov 24, 2021 |
| HP            | EliteBook 8460p             | [ca30b13118](https://linux-hardware.org/?probe=ca30b13118) | Nov 24, 2021 |
| HP            | EliteBook 8570p             | [6c08986736](https://linux-hardware.org/?probe=6c08986736) | Nov 24, 2021 |
| Acer          | Okinawa                     | [2953f32ed9](https://linux-hardware.org/?probe=2953f32ed9) | Nov 23, 2021 |
| HP            | Pavilion 17                 | [315037ddfd](https://linux-hardware.org/?probe=315037ddfd) | Nov 23, 2021 |
| Sony          | VPCSA3N9E                   | [33a3597313](https://linux-hardware.org/?probe=33a3597313) | Nov 23, 2021 |
| Sony          | VPCSA3N9E                   | [c1bf05d67a](https://linux-hardware.org/?probe=c1bf05d67a) | Nov 23, 2021 |
| ASUSTek       | GL552VW                     | [59670a3933](https://linux-hardware.org/?probe=59670a3933) | Nov 23, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [56ff76e064](https://linux-hardware.org/?probe=56ff76e064) | Nov 23, 2021 |
| ASUSTek       | G750JX                      | [f503f26e28](https://linux-hardware.org/?probe=f503f26e28) | Nov 23, 2021 |
| HP            | Pavilion dv7                | [fa2ac7c179](https://linux-hardware.org/?probe=fa2ac7c179) | Nov 23, 2021 |
| Lenovo        | G580 20150                  | [baade6ba54](https://linux-hardware.org/?probe=baade6ba54) | Nov 22, 2021 |
| Lenovo        | G580 20150                  | [b7718027af](https://linux-hardware.org/?probe=b7718027af) | Nov 22, 2021 |
| HP            | 15                          | [1753404669](https://linux-hardware.org/?probe=1753404669) | Nov 22, 2021 |
| HP            | Notebook                    | [9e9ce14e95](https://linux-hardware.org/?probe=9e9ce14e95) | Nov 22, 2021 |
| ASUSTek       | X751SA                      | [d19fd8c59f](https://linux-hardware.org/?probe=d19fd8c59f) | Nov 22, 2021 |
| Toshiba       | Satellite L500              | [30bfdcb5ff](https://linux-hardware.org/?probe=30bfdcb5ff) | Nov 22, 2021 |
| HP            | ENVY TS 15                  | [ca6e82745c](https://linux-hardware.org/?probe=ca6e82745c) | Nov 22, 2021 |
| Fujitsu Si... | AMILO Pa 1510               | [9f731acb7e](https://linux-hardware.org/?probe=9f731acb7e) | Nov 22, 2021 |
| HP            | 15                          | [bca58eb5e0](https://linux-hardware.org/?probe=bca58eb5e0) | Nov 22, 2021 |
| Apple         | MacBookPro5,3               | [5a4e91eace](https://linux-hardware.org/?probe=5a4e91eace) | Nov 22, 2021 |
| ASUSTek       | U56E                        | [2b347f1923](https://linux-hardware.org/?probe=2b347f1923) | Nov 22, 2021 |
| Lenovo        | G560 0679                   | [15348ebbf9](https://linux-hardware.org/?probe=15348ebbf9) | Nov 22, 2021 |
| HP            | Pavilion 15                 | [0f1442bb2c](https://linux-hardware.org/?probe=0f1442bb2c) | Nov 22, 2021 |
| Toshiba       | PORTEGE R705                | [47688cd36a](https://linux-hardware.org/?probe=47688cd36a) | Nov 21, 2021 |
| Toshiba       | Satellite U300              | [827ec6ed62](https://linux-hardware.org/?probe=827ec6ed62) | Nov 21, 2021 |
| HP            | Pavilion dv7                | [7c745f9e5a](https://linux-hardware.org/?probe=7c745f9e5a) | Nov 21, 2021 |
| HP            | ENVY Notebook               | [09767edae3](https://linux-hardware.org/?probe=09767edae3) | Nov 21, 2021 |
| Dell          | Latitude E6440              | [babff23db6](https://linux-hardware.org/?probe=babff23db6) | Nov 21, 2021 |
| Dell          | G7 7700                     | [730daa1080](https://linux-hardware.org/?probe=730daa1080) | Nov 21, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6505        | [c99c5700f6](https://linux-hardware.org/?probe=c99c5700f6) | Nov 20, 2021 |
| HP            | Pavilion Notebook           | [ca1ccc6e65](https://linux-hardware.org/?probe=ca1ccc6e65) | Nov 20, 2021 |
| ASUSTek       | K53U                        | [12136b1cbd](https://linux-hardware.org/?probe=12136b1cbd) | Nov 20, 2021 |
| HP            | Pavilion 15                 | [687ecf1c58](https://linux-hardware.org/?probe=687ecf1c58) | Nov 20, 2021 |
| Sony          | SVE1713D1EW                 | [20d3ee7401](https://linux-hardware.org/?probe=20d3ee7401) | Nov 20, 2021 |
| ASUSTek       | K53U                        | [5a5b8c420f](https://linux-hardware.org/?probe=5a5b8c420f) | Nov 20, 2021 |
| Dell          | Latitude E7440              | [89fdff42c1](https://linux-hardware.org/?probe=89fdff42c1) | Nov 20, 2021 |
| Dell          | Precision M6700             | [a8bf3915fb](https://linux-hardware.org/?probe=a8bf3915fb) | Nov 20, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [7ddd35d3e8](https://linux-hardware.org/?probe=7ddd35d3e8) | Nov 20, 2021 |
| Sony          | SVE1713Y1EB                 | [4a77a751d9](https://linux-hardware.org/?probe=4a77a751d9) | Nov 20, 2021 |
| Toshiba       | Satellite C50D-B            | [6c92d7fef6](https://linux-hardware.org/?probe=6c92d7fef6) | Nov 19, 2021 |
| Dell          | Latitude E5550              | [2f52aa274c](https://linux-hardware.org/?probe=2f52aa274c) | Nov 19, 2021 |
| LG Electro... | S460-G.BG31P1               | [96d8266022](https://linux-hardware.org/?probe=96d8266022) | Nov 19, 2021 |
| Sony          | SVE1713D1EW                 | [cf21ed12bc](https://linux-hardware.org/?probe=cf21ed12bc) | Nov 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S1GW1Q    | [3b8a61e460](https://linux-hardware.org/?probe=3b8a61e460) | Nov 18, 2021 |
| Google        | Lars                        | [c346746b7e](https://linux-hardware.org/?probe=c346746b7e) | Nov 18, 2021 |
| Dell          | Latitude 5590               | [8bef1790bd](https://linux-hardware.org/?probe=8bef1790bd) | Nov 18, 2021 |
| Toshiba       | Satellite C870-1C2          | [e3e16a0c1f](https://linux-hardware.org/?probe=e3e16a0c1f) | Nov 17, 2021 |
| Acer          | TravelMate 6292             | [2cec3b7547](https://linux-hardware.org/?probe=2cec3b7547) | Nov 17, 2021 |
| HP            | ENVY m7 Notebook            | [4b101cc132](https://linux-hardware.org/?probe=4b101cc132) | Nov 17, 2021 |
| HP            | Stream Notebook PC 14       | [31499aa79d](https://linux-hardware.org/?probe=31499aa79d) | Nov 17, 2021 |
| HP            | Stream Notebook PC 14       | [8c30001e99](https://linux-hardware.org/?probe=8c30001e99) | Nov 17, 2021 |
| Dell          | Precision M6700             | [fb4051d1de](https://linux-hardware.org/?probe=fb4051d1de) | Nov 17, 2021 |
| Lenovo        | ThinkPad T430 23445PU       | [e5fe64db56](https://linux-hardware.org/?probe=e5fe64db56) | Nov 16, 2021 |
| Toshiba       | Satellite C655D             | [cd8abc5170](https://linux-hardware.org/?probe=cd8abc5170) | Nov 16, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | [bfef77542f](https://linux-hardware.org/?probe=bfef77542f) | Nov 15, 2021 |
| Samsung       | 900X3C/900X3D/900X4C/900... | [76b69deb69](https://linux-hardware.org/?probe=76b69deb69) | Nov 14, 2021 |
| ASUSTek       | Vivobook_ASUSLaptop M350... | [3a3f503917](https://linux-hardware.org/?probe=3a3f503917) | Nov 14, 2021 |
| HP            | Notebook                    | [226dc7dc39](https://linux-hardware.org/?probe=226dc7dc39) | Nov 12, 2021 |
| HP            | Notebook                    | [c03f407f50](https://linux-hardware.org/?probe=c03f407f50) | Nov 12, 2021 |
| HP            | Notebook                    | [a2bae8d4b8](https://linux-hardware.org/?probe=a2bae8d4b8) | Nov 12, 2021 |
| HP            | Notebook                    | [87dec3cf7c](https://linux-hardware.org/?probe=87dec3cf7c) | Nov 12, 2021 |
| HP            | EliteBook 2560p             | [e3997c3bcb](https://linux-hardware.org/?probe=e3997c3bcb) | Nov 12, 2021 |
| Dell          | Inspiron 15-3567            | [e8879e98df](https://linux-hardware.org/?probe=e8879e98df) | Nov 12, 2021 |
| Google        | Kindred                     | [0046ef8942](https://linux-hardware.org/?probe=0046ef8942) | Nov 12, 2021 |
| Google        | Kindred                     | [9d72c8972c](https://linux-hardware.org/?probe=9d72c8972c) | Nov 12, 2021 |
| Acer          | Aspire 4830T                | [9ae2c69b2a](https://linux-hardware.org/?probe=9ae2c69b2a) | Nov 12, 2021 |
| Dell          | Precision M6700             | [9bf18c23c6](https://linux-hardware.org/?probe=9bf18c23c6) | Nov 12, 2021 |
| Notebook      | N85_N87HCHNHZ               | [32988fae95](https://linux-hardware.org/?probe=32988fae95) | Nov 11, 2021 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [c948868090](https://linux-hardware.org/?probe=c948868090) | Nov 11, 2021 |
| Dell          | Inspiron 1750               | [6ffff20ec8](https://linux-hardware.org/?probe=6ffff20ec8) | Nov 11, 2021 |
| Sony          | SVF14211CLB                 | [7c0dacdd54](https://linux-hardware.org/?probe=7c0dacdd54) | Nov 10, 2021 |
| HUAWEI        | BOHB-WAX9                   | [3b1f90f3ab](https://linux-hardware.org/?probe=3b1f90f3ab) | Nov 10, 2021 |
| HUAWEI        | BOHB-WAX9                   | [3858faa240](https://linux-hardware.org/?probe=3858faa240) | Nov 10, 2021 |
| Sony          | SVF14211CLB                 | [fdfd650fcc](https://linux-hardware.org/?probe=fdfd650fcc) | Nov 10, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [94da614270](https://linux-hardware.org/?probe=94da614270) | Nov 10, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6505        | [72dd15e9c5](https://linux-hardware.org/?probe=72dd15e9c5) | Nov 10, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [0d017f9835](https://linux-hardware.org/?probe=0d017f9835) | Nov 10, 2021 |
| ASUSTek       | U46E                        | [d52a43c7fd](https://linux-hardware.org/?probe=d52a43c7fd) | Nov 10, 2021 |
| Dell          | Latitude 3440               | [eb76b9d1cf](https://linux-hardware.org/?probe=eb76b9d1cf) | Nov 09, 2021 |
| HP            | Pavilion dv6                | [605479abf7](https://linux-hardware.org/?probe=605479abf7) | Nov 08, 2021 |
| HP            | Pavilion dv6                | [b7a410c2e6](https://linux-hardware.org/?probe=b7a410c2e6) | Nov 08, 2021 |
| MSI           | GF63 Thin 9SC               | [d85e7a0ad3](https://linux-hardware.org/?probe=d85e7a0ad3) | Nov 07, 2021 |
| Dell          | Latitude E5420              | [b53c6bd6d2](https://linux-hardware.org/?probe=b53c6bd6d2) | Nov 07, 2021 |
| Acer          | Swift SF314-56G             | [bf298c7d2d](https://linux-hardware.org/?probe=bf298c7d2d) | Nov 07, 2021 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [520a472266](https://linux-hardware.org/?probe=520a472266) | Nov 07, 2021 |
| HP            | Compaq 8510p                | [ddecc261a1](https://linux-hardware.org/?probe=ddecc261a1) | Nov 07, 2021 |
| HP            | Compaq 8510p                | [c2434c1c08](https://linux-hardware.org/?probe=c2434c1c08) | Nov 07, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [a0d13572a5](https://linux-hardware.org/?probe=a0d13572a5) | Nov 06, 2021 |
| HP            | Laptop 15-bw0xx             | [746f64d20b](https://linux-hardware.org/?probe=746f64d20b) | Nov 06, 2021 |
| HP            | Laptop 15-bw0xx             | [245941966f](https://linux-hardware.org/?probe=245941966f) | Nov 06, 2021 |
| Sony          | SVE1713D1EW                 | [64fd6b328f](https://linux-hardware.org/?probe=64fd6b328f) | Nov 06, 2021 |
| Sony          | SVE1713D1EW                 | [45609f28be](https://linux-hardware.org/?probe=45609f28be) | Nov 06, 2021 |
| HP            | Compaq 6710b (KE121ET#AB... | [5d577f71a4](https://linux-hardware.org/?probe=5d577f71a4) | Nov 06, 2021 |
| HP            | Compaq 6710b (KE121ET#AB... | [c37780e9ad](https://linux-hardware.org/?probe=c37780e9ad) | Nov 06, 2021 |
| ASUSTek       | K53TA                       | [e924b214bc](https://linux-hardware.org/?probe=e924b214bc) | Nov 06, 2021 |
| Acer          | Aspire ES1-521              | [5ef4af5924](https://linux-hardware.org/?probe=5ef4af5924) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [73b5ea9e0b](https://linux-hardware.org/?probe=73b5ea9e0b) | Nov 06, 2021 |
| HP            | ProBook 450 G4              | [a96a96d455](https://linux-hardware.org/?probe=a96a96d455) | Nov 05, 2021 |
| ASUSTek       | K45A                        | [f9bc7efe7b](https://linux-hardware.org/?probe=f9bc7efe7b) | Nov 05, 2021 |
| ASUSTek       | K45A                        | [096deec12d](https://linux-hardware.org/?probe=096deec12d) | Nov 05, 2021 |
| Sony          | VPCEG23EL                   | [cc967c03fb](https://linux-hardware.org/?probe=cc967c03fb) | Nov 05, 2021 |
| Acer          | Swift SF314-54              | [b506625dc2](https://linux-hardware.org/?probe=b506625dc2) | Nov 05, 2021 |
| ASUSTek       | X751NV                      | [ecf08805fe](https://linux-hardware.org/?probe=ecf08805fe) | Nov 03, 2021 |
| Dell          | Precision M6700             | [1865ed7cca](https://linux-hardware.org/?probe=1865ed7cca) | Nov 03, 2021 |
| Dell          | Latitude 5490               | [c5c1f555f1](https://linux-hardware.org/?probe=c5c1f555f1) | Nov 03, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | [9e7a883a59](https://linux-hardware.org/?probe=9e7a883a59) | Nov 03, 2021 |
| HP            | Notebook                    | [ee3bc3deef](https://linux-hardware.org/?probe=ee3bc3deef) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [3acc230d6a](https://linux-hardware.org/?probe=3acc230d6a) | Nov 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c88adaac6e](https://linux-hardware.org/?probe=c88adaac6e) | Nov 02, 2021 |
| Lenovo        | ThinkPad T430 2349ED5       | [0697993e7c](https://linux-hardware.org/?probe=0697993e7c) | Nov 02, 2021 |
| Lenovo        | IdeaPad Z580                | [0f9c8eb860](https://linux-hardware.org/?probe=0f9c8eb860) | Nov 02, 2021 |
| Toshiba       | Satellite C870-1C2          | [7e5a2d91f8](https://linux-hardware.org/?probe=7e5a2d91f8) | Nov 02, 2021 |
| HP            | ProBook 440 G4              | [695b9a4e0c](https://linux-hardware.org/?probe=695b9a4e0c) | Nov 01, 2021 |
| HP            | ProBook 440 G4              | [4bba4734e8](https://linux-hardware.org/?probe=4bba4734e8) | Nov 01, 2021 |
| Dell          | XPS 15 9510                 | [9ad082f18e](https://linux-hardware.org/?probe=9ad082f18e) | Nov 01, 2021 |
| ASUSTek       | K52Jc                       | [dfb687f14d](https://linux-hardware.org/?probe=dfb687f14d) | Nov 01, 2021 |
| HP            | 255 G8 Notebook PC          | [600b7b9957](https://linux-hardware.org/?probe=600b7b9957) | Nov 01, 2021 |
| Acer          | Aspire E1-522               | [56b475a93d](https://linux-hardware.org/?probe=56b475a93d) | Nov 01, 2021 |
| Toshiba       | Satellite Pro T110          | [3ae7a19459](https://linux-hardware.org/?probe=3ae7a19459) | Oct 31, 2021 |
| ASUSTek       | N61Ja                       | [e3fc4e0622](https://linux-hardware.org/?probe=e3fc4e0622) | Oct 31, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [83d642714b](https://linux-hardware.org/?probe=83d642714b) | Oct 31, 2021 |
| Apple         | MacBookPro11,2              | [eabb3946ad](https://linux-hardware.org/?probe=eabb3946ad) | Oct 31, 2021 |
| ASUSTek       | N61Ja                       | [3861fce83e](https://linux-hardware.org/?probe=3861fce83e) | Oct 31, 2021 |
| Apple         | MacBookPro11,2              | [2388e68622](https://linux-hardware.org/?probe=2388e68622) | Oct 31, 2021 |
| Dell          | Inspiron 7720               | [9f298535a5](https://linux-hardware.org/?probe=9f298535a5) | Oct 31, 2021 |
| HP            | 255 G8 Notebook PC          | [cb9c15cf6f](https://linux-hardware.org/?probe=cb9c15cf6f) | Oct 30, 2021 |
| Dell          | Latitude E6500              | [e475348b1e](https://linux-hardware.org/?probe=e475348b1e) | Oct 30, 2021 |
| MECER         | Z140C+Home                  | [2fbf6f153b](https://linux-hardware.org/?probe=2fbf6f153b) | Oct 30, 2021 |
| HP            | Pavilion Notebook           | [85a55f5c3c](https://linux-hardware.org/?probe=85a55f5c3c) | Oct 30, 2021 |
| Lenovo        | IdeaPad Z580                | [16ebdc4388](https://linux-hardware.org/?probe=16ebdc4388) | Oct 30, 2021 |
| Lenovo        | IdeaPad Z580                | [6260be6de5](https://linux-hardware.org/?probe=6260be6de5) | Oct 30, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [af0a995721](https://linux-hardware.org/?probe=af0a995721) | Oct 30, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [88286c36e9](https://linux-hardware.org/?probe=88286c36e9) | Oct 29, 2021 |
| Acer          | Aspire A315-21              | [f5f4e2457b](https://linux-hardware.org/?probe=f5f4e2457b) | Oct 29, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [c74557d180](https://linux-hardware.org/?probe=c74557d180) | Oct 29, 2021 |
| Acer          | Aspire A315-21              | [35b5fcb787](https://linux-hardware.org/?probe=35b5fcb787) | Oct 28, 2021 |
| ASUSTek       | N71Jv                       | [29e3747e17](https://linux-hardware.org/?probe=29e3747e17) | Oct 28, 2021 |
| ASUSTek       | X750JB                      | [90fd9f38fc](https://linux-hardware.org/?probe=90fd9f38fc) | Oct 27, 2021 |
| Lenovo        | G570 4334                   | [cc07ebf9b6](https://linux-hardware.org/?probe=cc07ebf9b6) | Oct 27, 2021 |
| HP            | EliteBook 8440p             | [f527983cc9](https://linux-hardware.org/?probe=f527983cc9) | Oct 27, 2021 |
| Toshiba       | PORTEGE Z20t-C              | [ed1722174a](https://linux-hardware.org/?probe=ed1722174a) | Oct 27, 2021 |
| Lenovo        | Legion Y920-17IKB Laptop... | [830d4c9d9d](https://linux-hardware.org/?probe=830d4c9d9d) | Oct 26, 2021 |
| Acer          | Aspire 5737Z                | [9bbf3befab](https://linux-hardware.org/?probe=9bbf3befab) | Oct 26, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | [4104e265ea](https://linux-hardware.org/?probe=4104e265ea) | Oct 26, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [3da20846f5](https://linux-hardware.org/?probe=3da20846f5) | Oct 26, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [2d19155e7f](https://linux-hardware.org/?probe=2d19155e7f) | Oct 26, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [ed4e9d1a03](https://linux-hardware.org/?probe=ed4e9d1a03) | Oct 26, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [f5b1e904b7](https://linux-hardware.org/?probe=f5b1e904b7) | Oct 26, 2021 |
| HP            | ProBook 445 G7              | [87b3274937](https://linux-hardware.org/?probe=87b3274937) | Oct 26, 2021 |
| HP            | Stream Notebook PC 11       | [c240a088a9](https://linux-hardware.org/?probe=c240a088a9) | Oct 26, 2021 |
| HP            | ENVY m7 Notebook            | [235fa5cacd](https://linux-hardware.org/?probe=235fa5cacd) | Oct 25, 2021 |
| Dell          | Latitude E6430              | [fa4d12994d](https://linux-hardware.org/?probe=fa4d12994d) | Oct 25, 2021 |
| Schenker      | VIA 15 Pro                  | [7242436545](https://linux-hardware.org/?probe=7242436545) | Oct 24, 2021 |
| Toshiba       | Satellite C70-B             | [a17b7c3888](https://linux-hardware.org/?probe=a17b7c3888) | Oct 24, 2021 |
| Thomson       | N17C512                     | [20abb09d3a](https://linux-hardware.org/?probe=20abb09d3a) | Oct 24, 2021 |
| Notebook      | X170SM                      | [2054d0dee6](https://linux-hardware.org/?probe=2054d0dee6) | Oct 24, 2021 |
| Notebook      | X170SM                      | [f704af17a3](https://linux-hardware.org/?probe=f704af17a3) | Oct 24, 2021 |
| Dell          | Latitude D630               | [1cfebe8169](https://linux-hardware.org/?probe=1cfebe8169) | Oct 23, 2021 |
| Dell          | Latitude E6410              | [f4cdc942dc](https://linux-hardware.org/?probe=f4cdc942dc) | Oct 23, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [fe4aa7e54d](https://linux-hardware.org/?probe=fe4aa7e54d) | Oct 23, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [db85bd77fc](https://linux-hardware.org/?probe=db85bd77fc) | Oct 23, 2021 |
| HP            | ProBook 6550b               | [4db59c8489](https://linux-hardware.org/?probe=4db59c8489) | Oct 23, 2021 |
| Acer          | Aspire ES1-521              | [c6582bba7d](https://linux-hardware.org/?probe=c6582bba7d) | Oct 23, 2021 |
| Acer          | Aspire ES1-521              | [248ab157b8](https://linux-hardware.org/?probe=248ab157b8) | Oct 23, 2021 |
| HP            | Notebook                    | [11013f1334](https://linux-hardware.org/?probe=11013f1334) | Oct 22, 2021 |
| Google        | Kindred                     | [675265477a](https://linux-hardware.org/?probe=675265477a) | Oct 22, 2021 |
| HP            | 255 G4 Notebook PC          | [e7e49e8cc0](https://linux-hardware.org/?probe=e7e49e8cc0) | Oct 22, 2021 |
| Dell          | Latitude E7470              | [061c5e449c](https://linux-hardware.org/?probe=061c5e449c) | Oct 22, 2021 |
| MSI           | Modern 14 B10MW             | [ae43e74753](https://linux-hardware.org/?probe=ae43e74753) | Oct 21, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | [8668abcc62](https://linux-hardware.org/?probe=8668abcc62) | Oct 21, 2021 |
| HP            | Compaq 8710p (GC102EA#AB... | [18cf55aa72](https://linux-hardware.org/?probe=18cf55aa72) | Oct 21, 2021 |
| Toshiba       | Satellite L755              | [985ff9ba03](https://linux-hardware.org/?probe=985ff9ba03) | Oct 21, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [63c9d05f24](https://linux-hardware.org/?probe=63c9d05f24) | Oct 20, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [85036968bb](https://linux-hardware.org/?probe=85036968bb) | Oct 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3F30... | [6d2d97674c](https://linux-hardware.org/?probe=6d2d97674c) | Oct 19, 2021 |
| Lenovo        | ThinkPad T460s 20FAS3F30... | [facdd98487](https://linux-hardware.org/?probe=facdd98487) | Oct 19, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [961f066acf](https://linux-hardware.org/?probe=961f066acf) | Oct 19, 2021 |
| Dell          | Latitude E7470              | [fdc6203a6e](https://linux-hardware.org/?probe=fdc6203a6e) | Oct 18, 2021 |
| Dell          | Latitude E6420              | [027441e6d4](https://linux-hardware.org/?probe=027441e6d4) | Oct 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6210b749a1](https://linux-hardware.org/?probe=6210b749a1) | Oct 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dbf1e020b0](https://linux-hardware.org/?probe=dbf1e020b0) | Oct 18, 2021 |
| Dell          | Inspiron 3521               | [2ffe8489e1](https://linux-hardware.org/?probe=2ffe8489e1) | Oct 18, 2021 |
| Toshiba       | Satellite C870-1C2          | [076883700d](https://linux-hardware.org/?probe=076883700d) | Oct 17, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [10f8e5f5cf](https://linux-hardware.org/?probe=10f8e5f5cf) | Oct 17, 2021 |
| Acer          | Aspire R3-131T              | [014464c088](https://linux-hardware.org/?probe=014464c088) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [15ce74dcd6](https://linux-hardware.org/?probe=15ce74dcd6) | Oct 17, 2021 |
| Fujitsu       | LIFEBOOK AH530              | [97c3495c65](https://linux-hardware.org/?probe=97c3495c65) | Oct 17, 2021 |
| Unknown       | CherryTrail                 | [01d095b201](https://linux-hardware.org/?probe=01d095b201) | Oct 17, 2021 |
| Acer          | Aspire E5-571               | [76090a2652](https://linux-hardware.org/?probe=76090a2652) | Oct 16, 2021 |
| HP            | Stream Laptop 14-ax0XX      | [ff6de8e062](https://linux-hardware.org/?probe=ff6de8e062) | Oct 16, 2021 |
| Lenovo        | G50-70 20351                | [d0d0d99be6](https://linux-hardware.org/?probe=d0d0d99be6) | Oct 16, 2021 |
| Lenovo        | Flex 2-14 20404             | [ef609865b5](https://linux-hardware.org/?probe=ef609865b5) | Oct 16, 2021 |
| Lenovo        | Flex 2-14 20404             | [4fc5c2f99f](https://linux-hardware.org/?probe=4fc5c2f99f) | Oct 16, 2021 |
| Dell          | Latitude E7440              | [cfe53904bc](https://linux-hardware.org/?probe=cfe53904bc) | Oct 16, 2021 |
| Unknown       | Unknown                     | [3233e1293c](https://linux-hardware.org/?probe=3233e1293c) | Oct 15, 2021 |
| Acer          | Aspire E5-576G              | [6f17f5d2c0](https://linux-hardware.org/?probe=6f17f5d2c0) | Oct 15, 2021 |
| HP            | Pavilion dv7                | [2d35a2ee5d](https://linux-hardware.org/?probe=2d35a2ee5d) | Oct 15, 2021 |
| HP            | ENVY m7 Notebook            | [f0af05f6f9](https://linux-hardware.org/?probe=f0af05f6f9) | Oct 15, 2021 |
| Unknown       | Unknown                     | [ddc6d80716](https://linux-hardware.org/?probe=ddc6d80716) | Oct 15, 2021 |
| Toshiba       | Satellite L755              | [fdaa2dd77e](https://linux-hardware.org/?probe=fdaa2dd77e) | Oct 14, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6edbff3019](https://linux-hardware.org/?probe=6edbff3019) | Oct 14, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [3f90ae6d67](https://linux-hardware.org/?probe=3f90ae6d67) | Oct 14, 2021 |
| Dell          | Latitude E6420              | [14b08ab14d](https://linux-hardware.org/?probe=14b08ab14d) | Oct 14, 2021 |
| ASUSTek       | GL702VI                     | [c342d6fdc1](https://linux-hardware.org/?probe=c342d6fdc1) | Oct 14, 2021 |
| HP            | 15                          | [5534f9e3fc](https://linux-hardware.org/?probe=5534f9e3fc) | Oct 14, 2021 |
| Acer          | Swift SF314-59              | [2cd9b13bb1](https://linux-hardware.org/?probe=2cd9b13bb1) | Oct 14, 2021 |
| HP            | 15                          | [bfc196e22b](https://linux-hardware.org/?probe=bfc196e22b) | Oct 13, 2021 |
| ASUSTek       | X501A1                      | [0494cb6f11](https://linux-hardware.org/?probe=0494cb6f11) | Oct 13, 2021 |
| HP            | Notebook                    | [58c6628ba2](https://linux-hardware.org/?probe=58c6628ba2) | Oct 12, 2021 |
| HP            | Notebook                    | [f3f5e6256d](https://linux-hardware.org/?probe=f3f5e6256d) | Oct 12, 2021 |
| Dell          | Inspiron 5721               | [a13d0383b6](https://linux-hardware.org/?probe=a13d0383b6) | Oct 12, 2021 |
| Dell          | Inspiron 5721               | [686377ccd0](https://linux-hardware.org/?probe=686377ccd0) | Oct 12, 2021 |
| HP            | EliteBook 840 G1            | [9bb8ba744e](https://linux-hardware.org/?probe=9bb8ba744e) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | [01a3f25bec](https://linux-hardware.org/?probe=01a3f25bec) | Oct 12, 2021 |
| Apple         | MacBookPro8,1               | [d8de6fc953](https://linux-hardware.org/?probe=d8de6fc953) | Oct 12, 2021 |
| Giani Limi... | ENY1158M                    | [1f9a85e980](https://linux-hardware.org/?probe=1f9a85e980) | Oct 11, 2021 |
| Giani Limi... | ENY1158M                    | [4516242881](https://linux-hardware.org/?probe=4516242881) | Oct 11, 2021 |
| Lenovo        | ThinkPad X220 4286CTO       | [471414140c](https://linux-hardware.org/?probe=471414140c) | Oct 11, 2021 |
| Unknown       | Z3735F-T02 V1.2             | [6ef4e9edf6](https://linux-hardware.org/?probe=6ef4e9edf6) | Oct 11, 2021 |
| Dell          | Inspiron 3537               | [9614492711](https://linux-hardware.org/?probe=9614492711) | Oct 11, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [f5147cd609](https://linux-hardware.org/?probe=f5147cd609) | Oct 10, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | [fc28e4f7f8](https://linux-hardware.org/?probe=fc28e4f7f8) | Oct 10, 2021 |
| HP            | x2 210                      | [ccf01919ab](https://linux-hardware.org/?probe=ccf01919ab) | Oct 09, 2021 |
| HP            | x2 210                      | [a35274c0a7](https://linux-hardware.org/?probe=a35274c0a7) | Oct 09, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [e1a73cbf10](https://linux-hardware.org/?probe=e1a73cbf10) | Oct 09, 2021 |
| Samsung       | 700Z3C/700Z5C               | [007ba2bac1](https://linux-hardware.org/?probe=007ba2bac1) | Oct 09, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [63e608b4af](https://linux-hardware.org/?probe=63e608b4af) | Oct 09, 2021 |
| Acer          | Aspire E5-571               | [e988105956](https://linux-hardware.org/?probe=e988105956) | Oct 09, 2021 |
| ASUSTek       | X555YA                      | [7bbcc6c5af](https://linux-hardware.org/?probe=7bbcc6c5af) | Oct 09, 2021 |
| HP            | Laptop 17z-cp000            | [db7c1566db](https://linux-hardware.org/?probe=db7c1566db) | Oct 09, 2021 |
| HP            | ENVY dv6                    | [21a3477c3d](https://linux-hardware.org/?probe=21a3477c3d) | Oct 08, 2021 |
| MSI           | GE66 Raider 10UH            | [43c72c2ff3](https://linux-hardware.org/?probe=43c72c2ff3) | Oct 08, 2021 |
| HP            | Unknown                     | [c65be179d9](https://linux-hardware.org/?probe=c65be179d9) | Oct 08, 2021 |
| Acer          | TravelMate P259-MG          | [c62543cf86](https://linux-hardware.org/?probe=c62543cf86) | Oct 07, 2021 |
| HP            | Laptop 15s-fq1xxx           | [b81ab61049](https://linux-hardware.org/?probe=b81ab61049) | Oct 07, 2021 |
| HP            | Pavilion dv7                | [e139664dbf](https://linux-hardware.org/?probe=e139664dbf) | Oct 07, 2021 |
| Lenovo        | Z50-75 80EC                 | [2550a17ad0](https://linux-hardware.org/?probe=2550a17ad0) | Oct 07, 2021 |
| Star Labs     | LabTop                      | [711f2b9e6d](https://linux-hardware.org/?probe=711f2b9e6d) | Oct 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [ae113c0df0](https://linux-hardware.org/?probe=ae113c0df0) | Oct 06, 2021 |
| Dell          | Latitude E5400              | [6878f58676](https://linux-hardware.org/?probe=6878f58676) | Oct 06, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a87e581c64](https://linux-hardware.org/?probe=a87e581c64) | Oct 06, 2021 |
| Dell          | Latitude E5400              | [b69897eca3](https://linux-hardware.org/?probe=b69897eca3) | Oct 06, 2021 |
| Dell          | Latitude E5530 non-vPro     | [afe8fca994](https://linux-hardware.org/?probe=afe8fca994) | Oct 06, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [dc9074514c](https://linux-hardware.org/?probe=dc9074514c) | Oct 06, 2021 |
| ASUSTek       | X550LB                      | [d96d114426](https://linux-hardware.org/?probe=d96d114426) | Oct 06, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [6717c35dc9](https://linux-hardware.org/?probe=6717c35dc9) | Oct 05, 2021 |
| Dell          | Inspiron 3542               | [f67c2f8d32](https://linux-hardware.org/?probe=f67c2f8d32) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | [6a5bc4355e](https://linux-hardware.org/?probe=6a5bc4355e) | Oct 05, 2021 |
| HP            | Notebook                    | [88b07c9f57](https://linux-hardware.org/?probe=88b07c9f57) | Oct 05, 2021 |
| HP            | Notebook                    | [28c9b584b1](https://linux-hardware.org/?probe=28c9b584b1) | Oct 05, 2021 |
| Dell          | Inspiron 3521               | [9e18ebff31](https://linux-hardware.org/?probe=9e18ebff31) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | [ccc6db1c41](https://linux-hardware.org/?probe=ccc6db1c41) | Oct 05, 2021 |
| Lenovo        | ThinkPad L470 20J5A00FLM    | [55ec005acb](https://linux-hardware.org/?probe=55ec005acb) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | [4b9f0ceb64](https://linux-hardware.org/?probe=4b9f0ceb64) | Oct 05, 2021 |
| HP            | ProBook 430 G1              | [01109c5fde](https://linux-hardware.org/?probe=01109c5fde) | Oct 04, 2021 |
| Toshiba       | Satellite C70-B             | [2d4b467fdc](https://linux-hardware.org/?probe=2d4b467fdc) | Oct 04, 2021 |
| Dell          | Latitude E5570              | [bfc3702626](https://linux-hardware.org/?probe=bfc3702626) | Oct 04, 2021 |
| HP            | EliteBook 8440p             | [0890806446](https://linux-hardware.org/?probe=0890806446) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [6d94d45cf0](https://linux-hardware.org/?probe=6d94d45cf0) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [ab6b537db8](https://linux-hardware.org/?probe=ab6b537db8) | Oct 04, 2021 |
| HP            | Notebook                    | [c405133048](https://linux-hardware.org/?probe=c405133048) | Oct 03, 2021 |
| Dell          | Latitude 7390               | [50080eb85e](https://linux-hardware.org/?probe=50080eb85e) | Oct 03, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [a2ee189c63](https://linux-hardware.org/?probe=a2ee189c63) | Oct 03, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [a4f833babc](https://linux-hardware.org/?probe=a4f833babc) | Oct 03, 2021 |
| HP            | Pavilion dv7                | [30875abc8f](https://linux-hardware.org/?probe=30875abc8f) | Oct 03, 2021 |
| Dell          | Inspiron 7773               | [2713f21dd7](https://linux-hardware.org/?probe=2713f21dd7) | Oct 03, 2021 |
| Dell          | Latitude E5400              | [ffc2d5a399](https://linux-hardware.org/?probe=ffc2d5a399) | Oct 03, 2021 |
| Toshiba       | Satellite L455D             | [9413906eaa](https://linux-hardware.org/?probe=9413906eaa) | Oct 03, 2021 |
| Dell          | Inspiron 3542               | [e3247b14fa](https://linux-hardware.org/?probe=e3247b14fa) | Oct 02, 2021 |
| Dell          | Latitude E5400              | [529e29fb9d](https://linux-hardware.org/?probe=529e29fb9d) | Oct 02, 2021 |
| Toshiba       | Satellite Pro T110          | [3bd8210e7e](https://linux-hardware.org/?probe=3bd8210e7e) | Oct 01, 2021 |
| HP            | Laptop 15-bw0xx             | [642e96374e](https://linux-hardware.org/?probe=642e96374e) | Oct 01, 2021 |
| Dell          | Latitude E6520              | [e1bf1df5ae](https://linux-hardware.org/?probe=e1bf1df5ae) | Oct 01, 2021 |
| Unknown       | Unknown                     | [f92fca6d48](https://linux-hardware.org/?probe=f92fca6d48) | Oct 01, 2021 |
| Acer          | Nitro AN515-44              | [a7a50b0dbf](https://linux-hardware.org/?probe=a7a50b0dbf) | Oct 01, 2021 |
| HP            | Pavilion dv7                | [590a48aff9](https://linux-hardware.org/?probe=590a48aff9) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | [359171629f](https://linux-hardware.org/?probe=359171629f) | Sep 30, 2021 |
| Apple         | MacBook5,2                  | [4e125287e4](https://linux-hardware.org/?probe=4e125287e4) | Sep 30, 2021 |
| HP            | EliteBook 830 G5            | [d0c34db7d4](https://linux-hardware.org/?probe=d0c34db7d4) | Sep 29, 2021 |
| HP            | ENVY 15                     | [4b949c1a1b](https://linux-hardware.org/?probe=4b949c1a1b) | Sep 29, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [3688fae067](https://linux-hardware.org/?probe=3688fae067) | Sep 29, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [3befe3f6e3](https://linux-hardware.org/?probe=3befe3f6e3) | Sep 29, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [fb88fc18f4](https://linux-hardware.org/?probe=fb88fc18f4) | Sep 29, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [cc9cc9e925](https://linux-hardware.org/?probe=cc9cc9e925) | Sep 28, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [6cf7de2b6b](https://linux-hardware.org/?probe=6cf7de2b6b) | Sep 28, 2021 |
| HP            | Pavilion dv7                | [7e0b76f736](https://linux-hardware.org/?probe=7e0b76f736) | Sep 28, 2021 |
| Acer          | Aspire 4830T                | [d36367eb22](https://linux-hardware.org/?probe=d36367eb22) | Sep 28, 2021 |
| Acer          | Aspire A315-56              | [3fc47b2c92](https://linux-hardware.org/?probe=3fc47b2c92) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [d573d0691e](https://linux-hardware.org/?probe=d573d0691e) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [f322cce11b](https://linux-hardware.org/?probe=f322cce11b) | Sep 27, 2021 |
| Acer          | Aspire ES1-512              | [6aa9666f2c](https://linux-hardware.org/?probe=6aa9666f2c) | Sep 27, 2021 |
| Dell          | Latitude E5570              | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| Toshiba       | PORTEGE R700                | [b7b8adedee](https://linux-hardware.org/?probe=b7b8adedee) | Sep 27, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [00b95678dd](https://linux-hardware.org/?probe=00b95678dd) | Sep 27, 2021 |
| ASUSTek       | X405UA                      | [3a78f7edf5](https://linux-hardware.org/?probe=3a78f7edf5) | Sep 26, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [a49a61fb7d](https://linux-hardware.org/?probe=a49a61fb7d) | Sep 26, 2021 |
| Lenovo        | ThinkPad T520 4242W19       | [0bbb8d9004](https://linux-hardware.org/?probe=0bbb8d9004) | Sep 26, 2021 |
| Acer          | Aspire 5738                 | [3a72e534d3](https://linux-hardware.org/?probe=3a72e534d3) | Sep 26, 2021 |
| Acer          | Aspire V3-571G              | [8bc152aa27](https://linux-hardware.org/?probe=8bc152aa27) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [9267f59e81](https://linux-hardware.org/?probe=9267f59e81) | Sep 25, 2021 |
| HP            | Pavilion Laptop 15z-cw10... | [5404d5874a](https://linux-hardware.org/?probe=5404d5874a) | Sep 25, 2021 |
| Apple         | MacBook3,1                  | [67212f51d0](https://linux-hardware.org/?probe=67212f51d0) | Sep 25, 2021 |
| Dell          | Latitude E6220              | [08e1d2f464](https://linux-hardware.org/?probe=08e1d2f464) | Sep 25, 2021 |
| Acer          | Aspire V3-571G              | [9d3daebd14](https://linux-hardware.org/?probe=9d3daebd14) | Sep 25, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [6b6f1c017d](https://linux-hardware.org/?probe=6b6f1c017d) | Sep 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [953ed13df8](https://linux-hardware.org/?probe=953ed13df8) | Sep 24, 2021 |
| Toshiba       | PORTEGE Z30-A               | [a65f8af3ac](https://linux-hardware.org/?probe=a65f8af3ac) | Sep 24, 2021 |
| Apple         | MacBookPro14,1              | [2d0d6ceff3](https://linux-hardware.org/?probe=2d0d6ceff3) | Sep 24, 2021 |
| KOGAN         | KAL11C250SB                 | [b76a44f6d5](https://linux-hardware.org/?probe=b76a44f6d5) | Sep 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [1af2027db5](https://linux-hardware.org/?probe=1af2027db5) | Sep 24, 2021 |
| Dell          | Latitude E6430              | [5e66bde0c9](https://linux-hardware.org/?probe=5e66bde0c9) | Sep 24, 2021 |
| ASUSTek       | E403NA                      | [382c1a7b47](https://linux-hardware.org/?probe=382c1a7b47) | Sep 24, 2021 |
| HP            | Presario V6000 (GM018UA#... | [944d6af89a](https://linux-hardware.org/?probe=944d6af89a) | Sep 23, 2021 |
| MSI           | Modern 15 A11M              | [fe99af6254](https://linux-hardware.org/?probe=fe99af6254) | Sep 23, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [25d01e8fc6](https://linux-hardware.org/?probe=25d01e8fc6) | Sep 23, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [4d2aa790e0](https://linux-hardware.org/?probe=4d2aa790e0) | Sep 23, 2021 |
| Apple         | MacBookPro9,2               | [effa7b0365](https://linux-hardware.org/?probe=effa7b0365) | Sep 22, 2021 |
| HP            | Notebook                    | [91d439a6a4](https://linux-hardware.org/?probe=91d439a6a4) | Sep 22, 2021 |
| Dynabook      | PORTEGE A30-E               | [93fd738472](https://linux-hardware.org/?probe=93fd738472) | Sep 21, 2021 |
| Dynabook      | PORTEGE A30-E               | [0ec5acd020](https://linux-hardware.org/?probe=0ec5acd020) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [a43f2dc4bf](https://linux-hardware.org/?probe=a43f2dc4bf) | Sep 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [069c0cafd0](https://linux-hardware.org/?probe=069c0cafd0) | Sep 21, 2021 |
| Toshiba       | Satellite L755              | [10baeecbf5](https://linux-hardware.org/?probe=10baeecbf5) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | [36c622eabc](https://linux-hardware.org/?probe=36c622eabc) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | [0ce8da0fe0](https://linux-hardware.org/?probe=0ce8da0fe0) | Sep 21, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [699803b74c](https://linux-hardware.org/?probe=699803b74c) | Sep 21, 2021 |
| UNOWHY        | Y13G011S4EI                 | [70511c9675](https://linux-hardware.org/?probe=70511c9675) | Sep 21, 2021 |
| Lenovo        | G580                        | [d7e35103d9](https://linux-hardware.org/?probe=d7e35103d9) | Sep 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [91055c07be](https://linux-hardware.org/?probe=91055c07be) | Sep 20, 2021 |
| LG Electro... | C400-G.BC22P1               | [ae16407ef3](https://linux-hardware.org/?probe=ae16407ef3) | Sep 20, 2021 |
| Acer          | Aspire E1-532               | [b0407bdd1c](https://linux-hardware.org/?probe=b0407bdd1c) | Sep 20, 2021 |
| Acer          | Aspire 5738                 | [01bb66e2a1](https://linux-hardware.org/?probe=01bb66e2a1) | Sep 20, 2021 |
| TianBei       | TB-H7                       | [06300b96a7](https://linux-hardware.org/?probe=06300b96a7) | Sep 19, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | [d80cdfb094](https://linux-hardware.org/?probe=d80cdfb094) | Sep 19, 2021 |
| Toshiba       | Satellite C870-1C2          | [6129e531d9](https://linux-hardware.org/?probe=6129e531d9) | Sep 19, 2021 |
| Apple         | MacBookPro9,2               | [37f34b16c5](https://linux-hardware.org/?probe=37f34b16c5) | Sep 19, 2021 |
| Acer          | Aspire 4352                 | [3a9aedb538](https://linux-hardware.org/?probe=3a9aedb538) | Sep 19, 2021 |
| ASUSTek       | U31F                        | [908a7184ae](https://linux-hardware.org/?probe=908a7184ae) | Sep 19, 2021 |
| Dell          | XPS 13 9350                 | [4dda7e9a7e](https://linux-hardware.org/?probe=4dda7e9a7e) | Sep 18, 2021 |
| ASUSTek       | U31F                        | [7cf4ac39de](https://linux-hardware.org/?probe=7cf4ac39de) | Sep 18, 2021 |
| Dell          | System XPS L321X            | [2345076968](https://linux-hardware.org/?probe=2345076968) | Sep 18, 2021 |
| Dell          | Latitude E6430              | [2d96c4a645](https://linux-hardware.org/?probe=2d96c4a645) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | [42d68963c6](https://linux-hardware.org/?probe=42d68963c6) | Sep 17, 2021 |
| Dell          | Vostro 15-3568              | [50f90e7684](https://linux-hardware.org/?probe=50f90e7684) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | [73a4cd0692](https://linux-hardware.org/?probe=73a4cd0692) | Sep 17, 2021 |
| HP            | Unknown                     | [b0b3846ace](https://linux-hardware.org/?probe=b0b3846ace) | Sep 17, 2021 |
| Lenovo        | ThinkPad T520 42435GG       | [518209a322](https://linux-hardware.org/?probe=518209a322) | Sep 17, 2021 |
| Dell          | Latitude E5470              | [9a036a26a4](https://linux-hardware.org/?probe=9a036a26a4) | Sep 17, 2021 |
| HP            | Notebook                    | [6b2785c2e0](https://linux-hardware.org/?probe=6b2785c2e0) | Sep 17, 2021 |
| Dell          | Latitude E5500              | [286c99863b](https://linux-hardware.org/?probe=286c99863b) | Sep 16, 2021 |
| HP            | 245 G5 Notebook PC          | [ece740cf39](https://linux-hardware.org/?probe=ece740cf39) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | [04ba56c326](https://linux-hardware.org/?probe=04ba56c326) | Sep 16, 2021 |
| Toshiba       | Satellite L755              | [142e3e40c2](https://linux-hardware.org/?probe=142e3e40c2) | Sep 16, 2021 |
| Toshiba       | Satellite C75D-B            | [152dd3680d](https://linux-hardware.org/?probe=152dd3680d) | Sep 16, 2021 |
| Jumper        | EZpad .A002                 | [c62d842a68](https://linux-hardware.org/?probe=c62d842a68) | Sep 16, 2021 |
| Lenovo        | ThinkPad P50 20EN001EUS     | [6d381b570b](https://linux-hardware.org/?probe=6d381b570b) | Sep 15, 2021 |
| HP            | 255 G4 Notebook PC          | [c8a384ed00](https://linux-hardware.org/?probe=c8a384ed00) | Sep 15, 2021 |
| HP            | EliteBook 840 G5            | [68305a2ede](https://linux-hardware.org/?probe=68305a2ede) | Sep 15, 2021 |
| Dell          | Latitude E7440              | [803cfd7e73](https://linux-hardware.org/?probe=803cfd7e73) | Sep 15, 2021 |
| Dell          | Latitude E6520              | [1bd8b6a82f](https://linux-hardware.org/?probe=1bd8b6a82f) | Sep 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [983922cfbf](https://linux-hardware.org/?probe=983922cfbf) | Sep 15, 2021 |
| Acer          | Aspire 5733Z                | [6cfdfd04c6](https://linux-hardware.org/?probe=6cfdfd04c6) | Sep 14, 2021 |
| HP            | Notebook                    | [d6825ad86c](https://linux-hardware.org/?probe=d6825ad86c) | Sep 14, 2021 |
| Lenovo        | G50-80 80E5                 | [ef850713da](https://linux-hardware.org/?probe=ef850713da) | Sep 14, 2021 |
| Sony          | VGN-SR5                     | [199ae9a9dd](https://linux-hardware.org/?probe=199ae9a9dd) | Sep 14, 2021 |
| Dell          | Latitude E5470              | [032f256bab](https://linux-hardware.org/?probe=032f256bab) | Sep 14, 2021 |
| Sony          | VPCF215FX                   | [173d8636d4](https://linux-hardware.org/?probe=173d8636d4) | Sep 14, 2021 |
| HP            | EliteBook Folio 9470m       | [b054524aac](https://linux-hardware.org/?probe=b054524aac) | Sep 14, 2021 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [29d5b02719](https://linux-hardware.org/?probe=29d5b02719) | Sep 13, 2021 |
| HP            | Pavilion Notebook           | [864dde8a99](https://linux-hardware.org/?probe=864dde8a99) | Sep 13, 2021 |
| Toshiba       | Satellite C870-1C2          | [3818ff8f07](https://linux-hardware.org/?probe=3818ff8f07) | Sep 12, 2021 |
| HP            | Victus by HP Laptop 16-e... | [6a980ac620](https://linux-hardware.org/?probe=6a980ac620) | Sep 12, 2021 |
| Dell          | Latitude E6430              | [aff84b5ec1](https://linux-hardware.org/?probe=aff84b5ec1) | Sep 12, 2021 |
| Google        | Kindred                     | [c9ee8560b8](https://linux-hardware.org/?probe=c9ee8560b8) | Sep 12, 2021 |
| Dell          | XPS M1330                   | [404d33775d](https://linux-hardware.org/?probe=404d33775d) | Sep 12, 2021 |
| Dell          | Latitude E5500              | [1e20247950](https://linux-hardware.org/?probe=1e20247950) | Sep 12, 2021 |
| Dell          | XPS M1330                   | [3dcddbd59e](https://linux-hardware.org/?probe=3dcddbd59e) | Sep 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b565f4eee3](https://linux-hardware.org/?probe=b565f4eee3) | Sep 11, 2021 |
| HP            | Laptop 15-dy1xxx            | [728e0facd6](https://linux-hardware.org/?probe=728e0facd6) | Sep 11, 2021 |
| Acer          | Aspire 4830T                | [4e69ac73e4](https://linux-hardware.org/?probe=4e69ac73e4) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | [33fd6d8c8f](https://linux-hardware.org/?probe=33fd6d8c8f) | Sep 11, 2021 |
| ASUSTek       | N55SF                       | [fa33f94b27](https://linux-hardware.org/?probe=fa33f94b27) | Sep 11, 2021 |
| MSI           | GE75 Raider 8RF             | [350527f093](https://linux-hardware.org/?probe=350527f093) | Sep 10, 2021 |
| Toshiba       | Satellite Pro L450D         | [a15c916899](https://linux-hardware.org/?probe=a15c916899) | Sep 10, 2021 |
| Toshiba       | Satellite C850-1CP          | [8cec9884a8](https://linux-hardware.org/?probe=8cec9884a8) | Sep 10, 2021 |
| Unknown       | Unknown                     | [bbf81cb33e](https://linux-hardware.org/?probe=bbf81cb33e) | Sep 10, 2021 |
| Dell          | Latitude E5470              | [f6d8fa5367](https://linux-hardware.org/?probe=f6d8fa5367) | Sep 10, 2021 |
| Dell          | Latitude E5470              | [87b52d41c7](https://linux-hardware.org/?probe=87b52d41c7) | Sep 10, 2021 |
| HP            | Notebook                    | [24690d1b8b](https://linux-hardware.org/?probe=24690d1b8b) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | [38098784dd](https://linux-hardware.org/?probe=38098784dd) | Sep 09, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [53c03e65ce](https://linux-hardware.org/?probe=53c03e65ce) | Sep 09, 2021 |
| HP            | 255 G7 Notebook PC          | [6ab68f26ba](https://linux-hardware.org/?probe=6ab68f26ba) | Sep 09, 2021 |
| Dell          | Vostro 3580                 | [e480169372](https://linux-hardware.org/?probe=e480169372) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [c06b09d9c4](https://linux-hardware.org/?probe=c06b09d9c4) | Sep 09, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [87e79937c9](https://linux-hardware.org/?probe=87e79937c9) | Sep 09, 2021 |
| Lenovo        | IdeaPad 310 Touch-15IKB ... | [ccb4dc3d9a](https://linux-hardware.org/?probe=ccb4dc3d9a) | Sep 09, 2021 |
| Toshiba       | Satellite C75D-B            | [0f52ac751b](https://linux-hardware.org/?probe=0f52ac751b) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [97b34f8c7f](https://linux-hardware.org/?probe=97b34f8c7f) | Sep 08, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [8404b1fc92](https://linux-hardware.org/?probe=8404b1fc92) | Sep 08, 2021 |
| Lenovo        | ThinkPad E14 20RAS1Q800     | [a4d93ee5d2](https://linux-hardware.org/?probe=a4d93ee5d2) | Sep 08, 2021 |
| HP            | EliteBook 8560p             | [6bff88fb9e](https://linux-hardware.org/?probe=6bff88fb9e) | Sep 08, 2021 |
| Sony          | VGN-SR5                     | [7f93c9c366](https://linux-hardware.org/?probe=7f93c9c366) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | [3fc588a18d](https://linux-hardware.org/?probe=3fc588a18d) | Sep 08, 2021 |
| MSI           | GS75 Stealth 10SF           | [fd38e5bf9d](https://linux-hardware.org/?probe=fd38e5bf9d) | Sep 08, 2021 |
| HP            | EliteBook 840 G3            | [22d88098a9](https://linux-hardware.org/?probe=22d88098a9) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [be8d4bd453](https://linux-hardware.org/?probe=be8d4bd453) | Sep 08, 2021 |
| Toshiba       | Satellite C75D-B            | [47317abce2](https://linux-hardware.org/?probe=47317abce2) | Sep 08, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [e8f88bd1b2](https://linux-hardware.org/?probe=e8f88bd1b2) | Sep 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [98874d48b2](https://linux-hardware.org/?probe=98874d48b2) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f872b42a74](https://linux-hardware.org/?probe=f872b42a74) | Sep 07, 2021 |
| Acer          | V5-171                      | [8068be142e](https://linux-hardware.org/?probe=8068be142e) | Sep 07, 2021 |
| HP            | Notebook                    | [62a2618cde](https://linux-hardware.org/?probe=62a2618cde) | Sep 07, 2021 |
| Toshiba       | Satellite L755              | [92d22f65bf](https://linux-hardware.org/?probe=92d22f65bf) | Sep 07, 2021 |
| Samsung       | 550P5C/550P7C               | [a2a7c20bf7](https://linux-hardware.org/?probe=a2a7c20bf7) | Sep 07, 2021 |
| Dell          | Precision 3520              | [15e6e2c91d](https://linux-hardware.org/?probe=15e6e2c91d) | Sep 07, 2021 |
| Dell          | Precision 5550              | [8ae36d685d](https://linux-hardware.org/?probe=8ae36d685d) | Sep 07, 2021 |
| Dell          | Latitude E5430 non-vPro     | [368f488133](https://linux-hardware.org/?probe=368f488133) | Sep 07, 2021 |
| MSI           | GL62 7RDX                   | [be53fd4c86](https://linux-hardware.org/?probe=be53fd4c86) | Sep 07, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | [3eaf057f6f](https://linux-hardware.org/?probe=3eaf057f6f) | Sep 07, 2021 |
| Acer          | Swift SF114-34              | [8a66ec8e37](https://linux-hardware.org/?probe=8a66ec8e37) | Sep 07, 2021 |
| Lenovo        | B50-30 20382                | [f91b1f41fc](https://linux-hardware.org/?probe=f91b1f41fc) | Sep 06, 2021 |
| HP            | Pavilion dv5                | [27607d962e](https://linux-hardware.org/?probe=27607d962e) | Sep 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d1af312696](https://linux-hardware.org/?probe=d1af312696) | Sep 06, 2021 |
| Acer          | Aspire V3-571G              | [46499caf7a](https://linux-hardware.org/?probe=46499caf7a) | Sep 05, 2021 |
| Sony          | VPCS135FX                   | [55c2fa54ae](https://linux-hardware.org/?probe=55c2fa54ae) | Sep 05, 2021 |
| Apple         | MacBook3,1                  | [1473909011](https://linux-hardware.org/?probe=1473909011) | Sep 05, 2021 |
| Lenovo        | G505s 20255                 | [263eeefef0](https://linux-hardware.org/?probe=263eeefef0) | Sep 04, 2021 |
| Lenovo        | G505s 20255                 | [8cd745db58](https://linux-hardware.org/?probe=8cd745db58) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [960930d457](https://linux-hardware.org/?probe=960930d457) | Sep 04, 2021 |
| HP            | ProBook 6450b               | [98041e0acd](https://linux-hardware.org/?probe=98041e0acd) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [303c36ac93](https://linux-hardware.org/?probe=303c36ac93) | Sep 03, 2021 |
| HP            | 255 G3                      | [bd1a8b58da](https://linux-hardware.org/?probe=bd1a8b58da) | Sep 03, 2021 |
| HP            | 255 G3                      | [b5f1c73339](https://linux-hardware.org/?probe=b5f1c73339) | Sep 03, 2021 |
| Acer          | Aspire A315-31              | [f07f0d19ca](https://linux-hardware.org/?probe=f07f0d19ca) | Sep 03, 2021 |
| HP            | EliteBook 840 G1            | [980716e0a8](https://linux-hardware.org/?probe=980716e0a8) | Sep 03, 2021 |
| ASUSTek       | GR8                         | [eb4fb4e1f2](https://linux-hardware.org/?probe=eb4fb4e1f2) | Sep 03, 2021 |
| Lenovo        | ThinkPad W520 4284AW3       | [6647a6a4b4](https://linux-hardware.org/?probe=6647a6a4b4) | Sep 03, 2021 |
| Acer          | Aspire R3-131T              | [62485c81e9](https://linux-hardware.org/?probe=62485c81e9) | Sep 02, 2021 |
| Acer          | Aspire E5-521G              | [d1aa71f003](https://linux-hardware.org/?probe=d1aa71f003) | Sep 02, 2021 |
| Acer          | Aspire 4830T                | [52441614fe](https://linux-hardware.org/?probe=52441614fe) | Sep 02, 2021 |
| Acer          | Aspire E1-522               | [8cd8899bae](https://linux-hardware.org/?probe=8cd8899bae) | Sep 02, 2021 |
| Toshiba       | Satellite C850D-11C         | [51748f289f](https://linux-hardware.org/?probe=51748f289f) | Sep 01, 2021 |
| HP            | ENVY 15                     | [d2bb5f165e](https://linux-hardware.org/?probe=d2bb5f165e) | Sep 01, 2021 |
| ASUSTek       | X405UA                      | [9bf230ee3f](https://linux-hardware.org/?probe=9bf230ee3f) | Aug 31, 2021 |
| Insyde        | i101c                       | [de0a5f2925](https://linux-hardware.org/?probe=de0a5f2925) | Aug 31, 2021 |
| HP            | EliteBook 840 G1            | [8439784c2b](https://linux-hardware.org/?probe=8439784c2b) | Aug 31, 2021 |
| HP            | Pavilion 15                 | [13ae124697](https://linux-hardware.org/?probe=13ae124697) | Aug 31, 2021 |
| ASUSTek       | K73SV                       | [e7c8d68b00](https://linux-hardware.org/?probe=e7c8d68b00) | Aug 31, 2021 |
| Dell          | XPS 15 9560                 | [fe38c67cd2](https://linux-hardware.org/?probe=fe38c67cd2) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | [80412fd612](https://linux-hardware.org/?probe=80412fd612) | Aug 30, 2021 |
| Acer          | Aspire E1-522               | [f2542100bc](https://linux-hardware.org/?probe=f2542100bc) | Aug 30, 2021 |
| Lenovo        | B50-70 80EU                 | [9507d559fc](https://linux-hardware.org/?probe=9507d559fc) | Aug 30, 2021 |
| Apple         | MacBookPro11,1              | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Packard Be... | DOT S                       | [0231531196](https://linux-hardware.org/?probe=0231531196) | Aug 29, 2021 |
| Packard Be... | DOT S                       | [4f0a335506](https://linux-hardware.org/?probe=4f0a335506) | Aug 29, 2021 |
| Lenovo        | ThinkPad T520 4242W4F       | [150dd830ac](https://linux-hardware.org/?probe=150dd830ac) | Aug 29, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [e63b8b96dd](https://linux-hardware.org/?probe=e63b8b96dd) | Aug 29, 2021 |
| Acer          | Aspire 5100                 | [2b16fed8a1](https://linux-hardware.org/?probe=2b16fed8a1) | Aug 28, 2021 |
| Toshiba       | Satellite S75Dt-A           | [c3e9c3d13b](https://linux-hardware.org/?probe=c3e9c3d13b) | Aug 28, 2021 |
| Acer          | Aspire A515-51              | [6acb0f573a](https://linux-hardware.org/?probe=6acb0f573a) | Aug 28, 2021 |
| ASUSTek       | K56CA                       | [90d571608f](https://linux-hardware.org/?probe=90d571608f) | Aug 28, 2021 |
| Dell          | Inspiron 5566               | [2c2761e770](https://linux-hardware.org/?probe=2c2761e770) | Aug 27, 2021 |
| Dell          | XPS 13 9310                 | [08009ad892](https://linux-hardware.org/?probe=08009ad892) | Aug 26, 2021 |
| Acer          | AO722                       | [e303d0c046](https://linux-hardware.org/?probe=e303d0c046) | Aug 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | [1798e6404c](https://linux-hardware.org/?probe=1798e6404c) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e18bc8fe09](https://linux-hardware.org/?probe=e18bc8fe09) | Aug 25, 2021 |
| Acer          | Aspire ES1-512              | [48b43bd242](https://linux-hardware.org/?probe=48b43bd242) | Aug 25, 2021 |
| Unknown       | Unknown                     | [e576736426](https://linux-hardware.org/?probe=e576736426) | Aug 25, 2021 |
| TianBei       | TB-H7                       | [455dce9834](https://linux-hardware.org/?probe=455dce9834) | Aug 25, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [a64e3a0513](https://linux-hardware.org/?probe=a64e3a0513) | Aug 25, 2021 |
| LG Electro... | S460-G.BG31P1               | [99df59aebd](https://linux-hardware.org/?probe=99df59aebd) | Aug 24, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [3d58cb6ce0](https://linux-hardware.org/?probe=3d58cb6ce0) | Aug 24, 2021 |
| Acer          | Aspire 7715Z                | [4de4de1a31](https://linux-hardware.org/?probe=4de4de1a31) | Aug 24, 2021 |
| Lenovo        | G50-30 80G0                 | [27cdfce14b](https://linux-hardware.org/?probe=27cdfce14b) | Aug 24, 2021 |
| LG Electro... | A410-K.BE47P1               | [bfc75c9c3d](https://linux-hardware.org/?probe=bfc75c9c3d) | Aug 24, 2021 |
| Acer          | Aspire 8940G                | [24ff3cf596](https://linux-hardware.org/?probe=24ff3cf596) | Aug 23, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b0830bd154](https://linux-hardware.org/?probe=b0830bd154) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [c56758deca](https://linux-hardware.org/?probe=c56758deca) | Aug 23, 2021 |
| Dell          | Inspiron 5566               | [eaef6e8392](https://linux-hardware.org/?probe=eaef6e8392) | Aug 23, 2021 |
| Dell          | Precision M4800             | [9766c85e7d](https://linux-hardware.org/?probe=9766c85e7d) | Aug 23, 2021 |
| Dell          | Precision M4800             | [cd3dbe3a32](https://linux-hardware.org/?probe=cd3dbe3a32) | Aug 23, 2021 |
| Unknown       | Unknown                     | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| TianBei       | TB-H7                       | [2d1b3b2756](https://linux-hardware.org/?probe=2d1b3b2756) | Aug 23, 2021 |
| ASUSTek       | X550LD                      | [04365cbbbf](https://linux-hardware.org/?probe=04365cbbbf) | Aug 22, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | [43f252f22a](https://linux-hardware.org/?probe=43f252f22a) | Aug 22, 2021 |
| Apple         | MacBookPro11,5              | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| HP            | ProBook 450 G2              | [99f47f1645](https://linux-hardware.org/?probe=99f47f1645) | Aug 21, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | [7b1954838a](https://linux-hardware.org/?probe=7b1954838a) | Aug 21, 2021 |
| HP            | Notebook                    | [2586dc3a41](https://linux-hardware.org/?probe=2586dc3a41) | Aug 21, 2021 |
| Lenovo        | G50-30 80G0                 | [afbefeb6d3](https://linux-hardware.org/?probe=afbefeb6d3) | Aug 21, 2021 |
| Lenovo        | ThinkPad X131e 3371AL2      | [1963322393](https://linux-hardware.org/?probe=1963322393) | Aug 21, 2021 |
| ASUSTek       | GR8                         | [88416da5e8](https://linux-hardware.org/?probe=88416da5e8) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| Sony          | VGN-SR5                     | [3bbd8b33f0](https://linux-hardware.org/?probe=3bbd8b33f0) | Aug 20, 2021 |
| HP            | ENVY 14                     | [34f9505762](https://linux-hardware.org/?probe=34f9505762) | Aug 20, 2021 |
| Lenovo        | G50-70 20351                | [40249b1ea8](https://linux-hardware.org/?probe=40249b1ea8) | Aug 20, 2021 |
| HP            | ENVY Sleekbook 4 PC         | [231e17454e](https://linux-hardware.org/?probe=231e17454e) | Aug 19, 2021 |
| Dell          | Inspiron N5040              | [0554d06022](https://linux-hardware.org/?probe=0554d06022) | Aug 19, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| Acer          | Nitro AN515-55              | [3a47dca146](https://linux-hardware.org/?probe=3a47dca146) | Aug 18, 2021 |
| HP            | ProBook 450 G2              | [a3e170c339](https://linux-hardware.org/?probe=a3e170c339) | Aug 17, 2021 |
| Acer          | Swift SF114-34              | [0a37eed9e8](https://linux-hardware.org/?probe=0a37eed9e8) | Aug 15, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fcfd1e5ba9](https://linux-hardware.org/?probe=fcfd1e5ba9) | Aug 15, 2021 |
| HP            | ProBook 430 G6              | [c5467376e9](https://linux-hardware.org/?probe=c5467376e9) | Aug 13, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [9718804b4a](https://linux-hardware.org/?probe=9718804b4a) | Aug 12, 2021 |
| HP            | ProBook 450 G2              | [67956ca49e](https://linux-hardware.org/?probe=67956ca49e) | Aug 10, 2021 |
| Acer          | Aspire E1-571               | [146f910c76](https://linux-hardware.org/?probe=146f910c76) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [c7a0820fe0](https://linux-hardware.org/?probe=c7a0820fe0) | Aug 09, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [950d41dbb8](https://linux-hardware.org/?probe=950d41dbb8) | Aug 09, 2021 |
| Dell          | Inspiron 7537               | [7a35ed5eb1](https://linux-hardware.org/?probe=7a35ed5eb1) | Aug 03, 2021 |
| Dell          | Inspiron 7537               | [3c865e72d1](https://linux-hardware.org/?probe=3c865e72d1) | Aug 03, 2021 |
| Acer          | Aspire E5-551G              | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Dell          | XPS L501X                   | [a3d8e737a5](https://linux-hardware.org/?probe=a3d8e737a5) | Jul 08, 2021 |
| Dell          | G3 3579                     | [92a8136dc4](https://linux-hardware.org/?probe=92a8136dc4) | Jul 03, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [1196d6821c](https://linux-hardware.org/?probe=1196d6821c) | Jul 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [d63c7755ee](https://linux-hardware.org/?probe=d63c7755ee) | Jun 29, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [369a214905](https://linux-hardware.org/?probe=369a214905) | Jun 25, 2021 |
| Dell          | Inspiron 3576               | [849d571ef0](https://linux-hardware.org/?probe=849d571ef0) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [9957b51bea](https://linux-hardware.org/?probe=9957b51bea) | Jun 24, 2021 |
| Dell          | Inspiron 3582               | [e2cd9a9c36](https://linux-hardware.org/?probe=e2cd9a9c36) | Jun 20, 2021 |
| Dell          | XPS 13 9370                 | [9e3a58b257](https://linux-hardware.org/?probe=9e3a58b257) | Jun 12, 2021 |
| Dell          | XPS 13 9370                 | [2aa1efb008](https://linux-hardware.org/?probe=2aa1efb008) | Jun 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [01cf29ba72](https://linux-hardware.org/?probe=01cf29ba72) | Jun 10, 2021 |
| HP            | 15                          | [f2132922af](https://linux-hardware.org/?probe=f2132922af) | Jun 08, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [a1dd6df8e7](https://linux-hardware.org/?probe=a1dd6df8e7) | Jun 07, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [957048adbb](https://linux-hardware.org/?probe=957048adbb) | Jun 06, 2021 |
| Dell          | Inspiron 3582               | [229600e417](https://linux-hardware.org/?probe=229600e417) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK AH532              | [719041c9d4](https://linux-hardware.org/?probe=719041c9d4) | Jun 04, 2021 |
| HP            | ProBook 650 G2              | [bb92ab2244](https://linux-hardware.org/?probe=bb92ab2244) | May 30, 2021 |
| HP            | Unknown                     | [e6e060ca51](https://linux-hardware.org/?probe=e6e060ca51) | May 29, 2021 |
| HP            | Unknown                     | [324d49aba6](https://linux-hardware.org/?probe=324d49aba6) | May 29, 2021 |
| Razer         | Book 13 - RZ09-0357         | [c1cc1fcf2e](https://linux-hardware.org/?probe=c1cc1fcf2e) | May 27, 2021 |
| Dell          | Vostro 5490                 | [9d8401675e](https://linux-hardware.org/?probe=9d8401675e) | May 18, 2021 |
| Dell          | Vostro 5490                 | [3f02204090](https://linux-hardware.org/?probe=3f02204090) | May 18, 2021 |
| Acer          | Swift SF313-51              | [2b27dc30ac](https://linux-hardware.org/?probe=2b27dc30ac) | May 17, 2021 |
| ASUSTek       | X406UAR                     | [5c50159b19](https://linux-hardware.org/?probe=5c50159b19) | May 16, 2021 |
| ASUSTek       | X406UAR                     | [e3be0eaa69](https://linux-hardware.org/?probe=e3be0eaa69) | May 16, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [b71b291af5](https://linux-hardware.org/?probe=b71b291af5) | May 10, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [157ae0cc83](https://linux-hardware.org/?probe=157ae0cc83) | May 02, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [12081d4e79](https://linux-hardware.org/?probe=12081d4e79) | Apr 25, 2021 |
| Lenovo        | IdeaPad Y570 0862           | [94d22e7673](https://linux-hardware.org/?probe=94d22e7673) | Apr 23, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.11.0-38-generic           | 94        | 12.05%  |
| 5.11.0-27-generic           | 92        | 11.79%  |
| 5.11.0-37-generic           | 72        | 9.23%   |
| 5.11.0-40-generic           | 64        | 8.21%   |
| 5.11.0-41-generic           | 61        | 7.82%   |
| 5.11.0-43-generic           | 59        | 7.56%   |
| 5.11.0-34-generic           | 57        | 7.31%   |
| 5.13.0-30-generic           | 46        | 5.9%    |
| 5.13.0-35-generic           | 41        | 5.26%   |
| 5.13.0-28-generic           | 38        | 4.87%   |
| 5.13.0-27-generic           | 29        | 3.72%   |
| 5.11.0-46-generic           | 25        | 3.21%   |
| 5.11.0-36-generic           | 22        | 2.82%   |
| 5.11.0-44-generic           | 18        | 2.31%   |
| 5.13.0-37-generic           | 12        | 1.54%   |
| 5.11.0-25-generic           | 9         | 1.15%   |
| 5.13.0-39-generic           | 8         | 1.03%   |
| 5.8.0-53-generic            | 6         | 0.77%   |
| 5.8.0-59-generic            | 5         | 0.64%   |
| 5.8.0-55-generic            | 5         | 0.64%   |
| 5.8.0-50-generic            | 4         | 0.51%   |
| 5.8.0-63-generic            | 1         | 0.13%   |
| 5.8.0-49-generic            | 1         | 0.13%   |
| 5.16.12-051612-generic      | 1         | 0.13%   |
| 5.16.0-051600rc8-lowlatency | 1         | 0.13%   |
| 5.16.0-051600rc4-generic    | 1         | 0.13%   |
| 5.15.24-xanmod1             | 1         | 0.13%   |
| 5.15.0-8.1-liquorix-amd64   | 1         | 0.13%   |
| 5.14.0-15.1-liquorix-amd64  | 1         | 0.13%   |
| 5.13.18-xanmod1             | 1         | 0.13%   |
| 5.13.0-25-generic           | 1         | 0.13%   |
| 5.13.0-1020-oem             | 1         | 0.13%   |
| 5.10.0-1052-oem             | 1         | 0.13%   |
| 5.10.0-1044-oem             | 1         | 0.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 538       | 72.9%   |
| 5.13.0  | 169       | 22.9%   |
| 5.8.0   | 22        | 2.98%   |
| 5.16.0  | 2         | 0.27%   |
| 5.10.0  | 2         | 0.27%   |
| 5.16.12 | 1         | 0.14%   |
| 5.15.24 | 1         | 0.14%   |
| 5.15.0  | 1         | 0.14%   |
| 5.14.0  | 1         | 0.14%   |
| 5.13.18 | 1         | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 538       | 72.9%   |
| 5.13    | 170       | 23.04%  |
| 5.8     | 22        | 2.98%   |
| 5.16    | 3         | 0.41%   |
| 5.15    | 2         | 0.27%   |
| 5.10    | 2         | 0.27%   |
| 5.14    | 1         | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 715       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 662       | 92.2%   |
| XFCE       | 49        | 6.82%   |
| Unknown    | 5         | 0.7%    |
| X-Cinnamon | 1         | 0.14%   |
| KDE        | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 704       | 98.19%  |
| Wayland | 11        | 1.53%   |
| Unknown | 2         | 0.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 556       | 77.01%  |
| GDM3    | 83        | 11.5%   |
| GDM     | 71        | 9.83%   |
| LightDM | 11        | 1.52%   |
| SDDM    | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 283       | 39.36%  |
| de_DE | 64        | 8.9%    |
| en_GB | 54        | 7.51%   |
| pt_BR | 43        | 5.98%   |
| en_IN | 26        | 3.62%   |
| es_ES | 24        | 3.34%   |
| en_CA | 21        | 2.92%   |
| fr_FR | 19        | 2.64%   |
| pl_PL | 16        | 2.23%   |
| it_IT | 15        | 2.09%   |
| nl_NL | 14        | 1.95%   |
| en_AU | 14        | 1.95%   |
| es_MX | 13        | 1.81%   |
| ru_RU | 10        | 1.39%   |
| pt_PT | 9         | 1.25%   |
| en_ZA | 8         | 1.11%   |
| cs_CZ | 8         | 1.11%   |
| fr_BE | 7         | 0.97%   |
| es_CL | 7         | 0.97%   |
| sv_SE | 5         | 0.7%    |
| de_AT | 5         | 0.7%    |
| en_NZ | 4         | 0.56%   |
| tr_TR | 3         | 0.42%   |
| nl_BE | 3         | 0.42%   |
| hu_HU | 3         | 0.42%   |
| el_GR | 3         | 0.42%   |
| de_CH | 3         | 0.42%   |
| bg_BG | 3         | 0.42%   |
| ru_UA | 2         | 0.28%   |
| nb_NO | 2         | 0.28%   |
| ja_JP | 2         | 0.28%   |
| hr_HR | 2         | 0.28%   |
| es_PE | 2         | 0.28%   |
| es_EC | 2         | 0.28%   |
| es_AR | 2         | 0.28%   |
| en_IL | 2         | 0.28%   |
| ar_EG | 2         | 0.28%   |
| sl_SI | 1         | 0.14%   |
| sk_SK | 1         | 0.14%   |
| ro_RO | 1         | 0.14%   |
| fr_CA | 1         | 0.14%   |
| fi_FI | 1         | 0.14%   |
| es_UY | 1         | 0.14%   |
| es_PA | 1         | 0.14%   |
| es_CR | 1         | 0.14%   |
| es_CO | 1         | 0.14%   |
| es_BO | 1         | 0.14%   |
| en_SG | 1         | 0.14%   |
| en_PH | 1         | 0.14%   |
| da_DK | 1         | 0.14%   |
| C     | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 432       | 59.75%  |
| BIOS | 291       | 40.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 679       | 94.7%   |
| Zfs     | 14        | 1.95%   |
| Btrfs   | 11        | 1.53%   |
| Overlay | 10        | 1.39%   |
| Xfs     | 2         | 0.28%   |
| Ext2    | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 641       | 88.9%   |
| GPT     | 70        | 9.71%   |
| MBR     | 10        | 1.39%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 704       | 98.32%  |
| Yes       | 12        | 1.68%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 653       | 90.95%  |
| Yes       | 65        | 9.05%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 152       | 21.26%  |
| Lenovo                 | 121       | 16.92%  |
| Dell                   | 110       | 15.38%  |
| ASUSTek Computer       | 90        | 12.59%  |
| Acer                   | 66        | 9.23%   |
| Toshiba                | 36        | 5.03%   |
| Apple                  | 18        | 2.52%   |
| MSI                    | 14        | 1.96%   |
| Sony                   | 13        | 1.82%   |
| Samsung Electronics    | 11        | 1.54%   |
| Unknown                | 10        | 1.4%    |
| Google                 | 6         | 0.84%   |
| Packard Bell           | 5         | 0.7%    |
| Notebook               | 5         | 0.7%    |
| LG Electronics         | 4         | 0.56%   |
| Razer                  | 3         | 0.42%   |
| Jumper                 | 3         | 0.42%   |
| Insyde                 | 3         | 0.42%   |
| HUAWEI                 | 3         | 0.42%   |
| Fujitsu                | 3         | 0.42%   |
| Chuwi                  | 3         | 0.42%   |
| TUXEDO                 | 2         | 0.28%   |
| Positivo               | 2         | 0.28%   |
| Multilaser             | 2         | 0.28%   |
| Fujitsu Siemens        | 2         | 0.28%   |
| Digibras               | 2         | 0.28%   |
| UNOWHY                 | 1         | 0.14%   |
| TianBei                | 1         | 0.14%   |
| Thomson                | 1         | 0.14%   |
| TCL Communication      | 1         | 0.14%   |
| Star Labs              | 1         | 0.14%   |
| Schenker               | 1         | 0.14%   |
| RCA                    | 1         | 0.14%   |
| Primux                 | 1         | 0.14%   |
| Novatech               | 1         | 0.14%   |
| NEC Computers          | 1         | 0.14%   |
| mPTech                 | 1         | 0.14%   |
| Mediacom               | 1         | 0.14%   |
| MECER                  | 1         | 0.14%   |
| Login Informatica      | 1         | 0.14%   |
| KOGAN                  | 1         | 0.14%   |
| Gigabyte Technology    | 1         | 0.14%   |
| Giani Limited          | 1         | 0.14%   |
| GEO                    | 1         | 0.14%   |
| Gateway                | 1         | 0.14%   |
| Fusion5                | 1         | 0.14%   |
| e-shop.gr              | 1         | 0.14%   |
| Dynabook               | 1         | 0.14%   |
| Compaq                 | 1         | 0.14%   |
| Clevo                  | 1         | 0.14%   |
| AXDIA International    | 1         | 0.14%   |
| Avell High Performance | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 12        | 1.68%   |
| HP Notebook                    | 10        | 1.4%    |
| HP 15                          | 6         | 0.84%   |
| HP Pavilion Notebook           | 4         | 0.56%   |
| HP Pavilion 15                 | 4         | 0.56%   |
| Dell Latitude E7440            | 4         | 0.56%   |
| Lenovo IdeaPad S340-14API 81NB | 3         | 0.42%   |
| Lenovo IdeaPad S145-15API 81V7 | 3         | 0.42%   |
| Lenovo IdeaPad Flex-14API 81SS | 3         | 0.42%   |
| HP ProBook 640 G1              | 3         | 0.42%   |
| HP Pavilion g6                 | 3         | 0.42%   |
| HP Pavilion dv7                | 3         | 0.42%   |
| HP OMEN by Laptop 15-dc1xxx    | 3         | 0.42%   |
| HP Laptop 15-bw0xx             | 3         | 0.42%   |
| Dell Latitude E6420            | 3         | 0.42%   |
| Apple MacBookPro8,1            | 3         | 0.42%   |
| Apple MacBookPro11,1           | 3         | 0.42%   |
| Acer V5-171                    | 3         | 0.42%   |
| Toshiba Satellite C660         | 2         | 0.28%   |
| Packard Bell EasyNote TK85     | 2         | 0.28%   |
| Lenovo Yoga 3 Pro-1370 80HE    | 2         | 0.28%   |
| Lenovo IdeaPad Yoga 13 20175   | 2         | 0.28%   |
| Lenovo IdeaPad 330-15IKB 81DE  | 2         | 0.28%   |
| Lenovo IdeaPad 3 15IIL05 81WE  | 2         | 0.28%   |
| Lenovo G560 0679               | 2         | 0.28%   |
| Lenovo G50-70 20351            | 2         | 0.28%   |
| Jumper EZbook                  | 2         | 0.28%   |
| Insyde i101c                   | 2         | 0.28%   |
| HP ProBook 6450b               | 2         | 0.28%   |
| HP ProBook 450 G2              | 2         | 0.28%   |
| HP Pavilion Laptop 15-cs3xxx   | 2         | 0.28%   |
| HP Pavilion dv5                | 2         | 0.28%   |
| HP Pavilion dv3                | 2         | 0.28%   |
| HP OMEN Notebook               | 2         | 0.28%   |
| HP ENVY Sleekbook 4 PC         | 2         | 0.28%   |
| HP EliteBook Folio 9470m       | 2         | 0.28%   |
| HP EliteBook 8440p             | 2         | 0.28%   |
| HP EliteBook 840 G1            | 2         | 0.28%   |
| HP Compaq 8510p                | 2         | 0.28%   |
| Google Kindred                 | 2         | 0.28%   |
| Digibras NH4CU03               | 2         | 0.28%   |
| Dell XPS 15 9510               | 2         | 0.28%   |
| Dell Vostro 1500               | 2         | 0.28%   |
| Dell Precision M4800           | 2         | 0.28%   |
| Dell Precision M4600           | 2         | 0.28%   |
| Dell Latitude E7470            | 2         | 0.28%   |
| Dell Latitude E6520            | 2         | 0.28%   |
| Dell Latitude E6430            | 2         | 0.28%   |
| Dell Latitude E5570            | 2         | 0.28%   |
| Dell Latitude E5500            | 2         | 0.28%   |
| Dell Latitude E5470            | 2         | 0.28%   |
| Dell Latitude 3440             | 2         | 0.28%   |
| Dell Inspiron M5030            | 2         | 0.28%   |
| Dell Inspiron 5770             | 2         | 0.28%   |
| Dell Inspiron 5566             | 2         | 0.28%   |
| Dell Inspiron 3542             | 2         | 0.28%   |
| Dell Inspiron 1750             | 2         | 0.28%   |
| Dell Inspiron 15-3567          | 2         | 0.28%   |
| Dell Inspiron 15 7000 Gaming   | 2         | 0.28%   |
| ASUS X553MA                    | 2         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 47        | 6.57%   |
| Lenovo ThinkPad       | 46        | 6.43%   |
| Acer Aspire           | 45        | 6.29%   |
| Lenovo IdeaPad        | 41        | 5.73%   |
| Dell Inspiron         | 34        | 4.76%   |
| HP Pavilion           | 33        | 4.62%   |
| Toshiba Satellite     | 28        | 3.92%   |
| HP ProBook            | 22        | 3.08%   |
| HP EliteBook          | 20        | 2.8%    |
| ASUS VivoBook         | 15        | 2.1%    |
| HP Laptop             | 14        | 1.96%   |
| Unknown               | 12        | 1.68%   |
| HP Notebook           | 10        | 1.4%    |
| HP ENVY               | 10        | 1.4%    |
| Dell XPS              | 8         | 1.12%   |
| Dell Vostro           | 8         | 1.12%   |
| HP 15                 | 7         | 0.98%   |
| Dell Precision        | 7         | 0.98%   |
| ASUS ZenBook          | 7         | 0.98%   |
| HP Stream             | 6         | 0.84%   |
| HP OMEN               | 6         | 0.84%   |
| HP Compaq             | 5         | 0.7%    |
| HP 255                | 5         | 0.7%    |
| Apple MacBookPro11    | 5         | 0.7%    |
| Acer Swift            | 5         | 0.7%    |
| Toshiba PORTEGE       | 4         | 0.56%   |
| Packard Bell EasyNote | 4         | 0.56%   |
| ASUS TUF              | 4         | 0.56%   |
| ASUS ASUS             | 4         | 0.56%   |
| Lenovo Yoga           | 3         | 0.42%   |
| Lenovo ThinkBook      | 3         | 0.42%   |
| Lenovo Legion         | 3         | 0.42%   |
| Fujitsu LIFEBOOK      | 3         | 0.42%   |
| ASUS ROG              | 3         | 0.42%   |
| Apple MacBookPro8     | 3         | 0.42%   |
| Acer V5-171           | 3         | 0.42%   |
| Acer Nitro            | 3         | 0.42%   |
| Toshiba TECRA         | 2         | 0.28%   |
| Toshiba QOSMIO        | 2         | 0.28%   |
| Razer Blade           | 2         | 0.28%   |
| MSI Modern            | 2         | 0.28%   |
| MSI GF63              | 2         | 0.28%   |
| MSI GE75              | 2         | 0.28%   |
| Lenovo G580           | 2         | 0.28%   |
| Lenovo G560           | 2         | 0.28%   |
| Lenovo G50-70         | 2         | 0.28%   |
| Lenovo Flex           | 2         | 0.28%   |
| Jumper EZbook         | 2         | 0.28%   |
| Insyde i101c          | 2         | 0.28%   |
| Google Kindred        | 2         | 0.28%   |
| Digibras NH4CU03      | 2         | 0.28%   |
| Chuwi GemiBook        | 2         | 0.28%   |
| ASUS X553MA           | 2         | 0.28%   |
| ASUS X405UA           | 2         | 0.28%   |
| Apple MacBook4        | 2         | 0.28%   |
| Acer TravelMate       | 2         | 0.28%   |
| Acer E1-510           | 2         | 0.28%   |
| UNOWHY Y13G011S4EI    | 1         | 0.14%   |
| TUXEDO Pulse          | 1         | 0.14%   |
| TUXEDO InfinityBook   | 1         | 0.14%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 73        | 10.21%  |
| 2012 | 71        | 9.93%   |
| 2013 | 65        | 9.09%   |
| 2019 | 60        | 8.39%   |
| 2020 | 56        | 7.83%   |
| 2017 | 52        | 7.27%   |
| 2021 | 51        | 7.13%   |
| 2014 | 51        | 7.13%   |
| 2018 | 46        | 6.43%   |
| 2016 | 42        | 5.87%   |
| 2010 | 42        | 5.87%   |
| 2015 | 33        | 4.62%   |
| 2008 | 30        | 4.2%    |
| 2009 | 23        | 3.22%   |
| 2007 | 17        | 2.38%   |
| 2006 | 3         | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 715       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 615       | 85.3%   |
| Enabled  | 106       | 14.7%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 708       | 99.02%  |
| Yes  | 7         | 0.98%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 256       | 35.75%  |
| 3.01-4.0    | 197       | 27.51%  |
| 8.01-16.0   | 103       | 14.39%  |
| 16.01-24.0  | 72        | 10.06%  |
| 1.01-2.0    | 41        | 5.73%   |
| 32.01-64.0  | 29        | 4.05%   |
| 2.01-3.0    | 10        | 1.4%    |
| 64.01-256.0 | 6         | 0.84%   |
| 24.01-32.0  | 1         | 0.14%   |
| 0.51-1.0    | 1         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 333       | 43.76%  |
| 2.01-3.0   | 247       | 32.46%  |
| 3.01-4.0   | 94        | 12.35%  |
| 4.01-8.0   | 64        | 8.41%   |
| 0.51-1.0   | 16        | 2.1%    |
| 8.01-16.0  | 5         | 0.66%   |
| 24.01-32.0 | 2         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 545       | 75.59%  |
| 2      | 152       | 21.08%  |
| 3      | 18        | 2.5%    |
| 4      | 5         | 0.69%   |
| 0      | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 396       | 55.08%  |
| Yes       | 323       | 44.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 582       | 81.4%   |
| No        | 133       | 18.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 689       | 96.23%  |
| No        | 27        | 3.77%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 530       | 73.61%  |
| No        | 190       | 26.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Notebooks | Percent |
|------------------------|-----------|---------|
| USA                    | 159       | 22.21%  |
| Germany                | 71        | 9.92%   |
| Brazil                 | 53        | 7.4%    |
| UK                     | 40        | 5.59%   |
| Spain                  | 28        | 3.91%   |
| India                  | 27        | 3.77%   |
| Canada                 | 24        | 3.35%   |
| Netherlands            | 19        | 2.65%   |
| Mexico                 | 18        | 2.51%   |
| France                 | 18        | 2.51%   |
| Italy                  | 17        | 2.37%   |
| Austria                | 14        | 1.96%   |
| Poland                 | 13        | 1.82%   |
| Belgium                | 13        | 1.82%   |
| Australia              | 13        | 1.82%   |
| South Africa           | 12        | 1.68%   |
| Russia                 | 11        | 1.54%   |
| Sweden                 | 9         | 1.26%   |
| Portugal               | 9         | 1.26%   |
| Turkey                 | 8         | 1.12%   |
| Czechia                | 8         | 1.12%   |
| Chile                  | 7         | 0.98%   |
| Switzerland            | 6         | 0.84%   |
| Greece                 | 6         | 0.84%   |
| Bulgaria               | 6         | 0.84%   |
| Romania                | 5         | 0.7%    |
| Norway                 | 5         | 0.7%    |
| Japan                  | 5         | 0.7%    |
| Hungary                | 5         | 0.7%    |
| New Zealand            | 4         | 0.56%   |
| Morocco                | 4         | 0.56%   |
| Indonesia              | 4         | 0.56%   |
| Ukraine                | 3         | 0.42%   |
| Saudi Arabia           | 3         | 0.42%   |
| Kenya                  | 3         | 0.42%   |
| Israel                 | 3         | 0.42%   |
| Ireland                | 3         | 0.42%   |
| Finland                | 3         | 0.42%   |
| Colombia               | 3         | 0.42%   |
| Argentina              | 3         | 0.42%   |
| Vietnam                | 2         | 0.28%   |
| Slovenia               | 2         | 0.28%   |
| Singapore              | 2         | 0.28%   |
| Philippines            | 2         | 0.28%   |
| Moldova                | 2         | 0.28%   |
| Malaysia               | 2         | 0.28%   |
| Lithuania              | 2         | 0.28%   |
| Ecuador                | 2         | 0.28%   |
| Croatia                | 2         | 0.28%   |
| Bosnia and Herzegovina | 2         | 0.28%   |
| Bangladesh             | 2         | 0.28%   |
| Venezuela              | 1         | 0.14%   |
| Uruguay                | 1         | 0.14%   |
| U.S. Virgin Islands    | 1         | 0.14%   |
| Thailand               | 1         | 0.14%   |
| Tanzania               | 1         | 0.14%   |
| Taiwan                 | 1         | 0.14%   |
| Slovakia               | 1         | 0.14%   |
| Qatar                  | 1         | 0.14%   |
| Puerto Rico            | 1         | 0.14%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Vienna                 | 8         | 1.09%   |
| Athens                 | 7         | 0.95%   |
| New York               | 6         | 0.82%   |
| Sydney                 | 5         | 0.68%   |
| Amsterdam              | 5         | 0.68%   |
| Johannesburg           | 4         | 0.54%   |
| Hamburg                | 4         | 0.54%   |
| Glasgow                | 4         | 0.54%   |
| Birmingham             | 4         | 0.54%   |
| Bernissart             | 4         | 0.54%   |
| Berlin                 | 4         | 0.54%   |
| Warsaw                 | 3         | 0.41%   |
| Stockholm              | 3         | 0.41%   |
| SÃ£o LuÃ­s         | 3         | 0.41%   |
| Rome                   | 3         | 0.41%   |
| Porto Alegre           | 3         | 0.41%   |
| Perth                  | 3         | 0.41%   |
| Paris                  | 3         | 0.41%   |
| Nairobi                | 3         | 0.41%   |
| Munich                 | 3         | 0.41%   |
| Moscow                 | 3         | 0.41%   |
| Minneapolis            | 3         | 0.41%   |
| Melbourne              | 3         | 0.41%   |
| Madrid                 | 3         | 0.41%   |
| London                 | 3         | 0.41%   |
| Dallas                 | 3         | 0.41%   |
| Chicago                | 3         | 0.41%   |
| Chennai                | 3         | 0.41%   |
| Brussels               | 3         | 0.41%   |
| Blue Springs           | 3         | 0.41%   |
| Barcelona              | 3         | 0.41%   |
| Zagreb                 | 2         | 0.27%   |
| Washington             | 2         | 0.27%   |
| Vilnius                | 2         | 0.27%   |
| Vila Nova de Gaia      | 2         | 0.27%   |
| Vicenza                | 2         | 0.27%   |
| Velikiye Luki          | 2         | 0.27%   |
| Valencia               | 2         | 0.27%   |
| Taboao da Serra        | 2         | 0.27%   |
| Stuttgart              | 2         | 0.27%   |
| St Petersburg          | 2         | 0.27%   |
| Smyrna                 | 2         | 0.27%   |
| Seattle                | 2         | 0.27%   |
| Sarajevo               | 2         | 0.27%   |
| Sao Paulo              | 2         | 0.27%   |
| Santiago               | 2         | 0.27%   |
| San Francisco          | 2         | 0.27%   |
| Rio de Janeiro         | 2         | 0.27%   |
| Richmond               | 2         | 0.27%   |
| Red Deer               | 2         | 0.27%   |
| Recife                 | 2         | 0.27%   |
| RÃ¼sselsheim am Main | 2         | 0.27%   |
| Pucking                | 2         | 0.27%   |
| Providence             | 2         | 0.27%   |
| Morrow                 | 2         | 0.27%   |
| Montreal               | 2         | 0.27%   |
| Montana                | 2         | 0.27%   |
| Mexico City            | 2         | 0.27%   |
| MacaÃ©               | 2         | 0.27%   |
| La LouviÃ¨re         | 2         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 122       | 151    | 14.44%  |
| Seagate                     | 111       | 131    | 13.14%  |
| WDC                         | 96        | 109    | 11.36%  |
| Toshiba                     | 84        | 90     | 9.94%   |
| Unknown                     | 65        | 78     | 7.69%   |
| SanDisk                     | 65        | 74     | 7.69%   |
| Kingston                    | 36        | 43     | 4.26%   |
| Crucial                     | 30        | 36     | 3.55%   |
| Hitachi                     | 27        | 32     | 3.2%    |
| SK Hynix                    | 23        | 30     | 2.72%   |
| HGST                        | 21        | 27     | 2.49%   |
| Intel                       | 20        | 23     | 2.37%   |
| Micron Technology           | 15        | 16     | 1.78%   |
| A-DATA Technology           | 13        | 14     | 1.54%   |
| Apple                       | 9         | 10     | 1.07%   |
| Intenso                     | 8         | 8      | 0.95%   |
| SPCC                        | 6         | 9      | 0.71%   |
| KIOXIA                      | 6         | 6      | 0.71%   |
| Transcend                   | 5         | 6      | 0.59%   |
| PNY                         | 5         | 6      | 0.59%   |
| LITEONIT                    | 5         | 6      | 0.59%   |
| Fujitsu                     | 5         | 6      | 0.59%   |
| China                       | 5         | 6      | 0.59%   |
| Patriot                     | 4         | 4      | 0.47%   |
| Netac                       | 4         | 4      | 0.47%   |
| JMicron                     | 4         | 5      | 0.47%   |
| GOODRAM                     | 4         | 5      | 0.47%   |
| Phison                      | 3         | 4      | 0.36%   |
| LITEON                      | 3         | 3      | 0.36%   |
| Lite-On                     | 3         | 5      | 0.36%   |
| Team                        | 2         | 2      | 0.24%   |
| SABRENT                     | 2         | 3      | 0.24%   |
| OCZ                         | 2         | 2      | 0.24%   |
| Micron/Crucial Technology   | 2         | 2      | 0.24%   |
| KingSpec                    | 2         | 2      | 0.24%   |
| Hewlett-Packard             | 2         | 2      | 0.24%   |
| BHT                         | 2         | 2      | 0.24%   |
| Unknown                     | 2         | 2      | 0.24%   |
| Yangtze Memory Technologies | 1         | 1      | 0.12%   |
| Verbatim                    | 1         | 1      | 0.12%   |
| Vaseky                      | 1         | 2      | 0.12%   |
| TO Exter                    | 1         | 1      | 0.12%   |
| Teclast                     | 1         | 1      | 0.12%   |
| T-FORCE                     | 1         | 1      | 0.12%   |
| Star                        | 1         | 1      | 0.12%   |
| Space ke                    | 1         | 1      | 0.12%   |
| Realtek Semiconductor       | 1         | 1      | 0.12%   |
| PLEXTOR                     | 1         | 1      | 0.12%   |
| OSCOO                       | 1         | 1      | 0.12%   |
| MidasForce                  | 1         | 1      | 0.12%   |
| LS                          | 1         | 1      | 0.12%   |
| Lexar                       | 1         | 1      | 0.12%   |
| KIOXIA-EXCERIA              | 1         | 1      | 0.12%   |
| KESU                        | 1         | 1      | 0.12%   |
| HS-SSD-E100                 | 1         | 1      | 0.12%   |
| FORESEE                     | 1         | 1      | 0.12%   |
| E535N                       | 1         | 1      | 0.12%   |
| DragonDiamond               | 1         | 1      | 0.12%   |
| BUFFALO                     | 1         | 1      | 0.12%   |
| ASMT                        | 1         | 1      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 25        | 2.84%   |
| Unknown MMC Card  64GB              | 21        | 2.39%   |
| Seagate ST1000LM035-1RK172 1TB      | 17        | 1.93%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 15        | 1.71%   |
| Sandisk NVMe SSD Drive 256GB        | 14        | 1.59%   |
| Samsung NVMe SSD Drive 512GB        | 13        | 1.48%   |
| Toshiba MQ04ABF100 1TB              | 11        | 1.25%   |
| Toshiba MQ01ABD100 1TB              | 11        | 1.25%   |
| Toshiba MQ01ABF050 500GB            | 10        | 1.14%   |
| Samsung NVMe SSD Drive 256GB        | 10        | 1.14%   |
| Kingston SA400S37240G 240GB SSD     | 9         | 1.02%   |
| Sandisk NVMe SSD Drive 512GB        | 8         | 0.91%   |
| Unknown MMC Card  128GB             | 7         | 0.8%    |
| Seagate ST9500325AS 500GB           | 7         | 0.8%    |
| Intel NVMe SSD Drive 512GB          | 7         | 0.8%    |
| Crucial CT240BX500SSD1 240GB        | 7         | 0.8%    |
| Samsung SSD 860 EVO 500GB           | 6         | 0.68%   |
| Kingston SA400S37480G 480GB SSD     | 6         | 0.68%   |
| Kingston SA400S37120G 120GB SSD     | 6         | 0.68%   |
| WDC WD10SPZX-24Z10 1TB              | 5         | 0.57%   |
| Unknown SD/MMC/MS PRO 32GB          | 5         | 0.57%   |
| SK Hynix NVMe SSD Drive 256GB       | 5         | 0.57%   |
| Seagate ST500LT012-1DG142 500GB     | 5         | 0.57%   |
| Seagate ST1000LM049-2GH172 1TB      | 5         | 0.57%   |
| Samsung SSD 860 EVO 250GB           | 5         | 0.57%   |
| Samsung SSD 850 EVO 500GB           | 5         | 0.57%   |
| HGST HTS725050A7E630 500GB          | 5         | 0.57%   |
| HGST HTS721010A9E630 1TB            | 5         | 0.57%   |
| Crucial CT500MX500SSD1 500GB        | 5         | 0.57%   |
| WDC WD10JPVX-22JC3T0 1TB            | 4         | 0.46%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 0.46%   |
| Seagate ST2000LM007-1R8174 2TB      | 4         | 0.46%   |
| SanDisk X400 M.2 2280 256GB SSD     | 4         | 0.46%   |
| Samsung SSD 860 EVO 1TB             | 4         | 0.46%   |
| Samsung NVMe SSD Drive 500GB        | 4         | 0.46%   |
| Micron NVMe SSD Drive 512GB         | 4         | 0.46%   |
| Intel NVMe SSD Drive 1024GB         | 4         | 0.46%   |
| HGST HTS541010A9E680 1TB            | 4         | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 3         | 0.34%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 3         | 0.34%   |
| WDC WD10JPVX-60JC3T0 1TB            | 3         | 0.34%   |
| Unknown MMC Card  16GB              | 3         | 0.34%   |
| Toshiba NVMe SSD Drive 256GB        | 3         | 0.34%   |
| Toshiba MK2555GSX 250GB             | 3         | 0.34%   |
| Toshiba MK2552GSX 250GB             | 3         | 0.34%   |
| SK Hynix NVMe SSD Drive 512GB       | 3         | 0.34%   |
| Seagate ST9500420AS 500GB           | 3         | 0.34%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 3         | 0.34%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 0.34%   |
| Seagate ST500LM021-1KJ152 500GB     | 3         | 0.34%   |
| Seagate ST1000LM014-1EJ164 1TB      | 3         | 0.34%   |
| Seagate Expansion 320GB             | 3         | 0.34%   |
| SanDisk SSD PLUS 240GB              | 3         | 0.34%   |
| Sandisk NVMe SSD Drive 1TB          | 3         | 0.34%   |
| Samsung SSD 850 EVO 250GB           | 3         | 0.34%   |
| Samsung SSD 840 EVO 250GB           | 3         | 0.34%   |
| Samsung NVMe SSD Drive 2TB          | 3         | 0.34%   |
| Samsung NVMe SSD Drive 1TB          | 3         | 0.34%   |
| PNY CS900 120GB SSD                 | 3         | 0.34%   |
| KIOXIA NVMe SSD Drive 512GB         | 3         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 110       | 129    | 34.81%  |
| WDC                 | 74        | 80     | 23.42%  |
| Toshiba             | 62        | 67     | 19.62%  |
| Hitachi             | 27        | 32     | 8.54%   |
| HGST                | 21        | 27     | 6.65%   |
| Unknown             | 5         | 5      | 1.58%   |
| Samsung Electronics | 5         | 5      | 1.58%   |
| Fujitsu             | 5         | 6      | 1.58%   |
| SABRENT             | 2         | 3      | 0.63%   |
| KESU                | 1         | 1      | 0.32%   |
| JMicron             | 1         | 1      | 0.32%   |
| Intenso             | 1         | 1      | 0.32%   |
| ASMT                | 1         | 1      | 0.32%   |
| Apple               | 1         | 1      | 0.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 72        | 85     | 23.38%  |
| SanDisk             | 33        | 39     | 10.71%  |
| Kingston            | 32        | 39     | 10.39%  |
| Crucial             | 30        | 35     | 9.74%   |
| Toshiba             | 16        | 16     | 5.19%   |
| WDC                 | 14        | 19     | 4.55%   |
| SK Hynix            | 10        | 10     | 3.25%   |
| A-DATA Technology   | 9         | 10     | 2.92%   |
| Micron Technology   | 8         | 9      | 2.6%    |
| Intenso             | 7         | 7      | 2.27%   |
| Apple               | 7         | 7      | 2.27%   |
| Transcend           | 5         | 6      | 1.62%   |
| SPCC                | 5         | 8      | 1.62%   |
| PNY                 | 5         | 6      | 1.62%   |
| LITEONIT            | 5         | 6      | 1.62%   |
| Intel               | 5         | 5      | 1.62%   |
| China               | 5         | 6      | 1.62%   |
| Patriot             | 4         | 4      | 1.3%    |
| Netac               | 4         | 4      | 1.3%    |
| GOODRAM             | 4         | 5      | 1.3%    |
| LITEON              | 3         | 3      | 0.97%   |
| Team                | 2         | 2      | 0.65%   |
| OCZ                 | 2         | 2      | 0.65%   |
| KingSpec            | 2         | 2      | 0.65%   |
| JMicron             | 2         | 3      | 0.65%   |
| Hewlett-Packard     | 2         | 2      | 0.65%   |
| BHT                 | 2         | 2      | 0.65%   |
| Verbatim            | 1         | 1      | 0.32%   |
| TO Exter            | 1         | 1      | 0.32%   |
| Teclast             | 1         | 1      | 0.32%   |
| Star                | 1         | 1      | 0.32%   |
| PLEXTOR             | 1         | 1      | 0.32%   |
| OSCOO               | 1         | 1      | 0.32%   |
| MidasForce          | 1         | 1      | 0.32%   |
| Lexar               | 1         | 1      | 0.32%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.32%   |
| HS-SSD-E100         | 1         | 1      | 0.32%   |
| FORESEE             | 1         | 1      | 0.32%   |
| BUFFALO             | 1         | 1      | 0.32%   |
| Unknown             | 1         | 1      | 0.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 311       | 359    | 37.79%  |
| SSD     | 294       | 355    | 35.72%  |
| NVMe    | 144       | 185    | 17.5%   |
| MMC     | 66        | 78     | 8.02%   |
| Unknown | 8         | 10     | 0.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 561       | 692    | 70.57%  |
| NVMe | 144       | 185    | 18.11%  |
| MMC  | 66        | 78     | 8.3%    |
| SAS  | 24        | 32     | 3.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 406       | 482    | 68.12%  |
| 0.51-1.0   | 173       | 205    | 29.03%  |
| 1.01-2.0   | 12        | 18     | 2.01%   |
| 3.01-4.0   | 2         | 6      | 0.34%   |
| 4.01-10.0  | 2         | 2      | 0.34%   |
| 2.01-3.0   | 1         | 1      | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 255       | 35.27%  |
| 251-500        | 198       | 27.39%  |
| 501-1000       | 104       | 14.38%  |
| 51-100         | 66        | 9.13%   |
| 21-50          | 40        | 5.53%   |
| 1001-2000      | 21        | 2.9%    |
| 1-20           | 14        | 1.94%   |
| Unknown        | 11        | 1.52%   |
| More than 3000 | 8         | 1.11%   |
| 2001-3000      | 6         | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 348       | 46.4%   |
| 21-50          | 207       | 27.6%   |
| 51-100         | 70        | 9.33%   |
| 101-250        | 64        | 8.53%   |
| 251-500        | 29        | 3.87%   |
| 501-1000       | 17        | 2.27%   |
| Unknown        | 11        | 1.47%   |
| More than 3000 | 3         | 0.4%    |
| 2001-3000      | 1         | 0.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB            | 2         | 2      | 18.18%  |
| WDC WD10SPZX-75Z10T2 1TB           | 1         | 1      | 9.09%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 9.09%   |
| Seagate ST9500420AS 500GB          | 1         | 1      | 9.09%   |
| Seagate ST9200420ASG 200GB         | 1         | 1      | 9.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 9.09%   |
| Hitachi HTS725032A9A364 320GB      | 1         | 1      | 9.09%   |
| HGST HTS725050A7E630 500GB         | 1         | 1      | 9.09%   |
| HGST HTS545050A7E680 500GB         | 1         | 1      | 9.09%   |
| Hewlett-Packard SSD S600 240GB     | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 3         | 3      | 27.27%  |
| WDC             | 2         | 2      | 18.18%  |
| Toshiba         | 2         | 2      | 18.18%  |
| HGST            | 2         | 2      | 18.18%  |
| Hitachi         | 1         | 1      | 9.09%   |
| Hewlett-Packard | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 30%     |
| WDC     | 2         | 2      | 20%     |
| Toshiba | 2         | 2      | 20%     |
| HGST    | 2         | 2      | 20%     |
| Hitachi | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 90.91%  |
| SSD  | 1         | 1      | 9.09%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                 | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk SSD i100 24GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SanDisk | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 642       | 886    | 87.95%  |
| Works    | 76        | 89     | 10.41%  |
| Malfunc  | 11        | 11     | 1.51%   |
| Failed   | 1         | 1      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 536       | 68.45%  |
| AMD                              | 93        | 11.88%  |
| Samsung Electronics              | 55        | 7.02%   |
| Sandisk                          | 33        | 4.21%   |
| SK Hynix                         | 12        | 1.53%   |
| Micron Technology                | 7         | 0.89%   |
| KIOXIA                           | 7         | 0.89%   |
| Toshiba America Info Systems     | 6         | 0.77%   |
| Nvidia                           | 4         | 0.51%   |
| Kingston Technology Company      | 4         | 0.51%   |
| ADATA Technology                 | 4         | 0.51%   |
| Phison Electronics               | 3         | 0.38%   |
| Micron/Crucial Technology        | 3         | 0.38%   |
| Marvell Technology Group         | 3         | 0.38%   |
| Lite-On Technology               | 3         | 0.38%   |
| ASMedia Technology               | 3         | 0.38%   |
| Realtek Semiconductor            | 2         | 0.26%   |
| Yangtze Memory Technologies      | 1         | 0.13%   |
| VIA Technologies                 | 1         | 0.13%   |
| Silicon Motion                   | 1         | 0.13%   |
| Silicon Integrated Systems [SiS] | 1         | 0.13%   |
| Apple                            | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 77        | 9.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 71        | 8.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 57        | 6.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 53        | 6.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 51        | 6.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 38        | 4.51%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 28        | 3.32%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 27        | 3.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 24        | 2.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 22        | 2.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 22        | 2.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 20        | 2.37%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 15        | 1.78%   |
| Samsung NVMe SSD Controller 980                                                        | 14        | 1.66%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 14        | 1.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 14        | 1.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 14        | 1.66%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 13        | 1.54%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 12        | 1.42%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 11        | 1.3%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 11        | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 11        | 1.3%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 10        | 1.19%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 10        | 1.19%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 9         | 1.07%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 9         | 1.07%   |
| Intel SSD 660P Series                                                                  | 8         | 0.95%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 8         | 0.95%   |
| Micron Non-Volatile memory controller                                                  | 7         | 0.83%   |
| KIOXIA Non-Volatile memory controller                                                  | 7         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 7         | 0.83%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 6         | 0.71%   |
| SK Hynix BC501 NVMe Solid State Drive                                                  | 5         | 0.59%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 5         | 0.59%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 5         | 0.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 5         | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 4         | 0.47%   |
| Intel Non-Volatile memory controller                                                   | 4         | 0.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 4         | 0.47%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 4         | 0.47%   |
| SK Hynix Gold P31 SSD                                                                  | 3         | 0.36%   |
| SK Hynix BC511                                                                         | 3         | 0.36%   |
| Sandisk Non-Volatile memory controller                                                 | 3         | 0.36%   |
| Samsung Apple PCIe SSD                                                                 | 3         | 0.36%   |
| Nvidia MCP79 AHCI Controller                                                           | 3         | 0.36%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                             | 3         | 0.36%   |
| Lite-On Non-Volatile memory controller                                                 | 3         | 0.36%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 3         | 0.36%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 3         | 0.36%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 3         | 0.36%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 3         | 0.36%   |
| AMD FCH IDE Controller                                                                 | 3         | 0.36%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 2         | 0.24%   |
| Sandisk PC SN520 NVMe SSD                                                              | 2         | 0.24%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 2         | 0.24%   |
| Samsung Electronics SATA controller                                                    | 2         | 0.24%   |
| Realtek Realtek Non-Volatile memory controller                                         | 2         | 0.24%   |
| Phison E12 NVMe Controller                                                             | 2         | 0.24%   |
| Intel SSD 600P Series                                                                  | 2         | 0.24%   |
| Intel SATA Controller [RAID mode]                                                      | 2         | 0.24%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 550       | 67.57%  |
| NVMe | 144       | 17.69%  |
| RAID | 71        | 8.72%   |
| IDE  | 49        | 6.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 603       | 84.22%  |
| AMD    | 113       | 15.78%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 14        | 1.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 1.54%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 1.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 1.54%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 10        | 1.4%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 1.26%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 1.26%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 9         | 1.26%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 8         | 1.12%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 8         | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 1.12%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 1.12%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 1.12%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 8         | 1.12%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 1.12%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 0.98%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 7         | 0.98%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 7         | 0.98%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 6         | 0.84%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 6         | 0.84%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 6         | 0.84%   |
| Intel Core i3-4030U CPU @ 1.90GHz             | 6         | 0.84%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 6         | 0.84%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 0.84%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 5         | 0.7%    |
| Intel Core i5-3317U CPU @ 1.70GHz             | 5         | 0.7%    |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 0.7%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 5         | 0.7%    |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 5         | 0.7%    |
| Intel Core i3-7020U CPU @ 2.30GHz             | 5         | 0.7%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 5         | 0.7%    |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 5         | 0.7%    |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 5         | 0.7%    |
| Intel Celeron CPU N3450 @ 1.10GHz             | 5         | 0.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 5         | 0.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.7%    |
| Intel Pentium CPU P6200 @ 2.13GHz             | 4         | 0.56%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 4         | 0.56%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.56%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 4         | 0.56%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 4         | 0.56%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 0.56%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 4         | 0.56%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 4         | 0.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.56%   |
| Intel Core i7 CPU Q 740 @ 1.73GHz             | 4         | 0.56%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 4         | 0.56%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 4         | 0.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 0.56%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 4         | 0.56%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 4         | 0.56%   |
| Intel Core i5 CPU M 460 @ 2.53GHz             | 4         | 0.56%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 4         | 0.56%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 4         | 0.56%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 4         | 0.56%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 4         | 0.56%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 4         | 0.56%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 4         | 0.56%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 4         | 0.56%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 4         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 194       | 27.09%  |
| Intel Core i7                        | 129       | 18.02%  |
| Intel Core i3                        | 81        | 11.31%  |
| Intel Celeron                        | 51        | 7.12%   |
| Intel Core 2 Duo                     | 46        | 6.42%   |
| Intel Pentium                        | 32        | 4.47%   |
| AMD Ryzen 5                          | 26        | 3.63%   |
| Other                                | 25        | 3.49%   |
| Intel Atom                           | 25        | 3.49%   |
| AMD Ryzen 7                          | 17        | 2.37%   |
| AMD A6                               | 15        | 2.09%   |
| AMD A10                              | 9         | 1.26%   |
| AMD E1                               | 7         | 0.98%   |
| AMD E                                | 5         | 0.7%    |
| Intel Pentium Dual-Core              | 4         | 0.56%   |
| Intel Pentium Dual                   | 4         | 0.56%   |
| Intel Core m5                        | 4         | 0.56%   |
| AMD Ryzen 3                          | 4         | 0.56%   |
| AMD A8                               | 4         | 0.56%   |
| AMD A4                               | 4         | 0.56%   |
| Intel Pentium Silver                 | 2         | 0.28%   |
| Intel Core M                         | 2         | 0.28%   |
| Intel Celeron Dual-Core              | 2         | 0.28%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 2         | 0.28%   |
| AMD Turion 64 X2 Mobile              | 2         | 0.28%   |
| AMD FX                               | 2         | 0.28%   |
| AMD E2                               | 2         | 0.28%   |
| AMD Athlon II                        | 2         | 0.28%   |
| Intel Xeon                           | 1         | 0.14%   |
| Intel Genuine                        | 1         | 0.14%   |
| Intel Core i9                        | 1         | 0.14%   |
| Intel Core 2                         | 1         | 0.14%   |
| Intel Celeron M                      | 1         | 0.14%   |
| AMD Turion II                        | 1         | 0.14%   |
| AMD Turion 64 Mobile                 | 1         | 0.14%   |
| AMD Sempron                          | 1         | 0.14%   |
| AMD Ryzen 9                          | 1         | 0.14%   |
| AMD Ryzen 7 PRO                      | 1         | 0.14%   |
| AMD Phenom II                        | 1         | 0.14%   |
| AMD C-60                             | 1         | 0.14%   |
| AMD Athlon X2                        | 1         | 0.14%   |
| AMD Athlon                           | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 439       | 61.31%  |
| 4      | 222       | 31.01%  |
| 6      | 26        | 3.63%   |
| 8      | 21        | 2.93%   |
| 1      | 6         | 0.84%   |
| 10     | 1         | 0.14%   |
| 3      | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 715       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 489       | 68.3%   |
| 1      | 227       | 31.7%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 715       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 71        | 9.82%   |
| 0x306a9    | 65        | 8.99%   |
| Unknown    | 48        | 6.64%   |
| 0x40651    | 42        | 5.81%   |
| 0x406e3    | 27        | 3.73%   |
| 0x20655    | 27        | 3.73%   |
| 0x806ea    | 26        | 3.6%    |
| 0x1067a    | 25        | 3.46%   |
| 0x306d4    | 24        | 3.32%   |
| 0x806ec    | 20        | 2.77%   |
| 0x306c3    | 18        | 2.49%   |
| 0x806e9    | 17        | 2.35%   |
| 0x806c1    | 17        | 2.35%   |
| 0x30678    | 16        | 2.21%   |
| 0x406c4    | 15        | 2.07%   |
| 0x906ea    | 13        | 1.8%    |
| 0x706e5    | 13        | 1.8%    |
| 0x506c9    | 13        | 1.8%    |
| 0x906e9    | 12        | 1.66%   |
| 0x20652    | 12        | 1.66%   |
| 0x10676    | 12        | 1.66%   |
| 0x08108102 | 12        | 1.66%   |
| 0x706a8    | 11        | 1.52%   |
| 0x6fd      | 11        | 1.52%   |
| 0x406c3    | 10        | 1.38%   |
| 0x08108109 | 10        | 1.38%   |
| 0x07030105 | 9         | 1.24%   |
| 0xa0652    | 7         | 0.97%   |
| 0x6fb      | 7         | 0.97%   |
| 0x08600106 | 7         | 0.97%   |
| 0x06006704 | 6         | 0.83%   |
| 0x05000119 | 6         | 0.83%   |
| 0x806eb    | 5         | 0.69%   |
| 0x106e5    | 5         | 0.69%   |
| 0x0a50000c | 5         | 0.69%   |
| 0x0700010f | 5         | 0.69%   |
| 0x06006705 | 5         | 0.69%   |
| 0x706a1    | 4         | 0.55%   |
| 0x506e3    | 4         | 0.55%   |
| 0x08608103 | 4         | 0.55%   |
| 0x07030106 | 4         | 0.55%   |
| 0x0600611a | 4         | 0.55%   |
| 0x010000c8 | 4         | 0.55%   |
| 0x806d1    | 3         | 0.41%   |
| 0x30673    | 3         | 0.41%   |
| 0x08600104 | 3         | 0.41%   |
| 0x08600103 | 3         | 0.41%   |
| 0x06003106 | 3         | 0.41%   |
| 0x03000027 | 3         | 0.41%   |
| 0x02000057 | 3         | 0.41%   |
| 0x6fa      | 2         | 0.28%   |
| 0x6f6      | 2         | 0.28%   |
| 0x40661    | 2         | 0.28%   |
| 0x30661    | 2         | 0.28%   |
| 0x106ca    | 2         | 0.28%   |
| 0x0a50000b | 2         | 0.28%   |
| 0x06001119 | 2         | 0.28%   |
| 0xa0655    | 1         | 0.14%   |
| 0x906ed    | 1         | 0.14%   |
| 0x906c0    | 1         | 0.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 109       | 15.22%  |
| SandyBridge     | 73        | 10.2%   |
| IvyBridge       | 67        | 9.36%   |
| Haswell         | 66        | 9.22%   |
| Silvermont      | 45        | 6.28%   |
| Westmere        | 40        | 5.59%   |
| Penryn          | 37        | 5.17%   |
| Skylake         | 34        | 4.75%   |
| Broadwell       | 24        | 3.35%   |
| Zen+            | 23        | 3.21%   |
| Core            | 23        | 3.21%   |
| TigerLake       | 19        | 2.65%   |
| IceLake         | 17        | 2.37%   |
| Excavator       | 16        | 2.23%   |
| Goldmont plus   | 15        | 2.09%   |
| Zen 2           | 14        | 1.96%   |
| Puma            | 14        | 1.96%   |
| Goldmont        | 14        | 1.96%   |
| CometLake       | 9         | 1.26%   |
| Zen 3           | 8         | 1.12%   |
| Bobcat          | 7         | 0.98%   |
| Nehalem         | 6         | 0.84%   |
| Jaguar          | 6         | 0.84%   |
| Unknown         | 5         | 0.7%    |
| K8 & K10 hybrid | 4         | 0.56%   |
| K10             | 4         | 0.56%   |
| Bonnell         | 4         | 0.56%   |
| Steamroller     | 3         | 0.42%   |
| Piledriver      | 3         | 0.42%   |
| K8 Hammer       | 3         | 0.42%   |
| K10 Llano       | 3         | 0.42%   |
| Tremont         | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 546       | 63.56%  |
| Nvidia                           | 162       | 18.86%  |
| AMD                              | 150       | 17.46%  |
| Silicon Integrated Systems [SiS] | 1         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 65        | 7.32%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 64        | 7.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 45        | 5.07%   |
| Intel Core Processor Integrated Graphics Controller                                      | 33        | 3.72%   |
| Intel UHD Graphics 620                                                                   | 27        | 3.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 25        | 2.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 24        | 2.7%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 23        | 2.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 21        | 2.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 2.25%   |
| Intel HD Graphics 620                                                                    | 19        | 2.14%   |
| Intel HD Graphics 5500                                                                   | 18        | 2.03%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 16        | 1.8%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 1.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 1.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 14        | 1.58%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 14        | 1.58%   |
| AMD Renoir                                                                               | 14        | 1.58%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 1.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 1.46%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 13        | 1.46%   |
| Intel HD Graphics 630                                                                    | 12        | 1.35%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 11        | 1.24%   |
| Intel HD Graphics 500                                                                    | 11        | 1.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 1.24%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 11        | 1.24%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 10        | 1.13%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 1.01%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 9         | 1.01%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.9%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 0.79%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 0.68%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 6         | 0.68%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 6         | 0.68%   |
| AMD Cezanne                                                                              | 6         | 0.68%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 5         | 0.56%   |
| AMD Lucienne                                                                             | 5         | 0.56%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.45%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 4         | 0.45%   |
| Intel HD Graphics 530                                                                    | 4         | 0.45%   |
| Intel HD Graphics 515                                                                    | 4         | 0.45%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.45%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 4         | 0.45%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 4         | 0.45%   |
| Nvidia TU117M                                                                            | 3         | 0.34%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 3         | 0.34%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.34%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.34%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.34%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.34%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 3         | 0.34%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 0.34%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.34%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 3         | 0.34%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.34%   |
| Intel Tiger Lake UHD Graphics                                                            | 3         | 0.34%   |
| Intel HD Graphics 5300                                                                   | 3         | 0.34%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.34%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 0.34%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 3         | 0.34%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 413       | 57.68%  |
| Intel + Nvidia | 109       | 15.22%  |
| 1 x AMD        | 103       | 14.39%  |
| 1 x Nvidia     | 42        | 5.87%   |
| Intel + AMD    | 24        | 3.35%   |
| 2 x AMD        | 13        | 1.82%   |
| AMD + Nvidia   | 10        | 1.4%    |
| 2 x Nvidia     | 1         | 0.14%   |
| 1 x SiS        | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 617       | 86.29%  |
| Proprietary | 89        | 12.45%  |
| Unknown     | 9         | 1.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 468       | 64.55%  |
| 0.01-0.5   | 83        | 11.45%  |
| 1.01-2.0   | 72        | 9.93%   |
| 0.51-1.0   | 53        | 7.31%   |
| 3.01-4.0   | 25        | 3.45%   |
| 5.01-6.0   | 12        | 1.66%   |
| 7.01-8.0   | 8         | 1.1%    |
| 2.01-3.0   | 3         | 0.41%   |
| 8.01-16.0  | 1         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 148       | 19.55%  |
| Chimei Innolux          | 111       | 14.66%  |
| LG Display              | 109       | 14.4%   |
| Samsung Electronics     | 105       | 13.87%  |
| BOE                     | 87        | 11.49%  |
| Chi Mei Optoelectronics | 28        | 3.7%    |
| Apple                   | 18        | 2.38%   |
| Sharp                   | 15        | 1.98%   |
| Lenovo                  | 15        | 1.98%   |
| Dell                    | 13        | 1.72%   |
| PANDA                   | 12        | 1.59%   |
| Goldstar                | 11        | 1.45%   |
| LG Philips              | 9         | 1.19%   |
| LGD                     | 5         | 0.66%   |
| Vizio                   | 4         | 0.53%   |
| CPT                     | 4         | 0.53%   |
| BenQ                    | 4         | 0.53%   |
| AOC                     | 4         | 0.53%   |
| Acer                    | 4         | 0.53%   |
| Philips                 | 3         | 0.4%    |
| KDC                     | 3         | 0.4%    |
| InfoVision              | 3         | 0.4%    |
| Hewlett-Packard         | 3         | 0.4%    |
| BOE Technology Group    | 3         | 0.4%    |
| Toshiba                 | 2         | 0.26%   |
| Sony                    | 2         | 0.26%   |
| Sanyo                   | 2         | 0.26%   |
| Quanta Display          | 2         | 0.26%   |
| ITE                     | 2         | 0.26%   |
| Iiyama                  | 2         | 0.26%   |
| HannStar                | 2         | 0.26%   |
| VIE                     | 1         | 0.13%   |
| Unknown                 | 1         | 0.13%   |
| SLD                     | 1         | 0.13%   |
| Sceptre Tech            | 1         | 0.13%   |
| Panasonic               | 1         | 0.13%   |
| MStar                   | 1         | 0.13%   |
| MSI                     | 1         | 0.13%   |
| KTC                     | 1         | 0.13%   |
| KDB                     | 1         | 0.13%   |
| InnoLux Display         | 1         | 0.13%   |
| HSI                     | 1         | 0.13%   |
| HRG                     | 1         | 0.13%   |
| HIC                     | 1         | 0.13%   |
| HDE                     | 1         | 0.13%   |
| Gateway                 | 1         | 0.13%   |
| Fujitsu Siemens         | 1         | 0.13%   |
| ELD                     | 1         | 0.13%   |
| Eizo                    | 1         | 0.13%   |
| Belinea                 | 1         | 0.13%   |
| ASUSTek Computer        | 1         | 0.13%   |
| Ancor Communications    | 1         | 0.13%   |
| Unknown                 | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 256x144mm 11.6-inch     | 7         | 0.92%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 7         | 0.92%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.92%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 7         | 0.92%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 6         | 0.78%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.78%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.78%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 0.65%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 5         | 0.65%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 5         | 0.65%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch     | 4         | 0.52%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 4         | 0.52%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 4         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 4         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 4         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch          | 4         | 0.52%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 4         | 0.52%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 4         | 0.52%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 4         | 0.52%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 4         | 0.52%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 4         | 0.52%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 4         | 0.52%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 3         | 0.39%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 3         | 0.39%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 3         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch    | 3         | 0.39%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                  | 3         | 0.39%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch          | 3         | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 3         | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 3         | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO1590 1366x768 344x194mm 15.5-inch | 3         | 0.39%   |
| BOE LCD Monitor BOE0653 1920x1080 309x173mm 13.9-inch                    | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO325C 1366x768 256x144mm 11.6-inch            | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch           | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO113D 1920x1080 309x173mm 13.9-inch           | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO109E 1600x900 380x210mm 17.1-inch            | 3         | 0.39%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 3         | 0.39%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch     | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch     | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch     | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch     | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 340x190mm 15.3-inch    | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SDC484E 1600x900 309x174mm 14.0-inch     | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch     | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch    | 2         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 2         | 0.26%   |
| LGD LCD Monitor 1920x1080                                                | 2         | 0.26%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 2         | 0.26%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 2         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 312       | 42.22%  |
| 1920x1080 (FHD)    | 232       | 31.39%  |
| 1600x900 (HD+)     | 56        | 7.58%   |
| 1280x800 (WXGA)    | 38        | 5.14%   |
| 3840x2160 (4K)     | 18        | 2.44%   |
| 1440x900 (WXGA+)   | 10        | 1.35%   |
| 2560x1600          | 7         | 0.95%   |
| 2560x1440 (QHD)    | 7         | 0.95%   |
| Unknown            | 6         | 0.81%   |
| 1680x1050 (WSXGA+) | 5         | 0.68%   |
| 1360x768           | 5         | 0.68%   |
| 3200x1800 (QHD+)   | 4         | 0.54%   |
| 2880x1800          | 4         | 0.54%   |
| 1920x1200 (WUXGA)  | 4         | 0.54%   |
| 1280x1024 (SXGA)   | 4         | 0.54%   |
| 3840x2400          | 3         | 0.41%   |
| 2256x1504          | 3         | 0.41%   |
| 2160x1440          | 3         | 0.41%   |
| 1024x600           | 3         | 0.41%   |
| 5760x1080          | 2         | 0.27%   |
| 3440x1440          | 2         | 0.27%   |
| 2560x1080          | 2         | 0.27%   |
| 1920x515           | 2         | 0.27%   |
| 4480x1600          | 1         | 0.14%   |
| 3840x1200          | 1         | 0.14%   |
| 3840x1080          | 1         | 0.14%   |
| 3600x1080          | 1         | 0.14%   |
| 1920x540           | 1         | 0.14%   |
| 1920x1280          | 1         | 0.14%   |
| 1680x945           | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 328       | 43.5%   |
| 13      | 115       | 15.25%  |
| 14      | 81        | 10.74%  |
| 17      | 66        | 8.75%   |
| 12      | 24        | 3.18%   |
| Unknown | 21        | 2.79%   |
| 11      | 20        | 2.65%   |
| 24      | 16        | 2.12%   |
| 27      | 13        | 1.72%   |
| 18      | 10        | 1.33%   |
| 23      | 8         | 1.06%   |
| 34      | 5         | 0.66%   |
| 31      | 5         | 0.66%   |
| 21      | 5         | 0.66%   |
| 20      | 5         | 0.66%   |
| 16      | 5         | 0.66%   |
| 10      | 5         | 0.66%   |
| 25      | 3         | 0.4%    |
| 72      | 2         | 0.27%   |
| 40      | 2         | 0.27%   |
| 32      | 2         | 0.27%   |
| 19      | 2         | 0.27%   |
| 84      | 1         | 0.13%   |
| 74      | 1         | 0.13%   |
| 64      | 1         | 0.13%   |
| 54      | 1         | 0.13%   |
| 52      | 1         | 0.13%   |
| 49      | 1         | 0.13%   |
| 48      | 1         | 0.13%   |
| 47      | 1         | 0.13%   |
| 46      | 1         | 0.13%   |
| 37      | 1         | 0.13%   |
| 26      | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 460       | 61.25%  |
| 201-300     | 105       | 13.98%  |
| 351-400     | 78        | 10.39%  |
| 501-600     | 36        | 4.79%   |
| 401-500     | 22        | 2.93%   |
| Unknown     | 21        | 2.8%    |
| 601-700     | 8         | 1.07%   |
| 701-800     | 7         | 0.93%   |
| 1001-1500   | 7         | 0.93%   |
| 1501-2000   | 4         | 0.53%   |
| 801-900     | 3         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 589       | 84.87%  |
| 16/10   | 69        | 9.94%   |
| Unknown | 16        | 2.31%   |
| 3/2     | 8         | 1.15%   |
| 21/9    | 5         | 0.72%   |
| 5/4     | 3         | 0.43%   |
| 4/3     | 2         | 0.29%   |
| 3.73    | 2         | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 330       | 43.71%  |
| 81-90          | 153       | 20.26%  |
| 121-130        | 56        | 7.42%   |
| 71-80          | 43        | 5.7%    |
| 201-250        | 27        | 3.58%   |
| 61-70          | 23        | 3.05%   |
| Unknown        | 21        | 2.78%   |
| 51-60          | 20        | 2.65%   |
| 301-350        | 14        | 1.85%   |
| 351-500        | 12        | 1.59%   |
| 141-150        | 12        | 1.59%   |
| More than 1000 | 9         | 1.19%   |
| 151-200        | 9         | 1.19%   |
| 131-140        | 7         | 0.93%   |
| 41-50          | 5         | 0.66%   |
| 501-1000       | 5         | 0.66%   |
| 251-300        | 4         | 0.53%   |
| 111-120        | 3         | 0.4%    |
| 91-100         | 2         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 325       | 43.62%  |
| 121-160       | 221       | 29.66%  |
| 51-100        | 112       | 15.03%  |
| 161-240       | 39        | 5.23%   |
| Unknown       | 21        | 2.82%   |
| More than 240 | 14        | 1.88%   |
| 1-50          | 13        | 1.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 624       | 86.55%  |
| 2     | 85        | 11.79%  |
| 0     | 8         | 1.11%   |
| 3     | 3         | 0.42%   |
| 4     | 1         | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 376       | 32.95%  |
| Intel                             | 318       | 27.87%  |
| Qualcomm Atheros                  | 197       | 17.27%  |
| Broadcom                          | 91        | 7.98%   |
| Broadcom Limited                  | 33        | 2.89%   |
| ASIX Electronics                  | 13        | 1.14%   |
| Ralink                            | 12        | 1.05%   |
| Marvell Technology Group          | 11        | 0.96%   |
| Dell                              | 10        | 0.88%   |
| Xiaomi                            | 7         | 0.61%   |
| Samsung Electronics               | 7         | 0.61%   |
| TP-Link                           | 6         | 0.53%   |
| Ralink Technology                 | 6         | 0.53%   |
| MEDIATEK                          | 5         | 0.44%   |
| DisplayLink                       | 5         | 0.44%   |
| Huawei Technologies               | 4         | 0.35%   |
| Hewlett-Packard                   | 4         | 0.35%   |
| Sierra Wireless                   | 3         | 0.26%   |
| Nvidia                            | 3         | 0.26%   |
| JMicron Technology                | 3         | 0.26%   |
| T & A Mobile Phones               | 2         | 0.18%   |
| Qualcomm                          | 2         | 0.18%   |
| OPPO Electronics                  | 2         | 0.18%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.18%   |
| Ericsson Business Mobile Networks | 2         | 0.18%   |
| Edimax Technology                 | 2         | 0.18%   |
| D-Link System                     | 2         | 0.18%   |
| ZyXEL Communications              | 1         | 0.09%   |
| ZyDAS                             | 1         | 0.09%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.09%   |
| Qualcomm Atheros Communications   | 1         | 0.09%   |
| Novatel Wireless                  | 1         | 0.09%   |
| NetGear                           | 1         | 0.09%   |
| Motorola PCS                      | 1         | 0.09%   |
| Motorola BCS                      | 1         | 0.09%   |
| Linksys                           | 1         | 0.09%   |
| Lenovo                            | 1         | 0.09%   |
| ICS Advent                        | 1         | 0.09%   |
| Exar                              | 1         | 0.09%   |
| DJI Technology                    | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 215       | 15.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 89        | 6.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 49        | 3.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 35        | 2.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 30        | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 30        | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 27        | 2%      |
| Intel Wireless 7260                                                     | 27        | 2%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 25        | 1.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 23        | 1.7%    |
| Intel Wireless 8260                                                     | 22        | 1.63%   |
| Broadcom BCM43142 802.11b/g/n                                           | 21        | 1.56%   |
| Intel Wireless 7265                                                     | 20        | 1.48%   |
| Intel Wireless 8265 / 8275                                              | 19        | 1.41%   |
| Intel Wi-Fi 6 AX200                                                     | 19        | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 16        | 1.19%   |
| Intel Wireless 3165                                                     | 16        | 1.19%   |
| Intel Wi-Fi 6 AX201                                                     | 14        | 1.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 13        | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 0.89%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 12        | 0.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 12        | 0.89%   |
| Intel WiFi Link 5100                                                    | 12        | 0.89%   |
| Intel Ethernet Connection I219-LM                                       | 12        | 0.89%   |
| ASIX AX88179 Gigabit Ethernet                                           | 12        | 0.89%   |
| Intel Centrino Ultimate-N 6300                                          | 10        | 0.74%   |
| Intel 82577LM Gigabit Network Connection                                | 10        | 0.74%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 10        | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 9         | 0.67%   |
| Intel Ethernet Connection I218-LM                                       | 9         | 0.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 9         | 0.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 0.59%   |
| Intel Centrino Advanced-N 6200                                          | 8         | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.52%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 0.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.52%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.52%   |
| Intel Ethernet Connection I217-LM                                       | 7         | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 6         | 0.44%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 6         | 0.44%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 6         | 0.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.44%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 6         | 0.44%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 6         | 0.44%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 0.44%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.44%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 5         | 0.37%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 0.37%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 5         | 0.37%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.37%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 5         | 0.37%   |
| Intel 82567LM Gigabit Network Connection                                | 5         | 0.37%   |
| Intel 82566MM Gigabit Network Connection                                | 5         | 0.37%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 5         | 0.37%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 5         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 301       | 41.81%  |
| Qualcomm Atheros                | 170       | 23.61%  |
| Realtek Semiconductor           | 119       | 16.53%  |
| Broadcom                        | 65        | 9.03%   |
| Broadcom Limited                | 21        | 2.92%   |
| Ralink                          | 12        | 1.67%   |
| Ralink Technology               | 6         | 0.83%   |
| Dell                            | 5         | 0.69%   |
| MEDIATEK                        | 4         | 0.56%   |
| TP-Link                         | 3         | 0.42%   |
| Sierra Wireless                 | 3         | 0.42%   |
| Edimax Technology               | 2         | 0.28%   |
| D-Link System                   | 2         | 0.28%   |
| ZyXEL Communications            | 1         | 0.14%   |
| ZyDAS                           | 1         | 0.14%   |
| Qualcomm Atheros Communications | 1         | 0.14%   |
| Qualcomm                        | 1         | 0.14%   |
| NetGear                         | 1         | 0.14%   |
| Linksys                         | 1         | 0.14%   |
| Hewlett-Packard                 | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 49        | 6.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 30        | 4.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 30        | 4.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 27        | 3.72%   |
| Intel Wireless 7260                                                     | 27        | 3.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 25        | 3.45%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 23        | 3.17%   |
| Intel Wireless 8260                                                     | 22        | 3.03%   |
| Broadcom BCM43142 802.11b/g/n                                           | 21        | 2.9%    |
| Intel Wireless 7265                                                     | 20        | 2.76%   |
| Intel Wireless 8265 / 8275                                              | 19        | 2.62%   |
| Intel Wi-Fi 6 AX200                                                     | 19        | 2.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 16        | 2.21%   |
| Intel Wireless 3165                                                     | 16        | 2.21%   |
| Intel Wi-Fi 6 AX201                                                     | 14        | 1.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 14        | 1.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 12        | 1.66%   |
| Intel WiFi Link 5100                                                    | 12        | 1.66%   |
| Intel Centrino Ultimate-N 6300                                          | 10        | 1.38%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 9         | 1.24%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 1.24%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 9         | 1.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.1%    |
| Intel Centrino Advanced-N 6200                                          | 8         | 1.1%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.97%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.97%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 0.97%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 6         | 0.83%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.83%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 6         | 0.83%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 6         | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 0.83%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.83%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 0.69%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 5         | 0.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 0.69%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 5         | 0.69%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 5         | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 4         | 0.55%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.55%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.55%   |
| Intel Wireless 3160                                                     | 4         | 0.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.55%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 0.55%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 0.55%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 0.55%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 4         | 0.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.41%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 0.41%   |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 0.41%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 3         | 0.41%   |
| Dell Hub of E-Port Replicator                                           | 3         | 0.41%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 3         | 0.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 324       | 53.47%  |
| Intel                            | 120       | 19.8%   |
| Qualcomm Atheros                 | 48        | 7.92%   |
| Broadcom                         | 34        | 5.61%   |
| Broadcom Limited                 | 14        | 2.31%   |
| ASIX Electronics                 | 13        | 2.15%   |
| Marvell Technology Group         | 11        | 1.82%   |
| Xiaomi                           | 7         | 1.16%   |
| Samsung Electronics              | 6         | 0.99%   |
| DisplayLink                      | 5         | 0.83%   |
| TP-Link                          | 3         | 0.5%    |
| Nvidia                           | 3         | 0.5%    |
| JMicron Technology               | 3         | 0.5%    |
| Huawei Technologies              | 3         | 0.5%    |
| OPPO Electronics                 | 2         | 0.33%   |
| Silicon Integrated Systems [SiS] | 1         | 0.17%   |
| Qualcomm                         | 1         | 0.17%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.17%   |
| Novatel Wireless                 | 1         | 0.17%   |
| Motorola PCS                     | 1         | 0.17%   |
| Motorola BCS                     | 1         | 0.17%   |
| MediaTek                         | 1         | 0.17%   |
| Lenovo                           | 1         | 0.17%   |
| ICS Advent                       | 1         | 0.17%   |
| Hewlett-Packard                  | 1         | 0.17%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 215       | 35.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 89        | 14.61%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 35        | 5.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13        | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 1.97%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 1.97%   |
| ASIX AX88179 Gigabit Ethernet                                     | 12        | 1.97%   |
| Intel 82577LM Gigabit Network Connection                          | 10        | 1.64%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 10        | 1.64%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 1.48%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 1.15%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 0.99%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 6         | 0.99%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.82%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 0.82%   |
| Intel 82566MM Gigabit Network Connection                          | 5         | 0.82%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 0.82%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.66%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.66%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.66%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 0.66%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.66%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.66%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 3         | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.49%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 3         | 0.49%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.49%   |
| Intel 82577LC Gigabit Network Connection                          | 3         | 0.49%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                 | 3         | 0.49%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 3         | 0.49%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 3         | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.33%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.33%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.33%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.33%   |
| OPPO RMX2001                                                      | 2         | 0.33%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.33%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 2         | 0.33%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.33%   |
| Intel Ethernet controller                                         | 2         | 0.33%   |
| Intel Ethernet Connection I218-V                                  | 2         | 0.33%   |
| Intel Ethernet Connection (6) I219-LM                             | 2         | 0.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.33%   |
| Intel 82562GT 10/100 Network Connection                           | 2         | 0.33%   |
| Huawei E353/E3131                                                 | 2         | 0.33%   |
| DisplayLink Universal Dual 4K Video Dock                          | 2         | 0.33%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.33%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.33%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 0.33%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 2         | 0.33%   |
| Broadcom Limited NetLink BCM5784M Gigabit Ethernet PCIe           | 2         | 0.33%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 2         | 0.33%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.16%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.16%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 689       | 53.62%  |
| Ethernet | 580       | 45.14%  |
| Modem    | 13        | 1.01%   |
| Unknown  | 3         | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 655       | 56.66%  |
| Ethernet | 498       | 43.08%  |
| Modem    | 2         | 0.17%   |
| Unknown  | 1         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 531       | 74.27%  |
| 1     | 152       | 21.26%  |
| 0     | 28        | 3.92%   |
| 3     | 4         | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 506       | 70.18%  |
| Yes  | 215       | 29.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 207       | 38.62%  |
| Qualcomm Atheros Communications | 67        | 12.5%   |
| Realtek Semiconductor           | 66        | 12.31%  |
| Broadcom                        | 36        | 6.72%   |
| IMC Networks                    | 27        | 5.04%   |
| Foxconn / Hon Hai               | 24        | 4.48%   |
| Lite-On Technology              | 23        | 4.29%   |
| Apple                           | 16        | 2.99%   |
| Dell                            | 15        | 2.8%    |
| Toshiba                         | 12        | 2.24%   |
| Hewlett-Packard                 | 12        | 2.24%   |
| Cambridge Silicon Radio         | 7         | 1.31%   |
| Ralink                          | 6         | 1.12%   |
| Foxconn International           | 4         | 0.75%   |
| ASUSTek Computer                | 4         | 0.75%   |
| Alps Electric                   | 3         | 0.56%   |
| Realtek                         | 2         | 0.37%   |
| Integrated System Solution      | 2         | 0.37%   |
| MediaTek                        | 1         | 0.19%   |
| Askey Computer                  | 1         | 0.19%   |
| Unknown                         | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 105       | 19.55%  |
| Realtek Bluetooth Radio                                                             | 47        | 8.75%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 31        | 5.77%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 29        | 5.4%    |
| Intel AX201 Bluetooth                                                               | 29        | 5.4%    |
| Intel AX200 Bluetooth                                                               | 19        | 3.54%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 13        | 2.42%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 12        | 2.23%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 11        | 2.05%   |
| IMC Networks Bluetooth Device                                                       | 11        | 2.05%   |
| Apple Bluetooth Host Controller                                                     | 11        | 2.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 9         | 1.68%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 9         | 1.68%   |
| IMC Networks Bluetooth Radio                                                        | 9         | 1.68%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 9         | 1.68%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 8         | 1.49%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 8         | 1.49%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 7         | 1.3%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 7         | 1.3%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 1.3%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 7         | 1.3%    |
| Ralink RT3290 Bluetooth                                                             | 6         | 1.12%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 5         | 0.93%   |
| Dell DW375 Bluetooth Module                                                         | 5         | 0.93%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 5         | 0.93%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 4         | 0.74%   |
| Lite-On Bluetooth Device                                                            | 4         | 0.74%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 4         | 0.74%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 4         | 0.74%   |
| Toshiba Bluetooth Device                                                            | 3         | 0.56%   |
| Toshiba BCM43142A0                                                                  | 3         | 0.56%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 3         | 0.56%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.56%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 0.56%   |
| Intel AX210 Bluetooth                                                               | 3         | 0.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 0.56%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 3         | 0.56%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 3         | 0.56%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 3         | 0.56%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 3         | 0.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 0.56%   |
| Apple Bluetooth HCI                                                                 | 3         | 0.56%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 3         | 0.56%   |
| Toshiba Integrated Bluetooth HCI                                                    | 2         | 0.37%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.37%   |
| Realtek Bluetooth Radio                                                             | 2         | 0.37%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 2         | 0.37%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 2         | 0.37%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.37%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.37%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 2         | 0.37%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.37%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 0.37%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 0.37%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.37%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 2         | 0.37%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.19%   |
| Toshiba BRCM Bluetooth Controller BCM2070                                           | 1         | 0.19%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.19%   |
| Toshiba Askey for                                                                   | 1         | 0.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 578       | 70.32%  |
| AMD                                  | 130       | 15.82%  |
| Nvidia                               | 96        | 11.68%  |
| SteelSeries ApS                      | 2         | 0.24%   |
| Realtek Semiconductor                | 2         | 0.24%   |
| Focusrite-Novation                   | 2         | 0.24%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.12%   |
| Tenx Technology                      | 1         | 0.12%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.12%   |
| Sennheiser Communications            | 1         | 0.12%   |
| Razer USA                            | 1         | 0.12%   |
| Lenovo                               | 1         | 0.12%   |
| GN Netcom                            | 1         | 0.12%   |
| Generalplus Technology               | 1         | 0.12%   |
| Creative Technology                  | 1         | 0.12%   |
| Corsair                              | 1         | 0.12%   |
| Conexant Systems                     | 1         | 0.12%   |
| C-Media Electronics                  | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 82        | 8.16%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 80        | 7.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 58        | 5.77%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 49        | 4.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 46        | 4.58%   |
| Intel 8 Series HD Audio Controller                                                                | 45        | 4.48%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 42        | 4.18%   |
| AMD FCH Azalia Controller                                                                         | 32        | 3.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 30        | 2.99%   |
| AMD Kabini HDMI/DP Audio                                                                          | 25        | 2.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 24        | 2.39%   |
| Intel Broadwell-U Audio Controller                                                                | 24        | 2.39%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 23        | 2.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 22        | 2.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 21        | 2.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 20        | 1.99%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 19        | 1.89%   |
| Intel Cannon Lake PCH cAVS                                                                        | 18        | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 16        | 1.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 16        | 1.59%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 16        | 1.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 15        | 1.49%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 14        | 1.39%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 14        | 1.39%   |
| Intel CM238 HD Audio Controller                                                                   | 14        | 1.39%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 1.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 14        | 1.39%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13        | 1.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 11        | 1.09%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 11        | 1.09%   |
| AMD High Definition Audio Controller                                                              | 11        | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10        | 1%      |
| Intel Comet Lake PCH cAVS                                                                         | 9         | 0.9%    |
| Nvidia High Definition Audio Controller                                                           | 8         | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 0.7%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 0.7%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 6         | 0.6%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 0.6%    |
| AMD Wrestler HDMI Audio                                                                           | 6         | 0.6%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 5         | 0.5%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 0.4%    |
| Nvidia Audio device                                                                               | 4         | 0.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 0.4%    |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.3%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.3%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.3%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.3%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.3%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.3%    |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.3%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.3%    |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.3%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.3%    |
| AMD RS780 HDMI Audio [Radeon 3000/3100 / HD 3200/3300]                                            | 3         | 0.3%    |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 0.3%    |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 0.3%    |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 3         | 0.3%    |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.2%    |
| Nvidia GF116 High Definition Audio Controller                                                     | 2         | 0.2%    |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.2%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 26.57%  |
| SK Hynix            | 34        | 23.78%  |
| Micron Technology   | 20        | 13.99%  |
| Unknown             | 9         | 6.29%   |
| Kingston            | 9         | 6.29%   |
| Unknown (ABCD)      | 7         | 4.9%    |
| A-DATA Technology   | 5         | 3.5%    |
| Nanya Technology    | 3         | 2.1%    |
| Crucial             | 3         | 2.1%    |
| Ramaxel Technology  | 2         | 1.4%    |
| Patriot             | 2         | 1.4%    |
| ELPIDA              | 2         | 1.4%    |
| Transcend           | 1         | 0.7%    |
| TIMETEC             | 1         | 0.7%    |
| Teikon              | 1         | 0.7%    |
| Team                | 1         | 0.7%    |
| Strontium           | 1         | 0.7%    |
| Smart               | 1         | 0.7%    |
| Puskill             | 1         | 0.7%    |
| AXIOM               | 1         | 0.7%    |
| Avant               | 1         | 0.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 6         | 4.03%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 4         | 2.68%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 4         | 2.68%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 2.01%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 2.01%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s              | 3         | 2.01%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 2         | 1.34%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 2         | 1.34%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 1.34%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s    | 2         | 1.34%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 2         | 1.34%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.34%   |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 2         | 1.34%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.34%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 2         | 1.34%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 2         | 1.34%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s            | 2         | 1.34%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 2         | 1.34%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s              | 2         | 1.34%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                         | 1         | 0.67%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                      | 1         | 0.67%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                        | 1         | 0.67%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 0.67%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.67%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1066MT/s                      | 1         | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s      | 1         | 0.67%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s              | 1         | 0.67%   |
| TIMETEC RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                       | 1         | 0.67%   |
| Teikon RAM TMT351S6EFR8A-PBHJ 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| Team RAM TEAMGROUP-SD4-2400 8192MB SODIMM DDR4 8400MT/s             | 1         | 0.67%   |
| Strontium RAM SRT4G86S1-P9H 4GB SODIMM DDR3 1600MT/s                | 1         | 0.67%   |
| Smart RAM SH564128FJ8NZRNSDG 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.67%   |
| SK Hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                   | 1         | 0.67%   |
| SK Hynix RAM HYMP112S64CP6-Y5 1GB SODIMM DDR 667MT/s                | 1         | 0.67%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.67%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.67%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.67%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.67%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.67%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s           | 1         | 0.67%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1334MT/s              | 1         | 0.67%   |
| SK Hynix RAM HMT112S6BFR6C-G7 1024MB SODIMM DDR3 1067MT/s           | 1         | 0.67%   |
| SK Hynix RAM HMP351S6AFR8C-S6 4GB SODIMM DDR2 800MT/s               | 1         | 0.67%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.67%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s           | 1         | 0.67%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.67%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.67%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.67%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.67%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 1         | 0.67%   |
| SK Hynix RAM HCNNNCPMBLHR-NEE 2GB Row Of Chips LPDDR4 4267MT/s      | 1         | 0.67%   |
| SK Hynix RAM H9CCNNNCPTMLBR-NTE 4096MB SODIMM LPDDR3 1600MT/s       | 1         | 0.67%   |
| Samsung RAM UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s          | 1         | 0.67%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s          | 1         | 0.67%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                      | 1         | 0.67%   |
| Samsung RAM Module 4096MB SODIMM LPDDR3 1600MT/s                    | 1         | 0.67%   |
| Samsung RAM M471B5773EB0-CK0 2048MB SODIMM DDR3 1600MT/s            | 1         | 0.67%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 1         | 0.67%   |
| Samsung RAM M471B5674BM0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 55        | 44.72%  |
| DDR3   | 41        | 33.33%  |
| LPDDR4 | 12        | 9.76%   |
| LPDDR3 | 7         | 5.69%   |
| SDRAM  | 4         | 3.25%   |
| DDR2   | 4         | 3.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 105       | 86.78%  |
| Row Of Chips | 14        | 11.57%  |
| DIMM         | 1         | 0.83%   |
| Chip         | 1         | 0.83%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 60        | 43.8%   |
| 8192  | 43        | 31.39%  |
| 2048  | 16        | 11.68%  |
| 16384 | 13        | 9.49%   |
| 1024  | 4         | 2.92%   |
| 32768 | 1         | 0.73%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 30        | 22.56%  |
| 1600    | 30        | 22.56%  |
| 3200    | 16        | 12.03%  |
| 2400    | 14        | 10.53%  |
| 1334    | 8         | 6.02%   |
| 2133    | 5         | 3.76%   |
| 4267    | 4         | 3.01%   |
| 3266    | 4         | 3.01%   |
| 1333    | 4         | 3.01%   |
| Unknown | 4         | 3.01%   |
| 800     | 3         | 2.26%   |
| 4199    | 2         | 1.5%    |
| 2048    | 2         | 1.5%    |
| 1867    | 2         | 1.5%    |
| 667     | 2         | 1.5%    |
| 8400    | 1         | 0.75%   |
| 1067    | 1         | 0.75%   |
| 1066    | 1         | 0.75%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 50%     |
| Canon               | 2         | 25%     |
| Seiko Epson         | 1         | 12.5%   |
| Samsung Electronics | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| Seiko Epson L3110 Series  | 1         | 12.5%   |
| Samsung M2020 Series      | 1         | 12.5%   |
| HP LaserJet 1200          | 1         | 12.5%   |
| HP LaserJet 1000          | 1         | 12.5%   |
| HP ENVY Photo 6200 series | 1         | 12.5%   |
| HP DeskJet 1110 series    | 1         | 12.5%   |
| Canon TS3100 series       | 1         | 12.5%   |
| Canon PIXMA MG3000 series | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 66.67%  |
| Canon       | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 66.67%  |
| Canon CanoScan LiDE 90                      | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 157       | 25.49%  |
| Realtek Semiconductor                  | 65        | 10.55%  |
| IMC Networks                           | 61        | 9.9%    |
| Microdia                               | 46        | 7.47%   |
| Acer                                   | 36        | 5.84%   |
| Sunplus Innovation Technology          | 33        | 5.36%   |
| Cheng Uei Precision Industry (Foxlink) | 33        | 5.36%   |
| Suyin                                  | 29        | 4.71%   |
| Quanta                                 | 27        | 4.38%   |
| Syntek                                 | 20        | 3.25%   |
| Apple                                  | 14        | 2.27%   |
| Ricoh                                  | 11        | 1.79%   |
| Silicon Motion                         | 10        | 1.62%   |
| Lite-On Technology                     | 10        | 1.62%   |
| Alcor Micro                            | 10        | 1.62%   |
| Primax Electronics                     | 6         | 0.97%   |
| Samsung Electronics                    | 5         | 0.81%   |
| Luxvisions Innotech Limited            | 4         | 0.65%   |
| USB Camera                             | 3         | 0.49%   |
| Sunplus Technology                     | 3         | 0.49%   |
| DJKANA1BIFZTDM                         | 3         | 0.49%   |
| ALi                                    | 3         | 0.49%   |
| Z-Star Microelectronics                | 2         | 0.32%   |
| Logitech                               | 2         | 0.32%   |
| Lenovo                                 | 2         | 0.32%   |
| Importek                               | 2         | 0.32%   |
| Genesys Logic                          | 2         | 0.32%   |
| YGTek                                  | 1         | 0.16%   |
| Y Media                                | 1         | 0.16%   |
| SunplusIT                              | 1         | 0.16%   |
| Sonix Technology                       | 1         | 0.16%   |
| Pixart Imaging                         | 1         | 0.16%   |
| Panasonic (Matsushita)                 | 1         | 0.16%   |
| OmniVision Technologies                | 1         | 0.16%   |
| Microsoft                              | 1         | 0.16%   |
| LG Electronics                         | 1         | 0.16%   |
| KYE Systems (Mouse Systems)            | 1         | 0.16%   |
| Huawei Technologies                    | 1         | 0.16%   |
| GenesysLogic Technology                | 1         | 0.16%   |
| Generalplus Technology                 | 1         | 0.16%   |
| GEMBIRD                                | 1         | 0.16%   |
| DigiTech                               | 1         | 0.16%   |
| Denron                                 | 1         | 0.16%   |
| ARC International                      | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 19        | 3.07%   |
| Chicony Integrated Camera                                                  | 19        | 3.07%   |
| Chicony HD WebCam                                                          | 18        | 2.91%   |
| Microdia Integrated_Webcam_HD                                              | 14        | 2.27%   |
| Realtek USB Camera                                                         | 12        | 1.94%   |
| Realtek Integrated_Webcam_HD                                               | 12        | 1.94%   |
| Chicony TOSHIBA Web Camera - HD                                            | 12        | 1.94%   |
| Microdia Integrated Webcam                                                 | 11        | 1.78%   |
| Acer Integrated Camera                                                     | 11        | 1.78%   |
| Syntek Integrated Camera                                                   | 10        | 1.62%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 9         | 1.46%   |
| IMC Networks Integrated Camera                                             | 9         | 1.46%   |
| Chicony HP TrueVision HD                                                   | 8         | 1.29%   |
| Acer Lenovo EasyCamera                                                     | 8         | 1.29%   |
| Sunplus Integrated_Webcam_HD                                               | 7         | 1.13%   |
| Sunplus HD WebCam                                                          | 6         | 0.97%   |
| Realtek Integrated Webcam                                                  | 6         | 0.97%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 6         | 0.97%   |
| Chicony Lenovo EasyCamera                                                  | 6         | 0.97%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 6         | 0.97%   |
| Syntek Lenovo EasyCamera                                                   | 5         | 0.81%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 5         | 0.81%   |
| Realtek Integrated Webcam HD                                               | 5         | 0.81%   |
| Quanta HP TrueVision HD Camera                                             | 5         | 0.81%   |
| Quanta HD User Facing                                                      | 5         | 0.81%   |
| Chicony VGA Webcam                                                         | 5         | 0.81%   |
| Chicony USB2.0 HD UVC WebCam                                               | 5         | 0.81%   |
| Chicony USB 2.0 Camera                                                     | 5         | 0.81%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 5         | 0.81%   |
| Chicony HP Webcam                                                          | 5         | 0.81%   |
| Chicony EasyCamera                                                         | 5         | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 5         | 0.81%   |
| Suyin Laptop_Integrated_Webcam_HD                                          | 4         | 0.65%   |
| Suyin HP TrueVision HD                                                     | 4         | 0.65%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 4         | 0.65%   |
| Ricoh USB2.0 Camera                                                        | 4         | 0.65%   |
| Realtek Lenovo EasyCamera                                                  | 4         | 0.65%   |
| Realtek HP Truevision HD integrated webcam                                 | 4         | 0.65%   |
| Quanta VGA WebCam                                                          | 4         | 0.65%   |
| Quanta HP Webcam                                                           | 4         | 0.65%   |
| Microdia Webcam Vitade AF                                                  | 4         | 0.65%   |
| Lite-On HP HD Camera                                                       | 4         | 0.65%   |
| Chicony HP Truevision HD camera                                            | 4         | 0.65%   |
| Chicony CNF9055 Toshiba Webcam                                             | 4         | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 4         | 0.65%   |
| Apple FaceTime HD Camera                                                   | 4         | 0.65%   |
| Alcor Micro USB 2.0 PC cam                                                 | 4         | 0.65%   |
| Alcor Micro Asus Integrated Webcam                                         | 4         | 0.65%   |
| Acer HD Webcam                                                             | 4         | 0.65%   |
| USB Camera USB Camera                                                      | 3         | 0.49%   |
| Suyin HD WebCam                                                            | 3         | 0.49%   |
| Suyin Acer/Lenovo Webcam [CN0316]                                          | 3         | 0.49%   |
| Sunplus ASUS Webcam                                                        | 3         | 0.49%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 3         | 0.49%   |
| Realtek HP Truevision HD                                                   | 3         | 0.49%   |
| Quanta HP Wide Vision HD Camera                                            | 3         | 0.49%   |
| Quanta HD Webcam                                                           | 3         | 0.49%   |
| Primax Villem                                                              | 3         | 0.49%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 3         | 0.49%   |
| IMC Networks USB2.0 HD IR UVC WebCam                                       | 3         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 52        | 46.02%  |
| Upek                       | 15        | 13.27%  |
| Shenzhen Goodix Technology | 13        | 11.5%   |
| AuthenTec                  | 12        | 10.62%  |
| Synaptics                  | 7         | 6.19%   |
| Elan Microelectronics      | 5         | 4.42%   |
| STMicroelectronics         | 4         | 3.54%   |
| LighTuning Technology      | 4         | 3.54%   |
| Focal-systems.Corp         | 1         | 0.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 14        | 12.39%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 10.62%  |
| Shenzhen Goodix  FingerPrint Device                                        | 7         | 6.19%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 5.31%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 3.54%   |
| Validity Sensors VFS491                                                    | 4         | 3.54%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 3.54%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 3.54%   |
| STMicroelectronics Fingerprint Reader                                      | 4         | 3.54%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 3.54%   |
| Elan ELAN:ARM-M4                                                           | 4         | 3.54%   |
| AuthenTec AES2810                                                          | 4         | 3.54%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 2.65%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.65%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 2.65%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.65%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 2.65%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 2.65%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 2.65%   |
| Unknown                                                                    | 3         | 2.65%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.77%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.77%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.77%   |
| AuthenTec AES1600                                                          | 2         | 1.77%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.88%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.88%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.88%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.88%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.88%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.88%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.88%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.88%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 31        | 59.62%  |
| Alcor Micro                       | 8         | 15.38%  |
| O2 Micro                          | 4         | 7.69%   |
| Yubico.com                        | 2         | 3.85%   |
| Upek                              | 2         | 3.85%   |
| Lenovo                            | 2         | 3.85%   |
| VASCO Data Security International | 1         | 1.92%   |
| SCM Microsystems                  | 1         | 1.92%   |
| OmniKey                           | 1         | 1.92%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 21.15%  |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 19.23%  |
| Broadcom 5880                                                                | 9         | 17.31%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 15.38%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 7.69%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 3.85%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.85%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.85%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 1.92%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 1.92%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 1.92%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.92%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 482       | 66.57%  |
| 1     | 188       | 25.97%  |
| 2     | 50        | 6.91%   |
| 3     | 4         | 0.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 112       | 38.23%  |
| Chipcard                 | 45        | 15.36%  |
| Graphics card            | 43        | 14.68%  |
| Multimedia controller    | 32        | 10.92%  |
| Net/wireless             | 28        | 9.56%   |
| Storage                  | 11        | 3.75%   |
| Bluetooth                | 8         | 2.73%   |
| Sound                    | 2         | 0.68%   |
| Net/ethernet             | 2         | 0.68%   |
| Flash memory             | 2         | 0.68%   |
| Camera                   | 2         | 0.68%   |
| Unclassified device      | 1         | 0.34%   |
| Storage/ide              | 1         | 0.34%   |
| Network                  | 1         | 0.34%   |
| Dvb card                 | 1         | 0.34%   |
| Communication controller | 1         | 0.34%   |
| Card reader              | 1         | 0.34%   |

