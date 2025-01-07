openSUSE Leap-15.5 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.5.

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

Total: 246

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Gaming FX505GT_FX505... | [4690fd028c](https://linux-hardware.org/?probe=4690fd028c) | Jan 01, 2025 |
| ASUSTek       | X751SA                      | [11d8d9b891](https://linux-hardware.org/?probe=11d8d9b891) | Dec 30, 2024 |
| ASUSTek       | X751SA                      | [2f216406f5](https://linux-hardware.org/?probe=2f216406f5) | Dec 28, 2024 |
| Dell          | Latitude 7400               | [79148dd5e2](https://linux-hardware.org/?probe=79148dd5e2) | Dec 14, 2024 |
| Dell          | Latitude 7400               | [77befeb4ea](https://linux-hardware.org/?probe=77befeb4ea) | Dec 09, 2024 |
| Dell          | XPS 13 9310                 | [cf504cfd50](https://linux-hardware.org/?probe=cf504cfd50) | Dec 05, 2024 |
| HP            | EliteBook 840 G1            | [775a4e3d49](https://linux-hardware.org/?probe=775a4e3d49) | Nov 17, 2024 |
| HP            | EliteBook 840 G1            | [cd9cf7bf34](https://linux-hardware.org/?probe=cd9cf7bf34) | Nov 17, 2024 |
| Medion        | E15433                      | [05ec29cd01](https://linux-hardware.org/?probe=05ec29cd01) | Nov 11, 2024 |
| Toshiba       | Satellite C55D-A            | [aa4ba3a227](https://linux-hardware.org/?probe=aa4ba3a227) | Nov 04, 2024 |
| Lenovo        | ThinkPad W520 4282A34       | [9c2a644e93](https://linux-hardware.org/?probe=9c2a644e93) | Nov 01, 2024 |
| Google        | Candy                       | [2ee49236e0](https://linux-hardware.org/?probe=2ee49236e0) | Oct 23, 2024 |
| Lenovo        | ThinkPad T490 20N2000LSP    | [34c10e27fb](https://linux-hardware.org/?probe=34c10e27fb) | Oct 03, 2024 |
| Google        | Candy                       | [1fd06c93d2](https://linux-hardware.org/?probe=1fd06c93d2) | Sep 26, 2024 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [26254c11a6](https://linux-hardware.org/?probe=26254c11a6) | Sep 18, 2024 |
| Sony          | VPCEH11FX                   | [76b181ca5c](https://linux-hardware.org/?probe=76b181ca5c) | Sep 03, 2024 |
| ASUSTek       | GL553VD                     | [bdaf9d87ea](https://linux-hardware.org/?probe=bdaf9d87ea) | Sep 01, 2024 |
| Acer          | Nitro AN517-51              | [33ffbac3ac](https://linux-hardware.org/?probe=33ffbac3ac) | Aug 29, 2024 |
| Dell          | Precision 3541              | [1c2a5e45f3](https://linux-hardware.org/?probe=1c2a5e45f3) | Aug 21, 2024 |
| Toshiba       | Satellite R945              | [4e4ca76ccf](https://linux-hardware.org/?probe=4e4ca76ccf) | Aug 19, 2024 |
| Dell          | Precision 3541              | [c5f2dba49c](https://linux-hardware.org/?probe=c5f2dba49c) | Aug 13, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [c670222db7](https://linux-hardware.org/?probe=c670222db7) | Aug 12, 2024 |
| Panasonic     | FZ40-1                      | [a8cf31fa9e](https://linux-hardware.org/?probe=a8cf31fa9e) | Aug 05, 2024 |
| Dell          | Latitude 7400               | [830e4194f2](https://linux-hardware.org/?probe=830e4194f2) | Aug 02, 2024 |
| Fujitsu       | LIFEBOOK E756               | [83394cc331](https://linux-hardware.org/?probe=83394cc331) | Jul 24, 2024 |
| Dell          | Latitude 5320               | [937747e0cd](https://linux-hardware.org/?probe=937747e0cd) | Jul 24, 2024 |
| HP            | EliteBook 850 G7 Noteboo... | [d32f73f43c](https://linux-hardware.org/?probe=d32f73f43c) | Jul 24, 2024 |
| Dell          | Latitude E6510              | [7bdf8e1d08](https://linux-hardware.org/?probe=7bdf8e1d08) | Jul 18, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [5e5b324a08](https://linux-hardware.org/?probe=5e5b324a08) | Jun 27, 2024 |
| Acer          | Aspire E1-571               | [554884bafe](https://linux-hardware.org/?probe=554884bafe) | Jun 23, 2024 |
| HP            | ENVY 14                     | [c0be266fe2](https://linux-hardware.org/?probe=c0be266fe2) | Jun 18, 2024 |
| HP            | ENVY 14                     | [0838fecf0e](https://linux-hardware.org/?probe=0838fecf0e) | Jun 18, 2024 |
| HP            | ENVY Laptop 17-ae1xx        | [e3e68fbf69](https://linux-hardware.org/?probe=e3e68fbf69) | Jun 15, 2024 |
| Wortmann      | TERRA_MOBILE_1512/1712      | [925af4ca04](https://linux-hardware.org/?probe=925af4ca04) | Jun 11, 2024 |
| Wortmann      | TERRA_MOBILE_1512/1712      | [b80c7ef54c](https://linux-hardware.org/?probe=b80c7ef54c) | Jun 11, 2024 |
| HP            | Victus by Laptop 16-e0xx... | [c9b9a5f54b](https://linux-hardware.org/?probe=c9b9a5f54b) | Jun 10, 2024 |
| HP            | Victus by Gaming Laptop ... | [39216d7b67](https://linux-hardware.org/?probe=39216d7b67) | Jun 06, 2024 |
| HP            | Victus by Gaming Laptop ... | [bd8df104f0](https://linux-hardware.org/?probe=bd8df104f0) | Jun 06, 2024 |
| LG Electro... | P1-J331P                    | [a24862e047](https://linux-hardware.org/?probe=a24862e047) | Jun 02, 2024 |
| LG Electro... | P1-J331P                    | [948cbb9a59](https://linux-hardware.org/?probe=948cbb9a59) | Jun 02, 2024 |
| Digibras      | NH4CU03                     | [ed38e31a5a](https://linux-hardware.org/?probe=ed38e31a5a) | May 31, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [ce453ef020](https://linux-hardware.org/?probe=ce453ef020) | May 30, 2024 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | [54446d7877](https://linux-hardware.org/?probe=54446d7877) | May 28, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [14a14a76f1](https://linux-hardware.org/?probe=14a14a76f1) | May 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [aa9d0999c0](https://linux-hardware.org/?probe=aa9d0999c0) | May 26, 2024 |
| Dell          | Precision 7510              | [2732302a98](https://linux-hardware.org/?probe=2732302a98) | May 23, 2024 |
| Dell          | Precision 7510              | [f1f16c7457](https://linux-hardware.org/?probe=f1f16c7457) | May 23, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [a2e639d9d5](https://linux-hardware.org/?probe=a2e639d9d5) | May 23, 2024 |
| ILLEGEAR      | RAVEN SE                    | [faac458723](https://linux-hardware.org/?probe=faac458723) | May 15, 2024 |
| ILLEGEAR      | RAVEN SE                    | [97f3382524](https://linux-hardware.org/?probe=97f3382524) | May 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [fce74afc84](https://linux-hardware.org/?probe=fce74afc84) | May 09, 2024 |
| Lenovo        | B590 20206                  | [9c08740bb5](https://linux-hardware.org/?probe=9c08740bb5) | May 02, 2024 |
| Dell          | Inspiron 5559               | [8a00241444](https://linux-hardware.org/?probe=8a00241444) | May 01, 2024 |
| Medion        | P662X                       | [3689ca2476](https://linux-hardware.org/?probe=3689ca2476) | May 01, 2024 |
| Wortmann      | TERRA_MOBILE_1749           | [cdfcbe795b](https://linux-hardware.org/?probe=cdfcbe795b) | May 01, 2024 |
| Dell          | Inspiron 5748               | [43d176db3e](https://linux-hardware.org/?probe=43d176db3e) | Apr 29, 2024 |
| Acer          | Aspire 7741                 | [69f109864f](https://linux-hardware.org/?probe=69f109864f) | Apr 28, 2024 |
| Lenovo        | ThinkPad L520 786035U       | [711272241a](https://linux-hardware.org/?probe=711272241a) | Apr 28, 2024 |
| ASUSTek       | N751JK                      | [1d2d8c3d7a](https://linux-hardware.org/?probe=1d2d8c3d7a) | Apr 25, 2024 |
| Lenovo        | U31-70 80M5                 | [2a4ad09169](https://linux-hardware.org/?probe=2a4ad09169) | Apr 25, 2024 |
| Lenovo        | G510 20238                  | [ec99c46757](https://linux-hardware.org/?probe=ec99c46757) | Apr 25, 2024 |
| Acer          | Aspire 5750G                | [a35bd4ad42](https://linux-hardware.org/?probe=a35bd4ad42) | Apr 23, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [8b5161f4ab](https://linux-hardware.org/?probe=8b5161f4ab) | Apr 22, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [8cff3fe858](https://linux-hardware.org/?probe=8cff3fe858) | Apr 20, 2024 |
| ASUSTek       | N751JK                      | [39bb3da888](https://linux-hardware.org/?probe=39bb3da888) | Apr 16, 2024 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [b29f521f01](https://linux-hardware.org/?probe=b29f521f01) | Apr 12, 2024 |
| HP            | EliteBook 2730p             | [843cd11924](https://linux-hardware.org/?probe=843cd11924) | Apr 10, 2024 |
| Fujitsu       | CELSIUS H780                | [f5dc0c7623](https://linux-hardware.org/?probe=f5dc0c7623) | Apr 10, 2024 |
| Dell          | Precision M4800             | [e0cd62ded2](https://linux-hardware.org/?probe=e0cd62ded2) | Apr 10, 2024 |
| HP            | Victus by Gaming Laptop ... | [75b15c6330](https://linux-hardware.org/?probe=75b15c6330) | Apr 09, 2024 |
| Dell          | Precision 3561              | [6bc6a2a9d9](https://linux-hardware.org/?probe=6bc6a2a9d9) | Apr 09, 2024 |
| Dell          | Latitude E7240              | [08dd3e8b44](https://linux-hardware.org/?probe=08dd3e8b44) | Apr 09, 2024 |
| MSI           | Summit E13FlipEvo A11MT     | [3c1bd6247c](https://linux-hardware.org/?probe=3c1bd6247c) | Apr 06, 2024 |
| HP            | Laptop 15-dw3xxx            | [e009d9dd56](https://linux-hardware.org/?probe=e009d9dd56) | Apr 05, 2024 |
| HP            | Laptop 17-cp0xxx            | [05643228c4](https://linux-hardware.org/?probe=05643228c4) | Apr 02, 2024 |
| Dell          | Vostro 3520                 | [233178d530](https://linux-hardware.org/?probe=233178d530) | Mar 25, 2024 |
| Lenovo        | B590 20206                  | [d3e9088b43](https://linux-hardware.org/?probe=d3e9088b43) | Mar 23, 2024 |
| Lenovo        | B590 20206                  | [36c66318b0](https://linux-hardware.org/?probe=36c66318b0) | Mar 22, 2024 |
| Dell          | Precision 5520              | [8d942977e2](https://linux-hardware.org/?probe=8d942977e2) | Mar 20, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [153f16ac8d](https://linux-hardware.org/?probe=153f16ac8d) | Mar 18, 2024 |
| Acer          | Aspire 5745                 | [512b58fc90](https://linux-hardware.org/?probe=512b58fc90) | Mar 16, 2024 |
| Apple         | MacBookPro9,2               | [174ace72e6](https://linux-hardware.org/?probe=174ace72e6) | Mar 15, 2024 |
| Schenker      | KEY (E23)                   | [f555bec75a](https://linux-hardware.org/?probe=f555bec75a) | Mar 12, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | [1e7f921f12](https://linux-hardware.org/?probe=1e7f921f12) | Mar 12, 2024 |
| Acer          | TravelMate P215-54          | [a8e5c041ef](https://linux-hardware.org/?probe=a8e5c041ef) | Mar 11, 2024 |
| HP            | EliteBook 8570w             | [4b83d77529](https://linux-hardware.org/?probe=4b83d77529) | Mar 10, 2024 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [66f2f3a361](https://linux-hardware.org/?probe=66f2f3a361) | Mar 04, 2024 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [3ab9b49b3e](https://linux-hardware.org/?probe=3ab9b49b3e) | Mar 04, 2024 |
| MSI           | Katana GF66 11UE            | [95b3dd2821](https://linux-hardware.org/?probe=95b3dd2821) | Mar 03, 2024 |
| Acer          | Aspire 5742Z                | [22ba0ca014](https://linux-hardware.org/?probe=22ba0ca014) | Feb 29, 2024 |
| HP            | Pavilion dv9500             | [233bd911e6](https://linux-hardware.org/?probe=233bd911e6) | Feb 28, 2024 |
| Lenovo        | ThinkPad L530 24814YG       | [41599a23c0](https://linux-hardware.org/?probe=41599a23c0) | Feb 28, 2024 |
| HP            | Pavilion dv9500             | [8c5ec97398](https://linux-hardware.org/?probe=8c5ec97398) | Feb 27, 2024 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [cded833645](https://linux-hardware.org/?probe=cded833645) | Feb 25, 2024 |
| HP            | Laptop 17-cp0xxx            | [85f840ba85](https://linux-hardware.org/?probe=85f840ba85) | Feb 24, 2024 |
| ASUSTek       | X751LX                      | [702ddba05b](https://linux-hardware.org/?probe=702ddba05b) | Feb 24, 2024 |
| HP            | Laptop 17z-ca200            | [1dbf9d63d5](https://linux-hardware.org/?probe=1dbf9d63d5) | Feb 21, 2024 |
| Acer          | Aspire A315-51              | [3e89cd8ab4](https://linux-hardware.org/?probe=3e89cd8ab4) | Feb 19, 2024 |
| HP            | EliteBook 8560p             | [748b126968](https://linux-hardware.org/?probe=748b126968) | Feb 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [d916f30fdc](https://linux-hardware.org/?probe=d916f30fdc) | Feb 10, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [f4930d0549](https://linux-hardware.org/?probe=f4930d0549) | Feb 09, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [c8567d0dcc](https://linux-hardware.org/?probe=c8567d0dcc) | Feb 06, 2024 |
| HP            | EliteBook 8460p             | [91197e4fa0](https://linux-hardware.org/?probe=91197e4fa0) | Feb 05, 2024 |
| Acer          | Aspire A317-32              | [9baf9646df](https://linux-hardware.org/?probe=9baf9646df) | Jan 27, 2024 |
| Lenovo        | ThinkPad E14 20RAS1S600     | [8544584b30](https://linux-hardware.org/?probe=8544584b30) | Jan 27, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [6dd363b754](https://linux-hardware.org/?probe=6dd363b754) | Jan 22, 2024 |
| Dell          | Latitude E6400              | [b2765b0e50](https://linux-hardware.org/?probe=b2765b0e50) | Jan 19, 2024 |
| TUXEDO        | Aura 15 Gen2                | [28a227c7d1](https://linux-hardware.org/?probe=28a227c7d1) | Jan 16, 2024 |
| TUXEDO        | Pulse 15 Gen2               | [1ec6103b31](https://linux-hardware.org/?probe=1ec6103b31) | Jan 16, 2024 |
| TUXEDO        | Aura 15 Gen2                | [96e3e7f937](https://linux-hardware.org/?probe=96e3e7f937) | Jan 16, 2024 |
| HP            | Laptop 15-dy2xxx            | [4dc1a2b98c](https://linux-hardware.org/?probe=4dc1a2b98c) | Jan 11, 2024 |
| HP            | EliteBook 2540p             | [088dbf4c2f](https://linux-hardware.org/?probe=088dbf4c2f) | Jan 10, 2024 |
| A-DATA Tec... | XENIA 15                    | [6cf5d66e62](https://linux-hardware.org/?probe=6cf5d66e62) | Jan 10, 2024 |
| Lenovo        | ThinkPad T530 2394W19       | [0dff2ac4a3](https://linux-hardware.org/?probe=0dff2ac4a3) | Jan 10, 2024 |
| HP            | Laptop 15s-eq2xxx           | [2e0223d4eb](https://linux-hardware.org/?probe=2e0223d4eb) | Jan 09, 2024 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [a304de1339](https://linux-hardware.org/?probe=a304de1339) | Jan 06, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [e340939ad8](https://linux-hardware.org/?probe=e340939ad8) | Jan 06, 2024 |
| Acer          | Aspire A317-32              | [806a8b59fb](https://linux-hardware.org/?probe=806a8b59fb) | Jan 05, 2024 |
| ASUSTek       | UX510UXK                    | [17be26f2de](https://linux-hardware.org/?probe=17be26f2de) | Jan 04, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [1504d9c050](https://linux-hardware.org/?probe=1504d9c050) | Jan 03, 2024 |
| Dell          | Inspiron 3443               | [0c56a0465b](https://linux-hardware.org/?probe=0c56a0465b) | Dec 29, 2023 |
| HP            | EliteBook 8560p             | [16a5247446](https://linux-hardware.org/?probe=16a5247446) | Dec 28, 2023 |
| HP            | EliteBook 8560p             | [82f94ea967](https://linux-hardware.org/?probe=82f94ea967) | Dec 28, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [87e63ff33e](https://linux-hardware.org/?probe=87e63ff33e) | Dec 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [626b056720](https://linux-hardware.org/?probe=626b056720) | Dec 27, 2023 |
| Dell          | System XPS L322X            | [6b050ff1c8](https://linux-hardware.org/?probe=6b050ff1c8) | Dec 23, 2023 |
| Acer          | TravelMate P215-41-G2       | [476ef9075c](https://linux-hardware.org/?probe=476ef9075c) | Dec 21, 2023 |
| Dell          | XPS 15 7590                 | [7e2afccdd6](https://linux-hardware.org/?probe=7e2afccdd6) | Dec 18, 2023 |
| System76      | Bonobo WS                   | [22f5ef6fce](https://linux-hardware.org/?probe=22f5ef6fce) | Dec 16, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [b949261978](https://linux-hardware.org/?probe=b949261978) | Dec 13, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | [e8383035b9](https://linux-hardware.org/?probe=e8383035b9) | Dec 10, 2023 |
| HP            | Compaq 515                  | [025d4116ed](https://linux-hardware.org/?probe=025d4116ed) | Dec 09, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [9d717185fb](https://linux-hardware.org/?probe=9d717185fb) | Dec 07, 2023 |
| HP            | Notebook                    | [0a554c91b1](https://linux-hardware.org/?probe=0a554c91b1) | Dec 01, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [4ba2fc285f](https://linux-hardware.org/?probe=4ba2fc285f) | Nov 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [0f9a06cc9f](https://linux-hardware.org/?probe=0f9a06cc9f) | Nov 30, 2023 |
| HP            | Notebook                    | [93464a0904](https://linux-hardware.org/?probe=93464a0904) | Nov 30, 2023 |
| Acer          | Aspire A317-32              | [02b205724a](https://linux-hardware.org/?probe=02b205724a) | Nov 29, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [1eda316922](https://linux-hardware.org/?probe=1eda316922) | Nov 28, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [b46ec04a69](https://linux-hardware.org/?probe=b46ec04a69) | Nov 27, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [d3122d678f](https://linux-hardware.org/?probe=d3122d678f) | Nov 27, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [312776837c](https://linux-hardware.org/?probe=312776837c) | Nov 26, 2023 |
| Acer          | Aspire A515-45G             | [1ec9d0635f](https://linux-hardware.org/?probe=1ec9d0635f) | Nov 23, 2023 |
| System76      | Lemur Pro                   | [45a6298cb5](https://linux-hardware.org/?probe=45a6298cb5) | Nov 22, 2023 |
| Unknown       | Unknown                     | [d169a02b18](https://linux-hardware.org/?probe=d169a02b18) | Nov 14, 2023 |
| Dell          | Latitude E6410              | [1e9606e755](https://linux-hardware.org/?probe=1e9606e755) | Nov 14, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | [242621dab3](https://linux-hardware.org/?probe=242621dab3) | Nov 13, 2023 |
| Dynabook      | PORTEGE X30L-K              | [161674ce4a](https://linux-hardware.org/?probe=161674ce4a) | Nov 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | [e736653169](https://linux-hardware.org/?probe=e736653169) | Nov 08, 2023 |
| Lenovo        | ThinkPad W541 20EGS1LB00    | [7a31e185b9](https://linux-hardware.org/?probe=7a31e185b9) | Nov 07, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VZ... | [680fae0bef](https://linux-hardware.org/?probe=680fae0bef) | Nov 07, 2023 |
| Lenovo        | ThinkPad T490 20N2000LSP    | [55e3cdf0cc](https://linux-hardware.org/?probe=55e3cdf0cc) | Nov 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | [d1d65399a0](https://linux-hardware.org/?probe=d1d65399a0) | Nov 03, 2023 |
| Acer          | Aspire VN7-591G             | [f446da83f1](https://linux-hardware.org/?probe=f446da83f1) | Nov 03, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [137dba2261](https://linux-hardware.org/?probe=137dba2261) | Nov 02, 2023 |
| Dell          | Inspiron N4050              | [7d5dc09b04](https://linux-hardware.org/?probe=7d5dc09b04) | Oct 30, 2023 |
| ASUSTek       | ZenBook UX434FL             | [139d1a74ed](https://linux-hardware.org/?probe=139d1a74ed) | Oct 25, 2023 |
| HUAWEI        | KLVL-WXXW                   | [b615345fa6](https://linux-hardware.org/?probe=b615345fa6) | Oct 21, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [398445f93d](https://linux-hardware.org/?probe=398445f93d) | Oct 14, 2023 |
| HP            | ProBook 4535s               | [e52e92c95b](https://linux-hardware.org/?probe=e52e92c95b) | Oct 14, 2023 |
| Lenovo        | ThinkPad T400 27658JG       | [3b3b7832c9](https://linux-hardware.org/?probe=3b3b7832c9) | Oct 11, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | [5e8749954f](https://linux-hardware.org/?probe=5e8749954f) | Oct 11, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [814f6c5c52](https://linux-hardware.org/?probe=814f6c5c52) | Oct 09, 2023 |
| Dell          | Precision M6500             | [18605f38d4](https://linux-hardware.org/?probe=18605f38d4) | Oct 05, 2023 |
| Lenovo        | ThinkPad X390 20Q1S5K400    | [4d9d1bf62a](https://linux-hardware.org/?probe=4d9d1bf62a) | Oct 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [6fc52a277a](https://linux-hardware.org/?probe=6fc52a277a) | Sep 28, 2023 |
| ASUSTek       | X510UAR                     | [f94566dde6](https://linux-hardware.org/?probe=f94566dde6) | Sep 23, 2023 |
| HP            | ENVY 17                     | [4f6463148f](https://linux-hardware.org/?probe=4f6463148f) | Sep 22, 2023 |
| Lenovo        | ThinkPad W500 40624DG       | [9bdd448e89](https://linux-hardware.org/?probe=9bdd448e89) | Sep 22, 2023 |
| ASUSTek       | X510UAR                     | [b962cd9626](https://linux-hardware.org/?probe=b962cd9626) | Sep 19, 2023 |
| Lenovo        | B490 37722QP                | [d68a92e72a](https://linux-hardware.org/?probe=d68a92e72a) | Sep 19, 2023 |
| Lenovo        | B490 37722QP                | [8b335d6bb0](https://linux-hardware.org/?probe=8b335d6bb0) | Sep 19, 2023 |
| Acer          | Nitro AN515-57              | [8e044378bd](https://linux-hardware.org/?probe=8e044378bd) | Sep 15, 2023 |
| Acer          | Swift SF314-511             | [4714deba45](https://linux-hardware.org/?probe=4714deba45) | Sep 14, 2023 |
| Dell          | Precision 7540              | [ced1086a24](https://linux-hardware.org/?probe=ced1086a24) | Sep 09, 2023 |
| Dell          | Latitude 5431               | [b2d976a088](https://linux-hardware.org/?probe=b2d976a088) | Sep 08, 2023 |
| Panasonic     | CF-C2CUGZXKM                | [d34f211b22](https://linux-hardware.org/?probe=d34f211b22) | Sep 07, 2023 |
| Panasonic     | CF-C2CUGZXKM                | [098294fb47](https://linux-hardware.org/?probe=098294fb47) | Sep 07, 2023 |
| Sony          | SVF1521A7EB                 | [8b130feb09](https://linux-hardware.org/?probe=8b130feb09) | Sep 06, 2023 |
| Panasonic     | CF-C2CUGZXKM                | [12ed8aee3f](https://linux-hardware.org/?probe=12ed8aee3f) | Sep 05, 2023 |
| Panasonic     | CF-C2CUGZXKM                | [fdcab89946](https://linux-hardware.org/?probe=fdcab89946) | Sep 05, 2023 |
| Medion        | S15449                      | [7e8cd1a434](https://linux-hardware.org/?probe=7e8cd1a434) | Sep 02, 2023 |
| Acer          | Aspire 5715Z                | [22c3bee6fa](https://linux-hardware.org/?probe=22c3bee6fa) | Sep 02, 2023 |
| Acer          | Aspire A317-32              | [0a46c781fc](https://linux-hardware.org/?probe=0a46c781fc) | Sep 01, 2023 |
| Acer          | Predator PH315-52           | [fd3c900751](https://linux-hardware.org/?probe=fd3c900751) | Aug 31, 2023 |
| Lenovo        | ThinkPad T470p 20J60014P... | [7690eb9089](https://linux-hardware.org/?probe=7690eb9089) | Aug 30, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [704a62ef33](https://linux-hardware.org/?probe=704a62ef33) | Aug 29, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [beb1174dde](https://linux-hardware.org/?probe=beb1174dde) | Aug 29, 2023 |
| HUAWEI        | CREF-XX                     | [c5b6554c6b](https://linux-hardware.org/?probe=c5b6554c6b) | Aug 26, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [b141917712](https://linux-hardware.org/?probe=b141917712) | Aug 23, 2023 |
| Toshiba       | Satellite Pro C70-A         | [dbb00fe95b](https://linux-hardware.org/?probe=dbb00fe95b) | Aug 15, 2023 |
| Acer          | Aspire E5-571G              | [f523831970](https://linux-hardware.org/?probe=f523831970) | Aug 14, 2023 |
| HP            | EliteBook 840 G3            | [66bcc74be2](https://linux-hardware.org/?probe=66bcc74be2) | Aug 13, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [6f722400c2](https://linux-hardware.org/?probe=6f722400c2) | Aug 11, 2023 |
| Dell          | Precision 7740              | [954d8472e5](https://linux-hardware.org/?probe=954d8472e5) | Aug 09, 2023 |
| Notebook      | NLx0MU                      | [bb99f6f69e](https://linux-hardware.org/?probe=bb99f6f69e) | Aug 07, 2023 |
| Dell          | Vostro 5471                 | [f4beee823e](https://linux-hardware.org/?probe=f4beee823e) | Aug 07, 2023 |
| HP            | 470 G7 Notebook PC          | [7e4a9b4618](https://linux-hardware.org/?probe=7e4a9b4618) | Aug 04, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [8fb651def8](https://linux-hardware.org/?probe=8fb651def8) | Aug 02, 2023 |
| Sony          | Unknown                     | [80613731cb](https://linux-hardware.org/?probe=80613731cb) | Jul 28, 2023 |
| Acer          | Aspire E5-774G              | [1568ba2843](https://linux-hardware.org/?probe=1568ba2843) | Jul 25, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [b7c7b058b7](https://linux-hardware.org/?probe=b7c7b058b7) | Jul 23, 2023 |
| MSI           | Cyborg 15 A13VE             | [edf7b092ec](https://linux-hardware.org/?probe=edf7b092ec) | Jul 23, 2023 |
| MSI           | Cyborg 15 A13VE             | [421c2ff6b0](https://linux-hardware.org/?probe=421c2ff6b0) | Jul 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [c741f10f18](https://linux-hardware.org/?probe=c741f10f18) | Jul 23, 2023 |
| Medion        | E6224                       | [c33b8a1fb1](https://linux-hardware.org/?probe=c33b8a1fb1) | Jul 22, 2023 |
| Sony          | Unknown                     | [427e52d6a6](https://linux-hardware.org/?probe=427e52d6a6) | Jul 20, 2023 |
| Medion        | E6224                       | [4ffae87044](https://linux-hardware.org/?probe=4ffae87044) | Jul 17, 2023 |
| Lenovo        | B5400 80B6QB0               | [7108435241](https://linux-hardware.org/?probe=7108435241) | Jul 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [6b351b341e](https://linux-hardware.org/?probe=6b351b341e) | Jul 15, 2023 |
| Lenovo        | ThinkPad T530 2394W19       | [874f8b41a7](https://linux-hardware.org/?probe=874f8b41a7) | Jul 14, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [9bee6805c0](https://linux-hardware.org/?probe=9bee6805c0) | Jul 13, 2023 |
| Dell          | Vostro 3400                 | [93d94feca6](https://linux-hardware.org/?probe=93d94feca6) | Jul 11, 2023 |
| ASUSTek       | K53SM                       | [7aac135bc0](https://linux-hardware.org/?probe=7aac135bc0) | Jul 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [a52e535dcb](https://linux-hardware.org/?probe=a52e535dcb) | Jul 11, 2023 |
| Dell          | Latitude E5410              | [8d980136c2](https://linux-hardware.org/?probe=8d980136c2) | Jul 10, 2023 |
| Lenovo        | V15-IGL 82C3                | [9f920e8a7e](https://linux-hardware.org/?probe=9f920e8a7e) | Jul 10, 2023 |
| HP            | Notebook                    | [a1c37a6a4b](https://linux-hardware.org/?probe=a1c37a6a4b) | Jul 09, 2023 |
| Toshiba       | dynabook Satellite B552/... | [f459621198](https://linux-hardware.org/?probe=f459621198) | Jul 06, 2023 |
| Notebook      | NLx0MU                      | [b3530f3e0e](https://linux-hardware.org/?probe=b3530f3e0e) | Jul 05, 2023 |
| Acer          | Nitro AN515-58              | [40b7950cb2](https://linux-hardware.org/?probe=40b7950cb2) | Jul 05, 2023 |
| Acer          | Nitro AN515-58              | [73435e5646](https://linux-hardware.org/?probe=73435e5646) | Jul 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [27c53e1152](https://linux-hardware.org/?probe=27c53e1152) | Jul 01, 2023 |
| Lenovo        | ThinkPad T530 2394W19       | [a1fc2e0020](https://linux-hardware.org/?probe=a1fc2e0020) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [a203a588f9](https://linux-hardware.org/?probe=a203a588f9) | Jun 30, 2023 |
| Lenovo        | ThinkPad X200 7458AH8       | [a81af2d7e2](https://linux-hardware.org/?probe=a81af2d7e2) | Jun 29, 2023 |
| Acer          | Aspire A317-53              | [1fe3acdf83](https://linux-hardware.org/?probe=1fe3acdf83) | Jun 25, 2023 |
| ASUSTek       | K53TK                       | [905653d393](https://linux-hardware.org/?probe=905653d393) | Jun 24, 2023 |
| Notebook      | NLx0MU                      | [733af664a4](https://linux-hardware.org/?probe=733af664a4) | Jun 18, 2023 |
| HP            | Laptop 17-bs0xx             | [bbb32d23be](https://linux-hardware.org/?probe=bbb32d23be) | Jun 17, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [0210669ff3](https://linux-hardware.org/?probe=0210669ff3) | Jun 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [fdc4101cba](https://linux-hardware.org/?probe=fdc4101cba) | Jun 13, 2023 |
| Notebook      | NS50_70MU                   | [87b818815c](https://linux-hardware.org/?probe=87b818815c) | Jun 10, 2023 |
| Apple         | MacBookPro11,4              | [6d70667d42](https://linux-hardware.org/?probe=6d70667d42) | Jun 09, 2023 |
| ASUSTek       | G771JW                      | [6d989f49b6](https://linux-hardware.org/?probe=6d989f49b6) | Jun 09, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [f6fddfcd65](https://linux-hardware.org/?probe=f6fddfcd65) | Jun 07, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [ab7c62da47](https://linux-hardware.org/?probe=ab7c62da47) | Jun 02, 2023 |
| Dell          | Inspiron 3501               | [2cf19f7b32](https://linux-hardware.org/?probe=2cf19f7b32) | Jun 02, 2023 |
| HP            | ENVY m6 Notebook            | [f133543500](https://linux-hardware.org/?probe=f133543500) | May 23, 2023 |
| HP            | ENVY m6 Notebook            | [c903e06758](https://linux-hardware.org/?probe=c903e06758) | May 22, 2023 |
| Dell          | Inspiron 3501               | [74c412b40a](https://linux-hardware.org/?probe=74c412b40a) | May 16, 2023 |
| HP            | Victus by Gaming Laptop ... | [2dc2bdd057](https://linux-hardware.org/?probe=2dc2bdd057) | May 14, 2023 |
| Dell          | Latitude E5530 non-vPro     | [aa5dc9770e](https://linux-hardware.org/?probe=aa5dc9770e) | May 13, 2023 |
| Dell          | Latitude E5530 non-vPro     | [51c66f0f57](https://linux-hardware.org/?probe=51c66f0f57) | May 13, 2023 |
| Dell          | Inspiron 3501               | [29d2a588e0](https://linux-hardware.org/?probe=29d2a588e0) | Apr 27, 2023 |
| Dell          | Latitude D530               | [92cf04edba](https://linux-hardware.org/?probe=92cf04edba) | Mar 21, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 5.14.21-150500.53-default    | 35        | 17.77%  |
| 5.14.21-150500.55.52-default | 20        | 10.15%  |
| 5.14.21-150500.55.19-default | 19        | 9.64%   |
| 5.14.21-150500.55.39-default | 18        | 9.14%   |
| 5.14.21-150500.55.36-default | 15        | 7.61%   |
| 5.14.21-150500.55.49-default | 14        | 7.11%   |
| 5.14.21-150500.55.31-default | 10        | 5.08%   |
| 5.14.21-150500.55.65-default | 9         | 4.57%   |
| 5.14.21-150500.55.68-default | 7         | 3.55%   |
| 5.14.21-150500.55.83-default | 6         | 3.05%   |
| 5.14.21-150500.55.7-default  | 6         | 3.05%   |
| 5.14.21-150500.55.59-default | 6         | 3.05%   |
| 5.14.21-150500.55.12-default | 6         | 3.05%   |
| 5.14.21-150500.55.73-default | 5         | 2.54%   |
| 5.14.21-150500.55.44-default | 5         | 2.54%   |
| 5.14.21-150500.52-default    | 4         | 2.03%   |
| 5.14.21-150500.55.62-default | 3         | 1.52%   |
| 5.14.21-150500.55.28-default | 3         | 1.52%   |
| 6.6.11-lp155.3-default       | 1         | 0.51%   |
| 6.5.9-lp154.6-default        | 1         | 0.51%   |
| 5.14.21-150500.55.88-default | 1         | 0.51%   |
| 5.14.21-150500.50-default    | 1         | 0.51%   |
| 5.14.21-150500.49-default    | 1         | 0.51%   |
| 5.14.21-150500.43-default    | 1         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.21 | 180       | 98.9%   |
| 6.6.11  | 1         | 0.55%   |
| 6.5.9   | 1         | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 180       | 98.9%   |
| 6.6     | 1         | 0.55%   |
| 6.5     | 1         | 0.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 181       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 136       | 75.14%  |
| GNOME    | 28        | 15.47%  |
| XFCE     | 8         | 4.42%   |
| Cinnamon | 2         | 1.1%    |
| Unknown  | 2         | 1.1%    |
| Trinity  | 1         | 0.55%   |
| LXQt     | 1         | 0.55%   |
| KDE      | 1         | 0.55%   |
| ICEWM    | 1         | 0.55%   |
| Deepin   | 1         | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 147       | 79.89%  |
| Wayland | 31        | 16.85%  |
| Tty     | 5         | 2.72%   |
| Unknown | 1         | 0.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 108       | 59.34%  |
| SDDM    | 53        | 29.12%  |
| LightDM | 10        | 5.49%   |
| GDM     | 7         | 3.85%   |
| XDM     | 4         | 2.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 62        | 34.07%  |
| de_DE           | 47        | 25.82%  |
| POSIX           | 22        | 12.09%  |
| pt_BR           | 7         | 3.85%   |
| es_ES           | 7         | 3.85%   |
| en_GB           | 5         | 2.75%   |
| ru_RU           | 4         | 2.2%    |
| pl_PL           | 4         | 2.2%    |
| it_IT           | 4         | 2.2%    |
| fr_FR           | 4         | 2.2%    |
| nl_NL           | 3         | 1.65%   |
| hu_HU           | 3         | 1.65%   |
| en_DK           | 2         | 1.1%    |
| zh_CN           | 1         | 0.55%   |
| sk_SK           | 1         | 0.55%   |
| pt_PT           | 1         | 0.55%   |
| ja_JP           | 1         | 0.55%   |
| en_ZA           | 1         | 0.55%   |
| en_US.ISO8859-1 | 1         | 0.55%   |
| cs_CZ           | 1         | 0.55%   |
| Unknown         | 1         | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 116       | 63.74%  |
| EFI  | 66        | 36.26%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 145       | 80.11%  |
| Ext4  | 29        | 16.02%  |
| Xfs   | 5         | 2.76%   |
| Tmpfs | 2         | 1.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 103       | 56.28%  |
| GPT     | 74        | 40.44%  |
| MBR     | 6         | 3.28%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 168       | 92.31%  |
| Yes       | 14        | 7.69%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 146       | 80.22%  |
| Yes       | 36        | 19.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 43        | 23.76%  |
| Hewlett-Packard     | 33        | 18.23%  |
| Dell                | 27        | 14.92%  |
| ASUSTek Computer    | 20        | 11.05%  |
| Acer                | 19        | 10.5%   |
| Toshiba             | 4         | 2.21%   |
| TUXEDO              | 3         | 1.66%   |
| Sony                | 3         | 1.66%   |
| MSI                 | 3         | 1.66%   |
| Medion              | 3         | 1.66%   |
| Wortmann AG         | 2         | 1.1%    |
| System76            | 2         | 1.1%    |
| Notebook            | 2         | 1.1%    |
| HUAWEI              | 2         | 1.1%    |
| Fujitsu             | 2         | 1.1%    |
| Apple               | 2         | 1.1%    |
| Schenker            | 1         | 0.55%   |
| Samsung Electronics | 1         | 0.55%   |
| Panasonic           | 1         | 0.55%   |
| LG Electronics      | 1         | 0.55%   |
| ILLEGEAR            | 1         | 0.55%   |
| Google              | 1         | 0.55%   |
| Fujitsu Siemens     | 1         | 0.55%   |
| Framework           | 1         | 0.55%   |
| Dynabook            | 1         | 0.55%   |
| Digibras            | 1         | 0.55%   |
| Unknown             | 1         | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| TUXEDO Aura 15 Gen2                                                                      | 2         | 1.1%    |
| HP Victus by Gaming Laptop 15-fb0xxx                                                     | 2         | 1.1%    |
| HP Notebook                                                                              | 2         | 1.1%    |
| Unknown                                                                                  | 2         | 1.1%    |
| Wortmann AG TERRA_MOBILE_1749                                                            | 1         | 0.55%   |
| Wortmann AG TERRA_MOBILE_1512/1712                                                       | 1         | 0.55%   |
| TUXEDO Pulse 15 Gen2                                                                     | 1         | 0.55%   |
| Toshiba Satellite R945                                                                   | 1         | 0.55%   |
| Toshiba Satellite Pro C70-A                                                              | 1         | 0.55%   |
| Toshiba Satellite C55D-A                                                                 | 1         | 0.55%   |
| Toshiba dynabook Satellite B552/H                                                        | 1         | 0.55%   |
| System76 Lemur Pro                                                                       | 1         | 0.55%   |
| System76 Bonobo WS                                                                       | 1         | 0.55%   |
| Sony VPCEH11FX                                                                           | 1         | 0.55%   |
| Sony SVF1521A7EB                                                                         | 1         | 0.55%   |
| Schenker KEY (E23)                                                                       | 1         | 0.55%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.55%   |
| Panasonic CF-C2CUGZXKM                                                                   | 1         | 0.55%   |
| Notebook NS50_70MU                                                                       | 1         | 0.55%   |
| Notebook NLx0MU                                                                          | 1         | 0.55%   |
| MSI Summit E13FlipEvo A11MT                                                              | 1         | 0.55%   |
| MSI Katana GF66 11UE                                                                     | 1         | 0.55%   |
| MSI Cyborg 15 A13VE                                                                      | 1         | 0.55%   |
| Medion S15449                                                                            | 1         | 0.55%   |
| Medion P662X                                                                             | 1         | 0.55%   |
| Medion E6224                                                                             | 1         | 0.55%   |
| LG P1-J331P                                                                              | 1         | 0.55%   |
| Lenovo Y520-15IKBN 80WK                                                                  | 1         | 0.55%   |
| Lenovo V15-IGL 82C3                                                                      | 1         | 0.55%   |
| Lenovo U31-70 80M5                                                                       | 1         | 0.55%   |
| Lenovo ThinkPad X390 20Q1S5K400                                                          | 1         | 0.55%   |
| Lenovo ThinkPad X270 W10DG 20K6S0X900                                                    | 1         | 0.55%   |
| Lenovo ThinkPad X200 7458AH8                                                             | 1         | 0.55%   |
| Lenovo ThinkPad W541 20EGS1LB00                                                          | 1         | 0.55%   |
| Lenovo ThinkPad W520 4282A34                                                             | 1         | 0.55%   |
| Lenovo ThinkPad W500 40624DG                                                             | 1         | 0.55%   |
| Lenovo ThinkPad T530 2394W19                                                             | 1         | 0.55%   |
| Lenovo ThinkPad T490 20N2000LSP                                                          | 1         | 0.55%   |
| Lenovo ThinkPad T470p 20J60014PB                                                         | 1         | 0.55%   |
| Lenovo ThinkPad T470 W10DG 20JNS09G00                                                    | 1         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 23        | 12.71%  |
| Acer Aspire            | 12        | 6.63%   |
| Lenovo IdeaPad         | 8         | 4.42%   |
| HP EliteBook           | 8         | 4.42%   |
| Dell Precision         | 8         | 4.42%   |
| Dell Latitude          | 8         | 4.42%   |
| HP Laptop              | 6         | 3.31%   |
| Lenovo Legion          | 5         | 2.76%   |
| Dell Inspiron          | 5         | 2.76%   |
| ASUS VivoBook          | 5         | 2.76%   |
| HP Victus              | 4         | 2.21%   |
| HP ENVY                | 4         | 2.21%   |
| Toshiba Satellite      | 3         | 1.66%   |
| Dell Vostro            | 3         | 1.66%   |
| Acer Nitro             | 3         | 1.66%   |
| Wortmann AG TERRA      | 2         | 1.1%    |
| TUXEDO Aura            | 2         | 1.1%    |
| HP ProBook             | 2         | 1.1%    |
| HP Pavilion            | 2         | 1.1%    |
| HP OMEN                | 2         | 1.1%    |
| HP Notebook            | 2         | 1.1%    |
| Dell XPS               | 2         | 1.1%    |
| ASUS Zenbook           | 2         | 1.1%    |
| ASUS ROG               | 2         | 1.1%    |
| Acer TravelMate        | 2         | 1.1%    |
| Unknown                | 2         | 1.1%    |
| TUXEDO Pulse           | 1         | 0.55%   |
| Toshiba dynabook       | 1         | 0.55%   |
| System76 Lemur         | 1         | 0.55%   |
| System76 Bonobo        | 1         | 0.55%   |
| Sony VPCEH11FX         | 1         | 0.55%   |
| Sony SVF1521A7EB       | 1         | 0.55%   |
| Schenker KEY           | 1         | 0.55%   |
| Samsung 355V4C         | 1         | 0.55%   |
| Panasonic CF-C2CUGZXKM | 1         | 0.55%   |
| Notebook NS50          | 1         | 0.55%   |
| Notebook NLx0MU        | 1         | 0.55%   |
| MSI Summit             | 1         | 0.55%   |
| MSI Katana             | 1         | 0.55%   |
| MSI Cyborg             | 1         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 25        | 13.81%  |
| 2019 | 19        | 10.5%   |
| 2022 | 17        | 9.39%   |
| 2020 | 17        | 9.39%   |
| 2023 | 13        | 7.18%   |
| 2010 | 13        | 7.18%   |
| 2017 | 12        | 6.63%   |
| 2013 | 11        | 6.08%   |
| 2011 | 11        | 6.08%   |
| 2012 | 10        | 5.52%   |
| 2015 | 7         | 3.87%   |
| 2016 | 6         | 3.31%   |
| 2014 | 6         | 3.31%   |
| 2009 | 4         | 2.21%   |
| 2008 | 4         | 2.21%   |
| 2018 | 2         | 1.1%    |
| 2007 | 2         | 1.1%    |
| 2024 | 1         | 0.55%   |
| 2006 | 1         | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 181       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 158       | 86.81%  |
| Enabled  | 24        | 13.19%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 178       | 98.34%  |
| Yes  | 3         | 1.66%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 52        | 28.57%  |
| 16.01-24.0  | 41        | 22.53%  |
| 8.01-16.0   | 34        | 18.68%  |
| 32.01-64.0  | 21        | 11.54%  |
| 3.01-4.0    | 19        | 10.44%  |
| 64.01-256.0 | 7         | 3.85%   |
| 1.01-2.0    | 5         | 2.75%   |
| 24.01-32.0  | 2         | 1.1%    |
| 2.01-3.0    | 1         | 0.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 59        | 31.05%  |
| 1.01-2.0   | 46        | 24.21%  |
| 3.01-4.0   | 39        | 20.53%  |
| 4.01-8.0   | 29        | 15.26%  |
| 8.01-16.0  | 10        | 5.26%   |
| 0.51-1.0   | 6         | 3.16%   |
| 16.01-24.0 | 1         | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 134       | 73.63%  |
| 2      | 42        | 23.08%  |
| 3      | 6         | 3.3%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 123       | 67.58%  |
| Yes       | 59        | 32.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 155       | 85.64%  |
| No        | 26        | 14.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 96.69%  |
| No        | 6         | 3.31%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 150       | 81.08%  |
| No        | 35        | 18.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 52        | 28.73%  |
| USA          | 30        | 16.57%  |
| Brazil       | 10        | 5.52%   |
| Poland       | 7         | 3.87%   |
| Italy        | 7         | 3.87%   |
| Russia       | 6         | 3.31%   |
| UK           | 5         | 2.76%   |
| Spain        | 5         | 2.76%   |
| Hungary      | 4         | 2.21%   |
| Netherlands  | 3         | 1.66%   |
| Mexico       | 3         | 1.66%   |
| India        | 3         | 1.66%   |
| Greece       | 3         | 1.66%   |
| Canada       | 3         | 1.66%   |
| Belgium      | 3         | 1.66%   |
| Ukraine      | 2         | 1.1%    |
| Serbia       | 2         | 1.1%    |
| Malaysia     | 2         | 1.1%    |
| France       | 2         | 1.1%    |
| Czechia      | 2         | 1.1%    |
| Colombia     | 2         | 1.1%    |
| Argentina    | 2         | 1.1%    |
| Venezuela    | 1         | 0.55%   |
| Türkiye     | 1         | 0.55%   |
| Turkey       | 1         | 0.55%   |
| Switzerland  | 1         | 0.55%   |
| Sweden       | 1         | 0.55%   |
| South Africa | 1         | 0.55%   |
| Slovenia     | 1         | 0.55%   |
| Slovakia     | 1         | 0.55%   |
| Senegal      | 1         | 0.55%   |
| Portugal     | 1         | 0.55%   |
| Peru         | 1         | 0.55%   |
| Japan        | 1         | 0.55%   |
| Israel       | 1         | 0.55%   |
| Ireland      | 1         | 0.55%   |
| Hong Kong    | 1         | 0.55%   |
| Finland      | 1         | 0.55%   |
| Denmark      | 1         | 0.55%   |
| Croatia      | 1         | 0.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Munich                | 6         | 3.26%   |
| Berlin                | 4         | 2.17%   |
| Warsaw                | 3         | 1.63%   |
| Sao Paulo             | 3         | 1.63%   |
| Leipzig               | 3         | 1.63%   |
| Hamburg               | 3         | 1.63%   |
| Budapest              | 3         | 1.63%   |
| Rio de Janeiro        | 2         | 1.09%   |
| Portland              | 2         | 1.09%   |
| Milan                 | 2         | 1.09%   |
| Kyiv                  | 2         | 1.09%   |
| Kuala Lumpur          | 2         | 1.09%   |
| Hanover               | 2         | 1.09%   |
| Bonn                  | 2         | 1.09%   |
| Alcobendas            | 2         | 1.09%   |
| Zetel                 | 1         | 0.54%   |
| Zagreb                | 1         | 0.54%   |
| Yokohama              | 1         | 0.54%   |
| Yekaterinburg         | 1         | 0.54%   |
| Wolfsburg             | 1         | 0.54%   |
| Wolfratshausen        | 1         | 0.54%   |
| Weilmuenster          | 1         | 0.54%   |
| Waterloo              | 1         | 0.54%   |
| Waidhofen an der Ybbs | 1         | 0.54%   |
| Wachtberg             | 1         | 0.54%   |
| Vinemont              | 1         | 0.54%   |
| Vigo                  | 1         | 0.54%   |
| Vechta                | 1         | 0.54%   |
| Trivandrum            | 1         | 0.54%   |
| Tolyatti              | 1         | 0.54%   |
| Tokaj                 | 1         | 0.54%   |
| Tel Aviv              | 1         | 0.54%   |
| Sydney                | 1         | 0.54%   |
| Sunapee               | 1         | 0.54%   |
| Stuttgart             | 1         | 0.54%   |
| St Petersburg         | 1         | 0.54%   |
| St Louis              | 1         | 0.54%   |
| Sofia                 | 1         | 0.54%   |
| Sigtuna               | 1         | 0.54%   |
| Siegen                | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 47        | 56     | 20.7%   |
| Seagate                     | 21        | 26     | 9.25%   |
| Sandisk                     | 19        | 25     | 8.37%   |
| WDC                         | 13        | 14     | 5.73%   |
| Toshiba                     | 12        | 14     | 5.29%   |
| SK hynix                    | 12        | 14     | 5.29%   |
| Micron Technology           | 11        | 11     | 4.85%   |
| Unknown                     | 10        | 12     | 4.41%   |
| Intel                       | 10        | 10     | 4.41%   |
| Kingston                    | 9         | 11     | 3.96%   |
| HGST                        | 6         | 6      | 2.64%   |
| Crucial                     | 6         | 6      | 2.64%   |
| Micron/Crucial Technology   | 4         | 6      | 1.76%   |
| Hitachi                     | 4         | 4      | 1.76%   |
| China                       | 4         | 5      | 1.76%   |
| KIOXIA                      | 3         | 4      | 1.32%   |
| Kingston Technology Company | 3         | 3      | 1.32%   |
| ADATA Technology            | 3         | 3      | 1.32%   |
| Silicon Motion              | 2         | 2      | 0.88%   |
| Phison Electronics          | 2         | 2      | 0.88%   |
| Fanxiang                    | 2         | 2      | 0.88%   |
| Dogfish                     | 2         | 2      | 0.88%   |
| Apple                       | 2         | 2      | 0.88%   |
| A-DATA Technology           | 2         | 2      | 0.88%   |
| Unknown                     | 2         | 2      | 0.88%   |
| Yangtze Memory Technologies | 1         | 1      | 0.44%   |
| Verbatim                    | 1         | 1      | 0.44%   |
| USB                         | 1         | 1      | 0.44%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.44%   |
| Union Memory                | 1         | 1      | 0.44%   |
| Transcend                   | 1         | 1      | 0.44%   |
| SPCC                        | 1         | 1      | 0.44%   |
| Realtek Semiconductor       | 1         | 1      | 0.44%   |
| PNY                         | 1         | 2      | 0.44%   |
| Patriot                     | 1         | 1      | 0.44%   |
| Netac                       | 1         | 2      | 0.44%   |
| KXG60ZNV                    | 1         | 1      | 0.44%   |
| GOODRAM                     | 1         | 1      | 0.44%   |
| Gigabyte Technology         | 1         | 1      | 0.44%   |
| BR                          | 1         | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB              | 9         | 3.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB               | 8         | 3.46%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                              | 6         | 2.6%    |
| Seagate ST1000LM035-1RK172 1TB                                    | 5         | 2.16%   |
| Intel SSD 660P Series 1024GB                                      | 5         | 2.16%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB                  | 4         | 1.73%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                             | 4         | 1.73%   |
| Unknown MMC Card  16GB                                            | 3         | 1.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                                | 3         | 1.3%    |
| Samsung SSD 840 EVO 250GB                                         | 3         | 1.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                                  | 2         | 0.87%   |
| Unknown MMC Card  32GB                                            | 2         | 0.87%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                            | 2         | 0.87%   |
| Toshiba MQ04ABF100 1TB                                            | 2         | 0.87%   |
| Toshiba MQ01ABD100 1TB                                            | 2         | 0.87%   |
| Seagate ST500LM012 HN-M500MBB 500GB                               | 2         | 0.87%   |
| Seagate ST1000LM048-2E7172 1TB                                    | 2         | 0.87%   |
| Samsung SSD 870 EVO 1TB                                           | 2         | 0.87%   |
| Samsung SSD 860 EVO 1TB                                           | 2         | 0.87%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                                  | 2         | 0.87%   |
| Samsung MZALQ256HAJD-000L2 256GB                                  | 2         | 0.87%   |
| KIOXIA KBG40ZNV256G 256GB                                         | 2         | 0.87%   |
| Kingston SNVS500G 500GB                                           | 2         | 0.87%   |
| Kingston SA400S37120G 120GB SSD                                   | 2         | 0.87%   |
| Intel SSD Pro 7600p/760p/E 6100p Series 512GB                     | 2         | 0.87%   |
| HGST HTS721010A9E630 1TB                                          | 2         | 0.87%   |
| HGST HTS541010A9E680 1TB                                          | 2         | 0.87%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 256GB | 2         | 0.87%   |
| Unknown                                                           | 2         | 0.87%   |
| Yangtze Memory ZHITAI TiPlus5000 1TB                              | 1         | 0.43%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                                  | 1         | 0.43%   |
| WDC WDS240G2G0C-00AJM0 240GB                                      | 1         | 0.43%   |
| WDC WD7500BPVT-22HXZT3 752GB                                      | 1         | 0.43%   |
| WDC WD5000LPVX-16V0TT3 500GB                                      | 1         | 0.43%   |
| WDC WD5000LPVT-08G33T1 500GB                                      | 1         | 0.43%   |
| WDC WD3200BPVT-24ZEST0 320GB                                      | 1         | 0.43%   |
| WDC WD3200BEVT-22A23T0 320GB                                      | 1         | 0.43%   |
| WDC WD3200BEKT-75PVMT0 320GB                                      | 1         | 0.43%   |
| WDC WD20SPZX-21UA7T0 2TB                                          | 1         | 0.43%   |
| WDC WD12 00BEVS-07LAT0 120GB                                      | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 18        | 20     | 40.91%  |
| WDC     | 8         | 8      | 18.18%  |
| Toshiba | 6         | 6      | 13.64%  |
| HGST    | 6         | 6      | 13.64%  |
| Hitachi | 4         | 4      | 9.09%   |
| ASMT    | 1         | 1      | 2.27%   |
| Apple   | 1         | 1      | 2.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 22     | 28.57%  |
| Crucial             | 6         | 6      | 9.52%   |
| SanDisk             | 5         | 9      | 7.94%   |
| Kingston            | 5         | 5      | 7.94%   |
| WDC                 | 4         | 5      | 6.35%   |
| China               | 4         | 5      | 6.35%   |
| Toshiba             | 3         | 4      | 4.76%   |
| Micron Technology   | 2         | 2      | 3.17%   |
| Dogfish             | 2         | 2      | 3.17%   |
| A-DATA Technology   | 2         | 2      | 3.17%   |
| Transcend           | 1         | 1      | 1.59%   |
| SPCC                | 1         | 1      | 1.59%   |
| SK hynix            | 1         | 1      | 1.59%   |
| PNY                 | 1         | 2      | 1.59%   |
| Patriot             | 1         | 1      | 1.59%   |
| Netac               | 1         | 2      | 1.59%   |
| Intel               | 1         | 1      | 1.59%   |
| GOODRAM             | 1         | 1      | 1.59%   |
| Gigabyte Technology | 1         | 1      | 1.59%   |
| Fanxiang            | 1         | 1      | 1.59%   |
| Apple               | 1         | 1      | 1.59%   |
| Unknown             | 1         | 1      | 1.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 92        | 119    | 43.81%  |
| SSD     | 59        | 76     | 28.1%   |
| HDD     | 43        | 46     | 20.48%  |
| MMC     | 10        | 12     | 4.76%   |
| Unknown | 6         | 9      | 2.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 95        | 121    | 46.34%  |
| NVMe | 92        | 118    | 44.88%  |
| MMC  | 10        | 12     | 4.88%   |
| SAS  | 8         | 11     | 3.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 66        | 73     | 63.46%  |
| 0.51-1.0   | 33        | 44     | 31.73%  |
| 1.01-2.0   | 3         | 3      | 2.88%   |
| 3.01-4.0   | 1         | 1      | 0.96%   |
| 4.01-10.0  | 1         | 1      | 0.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 54        | 29.67%  |
| 1001-2000      | 40        | 21.98%  |
| 501-1000       | 24        | 13.19%  |
| 2001-3000      | 23        | 12.64%  |
| 251-500        | 20        | 10.99%  |
| 101-250        | 15        | 8.24%   |
| 21-50          | 3         | 1.65%   |
| 51-100         | 2         | 1.1%    |
| Unknown        | 1         | 0.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 62        | 32.8%   |
| 51-100         | 36        | 19.05%  |
| 251-500        | 34        | 17.99%  |
| 501-1000       | 18        | 9.52%   |
| 1-20           | 14        | 7.41%   |
| More than 3000 | 8         | 4.23%   |
| 1001-2000      | 8         | 4.23%   |
| 21-50          | 6         | 3.17%   |
| 2001-3000      | 2         | 1.06%   |
| Unknown        | 1         | 0.53%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZALQ256HBJD-00BL2 256GB | 1         | 1      | 20%     |
| Intel SSD 600P Series 256GB                  | 1         | 1      | 20%     |
| Hitachi HTS727550A9E364 500GB                | 1         | 1      | 20%     |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 20%     |
| Crucial CT240M500SSD1 240GB                  | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 20%     |
| Intel               | 1         | 1      | 20%     |
| Hitachi             | 1         | 1      | 20%     |
| HGST                | 1         | 1      | 20%     |
| Crucial             | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 50%     |
| HGST    | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 2         | 2      | 40%     |
| HDD  | 2         | 2      | 40%     |
| SSD  | 1         | 1      | 20%     |

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
| Detected | 108       | 155    | 56.54%  |
| Works    | 78        | 102    | 40.84%  |
| Malfunc  | 5         | 5      | 2.62%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 121       | 51.49%  |
| Samsung Electronics          | 30        | 12.77%  |
| AMD                          | 17        | 7.23%   |
| SanDisk                      | 15        | 6.38%   |
| SK hynix                     | 11        | 4.68%   |
| Micron Technology            | 9         | 3.83%   |
| Kingston Technology Company  | 7         | 2.98%   |
| Toshiba America Info Systems | 4         | 1.7%    |
| Micron/Crucial Technology    | 4         | 1.7%    |
| KIOXIA                       | 3         | 1.28%   |
| ADATA Technology             | 3         | 1.28%   |
| Union Memory (Shenzhen)      | 2         | 0.85%   |
| Silicon Motion               | 2         | 0.85%   |
| Seagate Technology           | 2         | 0.85%   |
| Phison Electronics           | 2         | 0.85%   |
| Yangtze Memory Technologies  | 1         | 0.43%   |
| Realtek Semiconductor        | 1         | 0.43%   |
| Nvidia                       | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 5.84%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 15        | 5.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 13        | 5.06%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 11        | 4.28%   |
| Intel Volume Management Device NVMe RAID Controller                            | 11        | 4.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 3.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 3.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 3.11%   |
| Intel Tiger Lake-LP SATA Controller                                            | 7         | 2.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 2.72%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.72%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 6         | 2.33%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 6         | 2.33%   |
| Intel SSD 660P Series                                                          | 5         | 1.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.95%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 1.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 1.95%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 4         | 1.56%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 4         | 1.56%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 4         | 1.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.56%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 4         | 1.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.56%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 3         | 1.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.17%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 1.17%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.78%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 2         | 0.78%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 2         | 0.78%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 2         | 0.78%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 0.78%   |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                           | 2         | 0.78%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 0.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.78%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 0.78%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 119       | 49.58%  |
| NVMe | 92        | 38.33%  |
| RAID | 21        | 8.75%   |
| IDE  | 8         | 3.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 144       | 79.56%  |
| AMD    | 37        | 20.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 7         | 3.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 6         | 3.31%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 5         | 2.76%   |
| AMD Ryzen 5 5500U with Radeon Graphics   | 5         | 2.76%   |
| AMD Ryzen 5 5600H with Radeon Graphics   | 4         | 2.21%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 3         | 1.66%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 3         | 1.66%   |
| Intel Core i3-2310M CPU @ 2.10GHz        | 3         | 1.66%   |
| Intel 13th Gen Core i9-13900HX           | 3         | 1.66%   |
| AMD Ryzen 7 5700U with Radeon Graphics   | 3         | 1.66%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 2         | 1.1%    |
| Intel Core i7-4720HQ CPU @ 2.60GHz       | 2         | 1.1%    |
| Intel Core i5-9300H CPU @ 2.40GHz        | 2         | 1.1%    |
| Intel Core i5-8250U CPU @ 1.60GHz        | 2         | 1.1%    |
| Intel Core i5-6300U CPU @ 2.40GHz        | 2         | 1.1%    |
| Intel Core i5-6200U CPU @ 2.30GHz        | 2         | 1.1%    |
| Intel Core i5-3210M CPU @ 2.50GHz        | 2         | 1.1%    |
| Intel Core i5-2520M CPU @ 2.50GHz        | 2         | 1.1%    |
| Intel Core i5-10210U CPU @ 1.60GHz       | 2         | 1.1%    |
| Intel Core i3 CPU M 380 @ 2.53GHz        | 2         | 1.1%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz     | 2         | 1.1%    |
| Intel Celeron N4020 CPU @ 1.10GHz        | 2         | 1.1%    |
| Intel 13th Gen Core i9-13900H            | 2         | 1.1%    |
| Intel 12th Gen Core i5-1235U             | 2         | 1.1%    |
| Intel 11th Gen Core i7-11800H @ 2.30GHz  | 2         | 1.1%    |
| AMD Ryzen 7 5800H with Radeon Graphics   | 2         | 1.1%    |
| AMD Ryzen 5 7530U with Radeon Graphics   | 2         | 1.1%    |
| Intel Xeon E-2276M CPU @ 2.80GHz         | 1         | 0.55%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz     | 1         | 0.55%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 1         | 0.55%   |
| Intel Pentium Gold 7505 @ 2.00GHz        | 1         | 0.55%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz   | 1         | 0.55%   |
| Intel Pentium CPU P6100 @ 2.00GHz        | 1         | 0.55%   |
| Intel Pentium CPU P6000 @ 1.87GHz        | 1         | 0.55%   |
| Intel Pentium CPU N3700 @ 1.60GHz        | 1         | 0.55%   |
| Intel Pentium CPU B940 @ 2.00GHz         | 1         | 0.55%   |
| Intel Pentium CPU 2117U @ 1.80GHz        | 1         | 0.55%   |
| Intel Pentium CPU 2020M @ 2.40GHz        | 1         | 0.55%   |
| Intel Core i7-9850H CPU @ 2.60GHz        | 1         | 0.55%   |
| Intel Core i7-8850H CPU @ 2.60GHz        | 1         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 38        | 20.99%  |
| Other                | 35        | 19.34%  |
| Intel Core i5        | 31        | 17.13%  |
| AMD Ryzen 5          | 15        | 8.29%   |
| Intel Core i3        | 14        | 7.73%   |
| AMD Ryzen 7          | 9         | 4.97%   |
| Intel Core 2 Duo     | 7         | 3.87%   |
| Intel Pentium        | 6         | 3.31%   |
| Intel Celeron        | 6         | 3.31%   |
| AMD A6               | 4         | 2.21%   |
| AMD Ryzen 7 PRO      | 3         | 1.66%   |
| Intel Xeon           | 2         | 1.1%    |
| Intel Pentium Silver | 1         | 0.55%   |
| Intel Pentium Gold   | 1         | 0.55%   |
| Intel Pentium Dual   | 1         | 0.55%   |
| Intel Core 2 Extreme | 1         | 0.55%   |
| Intel Core 2         | 1         | 0.55%   |
| AMD Ryzen 3          | 1         | 0.55%   |
| AMD FX               | 1         | 0.55%   |
| AMD Athlon X2        | 1         | 0.55%   |
| AMD Athlon           | 1         | 0.55%   |
| AMD A8               | 1         | 0.55%   |
| AMD A4               | 1         | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 72        | 39.78%  |
| 4      | 56        | 30.94%  |
| 6      | 23        | 12.71%  |
| 8      | 15        | 8.29%   |
| 14     | 4         | 2.21%   |
| 24     | 3         | 1.66%   |
| 12     | 3         | 1.66%   |
| 10     | 3         | 1.66%   |
| 20     | 1         | 0.55%   |
| 1      | 1         | 0.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 181       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 149       | 82.32%  |
| 1      | 32        | 17.68%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 181       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 100       | 54.95%  |
| 0x806c1    | 12        | 6.59%   |
| 0x806ec    | 7         | 3.85%   |
| 0x906ea    | 5         | 2.75%   |
| 0x08608103 | 5         | 2.75%   |
| 0x406e3    | 4         | 2.2%    |
| 0x306a9    | 4         | 2.2%    |
| 0xb0671    | 3         | 1.65%   |
| 0xb06a2    | 2         | 1.1%    |
| 0x906e9    | 2         | 1.1%    |
| 0x906a3    | 2         | 1.1%    |
| 0x806ea    | 2         | 1.1%    |
| 0x806e9    | 2         | 1.1%    |
| 0x40651    | 2         | 1.1%    |
| 0x20655    | 2         | 1.1%    |
| 0x1067a    | 2         | 1.1%    |
| 0x0a50000d | 2         | 1.1%    |
| 0x0a50000c | 2         | 1.1%    |
| 0x08608102 | 2         | 1.1%    |
| 0x08600106 | 2         | 1.1%    |
| 0x906ed    | 1         | 0.55%   |
| 0x806d1    | 1         | 0.55%   |
| 0x806c2    | 1         | 0.55%   |
| 0x706e5    | 1         | 0.55%   |
| 0x706a8    | 1         | 0.55%   |
| 0x6f6      | 1         | 0.55%   |
| 0x506e3    | 1         | 0.55%   |
| 0x306d4    | 1         | 0.55%   |
| 0x306c3    | 1         | 0.55%   |
| 0x206a7    | 1         | 0.55%   |
| 0x106e5    | 1         | 0.55%   |
| 0x10676    | 1         | 0.55%   |
| 0x0a704103 | 1         | 0.55%   |
| 0x0a601203 | 1         | 0.55%   |
| 0x0a50000f | 1         | 0.55%   |
| 0x0a404102 | 1         | 0.55%   |
| 0x0a404101 | 1         | 0.55%   |
| 0x03000027 | 1         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 27        | 14.92%  |
| Unknown          | 24        | 13.26%  |
| TigerLake        | 18        | 9.94%   |
| IvyBridge        | 14        | 7.73%   |
| Haswell          | 13        | 7.18%   |
| Zen 3            | 11        | 6.08%   |
| SandyBridge      | 11        | 6.08%   |
| Skylake          | 10        | 5.52%   |
| Westmere         | 9         | 4.97%   |
| Alderlake Hybrid | 7         | 3.87%   |
| Penryn           | 6         | 3.31%   |
| Core             | 4         | 2.21%   |
| Broadwell        | 4         | 2.21%   |
| Zen 2            | 3         | 1.66%   |
| IceLake          | 3         | 1.66%   |
| Goldmont plus    | 3         | 1.66%   |
| Excavator        | 3         | 1.66%   |
| Zen+             | 2         | 1.1%    |
| Silvermont       | 2         | 1.1%    |
| Nehalem          | 2         | 1.1%    |
| K10 Llano        | 2         | 1.1%    |
| Piledriver       | 1         | 0.55%   |
| K8 & K10 hybrid  | 1         | 0.55%   |
| Jaguar           | 1         | 0.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 133       | 54.73%  |
| Nvidia | 61        | 25.1%   |
| AMD    | 49        | 20.16%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 16        | 6.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 13        | 5.24%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 10        | 4.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 10        | 4.03%   |
| AMD Lucienne                                                                          | 9         | 3.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 8         | 3.23%   |
| Intel Core Processor Integrated Graphics Controller                                   | 7         | 2.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 2.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 6         | 2.42%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 5         | 2.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 2.02%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 5         | 2.02%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                       | 4         | 1.61%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 1.61%   |
| Intel Raptor Lake-S UHD Graphics                                                      | 4         | 1.61%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 4         | 1.61%   |
| Intel HD Graphics 5500                                                                | 4         | 1.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 3         | 1.21%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 3         | 1.21%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 1.21%   |
| Intel UHD Graphics 620                                                                | 3         | 1.21%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 3         | 1.21%   |
| Intel HD Graphics 630                                                                 | 3         | 1.21%   |
| Intel HD Graphics 620                                                                 | 3         | 1.21%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 1.21%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 3         | 1.21%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                           | 3         | 1.21%   |
| AMD Barcelo                                                                           | 3         | 1.21%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 0.81%   |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 2         | 0.81%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 2         | 0.81%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 2         | 0.81%   |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                                           | 2         | 0.81%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 2         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 2         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 2         | 0.81%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 0.81%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                           | 2         | 0.81%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 0.81%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 2         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 80        | 44.2%   |
| Intel + Nvidia | 42        | 23.2%   |
| 1 x AMD        | 26        | 14.36%  |
| Intel + AMD    | 11        | 6.08%   |
| 1 x Nvidia     | 10        | 5.52%   |
| AMD + Nvidia   | 9         | 4.97%   |
| 2 x AMD        | 3         | 1.66%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 156       | 86.19%  |
| Proprietary | 22        | 12.15%  |
| Unknown     | 3         | 1.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 141       | 77.9%   |
| 1.01-2.0   | 15        | 8.29%   |
| 0.01-0.5   | 13        | 7.18%   |
| 3.01-4.0   | 6         | 3.31%   |
| 7.01-8.0   | 4         | 2.21%   |
| 0.51-1.0   | 2         | 1.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 36        | 16.98%  |
| LG Display              | 33        | 15.57%  |
| Chimei Innolux          | 32        | 15.09%  |
| BOE                     | 31        | 14.62%  |
| Samsung Electronics     | 21        | 9.91%   |
| Sharp                   | 6         | 2.83%   |
| Lenovo                  | 6         | 2.83%   |
| Sony                    | 5         | 2.36%   |
| Goldstar                | 5         | 2.36%   |
| Dell                    | 5         | 2.36%   |
| Chi Mei Optoelectronics | 4         | 1.89%   |
| BenQ                    | 4         | 1.89%   |
| PANDA                   | 3         | 1.42%   |
| CSO                     | 3         | 1.42%   |
| HKC                     | 2         | 0.94%   |
| Apple                   | 2         | 0.94%   |
| AOC                     | 2         | 0.94%   |
| Toshiba                 | 1         | 0.47%   |
| SANYO                   | 1         | 0.47%   |
| Philips                 | 1         | 0.47%   |
| IPS                     | 1         | 0.47%   |
| Insignia                | 1         | 0.47%   |
| Iiyama                  | 1         | 0.47%   |
| IBM                     | 1         | 0.47%   |
| Hewlett-Packard         | 1         | 0.47%   |
| GreenWood               | 1         | 0.47%   |
| Eizo                    | 1         | 0.47%   |
| CGC                     | 1         | 0.47%   |
| ASUSTek Computer        | 1         | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 4         | 1.89%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 1.42%   |
| Sony TV *00 SNY4904 3840x2160                                            | 2         | 0.94%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 2         | 0.94%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.94%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.94%   |
| BOE LCD Monitor BOE0BB7 3840x2160 381x214mm 17.2-inch                    | 2         | 0.94%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 2         | 0.94%   |
| AU Optronics LCD Monitor AUOFA9B 1920x1200 301x188mm 14.0-inch           | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch           | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch            | 2         | 0.94%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                    | 1         | 0.47%   |
| Sony TV SNYEE01 1920x1080                                                | 1         | 0.47%   |
| Sony TV *00 SNYF303 1920x1080 952x535mm 43.0-inch                        | 1         | 0.47%   |
| Sony LCD MS_0025 1920x1080 531x299mm 24.0-inch                           | 1         | 0.47%   |
| Sharp LQ156D1JW04 SHP1436 3840x2160 346x194mm 15.6-inch                  | 1         | 0.47%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 288x180mm 13.4-inch                  | 1         | 0.47%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 1         | 0.47%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                  | 1         | 0.47%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 1         | 0.47%   |
| Sharp LCD Monitor SHP1446 3840x2160 382x215mm 17.3-inch                  | 1         | 0.47%   |
| SANYO LCD SAN0B75 1920x540                                               | 1         | 0.47%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 608x345mm 27.5-inch        | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0586 1920x1200 518x324mm 24.1-inch     | 1         | 0.47%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch       | 1         | 0.47%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch        | 1         | 0.47%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch        | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 367x230mm 17.1-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5244 1600x900 360x210mm 16.4-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3253 1366x768 344x194mm 15.5-inch     | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 89        | 44.28%  |
| 1366x768 (WXGA)    | 43        | 21.39%  |
| 3840x2160 (4K)     | 14        | 6.97%   |
| 1600x900 (HD+)     | 13        | 6.47%   |
| 1920x1200 (WUXGA)  | 10        | 4.98%   |
| 2560x1600          | 6         | 2.99%   |
| 2560x1440 (QHD)    | 6         | 2.99%   |
| 1440x900 (WXGA+)   | 5         | 2.49%   |
| 1280x800 (WXGA)    | 4         | 1.99%   |
| 2880x1800          | 2         | 1%      |
| 3440x1440          | 1         | 0.5%    |
| 2560x1080          | 1         | 0.5%    |
| 2520x1680          | 1         | 0.5%    |
| 2256x1504          | 1         | 0.5%    |
| 2160x1440          | 1         | 0.5%    |
| 1920x540           | 1         | 0.5%    |
| 1680x1050 (WSXGA+) | 1         | 0.5%    |
| 1280x1024 (SXGA)   | 1         | 0.5%    |
| 1024x768 (XGA)     | 1         | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 90        | 42.65%  |
| 17      | 28        | 13.27%  |
| 14      | 21        | 9.95%   |
| 13      | 15        | 7.11%   |
| 16      | 13        | 6.16%   |
| 27      | 10        | 4.74%   |
| 24      | 6         | 2.84%   |
| 12      | 5         | 2.37%   |
| 23      | 4         | 1.9%    |
| 21      | 4         | 1.9%    |
| 72      | 3         | 1.42%   |
| 34      | 2         | 0.95%   |
| Unknown | 2         | 0.95%   |
| 86      | 1         | 0.47%   |
| 75      | 1         | 0.47%   |
| 40      | 1         | 0.47%   |
| 38      | 1         | 0.47%   |
| 33      | 1         | 0.47%   |
| 28      | 1         | 0.47%   |
| 19      | 1         | 0.47%   |
| 11      | 1         | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 124       | 59.05%  |
| 351-400     | 33        | 15.71%  |
| 501-600     | 17        | 8.1%    |
| 201-300     | 15        | 7.14%   |
| 401-500     | 5         | 2.38%   |
| 601-700     | 4         | 1.9%    |
| 1501-2000   | 4         | 1.9%    |
| 701-800     | 3         | 1.43%   |
| 801-900     | 2         | 0.95%   |
| Unknown     | 2         | 0.95%   |
| 1001-1500   | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 149       | 80.54%  |
| 16/10 | 27        | 14.59%  |
| 3/2   | 3         | 1.62%   |
| 21/9  | 2         | 1.08%   |
| 5/4   | 1         | 0.54%   |
| 4/3   | 1         | 0.54%   |
| 32/9  | 1         | 0.54%   |
| 0.56  | 1         | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 93        | 44.08%  |
| 81-90          | 30        | 14.22%  |
| 121-130        | 23        | 10.9%   |
| 301-350        | 10        | 4.74%   |
| 111-120        | 10        | 4.74%   |
| 71-80          | 6         | 2.84%   |
| 201-250        | 6         | 2.84%   |
| More than 1000 | 5         | 2.37%   |
| 61-70          | 5         | 2.37%   |
| 251-300        | 5         | 2.37%   |
| 351-500        | 4         | 1.9%    |
| 151-200        | 4         | 1.9%    |
| 131-140        | 4         | 1.9%    |
| 501-1000       | 2         | 0.95%   |
| Unknown        | 2         | 0.95%   |
| 51-60          | 1         | 0.47%   |
| 141-150        | 1         | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 89        | 43%     |
| 101-120       | 53        | 25.6%   |
| 51-100        | 31        | 14.98%  |
| 161-240       | 22        | 10.63%  |
| More than 240 | 7         | 3.38%   |
| 1-50          | 3         | 1.45%   |
| Unknown       | 2         | 0.97%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 142       | 78.45%  |
| 2     | 35        | 19.34%  |
| 0     | 4         | 2.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 104       | 34.78%  |
| Realtek Semiconductor             | 101       | 33.78%  |
| Qualcomm Atheros                  | 33        | 11.04%  |
| Broadcom                          | 18        | 6.02%   |
| MediaTek                          | 10        | 3.34%   |
| ASIX Electronics                  | 4         | 1.34%   |
| Broadcom Limited                  | 3         | 1%      |
| Xiaomi                            | 2         | 0.67%   |
| Sierra Wireless                   | 2         | 0.67%   |
| Samsung Electronics               | 2         | 0.67%   |
| Marvell Technology Group          | 2         | 0.67%   |
| Lenovo                            | 2         | 0.67%   |
| Dell                              | 2         | 0.67%   |
| U-Blox                            | 1         | 0.33%   |
| Sitecom Europe                    | 1         | 0.33%   |
| Qualcomm                          | 1         | 0.33%   |
| Nvidia                            | 1         | 0.33%   |
| LSI                               | 1         | 0.33%   |
| ICS Advent                        | 1         | 0.33%   |
| Huawei Technologies               | 1         | 0.33%   |
| Ericsson Business Mobile Networks | 1         | 0.33%   |
| ELATEC                            | 1         | 0.33%   |
| DisplayLink                       | 1         | 0.33%   |
| D-Link                            | 1         | 0.33%   |
| Belkin Components                 | 1         | 0.33%   |
| AVM                               | 1         | 0.33%   |
| ASUSTek Computer                  | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 73        | 20.56%  |
| Intel Wi-Fi 6 AX200                                                    | 15        | 4.23%   |
| Intel Wi-Fi 6 AX201                                                    | 11        | 3.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 2.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 6         | 1.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 1.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6         | 1.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 6         | 1.69%   |
| Intel Wireless 8260                                                    | 6         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 1.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 6         | 1.69%   |
| Broadcom BCM43142 802.11b/g/n                                          | 6         | 1.69%   |
| Intel Wireless 7260                                                    | 5         | 1.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 1.41%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 1.13%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4         | 1.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 4         | 1.13%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 4         | 1.13%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 1.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 4         | 1.13%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 1.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 0.85%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 3         | 0.85%   |
| Intel Wireless 8265 / 8275                                             | 3         | 0.85%   |
| Intel Wireless 7265                                                    | 3         | 0.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3         | 0.85%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 3         | 0.85%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 3         | 0.85%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.85%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 0.85%   |
| Intel Ethernet Connection (13) I219-V                                  | 3         | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 3         | 0.85%   |
| Intel Centrino Advanced-N 6200                                         | 3         | 0.85%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.85%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 0.85%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.56%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2         | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 2         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 97        | 52.15%  |
| Qualcomm Atheros      | 29        | 15.59%  |
| Realtek Semiconductor | 26        | 13.98%  |
| Broadcom              | 13        | 6.99%   |
| MediaTek              | 9         | 4.84%   |
| Sierra Wireless       | 2         | 1.08%   |
| Dell                  | 2         | 1.08%   |
| Broadcom Limited      | 2         | 1.08%   |
| Sitecom Europe        | 1         | 0.54%   |
| Qualcomm              | 1         | 0.54%   |
| D-Link                | 1         | 0.54%   |
| Belkin Components     | 1         | 0.54%   |
| AVM                   | 1         | 0.54%   |
| ASUSTek Computer      | 1         | 0.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 15        | 8.06%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 5.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 3.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 3.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 3.23%   |
| Intel Wireless 8260                                                     | 6         | 3.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 3.23%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 3.23%   |
| Intel Wireless 7260                                                     | 5         | 2.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 2.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 2.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 2.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4         | 2.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 2.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.61%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.61%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.61%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.61%   |
| Intel Wireless 7265                                                     | 3         | 1.61%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 3         | 1.61%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                       | 3         | 1.61%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 3         | 1.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.61%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.61%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 1.08%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.08%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.08%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.08%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 2         | 1.08%   |
| Intel Wireless 3160                                                     | 2         | 1.08%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 1.08%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.08%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.08%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.08%   |
| Dell Hub of E-Port Replicator                                           | 2         | 1.08%   |
| Sitecom Europe 802.11n WLAN Adapter                                     | 1         | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 90        | 54.55%  |
| Intel                    | 41        | 24.85%  |
| Broadcom                 | 9         | 5.45%   |
| Qualcomm Atheros         | 6         | 3.64%   |
| ASIX Electronics         | 4         | 2.42%   |
| Xiaomi                   | 2         | 1.21%   |
| Samsung Electronics      | 2         | 1.21%   |
| Marvell Technology Group | 2         | 1.21%   |
| Lenovo                   | 2         | 1.21%   |
| Nvidia                   | 1         | 0.61%   |
| MediaTek                 | 1         | 0.61%   |
| LSI                      | 1         | 0.61%   |
| ICS Advent               | 1         | 0.61%   |
| Huawei Technologies      | 1         | 0.61%   |
| DisplayLink              | 1         | 0.61%   |
| Broadcom Limited         | 1         | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 73        | 43.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 8         | 4.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 6         | 3.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 3.01%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 2.41%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 2.41%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 1.81%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 1.81%   |
| Intel Ethernet Connection (13) I219-V                                  | 3         | 1.81%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.81%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 1.81%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 1.2%    |
| Realtek Killer E2600 GbE Controller                                    | 2         | 1.2%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 1.2%    |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.2%    |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 1.2%    |
| Intel Ethernet Connection (16) I219-V                                  | 2         | 1.2%    |
| Intel 82579V Gigabit Network Connection                                | 2         | 1.2%    |
| Intel 82567LF Gigabit Network Connection                               | 2         | 1.2%    |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 2         | 1.2%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 1.2%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 1.2%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.6%    |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.6%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.6%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1         | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.6%    |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.6%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.6%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 0.6%    |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                   | 1         | 0.6%    |
| LSI ET-131x PCI-E Ethernet Controller                                  | 1         | 0.6%    |
| Lenovo Thinkpad LAN                                                    | 1         | 0.6%    |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]            | 1         | 0.6%    |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller (3)                | 1         | 0.6%    |
| Intel Ethernet Connection I219-V                                       | 1         | 0.6%    |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 0.6%    |
| Intel Ethernet Connection (5) I219-V                                   | 1         | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 174       | 52.25%  |
| Ethernet | 156       | 46.85%  |
| Modem    | 3         | 0.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 129       | 67.54%  |
| Ethernet | 62        | 32.46%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 139       | 76.8%   |
| 1     | 42        | 23.2%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 118       | 64.84%  |
| Yes  | 64        | 35.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 76        | 49.67%  |
| Realtek Semiconductor           | 18        | 11.76%  |
| Foxconn / Hon Hai               | 9         | 5.88%   |
| Qualcomm Atheros Communications | 8         | 5.23%   |
| Broadcom                        | 8         | 5.23%   |
| IMC Networks                    | 7         | 4.58%   |
| Lite-On Technology              | 6         | 3.92%   |
| Hewlett-Packard                 | 5         | 3.27%   |
| Dell                            | 5         | 3.27%   |
| Foxconn International           | 2         | 1.31%   |
| Cambridge Silicon Radio         | 2         | 1.31%   |
| Apple                           | 2         | 1.31%   |
| USI                             | 1         | 0.65%   |
| TP-Link                         | 1         | 0.65%   |
| Realtek                         | 1         | 0.65%   |
| MediaTek                        | 1         | 0.65%   |
| Fujitsu                         | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 19        | 12.42%  |
| Intel AX201 Bluetooth                                                               | 19        | 12.42%  |
| Intel AX200 Bluetooth                                                               | 14        | 9.15%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 13        | 8.5%    |
| Realtek Bluetooth Radio                                                             | 12        | 7.84%   |
| Intel AX211 Bluetooth                                                               | 6         | 3.92%   |
| IMC Networks Wireless_Device                                                        | 4         | 2.61%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 2.61%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.96%   |
| Intel AX210 Bluetooth                                                               | 3         | 1.96%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 3         | 1.96%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 3         | 1.96%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.31%   |
| Realtek 802.11ac WLAN Adapter                                                       | 2         | 1.31%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 1.31%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.31%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.31%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 1.31%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.31%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.31%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.31%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 1.31%   |
| USI Bluetooth Device                                                                | 1         | 0.65%   |
| TP-Link TP-Link Bluetooth USB Adapter                                               | 1         | 0.65%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.65%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.65%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.65%   |
| MediaTek Wireless_Device                                                            | 1         | 0.65%   |
| Lite-On Wireless_Device                                                             | 1         | 0.65%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.65%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.65%   |
| IMC Networks Bluetooth Module                                                       | 1         | 0.65%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.65%   |
| Fujitsu Bluetooth Device                                                            | 1         | 0.65%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.65%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 143       | 62.45%  |
| AMD                    | 46        | 20.09%  |
| Nvidia                 | 23        | 10.04%  |
| Logitech               | 2         | 0.87%   |
| Lenovo                 | 2         | 0.87%   |
| ASUSTek Computer       | 2         | 0.87%   |
| Yamaha                 | 1         | 0.44%   |
| Walmart                | 1         | 0.44%   |
| Realtek Semiconductor  | 1         | 0.44%   |
| Plantronics            | 1         | 0.44%   |
| Kingston Technology    | 1         | 0.44%   |
| GN Netcom              | 1         | 0.44%   |
| Generalplus Technology | 1         | 0.44%   |
| DSEA A/S               | 1         | 0.44%   |
| Cambridge Audio        | 1         | 0.44%   |
| C-Media Electronics    | 1         | 0.44%   |
| Arturia                | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 28        | 10.14%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 20        | 7.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 18        | 6.52%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 5.43%   |
| Intel Sunrise Point-LP HD Audio                                            | 14        | 5.07%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 3.99%   |
| Intel Cannon Lake PCH cAVS                                                 | 10        | 3.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 3.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 2.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 2.54%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 6         | 2.17%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 5         | 1.81%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 1.81%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.81%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 1.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.45%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.45%   |
| Intel Raptor Lake High Definition Audio Controller                         | 4         | 1.45%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.45%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.45%   |
| AMD FCH Azalia Controller                                                  | 4         | 1.45%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.09%   |
| Nvidia GA107 High Definition Audio Controller                              | 3         | 1.09%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.09%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.09%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.09%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 1.09%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.09%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.72%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.72%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 0.72%   |
| Nvidia AD107 High Definition Audio Controller                              | 2         | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.72%   |
| ASUSTek Computer C-Media Audio                                             | 2         | 0.72%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 2         | 0.72%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 0.72%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.72%   |
| AMD High Definition Audio Controller                                       | 2         | 0.72%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 2         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 28.87%  |
| Micron Technology   | 20        | 20.62%  |
| SK hynix            | 19        | 19.59%  |
| Kingston            | 11        | 11.34%  |
| Nanya Technology    | 4         | 4.12%   |
| Unknown             | 2         | 2.06%   |
| Smart               | 2         | 2.06%   |
| Elpida              | 2         | 2.06%   |
| Corsair             | 2         | 2.06%   |
| Team                | 1         | 1.03%   |
| Silicon Power       | 1         | 1.03%   |
| GOODRAM             | 1         | 1.03%   |
| G.Skill             | 1         | 1.03%   |
| Crucial             | 1         | 1.03%   |
| A-DATA Technology   | 1         | 1.03%   |
| Unknown             | 1         | 1.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 5         | 4.81%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 3         | 2.88%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s          | 2         | 1.92%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 2         | 1.92%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 2         | 1.92%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 1.92%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 2         | 1.92%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 2         | 1.92%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s           | 2         | 1.92%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s          | 2         | 1.92%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s           | 2         | 1.92%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s           | 2         | 1.92%   |
| Unknown RAM Module 512MB SODIMM DDR2                           | 1         | 0.96%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 0.96%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s            | 1         | 0.96%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s          | 1         | 0.96%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s          | 1         | 0.96%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s         | 1         | 0.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 0.96%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 0.96%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s         | 1         | 0.96%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s        | 1         | 0.96%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 0.96%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s   | 1         | 0.96%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s   | 1         | 0.96%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 1         | 0.96%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1         | 0.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 1         | 0.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s         | 1         | 0.96%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 1         | 0.96%   |
| SK hynix RAM H58G78BK7BX114 8GB SODIMM LPDDR5 6400MT/s         | 1         | 0.96%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s    | 1         | 0.96%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.96%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 0.96%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR5 6400MT/s            | 1         | 0.96%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                   | 1         | 0.96%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 0.96%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 0.96%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 0.96%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s          | 1         | 0.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 50        | 60.24%  |
| DDR3   | 16        | 19.28%  |
| LPDDR5 | 5         | 6.02%   |
| DDR5   | 5         | 6.02%   |
| LPDDR4 | 3         | 3.61%   |
| DDR2   | 2         | 2.41%   |
| SDRAM  | 1         | 1.2%    |
| LPDDR3 | 1         | 1.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 73        | 86.9%   |
| Row Of Chips | 11        | 13.1%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 45        | 50.56%  |
| 16384 | 15        | 16.85%  |
| 4096  | 15        | 16.85%  |
| 2048  | 8         | 8.99%   |
| 32768 | 5         | 5.62%   |
| 512   | 1         | 1.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 28        | 31.11%  |
| 2667    | 19        | 21.11%  |
| 1600    | 9         | 10%     |
| 2400    | 5         | 5.56%   |
| 1334    | 5         | 5.56%   |
| 6400    | 4         | 4.44%   |
| 5600    | 4         | 4.44%   |
| 2133    | 3         | 3.33%   |
| 4267    | 2         | 2.22%   |
| 1867    | 2         | 2.22%   |
| 1333    | 2         | 2.22%   |
| 7500    | 1         | 1.11%   |
| 4800    | 1         | 1.11%   |
| 3266    | 1         | 1.11%   |
| 2048    | 1         | 1.11%   |
| 1067    | 1         | 1.11%   |
| 975     | 1         | 1.11%   |
| Unknown | 1         | 1.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 2         | 66.67%  |
| Lexmark International | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Lexmark International MC3224dwe | 1         | 33.33%  |
| HP OfficeJet 6950               | 1         | 33.33%  |
| HP DeskJet 4100 series          | 1         | 33.33%  |

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
| Chicony Electronics                    | 40        | 25.32%  |
| IMC Networks                           | 17        | 10.76%  |
| Realtek Semiconductor                  | 11        | 6.96%   |
| Bison Electronics                      | 11        | 6.96%   |
| Luxvisions Innotech Limited            | 10        | 6.33%   |
| Microdia                               | 9         | 5.7%    |
| Syntek                                 | 8         | 5.06%   |
| Quanta                                 | 8         | 5.06%   |
| Suyin                                  | 7         | 4.43%   |
| Sunplus Innovation Technology          | 7         | 4.43%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.53%   |
| Acer                                   | 4         | 2.53%   |
| Sonix Technology                       | 3         | 1.9%    |
| Primax Electronics                     | 3         | 1.9%    |
| Importek                               | 3         | 1.9%    |
| Logitech                               | 2         | 1.27%   |
| Z-Star Microelectronics                | 1         | 0.63%   |
| Sunplus Technology                     | 1         | 0.63%   |
| Samsung Electronics                    | 1         | 0.63%   |
| Ricoh                                  | 1         | 0.63%   |
| Microsoft                              | 1         | 0.63%   |
| Lite-On Technology                     | 1         | 0.63%   |
| Lenovo                                 | 1         | 0.63%   |
| icSpring                               | 1         | 0.63%   |
| Generalplus Technology                 | 1         | 0.63%   |
| Apple                                  | 1         | 0.63%   |
| ALi                                    | 1         | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 9         | 5.7%    |
| Syntek Integrated Camera                                    | 7         | 4.43%   |
| Microdia Integrated_Webcam_HD                               | 5         | 3.16%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 5         | 3.16%   |
| IMC Networks Integrated Camera                              | 5         | 3.16%   |
| Sunplus Integrated_Webcam_HD                                | 4         | 2.53%   |
| Realtek Integrated_Webcam_HD                                | 4         | 2.53%   |
| Chicony HD User Facing                                      | 4         | 2.53%   |
| Primax HP HD Webcam [Fixed]                                 | 3         | 1.9%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera        | 3         | 1.9%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 3         | 1.9%    |
| Chicony HD Webcam                                           | 3         | 1.9%    |
| Bison Integrated Camera                                     | 3         | 1.9%    |
| Acer BisonCam,NB Pro                                        | 3         | 1.9%    |
| Realtek USB2.0 HD UVC WebCam                                | 2         | 1.27%   |
| Quanta VGA WebCam                                           | 2         | 1.27%   |
| Quanta HP TrueVision HD Camera                              | 2         | 1.27%   |
| Quanta HD User Facing                                       | 2         | 1.27%   |
| Microdia Integrated Webcam                                  | 2         | 1.27%   |
| Luxvisions Innotech Limited HP HD Camera                    | 2         | 1.27%   |
| Logitech Webcam C270                                        | 2         | 1.27%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 1.27%   |
| Chicony USB2.0 Camera                                       | 2         | 1.27%   |
| Chicony HP HD Camera                                        | 2         | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 2         | 1.27%   |
| Bison Lenovo Integrated Webcam                              | 2         | 1.27%   |
| Bison HD Webcam                                             | 2         | 1.27%   |
| Z-Star WebCam SC-03FFL11739P                                | 1         | 0.63%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.63%   |
| Suyin USB 2.0 UVC 1.3M WebCam                               | 1         | 0.63%   |
| Suyin Sony Visual Communication Camera                      | 1         | 0.63%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 0.63%   |
| Suyin Integrated Webcam                                     | 1         | 0.63%   |
| Suyin HP Truevision HD                                      | 1         | 0.63%   |
| Suyin HP ENVY HD Webcam                                     | 1         | 0.63%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.63%   |
| Sunplus 1.3M HD WebCam                                      | 1         | 0.63%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 0.63%   |
| Sunplus Laptop Integrated Webcam HD                         | 1         | 0.63%   |
| Sunplus HD WebCam                                           | 1         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 28%     |
| Synaptics                  | 7         | 28%     |
| Shenzhen Goodix Technology | 5         | 20%     |
| Upek                       | 3         | 12%     |
| AuthenTec                  | 2         | 8%      |
| Next Biometrics            | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 4         | 16%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 3         | 12%     |
| Shenzhen Goodix  FingerPrint Device                      | 3         | 12%     |
| Validity Sensors VFS495 Fingerprint Reader               | 2         | 8%      |
| Validity Sensors Synaptics WBDI                          | 2         | 8%      |
| Synaptics UWP WBDI Device                                | 2         | 8%      |
| AuthenTec AES2810                                        | 2         | 8%      |
| Validity Sensors VFS491                                  | 1         | 4%      |
| Validity Sensors VFS451 Fingerprint Reader               | 1         | 4%      |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 4%      |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 4%      |
| Shenzhen Goodix Fingerprint Reader                       | 1         | 4%      |
| Shenzhen Goodix FingerPrint                              | 1         | 4%      |
| Next Biometrics NB-2020-U Fingerprint Reader             | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 11        | 52.38%  |
| Alcor Micro | 6         | 28.57%  |
| O2 Micro    | 2         | 9.52%   |
| Upek        | 1         | 4.76%   |
| Lenovo      | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 19.05%  |
| Broadcom 58200                                                               | 4         | 19.05%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 9.52%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 9.52%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 4.76%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4.76%   |
| Broadcom 5880                                                                | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 99        | 54.7%   |
| 1     | 60        | 33.15%  |
| 2     | 18        | 9.94%   |
| 3     | 3         | 1.66%   |
| 4     | 1         | 0.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 26        | 23.85%  |
| Fingerprint reader    | 25        | 22.94%  |
| Chipcard              | 20        | 18.35%  |
| Net/wireless          | 14        | 12.84%  |
| Sound                 | 7         | 6.42%   |
| Multimedia controller | 6         | 5.5%    |
| Camera                | 6         | 5.5%    |
| Card reader           | 2         | 1.83%   |
| Network               | 1         | 0.92%   |
| Net/ethernet          | 1         | 0.92%   |
| Modem                 | 1         | 0.92%   |

