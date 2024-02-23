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

Total: 287

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell      | Latitude D630               | [bf9ce8c208](https://linux-hardware.org/?probe=bf9ce8c208) | Jan 21, 2024 |
| Dell      | Latitude D630               | [b2a68014db](https://linux-hardware.org/?probe=b2a68014db) | Jan 21, 2024 |
| Acer      | Aspire A715-51G             | [2a3ea77b7a](https://linux-hardware.org/?probe=2a3ea77b7a) | Jan 10, 2024 |
| Acer      | Aspire A715-51G             | [d4a9b3c259](https://linux-hardware.org/?probe=d4a9b3c259) | Jan 09, 2024 |
| Lenovo    | IdeaPad S145-14API 81UV     | [3a14a938f8](https://linux-hardware.org/?probe=3a14a938f8) | Jan 08, 2024 |
| HP        | 1000                        | [2279f68ba4](https://linux-hardware.org/?probe=2279f68ba4) | Dec 21, 2023 |
| HP        | OMEN by Laptop 15-dh1xxx    | [6a493a834d](https://linux-hardware.org/?probe=6a493a834d) | Dec 14, 2023 |
| HP        | OMEN by Laptop 15-dh1xxx    | [9d34609e0d](https://linux-hardware.org/?probe=9d34609e0d) | Dec 14, 2023 |
| HP        | Laptop 15-dw1xxx            | [d05f324edf](https://linux-hardware.org/?probe=d05f324edf) | Nov 22, 2023 |
| Lenovo    | IdeaPad 5 Pro 16IHU6 82L... | [cc934b68d9](https://linux-hardware.org/?probe=cc934b68d9) | Nov 22, 2023 |
| HP        | Unknown                     | [d065dfae65](https://linux-hardware.org/?probe=d065dfae65) | Nov 19, 2023 |
| HP        | Unknown                     | [539958ff9d](https://linux-hardware.org/?probe=539958ff9d) | Nov 19, 2023 |
| MSI       | PRO H610M-G DDR4            | [5955e4e776](https://linux-hardware.org/?probe=5955e4e776) | Nov 15, 2023 |
| MSI       | PRO H610M-G DDR4            | [f41807e01e](https://linux-hardware.org/?probe=f41807e01e) | Nov 14, 2023 |
| Toshiba   | Satellite S55-B             | [bcc2e19a3a](https://linux-hardware.org/?probe=bcc2e19a3a) | Nov 12, 2023 |
| HP        | 245 G8                      | [0b471d312a](https://linux-hardware.org/?probe=0b471d312a) | Nov 11, 2023 |
| HP        | 245 G8                      | [b29efc88ec](https://linux-hardware.org/?probe=b29efc88ec) | Nov 11, 2023 |
| HP        | 245 G8                      | [e9c1cc78b8](https://linux-hardware.org/?probe=e9c1cc78b8) | Nov 06, 2023 |
| Razer     | Blade Stealth               | [0ebbfdba6a](https://linux-hardware.org/?probe=0ebbfdba6a) | Oct 26, 2023 |
| HP        | Pavilion Laptop 15-cw1xx... | [21a31e5298](https://linux-hardware.org/?probe=21a31e5298) | Oct 21, 2023 |
| MSI       | Stealth 16Studio A13VG      | [46e4f7a743](https://linux-hardware.org/?probe=46e4f7a743) | Oct 21, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop X160... | [3a6c620560](https://linux-hardware.org/?probe=3a6c620560) | Oct 13, 2023 |
| Alienware | m15                         | [9ac9acc336](https://linux-hardware.org/?probe=9ac9acc336) | Oct 12, 2023 |
| Alienware | m15                         | [8b4a8c8fc9](https://linux-hardware.org/?probe=8b4a8c8fc9) | Oct 12, 2023 |
| Apple     | MacBookPro12,1              | [bd6094c5cd](https://linux-hardware.org/?probe=bd6094c5cd) | Oct 08, 2023 |
| Apple     | MacBookPro12,1              | [d343f99b47](https://linux-hardware.org/?probe=d343f99b47) | Oct 06, 2023 |
| Toshiba   | Satellite A205              | [7b78b2ea5b](https://linux-hardware.org/?probe=7b78b2ea5b) | Oct 06, 2023 |
| Lenovo    | ThinkPad X13 Gen 1 20UGA... | [8c1d3fc469](https://linux-hardware.org/?probe=8c1d3fc469) | Sep 29, 2023 |
| Lenovo    | ThinkPad X13 Gen 1 20UGA... | [c38ca27643](https://linux-hardware.org/?probe=c38ca27643) | Sep 29, 2023 |
| Valve     | Jupiter                     | [f4582a5754](https://linux-hardware.org/?probe=f4582a5754) | Sep 22, 2023 |
| Lenovo    | IdeaPad 3 15ADA05 81W1      | [5fac0d7732](https://linux-hardware.org/?probe=5fac0d7732) | Sep 20, 2023 |
| Dell      | Latitude E5430 non-vPro     | [09c45a1e2d](https://linux-hardware.org/?probe=09c45a1e2d) | Sep 17, 2023 |
| Lenovo    | ThinkPad E520 11433FU       | [eb0aa53dc9](https://linux-hardware.org/?probe=eb0aa53dc9) | Sep 08, 2023 |
| Toshiba   | Satellite A205              | [9a44e74608](https://linux-hardware.org/?probe=9a44e74608) | Sep 06, 2023 |
| Toshiba   | Satellite A205              | [a2b456886d](https://linux-hardware.org/?probe=a2b456886d) | Sep 05, 2023 |
| Lenovo    | ThinkPad E520 11433FU       | [ecc10a1197](https://linux-hardware.org/?probe=ecc10a1197) | Sep 04, 2023 |
| Toshiba   | Satellite L50-B             | [9dd40cd022](https://linux-hardware.org/?probe=9dd40cd022) | Sep 03, 2023 |
| HP        | Laptop 14-cm0xxx            | [a1caab6466](https://linux-hardware.org/?probe=a1caab6466) | Aug 27, 2023 |
| Apple     | MacBookPro9,2               | [4ea732e404](https://linux-hardware.org/?probe=4ea732e404) | Aug 17, 2023 |
| Lenovo    | IdeaPad 3 14ITL6 82H7       | [bbf57bf744](https://linux-hardware.org/?probe=bbf57bf744) | Aug 17, 2023 |
| Apple     | MacBookPro5,5               | [ee72caa76d](https://linux-hardware.org/?probe=ee72caa76d) | Aug 16, 2023 |
| ASUSTek   | VivoBook_ASUS Laptop X51... | [2a3b142ddd](https://linux-hardware.org/?probe=2a3b142ddd) | Aug 16, 2023 |
| Lenovo    | Legion 5 15ACH6 82JW        | [5bd12768fa](https://linux-hardware.org/?probe=5bd12768fa) | Aug 09, 2023 |
| Dell      | Vostro 3480                 | [78fbe42595](https://linux-hardware.org/?probe=78fbe42595) | Aug 07, 2023 |
| Toshiba   | Satellite A135              | [2eddaa2a26](https://linux-hardware.org/?probe=2eddaa2a26) | Jul 30, 2023 |
| Toshiba   | Satellite A135              | [5bd6d0c2d8](https://linux-hardware.org/?probe=5bd6d0c2d8) | Jul 20, 2023 |
| HP        | ENVY m6 Notebook            | [602c50a904](https://linux-hardware.org/?probe=602c50a904) | Jul 06, 2023 |
| HUAWEI    | BOHK-WAX9X                  | [b05e4ee752](https://linux-hardware.org/?probe=b05e4ee752) | Jun 15, 2023 |
| Dell      | Inspiron 3493               | [ffcd21fc3b](https://linux-hardware.org/?probe=ffcd21fc3b) | Jun 09, 2023 |
| Acer      | Aspire A515-45              | [f661806559](https://linux-hardware.org/?probe=f661806559) | Jun 02, 2023 |
| Acer      | Aspire A515-45              | [a57949da97](https://linux-hardware.org/?probe=a57949da97) | Jun 01, 2023 |
| Lenovo    | IdeaPad S145-15AST 81N3     | [7f0cf2e62d](https://linux-hardware.org/?probe=7f0cf2e62d) | Jun 01, 2023 |
| Lenovo    | IdeaPad 330S-15IKB 81F5     | [5f8bd19e3d](https://linux-hardware.org/?probe=5f8bd19e3d) | May 31, 2023 |
| Lenovo    | ThinkPad L480 20LTA01LLM    | [ed45fc495a](https://linux-hardware.org/?probe=ed45fc495a) | May 22, 2023 |
| Lenovo    | IdeaPad 3 15ALC6 82KU       | [8fb1a89166](https://linux-hardware.org/?probe=8fb1a89166) | May 17, 2023 |
| Acer      | Extensa 5220                | [261e743adc](https://linux-hardware.org/?probe=261e743adc) | May 11, 2023 |
| Sony      | VPCEG23EL                   | [c28e3338ce](https://linux-hardware.org/?probe=c28e3338ce) | Apr 28, 2023 |
| Lenovo    | IdeaPad S145-14IGM 81MW     | [5cb6709055](https://linux-hardware.org/?probe=5cb6709055) | Apr 20, 2023 |
| HP        | Notebook                    | [4a5d785f73](https://linux-hardware.org/?probe=4a5d785f73) | Apr 09, 2023 |
| HP        | 245 G6                      | [c6a1e2951c](https://linux-hardware.org/?probe=c6a1e2951c) | Apr 05, 2023 |
| Valve     | Jupiter                     | [078e440a68](https://linux-hardware.org/?probe=078e440a68) | Mar 31, 2023 |
| Acer      | Aspire A515-43              | [1812fe9a19](https://linux-hardware.org/?probe=1812fe9a19) | Mar 26, 2023 |
| Acer      | Aspire A515-43              | [a302d93972](https://linux-hardware.org/?probe=a302d93972) | Mar 26, 2023 |
| ASUSTek   | ASUS TUF Gaming A15 FA50... | [9e45f992a1](https://linux-hardware.org/?probe=9e45f992a1) | Mar 25, 2023 |
| ASUSTek   | ASUS TUF Gaming A15 FA50... | [34fd631d2b](https://linux-hardware.org/?probe=34fd631d2b) | Mar 22, 2023 |
| Samsung   | R519/R719                   | [9e1cdf3582](https://linux-hardware.org/?probe=9e1cdf3582) | Mar 17, 2023 |
| HP        | Laptop 14-cf3xxx            | [bdb510861b](https://linux-hardware.org/?probe=bdb510861b) | Mar 16, 2023 |
| HP        | Laptop 14-cf3xxx            | [75a93c0ac6](https://linux-hardware.org/?probe=75a93c0ac6) | Mar 16, 2023 |
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


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 23        | 11.22%  |
| Ubuntu 18.04                 | 11        | 5.37%   |
| Ubuntu 22.04                 | 8         | 3.9%    |
| Debian 11                    | 8         | 3.9%    |
| Linux Mint 20.3              | 7         | 3.41%   |
| KDE neon 20.04               | 6         | 2.93%   |
| Fedora 38                    | 6         | 2.93%   |
| OpenMandriva 4.3             | 5         | 2.44%   |
| Linux Mint 21.1              | 5         | 2.44%   |
| Linux Mint 19.3              | 5         | 2.44%   |
| Zorin 16                     | 4         | 1.95%   |
| Zorin 15                     | 4         | 1.95%   |
| Pop!_OS 21.10                | 3         | 1.46%   |
| OpenMandriva 23.03           | 3         | 1.46%   |
| LMDE 5                       | 3         | 1.46%   |
| LMDE 4                       | 3         | 1.46%   |
| Linux Mint 21.2              | 3         | 1.46%   |
| Fedora 37                    | 3         | 1.46%   |
| Fedora 34                    | 3         | 1.46%   |
| Fedora 33                    | 3         | 1.46%   |
| Xubuntu 20.04                | 2         | 0.98%   |
| Ubuntu 23.10                 | 2         | 0.98%   |
| Ubuntu 22.10                 | 2         | 0.98%   |
| Ubuntu 21.10                 | 2         | 0.98%   |
| Ubuntu 21.04                 | 2         | 0.98%   |
| Ubuntu                       | 2         | 0.98%   |
| Pop!_OS 21.04                | 2         | 0.98%   |
| Pop!_OS 20.04                | 2         | 0.98%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.98%   |
| OpenMandriva 23.01           | 2         | 0.98%   |
| Linux Mint 20.1              | 2         | 0.98%   |
| Linux Mint 20                | 2         | 0.98%   |
| Kubuntu 22.04                | 2         | 0.98%   |
| Garuda Linux Soaring         | 2         | 0.98%   |
| Fedora 36                    | 2         | 0.98%   |
| Elementary 5.1.7             | 2         | 0.98%   |
| Debian 12                    | 2         | 0.98%   |
| BlackPanther 18.1            | 2         | 0.98%   |
| ArcoLinux Rolling            | 2         | 0.98%   |
| Arch Rolling                 | 2         | 0.98%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 53        | 26.77%  |
| Linux Mint    | 24        | 12.12%  |
| Fedora        | 21        | 10.61%  |
| OpenMandriva  | 13        | 6.57%   |
| Debian        | 12        | 6.06%   |
| Zorin         | 8         | 4.04%   |
| Pop!_OS       | 8         | 4.04%   |
| KDE neon      | 7         | 3.54%   |
| LMDE          | 5         | 2.53%   |
| Elementary    | 5         | 2.53%   |
| Xubuntu       | 4         | 2.02%   |
| Manjaro       | 4         | 2.02%   |
| Lubuntu       | 4         | 2.02%   |
| Kubuntu       | 3         | 1.52%   |
| Arch          | 3         | 1.52%   |
| Ubuntu MATE   | 2         | 1.01%   |
| Ubuntu Budgie | 2         | 1.01%   |
| SteamOS       | 2         | 1.01%   |
| openSUSE      | 2         | 1.01%   |
| Kali          | 2         | 1.01%   |
| Garuda Linux  | 2         | 1.01%   |
| Endless       | 2         | 1.01%   |
| BlackPanther  | 2         | 1.01%   |
| ArcoLinux     | 2         | 1.01%   |
| Xero          | 1         | 0.51%   |
| Void Linux    | 1         | 0.51%   |
| RHEL          | 1         | 0.51%   |
| Parrot        | 1         | 0.51%   |
| EndeavourOS   | 1         | 0.51%   |
| Deepin        | 1         | 0.51%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-54-generic         | 4         | 1.81%   |
| 5.4.0-42-generic         | 4         | 1.81%   |
| 5.16.7-desktop-1omv4003  | 4         | 1.81%   |
| 5.15.0-33-generic        | 4         | 1.81%   |
| 5.13.0-35-generic        | 4         | 1.81%   |
| 5.4.0-58-generic         | 3         | 1.36%   |
| 5.4.0-56-generic         | 3         | 1.36%   |
| 5.4.0-48-generic         | 3         | 1.36%   |
| 5.4.0-45-generic         | 3         | 1.36%   |
| 5.4.0-26-generic         | 3         | 1.36%   |
| 5.16.11-76051611-generic | 3         | 1.36%   |
| 5.15.0-56-generic        | 3         | 1.36%   |
| 6.2.6-desktop-1omv2390   | 2         | 0.9%    |
| 6.1.1-desktop-1omv2290   | 2         | 0.9%    |
| 6.1.0-13-amd64           | 2         | 0.9%    |
| 5.8.0-43-generic         | 2         | 0.9%    |
| 5.8.0-41-generic         | 2         | 0.9%    |
| 5.8.0-14-generic         | 2         | 0.9%    |
| 5.4.0-77-generic         | 2         | 0.9%    |
| 5.4.0-7634-generic       | 2         | 0.9%    |
| 5.4.0-110-generic        | 2         | 0.9%    |
| 5.3.0-62-generic         | 2         | 0.9%    |
| 5.15.59-xanmod1          | 2         | 0.9%    |
| 5.15.0-58-generic        | 2         | 0.9%    |
| 5.15.0-27-generic        | 2         | 0.9%    |
| 5.13.0-7614-generic      | 2         | 0.9%    |
| 5.13.0-51-generic        | 2         | 0.9%    |
| 5.13.0-27-generic        | 2         | 0.9%    |
| 5.10.0-23-amd64          | 2         | 0.9%    |
| 5.0.0-37-generic         | 2         | 0.9%    |
| 5.0.0-23-generic         | 2         | 0.9%    |
| 4.18.16-desktop-1bP      | 2         | 0.9%    |
| 4.15.0-54-generic        | 2         | 0.9%    |
| 6.5.9-arch2-1            | 1         | 0.45%   |
| 6.5.9-1-default          | 1         | 0.45%   |
| 6.5.6-200.fc38.x86_64    | 1         | 0.45%   |
| 6.5.3-1-default          | 1         | 0.45%   |
| 6.5.11-300.fc39.x86_64   | 1         | 0.45%   |
| 6.5.0-kali3-amd64        | 1         | 0.45%   |
| 6.5.0-9-generic          | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 42        | 20%     |
| 5.15.0  | 22        | 10.48%  |
| 5.13.0  | 15        | 7.14%   |
| 4.15.0  | 8         | 3.81%   |
| 5.8.0   | 7         | 3.33%   |
| 5.0.0   | 7         | 3.33%   |
| 5.10.0  | 6         | 2.86%   |
| 6.1.0   | 5         | 2.38%   |
| 5.11.0  | 5         | 2.38%   |
| 6.5.0   | 4         | 1.9%    |
| 6.2.0   | 4         | 1.9%    |
| 5.3.0   | 4         | 1.9%    |
| 5.19.0  | 4         | 1.9%    |
| 5.16.7  | 4         | 1.9%    |
| 5.16.11 | 3         | 1.43%   |
| 6.5.9   | 2         | 0.95%   |
| 6.4.10  | 2         | 0.95%   |
| 6.3.5   | 2         | 0.95%   |
| 6.2.6   | 2         | 0.95%   |
| 6.2.2   | 2         | 0.95%   |
| 6.1.1   | 2         | 0.95%   |
| 5.17.5  | 2         | 0.95%   |
| 5.15.59 | 2         | 0.95%   |
| 4.18.16 | 2         | 0.95%   |
| 4.18.0  | 2         | 0.95%   |
| 6.5.6   | 1         | 0.48%   |
| 6.5.3   | 1         | 0.48%   |
| 6.5.11  | 1         | 0.48%   |
| 6.4.8   | 1         | 0.48%   |
| 6.4.6   | 1         | 0.48%   |
| 6.2.9   | 1         | 0.48%   |
| 6.2.15  | 1         | 0.48%   |
| 6.2.12  | 1         | 0.48%   |
| 6.1.9   | 1         | 0.48%   |
| 6.1.2   | 1         | 0.48%   |
| 6.0.2   | 1         | 0.48%   |
| 6.0.18  | 1         | 0.48%   |
| 6.0.10  | 1         | 0.48%   |
| 5.9.16  | 1         | 0.48%   |
| 5.8.15  | 1         | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 45        | 21.84%  |
| 5.15    | 26        | 12.62%  |
| 5.13    | 15        | 7.28%   |
| 6.2     | 11        | 5.34%   |
| 5.16    | 10        | 4.85%   |
| 5.10    | 10        | 4.85%   |
| 6.5     | 9         | 4.37%   |
| 6.1     | 9         | 4.37%   |
| 5.8     | 8         | 3.88%   |
| 4.15    | 8         | 3.88%   |
| 5.11    | 7         | 3.4%    |
| 5.0     | 7         | 3.4%    |
| 5.19    | 6         | 2.91%   |
| 5.3     | 5         | 2.43%   |
| 6.4     | 4         | 1.94%   |
| 4.18    | 4         | 1.94%   |
| 6.0     | 3         | 1.46%   |
| 5.18    | 3         | 1.46%   |
| 5.14    | 3         | 1.46%   |
| 6.3     | 2         | 0.97%   |
| 5.7     | 2         | 0.97%   |
| 5.5     | 2         | 0.97%   |
| 5.17    | 2         | 0.97%   |
| 5.12    | 2         | 0.97%   |
| 5.9     | 1         | 0.49%   |
| 4.9     | 1         | 0.49%   |
| 4.19    | 1         | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 179       | 94.71%  |
| i686   | 10        | 5.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 82        | 41.41%  |
| KDE5       | 32        | 16.16%  |
| X-Cinnamon | 22        | 11.11%  |
| Unknown    | 20        | 10.1%   |
| XFCE       | 12        | 6.06%   |
| MATE       | 7         | 3.54%   |
| Pantheon   | 5         | 2.53%   |
| KDE        | 5         | 2.53%   |
| LXQt       | 4         | 2.02%   |
| LXDE       | 2         | 1.01%   |
| Budgie     | 2         | 1.01%   |
| qtile      | 1         | 0.51%   |
| jwm        | 1         | 0.51%   |
| ICEWM      | 1         | 0.51%   |
| Deepin     | 1         | 0.51%   |
| Cinnamon   | 1         | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 148       | 75.13%  |
| Wayland | 37        | 18.78%  |
| Unknown | 12        | 6.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 104       | 52.26%  |
| SDDM    | 30        | 15.08%  |
| GDM     | 24        | 12.06%  |
| LightDM | 20        | 10.05%  |
| GDM3    | 18        | 9.05%   |
| TDM     | 3         | 1.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_EC   | 86        | 44.56%  |
| en_US   | 50        | 25.91%  |
| es_ES   | 18        | 9.33%   |
| Unknown | 15        | 7.77%   |
| es_MX   | 7         | 3.63%   |
| de_DE   | 4         | 2.07%   |
| es_US   | 3         | 1.55%   |
| es_CO   | 3         | 1.55%   |
| es_PE   | 2         | 1.04%   |
| C       | 2         | 1.04%   |
| ru_RU   | 1         | 0.52%   |
| fr_FR   | 1         | 0.52%   |
| en_GB   | 1         | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 109       | 56.19%  |
| BIOS | 85        | 43.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 144       | 74.23%  |
| Btrfs   | 24        | 12.37%  |
| Overlay | 15        | 7.73%   |
| Tmpfs   | 5         | 2.58%   |
| Zfs     | 2         | 1.03%   |
| Xfs     | 2         | 1.03%   |
| Ext2    | 1         | 0.52%   |
| Unknown | 1         | 0.52%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 105       | 54.4%   |
| GPT     | 73        | 37.82%  |
| MBR     | 15        | 7.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 164       | 85.86%  |
| Yes       | 27        | 14.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 133       | 69.27%  |
| Yes       | 59        | 30.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 43        | 22.75%  |
| Lenovo              | 31        | 16.4%   |
| Dell                | 29        | 15.34%  |
| ASUSTek Computer    | 17        | 8.99%   |
| Toshiba             | 14        | 7.41%   |
| Acer                | 10        | 5.29%   |
| Apple               | 8         | 4.23%   |
| Sony                | 6         | 3.17%   |
| Google              | 6         | 3.17%   |
| Samsung Electronics | 4         | 2.12%   |
| MSI                 | 3         | 1.59%   |
| Gateway             | 3         | 1.59%   |
| Unknown             | 3         | 1.59%   |
| Valve               | 2         | 1.06%   |
| Razer               | 2         | 1.06%   |
| Alienware           | 2         | 1.06%   |
| Timi                | 1         | 0.53%   |
| HUAWEI              | 1         | 0.53%   |
| Fujitsu             | 1         | 0.53%   |
| Dynabook            | 1         | 0.53%   |
| Compal              | 1         | 0.53%   |
| Chuwi               | 1         | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 5         | 2.65%   |
| HP Notebook                              | 3         | 1.59%   |
| Valve Jupiter                            | 2         | 1.06%   |
| Toshiba Satellite S55-B                  | 2         | 1.06%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 2         | 1.06%   |
| Lenovo IdeaPad 330S-15IKB 81F5           | 2         | 1.06%   |
| Lenovo IdeaPad 320-15ABR 80XS            | 2         | 1.06%   |
| HP ProBook 4440s                         | 2         | 1.06%   |
| HP Pavilion Laptop 15-cw1xxx             | 2         | 1.06%   |
| HP Pavilion Laptop 15-cw0xxx             | 2         | 1.06%   |
| HP Laptop 15-da0xxx                      | 2         | 1.06%   |
| HP 1000                                  | 2         | 1.06%   |
| Dell Vostro 3480                         | 2         | 1.06%   |
| Dell Inspiron 5570                       | 2         | 1.06%   |
| Dell Inspiron 3442                       | 2         | 1.06%   |
| Dell Inspiron 1420                       | 2         | 1.06%   |
| Dell G5 5587                             | 2         | 1.06%   |
| ASUS ASUS TUF Gaming A15 FA506II_FA506II | 2         | 1.06%   |
| Apple MacBookPro12,1                     | 2         | 1.06%   |
| Toshiba Satellite S55-A                  | 1         | 0.53%   |
| Toshiba Satellite P775                   | 1         | 0.53%   |
| Toshiba Satellite P55W-C                 | 1         | 0.53%   |
| Toshiba Satellite L50-B                  | 1         | 0.53%   |
| Toshiba Satellite L45-B                  | 1         | 0.53%   |
| Toshiba Satellite E45t-B                 | 1         | 0.53%   |
| Toshiba Satellite C55D-A                 | 1         | 0.53%   |
| Toshiba Satellite C55-B                  | 1         | 0.53%   |
| Toshiba Satellite C45-A                  | 1         | 0.53%   |
| Toshiba Satellite A205                   | 1         | 0.53%   |
| Toshiba Satellite A135                   | 1         | 0.53%   |
| Toshiba PORTEGE M805                     | 1         | 0.53%   |
| Timi RedmiBook 14-APCS                   | 1         | 0.53%   |
| Sony VPCEG30EL                           | 1         | 0.53%   |
| Sony VPCEG23EL                           | 1         | 0.53%   |
| Sony VPCCW1S1E                           | 1         | 0.53%   |
| Sony VGN-CR120E                          | 1         | 0.53%   |
| Sony SVE14A25CLB                         | 1         | 0.53%   |
| Sony SVE14113ELW                         | 1         | 0.53%   |
| Samsung R519/R719                        | 1         | 0.53%   |
| Samsung N102SP/N100SP/N101SP             | 1         | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 17        | 8.99%   |
| Dell Inspiron      | 17        | 8.99%   |
| Toshiba Satellite  | 13        | 6.88%   |
| HP Pavilion        | 10        | 5.29%   |
| HP Laptop          | 8         | 4.23%   |
| Lenovo ThinkPad    | 7         | 3.7%    |
| ASUS VivoBook      | 7         | 3.7%    |
| Dell Latitude      | 6         | 3.17%   |
| Acer Aspire        | 6         | 3.17%   |
| Unknown            | 5         | 2.65%   |
| HP ProBook         | 3         | 1.59%   |
| HP Notebook        | 3         | 1.59%   |
| HP ENVY            | 3         | 1.59%   |
| Valve Jupiter      | 2         | 1.06%   |
| Razer Blade        | 2         | 1.06%   |
| HP EliteBook       | 2         | 1.06%   |
| HP 245             | 2         | 1.06%   |
| HP 15              | 2         | 1.06%   |
| HP 1000            | 2         | 1.06%   |
| Dell Vostro        | 2         | 1.06%   |
| Dell G5            | 2         | 1.06%   |
| ASUS ASUS          | 2         | 1.06%   |
| Apple MacBookPro12 | 2         | 1.06%   |
| Acer TravelMate    | 2         | 1.06%   |
| Toshiba PORTEGE    | 1         | 0.53%   |
| Timi RedmiBook     | 1         | 0.53%   |
| Sony VPCEG30EL     | 1         | 0.53%   |
| Sony VPCEG23EL     | 1         | 0.53%   |
| Sony VPCCW1S1E     | 1         | 0.53%   |
| Sony VGN-CR120E    | 1         | 0.53%   |
| Sony SVE14A25CLB   | 1         | 0.53%   |
| Sony SVE14113ELW   | 1         | 0.53%   |
| Samsung R519       | 1         | 0.53%   |
| Samsung N102SP     | 1         | 0.53%   |
| Samsung 550XCJ     | 1         | 0.53%   |
| Samsung 530U4E     | 1         | 0.53%   |
| MSI Stealth        | 1         | 0.53%   |
| MSI MS-7D46        | 1         | 0.53%   |
| MSI GF63           | 1         | 0.53%   |
| Lenovo ZHAOYANG    | 1         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 23        | 12.17%  |
| 2019 | 19        | 10.05%  |
| 2020 | 17        | 8.99%   |
| 2012 | 17        | 8.99%   |
| 2017 | 16        | 8.47%   |
| 2021 | 13        | 6.88%   |
| 2013 | 13        | 6.88%   |
| 2016 | 10        | 5.29%   |
| 2015 | 10        | 5.29%   |
| 2011 | 10        | 5.29%   |
| 2007 | 9         | 4.76%   |
| 2014 | 8         | 4.23%   |
| 2022 | 6         | 3.17%   |
| 2010 | 6         | 3.17%   |
| 2009 | 5         | 2.65%   |
| 2006 | 3         | 1.59%   |
| 2023 | 2         | 1.06%   |
| 2008 | 1         | 0.53%   |
| 2005 | 1         | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 189       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 174       | 92.06%  |
| Enabled  | 15        | 7.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 182       | 96.3%   |
| Yes  | 7         | 3.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 60        | 30.93%  |
| 3.01-4.0    | 39        | 20.1%   |
| 8.01-16.0   | 36        | 18.56%  |
| 16.01-24.0  | 27        | 13.92%  |
| 1.01-2.0    | 14        | 7.22%   |
| 32.01-64.0  | 10        | 5.15%   |
| 2.01-3.0    | 4         | 2.06%   |
| 24.01-32.0  | 2         | 1.03%   |
| 64.01-256.0 | 1         | 0.52%   |
| 0.51-1.0    | 1         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 61        | 29.9%   |
| 1.01-2.0   | 59        | 28.92%  |
| 4.01-8.0   | 37        | 18.14%  |
| 3.01-4.0   | 30        | 14.71%  |
| 8.01-16.0  | 7         | 3.43%   |
| 0.51-1.0   | 7         | 3.43%   |
| 0.01-0.5   | 2         | 0.98%   |
| 24.01-32.0 | 1         | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 141       | 73.44%  |
| 2      | 49        | 25.52%  |
| 3      | 2         | 1.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 127       | 66.84%  |
| Yes       | 63        | 33.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 152       | 80.42%  |
| No        | 37        | 19.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 188       | 99.47%  |
| No        | 1         | 0.53%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 149       | 78.01%  |
| No        | 42        | 21.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Ecuador | 189       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Quito                          | 76        | 38.78%  |
| Guayaquil                      | 51        | 26.02%  |
| Cuenca                         | 23        | 11.73%  |
| Loja                           | 9         | 4.59%   |
| Ambato                         | 5         | 2.55%   |
| Manta                          | 4         | 2.04%   |
| Machala                        | 4         | 2.04%   |
| Portoviejo                     | 3         | 1.53%   |
| Riobamba                       | 2         | 1.02%   |
| Hacienda Ibarra                | 2         | 1.02%   |
| Uyumbicho                      | 1         | 0.51%   |
| Santo Domingo de los Colorados | 1         | 0.51%   |
| Samborondon                    | 1         | 0.51%   |
| Ponceano                       | 1         | 0.51%   |
| Nueva Loja                     | 1         | 0.51%   |
| Montecristi                    | 1         | 0.51%   |
| Latacunga                      | 1         | 0.51%   |
| La Troncal                     | 1         | 0.51%   |
| La Providencia                 | 1         | 0.51%   |
| La Mana                        | 1         | 0.51%   |
| La Concordia Numero Uno        | 1         | 0.51%   |
| Ibarra                         | 1         | 0.51%   |
| Hacienda San Sebastian         | 1         | 0.51%   |
| Guamani                        | 1         | 0.51%   |
| Cayambe                        | 1         | 0.51%   |
| Babahoyo                       | 1         | 0.51%   |
| Ayacucho                       | 1         | 0.51%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 45        | 55     | 19.07%  |
| Toshiba                     | 37        | 40     | 15.68%  |
| Seagate                     | 29        | 45     | 12.29%  |
| Samsung Electronics         | 14        | 14     | 5.93%   |
| Kingston                    | 14        | 16     | 5.93%   |
| SK hynix                    | 11        | 13     | 4.66%   |
| Hitachi                     | 10        | 13     | 4.24%   |
| Unknown                     | 8         | 13     | 3.39%   |
| SanDisk                     | 8         | 12     | 3.39%   |
| A-DATA Technology           | 8         | 11     | 3.39%   |
| HGST                        | 6         | 8      | 2.54%   |
| Hewlett-Packard             | 6         | 6      | 2.54%   |
| Micron Technology           | 5         | 5      | 2.12%   |
| Apple                       | 4         | 5      | 1.69%   |
| KIOXIA                      | 3         | 3      | 1.27%   |
| Kingston Technology Company | 2         | 2      | 0.85%   |
| JMicron Technology          | 2         | 2      | 0.85%   |
| Intel                       | 2         | 3      | 0.85%   |
| Fujitsu                     | 2         | 2      | 0.85%   |
| Crucial                     | 2         | 2      | 0.85%   |
| USB3.0                      | 1         | 1      | 0.42%   |
| UMIS                        | 1         | 1      | 0.42%   |
| SABRENT                     | 1         | 1      | 0.42%   |
| Realtek Semiconductor       | 1         | 1      | 0.42%   |
| PNY                         | 1         | 1      | 0.42%   |
| Phison Electronics          | 1         | 1      | 0.42%   |
| Phison                      | 1         | 1      | 0.42%   |
| Patriot                     | 1         | 1      | 0.42%   |
| OWC                         | 1         | 1      | 0.42%   |
| Netac                       | 1         | 1      | 0.42%   |
| Micron/Crucial Technology   | 1         | 1      | 0.42%   |
| LITEON                      | 1         | 1      | 0.42%   |
| Lite-On                     | 1         | 1      | 0.42%   |
| HS-SSD-E100N                | 1         | 1      | 0.42%   |
| Hjwdz                       | 1         | 1      | 0.42%   |
| Golden                      | 1         | 1      | 0.42%   |
| Gigabyte Technology         | 1         | 1      | 0.42%   |
| Unknown                     | 1         | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                            | 7         | 2.87%   |
| Seagate ST1000LM035-1RK172 1TB                    | 7         | 2.87%   |
| Toshiba MQ01ABF050 500GB                          | 6         | 2.46%   |
| Kingston SA400S37240G 240GB SSD                   | 5         | 2.05%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 4         | 1.64%   |
| WDC WD10SPZX-24Z10 1TB                            | 4         | 1.64%   |
| Unknown MMC Card  16GB                            | 4         | 1.64%   |
| Seagate ST2000LM007-1R8174 2TB                    | 4         | 1.64%   |
| Kingston SA400S37480G 480GB SSD                   | 3         | 1.23%   |
| HP SSD S700 500GB                                 | 3         | 1.23%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 2         | 0.82%   |
| WDC WD1600BEVT-22ZCT0 160GB                       | 2         | 0.82%   |
| WDC WD10SPZX-24Z10T0 1TB                          | 2         | 0.82%   |
| WDC WD10SPZX-22Z10T1 1TB                          | 2         | 0.82%   |
| WDC WD10JPVX-75JC3T0 1TB                          | 2         | 0.82%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 2         | 0.82%   |
| Unknown MMC Card  32GB                            | 2         | 0.82%   |
| Toshiba MQ01ABD100M 1TB                           | 2         | 0.82%   |
| Toshiba MQ01ABD100 1TB                            | 2         | 0.82%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD           | 2         | 0.82%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB            | 2         | 0.82%   |
| Seagate ST9500325AS 500GB                         | 2         | 0.82%   |
| Seagate ST500LT012-9WS142 500GB                   | 2         | 0.82%   |
| Seagate ST500LT012-1DG142 500GB                   | 2         | 0.82%   |
| Samsung SSD 860 EVO 1TB                           | 2         | 0.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 0.82%   |
| Micron NVMe SSD Drive 512GB                       | 2         | 0.82%   |
| Hitachi HTS543232A7A384 320GB                     | 2         | 0.82%   |
| Hitachi HTS541616J9SA00 160GB                     | 2         | 0.82%   |
| HGST HTS545050A7E380 500GB                        | 2         | 0.82%   |
| HGST HTS541010A9E680 1TB                          | 2         | 0.82%   |
| A-DATA SU650 120GB SSD                            | 2         | 0.82%   |
| A-DATA SU630 960GB SSD                            | 2         | 0.82%   |
| A-DATA ED600 1TB SSD                              | 2         | 0.82%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                  | 1         | 0.41%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1         | 0.41%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                  | 1         | 0.41%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 1         | 0.41%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                    | 1         | 0.41%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                    | 1         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 33        | 35     | 29.46%  |
| WDC                 | 29        | 37     | 25.89%  |
| Seagate             | 29        | 45     | 25.89%  |
| Hitachi             | 10        | 13     | 8.93%   |
| HGST                | 6         | 8      | 5.36%   |
| Fujitsu             | 2         | 2      | 1.79%   |
| Unknown             | 1         | 3      | 0.89%   |
| Samsung Electronics | 1         | 1      | 0.89%   |
| JMicron Technology  | 1         | 1      | 0.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 11        | 12     | 17.74%  |
| Kingston            | 11        | 11     | 17.74%  |
| A-DATA Technology   | 7         | 10     | 11.29%  |
| SanDisk             | 5         | 5      | 8.06%   |
| Hewlett-Packard     | 5         | 5      | 8.06%   |
| Samsung Electronics | 3         | 3      | 4.84%   |
| Apple               | 3         | 4      | 4.84%   |
| Toshiba             | 2         | 3      | 3.23%   |
| SK hynix            | 2         | 2      | 3.23%   |
| Crucial             | 2         | 2      | 3.23%   |
| USB3.0              | 1         | 1      | 1.61%   |
| SABRENT             | 1         | 1      | 1.61%   |
| PNY                 | 1         | 1      | 1.61%   |
| Patriot             | 1         | 1      | 1.61%   |
| OWC                 | 1         | 1      | 1.61%   |
| Netac               | 1         | 1      | 1.61%   |
| Micron Technology   | 1         | 1      | 1.61%   |
| LITEON              | 1         | 1      | 1.61%   |
| HS-SSD-E100N        | 1         | 1      | 1.61%   |
| Golden              | 1         | 1      | 1.61%   |
| Gigabyte Technology | 1         | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 108       | 145    | 48.21%  |
| SSD     | 55        | 68     | 24.55%  |
| NVMe    | 51        | 62     | 22.77%  |
| MMC     | 8         | 11     | 3.57%   |
| Unknown | 2         | 2      | 0.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 150       | 199    | 68.81%  |
| NVMe | 51        | 62     | 23.39%  |
| SAS  | 9         | 16     | 4.13%   |
| MMC  | 8         | 11     | 3.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 102       | 123    | 61.45%  |
| 0.51-1.0   | 57        | 83     | 34.34%  |
| 1.01-2.0   | 7         | 7      | 4.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 50        | 25.38%  |
| 251-500        | 48        | 24.37%  |
| 501-1000       | 29        | 14.72%  |
| 1001-2000      | 24        | 12.18%  |
| 1-20           | 14        | 7.11%   |
| 21-50          | 12        | 6.09%   |
| 51-100         | 12        | 6.09%   |
| Unknown        | 6         | 3.05%   |
| More than 3000 | 2         | 1.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 74        | 36.45%  |
| 21-50     | 39        | 19.21%  |
| 101-250   | 36        | 17.73%  |
| 251-500   | 18        | 8.87%   |
| 51-100    | 17        | 8.37%   |
| 501-1000  | 9         | 4.43%   |
| Unknown   | 6         | 2.96%   |
| 1001-2000 | 3         | 1.48%   |
| 2001-3000 | 1         | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC WD5000LPVT-00G33T0 500GB   | 1         | 1      | 7.14%   |
| WDC WD5000LPCX-24VHAT0 500GB   | 1         | 1      | 7.14%   |
| Toshiba MQ01ABF050 500GB       | 1         | 2      | 7.14%   |
| Toshiba MQ01ABD100M 1TB        | 1         | 1      | 7.14%   |
| Toshiba MQ01ABD100 1TB         | 1         | 1      | 7.14%   |
| Toshiba MK3265GSXN 320GB       | 1         | 1      | 7.14%   |
| Toshiba MK3259GSXP 320GB       | 1         | 1      | 7.14%   |
| Toshiba MK2561GSYN 250GB       | 1         | 2      | 7.14%   |
| Seagate ST1000LX015-1U7172 1TB | 1         | 3      | 7.14%   |
| Seagate ST1000LM035-1RK172 1TB | 1         | 1      | 7.14%   |
| Hitachi HTS547550A9E384 500GB  | 1         | 1      | 7.14%   |
| Hitachi HTS543232L9SA00 320GB  | 1         | 1      | 7.14%   |
| HGST HTS545050A7E380 500GB     | 1         | 1      | 7.14%   |
| Fujitsu MHY2250BH 250GB        | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 6         | 8      | 42.86%  |
| WDC     | 2         | 2      | 14.29%  |
| Seagate | 2         | 4      | 14.29%  |
| Hitachi | 2         | 2      | 14.29%  |
| HGST    | 1         | 1      | 7.14%   |
| Fujitsu | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 6         | 8      | 42.86%  |
| WDC     | 2         | 2      | 14.29%  |
| Seagate | 2         | 4      | 14.29%  |
| Hitachi | 2         | 2      | 14.29%  |
| HGST    | 1         | 1      | 7.14%   |
| Fujitsu | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 18     | 100%    |

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
| Detected | 116       | 179    | 58.29%  |
| Works    | 69        | 91     | 34.67%  |
| Malfunc  | 14        | 18     | 7.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 129       | 58.64%  |
| AMD                          | 36        | 16.36%  |
| Samsung Electronics          | 13        | 5.91%   |
| SK hynix                     | 9         | 4.09%   |
| SanDisk                      | 9         | 4.09%   |
| Kingston Technology Company  | 5         | 2.27%   |
| Micron Technology            | 4         | 1.82%   |
| KIOXIA                       | 3         | 1.36%   |
| Toshiba America Info Systems | 2         | 0.91%   |
| Phison Electronics           | 2         | 0.91%   |
| Union Memory (Shenzhen)      | 1         | 0.45%   |
| Silicon Motion               | 1         | 0.45%   |
| Realtek Semiconductor        | 1         | 0.45%   |
| Nvidia                       | 1         | 0.45%   |
| Micron/Crucial Technology    | 1         | 0.45%   |
| Lite-On Technology           | 1         | 0.45%   |
| Apple                        | 1         | 0.45%   |
| ADATA Technology             | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 34        | 14.53%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 18        | 7.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 17        | 7.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 15        | 6.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 9         | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 3.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 2.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 2.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 2.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 2.14%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 4         | 1.71%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 4         | 1.71%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 1.71%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.71%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 3         | 1.28%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 1.28%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.28%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 1.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.28%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 1.28%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.85%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 2         | 0.85%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 2         | 0.85%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 0.85%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                               | 2         | 0.85%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation            | 2         | 0.85%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.85%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 0.85%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                  | 1         | 0.43%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.43%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 1         | 0.43%   |
| SK hynix PC601 NVMe Solid State Drive                                            | 1         | 0.43%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 137       | 60.09%  |
| NVMe | 51        | 22.37%  |
| RAID | 24        | 10.53%  |
| IDE  | 16        | 7.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 144       | 76.19%  |
| AMD    | 45        | 23.81%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 4.76%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 3.17%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.65%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 4         | 2.12%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.12%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.59%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 3         | 1.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.59%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.59%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 1.59%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 1.59%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 3         | 1.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.06%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.06%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.06%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.06%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.06%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.06%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.06%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.06%   |
| Intel Core i5-5257U CPU @ 2.70GHz             | 2         | 1.06%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.06%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.06%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.06%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 1.06%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.06%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.06%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 2         | 1.06%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz          | 2         | 1.06%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 2         | 1.06%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.06%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.06%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 2         | 1.06%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.06%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.06%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 2         | 1.06%   |
| AMD E2-9000e RADEON R2, 4 COMPUTE CORES 2C+2G | 2         | 1.06%   |
| AMD E-300 APU with Radeon HD Graphics         | 2         | 1.06%   |
| AMD Custom APU 0405                           | 2         | 1.06%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 45        | 23.81%  |
| Intel Core i5           | 30        | 15.87%  |
| Intel Core i3           | 19        | 10.05%  |
| Intel Celeron           | 16        | 8.47%   |
| Other                   | 15        | 7.94%   |
| Intel Core 2 Duo        | 11        | 5.82%   |
| AMD Ryzen 5             | 11        | 5.82%   |
| AMD Ryzen 7             | 6         | 3.17%   |
| Intel Atom              | 3         | 1.59%   |
| AMD Ryzen 3             | 3         | 1.59%   |
| AMD E2                  | 3         | 1.59%   |
| AMD A6                  | 3         | 1.59%   |
| Intel Pentium Dual-Core | 2         | 1.06%   |
| Intel Pentium           | 2         | 1.06%   |
| Intel Genuine           | 2         | 1.06%   |
| AMD E1                  | 2         | 1.06%   |
| AMD E                   | 2         | 1.06%   |
| AMD A8                  | 2         | 1.06%   |
| AMD A4                  | 2         | 1.06%   |
| AMD A12                 | 2         | 1.06%   |
| Intel Pentium M         | 1         | 0.53%   |
| Intel Core m3           | 1         | 0.53%   |
| Intel Celeron M         | 1         | 0.53%   |
| AMD Ryzen 7 PRO         | 1         | 0.53%   |
| AMD FX                  | 1         | 0.53%   |
| AMD C-70                | 1         | 0.53%   |
| AMD C-60                | 1         | 0.53%   |
| AMD A10                 | 1         | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 106       | 56.08%  |
| 4      | 54        | 28.57%  |
| 6      | 11        | 5.82%   |
| 1      | 8         | 4.23%   |
| 8      | 7         | 3.7%    |
| 14     | 2         | 1.06%   |
| 12     | 1         | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 189       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 133       | 70.37%  |
| 1      | 56        | 29.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 185       | 97.88%  |
| 32-bit         | 3         | 1.59%   |
| Unknown        | 1         | 0.53%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 46        | 23.59%  |
| 0x806ea    | 12        | 6.15%   |
| 0x306a9    | 11        | 5.64%   |
| 0x206a7    | 11        | 5.64%   |
| 0x306d4    | 9         | 4.62%   |
| 0x6fd      | 7         | 3.59%   |
| 0x40651    | 7         | 3.59%   |
| 0x08108109 | 7         | 3.59%   |
| 0x06006705 | 5         | 2.56%   |
| 0x806c1    | 4         | 2.05%   |
| 0x706e5    | 4         | 2.05%   |
| 0x306c3    | 4         | 2.05%   |
| 0x1067a    | 4         | 2.05%   |
| 0x05000119 | 4         | 2.05%   |
| 0x906ea    | 3         | 1.54%   |
| 0x806eb    | 3         | 1.54%   |
| 0x806e9    | 3         | 1.54%   |
| 0x06006704 | 3         | 1.54%   |
| 0x0600611a | 3         | 1.54%   |
| 0x906ed    | 2         | 1.03%   |
| 0x806ec    | 2         | 1.03%   |
| 0x706a1    | 2         | 1.03%   |
| 0x6e8      | 2         | 1.03%   |
| 0x406e3    | 2         | 1.03%   |
| 0x406c4    | 2         | 1.03%   |
| 0x30678    | 2         | 1.03%   |
| 0x20655    | 2         | 1.03%   |
| 0x106ca    | 2         | 1.03%   |
| 0x08600104 | 2         | 1.03%   |
| 0x0810100b | 2         | 1.03%   |
| 0xa0660    | 1         | 0.51%   |
| 0xa0652    | 1         | 0.51%   |
| 0x906a3    | 1         | 0.51%   |
| 0x706a8    | 1         | 0.51%   |
| 0x6fa      | 1         | 0.51%   |
| 0x6d8      | 1         | 0.51%   |
| 0x506e3    | 1         | 0.51%   |
| 0x506c9    | 1         | 0.51%   |
| 0x406c3    | 1         | 0.51%   |
| 0x30673    | 1         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 37        | 19.58%  |
| IvyBridge        | 14        | 7.41%   |
| Haswell          | 14        | 7.41%   |
| SandyBridge      | 12        | 6.35%   |
| Excavator        | 12        | 6.35%   |
| Core             | 11        | 5.82%   |
| Zen+             | 9         | 4.76%   |
| Broadwell        | 9         | 4.76%   |
| TigerLake        | 7         | 3.7%    |
| Unknown          | 7         | 3.7%    |
| Silvermont       | 6         | 3.17%   |
| Penryn           | 5         | 2.65%   |
| IceLake          | 5         | 2.65%   |
| Bobcat           | 5         | 2.65%   |
| Zen 2            | 4         | 2.12%   |
| Zen              | 4         | 2.12%   |
| Skylake          | 4         | 2.12%   |
| Westmere         | 3         | 1.59%   |
| P6               | 3         | 1.59%   |
| Goldmont plus    | 3         | 1.59%   |
| CometLake        | 3         | 1.59%   |
| Bonnell          | 3         | 1.59%   |
| Alderlake Hybrid | 3         | 1.59%   |
| Puma             | 2         | 1.06%   |
| Zen 3            | 1         | 0.53%   |
| K10 Llano        | 1         | 0.53%   |
| Jaguar           | 1         | 0.53%   |
| Goldmont         | 1         | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 136       | 60.71%  |
| AMD    | 56        | 25%     |
| Nvidia | 32        | 14.29%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 16        | 6.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 5.93%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 5.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 4.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 4.24%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 3.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 3.39%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 3.39%   |
| Intel HD Graphics 5500                                                                   | 7         | 2.97%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 2.97%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 2.54%   |
| Intel HD Graphics 620                                                                    | 6         | 2.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.12%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 2.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.69%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 1.69%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 4         | 1.69%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.27%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.27%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.27%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.27%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 1.27%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.27%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.27%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.27%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.27%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.27%   |
| AMD Lucienne                                                                             | 3         | 1.27%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.85%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.85%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.85%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 2         | 0.85%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.85%   |
| Intel Iris Graphics 6100                                                                 | 2         | 0.85%   |
| Intel HD Graphics 630                                                                    | 2         | 0.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.85%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.85%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 0.85%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 103       | 54.5%   |
| 1 x AMD        | 42        | 22.22%  |
| Intel + Nvidia | 21        | 11.11%  |
| Intel + AMD    | 9         | 4.76%   |
| 1 x Nvidia     | 7         | 3.7%    |
| AMD + Nvidia   | 4         | 2.12%   |
| 2 x Intel      | 2         | 1.06%   |
| 2 x AMD        | 1         | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 168       | 88.42%  |
| Proprietary | 17        | 8.95%   |
| Unknown     | 5         | 2.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 118       | 61.46%  |
| 0.01-0.5   | 28        | 14.58%  |
| 1.01-2.0   | 21        | 10.94%  |
| 3.01-4.0   | 13        | 6.77%   |
| 0.51-1.0   | 7         | 3.65%   |
| 7.01-8.0   | 2         | 1.04%   |
| 5.01-6.0   | 2         | 1.04%   |
| 2.01-3.0   | 1         | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 37        | 16.97%  |
| Chimei Innolux          | 34        | 15.6%   |
| AU Optronics            | 34        | 15.6%   |
| LG Display              | 27        | 12.39%  |
| Samsung Electronics     | 17        | 7.8%    |
| Goldstar                | 15        | 6.88%   |
| Apple                   | 8         | 3.67%   |
| Chi Mei Optoelectronics | 7         | 3.21%   |
| PANDA                   | 4         | 1.83%   |
| AOC                     | 4         | 1.83%   |
| LG Philips              | 3         | 1.38%   |
| Valve                   | 2         | 0.92%   |
| Sony                    | 2         | 0.92%   |
| Sharp                   | 2         | 0.92%   |
| InnoLux Display         | 2         | 0.92%   |
| InfoVision              | 2         | 0.92%   |
| ASUSTek Computer        | 2         | 0.92%   |
| Acer                    | 2         | 0.92%   |
| ViewSonic               | 1         | 0.46%   |
| Unknown (XXX)           | 1         | 0.46%   |
| Toshiba                 | 1         | 0.46%   |
| TCL                     | 1         | 0.46%   |
| SKY                     | 1         | 0.46%   |
| MSI                     | 1         | 0.46%   |
| Lenovo                  | 1         | 0.46%   |
| Huion                   | 1         | 0.46%   |
| Hewlett-Packard         | 1         | 0.46%   |
| Gigabyte Technology     | 1         | 0.46%   |
| Dell                    | 1         | 0.46%   |
| CSO                     | 1         | 0.46%   |
| CPT                     | 1         | 0.46%   |
| BenQ                    | 1         | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                      | 5         | 2.28%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 4         | 1.83%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 4         | 1.83%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch       | 3         | 1.37%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 3         | 1.37%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.37%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                        | 3         | 1.37%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 2         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 2         | 0.91%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 2         | 0.91%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 0.91%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 2         | 0.91%   |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                   | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch       | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 2         | 0.91%   |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                 | 2         | 0.91%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.91%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                  | 2         | 0.91%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                 | 2         | 0.91%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 0.91%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO325C 1366x768 256x144mm 11.6-inch         | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 0.91%   |
| Apple Color LCD APPA029 2560x1600 286x179mm 13.3-inch                 | 2         | 0.91%   |
| ViewSonic VA2855 SERIES VSCD62F 1920x1080 621x341mm 27.9-inch         | 1         | 0.46%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1         | 0.46%   |
| Toshiba LCD Monitor LCD3706 1280x800 261x163mm 12.1-inch              | 1         | 0.46%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                   | 1         | 0.46%   |
| Sony TV SNYAB03 1920x1080                                             | 1         | 0.46%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.46%   |
| SKY TV-monitor SKY1202 1920x1080 885x498mm 40.0-inch                  | 1         | 0.46%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.46%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 0.46%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5557 1920x1200 367x230mm 17.1-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch  | 1         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 98        | 47.57%  |
| 1920x1080 (FHD)   | 60        | 29.13%  |
| 1600x900 (HD+)    | 12        | 5.83%   |
| 1280x800 (WXGA)   | 12        | 5.83%   |
| 2560x1600         | 6         | 2.91%   |
| 3840x2160 (4K)    | 4         | 1.94%   |
| 1024x600          | 3         | 1.46%   |
| 800x1280          | 2         | 0.97%   |
| 2560x1440 (QHD)   | 2         | 0.97%   |
| 1920x1200 (WUXGA) | 2         | 0.97%   |
| 1440x900 (WXGA+)  | 2         | 0.97%   |
| 3440x1440         | 1         | 0.49%   |
| 2880x1800         | 1         | 0.49%   |
| 1024x768 (XGA)    | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 87        | 39.73%  |
| 13     | 38        | 17.35%  |
| 14     | 27        | 12.33%  |
| 19     | 9         | 4.11%   |
| 11     | 9         | 4.11%   |
| 18     | 8         | 3.65%   |
| 21     | 7         | 3.2%    |
| 17     | 6         | 2.74%   |
| 12     | 6         | 2.74%   |
| 31     | 3         | 1.37%   |
| 23     | 3         | 1.37%   |
| 16     | 3         | 1.37%   |
| 10     | 3         | 1.37%   |
| 54     | 2         | 0.91%   |
| 27     | 2         | 0.91%   |
| 7      | 2         | 0.91%   |
| 72     | 1         | 0.46%   |
| 40     | 1         | 0.46%   |
| 34     | 1         | 0.46%   |
| 24     | 1         | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 141       | 64.98%  |
| 201-300     | 31        | 14.29%  |
| 401-500     | 22        | 10.14%  |
| 351-400     | 7         | 3.23%   |
| 501-600     | 5         | 2.3%    |
| 601-700     | 4         | 1.84%   |
| 1001-1500   | 2         | 0.92%   |
| 1-100       | 2         | 0.92%   |
| 801-900     | 1         | 0.46%   |
| 701-800     | 1         | 0.46%   |
| 1501-2000   | 1         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 159       | 85.03%  |
| 16/10 | 23        | 12.3%   |
| 0.67  | 2         | 1.07%   |
| 4/3   | 1         | 0.53%   |
| 3/2   | 1         | 0.53%   |
| 21/9  | 1         | 0.53%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 86        | 39.27%  |
| 81-90          | 56        | 25.57%  |
| 151-200        | 11        | 5.02%   |
| 71-80          | 9         | 4.11%   |
| 51-60          | 9         | 4.11%   |
| 201-250        | 9         | 4.11%   |
| 141-150        | 8         | 3.65%   |
| 61-70          | 6         | 2.74%   |
| 121-130        | 5         | 2.28%   |
| 351-500        | 4         | 1.83%   |
| More than 1000 | 3         | 1.37%   |
| 41-50          | 3         | 1.37%   |
| 111-120        | 3         | 1.37%   |
| 1-40           | 2         | 0.91%   |
| 301-350        | 2         | 0.91%   |
| 131-140        | 1         | 0.46%   |
| 501-1000       | 1         | 0.46%   |
| 91-100         | 1         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 98        | 46.01%  |
| 121-160       | 68        | 31.92%  |
| 51-100        | 29        | 13.62%  |
| 161-240       | 13        | 6.1%    |
| 1-50          | 4         | 1.88%   |
| More than 240 | 1         | 0.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 153       | 79.69%  |
| 2     | 34        | 17.71%  |
| 0     | 4         | 2.08%   |
| 3     | 1         | 0.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 118       | 39.2%   |
| Intel                           | 63        | 20.93%  |
| Qualcomm Atheros                | 58        | 19.27%  |
| Broadcom                        | 27        | 8.97%   |
| Ralink                          | 5         | 1.66%   |
| MediaTek                        | 5         | 1.66%   |
| Marvell Technology Group        | 5         | 1.66%   |
| Broadcom Limited                | 4         | 1.33%   |
| TP-Link                         | 3         | 1%      |
| ASIX Electronics                | 3         | 1%      |
| Xiaomi                          | 2         | 0.66%   |
| Samsung Electronics             | 2         | 0.66%   |
| Ralink Technology               | 1         | 0.33%   |
| Qualcomm Atheros Communications | 1         | 0.33%   |
| OPPO Electronics                | 1         | 0.33%   |
| Nvidia                          | 1         | 0.33%   |
| NetGear                         | 1         | 0.33%   |
| Hewlett-Packard                 | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 62        | 17.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 35        | 9.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 4.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 3.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 3.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 2.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 2.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.95%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 1.95%   |
| Intel Wireless 8265 / 8275                                              | 6         | 1.67%   |
| Intel Wireless 3160                                                     | 6         | 1.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.67%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 1.11%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 4         | 1.11%   |
| Intel Wireless 7260                                                     | 4         | 1.11%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.84%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 0.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.84%   |
| Intel Wireless 7265                                                     | 3         | 0.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 0.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 0.84%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 3         | 0.84%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 3         | 0.84%   |
| ASIX AX88179 Gigabit Ethernet                                           | 3         | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 2         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 2         | 0.56%   |
| Intel Wireless 8260                                                     | 2         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 62        | 31.63%  |
| Qualcomm Atheros                | 51        | 26.02%  |
| Realtek Semiconductor           | 44        | 22.45%  |
| Broadcom                        | 22        | 11.22%  |
| Ralink                          | 5         | 2.55%   |
| MediaTek                        | 5         | 2.55%   |
| TP-Link                         | 2         | 1.02%   |
| Broadcom Limited                | 2         | 1.02%   |
| Ralink Technology               | 1         | 0.51%   |
| Qualcomm Atheros Communications | 1         | 0.51%   |
| NetGear                         | 1         | 0.51%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 7.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 7.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 5.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 4.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 4.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.54%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 3.54%   |
| Intel Wireless 8265 / 8275                                              | 6         | 3.03%   |
| Intel Wireless 3160                                                     | 6         | 3.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 3.03%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2.53%   |
| Intel Wireless 7260                                                     | 4         | 2.02%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 2.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.52%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 1.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.52%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.52%   |
| Intel Wireless 7265                                                     | 3         | 1.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.52%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 3         | 1.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.01%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.01%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.01%   |
| Intel Wireless 8260                                                     | 2         | 1.01%   |
| Intel WiFi Link 5100                                                    | 2         | 1.01%   |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.01%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 2         | 1.01%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.01%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 1.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.01%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 1.01%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 1.01%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 1         | 0.51%   |
| TP-Link 802.11ac WLAN Adapter                                           | 1         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 105       | 67.31%  |
| Qualcomm Atheros         | 13        | 8.33%   |
| Intel                    | 11        | 7.05%   |
| Broadcom                 | 11        | 7.05%   |
| Marvell Technology Group | 5         | 3.21%   |
| ASIX Electronics         | 3         | 1.92%   |
| Xiaomi                   | 2         | 1.28%   |
| Broadcom Limited         | 2         | 1.28%   |
| TP-Link                  | 1         | 0.64%   |
| Samsung Electronics      | 1         | 0.64%   |
| OPPO Electronics         | 1         | 0.64%   |
| Nvidia                   | 1         | 0.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 62        | 39.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 35        | 22.15%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 2.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 2.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 1.9%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 3         | 1.9%    |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 1.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 1.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 1.27%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 1.27%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 1.27%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.27%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 1.27%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.63%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.63%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.63%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 1         | 0.63%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.63%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 0.63%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 0.63%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                  | 1         | 0.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.63%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 1         | 0.63%   |
| Intel WiMAX Connection 2400m                                           | 1         | 0.63%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.63%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 0.63%   |
| Intel Ethernet Connection (17) I219-V                                  | 1         | 0.63%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 0.63%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 0.63%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 0.63%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 0.63%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 0.63%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 0.63%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 1         | 0.63%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 188       | 54.81%  |
| Ethernet | 152       | 44.31%  |
| Modem    | 3         | 0.87%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 146       | 73%     |
| Ethernet | 54        | 27%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 140       | 74.07%  |
| 1     | 48        | 25.4%   |
| 0     | 1         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 156       | 81.68%  |
| Yes  | 35        | 18.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 45        | 30.2%   |
| Realtek Semiconductor           | 25        | 16.78%  |
| Qualcomm Atheros Communications | 25        | 16.78%  |
| Lite-On Technology              | 9         | 6.04%   |
| IMC Networks                    | 8         | 5.37%   |
| Foxconn / Hon Hai               | 8         | 5.37%   |
| Broadcom                        | 8         | 5.37%   |
| Apple                           | 6         | 4.03%   |
| Toshiba                         | 3         | 2.01%   |
| Cambridge Silicon Radio         | 3         | 2.01%   |
| Ralink Technology               | 2         | 1.34%   |
| Ralink                          | 2         | 1.34%   |
| Realtek                         | 1         | 0.67%   |
| Hewlett-Packard                 | 1         | 0.67%   |
| Foxconn International           | 1         | 0.67%   |
| Dell                            | 1         | 0.67%   |
| Alps Electric                   | 1         | 0.67%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 23        | 15.44%  |
| Qualcomm Atheros  Bluetooth Device                  | 17        | 11.41%  |
| Realtek  Bluetooth 4.2 Adapter                      | 13        | 8.72%   |
| Realtek Bluetooth Radio                             | 12        | 8.05%   |
| Intel AX201 Bluetooth                               | 8         | 5.37%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 4.03%   |
| IMC Networks Bluetooth Radio                        | 6         | 4.03%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 2.68%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 2.68%   |
| Toshiba Bluetooth Device                            | 3         | 2.01%   |
| Lite-On Wireless_Device                             | 3         | 2.01%   |
| Lite-On Bluetooth Device                            | 3         | 2.01%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 2.01%   |
| Apple Bluetooth Host Controller                     | 3         | 2.01%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.34%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.34%   |
| Lite-On Bluetooth Radio                             | 2         | 1.34%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.34%   |
| Intel Bluetooth Device                              | 2         | 1.34%   |
| Intel AX200 Bluetooth                               | 2         | 1.34%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 1.34%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.34%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.34%   |
| Realtek Bluetooth Radio                             | 1         | 0.67%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.67%   |
| Ralink CSR BS8510                                   | 1         | 0.67%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.67%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.67%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.67%   |
| IMC Networks Wireless_Device                        | 1         | 0.67%   |
| IMC Networks BCM20702A0                             | 1         | 0.67%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.67%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.67%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.67%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.67%   |
| Broadcom HP Portable Valentine                      | 1         | 0.67%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.67%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 143       | 67.45%  |
| AMD                 | 46        | 21.7%   |
| Nvidia              | 17        | 8.02%   |
| Sony                | 1         | 0.47%   |
| GN Netcom           | 1         | 0.47%   |
| Focusrite-Novation  | 1         | 0.47%   |
| C-Media Electronics | 1         | 0.47%   |
| Audient             | 1         | 0.47%   |
| Apple               | 1         | 0.47%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 25        | 9.06%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 22        | 7.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 6.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 13        | 4.71%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 3.62%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 3.62%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 10        | 3.62%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 3.26%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 3.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 3.26%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 2.9%    |
| AMD High Definition Audio Controller                                                              | 8         | 2.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 2.54%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 2.54%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 2.54%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 2.54%   |
| AMD FCH Azalia Controller                                                                         | 7         | 2.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.81%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 1.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.45%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.45%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.09%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.09%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.09%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 3         | 1.09%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.72%   |
| Intel USB PnP Sound Device                                                                        | 2         | 0.72%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 0.72%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.72%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.72%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.36%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 43        | 30.94%  |
| SK hynix            | 32        | 23.02%  |
| Micron Technology   | 16        | 11.51%  |
| Kingston            | 13        | 9.35%   |
| Unknown             | 6         | 4.32%   |
| Ramaxel Technology  | 6         | 4.32%   |
| A-DATA Technology   | 6         | 4.32%   |
| Crucial             | 4         | 2.88%   |
| Nanya Technology    | 3         | 2.16%   |
| Unknown (ABCD)      | 2         | 1.44%   |
| Avant               | 2         | 1.44%   |
| Team                | 1         | 0.72%   |
| Hikvision           | 1         | 0.72%   |
| GOODRAM             | 1         | 0.72%   |
| Elpida              | 1         | 0.72%   |
| Corsair             | 1         | 0.72%   |
| Unknown             | 1         | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 6         | 4.08%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 2.72%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 2.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 3         | 2.04%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 2.04%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 3         | 2.04%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 1.36%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.36%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 1.36%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 1.36%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 2         | 1.36%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 2         | 1.36%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 2         | 1.36%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.36%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s             | 2         | 1.36%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s           | 2         | 1.36%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s                | 2         | 1.36%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s             | 2         | 1.36%   |
| Kingston RAM 99U5428-018.A00LF 8192MB SODIMM DDR3 1600MT/s          | 2         | 1.36%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                         | 1         | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                          | 1         | 0.68%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                            | 1         | 0.68%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                          | 1         | 0.68%   |
| Unknown RAM Module 1GB SODIMM DDR                                   | 1         | 0.68%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 0.68%   |
| Unknown RAM Module 1024MB SODIMM DDR2                               | 1         | 0.68%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                            | 1         | 0.68%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 8400MT/s                | 1         | 0.68%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.68%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.68%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.68%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.68%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.68%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.68%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.68%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 0.68%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.68%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s              | 1         | 0.68%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.68%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 60        | 55.56%  |
| DDR3    | 30        | 27.78%  |
| LPDDR4  | 6         | 5.56%   |
| DDR2    | 4         | 3.7%    |
| LPDDR3  | 3         | 2.78%   |
| SDRAM   | 2         | 1.85%   |
| DDR5    | 1         | 0.93%   |
| DDR     | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 98        | 90.74%  |
| Row Of Chips | 9         | 8.33%   |
| Unknown      | 1         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 45        | 36.59%  |
| 4096  | 45        | 36.59%  |
| 16384 | 17        | 13.82%  |
| 2048  | 9         | 7.32%   |
| 1024  | 5         | 4.07%   |
| 32768 | 2         | 1.63%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 38        | 30.65%  |
| 1600    | 27        | 21.77%  |
| 3200    | 16        | 12.9%   |
| 2400    | 9         | 7.26%   |
| 3266    | 6         | 4.84%   |
| 1334    | 5         | 4.03%   |
| 2133    | 3         | 2.42%   |
| 4199    | 2         | 1.61%   |
| 1867    | 2         | 1.61%   |
| 667     | 2         | 1.61%   |
| Unknown | 2         | 1.61%   |
| 8400    | 1         | 0.81%   |
| 5600    | 1         | 0.81%   |
| 4267    | 1         | 0.81%   |
| 3733    | 1         | 0.81%   |
| 1776    | 1         | 0.81%   |
| 1333    | 1         | 0.81%   |
| 1067    | 1         | 0.81%   |
| 1066    | 1         | 0.81%   |
| 975     | 1         | 0.81%   |
| 933     | 1         | 0.81%   |
| 800     | 1         | 0.81%   |
| 533     | 1         | 0.81%   |

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
| Chicony Electronics                    | 44        | 26.35%  |
| IMC Networks                           | 22        | 13.17%  |
| Realtek Semiconductor                  | 12        | 7.19%   |
| Quanta                                 | 12        | 7.19%   |
| Microdia                               | 12        | 7.19%   |
| Suyin                                  | 8         | 4.79%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 4.79%   |
| Syntek                                 | 7         | 4.19%   |
| Sunplus Innovation Technology          | 6         | 3.59%   |
| Lite-On Technology                     | 5         | 2.99%   |
| Apple                                  | 4         | 2.4%    |
| Silicon Motion                         | 3         | 1.8%    |
| Ricoh                                  | 3         | 1.8%    |
| Acer                                   | 3         | 1.8%    |
| OmniVision Technologies                | 2         | 1.2%    |
| Luxvisions Innotech Limited            | 2         | 1.2%    |
| Bison Electronics                      | 2         | 1.2%    |
| Alcor Micro                            | 2         | 1.2%    |
| Z-Star Microelectronics                | 1         | 0.6%    |
| USB Camera                             | 1         | 0.6%    |
| Trust                                  | 1         | 0.6%    |
| Sonix Technology                       | 1         | 0.6%    |
| Samsung Electronics                    | 1         | 0.6%    |
| Lenovo                                 | 1         | 0.6%    |
| Importek                               | 1         | 0.6%    |
| Generalplus Technology                 | 1         | 0.6%    |
| Foxconn / Hon Hai                      | 1         | 0.6%    |
| ALi                                    | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 8         | 4.79%   |
| Chicony Integrated Camera                                      | 7         | 4.19%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 6         | 3.59%   |
| Chicony HP Truevision HD                                       | 6         | 3.59%   |
| IMC Networks Integrated Camera                                 | 5         | 2.99%   |
| Realtek Integrated_Webcam_HD                                   | 4         | 2.4%    |
| IMC Networks VGA UVC WebCam                                    | 3         | 1.8%    |
| IMC Networks TOSHIBA Web Camera - HD                           | 3         | 1.8%    |
| Chicony TOSHIBA Web Camera - HD                                | 3         | 1.8%    |
| Chicony HD User Facing                                         | 3         | 1.8%    |
| Syntek Lenovo EasyCamera                                       | 2         | 1.2%    |
| Syntek Integrated Camera                                       | 2         | 1.2%    |
| Syntek EasyCamera                                              | 2         | 1.2%    |
| Suyin Integrated_Webcam_HD                                     | 2         | 1.2%    |
| Suyin HP Truevision HD                                         | 2         | 1.2%    |
| Suyin HD WebCam                                                | 2         | 1.2%    |
| Sunplus Integrated_Webcam_HD                                   | 2         | 1.2%    |
| Realtek Integrated Webcam                                      | 2         | 1.2%    |
| Realtek HP "Truevision HD" laptop camera                       | 2         | 1.2%    |
| Quanta HP Wide Vision HD Camera                                | 2         | 1.2%    |
| Quanta HP Webcam-50                                            | 2         | 1.2%    |
| Quanta HP Webcam                                               | 2         | 1.2%    |
| OmniVision OV2640 Webcam                                       | 2         | 1.2%    |
| Microdia USB 2.0 Camera                                        | 2         | 1.2%    |
| Lite-On TOSHIBA Web Camera - HD                                | 2         | 1.2%    |
| Lite-On HP TrueVision HD Camera                                | 2         | 1.2%    |
| Chicony Integrated Camera (1280x720@30)                        | 2         | 1.2%    |
| Chicony HP Wide Vision HD Camera                               | 2         | 1.2%    |
| Chicony HP TrueVision HD Camera                                | 2         | 1.2%    |
| Chicony HP HD Webcam [Fixed]                                   | 2         | 1.2%    |
| Chicony EasyCamera                                             | 2         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD        | 2         | 1.2%    |
| Alcor Micro USB 2.0 Camera                                     | 2         | 1.2%    |
| Acer Integrated Camera                                         | 2         | 1.2%    |
| Z-Star WebCam SCB-0320N                                        | 1         | 0.6%    |
| USB Camera USB Camera                                          | 1         | 0.6%    |
| Trust USB Camera                                               | 1         | 0.6%    |
| Syntek USB Video Device                                        | 1         | 0.6%    |
| Suyin HP TrueVision HD Integrated Webcam                       | 1         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 18.75%  |
| Synaptics                  | 3         | 18.75%  |
| AuthenTec                  | 3         | 18.75%  |
| Upek                       | 2         | 12.5%   |
| Shenzhen Goodix Technology | 2         | 12.5%   |
| STMicroelectronics         | 1         | 6.25%   |
| LighTuning Technology      | 1         | 6.25%   |
| Elan Microelectronics      | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors Swipe Fingerprint Sensor              | 2         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 12.5%   |
| Shenzhen Goodix  FingerPrint Device                    | 2         | 12.5%   |
| AuthenTec AES1600                                      | 2         | 12.5%   |
| Validity Sensors Fingerprint scanner                   | 1         | 6.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 6.25%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 6.25%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 6.25%   |
| LighTuning Fingerprint Sensor                          | 1         | 6.25%   |
| Elan ELAN:Fingerprint                                  | 1         | 6.25%   |
| AuthenTec AES2810                                      | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| O2 Micro | 3         | 50%     |
| Broadcom | 2         | 33.33%  |
| Upek     | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 33.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 16.67%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom 5880                                                                | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 130       | 68.42%  |
| 1     | 51        | 26.84%  |
| 2     | 8         | 4.21%   |
| 5     | 1         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 18        | 25%     |
| Fingerprint reader       | 16        | 22.22%  |
| Net/wireless             | 12        | 16.67%  |
| Multimedia controller    | 7         | 9.72%   |
| Chipcard                 | 6         | 8.33%   |
| Camera                   | 3         | 4.17%   |
| Bluetooth                | 3         | 4.17%   |
| Storage                  | 2         | 2.78%   |
| Sound                    | 2         | 2.78%   |
| Network                  | 1         | 1.39%   |
| Net/ethernet             | 1         | 1.39%   |
| Communication controller | 1         | 1.39%   |

