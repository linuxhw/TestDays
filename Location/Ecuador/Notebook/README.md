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

Total: 219

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell      | Latitude E6420              | [a84f4dbcbb](https://linux-hardware.org/?probe=a84f4dbcbb) | Feb 28, 2023 |
| Dell      | Inspiron 14-3467            | [5bf68a313d](https://linux-hardware.org/?probe=5bf68a313d) | Feb 27, 2023 |
| Apple     | MacBookAir6,1               | [72d2220b42](https://linux-hardware.org/?probe=72d2220b42) | Feb 07, 2023 |
| HP        | Setzer                      | [bd65b300ae](https://linux-hardware.org/?probe=bd65b300ae) | Feb 06, 2023 |
| Lenovo    | IdeaPad S145-14AST 81ST     | [85dbbce597](https://linux-hardware.org/?probe=85dbbce597) | Jan 27, 2023 |
| Alienware | 15 R3                       | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Samsung   | N102SP/N100SP/N101SP        | [b4d38fb35a](https://linux-hardware.org/?probe=b4d38fb35a) | Jan 18, 2023 |
| Gateway   | NV55C                       | [b8ae4adfdc](https://linux-hardware.org/?probe=b8ae4adfdc) | Jan 12, 2023 |
| Apple     | MacBookPro16,2              | [d7abd06e34](https://linux-hardware.org/?probe=d7abd06e34) | Jan 08, 2023 |
| Apple     | MacBookPro16,2              | [aa67834a96](https://linux-hardware.org/?probe=aa67834a96) | Jan 08, 2023 |
| HP        | ENVY 15                     | [e91c6321b3](https://linux-hardware.org/?probe=e91c6321b3) | Jan 04, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop X421... | [cf4ba78c7d](https://linux-hardware.org/?probe=cf4ba78c7d) | Dec 24, 2022 |
| Unknown   | OA Q-ONE BRAND_V2.0         | [e554aa3d11](https://linux-hardware.org/?probe=e554aa3d11) | Dec 24, 2022 |
| Dynabook  | PORTEGE X40-J               | [3f1fc426b0](https://linux-hardware.org/?probe=3f1fc426b0) | Dec 05, 2022 |
| HP        | Laptop 14-cf3xxx            | [21d31ce6b0](https://linux-hardware.org/?probe=21d31ce6b0) | Nov 15, 2022 |
| HP        | Laptop 15-da0xxx            | [554f0e2130](https://linux-hardware.org/?probe=554f0e2130) | Oct 30, 2022 |
| HP        | Laptop 15-dy2xxx            | [304a013939](https://linux-hardware.org/?probe=304a013939) | Oct 27, 2022 |
| HP        | Laptop 14-cf3xxx            | [a782c95632](https://linux-hardware.org/?probe=a782c95632) | Oct 25, 2022 |
| Lenovo    | IdeaPad L340-15IRH Gamin... | [14830504a7](https://linux-hardware.org/?probe=14830504a7) | Oct 22, 2022 |
| Gateway   | NV510P                      | [13fe5a5e78](https://linux-hardware.org/?probe=13fe5a5e78) | Oct 16, 2022 |
| Gateway   | NV510P                      | [7cb93d25ac](https://linux-hardware.org/?probe=7cb93d25ac) | Oct 16, 2022 |
| HP        | Laptop 14-cf3xxx            | [7664f462d0](https://linux-hardware.org/?probe=7664f462d0) | Oct 09, 2022 |
| Lenovo    | ZHAOYANG E53-80 81CM        | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| HP        | Laptop 15-da0xxx            | [c62874f456](https://linux-hardware.org/?probe=c62874f456) | Oct 04, 2022 |
| HP        | Laptop 14-cf3xxx            | [9386d6b529](https://linux-hardware.org/?probe=9386d6b529) | Sep 23, 2022 |
| HP        | Laptop 14-cf3xxx            | [3ba944192e](https://linux-hardware.org/?probe=3ba944192e) | Sep 22, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop X515... | [f3dcbfead7](https://linux-hardware.org/?probe=f3dcbfead7) | Sep 02, 2022 |
| Lenovo    | ThinkBook 13s G4 ARB 21A... | [1f0f793a37](https://linux-hardware.org/?probe=1f0f793a37) | Sep 02, 2022 |
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


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 23        | 14.84%  |
| Ubuntu 18.04        | 11        | 7.1%    |
| Linux Mint 20.3     | 7         | 4.52%   |
| KDE neon 20.04      | 6         | 3.87%   |
| Ubuntu 22.04        | 5         | 3.23%   |
| Linux Mint 19.3     | 5         | 3.23%   |
| Debian 11           | 5         | 3.23%   |
| Zorin 15            | 4         | 2.58%   |
| OpenMandriva 4.3    | 4         | 2.58%   |
| Pop!_OS 21.10       | 3         | 1.94%   |
| LMDE 4              | 3         | 1.94%   |
| Fedora 34           | 3         | 1.94%   |
| Fedora 33           | 3         | 1.94%   |
| Zorin 16            | 2         | 1.29%   |
| Xubuntu 20.04       | 2         | 1.29%   |
| Ubuntu 22.10        | 2         | 1.29%   |
| Ubuntu 21.10        | 2         | 1.29%   |
| Ubuntu 21.04        | 2         | 1.29%   |
| Ubuntu              | 2         | 1.29%   |
| Pop!_OS 21.04       | 2         | 1.29%   |
| Pop!_OS 20.04       | 2         | 1.29%   |
| OpenMandriva 23.01  | 2         | 1.29%   |
| Linux Mint 20.1     | 2         | 1.29%   |
| Linux Mint 20       | 2         | 1.29%   |
| Kubuntu 22.04       | 2         | 1.29%   |
| Fedora 36           | 2         | 1.29%   |
| Elementary 5.1.7    | 2         | 1.29%   |
| BlackPanther 18.1   | 2         | 1.29%   |
| ArcoLinux Rolling   | 2         | 1.29%   |
| Xubuntu 22.10       | 1         | 0.65%   |
| Xubuntu 18.04       | 1         | 0.65%   |
| Void Linux          | 1         | 0.65%   |
| Ubuntu MATE 20.04   | 1         | 0.65%   |
| Ubuntu MATE 18.04   | 1         | 0.65%   |
| Ubuntu Budgie 22.04 | 1         | 0.65%   |
| Ubuntu Budgie 20.04 | 1         | 0.65%   |
| Ubuntu 20.10        | 1         | 0.65%   |
| Ubuntu 19.04        | 1         | 0.65%   |
| Ubuntu 18.10        | 1         | 0.65%   |
| RHEL 8              | 1         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 48        | 32.21%  |
| Linux Mint    | 17        | 11.41%  |
| Fedora        | 12        | 8.05%   |
| Pop!_OS       | 8         | 5.37%   |
| OpenMandriva  | 8         | 5.37%   |
| KDE neon      | 7         | 4.7%    |
| Zorin         | 6         | 4.03%   |
| Debian        | 6         | 4.03%   |
| Xubuntu       | 4         | 2.68%   |
| Manjaro       | 3         | 2.01%   |
| Lubuntu       | 3         | 2.01%   |
| LMDE          | 3         | 2.01%   |
| Kubuntu       | 3         | 2.01%   |
| Elementary    | 3         | 2.01%   |
| Ubuntu MATE   | 2         | 1.34%   |
| Ubuntu Budgie | 2         | 1.34%   |
| Endless       | 2         | 1.34%   |
| BlackPanther  | 2         | 1.34%   |
| ArcoLinux     | 2         | 1.34%   |
| Arch          | 2         | 1.34%   |
| Void Linux    | 1         | 0.67%   |
| RHEL          | 1         | 0.67%   |
| Kali          | 1         | 0.67%   |
| Garuda Linux  | 1         | 0.67%   |
| EndeavourOS   | 1         | 0.67%   |
| Deepin        | 1         | 0.67%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-54-generic         | 4         | 2.34%   |
| 5.4.0-42-generic         | 4         | 2.34%   |
| 5.15.0-33-generic        | 4         | 2.34%   |
| 5.13.0-35-generic        | 4         | 2.34%   |
| 5.4.0-58-generic         | 3         | 1.75%   |
| 5.4.0-56-generic         | 3         | 1.75%   |
| 5.4.0-48-generic         | 3         | 1.75%   |
| 5.4.0-45-generic         | 3         | 1.75%   |
| 5.4.0-26-generic         | 3         | 1.75%   |
| 5.16.7-desktop-1omv4003  | 3         | 1.75%   |
| 5.16.11-76051611-generic | 3         | 1.75%   |
| 6.1.1-desktop-1omv2290   | 2         | 1.17%   |
| 5.8.0-43-generic         | 2         | 1.17%   |
| 5.8.0-41-generic         | 2         | 1.17%   |
| 5.8.0-14-generic         | 2         | 1.17%   |
| 5.4.0-77-generic         | 2         | 1.17%   |
| 5.4.0-7634-generic       | 2         | 1.17%   |
| 5.4.0-110-generic        | 2         | 1.17%   |
| 5.3.0-62-generic         | 2         | 1.17%   |
| 5.15.59-xanmod1          | 2         | 1.17%   |
| 5.15.0-58-generic        | 2         | 1.17%   |
| 5.15.0-27-generic        | 2         | 1.17%   |
| 5.13.0-7614-generic      | 2         | 1.17%   |
| 5.13.0-51-generic        | 2         | 1.17%   |
| 5.13.0-27-generic        | 2         | 1.17%   |
| 5.0.0-37-generic         | 2         | 1.17%   |
| 5.0.0-23-generic         | 2         | 1.17%   |
| 4.18.16-desktop-1bP      | 2         | 1.17%   |
| 4.15.0-54-generic        | 2         | 1.17%   |
| 6.1.9-arch1-1            | 1         | 0.58%   |
| 6.1.2-arch1-1            | 1         | 0.58%   |
| 6.0.2-76060002-generic   | 1         | 0.58%   |
| 6.0.10-desktop-2omv22090 | 1         | 0.58%   |
| 5.9.16-200.fc33.x86_64   | 1         | 0.58%   |
| 5.8.15-201.fc32.x86_64   | 1         | 0.58%   |
| 5.8.0-45-generic         | 1         | 0.58%   |
| 5.7.17-2-MANJARO         | 1         | 0.58%   |
| 5.7.1-050701-generic     | 1         | 0.58%   |
| 5.5.5-arch1-1            | 1         | 0.58%   |
| 5.5.16-200.fc31.x86_64   | 1         | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 42        | 26.09%  |
| 5.13.0  | 13        | 8.07%   |
| 5.15.0  | 12        | 7.45%   |
| 4.15.0  | 8         | 4.97%   |
| 5.8.0   | 7         | 4.35%   |
| 5.0.0   | 7         | 4.35%   |
| 5.11.0  | 5         | 3.11%   |
| 5.3.0   | 4         | 2.48%   |
| 5.10.0  | 4         | 2.48%   |
| 5.19.0  | 3         | 1.86%   |
| 5.16.7  | 3         | 1.86%   |
| 5.16.11 | 3         | 1.86%   |
| 6.1.1   | 2         | 1.24%   |
| 5.17.5  | 2         | 1.24%   |
| 5.15.59 | 2         | 1.24%   |
| 4.18.16 | 2         | 1.24%   |
| 4.18.0  | 2         | 1.24%   |
| 6.1.9   | 1         | 0.62%   |
| 6.1.2   | 1         | 0.62%   |
| 6.0.2   | 1         | 0.62%   |
| 6.0.10  | 1         | 0.62%   |
| 5.9.16  | 1         | 0.62%   |
| 5.8.15  | 1         | 0.62%   |
| 5.7.17  | 1         | 0.62%   |
| 5.7.1   | 1         | 0.62%   |
| 5.5.5   | 1         | 0.62%   |
| 5.5.16  | 1         | 0.62%   |
| 5.4.50  | 1         | 0.62%   |
| 5.4.26  | 1         | 0.62%   |
| 5.4.111 | 1         | 0.62%   |
| 5.3.9   | 1         | 0.62%   |
| 5.19.15 | 1         | 0.62%   |
| 5.19.10 | 1         | 0.62%   |
| 5.18.6  | 1         | 0.62%   |
| 5.18.12 | 1         | 0.62%   |
| 5.18.0  | 1         | 0.62%   |
| 5.16.15 | 1         | 0.62%   |
| 5.16.13 | 1         | 0.62%   |
| 5.16.0  | 1         | 0.62%   |
| 5.15.78 | 1         | 0.62%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 45        | 28.66%  |
| 5.15    | 16        | 10.19%  |
| 5.13    | 13        | 8.28%   |
| 5.16    | 9         | 5.73%   |
| 5.8     | 8         | 5.1%    |
| 4.15    | 8         | 5.1%    |
| 5.11    | 7         | 4.46%   |
| 5.10    | 7         | 4.46%   |
| 5.0     | 7         | 4.46%   |
| 5.3     | 5         | 3.18%   |
| 5.19    | 5         | 3.18%   |
| 6.1     | 4         | 2.55%   |
| 4.18    | 4         | 2.55%   |
| 5.18    | 3         | 1.91%   |
| 5.14    | 3         | 1.91%   |
| 6.0     | 2         | 1.27%   |
| 5.7     | 2         | 1.27%   |
| 5.5     | 2         | 1.27%   |
| 5.17    | 2         | 1.27%   |
| 5.12    | 2         | 1.27%   |
| 5.9     | 1         | 0.64%   |
| 4.9     | 1         | 0.64%   |
| 4.19    | 1         | 0.64%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 132       | 92.96%  |
| i686   | 10        | 7.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 63        | 42.28%  |
| Unknown    | 19        | 12.75%  |
| KDE5       | 18        | 12.08%  |
| X-Cinnamon | 16        | 10.74%  |
| XFCE       | 10        | 6.71%   |
| MATE       | 5         | 3.36%   |
| KDE        | 5         | 3.36%   |
| Pantheon   | 3         | 2.01%   |
| LXQt       | 2         | 1.34%   |
| Budgie     | 2         | 1.34%   |
| qtile      | 1         | 0.67%   |
| LXDE       | 1         | 0.67%   |
| jwm        | 1         | 0.67%   |
| ICEWM      | 1         | 0.67%   |
| Deepin     | 1         | 0.67%   |
| Cinnamon   | 1         | 0.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 115       | 77.18%  |
| Wayland | 22        | 14.77%  |
| Unknown | 12        | 8.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 87        | 58%     |
| SDDM    | 18        | 12%     |
| GDM     | 18        | 12%     |
| LightDM | 13        | 8.67%   |
| GDM3    | 11        | 7.33%   |
| TDM     | 3         | 2%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_EC   | 69        | 47.59%  |
| en_US   | 35        | 24.14%  |
| Unknown | 14        | 9.66%   |
| es_ES   | 12        | 8.28%   |
| es_MX   | 4         | 2.76%   |
| es_US   | 2         | 1.38%   |
| es_CO   | 2         | 1.38%   |
| de_DE   | 2         | 1.38%   |
| C       | 2         | 1.38%   |
| ru_RU   | 1         | 0.69%   |
| fr_FR   | 1         | 0.69%   |
| es_PE   | 1         | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 78        | 53.42%  |
| BIOS | 68        | 46.58%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 118       | 80.82%  |
| Btrfs   | 12        | 8.22%   |
| Overlay | 11        | 7.53%   |
| Zfs     | 1         | 0.68%   |
| Xfs     | 1         | 0.68%   |
| Tmpfs   | 1         | 0.68%   |
| Ext2    | 1         | 0.68%   |
| Unknown | 1         | 0.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 89        | 61.38%  |
| GPT     | 45        | 31.03%  |
| MBR     | 11        | 7.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 126       | 87.5%   |
| Yes       | 18        | 12.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 104       | 72.22%  |
| Yes       | 40        | 27.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 33        | 23.24%  |
| Dell                | 25        | 17.61%  |
| Lenovo              | 19        | 13.38%  |
| ASUSTek Computer    | 14        | 9.86%   |
| Toshiba             | 11        | 7.75%   |
| Google              | 6         | 4.23%   |
| Acer                | 6         | 4.23%   |
| Sony                | 5         | 3.52%   |
| Apple               | 5         | 3.52%   |
| Samsung Electronics | 3         | 2.11%   |
| Gateway             | 3         | 2.11%   |
| Unknown             | 3         | 2.11%   |
| Razer               | 2         | 1.41%   |
| Timi                | 1         | 0.7%    |
| MSI                 | 1         | 0.7%    |
| Fujitsu             | 1         | 0.7%    |
| Dynabook            | 1         | 0.7%    |
| Compal              | 1         | 0.7%    |
| Chuwi               | 1         | 0.7%    |
| Alienware           | 1         | 0.7%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Unknown                                            | 4         | 2.82%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK              | 2         | 1.41%   |
| Lenovo IdeaPad 320-15ABR 80XS                      | 2         | 1.41%   |
| HP ProBook 4440s                                   | 2         | 1.41%   |
| HP Pavilion Laptop 15-cw0xxx                       | 2         | 1.41%   |
| HP Notebook                                        | 2         | 1.41%   |
| HP Laptop 15-da0xxx                                | 2         | 1.41%   |
| Dell Inspiron 5570                                 | 2         | 1.41%   |
| Dell Inspiron 3442                                 | 2         | 1.41%   |
| Dell Inspiron 1420                                 | 2         | 1.41%   |
| Dell G5 5587                                       | 2         | 1.41%   |
| Toshiba Satellite S55-B                            | 1         | 0.7%    |
| Toshiba Satellite S55-A                            | 1         | 0.7%    |
| Toshiba Satellite P775                             | 1         | 0.7%    |
| Toshiba Satellite P55W-C                           | 1         | 0.7%    |
| Toshiba Satellite L50-B                            | 1         | 0.7%    |
| Toshiba Satellite L45-B                            | 1         | 0.7%    |
| Toshiba Satellite E45t-B                           | 1         | 0.7%    |
| Toshiba Satellite C55D-A                           | 1         | 0.7%    |
| Toshiba Satellite C55-B                            | 1         | 0.7%    |
| Toshiba Satellite C45-A                            | 1         | 0.7%    |
| Toshiba PORTEGE M805                               | 1         | 0.7%    |
| Timi RedmiBook 14-APCS                             | 1         | 0.7%    |
| Sony VPCEG30EL                                     | 1         | 0.7%    |
| Sony VPCCW1S1E                                     | 1         | 0.7%    |
| Sony VGN-CR120E                                    | 1         | 0.7%    |
| Sony SVE14A25CLB                                   | 1         | 0.7%    |
| Sony SVE14113ELW                                   | 1         | 0.7%    |
| Samsung N102SP/N100SP/N101SP                       | 1         | 0.7%    |
| Samsung 550XCJ/550XCR                              | 1         | 0.7%    |
| Samsung 530U4E/540U4E                              | 1         | 0.7%    |
| Razer Blade Stealth                                | 1         | 0.7%    |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.7%    |
| MSI GF63 Thin 9SC                                  | 1         | 0.7%    |
| Lenovo ZHAOYANG E53-80 81CM                        | 1         | 0.7%    |
| Lenovo V15-IIL 82C5                                | 1         | 0.7%    |
| Lenovo ThinkPad X201 3680PKS                       | 1         | 0.7%    |
| Lenovo ThinkPad T530 2429JB5                       | 1         | 0.7%    |
| Lenovo ThinkPad E590 20NB002AMH                    | 1         | 0.7%    |
| Lenovo ThinkPad E15 20REA00000                     | 1         | 0.7%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell Inspiron     | 16        | 11.27%  |
| Toshiba Satellite | 10        | 7.04%   |
| Lenovo IdeaPad    | 9         | 6.34%   |
| HP Pavilion       | 9         | 6.34%   |
| HP Laptop         | 6         | 4.23%   |
| ASUS VivoBook     | 5         | 3.52%   |
| Lenovo ThinkPad   | 4         | 2.82%   |
| Dell Latitude     | 4         | 2.82%   |
| Unknown           | 4         | 2.82%   |
| HP ProBook        | 3         | 2.11%   |
| Acer Aspire       | 3         | 2.11%   |
| Razer Blade       | 2         | 1.41%   |
| HP Notebook       | 2         | 1.41%   |
| HP ENVY           | 2         | 1.41%   |
| HP EliteBook      | 2         | 1.41%   |
| HP 15             | 2         | 1.41%   |
| Dell G5           | 2         | 1.41%   |
| Acer TravelMate   | 2         | 1.41%   |
| Toshiba PORTEGE   | 1         | 0.7%    |
| Timi RedmiBook    | 1         | 0.7%    |
| Sony VPCEG30EL    | 1         | 0.7%    |
| Sony VPCCW1S1E    | 1         | 0.7%    |
| Sony VGN-CR120E   | 1         | 0.7%    |
| Sony SVE14A25CLB  | 1         | 0.7%    |
| Sony SVE14113ELW  | 1         | 0.7%    |
| Samsung N102SP    | 1         | 0.7%    |
| Samsung 550XCJ    | 1         | 0.7%    |
| Samsung 530U4E    | 1         | 0.7%    |
| MSI GF63          | 1         | 0.7%    |
| Lenovo ZHAOYANG   | 1         | 0.7%    |
| Lenovo V15-IIL    | 1         | 0.7%    |
| Lenovo ThinkBook  | 1         | 0.7%    |
| Lenovo G710       | 1         | 0.7%    |
| Lenovo G580       | 1         | 0.7%    |
| Lenovo 3000       | 1         | 0.7%    |
| HP Setzer         | 1         | 0.7%    |
| HP Mini           | 1         | 0.7%    |
| HP G42            | 1         | 0.7%    |
| HP 3115m          | 1         | 0.7%    |
| HP 240            | 1         | 0.7%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 18        | 12.68%  |
| 2017 | 15        | 10.56%  |
| 2020 | 14        | 9.86%   |
| 2012 | 13        | 9.15%   |
| 2013 | 12        | 8.45%   |
| 2019 | 10        | 7.04%   |
| 2016 | 8         | 5.63%   |
| 2015 | 8         | 5.63%   |
| 2014 | 8         | 5.63%   |
| 2011 | 8         | 5.63%   |
| 2021 | 7         | 4.93%   |
| 2010 | 6         | 4.23%   |
| 2007 | 6         | 4.23%   |
| 2009 | 3         | 2.11%   |
| 2022 | 2         | 1.41%   |
| 2006 | 2         | 1.41%   |
| 2008 | 1         | 0.7%    |
| 2005 | 1         | 0.7%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 142       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 130       | 91.55%  |
| Enabled  | 12        | 8.45%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 135       | 95.07%  |
| Yes  | 7         | 4.93%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 44        | 29.93%  |
| 3.01-4.0   | 33        | 22.45%  |
| 8.01-16.0  | 29        | 19.73%  |
| 16.01-24.0 | 16        | 10.88%  |
| 1.01-2.0   | 12        | 8.16%   |
| 32.01-64.0 | 7         | 4.76%   |
| 2.01-3.0   | 3         | 2.04%   |
| 24.01-32.0 | 2         | 1.36%   |
| 0.51-1.0   | 1         | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 48        | 30.57%  |
| 1.01-2.0   | 48        | 30.57%  |
| 4.01-8.0   | 27        | 17.2%   |
| 3.01-4.0   | 20        | 12.74%  |
| 0.51-1.0   | 7         | 4.46%   |
| 8.01-16.0  | 5         | 3.18%   |
| 24.01-32.0 | 1         | 0.64%   |
| 0.01-0.5   | 1         | 0.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 110       | 75.86%  |
| 2      | 33        | 22.76%  |
| 3      | 2         | 1.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 92        | 64.34%  |
| Yes       | 51        | 35.66%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 80.28%  |
| No        | 28        | 19.72%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 99.3%   |
| No        | 1         | 0.7%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 75.69%  |
| No        | 35        | 24.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Ecuador | 142       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Quito           | 62        | 41.61%  |
| Guayaquil       | 40        | 26.85%  |
| Cuenca          | 15        | 10.07%  |
| Loja            | 4         | 2.68%   |
| Ambato          | 4         | 2.68%   |
| Portoviejo      | 3         | 2.01%   |
| Manta           | 3         | 2.01%   |
| Machala         | 3         | 2.01%   |
| Hacienda Ibarra | 2         | 1.34%   |
| Uyumbicho       | 1         | 0.67%   |
| Samborondon     | 1         | 0.67%   |
| Riobamba        | 1         | 0.67%   |
| Ponceano        | 1         | 0.67%   |
| Nueva Loja      | 1         | 0.67%   |
| Montecristi     | 1         | 0.67%   |
| La Troncal      | 1         | 0.67%   |
| La Providencia  | 1         | 0.67%   |
| Ibarra          | 1         | 0.67%   |
| Guamani         | 1         | 0.67%   |
| Cayambe         | 1         | 0.67%   |
| Babahoyo        | 1         | 0.67%   |
| Ayacucho        | 1         | 0.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 36        | 44     | 20.81%  |
| Toshiba                   | 30        | 33     | 17.34%  |
| Seagate                   | 23        | 37     | 13.29%  |
| Hitachi                   | 9         | 11     | 5.2%    |
| Unknown                   | 8         | 13     | 4.62%   |
| SanDisk                   | 8         | 11     | 4.62%   |
| Samsung Electronics       | 8         | 8      | 4.62%   |
| Kingston                  | 7         | 9      | 4.05%   |
| SK hynix                  | 6         | 8      | 3.47%   |
| Hewlett-Packard           | 5         | 5      | 2.89%   |
| HGST                      | 4         | 6      | 2.31%   |
| A-DATA Technology         | 4         | 7      | 2.31%   |
| Micron Technology         | 3         | 3      | 1.73%   |
| Apple                     | 3         | 4      | 1.73%   |
| Fujitsu                   | 2         | 2      | 1.16%   |
| Crucial                   | 2         | 2      | 1.16%   |
| USB3.0                    | 1         | 1      | 0.58%   |
| UMIS                      | 1         | 1      | 0.58%   |
| SABRENT                   | 1         | 1      | 0.58%   |
| PNY                       | 1         | 1      | 0.58%   |
| Phison                    | 1         | 1      | 0.58%   |
| OWC                       | 1         | 1      | 0.58%   |
| Netac                     | 1         | 1      | 0.58%   |
| Micron/Crucial Technology | 1         | 1      | 0.58%   |
| LITEON                    | 1         | 1      | 0.58%   |
| Lite-On                   | 1         | 1      | 0.58%   |
| JMicron Technology        | 1         | 1      | 0.58%   |
| Intel                     | 1         | 2      | 0.58%   |
| HS-SSD-E100N              | 1         | 1      | 0.58%   |
| Golden                    | 1         | 1      | 0.58%   |
| Unknown                   | 1         | 1      | 0.58%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                | 6         | 3.33%   |
| Seagate ST1000LM035-1RK172 1TB          | 6         | 3.33%   |
| Toshiba MQ04ABF100 1TB                  | 5         | 2.78%   |
| Unknown MMC Card  16GB                  | 4         | 2.22%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 3         | 1.67%   |
| WDC WD10SPZX-24Z10 1TB                  | 3         | 1.67%   |
| Seagate ST2000LM007-1R8174 2TB          | 3         | 1.67%   |
| WDC WD5000LPVX-22V0TT0 500GB            | 2         | 1.11%   |
| WDC WD1600BEVT-22ZCT0 160GB             | 2         | 1.11%   |
| WDC WD10SPZX-24Z10T0 1TB                | 2         | 1.11%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 1.11%   |
| Unknown MMC Card  32GB                  | 2         | 1.11%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 1.11%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 2         | 1.11%   |
| Seagate ST9500325AS 500GB               | 2         | 1.11%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 1.11%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 1.11%   |
| Micron NVMe SSD Drive 512GB             | 2         | 1.11%   |
| Kingston SA400S37480G 480GB SSD         | 2         | 1.11%   |
| Hitachi HTS543232A7A384 320GB           | 2         | 1.11%   |
| Hitachi HTS541616J9SA00 160GB           | 2         | 1.11%   |
| HGST HTS545050A7E380 500GB              | 2         | 1.11%   |
| HP SSD S700 500GB                       | 2         | 1.11%   |
| A-DATA ED600 1TB SSD                    | 2         | 1.11%   |
| WDC WDS500G2B0B-00YS70 500GB SSD        | 1         | 0.56%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.56%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.56%   |
| WDC WDS120G2G0A-00JH30 120GB SSD        | 1         | 0.56%   |
| WDC WDS100T2B0B-00YS70 1TB SSD          | 1         | 0.56%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 1         | 0.56%   |
| WDC WD7500BPKX-80HPJT0 752GB            | 1         | 0.56%   |
| WDC WD7500BPKT-75PK4T0 752GB            | 1         | 0.56%   |
| WDC WD5000LPVT-00G33T0 500GB            | 1         | 0.56%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 1         | 0.56%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 0.56%   |
| WDC WD2500BEVT-60ZCT1 250GB             | 1         | 0.56%   |
| WDC WD2500BEVS-75UST0 250GB             | 1         | 0.56%   |
| WDC WD20SPZX-75UA7T1 2TB                | 1         | 0.56%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 0.56%   |
| WDC WD10SPZX-35Z10T0 1TB                | 1         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 27        | 29     | 28.72%  |
| WDC                 | 24        | 31     | 25.53%  |
| Seagate             | 23        | 37     | 24.47%  |
| Hitachi             | 9         | 11     | 9.57%   |
| HGST                | 4         | 6      | 4.26%   |
| Fujitsu             | 2         | 2      | 2.13%   |
| USB3.0              | 1         | 1      | 1.06%   |
| Unknown             | 1         | 3      | 1.06%   |
| Samsung Electronics | 1         | 1      | 1.06%   |
| SABRENT             | 1         | 1      | 1.06%   |
| JMicron Technology  | 1         | 1      | 1.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 20.45%  |
| Kingston            | 6         | 6      | 13.64%  |
| SanDisk             | 5         | 5      | 11.36%  |
| Hewlett-Packard     | 4         | 4      | 9.09%   |
| A-DATA Technology   | 4         | 7      | 9.09%   |
| Toshiba             | 2         | 3      | 4.55%   |
| SK hynix            | 2         | 2      | 4.55%   |
| Crucial             | 2         | 2      | 4.55%   |
| Apple               | 2         | 3      | 4.55%   |
| Samsung Electronics | 1         | 1      | 2.27%   |
| PNY                 | 1         | 1      | 2.27%   |
| OWC                 | 1         | 1      | 2.27%   |
| Netac               | 1         | 1      | 2.27%   |
| Micron Technology   | 1         | 1      | 2.27%   |
| LITEON              | 1         | 1      | 2.27%   |
| HS-SSD-E100N        | 1         | 1      | 2.27%   |
| Golden              | 1         | 1      | 2.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 89        | 123    | 54.27%  |
| SSD  | 39        | 49     | 23.78%  |
| NVMe | 28        | 36     | 17.07%  |
| MMC  | 8         | 11     | 4.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 118       | 159    | 73.75%  |
| NVMe | 28        | 36     | 17.5%   |
| MMC  | 8         | 11     | 5%      |
| SAS  | 6         | 13     | 3.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 80        | 99     | 60.61%  |
| 0.51-1.0   | 46        | 67     | 34.85%  |
| 1.01-2.0   | 6         | 6      | 4.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 40        | 27.03%  |
| 101-250        | 38        | 25.68%  |
| 501-1000       | 21        | 14.19%  |
| 1001-2000      | 14        | 9.46%   |
| 21-50          | 11        | 7.43%   |
| 1-20           | 10        | 6.76%   |
| 51-100         | 9         | 6.08%   |
| Unknown        | 4         | 2.7%    |
| More than 3000 | 1         | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 59        | 38.31%  |
| 21-50     | 29        | 18.83%  |
| 101-250   | 28        | 18.18%  |
| 251-500   | 14        | 9.09%   |
| 51-100    | 13        | 8.44%   |
| 501-1000  | 6         | 3.9%    |
| Unknown   | 4         | 2.6%    |
| 1001-2000 | 1         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD5000LPVT-00G33T0 500GB   | 1         | 1      | 8.33%   |
| WDC WD5000LPCX-24VHAT0 500GB   | 1         | 1      | 8.33%   |
| Toshiba MQ01ABF050 500GB       | 1         | 2      | 8.33%   |
| Toshiba MQ01ABD100 1TB         | 1         | 1      | 8.33%   |
| Toshiba MK3259GSXP 320GB       | 1         | 1      | 8.33%   |
| Toshiba MK2561GSYN 250GB       | 1         | 2      | 8.33%   |
| Seagate ST1000LX015-1U7172 1TB | 1         | 3      | 8.33%   |
| Seagate ST1000LM035-1RK172 1TB | 1         | 1      | 8.33%   |
| Hitachi HTS547550A9E384 500GB  | 1         | 1      | 8.33%   |
| Hitachi HTS543232L9SA00 320GB  | 1         | 1      | 8.33%   |
| HGST HTS545050A7E380 500GB     | 1         | 1      | 8.33%   |
| Fujitsu MHY2250BH 250GB        | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 6      | 33.33%  |
| WDC     | 2         | 2      | 16.67%  |
| Seagate | 2         | 4      | 16.67%  |
| Hitachi | 2         | 2      | 16.67%  |
| HGST    | 1         | 1      | 8.33%   |
| Fujitsu | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 6      | 33.33%  |
| WDC     | 2         | 2      | 16.67%  |
| Seagate | 2         | 4      | 16.67%  |
| Hitachi | 2         | 2      | 16.67%  |
| HGST    | 1         | 1      | 8.33%   |
| Fujitsu | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 16     | 100%    |

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
| Detected | 95        | 149    | 63.76%  |
| Works    | 42        | 54     | 28.19%  |
| Malfunc  | 12        | 16     | 8.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 102       | 66.23%  |
| AMD                          | 23        | 14.94%  |
| Samsung Electronics          | 8         | 5.19%   |
| SanDisk                      | 7         | 4.55%   |
| SK hynix                     | 4         | 2.6%    |
| Micron Technology            | 2         | 1.3%    |
| Union Memory (Shenzhen)      | 1         | 0.65%   |
| Toshiba America Info Systems | 1         | 0.65%   |
| Silicon Motion               | 1         | 0.65%   |
| Phison Electronics           | 1         | 0.65%   |
| Micron/Crucial Technology    | 1         | 0.65%   |
| Lite-On Technology           | 1         | 0.65%   |
| Kingston Technology Company  | 1         | 0.65%   |
| Apple                        | 1         | 0.65%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 21        | 12.8%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 14        | 8.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 13        | 7.93%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 12        | 7.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 4.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 4.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 3.66%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 2.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 4         | 2.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 2.44%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 1.83%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 3         | 1.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.83%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.83%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 1.22%   |
| Micron Non-Volatile memory controller                                            | 2         | 1.22%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 1.22%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 1.22%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 2         | 1.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 1.22%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 1.22%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 1.22%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.22%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.61%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 1         | 0.61%   |
| SK hynix BC511                                                                   | 1         | 0.61%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.61%   |
| SanDisk WD Blue SN570 NVMe SSD                                                   | 1         | 0.61%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.61%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.61%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 0.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.61%   |
| Samsung Electronics SATA controller                                              | 1         | 0.61%   |
| Samsung Apple PCIe SSD                                                           | 1         | 0.61%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 106       | 66.25%  |
| NVMe | 28        | 17.5%   |
| RAID | 14        | 8.75%   |
| IDE  | 12        | 7.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 115       | 80.99%  |
| AMD    | 27        | 19.01%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz               | 8         | 5.63%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 3         | 2.11%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 3         | 2.11%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 3         | 2.11%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 3         | 2.11%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 3         | 2.11%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 3         | 2.11%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 3         | 2.11%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 3         | 2.11%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 1.41%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 1.41%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 2         | 1.41%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 2         | 1.41%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 2         | 1.41%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 1.41%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 2         | 1.41%   |
| Intel Core i3-8130U CPU @ 2.20GHz               | 2         | 1.41%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 2         | 1.41%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 2         | 1.41%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 2         | 1.41%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz            | 2         | 1.41%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz            | 2         | 1.41%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 2         | 1.41%   |
| Intel Atom CPU N455 @ 1.66GHz                   | 2         | 1.41%   |
| AMD Ryzen 3 3250U with Radeon Graphics          | 2         | 1.41%   |
| AMD E-300 APU with Radeon HD Graphics           | 2         | 1.41%   |
| AMD A4-9120C RADEON R4, 5 COMPUTE CORES 2C+3G   | 2         | 1.41%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 2         | 1.41%   |
| Intel Pentium M processor 1.86GHz               | 1         | 0.7%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 1         | 0.7%    |
| Intel Pentium CPU N3520 @ 2.16GHz               | 1         | 0.7%    |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 0.7%    |
| Intel Genuine CPU T2500 @ 2.00GHz               | 1         | 0.7%    |
| Intel Genuine CPU T2300 @ 1.66GHz               | 1         | 0.7%    |
| Intel Core m3-6Y30 CPU @ 0.90GHz                | 1         | 0.7%    |
| Intel Core i7-9750HF CPU @ 2.60GHz              | 1         | 0.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 0.7%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 1         | 0.7%    |
| Intel Core i7-4702MQ CPU @ 2.20GHz              | 1         | 0.7%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz              | 1         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 38        | 26.76%  |
| Intel Core i5           | 23        | 16.2%   |
| Intel Core i3           | 17        | 11.97%  |
| Intel Celeron           | 13        | 9.15%   |
| Intel Core 2 Duo        | 9         | 6.34%   |
| Other                   | 6         | 4.23%   |
| AMD Ryzen 5             | 6         | 4.23%   |
| Intel Atom              | 3         | 2.11%   |
| AMD Ryzen 7             | 3         | 2.11%   |
| Intel Pentium           | 2         | 1.41%   |
| Intel Genuine           | 2         | 1.41%   |
| AMD Ryzen 3             | 2         | 1.41%   |
| AMD E1                  | 2         | 1.41%   |
| AMD E                   | 2         | 1.41%   |
| AMD A8                  | 2         | 1.41%   |
| AMD A4                  | 2         | 1.41%   |
| AMD A12                 | 2         | 1.41%   |
| Intel Pentium M         | 1         | 0.7%    |
| Intel Pentium Dual-Core | 1         | 0.7%    |
| Intel Core m3           | 1         | 0.7%    |
| AMD E2                  | 1         | 0.7%    |
| AMD C-70                | 1         | 0.7%    |
| AMD C-60                | 1         | 0.7%    |
| AMD A6                  | 1         | 0.7%    |
| AMD A10                 | 1         | 0.7%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 89        | 62.68%  |
| 4      | 40        | 28.17%  |
| 6      | 6         | 4.23%   |
| 1      | 4         | 2.82%   |
| 8      | 3         | 2.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 142       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 101       | 71.13%  |
| 1      | 41        | 28.87%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 138       | 97.18%  |
| 32-bit         | 3         | 2.11%   |
| Unknown        | 1         | 0.7%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 15.07%  |
| 0x806ea    | 11        | 7.53%   |
| 0x206a7    | 10        | 6.85%   |
| 0x306a9    | 9         | 6.16%   |
| 0x306d4    | 8         | 5.48%   |
| 0x40651    | 7         | 4.79%   |
| 0x6fd      | 6         | 4.11%   |
| 0x806c1    | 4         | 2.74%   |
| 0x706e5    | 4         | 2.74%   |
| 0x306c3    | 4         | 2.74%   |
| 0x05000119 | 4         | 2.74%   |
| 0x906ea    | 3         | 2.05%   |
| 0x806eb    | 3         | 2.05%   |
| 0x806e9    | 3         | 2.05%   |
| 0x1067a    | 3         | 2.05%   |
| 0x08108109 | 3         | 2.05%   |
| 0x06006705 | 3         | 2.05%   |
| 0x0600611a | 3         | 2.05%   |
| 0x906ed    | 2         | 1.37%   |
| 0x6e8      | 2         | 1.37%   |
| 0x406e3    | 2         | 1.37%   |
| 0x406c4    | 2         | 1.37%   |
| 0x30678    | 2         | 1.37%   |
| 0x20655    | 2         | 1.37%   |
| 0x106ca    | 2         | 1.37%   |
| 0x0810100b | 2         | 1.37%   |
| 0x06006704 | 2         | 1.37%   |
| 0xa0660    | 1         | 0.68%   |
| 0x806ec    | 1         | 0.68%   |
| 0x706a8    | 1         | 0.68%   |
| 0x706a1    | 1         | 0.68%   |
| 0x6fa      | 1         | 0.68%   |
| 0x6d8      | 1         | 0.68%   |
| 0x506e3    | 1         | 0.68%   |
| 0x506c9    | 1         | 0.68%   |
| 0x406c3    | 1         | 0.68%   |
| 0x30673    | 1         | 0.68%   |
| 0x0a404102 | 1         | 0.68%   |
| 0x08600104 | 1         | 0.68%   |
| 0x08108102 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 30        | 21.13%  |
| Haswell       | 13        | 9.15%   |
| IvyBridge     | 11        | 7.75%   |
| SandyBridge   | 10        | 7.04%   |
| Excavator     | 8         | 5.63%   |
| Broadwell     | 8         | 5.63%   |
| Core          | 7         | 4.93%   |
| Silvermont    | 6         | 4.23%   |
| Zen+          | 5         | 3.52%   |
| TigerLake     | 5         | 3.52%   |
| Bobcat        | 5         | 3.52%   |
| Skylake       | 4         | 2.82%   |
| IceLake       | 4         | 2.82%   |
| Zen           | 3         | 2.11%   |
| Westmere      | 3         | 2.11%   |
| Penryn        | 3         | 2.11%   |
| P6            | 3         | 2.11%   |
| Bonnell       | 3         | 2.11%   |
| Zen 2         | 2         | 1.41%   |
| Goldmont plus | 2         | 1.41%   |
| CometLake     | 2         | 1.41%   |
| Puma          | 1         | 0.7%    |
| K10 Llano     | 1         | 0.7%    |
| Jaguar        | 1         | 0.7%    |
| Goldmont      | 1         | 0.7%    |
| Unknown       | 1         | 0.7%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 110       | 64.71%  |
| AMD    | 37        | 21.76%  |
| Nvidia | 23        | 13.53%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 13        | 7.3%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 6.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 5.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 5.06%   |
| Intel HD Graphics 5500                                                                   | 7         | 3.93%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 3.37%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 2.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 2.81%   |
| Intel HD Graphics 620                                                                    | 5         | 2.81%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 2.81%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 2.25%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.69%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.69%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 1.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.69%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 1.12%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1.12%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 1.12%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 1.12%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.12%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 1.12%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.12%   |
| Intel HD Graphics 630                                                                    | 2         | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.12%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.12%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 1.12%   |
| AMD Renoir                                                                               | 2         | 1.12%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.56%   |
| Nvidia TU117M                                                                            | 1         | 0.56%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.56%   |
| Nvidia GT216M [GeForce GT 230M]                                                          | 1         | 0.56%   |
| Nvidia GP108M [GeForce MX330]                                                            | 1         | 0.56%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 84        | 59.15%  |
| 1 x AMD        | 26        | 18.31%  |
| Intel + Nvidia | 17        | 11.97%  |
| Intel + AMD    | 8         | 5.63%   |
| 1 x Nvidia     | 4         | 2.82%   |
| AMD + Nvidia   | 2         | 1.41%   |
| 2 x AMD        | 1         | 0.7%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 126       | 88.11%  |
| Proprietary | 12        | 8.39%   |
| Unknown     | 5         | 3.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 91        | 62.76%  |
| 0.01-0.5   | 21        | 14.48%  |
| 1.01-2.0   | 16        | 11.03%  |
| 3.01-4.0   | 11        | 7.59%   |
| 0.51-1.0   | 3         | 2.07%   |
| 7.01-8.0   | 1         | 0.69%   |
| 5.01-6.0   | 1         | 0.69%   |
| 2.01-3.0   | 1         | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 27        | 16.67%  |
| Chimei Innolux          | 26        | 16.05%  |
| LG Display              | 24        | 14.81%  |
| AU Optronics            | 24        | 14.81%  |
| Samsung Electronics     | 12        | 7.41%   |
| Goldstar                | 10        | 6.17%   |
| Chi Mei Optoelectronics | 6         | 3.7%    |
| Apple                   | 5         | 3.09%   |
| AOC                     | 4         | 2.47%   |
| Sharp                   | 2         | 1.23%   |
| PANDA                   | 2         | 1.23%   |
| LG Philips              | 2         | 1.23%   |
| InfoVision              | 2         | 1.23%   |
| ASUSTek Computer        | 2         | 1.23%   |
| Acer                    | 2         | 1.23%   |
| Unknown (XXX)           | 1         | 0.62%   |
| Toshiba                 | 1         | 0.62%   |
| TCL                     | 1         | 0.62%   |
| Sony                    | 1         | 0.62%   |
| SKY                     | 1         | 0.62%   |
| Lenovo                  | 1         | 0.62%   |
| InnoLux Display         | 1         | 0.62%   |
| Huion                   | 1         | 0.62%   |
| Hewlett-Packard         | 1         | 0.62%   |
| Dell                    | 1         | 0.62%   |
| CPT                     | 1         | 0.62%   |
| BenQ                    | 1         | 0.62%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                      | 3         | 1.84%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.84%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.84%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                        | 3         | 1.84%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 2         | 1.23%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch       | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch       | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 2         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 2         | 1.23%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                 | 2         | 1.23%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 1.23%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 2         | 1.23%   |
| AU Optronics LCD Monitor AUO325C 1366x768 256x144mm 11.6-inch         | 2         | 1.23%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1         | 0.61%   |
| Toshiba LCD Monitor LCD3706 1280x800 261x163mm 12.1-inch              | 1         | 0.61%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                   | 1         | 0.61%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                 | 1         | 0.61%   |
| SKY TV-monitor SKY1202 1920x1080 885x498mm 40.0-inch                  | 1         | 0.61%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.61%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 0.61%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC5557 1920x1200 367x230mm 17.1-inch | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 1         | 0.61%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 1         | 0.61%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch               | 1         | 0.61%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 1         | 0.61%   |
| LG Philips LCD Monitor LPL2601 1280x800 286x179mm 13.3-inch           | 1         | 0.61%   |
| LG Philips LCD Monitor LPL0D01 1280x800 304x190mm 14.1-inch           | 1         | 0.61%   |
| LG Display LCD Monitor LGD0710 2560x1600 286x179mm 13.3-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD0709 1920x1080 344x194mm 15.5-inch          | 1         | 0.61%   |
| LG Display LCD Monitor LGD05D0 1920x1080 344x194mm 15.5-inch          | 1         | 0.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 77        | 49.36%  |
| 1920x1080 (FHD)   | 45        | 28.85%  |
| 1600x900 (HD+)    | 11        | 7.05%   |
| 1280x800 (WXGA)   | 7         | 4.49%   |
| 3840x2160 (4K)    | 4         | 2.56%   |
| 2560x1600         | 3         | 1.92%   |
| 1024x600          | 3         | 1.92%   |
| 1440x900 (WXGA+)  | 2         | 1.28%   |
| 2880x1800         | 1         | 0.64%   |
| 2560x1440 (QHD)   | 1         | 0.64%   |
| 1920x1200 (WUXGA) | 1         | 0.64%   |
| 1024x768 (XGA)    | 1         | 0.64%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 62        | 38.04%  |
| 13     | 27        | 16.56%  |
| 14     | 22        | 13.5%   |
| 11     | 9         | 5.52%   |
| 19     | 8         | 4.91%   |
| 21     | 6         | 3.68%   |
| 18     | 6         | 3.68%   |
| 17     | 6         | 3.68%   |
| 12     | 6         | 3.68%   |
| 10     | 3         | 1.84%   |
| 54     | 2         | 1.23%   |
| 31     | 2         | 1.23%   |
| 40     | 1         | 0.61%   |
| 27     | 1         | 0.61%   |
| 24     | 1         | 0.61%   |
| 23     | 1         | 0.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 102       | 63.35%  |
| 201-300     | 27        | 16.77%  |
| 401-500     | 18        | 11.18%  |
| 351-400     | 6         | 3.73%   |
| 501-600     | 3         | 1.86%   |
| 601-700     | 2         | 1.24%   |
| 1001-1500   | 2         | 1.24%   |
| 801-900     | 1         | 0.62%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 124       | 89.21%  |
| 16/10 | 13        | 9.35%   |
| 4/3   | 1         | 0.72%   |
| 3/2   | 1         | 0.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 61        | 37.42%  |
| 81-90          | 42        | 25.77%  |
| 151-200        | 10        | 6.13%   |
| 51-60          | 9         | 5.52%   |
| 71-80          | 7         | 4.29%   |
| 61-70          | 6         | 3.68%   |
| 201-250        | 6         | 3.68%   |
| 141-150        | 6         | 3.68%   |
| 121-130        | 5         | 3.07%   |
| 41-50          | 3         | 1.84%   |
| More than 1000 | 2         | 1.23%   |
| 351-500        | 2         | 1.23%   |
| 301-350        | 1         | 0.61%   |
| 131-140        | 1         | 0.61%   |
| 501-1000       | 1         | 0.61%   |
| 91-100         | 1         | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 75        | 47.47%  |
| 121-160       | 54        | 34.18%  |
| 51-100        | 18        | 11.39%  |
| 161-240       | 7         | 4.43%   |
| 1-50          | 3         | 1.9%    |
| More than 240 | 1         | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 115       | 79.86%  |
| 2     | 24        | 16.67%  |
| 0     | 4         | 2.78%   |
| 3     | 1         | 0.69%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 87        | 38.5%   |
| Intel                           | 52        | 23.01%  |
| Qualcomm Atheros                | 44        | 19.47%  |
| Broadcom                        | 19        | 8.41%   |
| Marvell Technology Group        | 5         | 2.21%   |
| Ralink                          | 4         | 1.77%   |
| Broadcom Limited                | 4         | 1.77%   |
| Xiaomi                          | 2         | 0.88%   |
| TP-Link                         | 2         | 0.88%   |
| MediaTek                        | 2         | 0.88%   |
| Samsung Electronics             | 1         | 0.44%   |
| Ralink Technology               | 1         | 0.44%   |
| Qualcomm Atheros Communications | 1         | 0.44%   |
| Hewlett-Packard                 | 1         | 0.44%   |
| ASIX Electronics                | 1         | 0.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 17.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 10.49%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11        | 4.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 10        | 3.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 3.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 3%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 2.25%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 5         | 1.87%   |
| Intel Wireless 3160                                               | 5         | 1.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 1.87%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.5%    |
| Intel Wireless 7260                                               | 4         | 1.5%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 1.12%   |
| Intel Wireless 7265                                               | 3         | 1.12%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.12%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.75%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.75%   |
| Intel Wireless 8260                                               | 2         | 0.75%   |
| Intel WiFi Link 5100                                              | 2         | 0.75%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 2         | 0.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.75%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.75%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 0.75%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.75%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.37%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 35.86%  |
| Qualcomm Atheros                | 38        | 26.21%  |
| Realtek Semiconductor           | 30        | 20.69%  |
| Broadcom                        | 14        | 9.66%   |
| Ralink                          | 4         | 2.76%   |
| MediaTek                        | 2         | 1.38%   |
| Broadcom Limited                | 2         | 1.38%   |
| TP-Link                         | 1         | 0.69%   |
| Ralink Technology               | 1         | 0.69%   |
| Qualcomm Atheros Communications | 1         | 0.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 11        | 7.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 10        | 6.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 10        | 6.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 8         | 5.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 6         | 4.08%   |
| Realtek RTL8723DE Wireless Network Adapter                    | 5         | 3.4%    |
| Intel Wireless 3160                                           | 5         | 3.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 5         | 3.4%    |
| Intel Wireless 8265 / 8275                                    | 4         | 2.72%   |
| Intel Wireless 7260                                           | 4         | 2.72%   |
| Realtek RTL8188EE Wireless Network Adapter                    | 3         | 2.04%   |
| Intel Wireless 7265                                           | 3         | 2.04%   |
| Intel Wi-Fi 6 AX201                                           | 3         | 2.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 3         | 2.04%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 3         | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 1.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 2         | 1.36%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 2         | 1.36%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 2         | 1.36%   |
| Intel Wireless 8260                                           | 2         | 1.36%   |
| Intel WiFi Link 5100                                          | 2         | 1.36%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection | 2         | 1.36%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 2         | 1.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 1.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 2         | 1.36%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 2         | 1.36%   |
| Broadcom BCM43142 802.11b/g/n                                 | 2         | 1.36%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                           | 1         | 0.68%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 1         | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 0.68%   |
| Realtek RTL8191SEvA Wireless LAN Controller                   | 1         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1         | 0.68%   |
| Realtek 802.11n WLAN Adapter                                  | 1         | 0.68%   |
| Realtek 802.11ac WLAN Adapter                                 | 1         | 0.68%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 0.68%   |
| Ralink RT3592 Wireless 802.11abgn 2T/2R PCIe                  | 1         | 0.68%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 1         | 0.68%   |
| Qualcomm Atheros AR9271 802.11n                               | 1         | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 78        | 67.24%  |
| Qualcomm Atheros         | 11        | 9.48%   |
| Intel                    | 9         | 7.76%   |
| Broadcom                 | 7         | 6.03%   |
| Marvell Technology Group | 5         | 4.31%   |
| Xiaomi                   | 2         | 1.72%   |
| Broadcom Limited         | 2         | 1.72%   |
| TP-Link                  | 1         | 0.86%   |
| ASIX Electronics         | 1         | 0.86%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 39.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 28        | 23.93%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.56%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 2.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.71%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.71%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.71%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.71%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.71%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.85%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.85%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.85%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.85%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.85%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.85%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.85%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.85%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.85%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.85%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.85%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.85%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.85%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.85%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 1         | 0.85%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.85%   |
| Broadcom Limited NetXtreme BCM5751M Gigabit Ethernet PCI Express  | 1         | 0.85%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 1         | 0.85%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 141       | 54.65%  |
| Ethernet | 114       | 44.19%  |
| Modem    | 3         | 1.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 112       | 76.19%  |
| Ethernet | 35        | 23.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 107       | 75.35%  |
| 1     | 34        | 23.94%  |
| 0     | 1         | 0.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 119       | 82.64%  |
| Yes  | 25        | 17.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 33.03%  |
| Realtek Semiconductor           | 18        | 16.51%  |
| Qualcomm Atheros Communications | 17        | 15.6%   |
| Foxconn / Hon Hai               | 8         | 7.34%   |
| Lite-On Technology              | 5         | 4.59%   |
| IMC Networks                    | 5         | 4.59%   |
| Broadcom                        | 5         | 4.59%   |
| Toshiba                         | 3         | 2.75%   |
| Apple                           | 3         | 2.75%   |
| Ralink Technology               | 2         | 1.83%   |
| Ralink                          | 2         | 1.83%   |
| Hewlett-Packard                 | 1         | 0.92%   |
| Foxconn International           | 1         | 0.92%   |
| Dell                            | 1         | 0.92%   |
| Cambridge Silicon Radio         | 1         | 0.92%   |
| Alps Electric                   | 1         | 0.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 20        | 18.35%  |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 11.01%  |
| Realtek  Bluetooth 4.2 Adapter                      | 10        | 9.17%   |
| Realtek Bluetooth Radio                             | 7         | 6.42%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 5.5%    |
| Intel AX201 Bluetooth                               | 5         | 4.59%   |
| IMC Networks Bluetooth Radio                        | 4         | 3.67%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 3.67%   |
| Toshiba Bluetooth Device                            | 3         | 2.75%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.83%   |
| Lite-On Bluetooth Device                            | 2         | 1.83%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 1.83%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.92%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.92%   |
| Ralink CSR BS8510                                   | 1         | 0.92%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.92%   |
| Lite-On Wireless_Device                             | 1         | 0.92%   |
| Lite-On Bluetooth Radio                             | 1         | 0.92%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.92%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.92%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.92%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.92%   |
| Intel AX200 Bluetooth                               | 1         | 0.92%   |
| IMC Networks BCM20702A0                             | 1         | 0.92%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.92%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.92%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.92%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.92%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.92%   |
| Broadcom HP Portable Valentine                      | 1         | 0.92%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.92%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.92%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 0.92%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.92%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 115       | 73.25%  |
| AMD                 | 28        | 17.83%  |
| Nvidia              | 11        | 7.01%   |
| Focusrite-Novation  | 1         | 0.64%   |
| C-Media Electronics | 1         | 0.64%   |
| Apple               | 1         | 0.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 10.4%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 6.93%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 5.45%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 4.46%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 4.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 3.96%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 3.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 3.47%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.97%   |
| AMD FCH Azalia Controller                                                                         | 6         | 2.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 2.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 2.48%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 2.48%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 2.48%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 2.48%   |
| AMD High Definition Audio Controller                                                              | 5         | 2.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.49%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.49%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.49%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.49%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.99%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.99%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 0.99%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.99%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 0.99%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.5%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.5%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.5%    |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 32.32%  |
| SK hynix            | 22        | 22.22%  |
| Kingston            | 11        | 11.11%  |
| Micron Technology   | 10        | 10.1%   |
| Ramaxel Technology  | 5         | 5.05%   |
| Unknown             | 4         | 4.04%   |
| Nanya Technology    | 3         | 3.03%   |
| A-DATA Technology   | 3         | 3.03%   |
| Unknown (ABCD)      | 2         | 2.02%   |
| Crucial             | 2         | 2.02%   |
| Team                | 1         | 1.01%   |
| Goodram             | 1         | 1.01%   |
| Elpida              | 1         | 1.01%   |
| Corsair             | 1         | 1.01%   |
| Avant               | 1         | 1.01%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 3.85%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 2.88%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.92%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.92%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.92%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 1.92%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.92%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.92%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s          | 2         | 1.92%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM 1334MT/s                  | 2         | 1.92%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.92%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 1.92%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.96%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.96%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.96%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.96%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                         | 1         | 0.96%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 8400MT/s             | 1         | 0.96%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.96%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.96%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.96%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.96%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.96%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.96%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.96%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.96%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.96%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.96%   |
| SK hynix RAM HMA851S6DJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.96%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.96%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.96%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 0.96%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.96%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.96%   |
| SK hynix RAM H9HCNNNBKMMLXR-NEE 1GB LPDDR4 3733MT/s              | 1         | 0.96%   |
| SK hynix RAM H9CCNNN8GTMLAR-NUD 2GB SODIMM LPDDR3 1776MT/s       | 1         | 0.96%   |
| Samsung RAM Module 8GB Row Of Chips DDR4 3200MT/s                | 1         | 0.96%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.96%   |
| Samsung RAM M471B5773DH0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 0.96%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 0.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 38        | 49.35%  |
| DDR3    | 25        | 32.47%  |
| LPDDR4  | 5         | 6.49%   |
| LPDDR3  | 3         | 3.9%    |
| DDR2    | 3         | 3.9%    |
| SDRAM   | 2         | 2.6%    |
| Unknown | 1         | 1.3%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 70        | 92.11%  |
| Row Of Chips | 5         | 6.58%   |
| Unknown      | 1         | 1.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 35        | 40.7%   |
| 8192  | 29        | 33.72%  |
| 16384 | 10        | 11.63%  |
| 2048  | 8         | 9.3%    |
| 1024  | 3         | 3.49%   |
| 32768 | 1         | 1.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 28        | 31.82%  |
| 1600    | 22        | 25%     |
| 3200    | 6         | 6.82%   |
| 2400    | 6         | 6.82%   |
| 1334    | 5         | 5.68%   |
| 3266    | 4         | 4.55%   |
| 4199    | 2         | 2.27%   |
| 2133    | 2         | 2.27%   |
| 667     | 2         | 2.27%   |
| 8400    | 1         | 1.14%   |
| 4267    | 1         | 1.14%   |
| 3733    | 1         | 1.14%   |
| 1867    | 1         | 1.14%   |
| 1776    | 1         | 1.14%   |
| 1333    | 1         | 1.14%   |
| 1066    | 1         | 1.14%   |
| 975     | 1         | 1.14%   |
| 933     | 1         | 1.14%   |
| 800     | 1         | 1.14%   |
| Unknown | 1         | 1.14%   |

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
| Chicony Electronics                    | 34        | 26.15%  |
| IMC Networks                           | 15        | 11.54%  |
| Realtek Semiconductor                  | 11        | 8.46%   |
| Microdia                               | 9         | 6.92%   |
| Quanta                                 | 8         | 6.15%   |
| Suyin                                  | 7         | 5.38%   |
| Syntek                                 | 6         | 4.62%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.62%   |
| Sunplus Innovation Technology          | 5         | 3.85%   |
| Lite-On Technology                     | 5         | 3.85%   |
| Silicon Motion                         | 3         | 2.31%   |
| Ricoh                                  | 3         | 2.31%   |
| Acer                                   | 3         | 2.31%   |
| OmniVision Technologies                | 2         | 1.54%   |
| Apple                                  | 2         | 1.54%   |
| Alcor Micro                            | 2         | 1.54%   |
| Sonix Technology                       | 1         | 0.77%   |
| Samsung Electronics                    | 1         | 0.77%   |
| Luxvisions Innotech Limited            | 1         | 0.77%   |
| Lenovo                                 | 1         | 0.77%   |
| Importek                               | 1         | 0.77%   |
| icSpring                               | 1         | 0.77%   |
| Generalplus Technology                 | 1         | 0.77%   |
| Foxconn / Hon Hai                      | 1         | 0.77%   |
| ALi                                    | 1         | 0.77%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 6         | 4.62%   |
| Realtek Integrated_Webcam_HD                        | 4         | 3.08%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 3.08%   |
| Chicony Integrated Camera                           | 4         | 3.08%   |
| Chicony HP Truevision HD                            | 4         | 3.08%   |
| IMC Networks TOSHIBA Web Camera - HD                | 3         | 2.31%   |
| Chicony TOSHIBA Web Camera - HD                     | 3         | 2.31%   |
| Syntek Lenovo EasyCamera                            | 2         | 1.54%   |
| Syntek EasyCamera                                   | 2         | 1.54%   |
| Suyin Integrated_Webcam_HD                          | 2         | 1.54%   |
| Suyin HP Truevision HD                              | 2         | 1.54%   |
| Suyin HD WebCam                                     | 2         | 1.54%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.54%   |
| Realtek Integrated Webcam                           | 2         | 1.54%   |
| Realtek HP "Truevision HD" laptop camera            | 2         | 1.54%   |
| Quanta HP Webcam-50                                 | 2         | 1.54%   |
| Quanta HP Webcam                                    | 2         | 1.54%   |
| OmniVision OV2640 Webcam                            | 2         | 1.54%   |
| Lite-On TOSHIBA Web Camera - HD                     | 2         | 1.54%   |
| Lite-On HP TrueVision HD Camera                     | 2         | 1.54%   |
| IMC Networks VGA UVC WebCam                         | 2         | 1.54%   |
| IMC Networks Integrated Camera                      | 2         | 1.54%   |
| Chicony HP Wide Vision HD Camera                    | 2         | 1.54%   |
| Chicony HP HD Webcam [Fixed]                        | 2         | 1.54%   |
| Chicony HD User Facing                              | 2         | 1.54%   |
| Chicony EasyCamera                                  | 2         | 1.54%   |
| Syntek USB Video Device                             | 1         | 0.77%   |
| Syntek Integrated Camera                            | 1         | 0.77%   |
| Suyin Asus Integrated Webcam                        | 1         | 0.77%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.77%   |
| Sunplus HP TrueVision HD Camera                     | 1         | 0.77%   |
| Sunplus HD WebCam                                   | 1         | 0.77%   |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 0.77%   |
| Silicon Motion WebCam SC-10HDP12631N                | 1         | 0.77%   |
| Silicon Motion WebCam SC-03FFL11939N                | 1         | 0.77%   |
| Silicon Motion Web Camera                           | 1         | 0.77%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 0.77%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870] | 1         | 0.77%   |
| Ricoh Sony Vaio Integrated Webcam                   | 1         | 0.77%   |
| Ricoh Integrated_Webcam_1.3M                        | 1         | 0.77%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 3         | 27.27%  |
| AuthenTec             | 3         | 27.27%  |
| Upek                  | 1         | 9.09%   |
| Synaptics             | 1         | 9.09%   |
| STMicroelectronics    | 1         | 9.09%   |
| LighTuning Technology | 1         | 9.09%   |
| Elan Microelectronics | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Swipe Fingerprint Sensor              | 2         | 18.18%  |
| AuthenTec AES1600                                      | 2         | 18.18%  |
| Validity Sensors Fingerprint scanner                   | 1         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 9.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 9.09%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 9.09%   |
| LighTuning Fingerprint Sensor                          | 1         | 9.09%   |
| Elan ELAN:Fingerprint                                  | 1         | 9.09%   |
| AuthenTec AES2810                                      | 1         | 9.09%   |

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
| 0     | 104       | 72.73%  |
| 1     | 32        | 22.38%  |
| 2     | 6         | 4.2%    |
| 5     | 1         | 0.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 11        | 22.45%  |
| Net/wireless             | 10        | 20.41%  |
| Graphics card            | 9         | 18.37%  |
| Chipcard                 | 5         | 10.2%   |
| Multimedia controller    | 4         | 8.16%   |
| Bluetooth                | 3         | 6.12%   |
| Storage                  | 2         | 4.08%   |
| Sound                    | 2         | 4.08%   |
| Network                  | 1         | 2.04%   |
| Communication controller | 1         | 2.04%   |
| Camera                   | 1         | 2.04%   |

