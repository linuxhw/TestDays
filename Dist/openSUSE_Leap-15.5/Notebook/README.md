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

Total: 195

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 5.14.21-150500.53-default    | 32        | 20%     |
| 5.14.21-150500.55.52-default | 20        | 12.5%   |
| 5.14.21-150500.55.19-default | 19        | 11.88%  |
| 5.14.21-150500.55.39-default | 18        | 11.25%  |
| 5.14.21-150500.55.36-default | 15        | 9.38%   |
| 5.14.21-150500.55.49-default | 14        | 8.75%   |
| 5.14.21-150500.55.31-default | 10        | 6.25%   |
| 5.14.21-150500.55.7-default  | 6         | 3.75%   |
| 5.14.21-150500.55.12-default | 6         | 3.75%   |
| 5.14.21-150500.55.44-default | 5         | 3.13%   |
| 5.14.21-150500.55.59-default | 4         | 2.5%    |
| 5.14.21-150500.52-default    | 4         | 2.5%    |
| 5.14.21-150500.55.28-default | 3         | 1.88%   |
| 6.6.11-lp155.3-default       | 1         | 0.63%   |
| 5.14.21-150500.50-default    | 1         | 0.63%   |
| 5.14.21-150500.49-default    | 1         | 0.63%   |
| 5.14.21-150500.43-default    | 1         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.21 | 146       | 99.32%  |
| 6.6.11  | 1         | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 146       | 99.32%  |
| 6.6     | 1         | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 146       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 106       | 72.6%   |
| GNOME    | 25        | 17.12%  |
| XFCE     | 8         | 5.48%   |
| Cinnamon | 2         | 1.37%   |
| Unknown  | 2         | 1.37%   |
| Trinity  | 1         | 0.68%   |
| KDE      | 1         | 0.68%   |
| ICEWM    | 1         | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 119       | 80.95%  |
| Wayland | 25        | 17.01%  |
| Tty     | 2         | 1.36%   |
| Unknown | 1         | 0.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 87        | 59.18%  |
| SDDM    | 39        | 26.53%  |
| LightDM | 10        | 6.8%    |
| GDM     | 7         | 4.76%   |
| XDM     | 4         | 2.72%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 45        | 30.61%  |
| de_DE           | 36        | 24.49%  |
| POSIX           | 17        | 11.56%  |
| es_ES           | 7         | 4.76%   |
| pt_BR           | 6         | 4.08%   |
| en_GB           | 5         | 3.4%    |
| ru_RU           | 4         | 2.72%   |
| pl_PL           | 4         | 2.72%   |
| it_IT           | 4         | 2.72%   |
| fr_FR           | 4         | 2.72%   |
| nl_NL           | 3         | 2.04%   |
| hu_HU           | 3         | 2.04%   |
| en_DK           | 2         | 1.36%   |
| zh_CN           | 1         | 0.68%   |
| sk_SK           | 1         | 0.68%   |
| ja_JP           | 1         | 0.68%   |
| en_ZA           | 1         | 0.68%   |
| en_US.ISO8859-1 | 1         | 0.68%   |
| cs_CZ           | 1         | 0.68%   |
| Unknown         | 1         | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 91        | 61.9%   |
| EFI  | 56        | 38.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 117       | 80.14%  |
| Ext4  | 25        | 17.12%  |
| Xfs   | 2         | 1.37%   |
| Tmpfs | 2         | 1.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 83        | 56.08%  |
| GPT     | 61        | 41.22%  |
| MBR     | 4         | 2.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 135       | 92.47%  |
| Yes       | 11        | 7.53%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 117       | 79.59%  |
| Yes       | 30        | 20.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 39        | 26.71%  |
| Hewlett-Packard     | 25        | 17.12%  |
| Dell                | 22        | 15.07%  |
| Acer                | 17        | 11.64%  |
| ASUSTek Computer    | 13        | 8.9%    |
| TUXEDO              | 3         | 2.05%   |
| MSI                 | 3         | 2.05%   |
| Medion              | 3         | 2.05%   |
| Toshiba             | 2         | 1.37%   |
| System76            | 2         | 1.37%   |
| Sony                | 2         | 1.37%   |
| Notebook            | 2         | 1.37%   |
| HUAWEI              | 2         | 1.37%   |
| Apple               | 2         | 1.37%   |
| Wortmann AG         | 1         | 0.68%   |
| Schenker            | 1         | 0.68%   |
| Samsung Electronics | 1         | 0.68%   |
| Panasonic           | 1         | 0.68%   |
| Fujitsu Siemens     | 1         | 0.68%   |
| Fujitsu             | 1         | 0.68%   |
| Framework           | 1         | 0.68%   |
| Dynabook            | 1         | 0.68%   |
| Unknown             | 1         | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                                                     | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| TUXEDO Aura 15 Gen2                                                                      | 2         | 1.37%   |
| HP Victus by Gaming Laptop 15-fb0xxx                                                     | 2         | 1.37%   |
| HP Notebook                                                                              | 2         | 1.37%   |
| Unknown                                                                                  | 2         | 1.37%   |
| Wortmann AG TERRA_MOBILE_1749                                                            | 1         | 0.68%   |
| TUXEDO Pulse 15 Gen2                                                                     | 1         | 0.68%   |
| Toshiba Satellite Pro C70-A                                                              | 1         | 0.68%   |
| Toshiba dynabook Satellite B552/H                                                        | 1         | 0.68%   |
| System76 Lemur Pro                                                                       | 1         | 0.68%   |
| System76 Bonobo WS                                                                       | 1         | 0.68%   |
| Sony SVF1521A7EB                                                                         | 1         | 0.68%   |
| Schenker KEY (E23)                                                                       | 1         | 0.68%   |
| Samsung 355V4C/355V4X/355V5C/355V5X/356V4C/356V4X/356V5C/356V5X/3445VC/3445VX/3545VC/354 | 1         | 0.68%   |
| Panasonic CF-C2CUGZXKM                                                                   | 1         | 0.68%   |
| Notebook NS50_70MU                                                                       | 1         | 0.68%   |
| Notebook NLx0MU                                                                          | 1         | 0.68%   |
| MSI Summit E13FlipEvo A11MT                                                              | 1         | 0.68%   |
| MSI Katana GF66 11UE                                                                     | 1         | 0.68%   |
| MSI Cyborg 15 A13VE                                                                      | 1         | 0.68%   |
| Medion S15449                                                                            | 1         | 0.68%   |
| Medion P662X                                                                             | 1         | 0.68%   |
| Medion E6224                                                                             | 1         | 0.68%   |
| Lenovo Y520-15IKBN 80WK                                                                  | 1         | 0.68%   |
| Lenovo V15-IGL 82C3                                                                      | 1         | 0.68%   |
| Lenovo U31-70 80M5                                                                       | 1         | 0.68%   |
| Lenovo ThinkPad X390 20Q1S5K400                                                          | 1         | 0.68%   |
| Lenovo ThinkPad X270 W10DG 20K6S0X900                                                    | 1         | 0.68%   |
| Lenovo ThinkPad X200 7458AH8                                                             | 1         | 0.68%   |
| Lenovo ThinkPad W541 20EGS1LB00                                                          | 1         | 0.68%   |
| Lenovo ThinkPad W500 40624DG                                                             | 1         | 0.68%   |
| Lenovo ThinkPad T530 2394W19                                                             | 1         | 0.68%   |
| Lenovo ThinkPad T490 20N2000LSP                                                          | 1         | 0.68%   |
| Lenovo ThinkPad T470p 20J60014PB                                                         | 1         | 0.68%   |
| Lenovo ThinkPad T470 W10DG 20JNS09G00                                                    | 1         | 0.68%   |
| Lenovo ThinkPad T400 27658JG                                                             | 1         | 0.68%   |
| Lenovo ThinkPad T14s Gen 4 21F8CTO1WW                                                    | 1         | 0.68%   |
| Lenovo ThinkPad T14 Gen 2i 20W00153US                                                    | 1         | 0.68%   |
| Lenovo ThinkPad P53 20QNCTO1WW                                                           | 1         | 0.68%   |
| Lenovo ThinkPad P14s Gen 4 21HFCTO1WW                                                    | 1         | 0.68%   |
| Lenovo ThinkPad L530 24814YG                                                             | 1         | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 21        | 14.38%  |
| Acer Aspire            | 11        | 7.53%   |
| Lenovo IdeaPad         | 6         | 4.11%   |
| HP Laptop              | 6         | 4.11%   |
| HP EliteBook           | 6         | 4.11%   |
| Dell Precision         | 6         | 4.11%   |
| Dell Latitude          | 6         | 4.11%   |
| Lenovo Legion          | 5         | 3.42%   |
| Dell Inspiron          | 5         | 3.42%   |
| Dell Vostro            | 3         | 2.05%   |
| ASUS VivoBook          | 3         | 2.05%   |
| TUXEDO Aura            | 2         | 1.37%   |
| HP Victus              | 2         | 1.37%   |
| HP ProBook             | 2         | 1.37%   |
| HP OMEN                | 2         | 1.37%   |
| HP Notebook            | 2         | 1.37%   |
| HP ENVY                | 2         | 1.37%   |
| ASUS ROG               | 2         | 1.37%   |
| Acer TravelMate        | 2         | 1.37%   |
| Acer Nitro             | 2         | 1.37%   |
| Unknown                | 2         | 1.37%   |
| Wortmann AG TERRA      | 1         | 0.68%   |
| TUXEDO Pulse           | 1         | 0.68%   |
| Toshiba Satellite      | 1         | 0.68%   |
| Toshiba dynabook       | 1         | 0.68%   |
| System76 Lemur         | 1         | 0.68%   |
| System76 Bonobo        | 1         | 0.68%   |
| Sony SVF1521A7EB       | 1         | 0.68%   |
| Schenker KEY           | 1         | 0.68%   |
| Samsung 355V4C         | 1         | 0.68%   |
| Panasonic CF-C2CUGZXKM | 1         | 0.68%   |
| Notebook NS50          | 1         | 0.68%   |
| Notebook NLx0MU        | 1         | 0.68%   |
| MSI Summit             | 1         | 0.68%   |
| MSI Katana             | 1         | 0.68%   |
| MSI Cyborg             | 1         | 0.68%   |
| Medion S15449          | 1         | 0.68%   |
| Medion P662X           | 1         | 0.68%   |
| Medion E6224           | 1         | 0.68%   |
| Lenovo Y520-15IKBN     | 1         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 23        | 15.75%  |
| 2022 | 14        | 9.59%   |
| 2020 | 13        | 8.9%    |
| 2023 | 12        | 8.22%   |
| 2019 | 12        | 8.22%   |
| 2010 | 11        | 7.53%   |
| 2017 | 10        | 6.85%   |
| 2011 | 9         | 6.16%   |
| 2012 | 8         | 5.48%   |
| 2013 | 7         | 4.79%   |
| 2014 | 6         | 4.11%   |
| 2015 | 5         | 3.42%   |
| 2016 | 4         | 2.74%   |
| 2009 | 4         | 2.74%   |
| 2008 | 4         | 2.74%   |
| 2018 | 2         | 1.37%   |
| 2007 | 2         | 1.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 146       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 126       | 86.3%   |
| Enabled  | 20        | 13.7%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 144       | 98.63%  |
| Yes  | 2         | 1.37%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 43        | 29.25%  |
| 16.01-24.0  | 34        | 23.13%  |
| 8.01-16.0   | 27        | 18.37%  |
| 32.01-64.0  | 16        | 10.88%  |
| 3.01-4.0    | 13        | 8.84%   |
| 64.01-256.0 | 7         | 4.76%   |
| 1.01-2.0    | 5         | 3.4%    |
| 24.01-32.0  | 2         | 1.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 52        | 33.77%  |
| 1.01-2.0   | 36        | 23.38%  |
| 3.01-4.0   | 31        | 20.13%  |
| 4.01-8.0   | 23        | 14.94%  |
| 8.01-16.0  | 7         | 4.55%   |
| 0.51-1.0   | 4         | 2.6%    |
| 16.01-24.0 | 1         | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 108       | 73.47%  |
| 2      | 33        | 22.45%  |
| 3      | 6         | 4.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 99        | 67.35%  |
| Yes       | 48        | 32.65%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 125       | 85.62%  |
| No        | 21        | 14.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 96.58%  |
| No        | 5         | 3.42%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 122       | 82.43%  |
| No        | 26        | 17.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| Germany      | 41        | 28.08%  |
| USA          | 18        | 12.33%  |
| Brazil       | 8         | 5.48%   |
| Poland       | 7         | 4.79%   |
| Russia       | 6         | 4.11%   |
| Italy        | 6         | 4.11%   |
| UK           | 5         | 3.42%   |
| Hungary      | 4         | 2.74%   |
| Spain        | 3         | 2.05%   |
| Netherlands  | 3         | 2.05%   |
| India        | 3         | 2.05%   |
| Greece       | 3         | 2.05%   |
| Belgium      | 3         | 2.05%   |
| Ukraine      | 2         | 1.37%   |
| Serbia       | 2         | 1.37%   |
| Mexico       | 2         | 1.37%   |
| France       | 2         | 1.37%   |
| Czechia      | 2         | 1.37%   |
| Colombia     | 2         | 1.37%   |
| Argentina    | 2         | 1.37%   |
| Venezuela    | 1         | 0.68%   |
| Turkey       | 1         | 0.68%   |
| Switzerland  | 1         | 0.68%   |
| Sweden       | 1         | 0.68%   |
| South Africa | 1         | 0.68%   |
| Slovenia     | 1         | 0.68%   |
| Slovakia     | 1         | 0.68%   |
| Senegal      | 1         | 0.68%   |
| Peru         | 1         | 0.68%   |
| Malaysia     | 1         | 0.68%   |
| Japan        | 1         | 0.68%   |
| Ireland      | 1         | 0.68%   |
| Hong Kong    | 1         | 0.68%   |
| Finland      | 1         | 0.68%   |
| Denmark      | 1         | 0.68%   |
| Croatia      | 1         | 0.68%   |
| China        | 1         | 0.68%   |
| Canada       | 1         | 0.68%   |
| Bulgaria     | 1         | 0.68%   |
| Bolivia      | 1         | 0.68%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Munich                      | 4         | 2.68%   |
| Berlin                      | 4         | 2.68%   |
| Warsaw                      | 3         | 2.01%   |
| Hamburg                     | 3         | 2.01%   |
| Budapest                    | 3         | 2.01%   |
| Sao Paulo                   | 2         | 1.34%   |
| Rio de Janeiro              | 2         | 1.34%   |
| Leipzig                     | 2         | 1.34%   |
| Kyiv                        | 2         | 1.34%   |
| Hanover                     | 2         | 1.34%   |
| Bonn                        | 2         | 1.34%   |
| Alcobendas                  | 2         | 1.34%   |
| Zetel                       | 1         | 0.67%   |
| Zagreb                      | 1         | 0.67%   |
| Yokohama                    | 1         | 0.67%   |
| Yekaterinburg               | 1         | 0.67%   |
| Wolfsburg                   | 1         | 0.67%   |
| Wolfratshausen              | 1         | 0.67%   |
| Weilmuenster                | 1         | 0.67%   |
| Waterloo                    | 1         | 0.67%   |
| Waidhofen an der Ybbs       | 1         | 0.67%   |
| Wachtberg                   | 1         | 0.67%   |
| Vechta                      | 1         | 0.67%   |
| Trivandrum                  | 1         | 0.67%   |
| Tolyatti                    | 1         | 0.67%   |
| Tokaj                       | 1         | 0.67%   |
| Sydney                      | 1         | 0.67%   |
| St Petersburg               | 1         | 0.67%   |
| St Louis                    | 1         | 0.67%   |
| Sofia                       | 1         | 0.67%   |
| Sigtuna                     | 1         | 0.67%   |
| Siegen                      | 1         | 0.67%   |
| Seattle                     | 1         | 0.67%   |
| Sao Vicente                 | 1         | 0.67%   |
| Santa Marta                 | 1         | 0.67%   |
| San Diego                   | 1         | 0.67%   |
| San Cristóbal de La Laguna | 1         | 0.67%   |
| San Antonio                 | 1         | 0.67%   |
| Samara                      | 1         | 0.67%   |
| Sainte-Luce-sur-Loire       | 1         | 0.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 43        | 52     | 23.63%  |
| Seagate                     | 15        | 20     | 8.24%   |
| SanDisk                     | 11        | 16     | 6.04%   |
| WDC                         | 10        | 11     | 5.49%   |
| SK hynix                    | 10        | 12     | 5.49%   |
| Intel                       | 10        | 10     | 5.49%   |
| Micron Technology           | 9         | 9      | 4.95%   |
| Kingston                    | 8         | 10     | 4.4%    |
| Unknown                     | 7         | 7      | 3.85%   |
| Toshiba                     | 7         | 9      | 3.85%   |
| Crucial                     | 5         | 5      | 2.75%   |
| Hitachi                     | 4         | 4      | 2.2%    |
| HGST                        | 4         | 4      | 2.2%    |
| China                       | 4         | 5      | 2.2%    |
| Micron/Crucial Technology   | 3         | 4      | 1.65%   |
| KIOXIA                      | 3         | 4      | 1.65%   |
| Kingston Technology Company | 3         | 3      | 1.65%   |
| ADATA Technology            | 3         | 3      | 1.65%   |
| Silicon Motion              | 2         | 2      | 1.1%    |
| Phison Electronics          | 2         | 2      | 1.1%    |
| Apple                       | 2         | 2      | 1.1%    |
| Yangtze Memory Technologies | 1         | 1      | 0.55%   |
| USB                         | 1         | 1      | 0.55%   |
| Union Memory                | 1         | 1      | 0.55%   |
| Transcend                   | 1         | 1      | 0.55%   |
| SPCC                        | 1         | 1      | 0.55%   |
| Realtek Semiconductor       | 1         | 1      | 0.55%   |
| PNY                         | 1         | 2      | 0.55%   |
| Patriot                     | 1         | 1      | 0.55%   |
| Netac                       | 1         | 2      | 0.55%   |
| KXG60ZNV                    | 1         | 1      | 0.55%   |
| GOODRAM                     | 1         | 1      | 0.55%   |
| Gigabyte Technology         | 1         | 1      | 0.55%   |
| Dogfish                     | 1         | 1      | 0.55%   |
| BR                          | 1         | 1      | 0.55%   |
| ASMT                        | 1         | 1      | 0.55%   |
| A-DATA Technology           | 1         | 1      | 0.55%   |
| Unknown                     | 1         | 1      | 0.55%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB              | 9         | 4.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB               | 7         | 3.76%   |
| Intel SSD 660P Series 1024GB                                    | 5         | 2.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                              | 3         | 1.61%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                              | 3         | 1.61%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB                | 3         | 1.61%   |
| Samsung SSD 840 EVO 250GB                                       | 3         | 1.61%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                             | 3         | 1.61%   |
| Unknown MMC Card  32GB                                          | 2         | 1.08%   |
| Unknown MMC Card  16GB                                          | 2         | 1.08%   |
| Toshiba MQ04ABF100 1TB                                          | 2         | 1.08%   |
| Seagate ST500LM012 HN-M500MBB 500GB                             | 2         | 1.08%   |
| Samsung SSD 870 EVO 1TB                                         | 2         | 1.08%   |
| Samsung SSD 860 EVO 1TB                                         | 2         | 1.08%   |
| Samsung MZALQ256HAJD-000L2 256GB                                | 2         | 1.08%   |
| KIOXIA KBG40ZNV256G 256GB                                       | 2         | 1.08%   |
| Kingston SNVS500G 500GB                                         | 2         | 1.08%   |
| Kingston SA400S37120G 120GB SSD                                 | 2         | 1.08%   |
| Intel SSD Pro 7600p/760p/E 6100p Series 256GB                   | 2         | 1.08%   |
| HGST HTS541010A9E680 1TB                                        | 2         | 1.08%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1TB | 2         | 1.08%   |
| Yangtze Memory ZHITAI TiPlus5000 1TB                            | 1         | 0.54%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                                | 1         | 0.54%   |
| WDC WDS240G2G0C-00AJM0 240GB                                    | 1         | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 1         | 0.54%   |
| WDC WD5000LPVX-16V0TT3 500GB                                    | 1         | 0.54%   |
| WDC WD5000LPVT-08G33T1 500GB                                    | 1         | 0.54%   |
| WDC WD3200BPVT-24ZEST0 320GB                                    | 1         | 0.54%   |
| WDC WD3200BEVT-22A23T0 320GB                                    | 1         | 0.54%   |
| WDC WD3200BEKT-75PVMT0 320GB                                    | 1         | 0.54%   |
| WDC WD20SPZX-21UA7T0 2TB                                        | 1         | 0.54%   |
| WDC WD12 00BEVS-07LAT0 120GB                                    | 1         | 0.54%   |
| USB SanDisk 3.2Gen1 128GB                                       | 1         | 0.54%   |
| Unknown USB DISK 3.2 1TB                                        | 1         | 0.54%   |
| Unknown MMC Card  8GB                                           | 1         | 0.54%   |
| Unknown MMC Card  64GB                                          | 1         | 0.54%   |
| Union Memory UMIS RPJTJ512MEE1OWX 512GB                         | 1         | 0.54%   |
| Transcend TS256GMTS430S 256GB SSD                               | 1         | 0.54%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                          | 1         | 0.54%   |
| Toshiba THNSNK128GVN8 128GB SSD                                 | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 12        | 14     | 38.71%  |
| WDC     | 7         | 7      | 22.58%  |
| Hitachi | 4         | 4      | 12.9%   |
| HGST    | 4         | 4      | 12.9%   |
| Toshiba | 3         | 3      | 9.68%   |
| Apple   | 1         | 1      | 3.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 21     | 32.69%  |
| Crucial             | 5         | 5      | 9.62%   |
| Kingston            | 4         | 4      | 7.69%   |
| China               | 4         | 5      | 7.69%   |
| Toshiba             | 3         | 4      | 5.77%   |
| WDC                 | 2         | 3      | 3.85%   |
| SanDisk             | 2         | 6      | 3.85%   |
| Micron Technology   | 2         | 2      | 3.85%   |
| Transcend           | 1         | 1      | 1.92%   |
| SPCC                | 1         | 1      | 1.92%   |
| SK hynix            | 1         | 1      | 1.92%   |
| PNY                 | 1         | 2      | 1.92%   |
| Patriot             | 1         | 1      | 1.92%   |
| Netac               | 1         | 2      | 1.92%   |
| Intel               | 1         | 1      | 1.92%   |
| GOODRAM             | 1         | 1      | 1.92%   |
| Gigabyte Technology | 1         | 1      | 1.92%   |
| Dogfish             | 1         | 1      | 1.92%   |
| ASMT                | 1         | 1      | 1.92%   |
| Apple               | 1         | 1      | 1.92%   |
| A-DATA Technology   | 1         | 1      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 78        | 101    | 46.99%  |
| SSD     | 47        | 65     | 28.31%  |
| HDD     | 30        | 33     | 18.07%  |
| MMC     | 7         | 7      | 4.22%   |
| Unknown | 4         | 7      | 2.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 78        | 100    | 47.27%  |
| SATA | 73        | 96     | 44.24%  |
| SAS  | 7         | 10     | 4.24%   |
| MMC  | 7         | 7      | 4.24%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 54        | 61     | 66.67%  |
| 0.51-1.0   | 22        | 32     | 27.16%  |
| 1.01-2.0   | 3         | 3      | 3.7%    |
| 3.01-4.0   | 2         | 2      | 2.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| More than 3000 | 46        | 31.29%  |
| 1001-2000      | 30        | 20.41%  |
| 501-1000       | 20        | 13.61%  |
| 2001-3000      | 19        | 12.93%  |
| 251-500        | 17        | 11.56%  |
| 101-250        | 9         | 6.12%   |
| 21-50          | 3         | 2.04%   |
| 51-100         | 2         | 1.36%   |
| Unknown        | 1         | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 47        | 30.72%  |
| 51-100         | 34        | 22.22%  |
| 251-500        | 24        | 15.69%  |
| 501-1000       | 14        | 9.15%   |
| 1-20           | 12        | 7.84%   |
| 1001-2000      | 8         | 5.23%   |
| More than 3000 | 7         | 4.58%   |
| 21-50          | 4         | 2.61%   |
| 2001-3000      | 2         | 1.31%   |
| Unknown        | 1         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZALQ256HBJD-00BL2 256GB | 1         | 1      | 33.33%  |
| Intel SSD 600P Series 256GB                  | 1         | 1      | 33.33%  |
| Hitachi HTS727550A9E364 500GB                | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 33.33%  |
| Intel               | 1         | 1      | 33.33%  |
| Hitachi             | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 2         | 2      | 66.67%  |
| HDD  | 1         | 1      | 33.33%  |

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
| Detected | 87        | 126    | 56.49%  |
| Works    | 64        | 84     | 41.56%  |
| Malfunc  | 3         | 3      | 1.95%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 97        | 50.52%  |
| Samsung Electronics          | 27        | 14.06%  |
| AMD                          | 14        | 7.29%   |
| SanDisk                      | 10        | 5.21%   |
| SK hynix                     | 9         | 4.69%   |
| Micron Technology            | 7         | 3.65%   |
| Kingston Technology Company  | 7         | 3.65%   |
| Micron/Crucial Technology    | 3         | 1.56%   |
| KIOXIA                       | 3         | 1.56%   |
| ADATA Technology             | 3         | 1.56%   |
| Toshiba America Info Systems | 2         | 1.04%   |
| Silicon Motion               | 2         | 1.04%   |
| Seagate Technology           | 2         | 1.04%   |
| Phison Electronics           | 2         | 1.04%   |
| Yangtze Memory Technologies  | 1         | 0.52%   |
| Union Memory (Shenzhen)      | 1         | 0.52%   |
| Realtek Semiconductor        | 1         | 0.52%   |
| Nvidia                       | 1         | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 12        | 5.66%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 5.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 4.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 4.25%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 9         | 4.25%   |
| Intel Volume Management Device NVMe RAID Controller                            | 9         | 4.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 3.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 3.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 3.3%    |
| Intel Tiger Lake-LP SATA Controller                                            | 6         | 2.83%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 2.36%   |
| Intel SSD 660P Series                                                          | 5         | 2.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.89%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 4         | 1.89%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.89%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 1.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 4         | 1.89%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3         | 1.42%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3         | 1.42%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 1.42%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.42%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 1.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 1.42%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.42%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 2         | 0.94%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                     | 2         | 0.94%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.94%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 2         | 0.94%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 0.94%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                             | 2         | 0.94%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 2         | 0.94%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 0.94%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 2         | 0.94%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 2         | 0.94%   |
| Yangtze Memory ZHITAI TiPro5000 NVMe SSD                                       | 1         | 0.47%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 512GB                          | 1         | 0.47%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 97        | 49.24%  |
| NVMe | 78        | 39.59%  |
| RAID | 15        | 7.61%   |
| IDE  | 7         | 3.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 115       | 78.77%  |
| AMD    | 31        | 21.23%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 6         | 4.11%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 5         | 3.42%   |
| AMD Ryzen 5 5500U with Radeon Graphics   | 5         | 3.42%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 3         | 2.05%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 3         | 2.05%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 3         | 2.05%   |
| Intel Core i3-2310M CPU @ 2.10GHz        | 3         | 2.05%   |
| Intel 13th Gen Core i9-13900HX           | 3         | 2.05%   |
| AMD Ryzen 7 5700U with Radeon Graphics   | 3         | 2.05%   |
| AMD Ryzen 5 5600H with Radeon Graphics   | 3         | 2.05%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz       | 2         | 1.37%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 2         | 1.37%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 2         | 1.37%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 2         | 1.37%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 2         | 1.37%   |
| Intel Core i3 CPU M 380 @ 2.53GHz        | 2         | 1.37%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz     | 2         | 1.37%   |
| Intel Celeron N4020 CPU @ 1.10GHz        | 2         | 1.37%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz  | 2         | 1.37%   |
| AMD Ryzen 7 5800H with Radeon Graphics   | 2         | 1.37%   |
| Intel Xeon E-2276M CPU @ 2.80GHz         | 1         | 0.68%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz     | 1         | 0.68%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 1         | 0.68%   |
| Intel Pentium Gold 7505 @ 2.00GHz        | 1         | 0.68%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz   | 1         | 0.68%   |
| Intel Pentium CPU P6100 @ 2.00GHz        | 1         | 0.68%   |
| Intel Pentium CPU P6000 @ 1.87GHz        | 1         | 0.68%   |
| Intel Pentium CPU 2117U @ 1.80GHz        | 1         | 0.68%   |
| Intel Pentium CPU 2020M @ 2.40GHz        | 1         | 0.68%   |
| Intel Core i7-9850H CPU @ 2.60GHz        | 1         | 0.68%   |
| Intel Core i7-8850H CPU @ 2.60GHz        | 1         | 0.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 1         | 0.68%   |
| Intel Core i7-7500U CPU @ 2.70GHz        | 1         | 0.68%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 1         | 0.68%   |
| Intel Core i7-5500U CPU @ 2.40GHz        | 1         | 0.68%   |
| Intel Core i7-4940MX CPU @ 3.10GHz       | 1         | 0.68%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz       | 1         | 0.68%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz       | 1         | 0.68%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz       | 1         | 0.68%   |
| Intel Core i7-4600U CPU @ 2.10GHz        | 1         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Other                | 30        | 20.55%  |
| Intel Core i7        | 29        | 19.86%  |
| Intel Core i5        | 23        | 15.75%  |
| Intel Core i3        | 12        | 8.22%   |
| AMD Ryzen 5          | 12        | 8.22%   |
| AMD Ryzen 7          | 9         | 6.16%   |
| Intel Core 2 Duo     | 7         | 4.79%   |
| Intel Pentium        | 4         | 2.74%   |
| Intel Celeron        | 4         | 2.74%   |
| AMD Ryzen 7 PRO      | 3         | 2.05%   |
| Intel Xeon           | 2         | 1.37%   |
| AMD A6               | 2         | 1.37%   |
| Intel Pentium Silver | 1         | 0.68%   |
| Intel Pentium Gold   | 1         | 0.68%   |
| Intel Pentium Dual   | 1         | 0.68%   |
| Intel Core 2 Extreme | 1         | 0.68%   |
| AMD Ryzen 3          | 1         | 0.68%   |
| AMD FX               | 1         | 0.68%   |
| AMD Athlon X2        | 1         | 0.68%   |
| AMD Athlon           | 1         | 0.68%   |
| AMD A8               | 1         | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 58        | 39.73%  |
| 4      | 42        | 28.77%  |
| 6      | 19        | 13.01%  |
| 8      | 15        | 10.27%  |
| 24     | 3         | 2.05%   |
| 14     | 3         | 2.05%   |
| 12     | 3         | 2.05%   |
| 10     | 2         | 1.37%   |
| 1      | 1         | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 146       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 123       | 84.25%  |
| 1      | 23        | 15.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 146       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 55.1%   |
| 0x806c1    | 10        | 6.8%    |
| 0x806ec    | 5         | 3.4%    |
| 0x08608103 | 5         | 3.4%    |
| 0x906ea    | 3         | 2.04%   |
| 0x406e3    | 3         | 2.04%   |
| 0x306a9    | 3         | 2.04%   |
| 0xb0671    | 2         | 1.36%   |
| 0x906a3    | 2         | 1.36%   |
| 0x806e9    | 2         | 1.36%   |
| 0x40651    | 2         | 1.36%   |
| 0x1067a    | 2         | 1.36%   |
| 0x0a50000d | 2         | 1.36%   |
| 0x0a50000c | 2         | 1.36%   |
| 0x08608102 | 2         | 1.36%   |
| 0x08600106 | 2         | 1.36%   |
| 0xb06a2    | 1         | 0.68%   |
| 0x906ed    | 1         | 0.68%   |
| 0x906e9    | 1         | 0.68%   |
| 0x806ea    | 1         | 0.68%   |
| 0x806d1    | 1         | 0.68%   |
| 0x806c2    | 1         | 0.68%   |
| 0x706e5    | 1         | 0.68%   |
| 0x706a8    | 1         | 0.68%   |
| 0x306d4    | 1         | 0.68%   |
| 0x306c3    | 1         | 0.68%   |
| 0x20655    | 1         | 0.68%   |
| 0x106e5    | 1         | 0.68%   |
| 0x10676    | 1         | 0.68%   |
| 0x0a704103 | 1         | 0.68%   |
| 0x0a601203 | 1         | 0.68%   |
| 0x0a50000f | 1         | 0.68%   |
| 0x0a404102 | 1         | 0.68%   |
| 0x0a404101 | 1         | 0.68%   |
| 0x03000027 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 23        | 15.75%  |
| KabyLake         | 19        | 13.01%  |
| TigerLake        | 15        | 10.27%  |
| Haswell          | 12        | 8.22%   |
| IvyBridge        | 11        | 7.53%   |
| Zen 3            | 9         | 6.16%   |
| SandyBridge      | 8         | 5.48%   |
| Westmere         | 7         | 4.79%   |
| Skylake          | 7         | 4.79%   |
| Penryn           | 6         | 4.11%   |
| Alderlake Hybrid | 5         | 3.42%   |
| Broadwell        | 4         | 2.74%   |
| Zen 2            | 3         | 2.05%   |
| Icelake          | 3         | 2.05%   |
| Goldmont plus    | 3         | 2.05%   |
| Core             | 3         | 2.05%   |
| Nehalem          | 2         | 1.37%   |
| K10 Llano        | 2         | 1.37%   |
| Zen+             | 1         | 0.68%   |
| Piledriver       | 1         | 0.68%   |
| K8 & K10 hybrid  | 1         | 0.68%   |
| Excavator        | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 105       | 53.85%  |
| Nvidia | 50        | 25.64%  |
| AMD    | 40        | 20.51%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 13        | 6.5%    |
| Intel 3rd Gen Core processor Graphics Controller                                      | 10        | 5%      |
| AMD Lucienne                                                                          | 9         | 4.5%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 7         | 3.5%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 7         | 3.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 6         | 3%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 6         | 3%      |
| Intel Core Processor Integrated Graphics Controller                                   | 5         | 2.5%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 5         | 2.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 4         | 2%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 2%      |
| Intel HD Graphics 5500                                                                | 4         | 2%      |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 4         | 2%      |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 3         | 1.5%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 1.5%    |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                       | 3         | 1.5%    |
| Intel Raptor Lake-S UHD Graphics                                                      | 3         | 1.5%    |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 3         | 1.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 3         | 1.5%    |
| Intel HD Graphics 620                                                                 | 3         | 1.5%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 3         | 1.5%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                         | 3         | 1.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 2         | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 1%      |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 2         | 1%      |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 2         | 1%      |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 2         | 1%      |
| Nvidia GA107BM [GeForce RTX 3050 Ti Mobile]                                           | 2         | 1%      |
| Intel UHD Graphics 620                                                                | 2         | 1%      |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 2         | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                   | 2         | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                     | 2         | 1%      |
| Intel HD Graphics 630                                                                 | 2         | 1%      |
| Intel GeminiLake [UHD Graphics 600]                                                   | 2         | 1%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 1%      |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 1%      |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 2         | 1%      |
| AMD Rembrandt [Radeon 680M]                                                           | 2         | 1%      |
| AMD Barcelo                                                                           | 2         | 1%      |
| Nvidia TU117M [GeForce MX450]                                                         | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 63        | 43.15%  |
| Intel + Nvidia | 33        | 22.6%   |
| 1 x AMD        | 21        | 14.38%  |
| 1 x Nvidia     | 10        | 6.85%   |
| Intel + AMD    | 9         | 6.16%   |
| AMD + Nvidia   | 7         | 4.79%   |
| 2 x AMD        | 3         | 2.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 126       | 86.3%   |
| Proprietary | 17        | 11.64%  |
| Unknown     | 3         | 2.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 110       | 75.34%  |
| 1.01-2.0   | 13        | 8.9%    |
| 0.01-0.5   | 13        | 8.9%    |
| 7.01-8.0   | 4         | 2.74%   |
| 3.01-4.0   | 4         | 2.74%   |
| 0.51-1.0   | 2         | 1.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 34        | 19.54%  |
| BOE                     | 26        | 14.94%  |
| LG Display              | 25        | 14.37%  |
| Chimei Innolux          | 23        | 13.22%  |
| Samsung Electronics     | 16        | 9.2%    |
| Sony                    | 5         | 2.87%   |
| Sharp                   | 5         | 2.87%   |
| Lenovo                  | 5         | 2.87%   |
| Goldstar                | 4         | 2.3%    |
| Dell                    | 4         | 2.3%    |
| Chi Mei Optoelectronics | 4         | 2.3%    |
| CSO                     | 3         | 1.72%   |
| BenQ                    | 3         | 1.72%   |
| HKC                     | 2         | 1.15%   |
| Apple                   | 2         | 1.15%   |
| AOC                     | 2         | 1.15%   |
| Toshiba                 | 1         | 0.57%   |
| SANYO                   | 1         | 0.57%   |
| PANDA                   | 1         | 0.57%   |
| IPS                     | 1         | 0.57%   |
| Insignia                | 1         | 0.57%   |
| Iiyama                  | 1         | 0.57%   |
| IBM                     | 1         | 0.57%   |
| Hewlett-Packard         | 1         | 0.57%   |
| GreenWood               | 1         | 0.57%   |
| Eizo                    | 1         | 0.57%   |
| ASUSTek Computer        | 1         | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 4         | 2.3%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 1.72%   |
| Sony TV *00 SNY4904 3840x2160                                            | 2         | 1.15%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 1.15%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 1.15%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 1.15%   |
| BOE LCD Monitor BOE0BB7 3840x2160 381x214mm 17.2-inch                    | 2         | 1.15%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 2         | 1.15%   |
| AU Optronics LCD Monitor AUOFA9B 1920x1200 301x188mm 14.0-inch           | 2         | 1.15%   |
| AU Optronics LCD Monitor AUO41EC 1366x768 344x193mm 15.5-inch            | 2         | 1.15%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 1.15%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch           | 2         | 1.15%   |
| AU Optronics LCD Monitor AUO119E 1600x900 382x214mm 17.2-inch            | 2         | 1.15%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                    | 1         | 0.57%   |
| Sony TV SNYEE01 1920x1080                                                | 1         | 0.57%   |
| Sony TV *00 SNYF303 1920x1080 1218x685mm 55.0-inch                       | 1         | 0.57%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 0.57%   |
| Sharp LQ156D1JW04 SHP1436 3840x2160 346x194mm 15.6-inch                  | 1         | 0.57%   |
| Sharp LQ134N1JW53 SHP1521 1920x1200 288x180mm 13.4-inch                  | 1         | 0.57%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                  | 1         | 0.57%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 1         | 0.57%   |
| Sharp LCD Monitor SHP1446 3840x2160 382x215mm 17.3-inch                  | 1         | 0.57%   |
| SANYO LCD SAN0B75 1920x540                                               | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                         | 1         | 0.57%   |
| Samsung Electronics SyncMaster SAM0586 1920x1200 518x324mm 24.1-inch     | 1         | 0.57%   |
| Samsung Electronics SMB2330H SAM064A 1920x1080 509x286mm 23.0-inch       | 1         | 0.57%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch        | 1         | 0.57%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch        | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC5443 1920x1200 367x230mm 17.1-inch    | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch     | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC5244 1600x900 360x210mm 16.4-inch     | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch     | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch    | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch     | 1         | 0.57%   |
| Samsung Electronics LCD Monitor SDC280F 1366x768 344x193mm 15.5-inch     | 1         | 0.57%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch                  | 1         | 0.57%   |
| LG Display LP156WH3-TLA2 LGD0210 1366x768 345x194mm 15.6-inch            | 1         | 0.57%   |
| LG Display LCD Monitor LGD071E 1920x1080 344x194mm 15.5-inch             | 1         | 0.57%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 71        | 43.03%  |
| 1366x768 (WXGA)    | 36        | 21.82%  |
| 3840x2160 (4K)     | 12        | 7.27%   |
| 1600x900 (HD+)     | 10        | 6.06%   |
| 1920x1200 (WUXGA)  | 7         | 4.24%   |
| 2560x1600          | 6         | 3.64%   |
| 2560x1440 (QHD)    | 6         | 3.64%   |
| 1440x900 (WXGA+)   | 4         | 2.42%   |
| 1280x800 (WXGA)    | 4         | 2.42%   |
| 2880x1800          | 1         | 0.61%   |
| 2560x1080          | 1         | 0.61%   |
| 2520x1680          | 1         | 0.61%   |
| 2256x1504          | 1         | 0.61%   |
| 2160x1440          | 1         | 0.61%   |
| 1920x540           | 1         | 0.61%   |
| 1680x1050 (WSXGA+) | 1         | 0.61%   |
| 1280x1024 (SXGA)   | 1         | 0.61%   |
| 1024x768 (XGA)     | 1         | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 74        | 42.77%  |
| 17      | 23        | 13.29%  |
| 14      | 17        | 9.83%   |
| 13      | 12        | 6.94%   |
| 16      | 10        | 5.78%   |
| 27      | 7         | 4.05%   |
| 24      | 6         | 3.47%   |
| 12      | 5         | 2.89%   |
| 23      | 4         | 2.31%   |
| 72      | 3         | 1.73%   |
| 21      | 3         | 1.73%   |
| Unknown | 2         | 1.16%   |
| 86      | 1         | 0.58%   |
| 75      | 1         | 0.58%   |
| 40      | 1         | 0.58%   |
| 38      | 1         | 0.58%   |
| 34      | 1         | 0.58%   |
| 33      | 1         | 0.58%   |
| 28      | 1         | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 101       | 58.72%  |
| 351-400     | 26        | 15.12%  |
| 501-600     | 15        | 8.72%   |
| 201-300     | 13        | 7.56%   |
| 1501-2000   | 4         | 2.33%   |
| 601-700     | 3         | 1.74%   |
| 401-500     | 3         | 1.74%   |
| 801-900     | 2         | 1.16%   |
| 701-800     | 2         | 1.16%   |
| Unknown     | 2         | 1.16%   |
| 1001-1500   | 1         | 0.58%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 120       | 79.47%  |
| 16/10 | 23        | 15.23%  |
| 3/2   | 3         | 1.99%   |
| 5/4   | 1         | 0.66%   |
| 4/3   | 1         | 0.66%   |
| 32/9  | 1         | 0.66%   |
| 21/9  | 1         | 0.66%   |
| 0.56  | 1         | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 75        | 43.35%  |
| 81-90          | 24        | 13.87%  |
| 121-130        | 18        | 10.4%   |
| 111-120        | 9         | 5.2%    |
| 301-350        | 7         | 4.05%   |
| 201-250        | 6         | 3.47%   |
| More than 1000 | 5         | 2.89%   |
| 71-80          | 5         | 2.89%   |
| 61-70          | 5         | 2.89%   |
| 251-300        | 5         | 2.89%   |
| 131-140        | 4         | 2.31%   |
| 351-500        | 3         | 1.73%   |
| 151-200        | 2         | 1.16%   |
| 501-1000       | 2         | 1.16%   |
| Unknown        | 2         | 1.16%   |
| 141-150        | 1         | 0.58%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 69        | 40.59%  |
| 101-120       | 41        | 24.12%  |
| 51-100        | 29        | 17.06%  |
| 161-240       | 20        | 11.76%  |
| More than 240 | 6         | 3.53%   |
| 1-50          | 3         | 1.76%   |
| Unknown       | 2         | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 112       | 76.71%  |
| 2     | 31        | 21.23%  |
| 0     | 3         | 2.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 82        | 34.02%  |
| Intel                             | 82        | 34.02%  |
| Qualcomm Atheros                  | 26        | 10.79%  |
| Broadcom                          | 16        | 6.64%   |
| MediaTek                          | 8         | 3.32%   |
| Broadcom Limited                  | 3         | 1.24%   |
| ASIX Electronics                  | 3         | 1.24%   |
| Xiaomi                            | 2         | 0.83%   |
| Marvell Technology Group          | 2         | 0.83%   |
| Lenovo                            | 2         | 0.83%   |
| Dell                              | 2         | 0.83%   |
| U-Blox                            | 1         | 0.41%   |
| Sierra Wireless                   | 1         | 0.41%   |
| Samsung Electronics               | 1         | 0.41%   |
| Qualcomm                          | 1         | 0.41%   |
| Nvidia                            | 1         | 0.41%   |
| ICS Advent                        | 1         | 0.41%   |
| Huawei Technologies               | 1         | 0.41%   |
| Ericsson Business Mobile Networks | 1         | 0.41%   |
| DisplayLink                       | 1         | 0.41%   |
| D-Link                            | 1         | 0.41%   |
| Belkin Components                 | 1         | 0.41%   |
| AVM                               | 1         | 0.41%   |
| ASUSTek Computer                  | 1         | 0.41%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 60        | 21.05%  |
| Intel Wi-Fi 6 AX200                                                     | 13        | 4.56%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 2.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 6         | 2.11%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 1.75%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 4         | 1.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.4%    |
| Intel Wireless 8260                                                     | 4         | 1.4%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4         | 1.4%    |
| Intel Ethernet Connection (7) I219-LM                                   | 4         | 1.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 1.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4         | 1.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.05%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 1.05%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.05%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.05%   |
| Intel Wireless 7260                                                     | 3         | 1.05%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 3         | 1.05%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                       | 3         | 1.05%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 3         | 1.05%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.05%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 1.05%   |
| ASIX AX88179 Gigabit Ethernet                                           | 3         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.7%    |
| Realtek Killer E2600 GbE Controller                                     | 2         | 0.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.7%    |
| Intel Wireless 3160                                                     | 2         | 0.7%    |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.7%    |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.7%    |
| Intel Ethernet Connection I219-LM                                       | 2         | 0.7%    |
| Intel Ethernet Connection I218-LM                                       | 2         | 0.7%    |
| Intel Ethernet Connection I217-LM                                       | 2         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 77        | 51.33%  |
| Qualcomm Atheros      | 23        | 15.33%  |
| Realtek Semiconductor | 20        | 13.33%  |
| Broadcom              | 12        | 8%      |
| MediaTek              | 8         | 5.33%   |
| Dell                  | 2         | 1.33%   |
| Broadcom Limited      | 2         | 1.33%   |
| Sierra Wireless       | 1         | 0.67%   |
| Qualcomm              | 1         | 0.67%   |
| D-Link                | 1         | 0.67%   |
| Belkin Components     | 1         | 0.67%   |
| AVM                   | 1         | 0.67%   |
| ASUSTek Computer      | 1         | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 13        | 8.67%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 5.33%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 4%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 3.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 3.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 3.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 2.67%   |
| Intel Wireless 8260                                                     | 4         | 2.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4         | 2.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 3         | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 2%      |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 2%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 3         | 2%      |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 3         | 2%      |
| Intel Wireless 8265 / 8275                                              | 3         | 2%      |
| Intel Wireless 7260                                                     | 3         | 2%      |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 3         | 2%      |
| Intel Raptor Lake-S PCH CNVi WiFi                                       | 3         | 2%      |
| Intel Raptor Lake PCH CNVi WiFi                                         | 3         | 2%      |
| Intel Centrino Advanced-N 6200                                          | 3         | 2%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.33%   |
| Intel Wireless 3160                                                     | 2         | 1.33%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 1.33%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.33%   |
| Dell Hub of E-Port Replicator                                           | 2         | 1.33%   |
| Sierra Wireless EM7455                                                  | 1         | 0.67%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1         | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.67%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.67%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.67%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 1         | 0.67%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 73        | 54.89%  |
| Intel                    | 32        | 24.06%  |
| Broadcom                 | 8         | 6.02%   |
| Qualcomm Atheros         | 5         | 3.76%   |
| ASIX Electronics         | 3         | 2.26%   |
| Xiaomi                   | 2         | 1.5%    |
| Marvell Technology Group | 2         | 1.5%    |
| Lenovo                   | 2         | 1.5%    |
| Samsung Electronics      | 1         | 0.75%   |
| Nvidia                   | 1         | 0.75%   |
| ICS Advent               | 1         | 0.75%   |
| Huawei Technologies      | 1         | 0.75%   |
| DisplayLink              | 1         | 0.75%   |
| Broadcom Limited         | 1         | 0.75%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 60        | 45.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6         | 4.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 3.01%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4         | 3.01%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 3.01%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 2.26%   |
| ASIX AX88179 Gigabit Ethernet                                          | 3         | 2.26%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 1.5%    |
| Intel Ethernet Connection I219-LM                                      | 2         | 1.5%    |
| Intel Ethernet Connection I218-LM                                      | 2         | 1.5%    |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.5%    |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 1.5%    |
| Intel Ethernet Connection (13) I219-V                                  | 2         | 1.5%    |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.5%    |
| Intel 82567LF Gigabit Network Connection                               | 2         | 1.5%    |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 2         | 1.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 1.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.75%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 1         | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.75%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 1         | 0.75%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.75%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.75%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 0.75%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                   | 1         | 0.75%   |
| Lenovo Thinkpad LAN                                                    | 1         | 0.75%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]            | 1         | 0.75%   |
| Intel Killer E3100X 2.5 Gigabit Ethernet Controller (3)                | 1         | 0.75%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.75%   |
| Intel Ethernet Connection (5) I219-V                                   | 1         | 0.75%   |
| Intel Ethernet Connection (23) I219-LM                                 | 1         | 0.75%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 0.75%   |
| Intel Ethernet Connection (14) I219-LM                                 | 1         | 0.75%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 0.75%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                | 1         | 0.75%   |
| Huawei E353/E3131                                                      | 1         | 0.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 141       | 52.42%  |
| Ethernet | 126       | 46.84%  |
| Modem    | 2         | 0.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 106       | 70.2%   |
| Ethernet | 45        | 29.8%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 112       | 76.71%  |
| 1     | 34        | 23.29%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 94        | 63.95%  |
| Yes  | 53        | 36.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 59        | 47.58%  |
| Realtek Semiconductor           | 14        | 11.29%  |
| Foxconn / Hon Hai               | 9         | 7.26%   |
| Qualcomm Atheros Communications | 8         | 6.45%   |
| Broadcom                        | 7         | 5.65%   |
| Lite-On Technology              | 6         | 4.84%   |
| IMC Networks                    | 4         | 3.23%   |
| Hewlett-Packard                 | 4         | 3.23%   |
| Dell                            | 4         | 3.23%   |
| Foxconn International           | 2         | 1.61%   |
| Apple                           | 2         | 1.61%   |
| USI                             | 1         | 0.81%   |
| TP-Link                         | 1         | 0.81%   |
| Realtek                         | 1         | 0.81%   |
| MediaTek                        | 1         | 0.81%   |
| Cambridge Silicon Radio         | 1         | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 14        | 11.29%  |
| Intel AX200 Bluetooth                                                               | 13        | 10.48%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 7.26%   |
| Realtek Bluetooth Radio                                                             | 8         | 6.45%   |
| Intel Bluetooth Device                                                              | 7         | 5.65%   |
| Intel Bluetooth wireless interface                                                  | 6         | 4.84%   |
| Intel AX211 Bluetooth                                                               | 6         | 4.84%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 2.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 2.42%   |
| Intel AX210 Bluetooth                                                               | 3         | 2.42%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 2.42%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 3         | 2.42%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 3         | 2.42%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.61%   |
| Realtek 802.11ac WLAN Adapter                                                       | 2         | 1.61%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 2         | 1.61%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.61%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 1.61%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.61%   |
| USI Bluetooth Device                                                                | 1         | 0.81%   |
| TP-Link UB500 Adapter                                                               | 1         | 0.81%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.81%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.81%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.81%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.81%   |
| MediaTek Wireless_Device                                                            | 1         | 0.81%   |
| Lite-On Wireless_Device                                                             | 1         | 0.81%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.81%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.81%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 1         | 0.81%   |
| IMC Networks Bluetooth Module                                                       | 1         | 0.81%   |
| IMC Networks Bluetooth Device                                                       | 1         | 0.81%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.81%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.81%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.81%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.81%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.81%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 114       | 60.96%  |
| AMD                    | 38        | 20.32%  |
| Nvidia                 | 21        | 11.23%  |
| Logitech               | 2         | 1.07%   |
| Lenovo                 | 2         | 1.07%   |
| ASUSTek Computer       | 2         | 1.07%   |
| Yamaha                 | 1         | 0.53%   |
| TX                     | 1         | 0.53%   |
| Realtek Semiconductor  | 1         | 0.53%   |
| Kingston Technology    | 1         | 0.53%   |
| Generalplus Technology | 1         | 0.53%   |
| Cambridge Audio        | 1         | 0.53%   |
| C-Media Electronics    | 1         | 0.53%   |
| Arturia                | 1         | 0.53%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 25        | 10.96%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 18        | 7.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 15        | 6.58%   |
| Intel Sunrise Point-LP HD Audio                                            | 11        | 4.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 4.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 3.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 3.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 3.07%   |
| Nvidia Audio device                                                        | 6         | 2.63%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 2.63%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 2.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 2.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.75%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.75%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 4         | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.75%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.75%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.75%   |
| Intel Raptor Lake High Definition Audio Controller                         | 3         | 1.32%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.32%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.32%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 1.32%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.88%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.88%   |
| Nvidia GA104 High Definition Audio Controller                              | 2         | 0.88%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.88%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.88%   |
| ASUSTek Computer C-Media Audio                                             | 2         | 0.88%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 2         | 0.88%   |
| Yamaha NX-U02                                                              | 1         | 0.44%   |
| TX USB Audio                                                               | 1         | 0.44%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.44%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.44%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.44%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 30.38%  |
| Micron Technology   | 18        | 22.78%  |
| SK hynix            | 14        | 17.72%  |
| Kingston            | 11        | 13.92%  |
| Smart               | 2         | 2.53%   |
| Elpida              | 2         | 2.53%   |
| Team                | 1         | 1.27%   |
| Silicon Power       | 1         | 1.27%   |
| Nanya Technology    | 1         | 1.27%   |
| GOODRAM             | 1         | 1.27%   |
| G.Skill             | 1         | 1.27%   |
| Corsair             | 1         | 1.27%   |
| A-DATA Technology   | 1         | 1.27%   |
| Unknown             | 1         | 1.27%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 5         | 5.88%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s       | 3         | 3.53%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s          | 2         | 2.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 2.35%   |
| Micron RAM 8KTF51264HZ-1G9P1 4GB SODIMM DDR3 1867MT/s          | 2         | 2.35%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s           | 2         | 2.35%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s          | 1         | 1.18%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s          | 1         | 1.18%   |
| Smart RAM SF4642G8CK8IEHLSBG 16GB SODIMM DDR4 2667MT/s         | 1         | 1.18%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.18%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 1.18%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s         | 1         | 1.18%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 1         | 1.18%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s   | 1         | 1.18%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s   | 1         | 1.18%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 1.18%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 1         | 1.18%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s        | 1         | 1.18%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 1         | 1.18%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 1         | 1.18%   |
| SK hynix RAM H58G78BK7BX114 8GB SODIMM LPDDR5 6400MT/s         | 1         | 1.18%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s    | 1         | 1.18%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 1.18%   |
| Samsung RAM Module 2GB Row Of Chips LPDDR5 6400MT/s            | 1         | 1.18%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                   | 1         | 1.18%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.18%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 1.18%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 1         | 1.18%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s          | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s    | 1         | 1.18%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 1.18%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s         | 1         | 1.18%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 1         | 1.18%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 1         | 1.18%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 1         | 1.18%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s          | 1         | 1.18%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 1         | 1.18%   |
| Samsung RAM M425R2GA3BB0-CWMOD 16GB SODIMM DDR5 5600MT/s       | 1         | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 41        | 61.19%  |
| DDR3   | 12        | 17.91%  |
| LPDDR5 | 5         | 7.46%   |
| DDR5   | 4         | 5.97%   |
| LPDDR4 | 2         | 2.99%   |
| SDRAM  | 1         | 1.49%   |
| LPDDR3 | 1         | 1.49%   |
| DDR2   | 1         | 1.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 58        | 85.29%  |
| Row Of Chips | 10        | 14.71%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 38        | 52.78%  |
| 4096  | 12        | 16.67%  |
| 16384 | 11        | 15.28%  |
| 2048  | 6         | 8.33%   |
| 32768 | 5         | 6.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 26        | 35.62%  |
| 2667  | 13        | 17.81%  |
| 1600  | 7         | 9.59%   |
| 6400  | 4         | 5.48%   |
| 2400  | 4         | 5.48%   |
| 5600  | 3         | 4.11%   |
| 2133  | 3         | 4.11%   |
| 1867  | 2         | 2.74%   |
| 1334  | 2         | 2.74%   |
| 1333  | 2         | 2.74%   |
| 7500  | 1         | 1.37%   |
| 4800  | 1         | 1.37%   |
| 4267  | 1         | 1.37%   |
| 3266  | 1         | 1.37%   |
| 2048  | 1         | 1.37%   |
| 1067  | 1         | 1.37%   |
| 975   | 1         | 1.37%   |

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
| Chicony Electronics                    | 31        | 24.6%   |
| IMC Networks                           | 13        | 10.32%  |
| Bison Electronics                      | 11        | 8.73%   |
| Quanta                                 | 8         | 6.35%   |
| Syntek                                 | 7         | 5.56%   |
| Microdia                               | 7         | 5.56%   |
| Suyin                                  | 6         | 4.76%   |
| Sunplus Innovation Technology          | 6         | 4.76%   |
| Realtek Semiconductor                  | 6         | 4.76%   |
| Luxvisions Innotech Limited            | 6         | 4.76%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.17%   |
| Primax Electronics                     | 3         | 2.38%   |
| Acer                                   | 3         | 2.38%   |
| Sonix Technology                       | 2         | 1.59%   |
| Z-Star Microelectronics                | 1         | 0.79%   |
| Sunplus Technology                     | 1         | 0.79%   |
| Samsung Electronics                    | 1         | 0.79%   |
| Ricoh                                  | 1         | 0.79%   |
| Microsoft                              | 1         | 0.79%   |
| Logitech                               | 1         | 0.79%   |
| Lite-On Technology                     | 1         | 0.79%   |
| Lenovo                                 | 1         | 0.79%   |
| Importek                               | 1         | 0.79%   |
| icSpring                               | 1         | 0.79%   |
| Generalplus Technology                 | 1         | 0.79%   |
| Apple                                  | 1         | 0.79%   |
| ALi                                    | 1         | 0.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 8         | 6.35%   |
| Syntek Integrated Camera                                    | 6         | 4.76%   |
| IMC Networks Integrated Camera                              | 5         | 3.97%   |
| Sunplus Integrated_Webcam_HD                                | 4         | 3.17%   |
| Microdia Integrated_Webcam_HD                               | 4         | 3.17%   |
| Bison BisonCam,NB Pro                                       | 4         | 3.17%   |
| Primax HP HD Webcam [Fixed]                                 | 3         | 2.38%   |
| Chicony USB2.0 Camera                                       | 3         | 2.38%   |
| Chicony HD User Facing                                      | 3         | 2.38%   |
| Realtek Integrated_Webcam_HD                                | 2         | 1.59%   |
| Quanta VGA WebCam                                           | 2         | 1.59%   |
| Quanta HP TrueVision HD Camera                              | 2         | 1.59%   |
| Quanta HD User Facing                                       | 2         | 1.59%   |
| Microdia Integrated Webcam                                  | 2         | 1.59%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera        | 2         | 1.59%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera         | 2         | 1.59%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 1.59%   |
| Chicony HP HD Camera                                        | 2         | 1.59%   |
| Chicony HD WebCam                                           | 2         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD     | 2         | 1.59%   |
| Bison Integrated Camera                                     | 2         | 1.59%   |
| Bison HD Webcam                                             | 2         | 1.59%   |
| Acer Lenovo Integrated Webcam                               | 2         | 1.59%   |
| Z-Star WebCam SC-03FFL11739P                                | 1         | 0.79%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.79%   |
| Suyin USB 2.0 UVC 1.3M WebCam                               | 1         | 0.79%   |
| Suyin Sony Visual Communication Camera                      | 1         | 0.79%   |
| Suyin Integrated Webcam                                     | 1         | 0.79%   |
| Suyin HP Truevision HD                                      | 1         | 0.79%   |
| Suyin HP ENVY HD Webcam                                     | 1         | 0.79%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.79%   |
| Sunplus 1.3M HD WebCam                                      | 1         | 0.79%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 0.79%   |
| Sunplus Laptop Integrated Webcam HD                         | 1         | 0.79%   |
| Sonix USB2.0 FHD UVC WebCam                                 | 1         | 0.79%   |
| Sonix Integrated Webcam_FHD                                 | 1         | 0.79%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 1         | 0.79%   |
| Ricoh HD Webcam                                             | 1         | 0.79%   |
| Realtek USB2.0 HD UVC WebCam                                | 1         | 0.79%   |
| Realtek USB Camera                                          | 1         | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 28.57%  |
| Synaptics                  | 5         | 23.81%  |
| Shenzhen Goodix Technology | 4         | 19.05%  |
| Upek                       | 3         | 14.29%  |
| AuthenTec                  | 2         | 9.52%   |
| Next Biometrics            | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 4         | 19.05%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device                    | 3         | 14.29%  |
| Validity Sensors Synaptics WBDI                        | 2         | 9.52%   |
| AuthenTec AES2810                                      | 2         | 9.52%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 4.76%   |
| Validity Sensors VFS491                                | 1         | 4.76%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 4.76%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 4.76%   |
| Synaptics UWP WBDI Device                              | 1         | 4.76%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 4.76%   |
| Next Biometrics NB-2020-U Fingerprint Reader           | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 53.33%  |
| Alcor Micro | 5         | 33.33%  |
| Upek        | 1         | 6.67%   |
| O2 Micro    | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 20%     |
| Broadcom 58200                                                               | 3         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 13.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 6.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 80        | 54.79%  |
| 1     | 50        | 34.25%  |
| 2     | 13        | 8.9%    |
| 3     | 3         | 2.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 21        | 24.71%  |
| Fingerprint reader    | 21        | 24.71%  |
| Chipcard              | 14        | 16.47%  |
| Net/wireless          | 9         | 10.59%  |
| Multimedia controller | 6         | 7.06%   |
| Sound                 | 5         | 5.88%   |
| Camera                | 4         | 4.71%   |
| Card reader           | 2         | 2.35%   |
| Network               | 1         | 1.18%   |
| Net/ethernet          | 1         | 1.18%   |
| Modem                 | 1         | 1.18%   |

