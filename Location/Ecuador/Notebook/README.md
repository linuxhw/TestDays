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

Total: 301

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo    | IdeaPad S145-14AST 81ST     | [a823e9adf2](https://linux-hardware.org/?probe=a823e9adf2) | Apr 26, 2024 |
| HP        | 1000                        | [dee2aa2dd9](https://linux-hardware.org/?probe=dee2aa2dd9) | Apr 25, 2024 |
| Apple     | MacBookPro9,2               | [d4f3102f5c](https://linux-hardware.org/?probe=d4f3102f5c) | Apr 25, 2024 |
| MSI       | Stealth GS77 12UE           | [47ff584537](https://linux-hardware.org/?probe=47ff584537) | Apr 14, 2024 |
| Apple     | MacBookPro9,2               | [39dff10b12](https://linux-hardware.org/?probe=39dff10b12) | Apr 08, 2024 |
| ASUSTek   | VivoBook_ASUSLaptop X160... | [a95e92f1f5](https://linux-hardware.org/?probe=a95e92f1f5) | Mar 16, 2024 |
| Dell      | G15 5515                    | [527be515b4](https://linux-hardware.org/?probe=527be515b4) | Mar 12, 2024 |
| Toshiba   | Satellite P855              | [cb7eb1810c](https://linux-hardware.org/?probe=cb7eb1810c) | Feb 26, 2024 |
| HP        | OMEN by Laptop              | [68bbab3ac1](https://linux-hardware.org/?probe=68bbab3ac1) | Feb 19, 2024 |
| Google    | Blooglet                    | [66b986a87d](https://linux-hardware.org/?probe=66b986a87d) | Feb 19, 2024 |
| HP        | 245 G8                      | [c66563da68](https://linux-hardware.org/?probe=c66563da68) | Feb 14, 2024 |
| Google    | Blooglet                    | [34a54def3d](https://linux-hardware.org/?probe=34a54def3d) | Feb 13, 2024 |
| HP        | OMEN by Laptop 15-dh1xxx    | [f4f20111f0](https://linux-hardware.org/?probe=f4f20111f0) | Feb 12, 2024 |
| Toshiba   | Satellite C55-B             | [f9989aa45a](https://linux-hardware.org/?probe=f9989aa45a) | Feb 09, 2024 |
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
| Ubuntu 20.04                 | 23        | 10.7%   |
| Ubuntu 18.04                 | 11        | 5.12%   |
| Ubuntu 22.04                 | 9         | 4.19%   |
| Debian 11                    | 8         | 3.72%   |
| Linux Mint 20.3              | 7         | 3.26%   |
| KDE neon 20.04               | 6         | 2.79%   |
| Fedora 38                    | 6         | 2.79%   |
| OpenMandriva 4.3             | 5         | 2.33%   |
| Linux Mint 21.1              | 5         | 2.33%   |
| Linux Mint 19.3              | 5         | 2.33%   |
| Zorin 16                     | 4         | 1.86%   |
| Zorin 15                     | 4         | 1.86%   |
| Ubuntu 23.10                 | 3         | 1.4%    |
| Pop!_OS 21.10                | 3         | 1.4%    |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 1.4%    |
| OpenMandriva 23.03           | 3         | 1.4%    |
| LMDE 5                       | 3         | 1.4%    |
| LMDE 4                       | 3         | 1.4%    |
| Linux Mint 21.2              | 3         | 1.4%    |
| Garuda Linux Soaring         | 3         | 1.4%    |
| Fedora 37                    | 3         | 1.4%    |
| Fedora 34                    | 3         | 1.4%    |
| Fedora 33                    | 3         | 1.4%    |
| ArcoLinux Rolling            | 3         | 1.4%    |
| Arch Rolling                 | 3         | 1.4%    |
| Zorin 17                     | 2         | 0.93%   |
| Xubuntu 20.04                | 2         | 0.93%   |
| Ubuntu 22.10                 | 2         | 0.93%   |
| Ubuntu 21.10                 | 2         | 0.93%   |
| Ubuntu 21.04                 | 2         | 0.93%   |
| Ubuntu                       | 2         | 0.93%   |
| Pop!_OS 21.04                | 2         | 0.93%   |
| Pop!_OS 20.04                | 2         | 0.93%   |
| OpenMandriva 23.01           | 2         | 0.93%   |
| Linux Mint 20.1              | 2         | 0.93%   |
| Linux Mint 20                | 2         | 0.93%   |
| Kubuntu 22.04                | 2         | 0.93%   |
| Fedora 36                    | 2         | 0.93%   |
| Elementary 5.1.7             | 2         | 0.93%   |
| Debian 12                    | 2         | 0.93%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 55        | 26.44%  |
| Linux Mint    | 24        | 11.54%  |
| Fedora        | 21        | 10.1%   |
| OpenMandriva  | 13        | 6.25%   |
| Debian        | 12        | 5.77%   |
| Zorin         | 10        | 4.81%   |
| Pop!_OS       | 8         | 3.85%   |
| KDE neon      | 7         | 3.37%   |
| LMDE          | 5         | 2.4%    |
| Elementary    | 5         | 2.4%    |
| Xubuntu       | 4         | 1.92%   |
| Manjaro       | 4         | 1.92%   |
| Lubuntu       | 4         | 1.92%   |
| Arch          | 4         | 1.92%   |
| Ubuntu MATE   | 3         | 1.44%   |
| openSUSE      | 3         | 1.44%   |
| Kubuntu       | 3         | 1.44%   |
| Garuda Linux  | 3         | 1.44%   |
| ArcoLinux     | 3         | 1.44%   |
| Ubuntu Budgie | 2         | 0.96%   |
| SteamOS       | 2         | 0.96%   |
| Kali          | 2         | 0.96%   |
| Endless       | 2         | 0.96%   |
| BlackPanther  | 2         | 0.96%   |
| Xero          | 1         | 0.48%   |
| Void Linux    | 1         | 0.48%   |
| ROSA          | 1         | 0.48%   |
| RHEL          | 1         | 0.48%   |
| Parrot        | 1         | 0.48%   |
| EndeavourOS   | 1         | 0.48%   |
| Deepin        | 1         | 0.48%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-54-generic         | 4         | 1.72%   |
| 5.4.0-42-generic         | 4         | 1.72%   |
| 5.16.7-desktop-1omv4003  | 4         | 1.72%   |
| 5.15.0-33-generic        | 4         | 1.72%   |
| 5.13.0-35-generic        | 4         | 1.72%   |
| 5.4.0-58-generic         | 3         | 1.29%   |
| 5.4.0-56-generic         | 3         | 1.29%   |
| 5.4.0-48-generic         | 3         | 1.29%   |
| 5.4.0-45-generic         | 3         | 1.29%   |
| 5.4.0-26-generic         | 3         | 1.29%   |
| 5.16.11-76051611-generic | 3         | 1.29%   |
| 5.15.0-56-generic        | 3         | 1.29%   |
| 6.2.6-desktop-1omv2390   | 2         | 0.86%   |
| 6.1.1-desktop-1omv2290   | 2         | 0.86%   |
| 6.1.0-13-amd64           | 2         | 0.86%   |
| 5.8.0-43-generic         | 2         | 0.86%   |
| 5.8.0-41-generic         | 2         | 0.86%   |
| 5.8.0-14-generic         | 2         | 0.86%   |
| 5.4.0-77-generic         | 2         | 0.86%   |
| 5.4.0-7634-generic       | 2         | 0.86%   |
| 5.4.0-110-generic        | 2         | 0.86%   |
| 5.3.0-62-generic         | 2         | 0.86%   |
| 5.15.59-xanmod1          | 2         | 0.86%   |
| 5.15.0-58-generic        | 2         | 0.86%   |
| 5.15.0-27-generic        | 2         | 0.86%   |
| 5.13.0-7614-generic      | 2         | 0.86%   |
| 5.13.0-51-generic        | 2         | 0.86%   |
| 5.13.0-27-generic        | 2         | 0.86%   |
| 5.10.0-23-amd64          | 2         | 0.86%   |
| 5.0.0-37-generic         | 2         | 0.86%   |
| 5.0.0-23-generic         | 2         | 0.86%   |
| 4.18.16-desktop-1bP      | 2         | 0.86%   |
| 4.15.0-54-generic        | 2         | 0.86%   |
| 6.8.5-zen1-1-zen         | 1         | 0.43%   |
| 6.7.9-arch1-1            | 1         | 0.43%   |
| 6.7.5-arch1-1            | 1         | 0.43%   |
| 6.7.5-1-default          | 1         | 0.43%   |
| 6.5.9-arch2-1            | 1         | 0.43%   |
| 6.5.9-1-default          | 1         | 0.43%   |
| 6.5.6-200.fc38.x86_64    | 1         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 42        | 18.92%  |
| 5.15.0  | 22        | 9.91%   |
| 5.13.0  | 15        | 6.76%   |
| 6.5.0   | 9         | 4.05%   |
| 4.15.0  | 8         | 3.6%    |
| 5.8.0   | 7         | 3.15%   |
| 5.0.0   | 7         | 3.15%   |
| 5.10.0  | 6         | 2.7%    |
| 6.1.0   | 5         | 2.25%   |
| 5.11.0  | 5         | 2.25%   |
| 6.2.0   | 4         | 1.8%    |
| 5.3.0   | 4         | 1.8%    |
| 5.19.0  | 4         | 1.8%    |
| 5.16.7  | 4         | 1.8%    |
| 5.16.11 | 3         | 1.35%   |
| 6.7.5   | 2         | 0.9%    |
| 6.5.9   | 2         | 0.9%    |
| 6.4.10  | 2         | 0.9%    |
| 6.3.5   | 2         | 0.9%    |
| 6.2.6   | 2         | 0.9%    |
| 6.2.2   | 2         | 0.9%    |
| 6.1.1   | 2         | 0.9%    |
| 5.17.5  | 2         | 0.9%    |
| 5.15.59 | 2         | 0.9%    |
| 4.18.16 | 2         | 0.9%    |
| 4.18.0  | 2         | 0.9%    |
| 6.8.5   | 1         | 0.45%   |
| 6.7.9   | 1         | 0.45%   |
| 6.5.6   | 1         | 0.45%   |
| 6.5.3   | 1         | 0.45%   |
| 6.5.11  | 1         | 0.45%   |
| 6.4.8   | 1         | 0.45%   |
| 6.4.6   | 1         | 0.45%   |
| 6.4.3   | 1         | 0.45%   |
| 6.2.9   | 1         | 0.45%   |
| 6.2.15  | 1         | 0.45%   |
| 6.2.12  | 1         | 0.45%   |
| 6.1.9   | 1         | 0.45%   |
| 6.1.86  | 1         | 0.45%   |
| 6.1.31  | 1         | 0.45%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 45        | 20.74%  |
| 5.15    | 26        | 11.98%  |
| 5.13    | 15        | 6.91%   |
| 6.5     | 14        | 6.45%   |
| 6.2     | 11        | 5.07%   |
| 6.1     | 10        | 4.61%   |
| 5.16    | 10        | 4.61%   |
| 5.10    | 10        | 4.61%   |
| 5.8     | 8         | 3.69%   |
| 4.15    | 8         | 3.69%   |
| 5.11    | 7         | 3.23%   |
| 5.0     | 7         | 3.23%   |
| 5.19    | 6         | 2.76%   |
| 6.4     | 5         | 2.3%    |
| 5.3     | 5         | 2.3%    |
| 4.18    | 4         | 1.84%   |
| 6.7     | 3         | 1.38%   |
| 6.0     | 3         | 1.38%   |
| 5.18    | 3         | 1.38%   |
| 5.14    | 3         | 1.38%   |
| 6.3     | 2         | 0.92%   |
| 5.7     | 2         | 0.92%   |
| 5.5     | 2         | 0.92%   |
| 5.17    | 2         | 0.92%   |
| 5.12    | 2         | 0.92%   |
| 6.8     | 1         | 0.46%   |
| 5.9     | 1         | 0.46%   |
| 4.9     | 1         | 0.46%   |
| 4.19    | 1         | 0.46%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 187       | 94.92%  |
| i686   | 10        | 5.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 87        | 42.23%  |
| KDE5       | 33        | 16.02%  |
| X-Cinnamon | 22        | 10.68%  |
| Unknown    | 20        | 9.71%   |
| XFCE       | 13        | 6.31%   |
| MATE       | 8         | 3.88%   |
| Pantheon   | 5         | 2.43%   |
| KDE        | 5         | 2.43%   |
| LXQt       | 4         | 1.94%   |
| LXDE       | 2         | 0.97%   |
| Budgie     | 2         | 0.97%   |
| qtile      | 1         | 0.49%   |
| jwm        | 1         | 0.49%   |
| ICEWM      | 1         | 0.49%   |
| Deepin     | 1         | 0.49%   |
| Cinnamon   | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 152       | 74.15%  |
| Wayland | 41        | 20%     |
| Unknown | 12        | 5.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 108       | 51.67%  |
| SDDM    | 31        | 14.83%  |
| GDM     | 25        | 11.96%  |
| LightDM | 21        | 10.05%  |
| GDM3    | 21        | 10.05%  |
| TDM     | 3         | 1.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_EC   | 89        | 44.06%  |
| en_US   | 52        | 25.74%  |
| es_ES   | 20        | 9.9%    |
| Unknown | 15        | 7.43%   |
| es_MX   | 9         | 4.46%   |
| de_DE   | 4         | 1.98%   |
| es_US   | 3         | 1.49%   |
| es_CO   | 3         | 1.49%   |
| es_PE   | 2         | 0.99%   |
| C       | 2         | 0.99%   |
| ru_RU   | 1         | 0.5%    |
| fr_FR   | 1         | 0.5%    |
| en_GB   | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 113       | 55.67%  |
| BIOS | 90        | 44.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 149       | 73.4%   |
| Btrfs   | 27        | 13.3%   |
| Overlay | 15        | 7.39%   |
| Tmpfs   | 6         | 2.96%   |
| Zfs     | 2         | 0.99%   |
| Xfs     | 2         | 0.99%   |
| Ext2    | 1         | 0.49%   |
| Unknown | 1         | 0.49%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 109       | 53.69%  |
| GPT     | 79        | 38.92%  |
| MBR     | 15        | 7.39%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 171       | 85.5%   |
| Yes       | 29        | 14.5%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 140       | 68.97%  |
| Yes       | 63        | 31.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 44        | 22.34%  |
| Lenovo              | 31        | 15.74%  |
| Dell                | 30        | 15.23%  |
| ASUSTek Computer    | 18        | 9.14%   |
| Toshiba             | 16        | 8.12%   |
| Acer                | 10        | 5.08%   |
| Apple               | 9         | 4.57%   |
| Google              | 7         | 3.55%   |
| Sony                | 6         | 3.05%   |
| Samsung Electronics | 4         | 2.03%   |
| MSI                 | 4         | 2.03%   |
| Gateway             | 3         | 1.52%   |
| Unknown             | 3         | 1.52%   |
| Valve               | 2         | 1.02%   |
| Razer               | 2         | 1.02%   |
| Alienware           | 2         | 1.02%   |
| Timi                | 1         | 0.51%   |
| HUAWEI              | 1         | 0.51%   |
| Fujitsu             | 1         | 0.51%   |
| Dynabook            | 1         | 0.51%   |
| Compal              | 1         | 0.51%   |
| Chuwi               | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 5         | 2.54%   |
| HP Notebook                              | 3         | 1.52%   |
| Valve Jupiter                            | 2         | 1.02%   |
| Toshiba Satellite S55-B                  | 2         | 1.02%   |
| Toshiba Satellite C55-B                  | 2         | 1.02%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 2         | 1.02%   |
| Lenovo IdeaPad 330S-15IKB 81F5           | 2         | 1.02%   |
| Lenovo IdeaPad 320-15ABR 80XS            | 2         | 1.02%   |
| HP ProBook 4440s                         | 2         | 1.02%   |
| HP Pavilion Laptop 15-cw1xxx             | 2         | 1.02%   |
| HP Pavilion Laptop 15-cw0xxx             | 2         | 1.02%   |
| HP Laptop 15-da0xxx                      | 2         | 1.02%   |
| HP 1000                                  | 2         | 1.02%   |
| Dell Vostro 3480                         | 2         | 1.02%   |
| Dell Inspiron 5570                       | 2         | 1.02%   |
| Dell Inspiron 3442                       | 2         | 1.02%   |
| Dell Inspiron 1420                       | 2         | 1.02%   |
| Dell G5 5587                             | 2         | 1.02%   |
| ASUS VivoBook_ASUSLaptop X1605VA_X1605VA | 2         | 1.02%   |
| ASUS ASUS TUF Gaming A15 FA506II_FA506II | 2         | 1.02%   |
| Apple MacBookPro9,2                      | 2         | 1.02%   |
| Apple MacBookPro12,1                     | 2         | 1.02%   |
| Toshiba Satellite S55-A                  | 1         | 0.51%   |
| Toshiba Satellite P855                   | 1         | 0.51%   |
| Toshiba Satellite P775                   | 1         | 0.51%   |
| Toshiba Satellite P55W-C                 | 1         | 0.51%   |
| Toshiba Satellite L50-B                  | 1         | 0.51%   |
| Toshiba Satellite L45-B                  | 1         | 0.51%   |
| Toshiba Satellite E45t-B                 | 1         | 0.51%   |
| Toshiba Satellite C55D-A                 | 1         | 0.51%   |
| Toshiba Satellite C45-A                  | 1         | 0.51%   |
| Toshiba Satellite A205                   | 1         | 0.51%   |
| Toshiba Satellite A135                   | 1         | 0.51%   |
| Toshiba PORTEGE M805                     | 1         | 0.51%   |
| Timi RedmiBook 14-APCS                   | 1         | 0.51%   |
| Sony VPCEG30EL                           | 1         | 0.51%   |
| Sony VPCEG23EL                           | 1         | 0.51%   |
| Sony VPCCW1S1E                           | 1         | 0.51%   |
| Sony VGN-CR120E                          | 1         | 0.51%   |
| Sony SVE14A25CLB                         | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 17        | 8.63%   |
| Dell Inspiron      | 17        | 8.63%   |
| Toshiba Satellite  | 15        | 7.61%   |
| HP Pavilion        | 10        | 5.08%   |
| HP Laptop          | 8         | 4.06%   |
| ASUS VivoBook      | 8         | 4.06%   |
| Lenovo ThinkPad    | 7         | 3.55%   |
| Dell Latitude      | 6         | 3.05%   |
| Acer Aspire        | 6         | 3.05%   |
| Unknown            | 5         | 2.54%   |
| HP ProBook         | 3         | 1.52%   |
| HP Notebook        | 3         | 1.52%   |
| HP ENVY            | 3         | 1.52%   |
| Valve Jupiter      | 2         | 1.02%   |
| Razer Blade        | 2         | 1.02%   |
| MSI Stealth        | 2         | 1.02%   |
| HP OMEN            | 2         | 1.02%   |
| HP EliteBook       | 2         | 1.02%   |
| HP 245             | 2         | 1.02%   |
| HP 15              | 2         | 1.02%   |
| HP 1000            | 2         | 1.02%   |
| Dell Vostro        | 2         | 1.02%   |
| Dell G5            | 2         | 1.02%   |
| ASUS ASUS          | 2         | 1.02%   |
| Apple MacBookPro9  | 2         | 1.02%   |
| Apple MacBookPro12 | 2         | 1.02%   |
| Acer TravelMate    | 2         | 1.02%   |
| Toshiba PORTEGE    | 1         | 0.51%   |
| Timi RedmiBook     | 1         | 0.51%   |
| Sony VPCEG30EL     | 1         | 0.51%   |
| Sony VPCEG23EL     | 1         | 0.51%   |
| Sony VPCCW1S1E     | 1         | 0.51%   |
| Sony VGN-CR120E    | 1         | 0.51%   |
| Sony SVE14A25CLB   | 1         | 0.51%   |
| Sony SVE14113ELW   | 1         | 0.51%   |
| Samsung R519       | 1         | 0.51%   |
| Samsung N102SP     | 1         | 0.51%   |
| Samsung 550XCJ     | 1         | 0.51%   |
| Samsung 530U4E     | 1         | 0.51%   |
| MSI MS-7D46        | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 23        | 11.68%  |
| 2019 | 19        | 9.64%   |
| 2012 | 19        | 9.64%   |
| 2020 | 18        | 9.14%   |
| 2017 | 16        | 8.12%   |
| 2021 | 14        | 7.11%   |
| 2013 | 13        | 6.6%    |
| 2016 | 10        | 5.08%   |
| 2014 | 10        | 5.08%   |
| 2011 | 10        | 5.08%   |
| 2015 | 9         | 4.57%   |
| 2007 | 9         | 4.57%   |
| 2022 | 7         | 3.55%   |
| 2010 | 6         | 3.05%   |
| 2009 | 5         | 2.54%   |
| 2023 | 3         | 1.52%   |
| 2006 | 3         | 1.52%   |
| 2024 | 1         | 0.51%   |
| 2008 | 1         | 0.51%   |
| 2005 | 1         | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 197       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 183       | 92.42%  |
| Enabled  | 15        | 7.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 189       | 95.94%  |
| Yes  | 8         | 4.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 63        | 31.03%  |
| 3.01-4.0    | 40        | 19.7%   |
| 8.01-16.0   | 36        | 17.73%  |
| 16.01-24.0  | 29        | 14.29%  |
| 1.01-2.0    | 14        | 6.9%    |
| 32.01-64.0  | 13        | 6.4%    |
| 2.01-3.0    | 4         | 1.97%   |
| 24.01-32.0  | 2         | 0.99%   |
| 64.01-256.0 | 1         | 0.49%   |
| 0.51-1.0    | 1         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 64        | 29.77%  |
| 1.01-2.0   | 60        | 27.91%  |
| 4.01-8.0   | 40        | 18.6%   |
| 3.01-4.0   | 33        | 15.35%  |
| 8.01-16.0  | 7         | 3.26%   |
| 0.51-1.0   | 7         | 3.26%   |
| 0.01-0.5   | 3         | 1.4%    |
| 24.01-32.0 | 1         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 148       | 73.63%  |
| 2      | 51        | 25.37%  |
| 3      | 2         | 1%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 133       | 67.17%  |
| Yes       | 65        | 32.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 158       | 80.2%   |
| No        | 39        | 19.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 196       | 99.49%  |
| No        | 1         | 0.51%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 155       | 77.89%  |
| No        | 44        | 22.11%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Ecuador | 197       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Quito                          | 80        | 38.83%  |
| Guayaquil                      | 52        | 25.24%  |
| Cuenca                         | 23        | 11.17%  |
| Loja                           | 9         | 4.37%   |
| Ambato                         | 5         | 2.43%   |
| Portoviejo                     | 4         | 1.94%   |
| Manta                          | 4         | 1.94%   |
| Machala                        | 4         | 1.94%   |
| Hacienda Ibarra                | 3         | 1.46%   |
| Riobamba                       | 2         | 0.97%   |
| Ayacucho                       | 2         | 0.97%   |
| Uyumbicho                      | 1         | 0.49%   |
| Santo Domingo de los Colorados | 1         | 0.49%   |
| Samborondon                    | 1         | 0.49%   |
| Provincia del Chimborazo       | 1         | 0.49%   |
| Otavalo                        | 1         | 0.49%   |
| Nueva Loja                     | 1         | 0.49%   |
| Montecristi                    | 1         | 0.49%   |
| Latacunga                      | 1         | 0.49%   |
| La Troncal                     | 1         | 0.49%   |
| La Providencia                 | 1         | 0.49%   |
| La Mana                        | 1         | 0.49%   |
| La Concordia Numero Uno        | 1         | 0.49%   |
| Ibarra                         | 1         | 0.49%   |
| Hacienda San Sebastian         | 1         | 0.49%   |
| Guamani                        | 1         | 0.49%   |
| Febres Cordero                 | 1         | 0.49%   |
| Cayambe                        | 1         | 0.49%   |
| Babahoyo                       | 1         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 46        | 57     | 18.7%   |
| Toshiba                     | 40        | 44     | 16.26%  |
| Seagate                     | 29        | 45     | 11.79%  |
| Kingston                    | 15        | 17     | 6.1%    |
| Samsung Electronics         | 14        | 15     | 5.69%   |
| SK hynix                    | 11        | 13     | 4.47%   |
| Hitachi                     | 10        | 13     | 4.07%   |
| Unknown                     | 9         | 14     | 3.66%   |
| SanDisk                     | 9         | 13     | 3.66%   |
| A-DATA Technology           | 8         | 11     | 3.25%   |
| Micron Technology           | 6         | 6      | 2.44%   |
| HGST                        | 6         | 8      | 2.44%   |
| Hewlett-Packard             | 6         | 7      | 2.44%   |
| Apple                       | 4         | 5      | 1.63%   |
| KIOXIA                      | 3         | 3      | 1.22%   |
| Kingston Technology Company | 3         | 3      | 1.22%   |
| JMicron Technology          | 3         | 3      | 1.22%   |
| Intel                       | 2         | 4      | 0.81%   |
| Fujitsu                     | 2         | 2      | 0.81%   |
| Crucial                     | 2         | 2      | 0.81%   |
| USB3.0                      | 1         | 1      | 0.41%   |
| UMIS                        | 1         | 1      | 0.41%   |
| SABRENT                     | 1         | 1      | 0.41%   |
| Realtek Semiconductor       | 1         | 1      | 0.41%   |
| PNY                         | 1         | 1      | 0.41%   |
| Phison Electronics          | 1         | 1      | 0.41%   |
| Phison                      | 1         | 1      | 0.41%   |
| Patriot                     | 1         | 1      | 0.41%   |
| OWC                         | 1         | 1      | 0.41%   |
| Netac                       | 1         | 1      | 0.41%   |
| Micron/Crucial Technology   | 1         | 1      | 0.41%   |
| LITEON                      | 1         | 1      | 0.41%   |
| Lite-On                     | 1         | 1      | 0.41%   |
| HS-SSD-E100N                | 1         | 1      | 0.41%   |
| Hjwdz                       | 1         | 1      | 0.41%   |
| Golden                      | 1         | 1      | 0.41%   |
| Gigabyte Technology         | 1         | 1      | 0.41%   |
| Unknown                     | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                            | 7         | 2.76%   |
| Seagate ST1000LM035-1RK172 1TB                    | 7         | 2.76%   |
| Toshiba MQ01ABF050 500GB                          | 6         | 2.36%   |
| Kingston SA400S37240G 240GB SSD                   | 5         | 1.97%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 4         | 1.57%   |
| WDC WD10SPZX-24Z10 1TB                            | 4         | 1.57%   |
| Unknown MMC Card  16GB                            | 4         | 1.57%   |
| Seagate ST2000LM007-1R8174 2TB                    | 4         | 1.57%   |
| Toshiba MQ01ABD100 1TB                            | 3         | 1.18%   |
| Toshiba MQ01ABD075 752GB                          | 3         | 1.18%   |
| Kingston SA400S37480G 480GB SSD                   | 3         | 1.18%   |
| HP SSD S700 500GB                                 | 3         | 1.18%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 2         | 0.79%   |
| WDC WD1600BEVT-22ZCT0 160GB                       | 2         | 0.79%   |
| WDC WD10SPZX-24Z10T0 1TB                          | 2         | 0.79%   |
| WDC WD10SPZX-22Z10T1 1TB                          | 2         | 0.79%   |
| WDC WD10JPVX-75JC3T0 1TB                          | 2         | 0.79%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 2         | 0.79%   |
| Unknown MMC Card  32GB                            | 2         | 0.79%   |
| Toshiba MQ01ABD100M 1TB                           | 2         | 0.79%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD           | 2         | 0.79%   |
| SK hynix SKHynix_HFS512GDE9X084N 512GB            | 2         | 0.79%   |
| Seagate ST9500325AS 500GB                         | 2         | 0.79%   |
| Seagate ST500LT012-9WS142 500GB                   | 2         | 0.79%   |
| Seagate ST500LT012-1DG142 500GB                   | 2         | 0.79%   |
| SanDisk NVMe SSD Drive 1TB                        | 2         | 0.79%   |
| Samsung SSD 860 EVO 1TB                           | 2         | 0.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 0.79%   |
| Micron NVMe SSD Drive 512GB                       | 2         | 0.79%   |
| Micron 3400_MTFDKBA1T0TFH 1TB                     | 2         | 0.79%   |
| JMicron Generic 320GB                             | 2         | 0.79%   |
| Hitachi HTS543232A7A384 320GB                     | 2         | 0.79%   |
| Hitachi HTS541616J9SA00 160GB                     | 2         | 0.79%   |
| HGST HTS545050A7E380 500GB                        | 2         | 0.79%   |
| HGST HTS541010A9E680 1TB                          | 2         | 0.79%   |
| A-DATA SU650 120GB SSD                            | 2         | 0.79%   |
| A-DATA SU630 960GB SSD                            | 2         | 0.79%   |
| A-DATA ED600 1TB SSD                              | 2         | 0.79%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                  | 1         | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 36        | 39     | 30.77%  |
| WDC                 | 29        | 38     | 24.79%  |
| Seagate             | 29        | 45     | 24.79%  |
| Hitachi             | 10        | 13     | 8.55%   |
| HGST                | 6         | 8      | 5.13%   |
| JMicron Technology  | 2         | 2      | 1.71%   |
| Fujitsu             | 2         | 2      | 1.71%   |
| Unknown             | 1         | 3      | 0.85%   |
| Samsung Electronics | 1         | 1      | 0.85%   |
| SABRENT             | 1         | 1      | 0.85%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 13     | 19.35%  |
| Kingston            | 11        | 11     | 17.74%  |
| A-DATA Technology   | 7         | 10     | 11.29%  |
| SanDisk             | 5         | 5      | 8.06%   |
| Hewlett-Packard     | 5         | 6      | 8.06%   |
| Samsung Electronics | 3         | 3      | 4.84%   |
| Apple               | 3         | 4      | 4.84%   |
| Toshiba             | 2         | 3      | 3.23%   |
| SK hynix            | 2         | 2      | 3.23%   |
| Crucial             | 2         | 2      | 3.23%   |
| USB3.0              | 1         | 1      | 1.61%   |
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
| HDD     | 112       | 152    | 48.07%  |
| NVMe    | 55        | 68     | 23.61%  |
| SSD     | 55        | 69     | 23.61%  |
| MMC     | 9         | 12     | 3.86%   |
| Unknown | 2         | 2      | 0.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 154       | 206    | 67.54%  |
| NVMe | 55        | 68     | 24.12%  |
| SAS  | 10        | 17     | 4.39%   |
| MMC  | 9         | 12     | 3.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 103       | 125    | 59.54%  |
| 0.51-1.0   | 62        | 88     | 35.84%  |
| 1.01-2.0   | 8         | 8      | 4.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 51        | 24.52%  |
| 251-500        | 50        | 24.04%  |
| 501-1000       | 32        | 15.38%  |
| 1001-2000      | 25        | 12.02%  |
| 1-20           | 14        | 6.73%   |
| 21-50          | 13        | 6.25%   |
| 51-100         | 12        | 5.77%   |
| Unknown        | 6         | 2.88%   |
| More than 3000 | 4         | 1.92%   |
| 2001-3000      | 1         | 0.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 74        | 34.74%  |
| 21-50     | 41        | 19.25%  |
| 101-250   | 39        | 18.31%  |
| 51-100    | 20        | 9.39%   |
| 251-500   | 19        | 8.92%   |
| 501-1000  | 10        | 4.69%   |
| Unknown   | 6         | 2.82%   |
| 1001-2000 | 3         | 1.41%   |
| 2001-3000 | 1         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB       | 2         | 3      | 12.5%   |
| WDC WD5000LPVT-00G33T0 500GB   | 1         | 1      | 6.25%   |
| WDC WD5000LPCX-24VHAT0 500GB   | 1         | 2      | 6.25%   |
| Toshiba MQ01ABD100M 1TB        | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD100 1TB         | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD075 752GB       | 1         | 1      | 6.25%   |
| Toshiba MK3265GSXN 320GB       | 1         | 1      | 6.25%   |
| Toshiba MK3259GSXP 320GB       | 1         | 1      | 6.25%   |
| Toshiba MK2561GSYN 250GB       | 1         | 2      | 6.25%   |
| Seagate ST1000LX015-1U7172 1TB | 1         | 3      | 6.25%   |
| Seagate ST1000LM035-1RK172 1TB | 1         | 1      | 6.25%   |
| Hitachi HTS547550A9E384 500GB  | 1         | 1      | 6.25%   |
| Hitachi HTS543232L9SA00 320GB  | 1         | 1      | 6.25%   |
| HGST HTS545050A7E380 500GB     | 1         | 1      | 6.25%   |
| Fujitsu MHY2250BH 250GB        | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 8         | 10     | 50%     |
| WDC     | 2         | 3      | 12.5%   |
| Seagate | 2         | 4      | 12.5%   |
| Hitachi | 2         | 2      | 12.5%   |
| HGST    | 1         | 1      | 6.25%   |
| Fujitsu | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 8         | 10     | 50%     |
| WDC     | 2         | 3      | 12.5%   |
| Seagate | 2         | 4      | 12.5%   |
| Hitachi | 2         | 2      | 12.5%   |
| HGST    | 1         | 1      | 6.25%   |
| Fujitsu | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 21     | 100%    |

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
| Detected | 123       | 189    | 58.85%  |
| Works    | 70        | 93     | 33.49%  |
| Malfunc  | 16        | 21     | 7.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 134       | 58.26%  |
| AMD                          | 37        | 16.09%  |
| Samsung Electronics          | 13        | 5.65%   |
| SanDisk                      | 10        | 4.35%   |
| SK hynix                     | 9         | 3.91%   |
| Kingston Technology Company  | 7         | 3.04%   |
| Micron Technology            | 5         | 2.17%   |
| KIOXIA                       | 3         | 1.3%    |
| Toshiba America Info Systems | 2         | 0.87%   |
| Phison Electronics           | 2         | 0.87%   |
| Union Memory (Shenzhen)      | 1         | 0.43%   |
| Silicon Motion               | 1         | 0.43%   |
| Realtek Semiconductor        | 1         | 0.43%   |
| Nvidia                       | 1         | 0.43%   |
| Micron/Crucial Technology    | 1         | 0.43%   |
| Lite-On Technology           | 1         | 0.43%   |
| Apple                        | 1         | 0.43%   |
| ADATA Technology             | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 35        | 14.29%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 18        | 7.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 17        | 6.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 16        | 6.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 3.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 2.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 2.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 6         | 2.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 2.04%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 4         | 1.63%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 4         | 1.63%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 1.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 1.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 4         | 1.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 4         | 1.63%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 3         | 1.22%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 1.22%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                               | 3         | 1.22%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation            | 3         | 1.22%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.22%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 1.22%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.22%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 1.22%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.82%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 2         | 0.82%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 2         | 0.82%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 2         | 0.82%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 0.82%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 2         | 0.82%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.82%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 0.82%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 0.82%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 0.82%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                  | 1         | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 141       | 59.24%  |
| NVMe | 55        | 23.11%  |
| RAID | 25        | 10.5%   |
| IDE  | 17        | 7.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 151       | 76.65%  |
| AMD    | 46        | 23.35%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 4.57%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 3.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.54%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 4         | 2.03%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.03%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 1.52%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 3         | 1.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.52%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.52%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.52%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 3         | 1.52%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 1.52%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 1.52%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 3         | 1.52%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 1.02%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.02%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.02%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.02%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 1.02%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.02%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 1.02%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.02%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.02%   |
| Intel Core i5-5257U CPU @ 2.70GHz             | 2         | 1.02%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.02%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.02%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.02%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.02%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 1.02%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 1.02%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 2         | 1.02%   |
| Intel Core 2 Duo CPU T5750 @ 2.00GHz          | 2         | 1.02%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 2         | 1.02%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 1.02%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 1.02%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 2         | 1.02%   |
| Intel 13th Gen Core i9-13900H                 | 2         | 1.02%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.02%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.02%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.02%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 47        | 23.86%  |
| Intel Core i5           | 31        | 15.74%  |
| Intel Core i3           | 20        | 10.15%  |
| Other                   | 17        | 8.63%   |
| Intel Celeron           | 16        | 8.12%   |
| Intel Core 2 Duo        | 11        | 5.58%   |
| AMD Ryzen 5             | 11        | 5.58%   |
| AMD Ryzen 7             | 7         | 3.55%   |
| Intel Atom              | 3         | 1.52%   |
| AMD Ryzen 3             | 3         | 1.52%   |
| AMD E2                  | 3         | 1.52%   |
| AMD A6                  | 3         | 1.52%   |
| Intel Pentium Dual-Core | 2         | 1.02%   |
| Intel Pentium           | 2         | 1.02%   |
| Intel Genuine           | 2         | 1.02%   |
| AMD E1                  | 2         | 1.02%   |
| AMD E                   | 2         | 1.02%   |
| AMD A8                  | 2         | 1.02%   |
| AMD A4                  | 2         | 1.02%   |
| AMD A12                 | 2         | 1.02%   |
| Intel Pentium Silver    | 1         | 0.51%   |
| Intel Pentium M         | 1         | 0.51%   |
| Intel Core m3           | 1         | 0.51%   |
| Intel Celeron M         | 1         | 0.51%   |
| AMD Ryzen 7 PRO         | 1         | 0.51%   |
| AMD FX                  | 1         | 0.51%   |
| AMD C-70                | 1         | 0.51%   |
| AMD C-60                | 1         | 0.51%   |
| AMD A10                 | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 108       | 54.82%  |
| 4      | 57        | 28.93%  |
| 6      | 11        | 5.58%   |
| 8      | 8         | 4.06%   |
| 1      | 8         | 4.06%   |
| 14     | 4         | 2.03%   |
| 12     | 1         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 197       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 140       | 71.07%  |
| 1      | 57        | 28.93%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 193       | 97.97%  |
| 32-bit         | 3         | 1.52%   |
| Unknown        | 1         | 0.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 55        | 26.96%  |
| 0x806ea    | 12        | 5.88%   |
| 0x306a9    | 11        | 5.39%   |
| 0x206a7    | 11        | 5.39%   |
| 0x306d4    | 9         | 4.41%   |
| 0x6fd      | 7         | 3.43%   |
| 0x40651    | 7         | 3.43%   |
| 0x08108109 | 7         | 3.43%   |
| 0x06006705 | 5         | 2.45%   |
| 0x806c1    | 4         | 1.96%   |
| 0x706e5    | 4         | 1.96%   |
| 0x306c3    | 4         | 1.96%   |
| 0x1067a    | 4         | 1.96%   |
| 0x05000119 | 4         | 1.96%   |
| 0x906ea    | 3         | 1.47%   |
| 0x806eb    | 3         | 1.47%   |
| 0x806e9    | 3         | 1.47%   |
| 0x06006704 | 3         | 1.47%   |
| 0x0600611a | 3         | 1.47%   |
| 0x906ed    | 2         | 0.98%   |
| 0x806ec    | 2         | 0.98%   |
| 0x706a1    | 2         | 0.98%   |
| 0x6e8      | 2         | 0.98%   |
| 0x406e3    | 2         | 0.98%   |
| 0x406c4    | 2         | 0.98%   |
| 0x30678    | 2         | 0.98%   |
| 0x20655    | 2         | 0.98%   |
| 0x106ca    | 2         | 0.98%   |
| 0x08600104 | 2         | 0.98%   |
| 0x0810100b | 2         | 0.98%   |
| 0xa0660    | 1         | 0.49%   |
| 0xa0652    | 1         | 0.49%   |
| 0x906a3    | 1         | 0.49%   |
| 0x706a8    | 1         | 0.49%   |
| 0x6fa      | 1         | 0.49%   |
| 0x6d8      | 1         | 0.49%   |
| 0x506e3    | 1         | 0.49%   |
| 0x506c9    | 1         | 0.49%   |
| 0x406c3    | 1         | 0.49%   |
| 0x30673    | 1         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 37        | 18.78%  |
| IvyBridge        | 16        | 8.12%   |
| Haswell          | 15        | 7.61%   |
| SandyBridge      | 12        | 6.09%   |
| Excavator        | 12        | 6.09%   |
| Core             | 11        | 5.58%   |
| Zen+             | 9         | 4.57%   |
| Broadwell        | 9         | 4.57%   |
| TigerLake        | 7         | 3.55%   |
| Unknown          | 7         | 3.55%   |
| Silvermont       | 6         | 3.05%   |
| Skylake          | 5         | 2.54%   |
| Penryn           | 5         | 2.54%   |
| IceLake          | 5         | 2.54%   |
| Bobcat           | 5         | 2.54%   |
| Alderlake Hybrid | 5         | 2.54%   |
| Zen 2            | 4         | 2.03%   |
| Zen              | 4         | 2.03%   |
| Goldmont plus    | 4         | 2.03%   |
| Westmere         | 3         | 1.52%   |
| P6               | 3         | 1.52%   |
| CometLake        | 3         | 1.52%   |
| Bonnell          | 3         | 1.52%   |
| Zen 3            | 2         | 1.02%   |
| Puma             | 2         | 1.02%   |
| K10 Llano        | 1         | 0.51%   |
| Jaguar           | 1         | 0.51%   |
| Goldmont         | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 143       | 60.85%  |
| AMD    | 57        | 24.26%  |
| Nvidia | 35        | 14.89%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 16        | 6.48%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 6.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 4.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 4.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 4.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 3.24%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 3.24%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 3.24%   |
| Intel HD Graphics 5500                                                                   | 7         | 2.83%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 2.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 2.43%   |
| Intel HD Graphics 620                                                                    | 6         | 2.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 2.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.62%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 1.62%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 4         | 1.62%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.21%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.21%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.21%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 3         | 1.21%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.21%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 1.21%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.21%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.21%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.21%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.21%   |
| AMD Lucienne                                                                             | 3         | 1.21%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.81%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.81%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.81%   |
| Intel Iris Graphics 6100                                                                 | 2         | 0.81%   |
| Intel HD Graphics 630                                                                    | 2         | 0.81%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.81%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.81%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 107       | 54.31%  |
| 1 x AMD        | 42        | 21.32%  |
| Intel + Nvidia | 23        | 11.68%  |
| Intel + AMD    | 9         | 4.57%   |
| 1 x Nvidia     | 7         | 3.55%   |
| AMD + Nvidia   | 5         | 2.54%   |
| 2 x Intel      | 2         | 1.02%   |
| Other          | 1         | 0.51%   |
| 2 x AMD        | 1         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 173       | 87.37%  |
| Proprietary | 20        | 10.1%   |
| Unknown     | 5         | 2.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 126       | 62.69%  |
| 0.01-0.5   | 29        | 14.43%  |
| 1.01-2.0   | 21        | 10.45%  |
| 3.01-4.0   | 13        | 6.47%   |
| 0.51-1.0   | 7         | 3.48%   |
| 7.01-8.0   | 2         | 1%      |
| 5.01-6.0   | 2         | 1%      |
| 2.01-3.0   | 1         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 38        | 16.74%  |
| Chimei Innolux          | 36        | 15.86%  |
| AU Optronics            | 35        | 15.42%  |
| LG Display              | 28        | 12.33%  |
| Samsung Electronics     | 17        | 7.49%   |
| Goldstar                | 15        | 6.61%   |
| Apple                   | 9         | 3.96%   |
| Chi Mei Optoelectronics | 8         | 3.52%   |
| PANDA                   | 4         | 1.76%   |
| AOC                     | 4         | 1.76%   |
| LG Philips              | 3         | 1.32%   |
| Valve                   | 2         | 0.88%   |
| Sony                    | 2         | 0.88%   |
| Sharp                   | 2         | 0.88%   |
| InnoLux Display         | 2         | 0.88%   |
| InfoVision              | 2         | 0.88%   |
| Dell                    | 2         | 0.88%   |
| ASUSTek Computer        | 2         | 0.88%   |
| Acer                    | 2         | 0.88%   |
| ViewSonic               | 1         | 0.44%   |
| Unknown (XXX)           | 1         | 0.44%   |
| Toshiba                 | 1         | 0.44%   |
| TCL                     | 1         | 0.44%   |
| SKY                     | 1         | 0.44%   |
| MSI                     | 1         | 0.44%   |
| Lenovo                  | 1         | 0.44%   |
| Huion                   | 1         | 0.44%   |
| HKC                     | 1         | 0.44%   |
| Hewlett-Packard         | 1         | 0.44%   |
| Gigabyte Technology     | 1         | 0.44%   |
| CSO                     | 1         | 0.44%   |
| CPT                     | 1         | 0.44%   |
| BenQ                    | 1         | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                      | 5         | 2.19%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 4         | 1.75%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 4         | 1.75%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 340x190mm 15.3-inch       | 3         | 1.32%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 3         | 1.32%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.32%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                        | 3         | 1.32%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 2         | 0.88%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 2         | 0.88%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch           | 2         | 0.88%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 2         | 0.88%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 2         | 0.88%   |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                   | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch      | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch       | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 2         | 0.88%   |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                 | 2         | 0.88%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.88%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                  | 2         | 0.88%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                 | 2         | 0.88%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 0.88%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO325C 1366x768 256x144mm 11.6-inch         | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 0.88%   |
| Apple Color LCD APPA029 2560x1600 286x179mm 13.3-inch                 | 2         | 0.88%   |
| ViewSonic VA2855 SERIES VSCD62F 1920x1080 621x341mm 27.9-inch         | 1         | 0.44%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch         | 1         | 0.44%   |
| Toshiba LCD Monitor LCD3706 1280x800 261x163mm 12.1-inch              | 1         | 0.44%   |
| TCL SMART TV TCL6586 3840x2160 1209x680mm 54.6-inch                   | 1         | 0.44%   |
| Sony TV SNYAB03 1920x1080                                             | 1         | 0.44%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.44%   |
| SKY TV-monitor SKY1202 1920x1080 885x498mm 40.0-inch                  | 1         | 0.44%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.44%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch               | 1         | 0.44%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5742 1366x768 309x174mm 14.0-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5557 1920x1200 367x230mm 17.1-inch | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 101       | 46.98%  |
| 1920x1080 (FHD)   | 63        | 29.3%   |
| 1280x800 (WXGA)   | 13        | 6.05%   |
| 1600x900 (HD+)    | 12        | 5.58%   |
| 2560x1600         | 6         | 2.79%   |
| 3840x2160 (4K)    | 4         | 1.86%   |
| 1920x1200 (WUXGA) | 3         | 1.4%    |
| 1024x600          | 3         | 1.4%    |
| 800x1280          | 2         | 0.93%   |
| 2560x1440 (QHD)   | 2         | 0.93%   |
| 1440x900 (WXGA+)  | 2         | 0.93%   |
| 3440x1440         | 1         | 0.47%   |
| 2880x1800         | 1         | 0.47%   |
| 1280x1024 (SXGA)  | 1         | 0.47%   |
| 1024x768 (XGA)    | 1         | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 91        | 39.91%  |
| 13     | 39        | 17.11%  |
| 14     | 28        | 12.28%  |
| 19     | 9         | 3.95%   |
| 11     | 9         | 3.95%   |
| 18     | 8         | 3.51%   |
| 17     | 8         | 3.51%   |
| 21     | 7         | 3.07%   |
| 12     | 6         | 2.63%   |
| 16     | 4         | 1.75%   |
| 31     | 3         | 1.32%   |
| 23     | 3         | 1.32%   |
| 10     | 3         | 1.32%   |
| 54     | 2         | 0.88%   |
| 27     | 2         | 0.88%   |
| 7      | 2         | 0.88%   |
| 72     | 1         | 0.44%   |
| 40     | 1         | 0.44%   |
| 34     | 1         | 0.44%   |
| 24     | 1         | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 147       | 65.33%  |
| 201-300     | 32        | 14.22%  |
| 401-500     | 22        | 9.78%   |
| 351-400     | 8         | 3.56%   |
| 501-600     | 5         | 2.22%   |
| 601-700     | 4         | 1.78%   |
| 1001-1500   | 2         | 0.89%   |
| 1-100       | 2         | 0.89%   |
| 801-900     | 1         | 0.44%   |
| 701-800     | 1         | 0.44%   |
| 1501-2000   | 1         | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 165       | 84.18%  |
| 16/10 | 25        | 12.76%  |
| 0.67  | 2         | 1.02%   |
| 5/4   | 1         | 0.51%   |
| 4/3   | 1         | 0.51%   |
| 3/2   | 1         | 0.51%   |
| 21/9  | 1         | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 90        | 39.47%  |
| 81-90          | 58        | 25.44%  |
| 151-200        | 11        | 4.82%   |
| 71-80          | 9         | 3.95%   |
| 51-60          | 9         | 3.95%   |
| 201-250        | 9         | 3.95%   |
| 141-150        | 9         | 3.95%   |
| 61-70          | 6         | 2.63%   |
| 121-130        | 6         | 2.63%   |
| 351-500        | 4         | 1.75%   |
| 111-120        | 4         | 1.75%   |
| More than 1000 | 3         | 1.32%   |
| 41-50          | 3         | 1.32%   |
| 1-40           | 2         | 0.88%   |
| 301-350        | 2         | 0.88%   |
| 131-140        | 1         | 0.44%   |
| 501-1000       | 1         | 0.44%   |
| 91-100         | 1         | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 100       | 45.05%  |
| 121-160       | 72        | 32.43%  |
| 51-100        | 32        | 14.41%  |
| 161-240       | 13        | 5.86%   |
| 1-50          | 4         | 1.8%    |
| More than 240 | 1         | 0.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 161       | 80.1%   |
| 2     | 35        | 17.41%  |
| 0     | 4         | 1.99%   |
| 3     | 1         | 0.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 123       | 39.17%  |
| Intel                           | 67        | 21.34%  |
| Qualcomm Atheros                | 59        | 18.79%  |
| Broadcom                        | 28        | 8.92%   |
| MediaTek                        | 6         | 1.91%   |
| Ralink                          | 5         | 1.59%   |
| Marvell Technology Group        | 5         | 1.59%   |
| Broadcom Limited                | 4         | 1.27%   |
| ASIX Electronics                | 4         | 1.27%   |
| TP-Link                         | 3         | 0.96%   |
| Xiaomi                          | 2         | 0.64%   |
| Samsung Electronics             | 2         | 0.64%   |
| Ralink Technology               | 1         | 0.32%   |
| Qualcomm Atheros Communications | 1         | 0.32%   |
| OPPO Electronics                | 1         | 0.32%   |
| Nvidia                          | 1         | 0.32%   |
| NetGear                         | 1         | 0.32%   |
| Hewlett-Packard                 | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 63        | 16.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 36        | 9.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 4.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 3.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 3.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 2.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 2.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 2.14%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 1.88%   |
| Intel Wireless 8265 / 8275                                              | 6         | 1.61%   |
| Intel Wireless 3160                                                     | 6         | 1.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.61%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 1.07%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 4         | 1.07%   |
| Intel Wireless 7265                                                     | 4         | 1.07%   |
| Intel Wireless 7260                                                     | 4         | 1.07%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.07%   |
| ASIX AX88179 Gigabit Ethernet                                           | 4         | 1.07%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.8%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 0.8%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.8%    |
| Intel Wi-Fi 6 AX200                                                     | 3         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 0.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 3         | 0.8%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 3         | 0.8%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 3         | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.54%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.54%   |
| Realtek Killer E3000 2.5GbE Controller                                  | 2         | 0.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 2         | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 2         | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 66        | 32.35%  |
| Qualcomm Atheros                | 52        | 25.49%  |
| Realtek Semiconductor           | 45        | 22.06%  |
| Broadcom                        | 23        | 11.27%  |
| MediaTek                        | 6         | 2.94%   |
| Ralink                          | 5         | 2.45%   |
| TP-Link                         | 2         | 0.98%   |
| Broadcom Limited                | 2         | 0.98%   |
| Ralink Technology               | 1         | 0.49%   |
| Qualcomm Atheros Communications | 1         | 0.49%   |
| NetGear                         | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 7.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 6.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 5.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 4.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 3.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 3.88%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 3.4%    |
| Intel Wireless 8265 / 8275                                              | 6         | 2.91%   |
| Intel Wireless 3160                                                     | 6         | 2.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 2.91%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2.43%   |
| Intel Wireless 7265                                                     | 4         | 1.94%   |
| Intel Wireless 7260                                                     | 4         | 1.94%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.46%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 1.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.46%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 1.46%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.46%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 3         | 1.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.97%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.97%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.97%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 2         | 0.97%   |
| Intel Wireless 8260                                                     | 2         | 0.97%   |
| Intel WiFi Link 5100                                                    | 2         | 0.97%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 2         | 0.97%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.97%   |
| Intel Centrino Wireless-N 2200                                          | 2         | 0.97%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.97%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.97%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 0.97%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 109       | 67.28%  |
| Qualcomm Atheros         | 13        | 8.02%   |
| Broadcom                 | 12        | 7.41%   |
| Intel                    | 11        | 6.79%   |
| Marvell Technology Group | 5         | 3.09%   |
| ASIX Electronics         | 4         | 2.47%   |
| Xiaomi                   | 2         | 1.23%   |
| Broadcom Limited         | 2         | 1.23%   |
| TP-Link                  | 1         | 0.62%   |
| Samsung Electronics      | 1         | 0.62%   |
| OPPO Electronics         | 1         | 0.62%   |
| Nvidia                   | 1         | 0.62%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 63        | 38.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 36        | 21.95%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 2.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 2.44%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 1.83%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 3         | 1.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 1.22%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 1.22%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 1.22%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 1.22%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 1.22%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 1.22%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 1.22%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.22%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 1.22%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.61%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.61%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.61%   |
| OPPO SM8350-MTP _SN:9338D66C                                           | 1         | 0.61%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.61%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 0.61%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 0.61%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                  | 1         | 0.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.61%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 1         | 0.61%   |
| Intel WiMAX Connection 2400m                                           | 1         | 0.61%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 0.61%   |
| Intel Ethernet Connection (17) I219-V                                  | 1         | 0.61%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 0.61%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 0.61%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 0.61%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 0.61%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 0.61%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 1         | 0.61%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 196       | 54.9%   |
| Ethernet | 158       | 44.26%  |
| Modem    | 3         | 0.84%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 153       | 73.21%  |
| Ethernet | 56        | 26.79%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 145       | 73.6%   |
| 1     | 51        | 25.89%  |
| 0     | 1         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 164       | 82.41%  |
| Yes  | 35        | 17.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 30.97%  |
| Realtek Semiconductor           | 26        | 16.77%  |
| Qualcomm Atheros Communications | 25        | 16.13%  |
| Lite-On Technology              | 9         | 5.81%   |
| IMC Networks                    | 9         | 5.81%   |
| Foxconn / Hon Hai               | 8         | 5.16%   |
| Broadcom                        | 8         | 5.16%   |
| Apple                           | 7         | 4.52%   |
| Toshiba                         | 3         | 1.94%   |
| Cambridge Silicon Radio         | 3         | 1.94%   |
| Ralink Technology               | 2         | 1.29%   |
| Ralink                          | 2         | 1.29%   |
| Realtek                         | 1         | 0.65%   |
| Hewlett-Packard                 | 1         | 0.65%   |
| Foxconn International           | 1         | 0.65%   |
| Dell                            | 1         | 0.65%   |
| Alps Electric                   | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                  | 17        | 10.97%  |
| Intel Bluetooth wireless interface                  | 16        | 10.32%  |
| Realtek  Bluetooth 4.2 Adapter                      | 12        | 7.74%   |
| Realtek Bluetooth Radio                             | 11        | 7.1%    |
| Intel Bluetooth Device                              | 8         | 5.16%   |
| Intel AX201 Bluetooth                               | 8         | 5.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 3.87%   |
| IMC Networks Bluetooth Radio                        | 6         | 3.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 2.58%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 2.58%   |
| Toshiba Bluetooth Device                            | 3         | 1.94%   |
| Lite-On Wireless_Device                             | 3         | 1.94%   |
| Lite-On Bluetooth Device                            | 3         | 1.94%   |
| Intel AX200 Bluetooth                               | 3         | 1.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.94%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.94%   |
| Apple Bluetooth Host Controller                     | 3         | 1.94%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 1.29%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.29%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.29%   |
| Lite-On Bluetooth Radio                             | 2         | 1.29%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.29%   |
| Intel AX211 Bluetooth                               | 2         | 1.29%   |
| IMC Networks Wireless_Device                        | 2         | 1.29%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 1.29%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.29%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.65%   |
| Realtek Bluetooth Radio                             | 1         | 0.65%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.65%   |
| Ralink CSR BS8510                                   | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.65%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.65%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.65%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.65%   |
| IMC Networks BCM20702A0                             | 1         | 0.65%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.65%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.65%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 150       | 67.26%  |
| AMD                 | 47        | 21.08%  |
| Nvidia              | 20        | 8.97%   |
| Sony                | 1         | 0.45%   |
| GN Netcom           | 1         | 0.45%   |
| Focusrite-Novation  | 1         | 0.45%   |
| C-Media Electronics | 1         | 0.45%   |
| Audient             | 1         | 0.45%   |
| Apple               | 1         | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 25        | 8.65%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 23        | 7.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 6.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 13        | 4.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 3.81%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 3.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 10        | 3.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 3.11%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 3.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 3.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 2.77%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 2.77%   |
| AMD High Definition Audio Controller                                                              | 8         | 2.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 2.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 2.42%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 2.42%   |
| AMD FCH Azalia Controller                                                                         | 7         | 2.42%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.73%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.73%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 1.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.38%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 1.38%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 1.04%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 3         | 1.04%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.04%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.04%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 3         | 1.04%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.69%   |
| Nvidia Audio device                                                                               | 2         | 0.69%   |
| Intel USB PnP Sound Device                                                                        | 2         | 0.69%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.69%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.69%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 46        | 31.94%  |
| SK hynix            | 32        | 22.22%  |
| Micron Technology   | 16        | 11.11%  |
| Kingston            | 15        | 10.42%  |
| Unknown             | 6         | 4.17%   |
| Ramaxel Technology  | 6         | 4.17%   |
| A-DATA Technology   | 6         | 4.17%   |
| Crucial             | 4         | 2.78%   |
| Nanya Technology    | 3         | 2.08%   |
| Unknown (ABCD)      | 2         | 1.39%   |
| Avant               | 2         | 1.39%   |
| Team                | 1         | 0.69%   |
| Hikvision           | 1         | 0.69%   |
| GOODRAM             | 1         | 0.69%   |
| Elpida              | 1         | 0.69%   |
| Corsair             | 1         | 0.69%   |
| Unknown             | 1         | 0.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 3.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 2.61%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.96%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.96%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.96%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.31%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.31%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.31%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 1.31%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.31%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.31%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 1.31%   |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.31%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.31%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s          | 2         | 1.31%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 1.31%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 1.31%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s          | 2         | 1.31%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 1.31%   |
| Kingston RAM 9905744-077.A00G 16GB SODIMM DDR4 3200MT/s          | 2         | 1.31%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 1         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.65%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 0.65%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 0.65%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.65%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.65%   |
| Unknown RAM Module 1024MB SODIMM 800MT/s                         | 1         | 0.65%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 8400MT/s             | 1         | 0.65%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.65%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.65%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 1         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 62        | 55.36%  |
| DDR3    | 31        | 27.68%  |
| LPDDR4  | 6         | 5.36%   |
| DDR2    | 4         | 3.57%   |
| LPDDR3  | 3         | 2.68%   |
| SDRAM   | 2         | 1.79%   |
| DDR5    | 2         | 1.79%   |
| DDR     | 1         | 0.89%   |
| Unknown | 1         | 0.89%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 102       | 91.07%  |
| Row Of Chips | 9         | 8.04%   |
| Unknown      | 1         | 0.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 46        | 36.22%  |
| 4096  | 46        | 36.22%  |
| 16384 | 19        | 14.96%  |
| 2048  | 9         | 7.09%   |
| 1024  | 5         | 3.94%   |
| 32768 | 2         | 1.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 38        | 29.69%  |
| 1600    | 28        | 21.88%  |
| 3200    | 18        | 14.06%  |
| 2400    | 9         | 7.03%   |
| 3266    | 6         | 4.69%   |
| 1334    | 5         | 3.91%   |
| 2133    | 3         | 2.34%   |
| 4199    | 2         | 1.56%   |
| 1867    | 2         | 1.56%   |
| 667     | 2         | 1.56%   |
| Unknown | 2         | 1.56%   |
| 8400    | 1         | 0.78%   |
| 5600    | 1         | 0.78%   |
| 4800    | 1         | 0.78%   |
| 4267    | 1         | 0.78%   |
| 3733    | 1         | 0.78%   |
| 1776    | 1         | 0.78%   |
| 1333    | 1         | 0.78%   |
| 1067    | 1         | 0.78%   |
| 1066    | 1         | 0.78%   |
| 975     | 1         | 0.78%   |
| 933     | 1         | 0.78%   |
| 800     | 1         | 0.78%   |
| 533     | 1         | 0.78%   |

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
| Chicony Electronics                    | 46        | 26.29%  |
| IMC Networks                           | 22        | 12.57%  |
| Microdia                               | 13        | 7.43%   |
| Realtek Semiconductor                  | 12        | 6.86%   |
| Quanta                                 | 12        | 6.86%   |
| Suyin                                  | 8         | 4.57%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 4.57%   |
| Syntek                                 | 7         | 4%      |
| Sunplus Innovation Technology          | 7         | 4%      |
| Bison Electronics                      | 6         | 3.43%   |
| Lite-On Technology                     | 5         | 2.86%   |
| Apple                                  | 5         | 2.86%   |
| Silicon Motion                         | 3         | 1.71%   |
| Ricoh                                  | 3         | 1.71%   |
| Luxvisions Innotech Limited            | 3         | 1.71%   |
| OmniVision Technologies                | 2         | 1.14%   |
| Alcor Micro                            | 2         | 1.14%   |
| Z-Star Microelectronics                | 1         | 0.57%   |
| Trust                                  | 1         | 0.57%   |
| Sonix Technology                       | 1         | 0.57%   |
| ShineTech                              | 1         | 0.57%   |
| Samsung Electronics                    | 1         | 0.57%   |
| Lenovo                                 | 1         | 0.57%   |
| Importek                               | 1         | 0.57%   |
| icSpring                               | 1         | 0.57%   |
| Generalplus Technology                 | 1         | 0.57%   |
| Foxconn / Hon Hai                      | 1         | 0.57%   |
| ALi                                    | 1         | 0.57%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 9         | 5.14%   |
| Chicony Integrated Camera                                      | 7         | 4%      |
| IMC Networks USB2.0 HD UVC WebCam                              | 6         | 3.43%   |
| Chicony HP Truevision HD                                       | 6         | 3.43%   |
| IMC Networks Integrated Camera                                 | 5         | 2.86%   |
| Chicony TOSHIBA Web Camera - HD                                | 5         | 2.86%   |
| Realtek Integrated_Webcam_HD                                   | 4         | 2.29%   |
| IMC Networks VGA UVC WebCam                                    | 3         | 1.71%   |
| IMC Networks TOSHIBA Web Camera - HD                           | 3         | 1.71%   |
| Chicony HD User Facing                                         | 3         | 1.71%   |
| Syntek Lenovo EasyCamera                                       | 2         | 1.14%   |
| Syntek Integrated Camera                                       | 2         | 1.14%   |
| Syntek EasyCamera                                              | 2         | 1.14%   |
| Suyin Integrated_Webcam_HD                                     | 2         | 1.14%   |
| Suyin HP Truevision HD                                         | 2         | 1.14%   |
| Suyin HD WebCam                                                | 2         | 1.14%   |
| Sunplus Integrated_Webcam_HD                                   | 2         | 1.14%   |
| Realtek Integrated Webcam                                      | 2         | 1.14%   |
| Realtek HP "Truevision HD" laptop camera                       | 2         | 1.14%   |
| Quanta HP Wide Vision HD Camera                                | 2         | 1.14%   |
| Quanta HP Webcam-50                                            | 2         | 1.14%   |
| Quanta HP Webcam                                               | 2         | 1.14%   |
| OmniVision OV2640 Webcam                                       | 2         | 1.14%   |
| Microdia USB 2.0 Camera                                        | 2         | 1.14%   |
| Lite-On TOSHIBA Web Camera - HD                                | 2         | 1.14%   |
| Lite-On HP TrueVision HD Camera                                | 2         | 1.14%   |
| Chicony Integrated Camera (1280x720@30)                        | 2         | 1.14%   |
| Chicony HP Wide Vision HD Camera                               | 2         | 1.14%   |
| Chicony HP TrueVision HD Camera                                | 2         | 1.14%   |
| Chicony HP HD Webcam [Fixed]                                   | 2         | 1.14%   |
| Chicony EasyCamera                                             | 2         | 1.14%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1.14%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD        | 2         | 1.14%   |
| Bison Integrated Camera                                        | 2         | 1.14%   |
| Apple FaceTime HD Camera                                       | 2         | 1.14%   |
| Z-Star WebCam SCB-0320N                                        | 1         | 0.57%   |
| Trust USB Camera                                               | 1         | 0.57%   |
| Syntek USB Video Device                                        | 1         | 0.57%   |
| Suyin HP TrueVision HD Integrated Webcam                       | 1         | 0.57%   |
| Suyin Asus Integrated Webcam                                   | 1         | 0.57%   |

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
| 0     | 139       | 70.2%   |
| 1     | 51        | 25.76%  |
| 2     | 7         | 3.54%   |
| 5     | 1         | 0.51%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 16        | 22.86%  |
| Graphics card            | 14        | 20%     |
| Net/wireless             | 13        | 18.57%  |
| Multimedia controller    | 7         | 10%     |
| Chipcard                 | 6         | 8.57%   |
| Camera                   | 3         | 4.29%   |
| Bluetooth                | 3         | 4.29%   |
| Storage                  | 2         | 2.86%   |
| Sound                    | 2         | 2.86%   |
| Communication controller | 2         | 2.86%   |
| Network                  | 1         | 1.43%   |
| Net/ethernet             | 1         | 1.43%   |

