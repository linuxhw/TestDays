Linux in Ecuador - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Ecuador.

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

Total: 191

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| HP        | Notebook                    | [487cfc16fc](https://linux-hardware.org/?probe=487cfc16fc) | Aug 10, 2022 |
| Dell      | Inspiron 7472               | [eaab7f2460](https://linux-hardware.org/?probe=eaab7f2460) | Aug 09, 2022 |
| HP        | Laptop 14-cf3xxx            | [2f628ea3bb](https://linux-hardware.org/?probe=2f628ea3bb) | Aug 09, 2022 |
| Lenovo    | ThinkPad E590 20NB002AMH    | [aed42791cd](https://linux-hardware.org/?probe=aed42791cd) | Aug 09, 2022 |
| Dell      | Latitude E6420              | [3817e724ac](https://linux-hardware.org/?probe=3817e724ac) | Aug 08, 2022 |
| HP        | Laptop 14-cf3xxx            | [2f565b89db](https://linux-hardware.org/?probe=2f565b89db) | Aug 06, 2022 |
| HP        | Laptop 14-cf3xxx            | [f6caa753ba](https://linux-hardware.org/?probe=f6caa753ba) | Aug 04, 2022 |
| MSI       | GF63 Thin 9SC               | [6d42baa166](https://linux-hardware.org/?probe=6d42baa166) | Jul 26, 2022 |
| MSI       | GF63 Thin 9SC               | [1a2403b95a](https://linux-hardware.org/?probe=1a2403b95a) | Jul 24, 2022 |
| HP        | Laptop 14-cf3xxx            | [63722e3660](https://linux-hardware.org/?probe=63722e3660) | Jul 23, 2022 |
| Dell      | Latitude 5520               | [6e9be54f47](https://linux-hardware.org/?probe=6e9be54f47) | Jul 09, 2022 |
| Apple     | MacBookPro12,1              | [570dd2f164](https://linux-hardware.org/?probe=570dd2f164) | Jun 28, 2022 |
| Google    | Delbin                      | [26becdfc83](https://linux-hardware.org/?probe=26becdfc83) | Jun 26, 2022 |
| ASUSTek   | X555QG                      | [53e208736b](https://linux-hardware.org/?probe=53e208736b) | Jun 25, 2022 |
| Fujitsu   | LIFEBOOK E752               | [c434320a62](https://linux-hardware.org/?probe=c434320a62) | Jun 19, 2022 |
| ASUSTek   | X411UN                      | [70d24e4237](https://linux-hardware.org/?probe=70d24e4237) | Jun 02, 2022 |
| ASUSTek   | UX360CA                     | [63fac2dc9b](https://linux-hardware.org/?probe=63fac2dc9b) | May 29, 2022 |
| Alienware | 15 R3                       | [84df370117](https://linux-hardware.org/?probe=84df370117) | May 26, 2022 |
| HP        | Laptop 14-cf3xxx            | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| Chuwi     | HeroBook Pro                | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| Sony      | SVE14113ELW                 | [647c09a7be](https://linux-hardware.org/?probe=647c09a7be) | May 23, 2022 |
| Chuwi     | HeroBook Pro                | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| Lenovo    | G580 20150                  | [ec5867b2f7](https://linux-hardware.org/?probe=ec5867b2f7) | May 17, 2022 |
| Lenovo    | G580 20150                  | [9b06242456](https://linux-hardware.org/?probe=9b06242456) | May 17, 2022 |
| Toshiba   | Satellite L45-B             | [7f46e36f35](https://linux-hardware.org/?probe=7f46e36f35) | May 14, 2022 |
| Toshiba   | Satellite L45-B             | [81b3317aa8](https://linux-hardware.org/?probe=81b3317aa8) | May 14, 2022 |
| Dell      | XPS 13 9370                 | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Toshiba   | Satellite L50-B             | [e559318a8b](https://linux-hardware.org/?probe=e559318a8b) | May 02, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop X421... | [c8d977cf63](https://linux-hardware.org/?probe=c8d977cf63) | May 02, 2022 |
| HP        | Laptop 14-cf3xxx            | [e049bbd414](https://linux-hardware.org/?probe=e049bbd414) | Apr 26, 2022 |
| HP        | Unknown                     | [0a47967da0](https://linux-hardware.org/?probe=0a47967da0) | Apr 23, 2022 |
| HP        | Unknown                     | [fa5bba3e33](https://linux-hardware.org/?probe=fa5bba3e33) | Apr 22, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop X421... | [a0ad75fa4b](https://linux-hardware.org/?probe=a0ad75fa4b) | Apr 16, 2022 |
| HP        | Pavilion dv6                | [bacb1d04de](https://linux-hardware.org/?probe=bacb1d04de) | Apr 02, 2022 |
| Lenovo    | V15-IIL 82C5                | [722eee0995](https://linux-hardware.org/?probe=722eee0995) | Mar 30, 2022 |
| Sony      | VPCEG30EL                   | [c19f1a4739](https://linux-hardware.org/?probe=c19f1a4739) | Mar 26, 2022 |
| Sony      | SVE14A25CLB                 | [2e6afba454](https://linux-hardware.org/?probe=2e6afba454) | Mar 25, 2022 |
| Apple     | MacBookPro12,1              | [a39345cbf9](https://linux-hardware.org/?probe=a39345cbf9) | Mar 22, 2022 |
| Dell      | Inspiron 7547               | [af0de64399](https://linux-hardware.org/?probe=af0de64399) | Mar 22, 2022 |
| Razer     | Blade 15 Base Model (Ear... | [1ef1ffe2a3](https://linux-hardware.org/?probe=1ef1ffe2a3) | Mar 20, 2022 |
| Razer     | Blade Stealth               | [6b524f20d4](https://linux-hardware.org/?probe=6b524f20d4) | Mar 20, 2022 |
| HP        | Laptop 14-cf3xxx            | [faae36d70e](https://linux-hardware.org/?probe=faae36d70e) | Mar 17, 2022 |
| HP        | Laptop 14-cf3xxx            | [4d5aa250a1](https://linux-hardware.org/?probe=4d5aa250a1) | Mar 17, 2022 |
| Toshiba   | Satellite C55D-A            | [fccc5b2ef5](https://linux-hardware.org/?probe=fccc5b2ef5) | Mar 16, 2022 |
| ASUSTek   | ROG Zephyrus G14 GA401IH... | [c27fb51c94](https://linux-hardware.org/?probe=c27fb51c94) | Mar 13, 2022 |
| ASUSTek   | ROG Zephyrus G14 GA401IH... | [15b0517729](https://linux-hardware.org/?probe=15b0517729) | Mar 13, 2022 |
| HP        | 15 Notebook PC              | [d9e67c0484](https://linux-hardware.org/?probe=d9e67c0484) | Mar 12, 2022 |
| HP        | EliteBook Folio 9470m       | [bd4f7daadb](https://linux-hardware.org/?probe=bd4f7daadb) | Mar 10, 2022 |
| Compal    | PBL2021                     | [4e367db737](https://linux-hardware.org/?probe=4e367db737) | Feb 28, 2022 |
| Dell      | G5 5587                     | [5f51492976](https://linux-hardware.org/?probe=5f51492976) | Jan 29, 2022 |
| Dell      | Latitude 7280               | [fdf5a41dcc](https://linux-hardware.org/?probe=fdf5a41dcc) | Jan 25, 2022 |
| Dell      | Latitude 7280               | [b4c6f2fe35](https://linux-hardware.org/?probe=b4c6f2fe35) | Jan 25, 2022 |
| Dell      | Inspiron 3442               | [d8fc419747](https://linux-hardware.org/?probe=d8fc419747) | Jan 18, 2022 |
| Acer      | Aspire A515-56              | [359493a8bf](https://linux-hardware.org/?probe=359493a8bf) | Dec 27, 2021 |
| Acer      | Aspire A515-56              | [54cb3818f3](https://linux-hardware.org/?probe=54cb3818f3) | Dec 20, 2021 |
| Lenovo    | IdeaPad 330-15AST 81D6      | [ef48db912e](https://linux-hardware.org/?probe=ef48db912e) | Nov 24, 2021 |
| ASUSTek   | VivoBook_ASUSLaptop X712... | [c30cc4860b](https://linux-hardware.org/?probe=c30cc4860b) | Nov 24, 2021 |
| ASUSTek   | G750JX                      | [f503f26e28](https://linux-hardware.org/?probe=f503f26e28) | Nov 23, 2021 |
| Google    | Treeya                      | [a0ab206cd8](https://linux-hardware.org/?probe=a0ab206cd8) | Nov 09, 2021 |
| Dell      | Inspiron MP061              | [d6ed71bc78](https://linux-hardware.org/?probe=d6ed71bc78) | Nov 02, 2021 |
| HP        | G42                         | [5ee39658a8](https://linux-hardware.org/?probe=5ee39658a8) | Oct 28, 2021 |
| Timi      | RedmiBook 14-APCS           | [d31c8b483c](https://linux-hardware.org/?probe=d31c8b483c) | Oct 28, 2021 |
| HP        | G42                         | [a8181c9c9b](https://linux-hardware.org/?probe=a8181c9c9b) | Oct 24, 2021 |
| Fujitsu   | LIFEBOOK E752               | [177f79d880](https://linux-hardware.org/?probe=177f79d880) | Oct 18, 2021 |
| Lenovo    | IdeaPad 330S-15IKB 81F5     | [70e96b19b2](https://linux-hardware.org/?probe=70e96b19b2) | Oct 17, 2021 |
| Dell      | Inspiron 3593               | [2297765c40](https://linux-hardware.org/?probe=2297765c40) | Oct 14, 2021 |
| ASUSTek   | ASUS TUF Gaming A15 FA50... | [da1bab4a9c](https://linux-hardware.org/?probe=da1bab4a9c) | Oct 13, 2021 |
| HP        | 240 G6 Notebook PC          | [87b00b0a80](https://linux-hardware.org/?probe=87b00b0a80) | Oct 12, 2021 |
| Unknown   | Unknown                     | [449fdc2d2d](https://linux-hardware.org/?probe=449fdc2d2d) | Aug 23, 2021 |
| Unknown   | Unknown                     | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| Toshiba   | Satellite S55-B             | [c4ec7d25a7](https://linux-hardware.org/?probe=c4ec7d25a7) | Aug 21, 2021 |
| HP        | Pavilion g4                 | [3276092f1e](https://linux-hardware.org/?probe=3276092f1e) | Aug 15, 2021 |
| ASUSTek   | VivoBook 15_ASUS Laptop ... | [6909a1a841](https://linux-hardware.org/?probe=6909a1a841) | Aug 14, 2021 |
| Unknown   | Unknown                     | [008647318c](https://linux-hardware.org/?probe=008647318c) | Aug 09, 2021 |
| Unknown   | Unknown                     | [5de2d0ae61](https://linux-hardware.org/?probe=5de2d0ae61) | Aug 09, 2021 |
| ASUSTek   | VivoBook_ASUSLaptop X512... | [69c078f12b](https://linux-hardware.org/?probe=69c078f12b) | Aug 01, 2021 |
| Acer      | TravelMate X3410-M          | [18b5757039](https://linux-hardware.org/?probe=18b5757039) | Jul 29, 2021 |
| Toshiba   | Satellite S55-A             | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| Toshiba   | Satellite S55-A             | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| Toshiba   | Satellite C45-A             | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| Fujitsu   | LIFEBOOK E752               | [a071db12c9](https://linux-hardware.org/?probe=a071db12c9) | Jul 12, 2021 |
| Google    | Banjo                       | [d451dcd617](https://linux-hardware.org/?probe=d451dcd617) | Jul 02, 2021 |
| Google    | Grunt                       | [2bb0921a94](https://linux-hardware.org/?probe=2bb0921a94) | Jul 01, 2021 |
| Google    | Grunt                       | [4ea5c8f438](https://linux-hardware.org/?probe=4ea5c8f438) | Jul 01, 2021 |
| Google    | Kip                         | [7634152b76](https://linux-hardware.org/?probe=7634152b76) | Jun 21, 2021 |
| Acer      | TravelMate B117-M           | [a5fc625cf2](https://linux-hardware.org/?probe=a5fc625cf2) | Jun 04, 2021 |
| MSI       | GF63 Thin 9SC               | [54a4075ac5](https://linux-hardware.org/?probe=54a4075ac5) | May 16, 2021 |
| HP        | 1000                        | [d23f6c89ad](https://linux-hardware.org/?probe=d23f6c89ad) | May 15, 2021 |
| HP        | 1000                        | [a1ff0a7b3d](https://linux-hardware.org/?probe=a1ff0a7b3d) | May 13, 2021 |
| Acer      | Aspire V5-121               | [cc73e2b026](https://linux-hardware.org/?probe=cc73e2b026) | May 13, 2021 |
| HP        | 1000                        | [4bbe06ec7a](https://linux-hardware.org/?probe=4bbe06ec7a) | May 13, 2021 |
| Lenovo    | ThinkPad E15 20REA00000     | [1ac42dd429](https://linux-hardware.org/?probe=1ac42dd429) | May 09, 2021 |
| MSI       | GF63 Thin 9SC               | [cd6a799646](https://linux-hardware.org/?probe=cd6a799646) | Apr 29, 2021 |
| Lenovo    | IdeaPad 330S-15IKB 81F5     | [140e992105](https://linux-hardware.org/?probe=140e992105) | Apr 24, 2021 |
| Samsung   | 550XCJ/550XCR               | [2a2a56b6d4](https://linux-hardware.org/?probe=2a2a56b6d4) | Apr 22, 2021 |
| Dell      | Inspiron 3442               | [921cfbf363](https://linux-hardware.org/?probe=921cfbf363) | Apr 18, 2021 |
| Dell      | G5 5587                     | [c88e053304](https://linux-hardware.org/?probe=c88e053304) | Apr 07, 2021 |
| Dell      | Inspiron 3558               | [0ba2e43e56](https://linux-hardware.org/?probe=0ba2e43e56) | Mar 24, 2021 |
| HP        | ProBook 640 G2              | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| Lenovo    | ThinkPad T530 2429JB5       | [b3eee9be3e](https://linux-hardware.org/?probe=b3eee9be3e) | Mar 23, 2021 |
| Lenovo    | ThinkPad T530 2429JB5       | [e04914d4de](https://linux-hardware.org/?probe=e04914d4de) | Mar 23, 2021 |
| Dell      | Inspiron 1420               | [7b12363b97](https://linux-hardware.org/?probe=7b12363b97) | Mar 04, 2021 |
| Dell      | Inspiron 7375               | [eea996c7d4](https://linux-hardware.org/?probe=eea996c7d4) | Feb 26, 2021 |
| Lenovo    | ThinkPad X201 3680PKS       | [14a1f8c536](https://linux-hardware.org/?probe=14a1f8c536) | Feb 07, 2021 |
| Lenovo    | ThinkPad X201 3680PKS       | [f935adf770](https://linux-hardware.org/?probe=f935adf770) | Feb 07, 2021 |
| Dell      | Vostro 3480                 | [2162db2610](https://linux-hardware.org/?probe=2162db2610) | Feb 03, 2021 |
| Sony      | VPCCW1S1E                   | [f57d56b50e](https://linux-hardware.org/?probe=f57d56b50e) | Jan 31, 2021 |
| Dell      | Inspiron 15 7000 Gaming     | [f4e1001265](https://linux-hardware.org/?probe=f4e1001265) | Jan 23, 2021 |
| HP        | Laptop 14-cf3xxx            | [063b008ad5](https://linux-hardware.org/?probe=063b008ad5) | Jan 15, 2021 |
| HP        | Laptop 14-cf3xxx            | [473e0472d5](https://linux-hardware.org/?probe=473e0472d5) | Jan 12, 2021 |
| HP        | EliteBook 2730p             | [5a7277af8b](https://linux-hardware.org/?probe=5a7277af8b) | Jan 08, 2021 |
| HP        | EliteBook 2730p             | [bbbf68f88b](https://linux-hardware.org/?probe=bbbf68f88b) | Jan 08, 2021 |
| Google    | Parrot                      | [a3a6c2f819](https://linux-hardware.org/?probe=a3a6c2f819) | Jan 04, 2021 |
| Google    | Parrot                      | [55b807260c](https://linux-hardware.org/?probe=55b807260c) | Jan 04, 2021 |
| HP        | Pavilion 14                 | [91b047b61a](https://linux-hardware.org/?probe=91b047b61a) | Dec 31, 2020 |
| Gateway   | NE56R                       | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| HP        | Laptop 14-cf3xxx            | [3f61162824](https://linux-hardware.org/?probe=3f61162824) | Dec 07, 2020 |
| Dell      | Inspiron 1420               | [e5dab19c0f](https://linux-hardware.org/?probe=e5dab19c0f) | Dec 05, 2020 |
| HP        | ProBook 4440s               | [b4747f87a1](https://linux-hardware.org/?probe=b4747f87a1) | Nov 24, 2020 |
| Dell      | Inspiron 1750               | [612608a41f](https://linux-hardware.org/?probe=612608a41f) | Nov 21, 2020 |
| Dell      | Latitude D430               | [77ef794b1d](https://linux-hardware.org/?probe=77ef794b1d) | Nov 21, 2020 |
| Dell      | Latitude D430               | [c028c146b6](https://linux-hardware.org/?probe=c028c146b6) | Nov 21, 2020 |
| Fujitsu   | LIFEBOOK E752               | [364a814fd0](https://linux-hardware.org/?probe=364a814fd0) | Nov 19, 2020 |
| Fujitsu   | LIFEBOOK E752               | [b0fbbd8176](https://linux-hardware.org/?probe=b0fbbd8176) | Nov 19, 2020 |
| HP        | 3115m                       | [1ae9651614](https://linux-hardware.org/?probe=1ae9651614) | Nov 17, 2020 |
| Gateway   | NE56R                       | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| ASUSTek   | X510UAR                     | [106453a877](https://linux-hardware.org/?probe=106453a877) | Oct 23, 2020 |
| ASUSTek   | X510UAR                     | [fea6f132fa](https://linux-hardware.org/?probe=fea6f132fa) | Oct 23, 2020 |
| Toshiba   | PORTEGE M805                | [cacfe4abd9](https://linux-hardware.org/?probe=cacfe4abd9) | Oct 22, 2020 |
| Toshiba   | Satellite C55-B             | [146545f430](https://linux-hardware.org/?probe=146545f430) | Oct 17, 2020 |
| Toshiba   | Satellite C55-B             | [61e809ea3a](https://linux-hardware.org/?probe=61e809ea3a) | Oct 12, 2020 |
| Toshiba   | Satellite C55-B             | [6353946b7e](https://linux-hardware.org/?probe=6353946b7e) | Oct 12, 2020 |
| Dell      | Inspiron 1420               | [03631f1005](https://linux-hardware.org/?probe=03631f1005) | Oct 08, 2020 |
| Dell      | Inspiron 1420               | [78e7085775](https://linux-hardware.org/?probe=78e7085775) | Oct 08, 2020 |
| Sony      | VGN-CR120E                  | [3e989ff916](https://linux-hardware.org/?probe=3e989ff916) | Sep 24, 2020 |
| Sony      | VGN-CR120E                  | [8569f91c17](https://linux-hardware.org/?probe=8569f91c17) | Sep 23, 2020 |
| Toshiba   | Satellite C45-A             | [2774da64f6](https://linux-hardware.org/?probe=2774da64f6) | Sep 18, 2020 |
| HP        | Pavilion 15                 | [f824ed9d26](https://linux-hardware.org/?probe=f824ed9d26) | Sep 18, 2020 |
| HP        | Mini 210-1100               | [3b76e02a8f](https://linux-hardware.org/?probe=3b76e02a8f) | Sep 17, 2020 |
| HP        | Pavilion 15                 | [d95e413136](https://linux-hardware.org/?probe=d95e413136) | Sep 16, 2020 |
| HP        | Laptop 14-cf3xxx            | [489cee4d9a](https://linux-hardware.org/?probe=489cee4d9a) | Sep 12, 2020 |
| Toshiba   | Satellite P775              | [d71ccb1065](https://linux-hardware.org/?probe=d71ccb1065) | Sep 10, 2020 |
| HP        | Pavilion dv2500             | [8626b52852](https://linux-hardware.org/?probe=8626b52852) | Sep 08, 2020 |
| Samsung   | 530U4E/540U4E               | [31a023d519](https://linux-hardware.org/?probe=31a023d519) | Sep 06, 2020 |
| Samsung   | 530U4E/540U4E               | [d94a252a6f](https://linux-hardware.org/?probe=d94a252a6f) | Sep 06, 2020 |
| HP        | Laptop 14-cf3xxx            | [c3f5f6d566](https://linux-hardware.org/?probe=c3f5f6d566) | Sep 06, 2020 |
| HP        | Laptop 14-cf3xxx            | [4e0f1689a3](https://linux-hardware.org/?probe=4e0f1689a3) | Sep 06, 2020 |
| Dell      | Inspiron 5570               | [8eb7cfa128](https://linux-hardware.org/?probe=8eb7cfa128) | Sep 05, 2020 |
| HP        | Laptop 14-df0xxx            | [1b11abd994](https://linux-hardware.org/?probe=1b11abd994) | Sep 04, 2020 |
| Lenovo    | IdeaPad 320-15IKB 80XL      | [21f0c0015c](https://linux-hardware.org/?probe=21f0c0015c) | Aug 26, 2020 |
| HP        | Pavilion Laptop 15-cw1xx... | [29f01daf9e](https://linux-hardware.org/?probe=29f01daf9e) | Aug 26, 2020 |
| Dell      | Inspiron N4050              | [e39ccc961c](https://linux-hardware.org/?probe=e39ccc961c) | Aug 20, 2020 |
| HP        | Pavilion Laptop 15-cw1xx... | [dd8aa75b79](https://linux-hardware.org/?probe=dd8aa75b79) | Aug 16, 2020 |
| ASUSTek   | X502CA                      | [7876d4c48d](https://linux-hardware.org/?probe=7876d4c48d) | Aug 14, 2020 |
| Lenovo    | IdeaPad 320-15ABR 80XS      | [9bcbc98b0f](https://linux-hardware.org/?probe=9bcbc98b0f) | Jul 26, 2020 |
| Lenovo    | IdeaPad 330-14IGM 81D0      | [c32745014a](https://linux-hardware.org/?probe=c32745014a) | Jul 22, 2020 |
| Lenovo    | IdeaPad L340-15IRH Gamin... | [a70d38c48c](https://linux-hardware.org/?probe=a70d38c48c) | Jul 20, 2020 |
| Acer      | AO722                       | [90943ce018](https://linux-hardware.org/?probe=90943ce018) | Jul 10, 2020 |
| Dell      | Inspiron 7375               | [e4318a8dea](https://linux-hardware.org/?probe=e4318a8dea) | Jul 04, 2020 |
| Dell      | Inspiron 7375               | [ba6d8528e9](https://linux-hardware.org/?probe=ba6d8528e9) | Jul 04, 2020 |
| HP        | Notebook                    | [b646ab05a7](https://linux-hardware.org/?probe=b646ab05a7) | Jun 30, 2020 |
| Lenovo    | IdeaPad 320-15ABR 80XS      | [b8b588701d](https://linux-hardware.org/?probe=b8b588701d) | Jun 22, 2020 |
| Lenovo    | 3000 V200 076433G           | [3d55960409](https://linux-hardware.org/?probe=3d55960409) | Jun 13, 2020 |
| Lenovo    | 3000 V200 076433G           | [1de1a4dbc4](https://linux-hardware.org/?probe=1de1a4dbc4) | Jun 13, 2020 |
| HP        | ProBook 4440s               | [5442b989be](https://linux-hardware.org/?probe=5442b989be) | May 30, 2020 |
| Dell      | Inspiron 5570               | [84339f57da](https://linux-hardware.org/?probe=84339f57da) | May 09, 2020 |
| Apple     | MacBookPro13,3              | [81946cb76f](https://linux-hardware.org/?probe=81946cb76f) | Apr 17, 2020 |
| Lenovo    | IdeaPad 320-15ABR 80XS      | [df8a7bcad8](https://linux-hardware.org/?probe=df8a7bcad8) | Mar 26, 2020 |
| Lenovo    | G710 20252                  | [2971fd6031](https://linux-hardware.org/?probe=2971fd6031) | Mar 26, 2020 |
| HP        | 15                          | [cb0cf73a5d](https://linux-hardware.org/?probe=cb0cf73a5d) | Mar 04, 2020 |
| HP        | 15                          | [687592ff11](https://linux-hardware.org/?probe=687592ff11) | Mar 04, 2020 |
| Acer      | AO722                       | [08d71a347b](https://linux-hardware.org/?probe=08d71a347b) | Feb 29, 2020 |
| Acer      | AO722                       | [291cea2763](https://linux-hardware.org/?probe=291cea2763) | Feb 29, 2020 |
| HP        | Pavilion Laptop 15-cw0xx... | [108b4a03ac](https://linux-hardware.org/?probe=108b4a03ac) | Feb 26, 2020 |
| ASUSTek   | UX303LA                     | [5ae0871de5](https://linux-hardware.org/?probe=5ae0871de5) | Feb 23, 2020 |
| ASUSTek   | UX303LA                     | [cfc85f91d5](https://linux-hardware.org/?probe=cfc85f91d5) | Feb 22, 2020 |
| ASUSTek   | UX303LA                     | [ab03f678e6](https://linux-hardware.org/?probe=ab03f678e6) | Feb 22, 2020 |
| Lenovo    | IdeaPad 320-15ABR 80XS      | [d2b7a56172](https://linux-hardware.org/?probe=d2b7a56172) | Jan 14, 2020 |
| Lenovo    | IdeaPad 320-15ABR 80XS      | [30baa09d89](https://linux-hardware.org/?probe=30baa09d89) | Jan 14, 2020 |
| Acer      | Aspire ES1-131              | [fcb74db0f2](https://linux-hardware.org/?probe=fcb74db0f2) | Jan 14, 2020 |
| HP        | Laptop 14-bs0xx             | [bd6b795d81](https://linux-hardware.org/?probe=bd6b795d81) | Nov 09, 2019 |
| Dell      | System XPS L502X            | [d43cf2a533](https://linux-hardware.org/?probe=d43cf2a533) | Sep 12, 2019 |
| HP        | Pavilion Laptop 15-cc1xx    | [a4264e7371](https://linux-hardware.org/?probe=a4264e7371) | Sep 12, 2019 |
| Toshiba   | Satellite E45t-B            | [156d965d57](https://linux-hardware.org/?probe=156d965d57) | Aug 14, 2019 |
| Toshiba   | Satellite P55W-C            | [cc12571867](https://linux-hardware.org/?probe=cc12571867) | Jul 27, 2019 |
| HP        | Laptop 15-da0xxx            | [76dbbe880b](https://linux-hardware.org/?probe=76dbbe880b) | Jul 10, 2019 |
| HP        | Pavilion 14                 | [6dde2ab979](https://linux-hardware.org/?probe=6dde2ab979) | Jun 08, 2019 |
| Apple     | MacBook1,1                  | [57ca5e1449](https://linux-hardware.org/?probe=57ca5e1449) | Jun 02, 2019 |
| HP        | Pavilion Laptop 15-cw0xx... | [a4d0b9a0cc](https://linux-hardware.org/?probe=a4d0b9a0cc) | May 27, 2019 |
| HP        | Pavilion Laptop 15-cc1xx    | [6abf9ea94e](https://linux-hardware.org/?probe=6abf9ea94e) | Apr 17, 2019 |
| HP        | ENVY Notebook               | [4d812e744e](https://linux-hardware.org/?probe=4d812e744e) | Apr 17, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Ubuntu 20.04         | 23        | 16.91%  |
| Ubuntu 18.04         | 11        | 8.09%   |
| Linux Mint 20.3      | 7         | 5.15%   |
| Ubuntu 22.04         | 5         | 3.68%   |
| Linux Mint 19.3      | 5         | 3.68%   |
| KDE neon 20.04       | 5         | 3.68%   |
| Debian 11            | 5         | 3.68%   |
| Zorin 15             | 4         | 2.94%   |
| OpenMandriva 4.3     | 4         | 2.94%   |
| Pop!_OS 21.10        | 3         | 2.21%   |
| Fedora 34            | 3         | 2.21%   |
| Fedora 33            | 3         | 2.21%   |
| Zorin 16             | 2         | 1.47%   |
| Xubuntu 20.04        | 2         | 1.47%   |
| Ubuntu 21.10         | 2         | 1.47%   |
| Ubuntu 21.04         | 2         | 1.47%   |
| Ubuntu               | 2         | 1.47%   |
| Pop!_OS 21.04        | 2         | 1.47%   |
| Pop!_OS 20.04        | 2         | 1.47%   |
| LMDE 4               | 2         | 1.47%   |
| Linux Mint 20.1      | 2         | 1.47%   |
| Linux Mint 20        | 2         | 1.47%   |
| Elementary 5.1.7     | 2         | 1.47%   |
| BlackPanther 18.1    | 2         | 1.47%   |
| Xubuntu 18.04        | 1         | 0.74%   |
| Void Linux           | 1         | 0.74%   |
| Ubuntu MATE 20.04    | 1         | 0.74%   |
| Ubuntu MATE 18.04    | 1         | 0.74%   |
| Ubuntu Budgie 22.04  | 1         | 0.74%   |
| Ubuntu Budgie 20.04  | 1         | 0.74%   |
| Ubuntu 20.10         | 1         | 0.74%   |
| Ubuntu 19.04         | 1         | 0.74%   |
| Ubuntu 18.10         | 1         | 0.74%   |
| RHEL 8               | 1         | 0.74%   |
| OpenMandriva 4.2     | 1         | 0.74%   |
| Manjaro 21.3.5       | 1         | 0.74%   |
| Manjaro 21.2.5       | 1         | 0.74%   |
| Manjaro 20.1         | 1         | 0.74%   |
| Manjaro              | 1         | 0.74%   |
| Lubuntu 20.04        | 1         | 0.74%   |
| Lubuntu 18.04        | 1         | 0.74%   |
| LMDE 5               | 1         | 0.74%   |
| Linux Mint 20.2      | 1         | 0.74%   |
| Kubuntu 22.04        | 1         | 0.74%   |
| Kubuntu 20.04        | 1         | 0.74%   |
| KDE neon 18.04       | 1         | 0.74%   |
| Garuda Linux Soaring | 1         | 0.74%   |
| Fedora 36            | 1         | 0.74%   |
| Fedora 35            | 1         | 0.74%   |
| Fedora 32            | 1         | 0.74%   |
| Fedora 31            | 1         | 0.74%   |
| Endless 3.9.4        | 1         | 0.74%   |
| Elementary 5.1.2     | 1         | 0.74%   |
| Deepin 20            | 1         | 0.74%   |
| Debian 10            | 1         | 0.74%   |
| ArcoLinux Rolling    | 1         | 0.74%   |
| Arch Rolling         | 1         | 0.74%   |
| Arch                 | 1         | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 46        | 35.38%  |
| Linux Mint    | 15        | 11.54%  |
| Fedora        | 10        | 7.69%   |
| Pop!_OS       | 7         | 5.38%   |
| Zorin         | 6         | 4.62%   |
| KDE neon      | 6         | 4.62%   |
| Debian        | 6         | 4.62%   |
| OpenMandriva  | 5         | 3.85%   |
| Xubuntu       | 3         | 2.31%   |
| Manjaro       | 3         | 2.31%   |
| Elementary    | 3         | 2.31%   |
| Ubuntu MATE   | 2         | 1.54%   |
| Ubuntu Budgie | 2         | 1.54%   |
| Lubuntu       | 2         | 1.54%   |
| LMDE          | 2         | 1.54%   |
| Kubuntu       | 2         | 1.54%   |
| BlackPanther  | 2         | 1.54%   |
| Arch          | 2         | 1.54%   |
| Void Linux    | 1         | 0.77%   |
| RHEL          | 1         | 0.77%   |
| Garuda Linux  | 1         | 0.77%   |
| Endless       | 1         | 0.77%   |
| Deepin        | 1         | 0.77%   |
| ArcoLinux     | 1         | 0.77%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-54-generic         | 4         | 2.68%   |
| 5.4.0-42-generic         | 4         | 2.68%   |
| 5.15.0-33-generic        | 4         | 2.68%   |
| 5.13.0-35-generic        | 4         | 2.68%   |
| 5.4.0-58-generic         | 3         | 2.01%   |
| 5.4.0-56-generic         | 3         | 2.01%   |
| 5.4.0-48-generic         | 3         | 2.01%   |
| 5.4.0-45-generic         | 3         | 2.01%   |
| 5.4.0-26-generic         | 3         | 2.01%   |
| 5.16.7-desktop-1omv4003  | 3         | 2.01%   |
| 5.16.11-76051611-generic | 3         | 2.01%   |
| 5.8.0-43-generic         | 2         | 1.34%   |
| 5.8.0-41-generic         | 2         | 1.34%   |
| 5.4.0-77-generic         | 2         | 1.34%   |
| 5.4.0-7634-generic       | 2         | 1.34%   |
| 5.4.0-110-generic        | 2         | 1.34%   |
| 5.3.0-62-generic         | 2         | 1.34%   |
| 5.15.59-xanmod1          | 2         | 1.34%   |
| 5.15.0-27-generic        | 2         | 1.34%   |
| 5.13.0-7614-generic      | 2         | 1.34%   |
| 5.13.0-51-generic        | 2         | 1.34%   |
| 5.13.0-27-generic        | 2         | 1.34%   |
| 5.0.0-37-generic         | 2         | 1.34%   |
| 5.0.0-23-generic         | 2         | 1.34%   |
| 4.18.16-desktop-1bP      | 2         | 1.34%   |
| 4.15.0-54-generic        | 2         | 1.34%   |
| 5.9.16-200.fc33.x86_64   | 1         | 0.67%   |
| 5.8.15-201.fc32.x86_64   | 1         | 0.67%   |
| 5.8.0-45-generic         | 1         | 0.67%   |
| 5.8.0-14-generic         | 1         | 0.67%   |
| 5.7.17-2-MANJARO         | 1         | 0.67%   |
| 5.7.1-050701-generic     | 1         | 0.67%   |
| 5.5.5-arch1-1            | 1         | 0.67%   |
| 5.5.16-200.fc31.x86_64   | 1         | 0.67%   |
| 5.4.50-amd64-desktop     | 1         | 0.67%   |
| 5.4.26-rt17-1-rt         | 1         | 0.67%   |
| 5.4.111                  | 1         | 0.67%   |
| 5.4.0-94-generic         | 1         | 0.67%   |
| 5.4.0-90-generic         | 1         | 0.67%   |
| 5.4.0-89-generic         | 1         | 0.67%   |
| 5.4.0-88-generic         | 1         | 0.67%   |
| 5.4.0-80-generic         | 1         | 0.67%   |
| 5.4.0-74-generic         | 1         | 0.67%   |
| 5.4.0-72-generic         | 1         | 0.67%   |
| 5.4.0-70-generic         | 1         | 0.67%   |
| 5.4.0-67-generic         | 1         | 0.67%   |
| 5.4.0-66-generic         | 1         | 0.67%   |
| 5.4.0-65-generic         | 1         | 0.67%   |
| 5.4.0-60-generic         | 1         | 0.67%   |
| 5.4.0-53-generic         | 1         | 0.67%   |
| 5.4.0-52-generic         | 1         | 0.67%   |
| 5.4.0-47-generic         | 1         | 0.67%   |
| 5.4.0-40-generic         | 1         | 0.67%   |
| 5.4.0-37-generic         | 1         | 0.67%   |
| 5.4.0-33-generic         | 1         | 0.67%   |
| 5.4.0-109-generic        | 1         | 0.67%   |
| 5.4.0-105-generic        | 1         | 0.67%   |
| 5.3.9_1                  | 1         | 0.67%   |
| 5.3.0-42-generic         | 1         | 0.67%   |
| 5.3.0-40-generic         | 1         | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.4.0    | 42        | 30%     |
| 5.13.0   | 13        | 9.29%   |
| 5.15.0   | 8         | 5.71%   |
| 4.15.0   | 8         | 5.71%   |
| 5.0.0    | 7         | 5%      |
| 5.8.0    | 6         | 4.29%   |
| 5.11.0   | 5         | 3.57%   |
| 5.3.0    | 4         | 2.86%   |
| 5.10.0   | 4         | 2.86%   |
| 5.16.7   | 3         | 2.14%   |
| 5.16.11  | 3         | 2.14%   |
| 5.15.59  | 2         | 1.43%   |
| 4.18.16  | 2         | 1.43%   |
| 4.18.0   | 2         | 1.43%   |
| 5.9.16   | 1         | 0.71%   |
| 5.8.15   | 1         | 0.71%   |
| 5.7.17   | 1         | 0.71%   |
| 5.7.1    | 1         | 0.71%   |
| 5.5.5    | 1         | 0.71%   |
| 5.5.16   | 1         | 0.71%   |
| 5.4.50   | 1         | 0.71%   |
| 5.4.26   | 1         | 0.71%   |
| 5.4.111  | 1         | 0.71%   |
| 5.3.9    | 1         | 0.71%   |
| 5.18.6   | 1         | 0.71%   |
| 5.18.12  | 1         | 0.71%   |
| 5.17.5   | 1         | 0.71%   |
| 5.16.15  | 1         | 0.71%   |
| 5.16.13  | 1         | 0.71%   |
| 5.16.0   | 1         | 0.71%   |
| 5.15.7   | 1         | 0.71%   |
| 5.15.56  | 1         | 0.71%   |
| 5.14.11  | 1         | 0.71%   |
| 5.14.10  | 1         | 0.71%   |
| 5.14.0   | 1         | 0.71%   |
| 5.12.9   | 1         | 0.71%   |
| 5.12.1   | 1         | 0.71%   |
| 5.12.0   | 1         | 0.71%   |
| 5.11.16  | 1         | 0.71%   |
| 5.11.11  | 1         | 0.71%   |
| 5.10.79  | 1         | 0.71%   |
| 5.10.14  | 1         | 0.71%   |
| 5.10.105 | 1         | 0.71%   |
| 4.9.0    | 1         | 0.71%   |
| 4.19.0   | 1         | 0.71%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 45        | 32.61%  |
| 5.13    | 13        | 9.42%   |
| 5.15    | 11        | 7.97%   |
| 5.16    | 9         | 6.52%   |
| 4.15    | 8         | 5.8%    |
| 5.8     | 7         | 5.07%   |
| 5.11    | 7         | 5.07%   |
| 5.10    | 7         | 5.07%   |
| 5.0     | 7         | 5.07%   |
| 5.3     | 5         | 3.62%   |
| 4.18    | 4         | 2.9%    |
| 5.14    | 3         | 2.17%   |
| 5.7     | 2         | 1.45%   |
| 5.5     | 2         | 1.45%   |
| 5.18    | 2         | 1.45%   |
| 5.12    | 2         | 1.45%   |
| 5.9     | 1         | 0.72%   |
| 5.17    | 1         | 0.72%   |
| 4.9     | 1         | 0.72%   |
| 4.19    | 1         | 0.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 115       | 92%     |
| i686   | 10        | 8%      |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 57        | 44.19%  |
| Unknown    | 18        | 13.95%  |
| X-Cinnamon | 14        | 10.85%  |
| KDE5       | 13        | 10.08%  |
| XFCE       | 7         | 5.43%   |
| KDE        | 5         | 3.88%   |
| MATE       | 4         | 3.1%    |
| Pantheon   | 3         | 2.33%   |
| Budgie     | 2         | 1.55%   |
| qtile      | 1         | 0.78%   |
| LXQt       | 1         | 0.78%   |
| LXDE       | 1         | 0.78%   |
| jwm        | 1         | 0.78%   |
| ICEWM      | 1         | 0.78%   |
| Deepin     | 1         | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 101       | 77.1%   |
| Wayland | 19        | 14.5%   |
| Unknown | 11        | 8.4%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 79        | 60.77%  |
| GDM     | 16        | 12.31%  |
| SDDM    | 14        | 10.77%  |
| GDM3    | 10        | 7.69%   |
| LightDM | 8         | 6.15%   |
| TDM     | 3         | 2.31%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_EC   | 67        | 52.76%  |
| en_US   | 28        | 22.05%  |
| Unknown | 13        | 10.24%  |
| es_ES   | 11        | 8.66%   |
| de_DE   | 2         | 1.57%   |
| C       | 2         | 1.57%   |
| ru_RU   | 1         | 0.79%   |
| fr_FR   | 1         | 0.79%   |
| es_US   | 1         | 0.79%   |
| es_PE   | 1         | 0.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 66        | 51.16%  |
| BIOS | 63        | 48.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 106       | 82.17%  |
| Overlay | 10        | 7.75%   |
| Btrfs   | 8         | 6.2%    |
| Zfs     | 1         | 0.78%   |
| Xfs     | 1         | 0.78%   |
| Tmpfs   | 1         | 0.78%   |
| Ext2    | 1         | 0.78%   |
| Unknown | 1         | 0.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 83        | 65.35%  |
| GPT     | 34        | 26.77%  |
| MBR     | 10        | 7.87%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 112       | 88.89%  |
| Yes       | 14        | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 91        | 71.65%  |
| Yes       | 36        | 28.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 29        | 23.2%   |
| Dell                | 24        | 19.2%   |
| Lenovo              | 15        | 12%     |
| ASUSTek Computer    | 13        | 10.4%   |
| Toshiba             | 11        | 8.8%    |
| Google              | 6         | 4.8%    |
| Acer                | 6         | 4.8%    |
| Sony                | 5         | 4%      |
| Apple               | 3         | 2.4%    |
| Samsung Electronics | 2         | 1.6%    |
| Razer               | 2         | 1.6%    |
| Unknown             | 2         | 1.6%    |
| Timi                | 1         | 0.8%    |
| MSI                 | 1         | 0.8%    |
| Gateway             | 1         | 0.8%    |
| Fujitsu             | 1         | 0.8%    |
| Compal              | 1         | 0.8%    |
| Chuwi               | 1         | 0.8%    |
| Alienware           | 1         | 0.8%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown                                            | 3         | 2.4%    |
| Lenovo IdeaPad 320-15ABR 80XS                      | 2         | 1.6%    |
| HP ProBook 4440s                                   | 2         | 1.6%    |
| HP Pavilion Laptop 15-cw0xxx                       | 2         | 1.6%    |
| HP Notebook                                        | 2         | 1.6%    |
| Dell Inspiron 5570                                 | 2         | 1.6%    |
| Dell Inspiron 3442                                 | 2         | 1.6%    |
| Dell Inspiron 1420                                 | 2         | 1.6%    |
| Dell G5 5587                                       | 2         | 1.6%    |
| Toshiba Satellite S55-B                            | 1         | 0.8%    |
| Toshiba Satellite S55-A                            | 1         | 0.8%    |
| Toshiba Satellite P775                             | 1         | 0.8%    |
| Toshiba Satellite P55W-C                           | 1         | 0.8%    |
| Toshiba Satellite L50-B                            | 1         | 0.8%    |
| Toshiba Satellite L45-B                            | 1         | 0.8%    |
| Toshiba Satellite E45t-B                           | 1         | 0.8%    |
| Toshiba Satellite C55D-A                           | 1         | 0.8%    |
| Toshiba Satellite C55-B                            | 1         | 0.8%    |
| Toshiba Satellite C45-A                            | 1         | 0.8%    |
| Toshiba PORTEGE M805                               | 1         | 0.8%    |
| Timi RedmiBook 14-APCS                             | 1         | 0.8%    |
| Sony VPCEG30EL                                     | 1         | 0.8%    |
| Sony VPCCW1S1E                                     | 1         | 0.8%    |
| Sony VGN-CR120E                                    | 1         | 0.8%    |
| Sony SVE14A25CLB                                   | 1         | 0.8%    |
| Sony SVE14113ELW                                   | 1         | 0.8%    |
| Samsung 550XCJ/550XCR                              | 1         | 0.8%    |
| Samsung 530U4E/540U4E                              | 1         | 0.8%    |
| Razer Blade Stealth                                | 1         | 0.8%    |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.8%    |
| MSI GF63 Thin 9SC                                  | 1         | 0.8%    |
| Lenovo V15-IIL 82C5                                | 1         | 0.8%    |
| Lenovo ThinkPad X201 3680PKS                       | 1         | 0.8%    |
| Lenovo ThinkPad T530 2429JB5                       | 1         | 0.8%    |
| Lenovo ThinkPad E590 20NB002AMH                    | 1         | 0.8%    |
| Lenovo ThinkPad E15 20REA00000                     | 1         | 0.8%    |
| Lenovo IdeaPad L340-15IRH Gaming 81LK              | 1         | 0.8%    |
| Lenovo IdeaPad 330S-15IKB 81F5                     | 1         | 0.8%    |
| Lenovo IdeaPad 330-15AST 81D6                      | 1         | 0.8%    |
| Lenovo IdeaPad 330-14IGM 81D0                      | 1         | 0.8%    |
| Lenovo IdeaPad 320-15IKB 80XL                      | 1         | 0.8%    |
| Lenovo G710 20252                                  | 1         | 0.8%    |
| Lenovo G580 20150                                  | 1         | 0.8%    |
| Lenovo 3000 V200 076433G                           | 1         | 0.8%    |
| HP ProBook 640 G2                                  | 1         | 0.8%    |
| HP Pavilion Laptop 15-cw1xxx                       | 1         | 0.8%    |
| HP Pavilion Laptop 15-cc1xx                        | 1         | 0.8%    |
| HP Pavilion g4                                     | 1         | 0.8%    |
| HP Pavilion dv6                                    | 1         | 0.8%    |
| HP Pavilion dv2500                                 | 1         | 0.8%    |
| HP Pavilion 15                                     | 1         | 0.8%    |
| HP Pavilion 14                                     | 1         | 0.8%    |
| HP Mini 210-1100                                   | 1         | 0.8%    |
| HP Laptop 15-da0xxx                                | 1         | 0.8%    |
| HP Laptop 14-df0xxx                                | 1         | 0.8%    |
| HP Laptop 14-cf3xxx                                | 1         | 0.8%    |
| HP Laptop 14-bs0xx                                 | 1         | 0.8%    |
| HP G42                                             | 1         | 0.8%    |
| HP ENVY Notebook                                   | 1         | 0.8%    |
| HP EliteBook Folio 9470m                           | 1         | 0.8%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Dell Inspiron      | 15        | 12%     |
| Toshiba Satellite  | 10        | 8%      |
| HP Pavilion        | 9         | 7.2%    |
| Lenovo IdeaPad     | 7         | 5.6%    |
| Lenovo ThinkPad    | 4         | 3.2%    |
| HP Laptop          | 4         | 3.2%    |
| Dell Latitude      | 4         | 3.2%    |
| ASUS VivoBook      | 4         | 3.2%    |
| HP ProBook         | 3         | 2.4%    |
| Acer Aspire        | 3         | 2.4%    |
| Unknown            | 3         | 2.4%    |
| Razer Blade        | 2         | 1.6%    |
| HP Notebook        | 2         | 1.6%    |
| HP EliteBook       | 2         | 1.6%    |
| HP 15              | 2         | 1.6%    |
| Dell G5            | 2         | 1.6%    |
| Acer TravelMate    | 2         | 1.6%    |
| Toshiba PORTEGE    | 1         | 0.8%    |
| Timi RedmiBook     | 1         | 0.8%    |
| Sony VPCEG30EL     | 1         | 0.8%    |
| Sony VPCCW1S1E     | 1         | 0.8%    |
| Sony VGN-CR120E    | 1         | 0.8%    |
| Sony SVE14A25CLB   | 1         | 0.8%    |
| Sony SVE14113ELW   | 1         | 0.8%    |
| Samsung 550XCJ     | 1         | 0.8%    |
| Samsung 530U4E     | 1         | 0.8%    |
| MSI GF63           | 1         | 0.8%    |
| Lenovo V15-IIL     | 1         | 0.8%    |
| Lenovo G710        | 1         | 0.8%    |
| Lenovo G580        | 1         | 0.8%    |
| Lenovo 3000        | 1         | 0.8%    |
| HP Mini            | 1         | 0.8%    |
| HP G42             | 1         | 0.8%    |
| HP ENVY            | 1         | 0.8%    |
| HP 3115m           | 1         | 0.8%    |
| HP 240             | 1         | 0.8%    |
| HP 1000            | 1         | 0.8%    |
| Google Treeya      | 1         | 0.8%    |
| Google Parrot      | 1         | 0.8%    |
| Google Kip         | 1         | 0.8%    |
| Google Grunt       | 1         | 0.8%    |
| Google Delbin      | 1         | 0.8%    |
| Google Banjo       | 1         | 0.8%    |
| Gateway NE56R      | 1         | 0.8%    |
| Fujitsu LIFEBOOK   | 1         | 0.8%    |
| Dell XPS           | 1         | 0.8%    |
| Dell Vostro        | 1         | 0.8%    |
| Dell System        | 1         | 0.8%    |
| Compal PBL2021     | 1         | 0.8%    |
| Chuwi HeroBook     | 1         | 0.8%    |
| ASUS X555QG        | 1         | 0.8%    |
| ASUS X510UAR       | 1         | 0.8%    |
| ASUS X502CA        | 1         | 0.8%    |
| ASUS X411UN        | 1         | 0.8%    |
| ASUS UX360CA       | 1         | 0.8%    |
| ASUS UX303LA       | 1         | 0.8%    |
| ASUS ROG           | 1         | 0.8%    |
| ASUS G750JX        | 1         | 0.8%    |
| ASUS ASUS          | 1         | 0.8%    |
| Apple MacBookPro13 | 1         | 0.8%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 17        | 13.6%   |
| 2017 | 13        | 10.4%   |
| 2012 | 12        | 9.6%    |
| 2020 | 11        | 8.8%    |
| 2013 | 11        | 8.8%    |
| 2019 | 8         | 6.4%    |
| 2016 | 8         | 6.4%    |
| 2015 | 8         | 6.4%    |
| 2011 | 8         | 6.4%    |
| 2014 | 7         | 5.6%    |
| 2007 | 6         | 4.8%    |
| 2021 | 5         | 4%      |
| 2010 | 4         | 3.2%    |
| 2009 | 3         | 2.4%    |
| 2006 | 2         | 1.6%    |
| 2008 | 1         | 0.8%    |
| 2005 | 1         | 0.8%    |

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
| Disabled | 113       | 90.4%   |
| Enabled  | 12        | 9.6%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 119       | 95.2%   |
| Yes  | 6         | 4.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 39        | 30.23%  |
| 3.01-4.0   | 27        | 20.93%  |
| 8.01-16.0  | 24        | 18.6%   |
| 16.01-24.0 | 15        | 11.63%  |
| 1.01-2.0   | 12        | 9.3%    |
| 32.01-64.0 | 6         | 4.65%   |
| 2.01-3.0   | 3         | 2.33%   |
| 24.01-32.0 | 2         | 1.55%   |
| 0.51-1.0   | 1         | 0.78%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 42        | 30.66%  |
| 2.01-3.0   | 39        | 28.47%  |
| 4.01-8.0   | 23        | 16.79%  |
| 3.01-4.0   | 19        | 13.87%  |
| 0.51-1.0   | 7         | 5.11%   |
| 8.01-16.0  | 5         | 3.65%   |
| 24.01-32.0 | 1         | 0.73%   |
| 0.01-0.5   | 1         | 0.73%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 96        | 75%     |
| 2      | 30        | 23.44%  |
| 3      | 2         | 1.56%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 77        | 61.6%   |
| Yes       | 48        | 38.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 83.2%   |
| No        | 21        | 16.8%   |

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
| Ecuador | 125       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Quito           | 56        | 43.41%  |
| Guayaquil       | 32        | 24.81%  |
| Cuenca          | 12        | 9.3%    |
| Portoviejo      | 3         | 2.33%   |
| Manta           | 3         | 2.33%   |
| Loja            | 3         | 2.33%   |
| Ambato          | 3         | 2.33%   |
| Machala         | 2         | 1.55%   |
| Hacienda Ibarra | 2         | 1.55%   |
| Uyumbicho       | 1         | 0.78%   |
| Samborondon     | 1         | 0.78%   |
| Riobamba        | 1         | 0.78%   |
| Ponceano        | 1         | 0.78%   |
| Nueva Loja      | 1         | 0.78%   |
| Montecristi     | 1         | 0.78%   |
| La Troncal      | 1         | 0.78%   |
| La Providencia  | 1         | 0.78%   |
| Ibarra          | 1         | 0.78%   |
| Guamani         | 1         | 0.78%   |
| Cayambe         | 1         | 0.78%   |
| Babahoyo        | 1         | 0.78%   |
| Ayacucho        | 1         | 0.78%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 32        | 40     | 21.05%  |
| Toshiba             | 29        | 31     | 19.08%  |
| Seagate             | 21        | 32     | 13.82%  |
| Hitachi             | 9         | 11     | 5.92%   |
| Unknown             | 7         | 12     | 4.61%   |
| SK hynix            | 6         | 7      | 3.95%   |
| SanDisk             | 6         | 6      | 3.95%   |
| Samsung Electronics | 6         | 6      | 3.95%   |
| Kingston            | 6         | 8      | 3.95%   |
| HGST                | 4         | 5      | 2.63%   |
| A-DATA Technology   | 4         | 6      | 2.63%   |
| Hewlett-Packard     | 3         | 3      | 1.97%   |
| Micron Technology   | 2         | 2      | 1.32%   |
| Fujitsu             | 2         | 2      | 1.32%   |
| Crucial             | 2         | 2      | 1.32%   |
| USB3.0              | 1         | 1      | 0.66%   |
| SABRENT             | 1         | 1      | 0.66%   |
| PNY                 | 1         | 1      | 0.66%   |
| Phison              | 1         | 1      | 0.66%   |
| OWC                 | 1         | 1      | 0.66%   |
| Netac               | 1         | 1      | 0.66%   |
| LITEON              | 1         | 1      | 0.66%   |
| Lite-On             | 1         | 1      | 0.66%   |
| JMicron Technology  | 1         | 1      | 0.66%   |
| Intel               | 1         | 2      | 0.66%   |
| HS-SSD-E100N        | 1         | 1      | 0.66%   |
| Golden              | 1         | 1      | 0.66%   |
| Apple               | 1         | 2      | 0.66%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                | 6         | 3.82%   |
| Seagate ST1000LM035-1RK172 1TB          | 6         | 3.82%   |
| Toshiba MQ04ABF100 1TB                  | 4         | 2.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 3         | 1.91%   |
| Unknown MMC Card  16GB                  | 3         | 1.91%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 2         | 1.27%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 2         | 1.27%   |
| WDC WD10SPZX-24Z10T0 1TB                | 2         | 1.27%   |
| WDC WD10SPZX-24Z10 1TB                  | 2         | 1.27%   |
| Unknown MMC Card  32GB                  | 2         | 1.27%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 1.27%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 2         | 1.27%   |
| Seagate ST9500325AS 500GB               | 2         | 1.27%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 1.27%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 1.27%   |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 1.27%   |
| Hitachi HTS543232A7A384 320GB           | 2         | 1.27%   |
| Hitachi HTS541616J9SA00 160GB           | 2         | 1.27%   |
| HGST HTS545050A7E380 500GB              | 2         | 1.27%   |
| A-DATA ED600 1TB SSD                    | 2         | 1.27%   |
| WDC WDS500G2B0B-00YS70 500GB SSD        | 1         | 0.64%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.64%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.64%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.64%   |
| WDC WDS100T2B0B-00YS70 1TB SSD          | 1         | 0.64%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 1         | 0.64%   |
| WDC WD7500BPKX-80HPJT0 752GB            | 1         | 0.64%   |
| WDC WD7500BPKT-75PK4T0 752GB            | 1         | 0.64%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 1         | 0.64%   |
| WDC WD2500BEVT-60ZCT1 250GB             | 1         | 0.64%   |
| WDC WD2500BEVS-75UST0 250GB             | 1         | 0.64%   |
| WDC WD20SPZX-75UA7T1 2TB                | 1         | 0.64%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 0.64%   |
| WDC WD10SPZX-35Z10T0 1TB                | 1         | 0.64%   |
| WDC WD10SPZX-22Z10T1 1TB                | 1         | 0.64%   |
| WDC WD10SPZX-00Z10T0 1TB                | 1         | 0.64%   |
| WDC WD10JPVX-75JC3T0 1TB                | 1         | 0.64%   |
| WDC WD10JPVX-22JC3T0 1TB                | 1         | 0.64%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB    | 1         | 0.64%   |
| WDC PC SN530 SDBPNPZ-1T00-1002 1TB      | 1         | 0.64%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB    | 1         | 0.64%   |
| WDC PC SN520 NVMe 256GB                 | 1         | 0.64%   |
| USB3.0 Super Speed 128GB                | 1         | 0.64%   |
| Unknown SD32G  32GB                     | 1         | 0.64%   |
| Unknown SD/MMC/MS PRO 128GB             | 1         | 0.64%   |
| Unknown SD  64GB                        | 1         | 0.64%   |
| Unknown DA4032  32GB                    | 1         | 0.64%   |
| Unknown 00000  2GB                      | 1         | 0.64%   |
| Toshiba MQ04ABD200 2TB                  | 1         | 0.64%   |
| Toshiba MQ02ABF100 1TB                  | 1         | 0.64%   |
| Toshiba MQ01ACF050 500GB                | 1         | 0.64%   |
| Toshiba MQ01ABD100M 1TB                 | 1         | 0.64%   |
| Toshiba MQ01ABD075 752GB                | 1         | 0.64%   |
| Toshiba MQ01ABD050V -63 500GB           | 1         | 0.64%   |
| Toshiba MK6475GSX 640GB                 | 1         | 0.64%   |
| Toshiba MK6008GAH 64GB                  | 1         | 0.64%   |
| Toshiba MK5061GSY 500GB                 | 1         | 0.64%   |
| Toshiba MK3259GSXP 320GB                | 1         | 0.64%   |
| Toshiba MK2561GSYN 250GB                | 1         | 0.64%   |
| Toshiba MK2552GSX 250GB                 | 1         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 26        | 27     | 30.23%  |
| Seagate             | 21        | 32     | 24.42%  |
| WDC                 | 20        | 27     | 23.26%  |
| Hitachi             | 9         | 11     | 10.47%  |
| HGST                | 4         | 5      | 4.65%   |
| Fujitsu             | 2         | 2      | 2.33%   |
| USB3.0              | 1         | 1      | 1.16%   |
| Unknown             | 1         | 3      | 1.16%   |
| Samsung Electronics | 1         | 1      | 1.16%   |
| SABRENT             | 1         | 1      | 1.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 21.95%  |
| SanDisk             | 5         | 5      | 12.2%   |
| Kingston            | 5         | 5      | 12.2%   |
| A-DATA Technology   | 4         | 6      | 9.76%   |
| Toshiba             | 2         | 3      | 4.88%   |
| SK hynix            | 2         | 2      | 4.88%   |
| Hewlett-Packard     | 2         | 2      | 4.88%   |
| Crucial             | 2         | 2      | 4.88%   |
| Samsung Electronics | 1         | 1      | 2.44%   |
| PNY                 | 1         | 1      | 2.44%   |
| OWC                 | 1         | 1      | 2.44%   |
| Netac               | 1         | 1      | 2.44%   |
| Micron Technology   | 1         | 1      | 2.44%   |
| LITEON              | 1         | 1      | 2.44%   |
| JMicron Technology  | 1         | 1      | 2.44%   |
| HS-SSD-E100N        | 1         | 1      | 2.44%   |
| Golden              | 1         | 1      | 2.44%   |
| Apple               | 1         | 2      | 2.44%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 81        | 110    | 56.64%  |
| SSD  | 36        | 45     | 25.17%  |
| NVMe | 20        | 24     | 13.99%  |
| MMC  | 6         | 9      | 4.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 107       | 143    | 76.98%  |
| NVMe | 20        | 24     | 14.39%  |
| SAS  | 6         | 12     | 4.32%   |
| MMC  | 6         | 9      | 4.32%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 75        | 94     | 62.5%   |
| 0.51-1.0   | 40        | 56     | 33.33%  |
| 1.01-2.0   | 5         | 5      | 4.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 35        | 26.92%  |
| 251-500        | 34        | 26.15%  |
| 501-1000       | 20        | 15.38%  |
| 1001-2000      | 12        | 9.23%   |
| 21-50          | 9         | 6.92%   |
| 1-20           | 8         | 6.15%   |
| 51-100         | 8         | 6.15%   |
| Unknown        | 3         | 2.31%   |
| More than 3000 | 1         | 0.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 51        | 37.78%  |
| 21-50     | 26        | 19.26%  |
| 101-250   | 25        | 18.52%  |
| 251-500   | 13        | 9.63%   |
| 51-100    | 10        | 7.41%   |
| 501-1000  | 6         | 4.44%   |
| Unknown   | 3         | 2.22%   |
| 1001-2000 | 1         | 0.74%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB       | 1         | 2      | 10%     |
| Toshiba MQ01ABD100 1TB         | 1         | 1      | 10%     |
| Toshiba MK3259GSXP 320GB       | 1         | 1      | 10%     |
| Toshiba MK2561GSYN 250GB       | 1         | 1      | 10%     |
| Seagate ST1000LX015-1U7172 1TB | 1         | 3      | 10%     |
| Seagate ST1000LM035-1RK172 1TB | 1         | 1      | 10%     |
| Hitachi HTS547550A9E384 500GB  | 1         | 1      | 10%     |
| Hitachi HTS543232L9SA00 320GB  | 1         | 1      | 10%     |
| HGST HTS545050A7E380 500GB     | 1         | 1      | 10%     |
| Fujitsu MHY2250BH 250GB        | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 5      | 40%     |
| Seagate | 2         | 4      | 20%     |
| Hitachi | 2         | 2      | 20%     |
| HGST    | 1         | 1      | 10%     |
| Fujitsu | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 5      | 40%     |
| Seagate | 2         | 4      | 20%     |
| Hitachi | 2         | 2      | 20%     |
| HGST    | 1         | 1      | 10%     |
| Fujitsu | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 13     | 100%    |

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
| Detected | 86        | 131    | 66.67%  |
| Works    | 33        | 44     | 25.58%  |
| Malfunc  | 10        | 13     | 7.75%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 92        | 69.17%  |
| AMD                          | 21        | 15.79%  |
| SanDisk                      | 5         | 3.76%   |
| Samsung Electronics          | 5         | 3.76%   |
| SK hynix                     | 4         | 3.01%   |
| Toshiba America Info Systems | 1         | 0.75%   |
| Silicon Motion               | 1         | 0.75%   |
| Phison Electronics           | 1         | 0.75%   |
| Micron Technology            | 1         | 0.75%   |
| Lite-On Technology           | 1         | 0.75%   |
| Kingston Technology Company  | 1         | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 19        | 13.29%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 13        | 9.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 12        | 8.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 11        | 7.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 5.59%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 4.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 4.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 2.8%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 2.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 2.1%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 2.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 2.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 3         | 2.1%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 2         | 1.4%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.4%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.4%    |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.4%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 1.4%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 1.4%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 1.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.4%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.7%    |
| SK hynix BC511                                                                   | 1         | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.7%    |
| SanDisk WD Blue SN570 NVMe SSD                                                   | 1         | 0.7%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.7%    |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.7%    |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.7%    |
| Samsung Electronics SATA controller                                              | 1         | 0.7%    |
| Phison E12 NVMe Controller                                                       | 1         | 0.7%    |
| Micron Non-Volatile memory controller                                            | 1         | 0.7%    |
| Lite-On NVMe Controller                                                          | 1         | 0.7%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.7%    |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.7%    |
| Intel Tiger Lake-LP SATA Controller                                              | 1         | 0.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.7%    |
| Intel NVMe Optane Memory Series                                                  | 1         | 0.7%    |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.7%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 1         | 0.7%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 1         | 0.7%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 1         | 0.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 0.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 0.7%    |
| AMD FCH IDE Controller                                                           | 1         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 95        | 68.35%  |
| NVMe | 20        | 14.39%  |
| RAID | 12        | 8.63%   |
| IDE  | 12        | 8.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 101       | 80.8%   |
| AMD    | 24        | 19.2%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz               | 7         | 5.6%    |
| Intel Core i7-5500U CPU @ 2.40GHz               | 3         | 2.4%    |
| Intel Core i7-4510U CPU @ 2.00GHz               | 3         | 2.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz               | 3         | 2.4%    |
| Intel Core i5-4210U CPU @ 1.70GHz               | 3         | 2.4%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 3         | 2.4%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 3         | 2.4%    |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 1.6%    |
| Intel Core i7-8565U CPU @ 1.80GHz               | 2         | 1.6%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 2         | 1.6%    |
| Intel Core i7-6600U CPU @ 2.60GHz               | 2         | 1.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 1.6%    |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.6%    |
| Intel Core i5-5200U CPU @ 2.20GHz               | 2         | 1.6%    |
| Intel Core i3-4005U CPU @ 1.70GHz               | 2         | 1.6%    |
| Intel Core i3-3110M CPU @ 2.40GHz               | 2         | 1.6%    |
| Intel Core i3-2350M CPU @ 2.30GHz               | 2         | 1.6%    |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz            | 2         | 1.6%    |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz            | 2         | 1.6%    |
| Intel Atom CPU N455 @ 1.66GHz                   | 2         | 1.6%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 1.6%    |
| AMD E-300 APU with Radeon HD Graphics           | 2         | 1.6%    |
| AMD A4-9120C RADEON R4, 5 COMPUTE CORES 2C+3G   | 2         | 1.6%    |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 2         | 1.6%    |
| Intel Pentium M processor 1.86GHz               | 1         | 0.8%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 1         | 0.8%    |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 0.8%    |
| Intel Genuine CPU T2500 @ 2.00GHz               | 1         | 0.8%    |
| Intel Genuine CPU T2300 @ 1.66GHz               | 1         | 0.8%    |
| Intel Core m3-6Y30 CPU @ 0.90GHz                | 1         | 0.8%    |
| Intel Core i7-9750HF CPU @ 2.60GHz              | 1         | 0.8%    |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.8%    |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 0.8%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 0.8%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 1         | 0.8%    |
| Intel Core i7-4700HQ CPU @ 2.40GHz              | 1         | 0.8%    |
| Intel Core i7-3520M CPU @ 2.90GHz               | 1         | 0.8%    |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 1         | 0.8%    |
| Intel Core i7-2630QM CPU @ 2.00GHz              | 1         | 0.8%    |
| Intel Core i7-2620M CPU @ 2.70GHz               | 1         | 0.8%    |
| Intel Core i7-10750H CPU @ 2.60GHz              | 1         | 0.8%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 1         | 0.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz              | 1         | 0.8%    |
| Intel Core i5-5257U CPU @ 2.70GHz               | 1         | 0.8%    |
| Intel Core i5-3437U CPU @ 1.90GHz               | 1         | 0.8%    |
| Intel Core i5-3337U CPU @ 1.80GHz               | 1         | 0.8%    |
| Intel Core i5-3230M CPU @ 2.60GHz               | 1         | 0.8%    |
| Intel Core i5-3210M CPU @ 2.50GHz               | 1         | 0.8%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 1         | 0.8%    |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 1         | 0.8%    |
| Intel Core i5 CPU M 450 @ 2.40GHz               | 1         | 0.8%    |
| Intel Core i3-8130U CPU @ 2.20GHz               | 1         | 0.8%    |
| Intel Core i3-7020U CPU @ 2.30GHz               | 1         | 0.8%    |
| Intel Core i3-5015U CPU @ 2.10GHz               | 1         | 0.8%    |
| Intel Core i3-5005U CPU @ 2.00GHz               | 1         | 0.8%    |
| Intel Core i3-4000M CPU @ 2.40GHz               | 1         | 0.8%    |
| Intel Core i3-3120M CPU @ 2.50GHz               | 1         | 0.8%    |
| Intel Core i3-2370M CPU @ 2.40GHz               | 1         | 0.8%    |
| Intel Core i3-2330M CPU @ 2.20GHz               | 1         | 0.8%    |
| Intel Core i3-10110U CPU @ 2.10GHz              | 1         | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 34        | 27.2%   |
| Intel Core i5           | 20        | 16%     |
| Intel Core i3           | 16        | 12.8%   |
| Intel Celeron           | 11        | 8.8%    |
| Intel Core 2 Duo        | 9         | 7.2%    |
| AMD Ryzen 5             | 6         | 4.8%    |
| Other                   | 4         | 3.2%    |
| Intel Genuine           | 2         | 1.6%    |
| Intel Atom              | 2         | 1.6%    |
| AMD Ryzen 7             | 2         | 1.6%    |
| AMD E1                  | 2         | 1.6%    |
| AMD E                   | 2         | 1.6%    |
| AMD A8                  | 2         | 1.6%    |
| AMD A4                  | 2         | 1.6%    |
| AMD A12                 | 2         | 1.6%    |
| Intel Pentium M         | 1         | 0.8%    |
| Intel Pentium Dual-Core | 1         | 0.8%    |
| Intel Pentium           | 1         | 0.8%    |
| Intel Core m3           | 1         | 0.8%    |
| AMD Ryzen 3             | 1         | 0.8%    |
| AMD E2                  | 1         | 0.8%    |
| AMD C-70                | 1         | 0.8%    |
| AMD C-60                | 1         | 0.8%    |
| AMD A10                 | 1         | 0.8%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 81        | 64.8%   |
| 4      | 34        | 27.2%   |
| 6      | 5         | 4%      |
| 1      | 3         | 2.4%    |
| 8      | 2         | 1.6%    |

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


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 88        | 70.4%   |
| 1      | 37        | 29.6%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 121       | 96.8%   |
| 32-bit         | 3         | 2.4%    |
| Unknown        | 1         | 0.8%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 14.73%  |
| 0x806ea    | 10        | 7.75%   |
| 0x206a7    | 10        | 7.75%   |
| 0x306a9    | 9         | 6.98%   |
| 0x306d4    | 8         | 6.2%    |
| 0x6fd      | 6         | 4.65%   |
| 0x40651    | 6         | 4.65%   |
| 0x05000119 | 4         | 3.1%    |
| 0x806eb    | 3         | 2.33%   |
| 0x706e5    | 3         | 2.33%   |
| 0x306c3    | 3         | 2.33%   |
| 0x1067a    | 3         | 2.33%   |
| 0x08108109 | 3         | 2.33%   |
| 0x0600611a | 3         | 2.33%   |
| 0x906ed    | 2         | 1.55%   |
| 0x906ea    | 2         | 1.55%   |
| 0x806e9    | 2         | 1.55%   |
| 0x806c1    | 2         | 1.55%   |
| 0x6e8      | 2         | 1.55%   |
| 0x406e3    | 2         | 1.55%   |
| 0x30678    | 2         | 1.55%   |
| 0x106ca    | 2         | 1.55%   |
| 0x0810100b | 2         | 1.55%   |
| 0x06006705 | 2         | 1.55%   |
| 0x06006704 | 2         | 1.55%   |
| 0xa0660    | 1         | 0.78%   |
| 0x806ec    | 1         | 0.78%   |
| 0x706a8    | 1         | 0.78%   |
| 0x706a1    | 1         | 0.78%   |
| 0x6fa      | 1         | 0.78%   |
| 0x6d8      | 1         | 0.78%   |
| 0x506e3    | 1         | 0.78%   |
| 0x406c4    | 1         | 0.78%   |
| 0x406c3    | 1         | 0.78%   |
| 0x20655    | 1         | 0.78%   |
| 0x08600104 | 1         | 0.78%   |
| 0x08108102 | 1         | 0.78%   |
| 0x08101007 | 1         | 0.78%   |
| 0x07030105 | 1         | 0.78%   |
| 0x0700010f | 1         | 0.78%   |
| 0x0500010d | 1         | 0.78%   |
| 0x03000027 | 1         | 0.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 20.8%   |
| IvyBridge     | 11        | 8.8%    |
| Haswell       | 11        | 8.8%    |
| SandyBridge   | 10        | 8%      |
| Broadwell     | 8         | 6.4%    |
| Excavator     | 7         | 5.6%    |
| Core          | 7         | 5.6%    |
| Bobcat        | 5         | 4%      |
| Zen+          | 4         | 3.2%    |
| Skylake       | 4         | 3.2%    |
| Silvermont    | 4         | 3.2%    |
| Zen           | 3         | 2.4%    |
| TigerLake     | 3         | 2.4%    |
| Penryn        | 3         | 2.4%    |
| P6            | 3         | 2.4%    |
| IceLake       | 3         | 2.4%    |
| Zen 2         | 2         | 1.6%    |
| Westmere      | 2         | 1.6%    |
| Goldmont plus | 2         | 1.6%    |
| CometLake     | 2         | 1.6%    |
| Bonnell       | 2         | 1.6%    |
| Puma          | 1         | 0.8%    |
| K10 Llano     | 1         | 0.8%    |
| Jaguar        | 1         | 0.8%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 96        | 63.58%  |
| AMD    | 33        | 21.85%  |
| Nvidia | 22        | 14.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 11        | 6.92%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 6.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 6.29%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 5.03%   |
| Intel HD Graphics 5500                                                                   | 7         | 4.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 3.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 3.14%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 5         | 3.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.52%   |
| Intel HD Graphics 620                                                                    | 4         | 2.52%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 2.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 2.52%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.89%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 1.89%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.26%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.26%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.26%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.26%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.26%   |
| Intel HD Graphics 630                                                                    | 2         | 1.26%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.26%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.26%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.26%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 1.26%   |
| AMD Renoir                                                                               | 2         | 1.26%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.63%   |
| Nvidia TU117M                                                                            | 1         | 0.63%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.63%   |
| Nvidia GT216M [GeForce GT 230M]                                                          | 1         | 0.63%   |
| Nvidia GP108M [GeForce MX330]                                                            | 1         | 0.63%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.63%   |
| Nvidia GP106BM [GeForce GTX 1060 Mobile 6GB]                                             | 1         | 0.63%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.63%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.63%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.63%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.63%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.63%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 0.63%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.63%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.63%   |
| Intel Tiger Lake UHD Graphics                                                            | 1         | 0.63%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 1         | 0.63%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.63%   |
| Intel Iris Graphics 6100                                                                 | 1         | 0.63%   |
| Intel HD Graphics 515                                                                    | 1         | 0.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.63%   |
| Intel Comet Lake UHD Graphics                                                            | 1         | 0.63%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 1         | 0.63%   |
| AMD Wrestler [Radeon HD 7290]                                                            | 1         | 0.63%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 1         | 0.63%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 1         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 72        | 57.6%   |
| 1 x AMD        | 23        | 18.4%   |
| Intel + Nvidia | 16        | 12.8%   |
| Intel + AMD    | 7         | 5.6%    |
| 1 x Nvidia     | 4         | 3.2%    |
| AMD + Nvidia   | 2         | 1.6%    |
| 2 x AMD        | 1         | 0.8%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 110       | 88%     |
| Proprietary | 11        | 8.8%    |
| Unknown     | 4         | 3.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 60.63%  |
| 0.01-0.5   | 20        | 15.75%  |
| 1.01-2.0   | 15        | 11.81%  |
| 3.01-4.0   | 10        | 7.87%   |
| 0.51-1.0   | 3         | 2.36%   |
| 7.01-8.0   | 1         | 0.79%   |
| 2.01-3.0   | 1         | 0.79%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 24        | 16.78%  |
| LG Display              | 23        | 16.08%  |
| Chimei Innolux          | 22        | 15.38%  |
| AU Optronics            | 20        | 13.99%  |
| Samsung Electronics     | 11        | 7.69%   |
| Goldstar                | 9         | 6.29%   |
| Chi Mei Optoelectronics | 5         | 3.5%    |
| Apple                   | 3         | 2.1%    |
| AOC                     | 3         | 2.1%    |
| Sharp                   | 2         | 1.4%    |
| PANDA                   | 2         | 1.4%    |
| LG Philips              | 2         | 1.4%    |
| InfoVision              | 2         | 1.4%    |
| ASUSTek Computer        | 2         | 1.4%    |
| Acer                    | 2         | 1.4%    |
| Unknown (XXX)           | 1         | 0.7%    |
| Toshiba                 | 1         | 0.7%    |
| TCL                     | 1         | 0.7%    |
| Sony                    | 1         | 0.7%    |
| SKY                     | 1         | 0.7%    |
| Lenovo                  | 1         | 0.7%    |
| InnoLux Display         | 1         | 0.7%    |
| Hewlett-Packard         | 1         | 0.7%    |
| Dell                    | 1         | 0.7%    |
| CPT                     | 1         | 0.7%    |
| BenQ                    | 1         | 0.7%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 2         | 1.39%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 1.39%   |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                      | 2         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch       | 2         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch       | 2         | 1.39%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 2         | 1.39%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 2         | 1.39%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                 | 2         | 1.39%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 2         | 1.39%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.39%   |
| AU Optronics LCD Monitor AUO325C 1366x768 256x144mm 11.6-inch         | 2         | 1.39%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.39%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                        | 2         | 1.39%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1         | 0.69%   |
| Toshiba LCD Monitor LCD3706 1280x800 261x163mm 12.1-inch              | 1         | 0.69%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                   | 1         | 0.69%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.69%   |
| SKY TV-monitor SKY1202 1920x1080 885x498mm 40.0-inch                  | 1         | 0.69%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.69%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 0.69%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC5557 1920x1200 367x230mm 17.1-inch | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 1         | 0.69%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch               | 1         | 0.69%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.69%   |
| LG Philips LCD Monitor LPL2601 1280x800 286x179mm 13.3-inch           | 1         | 0.69%   |
| LG Philips LCD Monitor LPL0D01 1280x800 304x190mm 14.1-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD0709 1920x1080 344x194mm 15.5-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD05D0 1920x1080 344x194mm 15.5-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD05AB 1920x1080 309x174mm 14.0-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD053C 1920x1080 309x174mm 14.0-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD049B 1920x1080 344x194mm 15.5-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD0479 1920x1080 309x174mm 14.0-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD0470 1920x1080 345x194mm 15.6-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD0448 1920x1080 345x194mm 15.6-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD03FA 1366x768 310x174mm 14.0-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD02B2 1366x768 310x174mm 14.0-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch           | 1         | 0.69%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 1         | 0.69%   |
| InnoLux Display BT101IW03 V.0 INL0011 1024x600 222x125mm 10.0-inch    | 1         | 0.69%   |
| InfoVision LCD Monitor IVO061A 1366x768 344x193mm 15.5-inch           | 1         | 0.69%   |
| InfoVision LCD Monitor IVO057E 1366x768 309x174mm 14.0-inch           | 1         | 0.69%   |
| Hewlett-Packard N246v HPN3509 1920x1080 528x297mm 23.9-inch           | 1         | 0.69%   |
| Goldstar W1934 GSM4B7A 1440x900 410x256mm 19.0-inch                   | 1         | 0.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 67        | 48.91%  |
| 1920x1080 (FHD)   | 40        | 29.2%   |
| 1600x900 (HD+)    | 10        | 7.3%    |
| 1280x800 (WXGA)   | 7         | 5.11%   |
| 3840x2160 (4K)    | 4         | 2.92%   |
| 1440x900 (WXGA+)  | 2         | 1.46%   |
| 1024x600          | 2         | 1.46%   |
| 2880x1800         | 1         | 0.73%   |
| 2560x1600         | 1         | 0.73%   |
| 2560x1440 (QHD)   | 1         | 0.73%   |
| 1920x1200 (WUXGA) | 1         | 0.73%   |
| 1024x768 (XGA)    | 1         | 0.73%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 56        | 38.89%  |
| 13     | 23        | 15.97%  |
| 14     | 20        | 13.89%  |
| 19     | 7         | 4.86%   |
| 11     | 7         | 4.86%   |
| 17     | 6         | 4.17%   |
| 21     | 5         | 3.47%   |
| 18     | 5         | 3.47%   |
| 12     | 5         | 3.47%   |
| 54     | 2         | 1.39%   |
| 31     | 2         | 1.39%   |
| 10     | 2         | 1.39%   |
| 40     | 1         | 0.69%   |
| 27     | 1         | 0.69%   |
| 24     | 1         | 0.69%   |
| 23     | 1         | 0.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 92        | 64.79%  |
| 201-300     | 21        | 14.79%  |
| 401-500     | 15        | 10.56%  |
| 351-400     | 6         | 4.23%   |
| 501-600     | 3         | 2.11%   |
| 601-700     | 2         | 1.41%   |
| 1001-1500   | 2         | 1.41%   |
| 801-900     | 1         | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 110       | 89.43%  |
| 16/10 | 11        | 8.94%   |
| 4/3   | 1         | 0.81%   |
| 3/2   | 1         | 0.81%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 55        | 38.19%  |
| 81-90          | 38        | 26.39%  |
| 151-200        | 8         | 5.56%   |
| 51-60          | 7         | 4.86%   |
| 201-250        | 6         | 4.17%   |
| 71-80          | 5         | 3.47%   |
| 61-70          | 5         | 3.47%   |
| 141-150        | 5         | 3.47%   |
| 121-130        | 5         | 3.47%   |
| More than 1000 | 2         | 1.39%   |
| 351-500        | 2         | 1.39%   |
| 41-50          | 2         | 1.39%   |
| 301-350        | 1         | 0.69%   |
| 131-140        | 1         | 0.69%   |
| 501-1000       | 1         | 0.69%   |
| 91-100         | 1         | 0.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 68        | 48.57%  |
| 121-160       | 47        | 33.57%  |
| 51-100        | 16        | 11.43%  |
| 161-240       | 5         | 3.57%   |
| 1-50          | 3         | 2.14%   |
| More than 240 | 1         | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 102       | 80.31%  |
| 2     | 21        | 16.54%  |
| 0     | 3         | 2.36%   |
| 3     | 1         | 0.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 74        | 37.37%  |
| Intel                           | 47        | 23.74%  |
| Qualcomm Atheros                | 40        | 20.2%   |
| Broadcom                        | 17        | 8.59%   |
| Marvell Technology Group        | 5         | 2.53%   |
| Ralink                          | 4         | 2.02%   |
| Broadcom Limited                | 3         | 1.52%   |
| Xiaomi                          | 2         | 1.01%   |
| TP-Link                         | 2         | 1.01%   |
| Ralink Technology               | 1         | 0.51%   |
| Qualcomm Atheros Communications | 1         | 0.51%   |
| MediaTek                        | 1         | 0.51%   |
| Hewlett-Packard                 | 1         | 0.51%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 41        | 17.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 26        | 10.92%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 4.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 3.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 3.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 2.52%   |
| Intel Wireless 3160                                                     | 5         | 2.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 2.1%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 1.68%   |
| Intel Wireless 8265 / 8275                                              | 4         | 1.68%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.26%   |
| Intel Wireless 7260                                                     | 3         | 1.26%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 1.26%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 3         | 1.26%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.84%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.84%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.84%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 0.84%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.84%   |
| Intel Wireless 8260                                                     | 2         | 0.84%   |
| Intel Wireless 7265                                                     | 2         | 0.84%   |
| Intel WiFi Link 5100                                                    | 2         | 0.84%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 0.84%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.84%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 2         | 0.84%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.84%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 1         | 0.42%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.42%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.42%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.42%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.42%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.42%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                            | 1         | 0.42%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.42%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 1         | 0.42%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.42%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 1         | 0.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 1         | 0.42%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.42%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 1         | 0.42%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 1         | 0.42%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                   | 1         | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 47        | 37.01%  |
| Qualcomm Atheros                | 34        | 26.77%  |
| Realtek Semiconductor           | 24        | 18.9%   |
| Broadcom                        | 13        | 10.24%  |
| Ralink                          | 4         | 3.15%   |
| TP-Link                         | 1         | 0.79%   |
| Ralink Technology               | 1         | 0.79%   |
| Qualcomm Atheros Communications | 1         | 0.79%   |
| MediaTek                        | 1         | 0.79%   |
| Broadcom Limited                | 1         | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 7.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 6.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 6.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 4.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 4.65%   |
| Intel Wireless 3160                                                     | 5         | 3.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 3.88%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 3.1%    |
| Intel Wireless 8265 / 8275                                              | 4         | 3.1%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 2.33%   |
| Intel Wireless 7260                                                     | 3         | 2.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.55%   |
| Intel Wireless 8260                                                     | 2         | 1.55%   |
| Intel Wireless 7265                                                     | 2         | 1.55%   |
| Intel WiFi Link 5100                                                    | 2         | 1.55%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.55%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.55%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 1.55%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.55%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.78%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.78%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 1         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.78%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.78%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                            | 1         | 0.78%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.78%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.78%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.78%   |
| Intel Wireless 3165                                                     | 1         | 0.78%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 0.78%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.78%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 1         | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1         | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1         | 0.78%   |
| Intel Centrino Wireless-N 2200                                          | 1         | 0.78%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 0.78%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.78%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.78%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                           | 1         | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 1         | 0.78%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 1         | 0.78%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 0.78%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1         | 0.78%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 1         | 0.78%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 0.78%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 70        | 66.04%  |
| Qualcomm Atheros         | 11        | 10.38%  |
| Intel                    | 9         | 8.49%   |
| Broadcom                 | 6         | 5.66%   |
| Marvell Technology Group | 5         | 4.72%   |
| Xiaomi                   | 2         | 1.89%   |
| Broadcom Limited         | 2         | 1.89%   |
| TP-Link                  | 1         | 0.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 38.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 24.3%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.8%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 2.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.87%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.87%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.87%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.87%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.87%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.93%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.93%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.93%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.93%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.93%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.93%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.93%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.93%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.93%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.93%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.93%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.93%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.93%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.93%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.93%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.93%   |
| Broadcom Limited NetXtreme BCM5751M Gigabit Ethernet PCI Express  | 1         | 0.93%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 0.93%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 124       | 53.91%  |
| Ethernet | 104       | 45.22%  |
| Modem    | 2         | 0.87%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 75.38%  |
| Ethernet | 32        | 24.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 99        | 79.2%   |
| 1     | 26        | 20.8%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 108       | 85.04%  |
| Yes  | 19        | 14.96%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 32.63%  |
| Realtek Semiconductor           | 15        | 15.79%  |
| Qualcomm Atheros Communications | 15        | 15.79%  |
| Foxconn / Hon Hai               | 7         | 7.37%   |
| Broadcom                        | 5         | 5.26%   |
| Lite-On Technology              | 4         | 4.21%   |
| IMC Networks                    | 4         | 4.21%   |
| Toshiba                         | 3         | 3.16%   |
| Ralink Technology               | 2         | 2.11%   |
| Ralink                          | 2         | 2.11%   |
| Apple                           | 2         | 2.11%   |
| Hewlett-Packard                 | 1         | 1.05%   |
| Foxconn International           | 1         | 1.05%   |
| Dell                            | 1         | 1.05%   |
| Cambridge Silicon Radio         | 1         | 1.05%   |
| Alps Electric                   | 1         | 1.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 17        | 17.89%  |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 10.53%  |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 9.47%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 6.32%   |
| Realtek Bluetooth Radio                             | 5         | 5.26%   |
| Intel AX201 Bluetooth                               | 4         | 4.21%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 4.21%   |
| Toshiba Bluetooth Device                            | 3         | 3.16%   |
| IMC Networks Bluetooth Radio                        | 3         | 3.16%   |
| Ralink RT3290 Bluetooth                             | 2         | 2.11%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 2.11%   |
| Lite-On Bluetooth Device                            | 2         | 2.11%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 2.11%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.05%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.05%   |
| Ralink CSR BS8510                                   | 1         | 1.05%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.05%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.05%   |
| Lite-On Wireless_Device                             | 1         | 1.05%   |
| Lite-On Bluetooth Radio                             | 1         | 1.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.05%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.05%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.05%   |
| Intel AX200 Bluetooth                               | 1         | 1.05%   |
| IMC Networks BCM20702A0                             | 1         | 1.05%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 1.05%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 1.05%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 1.05%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.05%   |
| Broadcom HP Portable Valentine                      | 1         | 1.05%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.05%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.05%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.05%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.05%   |
| Apple Bluetooth Host Controller                     | 1         | 1.05%   |
| Apple Bluetooth HCI                                 | 1         | 1.05%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 1.05%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 101       | 72.66%  |
| AMD                 | 25        | 17.99%  |
| Nvidia              | 11        | 7.91%   |
| Focusrite-Novation  | 1         | 0.72%   |
| C-Media Electronics | 1         | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 10.06%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 7.82%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 5.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 4.47%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 4.47%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 4.47%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 4.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 3.91%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 3.91%   |
| AMD FCH Azalia Controller                                                                         | 6         | 3.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 2.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 2.79%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 2.79%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 2.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 2.79%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 2.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 2.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 2.23%   |
| AMD High Definition Audio Controller                                                              | 4         | 2.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.68%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 3         | 1.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.12%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.12%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 1.12%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.12%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.12%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.12%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.56%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.56%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.56%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 1         | 0.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.56%   |
| Focusrite-Novation Focusrite Scarlett 2i2 2nd Gen                                                 | 1         | 0.56%   |
| C-Media Electronics CM108 Audio Controller                                                        | 1         | 0.56%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.56%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 25        | 29.76%  |
| SK hynix            | 18        | 21.43%  |
| Kingston            | 11        | 13.1%   |
| Micron Technology   | 9         | 10.71%  |
| Ramaxel Technology  | 5         | 5.95%   |
| Unknown             | 3         | 3.57%   |
| A-DATA Technology   | 3         | 3.57%   |
| Nanya Technology    | 2         | 2.38%   |
| Crucial             | 2         | 2.38%   |
| Unknown (ABCD)      | 1         | 1.19%   |
| Team                | 1         | 1.19%   |
| Goodram             | 1         | 1.19%   |
| Elpida              | 1         | 1.19%   |
| Corsair             | 1         | 1.19%   |
| Avant               | 1         | 1.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 3         | 3.45%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 2.3%    |
| Ramaxel RAM RMT3020EC58E9F1333 4096MB SODIMM DDR3 4199MT/s          | 2         | 2.3%    |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s                | 2         | 2.3%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 2.3%    |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s             | 2         | 2.3%    |
| Unknown RAM Module 2048MB SODIMM 800MT/s                            | 1         | 1.15%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 1.15%   |
| Unknown RAM Module 1024MB SODIMM DDR2                               | 1         | 1.15%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                            | 1         | 1.15%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 1.15%   |
| Team RAM TEAMGROUP-SD4-2400 16GB SODIMM DDR4 8400MT/s               | 1         | 1.15%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.15%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.15%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.15%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 1.15%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.15%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.15%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.15%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 1.15%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 1.15%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 1.15%   |
| SK hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s           | 1         | 1.15%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 1.15%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 1.15%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 1         | 1.15%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.15%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 1.15%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 1.15%   |
| SK hynix RAM H9HCNNNBKMMLXR-NEE 4GB LPDDR4 3733MT/s                 | 1         | 1.15%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                      | 1         | 1.15%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 1.15%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 1         | 1.15%   |
| Samsung RAM M471B5273CH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.15%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.15%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 1.15%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.15%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.15%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.15%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.15%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 1         | 1.15%   |
| Samsung RAM M471A5244CB0-CTD 4096MB Row Of Chips DDR4 2667MT/s      | 1         | 1.15%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 1.15%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 1.15%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 1         | 1.15%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.15%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.15%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.15%   |
| Samsung RAM M4 70T5663QZ3-CE6 2GB SODIMM DDR2 667MT/s               | 1         | 1.15%   |
| Samsung RAM K4E6E304EB-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 1         | 1.15%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s             | 1         | 1.15%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s           | 1         | 1.15%   |
| Ramaxel RAM RMSA3270MB86H9F2400 4GB SODIMM DDR4 2400MT/s            | 1         | 1.15%   |
| Micron RAM MT52L512M32D2PF-10 4GB Row Of Chips LPDDR3 1867MT/s      | 1         | 1.15%   |
| Micron RAM 8ATF51264HZ-2G1B1 8GB SODIMM DDR4 2667MT/s               | 1         | 1.15%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 1         | 1.15%   |
| Micron RAM 8ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2400MT/s                | 1         | 1.15%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s               | 1         | 1.15%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 31        | 47.69%  |
| DDR3    | 23        | 35.38%  |
| LPDDR4  | 3         | 4.62%   |
| DDR2    | 3         | 4.62%   |
| SDRAM   | 2         | 3.08%   |
| LPDDR3  | 2         | 3.08%   |
| Unknown | 1         | 1.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 59        | 93.65%  |
| Row Of Chips | 3         | 4.76%   |
| Unknown      | 1         | 1.59%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 33        | 45.21%  |
| 8192  | 21        | 28.77%  |
| 16384 | 9         | 12.33%  |
| 2048  | 6         | 8.22%   |
| 1024  | 3         | 4.11%   |
| 32768 | 1         | 1.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 23        | 30.67%  |
| 1600    | 20        | 26.67%  |
| 2400    | 5         | 6.67%   |
| 1334    | 5         | 6.67%   |
| 3200    | 4         | 5.33%   |
| 3266    | 3         | 4%      |
| 4199    | 2         | 2.67%   |
| 2133    | 2         | 2.67%   |
| 667     | 2         | 2.67%   |
| 8400    | 1         | 1.33%   |
| 3733    | 1         | 1.33%   |
| 1867    | 1         | 1.33%   |
| 1333    | 1         | 1.33%   |
| 1066    | 1         | 1.33%   |
| 975     | 1         | 1.33%   |
| 933     | 1         | 1.33%   |
| 800     | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 1         | 33.33%  |
| Prolific Technology | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Seiko Epson L3110 Series        | 1         | 33.33%  |
| Prolific PL2305 Parallel Port   | 1         | 33.33%  |
| HP Ink Tank Wireless 410 series | 1         | 33.33%  |

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
| Chicony Electronics                    | 27        | 23.48%  |
| IMC Networks                           | 15        | 13.04%  |
| Realtek Semiconductor                  | 9         | 7.83%   |
| Microdia                               | 9         | 7.83%   |
| Quanta                                 | 8         | 6.96%   |
| Suyin                                  | 7         | 6.09%   |
| Syntek                                 | 6         | 5.22%   |
| Sunplus Innovation Technology          | 5         | 4.35%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.35%   |
| Lite-On Technology                     | 4         | 3.48%   |
| Ricoh                                  | 3         | 2.61%   |
| Acer                                   | 3         | 2.61%   |
| Silicon Motion                         | 2         | 1.74%   |
| OmniVision Technologies                | 2         | 1.74%   |
| Apple                                  | 2         | 1.74%   |
| Alcor Micro                            | 2         | 1.74%   |
| Samsung Electronics                    | 1         | 0.87%   |
| Lenovo                                 | 1         | 0.87%   |
| Importek                               | 1         | 0.87%   |
| Generalplus Technology                 | 1         | 0.87%   |
| Foxconn / Hon Hai                      | 1         | 0.87%   |
| ALi                                    | 1         | 0.87%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 6         | 5.22%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 3.48%   |
| Realtek Integrated_Webcam_HD                        | 3         | 2.61%   |
| IMC Networks TOSHIBA Web Camera - HD                | 3         | 2.61%   |
| Chicony TOSHIBA Web Camera - HD                     | 3         | 2.61%   |
| Chicony Integrated Camera                           | 3         | 2.61%   |
| Chicony HP Truevision HD                            | 3         | 2.61%   |
| Syntek Lenovo EasyCamera                            | 2         | 1.74%   |
| Syntek EasyCamera                                   | 2         | 1.74%   |
| Suyin Integrated_Webcam_HD                          | 2         | 1.74%   |
| Suyin HP Truevision HD                              | 2         | 1.74%   |
| Suyin HD WebCam                                     | 2         | 1.74%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.74%   |
| Realtek Integrated Webcam                           | 2         | 1.74%   |
| Quanta HP Webcam-50                                 | 2         | 1.74%   |
| Quanta HP Webcam                                    | 2         | 1.74%   |
| OmniVision OV2640 Webcam                            | 2         | 1.74%   |
| Lite-On TOSHIBA Web Camera - HD                     | 2         | 1.74%   |
| Lite-On HP TrueVision HD Camera                     | 2         | 1.74%   |
| IMC Networks VGA UVC WebCam                         | 2         | 1.74%   |
| IMC Networks Integrated Camera                      | 2         | 1.74%   |
| Chicony HP Wide Vision HD Camera                    | 2         | 1.74%   |
| Chicony HP HD Webcam [Fixed]                        | 2         | 1.74%   |
| Chicony HD User Facing                              | 2         | 1.74%   |
| Chicony EasyCamera                                  | 2         | 1.74%   |
| Syntek USB Video Device                             | 1         | 0.87%   |
| Syntek Integrated Camera                            | 1         | 0.87%   |
| Suyin Asus Integrated Webcam                        | 1         | 0.87%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.87%   |
| Sunplus HP TrueVision HD Camera                     | 1         | 0.87%   |
| Sunplus HD WebCam                                   | 1         | 0.87%   |
| Silicon Motion WebCam SC-10HDP12631N                | 1         | 0.87%   |
| Silicon Motion Web Camera                           | 1         | 0.87%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 0.87%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870] | 1         | 0.87%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 0.87%   |
| Ricoh Integrated_Webcam_1.3M                        | 1         | 0.87%   |
| Realtek Integrated Webcam HD                        | 1         | 0.87%   |
| Realtek HP Truevision HD                            | 1         | 0.87%   |
| Realtek HP "Truevision HD" laptop camera            | 1         | 0.87%   |
| Realtek HD WebCam                                   | 1         | 0.87%   |
| Quanta USB2.0 HD UVC WebCam                         | 1         | 0.87%   |
| Quanta Laptop_Integrated_Webcam_2HDM                | 1         | 0.87%   |
| Quanta HP TrueVision HD Webcam                      | 1         | 0.87%   |
| Quanta HP TrueVision HD Camera                      | 1         | 0.87%   |
| Microdia Sony Visual Communication Camera           | 1         | 0.87%   |
| Microdia Rapoo camera                               | 1         | 0.87%   |
| Microdia Integrated Webcam                          | 1         | 0.87%   |
| Lenovo Integrated Webcam                            | 1         | 0.87%   |
| Importek TOSHIBA Web Camera - HD                    | 1         | 0.87%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 0.87%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 0.87%   |
| IMC Networks USB Camera                             | 1         | 0.87%   |
| IMC Networks EasyCamera                             | 1         | 0.87%   |
| Generalplus GENERAL - UVC                           | 1         | 0.87%   |
| Foxconn / Hon Hai USB2.0 Camera                     | 1         | 0.87%   |
| Chicony Webcam-101                                  | 1         | 0.87%   |
| Chicony VGA 30fps UVC Webcam                        | 1         | 0.87%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 0.87%   |
| Chicony USB2.0 HD UVC WebCam                        | 1         | 0.87%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| AuthenTec             | 3         | 30%     |
| Validity Sensors      | 2         | 20%     |
| Upek                  | 1         | 10%     |
| Synaptics             | 1         | 10%     |
| STMicroelectronics    | 1         | 10%     |
| LighTuning Technology | 1         | 10%     |
| Elan Microelectronics | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES1600                                      | 2         | 20%     |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 10%     |
| Validity Sensors Fingerprint scanner                   | 1         | 10%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 10%     |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 10%     |
| STMicroelectronics Fingerprint Reader                  | 1         | 10%     |
| LighTuning Fingerprint Sensor                          | 1         | 10%     |
| Elan ELAN:Fingerprint                                  | 1         | 10%     |
| AuthenTec AES2810                                      | 1         | 10%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| O2 Micro | 2         | 40%     |
| Broadcom | 2         | 40%     |
| Upek     | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 20%     |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 20%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |
| Broadcom 5880                                                                | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 94        | 74.6%   |
| 1     | 28        | 22.22%  |
| 2     | 4         | 3.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 10        | 27.78%  |
| Net/wireless             | 8         | 22.22%  |
| Graphics card            | 6         | 16.67%  |
| Chipcard                 | 5         | 13.89%  |
| Storage                  | 2         | 5.56%   |
| Multimedia controller    | 2         | 5.56%   |
| Bluetooth                | 2         | 5.56%   |
| Communication controller | 1         | 2.78%   |

